# Comparing `tmp/ml_plugins_2-0.0.19.tar.gz` & `tmp/ml_plugins_2-0.0.20.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "ml_plugins_2-0.0.19.tar", last modified: Tue Jun 27 23:42:29 2023, max compression
+gzip compressed data, was "ml_plugins_2-0.0.20.tar", last modified: Wed Jun 28 00:40:39 2023, max compression
```

## Comparing `ml_plugins_2-0.0.19.tar` & `ml_plugins_2-0.0.20.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-27 23:42:29.035112 ml_plugins_2-0.0.19/
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)       57 2023-06-27 23:42:29.034859 ml_plugins_2-0.0.19/PKG-INFO
-drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-27 23:42:29.031635 ml_plugins_2-0.0.19/examples/
-drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-27 23:42:29.031919 ml_plugins_2-0.0.19/examples/pip/
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)     1751 2023-06-15 05:26:48.000000 ml_plugins_2-0.0.19/examples/pip/extras_flow.py
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)     1975 2023-06-15 05:26:48.000000 ml_plugins_2-0.0.19/examples/pip/pip_flow.py
-drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-27 23:42:29.032066 ml_plugins_2-0.0.19/examples/poetry/
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)     1901 2023-06-15 05:26:48.000000 ml_plugins_2-0.0.19/examples/poetry/poetry_flow.py
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)     3857 2023-06-15 05:26:48.000000 ml_plugins_2-0.0.19/examples/reference.py
-drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-27 23:42:29.032876 ml_plugins_2-0.0.19/ml_plugins_2.egg-info/
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)       57 2023-06-27 23:42:29.000000 ml_plugins_2-0.0.19/ml_plugins_2.egg-info/PKG-INFO
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)      417 2023-06-27 23:42:29.000000 ml_plugins_2-0.0.19/ml_plugins_2.egg-info/SOURCES.txt
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)        1 2023-06-27 23:42:29.000000 ml_plugins_2-0.0.19/ml_plugins_2.egg-info/dependency_links.txt
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)       23 2023-06-27 23:42:29.000000 ml_plugins_2-0.0.19/ml_plugins_2.egg-info/requires.txt
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)       22 2023-06-27 23:42:29.000000 ml_plugins_2-0.0.19/ml_plugins_2.egg-info/top_level.txt
-drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-27 23:42:29.033049 ml_plugins_2-0.0.19/plugins/
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)        0 2023-06-07 05:31:29.000000 ml_plugins_2-0.0.19/plugins/__init__.py
-drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-27 23:42:29.033310 ml_plugins_2-0.0.19/plugins/pip/
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)        0 2023-06-07 05:31:29.000000 ml_plugins_2-0.0.19/plugins/pip/__init__.py
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)     1390 2023-06-27 01:59:00.000000 ml_plugins_2-0.0.19/plugins/pip/plugin.py
-drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-27 23:42:29.034329 ml_plugins_2-0.0.19/plugins/poetry/
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)        0 2023-06-07 05:31:29.000000 ml_plugins_2-0.0.19/plugins/poetry/__init__.py
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)     1544 2023-06-27 06:28:58.000000 ml_plugins_2-0.0.19/plugins/poetry/plugin.py
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)      284 2023-06-27 23:41:55.000000 ml_plugins_2-0.0.19/pyproject.toml
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)       38 2023-06-27 23:42:29.035169 ml_plugins_2-0.0.19/setup.cfg
+drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-28 00:40:39.713034 ml_plugins_2-0.0.20/
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)       57 2023-06-28 00:40:39.712870 ml_plugins_2-0.0.20/PKG-INFO
+drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-28 00:40:39.710578 ml_plugins_2-0.0.20/examples/
+drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-28 00:40:39.710886 ml_plugins_2-0.0.20/examples/pip/
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)     1751 2023-06-15 05:26:48.000000 ml_plugins_2-0.0.20/examples/pip/extras_flow.py
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)     1975 2023-06-15 05:26:48.000000 ml_plugins_2-0.0.20/examples/pip/pip_flow.py
+drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-28 00:40:39.711038 ml_plugins_2-0.0.20/examples/poetry/
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)     1901 2023-06-15 05:26:48.000000 ml_plugins_2-0.0.20/examples/poetry/poetry_flow.py
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)     3857 2023-06-15 05:26:48.000000 ml_plugins_2-0.0.20/examples/reference.py
+drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-28 00:40:39.711837 ml_plugins_2-0.0.20/ml_plugins_2.egg-info/
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)       57 2023-06-28 00:40:39.000000 ml_plugins_2-0.0.20/ml_plugins_2.egg-info/PKG-INFO
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)      417 2023-06-28 00:40:39.000000 ml_plugins_2-0.0.20/ml_plugins_2.egg-info/SOURCES.txt
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)        1 2023-06-28 00:40:39.000000 ml_plugins_2-0.0.20/ml_plugins_2.egg-info/dependency_links.txt
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)       23 2023-06-28 00:40:39.000000 ml_plugins_2-0.0.20/ml_plugins_2.egg-info/requires.txt
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)       22 2023-06-28 00:40:39.000000 ml_plugins_2-0.0.20/ml_plugins_2.egg-info/top_level.txt
+drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-28 00:40:39.711969 ml_plugins_2-0.0.20/plugins/
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)        0 2023-06-07 05:31:29.000000 ml_plugins_2-0.0.20/plugins/__init__.py
+drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-28 00:40:39.712236 ml_plugins_2-0.0.20/plugins/pip/
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)        0 2023-06-07 05:31:29.000000 ml_plugins_2-0.0.20/plugins/pip/__init__.py
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)     1390 2023-06-27 01:59:00.000000 ml_plugins_2-0.0.20/plugins/pip/plugin.py
+drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-28 00:40:39.712612 ml_plugins_2-0.0.20/plugins/poetry/
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)        0 2023-06-07 05:31:29.000000 ml_plugins_2-0.0.20/plugins/poetry/__init__.py
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)     1552 2023-06-28 00:40:08.000000 ml_plugins_2-0.0.20/plugins/poetry/plugin.py
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)      284 2023-06-28 00:40:31.000000 ml_plugins_2-0.0.20/pyproject.toml
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)       38 2023-06-28 00:40:39.713080 ml_plugins_2-0.0.20/setup.cfg
```

### Comparing `ml_plugins_2-0.0.19/examples/pip/extras_flow.py` & `ml_plugins_2-0.0.20/examples/pip/extras_flow.py`

 * *Files identical despite different names*

### Comparing `ml_plugins_2-0.0.19/examples/pip/pip_flow.py` & `ml_plugins_2-0.0.20/examples/pip/pip_flow.py`

 * *Files identical despite different names*

### Comparing `ml_plugins_2-0.0.19/examples/poetry/poetry_flow.py` & `ml_plugins_2-0.0.20/examples/poetry/poetry_flow.py`

 * *Files identical despite different names*

### Comparing `ml_plugins_2-0.0.19/examples/reference.py` & `ml_plugins_2-0.0.20/examples/reference.py`

 * *Files identical despite different names*

### Comparing `ml_plugins_2-0.0.19/plugins/pip/plugin.py` & `ml_plugins_2-0.0.20/plugins/pip/plugin.py`

 * *Files identical despite different names*

### Comparing `ml_plugins_2-0.0.19/plugins/poetry/plugin.py` & `ml_plugins_2-0.0.20/plugins/poetry/plugin.py`

 * *Files 6% similar despite different names*

```diff
@@ -26,13 +26,13 @@
             if(not use_pypi):
                 subprocess.run('poetry', 'source', 'add', '--priority=default', 'local', f'file:///{local_module_dir}')
             if(additional_libraries):
                 additional_libraries_str = ''
                 for library, version in additional_libraries.items():
                     curr = f'{library}{version}'
                     additional_libraries_str = f'{additional_libraries_str} {curr}'
-                subprocess.run('poetry', 'add', additional_libraries_str)
+                subprocess.run('poetry', 'add', additional_libraries_str.strip())
             subprocess.run([sys.executable, '-m', 'poetry', 'install', '-C', 'pyproject.toml'])
             return function(self, *args)
         return wrapper
     return decorator
```

