# Comparing `tmp/types-aiobotocore-cognito-sync-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-cognito-sync-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-cognito-sync-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:24 2023, max compression
+gzip compressed data, was "types-aiobotocore-cognito-sync-2.5.1.tar", last modified: Wed Jun 28 01:43:18 2023, max compression
```

## Comparing `types-aiobotocore-cognito-sync-2.5.0.post1.tar` & `types-aiobotocore-cognito-sync-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:24.927074 types-aiobotocore-cognito-sync-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:11:35.000000 types-aiobotocore-cognito-sync-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    13899 2023-03-11 12:26:24.923074 types-aiobotocore-cognito-sync-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    12309 2023-03-11 12:11:35.000000 types-aiobotocore-cognito-sync-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:24.927074 types-aiobotocore-cognito-sync-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2158 2023-03-11 12:11:35.000000 types-aiobotocore-cognito-sync-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:24.919074 types-aiobotocore-cognito-sync-2.5.0.post1/types_aiobotocore_cognito_sync/
--rw-r--r--   0 runner    (1001) docker     (123)      477 2023-03-11 12:11:35.000000 types-aiobotocore-cognito-sync-2.5.0.post1/types_aiobotocore_cognito_sync/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      476 2023-03-11 12:11:35.000000 types-aiobotocore-cognito-sync-2.5.0.post1/types_aiobotocore_cognito_sync/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      961 2023-03-11 12:11:35.000000 types-aiobotocore-cognito-sync-2.5.0.post1/types_aiobotocore_cognito_sync/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    15515 2023-03-11 12:11:35.000000 types-aiobotocore-cognito-sync-2.5.0.post1/types_aiobotocore_cognito_sync/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    15490 2023-03-11 12:11:35.000000 types-aiobotocore-cognito-sync-2.5.0.post1/types_aiobotocore_cognito_sync/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7938 2023-03-11 12:11:35.000000 types-aiobotocore-cognito-sync-2.5.0.post1/types_aiobotocore_cognito_sync/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7936 2023-03-11 12:11:35.000000 types-aiobotocore-cognito-sync-2.5.0.post1/types_aiobotocore_cognito_sync/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:11:35.000000 types-aiobotocore-cognito-sync-2.5.0.post1/types_aiobotocore_cognito_sync/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    12760 2023-03-11 12:11:36.000000 types-aiobotocore-cognito-sync-2.5.0.post1/types_aiobotocore_cognito_sync/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    12750 2023-03-11 12:11:36.000000 types-aiobotocore-cognito-sync-2.5.0.post1/types_aiobotocore_cognito_sync/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:11:35.000000 types-aiobotocore-cognito-sync-2.5.0.post1/types_aiobotocore_cognito_sync/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:24.923074 types-aiobotocore-cognito-sync-2.5.0.post1/types_aiobotocore_cognito_sync.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    13899 2023-03-11 12:26:24.000000 types-aiobotocore-cognito-sync-2.5.0.post1/types_aiobotocore_cognito_sync.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      819 2023-03-11 12:26:24.000000 types-aiobotocore-cognito-sync-2.5.0.post1/types_aiobotocore_cognito_sync.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:24.000000 types-aiobotocore-cognito-sync-2.5.0.post1/types_aiobotocore_cognito_sync.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:24.000000 types-aiobotocore-cognito-sync-2.5.0.post1/types_aiobotocore_cognito_sync.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:24.000000 types-aiobotocore-cognito-sync-2.5.0.post1/types_aiobotocore_cognito_sync.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       31 2023-03-11 12:26:24.000000 types-aiobotocore-cognito-sync-2.5.0.post1/types_aiobotocore_cognito_sync.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:18.010115 types-aiobotocore-cognito-sync-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:28:13.000000 types-aiobotocore-cognito-sync-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    13896 2023-06-28 01:43:18.002115 types-aiobotocore-cognito-sync-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    12312 2023-06-28 01:28:13.000000 types-aiobotocore-cognito-sync-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:18.010115 types-aiobotocore-cognito-sync-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2152 2023-06-28 01:28:12.000000 types-aiobotocore-cognito-sync-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:18.002115 types-aiobotocore-cognito-sync-2.5.1/types_aiobotocore_cognito_sync/
+-rw-r--r--   0 runner    (1001) docker     (123)      477 2023-06-28 01:28:13.000000 types-aiobotocore-cognito-sync-2.5.1/types_aiobotocore_cognito_sync/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      476 2023-06-28 01:28:13.000000 types-aiobotocore-cognito-sync-2.5.1/types_aiobotocore_cognito_sync/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      949 2023-06-28 01:28:13.000000 types-aiobotocore-cognito-sync-2.5.1/types_aiobotocore_cognito_sync/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15515 2023-06-28 01:28:13.000000 types-aiobotocore-cognito-sync-2.5.1/types_aiobotocore_cognito_sync/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15490 2023-06-28 01:28:13.000000 types-aiobotocore-cognito-sync-2.5.1/types_aiobotocore_cognito_sync/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8147 2023-06-28 01:28:13.000000 types-aiobotocore-cognito-sync-2.5.1/types_aiobotocore_cognito_sync/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8145 2023-06-28 01:28:13.000000 types-aiobotocore-cognito-sync-2.5.1/types_aiobotocore_cognito_sync/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:28:13.000000 types-aiobotocore-cognito-sync-2.5.1/types_aiobotocore_cognito_sync/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    12790 2023-06-28 01:28:13.000000 types-aiobotocore-cognito-sync-2.5.1/types_aiobotocore_cognito_sync/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12780 2023-06-28 01:28:13.000000 types-aiobotocore-cognito-sync-2.5.1/types_aiobotocore_cognito_sync/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:28:13.000000 types-aiobotocore-cognito-sync-2.5.1/types_aiobotocore_cognito_sync/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:18.002115 types-aiobotocore-cognito-sync-2.5.1/types_aiobotocore_cognito_sync.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    13896 2023-06-28 01:43:17.000000 types-aiobotocore-cognito-sync-2.5.1/types_aiobotocore_cognito_sync.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      819 2023-06-28 01:43:17.000000 types-aiobotocore-cognito-sync-2.5.1/types_aiobotocore_cognito_sync.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:17.000000 types-aiobotocore-cognito-sync-2.5.1/types_aiobotocore_cognito_sync.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:17.000000 types-aiobotocore-cognito-sync-2.5.1/types_aiobotocore_cognito_sync.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:17.000000 types-aiobotocore-cognito-sync-2.5.1/types_aiobotocore_cognito_sync.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       31 2023-06-28 01:43:17.000000 types-aiobotocore-cognito-sync-2.5.1/types_aiobotocore_cognito_sync.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-cognito-sync-2.5.0.post1/LICENSE` & `types-aiobotocore-cognito-sync-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-cognito-sync-2.5.0.post1/PKG-INFO` & `types-aiobotocore-cognito-sync-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-cognito-sync
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CognitoSync 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CognitoSync 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cognito_sync/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-cognito-sync"></a>
 
 # types-aiobotocore-cognito-sync
 
 [![PyPI - types-aiobotocore-cognito-sync](https://img.shields.io/pypi/v/types-aiobotocore-cognito-sync.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cognito-sync)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-cognito-sync.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cognito-sync)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cognito_sync/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-cognito-sync?color=blue)](https://pypistats.org/packages/types-aiobotocore-cognito-sync)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CognitoSync 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-sync.html#CognitoSync)
+[aiobotocore.CognitoSync 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-sync.html#CognitoSync)
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
 [types-aiobotocore-cognito-sync docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cognito_sync/).
 
 See how it helps to find and fix potential bugs:
 
@@ -294,41 +294,41 @@
 
 `types_aiobotocore_cognito_sync.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_cognito_sync.type_defs import (
     BulkPublishRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    BulkPublishResponseTypeDef,
     CognitoStreamsTypeDef,
     DatasetTypeDef,
     DeleteDatasetRequestRequestTypeDef,
     DescribeDatasetRequestRequestTypeDef,
     DescribeIdentityPoolUsageRequestRequestTypeDef,
     IdentityPoolUsageTypeDef,
     DescribeIdentityUsageRequestRequestTypeDef,
     IdentityUsageTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetBulkPublishDetailsRequestRequestTypeDef,
+    GetBulkPublishDetailsResponseTypeDef,
     GetCognitoEventsRequestRequestTypeDef,
+    GetCognitoEventsResponseTypeDef,
     GetIdentityPoolConfigurationRequestRequestTypeDef,
     PushSyncTypeDef,
     ListDatasetsRequestRequestTypeDef,
     ListIdentityPoolUsageRequestRequestTypeDef,
     ListRecordsRequestRequestTypeDef,
     RecordTypeDef,
     RecordPatchTypeDef,
     RegisterDeviceRequestRequestTypeDef,
+    RegisterDeviceResponseTypeDef,
+    ResponseMetadataTypeDef,
     SetCognitoEventsRequestRequestTypeDef,
     SubscribeToDatasetRequestRequestTypeDef,
     UnsubscribeFromDatasetRequestRequestTypeDef,
-    BulkPublishResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetBulkPublishDetailsResponseTypeDef,
-    GetCognitoEventsResponseTypeDef,
-    RegisterDeviceResponseTypeDef,
     DeleteDatasetResponseTypeDef,
     DescribeDatasetResponseTypeDef,
     ListDatasetsResponseTypeDef,
     DescribeIdentityPoolUsageResponseTypeDef,
     ListIdentityPoolUsageResponseTypeDef,
     DescribeIdentityUsageResponseTypeDef,
     GetIdentityPoolConfigurationResponseTypeDef,
@@ -347,43 +347,43 @@
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

### Comparing `types-aiobotocore-cognito-sync-2.5.0.post1/README.md` & `types-aiobotocore-cognito-sync-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-cognito-sync"></a>
 
 # types-aiobotocore-cognito-sync
 
 [![PyPI - types-aiobotocore-cognito-sync](https://img.shields.io/pypi/v/types-aiobotocore-cognito-sync.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cognito-sync)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-cognito-sync.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cognito-sync)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cognito_sync/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-cognito-sync?color=blue)](https://pypistats.org/packages/types-aiobotocore-cognito-sync)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CognitoSync 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-sync.html#CognitoSync)
+[aiobotocore.CognitoSync 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-sync.html#CognitoSync)
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
 [types-aiobotocore-cognito-sync docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cognito_sync/).
 
 See how it helps to find and fix potential bugs:
 
@@ -261,41 +261,41 @@
 
 `types_aiobotocore_cognito_sync.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_cognito_sync.type_defs import (
     BulkPublishRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    BulkPublishResponseTypeDef,
     CognitoStreamsTypeDef,
     DatasetTypeDef,
     DeleteDatasetRequestRequestTypeDef,
     DescribeDatasetRequestRequestTypeDef,
     DescribeIdentityPoolUsageRequestRequestTypeDef,
     IdentityPoolUsageTypeDef,
     DescribeIdentityUsageRequestRequestTypeDef,
     IdentityUsageTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetBulkPublishDetailsRequestRequestTypeDef,
+    GetBulkPublishDetailsResponseTypeDef,
     GetCognitoEventsRequestRequestTypeDef,
+    GetCognitoEventsResponseTypeDef,
     GetIdentityPoolConfigurationRequestRequestTypeDef,
     PushSyncTypeDef,
     ListDatasetsRequestRequestTypeDef,
     ListIdentityPoolUsageRequestRequestTypeDef,
     ListRecordsRequestRequestTypeDef,
     RecordTypeDef,
     RecordPatchTypeDef,
     RegisterDeviceRequestRequestTypeDef,
+    RegisterDeviceResponseTypeDef,
+    ResponseMetadataTypeDef,
     SetCognitoEventsRequestRequestTypeDef,
     SubscribeToDatasetRequestRequestTypeDef,
     UnsubscribeFromDatasetRequestRequestTypeDef,
-    BulkPublishResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetBulkPublishDetailsResponseTypeDef,
-    GetCognitoEventsResponseTypeDef,
-    RegisterDeviceResponseTypeDef,
     DeleteDatasetResponseTypeDef,
     DescribeDatasetResponseTypeDef,
     ListDatasetsResponseTypeDef,
     DescribeIdentityPoolUsageResponseTypeDef,
     ListIdentityPoolUsageResponseTypeDef,
     DescribeIdentityUsageResponseTypeDef,
     GetIdentityPoolConfigurationResponseTypeDef,
@@ -314,43 +314,43 @@
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

### Comparing `types-aiobotocore-cognito-sync-2.5.0.post1/setup.py` & `types-aiobotocore-cognito-sync-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-cognito-sync.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-cognito-sync",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_cognito_sync"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.CognitoSync 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.CognitoSync 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cognito_sync/"
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

### Comparing `types-aiobotocore-cognito-sync-2.5.0.post1/types_aiobotocore_cognito_sync/__main__.py` & `types-aiobotocore-cognito-sync-2.5.1/types_aiobotocore_cognito_sync/__main__.py`

 * *Files 24% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.CognitoSync 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.CognitoSync 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cognito_sync//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-sync.html#CognitoSync\nOther"
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

### Comparing `types-aiobotocore-cognito-sync-2.5.0.post1/types_aiobotocore_cognito_sync/client.py` & `types-aiobotocore-cognito-sync-2.5.1/types_aiobotocore_cognito_sync/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cognito-sync-2.5.0.post1/types_aiobotocore_cognito_sync/client.pyi` & `types-aiobotocore-cognito-sync-2.5.1/types_aiobotocore_cognito_sync/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-cognito-sync-2.5.0.post1/types_aiobotocore_cognito_sync/literals.py` & `types-aiobotocore-cognito-sync-2.5.1/types_aiobotocore_cognito_sync/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -94,14 +94,15 @@
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
@@ -180,14 +181,15 @@
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
@@ -198,14 +200,15 @@
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
@@ -241,14 +244,15 @@
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
@@ -267,16 +271,19 @@
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
@@ -360,15 +367,17 @@
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

### Comparing `types-aiobotocore-cognito-sync-2.5.0.post1/types_aiobotocore_cognito_sync/literals.pyi` & `types-aiobotocore-cognito-sync-2.5.1/types_aiobotocore_cognito_sync/literals.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -92,14 +92,15 @@
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
@@ -178,14 +179,15 @@
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
@@ -196,14 +198,15 @@
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
@@ -239,14 +242,15 @@
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
@@ -265,16 +269,19 @@
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
@@ -358,15 +365,17 @@
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

### Comparing `types-aiobotocore-cognito-sync-2.5.0.post1/types_aiobotocore_cognito_sync/type_defs.py` & `types-aiobotocore-cognito-sync-2.5.1/types_aiobotocore_cognito_sync/type_defs.pyi`

 * *Files 7% similar despite different names*

```diff
@@ -18,44 +18,43 @@
 from .literals import BulkPublishStatusType, OperationType, PlatformType, StreamingStatusType
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "BulkPublishRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "BulkPublishResponseTypeDef",
     "CognitoStreamsTypeDef",
     "DatasetTypeDef",
     "DeleteDatasetRequestRequestTypeDef",
     "DescribeDatasetRequestRequestTypeDef",
     "DescribeIdentityPoolUsageRequestRequestTypeDef",
     "IdentityPoolUsageTypeDef",
     "DescribeIdentityUsageRequestRequestTypeDef",
     "IdentityUsageTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetBulkPublishDetailsRequestRequestTypeDef",
+    "GetBulkPublishDetailsResponseTypeDef",
     "GetCognitoEventsRequestRequestTypeDef",
+    "GetCognitoEventsResponseTypeDef",
     "GetIdentityPoolConfigurationRequestRequestTypeDef",
     "PushSyncTypeDef",
     "ListDatasetsRequestRequestTypeDef",
     "ListIdentityPoolUsageRequestRequestTypeDef",
     "ListRecordsRequestRequestTypeDef",
     "RecordTypeDef",
     "RecordPatchTypeDef",
     "RegisterDeviceRequestRequestTypeDef",
+    "RegisterDeviceResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "SetCognitoEventsRequestRequestTypeDef",
     "SubscribeToDatasetRequestRequestTypeDef",
     "UnsubscribeFromDatasetRequestRequestTypeDef",
-    "BulkPublishResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetBulkPublishDetailsResponseTypeDef",
-    "GetCognitoEventsResponseTypeDef",
-    "RegisterDeviceResponseTypeDef",
     "DeleteDatasetResponseTypeDef",
     "DescribeDatasetResponseTypeDef",
     "ListDatasetsResponseTypeDef",
     "DescribeIdentityPoolUsageResponseTypeDef",
     "ListIdentityPoolUsageResponseTypeDef",
     "DescribeIdentityUsageResponseTypeDef",
     "GetIdentityPoolConfigurationResponseTypeDef",
@@ -69,22 +68,19 @@
 BulkPublishRequestRequestTypeDef = TypedDict(
     "BulkPublishRequestRequestTypeDef",
     {
         "IdentityPoolId": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+BulkPublishResponseTypeDef = TypedDict(
+    "BulkPublishResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "IdentityPoolId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CognitoStreamsTypeDef = TypedDict(
     "CognitoStreamsTypeDef",
     {
         "StreamName": str,
@@ -160,28 +156,55 @@
         "LastModifiedDate": datetime,
         "DatasetCount": int,
         "DataStorage": int,
     },
     total=False,
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetBulkPublishDetailsRequestRequestTypeDef = TypedDict(
     "GetBulkPublishDetailsRequestRequestTypeDef",
     {
         "IdentityPoolId": str,
     },
 )
 
+GetBulkPublishDetailsResponseTypeDef = TypedDict(
+    "GetBulkPublishDetailsResponseTypeDef",
+    {
+        "IdentityPoolId": str,
+        "BulkPublishStartTime": datetime,
+        "BulkPublishCompleteTime": datetime,
+        "BulkPublishStatus": BulkPublishStatusType,
+        "FailureMessage": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetCognitoEventsRequestRequestTypeDef = TypedDict(
     "GetCognitoEventsRequestRequestTypeDef",
     {
         "IdentityPoolId": str,
     },
 )
 
+GetCognitoEventsResponseTypeDef = TypedDict(
+    "GetCognitoEventsResponseTypeDef",
+    {
+        "Events": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetIdentityPoolConfigurationRequestRequestTypeDef = TypedDict(
     "GetIdentityPoolConfigurationRequestRequestTypeDef",
     {
         "IdentityPoolId": str,
     },
 )
 
@@ -206,21 +229,19 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-
 class ListDatasetsRequestRequestTypeDef(
     _RequiredListDatasetsRequestRequestTypeDef, _OptionalListDatasetsRequestRequestTypeDef
 ):
     pass
 
-
 ListIdentityPoolUsageRequestRequestTypeDef = TypedDict(
     "ListIdentityPoolUsageRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
@@ -241,21 +262,19 @@
         "NextToken": str,
         "MaxResults": int,
         "SyncSessionToken": str,
     },
     total=False,
 )
 
-
 class ListRecordsRequestRequestTypeDef(
     _RequiredListRecordsRequestRequestTypeDef, _OptionalListRecordsRequestRequestTypeDef
 ):
     pass
 
-
 RecordTypeDef = TypedDict(
     "RecordTypeDef",
     {
         "Key": str,
         "Value": str,
         "SyncCount": int,
         "LastModifiedDate": datetime,
@@ -278,29 +297,46 @@
     {
         "Value": str,
         "DeviceLastModifiedDate": Union[datetime, str],
     },
     total=False,
 )
 
-
 class RecordPatchTypeDef(_RequiredRecordPatchTypeDef, _OptionalRecordPatchTypeDef):
     pass
 
-
 RegisterDeviceRequestRequestTypeDef = TypedDict(
     "RegisterDeviceRequestRequestTypeDef",
     {
         "IdentityPoolId": str,
         "IdentityId": str,
         "Platform": PlatformType,
         "Token": str,
     },
 )
 
+RegisterDeviceResponseTypeDef = TypedDict(
+    "RegisterDeviceResponseTypeDef",
+    {
+        "DeviceId": str,
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
 SetCognitoEventsRequestRequestTypeDef = TypedDict(
     "SetCognitoEventsRequestRequestTypeDef",
     {
         "IdentityPoolId": str,
         "Events": Mapping[str, str],
     },
 )
@@ -321,117 +357,74 @@
         "IdentityPoolId": str,
         "IdentityId": str,
         "DatasetName": str,
         "DeviceId": str,
     },
 )
 
-BulkPublishResponseTypeDef = TypedDict(
-    "BulkPublishResponseTypeDef",
-    {
-        "IdentityPoolId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetBulkPublishDetailsResponseTypeDef = TypedDict(
-    "GetBulkPublishDetailsResponseTypeDef",
-    {
-        "IdentityPoolId": str,
-        "BulkPublishStartTime": datetime,
-        "BulkPublishCompleteTime": datetime,
-        "BulkPublishStatus": BulkPublishStatusType,
-        "FailureMessage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetCognitoEventsResponseTypeDef = TypedDict(
-    "GetCognitoEventsResponseTypeDef",
-    {
-        "Events": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RegisterDeviceResponseTypeDef = TypedDict(
-    "RegisterDeviceResponseTypeDef",
-    {
-        "DeviceId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 DeleteDatasetResponseTypeDef = TypedDict(
     "DeleteDatasetResponseTypeDef",
     {
         "Dataset": DatasetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDatasetResponseTypeDef = TypedDict(
     "DescribeDatasetResponseTypeDef",
     {
         "Dataset": DatasetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDatasetsResponseTypeDef = TypedDict(
     "ListDatasetsResponseTypeDef",
     {
         "Datasets": List[DatasetTypeDef],
         "Count": int,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeIdentityPoolUsageResponseTypeDef = TypedDict(
     "DescribeIdentityPoolUsageResponseTypeDef",
     {
         "IdentityPoolUsage": IdentityPoolUsageTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListIdentityPoolUsageResponseTypeDef = TypedDict(
     "ListIdentityPoolUsageResponseTypeDef",
     {
         "IdentityPoolUsages": List[IdentityPoolUsageTypeDef],
         "MaxResults": int,
         "Count": int,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeIdentityUsageResponseTypeDef = TypedDict(
     "DescribeIdentityUsageResponseTypeDef",
     {
         "IdentityUsage": IdentityUsageTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetIdentityPoolConfigurationResponseTypeDef = TypedDict(
     "GetIdentityPoolConfigurationResponseTypeDef",
     {
         "IdentityPoolId": str,
         "PushSync": PushSyncTypeDef,
         "CognitoStreams": CognitoStreamsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSetIdentityPoolConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredSetIdentityPoolConfigurationRequestRequestTypeDef",
     {
         "IdentityPoolId": str,
@@ -442,29 +435,27 @@
     {
         "PushSync": PushSyncTypeDef,
         "CognitoStreams": CognitoStreamsTypeDef,
     },
     total=False,
 )
 
-
 class SetIdentityPoolConfigurationRequestRequestTypeDef(
     _RequiredSetIdentityPoolConfigurationRequestRequestTypeDef,
     _OptionalSetIdentityPoolConfigurationRequestRequestTypeDef,
 ):
     pass
 
-
 SetIdentityPoolConfigurationResponseTypeDef = TypedDict(
     "SetIdentityPoolConfigurationResponseTypeDef",
     {
         "IdentityPoolId": str,
         "PushSync": PushSyncTypeDef,
         "CognitoStreams": CognitoStreamsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRecordsResponseTypeDef = TypedDict(
     "ListRecordsResponseTypeDef",
     {
         "Records": List[RecordTypeDef],
@@ -472,23 +463,23 @@
         "Count": int,
         "DatasetSyncCount": int,
         "LastModifiedBy": str,
         "MergedDatasetNames": List[str],
         "DatasetExists": bool,
         "DatasetDeletedAfterRequestedSyncCount": bool,
         "SyncSessionToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateRecordsResponseTypeDef = TypedDict(
     "UpdateRecordsResponseTypeDef",
     {
         "Records": List[RecordTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateRecordsRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateRecordsRequestRequestTypeDef",
     {
         "IdentityPoolId": str,
@@ -503,12 +494,11 @@
         "DeviceId": str,
         "RecordPatches": Sequence[RecordPatchTypeDef],
         "ClientContext": str,
     },
     total=False,
 )
 
-
 class UpdateRecordsRequestRequestTypeDef(
     _RequiredUpdateRecordsRequestRequestTypeDef, _OptionalUpdateRecordsRequestRequestTypeDef
 ):
     pass
```

### Comparing `types-aiobotocore-cognito-sync-2.5.0.post1/types_aiobotocore_cognito_sync/type_defs.pyi` & `types-aiobotocore-cognito-sync-2.5.1/types_aiobotocore_cognito_sync/type_defs.py`

 * *Files 9% similar despite different names*

```diff
@@ -18,43 +18,44 @@
 from .literals import BulkPublishStatusType, OperationType, PlatformType, StreamingStatusType
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "BulkPublishRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "BulkPublishResponseTypeDef",
     "CognitoStreamsTypeDef",
     "DatasetTypeDef",
     "DeleteDatasetRequestRequestTypeDef",
     "DescribeDatasetRequestRequestTypeDef",
     "DescribeIdentityPoolUsageRequestRequestTypeDef",
     "IdentityPoolUsageTypeDef",
     "DescribeIdentityUsageRequestRequestTypeDef",
     "IdentityUsageTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetBulkPublishDetailsRequestRequestTypeDef",
+    "GetBulkPublishDetailsResponseTypeDef",
     "GetCognitoEventsRequestRequestTypeDef",
+    "GetCognitoEventsResponseTypeDef",
     "GetIdentityPoolConfigurationRequestRequestTypeDef",
     "PushSyncTypeDef",
     "ListDatasetsRequestRequestTypeDef",
     "ListIdentityPoolUsageRequestRequestTypeDef",
     "ListRecordsRequestRequestTypeDef",
     "RecordTypeDef",
     "RecordPatchTypeDef",
     "RegisterDeviceRequestRequestTypeDef",
+    "RegisterDeviceResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "SetCognitoEventsRequestRequestTypeDef",
     "SubscribeToDatasetRequestRequestTypeDef",
     "UnsubscribeFromDatasetRequestRequestTypeDef",
-    "BulkPublishResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetBulkPublishDetailsResponseTypeDef",
-    "GetCognitoEventsResponseTypeDef",
-    "RegisterDeviceResponseTypeDef",
     "DeleteDatasetResponseTypeDef",
     "DescribeDatasetResponseTypeDef",
     "ListDatasetsResponseTypeDef",
     "DescribeIdentityPoolUsageResponseTypeDef",
     "ListIdentityPoolUsageResponseTypeDef",
     "DescribeIdentityUsageResponseTypeDef",
     "GetIdentityPoolConfigurationResponseTypeDef",
@@ -68,22 +69,19 @@
 BulkPublishRequestRequestTypeDef = TypedDict(
     "BulkPublishRequestRequestTypeDef",
     {
         "IdentityPoolId": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+BulkPublishResponseTypeDef = TypedDict(
+    "BulkPublishResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "IdentityPoolId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CognitoStreamsTypeDef = TypedDict(
     "CognitoStreamsTypeDef",
     {
         "StreamName": str,
@@ -159,28 +157,55 @@
         "LastModifiedDate": datetime,
         "DatasetCount": int,
         "DataStorage": int,
     },
     total=False,
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetBulkPublishDetailsRequestRequestTypeDef = TypedDict(
     "GetBulkPublishDetailsRequestRequestTypeDef",
     {
         "IdentityPoolId": str,
     },
 )
 
+GetBulkPublishDetailsResponseTypeDef = TypedDict(
+    "GetBulkPublishDetailsResponseTypeDef",
+    {
+        "IdentityPoolId": str,
+        "BulkPublishStartTime": datetime,
+        "BulkPublishCompleteTime": datetime,
+        "BulkPublishStatus": BulkPublishStatusType,
+        "FailureMessage": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetCognitoEventsRequestRequestTypeDef = TypedDict(
     "GetCognitoEventsRequestRequestTypeDef",
     {
         "IdentityPoolId": str,
     },
 )
 
+GetCognitoEventsResponseTypeDef = TypedDict(
+    "GetCognitoEventsResponseTypeDef",
+    {
+        "Events": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetIdentityPoolConfigurationRequestRequestTypeDef = TypedDict(
     "GetIdentityPoolConfigurationRequestRequestTypeDef",
     {
         "IdentityPoolId": str,
     },
 )
 
@@ -205,19 +230,21 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+
 class ListDatasetsRequestRequestTypeDef(
     _RequiredListDatasetsRequestRequestTypeDef, _OptionalListDatasetsRequestRequestTypeDef
 ):
     pass
 
+
 ListIdentityPoolUsageRequestRequestTypeDef = TypedDict(
     "ListIdentityPoolUsageRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
@@ -238,19 +265,21 @@
         "NextToken": str,
         "MaxResults": int,
         "SyncSessionToken": str,
     },
     total=False,
 )
 
+
 class ListRecordsRequestRequestTypeDef(
     _RequiredListRecordsRequestRequestTypeDef, _OptionalListRecordsRequestRequestTypeDef
 ):
     pass
 
+
 RecordTypeDef = TypedDict(
     "RecordTypeDef",
     {
         "Key": str,
         "Value": str,
         "SyncCount": int,
         "LastModifiedDate": datetime,
@@ -273,27 +302,48 @@
     {
         "Value": str,
         "DeviceLastModifiedDate": Union[datetime, str],
     },
     total=False,
 )
 
+
 class RecordPatchTypeDef(_RequiredRecordPatchTypeDef, _OptionalRecordPatchTypeDef):
     pass
 
+
 RegisterDeviceRequestRequestTypeDef = TypedDict(
     "RegisterDeviceRequestRequestTypeDef",
     {
         "IdentityPoolId": str,
         "IdentityId": str,
         "Platform": PlatformType,
         "Token": str,
     },
 )
 
+RegisterDeviceResponseTypeDef = TypedDict(
+    "RegisterDeviceResponseTypeDef",
+    {
+        "DeviceId": str,
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
 SetCognitoEventsRequestRequestTypeDef = TypedDict(
     "SetCognitoEventsRequestRequestTypeDef",
     {
         "IdentityPoolId": str,
         "Events": Mapping[str, str],
     },
 )
@@ -314,117 +364,74 @@
         "IdentityPoolId": str,
         "IdentityId": str,
         "DatasetName": str,
         "DeviceId": str,
     },
 )
 
-BulkPublishResponseTypeDef = TypedDict(
-    "BulkPublishResponseTypeDef",
-    {
-        "IdentityPoolId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetBulkPublishDetailsResponseTypeDef = TypedDict(
-    "GetBulkPublishDetailsResponseTypeDef",
-    {
-        "IdentityPoolId": str,
-        "BulkPublishStartTime": datetime,
-        "BulkPublishCompleteTime": datetime,
-        "BulkPublishStatus": BulkPublishStatusType,
-        "FailureMessage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetCognitoEventsResponseTypeDef = TypedDict(
-    "GetCognitoEventsResponseTypeDef",
-    {
-        "Events": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RegisterDeviceResponseTypeDef = TypedDict(
-    "RegisterDeviceResponseTypeDef",
-    {
-        "DeviceId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 DeleteDatasetResponseTypeDef = TypedDict(
     "DeleteDatasetResponseTypeDef",
     {
         "Dataset": DatasetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDatasetResponseTypeDef = TypedDict(
     "DescribeDatasetResponseTypeDef",
     {
         "Dataset": DatasetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDatasetsResponseTypeDef = TypedDict(
     "ListDatasetsResponseTypeDef",
     {
         "Datasets": List[DatasetTypeDef],
         "Count": int,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeIdentityPoolUsageResponseTypeDef = TypedDict(
     "DescribeIdentityPoolUsageResponseTypeDef",
     {
         "IdentityPoolUsage": IdentityPoolUsageTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListIdentityPoolUsageResponseTypeDef = TypedDict(
     "ListIdentityPoolUsageResponseTypeDef",
     {
         "IdentityPoolUsages": List[IdentityPoolUsageTypeDef],
         "MaxResults": int,
         "Count": int,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeIdentityUsageResponseTypeDef = TypedDict(
     "DescribeIdentityUsageResponseTypeDef",
     {
         "IdentityUsage": IdentityUsageTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetIdentityPoolConfigurationResponseTypeDef = TypedDict(
     "GetIdentityPoolConfigurationResponseTypeDef",
     {
         "IdentityPoolId": str,
         "PushSync": PushSyncTypeDef,
         "CognitoStreams": CognitoStreamsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSetIdentityPoolConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredSetIdentityPoolConfigurationRequestRequestTypeDef",
     {
         "IdentityPoolId": str,
@@ -435,27 +442,29 @@
     {
         "PushSync": PushSyncTypeDef,
         "CognitoStreams": CognitoStreamsTypeDef,
     },
     total=False,
 )
 
+
 class SetIdentityPoolConfigurationRequestRequestTypeDef(
     _RequiredSetIdentityPoolConfigurationRequestRequestTypeDef,
     _OptionalSetIdentityPoolConfigurationRequestRequestTypeDef,
 ):
     pass
 
+
 SetIdentityPoolConfigurationResponseTypeDef = TypedDict(
     "SetIdentityPoolConfigurationResponseTypeDef",
     {
         "IdentityPoolId": str,
         "PushSync": PushSyncTypeDef,
         "CognitoStreams": CognitoStreamsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRecordsResponseTypeDef = TypedDict(
     "ListRecordsResponseTypeDef",
     {
         "Records": List[RecordTypeDef],
@@ -463,23 +472,23 @@
         "Count": int,
         "DatasetSyncCount": int,
         "LastModifiedBy": str,
         "MergedDatasetNames": List[str],
         "DatasetExists": bool,
         "DatasetDeletedAfterRequestedSyncCount": bool,
         "SyncSessionToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateRecordsResponseTypeDef = TypedDict(
     "UpdateRecordsResponseTypeDef",
     {
         "Records": List[RecordTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateRecordsRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateRecordsRequestRequestTypeDef",
     {
         "IdentityPoolId": str,
@@ -494,11 +503,12 @@
         "DeviceId": str,
         "RecordPatches": Sequence[RecordPatchTypeDef],
         "ClientContext": str,
     },
     total=False,
 )
 
+
 class UpdateRecordsRequestRequestTypeDef(
     _RequiredUpdateRecordsRequestRequestTypeDef, _OptionalUpdateRecordsRequestRequestTypeDef
 ):
     pass
```

### Comparing `types-aiobotocore-cognito-sync-2.5.0.post1/types_aiobotocore_cognito_sync.egg-info/PKG-INFO` & `types-aiobotocore-cognito-sync-2.5.1/types_aiobotocore_cognito_sync.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-cognito-sync
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CognitoSync 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CognitoSync 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cognito_sync/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-cognito-sync"></a>
 
 # types-aiobotocore-cognito-sync
 
 [![PyPI - types-aiobotocore-cognito-sync](https://img.shields.io/pypi/v/types-aiobotocore-cognito-sync.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cognito-sync)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-cognito-sync.svg?color=blue)](https://pypi.org/project/types-aiobotocore-cognito-sync)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cognito_sync/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-cognito-sync?color=blue)](https://pypistats.org/packages/types-aiobotocore-cognito-sync)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CognitoSync 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-sync.html#CognitoSync)
+[aiobotocore.CognitoSync 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/cognito-sync.html#CognitoSync)
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
 [types-aiobotocore-cognito-sync docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cognito_sync/).
 
 See how it helps to find and fix potential bugs:
 
@@ -294,41 +294,41 @@
 
 `types_aiobotocore_cognito_sync.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_cognito_sync.type_defs import (
     BulkPublishRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    BulkPublishResponseTypeDef,
     CognitoStreamsTypeDef,
     DatasetTypeDef,
     DeleteDatasetRequestRequestTypeDef,
     DescribeDatasetRequestRequestTypeDef,
     DescribeIdentityPoolUsageRequestRequestTypeDef,
     IdentityPoolUsageTypeDef,
     DescribeIdentityUsageRequestRequestTypeDef,
     IdentityUsageTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetBulkPublishDetailsRequestRequestTypeDef,
+    GetBulkPublishDetailsResponseTypeDef,
     GetCognitoEventsRequestRequestTypeDef,
+    GetCognitoEventsResponseTypeDef,
     GetIdentityPoolConfigurationRequestRequestTypeDef,
     PushSyncTypeDef,
     ListDatasetsRequestRequestTypeDef,
     ListIdentityPoolUsageRequestRequestTypeDef,
     ListRecordsRequestRequestTypeDef,
     RecordTypeDef,
     RecordPatchTypeDef,
     RegisterDeviceRequestRequestTypeDef,
+    RegisterDeviceResponseTypeDef,
+    ResponseMetadataTypeDef,
     SetCognitoEventsRequestRequestTypeDef,
     SubscribeToDatasetRequestRequestTypeDef,
     UnsubscribeFromDatasetRequestRequestTypeDef,
-    BulkPublishResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetBulkPublishDetailsResponseTypeDef,
-    GetCognitoEventsResponseTypeDef,
-    RegisterDeviceResponseTypeDef,
     DeleteDatasetResponseTypeDef,
     DescribeDatasetResponseTypeDef,
     ListDatasetsResponseTypeDef,
     DescribeIdentityPoolUsageResponseTypeDef,
     ListIdentityPoolUsageResponseTypeDef,
     DescribeIdentityUsageResponseTypeDef,
     GetIdentityPoolConfigurationResponseTypeDef,
@@ -347,43 +347,43 @@
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

### Comparing `types-aiobotocore-cognito-sync-2.5.0.post1/types_aiobotocore_cognito_sync.egg-info/SOURCES.txt` & `types-aiobotocore-cognito-sync-2.5.1/types_aiobotocore_cognito_sync.egg-info/SOURCES.txt`

 * *Files identical despite different names*

