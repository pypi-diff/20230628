# Comparing `tmp/nonstd-0.0.6.tar.gz` & `tmp/nonstd-0.0.7.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "nonstd-0.0.6.tar", max compression
+gzip compressed data, was "nonstd-0.0.7.tar", max compression
```

## Comparing `nonstd-0.0.6.tar` & `nonstd-0.0.7.tar`

### file list

```diff
@@ -1,9 +1,9 @@
--rw-r--r--   0        0        0      226 2022-10-07 18:40:14.007136 nonstd-0.0.6/README.md
--rw-r--r--   0        0        0        0 2022-09-19 13:55:15.915217 nonstd-0.0.6/nonstd/__init__.py
--rw-r--r--   0        0        0     1119 2023-05-11 17:20:08.640707 nonstd-0.0.6/nonstd/derivative.py
--rw-r--r--   0        0        0     9740 2023-05-11 20:32:44.919166 nonstd-0.0.6/nonstd/distributions.py
--rw-r--r--   0        0        0      900 2023-05-11 10:37:06.980105 nonstd-0.0.6/nonstd/logging.py
--rw-r--r--   0        0        0    12222 2023-05-11 17:20:08.641178 nonstd-0.0.6/nonstd/sequence.py
--rw-r--r--   0        0        0     1685 2023-05-11 17:20:08.641331 nonstd-0.0.6/nonstd/sequence_math.py
--rw-r--r--   0        0        0      600 2023-05-13 13:35:38.303646 nonstd-0.0.6/pyproject.toml
--rw-r--r--   0        0        0      809 1970-01-01 00:00:00.000000 nonstd-0.0.6/PKG-INFO
+-rw-r--r--   0        0        0      226 2022-10-07 18:40:14.007136 nonstd-0.0.7/README.md
+-rw-r--r--   0        0        0        0 2022-09-19 13:55:15.915217 nonstd-0.0.7/nonstd/__init__.py
+-rw-r--r--   0        0        0     1119 2023-05-11 17:20:08.640707 nonstd-0.0.7/nonstd/derivative.py
+-rw-r--r--   0        0        0      900 2023-05-11 10:37:06.980105 nonstd-0.0.7/nonstd/logging.py
+-rw-r--r--   0        0        0    12222 2023-05-11 17:20:08.641178 nonstd-0.0.7/nonstd/sequence.py
+-rw-r--r--   0        0        0     1685 2023-05-11 17:20:08.641331 nonstd-0.0.7/nonstd/sequence_math.py
+-rw-r--r--   0        0        0      297 2023-06-12 16:05:44.065605 nonstd-0.0.7/nonstd/timer.py
+-rw-r--r--   0        0        0      622 2023-06-28 14:41:27.375581 nonstd-0.0.7/pyproject.toml
+-rw-r--r--   0        0        0      852 1970-01-01 00:00:00.000000 nonstd-0.0.7/PKG-INFO
```

### Comparing `nonstd-0.0.6/nonstd/derivative.py` & `nonstd-0.0.7/nonstd/derivative.py`

 * *Files identical despite different names*

### Comparing `nonstd-0.0.6/nonstd/logging.py` & `nonstd-0.0.7/nonstd/logging.py`

 * *Files identical despite different names*

### Comparing `nonstd-0.0.6/nonstd/sequence.py` & `nonstd-0.0.7/nonstd/sequence.py`

 * *Files identical despite different names*

### Comparing `nonstd-0.0.6/nonstd/sequence_math.py` & `nonstd-0.0.7/nonstd/sequence_math.py`

 * *Files identical despite different names*

### Comparing `nonstd-0.0.6/pyproject.toml` & `nonstd-0.0.7/pyproject.toml`

 * *Files 18% similar despite different names*

```diff
@@ -1,18 +1,19 @@
 [tool.poetry]
 name = "nonstd"
-version = "0.0.6"
+version = "0.0.7"
 description = "Tom's non-standard library of useful classes and functions."
 authors = ["tadamcz <tadamczewskipublic@gmail.com>"]
 readme = "README.md"
 homepage = "https://github.com/tadamcz/nonstd"
 
 [tool.poetry.dependencies]
 python = ">=3.8,<3.12"
 scipy = "^1.10.1"
+codetiming = "^1.4.0"
 
 [tool.poetry.dev-dependencies]
 pytest = "^7.1.3"
 pytest-pycharm = "^0.7.0"
 
 [tool.poetry.group.dev.dependencies]
 bump2version = "^1.0.1"
```

### Comparing `nonstd-0.0.6/PKG-INFO` & `nonstd-0.0.7/PKG-INFO`

 * *Files 7% similar despite different names*

```diff
@@ -1,20 +1,21 @@
 Metadata-Version: 2.1
 Name: nonstd
-Version: 0.0.6
+Version: 0.0.7
 Summary: Tom's non-standard library of useful classes and functions.
 Home-page: https://github.com/tadamcz/nonstd
 Author: tadamcz
 Author-email: tadamczewskipublic@gmail.com
 Requires-Python: >=3.8,<3.12
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
+Requires-Dist: codetiming (>=1.4.0,<2.0.0)
 Requires-Dist: scipy (>=1.10.1,<2.0.0)
 Description-Content-Type: text/markdown
 
 # My non-standard library
 Personal collection of Python utilities.  
 
 # Installation
```

