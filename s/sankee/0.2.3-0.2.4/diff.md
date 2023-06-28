# Comparing `tmp/sankee-0.2.3.tar.gz` & `tmp/sankee-0.2.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "sankee-0.2.3.tar", last modified: Wed Mar 15 02:21:37 2023, max compression
+gzip compressed data, was "sankee-0.2.4.tar", last modified: Wed Jun 28 06:04:26 2023, max compression
```

## Comparing `sankee-0.2.3.tar` & `sankee-0.2.4.tar`

### file list

```diff
@@ -1,19 +1,19 @@
-drwxrwxr-x   0 az        (1000) az        (1000)        0 2023-03-15 02:21:37.177665 sankee-0.2.3/
--rw-rw-r--   0 az        (1000) az        (1000)    35149 2021-09-09 00:35:42.000000 sankee-0.2.3/LICENSE
--rw-rw-r--   0 az        (1000) az        (1000)     5716 2023-03-15 02:21:37.177665 sankee-0.2.3/PKG-INFO
--rw-rw-r--   0 az        (1000) az        (1000)     4675 2022-07-16 19:30:24.000000 sankee-0.2.3/README.md
-drwxrwxr-x   0 az        (1000) az        (1000)        0 2023-03-15 02:21:37.177665 sankee-0.2.3/sankee/
--rw-rw-r--   0 az        (1000) az        (1000)      178 2023-03-15 02:21:21.000000 sankee-0.2.3/sankee/__init__.py
--rw-rw-r--   0 az        (1000) az        (1000)    22594 2023-03-15 02:14:57.000000 sankee-0.2.3/sankee/datasets.py
--rw-rw-r--   0 az        (1000) az        (1000)    15193 2023-03-15 02:17:37.000000 sankee-0.2.3/sankee/plotting.py
--rw-rw-r--   0 az        (1000) az        (1000)     2572 2022-12-09 01:10:59.000000 sankee-0.2.3/sankee/sampling.py
--rw-rw-r--   0 az        (1000) az        (1000)     3576 2023-03-15 02:17:37.000000 sankee-0.2.3/sankee/themes.py
--rw-rw-r--   0 az        (1000) az        (1000)     1648 2022-07-16 19:30:24.000000 sankee-0.2.3/sankee/utils.py
-drwxrwxr-x   0 az        (1000) az        (1000)        0 2023-03-15 02:21:37.177665 sankee-0.2.3/sankee.egg-info/
--rw-rw-r--   0 az        (1000) az        (1000)     5716 2023-03-15 02:21:37.000000 sankee-0.2.3/sankee.egg-info/PKG-INFO
--rw-rw-r--   0 az        (1000) az        (1000)      284 2023-03-15 02:21:37.000000 sankee-0.2.3/sankee.egg-info/SOURCES.txt
--rw-rw-r--   0 az        (1000) az        (1000)        1 2023-03-15 02:21:37.000000 sankee-0.2.3/sankee.egg-info/dependency_links.txt
--rw-rw-r--   0 az        (1000) az        (1000)      269 2023-03-15 02:21:37.000000 sankee-0.2.3/sankee.egg-info/requires.txt
--rw-rw-r--   0 az        (1000) az        (1000)        7 2023-03-15 02:21:37.000000 sankee-0.2.3/sankee.egg-info/top_level.txt
--rw-rw-r--   0 az        (1000) az        (1000)       38 2023-03-15 02:21:37.177665 sankee-0.2.3/setup.cfg
--rw-rw-r--   0 az        (1000) az        (1000)     1984 2023-03-15 02:21:21.000000 sankee-0.2.3/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 06:04:26.398585 sankee-0.2.4/
+-rw-rw-rw-   0        0        0     1090 2023-06-28 06:01:41.000000 sankee-0.2.4/LICENSE
+-rw-rw-rw-   0        0        0     5860 2023-06-28 06:04:26.397587 sankee-0.2.4/PKG-INFO
+-rw-rw-rw-   0        0        0     4789 2022-07-16 19:40:08.000000 sankee-0.2.4/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 06:04:26.379587 sankee-0.2.4/sankee/
+-rw-rw-rw-   0        0        0      189 2023-06-28 05:59:31.000000 sankee-0.2.4/sankee/__init__.py
+-rw-rw-rw-   0        0        0    23376 2023-06-28 05:43:40.000000 sankee-0.2.4/sankee/datasets.py
+-rw-rw-rw-   0        0        0    15694 2023-06-28 05:59:55.000000 sankee-0.2.4/sankee/plotting.py
+-rw-rw-rw-   0        0        0     2644 2023-06-28 05:14:22.000000 sankee-0.2.4/sankee/sampling.py
+-rw-rw-rw-   0        0        0     3708 2023-06-28 05:14:22.000000 sankee-0.2.4/sankee/themes.py
+-rw-rw-rw-   0        0        0     1702 2022-07-16 19:40:08.000000 sankee-0.2.4/sankee/utils.py
+drwxrwxrwx   0        0        0        0 2023-06-28 06:04:26.396585 sankee-0.2.4/sankee.egg-info/
+-rw-rw-rw-   0        0        0     5860 2023-06-28 06:04:25.000000 sankee-0.2.4/sankee.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      284 2023-06-28 06:04:26.000000 sankee-0.2.4/sankee.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 06:04:25.000000 sankee-0.2.4/sankee.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0      269 2023-06-28 06:04:26.000000 sankee-0.2.4/sankee.egg-info/requires.txt
+-rw-rw-rw-   0        0        0        7 2023-06-28 06:04:26.000000 sankee-0.2.4/sankee.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       42 2023-06-28 06:04:26.398585 sankee-0.2.4/setup.cfg
+-rw-rw-rw-   0        0        0     2053 2023-06-28 05:59:31.000000 sankee-0.2.4/setup.py
```

### Comparing `sankee-0.2.3/PKG-INFO` & `sankee-0.2.4/PKG-INFO`

 * *Files 13% similar despite different names*

```diff
@@ -1,144 +1,144 @@
-Metadata-Version: 2.1
-Name: sankee
-Version: 0.2.3
-Summary: Visualize classified time series data with interactive Sankey plots in Google Earth Engine.
-Home-page: https://github.com/aazuspan/sankee
-Author: Aaron Zuspan
-Author-email: aa.zuspan@gmail.com
-License: UNKNOWN
-Project-URL: Bug Reports, https://github.com/aazuspan/sankee/issues
-Project-URL: Source, https://github.com/aazuspan/sankee/
-Keywords: sankey land cover visualization
-Platform: UNKNOWN
-Classifier: Development Status :: 3 - Alpha
-Classifier: Intended Audience :: Science/Research
-Classifier: Topic :: Scientific/Engineering
-Classifier: License :: OSI Approved :: MIT License
-Classifier: Programming Language :: Python :: 3
-Classifier: Programming Language :: Python :: 3.7
-Classifier: Programming Language :: Python :: 3.8
-Classifier: Programming Language :: Python :: 3.9
-Classifier: Programming Language :: Python :: 3.10
-Requires-Python: >=3.7
-Description-Content-Type: text/markdown
-Provides-Extra: doc
-Provides-Extra: dev
-Provides-Extra: test
-License-File: LICENSE
-
-# sankee
-
-[![Earth Engine Python](https://img.shields.io/badge/Earth%20Engine%20API-Python-green)](https://developers.google.com/earth-engine/tutorials/community/intro-to-python-api)
-[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/aazuspan/sankee/HEAD?filepath=docs%2Fexamples%2Fmodis_snow_and_ice.ipynb)
-[![conda-forge link](https://img.shields.io/conda/vn/conda-forge/sankee)](https://anaconda.org/conda-forge/sankee)
-[![conda-forge link](https://img.shields.io/pypi/v/sankee)](https://pypi.org/project/sankee)
-[![Testing workflow](https://github.com/aazuspan/sankee/actions/workflows/test.yml/badge.svg)](https://github.com/aazuspan/sankee/actions/workflows/test.yml)
-[![codecov](https://codecov.io/gh/aazuspan/sankee/branch/main/graph/badge.svg?token=39REP2HZQC)](https://codecov.io/gh/aazuspan/sankee)
-[![Read the Docs](https://readthedocs.org/projects/sankee/badge/?version=latest&style=flat)](https://sankee.readthedocs.io/en/latest/?badge=latest)
-[![Downloads](https://pepy.tech/badge/sankee)](https://pepy.tech/project/sankee)
-
-Visualize changes in classified time series data with interactive Sankey plots in Google Earth Engine
-
-![Sankee example showing grassland expansion in the Nile Delta](docs/_static/demo.gif)
-
-## Description
-
-Use [Earth Engine](https://github.com/google/earthengine-api) to visualize changes in land cover, plant health, burn severity, or any other time series of classified imagery with interactive Sankey plots. Use a library of [built-in datasets](https://sankee.readthedocs.io/en/latest/sankee.html#premade-datasets) for convenience or define your own [custom datasets](https://sankee.readthedocs.io/en/latest/sankee.html#custom-datasets) for flexibility.
-
-
-## Installation
-
-### Pip
-
-```bash
-pip install sankee
-```
-
-### Conda
-
-```bash
-conda install -c conda-forge sankee
-```
-
-## Quickstart
-
-### Premade Datasets
-
-Visualize annual changes in land cover using [popular LULC datasets](https://sankee.readthedocs.io/en/latest/sankee.html#supported-datasets) with a couple lines of code. Just choose a dataset, an area of interest, and a list of years to generate a Sankey diagram from a premade dataset. Below, we can look at 30 years of vegetation recovery in the area devastated by the Mt. St. Helens eruption.
-
-```python
-import sankee
-import ee
-
-ee.Initialize()
-
-sankee.datasets.LCMS_LC.sankify(
-  years=[1990, 2000, 2010, 2020],
-  region=ee.Geometry.Point([-122.192688, 46.25917]).buffer(2000),
-  max_classes=3,
-  title="Mt. St. Helens Recovery"
-)
-```
-
-![Proportions of land cover over 4 periods increase from barren to grass and tree cover in a Sankey diagram](docs/_static/helens_recovery.png)
-
-Check out the [example notebook](https://sankee.readthedocs.io/en/latest/examples/modis_snow_and_ice.html) for an interactive demo.
-
-### Custom Datasets
-
-Any classified images can be used by defining the dataset parameters (which pixel values correspond to which labels and colors). For example, we can look at classified [Dynamic World](https://developers.google.com/earth-engine/datasets/catalog/GOOGLE_DYNAMICWORLD_V1) scenes just two weeks apart that show substantial snow loss on Mountain Jefferson during the 2021 Heat Dome in the Pacific Northwest.
-
-```python
-import sankee
-import ee
-
-ee.Initialize()
-
-# Load a set of classified images
-img_list = [
-    ee.Image("GOOGLE/DYNAMICWORLD/V1/20210616T185919_20210616T190431_T10TEQ"),
-    ee.Image("GOOGLE/DYNAMICWORLD/V1/20210706T185919_20210706T190638_T10TEQ")
-]
-
-# Which band contains the classified data?
-band = "label"
-
-# What labels correspond to which pixel values?
-labels = {
-    0: "Water", 1: "Trees", 2: "Grass", 3: "Flooded", 4: "Crops",
-    5: "Shrub / Scrub", 6: "Build", 7: "Bare", 8: "Snow / Ice",
-}
-
-# What colors should be applied to which pixel values?
-palette = {
-    0: "#419BDF", 1: "#397D49", 2: "#88B053", 3: "#7A87C6", 4: "#E49635",
-    5: "#DFC35A", 6: "#C4281B", 7: "#A59B8F", 8: "#B39FE1"
-}
-
-plot = sankee.sankify(
-    image_list=img_list, 
-    band=band, 
-    labels=labels,
-    palette=palette,
-    region=ee.Geometry.Point([-121.80183, 44.67655]).buffer(3000), 
-    max_classes=3,
-    title="Mt. Jefferson Snow Loss - June 2021"
-)
-```
-
-![](docs/_static/jefferson_snow.png)
-
-### Integration with geemap
-
-`sankee` premade datasets are usable through the [geemap](https://github.com/giswqs/geemap) interactive GUI. Check out the [documentation](https://geemap.org/notebooks/75_sankee/) and [video tutorials](https://www.youtube.com/watch?v=IZWpJYX6w8I) by [@giswqs](https://github.com/giswqs).
-
-
-## Contributing
-
-If you find bugs or have feature requests, please open an issue!
-
----
-
-[Top](https://github.com/aazuspan/sankee#sankee)
-
-
+Metadata-Version: 2.1
+Name: sankee
+Version: 0.2.4
+Summary: Visualize classified time series data with interactive Sankey plots in Google Earth Engine.
+Home-page: https://github.com/aazuspan/sankee
+Author: Aaron Zuspan
+Author-email: aa.zuspan@gmail.com
+License: UNKNOWN
+Project-URL: Bug Reports, https://github.com/aazuspan/sankee/issues
+Project-URL: Source, https://github.com/aazuspan/sankee/
+Keywords: sankey land cover visualization
+Platform: UNKNOWN
+Classifier: Development Status :: 3 - Alpha
+Classifier: Intended Audience :: Science/Research
+Classifier: Topic :: Scientific/Engineering
+Classifier: License :: OSI Approved :: MIT License
+Classifier: Programming Language :: Python :: 3
+Classifier: Programming Language :: Python :: 3.7
+Classifier: Programming Language :: Python :: 3.8
+Classifier: Programming Language :: Python :: 3.9
+Classifier: Programming Language :: Python :: 3.10
+Requires-Python: >=3.7
+Description-Content-Type: text/markdown
+Provides-Extra: doc
+Provides-Extra: dev
+Provides-Extra: test
+License-File: LICENSE
+
+# sankee
+
+[![Earth Engine Python](https://img.shields.io/badge/Earth%20Engine%20API-Python-green)](https://developers.google.com/earth-engine/tutorials/community/intro-to-python-api)
+[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/aazuspan/sankee/HEAD?filepath=docs%2Fexamples%2Fmodis_snow_and_ice.ipynb)
+[![conda-forge link](https://img.shields.io/conda/vn/conda-forge/sankee)](https://anaconda.org/conda-forge/sankee)
+[![conda-forge link](https://img.shields.io/pypi/v/sankee)](https://pypi.org/project/sankee)
+[![Testing workflow](https://github.com/aazuspan/sankee/actions/workflows/test.yml/badge.svg)](https://github.com/aazuspan/sankee/actions/workflows/test.yml)
+[![codecov](https://codecov.io/gh/aazuspan/sankee/branch/main/graph/badge.svg?token=39REP2HZQC)](https://codecov.io/gh/aazuspan/sankee)
+[![Read the Docs](https://readthedocs.org/projects/sankee/badge/?version=latest&style=flat)](https://sankee.readthedocs.io/en/latest/?badge=latest)
+[![Downloads](https://pepy.tech/badge/sankee)](https://pepy.tech/project/sankee)
+
+Visualize changes in classified time series data with interactive Sankey plots in Google Earth Engine
+
+![Sankee example showing grassland expansion in the Nile Delta](docs/_static/demo.gif)
+
+## Description
+
+Use [Earth Engine](https://github.com/google/earthengine-api) to visualize changes in land cover, plant health, burn severity, or any other time series of classified imagery with interactive Sankey plots. Use a library of [built-in datasets](https://sankee.readthedocs.io/en/latest/sankee.html#premade-datasets) for convenience or define your own [custom datasets](https://sankee.readthedocs.io/en/latest/sankee.html#custom-datasets) for flexibility.
+
+
+## Installation
+
+### Pip
+
+```bash
+pip install sankee
+```
+
+### Conda
+
+```bash
+conda install -c conda-forge sankee
+```
+
+## Quickstart
+
+### Premade Datasets
+
+Visualize annual changes in land cover using [popular LULC datasets](https://sankee.readthedocs.io/en/latest/sankee.html#supported-datasets) with a couple lines of code. Just choose a dataset, an area of interest, and a list of years to generate a Sankey diagram from a premade dataset. Below, we can look at 30 years of vegetation recovery in the area devastated by the Mt. St. Helens eruption.
+
+```python
+import sankee
+import ee
+
+ee.Initialize()
+
+sankee.datasets.LCMS_LC.sankify(
+  years=[1990, 2000, 2010, 2020],
+  region=ee.Geometry.Point([-122.192688, 46.25917]).buffer(2000),
+  max_classes=3,
+  title="Mt. St. Helens Recovery"
+)
+```
+
+![Proportions of land cover over 4 periods increase from barren to grass and tree cover in a Sankey diagram](docs/_static/helens_recovery.png)
+
+Check out the [example notebook](https://sankee.readthedocs.io/en/latest/examples/modis_snow_and_ice.html) for an interactive demo.
+
+### Custom Datasets
+
+Any classified images can be used by defining the dataset parameters (which pixel values correspond to which labels and colors). For example, we can look at classified [Dynamic World](https://developers.google.com/earth-engine/datasets/catalog/GOOGLE_DYNAMICWORLD_V1) scenes just two weeks apart that show substantial snow loss on Mountain Jefferson during the 2021 Heat Dome in the Pacific Northwest.
+
+```python
+import sankee
+import ee
+
+ee.Initialize()
+
+# Load a set of classified images
+img_list = [
+    ee.Image("GOOGLE/DYNAMICWORLD/V1/20210616T185919_20210616T190431_T10TEQ"),
+    ee.Image("GOOGLE/DYNAMICWORLD/V1/20210706T185919_20210706T190638_T10TEQ")
+]
+
+# Which band contains the classified data?
+band = "label"
+
+# What labels correspond to which pixel values?
+labels = {
+    0: "Water", 1: "Trees", 2: "Grass", 3: "Flooded", 4: "Crops",
+    5: "Shrub / Scrub", 6: "Build", 7: "Bare", 8: "Snow / Ice",
+}
+
+# What colors should be applied to which pixel values?
+palette = {
+    0: "#419BDF", 1: "#397D49", 2: "#88B053", 3: "#7A87C6", 4: "#E49635",
+    5: "#DFC35A", 6: "#C4281B", 7: "#A59B8F", 8: "#B39FE1"
+}
+
+plot = sankee.sankify(
+    image_list=img_list, 
+    band=band, 
+    labels=labels,
+    palette=palette,
+    region=ee.Geometry.Point([-121.80183, 44.67655]).buffer(3000), 
+    max_classes=3,
+    title="Mt. Jefferson Snow Loss - June 2021"
+)
+```
+
+![](docs/_static/jefferson_snow.png)
+
+### Integration with geemap
+
+`sankee` premade datasets are usable through the [geemap](https://github.com/giswqs/geemap) interactive GUI. Check out the [documentation](https://geemap.org/notebooks/75_sankee/) and [video tutorials](https://www.youtube.com/watch?v=IZWpJYX6w8I) by [@giswqs](https://github.com/giswqs).
+
+
+## Contributing
+
+If you find bugs or have feature requests, please open an issue!
+
+---
+
+[Top](https://github.com/aazuspan/sankee#sankee)
+
+
```

### Comparing `sankee-0.2.3/README.md` & `sankee-0.2.4/README.md`

 * *Ordering differences only*

 * *Files 15% similar despite different names*

```diff
@@ -1,114 +1,114 @@
-# sankee
-
-[![Earth Engine Python](https://img.shields.io/badge/Earth%20Engine%20API-Python-green)](https://developers.google.com/earth-engine/tutorials/community/intro-to-python-api)
-[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/aazuspan/sankee/HEAD?filepath=docs%2Fexamples%2Fmodis_snow_and_ice.ipynb)
-[![conda-forge link](https://img.shields.io/conda/vn/conda-forge/sankee)](https://anaconda.org/conda-forge/sankee)
-[![conda-forge link](https://img.shields.io/pypi/v/sankee)](https://pypi.org/project/sankee)
-[![Testing workflow](https://github.com/aazuspan/sankee/actions/workflows/test.yml/badge.svg)](https://github.com/aazuspan/sankee/actions/workflows/test.yml)
-[![codecov](https://codecov.io/gh/aazuspan/sankee/branch/main/graph/badge.svg?token=39REP2HZQC)](https://codecov.io/gh/aazuspan/sankee)
-[![Read the Docs](https://readthedocs.org/projects/sankee/badge/?version=latest&style=flat)](https://sankee.readthedocs.io/en/latest/?badge=latest)
-[![Downloads](https://pepy.tech/badge/sankee)](https://pepy.tech/project/sankee)
-
-Visualize changes in classified time series data with interactive Sankey plots in Google Earth Engine
-
-![Sankee example showing grassland expansion in the Nile Delta](docs/_static/demo.gif)
-
-## Description
-
-Use [Earth Engine](https://github.com/google/earthengine-api) to visualize changes in land cover, plant health, burn severity, or any other time series of classified imagery with interactive Sankey plots. Use a library of [built-in datasets](https://sankee.readthedocs.io/en/latest/sankee.html#premade-datasets) for convenience or define your own [custom datasets](https://sankee.readthedocs.io/en/latest/sankee.html#custom-datasets) for flexibility.
-
-
-## Installation
-
-### Pip
-
-```bash
-pip install sankee
-```
-
-### Conda
-
-```bash
-conda install -c conda-forge sankee
-```
-
-## Quickstart
-
-### Premade Datasets
-
-Visualize annual changes in land cover using [popular LULC datasets](https://sankee.readthedocs.io/en/latest/sankee.html#supported-datasets) with a couple lines of code. Just choose a dataset, an area of interest, and a list of years to generate a Sankey diagram from a premade dataset. Below, we can look at 30 years of vegetation recovery in the area devastated by the Mt. St. Helens eruption.
-
-```python
-import sankee
-import ee
-
-ee.Initialize()
-
-sankee.datasets.LCMS_LC.sankify(
-  years=[1990, 2000, 2010, 2020],
-  region=ee.Geometry.Point([-122.192688, 46.25917]).buffer(2000),
-  max_classes=3,
-  title="Mt. St. Helens Recovery"
-)
-```
-
-![Proportions of land cover over 4 periods increase from barren to grass and tree cover in a Sankey diagram](docs/_static/helens_recovery.png)
-
-Check out the [example notebook](https://sankee.readthedocs.io/en/latest/examples/modis_snow_and_ice.html) for an interactive demo.
-
-### Custom Datasets
-
-Any classified images can be used by defining the dataset parameters (which pixel values correspond to which labels and colors). For example, we can look at classified [Dynamic World](https://developers.google.com/earth-engine/datasets/catalog/GOOGLE_DYNAMICWORLD_V1) scenes just two weeks apart that show substantial snow loss on Mountain Jefferson during the 2021 Heat Dome in the Pacific Northwest.
-
-```python
-import sankee
-import ee
-
-ee.Initialize()
-
-# Load a set of classified images
-img_list = [
-    ee.Image("GOOGLE/DYNAMICWORLD/V1/20210616T185919_20210616T190431_T10TEQ"),
-    ee.Image("GOOGLE/DYNAMICWORLD/V1/20210706T185919_20210706T190638_T10TEQ")
-]
-
-# Which band contains the classified data?
-band = "label"
-
-# What labels correspond to which pixel values?
-labels = {
-    0: "Water", 1: "Trees", 2: "Grass", 3: "Flooded", 4: "Crops",
-    5: "Shrub / Scrub", 6: "Build", 7: "Bare", 8: "Snow / Ice",
-}
-
-# What colors should be applied to which pixel values?
-palette = {
-    0: "#419BDF", 1: "#397D49", 2: "#88B053", 3: "#7A87C6", 4: "#E49635",
-    5: "#DFC35A", 6: "#C4281B", 7: "#A59B8F", 8: "#B39FE1"
-}
-
-plot = sankee.sankify(
-    image_list=img_list, 
-    band=band, 
-    labels=labels,
-    palette=palette,
-    region=ee.Geometry.Point([-121.80183, 44.67655]).buffer(3000), 
-    max_classes=3,
-    title="Mt. Jefferson Snow Loss - June 2021"
-)
-```
-
-![](docs/_static/jefferson_snow.png)
-
-### Integration with geemap
-
-`sankee` premade datasets are usable through the [geemap](https://github.com/giswqs/geemap) interactive GUI. Check out the [documentation](https://geemap.org/notebooks/75_sankee/) and [video tutorials](https://www.youtube.com/watch?v=IZWpJYX6w8I) by [@giswqs](https://github.com/giswqs).
-
-
-## Contributing
-
-If you find bugs or have feature requests, please open an issue!
-
----
-
-[Top](https://github.com/aazuspan/sankee#sankee)
+# sankee
+
+[![Earth Engine Python](https://img.shields.io/badge/Earth%20Engine%20API-Python-green)](https://developers.google.com/earth-engine/tutorials/community/intro-to-python-api)
+[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/aazuspan/sankee/HEAD?filepath=docs%2Fexamples%2Fmodis_snow_and_ice.ipynb)
+[![conda-forge link](https://img.shields.io/conda/vn/conda-forge/sankee)](https://anaconda.org/conda-forge/sankee)
+[![conda-forge link](https://img.shields.io/pypi/v/sankee)](https://pypi.org/project/sankee)
+[![Testing workflow](https://github.com/aazuspan/sankee/actions/workflows/test.yml/badge.svg)](https://github.com/aazuspan/sankee/actions/workflows/test.yml)
+[![codecov](https://codecov.io/gh/aazuspan/sankee/branch/main/graph/badge.svg?token=39REP2HZQC)](https://codecov.io/gh/aazuspan/sankee)
+[![Read the Docs](https://readthedocs.org/projects/sankee/badge/?version=latest&style=flat)](https://sankee.readthedocs.io/en/latest/?badge=latest)
+[![Downloads](https://pepy.tech/badge/sankee)](https://pepy.tech/project/sankee)
+
+Visualize changes in classified time series data with interactive Sankey plots in Google Earth Engine
+
+![Sankee example showing grassland expansion in the Nile Delta](docs/_static/demo.gif)
+
+## Description
+
+Use [Earth Engine](https://github.com/google/earthengine-api) to visualize changes in land cover, plant health, burn severity, or any other time series of classified imagery with interactive Sankey plots. Use a library of [built-in datasets](https://sankee.readthedocs.io/en/latest/sankee.html#premade-datasets) for convenience or define your own [custom datasets](https://sankee.readthedocs.io/en/latest/sankee.html#custom-datasets) for flexibility.
+
+
+## Installation
+
+### Pip
+
+```bash
+pip install sankee
+```
+
+### Conda
+
+```bash
+conda install -c conda-forge sankee
+```
+
+## Quickstart
+
+### Premade Datasets
+
+Visualize annual changes in land cover using [popular LULC datasets](https://sankee.readthedocs.io/en/latest/sankee.html#supported-datasets) with a couple lines of code. Just choose a dataset, an area of interest, and a list of years to generate a Sankey diagram from a premade dataset. Below, we can look at 30 years of vegetation recovery in the area devastated by the Mt. St. Helens eruption.
+
+```python
+import sankee
+import ee
+
+ee.Initialize()
+
+sankee.datasets.LCMS_LC.sankify(
+  years=[1990, 2000, 2010, 2020],
+  region=ee.Geometry.Point([-122.192688, 46.25917]).buffer(2000),
+  max_classes=3,
+  title="Mt. St. Helens Recovery"
+)
+```
+
+![Proportions of land cover over 4 periods increase from barren to grass and tree cover in a Sankey diagram](docs/_static/helens_recovery.png)
+
+Check out the [example notebook](https://sankee.readthedocs.io/en/latest/examples/modis_snow_and_ice.html) for an interactive demo.
+
+### Custom Datasets
+
+Any classified images can be used by defining the dataset parameters (which pixel values correspond to which labels and colors). For example, we can look at classified [Dynamic World](https://developers.google.com/earth-engine/datasets/catalog/GOOGLE_DYNAMICWORLD_V1) scenes just two weeks apart that show substantial snow loss on Mountain Jefferson during the 2021 Heat Dome in the Pacific Northwest.
+
+```python
+import sankee
+import ee
+
+ee.Initialize()
+
+# Load a set of classified images
+img_list = [
+    ee.Image("GOOGLE/DYNAMICWORLD/V1/20210616T185919_20210616T190431_T10TEQ"),
+    ee.Image("GOOGLE/DYNAMICWORLD/V1/20210706T185919_20210706T190638_T10TEQ")
+]
+
+# Which band contains the classified data?
+band = "label"
+
+# What labels correspond to which pixel values?
+labels = {
+    0: "Water", 1: "Trees", 2: "Grass", 3: "Flooded", 4: "Crops",
+    5: "Shrub / Scrub", 6: "Build", 7: "Bare", 8: "Snow / Ice",
+}
+
+# What colors should be applied to which pixel values?
+palette = {
+    0: "#419BDF", 1: "#397D49", 2: "#88B053", 3: "#7A87C6", 4: "#E49635",
+    5: "#DFC35A", 6: "#C4281B", 7: "#A59B8F", 8: "#B39FE1"
+}
+
+plot = sankee.sankify(
+    image_list=img_list, 
+    band=band, 
+    labels=labels,
+    palette=palette,
+    region=ee.Geometry.Point([-121.80183, 44.67655]).buffer(3000), 
+    max_classes=3,
+    title="Mt. Jefferson Snow Loss - June 2021"
+)
+```
+
+![](docs/_static/jefferson_snow.png)
+
+### Integration with geemap
+
+`sankee` premade datasets are usable through the [geemap](https://github.com/giswqs/geemap) interactive GUI. Check out the [documentation](https://geemap.org/notebooks/75_sankee/) and [video tutorials](https://www.youtube.com/watch?v=IZWpJYX6w8I) by [@giswqs](https://github.com/giswqs).
+
+
+## Contributing
+
+If you find bugs or have feature requests, please open an issue!
+
+---
+
+[Top](https://github.com/aazuspan/sankee#sankee)
```

### Comparing `sankee-0.2.3/sankee/plotting.py` & `sankee-0.2.4/sankee/plotting.py`

 * *Files 18% similar despite different names*

```diff
@@ -1,415 +1,417 @@
-from collections import namedtuple
-from typing import Dict, List, Union
-
-import ee
-import ipywidgets as widgets
-import pandas as pd
-import plotly.graph_objects as go
-
-from sankee import sampling, themes, utils
-
-SankeyParameters = namedtuple(
-    "SankeyParameters",
-    [
-        "node_labels",
-        "link_labels",
-        "node_palette",
-        "link_palette",
-        "label",
-        "source",
-        "target",
-        "value",
-    ],
-)
-
-
-def sankify(
-    image_list: List[ee.Image],
-    band: str,
-    labels: Dict[int, str],
-    palette: Dict[int, str],
-    region: Union[None, ee.Geometry] = None,
-    label_list: Union[None, List[str]] = None,
-    max_classes: Union[None, int] = None,
-    n: int = 500,
-    title: Union[None, str] = None,
-    scale: Union[None, int] = None,
-    seed: int = 0,
-    label_type: Union[None, str] = "class",
-    theme: Union[str, themes.Theme] = "default",
-) -> go.Figure:
-    """
-    Generate an interactive Sankey plot showing land cover change over time from a series of images.
-
-    Parameters
-    ----------
-    image_list : List[ee.Image]
-        An ordered list of images representing a time series of classified data. Each image will be
-        sampled to generate the Sankey plot. Any length of list is allowed, but lists with more than
-        3 or 4 images may produce unusable plots.
-    band : str
-        The name of the band in all images of image_list that contains classified data.
-    labels : dict
-        The labels associated with each value of all images in image_list. Any values not defined
-        in the labels will be dropped from the sampled data.
-    palette : dict
-        The colors associated with each value of all images in image_list.
-    region : ee.Geometry, default None
-        A region to generate samples within. The region must overlap all images. If none is
-        provided, the geometry of the first image will be used. For this to work, images must be
-        bounded.
-    label_list : List[str], default None
-        An ordered list of labels corresponding to the images. The list must be the same length as
-        image_list. If none is provided, sequential numeric labels will be automatically assigned
-        starting at 0. Labels are displayed on-hover on the Sankey nodes.
-    max_classes : int, default None
-        If a value is provided, small classes will be removed until max_classes remain. Class size
-        is calculated based on total times sampled in the time series.
-    n : int, default 500
-        The number of sample points to randomly generate for characterizing all images. More samples
-        will provide more representative data but will take longer to process.
-    title : str, default None
-        An optional title that will be displayed above the Sankey plot.
-    scale : int, default None
-        The scale in image units to perform sampling at. If none is provided, GEE will attempt to
-        use the image's nominal scale, which may cause errors depending on the image projection.
-    seed : int, default 0
-        The seed value used to generate repeatable results during random sampling.
-    label_type : str, default "class"
-        The type of label to display for each link, one of "class", "percent", "count", or False.
-        Selecting "class" will use the class label, "percent" will use the proportion of sampled
-        pixels in each class, and "count" will use the number of sampled pixels in each class.
-        False will disable link labels.
-    theme : str or Theme
-        The theme to apply to the Sankey diagram. Can be the name of a built-in theme (e.g. "d3") or
-        a custom `sankee.Theme` object.
-
-    Returns
-    -------
-    plotly.graph_objs._figure.Figure
-        An interactive Sankey plot.
-    """
-    if region is None:
-        region = image_list[0].geometry()
-
-    label_list = label_list if label_list is not None else list(range(len(image_list)))
-    label_list = [str(label) for label in label_list]
-    if len(label_list) != len(image_list):
-        raise ValueError("The number of labels must match the number of images.")
-    if len(set(label_list)) != len(label_list):
-        raise ValueError("All labels in the `label_list` must be unique.")
-
-    data, samples = sampling.generate_sample_data(
-        image_list=image_list,
-        image_labels=label_list,
-        band=band,
-        scale=scale,
-        include=list(labels.keys()),
-        max_classes=max_classes,
-        region=region,
-        n=n,
-        seed=seed,
-    )
-
-    return SankeyPlot(
-        data=data,
-        labels=labels,
-        palette=palette,
-        title=title,
-        samples=samples,
-        label_type=label_type,
-        theme=theme,
-    )
-
-
-class SankeyPlot(widgets.DOMWidget):
-    def __init__(
-        self,
-        data: pd.DataFrame,
-        labels: Dict[int, str],
-        palette: Dict[int, str],
-        title: str,
-        samples: ee.FeatureCollection,
-        label_type: str,
-        theme: Union[str, themes.Theme],
-    ):
-        self.data = data
-        self.labels = labels
-        self.palette = palette
-        self.title = title
-        self.samples = samples
-        self.label_type = label_type
-        self.theme = theme
-
-        self.hide = []
-        # Initialized by `self.generate_plot`
-        self.df = None
-        self.plot = self.generate_plot()
-        self.gui = self.generate_gui()
-
-    def get_sorted_classes(self) -> pd.Series:
-        """Return all unique class values, sorted by the total number of observations."""
-        start_count = (
-            self.df.groupby("source")
-            .mean()
-            .reset_index()[["source", "total"]]
-            .rename(columns={"source": "class", "total": "count"})
-        )
-        end_count = (
-            self.df.groupby("target")
-            .sum()
-            .reset_index()[["target", "changed"]]
-            .rename(columns={"target": "class", "changed": "count"})
-        )
-        total_count = pd.concat([start_count, end_count]).groupby("class").sum().reset_index()
-
-        return total_count.sort_values(by="count", ascending=False)["class"].reset_index(drop=True)
-
-    def get_active_classes(self) -> pd.Series:
-        """Return all unique active, visibile class values after filtering."""
-        return self.df[["source", "target"]].melt().value.unique()
-
-    def generate_plot_parameters(self) -> SankeyParameters:
-        """Generate Sankey plot parameters from a formatted, cleaned dataframe"""
-        df = self.df.copy()
-
-        source_df = df[["source", "source_year"]].rename(
-            columns={"source": "class", "source_year": "year"}
-        )
-        target_df = df[["target", "target_year"]].rename(
-            columns={"target": "class", "target_year": "year"}
-        )
-        all_classes = pd.concat([source_df, target_df])
-
-        all_classes = all_classes.drop_duplicates().reset_index(drop=True)
-        all_classes["color"] = all_classes["class"].apply(lambda k: self.palette[k]).tolist()
-        all_classes["id"] = all_classes.groupby(["year", "class"], sort=False).ngroup()
-
-        # Join the sequential class-year IDs to the dataframe
-        df["source_id"] = pd.merge(
-            left=df,
-            right=all_classes,
-            how="left",
-            left_on=["source_year", "source"],
-            right_on=["year", "class"],
-        )["id"]
-        df["target_id"] = pd.merge(
-            left=df,
-            right=all_classes,
-            how="left",
-            left_on=["target_year", "target"],
-            right_on=["year", "class"],
-        )["id"]
-
-        # Calculate the proportion of each class in each year
-        melted = self.data.melt(var_name="year")
-        melted = melted.groupby(["year", "value"]).size().reset_index(name="count")
-        melted["proportion_of_total"] = (
-            melted.groupby("year")["count"]
-            .transform(lambda x: x / x.sum())
-            .apply(lambda x: f"{x:.0%}")
-        )
-        all_classes = all_classes.merge(
-            melted, left_on=["year", "class"], right_on=["year", "value"]
-        )
-
-        if self.label_type == "class":
-            all_classes["label"] = all_classes["class"].apply(lambda k: self.labels[k])
-        elif self.label_type == "percent":
-            all_classes["label"] = all_classes["proportion_of_total"]
-        elif self.label_type == "count":
-            all_classes["label"] = all_classes["count"]
-        elif not self.label_type:
-            all_classes["label"] = ""
-        else:
-            raise ValueError(
-                "Invalid label_type. Choose from 'class', 'percent', 'count', or False."
-            )
-
-        return SankeyParameters(
-            node_labels=all_classes.year,
-            link_labels=df.link_label,
-            node_palette=all_classes.color,
-            link_palette=df.source_color,
-            label=all_classes.label,
-            source=df.source_id,
-            target=df.target_id,
-            value=df.changed,
-        )
-
-    def generate_dataframe(self) -> pd.DataFrame:
-        """Convert raw sampling data to a formatted dataframe"""
-        data = self.data.copy()
-
-        if self.hide:
-            hide_mask = pd.concat([(data == i).any(axis=1) for i in self.hide], axis=1).any(axis=1)
-            data = data[~hide_mask]
-
-        permutations = []
-        # Get all unique class-year combinations
-        for source, target in utils.pairwise(data.columns):
-            permutations += list(
-                zip([source] * len(data), [target] * len(data), data[source], data[target])
-            )
-        df = pd.DataFrame(permutations, columns=["source_year", "target_year", "source", "target"])
-
-        # Count the unique combinations of all four fields
-        df = (
-            df.groupby(["source_year", "target_year", "source", "target"])
-            .size()
-            .reset_index()
-            .rename(columns={0: "changed"})
-        )
-        # Count the total number of source samples in each year
-        df["total"] = df.groupby(["source_year", "source"]).changed.transform(sum)
-        # Calculate what percent of the source samples went into each target class
-        df["proportion"] = df["changed"] / df["total"]
-
-        # Join the class labels and colors to the class IDs
-        df["source_label"] = df.source.apply(lambda k: self.labels[k])
-        df["target_label"] = df.target.apply(lambda k: self.labels[k])
-        df["source_color"] = df.source.apply(lambda k: self.palette[k])
-        df["target_color"] = df.target.apply(lambda k: self.palette[k])
-
-        def build_link_label(row: pd.Series) -> str:
-            # Early exit in case all classes are excluded
-            if row.shape[0] == 0:
-                return ""
-
-            verb = "remained" if row.source == row.target else "became"
-            pct = f"{row.proportion:.0%}"
-            return f"<b>{pct}</b> of <b>{row.source_label}</b> {verb} <b>{row.target_label}</b>"
-
-        # Describe the class changes
-        df["link_label"] = df.apply(build_link_label, axis=1)
-
-        return df
-
-    @property
-    def _view_name(self):
-        """When the Sankey object is displayed by IPython, render the plot"""
-        return self.gui._view_name
-
-    @property
-    def _model_id(self):
-        """When the Sankey object is displayed by IPython, render the plot"""
-        return self.gui._model_id
-
-    def update_layout(self, *args, **kwargs):
-        """Pass layout changes to the plot. This is primarily kept for compatibility with geemap."""
-        self.plot.update_layout(*args, **kwargs)
-
-    def generate_gui(self):
-        BUTTON_HEIGHT = "24px"
-        BUTTON_WIDTH = "24px"
-
-        unique_classes = self.get_sorted_classes()
-
-        def toggle_button(button):
-            button.toggle()
-
-            class_name = button.tooltip
-            class_id = [key for key in self.labels.keys() if self.labels[key] == class_name][0]
-
-            if not button.state:
-                self.hide.append(class_id)
-            else:
-                self.hide.remove(class_id)
-
-            update_plot()
-
-        def update_plot():
-            """Swap new data into the plot"""
-            new_plot = self.generate_plot()
-            self.plot.data[0].link = new_plot.data[0].link
-            self.plot.data[0].node = new_plot.data[0].node
-
-        buttons = []
-        active_classes = self.get_active_classes()
-        for i in unique_classes:
-            label = self.labels[i]
-            on_color = self.palette[i]
-            state = i in active_classes
-
-            button = utils.ColorToggleButton(tooltip=label, on_color=on_color, state=state)
-            button.layout.width = BUTTON_WIDTH
-            button.layout.height = BUTTON_HEIGHT
-
-            button.on_click(toggle_button)
-            buttons.append(button)
-
-        def reset_plot(_):
-            for button in buttons:
-                if not button.state:
-                    button.click()
-
-        reset_button = widgets.Button(
-            icon="refresh",
-            tooltip="Reset plot",
-            layout=widgets.Layout(height=BUTTON_HEIGHT, width=BUTTON_WIDTH, padding="0 0 0 3px"),
-        )
-        reset_button.on_click(reset_plot)
-
-        open_button = widgets.Button(
-            icon="external-link",
-            tooltip="Open in new tab",
-            layout=widgets.Layout(height=BUTTON_HEIGHT, width=BUTTON_WIDTH, padding="0 0 0 3px"),
-        )
-        open_button.on_click(
-            lambda _: self.plot.update_layout(width=None, height=None).show(renderer="browser")
-        )
-
-        button_box = widgets.HBox([*buttons, widgets.Label("|"), reset_button, open_button])
-
-        gui = widgets.VBox(
-            [
-                self.plot,
-                widgets.VBox([button_box], layout=widgets.Layout(align_items="center")),
-            ]
-        )
-
-        return gui
-
-    def generate_plot(self) -> go.Figure:
-        self.df = self.generate_dataframe()
-        params = self.generate_plot_parameters()
-
-        theme = (
-            self.theme if isinstance(self.theme, themes.Theme) else themes.load_theme(self.theme)
-        )
-
-        node_kwargs = dict(
-            customdata=params.node_labels,
-            hovertemplate="<b>%{customdata}</b><extra></extra>",
-            label=[f"<span style='{theme.label_style}'>{s}</span>" for s in params.label],
-            color=params.node_palette,
-        )
-        link_kwargs = dict(
-            source=params.source,
-            target=params.target,
-            value=params.value,
-            color=params.link_palette,
-            customdata=params.link_labels,
-            hovertemplate="%{customdata} <extra></extra>",
-        )
-
-        fig = go.FigureWidget(
-            data=[
-                go.Sankey(
-                    arrangement="snap",
-                    node={**node_kwargs, **theme.node_kwargs},
-                    link={**link_kwargs, **theme.link_kwargs},
-                )
-            ]
-        )
-
-        fig.update_layout(
-            title_text=f"<span style='{theme.title_style}'>{self.title}</span>"
-            if self.title
-            else None,
-            font_size=16,
-            title_x=0.5,
-            paper_bgcolor="rgba(0, 0, 0, 0)",
-        )
-
-        return fig
+from collections import namedtuple
+from typing import Dict, List, Union
+
+import ee
+import ipywidgets as widgets
+import pandas as pd
+import plotly.graph_objects as go
+
+from sankee import sampling, themes, utils
+
+SankeyParameters = namedtuple(
+    "SankeyParameters",
+    [
+        "node_labels",
+        "link_labels",
+        "node_palette",
+        "link_palette",
+        "label",
+        "source",
+        "target",
+        "value",
+    ],
+)
+
+
+def sankify(
+    image_list: List[ee.Image],
+    band: str,
+    labels: Dict[int, str],
+    palette: Dict[int, str],
+    region: Union[None, ee.Geometry] = None,
+    label_list: Union[None, List[str]] = None,
+    max_classes: Union[None, int] = None,
+    n: int = 500,
+    title: Union[None, str] = None,
+    scale: Union[None, int] = None,
+    seed: int = 0,
+    label_type: Union[None, str] = "class",
+    theme: Union[str, themes.Theme] = "default",
+) -> go.Figure:
+    """
+    Generate an interactive Sankey plot showing land cover change over time from a series of images.
+
+    Parameters
+    ----------
+    image_list : List[ee.Image]
+        An ordered list of images representing a time series of classified data. Each image will be
+        sampled to generate the Sankey plot. Any length of list is allowed, but lists with more than
+        3 or 4 images may produce unusable plots.
+    band : str
+        The name of the band in all images of image_list that contains classified data.
+    labels : dict
+        The labels associated with each value of all images in image_list. Any values not defined
+        in the labels will be dropped from the sampled data.
+    palette : dict
+        The colors associated with each value of all images in image_list.
+    region : ee.Geometry, default None
+        A region to generate samples within. The region must overlap all images. If none is
+        provided, the geometry of the first image will be used. For this to work, images must be
+        bounded.
+    label_list : List[str], default None
+        An ordered list of labels corresponding to the images. The list must be the same length as
+        image_list. If none is provided, sequential numeric labels will be automatically assigned
+        starting at 0. Labels are displayed on-hover on the Sankey nodes.
+    max_classes : int, default None
+        If a value is provided, small classes will be removed until max_classes remain. Class size
+        is calculated based on total times sampled in the time series.
+    n : int, default 500
+        The number of sample points to randomly generate for characterizing all images. More samples
+        will provide more representative data but will take longer to process.
+    title : str, default None
+        An optional title that will be displayed above the Sankey plot.
+    scale : int, default None
+        The scale in image units to perform sampling at. If none is provided, GEE will attempt to
+        use the image's nominal scale, which may cause errors depending on the image projection.
+    seed : int, default 0
+        The seed value used to generate repeatable results during random sampling.
+    label_type : str, default "class"
+        The type of label to display for each link, one of "class", "percent", "count", or False.
+        Selecting "class" will use the class label, "percent" will use the proportion of sampled
+        pixels in each class, and "count" will use the number of sampled pixels in each class.
+        False will disable link labels.
+    theme : str or Theme
+        The theme to apply to the Sankey diagram. Can be the name of a built-in theme (e.g. "d3") or
+        a custom `sankee.Theme` object.
+
+    Returns
+    -------
+    plotly.graph_objs._figure.Figure
+        An interactive Sankey plot.
+    """
+    if region is None:
+        region = image_list[0].geometry()
+
+    label_list = label_list if label_list is not None else list(range(len(image_list)))
+    label_list = [str(label) for label in label_list]
+    if len(label_list) != len(image_list):
+        raise ValueError("The number of labels must match the number of images.")
+    if len(set(label_list)) != len(label_list):
+        raise ValueError("All labels in the `label_list` must be unique.")
+
+    data, samples = sampling.generate_sample_data(
+        image_list=image_list,
+        image_labels=label_list,
+        band=band,
+        scale=scale,
+        include=list(labels.keys()),
+        max_classes=max_classes,
+        region=region,
+        n=n,
+        seed=seed,
+    )
+
+    return SankeyPlot(
+        data=data,
+        labels=labels,
+        palette=palette,
+        title=title,
+        samples=samples,
+        label_type=label_type,
+        theme=theme,
+    )
+
+
+class SankeyPlot(widgets.DOMWidget):
+    def __init__(
+        self,
+        data: pd.DataFrame,
+        labels: Dict[int, str],
+        palette: Dict[int, str],
+        title: str,
+        samples: ee.FeatureCollection,
+        label_type: str,
+        theme: Union[str, themes.Theme],
+    ):
+        self.data = data
+        self.labels = labels
+        self.palette = palette
+        self.title = title
+        self.samples = samples
+        self.label_type = label_type
+        self.theme = theme
+
+        self.hide = []
+        # Initialized by `self.generate_plot`
+        self.df = None
+        self.plot = self.generate_plot()
+        self.gui = self.generate_gui()
+
+    def get_sorted_classes(self) -> pd.Series:
+        """Return all unique class values, sorted by the total number of observations."""
+        start_count = (
+            self.df.loc[:, ["source", "total"]]
+            .groupby("source")
+            .mean()
+            .reset_index()[["source", "total"]]
+            .rename(columns={"source": "class", "total": "count"})
+        )
+        end_count = (
+            self.df.loc[:, ["target", "changed"]]
+            .groupby("target")
+            .sum()
+            .reset_index()[["target", "changed"]]
+            .rename(columns={"target": "class", "changed": "count"})
+        )
+        total_count = pd.concat([start_count, end_count]).groupby("class").sum().reset_index()
+
+        return total_count.sort_values(by="count", ascending=False)["class"].reset_index(drop=True)
+
+    def get_active_classes(self) -> pd.Series:
+        """Return all unique active, visibile class values after filtering."""
+        return self.df[["source", "target"]].melt().value.unique()
+
+    def generate_plot_parameters(self) -> SankeyParameters:
+        """Generate Sankey plot parameters from a formatted, cleaned dataframe"""
+        df = self.df.copy()
+
+        source_df = df[["source", "source_year"]].rename(
+            columns={"source": "class", "source_year": "year"}
+        )
+        target_df = df[["target", "target_year"]].rename(
+            columns={"target": "class", "target_year": "year"}
+        )
+        all_classes = pd.concat([source_df, target_df])
+
+        all_classes = all_classes.drop_duplicates().reset_index(drop=True)
+        all_classes["color"] = all_classes["class"].apply(lambda k: self.palette[k]).tolist()
+        all_classes["id"] = all_classes.groupby(["year", "class"], sort=False).ngroup()
+
+        # Join the sequential class-year IDs to the dataframe
+        df["source_id"] = pd.merge(
+            left=df,
+            right=all_classes,
+            how="left",
+            left_on=["source_year", "source"],
+            right_on=["year", "class"],
+        )["id"]
+        df["target_id"] = pd.merge(
+            left=df,
+            right=all_classes,
+            how="left",
+            left_on=["target_year", "target"],
+            right_on=["year", "class"],
+        )["id"]
+
+        # Calculate the proportion of each class in each year
+        melted = self.data.melt(var_name="year")
+        melted = melted.groupby(["year", "value"]).size().reset_index(name="count")
+        melted["proportion_of_total"] = (
+            melted.groupby("year")["count"]
+            .transform(lambda x: x / x.sum())
+            .apply(lambda x: f"{x:.0%}")
+        )
+        all_classes = all_classes.merge(
+            melted, left_on=["year", "class"], right_on=["year", "value"]
+        )
+
+        if self.label_type == "class":
+            all_classes["label"] = all_classes["class"].apply(lambda k: self.labels[k])
+        elif self.label_type == "percent":
+            all_classes["label"] = all_classes["proportion_of_total"]
+        elif self.label_type == "count":
+            all_classes["label"] = all_classes["count"]
+        elif not self.label_type:
+            all_classes["label"] = ""
+        else:
+            raise ValueError(
+                "Invalid label_type. Choose from 'class', 'percent', 'count', or False."
+            )
+
+        return SankeyParameters(
+            node_labels=all_classes.year,
+            link_labels=df.link_label,
+            node_palette=all_classes.color,
+            link_palette=df.source_color,
+            label=all_classes.label,
+            source=df.source_id,
+            target=df.target_id,
+            value=df.changed,
+        )
+
+    def generate_dataframe(self) -> pd.DataFrame:
+        """Convert raw sampling data to a formatted dataframe"""
+        data = self.data.copy()
+
+        if self.hide:
+            hide_mask = pd.concat([(data == i).any(axis=1) for i in self.hide], axis=1).any(axis=1)
+            data = data[~hide_mask]
+
+        permutations = []
+        # Get all unique class-year combinations
+        for source, target in utils.pairwise(data.columns):
+            permutations += list(
+                zip([source] * len(data), [target] * len(data), data[source], data[target])
+            )
+        df = pd.DataFrame(permutations, columns=["source_year", "target_year", "source", "target"])
+
+        # Count the unique combinations of all four fields
+        df = (
+            df.groupby(["source_year", "target_year", "source", "target"])
+            .size()
+            .reset_index()
+            .rename(columns={0: "changed"})
+        )
+        # Count the total number of source samples in each year
+        df["total"] = df.groupby(["source_year", "source"]).changed.transform(sum)
+        # Calculate what percent of the source samples went into each target class
+        df["proportion"] = df["changed"] / df["total"]
+
+        # Join the class labels and colors to the class IDs
+        df["source_label"] = df.source.apply(lambda k: self.labels[k])
+        df["target_label"] = df.target.apply(lambda k: self.labels[k])
+        df["source_color"] = df.source.apply(lambda k: self.palette[k])
+        df["target_color"] = df.target.apply(lambda k: self.palette[k])
+
+        def build_link_label(row: pd.Series) -> str:
+            # Early exit in case all classes are excluded
+            if row.shape[0] == 0:
+                return ""
+
+            verb = "remained" if row.source == row.target else "became"
+            pct = f"{row.proportion:.0%}"
+            return f"<b>{pct}</b> of <b>{row.source_label}</b> {verb} <b>{row.target_label}</b>"
+
+        # Describe the class changes
+        df["link_label"] = df.apply(build_link_label, axis=1)
+
+        return df
+
+    @property
+    def _view_name(self):
+        """When the Sankey object is displayed by IPython, render the plot"""
+        return self.gui._view_name
+
+    @property
+    def _model_id(self):
+        """When the Sankey object is displayed by IPython, render the plot"""
+        return self.gui._model_id
+
+    def update_layout(self, *args, **kwargs):
+        """Pass layout changes to the plot. This is primarily kept for compatibility with geemap."""
+        self.plot.update_layout(*args, **kwargs)
+
+    def generate_gui(self):
+        BUTTON_HEIGHT = "24px"
+        BUTTON_WIDTH = "24px"
+
+        unique_classes = self.get_sorted_classes()
+
+        def toggle_button(button):
+            button.toggle()
+
+            class_name = button.tooltip
+            class_id = [key for key in self.labels.keys() if self.labels[key] == class_name][0]
+
+            if not button.state:
+                self.hide.append(class_id)
+            else:
+                self.hide.remove(class_id)
+
+            update_plot()
+
+        def update_plot():
+            """Swap new data into the plot"""
+            new_plot = self.generate_plot()
+            self.plot.data[0].link = new_plot.data[0].link
+            self.plot.data[0].node = new_plot.data[0].node
+
+        buttons = []
+        active_classes = self.get_active_classes()
+        for i in unique_classes:
+            label = self.labels[i]
+            on_color = self.palette[i]
+            state = i in active_classes
+
+            button = utils.ColorToggleButton(tooltip=label, on_color=on_color, state=state)
+            button.layout.width = BUTTON_WIDTH
+            button.layout.height = BUTTON_HEIGHT
+
+            button.on_click(toggle_button)
+            buttons.append(button)
+
+        def reset_plot(_):
+            for button in buttons:
+                if not button.state:
+                    button.click()
+
+        reset_button = widgets.Button(
+            icon="refresh",
+            tooltip="Reset plot",
+            layout=widgets.Layout(height=BUTTON_HEIGHT, width=BUTTON_WIDTH, padding="0 0 0 3px"),
+        )
+        reset_button.on_click(reset_plot)
+
+        open_button = widgets.Button(
+            icon="external-link",
+            tooltip="Open in new tab",
+            layout=widgets.Layout(height=BUTTON_HEIGHT, width=BUTTON_WIDTH, padding="0 0 0 3px"),
+        )
+        open_button.on_click(
+            lambda _: self.plot.update_layout(width=None, height=None).show(renderer="browser")
+        )
+
+        button_box = widgets.HBox([*buttons, widgets.Label("|"), reset_button, open_button])
+
+        gui = widgets.VBox(
+            [
+                self.plot,
+                widgets.VBox([button_box], layout=widgets.Layout(align_items="center")),
+            ]
+        )
+
+        return gui
+
+    def generate_plot(self) -> go.Figure:
+        self.df = self.generate_dataframe()
+        params = self.generate_plot_parameters()
+
+        theme = (
+            self.theme if isinstance(self.theme, themes.Theme) else themes.load_theme(self.theme)
+        )
+
+        node_kwargs = dict(
+            customdata=params.node_labels,
+            hovertemplate="<b>%{customdata}</b><extra></extra>",
+            label=[f"<span style='{theme.label_style}'>{s}</span>" for s in params.label],
+            color=params.node_palette,
+        )
+        link_kwargs = dict(
+            source=params.source,
+            target=params.target,
+            value=params.value,
+            color=params.link_palette,
+            customdata=params.link_labels,
+            hovertemplate="%{customdata} <extra></extra>",
+        )
+
+        fig = go.FigureWidget(
+            data=[
+                go.Sankey(
+                    arrangement="snap",
+                    node={**node_kwargs, **theme.node_kwargs},
+                    link={**link_kwargs, **theme.link_kwargs},
+                )
+            ]
+        )
+
+        fig.update_layout(
+            title_text=f"<span style='{theme.title_style}'>{self.title}</span>"
+            if self.title
+            else None,
+            font_size=16,
+            title_x=0.5,
+            paper_bgcolor="rgba(0, 0, 0, 0)",
+        )
+
+        return fig
```

### Comparing `sankee-0.2.3/sankee/themes.py` & `sankee-0.2.4/sankee/themes.py`

 * *Ordering differences only*

 * *Files 18% similar despite different names*

```diff
@@ -1,132 +1,132 @@
-from typing import Dict, Union
-
-
-class Theme:
-    """
-    Attributes
-    ----------
-    label_style : str, optional
-        CSS style for the node labels.
-    title_style : str, optional
-        CSS style for the figure title.
-    node_kwargs : dict, optional
-        Keyword arguments applied to Sankey nodes. See the `Plotly Sankey.node documentation
-        <https://plotly.com/python/reference/sankey/#sankey-node>`_ for details.
-    link_kwargs : dict, optional
-        Keyword arguments applied to Sankey links. See the `Plotly Sankey.link documentation
-        <https://plotly.com/python/reference/sankey/#sankey-link>`_ for details.
-
-    Examples
-    --------
-    >>> theme = Theme(
-    ...     label_style=\"""
-    ...         color: #fff;
-    ...         font-weight: 600;
-    ...         letter-spacing: -1px;
-    ...         text-shadow:
-    ...             0 0 4px black,
-    ...             -1px 1px 0 #76777a,
-    ...             1px 1px 0 #76777a,
-    ...             1px -1px 0 #76777a,
-    ...             -1px -1px 0 #76777a;
-    ...     \""",
-    ...     title_style=\"""
-    ...         color: #fff;
-    ...         font-weight: 900;
-    ...         word-spacing: 10px;
-    ...         letter-spacing: 3px;
-    ...         text-shadow:
-    ...             0 0 1px black,
-    ...             0 0 2px black,
-    ...             0 0 4px black;
-    ...     \""",
-    ...     node_kwargs=dict(
-    ...         pad=30,
-    ...         thickness=10,
-    ...         line=dict(color="#505050", width=1.5),
-    ...     ),
-    ...     link_kwargs=dict(
-    ...         line=dict(color="#909090", width=1),
-    ...     ),
-    ... )
-    """
-
-    def __init__(
-        self,
-        label_style: Union[None, str] = None,
-        title_style: Union[None, str] = None,
-        node_kwargs: Union[None, Dict] = None,
-        link_kwargs: Union[None, Dict] = None,
-    ):
-
-        self.label_style = label_style
-        self.title_style = title_style
-        self.node_kwargs = node_kwargs if node_kwargs is not None else {}
-        self.link_kwargs = link_kwargs if link_kwargs is not None else {}
-
-
-DEFAULT = Theme(
-    node_kwargs=dict(
-        pad=30,
-        thickness=10,
-        line=dict(color="#505050", width=1.5),
-    ),
-    link_kwargs=dict(
-        line=dict(color="#909090", width=1),
-    ),
-    label_style="""
-        color: #fff;
-        font-weight: 600;
-        letter-spacing: -1px;
-        text-shadow:
-            0 0 4px black,
-            -1px 1px 0 #76777a,
-            1px 1px 0 #76777a,
-            1px -1px 0 #76777a,
-            -1px -1px 0 #76777a;
-    """,
-    title_style="""
-        color: #fff;
-        font-weight: 900;
-        word-spacing: 10px;
-        letter-spacing: 3px;
-        text-shadow:
-            0 0 1px black,
-            0 0 2px black,
-            0 0 4px black;
-    """,
-)
-
-
-D3 = Theme(
-    node_kwargs=dict(line=dict(width=1), pad=20, thickness=15),
-    link_kwargs=dict(color="rgba(120, 120, 120, 0.25)"),
-)
-
-SIMPLE = Theme(
-    node_kwargs=dict(line=dict(width=0), pad=60, thickness=30),
-    link_kwargs=dict(color="rgba(120, 120, 120, 0.25)"),
-    label_style="""
-        color: #666666;
-        font-size: 18px;
-        color: #666666;
-    """,
-    title_style="""
-        color: #666666;
-        font-size: 24px;
-        font-weight: 900;
-    """,
-)
-
-
-THEMES = {
-    "default": DEFAULT,
-    "d3": D3,
-    "simple": SIMPLE,
-}
-
-
-def load_theme(theme_name):
-    if theme_name not in THEMES:
-        raise ValueError(f"Theme `{theme_name}` not found. Choose from {list(THEMES.keys())}.")
-    return THEMES[theme_name]
+from typing import Dict, Union
+
+
+class Theme:
+    """
+    Attributes
+    ----------
+    label_style : str, optional
+        CSS style for the node labels.
+    title_style : str, optional
+        CSS style for the figure title.
+    node_kwargs : dict, optional
+        Keyword arguments applied to Sankey nodes. See the `Plotly Sankey.node documentation
+        <https://plotly.com/python/reference/sankey/#sankey-node>`_ for details.
+    link_kwargs : dict, optional
+        Keyword arguments applied to Sankey links. See the `Plotly Sankey.link documentation
+        <https://plotly.com/python/reference/sankey/#sankey-link>`_ for details.
+
+    Examples
+    --------
+    >>> theme = Theme(
+    ...     label_style=\"""
+    ...         color: #fff;
+    ...         font-weight: 600;
+    ...         letter-spacing: -1px;
+    ...         text-shadow:
+    ...             0 0 4px black,
+    ...             -1px 1px 0 #76777a,
+    ...             1px 1px 0 #76777a,
+    ...             1px -1px 0 #76777a,
+    ...             -1px -1px 0 #76777a;
+    ...     \""",
+    ...     title_style=\"""
+    ...         color: #fff;
+    ...         font-weight: 900;
+    ...         word-spacing: 10px;
+    ...         letter-spacing: 3px;
+    ...         text-shadow:
+    ...             0 0 1px black,
+    ...             0 0 2px black,
+    ...             0 0 4px black;
+    ...     \""",
+    ...     node_kwargs=dict(
+    ...         pad=30,
+    ...         thickness=10,
+    ...         line=dict(color="#505050", width=1.5),
+    ...     ),
+    ...     link_kwargs=dict(
+    ...         line=dict(color="#909090", width=1),
+    ...     ),
+    ... )
+    """
+
+    def __init__(
+        self,
+        label_style: Union[None, str] = None,
+        title_style: Union[None, str] = None,
+        node_kwargs: Union[None, Dict] = None,
+        link_kwargs: Union[None, Dict] = None,
+    ):
+
+        self.label_style = label_style
+        self.title_style = title_style
+        self.node_kwargs = node_kwargs if node_kwargs is not None else {}
+        self.link_kwargs = link_kwargs if link_kwargs is not None else {}
+
+
+DEFAULT = Theme(
+    node_kwargs=dict(
+        pad=30,
+        thickness=10,
+        line=dict(color="#505050", width=1.5),
+    ),
+    link_kwargs=dict(
+        line=dict(color="#909090", width=1),
+    ),
+    label_style="""
+        color: #fff;
+        font-weight: 600;
+        letter-spacing: -1px;
+        text-shadow:
+            0 0 4px black,
+            -1px 1px 0 #76777a,
+            1px 1px 0 #76777a,
+            1px -1px 0 #76777a,
+            -1px -1px 0 #76777a;
+    """,
+    title_style="""
+        color: #fff;
+        font-weight: 900;
+        word-spacing: 10px;
+        letter-spacing: 3px;
+        text-shadow:
+            0 0 1px black,
+            0 0 2px black,
+            0 0 4px black;
+    """,
+)
+
+
+D3 = Theme(
+    node_kwargs=dict(line=dict(width=1), pad=20, thickness=15),
+    link_kwargs=dict(color="rgba(120, 120, 120, 0.25)"),
+)
+
+SIMPLE = Theme(
+    node_kwargs=dict(line=dict(width=0), pad=60, thickness=30),
+    link_kwargs=dict(color="rgba(120, 120, 120, 0.25)"),
+    label_style="""
+        color: #666666;
+        font-size: 18px;
+        color: #666666;
+    """,
+    title_style="""
+        color: #666666;
+        font-size: 24px;
+        font-weight: 900;
+    """,
+)
+
+
+THEMES = {
+    "default": DEFAULT,
+    "d3": D3,
+    "simple": SIMPLE,
+}
+
+
+def load_theme(theme_name):
+    if theme_name not in THEMES:
+        raise ValueError(f"Theme `{theme_name}` not found. Choose from {list(THEMES.keys())}.")
+    return THEMES[theme_name]
```

### Comparing `sankee-0.2.3/sankee/utils.py` & `sankee-0.2.4/sankee/utils.py`

 * *Ordering differences only*

 * *Files 13% similar despite different names*

```diff
@@ -1,54 +1,54 @@
-import itertools
-from collections import Counter
-from typing import List
-
-import ee
-import ipywidgets as widgets
-
-
-def pairwise(iterable):
-    """Polyfill itertools.pairwise for pre 3.10.
-
-    https://docs.python.org/3/library/itertools.html#itertools.pairwise
-    """
-    a, b = itertools.tee(iterable)
-    next(b, None)
-    return zip(a, b)
-
-
-def get_shared_bands(images: List[ee.Image]) -> List[str]:
-    """Get the list of bands that are shared by all images in the list.
-
-    Args:
-        img_list: List of ee.Image objects.
-
-    Returns:
-        List of band names.
-    """
-    band_counts = Counter(itertools.chain(*[img.bandNames().getInfo() for img in images]))
-    return [band for band, count in band_counts.items() if count == len(images)]
-
-
-class ColorToggleButton(widgets.Button):
-    """
-    The ipywidgets.ToggleButton doesn't support a `button_color` style, so this turns a standard
-    ipywidgets.Button into a toggle button.
-    """
-
-    def __init__(self, *args, on_color, off_color=None, state=True, **kwargs):
-        super().__init__(*args, **kwargs)
-        self.state = state
-        self.on_color = on_color
-        # Set an alpha value for the default off color
-        self.off_color = off_color if off_color is not None else f"{on_color}20"
-        current_color = on_color if state else self.off_color
-        self.style.button_color = current_color
-        self.layout.border = f"1px dashed {self.on_color}"
-
-    def toggle(self):
-        self.state = not self.state
-        self.update()
-
-    def update(self):
-        color = self.on_color if self.state else self.off_color
-        self.style.button_color = color
+import itertools
+from collections import Counter
+from typing import List
+
+import ee
+import ipywidgets as widgets
+
+
+def pairwise(iterable):
+    """Polyfill itertools.pairwise for pre 3.10.
+
+    https://docs.python.org/3/library/itertools.html#itertools.pairwise
+    """
+    a, b = itertools.tee(iterable)
+    next(b, None)
+    return zip(a, b)
+
+
+def get_shared_bands(images: List[ee.Image]) -> List[str]:
+    """Get the list of bands that are shared by all images in the list.
+
+    Args:
+        img_list: List of ee.Image objects.
+
+    Returns:
+        List of band names.
+    """
+    band_counts = Counter(itertools.chain(*[img.bandNames().getInfo() for img in images]))
+    return [band for band, count in band_counts.items() if count == len(images)]
+
+
+class ColorToggleButton(widgets.Button):
+    """
+    The ipywidgets.ToggleButton doesn't support a `button_color` style, so this turns a standard
+    ipywidgets.Button into a toggle button.
+    """
+
+    def __init__(self, *args, on_color, off_color=None, state=True, **kwargs):
+        super().__init__(*args, **kwargs)
+        self.state = state
+        self.on_color = on_color
+        # Set an alpha value for the default off color
+        self.off_color = off_color if off_color is not None else f"{on_color}20"
+        current_color = on_color if state else self.off_color
+        self.style.button_color = current_color
+        self.layout.border = f"1px dashed {self.on_color}"
+
+    def toggle(self):
+        self.state = not self.state
+        self.update()
+
+    def update(self):
+        color = self.on_color if self.state else self.off_color
+        self.style.button_color = color
```

### Comparing `sankee-0.2.3/sankee.egg-info/PKG-INFO` & `sankee-0.2.4/sankee.egg-info/PKG-INFO`

 * *Files 13% similar despite different names*

```diff
@@ -1,144 +1,144 @@
-Metadata-Version: 2.1
-Name: sankee
-Version: 0.2.3
-Summary: Visualize classified time series data with interactive Sankey plots in Google Earth Engine.
-Home-page: https://github.com/aazuspan/sankee
-Author: Aaron Zuspan
-Author-email: aa.zuspan@gmail.com
-License: UNKNOWN
-Project-URL: Bug Reports, https://github.com/aazuspan/sankee/issues
-Project-URL: Source, https://github.com/aazuspan/sankee/
-Keywords: sankey land cover visualization
-Platform: UNKNOWN
-Classifier: Development Status :: 3 - Alpha
-Classifier: Intended Audience :: Science/Research
-Classifier: Topic :: Scientific/Engineering
-Classifier: License :: OSI Approved :: MIT License
-Classifier: Programming Language :: Python :: 3
-Classifier: Programming Language :: Python :: 3.7
-Classifier: Programming Language :: Python :: 3.8
-Classifier: Programming Language :: Python :: 3.9
-Classifier: Programming Language :: Python :: 3.10
-Requires-Python: >=3.7
-Description-Content-Type: text/markdown
-Provides-Extra: doc
-Provides-Extra: dev
-Provides-Extra: test
-License-File: LICENSE
-
-# sankee
-
-[![Earth Engine Python](https://img.shields.io/badge/Earth%20Engine%20API-Python-green)](https://developers.google.com/earth-engine/tutorials/community/intro-to-python-api)
-[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/aazuspan/sankee/HEAD?filepath=docs%2Fexamples%2Fmodis_snow_and_ice.ipynb)
-[![conda-forge link](https://img.shields.io/conda/vn/conda-forge/sankee)](https://anaconda.org/conda-forge/sankee)
-[![conda-forge link](https://img.shields.io/pypi/v/sankee)](https://pypi.org/project/sankee)
-[![Testing workflow](https://github.com/aazuspan/sankee/actions/workflows/test.yml/badge.svg)](https://github.com/aazuspan/sankee/actions/workflows/test.yml)
-[![codecov](https://codecov.io/gh/aazuspan/sankee/branch/main/graph/badge.svg?token=39REP2HZQC)](https://codecov.io/gh/aazuspan/sankee)
-[![Read the Docs](https://readthedocs.org/projects/sankee/badge/?version=latest&style=flat)](https://sankee.readthedocs.io/en/latest/?badge=latest)
-[![Downloads](https://pepy.tech/badge/sankee)](https://pepy.tech/project/sankee)
-
-Visualize changes in classified time series data with interactive Sankey plots in Google Earth Engine
-
-![Sankee example showing grassland expansion in the Nile Delta](docs/_static/demo.gif)
-
-## Description
-
-Use [Earth Engine](https://github.com/google/earthengine-api) to visualize changes in land cover, plant health, burn severity, or any other time series of classified imagery with interactive Sankey plots. Use a library of [built-in datasets](https://sankee.readthedocs.io/en/latest/sankee.html#premade-datasets) for convenience or define your own [custom datasets](https://sankee.readthedocs.io/en/latest/sankee.html#custom-datasets) for flexibility.
-
-
-## Installation
-
-### Pip
-
-```bash
-pip install sankee
-```
-
-### Conda
-
-```bash
-conda install -c conda-forge sankee
-```
-
-## Quickstart
-
-### Premade Datasets
-
-Visualize annual changes in land cover using [popular LULC datasets](https://sankee.readthedocs.io/en/latest/sankee.html#supported-datasets) with a couple lines of code. Just choose a dataset, an area of interest, and a list of years to generate a Sankey diagram from a premade dataset. Below, we can look at 30 years of vegetation recovery in the area devastated by the Mt. St. Helens eruption.
-
-```python
-import sankee
-import ee
-
-ee.Initialize()
-
-sankee.datasets.LCMS_LC.sankify(
-  years=[1990, 2000, 2010, 2020],
-  region=ee.Geometry.Point([-122.192688, 46.25917]).buffer(2000),
-  max_classes=3,
-  title="Mt. St. Helens Recovery"
-)
-```
-
-![Proportions of land cover over 4 periods increase from barren to grass and tree cover in a Sankey diagram](docs/_static/helens_recovery.png)
-
-Check out the [example notebook](https://sankee.readthedocs.io/en/latest/examples/modis_snow_and_ice.html) for an interactive demo.
-
-### Custom Datasets
-
-Any classified images can be used by defining the dataset parameters (which pixel values correspond to which labels and colors). For example, we can look at classified [Dynamic World](https://developers.google.com/earth-engine/datasets/catalog/GOOGLE_DYNAMICWORLD_V1) scenes just two weeks apart that show substantial snow loss on Mountain Jefferson during the 2021 Heat Dome in the Pacific Northwest.
-
-```python
-import sankee
-import ee
-
-ee.Initialize()
-
-# Load a set of classified images
-img_list = [
-    ee.Image("GOOGLE/DYNAMICWORLD/V1/20210616T185919_20210616T190431_T10TEQ"),
-    ee.Image("GOOGLE/DYNAMICWORLD/V1/20210706T185919_20210706T190638_T10TEQ")
-]
-
-# Which band contains the classified data?
-band = "label"
-
-# What labels correspond to which pixel values?
-labels = {
-    0: "Water", 1: "Trees", 2: "Grass", 3: "Flooded", 4: "Crops",
-    5: "Shrub / Scrub", 6: "Build", 7: "Bare", 8: "Snow / Ice",
-}
-
-# What colors should be applied to which pixel values?
-palette = {
-    0: "#419BDF", 1: "#397D49", 2: "#88B053", 3: "#7A87C6", 4: "#E49635",
-    5: "#DFC35A", 6: "#C4281B", 7: "#A59B8F", 8: "#B39FE1"
-}
-
-plot = sankee.sankify(
-    image_list=img_list, 
-    band=band, 
-    labels=labels,
-    palette=palette,
-    region=ee.Geometry.Point([-121.80183, 44.67655]).buffer(3000), 
-    max_classes=3,
-    title="Mt. Jefferson Snow Loss - June 2021"
-)
-```
-
-![](docs/_static/jefferson_snow.png)
-
-### Integration with geemap
-
-`sankee` premade datasets are usable through the [geemap](https://github.com/giswqs/geemap) interactive GUI. Check out the [documentation](https://geemap.org/notebooks/75_sankee/) and [video tutorials](https://www.youtube.com/watch?v=IZWpJYX6w8I) by [@giswqs](https://github.com/giswqs).
-
-
-## Contributing
-
-If you find bugs or have feature requests, please open an issue!
-
----
-
-[Top](https://github.com/aazuspan/sankee#sankee)
-
-
+Metadata-Version: 2.1
+Name: sankee
+Version: 0.2.4
+Summary: Visualize classified time series data with interactive Sankey plots in Google Earth Engine.
+Home-page: https://github.com/aazuspan/sankee
+Author: Aaron Zuspan
+Author-email: aa.zuspan@gmail.com
+License: UNKNOWN
+Project-URL: Bug Reports, https://github.com/aazuspan/sankee/issues
+Project-URL: Source, https://github.com/aazuspan/sankee/
+Keywords: sankey land cover visualization
+Platform: UNKNOWN
+Classifier: Development Status :: 3 - Alpha
+Classifier: Intended Audience :: Science/Research
+Classifier: Topic :: Scientific/Engineering
+Classifier: License :: OSI Approved :: MIT License
+Classifier: Programming Language :: Python :: 3
+Classifier: Programming Language :: Python :: 3.7
+Classifier: Programming Language :: Python :: 3.8
+Classifier: Programming Language :: Python :: 3.9
+Classifier: Programming Language :: Python :: 3.10
+Requires-Python: >=3.7
+Description-Content-Type: text/markdown
+Provides-Extra: doc
+Provides-Extra: dev
+Provides-Extra: test
+License-File: LICENSE
+
+# sankee
+
+[![Earth Engine Python](https://img.shields.io/badge/Earth%20Engine%20API-Python-green)](https://developers.google.com/earth-engine/tutorials/community/intro-to-python-api)
+[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/aazuspan/sankee/HEAD?filepath=docs%2Fexamples%2Fmodis_snow_and_ice.ipynb)
+[![conda-forge link](https://img.shields.io/conda/vn/conda-forge/sankee)](https://anaconda.org/conda-forge/sankee)
+[![conda-forge link](https://img.shields.io/pypi/v/sankee)](https://pypi.org/project/sankee)
+[![Testing workflow](https://github.com/aazuspan/sankee/actions/workflows/test.yml/badge.svg)](https://github.com/aazuspan/sankee/actions/workflows/test.yml)
+[![codecov](https://codecov.io/gh/aazuspan/sankee/branch/main/graph/badge.svg?token=39REP2HZQC)](https://codecov.io/gh/aazuspan/sankee)
+[![Read the Docs](https://readthedocs.org/projects/sankee/badge/?version=latest&style=flat)](https://sankee.readthedocs.io/en/latest/?badge=latest)
+[![Downloads](https://pepy.tech/badge/sankee)](https://pepy.tech/project/sankee)
+
+Visualize changes in classified time series data with interactive Sankey plots in Google Earth Engine
+
+![Sankee example showing grassland expansion in the Nile Delta](docs/_static/demo.gif)
+
+## Description
+
+Use [Earth Engine](https://github.com/google/earthengine-api) to visualize changes in land cover, plant health, burn severity, or any other time series of classified imagery with interactive Sankey plots. Use a library of [built-in datasets](https://sankee.readthedocs.io/en/latest/sankee.html#premade-datasets) for convenience or define your own [custom datasets](https://sankee.readthedocs.io/en/latest/sankee.html#custom-datasets) for flexibility.
+
+
+## Installation
+
+### Pip
+
+```bash
+pip install sankee
+```
+
+### Conda
+
+```bash
+conda install -c conda-forge sankee
+```
+
+## Quickstart
+
+### Premade Datasets
+
+Visualize annual changes in land cover using [popular LULC datasets](https://sankee.readthedocs.io/en/latest/sankee.html#supported-datasets) with a couple lines of code. Just choose a dataset, an area of interest, and a list of years to generate a Sankey diagram from a premade dataset. Below, we can look at 30 years of vegetation recovery in the area devastated by the Mt. St. Helens eruption.
+
+```python
+import sankee
+import ee
+
+ee.Initialize()
+
+sankee.datasets.LCMS_LC.sankify(
+  years=[1990, 2000, 2010, 2020],
+  region=ee.Geometry.Point([-122.192688, 46.25917]).buffer(2000),
+  max_classes=3,
+  title="Mt. St. Helens Recovery"
+)
+```
+
+![Proportions of land cover over 4 periods increase from barren to grass and tree cover in a Sankey diagram](docs/_static/helens_recovery.png)
+
+Check out the [example notebook](https://sankee.readthedocs.io/en/latest/examples/modis_snow_and_ice.html) for an interactive demo.
+
+### Custom Datasets
+
+Any classified images can be used by defining the dataset parameters (which pixel values correspond to which labels and colors). For example, we can look at classified [Dynamic World](https://developers.google.com/earth-engine/datasets/catalog/GOOGLE_DYNAMICWORLD_V1) scenes just two weeks apart that show substantial snow loss on Mountain Jefferson during the 2021 Heat Dome in the Pacific Northwest.
+
+```python
+import sankee
+import ee
+
+ee.Initialize()
+
+# Load a set of classified images
+img_list = [
+    ee.Image("GOOGLE/DYNAMICWORLD/V1/20210616T185919_20210616T190431_T10TEQ"),
+    ee.Image("GOOGLE/DYNAMICWORLD/V1/20210706T185919_20210706T190638_T10TEQ")
+]
+
+# Which band contains the classified data?
+band = "label"
+
+# What labels correspond to which pixel values?
+labels = {
+    0: "Water", 1: "Trees", 2: "Grass", 3: "Flooded", 4: "Crops",
+    5: "Shrub / Scrub", 6: "Build", 7: "Bare", 8: "Snow / Ice",
+}
+
+# What colors should be applied to which pixel values?
+palette = {
+    0: "#419BDF", 1: "#397D49", 2: "#88B053", 3: "#7A87C6", 4: "#E49635",
+    5: "#DFC35A", 6: "#C4281B", 7: "#A59B8F", 8: "#B39FE1"
+}
+
+plot = sankee.sankify(
+    image_list=img_list, 
+    band=band, 
+    labels=labels,
+    palette=palette,
+    region=ee.Geometry.Point([-121.80183, 44.67655]).buffer(3000), 
+    max_classes=3,
+    title="Mt. Jefferson Snow Loss - June 2021"
+)
+```
+
+![](docs/_static/jefferson_snow.png)
+
+### Integration with geemap
+
+`sankee` premade datasets are usable through the [geemap](https://github.com/giswqs/geemap) interactive GUI. Check out the [documentation](https://geemap.org/notebooks/75_sankee/) and [video tutorials](https://www.youtube.com/watch?v=IZWpJYX6w8I) by [@giswqs](https://github.com/giswqs).
+
+
+## Contributing
+
+If you find bugs or have feature requests, please open an issue!
+
+---
+
+[Top](https://github.com/aazuspan/sankee#sankee)
+
+
```

### Comparing `sankee-0.2.3/setup.py` & `sankee-0.2.4/setup.py`

 * *Files 19% similar despite different names*

```diff
@@ -1,69 +1,69 @@
-from os import path
-
-from setuptools import find_packages, setup
-
-here = path.abspath(path.dirname(__file__))
-
-with open(path.join(here, "README.md"), encoding="utf-8") as f:
-    long_description = f.read()
-
-requirements = [
-    "earthengine-api>=0.1.230",
-    "numpy",
-    "pandas",
-    "plotly>=5.2.2",
-    "ipywidgets",
-]
-doc_requirements = ["nbsphinx", "sphinx", "sphinx_rtd_theme"]
-test_requirements = ["pytest", "coverage", "pytest-cov", "httplib2"]
-dev_requirements = (
-    [
-        "pre-commit",
-        "mypy",
-        "black",
-        "isort",
-        "bumpversion",
-        "twine",
-    ]
-    + doc_requirements
-    + test_requirements
-)
-
-extras_requirements = {
-    "doc": doc_requirements,
-    "dev": dev_requirements,
-    "test": test_requirements,
-}
-
-
-setup(
-    name="sankee",
-    version="0.2.3",
-    description="Visualize classified time series data with interactive Sankey plots in Google Earth Engine.",
-    long_description=long_description,
-    long_description_content_type="text/markdown",
-    url="https://github.com/aazuspan/sankee",
-    author="Aaron Zuspan",
-    author_email="aa.zuspan@gmail.com",
-    classifiers=[
-        "Development Status :: 3 - Alpha",
-        "Intended Audience :: Science/Research",
-        "Topic :: Scientific/Engineering",
-        "License :: OSI Approved :: MIT License",
-        "Programming Language :: Python :: 3",
-        "Programming Language :: Python :: 3.7",
-        "Programming Language :: Python :: 3.8",
-        "Programming Language :: Python :: 3.9",
-        "Programming Language :: Python :: 3.10",
-    ],
-    keywords="sankey land cover visualization",
-    packages=find_packages(include=["sankee", "sankee."]),
-    python_requires=">=3.7",
-    install_requires=requirements,
-    tests_require=test_requirements,
-    extras_require=extras_requirements,
-    project_urls={
-        "Bug Reports": "https://github.com/aazuspan/sankee/issues",
-        "Source": "https://github.com/aazuspan/sankee/",
-    },
-)
+from os import path
+
+from setuptools import find_packages, setup
+
+here = path.abspath(path.dirname(__file__))
+
+with open(path.join(here, "README.md"), encoding="utf-8") as f:
+    long_description = f.read()
+
+requirements = [
+    "earthengine-api>=0.1.230",
+    "numpy",
+    "pandas",
+    "plotly>=5.2.2",
+    "ipywidgets",
+]
+doc_requirements = ["nbsphinx", "sphinx", "sphinx_rtd_theme"]
+test_requirements = ["pytest", "coverage", "pytest-cov", "httplib2"]
+dev_requirements = (
+    [
+        "pre-commit",
+        "mypy",
+        "black",
+        "isort",
+        "bumpversion",
+        "twine",
+    ]
+    + doc_requirements
+    + test_requirements
+)
+
+extras_requirements = {
+    "doc": doc_requirements,
+    "dev": dev_requirements,
+    "test": test_requirements,
+}
+
+
+setup(
+    name="sankee",
+    version="0.2.4",
+    description="Visualize classified time series data with interactive Sankey plots in Google Earth Engine.",
+    long_description=long_description,
+    long_description_content_type="text/markdown",
+    url="https://github.com/aazuspan/sankee",
+    author="Aaron Zuspan",
+    author_email="aa.zuspan@gmail.com",
+    classifiers=[
+        "Development Status :: 3 - Alpha",
+        "Intended Audience :: Science/Research",
+        "Topic :: Scientific/Engineering",
+        "License :: OSI Approved :: MIT License",
+        "Programming Language :: Python :: 3",
+        "Programming Language :: Python :: 3.7",
+        "Programming Language :: Python :: 3.8",
+        "Programming Language :: Python :: 3.9",
+        "Programming Language :: Python :: 3.10",
+    ],
+    keywords="sankey land cover visualization",
+    packages=find_packages(include=["sankee", "sankee."]),
+    python_requires=">=3.7",
+    install_requires=requirements,
+    tests_require=test_requirements,
+    extras_require=extras_requirements,
+    project_urls={
+        "Bug Reports": "https://github.com/aazuspan/sankee/issues",
+        "Source": "https://github.com/aazuspan/sankee/",
+    },
+)
```

