# Comparing `tmp/ml_plugins_2-0.0.18.tar.gz` & `tmp/ml_plugins_2-0.0.19.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "ml_plugins_2-0.0.18.tar", last modified: Thu Jun 15 06:20:06 2023, max compression
+gzip compressed data, was "ml_plugins_2-0.0.19.tar", last modified: Tue Jun 27 23:42:29 2023, max compression
```

## Comparing `ml_plugins_2-0.0.18.tar` & `ml_plugins_2-0.0.19.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-15 06:20:06.510986 ml_plugins_2-0.0.18/
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)       57 2023-06-15 06:20:06.510792 ml_plugins_2-0.0.18/PKG-INFO
-drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-15 06:20:06.508226 ml_plugins_2-0.0.18/examples/
-drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-15 06:20:06.508513 ml_plugins_2-0.0.18/examples/pip/
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)     1751 2023-06-15 05:26:48.000000 ml_plugins_2-0.0.18/examples/pip/extras_flow.py
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)     1975 2023-06-15 05:26:48.000000 ml_plugins_2-0.0.18/examples/pip/pip_flow.py
-drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-15 06:20:06.508667 ml_plugins_2-0.0.18/examples/poetry/
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)     1901 2023-06-15 05:26:48.000000 ml_plugins_2-0.0.18/examples/poetry/poetry_flow.py
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)     3857 2023-06-15 05:26:48.000000 ml_plugins_2-0.0.18/examples/reference.py
-drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-15 06:20:06.509513 ml_plugins_2-0.0.18/ml_plugins_2.egg-info/
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)       57 2023-06-15 06:20:06.000000 ml_plugins_2-0.0.18/ml_plugins_2.egg-info/PKG-INFO
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)      417 2023-06-15 06:20:06.000000 ml_plugins_2-0.0.18/ml_plugins_2.egg-info/SOURCES.txt
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)        1 2023-06-15 06:20:06.000000 ml_plugins_2-0.0.18/ml_plugins_2.egg-info/dependency_links.txt
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)       23 2023-06-15 06:20:06.000000 ml_plugins_2-0.0.18/ml_plugins_2.egg-info/requires.txt
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)       22 2023-06-15 06:20:06.000000 ml_plugins_2-0.0.18/ml_plugins_2.egg-info/top_level.txt
-drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-15 06:20:06.509659 ml_plugins_2-0.0.18/plugins/
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)        0 2023-06-07 05:31:29.000000 ml_plugins_2-0.0.18/plugins/__init__.py
-drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-15 06:20:06.509904 ml_plugins_2-0.0.18/plugins/pip/
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)        0 2023-06-07 05:31:29.000000 ml_plugins_2-0.0.18/plugins/pip/__init__.py
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)      994 2023-06-15 05:26:48.000000 ml_plugins_2-0.0.18/plugins/pip/plugin.py
-drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-15 06:20:06.510172 ml_plugins_2-0.0.18/plugins/poetry/
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)        0 2023-06-07 05:31:29.000000 ml_plugins_2-0.0.18/plugins/poetry/__init__.py
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)      723 2023-06-15 05:29:54.000000 ml_plugins_2-0.0.18/plugins/poetry/plugin.py
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)      284 2023-06-15 06:19:56.000000 ml_plugins_2-0.0.18/pyproject.toml
--rw-r--r--   0 rikish.kamboj   (503) staff       (20)       38 2023-06-15 06:20:06.511036 ml_plugins_2-0.0.18/setup.cfg
+drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-27 23:42:29.035112 ml_plugins_2-0.0.19/
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)       57 2023-06-27 23:42:29.034859 ml_plugins_2-0.0.19/PKG-INFO
+drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-27 23:42:29.031635 ml_plugins_2-0.0.19/examples/
+drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-27 23:42:29.031919 ml_plugins_2-0.0.19/examples/pip/
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)     1751 2023-06-15 05:26:48.000000 ml_plugins_2-0.0.19/examples/pip/extras_flow.py
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)     1975 2023-06-15 05:26:48.000000 ml_plugins_2-0.0.19/examples/pip/pip_flow.py
+drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-27 23:42:29.032066 ml_plugins_2-0.0.19/examples/poetry/
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)     1901 2023-06-15 05:26:48.000000 ml_plugins_2-0.0.19/examples/poetry/poetry_flow.py
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)     3857 2023-06-15 05:26:48.000000 ml_plugins_2-0.0.19/examples/reference.py
+drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-27 23:42:29.032876 ml_plugins_2-0.0.19/ml_plugins_2.egg-info/
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)       57 2023-06-27 23:42:29.000000 ml_plugins_2-0.0.19/ml_plugins_2.egg-info/PKG-INFO
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)      417 2023-06-27 23:42:29.000000 ml_plugins_2-0.0.19/ml_plugins_2.egg-info/SOURCES.txt
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)        1 2023-06-27 23:42:29.000000 ml_plugins_2-0.0.19/ml_plugins_2.egg-info/dependency_links.txt
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)       23 2023-06-27 23:42:29.000000 ml_plugins_2-0.0.19/ml_plugins_2.egg-info/requires.txt
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)       22 2023-06-27 23:42:29.000000 ml_plugins_2-0.0.19/ml_plugins_2.egg-info/top_level.txt
+drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-27 23:42:29.033049 ml_plugins_2-0.0.19/plugins/
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)        0 2023-06-07 05:31:29.000000 ml_plugins_2-0.0.19/plugins/__init__.py
+drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-27 23:42:29.033310 ml_plugins_2-0.0.19/plugins/pip/
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)        0 2023-06-07 05:31:29.000000 ml_plugins_2-0.0.19/plugins/pip/__init__.py
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)     1390 2023-06-27 01:59:00.000000 ml_plugins_2-0.0.19/plugins/pip/plugin.py
+drwxr-xr-x   0 rikish.kamboj   (503) staff       (20)        0 2023-06-27 23:42:29.034329 ml_plugins_2-0.0.19/plugins/poetry/
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)        0 2023-06-07 05:31:29.000000 ml_plugins_2-0.0.19/plugins/poetry/__init__.py
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)     1544 2023-06-27 06:28:58.000000 ml_plugins_2-0.0.19/plugins/poetry/plugin.py
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)      284 2023-06-27 23:41:55.000000 ml_plugins_2-0.0.19/pyproject.toml
+-rw-r--r--   0 rikish.kamboj   (503) staff       (20)       38 2023-06-27 23:42:29.035169 ml_plugins_2-0.0.19/setup.cfg
```

### Comparing `ml_plugins_2-0.0.18/examples/pip/extras_flow.py` & `ml_plugins_2-0.0.19/examples/pip/extras_flow.py`

 * *Files identical despite different names*

### Comparing `ml_plugins_2-0.0.18/examples/pip/pip_flow.py` & `ml_plugins_2-0.0.19/examples/pip/pip_flow.py`

 * *Files identical despite different names*

### Comparing `ml_plugins_2-0.0.18/examples/poetry/poetry_flow.py` & `ml_plugins_2-0.0.19/examples/poetry/poetry_flow.py`

 * *Files identical despite different names*

### Comparing `ml_plugins_2-0.0.18/examples/reference.py` & `ml_plugins_2-0.0.19/examples/reference.py`

 * *Files identical despite different names*

### Comparing `ml_plugins_2-0.0.18/plugins/pip/plugin.py` & `ml_plugins_2-0.0.19/plugins/pip/plugin.py`

 * *Files 21% similar despite different names*

```diff
@@ -4,29 +4,35 @@
 
 from typing import Dict
 
 def write_to_disk(data: str, filename: str) -> None:
     with open(filename, mode='w+') as f:
         f.write(data)
 
-def pip():
+def pip(use_pypi: bool = True):
     def decorator(function):
         @functools.wraps(function)
         def wrapper(self, *args):
             write_to_disk(self.requirements, "requirements.txt")
-            subprocess.run([sys.executable, '-m' 'pip', 'install', "-r" 'requirements.txt'])
+            if(use_pypi):
+                subprocess.run([sys.executable, '-m' 'pip', 'install', "-r" 'requirements.txt'])
+            else:
+                subprocess.run([sys.executable, '-m' 'pip', 'install', '--no-index', "-r" 'requirements.txt'])
             return function(self, *args)
         return wrapper
     return decorator
  
-def extra(libraries: Dict[str, str]):
+def extra(libraries: Dict[str, str], use_pypi: bool = True):
     def decorator(function):
         @functools.wraps(function)
         def wrapper(*args, **kwargs):
             for library, version in libraries.items():
                 print('Pip Install:', library, version)
-                subprocess.run([sys.executable, '-m', 'pip', 'install', '--quiet', library + '==' + version])
+                if(use_pypi):
+                    subprocess.run([sys.executable, '-m', 'pip', 'install', '--quiet', library + '==' + version])
+                else:
+                    subprocess.run([sys.executable, '-m', 'pip', 'install', '--no-index', '--quiet', library + '==' + version])         
             return function(*args, **kwargs)
 
         return wrapper
 
     return decorator
```

