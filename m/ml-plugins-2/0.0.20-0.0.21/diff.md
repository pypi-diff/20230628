# Comparing `tmp/ml_plugins_2-0.0.20.tar.gz` & `tmp/ml_plugins_2-0.0.21.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "ml_plugins_2-0.0.20.tar", last modified: Wed Jun 28 00:40:39 2023, max compression
+gzip compressed data, was "ml_plugins_2-0.0.21.tar", last modified: Wed Jun 28 00:52:40 2023, max compression
```

## Comparing `ml_plugins_2-0.0.20.tar` & `ml_plugins_2-0.0.21.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-28 00:40:39.713034 ml_plugins_2-0.0.20/
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)       57 2023-06-28 00:40:39.712870 ml_plugins_2-0.0.20/PKG-INFO
-drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-28 00:40:39.710578 ml_plugins_2-0.0.20/examples/
-drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-28 00:40:39.710886 ml_plugins_2-0.0.20/examples/pip/
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)     1751 2023-06-15 05:26:48.000000 ml_plugins_2-0.0.20/examples/pip/extras_flow.py
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)     1975 2023-06-15 05:26:48.000000 ml_plugins_2-0.0.20/examples/pip/pip_flow.py
-drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-28 00:40:39.711038 ml_plugins_2-0.0.20/examples/poetry/
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)     1901 2023-06-15 05:26:48.000000 ml_plugins_2-0.0.20/examples/poetry/poetry_flow.py
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)     3857 2023-06-15 05:26:48.000000 ml_plugins_2-0.0.20/examples/reference.py
-drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-28 00:40:39.711837 ml_plugins_2-0.0.20/ml_plugins_2.egg-info/
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)       57 2023-06-28 00:40:39.000000 ml_plugins_2-0.0.20/ml_plugins_2.egg-info/PKG-INFO
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)      417 2023-06-28 00:40:39.000000 ml_plugins_2-0.0.20/ml_plugins_2.egg-info/SOURCES.txt
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)        1 2023-06-28 00:40:39.000000 ml_plugins_2-0.0.20/ml_plugins_2.egg-info/dependency_links.txt
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)       23 2023-06-28 00:40:39.000000 ml_plugins_2-0.0.20/ml_plugins_2.egg-info/requires.txt
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)       22 2023-06-28 00:40:39.000000 ml_plugins_2-0.0.20/ml_plugins_2.egg-info/top_level.txt
-drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-28 00:40:39.711969 ml_plugins_2-0.0.20/plugins/
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)        0 2023-06-07 05:31:29.000000 ml_plugins_2-0.0.20/plugins/__init__.py
-drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-28 00:40:39.712236 ml_plugins_2-0.0.20/plugins/pip/
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)        0 2023-06-07 05:31:29.000000 ml_plugins_2-0.0.20/plugins/pip/__init__.py
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)     1390 2023-06-27 01:59:00.000000 ml_plugins_2-0.0.20/plugins/pip/plugin.py
-drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-28 00:40:39.712612 ml_plugins_2-0.0.20/plugins/poetry/
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)        0 2023-06-07 05:31:29.000000 ml_plugins_2-0.0.20/plugins/poetry/__init__.py
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)     1552 2023-06-28 00:40:08.000000 ml_plugins_2-0.0.20/plugins/poetry/plugin.py
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)      284 2023-06-28 00:40:31.000000 ml_plugins_2-0.0.20/pyproject.toml
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)       38 2023-06-28 00:40:39.713080 ml_plugins_2-0.0.20/setup.cfg
+drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-28 00:52:40.635883 ml_plugins_2-0.0.21/
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)       57 2023-06-28 00:52:40.635699 ml_plugins_2-0.0.21/PKG-INFO
+drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-28 00:52:40.633196 ml_plugins_2-0.0.21/examples/
+drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-28 00:52:40.633492 ml_plugins_2-0.0.21/examples/pip/
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)     1751 2023-06-15 05:26:48.000000 ml_plugins_2-0.0.21/examples/pip/extras_flow.py
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)     1975 2023-06-15 05:26:48.000000 ml_plugins_2-0.0.21/examples/pip/pip_flow.py
+drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-28 00:52:40.633631 ml_plugins_2-0.0.21/examples/poetry/
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)     1901 2023-06-15 05:26:48.000000 ml_plugins_2-0.0.21/examples/poetry/poetry_flow.py
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)     3857 2023-06-15 05:26:48.000000 ml_plugins_2-0.0.21/examples/reference.py
+drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-28 00:52:40.634849 ml_plugins_2-0.0.21/ml_plugins_2.egg-info/
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)       57 2023-06-28 00:52:40.000000 ml_plugins_2-0.0.21/ml_plugins_2.egg-info/PKG-INFO
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)      417 2023-06-28 00:52:40.000000 ml_plugins_2-0.0.21/ml_plugins_2.egg-info/SOURCES.txt
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)        1 2023-06-28 00:52:40.000000 ml_plugins_2-0.0.21/ml_plugins_2.egg-info/dependency_links.txt
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)       23 2023-06-28 00:52:40.000000 ml_plugins_2-0.0.21/ml_plugins_2.egg-info/requires.txt
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)       22 2023-06-28 00:52:40.000000 ml_plugins_2-0.0.21/ml_plugins_2.egg-info/top_level.txt
+drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-28 00:52:40.635006 ml_plugins_2-0.0.21/plugins/
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)        0 2023-06-07 05:31:29.000000 ml_plugins_2-0.0.21/plugins/__init__.py
+drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-28 00:52:40.635224 ml_plugins_2-0.0.21/plugins/pip/
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)        0 2023-06-07 05:31:29.000000 ml_plugins_2-0.0.21/plugins/pip/__init__.py
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)     1390 2023-06-27 01:59:00.000000 ml_plugins_2-0.0.21/plugins/pip/plugin.py
+drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-28 00:52:40.635492 ml_plugins_2-0.0.21/plugins/poetry/
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)        0 2023-06-07 05:31:29.000000 ml_plugins_2-0.0.21/plugins/poetry/__init__.py
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)     1559 2023-06-28 00:52:06.000000 ml_plugins_2-0.0.21/plugins/poetry/plugin.py
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)      284 2023-06-28 00:52:12.000000 ml_plugins_2-0.0.21/pyproject.toml
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)       38 2023-06-28 00:52:40.635929 ml_plugins_2-0.0.21/setup.cfg
```

### Comparing `ml_plugins_2-0.0.20/examples/pip/extras_flow.py` & `ml_plugins_2-0.0.21/examples/pip/extras_flow.py`

 * *Files identical despite different names*

### Comparing `ml_plugins_2-0.0.20/examples/pip/pip_flow.py` & `ml_plugins_2-0.0.21/examples/pip/pip_flow.py`

 * *Files identical despite different names*

### Comparing `ml_plugins_2-0.0.20/examples/poetry/poetry_flow.py` & `ml_plugins_2-0.0.21/examples/poetry/poetry_flow.py`

 * *Files identical despite different names*

### Comparing `ml_plugins_2-0.0.20/examples/reference.py` & `ml_plugins_2-0.0.21/examples/reference.py`

 * *Files identical despite different names*

### Comparing `ml_plugins_2-0.0.20/plugins/pip/plugin.py` & `ml_plugins_2-0.0.21/plugins/pip/plugin.py`

 * *Files identical despite different names*

### Comparing `ml_plugins_2-0.0.20/plugins/poetry/plugin.py` & `ml_plugins_2-0.0.21/plugins/poetry/plugin.py`

 * *Files 1% similar despite different names*

```diff
@@ -12,15 +12,15 @@
         f.write(data)
 
 # TODO: extras option, poetry add extra stuff 
 # additonal_libraries: [library, version]
 # dictionary of library name and version constraint
 # make sure to supply constraint in version: ==, >=, @^, @~, @latest
 
-def poetry(additional_libraries: Dict[str, str], use_pypi: bool = True, local_module_dir: str = None):
+def poetry(additional_libraries: Dict[str, str] = None, use_pypi: bool = True, local_module_dir: str = None):
     def decorator(function):
         @functools.wraps(function)
         def wrapper(self, *args):
             if hasattr(self, "lockfile"):
                 write_to_disk(self.lockfile, "poetry.lock")
             write_to_disk(self.pyproject, "pyproject.toml")
             if(not use_pypi):
```

