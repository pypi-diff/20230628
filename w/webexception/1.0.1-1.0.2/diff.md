# Comparing `tmp/webexception-1.0.1.tar.gz` & `tmp/webexception-1.0.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "webexception-1.0.1.tar", max compression
+gzip compressed data, was "webexception-1.0.2.tar", max compression
```

## Comparing `webexception-1.0.1.tar` & `webexception-1.0.2.tar`

### file list

```diff
@@ -1,5 +1,5 @@
--rw-r--r--   0        0        0     6185 2023-06-20 15:11:48.458636 webexception-1.0.1/README.md
--rw-r--r--   0        0        0      566 2023-06-21 06:44:29.014826 webexception-1.0.1/pyproject.toml
--rw-r--r--   0        0        0        0 2023-06-20 15:13:03.845839 webexception-1.0.1/webexception/__init__.py
--rw-r--r--   0        0        0      664 2023-06-20 16:00:55.717895 webexception-1.0.1/webexception/webexception.py
--rw-r--r--   0        0        0     6478 1970-01-01 00:00:00.000000 webexception-1.0.1/PKG-INFO
+-rw-r--r--   0        0        0     6185 2023-06-20 15:11:48.458636 webexception-1.0.2/README.md
+-rw-r--r--   0        0        0      566 2023-06-28 12:06:13.302888 webexception-1.0.2/pyproject.toml
+-rw-r--r--   0        0        0        0 2023-06-20 15:13:03.845839 webexception-1.0.2/webexception/__init__.py
+-rw-r--r--   0        0        0      641 2023-06-28 12:05:58.818956 webexception-1.0.2/webexception/webexception.py
+-rw-r--r--   0        0        0     6478 1970-01-01 00:00:00.000000 webexception-1.0.2/PKG-INFO
```

### Comparing `webexception-1.0.1/README.md` & `webexception-1.0.2/README.md`

 * *Files identical despite different names*

### Comparing `webexception-1.0.1/pyproject.toml` & `webexception-1.0.2/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "webexception"
-version = "1.0.1"
+version = "1.0.2"
 description = ""
 authors = ["Marco Bartel <bsimpson888@gmail.com>"]
 readme = "README.md"
 
 [tool.poetry.dependencies]
 python = "^3.11"
```

### Comparing `webexception-1.0.1/webexception/webexception.py` & `webexception-1.0.2/webexception/webexception.py`

 * *Files 20% similar despite different names*

```diff
@@ -1,9 +1,8 @@
 import traceback
-from typing import Any
 
 
 class WebException(Exception):
     status_code: int = 500
 
     def __init__(self, *args: object, **kwargs) -> None:
         super().__init__(*args)
```

### Comparing `webexception-1.0.1/PKG-INFO` & `webexception-1.0.2/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: webexception
-Version: 1.0.1
+Version: 1.0.2
 Summary: 
 Author: Marco Bartel
 Author-email: bsimpson888@gmail.com
 Requires-Python: >=3.11,<4.0
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.11
 Description-Content-Type: text/markdown
```

