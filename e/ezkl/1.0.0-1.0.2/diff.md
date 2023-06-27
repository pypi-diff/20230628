# Comparing `tmp/ezkl-1.0.0.tar.gz` & `tmp/ezkl-1.0.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "ezkl-1.0.0.tar", max compression
+gzip compressed data, was "ezkl-1.0.2.tar", max compression
```

## Comparing `ezkl-1.0.0.tar` & `ezkl-1.0.2.tar`

### file list

```diff
@@ -1,6 +1,6 @@
--rw-r--r--   0        0        0    11357 2023-06-22 17:32:38.768713 ezkl-1.0.0/LICENSE
--rw-r--r--   0        0        0     2692 2023-06-22 17:32:38.768713 ezkl-1.0.0/README.md
--rw-r--r--   0        0        0      319 2023-06-22 17:32:38.768713 ezkl-1.0.0/ezkl/__init__.py
--rw-r--r--   0        0        0     4627 2023-06-22 17:32:38.768713 ezkl-1.0.0/ezkl/export.py
--rw-r--r--   0        0        0      950 2023-06-22 17:32:49.720804 ezkl-1.0.0/pyproject.toml
--rw-r--r--   0        0        0     3544 1970-01-01 00:00:00.000000 ezkl-1.0.0/PKG-INFO
+-rw-r--r--   0        0        0    11357 2023-06-27 22:30:16.144992 ezkl-1.0.2/LICENSE
+-rw-r--r--   0        0        0     2692 2023-06-27 22:30:16.144992 ezkl-1.0.2/README.md
+-rw-r--r--   0        0        0      319 2023-06-27 22:30:16.144992 ezkl-1.0.2/ezkl/__init__.py
+-rw-r--r--   0        0        0     4627 2023-06-27 22:30:16.144992 ezkl-1.0.2/ezkl/export.py
+-rw-r--r--   0        0        0      968 2023-06-27 22:30:30.569037 ezkl-1.0.2/pyproject.toml
+-rw-r--r--   0        0        0     3598 1970-01-01 00:00:00.000000 ezkl-1.0.2/PKG-INFO
```

### Comparing `ezkl-1.0.0/LICENSE` & `ezkl-1.0.2/LICENSE`

 * *Files identical despite different names*

### Comparing `ezkl-1.0.0/README.md` & `ezkl-1.0.2/README.md`

 * *Files identical despite different names*

### Comparing `ezkl-1.0.0/ezkl/export.py` & `ezkl-1.0.2/ezkl/export.py`

 * *Files identical despite different names*

### Comparing `ezkl-1.0.0/pyproject.toml` & `ezkl-1.0.2/pyproject.toml`

 * *Files 10% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "ezkl"
-version = "1.0.0"
+version = "1.0.2"
 description = "Easy zero-knowledge learning in Python"
 authors = [
   "Jason Morton <jason@zkonduit.com>",
   "Dante Camuto <jason@zkonduit.com>",
 ]
 readme = "README.md"
 license = "Apache-2.0"
@@ -15,17 +15,17 @@
     "Programming Language :: Python :: 3",
     "License :: OSI Approved :: Apache Software License",
     "Operating System :: OS Independent",
 ]
 
 [tool.poetry.dependencies]
 python = ">=3.8"
-numpy = "*"
-torch = "*"
-onnx = "*"
+numpy = "^1.24.3"
+torch = "^1.13.1"
+onnx = "^1.14.0"
 ezkl_lib = "^0.3.0"
 
 [tool.poetry.group.dev.dependencies]
 pytest = "^7.3.1"
 scikit-learn = "^1.2.2"
 pandas = "^2.0.2"
 jupyter = "^1.0.0"
```

### Comparing `ezkl-1.0.0/PKG-INFO` & `ezkl-1.0.2/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: ezkl
-Version: 1.0.0
+Version: 1.0.2
 Summary: Easy zero-knowledge learning in Python
 Home-page: https://github.com/zkonduit/pyezkl
 License: Apache-2.0
 Author: Jason Morton
 Author-email: jason@zkonduit.com
 Requires-Python: >=3.8
 Classifier: License :: OSI Approved :: Apache Software License
@@ -12,17 +12,17 @@
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
 Classifier: Programming Language :: Python :: 3
 Requires-Dist: ezkl_lib (>=0.3.0,<0.4.0)
-Requires-Dist: numpy
-Requires-Dist: onnx
-Requires-Dist: torch
+Requires-Dist: numpy (>=1.24.3,<2.0.0)
+Requires-Dist: onnx (>=1.14.0,<2.0.0)
+Requires-Dist: torch (>=1.13.1,<2.0.0)
 Project-URL: Repository, https://github.com/zkonduit/pyezkl
 Description-Content-Type: text/markdown
 
 # ezkl
 This repository contains the Python bindings for [ezkl](https://github.com/zkonduit/ezkl).
```

