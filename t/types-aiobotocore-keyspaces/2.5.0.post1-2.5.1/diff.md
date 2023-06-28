# Comparing `tmp/types-aiobotocore-keyspaces-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-keyspaces-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-keyspaces-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:50 2023, max compression
+gzip compressed data, was "types-aiobotocore-keyspaces-2.5.1.tar", last modified: Wed Jun 28 01:43:42 2023, max compression
```

## Comparing `types-aiobotocore-keyspaces-2.5.0.post1.tar` & `types-aiobotocore-keyspaces-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:50.043330 types-aiobotocore-keyspaces-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:16:53.000000 types-aiobotocore-keyspaces-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    14863 2023-03-11 12:26:50.043330 types-aiobotocore-keyspaces-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13284 2023-03-11 12:16:53.000000 types-aiobotocore-keyspaces-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:50.043330 types-aiobotocore-keyspaces-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2138 2023-03-11 12:16:53.000000 types-aiobotocore-keyspaces-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:50.039330 types-aiobotocore-keyspaces-2.5.0.post1/types_aiobotocore_keyspaces/
--rw-r--r--   0 runner    (1001) docker     (123)     1054 2023-03-11 12:16:53.000000 types-aiobotocore-keyspaces-2.5.0.post1/types_aiobotocore_keyspaces/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1053 2023-03-11 12:16:53.000000 types-aiobotocore-keyspaces-2.5.0.post1/types_aiobotocore_keyspaces/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      951 2023-03-11 12:16:53.000000 types-aiobotocore-keyspaces-2.5.0.post1/types_aiobotocore_keyspaces/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    14528 2023-03-11 12:16:53.000000 types-aiobotocore-keyspaces-2.5.0.post1/types_aiobotocore_keyspaces/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    14503 2023-03-11 12:16:53.000000 types-aiobotocore-keyspaces-2.5.0.post1/types_aiobotocore_keyspaces/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8704 2023-03-11 12:16:53.000000 types-aiobotocore-keyspaces-2.5.0.post1/types_aiobotocore_keyspaces/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8702 2023-03-11 12:16:53.000000 types-aiobotocore-keyspaces-2.5.0.post1/types_aiobotocore_keyspaces/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     4310 2023-03-11 12:16:53.000000 types-aiobotocore-keyspaces-2.5.0.post1/types_aiobotocore_keyspaces/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     4304 2023-03-11 12:16:53.000000 types-aiobotocore-keyspaces-2.5.0.post1/types_aiobotocore_keyspaces/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:16:53.000000 types-aiobotocore-keyspaces-2.5.0.post1/types_aiobotocore_keyspaces/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    15274 2023-03-11 12:16:53.000000 types-aiobotocore-keyspaces-2.5.0.post1/types_aiobotocore_keyspaces/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    15247 2023-03-11 12:16:53.000000 types-aiobotocore-keyspaces-2.5.0.post1/types_aiobotocore_keyspaces/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:16:53.000000 types-aiobotocore-keyspaces-2.5.0.post1/types_aiobotocore_keyspaces/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:50.043330 types-aiobotocore-keyspaces-2.5.0.post1/types_aiobotocore_keyspaces.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    14863 2023-03-11 12:26:49.000000 types-aiobotocore-keyspaces-2.5.0.post1/types_aiobotocore_keyspaces.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      851 2023-03-11 12:26:49.000000 types-aiobotocore-keyspaces-2.5.0.post1/types_aiobotocore_keyspaces.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:49.000000 types-aiobotocore-keyspaces-2.5.0.post1/types_aiobotocore_keyspaces.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:49.000000 types-aiobotocore-keyspaces-2.5.0.post1/types_aiobotocore_keyspaces.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:49.000000 types-aiobotocore-keyspaces-2.5.0.post1/types_aiobotocore_keyspaces.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       28 2023-03-11 12:26:49.000000 types-aiobotocore-keyspaces-2.5.0.post1/types_aiobotocore_keyspaces.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:42.402161 types-aiobotocore-keyspaces-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:33:33.000000 types-aiobotocore-keyspaces-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    14987 2023-06-28 01:43:42.402161 types-aiobotocore-keyspaces-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13414 2023-06-28 01:33:33.000000 types-aiobotocore-keyspaces-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:42.402161 types-aiobotocore-keyspaces-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2132 2023-06-28 01:33:33.000000 types-aiobotocore-keyspaces-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:42.402161 types-aiobotocore-keyspaces-2.5.1/types_aiobotocore_keyspaces/
+-rw-r--r--   0 runner    (1001) docker     (123)     1054 2023-06-28 01:33:33.000000 types-aiobotocore-keyspaces-2.5.1/types_aiobotocore_keyspaces/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1053 2023-06-28 01:33:33.000000 types-aiobotocore-keyspaces-2.5.1/types_aiobotocore_keyspaces/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      939 2023-06-28 01:33:33.000000 types-aiobotocore-keyspaces-2.5.1/types_aiobotocore_keyspaces/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14825 2023-06-28 01:33:33.000000 types-aiobotocore-keyspaces-2.5.1/types_aiobotocore_keyspaces/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14800 2023-06-28 01:33:33.000000 types-aiobotocore-keyspaces-2.5.1/types_aiobotocore_keyspaces/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9081 2023-06-28 01:33:33.000000 types-aiobotocore-keyspaces-2.5.1/types_aiobotocore_keyspaces/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9079 2023-06-28 01:33:33.000000 types-aiobotocore-keyspaces-2.5.1/types_aiobotocore_keyspaces/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     4196 2023-06-28 01:33:33.000000 types-aiobotocore-keyspaces-2.5.1/types_aiobotocore_keyspaces/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4191 2023-06-28 01:33:33.000000 types-aiobotocore-keyspaces-2.5.1/types_aiobotocore_keyspaces/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:33:33.000000 types-aiobotocore-keyspaces-2.5.1/types_aiobotocore_keyspaces/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    16637 2023-06-28 01:33:34.000000 types-aiobotocore-keyspaces-2.5.1/types_aiobotocore_keyspaces/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16606 2023-06-28 01:33:34.000000 types-aiobotocore-keyspaces-2.5.1/types_aiobotocore_keyspaces/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:33:33.000000 types-aiobotocore-keyspaces-2.5.1/types_aiobotocore_keyspaces/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:42.402161 types-aiobotocore-keyspaces-2.5.1/types_aiobotocore_keyspaces.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    14987 2023-06-28 01:43:42.000000 types-aiobotocore-keyspaces-2.5.1/types_aiobotocore_keyspaces.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      851 2023-06-28 01:43:42.000000 types-aiobotocore-keyspaces-2.5.1/types_aiobotocore_keyspaces.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:42.000000 types-aiobotocore-keyspaces-2.5.1/types_aiobotocore_keyspaces.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:42.000000 types-aiobotocore-keyspaces-2.5.1/types_aiobotocore_keyspaces.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:42.000000 types-aiobotocore-keyspaces-2.5.1/types_aiobotocore_keyspaces.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       28 2023-06-28 01:43:42.000000 types-aiobotocore-keyspaces-2.5.1/types_aiobotocore_keyspaces.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-keyspaces-2.5.0.post1/LICENSE` & `types-aiobotocore-keyspaces-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-keyspaces-2.5.0.post1/PKG-INFO` & `types-aiobotocore-keyspaces-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-keyspaces
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Keyspaces 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Keyspaces 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_keyspaces/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-keyspaces"></a>
 
 # types-aiobotocore-keyspaces
 
 [![PyPI - types-aiobotocore-keyspaces](https://img.shields.io/pypi/v/types-aiobotocore-keyspaces.svg?color=blue)](https://pypi.org/project/types-aiobotocore-keyspaces)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-keyspaces.svg?color=blue)](https://pypi.org/project/types-aiobotocore-keyspaces)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_keyspaces/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-keyspaces?color=blue)](https://pypistats.org/packages/types-aiobotocore-keyspaces)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Keyspaces 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/keyspaces.html#Keyspaces)
+[aiobotocore.Keyspaces 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/keyspaces.html#Keyspaces)
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
 [types-aiobotocore-keyspaces docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_keyspaces/).
 
 See how it helps to find and fix potential bugs:
 
@@ -300,82 +300,86 @@
 ### Literals
 
 `types_aiobotocore_keyspaces.literals` module contains literals extracted from
 shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_keyspaces.literals import (
+    ClientSideTimestampsStatusType,
     EncryptionTypeType,
     ListKeyspacesPaginatorName,
     ListTablesPaginatorName,
     ListTagsForResourcePaginatorName,
     PointInTimeRecoveryStatusType,
     SortOrderType,
     TableStatusType,
     ThroughputModeType,
     TimeToLiveStatusType,
+    rsType,
     KeyspacesServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
 
 
-def check_value(value: EncryptionTypeType) -> bool:
+def check_value(value: ClientSideTimestampsStatusType) -> bool:
     ...
 ```
 
 <a id="typed-dictionaries"></a>
 
 ### Typed dictionaries
 
 `types_aiobotocore_keyspaces.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_keyspaces.type_defs import (
     CapacitySpecificationSummaryTypeDef,
     CapacitySpecificationTypeDef,
+    ClientSideTimestampsTypeDef,
     ClusteringKeyTypeDef,
     ColumnDefinitionTypeDef,
     CommentTypeDef,
+    ReplicationSpecificationTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateKeyspaceResponseTypeDef,
     EncryptionSpecificationTypeDef,
     PointInTimeRecoveryTypeDef,
     TimeToLiveTypeDef,
+    CreateTableResponseTypeDef,
     DeleteKeyspaceRequestRequestTypeDef,
     DeleteTableRequestRequestTypeDef,
     GetKeyspaceRequestRequestTypeDef,
+    GetKeyspaceResponseTypeDef,
     GetTableRequestRequestTypeDef,
     PointInTimeRecoverySummaryTypeDef,
     KeyspaceSummaryTypeDef,
-    PaginatorConfigTypeDef,
+    ListKeyspacesRequestListKeyspacesPaginateTypeDef,
     ListKeyspacesRequestRequestTypeDef,
+    ListTablesRequestListTablesPaginateTypeDef,
     ListTablesRequestRequestTypeDef,
     TableSummaryTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     PartitionKeyTypeDef,
+    ResponseMetadataTypeDef,
+    RestoreTableResponseTypeDef,
     StaticColumnTypeDef,
+    UpdateTableResponseTypeDef,
     CreateKeyspaceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
-    CreateKeyspaceResponseTypeDef,
-    CreateTableResponseTypeDef,
-    GetKeyspaceResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    RestoreTableResponseTypeDef,
-    UpdateTableResponseTypeDef,
     RestoreTableRequestRequestTypeDef,
     UpdateTableRequestRequestTypeDef,
     ListKeyspacesResponseTypeDef,
-    ListKeyspacesRequestListKeyspacesPaginateTypeDef,
-    ListTablesRequestListTablesPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTablesResponseTypeDef,
     SchemaDefinitionTypeDef,
     CreateTableRequestRequestTypeDef,
     GetTableResponseTypeDef,
 )
 
 
@@ -386,43 +390,43 @@
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

### Comparing `types-aiobotocore-keyspaces-2.5.0.post1/README.md` & `types-aiobotocore-keyspaces-2.5.1/README.md`

 * *Files 0% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-keyspaces"></a>
 
 # types-aiobotocore-keyspaces
 
 [![PyPI - types-aiobotocore-keyspaces](https://img.shields.io/pypi/v/types-aiobotocore-keyspaces.svg?color=blue)](https://pypi.org/project/types-aiobotocore-keyspaces)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-keyspaces.svg?color=blue)](https://pypi.org/project/types-aiobotocore-keyspaces)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_keyspaces/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-keyspaces?color=blue)](https://pypistats.org/packages/types-aiobotocore-keyspaces)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Keyspaces 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/keyspaces.html#Keyspaces)
+[aiobotocore.Keyspaces 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/keyspaces.html#Keyspaces)
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
 [types-aiobotocore-keyspaces docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_keyspaces/).
 
 See how it helps to find and fix potential bugs:
 
@@ -267,82 +267,86 @@
 ### Literals
 
 `types_aiobotocore_keyspaces.literals` module contains literals extracted from
 shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_keyspaces.literals import (
+    ClientSideTimestampsStatusType,
     EncryptionTypeType,
     ListKeyspacesPaginatorName,
     ListTablesPaginatorName,
     ListTagsForResourcePaginatorName,
     PointInTimeRecoveryStatusType,
     SortOrderType,
     TableStatusType,
     ThroughputModeType,
     TimeToLiveStatusType,
+    rsType,
     KeyspacesServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
 
 
-def check_value(value: EncryptionTypeType) -> bool:
+def check_value(value: ClientSideTimestampsStatusType) -> bool:
     ...
 ```
 
 <a id="typed-dictionaries"></a>
 
 ### Typed dictionaries
 
 `types_aiobotocore_keyspaces.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_keyspaces.type_defs import (
     CapacitySpecificationSummaryTypeDef,
     CapacitySpecificationTypeDef,
+    ClientSideTimestampsTypeDef,
     ClusteringKeyTypeDef,
     ColumnDefinitionTypeDef,
     CommentTypeDef,
+    ReplicationSpecificationTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateKeyspaceResponseTypeDef,
     EncryptionSpecificationTypeDef,
     PointInTimeRecoveryTypeDef,
     TimeToLiveTypeDef,
+    CreateTableResponseTypeDef,
     DeleteKeyspaceRequestRequestTypeDef,
     DeleteTableRequestRequestTypeDef,
     GetKeyspaceRequestRequestTypeDef,
+    GetKeyspaceResponseTypeDef,
     GetTableRequestRequestTypeDef,
     PointInTimeRecoverySummaryTypeDef,
     KeyspaceSummaryTypeDef,
-    PaginatorConfigTypeDef,
+    ListKeyspacesRequestListKeyspacesPaginateTypeDef,
     ListKeyspacesRequestRequestTypeDef,
+    ListTablesRequestListTablesPaginateTypeDef,
     ListTablesRequestRequestTypeDef,
     TableSummaryTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     PartitionKeyTypeDef,
+    ResponseMetadataTypeDef,
+    RestoreTableResponseTypeDef,
     StaticColumnTypeDef,
+    UpdateTableResponseTypeDef,
     CreateKeyspaceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
-    CreateKeyspaceResponseTypeDef,
-    CreateTableResponseTypeDef,
-    GetKeyspaceResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    RestoreTableResponseTypeDef,
-    UpdateTableResponseTypeDef,
     RestoreTableRequestRequestTypeDef,
     UpdateTableRequestRequestTypeDef,
     ListKeyspacesResponseTypeDef,
-    ListKeyspacesRequestListKeyspacesPaginateTypeDef,
-    ListTablesRequestListTablesPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTablesResponseTypeDef,
     SchemaDefinitionTypeDef,
     CreateTableRequestRequestTypeDef,
     GetTableResponseTypeDef,
 )
 
 
@@ -353,43 +357,43 @@
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

### Comparing `types-aiobotocore-keyspaces-2.5.0.post1/setup.py` & `types-aiobotocore-keyspaces-2.5.1/setup.py`

 * *Files 11% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-keyspaces.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-keyspaces",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_keyspaces"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Keyspaces 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.Keyspaces 2.5.1 service generated with mypy-boto3-builder"
+        " 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -48,11 +48,11 @@
         "Documentation": (
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_keyspaces/"
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

### Comparing `types-aiobotocore-keyspaces-2.5.0.post1/types_aiobotocore_keyspaces/__init__.py` & `types-aiobotocore-keyspaces-2.5.1/types_aiobotocore_keyspaces/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-keyspaces-2.5.0.post1/types_aiobotocore_keyspaces/__init__.pyi` & `types-aiobotocore-keyspaces-2.5.1/types_aiobotocore_keyspaces/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-keyspaces-2.5.0.post1/types_aiobotocore_keyspaces/__main__.py` & `types-aiobotocore-keyspaces-2.5.1/types_aiobotocore_keyspaces/__main__.py`

 * *Files 15% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Keyspaces 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Keyspaces 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_keyspaces//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/keyspaces.html#Keyspaces\nOther"
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

### Comparing `types-aiobotocore-keyspaces-2.5.0.post1/types_aiobotocore_keyspaces/client.py` & `types-aiobotocore-keyspaces-2.5.1/types_aiobotocore_keyspaces/client.py`

 * *Files 2% similar despite different names*

```diff
@@ -20,25 +20,27 @@
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .paginator import ListKeyspacesPaginator, ListTablesPaginator, ListTagsForResourcePaginator
 from .type_defs import (
     CapacitySpecificationTypeDef,
+    ClientSideTimestampsTypeDef,
     ColumnDefinitionTypeDef,
     CommentTypeDef,
     CreateKeyspaceResponseTypeDef,
     CreateTableResponseTypeDef,
     EncryptionSpecificationTypeDef,
     GetKeyspaceResponseTypeDef,
     GetTableResponseTypeDef,
     ListKeyspacesResponseTypeDef,
     ListTablesResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     PointInTimeRecoveryTypeDef,
+    ReplicationSpecificationTypeDef,
     RestoreTableResponseTypeDef,
     SchemaDefinitionTypeDef,
     TagTypeDef,
     TimeToLiveTypeDef,
     UpdateTableResponseTypeDef,
 )
 
@@ -99,15 +101,19 @@
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/keyspaces.html#Keyspaces.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_keyspaces/client/#close)
         """
 
     async def create_keyspace(
-        self, *, keyspaceName: str, tags: Sequence[TagTypeDef] = ...
+        self,
+        *,
+        keyspaceName: str,
+        tags: Sequence[TagTypeDef] = ...,
+        replicationSpecification: ReplicationSpecificationTypeDef = ...
     ) -> CreateKeyspaceResponseTypeDef:
         """
         The `CreateKeyspace` operation adds a new keyspace to your account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/keyspaces.html#Keyspaces.Client.create_keyspace)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_keyspaces/client/#create_keyspace)
         """
@@ -120,15 +126,16 @@
         schemaDefinition: SchemaDefinitionTypeDef,
         comment: CommentTypeDef = ...,
         capacitySpecification: CapacitySpecificationTypeDef = ...,
         encryptionSpecification: EncryptionSpecificationTypeDef = ...,
         pointInTimeRecovery: PointInTimeRecoveryTypeDef = ...,
         ttl: TimeToLiveTypeDef = ...,
         defaultTimeToLive: int = ...,
-        tags: Sequence[TagTypeDef] = ...
+        tags: Sequence[TagTypeDef] = ...,
+        clientSideTimestamps: ClientSideTimestampsTypeDef = ...
     ) -> CreateTableResponseTypeDef:
         """
         The `CreateTable` operation adds a new table to the specified keyspace.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/keyspaces.html#Keyspaces.Client.create_table)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_keyspaces/client/#create_table)
         """
@@ -256,15 +263,16 @@
         keyspaceName: str,
         tableName: str,
         addColumns: Sequence[ColumnDefinitionTypeDef] = ...,
         capacitySpecification: CapacitySpecificationTypeDef = ...,
         encryptionSpecification: EncryptionSpecificationTypeDef = ...,
         pointInTimeRecovery: PointInTimeRecoveryTypeDef = ...,
         ttl: TimeToLiveTypeDef = ...,
-        defaultTimeToLive: int = ...
+        defaultTimeToLive: int = ...,
+        clientSideTimestamps: ClientSideTimestampsTypeDef = ...
     ) -> UpdateTableResponseTypeDef:
         """
         Adds new columns to the table or updates one of the table's settings, for
         example capacity mode, encryption, point-in-time recovery, or ttl settings.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/keyspaces.html#Keyspaces.Client.update_table)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_keyspaces/client/#update_table)
```

### Comparing `types-aiobotocore-keyspaces-2.5.0.post1/types_aiobotocore_keyspaces/client.pyi` & `types-aiobotocore-keyspaces-2.5.1/types_aiobotocore_keyspaces/client.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -20,25 +20,27 @@
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .paginator import ListKeyspacesPaginator, ListTablesPaginator, ListTagsForResourcePaginator
 from .type_defs import (
     CapacitySpecificationTypeDef,
+    ClientSideTimestampsTypeDef,
     ColumnDefinitionTypeDef,
     CommentTypeDef,
     CreateKeyspaceResponseTypeDef,
     CreateTableResponseTypeDef,
     EncryptionSpecificationTypeDef,
     GetKeyspaceResponseTypeDef,
     GetTableResponseTypeDef,
     ListKeyspacesResponseTypeDef,
     ListTablesResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     PointInTimeRecoveryTypeDef,
+    ReplicationSpecificationTypeDef,
     RestoreTableResponseTypeDef,
     SchemaDefinitionTypeDef,
     TagTypeDef,
     TimeToLiveTypeDef,
     UpdateTableResponseTypeDef,
 )
 
@@ -92,15 +94,19 @@
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/keyspaces.html#Keyspaces.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_keyspaces/client/#close)
         """
     async def create_keyspace(
-        self, *, keyspaceName: str, tags: Sequence[TagTypeDef] = ...
+        self,
+        *,
+        keyspaceName: str,
+        tags: Sequence[TagTypeDef] = ...,
+        replicationSpecification: ReplicationSpecificationTypeDef = ...
     ) -> CreateKeyspaceResponseTypeDef:
         """
         The `CreateKeyspace` operation adds a new keyspace to your account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/keyspaces.html#Keyspaces.Client.create_keyspace)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_keyspaces/client/#create_keyspace)
         """
@@ -112,15 +118,16 @@
         schemaDefinition: SchemaDefinitionTypeDef,
         comment: CommentTypeDef = ...,
         capacitySpecification: CapacitySpecificationTypeDef = ...,
         encryptionSpecification: EncryptionSpecificationTypeDef = ...,
         pointInTimeRecovery: PointInTimeRecoveryTypeDef = ...,
         ttl: TimeToLiveTypeDef = ...,
         defaultTimeToLive: int = ...,
-        tags: Sequence[TagTypeDef] = ...
+        tags: Sequence[TagTypeDef] = ...,
+        clientSideTimestamps: ClientSideTimestampsTypeDef = ...
     ) -> CreateTableResponseTypeDef:
         """
         The `CreateTable` operation adds a new table to the specified keyspace.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/keyspaces.html#Keyspaces.Client.create_table)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_keyspaces/client/#create_table)
         """
@@ -236,15 +243,16 @@
         keyspaceName: str,
         tableName: str,
         addColumns: Sequence[ColumnDefinitionTypeDef] = ...,
         capacitySpecification: CapacitySpecificationTypeDef = ...,
         encryptionSpecification: EncryptionSpecificationTypeDef = ...,
         pointInTimeRecovery: PointInTimeRecoveryTypeDef = ...,
         ttl: TimeToLiveTypeDef = ...,
-        defaultTimeToLive: int = ...
+        defaultTimeToLive: int = ...,
+        clientSideTimestamps: ClientSideTimestampsTypeDef = ...
     ) -> UpdateTableResponseTypeDef:
         """
         Adds new columns to the table or updates one of the table's settings, for
         example capacity mode, encryption, point-in-time recovery, or ttl settings.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/keyspaces.html#Keyspaces.Client.update_table)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_keyspaces/client/#update_table)
```

### Comparing `types-aiobotocore-keyspaces-2.5.0.post1/types_aiobotocore_keyspaces/literals.py` & `types-aiobotocore-keyspaces-2.5.1/types_aiobotocore_keyspaces/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -2,45 +2,46 @@
 Type annotations for keyspaces service literal definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_keyspaces/literals/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_keyspaces.literals import EncryptionTypeType
+    from types_aiobotocore_keyspaces.literals import ClientSideTimestampsStatusType
 
-    data: EncryptionTypeType = "AWS_OWNED_KMS_KEY"
+    data: ClientSideTimestampsStatusType = "ENABLED"
     ```
 """
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
+    "ClientSideTimestampsStatusType",
     "EncryptionTypeType",
     "ListKeyspacesPaginatorName",
     "ListTablesPaginatorName",
     "ListTagsForResourcePaginatorName",
     "PointInTimeRecoveryStatusType",
     "SortOrderType",
     "TableStatusType",
     "ThroughputModeType",
     "TimeToLiveStatusType",
+    "rsType",
     "KeyspacesServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
-
+ClientSideTimestampsStatusType = Literal["ENABLED"]
 EncryptionTypeType = Literal["AWS_OWNED_KMS_KEY", "CUSTOMER_MANAGED_KMS_KEY"]
 ListKeyspacesPaginatorName = Literal["list_keyspaces"]
 ListTablesPaginatorName = Literal["list_tables"]
 ListTagsForResourcePaginatorName = Literal["list_tags_for_resource"]
 PointInTimeRecoveryStatusType = Literal["DISABLED", "ENABLED"]
 SortOrderType = Literal["ASC", "DESC"]
 TableStatusType = Literal[
@@ -50,14 +51,15 @@
     "DELETING",
     "INACCESSIBLE_ENCRYPTION_CREDENTIALS",
     "RESTORING",
     "UPDATING",
 ]
 ThroughputModeType = Literal["PAY_PER_REQUEST", "PROVISIONED"]
 TimeToLiveStatusType = Literal["ENABLED"]
+rsType = Literal["MULTI_REGION", "SINGLE_REGION"]
 KeyspacesServiceName = Literal["keyspaces"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
     "alexaforbusiness",
@@ -113,14 +115,15 @@
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
@@ -199,14 +202,15 @@
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
@@ -217,14 +221,15 @@
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
@@ -260,14 +265,15 @@
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
@@ -286,16 +292,19 @@
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
@@ -379,15 +388,17 @@
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

### Comparing `types-aiobotocore-keyspaces-2.5.0.post1/types_aiobotocore_keyspaces/literals.pyi` & `types-aiobotocore-keyspaces-2.5.1/types_aiobotocore_keyspaces/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -2,43 +2,48 @@
 Type annotations for keyspaces service literal definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_keyspaces/literals/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_keyspaces.literals import EncryptionTypeType
+    from types_aiobotocore_keyspaces.literals import ClientSideTimestampsStatusType
 
-    data: EncryptionTypeType = "AWS_OWNED_KMS_KEY"
+    data: ClientSideTimestampsStatusType = "ENABLED"
     ```
 """
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
+    "ClientSideTimestampsStatusType",
     "EncryptionTypeType",
     "ListKeyspacesPaginatorName",
     "ListTablesPaginatorName",
     "ListTagsForResourcePaginatorName",
     "PointInTimeRecoveryStatusType",
     "SortOrderType",
     "TableStatusType",
     "ThroughputModeType",
     "TimeToLiveStatusType",
+    "rsType",
     "KeyspacesServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
+
+ClientSideTimestampsStatusType = Literal["ENABLED"]
 EncryptionTypeType = Literal["AWS_OWNED_KMS_KEY", "CUSTOMER_MANAGED_KMS_KEY"]
 ListKeyspacesPaginatorName = Literal["list_keyspaces"]
 ListTablesPaginatorName = Literal["list_tables"]
 ListTagsForResourcePaginatorName = Literal["list_tags_for_resource"]
 PointInTimeRecoveryStatusType = Literal["DISABLED", "ENABLED"]
 SortOrderType = Literal["ASC", "DESC"]
 TableStatusType = Literal[
@@ -48,14 +53,15 @@
     "DELETING",
     "INACCESSIBLE_ENCRYPTION_CREDENTIALS",
     "RESTORING",
     "UPDATING",
 ]
 ThroughputModeType = Literal["PAY_PER_REQUEST", "PROVISIONED"]
 TimeToLiveStatusType = Literal["ENABLED"]
+rsType = Literal["MULTI_REGION", "SINGLE_REGION"]
 KeyspacesServiceName = Literal["keyspaces"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
     "alexaforbusiness",
@@ -111,14 +117,15 @@
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
@@ -197,14 +204,15 @@
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
@@ -215,14 +223,15 @@
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
@@ -258,14 +267,15 @@
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
@@ -284,16 +294,19 @@
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
@@ -377,15 +390,17 @@
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

### Comparing `types-aiobotocore-keyspaces-2.5.0.post1/types_aiobotocore_keyspaces/paginator.py` & `types-aiobotocore-keyspaces-2.5.1/types_aiobotocore_keyspaces/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -20,82 +20,70 @@
         client: KeyspacesClient
 
         list_keyspaces_paginator: ListKeyspacesPaginator = client.get_paginator("list_keyspaces")
         list_tables_paginator: ListTablesPaginator = client.get_paginator("list_tables")
         list_tags_for_resource_paginator: ListTagsForResourcePaginator = client.get_paginator("list_tags_for_resource")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListKeyspacesResponseTypeDef,
     ListTablesResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListKeyspacesPaginator", "ListTablesPaginator", "ListTagsForResourcePaginator")
 
-
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
-
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
-
 class ListKeyspacesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/keyspaces.html#Keyspaces.Paginator.ListKeyspaces)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_keyspaces/paginators/#listkeyspacespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListKeyspacesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/keyspaces.html#Keyspaces.Paginator.ListKeyspaces.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_keyspaces/paginators/#listkeyspacespaginator)
         """
 
-
 class ListTablesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/keyspaces.html#Keyspaces.Paginator.ListTables)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_keyspaces/paginators/#listtablespaginator)
     """
 
     def paginate(
-        self, *, keyspaceName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, keyspaceName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTablesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/keyspaces.html#Keyspaces.Paginator.ListTables.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_keyspaces/paginators/#listtablespaginator)
         """
 
-
 class ListTagsForResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/keyspaces.html#Keyspaces.Paginator.ListTagsForResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_keyspaces/paginators/#listtagsforresourcepaginator)
     """
 
     def paginate(
-        self, *, resourceArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, resourceArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsForResourceResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/keyspaces.html#Keyspaces.Paginator.ListTagsForResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_keyspaces/paginators/#listtagsforresourcepaginator)
         """
```

### Comparing `types-aiobotocore-keyspaces-2.5.0.post1/types_aiobotocore_keyspaces/paginator.pyi` & `types-aiobotocore-keyspaces-2.5.1/types_aiobotocore_keyspaces/paginator.py`

 * *Files 8% similar despite different names*

```diff
@@ -20,76 +20,75 @@
         client: KeyspacesClient
 
         list_keyspaces_paginator: ListKeyspacesPaginator = client.get_paginator("list_keyspaces")
         list_tables_paginator: ListTablesPaginator = client.get_paginator("list_tables")
         list_tags_for_resource_paginator: ListTagsForResourcePaginator = client.get_paginator("list_tags_for_resource")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListKeyspacesResponseTypeDef,
     ListTablesResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListKeyspacesPaginator", "ListTablesPaginator", "ListTagsForResourcePaginator")
 
+
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
+
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
+
 class ListKeyspacesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/keyspaces.html#Keyspaces.Paginator.ListKeyspaces)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_keyspaces/paginators/#listkeyspacespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListKeyspacesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/keyspaces.html#Keyspaces.Paginator.ListKeyspaces.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_keyspaces/paginators/#listkeyspacespaginator)
         """
 
+
 class ListTablesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/keyspaces.html#Keyspaces.Paginator.ListTables)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_keyspaces/paginators/#listtablespaginator)
     """
 
     def paginate(
-        self, *, keyspaceName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, keyspaceName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTablesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/keyspaces.html#Keyspaces.Paginator.ListTables.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_keyspaces/paginators/#listtablespaginator)
         """
 
+
 class ListTagsForResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/keyspaces.html#Keyspaces.Paginator.ListTagsForResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_keyspaces/paginators/#listtagsforresourcepaginator)
     """
 
     def paginate(
-        self, *, resourceArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, resourceArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsForResourceResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/keyspaces.html#Keyspaces.Paginator.ListTagsForResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_keyspaces/paginators/#listtagsforresourcepaginator)
         """
```

### Comparing `types-aiobotocore-keyspaces-2.5.0.post1/types_aiobotocore_keyspaces/type_defs.py` & `types-aiobotocore-keyspaces-2.5.1/types_aiobotocore_keyspaces/type_defs.py`

 * *Files 4% similar despite different names*

```diff
@@ -17,14 +17,15 @@
 
 from .literals import (
     EncryptionTypeType,
     PointInTimeRecoveryStatusType,
     SortOrderType,
     TableStatusType,
     ThroughputModeType,
+    rsType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
@@ -32,50 +33,52 @@
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "CapacitySpecificationSummaryTypeDef",
     "CapacitySpecificationTypeDef",
+    "ClientSideTimestampsTypeDef",
     "ClusteringKeyTypeDef",
     "ColumnDefinitionTypeDef",
     "CommentTypeDef",
+    "ReplicationSpecificationTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateKeyspaceResponseTypeDef",
     "EncryptionSpecificationTypeDef",
     "PointInTimeRecoveryTypeDef",
     "TimeToLiveTypeDef",
+    "CreateTableResponseTypeDef",
     "DeleteKeyspaceRequestRequestTypeDef",
     "DeleteTableRequestRequestTypeDef",
     "GetKeyspaceRequestRequestTypeDef",
+    "GetKeyspaceResponseTypeDef",
     "GetTableRequestRequestTypeDef",
     "PointInTimeRecoverySummaryTypeDef",
     "KeyspaceSummaryTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListKeyspacesRequestListKeyspacesPaginateTypeDef",
     "ListKeyspacesRequestRequestTypeDef",
+    "ListTablesRequestListTablesPaginateTypeDef",
     "ListTablesRequestRequestTypeDef",
     "TableSummaryTypeDef",
+    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "PartitionKeyTypeDef",
+    "ResponseMetadataTypeDef",
+    "RestoreTableResponseTypeDef",
     "StaticColumnTypeDef",
+    "UpdateTableResponseTypeDef",
     "CreateKeyspaceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
-    "CreateKeyspaceResponseTypeDef",
-    "CreateTableResponseTypeDef",
-    "GetKeyspaceResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "RestoreTableResponseTypeDef",
-    "UpdateTableResponseTypeDef",
     "RestoreTableRequestRequestTypeDef",
     "UpdateTableRequestRequestTypeDef",
     "ListKeyspacesResponseTypeDef",
-    "ListKeyspacesRequestListKeyspacesPaginateTypeDef",
-    "ListTablesRequestListTablesPaginateTypeDef",
-    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
     "ListTablesResponseTypeDef",
     "SchemaDefinitionTypeDef",
     "CreateTableRequestRequestTypeDef",
     "GetTableResponseTypeDef",
 )
 
 _RequiredCapacitySpecificationSummaryTypeDef = TypedDict(
@@ -119,14 +122,21 @@
 
 class CapacitySpecificationTypeDef(
     _RequiredCapacitySpecificationTypeDef, _OptionalCapacitySpecificationTypeDef
 ):
     pass
 
 
+ClientSideTimestampsTypeDef = TypedDict(
+    "ClientSideTimestampsTypeDef",
+    {
+        "status": Literal["ENABLED"],
+    },
+)
+
 ClusteringKeyTypeDef = TypedDict(
     "ClusteringKeyTypeDef",
     {
         "name": str,
         "orderBy": SortOrderType,
     },
 )
@@ -142,30 +152,48 @@
 CommentTypeDef = TypedDict(
     "CommentTypeDef",
     {
         "message": str,
     },
 )
 
+_RequiredReplicationSpecificationTypeDef = TypedDict(
+    "_RequiredReplicationSpecificationTypeDef",
+    {
+        "replicationStrategy": rsType,
+    },
+)
+_OptionalReplicationSpecificationTypeDef = TypedDict(
+    "_OptionalReplicationSpecificationTypeDef",
+    {
+        "regionList": Sequence[str],
+    },
+    total=False,
+)
+
+
+class ReplicationSpecificationTypeDef(
+    _RequiredReplicationSpecificationTypeDef, _OptionalReplicationSpecificationTypeDef
+):
+    pass
+
+
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "key": str,
         "value": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateKeyspaceResponseTypeDef = TypedDict(
+    "CreateKeyspaceResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "resourceArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredEncryptionSpecificationTypeDef = TypedDict(
     "_RequiredEncryptionSpecificationTypeDef",
     {
         "type": EncryptionTypeType,
@@ -196,14 +224,22 @@
 TimeToLiveTypeDef = TypedDict(
     "TimeToLiveTypeDef",
     {
         "status": Literal["ENABLED"],
     },
 )
 
+CreateTableResponseTypeDef = TypedDict(
+    "CreateTableResponseTypeDef",
+    {
+        "resourceArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteKeyspaceRequestRequestTypeDef = TypedDict(
     "DeleteKeyspaceRequestRequestTypeDef",
     {
         "keyspaceName": str,
     },
 )
 
@@ -218,14 +254,25 @@
 GetKeyspaceRequestRequestTypeDef = TypedDict(
     "GetKeyspaceRequestRequestTypeDef",
     {
         "keyspaceName": str,
     },
 )
 
+GetKeyspaceResponseTypeDef = TypedDict(
+    "GetKeyspaceResponseTypeDef",
+    {
+        "keyspaceName": str,
+        "resourceArn": str,
+        "replicationStrategy": rsType,
+        "replicationRegions": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetTableRequestRequestTypeDef = TypedDict(
     "GetTableRequestRequestTypeDef",
     {
         "keyspaceName": str,
         "tableName": str,
     },
 )
@@ -247,41 +294,74 @@
 
 class PointInTimeRecoverySummaryTypeDef(
     _RequiredPointInTimeRecoverySummaryTypeDef, _OptionalPointInTimeRecoverySummaryTypeDef
 ):
     pass
 
 
-KeyspaceSummaryTypeDef = TypedDict(
-    "KeyspaceSummaryTypeDef",
+_RequiredKeyspaceSummaryTypeDef = TypedDict(
+    "_RequiredKeyspaceSummaryTypeDef",
     {
         "keyspaceName": str,
         "resourceArn": str,
+        "replicationStrategy": rsType,
+    },
+)
+_OptionalKeyspaceSummaryTypeDef = TypedDict(
+    "_OptionalKeyspaceSummaryTypeDef",
+    {
+        "replicationRegions": List[str],
     },
+    total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+
+class KeyspaceSummaryTypeDef(_RequiredKeyspaceSummaryTypeDef, _OptionalKeyspaceSummaryTypeDef):
+    pass
+
+
+ListKeyspacesRequestListKeyspacesPaginateTypeDef = TypedDict(
+    "ListKeyspacesRequestListKeyspacesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListKeyspacesRequestRequestTypeDef = TypedDict(
     "ListKeyspacesRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+_RequiredListTablesRequestListTablesPaginateTypeDef = TypedDict(
+    "_RequiredListTablesRequestListTablesPaginateTypeDef",
+    {
+        "keyspaceName": str,
+    },
+)
+_OptionalListTablesRequestListTablesPaginateTypeDef = TypedDict(
+    "_OptionalListTablesRequestListTablesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListTablesRequestListTablesPaginateTypeDef(
+    _RequiredListTablesRequestListTablesPaginateTypeDef,
+    _OptionalListTablesRequestListTablesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListTablesRequestRequestTypeDef = TypedDict(
     "_RequiredListTablesRequestRequestTypeDef",
     {
         "keyspaceName": str,
     },
 )
 _OptionalListTablesRequestRequestTypeDef = TypedDict(
@@ -305,14 +385,36 @@
     {
         "keyspaceName": str,
         "tableName": str,
         "resourceArn": str,
     },
 )
 
+_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
+    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    {
+        "resourceArn": str,
+    },
+)
+_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
+    "_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListTagsForResourceRequestListTagsForResourcePaginateTypeDef(
+    _RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
+    _OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
+):
+    pass
+
+
 _RequiredListTagsForResourceRequestRequestTypeDef = TypedDict(
     "_RequiredListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 _OptionalListTagsForResourceRequestRequestTypeDef = TypedDict(
@@ -328,112 +430,109 @@
 class ListTagsForResourceRequestRequestTypeDef(
     _RequiredListTagsForResourceRequestRequestTypeDef,
     _OptionalListTagsForResourceRequestRequestTypeDef,
 ):
     pass
 
 
+PaginatorConfigTypeDef = TypedDict(
+    "PaginatorConfigTypeDef",
+    {
+        "MaxItems": int,
+        "PageSize": int,
+        "StartingToken": str,
+    },
+    total=False,
+)
+
 PartitionKeyTypeDef = TypedDict(
     "PartitionKeyTypeDef",
     {
         "name": str,
     },
 )
 
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
+RestoreTableResponseTypeDef = TypedDict(
+    "RestoreTableResponseTypeDef",
+    {
+        "restoredTableARN": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StaticColumnTypeDef = TypedDict(
     "StaticColumnTypeDef",
     {
         "name": str,
     },
 )
 
+UpdateTableResponseTypeDef = TypedDict(
+    "UpdateTableResponseTypeDef",
+    {
+        "resourceArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateKeyspaceRequestRequestTypeDef = TypedDict(
     "_RequiredCreateKeyspaceRequestRequestTypeDef",
     {
         "keyspaceName": str,
     },
 )
 _OptionalCreateKeyspaceRequestRequestTypeDef = TypedDict(
     "_OptionalCreateKeyspaceRequestRequestTypeDef",
     {
         "tags": Sequence[TagTypeDef],
+        "replicationSpecification": ReplicationSpecificationTypeDef,
     },
     total=False,
 )
 
 
 class CreateKeyspaceRequestRequestTypeDef(
     _RequiredCreateKeyspaceRequestRequestTypeDef, _OptionalCreateKeyspaceRequestRequestTypeDef
 ):
     pass
 
 
-TagResourceRequestRequestTypeDef = TypedDict(
-    "TagResourceRequestRequestTypeDef",
-    {
-        "resourceArn": str,
-        "tags": Sequence[TagTypeDef],
-    },
-)
-
-UntagResourceRequestRequestTypeDef = TypedDict(
-    "UntagResourceRequestRequestTypeDef",
-    {
-        "resourceArn": str,
-        "tags": Sequence[TagTypeDef],
-    },
-)
-
-CreateKeyspaceResponseTypeDef = TypedDict(
-    "CreateKeyspaceResponseTypeDef",
-    {
-        "resourceArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateTableResponseTypeDef = TypedDict(
-    "CreateTableResponseTypeDef",
-    {
-        "resourceArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetKeyspaceResponseTypeDef = TypedDict(
-    "GetKeyspaceResponseTypeDef",
-    {
-        "keyspaceName": str,
-        "resourceArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "nextToken": str,
         "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-RestoreTableResponseTypeDef = TypedDict(
-    "RestoreTableResponseTypeDef",
+TagResourceRequestRequestTypeDef = TypedDict(
+    "TagResourceRequestRequestTypeDef",
     {
-        "restoredTableARN": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "resourceArn": str,
+        "tags": Sequence[TagTypeDef],
     },
 )
 
-UpdateTableResponseTypeDef = TypedDict(
-    "UpdateTableResponseTypeDef",
+UntagResourceRequestRequestTypeDef = TypedDict(
+    "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "tags": Sequence[TagTypeDef],
     },
 )
 
 _RequiredRestoreTableRequestRequestTypeDef = TypedDict(
     "_RequiredRestoreTableRequestRequestTypeDef",
     {
         "sourceKeyspaceName": str,
@@ -473,14 +572,15 @@
     {
         "addColumns": Sequence[ColumnDefinitionTypeDef],
         "capacitySpecification": CapacitySpecificationTypeDef,
         "encryptionSpecification": EncryptionSpecificationTypeDef,
         "pointInTimeRecovery": PointInTimeRecoveryTypeDef,
         "ttl": TimeToLiveTypeDef,
         "defaultTimeToLive": int,
+        "clientSideTimestamps": ClientSideTimestampsTypeDef,
     },
     total=False,
 )
 
 
 class UpdateTableRequestRequestTypeDef(
     _RequiredUpdateTableRequestRequestTypeDef, _OptionalUpdateTableRequestRequestTypeDef
@@ -489,76 +589,24 @@
 
 
 ListKeyspacesResponseTypeDef = TypedDict(
     "ListKeyspacesResponseTypeDef",
     {
         "nextToken": str,
         "keyspaces": List[KeyspaceSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListKeyspacesRequestListKeyspacesPaginateTypeDef = TypedDict(
-    "ListKeyspacesRequestListKeyspacesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListTablesRequestListTablesPaginateTypeDef = TypedDict(
-    "_RequiredListTablesRequestListTablesPaginateTypeDef",
-    {
-        "keyspaceName": str,
-    },
-)
-_OptionalListTablesRequestListTablesPaginateTypeDef = TypedDict(
-    "_OptionalListTablesRequestListTablesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListTablesRequestListTablesPaginateTypeDef(
-    _RequiredListTablesRequestListTablesPaginateTypeDef,
-    _OptionalListTablesRequestListTablesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    {
-        "resourceArn": str,
-    },
-)
-_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-
-class ListTagsForResourceRequestListTagsForResourcePaginateTypeDef(
-    _RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-    _OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-):
-    pass
-
-
 ListTablesResponseTypeDef = TypedDict(
     "ListTablesResponseTypeDef",
     {
         "nextToken": str,
         "tables": List[TableSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSchemaDefinitionTypeDef = TypedDict(
     "_RequiredSchemaDefinitionTypeDef",
     {
         "allColumns": Sequence[ColumnDefinitionTypeDef],
@@ -593,14 +641,15 @@
         "comment": CommentTypeDef,
         "capacitySpecification": CapacitySpecificationTypeDef,
         "encryptionSpecification": EncryptionSpecificationTypeDef,
         "pointInTimeRecovery": PointInTimeRecoveryTypeDef,
         "ttl": TimeToLiveTypeDef,
         "defaultTimeToLive": int,
         "tags": Sequence[TagTypeDef],
+        "clientSideTimestamps": ClientSideTimestampsTypeDef,
     },
     total=False,
 )
 
 
 class CreateTableRequestRequestTypeDef(
     _RequiredCreateTableRequestRequestTypeDef, _OptionalCreateTableRequestRequestTypeDef
@@ -619,10 +668,11 @@
         "schemaDefinition": SchemaDefinitionTypeDef,
         "capacitySpecification": CapacitySpecificationSummaryTypeDef,
         "encryptionSpecification": EncryptionSpecificationTypeDef,
         "pointInTimeRecovery": PointInTimeRecoverySummaryTypeDef,
         "ttl": TimeToLiveTypeDef,
         "defaultTimeToLive": int,
         "comment": CommentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "clientSideTimestamps": ClientSideTimestampsTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-keyspaces-2.5.0.post1/types_aiobotocore_keyspaces/type_defs.pyi` & `types-aiobotocore-keyspaces-2.5.1/types_aiobotocore_keyspaces/type_defs.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -17,64 +17,67 @@
 
 from .literals import (
     EncryptionTypeType,
     PointInTimeRecoveryStatusType,
     SortOrderType,
     TableStatusType,
     ThroughputModeType,
+    rsType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "CapacitySpecificationSummaryTypeDef",
     "CapacitySpecificationTypeDef",
+    "ClientSideTimestampsTypeDef",
     "ClusteringKeyTypeDef",
     "ColumnDefinitionTypeDef",
     "CommentTypeDef",
+    "ReplicationSpecificationTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateKeyspaceResponseTypeDef",
     "EncryptionSpecificationTypeDef",
     "PointInTimeRecoveryTypeDef",
     "TimeToLiveTypeDef",
+    "CreateTableResponseTypeDef",
     "DeleteKeyspaceRequestRequestTypeDef",
     "DeleteTableRequestRequestTypeDef",
     "GetKeyspaceRequestRequestTypeDef",
+    "GetKeyspaceResponseTypeDef",
     "GetTableRequestRequestTypeDef",
     "PointInTimeRecoverySummaryTypeDef",
     "KeyspaceSummaryTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListKeyspacesRequestListKeyspacesPaginateTypeDef",
     "ListKeyspacesRequestRequestTypeDef",
+    "ListTablesRequestListTablesPaginateTypeDef",
     "ListTablesRequestRequestTypeDef",
     "TableSummaryTypeDef",
+    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "PartitionKeyTypeDef",
+    "ResponseMetadataTypeDef",
+    "RestoreTableResponseTypeDef",
     "StaticColumnTypeDef",
+    "UpdateTableResponseTypeDef",
     "CreateKeyspaceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
-    "CreateKeyspaceResponseTypeDef",
-    "CreateTableResponseTypeDef",
-    "GetKeyspaceResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "RestoreTableResponseTypeDef",
-    "UpdateTableResponseTypeDef",
     "RestoreTableRequestRequestTypeDef",
     "UpdateTableRequestRequestTypeDef",
     "ListKeyspacesResponseTypeDef",
-    "ListKeyspacesRequestListKeyspacesPaginateTypeDef",
-    "ListTablesRequestListTablesPaginateTypeDef",
-    "ListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
     "ListTablesResponseTypeDef",
     "SchemaDefinitionTypeDef",
     "CreateTableRequestRequestTypeDef",
     "GetTableResponseTypeDef",
 )
 
 _RequiredCapacitySpecificationSummaryTypeDef = TypedDict(
@@ -114,14 +117,21 @@
 )
 
 class CapacitySpecificationTypeDef(
     _RequiredCapacitySpecificationTypeDef, _OptionalCapacitySpecificationTypeDef
 ):
     pass
 
+ClientSideTimestampsTypeDef = TypedDict(
+    "ClientSideTimestampsTypeDef",
+    {
+        "status": Literal["ENABLED"],
+    },
+)
+
 ClusteringKeyTypeDef = TypedDict(
     "ClusteringKeyTypeDef",
     {
         "name": str,
         "orderBy": SortOrderType,
     },
 )
@@ -137,30 +147,46 @@
 CommentTypeDef = TypedDict(
     "CommentTypeDef",
     {
         "message": str,
     },
 )
 
+_RequiredReplicationSpecificationTypeDef = TypedDict(
+    "_RequiredReplicationSpecificationTypeDef",
+    {
+        "replicationStrategy": rsType,
+    },
+)
+_OptionalReplicationSpecificationTypeDef = TypedDict(
+    "_OptionalReplicationSpecificationTypeDef",
+    {
+        "regionList": Sequence[str],
+    },
+    total=False,
+)
+
+class ReplicationSpecificationTypeDef(
+    _RequiredReplicationSpecificationTypeDef, _OptionalReplicationSpecificationTypeDef
+):
+    pass
+
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "key": str,
         "value": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateKeyspaceResponseTypeDef = TypedDict(
+    "CreateKeyspaceResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "resourceArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredEncryptionSpecificationTypeDef = TypedDict(
     "_RequiredEncryptionSpecificationTypeDef",
     {
         "type": EncryptionTypeType,
@@ -189,14 +215,22 @@
 TimeToLiveTypeDef = TypedDict(
     "TimeToLiveTypeDef",
     {
         "status": Literal["ENABLED"],
     },
 )
 
+CreateTableResponseTypeDef = TypedDict(
+    "CreateTableResponseTypeDef",
+    {
+        "resourceArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteKeyspaceRequestRequestTypeDef = TypedDict(
     "DeleteKeyspaceRequestRequestTypeDef",
     {
         "keyspaceName": str,
     },
 )
 
@@ -211,14 +245,25 @@
 GetKeyspaceRequestRequestTypeDef = TypedDict(
     "GetKeyspaceRequestRequestTypeDef",
     {
         "keyspaceName": str,
     },
 )
 
+GetKeyspaceResponseTypeDef = TypedDict(
+    "GetKeyspaceResponseTypeDef",
+    {
+        "keyspaceName": str,
+        "resourceArn": str,
+        "replicationStrategy": rsType,
+        "replicationRegions": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetTableRequestRequestTypeDef = TypedDict(
     "GetTableRequestRequestTypeDef",
     {
         "keyspaceName": str,
         "tableName": str,
     },
 )
@@ -238,41 +283,70 @@
 )
 
 class PointInTimeRecoverySummaryTypeDef(
     _RequiredPointInTimeRecoverySummaryTypeDef, _OptionalPointInTimeRecoverySummaryTypeDef
 ):
     pass
 
-KeyspaceSummaryTypeDef = TypedDict(
-    "KeyspaceSummaryTypeDef",
+_RequiredKeyspaceSummaryTypeDef = TypedDict(
+    "_RequiredKeyspaceSummaryTypeDef",
     {
         "keyspaceName": str,
         "resourceArn": str,
+        "replicationStrategy": rsType,
+    },
+)
+_OptionalKeyspaceSummaryTypeDef = TypedDict(
+    "_OptionalKeyspaceSummaryTypeDef",
+    {
+        "replicationRegions": List[str],
     },
+    total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+class KeyspaceSummaryTypeDef(_RequiredKeyspaceSummaryTypeDef, _OptionalKeyspaceSummaryTypeDef):
+    pass
+
+ListKeyspacesRequestListKeyspacesPaginateTypeDef = TypedDict(
+    "ListKeyspacesRequestListKeyspacesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListKeyspacesRequestRequestTypeDef = TypedDict(
     "ListKeyspacesRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+_RequiredListTablesRequestListTablesPaginateTypeDef = TypedDict(
+    "_RequiredListTablesRequestListTablesPaginateTypeDef",
+    {
+        "keyspaceName": str,
+    },
+)
+_OptionalListTablesRequestListTablesPaginateTypeDef = TypedDict(
+    "_OptionalListTablesRequestListTablesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListTablesRequestListTablesPaginateTypeDef(
+    _RequiredListTablesRequestListTablesPaginateTypeDef,
+    _OptionalListTablesRequestListTablesPaginateTypeDef,
+):
+    pass
+
 _RequiredListTablesRequestRequestTypeDef = TypedDict(
     "_RequiredListTablesRequestRequestTypeDef",
     {
         "keyspaceName": str,
     },
 )
 _OptionalListTablesRequestRequestTypeDef = TypedDict(
@@ -294,14 +368,34 @@
     {
         "keyspaceName": str,
         "tableName": str,
         "resourceArn": str,
     },
 )
 
+_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
+    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    {
+        "resourceArn": str,
+    },
+)
+_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
+    "_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListTagsForResourceRequestListTagsForResourcePaginateTypeDef(
+    _RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
+    _OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
+):
+    pass
+
 _RequiredListTagsForResourceRequestRequestTypeDef = TypedDict(
     "_RequiredListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 _OptionalListTagsForResourceRequestRequestTypeDef = TypedDict(
@@ -315,110 +409,107 @@
 
 class ListTagsForResourceRequestRequestTypeDef(
     _RequiredListTagsForResourceRequestRequestTypeDef,
     _OptionalListTagsForResourceRequestRequestTypeDef,
 ):
     pass
 
-PartitionKeyTypeDef = TypedDict(
-    "PartitionKeyTypeDef",
+PaginatorConfigTypeDef = TypedDict(
+    "PaginatorConfigTypeDef",
     {
-        "name": str,
+        "MaxItems": int,
+        "PageSize": int,
+        "StartingToken": str,
     },
+    total=False,
 )
 
-StaticColumnTypeDef = TypedDict(
-    "StaticColumnTypeDef",
+PartitionKeyTypeDef = TypedDict(
+    "PartitionKeyTypeDef",
     {
         "name": str,
     },
 )
 
-_RequiredCreateKeyspaceRequestRequestTypeDef = TypedDict(
-    "_RequiredCreateKeyspaceRequestRequestTypeDef",
-    {
-        "keyspaceName": str,
-    },
-)
-_OptionalCreateKeyspaceRequestRequestTypeDef = TypedDict(
-    "_OptionalCreateKeyspaceRequestRequestTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "tags": Sequence[TagTypeDef],
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
-    total=False,
 )
 
-class CreateKeyspaceRequestRequestTypeDef(
-    _RequiredCreateKeyspaceRequestRequestTypeDef, _OptionalCreateKeyspaceRequestRequestTypeDef
-):
-    pass
-
-TagResourceRequestRequestTypeDef = TypedDict(
-    "TagResourceRequestRequestTypeDef",
+RestoreTableResponseTypeDef = TypedDict(
+    "RestoreTableResponseTypeDef",
     {
-        "resourceArn": str,
-        "tags": Sequence[TagTypeDef],
+        "restoredTableARN": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UntagResourceRequestRequestTypeDef = TypedDict(
-    "UntagResourceRequestRequestTypeDef",
+StaticColumnTypeDef = TypedDict(
+    "StaticColumnTypeDef",
     {
-        "resourceArn": str,
-        "tags": Sequence[TagTypeDef],
+        "name": str,
     },
 )
 
-CreateKeyspaceResponseTypeDef = TypedDict(
-    "CreateKeyspaceResponseTypeDef",
+UpdateTableResponseTypeDef = TypedDict(
+    "UpdateTableResponseTypeDef",
     {
         "resourceArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateTableResponseTypeDef = TypedDict(
-    "CreateTableResponseTypeDef",
+_RequiredCreateKeyspaceRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateKeyspaceRequestRequestTypeDef",
     {
-        "resourceArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "keyspaceName": str,
     },
 )
-
-GetKeyspaceResponseTypeDef = TypedDict(
-    "GetKeyspaceResponseTypeDef",
+_OptionalCreateKeyspaceRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateKeyspaceRequestRequestTypeDef",
     {
-        "keyspaceName": str,
-        "resourceArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "tags": Sequence[TagTypeDef],
+        "replicationSpecification": ReplicationSpecificationTypeDef,
     },
+    total=False,
 )
 
+class CreateKeyspaceRequestRequestTypeDef(
+    _RequiredCreateKeyspaceRequestRequestTypeDef, _OptionalCreateKeyspaceRequestRequestTypeDef
+):
+    pass
+
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "nextToken": str,
         "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-RestoreTableResponseTypeDef = TypedDict(
-    "RestoreTableResponseTypeDef",
+TagResourceRequestRequestTypeDef = TypedDict(
+    "TagResourceRequestRequestTypeDef",
     {
-        "restoredTableARN": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "resourceArn": str,
+        "tags": Sequence[TagTypeDef],
     },
 )
 
-UpdateTableResponseTypeDef = TypedDict(
-    "UpdateTableResponseTypeDef",
+UntagResourceRequestRequestTypeDef = TypedDict(
+    "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "tags": Sequence[TagTypeDef],
     },
 )
 
 _RequiredRestoreTableRequestRequestTypeDef = TypedDict(
     "_RequiredRestoreTableRequestRequestTypeDef",
     {
         "sourceKeyspaceName": str,
@@ -456,86 +547,39 @@
     {
         "addColumns": Sequence[ColumnDefinitionTypeDef],
         "capacitySpecification": CapacitySpecificationTypeDef,
         "encryptionSpecification": EncryptionSpecificationTypeDef,
         "pointInTimeRecovery": PointInTimeRecoveryTypeDef,
         "ttl": TimeToLiveTypeDef,
         "defaultTimeToLive": int,
+        "clientSideTimestamps": ClientSideTimestampsTypeDef,
     },
     total=False,
 )
 
 class UpdateTableRequestRequestTypeDef(
     _RequiredUpdateTableRequestRequestTypeDef, _OptionalUpdateTableRequestRequestTypeDef
 ):
     pass
 
 ListKeyspacesResponseTypeDef = TypedDict(
     "ListKeyspacesResponseTypeDef",
     {
         "nextToken": str,
         "keyspaces": List[KeyspaceSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListKeyspacesRequestListKeyspacesPaginateTypeDef = TypedDict(
-    "ListKeyspacesRequestListKeyspacesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListTablesRequestListTablesPaginateTypeDef = TypedDict(
-    "_RequiredListTablesRequestListTablesPaginateTypeDef",
-    {
-        "keyspaceName": str,
-    },
-)
-_OptionalListTablesRequestListTablesPaginateTypeDef = TypedDict(
-    "_OptionalListTablesRequestListTablesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListTablesRequestListTablesPaginateTypeDef(
-    _RequiredListTablesRequestListTablesPaginateTypeDef,
-    _OptionalListTablesRequestListTablesPaginateTypeDef,
-):
-    pass
-
-_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    {
-        "resourceArn": str,
-    },
-)
-_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef = TypedDict(
-    "_OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListTagsForResourceRequestListTagsForResourcePaginateTypeDef(
-    _RequiredListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-    _OptionalListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
-):
-    pass
-
 ListTablesResponseTypeDef = TypedDict(
     "ListTablesResponseTypeDef",
     {
         "nextToken": str,
         "tables": List[TableSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSchemaDefinitionTypeDef = TypedDict(
     "_RequiredSchemaDefinitionTypeDef",
     {
         "allColumns": Sequence[ColumnDefinitionTypeDef],
@@ -568,14 +612,15 @@
         "comment": CommentTypeDef,
         "capacitySpecification": CapacitySpecificationTypeDef,
         "encryptionSpecification": EncryptionSpecificationTypeDef,
         "pointInTimeRecovery": PointInTimeRecoveryTypeDef,
         "ttl": TimeToLiveTypeDef,
         "defaultTimeToLive": int,
         "tags": Sequence[TagTypeDef],
+        "clientSideTimestamps": ClientSideTimestampsTypeDef,
     },
     total=False,
 )
 
 class CreateTableRequestRequestTypeDef(
     _RequiredCreateTableRequestRequestTypeDef, _OptionalCreateTableRequestRequestTypeDef
 ):
@@ -592,10 +637,11 @@
         "schemaDefinition": SchemaDefinitionTypeDef,
         "capacitySpecification": CapacitySpecificationSummaryTypeDef,
         "encryptionSpecification": EncryptionSpecificationTypeDef,
         "pointInTimeRecovery": PointInTimeRecoverySummaryTypeDef,
         "ttl": TimeToLiveTypeDef,
         "defaultTimeToLive": int,
         "comment": CommentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "clientSideTimestamps": ClientSideTimestampsTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-keyspaces-2.5.0.post1/types_aiobotocore_keyspaces.egg-info/PKG-INFO` & `types-aiobotocore-keyspaces-2.5.1/types_aiobotocore_keyspaces.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-keyspaces
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Keyspaces 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Keyspaces 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_keyspaces/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-keyspaces"></a>
 
 # types-aiobotocore-keyspaces
 
 [![PyPI - types-aiobotocore-keyspaces](https://img.shields.io/pypi/v/types-aiobotocore-keyspaces.svg?color=blue)](https://pypi.org/project/types-aiobotocore-keyspaces)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-keyspaces.svg?color=blue)](https://pypi.org/project/types-aiobotocore-keyspaces)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_keyspaces/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-keyspaces?color=blue)](https://pypistats.org/packages/types-aiobotocore-keyspaces)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Keyspaces 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/keyspaces.html#Keyspaces)
+[aiobotocore.Keyspaces 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/keyspaces.html#Keyspaces)
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
 [types-aiobotocore-keyspaces docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_keyspaces/).
 
 See how it helps to find and fix potential bugs:
 
@@ -300,82 +300,86 @@
 ### Literals
 
 `types_aiobotocore_keyspaces.literals` module contains literals extracted from
 shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_keyspaces.literals import (
+    ClientSideTimestampsStatusType,
     EncryptionTypeType,
     ListKeyspacesPaginatorName,
     ListTablesPaginatorName,
     ListTagsForResourcePaginatorName,
     PointInTimeRecoveryStatusType,
     SortOrderType,
     TableStatusType,
     ThroughputModeType,
     TimeToLiveStatusType,
+    rsType,
     KeyspacesServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
 
 
-def check_value(value: EncryptionTypeType) -> bool:
+def check_value(value: ClientSideTimestampsStatusType) -> bool:
     ...
 ```
 
 <a id="typed-dictionaries"></a>
 
 ### Typed dictionaries
 
 `types_aiobotocore_keyspaces.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_keyspaces.type_defs import (
     CapacitySpecificationSummaryTypeDef,
     CapacitySpecificationTypeDef,
+    ClientSideTimestampsTypeDef,
     ClusteringKeyTypeDef,
     ColumnDefinitionTypeDef,
     CommentTypeDef,
+    ReplicationSpecificationTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateKeyspaceResponseTypeDef,
     EncryptionSpecificationTypeDef,
     PointInTimeRecoveryTypeDef,
     TimeToLiveTypeDef,
+    CreateTableResponseTypeDef,
     DeleteKeyspaceRequestRequestTypeDef,
     DeleteTableRequestRequestTypeDef,
     GetKeyspaceRequestRequestTypeDef,
+    GetKeyspaceResponseTypeDef,
     GetTableRequestRequestTypeDef,
     PointInTimeRecoverySummaryTypeDef,
     KeyspaceSummaryTypeDef,
-    PaginatorConfigTypeDef,
+    ListKeyspacesRequestListKeyspacesPaginateTypeDef,
     ListKeyspacesRequestRequestTypeDef,
+    ListTablesRequestListTablesPaginateTypeDef,
     ListTablesRequestRequestTypeDef,
     TableSummaryTypeDef,
+    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     PartitionKeyTypeDef,
+    ResponseMetadataTypeDef,
+    RestoreTableResponseTypeDef,
     StaticColumnTypeDef,
+    UpdateTableResponseTypeDef,
     CreateKeyspaceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
-    CreateKeyspaceResponseTypeDef,
-    CreateTableResponseTypeDef,
-    GetKeyspaceResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    RestoreTableResponseTypeDef,
-    UpdateTableResponseTypeDef,
     RestoreTableRequestRequestTypeDef,
     UpdateTableRequestRequestTypeDef,
     ListKeyspacesResponseTypeDef,
-    ListKeyspacesRequestListKeyspacesPaginateTypeDef,
-    ListTablesRequestListTablesPaginateTypeDef,
-    ListTagsForResourceRequestListTagsForResourcePaginateTypeDef,
     ListTablesResponseTypeDef,
     SchemaDefinitionTypeDef,
     CreateTableRequestRequestTypeDef,
     GetTableResponseTypeDef,
 )
 
 
@@ -386,43 +390,43 @@
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

### Comparing `types-aiobotocore-keyspaces-2.5.0.post1/types_aiobotocore_keyspaces.egg-info/SOURCES.txt` & `types-aiobotocore-keyspaces-2.5.1/types_aiobotocore_keyspaces.egg-info/SOURCES.txt`

 * *Files identical despite different names*

