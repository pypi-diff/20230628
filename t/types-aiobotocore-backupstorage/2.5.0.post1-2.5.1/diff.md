# Comparing `tmp/types-aiobotocore-backupstorage-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-backupstorage-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-backupstorage-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:15 2023, max compression
+gzip compressed data, was "types-aiobotocore-backupstorage-2.5.1.tar", last modified: Wed Jun 28 01:43:08 2023, max compression
```

## Comparing `types-aiobotocore-backupstorage-2.5.0.post1.tar` & `types-aiobotocore-backupstorage-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:15.178974 types-aiobotocore-backupstorage-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:10:07.000000 types-aiobotocore-backupstorage-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    13069 2023-03-11 12:26:15.170973 types-aiobotocore-backupstorage-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    11474 2023-03-11 12:10:07.000000 types-aiobotocore-backupstorage-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:15.178974 types-aiobotocore-backupstorage-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2166 2023-03-11 12:10:07.000000 types-aiobotocore-backupstorage-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:15.170973 types-aiobotocore-backupstorage-2.5.0.post1/types_aiobotocore_backupstorage/
--rw-r--r--   0 runner    (1001) docker     (123)      490 2023-03-11 12:10:07.000000 types-aiobotocore-backupstorage-2.5.0.post1/types_aiobotocore_backupstorage/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      489 2023-03-11 12:10:07.000000 types-aiobotocore-backupstorage-2.5.0.post1/types_aiobotocore_backupstorage/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      967 2023-03-11 12:10:07.000000 types-aiobotocore-backupstorage-2.5.0.post1/types_aiobotocore_backupstorage/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    11103 2023-03-11 12:10:07.000000 types-aiobotocore-backupstorage-2.5.0.post1/types_aiobotocore_backupstorage/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    11085 2023-03-11 12:10:07.000000 types-aiobotocore-backupstorage-2.5.0.post1/types_aiobotocore_backupstorage/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7616 2023-03-11 12:10:08.000000 types-aiobotocore-backupstorage-2.5.0.post1/types_aiobotocore_backupstorage/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7614 2023-03-11 12:10:08.000000 types-aiobotocore-backupstorage-2.5.0.post1/types_aiobotocore_backupstorage/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:10:07.000000 types-aiobotocore-backupstorage-2.5.0.post1/types_aiobotocore_backupstorage/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     8464 2023-03-11 12:10:08.000000 types-aiobotocore-backupstorage-2.5.0.post1/types_aiobotocore_backupstorage/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     8451 2023-03-11 12:10:08.000000 types-aiobotocore-backupstorage-2.5.0.post1/types_aiobotocore_backupstorage/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:10:07.000000 types-aiobotocore-backupstorage-2.5.0.post1/types_aiobotocore_backupstorage/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:15.170973 types-aiobotocore-backupstorage-2.5.0.post1/types_aiobotocore_backupstorage.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    13069 2023-03-11 12:26:14.000000 types-aiobotocore-backupstorage-2.5.0.post1/types_aiobotocore_backupstorage.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      836 2023-03-11 12:26:15.000000 types-aiobotocore-backupstorage-2.5.0.post1/types_aiobotocore_backupstorage.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:14.000000 types-aiobotocore-backupstorage-2.5.0.post1/types_aiobotocore_backupstorage.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:14.000000 types-aiobotocore-backupstorage-2.5.0.post1/types_aiobotocore_backupstorage.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:14.000000 types-aiobotocore-backupstorage-2.5.0.post1/types_aiobotocore_backupstorage.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       32 2023-03-11 12:26:14.000000 types-aiobotocore-backupstorage-2.5.0.post1/types_aiobotocore_backupstorage.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:08.898099 types-aiobotocore-backupstorage-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:26:44.000000 types-aiobotocore-backupstorage-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    13067 2023-06-28 01:43:08.898099 types-aiobotocore-backupstorage-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    11478 2023-06-28 01:26:44.000000 types-aiobotocore-backupstorage-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:08.898099 types-aiobotocore-backupstorage-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2160 2023-06-28 01:26:44.000000 types-aiobotocore-backupstorage-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:08.894099 types-aiobotocore-backupstorage-2.5.1/types_aiobotocore_backupstorage/
+-rw-r--r--   0 runner    (1001) docker     (123)      490 2023-06-28 01:26:44.000000 types-aiobotocore-backupstorage-2.5.1/types_aiobotocore_backupstorage/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      489 2023-06-28 01:26:44.000000 types-aiobotocore-backupstorage-2.5.1/types_aiobotocore_backupstorage/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      955 2023-06-28 01:26:44.000000 types-aiobotocore-backupstorage-2.5.1/types_aiobotocore_backupstorage/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11103 2023-06-28 01:26:44.000000 types-aiobotocore-backupstorage-2.5.1/types_aiobotocore_backupstorage/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11085 2023-06-28 01:26:44.000000 types-aiobotocore-backupstorage-2.5.1/types_aiobotocore_backupstorage/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     7825 2023-06-28 01:26:44.000000 types-aiobotocore-backupstorage-2.5.1/types_aiobotocore_backupstorage/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7823 2023-06-28 01:26:44.000000 types-aiobotocore-backupstorage-2.5.1/types_aiobotocore_backupstorage/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:26:44.000000 types-aiobotocore-backupstorage-2.5.1/types_aiobotocore_backupstorage/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     8482 2023-06-28 01:26:44.000000 types-aiobotocore-backupstorage-2.5.1/types_aiobotocore_backupstorage/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8469 2023-06-28 01:26:44.000000 types-aiobotocore-backupstorage-2.5.1/types_aiobotocore_backupstorage/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:26:44.000000 types-aiobotocore-backupstorage-2.5.1/types_aiobotocore_backupstorage/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:08.898099 types-aiobotocore-backupstorage-2.5.1/types_aiobotocore_backupstorage.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    13067 2023-06-28 01:43:08.000000 types-aiobotocore-backupstorage-2.5.1/types_aiobotocore_backupstorage.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      836 2023-06-28 01:43:08.000000 types-aiobotocore-backupstorage-2.5.1/types_aiobotocore_backupstorage.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:08.000000 types-aiobotocore-backupstorage-2.5.1/types_aiobotocore_backupstorage.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:08.000000 types-aiobotocore-backupstorage-2.5.1/types_aiobotocore_backupstorage.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:08.000000 types-aiobotocore-backupstorage-2.5.1/types_aiobotocore_backupstorage.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       32 2023-06-28 01:43:08.000000 types-aiobotocore-backupstorage-2.5.1/types_aiobotocore_backupstorage.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-backupstorage-2.5.0.post1/LICENSE` & `types-aiobotocore-backupstorage-2.5.1/LICENSE`

 * *Files 12% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 MIT License
 
-Copyright (c) 2022 Vlad Emelianov
+Copyright (c) 2023 Vlad Emelianov
 
 Permission is hereby granted, free of charge, to any person obtaining a copy
 of this software and associated documentation files (the "Software"), to deal
 in the Software without restriction, including without limitation the rights
 to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
 copies of the Software, and to permit persons to whom the Software is
 furnished to do so, subject to the following conditions:
```

### Comparing `types-aiobotocore-backupstorage-2.5.0.post1/PKG-INFO` & `types-aiobotocore-backupstorage-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-backupstorage
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.BackupStorage 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.BackupStorage 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backupstorage/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-backupstorage"></a>
 
 # types-aiobotocore-backupstorage
 
 [![PyPI - types-aiobotocore-backupstorage](https://img.shields.io/pypi/v/types-aiobotocore-backupstorage.svg?color=blue)](https://pypi.org/project/types-aiobotocore-backupstorage)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-backupstorage.svg?color=blue)](https://pypi.org/project/types-aiobotocore-backupstorage)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backupstorage/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-backupstorage?color=blue)](https://pypistats.org/packages/types-aiobotocore-backupstorage)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.BackupStorage 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backupstorage.html#BackupStorage)
+[aiobotocore.BackupStorage 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backupstorage.html#BackupStorage)
 service compatible with [VSCode](https://code.visualstudio.com/),
 [PyCharm](https://www.jetbrains.com/pycharm/),
 [Emacs](https://www.gnu.org/software/emacs/),
 [Sublime Text](https://www.sublimetext.com/),
 [mypy](https://github.com/python/mypy),
 [pyright](https://github.com/microsoft/pyright) and other tools.
 
 Generated by
-[mypy-boto3-builder 7.13.0](https://github.com/youtype/mypy_boto3_builder).
+[mypy-boto3-builder 7.14.5](https://github.com/youtype/mypy_boto3_builder).
 
 More information can be found on
 [types-aiobotocore](https://pypi.org/project/types-aiobotocore/) page and in
 [types-aiobotocore-backupstorage docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backupstorage/).
 
 See how it helps to find and fix potential bugs:
 
@@ -294,75 +294,75 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_backupstorage.type_defs import (
     BackupObjectTypeDef,
     ChunkTypeDef,
     DeleteObjectInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetChunkInputRequestTypeDef,
+    GetChunkOutputTypeDef,
     GetObjectMetadataInputRequestTypeDef,
+    GetObjectMetadataOutputTypeDef,
     ListChunksInputRequestTypeDef,
     ListObjectsInputRequestTypeDef,
     NotifyObjectCompleteInputRequestTypeDef,
-    PutChunkInputRequestTypeDef,
-    PutObjectInputRequestTypeDef,
-    StartObjectInputRequestTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetChunkOutputTypeDef,
-    GetObjectMetadataOutputTypeDef,
-    ListChunksOutputTypeDef,
-    ListObjectsOutputTypeDef,
     NotifyObjectCompleteOutputTypeDef,
+    PutChunkInputRequestTypeDef,
     PutChunkOutputTypeDef,
+    PutObjectInputRequestTypeDef,
     PutObjectOutputTypeDef,
+    ResponseMetadataTypeDef,
+    StartObjectInputRequestTypeDef,
     StartObjectOutputTypeDef,
+    ListObjectsOutputTypeDef,
+    ListChunksOutputTypeDef,
 )
 
 
 def get_structure() -> BackupObjectTypeDef:
     return {...}
 ```
 
 <a id="how-it-works"></a>
 
 ## How it works
 
 Fully automated
 [mypy-boto3-builder](https://github.com/youtype/mypy_boto3_builder) carefully
 generates type annotations for each service, patiently waiting for
-`aiobotocore` updates. It delivers a drop-in type annotations for you and makes
+`aiobotocore` updates. It delivers drop-in type annotations for you and makes
 sure that:
 
 - All available `aiobotocore` services are covered.
 - Each public class and method of every `aiobotocore` service gets valid type
-  annotations extracted from the documentation (blame `botocore` docs if types
-  are incorrect).
+  annotations extracted from `botocore` schemas.
 - Type annotations include up-to-date documentation.
 - Link to documentation is provided for every method.
 - Code is processed by [black](https://github.com/psf/black) and
   [isort](https://github.com/PyCQA/isort) for readability.
 
 <a id="what's-new"></a>
 
 ## What's new
 
 <a id="implemented-features"></a>
 
 ### Implemented features
 
-- Fully type annotated `boto3`, `botocore` and `aiobotocore` libraries
+- Fully type annotated `boto3`, `botocore`, `aiobotocore` and `aioboto3`
+  libraries
 - `mypy`, `pyright`, `VSCode`, `PyCharm`, `Sublime Text` and `Emacs`
   compatibility
 - `Client`, `ServiceResource`, `Resource`, `Waiter` `Paginator` type
   annotations for each service
 - Generated `TypeDefs` for each service
 - Generated `Literals` for each service
-- Auto discovery of types for `boto3.client` and `boto3.session` calls
-- Auto discovery of types for `session.client` and `session.session` calls
+- Auto discovery of types for `boto3.client` and `boto3.resource` calls
+- Auto discovery of types for `session.client` and `session.resource` calls
 - Auto discovery of types for `client.get_waiter` and `client.get_paginator`
   calls
 - Auto discovery of types for `ServiceResource` and `Resource` collections
 - Auto discovery of types for `aiobotocore.Session.create_client` calls
 
 <a id="latest-changes"></a>
```

### Comparing `types-aiobotocore-backupstorage-2.5.0.post1/README.md` & `types-aiobotocore-backupstorage-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-backupstorage"></a>
 
 # types-aiobotocore-backupstorage
 
 [![PyPI - types-aiobotocore-backupstorage](https://img.shields.io/pypi/v/types-aiobotocore-backupstorage.svg?color=blue)](https://pypi.org/project/types-aiobotocore-backupstorage)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-backupstorage.svg?color=blue)](https://pypi.org/project/types-aiobotocore-backupstorage)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backupstorage/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-backupstorage?color=blue)](https://pypistats.org/packages/types-aiobotocore-backupstorage)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.BackupStorage 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backupstorage.html#BackupStorage)
+[aiobotocore.BackupStorage 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backupstorage.html#BackupStorage)
 service compatible with [VSCode](https://code.visualstudio.com/),
 [PyCharm](https://www.jetbrains.com/pycharm/),
 [Emacs](https://www.gnu.org/software/emacs/),
 [Sublime Text](https://www.sublimetext.com/),
 [mypy](https://github.com/python/mypy),
 [pyright](https://github.com/microsoft/pyright) and other tools.
 
 Generated by
-[mypy-boto3-builder 7.13.0](https://github.com/youtype/mypy_boto3_builder).
+[mypy-boto3-builder 7.14.5](https://github.com/youtype/mypy_boto3_builder).
 
 More information can be found on
 [types-aiobotocore](https://pypi.org/project/types-aiobotocore/) page and in
 [types-aiobotocore-backupstorage docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backupstorage/).
 
 See how it helps to find and fix potential bugs:
 
@@ -261,75 +261,75 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_backupstorage.type_defs import (
     BackupObjectTypeDef,
     ChunkTypeDef,
     DeleteObjectInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetChunkInputRequestTypeDef,
+    GetChunkOutputTypeDef,
     GetObjectMetadataInputRequestTypeDef,
+    GetObjectMetadataOutputTypeDef,
     ListChunksInputRequestTypeDef,
     ListObjectsInputRequestTypeDef,
     NotifyObjectCompleteInputRequestTypeDef,
-    PutChunkInputRequestTypeDef,
-    PutObjectInputRequestTypeDef,
-    StartObjectInputRequestTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetChunkOutputTypeDef,
-    GetObjectMetadataOutputTypeDef,
-    ListChunksOutputTypeDef,
-    ListObjectsOutputTypeDef,
     NotifyObjectCompleteOutputTypeDef,
+    PutChunkInputRequestTypeDef,
     PutChunkOutputTypeDef,
+    PutObjectInputRequestTypeDef,
     PutObjectOutputTypeDef,
+    ResponseMetadataTypeDef,
+    StartObjectInputRequestTypeDef,
     StartObjectOutputTypeDef,
+    ListObjectsOutputTypeDef,
+    ListChunksOutputTypeDef,
 )
 
 
 def get_structure() -> BackupObjectTypeDef:
     return {...}
 ```
 
 <a id="how-it-works"></a>
 
 ## How it works
 
 Fully automated
 [mypy-boto3-builder](https://github.com/youtype/mypy_boto3_builder) carefully
 generates type annotations for each service, patiently waiting for
-`aiobotocore` updates. It delivers a drop-in type annotations for you and makes
+`aiobotocore` updates. It delivers drop-in type annotations for you and makes
 sure that:
 
 - All available `aiobotocore` services are covered.
 - Each public class and method of every `aiobotocore` service gets valid type
-  annotations extracted from the documentation (blame `botocore` docs if types
-  are incorrect).
+  annotations extracted from `botocore` schemas.
 - Type annotations include up-to-date documentation.
 - Link to documentation is provided for every method.
 - Code is processed by [black](https://github.com/psf/black) and
   [isort](https://github.com/PyCQA/isort) for readability.
 
 <a id="what's-new"></a>
 
 ## What's new
 
 <a id="implemented-features"></a>
 
 ### Implemented features
 
-- Fully type annotated `boto3`, `botocore` and `aiobotocore` libraries
+- Fully type annotated `boto3`, `botocore`, `aiobotocore` and `aioboto3`
+  libraries
 - `mypy`, `pyright`, `VSCode`, `PyCharm`, `Sublime Text` and `Emacs`
   compatibility
 - `Client`, `ServiceResource`, `Resource`, `Waiter` `Paginator` type
   annotations for each service
 - Generated `TypeDefs` for each service
 - Generated `Literals` for each service
-- Auto discovery of types for `boto3.client` and `boto3.session` calls
-- Auto discovery of types for `session.client` and `session.session` calls
+- Auto discovery of types for `boto3.client` and `boto3.resource` calls
+- Auto discovery of types for `session.client` and `session.resource` calls
 - Auto discovery of types for `client.get_waiter` and `client.get_paginator`
   calls
 - Auto discovery of types for `ServiceResource` and `Resource` collections
 - Auto discovery of types for `aiobotocore.Session.create_client` calls
 
 <a id="latest-changes"></a>
```

### Comparing `types-aiobotocore-backupstorage-2.5.0.post1/setup.py` & `types-aiobotocore-backupstorage-2.5.1/setup.py`

 * *Files 13% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-backupstorage.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-backupstorage",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_backupstorage"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.BackupStorage 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.BackupStorage 2.5.1 service generated with"
+        " mypy-boto3-builder 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -48,11 +48,11 @@
         "Documentation": (
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backupstorage/"
         ),
         "Source": "https://github.com/youtype/mypy_boto3_builder",
         "Tracker": "https://github.com/youtype/mypy_boto3_builder/issues",
     },
     install_requires=[
-        "typing-extensions>=4.1.0",
+        'typing-extensions>=4.1.0; python_version<"3.9"',
     ],
     zip_safe=False,
 )
```

### Comparing `types-aiobotocore-backupstorage-2.5.0.post1/types_aiobotocore_backupstorage/__main__.py` & `types-aiobotocore-backupstorage-2.5.1/types_aiobotocore_backupstorage/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.BackupStorage 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.BackupStorage 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backupstorage//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backupstorage.html#BackupStorage\nOther"
         " services:  https://pypi.org/project/boto3-stubs/\nChangelog:      "
         " https://github.com/youtype/mypy_boto3_builder/releases"
     )
 
 
 def print_version() -> None:
     """
     Print package version to stdout.
     """
-    print("2.5.0.post1")
+    print("2.5.1")
 
 
 def main() -> None:
     """
     Main CLI entrypoint.
     """
     if "--version" in sys.argv:
```

### Comparing `types-aiobotocore-backupstorage-2.5.0.post1/types_aiobotocore_backupstorage/client.py` & `types-aiobotocore-backupstorage-2.5.1/types_aiobotocore_backupstorage/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-backupstorage-2.5.0.post1/types_aiobotocore_backupstorage/client.pyi` & `types-aiobotocore-backupstorage-2.5.1/types_aiobotocore_backupstorage/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-backupstorage-2.5.0.post1/types_aiobotocore_backupstorage/literals.py` & `types-aiobotocore-backupstorage-2.5.1/types_aiobotocore_backupstorage/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -90,14 +90,15 @@
     "cloudwatch",
     "codeartifact",
     "codebuild",
     "codecatalyst",
     "codecommit",
     "codedeploy",
     "codeguru-reviewer",
+    "codeguru-security",
     "codeguruprofiler",
     "codepipeline",
     "codestar",
     "codestar-connections",
     "codestar-notifications",
     "cognito-identity",
     "cognito-idp",
@@ -176,14 +177,15 @@
     "honeycode",
     "iam",
     "identitystore",
     "imagebuilder",
     "importexport",
     "inspector",
     "inspector2",
+    "internetmonitor",
     "iot",
     "iot-data",
     "iot-jobs-data",
     "iot-roborunner",
     "iot1click-devices",
     "iot1click-projects",
     "iotanalytics",
@@ -194,14 +196,15 @@
     "iotfleetwise",
     "iotsecuretunneling",
     "iotsitewise",
     "iotthingsgraph",
     "iottwinmaker",
     "iotwireless",
     "ivs",
+    "ivs-realtime",
     "ivschat",
     "kafka",
     "kafkaconnect",
     "kendra",
     "kendra-ranking",
     "keyspaces",
     "kinesis",
@@ -237,14 +240,15 @@
     "marketplace-entitlement",
     "marketplacecommerceanalytics",
     "mediaconnect",
     "mediaconvert",
     "medialive",
     "mediapackage",
     "mediapackage-vod",
+    "mediapackagev2",
     "mediastore",
     "mediastore-data",
     "mediatailor",
     "memorydb",
     "meteringmarketplace",
     "mgh",
     "mgn",
@@ -263,16 +267,19 @@
     "oam",
     "omics",
     "opensearch",
     "opensearchserverless",
     "opsworks",
     "opsworkscm",
     "organizations",
+    "osis",
     "outposts",
     "panorama",
+    "payment-cryptography",
+    "payment-cryptography-data",
     "personalize",
     "personalize-events",
     "personalize-runtime",
     "pi",
     "pinpoint",
     "pinpoint-email",
     "pinpoint-sms-voice",
@@ -356,15 +363,17 @@
     "textract",
     "timestream-query",
     "timestream-write",
     "tnb",
     "transcribe",
     "transfer",
     "translate",
+    "verifiedpermissions",
     "voice-id",
+    "vpc-lattice",
     "waf",
     "waf-regional",
     "wafv2",
     "wellarchitected",
     "wisdom",
     "workdocs",
     "worklink",
```

### Comparing `types-aiobotocore-backupstorage-2.5.0.post1/types_aiobotocore_backupstorage/literals.pyi` & `types-aiobotocore-backupstorage-2.5.1/types_aiobotocore_backupstorage/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -88,14 +88,15 @@
     "cloudwatch",
     "codeartifact",
     "codebuild",
     "codecatalyst",
     "codecommit",
     "codedeploy",
     "codeguru-reviewer",
+    "codeguru-security",
     "codeguruprofiler",
     "codepipeline",
     "codestar",
     "codestar-connections",
     "codestar-notifications",
     "cognito-identity",
     "cognito-idp",
@@ -174,14 +175,15 @@
     "honeycode",
     "iam",
     "identitystore",
     "imagebuilder",
     "importexport",
     "inspector",
     "inspector2",
+    "internetmonitor",
     "iot",
     "iot-data",
     "iot-jobs-data",
     "iot-roborunner",
     "iot1click-devices",
     "iot1click-projects",
     "iotanalytics",
@@ -192,14 +194,15 @@
     "iotfleetwise",
     "iotsecuretunneling",
     "iotsitewise",
     "iotthingsgraph",
     "iottwinmaker",
     "iotwireless",
     "ivs",
+    "ivs-realtime",
     "ivschat",
     "kafka",
     "kafkaconnect",
     "kendra",
     "kendra-ranking",
     "keyspaces",
     "kinesis",
@@ -235,14 +238,15 @@
     "marketplace-entitlement",
     "marketplacecommerceanalytics",
     "mediaconnect",
     "mediaconvert",
     "medialive",
     "mediapackage",
     "mediapackage-vod",
+    "mediapackagev2",
     "mediastore",
     "mediastore-data",
     "mediatailor",
     "memorydb",
     "meteringmarketplace",
     "mgh",
     "mgn",
@@ -261,16 +265,19 @@
     "oam",
     "omics",
     "opensearch",
     "opensearchserverless",
     "opsworks",
     "opsworkscm",
     "organizations",
+    "osis",
     "outposts",
     "panorama",
+    "payment-cryptography",
+    "payment-cryptography-data",
     "personalize",
     "personalize-events",
     "personalize-runtime",
     "pi",
     "pinpoint",
     "pinpoint-email",
     "pinpoint-sms-voice",
@@ -354,15 +361,17 @@
     "textract",
     "timestream-query",
     "timestream-write",
     "tnb",
     "transcribe",
     "transfer",
     "translate",
+    "verifiedpermissions",
     "voice-id",
+    "vpc-lattice",
     "waf",
     "waf-regional",
     "wafv2",
     "wellarchitected",
     "wisdom",
     "workdocs",
     "worklink",
```

### Comparing `types-aiobotocore-backupstorage-2.5.0.post1/types_aiobotocore_backupstorage/type_defs.py` & `types-aiobotocore-backupstorage-2.5.1/types_aiobotocore_backupstorage/type_defs.py`

 * *Files 1% similar despite different names*

```diff
@@ -27,32 +27,32 @@
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "BackupObjectTypeDef",
     "ChunkTypeDef",
     "DeleteObjectInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetChunkInputRequestTypeDef",
+    "GetChunkOutputTypeDef",
     "GetObjectMetadataInputRequestTypeDef",
+    "GetObjectMetadataOutputTypeDef",
     "ListChunksInputRequestTypeDef",
     "ListObjectsInputRequestTypeDef",
     "NotifyObjectCompleteInputRequestTypeDef",
-    "PutChunkInputRequestTypeDef",
-    "PutObjectInputRequestTypeDef",
-    "StartObjectInputRequestTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetChunkOutputTypeDef",
-    "GetObjectMetadataOutputTypeDef",
-    "ListChunksOutputTypeDef",
-    "ListObjectsOutputTypeDef",
     "NotifyObjectCompleteOutputTypeDef",
+    "PutChunkInputRequestTypeDef",
     "PutChunkOutputTypeDef",
+    "PutObjectInputRequestTypeDef",
     "PutObjectOutputTypeDef",
+    "ResponseMetadataTypeDef",
+    "StartObjectInputRequestTypeDef",
     "StartObjectOutputTypeDef",
+    "ListObjectsOutputTypeDef",
+    "ListChunksOutputTypeDef",
 )
 
 _RequiredBackupObjectTypeDef = TypedDict(
     "_RequiredBackupObjectTypeDef",
     {
         "Name": str,
         "ObjectChecksum": str,
@@ -89,41 +89,60 @@
     "DeleteObjectInputRequestTypeDef",
     {
         "BackupJobId": str,
         "ObjectName": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetChunkInputRequestTypeDef = TypedDict(
     "GetChunkInputRequestTypeDef",
     {
         "StorageJobId": str,
         "ChunkToken": str,
     },
 )
 
+GetChunkOutputTypeDef = TypedDict(
+    "GetChunkOutputTypeDef",
+    {
+        "Data": StreamingBody,
+        "Length": int,
+        "Checksum": str,
+        "ChecksumAlgorithm": Literal["SHA256"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetObjectMetadataInputRequestTypeDef = TypedDict(
     "GetObjectMetadataInputRequestTypeDef",
     {
         "StorageJobId": str,
         "ObjectToken": str,
     },
 )
 
+GetObjectMetadataOutputTypeDef = TypedDict(
+    "GetObjectMetadataOutputTypeDef",
+    {
+        "MetadataString": str,
+        "MetadataBlob": StreamingBody,
+        "MetadataBlobLength": int,
+        "MetadataBlobChecksum": str,
+        "MetadataBlobChecksumAlgorithm": Literal["SHA256"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredListChunksInputRequestTypeDef = TypedDict(
     "_RequiredListChunksInputRequestTypeDef",
     {
         "StorageJobId": str,
         "ObjectToken": str,
     },
 )
@@ -194,27 +213,45 @@
 class NotifyObjectCompleteInputRequestTypeDef(
     _RequiredNotifyObjectCompleteInputRequestTypeDef,
     _OptionalNotifyObjectCompleteInputRequestTypeDef,
 ):
     pass
 
 
+NotifyObjectCompleteOutputTypeDef = TypedDict(
+    "NotifyObjectCompleteOutputTypeDef",
+    {
+        "ObjectChecksum": str,
+        "ObjectChecksumAlgorithm": Literal["SUMMARY"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 PutChunkInputRequestTypeDef = TypedDict(
     "PutChunkInputRequestTypeDef",
     {
         "BackupJobId": str,
         "UploadId": str,
         "ChunkIndex": int,
         "Data": Union[str, bytes, IO[Any], StreamingBody],
         "Length": int,
         "Checksum": str,
         "ChecksumAlgorithm": Literal["SHA256"],
     },
 )
 
+PutChunkOutputTypeDef = TypedDict(
+    "PutChunkOutputTypeDef",
+    {
+        "ChunkChecksum": str,
+        "ChunkChecksumAlgorithm": Literal["SHA256"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredPutObjectInputRequestTypeDef = TypedDict(
     "_RequiredPutObjectInputRequestTypeDef",
     {
         "BackupJobId": str,
         "ObjectName": str,
     },
 )
@@ -236,14 +273,36 @@
 
 class PutObjectInputRequestTypeDef(
     _RequiredPutObjectInputRequestTypeDef, _OptionalPutObjectInputRequestTypeDef
 ):
     pass
 
 
+PutObjectOutputTypeDef = TypedDict(
+    "PutObjectOutputTypeDef",
+    {
+        "InlineChunkChecksum": str,
+        "InlineChunkChecksumAlgorithm": Literal["SHA256"],
+        "ObjectChecksum": str,
+        "ObjectChecksumAlgorithm": Literal["SUMMARY"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
+    {
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
+    },
+)
+
 _RequiredStartObjectInputRequestTypeDef = TypedDict(
     "_RequiredStartObjectInputRequestTypeDef",
     {
         "BackupJobId": str,
         "ObjectName": str,
     },
 )
@@ -258,91 +317,32 @@
 
 class StartObjectInputRequestTypeDef(
     _RequiredStartObjectInputRequestTypeDef, _OptionalStartObjectInputRequestTypeDef
 ):
     pass
 
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetChunkOutputTypeDef = TypedDict(
-    "GetChunkOutputTypeDef",
-    {
-        "Data": StreamingBody,
-        "Length": int,
-        "Checksum": str,
-        "ChecksumAlgorithm": Literal["SHA256"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetObjectMetadataOutputTypeDef = TypedDict(
-    "GetObjectMetadataOutputTypeDef",
-    {
-        "MetadataString": str,
-        "MetadataBlob": StreamingBody,
-        "MetadataBlobLength": int,
-        "MetadataBlobChecksum": str,
-        "MetadataBlobChecksumAlgorithm": Literal["SHA256"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListChunksOutputTypeDef = TypedDict(
-    "ListChunksOutputTypeDef",
+StartObjectOutputTypeDef = TypedDict(
+    "StartObjectOutputTypeDef",
     {
-        "ChunkList": List[ChunkTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "UploadId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListObjectsOutputTypeDef = TypedDict(
     "ListObjectsOutputTypeDef",
     {
         "ObjectList": List[BackupObjectTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-NotifyObjectCompleteOutputTypeDef = TypedDict(
-    "NotifyObjectCompleteOutputTypeDef",
-    {
-        "ObjectChecksum": str,
-        "ObjectChecksumAlgorithm": Literal["SUMMARY"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutChunkOutputTypeDef = TypedDict(
-    "PutChunkOutputTypeDef",
-    {
-        "ChunkChecksum": str,
-        "ChunkChecksumAlgorithm": Literal["SHA256"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-PutObjectOutputTypeDef = TypedDict(
-    "PutObjectOutputTypeDef",
-    {
-        "InlineChunkChecksum": str,
-        "InlineChunkChecksumAlgorithm": Literal["SHA256"],
-        "ObjectChecksum": str,
-        "ObjectChecksumAlgorithm": Literal["SUMMARY"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartObjectOutputTypeDef = TypedDict(
-    "StartObjectOutputTypeDef",
+ListChunksOutputTypeDef = TypedDict(
+    "ListChunksOutputTypeDef",
     {
-        "UploadId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ChunkList": List[ChunkTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-backupstorage-2.5.0.post1/types_aiobotocore_backupstorage/type_defs.pyi` & `types-aiobotocore-backupstorage-2.5.1/types_aiobotocore_backupstorage/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -26,32 +26,32 @@
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "BackupObjectTypeDef",
     "ChunkTypeDef",
     "DeleteObjectInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetChunkInputRequestTypeDef",
+    "GetChunkOutputTypeDef",
     "GetObjectMetadataInputRequestTypeDef",
+    "GetObjectMetadataOutputTypeDef",
     "ListChunksInputRequestTypeDef",
     "ListObjectsInputRequestTypeDef",
     "NotifyObjectCompleteInputRequestTypeDef",
-    "PutChunkInputRequestTypeDef",
-    "PutObjectInputRequestTypeDef",
-    "StartObjectInputRequestTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetChunkOutputTypeDef",
-    "GetObjectMetadataOutputTypeDef",
-    "ListChunksOutputTypeDef",
-    "ListObjectsOutputTypeDef",
     "NotifyObjectCompleteOutputTypeDef",
+    "PutChunkInputRequestTypeDef",
     "PutChunkOutputTypeDef",
+    "PutObjectInputRequestTypeDef",
     "PutObjectOutputTypeDef",
+    "ResponseMetadataTypeDef",
+    "StartObjectInputRequestTypeDef",
     "StartObjectOutputTypeDef",
+    "ListObjectsOutputTypeDef",
+    "ListChunksOutputTypeDef",
 )
 
 _RequiredBackupObjectTypeDef = TypedDict(
     "_RequiredBackupObjectTypeDef",
     {
         "Name": str,
         "ObjectChecksum": str,
@@ -86,41 +86,60 @@
     "DeleteObjectInputRequestTypeDef",
     {
         "BackupJobId": str,
         "ObjectName": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetChunkInputRequestTypeDef = TypedDict(
     "GetChunkInputRequestTypeDef",
     {
         "StorageJobId": str,
         "ChunkToken": str,
     },
 )
 
+GetChunkOutputTypeDef = TypedDict(
+    "GetChunkOutputTypeDef",
+    {
+        "Data": StreamingBody,
+        "Length": int,
+        "Checksum": str,
+        "ChecksumAlgorithm": Literal["SHA256"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetObjectMetadataInputRequestTypeDef = TypedDict(
     "GetObjectMetadataInputRequestTypeDef",
     {
         "StorageJobId": str,
         "ObjectToken": str,
     },
 )
 
+GetObjectMetadataOutputTypeDef = TypedDict(
+    "GetObjectMetadataOutputTypeDef",
+    {
+        "MetadataString": str,
+        "MetadataBlob": StreamingBody,
+        "MetadataBlobLength": int,
+        "MetadataBlobChecksum": str,
+        "MetadataBlobChecksumAlgorithm": Literal["SHA256"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredListChunksInputRequestTypeDef = TypedDict(
     "_RequiredListChunksInputRequestTypeDef",
     {
         "StorageJobId": str,
         "ObjectToken": str,
     },
 )
@@ -185,27 +204,45 @@
 
 class NotifyObjectCompleteInputRequestTypeDef(
     _RequiredNotifyObjectCompleteInputRequestTypeDef,
     _OptionalNotifyObjectCompleteInputRequestTypeDef,
 ):
     pass
 
+NotifyObjectCompleteOutputTypeDef = TypedDict(
+    "NotifyObjectCompleteOutputTypeDef",
+    {
+        "ObjectChecksum": str,
+        "ObjectChecksumAlgorithm": Literal["SUMMARY"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 PutChunkInputRequestTypeDef = TypedDict(
     "PutChunkInputRequestTypeDef",
     {
         "BackupJobId": str,
         "UploadId": str,
         "ChunkIndex": int,
         "Data": Union[str, bytes, IO[Any], StreamingBody],
         "Length": int,
         "Checksum": str,
         "ChecksumAlgorithm": Literal["SHA256"],
     },
 )
 
+PutChunkOutputTypeDef = TypedDict(
+    "PutChunkOutputTypeDef",
+    {
+        "ChunkChecksum": str,
+        "ChunkChecksumAlgorithm": Literal["SHA256"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredPutObjectInputRequestTypeDef = TypedDict(
     "_RequiredPutObjectInputRequestTypeDef",
     {
         "BackupJobId": str,
         "ObjectName": str,
     },
 )
@@ -225,14 +262,36 @@
 )
 
 class PutObjectInputRequestTypeDef(
     _RequiredPutObjectInputRequestTypeDef, _OptionalPutObjectInputRequestTypeDef
 ):
     pass
 
+PutObjectOutputTypeDef = TypedDict(
+    "PutObjectOutputTypeDef",
+    {
+        "InlineChunkChecksum": str,
+        "InlineChunkChecksumAlgorithm": Literal["SHA256"],
+        "ObjectChecksum": str,
+        "ObjectChecksumAlgorithm": Literal["SUMMARY"],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
+    {
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
+    },
+)
+
 _RequiredStartObjectInputRequestTypeDef = TypedDict(
     "_RequiredStartObjectInputRequestTypeDef",
     {
         "BackupJobId": str,
         "ObjectName": str,
     },
 )
@@ -245,91 +304,32 @@
 )
 
 class StartObjectInputRequestTypeDef(
     _RequiredStartObjectInputRequestTypeDef, _OptionalStartObjectInputRequestTypeDef
 ):
     pass
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetChunkOutputTypeDef = TypedDict(
-    "GetChunkOutputTypeDef",
-    {
-        "Data": StreamingBody,
-        "Length": int,
-        "Checksum": str,
-        "ChecksumAlgorithm": Literal["SHA256"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetObjectMetadataOutputTypeDef = TypedDict(
-    "GetObjectMetadataOutputTypeDef",
-    {
-        "MetadataString": str,
-        "MetadataBlob": StreamingBody,
-        "MetadataBlobLength": int,
-        "MetadataBlobChecksum": str,
-        "MetadataBlobChecksumAlgorithm": Literal["SHA256"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListChunksOutputTypeDef = TypedDict(
-    "ListChunksOutputTypeDef",
+StartObjectOutputTypeDef = TypedDict(
+    "StartObjectOutputTypeDef",
     {
-        "ChunkList": List[ChunkTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "UploadId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListObjectsOutputTypeDef = TypedDict(
     "ListObjectsOutputTypeDef",
     {
         "ObjectList": List[BackupObjectTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-NotifyObjectCompleteOutputTypeDef = TypedDict(
-    "NotifyObjectCompleteOutputTypeDef",
-    {
-        "ObjectChecksum": str,
-        "ObjectChecksumAlgorithm": Literal["SUMMARY"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutChunkOutputTypeDef = TypedDict(
-    "PutChunkOutputTypeDef",
-    {
-        "ChunkChecksum": str,
-        "ChunkChecksumAlgorithm": Literal["SHA256"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-PutObjectOutputTypeDef = TypedDict(
-    "PutObjectOutputTypeDef",
-    {
-        "InlineChunkChecksum": str,
-        "InlineChunkChecksumAlgorithm": Literal["SHA256"],
-        "ObjectChecksum": str,
-        "ObjectChecksumAlgorithm": Literal["SUMMARY"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartObjectOutputTypeDef = TypedDict(
-    "StartObjectOutputTypeDef",
+ListChunksOutputTypeDef = TypedDict(
+    "ListChunksOutputTypeDef",
     {
-        "UploadId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ChunkList": List[ChunkTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-backupstorage-2.5.0.post1/types_aiobotocore_backupstorage.egg-info/PKG-INFO` & `types-aiobotocore-backupstorage-2.5.1/types_aiobotocore_backupstorage.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-backupstorage
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.BackupStorage 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.BackupStorage 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backupstorage/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-backupstorage"></a>
 
 # types-aiobotocore-backupstorage
 
 [![PyPI - types-aiobotocore-backupstorage](https://img.shields.io/pypi/v/types-aiobotocore-backupstorage.svg?color=blue)](https://pypi.org/project/types-aiobotocore-backupstorage)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-backupstorage.svg?color=blue)](https://pypi.org/project/types-aiobotocore-backupstorage)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backupstorage/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-backupstorage?color=blue)](https://pypistats.org/packages/types-aiobotocore-backupstorage)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.BackupStorage 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backupstorage.html#BackupStorage)
+[aiobotocore.BackupStorage 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/backupstorage.html#BackupStorage)
 service compatible with [VSCode](https://code.visualstudio.com/),
 [PyCharm](https://www.jetbrains.com/pycharm/),
 [Emacs](https://www.gnu.org/software/emacs/),
 [Sublime Text](https://www.sublimetext.com/),
 [mypy](https://github.com/python/mypy),
 [pyright](https://github.com/microsoft/pyright) and other tools.
 
 Generated by
-[mypy-boto3-builder 7.13.0](https://github.com/youtype/mypy_boto3_builder).
+[mypy-boto3-builder 7.14.5](https://github.com/youtype/mypy_boto3_builder).
 
 More information can be found on
 [types-aiobotocore](https://pypi.org/project/types-aiobotocore/) page and in
 [types-aiobotocore-backupstorage docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_backupstorage/).
 
 See how it helps to find and fix potential bugs:
 
@@ -294,75 +294,75 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_backupstorage.type_defs import (
     BackupObjectTypeDef,
     ChunkTypeDef,
     DeleteObjectInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetChunkInputRequestTypeDef,
+    GetChunkOutputTypeDef,
     GetObjectMetadataInputRequestTypeDef,
+    GetObjectMetadataOutputTypeDef,
     ListChunksInputRequestTypeDef,
     ListObjectsInputRequestTypeDef,
     NotifyObjectCompleteInputRequestTypeDef,
-    PutChunkInputRequestTypeDef,
-    PutObjectInputRequestTypeDef,
-    StartObjectInputRequestTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetChunkOutputTypeDef,
-    GetObjectMetadataOutputTypeDef,
-    ListChunksOutputTypeDef,
-    ListObjectsOutputTypeDef,
     NotifyObjectCompleteOutputTypeDef,
+    PutChunkInputRequestTypeDef,
     PutChunkOutputTypeDef,
+    PutObjectInputRequestTypeDef,
     PutObjectOutputTypeDef,
+    ResponseMetadataTypeDef,
+    StartObjectInputRequestTypeDef,
     StartObjectOutputTypeDef,
+    ListObjectsOutputTypeDef,
+    ListChunksOutputTypeDef,
 )
 
 
 def get_structure() -> BackupObjectTypeDef:
     return {...}
 ```
 
 <a id="how-it-works"></a>
 
 ## How it works
 
 Fully automated
 [mypy-boto3-builder](https://github.com/youtype/mypy_boto3_builder) carefully
 generates type annotations for each service, patiently waiting for
-`aiobotocore` updates. It delivers a drop-in type annotations for you and makes
+`aiobotocore` updates. It delivers drop-in type annotations for you and makes
 sure that:
 
 - All available `aiobotocore` services are covered.
 - Each public class and method of every `aiobotocore` service gets valid type
-  annotations extracted from the documentation (blame `botocore` docs if types
-  are incorrect).
+  annotations extracted from `botocore` schemas.
 - Type annotations include up-to-date documentation.
 - Link to documentation is provided for every method.
 - Code is processed by [black](https://github.com/psf/black) and
   [isort](https://github.com/PyCQA/isort) for readability.
 
 <a id="what's-new"></a>
 
 ## What's new
 
 <a id="implemented-features"></a>
 
 ### Implemented features
 
-- Fully type annotated `boto3`, `botocore` and `aiobotocore` libraries
+- Fully type annotated `boto3`, `botocore`, `aiobotocore` and `aioboto3`
+  libraries
 - `mypy`, `pyright`, `VSCode`, `PyCharm`, `Sublime Text` and `Emacs`
   compatibility
 - `Client`, `ServiceResource`, `Resource`, `Waiter` `Paginator` type
   annotations for each service
 - Generated `TypeDefs` for each service
 - Generated `Literals` for each service
-- Auto discovery of types for `boto3.client` and `boto3.session` calls
-- Auto discovery of types for `session.client` and `session.session` calls
+- Auto discovery of types for `boto3.client` and `boto3.resource` calls
+- Auto discovery of types for `session.client` and `session.resource` calls
 - Auto discovery of types for `client.get_waiter` and `client.get_paginator`
   calls
 - Auto discovery of types for `ServiceResource` and `Resource` collections
 - Auto discovery of types for `aiobotocore.Session.create_client` calls
 
 <a id="latest-changes"></a>
```

### Comparing `types-aiobotocore-backupstorage-2.5.0.post1/types_aiobotocore_backupstorage.egg-info/SOURCES.txt` & `types-aiobotocore-backupstorage-2.5.1/types_aiobotocore_backupstorage.egg-info/SOURCES.txt`

 * *Files identical despite different names*

