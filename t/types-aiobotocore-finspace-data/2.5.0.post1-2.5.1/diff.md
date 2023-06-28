# Comparing `tmp/types-aiobotocore-finspace-data-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-finspace-data-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-finspace-data-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:37 2023, max compression
+gzip compressed data, was "types-aiobotocore-finspace-data-2.5.1.tar", last modified: Wed Jun 28 01:43:29 2023, max compression
```

## Comparing `types-aiobotocore-finspace-data-2.5.0.post1.tar` & `types-aiobotocore-finspace-data-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:37.451204 types-aiobotocore-finspace-data-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:14:32.000000 types-aiobotocore-finspace-data-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    17542 2023-03-11 12:26:37.447204 types-aiobotocore-finspace-data-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    15948 2023-03-11 12:14:32.000000 types-aiobotocore-finspace-data-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:37.451204 types-aiobotocore-finspace-data-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2165 2023-03-11 12:14:32.000000 types-aiobotocore-finspace-data-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:37.447204 types-aiobotocore-finspace-data-2.5.0.post1/types_aiobotocore_finspace_data/
--rw-r--r--   0 runner    (1001) docker     (123)     1466 2023-03-11 12:14:32.000000 types-aiobotocore-finspace-data-2.5.0.post1/types_aiobotocore_finspace_data/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1465 2023-03-11 12:14:32.000000 types-aiobotocore-finspace-data-2.5.0.post1/types_aiobotocore_finspace_data/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      965 2023-03-11 12:14:32.000000 types-aiobotocore-finspace-data-2.5.0.post1/types_aiobotocore_finspace_data/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    27152 2023-03-11 12:14:33.000000 types-aiobotocore-finspace-data-2.5.0.post1/types_aiobotocore_finspace_data/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    27107 2023-03-11 12:14:33.000000 types-aiobotocore-finspace-data-2.5.0.post1/types_aiobotocore_finspace_data/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9869 2023-03-11 12:14:33.000000 types-aiobotocore-finspace-data-2.5.0.post1/types_aiobotocore_finspace_data/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9867 2023-03-11 12:14:33.000000 types-aiobotocore-finspace-data-2.5.0.post1/types_aiobotocore_finspace_data/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     6572 2023-03-11 12:14:33.000000 types-aiobotocore-finspace-data-2.5.0.post1/types_aiobotocore_finspace_data/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     6564 2023-03-11 12:14:33.000000 types-aiobotocore-finspace-data-2.5.0.post1/types_aiobotocore_finspace_data/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:14:32.000000 types-aiobotocore-finspace-data-2.5.0.post1/types_aiobotocore_finspace_data/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    34475 2023-03-11 12:14:34.000000 types-aiobotocore-finspace-data-2.5.0.post1/types_aiobotocore_finspace_data/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    34422 2023-03-11 12:14:33.000000 types-aiobotocore-finspace-data-2.5.0.post1/types_aiobotocore_finspace_data/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:14:32.000000 types-aiobotocore-finspace-data-2.5.0.post1/types_aiobotocore_finspace_data/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:37.447204 types-aiobotocore-finspace-data-2.5.0.post1/types_aiobotocore_finspace_data.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    17542 2023-03-11 12:26:37.000000 types-aiobotocore-finspace-data-2.5.0.post1/types_aiobotocore_finspace_data.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      927 2023-03-11 12:26:37.000000 types-aiobotocore-finspace-data-2.5.0.post1/types_aiobotocore_finspace_data.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:37.000000 types-aiobotocore-finspace-data-2.5.0.post1/types_aiobotocore_finspace_data.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:37.000000 types-aiobotocore-finspace-data-2.5.0.post1/types_aiobotocore_finspace_data.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:37.000000 types-aiobotocore-finspace-data-2.5.0.post1/types_aiobotocore_finspace_data.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       32 2023-03-11 12:26:37.000000 types-aiobotocore-finspace-data-2.5.0.post1/types_aiobotocore_finspace_data.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:29.490136 types-aiobotocore-finspace-data-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:31:09.000000 types-aiobotocore-finspace-data-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    17540 2023-06-28 01:43:29.490136 types-aiobotocore-finspace-data-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    15952 2023-06-28 01:31:09.000000 types-aiobotocore-finspace-data-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:29.490136 types-aiobotocore-finspace-data-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2159 2023-06-28 01:31:09.000000 types-aiobotocore-finspace-data-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:29.490136 types-aiobotocore-finspace-data-2.5.1/types_aiobotocore_finspace_data/
+-rw-r--r--   0 runner    (1001) docker     (123)     1466 2023-06-28 01:31:09.000000 types-aiobotocore-finspace-data-2.5.1/types_aiobotocore_finspace_data/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1465 2023-06-28 01:31:09.000000 types-aiobotocore-finspace-data-2.5.1/types_aiobotocore_finspace_data/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      953 2023-06-28 01:31:09.000000 types-aiobotocore-finspace-data-2.5.1/types_aiobotocore_finspace_data/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27152 2023-06-28 01:31:10.000000 types-aiobotocore-finspace-data-2.5.1/types_aiobotocore_finspace_data/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27107 2023-06-28 01:31:09.000000 types-aiobotocore-finspace-data-2.5.1/types_aiobotocore_finspace_data/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10078 2023-06-28 01:31:10.000000 types-aiobotocore-finspace-data-2.5.1/types_aiobotocore_finspace_data/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10076 2023-06-28 01:31:10.000000 types-aiobotocore-finspace-data-2.5.1/types_aiobotocore_finspace_data/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     6462 2023-06-28 01:31:10.000000 types-aiobotocore-finspace-data-2.5.1/types_aiobotocore_finspace_data/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6455 2023-06-28 01:31:10.000000 types-aiobotocore-finspace-data-2.5.1/types_aiobotocore_finspace_data/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:31:09.000000 types-aiobotocore-finspace-data-2.5.1/types_aiobotocore_finspace_data/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    34547 2023-06-28 01:31:11.000000 types-aiobotocore-finspace-data-2.5.1/types_aiobotocore_finspace_data/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    34494 2023-06-28 01:31:11.000000 types-aiobotocore-finspace-data-2.5.1/types_aiobotocore_finspace_data/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:31:09.000000 types-aiobotocore-finspace-data-2.5.1/types_aiobotocore_finspace_data/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:29.490136 types-aiobotocore-finspace-data-2.5.1/types_aiobotocore_finspace_data.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    17540 2023-06-28 01:43:29.000000 types-aiobotocore-finspace-data-2.5.1/types_aiobotocore_finspace_data.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      927 2023-06-28 01:43:29.000000 types-aiobotocore-finspace-data-2.5.1/types_aiobotocore_finspace_data.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:29.000000 types-aiobotocore-finspace-data-2.5.1/types_aiobotocore_finspace_data.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:29.000000 types-aiobotocore-finspace-data-2.5.1/types_aiobotocore_finspace_data.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:29.000000 types-aiobotocore-finspace-data-2.5.1/types_aiobotocore_finspace_data.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       32 2023-06-28 01:43:29.000000 types-aiobotocore-finspace-data-2.5.1/types_aiobotocore_finspace_data.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-finspace-data-2.5.0.post1/LICENSE` & `types-aiobotocore-finspace-data-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-finspace-data-2.5.0.post1/PKG-INFO` & `types-aiobotocore-finspace-data-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-finspace-data
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.FinSpaceData 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.FinSpaceData 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_finspace_data/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-finspace-data"></a>
 
 # types-aiobotocore-finspace-data
 
 [![PyPI - types-aiobotocore-finspace-data](https://img.shields.io/pypi/v/types-aiobotocore-finspace-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-finspace-data)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-finspace-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-finspace-data)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_finspace_data/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-finspace-data?color=blue)](https://pypistats.org/packages/types-aiobotocore-finspace-data)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.FinSpaceData 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/finspace-data.html#FinSpaceData)
+[aiobotocore.FinSpaceData 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/finspace-data.html#FinSpaceData)
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
 [types-aiobotocore-finspace-data docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_finspace_data/).
 
 See how it helps to find and fix potential bugs:
 
@@ -345,89 +345,89 @@
 
 `types_aiobotocore_finspace_data.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_finspace_data.type_defs import (
     AssociateUserToPermissionGroupRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AssociateUserToPermissionGroupResponseTypeDef,
     AwsCredentialsTypeDef,
     ChangesetErrorInfoTypeDef,
     ColumnDefinitionTypeDef,
     CreateChangesetRequestRequestTypeDef,
+    CreateChangesetResponseTypeDef,
     DataViewDestinationTypeParamsTypeDef,
+    CreateDataViewResponseTypeDef,
     DatasetOwnerInfoTypeDef,
+    CreateDatasetResponseTypeDef,
     CreatePermissionGroupRequestRequestTypeDef,
+    CreatePermissionGroupResponseTypeDef,
     CreateUserRequestRequestTypeDef,
+    CreateUserResponseTypeDef,
     CredentialsTypeDef,
     DataViewErrorInfoTypeDef,
     DeleteDatasetRequestRequestTypeDef,
+    DeleteDatasetResponseTypeDef,
     DeletePermissionGroupRequestRequestTypeDef,
+    DeletePermissionGroupResponseTypeDef,
     DisableUserRequestRequestTypeDef,
+    DisableUserResponseTypeDef,
     DisassociateUserFromPermissionGroupRequestRequestTypeDef,
+    DisassociateUserFromPermissionGroupResponseTypeDef,
     EnableUserRequestRequestTypeDef,
+    EnableUserResponseTypeDef,
     GetChangesetRequestRequestTypeDef,
     GetDataViewRequestRequestTypeDef,
     GetDatasetRequestRequestTypeDef,
     GetExternalDataViewAccessDetailsRequestRequestTypeDef,
     S3LocationTypeDef,
     GetPermissionGroupRequestRequestTypeDef,
     PermissionGroupTypeDef,
     GetProgrammaticAccessCredentialsRequestRequestTypeDef,
     GetUserRequestRequestTypeDef,
+    GetUserResponseTypeDef,
     GetWorkingLocationRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetWorkingLocationResponseTypeDef,
+    ListChangesetsRequestListChangesetsPaginateTypeDef,
     ListChangesetsRequestRequestTypeDef,
+    ListDataViewsRequestListDataViewsPaginateTypeDef,
     ListDataViewsRequestRequestTypeDef,
+    ListDatasetsRequestListDatasetsPaginateTypeDef,
     ListDatasetsRequestRequestTypeDef,
     ListPermissionGroupsByUserRequestRequestTypeDef,
     PermissionGroupByUserTypeDef,
+    ListPermissionGroupsRequestListPermissionGroupsPaginateTypeDef,
     ListPermissionGroupsRequestRequestTypeDef,
     ListUsersByPermissionGroupRequestRequestTypeDef,
     UserByPermissionGroupTypeDef,
+    ListUsersRequestListUsersPaginateTypeDef,
     ListUsersRequestRequestTypeDef,
     UserTypeDef,
+    PaginatorConfigTypeDef,
     ResourcePermissionTypeDef,
     ResetUserPasswordRequestRequestTypeDef,
-    UpdateChangesetRequestRequestTypeDef,
-    UpdatePermissionGroupRequestRequestTypeDef,
-    UpdateUserRequestRequestTypeDef,
-    AssociateUserToPermissionGroupResponseTypeDef,
-    CreateChangesetResponseTypeDef,
-    CreateDataViewResponseTypeDef,
-    CreateDatasetResponseTypeDef,
-    CreatePermissionGroupResponseTypeDef,
-    CreateUserResponseTypeDef,
-    DeleteDatasetResponseTypeDef,
-    DeletePermissionGroupResponseTypeDef,
-    DisableUserResponseTypeDef,
-    DisassociateUserFromPermissionGroupResponseTypeDef,
-    EnableUserResponseTypeDef,
-    GetUserResponseTypeDef,
-    GetWorkingLocationResponseTypeDef,
     ResetUserPasswordResponseTypeDef,
+    ResponseMetadataTypeDef,
+    UpdateChangesetRequestRequestTypeDef,
     UpdateChangesetResponseTypeDef,
     UpdateDatasetResponseTypeDef,
+    UpdatePermissionGroupRequestRequestTypeDef,
     UpdatePermissionGroupResponseTypeDef,
+    UpdateUserRequestRequestTypeDef,
     UpdateUserResponseTypeDef,
     ChangesetSummaryTypeDef,
     GetChangesetResponseTypeDef,
     SchemaDefinitionTypeDef,
     CreateDataViewRequestRequestTypeDef,
     GetProgrammaticAccessCredentialsResponseTypeDef,
     DataViewSummaryTypeDef,
     GetDataViewResponseTypeDef,
     GetExternalDataViewAccessDetailsResponseTypeDef,
     GetPermissionGroupResponseTypeDef,
     ListPermissionGroupsResponseTypeDef,
-    ListChangesetsRequestListChangesetsPaginateTypeDef,
-    ListDataViewsRequestListDataViewsPaginateTypeDef,
-    ListDatasetsRequestListDatasetsPaginateTypeDef,
-    ListPermissionGroupsRequestListPermissionGroupsPaginateTypeDef,
-    ListUsersRequestListUsersPaginateTypeDef,
     ListPermissionGroupsByUserResponseTypeDef,
     ListUsersByPermissionGroupResponseTypeDef,
     ListUsersResponseTypeDef,
     PermissionGroupParamsTypeDef,
     ListChangesetsResponseTypeDef,
     SchemaUnionTypeDef,
     ListDataViewsResponseTypeDef,
@@ -446,43 +446,43 @@
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

### Comparing `types-aiobotocore-finspace-data-2.5.0.post1/README.md` & `types-aiobotocore-finspace-data-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-finspace-data"></a>
 
 # types-aiobotocore-finspace-data
 
 [![PyPI - types-aiobotocore-finspace-data](https://img.shields.io/pypi/v/types-aiobotocore-finspace-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-finspace-data)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-finspace-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-finspace-data)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_finspace_data/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-finspace-data?color=blue)](https://pypistats.org/packages/types-aiobotocore-finspace-data)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.FinSpaceData 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/finspace-data.html#FinSpaceData)
+[aiobotocore.FinSpaceData 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/finspace-data.html#FinSpaceData)
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
 [types-aiobotocore-finspace-data docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_finspace_data/).
 
 See how it helps to find and fix potential bugs:
 
@@ -312,89 +312,89 @@
 
 `types_aiobotocore_finspace_data.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_finspace_data.type_defs import (
     AssociateUserToPermissionGroupRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AssociateUserToPermissionGroupResponseTypeDef,
     AwsCredentialsTypeDef,
     ChangesetErrorInfoTypeDef,
     ColumnDefinitionTypeDef,
     CreateChangesetRequestRequestTypeDef,
+    CreateChangesetResponseTypeDef,
     DataViewDestinationTypeParamsTypeDef,
+    CreateDataViewResponseTypeDef,
     DatasetOwnerInfoTypeDef,
+    CreateDatasetResponseTypeDef,
     CreatePermissionGroupRequestRequestTypeDef,
+    CreatePermissionGroupResponseTypeDef,
     CreateUserRequestRequestTypeDef,
+    CreateUserResponseTypeDef,
     CredentialsTypeDef,
     DataViewErrorInfoTypeDef,
     DeleteDatasetRequestRequestTypeDef,
+    DeleteDatasetResponseTypeDef,
     DeletePermissionGroupRequestRequestTypeDef,
+    DeletePermissionGroupResponseTypeDef,
     DisableUserRequestRequestTypeDef,
+    DisableUserResponseTypeDef,
     DisassociateUserFromPermissionGroupRequestRequestTypeDef,
+    DisassociateUserFromPermissionGroupResponseTypeDef,
     EnableUserRequestRequestTypeDef,
+    EnableUserResponseTypeDef,
     GetChangesetRequestRequestTypeDef,
     GetDataViewRequestRequestTypeDef,
     GetDatasetRequestRequestTypeDef,
     GetExternalDataViewAccessDetailsRequestRequestTypeDef,
     S3LocationTypeDef,
     GetPermissionGroupRequestRequestTypeDef,
     PermissionGroupTypeDef,
     GetProgrammaticAccessCredentialsRequestRequestTypeDef,
     GetUserRequestRequestTypeDef,
+    GetUserResponseTypeDef,
     GetWorkingLocationRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetWorkingLocationResponseTypeDef,
+    ListChangesetsRequestListChangesetsPaginateTypeDef,
     ListChangesetsRequestRequestTypeDef,
+    ListDataViewsRequestListDataViewsPaginateTypeDef,
     ListDataViewsRequestRequestTypeDef,
+    ListDatasetsRequestListDatasetsPaginateTypeDef,
     ListDatasetsRequestRequestTypeDef,
     ListPermissionGroupsByUserRequestRequestTypeDef,
     PermissionGroupByUserTypeDef,
+    ListPermissionGroupsRequestListPermissionGroupsPaginateTypeDef,
     ListPermissionGroupsRequestRequestTypeDef,
     ListUsersByPermissionGroupRequestRequestTypeDef,
     UserByPermissionGroupTypeDef,
+    ListUsersRequestListUsersPaginateTypeDef,
     ListUsersRequestRequestTypeDef,
     UserTypeDef,
+    PaginatorConfigTypeDef,
     ResourcePermissionTypeDef,
     ResetUserPasswordRequestRequestTypeDef,
-    UpdateChangesetRequestRequestTypeDef,
-    UpdatePermissionGroupRequestRequestTypeDef,
-    UpdateUserRequestRequestTypeDef,
-    AssociateUserToPermissionGroupResponseTypeDef,
-    CreateChangesetResponseTypeDef,
-    CreateDataViewResponseTypeDef,
-    CreateDatasetResponseTypeDef,
-    CreatePermissionGroupResponseTypeDef,
-    CreateUserResponseTypeDef,
-    DeleteDatasetResponseTypeDef,
-    DeletePermissionGroupResponseTypeDef,
-    DisableUserResponseTypeDef,
-    DisassociateUserFromPermissionGroupResponseTypeDef,
-    EnableUserResponseTypeDef,
-    GetUserResponseTypeDef,
-    GetWorkingLocationResponseTypeDef,
     ResetUserPasswordResponseTypeDef,
+    ResponseMetadataTypeDef,
+    UpdateChangesetRequestRequestTypeDef,
     UpdateChangesetResponseTypeDef,
     UpdateDatasetResponseTypeDef,
+    UpdatePermissionGroupRequestRequestTypeDef,
     UpdatePermissionGroupResponseTypeDef,
+    UpdateUserRequestRequestTypeDef,
     UpdateUserResponseTypeDef,
     ChangesetSummaryTypeDef,
     GetChangesetResponseTypeDef,
     SchemaDefinitionTypeDef,
     CreateDataViewRequestRequestTypeDef,
     GetProgrammaticAccessCredentialsResponseTypeDef,
     DataViewSummaryTypeDef,
     GetDataViewResponseTypeDef,
     GetExternalDataViewAccessDetailsResponseTypeDef,
     GetPermissionGroupResponseTypeDef,
     ListPermissionGroupsResponseTypeDef,
-    ListChangesetsRequestListChangesetsPaginateTypeDef,
-    ListDataViewsRequestListDataViewsPaginateTypeDef,
-    ListDatasetsRequestListDatasetsPaginateTypeDef,
-    ListPermissionGroupsRequestListPermissionGroupsPaginateTypeDef,
-    ListUsersRequestListUsersPaginateTypeDef,
     ListPermissionGroupsByUserResponseTypeDef,
     ListUsersByPermissionGroupResponseTypeDef,
     ListUsersResponseTypeDef,
     PermissionGroupParamsTypeDef,
     ListChangesetsResponseTypeDef,
     SchemaUnionTypeDef,
     ListDataViewsResponseTypeDef,
@@ -413,43 +413,43 @@
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

### Comparing `types-aiobotocore-finspace-data-2.5.0.post1/setup.py` & `types-aiobotocore-finspace-data-2.5.1/setup.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-finspace-data.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-finspace-data",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_finspace_data"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.FinSpaceData 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.FinSpaceData 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_finspace_data/"
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

### Comparing `types-aiobotocore-finspace-data-2.5.0.post1/types_aiobotocore_finspace_data/__init__.py` & `types-aiobotocore-finspace-data-2.5.1/types_aiobotocore_finspace_data/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-finspace-data-2.5.0.post1/types_aiobotocore_finspace_data/__init__.pyi` & `types-aiobotocore-finspace-data-2.5.1/types_aiobotocore_finspace_data/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-finspace-data-2.5.0.post1/types_aiobotocore_finspace_data/__main__.py` & `types-aiobotocore-finspace-data-2.5.1/types_aiobotocore_finspace_data/__main__.py`

 * *Files 13% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.FinSpaceData 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.FinSpaceData 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_finspace_data//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/finspace-data.html#FinSpaceData\nOther"
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

### Comparing `types-aiobotocore-finspace-data-2.5.0.post1/types_aiobotocore_finspace_data/client.py` & `types-aiobotocore-finspace-data-2.5.1/types_aiobotocore_finspace_data/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-finspace-data-2.5.0.post1/types_aiobotocore_finspace_data/client.pyi` & `types-aiobotocore-finspace-data-2.5.1/types_aiobotocore_finspace_data/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-finspace-data-2.5.0.post1/types_aiobotocore_finspace_data/literals.py` & `types-aiobotocore-finspace-data-2.5.1/types_aiobotocore_finspace_data/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -166,14 +166,15 @@
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
@@ -252,14 +253,15 @@
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
@@ -270,14 +272,15 @@
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
@@ -313,14 +316,15 @@
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
@@ -339,16 +343,19 @@
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
@@ -432,15 +439,17 @@
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

### Comparing `types-aiobotocore-finspace-data-2.5.0.post1/types_aiobotocore_finspace_data/literals.pyi` & `types-aiobotocore-finspace-data-2.5.1/types_aiobotocore_finspace_data/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -164,14 +164,15 @@
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
@@ -250,14 +251,15 @@
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
@@ -268,14 +270,15 @@
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
@@ -311,14 +314,15 @@
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
@@ -337,16 +341,19 @@
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
@@ -430,15 +437,17 @@
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

### Comparing `types-aiobotocore-finspace-data-2.5.0.post1/types_aiobotocore_finspace_data/paginator.py` & `types-aiobotocore-finspace-data-2.5.1/types_aiobotocore_finspace_data/paginator.py`

 * *Files 4% similar despite different names*

```diff
@@ -24,35 +24,28 @@
         list_changesets_paginator: ListChangesetsPaginator = client.get_paginator("list_changesets")
         list_data_views_paginator: ListDataViewsPaginator = client.get_paginator("list_data_views")
         list_datasets_paginator: ListDatasetsPaginator = client.get_paginator("list_datasets")
         list_permission_groups_paginator: ListPermissionGroupsPaginator = client.get_paginator("list_permission_groups")
         list_users_paginator: ListUsersPaginator = client.get_paginator("list_users")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListChangesetsResponseTypeDef,
     ListDatasetsResponseTypeDef,
     ListDataViewsResponseTypeDef,
     ListPermissionGroupsResponseTypeDef,
     ListUsersResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListChangesetsPaginator",
     "ListDataViewsPaginator",
     "ListDatasetsPaginator",
     "ListPermissionGroupsPaginator",
     "ListUsersPaginator",
 )
@@ -71,73 +64,73 @@
 class ListChangesetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/finspace-data.html#FinSpaceData.Paginator.ListChangesets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_finspace_data/paginators/#listchangesetspaginator)
     """
 
     def paginate(
-        self, *, datasetId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, datasetId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListChangesetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/finspace-data.html#FinSpaceData.Paginator.ListChangesets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_finspace_data/paginators/#listchangesetspaginator)
         """
 
 
 class ListDataViewsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/finspace-data.html#FinSpaceData.Paginator.ListDataViews)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_finspace_data/paginators/#listdataviewspaginator)
     """
 
     def paginate(
-        self, *, datasetId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, datasetId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDataViewsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/finspace-data.html#FinSpaceData.Paginator.ListDataViews.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_finspace_data/paginators/#listdataviewspaginator)
         """
 
 
 class ListDatasetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/finspace-data.html#FinSpaceData.Paginator.ListDatasets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_finspace_data/paginators/#listdatasetspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDatasetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/finspace-data.html#FinSpaceData.Paginator.ListDatasets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_finspace_data/paginators/#listdatasetspaginator)
         """
 
 
 class ListPermissionGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/finspace-data.html#FinSpaceData.Paginator.ListPermissionGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_finspace_data/paginators/#listpermissiongroupspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPermissionGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/finspace-data.html#FinSpaceData.Paginator.ListPermissionGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_finspace_data/paginators/#listpermissiongroupspaginator)
         """
 
 
 class ListUsersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/finspace-data.html#FinSpaceData.Paginator.ListUsers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_finspace_data/paginators/#listuserspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListUsersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/finspace-data.html#FinSpaceData.Paginator.ListUsers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_finspace_data/paginators/#listuserspaginator)
         """
```

### Comparing `types-aiobotocore-finspace-data-2.5.0.post1/types_aiobotocore_finspace_data/paginator.pyi` & `types-aiobotocore-finspace-data-2.5.1/types_aiobotocore_finspace_data/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -24,34 +24,28 @@
         list_changesets_paginator: ListChangesetsPaginator = client.get_paginator("list_changesets")
         list_data_views_paginator: ListDataViewsPaginator = client.get_paginator("list_data_views")
         list_datasets_paginator: ListDatasetsPaginator = client.get_paginator("list_datasets")
         list_permission_groups_paginator: ListPermissionGroupsPaginator = client.get_paginator("list_permission_groups")
         list_users_paginator: ListUsersPaginator = client.get_paginator("list_users")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListChangesetsResponseTypeDef,
     ListDatasetsResponseTypeDef,
     ListDataViewsResponseTypeDef,
     ListPermissionGroupsResponseTypeDef,
     ListUsersResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListChangesetsPaginator",
     "ListDataViewsPaginator",
     "ListDatasetsPaginator",
     "ListPermissionGroupsPaginator",
     "ListUsersPaginator",
 )
@@ -67,69 +61,69 @@
 class ListChangesetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/finspace-data.html#FinSpaceData.Paginator.ListChangesets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_finspace_data/paginators/#listchangesetspaginator)
     """
 
     def paginate(
-        self, *, datasetId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, datasetId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListChangesetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/finspace-data.html#FinSpaceData.Paginator.ListChangesets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_finspace_data/paginators/#listchangesetspaginator)
         """
 
 class ListDataViewsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/finspace-data.html#FinSpaceData.Paginator.ListDataViews)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_finspace_data/paginators/#listdataviewspaginator)
     """
 
     def paginate(
-        self, *, datasetId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, datasetId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDataViewsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/finspace-data.html#FinSpaceData.Paginator.ListDataViews.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_finspace_data/paginators/#listdataviewspaginator)
         """
 
 class ListDatasetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/finspace-data.html#FinSpaceData.Paginator.ListDatasets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_finspace_data/paginators/#listdatasetspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDatasetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/finspace-data.html#FinSpaceData.Paginator.ListDatasets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_finspace_data/paginators/#listdatasetspaginator)
         """
 
 class ListPermissionGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/finspace-data.html#FinSpaceData.Paginator.ListPermissionGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_finspace_data/paginators/#listpermissiongroupspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPermissionGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/finspace-data.html#FinSpaceData.Paginator.ListPermissionGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_finspace_data/paginators/#listpermissiongroupspaginator)
         """
 
 class ListUsersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/finspace-data.html#FinSpaceData.Paginator.ListUsers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_finspace_data/paginators/#listuserspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListUsersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/finspace-data.html#FinSpaceData.Paginator.ListUsers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_finspace_data/paginators/#listuserspaginator)
         """
```

### Comparing `types-aiobotocore-finspace-data-2.5.0.post1/types_aiobotocore_finspace_data/type_defs.py` & `types-aiobotocore-finspace-data-2.5.1/types_aiobotocore_finspace_data/type_defs.py`

 * *Files 3% similar despite different names*

```diff
@@ -35,89 +35,89 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AssociateUserToPermissionGroupRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "AssociateUserToPermissionGroupResponseTypeDef",
     "AwsCredentialsTypeDef",
     "ChangesetErrorInfoTypeDef",
     "ColumnDefinitionTypeDef",
     "CreateChangesetRequestRequestTypeDef",
+    "CreateChangesetResponseTypeDef",
     "DataViewDestinationTypeParamsTypeDef",
+    "CreateDataViewResponseTypeDef",
     "DatasetOwnerInfoTypeDef",
+    "CreateDatasetResponseTypeDef",
     "CreatePermissionGroupRequestRequestTypeDef",
+    "CreatePermissionGroupResponseTypeDef",
     "CreateUserRequestRequestTypeDef",
+    "CreateUserResponseTypeDef",
     "CredentialsTypeDef",
     "DataViewErrorInfoTypeDef",
     "DeleteDatasetRequestRequestTypeDef",
+    "DeleteDatasetResponseTypeDef",
     "DeletePermissionGroupRequestRequestTypeDef",
+    "DeletePermissionGroupResponseTypeDef",
     "DisableUserRequestRequestTypeDef",
+    "DisableUserResponseTypeDef",
     "DisassociateUserFromPermissionGroupRequestRequestTypeDef",
+    "DisassociateUserFromPermissionGroupResponseTypeDef",
     "EnableUserRequestRequestTypeDef",
+    "EnableUserResponseTypeDef",
     "GetChangesetRequestRequestTypeDef",
     "GetDataViewRequestRequestTypeDef",
     "GetDatasetRequestRequestTypeDef",
     "GetExternalDataViewAccessDetailsRequestRequestTypeDef",
     "S3LocationTypeDef",
     "GetPermissionGroupRequestRequestTypeDef",
     "PermissionGroupTypeDef",
     "GetProgrammaticAccessCredentialsRequestRequestTypeDef",
     "GetUserRequestRequestTypeDef",
+    "GetUserResponseTypeDef",
     "GetWorkingLocationRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetWorkingLocationResponseTypeDef",
+    "ListChangesetsRequestListChangesetsPaginateTypeDef",
     "ListChangesetsRequestRequestTypeDef",
+    "ListDataViewsRequestListDataViewsPaginateTypeDef",
     "ListDataViewsRequestRequestTypeDef",
+    "ListDatasetsRequestListDatasetsPaginateTypeDef",
     "ListDatasetsRequestRequestTypeDef",
     "ListPermissionGroupsByUserRequestRequestTypeDef",
     "PermissionGroupByUserTypeDef",
+    "ListPermissionGroupsRequestListPermissionGroupsPaginateTypeDef",
     "ListPermissionGroupsRequestRequestTypeDef",
     "ListUsersByPermissionGroupRequestRequestTypeDef",
     "UserByPermissionGroupTypeDef",
+    "ListUsersRequestListUsersPaginateTypeDef",
     "ListUsersRequestRequestTypeDef",
     "UserTypeDef",
+    "PaginatorConfigTypeDef",
     "ResourcePermissionTypeDef",
     "ResetUserPasswordRequestRequestTypeDef",
-    "UpdateChangesetRequestRequestTypeDef",
-    "UpdatePermissionGroupRequestRequestTypeDef",
-    "UpdateUserRequestRequestTypeDef",
-    "AssociateUserToPermissionGroupResponseTypeDef",
-    "CreateChangesetResponseTypeDef",
-    "CreateDataViewResponseTypeDef",
-    "CreateDatasetResponseTypeDef",
-    "CreatePermissionGroupResponseTypeDef",
-    "CreateUserResponseTypeDef",
-    "DeleteDatasetResponseTypeDef",
-    "DeletePermissionGroupResponseTypeDef",
-    "DisableUserResponseTypeDef",
-    "DisassociateUserFromPermissionGroupResponseTypeDef",
-    "EnableUserResponseTypeDef",
-    "GetUserResponseTypeDef",
-    "GetWorkingLocationResponseTypeDef",
     "ResetUserPasswordResponseTypeDef",
+    "ResponseMetadataTypeDef",
+    "UpdateChangesetRequestRequestTypeDef",
     "UpdateChangesetResponseTypeDef",
     "UpdateDatasetResponseTypeDef",
+    "UpdatePermissionGroupRequestRequestTypeDef",
     "UpdatePermissionGroupResponseTypeDef",
+    "UpdateUserRequestRequestTypeDef",
     "UpdateUserResponseTypeDef",
     "ChangesetSummaryTypeDef",
     "GetChangesetResponseTypeDef",
     "SchemaDefinitionTypeDef",
     "CreateDataViewRequestRequestTypeDef",
     "GetProgrammaticAccessCredentialsResponseTypeDef",
     "DataViewSummaryTypeDef",
     "GetDataViewResponseTypeDef",
     "GetExternalDataViewAccessDetailsResponseTypeDef",
     "GetPermissionGroupResponseTypeDef",
     "ListPermissionGroupsResponseTypeDef",
-    "ListChangesetsRequestListChangesetsPaginateTypeDef",
-    "ListDataViewsRequestListDataViewsPaginateTypeDef",
-    "ListDatasetsRequestListDatasetsPaginateTypeDef",
-    "ListPermissionGroupsRequestListPermissionGroupsPaginateTypeDef",
-    "ListUsersRequestListUsersPaginateTypeDef",
     "ListPermissionGroupsByUserResponseTypeDef",
     "ListUsersByPermissionGroupResponseTypeDef",
     "ListUsersResponseTypeDef",
     "PermissionGroupParamsTypeDef",
     "ListChangesetsResponseTypeDef",
     "SchemaUnionTypeDef",
     "ListDataViewsResponseTypeDef",
@@ -147,22 +147,19 @@
 class AssociateUserToPermissionGroupRequestRequestTypeDef(
     _RequiredAssociateUserToPermissionGroupRequestRequestTypeDef,
     _OptionalAssociateUserToPermissionGroupRequestRequestTypeDef,
 ):
     pass
 
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AssociateUserToPermissionGroupResponseTypeDef = TypedDict(
+    "AssociateUserToPermissionGroupResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "statusCode": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AwsCredentialsTypeDef = TypedDict(
     "AwsCredentialsTypeDef",
     {
         "accessKeyId": str,
@@ -212,14 +209,23 @@
 
 class CreateChangesetRequestRequestTypeDef(
     _RequiredCreateChangesetRequestRequestTypeDef, _OptionalCreateChangesetRequestRequestTypeDef
 ):
     pass
 
 
+CreateChangesetResponseTypeDef = TypedDict(
+    "CreateChangesetResponseTypeDef",
+    {
+        "datasetId": str,
+        "changesetId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDataViewDestinationTypeParamsTypeDef = TypedDict(
     "_RequiredDataViewDestinationTypeParamsTypeDef",
     {
         "destinationType": str,
     },
 )
 _OptionalDataViewDestinationTypeParamsTypeDef = TypedDict(
@@ -234,24 +240,41 @@
 
 class DataViewDestinationTypeParamsTypeDef(
     _RequiredDataViewDestinationTypeParamsTypeDef, _OptionalDataViewDestinationTypeParamsTypeDef
 ):
     pass
 
 
+CreateDataViewResponseTypeDef = TypedDict(
+    "CreateDataViewResponseTypeDef",
+    {
+        "datasetId": str,
+        "dataViewId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DatasetOwnerInfoTypeDef = TypedDict(
     "DatasetOwnerInfoTypeDef",
     {
         "name": str,
         "phoneNumber": str,
         "email": str,
     },
     total=False,
 )
 
+CreateDatasetResponseTypeDef = TypedDict(
+    "CreateDatasetResponseTypeDef",
+    {
+        "datasetId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreatePermissionGroupRequestRequestTypeDef = TypedDict(
     "_RequiredCreatePermissionGroupRequestRequestTypeDef",
     {
         "name": str,
         "applicationPermissions": Sequence[ApplicationPermissionType],
     },
 )
@@ -268,14 +291,22 @@
 class CreatePermissionGroupRequestRequestTypeDef(
     _RequiredCreatePermissionGroupRequestRequestTypeDef,
     _OptionalCreatePermissionGroupRequestRequestTypeDef,
 ):
     pass
 
 
+CreatePermissionGroupResponseTypeDef = TypedDict(
+    "CreatePermissionGroupResponseTypeDef",
+    {
+        "permissionGroupId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateUserRequestRequestTypeDef = TypedDict(
     "_RequiredCreateUserRequestRequestTypeDef",
     {
         "emailAddress": str,
         "type": UserTypeType,
     },
 )
@@ -294,14 +325,22 @@
 
 class CreateUserRequestRequestTypeDef(
     _RequiredCreateUserRequestRequestTypeDef, _OptionalCreateUserRequestRequestTypeDef
 ):
     pass
 
 
+CreateUserResponseTypeDef = TypedDict(
+    "CreateUserResponseTypeDef",
+    {
+        "userId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CredentialsTypeDef = TypedDict(
     "CredentialsTypeDef",
     {
         "accessKeyId": str,
         "secretAccessKey": str,
         "sessionToken": str,
     },
@@ -334,14 +373,22 @@
 
 class DeleteDatasetRequestRequestTypeDef(
     _RequiredDeleteDatasetRequestRequestTypeDef, _OptionalDeleteDatasetRequestRequestTypeDef
 ):
     pass
 
 
+DeleteDatasetResponseTypeDef = TypedDict(
+    "DeleteDatasetResponseTypeDef",
+    {
+        "datasetId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeletePermissionGroupRequestRequestTypeDef = TypedDict(
     "_RequiredDeletePermissionGroupRequestRequestTypeDef",
     {
         "permissionGroupId": str,
     },
 )
 _OptionalDeletePermissionGroupRequestRequestTypeDef = TypedDict(
@@ -356,14 +403,22 @@
 class DeletePermissionGroupRequestRequestTypeDef(
     _RequiredDeletePermissionGroupRequestRequestTypeDef,
     _OptionalDeletePermissionGroupRequestRequestTypeDef,
 ):
     pass
 
 
+DeletePermissionGroupResponseTypeDef = TypedDict(
+    "DeletePermissionGroupResponseTypeDef",
+    {
+        "permissionGroupId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDisableUserRequestRequestTypeDef = TypedDict(
     "_RequiredDisableUserRequestRequestTypeDef",
     {
         "userId": str,
     },
 )
 _OptionalDisableUserRequestRequestTypeDef = TypedDict(
@@ -377,14 +432,22 @@
 
 class DisableUserRequestRequestTypeDef(
     _RequiredDisableUserRequestRequestTypeDef, _OptionalDisableUserRequestRequestTypeDef
 ):
     pass
 
 
+DisableUserResponseTypeDef = TypedDict(
+    "DisableUserResponseTypeDef",
+    {
+        "userId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDisassociateUserFromPermissionGroupRequestRequestTypeDef = TypedDict(
     "_RequiredDisassociateUserFromPermissionGroupRequestRequestTypeDef",
     {
         "permissionGroupId": str,
         "userId": str,
     },
 )
@@ -400,14 +463,22 @@
 class DisassociateUserFromPermissionGroupRequestRequestTypeDef(
     _RequiredDisassociateUserFromPermissionGroupRequestRequestTypeDef,
     _OptionalDisassociateUserFromPermissionGroupRequestRequestTypeDef,
 ):
     pass
 
 
+DisassociateUserFromPermissionGroupResponseTypeDef = TypedDict(
+    "DisassociateUserFromPermissionGroupResponseTypeDef",
+    {
+        "statusCode": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredEnableUserRequestRequestTypeDef = TypedDict(
     "_RequiredEnableUserRequestRequestTypeDef",
     {
         "userId": str,
     },
 )
 _OptionalEnableUserRequestRequestTypeDef = TypedDict(
@@ -421,14 +492,22 @@
 
 class EnableUserRequestRequestTypeDef(
     _RequiredEnableUserRequestRequestTypeDef, _OptionalEnableUserRequestRequestTypeDef
 ):
     pass
 
 
+EnableUserResponseTypeDef = TypedDict(
+    "EnableUserResponseTypeDef",
+    {
+        "userId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetChangesetRequestRequestTypeDef = TypedDict(
     "GetChangesetRequestRequestTypeDef",
     {
         "datasetId": str,
         "changesetId": str,
     },
 )
@@ -510,32 +589,74 @@
 GetUserRequestRequestTypeDef = TypedDict(
     "GetUserRequestRequestTypeDef",
     {
         "userId": str,
     },
 )
 
+GetUserResponseTypeDef = TypedDict(
+    "GetUserResponseTypeDef",
+    {
+        "userId": str,
+        "status": UserStatusType,
+        "firstName": str,
+        "lastName": str,
+        "emailAddress": str,
+        "type": UserTypeType,
+        "apiAccess": ApiAccessType,
+        "apiAccessPrincipalArn": str,
+        "createTime": int,
+        "lastEnabledTime": int,
+        "lastDisabledTime": int,
+        "lastModifiedTime": int,
+        "lastLoginTime": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetWorkingLocationRequestRequestTypeDef = TypedDict(
     "GetWorkingLocationRequestRequestTypeDef",
     {
         "locationType": locationTypeType,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetWorkingLocationResponseTypeDef = TypedDict(
+    "GetWorkingLocationResponseTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "s3Uri": str,
+        "s3Path": str,
+        "s3Bucket": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListChangesetsRequestListChangesetsPaginateTypeDef = TypedDict(
+    "_RequiredListChangesetsRequestListChangesetsPaginateTypeDef",
+    {
+        "datasetId": str,
+    },
+)
+_OptionalListChangesetsRequestListChangesetsPaginateTypeDef = TypedDict(
+    "_OptionalListChangesetsRequestListChangesetsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListChangesetsRequestListChangesetsPaginateTypeDef(
+    _RequiredListChangesetsRequestListChangesetsPaginateTypeDef,
+    _OptionalListChangesetsRequestListChangesetsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListChangesetsRequestRequestTypeDef = TypedDict(
     "_RequiredListChangesetsRequestRequestTypeDef",
     {
         "datasetId": str,
     },
 )
 _OptionalListChangesetsRequestRequestTypeDef = TypedDict(
@@ -550,14 +671,36 @@
 
 class ListChangesetsRequestRequestTypeDef(
     _RequiredListChangesetsRequestRequestTypeDef, _OptionalListChangesetsRequestRequestTypeDef
 ):
     pass
 
 
+_RequiredListDataViewsRequestListDataViewsPaginateTypeDef = TypedDict(
+    "_RequiredListDataViewsRequestListDataViewsPaginateTypeDef",
+    {
+        "datasetId": str,
+    },
+)
+_OptionalListDataViewsRequestListDataViewsPaginateTypeDef = TypedDict(
+    "_OptionalListDataViewsRequestListDataViewsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListDataViewsRequestListDataViewsPaginateTypeDef(
+    _RequiredListDataViewsRequestListDataViewsPaginateTypeDef,
+    _OptionalListDataViewsRequestListDataViewsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListDataViewsRequestRequestTypeDef = TypedDict(
     "_RequiredListDataViewsRequestRequestTypeDef",
     {
         "datasetId": str,
     },
 )
 _OptionalListDataViewsRequestRequestTypeDef = TypedDict(
@@ -572,14 +715,22 @@
 
 class ListDataViewsRequestRequestTypeDef(
     _RequiredListDataViewsRequestRequestTypeDef, _OptionalListDataViewsRequestRequestTypeDef
 ):
     pass
 
 
+ListDatasetsRequestListDatasetsPaginateTypeDef = TypedDict(
+    "ListDatasetsRequestListDatasetsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDatasetsRequestRequestTypeDef = TypedDict(
     "ListDatasetsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
@@ -614,14 +765,22 @@
         "permissionGroupId": str,
         "name": str,
         "membershipStatus": PermissionGroupMembershipStatusType,
     },
     total=False,
 )
 
+ListPermissionGroupsRequestListPermissionGroupsPaginateTypeDef = TypedDict(
+    "ListPermissionGroupsRequestListPermissionGroupsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 _RequiredListPermissionGroupsRequestRequestTypeDef = TypedDict(
     "_RequiredListPermissionGroupsRequestRequestTypeDef",
     {
         "maxResults": int,
     },
 )
 _OptionalListPermissionGroupsRequestRequestTypeDef = TypedDict(
@@ -675,14 +834,22 @@
         "apiAccess": ApiAccessType,
         "apiAccessPrincipalArn": str,
         "membershipStatus": PermissionGroupMembershipStatusType,
     },
     total=False,
 )
 
+ListUsersRequestListUsersPaginateTypeDef = TypedDict(
+    "ListUsersRequestListUsersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 _RequiredListUsersRequestRequestTypeDef = TypedDict(
     "_RequiredListUsersRequestRequestTypeDef",
     {
         "maxResults": int,
     },
 )
 _OptionalListUsersRequestRequestTypeDef = TypedDict(
@@ -716,14 +883,24 @@
         "lastDisabledTime": int,
         "lastModifiedTime": int,
         "lastLoginTime": int,
     },
     total=False,
 )
 
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
 ResourcePermissionTypeDef = TypedDict(
     "ResourcePermissionTypeDef",
     {
         "permission": str,
     },
     total=False,
 )
@@ -745,14 +922,34 @@
 
 class ResetUserPasswordRequestRequestTypeDef(
     _RequiredResetUserPasswordRequestRequestTypeDef, _OptionalResetUserPasswordRequestRequestTypeDef
 ):
     pass
 
 
+ResetUserPasswordResponseTypeDef = TypedDict(
+    "ResetUserPasswordResponseTypeDef",
+    {
+        "userId": str,
+        "temporaryPassword": str,
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
 _RequiredUpdateChangesetRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateChangesetRequestRequestTypeDef",
     {
         "datasetId": str,
         "changesetId": str,
         "sourceParams": Mapping[str, str],
         "formatParams": Mapping[str, str],
@@ -769,14 +966,31 @@
 
 class UpdateChangesetRequestRequestTypeDef(
     _RequiredUpdateChangesetRequestRequestTypeDef, _OptionalUpdateChangesetRequestRequestTypeDef
 ):
     pass
 
 
+UpdateChangesetResponseTypeDef = TypedDict(
+    "UpdateChangesetResponseTypeDef",
+    {
+        "changesetId": str,
+        "datasetId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateDatasetResponseTypeDef = TypedDict(
+    "UpdateDatasetResponseTypeDef",
+    {
+        "datasetId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdatePermissionGroupRequestRequestTypeDef = TypedDict(
     "_RequiredUpdatePermissionGroupRequestRequestTypeDef",
     {
         "permissionGroupId": str,
     },
 )
 _OptionalUpdatePermissionGroupRequestRequestTypeDef = TypedDict(
@@ -794,14 +1008,22 @@
 class UpdatePermissionGroupRequestRequestTypeDef(
     _RequiredUpdatePermissionGroupRequestRequestTypeDef,
     _OptionalUpdatePermissionGroupRequestRequestTypeDef,
 ):
     pass
 
 
+UpdatePermissionGroupResponseTypeDef = TypedDict(
+    "UpdatePermissionGroupResponseTypeDef",
+    {
+        "permissionGroupId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateUserRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateUserRequestRequestTypeDef",
     {
         "userId": str,
     },
 )
 _OptionalUpdateUserRequestRequestTypeDef = TypedDict(
@@ -820,173 +1042,19 @@
 
 class UpdateUserRequestRequestTypeDef(
     _RequiredUpdateUserRequestRequestTypeDef, _OptionalUpdateUserRequestRequestTypeDef
 ):
     pass
 
 
-AssociateUserToPermissionGroupResponseTypeDef = TypedDict(
-    "AssociateUserToPermissionGroupResponseTypeDef",
-    {
-        "statusCode": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateChangesetResponseTypeDef = TypedDict(
-    "CreateChangesetResponseTypeDef",
-    {
-        "datasetId": str,
-        "changesetId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDataViewResponseTypeDef = TypedDict(
-    "CreateDataViewResponseTypeDef",
-    {
-        "datasetId": str,
-        "dataViewId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDatasetResponseTypeDef = TypedDict(
-    "CreateDatasetResponseTypeDef",
-    {
-        "datasetId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreatePermissionGroupResponseTypeDef = TypedDict(
-    "CreatePermissionGroupResponseTypeDef",
-    {
-        "permissionGroupId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateUserResponseTypeDef = TypedDict(
-    "CreateUserResponseTypeDef",
-    {
-        "userId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteDatasetResponseTypeDef = TypedDict(
-    "DeleteDatasetResponseTypeDef",
-    {
-        "datasetId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeletePermissionGroupResponseTypeDef = TypedDict(
-    "DeletePermissionGroupResponseTypeDef",
-    {
-        "permissionGroupId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DisableUserResponseTypeDef = TypedDict(
-    "DisableUserResponseTypeDef",
-    {
-        "userId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DisassociateUserFromPermissionGroupResponseTypeDef = TypedDict(
-    "DisassociateUserFromPermissionGroupResponseTypeDef",
-    {
-        "statusCode": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-EnableUserResponseTypeDef = TypedDict(
-    "EnableUserResponseTypeDef",
-    {
-        "userId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetUserResponseTypeDef = TypedDict(
-    "GetUserResponseTypeDef",
-    {
-        "userId": str,
-        "status": UserStatusType,
-        "firstName": str,
-        "lastName": str,
-        "emailAddress": str,
-        "type": UserTypeType,
-        "apiAccess": ApiAccessType,
-        "apiAccessPrincipalArn": str,
-        "createTime": int,
-        "lastEnabledTime": int,
-        "lastDisabledTime": int,
-        "lastModifiedTime": int,
-        "lastLoginTime": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetWorkingLocationResponseTypeDef = TypedDict(
-    "GetWorkingLocationResponseTypeDef",
-    {
-        "s3Uri": str,
-        "s3Path": str,
-        "s3Bucket": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ResetUserPasswordResponseTypeDef = TypedDict(
-    "ResetUserPasswordResponseTypeDef",
-    {
-        "userId": str,
-        "temporaryPassword": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateChangesetResponseTypeDef = TypedDict(
-    "UpdateChangesetResponseTypeDef",
-    {
-        "changesetId": str,
-        "datasetId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateDatasetResponseTypeDef = TypedDict(
-    "UpdateDatasetResponseTypeDef",
-    {
-        "datasetId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdatePermissionGroupResponseTypeDef = TypedDict(
-    "UpdatePermissionGroupResponseTypeDef",
-    {
-        "permissionGroupId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 UpdateUserResponseTypeDef = TypedDict(
     "UpdateUserResponseTypeDef",
     {
         "userId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ChangesetSummaryTypeDef = TypedDict(
     "ChangesetSummaryTypeDef",
     {
         "changesetId": str,
@@ -1018,15 +1086,15 @@
         "createTime": int,
         "status": IngestionStatusType,
         "errorInfo": ChangesetErrorInfoTypeDef,
         "activeUntilTimestamp": int,
         "activeFromTimestamp": int,
         "updatesChangesetId": str,
         "updatedByChangesetId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SchemaDefinitionTypeDef = TypedDict(
     "SchemaDefinitionTypeDef",
     {
         "columns": Sequence[ColumnDefinitionTypeDef],
@@ -1062,15 +1130,15 @@
 
 
 GetProgrammaticAccessCredentialsResponseTypeDef = TypedDict(
     "GetProgrammaticAccessCredentialsResponseTypeDef",
     {
         "credentials": CredentialsTypeDef,
         "durationInMinutes": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DataViewSummaryTypeDef = TypedDict(
     "DataViewSummaryTypeDef",
     {
         "dataViewId": str,
@@ -1100,136 +1168,68 @@
         "lastModifiedTime": int,
         "createTime": int,
         "sortColumns": List[str],
         "dataViewId": str,
         "dataViewArn": str,
         "destinationTypeParams": DataViewDestinationTypeParamsTypeDef,
         "status": DataViewStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetExternalDataViewAccessDetailsResponseTypeDef = TypedDict(
     "GetExternalDataViewAccessDetailsResponseTypeDef",
     {
         "credentials": AwsCredentialsTypeDef,
         "s3Location": S3LocationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetPermissionGroupResponseTypeDef = TypedDict(
     "GetPermissionGroupResponseTypeDef",
     {
         "permissionGroup": PermissionGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPermissionGroupsResponseTypeDef = TypedDict(
     "ListPermissionGroupsResponseTypeDef",
     {
         "permissionGroups": List[PermissionGroupTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-_RequiredListChangesetsRequestListChangesetsPaginateTypeDef = TypedDict(
-    "_RequiredListChangesetsRequestListChangesetsPaginateTypeDef",
-    {
-        "datasetId": str,
-    },
-)
-_OptionalListChangesetsRequestListChangesetsPaginateTypeDef = TypedDict(
-    "_OptionalListChangesetsRequestListChangesetsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListChangesetsRequestListChangesetsPaginateTypeDef(
-    _RequiredListChangesetsRequestListChangesetsPaginateTypeDef,
-    _OptionalListChangesetsRequestListChangesetsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListDataViewsRequestListDataViewsPaginateTypeDef = TypedDict(
-    "_RequiredListDataViewsRequestListDataViewsPaginateTypeDef",
-    {
-        "datasetId": str,
-    },
-)
-_OptionalListDataViewsRequestListDataViewsPaginateTypeDef = TypedDict(
-    "_OptionalListDataViewsRequestListDataViewsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListDataViewsRequestListDataViewsPaginateTypeDef(
-    _RequiredListDataViewsRequestListDataViewsPaginateTypeDef,
-    _OptionalListDataViewsRequestListDataViewsPaginateTypeDef,
-):
-    pass
-
-
-ListDatasetsRequestListDatasetsPaginateTypeDef = TypedDict(
-    "ListDatasetsRequestListDatasetsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListPermissionGroupsRequestListPermissionGroupsPaginateTypeDef = TypedDict(
-    "ListPermissionGroupsRequestListPermissionGroupsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListUsersRequestListUsersPaginateTypeDef = TypedDict(
-    "ListUsersRequestListUsersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListPermissionGroupsByUserResponseTypeDef = TypedDict(
     "ListPermissionGroupsByUserResponseTypeDef",
     {
         "permissionGroups": List[PermissionGroupByUserTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListUsersByPermissionGroupResponseTypeDef = TypedDict(
     "ListUsersByPermissionGroupResponseTypeDef",
     {
         "users": List[UserByPermissionGroupTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListUsersResponseTypeDef = TypedDict(
     "ListUsersResponseTypeDef",
     {
         "users": List[UserTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PermissionGroupParamsTypeDef = TypedDict(
     "PermissionGroupParamsTypeDef",
     {
         "permissionGroupId": str,
@@ -1239,15 +1239,15 @@
 )
 
 ListChangesetsResponseTypeDef = TypedDict(
     "ListChangesetsResponseTypeDef",
     {
         "changesets": List[ChangesetSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SchemaUnionTypeDef = TypedDict(
     "SchemaUnionTypeDef",
     {
         "tabularSchemaConfig": SchemaDefinitionTypeDef,
@@ -1256,15 +1256,15 @@
 )
 
 ListDataViewsResponseTypeDef = TypedDict(
     "ListDataViewsResponseTypeDef",
     {
         "nextToken": str,
         "dataViews": List[DataViewSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateDatasetRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDatasetRequestRequestTypeDef",
     {
         "datasetTitle": str,
@@ -1317,15 +1317,15 @@
         "kind": DatasetKindType,
         "datasetDescription": str,
         "createTime": int,
         "lastModifiedTime": int,
         "schemaDefinition": SchemaUnionTypeDef,
         "alias": str,
         "status": DatasetStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateDatasetRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateDatasetRequestRequestTypeDef",
     {
         "datasetId": str,
@@ -1352,10 +1352,10 @@
 
 
 ListDatasetsResponseTypeDef = TypedDict(
     "ListDatasetsResponseTypeDef",
     {
         "datasets": List[DatasetTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-finspace-data-2.5.0.post1/types_aiobotocore_finspace_data/type_defs.pyi` & `types-aiobotocore-finspace-data-2.5.1/types_aiobotocore_finspace_data/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -34,89 +34,89 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AssociateUserToPermissionGroupRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "AssociateUserToPermissionGroupResponseTypeDef",
     "AwsCredentialsTypeDef",
     "ChangesetErrorInfoTypeDef",
     "ColumnDefinitionTypeDef",
     "CreateChangesetRequestRequestTypeDef",
+    "CreateChangesetResponseTypeDef",
     "DataViewDestinationTypeParamsTypeDef",
+    "CreateDataViewResponseTypeDef",
     "DatasetOwnerInfoTypeDef",
+    "CreateDatasetResponseTypeDef",
     "CreatePermissionGroupRequestRequestTypeDef",
+    "CreatePermissionGroupResponseTypeDef",
     "CreateUserRequestRequestTypeDef",
+    "CreateUserResponseTypeDef",
     "CredentialsTypeDef",
     "DataViewErrorInfoTypeDef",
     "DeleteDatasetRequestRequestTypeDef",
+    "DeleteDatasetResponseTypeDef",
     "DeletePermissionGroupRequestRequestTypeDef",
+    "DeletePermissionGroupResponseTypeDef",
     "DisableUserRequestRequestTypeDef",
+    "DisableUserResponseTypeDef",
     "DisassociateUserFromPermissionGroupRequestRequestTypeDef",
+    "DisassociateUserFromPermissionGroupResponseTypeDef",
     "EnableUserRequestRequestTypeDef",
+    "EnableUserResponseTypeDef",
     "GetChangesetRequestRequestTypeDef",
     "GetDataViewRequestRequestTypeDef",
     "GetDatasetRequestRequestTypeDef",
     "GetExternalDataViewAccessDetailsRequestRequestTypeDef",
     "S3LocationTypeDef",
     "GetPermissionGroupRequestRequestTypeDef",
     "PermissionGroupTypeDef",
     "GetProgrammaticAccessCredentialsRequestRequestTypeDef",
     "GetUserRequestRequestTypeDef",
+    "GetUserResponseTypeDef",
     "GetWorkingLocationRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetWorkingLocationResponseTypeDef",
+    "ListChangesetsRequestListChangesetsPaginateTypeDef",
     "ListChangesetsRequestRequestTypeDef",
+    "ListDataViewsRequestListDataViewsPaginateTypeDef",
     "ListDataViewsRequestRequestTypeDef",
+    "ListDatasetsRequestListDatasetsPaginateTypeDef",
     "ListDatasetsRequestRequestTypeDef",
     "ListPermissionGroupsByUserRequestRequestTypeDef",
     "PermissionGroupByUserTypeDef",
+    "ListPermissionGroupsRequestListPermissionGroupsPaginateTypeDef",
     "ListPermissionGroupsRequestRequestTypeDef",
     "ListUsersByPermissionGroupRequestRequestTypeDef",
     "UserByPermissionGroupTypeDef",
+    "ListUsersRequestListUsersPaginateTypeDef",
     "ListUsersRequestRequestTypeDef",
     "UserTypeDef",
+    "PaginatorConfigTypeDef",
     "ResourcePermissionTypeDef",
     "ResetUserPasswordRequestRequestTypeDef",
-    "UpdateChangesetRequestRequestTypeDef",
-    "UpdatePermissionGroupRequestRequestTypeDef",
-    "UpdateUserRequestRequestTypeDef",
-    "AssociateUserToPermissionGroupResponseTypeDef",
-    "CreateChangesetResponseTypeDef",
-    "CreateDataViewResponseTypeDef",
-    "CreateDatasetResponseTypeDef",
-    "CreatePermissionGroupResponseTypeDef",
-    "CreateUserResponseTypeDef",
-    "DeleteDatasetResponseTypeDef",
-    "DeletePermissionGroupResponseTypeDef",
-    "DisableUserResponseTypeDef",
-    "DisassociateUserFromPermissionGroupResponseTypeDef",
-    "EnableUserResponseTypeDef",
-    "GetUserResponseTypeDef",
-    "GetWorkingLocationResponseTypeDef",
     "ResetUserPasswordResponseTypeDef",
+    "ResponseMetadataTypeDef",
+    "UpdateChangesetRequestRequestTypeDef",
     "UpdateChangesetResponseTypeDef",
     "UpdateDatasetResponseTypeDef",
+    "UpdatePermissionGroupRequestRequestTypeDef",
     "UpdatePermissionGroupResponseTypeDef",
+    "UpdateUserRequestRequestTypeDef",
     "UpdateUserResponseTypeDef",
     "ChangesetSummaryTypeDef",
     "GetChangesetResponseTypeDef",
     "SchemaDefinitionTypeDef",
     "CreateDataViewRequestRequestTypeDef",
     "GetProgrammaticAccessCredentialsResponseTypeDef",
     "DataViewSummaryTypeDef",
     "GetDataViewResponseTypeDef",
     "GetExternalDataViewAccessDetailsResponseTypeDef",
     "GetPermissionGroupResponseTypeDef",
     "ListPermissionGroupsResponseTypeDef",
-    "ListChangesetsRequestListChangesetsPaginateTypeDef",
-    "ListDataViewsRequestListDataViewsPaginateTypeDef",
-    "ListDatasetsRequestListDatasetsPaginateTypeDef",
-    "ListPermissionGroupsRequestListPermissionGroupsPaginateTypeDef",
-    "ListUsersRequestListUsersPaginateTypeDef",
     "ListPermissionGroupsByUserResponseTypeDef",
     "ListUsersByPermissionGroupResponseTypeDef",
     "ListUsersResponseTypeDef",
     "PermissionGroupParamsTypeDef",
     "ListChangesetsResponseTypeDef",
     "SchemaUnionTypeDef",
     "ListDataViewsResponseTypeDef",
@@ -144,22 +144,19 @@
 
 class AssociateUserToPermissionGroupRequestRequestTypeDef(
     _RequiredAssociateUserToPermissionGroupRequestRequestTypeDef,
     _OptionalAssociateUserToPermissionGroupRequestRequestTypeDef,
 ):
     pass
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AssociateUserToPermissionGroupResponseTypeDef = TypedDict(
+    "AssociateUserToPermissionGroupResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "statusCode": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AwsCredentialsTypeDef = TypedDict(
     "AwsCredentialsTypeDef",
     {
         "accessKeyId": str,
@@ -207,14 +204,23 @@
 )
 
 class CreateChangesetRequestRequestTypeDef(
     _RequiredCreateChangesetRequestRequestTypeDef, _OptionalCreateChangesetRequestRequestTypeDef
 ):
     pass
 
+CreateChangesetResponseTypeDef = TypedDict(
+    "CreateChangesetResponseTypeDef",
+    {
+        "datasetId": str,
+        "changesetId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDataViewDestinationTypeParamsTypeDef = TypedDict(
     "_RequiredDataViewDestinationTypeParamsTypeDef",
     {
         "destinationType": str,
     },
 )
 _OptionalDataViewDestinationTypeParamsTypeDef = TypedDict(
@@ -227,24 +233,41 @@
 )
 
 class DataViewDestinationTypeParamsTypeDef(
     _RequiredDataViewDestinationTypeParamsTypeDef, _OptionalDataViewDestinationTypeParamsTypeDef
 ):
     pass
 
+CreateDataViewResponseTypeDef = TypedDict(
+    "CreateDataViewResponseTypeDef",
+    {
+        "datasetId": str,
+        "dataViewId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DatasetOwnerInfoTypeDef = TypedDict(
     "DatasetOwnerInfoTypeDef",
     {
         "name": str,
         "phoneNumber": str,
         "email": str,
     },
     total=False,
 )
 
+CreateDatasetResponseTypeDef = TypedDict(
+    "CreateDatasetResponseTypeDef",
+    {
+        "datasetId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreatePermissionGroupRequestRequestTypeDef = TypedDict(
     "_RequiredCreatePermissionGroupRequestRequestTypeDef",
     {
         "name": str,
         "applicationPermissions": Sequence[ApplicationPermissionType],
     },
 )
@@ -259,14 +282,22 @@
 
 class CreatePermissionGroupRequestRequestTypeDef(
     _RequiredCreatePermissionGroupRequestRequestTypeDef,
     _OptionalCreatePermissionGroupRequestRequestTypeDef,
 ):
     pass
 
+CreatePermissionGroupResponseTypeDef = TypedDict(
+    "CreatePermissionGroupResponseTypeDef",
+    {
+        "permissionGroupId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateUserRequestRequestTypeDef = TypedDict(
     "_RequiredCreateUserRequestRequestTypeDef",
     {
         "emailAddress": str,
         "type": UserTypeType,
     },
 )
@@ -283,14 +314,22 @@
 )
 
 class CreateUserRequestRequestTypeDef(
     _RequiredCreateUserRequestRequestTypeDef, _OptionalCreateUserRequestRequestTypeDef
 ):
     pass
 
+CreateUserResponseTypeDef = TypedDict(
+    "CreateUserResponseTypeDef",
+    {
+        "userId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CredentialsTypeDef = TypedDict(
     "CredentialsTypeDef",
     {
         "accessKeyId": str,
         "secretAccessKey": str,
         "sessionToken": str,
     },
@@ -321,14 +360,22 @@
 )
 
 class DeleteDatasetRequestRequestTypeDef(
     _RequiredDeleteDatasetRequestRequestTypeDef, _OptionalDeleteDatasetRequestRequestTypeDef
 ):
     pass
 
+DeleteDatasetResponseTypeDef = TypedDict(
+    "DeleteDatasetResponseTypeDef",
+    {
+        "datasetId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeletePermissionGroupRequestRequestTypeDef = TypedDict(
     "_RequiredDeletePermissionGroupRequestRequestTypeDef",
     {
         "permissionGroupId": str,
     },
 )
 _OptionalDeletePermissionGroupRequestRequestTypeDef = TypedDict(
@@ -341,14 +388,22 @@
 
 class DeletePermissionGroupRequestRequestTypeDef(
     _RequiredDeletePermissionGroupRequestRequestTypeDef,
     _OptionalDeletePermissionGroupRequestRequestTypeDef,
 ):
     pass
 
+DeletePermissionGroupResponseTypeDef = TypedDict(
+    "DeletePermissionGroupResponseTypeDef",
+    {
+        "permissionGroupId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDisableUserRequestRequestTypeDef = TypedDict(
     "_RequiredDisableUserRequestRequestTypeDef",
     {
         "userId": str,
     },
 )
 _OptionalDisableUserRequestRequestTypeDef = TypedDict(
@@ -360,14 +415,22 @@
 )
 
 class DisableUserRequestRequestTypeDef(
     _RequiredDisableUserRequestRequestTypeDef, _OptionalDisableUserRequestRequestTypeDef
 ):
     pass
 
+DisableUserResponseTypeDef = TypedDict(
+    "DisableUserResponseTypeDef",
+    {
+        "userId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDisassociateUserFromPermissionGroupRequestRequestTypeDef = TypedDict(
     "_RequiredDisassociateUserFromPermissionGroupRequestRequestTypeDef",
     {
         "permissionGroupId": str,
         "userId": str,
     },
 )
@@ -381,14 +444,22 @@
 
 class DisassociateUserFromPermissionGroupRequestRequestTypeDef(
     _RequiredDisassociateUserFromPermissionGroupRequestRequestTypeDef,
     _OptionalDisassociateUserFromPermissionGroupRequestRequestTypeDef,
 ):
     pass
 
+DisassociateUserFromPermissionGroupResponseTypeDef = TypedDict(
+    "DisassociateUserFromPermissionGroupResponseTypeDef",
+    {
+        "statusCode": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredEnableUserRequestRequestTypeDef = TypedDict(
     "_RequiredEnableUserRequestRequestTypeDef",
     {
         "userId": str,
     },
 )
 _OptionalEnableUserRequestRequestTypeDef = TypedDict(
@@ -400,14 +471,22 @@
 )
 
 class EnableUserRequestRequestTypeDef(
     _RequiredEnableUserRequestRequestTypeDef, _OptionalEnableUserRequestRequestTypeDef
 ):
     pass
 
+EnableUserResponseTypeDef = TypedDict(
+    "EnableUserResponseTypeDef",
+    {
+        "userId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetChangesetRequestRequestTypeDef = TypedDict(
     "GetChangesetRequestRequestTypeDef",
     {
         "datasetId": str,
         "changesetId": str,
     },
 )
@@ -487,32 +566,72 @@
 GetUserRequestRequestTypeDef = TypedDict(
     "GetUserRequestRequestTypeDef",
     {
         "userId": str,
     },
 )
 
+GetUserResponseTypeDef = TypedDict(
+    "GetUserResponseTypeDef",
+    {
+        "userId": str,
+        "status": UserStatusType,
+        "firstName": str,
+        "lastName": str,
+        "emailAddress": str,
+        "type": UserTypeType,
+        "apiAccess": ApiAccessType,
+        "apiAccessPrincipalArn": str,
+        "createTime": int,
+        "lastEnabledTime": int,
+        "lastDisabledTime": int,
+        "lastModifiedTime": int,
+        "lastLoginTime": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetWorkingLocationRequestRequestTypeDef = TypedDict(
     "GetWorkingLocationRequestRequestTypeDef",
     {
         "locationType": locationTypeType,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetWorkingLocationResponseTypeDef = TypedDict(
+    "GetWorkingLocationResponseTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "s3Uri": str,
+        "s3Path": str,
+        "s3Bucket": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListChangesetsRequestListChangesetsPaginateTypeDef = TypedDict(
+    "_RequiredListChangesetsRequestListChangesetsPaginateTypeDef",
+    {
+        "datasetId": str,
+    },
+)
+_OptionalListChangesetsRequestListChangesetsPaginateTypeDef = TypedDict(
+    "_OptionalListChangesetsRequestListChangesetsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListChangesetsRequestListChangesetsPaginateTypeDef(
+    _RequiredListChangesetsRequestListChangesetsPaginateTypeDef,
+    _OptionalListChangesetsRequestListChangesetsPaginateTypeDef,
+):
+    pass
+
 _RequiredListChangesetsRequestRequestTypeDef = TypedDict(
     "_RequiredListChangesetsRequestRequestTypeDef",
     {
         "datasetId": str,
     },
 )
 _OptionalListChangesetsRequestRequestTypeDef = TypedDict(
@@ -525,14 +644,34 @@
 )
 
 class ListChangesetsRequestRequestTypeDef(
     _RequiredListChangesetsRequestRequestTypeDef, _OptionalListChangesetsRequestRequestTypeDef
 ):
     pass
 
+_RequiredListDataViewsRequestListDataViewsPaginateTypeDef = TypedDict(
+    "_RequiredListDataViewsRequestListDataViewsPaginateTypeDef",
+    {
+        "datasetId": str,
+    },
+)
+_OptionalListDataViewsRequestListDataViewsPaginateTypeDef = TypedDict(
+    "_OptionalListDataViewsRequestListDataViewsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListDataViewsRequestListDataViewsPaginateTypeDef(
+    _RequiredListDataViewsRequestListDataViewsPaginateTypeDef,
+    _OptionalListDataViewsRequestListDataViewsPaginateTypeDef,
+):
+    pass
+
 _RequiredListDataViewsRequestRequestTypeDef = TypedDict(
     "_RequiredListDataViewsRequestRequestTypeDef",
     {
         "datasetId": str,
     },
 )
 _OptionalListDataViewsRequestRequestTypeDef = TypedDict(
@@ -545,14 +684,22 @@
 )
 
 class ListDataViewsRequestRequestTypeDef(
     _RequiredListDataViewsRequestRequestTypeDef, _OptionalListDataViewsRequestRequestTypeDef
 ):
     pass
 
+ListDatasetsRequestListDatasetsPaginateTypeDef = TypedDict(
+    "ListDatasetsRequestListDatasetsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDatasetsRequestRequestTypeDef = TypedDict(
     "ListDatasetsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
@@ -585,14 +732,22 @@
         "permissionGroupId": str,
         "name": str,
         "membershipStatus": PermissionGroupMembershipStatusType,
     },
     total=False,
 )
 
+ListPermissionGroupsRequestListPermissionGroupsPaginateTypeDef = TypedDict(
+    "ListPermissionGroupsRequestListPermissionGroupsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 _RequiredListPermissionGroupsRequestRequestTypeDef = TypedDict(
     "_RequiredListPermissionGroupsRequestRequestTypeDef",
     {
         "maxResults": int,
     },
 )
 _OptionalListPermissionGroupsRequestRequestTypeDef = TypedDict(
@@ -642,14 +797,22 @@
         "apiAccess": ApiAccessType,
         "apiAccessPrincipalArn": str,
         "membershipStatus": PermissionGroupMembershipStatusType,
     },
     total=False,
 )
 
+ListUsersRequestListUsersPaginateTypeDef = TypedDict(
+    "ListUsersRequestListUsersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 _RequiredListUsersRequestRequestTypeDef = TypedDict(
     "_RequiredListUsersRequestRequestTypeDef",
     {
         "maxResults": int,
     },
 )
 _OptionalListUsersRequestRequestTypeDef = TypedDict(
@@ -681,14 +844,24 @@
         "lastDisabledTime": int,
         "lastModifiedTime": int,
         "lastLoginTime": int,
     },
     total=False,
 )
 
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
 ResourcePermissionTypeDef = TypedDict(
     "ResourcePermissionTypeDef",
     {
         "permission": str,
     },
     total=False,
 )
@@ -708,14 +881,34 @@
 )
 
 class ResetUserPasswordRequestRequestTypeDef(
     _RequiredResetUserPasswordRequestRequestTypeDef, _OptionalResetUserPasswordRequestRequestTypeDef
 ):
     pass
 
+ResetUserPasswordResponseTypeDef = TypedDict(
+    "ResetUserPasswordResponseTypeDef",
+    {
+        "userId": str,
+        "temporaryPassword": str,
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
 _RequiredUpdateChangesetRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateChangesetRequestRequestTypeDef",
     {
         "datasetId": str,
         "changesetId": str,
         "sourceParams": Mapping[str, str],
         "formatParams": Mapping[str, str],
@@ -730,14 +923,31 @@
 )
 
 class UpdateChangesetRequestRequestTypeDef(
     _RequiredUpdateChangesetRequestRequestTypeDef, _OptionalUpdateChangesetRequestRequestTypeDef
 ):
     pass
 
+UpdateChangesetResponseTypeDef = TypedDict(
+    "UpdateChangesetResponseTypeDef",
+    {
+        "changesetId": str,
+        "datasetId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateDatasetResponseTypeDef = TypedDict(
+    "UpdateDatasetResponseTypeDef",
+    {
+        "datasetId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdatePermissionGroupRequestRequestTypeDef = TypedDict(
     "_RequiredUpdatePermissionGroupRequestRequestTypeDef",
     {
         "permissionGroupId": str,
     },
 )
 _OptionalUpdatePermissionGroupRequestRequestTypeDef = TypedDict(
@@ -753,14 +963,22 @@
 
 class UpdatePermissionGroupRequestRequestTypeDef(
     _RequiredUpdatePermissionGroupRequestRequestTypeDef,
     _OptionalUpdatePermissionGroupRequestRequestTypeDef,
 ):
     pass
 
+UpdatePermissionGroupResponseTypeDef = TypedDict(
+    "UpdatePermissionGroupResponseTypeDef",
+    {
+        "permissionGroupId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateUserRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateUserRequestRequestTypeDef",
     {
         "userId": str,
     },
 )
 _OptionalUpdateUserRequestRequestTypeDef = TypedDict(
@@ -777,173 +995,19 @@
 )
 
 class UpdateUserRequestRequestTypeDef(
     _RequiredUpdateUserRequestRequestTypeDef, _OptionalUpdateUserRequestRequestTypeDef
 ):
     pass
 
-AssociateUserToPermissionGroupResponseTypeDef = TypedDict(
-    "AssociateUserToPermissionGroupResponseTypeDef",
-    {
-        "statusCode": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateChangesetResponseTypeDef = TypedDict(
-    "CreateChangesetResponseTypeDef",
-    {
-        "datasetId": str,
-        "changesetId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDataViewResponseTypeDef = TypedDict(
-    "CreateDataViewResponseTypeDef",
-    {
-        "datasetId": str,
-        "dataViewId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDatasetResponseTypeDef = TypedDict(
-    "CreateDatasetResponseTypeDef",
-    {
-        "datasetId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreatePermissionGroupResponseTypeDef = TypedDict(
-    "CreatePermissionGroupResponseTypeDef",
-    {
-        "permissionGroupId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateUserResponseTypeDef = TypedDict(
-    "CreateUserResponseTypeDef",
-    {
-        "userId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteDatasetResponseTypeDef = TypedDict(
-    "DeleteDatasetResponseTypeDef",
-    {
-        "datasetId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeletePermissionGroupResponseTypeDef = TypedDict(
-    "DeletePermissionGroupResponseTypeDef",
-    {
-        "permissionGroupId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DisableUserResponseTypeDef = TypedDict(
-    "DisableUserResponseTypeDef",
-    {
-        "userId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DisassociateUserFromPermissionGroupResponseTypeDef = TypedDict(
-    "DisassociateUserFromPermissionGroupResponseTypeDef",
-    {
-        "statusCode": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-EnableUserResponseTypeDef = TypedDict(
-    "EnableUserResponseTypeDef",
-    {
-        "userId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetUserResponseTypeDef = TypedDict(
-    "GetUserResponseTypeDef",
-    {
-        "userId": str,
-        "status": UserStatusType,
-        "firstName": str,
-        "lastName": str,
-        "emailAddress": str,
-        "type": UserTypeType,
-        "apiAccess": ApiAccessType,
-        "apiAccessPrincipalArn": str,
-        "createTime": int,
-        "lastEnabledTime": int,
-        "lastDisabledTime": int,
-        "lastModifiedTime": int,
-        "lastLoginTime": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetWorkingLocationResponseTypeDef = TypedDict(
-    "GetWorkingLocationResponseTypeDef",
-    {
-        "s3Uri": str,
-        "s3Path": str,
-        "s3Bucket": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ResetUserPasswordResponseTypeDef = TypedDict(
-    "ResetUserPasswordResponseTypeDef",
-    {
-        "userId": str,
-        "temporaryPassword": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateChangesetResponseTypeDef = TypedDict(
-    "UpdateChangesetResponseTypeDef",
-    {
-        "changesetId": str,
-        "datasetId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateDatasetResponseTypeDef = TypedDict(
-    "UpdateDatasetResponseTypeDef",
-    {
-        "datasetId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdatePermissionGroupResponseTypeDef = TypedDict(
-    "UpdatePermissionGroupResponseTypeDef",
-    {
-        "permissionGroupId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 UpdateUserResponseTypeDef = TypedDict(
     "UpdateUserResponseTypeDef",
     {
         "userId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ChangesetSummaryTypeDef = TypedDict(
     "ChangesetSummaryTypeDef",
     {
         "changesetId": str,
@@ -975,15 +1039,15 @@
         "createTime": int,
         "status": IngestionStatusType,
         "errorInfo": ChangesetErrorInfoTypeDef,
         "activeUntilTimestamp": int,
         "activeFromTimestamp": int,
         "updatesChangesetId": str,
         "updatedByChangesetId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SchemaDefinitionTypeDef = TypedDict(
     "SchemaDefinitionTypeDef",
     {
         "columns": Sequence[ColumnDefinitionTypeDef],
@@ -1017,15 +1081,15 @@
     pass
 
 GetProgrammaticAccessCredentialsResponseTypeDef = TypedDict(
     "GetProgrammaticAccessCredentialsResponseTypeDef",
     {
         "credentials": CredentialsTypeDef,
         "durationInMinutes": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DataViewSummaryTypeDef = TypedDict(
     "DataViewSummaryTypeDef",
     {
         "dataViewId": str,
@@ -1055,132 +1119,68 @@
         "lastModifiedTime": int,
         "createTime": int,
         "sortColumns": List[str],
         "dataViewId": str,
         "dataViewArn": str,
         "destinationTypeParams": DataViewDestinationTypeParamsTypeDef,
         "status": DataViewStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetExternalDataViewAccessDetailsResponseTypeDef = TypedDict(
     "GetExternalDataViewAccessDetailsResponseTypeDef",
     {
         "credentials": AwsCredentialsTypeDef,
         "s3Location": S3LocationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetPermissionGroupResponseTypeDef = TypedDict(
     "GetPermissionGroupResponseTypeDef",
     {
         "permissionGroup": PermissionGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPermissionGroupsResponseTypeDef = TypedDict(
     "ListPermissionGroupsResponseTypeDef",
     {
         "permissionGroups": List[PermissionGroupTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-_RequiredListChangesetsRequestListChangesetsPaginateTypeDef = TypedDict(
-    "_RequiredListChangesetsRequestListChangesetsPaginateTypeDef",
-    {
-        "datasetId": str,
-    },
-)
-_OptionalListChangesetsRequestListChangesetsPaginateTypeDef = TypedDict(
-    "_OptionalListChangesetsRequestListChangesetsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListChangesetsRequestListChangesetsPaginateTypeDef(
-    _RequiredListChangesetsRequestListChangesetsPaginateTypeDef,
-    _OptionalListChangesetsRequestListChangesetsPaginateTypeDef,
-):
-    pass
-
-_RequiredListDataViewsRequestListDataViewsPaginateTypeDef = TypedDict(
-    "_RequiredListDataViewsRequestListDataViewsPaginateTypeDef",
-    {
-        "datasetId": str,
-    },
-)
-_OptionalListDataViewsRequestListDataViewsPaginateTypeDef = TypedDict(
-    "_OptionalListDataViewsRequestListDataViewsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListDataViewsRequestListDataViewsPaginateTypeDef(
-    _RequiredListDataViewsRequestListDataViewsPaginateTypeDef,
-    _OptionalListDataViewsRequestListDataViewsPaginateTypeDef,
-):
-    pass
-
-ListDatasetsRequestListDatasetsPaginateTypeDef = TypedDict(
-    "ListDatasetsRequestListDatasetsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListPermissionGroupsRequestListPermissionGroupsPaginateTypeDef = TypedDict(
-    "ListPermissionGroupsRequestListPermissionGroupsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListUsersRequestListUsersPaginateTypeDef = TypedDict(
-    "ListUsersRequestListUsersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListPermissionGroupsByUserResponseTypeDef = TypedDict(
     "ListPermissionGroupsByUserResponseTypeDef",
     {
         "permissionGroups": List[PermissionGroupByUserTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListUsersByPermissionGroupResponseTypeDef = TypedDict(
     "ListUsersByPermissionGroupResponseTypeDef",
     {
         "users": List[UserByPermissionGroupTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListUsersResponseTypeDef = TypedDict(
     "ListUsersResponseTypeDef",
     {
         "users": List[UserTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PermissionGroupParamsTypeDef = TypedDict(
     "PermissionGroupParamsTypeDef",
     {
         "permissionGroupId": str,
@@ -1190,15 +1190,15 @@
 )
 
 ListChangesetsResponseTypeDef = TypedDict(
     "ListChangesetsResponseTypeDef",
     {
         "changesets": List[ChangesetSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SchemaUnionTypeDef = TypedDict(
     "SchemaUnionTypeDef",
     {
         "tabularSchemaConfig": SchemaDefinitionTypeDef,
@@ -1207,15 +1207,15 @@
 )
 
 ListDataViewsResponseTypeDef = TypedDict(
     "ListDataViewsResponseTypeDef",
     {
         "nextToken": str,
         "dataViews": List[DataViewSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateDatasetRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDatasetRequestRequestTypeDef",
     {
         "datasetTitle": str,
@@ -1266,15 +1266,15 @@
         "kind": DatasetKindType,
         "datasetDescription": str,
         "createTime": int,
         "lastModifiedTime": int,
         "schemaDefinition": SchemaUnionTypeDef,
         "alias": str,
         "status": DatasetStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateDatasetRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateDatasetRequestRequestTypeDef",
     {
         "datasetId": str,
@@ -1299,10 +1299,10 @@
     pass
 
 ListDatasetsResponseTypeDef = TypedDict(
     "ListDatasetsResponseTypeDef",
     {
         "datasets": List[DatasetTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-finspace-data-2.5.0.post1/types_aiobotocore_finspace_data.egg-info/PKG-INFO` & `types-aiobotocore-finspace-data-2.5.1/types_aiobotocore_finspace_data.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-finspace-data
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.FinSpaceData 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.FinSpaceData 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_finspace_data/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-finspace-data"></a>
 
 # types-aiobotocore-finspace-data
 
 [![PyPI - types-aiobotocore-finspace-data](https://img.shields.io/pypi/v/types-aiobotocore-finspace-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-finspace-data)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-finspace-data.svg?color=blue)](https://pypi.org/project/types-aiobotocore-finspace-data)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_finspace_data/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-finspace-data?color=blue)](https://pypistats.org/packages/types-aiobotocore-finspace-data)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.FinSpaceData 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/finspace-data.html#FinSpaceData)
+[aiobotocore.FinSpaceData 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/finspace-data.html#FinSpaceData)
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
 [types-aiobotocore-finspace-data docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_finspace_data/).
 
 See how it helps to find and fix potential bugs:
 
@@ -345,89 +345,89 @@
 
 `types_aiobotocore_finspace_data.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_finspace_data.type_defs import (
     AssociateUserToPermissionGroupRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AssociateUserToPermissionGroupResponseTypeDef,
     AwsCredentialsTypeDef,
     ChangesetErrorInfoTypeDef,
     ColumnDefinitionTypeDef,
     CreateChangesetRequestRequestTypeDef,
+    CreateChangesetResponseTypeDef,
     DataViewDestinationTypeParamsTypeDef,
+    CreateDataViewResponseTypeDef,
     DatasetOwnerInfoTypeDef,
+    CreateDatasetResponseTypeDef,
     CreatePermissionGroupRequestRequestTypeDef,
+    CreatePermissionGroupResponseTypeDef,
     CreateUserRequestRequestTypeDef,
+    CreateUserResponseTypeDef,
     CredentialsTypeDef,
     DataViewErrorInfoTypeDef,
     DeleteDatasetRequestRequestTypeDef,
+    DeleteDatasetResponseTypeDef,
     DeletePermissionGroupRequestRequestTypeDef,
+    DeletePermissionGroupResponseTypeDef,
     DisableUserRequestRequestTypeDef,
+    DisableUserResponseTypeDef,
     DisassociateUserFromPermissionGroupRequestRequestTypeDef,
+    DisassociateUserFromPermissionGroupResponseTypeDef,
     EnableUserRequestRequestTypeDef,
+    EnableUserResponseTypeDef,
     GetChangesetRequestRequestTypeDef,
     GetDataViewRequestRequestTypeDef,
     GetDatasetRequestRequestTypeDef,
     GetExternalDataViewAccessDetailsRequestRequestTypeDef,
     S3LocationTypeDef,
     GetPermissionGroupRequestRequestTypeDef,
     PermissionGroupTypeDef,
     GetProgrammaticAccessCredentialsRequestRequestTypeDef,
     GetUserRequestRequestTypeDef,
+    GetUserResponseTypeDef,
     GetWorkingLocationRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetWorkingLocationResponseTypeDef,
+    ListChangesetsRequestListChangesetsPaginateTypeDef,
     ListChangesetsRequestRequestTypeDef,
+    ListDataViewsRequestListDataViewsPaginateTypeDef,
     ListDataViewsRequestRequestTypeDef,
+    ListDatasetsRequestListDatasetsPaginateTypeDef,
     ListDatasetsRequestRequestTypeDef,
     ListPermissionGroupsByUserRequestRequestTypeDef,
     PermissionGroupByUserTypeDef,
+    ListPermissionGroupsRequestListPermissionGroupsPaginateTypeDef,
     ListPermissionGroupsRequestRequestTypeDef,
     ListUsersByPermissionGroupRequestRequestTypeDef,
     UserByPermissionGroupTypeDef,
+    ListUsersRequestListUsersPaginateTypeDef,
     ListUsersRequestRequestTypeDef,
     UserTypeDef,
+    PaginatorConfigTypeDef,
     ResourcePermissionTypeDef,
     ResetUserPasswordRequestRequestTypeDef,
-    UpdateChangesetRequestRequestTypeDef,
-    UpdatePermissionGroupRequestRequestTypeDef,
-    UpdateUserRequestRequestTypeDef,
-    AssociateUserToPermissionGroupResponseTypeDef,
-    CreateChangesetResponseTypeDef,
-    CreateDataViewResponseTypeDef,
-    CreateDatasetResponseTypeDef,
-    CreatePermissionGroupResponseTypeDef,
-    CreateUserResponseTypeDef,
-    DeleteDatasetResponseTypeDef,
-    DeletePermissionGroupResponseTypeDef,
-    DisableUserResponseTypeDef,
-    DisassociateUserFromPermissionGroupResponseTypeDef,
-    EnableUserResponseTypeDef,
-    GetUserResponseTypeDef,
-    GetWorkingLocationResponseTypeDef,
     ResetUserPasswordResponseTypeDef,
+    ResponseMetadataTypeDef,
+    UpdateChangesetRequestRequestTypeDef,
     UpdateChangesetResponseTypeDef,
     UpdateDatasetResponseTypeDef,
+    UpdatePermissionGroupRequestRequestTypeDef,
     UpdatePermissionGroupResponseTypeDef,
+    UpdateUserRequestRequestTypeDef,
     UpdateUserResponseTypeDef,
     ChangesetSummaryTypeDef,
     GetChangesetResponseTypeDef,
     SchemaDefinitionTypeDef,
     CreateDataViewRequestRequestTypeDef,
     GetProgrammaticAccessCredentialsResponseTypeDef,
     DataViewSummaryTypeDef,
     GetDataViewResponseTypeDef,
     GetExternalDataViewAccessDetailsResponseTypeDef,
     GetPermissionGroupResponseTypeDef,
     ListPermissionGroupsResponseTypeDef,
-    ListChangesetsRequestListChangesetsPaginateTypeDef,
-    ListDataViewsRequestListDataViewsPaginateTypeDef,
-    ListDatasetsRequestListDatasetsPaginateTypeDef,
-    ListPermissionGroupsRequestListPermissionGroupsPaginateTypeDef,
-    ListUsersRequestListUsersPaginateTypeDef,
     ListPermissionGroupsByUserResponseTypeDef,
     ListUsersByPermissionGroupResponseTypeDef,
     ListUsersResponseTypeDef,
     PermissionGroupParamsTypeDef,
     ListChangesetsResponseTypeDef,
     SchemaUnionTypeDef,
     ListDataViewsResponseTypeDef,
@@ -446,43 +446,43 @@
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

### Comparing `types-aiobotocore-finspace-data-2.5.0.post1/types_aiobotocore_finspace_data.egg-info/SOURCES.txt` & `types-aiobotocore-finspace-data-2.5.1/types_aiobotocore_finspace_data.egg-info/SOURCES.txt`

 * *Files identical despite different names*

