# Comparing `tmp/mem_usage_ui-1.0.6.tar.gz` & `tmp/mem_usage_ui-1.0.7.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/mem_usage_ui-1.0.6.tar", last modified: Thu May 27 13:32:17 2021, max compression
+gzip compressed data, was "mem_usage_ui-1.0.7.tar", max compression
```

## Comparing `mem_usage_ui-1.0.6.tar` & `mem_usage_ui-1.0.7.tar`

### file list

```diff
@@ -1,27 +1,24 @@
-drwxrwxr-x   0 travis    (2000) travis    (2000)        0 2021-05-27 13:32:17.000000 mem_usage_ui-1.0.6/
--rw-rw-r--   0 travis    (2000) travis    (2000)     3351 2021-05-27 13:31:56.000000 mem_usage_ui-1.0.6/CODE_OF_CONDUCT.md
--rw-rw-r--   0 travis    (2000) travis    (2000)      413 2021-05-27 13:31:56.000000 mem_usage_ui-1.0.6/CONTRIBUTING.md
--rw-rw-r--   0 travis    (2000) travis    (2000)     2006 2021-05-27 13:32:17.000000 mem_usage_ui-1.0.6/PKG-INFO
--rw-rw-r--   0 travis    (2000) travis    (2000)     1100 2021-05-27 13:31:56.000000 mem_usage_ui-1.0.6/README.md
-drwxrwxr-x   0 travis    (2000) travis    (2000)        0 2021-05-27 13:32:17.000000 mem_usage_ui-1.0.6/mem_usage_ui/
--rw-rw-r--   0 travis    (2000) travis    (2000)     1003 2021-05-27 13:31:56.000000 mem_usage_ui-1.0.6/mem_usage_ui/__init__.py
--rw-rw-r--   0 travis    (2000) travis    (2000)     1312 2021-05-27 13:31:56.000000 mem_usage_ui-1.0.6/mem_usage_ui/__main__.py
--rw-rw-r--   0 travis    (2000) travis    (2000)      280 2021-05-27 13:31:56.000000 mem_usage_ui-1.0.6/mem_usage_ui/routes.py
--rw-rw-r--   0 travis    (2000) travis    (2000)      168 2021-05-27 13:31:56.000000 mem_usage_ui-1.0.6/mem_usage_ui/settings.py
--rw-rw-r--   0 travis    (2000) travis    (2000)     6720 2021-05-27 13:31:56.000000 mem_usage_ui-1.0.6/mem_usage_ui/snapshot.py
-drwxrwxr-x   0 travis    (2000) travis    (2000)        0 2021-05-27 13:32:17.000000 mem_usage_ui-1.0.6/mem_usage_ui/static/
-drwxrwxr-x   0 travis    (2000) travis    (2000)        0 2021-05-27 13:32:17.000000 mem_usage_ui-1.0.6/mem_usage_ui/static/img/
--rw-rw-r--   0 travis    (2000) travis    (2000)     7019 2021-05-27 13:31:56.000000 mem_usage_ui-1.0.6/mem_usage_ui/static/img/android-chrome-192x192.png
--rw-rw-r--   0 travis    (2000) travis    (2000)    21392 2021-05-27 13:31:56.000000 mem_usage_ui-1.0.6/mem_usage_ui/static/img/android-chrome-512x512.png
--rw-rw-r--   0 travis    (2000) travis    (2000)     6625 2021-05-27 13:31:56.000000 mem_usage_ui-1.0.6/mem_usage_ui/static/img/apple-touch-icon.png
--rw-rw-r--   0 travis    (2000) travis    (2000)      370 2021-05-27 13:31:56.000000 mem_usage_ui-1.0.6/mem_usage_ui/static/img/favicon-16x16.png
--rw-rw-r--   0 travis    (2000) travis    (2000)      836 2021-05-27 13:31:56.000000 mem_usage_ui-1.0.6/mem_usage_ui/static/img/favicon-32x32.png
--rw-rw-r--   0 travis    (2000) travis    (2000)    15406 2021-05-27 13:31:56.000000 mem_usage_ui-1.0.6/mem_usage_ui/static/img/favicon.ico
--rw-rw-r--   0 travis    (2000) travis    (2000)      263 2021-05-27 13:31:56.000000 mem_usage_ui-1.0.6/mem_usage_ui/static/img/site.webmanifest
-drwxrwxr-x   0 travis    (2000) travis    (2000)        0 2021-05-27 13:32:17.000000 mem_usage_ui-1.0.6/mem_usage_ui/static/js/
--rw-rw-r--   0 travis    (2000) travis    (2000)   580378 2021-05-27 13:31:56.000000 mem_usage_ui-1.0.6/mem_usage_ui/static/js/build.js
-drwxrwxr-x   0 travis    (2000) travis    (2000)        0 2021-05-27 13:32:17.000000 mem_usage_ui-1.0.6/mem_usage_ui/templates/
--rw-rw-r--   0 travis    (2000) travis    (2000)      873 2021-05-27 13:31:56.000000 mem_usage_ui-1.0.6/mem_usage_ui/templates/index.html
--rw-rw-r--   0 travis    (2000) travis    (2000)     1597 2021-05-27 13:31:56.000000 mem_usage_ui-1.0.6/mem_usage_ui/views.py
--rw-rw-r--   0 travis    (2000) travis    (2000)      196 2021-05-27 13:31:56.000000 mem_usage_ui-1.0.6/requirements.txt
--rw-rw-r--   0 travis    (2000) travis    (2000)     1544 2021-05-27 13:31:56.000000 mem_usage_ui-1.0.6/setup.py
+-rw-r--r--   0        0        0     1068 2019-04-03 19:13:20.001122 mem_usage_ui-1.0.7/LICENSE
+-rw-r--r--   0        0        0     1100 2020-11-01 12:17:19.272035 mem_usage_ui-1.0.7/README.md
+-rw-r--r--   0        0        0     6148 2020-12-30 13:33:14.726407 mem_usage_ui-1.0.7/mem_usage_ui/.DS_Store
+-rw-r--r--   0        0        0      971 2023-06-28 10:19:39.873009 mem_usage_ui-1.0.7/mem_usage_ui/__init__.py
+-rw-r--r--   0        0        0     1312 2021-05-27 13:16:28.991229 mem_usage_ui-1.0.7/mem_usage_ui/__main__.py
+-rw-r--r--   0        0        0      280 2019-10-22 09:18:44.346026 mem_usage_ui-1.0.7/mem_usage_ui/routes.py
+-rw-r--r--   0        0        0      168 2020-10-22 19:51:15.796053 mem_usage_ui-1.0.7/mem_usage_ui/settings.py
+-rw-r--r--   0        0        0     6720 2021-05-27 13:16:28.992857 mem_usage_ui-1.0.7/mem_usage_ui/snapshot.py
+-rw-r--r--   0        0        0     7019 2019-10-22 18:10:40.000000 mem_usage_ui-1.0.7/mem_usage_ui/static/img/android-chrome-192x192.png
+-rw-r--r--   0        0        0    21392 2019-10-22 18:10:40.000000 mem_usage_ui-1.0.7/mem_usage_ui/static/img/android-chrome-512x512.png
+-rw-r--r--   0        0        0     6625 2019-10-22 18:10:40.000000 mem_usage_ui-1.0.7/mem_usage_ui/static/img/apple-touch-icon.png
+-rw-r--r--   0        0        0      370 2019-10-22 18:10:40.000000 mem_usage_ui-1.0.7/mem_usage_ui/static/img/favicon-16x16.png
+-rw-r--r--   0        0        0      836 2019-10-22 18:10:40.000000 mem_usage_ui-1.0.7/mem_usage_ui/static/img/favicon-32x32.png
+-rw-r--r--   0        0        0    15406 2019-10-22 18:10:40.000000 mem_usage_ui-1.0.7/mem_usage_ui/static/img/favicon.ico
+-rw-r--r--   0        0        0      263 2019-10-22 18:10:40.000000 mem_usage_ui-1.0.7/mem_usage_ui/static/img/site.webmanifest
+-rw-r--r--   0        0        0   580378 2020-11-04 17:36:00.403217 mem_usage_ui-1.0.7/mem_usage_ui/static/js/build.js
+-rw-r--r--   0        0        0      261 2020-11-04 17:36:00.398720 mem_usage_ui-1.0.7/mem_usage_ui/static/js/build.js.LICENSE.txt
+-rw-r--r--   0        0        0  2299812 2020-11-04 17:36:00.399614 mem_usage_ui-1.0.7/mem_usage_ui/static/js/build.js.map
+-rw-r--r--   0        0        0      873 2019-10-22 21:11:59.530346 mem_usage_ui-1.0.7/mem_usage_ui/templates/index.html
+-rw-r--r--   0        0        0        0 2019-01-08 18:49:06.897218 mem_usage_ui-1.0.7/mem_usage_ui/tests/__init__.py
+-rw-r--r--   0        0        0     2034 2019-05-02 10:03:42.059823 mem_usage_ui-1.0.7/mem_usage_ui/tests/test_views.py
+-rw-r--r--   0        0        0     1597 2020-10-22 19:51:15.800836 mem_usage_ui-1.0.7/mem_usage_ui/views.py
+-rw-r--r--   0        0        0      660 2023-06-28 10:34:23.080776 mem_usage_ui-1.0.7/pyproject.toml
+-rw-r--r--   0        0        0     1817 1970-01-01 00:00:00.000000 mem_usage_ui-1.0.7/PKG-INFO
```

### filetype from file(1)

```diff
@@ -1 +1 @@
-POSIX tar archive (GNU)
+POSIX tar archive
```

### Comparing `mem_usage_ui-1.0.6/PKG-INFO` & `mem_usage_ui-1.0.7/PKG-INFO`

 * *Files 15% similar despite different names*

```diff
@@ -1,49 +1,52 @@
-Metadata-Version: 1.1
-Name: mem_usage_ui
-Version: 1.0.6
+Metadata-Version: 2.1
+Name: mem-usage-ui
+Version: 1.0.7
 Summary: Measuring and graphing memory usage of local processes
-Home-page: https://github.com/parikls/mem_usage_ui
+License: MIT
 Author: Dmytro Smyk
 Author-email: porovozls@gmail.com
-License: UNKNOWN
-Description: mem-usage-ui
-        ============
-        
-        - [![Build Status](https://travis-ci.org/parikls/mem_usage_ui.svg?branch=master)](https://travis-ci.org/parikls/mem_usage_ui) [![PyPI version](https://badge.fury.io/py/mem-usage-ui.svg)](https://badge.fury.io/py/mem-usage-ui) ![PyPI - Python Version](https://img.shields.io/pypi/pyversions/mem_usage_ui.svg)
-        - ![GitHub stars](https://img.shields.io/github/stars/parikls/mem_usage_ui.svg) ![PyPI - Downloads](https://img.shields.io/pypi/dm/mem_usage_ui.svg) ![GitHub issues](https://img.shields.io/github/issues/parikls/mem_usage_ui.svg)
-        
-        
-        ![alt text](https://raw.githubusercontent.com/parikls/mem_usage_ui/master/mem_usage_ui.png)
-        
-        Description
-        ===========
-        
-        - Measuring and graphing memory usage of local processes
-        - Supported python versions are `3.5+`
-        
-        Installation
-        ============
-        
-        - `pip install mem_usage_ui`
-        
-        Usage
-        =====
-        
-        - Run in shell: `mem_usage_ui`
-        - Default browser will be opened automatically
-        - Running on `http://localhost:8080`
-        
-        Possible Command Line Arguments
-        ===============================
-        
-        - `--host` - defaults to `localhost`
-        - `--port` - defaults to `8080`
-Platform: UNKNOWN
-Classifier: Operating System :: OS Independent
-Classifier: Intended Audience :: Developers
-Classifier: Programming Language :: Python
-Classifier: Programming Language :: Python :: 3.5
+Requires-Python: >=3.5.3,<4
+Classifier: License :: OSI Approved :: MIT License
+Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.6
 Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
+Classifier: Programming Language :: Python :: 3.10
+Classifier: Programming Language :: Python :: 3.11
+Requires-Dist: aiohttp (>=3,<5)
+Requires-Dist: psutil (<6)
+Description-Content-Type: text/markdown
+
+mem-usage-ui
+============
+
+- [![Build Status](https://travis-ci.org/parikls/mem_usage_ui.svg?branch=master)](https://travis-ci.org/parikls/mem_usage_ui) [![PyPI version](https://badge.fury.io/py/mem-usage-ui.svg)](https://badge.fury.io/py/mem-usage-ui) ![PyPI - Python Version](https://img.shields.io/pypi/pyversions/mem_usage_ui.svg)
+- ![GitHub stars](https://img.shields.io/github/stars/parikls/mem_usage_ui.svg) ![PyPI - Downloads](https://img.shields.io/pypi/dm/mem_usage_ui.svg) ![GitHub issues](https://img.shields.io/github/issues/parikls/mem_usage_ui.svg)
+
+
+![alt text](https://raw.githubusercontent.com/parikls/mem_usage_ui/master/mem_usage_ui.png)
+
+Description
+===========
+
+- Measuring and graphing memory usage of local processes
+- Supported python versions are `3.5+`
+
+Installation
+============
+
+- `pip install mem_usage_ui`
+
+Usage
+=====
+
+- Run in shell: `mem_usage_ui`
+- Default browser will be opened automatically
+- Running on `http://localhost:8080`
+
+Possible Command Line Arguments
+===============================
+
+- `--host` - defaults to `localhost`
+- `--port` - defaults to `8080`
```

### Comparing `mem_usage_ui-1.0.6/README.md` & `mem_usage_ui-1.0.7/README.md`

 * *Files identical despite different names*

### Comparing `mem_usage_ui-1.0.6/mem_usage_ui/__init__.py` & `mem_usage_ui-1.0.7/mem_usage_ui/__init__.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,14 +1,11 @@
 import asyncio
 import sys
 from logging.config import dictConfig
 
-import uvloop
-
-uvloop.install()
 
 _py_version = (sys.version_info.major, sys.version_info.minor)
 __version__ = '1.0.6'
 
 if _py_version < (3, 5):
     raise RuntimeError("Python versions prior to 3.5 are not supported")
```

### Comparing `mem_usage_ui-1.0.6/mem_usage_ui/__main__.py` & `mem_usage_ui-1.0.7/mem_usage_ui/__main__.py`

 * *Files identical despite different names*

### Comparing `mem_usage_ui-1.0.6/mem_usage_ui/snapshot.py` & `mem_usage_ui-1.0.7/mem_usage_ui/snapshot.py`

 * *Files identical despite different names*

### Comparing `mem_usage_ui-1.0.6/mem_usage_ui/static/img/android-chrome-192x192.png` & `mem_usage_ui-1.0.7/mem_usage_ui/static/img/android-chrome-192x192.png`

 * *Files identical despite different names*

### Comparing `mem_usage_ui-1.0.6/mem_usage_ui/static/img/android-chrome-512x512.png` & `mem_usage_ui-1.0.7/mem_usage_ui/static/img/android-chrome-512x512.png`

 * *Files identical despite different names*

### Comparing `mem_usage_ui-1.0.6/mem_usage_ui/static/img/apple-touch-icon.png` & `mem_usage_ui-1.0.7/mem_usage_ui/static/img/apple-touch-icon.png`

 * *Files identical despite different names*

### Comparing `mem_usage_ui-1.0.6/mem_usage_ui/static/img/favicon-32x32.png` & `mem_usage_ui-1.0.7/mem_usage_ui/static/img/favicon-32x32.png`

 * *Files identical despite different names*

### Comparing `mem_usage_ui-1.0.6/mem_usage_ui/static/img/favicon.ico` & `mem_usage_ui-1.0.7/mem_usage_ui/static/img/favicon.ico`

 * *Files identical despite different names*

### Comparing `mem_usage_ui-1.0.6/mem_usage_ui/static/js/build.js` & `mem_usage_ui-1.0.7/mem_usage_ui/static/js/build.js`

 * *Files identical despite different names*

### Comparing `mem_usage_ui-1.0.6/mem_usage_ui/templates/index.html` & `mem_usage_ui-1.0.7/mem_usage_ui/templates/index.html`

 * *Files identical despite different names*

### Comparing `mem_usage_ui-1.0.6/mem_usage_ui/views.py` & `mem_usage_ui-1.0.7/mem_usage_ui/views.py`

 * *Files identical despite different names*

