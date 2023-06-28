# Comparing `tmp/types-aiobotocore-kms-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-kms-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-kms-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:51 2023, max compression
+gzip compressed data, was "types-aiobotocore-kms-2.5.1.tar", last modified: Wed Jun 28 01:43:44 2023, max compression
```

## Comparing `types-aiobotocore-kms-2.5.0.post1.tar` & `types-aiobotocore-kms-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:51.835348 types-aiobotocore-kms-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:17:04.000000 types-aiobotocore-kms-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    18134 2023-03-11 12:26:51.831348 types-aiobotocore-kms-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    16579 2023-03-11 12:17:04.000000 types-aiobotocore-kms-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:51.835348 types-aiobotocore-kms-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2072 2023-03-11 12:17:04.000000 types-aiobotocore-kms-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:51.831348 types-aiobotocore-kms-2.5.0.post1/types_aiobotocore_kms/
--rw-r--r--   0 runner    (1001) docker     (123)     1813 2023-03-11 12:17:04.000000 types-aiobotocore-kms-2.5.0.post1/types_aiobotocore_kms/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1812 2023-03-11 12:17:04.000000 types-aiobotocore-kms-2.5.0.post1/types_aiobotocore_kms/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      916 2023-03-11 12:17:04.000000 types-aiobotocore-kms-2.5.0.post1/types_aiobotocore_kms/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    42848 2023-03-11 12:17:06.000000 types-aiobotocore-kms-2.5.0.post1/types_aiobotocore_kms/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    42782 2023-03-11 12:17:05.000000 types-aiobotocore-kms-2.5.0.post1/types_aiobotocore_kms/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    12537 2023-03-11 12:17:07.000000 types-aiobotocore-kms-2.5.0.post1/types_aiobotocore_kms/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    12535 2023-03-11 12:17:07.000000 types-aiobotocore-kms-2.5.0.post1/types_aiobotocore_kms/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8538 2023-03-11 12:17:06.000000 types-aiobotocore-kms-2.5.0.post1/types_aiobotocore_kms/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     8528 2023-03-11 12:17:06.000000 types-aiobotocore-kms-2.5.0.post1/types_aiobotocore_kms/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:17:04.000000 types-aiobotocore-kms-2.5.0.post1/types_aiobotocore_kms/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    39706 2023-03-11 12:17:07.000000 types-aiobotocore-kms-2.5.0.post1/types_aiobotocore_kms/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    39647 2023-03-11 12:17:07.000000 types-aiobotocore-kms-2.5.0.post1/types_aiobotocore_kms/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:17:04.000000 types-aiobotocore-kms-2.5.0.post1/types_aiobotocore_kms/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:51.831348 types-aiobotocore-kms-2.5.0.post1/types_aiobotocore_kms.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    18134 2023-03-11 12:26:51.000000 types-aiobotocore-kms-2.5.0.post1/types_aiobotocore_kms.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      737 2023-03-11 12:26:51.000000 types-aiobotocore-kms-2.5.0.post1/types_aiobotocore_kms.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:51.000000 types-aiobotocore-kms-2.5.0.post1/types_aiobotocore_kms.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:51.000000 types-aiobotocore-kms-2.5.0.post1/types_aiobotocore_kms.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:51.000000 types-aiobotocore-kms-2.5.0.post1/types_aiobotocore_kms.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-03-11 12:26:51.000000 types-aiobotocore-kms-2.5.0.post1/types_aiobotocore_kms.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:44.266164 types-aiobotocore-kms-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:33:46.000000 types-aiobotocore-kms-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    18180 2023-06-28 01:43:44.266164 types-aiobotocore-kms-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    16631 2023-06-28 01:33:46.000000 types-aiobotocore-kms-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:44.266164 types-aiobotocore-kms-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2066 2023-06-28 01:33:46.000000 types-aiobotocore-kms-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:44.262164 types-aiobotocore-kms-2.5.1/types_aiobotocore_kms/
+-rw-r--r--   0 runner    (1001) docker     (123)     1813 2023-06-28 01:33:46.000000 types-aiobotocore-kms-2.5.1/types_aiobotocore_kms/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1812 2023-06-28 01:33:46.000000 types-aiobotocore-kms-2.5.1/types_aiobotocore_kms/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      904 2023-06-28 01:33:46.000000 types-aiobotocore-kms-2.5.1/types_aiobotocore_kms/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    43136 2023-06-28 01:33:46.000000 types-aiobotocore-kms-2.5.1/types_aiobotocore_kms/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    43070 2023-06-28 01:33:46.000000 types-aiobotocore-kms-2.5.1/types_aiobotocore_kms/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    12946 2023-06-28 01:33:46.000000 types-aiobotocore-kms-2.5.1/types_aiobotocore_kms/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12944 2023-06-28 01:33:46.000000 types-aiobotocore-kms-2.5.1/types_aiobotocore_kms/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8432 2023-06-28 01:33:46.000000 types-aiobotocore-kms-2.5.1/types_aiobotocore_kms/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8423 2023-06-28 01:33:46.000000 types-aiobotocore-kms-2.5.1/types_aiobotocore_kms/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:33:46.000000 types-aiobotocore-kms-2.5.1/types_aiobotocore_kms/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    40403 2023-06-28 01:33:47.000000 types-aiobotocore-kms-2.5.1/types_aiobotocore_kms/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    40344 2023-06-28 01:33:47.000000 types-aiobotocore-kms-2.5.1/types_aiobotocore_kms/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:33:46.000000 types-aiobotocore-kms-2.5.1/types_aiobotocore_kms/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:44.266164 types-aiobotocore-kms-2.5.1/types_aiobotocore_kms.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    18180 2023-06-28 01:43:44.000000 types-aiobotocore-kms-2.5.1/types_aiobotocore_kms.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      737 2023-06-28 01:43:44.000000 types-aiobotocore-kms-2.5.1/types_aiobotocore_kms.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:44.000000 types-aiobotocore-kms-2.5.1/types_aiobotocore_kms.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:44.000000 types-aiobotocore-kms-2.5.1/types_aiobotocore_kms.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:44.000000 types-aiobotocore-kms-2.5.1/types_aiobotocore_kms.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 01:43:44.000000 types-aiobotocore-kms-2.5.1/types_aiobotocore_kms.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-kms-2.5.0.post1/LICENSE` & `types-aiobotocore-kms-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-kms-2.5.0.post1/PKG-INFO` & `types-aiobotocore-kms-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-kms
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.KMS 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.KMS 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-kms"></a>
 
 # types-aiobotocore-kms
 
 [![PyPI - types-aiobotocore-kms](https://img.shields.io/pypi/v/types-aiobotocore-kms.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kms)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-kms.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kms)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-kms?color=blue)](https://pypistats.org/packages/types-aiobotocore-kms)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.KMS 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS)
+[aiobotocore.KMS 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS)
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
 [types-aiobotocore-kms docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/).
 
 See how it helps to find and fix potential bugs:
 
@@ -323,14 +323,15 @@
     CustomerMasterKeySpecType,
     DataKeyPairSpecType,
     DataKeySpecType,
     DescribeCustomKeyStoresPaginatorName,
     EncryptionAlgorithmSpecType,
     ExpirationModelTypeType,
     GrantOperationType,
+    KeyEncryptionMechanismType,
     KeyManagerTypeType,
     KeySpecType,
     KeyStateType,
     KeyUsageTypeType,
     ListAliasesPaginatorName,
     ListGrantsPaginatorName,
     ListKeyPoliciesPaginatorName,
@@ -363,105 +364,106 @@
 `types_aiobotocore_kms.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_kms.type_defs import (
     AliasListEntryTypeDef,
     CancelKeyDeletionRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CancelKeyDeletionResponseTypeDef,
     ConnectCustomKeyStoreRequestRequestTypeDef,
     CreateAliasRequestRequestTypeDef,
     XksProxyAuthenticationCredentialTypeTypeDef,
+    CreateCustomKeyStoreResponseTypeDef,
     GrantConstraintsTypeDef,
+    CreateGrantResponseTypeDef,
     TagTypeDef,
     XksProxyConfigurationTypeTypeDef,
-    DecryptRequestRequestTypeDef,
+    RecipientInfoTypeDef,
+    DecryptResponseTypeDef,
     DeleteAliasRequestRequestTypeDef,
     DeleteCustomKeyStoreRequestRequestTypeDef,
     DeleteImportedKeyMaterialRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeCustomKeyStoresRequestDescribeCustomKeyStoresPaginateTypeDef,
     DescribeCustomKeyStoresRequestRequestTypeDef,
     DescribeKeyRequestRequestTypeDef,
     DisableKeyRequestRequestTypeDef,
     DisableKeyRotationRequestRequestTypeDef,
     DisconnectCustomKeyStoreRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EnableKeyRequestRequestTypeDef,
     EnableKeyRotationRequestRequestTypeDef,
     EncryptRequestRequestTypeDef,
-    GenerateDataKeyPairRequestRequestTypeDef,
+    EncryptResponseTypeDef,
+    GenerateDataKeyPairResponseTypeDef,
     GenerateDataKeyPairWithoutPlaintextRequestRequestTypeDef,
-    GenerateDataKeyRequestRequestTypeDef,
+    GenerateDataKeyPairWithoutPlaintextResponseTypeDef,
+    GenerateDataKeyResponseTypeDef,
     GenerateDataKeyWithoutPlaintextRequestRequestTypeDef,
+    GenerateDataKeyWithoutPlaintextResponseTypeDef,
     GenerateMacRequestRequestTypeDef,
-    GenerateRandomRequestRequestTypeDef,
+    GenerateMacResponseTypeDef,
+    GenerateRandomResponseTypeDef,
     GetKeyPolicyRequestRequestTypeDef,
+    GetKeyPolicyResponseTypeDef,
     GetKeyRotationStatusRequestRequestTypeDef,
+    GetKeyRotationStatusResponseTypeDef,
     GetParametersForImportRequestRequestTypeDef,
+    GetParametersForImportResponseTypeDef,
     GetPublicKeyRequestRequestTypeDef,
+    GetPublicKeyResponseTypeDef,
     ImportKeyMaterialRequestRequestTypeDef,
     KeyListEntryTypeDef,
     XksKeyConfigurationTypeTypeDef,
+    ListAliasesRequestListAliasesPaginateTypeDef,
     ListAliasesRequestRequestTypeDef,
+    ListGrantsRequestListGrantsPaginateTypeDef,
     ListGrantsRequestRequestTypeDef,
+    ListKeyPoliciesRequestListKeyPoliciesPaginateTypeDef,
     ListKeyPoliciesRequestRequestTypeDef,
+    ListKeyPoliciesResponseTypeDef,
+    ListKeysRequestListKeysPaginateTypeDef,
     ListKeysRequestRequestTypeDef,
+    ListResourceTagsRequestListResourceTagsPaginateTypeDef,
     ListResourceTagsRequestRequestTypeDef,
+    ListRetirableGrantsRequestListRetirableGrantsPaginateTypeDef,
     ListRetirableGrantsRequestRequestTypeDef,
     MultiRegionKeyTypeDef,
+    PaginatorConfigTypeDef,
     PutKeyPolicyRequestRequestTypeDef,
     ReEncryptRequestRequestTypeDef,
+    ReEncryptResponseTypeDef,
+    ResponseMetadataTypeDef,
     RetireGrantRequestRequestTypeDef,
     RevokeGrantRequestRequestTypeDef,
     ScheduleKeyDeletionRequestRequestTypeDef,
+    ScheduleKeyDeletionResponseTypeDef,
     SignRequestRequestTypeDef,
+    SignResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateAliasRequestRequestTypeDef,
     UpdateKeyDescriptionRequestRequestTypeDef,
     UpdatePrimaryRegionRequestRequestTypeDef,
     VerifyMacRequestRequestTypeDef,
-    VerifyRequestRequestTypeDef,
-    CancelKeyDeletionResponseTypeDef,
-    CreateCustomKeyStoreResponseTypeDef,
-    CreateGrantResponseTypeDef,
-    DecryptResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    EncryptResponseTypeDef,
-    GenerateDataKeyPairResponseTypeDef,
-    GenerateDataKeyPairWithoutPlaintextResponseTypeDef,
-    GenerateDataKeyResponseTypeDef,
-    GenerateDataKeyWithoutPlaintextResponseTypeDef,
-    GenerateMacResponseTypeDef,
-    GenerateRandomResponseTypeDef,
-    GetKeyPolicyResponseTypeDef,
-    GetKeyRotationStatusResponseTypeDef,
-    GetParametersForImportResponseTypeDef,
-    GetPublicKeyResponseTypeDef,
-    ListAliasesResponseTypeDef,
-    ListKeyPoliciesResponseTypeDef,
-    ReEncryptResponseTypeDef,
-    ScheduleKeyDeletionResponseTypeDef,
-    SignResponseTypeDef,
     VerifyMacResponseTypeDef,
+    VerifyRequestRequestTypeDef,
     VerifyResponseTypeDef,
+    ListAliasesResponseTypeDef,
     CreateCustomKeyStoreRequestRequestTypeDef,
     UpdateCustomKeyStoreRequestRequestTypeDef,
     CreateGrantRequestRequestTypeDef,
     GrantListEntryTypeDef,
     CreateKeyRequestRequestTypeDef,
     ListResourceTagsResponseTypeDef,
     ReplicateKeyRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     CustomKeyStoresListEntryTypeDef,
-    DescribeCustomKeyStoresRequestDescribeCustomKeyStoresPaginateTypeDef,
-    ListAliasesRequestListAliasesPaginateTypeDef,
-    ListGrantsRequestListGrantsPaginateTypeDef,
-    ListKeyPoliciesRequestListKeyPoliciesPaginateTypeDef,
-    ListKeysRequestListKeysPaginateTypeDef,
-    ListResourceTagsRequestListResourceTagsPaginateTypeDef,
-    ListRetirableGrantsRequestListRetirableGrantsPaginateTypeDef,
+    DecryptRequestRequestTypeDef,
+    GenerateDataKeyPairRequestRequestTypeDef,
+    GenerateDataKeyRequestRequestTypeDef,
+    GenerateRandomRequestRequestTypeDef,
     ListKeysResponseTypeDef,
     MultiRegionConfigurationTypeDef,
     ListGrantsResponseTypeDef,
     DescribeCustomKeyStoresResponseTypeDef,
     KeyMetadataTypeDef,
     CreateKeyResponseTypeDef,
     DescribeKeyResponseTypeDef,
@@ -476,43 +478,43 @@
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

### Comparing `types-aiobotocore-kms-2.5.0.post1/README.md` & `types-aiobotocore-kms-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-kms"></a>
 
 # types-aiobotocore-kms
 
 [![PyPI - types-aiobotocore-kms](https://img.shields.io/pypi/v/types-aiobotocore-kms.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kms)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-kms.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kms)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-kms?color=blue)](https://pypistats.org/packages/types-aiobotocore-kms)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.KMS 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS)
+[aiobotocore.KMS 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS)
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
 [types-aiobotocore-kms docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/).
 
 See how it helps to find and fix potential bugs:
 
@@ -290,14 +290,15 @@
     CustomerMasterKeySpecType,
     DataKeyPairSpecType,
     DataKeySpecType,
     DescribeCustomKeyStoresPaginatorName,
     EncryptionAlgorithmSpecType,
     ExpirationModelTypeType,
     GrantOperationType,
+    KeyEncryptionMechanismType,
     KeyManagerTypeType,
     KeySpecType,
     KeyStateType,
     KeyUsageTypeType,
     ListAliasesPaginatorName,
     ListGrantsPaginatorName,
     ListKeyPoliciesPaginatorName,
@@ -330,105 +331,106 @@
 `types_aiobotocore_kms.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_kms.type_defs import (
     AliasListEntryTypeDef,
     CancelKeyDeletionRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CancelKeyDeletionResponseTypeDef,
     ConnectCustomKeyStoreRequestRequestTypeDef,
     CreateAliasRequestRequestTypeDef,
     XksProxyAuthenticationCredentialTypeTypeDef,
+    CreateCustomKeyStoreResponseTypeDef,
     GrantConstraintsTypeDef,
+    CreateGrantResponseTypeDef,
     TagTypeDef,
     XksProxyConfigurationTypeTypeDef,
-    DecryptRequestRequestTypeDef,
+    RecipientInfoTypeDef,
+    DecryptResponseTypeDef,
     DeleteAliasRequestRequestTypeDef,
     DeleteCustomKeyStoreRequestRequestTypeDef,
     DeleteImportedKeyMaterialRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeCustomKeyStoresRequestDescribeCustomKeyStoresPaginateTypeDef,
     DescribeCustomKeyStoresRequestRequestTypeDef,
     DescribeKeyRequestRequestTypeDef,
     DisableKeyRequestRequestTypeDef,
     DisableKeyRotationRequestRequestTypeDef,
     DisconnectCustomKeyStoreRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EnableKeyRequestRequestTypeDef,
     EnableKeyRotationRequestRequestTypeDef,
     EncryptRequestRequestTypeDef,
-    GenerateDataKeyPairRequestRequestTypeDef,
+    EncryptResponseTypeDef,
+    GenerateDataKeyPairResponseTypeDef,
     GenerateDataKeyPairWithoutPlaintextRequestRequestTypeDef,
-    GenerateDataKeyRequestRequestTypeDef,
+    GenerateDataKeyPairWithoutPlaintextResponseTypeDef,
+    GenerateDataKeyResponseTypeDef,
     GenerateDataKeyWithoutPlaintextRequestRequestTypeDef,
+    GenerateDataKeyWithoutPlaintextResponseTypeDef,
     GenerateMacRequestRequestTypeDef,
-    GenerateRandomRequestRequestTypeDef,
+    GenerateMacResponseTypeDef,
+    GenerateRandomResponseTypeDef,
     GetKeyPolicyRequestRequestTypeDef,
+    GetKeyPolicyResponseTypeDef,
     GetKeyRotationStatusRequestRequestTypeDef,
+    GetKeyRotationStatusResponseTypeDef,
     GetParametersForImportRequestRequestTypeDef,
+    GetParametersForImportResponseTypeDef,
     GetPublicKeyRequestRequestTypeDef,
+    GetPublicKeyResponseTypeDef,
     ImportKeyMaterialRequestRequestTypeDef,
     KeyListEntryTypeDef,
     XksKeyConfigurationTypeTypeDef,
+    ListAliasesRequestListAliasesPaginateTypeDef,
     ListAliasesRequestRequestTypeDef,
+    ListGrantsRequestListGrantsPaginateTypeDef,
     ListGrantsRequestRequestTypeDef,
+    ListKeyPoliciesRequestListKeyPoliciesPaginateTypeDef,
     ListKeyPoliciesRequestRequestTypeDef,
+    ListKeyPoliciesResponseTypeDef,
+    ListKeysRequestListKeysPaginateTypeDef,
     ListKeysRequestRequestTypeDef,
+    ListResourceTagsRequestListResourceTagsPaginateTypeDef,
     ListResourceTagsRequestRequestTypeDef,
+    ListRetirableGrantsRequestListRetirableGrantsPaginateTypeDef,
     ListRetirableGrantsRequestRequestTypeDef,
     MultiRegionKeyTypeDef,
+    PaginatorConfigTypeDef,
     PutKeyPolicyRequestRequestTypeDef,
     ReEncryptRequestRequestTypeDef,
+    ReEncryptResponseTypeDef,
+    ResponseMetadataTypeDef,
     RetireGrantRequestRequestTypeDef,
     RevokeGrantRequestRequestTypeDef,
     ScheduleKeyDeletionRequestRequestTypeDef,
+    ScheduleKeyDeletionResponseTypeDef,
     SignRequestRequestTypeDef,
+    SignResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateAliasRequestRequestTypeDef,
     UpdateKeyDescriptionRequestRequestTypeDef,
     UpdatePrimaryRegionRequestRequestTypeDef,
     VerifyMacRequestRequestTypeDef,
-    VerifyRequestRequestTypeDef,
-    CancelKeyDeletionResponseTypeDef,
-    CreateCustomKeyStoreResponseTypeDef,
-    CreateGrantResponseTypeDef,
-    DecryptResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    EncryptResponseTypeDef,
-    GenerateDataKeyPairResponseTypeDef,
-    GenerateDataKeyPairWithoutPlaintextResponseTypeDef,
-    GenerateDataKeyResponseTypeDef,
-    GenerateDataKeyWithoutPlaintextResponseTypeDef,
-    GenerateMacResponseTypeDef,
-    GenerateRandomResponseTypeDef,
-    GetKeyPolicyResponseTypeDef,
-    GetKeyRotationStatusResponseTypeDef,
-    GetParametersForImportResponseTypeDef,
-    GetPublicKeyResponseTypeDef,
-    ListAliasesResponseTypeDef,
-    ListKeyPoliciesResponseTypeDef,
-    ReEncryptResponseTypeDef,
-    ScheduleKeyDeletionResponseTypeDef,
-    SignResponseTypeDef,
     VerifyMacResponseTypeDef,
+    VerifyRequestRequestTypeDef,
     VerifyResponseTypeDef,
+    ListAliasesResponseTypeDef,
     CreateCustomKeyStoreRequestRequestTypeDef,
     UpdateCustomKeyStoreRequestRequestTypeDef,
     CreateGrantRequestRequestTypeDef,
     GrantListEntryTypeDef,
     CreateKeyRequestRequestTypeDef,
     ListResourceTagsResponseTypeDef,
     ReplicateKeyRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     CustomKeyStoresListEntryTypeDef,
-    DescribeCustomKeyStoresRequestDescribeCustomKeyStoresPaginateTypeDef,
-    ListAliasesRequestListAliasesPaginateTypeDef,
-    ListGrantsRequestListGrantsPaginateTypeDef,
-    ListKeyPoliciesRequestListKeyPoliciesPaginateTypeDef,
-    ListKeysRequestListKeysPaginateTypeDef,
-    ListResourceTagsRequestListResourceTagsPaginateTypeDef,
-    ListRetirableGrantsRequestListRetirableGrantsPaginateTypeDef,
+    DecryptRequestRequestTypeDef,
+    GenerateDataKeyPairRequestRequestTypeDef,
+    GenerateDataKeyRequestRequestTypeDef,
+    GenerateRandomRequestRequestTypeDef,
     ListKeysResponseTypeDef,
     MultiRegionConfigurationTypeDef,
     ListGrantsResponseTypeDef,
     DescribeCustomKeyStoresResponseTypeDef,
     KeyMetadataTypeDef,
     CreateKeyResponseTypeDef,
     DescribeKeyResponseTypeDef,
@@ -443,43 +445,43 @@
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

### Comparing `types-aiobotocore-kms-2.5.0.post1/setup.py` & `types-aiobotocore-kms-2.5.1/setup.py`

 * *Files 11% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-kms.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-kms",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_kms"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.KMS 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.KMS 2.5.1 service generated with mypy-boto3-builder"
+        " 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -46,11 +46,11 @@
     python_requires=">=3.7",
     project_urls={
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/",
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

### Comparing `types-aiobotocore-kms-2.5.0.post1/types_aiobotocore_kms/__init__.py` & `types-aiobotocore-kms-2.5.1/types_aiobotocore_kms/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-kms-2.5.0.post1/types_aiobotocore_kms/__init__.pyi` & `types-aiobotocore-kms-2.5.1/types_aiobotocore_kms/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-kms-2.5.0.post1/types_aiobotocore_kms/__main__.py` & `types-aiobotocore-kms-2.5.1/types_aiobotocore_kms/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.KMS 2.5.0\nVersion:         2.5.0.post1\nBuilder version:"
-        " 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.KMS 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms//\nBoto3 docs:    "
         "  https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS\nOther"
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

### Comparing `types-aiobotocore-kms-2.5.0.post1/types_aiobotocore_kms/client.py` & `types-aiobotocore-kms-2.5.1/types_aiobotocore_kms/client.py`

 * *Files 1% similar despite different names*

```diff
@@ -33,14 +33,15 @@
     GrantOperationType,
     KeySpecType,
     KeyUsageTypeType,
     MacAlgorithmSpecType,
     MessageTypeType,
     OriginTypeType,
     SigningAlgorithmSpecType,
+    WrappingKeySpecType,
     XksProxyConnectivityTypeType,
 )
 from .paginator import (
     DescribeCustomKeyStoresPaginator,
     ListAliasesPaginator,
     ListGrantsPaginator,
     ListKeyPoliciesPaginator,
@@ -70,14 +71,15 @@
     GetPublicKeyResponseTypeDef,
     GrantConstraintsTypeDef,
     ListAliasesResponseTypeDef,
     ListGrantsResponseTypeDef,
     ListKeyPoliciesResponseTypeDef,
     ListKeysResponseTypeDef,
     ListResourceTagsResponseTypeDef,
+    RecipientInfoTypeDef,
     ReEncryptResponseTypeDef,
     ReplicateKeyResponseTypeDef,
     ScheduleKeyDeletionResponseTypeDef,
     SignResponseTypeDef,
     TagTypeDef,
     VerifyMacResponseTypeDef,
     VerifyResponseTypeDef,
@@ -280,21 +282,22 @@
     async def decrypt(
         self,
         *,
         CiphertextBlob: Union[str, bytes, IO[Any], StreamingBody],
         EncryptionContext: Mapping[str, str] = ...,
         GrantTokens: Sequence[str] = ...,
         KeyId: str = ...,
-        EncryptionAlgorithm: EncryptionAlgorithmSpecType = ...
+        EncryptionAlgorithm: EncryptionAlgorithmSpecType = ...,
+        Recipient: RecipientInfoTypeDef = ...
     ) -> DecryptResponseTypeDef:
         """
         Decrypts ciphertext that was encrypted by a KMS key using any of the following
-        operations *  Encrypt *  GenerateDataKey *  GenerateDataKeyPair *
+        operations: *  Encrypt *  GenerateDataKey *  GenerateDataKeyPair *
         GenerateDataKeyWithoutPlaintext *  GenerateDataKeyPairWithoutPlaintext You can
-        use this operation to decrypt cipher...
+        use this operation to decrypt ciphertext that was enc...
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.decrypt)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/client/#decrypt)
         """
 
     async def delete_alias(self, *, AliasName: str) -> EmptyResponseMetadataTypeDef:
         """
@@ -312,15 +315,15 @@
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.delete_custom_key_store)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/client/#delete_custom_key_store)
         """
 
     async def delete_imported_key_material(self, *, KeyId: str) -> EmptyResponseMetadataTypeDef:
         """
-        Deletes key material that you previously imported.
+        Deletes key material that was previously imported.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.delete_imported_key_material)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/client/#delete_imported_key_material)
         """
 
     async def describe_custom_key_stores(
         self,
@@ -414,30 +417,32 @@
     async def generate_data_key(
         self,
         *,
         KeyId: str,
         EncryptionContext: Mapping[str, str] = ...,
         NumberOfBytes: int = ...,
         KeySpec: DataKeySpecType = ...,
-        GrantTokens: Sequence[str] = ...
+        GrantTokens: Sequence[str] = ...,
+        Recipient: RecipientInfoTypeDef = ...
     ) -> GenerateDataKeyResponseTypeDef:
         """
         Returns a unique symmetric data key for use outside of KMS.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.generate_data_key)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/client/#generate_data_key)
         """
 
     async def generate_data_key_pair(
         self,
         *,
         KeyId: str,
         KeyPairSpec: DataKeyPairSpecType,
         EncryptionContext: Mapping[str, str] = ...,
-        GrantTokens: Sequence[str] = ...
+        GrantTokens: Sequence[str] = ...,
+        Recipient: RecipientInfoTypeDef = ...
     ) -> GenerateDataKeyPairResponseTypeDef:
         """
         Returns a unique asymmetric data key pair for use outside of KMS.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.generate_data_key_pair)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/client/#generate_data_key_pair)
         """
@@ -500,15 +505,19 @@
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/client/#generate_presigned_url)
         """
 
     async def generate_random(
-        self, *, NumberOfBytes: int = ..., CustomKeyStoreId: str = ...
+        self,
+        *,
+        NumberOfBytes: int = ...,
+        CustomKeyStoreId: str = ...,
+        Recipient: RecipientInfoTypeDef = ...
     ) -> GenerateRandomResponseTypeDef:
         """
         Returns a random byte string that is cryptographically secure.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.generate_random)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/client/#generate_random)
         """
@@ -532,19 +541,19 @@
         """
 
     async def get_parameters_for_import(
         self,
         *,
         KeyId: str,
         WrappingAlgorithm: AlgorithmSpecType,
-        WrappingKeySpec: Literal["RSA_2048"]
+        WrappingKeySpec: WrappingKeySpecType
     ) -> GetParametersForImportResponseTypeDef:
         """
-        Returns the items you need to import key material into a symmetric encryption
-        KMS key.
+        Returns the public key and an import token you need to import or reimport key
+        material for a KMS key.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.get_parameters_for_import)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/client/#get_parameters_for_import)
         """
 
     async def get_public_key(
         self, *, KeyId: str, GrantTokens: Sequence[str] = ...
@@ -562,16 +571,16 @@
         KeyId: str,
         ImportToken: Union[str, bytes, IO[Any], StreamingBody],
         EncryptedKeyMaterial: Union[str, bytes, IO[Any], StreamingBody],
         ValidTo: Union[datetime, str] = ...,
         ExpirationModel: ExpirationModelTypeType = ...
     ) -> Dict[str, Any]:
         """
-        Imports key material into an existing symmetric encryption KMS key that was
-        created without key material.
+        Imports or reimports key material into an existing KMS key that was created
+        without key material.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.import_key_material)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/client/#import_key_material)
         """
 
     async def list_aliases(
         self, *, KeyId: str = ..., Limit: int = ..., Marker: str = ...
```

### Comparing `types-aiobotocore-kms-2.5.0.post1/types_aiobotocore_kms/client.pyi` & `types-aiobotocore-kms-2.5.1/types_aiobotocore_kms/client.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -33,14 +33,15 @@
     GrantOperationType,
     KeySpecType,
     KeyUsageTypeType,
     MacAlgorithmSpecType,
     MessageTypeType,
     OriginTypeType,
     SigningAlgorithmSpecType,
+    WrappingKeySpecType,
     XksProxyConnectivityTypeType,
 )
 from .paginator import (
     DescribeCustomKeyStoresPaginator,
     ListAliasesPaginator,
     ListGrantsPaginator,
     ListKeyPoliciesPaginator,
@@ -70,14 +71,15 @@
     GetPublicKeyResponseTypeDef,
     GrantConstraintsTypeDef,
     ListAliasesResponseTypeDef,
     ListGrantsResponseTypeDef,
     ListKeyPoliciesResponseTypeDef,
     ListKeysResponseTypeDef,
     ListResourceTagsResponseTypeDef,
+    RecipientInfoTypeDef,
     ReEncryptResponseTypeDef,
     ReplicateKeyResponseTypeDef,
     ScheduleKeyDeletionResponseTypeDef,
     SignResponseTypeDef,
     TagTypeDef,
     VerifyMacResponseTypeDef,
     VerifyResponseTypeDef,
@@ -267,21 +269,22 @@
     async def decrypt(
         self,
         *,
         CiphertextBlob: Union[str, bytes, IO[Any], StreamingBody],
         EncryptionContext: Mapping[str, str] = ...,
         GrantTokens: Sequence[str] = ...,
         KeyId: str = ...,
-        EncryptionAlgorithm: EncryptionAlgorithmSpecType = ...
+        EncryptionAlgorithm: EncryptionAlgorithmSpecType = ...,
+        Recipient: RecipientInfoTypeDef = ...
     ) -> DecryptResponseTypeDef:
         """
         Decrypts ciphertext that was encrypted by a KMS key using any of the following
-        operations *  Encrypt *  GenerateDataKey *  GenerateDataKeyPair *
+        operations: *  Encrypt *  GenerateDataKey *  GenerateDataKeyPair *
         GenerateDataKeyWithoutPlaintext *  GenerateDataKeyPairWithoutPlaintext You can
-        use this operation to decrypt cipher...
+        use this operation to decrypt ciphertext that was enc...
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.decrypt)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/client/#decrypt)
         """
     async def delete_alias(self, *, AliasName: str) -> EmptyResponseMetadataTypeDef:
         """
         Deletes the specified alias.
@@ -296,15 +299,15 @@
         overview.html)_.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.delete_custom_key_store)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/client/#delete_custom_key_store)
         """
     async def delete_imported_key_material(self, *, KeyId: str) -> EmptyResponseMetadataTypeDef:
         """
-        Deletes key material that you previously imported.
+        Deletes key material that was previously imported.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.delete_imported_key_material)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/client/#delete_imported_key_material)
         """
     async def describe_custom_key_stores(
         self,
         *,
@@ -389,29 +392,31 @@
     async def generate_data_key(
         self,
         *,
         KeyId: str,
         EncryptionContext: Mapping[str, str] = ...,
         NumberOfBytes: int = ...,
         KeySpec: DataKeySpecType = ...,
-        GrantTokens: Sequence[str] = ...
+        GrantTokens: Sequence[str] = ...,
+        Recipient: RecipientInfoTypeDef = ...
     ) -> GenerateDataKeyResponseTypeDef:
         """
         Returns a unique symmetric data key for use outside of KMS.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.generate_data_key)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/client/#generate_data_key)
         """
     async def generate_data_key_pair(
         self,
         *,
         KeyId: str,
         KeyPairSpec: DataKeyPairSpecType,
         EncryptionContext: Mapping[str, str] = ...,
-        GrantTokens: Sequence[str] = ...
+        GrantTokens: Sequence[str] = ...,
+        Recipient: RecipientInfoTypeDef = ...
     ) -> GenerateDataKeyPairResponseTypeDef:
         """
         Returns a unique asymmetric data key pair for use outside of KMS.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.generate_data_key_pair)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/client/#generate_data_key_pair)
         """
@@ -469,15 +474,19 @@
         """
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/client/#generate_presigned_url)
         """
     async def generate_random(
-        self, *, NumberOfBytes: int = ..., CustomKeyStoreId: str = ...
+        self,
+        *,
+        NumberOfBytes: int = ...,
+        CustomKeyStoreId: str = ...,
+        Recipient: RecipientInfoTypeDef = ...
     ) -> GenerateRandomResponseTypeDef:
         """
         Returns a random byte string that is cryptographically secure.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.generate_random)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/client/#generate_random)
         """
@@ -498,19 +507,19 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/client/#get_key_rotation_status)
         """
     async def get_parameters_for_import(
         self,
         *,
         KeyId: str,
         WrappingAlgorithm: AlgorithmSpecType,
-        WrappingKeySpec: Literal["RSA_2048"]
+        WrappingKeySpec: WrappingKeySpecType
     ) -> GetParametersForImportResponseTypeDef:
         """
-        Returns the items you need to import key material into a symmetric encryption
-        KMS key.
+        Returns the public key and an import token you need to import or reimport key
+        material for a KMS key.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.get_parameters_for_import)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/client/#get_parameters_for_import)
         """
     async def get_public_key(
         self, *, KeyId: str, GrantTokens: Sequence[str] = ...
     ) -> GetPublicKeyResponseTypeDef:
@@ -526,16 +535,16 @@
         KeyId: str,
         ImportToken: Union[str, bytes, IO[Any], StreamingBody],
         EncryptedKeyMaterial: Union[str, bytes, IO[Any], StreamingBody],
         ValidTo: Union[datetime, str] = ...,
         ExpirationModel: ExpirationModelTypeType = ...
     ) -> Dict[str, Any]:
         """
-        Imports key material into an existing symmetric encryption KMS key that was
-        created without key material.
+        Imports or reimports key material into an existing KMS key that was created
+        without key material.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Client.import_key_material)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/client/#import_key_material)
         """
     async def list_aliases(
         self, *, KeyId: str = ..., Limit: int = ..., Marker: str = ...
     ) -> ListAliasesResponseTypeDef:
```

### Comparing `types-aiobotocore-kms-2.5.0.post1/types_aiobotocore_kms/literals.py` & `types-aiobotocore-kms-2.5.1/types_aiobotocore_kms/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -4,15 +4,15 @@
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/literals/)
 
 Usage::
 
     ```python
     from types_aiobotocore_kms.literals import AlgorithmSpecType
 
-    data: AlgorithmSpecType = "RSAES_OAEP_SHA_1"
+    data: AlgorithmSpecType = "RSA_AES_KEY_WRAP_SHA_1"
     ```
 """
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
@@ -27,14 +27,15 @@
     "CustomerMasterKeySpecType",
     "DataKeyPairSpecType",
     "DataKeySpecType",
     "DescribeCustomKeyStoresPaginatorName",
     "EncryptionAlgorithmSpecType",
     "ExpirationModelTypeType",
     "GrantOperationType",
+    "KeyEncryptionMechanismType",
     "KeyManagerTypeType",
     "KeySpecType",
     "KeyStateType",
     "KeyUsageTypeType",
     "ListAliasesPaginatorName",
     "ListGrantsPaginatorName",
     "ListKeyPoliciesPaginatorName",
@@ -52,15 +53,21 @@
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
 
-AlgorithmSpecType = Literal["RSAES_OAEP_SHA_1", "RSAES_OAEP_SHA_256", "RSAES_PKCS1_V1_5"]
+AlgorithmSpecType = Literal[
+    "RSAES_OAEP_SHA_1",
+    "RSAES_OAEP_SHA_256",
+    "RSAES_PKCS1_V1_5",
+    "RSA_AES_KEY_WRAP_SHA_1",
+    "RSA_AES_KEY_WRAP_SHA_256",
+]
 ConnectionErrorCodeTypeType = Literal[
     "CLUSTER_NOT_FOUND",
     "INSUFFICIENT_CLOUDHSM_HSMS",
     "INSUFFICIENT_FREE_ADDRESSES_IN_SUBNET",
     "INTERNAL_ERROR",
     "INVALID_CREDENTIALS",
     "NETWORK_ERRORS",
@@ -126,14 +133,15 @@
     "ReEncryptFrom",
     "ReEncryptTo",
     "RetireGrant",
     "Sign",
     "Verify",
     "VerifyMac",
 ]
+KeyEncryptionMechanismType = Literal["RSAES_OAEP_SHA_256"]
 KeyManagerTypeType = Literal["AWS", "CUSTOMER"]
 KeySpecType = Literal[
     "ECC_NIST_P256",
     "ECC_NIST_P384",
     "ECC_NIST_P521",
     "ECC_SECG_P256K1",
     "HMAC_224",
@@ -175,15 +183,15 @@
     "RSASSA_PKCS1_V1_5_SHA_384",
     "RSASSA_PKCS1_V1_5_SHA_512",
     "RSASSA_PSS_SHA_256",
     "RSASSA_PSS_SHA_384",
     "RSASSA_PSS_SHA_512",
     "SM2DSA",
 ]
-WrappingKeySpecType = Literal["RSA_2048"]
+WrappingKeySpecType = Literal["RSA_2048", "RSA_3072", "RSA_4096"]
 XksProxyConnectivityTypeType = Literal["PUBLIC_ENDPOINT", "VPC_ENDPOINT_SERVICE"]
 KMSServiceName = Literal["kms"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
@@ -240,14 +248,15 @@
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
@@ -326,14 +335,15 @@
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
@@ -344,14 +354,15 @@
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
@@ -387,14 +398,15 @@
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
@@ -413,16 +425,19 @@
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
@@ -506,15 +521,17 @@
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

### Comparing `types-aiobotocore-kms-2.5.0.post1/types_aiobotocore_kms/literals.pyi` & `types-aiobotocore-kms-2.5.1/types_aiobotocore_kms/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -4,15 +4,15 @@
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/literals/)
 
 Usage::
 
     ```python
     from types_aiobotocore_kms.literals import AlgorithmSpecType
 
-    data: AlgorithmSpecType = "RSAES_OAEP_SHA_1"
+    data: AlgorithmSpecType = "RSA_AES_KEY_WRAP_SHA_1"
     ```
 """
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
@@ -26,14 +26,15 @@
     "CustomerMasterKeySpecType",
     "DataKeyPairSpecType",
     "DataKeySpecType",
     "DescribeCustomKeyStoresPaginatorName",
     "EncryptionAlgorithmSpecType",
     "ExpirationModelTypeType",
     "GrantOperationType",
+    "KeyEncryptionMechanismType",
     "KeyManagerTypeType",
     "KeySpecType",
     "KeyStateType",
     "KeyUsageTypeType",
     "ListAliasesPaginatorName",
     "ListGrantsPaginatorName",
     "ListKeyPoliciesPaginatorName",
@@ -50,15 +51,21 @@
     "KMSServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
-AlgorithmSpecType = Literal["RSAES_OAEP_SHA_1", "RSAES_OAEP_SHA_256", "RSAES_PKCS1_V1_5"]
+AlgorithmSpecType = Literal[
+    "RSAES_OAEP_SHA_1",
+    "RSAES_OAEP_SHA_256",
+    "RSAES_PKCS1_V1_5",
+    "RSA_AES_KEY_WRAP_SHA_1",
+    "RSA_AES_KEY_WRAP_SHA_256",
+]
 ConnectionErrorCodeTypeType = Literal[
     "CLUSTER_NOT_FOUND",
     "INSUFFICIENT_CLOUDHSM_HSMS",
     "INSUFFICIENT_FREE_ADDRESSES_IN_SUBNET",
     "INTERNAL_ERROR",
     "INVALID_CREDENTIALS",
     "NETWORK_ERRORS",
@@ -124,14 +131,15 @@
     "ReEncryptFrom",
     "ReEncryptTo",
     "RetireGrant",
     "Sign",
     "Verify",
     "VerifyMac",
 ]
+KeyEncryptionMechanismType = Literal["RSAES_OAEP_SHA_256"]
 KeyManagerTypeType = Literal["AWS", "CUSTOMER"]
 KeySpecType = Literal[
     "ECC_NIST_P256",
     "ECC_NIST_P384",
     "ECC_NIST_P521",
     "ECC_SECG_P256K1",
     "HMAC_224",
@@ -173,15 +181,15 @@
     "RSASSA_PKCS1_V1_5_SHA_384",
     "RSASSA_PKCS1_V1_5_SHA_512",
     "RSASSA_PSS_SHA_256",
     "RSASSA_PSS_SHA_384",
     "RSASSA_PSS_SHA_512",
     "SM2DSA",
 ]
-WrappingKeySpecType = Literal["RSA_2048"]
+WrappingKeySpecType = Literal["RSA_2048", "RSA_3072", "RSA_4096"]
 XksProxyConnectivityTypeType = Literal["PUBLIC_ENDPOINT", "VPC_ENDPOINT_SERVICE"]
 KMSServiceName = Literal["kms"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
@@ -238,14 +246,15 @@
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
@@ -324,14 +333,15 @@
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
@@ -342,14 +352,15 @@
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
@@ -385,14 +396,15 @@
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
@@ -411,16 +423,19 @@
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
@@ -504,15 +519,17 @@
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

### Comparing `types-aiobotocore-kms-2.5.0.post1/types_aiobotocore_kms/paginator.py` & `types-aiobotocore-kms-2.5.1/types_aiobotocore_kms/paginator.py`

 * *Files 3% similar despite different names*

```diff
@@ -28,36 +28,29 @@
         list_grants_paginator: ListGrantsPaginator = client.get_paginator("list_grants")
         list_key_policies_paginator: ListKeyPoliciesPaginator = client.get_paginator("list_key_policies")
         list_keys_paginator: ListKeysPaginator = client.get_paginator("list_keys")
         list_resource_tags_paginator: ListResourceTagsPaginator = client.get_paginator("list_resource_tags")
         list_retirable_grants_paginator: ListRetirableGrantsPaginator = client.get_paginator("list_retirable_grants")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DescribeCustomKeyStoresResponseTypeDef,
     ListAliasesResponseTypeDef,
     ListGrantsResponseTypeDef,
     ListKeyPoliciesResponseTypeDef,
     ListKeysResponseTypeDef,
     ListResourceTagsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "DescribeCustomKeyStoresPaginator",
     "ListAliasesPaginator",
     "ListGrantsPaginator",
     "ListKeyPoliciesPaginator",
     "ListKeysPaginator",
     "ListResourceTagsPaginator",
@@ -82,30 +75,30 @@
     """
 
     def paginate(
         self,
         *,
         CustomKeyStoreId: str = ...,
         CustomKeyStoreName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeCustomKeyStoresResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Paginator.DescribeCustomKeyStores.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/paginators/#describecustomkeystorespaginator)
         """
 
 
 class ListAliasesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Paginator.ListAliases)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/paginators/#listaliasespaginator)
     """
 
     def paginate(
-        self, *, KeyId: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, KeyId: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAliasesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Paginator.ListAliases.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/paginators/#listaliasespaginator)
         """
 
 
@@ -117,73 +110,73 @@
 
     def paginate(
         self,
         *,
         KeyId: str,
         GrantId: str = ...,
         GranteePrincipal: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGrantsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Paginator.ListGrants.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/paginators/#listgrantspaginator)
         """
 
 
 class ListKeyPoliciesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Paginator.ListKeyPolicies)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/paginators/#listkeypoliciespaginator)
     """
 
     def paginate(
-        self, *, KeyId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, KeyId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListKeyPoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Paginator.ListKeyPolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/paginators/#listkeypoliciespaginator)
         """
 
 
 class ListKeysPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Paginator.ListKeys)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/paginators/#listkeyspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListKeysResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Paginator.ListKeys.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/paginators/#listkeyspaginator)
         """
 
 
 class ListResourceTagsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Paginator.ListResourceTags)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/paginators/#listresourcetagspaginator)
     """
 
     def paginate(
-        self, *, KeyId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, KeyId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResourceTagsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Paginator.ListResourceTags.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/paginators/#listresourcetagspaginator)
         """
 
 
 class ListRetirableGrantsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Paginator.ListRetirableGrants)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/paginators/#listretirablegrantspaginator)
     """
 
     def paginate(
-        self, *, RetiringPrincipal: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, RetiringPrincipal: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGrantsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Paginator.ListRetirableGrants.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/paginators/#listretirablegrantspaginator)
         """
```

### Comparing `types-aiobotocore-kms-2.5.0.post1/types_aiobotocore_kms/paginator.pyi` & `types-aiobotocore-kms-2.5.1/types_aiobotocore_kms/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -28,35 +28,29 @@
         list_grants_paginator: ListGrantsPaginator = client.get_paginator("list_grants")
         list_key_policies_paginator: ListKeyPoliciesPaginator = client.get_paginator("list_key_policies")
         list_keys_paginator: ListKeysPaginator = client.get_paginator("list_keys")
         list_resource_tags_paginator: ListResourceTagsPaginator = client.get_paginator("list_resource_tags")
         list_retirable_grants_paginator: ListRetirableGrantsPaginator = client.get_paginator("list_retirable_grants")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DescribeCustomKeyStoresResponseTypeDef,
     ListAliasesResponseTypeDef,
     ListGrantsResponseTypeDef,
     ListKeyPoliciesResponseTypeDef,
     ListKeysResponseTypeDef,
     ListResourceTagsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "DescribeCustomKeyStoresPaginator",
     "ListAliasesPaginator",
     "ListGrantsPaginator",
     "ListKeyPoliciesPaginator",
     "ListKeysPaginator",
     "ListResourceTagsPaginator",
@@ -78,29 +72,29 @@
     """
 
     def paginate(
         self,
         *,
         CustomKeyStoreId: str = ...,
         CustomKeyStoreName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeCustomKeyStoresResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Paginator.DescribeCustomKeyStores.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/paginators/#describecustomkeystorespaginator)
         """
 
 class ListAliasesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Paginator.ListAliases)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/paginators/#listaliasespaginator)
     """
 
     def paginate(
-        self, *, KeyId: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, KeyId: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAliasesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Paginator.ListAliases.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/paginators/#listaliasespaginator)
         """
 
 class ListGrantsPaginator(AioPaginator):
@@ -111,69 +105,69 @@
 
     def paginate(
         self,
         *,
         KeyId: str,
         GrantId: str = ...,
         GranteePrincipal: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGrantsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Paginator.ListGrants.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/paginators/#listgrantspaginator)
         """
 
 class ListKeyPoliciesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Paginator.ListKeyPolicies)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/paginators/#listkeypoliciespaginator)
     """
 
     def paginate(
-        self, *, KeyId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, KeyId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListKeyPoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Paginator.ListKeyPolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/paginators/#listkeypoliciespaginator)
         """
 
 class ListKeysPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Paginator.ListKeys)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/paginators/#listkeyspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListKeysResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Paginator.ListKeys.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/paginators/#listkeyspaginator)
         """
 
 class ListResourceTagsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Paginator.ListResourceTags)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/paginators/#listresourcetagspaginator)
     """
 
     def paginate(
-        self, *, KeyId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, KeyId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListResourceTagsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Paginator.ListResourceTags.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/paginators/#listresourcetagspaginator)
         """
 
 class ListRetirableGrantsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Paginator.ListRetirableGrants)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/paginators/#listretirablegrantspaginator)
     """
 
     def paginate(
-        self, *, RetiringPrincipal: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, RetiringPrincipal: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGrantsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS.Paginator.ListRetirableGrants.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/paginators/#listretirablegrantspaginator)
         """
```

### Comparing `types-aiobotocore-kms-2.5.0.post1/types_aiobotocore_kms/type_defs.py` & `types-aiobotocore-kms-2.5.1/types_aiobotocore_kms/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -33,14 +33,15 @@
     KeyStateType,
     KeyUsageTypeType,
     MacAlgorithmSpecType,
     MessageTypeType,
     MultiRegionKeyTypeType,
     OriginTypeType,
     SigningAlgorithmSpecType,
+    WrappingKeySpecType,
     XksProxyConnectivityTypeType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
@@ -49,105 +50,106 @@
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AliasListEntryTypeDef",
     "CancelKeyDeletionRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CancelKeyDeletionResponseTypeDef",
     "ConnectCustomKeyStoreRequestRequestTypeDef",
     "CreateAliasRequestRequestTypeDef",
     "XksProxyAuthenticationCredentialTypeTypeDef",
+    "CreateCustomKeyStoreResponseTypeDef",
     "GrantConstraintsTypeDef",
+    "CreateGrantResponseTypeDef",
     "TagTypeDef",
     "XksProxyConfigurationTypeTypeDef",
-    "DecryptRequestRequestTypeDef",
+    "RecipientInfoTypeDef",
+    "DecryptResponseTypeDef",
     "DeleteAliasRequestRequestTypeDef",
     "DeleteCustomKeyStoreRequestRequestTypeDef",
     "DeleteImportedKeyMaterialRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeCustomKeyStoresRequestDescribeCustomKeyStoresPaginateTypeDef",
     "DescribeCustomKeyStoresRequestRequestTypeDef",
     "DescribeKeyRequestRequestTypeDef",
     "DisableKeyRequestRequestTypeDef",
     "DisableKeyRotationRequestRequestTypeDef",
     "DisconnectCustomKeyStoreRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EnableKeyRequestRequestTypeDef",
     "EnableKeyRotationRequestRequestTypeDef",
     "EncryptRequestRequestTypeDef",
-    "GenerateDataKeyPairRequestRequestTypeDef",
+    "EncryptResponseTypeDef",
+    "GenerateDataKeyPairResponseTypeDef",
     "GenerateDataKeyPairWithoutPlaintextRequestRequestTypeDef",
-    "GenerateDataKeyRequestRequestTypeDef",
+    "GenerateDataKeyPairWithoutPlaintextResponseTypeDef",
+    "GenerateDataKeyResponseTypeDef",
     "GenerateDataKeyWithoutPlaintextRequestRequestTypeDef",
+    "GenerateDataKeyWithoutPlaintextResponseTypeDef",
     "GenerateMacRequestRequestTypeDef",
-    "GenerateRandomRequestRequestTypeDef",
+    "GenerateMacResponseTypeDef",
+    "GenerateRandomResponseTypeDef",
     "GetKeyPolicyRequestRequestTypeDef",
+    "GetKeyPolicyResponseTypeDef",
     "GetKeyRotationStatusRequestRequestTypeDef",
+    "GetKeyRotationStatusResponseTypeDef",
     "GetParametersForImportRequestRequestTypeDef",
+    "GetParametersForImportResponseTypeDef",
     "GetPublicKeyRequestRequestTypeDef",
+    "GetPublicKeyResponseTypeDef",
     "ImportKeyMaterialRequestRequestTypeDef",
     "KeyListEntryTypeDef",
     "XksKeyConfigurationTypeTypeDef",
+    "ListAliasesRequestListAliasesPaginateTypeDef",
     "ListAliasesRequestRequestTypeDef",
+    "ListGrantsRequestListGrantsPaginateTypeDef",
     "ListGrantsRequestRequestTypeDef",
+    "ListKeyPoliciesRequestListKeyPoliciesPaginateTypeDef",
     "ListKeyPoliciesRequestRequestTypeDef",
+    "ListKeyPoliciesResponseTypeDef",
+    "ListKeysRequestListKeysPaginateTypeDef",
     "ListKeysRequestRequestTypeDef",
+    "ListResourceTagsRequestListResourceTagsPaginateTypeDef",
     "ListResourceTagsRequestRequestTypeDef",
+    "ListRetirableGrantsRequestListRetirableGrantsPaginateTypeDef",
     "ListRetirableGrantsRequestRequestTypeDef",
     "MultiRegionKeyTypeDef",
+    "PaginatorConfigTypeDef",
     "PutKeyPolicyRequestRequestTypeDef",
     "ReEncryptRequestRequestTypeDef",
+    "ReEncryptResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "RetireGrantRequestRequestTypeDef",
     "RevokeGrantRequestRequestTypeDef",
     "ScheduleKeyDeletionRequestRequestTypeDef",
+    "ScheduleKeyDeletionResponseTypeDef",
     "SignRequestRequestTypeDef",
+    "SignResponseTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateAliasRequestRequestTypeDef",
     "UpdateKeyDescriptionRequestRequestTypeDef",
     "UpdatePrimaryRegionRequestRequestTypeDef",
     "VerifyMacRequestRequestTypeDef",
-    "VerifyRequestRequestTypeDef",
-    "CancelKeyDeletionResponseTypeDef",
-    "CreateCustomKeyStoreResponseTypeDef",
-    "CreateGrantResponseTypeDef",
-    "DecryptResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "EncryptResponseTypeDef",
-    "GenerateDataKeyPairResponseTypeDef",
-    "GenerateDataKeyPairWithoutPlaintextResponseTypeDef",
-    "GenerateDataKeyResponseTypeDef",
-    "GenerateDataKeyWithoutPlaintextResponseTypeDef",
-    "GenerateMacResponseTypeDef",
-    "GenerateRandomResponseTypeDef",
-    "GetKeyPolicyResponseTypeDef",
-    "GetKeyRotationStatusResponseTypeDef",
-    "GetParametersForImportResponseTypeDef",
-    "GetPublicKeyResponseTypeDef",
-    "ListAliasesResponseTypeDef",
-    "ListKeyPoliciesResponseTypeDef",
-    "ReEncryptResponseTypeDef",
-    "ScheduleKeyDeletionResponseTypeDef",
-    "SignResponseTypeDef",
     "VerifyMacResponseTypeDef",
+    "VerifyRequestRequestTypeDef",
     "VerifyResponseTypeDef",
+    "ListAliasesResponseTypeDef",
     "CreateCustomKeyStoreRequestRequestTypeDef",
     "UpdateCustomKeyStoreRequestRequestTypeDef",
     "CreateGrantRequestRequestTypeDef",
     "GrantListEntryTypeDef",
     "CreateKeyRequestRequestTypeDef",
     "ListResourceTagsResponseTypeDef",
     "ReplicateKeyRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "CustomKeyStoresListEntryTypeDef",
-    "DescribeCustomKeyStoresRequestDescribeCustomKeyStoresPaginateTypeDef",
-    "ListAliasesRequestListAliasesPaginateTypeDef",
-    "ListGrantsRequestListGrantsPaginateTypeDef",
-    "ListKeyPoliciesRequestListKeyPoliciesPaginateTypeDef",
-    "ListKeysRequestListKeysPaginateTypeDef",
-    "ListResourceTagsRequestListResourceTagsPaginateTypeDef",
-    "ListRetirableGrantsRequestListRetirableGrantsPaginateTypeDef",
+    "DecryptRequestRequestTypeDef",
+    "GenerateDataKeyPairRequestRequestTypeDef",
+    "GenerateDataKeyRequestRequestTypeDef",
+    "GenerateRandomRequestRequestTypeDef",
     "ListKeysResponseTypeDef",
     "MultiRegionConfigurationTypeDef",
     "ListGrantsResponseTypeDef",
     "DescribeCustomKeyStoresResponseTypeDef",
     "KeyMetadataTypeDef",
     "CreateKeyResponseTypeDef",
     "DescribeKeyResponseTypeDef",
@@ -169,22 +171,19 @@
 CancelKeyDeletionRequestRequestTypeDef = TypedDict(
     "CancelKeyDeletionRequestRequestTypeDef",
     {
         "KeyId": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CancelKeyDeletionResponseTypeDef = TypedDict(
+    "CancelKeyDeletionResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "KeyId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ConnectCustomKeyStoreRequestRequestTypeDef = TypedDict(
     "ConnectCustomKeyStoreRequestRequestTypeDef",
     {
         "CustomKeyStoreId": str,
@@ -203,23 +202,40 @@
     "XksProxyAuthenticationCredentialTypeTypeDef",
     {
         "AccessKeyId": str,
         "RawSecretAccessKey": str,
     },
 )
 
+CreateCustomKeyStoreResponseTypeDef = TypedDict(
+    "CreateCustomKeyStoreResponseTypeDef",
+    {
+        "CustomKeyStoreId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GrantConstraintsTypeDef = TypedDict(
     "GrantConstraintsTypeDef",
     {
         "EncryptionContextSubset": Mapping[str, str],
         "EncryptionContextEquals": Mapping[str, str],
     },
     total=False,
 )
 
+CreateGrantResponseTypeDef = TypedDict(
+    "CreateGrantResponseTypeDef",
+    {
+        "GrantToken": str,
+        "GrantId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "TagKey": str,
         "TagValue": str,
     },
 )
@@ -232,38 +248,34 @@
         "UriEndpoint": str,
         "UriPath": str,
         "VpcEndpointServiceName": str,
     },
     total=False,
 )
 
-_RequiredDecryptRequestRequestTypeDef = TypedDict(
-    "_RequiredDecryptRequestRequestTypeDef",
+RecipientInfoTypeDef = TypedDict(
+    "RecipientInfoTypeDef",
     {
-        "CiphertextBlob": Union[str, bytes, IO[Any], StreamingBody],
+        "KeyEncryptionAlgorithm": Literal["RSAES_OAEP_SHA_256"],
+        "AttestationDocument": Union[str, bytes, IO[Any], StreamingBody],
     },
+    total=False,
 )
-_OptionalDecryptRequestRequestTypeDef = TypedDict(
-    "_OptionalDecryptRequestRequestTypeDef",
+
+DecryptResponseTypeDef = TypedDict(
+    "DecryptResponseTypeDef",
     {
-        "EncryptionContext": Mapping[str, str],
-        "GrantTokens": Sequence[str],
         "KeyId": str,
+        "Plaintext": bytes,
         "EncryptionAlgorithm": EncryptionAlgorithmSpecType,
+        "CiphertextForRecipient": bytes,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-
-class DecryptRequestRequestTypeDef(
-    _RequiredDecryptRequestRequestTypeDef, _OptionalDecryptRequestRequestTypeDef
-):
-    pass
-
-
 DeleteAliasRequestRequestTypeDef = TypedDict(
     "DeleteAliasRequestRequestTypeDef",
     {
         "AliasName": str,
     },
 )
 
@@ -277,20 +289,20 @@
 DeleteImportedKeyMaterialRequestRequestTypeDef = TypedDict(
     "DeleteImportedKeyMaterialRequestRequestTypeDef",
     {
         "KeyId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeCustomKeyStoresRequestDescribeCustomKeyStoresPaginateTypeDef = TypedDict(
+    "DescribeCustomKeyStoresRequestDescribeCustomKeyStoresPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "CustomKeyStoreId": str,
+        "CustomKeyStoreName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeCustomKeyStoresRequestRequestTypeDef = TypedDict(
     "DescribeCustomKeyStoresRequestRequestTypeDef",
     {
@@ -340,14 +352,21 @@
 DisconnectCustomKeyStoreRequestRequestTypeDef = TypedDict(
     "DisconnectCustomKeyStoreRequestRequestTypeDef",
     {
         "CustomKeyStoreId": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EnableKeyRequestRequestTypeDef = TypedDict(
     "EnableKeyRequestRequestTypeDef",
     {
         "KeyId": str,
     },
 )
 
@@ -378,38 +397,37 @@
 
 class EncryptRequestRequestTypeDef(
     _RequiredEncryptRequestRequestTypeDef, _OptionalEncryptRequestRequestTypeDef
 ):
     pass
 
 
-_RequiredGenerateDataKeyPairRequestRequestTypeDef = TypedDict(
-    "_RequiredGenerateDataKeyPairRequestRequestTypeDef",
+EncryptResponseTypeDef = TypedDict(
+    "EncryptResponseTypeDef",
     {
+        "CiphertextBlob": bytes,
         "KeyId": str,
-        "KeyPairSpec": DataKeyPairSpecType,
+        "EncryptionAlgorithm": EncryptionAlgorithmSpecType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalGenerateDataKeyPairRequestRequestTypeDef = TypedDict(
-    "_OptionalGenerateDataKeyPairRequestRequestTypeDef",
+
+GenerateDataKeyPairResponseTypeDef = TypedDict(
+    "GenerateDataKeyPairResponseTypeDef",
     {
-        "EncryptionContext": Mapping[str, str],
-        "GrantTokens": Sequence[str],
+        "PrivateKeyCiphertextBlob": bytes,
+        "PrivateKeyPlaintext": bytes,
+        "PublicKey": bytes,
+        "KeyId": str,
+        "KeyPairSpec": DataKeyPairSpecType,
+        "CiphertextForRecipient": bytes,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-
-class GenerateDataKeyPairRequestRequestTypeDef(
-    _RequiredGenerateDataKeyPairRequestRequestTypeDef,
-    _OptionalGenerateDataKeyPairRequestRequestTypeDef,
-):
-    pass
-
-
 _RequiredGenerateDataKeyPairWithoutPlaintextRequestRequestTypeDef = TypedDict(
     "_RequiredGenerateDataKeyPairWithoutPlaintextRequestRequestTypeDef",
     {
         "KeyId": str,
         "KeyPairSpec": DataKeyPairSpecType,
     },
 )
@@ -426,38 +444,36 @@
 class GenerateDataKeyPairWithoutPlaintextRequestRequestTypeDef(
     _RequiredGenerateDataKeyPairWithoutPlaintextRequestRequestTypeDef,
     _OptionalGenerateDataKeyPairWithoutPlaintextRequestRequestTypeDef,
 ):
     pass
 
 
-_RequiredGenerateDataKeyRequestRequestTypeDef = TypedDict(
-    "_RequiredGenerateDataKeyRequestRequestTypeDef",
+GenerateDataKeyPairWithoutPlaintextResponseTypeDef = TypedDict(
+    "GenerateDataKeyPairWithoutPlaintextResponseTypeDef",
     {
+        "PrivateKeyCiphertextBlob": bytes,
+        "PublicKey": bytes,
         "KeyId": str,
+        "KeyPairSpec": DataKeyPairSpecType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalGenerateDataKeyRequestRequestTypeDef = TypedDict(
-    "_OptionalGenerateDataKeyRequestRequestTypeDef",
+
+GenerateDataKeyResponseTypeDef = TypedDict(
+    "GenerateDataKeyResponseTypeDef",
     {
-        "EncryptionContext": Mapping[str, str],
-        "NumberOfBytes": int,
-        "KeySpec": DataKeySpecType,
-        "GrantTokens": Sequence[str],
+        "CiphertextBlob": bytes,
+        "Plaintext": bytes,
+        "KeyId": str,
+        "CiphertextForRecipient": bytes,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-
-class GenerateDataKeyRequestRequestTypeDef(
-    _RequiredGenerateDataKeyRequestRequestTypeDef, _OptionalGenerateDataKeyRequestRequestTypeDef
-):
-    pass
-
-
 _RequiredGenerateDataKeyWithoutPlaintextRequestRequestTypeDef = TypedDict(
     "_RequiredGenerateDataKeyWithoutPlaintextRequestRequestTypeDef",
     {
         "KeyId": str,
     },
 )
 _OptionalGenerateDataKeyWithoutPlaintextRequestRequestTypeDef = TypedDict(
@@ -475,14 +491,23 @@
 class GenerateDataKeyWithoutPlaintextRequestRequestTypeDef(
     _RequiredGenerateDataKeyWithoutPlaintextRequestRequestTypeDef,
     _OptionalGenerateDataKeyWithoutPlaintextRequestRequestTypeDef,
 ):
     pass
 
 
+GenerateDataKeyWithoutPlaintextResponseTypeDef = TypedDict(
+    "GenerateDataKeyWithoutPlaintextResponseTypeDef",
+    {
+        "CiphertextBlob": bytes,
+        "KeyId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGenerateMacRequestRequestTypeDef = TypedDict(
     "_RequiredGenerateMacRequestRequestTypeDef",
     {
         "Message": Union[str, bytes, IO[Any], StreamingBody],
         "KeyId": str,
         "MacAlgorithm": MacAlgorithmSpecType,
     },
@@ -498,44 +523,81 @@
 
 class GenerateMacRequestRequestTypeDef(
     _RequiredGenerateMacRequestRequestTypeDef, _OptionalGenerateMacRequestRequestTypeDef
 ):
     pass
 
 
-GenerateRandomRequestRequestTypeDef = TypedDict(
-    "GenerateRandomRequestRequestTypeDef",
+GenerateMacResponseTypeDef = TypedDict(
+    "GenerateMacResponseTypeDef",
     {
-        "NumberOfBytes": int,
-        "CustomKeyStoreId": str,
+        "Mac": bytes,
+        "MacAlgorithm": MacAlgorithmSpecType,
+        "KeyId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GenerateRandomResponseTypeDef = TypedDict(
+    "GenerateRandomResponseTypeDef",
+    {
+        "Plaintext": bytes,
+        "CiphertextForRecipient": bytes,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
 GetKeyPolicyRequestRequestTypeDef = TypedDict(
     "GetKeyPolicyRequestRequestTypeDef",
     {
         "KeyId": str,
         "PolicyName": str,
     },
 )
 
+GetKeyPolicyResponseTypeDef = TypedDict(
+    "GetKeyPolicyResponseTypeDef",
+    {
+        "Policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetKeyRotationStatusRequestRequestTypeDef = TypedDict(
     "GetKeyRotationStatusRequestRequestTypeDef",
     {
         "KeyId": str,
     },
 )
 
+GetKeyRotationStatusResponseTypeDef = TypedDict(
+    "GetKeyRotationStatusResponseTypeDef",
+    {
+        "KeyRotationEnabled": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetParametersForImportRequestRequestTypeDef = TypedDict(
     "GetParametersForImportRequestRequestTypeDef",
     {
         "KeyId": str,
         "WrappingAlgorithm": AlgorithmSpecType,
-        "WrappingKeySpec": Literal["RSA_2048"],
+        "WrappingKeySpec": WrappingKeySpecType,
+    },
+)
+
+GetParametersForImportResponseTypeDef = TypedDict(
+    "GetParametersForImportResponseTypeDef",
+    {
+        "KeyId": str,
+        "ImportToken": bytes,
+        "PublicKey": bytes,
+        "ParametersValidTo": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetPublicKeyRequestRequestTypeDef = TypedDict(
     "_RequiredGetPublicKeyRequestRequestTypeDef",
     {
         "KeyId": str,
@@ -552,14 +614,28 @@
 
 class GetPublicKeyRequestRequestTypeDef(
     _RequiredGetPublicKeyRequestRequestTypeDef, _OptionalGetPublicKeyRequestRequestTypeDef
 ):
     pass
 
 
+GetPublicKeyResponseTypeDef = TypedDict(
+    "GetPublicKeyResponseTypeDef",
+    {
+        "KeyId": str,
+        "PublicKey": bytes,
+        "CustomerMasterKeySpec": CustomerMasterKeySpecType,
+        "KeySpec": KeySpecType,
+        "KeyUsage": KeyUsageTypeType,
+        "EncryptionAlgorithms": List[EncryptionAlgorithmSpecType],
+        "SigningAlgorithms": List[SigningAlgorithmSpecType],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredImportKeyMaterialRequestRequestTypeDef = TypedDict(
     "_RequiredImportKeyMaterialRequestRequestTypeDef",
     {
         "KeyId": str,
         "ImportToken": Union[str, bytes, IO[Any], StreamingBody],
         "EncryptedKeyMaterial": Union[str, bytes, IO[Any], StreamingBody],
     },
@@ -593,24 +669,57 @@
     "XksKeyConfigurationTypeTypeDef",
     {
         "Id": str,
     },
     total=False,
 )
 
+ListAliasesRequestListAliasesPaginateTypeDef = TypedDict(
+    "ListAliasesRequestListAliasesPaginateTypeDef",
+    {
+        "KeyId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListAliasesRequestRequestTypeDef = TypedDict(
     "ListAliasesRequestRequestTypeDef",
     {
         "KeyId": str,
         "Limit": int,
         "Marker": str,
     },
     total=False,
 )
 
+_RequiredListGrantsRequestListGrantsPaginateTypeDef = TypedDict(
+    "_RequiredListGrantsRequestListGrantsPaginateTypeDef",
+    {
+        "KeyId": str,
+    },
+)
+_OptionalListGrantsRequestListGrantsPaginateTypeDef = TypedDict(
+    "_OptionalListGrantsRequestListGrantsPaginateTypeDef",
+    {
+        "GrantId": str,
+        "GranteePrincipal": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListGrantsRequestListGrantsPaginateTypeDef(
+    _RequiredListGrantsRequestListGrantsPaginateTypeDef,
+    _OptionalListGrantsRequestListGrantsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListGrantsRequestRequestTypeDef = TypedDict(
     "_RequiredListGrantsRequestRequestTypeDef",
     {
         "KeyId": str,
     },
 )
 _OptionalListGrantsRequestRequestTypeDef = TypedDict(
@@ -627,14 +736,36 @@
 
 class ListGrantsRequestRequestTypeDef(
     _RequiredListGrantsRequestRequestTypeDef, _OptionalListGrantsRequestRequestTypeDef
 ):
     pass
 
 
+_RequiredListKeyPoliciesRequestListKeyPoliciesPaginateTypeDef = TypedDict(
+    "_RequiredListKeyPoliciesRequestListKeyPoliciesPaginateTypeDef",
+    {
+        "KeyId": str,
+    },
+)
+_OptionalListKeyPoliciesRequestListKeyPoliciesPaginateTypeDef = TypedDict(
+    "_OptionalListKeyPoliciesRequestListKeyPoliciesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListKeyPoliciesRequestListKeyPoliciesPaginateTypeDef(
+    _RequiredListKeyPoliciesRequestListKeyPoliciesPaginateTypeDef,
+    _OptionalListKeyPoliciesRequestListKeyPoliciesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListKeyPoliciesRequestRequestTypeDef = TypedDict(
     "_RequiredListKeyPoliciesRequestRequestTypeDef",
     {
         "KeyId": str,
     },
 )
 _OptionalListKeyPoliciesRequestRequestTypeDef = TypedDict(
@@ -649,23 +780,63 @@
 
 class ListKeyPoliciesRequestRequestTypeDef(
     _RequiredListKeyPoliciesRequestRequestTypeDef, _OptionalListKeyPoliciesRequestRequestTypeDef
 ):
     pass
 
 
+ListKeyPoliciesResponseTypeDef = TypedDict(
+    "ListKeyPoliciesResponseTypeDef",
+    {
+        "PolicyNames": List[str],
+        "NextMarker": str,
+        "Truncated": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListKeysRequestListKeysPaginateTypeDef = TypedDict(
+    "ListKeysRequestListKeysPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListKeysRequestRequestTypeDef = TypedDict(
     "ListKeysRequestRequestTypeDef",
     {
         "Limit": int,
         "Marker": str,
     },
     total=False,
 )
 
+_RequiredListResourceTagsRequestListResourceTagsPaginateTypeDef = TypedDict(
+    "_RequiredListResourceTagsRequestListResourceTagsPaginateTypeDef",
+    {
+        "KeyId": str,
+    },
+)
+_OptionalListResourceTagsRequestListResourceTagsPaginateTypeDef = TypedDict(
+    "_OptionalListResourceTagsRequestListResourceTagsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListResourceTagsRequestListResourceTagsPaginateTypeDef(
+    _RequiredListResourceTagsRequestListResourceTagsPaginateTypeDef,
+    _OptionalListResourceTagsRequestListResourceTagsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListResourceTagsRequestRequestTypeDef = TypedDict(
     "_RequiredListResourceTagsRequestRequestTypeDef",
     {
         "KeyId": str,
     },
 )
 _OptionalListResourceTagsRequestRequestTypeDef = TypedDict(
@@ -680,14 +851,36 @@
 
 class ListResourceTagsRequestRequestTypeDef(
     _RequiredListResourceTagsRequestRequestTypeDef, _OptionalListResourceTagsRequestRequestTypeDef
 ):
     pass
 
 
+_RequiredListRetirableGrantsRequestListRetirableGrantsPaginateTypeDef = TypedDict(
+    "_RequiredListRetirableGrantsRequestListRetirableGrantsPaginateTypeDef",
+    {
+        "RetiringPrincipal": str,
+    },
+)
+_OptionalListRetirableGrantsRequestListRetirableGrantsPaginateTypeDef = TypedDict(
+    "_OptionalListRetirableGrantsRequestListRetirableGrantsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListRetirableGrantsRequestListRetirableGrantsPaginateTypeDef(
+    _RequiredListRetirableGrantsRequestListRetirableGrantsPaginateTypeDef,
+    _OptionalListRetirableGrantsRequestListRetirableGrantsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListRetirableGrantsRequestRequestTypeDef = TypedDict(
     "_RequiredListRetirableGrantsRequestRequestTypeDef",
     {
         "RetiringPrincipal": str,
     },
 )
 _OptionalListRetirableGrantsRequestRequestTypeDef = TypedDict(
@@ -712,14 +905,24 @@
     {
         "Arn": str,
         "Region": str,
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
 _RequiredPutKeyPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredPutKeyPolicyRequestRequestTypeDef",
     {
         "KeyId": str,
         "PolicyName": str,
         "Policy": str,
     },
@@ -762,14 +965,37 @@
 
 class ReEncryptRequestRequestTypeDef(
     _RequiredReEncryptRequestRequestTypeDef, _OptionalReEncryptRequestRequestTypeDef
 ):
     pass
 
 
+ReEncryptResponseTypeDef = TypedDict(
+    "ReEncryptResponseTypeDef",
+    {
+        "CiphertextBlob": bytes,
+        "SourceKeyId": str,
+        "KeyId": str,
+        "SourceEncryptionAlgorithm": EncryptionAlgorithmSpecType,
+        "DestinationEncryptionAlgorithm": EncryptionAlgorithmSpecType,
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
 RetireGrantRequestRequestTypeDef = TypedDict(
     "RetireGrantRequestRequestTypeDef",
     {
         "GrantToken": str,
         "KeyId": str,
         "GrantId": str,
     },
@@ -802,14 +1028,25 @@
 class ScheduleKeyDeletionRequestRequestTypeDef(
     _RequiredScheduleKeyDeletionRequestRequestTypeDef,
     _OptionalScheduleKeyDeletionRequestRequestTypeDef,
 ):
     pass
 
 
+ScheduleKeyDeletionResponseTypeDef = TypedDict(
+    "ScheduleKeyDeletionResponseTypeDef",
+    {
+        "KeyId": str,
+        "DeletionDate": datetime,
+        "KeyState": KeyStateType,
+        "PendingWindowInDays": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredSignRequestRequestTypeDef = TypedDict(
     "_RequiredSignRequestRequestTypeDef",
     {
         "KeyId": str,
         "Message": Union[str, bytes, IO[Any], StreamingBody],
         "SigningAlgorithm": SigningAlgorithmSpecType,
     },
@@ -826,14 +1063,24 @@
 
 class SignRequestRequestTypeDef(
     _RequiredSignRequestRequestTypeDef, _OptionalSignRequestRequestTypeDef
 ):
     pass
 
 
+SignResponseTypeDef = TypedDict(
+    "SignResponseTypeDef",
+    {
+        "KeyId": str,
+        "Signature": bytes,
+        "SigningAlgorithm": SigningAlgorithmSpecType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "KeyId": str,
         "TagKeys": Sequence[str],
     },
 )
@@ -882,14 +1129,24 @@
 
 class VerifyMacRequestRequestTypeDef(
     _RequiredVerifyMacRequestRequestTypeDef, _OptionalVerifyMacRequestRequestTypeDef
 ):
     pass
 
 
+VerifyMacResponseTypeDef = TypedDict(
+    "VerifyMacResponseTypeDef",
+    {
+        "KeyId": str,
+        "MacValid": bool,
+        "MacAlgorithm": MacAlgorithmSpecType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredVerifyRequestRequestTypeDef = TypedDict(
     "_RequiredVerifyRequestRequestTypeDef",
     {
         "KeyId": str,
         "Message": Union[str, bytes, IO[Any], StreamingBody],
         "Signature": Union[str, bytes, IO[Any], StreamingBody],
         "SigningAlgorithm": SigningAlgorithmSpecType,
@@ -907,237 +1164,31 @@
 
 class VerifyRequestRequestTypeDef(
     _RequiredVerifyRequestRequestTypeDef, _OptionalVerifyRequestRequestTypeDef
 ):
     pass
 
 
-CancelKeyDeletionResponseTypeDef = TypedDict(
-    "CancelKeyDeletionResponseTypeDef",
-    {
-        "KeyId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateCustomKeyStoreResponseTypeDef = TypedDict(
-    "CreateCustomKeyStoreResponseTypeDef",
-    {
-        "CustomKeyStoreId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateGrantResponseTypeDef = TypedDict(
-    "CreateGrantResponseTypeDef",
-    {
-        "GrantToken": str,
-        "GrantId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DecryptResponseTypeDef = TypedDict(
-    "DecryptResponseTypeDef",
-    {
-        "KeyId": str,
-        "Plaintext": bytes,
-        "EncryptionAlgorithm": EncryptionAlgorithmSpecType,
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
-EncryptResponseTypeDef = TypedDict(
-    "EncryptResponseTypeDef",
-    {
-        "CiphertextBlob": bytes,
-        "KeyId": str,
-        "EncryptionAlgorithm": EncryptionAlgorithmSpecType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GenerateDataKeyPairResponseTypeDef = TypedDict(
-    "GenerateDataKeyPairResponseTypeDef",
-    {
-        "PrivateKeyCiphertextBlob": bytes,
-        "PrivateKeyPlaintext": bytes,
-        "PublicKey": bytes,
-        "KeyId": str,
-        "KeyPairSpec": DataKeyPairSpecType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GenerateDataKeyPairWithoutPlaintextResponseTypeDef = TypedDict(
-    "GenerateDataKeyPairWithoutPlaintextResponseTypeDef",
-    {
-        "PrivateKeyCiphertextBlob": bytes,
-        "PublicKey": bytes,
-        "KeyId": str,
-        "KeyPairSpec": DataKeyPairSpecType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GenerateDataKeyResponseTypeDef = TypedDict(
-    "GenerateDataKeyResponseTypeDef",
-    {
-        "CiphertextBlob": bytes,
-        "Plaintext": bytes,
-        "KeyId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GenerateDataKeyWithoutPlaintextResponseTypeDef = TypedDict(
-    "GenerateDataKeyWithoutPlaintextResponseTypeDef",
-    {
-        "CiphertextBlob": bytes,
-        "KeyId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GenerateMacResponseTypeDef = TypedDict(
-    "GenerateMacResponseTypeDef",
-    {
-        "Mac": bytes,
-        "MacAlgorithm": MacAlgorithmSpecType,
-        "KeyId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GenerateRandomResponseTypeDef = TypedDict(
-    "GenerateRandomResponseTypeDef",
-    {
-        "Plaintext": bytes,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetKeyPolicyResponseTypeDef = TypedDict(
-    "GetKeyPolicyResponseTypeDef",
-    {
-        "Policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetKeyRotationStatusResponseTypeDef = TypedDict(
-    "GetKeyRotationStatusResponseTypeDef",
-    {
-        "KeyRotationEnabled": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetParametersForImportResponseTypeDef = TypedDict(
-    "GetParametersForImportResponseTypeDef",
-    {
-        "KeyId": str,
-        "ImportToken": bytes,
-        "PublicKey": bytes,
-        "ParametersValidTo": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetPublicKeyResponseTypeDef = TypedDict(
-    "GetPublicKeyResponseTypeDef",
+VerifyResponseTypeDef = TypedDict(
+    "VerifyResponseTypeDef",
     {
         "KeyId": str,
-        "PublicKey": bytes,
-        "CustomerMasterKeySpec": CustomerMasterKeySpecType,
-        "KeySpec": KeySpecType,
-        "KeyUsage": KeyUsageTypeType,
-        "EncryptionAlgorithms": List[EncryptionAlgorithmSpecType],
-        "SigningAlgorithms": List[SigningAlgorithmSpecType],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "SignatureValid": bool,
+        "SigningAlgorithm": SigningAlgorithmSpecType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAliasesResponseTypeDef = TypedDict(
     "ListAliasesResponseTypeDef",
     {
         "Aliases": List[AliasListEntryTypeDef],
         "NextMarker": str,
         "Truncated": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListKeyPoliciesResponseTypeDef = TypedDict(
-    "ListKeyPoliciesResponseTypeDef",
-    {
-        "PolicyNames": List[str],
-        "NextMarker": str,
-        "Truncated": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ReEncryptResponseTypeDef = TypedDict(
-    "ReEncryptResponseTypeDef",
-    {
-        "CiphertextBlob": bytes,
-        "SourceKeyId": str,
-        "KeyId": str,
-        "SourceEncryptionAlgorithm": EncryptionAlgorithmSpecType,
-        "DestinationEncryptionAlgorithm": EncryptionAlgorithmSpecType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ScheduleKeyDeletionResponseTypeDef = TypedDict(
-    "ScheduleKeyDeletionResponseTypeDef",
-    {
-        "KeyId": str,
-        "DeletionDate": datetime,
-        "KeyState": KeyStateType,
-        "PendingWindowInDays": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SignResponseTypeDef = TypedDict(
-    "SignResponseTypeDef",
-    {
-        "KeyId": str,
-        "Signature": bytes,
-        "SigningAlgorithm": SigningAlgorithmSpecType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-VerifyMacResponseTypeDef = TypedDict(
-    "VerifyMacResponseTypeDef",
-    {
-        "KeyId": str,
-        "MacValid": bool,
-        "MacAlgorithm": MacAlgorithmSpecType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-VerifyResponseTypeDef = TypedDict(
-    "VerifyResponseTypeDef",
-    {
-        "KeyId": str,
-        "SignatureValid": bool,
-        "SigningAlgorithm": SigningAlgorithmSpecType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateCustomKeyStoreRequestRequestTypeDef = TypedDict(
     "_RequiredCreateCustomKeyStoreRequestRequestTypeDef",
     {
         "CustomKeyStoreName": str,
@@ -1258,15 +1309,15 @@
 
 ListResourceTagsResponseTypeDef = TypedDict(
     "ListResourceTagsResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
         "NextMarker": str,
         "Truncated": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredReplicateKeyRequestRequestTypeDef = TypedDict(
     "_RequiredReplicateKeyRequestRequestTypeDef",
     {
         "KeyId": str,
@@ -1311,138 +1362,106 @@
         "CreationDate": datetime,
         "CustomKeyStoreType": CustomKeyStoreTypeType,
         "XksProxyConfiguration": XksProxyConfigurationTypeTypeDef,
     },
     total=False,
 )
 
-DescribeCustomKeyStoresRequestDescribeCustomKeyStoresPaginateTypeDef = TypedDict(
-    "DescribeCustomKeyStoresRequestDescribeCustomKeyStoresPaginateTypeDef",
-    {
-        "CustomKeyStoreId": str,
-        "CustomKeyStoreName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListAliasesRequestListAliasesPaginateTypeDef = TypedDict(
-    "ListAliasesRequestListAliasesPaginateTypeDef",
+_RequiredDecryptRequestRequestTypeDef = TypedDict(
+    "_RequiredDecryptRequestRequestTypeDef",
     {
-        "KeyId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "CiphertextBlob": Union[str, bytes, IO[Any], StreamingBody],
     },
-    total=False,
 )
-
-_RequiredListGrantsRequestListGrantsPaginateTypeDef = TypedDict(
-    "_RequiredListGrantsRequestListGrantsPaginateTypeDef",
+_OptionalDecryptRequestRequestTypeDef = TypedDict(
+    "_OptionalDecryptRequestRequestTypeDef",
     {
+        "EncryptionContext": Mapping[str, str],
+        "GrantTokens": Sequence[str],
         "KeyId": str,
-    },
-)
-_OptionalListGrantsRequestListGrantsPaginateTypeDef = TypedDict(
-    "_OptionalListGrantsRequestListGrantsPaginateTypeDef",
-    {
-        "GrantId": str,
-        "GranteePrincipal": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "EncryptionAlgorithm": EncryptionAlgorithmSpecType,
+        "Recipient": RecipientInfoTypeDef,
     },
     total=False,
 )
 
 
-class ListGrantsRequestListGrantsPaginateTypeDef(
-    _RequiredListGrantsRequestListGrantsPaginateTypeDef,
-    _OptionalListGrantsRequestListGrantsPaginateTypeDef,
+class DecryptRequestRequestTypeDef(
+    _RequiredDecryptRequestRequestTypeDef, _OptionalDecryptRequestRequestTypeDef
 ):
     pass
 
 
-_RequiredListKeyPoliciesRequestListKeyPoliciesPaginateTypeDef = TypedDict(
-    "_RequiredListKeyPoliciesRequestListKeyPoliciesPaginateTypeDef",
+_RequiredGenerateDataKeyPairRequestRequestTypeDef = TypedDict(
+    "_RequiredGenerateDataKeyPairRequestRequestTypeDef",
     {
         "KeyId": str,
+        "KeyPairSpec": DataKeyPairSpecType,
     },
 )
-_OptionalListKeyPoliciesRequestListKeyPoliciesPaginateTypeDef = TypedDict(
-    "_OptionalListKeyPoliciesRequestListKeyPoliciesPaginateTypeDef",
+_OptionalGenerateDataKeyPairRequestRequestTypeDef = TypedDict(
+    "_OptionalGenerateDataKeyPairRequestRequestTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "EncryptionContext": Mapping[str, str],
+        "GrantTokens": Sequence[str],
+        "Recipient": RecipientInfoTypeDef,
     },
     total=False,
 )
 
 
-class ListKeyPoliciesRequestListKeyPoliciesPaginateTypeDef(
-    _RequiredListKeyPoliciesRequestListKeyPoliciesPaginateTypeDef,
-    _OptionalListKeyPoliciesRequestListKeyPoliciesPaginateTypeDef,
+class GenerateDataKeyPairRequestRequestTypeDef(
+    _RequiredGenerateDataKeyPairRequestRequestTypeDef,
+    _OptionalGenerateDataKeyPairRequestRequestTypeDef,
 ):
     pass
 
 
-ListKeysRequestListKeysPaginateTypeDef = TypedDict(
-    "ListKeysRequestListKeysPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListResourceTagsRequestListResourceTagsPaginateTypeDef = TypedDict(
-    "_RequiredListResourceTagsRequestListResourceTagsPaginateTypeDef",
+_RequiredGenerateDataKeyRequestRequestTypeDef = TypedDict(
+    "_RequiredGenerateDataKeyRequestRequestTypeDef",
     {
         "KeyId": str,
     },
 )
-_OptionalListResourceTagsRequestListResourceTagsPaginateTypeDef = TypedDict(
-    "_OptionalListResourceTagsRequestListResourceTagsPaginateTypeDef",
+_OptionalGenerateDataKeyRequestRequestTypeDef = TypedDict(
+    "_OptionalGenerateDataKeyRequestRequestTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "EncryptionContext": Mapping[str, str],
+        "NumberOfBytes": int,
+        "KeySpec": DataKeySpecType,
+        "GrantTokens": Sequence[str],
+        "Recipient": RecipientInfoTypeDef,
     },
     total=False,
 )
 
 
-class ListResourceTagsRequestListResourceTagsPaginateTypeDef(
-    _RequiredListResourceTagsRequestListResourceTagsPaginateTypeDef,
-    _OptionalListResourceTagsRequestListResourceTagsPaginateTypeDef,
+class GenerateDataKeyRequestRequestTypeDef(
+    _RequiredGenerateDataKeyRequestRequestTypeDef, _OptionalGenerateDataKeyRequestRequestTypeDef
 ):
     pass
 
 
-_RequiredListRetirableGrantsRequestListRetirableGrantsPaginateTypeDef = TypedDict(
-    "_RequiredListRetirableGrantsRequestListRetirableGrantsPaginateTypeDef",
-    {
-        "RetiringPrincipal": str,
-    },
-)
-_OptionalListRetirableGrantsRequestListRetirableGrantsPaginateTypeDef = TypedDict(
-    "_OptionalListRetirableGrantsRequestListRetirableGrantsPaginateTypeDef",
+GenerateRandomRequestRequestTypeDef = TypedDict(
+    "GenerateRandomRequestRequestTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "NumberOfBytes": int,
+        "CustomKeyStoreId": str,
+        "Recipient": RecipientInfoTypeDef,
     },
     total=False,
 )
 
-
-class ListRetirableGrantsRequestListRetirableGrantsPaginateTypeDef(
-    _RequiredListRetirableGrantsRequestListRetirableGrantsPaginateTypeDef,
-    _OptionalListRetirableGrantsRequestListRetirableGrantsPaginateTypeDef,
-):
-    pass
-
-
 ListKeysResponseTypeDef = TypedDict(
     "ListKeysResponseTypeDef",
     {
         "Keys": List[KeyListEntryTypeDef],
         "NextMarker": str,
         "Truncated": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 MultiRegionConfigurationTypeDef = TypedDict(
     "MultiRegionConfigurationTypeDef",
     {
         "MultiRegionKeyType": MultiRegionKeyTypeType,
@@ -1454,25 +1473,25 @@
 
 ListGrantsResponseTypeDef = TypedDict(
     "ListGrantsResponseTypeDef",
     {
         "Grants": List[GrantListEntryTypeDef],
         "NextMarker": str,
         "Truncated": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeCustomKeyStoresResponseTypeDef = TypedDict(
     "DescribeCustomKeyStoresResponseTypeDef",
     {
         "CustomKeyStores": List[CustomKeyStoresListEntryTypeDef],
         "NextMarker": str,
         "Truncated": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredKeyMetadataTypeDef = TypedDict(
     "_RequiredKeyMetadataTypeDef",
     {
         "KeyId": str,
@@ -1513,28 +1532,28 @@
     pass
 
 
 CreateKeyResponseTypeDef = TypedDict(
     "CreateKeyResponseTypeDef",
     {
         "KeyMetadata": KeyMetadataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeKeyResponseTypeDef = TypedDict(
     "DescribeKeyResponseTypeDef",
     {
         "KeyMetadata": KeyMetadataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReplicateKeyResponseTypeDef = TypedDict(
     "ReplicateKeyResponseTypeDef",
     {
         "ReplicaKeyMetadata": KeyMetadataTypeDef,
         "ReplicaPolicy": str,
         "ReplicaTags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-kms-2.5.0.post1/types_aiobotocore_kms/type_defs.pyi` & `types-aiobotocore-kms-2.5.1/types_aiobotocore_kms/type_defs.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -33,14 +33,15 @@
     KeyStateType,
     KeyUsageTypeType,
     MacAlgorithmSpecType,
     MessageTypeType,
     MultiRegionKeyTypeType,
     OriginTypeType,
     SigningAlgorithmSpecType,
+    WrappingKeySpecType,
     XksProxyConnectivityTypeType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
@@ -48,105 +49,106 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AliasListEntryTypeDef",
     "CancelKeyDeletionRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CancelKeyDeletionResponseTypeDef",
     "ConnectCustomKeyStoreRequestRequestTypeDef",
     "CreateAliasRequestRequestTypeDef",
     "XksProxyAuthenticationCredentialTypeTypeDef",
+    "CreateCustomKeyStoreResponseTypeDef",
     "GrantConstraintsTypeDef",
+    "CreateGrantResponseTypeDef",
     "TagTypeDef",
     "XksProxyConfigurationTypeTypeDef",
-    "DecryptRequestRequestTypeDef",
+    "RecipientInfoTypeDef",
+    "DecryptResponseTypeDef",
     "DeleteAliasRequestRequestTypeDef",
     "DeleteCustomKeyStoreRequestRequestTypeDef",
     "DeleteImportedKeyMaterialRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeCustomKeyStoresRequestDescribeCustomKeyStoresPaginateTypeDef",
     "DescribeCustomKeyStoresRequestRequestTypeDef",
     "DescribeKeyRequestRequestTypeDef",
     "DisableKeyRequestRequestTypeDef",
     "DisableKeyRotationRequestRequestTypeDef",
     "DisconnectCustomKeyStoreRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EnableKeyRequestRequestTypeDef",
     "EnableKeyRotationRequestRequestTypeDef",
     "EncryptRequestRequestTypeDef",
-    "GenerateDataKeyPairRequestRequestTypeDef",
+    "EncryptResponseTypeDef",
+    "GenerateDataKeyPairResponseTypeDef",
     "GenerateDataKeyPairWithoutPlaintextRequestRequestTypeDef",
-    "GenerateDataKeyRequestRequestTypeDef",
+    "GenerateDataKeyPairWithoutPlaintextResponseTypeDef",
+    "GenerateDataKeyResponseTypeDef",
     "GenerateDataKeyWithoutPlaintextRequestRequestTypeDef",
+    "GenerateDataKeyWithoutPlaintextResponseTypeDef",
     "GenerateMacRequestRequestTypeDef",
-    "GenerateRandomRequestRequestTypeDef",
+    "GenerateMacResponseTypeDef",
+    "GenerateRandomResponseTypeDef",
     "GetKeyPolicyRequestRequestTypeDef",
+    "GetKeyPolicyResponseTypeDef",
     "GetKeyRotationStatusRequestRequestTypeDef",
+    "GetKeyRotationStatusResponseTypeDef",
     "GetParametersForImportRequestRequestTypeDef",
+    "GetParametersForImportResponseTypeDef",
     "GetPublicKeyRequestRequestTypeDef",
+    "GetPublicKeyResponseTypeDef",
     "ImportKeyMaterialRequestRequestTypeDef",
     "KeyListEntryTypeDef",
     "XksKeyConfigurationTypeTypeDef",
+    "ListAliasesRequestListAliasesPaginateTypeDef",
     "ListAliasesRequestRequestTypeDef",
+    "ListGrantsRequestListGrantsPaginateTypeDef",
     "ListGrantsRequestRequestTypeDef",
+    "ListKeyPoliciesRequestListKeyPoliciesPaginateTypeDef",
     "ListKeyPoliciesRequestRequestTypeDef",
+    "ListKeyPoliciesResponseTypeDef",
+    "ListKeysRequestListKeysPaginateTypeDef",
     "ListKeysRequestRequestTypeDef",
+    "ListResourceTagsRequestListResourceTagsPaginateTypeDef",
     "ListResourceTagsRequestRequestTypeDef",
+    "ListRetirableGrantsRequestListRetirableGrantsPaginateTypeDef",
     "ListRetirableGrantsRequestRequestTypeDef",
     "MultiRegionKeyTypeDef",
+    "PaginatorConfigTypeDef",
     "PutKeyPolicyRequestRequestTypeDef",
     "ReEncryptRequestRequestTypeDef",
+    "ReEncryptResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "RetireGrantRequestRequestTypeDef",
     "RevokeGrantRequestRequestTypeDef",
     "ScheduleKeyDeletionRequestRequestTypeDef",
+    "ScheduleKeyDeletionResponseTypeDef",
     "SignRequestRequestTypeDef",
+    "SignResponseTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateAliasRequestRequestTypeDef",
     "UpdateKeyDescriptionRequestRequestTypeDef",
     "UpdatePrimaryRegionRequestRequestTypeDef",
     "VerifyMacRequestRequestTypeDef",
-    "VerifyRequestRequestTypeDef",
-    "CancelKeyDeletionResponseTypeDef",
-    "CreateCustomKeyStoreResponseTypeDef",
-    "CreateGrantResponseTypeDef",
-    "DecryptResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "EncryptResponseTypeDef",
-    "GenerateDataKeyPairResponseTypeDef",
-    "GenerateDataKeyPairWithoutPlaintextResponseTypeDef",
-    "GenerateDataKeyResponseTypeDef",
-    "GenerateDataKeyWithoutPlaintextResponseTypeDef",
-    "GenerateMacResponseTypeDef",
-    "GenerateRandomResponseTypeDef",
-    "GetKeyPolicyResponseTypeDef",
-    "GetKeyRotationStatusResponseTypeDef",
-    "GetParametersForImportResponseTypeDef",
-    "GetPublicKeyResponseTypeDef",
-    "ListAliasesResponseTypeDef",
-    "ListKeyPoliciesResponseTypeDef",
-    "ReEncryptResponseTypeDef",
-    "ScheduleKeyDeletionResponseTypeDef",
-    "SignResponseTypeDef",
     "VerifyMacResponseTypeDef",
+    "VerifyRequestRequestTypeDef",
     "VerifyResponseTypeDef",
+    "ListAliasesResponseTypeDef",
     "CreateCustomKeyStoreRequestRequestTypeDef",
     "UpdateCustomKeyStoreRequestRequestTypeDef",
     "CreateGrantRequestRequestTypeDef",
     "GrantListEntryTypeDef",
     "CreateKeyRequestRequestTypeDef",
     "ListResourceTagsResponseTypeDef",
     "ReplicateKeyRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "CustomKeyStoresListEntryTypeDef",
-    "DescribeCustomKeyStoresRequestDescribeCustomKeyStoresPaginateTypeDef",
-    "ListAliasesRequestListAliasesPaginateTypeDef",
-    "ListGrantsRequestListGrantsPaginateTypeDef",
-    "ListKeyPoliciesRequestListKeyPoliciesPaginateTypeDef",
-    "ListKeysRequestListKeysPaginateTypeDef",
-    "ListResourceTagsRequestListResourceTagsPaginateTypeDef",
-    "ListRetirableGrantsRequestListRetirableGrantsPaginateTypeDef",
+    "DecryptRequestRequestTypeDef",
+    "GenerateDataKeyPairRequestRequestTypeDef",
+    "GenerateDataKeyRequestRequestTypeDef",
+    "GenerateRandomRequestRequestTypeDef",
     "ListKeysResponseTypeDef",
     "MultiRegionConfigurationTypeDef",
     "ListGrantsResponseTypeDef",
     "DescribeCustomKeyStoresResponseTypeDef",
     "KeyMetadataTypeDef",
     "CreateKeyResponseTypeDef",
     "DescribeKeyResponseTypeDef",
@@ -168,22 +170,19 @@
 CancelKeyDeletionRequestRequestTypeDef = TypedDict(
     "CancelKeyDeletionRequestRequestTypeDef",
     {
         "KeyId": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CancelKeyDeletionResponseTypeDef = TypedDict(
+    "CancelKeyDeletionResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "KeyId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ConnectCustomKeyStoreRequestRequestTypeDef = TypedDict(
     "ConnectCustomKeyStoreRequestRequestTypeDef",
     {
         "CustomKeyStoreId": str,
@@ -202,23 +201,40 @@
     "XksProxyAuthenticationCredentialTypeTypeDef",
     {
         "AccessKeyId": str,
         "RawSecretAccessKey": str,
     },
 )
 
+CreateCustomKeyStoreResponseTypeDef = TypedDict(
+    "CreateCustomKeyStoreResponseTypeDef",
+    {
+        "CustomKeyStoreId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GrantConstraintsTypeDef = TypedDict(
     "GrantConstraintsTypeDef",
     {
         "EncryptionContextSubset": Mapping[str, str],
         "EncryptionContextEquals": Mapping[str, str],
     },
     total=False,
 )
 
+CreateGrantResponseTypeDef = TypedDict(
+    "CreateGrantResponseTypeDef",
+    {
+        "GrantToken": str,
+        "GrantId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "TagKey": str,
         "TagValue": str,
     },
 )
@@ -231,36 +247,34 @@
         "UriEndpoint": str,
         "UriPath": str,
         "VpcEndpointServiceName": str,
     },
     total=False,
 )
 
-_RequiredDecryptRequestRequestTypeDef = TypedDict(
-    "_RequiredDecryptRequestRequestTypeDef",
+RecipientInfoTypeDef = TypedDict(
+    "RecipientInfoTypeDef",
     {
-        "CiphertextBlob": Union[str, bytes, IO[Any], StreamingBody],
+        "KeyEncryptionAlgorithm": Literal["RSAES_OAEP_SHA_256"],
+        "AttestationDocument": Union[str, bytes, IO[Any], StreamingBody],
     },
+    total=False,
 )
-_OptionalDecryptRequestRequestTypeDef = TypedDict(
-    "_OptionalDecryptRequestRequestTypeDef",
+
+DecryptResponseTypeDef = TypedDict(
+    "DecryptResponseTypeDef",
     {
-        "EncryptionContext": Mapping[str, str],
-        "GrantTokens": Sequence[str],
         "KeyId": str,
+        "Plaintext": bytes,
         "EncryptionAlgorithm": EncryptionAlgorithmSpecType,
+        "CiphertextForRecipient": bytes,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-class DecryptRequestRequestTypeDef(
-    _RequiredDecryptRequestRequestTypeDef, _OptionalDecryptRequestRequestTypeDef
-):
-    pass
-
 DeleteAliasRequestRequestTypeDef = TypedDict(
     "DeleteAliasRequestRequestTypeDef",
     {
         "AliasName": str,
     },
 )
 
@@ -274,20 +288,20 @@
 DeleteImportedKeyMaterialRequestRequestTypeDef = TypedDict(
     "DeleteImportedKeyMaterialRequestRequestTypeDef",
     {
         "KeyId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeCustomKeyStoresRequestDescribeCustomKeyStoresPaginateTypeDef = TypedDict(
+    "DescribeCustomKeyStoresRequestDescribeCustomKeyStoresPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "CustomKeyStoreId": str,
+        "CustomKeyStoreName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeCustomKeyStoresRequestRequestTypeDef = TypedDict(
     "DescribeCustomKeyStoresRequestRequestTypeDef",
     {
@@ -335,14 +349,21 @@
 DisconnectCustomKeyStoreRequestRequestTypeDef = TypedDict(
     "DisconnectCustomKeyStoreRequestRequestTypeDef",
     {
         "CustomKeyStoreId": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EnableKeyRequestRequestTypeDef = TypedDict(
     "EnableKeyRequestRequestTypeDef",
     {
         "KeyId": str,
     },
 )
 
@@ -371,36 +392,37 @@
 )
 
 class EncryptRequestRequestTypeDef(
     _RequiredEncryptRequestRequestTypeDef, _OptionalEncryptRequestRequestTypeDef
 ):
     pass
 
-_RequiredGenerateDataKeyPairRequestRequestTypeDef = TypedDict(
-    "_RequiredGenerateDataKeyPairRequestRequestTypeDef",
+EncryptResponseTypeDef = TypedDict(
+    "EncryptResponseTypeDef",
     {
+        "CiphertextBlob": bytes,
         "KeyId": str,
-        "KeyPairSpec": DataKeyPairSpecType,
+        "EncryptionAlgorithm": EncryptionAlgorithmSpecType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalGenerateDataKeyPairRequestRequestTypeDef = TypedDict(
-    "_OptionalGenerateDataKeyPairRequestRequestTypeDef",
+
+GenerateDataKeyPairResponseTypeDef = TypedDict(
+    "GenerateDataKeyPairResponseTypeDef",
     {
-        "EncryptionContext": Mapping[str, str],
-        "GrantTokens": Sequence[str],
+        "PrivateKeyCiphertextBlob": bytes,
+        "PrivateKeyPlaintext": bytes,
+        "PublicKey": bytes,
+        "KeyId": str,
+        "KeyPairSpec": DataKeyPairSpecType,
+        "CiphertextForRecipient": bytes,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-class GenerateDataKeyPairRequestRequestTypeDef(
-    _RequiredGenerateDataKeyPairRequestRequestTypeDef,
-    _OptionalGenerateDataKeyPairRequestRequestTypeDef,
-):
-    pass
-
 _RequiredGenerateDataKeyPairWithoutPlaintextRequestRequestTypeDef = TypedDict(
     "_RequiredGenerateDataKeyPairWithoutPlaintextRequestRequestTypeDef",
     {
         "KeyId": str,
         "KeyPairSpec": DataKeyPairSpecType,
     },
 )
@@ -415,36 +437,36 @@
 
 class GenerateDataKeyPairWithoutPlaintextRequestRequestTypeDef(
     _RequiredGenerateDataKeyPairWithoutPlaintextRequestRequestTypeDef,
     _OptionalGenerateDataKeyPairWithoutPlaintextRequestRequestTypeDef,
 ):
     pass
 
-_RequiredGenerateDataKeyRequestRequestTypeDef = TypedDict(
-    "_RequiredGenerateDataKeyRequestRequestTypeDef",
+GenerateDataKeyPairWithoutPlaintextResponseTypeDef = TypedDict(
+    "GenerateDataKeyPairWithoutPlaintextResponseTypeDef",
     {
+        "PrivateKeyCiphertextBlob": bytes,
+        "PublicKey": bytes,
         "KeyId": str,
+        "KeyPairSpec": DataKeyPairSpecType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalGenerateDataKeyRequestRequestTypeDef = TypedDict(
-    "_OptionalGenerateDataKeyRequestRequestTypeDef",
+
+GenerateDataKeyResponseTypeDef = TypedDict(
+    "GenerateDataKeyResponseTypeDef",
     {
-        "EncryptionContext": Mapping[str, str],
-        "NumberOfBytes": int,
-        "KeySpec": DataKeySpecType,
-        "GrantTokens": Sequence[str],
+        "CiphertextBlob": bytes,
+        "Plaintext": bytes,
+        "KeyId": str,
+        "CiphertextForRecipient": bytes,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-class GenerateDataKeyRequestRequestTypeDef(
-    _RequiredGenerateDataKeyRequestRequestTypeDef, _OptionalGenerateDataKeyRequestRequestTypeDef
-):
-    pass
-
 _RequiredGenerateDataKeyWithoutPlaintextRequestRequestTypeDef = TypedDict(
     "_RequiredGenerateDataKeyWithoutPlaintextRequestRequestTypeDef",
     {
         "KeyId": str,
     },
 )
 _OptionalGenerateDataKeyWithoutPlaintextRequestRequestTypeDef = TypedDict(
@@ -460,14 +482,23 @@
 
 class GenerateDataKeyWithoutPlaintextRequestRequestTypeDef(
     _RequiredGenerateDataKeyWithoutPlaintextRequestRequestTypeDef,
     _OptionalGenerateDataKeyWithoutPlaintextRequestRequestTypeDef,
 ):
     pass
 
+GenerateDataKeyWithoutPlaintextResponseTypeDef = TypedDict(
+    "GenerateDataKeyWithoutPlaintextResponseTypeDef",
+    {
+        "CiphertextBlob": bytes,
+        "KeyId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGenerateMacRequestRequestTypeDef = TypedDict(
     "_RequiredGenerateMacRequestRequestTypeDef",
     {
         "Message": Union[str, bytes, IO[Any], StreamingBody],
         "KeyId": str,
         "MacAlgorithm": MacAlgorithmSpecType,
     },
@@ -481,44 +512,81 @@
 )
 
 class GenerateMacRequestRequestTypeDef(
     _RequiredGenerateMacRequestRequestTypeDef, _OptionalGenerateMacRequestRequestTypeDef
 ):
     pass
 
-GenerateRandomRequestRequestTypeDef = TypedDict(
-    "GenerateRandomRequestRequestTypeDef",
+GenerateMacResponseTypeDef = TypedDict(
+    "GenerateMacResponseTypeDef",
     {
-        "NumberOfBytes": int,
-        "CustomKeyStoreId": str,
+        "Mac": bytes,
+        "MacAlgorithm": MacAlgorithmSpecType,
+        "KeyId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GenerateRandomResponseTypeDef = TypedDict(
+    "GenerateRandomResponseTypeDef",
+    {
+        "Plaintext": bytes,
+        "CiphertextForRecipient": bytes,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
 GetKeyPolicyRequestRequestTypeDef = TypedDict(
     "GetKeyPolicyRequestRequestTypeDef",
     {
         "KeyId": str,
         "PolicyName": str,
     },
 )
 
+GetKeyPolicyResponseTypeDef = TypedDict(
+    "GetKeyPolicyResponseTypeDef",
+    {
+        "Policy": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetKeyRotationStatusRequestRequestTypeDef = TypedDict(
     "GetKeyRotationStatusRequestRequestTypeDef",
     {
         "KeyId": str,
     },
 )
 
+GetKeyRotationStatusResponseTypeDef = TypedDict(
+    "GetKeyRotationStatusResponseTypeDef",
+    {
+        "KeyRotationEnabled": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetParametersForImportRequestRequestTypeDef = TypedDict(
     "GetParametersForImportRequestRequestTypeDef",
     {
         "KeyId": str,
         "WrappingAlgorithm": AlgorithmSpecType,
-        "WrappingKeySpec": Literal["RSA_2048"],
+        "WrappingKeySpec": WrappingKeySpecType,
+    },
+)
+
+GetParametersForImportResponseTypeDef = TypedDict(
+    "GetParametersForImportResponseTypeDef",
+    {
+        "KeyId": str,
+        "ImportToken": bytes,
+        "PublicKey": bytes,
+        "ParametersValidTo": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetPublicKeyRequestRequestTypeDef = TypedDict(
     "_RequiredGetPublicKeyRequestRequestTypeDef",
     {
         "KeyId": str,
@@ -533,14 +601,28 @@
 )
 
 class GetPublicKeyRequestRequestTypeDef(
     _RequiredGetPublicKeyRequestRequestTypeDef, _OptionalGetPublicKeyRequestRequestTypeDef
 ):
     pass
 
+GetPublicKeyResponseTypeDef = TypedDict(
+    "GetPublicKeyResponseTypeDef",
+    {
+        "KeyId": str,
+        "PublicKey": bytes,
+        "CustomerMasterKeySpec": CustomerMasterKeySpecType,
+        "KeySpec": KeySpecType,
+        "KeyUsage": KeyUsageTypeType,
+        "EncryptionAlgorithms": List[EncryptionAlgorithmSpecType],
+        "SigningAlgorithms": List[SigningAlgorithmSpecType],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredImportKeyMaterialRequestRequestTypeDef = TypedDict(
     "_RequiredImportKeyMaterialRequestRequestTypeDef",
     {
         "KeyId": str,
         "ImportToken": Union[str, bytes, IO[Any], StreamingBody],
         "EncryptedKeyMaterial": Union[str, bytes, IO[Any], StreamingBody],
     },
@@ -572,24 +654,55 @@
     "XksKeyConfigurationTypeTypeDef",
     {
         "Id": str,
     },
     total=False,
 )
 
+ListAliasesRequestListAliasesPaginateTypeDef = TypedDict(
+    "ListAliasesRequestListAliasesPaginateTypeDef",
+    {
+        "KeyId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListAliasesRequestRequestTypeDef = TypedDict(
     "ListAliasesRequestRequestTypeDef",
     {
         "KeyId": str,
         "Limit": int,
         "Marker": str,
     },
     total=False,
 )
 
+_RequiredListGrantsRequestListGrantsPaginateTypeDef = TypedDict(
+    "_RequiredListGrantsRequestListGrantsPaginateTypeDef",
+    {
+        "KeyId": str,
+    },
+)
+_OptionalListGrantsRequestListGrantsPaginateTypeDef = TypedDict(
+    "_OptionalListGrantsRequestListGrantsPaginateTypeDef",
+    {
+        "GrantId": str,
+        "GranteePrincipal": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListGrantsRequestListGrantsPaginateTypeDef(
+    _RequiredListGrantsRequestListGrantsPaginateTypeDef,
+    _OptionalListGrantsRequestListGrantsPaginateTypeDef,
+):
+    pass
+
 _RequiredListGrantsRequestRequestTypeDef = TypedDict(
     "_RequiredListGrantsRequestRequestTypeDef",
     {
         "KeyId": str,
     },
 )
 _OptionalListGrantsRequestRequestTypeDef = TypedDict(
@@ -604,14 +717,34 @@
 )
 
 class ListGrantsRequestRequestTypeDef(
     _RequiredListGrantsRequestRequestTypeDef, _OptionalListGrantsRequestRequestTypeDef
 ):
     pass
 
+_RequiredListKeyPoliciesRequestListKeyPoliciesPaginateTypeDef = TypedDict(
+    "_RequiredListKeyPoliciesRequestListKeyPoliciesPaginateTypeDef",
+    {
+        "KeyId": str,
+    },
+)
+_OptionalListKeyPoliciesRequestListKeyPoliciesPaginateTypeDef = TypedDict(
+    "_OptionalListKeyPoliciesRequestListKeyPoliciesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListKeyPoliciesRequestListKeyPoliciesPaginateTypeDef(
+    _RequiredListKeyPoliciesRequestListKeyPoliciesPaginateTypeDef,
+    _OptionalListKeyPoliciesRequestListKeyPoliciesPaginateTypeDef,
+):
+    pass
+
 _RequiredListKeyPoliciesRequestRequestTypeDef = TypedDict(
     "_RequiredListKeyPoliciesRequestRequestTypeDef",
     {
         "KeyId": str,
     },
 )
 _OptionalListKeyPoliciesRequestRequestTypeDef = TypedDict(
@@ -624,23 +757,61 @@
 )
 
 class ListKeyPoliciesRequestRequestTypeDef(
     _RequiredListKeyPoliciesRequestRequestTypeDef, _OptionalListKeyPoliciesRequestRequestTypeDef
 ):
     pass
 
+ListKeyPoliciesResponseTypeDef = TypedDict(
+    "ListKeyPoliciesResponseTypeDef",
+    {
+        "PolicyNames": List[str],
+        "NextMarker": str,
+        "Truncated": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListKeysRequestListKeysPaginateTypeDef = TypedDict(
+    "ListKeysRequestListKeysPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListKeysRequestRequestTypeDef = TypedDict(
     "ListKeysRequestRequestTypeDef",
     {
         "Limit": int,
         "Marker": str,
     },
     total=False,
 )
 
+_RequiredListResourceTagsRequestListResourceTagsPaginateTypeDef = TypedDict(
+    "_RequiredListResourceTagsRequestListResourceTagsPaginateTypeDef",
+    {
+        "KeyId": str,
+    },
+)
+_OptionalListResourceTagsRequestListResourceTagsPaginateTypeDef = TypedDict(
+    "_OptionalListResourceTagsRequestListResourceTagsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListResourceTagsRequestListResourceTagsPaginateTypeDef(
+    _RequiredListResourceTagsRequestListResourceTagsPaginateTypeDef,
+    _OptionalListResourceTagsRequestListResourceTagsPaginateTypeDef,
+):
+    pass
+
 _RequiredListResourceTagsRequestRequestTypeDef = TypedDict(
     "_RequiredListResourceTagsRequestRequestTypeDef",
     {
         "KeyId": str,
     },
 )
 _OptionalListResourceTagsRequestRequestTypeDef = TypedDict(
@@ -653,14 +824,34 @@
 )
 
 class ListResourceTagsRequestRequestTypeDef(
     _RequiredListResourceTagsRequestRequestTypeDef, _OptionalListResourceTagsRequestRequestTypeDef
 ):
     pass
 
+_RequiredListRetirableGrantsRequestListRetirableGrantsPaginateTypeDef = TypedDict(
+    "_RequiredListRetirableGrantsRequestListRetirableGrantsPaginateTypeDef",
+    {
+        "RetiringPrincipal": str,
+    },
+)
+_OptionalListRetirableGrantsRequestListRetirableGrantsPaginateTypeDef = TypedDict(
+    "_OptionalListRetirableGrantsRequestListRetirableGrantsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListRetirableGrantsRequestListRetirableGrantsPaginateTypeDef(
+    _RequiredListRetirableGrantsRequestListRetirableGrantsPaginateTypeDef,
+    _OptionalListRetirableGrantsRequestListRetirableGrantsPaginateTypeDef,
+):
+    pass
+
 _RequiredListRetirableGrantsRequestRequestTypeDef = TypedDict(
     "_RequiredListRetirableGrantsRequestRequestTypeDef",
     {
         "RetiringPrincipal": str,
     },
 )
 _OptionalListRetirableGrantsRequestRequestTypeDef = TypedDict(
@@ -683,14 +874,24 @@
     {
         "Arn": str,
         "Region": str,
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
 _RequiredPutKeyPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredPutKeyPolicyRequestRequestTypeDef",
     {
         "KeyId": str,
         "PolicyName": str,
         "Policy": str,
     },
@@ -729,14 +930,37 @@
 )
 
 class ReEncryptRequestRequestTypeDef(
     _RequiredReEncryptRequestRequestTypeDef, _OptionalReEncryptRequestRequestTypeDef
 ):
     pass
 
+ReEncryptResponseTypeDef = TypedDict(
+    "ReEncryptResponseTypeDef",
+    {
+        "CiphertextBlob": bytes,
+        "SourceKeyId": str,
+        "KeyId": str,
+        "SourceEncryptionAlgorithm": EncryptionAlgorithmSpecType,
+        "DestinationEncryptionAlgorithm": EncryptionAlgorithmSpecType,
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
 RetireGrantRequestRequestTypeDef = TypedDict(
     "RetireGrantRequestRequestTypeDef",
     {
         "GrantToken": str,
         "KeyId": str,
         "GrantId": str,
     },
@@ -767,14 +991,25 @@
 
 class ScheduleKeyDeletionRequestRequestTypeDef(
     _RequiredScheduleKeyDeletionRequestRequestTypeDef,
     _OptionalScheduleKeyDeletionRequestRequestTypeDef,
 ):
     pass
 
+ScheduleKeyDeletionResponseTypeDef = TypedDict(
+    "ScheduleKeyDeletionResponseTypeDef",
+    {
+        "KeyId": str,
+        "DeletionDate": datetime,
+        "KeyState": KeyStateType,
+        "PendingWindowInDays": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredSignRequestRequestTypeDef = TypedDict(
     "_RequiredSignRequestRequestTypeDef",
     {
         "KeyId": str,
         "Message": Union[str, bytes, IO[Any], StreamingBody],
         "SigningAlgorithm": SigningAlgorithmSpecType,
     },
@@ -789,14 +1024,24 @@
 )
 
 class SignRequestRequestTypeDef(
     _RequiredSignRequestRequestTypeDef, _OptionalSignRequestRequestTypeDef
 ):
     pass
 
+SignResponseTypeDef = TypedDict(
+    "SignResponseTypeDef",
+    {
+        "KeyId": str,
+        "Signature": bytes,
+        "SigningAlgorithm": SigningAlgorithmSpecType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "KeyId": str,
         "TagKeys": Sequence[str],
     },
 )
@@ -843,14 +1088,24 @@
 )
 
 class VerifyMacRequestRequestTypeDef(
     _RequiredVerifyMacRequestRequestTypeDef, _OptionalVerifyMacRequestRequestTypeDef
 ):
     pass
 
+VerifyMacResponseTypeDef = TypedDict(
+    "VerifyMacResponseTypeDef",
+    {
+        "KeyId": str,
+        "MacValid": bool,
+        "MacAlgorithm": MacAlgorithmSpecType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredVerifyRequestRequestTypeDef = TypedDict(
     "_RequiredVerifyRequestRequestTypeDef",
     {
         "KeyId": str,
         "Message": Union[str, bytes, IO[Any], StreamingBody],
         "Signature": Union[str, bytes, IO[Any], StreamingBody],
         "SigningAlgorithm": SigningAlgorithmSpecType,
@@ -866,237 +1121,31 @@
 )
 
 class VerifyRequestRequestTypeDef(
     _RequiredVerifyRequestRequestTypeDef, _OptionalVerifyRequestRequestTypeDef
 ):
     pass
 
-CancelKeyDeletionResponseTypeDef = TypedDict(
-    "CancelKeyDeletionResponseTypeDef",
-    {
-        "KeyId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateCustomKeyStoreResponseTypeDef = TypedDict(
-    "CreateCustomKeyStoreResponseTypeDef",
-    {
-        "CustomKeyStoreId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateGrantResponseTypeDef = TypedDict(
-    "CreateGrantResponseTypeDef",
-    {
-        "GrantToken": str,
-        "GrantId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DecryptResponseTypeDef = TypedDict(
-    "DecryptResponseTypeDef",
-    {
-        "KeyId": str,
-        "Plaintext": bytes,
-        "EncryptionAlgorithm": EncryptionAlgorithmSpecType,
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
-EncryptResponseTypeDef = TypedDict(
-    "EncryptResponseTypeDef",
-    {
-        "CiphertextBlob": bytes,
-        "KeyId": str,
-        "EncryptionAlgorithm": EncryptionAlgorithmSpecType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GenerateDataKeyPairResponseTypeDef = TypedDict(
-    "GenerateDataKeyPairResponseTypeDef",
-    {
-        "PrivateKeyCiphertextBlob": bytes,
-        "PrivateKeyPlaintext": bytes,
-        "PublicKey": bytes,
-        "KeyId": str,
-        "KeyPairSpec": DataKeyPairSpecType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GenerateDataKeyPairWithoutPlaintextResponseTypeDef = TypedDict(
-    "GenerateDataKeyPairWithoutPlaintextResponseTypeDef",
-    {
-        "PrivateKeyCiphertextBlob": bytes,
-        "PublicKey": bytes,
-        "KeyId": str,
-        "KeyPairSpec": DataKeyPairSpecType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GenerateDataKeyResponseTypeDef = TypedDict(
-    "GenerateDataKeyResponseTypeDef",
-    {
-        "CiphertextBlob": bytes,
-        "Plaintext": bytes,
-        "KeyId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GenerateDataKeyWithoutPlaintextResponseTypeDef = TypedDict(
-    "GenerateDataKeyWithoutPlaintextResponseTypeDef",
-    {
-        "CiphertextBlob": bytes,
-        "KeyId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GenerateMacResponseTypeDef = TypedDict(
-    "GenerateMacResponseTypeDef",
-    {
-        "Mac": bytes,
-        "MacAlgorithm": MacAlgorithmSpecType,
-        "KeyId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GenerateRandomResponseTypeDef = TypedDict(
-    "GenerateRandomResponseTypeDef",
-    {
-        "Plaintext": bytes,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetKeyPolicyResponseTypeDef = TypedDict(
-    "GetKeyPolicyResponseTypeDef",
-    {
-        "Policy": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetKeyRotationStatusResponseTypeDef = TypedDict(
-    "GetKeyRotationStatusResponseTypeDef",
-    {
-        "KeyRotationEnabled": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetParametersForImportResponseTypeDef = TypedDict(
-    "GetParametersForImportResponseTypeDef",
-    {
-        "KeyId": str,
-        "ImportToken": bytes,
-        "PublicKey": bytes,
-        "ParametersValidTo": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetPublicKeyResponseTypeDef = TypedDict(
-    "GetPublicKeyResponseTypeDef",
+VerifyResponseTypeDef = TypedDict(
+    "VerifyResponseTypeDef",
     {
         "KeyId": str,
-        "PublicKey": bytes,
-        "CustomerMasterKeySpec": CustomerMasterKeySpecType,
-        "KeySpec": KeySpecType,
-        "KeyUsage": KeyUsageTypeType,
-        "EncryptionAlgorithms": List[EncryptionAlgorithmSpecType],
-        "SigningAlgorithms": List[SigningAlgorithmSpecType],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "SignatureValid": bool,
+        "SigningAlgorithm": SigningAlgorithmSpecType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAliasesResponseTypeDef = TypedDict(
     "ListAliasesResponseTypeDef",
     {
         "Aliases": List[AliasListEntryTypeDef],
         "NextMarker": str,
         "Truncated": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListKeyPoliciesResponseTypeDef = TypedDict(
-    "ListKeyPoliciesResponseTypeDef",
-    {
-        "PolicyNames": List[str],
-        "NextMarker": str,
-        "Truncated": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ReEncryptResponseTypeDef = TypedDict(
-    "ReEncryptResponseTypeDef",
-    {
-        "CiphertextBlob": bytes,
-        "SourceKeyId": str,
-        "KeyId": str,
-        "SourceEncryptionAlgorithm": EncryptionAlgorithmSpecType,
-        "DestinationEncryptionAlgorithm": EncryptionAlgorithmSpecType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ScheduleKeyDeletionResponseTypeDef = TypedDict(
-    "ScheduleKeyDeletionResponseTypeDef",
-    {
-        "KeyId": str,
-        "DeletionDate": datetime,
-        "KeyState": KeyStateType,
-        "PendingWindowInDays": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SignResponseTypeDef = TypedDict(
-    "SignResponseTypeDef",
-    {
-        "KeyId": str,
-        "Signature": bytes,
-        "SigningAlgorithm": SigningAlgorithmSpecType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-VerifyMacResponseTypeDef = TypedDict(
-    "VerifyMacResponseTypeDef",
-    {
-        "KeyId": str,
-        "MacValid": bool,
-        "MacAlgorithm": MacAlgorithmSpecType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-VerifyResponseTypeDef = TypedDict(
-    "VerifyResponseTypeDef",
-    {
-        "KeyId": str,
-        "SignatureValid": bool,
-        "SigningAlgorithm": SigningAlgorithmSpecType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateCustomKeyStoreRequestRequestTypeDef = TypedDict(
     "_RequiredCreateCustomKeyStoreRequestRequestTypeDef",
     {
         "CustomKeyStoreName": str,
@@ -1211,15 +1260,15 @@
 
 ListResourceTagsResponseTypeDef = TypedDict(
     "ListResourceTagsResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
         "NextMarker": str,
         "Truncated": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredReplicateKeyRequestRequestTypeDef = TypedDict(
     "_RequiredReplicateKeyRequestRequestTypeDef",
     {
         "KeyId": str,
@@ -1262,130 +1311,100 @@
         "CreationDate": datetime,
         "CustomKeyStoreType": CustomKeyStoreTypeType,
         "XksProxyConfiguration": XksProxyConfigurationTypeTypeDef,
     },
     total=False,
 )
 
-DescribeCustomKeyStoresRequestDescribeCustomKeyStoresPaginateTypeDef = TypedDict(
-    "DescribeCustomKeyStoresRequestDescribeCustomKeyStoresPaginateTypeDef",
-    {
-        "CustomKeyStoreId": str,
-        "CustomKeyStoreName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListAliasesRequestListAliasesPaginateTypeDef = TypedDict(
-    "ListAliasesRequestListAliasesPaginateTypeDef",
+_RequiredDecryptRequestRequestTypeDef = TypedDict(
+    "_RequiredDecryptRequestRequestTypeDef",
     {
-        "KeyId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "CiphertextBlob": Union[str, bytes, IO[Any], StreamingBody],
     },
-    total=False,
 )
-
-_RequiredListGrantsRequestListGrantsPaginateTypeDef = TypedDict(
-    "_RequiredListGrantsRequestListGrantsPaginateTypeDef",
+_OptionalDecryptRequestRequestTypeDef = TypedDict(
+    "_OptionalDecryptRequestRequestTypeDef",
     {
+        "EncryptionContext": Mapping[str, str],
+        "GrantTokens": Sequence[str],
         "KeyId": str,
-    },
-)
-_OptionalListGrantsRequestListGrantsPaginateTypeDef = TypedDict(
-    "_OptionalListGrantsRequestListGrantsPaginateTypeDef",
-    {
-        "GrantId": str,
-        "GranteePrincipal": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "EncryptionAlgorithm": EncryptionAlgorithmSpecType,
+        "Recipient": RecipientInfoTypeDef,
     },
     total=False,
 )
 
-class ListGrantsRequestListGrantsPaginateTypeDef(
-    _RequiredListGrantsRequestListGrantsPaginateTypeDef,
-    _OptionalListGrantsRequestListGrantsPaginateTypeDef,
+class DecryptRequestRequestTypeDef(
+    _RequiredDecryptRequestRequestTypeDef, _OptionalDecryptRequestRequestTypeDef
 ):
     pass
 
-_RequiredListKeyPoliciesRequestListKeyPoliciesPaginateTypeDef = TypedDict(
-    "_RequiredListKeyPoliciesRequestListKeyPoliciesPaginateTypeDef",
+_RequiredGenerateDataKeyPairRequestRequestTypeDef = TypedDict(
+    "_RequiredGenerateDataKeyPairRequestRequestTypeDef",
     {
         "KeyId": str,
+        "KeyPairSpec": DataKeyPairSpecType,
     },
 )
-_OptionalListKeyPoliciesRequestListKeyPoliciesPaginateTypeDef = TypedDict(
-    "_OptionalListKeyPoliciesRequestListKeyPoliciesPaginateTypeDef",
+_OptionalGenerateDataKeyPairRequestRequestTypeDef = TypedDict(
+    "_OptionalGenerateDataKeyPairRequestRequestTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "EncryptionContext": Mapping[str, str],
+        "GrantTokens": Sequence[str],
+        "Recipient": RecipientInfoTypeDef,
     },
     total=False,
 )
 
-class ListKeyPoliciesRequestListKeyPoliciesPaginateTypeDef(
-    _RequiredListKeyPoliciesRequestListKeyPoliciesPaginateTypeDef,
-    _OptionalListKeyPoliciesRequestListKeyPoliciesPaginateTypeDef,
+class GenerateDataKeyPairRequestRequestTypeDef(
+    _RequiredGenerateDataKeyPairRequestRequestTypeDef,
+    _OptionalGenerateDataKeyPairRequestRequestTypeDef,
 ):
     pass
 
-ListKeysRequestListKeysPaginateTypeDef = TypedDict(
-    "ListKeysRequestListKeysPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListResourceTagsRequestListResourceTagsPaginateTypeDef = TypedDict(
-    "_RequiredListResourceTagsRequestListResourceTagsPaginateTypeDef",
+_RequiredGenerateDataKeyRequestRequestTypeDef = TypedDict(
+    "_RequiredGenerateDataKeyRequestRequestTypeDef",
     {
         "KeyId": str,
     },
 )
-_OptionalListResourceTagsRequestListResourceTagsPaginateTypeDef = TypedDict(
-    "_OptionalListResourceTagsRequestListResourceTagsPaginateTypeDef",
+_OptionalGenerateDataKeyRequestRequestTypeDef = TypedDict(
+    "_OptionalGenerateDataKeyRequestRequestTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "EncryptionContext": Mapping[str, str],
+        "NumberOfBytes": int,
+        "KeySpec": DataKeySpecType,
+        "GrantTokens": Sequence[str],
+        "Recipient": RecipientInfoTypeDef,
     },
     total=False,
 )
 
-class ListResourceTagsRequestListResourceTagsPaginateTypeDef(
-    _RequiredListResourceTagsRequestListResourceTagsPaginateTypeDef,
-    _OptionalListResourceTagsRequestListResourceTagsPaginateTypeDef,
+class GenerateDataKeyRequestRequestTypeDef(
+    _RequiredGenerateDataKeyRequestRequestTypeDef, _OptionalGenerateDataKeyRequestRequestTypeDef
 ):
     pass
 
-_RequiredListRetirableGrantsRequestListRetirableGrantsPaginateTypeDef = TypedDict(
-    "_RequiredListRetirableGrantsRequestListRetirableGrantsPaginateTypeDef",
-    {
-        "RetiringPrincipal": str,
-    },
-)
-_OptionalListRetirableGrantsRequestListRetirableGrantsPaginateTypeDef = TypedDict(
-    "_OptionalListRetirableGrantsRequestListRetirableGrantsPaginateTypeDef",
+GenerateRandomRequestRequestTypeDef = TypedDict(
+    "GenerateRandomRequestRequestTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "NumberOfBytes": int,
+        "CustomKeyStoreId": str,
+        "Recipient": RecipientInfoTypeDef,
     },
     total=False,
 )
 
-class ListRetirableGrantsRequestListRetirableGrantsPaginateTypeDef(
-    _RequiredListRetirableGrantsRequestListRetirableGrantsPaginateTypeDef,
-    _OptionalListRetirableGrantsRequestListRetirableGrantsPaginateTypeDef,
-):
-    pass
-
 ListKeysResponseTypeDef = TypedDict(
     "ListKeysResponseTypeDef",
     {
         "Keys": List[KeyListEntryTypeDef],
         "NextMarker": str,
         "Truncated": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 MultiRegionConfigurationTypeDef = TypedDict(
     "MultiRegionConfigurationTypeDef",
     {
         "MultiRegionKeyType": MultiRegionKeyTypeType,
@@ -1397,25 +1416,25 @@
 
 ListGrantsResponseTypeDef = TypedDict(
     "ListGrantsResponseTypeDef",
     {
         "Grants": List[GrantListEntryTypeDef],
         "NextMarker": str,
         "Truncated": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeCustomKeyStoresResponseTypeDef = TypedDict(
     "DescribeCustomKeyStoresResponseTypeDef",
     {
         "CustomKeyStores": List[CustomKeyStoresListEntryTypeDef],
         "NextMarker": str,
         "Truncated": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredKeyMetadataTypeDef = TypedDict(
     "_RequiredKeyMetadataTypeDef",
     {
         "KeyId": str,
@@ -1454,28 +1473,28 @@
 class KeyMetadataTypeDef(_RequiredKeyMetadataTypeDef, _OptionalKeyMetadataTypeDef):
     pass
 
 CreateKeyResponseTypeDef = TypedDict(
     "CreateKeyResponseTypeDef",
     {
         "KeyMetadata": KeyMetadataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeKeyResponseTypeDef = TypedDict(
     "DescribeKeyResponseTypeDef",
     {
         "KeyMetadata": KeyMetadataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReplicateKeyResponseTypeDef = TypedDict(
     "ReplicateKeyResponseTypeDef",
     {
         "ReplicaKeyMetadata": KeyMetadataTypeDef,
         "ReplicaPolicy": str,
         "ReplicaTags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-kms-2.5.0.post1/types_aiobotocore_kms.egg-info/PKG-INFO` & `types-aiobotocore-kms-2.5.1/types_aiobotocore_kms.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-kms
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.KMS 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.KMS 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-kms"></a>
 
 # types-aiobotocore-kms
 
 [![PyPI - types-aiobotocore-kms](https://img.shields.io/pypi/v/types-aiobotocore-kms.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kms)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-kms.svg?color=blue)](https://pypi.org/project/types-aiobotocore-kms)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-kms?color=blue)](https://pypistats.org/packages/types-aiobotocore-kms)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.KMS 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS)
+[aiobotocore.KMS 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/kms.html#KMS)
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
 [types-aiobotocore-kms docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kms/).
 
 See how it helps to find and fix potential bugs:
 
@@ -323,14 +323,15 @@
     CustomerMasterKeySpecType,
     DataKeyPairSpecType,
     DataKeySpecType,
     DescribeCustomKeyStoresPaginatorName,
     EncryptionAlgorithmSpecType,
     ExpirationModelTypeType,
     GrantOperationType,
+    KeyEncryptionMechanismType,
     KeyManagerTypeType,
     KeySpecType,
     KeyStateType,
     KeyUsageTypeType,
     ListAliasesPaginatorName,
     ListGrantsPaginatorName,
     ListKeyPoliciesPaginatorName,
@@ -363,105 +364,106 @@
 `types_aiobotocore_kms.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_kms.type_defs import (
     AliasListEntryTypeDef,
     CancelKeyDeletionRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CancelKeyDeletionResponseTypeDef,
     ConnectCustomKeyStoreRequestRequestTypeDef,
     CreateAliasRequestRequestTypeDef,
     XksProxyAuthenticationCredentialTypeTypeDef,
+    CreateCustomKeyStoreResponseTypeDef,
     GrantConstraintsTypeDef,
+    CreateGrantResponseTypeDef,
     TagTypeDef,
     XksProxyConfigurationTypeTypeDef,
-    DecryptRequestRequestTypeDef,
+    RecipientInfoTypeDef,
+    DecryptResponseTypeDef,
     DeleteAliasRequestRequestTypeDef,
     DeleteCustomKeyStoreRequestRequestTypeDef,
     DeleteImportedKeyMaterialRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeCustomKeyStoresRequestDescribeCustomKeyStoresPaginateTypeDef,
     DescribeCustomKeyStoresRequestRequestTypeDef,
     DescribeKeyRequestRequestTypeDef,
     DisableKeyRequestRequestTypeDef,
     DisableKeyRotationRequestRequestTypeDef,
     DisconnectCustomKeyStoreRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EnableKeyRequestRequestTypeDef,
     EnableKeyRotationRequestRequestTypeDef,
     EncryptRequestRequestTypeDef,
-    GenerateDataKeyPairRequestRequestTypeDef,
+    EncryptResponseTypeDef,
+    GenerateDataKeyPairResponseTypeDef,
     GenerateDataKeyPairWithoutPlaintextRequestRequestTypeDef,
-    GenerateDataKeyRequestRequestTypeDef,
+    GenerateDataKeyPairWithoutPlaintextResponseTypeDef,
+    GenerateDataKeyResponseTypeDef,
     GenerateDataKeyWithoutPlaintextRequestRequestTypeDef,
+    GenerateDataKeyWithoutPlaintextResponseTypeDef,
     GenerateMacRequestRequestTypeDef,
-    GenerateRandomRequestRequestTypeDef,
+    GenerateMacResponseTypeDef,
+    GenerateRandomResponseTypeDef,
     GetKeyPolicyRequestRequestTypeDef,
+    GetKeyPolicyResponseTypeDef,
     GetKeyRotationStatusRequestRequestTypeDef,
+    GetKeyRotationStatusResponseTypeDef,
     GetParametersForImportRequestRequestTypeDef,
+    GetParametersForImportResponseTypeDef,
     GetPublicKeyRequestRequestTypeDef,
+    GetPublicKeyResponseTypeDef,
     ImportKeyMaterialRequestRequestTypeDef,
     KeyListEntryTypeDef,
     XksKeyConfigurationTypeTypeDef,
+    ListAliasesRequestListAliasesPaginateTypeDef,
     ListAliasesRequestRequestTypeDef,
+    ListGrantsRequestListGrantsPaginateTypeDef,
     ListGrantsRequestRequestTypeDef,
+    ListKeyPoliciesRequestListKeyPoliciesPaginateTypeDef,
     ListKeyPoliciesRequestRequestTypeDef,
+    ListKeyPoliciesResponseTypeDef,
+    ListKeysRequestListKeysPaginateTypeDef,
     ListKeysRequestRequestTypeDef,
+    ListResourceTagsRequestListResourceTagsPaginateTypeDef,
     ListResourceTagsRequestRequestTypeDef,
+    ListRetirableGrantsRequestListRetirableGrantsPaginateTypeDef,
     ListRetirableGrantsRequestRequestTypeDef,
     MultiRegionKeyTypeDef,
+    PaginatorConfigTypeDef,
     PutKeyPolicyRequestRequestTypeDef,
     ReEncryptRequestRequestTypeDef,
+    ReEncryptResponseTypeDef,
+    ResponseMetadataTypeDef,
     RetireGrantRequestRequestTypeDef,
     RevokeGrantRequestRequestTypeDef,
     ScheduleKeyDeletionRequestRequestTypeDef,
+    ScheduleKeyDeletionResponseTypeDef,
     SignRequestRequestTypeDef,
+    SignResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateAliasRequestRequestTypeDef,
     UpdateKeyDescriptionRequestRequestTypeDef,
     UpdatePrimaryRegionRequestRequestTypeDef,
     VerifyMacRequestRequestTypeDef,
-    VerifyRequestRequestTypeDef,
-    CancelKeyDeletionResponseTypeDef,
-    CreateCustomKeyStoreResponseTypeDef,
-    CreateGrantResponseTypeDef,
-    DecryptResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    EncryptResponseTypeDef,
-    GenerateDataKeyPairResponseTypeDef,
-    GenerateDataKeyPairWithoutPlaintextResponseTypeDef,
-    GenerateDataKeyResponseTypeDef,
-    GenerateDataKeyWithoutPlaintextResponseTypeDef,
-    GenerateMacResponseTypeDef,
-    GenerateRandomResponseTypeDef,
-    GetKeyPolicyResponseTypeDef,
-    GetKeyRotationStatusResponseTypeDef,
-    GetParametersForImportResponseTypeDef,
-    GetPublicKeyResponseTypeDef,
-    ListAliasesResponseTypeDef,
-    ListKeyPoliciesResponseTypeDef,
-    ReEncryptResponseTypeDef,
-    ScheduleKeyDeletionResponseTypeDef,
-    SignResponseTypeDef,
     VerifyMacResponseTypeDef,
+    VerifyRequestRequestTypeDef,
     VerifyResponseTypeDef,
+    ListAliasesResponseTypeDef,
     CreateCustomKeyStoreRequestRequestTypeDef,
     UpdateCustomKeyStoreRequestRequestTypeDef,
     CreateGrantRequestRequestTypeDef,
     GrantListEntryTypeDef,
     CreateKeyRequestRequestTypeDef,
     ListResourceTagsResponseTypeDef,
     ReplicateKeyRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     CustomKeyStoresListEntryTypeDef,
-    DescribeCustomKeyStoresRequestDescribeCustomKeyStoresPaginateTypeDef,
-    ListAliasesRequestListAliasesPaginateTypeDef,
-    ListGrantsRequestListGrantsPaginateTypeDef,
-    ListKeyPoliciesRequestListKeyPoliciesPaginateTypeDef,
-    ListKeysRequestListKeysPaginateTypeDef,
-    ListResourceTagsRequestListResourceTagsPaginateTypeDef,
-    ListRetirableGrantsRequestListRetirableGrantsPaginateTypeDef,
+    DecryptRequestRequestTypeDef,
+    GenerateDataKeyPairRequestRequestTypeDef,
+    GenerateDataKeyRequestRequestTypeDef,
+    GenerateRandomRequestRequestTypeDef,
     ListKeysResponseTypeDef,
     MultiRegionConfigurationTypeDef,
     ListGrantsResponseTypeDef,
     DescribeCustomKeyStoresResponseTypeDef,
     KeyMetadataTypeDef,
     CreateKeyResponseTypeDef,
     DescribeKeyResponseTypeDef,
@@ -476,43 +478,43 @@
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

### Comparing `types-aiobotocore-kms-2.5.0.post1/types_aiobotocore_kms.egg-info/SOURCES.txt` & `types-aiobotocore-kms-2.5.1/types_aiobotocore_kms.egg-info/SOURCES.txt`

 * *Files identical despite different names*

