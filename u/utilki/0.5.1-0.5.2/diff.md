# Comparing `tmp/utilki-0.5.1.tar.gz` & `tmp/utilki-0.5.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "utilki-0.5.1.tar", max compression
+gzip compressed data, was "utilki-0.5.2.tar", max compression
```

## Comparing `utilki-0.5.1.tar` & `utilki-0.5.2.tar`

### file list

```diff
@@ -1,7 +1,7 @@
--rw-r--r--   0        0        0     1064 2023-06-27 14:34:10.017912 utilki-0.5.1/README.md
--rw-r--r--   0        0        0      525 2023-06-27 14:34:10.017912 utilki-0.5.1/pyproject.toml
--rw-r--r--   0        0        0      269 2023-06-27 14:34:10.017912 utilki-0.5.1/utilki/__init__.py
--rw-r--r--   0        0        0     2184 2023-06-27 14:34:10.017912 utilki-0.5.1/utilki/cli.py
--rw-r--r--   0        0        0     5273 2023-06-27 14:34:10.017912 utilki-0.5.1/utilki/log_utils.py
--rw-r--r--   0        0        0     7325 2023-06-27 14:34:10.017912 utilki-0.5.1/utilki/task_mixin.py
--rw-r--r--   0        0        0     1659 1970-01-01 00:00:00.000000 utilki-0.5.1/PKG-INFO
+-rw-r--r--   0        0        0     1064 2023-06-28 14:33:35.758064 utilki-0.5.2/README.md
+-rw-r--r--   0        0        0      525 2023-06-28 14:33:35.758064 utilki-0.5.2/pyproject.toml
+-rw-r--r--   0        0        0      269 2023-06-28 14:33:35.758064 utilki-0.5.2/utilki/__init__.py
+-rw-r--r--   0        0        0     2184 2023-06-28 14:33:35.758064 utilki-0.5.2/utilki/cli.py
+-rw-r--r--   0        0        0     5346 2023-06-28 14:33:35.758064 utilki-0.5.2/utilki/log_utils.py
+-rw-r--r--   0        0        0     7325 2023-06-28 14:33:35.758064 utilki-0.5.2/utilki/task_mixin.py
+-rw-r--r--   0        0        0     1659 1970-01-01 00:00:00.000000 utilki-0.5.2/PKG-INFO
```

### Comparing `utilki-0.5.1/README.md` & `utilki-0.5.2/README.md`

 * *Files identical despite different names*

### Comparing `utilki-0.5.1/pyproject.toml` & `utilki-0.5.2/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "utilki"
-version = "0.5.1"
+version = "0.5.2"
 description = "A collection of useful utilities"
 readme = "README.md"
 authors = ["Khaidar Bikmaev <khaidar@bikmaev.com>"]
 
 [tool.poetry.dependencies]
 python = ">=3.7"
 click = "^8.1.3"
```

### Comparing `utilki-0.5.1/utilki/cli.py` & `utilki-0.5.2/utilki/cli.py`

 * *Files identical despite different names*

### Comparing `utilki-0.5.1/utilki/log_utils.py` & `utilki-0.5.2/utilki/log_utils.py`

 * *Files 2% similar despite different names*

```diff
@@ -99,19 +99,20 @@
 def err(message: Any):
     message = str(message)
     logger = _get_logger()
     if_level(logging.ERROR, message)
     logger.error(message)
 
 
-def basic_config():
+def basic_config(level=logging.CRITICAL):
     logging.basicConfig(
         format="%(asctime)s %(levelname)s %(message)s",
         datefmt="%Y-%m-%d %H:%M:%S",
-        level=logging.DEBUG,
+        # NB: this is the default level of the root logger
+        level=level,
         stream=sys.stdout,
     )
 
 
 A = TypeVar("A")
```

### Comparing `utilki-0.5.1/utilki/task_mixin.py` & `utilki-0.5.2/utilki/task_mixin.py`

 * *Files identical despite different names*

### Comparing `utilki-0.5.1/PKG-INFO` & `utilki-0.5.2/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: utilki
-Version: 0.5.1
+Version: 0.5.2
 Summary: A collection of useful utilities
 Author: Khaidar Bikmaev
 Author-email: khaidar@bikmaev.com
 Requires-Python: >=3.7
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
```

