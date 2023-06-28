# Comparing `tmp/pushcart_deploy-1.5.1.tar.gz` & `tmp/pushcart_deploy-1.6.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pushcart_deploy-1.5.1.tar", max compression
+gzip compressed data, was "pushcart_deploy-1.6.0.tar", max compression
```

## Comparing `pushcart_deploy-1.5.1.tar` & `pushcart_deploy-1.6.0.tar`

### file list

```diff
@@ -1,19 +1,19 @@
--rw-r--r--   0        0        0    35149 2023-06-07 20:53:48.103196 pushcart_deploy-1.5.1/LICENSE
--rw-r--r--   0        0        0       80 2023-06-07 20:53:48.103196 pushcart_deploy-1.5.1/README.md
--rw-r--r--   0        0        0     2502 2023-06-07 20:55:12.632576 pushcart_deploy-1.5.1/pyproject.toml
--rw-r--r--   0        0        0      483 2023-06-07 20:53:48.103196 pushcart_deploy-1.5.1/src/pushcart_deploy/__init__.py
--rw-r--r--   0        0        0    15944 2023-06-07 20:53:48.103196 pushcart_deploy-1.5.1/src/pushcart_deploy/configuration.py
--rw-r--r--   0        0        0      500 2023-06-07 20:53:48.103196 pushcart_deploy-1.5.1/src/pushcart_deploy/databricks_api/__init__.py
--rw-r--r--   0        0        0     3482 2023-06-07 20:53:48.103196 pushcart_deploy-1.5.1/src/pushcart_deploy/databricks_api/jobs_wrapper.py
--rw-r--r--   0        0        0     4706 2023-06-07 20:53:48.103196 pushcart_deploy-1.5.1/src/pushcart_deploy/databricks_api/pipelines_wrapper.py
--rw-r--r--   0        0        0     4496 2023-06-07 20:53:48.103196 pushcart_deploy-1.5.1/src/pushcart_deploy/databricks_api/repos_wrapper.py
--rw-r--r--   0        0        0    12091 2023-06-07 20:53:48.103196 pushcart_deploy-1.5.1/src/pushcart_deploy/databricks_api/scheduler.py
--rw-r--r--   0        0        0     3173 2023-06-07 20:53:48.107196 pushcart_deploy-1.5.1/src/pushcart_deploy/databricks_api/secrets_wrapper.py
--rw-r--r--   0        0        0      254 2023-06-07 20:53:48.107196 pushcart_deploy-1.5.1/src/pushcart_deploy/databricks_api/settings/__init__.py
--rw-r--r--   0        0        0     4385 2023-06-07 20:53:48.107196 pushcart_deploy-1.5.1/src/pushcart_deploy/databricks_api/settings/base_settings.py
--rw-r--r--   0        0        0     4175 2023-06-07 20:53:48.107196 pushcart_deploy-1.5.1/src/pushcart_deploy/databricks_api/settings/job_settings.py
--rw-r--r--   0        0        0     6882 2023-06-07 20:53:48.107196 pushcart_deploy-1.5.1/src/pushcart_deploy/databricks_api/settings/pipeline_settings.py
--rw-r--r--   0        0        0     9661 2023-06-07 20:53:48.107196 pushcart_deploy-1.5.1/src/pushcart_deploy/metadata.py
--rw-r--r--   0        0        0     4201 2023-06-07 20:53:48.107196 pushcart_deploy-1.5.1/src/pushcart_deploy/setup.py
--rw-r--r--   0        0        0     3397 2023-06-07 20:53:48.107196 pushcart_deploy-1.5.1/src/pushcart_deploy/validation.py
--rw-r--r--   0        0        0     1285 1970-01-01 00:00:00.000000 pushcart_deploy-1.5.1/PKG-INFO
+-rw-r--r--   0        0        0    35149 2023-06-28 12:03:16.429340 pushcart_deploy-1.6.0/LICENSE
+-rw-r--r--   0        0        0       80 2023-06-28 12:03:16.429340 pushcart_deploy-1.6.0/README.md
+-rw-r--r--   0        0        0     2502 2023-06-28 12:05:08.686186 pushcart_deploy-1.6.0/pyproject.toml
+-rw-r--r--   0        0        0      483 2023-06-28 12:03:16.429340 pushcart_deploy-1.6.0/src/pushcart_deploy/__init__.py
+-rw-r--r--   0        0        0    16356 2023-06-28 12:03:16.429340 pushcart_deploy-1.6.0/src/pushcart_deploy/configuration.py
+-rw-r--r--   0        0        0      500 2023-06-28 12:03:16.429340 pushcart_deploy-1.6.0/src/pushcart_deploy/databricks_api/__init__.py
+-rw-r--r--   0        0        0     3482 2023-06-28 12:03:16.429340 pushcart_deploy-1.6.0/src/pushcart_deploy/databricks_api/jobs_wrapper.py
+-rw-r--r--   0        0        0     4706 2023-06-28 12:03:16.429340 pushcart_deploy-1.6.0/src/pushcart_deploy/databricks_api/pipelines_wrapper.py
+-rw-r--r--   0        0        0     4496 2023-06-28 12:03:16.429340 pushcart_deploy-1.6.0/src/pushcart_deploy/databricks_api/repos_wrapper.py
+-rw-r--r--   0        0        0    12091 2023-06-28 12:03:16.429340 pushcart_deploy-1.6.0/src/pushcart_deploy/databricks_api/scheduler.py
+-rw-r--r--   0        0        0     3173 2023-06-28 12:03:16.429340 pushcart_deploy-1.6.0/src/pushcart_deploy/databricks_api/secrets_wrapper.py
+-rw-r--r--   0        0        0      254 2023-06-28 12:03:16.429340 pushcart_deploy-1.6.0/src/pushcart_deploy/databricks_api/settings/__init__.py
+-rw-r--r--   0        0        0     4385 2023-06-28 12:03:16.429340 pushcart_deploy-1.6.0/src/pushcart_deploy/databricks_api/settings/base_settings.py
+-rw-r--r--   0        0        0     4175 2023-06-28 12:03:16.429340 pushcart_deploy-1.6.0/src/pushcart_deploy/databricks_api/settings/job_settings.py
+-rw-r--r--   0        0        0     6882 2023-06-28 12:03:16.433340 pushcart_deploy-1.6.0/src/pushcart_deploy/databricks_api/settings/pipeline_settings.py
+-rw-r--r--   0        0        0     9661 2023-06-28 12:03:16.433340 pushcart_deploy-1.6.0/src/pushcart_deploy/metadata.py
+-rw-r--r--   0        0        0     4201 2023-06-28 12:03:16.433340 pushcart_deploy-1.6.0/src/pushcart_deploy/setup.py
+-rw-r--r--   0        0        0     3397 2023-06-28 12:03:16.433340 pushcart_deploy-1.6.0/src/pushcart_deploy/validation.py
+-rw-r--r--   0        0        0     1285 1970-01-01 00:00:00.000000 pushcart_deploy-1.6.0/PKG-INFO
```

### Comparing `pushcart_deploy-1.5.1/LICENSE` & `pushcart_deploy-1.6.0/LICENSE`

 * *Files identical despite different names*

### Comparing `pushcart_deploy-1.5.1/pyproject.toml` & `pushcart_deploy-1.6.0/pyproject.toml`

 * *Files 5% similar despite different names*

```diff
@@ -74,15 +74,15 @@
   "YTT",
 ]
 unfixable = []
 exclude = [".venv", "tests"]
 
 [tool.poetry]
 name = "pushcart-deploy"
-version = "1.5.1"
+version = "1.6.0"
 description = "Deployment helper for pipeline configurations using Pushcart"
 authors = ["Georgel Preput <georgelpreput@mailbox.org>"]
 license = "GPL-3.0-or-later"
 readme = "README.md"
 classifiers = [
   "Programming Language :: Python :: 3.10",
   "License :: OSI Approved :: GNU General Public License v3 or later (GPLv3+)",
```

### Comparing `pushcart_deploy-1.5.1/src/pushcart_deploy/configuration.py` & `pushcart_deploy-1.6.0/src/pushcart_deploy/configuration.py`

 * *Files 6% similar despite different names*

```diff
@@ -12,25 +12,25 @@
 Notes:
 -----
 Configuration must have at least one stage (Source, Transformation, Destination) of the
 data pipeline defined.
 
 """
 
-import csv
 import json
 import logging
 import os
 from collections import defaultdict
 from collections.abc import AsyncIterator
 from io import StringIO
 from itertools import groupby
 from pathlib import Path
 
 import aiofiles
+import pandas as pd
 import tomli
 import yaml
 from pydantic import (
     Field,
     conint,
     constr,
     dataclasses,
@@ -57,20 +57,34 @@
     ------
     Iterator[AsyncIterator[dict]]
         One row containing details for one transformation step
     """
     if isinstance(csv_path, str):
         csv_path = Path(csv_path)
 
+    types_dict = {
+        "column_order": int,
+        "source_column_name": str,
+        "source_column_type": str,
+        "dest_column_name": str,
+        "dest_column_type": str,
+        "transform_function": str,
+        "default_value": str,
+        "validation_rule": str,
+        "validation_action": str,
+    }
+
     async with aiofiles.open(csv_path, "r") as aio_file:
         contents = await aio_file.read()
         csv_file = StringIO(contents)
-        reader = csv.DictReader(csv_file)
 
-        for row in reader:
+        csv_df = pd.read_csv(csv_file, dtype=types_dict).fillna("")
+        csv_dict = csv_df.to_dict(orient="records")
+
+        for row in csv_dict:
             yield row
 
 
 async def get_transformations_from_sql(sql_path: Path | str) -> str:
     """Return transformations from SQL file.
 
     Parameters
```

### Comparing `pushcart_deploy-1.5.1/src/pushcart_deploy/databricks_api/jobs_wrapper.py` & `pushcart_deploy-1.6.0/src/pushcart_deploy/databricks_api/jobs_wrapper.py`

 * *Files identical despite different names*

### Comparing `pushcart_deploy-1.5.1/src/pushcart_deploy/databricks_api/pipelines_wrapper.py` & `pushcart_deploy-1.6.0/src/pushcart_deploy/databricks_api/pipelines_wrapper.py`

 * *Files identical despite different names*

### Comparing `pushcart_deploy-1.5.1/src/pushcart_deploy/databricks_api/repos_wrapper.py` & `pushcart_deploy-1.6.0/src/pushcart_deploy/databricks_api/repos_wrapper.py`

 * *Files identical despite different names*

### Comparing `pushcart_deploy-1.5.1/src/pushcart_deploy/databricks_api/scheduler.py` & `pushcart_deploy-1.6.0/src/pushcart_deploy/databricks_api/scheduler.py`

 * *Files identical despite different names*

### Comparing `pushcart_deploy-1.5.1/src/pushcart_deploy/databricks_api/secrets_wrapper.py` & `pushcart_deploy-1.6.0/src/pushcart_deploy/databricks_api/secrets_wrapper.py`

 * *Files identical despite different names*

### Comparing `pushcart_deploy-1.5.1/src/pushcart_deploy/databricks_api/settings/base_settings.py` & `pushcart_deploy-1.6.0/src/pushcart_deploy/databricks_api/settings/base_settings.py`

 * *Files identical despite different names*

### Comparing `pushcart_deploy-1.5.1/src/pushcart_deploy/databricks_api/settings/job_settings.py` & `pushcart_deploy-1.6.0/src/pushcart_deploy/databricks_api/settings/job_settings.py`

 * *Files identical despite different names*

### Comparing `pushcart_deploy-1.5.1/src/pushcart_deploy/databricks_api/settings/pipeline_settings.py` & `pushcart_deploy-1.6.0/src/pushcart_deploy/databricks_api/settings/pipeline_settings.py`

 * *Files identical despite different names*

### Comparing `pushcart_deploy-1.5.1/src/pushcart_deploy/metadata.py` & `pushcart_deploy-1.6.0/src/pushcart_deploy/metadata.py`

 * *Files identical despite different names*

### Comparing `pushcart_deploy-1.5.1/src/pushcart_deploy/setup.py` & `pushcart_deploy-1.6.0/src/pushcart_deploy/setup.py`

 * *Files identical despite different names*

### Comparing `pushcart_deploy-1.5.1/src/pushcart_deploy/validation.py` & `pushcart_deploy-1.6.0/src/pushcart_deploy/validation.py`

 * *Files identical despite different names*

### Comparing `pushcart_deploy-1.5.1/PKG-INFO` & `pushcart_deploy-1.6.0/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pushcart-deploy
-Version: 1.5.1
+Version: 1.6.0
 Summary: Deployment helper for pipeline configurations using Pushcart
 License: GPL-3.0-or-later
 Author: Georgel Preput
 Author-email: georgelpreput@mailbox.org
 Requires-Python: >=3.10,<4.0
 Classifier: License :: OSI Approved :: GNU General Public License v3 or later (GPLv3+)
 Classifier: Operating System :: OS Independent
```

