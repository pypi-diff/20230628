# Comparing `tmp/cryptodatapi-1.0.5.tar.gz` & `tmp/cryptodatapi-1.0.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/cryptodatapi-1.0.5.tar", last modified: Thu Jan 26 03:17:21 2023, max compression
+gzip compressed data, was "dist/cryptodatapi-1.0.6.tar", last modified: Wed Jun 28 12:34:42 2023, max compression
```

## Comparing `cryptodatapi-1.0.5.tar` & `cryptodatapi-1.0.6.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 finn       (501) staff       (20)        0 2023-01-26 03:17:21.424494 cryptodatapi-1.0.5/
--rw-r--r--   0 finn       (501) staff       (20)     8089 2023-01-26 03:17:21.424850 cryptodatapi-1.0.5/PKG-INFO
--rw-r--r--   0 finn       (501) staff       (20)     4419 2023-01-26 03:07:05.000000 cryptodatapi-1.0.5/README.md
-drwxr-xr-x   0 finn       (501) staff       (20)        0 2023-01-26 03:17:21.420544 cryptodatapi-1.0.5/cryptodatapi/
--rw-r--r--   0 finn       (501) staff       (20)      361 2022-09-13 20:54:36.000000 cryptodatapi-1.0.5/cryptodatapi/__init__.py
--rw-r--r--   0 finn       (501) staff       (20)     1613 1970-01-01 00:00:00.000000 cryptodatapi-1.0.5/cryptodatapi/crypto_price.py
--rw-r--r--   0 finn       (501) staff       (20)     1542 1970-01-01 00:00:00.000000 cryptodatapi-1.0.5/cryptodatapi/derivatives.py
--rw-r--r--   0 finn       (501) staff       (20)     1478 1970-01-01 00:00:00.000000 cryptodatapi-1.0.5/cryptodatapi/dex.py
--rw-r--r--   0 finn       (501) staff       (20)     1463 2022-09-13 20:54:10.000000 cryptodatapi-1.0.5/cryptodatapi/gainers.py
--rw-r--r--   0 finn       (501) staff       (20)     4817 2023-01-26 03:13:22.000000 cryptodatapi-1.0.5/cryptodatapi/hist_price.py
--rw-r--r--   0 finn       (501) staff       (20)     1510 1970-01-01 00:00:00.000000 cryptodatapi-1.0.5/cryptodatapi/lending.py
--rw-r--r--   0 finn       (501) staff       (20)      626 1970-01-01 00:00:00.000000 cryptodatapi-1.0.5/cryptodatapi/login.py
--rw-r--r--   0 finn       (501) staff       (20)     1455 2022-09-13 20:54:08.000000 cryptodatapi-1.0.5/cryptodatapi/losers.py
--rw-r--r--   0 finn       (501) staff       (20)     1486 1970-01-01 00:00:00.000000 cryptodatapi-1.0.5/cryptodatapi/news.py
--rw-r--r--   0 finn       (501) staff       (20)     1486 1970-01-01 00:00:00.000000 cryptodatapi-1.0.5/cryptodatapi/spot.py
--rw-r--r--   0 finn       (501) staff       (20)       17 2022-09-13 21:05:24.000000 cryptodatapi-1.0.5/cryptodatapi/version.py
-drwxr-xr-x   0 finn       (501) staff       (20)        0 2023-01-26 03:17:21.423920 cryptodatapi-1.0.5/cryptodatapi.egg-info/
--rw-r--r--   0 finn       (501) staff       (20)     8089 2023-01-26 03:17:21.000000 cryptodatapi-1.0.5/cryptodatapi.egg-info/PKG-INFO
--rw-r--r--   0 finn       (501) staff       (20)      530 2023-01-26 03:17:21.000000 cryptodatapi-1.0.5/cryptodatapi.egg-info/SOURCES.txt
--rw-r--r--   0 finn       (501) staff       (20)        1 2023-01-26 03:17:21.000000 cryptodatapi-1.0.5/cryptodatapi.egg-info/dependency_links.txt
--rw-r--r--   0 finn       (501) staff       (20)        1 2023-01-26 03:17:11.000000 cryptodatapi-1.0.5/cryptodatapi.egg-info/not-zip-safe
--rw-r--r--   0 finn       (501) staff       (20)        9 2023-01-26 03:17:21.000000 cryptodatapi-1.0.5/cryptodatapi.egg-info/requires.txt
--rw-r--r--   0 finn       (501) staff       (20)       13 2023-01-26 03:17:21.000000 cryptodatapi-1.0.5/cryptodatapi.egg-info/top_level.txt
--rw-r--r--   0 finn       (501) staff       (20)       38 2023-01-26 03:17:21.425678 cryptodatapi-1.0.5/setup.cfg
--rw-r--r--   0 finn       (501) staff       (20)     2571 2023-01-26 03:15:08.000000 cryptodatapi-1.0.5/setup.py
+drwxr-xr-x   0 finn       (501) staff       (20)        0 2023-06-28 12:34:42.924672 cryptodatapi-1.0.6/
+-rw-r--r--   0 finn       (501) staff       (20)     8089 2023-06-28 12:34:42.925066 cryptodatapi-1.0.6/PKG-INFO
+-rw-r--r--   0 finn       (501) staff       (20)     4419 2023-06-28 12:31:43.000000 cryptodatapi-1.0.6/README.md
+drwxr-xr-x   0 finn       (501) staff       (20)        0 2023-06-28 12:34:42.918753 cryptodatapi-1.0.6/cryptodatapi/
+-rw-r--r--   0 finn       (501) staff       (20)      361 2023-06-28 12:31:58.000000 cryptodatapi-1.0.6/cryptodatapi/__init__.py
+-rw-r--r--   0 finn       (501) staff       (20)     1613 2023-06-28 12:31:58.000000 cryptodatapi-1.0.6/cryptodatapi/crypto_price.py
+-rw-r--r--   0 finn       (501) staff       (20)     1542 2023-06-28 12:31:58.000000 cryptodatapi-1.0.6/cryptodatapi/derivatives.py
+-rw-r--r--   0 finn       (501) staff       (20)     1478 2023-06-28 12:31:58.000000 cryptodatapi-1.0.6/cryptodatapi/dex.py
+-rw-r--r--   0 finn       (501) staff       (20)     1463 2023-06-28 12:31:58.000000 cryptodatapi-1.0.6/cryptodatapi/gainers.py
+-rw-r--r--   0 finn       (501) staff       (20)     4817 2023-06-28 12:31:58.000000 cryptodatapi-1.0.6/cryptodatapi/hist_price.py
+-rw-r--r--   0 finn       (501) staff       (20)     1510 2023-06-28 12:31:58.000000 cryptodatapi-1.0.6/cryptodatapi/lending.py
+-rw-r--r--   0 finn       (501) staff       (20)      626 2023-06-28 12:31:58.000000 cryptodatapi-1.0.6/cryptodatapi/login.py
+-rw-r--r--   0 finn       (501) staff       (20)     1455 2023-06-28 12:31:58.000000 cryptodatapi-1.0.6/cryptodatapi/losers.py
+-rw-r--r--   0 finn       (501) staff       (20)     1486 2023-06-28 12:31:58.000000 cryptodatapi-1.0.6/cryptodatapi/news.py
+-rw-r--r--   0 finn       (501) staff       (20)     1486 2023-06-28 12:31:58.000000 cryptodatapi-1.0.6/cryptodatapi/spot.py
+-rw-r--r--   0 finn       (501) staff       (20)       17 2023-06-28 12:31:58.000000 cryptodatapi-1.0.6/cryptodatapi/version.py
+drwxr-xr-x   0 finn       (501) staff       (20)        0 2023-06-28 12:34:42.924039 cryptodatapi-1.0.6/cryptodatapi.egg-info/
+-rw-r--r--   0 finn       (501) staff       (20)     8089 2023-06-28 12:34:42.000000 cryptodatapi-1.0.6/cryptodatapi.egg-info/PKG-INFO
+-rw-r--r--   0 finn       (501) staff       (20)      530 2023-06-28 12:34:42.000000 cryptodatapi-1.0.6/cryptodatapi.egg-info/SOURCES.txt
+-rw-r--r--   0 finn       (501) staff       (20)        1 2023-06-28 12:34:42.000000 cryptodatapi-1.0.6/cryptodatapi.egg-info/dependency_links.txt
+-rw-r--r--   0 finn       (501) staff       (20)        1 2023-06-28 12:33:59.000000 cryptodatapi-1.0.6/cryptodatapi.egg-info/not-zip-safe
+-rw-r--r--   0 finn       (501) staff       (20)        9 2023-06-28 12:34:42.000000 cryptodatapi-1.0.6/cryptodatapi.egg-info/requires.txt
+-rw-r--r--   0 finn       (501) staff       (20)       13 2023-06-28 12:34:42.000000 cryptodatapi-1.0.6/cryptodatapi.egg-info/top_level.txt
+-rw-r--r--   0 finn       (501) staff       (20)       38 2023-06-28 12:34:42.926124 cryptodatapi-1.0.6/setup.cfg
+-rw-r--r--   0 finn       (501) staff       (20)     2571 2023-06-28 12:31:43.000000 cryptodatapi-1.0.6/setup.py
```

### Comparing `cryptodatapi-1.0.5/PKG-INFO` & `cryptodatapi-1.0.6/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: cryptodatapi
-Version: 1.0.5
+Version: 1.0.6
 Summary: Python SDK for integrating with Crypto API.
 Home-page: https://moatsystems.com/crypto-api/
 Author: Moat Systems Limited
 Author-email: support@moatsystems.com
 License: MIT
 Project-URL: Bug Tracker, https://github.com/moatsystems/cryptodatapi-py-sdk/issues
 Project-URL: Changes, https://github.com/moatsystems/cryptodatapi-py-sdk/blob/main/CHANGELOG.md
```

### Comparing `cryptodatapi-1.0.5/README.md` & `cryptodatapi-1.0.6/README.md`

 * *Files identical despite different names*

### Comparing `cryptodatapi-1.0.5/cryptodatapi/crypto_price.py` & `cryptodatapi-1.0.6/cryptodatapi/crypto_price.py`

 * *Files identical despite different names*

### Comparing `cryptodatapi-1.0.5/cryptodatapi/derivatives.py` & `cryptodatapi-1.0.6/cryptodatapi/derivatives.py`

 * *Files identical despite different names*

### Comparing `cryptodatapi-1.0.5/cryptodatapi/dex.py` & `cryptodatapi-1.0.6/cryptodatapi/dex.py`

 * *Files identical despite different names*

### Comparing `cryptodatapi-1.0.5/cryptodatapi/gainers.py` & `cryptodatapi-1.0.6/cryptodatapi/gainers.py`

 * *Files identical despite different names*

### Comparing `cryptodatapi-1.0.5/cryptodatapi/hist_price.py` & `cryptodatapi-1.0.6/cryptodatapi/hist_price.py`

 * *Files identical despite different names*

### Comparing `cryptodatapi-1.0.5/cryptodatapi/lending.py` & `cryptodatapi-1.0.6/cryptodatapi/lending.py`

 * *Files identical despite different names*

### Comparing `cryptodatapi-1.0.5/cryptodatapi/login.py` & `cryptodatapi-1.0.6/cryptodatapi/login.py`

 * *Files identical despite different names*

### Comparing `cryptodatapi-1.0.5/cryptodatapi/losers.py` & `cryptodatapi-1.0.6/cryptodatapi/losers.py`

 * *Files identical despite different names*

### Comparing `cryptodatapi-1.0.5/cryptodatapi/news.py` & `cryptodatapi-1.0.6/cryptodatapi/news.py`

 * *Files identical despite different names*

### Comparing `cryptodatapi-1.0.5/cryptodatapi/spot.py` & `cryptodatapi-1.0.6/cryptodatapi/spot.py`

 * *Files identical despite different names*

### Comparing `cryptodatapi-1.0.5/cryptodatapi.egg-info/PKG-INFO` & `cryptodatapi-1.0.6/cryptodatapi.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: cryptodatapi
-Version: 1.0.5
+Version: 1.0.6
 Summary: Python SDK for integrating with Crypto API.
 Home-page: https://moatsystems.com/crypto-api/
 Author: Moat Systems Limited
 Author-email: support@moatsystems.com
 License: MIT
 Project-URL: Bug Tracker, https://github.com/moatsystems/cryptodatapi-py-sdk/issues
 Project-URL: Changes, https://github.com/moatsystems/cryptodatapi-py-sdk/blob/main/CHANGELOG.md
```

### Comparing `cryptodatapi-1.0.5/cryptodatapi.egg-info/SOURCES.txt` & `cryptodatapi-1.0.6/cryptodatapi.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `cryptodatapi-1.0.5/setup.py` & `cryptodatapi-1.0.6/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 # coding: utf-8
 
 import sys
 from setuptools import setup, find_packages  # noqa: H301
 from distutils.core import Extension
 
 NAME = "cryptodatapi"
-VERSION = "1.0.5"
+VERSION = "1.0.6"
 REQUIRES = ["requests"]
 
 # read the contents of your README file
 from os import path
 this_directory = path.abspath(path.dirname(__file__))
 with open(path.join(this_directory, 'LONG_DESCRIPTION.rst')) as f:
     long_description = f.read()
```

