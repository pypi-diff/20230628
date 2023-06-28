# Comparing `tmp/clisops-0.9.5.tar.gz` & `tmp/clisops-0.9.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "clisops-0.9.5.tar", last modified: Wed Dec 14 10:11:58 2022, max compression
+gzip compressed data, was "clisops-0.9.6.tar", last modified: Wed Apr  5 14:20:40 2023, max compression
```

## Comparing `clisops-0.9.5.tar` & `clisops-0.9.6.tar`

### file list

```diff
@@ -1,41 +1,41 @@
-drwxr-xr-x   0 pingu      (501) staff       (20)        0 2022-12-14 10:11:58.265783 clisops-0.9.5/
--rw-r--r--   0 pingu      (501) staff       (20)      612 2022-04-13 09:39:09.000000 clisops-0.9.5/AUTHORS.rst
--rw-r--r--   0 pingu      (501) staff       (20)     4254 2022-07-22 12:14:15.000000 clisops-0.9.5/CONTRIBUTING.rst
--rw-r--r--   0 pingu      (501) staff       (20)    13905 2022-12-14 10:11:19.000000 clisops-0.9.5/HISTORY.rst
--rw-r--r--   0 pingu      (501) staff       (20)     1516 2021-08-26 11:15:07.000000 clisops-0.9.5/LICENSE
--rw-r--r--   0 pingu      (501) staff       (20)      186 2021-08-26 11:15:07.000000 clisops-0.9.5/MANIFEST.in
--rw-r--r--   0 pingu      (501) staff       (20)     3608 2022-12-14 10:11:58.265986 clisops-0.9.5/PKG-INFO
--rw-r--r--   0 pingu      (501) staff       (20)     2052 2022-12-12 12:50:53.000000 clisops-0.9.5/README.rst
-drwxr-xr-x   0 pingu      (501) staff       (20)        0 2022-12-14 10:11:58.246774 clisops-0.9.5/clisops/
--rw-r--r--   0 pingu      (501) staff       (20)     1067 2022-04-12 10:55:27.000000 clisops-0.9.5/clisops/__init__.py
--rw-r--r--   0 pingu      (501) staff       (20)      312 2022-12-14 10:11:19.000000 clisops-0.9.5/clisops/__version__.py
-drwxr-xr-x   0 pingu      (501) staff       (20)        0 2022-12-14 10:11:58.252929 clisops-0.9.5/clisops/core/
--rw-r--r--   0 pingu      (501) staff       (20)      219 2022-02-23 16:44:42.000000 clisops-0.9.5/clisops/core/__init__.py
--rw-r--r--   0 pingu      (501) staff       (20)    10135 2022-12-12 12:50:53.000000 clisops-0.9.5/clisops/core/average.py
--rw-r--r--   0 pingu      (501) staff       (20)    66514 2022-12-14 10:11:19.000000 clisops-0.9.5/clisops/core/subset.py
-drwxr-xr-x   0 pingu      (501) staff       (20)        0 2022-12-14 10:11:58.253823 clisops-0.9.5/clisops/etc/
--rw-r--r--   0 pingu      (501) staff       (20)     1288 2022-02-23 16:44:42.000000 clisops-0.9.5/clisops/etc/roocs.ini
--rw-r--r--   0 pingu      (501) staff       (20)      100 2021-08-26 11:15:07.000000 clisops-0.9.5/clisops/exceptions.py
-drwxr-xr-x   0 pingu      (501) staff       (20)        0 2022-12-14 10:11:58.257892 clisops-0.9.5/clisops/ops/
--rw-r--r--   0 pingu      (501) staff       (20)       56 2022-02-23 16:44:42.000000 clisops-0.9.5/clisops/ops/__init__.py
--rw-r--r--   0 pingu      (501) staff       (20)     5035 2022-12-12 12:50:53.000000 clisops-0.9.5/clisops/ops/average.py
--rw-r--r--   0 pingu      (501) staff       (20)     5643 2022-12-12 12:50:53.000000 clisops-0.9.5/clisops/ops/base_operation.py
--rw-r--r--   0 pingu      (501) staff       (20)     9278 2022-12-13 11:59:22.000000 clisops-0.9.5/clisops/ops/subset.py
-drwxr-xr-x   0 pingu      (501) staff       (20)        0 2022-12-14 10:11:58.265166 clisops-0.9.5/clisops/utils/
--rw-r--r--   0 pingu      (501) staff       (20)       46 2021-08-26 11:15:07.000000 clisops-0.9.5/clisops/utils/__init__.py
--rw-r--r--   0 pingu      (501) staff       (20)     1296 2022-12-12 12:50:53.000000 clisops-0.9.5/clisops/utils/common.py
--rw-r--r--   0 pingu      (501) staff       (20)    18861 2022-12-12 12:50:53.000000 clisops-0.9.5/clisops/utils/dataset_utils.py
--rw-r--r--   0 pingu      (501) staff       (20)     3184 2022-12-12 12:50:53.000000 clisops-0.9.5/clisops/utils/file_namers.py
--rw-r--r--   0 pingu      (501) staff       (20)     7267 2022-12-12 12:50:53.000000 clisops-0.9.5/clisops/utils/output_utils.py
--rw-r--r--   0 pingu      (501) staff       (20)     1154 2022-12-12 12:50:53.000000 clisops-0.9.5/clisops/utils/time_utils.py
--rw-r--r--   0 pingu      (501) staff       (20)     7428 2022-12-12 12:50:53.000000 clisops-0.9.5/clisops/utils/tutorial.py
-drwxr-xr-x   0 pingu      (501) staff       (20)        0 2022-12-14 10:11:58.249542 clisops-0.9.5/clisops.egg-info/
--rw-r--r--   0 pingu      (501) staff       (20)     3608 2022-12-14 10:11:58.000000 clisops-0.9.5/clisops.egg-info/PKG-INFO
--rw-r--r--   0 pingu      (501) staff       (20)      734 2022-12-14 10:11:58.000000 clisops-0.9.5/clisops.egg-info/SOURCES.txt
--rw-r--r--   0 pingu      (501) staff       (20)        1 2022-12-14 10:11:58.000000 clisops-0.9.5/clisops.egg-info/dependency_links.txt
--rw-r--r--   0 pingu      (501) staff       (20)      593 2022-12-14 10:11:58.000000 clisops-0.9.5/clisops.egg-info/requires.txt
--rw-r--r--   0 pingu      (501) staff       (20)       14 2022-12-14 10:11:58.000000 clisops-0.9.5/clisops.egg-info/top_level.txt
--rw-r--r--   0 pingu      (501) staff       (20)      399 2022-12-12 12:50:53.000000 clisops-0.9.5/requirements.txt
--rw-r--r--   0 pingu      (501) staff       (20)      209 2022-04-12 10:55:27.000000 clisops-0.9.5/requirements_dev.txt
--rw-r--r--   0 pingu      (501) staff       (20)      872 2022-12-14 10:11:58.267079 clisops-0.9.5/setup.cfg
--rw-r--r--   0 pingu      (501) staff       (20)     2903 2022-07-22 12:14:15.000000 clisops-0.9.5/setup.py
+drwxr-xr-x   0 tjs       (1000) tjs       (1000)        0 2023-04-05 14:20:40.160233 clisops-0.9.6/
+-rw-r--r--   0 tjs       (1000) tjs       (1000)      612 2022-05-27 18:49:36.000000 clisops-0.9.6/AUTHORS.rst
+-rw-r--r--   0 tjs       (1000) tjs       (1000)     4254 2022-06-14 14:41:12.000000 clisops-0.9.6/CONTRIBUTING.rst
+-rw-r--r--   0 tjs       (1000) tjs       (1000)    14670 2023-04-05 14:15:50.000000 clisops-0.9.6/HISTORY.rst
+-rw-r--r--   0 tjs       (1000) tjs       (1000)     1516 2022-03-29 16:16:35.000000 clisops-0.9.6/LICENSE
+-rw-r--r--   0 tjs       (1000) tjs       (1000)      186 2022-03-29 16:16:35.000000 clisops-0.9.6/MANIFEST.in
+-rw-r--r--   0 tjs       (1000) tjs       (1000)     3758 2023-04-05 14:20:40.160233 clisops-0.9.6/PKG-INFO
+-rw-r--r--   0 tjs       (1000) tjs       (1000)     2222 2023-04-03 17:09:11.000000 clisops-0.9.6/README.rst
+drwxr-xr-x   0 tjs       (1000) tjs       (1000)        0 2023-04-05 14:20:40.147232 clisops-0.9.6/clisops/
+-rw-r--r--   0 tjs       (1000) tjs       (1000)     1067 2022-05-27 18:49:36.000000 clisops-0.9.6/clisops/__init__.py
+-rw-r--r--   0 tjs       (1000) tjs       (1000)      312 2023-04-05 14:07:59.000000 clisops-0.9.6/clisops/__version__.py
+drwxr-xr-x   0 tjs       (1000) tjs       (1000)        0 2023-04-05 14:20:40.151233 clisops-0.9.6/clisops/core/
+-rw-r--r--   0 tjs       (1000) tjs       (1000)      219 2022-03-29 16:16:35.000000 clisops-0.9.6/clisops/core/__init__.py
+-rw-r--r--   0 tjs       (1000) tjs       (1000)    10135 2022-11-28 18:31:24.000000 clisops-0.9.6/clisops/core/average.py
+-rw-r--r--   0 tjs       (1000) tjs       (1000)    66653 2023-04-05 14:06:09.000000 clisops-0.9.6/clisops/core/subset.py
+drwxr-xr-x   0 tjs       (1000) tjs       (1000)        0 2023-04-05 14:20:40.151233 clisops-0.9.6/clisops/etc/
+-rw-r--r--   0 tjs       (1000) tjs       (1000)     1288 2022-03-29 16:16:35.000000 clisops-0.9.6/clisops/etc/roocs.ini
+-rw-r--r--   0 tjs       (1000) tjs       (1000)      100 2022-03-29 16:16:35.000000 clisops-0.9.6/clisops/exceptions.py
+drwxr-xr-x   0 tjs       (1000) tjs       (1000)        0 2023-04-05 14:20:40.154233 clisops-0.9.6/clisops/ops/
+-rw-r--r--   0 tjs       (1000) tjs       (1000)       56 2022-03-29 16:16:35.000000 clisops-0.9.6/clisops/ops/__init__.py
+-rw-r--r--   0 tjs       (1000) tjs       (1000)     5034 2023-02-07 21:39:40.000000 clisops-0.9.6/clisops/ops/average.py
+-rw-r--r--   0 tjs       (1000) tjs       (1000)     5642 2023-02-07 21:39:40.000000 clisops-0.9.6/clisops/ops/base_operation.py
+-rw-r--r--   0 tjs       (1000) tjs       (1000)     9277 2023-02-07 21:39:40.000000 clisops-0.9.6/clisops/ops/subset.py
+drwxr-xr-x   0 tjs       (1000) tjs       (1000)        0 2023-04-05 14:20:40.159232 clisops-0.9.6/clisops/utils/
+-rw-r--r--   0 tjs       (1000) tjs       (1000)       46 2022-03-29 16:16:35.000000 clisops-0.9.6/clisops/utils/__init__.py
+-rw-r--r--   0 tjs       (1000) tjs       (1000)     1296 2022-11-28 18:31:24.000000 clisops-0.9.6/clisops/utils/common.py
+-rw-r--r--   0 tjs       (1000) tjs       (1000)    18861 2022-11-28 18:31:24.000000 clisops-0.9.6/clisops/utils/dataset_utils.py
+-rw-r--r--   0 tjs       (1000) tjs       (1000)     3184 2022-11-28 18:31:24.000000 clisops-0.9.6/clisops/utils/file_namers.py
+-rw-r--r--   0 tjs       (1000) tjs       (1000)     7263 2023-02-07 21:39:40.000000 clisops-0.9.6/clisops/utils/output_utils.py
+-rw-r--r--   0 tjs       (1000) tjs       (1000)     1154 2022-11-28 18:31:24.000000 clisops-0.9.6/clisops/utils/time_utils.py
+-rw-r--r--   0 tjs       (1000) tjs       (1000)     7428 2022-11-28 18:31:24.000000 clisops-0.9.6/clisops/utils/tutorial.py
+drwxr-xr-x   0 tjs       (1000) tjs       (1000)        0 2023-04-05 14:20:40.149232 clisops-0.9.6/clisops.egg-info/
+-rw-r--r--   0 tjs       (1000) tjs       (1000)     3758 2023-04-05 14:20:40.000000 clisops-0.9.6/clisops.egg-info/PKG-INFO
+-rw-r--r--   0 tjs       (1000) tjs       (1000)      734 2023-04-05 14:20:40.000000 clisops-0.9.6/clisops.egg-info/SOURCES.txt
+-rw-r--r--   0 tjs       (1000) tjs       (1000)        1 2023-04-05 14:20:40.000000 clisops-0.9.6/clisops.egg-info/dependency_links.txt
+-rw-r--r--   0 tjs       (1000) tjs       (1000)      607 2023-04-05 14:20:40.000000 clisops-0.9.6/clisops.egg-info/requires.txt
+-rw-r--r--   0 tjs       (1000) tjs       (1000)       14 2023-04-05 14:20:40.000000 clisops-0.9.6/clisops.egg-info/top_level.txt
+-rw-r--r--   0 tjs       (1000) tjs       (1000)      398 2023-04-05 14:06:09.000000 clisops-0.9.6/requirements.txt
+-rw-r--r--   0 tjs       (1000) tjs       (1000)      225 2023-04-05 14:06:09.000000 clisops-0.9.6/requirements_dev.txt
+-rw-r--r--   0 tjs       (1000) tjs       (1000)      945 2023-04-05 14:20:40.161233 clisops-0.9.6/setup.cfg
+-rw-r--r--   0 tjs       (1000) tjs       (1000)     2903 2022-06-14 14:41:12.000000 clisops-0.9.6/setup.py
```

### Comparing `clisops-0.9.5/AUTHORS.rst` & `clisops-0.9.6/AUTHORS.rst`

 * *Files identical despite different names*

### Comparing `clisops-0.9.5/CONTRIBUTING.rst` & `clisops-0.9.6/CONTRIBUTING.rst`

 * *Files identical despite different names*

### Comparing `clisops-0.9.5/HISTORY.rst` & `clisops-0.9.6/HISTORY.rst`

 * *Files 2% similar despite different names*

```diff
@@ -1,16 +1,30 @@
 Version History
 ===============
 
-v0.9.5 (2022-12-14)
+v0.9.6 (2023-04-05)
 -------------------
 
 Bug Fixes
 ^^^^^^^^^
+* Fixed an issue with the `pytest` fixtures that was needlessly calling ``load_esgf_test_data`` multiple times while tests were running (#278).
+* Corrected a temporary workaround for updating split geometries that was causing issues with modern `pandas` versions (#278).
+
+Other Changes
+^^^^^^^^^^^^^
+* Removed some obsolete tests and adjusted pytest to always report in colour (#272).
+* Split conda CI builds to explicitly test against xarray/stable and xarray/dev (#272).
+* GitHub CI now reports coverage statistics to Coveralls.io (#276).
+* Updated `geopandas` (>=0.11), `pyproj` (>=3.3.0), `shapely` (>=1.9), `tox` (>=4.0), `xarray` (>=0.21), and `xesmf` (>=0.6.3) to use more modern versions (#278).
 
+v0.9.5 (2022-12-14)
+-------------------
+
+Bug Fixes
+^^^^^^^^^
 * Fixed `core.subset.check_levels_exist` decorator by rounding (precision 4) level values like 1000.00000001 (#265).
 
 v0.9.4 (2022-12-13)
 -------------------
 
 Bug Fixes
 ^^^^^^^^^
```

### Comparing `clisops-0.9.5/LICENSE` & `clisops-0.9.6/LICENSE`

 * *Files identical despite different names*

### Comparing `clisops-0.9.5/PKG-INFO` & `clisops-0.9.6/PKG-INFO`

 * *Files 7% similar despite different names*

```diff
@@ -1,17 +1,16 @@
 Metadata-Version: 2.1
 Name: clisops
-Version: 0.9.5
+Version: 0.9.6
 Summary: clisops - climate simulation operations.
 Home-page: https://github.com/roocs/clisops
 Author: Elle Smith
 Author-email: eleanor.smith@stfc.ac.uk
 License: BSD
 Keywords: clisops
-Platform: UNKNOWN
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Environment :: Console
 Classifier: Environment :: Web Environment
 Classifier: Intended Audience :: End Users/Desktop
 Classifier: Intended Audience :: Developers
 Classifier: Intended Audience :: System Administrators
 Classifier: Intended Audience :: Science/Research
@@ -50,14 +49,18 @@
    :target: https://anaconda.org/conda-forge/clisops
    :alt: Conda Forge
 
 .. image:: https://github.com/roocs/clisops/workflows/build/badge.svg
    :target: https://github.com/roocs/clisops/actions
    :alt: Build Status
 
+.. image:: https://coveralls.io/repos/github/roocs/clisops/badge.svg?branch=master
+   :target: https://coveralls.io/github/roocs/clisops?branch=master
+   :alt: Coverage
+
 .. image:: https://readthedocs.org/projects/clisops/badge/?version=latest
    :target: https://clisops.readthedocs.io/en/latest/?badge=latest
    :alt: Documentation
 
 The ``clisops`` package (pronounced "clie-sops") provides a python library for running
 *data-reduction* operations on `Xarray <http://xarray.pydata.org/>`_ data sets or files
 that can be interpreted by Xarray. These basic operations (subsetting, averaging and
@@ -92,9 +95,7 @@
 
 * Cookiecutter: https://github.com/audreyr/cookiecutter
 * cookiecutter-pypackage: https://github.com/audreyr/cookiecutter-pypackage
 
 .. image:: https://img.shields.io/badge/code%20style-black-000000.svg
    :target: https://github.com/python/black
    :alt: Python Black
-
-
```

### Comparing `clisops-0.9.5/README.rst` & `clisops-0.9.6/README.rst`

 * *Files 5% similar despite different names*

```diff
@@ -9,14 +9,18 @@
    :target: https://anaconda.org/conda-forge/clisops
    :alt: Conda Forge
 
 .. image:: https://github.com/roocs/clisops/workflows/build/badge.svg
    :target: https://github.com/roocs/clisops/actions
    :alt: Build Status
 
+.. image:: https://coveralls.io/repos/github/roocs/clisops/badge.svg?branch=master
+   :target: https://coveralls.io/github/roocs/clisops?branch=master
+   :alt: Coverage
+
 .. image:: https://readthedocs.org/projects/clisops/badge/?version=latest
    :target: https://clisops.readthedocs.io/en/latest/?badge=latest
    :alt: Documentation
 
 The ``clisops`` package (pronounced "clie-sops") provides a python library for running
 *data-reduction* operations on `Xarray <http://xarray.pydata.org/>`_ data sets or files
 that can be interpreted by Xarray. These basic operations (subsetting, averaging and
```

### Comparing `clisops-0.9.5/clisops/__init__.py` & `clisops-0.9.6/clisops/__init__.py`

 * *Files identical despite different names*

### Comparing `clisops-0.9.5/clisops/core/average.py` & `clisops-0.9.6/clisops/core/average.py`

 * *Files identical despite different names*

### Comparing `clisops-0.9.5/clisops/core/subset.py` & `clisops-0.9.6/clisops/core/subset.py`

 * *Files 1% similar despite different names*

```diff
@@ -7,14 +7,15 @@
 from typing import Dict, Optional, Sequence, Tuple, Union
 
 import cf_xarray  # noqa
 import geopandas as gpd
 import numpy as np
 import xarray
 from packaging import version
+from pandas import DataFrame
 from pandas.api.types import is_integer_dtype  # noqa
 from pyproj import Geod
 from pyproj.crs import CRS
 from pyproj.exceptions import CRSError
 from roocs_utils.utils.time_utils import to_isoformat
 from roocs_utils.xarray_utils import xarray_utils as xu
 from shapely import vectorized
@@ -410,14 +411,16 @@
                 # TODO: This should raise an exception, right?
                 warnings.warn(
                     "DataArray doesn't seem to be using lons between 0 and 360 degrees or between -180 and 180 degrees."
                     " Tread with caution.",
                     UserWarning,
                     stacklevel=4,
                 )
+
+            split_features = dict()
             split_flag = False
             for index, feature in poly.iterrows():
                 if (feature.geometry.bounds[0] < 0) and (
                     feature.geometry.bounds[2] > 0
                 ):
                     split_flag = True
                     warnings.warn(
@@ -435,21 +438,27 @@
                     meridian = LineString([Point(0, 90), Point(0, -90)])
                     buffered = meridian.buffer(0.000000001)
                     split_polygons = split(union, meridian)
                     buffered_split_polygons = [
                         feat.difference(buffered) for feat in split_polygons.geoms
                     ]
 
-                    # Cannot assign iterable with `at` (pydata/pandas#26333) so a small hack:
-                    # Load split features into a new GeoDataFrame with WGS84 CRS
-                    split_gdf = gpd.GeoDataFrame(
-                        geometry=[unary_union(buffered_split_polygons)],
-                        crs=CRS(4326),
-                    )
-                    poly.at[[index], "geometry"] = split_gdf.geometry.values
+                    split_features[index] = [unary_union(buffered_split_polygons)]
+
+            if split_flag:
+                split_df = DataFrame.from_dict(
+                    split_features,
+                    orient="index",
+                    columns=["geometry"],
+                )
+                split_gdf = gpd.GeoDataFrame(split_df, geometry=split_df.geometry)
+                poly.update(split_gdf)
+
+            # Set CRS on polygon for correct reprojection
+            poly = poly.set_crs(CRS(4326))
 
             # Reproject features in WGS84 CSR to use 0 to 360 as longitudinal values
             wrapped_lons = CRS.from_string(
                 "+proj=longlat +ellps=WGS84 +lon_wrap=180 +datum=WGS84 +no_defs"
             )
 
             poly = poly.to_crs(crs=wrapped_lons)
@@ -815,15 +824,15 @@
         inds = np.unravel_index(flat_ind, lon.shape)
         # Create index dictionary on native dimensions, e.g. rlon, rlat
         native_ind = dict(zip(lon.dims, inds))
 
     # Create slices, adding a halo around selection to account for `nearest` grid cell center approximation.
     out = {}
     halo = 2
-    for (k, v) in native_ind.items():
+    for k, v in native_ind.items():
         vmin = np.clip(v.min() - halo, 0, ds[k].size)
         vmax = np.clip(v.max() + halo + 1, 0, ds[k].size)
         out[k] = slice(vmin, vmax)
     return out
 
 
 def create_weight_masks(
@@ -1198,15 +1207,14 @@
         prSub = subset_bbox(ds.pr, lon_bnds=[-75, -70], lat_bnds=[40, 45])
     """
     lat = get_lat(da).name
     lon = get_lon(da).name
 
     # Rectilinear case (lat and lon are the 1D dimensions)
     if (lat in da.dims) or (lon in da.dims):
-
         if lat in da.dims and lat_bnds is not None:
             lat_bnds = _check_desc_coords(coord=da[lat], bounds=lat_bnds, dim=lat)
             da = da.sel({lat: slice(*lat_bnds)})
 
         if lon in da.dims and lon_bnds is not None:
             lon_bnds = _check_desc_coords(coord=da[lon], bounds=lon_bnds, dim=lon)
             da = da.sel({lon: slice(*lon_bnds)})
@@ -1270,15 +1278,14 @@
         if isinstance(da, xarray.Dataset):
             # If da is a xr.DataSet Mask only variables that have the
             # same 2d coordinates as lat (or lon)
             for var in da.data_vars:
                 if set(da[lat].dims).issubset(da[var].dims):
                     da[var] = da[var].where(lon_cond & lat_cond, drop=True)
         else:
-
             da = da.where(lon_cond & lat_cond, drop=True)
 
     else:
         raise (
             Exception(
                 f'{subset_bbox.__name__} requires input data with "lon" and "lat" dimensions, coordinates, or variables.'
             )
@@ -1355,15 +1362,15 @@
             UserWarning,
             stacklevel=5,
         )
 
 
 def _check_has_overlaps_old(polygons: gpd.GeoDataFrame):
     for i, (inda, pola) in enumerate(polygons.iterrows()):
-        for (indb, polb) in polygons.iloc[i + 1 :].iterrows():
+        for indb, polb in polygons.iloc[i + 1 :].iterrows():
             if pola.geometry.intersects(polb.geometry):
                 warnings.warn(
                     f"List of shapes contains overlap between {inda} and {indb}. Points will be assigned to {inda}.",
                     UserWarning,
                     stacklevel=5,
                 )
```

### Comparing `clisops-0.9.5/clisops/etc/roocs.ini` & `clisops-0.9.6/clisops/etc/roocs.ini`

 * *Files identical despite different names*

### Comparing `clisops-0.9.5/clisops/ops/average.py` & `clisops-0.9.6/clisops/ops/average.py`

 * *Files 0% similar despite different names*

```diff
@@ -17,15 +17,14 @@
     def _resolve_params(self, **params):
         dims = DimensionParameter(params.get("dims", None)).value
         ignore_undetected_dims = params.get("ignore_undetected_dims", False)
 
         self.params = {"dims": dims, "ignore_undetected_dims": ignore_undetected_dims}
 
     def _get_file_namer(self):
-
         if self.params.get("dims", None):
             dims = [convert_coord_to_axis(dim) for dim in self.params["dims"]]
             extra = f"_avg-{''.join(sorted(dims))}"
         else:
             extra = ""
 
         namer = get_file_namer(self._file_namer)(extra=extra)
```

### Comparing `clisops-0.9.5/clisops/ops/base_operation.py` & `clisops-0.9.6/clisops/ops/base_operation.py`

 * *Files 0% similar despite different names*

```diff
@@ -135,15 +135,14 @@
 
         # Work out how many outputs should be created based on the size
         # of the array. Manage this as a list of time slices.
         time_slices = get_time_slices(processed_ds, self._split_method)
 
         # Loop through each time slice
         for tslice in time_slices:
-
             # If there is only one time slice, and it is None:
             # - then just set the result Dataset to the processed Dataset
             if tslice is None:
                 result_ds = processed_ds
             # If there is a time slice then extract the time slice from the
             # processed Dataset
             else:
```

### Comparing `clisops-0.9.5/clisops/ops/subset.py` & `clisops-0.9.6/clisops/ops/subset.py`

 * *Files 0% similar despite different names*

```diff
@@ -48,15 +48,14 @@
             level=level,
             time_components=time_comps,
         )
 
         # For each required parameter, check if the parameter can be accessed as a tuple
         # If not: then use the dictionary representation for it
         for param_name in ["time", "area", "level", "time_components"]:
-
             param_value = parameters.get(param_name)
             if param_value.value is not None:
                 args.update(param_value.asdict())
 
         # Rename start_time and end_time to start_date and end_date to
         # match clisops.core.subset function parameters.
         if "start_time" in args:
```

### Comparing `clisops-0.9.5/clisops/utils/common.py` & `clisops-0.9.6/clisops/utils/common.py`

 * *Files identical despite different names*

### Comparing `clisops-0.9.5/clisops/utils/dataset_utils.py` & `clisops-0.9.6/clisops/utils/dataset_utils.py`

 * *Files identical despite different names*

### Comparing `clisops-0.9.5/clisops/utils/file_namers.py` & `clisops-0.9.6/clisops/utils/file_namers.py`

 * *Files identical despite different names*

### Comparing `clisops-0.9.5/clisops/utils/output_utils.py` & `clisops-0.9.6/clisops/utils/output_utils.py`

 * *Files 0% similar despite different names*

```diff
@@ -86,15 +86,14 @@
 def get_time_slices(
     ds: Union[xr.Dataset, xr.DataArray],
     split_method,
     start=None,
     end=None,
     file_size_limit: str = None,
 ) -> List[Tuple[str, str]]:
-
     """
     Take an xarray Dataset or DataArray, assume it can be split on the time axis
     into a sequence of slices. Optionally, take a start and end date to specify
     a sub-slice of the main time axis.
 
     Use the prescribed file size limit to generate a list of
     ("YYYY-MM-DD", "YYYY-MM-DD") slices so that the output files do
@@ -144,15 +143,14 @@
     if slice_length == 0:
         raise Exception("Unable to calculate slice length for splitting output files.")
 
     indx = 0
     final_indx = n_times - 1
 
     while indx <= final_indx:
-
         start_indx = indx
         indx += slice_length
         end_indx = indx - 1
 
         if end_indx > final_indx:
             end_indx = final_indx
         slices.append(
@@ -231,23 +229,21 @@
     else:
         target_path = output_path
 
     # TODO: writing output works currently only in sync mode, see:
     #  - https://github.com/roocs/rook/issues/55
     #  - https://docs.dask.org/en/latest/scheduling.html
     with dask.config.set(scheduler="synchronous"):
-
         writer = getattr(chunked_ds, format_writer)
         delayed_obj = writer(target_path, compute=False)
         delayed_obj.compute()
 
     # If "output_staging_dir" is set, then pause, move the output file,
     # and clean up the temporary directory
     if os.path.isdir(staging_dir):
-
         shutil.move(target_path, output_path)
         # Sleeping, to allow file system caching/syncing delays
         time.sleep(3)
         tmp_dir.cleanup()
 
     logger.info(f"Wrote output file: {output_path}")
     return output_path
```

### Comparing `clisops-0.9.5/clisops/utils/time_utils.py` & `clisops-0.9.6/clisops/utils/time_utils.py`

 * *Files identical despite different names*

### Comparing `clisops-0.9.5/clisops/utils/tutorial.py` & `clisops-0.9.6/clisops/utils/tutorial.py`

 * *Files identical despite different names*

### Comparing `clisops-0.9.5/clisops.egg-info/PKG-INFO` & `clisops-0.9.6/clisops.egg-info/PKG-INFO`

 * *Files 7% similar despite different names*

```diff
@@ -1,17 +1,16 @@
 Metadata-Version: 2.1
 Name: clisops
-Version: 0.9.5
+Version: 0.9.6
 Summary: clisops - climate simulation operations.
 Home-page: https://github.com/roocs/clisops
 Author: Elle Smith
 Author-email: eleanor.smith@stfc.ac.uk
 License: BSD
 Keywords: clisops
-Platform: UNKNOWN
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Environment :: Console
 Classifier: Environment :: Web Environment
 Classifier: Intended Audience :: End Users/Desktop
 Classifier: Intended Audience :: Developers
 Classifier: Intended Audience :: System Administrators
 Classifier: Intended Audience :: Science/Research
@@ -50,14 +49,18 @@
    :target: https://anaconda.org/conda-forge/clisops
    :alt: Conda Forge
 
 .. image:: https://github.com/roocs/clisops/workflows/build/badge.svg
    :target: https://github.com/roocs/clisops/actions
    :alt: Build Status
 
+.. image:: https://coveralls.io/repos/github/roocs/clisops/badge.svg?branch=master
+   :target: https://coveralls.io/github/roocs/clisops?branch=master
+   :alt: Coverage
+
 .. image:: https://readthedocs.org/projects/clisops/badge/?version=latest
    :target: https://clisops.readthedocs.io/en/latest/?badge=latest
    :alt: Documentation
 
 The ``clisops`` package (pronounced "clie-sops") provides a python library for running
 *data-reduction* operations on `Xarray <http://xarray.pydata.org/>`_ data sets or files
 that can be interpreted by Xarray. These basic operations (subsetting, averaging and
@@ -92,9 +95,7 @@
 
 * Cookiecutter: https://github.com/audreyr/cookiecutter
 * cookiecutter-pypackage: https://github.com/audreyr/cookiecutter-pypackage
 
 .. image:: https://img.shields.io/badge/code%20style-black-000000.svg
    :target: https://github.com/python/black
    :alt: Python Black
-
-
```

### Comparing `clisops-0.9.5/clisops.egg-info/SOURCES.txt` & `clisops-0.9.6/clisops.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `clisops-0.9.5/setup.cfg` & `clisops-0.9.6/setup.cfg`

 * *Files 14% similar despite different names*

```diff
@@ -1,23 +1,27 @@
 [bumpversion]
-current_version = 0.9.5
+current_version = 0.9.6
 commit = True
 tag = True
 
 [bumpversion:file:clisops/__version__.py]
 search = __version__ = "{current_version}"
 replace = __version__ = "{new_version}"
 
 [bumpversion:file:docs/conf.py]
 search = version = "{current_version}"
 replace = version = "{new_version}"
 
 [bdist_wheel]
 universal = 1
 
+[coverage:run]
+relative_files = True
+omit = */tests/*.py
+
 [flake8]
 exclude = 
 	.git,
 	docs,
 	build,
 	.eggs,
 	tests/mini-esgf-data
@@ -37,15 +41,17 @@
 	F405
 
 [aliases]
 test = pytest
 
 [tool:pytest]
 collect_ignore = ["setup.py"]
-addopts = --verbose
+addopts = 
+	--color=yes
+	--verbose
 filterwarnings = 
 	ignore::UserWarning
 markers = 
 	online: mark test to need internet connection
 	slow: mark test to be slow
 
 [pylint]
```

### Comparing `clisops-0.9.5/setup.py` & `clisops-0.9.6/setup.py`

 * *Files identical despite different names*

