# Comparing `tmp/pyhelpers_daevski-0.3.0.tar.gz` & `tmp/pyhelpers_daevski-0.3.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pyhelpers_daevski-0.3.0.tar", max compression
+gzip compressed data, was "pyhelpers_daevski-0.3.1.tar", max compression
```

## Comparing `pyhelpers_daevski-0.3.0.tar` & `pyhelpers_daevski-0.3.1.tar`

### file list

```diff
@@ -1,6 +1,6 @@
--rw-r--r--   0        0        0     1660 2023-03-31 03:44:40.245871 pyhelpers_daevski-0.3.0/pyhelpers_daevski/__init__.py
--rw-r--r--   0        0        0      652 2023-01-03 18:23:53.000000 pyhelpers_daevski-0.3.0/pyhelpers_daevski/QuickCommand.py
--rw-r--r--   0        0        0     5327 2023-03-31 03:44:40.248872 pyhelpers_daevski-0.3.0/pyhelpers_daevski/security.py
--rw-r--r--   0        0        0      613 2023-03-31 03:44:40.252382 pyhelpers_daevski-0.3.0/pyproject.toml
--rw-r--r--   0        0        0       62 2023-01-04 17:55:12.912883 pyhelpers_daevski-0.3.0/README.md
--rw-r--r--   0        0        0      607 1970-01-01 00:00:00.000000 pyhelpers_daevski-0.3.0/PKG-INFO
+-rw-r--r--   0        0        0     1814 2023-06-28 15:31:35.680973 pyhelpers_daevski-0.3.1/pyhelpers_daevski/__init__.py
+-rw-r--r--   0        0        0      652 2023-01-03 18:23:53.000000 pyhelpers_daevski-0.3.1/pyhelpers_daevski/QuickCommand.py
+-rw-r--r--   0        0        0     5327 2023-03-31 03:44:40.248872 pyhelpers_daevski-0.3.1/pyhelpers_daevski/security.py
+-rw-r--r--   0        0        0      613 2023-06-28 15:42:15.486333 pyhelpers_daevski-0.3.1/pyproject.toml
+-rw-r--r--   0        0        0       62 2023-01-04 17:55:12.912883 pyhelpers_daevski-0.3.1/README.md
+-rw-r--r--   0        0        0      607 1970-01-01 00:00:00.000000 pyhelpers_daevski-0.3.1/PKG-INFO
```

### Comparing `pyhelpers_daevski-0.3.0/pyhelpers_daevski/__init__.py` & `pyhelpers_daevski-0.3.1/pyhelpers_daevski/__init__.py`

 * *Files 7% similar despite different names*

```diff
@@ -15,14 +15,19 @@
 
 
 def get_configuration(config_file: Path):
     with config_file.open() as f:
         return yaml.safe_load(f)
 
 
+def set_configuration(configuration: dict, config_file: Path):
+    with config_file.open("w") as f:
+        f.write(yaml.safe_dump(configuration))
+
+
 def get_logger(
     appconfig: dict[Any, Any],
     logging_level: int = logging.INFO,
     format: str = "[%Y-%m-%d] [%H:%M]",
     configkey_logdir: str = "LoggingDirectory",
 ):
     location = (
```

### Comparing `pyhelpers_daevski-0.3.0/pyhelpers_daevski/QuickCommand.py` & `pyhelpers_daevski-0.3.1/pyhelpers_daevski/QuickCommand.py`

 * *Files identical despite different names*

### Comparing `pyhelpers_daevski-0.3.0/pyhelpers_daevski/security.py` & `pyhelpers_daevski-0.3.1/pyhelpers_daevski/security.py`

 * *Files identical despite different names*

### Comparing `pyhelpers_daevski-0.3.0/pyproject.toml` & `pyhelpers_daevski-0.3.1/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "pyhelpers-daevski"
-version = "0.3.0"
+version = "0.3.1"
 description = "helper functions for personal use"
 authors = ["David Mckee <daevski@gmail.com>"]
 readme = "README.md"
 packages = [{include = "pyhelpers_daevski"}]
 
 [tool.poetry.dependencies]
 python = "^3.9"
```

### Comparing `pyhelpers_daevski-0.3.0/PKG-INFO` & `pyhelpers_daevski-0.3.1/PKG-INFO`

 * *Files 16% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pyhelpers-daevski
-Version: 0.3.0
+Version: 0.3.1
 Summary: helper functions for personal use
 Author: David Mckee
 Author-email: daevski@gmail.com
 Requires-Python: >=3.9,<4.0
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
```

