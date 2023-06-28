# Comparing `tmp/mls-api-2.0.0.tar.gz` & `tmp/mls-api-2.0.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/mls-api-2.0.0.tar", last modified: Mon Apr 17 17:24:22 2023, max compression
+gzip compressed data, was "dist/mls-api-2.0.1.tar", last modified: Wed Jun 28 12:20:25 2023, max compression
```

## Comparing `mls-api-2.0.0.tar` & `mls-api-2.0.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 finn       (501) staff       (20)        0 2023-04-17 17:24:22.307008 mls-api-2.0.0/
--rw-r--r--   0 finn       (501) staff       (20)     5415 2023-04-17 17:24:22.307538 mls-api-2.0.0/PKG-INFO
--rw-r--r--   0 finn       (501) staff       (20)     2329 2023-04-17 17:23:31.000000 mls-api-2.0.0/README.md
-drwxr-xr-x   0 finn       (501) staff       (20)        0 2023-04-17 17:24:22.296240 mls-api-2.0.0/mls_api/
--rw-r--r--   0 finn       (501) staff       (20)      343 2023-04-16 16:43:33.000000 mls-api-2.0.0/mls_api/__init__.py
--rw-r--r--   0 finn       (501) staff       (20)     1492 2023-04-16 16:55:53.000000 mls-api-2.0.0/mls_api/assists.py
--rw-r--r--   0 finn       (501) staff       (20)      658 2023-04-17 17:22:53.000000 mls-api-2.0.0/mls_api/auth.py
--rw-r--r--   0 finn       (501) staff       (20)     1500 2023-04-16 16:56:03.000000 mls-api-2.0.0/mls_api/fixtures.py
--rw-r--r--   0 finn       (501) staff       (20)     1510 2023-04-16 16:56:14.000000 mls-api-2.0.0/mls_api/historical.py
--rw-r--r--   0 finn       (501) staff       (20)     1496 2023-04-16 16:56:25.000000 mls-api-2.0.0/mls_api/latest_news.py
--rw-r--r--   0 finn       (501) staff       (20)     1492 2023-04-16 16:56:48.000000 mls-api-2.0.0/mls_api/offense.py
--rw-r--r--   0 finn       (501) staff       (20)     1691 2023-04-16 17:08:48.000000 mls-api-2.0.0/mls_api/players.py
--rw-r--r--   0 finn       (501) staff       (20)     1458 2023-04-16 16:57:12.000000 mls-api-2.0.0/mls_api/rtd.py
--rw-r--r--   0 finn       (501) staff       (20)    34581 2023-04-16 06:09:23.000000 mls-api-2.0.0/mls_api/six.py
--rw-r--r--   0 finn       (501) staff       (20)     1508 2023-04-16 16:57:23.000000 mls-api-2.0.0/mls_api/standings.py
--rw-r--r--   0 finn       (501) staff       (20)     1476 2023-04-16 16:57:34.000000 mls-api-2.0.0/mls_api/teams.py
--rw-r--r--   0 finn       (501) staff       (20)     1512 2023-04-16 16:57:46.000000 mls-api-2.0.0/mls_api/top_scorer.py
--rw-r--r--   0 finn       (501) staff       (20)       17 2023-04-17 17:22:41.000000 mls-api-2.0.0/mls_api/version.py
-drwxr-xr-x   0 finn       (501) staff       (20)        0 2023-04-17 17:24:22.306279 mls-api-2.0.0/mls_api.egg-info/
--rw-r--r--   0 finn       (501) staff       (20)     5415 2023-04-17 17:24:22.000000 mls-api-2.0.0/mls_api.egg-info/PKG-INFO
--rw-r--r--   0 finn       (501) staff       (20)      479 2023-04-17 17:24:22.000000 mls-api-2.0.0/mls_api.egg-info/SOURCES.txt
--rw-r--r--   0 finn       (501) staff       (20)        1 2023-04-17 17:24:22.000000 mls-api-2.0.0/mls_api.egg-info/dependency_links.txt
--rw-r--r--   0 finn       (501) staff       (20)        1 2023-04-17 17:24:05.000000 mls-api-2.0.0/mls_api.egg-info/not-zip-safe
--rw-r--r--   0 finn       (501) staff       (20)        9 2023-04-17 17:24:22.000000 mls-api-2.0.0/mls_api.egg-info/requires.txt
--rw-r--r--   0 finn       (501) staff       (20)        8 2023-04-17 17:24:22.000000 mls-api-2.0.0/mls_api.egg-info/top_level.txt
--rw-r--r--   0 finn       (501) staff       (20)       38 2023-04-17 17:24:22.309198 mls-api-2.0.0/setup.cfg
--rw-r--r--   0 finn       (501) staff       (20)     2476 2023-04-17 17:22:41.000000 mls-api-2.0.0/setup.py
+drwxr-xr-x   0 finn       (501) staff       (20)        0 2023-06-28 12:20:25.149834 mls-api-2.0.1/
+-rw-r--r--   0 finn       (501) staff       (20)     5415 2023-06-28 12:20:25.150092 mls-api-2.0.1/PKG-INFO
+-rw-r--r--   0 finn       (501) staff       (20)     2329 2023-04-17 17:23:31.000000 mls-api-2.0.1/README.md
+drwxr-xr-x   0 finn       (501) staff       (20)        0 2023-06-28 12:20:25.144855 mls-api-2.0.1/mls_api/
+-rw-r--r--   0 finn       (501) staff       (20)      343 2023-04-16 16:43:33.000000 mls-api-2.0.1/mls_api/__init__.py
+-rw-r--r--   0 finn       (501) staff       (20)     1492 2023-04-16 16:55:53.000000 mls-api-2.0.1/mls_api/assists.py
+-rw-r--r--   0 finn       (501) staff       (20)      658 2023-04-17 17:22:53.000000 mls-api-2.0.1/mls_api/auth.py
+-rw-r--r--   0 finn       (501) staff       (20)     1500 2023-04-16 16:56:03.000000 mls-api-2.0.1/mls_api/fixtures.py
+-rw-r--r--   0 finn       (501) staff       (20)     1510 2023-04-16 16:56:14.000000 mls-api-2.0.1/mls_api/historical.py
+-rw-r--r--   0 finn       (501) staff       (20)     1496 2023-04-16 16:56:25.000000 mls-api-2.0.1/mls_api/latest_news.py
+-rw-r--r--   0 finn       (501) staff       (20)     1492 2023-04-16 16:56:48.000000 mls-api-2.0.1/mls_api/offense.py
+-rw-r--r--   0 finn       (501) staff       (20)     1691 2023-04-16 17:08:48.000000 mls-api-2.0.1/mls_api/players.py
+-rw-r--r--   0 finn       (501) staff       (20)     1458 2023-04-16 16:57:12.000000 mls-api-2.0.1/mls_api/rtd.py
+-rw-r--r--   0 finn       (501) staff       (20)    34581 2023-04-16 06:09:23.000000 mls-api-2.0.1/mls_api/six.py
+-rw-r--r--   0 finn       (501) staff       (20)     1508 2023-04-16 16:57:23.000000 mls-api-2.0.1/mls_api/standings.py
+-rw-r--r--   0 finn       (501) staff       (20)     1476 2023-04-16 16:57:34.000000 mls-api-2.0.1/mls_api/teams.py
+-rw-r--r--   0 finn       (501) staff       (20)     1512 2023-04-16 16:57:46.000000 mls-api-2.0.1/mls_api/top_scorer.py
+-rw-r--r--   0 finn       (501) staff       (20)       17 2023-06-28 12:19:19.000000 mls-api-2.0.1/mls_api/version.py
+drwxr-xr-x   0 finn       (501) staff       (20)        0 2023-06-28 12:20:25.149366 mls-api-2.0.1/mls_api.egg-info/
+-rw-r--r--   0 finn       (501) staff       (20)     5415 2023-06-28 12:20:25.000000 mls-api-2.0.1/mls_api.egg-info/PKG-INFO
+-rw-r--r--   0 finn       (501) staff       (20)      479 2023-06-28 12:20:25.000000 mls-api-2.0.1/mls_api.egg-info/SOURCES.txt
+-rw-r--r--   0 finn       (501) staff       (20)        1 2023-06-28 12:20:25.000000 mls-api-2.0.1/mls_api.egg-info/dependency_links.txt
+-rw-r--r--   0 finn       (501) staff       (20)        1 2023-06-28 12:19:41.000000 mls-api-2.0.1/mls_api.egg-info/not-zip-safe
+-rw-r--r--   0 finn       (501) staff       (20)        9 2023-06-28 12:20:25.000000 mls-api-2.0.1/mls_api.egg-info/requires.txt
+-rw-r--r--   0 finn       (501) staff       (20)        8 2023-06-28 12:20:25.000000 mls-api-2.0.1/mls_api.egg-info/top_level.txt
+-rw-r--r--   0 finn       (501) staff       (20)       38 2023-06-28 12:20:25.150605 mls-api-2.0.1/setup.cfg
+-rw-r--r--   0 finn       (501) staff       (20)     2476 2023-06-28 12:19:19.000000 mls-api-2.0.1/setup.py
```

### Comparing `mls-api-2.0.0/PKG-INFO` & `mls-api-2.0.1/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: mls-api
-Version: 2.0.0
+Version: 2.0.1
 Summary: Python library for integrating with the MLS (Major League Soccer) API.
 Home-page: https://moatsystems.com/mls-api/
 Author: Moat Systems Limited
 Author-email: support@moatsystems.com
 License: MIT
 Project-URL: Bug Tracker, https://github.com/moatsystems/mlsapi-python/issues
 Project-URL: Changes, https://github.com/moatsystems/mlsapi-python/blob/main/CHANGELOG.md
```

### Comparing `mls-api-2.0.0/README.md` & `mls-api-2.0.1/README.md`

 * *Files identical despite different names*

### Comparing `mls-api-2.0.0/mls_api/assists.py` & `mls-api-2.0.1/mls_api/assists.py`

 * *Files identical despite different names*

### Comparing `mls-api-2.0.0/mls_api/auth.py` & `mls-api-2.0.1/mls_api/auth.py`

 * *Files identical despite different names*

### Comparing `mls-api-2.0.0/mls_api/fixtures.py` & `mls-api-2.0.1/mls_api/fixtures.py`

 * *Files identical despite different names*

### Comparing `mls-api-2.0.0/mls_api/historical.py` & `mls-api-2.0.1/mls_api/historical.py`

 * *Files identical despite different names*

### Comparing `mls-api-2.0.0/mls_api/latest_news.py` & `mls-api-2.0.1/mls_api/latest_news.py`

 * *Files identical despite different names*

### Comparing `mls-api-2.0.0/mls_api/offense.py` & `mls-api-2.0.1/mls_api/offense.py`

 * *Files identical despite different names*

### Comparing `mls-api-2.0.0/mls_api/players.py` & `mls-api-2.0.1/mls_api/players.py`

 * *Files identical despite different names*

### Comparing `mls-api-2.0.0/mls_api/rtd.py` & `mls-api-2.0.1/mls_api/rtd.py`

 * *Files identical despite different names*

### Comparing `mls-api-2.0.0/mls_api/six.py` & `mls-api-2.0.1/mls_api/six.py`

 * *Files identical despite different names*

### Comparing `mls-api-2.0.0/mls_api/standings.py` & `mls-api-2.0.1/mls_api/standings.py`

 * *Files identical despite different names*

### Comparing `mls-api-2.0.0/mls_api/teams.py` & `mls-api-2.0.1/mls_api/teams.py`

 * *Files identical despite different names*

### Comparing `mls-api-2.0.0/mls_api/top_scorer.py` & `mls-api-2.0.1/mls_api/top_scorer.py`

 * *Files identical despite different names*

### Comparing `mls-api-2.0.0/mls_api.egg-info/PKG-INFO` & `mls-api-2.0.1/mls_api.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: mls-api
-Version: 2.0.0
+Version: 2.0.1
 Summary: Python library for integrating with the MLS (Major League Soccer) API.
 Home-page: https://moatsystems.com/mls-api/
 Author: Moat Systems Limited
 Author-email: support@moatsystems.com
 License: MIT
 Project-URL: Bug Tracker, https://github.com/moatsystems/mlsapi-python/issues
 Project-URL: Changes, https://github.com/moatsystems/mlsapi-python/blob/main/CHANGELOG.md
```

### Comparing `mls-api-2.0.0/setup.py` & `mls-api-2.0.1/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 # coding: utf-8
 
 import sys
 from setuptools import setup, find_packages  # noqa: H301
 from distutils.core import Extension
 
 NAME = "mls-api"
-VERSION = "2.0.0"
+VERSION = "2.0.1"
 REQUIRES = ["requests"]
 
 # read the contents of your README file
 from os import path
 this_directory = path.abspath(path.dirname(__file__))
 with open(path.join(this_directory, 'LONG_DESCRIPTION.rst')) as f:
     long_description = f.read()
```

