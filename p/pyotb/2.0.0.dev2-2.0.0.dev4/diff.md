# Comparing `tmp/pyotb-2.0.0.dev2.tar.gz` & `tmp/pyotb-2.0.0.dev4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pyotb-2.0.0.dev2.tar", last modified: Thu Jun  1 22:03:40 2023, max compression
+gzip compressed data, was "pyotb-2.0.0.dev4.tar", last modified: Wed Jun 28 14:40:17 2023, max compression
```

## Comparing `pyotb-2.0.0.dev2.tar` & `pyotb-2.0.0.dev4.tar`

### file list

```diff
@@ -1,24 +1,24 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-01 22:03:40.875204 pyotb-2.0.0.dev2/
--rw-rw-rw-   0 root         (0) root         (0)      257 2023-05-30 15:37:02.000000 pyotb-2.0.0.dev2/AUTHORS.md
--rw-rw-rw-   0 root         (0) root         (0)    11354 2023-05-24 08:56:53.000000 pyotb-2.0.0.dev2/LICENSE
--rw-r--r--   0 root         (0) root         (0)    16453 2023-06-01 22:03:40.875204 pyotb-2.0.0.dev2/PKG-INFO
--rw-rw-rw-   0 root         (0) root         (0)     2346 2023-05-31 07:58:34.000000 pyotb-2.0.0.dev2/README.md
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-01 22:03:40.871204 pyotb-2.0.0.dev2/pyotb/
--rw-rw-rw-   0 root         (0) root         (0)      424 2023-06-01 21:35:33.000000 pyotb-2.0.0.dev2/pyotb/__init__.py
--rw-rw-rw-   0 root         (0) root         (0)     5556 2023-06-01 18:37:22.000000 pyotb-2.0.0.dev2/pyotb/apps.py
--rw-rw-rw-   0 root         (0) root         (0)    66822 2023-06-01 18:37:22.000000 pyotb-2.0.0.dev2/pyotb/core.py
--rw-rw-rw-   0 root         (0) root         (0)    22175 2023-06-01 18:37:22.000000 pyotb-2.0.0.dev2/pyotb/functions.py
--rw-rw-rw-   0 root         (0) root         (0)    13150 2023-06-01 18:37:22.000000 pyotb-2.0.0.dev2/pyotb/helpers.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-01 22:03:40.875204 pyotb-2.0.0.dev2/pyotb.egg-info/
--rw-r--r--   0 root         (0) root         (0)    16453 2023-06-01 22:03:40.000000 pyotb-2.0.0.dev2/pyotb.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)      351 2023-06-01 22:03:40.000000 pyotb-2.0.0.dev2/pyotb.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-01 22:03:40.000000 pyotb-2.0.0.dev2/pyotb.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)       69 2023-06-01 22:03:40.000000 pyotb-2.0.0.dev2/pyotb.egg-info/requires.txt
--rw-r--r--   0 root         (0) root         (0)        6 2023-06-01 22:03:40.000000 pyotb-2.0.0.dev2/pyotb.egg-info/top_level.txt
--rw-rw-rw-   0 root         (0) root         (0)     1780 2023-06-01 18:37:22.000000 pyotb-2.0.0.dev2/pyproject.toml
--rw-r--r--   0 root         (0) root         (0)       38 2023-06-01 22:03:40.875204 pyotb-2.0.0.dev2/setup.cfg
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-01 22:03:40.875204 pyotb-2.0.0.dev2/tests/
--rw-rw-rw-   0 root         (0) root         (0)     9942 2023-05-31 10:05:29.000000 pyotb-2.0.0.dev2/tests/test_core.py
--rw-rw-rw-   0 root         (0) root         (0)     1769 2023-05-24 08:56:53.000000 pyotb-2.0.0.dev2/tests/test_numpy.py
--rw-rw-rw-   0 root         (0) root         (0)     3813 2023-05-24 08:56:53.000000 pyotb-2.0.0.dev2/tests/test_pipeline.py
--rw-rw-rw-   0 root         (0) root         (0)      811 2023-05-24 08:56:53.000000 pyotb-2.0.0.dev2/tests/tests_data.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:40:17.250671 pyotb-2.0.0.dev4/
+-rw-rw-rw-   0 root         (0) root         (0)      155 2023-06-27 16:38:00.000000 pyotb-2.0.0.dev4/AUTHORS.md
+-rw-rw-rw-   0 root         (0) root         (0)    11354 2023-06-26 17:31:47.000000 pyotb-2.0.0.dev4/LICENSE
+-rw-r--r--   0 root         (0) root         (0)     3482 2023-06-28 14:40:17.250671 pyotb-2.0.0.dev4/PKG-INFO
+-rw-rw-rw-   0 root         (0) root         (0)     2335 2023-06-26 17:31:47.000000 pyotb-2.0.0.dev4/README.md
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:40:17.246671 pyotb-2.0.0.dev4/pyotb/
+-rw-rw-rw-   0 root         (0) root         (0)      424 2023-06-28 14:33:16.000000 pyotb-2.0.0.dev4/pyotb/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)     5556 2023-06-26 17:31:47.000000 pyotb-2.0.0.dev4/pyotb/apps.py
+-rw-rw-rw-   0 root         (0) root         (0)    68852 2023-06-28 13:34:55.000000 pyotb-2.0.0.dev4/pyotb/core.py
+-rw-rw-rw-   0 root         (0) root         (0)    22175 2023-06-26 17:31:47.000000 pyotb-2.0.0.dev4/pyotb/functions.py
+-rw-rw-rw-   0 root         (0) root         (0)    13150 2023-06-26 17:31:47.000000 pyotb-2.0.0.dev4/pyotb/helpers.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:40:17.250671 pyotb-2.0.0.dev4/pyotb.egg-info/
+-rw-r--r--   0 root         (0) root         (0)     3482 2023-06-28 14:40:17.000000 pyotb-2.0.0.dev4/pyotb.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)      351 2023-06-28 14:40:17.000000 pyotb-2.0.0.dev4/pyotb.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 14:40:17.000000 pyotb-2.0.0.dev4/pyotb.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)       69 2023-06-28 14:40:17.000000 pyotb-2.0.0.dev4/pyotb.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)        6 2023-06-28 14:40:17.000000 pyotb-2.0.0.dev4/pyotb.egg-info/top_level.txt
+-rw-rw-rw-   0 root         (0) root         (0)     1761 2023-06-28 14:33:16.000000 pyotb-2.0.0.dev4/pyproject.toml
+-rw-r--r--   0 root         (0) root         (0)       38 2023-06-28 14:40:17.250671 pyotb-2.0.0.dev4/setup.cfg
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 14:40:17.250671 pyotb-2.0.0.dev4/tests/
+-rw-rw-rw-   0 root         (0) root         (0)    12432 2023-06-28 13:34:55.000000 pyotb-2.0.0.dev4/tests/test_core.py
+-rw-rw-rw-   0 root         (0) root         (0)     1769 2023-06-26 17:31:47.000000 pyotb-2.0.0.dev4/tests/test_numpy.py
+-rw-rw-rw-   0 root         (0) root         (0)     3813 2023-06-26 17:31:47.000000 pyotb-2.0.0.dev4/tests/test_pipeline.py
+-rw-rw-rw-   0 root         (0) root         (0)      811 2023-06-26 17:31:47.000000 pyotb-2.0.0.dev4/tests/tests_data.py
```

### Comparing `pyotb-2.0.0.dev2/LICENSE` & `pyotb-2.0.0.dev4/LICENSE`

 * *Files identical despite different names*

### Comparing `pyotb-2.0.0.dev2/README.md` & `pyotb-2.0.0.dev4/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -39,15 +39,15 @@
 ndvi = pyotb.BandMath(calib, exp="ndvi(im1b1, im1b4)")
 
 # Pythonic slicing using lazy computation (no memory used)
 roi = ndvi[20:586, 9:572]
 
 # Pipeline execution
 # The actual computation happens here !
-roi.write("output.tif", pixel_type="float")
+roi.write("output.tif", "float")
 ```
 
 pyotb's objects also enable easy interoperability with 
 [numpy](https://numpy.org/) and [rasterio](https://rasterio.readthedocs.io/):
 
 ```python
 # Numpy and RasterIO style attributes
```

### Comparing `pyotb-2.0.0.dev2/pyotb/apps.py` & `pyotb-2.0.0.dev4/pyotb/apps.py`

 * *Files identical despite different names*

### Comparing `pyotb-2.0.0.dev2/pyotb/core.py` & `pyotb-2.0.0.dev4/pyotb/core.py`

 * *Files 1% similar despite different names*

```diff
@@ -35,16 +35,50 @@
     @property
     @abstractmethod
     def exports_dic(self) -> dict[str, dict]:
         """Return an internal dict object containing np.array exports, to avoid duplicated ExportImage() calls."""
 
     @property
     def metadata(self) -> dict[str, (str, float, list[float])]:
-        """Return first output image metadata dictionary."""
-        return dict(self.app.GetMetadataDictionary(self.output_image_key))
+        """Return metadata.
+
+        The returned dict results from the concatenation of the first output
+        image metadata dictionary and the metadata dictionary.
+
+        """
+        # Image Metadata
+        otb_imd = self.app.GetImageMetadata(self.output_image_key)
+        cats = ["Num", "Str", "L1D", "Time"]
+        imd = {
+            key: getattr(otb_imd, f"get_{cat.lower()}")(key)
+            for cat in cats
+            for key in getattr(otb_imd, f"GetKeyList{cat}")().split(" ")
+            if getattr(otb_imd, "has")(key)
+        }
+
+        # Metadata dictionary
+        # Replace items like {"metadata_1": "TIFFTAG_SOFTWARE=CSinG - 13
+        # SEPTEMBRE 2012"} with {"TIFFTAG_SOFTWARE": "CSinG - 13 SEPTEMBRE
+        # 2012"}
+        mdd = dict(self.app.GetMetadataDictionary(self.output_image_key))
+        new_mdd = {}
+        for key, val in mdd.items():
+            new_key = key
+            new_val = val
+            if isinstance(val, str):
+                splits = val.split("=")
+                if key.lower().startswith("metadata_") and len(splits) == 2:
+                    new_key = splits[0].strip()
+                    new_val = splits[1].strip()
+            new_mdd[new_key] = new_val
+
+        return {
+            **new_mdd,
+            **imd
+        }
 
     @property
     def dtype(self) -> np.dtype:
         """Expose the pixel type of output image using numpy convention.
 
         Returns:
             dtype: pixel type of the output image
@@ -725,17 +759,17 @@
             self._time_start = perf_counter()
             self.app.ExecuteAndWriteOutput()
         self._time_end = perf_counter()
 
     def write(
         self,
         path: str | Path | dict[str, str] = None,
-        ext_fname: str = "",
         pixel_type: dict[str, str] | str = None,
         preserve_dtype: bool = False,
+        ext_fname: str = "",
         **kwargs,
     ) -> bool:
         """Set output pixel type and write the output raster files.
 
         Args:
             path: Can be : - filepath, useful when there is only one output, e.g. 'output.tif'
                            - dictionary containing key-arguments enumeration. Useful when a key contains
@@ -772,27 +806,45 @@
             raise KeyError(
                 f"{self.name}: at least one filepath is required, if not provided during App init"
             )
         parameters = kwargs.copy()
 
         # Append filename extension to filenames
         if ext_fname:
-            logger.debug(
-                "%s: using extended filename for outputs: %s", self.name, ext_fname
-            )
-            if not ext_fname.startswith("?"):
-                ext_fname = "?&" + ext_fname
-            elif not ext_fname.startswith("?&"):
-                ext_fname = "?&" + ext_fname[1:]
-            for key, value in kwargs.items():
-                if (
-                    self._out_param_types[key] == otb.ParameterType_OutputImage
-                    and "?" not in value
-                ):
-                    parameters[key] = value + ext_fname
+            if not isinstance(ext_fname, (dict, str)):
+                raise ValueError("Extended filename must be a str or a dict")
+            def _str2dict(ext_str):
+                """Function that converts str to dict."""
+                splits = [pair.split("=") for pair in ext_str.split("&")]
+                return dict(split for split in splits if len(split) == 2)
+
+            if isinstance(ext_fname, str):
+                ext_fname = _str2dict(ext_fname)
+
+            logger.debug("%s: extended filename for all outputs:", self.name)
+            for key, ext in ext_fname.items():
+                logger.debug("%s: %s", key, ext)
+
+            for key, filepath in kwargs.items():
+                if self._out_param_types[key] == otb.ParameterType_OutputImage:
+                    new_ext_fname = ext_fname.copy()
+
+                    # grab already set extended filename key/values
+                    if "?&" in filepath:
+                        filepath, already_set_ext = filepath.split("?&", 1)
+                        # extensions in filepath prevail over `new_ext_fname`
+                        new_ext_fname.update(_str2dict(already_set_ext))
+
+                    # transform dict to str
+                    ext_fname_str = "&".join([
+                        f"{key}={value}"
+                        for key, value in new_ext_fname.items()
+                    ])
+                    parameters[key] = f"{filepath}?&{ext_fname_str}"
+
         # Manage output pixel types
         data_types = {}
         if pixel_type:
             if isinstance(pixel_type, str):
                 dtype = parse_pixel_type(pixel_type)
                 type_name = self.app.ConvertPixelTypeToNumpy(dtype)
                 logger.debug(
```

### Comparing `pyotb-2.0.0.dev2/pyotb/functions.py` & `pyotb-2.0.0.dev4/pyotb/functions.py`

 * *Files identical despite different names*

### Comparing `pyotb-2.0.0.dev2/pyotb/helpers.py` & `pyotb-2.0.0.dev4/pyotb/helpers.py`

 * *Files identical despite different names*

### Comparing `pyotb-2.0.0.dev2/pyproject.toml` & `pyotb-2.0.0.dev4/pyproject.toml`

 * *Files 6% similar despite different names*

```diff
@@ -2,23 +2,23 @@
 requires = ["setuptools >= 61.0", "wheel"]
 build-backend = "setuptools.build_meta"
 
 [project]
 name = "pyotb"
 description = "Library to enable easy use of the Orfeo ToolBox (OTB) in Python"
 authors = [
-    { name = "Rémi Cresson", email = "remi.cresson@inrae.fr" },
-    { name = "Nicolas Narçon" },
-    { name = "Vincent Delbar" },
+    {name="Rémi Cresson", email="remi.cresson@inrae.fr"},
+    {name="Nicolas Narçon"},
+    {name="Vincent Delbar"},
 ]
 requires-python = ">=3.7"
 keywords = ["gis", "remote sensing", "otb", "orfeotoolbox", "orfeo toolbox"]
 dependencies = ["numpy>=1.16"]
 readme = "README.md"
-license = { file = "LICENSE" }
+license = {text="Apache-2.0"}
 dynamic = ["version"]
 classifiers = [
     "Programming Language :: Python :: 3",
     "Programming Language :: Python :: 3.7",
     "Programming Language :: Python :: 3.8",
     "Programming Language :: Python :: 3.9",
     "Programming Language :: Python :: 3.10",
@@ -37,15 +37,15 @@
 homepage = "https://github.com/orfeotoolbox/pyotb"
 repository = "https://gitlab.orfeo-toolbox.org/nicolasnn/pyotb"
 
 [tool.setuptools]
 packages = ["pyotb"]
 
 [tool.setuptools.dynamic]
-version = { attr = "pyotb.__version__" }
+version = {attr="pyotb.__version__"}
 
 [tool.pylint]
 max-line-length = 88
 max-module-lines = 2000
 good-names = ["x", "y", "i", "j", "k", "e"]
 disable = [
     "fixme",
```

### Comparing `pyotb-2.0.0.dev2/tests/test_core.py` & `pyotb-2.0.0.dev4/tests/test_core.py`

 * *Files 19% similar despite different names*

```diff
@@ -1,10 +1,9 @@
 import pytest
 
-import pyotb
 from tests_data import *
 
 
 # Input settings
 def test_parameters():
     assert INPUT.parameters
     assert INPUT.parameters["in"] == FILEPATH
@@ -74,15 +73,26 @@
 
 
 def test_data():
     assert pyotb.ComputeImagesStatistics(INPUT).data == TEST_IMAGE_STATS
 
 
 def test_metadata():
-    assert INPUT.metadata["Metadata_1"] == "TIFFTAG_SOFTWARE=CSinG - 13 SEPTEMBRE 2012"
+    INPUT2 = pyotb.Input(
+        "https://sentinel-cogs.s3.us-west-2.amazonaws.com/sentinel-s2-l2a-cogs/"
+        "47/Q/RU/2021/12/S2B_47QRU_20211227_0_L2A/B04.tif"
+    )
+    assert "ProjectionRef", "TIFFTAG_SOFTWARE" in INPUT.metadata
+    assert "ProjectionRef", "OVR_RESAMPLING_ALG" in INPUT2.metadata
+
+    # Metadata with numeric values (e.g. TileHintX)
+    fp = "https://gitlab.orfeo-toolbox.org/orfeotoolbox/otb/-/raw/develop/" \
+         "Data/Input/radarsat2/RADARSAT2_ALTONA_300_300_VV.tif?inline=false"
+    app = pyotb.BandMath({"il": [fp], "exp": "im1b1"})
+    assert "TileHintX" in app.metadata
 
 
 def test_nonraster_property():
     with pytest.raises(TypeError):
         assert pyotb.ReadImageInfo(INPUT).dtype == "uint8"
 
 
@@ -107,14 +117,76 @@
 
 
 def test_write():
     assert INPUT.write("/tmp/test_write.tif", ext_fname="nodata=0")
     INPUT["out"].filepath.unlink()
 
 
+def test_ext_fname():
+    def _check(expected: str, key: str = "out", app = INPUT.app):
+        fn = app.GetParameterString(key)
+        assert "?&" in fn
+        assert fn.split("?&", 1)[1] == expected
+
+    assert INPUT.write("/tmp/test_write.tif", ext_fname="nodata=0")
+    _check("nodata=0")
+    assert INPUT.write("/tmp/test_write.tif", ext_fname={"nodata": "0"})
+    _check("nodata=0")
+    assert INPUT.write("/tmp/test_write.tif", ext_fname={"nodata": 0})
+    _check("nodata=0")
+    assert INPUT.write(
+        "/tmp/test_write.tif",
+        ext_fname={
+            "nodata": 0,
+            "gdal:co:COMPRESS": "DEFLATE"
+        }
+    )
+    _check("nodata=0&gdal:co:COMPRESS=DEFLATE")
+    assert INPUT.write(
+        "/tmp/test_write.tif",
+        ext_fname="nodata=0&gdal:co:COMPRESS=DEFLATE"
+    )
+    _check("nodata=0&gdal:co:COMPRESS=DEFLATE")
+    assert INPUT.write(
+        "/tmp/test_write.tif?&box=0:0:10:10",
+        ext_fname={
+            "nodata": "0",
+            "gdal:co:COMPRESS": "DEFLATE",
+            "box": "0:0:20:20"
+        }
+    )
+    # Check that the bbox is the one specified in the filepath, not the one
+    # specified in `ext_filename`
+    _check("nodata=0&gdal:co:COMPRESS=DEFLATE&box=0:0:10:10")
+    assert INPUT.write(
+        "/tmp/test_write.tif?&box=0:0:10:10",
+        ext_fname="nodata=0&gdal:co:COMPRESS=DEFLATE&box=0:0:20:20"
+    )
+    _check("nodata=0&gdal:co:COMPRESS=DEFLATE&box=0:0:10:10")
+
+    INPUT["out"].filepath.unlink()
+
+    mss = pyotb.MeanShiftSmoothing(FILEPATH)
+    mss.write(
+        {
+            "fout": "/tmp/test_ext_fn_fout.tif?&nodata=1",
+            "foutpos": "/tmp/test_ext_fn_foutpos.tif?&nodata=2"
+        },
+        ext_fname={
+            "nodata": 0,
+            "gdal:co:COMPRESS": "DEFLATE"
+        }
+    )
+    _check("nodata=1&gdal:co:COMPRESS=DEFLATE", key="fout", app=mss.app)
+    _check("nodata=2&gdal:co:COMPRESS=DEFLATE", key="foutpos", app=mss.app)
+    mss["fout"].filepath.unlink()
+    mss["foutpos"].filepath.unlink()
+
+
+
 def test_frozen_app_write():
     app = pyotb.BandMath(INPUT, exp="im1b1", frozen=True)
     assert app.write("/tmp/test_frozen_app_write.tif")
     app["out"].filepath.unlink()
 
     app = pyotb.BandMath(INPUT, exp="im1b1", out="/tmp/test_frozen_app_write.tif", frozen=True)
     assert app.write()
@@ -242,16 +314,16 @@
 
 
 # BandMath NDVI == RadiometricIndices NDVI ?
 def test_ndvi_comparison():
     ndvi_bandmath = (INPUT[:, :, -1] - INPUT[:, :, [0]]) / (INPUT[:, :, -1] + INPUT[:, :, 0])
     ndvi_indices = pyotb.RadiometricIndices(INPUT, {"list": ["Vegetation:NDVI"], "channels.red": 1, "channels.nir": 4})
     assert ndvi_bandmath.exp == "((im1b4 - im1b1) / (im1b4 + im1b1))"
-    assert ndvi_bandmath.write("/tmp/ndvi_bandmath.tif", pixel_type="float")
-    assert ndvi_indices.write("/tmp/ndvi_indices.tif", pixel_type="float")
+    assert ndvi_bandmath.write("/tmp/ndvi_bandmath.tif", "float")
+    assert ndvi_indices.write("/tmp/ndvi_indices.tif", "float")
 
     compared = pyotb.CompareImages({"ref.in": ndvi_indices, "meas.in": "/tmp/ndvi_bandmath.tif"})
     assert (compared["count"], compared["mse"]) == (0, 0)
     thresholded_indices = pyotb.where(ndvi_indices >= 0.3, 1, 0)
     assert thresholded_indices["exp"] == "((im1b1 >= 0.3) ? 1 : 0)"
     thresholded_bandmath = pyotb.where(ndvi_bandmath >= 0.3, 1, 0)
     assert thresholded_bandmath["exp"] == "((((im1b4 - im1b1) / (im1b4 + im1b1)) >= 0.3) ? 1 : 0)"
```

### Comparing `pyotb-2.0.0.dev2/tests/test_numpy.py` & `pyotb-2.0.0.dev4/tests/test_numpy.py`

 * *Files identical despite different names*

### Comparing `pyotb-2.0.0.dev2/tests/test_pipeline.py` & `pyotb-2.0.0.dev4/tests/test_pipeline.py`

 * *Files identical despite different names*

### Comparing `pyotb-2.0.0.dev2/tests/tests_data.py` & `pyotb-2.0.0.dev4/tests/tests_data.py`

 * *Files identical despite different names*

