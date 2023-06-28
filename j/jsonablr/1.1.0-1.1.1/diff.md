# Comparing `tmp/jsonablr-1.1.0.tar.gz` & `tmp/jsonablr-1.1.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "jsonablr-1.1.0.tar", max compression
+gzip compressed data, was "jsonablr-1.1.1.tar", max compression
```

## Comparing `jsonablr-1.1.0.tar` & `jsonablr-1.1.1.tar`

### file list

```diff
@@ -1,6 +1,6 @@
--rw-r--r--   0        0        0     1076 2023-06-26 17:24:04.431422 jsonablr-1.1.0/LICENSE
--rw-r--r--   0        0        0     1870 2023-06-26 21:39:00.368116 jsonablr-1.1.0/README.md
--rw-r--r--   0        0        0      118 2023-06-27 16:27:20.064626 jsonablr-1.1.0/jsonablr/__init__.py
--rw-r--r--   0        0        0     6822 2023-06-27 16:28:38.207825 jsonablr-1.1.0/jsonablr/main.py
--rw-r--r--   0        0        0      561 2023-06-27 16:32:21.155708 jsonablr-1.1.0/pyproject.toml
--rw-r--r--   0        0        0     2501 1970-01-01 00:00:00.000000 jsonablr-1.1.0/PKG-INFO
+-rw-r--r--   0        0        0     1076 2023-06-26 17:24:04.431422 jsonablr-1.1.1/LICENSE
+-rw-r--r--   0        0        0     1870 2023-06-26 21:39:00.368116 jsonablr-1.1.1/README.md
+-rw-r--r--   0        0        0      118 2023-06-27 16:27:20.064626 jsonablr-1.1.1/jsonablr/__init__.py
+-rw-r--r--   0        0        0     6822 2023-06-27 16:28:38.207825 jsonablr-1.1.1/jsonablr/main.py
+-rw-r--r--   0        0        0      561 2023-06-28 13:06:28.936110 jsonablr-1.1.1/pyproject.toml
+-rw-r--r--   0        0        0     2551 1970-01-01 00:00:00.000000 jsonablr-1.1.1/PKG-INFO
```

### Comparing `jsonablr-1.1.0/LICENSE` & `jsonablr-1.1.1/LICENSE`

 * *Files identical despite different names*

### Comparing `jsonablr-1.1.0/README.md` & `jsonablr-1.1.1/README.md`

 * *Files identical despite different names*

### Comparing `jsonablr-1.1.0/jsonablr/main.py` & `jsonablr-1.1.1/jsonablr/main.py`

 * *Files identical despite different names*

### Comparing `jsonablr-1.1.0/pyproject.toml` & `jsonablr-1.1.1/pyproject.toml`

 * *Files 18% similar despite different names*

```diff
@@ -1,18 +1,18 @@
 [tool.poetry]
 authors = ["Bernard van Niekerk <bernard.van.niekerk@icloud.com>"]
 description = "Serialize Pydantic models and non-JSONable types into a JSONable variable."
 name = "jsonablr"
 readme = "README.md"
 repository = "https://github.com/frizzy/jsonablr.git"
-version = "1.1.0"
+version = "1.1.1"
 
 [tool.poetry.dependencies]
 pydantic = "^1.10"
-python = "^3.9"
+python = "^3.8"
 
 [tool.poetry.group.test]
 optional = true
 
 [tool.poetry.group.test.dependencies]
 pytest = "^7.4.0"
```

### Comparing `jsonablr-1.1.0/PKG-INFO` & `jsonablr-1.1.1/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,16 +1,17 @@
 Metadata-Version: 2.1
 Name: jsonablr
-Version: 1.1.0
+Version: 1.1.1
 Summary: Serialize Pydantic models and non-JSONable types into a JSONable variable.
 Home-page: https://github.com/frizzy/jsonablr.git
 Author: Bernard van Niekerk
 Author-email: bernard.van.niekerk@icloud.com
-Requires-Python: >=3.9,<4.0
+Requires-Python: >=3.8,<4.0
 Classifier: Programming Language :: Python :: 3
+Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
 Requires-Dist: pydantic (>=1.10,<2.0)
 Project-URL: Repository, https://github.com/frizzy/jsonablr.git
 Description-Content-Type: text/markdown
```

