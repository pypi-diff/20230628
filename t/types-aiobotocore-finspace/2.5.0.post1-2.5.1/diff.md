# Comparing `tmp/types-aiobotocore-finspace-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-finspace-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-finspace-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:38 2023, max compression
+gzip compressed data, was "types-aiobotocore-finspace-2.5.1.tar", last modified: Wed Jun 28 01:43:29 2023, max compression
```

## Comparing `types-aiobotocore-finspace-2.5.0.post1.tar` & `types-aiobotocore-finspace-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:37.987210 types-aiobotocore-finspace-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:14:32.000000 types-aiobotocore-finspace-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    12777 2023-03-11 12:26:37.987210 types-aiobotocore-finspace-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    11202 2023-03-11 12:14:32.000000 types-aiobotocore-finspace-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:37.987210 types-aiobotocore-finspace-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2131 2023-03-11 12:14:32.000000 types-aiobotocore-finspace-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:37.987210 types-aiobotocore-finspace-2.5.0.post1/types_aiobotocore_finspace/
--rw-r--r--   0 runner    (1001) docker     (123)      450 2023-03-11 12:14:32.000000 types-aiobotocore-finspace-2.5.0.post1/types_aiobotocore_finspace/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      449 2023-03-11 12:14:32.000000 types-aiobotocore-finspace-2.5.0.post1/types_aiobotocore_finspace/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      947 2023-03-11 12:14:32.000000 types-aiobotocore-finspace-2.5.0.post1/types_aiobotocore_finspace/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     8983 2023-03-11 12:14:32.000000 types-aiobotocore-finspace-2.5.0.post1/types_aiobotocore_finspace/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     8967 2023-03-11 12:14:32.000000 types-aiobotocore-finspace-2.5.0.post1/types_aiobotocore_finspace/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7775 2023-03-11 12:14:32.000000 types-aiobotocore-finspace-2.5.0.post1/types_aiobotocore_finspace/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7773 2023-03-11 12:14:32.000000 types-aiobotocore-finspace-2.5.0.post1/types_aiobotocore_finspace/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:14:32.000000 types-aiobotocore-finspace-2.5.0.post1/types_aiobotocore_finspace/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     5902 2023-03-11 12:14:32.000000 types-aiobotocore-finspace-2.5.0.post1/types_aiobotocore_finspace/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     5897 2023-03-11 12:14:32.000000 types-aiobotocore-finspace-2.5.0.post1/types_aiobotocore_finspace/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:14:32.000000 types-aiobotocore-finspace-2.5.0.post1/types_aiobotocore_finspace/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:37.987210 types-aiobotocore-finspace-2.5.0.post1/types_aiobotocore_finspace.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    12777 2023-03-11 12:26:37.000000 types-aiobotocore-finspace-2.5.0.post1/types_aiobotocore_finspace.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      751 2023-03-11 12:26:37.000000 types-aiobotocore-finspace-2.5.0.post1/types_aiobotocore_finspace.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:37.000000 types-aiobotocore-finspace-2.5.0.post1/types_aiobotocore_finspace.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:37.000000 types-aiobotocore-finspace-2.5.0.post1/types_aiobotocore_finspace.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:37.000000 types-aiobotocore-finspace-2.5.0.post1/types_aiobotocore_finspace.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       27 2023-03-11 12:26:37.000000 types-aiobotocore-finspace-2.5.0.post1/types_aiobotocore_finspace.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:29.658137 types-aiobotocore-finspace-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:31:07.000000 types-aiobotocore-finspace-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    16401 2023-06-28 01:43:29.658137 types-aiobotocore-finspace-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    14832 2023-06-28 01:31:07.000000 types-aiobotocore-finspace-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:29.658137 types-aiobotocore-finspace-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2125 2023-06-28 01:31:07.000000 types-aiobotocore-finspace-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:29.658137 types-aiobotocore-finspace-2.5.1/types_aiobotocore_finspace/
+-rw-r--r--   0 runner    (1001) docker     (123)      681 2023-06-28 01:31:07.000000 types-aiobotocore-finspace-2.5.1/types_aiobotocore_finspace/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      680 2023-06-28 01:31:07.000000 types-aiobotocore-finspace-2.5.1/types_aiobotocore_finspace/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      935 2023-06-28 01:31:07.000000 types-aiobotocore-finspace-2.5.1/types_aiobotocore_finspace/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    26541 2023-06-28 01:31:08.000000 types-aiobotocore-finspace-2.5.1/types_aiobotocore_finspace/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    26497 2023-06-28 01:31:08.000000 types-aiobotocore-finspace-2.5.1/types_aiobotocore_finspace/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9697 2023-06-28 01:31:08.000000 types-aiobotocore-finspace-2.5.1/types_aiobotocore_finspace/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9695 2023-06-28 01:31:08.000000 types-aiobotocore-finspace-2.5.1/types_aiobotocore_finspace/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     2044 2023-06-28 01:31:08.000000 types-aiobotocore-finspace-2.5.1/types_aiobotocore_finspace/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2041 2023-06-28 01:31:08.000000 types-aiobotocore-finspace-2.5.1/types_aiobotocore_finspace/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:31:07.000000 types-aiobotocore-finspace-2.5.1/types_aiobotocore_finspace/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    34947 2023-06-28 01:31:08.000000 types-aiobotocore-finspace-2.5.1/types_aiobotocore_finspace/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    34909 2023-06-28 01:31:08.000000 types-aiobotocore-finspace-2.5.1/types_aiobotocore_finspace/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:31:07.000000 types-aiobotocore-finspace-2.5.1/types_aiobotocore_finspace/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:29.658137 types-aiobotocore-finspace-2.5.1/types_aiobotocore_finspace.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    16401 2023-06-28 01:43:29.000000 types-aiobotocore-finspace-2.5.1/types_aiobotocore_finspace.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      832 2023-06-28 01:43:29.000000 types-aiobotocore-finspace-2.5.1/types_aiobotocore_finspace.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:29.000000 types-aiobotocore-finspace-2.5.1/types_aiobotocore_finspace.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:29.000000 types-aiobotocore-finspace-2.5.1/types_aiobotocore_finspace.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:29.000000 types-aiobotocore-finspace-2.5.1/types_aiobotocore_finspace.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       27 2023-06-28 01:43:29.000000 types-aiobotocore-finspace-2.5.1/types_aiobotocore_finspace.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-finspace-2.5.0.post1/LICENSE` & `types-aiobotocore-finspace-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-finspace-2.5.0.post1/README.md` & `types-aiobotocore-finspace-2.5.1/PKG-INFO`

 * *Files 23% similar despite different names*

```diff
@@ -1,29 +1,62 @@
+Metadata-Version: 2.1
+Name: types-aiobotocore-finspace
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.finspace 2.5.1 service generated with mypy-boto3-builder 7.14.5
+Home-page: https://github.com/youtype/mypy_boto3_builder
+Author: Vlad Emelianov
+Author-email: vlad.emelianov.nz@gmail.com
+License: MIT License
+Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_finspace/
+Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
+Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
+Keywords: aiobotocore finspace type-annotations boto3-stubs mypy typeshed autocomplete
+Classifier: Development Status :: 5 - Production/Stable
+Classifier: Intended Audience :: Developers
+Classifier: Environment :: Console
+Classifier: License :: OSI Approved :: MIT License
+Classifier: Natural Language :: English
+Classifier: Operating System :: OS Independent
+Classifier: Programming Language :: Python :: 3
+Classifier: Programming Language :: Python :: 3.7
+Classifier: Programming Language :: Python :: 3.7
+Classifier: Programming Language :: Python :: 3.8
+Classifier: Programming Language :: Python :: 3.9
+Classifier: Programming Language :: Python :: 3.10
+Classifier: Programming Language :: Python :: 3.11
+Classifier: Programming Language :: Python :: 3.12
+Classifier: Programming Language :: Python :: 3 :: Only
+Classifier: Programming Language :: Python :: Implementation :: CPython
+Classifier: Typing :: Typed
+Requires-Python: >=3.7
+Description-Content-Type: text/markdown
+License-File: LICENSE
+
 <a id="types-aiobotocore-finspace"></a>
 
 # types-aiobotocore-finspace
 
 [![PyPI - types-aiobotocore-finspace](https://img.shields.io/pypi/v/types-aiobotocore-finspace.svg?color=blue)](https://pypi.org/project/types-aiobotocore-finspace)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-finspace.svg?color=blue)](https://pypi.org/project/types-aiobotocore-finspace)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_finspace/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-finspace?color=blue)](https://pypistats.org/packages/types-aiobotocore-finspace)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.finspace 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/finspace.html#finspace)
+[aiobotocore.finspace 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/finspace.html#finspace)
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
 [types-aiobotocore-finspace docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_finspace/).
 
 See how it helps to find and fix potential bugs:
 
@@ -39,14 +72,15 @@
     - [Emacs](#emacs)
     - [Sublime Text](#sublime-text)
     - [Other IDEs](#other-ides)
     - [mypy](#mypy)
     - [pyright](#pyright)
   - [Explicit type annotations](#explicit-type-annotations)
     - [Client annotations](#client-annotations)
+    - [Paginators annotations](#paginators-annotations)
     - [Literals](#literals)
     - [Typed dictionaries](#typed-dictionaries)
   - [How it works](#how-it-works)
   - [What's new](#what's-new)
     - [Implemented features](#implemented-features)
     - [Latest changes](#latest-changes)
   - [Versioning](#versioning)
@@ -226,105 +260,210 @@
 
 session = get_session()
 async with session.create_client("finspace") as client:
     client: finspaceClient
     # now client usage is checked by mypy and IDE should provide code completion
 ```
 
+<a id="paginators-annotations"></a>
+
+### Paginators annotations
+
+`types_aiobotocore_finspace.paginator` module contains type annotations for all
+paginators.
+
+```python
+from aiobotocore.session import get_session
+
+from types_aiobotocore_finspace import finspaceClient
+from types_aiobotocore_finspace.paginator import ListKxEnvironmentsPaginator
+
+session = get_session()
+async with session.create_client("finspace") as client:
+    client: finspaceClient
+
+    # Explicit type annotations are optional here
+    # Types should be correctly discovered by mypy and IDEs
+    list_kx_environments_paginator: ListKxEnvironmentsPaginator = client.get_paginator(
+        "list_kx_environments"
+    )
+```
+
 <a id="literals"></a>
 
 ### Literals
 
 `types_aiobotocore_finspace.literals` module contains literals extracted from
 shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_finspace.literals import (
+    AutoScalingMetricType,
+    ChangeTypeType,
+    ChangesetStatusType,
     EnvironmentStatusType,
+    ErrorDetailsType,
     FederationModeType,
+    IPAddressTypeType,
+    KxAzModeType,
+    KxClusterStatusType,
+    KxClusterTypeType,
+    KxSavedownStorageTypeType,
+    ListKxEnvironmentsPaginatorName,
+    dnsStatusType,
+    tgwStatusType,
     finspaceServiceName,
     ServiceName,
     ResourceServiceName,
+    PaginatorName,
     RegionName,
 )
 
 
-def check_value(value: EnvironmentStatusType) -> bool:
+def check_value(value: AutoScalingMetricType) -> bool:
     ...
 ```
 
 <a id="typed-dictionaries"></a>
 
 ### Typed dictionaries
 
 `types_aiobotocore_finspace.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_finspace.type_defs import (
+    AutoScalingConfigurationTypeDef,
+    CapacityConfigurationTypeDef,
+    ChangeRequestTypeDef,
+    CodeConfigurationTypeDef,
     FederationParametersTypeDef,
     SuperuserParametersTypeDef,
-    ResponseMetadataTypeDef,
+    CreateEnvironmentResponseTypeDef,
+    ErrorInfoTypeDef,
+    KxCacheStorageConfigurationTypeDef,
+    KxCommandLineArgumentTypeDef,
+    KxSavedownStorageConfigurationTypeDef,
+    VpcConfigurationTypeDef,
+    CreateKxDatabaseRequestRequestTypeDef,
+    CreateKxDatabaseResponseTypeDef,
+    CreateKxEnvironmentRequestRequestTypeDef,
+    CreateKxEnvironmentResponseTypeDef,
+    CreateKxUserRequestRequestTypeDef,
+    CreateKxUserResponseTypeDef,
+    CustomDNSServerTypeDef,
     DeleteEnvironmentRequestRequestTypeDef,
+    DeleteKxClusterRequestRequestTypeDef,
+    DeleteKxDatabaseRequestRequestTypeDef,
+    DeleteKxEnvironmentRequestRequestTypeDef,
+    DeleteKxUserRequestRequestTypeDef,
     GetEnvironmentRequestRequestTypeDef,
+    GetKxChangesetRequestRequestTypeDef,
+    GetKxClusterRequestRequestTypeDef,
+    GetKxConnectionStringRequestRequestTypeDef,
+    GetKxConnectionStringResponseTypeDef,
+    GetKxDatabaseRequestRequestTypeDef,
+    GetKxDatabaseResponseTypeDef,
+    GetKxEnvironmentRequestRequestTypeDef,
+    TransitGatewayConfigurationTypeDef,
+    GetKxUserRequestRequestTypeDef,
+    GetKxUserResponseTypeDef,
+    KxChangesetListEntryTypeDef,
+    KxClusterTypeDef,
+    KxDatabaseCacheConfigurationTypeDef,
+    KxDatabaseListEntryTypeDef,
+    KxNodeTypeDef,
+    KxUserTypeDef,
     ListEnvironmentsRequestRequestTypeDef,
+    ListKxChangesetsRequestRequestTypeDef,
+    ListKxClusterNodesRequestRequestTypeDef,
+    ListKxClustersRequestRequestTypeDef,
+    ListKxDatabasesRequestRequestTypeDef,
+    ListKxEnvironmentsRequestListKxEnvironmentsPaginateTypeDef,
+    ListKxEnvironmentsRequestRequestTypeDef,
+    ListKxUsersRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateKxDatabaseRequestRequestTypeDef,
+    UpdateKxDatabaseResponseTypeDef,
+    UpdateKxEnvironmentRequestRequestTypeDef,
+    UpdateKxUserRequestRequestTypeDef,
+    UpdateKxUserResponseTypeDef,
+    CreateKxChangesetRequestRequestTypeDef,
     EnvironmentTypeDef,
     UpdateEnvironmentRequestRequestTypeDef,
     CreateEnvironmentRequestRequestTypeDef,
-    CreateEnvironmentResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
+    CreateKxChangesetResponseTypeDef,
+    GetKxChangesetResponseTypeDef,
+    GetKxEnvironmentResponseTypeDef,
+    KxEnvironmentTypeDef,
+    UpdateKxEnvironmentNetworkRequestRequestTypeDef,
+    UpdateKxEnvironmentNetworkResponseTypeDef,
+    UpdateKxEnvironmentResponseTypeDef,
+    ListKxChangesetsResponseTypeDef,
+    ListKxClustersResponseTypeDef,
+    KxDatabaseConfigurationTypeDef,
+    ListKxDatabasesResponseTypeDef,
+    ListKxClusterNodesResponseTypeDef,
+    ListKxUsersResponseTypeDef,
     GetEnvironmentResponseTypeDef,
     ListEnvironmentsResponseTypeDef,
     UpdateEnvironmentResponseTypeDef,
+    ListKxEnvironmentsResponseTypeDef,
+    CreateKxClusterRequestRequestTypeDef,
+    CreateKxClusterResponseTypeDef,
+    GetKxClusterResponseTypeDef,
+    UpdateKxClusterDatabasesRequestRequestTypeDef,
 )
 
 
-def get_structure() -> FederationParametersTypeDef:
+def get_structure() -> AutoScalingConfigurationTypeDef:
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

### Comparing `types-aiobotocore-finspace-2.5.0.post1/setup.py` & `types-aiobotocore-finspace-2.5.1/setup.py`

 * *Files 13% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-finspace.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-finspace",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_finspace"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.finspace 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.finspace 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_finspace/"
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

### Comparing `types-aiobotocore-finspace-2.5.0.post1/types_aiobotocore_finspace/__main__.py` & `types-aiobotocore-finspace-2.5.1/types_aiobotocore_finspace/__main__.py`

 * *Files 16% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.finspace 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.finspace 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_finspace//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/finspace.html#finspace\nOther"
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

### Comparing `types-aiobotocore-finspace-2.5.0.post1/types_aiobotocore_finspace/literals.py` & `types-aiobotocore-finspace-2.5.1/types_aiobotocore_finspace/literals.py`

 * *Files 25% similar despite different names*

```diff
@@ -2,50 +2,100 @@
 Type annotations for finspace service literal definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_finspace/literals/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_finspace.literals import EnvironmentStatusType
+    from types_aiobotocore_finspace.literals import AutoScalingMetricType
 
-    data: EnvironmentStatusType = "CREATE_REQUESTED"
+    data: AutoScalingMetricType = "CPU_UTILIZATION_PERCENTAGE"
     ```
 """
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 
 __all__ = (
+    "AutoScalingMetricType",
+    "ChangeTypeType",
+    "ChangesetStatusType",
     "EnvironmentStatusType",
+    "ErrorDetailsType",
     "FederationModeType",
+    "IPAddressTypeType",
+    "KxAzModeType",
+    "KxClusterStatusType",
+    "KxClusterTypeType",
+    "KxSavedownStorageTypeType",
+    "ListKxEnvironmentsPaginatorName",
+    "dnsStatusType",
+    "tgwStatusType",
     "finspaceServiceName",
     "ServiceName",
     "ResourceServiceName",
+    "PaginatorName",
     "RegionName",
 )
 
 
+AutoScalingMetricType = Literal["CPU_UTILIZATION_PERCENTAGE"]
+ChangeTypeType = Literal["DELETE", "PUT"]
+ChangesetStatusType = Literal["COMPLETED", "FAILED", "PENDING", "PROCESSING"]
 EnvironmentStatusType = Literal[
     "CREATED",
     "CREATE_REQUESTED",
     "CREATING",
     "DELETED",
     "DELETE_REQUESTED",
     "DELETING",
     "FAILED_CREATION",
     "FAILED_DELETION",
+    "FAILED_UPDATING_NETWORK",
     "RETRY_DELETION",
     "SUSPENDED",
+    "UPDATE_NETWORK_REQUESTED",
+    "UPDATING_NETWORK",
+]
+ErrorDetailsType = Literal[
+    "A user recoverable error has occurred",
+    "An internal error has occurred.",
+    "Cancelled",
+    "Missing required permission to perform this request.",
+    "One or more inputs to this request were not found.",
+    "Service limits have been exceeded.",
+    "The inputs to this request are invalid.",
+    "The system temporarily lacks sufficient resources to process the request.",
 ]
 FederationModeType = Literal["FEDERATED", "LOCAL"]
+IPAddressTypeType = Literal["IP_V4"]
+KxAzModeType = Literal["MULTI", "SINGLE"]
+KxClusterStatusType = Literal[
+    "CREATE_FAILED",
+    "CREATING",
+    "DELETED",
+    "DELETE_FAILED",
+    "DELETING",
+    "PENDING",
+    "RUNNING",
+    "UPDATING",
+]
+KxClusterTypeType = Literal["GATEWAY", "HDB", "RDB"]
+KxSavedownStorageTypeType = Literal["SDS01"]
+ListKxEnvironmentsPaginatorName = Literal["list_kx_environments"]
+dnsStatusType = Literal[
+    "FAILED_UPDATE", "NONE", "SUCCESSFULLY_UPDATED", "UPDATE_REQUESTED", "UPDATING"
+]
+tgwStatusType = Literal[
+    "FAILED_UPDATE", "NONE", "SUCCESSFULLY_UPDATED", "UPDATE_REQUESTED", "UPDATING"
+]
 finspaceServiceName = Literal["finspace"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
     "alexaforbusiness",
@@ -101,14 +151,15 @@
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
@@ -187,14 +238,15 @@
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
@@ -205,14 +257,15 @@
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
@@ -248,14 +301,15 @@
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
@@ -274,16 +328,19 @@
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
@@ -367,15 +424,17 @@
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
@@ -393,8 +452,9 @@
     "glacier",
     "iam",
     "opsworks",
     "s3",
     "sns",
     "sqs",
 ]
+PaginatorName = Literal["list_kx_environments"]
 RegionName = Literal["ca-central-1", "eu-west-1", "us-east-1", "us-east-2", "us-west-2"]
```

### Comparing `types-aiobotocore-finspace-2.5.0.post1/types_aiobotocore_finspace/literals.pyi` & `types-aiobotocore-finspace-2.5.1/types_aiobotocore_finspace/literals.pyi`

 * *Files 25% similar despite different names*

```diff
@@ -2,48 +2,98 @@
 Type annotations for finspace service literal definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_finspace/literals/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_finspace.literals import EnvironmentStatusType
+    from types_aiobotocore_finspace.literals import AutoScalingMetricType
 
-    data: EnvironmentStatusType = "CREATE_REQUESTED"
+    data: AutoScalingMetricType = "CPU_UTILIZATION_PERCENTAGE"
     ```
 """
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 __all__ = (
+    "AutoScalingMetricType",
+    "ChangeTypeType",
+    "ChangesetStatusType",
     "EnvironmentStatusType",
+    "ErrorDetailsType",
     "FederationModeType",
+    "IPAddressTypeType",
+    "KxAzModeType",
+    "KxClusterStatusType",
+    "KxClusterTypeType",
+    "KxSavedownStorageTypeType",
+    "ListKxEnvironmentsPaginatorName",
+    "dnsStatusType",
+    "tgwStatusType",
     "finspaceServiceName",
     "ServiceName",
     "ResourceServiceName",
+    "PaginatorName",
     "RegionName",
 )
 
+AutoScalingMetricType = Literal["CPU_UTILIZATION_PERCENTAGE"]
+ChangeTypeType = Literal["DELETE", "PUT"]
+ChangesetStatusType = Literal["COMPLETED", "FAILED", "PENDING", "PROCESSING"]
 EnvironmentStatusType = Literal[
     "CREATED",
     "CREATE_REQUESTED",
     "CREATING",
     "DELETED",
     "DELETE_REQUESTED",
     "DELETING",
     "FAILED_CREATION",
     "FAILED_DELETION",
+    "FAILED_UPDATING_NETWORK",
     "RETRY_DELETION",
     "SUSPENDED",
+    "UPDATE_NETWORK_REQUESTED",
+    "UPDATING_NETWORK",
+]
+ErrorDetailsType = Literal[
+    "A user recoverable error has occurred",
+    "An internal error has occurred.",
+    "Cancelled",
+    "Missing required permission to perform this request.",
+    "One or more inputs to this request were not found.",
+    "Service limits have been exceeded.",
+    "The inputs to this request are invalid.",
+    "The system temporarily lacks sufficient resources to process the request.",
 ]
 FederationModeType = Literal["FEDERATED", "LOCAL"]
+IPAddressTypeType = Literal["IP_V4"]
+KxAzModeType = Literal["MULTI", "SINGLE"]
+KxClusterStatusType = Literal[
+    "CREATE_FAILED",
+    "CREATING",
+    "DELETED",
+    "DELETE_FAILED",
+    "DELETING",
+    "PENDING",
+    "RUNNING",
+    "UPDATING",
+]
+KxClusterTypeType = Literal["GATEWAY", "HDB", "RDB"]
+KxSavedownStorageTypeType = Literal["SDS01"]
+ListKxEnvironmentsPaginatorName = Literal["list_kx_environments"]
+dnsStatusType = Literal[
+    "FAILED_UPDATE", "NONE", "SUCCESSFULLY_UPDATED", "UPDATE_REQUESTED", "UPDATING"
+]
+tgwStatusType = Literal[
+    "FAILED_UPDATE", "NONE", "SUCCESSFULLY_UPDATED", "UPDATE_REQUESTED", "UPDATING"
+]
 finspaceServiceName = Literal["finspace"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
     "alexaforbusiness",
@@ -99,14 +149,15 @@
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
@@ -185,14 +236,15 @@
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
@@ -203,14 +255,15 @@
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
@@ -246,14 +299,15 @@
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
@@ -272,16 +326,19 @@
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
@@ -365,15 +422,17 @@
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
@@ -391,8 +450,9 @@
     "glacier",
     "iam",
     "opsworks",
     "s3",
     "sns",
     "sqs",
 ]
+PaginatorName = Literal["list_kx_environments"]
 RegionName = Literal["ca-central-1", "eu-west-1", "us-east-1", "us-east-2", "us-west-2"]
```

### Comparing `types-aiobotocore-finspace-2.5.0.post1/types_aiobotocore_finspace.egg-info/SOURCES.txt` & `types-aiobotocore-finspace-2.5.1/types_aiobotocore_finspace.egg-info/SOURCES.txt`

 * *Files 14% similar despite different names*

```diff
@@ -4,14 +4,16 @@
 types_aiobotocore_finspace/__init__.py
 types_aiobotocore_finspace/__init__.pyi
 types_aiobotocore_finspace/__main__.py
 types_aiobotocore_finspace/client.py
 types_aiobotocore_finspace/client.pyi
 types_aiobotocore_finspace/literals.py
 types_aiobotocore_finspace/literals.pyi
+types_aiobotocore_finspace/paginator.py
+types_aiobotocore_finspace/paginator.pyi
 types_aiobotocore_finspace/py.typed
 types_aiobotocore_finspace/type_defs.py
 types_aiobotocore_finspace/type_defs.pyi
 types_aiobotocore_finspace/version.py
 types_aiobotocore_finspace.egg-info/PKG-INFO
 types_aiobotocore_finspace.egg-info/SOURCES.txt
 types_aiobotocore_finspace.egg-info/dependency_links.txt
```

