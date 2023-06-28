# Comparing `tmp/sortinghat_openinfra-0.1.6.tar.gz` & `tmp/sortinghat_openinfra-0.1.7.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "sortinghat_openinfra-0.1.6.tar", max compression
+gzip compressed data, was "sortinghat_openinfra-0.1.7.tar", max compression
```

## Comparing `sortinghat_openinfra-0.1.6.tar` & `sortinghat_openinfra-0.1.7.tar`

### file list

```diff
@@ -1,12 +1,12 @@
--rw-r--r--   0        0        0    35149 2023-05-18 12:01:14.567303 sortinghat_openinfra-0.1.6/LICENSE
--rw-r--r--   0        0        0     2244 2023-05-18 12:01:14.567303 sortinghat_openinfra-0.1.6/README.md
--rw-r--r--   0        0        0     1248 2023-05-18 12:01:14.567303 sortinghat_openinfra-0.1.6/pyproject.toml
--rw-r--r--   0        0        0       86 2023-05-18 12:01:14.567303 sortinghat_openinfra-0.1.6/sortinghat/core/importer/backends/_version.py
--rw-r--r--   0        0        0     7917 2023-05-18 12:01:14.567303 sortinghat_openinfra-0.1.6/sortinghat/core/importer/backends/openinfra.py
--rw-r--r--   0        0        0        0 2023-05-18 12:01:14.567303 sortinghat_openinfra-0.1.6/tests/__init__.py
--rw-r--r--   0        0        0     6403 2023-05-18 12:01:14.567303 sortinghat_openinfra-0.1.6/tests/data/openinfra_page_1.json
--rw-r--r--   0        0        0     5073 2023-05-18 12:01:14.567303 sortinghat_openinfra-0.1.6/tests/data/openinfra_page_2.json
--rw-r--r--   0        0        0     2595 2023-05-18 12:01:14.567303 sortinghat_openinfra-0.1.6/tests/data/openinfra_private.json
--rw-r--r--   0        0        0      143 2023-05-18 12:01:14.567303 sortinghat_openinfra-0.1.6/tests/data/openinfra_token_error.json
--rw-r--r--   0        0        0    21169 2023-05-18 12:01:14.567303 sortinghat_openinfra-0.1.6/tests/test_openinfra.py
--rw-r--r--   0        0        0     3407 1970-01-01 00:00:00.000000 sortinghat_openinfra-0.1.6/PKG-INFO
+-rw-r--r--   0        0        0    35149 2023-06-28 14:15:24.551506 sortinghat_openinfra-0.1.7/LICENSE
+-rw-r--r--   0        0        0     2244 2023-06-28 14:15:24.551506 sortinghat_openinfra-0.1.7/README.md
+-rw-r--r--   0        0        0     1248 2023-06-28 14:15:24.555506 sortinghat_openinfra-0.1.7/pyproject.toml
+-rw-r--r--   0        0        0       86 2023-06-28 14:15:24.555506 sortinghat_openinfra-0.1.7/sortinghat/core/importer/backends/_version.py
+-rw-r--r--   0        0        0     7917 2023-06-28 14:15:24.555506 sortinghat_openinfra-0.1.7/sortinghat/core/importer/backends/openinfra.py
+-rw-r--r--   0        0        0        0 2023-06-28 14:15:24.555506 sortinghat_openinfra-0.1.7/tests/__init__.py
+-rw-r--r--   0        0        0     6403 2023-06-28 14:15:24.555506 sortinghat_openinfra-0.1.7/tests/data/openinfra_page_1.json
+-rw-r--r--   0        0        0     5073 2023-06-28 14:15:24.555506 sortinghat_openinfra-0.1.7/tests/data/openinfra_page_2.json
+-rw-r--r--   0        0        0     2595 2023-06-28 14:15:24.555506 sortinghat_openinfra-0.1.7/tests/data/openinfra_private.json
+-rw-r--r--   0        0        0      143 2023-06-28 14:15:24.555506 sortinghat_openinfra-0.1.7/tests/data/openinfra_token_error.json
+-rw-r--r--   0        0        0    21169 2023-06-28 14:15:24.555506 sortinghat_openinfra-0.1.7/tests/test_openinfra.py
+-rw-r--r--   0        0        0     3359 1970-01-01 00:00:00.000000 sortinghat_openinfra-0.1.7/PKG-INFO
```

### Comparing `sortinghat_openinfra-0.1.6/LICENSE` & `sortinghat_openinfra-0.1.7/LICENSE`

 * *Files identical despite different names*

### Comparing `sortinghat_openinfra-0.1.6/README.md` & `sortinghat_openinfra-0.1.7/README.md`

 * *Files identical despite different names*

### Comparing `sortinghat_openinfra-0.1.6/pyproject.toml` & `sortinghat_openinfra-0.1.7/pyproject.toml`

 * *Files 8% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "sortinghat-openinfra"
-version = "0.1.6"
+version = "0.1.7"
 description = "SortingHat backend to import identities from OpenInfraID"
 authors = [
     "Bitergia Developers"
 ]
 license = "GPL-3.0+"
 
 readme = "README.md"
```

### Comparing `sortinghat_openinfra-0.1.6/sortinghat/core/importer/backends/openinfra.py` & `sortinghat_openinfra-0.1.7/sortinghat/core/importer/backends/openinfra.py`

 * *Files identical despite different names*

### Comparing `sortinghat_openinfra-0.1.6/tests/data/openinfra_page_1.json` & `sortinghat_openinfra-0.1.7/tests/data/openinfra_page_1.json`

 * *Files identical despite different names*

### Comparing `sortinghat_openinfra-0.1.6/tests/data/openinfra_page_2.json` & `sortinghat_openinfra-0.1.7/tests/data/openinfra_page_2.json`

 * *Files identical despite different names*

### Comparing `sortinghat_openinfra-0.1.6/tests/data/openinfra_private.json` & `sortinghat_openinfra-0.1.7/tests/data/openinfra_private.json`

 * *Files identical despite different names*

### Comparing `sortinghat_openinfra-0.1.6/tests/test_openinfra.py` & `sortinghat_openinfra-0.1.7/tests/test_openinfra.py`

 * *Files identical despite different names*

### Comparing `sortinghat_openinfra-0.1.6/PKG-INFO` & `sortinghat_openinfra-0.1.7/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: sortinghat-openinfra
-Version: 0.1.6
+Version: 0.1.7
 Summary: SortingHat backend to import identities from OpenInfraID
 Home-page: https://chaoss.github.io/grimoirelab/
 License: GPL-3.0+
 Keywords: development,grimoirelab,sortinghat
 Author: Bitergia Developers
 Requires-Python: >=3.7.1,<4.0.0
 Classifier: Development Status :: 4 - Beta
@@ -12,15 +12,14 @@
 Classifier: Intended Audience :: Science/Research
 Classifier: License :: OSI Approved :: GNU General Public License v3 or later (GPLv3+)
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
-Classifier: Programming Language :: Python :: 3
 Classifier: Topic :: Software Development
 Requires-Dist: grimoirelab-toolkit (>=0.3)
 Requires-Dist: sortinghat (>=0.8.1)
 Project-URL: Bug Tracker, https://github.com/bitergia-analytics/sortinghat-openinfra/issues
 Project-URL: Repository, https://github.com/bitergia-analytics/sortinghat-openinfra
 Description-Content-Type: text/markdown
```

