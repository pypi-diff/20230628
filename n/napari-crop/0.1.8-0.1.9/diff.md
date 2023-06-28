# Comparing `tmp/napari-crop-0.1.8.tar.gz` & `tmp/napari-crop-0.1.9.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "napari-crop-0.1.8.tar", last modified: Tue Jun 27 15:17:14 2023, max compression
+gzip compressed data, was "napari-crop-0.1.9.tar", last modified: Wed Jun 28 13:57:42 2023, max compression
```

## Comparing `napari-crop-0.1.8.tar` & `napari-crop-0.1.9.tar`

### file list

```diff
@@ -1,26 +1,24 @@
-drwxrwxrwx   0        0        0        0 2023-06-27 15:17:14.584505 napari-crop-0.1.8/
--rw-rw-rw-   0        0        0     1623 2022-02-07 14:47:59.000000 napari-crop-0.1.8/LICENSE
--rw-rw-rw-   0        0        0      127 2022-02-07 14:47:59.000000 napari-crop-0.1.8/MANIFEST.in
--rw-rw-rw-   0        0        0     4789 2023-06-27 15:17:14.585509 napari-crop-0.1.8/PKG-INFO
--rw-rw-rw-   0        0        0     3517 2023-06-27 08:24:08.000000 napari-crop-0.1.8/README.md
-drwxrwxrwx   0        0        0        0 2023-06-27 15:17:14.503694 napari-crop-0.1.8/napari_crop/
--rw-rw-rw-   0        0        0      149 2023-06-26 07:09:46.000000 napari-crop-0.1.8/napari_crop/__init__.py
--rw-rw-rw-   0        0        0    10604 2023-06-27 14:52:20.000000 napari-crop-0.1.8/napari_crop/_dock_widgets.py
--rw-rw-rw-   0        0        0     7906 2023-06-27 07:10:02.000000 napari-crop-0.1.8/napari_crop/_function.py
-drwxrwxrwx   0        0        0        0 2023-06-27 15:17:14.581503 napari-crop-0.1.8/napari_crop/_tests/
--rw-rw-rw-   0        0        0        0 2022-02-07 14:47:59.000000 napari-crop-0.1.8/napari_crop/_tests/__init__.py
--rw-rw-rw-   0        0        0     8475 2023-06-26 14:56:20.000000 napari-crop-0.1.8/napari_crop/_tests/test_function.py
--rw-rw-rw-   0        0        0      917 2023-06-23 14:29:47.000000 napari-crop-0.1.8/napari_crop/_tests/test_widget.py
--rw-rw-rw-   0        0        0     1272 2023-06-27 06:45:09.000000 napari-crop-0.1.8/napari_crop/_utils.py
--rw-rw-rw-   0        0        0      610 2023-06-27 06:58:54.000000 napari-crop-0.1.8/napari_crop/bla.py
--rw-rw-rw-   0        0        0      541 2023-06-27 07:28:49.000000 napari-crop-0.1.8/napari_crop/try_cut_plane.py
-drwxrwxrwx   0        0        0        0 2023-06-27 15:17:14.551892 napari-crop-0.1.8/napari_crop.egg-info/
--rw-rw-rw-   0        0        0     4789 2023-06-27 15:17:14.000000 napari-crop-0.1.8/napari_crop.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      526 2023-06-27 15:17:14.000000 napari-crop-0.1.8/napari_crop.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-27 15:17:14.000000 napari-crop-0.1.8/napari_crop.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       42 2023-06-27 15:17:14.000000 napari-crop-0.1.8/napari_crop.egg-info/entry_points.txt
--rw-rw-rw-   0        0        0       90 2023-06-27 15:17:14.000000 napari-crop-0.1.8/napari_crop.egg-info/requires.txt
--rw-rw-rw-   0        0        0       12 2023-06-27 15:17:14.000000 napari-crop-0.1.8/napari_crop.egg-info/top_level.txt
--rw-rw-rw-   0        0        0      198 2022-02-07 14:47:59.000000 napari-crop-0.1.8/requirements.txt
--rw-rw-rw-   0        0        0     1409 2023-06-27 15:17:14.593052 napari-crop-0.1.8/setup.cfg
--rw-rw-rw-   0        0        0       89 2022-02-07 14:47:59.000000 napari-crop-0.1.8/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:57:42.879087 napari-crop-0.1.9/
+-rw-rw-rw-   0        0        0     1623 2022-02-07 14:47:59.000000 napari-crop-0.1.9/LICENSE
+-rw-rw-rw-   0        0        0      127 2022-02-07 14:47:59.000000 napari-crop-0.1.9/MANIFEST.in
+-rw-rw-rw-   0        0        0     4645 2023-06-28 13:57:42.880061 napari-crop-0.1.9/PKG-INFO
+-rw-rw-rw-   0        0        0     3424 2023-06-28 13:21:37.000000 napari-crop-0.1.9/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 13:57:42.781634 napari-crop-0.1.9/napari_crop/
+-rw-rw-rw-   0        0        0      149 2023-06-28 13:23:27.000000 napari-crop-0.1.9/napari_crop/__init__.py
+-rw-rw-rw-   0        0        0    10604 2023-06-28 13:21:37.000000 napari-crop-0.1.9/napari_crop/_dock_widgets.py
+-rw-rw-rw-   0        0        0     7906 2023-06-28 13:21:37.000000 napari-crop-0.1.9/napari_crop/_function.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:57:42.875045 napari-crop-0.1.9/napari_crop/_tests/
+-rw-rw-rw-   0        0        0        0 2022-02-07 14:47:59.000000 napari-crop-0.1.9/napari_crop/_tests/__init__.py
+-rw-rw-rw-   0        0        0     8475 2023-06-28 13:21:37.000000 napari-crop-0.1.9/napari_crop/_tests/test_function.py
+-rw-rw-rw-   0        0        0      917 2023-06-28 13:21:37.000000 napari-crop-0.1.9/napari_crop/_tests/test_widget.py
+-rw-rw-rw-   0        0        0     1272 2023-06-28 13:21:37.000000 napari-crop-0.1.9/napari_crop/_utils.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:57:42.846361 napari-crop-0.1.9/napari_crop.egg-info/
+-rw-rw-rw-   0        0        0     4645 2023-06-28 13:57:42.000000 napari-crop-0.1.9/napari_crop.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      478 2023-06-28 13:57:42.000000 napari-crop-0.1.9/napari_crop.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 13:57:42.000000 napari-crop-0.1.9/napari_crop.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       42 2023-06-28 13:57:42.000000 napari-crop-0.1.9/napari_crop.egg-info/entry_points.txt
+-rw-rw-rw-   0        0        0       90 2023-06-28 13:57:42.000000 napari-crop-0.1.9/napari_crop.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       12 2023-06-28 13:57:42.000000 napari-crop-0.1.9/napari_crop.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0      198 2022-02-07 14:47:59.000000 napari-crop-0.1.9/requirements.txt
+-rw-rw-rw-   0        0        0     1369 2023-06-28 13:57:42.891072 napari-crop-0.1.9/setup.cfg
+-rw-rw-rw-   0        0        0       89 2022-02-07 14:47:59.000000 napari-crop-0.1.9/setup.py
```

### Comparing `napari-crop-0.1.8/LICENSE` & `napari-crop-0.1.9/LICENSE`

 * *Files identical despite different names*

### Comparing `napari-crop-0.1.8/PKG-INFO` & `napari-crop-0.1.9/PKG-INFO`

 * *Files 17% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: napari-crop
-Version: 0.1.8
+Version: 0.1.9
 Summary: Crop regions in napari manually
 Home-page: https://github.com/biapol/napari-crop
 Author: Robert Haase, Tim Morello, Marcelo Leomil Zoccoler, Johannes Muller
 Author-email: robert.haase@tu-dresden.de
 License: BSD-3-Clause
 Project-URL: Bug Tracker, https://github.com/biapol/napari-crop/issues
 Project-URL: Documentation, https://github.com/biapol/napari-crop#README.md
@@ -13,63 +13,62 @@
 Classifier: Development Status :: 3 - Alpha
 Classifier: Intended Audience :: Developers
 Classifier: Framework :: napari
 Classifier: Topic :: Scientific/Engineering :: Image Processing
 Classifier: Topic :: Scientific/Engineering :: Information Analysis
 Classifier: Programming Language :: Python
 Classifier: Programming Language :: Python :: 3
-Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Operating System :: OS Independent
 Classifier: License :: OSI Approved :: BSD License
-Requires-Python: >=3.7
+Requires-Python: >=3.8
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 # napari-crop
 
-[![License](https://img.shields.io/pypi/l/napari-crop.svg?color=green)](https://github.com/haesleinhuepf/napari-crop/raw/master/LICENSE)
+[![License](https://img.shields.io/pypi/l/napari-crop.svg?color=green)](https://github.com/BiAPoL/napari-crop/raw/master/LICENSE)
 [![PyPI](https://img.shields.io/pypi/v/napari-crop.svg?color=green)](https://pypi.org/project/napari-crop)
 [![Python Version](https://img.shields.io/pypi/pyversions/napari-crop.svg?color=green)](https://python.org)
-[![tests](https://github.com/haesleinhuepf/napari-crop/workflows/tests/badge.svg)](https://github.com/haesleinhuepf/napari-crop/actions)
-[![codecov](https://codecov.io/gh/haesleinhuepf/napari-crop/branch/master/graph/badge.svg)](https://codecov.io/gh/haesleinhuepf/napari-crop)
+[![tests](https://github.com/BiAPoL/napari-crop/workflows/tests/badge.svg)](https://github.com/BiAPoL/napari-crop/actions)
+[![codecov](https://codecov.io/gh/BiAPoL/napari-crop/branch/main/graph/badge.svg)](https://codecov.io/gh/BiAPoL/napari-crop)
 [![DOI](https://zenodo.org/badge/419822240.svg)](https://zenodo.org/badge/latestdoi/419822240)
 
 Crop regions in napari manually
 
-![](https://github.com/haesleinhuepf/napari-crop/raw/main/images/screencast.gif)
+![](https://github.com/BiAPoL/napari-crop/raw/main/images/screencast.gif)
 
 Crop in any dimension
 
-![](https://github.com/haesleinhuepf/napari-crop/raw/main/images/side_crop.gif)
+![](https://github.com/BiAPoL/napari-crop/raw/main/images/side_crop.gif)
 
 Cut a volume using a plane
 
 *Note: this functionality currently only works with 3D data*
 
-![](https://github.com/haesleinhuepf/napari-crop/raw/main/images/napari_crop_cut_with_plane_demo.gif)
+![](https://github.com/BiAPoL/napari-crop/raw/main/images/napari_crop_cut_with_plane_demo.gif)
 
 ## Usage
 Create a new shapes layer to annotate the region you would like to crop:
 
-![](https://github.com/haesleinhuepf/napari-crop/raw/main/images/shapes.png)
+![](https://github.com/BiAPoL/napari-crop/raw/main/images/shapes.png)
 
 Use the rectangle tool to annotate a region. Start the `crop` tool from the `Tools > Utilities > Crop region` menu. 
 Click the `Run` button to crop the region.
 
-![](https://github.com/haesleinhuepf/napari-crop/raw/main/images/draw_rectangle.png)
+![](https://github.com/BiAPoL/napari-crop/raw/main/images/draw_rectangle.png)
 
 You can also use the `Select shapes` tool to move the rectangle to a new place and crop another region by clicking on `Run`.
 
-![](https://github.com/haesleinhuepf/napari-crop/raw/main/images/move_rectangle.png)
+![](https://github.com/BiAPoL/napari-crop/raw/main/images/move_rectangle.png)
 
 Hint: You can also use the [napari-tabu](https://www.napari-hub.org/plugins/napari-tabu) plugin to send all your cropped images to a new napari window.
 
-![](https://github.com/haesleinhuepf/napari-crop/raw/main/images/new_window.gif)
+![](https://github.com/BiAPoL/napari-crop/raw/main/images/new_window.gif)
 
 ----------------------------------
 
 This [napari] plugin was generated with [Cookiecutter] using with [@napari]'s [cookiecutter-napari-plugin] template.
 
 ## Installation
 
@@ -96,15 +95,15 @@
 [MIT]: http://opensource.org/licenses/MIT
 [BSD-3]: http://opensource.org/licenses/BSD-3-Clause
 [GNU GPL v3.0]: http://www.gnu.org/licenses/gpl-3.0.txt
 [GNU LGPL v3.0]: http://www.gnu.org/licenses/lgpl-3.0.txt
 [Apache Software License 2.0]: http://www.apache.org/licenses/LICENSE-2.0
 [Mozilla Public License 2.0]: https://www.mozilla.org/media/MPL/2.0/index.txt
 [cookiecutter-napari-plugin]: https://github.com/napari/cookiecutter-napari-plugin
-[file an issue]: https://github.com/haesleinhuepf/napari-crop/issues
+[file an issue]: https://github.com/BiAPoL/napari-crop/issues
 [napari]: https://github.com/napari/napari
 [tox]: https://tox.readthedocs.io/en/latest/
 [pip]: https://pypi.org/project/pip/
 [PyPI]: https://pypi.org/
 [image.sc]: https://image.sc
 [@haesleinhuepf]: https://twitter.com/haesleinhuepf
```

### Comparing `napari-crop-0.1.8/README.md` & `napari-crop-0.1.9/README.md`

 * *Files 23% similar despite different names*

```diff
@@ -1,47 +1,47 @@
 # napari-crop
 
-[![License](https://img.shields.io/pypi/l/napari-crop.svg?color=green)](https://github.com/haesleinhuepf/napari-crop/raw/master/LICENSE)
+[![License](https://img.shields.io/pypi/l/napari-crop.svg?color=green)](https://github.com/BiAPoL/napari-crop/raw/master/LICENSE)
 [![PyPI](https://img.shields.io/pypi/v/napari-crop.svg?color=green)](https://pypi.org/project/napari-crop)
 [![Python Version](https://img.shields.io/pypi/pyversions/napari-crop.svg?color=green)](https://python.org)
-[![tests](https://github.com/haesleinhuepf/napari-crop/workflows/tests/badge.svg)](https://github.com/haesleinhuepf/napari-crop/actions)
-[![codecov](https://codecov.io/gh/haesleinhuepf/napari-crop/branch/master/graph/badge.svg)](https://codecov.io/gh/haesleinhuepf/napari-crop)
+[![tests](https://github.com/BiAPoL/napari-crop/workflows/tests/badge.svg)](https://github.com/BiAPoL/napari-crop/actions)
+[![codecov](https://codecov.io/gh/BiAPoL/napari-crop/branch/main/graph/badge.svg)](https://codecov.io/gh/BiAPoL/napari-crop)
 [![DOI](https://zenodo.org/badge/419822240.svg)](https://zenodo.org/badge/latestdoi/419822240)
 
 Crop regions in napari manually
 
-![](https://github.com/haesleinhuepf/napari-crop/raw/main/images/screencast.gif)
+![](https://github.com/BiAPoL/napari-crop/raw/main/images/screencast.gif)
 
 Crop in any dimension
 
-![](https://github.com/haesleinhuepf/napari-crop/raw/main/images/side_crop.gif)
+![](https://github.com/BiAPoL/napari-crop/raw/main/images/side_crop.gif)
 
 Cut a volume using a plane
 
 *Note: this functionality currently only works with 3D data*
 
-![](https://github.com/haesleinhuepf/napari-crop/raw/main/images/napari_crop_cut_with_plane_demo.gif)
+![](https://github.com/BiAPoL/napari-crop/raw/main/images/napari_crop_cut_with_plane_demo.gif)
 
 ## Usage
 Create a new shapes layer to annotate the region you would like to crop:
 
-![](https://github.com/haesleinhuepf/napari-crop/raw/main/images/shapes.png)
+![](https://github.com/BiAPoL/napari-crop/raw/main/images/shapes.png)
 
 Use the rectangle tool to annotate a region. Start the `crop` tool from the `Tools > Utilities > Crop region` menu. 
 Click the `Run` button to crop the region.
 
-![](https://github.com/haesleinhuepf/napari-crop/raw/main/images/draw_rectangle.png)
+![](https://github.com/BiAPoL/napari-crop/raw/main/images/draw_rectangle.png)
 
 You can also use the `Select shapes` tool to move the rectangle to a new place and crop another region by clicking on `Run`.
 
-![](https://github.com/haesleinhuepf/napari-crop/raw/main/images/move_rectangle.png)
+![](https://github.com/BiAPoL/napari-crop/raw/main/images/move_rectangle.png)
 
 Hint: You can also use the [napari-tabu](https://www.napari-hub.org/plugins/napari-tabu) plugin to send all your cropped images to a new napari window.
 
-![](https://github.com/haesleinhuepf/napari-crop/raw/main/images/new_window.gif)
+![](https://github.com/BiAPoL/napari-crop/raw/main/images/new_window.gif)
 
 ----------------------------------
 
 This [napari] plugin was generated with [Cookiecutter] using with [@napari]'s [cookiecutter-napari-plugin] template.
 
 ## Installation
 
@@ -68,15 +68,15 @@
 [MIT]: http://opensource.org/licenses/MIT
 [BSD-3]: http://opensource.org/licenses/BSD-3-Clause
 [GNU GPL v3.0]: http://www.gnu.org/licenses/gpl-3.0.txt
 [GNU LGPL v3.0]: http://www.gnu.org/licenses/lgpl-3.0.txt
 [Apache Software License 2.0]: http://www.apache.org/licenses/LICENSE-2.0
 [Mozilla Public License 2.0]: https://www.mozilla.org/media/MPL/2.0/index.txt
 [cookiecutter-napari-plugin]: https://github.com/napari/cookiecutter-napari-plugin
-[file an issue]: https://github.com/haesleinhuepf/napari-crop/issues
+[file an issue]: https://github.com/BiAPoL/napari-crop/issues
 [napari]: https://github.com/napari/napari
 [tox]: https://tox.readthedocs.io/en/latest/
 [pip]: https://pypi.org/project/pip/
 [PyPI]: https://pypi.org/
 [image.sc]: https://image.sc
 [@haesleinhuepf]: https://twitter.com/haesleinhuepf
```

### Comparing `napari-crop-0.1.8/napari_crop/_dock_widgets.py` & `napari-crop-0.1.9/napari_crop/_dock_widgets.py`

 * *Files identical despite different names*

### Comparing `napari-crop-0.1.8/napari_crop/_function.py` & `napari-crop-0.1.9/napari_crop/_function.py`

 * *Files identical despite different names*

### Comparing `napari-crop-0.1.8/napari_crop/_tests/test_function.py` & `napari-crop-0.1.9/napari_crop/_tests/test_function.py`

 * *Files identical despite different names*

### Comparing `napari-crop-0.1.8/napari_crop/_tests/test_widget.py` & `napari-crop-0.1.9/napari_crop/_tests/test_widget.py`

 * *Files identical despite different names*

### Comparing `napari-crop-0.1.8/napari_crop/_utils.py` & `napari-crop-0.1.9/napari_crop/_utils.py`

 * *Files identical despite different names*

### Comparing `napari-crop-0.1.8/napari_crop.egg-info/PKG-INFO` & `napari-crop-0.1.9/napari_crop.egg-info/PKG-INFO`

 * *Files 17% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: napari-crop
-Version: 0.1.8
+Version: 0.1.9
 Summary: Crop regions in napari manually
 Home-page: https://github.com/biapol/napari-crop
 Author: Robert Haase, Tim Morello, Marcelo Leomil Zoccoler, Johannes Muller
 Author-email: robert.haase@tu-dresden.de
 License: BSD-3-Clause
 Project-URL: Bug Tracker, https://github.com/biapol/napari-crop/issues
 Project-URL: Documentation, https://github.com/biapol/napari-crop#README.md
@@ -13,63 +13,62 @@
 Classifier: Development Status :: 3 - Alpha
 Classifier: Intended Audience :: Developers
 Classifier: Framework :: napari
 Classifier: Topic :: Scientific/Engineering :: Image Processing
 Classifier: Topic :: Scientific/Engineering :: Information Analysis
 Classifier: Programming Language :: Python
 Classifier: Programming Language :: Python :: 3
-Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Operating System :: OS Independent
 Classifier: License :: OSI Approved :: BSD License
-Requires-Python: >=3.7
+Requires-Python: >=3.8
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 # napari-crop
 
-[![License](https://img.shields.io/pypi/l/napari-crop.svg?color=green)](https://github.com/haesleinhuepf/napari-crop/raw/master/LICENSE)
+[![License](https://img.shields.io/pypi/l/napari-crop.svg?color=green)](https://github.com/BiAPoL/napari-crop/raw/master/LICENSE)
 [![PyPI](https://img.shields.io/pypi/v/napari-crop.svg?color=green)](https://pypi.org/project/napari-crop)
 [![Python Version](https://img.shields.io/pypi/pyversions/napari-crop.svg?color=green)](https://python.org)
-[![tests](https://github.com/haesleinhuepf/napari-crop/workflows/tests/badge.svg)](https://github.com/haesleinhuepf/napari-crop/actions)
-[![codecov](https://codecov.io/gh/haesleinhuepf/napari-crop/branch/master/graph/badge.svg)](https://codecov.io/gh/haesleinhuepf/napari-crop)
+[![tests](https://github.com/BiAPoL/napari-crop/workflows/tests/badge.svg)](https://github.com/BiAPoL/napari-crop/actions)
+[![codecov](https://codecov.io/gh/BiAPoL/napari-crop/branch/main/graph/badge.svg)](https://codecov.io/gh/BiAPoL/napari-crop)
 [![DOI](https://zenodo.org/badge/419822240.svg)](https://zenodo.org/badge/latestdoi/419822240)
 
 Crop regions in napari manually
 
-![](https://github.com/haesleinhuepf/napari-crop/raw/main/images/screencast.gif)
+![](https://github.com/BiAPoL/napari-crop/raw/main/images/screencast.gif)
 
 Crop in any dimension
 
-![](https://github.com/haesleinhuepf/napari-crop/raw/main/images/side_crop.gif)
+![](https://github.com/BiAPoL/napari-crop/raw/main/images/side_crop.gif)
 
 Cut a volume using a plane
 
 *Note: this functionality currently only works with 3D data*
 
-![](https://github.com/haesleinhuepf/napari-crop/raw/main/images/napari_crop_cut_with_plane_demo.gif)
+![](https://github.com/BiAPoL/napari-crop/raw/main/images/napari_crop_cut_with_plane_demo.gif)
 
 ## Usage
 Create a new shapes layer to annotate the region you would like to crop:
 
-![](https://github.com/haesleinhuepf/napari-crop/raw/main/images/shapes.png)
+![](https://github.com/BiAPoL/napari-crop/raw/main/images/shapes.png)
 
 Use the rectangle tool to annotate a region. Start the `crop` tool from the `Tools > Utilities > Crop region` menu. 
 Click the `Run` button to crop the region.
 
-![](https://github.com/haesleinhuepf/napari-crop/raw/main/images/draw_rectangle.png)
+![](https://github.com/BiAPoL/napari-crop/raw/main/images/draw_rectangle.png)
 
 You can also use the `Select shapes` tool to move the rectangle to a new place and crop another region by clicking on `Run`.
 
-![](https://github.com/haesleinhuepf/napari-crop/raw/main/images/move_rectangle.png)
+![](https://github.com/BiAPoL/napari-crop/raw/main/images/move_rectangle.png)
 
 Hint: You can also use the [napari-tabu](https://www.napari-hub.org/plugins/napari-tabu) plugin to send all your cropped images to a new napari window.
 
-![](https://github.com/haesleinhuepf/napari-crop/raw/main/images/new_window.gif)
+![](https://github.com/BiAPoL/napari-crop/raw/main/images/new_window.gif)
 
 ----------------------------------
 
 This [napari] plugin was generated with [Cookiecutter] using with [@napari]'s [cookiecutter-napari-plugin] template.
 
 ## Installation
 
@@ -96,15 +95,15 @@
 [MIT]: http://opensource.org/licenses/MIT
 [BSD-3]: http://opensource.org/licenses/BSD-3-Clause
 [GNU GPL v3.0]: http://www.gnu.org/licenses/gpl-3.0.txt
 [GNU LGPL v3.0]: http://www.gnu.org/licenses/lgpl-3.0.txt
 [Apache Software License 2.0]: http://www.apache.org/licenses/LICENSE-2.0
 [Mozilla Public License 2.0]: https://www.mozilla.org/media/MPL/2.0/index.txt
 [cookiecutter-napari-plugin]: https://github.com/napari/cookiecutter-napari-plugin
-[file an issue]: https://github.com/haesleinhuepf/napari-crop/issues
+[file an issue]: https://github.com/BiAPoL/napari-crop/issues
 [napari]: https://github.com/napari/napari
 [tox]: https://tox.readthedocs.io/en/latest/
 [pip]: https://pypi.org/project/pip/
 [PyPI]: https://pypi.org/
 [image.sc]: https://image.sc
 [@haesleinhuepf]: https://twitter.com/haesleinhuepf
```

### Comparing `napari-crop-0.1.8/setup.cfg` & `napari-crop-0.1.9/setup.cfg`

 * *Files 9% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 00000000: 5b6d 6574 6164 6174 615d 0d0a 6e61 6d65  [metadata]..name
 00000010: 203d 206e 6170 6172 692d 6372 6f70 0d0a   = napari-crop..
-00000020: 7665 7273 696f 6e20 3d20 302e 312e 380d  version = 0.1.8.
+00000020: 7665 7273 696f 6e20 3d20 302e 312e 390d  version = 0.1.9.
 00000030: 0a61 7574 686f 7220 3d20 526f 6265 7274  .author = Robert
 00000040: 2048 6161 7365 2c20 5469 6d20 4d6f 7265   Haase, Tim More
 00000050: 6c6c 6f2c 204d 6172 6365 6c6f 204c 656f  llo, Marcelo Leo
 00000060: 6d69 6c20 5a6f 6363 6f6c 6572 2c20 4a6f  mil Zoccoler, Jo
 00000070: 6861 6e6e 6573 204d 756c 6c65 720d 0a61  hannes Muller..a
 00000080: 7574 686f 725f 656d 6169 6c20 3d20 726f  uthor_email = ro
 00000090: 6265 7274 2e68 6161 7365 4074 752d 6472  bert.haase@tu-dr
@@ -37,53 +37,50 @@
 00000240: 2041 6e61 6c79 7369 730d 0a09 5072 6f67   Analysis...Prog
 00000250: 7261 6d6d 696e 6720 4c61 6e67 7561 6765  ramming Language
 00000260: 203a 3a20 5079 7468 6f6e 0d0a 0950 726f   :: Python...Pro
 00000270: 6772 616d 6d69 6e67 204c 616e 6775 6167  gramming Languag
 00000280: 6520 3a3a 2050 7974 686f 6e20 3a3a 2033  e :: Python :: 3
 00000290: 0d0a 0950 726f 6772 616d 6d69 6e67 204c  ...Programming L
 000002a0: 616e 6775 6167 6520 3a3a 2050 7974 686f  anguage :: Pytho
-000002b0: 6e20 3a3a 2033 2e37 0d0a 0950 726f 6772  n :: 3.7...Progr
+000002b0: 6e20 3a3a 2033 2e38 0d0a 0950 726f 6772  n :: 3.8...Progr
 000002c0: 616d 6d69 6e67 204c 616e 6775 6167 6520  amming Language 
-000002d0: 3a3a 2050 7974 686f 6e20 3a3a 2033 2e38  :: Python :: 3.8
-000002e0: 0d0a 0950 726f 6772 616d 6d69 6e67 204c  ...Programming L
-000002f0: 616e 6775 6167 6520 3a3a 2050 7974 686f  anguage :: Pytho
-00000300: 6e20 3a3a 2033 2e39 0d0a 094f 7065 7261  n :: 3.9...Opera
-00000310: 7469 6e67 2053 7973 7465 6d20 3a3a 204f  ting System :: O
-00000320: 5320 496e 6465 7065 6e64 656e 740d 0a09  S Independent...
-00000330: 4c69 6365 6e73 6520 3a3a 204f 5349 2041  License :: OSI A
-00000340: 7070 726f 7665 6420 3a3a 2042 5344 204c  pproved :: BSD L
-00000350: 6963 656e 7365 0d0a 7072 6f6a 6563 745f  icense..project_
-00000360: 7572 6c73 203d 200d 0a09 4275 6720 5472  urls = ...Bug Tr
-00000370: 6163 6b65 7220 3d20 6874 7470 733a 2f2f  acker = https://
-00000380: 6769 7468 7562 2e63 6f6d 2f62 6961 706f  github.com/biapo
-00000390: 6c2f 6e61 7061 7269 2d63 726f 702f 6973  l/napari-crop/is
-000003a0: 7375 6573 0d0a 0944 6f63 756d 656e 7461  sues...Documenta
-000003b0: 7469 6f6e 203d 2068 7474 7073 3a2f 2f67  tion = https://g
-000003c0: 6974 6875 622e 636f 6d2f 6269 6170 6f6c  ithub.com/biapol
-000003d0: 2f6e 6170 6172 692d 6372 6f70 2352 4541  /napari-crop#REA
-000003e0: 444d 452e 6d64 0d0a 0953 6f75 7263 6520  DME.md...Source 
-000003f0: 436f 6465 203d 2068 7474 7073 3a2f 2f67  Code = https://g
-00000400: 6974 6875 622e 636f 6d2f 6269 6170 6f6c  ithub.com/biapol
-00000410: 2f6e 6170 6172 692d 6372 6f70 0d0a 0955  /napari-crop...U
-00000420: 7365 7220 5375 7070 6f72 7420 3d20 6874  ser Support = ht
-00000430: 7470 733a 2f2f 6769 7468 7562 2e63 6f6d  tps://github.com
-00000440: 2f62 6961 706f 6c2f 6e61 7061 7269 2d63  /biapol/napari-c
-00000450: 726f 702f 6973 7375 6573 0d0a 0d0a 5b6f  rop/issues....[o
-00000460: 7074 696f 6e73 5d0d 0a70 6163 6b61 6765  ptions]..package
-00000470: 7320 3d20 6669 6e64 3a0d 0a70 7974 686f  s = find:..pytho
-00000480: 6e5f 7265 7175 6972 6573 203d 203e 3d33  n_requires = >=3
-00000490: 2e37 0d0a 696e 7374 616c 6c5f 7265 7175  .7..install_requ
-000004a0: 6972 6573 203d 200d 0a09 6e61 7061 7269  ires = ...napari
-000004b0: 2d70 6c75 6769 6e2d 656e 6769 6e65 3e3d  -plugin-engine>=
-000004c0: 302e 312e 340d 0a09 6e75 6d70 790d 0a09  0.1.4...numpy...
-000004d0: 7363 696b 6974 2d69 6d61 6765 0d0a 096e  scikit-image...n
-000004e0: 6170 6172 692d 746f 6f6c 732d 6d65 6e75  apari-tools-menu
-000004f0: 3e3d 302e 312e 3137 0d0a 096e 6170 6172  >=0.1.17...napar
-00000500: 692d 776f 726b 666c 6f77 730d 0a0d 0a5b  i-workflows....[
-00000510: 6f70 7469 6f6e 732e 656e 7472 795f 706f  options.entry_po
-00000520: 696e 7473 5d0d 0a6e 6170 6172 692e 706c  ints]..napari.pl
-00000530: 7567 696e 203d 200d 0a09 6e61 7061 7269  ugin = ...napari
-00000540: 2d63 726f 7020 3d20 6e61 7061 7269 5f63  -crop = napari_c
-00000550: 726f 700d 0a0d 0a5b 6567 675f 696e 666f  rop....[egg_info
-00000560: 5d0d 0a74 6167 5f62 7569 6c64 203d 200d  ]..tag_build = .
-00000570: 0a74 6167 5f64 6174 6520 3d20 300d 0a0d  .tag_date = 0...
-00000580: 0a                                       .
+000002d0: 3a3a 2050 7974 686f 6e20 3a3a 2033 2e39  :: Python :: 3.9
+000002e0: 0d0a 094f 7065 7261 7469 6e67 2053 7973  ...Operating Sys
+000002f0: 7465 6d20 3a3a 204f 5320 496e 6465 7065  tem :: OS Indepe
+00000300: 6e64 656e 740d 0a09 4c69 6365 6e73 6520  ndent...License 
+00000310: 3a3a 204f 5349 2041 7070 726f 7665 6420  :: OSI Approved 
+00000320: 3a3a 2042 5344 204c 6963 656e 7365 0d0a  :: BSD License..
+00000330: 7072 6f6a 6563 745f 7572 6c73 203d 200d  project_urls = .
+00000340: 0a09 4275 6720 5472 6163 6b65 7220 3d20  ..Bug Tracker = 
+00000350: 6874 7470 733a 2f2f 6769 7468 7562 2e63  https://github.c
+00000360: 6f6d 2f62 6961 706f 6c2f 6e61 7061 7269  om/biapol/napari
+00000370: 2d63 726f 702f 6973 7375 6573 0d0a 0944  -crop/issues...D
+00000380: 6f63 756d 656e 7461 7469 6f6e 203d 2068  ocumentation = h
+00000390: 7474 7073 3a2f 2f67 6974 6875 622e 636f  ttps://github.co
+000003a0: 6d2f 6269 6170 6f6c 2f6e 6170 6172 692d  m/biapol/napari-
+000003b0: 6372 6f70 2352 4541 444d 452e 6d64 0d0a  crop#README.md..
+000003c0: 0953 6f75 7263 6520 436f 6465 203d 2068  .Source Code = h
+000003d0: 7474 7073 3a2f 2f67 6974 6875 622e 636f  ttps://github.co
+000003e0: 6d2f 6269 6170 6f6c 2f6e 6170 6172 692d  m/biapol/napari-
+000003f0: 6372 6f70 0d0a 0955 7365 7220 5375 7070  crop...User Supp
+00000400: 6f72 7420 3d20 6874 7470 733a 2f2f 6769  ort = https://gi
+00000410: 7468 7562 2e63 6f6d 2f62 6961 706f 6c2f  thub.com/biapol/
+00000420: 6e61 7061 7269 2d63 726f 702f 6973 7375  napari-crop/issu
+00000430: 6573 0d0a 0d0a 5b6f 7074 696f 6e73 5d0d  es....[options].
+00000440: 0a70 6163 6b61 6765 7320 3d20 6669 6e64  .packages = find
+00000450: 3a0d 0a70 7974 686f 6e5f 7265 7175 6972  :..python_requir
+00000460: 6573 203d 203e 3d33 2e38 0d0a 696e 7374  es = >=3.8..inst
+00000470: 616c 6c5f 7265 7175 6972 6573 203d 200d  all_requires = .
+00000480: 0a09 6e61 7061 7269 2d70 6c75 6769 6e2d  ..napari-plugin-
+00000490: 656e 6769 6e65 3e3d 302e 312e 340d 0a09  engine>=0.1.4...
+000004a0: 6e75 6d70 790d 0a09 7363 696b 6974 2d69  numpy...scikit-i
+000004b0: 6d61 6765 0d0a 096e 6170 6172 692d 746f  mage...napari-to
+000004c0: 6f6c 732d 6d65 6e75 3e3d 302e 312e 3137  ols-menu>=0.1.17
+000004d0: 0d0a 096e 6170 6172 692d 776f 726b 666c  ...napari-workfl
+000004e0: 6f77 730d 0a0d 0a5b 6f70 7469 6f6e 732e  ows....[options.
+000004f0: 656e 7472 795f 706f 696e 7473 5d0d 0a6e  entry_points]..n
+00000500: 6170 6172 692e 706c 7567 696e 203d 200d  apari.plugin = .
+00000510: 0a09 6e61 7061 7269 2d63 726f 7020 3d20  ..napari-crop = 
+00000520: 6e61 7061 7269 5f63 726f 700d 0a0d 0a5b  napari_crop....[
+00000530: 6567 675f 696e 666f 5d0d 0a74 6167 5f62  egg_info]..tag_b
+00000540: 7569 6c64 203d 200d 0a74 6167 5f64 6174  uild = ..tag_dat
+00000550: 6520 3d20 300d 0a0d 0a                   e = 0....
```

