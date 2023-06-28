# Comparing `tmp/moosez-2.1.5.tar.gz` & `tmp/moosez-2.1.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "moosez-2.1.5.tar", last modified: Wed Jun 28 15:38:05 2023, max compression
+gzip compressed data, was "moosez-2.1.6.tar", last modified: Wed Jun 28 16:07:08 2023, max compression
```

## Comparing `moosez-2.1.5.tar` & `moosez-2.1.6.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:38:05.711101 moosez-2.1.5/
--rw-r--r--   0 runner    (1001) docker     (123)    11357 2023-06-28 15:37:56.000000 moosez-2.1.5/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)     1408 2023-06-28 15:38:05.707101 moosez-2.1.5/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     9205 2023-06-28 15:37:56.000000 moosez-2.1.5/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:38:05.707101 moosez-2.1.5/moosez/
--rw-r--r--   0 runner    (1001) docker     (123)      227 2023-06-28 15:37:56.000000 moosez-2.1.5/moosez/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1759 2023-06-28 15:37:56.000000 moosez-2.1.5/moosez/constants.py
--rw-r--r--   0 runner    (1001) docker     (123)     5407 2023-06-28 15:37:56.000000 moosez-2.1.5/moosez/display.py
--rw-r--r--   0 runner    (1001) docker     (123)     3630 2023-06-28 15:37:56.000000 moosez-2.1.5/moosez/download.py
--rw-r--r--   0 runner    (1001) docker     (123)     4152 2023-06-28 15:37:56.000000 moosez-2.1.5/moosez/file_utilities.py
--rw-r--r--   0 runner    (1001) docker     (123)     4315 2023-06-28 15:37:56.000000 moosez-2.1.5/moosez/image_conversion.py
--rw-r--r--   0 runner    (1001) docker     (123)    19480 2023-06-28 15:37:56.000000 moosez-2.1.5/moosez/image_processing.py
--rw-r--r--   0 runner    (1001) docker     (123)     4559 2023-06-28 15:37:56.000000 moosez-2.1.5/moosez/input_validation.py
--rw-r--r--   0 runner    (1001) docker     (123)     7410 2023-06-28 15:37:56.000000 moosez-2.1.5/moosez/moosez.py
--rw-r--r--   0 runner    (1001) docker     (123)    11697 2023-06-28 15:37:56.000000 moosez-2.1.5/moosez/predict.py
--rw-r--r--   0 runner    (1001) docker     (123)     3948 2023-06-28 15:37:56.000000 moosez-2.1.5/moosez/resources.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:38:05.707101 moosez-2.1.5/moosez.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     1408 2023-06-28 15:38:05.000000 moosez-2.1.5/moosez.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      445 2023-06-28 15:38:05.000000 moosez-2.1.5/moosez.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 15:38:05.000000 moosez-2.1.5/moosez.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       46 2023-06-28 15:38:05.000000 moosez-2.1.5/moosez.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (123)      273 2023-06-28 15:38:05.000000 moosez-2.1.5/moosez.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)        7 2023-06-28 15:38:05.000000 moosez-2.1.5/moosez.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 15:38:05.711101 moosez-2.1.5/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2279 2023-06-28 15:37:56.000000 moosez-2.1.5/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 16:07:08.008209 moosez-2.1.6/
+-rw-r--r--   0 runner    (1001) docker     (123)    11357 2023-06-28 16:06:58.000000 moosez-2.1.6/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     1408 2023-06-28 16:07:08.008209 moosez-2.1.6/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     9205 2023-06-28 16:06:58.000000 moosez-2.1.6/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 16:07:08.008209 moosez-2.1.6/moosez/
+-rw-r--r--   0 runner    (1001) docker     (123)      227 2023-06-28 16:06:58.000000 moosez-2.1.6/moosez/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1759 2023-06-28 16:06:58.000000 moosez-2.1.6/moosez/constants.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5407 2023-06-28 16:06:58.000000 moosez-2.1.6/moosez/display.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3630 2023-06-28 16:06:58.000000 moosez-2.1.6/moosez/download.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4152 2023-06-28 16:06:58.000000 moosez-2.1.6/moosez/file_utilities.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4315 2023-06-28 16:06:58.000000 moosez-2.1.6/moosez/image_conversion.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19480 2023-06-28 16:06:58.000000 moosez-2.1.6/moosez/image_processing.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4559 2023-06-28 16:06:58.000000 moosez-2.1.6/moosez/input_validation.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7547 2023-06-28 16:06:58.000000 moosez-2.1.6/moosez/moosez.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11697 2023-06-28 16:06:58.000000 moosez-2.1.6/moosez/predict.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3948 2023-06-28 16:06:58.000000 moosez-2.1.6/moosez/resources.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 16:07:08.008209 moosez-2.1.6/moosez.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     1408 2023-06-28 16:07:08.000000 moosez-2.1.6/moosez.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      445 2023-06-28 16:07:08.000000 moosez-2.1.6/moosez.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 16:07:08.000000 moosez-2.1.6/moosez.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       46 2023-06-28 16:07:08.000000 moosez-2.1.6/moosez.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      273 2023-06-28 16:07:08.000000 moosez-2.1.6/moosez.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        7 2023-06-28 16:07:08.000000 moosez-2.1.6/moosez.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 16:07:08.008209 moosez-2.1.6/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2279 2023-06-28 16:06:58.000000 moosez-2.1.6/setup.py
```

### Comparing `moosez-2.1.5/LICENSE` & `moosez-2.1.6/LICENSE`

 * *Files identical despite different names*

### Comparing `moosez-2.1.5/PKG-INFO` & `moosez-2.1.6/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: moosez
-Version: 2.1.5
+Version: 2.1.6
 Summary: An AI-inference engine for 3D clinical and preclinical whole-body segmentation tasks
 Home-page: https://github.com/QIMP-Team/mooseZ
 Author: Lalith Kumar Shiyam Sundar
 Author-email: Lalith.shiyamsundar@meduniwien.ac.at
 License: Apache 2.0
 Keywords: moosez model-zoo nnUNet medical-imaging tumor-segmentation organ-segmentation bone-segmentation lung-segmentation muscle-segmentation fat-segmentation vessel-segmentation vertebral-segmentation rib-segmentation preclinical-segmentation clinical-segmentation
 Classifier: Development Status :: 4 - Beta
```

### Comparing `moosez-2.1.5/README.md` & `moosez-2.1.6/README.md`

 * *Files identical despite different names*

### Comparing `moosez-2.1.5/moosez/constants.py` & `moosez-2.1.6/moosez/constants.py`

 * *Files identical despite different names*

### Comparing `moosez-2.1.5/moosez/display.py` & `moosez-2.1.6/moosez/display.py`

 * *Files identical despite different names*

### Comparing `moosez-2.1.5/moosez/download.py` & `moosez-2.1.6/moosez/download.py`

 * *Files identical despite different names*

### Comparing `moosez-2.1.5/moosez/file_utilities.py` & `moosez-2.1.6/moosez/file_utilities.py`

 * *Files identical despite different names*

### Comparing `moosez-2.1.5/moosez/image_conversion.py` & `moosez-2.1.6/moosez/image_conversion.py`

 * *Files identical despite different names*

### Comparing `moosez-2.1.5/moosez/image_processing.py` & `moosez-2.1.6/moosez/image_processing.py`

 * *Files identical despite different names*

### Comparing `moosez-2.1.5/moosez/input_validation.py` & `moosez-2.1.6/moosez/input_validation.py`

 * *Files identical despite different names*

### Comparing `moosez-2.1.5/moosez/moosez.py` & `moosez-2.1.6/moosez/moosez.py`

 * *Files 6% similar despite different names*

```diff
@@ -170,14 +170,16 @@
         end_time = time.time()
         elapsed_time = end_time - start_time
         spinner.text = f' {constants.ANSI_GREEN}Prediction done for {os.path.basename(subject)} using {model_name}!' \
                        f' | Elapsed time: {round(elapsed_time / 60, 1)} min{constants.ANSI_RESET}'
         time.sleep(3)
     end_total_time = time.time()
     total_elapsed_time = (end_total_time - start_total_time) / 60
+    time_per_dataset = total_elapsed_time / len(moose_compliant_subjects)
+
     spinner.succeed(f'{constants.ANSI_GREEN} All predictions done! | Total elapsed time for '
-                    f'{len(moose_compliant_subjects)}: {round(total_elapsed_time, 1)} min'
-                    f' {constants.ANSI_RESET}')
+                    f'{len(moose_compliant_subjects)} datasets: {round(total_elapsed_time, 1)} min'
+                    f' | Time per dataset: {round(time_per_dataset, 2)} min {constants.ANSI_RESET}')
 
 
 if __name__ == '__main__':
     main()
```

### Comparing `moosez-2.1.5/moosez/predict.py` & `moosez-2.1.6/moosez/predict.py`

 * *Files identical despite different names*

### Comparing `moosez-2.1.5/moosez/resources.py` & `moosez-2.1.6/moosez/resources.py`

 * *Files identical despite different names*

### Comparing `moosez-2.1.5/moosez.egg-info/PKG-INFO` & `moosez-2.1.6/moosez.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: moosez
-Version: 2.1.5
+Version: 2.1.6
 Summary: An AI-inference engine for 3D clinical and preclinical whole-body segmentation tasks
 Home-page: https://github.com/QIMP-Team/mooseZ
 Author: Lalith Kumar Shiyam Sundar
 Author-email: Lalith.shiyamsundar@meduniwien.ac.at
 License: Apache 2.0
 Keywords: moosez model-zoo nnUNet medical-imaging tumor-segmentation organ-segmentation bone-segmentation lung-segmentation muscle-segmentation fat-segmentation vessel-segmentation vertebral-segmentation rib-segmentation preclinical-segmentation clinical-segmentation
 Classifier: Development Status :: 4 - Beta
```

### Comparing `moosez-2.1.5/setup.py` & `moosez-2.1.6/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 from setuptools import setup, find_packages
 
 
 setup(
     name='moosez',
-    version='2.1.5',
+    version='2.1.6',
     author='Lalith Kumar Shiyam Sundar',
     author_email='Lalith.shiyamsundar@meduniwien.ac.at',
     description='An AI-inference engine for 3D clinical and preclinical whole-body segmentation tasks',
     python_requires='>=3.9',
     long_description='mooseZ is an AI-inference engine based on nnUNet, designed for 3D clinical and preclinical'
                      ' whole-body segmentation tasks. It serves models tailored towards different modalities such'
                      ' as PET, CT, and MR. mooseZ provides fast and accurate segmentation results, making it a '
```

