# Comparing `tmp/objinspect-0.2.2.tar.gz` & `tmp/objinspect-0.2.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "objinspect-0.2.2.tar", last modified: Wed May 24 19:09:01 2023, max compression
+gzip compressed data, was "objinspect-0.2.3.tar", last modified: Wed Jun 28 15:53:43 2023, max compression
```

## Comparing `objinspect-0.2.2.tar` & `objinspect-0.2.3.tar`

### file list

```diff
@@ -1,21 +1,21 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-24 19:09:01.292092 objinspect-0.2.2/
--rw-r--r--   0 runner    (1001) docker     (123)     1071 2023-05-24 19:08:47.000000 objinspect-0.2.2/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)     2756 2023-05-24 19:09:01.292092 objinspect-0.2.2/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1909 2023-05-24 19:08:47.000000 objinspect-0.2.2/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-24 19:09:01.292092 objinspect-0.2.2/objinspect/
--rw-r--r--   0 runner    (1001) docker     (123)     2069 2023-05-24 19:08:47.000000 objinspect-0.2.2/objinspect/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     5784 2023-05-24 19:08:47.000000 objinspect-0.2.2/objinspect/_class.py
--rw-r--r--   0 runner    (1001) docker     (123)      150 2023-05-24 19:08:47.000000 objinspect-0.2.2/objinspect/constants.py
--rw-r--r--   0 runner    (1001) docker     (123)     4213 2023-05-24 19:08:47.000000 objinspect-0.2.2/objinspect/function.py
--rw-r--r--   0 runner    (1001) docker     (123)     3439 2023-05-24 19:08:47.000000 objinspect-0.2.2/objinspect/method.py
--rw-r--r--   0 runner    (1001) docker     (123)     2497 2023-05-24 19:08:47.000000 objinspect-0.2.2/objinspect/parameter.py
--rw-r--r--   0 runner    (1001) docker     (123)     2107 2023-05-24 19:08:47.000000 objinspect-0.2.2/objinspect/util.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-24 19:09:01.292092 objinspect-0.2.2/objinspect.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     2756 2023-05-24 19:09:01.000000 objinspect-0.2.2/objinspect.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      365 2023-05-24 19:09:01.000000 objinspect-0.2.2/objinspect.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-05-24 19:09:01.000000 objinspect-0.2.2/objinspect.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       67 2023-05-24 19:09:01.000000 objinspect-0.2.2/objinspect.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       11 2023-05-24 19:09:01.000000 objinspect-0.2.2/objinspect.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)     1543 2023-05-24 19:08:47.000000 objinspect-0.2.2/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-05-24 19:09:01.292092 objinspect-0.2.2/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-05-24 19:08:47.000000 objinspect-0.2.2/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:53:43.070666 objinspect-0.2.3/
+-rw-r--r--   0 runner    (1001) docker     (123)     1071 2023-06-28 15:53:32.000000 objinspect-0.2.3/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     2756 2023-06-28 15:53:43.070666 objinspect-0.2.3/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1909 2023-06-28 15:53:32.000000 objinspect-0.2.3/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:53:43.070666 objinspect-0.2.3/objinspect/
+-rw-r--r--   0 runner    (1001) docker     (123)     2069 2023-06-28 15:53:32.000000 objinspect-0.2.3/objinspect/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5784 2023-06-28 15:53:32.000000 objinspect-0.2.3/objinspect/_class.py
+-rw-r--r--   0 runner    (1001) docker     (123)      150 2023-06-28 15:53:32.000000 objinspect-0.2.3/objinspect/constants.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4213 2023-06-28 15:53:32.000000 objinspect-0.2.3/objinspect/function.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3439 2023-06-28 15:53:32.000000 objinspect-0.2.3/objinspect/method.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2497 2023-06-28 15:53:32.000000 objinspect-0.2.3/objinspect/parameter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2107 2023-06-28 15:53:32.000000 objinspect-0.2.3/objinspect/util.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:53:43.070666 objinspect-0.2.3/objinspect.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     2756 2023-06-28 15:53:43.000000 objinspect-0.2.3/objinspect.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      365 2023-06-28 15:53:43.000000 objinspect-0.2.3/objinspect.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 15:53:43.000000 objinspect-0.2.3/objinspect.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       67 2023-06-28 15:53:43.000000 objinspect-0.2.3/objinspect.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       11 2023-06-28 15:53:43.000000 objinspect-0.2.3/objinspect.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)     1543 2023-06-28 15:53:32.000000 objinspect-0.2.3/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 15:53:43.070666 objinspect-0.2.3/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 15:53:32.000000 objinspect-0.2.3/setup.py
```

### Comparing `objinspect-0.2.2/LICENSE` & `objinspect-0.2.3/LICENSE`

 * *Files identical despite different names*

### Comparing `objinspect-0.2.2/PKG-INFO` & `objinspect-0.2.3/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: objinspect
-Version: 0.2.2
+Version: 0.2.3
 Summary: View the structure of Python classes and functions
 Author-email: Žiga Ivanšek <ziga.ivansek@gmail.com>
 Project-URL: Repository, https://github.com/zigai/obj-inspect
 Keywords: objinspect,object inspection,code introspection,python inspect
 Classifier: Intended Audience :: Developers
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```

### Comparing `objinspect-0.2.2/README.md` & `objinspect-0.2.3/README.md`

 * *Files identical despite different names*

### Comparing `objinspect-0.2.2/objinspect/__init__.py` & `objinspect-0.2.3/objinspect/__init__.py`

 * *Files identical despite different names*

### Comparing `objinspect-0.2.2/objinspect/_class.py` & `objinspect-0.2.3/objinspect/_class.py`

 * *Files identical despite different names*

### Comparing `objinspect-0.2.2/objinspect/function.py` & `objinspect-0.2.3/objinspect/function.py`

 * *Files identical despite different names*

### Comparing `objinspect-0.2.2/objinspect/method.py` & `objinspect-0.2.3/objinspect/method.py`

 * *Files identical despite different names*

### Comparing `objinspect-0.2.2/objinspect/parameter.py` & `objinspect-0.2.3/objinspect/parameter.py`

 * *Files identical despite different names*

### Comparing `objinspect-0.2.2/objinspect/util.py` & `objinspect-0.2.3/objinspect/util.py`

 * *Files identical despite different names*

### Comparing `objinspect-0.2.2/objinspect.egg-info/PKG-INFO` & `objinspect-0.2.3/objinspect.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: objinspect
-Version: 0.2.2
+Version: 0.2.3
 Summary: View the structure of Python classes and functions
 Author-email: Žiga Ivanšek <ziga.ivansek@gmail.com>
 Project-URL: Repository, https://github.com/zigai/obj-inspect
 Keywords: objinspect,object inspection,code introspection,python inspect
 Classifier: Intended Audience :: Developers
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```

### Comparing `objinspect-0.2.2/pyproject.toml` & `objinspect-0.2.3/pyproject.toml`

 * *Files 18% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 [build-system]
 requires = ["setuptools", "setuptools-scm"]
 build-backend = "setuptools.build_meta"
 
 [project]
 name = "objinspect"
-version = "0.2.2"
+version = "0.2.3"
 description = "View the structure of Python classes and functions"
 authors = [{ name = "Žiga Ivanšek", email = "ziga.ivansek@gmail.com" }]
 license = { file = "LICENSE.txt" }
 readme = "README.md"
 requires-python = ">=3.10"
 
 classifiers = [
@@ -25,15 +25,15 @@
 keywords = [
   "objinspect",
   "object inspection",
   "code introspection",
   "python inspect",
 ]
 
-dependencies = ["docstring-parser==0.14.1"]
+dependencies = ["docstring-parser==0.15.0"]
 
 [project.optional-dependencies]
 test = ["pytest"]
 dev = ["black", "pytest", "flake8"]
 
 [project.urls]
 Repository = "https://github.com/zigai/obj-inspect"
```

