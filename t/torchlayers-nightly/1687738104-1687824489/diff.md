# Comparing `tmp/torchlayers-nightly-1687738104.tar.gz` & `tmp/torchlayers-nightly-1687824489.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/torchlayers-nightly-1687738104.tar", last modified: Mon Jun 26 00:08:30 2023, max compression
+gzip compressed data, was "dist/torchlayers-nightly-1687824489.tar", last modified: Tue Jun 27 00:08:14 2023, max compression
```

## Comparing `torchlayers-nightly-1687738104.tar` & `torchlayers-nightly-1687824489.tar`

### file list

```diff
@@ -1,42 +1,42 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 00:08:30.000000 torchlayers-nightly-1687738104/
--rw-r--r--   0 runner    (1001) docker     (123)    17559 2023-06-26 00:08:30.000000 torchlayers-nightly-1687738104/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13812 2023-06-26 00:08:24.000000 torchlayers-nightly-1687738104/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-26 00:08:30.000000 torchlayers-nightly-1687738104/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     1882 2023-06-26 00:08:24.000000 torchlayers-nightly-1687738104/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 00:08:30.000000 torchlayers-nightly-1687738104/tests/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-26 00:08:24.000000 torchlayers-nightly-1687738104/tests/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      358 2023-06-26 00:08:24.000000 torchlayers-nightly-1687738104/tests/activations_test.py
--rw-r--r--   0 runner    (1001) docker     (123)      146 2023-06-26 00:08:24.000000 torchlayers-nightly-1687738104/tests/attributes_test.py
--rw-r--r--   0 runner    (1001) docker     (123)     7058 2023-06-26 00:08:24.000000 torchlayers-nightly-1687738104/tests/convolution_test.py
--rw-r--r--   0 runner    (1001) docker     (123)     1883 2023-06-26 00:08:24.000000 torchlayers-nightly-1687738104/tests/general_test.py
--rw-r--r--   0 runner    (1001) docker     (123)      784 2023-06-26 00:08:24.000000 torchlayers-nightly-1687738104/tests/jit_test.py
--rw-r--r--   0 runner    (1001) docker     (123)      228 2023-06-26 00:08:24.000000 torchlayers-nightly-1687738104/tests/linear_test.py
--rw-r--r--   0 runner    (1001) docker     (123)      138 2023-06-26 00:08:24.000000 torchlayers-nightly-1687738104/tests/normalization_test.py
--rw-r--r--   0 runner    (1001) docker     (123)      230 2023-06-26 00:08:24.000000 torchlayers-nightly-1687738104/tests/padding_test.py
--rw-r--r--   0 runner    (1001) docker     (123)     1174 2023-06-26 00:08:24.000000 torchlayers-nightly-1687738104/tests/pickle_test.py
--rw-r--r--   0 runner    (1001) docker     (123)     4444 2023-06-26 00:08:24.000000 torchlayers-nightly-1687738104/tests/preprocessing_test.py
--rw-r--r--   0 runner    (1001) docker     (123)      468 2023-06-26 00:08:24.000000 torchlayers-nightly-1687738104/tests/recurrent_test.py
--rw-r--r--   0 runner    (1001) docker     (123)     1646 2023-06-26 00:08:24.000000 torchlayers-nightly-1687738104/tests/regularization_test.py
--rw-r--r--   0 runner    (1001) docker     (123)     2128 2023-06-26 00:08:24.000000 torchlayers-nightly-1687738104/tests/torchlayers_test.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 00:08:30.000000 torchlayers-nightly-1687738104/torchlayers/
--rw-r--r--   0 runner    (1001) docker     (123)    24781 2023-06-26 00:08:24.000000 torchlayers-nightly-1687738104/torchlayers/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 00:08:30.000000 torchlayers-nightly-1687738104/torchlayers/_dev_utils/
--rw-r--r--   0 runner    (1001) docker     (123)       20 2023-06-26 00:08:24.000000 torchlayers-nightly-1687738104/torchlayers/_dev_utils/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2647 2023-06-26 00:08:24.000000 torchlayers-nightly-1687738104/torchlayers/_dev_utils/helpers.py
--rw-r--r--   0 runner    (1001) docker     (123)    11858 2023-06-26 00:08:24.000000 torchlayers-nightly-1687738104/torchlayers/_dev_utils/infer.py
--rw-r--r--   0 runner    (1001) docker     (123)       30 2023-06-26 00:08:24.000000 torchlayers-nightly-1687738104/torchlayers/_name.py
--rw-r--r--   0 runner    (1001) docker     (123)       27 2023-06-26 00:08:24.000000 torchlayers-nightly-1687738104/torchlayers/_version.py
--rw-r--r--   0 runner    (1001) docker     (123)     2914 2023-06-26 00:08:24.000000 torchlayers-nightly-1687738104/torchlayers/activations.py
--rw-r--r--   0 runner    (1001) docker     (123)    36698 2023-06-26 00:08:24.000000 torchlayers-nightly-1687738104/torchlayers/convolution.py
--rw-r--r--   0 runner    (1001) docker     (123)     4477 2023-06-26 00:08:24.000000 torchlayers-nightly-1687738104/torchlayers/module.py
--rw-r--r--   0 runner    (1001) docker     (123)     4878 2023-06-26 00:08:24.000000 torchlayers-nightly-1687738104/torchlayers/normalization.py
--rw-r--r--   0 runner    (1001) docker     (123)     8375 2023-06-26 00:08:24.000000 torchlayers-nightly-1687738104/torchlayers/pooling.py
--rw-r--r--   0 runner    (1001) docker     (123)    13825 2023-06-26 00:08:24.000000 torchlayers-nightly-1687738104/torchlayers/preprocessing.py
--rw-r--r--   0 runner    (1001) docker     (123)     7605 2023-06-26 00:08:24.000000 torchlayers-nightly-1687738104/torchlayers/regularization.py
--rw-r--r--   0 runner    (1001) docker     (123)     5321 2023-06-26 00:08:24.000000 torchlayers-nightly-1687738104/torchlayers/upsample.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-26 00:08:30.000000 torchlayers-nightly-1687738104/torchlayers_nightly.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    17559 2023-06-26 00:08:30.000000 torchlayers-nightly-1687738104/torchlayers_nightly.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      947 2023-06-26 00:08:30.000000 torchlayers-nightly-1687738104/torchlayers_nightly.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-26 00:08:30.000000 torchlayers-nightly-1687738104/torchlayers_nightly.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       13 2023-06-26 00:08:30.000000 torchlayers-nightly-1687738104/torchlayers_nightly.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       18 2023-06-26 00:08:30.000000 torchlayers-nightly-1687738104/torchlayers_nightly.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 00:08:14.000000 torchlayers-nightly-1687824489/
+-rw-r--r--   0 runner    (1001) docker     (123)    17559 2023-06-27 00:08:14.000000 torchlayers-nightly-1687824489/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13812 2023-06-27 00:08:09.000000 torchlayers-nightly-1687824489/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-27 00:08:14.000000 torchlayers-nightly-1687824489/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     1882 2023-06-27 00:08:09.000000 torchlayers-nightly-1687824489/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 00:08:14.000000 torchlayers-nightly-1687824489/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 00:08:09.000000 torchlayers-nightly-1687824489/tests/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      358 2023-06-27 00:08:09.000000 torchlayers-nightly-1687824489/tests/activations_test.py
+-rw-r--r--   0 runner    (1001) docker     (123)      146 2023-06-27 00:08:09.000000 torchlayers-nightly-1687824489/tests/attributes_test.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7058 2023-06-27 00:08:09.000000 torchlayers-nightly-1687824489/tests/convolution_test.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1883 2023-06-27 00:08:09.000000 torchlayers-nightly-1687824489/tests/general_test.py
+-rw-r--r--   0 runner    (1001) docker     (123)      784 2023-06-27 00:08:09.000000 torchlayers-nightly-1687824489/tests/jit_test.py
+-rw-r--r--   0 runner    (1001) docker     (123)      228 2023-06-27 00:08:09.000000 torchlayers-nightly-1687824489/tests/linear_test.py
+-rw-r--r--   0 runner    (1001) docker     (123)      138 2023-06-27 00:08:09.000000 torchlayers-nightly-1687824489/tests/normalization_test.py
+-rw-r--r--   0 runner    (1001) docker     (123)      230 2023-06-27 00:08:09.000000 torchlayers-nightly-1687824489/tests/padding_test.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1174 2023-06-27 00:08:09.000000 torchlayers-nightly-1687824489/tests/pickle_test.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4444 2023-06-27 00:08:09.000000 torchlayers-nightly-1687824489/tests/preprocessing_test.py
+-rw-r--r--   0 runner    (1001) docker     (123)      468 2023-06-27 00:08:09.000000 torchlayers-nightly-1687824489/tests/recurrent_test.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1646 2023-06-27 00:08:09.000000 torchlayers-nightly-1687824489/tests/regularization_test.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2128 2023-06-27 00:08:09.000000 torchlayers-nightly-1687824489/tests/torchlayers_test.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 00:08:14.000000 torchlayers-nightly-1687824489/torchlayers/
+-rw-r--r--   0 runner    (1001) docker     (123)    24781 2023-06-27 00:08:09.000000 torchlayers-nightly-1687824489/torchlayers/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 00:08:14.000000 torchlayers-nightly-1687824489/torchlayers/_dev_utils/
+-rw-r--r--   0 runner    (1001) docker     (123)       20 2023-06-27 00:08:09.000000 torchlayers-nightly-1687824489/torchlayers/_dev_utils/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2647 2023-06-27 00:08:09.000000 torchlayers-nightly-1687824489/torchlayers/_dev_utils/helpers.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11858 2023-06-27 00:08:09.000000 torchlayers-nightly-1687824489/torchlayers/_dev_utils/infer.py
+-rw-r--r--   0 runner    (1001) docker     (123)       30 2023-06-27 00:08:09.000000 torchlayers-nightly-1687824489/torchlayers/_name.py
+-rw-r--r--   0 runner    (1001) docker     (123)       27 2023-06-27 00:08:09.000000 torchlayers-nightly-1687824489/torchlayers/_version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2914 2023-06-27 00:08:09.000000 torchlayers-nightly-1687824489/torchlayers/activations.py
+-rw-r--r--   0 runner    (1001) docker     (123)    36698 2023-06-27 00:08:09.000000 torchlayers-nightly-1687824489/torchlayers/convolution.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4477 2023-06-27 00:08:09.000000 torchlayers-nightly-1687824489/torchlayers/module.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4878 2023-06-27 00:08:09.000000 torchlayers-nightly-1687824489/torchlayers/normalization.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8375 2023-06-27 00:08:09.000000 torchlayers-nightly-1687824489/torchlayers/pooling.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13825 2023-06-27 00:08:09.000000 torchlayers-nightly-1687824489/torchlayers/preprocessing.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7605 2023-06-27 00:08:09.000000 torchlayers-nightly-1687824489/torchlayers/regularization.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5321 2023-06-27 00:08:09.000000 torchlayers-nightly-1687824489/torchlayers/upsample.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 00:08:14.000000 torchlayers-nightly-1687824489/torchlayers_nightly.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    17559 2023-06-27 00:08:14.000000 torchlayers-nightly-1687824489/torchlayers_nightly.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      947 2023-06-27 00:08:14.000000 torchlayers-nightly-1687824489/torchlayers_nightly.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-27 00:08:14.000000 torchlayers-nightly-1687824489/torchlayers_nightly.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       13 2023-06-27 00:08:14.000000 torchlayers-nightly-1687824489/torchlayers_nightly.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       18 2023-06-27 00:08:14.000000 torchlayers-nightly-1687824489/torchlayers_nightly.egg-info/top_level.txt
```

### Comparing `torchlayers-nightly-1687738104/PKG-INFO` & `torchlayers-nightly-1687824489/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: torchlayers-nightly
-Version: 1687738104
+Version: 1687824489
 Summary: Input shape inference and SOTA custom layers for PyTorch.
 Home-page: https://github.com/pypa/torchlayers
 Author: Szymon Maszke
 Author-email: szymon.maszke@protonmail.com
 License: MIT
 Project-URL: Website, https://szymonmaszke.github.io/torchlayers
 Project-URL: Documentation, https://szymonmaszke.github.io/torchlayers/#torchlayers
```

### Comparing `torchlayers-nightly-1687738104/README.md` & `torchlayers-nightly-1687824489/README.md`

 * *Files identical despite different names*

### Comparing `torchlayers-nightly-1687738104/setup.py` & `torchlayers-nightly-1687824489/setup.py`

 * *Files identical despite different names*

### Comparing `torchlayers-nightly-1687738104/tests/convolution_test.py` & `torchlayers-nightly-1687824489/tests/convolution_test.py`

 * *Files identical despite different names*

### Comparing `torchlayers-nightly-1687738104/tests/general_test.py` & `torchlayers-nightly-1687824489/tests/general_test.py`

 * *Files identical despite different names*

### Comparing `torchlayers-nightly-1687738104/tests/jit_test.py` & `torchlayers-nightly-1687824489/tests/jit_test.py`

 * *Files identical despite different names*

### Comparing `torchlayers-nightly-1687738104/tests/pickle_test.py` & `torchlayers-nightly-1687824489/tests/pickle_test.py`

 * *Files identical despite different names*

### Comparing `torchlayers-nightly-1687738104/tests/preprocessing_test.py` & `torchlayers-nightly-1687824489/tests/preprocessing_test.py`

 * *Files identical despite different names*

### Comparing `torchlayers-nightly-1687738104/tests/regularization_test.py` & `torchlayers-nightly-1687824489/tests/regularization_test.py`

 * *Files identical despite different names*

### Comparing `torchlayers-nightly-1687738104/tests/torchlayers_test.py` & `torchlayers-nightly-1687824489/tests/torchlayers_test.py`

 * *Files identical despite different names*

### Comparing `torchlayers-nightly-1687738104/torchlayers/__init__.py` & `torchlayers-nightly-1687824489/torchlayers/__init__.py`

 * *Files identical despite different names*

### Comparing `torchlayers-nightly-1687738104/torchlayers/_dev_utils/helpers.py` & `torchlayers-nightly-1687824489/torchlayers/_dev_utils/helpers.py`

 * *Files identical despite different names*

### Comparing `torchlayers-nightly-1687738104/torchlayers/_dev_utils/infer.py` & `torchlayers-nightly-1687824489/torchlayers/_dev_utils/infer.py`

 * *Files identical despite different names*

### Comparing `torchlayers-nightly-1687738104/torchlayers/activations.py` & `torchlayers-nightly-1687824489/torchlayers/activations.py`

 * *Files identical despite different names*

### Comparing `torchlayers-nightly-1687738104/torchlayers/convolution.py` & `torchlayers-nightly-1687824489/torchlayers/convolution.py`

 * *Files identical despite different names*

### Comparing `torchlayers-nightly-1687738104/torchlayers/module.py` & `torchlayers-nightly-1687824489/torchlayers/module.py`

 * *Files identical despite different names*

### Comparing `torchlayers-nightly-1687738104/torchlayers/normalization.py` & `torchlayers-nightly-1687824489/torchlayers/normalization.py`

 * *Files identical despite different names*

### Comparing `torchlayers-nightly-1687738104/torchlayers/pooling.py` & `torchlayers-nightly-1687824489/torchlayers/pooling.py`

 * *Files identical despite different names*

### Comparing `torchlayers-nightly-1687738104/torchlayers/preprocessing.py` & `torchlayers-nightly-1687824489/torchlayers/preprocessing.py`

 * *Files identical despite different names*

### Comparing `torchlayers-nightly-1687738104/torchlayers/regularization.py` & `torchlayers-nightly-1687824489/torchlayers/regularization.py`

 * *Files identical despite different names*

### Comparing `torchlayers-nightly-1687738104/torchlayers/upsample.py` & `torchlayers-nightly-1687824489/torchlayers/upsample.py`

 * *Files identical despite different names*

### Comparing `torchlayers-nightly-1687738104/torchlayers_nightly.egg-info/PKG-INFO` & `torchlayers-nightly-1687824489/torchlayers_nightly.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: torchlayers-nightly
-Version: 1687738104
+Version: 1687824489
 Summary: Input shape inference and SOTA custom layers for PyTorch.
 Home-page: https://github.com/pypa/torchlayers
 Author: Szymon Maszke
 Author-email: szymon.maszke@protonmail.com
 License: MIT
 Project-URL: Website, https://szymonmaszke.github.io/torchlayers
 Project-URL: Documentation, https://szymonmaszke.github.io/torchlayers/#torchlayers
```

### Comparing `torchlayers-nightly-1687738104/torchlayers_nightly.egg-info/SOURCES.txt` & `torchlayers-nightly-1687824489/torchlayers_nightly.egg-info/SOURCES.txt`

 * *Files identical despite different names*

