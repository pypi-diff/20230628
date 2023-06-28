# Comparing `tmp/robocorp_browser-1.0.1.tar.gz` & `tmp/robocorp_browser-1.0.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "robocorp_browser-1.0.1.tar", max compression
+gzip compressed data, was "robocorp_browser-1.0.2.tar", max compression
```

## Comparing `robocorp_browser-1.0.1.tar` & `robocorp_browser-1.0.2.tar`

### file list

```diff
@@ -1,9 +1,9 @@
--rw-r--r--   0        0        0     1583 2023-06-13 15:07:28.840150 robocorp_browser-1.0.1/README.md
--rw-r--r--   0        0        0      636 2023-06-13 15:07:28.844150 robocorp_browser-1.0.1/pyproject.toml
--rw-r--r--   0        0        0     6289 2023-06-13 15:07:28.844150 robocorp_browser-1.0.1/src/robocorp/browser/__init__.py
--rw-r--r--   0        0        0       81 2023-06-13 15:07:28.844150 robocorp_browser-1.0.1/src/robocorp/browser/__main__.py
--rw-r--r--   0        0        0     6725 2023-06-13 15:07:28.844150 robocorp_browser-1.0.1/src/robocorp/browser/_browser_context.py
--rw-r--r--   0        0        0     1890 2023-06-13 15:07:28.844150 robocorp_browser-1.0.1/src/robocorp/browser/_browser_engines.py
--rw-r--r--   0        0        0      825 2023-06-13 15:07:28.844150 robocorp_browser-1.0.1/src/robocorp/browser/cli.py
--rw-r--r--   0        0        0        0 2023-06-13 15:07:28.844150 robocorp_browser-1.0.1/src/robocorp/browser/py.typed
--rw-r--r--   0        0        0     2091 1970-01-01 00:00:00.000000 robocorp_browser-1.0.1/PKG-INFO
+-rw-r--r--   0        0        0     1583 2023-06-28 14:28:15.580296 robocorp_browser-1.0.2/README.md
+-rw-r--r--   0        0        0      712 2023-06-28 14:28:15.580296 robocorp_browser-1.0.2/pyproject.toml
+-rw-r--r--   0        0        0     6318 2023-06-28 14:28:15.580296 robocorp_browser-1.0.2/src/robocorp/browser/__init__.py
+-rw-r--r--   0        0        0       81 2023-06-28 14:28:15.580296 robocorp_browser-1.0.2/src/robocorp/browser/__main__.py
+-rw-r--r--   0        0        0     6725 2023-06-28 14:28:15.580296 robocorp_browser-1.0.2/src/robocorp/browser/_browser_context.py
+-rw-r--r--   0        0        0     1890 2023-06-28 14:28:15.580296 robocorp_browser-1.0.2/src/robocorp/browser/_browser_engines.py
+-rw-r--r--   0        0        0      825 2023-06-28 14:28:15.580296 robocorp_browser-1.0.2/src/robocorp/browser/cli.py
+-rw-r--r--   0        0        0        0 2023-06-28 14:28:15.580296 robocorp_browser-1.0.2/src/robocorp/browser/py.typed
+-rw-r--r--   0        0        0     2278 1970-01-01 00:00:00.000000 robocorp_browser-1.0.2/PKG-INFO
```

### Comparing `robocorp_browser-1.0.1/README.md` & `robocorp_browser-1.0.2/README.md`

 * *Files identical despite different names*

### Comparing `robocorp_browser-1.0.1/pyproject.toml` & `robocorp_browser-1.0.2/pyproject.toml`

 * *Files 24% similar despite different names*

```diff
@@ -1,23 +1,25 @@
 [tool.poetry]
 name = "robocorp-browser"
-version = "1.0.1"
+version = "1.0.2"
 description = "Robocorp browser automation library"
 authors = [
 	"Fabio Z. <fabio@robocorp.com>",
 	"Kerkko P. <kerkko@robocorp.com>",
 	"Ossi R. <ossi@robocorp.com>",
 ]
 readme = "README.md"
+repository = "https://github.com/robocorp/robo/"
+license = "Apache-2.0"
 packages = [{include = "robocorp", from="src"}]
 
 [tool.poetry.dependencies]
 python = "^3.9"
 playwright = "^1.32.1"
-robocorp-tasks = "^1"
+robocorp-tasks = ">=1,<3"
 
 [tool.poetry.group.dev.dependencies]
 robocorp-devutils = {path = "../devutils/", develop = true}
 
 [build-system]
 requires = ["poetry-core"]
 build-backend = "poetry.core.masonry.api"
```

### Comparing `robocorp_browser-1.0.1/src/robocorp/browser/__init__.py` & `robocorp_browser-1.0.2/src/robocorp/browser/__init__.py`

 * *Files 1% similar despite different names*

```diff
@@ -7,15 +7,15 @@
     Locator,
     Page,
     Playwright,
 )
 
 from ._browser_engines import BrowserEngine
 
-__version__ = "1.0.1"
+__version__ = "1.0.2"
 version_info = [int(x) for x in __version__.split(".")]
 
 
 def configure(**kwargs) -> None:
     """
     May be called before any other method to configure the browser settings.
 
@@ -184,15 +184,16 @@
         in_bytes = element.screenshot(timeout=timeout, type=image_type)
         in_base64 = base64.b64encode(in_bytes).decode("ascii")
 
     log.html(
         f'<img src="data:image/{image_type};base64,{in_base64}"/>', level=log_level
     )
 
-    return in_bytes
+    with log.suppress():
+        return in_bytes
 
 
 def install(browser_engine: BrowserEngine):
     """
     Downloads and installs the given browser engine.
 
     Note: Google Chrome or Microsoft Edge installations will be installed
```

### Comparing `robocorp_browser-1.0.1/src/robocorp/browser/_browser_context.py` & `robocorp_browser-1.0.2/src/robocorp/browser/_browser_context.py`

 * *Files identical despite different names*

### Comparing `robocorp_browser-1.0.1/src/robocorp/browser/_browser_engines.py` & `robocorp_browser-1.0.2/src/robocorp/browser/_browser_engines.py`

 * *Files identical despite different names*

### Comparing `robocorp_browser-1.0.1/src/robocorp/browser/cli.py` & `robocorp_browser-1.0.2/src/robocorp/browser/cli.py`

 * *Files identical despite different names*

### Comparing `robocorp_browser-1.0.1/PKG-INFO` & `robocorp_browser-1.0.2/PKG-INFO`

 * *Files 12% similar despite different names*

```diff
@@ -1,20 +1,24 @@
 Metadata-Version: 2.1
 Name: robocorp-browser
-Version: 1.0.1
+Version: 1.0.2
 Summary: Robocorp browser automation library
+Home-page: https://github.com/robocorp/robo/
+License: Apache-2.0
 Author: Fabio Z.
 Author-email: fabio@robocorp.com
 Requires-Python: >=3.9,<4.0
+Classifier: License :: OSI Approved :: Apache Software License
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
 Requires-Dist: playwright (>=1.32.1,<2.0.0)
-Requires-Dist: robocorp-tasks (>=1,<2)
+Requires-Dist: robocorp-tasks (>=1,<3)
+Project-URL: Repository, https://github.com/robocorp/robo/
 Description-Content-Type: text/markdown
 
 # Robocorp browser library
 
 The `robocorp-browser` library helps in automating browsers by providing 
 convenient APIs to manage the lifecycle of playwright objects using `robocorp-tasks`.
```

