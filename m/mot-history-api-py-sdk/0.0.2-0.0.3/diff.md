# Comparing `tmp/mot-history-api-py-sdk-0.0.2.tar.gz` & `tmp/mot-history-api-py-sdk-0.0.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/mot-history-api-py-sdk-0.0.2.tar", last modified: Sat Feb 18 22:28:31 2023, max compression
+gzip compressed data, was "dist/mot-history-api-py-sdk-0.0.3.tar", last modified: Wed Jun 28 11:50:53 2023, max compression
```

## Comparing `mot-history-api-py-sdk-0.0.2.tar` & `mot-history-api-py-sdk-0.0.3.tar`

### file list

```diff
@@ -1,15 +1,15 @@
-drwxr-xr-x   0 finn       (501) staff       (20)        0 2023-02-18 22:28:31.586650 mot-history-api-py-sdk-0.0.2/
--rw-r--r--   0 finn       (501) staff       (20)     5527 2023-02-18 22:28:31.587020 mot-history-api-py-sdk-0.0.2/PKG-INFO
--rw-r--r--   0 finn       (501) staff       (20)     2433 2023-02-18 22:24:20.000000 mot-history-api-py-sdk-0.0.2/README.md
-drwxr-xr-x   0 finn       (501) staff       (20)        0 2023-02-18 22:28:31.584830 mot-history-api-py-sdk-0.0.2/mot_history_api_py_sdk.egg-info/
--rw-r--r--   0 finn       (501) staff       (20)     5527 2023-02-18 22:28:31.000000 mot-history-api-py-sdk-0.0.2/mot_history_api_py_sdk.egg-info/PKG-INFO
--rw-r--r--   0 finn       (501) staff       (20)      339 2023-02-18 22:28:31.000000 mot-history-api-py-sdk-0.0.2/mot_history_api_py_sdk.egg-info/SOURCES.txt
--rw-r--r--   0 finn       (501) staff       (20)        1 2023-02-18 22:28:31.000000 mot-history-api-py-sdk-0.0.2/mot_history_api_py_sdk.egg-info/dependency_links.txt
--rw-r--r--   0 finn       (501) staff       (20)        1 2023-02-18 22:27:52.000000 mot-history-api-py-sdk-0.0.2/mot_history_api_py_sdk.egg-info/not-zip-safe
--rw-r--r--   0 finn       (501) staff       (20)        9 2023-02-18 22:28:31.000000 mot-history-api-py-sdk-0.0.2/mot_history_api_py_sdk.egg-info/requires.txt
--rw-r--r--   0 finn       (501) staff       (20)        7 2023-02-18 22:28:31.000000 mot-history-api-py-sdk-0.0.2/mot_history_api_py_sdk.egg-info/top_level.txt
-drwxr-xr-x   0 finn       (501) staff       (20)        0 2023-02-18 22:28:31.586073 mot-history-api-py-sdk-0.0.2/motapi/
--rw-r--r--   0 finn       (501) staff       (20)       28 2023-02-17 11:50:16.000000 mot-history-api-py-sdk-0.0.2/motapi/__init__.py
--rw-r--r--   0 finn       (501) staff       (20)     1421 2023-02-18 22:15:14.000000 mot-history-api-py-sdk-0.0.2/motapi/motdata.py
--rw-r--r--   0 finn       (501) staff       (20)       38 2023-02-18 22:28:31.587666 mot-history-api-py-sdk-0.0.2/setup.cfg
--rw-r--r--   0 finn       (501) staff       (20)     2606 2023-02-18 22:26:49.000000 mot-history-api-py-sdk-0.0.2/setup.py
+drwxr-xr-x   0 finn       (501) staff       (20)        0 2023-06-28 11:50:53.319580 mot-history-api-py-sdk-0.0.3/
+-rw-r--r--   0 finn       (501) staff       (20)     5527 2023-06-28 11:50:53.319908 mot-history-api-py-sdk-0.0.3/PKG-INFO
+-rw-r--r--   0 finn       (501) staff       (20)     2433 2023-02-18 22:24:20.000000 mot-history-api-py-sdk-0.0.3/README.md
+drwxr-xr-x   0 finn       (501) staff       (20)        0 2023-06-28 11:50:53.316887 mot-history-api-py-sdk-0.0.3/mot_history_api_py_sdk.egg-info/
+-rw-r--r--   0 finn       (501) staff       (20)     5527 2023-06-28 11:50:53.000000 mot-history-api-py-sdk-0.0.3/mot_history_api_py_sdk.egg-info/PKG-INFO
+-rw-r--r--   0 finn       (501) staff       (20)      339 2023-06-28 11:50:53.000000 mot-history-api-py-sdk-0.0.3/mot_history_api_py_sdk.egg-info/SOURCES.txt
+-rw-r--r--   0 finn       (501) staff       (20)        1 2023-06-28 11:50:53.000000 mot-history-api-py-sdk-0.0.3/mot_history_api_py_sdk.egg-info/dependency_links.txt
+-rw-r--r--   0 finn       (501) staff       (20)        1 2023-06-28 11:50:32.000000 mot-history-api-py-sdk-0.0.3/mot_history_api_py_sdk.egg-info/not-zip-safe
+-rw-r--r--   0 finn       (501) staff       (20)        9 2023-06-28 11:50:53.000000 mot-history-api-py-sdk-0.0.3/mot_history_api_py_sdk.egg-info/requires.txt
+-rw-r--r--   0 finn       (501) staff       (20)        7 2023-06-28 11:50:53.000000 mot-history-api-py-sdk-0.0.3/mot_history_api_py_sdk.egg-info/top_level.txt
+drwxr-xr-x   0 finn       (501) staff       (20)        0 2023-06-28 11:50:53.318547 mot-history-api-py-sdk-0.0.3/motapi/
+-rw-r--r--   0 finn       (501) staff       (20)       28 2023-02-17 11:50:16.000000 mot-history-api-py-sdk-0.0.3/motapi/__init__.py
+-rw-r--r--   0 finn       (501) staff       (20)     1421 2023-02-18 22:15:14.000000 mot-history-api-py-sdk-0.0.3/motapi/motdata.py
+-rw-r--r--   0 finn       (501) staff       (20)       38 2023-06-28 11:50:53.320959 mot-history-api-py-sdk-0.0.3/setup.cfg
+-rw-r--r--   0 finn       (501) staff       (20)     2606 2023-06-28 11:47:17.000000 mot-history-api-py-sdk-0.0.3/setup.py
```

### Comparing `mot-history-api-py-sdk-0.0.2/PKG-INFO` & `mot-history-api-py-sdk-0.0.3/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: mot-history-api-py-sdk
-Version: 0.0.2
+Version: 0.0.3
 Summary: The SDK provides convenient access to the MOT History API for applications written in the Python programming language.
 Home-page: https://dvsa.github.io/mot-history-api-documentation/
 Author: Finbarrs Oketunji
 Author-email: f@finbarrs.eu
 License: MIT
 Project-URL: Bug Tracker, https://github.com/0xnu/mot-history-api-sdk/issues
 Project-URL: Changes, https://github.com/0xnu/mot-history-api-sdk/blob/main/CHANGELOG.md
```

### Comparing `mot-history-api-py-sdk-0.0.2/README.md` & `mot-history-api-py-sdk-0.0.3/README.md`

 * *Files identical despite different names*

### Comparing `mot-history-api-py-sdk-0.0.2/mot_history_api_py_sdk.egg-info/PKG-INFO` & `mot-history-api-py-sdk-0.0.3/mot_history_api_py_sdk.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: mot-history-api-py-sdk
-Version: 0.0.2
+Version: 0.0.3
 Summary: The SDK provides convenient access to the MOT History API for applications written in the Python programming language.
 Home-page: https://dvsa.github.io/mot-history-api-documentation/
 Author: Finbarrs Oketunji
 Author-email: f@finbarrs.eu
 License: MIT
 Project-URL: Bug Tracker, https://github.com/0xnu/mot-history-api-sdk/issues
 Project-URL: Changes, https://github.com/0xnu/mot-history-api-sdk/blob/main/CHANGELOG.md
```

### Comparing `mot-history-api-py-sdk-0.0.2/motapi/motdata.py` & `mot-history-api-py-sdk-0.0.3/motapi/motdata.py`

 * *Files identical despite different names*

### Comparing `mot-history-api-py-sdk-0.0.2/setup.py` & `mot-history-api-py-sdk-0.0.3/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 # coding: utf-8
 
 import sys
 from setuptools import setup, find_packages  # noqa: H301
 from distutils.core import Extension
 
 NAME = "mot-history-api-py-sdk"
-VERSION = "0.0.2"
+VERSION = "0.0.3"
 REQUIRES = ["requests"]
 
 # read the contents of your README file
 from os import path
 this_directory = path.abspath(path.dirname(__file__))
 with open(path.join(this_directory, 'LONG_DESCRIPTION.rst')) as f:
     long_description = f.read()
```

