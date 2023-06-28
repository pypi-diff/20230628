# Comparing `tmp/utilki-0.5.4.tar.gz` & `tmp/utilki-0.5.5.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "utilki-0.5.4.tar", max compression
+gzip compressed data, was "utilki-0.5.5.tar", max compression
```

## Comparing `utilki-0.5.4.tar` & `utilki-0.5.5.tar`

### file list

```diff
@@ -1,7 +1,7 @@
--rw-r--r--   0        0        0     1064 2023-06-28 14:54:53.382946 utilki-0.5.4/README.md
--rw-r--r--   0        0        0      525 2023-06-28 14:54:53.382946 utilki-0.5.4/pyproject.toml
--rw-r--r--   0        0        0      368 2023-06-28 14:54:53.382946 utilki-0.5.4/utilki/__init__.py
--rw-r--r--   0        0        0     2184 2023-06-28 14:54:53.382946 utilki-0.5.4/utilki/cli.py
--rw-r--r--   0        0        0     5868 2023-06-28 14:54:53.382946 utilki-0.5.4/utilki/log_utils.py
--rw-r--r--   0        0        0     7325 2023-06-28 14:54:53.382946 utilki-0.5.4/utilki/task_mixin.py
--rw-r--r--   0        0        0     1659 1970-01-01 00:00:00.000000 utilki-0.5.4/PKG-INFO
+-rw-r--r--   0        0        0     1064 2023-06-28 14:59:26.559605 utilki-0.5.5/README.md
+-rw-r--r--   0        0        0      525 2023-06-28 14:59:26.559605 utilki-0.5.5/pyproject.toml
+-rw-r--r--   0        0        0      368 2023-06-28 14:59:26.559605 utilki-0.5.5/utilki/__init__.py
+-rw-r--r--   0        0        0     2184 2023-06-28 14:59:26.559605 utilki-0.5.5/utilki/cli.py
+-rw-r--r--   0        0        0     5872 2023-06-28 14:59:26.559605 utilki-0.5.5/utilki/log_utils.py
+-rw-r--r--   0        0        0     7325 2023-06-28 14:59:26.559605 utilki-0.5.5/utilki/task_mixin.py
+-rw-r--r--   0        0        0     1659 1970-01-01 00:00:00.000000 utilki-0.5.5/PKG-INFO
```

### Comparing `utilki-0.5.4/README.md` & `utilki-0.5.5/README.md`

 * *Files identical despite different names*

### Comparing `utilki-0.5.4/pyproject.toml` & `utilki-0.5.5/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "utilki"
-version = "0.5.4"
+version = "0.5.5"
 description = "A collection of useful utilities"
 readme = "README.md"
 authors = ["Khaidar Bikmaev <khaidar@bikmaev.com>"]
 
 [tool.poetry.dependencies]
 python = ">=3.7"
 click = "^8.1.3"
```

### Comparing `utilki-0.5.4/utilki/cli.py` & `utilki-0.5.5/utilki/cli.py`

 * *Files identical despite different names*

### Comparing `utilki-0.5.4/utilki/log_utils.py` & `utilki-0.5.5/utilki/log_utils.py`

 * *Files 1% similar despite different names*

```diff
@@ -89,15 +89,15 @@
     globals()["_log_fn_level"] = level
 
 
 def _get_log_fn_level() -> int:
     try:
         log_fn_level = globals()["_log_fn_level"]
     except KeyError:
-        log_fn_level = logging.INFO
+        log_fn_level = logging.CRITICAL
     return log_fn_level
 
 
 def log(message: Any):
     message = str(message)
     logger = _get_logger()
     if_level(_get_log_fn_level(), message)
```

### Comparing `utilki-0.5.4/utilki/task_mixin.py` & `utilki-0.5.5/utilki/task_mixin.py`

 * *Files identical despite different names*

### Comparing `utilki-0.5.4/PKG-INFO` & `utilki-0.5.5/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: utilki
-Version: 0.5.4
+Version: 0.5.5
 Summary: A collection of useful utilities
 Author: Khaidar Bikmaev
 Author-email: khaidar@bikmaev.com
 Requires-Python: >=3.7
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
```

