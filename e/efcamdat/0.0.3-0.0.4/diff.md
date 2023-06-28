# Comparing `tmp/efcamdat-0.0.3.tar.gz` & `tmp/efcamdat-0.0.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "efcamdat-0.0.3.tar", max compression
+gzip compressed data, was "efcamdat-0.0.4.tar", max compression
```

## Comparing `efcamdat-0.0.3.tar` & `efcamdat-0.0.4.tar`

### file list

```diff
@@ -1,7 +1,7 @@
--rw-r--r--   0        0        0     1074 2023-06-28 11:18:03.859806 efcamdat-0.0.3/LICENSE
--rw-r--r--   0        0        0      209 2023-06-28 11:17:36.112139 efcamdat-0.0.3/README.md
--rw-r--r--   0        0        0      651 2023-06-28 15:31:04.408756 efcamdat-0.0.3/pyproject.toml
--rw-r--r--   0        0        0        0 2023-06-28 11:11:07.423621 efcamdat-0.0.3/src/efcamdat/__init__.py
--rw-r--r--   0        0        0      290 2023-06-28 15:04:22.609947 efcamdat-0.0.3/src/efcamdat/cli.py
--rw-r--r--   0        0        0       80 2023-06-28 13:18:25.911321 efcamdat-0.0.3/src/efcamdat/transform.py
--rw-r--r--   0        0        0      955 1970-01-01 00:00:00.000000 efcamdat-0.0.3/PKG-INFO
+-rw-r--r--   0        0        0     1074 2023-06-28 11:18:03.859806 efcamdat-0.0.4/LICENSE
+-rw-r--r--   0        0        0      209 2023-06-28 11:17:36.112139 efcamdat-0.0.4/README.md
+-rw-r--r--   0        0        0        0 2023-06-28 11:11:07.423621 efcamdat-0.0.4/efcamdat/__init__.py
+-rw-r--r--   0        0        0      290 2023-06-28 15:31:55.837660 efcamdat-0.0.4/efcamdat/cli.py
+-rw-r--r--   0        0        0       80 2023-06-28 15:31:57.111424 efcamdat-0.0.4/efcamdat/transform.py
+-rw-r--r--   0        0        0      651 2023-06-28 15:36:43.747455 efcamdat-0.0.4/pyproject.toml
+-rw-r--r--   0        0        0      955 1970-01-01 00:00:00.000000 efcamdat-0.0.4/PKG-INFO
```

### Comparing `efcamdat-0.0.3/LICENSE` & `efcamdat-0.0.4/LICENSE`

 * *Files identical despite different names*

### Comparing `efcamdat-0.0.3/pyproject.toml` & `efcamdat-0.0.4/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "EFCAMDAT"
-version = "0.0.3"
+version = "0.0.4"
 authors = [ "Bernardo Stearns <bernardo.stearns@gmail.com>" ]
 description = "A library for doing all preprocessing related to EFCAMDAT"
 readme = "README.md"
 classifiers = [
     "Programming Language :: Python :: 3",
     "License :: OSI Approved :: MIT License",
     "Operating System :: OS Independent",
```

### Comparing `efcamdat-0.0.3/PKG-INFO` & `efcamdat-0.0.4/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: efcamdat
-Version: 0.0.3
+Version: 0.0.4
 Summary: A library for doing all preprocessing related to EFCAMDAT
 Author: Bernardo Stearns
 Author-email: bernardo.stearns@gmail.com
 Requires-Python: >=3.6,<4.0
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
 Classifier: Programming Language :: Python :: 3
```

