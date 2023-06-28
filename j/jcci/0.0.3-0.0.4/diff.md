# Comparing `tmp/jcci-0.0.3.tar.gz` & `tmp/jcci-0.0.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "jcci-0.0.3.tar", last modified: Mon Jun 26 05:44:59 2023, max compression
+gzip compressed data, was "jcci-0.0.4.tar", last modified: Wed Jun 28 11:10:53 2023, max compression
```

## Comparing `jcci-0.0.3.tar` & `jcci-0.0.4.tar`

### file list

```diff
@@ -1,16 +1,17 @@
-drwxrwxrwx   0        0        0        0 2023-06-26 05:44:59.933879 jcci-0.0.3/
--rw-rw-rw-   0        0        0        0 2022-09-20 03:06:31.000000 jcci-0.0.3/LICENSE
--rw-rw-rw-   0        0        0     1468 2023-06-26 05:44:59.932881 jcci-0.0.3/PKG-INFO
--rw-rw-rw-   0        0        0      955 2023-06-26 05:36:35.000000 jcci-0.0.3/README.md
--rw-rw-rw-   0        0        0      661 2023-06-26 05:44:47.000000 jcci-0.0.3/pyproject.toml
--rw-rw-rw-   0        0        0       42 2023-06-26 05:44:59.933879 jcci-0.0.3/setup.cfg
-drwxrwxrwx   0        0        0        0 2023-06-26 05:44:59.918882 jcci-0.0.3/src/
-drwxrwxrwx   0        0        0        0 2023-06-26 05:44:59.925881 jcci-0.0.3/src/jcci/
--rw-rw-rw-   0        0        0        0 2022-09-20 03:04:57.000000 jcci-0.0.3/src/jcci/__init__.py
--rw-rw-rw-   0        0        0     2083 2023-06-25 09:25:01.000000 jcci-0.0.3/src/jcci/java_analyzer.py
--rw-rw-rw-   0        0        0    41682 2023-06-26 05:17:01.000000 jcci-0.0.3/src/jcci/jcci.py
-drwxrwxrwx   0        0        0        0 2023-06-26 05:44:59.930880 jcci-0.0.3/src/jcci.egg-info/
--rw-rw-rw-   0        0        0     1468 2023-06-26 05:44:59.000000 jcci-0.0.3/src/jcci.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      224 2023-06-26 05:44:59.000000 jcci-0.0.3/src/jcci.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-26 05:44:59.000000 jcci-0.0.3/src/jcci.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0        5 2023-06-26 05:44:59.000000 jcci-0.0.3/src/jcci.egg-info/top_level.txt
+drwxrwxrwx   0        0        0        0 2023-06-28 11:10:53.264125 jcci-0.0.4/
+-rw-rw-rw-   0        0        0        0 2022-09-20 03:06:31.000000 jcci-0.0.4/LICENSE
+-rw-rw-rw-   0        0        0     1468 2023-06-28 11:10:53.263138 jcci-0.0.4/PKG-INFO
+-rw-rw-rw-   0        0        0      955 2023-06-26 05:36:35.000000 jcci-0.0.4/README.md
+-rw-rw-rw-   0        0        0      695 2023-06-28 11:10:41.000000 jcci-0.0.4/pyproject.toml
+-rw-rw-rw-   0        0        0       42 2023-06-28 11:10:53.264125 jcci-0.0.4/setup.cfg
+drwxrwxrwx   0        0        0        0 2023-06-28 11:10:53.248137 jcci-0.0.4/src/
+drwxrwxrwx   0        0        0        0 2023-06-28 11:10:53.254125 jcci-0.0.4/src/jcci/
+-rw-rw-rw-   0        0        0        0 2022-09-20 03:04:57.000000 jcci-0.0.4/src/jcci/__init__.py
+-rw-rw-rw-   0        0        0     2083 2023-06-25 09:25:01.000000 jcci-0.0.4/src/jcci/java_analyzer.py
+-rw-rw-rw-   0        0        0    41682 2023-06-26 05:17:01.000000 jcci-0.0.4/src/jcci/jcci.py
+drwxrwxrwx   0        0        0        0 2023-06-28 11:10:53.262124 jcci-0.0.4/src/jcci.egg-info/
+-rw-rw-rw-   0        0        0     1468 2023-06-28 11:10:53.000000 jcci-0.0.4/src/jcci.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      255 2023-06-28 11:10:53.000000 jcci-0.0.4/src/jcci.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 11:10:53.000000 jcci-0.0.4/src/jcci.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       32 2023-06-28 11:10:53.000000 jcci-0.0.4/src/jcci.egg-info/requires.txt
+-rw-rw-rw-   0        0        0        5 2023-06-28 11:10:53.000000 jcci-0.0.4/src/jcci.egg-info/top_level.txt
```

### Comparing `jcci-0.0.3/PKG-INFO` & `jcci-0.0.4/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: jcci
-Version: 0.0.3
+Version: 0.0.4
 Summary: Java code commit impact in pure Python
 Author-email: Quan Li <441640312@qq.com>
 Project-URL: Homepage, https://github.com/baikaishuipp/jcci
 Project-URL: Bug Tracker, https://github.com/baikaishuipp/jcci/issues
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```

### Comparing `jcci-0.0.3/README.md` & `jcci-0.0.4/README.md`

 * *Files identical despite different names*

### Comparing `jcci-0.0.3/pyproject.toml` & `jcci-0.0.4/pyproject.toml`

 * *Files 16% similar despite different names*

```diff
@@ -1,23 +1,27 @@
 [build-system]
-requires = ["setuptools>=61.0", "javalang>=0.13.0", "unidiff>=0.7.4"]
+requires = ["setuptools>=61.0"]
 build-backend = "setuptools.build_meta"
 
 [project]
 name = "jcci"
-version = "0.0.3"
+version = "0.0.4"
 authors = [
   { name="Quan Li", email="441640312@qq.com" },
 ]
 description = "Java code commit impact in pure Python"
 readme = "README.md"
 license = { file="LICENSE" }
 requires-python = ">=3.7"
 classifiers = [
     "Programming Language :: Python :: 3",
     "License :: OSI Approved :: MIT License",
     "Operating System :: OS Independent",
 ]
+dependencies = [
+    "javalang >= 0.13.0",
+    "unidiff >= 0.7.4"
+]
 
 [project.urls]
 "Homepage" = "https://github.com/baikaishuipp/jcci"
 "Bug Tracker" = "https://github.com/baikaishuipp/jcci/issues"
```

### Comparing `jcci-0.0.3/src/jcci/java_analyzer.py` & `jcci-0.0.4/src/jcci/java_analyzer.py`

 * *Files identical despite different names*

### Comparing `jcci-0.0.3/src/jcci/jcci.py` & `jcci-0.0.4/src/jcci/jcci.py`

 * *Files identical despite different names*

### Comparing `jcci-0.0.3/src/jcci.egg-info/PKG-INFO` & `jcci-0.0.4/src/jcci.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: jcci
-Version: 0.0.3
+Version: 0.0.4
 Summary: Java code commit impact in pure Python
 Author-email: Quan Li <441640312@qq.com>
 Project-URL: Homepage, https://github.com/baikaishuipp/jcci
 Project-URL: Bug Tracker, https://github.com/baikaishuipp/jcci/issues
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```

