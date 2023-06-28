# Comparing `tmp/types-aiobotocore-signer-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-signer-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-signer-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:21 2023, max compression
+gzip compressed data, was "types-aiobotocore-signer-2.5.1.tar", last modified: Wed Jun 28 01:44:12 2023, max compression
```

## Comparing `types-aiobotocore-signer-2.5.0.post1.tar` & `types-aiobotocore-signer-2.5.1.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:21.083634 types-aiobotocore-signer-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:24:15.000000 types-aiobotocore-signer-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    16310 2023-03-11 12:27:21.083634 types-aiobotocore-signer-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    14743 2023-03-11 12:24:15.000000 types-aiobotocore-signer-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:21.083634 types-aiobotocore-signer-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2117 2023-03-11 12:24:15.000000 types-aiobotocore-signer-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:21.067634 types-aiobotocore-signer-2.5.0.post1/types_aiobotocore_signer/
--rw-r--r--   0 runner    (1001) docker     (123)     1347 2023-03-11 12:24:15.000000 types-aiobotocore-signer-2.5.0.post1/types_aiobotocore_signer/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1346 2023-03-11 12:24:15.000000 types-aiobotocore-signer-2.5.0.post1/types_aiobotocore_signer/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      928 2023-03-11 12:24:15.000000 types-aiobotocore-signer-2.5.0.post1/types_aiobotocore_signer/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    17286 2023-03-11 12:24:15.000000 types-aiobotocore-signer-2.5.0.post1/types_aiobotocore_signer/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    17256 2023-03-11 12:24:15.000000 types-aiobotocore-signer-2.5.0.post1/types_aiobotocore_signer/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8456 2023-03-11 12:24:15.000000 types-aiobotocore-signer-2.5.0.post1/types_aiobotocore_signer/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8454 2023-03-11 12:24:15.000000 types-aiobotocore-signer-2.5.0.post1/types_aiobotocore_signer/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     5017 2023-03-11 12:24:15.000000 types-aiobotocore-signer-2.5.0.post1/types_aiobotocore_signer/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     5011 2023-03-11 12:24:15.000000 types-aiobotocore-signer-2.5.0.post1/types_aiobotocore_signer/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:24:15.000000 types-aiobotocore-signer-2.5.0.post1/types_aiobotocore_signer/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    20028 2023-03-11 12:24:16.000000 types-aiobotocore-signer-2.5.0.post1/types_aiobotocore_signer/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    20013 2023-03-11 12:24:16.000000 types-aiobotocore-signer-2.5.0.post1/types_aiobotocore_signer/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:24:15.000000 types-aiobotocore-signer-2.5.0.post1/types_aiobotocore_signer/version.py
--rw-r--r--   0 runner    (1001) docker     (123)     1564 2023-03-11 12:24:15.000000 types-aiobotocore-signer-2.5.0.post1/types_aiobotocore_signer/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)     1563 2023-03-11 12:24:15.000000 types-aiobotocore-signer-2.5.0.post1/types_aiobotocore_signer/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:21.083634 types-aiobotocore-signer-2.5.0.post1/types_aiobotocore_signer.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    16310 2023-03-11 12:27:20.000000 types-aiobotocore-signer-2.5.0.post1/types_aiobotocore_signer.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      865 2023-03-11 12:27:20.000000 types-aiobotocore-signer-2.5.0.post1/types_aiobotocore_signer.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:20.000000 types-aiobotocore-signer-2.5.0.post1/types_aiobotocore_signer.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:20.000000 types-aiobotocore-signer-2.5.0.post1/types_aiobotocore_signer.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:20.000000 types-aiobotocore-signer-2.5.0.post1/types_aiobotocore_signer.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:20.000000 types-aiobotocore-signer-2.5.0.post1/types_aiobotocore_signer.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:12.174217 types-aiobotocore-signer-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:41:03.000000 types-aiobotocore-signer-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    16473 2023-06-28 01:44:12.174217 types-aiobotocore-signer-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    14912 2023-06-28 01:41:03.000000 types-aiobotocore-signer-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:12.174217 types-aiobotocore-signer-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2111 2023-06-28 01:41:03.000000 types-aiobotocore-signer-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:12.166217 types-aiobotocore-signer-2.5.1/types_aiobotocore_signer/
+-rw-r--r--   0 runner    (1001) docker     (123)     1347 2023-06-28 01:41:03.000000 types-aiobotocore-signer-2.5.1/types_aiobotocore_signer/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1346 2023-06-28 01:41:03.000000 types-aiobotocore-signer-2.5.1/types_aiobotocore_signer/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      916 2023-06-28 01:41:03.000000 types-aiobotocore-signer-2.5.1/types_aiobotocore_signer/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18767 2023-06-28 01:41:03.000000 types-aiobotocore-signer-2.5.1/types_aiobotocore_signer/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18735 2023-06-28 01:41:03.000000 types-aiobotocore-signer-2.5.1/types_aiobotocore_signer/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9078 2023-06-28 01:41:03.000000 types-aiobotocore-signer-2.5.1/types_aiobotocore_signer/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9076 2023-06-28 01:41:03.000000 types-aiobotocore-signer-2.5.1/types_aiobotocore_signer/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     4903 2023-06-28 01:41:03.000000 types-aiobotocore-signer-2.5.1/types_aiobotocore_signer/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4898 2023-06-28 01:41:03.000000 types-aiobotocore-signer-2.5.1/types_aiobotocore_signer/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:41:03.000000 types-aiobotocore-signer-2.5.1/types_aiobotocore_signer/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    21583 2023-06-28 01:41:04.000000 types-aiobotocore-signer-2.5.1/types_aiobotocore_signer/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21566 2023-06-28 01:41:04.000000 types-aiobotocore-signer-2.5.1/types_aiobotocore_signer/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:41:03.000000 types-aiobotocore-signer-2.5.1/types_aiobotocore_signer/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1564 2023-06-28 01:41:03.000000 types-aiobotocore-signer-2.5.1/types_aiobotocore_signer/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1563 2023-06-28 01:41:03.000000 types-aiobotocore-signer-2.5.1/types_aiobotocore_signer/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:12.174217 types-aiobotocore-signer-2.5.1/types_aiobotocore_signer.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    16473 2023-06-28 01:44:12.000000 types-aiobotocore-signer-2.5.1/types_aiobotocore_signer.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      865 2023-06-28 01:44:12.000000 types-aiobotocore-signer-2.5.1/types_aiobotocore_signer.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:12.000000 types-aiobotocore-signer-2.5.1/types_aiobotocore_signer.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:12.000000 types-aiobotocore-signer-2.5.1/types_aiobotocore_signer.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:12.000000 types-aiobotocore-signer-2.5.1/types_aiobotocore_signer.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       25 2023-06-28 01:44:12.000000 types-aiobotocore-signer-2.5.1/types_aiobotocore_signer.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-signer-2.5.0.post1/LICENSE` & `types-aiobotocore-signer-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-signer-2.5.0.post1/PKG-INFO` & `types-aiobotocore-signer-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-signer
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.signer 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.signer 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_signer/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-signer"></a>
 
 # types-aiobotocore-signer
 
 [![PyPI - types-aiobotocore-signer](https://img.shields.io/pypi/v/types-aiobotocore-signer.svg?color=blue)](https://pypi.org/project/types-aiobotocore-signer)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-signer.svg?color=blue)](https://pypi.org/project/types-aiobotocore-signer)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_signer/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-signer?color=blue)](https://pypistats.org/packages/types-aiobotocore-signer)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.signer 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/signer.html#signer)
+[aiobotocore.signer 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/signer.html#signer)
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
 [types-aiobotocore-signer docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_signer/).
 
 See how it helps to find and fix potential bugs:
 
@@ -344,14 +344,15 @@
     SuccessfulSigningJobWaiterName,
     ValidityTypeType,
     signerServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     WaiterName,
+    RegionName,
 )
 
 
 def check_value(value: CategoryType) -> bool:
     ...
 ```
 
@@ -361,57 +362,61 @@
 
 `types_aiobotocore_signer.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_signer.type_defs import (
     AddProfilePermissionRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AddProfilePermissionResponseTypeDef,
     CancelSigningProfileRequestRequestTypeDef,
     DescribeSigningJobRequestRequestTypeDef,
     WaiterConfigTypeDef,
     SigningJobRevocationRecordTypeDef,
     SigningMaterialTypeDef,
     S3DestinationTypeDef,
+    EmptyResponseMetadataTypeDef,
     EncryptionAlgorithmOptionsTypeDef,
+    GetRevocationStatusRequestRequestTypeDef,
+    GetRevocationStatusResponseTypeDef,
     GetSigningPlatformRequestRequestTypeDef,
     SigningImageFormatTypeDef,
     GetSigningProfileRequestRequestTypeDef,
     SignatureValidityPeriodTypeDef,
     SigningProfileRevocationRecordTypeDef,
     HashAlgorithmOptionsTypeDef,
     ListProfilePermissionsRequestRequestTypeDef,
     PermissionTypeDef,
-    PaginatorConfigTypeDef,
+    ListSigningJobsRequestListSigningJobsPaginateTypeDef,
     ListSigningJobsRequestRequestTypeDef,
+    ListSigningPlatformsRequestListSigningPlatformsPaginateTypeDef,
     ListSigningPlatformsRequestRequestTypeDef,
+    ListSigningProfilesRequestListSigningProfilesPaginateTypeDef,
     ListSigningProfilesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
+    PutSigningProfileResponseTypeDef,
     RemoveProfilePermissionRequestRequestTypeDef,
+    RemoveProfilePermissionResponseTypeDef,
+    ResponseMetadataTypeDef,
     RevokeSignatureRequestRequestTypeDef,
     RevokeSigningProfileRequestRequestTypeDef,
     S3SignedObjectTypeDef,
     S3SourceTypeDef,
+    SignPayloadRequestRequestTypeDef,
+    SignPayloadResponseTypeDef,
     SigningConfigurationOverridesTypeDef,
+    StartSigningJobResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
-    AddProfilePermissionResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    PutSigningProfileResponseTypeDef,
-    RemoveProfilePermissionResponseTypeDef,
-    StartSigningJobResponseTypeDef,
     DescribeSigningJobRequestSuccessfulSigningJobWaitTypeDef,
     DestinationTypeDef,
     SigningProfileTypeDef,
     SigningConfigurationTypeDef,
     ListProfilePermissionsResponseTypeDef,
-    ListSigningJobsRequestListSigningJobsPaginateTypeDef,
-    ListSigningPlatformsRequestListSigningPlatformsPaginateTypeDef,
-    ListSigningProfilesRequestListSigningProfilesPaginateTypeDef,
     SignedObjectTypeDef,
     SourceTypeDef,
     SigningPlatformOverridesTypeDef,
     ListSigningProfilesResponseTypeDef,
     GetSigningPlatformResponseTypeDef,
     SigningPlatformTypeDef,
     SigningJobTypeDef,
@@ -431,43 +436,43 @@
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

### Comparing `types-aiobotocore-signer-2.5.0.post1/README.md` & `types-aiobotocore-signer-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-signer"></a>
 
 # types-aiobotocore-signer
 
 [![PyPI - types-aiobotocore-signer](https://img.shields.io/pypi/v/types-aiobotocore-signer.svg?color=blue)](https://pypi.org/project/types-aiobotocore-signer)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-signer.svg?color=blue)](https://pypi.org/project/types-aiobotocore-signer)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_signer/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-signer?color=blue)](https://pypistats.org/packages/types-aiobotocore-signer)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.signer 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/signer.html#signer)
+[aiobotocore.signer 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/signer.html#signer)
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
 [types-aiobotocore-signer docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_signer/).
 
 See how it helps to find and fix potential bugs:
 
@@ -311,14 +311,15 @@
     SuccessfulSigningJobWaiterName,
     ValidityTypeType,
     signerServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     WaiterName,
+    RegionName,
 )
 
 
 def check_value(value: CategoryType) -> bool:
     ...
 ```
 
@@ -328,57 +329,61 @@
 
 `types_aiobotocore_signer.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_signer.type_defs import (
     AddProfilePermissionRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AddProfilePermissionResponseTypeDef,
     CancelSigningProfileRequestRequestTypeDef,
     DescribeSigningJobRequestRequestTypeDef,
     WaiterConfigTypeDef,
     SigningJobRevocationRecordTypeDef,
     SigningMaterialTypeDef,
     S3DestinationTypeDef,
+    EmptyResponseMetadataTypeDef,
     EncryptionAlgorithmOptionsTypeDef,
+    GetRevocationStatusRequestRequestTypeDef,
+    GetRevocationStatusResponseTypeDef,
     GetSigningPlatformRequestRequestTypeDef,
     SigningImageFormatTypeDef,
     GetSigningProfileRequestRequestTypeDef,
     SignatureValidityPeriodTypeDef,
     SigningProfileRevocationRecordTypeDef,
     HashAlgorithmOptionsTypeDef,
     ListProfilePermissionsRequestRequestTypeDef,
     PermissionTypeDef,
-    PaginatorConfigTypeDef,
+    ListSigningJobsRequestListSigningJobsPaginateTypeDef,
     ListSigningJobsRequestRequestTypeDef,
+    ListSigningPlatformsRequestListSigningPlatformsPaginateTypeDef,
     ListSigningPlatformsRequestRequestTypeDef,
+    ListSigningProfilesRequestListSigningProfilesPaginateTypeDef,
     ListSigningProfilesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
+    PutSigningProfileResponseTypeDef,
     RemoveProfilePermissionRequestRequestTypeDef,
+    RemoveProfilePermissionResponseTypeDef,
+    ResponseMetadataTypeDef,
     RevokeSignatureRequestRequestTypeDef,
     RevokeSigningProfileRequestRequestTypeDef,
     S3SignedObjectTypeDef,
     S3SourceTypeDef,
+    SignPayloadRequestRequestTypeDef,
+    SignPayloadResponseTypeDef,
     SigningConfigurationOverridesTypeDef,
+    StartSigningJobResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
-    AddProfilePermissionResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    PutSigningProfileResponseTypeDef,
-    RemoveProfilePermissionResponseTypeDef,
-    StartSigningJobResponseTypeDef,
     DescribeSigningJobRequestSuccessfulSigningJobWaitTypeDef,
     DestinationTypeDef,
     SigningProfileTypeDef,
     SigningConfigurationTypeDef,
     ListProfilePermissionsResponseTypeDef,
-    ListSigningJobsRequestListSigningJobsPaginateTypeDef,
-    ListSigningPlatformsRequestListSigningPlatformsPaginateTypeDef,
-    ListSigningProfilesRequestListSigningProfilesPaginateTypeDef,
     SignedObjectTypeDef,
     SourceTypeDef,
     SigningPlatformOverridesTypeDef,
     ListSigningProfilesResponseTypeDef,
     GetSigningPlatformResponseTypeDef,
     SigningPlatformTypeDef,
     SigningJobTypeDef,
@@ -398,43 +403,43 @@
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

### Comparing `types-aiobotocore-signer-2.5.0.post1/setup.py` & `types-aiobotocore-signer-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-signer.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-signer",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_signer"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.signer 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.signer 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_signer/"
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

### Comparing `types-aiobotocore-signer-2.5.0.post1/types_aiobotocore_signer/__init__.py` & `types-aiobotocore-signer-2.5.1/types_aiobotocore_signer/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-signer-2.5.0.post1/types_aiobotocore_signer/__init__.pyi` & `types-aiobotocore-signer-2.5.1/types_aiobotocore_signer/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-signer-2.5.0.post1/types_aiobotocore_signer/__main__.py` & `types-aiobotocore-signer-2.5.1/types_aiobotocore_signer/__main__.py`

 * *Files 6% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.signer 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.signer 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_signer//\nBoto3 docs: "
         "     https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/signer.html#signer\nOther"
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

### Comparing `types-aiobotocore-signer-2.5.0.post1/types_aiobotocore_signer/client.py` & `types-aiobotocore-signer-2.5.1/types_aiobotocore_signer/client.py`

 * *Files 2% similar despite different names*

```diff
@@ -12,42 +12,45 @@
     session = get_session()
     async with session.create_client("signer") as client:
         client: signerClient
     ```
 """
 import sys
 from datetime import datetime
-from typing import Any, Dict, Mapping, Sequence, Type, Union, overload
+from typing import IO, Any, Dict, Mapping, Sequence, Type, Union, overload
 
 from aiobotocore.client import AioBaseClient
+from aiobotocore.response import StreamingBody
 from botocore.client import ClientMeta
 
 from .literals import SigningProfileStatusType, SigningStatusType
 from .paginator import (
     ListSigningJobsPaginator,
     ListSigningPlatformsPaginator,
     ListSigningProfilesPaginator,
 )
 from .type_defs import (
     AddProfilePermissionResponseTypeDef,
     DescribeSigningJobResponseTypeDef,
     DestinationTypeDef,
     EmptyResponseMetadataTypeDef,
+    GetRevocationStatusResponseTypeDef,
     GetSigningPlatformResponseTypeDef,
     GetSigningProfileResponseTypeDef,
     ListProfilePermissionsResponseTypeDef,
     ListSigningJobsResponseTypeDef,
     ListSigningPlatformsResponseTypeDef,
     ListSigningProfilesResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     PutSigningProfileResponseTypeDef,
     RemoveProfilePermissionResponseTypeDef,
     SignatureValidityPeriodTypeDef,
     SigningMaterialTypeDef,
     SigningPlatformOverridesTypeDef,
+    SignPayloadResponseTypeDef,
     SourceTypeDef,
     StartSigningJobResponseTypeDef,
 )
 from .waiter import SuccessfulSigningJobWaiter
 
 if sys.version_info >= (3, 9):
     from typing import Literal
@@ -156,14 +159,31 @@
         """
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/signer.html#signer.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_signer/client/#generate_presigned_url)
         """
 
+    async def get_revocation_status(
+        self,
+        *,
+        signatureTimestamp: Union[datetime, str],
+        platformId: str,
+        profileVersionArn: str,
+        jobArn: str,
+        certificateHashes: Sequence[str]
+    ) -> GetRevocationStatusResponseTypeDef:
+        """
+        Retrieves the revocation status of one or more of the signing profile, signing
+        job, and signing certificate.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/signer.html#signer.Client.get_revocation_status)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_signer/client/#get_revocation_status)
+        """
+
     async def get_signing_platform(self, *, platformId: str) -> GetSigningPlatformResponseTypeDef:
         """
         Returns information on a specific signing platform.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/signer.html#signer.Client.get_signing_platform)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_signer/client/#get_signing_platform)
         """
@@ -300,14 +320,29 @@
         """
         Changes the state of a signing profile to REVOKED.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/signer.html#signer.Client.revoke_signing_profile)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_signer/client/#revoke_signing_profile)
         """
 
+    async def sign_payload(
+        self,
+        *,
+        profileName: str,
+        payload: Union[str, bytes, IO[Any], StreamingBody],
+        payloadFormat: str,
+        profileOwner: str = ...
+    ) -> SignPayloadResponseTypeDef:
+        """
+        Signs a binary payload and returns a signature envelope.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/signer.html#signer.Client.sign_payload)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_signer/client/#sign_payload)
+        """
+
     async def start_signing_job(
         self,
         *,
         source: SourceTypeDef,
         destination: DestinationTypeDef,
         profileName: str,
         clientRequestToken: str,
```

### Comparing `types-aiobotocore-signer-2.5.0.post1/types_aiobotocore_signer/client.pyi` & `types-aiobotocore-signer-2.5.1/types_aiobotocore_signer/client.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -12,42 +12,45 @@
     session = get_session()
     async with session.create_client("signer") as client:
         client: signerClient
     ```
 """
 import sys
 from datetime import datetime
-from typing import Any, Dict, Mapping, Sequence, Type, Union, overload
+from typing import IO, Any, Dict, Mapping, Sequence, Type, Union, overload
 
 from aiobotocore.client import AioBaseClient
+from aiobotocore.response import StreamingBody
 from botocore.client import ClientMeta
 
 from .literals import SigningProfileStatusType, SigningStatusType
 from .paginator import (
     ListSigningJobsPaginator,
     ListSigningPlatformsPaginator,
     ListSigningProfilesPaginator,
 )
 from .type_defs import (
     AddProfilePermissionResponseTypeDef,
     DescribeSigningJobResponseTypeDef,
     DestinationTypeDef,
     EmptyResponseMetadataTypeDef,
+    GetRevocationStatusResponseTypeDef,
     GetSigningPlatformResponseTypeDef,
     GetSigningProfileResponseTypeDef,
     ListProfilePermissionsResponseTypeDef,
     ListSigningJobsResponseTypeDef,
     ListSigningPlatformsResponseTypeDef,
     ListSigningProfilesResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     PutSigningProfileResponseTypeDef,
     RemoveProfilePermissionResponseTypeDef,
     SignatureValidityPeriodTypeDef,
     SigningMaterialTypeDef,
     SigningPlatformOverridesTypeDef,
+    SignPayloadResponseTypeDef,
     SourceTypeDef,
     StartSigningJobResponseTypeDef,
 )
 from .waiter import SuccessfulSigningJobWaiter
 
 if sys.version_info >= (3, 9):
     from typing import Literal
@@ -145,14 +148,30 @@
     ) -> str:
         """
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/signer.html#signer.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_signer/client/#generate_presigned_url)
         """
+    async def get_revocation_status(
+        self,
+        *,
+        signatureTimestamp: Union[datetime, str],
+        platformId: str,
+        profileVersionArn: str,
+        jobArn: str,
+        certificateHashes: Sequence[str]
+    ) -> GetRevocationStatusResponseTypeDef:
+        """
+        Retrieves the revocation status of one or more of the signing profile, signing
+        job, and signing certificate.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/signer.html#signer.Client.get_revocation_status)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_signer/client/#get_revocation_status)
+        """
     async def get_signing_platform(self, *, platformId: str) -> GetSigningPlatformResponseTypeDef:
         """
         Returns information on a specific signing platform.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/signer.html#signer.Client.get_signing_platform)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_signer/client/#get_signing_platform)
         """
@@ -278,14 +297,28 @@
     ) -> EmptyResponseMetadataTypeDef:
         """
         Changes the state of a signing profile to REVOKED.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/signer.html#signer.Client.revoke_signing_profile)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_signer/client/#revoke_signing_profile)
         """
+    async def sign_payload(
+        self,
+        *,
+        profileName: str,
+        payload: Union[str, bytes, IO[Any], StreamingBody],
+        payloadFormat: str,
+        profileOwner: str = ...
+    ) -> SignPayloadResponseTypeDef:
+        """
+        Signs a binary payload and returns a signature envelope.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/signer.html#signer.Client.sign_payload)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_signer/client/#sign_payload)
+        """
     async def start_signing_job(
         self,
         *,
         source: SourceTypeDef,
         destination: DestinationTypeDef,
         profileName: str,
         clientRequestToken: str,
```

### Comparing `types-aiobotocore-signer-2.5.0.post1/types_aiobotocore_signer/literals.py` & `types-aiobotocore-signer-2.5.1/types_aiobotocore_signer/literals.py`

 * *Files 13% similar despite different names*

```diff
@@ -32,14 +32,15 @@
     "SuccessfulSigningJobWaiterName",
     "ValidityTypeType",
     "signerServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "WaiterName",
+    "RegionName",
 )
 
 
 CategoryType = Literal["AWSIoT"]
 EncryptionAlgorithmType = Literal["ECDSA", "RSA"]
 HashAlgorithmType = Literal["SHA1", "SHA256"]
 ImageFormatType = Literal["JSON", "JSONDetached", "JSONEmbedded"]
@@ -109,14 +110,15 @@
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
@@ -195,14 +197,15 @@
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
@@ -213,14 +216,15 @@
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
@@ -256,14 +260,15 @@
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
@@ -282,16 +287,19 @@
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
@@ -375,15 +383,17 @@
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
@@ -403,7 +413,29 @@
     "opsworks",
     "s3",
     "sns",
     "sqs",
 ]
 PaginatorName = Literal["list_signing_jobs", "list_signing_platforms", "list_signing_profiles"]
 WaiterName = Literal["successful_signing_job"]
+RegionName = Literal[
+    "af-south-1",
+    "ap-east-1",
+    "ap-northeast-1",
+    "ap-northeast-2",
+    "ap-south-1",
+    "ap-southeast-1",
+    "ap-southeast-2",
+    "ca-central-1",
+    "eu-central-1",
+    "eu-north-1",
+    "eu-south-1",
+    "eu-west-1",
+    "eu-west-2",
+    "eu-west-3",
+    "me-south-1",
+    "sa-east-1",
+    "us-east-1",
+    "us-east-2",
+    "us-west-1",
+    "us-west-2",
+]
```

### Comparing `types-aiobotocore-signer-2.5.0.post1/types_aiobotocore_signer/literals.pyi` & `types-aiobotocore-signer-2.5.1/types_aiobotocore_signer/literals.pyi`

 * *Files 13% similar despite different names*

```diff
@@ -31,14 +31,15 @@
     "SuccessfulSigningJobWaiterName",
     "ValidityTypeType",
     "signerServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "WaiterName",
+    "RegionName",
 )
 
 CategoryType = Literal["AWSIoT"]
 EncryptionAlgorithmType = Literal["ECDSA", "RSA"]
 HashAlgorithmType = Literal["SHA1", "SHA256"]
 ImageFormatType = Literal["JSON", "JSONDetached", "JSONEmbedded"]
 ListSigningJobsPaginatorName = Literal["list_signing_jobs"]
@@ -107,14 +108,15 @@
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
@@ -193,14 +195,15 @@
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
@@ -211,14 +214,15 @@
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
@@ -254,14 +258,15 @@
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
@@ -280,16 +285,19 @@
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
@@ -373,15 +381,17 @@
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
@@ -401,7 +411,29 @@
     "opsworks",
     "s3",
     "sns",
     "sqs",
 ]
 PaginatorName = Literal["list_signing_jobs", "list_signing_platforms", "list_signing_profiles"]
 WaiterName = Literal["successful_signing_job"]
+RegionName = Literal[
+    "af-south-1",
+    "ap-east-1",
+    "ap-northeast-1",
+    "ap-northeast-2",
+    "ap-south-1",
+    "ap-southeast-1",
+    "ap-southeast-2",
+    "ca-central-1",
+    "eu-central-1",
+    "eu-north-1",
+    "eu-south-1",
+    "eu-west-1",
+    "eu-west-2",
+    "eu-west-3",
+    "me-south-1",
+    "sa-east-1",
+    "us-east-1",
+    "us-east-2",
+    "us-west-1",
+    "us-west-2",
+]
```

### Comparing `types-aiobotocore-signer-2.5.0.post1/types_aiobotocore_signer/paginator.py` & `types-aiobotocore-signer-2.5.1/types_aiobotocore_signer/paginator.py`

 * *Files 4% similar despite different names*

```diff
@@ -20,35 +20,28 @@
         client: signerClient
 
         list_signing_jobs_paginator: ListSigningJobsPaginator = client.get_paginator("list_signing_jobs")
         list_signing_platforms_paginator: ListSigningPlatformsPaginator = client.get_paginator("list_signing_platforms")
         list_signing_profiles_paginator: ListSigningProfilesPaginator = client.get_paginator("list_signing_profiles")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, Sequence, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import SigningProfileStatusType, SigningStatusType
 from .type_defs import (
     ListSigningJobsResponseTypeDef,
     ListSigningPlatformsResponseTypeDef,
     ListSigningProfilesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListSigningJobsPaginator",
     "ListSigningPlatformsPaginator",
     "ListSigningProfilesPaginator",
 )
 
 
@@ -74,15 +67,15 @@
         status: SigningStatusType = ...,
         platformId: str = ...,
         requestedBy: str = ...,
         isRevoked: bool = ...,
         signatureExpiresBefore: Union[datetime, str] = ...,
         signatureExpiresAfter: Union[datetime, str] = ...,
         jobInvoker: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSigningJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/signer.html#signer.Paginator.ListSigningJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_signer/paginators/#listsigningjobspaginator)
         """
 
 
@@ -94,15 +87,15 @@
 
     def paginate(
         self,
         *,
         category: str = ...,
         partner: str = ...,
         target: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSigningPlatformsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/signer.html#signer.Paginator.ListSigningPlatforms.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_signer/paginators/#listsigningplatformspaginator)
         """
 
 
@@ -114,13 +107,13 @@
 
     def paginate(
         self,
         *,
         includeCanceled: bool = ...,
         platformId: str = ...,
         statuses: Sequence[SigningProfileStatusType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSigningProfilesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/signer.html#signer.Paginator.ListSigningProfiles.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_signer/paginators/#listsigningprofilespaginator)
         """
```

### Comparing `types-aiobotocore-signer-2.5.0.post1/types_aiobotocore_signer/paginator.pyi` & `types-aiobotocore-signer-2.5.1/types_aiobotocore_signer/paginator.pyi`

 * *Files 8% similar despite different names*

```diff
@@ -20,34 +20,28 @@
         client: signerClient
 
         list_signing_jobs_paginator: ListSigningJobsPaginator = client.get_paginator("list_signing_jobs")
         list_signing_platforms_paginator: ListSigningPlatformsPaginator = client.get_paginator("list_signing_platforms")
         list_signing_profiles_paginator: ListSigningProfilesPaginator = client.get_paginator("list_signing_profiles")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, Sequence, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import SigningProfileStatusType, SigningStatusType
 from .type_defs import (
     ListSigningJobsResponseTypeDef,
     ListSigningPlatformsResponseTypeDef,
     ListSigningProfilesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListSigningJobsPaginator",
     "ListSigningPlatformsPaginator",
     "ListSigningProfilesPaginator",
 )
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
@@ -70,15 +64,15 @@
         status: SigningStatusType = ...,
         platformId: str = ...,
         requestedBy: str = ...,
         isRevoked: bool = ...,
         signatureExpiresBefore: Union[datetime, str] = ...,
         signatureExpiresAfter: Union[datetime, str] = ...,
         jobInvoker: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSigningJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/signer.html#signer.Paginator.ListSigningJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_signer/paginators/#listsigningjobspaginator)
         """
 
 class ListSigningPlatformsPaginator(AioPaginator):
@@ -89,15 +83,15 @@
 
     def paginate(
         self,
         *,
         category: str = ...,
         partner: str = ...,
         target: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSigningPlatformsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/signer.html#signer.Paginator.ListSigningPlatforms.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_signer/paginators/#listsigningplatformspaginator)
         """
 
 class ListSigningProfilesPaginator(AioPaginator):
@@ -108,13 +102,13 @@
 
     def paginate(
         self,
         *,
         includeCanceled: bool = ...,
         platformId: str = ...,
         statuses: Sequence[SigningProfileStatusType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSigningProfilesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/signer.html#signer.Paginator.ListSigningProfiles.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_signer/paginators/#listsigningprofilespaginator)
         """
```

### Comparing `types-aiobotocore-signer-2.5.0.post1/types_aiobotocore_signer/type_defs.py` & `types-aiobotocore-signer-2.5.1/types_aiobotocore_signer/type_defs.pyi`

 * *Files 8% similar despite different names*

```diff
@@ -9,15 +9,17 @@
     from types_aiobotocore_signer.type_defs import AddProfilePermissionRequestRequestTypeDef
 
     data: AddProfilePermissionRequestRequestTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
-from typing import Dict, List, Mapping, Sequence, Union
+from typing import IO, Any, Dict, List, Mapping, Sequence, Union
+
+from aiobotocore.response import StreamingBody
 
 from .literals import (
     EncryptionAlgorithmType,
     HashAlgorithmType,
     ImageFormatType,
     SigningProfileStatusType,
     SigningStatusType,
@@ -29,60 +31,63 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "AddProfilePermissionRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "AddProfilePermissionResponseTypeDef",
     "CancelSigningProfileRequestRequestTypeDef",
     "DescribeSigningJobRequestRequestTypeDef",
     "WaiterConfigTypeDef",
     "SigningJobRevocationRecordTypeDef",
     "SigningMaterialTypeDef",
     "S3DestinationTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EncryptionAlgorithmOptionsTypeDef",
+    "GetRevocationStatusRequestRequestTypeDef",
+    "GetRevocationStatusResponseTypeDef",
     "GetSigningPlatformRequestRequestTypeDef",
     "SigningImageFormatTypeDef",
     "GetSigningProfileRequestRequestTypeDef",
     "SignatureValidityPeriodTypeDef",
     "SigningProfileRevocationRecordTypeDef",
     "HashAlgorithmOptionsTypeDef",
     "ListProfilePermissionsRequestRequestTypeDef",
     "PermissionTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListSigningJobsRequestListSigningJobsPaginateTypeDef",
     "ListSigningJobsRequestRequestTypeDef",
+    "ListSigningPlatformsRequestListSigningPlatformsPaginateTypeDef",
     "ListSigningPlatformsRequestRequestTypeDef",
+    "ListSigningProfilesRequestListSigningProfilesPaginateTypeDef",
     "ListSigningProfilesRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
+    "PutSigningProfileResponseTypeDef",
     "RemoveProfilePermissionRequestRequestTypeDef",
+    "RemoveProfilePermissionResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "RevokeSignatureRequestRequestTypeDef",
     "RevokeSigningProfileRequestRequestTypeDef",
     "S3SignedObjectTypeDef",
     "S3SourceTypeDef",
+    "SignPayloadRequestRequestTypeDef",
+    "SignPayloadResponseTypeDef",
     "SigningConfigurationOverridesTypeDef",
+    "StartSigningJobResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
-    "AddProfilePermissionResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "PutSigningProfileResponseTypeDef",
-    "RemoveProfilePermissionResponseTypeDef",
-    "StartSigningJobResponseTypeDef",
     "DescribeSigningJobRequestSuccessfulSigningJobWaitTypeDef",
     "DestinationTypeDef",
     "SigningProfileTypeDef",
     "SigningConfigurationTypeDef",
     "ListProfilePermissionsResponseTypeDef",
-    "ListSigningJobsRequestListSigningJobsPaginateTypeDef",
-    "ListSigningPlatformsRequestListSigningPlatformsPaginateTypeDef",
-    "ListSigningProfilesRequestListSigningProfilesPaginateTypeDef",
     "SignedObjectTypeDef",
     "SourceTypeDef",
     "SigningPlatformOverridesTypeDef",
     "ListSigningProfilesResponseTypeDef",
     "GetSigningPlatformResponseTypeDef",
     "SigningPlatformTypeDef",
     "SigningJobTypeDef",
@@ -108,30 +113,25 @@
     {
         "profileVersion": str,
         "revisionId": str,
     },
     total=False,
 )
 
-
 class AddProfilePermissionRequestRequestTypeDef(
     _RequiredAddProfilePermissionRequestRequestTypeDef,
     _OptionalAddProfilePermissionRequestRequestTypeDef,
 ):
     pass
 
-
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AddProfilePermissionResponseTypeDef = TypedDict(
+    "AddProfilePermissionResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "revisionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CancelSigningProfileRequestRequestTypeDef = TypedDict(
     "CancelSigningProfileRequestRequestTypeDef",
     {
         "profileName": str,
@@ -176,22 +176,48 @@
     {
         "bucketName": str,
         "prefix": str,
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
 EncryptionAlgorithmOptionsTypeDef = TypedDict(
     "EncryptionAlgorithmOptionsTypeDef",
     {
         "allowedValues": List[EncryptionAlgorithmType],
         "defaultValue": EncryptionAlgorithmType,
     },
 )
 
+GetRevocationStatusRequestRequestTypeDef = TypedDict(
+    "GetRevocationStatusRequestRequestTypeDef",
+    {
+        "signatureTimestamp": Union[datetime, str],
+        "platformId": str,
+        "profileVersionArn": str,
+        "jobArn": str,
+        "certificateHashes": Sequence[str],
+    },
+)
+
+GetRevocationStatusResponseTypeDef = TypedDict(
+    "GetRevocationStatusResponseTypeDef",
+    {
+        "revokedEntities": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetSigningPlatformRequestRequestTypeDef = TypedDict(
     "GetSigningPlatformRequestRequestTypeDef",
     {
         "platformId": str,
     },
 )
 
@@ -213,21 +239,19 @@
     "_OptionalGetSigningProfileRequestRequestTypeDef",
     {
         "profileOwner": str,
     },
     total=False,
 )
 
-
 class GetSigningProfileRequestRequestTypeDef(
     _RequiredGetSigningProfileRequestRequestTypeDef, _OptionalGetSigningProfileRequestRequestTypeDef
 ):
     pass
 
-
 SignatureValidityPeriodTypeDef = TypedDict(
     "SignatureValidityPeriodTypeDef",
     {
         "value": int,
         "type": ValidityTypeType,
     },
     total=False,
@@ -261,39 +285,42 @@
     "_OptionalListProfilePermissionsRequestRequestTypeDef",
     {
         "nextToken": str,
     },
     total=False,
 )
 
-
 class ListProfilePermissionsRequestRequestTypeDef(
     _RequiredListProfilePermissionsRequestRequestTypeDef,
     _OptionalListProfilePermissionsRequestRequestTypeDef,
 ):
     pass
 
-
 PermissionTypeDef = TypedDict(
     "PermissionTypeDef",
     {
         "action": str,
         "principal": str,
         "statementId": str,
         "profileVersion": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListSigningJobsRequestListSigningJobsPaginateTypeDef = TypedDict(
+    "ListSigningJobsRequestListSigningJobsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "status": SigningStatusType,
+        "platformId": str,
+        "requestedBy": str,
+        "isRevoked": bool,
+        "signatureExpiresBefore": Union[datetime, str],
+        "signatureExpiresAfter": Union[datetime, str],
+        "jobInvoker": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListSigningJobsRequestRequestTypeDef = TypedDict(
     "ListSigningJobsRequestRequestTypeDef",
     {
@@ -306,26 +333,48 @@
         "signatureExpiresBefore": Union[datetime, str],
         "signatureExpiresAfter": Union[datetime, str],
         "jobInvoker": str,
     },
     total=False,
 )
 
+ListSigningPlatformsRequestListSigningPlatformsPaginateTypeDef = TypedDict(
+    "ListSigningPlatformsRequestListSigningPlatformsPaginateTypeDef",
+    {
+        "category": str,
+        "partner": str,
+        "target": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSigningPlatformsRequestRequestTypeDef = TypedDict(
     "ListSigningPlatformsRequestRequestTypeDef",
     {
         "category": str,
         "partner": str,
         "target": str,
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+ListSigningProfilesRequestListSigningProfilesPaginateTypeDef = TypedDict(
+    "ListSigningProfilesRequestListSigningProfilesPaginateTypeDef",
+    {
+        "includeCanceled": bool,
+        "platformId": str,
+        "statuses": Sequence[SigningProfileStatusType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSigningProfilesRequestRequestTypeDef = TypedDict(
     "ListSigningProfilesRequestRequestTypeDef",
     {
         "includeCanceled": bool,
         "maxResults": int,
         "nextToken": str,
         "platformId": str,
@@ -337,23 +386,70 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
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
+PutSigningProfileResponseTypeDef = TypedDict(
+    "PutSigningProfileResponseTypeDef",
+    {
+        "arn": str,
+        "profileVersion": str,
+        "profileVersionArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RemoveProfilePermissionRequestRequestTypeDef = TypedDict(
     "RemoveProfilePermissionRequestRequestTypeDef",
     {
         "profileName": str,
         "revisionId": str,
         "statementId": str,
     },
 )
 
+RemoveProfilePermissionResponseTypeDef = TypedDict(
+    "RemoveProfilePermissionResponseTypeDef",
+    {
+        "revisionId": str,
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
 _RequiredRevokeSignatureRequestRequestTypeDef = TypedDict(
     "_RequiredRevokeSignatureRequestRequestTypeDef",
     {
         "jobId": str,
         "reason": str,
     },
 )
@@ -361,21 +457,19 @@
     "_OptionalRevokeSignatureRequestRequestTypeDef",
     {
         "jobOwner": str,
     },
     total=False,
 )
 
-
 class RevokeSignatureRequestRequestTypeDef(
     _RequiredRevokeSignatureRequestRequestTypeDef, _OptionalRevokeSignatureRequestRequestTypeDef
 ):
     pass
 
-
 RevokeSigningProfileRequestRequestTypeDef = TypedDict(
     "RevokeSigningProfileRequestRequestTypeDef",
     {
         "profileName": str,
         "profileVersion": str,
         "reason": str,
         "effectiveTime": Union[datetime, str],
@@ -396,86 +490,77 @@
     {
         "bucketName": str,
         "key": str,
         "version": str,
     },
 )
 
-SigningConfigurationOverridesTypeDef = TypedDict(
-    "SigningConfigurationOverridesTypeDef",
+_RequiredSignPayloadRequestRequestTypeDef = TypedDict(
+    "_RequiredSignPayloadRequestRequestTypeDef",
     {
-        "encryptionAlgorithm": EncryptionAlgorithmType,
-        "hashAlgorithm": HashAlgorithmType,
-    },
-    total=False,
-)
-
-TagResourceRequestRequestTypeDef = TypedDict(
-    "TagResourceRequestRequestTypeDef",
-    {
-        "resourceArn": str,
-        "tags": Mapping[str, str],
+        "profileName": str,
+        "payload": Union[str, bytes, IO[Any], StreamingBody],
+        "payloadFormat": str,
     },
 )
-
-UntagResourceRequestRequestTypeDef = TypedDict(
-    "UntagResourceRequestRequestTypeDef",
+_OptionalSignPayloadRequestRequestTypeDef = TypedDict(
+    "_OptionalSignPayloadRequestRequestTypeDef",
     {
-        "resourceArn": str,
-        "tagKeys": Sequence[str],
+        "profileOwner": str,
     },
+    total=False,
 )
 
-AddProfilePermissionResponseTypeDef = TypedDict(
-    "AddProfilePermissionResponseTypeDef",
-    {
-        "revisionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class SignPayloadRequestRequestTypeDef(
+    _RequiredSignPayloadRequestRequestTypeDef, _OptionalSignPayloadRequestRequestTypeDef
+):
+    pass
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
+SignPayloadResponseTypeDef = TypedDict(
+    "SignPayloadResponseTypeDef",
     {
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "jobId": str,
+        "jobOwner": str,
+        "metadata": Dict[str, str],
+        "signature": bytes,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
+SigningConfigurationOverridesTypeDef = TypedDict(
+    "SigningConfigurationOverridesTypeDef",
     {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "encryptionAlgorithm": EncryptionAlgorithmType,
+        "hashAlgorithm": HashAlgorithmType,
     },
+    total=False,
 )
 
-PutSigningProfileResponseTypeDef = TypedDict(
-    "PutSigningProfileResponseTypeDef",
+StartSigningJobResponseTypeDef = TypedDict(
+    "StartSigningJobResponseTypeDef",
     {
-        "arn": str,
-        "profileVersion": str,
-        "profileVersionArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "jobId": str,
+        "jobOwner": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-RemoveProfilePermissionResponseTypeDef = TypedDict(
-    "RemoveProfilePermissionResponseTypeDef",
+TagResourceRequestRequestTypeDef = TypedDict(
+    "TagResourceRequestRequestTypeDef",
     {
-        "revisionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "resourceArn": str,
+        "tags": Mapping[str, str],
     },
 )
 
-StartSigningJobResponseTypeDef = TypedDict(
-    "StartSigningJobResponseTypeDef",
+UntagResourceRequestRequestTypeDef = TypedDict(
+    "UntagResourceRequestRequestTypeDef",
     {
-        "jobId": str,
-        "jobOwner": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "resourceArn": str,
+        "tagKeys": Sequence[str],
     },
 )
 
 _RequiredDescribeSigningJobRequestSuccessfulSigningJobWaitTypeDef = TypedDict(
     "_RequiredDescribeSigningJobRequestSuccessfulSigningJobWaitTypeDef",
     {
         "jobId": str,
@@ -485,22 +570,20 @@
     "_OptionalDescribeSigningJobRequestSuccessfulSigningJobWaitTypeDef",
     {
         "WaiterConfig": WaiterConfigTypeDef,
     },
     total=False,
 )
 
-
 class DescribeSigningJobRequestSuccessfulSigningJobWaitTypeDef(
     _RequiredDescribeSigningJobRequestSuccessfulSigningJobWaitTypeDef,
     _OptionalDescribeSigningJobRequestSuccessfulSigningJobWaitTypeDef,
 ):
     pass
 
-
 DestinationTypeDef = TypedDict(
     "DestinationTypeDef",
     {
         "s3": S3DestinationTypeDef,
     },
     total=False,
 )
@@ -534,53 +617,16 @@
 ListProfilePermissionsResponseTypeDef = TypedDict(
     "ListProfilePermissionsResponseTypeDef",
     {
         "revisionId": str,
         "policySizeBytes": int,
         "permissions": List[PermissionTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListSigningJobsRequestListSigningJobsPaginateTypeDef = TypedDict(
-    "ListSigningJobsRequestListSigningJobsPaginateTypeDef",
-    {
-        "status": SigningStatusType,
-        "platformId": str,
-        "requestedBy": str,
-        "isRevoked": bool,
-        "signatureExpiresBefore": Union[datetime, str],
-        "signatureExpiresAfter": Union[datetime, str],
-        "jobInvoker": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListSigningPlatformsRequestListSigningPlatformsPaginateTypeDef = TypedDict(
-    "ListSigningPlatformsRequestListSigningPlatformsPaginateTypeDef",
-    {
-        "category": str,
-        "partner": str,
-        "target": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
-)
-
-ListSigningProfilesRequestListSigningProfilesPaginateTypeDef = TypedDict(
-    "ListSigningProfilesRequestListSigningProfilesPaginateTypeDef",
-    {
-        "includeCanceled": bool,
-        "platformId": str,
-        "statuses": Sequence[SigningProfileStatusType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
 )
 
 SignedObjectTypeDef = TypedDict(
     "SignedObjectTypeDef",
     {
         "s3": S3SignedObjectTypeDef,
     },
@@ -605,15 +651,15 @@
 )
 
 ListSigningProfilesResponseTypeDef = TypedDict(
     "ListSigningProfilesResponseTypeDef",
     {
         "profiles": List[SigningProfileTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSigningPlatformResponseTypeDef = TypedDict(
     "GetSigningPlatformResponseTypeDef",
     {
         "platformId": str,
@@ -621,15 +667,15 @@
         "partner": str,
         "target": str,
         "category": Literal["AWSIoT"],
         "signingConfiguration": SigningConfigurationTypeDef,
         "signingImageFormat": SigningImageFormatTypeDef,
         "maxSizeInMB": int,
         "revocationSupported": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SigningPlatformTypeDef = TypedDict(
     "SigningPlatformTypeDef",
     {
         "platformId": str,
@@ -679,21 +725,19 @@
     "_OptionalStartSigningJobRequestRequestTypeDef",
     {
         "profileOwner": str,
     },
     total=False,
 )
 
-
 class StartSigningJobRequestRequestTypeDef(
     _RequiredStartSigningJobRequestRequestTypeDef, _OptionalStartSigningJobRequestRequestTypeDef
 ):
     pass
 
-
 DescribeSigningJobResponseTypeDef = TypedDict(
     "DescribeSigningJobResponseTypeDef",
     {
         "jobId": str,
         "source": SourceTypeDef,
         "signingMaterial": SigningMaterialTypeDef,
         "platformId": str,
@@ -708,15 +752,15 @@
         "requestedBy": str,
         "status": SigningStatusType,
         "statusReason": str,
         "revocationRecord": SigningJobRevocationRecordTypeDef,
         "signedObject": SignedObjectTypeDef,
         "jobOwner": str,
         "jobInvoker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSigningProfileResponseTypeDef = TypedDict(
     "GetSigningProfileResponseTypeDef",
     {
         "profileName": str,
@@ -729,15 +773,15 @@
         "signatureValidityPeriod": SignatureValidityPeriodTypeDef,
         "overrides": SigningPlatformOverridesTypeDef,
         "signingParameters": Dict[str, str],
         "status": SigningProfileStatusType,
         "statusReason": str,
         "arn": str,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutSigningProfileRequestRequestTypeDef = TypedDict(
     "_RequiredPutSigningProfileRequestRequestTypeDef",
     {
         "profileName": str,
@@ -752,31 +796,29 @@
         "overrides": SigningPlatformOverridesTypeDef,
         "signingParameters": Mapping[str, str],
         "tags": Mapping[str, str],
     },
     total=False,
 )
 
-
 class PutSigningProfileRequestRequestTypeDef(
     _RequiredPutSigningProfileRequestRequestTypeDef, _OptionalPutSigningProfileRequestRequestTypeDef
 ):
     pass
 
-
 ListSigningPlatformsResponseTypeDef = TypedDict(
     "ListSigningPlatformsResponseTypeDef",
     {
         "platforms": List[SigningPlatformTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSigningJobsResponseTypeDef = TypedDict(
     "ListSigningJobsResponseTypeDef",
     {
         "jobs": List[SigningJobTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-signer-2.5.0.post1/types_aiobotocore_signer/type_defs.pyi` & `types-aiobotocore-signer-2.5.1/types_aiobotocore_signer/type_defs.py`

 * *Files 10% similar despite different names*

```diff
@@ -9,15 +9,17 @@
     from types_aiobotocore_signer.type_defs import AddProfilePermissionRequestRequestTypeDef
 
     data: AddProfilePermissionRequestRequestTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
-from typing import Dict, List, Mapping, Sequence, Union
+from typing import IO, Any, Dict, List, Mapping, Sequence, Union
+
+from aiobotocore.response import StreamingBody
 
 from .literals import (
     EncryptionAlgorithmType,
     HashAlgorithmType,
     ImageFormatType,
     SigningProfileStatusType,
     SigningStatusType,
@@ -29,59 +31,64 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "AddProfilePermissionRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "AddProfilePermissionResponseTypeDef",
     "CancelSigningProfileRequestRequestTypeDef",
     "DescribeSigningJobRequestRequestTypeDef",
     "WaiterConfigTypeDef",
     "SigningJobRevocationRecordTypeDef",
     "SigningMaterialTypeDef",
     "S3DestinationTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EncryptionAlgorithmOptionsTypeDef",
+    "GetRevocationStatusRequestRequestTypeDef",
+    "GetRevocationStatusResponseTypeDef",
     "GetSigningPlatformRequestRequestTypeDef",
     "SigningImageFormatTypeDef",
     "GetSigningProfileRequestRequestTypeDef",
     "SignatureValidityPeriodTypeDef",
     "SigningProfileRevocationRecordTypeDef",
     "HashAlgorithmOptionsTypeDef",
     "ListProfilePermissionsRequestRequestTypeDef",
     "PermissionTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListSigningJobsRequestListSigningJobsPaginateTypeDef",
     "ListSigningJobsRequestRequestTypeDef",
+    "ListSigningPlatformsRequestListSigningPlatformsPaginateTypeDef",
     "ListSigningPlatformsRequestRequestTypeDef",
+    "ListSigningProfilesRequestListSigningProfilesPaginateTypeDef",
     "ListSigningProfilesRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
+    "PutSigningProfileResponseTypeDef",
     "RemoveProfilePermissionRequestRequestTypeDef",
+    "RemoveProfilePermissionResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "RevokeSignatureRequestRequestTypeDef",
     "RevokeSigningProfileRequestRequestTypeDef",
     "S3SignedObjectTypeDef",
     "S3SourceTypeDef",
+    "SignPayloadRequestRequestTypeDef",
+    "SignPayloadResponseTypeDef",
     "SigningConfigurationOverridesTypeDef",
+    "StartSigningJobResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
-    "AddProfilePermissionResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "PutSigningProfileResponseTypeDef",
-    "RemoveProfilePermissionResponseTypeDef",
-    "StartSigningJobResponseTypeDef",
     "DescribeSigningJobRequestSuccessfulSigningJobWaitTypeDef",
     "DestinationTypeDef",
     "SigningProfileTypeDef",
     "SigningConfigurationTypeDef",
     "ListProfilePermissionsResponseTypeDef",
-    "ListSigningJobsRequestListSigningJobsPaginateTypeDef",
-    "ListSigningPlatformsRequestListSigningPlatformsPaginateTypeDef",
-    "ListSigningProfilesRequestListSigningProfilesPaginateTypeDef",
     "SignedObjectTypeDef",
     "SourceTypeDef",
     "SigningPlatformOverridesTypeDef",
     "ListSigningProfilesResponseTypeDef",
     "GetSigningPlatformResponseTypeDef",
     "SigningPlatformTypeDef",
     "SigningJobTypeDef",
@@ -107,28 +114,27 @@
     {
         "profileVersion": str,
         "revisionId": str,
     },
     total=False,
 )
 
+
 class AddProfilePermissionRequestRequestTypeDef(
     _RequiredAddProfilePermissionRequestRequestTypeDef,
     _OptionalAddProfilePermissionRequestRequestTypeDef,
 ):
     pass
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+
+AddProfilePermissionResponseTypeDef = TypedDict(
+    "AddProfilePermissionResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "revisionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CancelSigningProfileRequestRequestTypeDef = TypedDict(
     "CancelSigningProfileRequestRequestTypeDef",
     {
         "profileName": str,
@@ -173,22 +179,48 @@
     {
         "bucketName": str,
         "prefix": str,
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
 EncryptionAlgorithmOptionsTypeDef = TypedDict(
     "EncryptionAlgorithmOptionsTypeDef",
     {
         "allowedValues": List[EncryptionAlgorithmType],
         "defaultValue": EncryptionAlgorithmType,
     },
 )
 
+GetRevocationStatusRequestRequestTypeDef = TypedDict(
+    "GetRevocationStatusRequestRequestTypeDef",
+    {
+        "signatureTimestamp": Union[datetime, str],
+        "platformId": str,
+        "profileVersionArn": str,
+        "jobArn": str,
+        "certificateHashes": Sequence[str],
+    },
+)
+
+GetRevocationStatusResponseTypeDef = TypedDict(
+    "GetRevocationStatusResponseTypeDef",
+    {
+        "revokedEntities": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetSigningPlatformRequestRequestTypeDef = TypedDict(
     "GetSigningPlatformRequestRequestTypeDef",
     {
         "platformId": str,
     },
 )
 
@@ -210,19 +242,21 @@
     "_OptionalGetSigningProfileRequestRequestTypeDef",
     {
         "profileOwner": str,
     },
     total=False,
 )
 
+
 class GetSigningProfileRequestRequestTypeDef(
     _RequiredGetSigningProfileRequestRequestTypeDef, _OptionalGetSigningProfileRequestRequestTypeDef
 ):
     pass
 
+
 SignatureValidityPeriodTypeDef = TypedDict(
     "SignatureValidityPeriodTypeDef",
     {
         "value": int,
         "type": ValidityTypeType,
     },
     total=False,
@@ -256,37 +290,44 @@
     "_OptionalListProfilePermissionsRequestRequestTypeDef",
     {
         "nextToken": str,
     },
     total=False,
 )
 
+
 class ListProfilePermissionsRequestRequestTypeDef(
     _RequiredListProfilePermissionsRequestRequestTypeDef,
     _OptionalListProfilePermissionsRequestRequestTypeDef,
 ):
     pass
 
+
 PermissionTypeDef = TypedDict(
     "PermissionTypeDef",
     {
         "action": str,
         "principal": str,
         "statementId": str,
         "profileVersion": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListSigningJobsRequestListSigningJobsPaginateTypeDef = TypedDict(
+    "ListSigningJobsRequestListSigningJobsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "status": SigningStatusType,
+        "platformId": str,
+        "requestedBy": str,
+        "isRevoked": bool,
+        "signatureExpiresBefore": Union[datetime, str],
+        "signatureExpiresAfter": Union[datetime, str],
+        "jobInvoker": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListSigningJobsRequestRequestTypeDef = TypedDict(
     "ListSigningJobsRequestRequestTypeDef",
     {
@@ -299,26 +340,48 @@
         "signatureExpiresBefore": Union[datetime, str],
         "signatureExpiresAfter": Union[datetime, str],
         "jobInvoker": str,
     },
     total=False,
 )
 
+ListSigningPlatformsRequestListSigningPlatformsPaginateTypeDef = TypedDict(
+    "ListSigningPlatformsRequestListSigningPlatformsPaginateTypeDef",
+    {
+        "category": str,
+        "partner": str,
+        "target": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSigningPlatformsRequestRequestTypeDef = TypedDict(
     "ListSigningPlatformsRequestRequestTypeDef",
     {
         "category": str,
         "partner": str,
         "target": str,
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+ListSigningProfilesRequestListSigningProfilesPaginateTypeDef = TypedDict(
+    "ListSigningProfilesRequestListSigningProfilesPaginateTypeDef",
+    {
+        "includeCanceled": bool,
+        "platformId": str,
+        "statuses": Sequence[SigningProfileStatusType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSigningProfilesRequestRequestTypeDef = TypedDict(
     "ListSigningProfilesRequestRequestTypeDef",
     {
         "includeCanceled": bool,
         "maxResults": int,
         "nextToken": str,
         "platformId": str,
@@ -330,23 +393,70 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
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
+PutSigningProfileResponseTypeDef = TypedDict(
+    "PutSigningProfileResponseTypeDef",
+    {
+        "arn": str,
+        "profileVersion": str,
+        "profileVersionArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RemoveProfilePermissionRequestRequestTypeDef = TypedDict(
     "RemoveProfilePermissionRequestRequestTypeDef",
     {
         "profileName": str,
         "revisionId": str,
         "statementId": str,
     },
 )
 
+RemoveProfilePermissionResponseTypeDef = TypedDict(
+    "RemoveProfilePermissionResponseTypeDef",
+    {
+        "revisionId": str,
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
 _RequiredRevokeSignatureRequestRequestTypeDef = TypedDict(
     "_RequiredRevokeSignatureRequestRequestTypeDef",
     {
         "jobId": str,
         "reason": str,
     },
 )
@@ -354,19 +464,21 @@
     "_OptionalRevokeSignatureRequestRequestTypeDef",
     {
         "jobOwner": str,
     },
     total=False,
 )
 
+
 class RevokeSignatureRequestRequestTypeDef(
     _RequiredRevokeSignatureRequestRequestTypeDef, _OptionalRevokeSignatureRequestRequestTypeDef
 ):
     pass
 
+
 RevokeSigningProfileRequestRequestTypeDef = TypedDict(
     "RevokeSigningProfileRequestRequestTypeDef",
     {
         "profileName": str,
         "profileVersion": str,
         "reason": str,
         "effectiveTime": Union[datetime, str],
@@ -387,86 +499,79 @@
     {
         "bucketName": str,
         "key": str,
         "version": str,
     },
 )
 
-SigningConfigurationOverridesTypeDef = TypedDict(
-    "SigningConfigurationOverridesTypeDef",
+_RequiredSignPayloadRequestRequestTypeDef = TypedDict(
+    "_RequiredSignPayloadRequestRequestTypeDef",
     {
-        "encryptionAlgorithm": EncryptionAlgorithmType,
-        "hashAlgorithm": HashAlgorithmType,
+        "profileName": str,
+        "payload": Union[str, bytes, IO[Any], StreamingBody],
+        "payloadFormat": str,
     },
-    total=False,
 )
-
-TagResourceRequestRequestTypeDef = TypedDict(
-    "TagResourceRequestRequestTypeDef",
+_OptionalSignPayloadRequestRequestTypeDef = TypedDict(
+    "_OptionalSignPayloadRequestRequestTypeDef",
     {
-        "resourceArn": str,
-        "tags": Mapping[str, str],
+        "profileOwner": str,
     },
+    total=False,
 )
 
-UntagResourceRequestRequestTypeDef = TypedDict(
-    "UntagResourceRequestRequestTypeDef",
-    {
-        "resourceArn": str,
-        "tagKeys": Sequence[str],
-    },
-)
 
-AddProfilePermissionResponseTypeDef = TypedDict(
-    "AddProfilePermissionResponseTypeDef",
-    {
-        "revisionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class SignPayloadRequestRequestTypeDef(
+    _RequiredSignPayloadRequestRequestTypeDef, _OptionalSignPayloadRequestRequestTypeDef
+):
+    pass
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
+
+SignPayloadResponseTypeDef = TypedDict(
+    "SignPayloadResponseTypeDef",
     {
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "jobId": str,
+        "jobOwner": str,
+        "metadata": Dict[str, str],
+        "signature": bytes,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
+SigningConfigurationOverridesTypeDef = TypedDict(
+    "SigningConfigurationOverridesTypeDef",
     {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "encryptionAlgorithm": EncryptionAlgorithmType,
+        "hashAlgorithm": HashAlgorithmType,
     },
+    total=False,
 )
 
-PutSigningProfileResponseTypeDef = TypedDict(
-    "PutSigningProfileResponseTypeDef",
+StartSigningJobResponseTypeDef = TypedDict(
+    "StartSigningJobResponseTypeDef",
     {
-        "arn": str,
-        "profileVersion": str,
-        "profileVersionArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "jobId": str,
+        "jobOwner": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-RemoveProfilePermissionResponseTypeDef = TypedDict(
-    "RemoveProfilePermissionResponseTypeDef",
+TagResourceRequestRequestTypeDef = TypedDict(
+    "TagResourceRequestRequestTypeDef",
     {
-        "revisionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "resourceArn": str,
+        "tags": Mapping[str, str],
     },
 )
 
-StartSigningJobResponseTypeDef = TypedDict(
-    "StartSigningJobResponseTypeDef",
+UntagResourceRequestRequestTypeDef = TypedDict(
+    "UntagResourceRequestRequestTypeDef",
     {
-        "jobId": str,
-        "jobOwner": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "resourceArn": str,
+        "tagKeys": Sequence[str],
     },
 )
 
 _RequiredDescribeSigningJobRequestSuccessfulSigningJobWaitTypeDef = TypedDict(
     "_RequiredDescribeSigningJobRequestSuccessfulSigningJobWaitTypeDef",
     {
         "jobId": str,
@@ -476,20 +581,22 @@
     "_OptionalDescribeSigningJobRequestSuccessfulSigningJobWaitTypeDef",
     {
         "WaiterConfig": WaiterConfigTypeDef,
     },
     total=False,
 )
 
+
 class DescribeSigningJobRequestSuccessfulSigningJobWaitTypeDef(
     _RequiredDescribeSigningJobRequestSuccessfulSigningJobWaitTypeDef,
     _OptionalDescribeSigningJobRequestSuccessfulSigningJobWaitTypeDef,
 ):
     pass
 
+
 DestinationTypeDef = TypedDict(
     "DestinationTypeDef",
     {
         "s3": S3DestinationTypeDef,
     },
     total=False,
 )
@@ -523,53 +630,16 @@
 ListProfilePermissionsResponseTypeDef = TypedDict(
     "ListProfilePermissionsResponseTypeDef",
     {
         "revisionId": str,
         "policySizeBytes": int,
         "permissions": List[PermissionTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListSigningJobsRequestListSigningJobsPaginateTypeDef = TypedDict(
-    "ListSigningJobsRequestListSigningJobsPaginateTypeDef",
-    {
-        "status": SigningStatusType,
-        "platformId": str,
-        "requestedBy": str,
-        "isRevoked": bool,
-        "signatureExpiresBefore": Union[datetime, str],
-        "signatureExpiresAfter": Union[datetime, str],
-        "jobInvoker": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListSigningPlatformsRequestListSigningPlatformsPaginateTypeDef = TypedDict(
-    "ListSigningPlatformsRequestListSigningPlatformsPaginateTypeDef",
-    {
-        "category": str,
-        "partner": str,
-        "target": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
-)
-
-ListSigningProfilesRequestListSigningProfilesPaginateTypeDef = TypedDict(
-    "ListSigningProfilesRequestListSigningProfilesPaginateTypeDef",
-    {
-        "includeCanceled": bool,
-        "platformId": str,
-        "statuses": Sequence[SigningProfileStatusType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
 )
 
 SignedObjectTypeDef = TypedDict(
     "SignedObjectTypeDef",
     {
         "s3": S3SignedObjectTypeDef,
     },
@@ -594,15 +664,15 @@
 )
 
 ListSigningProfilesResponseTypeDef = TypedDict(
     "ListSigningProfilesResponseTypeDef",
     {
         "profiles": List[SigningProfileTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSigningPlatformResponseTypeDef = TypedDict(
     "GetSigningPlatformResponseTypeDef",
     {
         "platformId": str,
@@ -610,15 +680,15 @@
         "partner": str,
         "target": str,
         "category": Literal["AWSIoT"],
         "signingConfiguration": SigningConfigurationTypeDef,
         "signingImageFormat": SigningImageFormatTypeDef,
         "maxSizeInMB": int,
         "revocationSupported": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SigningPlatformTypeDef = TypedDict(
     "SigningPlatformTypeDef",
     {
         "platformId": str,
@@ -668,19 +738,21 @@
     "_OptionalStartSigningJobRequestRequestTypeDef",
     {
         "profileOwner": str,
     },
     total=False,
 )
 
+
 class StartSigningJobRequestRequestTypeDef(
     _RequiredStartSigningJobRequestRequestTypeDef, _OptionalStartSigningJobRequestRequestTypeDef
 ):
     pass
 
+
 DescribeSigningJobResponseTypeDef = TypedDict(
     "DescribeSigningJobResponseTypeDef",
     {
         "jobId": str,
         "source": SourceTypeDef,
         "signingMaterial": SigningMaterialTypeDef,
         "platformId": str,
@@ -695,15 +767,15 @@
         "requestedBy": str,
         "status": SigningStatusType,
         "statusReason": str,
         "revocationRecord": SigningJobRevocationRecordTypeDef,
         "signedObject": SignedObjectTypeDef,
         "jobOwner": str,
         "jobInvoker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSigningProfileResponseTypeDef = TypedDict(
     "GetSigningProfileResponseTypeDef",
     {
         "profileName": str,
@@ -716,15 +788,15 @@
         "signatureValidityPeriod": SignatureValidityPeriodTypeDef,
         "overrides": SigningPlatformOverridesTypeDef,
         "signingParameters": Dict[str, str],
         "status": SigningProfileStatusType,
         "statusReason": str,
         "arn": str,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutSigningProfileRequestRequestTypeDef = TypedDict(
     "_RequiredPutSigningProfileRequestRequestTypeDef",
     {
         "profileName": str,
@@ -739,29 +811,31 @@
         "overrides": SigningPlatformOverridesTypeDef,
         "signingParameters": Mapping[str, str],
         "tags": Mapping[str, str],
     },
     total=False,
 )
 
+
 class PutSigningProfileRequestRequestTypeDef(
     _RequiredPutSigningProfileRequestRequestTypeDef, _OptionalPutSigningProfileRequestRequestTypeDef
 ):
     pass
 
+
 ListSigningPlatformsResponseTypeDef = TypedDict(
     "ListSigningPlatformsResponseTypeDef",
     {
         "platforms": List[SigningPlatformTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSigningJobsResponseTypeDef = TypedDict(
     "ListSigningJobsResponseTypeDef",
     {
         "jobs": List[SigningJobTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-signer-2.5.0.post1/types_aiobotocore_signer/waiter.py` & `types-aiobotocore-signer-2.5.1/types_aiobotocore_signer/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-signer-2.5.0.post1/types_aiobotocore_signer/waiter.pyi` & `types-aiobotocore-signer-2.5.1/types_aiobotocore_signer/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-signer-2.5.0.post1/types_aiobotocore_signer.egg-info/PKG-INFO` & `types-aiobotocore-signer-2.5.1/types_aiobotocore_signer.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-signer
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.signer 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.signer 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_signer/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-signer"></a>
 
 # types-aiobotocore-signer
 
 [![PyPI - types-aiobotocore-signer](https://img.shields.io/pypi/v/types-aiobotocore-signer.svg?color=blue)](https://pypi.org/project/types-aiobotocore-signer)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-signer.svg?color=blue)](https://pypi.org/project/types-aiobotocore-signer)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_signer/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-signer?color=blue)](https://pypistats.org/packages/types-aiobotocore-signer)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.signer 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/signer.html#signer)
+[aiobotocore.signer 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/signer.html#signer)
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
 [types-aiobotocore-signer docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_signer/).
 
 See how it helps to find and fix potential bugs:
 
@@ -344,14 +344,15 @@
     SuccessfulSigningJobWaiterName,
     ValidityTypeType,
     signerServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     WaiterName,
+    RegionName,
 )
 
 
 def check_value(value: CategoryType) -> bool:
     ...
 ```
 
@@ -361,57 +362,61 @@
 
 `types_aiobotocore_signer.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_signer.type_defs import (
     AddProfilePermissionRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AddProfilePermissionResponseTypeDef,
     CancelSigningProfileRequestRequestTypeDef,
     DescribeSigningJobRequestRequestTypeDef,
     WaiterConfigTypeDef,
     SigningJobRevocationRecordTypeDef,
     SigningMaterialTypeDef,
     S3DestinationTypeDef,
+    EmptyResponseMetadataTypeDef,
     EncryptionAlgorithmOptionsTypeDef,
+    GetRevocationStatusRequestRequestTypeDef,
+    GetRevocationStatusResponseTypeDef,
     GetSigningPlatformRequestRequestTypeDef,
     SigningImageFormatTypeDef,
     GetSigningProfileRequestRequestTypeDef,
     SignatureValidityPeriodTypeDef,
     SigningProfileRevocationRecordTypeDef,
     HashAlgorithmOptionsTypeDef,
     ListProfilePermissionsRequestRequestTypeDef,
     PermissionTypeDef,
-    PaginatorConfigTypeDef,
+    ListSigningJobsRequestListSigningJobsPaginateTypeDef,
     ListSigningJobsRequestRequestTypeDef,
+    ListSigningPlatformsRequestListSigningPlatformsPaginateTypeDef,
     ListSigningPlatformsRequestRequestTypeDef,
+    ListSigningProfilesRequestListSigningProfilesPaginateTypeDef,
     ListSigningProfilesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
+    PutSigningProfileResponseTypeDef,
     RemoveProfilePermissionRequestRequestTypeDef,
+    RemoveProfilePermissionResponseTypeDef,
+    ResponseMetadataTypeDef,
     RevokeSignatureRequestRequestTypeDef,
     RevokeSigningProfileRequestRequestTypeDef,
     S3SignedObjectTypeDef,
     S3SourceTypeDef,
+    SignPayloadRequestRequestTypeDef,
+    SignPayloadResponseTypeDef,
     SigningConfigurationOverridesTypeDef,
+    StartSigningJobResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
-    AddProfilePermissionResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    PutSigningProfileResponseTypeDef,
-    RemoveProfilePermissionResponseTypeDef,
-    StartSigningJobResponseTypeDef,
     DescribeSigningJobRequestSuccessfulSigningJobWaitTypeDef,
     DestinationTypeDef,
     SigningProfileTypeDef,
     SigningConfigurationTypeDef,
     ListProfilePermissionsResponseTypeDef,
-    ListSigningJobsRequestListSigningJobsPaginateTypeDef,
-    ListSigningPlatformsRequestListSigningPlatformsPaginateTypeDef,
-    ListSigningProfilesRequestListSigningProfilesPaginateTypeDef,
     SignedObjectTypeDef,
     SourceTypeDef,
     SigningPlatformOverridesTypeDef,
     ListSigningProfilesResponseTypeDef,
     GetSigningPlatformResponseTypeDef,
     SigningPlatformTypeDef,
     SigningJobTypeDef,
@@ -431,43 +436,43 @@
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

### Comparing `types-aiobotocore-signer-2.5.0.post1/types_aiobotocore_signer.egg-info/SOURCES.txt` & `types-aiobotocore-signer-2.5.1/types_aiobotocore_signer.egg-info/SOURCES.txt`

 * *Files identical despite different names*

