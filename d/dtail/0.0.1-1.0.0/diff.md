# Comparing `tmp/dtail-0.0.1.tar.gz` & `tmp/dtail-1.0.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dtail-0.0.1.tar", last modified: Wed Jun 28 05:11:56 2023, max compression
+gzip compressed data, was "dtail-1.0.0.tar", last modified: Wed Jun 28 16:11:07 2023, max compression
```

## Comparing `dtail-0.0.1.tar` & `dtail-1.0.0.tar`

### file list

```diff
@@ -1,15 +1,15 @@
-drwxrwxr-x   0 dan       (1000) dan       (1000)        0 2023-06-28 05:11:56.629823 dtail-0.0.1/
--rw-rw-r--   0 dan       (1000) dan       (1000)     1074 2023-06-28 05:11:01.000000 dtail-0.0.1/LICENSE
--rw-rw-r--   0 dan       (1000) dan       (1000)      549 2023-06-28 05:11:56.629823 dtail-0.0.1/PKG-INFO
--rw-rw-r--   0 dan       (1000) dan       (1000)      119 2023-06-28 04:28:50.000000 dtail-0.0.1/README.md
-drwxrwxr-x   0 dan       (1000) dan       (1000)        0 2023-06-28 05:11:56.629823 dtail-0.0.1/bin/
--rwxrwxr-x   0 dan       (1000) dan       (1000)      436 2023-06-28 04:15:13.000000 dtail-0.0.1/bin/dtail
-drwxrwxr-x   0 dan       (1000) dan       (1000)        0 2023-06-28 05:11:56.629823 dtail-0.0.1/dtail/
--rw-rw-r--   0 dan       (1000) dan       (1000)     2120 2023-06-28 04:16:49.000000 dtail-0.0.1/dtail/__init__.py
-drwxrwxr-x   0 dan       (1000) dan       (1000)        0 2023-06-28 05:11:56.629823 dtail-0.0.1/dtail.egg-info/
--rw-rw-r--   0 dan       (1000) dan       (1000)      549 2023-06-28 05:11:56.000000 dtail-0.0.1/dtail.egg-info/PKG-INFO
--rw-rw-r--   0 dan       (1000) dan       (1000)      176 2023-06-28 05:11:56.000000 dtail-0.0.1/dtail.egg-info/SOURCES.txt
--rw-rw-r--   0 dan       (1000) dan       (1000)        1 2023-06-28 05:11:56.000000 dtail-0.0.1/dtail.egg-info/dependency_links.txt
--rw-rw-r--   0 dan       (1000) dan       (1000)        6 2023-06-28 05:11:56.000000 dtail-0.0.1/dtail.egg-info/top_level.txt
--rw-rw-r--   0 dan       (1000) dan       (1000)      560 2023-06-28 05:11:01.000000 dtail-0.0.1/pyproject.toml
--rw-rw-r--   0 dan       (1000) dan       (1000)       38 2023-06-28 05:11:56.629823 dtail-0.0.1/setup.cfg
+drwxrwxr-x   0 dan       (1001) dan       (1001)        0 2023-06-28 16:11:07.454229 dtail-1.0.0/
+-rw-rw-r--   0 dan       (1001) dan       (1001)     1074 2023-06-28 16:07:24.000000 dtail-1.0.0/LICENSE
+-rw-rw-r--   0 dan       (1001) dan       (1001)      548 2023-06-28 16:11:07.454229 dtail-1.0.0/PKG-INFO
+-rw-rw-r--   0 dan       (1001) dan       (1001)      119 2023-06-28 16:07:24.000000 dtail-1.0.0/README.md
+drwxrwxr-x   0 dan       (1001) dan       (1001)        0 2023-06-28 16:11:07.454229 dtail-1.0.0/bin/
+-rwxrwxr-x   0 dan       (1001) dan       (1001)      436 2023-06-28 16:07:24.000000 dtail-1.0.0/bin/dtail
+drwxrwxr-x   0 dan       (1001) dan       (1001)        0 2023-06-28 16:11:07.454229 dtail-1.0.0/dtail/
+-rw-rw-r--   0 dan       (1001) dan       (1001)     2120 2023-06-28 16:07:24.000000 dtail-1.0.0/dtail/__init__.py
+drwxrwxr-x   0 dan       (1001) dan       (1001)        0 2023-06-28 16:11:07.454229 dtail-1.0.0/dtail.egg-info/
+-rw-rw-r--   0 dan       (1001) dan       (1001)      548 2023-06-28 16:11:07.000000 dtail-1.0.0/dtail.egg-info/PKG-INFO
+-rw-rw-r--   0 dan       (1001) dan       (1001)      176 2023-06-28 16:11:07.000000 dtail-1.0.0/dtail.egg-info/SOURCES.txt
+-rw-rw-r--   0 dan       (1001) dan       (1001)        1 2023-06-28 16:11:07.000000 dtail-1.0.0/dtail.egg-info/dependency_links.txt
+-rw-rw-r--   0 dan       (1001) dan       (1001)        6 2023-06-28 16:11:07.000000 dtail-1.0.0/dtail.egg-info/top_level.txt
+-rw-rw-r--   0 dan       (1001) dan       (1001)      559 2023-06-28 16:08:56.000000 dtail-1.0.0/pyproject.toml
+-rw-rw-r--   0 dan       (1001) dan       (1001)       38 2023-06-28 16:11:07.454229 dtail-1.0.0/setup.cfg
```

### Comparing `dtail-0.0.1/LICENSE` & `dtail-1.0.0/LICENSE`

 * *Files identical despite different names*

### Comparing `dtail-0.0.1/PKG-INFO` & `dtail-1.0.0/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,16 +1,16 @@
 Metadata-Version: 2.1
 Name: dtail
-Version: 0.0.1
+Version: 1.0.0
 Summary: tail with globs and colors
 Author-email: Dan <dansonlinepresence@gmail.com>
 Project-URL: Homepage, https://github.com/dansgithubuser/dtail
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
-Requires-Python: >=3.10
+Requires-Python: >=3.6
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 A tail utility with a couple powers:
 1. tail a glob of present and future files
 2. use regular expressions to colorize
```

### Comparing `dtail-0.0.1/dtail/__init__.py` & `dtail-1.0.0/dtail/__init__.py`

 * *Files identical despite different names*

### Comparing `dtail-0.0.1/dtail.egg-info/PKG-INFO` & `dtail-1.0.0/dtail.egg-info/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,16 +1,16 @@
 Metadata-Version: 2.1
 Name: dtail
-Version: 0.0.1
+Version: 1.0.0
 Summary: tail with globs and colors
 Author-email: Dan <dansonlinepresence@gmail.com>
 Project-URL: Homepage, https://github.com/dansgithubuser/dtail
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
-Requires-Python: >=3.10
+Requires-Python: >=3.6
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 A tail utility with a couple powers:
 1. tail a glob of present and future files
 2. use regular expressions to colorize
```

### Comparing `dtail-0.0.1/pyproject.toml` & `dtail-1.0.0/pyproject.toml`

 * *Files 25% similar despite different names*

```diff
@@ -1,16 +1,16 @@
 [project]
 name = "dtail"
-version = "0.0.1"
+version = "1.0.0"
 authors = [
   { name="Dan", email="dansonlinepresence@gmail.com" },
 ]
 description = "tail with globs and colors"
 readme = "README.md"
-requires-python = ">=3.10"
+requires-python = ">=3.6"
 classifiers = [
     "Programming Language :: Python :: 3",
     "License :: OSI Approved :: MIT License",
     "Operating System :: OS Independent",
 ]
 
 [project.urls]
```

