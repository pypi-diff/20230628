# Comparing `tmp/pdf_oralia-0.3.tar.gz` & `tmp/pdf_oralia-0.3.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pdf_oralia-0.3.tar", max compression
+gzip compressed data, was "pdf_oralia-0.3.1.tar", max compression
```

## Comparing `pdf_oralia-0.3.tar` & `pdf_oralia-0.3.1.tar`

### file list

```diff
@@ -1,11 +1,11 @@
--rw-r--r--   0        0        0       73 2023-06-27 10:04:02.619132 pdf_oralia-0.3/README.md
--rw-r--r--   0        0        0        0 2023-06-27 10:04:02.619132 pdf_oralia-0.3/pdf_oralia/__init__.py
--rw-r--r--   0        0        0     3056 2023-06-27 10:04:02.619132 pdf_oralia-0.3/pdf_oralia/extract.py
--rw-r--r--   0        0        0       59 2023-06-27 10:04:02.619132 pdf_oralia-0.3/pdf_oralia/pages/__init__.py
--rw-r--r--   0        0        0     1788 2023-06-27 10:04:02.619132 pdf_oralia-0.3/pdf_oralia/pages/charge.py
--rw-r--r--   0        0        0     3636 2023-06-27 10:04:02.623132 pdf_oralia-0.3/pdf_oralia/pages/locataire.py
--rw-r--r--   0        0        0       99 2023-06-27 10:04:02.623132 pdf_oralia-0.3/pdf_oralia/pages/patrimoine.py
--rw-r--r--   0        0        0      904 2023-06-27 10:04:02.623132 pdf_oralia-0.3/pdf_oralia/pages/recapitulatif.py
--rw-r--r--   0        0        0     1591 2023-06-27 10:04:02.623132 pdf_oralia-0.3/pdf_oralia/scripts.py
--rw-r--r--   0        0        0      561 2023-06-27 10:04:06.202934 pdf_oralia-0.3/pyproject.toml
--rw-r--r--   0        0        0      587 1970-01-01 00:00:00.000000 pdf_oralia-0.3/PKG-INFO
+-rw-r--r--   0        0        0       73 2023-06-28 07:41:54.091433 pdf_oralia-0.3.1/README.md
+-rw-r--r--   0        0        0        0 2023-06-28 07:41:54.091433 pdf_oralia-0.3.1/pdf_oralia/__init__.py
+-rw-r--r--   0        0        0     3056 2023-06-28 07:41:54.091433 pdf_oralia-0.3.1/pdf_oralia/extract.py
+-rw-r--r--   0        0        0       59 2023-06-28 07:41:54.091433 pdf_oralia-0.3.1/pdf_oralia/pages/__init__.py
+-rw-r--r--   0        0        0     1788 2023-06-28 07:41:54.091433 pdf_oralia-0.3.1/pdf_oralia/pages/charge.py
+-rw-r--r--   0        0        0     3636 2023-06-28 07:41:54.091433 pdf_oralia-0.3.1/pdf_oralia/pages/locataire.py
+-rw-r--r--   0        0        0       99 2023-06-28 07:41:54.091433 pdf_oralia-0.3.1/pdf_oralia/pages/patrimoine.py
+-rw-r--r--   0        0        0      904 2023-06-28 07:41:54.091433 pdf_oralia-0.3.1/pdf_oralia/pages/recapitulatif.py
+-rw-r--r--   0        0        0     1542 2023-06-28 07:41:54.091433 pdf_oralia-0.3.1/pdf_oralia/scripts.py
+-rw-r--r--   0        0        0      563 2023-06-28 07:41:57.947221 pdf_oralia-0.3.1/pyproject.toml
+-rw-r--r--   0        0        0      589 1970-01-01 00:00:00.000000 pdf_oralia-0.3.1/PKG-INFO
```

### Comparing `pdf_oralia-0.3/pdf_oralia/extract.py` & `pdf_oralia-0.3.1/pdf_oralia/extract.py`

 * *Files identical despite different names*

### Comparing `pdf_oralia-0.3/pdf_oralia/pages/charge.py` & `pdf_oralia-0.3.1/pdf_oralia/pages/charge.py`

 * *Files identical despite different names*

### Comparing `pdf_oralia-0.3/pdf_oralia/pages/locataire.py` & `pdf_oralia-0.3.1/pdf_oralia/pages/locataire.py`

 * *Files identical despite different names*

### Comparing `pdf_oralia-0.3/pdf_oralia/pages/recapitulatif.py` & `pdf_oralia-0.3.1/pdf_oralia/pages/recapitulatif.py`

 * *Files identical despite different names*

### Comparing `pdf_oralia-0.3/pdf_oralia/scripts.py` & `pdf_oralia-0.3.1/pdf_oralia/scripts.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,16 +1,14 @@
 import logging
 from logging.config import dictConfig
 from pathlib import Path
 
 import click
-import pandas as pd
 
 from .extract import extract_save
-from .join import join_excel
 
 logging_config = dict(
     version=1,
     formatters={"f": {"format": "%(levelname)-8s %(name)-12s %(message)s"}},
     handlers={
         "h": {
             "class": "logging.StreamHandler",
```

### Comparing `pdf_oralia-0.3/pyproject.toml` & `pdf_oralia-0.3.1/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "pdf-oralia"
-version = "v0.3"
+version = "v0.3.1"
 description = ""
 authors = ["Bertrand Benjamin <benjamin.bertrand@opytex.org>"]
 readme = "README.md"
 packages = [{include = "pdf_oralia"}]
 
 [tool.poetry.scripts]
 pdf-oralia = "pdf_oralia.scripts:main"
```

### Comparing `pdf_oralia-0.3/PKG-INFO` & `pdf_oralia-0.3.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pdf-oralia
-Version: 0.3
+Version: 0.3.1
 Summary: 
 Author: Bertrand Benjamin
 Author-email: benjamin.bertrand@opytex.org
 Requires-Python: >=3.10,<4.0
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
```

