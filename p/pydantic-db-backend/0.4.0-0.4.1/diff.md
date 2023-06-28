# Comparing `tmp/pydantic_db_backend-0.4.0.tar.gz` & `tmp/pydantic_db_backend-0.4.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pydantic_db_backend-0.4.0.tar", max compression
+gzip compressed data, was "pydantic_db_backend-0.4.1.tar", max compression
```

## Comparing `pydantic_db_backend-0.4.0.tar` & `pydantic_db_backend-0.4.1.tar`

### file list

```diff
@@ -1,10 +1,10 @@
--rw-r--r--   0        0        0       87 2023-06-14 17:15:43.151729 pydantic_db_backend-0.4.0/README.md
--rw-r--r--   0        0        0        0 2023-05-11 08:45:17.171212 pydantic_db_backend-0.4.0/pydantic_db_backend/__init__.py
--rw-r--r--   0        0        0     6222 2023-06-28 07:49:52.142216 pydantic_db_backend-0.4.0/pydantic_db_backend/backend.py
--rw-r--r--   0        0        0        0 2023-05-13 10:06:57.338481 pydantic_db_backend-0.4.0/pydantic_db_backend/backends/__init__.py
--rw-r--r--   0        0        0     6047 2023-06-28 08:42:50.521114 pydantic_db_backend-0.4.0/pydantic_db_backend/backends/couchdb.py
--rw-r--r--   0        0        0      100 2023-06-14 12:06:00.522425 pydantic_db_backend-0.4.0/pydantic_db_backend/backends/json_files.py
--rw-r--r--   0        0        0      701 2023-06-20 16:53:47.237618 pydantic_db_backend-0.4.0/pydantic_db_backend/exceptions/__init__.py
--rw-r--r--   0        0        0     1192 2023-06-28 08:36:47.839745 pydantic_db_backend-0.4.0/pydantic_db_backend/utils.py
--rw-r--r--   0        0        0     1000 2023-06-28 09:04:32.275813 pydantic_db_backend-0.4.0/pyproject.toml
--rw-r--r--   0        0        0      766 1970-01-01 00:00:00.000000 pydantic_db_backend-0.4.0/PKG-INFO
+-rw-r--r--   0        0        0       87 2023-06-14 17:15:43.151729 pydantic_db_backend-0.4.1/README.md
+-rw-r--r--   0        0        0        0 2023-05-11 08:45:17.171212 pydantic_db_backend-0.4.1/pydantic_db_backend/__init__.py
+-rw-r--r--   0        0        0     6222 2023-06-28 07:49:52.142216 pydantic_db_backend-0.4.1/pydantic_db_backend/backend.py
+-rw-r--r--   0        0        0        0 2023-05-13 10:06:57.338481 pydantic_db_backend-0.4.1/pydantic_db_backend/backends/__init__.py
+-rw-r--r--   0        0        0     6047 2023-06-28 09:24:42.810581 pydantic_db_backend-0.4.1/pydantic_db_backend/backends/couchdb.py
+-rw-r--r--   0        0        0      100 2023-06-14 12:06:00.522425 pydantic_db_backend-0.4.1/pydantic_db_backend/backends/json_files.py
+-rw-r--r--   0        0        0      701 2023-06-20 16:53:47.237618 pydantic_db_backend-0.4.1/pydantic_db_backend/exceptions/__init__.py
+-rw-r--r--   0        0        0     1192 2023-06-28 08:36:47.839745 pydantic_db_backend-0.4.1/pydantic_db_backend/utils.py
+-rw-r--r--   0        0        0     1000 2023-06-28 12:08:06.145265 pydantic_db_backend-0.4.1/pyproject.toml
+-rw-r--r--   0        0        0      766 1970-01-01 00:00:00.000000 pydantic_db_backend-0.4.1/PKG-INFO
```

### Comparing `pydantic_db_backend-0.4.0/pydantic_db_backend/backend.py` & `pydantic_db_backend-0.4.1/pydantic_db_backend/backend.py`

 * *Files identical despite different names*

### Comparing `pydantic_db_backend-0.4.0/pydantic_db_backend/backends/couchdb.py` & `pydantic_db_backend-0.4.1/pydantic_db_backend/backends/couchdb.py`

 * *Ordering differences only*

 * *Files 1% similar despite different names*

```diff
@@ -1,19 +1,19 @@
 from __future__ import annotations
 
 import json
 import logging
 import os
 from typing import Dict, Type, List
 
-import couchdb
 import pydash
 from couchdb import ResourceConflict
 from pydantic import BaseModel, Field
 
+import couchdb
 from pydantic_db_backend.backend import BackendBase, BackendModel
 from pydantic_db_backend.exceptions import RevisionConflict, NotFound, AlreadyExists
 from pydantic_db_backend.utils import CustomJSONEncoder
 
 log = logging.getLogger(__name__)
```

### Comparing `pydantic_db_backend-0.4.0/pydantic_db_backend/exceptions/__init__.py` & `pydantic_db_backend-0.4.1/pydantic_db_backend/exceptions/__init__.py`

 * *Files identical despite different names*

### Comparing `pydantic_db_backend-0.4.0/pydantic_db_backend/utils.py` & `pydantic_db_backend-0.4.1/pydantic_db_backend/utils.py`

 * *Files identical despite different names*

### Comparing `pydantic_db_backend-0.4.0/pyproject.toml` & `pydantic_db_backend-0.4.1/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,23 +1,23 @@
 [tool.poetry]
 name = "pydantic-db-backend"
-version = "0.4.0"
+version = "0.4.1"
 description = ""
 authors = ["Marco Bartel <bsimpson888@gmail.com>"]
 readme = "README.md"
 
 [tool.poetry.dependencies]
 python = "^3.11"
 python-dotenv = "^1.0.0"
 couchdb = { version = "^1.2", optional = true }
 pymongo = { version = "^3.13.0", optional = true }
 pydash = "^7.0.3"
 iso8601 = "^1.1.0"
 pydantic = "^1.10.7"
-webexception = "^1.0.1"
+webexception = "^1.0.2"
 
 
 [tool.poetry.group.dev.dependencies]
 coverage = "^7.2.7"
 pytest = "^7.3.1"
 freezegun = "^1.2.2"
 couchdb = "^1.2"
```

### Comparing `pydantic_db_backend-0.4.0/PKG-INFO` & `pydantic_db_backend-0.4.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,25 +1,25 @@
 Metadata-Version: 2.1
 Name: pydantic-db-backend
-Version: 0.4.0
+Version: 0.4.1
 Summary: 
 Author: Marco Bartel
 Author-email: bsimpson888@gmail.com
 Requires-Python: >=3.11,<4.0
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.11
 Provides-Extra: couchdb
 Provides-Extra: mongodb
 Requires-Dist: couchdb (>=1.2,<2.0) ; extra == "couchdb"
 Requires-Dist: iso8601 (>=1.1.0,<2.0.0)
 Requires-Dist: pydantic (>=1.10.7,<2.0.0)
 Requires-Dist: pydash (>=7.0.3,<8.0.0)
 Requires-Dist: pymongo (>=3.13.0,<4.0.0) ; extra == "mongodb"
 Requires-Dist: python-dotenv (>=1.0.0,<2.0.0)
-Requires-Dist: webexception (>=1.0.1,<2.0.0)
+Requires-Dist: webexception (>=1.0.2,<2.0.0)
 Description-Content-Type: text/markdown
 
 # Testing
 
 ### CouchDB
 
 http://localhost:5984/_utils/#
```

