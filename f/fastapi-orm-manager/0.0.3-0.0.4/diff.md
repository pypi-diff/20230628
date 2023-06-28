# Comparing `tmp/fastapi_orm_manager-0.0.3.tar.gz` & `tmp/fastapi_orm_manager-0.0.4.tar.gz`

## Comparing `fastapi_orm_manager-0.0.3.tar` & `fastapi_orm_manager-0.0.4.tar`

### file list

```diff
@@ -1,10 +1,10 @@
--rw-r--r--   0        0        0       35 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.3/requirements.txt
--rw-r--r--   0        0        0       70 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.3/fastapi_manager/__init__.py
--rw-r--r--   0        0        0      713 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.3/fastapi_manager/decorators.py
--rw-r--r--   0        0        0     2452 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.3/fastapi_manager/managers.py
--rw-r--r--   0        0        0      513 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.3/fastapi_manager/meta.py
--rw-r--r--   0        0        0     3076 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.3/.gitignore
--rw-r--r--   0        0        0     1073 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.3/LICENSE
--rw-r--r--   0        0        0      130 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.3/README.md
--rw-r--r--   0        0        0      730 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.3/pyproject.toml
--rw-r--r--   0        0        0      796 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.3/PKG-INFO
+-rw-r--r--   0        0        0       35 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.4/requirements.txt
+-rw-r--r--   0        0        0       70 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.4/fastapi_manager/__init__.py
+-rw-r--r--   0        0        0      713 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.4/fastapi_manager/decorators.py
+-rw-r--r--   0        0        0     2456 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.4/fastapi_manager/managers.py
+-rw-r--r--   0        0        0     1046 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.4/fastapi_manager/meta.py
+-rw-r--r--   0        0        0     3076 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.4/.gitignore
+-rw-r--r--   0        0        0     1073 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.4/LICENSE
+-rw-r--r--   0        0        0      130 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.4/README.md
+-rw-r--r--   0        0        0      730 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.4/pyproject.toml
+-rw-r--r--   0        0        0      796 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.4/PKG-INFO
```

### Comparing `fastapi_orm_manager-0.0.3/fastapi_manager/decorators.py` & `fastapi_orm_manager-0.0.4/fastapi_manager/decorators.py`

 * *Files identical despite different names*

### Comparing `fastapi_orm_manager-0.0.3/fastapi_manager/managers.py` & `fastapi_orm_manager-0.0.4/fastapi_manager/managers.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,21 +1,21 @@
-from typing import Generic, Type, TypeVar
+from typing import Generic, Sequence, Type, TypeVar
 
 from pydantic import BaseModel
 from sqlalchemy import select
 from sqlalchemy.exc import NoResultFound
 from sqlalchemy.ext.asyncio import AsyncSession
 from sqlalchemy.orm import Session
 
-from .meta import SQLAlchemyErrorHandlerMeta
+from .meta import BaseManagerMeta
 
 T = TypeVar('T')
 
 
-class BaseManager(Generic[T], metaclass=SQLAlchemyErrorHandlerMeta):
+class BaseManager(Generic[T], metaclass=BaseManagerMeta):
     model: Type[T]
 
     class Params(BaseModel):
         pass
 
     @classmethod
     def add(cls, session: Session, instance: T):
@@ -45,22 +45,22 @@
 
         try:
             return item.scalar()
         except NoResultFound:
             return None
 
     @classmethod
-    def search(cls, session: Session, params: Params) -> [T]:
+    def search(cls, session: Session, params: Params) -> Sequence[T]:
         statement = select(cls.model).filter_by(**params.dict(exclude_none=True))
 
         items = session.execute(statement)
         return items.scalars().all()
 
     @classmethod
-    async def async_search(cls, session: AsyncSession, params: Params) -> [T]:
+    async def async_search(cls, session: AsyncSession, params: Params) -> Sequence[T]:
         statement = select(cls.model).filter_by(**params.dict(exclude_none=True))
 
         items = await session.execute(statement)
         return items.scalars().all()
 
     @classmethod
     def update(cls, session: Session, instance: T, **kwargs):
```

### Comparing `fastapi_orm_manager-0.0.3/.gitignore` & `fastapi_orm_manager-0.0.4/.gitignore`

 * *Files identical despite different names*

### Comparing `fastapi_orm_manager-0.0.3/LICENSE` & `fastapi_orm_manager-0.0.4/LICENSE`

 * *Files identical despite different names*

### Comparing `fastapi_orm_manager-0.0.3/pyproject.toml` & `fastapi_orm_manager-0.0.4/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 [build-system]
 requires = ["hatchling"]
 build-backend = "hatchling.build"
 
 [project]
 name = "fastapi-orm-manager"
-version = "0.0.3"
+version = "0.0.4"
 authors = [
   { name="Nazar Kaliuzhnyi", email="kaluzghnyy@gmail.com" },
 ]
 description = "A base manager class to handle CRUD on SQLAlchemy models. Suitable to use in FastAPI projects."
 readme = "README.md"
 requires-python = ">=3.7"
 classifiers = [
```

### Comparing `fastapi_orm_manager-0.0.3/PKG-INFO` & `fastapi_orm_manager-0.0.4/PKG-INFO`

 * *Files 10% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: fastapi-orm-manager
-Version: 0.0.3
+Version: 0.0.4
 Summary: A base manager class to handle CRUD on SQLAlchemy models. Suitable to use in FastAPI projects.
 Project-URL: Homepage, https://github.com/nakeeon/FastAPI-ORM-Manager
 Project-URL: Bug Tracker, https://github.com/nakeeon/FastAPI-ORM-Manager/issues
 Author-email: Nazar Kaliuzhnyi <kaluzghnyy@gmail.com>
 License-File: LICENSE
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```

