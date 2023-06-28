# Comparing `tmp/fxdatapi-1.1.2.tar.gz` & `tmp/fxdatapi-1.1.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/fxdatapi-1.1.2.tar", last modified: Thu May 11 01:17:01 2023, max compression
+gzip compressed data, was "dist/fxdatapi-1.1.3.tar", last modified: Wed Jun 28 12:12:58 2023, max compression
```

## Comparing `fxdatapi-1.1.2.tar` & `fxdatapi-1.1.3.tar`

### file list

```diff
@@ -1,26 +1,26 @@
-drwxr-xr-x   0 finn       (501) staff       (20)        0 2023-05-11 01:17:01.920995 fxdatapi-1.1.2/
--rw-r--r--   0 finn       (501) staff       (20)     7211 2023-05-11 01:17:01.921319 fxdatapi-1.1.2/PKG-INFO
--rw-r--r--   0 finn       (501) staff       (20)     3859 2023-05-11 01:13:28.000000 fxdatapi-1.1.2/README.md
-drwxr-xr-x   0 finn       (501) staff       (20)        0 2023-05-11 01:17:01.916353 fxdatapi-1.1.2/fxdatapi/
--rw-r--r--   0 finn       (501) staff       (20)      381 2023-05-11 01:15:48.000000 fxdatapi-1.1.2/fxdatapi/__init__.py
--rw-r--r--   0 finn       (501) staff       (20)      906 2023-05-11 01:15:43.000000 fxdatapi-1.1.2/fxdatapi/auth.py
--rw-r--r--   0 finn       (501) staff       (20)      753 2023-05-11 01:15:35.000000 fxdatapi-1.1.2/fxdatapi/convert.py
--rw-r--r--   0 finn       (501) staff       (20)      707 2023-05-11 01:15:39.000000 fxdatapi-1.1.2/fxdatapi/convert_all.py
--rw-r--r--   0 finn       (501) staff       (20)     1147 2023-05-11 01:15:31.000000 fxdatapi-1.1.2/fxdatapi/currencies.py
--rw-r--r--   0 finn       (501) staff       (20)      491 2023-05-11 01:15:27.000000 fxdatapi-1.1.2/fxdatapi/daily_average.py
--rw-r--r--   0 finn       (501) staff       (20)     1259 2023-05-11 01:15:19.000000 fxdatapi-1.1.2/fxdatapi/historical.py
--rw-r--r--   0 finn       (501) staff       (20)     1216 2023-05-11 01:15:11.000000 fxdatapi-1.1.2/fxdatapi/margins_spreads.py
--rw-r--r--   0 finn       (501) staff       (20)      514 2023-05-11 01:15:07.000000 fxdatapi-1.1.2/fxdatapi/monthly_average.py
--rw-r--r--   0 finn       (501) staff       (20)      972 2023-05-11 01:15:01.000000 fxdatapi-1.1.2/fxdatapi/performances.py
--rw-r--r--   0 finn       (501) staff       (20)      937 2023-05-11 01:14:55.000000 fxdatapi-1.1.2/fxdatapi/signals.py
--rw-r--r--   0 finn       (501) staff       (20)       17 2023-05-11 01:14:51.000000 fxdatapi-1.1.2/fxdatapi/version.py
--rw-r--r--   0 finn       (501) staff       (20)      528 2023-05-11 01:14:43.000000 fxdatapi-1.1.2/fxdatapi/weekly_average.py
-drwxr-xr-x   0 finn       (501) staff       (20)        0 2023-05-11 01:17:01.920413 fxdatapi-1.1.2/fxdatapi.egg-info/
--rw-r--r--   0 finn       (501) staff       (20)     7211 2023-05-11 01:17:01.000000 fxdatapi-1.1.2/fxdatapi.egg-info/PKG-INFO
--rw-r--r--   0 finn       (501) staff       (20)      520 2023-05-11 01:17:01.000000 fxdatapi-1.1.2/fxdatapi.egg-info/SOURCES.txt
--rw-r--r--   0 finn       (501) staff       (20)        1 2023-05-11 01:17:01.000000 fxdatapi-1.1.2/fxdatapi.egg-info/dependency_links.txt
--rw-r--r--   0 finn       (501) staff       (20)        1 2023-05-11 01:16:46.000000 fxdatapi-1.1.2/fxdatapi.egg-info/not-zip-safe
--rw-r--r--   0 finn       (501) staff       (20)        9 2023-05-11 01:17:01.000000 fxdatapi-1.1.2/fxdatapi.egg-info/requires.txt
--rw-r--r--   0 finn       (501) staff       (20)        9 2023-05-11 01:17:01.000000 fxdatapi-1.1.2/fxdatapi.egg-info/top_level.txt
--rw-r--r--   0 finn       (501) staff       (20)       38 2023-05-11 01:17:01.922020 fxdatapi-1.1.2/setup.cfg
--rw-r--r--   0 finn       (501) staff       (20)     2632 2023-05-11 01:13:13.000000 fxdatapi-1.1.2/setup.py
+drwxr-xr-x   0 finn       (501) staff       (20)        0 2023-06-28 12:12:58.236707 fxdatapi-1.1.3/
+-rw-r--r--   0 finn       (501) staff       (20)     7211 2023-06-28 12:12:58.236999 fxdatapi-1.1.3/PKG-INFO
+-rw-r--r--   0 finn       (501) staff       (20)     3859 2023-05-11 01:13:28.000000 fxdatapi-1.1.3/README.md
+drwxr-xr-x   0 finn       (501) staff       (20)        0 2023-06-28 12:12:58.232354 fxdatapi-1.1.3/fxdatapi/
+-rw-r--r--   0 finn       (501) staff       (20)      381 2023-05-11 01:15:48.000000 fxdatapi-1.1.3/fxdatapi/__init__.py
+-rw-r--r--   0 finn       (501) staff       (20)      906 2023-05-11 01:15:43.000000 fxdatapi-1.1.3/fxdatapi/auth.py
+-rw-r--r--   0 finn       (501) staff       (20)      753 2023-05-11 01:15:35.000000 fxdatapi-1.1.3/fxdatapi/convert.py
+-rw-r--r--   0 finn       (501) staff       (20)      707 2023-05-11 01:15:39.000000 fxdatapi-1.1.3/fxdatapi/convert_all.py
+-rw-r--r--   0 finn       (501) staff       (20)     1147 2023-05-11 01:15:31.000000 fxdatapi-1.1.3/fxdatapi/currencies.py
+-rw-r--r--   0 finn       (501) staff       (20)      491 2023-05-11 01:15:27.000000 fxdatapi-1.1.3/fxdatapi/daily_average.py
+-rw-r--r--   0 finn       (501) staff       (20)     1259 2023-05-11 01:15:19.000000 fxdatapi-1.1.3/fxdatapi/historical.py
+-rw-r--r--   0 finn       (501) staff       (20)     1216 2023-05-11 01:15:11.000000 fxdatapi-1.1.3/fxdatapi/margins_spreads.py
+-rw-r--r--   0 finn       (501) staff       (20)      514 2023-05-11 01:15:07.000000 fxdatapi-1.1.3/fxdatapi/monthly_average.py
+-rw-r--r--   0 finn       (501) staff       (20)      972 2023-05-11 01:15:01.000000 fxdatapi-1.1.3/fxdatapi/performances.py
+-rw-r--r--   0 finn       (501) staff       (20)      937 2023-05-11 01:14:55.000000 fxdatapi-1.1.3/fxdatapi/signals.py
+-rw-r--r--   0 finn       (501) staff       (20)       17 2023-06-28 12:11:46.000000 fxdatapi-1.1.3/fxdatapi/version.py
+-rw-r--r--   0 finn       (501) staff       (20)      528 2023-05-11 01:14:43.000000 fxdatapi-1.1.3/fxdatapi/weekly_average.py
+drwxr-xr-x   0 finn       (501) staff       (20)        0 2023-06-28 12:12:58.235922 fxdatapi-1.1.3/fxdatapi.egg-info/
+-rw-r--r--   0 finn       (501) staff       (20)     7211 2023-06-28 12:12:58.000000 fxdatapi-1.1.3/fxdatapi.egg-info/PKG-INFO
+-rw-r--r--   0 finn       (501) staff       (20)      520 2023-06-28 12:12:58.000000 fxdatapi-1.1.3/fxdatapi.egg-info/SOURCES.txt
+-rw-r--r--   0 finn       (501) staff       (20)        1 2023-06-28 12:12:58.000000 fxdatapi-1.1.3/fxdatapi.egg-info/dependency_links.txt
+-rw-r--r--   0 finn       (501) staff       (20)        1 2023-06-28 12:12:34.000000 fxdatapi-1.1.3/fxdatapi.egg-info/not-zip-safe
+-rw-r--r--   0 finn       (501) staff       (20)        9 2023-06-28 12:12:58.000000 fxdatapi-1.1.3/fxdatapi.egg-info/requires.txt
+-rw-r--r--   0 finn       (501) staff       (20)        9 2023-06-28 12:12:58.000000 fxdatapi-1.1.3/fxdatapi.egg-info/top_level.txt
+-rw-r--r--   0 finn       (501) staff       (20)       38 2023-06-28 12:12:58.237532 fxdatapi-1.1.3/setup.cfg
+-rw-r--r--   0 finn       (501) staff       (20)     2632 2023-06-28 12:11:46.000000 fxdatapi-1.1.3/setup.py
```

### Comparing `fxdatapi-1.1.2/PKG-INFO` & `fxdatapi-1.1.3/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: fxdatapi
-Version: 1.1.2
+Version: 1.1.3
 Summary: Python library for integrating with the Currency API.
 Home-page: https://moatsystems.com/currency-api/
 Author: Moat Systems Limited
 Author-email: support@moatsystems.com
 License: BSD 3-Clause
 Project-URL: Bug Tracker, https://github.com/moatsystems/fxdatapi_sdk/issues
 Project-URL: Changes, https://github.com/moatsystems/fxdatapi_sdk/blob/main/CHANGELOG.md
```

### Comparing `fxdatapi-1.1.2/README.md` & `fxdatapi-1.1.3/README.md`

 * *Files identical despite different names*

### Comparing `fxdatapi-1.1.2/fxdatapi/auth.py` & `fxdatapi-1.1.3/fxdatapi/auth.py`

 * *Files identical despite different names*

### Comparing `fxdatapi-1.1.2/fxdatapi/convert.py` & `fxdatapi-1.1.3/fxdatapi/convert.py`

 * *Files identical despite different names*

### Comparing `fxdatapi-1.1.2/fxdatapi/convert_all.py` & `fxdatapi-1.1.3/fxdatapi/convert_all.py`

 * *Files identical despite different names*

### Comparing `fxdatapi-1.1.2/fxdatapi/currencies.py` & `fxdatapi-1.1.3/fxdatapi/currencies.py`

 * *Files identical despite different names*

### Comparing `fxdatapi-1.1.2/fxdatapi/historical.py` & `fxdatapi-1.1.3/fxdatapi/historical.py`

 * *Files identical despite different names*

### Comparing `fxdatapi-1.1.2/fxdatapi/margins_spreads.py` & `fxdatapi-1.1.3/fxdatapi/margins_spreads.py`

 * *Files identical despite different names*

### Comparing `fxdatapi-1.1.2/fxdatapi/monthly_average.py` & `fxdatapi-1.1.3/fxdatapi/monthly_average.py`

 * *Files identical despite different names*

### Comparing `fxdatapi-1.1.2/fxdatapi/performances.py` & `fxdatapi-1.1.3/fxdatapi/performances.py`

 * *Files identical despite different names*

### Comparing `fxdatapi-1.1.2/fxdatapi/signals.py` & `fxdatapi-1.1.3/fxdatapi/signals.py`

 * *Files identical despite different names*

### Comparing `fxdatapi-1.1.2/fxdatapi/weekly_average.py` & `fxdatapi-1.1.3/fxdatapi/weekly_average.py`

 * *Files identical despite different names*

### Comparing `fxdatapi-1.1.2/fxdatapi.egg-info/PKG-INFO` & `fxdatapi-1.1.3/fxdatapi.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: fxdatapi
-Version: 1.1.2
+Version: 1.1.3
 Summary: Python library for integrating with the Currency API.
 Home-page: https://moatsystems.com/currency-api/
 Author: Moat Systems Limited
 Author-email: support@moatsystems.com
 License: BSD 3-Clause
 Project-URL: Bug Tracker, https://github.com/moatsystems/fxdatapi_sdk/issues
 Project-URL: Changes, https://github.com/moatsystems/fxdatapi_sdk/blob/main/CHANGELOG.md
```

### Comparing `fxdatapi-1.1.2/fxdatapi.egg-info/SOURCES.txt` & `fxdatapi-1.1.3/fxdatapi.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `fxdatapi-1.1.2/setup.py` & `fxdatapi-1.1.3/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 # coding: utf-8
 
 import sys
 from setuptools import setup, find_packages  # noqa: H301
 from distutils.core import Extension
 
 NAME = "fxdatapi"
-VERSION = "1.1.2"
+VERSION = "1.1.3"
 REQUIRES = ["requests"]
 
 # read the contents of your README file
 from os import path
 this_directory = path.abspath(path.dirname(__file__))
 with open(path.join(this_directory, 'LONG_DESCRIPTION.rst')) as f:
     long_description = f.read()
```

