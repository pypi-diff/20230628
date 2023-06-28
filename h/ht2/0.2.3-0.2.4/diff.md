# Comparing `tmp/ht2-0.2.3.tar.gz` & `tmp/ht2-0.2.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "ht2-0.2.3.tar", last modified: Wed Jun 28 07:20:58 2023, max compression
+gzip compressed data, was "ht2-0.2.4.tar", last modified: Wed Jun 28 07:36:18 2023, max compression
```

## Comparing `ht2-0.2.3.tar` & `ht2-0.2.4.tar`

### file list

```diff
@@ -1,26 +1,26 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:20:58.174095 ht2-0.2.3/
--rw-r--r--   0 root         (0) root         (0)     1070 2023-06-25 03:35:59.000000 ht2-0.2.3/LICENSE
--rw-r--r--   0 root         (0) root         (0)      807 2023-06-28 07:20:58.174095 ht2-0.2.3/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)      282 2023-06-25 03:35:59.000000 ht2-0.2.3/README.md
--rw-r--r--   0 root         (0) root         (0)      722 2023-06-28 07:16:51.000000 ht2-0.2.3/pyproject.toml
--rw-r--r--   0 root         (0) root         (0)       38 2023-06-28 07:20:58.174095 ht2-0.2.3/setup.cfg
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:20:58.166096 ht2-0.2.3/src/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:20:58.170096 ht2-0.2.3/src/ht2/
--rw-r--r--   0 root         (0) root         (0)      186 2023-06-25 03:35:59.000000 ht2-0.2.3/src/ht2/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:20:58.170096 ht2-0.2.3/src/ht2/schemas/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-25 03:35:59.000000 ht2-0.2.3/src/ht2/schemas/basic.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:20:58.174095 ht2-0.2.3/src/ht2/utils_dev/
--rw-r--r--   0 root         (0) root         (0)     1556 2023-06-28 03:26:06.000000 ht2-0.2.3/src/ht2/utils_dev/converts.py
--rw-r--r--   0 root         (0) root         (0)       71 2023-06-25 03:35:59.000000 ht2-0.2.3/src/ht2/utils_dev/example.py
--rw-r--r--   0 root         (0) root         (0)     6068 2023-06-25 03:35:59.000000 ht2-0.2.3/src/ht2/utils_dev/files.py
--rw-r--r--   0 root         (0) root         (0)     1071 2023-06-25 03:35:59.000000 ht2-0.2.3/src/ht2/utils_dev/image.py
--rw-r--r--   0 root         (0) root         (0)      467 2023-06-25 03:35:59.000000 ht2-0.2.3/src/ht2/utils_dev/misc.py
--rw-r--r--   0 root         (0) root         (0)      434 2023-06-25 03:35:59.000000 ht2-0.2.3/src/ht2/utils_dev/os.py
--rw-r--r--   0 root         (0) root         (0)      672 2023-06-25 03:35:59.000000 ht2-0.2.3/src/ht2/utils_dev/text.py
--rw-r--r--   0 root         (0) root         (0)      503 2023-06-25 03:35:59.000000 ht2-0.2.3/src/ht2/utils_dev/visualize.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:20:58.170096 ht2-0.2.3/src/ht2.egg-info/
--rw-r--r--   0 root         (0) root         (0)      807 2023-06-28 07:20:58.000000 ht2-0.2.3/src/ht2.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)      451 2023-06-28 07:20:58.000000 ht2-0.2.3/src/ht2.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 07:20:58.000000 ht2-0.2.3/src/ht2.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)       67 2023-06-28 07:20:58.000000 ht2-0.2.3/src/ht2.egg-info/requires.txt
--rw-r--r--   0 root         (0) root         (0)        4 2023-06-28 07:20:58.000000 ht2-0.2.3/src/ht2.egg-info/top_level.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:36:18.331578 ht2-0.2.4/
+-rw-r--r--   0 root         (0) root         (0)     1070 2023-06-25 03:35:59.000000 ht2-0.2.4/LICENSE
+-rw-r--r--   0 root         (0) root         (0)      807 2023-06-28 07:36:18.331578 ht2-0.2.4/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)      282 2023-06-25 03:35:59.000000 ht2-0.2.4/README.md
+-rw-r--r--   0 root         (0) root         (0)      722 2023-06-28 07:34:14.000000 ht2-0.2.4/pyproject.toml
+-rw-r--r--   0 root         (0) root         (0)       38 2023-06-28 07:36:18.331578 ht2-0.2.4/setup.cfg
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:36:18.331578 ht2-0.2.4/src/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:36:18.331578 ht2-0.2.4/src/ht2/
+-rw-r--r--   0 root         (0) root         (0)      220 2023-06-28 07:33:54.000000 ht2-0.2.4/src/ht2/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:36:18.331578 ht2-0.2.4/src/ht2/schemas/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-25 03:35:59.000000 ht2-0.2.4/src/ht2/schemas/basic.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:36:18.331578 ht2-0.2.4/src/ht2/utils_dev/
+-rw-r--r--   0 root         (0) root         (0)     1556 2023-06-28 03:26:06.000000 ht2-0.2.4/src/ht2/utils_dev/converts.py
+-rw-r--r--   0 root         (0) root         (0)       71 2023-06-25 03:35:59.000000 ht2-0.2.4/src/ht2/utils_dev/example.py
+-rw-r--r--   0 root         (0) root         (0)     6068 2023-06-25 03:35:59.000000 ht2-0.2.4/src/ht2/utils_dev/files.py
+-rw-r--r--   0 root         (0) root         (0)     1071 2023-06-25 03:35:59.000000 ht2-0.2.4/src/ht2/utils_dev/image.py
+-rw-r--r--   0 root         (0) root         (0)      467 2023-06-25 03:35:59.000000 ht2-0.2.4/src/ht2/utils_dev/misc.py
+-rw-r--r--   0 root         (0) root         (0)      434 2023-06-25 03:35:59.000000 ht2-0.2.4/src/ht2/utils_dev/os.py
+-rw-r--r--   0 root         (0) root         (0)      672 2023-06-25 03:35:59.000000 ht2-0.2.4/src/ht2/utils_dev/text.py
+-rw-r--r--   0 root         (0) root         (0)      503 2023-06-25 03:35:59.000000 ht2-0.2.4/src/ht2/utils_dev/visualize.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 07:36:18.331578 ht2-0.2.4/src/ht2.egg-info/
+-rw-r--r--   0 root         (0) root         (0)      807 2023-06-28 07:36:18.000000 ht2-0.2.4/src/ht2.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)      451 2023-06-28 07:36:18.000000 ht2-0.2.4/src/ht2.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 07:36:18.000000 ht2-0.2.4/src/ht2.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)       67 2023-06-28 07:36:18.000000 ht2-0.2.4/src/ht2.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)        4 2023-06-28 07:36:18.000000 ht2-0.2.4/src/ht2.egg-info/top_level.txt
```

### Comparing `ht2-0.2.3/LICENSE` & `ht2-0.2.4/LICENSE`

 * *Files identical despite different names*

### Comparing `ht2-0.2.3/PKG-INFO` & `ht2-0.2.4/PKG-INFO`

 * *Files 16% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: ht2
-Version: 0.2.3
+Version: 0.2.4
 Summary: Just a bag of quality of life tools for Machine Learning Engineers
 Author-email: Haotian Zhang <z.haotian@columbia.edu>
 Project-URL: Homepage, https://github.com/htplex/ht2
 Project-URL: Bug Tracker, https://github.com/htplex/ht2/issues
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```

### Comparing `ht2-0.2.3/pyproject.toml` & `ht2-0.2.4/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 [build-system]
 requires = ["setuptools>=61.0"]
 build-backend = "setuptools.build_meta"
 
 [project]
 name = "ht2"
-version = "0.2.3"
+version = "0.2.4"
 authors = [
   { name="Haotian Zhang", email="z.haotian@columbia.edu" },
 ]
 description = "Just a bag of quality of life tools for Machine Learning Engineers"
 readme = "README.md"
 requires-python = ">=3.7"
 classifiers = [
```

### Comparing `ht2-0.2.3/src/ht2/utils_dev/converts.py` & `ht2-0.2.4/src/ht2/utils_dev/converts.py`

 * *Files identical despite different names*

### Comparing `ht2-0.2.3/src/ht2/utils_dev/files.py` & `ht2-0.2.4/src/ht2/utils_dev/files.py`

 * *Files identical despite different names*

### Comparing `ht2-0.2.3/src/ht2/utils_dev/image.py` & `ht2-0.2.4/src/ht2/utils_dev/image.py`

 * *Files identical despite different names*

### Comparing `ht2-0.2.3/src/ht2/utils_dev/text.py` & `ht2-0.2.4/src/ht2/utils_dev/text.py`

 * *Files identical despite different names*

### Comparing `ht2-0.2.3/src/ht2.egg-info/PKG-INFO` & `ht2-0.2.4/src/ht2.egg-info/PKG-INFO`

 * *Files 16% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: ht2
-Version: 0.2.3
+Version: 0.2.4
 Summary: Just a bag of quality of life tools for Machine Learning Engineers
 Author-email: Haotian Zhang <z.haotian@columbia.edu>
 Project-URL: Homepage, https://github.com/htplex/ht2
 Project-URL: Bug Tracker, https://github.com/htplex/ht2/issues
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```

