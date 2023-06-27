# Comparing `tmp/ODetaM-1.5.0.tar.gz` & `tmp/odetam-1.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "ODetaM-1.5.0.tar", max compression
+gzip compressed data, was "odetam-1.5.1.tar", max compression
```

## Comparing `ODetaM-1.5.0.tar` & `odetam-1.5.1.tar`

### file list

```diff
@@ -1,11 +1,10 @@
--rw-r--r--   0        0        0     1067 2023-04-14 17:50:37.193237 ODetaM-1.5.0/LICENSE
--rw-r--r--   0        0        0     6072 2023-04-14 17:50:37.193347 ODetaM-1.5.0/README.md
--rw-r--r--   0        0        0       51 2023-04-14 17:50:37.193443 ODetaM-1.5.0/odetam/__init__.py
--rw-r--r--   0        0        0     4589 2023-04-14 17:50:37.193531 ODetaM-1.5.0/odetam/async_model.py
--rw-r--r--   0        0        0      169 2023-04-14 17:50:37.193586 ODetaM-1.5.0/odetam/exceptions.py
--rw-r--r--   0        0        0     4053 2023-04-14 17:50:37.193661 ODetaM-1.5.0/odetam/field.py
--rw-r--r--   0        0        0     8554 2023-04-14 17:50:37.193761 ODetaM-1.5.0/odetam/model.py
--rw-r--r--   0        0        0     2332 2023-04-14 17:50:37.193830 ODetaM-1.5.0/odetam/query.py
--rw-r--r--   0        0        0      671 2023-04-14 17:52:27.522832 ODetaM-1.5.0/pyproject.toml
--rw-r--r--   0        0        0     7069 1970-01-01 00:00:00.000000 ODetaM-1.5.0/setup.py
--rw-r--r--   0        0        0     6843 1970-01-01 00:00:00.000000 ODetaM-1.5.0/PKG-INFO
+-rw-r--r--   0        0        0     1067 2023-06-12 22:41:23.174675 odetam-1.5.1/LICENSE
+-rw-r--r--   0        0        0     6072 2023-06-12 22:41:23.174785 odetam-1.5.1/README.md
+-rw-r--r--   0        0        0       51 2023-06-12 22:41:23.174872 odetam-1.5.1/odetam/__init__.py
+-rw-r--r--   0        0        0     4677 2023-06-27 22:24:36.753514 odetam-1.5.1/odetam/async_model.py
+-rw-r--r--   0        0        0      169 2023-06-12 22:41:23.175004 odetam-1.5.1/odetam/exceptions.py
+-rw-r--r--   0        0        0     4053 2023-06-12 22:41:23.175072 odetam-1.5.1/odetam/field.py
+-rw-r--r--   0        0        0     8736 2023-06-27 22:24:36.753671 odetam-1.5.1/odetam/model.py
+-rw-r--r--   0        0        0     2332 2023-06-12 22:41:23.175223 odetam-1.5.1/odetam/query.py
+-rw-r--r--   0        0        0      671 2023-06-27 22:24:48.795457 odetam-1.5.1/pyproject.toml
+-rw-r--r--   0        0        0     6894 1970-01-01 00:00:00.000000 odetam-1.5.1/PKG-INFO
```

### Comparing `ODetaM-1.5.0/LICENSE` & `odetam-1.5.1/LICENSE`

 * *Files identical despite different names*

### Comparing `ODetaM-1.5.0/README.md` & `odetam-1.5.1/README.md`

 * *Files identical despite different names*

### Comparing `ODetaM-1.5.0/odetam/async_model.py` & `odetam-1.5.1/odetam/async_model.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,12 +1,11 @@
-from typing import Any, Dict, List, Optional, Union
+from typing import Any, Dict, List, Optional, Type, TypeVar, Union
 
 from deta import AsyncBase, Deta
 from deta.base import FetchResponse
-from typing_extensions import Self
 
 from odetam.exceptions import DetaError, InvalidKey, ItemNotFound
 from odetam.model import BaseDetaModel, DetaModelMetaClass, handle_db_property
 from odetam.query import DetaQuery, DetaQueryList, DetaQueryStatement
 
 
 class AsyncDetaModelMetaClass(DetaModelMetaClass):
@@ -15,71 +14,74 @@
         if getattr(cls.Config, "deta_key", None) is not None:
             deta = Deta(cls.Config.deta_key)
             return handle_db_property(cls, deta.AsyncBase)
 
         return handle_db_property(cls, AsyncBase)
 
 
+T = TypeVar("T", bound="AsyncDetaModel")
+
+
 class AsyncDetaModel(BaseDetaModel, metaclass=AsyncDetaModelMetaClass):
     @classmethod
-    async def get(cls, key: str) -> Self:
+    async def get(cls: Type[T], key: str) -> T:
         """
         Get a single instance
         :param key: Deta database key
         :return: object found in database serialized into its pydantic object
 
         :raises ItemNotFound: No matching item was found
         """
         if key is None:
             raise InvalidKey("key cannot be None")
 
         item: Dict[str, Any] = await cls.__db__.get(key)
         return cls._return_item_or_raise(item)
 
     @classmethod
-    async def get_or_none(cls, key: str) -> Optional[Self]:
+    async def get_or_none(cls: Type[T], key: str) -> Optional[T]:
         """Try to get item by key or return None if item not found"""
         try:
             return await cls.get(key)
         except ItemNotFound:
             return None
 
     @classmethod
-    async def get_all(cls) -> List[Self]:
+    async def get_all(cls: Type[T]) -> List[T]:
         """Get all the records from the database"""
         response: FetchResponse = await cls.__db__.fetch()
         records: List[Dict[str, Any]] = response.items
         while response.last:
             response = await cls.__db__.fetch(last=response.last)
             records += response.items
 
         return [cls._deserialize(record) for record in records]
 
     @classmethod
     async def query(
-        cls, query_statement: Union[DetaQuery, DetaQueryStatement, DetaQueryList]
-    ) -> List[Self]:
+        cls: Type[T], query_statement: Union[DetaQuery, DetaQueryStatement, DetaQueryList]
+    ) -> List[T]:
         """Get items from database based on the query."""
         response: FetchResponse = await cls.__db__.fetch(query_statement.as_query())
         records: List[Dict[str, Any]] = response.items
         while response.last:
             response = await cls.__db__.fetch(
                 query_statement.as_query(), last=response.last
             )
             records += response.items
 
         return [cls._deserialize(item) for item in records]
 
     @classmethod
-    async def delete_key(cls, key: str):
+    async def delete_key(cls, key: str) -> None:
         """Delete an item based on the key"""
         await cls.__db__.delete(key)
 
     @classmethod
-    async def put_many(cls, items: List[Self]):
+    async def put_many(cls: Type[T], items: List[T]) -> List[T]:
         """Put multiple instances at once
 
         :param items: List of pydantic objects to put in the database
         :returns: List of items successfully added, serialized with pydantic
         """
         records = []
         processed: List[Dict[str, Any]] = []
@@ -99,26 +101,26 @@
 
         return [cls._deserialize(record) for record in processed]
 
     @classmethod
     async def _db_put(cls, data: List[Dict[str, Any]]) -> List[Dict[str, Any]]:
         return await cls.__db__.put(data)
 
-    async def save(self):
+    async def save(self) -> None:
         """Saves the record to the database. Behaves as upsert, will create
         if not present. Database key will then be set on the object."""
         # exclude = set()
         # if self.key is None:
         #     exclude.add("key")
         # # this is dumb, but it ensures everything is in a json-serializable form
         # data = ujson.loads(self.json(exclude=exclude))
         saved = await self._db_put(self._serialize())
         self.key = saved["key"]
 
-    async def delete(self):
+    async def delete(self) -> None:
         """Delete the open object from the database. The object will still exist in
         python, but will be deleted from the database and the key attribute will be
         set to None."""
         if not self.key:
             raise DetaError("Item does not have key for deletion.")
         await self.delete_key(self.key)
         self.key = None
```

### Comparing `ODetaM-1.5.0/odetam/field.py` & `odetam-1.5.1/odetam/field.py`

 * *Files identical despite different names*

### Comparing `ODetaM-1.5.0/odetam/model.py` & `odetam-1.5.1/odetam/model.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,17 +1,16 @@
 import datetime
 import re
-from typing import Any, Callable, Container, Dict, List, Optional, Union
+from typing import Any, Callable, Container, Dict, List, Optional, Type, TypeVar, Union
 
 import pydantic
 import ujson
 from deta import Base, Deta
 from deta.base import FetchResponse, _Base
 from pydantic import BaseModel, Field, ValidationError
-from typing_extensions import Self
 
 from odetam.exceptions import DetaError, InvalidKey, ItemNotFound
 from odetam.field import DetaField
 from odetam.query import DetaQuery, DetaQueryList, DetaQueryStatement
 
 DETA_BASIC_TYPES = [Dict[str, Any], List[Any], str, int, float, bool]
 DETA_OPTIONAL_TYPES = [Optional[type_] for type_ in DETA_BASIC_TYPES]
@@ -49,14 +48,17 @@
         if getattr(cls.Config, "deta_key", None) is not None:
             deta = Deta(cls.Config.deta_key)
             return handle_db_property(cls, deta.Base)
 
         return handle_db_property(cls, Base)
 
 
+K = TypeVar("K", bound="BaseDetaModel")
+
+
 class BaseDetaModel(BaseModel):
     __db__ = Optional[_Base]
 
     key: Optional[str] = Field(
         default=None, title="Key", description="Primary key in the database"
     )
 
@@ -73,38 +75,40 @@
             elif getattr(self, field_name, None) is None:
                 as_dict[field_name] = None
             elif field.type_ in DETA_TYPES:
                 as_dict[field_name] = getattr(self, field_name)
             elif field.type_ == datetime.datetime:
                 as_dict[field_name] = getattr(self, field_name).timestamp()
             elif field.type_ == datetime.date:
-                as_dict[field_name] = int(getattr(self, field_name).strftime("%Y%m%d"))
+                as_dict[field_name] = int(
+                    getattr(self, field_name).strftime("%Y%m%d"))
             elif field.type_ == datetime.time:
                 as_dict[field_name] = int(
                     getattr(self, field_name).strftime("%H%M%S%f")
                 )
             else:
                 as_dict[field_name] = ujson.loads(self.json(include={field_name}))[
                     field_name
                 ]
 
         return as_dict
 
     @classmethod
-    def _deserialize(cls, data: Dict[str, Any]) -> Self:
+    def _deserialize(cls: Type[K], data: Dict[str, Any]) -> K:
         as_dict: Dict[str, Any] = {}
         for field_name, field in cls.__fields__.items():
             if field_name not in data:
                 continue
             elif data.get(field_name) is None:
                 as_dict[field_name] = None
             elif field.type_ in DETA_TYPES:
                 as_dict[field_name] = data[field_name]
             elif field.type_ == datetime.datetime:
-                as_dict[field_name] = datetime.datetime.fromtimestamp(data[field_name])
+                as_dict[field_name] = datetime.datetime.fromtimestamp(
+                    data[field_name])
             elif field.type_ == datetime.date:
                 as_dict[field_name] = datetime.datetime.strptime(
                     str(data[field_name]), "%Y%m%d"
                 ).date()
             elif field.type_ == datetime.time:
                 as_dict[field_name] = datetime.datetime.strptime(
                     str(data[field_name]), "%H%M%S%f"
@@ -116,78 +120,82 @@
                     as_dict[field_name] = ujson.loads(value)
                 except (TypeError, ValueError):
                     as_dict[field_name] = value
 
         return cls.parse_obj(as_dict)
 
     @classmethod
-    def _return_item_or_raise(cls, item: Optional[Dict[str, Any]]) -> Self:
+    def _return_item_or_raise(cls: Type[K], item: Optional[Dict[str, Any]]) -> K:
         if item is None or item.get("key") == "None":
             raise ItemNotFound("Could not find item matching that key")
         try:
             return cls._deserialize(item)
         except ValidationError:
             raise ItemNotFound("Could not find item matching that key")
 
 
+T = TypeVar("T", bound="DetaModel")
+
+
 class DetaModel(BaseDetaModel, metaclass=DetaModelMetaClass):
     @classmethod
-    def get(cls, key: str) -> Self:
+    def get(cls: Type[T], key: str) -> T:
         """
         Get a single instance
         :param key: Deta database key
         :return: object found in database serialized into its pydantic object
 
         :raises ItemNotFound: No matching item was found
         """
         if key is None:
             raise InvalidKey("key cannot be None")
 
         item: Dict[str, Any] = cls.__db__.get(key)
         return cls._return_item_or_raise(item)
 
     @classmethod
-    def get_or_none(cls, key: str) -> Optional[Self]:
+    def get_or_none(cls: Type[T], key: str) -> Optional[T]:
         """Try to get item by key or return None if item not found"""
         try:
             return cls.get(key)
         except ItemNotFound:
             return None
 
     @classmethod
-    def get_all(cls) -> List[Self]:
+    def get_all(cls: Type[T]) -> List[T]:
         """Get all the records from the database"""
         response: FetchResponse = cls.__db__.fetch()
         records: List[Dict[str, Any]] = response.items
         while response.last:
             response = cls.__db__.fetch(last=response.last)
             records += response.items
 
         return [cls._deserialize(record) for record in records]
 
     @classmethod
     def query(
-        cls, query_statement: Union[DetaQuery, DetaQueryStatement, DetaQueryList]
-    ) -> List[Self]:
+        cls: Type[T], query_statement: Union[DetaQuery, DetaQueryStatement, DetaQueryList]
+    ) -> List[T]:
         """Get items from database based on the query."""
         response: FetchResponse = cls.__db__.fetch(query_statement.as_query())
         records: List[Dict[str, Any]] = response.items
         while response.last:
-            response = cls.__db__.fetch(query_statement.as_query(), last=response.last)
+            response = cls.__db__.fetch(
+                query_statement.as_query(), last=response.last)
             records += response.items
 
         return [cls._deserialize(item) for item in records]
 
     @classmethod
-    def delete_key(cls, key: str):
+    def delete_key(cls, key: str) -> None:
         """Delete an item based on the key"""
         cls.__db__.delete(key)
 
     @classmethod
-    def put_many(cls, items: List[Self]) -> List[Self]:
+    def put_many(cls: Type[T], items: List[T]) -> List[T]:
         """Put multiple instances at once
 
         :param items: List of pydantic objects to put in the database
         :returns: List of items successfully added, serialized with pydantic
         """
         records = []
         processed: List[Dict[str, Any]] = []
@@ -207,26 +215,26 @@
 
         return [cls._deserialize(record) for record in processed]
 
     @classmethod
     def _db_put(cls, data: List[Dict[str, Any]]) -> List[Dict[str, Any]]:
         return cls.__db__.put(data)  # type: ignore
 
-    def save(self):
+    def save(self) -> None:
         """Saves the record to the database. Behaves as upsert, will create
         if not present. Database key will then be set on the object."""
         # exclude = set()
         # if self.key is None:
         #     exclude.add("key")
         # # this is dumb, but it ensures everything is in a json-serializable form
         # data = ujson.loads(self.json(exclude=exclude))
         saved = self._db_put(self._serialize())
         self.key = saved["key"]
 
-    def delete(self):
+    def delete(self) -> None:
         """Delete the open object from the database. The object will still exist in
         python, but will be deleted from the database and the key attribute will be
         set to None."""
         if not self.key:
             raise DetaError("Item does not have key for deletion")
         self.delete_key(self.key)
         self.key = None
```

### Comparing `ODetaM-1.5.0/odetam/query.py` & `odetam-1.5.1/odetam/query.py`

 * *Files identical despite different names*

### Comparing `ODetaM-1.5.0/pyproject.toml` & `odetam-1.5.1/pyproject.toml`

 * *Files 10% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "ODetaM"
-version = "1.5.0"
+version = "1.5.1"
 description = "A simple ODM (Object Document Mapper) for Deta Base, based on pydantic."
 authors = ["Rick Henry <rickhenry@rickhenry.dev>"]
 readme = "README.md"
 repository = "https://github.com/rickh94/odetam"
 
 [tool.poetry.dependencies]
 python = ">=3.7,<4.0"
```

### Comparing `ODetaM-1.5.0/setup.py` & `odetam-1.5.1/PKG-INFO`

 * *Files 25% similar despite different names*

```diff
@@ -1,33 +1,250 @@
-# -*- coding: utf-8 -*-
-from setuptools import setup
+Metadata-Version: 2.1
+Name: odetam
+Version: 1.5.1
+Summary: A simple ODM (Object Document Mapper) for Deta Base, based on pydantic.
+Home-page: https://github.com/rickh94/odetam
+Author: Rick Henry
+Author-email: rickhenry@rickhenry.dev
+Requires-Python: >=3.7,<4.0
+Classifier: Programming Language :: Python :: 3
+Classifier: Programming Language :: Python :: 3.7
+Classifier: Programming Language :: Python :: 3.8
+Classifier: Programming Language :: Python :: 3.9
+Classifier: Programming Language :: Python :: 3.10
+Classifier: Programming Language :: Python :: 3.11
+Requires-Dist: deta[async] (==1.1.0a2)
+Requires-Dist: pydantic (>=1.7,<2.0)
+Requires-Dist: typing-extensions (>=4.5.0,<5.0.0)
+Requires-Dist: ujson (>=4.0,<5.0)
+Project-URL: Repository, https://github.com/rickh94/odetam
+Description-Content-Type: text/markdown
+
+# ODetaM
+
+[![Test](https://github.com/rickh94/ODetaM/actions/workflows/test.yml/badge.svg)](https://github.com/rickh94/ODetaM/actions/workflows/test.yml)
+[![codecov](https://codecov.io/gh/rickh94/odetam/branch/main/graph/badge.svg?token=BLDIMHU9FB)](https://codecov.io/gh/rickh94/odetam)
+
+A simple ODM (Object Document Mapper) for [Deta Base](https://deta.sh) base on
+[pydantic](https://github.com/samuelcolvin/pydantic/).
+
+## Installation
+
+`pip install odetam`
+
+## Usage
+
+Create pydantic models as normal, but inherit from `DetaModel` instead of 
+pydantic BaseModel. You will need to set the environment variable 
+`DETA_PROJECT_KEY` to your Deta project key so that databases can be 
+accessed/created, instead you are working under deta initialized project. 
+Your also can specify Deta project key in Config class of your model, for 
+migration from Deta Cloud or importing external Collection (read [DetaBase Docs](https://deta.space/docs/en/basics/data)) 
+This is a secret key, so handle it appropriately (hence the environment variable).
+
+Bases will be automatically created based on model names (changed from 
+PascalCase/CamelCase case to snake_case). A `key` field (Deta's unique id) will 
+be automatically added to any model. You can supply the key on creation, or 
+Deta will generate one automatically and it will be added to the object when it 
+is saved.
+
+## Async Support
+
+Async/await is now supported! As of version 1.2.0, you can now 
+`from odetam.async_model import AsyncDetaModel`, inherit from that, and run all 
+the examples below just the same, but with `await` in front of the calls.
+
+You must `pip install deta[async]`, to use asynchronous base.
+
+
+### Get All
+
+`DetaModel.get_all()` should handle large bases better now, but you should 
+consider querying instead of getting everything if possible, because it is
+unlikely to perform well on large bases.
+
+
+## Example
+
+### Basics
+
+```python
+import datetime
+from typing import List
+
+from odetam import DetaModel
+
+
+class Captain(DetaModel):
+    name: str
+    joined: datetime.date
+    ships: List[str]
+
+
+# create
+kirk = Captain(
+        name="James T. Kirk",
+        joined=datetime.date(2252, 1, 1),
+        ships=["Enterprise"],
+        )
+
+sisko = Captain(
+        name="Benjamin Sisko",
+        joined=datetime.date(2350, 1, 1),
+        ships=["Deep Space 9", "Defiant"],
+        )
+
+# initial save, key is now set
+kirk.save()
+
+# update the object
+kirk.ships.append("Enterprise-A")
+
+# save again, this will be an update
+kirk.save()
+
+sisko.save()
+
+Captain.get_all()
+# [
+#     Captain(
+#         name="James T. Kirk", 
+#         joined=datetime.date(2252, 01, 01), 
+#         ships=["Enterprise", "Enterprise-A"],
+#         key="key1",
+#     ),
+#     Captain(
+#         name="Benjamin Sisko",
+#         joined=datetime.date(2350, 01, 01), 
+#         ships=["Deep Space 9", "Defiant"],
+#         key="key2",
+#     ),
+# ]
+
+Captain.get("key1")
+# Captain(
+#     name="James T. Kirk", 
+#     joined=datetime.date(2252, 01, 01), 
+#     ships=["Enterprise", "Enterprise-A"],
+#     key="key1",
+# )
+
+Captain.get("key3")
+# Traceback (most recent call last):
+#   File "<stdin>", line 1, in <module>
+# odetam.exceptions.ItemNotFound
+
+Captain.get_or_none("key3")
+# None
+
+Captain.query(Captain.name == "James T. Kirk")
+# Captain(
+#     name="James T. Kirk", 
+#     joined=datetime.date(2252, 01, 01), 
+#     ships=["Enterprise", "Enterprise-A"],
+#     key="key1",
+# )
+
+Captain.query(Captain.ships.contains("Defiant"))
+# Captain(
+#     name="Benjamin Sisko",
+#     joined=datetime.date(2350, 01, 01),
+#     ships=["Deep Space 9", "Defiant"],
+# )
+
+Captain.query(Captain.name.prefix("Ben"))
+# Captain(
+#     name="Benjamin Sisko",
+#     joined=datetime.date(2350, 01, 01),
+#     ships=["Deep Space 9", "Defiant"],
+# )
+
+kirk.delete()
+Captain.delete_key("key2")
+
+Captain.get_all()
+# []
+
+# you can also save several at once for better speed
+Captain.put_many([kirk, sisko])
+# [
+#     Captain(
+#         name="James T. Kirk", 
+#         joined=datetime.date(2252, 01, 01), 
+#         ships=["Enterprise", "Enterprise-A"],
+#         key="key1",
+#     ),
+#     Captain(
+#         name="Benjamin Sisko",
+#         joined=datetime.date(2350, 01, 01), 
+#         ships=["Deep Space 9", "Defiant"],
+#         key="key2",
+#     ),
+# ]
+
+```
+
+### Async model
+
+```python
+import datetime
+from typing import List
+
+from odetam.async_model import AsyncDetaModel
+
+
+class Captain(AsyncDetaModel):
+    name: str
+    joined: datetime.date
+    ships: List[str]
+
+
+async foo():
+    items = await Captain.get_all()
+
+```
+
+### Config
+
+```python
+
+class Captain(AsyncDetaModel):
+    name: str
+    joined: datetime.date
+    ships: List[str]
+
+    class Config:
+        table_name = "my_custom_table_name"
+        deta_key = "123_123" # project key from Deta Cloud or Data Key from another Deta Space project
+
+```
+
+## Save
+
+Models have the `.save()` method which will always behave as an upsert, 
+updating a record if it has a key, otherwise creating it and setting a key. 
+Deta has pure insert behavior, but it's less performant. If you need it, please 
+open a pull request.
+
+## Querying
+
+All basic comparison operators are implemented to map to their equivalents as 
+`(Model.field >= comparison_value)`. There is also a `.contains()` and 
+`.not_contains()` method for strings and lists of strings, as well as a 
+`.prefix()` method for strings. There is also a `.range()` for number types 
+that takes a lower and upper bound. You can also use `&`  as AND and `|` as OR. 
+ORs cannot be nested within ands, use a list of options as comparison instead. 
+You can use as many ORs as you want, as long as they execute after the ANDs in 
+the order of operations. This is due to how the Deta Base api works.
+
+## Deta Base
+
+Direct access to the base is available in the dunder attribute `__db__`, though 
+the point is to avoid that.
+
+## Exceptions
+
+ - `DetaError`: Base exception when anything goes wrong.
+ - `ItemNotFound`: Fairly self-explanatory...
+ - `InvalidDetaQuery`: Something is wrong with queries. Make sure you aren't using
+ queries with unsupported types
 
-packages = \
-['odetam']
-
-package_data = \
-{'': ['*']}
-
-install_requires = \
-['deta[async]==1.1.0a2',
- 'pydantic>=1.7,<2.0',
- 'typing-extensions>=4.5.0,<5.0.0',
- 'ujson>=4.0,<5.0']
-
-setup_kwargs = {
-    'name': 'odetam',
-    'version': '1.5.0',
-    'description': 'A simple ODM (Object Document Mapper) for Deta Base, based on pydantic.',
-    'long_description': '# ODetaM\n\n[![Test](https://github.com/rickh94/ODetaM/actions/workflows/test.yml/badge.svg)](https://github.com/rickh94/ODetaM/actions/workflows/test.yml)\n[![codecov](https://codecov.io/gh/rickh94/odetam/branch/main/graph/badge.svg?token=BLDIMHU9FB)](https://codecov.io/gh/rickh94/odetam)\n\nA simple ODM (Object Document Mapper) for [Deta Base](https://deta.sh) base on\n[pydantic](https://github.com/samuelcolvin/pydantic/).\n\n## Installation\n\n`pip install odetam`\n\n## Usage\n\nCreate pydantic models as normal, but inherit from `DetaModel` instead of \npydantic BaseModel. You will need to set the environment variable \n`DETA_PROJECT_KEY` to your Deta project key so that databases can be \naccessed/created, instead you are working under deta initialized project. \nYour also can specify Deta project key in Config class of your model, for \nmigration from Deta Cloud or importing external Collection (read [DetaBase Docs](https://deta.space/docs/en/basics/data)) \nThis is a secret key, so handle it appropriately (hence the environment variable).\n\nBases will be automatically created based on model names (changed from \nPascalCase/CamelCase case to snake_case). A `key` field (Deta\'s unique id) will \nbe automatically added to any model. You can supply the key on creation, or \nDeta will generate one automatically and it will be added to the object when it \nis saved.\n\n## Async Support\n\nAsync/await is now supported! As of version 1.2.0, you can now \n`from odetam.async_model import AsyncDetaModel`, inherit from that, and run all \nthe examples below just the same, but with `await` in front of the calls.\n\nYou must `pip install deta[async]`, to use asynchronous base.\n\n\n### Get All\n\n`DetaModel.get_all()` should handle large bases better now, but you should \nconsider querying instead of getting everything if possible, because it is\nunlikely to perform well on large bases.\n\n\n## Example\n\n### Basics\n\n```python\nimport datetime\nfrom typing import List\n\nfrom odetam import DetaModel\n\n\nclass Captain(DetaModel):\n    name: str\n    joined: datetime.date\n    ships: List[str]\n\n\n# create\nkirk = Captain(\n        name="James T. Kirk",\n        joined=datetime.date(2252, 1, 1),\n        ships=["Enterprise"],\n        )\n\nsisko = Captain(\n        name="Benjamin Sisko",\n        joined=datetime.date(2350, 1, 1),\n        ships=["Deep Space 9", "Defiant"],\n        )\n\n# initial save, key is now set\nkirk.save()\n\n# update the object\nkirk.ships.append("Enterprise-A")\n\n# save again, this will be an update\nkirk.save()\n\nsisko.save()\n\nCaptain.get_all()\n# [\n#     Captain(\n#         name="James T. Kirk", \n#         joined=datetime.date(2252, 01, 01), \n#         ships=["Enterprise", "Enterprise-A"],\n#         key="key1",\n#     ),\n#     Captain(\n#         name="Benjamin Sisko",\n#         joined=datetime.date(2350, 01, 01), \n#         ships=["Deep Space 9", "Defiant"],\n#         key="key2",\n#     ),\n# ]\n\nCaptain.get("key1")\n# Captain(\n#     name="James T. Kirk", \n#     joined=datetime.date(2252, 01, 01), \n#     ships=["Enterprise", "Enterprise-A"],\n#     key="key1",\n# )\n\nCaptain.get("key3")\n# Traceback (most recent call last):\n#   File "<stdin>", line 1, in <module>\n# odetam.exceptions.ItemNotFound\n\nCaptain.get_or_none("key3")\n# None\n\nCaptain.query(Captain.name == "James T. Kirk")\n# Captain(\n#     name="James T. Kirk", \n#     joined=datetime.date(2252, 01, 01), \n#     ships=["Enterprise", "Enterprise-A"],\n#     key="key1",\n# )\n\nCaptain.query(Captain.ships.contains("Defiant"))\n# Captain(\n#     name="Benjamin Sisko",\n#     joined=datetime.date(2350, 01, 01),\n#     ships=["Deep Space 9", "Defiant"],\n# )\n\nCaptain.query(Captain.name.prefix("Ben"))\n# Captain(\n#     name="Benjamin Sisko",\n#     joined=datetime.date(2350, 01, 01),\n#     ships=["Deep Space 9", "Defiant"],\n# )\n\nkirk.delete()\nCaptain.delete_key("key2")\n\nCaptain.get_all()\n# []\n\n# you can also save several at once for better speed\nCaptain.put_many([kirk, sisko])\n# [\n#     Captain(\n#         name="James T. Kirk", \n#         joined=datetime.date(2252, 01, 01), \n#         ships=["Enterprise", "Enterprise-A"],\n#         key="key1",\n#     ),\n#     Captain(\n#         name="Benjamin Sisko",\n#         joined=datetime.date(2350, 01, 01), \n#         ships=["Deep Space 9", "Defiant"],\n#         key="key2",\n#     ),\n# ]\n\n```\n\n### Async model\n\n```python\nimport datetime\nfrom typing import List\n\nfrom odetam.async_model import AsyncDetaModel\n\n\nclass Captain(AsyncDetaModel):\n    name: str\n    joined: datetime.date\n    ships: List[str]\n\n\nasync foo():\n    items = await Captain.get_all()\n\n```\n\n### Config\n\n```python\n\nclass Captain(AsyncDetaModel):\n    name: str\n    joined: datetime.date\n    ships: List[str]\n\n    class Config:\n        table_name = "my_custom_table_name"\n        deta_key = "123_123" # project key from Deta Cloud or Data Key from another Deta Space project\n\n```\n\n## Save\n\nModels have the `.save()` method which will always behave as an upsert, \nupdating a record if it has a key, otherwise creating it and setting a key. \nDeta has pure insert behavior, but it\'s less performant. If you need it, please \nopen a pull request.\n\n## Querying\n\nAll basic comparison operators are implemented to map to their equivalents as \n`(Model.field >= comparison_value)`. There is also a `.contains()` and \n`.not_contains()` method for strings and lists of strings, as well as a \n`.prefix()` method for strings. There is also a `.range()` for number types \nthat takes a lower and upper bound. You can also use `&`  as AND and `|` as OR. \nORs cannot be nested within ands, use a list of options as comparison instead. \nYou can use as many ORs as you want, as long as they execute after the ANDs in \nthe order of operations. This is due to how the Deta Base api works.\n\n## Deta Base\n\nDirect access to the base is available in the dunder attribute `__db__`, though \nthe point is to avoid that.\n\n## Exceptions\n\n - `DetaError`: Base exception when anything goes wrong.\n - `ItemNotFound`: Fairly self-explanatory...\n - `InvalidDetaQuery`: Something is wrong with queries. Make sure you aren\'t using\n queries with unsupported types\n',
-    'author': 'Rick Henry',
-    'author_email': 'rickhenry@rickhenry.dev',
-    'maintainer': 'None',
-    'maintainer_email': 'None',
-    'url': 'https://github.com/rickh94/odetam',
-    'packages': packages,
-    'package_data': package_data,
-    'install_requires': install_requires,
-    'python_requires': '>=3.7,<4.0',
-}
-
-
-setup(**setup_kwargs)
```

