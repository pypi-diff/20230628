# Comparing `tmp/pydantic_db_backend-0.3.3.tar.gz` & `tmp/pydantic_db_backend-0.4.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pydantic_db_backend-0.3.3.tar", max compression
+gzip compressed data, was "pydantic_db_backend-0.4.0.tar", max compression
```

## Comparing `pydantic_db_backend-0.3.3.tar` & `pydantic_db_backend-0.4.0.tar`

### file list

```diff
@@ -1,10 +1,10 @@
--rw-r--r--   0        0        0       87 2023-06-14 17:15:43.151729 pydantic_db_backend-0.3.3/README.md
--rw-r--r--   0        0        0        0 2023-05-11 08:45:17.171212 pydantic_db_backend-0.3.3/pydantic_db_backend/__init__.py
--rw-r--r--   0        0        0     6072 2023-06-26 13:34:47.557755 pydantic_db_backend-0.3.3/pydantic_db_backend/backend.py
--rw-r--r--   0        0        0        0 2023-05-13 10:06:57.338481 pydantic_db_backend-0.3.3/pydantic_db_backend/backends/__init__.py
--rw-r--r--   0        0        0     5757 2023-06-26 13:43:26.341233 pydantic_db_backend-0.3.3/pydantic_db_backend/backends/couchdb.py
--rw-r--r--   0        0        0      100 2023-06-14 12:06:00.522425 pydantic_db_backend-0.3.3/pydantic_db_backend/backends/json_files.py
--rw-r--r--   0        0        0      701 2023-06-20 16:53:47.237618 pydantic_db_backend-0.3.3/pydantic_db_backend/exceptions/__init__.py
--rw-r--r--   0        0        0      577 2023-06-16 13:56:03.761606 pydantic_db_backend-0.3.3/pydantic_db_backend/utils.py
--rw-r--r--   0        0        0     1000 2023-06-26 14:02:35.672668 pydantic_db_backend-0.3.3/pyproject.toml
--rw-r--r--   0        0        0      766 1970-01-01 00:00:00.000000 pydantic_db_backend-0.3.3/PKG-INFO
+-rw-r--r--   0        0        0       87 2023-06-14 17:15:43.151729 pydantic_db_backend-0.4.0/README.md
+-rw-r--r--   0        0        0        0 2023-05-11 08:45:17.171212 pydantic_db_backend-0.4.0/pydantic_db_backend/__init__.py
+-rw-r--r--   0        0        0     6222 2023-06-28 07:49:52.142216 pydantic_db_backend-0.4.0/pydantic_db_backend/backend.py
+-rw-r--r--   0        0        0        0 2023-05-13 10:06:57.338481 pydantic_db_backend-0.4.0/pydantic_db_backend/backends/__init__.py
+-rw-r--r--   0        0        0     6047 2023-06-28 08:42:50.521114 pydantic_db_backend-0.4.0/pydantic_db_backend/backends/couchdb.py
+-rw-r--r--   0        0        0      100 2023-06-14 12:06:00.522425 pydantic_db_backend-0.4.0/pydantic_db_backend/backends/json_files.py
+-rw-r--r--   0        0        0      701 2023-06-20 16:53:47.237618 pydantic_db_backend-0.4.0/pydantic_db_backend/exceptions/__init__.py
+-rw-r--r--   0        0        0     1192 2023-06-28 08:36:47.839745 pydantic_db_backend-0.4.0/pydantic_db_backend/utils.py
+-rw-r--r--   0        0        0     1000 2023-06-28 09:04:32.275813 pydantic_db_backend-0.4.0/pyproject.toml
+-rw-r--r--   0        0        0      766 1970-01-01 00:00:00.000000 pydantic_db_backend-0.4.0/PKG-INFO
```

### Comparing `pydantic_db_backend-0.3.3/pydantic_db_backend/backend.py` & `pydantic_db_backend-0.4.0/pydantic_db_backend/backend.py`

 * *Files 2% similar despite different names*

```diff
@@ -6,14 +6,15 @@
 import re
 from contextvars import ContextVar
 from typing import Type, Dict, List
 
 from dotenv import load_dotenv
 import logging
 
+from freezegun.api import FakeDatetime
 from pydantic import BaseModel, Field
 
 from pydantic_db_backend.utils import uid, utcnow, str_to_datetime_if_parseable
 
 log = logging.getLogger(__name__)
 
 backend_context_var = ContextVar('backend_context_var')
@@ -25,18 +26,18 @@
     revision: str | None = None
     version: int | None = 1
     created_time: datetime.datetime | None = Field(default_factory=utcnow)
     updated_time: datetime.datetime | None = Field(default_factory=utcnow)
 
     class Config:
         json_encoders = {
-            datetime.datetime: lambda x: x.isoformat()
+            datetime.datetime: lambda x: x.isoformat(),
         }
         json_decoders = {
-            datetime.datetime: str_to_datetime_if_parseable
+            datetime.datetime: str_to_datetime_if_parseable,
         }
 
 
 class Backend(object):
     @staticmethod
     @contextlib.contextmanager
     def provider(backend: Type[BackendBase]):
@@ -162,8 +163,10 @@
 
     @classmethod
     def delete_uid(cls, model: Type[BackendModel], uid: str) -> None:
         raise NotImplementedError
 
     @classmethod
     def delete_collection(cls, model: Type[BackendModel]) -> None:
-        raise NotImplementedError
+        # delete index info , for recreating it on next collection usage
+        if model in cls._indexes:
+            del cls._indexes[model]
```

### Comparing `pydantic_db_backend-0.3.3/pydantic_db_backend/backends/couchdb.py` & `pydantic_db_backend-0.4.0/pydantic_db_backend/backends/couchdb.py`

 * *Files 9% similar despite different names*

```diff
@@ -1,23 +1,22 @@
 from __future__ import annotations
 
+import json
+import logging
 import os
-import sys
 from typing import Dict, Type, List
 
+import couchdb
 import pydash
 from couchdb import ResourceConflict
 from pydantic import BaseModel, Field
-import couchdb
 
-import pydantic_db_backend.utils
 from pydantic_db_backend.backend import BackendBase, BackendModel
-import logging
-
 from pydantic_db_backend.exceptions import RevisionConflict, NotFound, AlreadyExists
+from pydantic_db_backend.utils import CustomJSONEncoder
 
 log = logging.getLogger(__name__)
 
 
 class CouchDbBackend(BackendBase):
     # _collections: Dict[Type[BaseModel], str] = {}
     _indexes: Dict[str, List[dict]] = {}
@@ -59,15 +58,14 @@
     def create_index(cls, collection_name: str, index_name: str, index_spec: list, db: couchdb.Database):
         super().create_index(collection_name, index_name, index_spec)
         i = (collection_name, index_name)
         indexes = db.index()
         if i not in indexes:
             indexes[i] = index_spec
 
-
     @classmethod
     def get_db(cls, model: Type[BackendModel]) -> couchdb.Database:
         db_name = cls.collection_name(model)
 
         with cls.alias() as alias:
             con = cls._connections[alias]
 
@@ -128,44 +126,63 @@
         db = cls.get_db(model)
         if uid in db:
             del db[uid]
         else:
             raise NotFound(uid=uid)
 
     @classmethod
-    def get_uids(cls, model: Type[BackendModel], skip: int = 0, limit: int = 0, query_filter: dict = None,
-                 sort: List = None) -> List[str]:
+    def get_uids(
+        cls,
+        model: Type[BackendModel],
+        skip: int = 0,
+        limit: int = 0,
+        query_filter: dict = None,
+        sort: List = None
+    ) -> List[str]:
         if query_filter is None:
             query_filter = {}
+
+        # convert to json and back again, to have iso datetime strings
+        query_filter = json.loads(json.dumps(query_filter, cls=CustomJSONEncoder))
+
         db = cls.get_db(model)
 
         find_dict = {
             "selector": query_filter,
             "skip": skip,
             "limit": limit
         }
         if sort is not None:
             find_dict["sort"] = sort
+
         result = [x["_id"] for x in (db.find(find_dict))]
         return result
 
     @classmethod
-    def get_instances(cls, model: Type[BackendModel], skip: int = 0, limit: int = 0, query_filter: dict = None,
-                      sort: List = None) -> List[BackendModel]:
+    def get_instances(
+        cls,
+        model: Type[BackendModel],
+        skip: int = 0,
+        limit: int = 0,
+        query_filter: dict = None,
+        sort: List = None
+    ) -> List[BackendModel]:
         ids = cls.get_uids(model=model, skip=skip, limit=limit, query_filter=query_filter, sort=sort)
         return [cls.get_instance(model, uid=x) for x in ids]
 
     @classmethod
     def delete_collection(cls, model: Type[BackendModel]) -> None:
         with cls.alias() as alias:
             server = cls._connections[alias].server
             name = cls.collection_name(model)
             if name in server:
                 server.delete(name)
 
+        super().delete_collection(model)
+
 
 class CouchDbConnectionModel(BaseModel):
     alias: str
     uri: str
     server: couchdb.Server
     dbs: Dict[str, couchdb.Database] = Field(default_factory=dict)
```

### Comparing `pydantic_db_backend-0.3.3/pydantic_db_backend/exceptions/__init__.py` & `pydantic_db_backend-0.4.0/pydantic_db_backend/exceptions/__init__.py`

 * *Files identical despite different names*

### Comparing `pydantic_db_backend-0.3.3/pyproject.toml` & `pydantic_db_backend-0.4.0/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "pydantic-db-backend"
-version = "0.3.3"
+version = "0.4.0"
 description = ""
 authors = ["Marco Bartel <bsimpson888@gmail.com>"]
 readme = "README.md"
 
 [tool.poetry.dependencies]
 python = "^3.11"
 python-dotenv = "^1.0.0"
```

### Comparing `pydantic_db_backend-0.3.3/PKG-INFO` & `pydantic_db_backend-0.4.0/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pydantic-db-backend
-Version: 0.3.3
+Version: 0.4.0
 Summary: 
 Author: Marco Bartel
 Author-email: bsimpson888@gmail.com
 Requires-Python: >=3.11,<4.0
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.11
 Provides-Extra: couchdb
```

