# Comparing `tmp/types-aiobotocore-secretsmanager-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-secretsmanager-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-secretsmanager-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:18 2023, max compression
+gzip compressed data, was "types-aiobotocore-secretsmanager-2.5.1.tar", last modified: Wed Jun 28 01:44:09 2023, max compression
```

## Comparing `types-aiobotocore-secretsmanager-2.5.0.post1.tar` & `types-aiobotocore-secretsmanager-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:18.387608 types-aiobotocore-secretsmanager-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:23:41.000000 types-aiobotocore-secretsmanager-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    15348 2023-03-11 12:27:18.387608 types-aiobotocore-secretsmanager-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13749 2023-03-11 12:23:41.000000 types-aiobotocore-secretsmanager-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:18.387608 types-aiobotocore-secretsmanager-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2173 2023-03-11 12:23:41.000000 types-aiobotocore-secretsmanager-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:18.383608 types-aiobotocore-secretsmanager-2.5.0.post1/types_aiobotocore_secretsmanager/
--rw-r--r--   0 runner    (1001) docker     (123)      685 2023-03-11 12:23:41.000000 types-aiobotocore-secretsmanager-2.5.0.post1/types_aiobotocore_secretsmanager/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      684 2023-03-11 12:23:41.000000 types-aiobotocore-secretsmanager-2.5.0.post1/types_aiobotocore_secretsmanager/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      971 2023-03-11 12:23:41.000000 types-aiobotocore-secretsmanager-2.5.0.post1/types_aiobotocore_secretsmanager/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    20417 2023-03-11 12:23:41.000000 types-aiobotocore-secretsmanager-2.5.0.post1/types_aiobotocore_secretsmanager/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    20385 2023-03-11 12:23:41.000000 types-aiobotocore-secretsmanager-2.5.0.post1/types_aiobotocore_secretsmanager/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8372 2023-03-11 12:23:42.000000 types-aiobotocore-secretsmanager-2.5.0.post1/types_aiobotocore_secretsmanager/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8370 2023-03-11 12:23:41.000000 types-aiobotocore-secretsmanager-2.5.0.post1/types_aiobotocore_secretsmanager/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     2371 2023-03-11 12:23:41.000000 types-aiobotocore-secretsmanager-2.5.0.post1/types_aiobotocore_secretsmanager/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     2367 2023-03-11 12:23:41.000000 types-aiobotocore-secretsmanager-2.5.0.post1/types_aiobotocore_secretsmanager/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:23:41.000000 types-aiobotocore-secretsmanager-2.5.0.post1/types_aiobotocore_secretsmanager/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    19620 2023-03-11 12:23:42.000000 types-aiobotocore-secretsmanager-2.5.0.post1/types_aiobotocore_secretsmanager/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    19597 2023-03-11 12:23:42.000000 types-aiobotocore-secretsmanager-2.5.0.post1/types_aiobotocore_secretsmanager/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:23:41.000000 types-aiobotocore-secretsmanager-2.5.0.post1/types_aiobotocore_secretsmanager/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:18.387608 types-aiobotocore-secretsmanager-2.5.0.post1/types_aiobotocore_secretsmanager.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    15348 2023-03-11 12:27:18.000000 types-aiobotocore-secretsmanager-2.5.0.post1/types_aiobotocore_secretsmanager.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      946 2023-03-11 12:27:18.000000 types-aiobotocore-secretsmanager-2.5.0.post1/types_aiobotocore_secretsmanager.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:18.000000 types-aiobotocore-secretsmanager-2.5.0.post1/types_aiobotocore_secretsmanager.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:18.000000 types-aiobotocore-secretsmanager-2.5.0.post1/types_aiobotocore_secretsmanager.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:18.000000 types-aiobotocore-secretsmanager-2.5.0.post1/types_aiobotocore_secretsmanager.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       33 2023-03-11 12:27:18.000000 types-aiobotocore-secretsmanager-2.5.0.post1/types_aiobotocore_secretsmanager.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:09.510212 types-aiobotocore-secretsmanager-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:40:25.000000 types-aiobotocore-secretsmanager-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    15347 2023-06-28 01:44:09.506212 types-aiobotocore-secretsmanager-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13754 2023-06-28 01:40:25.000000 types-aiobotocore-secretsmanager-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:09.510212 types-aiobotocore-secretsmanager-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2167 2023-06-28 01:40:25.000000 types-aiobotocore-secretsmanager-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:09.494212 types-aiobotocore-secretsmanager-2.5.1/types_aiobotocore_secretsmanager/
+-rw-r--r--   0 runner    (1001) docker     (123)      685 2023-06-28 01:40:25.000000 types-aiobotocore-secretsmanager-2.5.1/types_aiobotocore_secretsmanager/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      684 2023-06-28 01:40:25.000000 types-aiobotocore-secretsmanager-2.5.1/types_aiobotocore_secretsmanager/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      959 2023-06-28 01:40:25.000000 types-aiobotocore-secretsmanager-2.5.1/types_aiobotocore_secretsmanager/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20417 2023-06-28 01:40:25.000000 types-aiobotocore-secretsmanager-2.5.1/types_aiobotocore_secretsmanager/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20385 2023-06-28 01:40:25.000000 types-aiobotocore-secretsmanager-2.5.1/types_aiobotocore_secretsmanager/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8581 2023-06-28 01:40:28.000000 types-aiobotocore-secretsmanager-2.5.1/types_aiobotocore_secretsmanager/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8579 2023-06-28 01:40:27.000000 types-aiobotocore-secretsmanager-2.5.1/types_aiobotocore_secretsmanager/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     2253 2023-06-28 01:40:25.000000 types-aiobotocore-secretsmanager-2.5.1/types_aiobotocore_secretsmanager/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2250 2023-06-28 01:40:25.000000 types-aiobotocore-secretsmanager-2.5.1/types_aiobotocore_secretsmanager/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:40:25.000000 types-aiobotocore-secretsmanager-2.5.1/types_aiobotocore_secretsmanager/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    19664 2023-06-28 01:40:28.000000 types-aiobotocore-secretsmanager-2.5.1/types_aiobotocore_secretsmanager/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19641 2023-06-28 01:40:28.000000 types-aiobotocore-secretsmanager-2.5.1/types_aiobotocore_secretsmanager/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:40:25.000000 types-aiobotocore-secretsmanager-2.5.1/types_aiobotocore_secretsmanager/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:09.506212 types-aiobotocore-secretsmanager-2.5.1/types_aiobotocore_secretsmanager.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    15347 2023-06-28 01:44:09.000000 types-aiobotocore-secretsmanager-2.5.1/types_aiobotocore_secretsmanager.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      946 2023-06-28 01:44:09.000000 types-aiobotocore-secretsmanager-2.5.1/types_aiobotocore_secretsmanager.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:09.000000 types-aiobotocore-secretsmanager-2.5.1/types_aiobotocore_secretsmanager.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:09.000000 types-aiobotocore-secretsmanager-2.5.1/types_aiobotocore_secretsmanager.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:09.000000 types-aiobotocore-secretsmanager-2.5.1/types_aiobotocore_secretsmanager.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       33 2023-06-28 01:44:09.000000 types-aiobotocore-secretsmanager-2.5.1/types_aiobotocore_secretsmanager.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-secretsmanager-2.5.0.post1/LICENSE` & `types-aiobotocore-secretsmanager-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-secretsmanager-2.5.0.post1/PKG-INFO` & `types-aiobotocore-secretsmanager-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-secretsmanager
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SecretsManager 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SecretsManager 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_secretsmanager/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-secretsmanager"></a>
 
 # types-aiobotocore-secretsmanager
 
 [![PyPI - types-aiobotocore-secretsmanager](https://img.shields.io/pypi/v/types-aiobotocore-secretsmanager.svg?color=blue)](https://pypi.org/project/types-aiobotocore-secretsmanager)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-secretsmanager.svg?color=blue)](https://pypi.org/project/types-aiobotocore-secretsmanager)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_secretsmanager/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-secretsmanager?color=blue)](https://pypistats.org/packages/types-aiobotocore-secretsmanager)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SecretsManager 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/secretsmanager.html#SecretsManager)
+[aiobotocore.SecretsManager 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/secretsmanager.html#SecretsManager)
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
 [types-aiobotocore-secretsmanager docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_secretsmanager/).
 
 See how it helps to find and fix potential bugs:
 
@@ -318,65 +318,65 @@
 
 `types_aiobotocore_secretsmanager.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_secretsmanager.type_defs import (
     CancelRotateSecretRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CancelRotateSecretResponseTypeDef,
     ReplicaRegionTypeTypeDef,
     TagTypeDef,
     ReplicationStatusTypeTypeDef,
     DeleteResourcePolicyRequestRequestTypeDef,
+    DeleteResourcePolicyResponseTypeDef,
     DeleteSecretRequestRequestTypeDef,
+    DeleteSecretResponseTypeDef,
     DescribeSecretRequestRequestTypeDef,
     RotationRulesTypeTypeDef,
+    EmptyResponseMetadataTypeDef,
     FilterTypeDef,
     GetRandomPasswordRequestRequestTypeDef,
+    GetRandomPasswordResponseTypeDef,
     GetResourcePolicyRequestRequestTypeDef,
+    GetResourcePolicyResponseTypeDef,
     GetSecretValueRequestRequestTypeDef,
+    GetSecretValueResponseTypeDef,
     ListSecretVersionIdsRequestRequestTypeDef,
     SecretVersionsListEntryTypeDef,
     PaginatorConfigTypeDef,
     PutResourcePolicyRequestRequestTypeDef,
+    PutResourcePolicyResponseTypeDef,
     PutSecretValueRequestRequestTypeDef,
+    PutSecretValueResponseTypeDef,
     RemoveRegionsFromReplicationRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     RestoreSecretRequestRequestTypeDef,
+    RestoreSecretResponseTypeDef,
+    RotateSecretResponseTypeDef,
     StopReplicationToReplicaRequestRequestTypeDef,
+    StopReplicationToReplicaResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateSecretRequestRequestTypeDef,
+    UpdateSecretResponseTypeDef,
     UpdateSecretVersionStageRequestRequestTypeDef,
+    UpdateSecretVersionStageResponseTypeDef,
     ValidateResourcePolicyRequestRequestTypeDef,
     ValidationErrorsEntryTypeDef,
-    CancelRotateSecretResponseTypeDef,
-    DeleteResourcePolicyResponseTypeDef,
-    DeleteSecretResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetRandomPasswordResponseTypeDef,
-    GetResourcePolicyResponseTypeDef,
-    GetSecretValueResponseTypeDef,
-    PutResourcePolicyResponseTypeDef,
-    PutSecretValueResponseTypeDef,
-    RestoreSecretResponseTypeDef,
-    RotateSecretResponseTypeDef,
-    StopReplicationToReplicaResponseTypeDef,
-    UpdateSecretResponseTypeDef,
-    UpdateSecretVersionStageResponseTypeDef,
     ReplicateSecretToRegionsRequestRequestTypeDef,
     CreateSecretRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     CreateSecretResponseTypeDef,
     RemoveRegionsFromReplicationResponseTypeDef,
     ReplicateSecretToRegionsResponseTypeDef,
     DescribeSecretResponseTypeDef,
     RotateSecretRequestRequestTypeDef,
     SecretListEntryTypeDef,
+    ListSecretsRequestListSecretsPaginateTypeDef,
     ListSecretsRequestRequestTypeDef,
     ListSecretVersionIdsResponseTypeDef,
-    ListSecretsRequestListSecretsPaginateTypeDef,
     ValidateResourcePolicyResponseTypeDef,
     ListSecretsResponseTypeDef,
 )
 
 
 def get_structure() -> CancelRotateSecretRequestRequestTypeDef:
     return {...}
@@ -385,43 +385,43 @@
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

### Comparing `types-aiobotocore-secretsmanager-2.5.0.post1/README.md` & `types-aiobotocore-secretsmanager-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-secretsmanager"></a>
 
 # types-aiobotocore-secretsmanager
 
 [![PyPI - types-aiobotocore-secretsmanager](https://img.shields.io/pypi/v/types-aiobotocore-secretsmanager.svg?color=blue)](https://pypi.org/project/types-aiobotocore-secretsmanager)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-secretsmanager.svg?color=blue)](https://pypi.org/project/types-aiobotocore-secretsmanager)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_secretsmanager/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-secretsmanager?color=blue)](https://pypistats.org/packages/types-aiobotocore-secretsmanager)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SecretsManager 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/secretsmanager.html#SecretsManager)
+[aiobotocore.SecretsManager 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/secretsmanager.html#SecretsManager)
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
 [types-aiobotocore-secretsmanager docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_secretsmanager/).
 
 See how it helps to find and fix potential bugs:
 
@@ -285,65 +285,65 @@
 
 `types_aiobotocore_secretsmanager.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_secretsmanager.type_defs import (
     CancelRotateSecretRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CancelRotateSecretResponseTypeDef,
     ReplicaRegionTypeTypeDef,
     TagTypeDef,
     ReplicationStatusTypeTypeDef,
     DeleteResourcePolicyRequestRequestTypeDef,
+    DeleteResourcePolicyResponseTypeDef,
     DeleteSecretRequestRequestTypeDef,
+    DeleteSecretResponseTypeDef,
     DescribeSecretRequestRequestTypeDef,
     RotationRulesTypeTypeDef,
+    EmptyResponseMetadataTypeDef,
     FilterTypeDef,
     GetRandomPasswordRequestRequestTypeDef,
+    GetRandomPasswordResponseTypeDef,
     GetResourcePolicyRequestRequestTypeDef,
+    GetResourcePolicyResponseTypeDef,
     GetSecretValueRequestRequestTypeDef,
+    GetSecretValueResponseTypeDef,
     ListSecretVersionIdsRequestRequestTypeDef,
     SecretVersionsListEntryTypeDef,
     PaginatorConfigTypeDef,
     PutResourcePolicyRequestRequestTypeDef,
+    PutResourcePolicyResponseTypeDef,
     PutSecretValueRequestRequestTypeDef,
+    PutSecretValueResponseTypeDef,
     RemoveRegionsFromReplicationRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     RestoreSecretRequestRequestTypeDef,
+    RestoreSecretResponseTypeDef,
+    RotateSecretResponseTypeDef,
     StopReplicationToReplicaRequestRequestTypeDef,
+    StopReplicationToReplicaResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateSecretRequestRequestTypeDef,
+    UpdateSecretResponseTypeDef,
     UpdateSecretVersionStageRequestRequestTypeDef,
+    UpdateSecretVersionStageResponseTypeDef,
     ValidateResourcePolicyRequestRequestTypeDef,
     ValidationErrorsEntryTypeDef,
-    CancelRotateSecretResponseTypeDef,
-    DeleteResourcePolicyResponseTypeDef,
-    DeleteSecretResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetRandomPasswordResponseTypeDef,
-    GetResourcePolicyResponseTypeDef,
-    GetSecretValueResponseTypeDef,
-    PutResourcePolicyResponseTypeDef,
-    PutSecretValueResponseTypeDef,
-    RestoreSecretResponseTypeDef,
-    RotateSecretResponseTypeDef,
-    StopReplicationToReplicaResponseTypeDef,
-    UpdateSecretResponseTypeDef,
-    UpdateSecretVersionStageResponseTypeDef,
     ReplicateSecretToRegionsRequestRequestTypeDef,
     CreateSecretRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     CreateSecretResponseTypeDef,
     RemoveRegionsFromReplicationResponseTypeDef,
     ReplicateSecretToRegionsResponseTypeDef,
     DescribeSecretResponseTypeDef,
     RotateSecretRequestRequestTypeDef,
     SecretListEntryTypeDef,
+    ListSecretsRequestListSecretsPaginateTypeDef,
     ListSecretsRequestRequestTypeDef,
     ListSecretVersionIdsResponseTypeDef,
-    ListSecretsRequestListSecretsPaginateTypeDef,
     ValidateResourcePolicyResponseTypeDef,
     ListSecretsResponseTypeDef,
 )
 
 
 def get_structure() -> CancelRotateSecretRequestRequestTypeDef:
     return {...}
@@ -352,43 +352,43 @@
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

### Comparing `types-aiobotocore-secretsmanager-2.5.0.post1/setup.py` & `types-aiobotocore-secretsmanager-2.5.1/setup.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-secretsmanager.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-secretsmanager",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_secretsmanager"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.SecretsManager 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.SecretsManager 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_secretsmanager/"
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

### Comparing `types-aiobotocore-secretsmanager-2.5.0.post1/types_aiobotocore_secretsmanager/__init__.py` & `types-aiobotocore-secretsmanager-2.5.1/types_aiobotocore_secretsmanager/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-secretsmanager-2.5.0.post1/types_aiobotocore_secretsmanager/__init__.pyi` & `types-aiobotocore-secretsmanager-2.5.1/types_aiobotocore_secretsmanager/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-secretsmanager-2.5.0.post1/types_aiobotocore_secretsmanager/__main__.py` & `types-aiobotocore-secretsmanager-2.5.1/types_aiobotocore_secretsmanager/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.SecretsManager 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.SecretsManager 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_secretsmanager//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/secretsmanager.html#SecretsManager\nOther"
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

### Comparing `types-aiobotocore-secretsmanager-2.5.0.post1/types_aiobotocore_secretsmanager/client.py` & `types-aiobotocore-secretsmanager-2.5.1/types_aiobotocore_secretsmanager/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-secretsmanager-2.5.0.post1/types_aiobotocore_secretsmanager/client.pyi` & `types-aiobotocore-secretsmanager-2.5.1/types_aiobotocore_secretsmanager/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-secretsmanager-2.5.0.post1/types_aiobotocore_secretsmanager/literals.py` & `types-aiobotocore-secretsmanager-2.5.1/types_aiobotocore_secretsmanager/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -97,14 +97,15 @@
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
@@ -183,14 +184,15 @@
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
@@ -201,14 +203,15 @@
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
@@ -244,14 +247,15 @@
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
@@ -270,16 +274,19 @@
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
@@ -363,15 +370,17 @@
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

### Comparing `types-aiobotocore-secretsmanager-2.5.0.post1/types_aiobotocore_secretsmanager/literals.pyi` & `types-aiobotocore-secretsmanager-2.5.1/types_aiobotocore_secretsmanager/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -95,14 +95,15 @@
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
@@ -181,14 +182,15 @@
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
@@ -199,14 +201,15 @@
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
@@ -242,14 +245,15 @@
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
@@ -268,16 +272,19 @@
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
@@ -361,15 +368,17 @@
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

### Comparing `types-aiobotocore-secretsmanager-2.5.0.post1/types_aiobotocore_secretsmanager/paginator.py` & `types-aiobotocore-secretsmanager-2.5.1/types_aiobotocore_secretsmanager/paginator.py`

 * *Files 3% similar despite different names*

```diff
@@ -16,29 +16,22 @@
     session = get_session()
     with session.create_client("secretsmanager") as client:
         client: SecretsManagerClient
 
         list_secrets_paginator: ListSecretsPaginator = client.get_paginator("list_secrets")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import SortOrderTypeType
 from .type_defs import FilterTypeDef, ListSecretsResponseTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListSecretsPaginator",)
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -56,13 +49,13 @@
 
     def paginate(
         self,
         *,
         IncludePlannedDeletion: bool = ...,
         Filters: Sequence[FilterTypeDef] = ...,
         SortOrder: SortOrderTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSecretsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/secretsmanager.html#SecretsManager.Paginator.ListSecrets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_secretsmanager/paginators/#listsecretspaginator)
         """
```

### Comparing `types-aiobotocore-secretsmanager-2.5.0.post1/types_aiobotocore_secretsmanager/paginator.pyi` & `types-aiobotocore-secretsmanager-2.5.1/types_aiobotocore_secretsmanager/paginator.pyi`

 * *Files 9% similar despite different names*

```diff
@@ -16,28 +16,22 @@
     session = get_session()
     with session.create_client("secretsmanager") as client:
         client: SecretsManagerClient
 
         list_secrets_paginator: ListSecretsPaginator = client.get_paginator("list_secrets")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import SortOrderTypeType
 from .type_defs import FilterTypeDef, ListSecretsResponseTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListSecretsPaginator",)
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -52,13 +46,13 @@
 
     def paginate(
         self,
         *,
         IncludePlannedDeletion: bool = ...,
         Filters: Sequence[FilterTypeDef] = ...,
         SortOrder: SortOrderTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSecretsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/secretsmanager.html#SecretsManager.Paginator.ListSecrets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_secretsmanager/paginators/#listsecretspaginator)
         """
```

### Comparing `types-aiobotocore-secretsmanager-2.5.0.post1/types_aiobotocore_secretsmanager/type_defs.py` & `types-aiobotocore-secretsmanager-2.5.1/types_aiobotocore_secretsmanager/type_defs.py`

 * *Files 11% similar despite different names*

```diff
@@ -23,84 +23,83 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "CancelRotateSecretRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CancelRotateSecretResponseTypeDef",
     "ReplicaRegionTypeTypeDef",
     "TagTypeDef",
     "ReplicationStatusTypeTypeDef",
     "DeleteResourcePolicyRequestRequestTypeDef",
+    "DeleteResourcePolicyResponseTypeDef",
     "DeleteSecretRequestRequestTypeDef",
+    "DeleteSecretResponseTypeDef",
     "DescribeSecretRequestRequestTypeDef",
     "RotationRulesTypeTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "FilterTypeDef",
     "GetRandomPasswordRequestRequestTypeDef",
+    "GetRandomPasswordResponseTypeDef",
     "GetResourcePolicyRequestRequestTypeDef",
+    "GetResourcePolicyResponseTypeDef",
     "GetSecretValueRequestRequestTypeDef",
+    "GetSecretValueResponseTypeDef",
     "ListSecretVersionIdsRequestRequestTypeDef",
     "SecretVersionsListEntryTypeDef",
     "PaginatorConfigTypeDef",
     "PutResourcePolicyRequestRequestTypeDef",
+    "PutResourcePolicyResponseTypeDef",
     "PutSecretValueRequestRequestTypeDef",
+    "PutSecretValueResponseTypeDef",
     "RemoveRegionsFromReplicationRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "RestoreSecretRequestRequestTypeDef",
+    "RestoreSecretResponseTypeDef",
+    "RotateSecretResponseTypeDef",
     "StopReplicationToReplicaRequestRequestTypeDef",
+    "StopReplicationToReplicaResponseTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateSecretRequestRequestTypeDef",
+    "UpdateSecretResponseTypeDef",
     "UpdateSecretVersionStageRequestRequestTypeDef",
+    "UpdateSecretVersionStageResponseTypeDef",
     "ValidateResourcePolicyRequestRequestTypeDef",
     "ValidationErrorsEntryTypeDef",
-    "CancelRotateSecretResponseTypeDef",
-    "DeleteResourcePolicyResponseTypeDef",
-    "DeleteSecretResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetRandomPasswordResponseTypeDef",
-    "GetResourcePolicyResponseTypeDef",
-    "GetSecretValueResponseTypeDef",
-    "PutResourcePolicyResponseTypeDef",
-    "PutSecretValueResponseTypeDef",
-    "RestoreSecretResponseTypeDef",
-    "RotateSecretResponseTypeDef",
-    "StopReplicationToReplicaResponseTypeDef",
-    "UpdateSecretResponseTypeDef",
-    "UpdateSecretVersionStageResponseTypeDef",
     "ReplicateSecretToRegionsRequestRequestTypeDef",
     "CreateSecretRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "CreateSecretResponseTypeDef",
     "RemoveRegionsFromReplicationResponseTypeDef",
     "ReplicateSecretToRegionsResponseTypeDef",
     "DescribeSecretResponseTypeDef",
     "RotateSecretRequestRequestTypeDef",
     "SecretListEntryTypeDef",
+    "ListSecretsRequestListSecretsPaginateTypeDef",
     "ListSecretsRequestRequestTypeDef",
     "ListSecretVersionIdsResponseTypeDef",
-    "ListSecretsRequestListSecretsPaginateTypeDef",
     "ValidateResourcePolicyResponseTypeDef",
     "ListSecretsResponseTypeDef",
 )
 
 CancelRotateSecretRequestRequestTypeDef = TypedDict(
     "CancelRotateSecretRequestRequestTypeDef",
     {
         "SecretId": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CancelRotateSecretResponseTypeDef = TypedDict(
+    "CancelRotateSecretResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ARN": str,
+        "Name": str,
+        "VersionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReplicaRegionTypeTypeDef = TypedDict(
     "ReplicaRegionTypeTypeDef",
     {
         "Region": str,
@@ -133,14 +132,23 @@
 DeleteResourcePolicyRequestRequestTypeDef = TypedDict(
     "DeleteResourcePolicyRequestRequestTypeDef",
     {
         "SecretId": str,
     },
 )
 
+DeleteResourcePolicyResponseTypeDef = TypedDict(
+    "DeleteResourcePolicyResponseTypeDef",
+    {
+        "ARN": str,
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteSecretRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteSecretRequestRequestTypeDef",
     {
         "SecretId": str,
     },
 )
 _OptionalDeleteSecretRequestRequestTypeDef = TypedDict(
@@ -155,14 +163,24 @@
 
 class DeleteSecretRequestRequestTypeDef(
     _RequiredDeleteSecretRequestRequestTypeDef, _OptionalDeleteSecretRequestRequestTypeDef
 ):
     pass
 
 
+DeleteSecretResponseTypeDef = TypedDict(
+    "DeleteSecretResponseTypeDef",
+    {
+        "ARN": str,
+        "Name": str,
+        "DeletionDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeSecretRequestRequestTypeDef = TypedDict(
     "DescribeSecretRequestRequestTypeDef",
     {
         "SecretId": str,
     },
 )
 
@@ -172,14 +190,21 @@
         "AutomaticallyAfterDays": int,
         "Duration": str,
         "ScheduleExpression": str,
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
 FilterTypeDef = TypedDict(
     "FilterTypeDef",
     {
         "Key": FilterNameStringTypeType,
         "Values": Sequence[str],
     },
     total=False,
@@ -196,21 +221,39 @@
         "ExcludeLowercase": bool,
         "IncludeSpace": bool,
         "RequireEachIncludedType": bool,
     },
     total=False,
 )
 
+GetRandomPasswordResponseTypeDef = TypedDict(
+    "GetRandomPasswordResponseTypeDef",
+    {
+        "RandomPassword": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetResourcePolicyRequestRequestTypeDef = TypedDict(
     "GetResourcePolicyRequestRequestTypeDef",
     {
         "SecretId": str,
     },
 )
 
+GetResourcePolicyResponseTypeDef = TypedDict(
+    "GetResourcePolicyResponseTypeDef",
+    {
+        "ARN": str,
+        "Name": str,
+        "ResourcePolicy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetSecretValueRequestRequestTypeDef = TypedDict(
     "_RequiredGetSecretValueRequestRequestTypeDef",
     {
         "SecretId": str,
     },
 )
 _OptionalGetSecretValueRequestRequestTypeDef = TypedDict(
@@ -225,14 +268,28 @@
 
 class GetSecretValueRequestRequestTypeDef(
     _RequiredGetSecretValueRequestRequestTypeDef, _OptionalGetSecretValueRequestRequestTypeDef
 ):
     pass
 
 
+GetSecretValueResponseTypeDef = TypedDict(
+    "GetSecretValueResponseTypeDef",
+    {
+        "ARN": str,
+        "Name": str,
+        "VersionId": str,
+        "SecretBinary": bytes,
+        "SecretString": str,
+        "VersionStages": List[str],
+        "CreatedDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredListSecretVersionIdsRequestRequestTypeDef = TypedDict(
     "_RequiredListSecretVersionIdsRequestRequestTypeDef",
     {
         "SecretId": str,
     },
 )
 _OptionalListSecretVersionIdsRequestRequestTypeDef = TypedDict(
@@ -293,14 +350,23 @@
 
 class PutResourcePolicyRequestRequestTypeDef(
     _RequiredPutResourcePolicyRequestRequestTypeDef, _OptionalPutResourcePolicyRequestRequestTypeDef
 ):
     pass
 
 
+PutResourcePolicyResponseTypeDef = TypedDict(
+    "PutResourcePolicyResponseTypeDef",
+    {
+        "ARN": str,
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredPutSecretValueRequestRequestTypeDef = TypedDict(
     "_RequiredPutSecretValueRequestRequestTypeDef",
     {
         "SecretId": str,
     },
 )
 _OptionalPutSecretValueRequestRequestTypeDef = TypedDict(
@@ -317,36 +383,85 @@
 
 class PutSecretValueRequestRequestTypeDef(
     _RequiredPutSecretValueRequestRequestTypeDef, _OptionalPutSecretValueRequestRequestTypeDef
 ):
     pass
 
 
+PutSecretValueResponseTypeDef = TypedDict(
+    "PutSecretValueResponseTypeDef",
+    {
+        "ARN": str,
+        "Name": str,
+        "VersionId": str,
+        "VersionStages": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RemoveRegionsFromReplicationRequestRequestTypeDef = TypedDict(
     "RemoveRegionsFromReplicationRequestRequestTypeDef",
     {
         "SecretId": str,
         "RemoveReplicaRegions": Sequence[str],
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
 RestoreSecretRequestRequestTypeDef = TypedDict(
     "RestoreSecretRequestRequestTypeDef",
     {
         "SecretId": str,
     },
 )
 
+RestoreSecretResponseTypeDef = TypedDict(
+    "RestoreSecretResponseTypeDef",
+    {
+        "ARN": str,
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+RotateSecretResponseTypeDef = TypedDict(
+    "RotateSecretResponseTypeDef",
+    {
+        "ARN": str,
+        "Name": str,
+        "VersionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopReplicationToReplicaRequestRequestTypeDef = TypedDict(
     "StopReplicationToReplicaRequestRequestTypeDef",
     {
         "SecretId": str,
     },
 )
 
+StopReplicationToReplicaResponseTypeDef = TypedDict(
+    "StopReplicationToReplicaResponseTypeDef",
+    {
+        "ARN": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "SecretId": str,
         "TagKeys": Sequence[str],
     },
 )
@@ -372,14 +487,24 @@
 
 class UpdateSecretRequestRequestTypeDef(
     _RequiredUpdateSecretRequestRequestTypeDef, _OptionalUpdateSecretRequestRequestTypeDef
 ):
     pass
 
 
+UpdateSecretResponseTypeDef = TypedDict(
+    "UpdateSecretResponseTypeDef",
+    {
+        "ARN": str,
+        "Name": str,
+        "VersionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateSecretVersionStageRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateSecretVersionStageRequestRequestTypeDef",
     {
         "SecretId": str,
         "VersionStage": str,
     },
 )
@@ -396,14 +521,23 @@
 class UpdateSecretVersionStageRequestRequestTypeDef(
     _RequiredUpdateSecretVersionStageRequestRequestTypeDef,
     _OptionalUpdateSecretVersionStageRequestRequestTypeDef,
 ):
     pass
 
 
+UpdateSecretVersionStageResponseTypeDef = TypedDict(
+    "UpdateSecretVersionStageResponseTypeDef",
+    {
+        "ARN": str,
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredValidateResourcePolicyRequestRequestTypeDef = TypedDict(
     "_RequiredValidateResourcePolicyRequestRequestTypeDef",
     {
         "ResourcePolicy": str,
     },
 )
 _OptionalValidateResourcePolicyRequestRequestTypeDef = TypedDict(
@@ -427,148 +561,14 @@
     {
         "CheckName": str,
         "ErrorMessage": str,
     },
     total=False,
 )
 
-CancelRotateSecretResponseTypeDef = TypedDict(
-    "CancelRotateSecretResponseTypeDef",
-    {
-        "ARN": str,
-        "Name": str,
-        "VersionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteResourcePolicyResponseTypeDef = TypedDict(
-    "DeleteResourcePolicyResponseTypeDef",
-    {
-        "ARN": str,
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteSecretResponseTypeDef = TypedDict(
-    "DeleteSecretResponseTypeDef",
-    {
-        "ARN": str,
-        "Name": str,
-        "DeletionDate": datetime,
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
-GetRandomPasswordResponseTypeDef = TypedDict(
-    "GetRandomPasswordResponseTypeDef",
-    {
-        "RandomPassword": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetResourcePolicyResponseTypeDef = TypedDict(
-    "GetResourcePolicyResponseTypeDef",
-    {
-        "ARN": str,
-        "Name": str,
-        "ResourcePolicy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSecretValueResponseTypeDef = TypedDict(
-    "GetSecretValueResponseTypeDef",
-    {
-        "ARN": str,
-        "Name": str,
-        "VersionId": str,
-        "SecretBinary": bytes,
-        "SecretString": str,
-        "VersionStages": List[str],
-        "CreatedDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutResourcePolicyResponseTypeDef = TypedDict(
-    "PutResourcePolicyResponseTypeDef",
-    {
-        "ARN": str,
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutSecretValueResponseTypeDef = TypedDict(
-    "PutSecretValueResponseTypeDef",
-    {
-        "ARN": str,
-        "Name": str,
-        "VersionId": str,
-        "VersionStages": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RestoreSecretResponseTypeDef = TypedDict(
-    "RestoreSecretResponseTypeDef",
-    {
-        "ARN": str,
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RotateSecretResponseTypeDef = TypedDict(
-    "RotateSecretResponseTypeDef",
-    {
-        "ARN": str,
-        "Name": str,
-        "VersionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StopReplicationToReplicaResponseTypeDef = TypedDict(
-    "StopReplicationToReplicaResponseTypeDef",
-    {
-        "ARN": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateSecretResponseTypeDef = TypedDict(
-    "UpdateSecretResponseTypeDef",
-    {
-        "ARN": str,
-        "Name": str,
-        "VersionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateSecretVersionStageResponseTypeDef = TypedDict(
-    "UpdateSecretVersionStageResponseTypeDef",
-    {
-        "ARN": str,
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 _RequiredReplicateSecretToRegionsRequestRequestTypeDef = TypedDict(
     "_RequiredReplicateSecretToRegionsRequestRequestTypeDef",
     {
         "SecretId": str,
         "AddReplicaRegions": Sequence[ReplicaRegionTypeTypeDef],
     },
 )
@@ -627,33 +627,33 @@
 CreateSecretResponseTypeDef = TypedDict(
     "CreateSecretResponseTypeDef",
     {
         "ARN": str,
         "Name": str,
         "VersionId": str,
         "ReplicationStatus": List[ReplicationStatusTypeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RemoveRegionsFromReplicationResponseTypeDef = TypedDict(
     "RemoveRegionsFromReplicationResponseTypeDef",
     {
         "ARN": str,
         "ReplicationStatus": List[ReplicationStatusTypeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReplicateSecretToRegionsResponseTypeDef = TypedDict(
     "ReplicateSecretToRegionsResponseTypeDef",
     {
         "ARN": str,
         "ReplicationStatus": List[ReplicationStatusTypeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSecretResponseTypeDef = TypedDict(
     "DescribeSecretResponseTypeDef",
     {
         "ARN": str,
@@ -670,15 +670,15 @@
         "NextRotationDate": datetime,
         "Tags": List[TagTypeDef],
         "VersionIdsToStages": Dict[str, List[str]],
         "OwningService": str,
         "CreatedDate": datetime,
         "PrimaryRegion": str,
         "ReplicationStatus": List[ReplicationStatusTypeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredRotateSecretRequestRequestTypeDef = TypedDict(
     "_RequiredRotateSecretRequestRequestTypeDef",
     {
         "SecretId": str,
@@ -722,14 +722,25 @@
         "OwningService": str,
         "CreatedDate": datetime,
         "PrimaryRegion": str,
     },
     total=False,
 )
 
+ListSecretsRequestListSecretsPaginateTypeDef = TypedDict(
+    "ListSecretsRequestListSecretsPaginateTypeDef",
+    {
+        "IncludePlannedDeletion": bool,
+        "Filters": Sequence[FilterTypeDef],
+        "SortOrder": SortOrderTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSecretsRequestRequestTypeDef = TypedDict(
     "ListSecretsRequestRequestTypeDef",
     {
         "IncludePlannedDeletion": bool,
         "MaxResults": int,
         "NextToken": str,
         "Filters": Sequence[FilterTypeDef],
@@ -741,39 +752,28 @@
 ListSecretVersionIdsResponseTypeDef = TypedDict(
     "ListSecretVersionIdsResponseTypeDef",
     {
         "Versions": List[SecretVersionsListEntryTypeDef],
         "NextToken": str,
         "ARN": str,
         "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListSecretsRequestListSecretsPaginateTypeDef = TypedDict(
-    "ListSecretsRequestListSecretsPaginateTypeDef",
-    {
-        "IncludePlannedDeletion": bool,
-        "Filters": Sequence[FilterTypeDef],
-        "SortOrder": SortOrderTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ValidateResourcePolicyResponseTypeDef = TypedDict(
     "ValidateResourcePolicyResponseTypeDef",
     {
         "PolicyValidationPassed": bool,
         "ValidationErrors": List[ValidationErrorsEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSecretsResponseTypeDef = TypedDict(
     "ListSecretsResponseTypeDef",
     {
         "SecretList": List[SecretListEntryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-secretsmanager-2.5.0.post1/types_aiobotocore_secretsmanager/type_defs.pyi` & `types-aiobotocore-secretsmanager-2.5.1/types_aiobotocore_secretsmanager/type_defs.pyi`

 * *Files 8% similar despite different names*

```diff
@@ -22,84 +22,83 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "CancelRotateSecretRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CancelRotateSecretResponseTypeDef",
     "ReplicaRegionTypeTypeDef",
     "TagTypeDef",
     "ReplicationStatusTypeTypeDef",
     "DeleteResourcePolicyRequestRequestTypeDef",
+    "DeleteResourcePolicyResponseTypeDef",
     "DeleteSecretRequestRequestTypeDef",
+    "DeleteSecretResponseTypeDef",
     "DescribeSecretRequestRequestTypeDef",
     "RotationRulesTypeTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "FilterTypeDef",
     "GetRandomPasswordRequestRequestTypeDef",
+    "GetRandomPasswordResponseTypeDef",
     "GetResourcePolicyRequestRequestTypeDef",
+    "GetResourcePolicyResponseTypeDef",
     "GetSecretValueRequestRequestTypeDef",
+    "GetSecretValueResponseTypeDef",
     "ListSecretVersionIdsRequestRequestTypeDef",
     "SecretVersionsListEntryTypeDef",
     "PaginatorConfigTypeDef",
     "PutResourcePolicyRequestRequestTypeDef",
+    "PutResourcePolicyResponseTypeDef",
     "PutSecretValueRequestRequestTypeDef",
+    "PutSecretValueResponseTypeDef",
     "RemoveRegionsFromReplicationRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "RestoreSecretRequestRequestTypeDef",
+    "RestoreSecretResponseTypeDef",
+    "RotateSecretResponseTypeDef",
     "StopReplicationToReplicaRequestRequestTypeDef",
+    "StopReplicationToReplicaResponseTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateSecretRequestRequestTypeDef",
+    "UpdateSecretResponseTypeDef",
     "UpdateSecretVersionStageRequestRequestTypeDef",
+    "UpdateSecretVersionStageResponseTypeDef",
     "ValidateResourcePolicyRequestRequestTypeDef",
     "ValidationErrorsEntryTypeDef",
-    "CancelRotateSecretResponseTypeDef",
-    "DeleteResourcePolicyResponseTypeDef",
-    "DeleteSecretResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetRandomPasswordResponseTypeDef",
-    "GetResourcePolicyResponseTypeDef",
-    "GetSecretValueResponseTypeDef",
-    "PutResourcePolicyResponseTypeDef",
-    "PutSecretValueResponseTypeDef",
-    "RestoreSecretResponseTypeDef",
-    "RotateSecretResponseTypeDef",
-    "StopReplicationToReplicaResponseTypeDef",
-    "UpdateSecretResponseTypeDef",
-    "UpdateSecretVersionStageResponseTypeDef",
     "ReplicateSecretToRegionsRequestRequestTypeDef",
     "CreateSecretRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "CreateSecretResponseTypeDef",
     "RemoveRegionsFromReplicationResponseTypeDef",
     "ReplicateSecretToRegionsResponseTypeDef",
     "DescribeSecretResponseTypeDef",
     "RotateSecretRequestRequestTypeDef",
     "SecretListEntryTypeDef",
+    "ListSecretsRequestListSecretsPaginateTypeDef",
     "ListSecretsRequestRequestTypeDef",
     "ListSecretVersionIdsResponseTypeDef",
-    "ListSecretsRequestListSecretsPaginateTypeDef",
     "ValidateResourcePolicyResponseTypeDef",
     "ListSecretsResponseTypeDef",
 )
 
 CancelRotateSecretRequestRequestTypeDef = TypedDict(
     "CancelRotateSecretRequestRequestTypeDef",
     {
         "SecretId": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CancelRotateSecretResponseTypeDef = TypedDict(
+    "CancelRotateSecretResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ARN": str,
+        "Name": str,
+        "VersionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReplicaRegionTypeTypeDef = TypedDict(
     "ReplicaRegionTypeTypeDef",
     {
         "Region": str,
@@ -132,14 +131,23 @@
 DeleteResourcePolicyRequestRequestTypeDef = TypedDict(
     "DeleteResourcePolicyRequestRequestTypeDef",
     {
         "SecretId": str,
     },
 )
 
+DeleteResourcePolicyResponseTypeDef = TypedDict(
+    "DeleteResourcePolicyResponseTypeDef",
+    {
+        "ARN": str,
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteSecretRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteSecretRequestRequestTypeDef",
     {
         "SecretId": str,
     },
 )
 _OptionalDeleteSecretRequestRequestTypeDef = TypedDict(
@@ -152,14 +160,24 @@
 )
 
 class DeleteSecretRequestRequestTypeDef(
     _RequiredDeleteSecretRequestRequestTypeDef, _OptionalDeleteSecretRequestRequestTypeDef
 ):
     pass
 
+DeleteSecretResponseTypeDef = TypedDict(
+    "DeleteSecretResponseTypeDef",
+    {
+        "ARN": str,
+        "Name": str,
+        "DeletionDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeSecretRequestRequestTypeDef = TypedDict(
     "DescribeSecretRequestRequestTypeDef",
     {
         "SecretId": str,
     },
 )
 
@@ -169,14 +187,21 @@
         "AutomaticallyAfterDays": int,
         "Duration": str,
         "ScheduleExpression": str,
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
 FilterTypeDef = TypedDict(
     "FilterTypeDef",
     {
         "Key": FilterNameStringTypeType,
         "Values": Sequence[str],
     },
     total=False,
@@ -193,21 +218,39 @@
         "ExcludeLowercase": bool,
         "IncludeSpace": bool,
         "RequireEachIncludedType": bool,
     },
     total=False,
 )
 
+GetRandomPasswordResponseTypeDef = TypedDict(
+    "GetRandomPasswordResponseTypeDef",
+    {
+        "RandomPassword": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetResourcePolicyRequestRequestTypeDef = TypedDict(
     "GetResourcePolicyRequestRequestTypeDef",
     {
         "SecretId": str,
     },
 )
 
+GetResourcePolicyResponseTypeDef = TypedDict(
+    "GetResourcePolicyResponseTypeDef",
+    {
+        "ARN": str,
+        "Name": str,
+        "ResourcePolicy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetSecretValueRequestRequestTypeDef = TypedDict(
     "_RequiredGetSecretValueRequestRequestTypeDef",
     {
         "SecretId": str,
     },
 )
 _OptionalGetSecretValueRequestRequestTypeDef = TypedDict(
@@ -220,14 +263,28 @@
 )
 
 class GetSecretValueRequestRequestTypeDef(
     _RequiredGetSecretValueRequestRequestTypeDef, _OptionalGetSecretValueRequestRequestTypeDef
 ):
     pass
 
+GetSecretValueResponseTypeDef = TypedDict(
+    "GetSecretValueResponseTypeDef",
+    {
+        "ARN": str,
+        "Name": str,
+        "VersionId": str,
+        "SecretBinary": bytes,
+        "SecretString": str,
+        "VersionStages": List[str],
+        "CreatedDate": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredListSecretVersionIdsRequestRequestTypeDef = TypedDict(
     "_RequiredListSecretVersionIdsRequestRequestTypeDef",
     {
         "SecretId": str,
     },
 )
 _OptionalListSecretVersionIdsRequestRequestTypeDef = TypedDict(
@@ -284,14 +341,23 @@
 )
 
 class PutResourcePolicyRequestRequestTypeDef(
     _RequiredPutResourcePolicyRequestRequestTypeDef, _OptionalPutResourcePolicyRequestRequestTypeDef
 ):
     pass
 
+PutResourcePolicyResponseTypeDef = TypedDict(
+    "PutResourcePolicyResponseTypeDef",
+    {
+        "ARN": str,
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredPutSecretValueRequestRequestTypeDef = TypedDict(
     "_RequiredPutSecretValueRequestRequestTypeDef",
     {
         "SecretId": str,
     },
 )
 _OptionalPutSecretValueRequestRequestTypeDef = TypedDict(
@@ -306,36 +372,85 @@
 )
 
 class PutSecretValueRequestRequestTypeDef(
     _RequiredPutSecretValueRequestRequestTypeDef, _OptionalPutSecretValueRequestRequestTypeDef
 ):
     pass
 
+PutSecretValueResponseTypeDef = TypedDict(
+    "PutSecretValueResponseTypeDef",
+    {
+        "ARN": str,
+        "Name": str,
+        "VersionId": str,
+        "VersionStages": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RemoveRegionsFromReplicationRequestRequestTypeDef = TypedDict(
     "RemoveRegionsFromReplicationRequestRequestTypeDef",
     {
         "SecretId": str,
         "RemoveReplicaRegions": Sequence[str],
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
 RestoreSecretRequestRequestTypeDef = TypedDict(
     "RestoreSecretRequestRequestTypeDef",
     {
         "SecretId": str,
     },
 )
 
+RestoreSecretResponseTypeDef = TypedDict(
+    "RestoreSecretResponseTypeDef",
+    {
+        "ARN": str,
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+RotateSecretResponseTypeDef = TypedDict(
+    "RotateSecretResponseTypeDef",
+    {
+        "ARN": str,
+        "Name": str,
+        "VersionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopReplicationToReplicaRequestRequestTypeDef = TypedDict(
     "StopReplicationToReplicaRequestRequestTypeDef",
     {
         "SecretId": str,
     },
 )
 
+StopReplicationToReplicaResponseTypeDef = TypedDict(
+    "StopReplicationToReplicaResponseTypeDef",
+    {
+        "ARN": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "SecretId": str,
         "TagKeys": Sequence[str],
     },
 )
@@ -359,14 +474,24 @@
 )
 
 class UpdateSecretRequestRequestTypeDef(
     _RequiredUpdateSecretRequestRequestTypeDef, _OptionalUpdateSecretRequestRequestTypeDef
 ):
     pass
 
+UpdateSecretResponseTypeDef = TypedDict(
+    "UpdateSecretResponseTypeDef",
+    {
+        "ARN": str,
+        "Name": str,
+        "VersionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateSecretVersionStageRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateSecretVersionStageRequestRequestTypeDef",
     {
         "SecretId": str,
         "VersionStage": str,
     },
 )
@@ -381,14 +506,23 @@
 
 class UpdateSecretVersionStageRequestRequestTypeDef(
     _RequiredUpdateSecretVersionStageRequestRequestTypeDef,
     _OptionalUpdateSecretVersionStageRequestRequestTypeDef,
 ):
     pass
 
+UpdateSecretVersionStageResponseTypeDef = TypedDict(
+    "UpdateSecretVersionStageResponseTypeDef",
+    {
+        "ARN": str,
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredValidateResourcePolicyRequestRequestTypeDef = TypedDict(
     "_RequiredValidateResourcePolicyRequestRequestTypeDef",
     {
         "ResourcePolicy": str,
     },
 )
 _OptionalValidateResourcePolicyRequestRequestTypeDef = TypedDict(
@@ -410,148 +544,14 @@
     {
         "CheckName": str,
         "ErrorMessage": str,
     },
     total=False,
 )
 
-CancelRotateSecretResponseTypeDef = TypedDict(
-    "CancelRotateSecretResponseTypeDef",
-    {
-        "ARN": str,
-        "Name": str,
-        "VersionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteResourcePolicyResponseTypeDef = TypedDict(
-    "DeleteResourcePolicyResponseTypeDef",
-    {
-        "ARN": str,
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteSecretResponseTypeDef = TypedDict(
-    "DeleteSecretResponseTypeDef",
-    {
-        "ARN": str,
-        "Name": str,
-        "DeletionDate": datetime,
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
-GetRandomPasswordResponseTypeDef = TypedDict(
-    "GetRandomPasswordResponseTypeDef",
-    {
-        "RandomPassword": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetResourcePolicyResponseTypeDef = TypedDict(
-    "GetResourcePolicyResponseTypeDef",
-    {
-        "ARN": str,
-        "Name": str,
-        "ResourcePolicy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSecretValueResponseTypeDef = TypedDict(
-    "GetSecretValueResponseTypeDef",
-    {
-        "ARN": str,
-        "Name": str,
-        "VersionId": str,
-        "SecretBinary": bytes,
-        "SecretString": str,
-        "VersionStages": List[str],
-        "CreatedDate": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutResourcePolicyResponseTypeDef = TypedDict(
-    "PutResourcePolicyResponseTypeDef",
-    {
-        "ARN": str,
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutSecretValueResponseTypeDef = TypedDict(
-    "PutSecretValueResponseTypeDef",
-    {
-        "ARN": str,
-        "Name": str,
-        "VersionId": str,
-        "VersionStages": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RestoreSecretResponseTypeDef = TypedDict(
-    "RestoreSecretResponseTypeDef",
-    {
-        "ARN": str,
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RotateSecretResponseTypeDef = TypedDict(
-    "RotateSecretResponseTypeDef",
-    {
-        "ARN": str,
-        "Name": str,
-        "VersionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StopReplicationToReplicaResponseTypeDef = TypedDict(
-    "StopReplicationToReplicaResponseTypeDef",
-    {
-        "ARN": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateSecretResponseTypeDef = TypedDict(
-    "UpdateSecretResponseTypeDef",
-    {
-        "ARN": str,
-        "Name": str,
-        "VersionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateSecretVersionStageResponseTypeDef = TypedDict(
-    "UpdateSecretVersionStageResponseTypeDef",
-    {
-        "ARN": str,
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 _RequiredReplicateSecretToRegionsRequestRequestTypeDef = TypedDict(
     "_RequiredReplicateSecretToRegionsRequestRequestTypeDef",
     {
         "SecretId": str,
         "AddReplicaRegions": Sequence[ReplicaRegionTypeTypeDef],
     },
 )
@@ -606,33 +606,33 @@
 CreateSecretResponseTypeDef = TypedDict(
     "CreateSecretResponseTypeDef",
     {
         "ARN": str,
         "Name": str,
         "VersionId": str,
         "ReplicationStatus": List[ReplicationStatusTypeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RemoveRegionsFromReplicationResponseTypeDef = TypedDict(
     "RemoveRegionsFromReplicationResponseTypeDef",
     {
         "ARN": str,
         "ReplicationStatus": List[ReplicationStatusTypeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReplicateSecretToRegionsResponseTypeDef = TypedDict(
     "ReplicateSecretToRegionsResponseTypeDef",
     {
         "ARN": str,
         "ReplicationStatus": List[ReplicationStatusTypeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSecretResponseTypeDef = TypedDict(
     "DescribeSecretResponseTypeDef",
     {
         "ARN": str,
@@ -649,15 +649,15 @@
         "NextRotationDate": datetime,
         "Tags": List[TagTypeDef],
         "VersionIdsToStages": Dict[str, List[str]],
         "OwningService": str,
         "CreatedDate": datetime,
         "PrimaryRegion": str,
         "ReplicationStatus": List[ReplicationStatusTypeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredRotateSecretRequestRequestTypeDef = TypedDict(
     "_RequiredRotateSecretRequestRequestTypeDef",
     {
         "SecretId": str,
@@ -699,14 +699,25 @@
         "OwningService": str,
         "CreatedDate": datetime,
         "PrimaryRegion": str,
     },
     total=False,
 )
 
+ListSecretsRequestListSecretsPaginateTypeDef = TypedDict(
+    "ListSecretsRequestListSecretsPaginateTypeDef",
+    {
+        "IncludePlannedDeletion": bool,
+        "Filters": Sequence[FilterTypeDef],
+        "SortOrder": SortOrderTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSecretsRequestRequestTypeDef = TypedDict(
     "ListSecretsRequestRequestTypeDef",
     {
         "IncludePlannedDeletion": bool,
         "MaxResults": int,
         "NextToken": str,
         "Filters": Sequence[FilterTypeDef],
@@ -718,39 +729,28 @@
 ListSecretVersionIdsResponseTypeDef = TypedDict(
     "ListSecretVersionIdsResponseTypeDef",
     {
         "Versions": List[SecretVersionsListEntryTypeDef],
         "NextToken": str,
         "ARN": str,
         "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListSecretsRequestListSecretsPaginateTypeDef = TypedDict(
-    "ListSecretsRequestListSecretsPaginateTypeDef",
-    {
-        "IncludePlannedDeletion": bool,
-        "Filters": Sequence[FilterTypeDef],
-        "SortOrder": SortOrderTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ValidateResourcePolicyResponseTypeDef = TypedDict(
     "ValidateResourcePolicyResponseTypeDef",
     {
         "PolicyValidationPassed": bool,
         "ValidationErrors": List[ValidationErrorsEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSecretsResponseTypeDef = TypedDict(
     "ListSecretsResponseTypeDef",
     {
         "SecretList": List[SecretListEntryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-secretsmanager-2.5.0.post1/types_aiobotocore_secretsmanager.egg-info/PKG-INFO` & `types-aiobotocore-secretsmanager-2.5.1/types_aiobotocore_secretsmanager.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-secretsmanager
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SecretsManager 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SecretsManager 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_secretsmanager/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-secretsmanager"></a>
 
 # types-aiobotocore-secretsmanager
 
 [![PyPI - types-aiobotocore-secretsmanager](https://img.shields.io/pypi/v/types-aiobotocore-secretsmanager.svg?color=blue)](https://pypi.org/project/types-aiobotocore-secretsmanager)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-secretsmanager.svg?color=blue)](https://pypi.org/project/types-aiobotocore-secretsmanager)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_secretsmanager/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-secretsmanager?color=blue)](https://pypistats.org/packages/types-aiobotocore-secretsmanager)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SecretsManager 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/secretsmanager.html#SecretsManager)
+[aiobotocore.SecretsManager 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/secretsmanager.html#SecretsManager)
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
 [types-aiobotocore-secretsmanager docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_secretsmanager/).
 
 See how it helps to find and fix potential bugs:
 
@@ -318,65 +318,65 @@
 
 `types_aiobotocore_secretsmanager.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_secretsmanager.type_defs import (
     CancelRotateSecretRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CancelRotateSecretResponseTypeDef,
     ReplicaRegionTypeTypeDef,
     TagTypeDef,
     ReplicationStatusTypeTypeDef,
     DeleteResourcePolicyRequestRequestTypeDef,
+    DeleteResourcePolicyResponseTypeDef,
     DeleteSecretRequestRequestTypeDef,
+    DeleteSecretResponseTypeDef,
     DescribeSecretRequestRequestTypeDef,
     RotationRulesTypeTypeDef,
+    EmptyResponseMetadataTypeDef,
     FilterTypeDef,
     GetRandomPasswordRequestRequestTypeDef,
+    GetRandomPasswordResponseTypeDef,
     GetResourcePolicyRequestRequestTypeDef,
+    GetResourcePolicyResponseTypeDef,
     GetSecretValueRequestRequestTypeDef,
+    GetSecretValueResponseTypeDef,
     ListSecretVersionIdsRequestRequestTypeDef,
     SecretVersionsListEntryTypeDef,
     PaginatorConfigTypeDef,
     PutResourcePolicyRequestRequestTypeDef,
+    PutResourcePolicyResponseTypeDef,
     PutSecretValueRequestRequestTypeDef,
+    PutSecretValueResponseTypeDef,
     RemoveRegionsFromReplicationRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     RestoreSecretRequestRequestTypeDef,
+    RestoreSecretResponseTypeDef,
+    RotateSecretResponseTypeDef,
     StopReplicationToReplicaRequestRequestTypeDef,
+    StopReplicationToReplicaResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateSecretRequestRequestTypeDef,
+    UpdateSecretResponseTypeDef,
     UpdateSecretVersionStageRequestRequestTypeDef,
+    UpdateSecretVersionStageResponseTypeDef,
     ValidateResourcePolicyRequestRequestTypeDef,
     ValidationErrorsEntryTypeDef,
-    CancelRotateSecretResponseTypeDef,
-    DeleteResourcePolicyResponseTypeDef,
-    DeleteSecretResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetRandomPasswordResponseTypeDef,
-    GetResourcePolicyResponseTypeDef,
-    GetSecretValueResponseTypeDef,
-    PutResourcePolicyResponseTypeDef,
-    PutSecretValueResponseTypeDef,
-    RestoreSecretResponseTypeDef,
-    RotateSecretResponseTypeDef,
-    StopReplicationToReplicaResponseTypeDef,
-    UpdateSecretResponseTypeDef,
-    UpdateSecretVersionStageResponseTypeDef,
     ReplicateSecretToRegionsRequestRequestTypeDef,
     CreateSecretRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     CreateSecretResponseTypeDef,
     RemoveRegionsFromReplicationResponseTypeDef,
     ReplicateSecretToRegionsResponseTypeDef,
     DescribeSecretResponseTypeDef,
     RotateSecretRequestRequestTypeDef,
     SecretListEntryTypeDef,
+    ListSecretsRequestListSecretsPaginateTypeDef,
     ListSecretsRequestRequestTypeDef,
     ListSecretVersionIdsResponseTypeDef,
-    ListSecretsRequestListSecretsPaginateTypeDef,
     ValidateResourcePolicyResponseTypeDef,
     ListSecretsResponseTypeDef,
 )
 
 
 def get_structure() -> CancelRotateSecretRequestRequestTypeDef:
     return {...}
@@ -385,43 +385,43 @@
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

### Comparing `types-aiobotocore-secretsmanager-2.5.0.post1/types_aiobotocore_secretsmanager.egg-info/SOURCES.txt` & `types-aiobotocore-secretsmanager-2.5.1/types_aiobotocore_secretsmanager.egg-info/SOURCES.txt`

 * *Files identical despite different names*

