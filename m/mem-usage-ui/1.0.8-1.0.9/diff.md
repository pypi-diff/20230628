# Comparing `tmp/mem_usage_ui-1.0.8.tar.gz` & `tmp/mem_usage_ui-1.0.9.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "mem_usage_ui-1.0.8.tar", max compression
+gzip compressed data, was "mem_usage_ui-1.0.9.tar", max compression
```

## Comparing `mem_usage_ui-1.0.8.tar` & `mem_usage_ui-1.0.9.tar`

### file list

```diff
@@ -1,24 +1,23 @@
--rw-r--r--   0        0        0     1068 2019-04-03 19:13:20.001122 mem_usage_ui-1.0.8/LICENSE
--rw-r--r--   0        0        0     1100 2020-11-01 12:17:19.272035 mem_usage_ui-1.0.8/README.md
--rw-r--r--   0        0        0     6148 2020-12-30 13:33:14.726407 mem_usage_ui-1.0.8/mem_usage_ui/.DS_Store
--rw-r--r--   0        0        0      971 2023-06-28 10:19:39.873009 mem_usage_ui-1.0.8/mem_usage_ui/__init__.py
--rw-r--r--   0        0        0     1317 2023-06-28 10:57:30.254670 mem_usage_ui-1.0.8/mem_usage_ui/__main__.py
--rw-r--r--   0        0        0      280 2019-10-22 09:18:44.346026 mem_usage_ui-1.0.8/mem_usage_ui/routes.py
--rw-r--r--   0        0        0      168 2020-10-22 19:51:15.796053 mem_usage_ui-1.0.8/mem_usage_ui/settings.py
--rw-r--r--   0        0        0     6875 2023-06-28 10:55:37.117223 mem_usage_ui-1.0.8/mem_usage_ui/snapshot.py
--rw-r--r--   0        0        0     7019 2019-10-22 18:10:40.000000 mem_usage_ui-1.0.8/mem_usage_ui/static/img/android-chrome-192x192.png
--rw-r--r--   0        0        0    21392 2019-10-22 18:10:40.000000 mem_usage_ui-1.0.8/mem_usage_ui/static/img/android-chrome-512x512.png
--rw-r--r--   0        0        0     6625 2019-10-22 18:10:40.000000 mem_usage_ui-1.0.8/mem_usage_ui/static/img/apple-touch-icon.png
--rw-r--r--   0        0        0      370 2019-10-22 18:10:40.000000 mem_usage_ui-1.0.8/mem_usage_ui/static/img/favicon-16x16.png
--rw-r--r--   0        0        0      836 2019-10-22 18:10:40.000000 mem_usage_ui-1.0.8/mem_usage_ui/static/img/favicon-32x32.png
--rw-r--r--   0        0        0    15406 2019-10-22 18:10:40.000000 mem_usage_ui-1.0.8/mem_usage_ui/static/img/favicon.ico
--rw-r--r--   0        0        0      263 2019-10-22 18:10:40.000000 mem_usage_ui-1.0.8/mem_usage_ui/static/img/site.webmanifest
--rw-r--r--   0        0        0   580378 2020-11-04 17:36:00.403217 mem_usage_ui-1.0.8/mem_usage_ui/static/js/build.js
--rw-r--r--   0        0        0      261 2020-11-04 17:36:00.398720 mem_usage_ui-1.0.8/mem_usage_ui/static/js/build.js.LICENSE.txt
--rw-r--r--   0        0        0  2299812 2020-11-04 17:36:00.399614 mem_usage_ui-1.0.8/mem_usage_ui/static/js/build.js.map
--rw-r--r--   0        0        0      873 2019-10-22 21:11:59.530346 mem_usage_ui-1.0.8/mem_usage_ui/templates/index.html
--rw-r--r--   0        0        0        0 2019-01-08 18:49:06.897218 mem_usage_ui-1.0.8/mem_usage_ui/tests/__init__.py
--rw-r--r--   0        0        0     2001 2023-06-28 10:57:10.501278 mem_usage_ui-1.0.8/mem_usage_ui/tests/test_views.py
--rw-r--r--   0        0        0     1597 2020-10-22 19:51:15.800836 mem_usage_ui-1.0.8/mem_usage_ui/views.py
--rw-r--r--   0        0        0      658 2023-06-28 10:58:25.263967 mem_usage_ui-1.0.8/pyproject.toml
--rw-r--r--   0        0        0     1765 1970-01-01 00:00:00.000000 mem_usage_ui-1.0.8/PKG-INFO
+-rw-r--r--   0        0        0     1068 2023-06-28 11:10:22.780164 mem_usage_ui-1.0.9/LICENSE
+-rw-r--r--   0        0        0     1100 2023-06-28 11:10:22.780164 mem_usage_ui-1.0.9/README.md
+-rw-r--r--   0        0        0      971 2023-06-28 11:10:22.784171 mem_usage_ui-1.0.9/mem_usage_ui/__init__.py
+-rw-r--r--   0        0        0     1302 2023-06-28 11:10:22.784171 mem_usage_ui-1.0.9/mem_usage_ui/__main__.py
+-rw-r--r--   0        0        0      280 2023-06-28 11:10:22.784171 mem_usage_ui-1.0.9/mem_usage_ui/routes.py
+-rw-r--r--   0        0        0      168 2023-06-28 11:10:22.784171 mem_usage_ui-1.0.9/mem_usage_ui/settings.py
+-rw-r--r--   0        0        0     6875 2023-06-28 11:10:22.784171 mem_usage_ui-1.0.9/mem_usage_ui/snapshot.py
+-rw-r--r--   0        0        0     7019 2023-06-28 11:10:22.784171 mem_usage_ui-1.0.9/mem_usage_ui/static/img/android-chrome-192x192.png
+-rw-r--r--   0        0        0    21392 2023-06-28 11:10:22.784171 mem_usage_ui-1.0.9/mem_usage_ui/static/img/android-chrome-512x512.png
+-rw-r--r--   0        0        0     6625 2023-06-28 11:10:22.784171 mem_usage_ui-1.0.9/mem_usage_ui/static/img/apple-touch-icon.png
+-rw-r--r--   0        0        0      370 2023-06-28 11:10:22.784171 mem_usage_ui-1.0.9/mem_usage_ui/static/img/favicon-16x16.png
+-rw-r--r--   0        0        0      836 2023-06-28 11:10:22.784171 mem_usage_ui-1.0.9/mem_usage_ui/static/img/favicon-32x32.png
+-rw-r--r--   0        0        0    15406 2023-06-28 11:10:22.784171 mem_usage_ui-1.0.9/mem_usage_ui/static/img/favicon.ico
+-rw-r--r--   0        0        0      263 2023-06-28 11:10:22.784171 mem_usage_ui-1.0.9/mem_usage_ui/static/img/site.webmanifest
+-rw-r--r--   0        0        0   580378 2023-06-28 11:10:22.788178 mem_usage_ui-1.0.9/mem_usage_ui/static/js/build.js
+-rw-r--r--   0        0        0      261 2023-06-28 11:10:22.788178 mem_usage_ui-1.0.9/mem_usage_ui/static/js/build.js.LICENSE.txt
+-rw-r--r--   0        0        0  2299812 2023-06-28 11:10:22.804206 mem_usage_ui-1.0.9/mem_usage_ui/static/js/build.js.map
+-rw-r--r--   0        0        0      873 2023-06-28 11:10:22.804206 mem_usage_ui-1.0.9/mem_usage_ui/templates/index.html
+-rw-r--r--   0        0        0        0 2023-06-28 11:10:22.804206 mem_usage_ui-1.0.9/mem_usage_ui/tests/__init__.py
+-rw-r--r--   0        0        0     2001 2023-06-28 11:10:22.804206 mem_usage_ui-1.0.9/mem_usage_ui/tests/test_views.py
+-rw-r--r--   0        0        0     1597 2023-06-28 11:10:22.804206 mem_usage_ui-1.0.9/mem_usage_ui/views.py
+-rw-r--r--   0        0        0      657 2023-06-28 11:10:36.722583 mem_usage_ui-1.0.9/pyproject.toml
+-rw-r--r--   0        0        0     1765 1970-01-01 00:00:00.000000 mem_usage_ui-1.0.9/PKG-INFO
```

### Comparing `mem_usage_ui-1.0.8/LICENSE` & `mem_usage_ui-1.0.9/LICENSE`

 * *Files identical despite different names*

### Comparing `mem_usage_ui-1.0.8/README.md` & `mem_usage_ui-1.0.9/README.md`

 * *Files identical despite different names*

### Comparing `mem_usage_ui-1.0.8/mem_usage_ui/__init__.py` & `mem_usage_ui-1.0.9/mem_usage_ui/__init__.py`

 * *Files identical despite different names*

### Comparing `mem_usage_ui-1.0.8/mem_usage_ui/__main__.py` & `mem_usage_ui-1.0.9/mem_usage_ui/__main__.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,8 +1,7 @@
-import asyncio
 from argparse import ArgumentParser
 from typing import Optional, Any
 
 from aiohttp import web
 
 from mem_usage_ui.routes import setup_routes
 from mem_usage_ui.snapshot import SnapshotProcessor
```

### Comparing `mem_usage_ui-1.0.8/mem_usage_ui/snapshot.py` & `mem_usage_ui-1.0.9/mem_usage_ui/snapshot.py`

 * *Files identical despite different names*

### Comparing `mem_usage_ui-1.0.8/mem_usage_ui/static/img/android-chrome-192x192.png` & `mem_usage_ui-1.0.9/mem_usage_ui/static/img/android-chrome-192x192.png`

 * *Files identical despite different names*

### Comparing `mem_usage_ui-1.0.8/mem_usage_ui/static/img/android-chrome-512x512.png` & `mem_usage_ui-1.0.9/mem_usage_ui/static/img/android-chrome-512x512.png`

 * *Files identical despite different names*

### Comparing `mem_usage_ui-1.0.8/mem_usage_ui/static/img/apple-touch-icon.png` & `mem_usage_ui-1.0.9/mem_usage_ui/static/img/apple-touch-icon.png`

 * *Files identical despite different names*

### Comparing `mem_usage_ui-1.0.8/mem_usage_ui/static/img/favicon-32x32.png` & `mem_usage_ui-1.0.9/mem_usage_ui/static/img/favicon-32x32.png`

 * *Files identical despite different names*

### Comparing `mem_usage_ui-1.0.8/mem_usage_ui/static/img/favicon.ico` & `mem_usage_ui-1.0.9/mem_usage_ui/static/img/favicon.ico`

 * *Files identical despite different names*

### Comparing `mem_usage_ui-1.0.8/mem_usage_ui/static/js/build.js` & `mem_usage_ui-1.0.9/mem_usage_ui/static/js/build.js`

 * *Files identical despite different names*

### Comparing `mem_usage_ui-1.0.8/mem_usage_ui/static/js/build.js.map` & `mem_usage_ui-1.0.9/mem_usage_ui/static/js/build.js.map`

 * *Files identical despite different names*

### Comparing `mem_usage_ui-1.0.8/mem_usage_ui/templates/index.html` & `mem_usage_ui-1.0.9/mem_usage_ui/templates/index.html`

 * *Files identical despite different names*

### Comparing `mem_usage_ui-1.0.8/mem_usage_ui/tests/test_views.py` & `mem_usage_ui-1.0.9/mem_usage_ui/tests/test_views.py`

 * *Files identical despite different names*

### Comparing `mem_usage_ui-1.0.8/mem_usage_ui/views.py` & `mem_usage_ui-1.0.9/mem_usage_ui/views.py`

 * *Files identical despite different names*

### Comparing `mem_usage_ui-1.0.8/pyproject.toml` & `mem_usage_ui-1.0.9/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "mem-usage-ui"
-version = "1.0.8"
+version = "1.0.9"
 description = "Measuring and graphing memory usage of local processes"
 authors = ["Dmytro Smyk <porovozls@gmail.com>"]
 license = "MIT"
 readme = "README.md"
 packages = [{include = "mem_usage_ui"}]
 include = ['templates/index.html', 'static/js/build.js', 'static/img/*']
 
@@ -18,11 +18,10 @@
 
 [tool.poetry.group.tests]
 optional = true
 
 [tool.poetry.group.tests.dependencies]
 pytest = ">=5,<7"
 
-
 [build-system]
 requires = ["poetry-core"]
 build-backend = "poetry.core.masonry.api"
```

### Comparing `mem_usage_ui-1.0.8/PKG-INFO` & `mem_usage_ui-1.0.9/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: mem-usage-ui
-Version: 1.0.8
+Version: 1.0.9
 Summary: Measuring and graphing memory usage of local processes
 License: MIT
 Author: Dmytro Smyk
 Author-email: porovozls@gmail.com
 Requires-Python: >=3.7,<4
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python :: 3
```

