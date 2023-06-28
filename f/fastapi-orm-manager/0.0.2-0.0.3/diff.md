# Comparing `tmp/fastapi_orm_manager-0.0.2.tar.gz` & `tmp/fastapi_orm_manager-0.0.3.tar.gz`

## Comparing `fastapi_orm_manager-0.0.2.tar` & `fastapi_orm_manager-0.0.3.tar`

### file list

```diff
@@ -1,18 +1,10 @@
--rw-r--r--   0        0        0       35 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.2/requirements.txt
--rw-r--r--   0        0        0      176 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.2/.idea/.gitignore
--rw-r--r--   0        0        0      206 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.2/.idea/misc.xml
--rw-r--r--   0        0        0      288 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.2/.idea/modules.xml
--rw-r--r--   0        0        0      338 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.2/.idea/sqlalchemy_manager.iml
--rw-r--r--   0        0        0      167 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.2/.idea/vcs.xml
--rw-r--r--   0        0        0     4997 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.2/.idea/workspace.xml
--rw-r--r--   0        0        0     4741 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.2/.idea/inspectionProfiles/Project_Default.xml
--rw-r--r--   0        0        0      174 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.2/.idea/inspectionProfiles/profiles_settings.xml
--rw-r--r--   0        0        0       70 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.2/fastapi_manager/__init__.py
--rw-r--r--   0        0        0      713 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.2/fastapi_manager/decorators.py
--rw-r--r--   0        0        0     2437 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.2/fastapi_manager/managers.py
--rw-r--r--   0        0        0      513 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.2/fastapi_manager/meta.py
--rw-r--r--   0        0        0     3077 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.2/.gitignore
--rw-r--r--   0        0        0     1073 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.2/LICENSE
--rw-r--r--   0        0        0      130 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.2/README.md
--rw-r--r--   0        0        0      730 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.2/pyproject.toml
--rw-r--r--   0        0        0      796 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.2/PKG-INFO
+-rw-r--r--   0        0        0       35 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.3/requirements.txt
+-rw-r--r--   0        0        0       70 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.3/fastapi_manager/__init__.py
+-rw-r--r--   0        0        0      713 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.3/fastapi_manager/decorators.py
+-rw-r--r--   0        0        0     2452 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.3/fastapi_manager/managers.py
+-rw-r--r--   0        0        0      513 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.3/fastapi_manager/meta.py
+-rw-r--r--   0        0        0     3076 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.3/.gitignore
+-rw-r--r--   0        0        0     1073 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.3/LICENSE
+-rw-r--r--   0        0        0      130 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.3/README.md
+-rw-r--r--   0        0        0      730 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.3/pyproject.toml
+-rw-r--r--   0        0        0      796 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.3/PKG-INFO
```

### Comparing `fastapi_orm_manager-0.0.2/fastapi_manager/decorators.py` & `fastapi_orm_manager-0.0.3/fastapi_manager/decorators.py`

 * *Files identical despite different names*

### Comparing `fastapi_orm_manager-0.0.2/fastapi_manager/managers.py` & `fastapi_orm_manager-0.0.3/fastapi_manager/managers.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,22 +1,22 @@
-from typing import Type, TypeVar
+from typing import Generic, Type, TypeVar
 
 from pydantic import BaseModel
 from sqlalchemy import select
 from sqlalchemy.exc import NoResultFound
 from sqlalchemy.ext.asyncio import AsyncSession
 from sqlalchemy.orm import Session
 
 from .meta import SQLAlchemyErrorHandlerMeta
 
 T = TypeVar('T')
 
 
-class BaseManager(metaclass=SQLAlchemyErrorHandlerMeta):
-    model: Type[T] = None
+class BaseManager(Generic[T], metaclass=SQLAlchemyErrorHandlerMeta):
+    model: Type[T]
 
     class Params(BaseModel):
         pass
 
     @classmethod
     def add(cls, session: Session, instance: T):
         session.add(instance)
@@ -79,8 +79,8 @@
     def delete(cls, session: Session, instance: T):
         session.delete(instance)
         session.commit()
 
     @classmethod
     async def async_delete(cls, session: AsyncSession, instance: T):
         await session.delete(instance)
-        await session.commit()
+        await session.commit()
```

### Comparing `fastapi_orm_manager-0.0.2/fastapi_manager/meta.py` & `fastapi_orm_manager-0.0.3/fastapi_manager/meta.py`

 * *Files identical despite different names*

### Comparing `fastapi_orm_manager-0.0.2/.gitignore` & `fastapi_orm_manager-0.0.3/.gitignore`

 * *Files 7% similar despite different names*

```diff
@@ -153,8 +153,8 @@
 cython_debug/
 
 # PyCharm
 #  JetBrains specific template is maintained in a separate JetBrains.gitignore that can
 #  be found at https://github.com/github/gitignore/blob/main/Global/JetBrains.gitignore
 #  and can be added to the global gitignore or merged into this file.  For a more nuclear
 #  option (not recommended) you can uncomment the following to ignore the entire idea folder.
-#.idea/
+.idea/
```

### Comparing `fastapi_orm_manager-0.0.2/LICENSE` & `fastapi_orm_manager-0.0.3/LICENSE`

 * *Files identical despite different names*

### Comparing `fastapi_orm_manager-0.0.2/pyproject.toml` & `fastapi_orm_manager-0.0.3/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 [build-system]
 requires = ["hatchling"]
 build-backend = "hatchling.build"
 
 [project]
 name = "fastapi-orm-manager"
-version = "0.0.2"
+version = "0.0.3"
 authors = [
   { name="Nazar Kaliuzhnyi", email="kaluzghnyy@gmail.com" },
 ]
 description = "A base manager class to handle CRUD on SQLAlchemy models. Suitable to use in FastAPI projects."
 readme = "README.md"
 requires-python = ">=3.7"
 classifiers = [
```

### Comparing `fastapi_orm_manager-0.0.2/PKG-INFO` & `fastapi_orm_manager-0.0.3/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: fastapi-orm-manager
-Version: 0.0.2
+Version: 0.0.3
 Summary: A base manager class to handle CRUD on SQLAlchemy models. Suitable to use in FastAPI projects.
 Project-URL: Homepage, https://github.com/nakeeon/FastAPI-ORM-Manager
 Project-URL: Bug Tracker, https://github.com/nakeeon/FastAPI-ORM-Manager/issues
 Author-email: Nazar Kaliuzhnyi <kaluzghnyy@gmail.com>
 License-File: LICENSE
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```

