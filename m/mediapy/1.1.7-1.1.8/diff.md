# Comparing `tmp/mediapy-1.1.7.tar.gz` & `tmp/mediapy-1.1.8.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "mediapy-1.1.7.tar", last modified: Fri Jan  1 00:00:00 2016, max compression
+gzip compressed data, was "mediapy-1.1.8.tar", last modified: Fri Jan  1 00:00:00 2016, max compression
```

## Comparing `mediapy-1.1.7.tar` & `mediapy-1.1.8.tar`

### file list

```diff
@@ -1,6 +1,6 @@
--rw-r--r--   0        0        0    11358 2023-06-26 18:02:57.144394 mediapy-1.1.7/LICENSE
--rw-r--r--   0        0        0     3738 2023-06-26 18:02:57.144394 mediapy-1.1.7/README.md
--rw-r--r--   0        0        0    65830 2023-06-26 18:02:57.144394 mediapy-1.1.7/mediapy/__init__.py
--rw-r--r--   0        0        0        0 2023-06-26 18:02:57.144394 mediapy-1.1.7/mediapy/py.typed
--rw-r--r--   0        0        0     2243 2023-06-26 18:02:57.152394 mediapy-1.1.7/pyproject.toml
--rw-r--r--   0        0        0     4751 1970-01-01 00:00:00.000000 mediapy-1.1.7/PKG-INFO
+-rw-r--r--   0        0        0    11358 2023-06-28 10:26:55.361774 mediapy-1.1.8/LICENSE
+-rw-r--r--   0        0        0     3738 2023-06-28 10:26:55.361774 mediapy-1.1.8/README.md
+-rw-r--r--   0        0        0    68015 2023-06-28 10:26:55.361774 mediapy-1.1.8/mediapy/__init__.py
+-rw-r--r--   0        0        0        0 2023-06-28 10:26:55.361774 mediapy-1.1.8/mediapy/py.typed
+-rw-r--r--   0        0        0     2243 2023-06-28 10:26:55.373774 mediapy-1.1.8/pyproject.toml
+-rw-r--r--   0        0        0     4751 1970-01-01 00:00:00.000000 mediapy-1.1.8/PKG-INFO
```

### Comparing `mediapy-1.1.7/LICENSE` & `mediapy-1.1.8/LICENSE`

 * *Files identical despite different names*

### Comparing `mediapy-1.1.7/README.md` & `mediapy-1.1.8/README.md`

 * *Files identical despite different names*

### Comparing `mediapy-1.1.7/mediapy/__init__.py` & `mediapy-1.1.8/mediapy/__init__.py`

 * *Files 3% similar despite different names*

```diff
@@ -51,14 +51,19 @@
     'original': checkerboard,
     'darkened': checkerboard * 0.7,
     'random': np.random.rand(32, 32, 3),
 }
 show_images(images, vmin=0.0, vmax=1.0, border=True, height=64)
 ```
 
+Compare two images using an interactive slider:
+```python
+compare_images([checkerboard, np.random.rand(128, 128, 3)])
+```
+
 ## Video examples
 
 Display a video (an iterable of images, e.g., a 3D or 4D array):
 ```python
 video = moving_circle((100, 100), num_images=10)
 show_video(video, fps=10)
 ```
@@ -95,15 +100,15 @@
       w.add_image(darken_image(image))
 ```
 """
 
 from __future__ import annotations
 
 __docformat__ = 'google'
-__version__ = '1.1.7'
+__version__ = '1.1.8'
 __version_info__ = tuple(int(num) for num in __version__.split('.'))
 
 import base64
 from collections.abc import Callable, Iterable, Iterator, Mapping, Sequence
 import contextlib
 import functools
 import importlib
@@ -133,14 +138,15 @@
 if not hasattr(PIL.Image, 'Resampling'):  # Allow Pillow<9.0.
   PIL.Image.Resampling = PIL.Image
 
 # Selected and reordered here for pdoc documentation.
 __all__ = [
     'show_image',
     'show_images',
+    'compare_images',
     'show_video',
     'show_videos',
     'read_image',
     'write_image',
     'read_video',
     'write_video',
     'VideoReader',
@@ -179,14 +185,30 @@
   _NDArray = typing.TypeVar('_NDArray')
   _DType = typing.TypeVar('_DType')  # pylint: disable=invalid-name
 
 _IPYTHON_HTML_SIZE_LIMIT = 20_000_000
 _T = typing.TypeVar('_T')
 _Path = typing.Union[str, os.PathLike]
 
+_IMAGE_COMPARISON_HTML = """\
+<script
+  defer
+  src="https://unpkg.com/img-comparison-slider@7/dist/index.js"
+></script>
+<link
+  rel="stylesheet"
+  href="https://unpkg.com/img-comparison-slider@7/dist/styles.css"
+/>
+
+<img-comparison-slider>
+  <img slot="first" src="data:image/png;base64,{b64_1}" />
+  <img slot="second" src="data:image/png;base64,{b64_2}" />
+</img-comparison-slider>
+"""
+
 # ** Miscellaneous.
 
 
 class _Config:
   ffmpeg_name_or_path: _Path = 'ffmpeg'
   show_save_dir: _Path | None = None
 
@@ -918,14 +940,35 @@
   if width and not height:
     return width, int(width * (shape[0] / shape[1]) + 0.5)
   if height and not width:
     return int(height * (shape[1] / shape[0]) + 0.5), height
   return shape[::-1]
 
 
+def _ensure_mapped_to_rgb(
+    image: _ArrayLike,
+    *,
+    vmin: float | None = None,
+    vmax: float | None = None,
+    cmap: str | Callable[[_ArrayLike], _NDArray] = 'gray',
+) -> _NDArray:
+  """Ensure image is mapped to RGB."""
+  image = _as_valid_media_array(image)
+  if not (image.ndim == 2 or (image.ndim == 3 and image.shape[2] in (1, 3, 4))):
+    raise ValueError(
+        f'Image with shape {image.shape} is neither a 2D array'
+        ' nor a 3D array with 1, 3, or 4 channels.'
+    )
+  if image.ndim == 3 and image.shape[2] == 1:
+    image = image[:, :, 0]
+  if image.ndim == 2:
+    image = to_rgb(image, vmin=vmin, vmax=vmax, cmap=cmap)
+  return image
+
+
 def show_image(
     image: _ArrayLike, *, title: str | None = None, **kwargs: Any
 ) -> str | None:
   """Displays an image in the notebook and optionally saves it to a file.
 
   See `show_images`.
 
@@ -1009,30 +1052,18 @@
     list_titles = [None] * len(list_images) if titles is None else list(titles)
     if len(list_images) != len(list_titles):
       raise ValueError(
           'Number of images does not match number of titles'
           f' ({len(list_images)} vs {len(list_titles)}).'
       )
 
-  def ensure_mapped_to_rgb(image: _ArrayLike) -> _NDArray:
-    image = _as_valid_media_array(image)
-    if not (
-        image.ndim == 2 or (image.ndim == 3 and image.shape[2] in (1, 3, 4))
-    ):
-      raise ValueError(
-          f'Image with shape {image.shape} is neither a 2D array'
-          ' nor a 3D array with 1, 3, or 4 channels.'
-      )
-    if image.ndim == 3 and image.shape[2] == 1:
-      image = image[:, :, 0]
-    if image.ndim == 2:
-      image = to_rgb(image, vmin=vmin, vmax=vmax, cmap=cmap)
-    return image
-
-  list_images = [ensure_mapped_to_rgb(image) for image in list_images]
+  list_images = [
+      _ensure_mapped_to_rgb(image, vmin=vmin, vmax=vmax, cmap=cmap)
+      for image in list_images
+  ]
 
   def maybe_downsample(image: _NDArray) -> _NDArray:
     shape: tuple[int, int] = image.shape[:2]  # type: ignore[assignment]
     w, h = _get_width_height(width, height, shape)
     if w < shape[1] or h < shape[0]:
       image = resize_image(image, (h, w))
     return image
@@ -1079,14 +1110,52 @@
     s = html_from_compressed_images()
   if return_html:
     return s
   _display_html(s)
   return None
 
 
+def compare_images(
+    images: Iterable[_ArrayLike],
+    *,
+    vmin: float | None = None,
+    vmax: float | None = None,
+    cmap: str | Callable[[_ArrayLike], _NDArray] = 'gray',
+) -> None:
+  """Compare two images using an interactive slider.
+
+  Displays an HTML slider component to interactively swipe between two images.
+  The slider functionality requires that the web browser have Internet access.
+  See additional info in `https://github.com/sneas/img-comparison-slider`.
+
+  >>> image1, image2 = np.random.rand(64, 64, 3), color_ramp((64, 64))
+  >>> compare_images([image1, image2])
+
+  Args:
+    images: Iterable of images.  Each image must be either a 2D array or a 3D
+      array with 1, 3, or 4 channels.  There must be exactly two images.
+    vmin: For single-channel image, explicit min value for display.
+    vmax: For single-channel image, explicit max value for display.
+    cmap: For single-channel image, `pyplot` color map or callable to map 1D to
+      3D color.
+  """
+  list_images = [
+      _ensure_mapped_to_rgb(image, vmin=vmin, vmax=vmax, cmap=cmap)
+      for image in images
+  ]
+  if len(list_images) != 2:
+    raise ValueError('The number of images must be 2.')
+  png_datas = [compress_image(to_uint8(image)) for image in list_images]
+  b64_1, b64_2 = [
+      base64.b64encode(png_data).decode('utf-8') for png_data in png_datas
+  ]
+  s = _IMAGE_COMPARISON_HTML.replace('{b64_1}', b64_1).replace('{b64_2}', b64_2)
+  _display_html(s)
+
+
 # ** Video I/O.
 
 
 def _filename_suffix_from_codec(codec: str) -> str:
   return '.gif' if codec == 'gif' else '.mp4'
```

### Comparing `mediapy-1.1.7/pyproject.toml` & `mediapy-1.1.8/pyproject.toml`

 * *Files identical despite different names*

### Comparing `mediapy-1.1.7/PKG-INFO` & `mediapy-1.1.8/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: mediapy
-Version: 1.1.7
+Version: 1.1.8
 Summary: Read/write/show images and videos in an IPython notebook
 Keywords: 
 Author-email: Google LLC <mediapy-owners@google.com>
 Requires-Python: >=3.8
 Description-Content-Type: text/markdown
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: Apache Software License
```

