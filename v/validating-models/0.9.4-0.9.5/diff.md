# Comparing `tmp/validating_models-0.9.4.tar.gz` & `tmp/validating_models-0.9.5.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "validating_models-0.9.4.tar", last modified: Tue Jun 27 12:27:05 2023, max compression
+gzip compressed data, was "validating_models-0.9.5.tar", last modified: Wed Jun 28 06:47:01 2023, max compression
```

## Comparing `validating_models-0.9.4.tar` & `validating_models-0.9.5.tar`

### file list

```diff
@@ -1,41 +1,41 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 12:27:05.644250 validating_models-0.9.4/
--rw-r--r--   0 runner    (1001) docker     (123)    35148 2023-06-27 12:26:54.000000 validating_models-0.9.4/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)       41 2023-06-27 12:26:54.000000 validating_models-0.9.4/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (123)     1960 2023-06-27 12:27:05.644250 validating_models-0.9.4/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1033 2023-06-27 12:26:54.000000 validating_models-0.9.4/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-27 12:27:05.644250 validating_models-0.9.4/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     1622 2023-06-27 12:26:54.000000 validating_models-0.9.4/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 12:27:05.640250 validating_models-0.9.4/validating_models/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 12:26:54.000000 validating_models-0.9.4/validating_models/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    19267 2023-06-27 12:26:54.000000 validating_models-0.9.4/validating_models/checker.py
--rw-r--r--   0 runner    (1001) docker     (123)      538 2023-06-27 12:26:54.000000 validating_models-0.9.4/validating_models/colors.py
--rw-r--r--   0 runner    (1001) docker     (123)     8533 2023-06-27 12:26:54.000000 validating_models-0.9.4/validating_models/constraint.py
--rw-r--r--   0 runner    (1001) docker     (123)    48649 2023-06-27 12:26:54.000000 validating_models-0.9.4/validating_models/dataset.py
--rw-r--r--   0 runner    (1001) docker     (123)    43216 2023-06-27 12:26:54.000000 validating_models-0.9.4/validating_models/drawing_utils.py
--rw-r--r--   0 runner    (1001) docker     (123)    23815 2023-06-27 12:26:54.000000 validating_models-0.9.4/validating_models/frequency_distribution_table.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 12:27:05.644250 validating_models-0.9.4/validating_models/groupings/
--rw-r--r--   0 runner    (1001) docker     (123)      398 2023-06-27 12:26:54.000000 validating_models-0.9.4/validating_models/groupings/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1287 2023-06-27 12:26:54.000000 validating_models-0.9.4/validating_models/groupings/classification.py
--rw-r--r--   0 runner    (1001) docker     (123)     1710 2023-06-27 12:26:54.000000 validating_models-0.9.4/validating_models/groupings/decision_trees.py
--rw-r--r--   0 runner    (1001) docker     (123)     1785 2023-06-27 12:26:54.000000 validating_models-0.9.4/validating_models/groupings/general.py
--rw-r--r--   0 runner    (1001) docker     (123)      645 2023-06-27 12:26:54.000000 validating_models-0.9.4/validating_models/groupings/random_forest.py
--rw-r--r--   0 runner    (1001) docker     (123)      399 2023-06-27 12:26:54.000000 validating_models-0.9.4/validating_models/logger.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 12:27:05.644250 validating_models-0.9.4/validating_models/models/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 12:26:54.000000 validating_models-0.9.4/validating_models/models/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2366 2023-06-27 12:26:54.000000 validating_models-0.9.4/validating_models/models/decision_tree.py
--rw-r--r--   0 runner    (1001) docker     (123)     3002 2023-06-27 12:26:54.000000 validating_models-0.9.4/validating_models/models/random_forest.py
--rw-r--r--   0 runner    (1001) docker     (123)     4609 2023-06-27 12:26:54.000000 validating_models-0.9.4/validating_models/shacl_validation_engine.py
--rw-r--r--   0 runner    (1001) docker     (123)     4218 2023-06-27 12:26:54.000000 validating_models-0.9.4/validating_models/stats.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 12:27:05.644250 validating_models-0.9.4/validating_models/visualizations/
--rw-r--r--   0 runner    (1001) docker     (123)      125 2023-06-27 12:26:54.000000 validating_models-0.9.4/validating_models/visualizations/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2404 2023-06-27 12:26:54.000000 validating_models-0.9.4/validating_models/visualizations/classification.py
--rw-r--r--   0 runner    (1001) docker     (123)    29424 2023-06-27 12:26:54.000000 validating_models-0.9.4/validating_models/visualizations/decision_trees.py
--rw-r--r--   0 runner    (1001) docker     (123)     6383 2023-06-27 12:26:54.000000 validating_models-0.9.4/validating_models/visualizations/ensembles.py
--rw-r--r--   0 runner    (1001) docker     (123)     5831 2023-06-27 12:26:54.000000 validating_models-0.9.4/validating_models/visualizations/graphviz_helper.py
--rw-r--r--   0 runner    (1001) docker     (123)     3404 2023-06-27 12:26:54.000000 validating_models-0.9.4/validating_models/visualizations/regression.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 12:27:05.644250 validating_models-0.9.4/validating_models.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     1960 2023-06-27 12:27:05.000000 validating_models-0.9.4/validating_models.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1204 2023-06-27 12:27:05.000000 validating_models-0.9.4/validating_models.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-27 12:27:05.000000 validating_models-0.9.4/validating_models.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)      186 2023-06-27 12:27:05.000000 validating_models-0.9.4/validating_models.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       18 2023-06-27 12:27:05.000000 validating_models-0.9.4/validating_models.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:47:01.385946 validating_models-0.9.5/
+-rw-r--r--   0 runner    (1001) docker     (123)    35148 2023-06-28 06:46:41.000000 validating_models-0.9.5/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)       41 2023-06-28 06:46:41.000000 validating_models-0.9.5/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)     1960 2023-06-28 06:47:01.381946 validating_models-0.9.5/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1033 2023-06-28 06:46:41.000000 validating_models-0.9.5/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 06:47:01.385946 validating_models-0.9.5/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     1622 2023-06-28 06:46:42.000000 validating_models-0.9.5/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:47:01.377946 validating_models-0.9.5/validating_models/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:46:42.000000 validating_models-0.9.5/validating_models/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19267 2023-06-28 06:46:42.000000 validating_models-0.9.5/validating_models/checker.py
+-rw-r--r--   0 runner    (1001) docker     (123)      538 2023-06-28 06:46:42.000000 validating_models-0.9.5/validating_models/colors.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8533 2023-06-28 06:46:42.000000 validating_models-0.9.5/validating_models/constraint.py
+-rw-r--r--   0 runner    (1001) docker     (123)    48649 2023-06-28 06:46:42.000000 validating_models-0.9.5/validating_models/dataset.py
+-rw-r--r--   0 runner    (1001) docker     (123)    43216 2023-06-28 06:46:42.000000 validating_models-0.9.5/validating_models/drawing_utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23815 2023-06-28 06:46:42.000000 validating_models-0.9.5/validating_models/frequency_distribution_table.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:47:01.381946 validating_models-0.9.5/validating_models/groupings/
+-rw-r--r--   0 runner    (1001) docker     (123)      398 2023-06-28 06:46:42.000000 validating_models-0.9.5/validating_models/groupings/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1287 2023-06-28 06:46:42.000000 validating_models-0.9.5/validating_models/groupings/classification.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1710 2023-06-28 06:46:42.000000 validating_models-0.9.5/validating_models/groupings/decision_trees.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1785 2023-06-28 06:46:42.000000 validating_models-0.9.5/validating_models/groupings/general.py
+-rw-r--r--   0 runner    (1001) docker     (123)      645 2023-06-28 06:46:42.000000 validating_models-0.9.5/validating_models/groupings/random_forest.py
+-rw-r--r--   0 runner    (1001) docker     (123)      399 2023-06-28 06:46:42.000000 validating_models-0.9.5/validating_models/logger.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:47:01.381946 validating_models-0.9.5/validating_models/models/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:46:42.000000 validating_models-0.9.5/validating_models/models/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2366 2023-06-28 06:46:42.000000 validating_models-0.9.5/validating_models/models/decision_tree.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3002 2023-06-28 06:46:42.000000 validating_models-0.9.5/validating_models/models/random_forest.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4609 2023-06-28 06:46:42.000000 validating_models-0.9.5/validating_models/shacl_validation_engine.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4218 2023-06-28 06:46:42.000000 validating_models-0.9.5/validating_models/stats.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:47:01.381946 validating_models-0.9.5/validating_models/visualizations/
+-rw-r--r--   0 runner    (1001) docker     (123)      125 2023-06-28 06:46:42.000000 validating_models-0.9.5/validating_models/visualizations/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2404 2023-06-28 06:46:42.000000 validating_models-0.9.5/validating_models/visualizations/classification.py
+-rw-r--r--   0 runner    (1001) docker     (123)    29424 2023-06-28 06:46:42.000000 validating_models-0.9.5/validating_models/visualizations/decision_trees.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6383 2023-06-28 06:46:42.000000 validating_models-0.9.5/validating_models/visualizations/ensembles.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5840 2023-06-28 06:46:42.000000 validating_models-0.9.5/validating_models/visualizations/graphviz_helper.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3404 2023-06-28 06:46:42.000000 validating_models-0.9.5/validating_models/visualizations/regression.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:47:01.381946 validating_models-0.9.5/validating_models.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     1960 2023-06-28 06:47:01.000000 validating_models-0.9.5/validating_models.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1204 2023-06-28 06:47:01.000000 validating_models-0.9.5/validating_models.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 06:47:01.000000 validating_models-0.9.5/validating_models.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      186 2023-06-28 06:47:01.000000 validating_models-0.9.5/validating_models.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       18 2023-06-28 06:47:01.000000 validating_models-0.9.5/validating_models.egg-info/top_level.txt
```

### Comparing `validating_models-0.9.4/LICENSE` & `validating_models-0.9.5/LICENSE`

 * *Files identical despite different names*

### Comparing `validating_models-0.9.4/PKG-INFO` & `validating_models-0.9.5/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 Metadata-Version: 2.1
 Name: validating_models
-Version: 0.9.4
+Version: 0.9.5
 Summary: Supporting Explainable AI on Semantic Constraint Validation
 Home-page: https://github.com/JulianLoewe/Validating_Models
-Download-URL: https://github.com/JulianLoewe/Validating_Models/archive/refs/tags/v0.9.4.tar.gz
+Download-URL: https://github.com/JulianLoewe/Validating_Models/archive/refs/tags/v0.9.5.tar.gz
 Author: Julian Gercke
 License: GNU/GPLv3
 Classifier: Development Status :: 4 - Beta
 Classifier: Programming Language :: Python
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3 :: Only
 Classifier: Programming Language :: Python :: 3.8
```

### Comparing `validating_models-0.9.4/README.md` & `validating_models-0.9.5/README.md`

 * *Files identical despite different names*

### Comparing `validating_models-0.9.4/setup.py` & `validating_models-0.9.5/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 #!/usr/bin/env python3
 import setuptools
 
-VERSION = '0.9.4'
+VERSION = '0.9.5'
 
 with open('README.md', 'r', encoding='utf-8') as fh:
     long_description = fh.read()
 
 setuptools.setup(
     name='validating_models',
     version=VERSION,
```

### Comparing `validating_models-0.9.4/validating_models/checker.py` & `validating_models-0.9.5/validating_models/checker.py`

 * *Files identical despite different names*

### Comparing `validating_models-0.9.4/validating_models/colors.py` & `validating_models-0.9.5/validating_models/colors.py`

 * *Files identical despite different names*

### Comparing `validating_models-0.9.4/validating_models/constraint.py` & `validating_models-0.9.5/validating_models/constraint.py`

 * *Files identical despite different names*

### Comparing `validating_models-0.9.4/validating_models/dataset.py` & `validating_models-0.9.5/validating_models/dataset.py`

 * *Files identical despite different names*

### Comparing `validating_models-0.9.4/validating_models/drawing_utils.py` & `validating_models-0.9.5/validating_models/drawing_utils.py`

 * *Files identical despite different names*

### Comparing `validating_models-0.9.4/validating_models/frequency_distribution_table.py` & `validating_models-0.9.5/validating_models/frequency_distribution_table.py`

 * *Files identical despite different names*

### Comparing `validating_models-0.9.4/validating_models/groupings/classification.py` & `validating_models-0.9.5/validating_models/groupings/classification.py`

 * *Files identical despite different names*

### Comparing `validating_models-0.9.4/validating_models/groupings/decision_trees.py` & `validating_models-0.9.5/validating_models/groupings/decision_trees.py`

 * *Files identical despite different names*

### Comparing `validating_models-0.9.4/validating_models/groupings/general.py` & `validating_models-0.9.5/validating_models/groupings/general.py`

 * *Files identical despite different names*

### Comparing `validating_models-0.9.4/validating_models/groupings/random_forest.py` & `validating_models-0.9.5/validating_models/groupings/random_forest.py`

 * *Files identical despite different names*

### Comparing `validating_models-0.9.4/validating_models/models/decision_tree.py` & `validating_models-0.9.5/validating_models/models/decision_tree.py`

 * *Files identical despite different names*

### Comparing `validating_models-0.9.4/validating_models/models/random_forest.py` & `validating_models-0.9.5/validating_models/models/random_forest.py`

 * *Files identical despite different names*

### Comparing `validating_models-0.9.4/validating_models/shacl_validation_engine.py` & `validating_models-0.9.5/validating_models/shacl_validation_engine.py`

 * *Files identical despite different names*

### Comparing `validating_models-0.9.4/validating_models/stats.py` & `validating_models-0.9.5/validating_models/stats.py`

 * *Files identical despite different names*

### Comparing `validating_models-0.9.4/validating_models/visualizations/classification.py` & `validating_models-0.9.5/validating_models/visualizations/classification.py`

 * *Files identical despite different names*

### Comparing `validating_models-0.9.4/validating_models/visualizations/decision_trees.py` & `validating_models-0.9.5/validating_models/visualizations/decision_trees.py`

 * *Files identical despite different names*

### Comparing `validating_models-0.9.4/validating_models/visualizations/ensembles.py` & `validating_models-0.9.5/validating_models/visualizations/ensembles.py`

 * *Files identical despite different names*

### Comparing `validating_models-0.9.4/validating_models/visualizations/graphviz_helper.py` & `validating_models-0.9.5/validating_models/visualizations/graphviz_helper.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,365 +1,365 @@
 00000000: 696d 706f 7274 206e 756d 7079 2061 7320  import numpy as 
 00000010: 6e70 0a66 726f 6d20 6474 7265 6576 697a  np.from dtreeviz
-00000020: 2e74 7265 6573 2069 6d70 6f72 7420 4454  .trees import DT
-00000030: 7265 6556 697a 4150 490a 696d 706f 7274  reeVizAPI.import
-00000040: 2074 656d 7066 696c 650a 696d 706f 7274   tempfile.import
-00000050: 206f 730a 6672 6f6d 2076 616c 6964 6174   os.from validat
-00000060: 696e 675f 6d6f 6465 6c73 2e73 7461 7473  ing_models.stats
-00000070: 2069 6d70 6f72 7420 6765 745f 6465 636f   import get_deco
-00000080: 7261 746f 720a 0a74 696d 655f 7069 6374  rator..time_pict
-00000090: 7572 655f 636f 706f 7369 7469 6f6e 203d  ure_coposition =
-000000a0: 2067 6574 5f64 6563 6f72 6174 6f72 2827   get_decorator('
-000000b0: 7069 6374 7572 655f 636f 6d70 6f73 6974  picture_composit
-000000c0: 696f 6e27 290a 0a74 6d70 203d 2074 656d  ion')..tmp = tem
-000000d0: 7066 696c 652e 6765 7474 656d 7064 6972  pfile.gettempdir
-000000e0: 2829 0a0a 636c 6173 7320 4454 7265 6556  ()..class DTreeV
-000000f0: 697a 436f 6e76 2844 5472 6565 5669 7a41  izConv(DTreeVizA
-00000100: 5049 293a 0a20 2020 2064 6566 205f 5f69  PI):.    def __i
-00000110: 6e69 745f 5f28 7365 6c66 2c20 646f 742c  nit__(self, dot,
-00000120: 2073 6361 6c65 3d31 2e30 293a 0a20 2020   scale=1.0):.   
-00000130: 2020 2020 2073 7570 6572 2829 2e5f 5f69       super().__i
-00000140: 6e69 745f 5f28 646f 742c 2073 6361 6c65  nit__(dot, scale
-00000150: 290a 2020 2020 0a20 2020 2040 7374 6174  ).    .    @stat
-00000160: 6963 6d65 7468 6f64 0a20 2020 2064 6566  icmethod.    def
-00000170: 2066 726f 6d5f 4454 7265 6556 697a 2864   from_DTreeViz(d
-00000180: 7472 6565 7669 7a29 3a0a 2020 2020 2020  treeviz):.      
-00000190: 2020 7265 7475 726e 2044 5472 6565 5669    return DTreeVi
-000001a0: 7a43 6f6e 7628 6474 7265 6576 697a 2e64  zConv(dtreeviz.d
-000001b0: 6f74 2c20 6474 7265 6576 697a 2e73 6361  ot, dtreeviz.sca
-000001c0: 6c65 290a 0a20 2020 2040 7469 6d65 5f70  le)..    @time_p
-000001d0: 6963 7475 7265 5f63 6f70 6f73 6974 696f  icture_copositio
-000001e0: 6e0a 2020 2020 6465 6620 7361 7665 2873  n.    def save(s
-000001f0: 656c 662c 2066 696c 656e 616d 652c 2074  elf, filename, t
-00000200: 7261 6e73 7061 7265 6e74 203d 2054 7275  ransparent = Tru
-00000210: 652c 2064 7069 3d31 3030 3029 3a0a 0a20  e, dpi=1000):.. 
-00000220: 2020 2020 2020 2064 6f74 5f69 6478 203d         dot_idx =
-00000230: 2066 696c 656e 616d 652e 7269 6e64 6578   filename.rindex
-00000240: 2827 2e27 290a 2020 2020 2020 2020 7376  ('.').        sv
-00000250: 675f 6669 6c65 203d 2066 696c 656e 616d  g_file = filenam
-00000260: 655b 3a64 6f74 5f69 6478 5d20 2b20 272e  e[:dot_idx] + '.
-00000270: 7376 6727 0a20 2020 2020 2020 2073 7570  svg'.        sup
-00000280: 6572 2829 2e73 6176 6528 7376 675f 6669  er().save(svg_fi
-00000290: 6c65 290a 2020 2020 2020 2020 0a20 2020  le).        .   
-000002a0: 2020 2020 2023 2041 6464 206d 6973 7369       # Add missi
-000002b0: 6e67 2068 6561 6465 720a 2020 2020 2020  ng header.      
-000002c0: 2020 6d69 7373 696e 675f 6865 6164 6572    missing_header
-000002d0: 203d 2027 3c3f 786d 6c20 7665 7273 696f   = '<?xml versio
-000002e0: 6e3d 2231 2e30 2220 656e 636f 6469 6e67  n="1.0" encoding
-000002f0: 3d22 7574 662d 3822 2073 7461 6e64 616c  ="utf-8" standal
-00000300: 6f6e 653d 226e 6f22 3f3e 5c6e 3c21 444f  one="no"?>\n<!DO
-00000310: 4354 5950 4520 7376 6720 5055 424c 4943  CTYPE svg PUBLIC
-00000320: 2022 2d2f 2f57 3343 2f2f 4454 4420 5356   "-//W3C//DTD SV
-00000330: 4720 312e 312f 2f45 4e22 2022 6874 7470  G 1.1//EN" "http
-00000340: 3a2f 2f77 7777 2e77 332e 6f72 672f 4772  ://www.w3.org/Gr
-00000350: 6170 6869 6373 2f53 5647 2f31 2e31 2f44  aphics/SVG/1.1/D
-00000360: 5444 2f73 7667 3131 2e64 7464 223e 5c6e  TD/svg11.dtd">\n
-00000370: 270a 2020 2020 2020 2020 7769 7468 206f  '.        with o
-00000380: 7065 6e28 7376 675f 6669 6c65 2c20 2772  pen(svg_file, 'r
-00000390: 2729 2061 7320 6f72 6967 696e 616c 3a0a  ') as original:.
-000003a0: 2020 2020 2020 2020 2020 2020 7376 675f              svg_
-000003b0: 636f 6e74 656e 7420 3d20 6f72 6967 696e  content = origin
-000003c0: 616c 2e72 6561 6428 290a 2020 2020 2020  al.read().      
-000003d0: 2020 0a20 2020 2020 2020 2069 6620 6669    .        if fi
-000003e0: 6c65 6e61 6d65 2e65 6e64 7377 6974 6828  lename.endswith(
-000003f0: 272e 7376 6727 293a 0a20 2020 2020 2020  '.svg'):.       
-00000400: 2020 2020 2077 6974 6820 6f70 656e 2866       with open(f
-00000410: 696c 656e 616d 652c 2027 7727 2920 6173  ilename, 'w') as
-00000420: 206e 6577 3a0a 2020 2020 2020 2020 2020   new:.          
-00000430: 2020 2020 2020 6e65 772e 7772 6974 6528        new.write(
-00000440: 6d69 7373 696e 675f 6865 6164 6572 290a  missing_header).
-00000450: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00000460: 6e65 772e 7772 6974 6528 7376 675f 636f  new.write(svg_co
-00000470: 6e74 656e 7429 0a20 2020 2020 2020 2065  ntent).        e
-00000480: 6c73 653a 0a20 2020 2020 2020 2020 2020  lse:.           
-00000490: 2069 6d70 6f72 7420 6361 6972 6f73 7667   import cairosvg
-000004a0: 0a20 2020 2020 2020 2020 2020 2069 6d70  .            imp
-000004b0: 6f72 7420 696f 0a20 2020 2020 2020 2020  ort io.         
-000004c0: 2020 2066 726f 6d20 5049 4c20 696d 706f     from PIL impo
-000004d0: 7274 2049 6d61 6765 0a20 2020 2020 2020  rt Image.       
-000004e0: 2020 2020 206f 7574 7075 745f 706e 6720       output_png 
-000004f0: 3d20 696f 2e42 7974 6573 494f 2829 0a20  = io.BytesIO(). 
-00000500: 2020 2020 2020 2020 2020 2063 6169 726f             cairo
-00000510: 7376 672e 7376 6732 706e 6728 6279 7465  svg.svg2png(byte
-00000520: 7374 7269 6e67 3d73 7667 5f63 6f6e 7465  string=svg_conte
-00000530: 6e74 2c20 7772 6974 655f 746f 3d6f 7574  nt, write_to=out
-00000540: 7075 745f 706e 672c 2073 6361 6c65 3d64  put_png, scale=d
-00000550: 7069 2f31 3030 290a 2020 2020 2020 2020  pi/100).        
-00000560: 2020 2020 696d 203d 2049 6d61 6765 2e6f      im = Image.o
-00000570: 7065 6e28 6f75 7470 7574 5f70 6e67 290a  pen(output_png).
-00000580: 2020 2020 2020 2020 2020 2020 6f75 7470              outp
-00000590: 7574 5f70 6e67 2e63 6c6f 7365 2829 0a0a  ut_png.close()..
-000005a0: 2020 2020 2020 2020 2020 2020 6966 2074              if t
-000005b0: 7261 6e73 7061 7265 6e74 3a0a 2020 2020  ransparent:.    
-000005c0: 2020 2020 2020 2020 2020 2020 696d 203d              im =
-000005d0: 2069 6d2e 636f 6e76 6572 7428 2752 4742   im.convert('RGB
-000005e0: 4127 290a 2020 2020 2020 2020 2020 2020  A').            
-000005f0: 2020 2020 6461 7461 203d 206e 702e 6172      data = np.ar
-00000600: 7261 7928 696d 290a 2020 2020 2020 2020  ray(im).        
-00000610: 2020 2020 2020 2020 2370 7269 6e74 2864          #print(d
-00000620: 6174 612e 7368 6170 6529 0a20 2020 2020  ata.shape).     
-00000630: 2020 2020 2020 2020 2020 2072 6762 203d             rgb =
-00000640: 2064 6174 615b 3a2c 3a2c 3a33 5d0a 2020   data[:,:,:3].  
-00000650: 2020 2020 2020 2020 2020 2020 2020 7768                wh
-00000660: 6974 6520 3d20 5b32 3535 2c32 3535 2c32  ite = [255,255,2
-00000670: 3535 5d0a 2020 2020 2020 2020 2020 2020  55].            
-00000680: 2020 2020 7472 616e 7370 6172 656e 7420      transparent 
-00000690: 3d20 5b32 3535 2c32 3535 2c32 3535 2c30  = [255,255,255,0
-000006a0: 5d0a 2020 2020 2020 2020 2020 2020 2020  ].              
-000006b0: 2020 6d61 736b 203d 206e 702e 616c 6c28    mask = np.all(
-000006c0: 7267 6220 3d3d 2077 6869 7465 2c20 6178  rgb == white, ax
-000006d0: 6973 203d 202d 3129 0a20 2020 2020 2020  is = -1).       
-000006e0: 2020 2020 2020 2020 2023 7072 696e 7428           #print(
-000006f0: 6e70 2e73 756d 286d 6173 6b29 290a 2020  np.sum(mask)).  
-00000700: 2020 2020 2020 2020 2020 2020 2020 6461                da
-00000710: 7461 5b6d 6173 6b5d 203d 2074 7261 6e73  ta[mask] = trans
-00000720: 7061 7265 6e74 0a20 2020 2020 2020 2020  parent.         
-00000730: 2020 2020 2020 2069 6d20 3d20 496d 6167         im = Imag
-00000740: 652e 6672 6f6d 6172 7261 7928 6461 7461  e.fromarray(data
-00000750: 290a 0a20 2020 2020 2020 2020 2020 2069  )..            i
-00000760: 6d2e 7361 7665 2866 696c 656e 616d 6529  m.save(filename)
-00000770: 0a0a 0a0a 6465 6620 6874 6d6c 5f6c 6162  ....def html_lab
-00000780: 656c 286c 6162 656c 2c20 636f 6c6f 722c  el(label, color,
-00000790: 2073 697a 6529 3a0a 2020 2020 2727 2752   size):.    '''R
-000007a0: 6574 7572 6e73 2074 6865 2068 746d 6c20  eturns the html 
-000007b0: 7265 7072 6573 656e 7461 7469 6f6e 2074  representation t
-000007c0: 6f20 7368 6f77 2061 206c 6162 656c 2069  o show a label i
-000007d0: 6e20 6120 6874 6d6c 2074 6162 6c65 2e0a  n a html table..
-000007e0: 2020 2020 2727 270a 2020 2020 7265 7475      '''.    retu
-000007f0: 726e 2066 273c 666f 6e74 2066 6163 653d  rn f'<font face=
-00000800: 2248 656c 7665 7469 6361 2220 636f 6c6f  "Helvetica" colo
-00000810: 723d 227b 636f 6c6f 727d 2220 706f 696e  r="{color}" poin
-00000820: 742d 7369 7a65 3d22 7b73 697a 657d 223e  t-size="{size}">
-00000830: 3c69 3e7b 6c61 6265 6c7d 3c2f 693e 3c2f  <i>{label}</i></
-00000840: 666f 6e74 3e27 0a0a 6465 6620 6874 6d6c  font>'..def html
-00000850: 5f69 6d61 6765 2868 746d 6c5f 6c61 6265  _image(html_labe
-00000860: 6c2c 2069 6d67 5f70 6174 6829 3a0a 2020  l, img_path):.  
-00000870: 2020 2727 2752 6574 7572 6e73 2074 6865    '''Returns the
-00000880: 2068 746d 6c20 7265 7072 6573 656e 7461   html representa
-00000890: 7469 6f6e 2074 6f20 7368 6f77 2074 6865  tion to show the
-000008a0: 206c 6162 656c 2061 626f 7665 2074 6865   label above the
-000008b0: 2067 6976 656e 2069 6d61 6765 2e0a 2020   given image..  
-000008c0: 2020 2727 270a 2020 2020 6874 6d6c 5f6c    '''.    html_l
-000008d0: 6162 656c 5f72 6f77 203d 2066 273c 7472  abel_row = f'<tr
-000008e0: 3e3c 7464 2043 454c 4c50 4144 4449 4e47  ><td CELLPADDING
-000008f0: 3d22 3022 2043 454c 4c53 5041 4349 4e47  ="0" CELLSPACING
-00000900: 3d22 3022 3e7b 6874 6d6c 5f6c 6162 656c  ="0">{html_label
-00000910: 7d3c 2f74 643e 3c2f 7472 3e27 0a20 2020  }</td></tr>'.   
-00000920: 2072 6574 7572 6e20 6622 2222 3c74 6162   return f"""<tab
-00000930: 6c65 2062 6f72 6465 723d 2230 2220 4345  le border="0" CE
-00000940: 4c4c 424f 5244 4552 3d22 3022 3e0a 2020  LLBORDER="0">.  
-00000950: 2020 2020 2020 7b68 746d 6c5f 6c61 6265        {html_labe
-00000960: 6c5f 726f 777d 0a20 2020 2020 2020 203c  l_row}.        <
-00000970: 7472 3e0a 2020 2020 2020 2020 2020 2020  tr>.            
-00000980: 2020 2020 3c74 643e 3c69 6d67 2073 7263      <td><img src
-00000990: 3d22 7b69 6d67 5f70 6174 687d 222f 3e3c  ="{img_path}"/><
-000009a0: 2f74 643e 0a20 2020 2020 2020 203c 2f74  /td>.        </t
-000009b0: 723e 0a20 2020 2020 2020 203c 2f74 6162  r>.        </tab
-000009c0: 6c65 3e22 2222 0a0a 6465 6620 6874 6d6c  le>"""..def html
-000009d0: 5f6e 6f64 655f 6c61 6265 6c28 6e6f 6465  _node_label(node
-000009e0: 2c20 636f 6c6f 722c 2073 697a 6529 3a0a  , color, size):.
-000009f0: 2020 2020 7265 7475 726e 2068 746d 6c5f      return html_
-00000a00: 6c61 6265 6c28 6622 4e6f 6465 207b 6e6f  label(f"Node {no
-00000a10: 6465 2e69 647d 222c 636f 6c6f 722c 2073  de.id}",color, s
-00000a20: 697a 6529 0a0a 6465 6620 6e6f 6465 5f73  ize)..def node_s
-00000a30: 746d 7428 6e6f 6465 5f6e 616d 652c 2068  tmt(node_name, h
-00000a40: 746d 6c5f 636f 6e74 656e 742c 2068 6967  tml_content, hig
-00000a50: 686c 6967 6874 3a62 6f6f 6c2c 2063 6f6c  hlight:bool, col
-00000a60: 6f72 7329 3a0a 2020 2020 6966 2068 6967  ors):.    if hig
-00000a70: 686c 6967 6874 3a0a 2020 2020 2020 2020  hlight:.        
-00000a80: 7265 7475 726e 2066 277b 6e6f 6465 5f6e  return f'{node_n
-00000a90: 616d 657d 205b 6d61 7267 696e 3d22 3022  ame} [margin="0"
-00000aa0: 2073 6861 7065 3d62 6f78 2070 656e 7769   shape=box penwi
-00000ab0: 6474 683d 222e 3522 2063 6f6c 6f72 3d22  dth=".5" color="
-00000ac0: 7b63 6f6c 6f72 735b 2268 6967 686c 6967  {colors["highlig
-00000ad0: 6874 225d 7d22 2073 7479 6c65 3d22 6461  ht"]}" style="da
-00000ae0: 7368 6564 2220 6c61 6265 6c3d 3c7b 6874  shed" label=<{ht
-00000af0: 6d6c 5f63 6f6e 7465 6e74 7d3e 5d27 200a  ml_content}>]' .
-00000b00: 2020 2020 656c 7365 3a20 0a20 2020 2020      else: .     
-00000b10: 2020 2072 6574 7572 6e20 6627 7b6e 6f64     return f'{nod
-00000b20: 655f 6e61 6d65 7d20 5b6d 6172 6769 6e3d  e_name} [margin=
-00000b30: 2230 2220 7368 6170 653d 626f 7820 7065  "0" shape=box pe
-00000b40: 6e77 6964 7468 3d22 3022 2063 6f6c 6f72  nwidth="0" color
-00000b50: 3d22 7b63 6f6c 6f72 735b 2274 6578 7422  ="{colors["text"
-00000b60: 5d7d 2220 6c61 6265 6c3d 3c7b 6874 6d6c  ]}" label=<{html
-00000b70: 5f63 6f6e 7465 6e74 7d3e 5d27 0a0a 6465  _content}>]'..de
-00000b80: 6620 636c 7573 7465 725f 6e6f 6465 7328  f cluster_nodes(
-00000b90: 636c 7573 7465 725f 6e61 6d65 2c20 6c61  cluster_name, la
-00000ba0: 6265 6c2c 206e 6f64 6573 293a 0a20 2020  bel, nodes):.   
-00000bb0: 206e 6577 6c69 6e65 203d 2022 5c6e 5c74   newline = "\n\t
-00000bc0: 220a 2020 2020 7265 7475 726e 2066 2727  ".    return f''
-00000bd0: 2773 7562 6772 6170 6820 636c 7573 7465  'subgraph cluste
-00000be0: 725f 7b63 6c75 7374 6572 5f6e 616d 657d  r_{cluster_name}
-00000bf0: 207b 7b0a 2020 2020 2020 2020 636f 6c6f   {{.        colo
-00000c00: 723d 6c69 6768 7467 7265 793b 0a20 2020  r=lightgrey;.   
-00000c10: 2020 2020 206c 6162 656c 3d22 7b6c 6162       label="{lab
-00000c20: 656c 7d22 3b0a 2020 2020 2020 2020 7b6e  el}";.        {n
-00000c30: 6577 6c69 6e65 2e6a 6f69 6e28 6e6f 6465  ewline.join(node
-00000c40: 7329 7d0a 2020 2020 7d7d 0a20 2020 2027  s)}.    }}.    '
-00000c50: 2727 0a0a 6465 6620 636c 6173 735f 6c65  ''..def class_le
-00000c60: 6765 6e64 5f67 7228 7061 7468 293a 0a20  gend_gr(path):. 
-00000c70: 2020 2069 6620 7061 7468 2021 3d20 4e6f     if path != No
-00000c80: 6e65 3a0a 2020 2020 2020 2020 7265 7475  ne:.        retu
-00000c90: 726e 2066 2727 2773 7562 6772 6170 6820  rn f'''subgraph 
-00000ca0: 636c 7573 7465 725f 6c65 6765 6e64 207b  cluster_legend {
-00000cb0: 7b0a 2020 2020 2020 2020 2020 2020 2020  {.              
-00000cc0: 2020 7374 796c 653d 696e 7669 733b 0a20    style=invis;. 
-00000cd0: 2020 2020 2020 2020 2020 2020 2020 206c                 l
-00000ce0: 6567 656e 6420 5b70 656e 7769 6474 683d  egend [penwidth=
-00000cf0: 2230 2220 6d61 7267 696e 3d22 3022 2073  "0" margin="0" s
-00000d00: 6861 7065 3d62 6f78 206d 6172 6769 6e3d  hape=box margin=
-00000d10: 2230 2e30 3322 2077 6964 7468 3d2e 312c  "0.03" width=.1,
-00000d20: 2068 6569 6768 743d 2e31 206c 6162 656c   height=.1 label
-00000d30: 3d3c 0a20 2020 2020 2020 2020 2020 2020  =<.             
-00000d40: 2020 207b 6874 6d6c 5f69 6d61 6765 2827     {html_image('
-00000d50: 272c 2070 6174 6829 7d0a 2020 2020 2020  ', path)}.      
-00000d60: 2020 2020 2020 2020 2020 3e5d 0a20 2020            >].   
-00000d70: 2020 2020 2020 2020 207d 7d0a 2020 2020           }}.    
-00000d80: 2020 2020 2020 2020 2727 270a 2020 2020          '''.    
-00000d90: 656c 7365 3a0a 2020 2020 2020 2020 7265  else:.        re
-00000da0: 7475 726e 2027 270a 0a64 6566 2067 6574  turn ''..def get
-00000db0: 5f69 6d61 6765 5f70 6174 6828 6964 656e  _image_path(iden
-00000dc0: 7469 6669 6572 3a20 7374 7229 3a0a 2020  tifier: str):.  
-00000dd0: 2020 7265 7475 726e 206f 732e 7061 7468    return os.path
-00000de0: 2e6a 6f69 6e28 746d 702c 6622 7b74 6d70  .join(tmp,f"{tmp
-00000df0: 7d2f 7b69 6465 6e74 6966 6965 727d 5f7b  }/{identifier}_{
-00000e00: 6f73 2e67 6574 7069 6428 297d 2e73 7667  os.getpid()}.svg
-00000e10: 2229 0a0a 6465 6620 6772 6964 5f6c 6179  ")..def grid_lay
-00000e20: 6f75 7428 7469 746c 652c 206e 6f64 6573  out(title, nodes
-00000e30: 2c20 6564 6765 732c 206c 6567 656e 642c  , edges, legend,
-00000e40: 2063 6f6c 6f72 732c 2073 697a 653d 4e6f   colors, size=No
-00000e50: 6e65 2c20 666f 6e74 6e61 6d65 3d27 4865  ne, fontname='He
-00000e60: 6c76 6574 6963 6127 2c20 7363 616c 653d  lvetica', scale=
-00000e70: 312e 302c 206f 7269 656e 7461 7469 6f6e  1.0, orientation
-00000e80: 203d 2027 4c52 2729 3a20 2320 4c52 206f   = 'LR'): # LR o
-00000e90: 7220 5444 0a20 2020 206e 6f64 655f 6e61  r TD.    node_na
-00000ea0: 6d65 7320 3d20 5b6e 6f64 652e 7370 6c69  mes = [node.spli
-00000eb0: 7428 2220 222c 3129 5b30 5d20 6966 206e  t(" ",1)[0] if n
-00000ec0: 6f64 652e 7370 6c69 7428 2220 222c 3129  ode.split(" ",1)
-00000ed0: 5b30 5d20 213d 2027 7375 6267 7261 7068  [0] != 'subgraph
-00000ee0: 2720 656c 7365 206e 6f64 652e 7370 6c69  ' else node.spli
-00000ef0: 7428 2220 222c 3229 5b31 5d20 666f 7220  t(" ",2)[1] for 
-00000f00: 6e6f 6465 2069 6e20 6e6f 6465 735d 0a20  node in nodes]. 
-00000f10: 2020 2069 6620 7369 7a65 203d 3d20 4e6f     if size == No
-00000f20: 6e65 3a0a 2020 2020 2020 2020 6772 6964  ne:.        grid
-00000f30: 5f73 697a 6520 3d20 696e 7428 6e70 2e63  _size = int(np.c
-00000f40: 6569 6c28 6e70 2e73 7172 7428 6c65 6e28  eil(np.sqrt(len(
-00000f50: 6e6f 6465 5f6e 616d 6573 2929 2929 0a20  node_names)))). 
-00000f60: 2020 2020 2020 2073 697a 6520 3d20 2867         size = (g
-00000f70: 7269 645f 7369 7a65 2c67 7269 645f 7369  rid_size,grid_si
-00000f80: 7a65 290a 0a20 2020 2073 697a 6520 3d20  ze)..    size = 
-00000f90: 6c69 7374 2873 697a 6529 0a20 2020 206e  list(size).    n
-00000fa0: 756d 5f6e 6f64 6573 203d 2073 697a 655b  um_nodes = size[
-00000fb0: 305d 202a 2073 697a 655b 315d 0a0a 2020  0] * size[1]..  
-00000fc0: 2020 6269 675f 696e 6465 7820 3d20 3020    big_index = 0 
-00000fd0: 6966 2073 697a 655b 305d 203e 2073 697a  if size[0] > siz
-00000fe0: 655b 315d 2065 6c73 6520 310a 0a20 2020  e[1] else 1..   
-00000ff0: 2077 6869 6c65 206e 756d 5f6e 6f64 6573   while num_nodes
-00001000: 203e 3d20 6c65 6e28 6e6f 6465 7329 202b   >= len(nodes) +
-00001010: 2073 697a 655b 6269 675f 696e 6465 785d   size[big_index]
-00001020: 3a0a 2020 2020 2020 2020 7369 7a65 5b62  :.        size[b
-00001030: 6967 5f69 6e64 6578 5d20 3d20 7369 7a65  ig_index] = size
-00001040: 5b62 6967 5f69 6e64 6578 5d20 2d20 310a  [big_index] - 1.
-00001050: 2020 2020 2020 2020 6e75 6d5f 6e6f 6465          num_node
-00001060: 7320 3d20 7369 7a65 5b30 5d20 2a20 7369  s = size[0] * si
-00001070: 7a65 5b31 5d0a 2020 2020 0a20 2020 2077  ze[1].    .    w
-00001080: 6869 6c65 206e 756d 5f6e 6f64 6573 203e  hile num_nodes >
-00001090: 3d20 6c65 6e28 6e6f 6465 7329 202b 2073  = len(nodes) + s
-000010a0: 697a 655b 2862 6967 5f69 6e64 6578 202b  ize[(big_index +
-000010b0: 2031 2920 2520 325d 3a0a 2020 2020 2020   1) % 2]:.      
-000010c0: 2020 7369 7a65 5b28 6269 675f 696e 6465    size[(big_inde
-000010d0: 7820 2b20 3129 2025 2032 5d20 3d20 7369  x + 1) % 2] = si
-000010e0: 7a65 5b28 6269 675f 696e 6465 7820 2b20  ze[(big_index + 
-000010f0: 3129 2025 2032 5d20 2d20 310a 2020 2020  1) % 2] - 1.    
-00001100: 2020 2020 6e75 6d5f 6e6f 6465 7320 3d20      num_nodes = 
-00001110: 7369 7a65 5b30 5d20 2a20 7369 7a65 5b31  size[0] * size[1
-00001120: 5d0a 0a20 2020 2023 2046 696c 6c20 6772  ]..    # Fill gr
-00001130: 6964 2077 6974 6820 7370 6163 6568 6f6c  id with spacehol
-00001140: 6465 7220 6e6f 6465 730a 2020 2020 6e75  der nodes.    nu
-00001150: 6d5f 7370 6163 6568 6f6c 6465 7273 203d  m_spaceholders =
-00001160: 2030 0a20 2020 2077 6869 6c65 206c 656e   0.    while len
-00001170: 286e 6f64 6573 2920 3c20 6e75 6d5f 6e6f  (nodes) < num_no
-00001180: 6465 733a 0a20 2020 2020 2020 206e 756d  des:.        num
-00001190: 5f73 7061 6365 686f 6c64 6572 7320 2b3d  _spaceholders +=
-000011a0: 2031 0a20 2020 2020 2020 206e 6f64 6573   1.        nodes
-000011b0: 2e61 7070 656e 6428 6e6f 6465 5f73 746d  .append(node_stm
-000011c0: 7428 6627 7370 6163 6568 6f6c 6465 727b  t(f'spaceholder{
-000011d0: 6e75 6d5f 7370 6163 6568 6f6c 6465 7273  num_spaceholders
-000011e0: 7d27 2c20 2727 2c20 4661 6c73 652c 2063  }', '', False, c
-000011f0: 6f6c 6f72 7329 290a 2020 2020 2020 2020  olors)).        
-00001200: 6e6f 6465 5f6e 616d 6573 2e61 7070 656e  node_names.appen
-00001210: 6428 6627 7370 6163 6568 6f6c 6465 727b  d(f'spaceholder{
-00001220: 6e75 6d5f 7370 6163 6568 6f6c 6465 7273  num_spaceholders
-00001230: 7d27 290a 0a20 2020 206e 6f64 655f 6e61  }')..    node_na
-00001240: 6d65 7320 3d20 6e70 2e61 7272 6179 286e  mes = np.array(n
-00001250: 6f64 655f 6e61 6d65 7329 2e72 6573 6861  ode_names).resha
-00001260: 7065 2828 7369 7a65 5b30 5d2c 7369 7a65  pe((size[0],size
-00001270: 5b31 5d29 290a 2020 2020 2320 4372 6561  [1])).    # Crea
-00001280: 7465 2067 7269 6420 7374 7275 6374 7572  te grid structur
-00001290: 650a 2020 2020 6772 6964 5f65 6467 6573  e.    grid_edges
-000012a0: 203d 205b 5d0a 2020 2020 666f 7220 6920   = [].    for i 
-000012b0: 696e 2072 616e 6765 2873 697a 655b 305d  in range(size[0]
-000012c0: 293a 200a 2020 2020 2020 2020 2320 486f  ): .        # Ho
-000012d0: 7269 7a6f 6e74 616c 2043 6f6e 6e65 6374  rizontal Connect
-000012e0: 696f 6e73 0a20 2020 2020 2020 2076 6563  ions.        vec
-000012f0: 203d 206e 6f64 655f 6e61 6d65 735b 692c   = node_names[i,
-00001300: 3a5d 0a20 2020 2020 2020 2076 6563 203d  :].        vec =
-00001310: 206c 6973 7428 7665 632e 7265 7368 6170   list(vec.reshap
-00001320: 6528 2d31 2c29 290a 2020 2020 2020 2020  e(-1,)).        
-00001330: 6966 206c 656e 2876 6563 2920 3e20 313a  if len(vec) > 1:
-00001340: 0a20 2020 2020 2020 2020 2020 2067 7269  .            gri
-00001350: 645f 6564 6765 732e 6170 7065 6e64 2827  d_edges.append('
-00001360: 7261 6e6b 3d73 616d 6520 7b27 202b 2027  rank=same {' + '
-00001370: 202d 2d20 272e 6a6f 696e 2876 6563 2920   -- '.join(vec) 
-00001380: 2b20 277d 2729 0a20 2020 200a 2020 2020  + '}').    .    
-00001390: 666f 7220 6a20 696e 2072 616e 6765 2873  for j in range(s
-000013a0: 697a 655b 315d 293a 0a20 2020 2020 2020  ize[1]):.       
-000013b0: 2023 2056 6572 7469 6361 6c20 436f 6e6e   # Vertical Conn
-000013c0: 6563 7469 6f6e 730a 2020 2020 2020 2020  ections.        
-000013d0: 7665 6320 3d20 6e6f 6465 5f6e 616d 6573  vec = node_names
-000013e0: 5b3a 2c6a 5d0a 2020 2020 2020 2020 7665  [:,j].        ve
-000013f0: 6320 3d20 6c69 7374 2876 6563 2e72 6573  c = list(vec.res
-00001400: 6861 7065 282d 312c 2929 0a20 2020 2020  hape(-1,)).     
-00001410: 2020 2069 6620 6c65 6e28 7665 6329 203e     if len(vec) >
-00001420: 2031 3a0a 2020 2020 2020 2020 2020 2020   1:.            
-00001430: 6772 6964 5f65 6467 6573 2e61 7070 656e  grid_edges.appen
-00001440: 6428 2720 2d2d 2027 2e6a 6f69 6e28 7665  d(' -- '.join(ve
-00001450: 6329 290a 2020 2020 2020 2020 0a20 2020  c)).        .   
-00001460: 2020 2020 2069 6620 6f72 6965 6e74 6174       if orientat
-00001470: 696f 6e20 3d3d 2027 4c52 2720 616e 6420  ion == 'LR' and 
-00001480: 6a20 3d3d 2030 2061 6e64 206c 6567 656e  j == 0 and legen
-00001490: 6420 213d 204e 6f6e 653a 0a20 2020 2020  d != None:.     
-000014a0: 2020 2020 2020 2067 7269 645f 6564 6765         grid_edge
-000014b0: 732e 6170 7065 6e64 2827 202d 2d20 6c65  s.append(' -- le
-000014c0: 6765 6e64 2729 0a0a 0a20 2020 206e 6577  gend')...    new
-000014d0: 6c69 6e65 203d 2022 5c6e 5c74 220a 2020  line = "\n\t".  
-000014e0: 2020 646f 7420 3d20 6627 2727 0a20 2020    dot = f'''.   
-000014f0: 2067 7261 7068 2047 207b 7b0a 2020 2020   graph G {{.    
-00001500: 2020 2020 7370 6c69 6e65 733d 6c69 6e65      splines=line
-00001510: 3b0a 2020 2020 2020 2020 666f 6e74 6e61  ;.        fontna
-00001520: 6d65 3d22 7b66 6f6e 746e 616d 657d 220a  me="{fontname}".
-00001530: 2020 2020 2020 2020 6e6f 6465 205b 666f          node [fo
-00001540: 6e74 6e61 6d65 3d22 7b66 6f6e 746e 616d  ntname="{fontnam
-00001550: 657d 225d 0a20 2020 2020 2020 2065 6467  e}"].        edg
-00001560: 6520 5b66 6f6e 746e 616d 653d 227b 666f  e [fontname="{fo
-00001570: 6e74 6e61 6d65 7d22 5d0a 2020 2020 2020  ntname}"].      
-00001580: 2020 6c61 796f 7574 3d64 6f74 0a20 2020    layout=dot.   
-00001590: 2020 2020 206c 6162 656c 3d22 7b74 6974       label="{tit
-000015a0: 6c65 7d22 0a20 2020 2020 2020 206c 6162  le}".        lab
-000015b0: 656c 6c6f 633d 2274 220a 2020 2020 2020  elloc="t".      
-000015c0: 2020 7261 6e6b 6469 723d 227b 6f72 6965    rankdir="{orie
-000015d0: 6e74 6174 696f 6e7d 220a 0a20 2020 2020  ntation}"..     
-000015e0: 2020 207b 6e65 776c 696e 652e 6a6f 696e     {newline.join
-000015f0: 286e 6f64 6573 297d 0a0a 2020 2020 2020  (nodes)}..      
-00001600: 2020 7b6e 6577 6c69 6e65 2e6a 6f69 6e28    {newline.join(
-00001610: 6564 6765 7329 7d0a 0a20 2020 2020 2020  edges)}..       
-00001620: 2065 6467 6520 5b73 7479 6c65 3d69 6e76   edge [style=inv
-00001630: 6973 5d0a 0a20 2020 2020 2020 207b 6e65  is]..        {ne
-00001640: 776c 696e 652e 6a6f 696e 2867 7269 645f  wline.join(grid_
-00001650: 6564 6765 7329 7d0a 2020 2020 2020 2020  edges)}.        
-00001660: 7b63 6c61 7373 5f6c 6567 656e 645f 6772  {class_legend_gr
-00001670: 286c 6567 656e 6429 2069 6620 6c65 6765  (legend) if lege
-00001680: 6e64 2021 3d20 4e6f 6e65 2065 6c73 6520  nd != None else 
-00001690: 2727 7d0a 0a20 2020 207d 7d0a 2020 2020  ''}..    }}.    
-000016a0: 2727 270a 2020 2020 7265 7475 726e 2044  '''.    return D
-000016b0: 5472 6565 5669 7a43 6f6e 7628 646f 742c  TreeVizConv(dot,
-000016c0: 2073 6361 6c65 29                         scale)
+00000020: 2e75 7469 6c73 2069 6d70 6f72 7420 4454  .utils import DT
+00000030: 7265 6556 697a 5265 6e64 6572 0a69 6d70  reeVizRender.imp
+00000040: 6f72 7420 7465 6d70 6669 6c65 0a69 6d70  ort tempfile.imp
+00000050: 6f72 7420 6f73 0a66 726f 6d20 7661 6c69  ort os.from vali
+00000060: 6461 7469 6e67 5f6d 6f64 656c 732e 7374  dating_models.st
+00000070: 6174 7320 696d 706f 7274 2067 6574 5f64  ats import get_d
+00000080: 6563 6f72 6174 6f72 0a0a 7469 6d65 5f70  ecorator..time_p
+00000090: 6963 7475 7265 5f63 6f70 6f73 6974 696f  icture_copositio
+000000a0: 6e20 3d20 6765 745f 6465 636f 7261 746f  n = get_decorato
+000000b0: 7228 2770 6963 7475 7265 5f63 6f6d 706f  r('picture_compo
+000000c0: 7369 7469 6f6e 2729 0a0a 746d 7020 3d20  sition')..tmp = 
+000000d0: 7465 6d70 6669 6c65 2e67 6574 7465 6d70  tempfile.gettemp
+000000e0: 6469 7228 290a 0a63 6c61 7373 2044 5472  dir()..class DTr
+000000f0: 6565 5669 7a43 6f6e 7628 4454 7265 6556  eeVizConv(DTreeV
+00000100: 697a 5265 6e64 6572 293a 0a20 2020 2064  izRender):.    d
+00000110: 6566 205f 5f69 6e69 745f 5f28 7365 6c66  ef __init__(self
+00000120: 2c20 646f 742c 2073 6361 6c65 3d31 2e30  , dot, scale=1.0
+00000130: 293a 0a20 2020 2020 2020 2073 7570 6572  ):.        super
+00000140: 2829 2e5f 5f69 6e69 745f 5f28 646f 742c  ().__init__(dot,
+00000150: 2073 6361 6c65 290a 2020 2020 0a20 2020   scale).    .   
+00000160: 2040 7374 6174 6963 6d65 7468 6f64 0a20   @staticmethod. 
+00000170: 2020 2064 6566 2066 726f 6d5f 4454 7265     def from_DTre
+00000180: 6556 697a 2864 7472 6565 7669 7a29 3a0a  eViz(dtreeviz):.
+00000190: 2020 2020 2020 2020 7265 7475 726e 2044          return D
+000001a0: 5472 6565 5669 7a43 6f6e 7628 6474 7265  TreeVizConv(dtre
+000001b0: 6576 697a 2e64 6f74 2c20 6474 7265 6576  eviz.dot, dtreev
+000001c0: 697a 2e73 6361 6c65 290a 0a20 2020 2040  iz.scale)..    @
+000001d0: 7469 6d65 5f70 6963 7475 7265 5f63 6f70  time_picture_cop
+000001e0: 6f73 6974 696f 6e0a 2020 2020 6465 6620  osition.    def 
+000001f0: 7361 7665 2873 656c 662c 2066 696c 656e  save(self, filen
+00000200: 616d 652c 2074 7261 6e73 7061 7265 6e74  ame, transparent
+00000210: 3d54 7275 652c 2064 7069 3d31 3030 3029  =True, dpi=1000)
+00000220: 3a0a 0a20 2020 2020 2020 2064 6f74 5f69  :..        dot_i
+00000230: 6478 203d 2066 696c 656e 616d 652e 7269  dx = filename.ri
+00000240: 6e64 6578 2827 2e27 290a 2020 2020 2020  ndex('.').      
+00000250: 2020 7376 675f 6669 6c65 203d 2066 696c    svg_file = fil
+00000260: 656e 616d 655b 3a64 6f74 5f69 6478 5d20  ename[:dot_idx] 
+00000270: 2b20 272e 7376 6727 0a20 2020 2020 2020  + '.svg'.       
+00000280: 2073 7570 6572 2829 2e73 6176 6528 7376   super().save(sv
+00000290: 675f 6669 6c65 290a 2020 2020 2020 2020  g_file).        
+000002a0: 0a20 2020 2020 2020 2023 2041 6464 206d  .        # Add m
+000002b0: 6973 7369 6e67 2068 6561 6465 720a 2020  issing header.  
+000002c0: 2020 2020 2020 6d69 7373 696e 675f 6865        missing_he
+000002d0: 6164 6572 203d 2027 3c3f 786d 6c20 7665  ader = '<?xml ve
+000002e0: 7273 696f 6e3d 2231 2e30 2220 656e 636f  rsion="1.0" enco
+000002f0: 6469 6e67 3d22 7574 662d 3822 2073 7461  ding="utf-8" sta
+00000300: 6e64 616c 6f6e 653d 226e 6f22 3f3e 5c6e  ndalone="no"?>\n
+00000310: 3c21 444f 4354 5950 4520 7376 6720 5055  <!DOCTYPE svg PU
+00000320: 424c 4943 2022 2d2f 2f57 3343 2f2f 4454  BLIC "-//W3C//DT
+00000330: 4420 5356 4720 312e 312f 2f45 4e22 2022  D SVG 1.1//EN" "
+00000340: 6874 7470 3a2f 2f77 7777 2e77 332e 6f72  http://www.w3.or
+00000350: 672f 4772 6170 6869 6373 2f53 5647 2f31  g/Graphics/SVG/1
+00000360: 2e31 2f44 5444 2f73 7667 3131 2e64 7464  .1/DTD/svg11.dtd
+00000370: 223e 5c6e 270a 2020 2020 2020 2020 7769  ">\n'.        wi
+00000380: 7468 206f 7065 6e28 7376 675f 6669 6c65  th open(svg_file
+00000390: 2c20 2772 2729 2061 7320 6f72 6967 696e  , 'r') as origin
+000003a0: 616c 3a0a 2020 2020 2020 2020 2020 2020  al:.            
+000003b0: 7376 675f 636f 6e74 656e 7420 3d20 6f72  svg_content = or
+000003c0: 6967 696e 616c 2e72 6561 6428 290a 2020  iginal.read().  
+000003d0: 2020 2020 2020 0a20 2020 2020 2020 2069        .        i
+000003e0: 6620 6669 6c65 6e61 6d65 2e65 6e64 7377  f filename.endsw
+000003f0: 6974 6828 272e 7376 6727 293a 0a20 2020  ith('.svg'):.   
+00000400: 2020 2020 2020 2020 2077 6974 6820 6f70           with op
+00000410: 656e 2866 696c 656e 616d 652c 2027 7727  en(filename, 'w'
+00000420: 2920 6173 206e 6577 3a0a 2020 2020 2020  ) as new:.      
+00000430: 2020 2020 2020 2020 2020 6e65 772e 7772            new.wr
+00000440: 6974 6528 6d69 7373 696e 675f 6865 6164  ite(missing_head
+00000450: 6572 290a 2020 2020 2020 2020 2020 2020  er).            
+00000460: 2020 2020 6e65 772e 7772 6974 6528 7376      new.write(sv
+00000470: 675f 636f 6e74 656e 7429 0a20 2020 2020  g_content).     
+00000480: 2020 2065 6c73 653a 0a20 2020 2020 2020     else:.       
+00000490: 2020 2020 2069 6d70 6f72 7420 6361 6972       import cair
+000004a0: 6f73 7667 0a20 2020 2020 2020 2020 2020  osvg.           
+000004b0: 2069 6d70 6f72 7420 696f 0a20 2020 2020   import io.     
+000004c0: 2020 2020 2020 2066 726f 6d20 5049 4c20         from PIL 
+000004d0: 696d 706f 7274 2049 6d61 6765 0a20 2020  import Image.   
+000004e0: 2020 2020 2020 2020 206f 7574 7075 745f           output_
+000004f0: 706e 6720 3d20 696f 2e42 7974 6573 494f  png = io.BytesIO
+00000500: 2829 0a20 2020 2020 2020 2020 2020 2063  ().            c
+00000510: 6169 726f 7376 672e 7376 6732 706e 6728  airosvg.svg2png(
+00000520: 6279 7465 7374 7269 6e67 3d73 7667 5f63  bytestring=svg_c
+00000530: 6f6e 7465 6e74 2c20 7772 6974 655f 746f  ontent, write_to
+00000540: 3d6f 7574 7075 745f 706e 672c 2073 6361  =output_png, sca
+00000550: 6c65 3d64 7069 2f31 3030 290a 2020 2020  le=dpi/100).    
+00000560: 2020 2020 2020 2020 696d 203d 2049 6d61          im = Ima
+00000570: 6765 2e6f 7065 6e28 6f75 7470 7574 5f70  ge.open(output_p
+00000580: 6e67 290a 2020 2020 2020 2020 2020 2020  ng).            
+00000590: 6f75 7470 7574 5f70 6e67 2e63 6c6f 7365  output_png.close
+000005a0: 2829 0a0a 2020 2020 2020 2020 2020 2020  ()..            
+000005b0: 6966 2074 7261 6e73 7061 7265 6e74 3a0a  if transparent:.
+000005c0: 2020 2020 2020 2020 2020 2020 2020 2020                  
+000005d0: 696d 203d 2069 6d2e 636f 6e76 6572 7428  im = im.convert(
+000005e0: 2752 4742 4127 290a 2020 2020 2020 2020  'RGBA').        
+000005f0: 2020 2020 2020 2020 6461 7461 203d 206e          data = n
+00000600: 702e 6172 7261 7928 696d 290a 2020 2020  p.array(im).    
+00000610: 2020 2020 2020 2020 2020 2020 2370 7269              #pri
+00000620: 6e74 2864 6174 612e 7368 6170 6529 0a20  nt(data.shape). 
+00000630: 2020 2020 2020 2020 2020 2020 2020 2072                 r
+00000640: 6762 203d 2064 6174 615b 3a2c 3a2c 3a33  gb = data[:,:,:3
+00000650: 5d0a 2020 2020 2020 2020 2020 2020 2020  ].              
+00000660: 2020 7768 6974 6520 3d20 5b32 3535 2c32    white = [255,2
+00000670: 3535 2c32 3535 5d0a 2020 2020 2020 2020  55,255].        
+00000680: 2020 2020 2020 2020 7472 616e 7370 6172          transpar
+00000690: 656e 7420 3d20 5b32 3535 2c32 3535 2c32  ent = [255,255,2
+000006a0: 3535 2c30 5d0a 2020 2020 2020 2020 2020  55,0].          
+000006b0: 2020 2020 2020 6d61 736b 203d 206e 702e        mask = np.
+000006c0: 616c 6c28 7267 6220 3d3d 2077 6869 7465  all(rgb == white
+000006d0: 2c20 6178 6973 203d 202d 3129 0a20 2020  , axis = -1).   
+000006e0: 2020 2020 2020 2020 2020 2020 2023 7072               #pr
+000006f0: 696e 7428 6e70 2e73 756d 286d 6173 6b29  int(np.sum(mask)
+00000700: 290a 2020 2020 2020 2020 2020 2020 2020  ).              
+00000710: 2020 6461 7461 5b6d 6173 6b5d 203d 2074    data[mask] = t
+00000720: 7261 6e73 7061 7265 6e74 0a20 2020 2020  ransparent.     
+00000730: 2020 2020 2020 2020 2020 2069 6d20 3d20             im = 
+00000740: 496d 6167 652e 6672 6f6d 6172 7261 7928  Image.fromarray(
+00000750: 6461 7461 290a 0a20 2020 2020 2020 2020  data)..         
+00000760: 2020 2069 6d2e 7361 7665 2866 696c 656e     im.save(filen
+00000770: 616d 6529 0a0a 0a0a 6465 6620 6874 6d6c  ame)....def html
+00000780: 5f6c 6162 656c 286c 6162 656c 2c20 636f  _label(label, co
+00000790: 6c6f 722c 2073 697a 6529 3a0a 2020 2020  lor, size):.    
+000007a0: 2727 2752 6574 7572 6e73 2074 6865 2068  '''Returns the h
+000007b0: 746d 6c20 7265 7072 6573 656e 7461 7469  tml representati
+000007c0: 6f6e 2074 6f20 7368 6f77 2061 206c 6162  on to show a lab
+000007d0: 656c 2069 6e20 6120 6874 6d6c 2074 6162  el in a html tab
+000007e0: 6c65 2e0a 2020 2020 2727 270a 2020 2020  le..    '''.    
+000007f0: 7265 7475 726e 2066 273c 666f 6e74 2066  return f'<font f
+00000800: 6163 653d 2248 656c 7665 7469 6361 2220  ace="Helvetica" 
+00000810: 636f 6c6f 723d 227b 636f 6c6f 727d 2220  color="{color}" 
+00000820: 706f 696e 742d 7369 7a65 3d22 7b73 697a  point-size="{siz
+00000830: 657d 223e 3c69 3e7b 6c61 6265 6c7d 3c2f  e}"><i>{label}</
+00000840: 693e 3c2f 666f 6e74 3e27 0a0a 6465 6620  i></font>'..def 
+00000850: 6874 6d6c 5f69 6d61 6765 2868 746d 6c5f  html_image(html_
+00000860: 6c61 6265 6c2c 2069 6d67 5f70 6174 6829  label, img_path)
+00000870: 3a0a 2020 2020 2727 2752 6574 7572 6e73  :.    '''Returns
+00000880: 2074 6865 2068 746d 6c20 7265 7072 6573   the html repres
+00000890: 656e 7461 7469 6f6e 2074 6f20 7368 6f77  entation to show
+000008a0: 2074 6865 206c 6162 656c 2061 626f 7665   the label above
+000008b0: 2074 6865 2067 6976 656e 2069 6d61 6765   the given image
+000008c0: 2e0a 2020 2020 2727 270a 2020 2020 6874  ..    '''.    ht
+000008d0: 6d6c 5f6c 6162 656c 5f72 6f77 203d 2066  ml_label_row = f
+000008e0: 273c 7472 3e3c 7464 2043 454c 4c50 4144  '<tr><td CELLPAD
+000008f0: 4449 4e47 3d22 3022 2043 454c 4c53 5041  DING="0" CELLSPA
+00000900: 4349 4e47 3d22 3022 3e7b 6874 6d6c 5f6c  CING="0">{html_l
+00000910: 6162 656c 7d3c 2f74 643e 3c2f 7472 3e27  abel}</td></tr>'
+00000920: 0a20 2020 2072 6574 7572 6e20 6622 2222  .    return f"""
+00000930: 3c74 6162 6c65 2062 6f72 6465 723d 2230  <table border="0
+00000940: 2220 4345 4c4c 424f 5244 4552 3d22 3022  " CELLBORDER="0"
+00000950: 3e0a 2020 2020 2020 2020 7b68 746d 6c5f  >.        {html_
+00000960: 6c61 6265 6c5f 726f 777d 0a20 2020 2020  label_row}.     
+00000970: 2020 203c 7472 3e0a 2020 2020 2020 2020     <tr>.        
+00000980: 2020 2020 2020 2020 3c74 643e 3c69 6d67          <td><img
+00000990: 2073 7263 3d22 7b69 6d67 5f70 6174 687d   src="{img_path}
+000009a0: 222f 3e3c 2f74 643e 0a20 2020 2020 2020  "/></td>.       
+000009b0: 203c 2f74 723e 0a20 2020 2020 2020 203c   </tr>.        <
+000009c0: 2f74 6162 6c65 3e22 2222 0a0a 6465 6620  /table>"""..def 
+000009d0: 6874 6d6c 5f6e 6f64 655f 6c61 6265 6c28  html_node_label(
+000009e0: 6e6f 6465 2c20 636f 6c6f 722c 2073 697a  node, color, siz
+000009f0: 6529 3a0a 2020 2020 7265 7475 726e 2068  e):.    return h
+00000a00: 746d 6c5f 6c61 6265 6c28 6622 4e6f 6465  tml_label(f"Node
+00000a10: 207b 6e6f 6465 2e69 647d 222c 636f 6c6f   {node.id}",colo
+00000a20: 722c 2073 697a 6529 0a0a 6465 6620 6e6f  r, size)..def no
+00000a30: 6465 5f73 746d 7428 6e6f 6465 5f6e 616d  de_stmt(node_nam
+00000a40: 652c 2068 746d 6c5f 636f 6e74 656e 742c  e, html_content,
+00000a50: 2068 6967 686c 6967 6874 3a62 6f6f 6c2c   highlight:bool,
+00000a60: 2063 6f6c 6f72 7329 3a0a 2020 2020 6966   colors):.    if
+00000a70: 2068 6967 686c 6967 6874 3a0a 2020 2020   highlight:.    
+00000a80: 2020 2020 7265 7475 726e 2066 277b 6e6f      return f'{no
+00000a90: 6465 5f6e 616d 657d 205b 6d61 7267 696e  de_name} [margin
+00000aa0: 3d22 3022 2073 6861 7065 3d62 6f78 2070  ="0" shape=box p
+00000ab0: 656e 7769 6474 683d 222e 3522 2063 6f6c  enwidth=".5" col
+00000ac0: 6f72 3d22 7b63 6f6c 6f72 735b 2268 6967  or="{colors["hig
+00000ad0: 686c 6967 6874 225d 7d22 2073 7479 6c65  hlight"]}" style
+00000ae0: 3d22 6461 7368 6564 2220 6c61 6265 6c3d  ="dashed" label=
+00000af0: 3c7b 6874 6d6c 5f63 6f6e 7465 6e74 7d3e  <{html_content}>
+00000b00: 5d27 200a 2020 2020 656c 7365 3a20 0a20  ]' .    else: . 
+00000b10: 2020 2020 2020 2072 6574 7572 6e20 6627         return f'
+00000b20: 7b6e 6f64 655f 6e61 6d65 7d20 5b6d 6172  {node_name} [mar
+00000b30: 6769 6e3d 2230 2220 7368 6170 653d 626f  gin="0" shape=bo
+00000b40: 7820 7065 6e77 6964 7468 3d22 3022 2063  x penwidth="0" c
+00000b50: 6f6c 6f72 3d22 7b63 6f6c 6f72 735b 2274  olor="{colors["t
+00000b60: 6578 7422 5d7d 2220 6c61 6265 6c3d 3c7b  ext"]}" label=<{
+00000b70: 6874 6d6c 5f63 6f6e 7465 6e74 7d3e 5d27  html_content}>]'
+00000b80: 0a0a 6465 6620 636c 7573 7465 725f 6e6f  ..def cluster_no
+00000b90: 6465 7328 636c 7573 7465 725f 6e61 6d65  des(cluster_name
+00000ba0: 2c20 6c61 6265 6c2c 206e 6f64 6573 293a  , label, nodes):
+00000bb0: 0a20 2020 206e 6577 6c69 6e65 203d 2022  .    newline = "
+00000bc0: 5c6e 5c74 220a 2020 2020 7265 7475 726e  \n\t".    return
+00000bd0: 2066 2727 2773 7562 6772 6170 6820 636c   f'''subgraph cl
+00000be0: 7573 7465 725f 7b63 6c75 7374 6572 5f6e  uster_{cluster_n
+00000bf0: 616d 657d 207b 7b0a 2020 2020 2020 2020  ame} {{.        
+00000c00: 636f 6c6f 723d 6c69 6768 7467 7265 793b  color=lightgrey;
+00000c10: 0a20 2020 2020 2020 206c 6162 656c 3d22  .        label="
+00000c20: 7b6c 6162 656c 7d22 3b0a 2020 2020 2020  {label}";.      
+00000c30: 2020 7b6e 6577 6c69 6e65 2e6a 6f69 6e28    {newline.join(
+00000c40: 6e6f 6465 7329 7d0a 2020 2020 7d7d 0a20  nodes)}.    }}. 
+00000c50: 2020 2027 2727 0a0a 6465 6620 636c 6173     '''..def clas
+00000c60: 735f 6c65 6765 6e64 5f67 7228 7061 7468  s_legend_gr(path
+00000c70: 293a 0a20 2020 2069 6620 7061 7468 2021  ):.    if path !
+00000c80: 3d20 4e6f 6e65 3a0a 2020 2020 2020 2020  = None:.        
+00000c90: 7265 7475 726e 2066 2727 2773 7562 6772  return f'''subgr
+00000ca0: 6170 6820 636c 7573 7465 725f 6c65 6765  aph cluster_lege
+00000cb0: 6e64 207b 7b0a 2020 2020 2020 2020 2020  nd {{.          
+00000cc0: 2020 2020 2020 7374 796c 653d 696e 7669        style=invi
+00000cd0: 733b 0a20 2020 2020 2020 2020 2020 2020  s;.             
+00000ce0: 2020 206c 6567 656e 6420 5b70 656e 7769     legend [penwi
+00000cf0: 6474 683d 2230 2220 6d61 7267 696e 3d22  dth="0" margin="
+00000d00: 3022 2073 6861 7065 3d62 6f78 206d 6172  0" shape=box mar
+00000d10: 6769 6e3d 2230 2e30 3322 2077 6964 7468  gin="0.03" width
+00000d20: 3d2e 312c 2068 6569 6768 743d 2e31 206c  =.1, height=.1 l
+00000d30: 6162 656c 3d3c 0a20 2020 2020 2020 2020  abel=<.         
+00000d40: 2020 2020 2020 207b 6874 6d6c 5f69 6d61         {html_ima
+00000d50: 6765 2827 272c 2070 6174 6829 7d0a 2020  ge('', path)}.  
+00000d60: 2020 2020 2020 2020 2020 2020 2020 3e5d                >]
+00000d70: 0a20 2020 2020 2020 2020 2020 207d 7d0a  .            }}.
+00000d80: 2020 2020 2020 2020 2020 2020 2727 270a              '''.
+00000d90: 2020 2020 656c 7365 3a0a 2020 2020 2020      else:.      
+00000da0: 2020 7265 7475 726e 2027 270a 0a64 6566    return ''..def
+00000db0: 2067 6574 5f69 6d61 6765 5f70 6174 6828   get_image_path(
+00000dc0: 6964 656e 7469 6669 6572 3a20 7374 7229  identifier: str)
+00000dd0: 3a0a 2020 2020 7265 7475 726e 206f 732e  :.    return os.
+00000de0: 7061 7468 2e6a 6f69 6e28 746d 702c 6622  path.join(tmp,f"
+00000df0: 7b74 6d70 7d2f 7b69 6465 6e74 6966 6965  {tmp}/{identifie
+00000e00: 727d 5f7b 6f73 2e67 6574 7069 6428 297d  r}_{os.getpid()}
+00000e10: 2e73 7667 2229 0a0a 6465 6620 6772 6964  .svg")..def grid
+00000e20: 5f6c 6179 6f75 7428 7469 746c 652c 206e  _layout(title, n
+00000e30: 6f64 6573 2c20 6564 6765 732c 206c 6567  odes, edges, leg
+00000e40: 656e 642c 2063 6f6c 6f72 732c 2073 697a  end, colors, siz
+00000e50: 653d 4e6f 6e65 2c20 666f 6e74 6e61 6d65  e=None, fontname
+00000e60: 3d27 4865 6c76 6574 6963 6127 2c20 7363  ='Helvetica', sc
+00000e70: 616c 653d 312e 302c 206f 7269 656e 7461  ale=1.0, orienta
+00000e80: 7469 6f6e 203d 2027 4c52 2729 3a20 2320  tion = 'LR'): # 
+00000e90: 4c52 206f 7220 5444 0a20 2020 206e 6f64  LR or TD.    nod
+00000ea0: 655f 6e61 6d65 7320 3d20 5b6e 6f64 652e  e_names = [node.
+00000eb0: 7370 6c69 7428 2220 222c 3129 5b30 5d20  split(" ",1)[0] 
+00000ec0: 6966 206e 6f64 652e 7370 6c69 7428 2220  if node.split(" 
+00000ed0: 222c 3129 5b30 5d20 213d 2027 7375 6267  ",1)[0] != 'subg
+00000ee0: 7261 7068 2720 656c 7365 206e 6f64 652e  raph' else node.
+00000ef0: 7370 6c69 7428 2220 222c 3229 5b31 5d20  split(" ",2)[1] 
+00000f00: 666f 7220 6e6f 6465 2069 6e20 6e6f 6465  for node in node
+00000f10: 735d 0a20 2020 2069 6620 7369 7a65 203d  s].    if size =
+00000f20: 3d20 4e6f 6e65 3a0a 2020 2020 2020 2020  = None:.        
+00000f30: 6772 6964 5f73 697a 6520 3d20 696e 7428  grid_size = int(
+00000f40: 6e70 2e63 6569 6c28 6e70 2e73 7172 7428  np.ceil(np.sqrt(
+00000f50: 6c65 6e28 6e6f 6465 5f6e 616d 6573 2929  len(node_names))
+00000f60: 2929 0a20 2020 2020 2020 2073 697a 6520  )).        size 
+00000f70: 3d20 2867 7269 645f 7369 7a65 2c67 7269  = (grid_size,gri
+00000f80: 645f 7369 7a65 290a 0a20 2020 2073 697a  d_size)..    siz
+00000f90: 6520 3d20 6c69 7374 2873 697a 6529 0a20  e = list(size). 
+00000fa0: 2020 206e 756d 5f6e 6f64 6573 203d 2073     num_nodes = s
+00000fb0: 697a 655b 305d 202a 2073 697a 655b 315d  ize[0] * size[1]
+00000fc0: 0a0a 2020 2020 6269 675f 696e 6465 7820  ..    big_index 
+00000fd0: 3d20 3020 6966 2073 697a 655b 305d 203e  = 0 if size[0] >
+00000fe0: 2073 697a 655b 315d 2065 6c73 6520 310a   size[1] else 1.
+00000ff0: 0a20 2020 2077 6869 6c65 206e 756d 5f6e  .    while num_n
+00001000: 6f64 6573 203e 3d20 6c65 6e28 6e6f 6465  odes >= len(node
+00001010: 7329 202b 2073 697a 655b 6269 675f 696e  s) + size[big_in
+00001020: 6465 785d 3a0a 2020 2020 2020 2020 7369  dex]:.        si
+00001030: 7a65 5b62 6967 5f69 6e64 6578 5d20 3d20  ze[big_index] = 
+00001040: 7369 7a65 5b62 6967 5f69 6e64 6578 5d20  size[big_index] 
+00001050: 2d20 310a 2020 2020 2020 2020 6e75 6d5f  - 1.        num_
+00001060: 6e6f 6465 7320 3d20 7369 7a65 5b30 5d20  nodes = size[0] 
+00001070: 2a20 7369 7a65 5b31 5d0a 2020 2020 0a20  * size[1].    . 
+00001080: 2020 2077 6869 6c65 206e 756d 5f6e 6f64     while num_nod
+00001090: 6573 203e 3d20 6c65 6e28 6e6f 6465 7329  es >= len(nodes)
+000010a0: 202b 2073 697a 655b 2862 6967 5f69 6e64   + size[(big_ind
+000010b0: 6578 202b 2031 2920 2520 325d 3a0a 2020  ex + 1) % 2]:.  
+000010c0: 2020 2020 2020 7369 7a65 5b28 6269 675f        size[(big_
+000010d0: 696e 6465 7820 2b20 3129 2025 2032 5d20  index + 1) % 2] 
+000010e0: 3d20 7369 7a65 5b28 6269 675f 696e 6465  = size[(big_inde
+000010f0: 7820 2b20 3129 2025 2032 5d20 2d20 310a  x + 1) % 2] - 1.
+00001100: 2020 2020 2020 2020 6e75 6d5f 6e6f 6465          num_node
+00001110: 7320 3d20 7369 7a65 5b30 5d20 2a20 7369  s = size[0] * si
+00001120: 7a65 5b31 5d0a 0a20 2020 2023 2046 696c  ze[1]..    # Fil
+00001130: 6c20 6772 6964 2077 6974 6820 7370 6163  l grid with spac
+00001140: 6568 6f6c 6465 7220 6e6f 6465 730a 2020  eholder nodes.  
+00001150: 2020 6e75 6d5f 7370 6163 6568 6f6c 6465    num_spaceholde
+00001160: 7273 203d 2030 0a20 2020 2077 6869 6c65  rs = 0.    while
+00001170: 206c 656e 286e 6f64 6573 2920 3c20 6e75   len(nodes) < nu
+00001180: 6d5f 6e6f 6465 733a 0a20 2020 2020 2020  m_nodes:.       
+00001190: 206e 756d 5f73 7061 6365 686f 6c64 6572   num_spaceholder
+000011a0: 7320 2b3d 2031 0a20 2020 2020 2020 206e  s += 1.        n
+000011b0: 6f64 6573 2e61 7070 656e 6428 6e6f 6465  odes.append(node
+000011c0: 5f73 746d 7428 6627 7370 6163 6568 6f6c  _stmt(f'spacehol
+000011d0: 6465 727b 6e75 6d5f 7370 6163 6568 6f6c  der{num_spacehol
+000011e0: 6465 7273 7d27 2c20 2727 2c20 4661 6c73  ders}', '', Fals
+000011f0: 652c 2063 6f6c 6f72 7329 290a 2020 2020  e, colors)).    
+00001200: 2020 2020 6e6f 6465 5f6e 616d 6573 2e61      node_names.a
+00001210: 7070 656e 6428 6627 7370 6163 6568 6f6c  ppend(f'spacehol
+00001220: 6465 727b 6e75 6d5f 7370 6163 6568 6f6c  der{num_spacehol
+00001230: 6465 7273 7d27 290a 0a20 2020 206e 6f64  ders}')..    nod
+00001240: 655f 6e61 6d65 7320 3d20 6e70 2e61 7272  e_names = np.arr
+00001250: 6179 286e 6f64 655f 6e61 6d65 7329 2e72  ay(node_names).r
+00001260: 6573 6861 7065 2828 7369 7a65 5b30 5d2c  eshape((size[0],
+00001270: 7369 7a65 5b31 5d29 290a 2020 2020 2320  size[1])).    # 
+00001280: 4372 6561 7465 2067 7269 6420 7374 7275  Create grid stru
+00001290: 6374 7572 650a 2020 2020 6772 6964 5f65  cture.    grid_e
+000012a0: 6467 6573 203d 205b 5d0a 2020 2020 666f  dges = [].    fo
+000012b0: 7220 6920 696e 2072 616e 6765 2873 697a  r i in range(siz
+000012c0: 655b 305d 293a 200a 2020 2020 2020 2020  e[0]): .        
+000012d0: 2320 486f 7269 7a6f 6e74 616c 2043 6f6e  # Horizontal Con
+000012e0: 6e65 6374 696f 6e73 0a20 2020 2020 2020  nections.       
+000012f0: 2076 6563 203d 206e 6f64 655f 6e61 6d65   vec = node_name
+00001300: 735b 692c 3a5d 0a20 2020 2020 2020 2076  s[i,:].        v
+00001310: 6563 203d 206c 6973 7428 7665 632e 7265  ec = list(vec.re
+00001320: 7368 6170 6528 2d31 2c29 290a 2020 2020  shape(-1,)).    
+00001330: 2020 2020 6966 206c 656e 2876 6563 2920      if len(vec) 
+00001340: 3e20 313a 0a20 2020 2020 2020 2020 2020  > 1:.           
+00001350: 2067 7269 645f 6564 6765 732e 6170 7065   grid_edges.appe
+00001360: 6e64 2827 7261 6e6b 3d73 616d 6520 7b27  nd('rank=same {'
+00001370: 202b 2027 202d 2d20 272e 6a6f 696e 2876   + ' -- '.join(v
+00001380: 6563 2920 2b20 277d 2729 0a20 2020 200a  ec) + '}').    .
+00001390: 2020 2020 666f 7220 6a20 696e 2072 616e      for j in ran
+000013a0: 6765 2873 697a 655b 315d 293a 0a20 2020  ge(size[1]):.   
+000013b0: 2020 2020 2023 2056 6572 7469 6361 6c20       # Vertical 
+000013c0: 436f 6e6e 6563 7469 6f6e 730a 2020 2020  Connections.    
+000013d0: 2020 2020 7665 6320 3d20 6e6f 6465 5f6e      vec = node_n
+000013e0: 616d 6573 5b3a 2c6a 5d0a 2020 2020 2020  ames[:,j].      
+000013f0: 2020 7665 6320 3d20 6c69 7374 2876 6563    vec = list(vec
+00001400: 2e72 6573 6861 7065 282d 312c 2929 0a20  .reshape(-1,)). 
+00001410: 2020 2020 2020 2069 6620 6c65 6e28 7665         if len(ve
+00001420: 6329 203e 2031 3a0a 2020 2020 2020 2020  c) > 1:.        
+00001430: 2020 2020 6772 6964 5f65 6467 6573 2e61      grid_edges.a
+00001440: 7070 656e 6428 2720 2d2d 2027 2e6a 6f69  ppend(' -- '.joi
+00001450: 6e28 7665 6329 290a 2020 2020 2020 2020  n(vec)).        
+00001460: 0a20 2020 2020 2020 2069 6620 6f72 6965  .        if orie
+00001470: 6e74 6174 696f 6e20 3d3d 2027 4c52 2720  ntation == 'LR' 
+00001480: 616e 6420 6a20 3d3d 2030 2061 6e64 206c  and j == 0 and l
+00001490: 6567 656e 6420 213d 204e 6f6e 653a 0a20  egend != None:. 
+000014a0: 2020 2020 2020 2020 2020 2067 7269 645f             grid_
+000014b0: 6564 6765 732e 6170 7065 6e64 2827 202d  edges.append(' -
+000014c0: 2d20 6c65 6765 6e64 2729 0a0a 0a20 2020  - legend')...   
+000014d0: 206e 6577 6c69 6e65 203d 2022 5c6e 5c74   newline = "\n\t
+000014e0: 220a 2020 2020 646f 7420 3d20 6627 2727  ".    dot = f'''
+000014f0: 0a20 2020 2067 7261 7068 2047 207b 7b0a  .    graph G {{.
+00001500: 2020 2020 2020 2020 7370 6c69 6e65 733d          splines=
+00001510: 6c69 6e65 3b0a 2020 2020 2020 2020 666f  line;.        fo
+00001520: 6e74 6e61 6d65 3d22 7b66 6f6e 746e 616d  ntname="{fontnam
+00001530: 657d 220a 2020 2020 2020 2020 6e6f 6465  e}".        node
+00001540: 205b 666f 6e74 6e61 6d65 3d22 7b66 6f6e   [fontname="{fon
+00001550: 746e 616d 657d 225d 0a20 2020 2020 2020  tname}"].       
+00001560: 2065 6467 6520 5b66 6f6e 746e 616d 653d   edge [fontname=
+00001570: 227b 666f 6e74 6e61 6d65 7d22 5d0a 2020  "{fontname}"].  
+00001580: 2020 2020 2020 6c61 796f 7574 3d64 6f74        layout=dot
+00001590: 0a20 2020 2020 2020 206c 6162 656c 3d22  .        label="
+000015a0: 7b74 6974 6c65 7d22 0a20 2020 2020 2020  {title}".       
+000015b0: 206c 6162 656c 6c6f 633d 2274 220a 2020   labelloc="t".  
+000015c0: 2020 2020 2020 7261 6e6b 6469 723d 227b        rankdir="{
+000015d0: 6f72 6965 6e74 6174 696f 6e7d 220a 0a20  orientation}".. 
+000015e0: 2020 2020 2020 207b 6e65 776c 696e 652e         {newline.
+000015f0: 6a6f 696e 286e 6f64 6573 297d 0a0a 2020  join(nodes)}..  
+00001600: 2020 2020 2020 7b6e 6577 6c69 6e65 2e6a        {newline.j
+00001610: 6f69 6e28 6564 6765 7329 7d0a 0a20 2020  oin(edges)}..   
+00001620: 2020 2020 2065 6467 6520 5b73 7479 6c65       edge [style
+00001630: 3d69 6e76 6973 5d0a 0a20 2020 2020 2020  =invis]..       
+00001640: 207b 6e65 776c 696e 652e 6a6f 696e 2867   {newline.join(g
+00001650: 7269 645f 6564 6765 7329 7d0a 2020 2020  rid_edges)}.    
+00001660: 2020 2020 7b63 6c61 7373 5f6c 6567 656e      {class_legen
+00001670: 645f 6772 286c 6567 656e 6429 2069 6620  d_gr(legend) if 
+00001680: 6c65 6765 6e64 2069 7320 6e6f 7420 4e6f  legend is not No
+00001690: 6e65 2065 6c73 6520 2727 7d0a 0a20 2020  ne else ''}..   
+000016a0: 207d 7d0a 2020 2020 2727 270a 2020 2020   }}.    '''.    
+000016b0: 7265 7475 726e 2044 5472 6565 5669 7a43  return DTreeVizC
+000016c0: 6f6e 7628 646f 742c 2073 6361 6c65 290a  onv(dot, scale).
```

### Comparing `validating_models-0.9.4/validating_models/visualizations/regression.py` & `validating_models-0.9.5/validating_models/visualizations/regression.py`

 * *Files identical despite different names*

### Comparing `validating_models-0.9.4/validating_models.egg-info/PKG-INFO` & `validating_models-0.9.5/validating_models.egg-info/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 Metadata-Version: 2.1
 Name: validating-models
-Version: 0.9.4
+Version: 0.9.5
 Summary: Supporting Explainable AI on Semantic Constraint Validation
 Home-page: https://github.com/JulianLoewe/Validating_Models
-Download-URL: https://github.com/JulianLoewe/Validating_Models/archive/refs/tags/v0.9.4.tar.gz
+Download-URL: https://github.com/JulianLoewe/Validating_Models/archive/refs/tags/v0.9.5.tar.gz
 Author: Julian Gercke
 License: GNU/GPLv3
 Classifier: Development Status :: 4 - Beta
 Classifier: Programming Language :: Python
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3 :: Only
 Classifier: Programming Language :: Python :: 3.8
```

### Comparing `validating_models-0.9.4/validating_models.egg-info/SOURCES.txt` & `validating_models-0.9.5/validating_models.egg-info/SOURCES.txt`

 * *Files identical despite different names*

