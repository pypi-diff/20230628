# Comparing `tmp/efcamdat-0.0.2.tar.gz` & `tmp/efcamdat-0.0.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "efcamdat-0.0.2.tar", max compression
+gzip compressed data, was "efcamdat-0.0.3.tar", max compression
```

## Comparing `efcamdat-0.0.2.tar` & `efcamdat-0.0.3.tar`

### file list

```diff
@@ -1,7 +1,7 @@
--rw-r--r--   0        0        0     1074 2023-06-28 11:18:03.859806 efcamdat-0.0.2/LICENSE
--rw-r--r--   0        0        0      209 2023-06-28 11:17:36.112139 efcamdat-0.0.2/README.md
--rw-r--r--   0        0        0      650 2023-06-28 15:14:41.420651 efcamdat-0.0.2/pyproject.toml
--rw-r--r--   0        0        0        0 2023-06-28 11:11:07.423621 efcamdat-0.0.2/src/efcamdat/__init__.py
--rw-r--r--   0        0        0      290 2023-06-28 15:04:22.609947 efcamdat-0.0.2/src/efcamdat/cli.py
--rw-r--r--   0        0        0       80 2023-06-28 13:18:25.911321 efcamdat-0.0.2/src/efcamdat/transform.py
--rw-r--r--   0        0        0      955 1970-01-01 00:00:00.000000 efcamdat-0.0.2/PKG-INFO
+-rw-r--r--   0        0        0     1074 2023-06-28 11:18:03.859806 efcamdat-0.0.3/LICENSE
+-rw-r--r--   0        0        0      209 2023-06-28 11:17:36.112139 efcamdat-0.0.3/README.md
+-rw-r--r--   0        0        0      651 2023-06-28 15:31:04.408756 efcamdat-0.0.3/pyproject.toml
+-rw-r--r--   0        0        0        0 2023-06-28 11:11:07.423621 efcamdat-0.0.3/src/efcamdat/__init__.py
+-rw-r--r--   0        0        0      290 2023-06-28 15:04:22.609947 efcamdat-0.0.3/src/efcamdat/cli.py
+-rw-r--r--   0        0        0       80 2023-06-28 13:18:25.911321 efcamdat-0.0.3/src/efcamdat/transform.py
+-rw-r--r--   0        0        0      955 1970-01-01 00:00:00.000000 efcamdat-0.0.3/PKG-INFO
```

### Comparing `efcamdat-0.0.2/LICENSE` & `efcamdat-0.0.3/LICENSE`

 * *Files identical despite different names*

### Comparing `efcamdat-0.0.2/pyproject.toml` & `efcamdat-0.0.3/pyproject.toml`

 * *Files 5% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "EFCAMDAT"
-version = "0.0.2"
+version = "0.0.3"
 authors = [ "Bernardo Stearns <bernardo.stearns@gmail.com>" ]
 description = "A library for doing all preprocessing related to EFCAMDAT"
 readme = "README.md"
 classifiers = [
     "Programming Language :: Python :: 3",
     "License :: OSI Approved :: MIT License",
     "Operating System :: OS Independent",
@@ -12,16 +12,16 @@
 
 [tool.poetry.dependencies]
 python = "^3.6"
 typer = {extras = ["all"], version = "^0.1.0"}
 
 [tool.poetry.dev-dependencies]
 pytest = "^5.2"
-poetry = "^1.5"
+twine = "^4.0.2"
 
 [tool.poetry.scripts]
-efcamdat_cli = "EFCAMDAT.cli:app"
+efcamdat_cli = "efcamdat.cli:app"
 
 [build-system]
 requires = ["poetry>=0.12"]
 build-backend = "poetry.masonry.api"
```

### Comparing `efcamdat-0.0.2/PKG-INFO` & `efcamdat-0.0.3/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: efcamdat
-Version: 0.0.2
+Version: 0.0.3
 Summary: A library for doing all preprocessing related to EFCAMDAT
 Author: Bernardo Stearns
 Author-email: bernardo.stearns@gmail.com
 Requires-Python: >=3.6,<4.0
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
 Classifier: Programming Language :: Python :: 3
```

