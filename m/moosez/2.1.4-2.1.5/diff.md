# Comparing `tmp/moosez-2.1.4.tar.gz` & `tmp/moosez-2.1.5.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "moosez-2.1.4.tar", last modified: Wed Jun 28 09:44:46 2023, max compression
+gzip compressed data, was "moosez-2.1.5.tar", last modified: Wed Jun 28 15:38:05 2023, max compression
```

## Comparing `moosez-2.1.4.tar` & `moosez-2.1.5.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:44:46.781505 moosez-2.1.4/
--rw-r--r--   0 runner    (1001) docker     (123)    11357 2023-06-28 09:44:37.000000 moosez-2.1.4/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)     1408 2023-06-28 09:44:46.781505 moosez-2.1.4/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     9205 2023-06-28 09:44:37.000000 moosez-2.1.4/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:44:46.781505 moosez-2.1.4/moosez/
--rw-r--r--   0 runner    (1001) docker     (123)      227 2023-06-28 09:44:37.000000 moosez-2.1.4/moosez/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1759 2023-06-28 09:44:37.000000 moosez-2.1.4/moosez/constants.py
--rw-r--r--   0 runner    (1001) docker     (123)     5407 2023-06-28 09:44:37.000000 moosez-2.1.4/moosez/display.py
--rw-r--r--   0 runner    (1001) docker     (123)     3630 2023-06-28 09:44:37.000000 moosez-2.1.4/moosez/download.py
--rw-r--r--   0 runner    (1001) docker     (123)     4152 2023-06-28 09:44:37.000000 moosez-2.1.4/moosez/file_utilities.py
--rw-r--r--   0 runner    (1001) docker     (123)     4315 2023-06-28 09:44:37.000000 moosez-2.1.4/moosez/image_conversion.py
--rw-r--r--   0 runner    (1001) docker     (123)    18964 2023-06-28 09:44:37.000000 moosez-2.1.4/moosez/image_processing.py
--rw-r--r--   0 runner    (1001) docker     (123)     4559 2023-06-28 09:44:37.000000 moosez-2.1.4/moosez/input_validation.py
--rw-r--r--   0 runner    (1001) docker     (123)     7410 2023-06-28 09:44:37.000000 moosez-2.1.4/moosez/moosez.py
--rw-r--r--   0 runner    (1001) docker     (123)    11697 2023-06-28 09:44:37.000000 moosez-2.1.4/moosez/predict.py
--rw-r--r--   0 runner    (1001) docker     (123)     3948 2023-06-28 09:44:37.000000 moosez-2.1.4/moosez/resources.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:44:46.781505 moosez-2.1.4/moosez.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     1408 2023-06-28 09:44:46.000000 moosez-2.1.4/moosez.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      445 2023-06-28 09:44:46.000000 moosez-2.1.4/moosez.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 09:44:46.000000 moosez-2.1.4/moosez.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       46 2023-06-28 09:44:46.000000 moosez-2.1.4/moosez.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (123)      273 2023-06-28 09:44:46.000000 moosez-2.1.4/moosez.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)        7 2023-06-28 09:44:46.000000 moosez-2.1.4/moosez.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 09:44:46.781505 moosez-2.1.4/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2279 2023-06-28 09:44:37.000000 moosez-2.1.4/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:38:05.711101 moosez-2.1.5/
+-rw-r--r--   0 runner    (1001) docker     (123)    11357 2023-06-28 15:37:56.000000 moosez-2.1.5/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     1408 2023-06-28 15:38:05.707101 moosez-2.1.5/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     9205 2023-06-28 15:37:56.000000 moosez-2.1.5/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:38:05.707101 moosez-2.1.5/moosez/
+-rw-r--r--   0 runner    (1001) docker     (123)      227 2023-06-28 15:37:56.000000 moosez-2.1.5/moosez/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1759 2023-06-28 15:37:56.000000 moosez-2.1.5/moosez/constants.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5407 2023-06-28 15:37:56.000000 moosez-2.1.5/moosez/display.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3630 2023-06-28 15:37:56.000000 moosez-2.1.5/moosez/download.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4152 2023-06-28 15:37:56.000000 moosez-2.1.5/moosez/file_utilities.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4315 2023-06-28 15:37:56.000000 moosez-2.1.5/moosez/image_conversion.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19480 2023-06-28 15:37:56.000000 moosez-2.1.5/moosez/image_processing.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4559 2023-06-28 15:37:56.000000 moosez-2.1.5/moosez/input_validation.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7410 2023-06-28 15:37:56.000000 moosez-2.1.5/moosez/moosez.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11697 2023-06-28 15:37:56.000000 moosez-2.1.5/moosez/predict.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3948 2023-06-28 15:37:56.000000 moosez-2.1.5/moosez/resources.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:38:05.707101 moosez-2.1.5/moosez.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     1408 2023-06-28 15:38:05.000000 moosez-2.1.5/moosez.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      445 2023-06-28 15:38:05.000000 moosez-2.1.5/moosez.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 15:38:05.000000 moosez-2.1.5/moosez.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       46 2023-06-28 15:38:05.000000 moosez-2.1.5/moosez.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      273 2023-06-28 15:38:05.000000 moosez-2.1.5/moosez.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        7 2023-06-28 15:38:05.000000 moosez-2.1.5/moosez.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 15:38:05.711101 moosez-2.1.5/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2279 2023-06-28 15:37:56.000000 moosez-2.1.5/setup.py
```

### Comparing `moosez-2.1.4/LICENSE` & `moosez-2.1.5/LICENSE`

 * *Files identical despite different names*

### Comparing `moosez-2.1.4/PKG-INFO` & `moosez-2.1.5/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: moosez
-Version: 2.1.4
+Version: 2.1.5
 Summary: An AI-inference engine for 3D clinical and preclinical whole-body segmentation tasks
 Home-page: https://github.com/QIMP-Team/mooseZ
 Author: Lalith Kumar Shiyam Sundar
 Author-email: Lalith.shiyamsundar@meduniwien.ac.at
 License: Apache 2.0
 Keywords: moosez model-zoo nnUNet medical-imaging tumor-segmentation organ-segmentation bone-segmentation lung-segmentation muscle-segmentation fat-segmentation vessel-segmentation vertebral-segmentation rib-segmentation preclinical-segmentation clinical-segmentation
 Classifier: Development Status :: 4 - Beta
```

### Comparing `moosez-2.1.4/README.md` & `moosez-2.1.5/README.md`

 * *Files identical despite different names*

### Comparing `moosez-2.1.4/moosez/constants.py` & `moosez-2.1.5/moosez/constants.py`

 * *Files identical despite different names*

### Comparing `moosez-2.1.4/moosez/display.py` & `moosez-2.1.5/moosez/display.py`

 * *Files identical despite different names*

### Comparing `moosez-2.1.4/moosez/download.py` & `moosez-2.1.5/moosez/download.py`

 * *Files identical despite different names*

### Comparing `moosez-2.1.4/moosez/file_utilities.py` & `moosez-2.1.5/moosez/file_utilities.py`

 * *Files identical despite different names*

### Comparing `moosez-2.1.4/moosez/image_conversion.py` & `moosez-2.1.5/moosez/image_conversion.py`

 * *Files identical despite different names*

### Comparing `moosez-2.1.4/moosez/image_processing.py` & `moosez-2.1.5/moosez/image_processing.py`

 * *Files 2% similar despite different names*

```diff
@@ -228,32 +228,43 @@
         return sitk_image
 
 
 class ImageResampler:
     @staticmethod
     def chunk_along_axis(axis: int) -> int:
         """
-        Determines the integer values that splits the axis evenly.
+        Determines the maximum number of evenly-sized chunks that the axis can be split into.
+        Each chunk is at least of size CHUNK_THRESHOLD.
 
         Args:
-            axis: the axis length as an integer.
+            axis (int): Length of the axis.
 
         Returns:
-            split: the determined integer values that splits the axis evenly.
+            int: The maximum number of evenly-sized chunks.
+
+        Raises:
+            ValueError: If axis is negative or if CHUNK_THRESHOLD is less than or equal to 0.
         """
-        split = 2
-        chunk_size = axis / split
-        rest = axis % split
-
-        while chunk_size >= CHUNK_THRESHOLD or rest != 0:
-            split += 1
-            chunk_size = axis / split
-            rest = axis % split
-            if split == axis:
-                return 1
+        # Check for negative input values
+        if axis < 0:
+            raise ValueError('Axis must be non-negative')
+
+        if CHUNK_THRESHOLD <= 0:
+            raise ValueError('CHUNK_THRESHOLD must be greater than 0')
+
+        # If the axis is smaller than the threshold, it cannot be split into smaller chunks
+        if axis < CHUNK_THRESHOLD:
+            return 1
+
+        # Determine the maximum number of chunks that the axis can be split into
+        split = axis // CHUNK_THRESHOLD
+
+        # Reduce the number of chunks until axis is evenly divisible by split
+        while axis % split != 0:
+            split -= 1
 
         return split
 
     @staticmethod
     def resample_chunk_SimpleITK(image_chunk: da.array, input_spacing: tuple, interpolation_method: int,
                                  output_spacing: tuple, output_size: tuple) -> da.array:
         """
```

### Comparing `moosez-2.1.4/moosez/input_validation.py` & `moosez-2.1.5/moosez/input_validation.py`

 * *Files identical despite different names*

### Comparing `moosez-2.1.4/moosez/moosez.py` & `moosez-2.1.5/moosez/moosez.py`

 * *Files identical despite different names*

### Comparing `moosez-2.1.4/moosez/predict.py` & `moosez-2.1.5/moosez/predict.py`

 * *Files identical despite different names*

### Comparing `moosez-2.1.4/moosez/resources.py` & `moosez-2.1.5/moosez/resources.py`

 * *Files identical despite different names*

### Comparing `moosez-2.1.4/moosez.egg-info/PKG-INFO` & `moosez-2.1.5/moosez.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: moosez
-Version: 2.1.4
+Version: 2.1.5
 Summary: An AI-inference engine for 3D clinical and preclinical whole-body segmentation tasks
 Home-page: https://github.com/QIMP-Team/mooseZ
 Author: Lalith Kumar Shiyam Sundar
 Author-email: Lalith.shiyamsundar@meduniwien.ac.at
 License: Apache 2.0
 Keywords: moosez model-zoo nnUNet medical-imaging tumor-segmentation organ-segmentation bone-segmentation lung-segmentation muscle-segmentation fat-segmentation vessel-segmentation vertebral-segmentation rib-segmentation preclinical-segmentation clinical-segmentation
 Classifier: Development Status :: 4 - Beta
```

### Comparing `moosez-2.1.4/setup.py` & `moosez-2.1.5/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 from setuptools import setup, find_packages
 
 
 setup(
     name='moosez',
-    version='2.1.4',
+    version='2.1.5',
     author='Lalith Kumar Shiyam Sundar',
     author_email='Lalith.shiyamsundar@meduniwien.ac.at',
     description='An AI-inference engine for 3D clinical and preclinical whole-body segmentation tasks',
     python_requires='>=3.9',
     long_description='mooseZ is an AI-inference engine based on nnUNet, designed for 3D clinical and preclinical'
                      ' whole-body segmentation tasks. It serves models tailored towards different modalities such'
                      ' as PET, CT, and MR. mooseZ provides fast and accurate segmentation results, making it a '
```

