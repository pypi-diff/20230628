# Comparing `tmp/akhdefo_functions-2.2.49.tar.gz` & `tmp/akhdefo_functions-2.2.50.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "akhdefo_functions-2.2.49.tar", last modified: Wed Jun 21 17:43:48 2023, max compression
+gzip compressed data, was "akhdefo_functions-2.2.50.tar", last modified: Wed Jun 28 05:23:00 2023, max compression
```

## Comparing `akhdefo_functions-2.2.49.tar` & `akhdefo_functions-2.2.50.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxrwxrwx   0        0        0        0 2023-06-21 17:43:48.134389 akhdefo_functions-2.2.49/
--rw-rw-rw-   0        0        0     2775 2023-06-21 17:43:48.133366 akhdefo_functions-2.2.49/PKG-INFO
--rw-rw-rw-   0        0        0     1520 2023-05-19 19:29:17.000000 akhdefo_functions-2.2.49/README.md
-drwxrwxrwx   0        0        0        0 2023-06-21 17:43:48.102364 akhdefo_functions-2.2.49/akhdefo_functions/
--rw-rw-rw-   0        0        0    42236 2023-06-15 05:15:29.000000 akhdefo_functions-2.2.49/akhdefo_functions/AkhdefoPlot.py
--rw-rw-rw-   0        0        0    11925 2023-06-14 11:29:49.000000 akhdefo_functions-2.2.49/akhdefo_functions/Akhdefo_Coreg.py
--rw-rw-rw-   0        0        0    32520 2023-06-20 19:16:34.000000 akhdefo_functions-2.2.49/akhdefo_functions/Akhdefo_GOI.py
--rw-rw-rw-   0        0        0    15923 2023-06-14 11:29:49.000000 akhdefo_functions-2.2.49/akhdefo_functions/Akhdefo_TS.py
--rw-rw-rw-   0        0        0    34778 2023-06-14 11:29:49.000000 akhdefo_functions-2.2.49/akhdefo_functions/Akhdefo_Tools.py
--rw-rw-rw-   0        0        0    33124 2023-06-21 17:43:30.000000 akhdefo_functions-2.2.49/akhdefo_functions/Akhdefo_utils.py
--rw-rw-rw-   0        0        0    19139 2023-06-21 17:42:19.000000 akhdefo_functions-2.2.49/akhdefo_functions/Filter_PreProc.py
--rw-rw-rw-   0        0        0     7148 2023-06-16 21:47:25.000000 akhdefo_functions-2.2.49/akhdefo_functions/Mosaic_Crop.py
--rw-rw-rw-   0        0        0    45101 2023-06-14 11:29:49.000000 akhdefo_functions-2.2.49/akhdefo_functions/OpticalFlow.py
--rw-rw-rw-   0        0        0    38789 2023-06-14 11:29:49.000000 akhdefo_functions-2.2.49/akhdefo_functions/Stacked_Velocity.py
--rw-rw-rw-   0        0        0    11051 2023-06-14 11:29:49.000000 akhdefo_functions-2.2.49/akhdefo_functions/Unzip_CopyFiles.py
--rw-rw-rw-   0        0        0      581 2023-06-15 06:41:41.000000 akhdefo_functions-2.2.49/akhdefo_functions/__init__.py
-drwxrwxrwx   0        0        0        0 2023-06-21 17:43:48.132367 akhdefo_functions-2.2.49/akhdefo_functions.egg-info/
--rw-rw-rw-   0        0        0     2775 2023-06-21 17:43:47.000000 akhdefo_functions-2.2.49/akhdefo_functions.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      680 2023-06-21 17:43:47.000000 akhdefo_functions-2.2.49/akhdefo_functions.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-21 17:43:47.000000 akhdefo_functions-2.2.49/akhdefo_functions.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0        2 2023-02-05 09:04:56.000000 akhdefo_functions-2.2.49/akhdefo_functions.egg-info/not-zip-safe
--rw-rw-rw-   0        0        0       18 2023-06-21 17:43:47.000000 akhdefo_functions-2.2.49/akhdefo_functions.egg-info/top_level.txt
--rw-rw-rw-   0        0        0     1222 2023-06-14 06:10:05.000000 akhdefo_functions-2.2.49/pyproject.toml
--rw-rw-rw-   0        0        0       42 2023-06-21 17:43:48.134389 akhdefo_functions-2.2.49/setup.cfg
--rw-rw-rw-   0        0        0     3609 2023-06-14 06:09:43.000000 akhdefo_functions-2.2.49/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 05:23:00.788072 akhdefo_functions-2.2.50/
+-rw-rw-rw-   0        0        0     2775 2023-06-28 05:23:00.787561 akhdefo_functions-2.2.50/PKG-INFO
+-rw-rw-rw-   0        0        0     1520 2023-05-19 19:29:17.000000 akhdefo_functions-2.2.50/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 05:23:00.756558 akhdefo_functions-2.2.50/akhdefo_functions/
+-rw-rw-rw-   0        0        0    42236 2023-06-15 05:15:29.000000 akhdefo_functions-2.2.50/akhdefo_functions/AkhdefoPlot.py
+-rw-rw-rw-   0        0        0    11925 2023-06-14 11:29:49.000000 akhdefo_functions-2.2.50/akhdefo_functions/Akhdefo_Coreg.py
+-rw-rw-rw-   0        0        0    32520 2023-06-20 19:16:34.000000 akhdefo_functions-2.2.50/akhdefo_functions/Akhdefo_GOI.py
+-rw-rw-rw-   0        0        0    36835 2023-06-28 05:15:50.000000 akhdefo_functions-2.2.50/akhdefo_functions/Akhdefo_TS.py
+-rw-rw-rw-   0        0        0    34778 2023-06-14 11:29:49.000000 akhdefo_functions-2.2.50/akhdefo_functions/Akhdefo_Tools.py
+-rw-rw-rw-   0        0        0    33124 2023-06-21 17:43:30.000000 akhdefo_functions-2.2.50/akhdefo_functions/Akhdefo_utils.py
+-rw-rw-rw-   0        0        0    19139 2023-06-21 17:42:19.000000 akhdefo_functions-2.2.50/akhdefo_functions/Filter_PreProc.py
+-rw-rw-rw-   0        0        0     7148 2023-06-16 21:47:25.000000 akhdefo_functions-2.2.50/akhdefo_functions/Mosaic_Crop.py
+-rw-rw-rw-   0        0        0    45101 2023-06-14 11:29:49.000000 akhdefo_functions-2.2.50/akhdefo_functions/OpticalFlow.py
+-rw-rw-rw-   0        0        0    38790 2023-06-27 00:01:31.000000 akhdefo_functions-2.2.50/akhdefo_functions/Stacked_Velocity.py
+-rw-rw-rw-   0        0        0    11051 2023-06-14 11:29:49.000000 akhdefo_functions-2.2.50/akhdefo_functions/Unzip_CopyFiles.py
+-rw-rw-rw-   0        0        0      581 2023-06-28 05:18:58.000000 akhdefo_functions-2.2.50/akhdefo_functions/__init__.py
+drwxrwxrwx   0        0        0        0 2023-06-28 05:23:00.785564 akhdefo_functions-2.2.50/akhdefo_functions.egg-info/
+-rw-rw-rw-   0        0        0     2775 2023-06-28 05:22:59.000000 akhdefo_functions-2.2.50/akhdefo_functions.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      647 2023-06-28 05:23:00.000000 akhdefo_functions-2.2.50/akhdefo_functions.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 05:22:59.000000 akhdefo_functions-2.2.50/akhdefo_functions.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0        2 2023-06-28 05:19:26.000000 akhdefo_functions-2.2.50/akhdefo_functions.egg-info/not-zip-safe
+-rw-rw-rw-   0        0        0       18 2023-06-28 05:22:59.000000 akhdefo_functions-2.2.50/akhdefo_functions.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0     1222 2023-06-28 05:17:27.000000 akhdefo_functions-2.2.50/pyproject.toml
+-rw-rw-rw-   0        0        0       42 2023-06-28 05:23:00.789087 akhdefo_functions-2.2.50/setup.cfg
+-rw-rw-rw-   0        0        0     3609 2023-06-28 05:17:07.000000 akhdefo_functions-2.2.50/setup.py
```

### Comparing `akhdefo_functions-2.2.49/PKG-INFO` & `akhdefo_functions-2.2.50/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: akhdefo_functions
-Version: 2.2.49
+Version: 2.2.50
 Summary: Land Deformation Monitoring Using Optical Satellite Imagery
 Home-page: https://github.com/mahmudsfu/AkhDefo
 Author: Mahmud Mustafa Muhammad
 Author-email: Mahmud Mustafa Muhammad <mahmud.muhamm1@gmail.com>
 License: Academic Free License (AFL)
 Project-URL: Homepage, https://github.com/mahmudsfu/AkhDefo
 Project-URL: Bug Tracker, https://github.com/mahmudsfu/AkhDefo/issues
```

### Comparing `akhdefo_functions-2.2.49/README.md` & `akhdefo_functions-2.2.50/README.md`

 * *Files identical despite different names*

### Comparing `akhdefo_functions-2.2.49/akhdefo_functions/AkhdefoPlot.py` & `akhdefo_functions-2.2.50/akhdefo_functions/AkhdefoPlot.py`

 * *Files identical despite different names*

### Comparing `akhdefo_functions-2.2.49/akhdefo_functions/Akhdefo_Coreg.py` & `akhdefo_functions-2.2.50/akhdefo_functions/Akhdefo_Coreg.py`

 * *Files identical despite different names*

### Comparing `akhdefo_functions-2.2.49/akhdefo_functions/Akhdefo_GOI.py` & `akhdefo_functions-2.2.50/akhdefo_functions/Akhdefo_GOI.py`

 * *Files identical despite different names*

### Comparing `akhdefo_functions-2.2.49/akhdefo_functions/Akhdefo_Tools.py` & `akhdefo_functions-2.2.50/akhdefo_functions/Akhdefo_Tools.py`

 * *Files identical despite different names*

### Comparing `akhdefo_functions-2.2.49/akhdefo_functions/Akhdefo_utils.py` & `akhdefo_functions-2.2.50/akhdefo_functions/Akhdefo_utils.py`

 * *Files identical despite different names*

### Comparing `akhdefo_functions-2.2.49/akhdefo_functions/Filter_PreProc.py` & `akhdefo_functions-2.2.50/akhdefo_functions/Filter_PreProc.py`

 * *Files identical despite different names*

### Comparing `akhdefo_functions-2.2.49/akhdefo_functions/Mosaic_Crop.py` & `akhdefo_functions-2.2.50/akhdefo_functions/Mosaic_Crop.py`

 * *Files identical despite different names*

### Comparing `akhdefo_functions-2.2.49/akhdefo_functions/OpticalFlow.py` & `akhdefo_functions-2.2.50/akhdefo_functions/OpticalFlow.py`

 * *Files identical despite different names*

### Comparing `akhdefo_functions-2.2.49/akhdefo_functions/Stacked_Velocity.py` & `akhdefo_functions-2.2.50/akhdefo_functions/Stacked_Velocity.py`

 * *Files 0% similar despite different names*

```diff
@@ -713,15 +713,15 @@
         profile.update(nodata=np.nan, dtype="float32")
 
     #Names for Interpolated raster
     import earthpy.spatial as es
     with rasterio.open(dem) as src:
         elevation = src.read(1)
         # Set masked values to np.nan
-        elevation[elevation < 0] = np.nan
+        #elevation[elevation < 0] = np.nan
     # Create and plot the hillshade with earthpy
     hillshade = es.hillshade(elevation, azimuth=270, altitude=45)
 
     dem = rxr.open_rasterio(dem, masked=True)
     dem_plotting_extent = plotting_extent(dem[0], dem.rio.transform())
```

### Comparing `akhdefo_functions-2.2.49/akhdefo_functions/Unzip_CopyFiles.py` & `akhdefo_functions-2.2.50/akhdefo_functions/Unzip_CopyFiles.py`

 * *Files identical despite different names*

### Comparing `akhdefo_functions-2.2.49/akhdefo_functions/__init__.py` & `akhdefo_functions-2.2.50/akhdefo_functions/__init__.py`

 * *Files 19% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 """
 akhdefo_functions
 
 collection of python modules performs geospatial image processing to moniter land deformation
 """
 
-__version__ = "2.2.49"
+__version__ = "2.2.50"
 __author__ = 'Mahmud Mustafa Muhammad'
 __credits__ = 'Simon Fraser university-Department of Earth Sciences'
 
 
 from .AkhdefoPlot import*
 from .Akhdefo_Tools import*
 from .Akhdefo_TS import*
```

### Comparing `akhdefo_functions-2.2.49/akhdefo_functions.egg-info/PKG-INFO` & `akhdefo_functions-2.2.50/akhdefo_functions.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: akhdefo-functions
-Version: 2.2.49
+Version: 2.2.50
 Summary: Land Deformation Monitoring Using Optical Satellite Imagery
 Home-page: https://github.com/mahmudsfu/AkhDefo
 Author: Mahmud Mustafa Muhammad
 Author-email: Mahmud Mustafa Muhammad <mahmud.muhamm1@gmail.com>
 License: Academic Free License (AFL)
 Project-URL: Homepage, https://github.com/mahmudsfu/AkhDefo
 Project-URL: Bug Tracker, https://github.com/mahmudsfu/AkhDefo/issues
```

### Comparing `akhdefo_functions-2.2.49/akhdefo_functions.egg-info/SOURCES.txt` & `akhdefo_functions-2.2.50/akhdefo_functions.egg-info/SOURCES.txt`

 * *Files 4% similar despite different names*

```diff
@@ -9,13 +9,12 @@
 akhdefo_functions/Akhdefo_utils.py
 akhdefo_functions/Filter_PreProc.py
 akhdefo_functions/Mosaic_Crop.py
 akhdefo_functions/OpticalFlow.py
 akhdefo_functions/Stacked_Velocity.py
 akhdefo_functions/Unzip_CopyFiles.py
 akhdefo_functions/__init__.py
-akhdefo_functions/akhdefo_GOI.py
 akhdefo_functions.egg-info/PKG-INFO
 akhdefo_functions.egg-info/SOURCES.txt
 akhdefo_functions.egg-info/dependency_links.txt
 akhdefo_functions.egg-info/not-zip-safe
 akhdefo_functions.egg-info/top_level.txt
```

### Comparing `akhdefo_functions-2.2.49/pyproject.toml` & `akhdefo_functions-2.2.50/pyproject.toml`

 * *Files 8% similar despite different names*

```diff
@@ -3,15 +3,15 @@
 requires = ["hatchling"]
 build-backend = "hatchling.build"
 
 
 
 [project]
 name = "akhdefo_functions"
-version = "2.2.49"
+version = "2.2.50"
 authors = [
   { name="Mahmud Mustafa Muhammad", email="mahmud.muhamm1@gmail.com" },
 ]
 description = "Land Deformation Monitoring Using Optical Satellite Imagery"
 readme = "README.md"
 requires-python = ">=3.7"
```

### Comparing `akhdefo_functions-2.2.49/setup.py` & `akhdefo_functions-2.2.50/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -82,15 +82,15 @@
 # Read the long description from the README file
 with open("README.md", "r", encoding="utf-8") as fh:
     long_description = fh.read()
 
 # Setup configuration
 setup(
     name='akhdefo_functions',
-    version='2.2.48',
+    version='2.2.50',
     description='Land Deformation Monitoring Using Optical Satellite Imagery',
     url='https://github.com/mahmudsfu/AkhDefo',
     author='Mahmud Mustafa Muhammad',
     author_email='mahmud.muhamm1@gmail.com',
     license='Academic Free License (AFL)',
     packages=['akhdefo_functions'],
     long_description=long_description,
```

