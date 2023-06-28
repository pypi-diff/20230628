# Comparing `tmp/types-aiobotocore-glacier-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-glacier-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-glacier-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:40 2023, max compression
+gzip compressed data, was "types-aiobotocore-glacier-2.5.1.tar", last modified: Wed Jun 28 01:43:31 2023, max compression
```

## Comparing `types-aiobotocore-glacier-2.5.0.post1.tar` & `types-aiobotocore-glacier-2.5.1.tar`

### file list

```diff
@@ -1,31 +1,31 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:40.359233 types-aiobotocore-glacier-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:15:01.000000 types-aiobotocore-glacier-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    20908 2023-03-11 12:26:40.351233 types-aiobotocore-glacier-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    19337 2023-03-11 12:15:01.000000 types-aiobotocore-glacier-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:40.359233 types-aiobotocore-glacier-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2124 2023-03-11 12:15:01.000000 types-aiobotocore-glacier-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:40.351233 types-aiobotocore-glacier-2.5.0.post1/types_aiobotocore_glacier/
--rw-r--r--   0 runner    (1001) docker     (123)     1692 2023-03-11 12:15:01.000000 types-aiobotocore-glacier-2.5.0.post1/types_aiobotocore_glacier/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1691 2023-03-11 12:15:01.000000 types-aiobotocore-glacier-2.5.0.post1/types_aiobotocore_glacier/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      943 2023-03-11 12:15:01.000000 types-aiobotocore-glacier-2.5.0.post1/types_aiobotocore_glacier/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    28530 2023-03-11 12:15:01.000000 types-aiobotocore-glacier-2.5.0.post1/types_aiobotocore_glacier/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    28482 2023-03-11 12:15:01.000000 types-aiobotocore-glacier-2.5.0.post1/types_aiobotocore_glacier/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9438 2023-03-11 12:15:03.000000 types-aiobotocore-glacier-2.5.0.post1/types_aiobotocore_glacier/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9436 2023-03-11 12:15:03.000000 types-aiobotocore-glacier-2.5.0.post1/types_aiobotocore_glacier/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     5430 2023-03-11 12:15:02.000000 types-aiobotocore-glacier-2.5.0.post1/types_aiobotocore_glacier/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     5423 2023-03-11 12:15:02.000000 types-aiobotocore-glacier-2.5.0.post1/types_aiobotocore_glacier/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:15:01.000000 types-aiobotocore-glacier-2.5.0.post1/types_aiobotocore_glacier/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    43090 2023-03-11 12:15:02.000000 types-aiobotocore-glacier-2.5.0.post1/types_aiobotocore_glacier/service_resource.py
--rw-r--r--   0 runner    (1001) docker     (123)    42972 2023-03-11 12:15:01.000000 types-aiobotocore-glacier-2.5.0.post1/types_aiobotocore_glacier/service_resource.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    40508 2023-03-11 12:15:04.000000 types-aiobotocore-glacier-2.5.0.post1/types_aiobotocore_glacier/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    40436 2023-03-11 12:15:04.000000 types-aiobotocore-glacier-2.5.0.post1/types_aiobotocore_glacier/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:15:01.000000 types-aiobotocore-glacier-2.5.0.post1/types_aiobotocore_glacier/version.py
--rw-r--r--   0 runner    (1001) docker     (123)     2483 2023-03-11 12:15:02.000000 types-aiobotocore-glacier-2.5.0.post1/types_aiobotocore_glacier/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)     2481 2023-03-11 12:15:02.000000 types-aiobotocore-glacier-2.5.0.post1/types_aiobotocore_glacier/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:40.351233 types-aiobotocore-glacier-2.5.0.post1/types_aiobotocore_glacier.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    20908 2023-03-11 12:26:40.000000 types-aiobotocore-glacier-2.5.0.post1/types_aiobotocore_glacier.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      979 2023-03-11 12:26:40.000000 types-aiobotocore-glacier-2.5.0.post1/types_aiobotocore_glacier.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:40.000000 types-aiobotocore-glacier-2.5.0.post1/types_aiobotocore_glacier.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:40.000000 types-aiobotocore-glacier-2.5.0.post1/types_aiobotocore_glacier.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:40.000000 types-aiobotocore-glacier-2.5.0.post1/types_aiobotocore_glacier.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       26 2023-03-11 12:26:40.000000 types-aiobotocore-glacier-2.5.0.post1/types_aiobotocore_glacier.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:31.954141 types-aiobotocore-glacier-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:31:37.000000 types-aiobotocore-glacier-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    20509 2023-06-28 01:43:31.946141 types-aiobotocore-glacier-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    18944 2023-06-28 01:31:37.000000 types-aiobotocore-glacier-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:31.954141 types-aiobotocore-glacier-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2118 2023-06-28 01:31:37.000000 types-aiobotocore-glacier-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:31.946141 types-aiobotocore-glacier-2.5.1/types_aiobotocore_glacier/
+-rw-r--r--   0 runner    (1001) docker     (123)     1692 2023-06-28 01:31:37.000000 types-aiobotocore-glacier-2.5.1/types_aiobotocore_glacier/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1691 2023-06-28 01:31:37.000000 types-aiobotocore-glacier-2.5.1/types_aiobotocore_glacier/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      931 2023-06-28 01:31:37.000000 types-aiobotocore-glacier-2.5.1/types_aiobotocore_glacier/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    28540 2023-06-28 01:31:38.000000 types-aiobotocore-glacier-2.5.1/types_aiobotocore_glacier/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    28492 2023-06-28 01:31:38.000000 types-aiobotocore-glacier-2.5.1/types_aiobotocore_glacier/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9647 2023-06-28 01:31:38.000000 types-aiobotocore-glacier-2.5.1/types_aiobotocore_glacier/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9645 2023-06-28 01:31:38.000000 types-aiobotocore-glacier-2.5.1/types_aiobotocore_glacier/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     5318 2023-06-28 01:31:38.000000 types-aiobotocore-glacier-2.5.1/types_aiobotocore_glacier/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5312 2023-06-28 01:31:38.000000 types-aiobotocore-glacier-2.5.1/types_aiobotocore_glacier/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:31:37.000000 types-aiobotocore-glacier-2.5.1/types_aiobotocore_glacier/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    42972 2023-06-28 01:31:38.000000 types-aiobotocore-glacier-2.5.1/types_aiobotocore_glacier/service_resource.py
+-rw-r--r--   0 runner    (1001) docker     (123)    42854 2023-06-28 01:31:38.000000 types-aiobotocore-glacier-2.5.1/types_aiobotocore_glacier/service_resource.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    38693 2023-06-28 01:31:40.000000 types-aiobotocore-glacier-2.5.1/types_aiobotocore_glacier/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    38621 2023-06-28 01:31:40.000000 types-aiobotocore-glacier-2.5.1/types_aiobotocore_glacier/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:31:37.000000 types-aiobotocore-glacier-2.5.1/types_aiobotocore_glacier/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2483 2023-06-28 01:31:38.000000 types-aiobotocore-glacier-2.5.1/types_aiobotocore_glacier/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2481 2023-06-28 01:31:38.000000 types-aiobotocore-glacier-2.5.1/types_aiobotocore_glacier/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:31.946141 types-aiobotocore-glacier-2.5.1/types_aiobotocore_glacier.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    20509 2023-06-28 01:43:31.000000 types-aiobotocore-glacier-2.5.1/types_aiobotocore_glacier.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      979 2023-06-28 01:43:31.000000 types-aiobotocore-glacier-2.5.1/types_aiobotocore_glacier.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:31.000000 types-aiobotocore-glacier-2.5.1/types_aiobotocore_glacier.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:31.000000 types-aiobotocore-glacier-2.5.1/types_aiobotocore_glacier.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:31.000000 types-aiobotocore-glacier-2.5.1/types_aiobotocore_glacier.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       26 2023-06-28 01:43:31.000000 types-aiobotocore-glacier-2.5.1/types_aiobotocore_glacier.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-glacier-2.5.0.post1/LICENSE` & `types-aiobotocore-glacier-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-glacier-2.5.0.post1/PKG-INFO` & `types-aiobotocore-glacier-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-glacier
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Glacier 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Glacier 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glacier/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-glacier"></a>
 
 # types-aiobotocore-glacier
 
 [![PyPI - types-aiobotocore-glacier](https://img.shields.io/pypi/v/types-aiobotocore-glacier.svg?color=blue)](https://pypi.org/project/types-aiobotocore-glacier)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-glacier.svg?color=blue)](https://pypi.org/project/types-aiobotocore-glacier)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glacier/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-glacier?color=blue)](https://pypistats.org/packages/types-aiobotocore-glacier)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Glacier 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glacier.html#Glacier)
+[aiobotocore.Glacier 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glacier.html#Glacier)
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
 [types-aiobotocore-glacier docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glacier/).
 
 See how it helps to find and fix potential bugs:
 
@@ -442,105 +442,95 @@
 `types_aiobotocore_glacier.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_glacier.type_defs import (
     AbortMultipartUploadInputRequestTypeDef,
     AbortVaultLockInputRequestTypeDef,
-    AccountVaultRequestTypeDef,
     AddTagsToVaultInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    ArchiveCreationOutputTypeDef,
     CSVInputTypeDef,
     CSVOutputTypeDef,
     CompleteMultipartUploadInputMultipartUploadCompleteTypeDef,
     CompleteMultipartUploadInputRequestTypeDef,
     CompleteVaultLockInputRequestTypeDef,
     CreateVaultInputAccountCreateVaultTypeDef,
     CreateVaultInputRequestTypeDef,
     CreateVaultInputServiceResourceCreateVaultTypeDef,
+    CreateVaultOutputTypeDef,
     DataRetrievalRuleTypeDef,
     DeleteArchiveInputRequestTypeDef,
     DeleteVaultAccessPolicyInputRequestTypeDef,
     DeleteVaultInputRequestTypeDef,
     DeleteVaultNotificationsInputRequestTypeDef,
     DescribeJobInputRequestTypeDef,
     DescribeVaultInputRequestTypeDef,
     WaiterConfigTypeDef,
+    DescribeVaultOutputResponseMetadataTypeDef,
     DescribeVaultOutputTypeDef,
+    EmptyResponseMetadataTypeDef,
     EncryptionTypeDef,
     GetDataRetrievalPolicyInputRequestTypeDef,
     GetJobOutputInputJobGetOutputTypeDef,
     GetJobOutputInputRequestTypeDef,
+    GetJobOutputOutputTypeDef,
     GetVaultAccessPolicyInputRequestTypeDef,
     VaultAccessPolicyTypeDef,
     GetVaultLockInputRequestTypeDef,
+    GetVaultLockOutputTypeDef,
     GetVaultNotificationsInputRequestTypeDef,
     VaultNotificationConfigTypeDef,
     InventoryRetrievalJobDescriptionTypeDef,
     GranteeTypeDef,
+    InitiateJobOutputTypeDef,
     InitiateMultipartUploadInputRequestTypeDef,
     InitiateMultipartUploadInputVaultInitiateMultipartUploadTypeDef,
+    InitiateMultipartUploadOutputTypeDef,
     VaultLockPolicyTypeDef,
+    InitiateVaultLockOutputTypeDef,
+    InventoryRetrievalJobDescriptionResponseMetadataTypeDef,
     InventoryRetrievalJobInputTypeDef,
-    PaginatorConfigTypeDef,
+    ListJobsInputListJobsPaginateTypeDef,
     ListJobsInputRequestTypeDef,
+    ListMultipartUploadsInputListMultipartUploadsPaginateTypeDef,
     ListMultipartUploadsInputRequestTypeDef,
     UploadListElementTypeDef,
+    ListPartsInputListPartsPaginateTypeDef,
     ListPartsInputMultipartUploadPartsTypeDef,
     ListPartsInputRequestTypeDef,
     PartListElementTypeDef,
     ListProvisionedCapacityInputRequestTypeDef,
     ProvisionedCapacityDescriptionTypeDef,
     ListTagsForVaultInputRequestTypeDef,
+    ListTagsForVaultOutputTypeDef,
+    ListVaultsInputListVaultsPaginateTypeDef,
     ListVaultsInputRequestTypeDef,
+    PaginatorConfigTypeDef,
     PurchaseProvisionedCapacityInputRequestTypeDef,
+    PurchaseProvisionedCapacityOutputTypeDef,
     RemoveTagsFromVaultInputRequestTypeDef,
-    ServiceResourceAccountRequestTypeDef,
-    ServiceResourceArchiveRequestTypeDef,
-    ServiceResourceJobRequestTypeDef,
-    ServiceResourceMultipartUploadRequestTypeDef,
-    ServiceResourceNotificationRequestTypeDef,
-    ServiceResourceVaultRequestTypeDef,
+    ResponseMetadataTypeDef,
     UploadArchiveInputRequestTypeDef,
     UploadArchiveInputVaultUploadArchiveTypeDef,
     UploadMultipartPartInputMultipartUploadUploadPartTypeDef,
     UploadMultipartPartInputRequestTypeDef,
-    VaultArchiveRequestTypeDef,
-    VaultJobRequestTypeDef,
-    VaultMultipartUploadRequestTypeDef,
-    ArchiveCreationOutputTypeDef,
-    CreateVaultOutputTypeDef,
-    DescribeVaultOutputResponseMetadataTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetJobOutputOutputTypeDef,
-    GetVaultLockOutputTypeDef,
-    InitiateJobOutputTypeDef,
-    InitiateMultipartUploadOutputTypeDef,
-    InitiateVaultLockOutputTypeDef,
-    InventoryRetrievalJobDescriptionResponseMetadataTypeDef,
-    ListTagsForVaultOutputTypeDef,
-    PurchaseProvisionedCapacityOutputTypeDef,
     UploadMultipartPartOutputTypeDef,
     InputSerializationTypeDef,
     OutputSerializationTypeDef,
     DataRetrievalPolicyTypeDef,
     DescribeVaultInputVaultExistsWaitTypeDef,
     DescribeVaultInputVaultNotExistsWaitTypeDef,
     ListVaultsOutputTypeDef,
     GetVaultAccessPolicyOutputTypeDef,
     SetVaultAccessPolicyInputRequestTypeDef,
     GetVaultNotificationsOutputTypeDef,
     SetVaultNotificationsInputNotificationSetTypeDef,
     SetVaultNotificationsInputRequestTypeDef,
     GrantTypeDef,
     InitiateVaultLockInputRequestTypeDef,
-    ListJobsInputListJobsPaginateTypeDef,
-    ListMultipartUploadsInputListMultipartUploadsPaginateTypeDef,
-    ListPartsInputListPartsPaginateTypeDef,
-    ListVaultsInputListVaultsPaginateTypeDef,
     ListMultipartUploadsOutputTypeDef,
     ListPartsOutputTypeDef,
     ListProvisionedCapacityOutputTypeDef,
     SelectParametersResponseMetadataTypeDef,
     SelectParametersTypeDef,
     GetDataRetrievalPolicyOutputTypeDef,
     SetDataRetrievalPolicyInputRequestTypeDef,
@@ -562,43 +552,43 @@
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

### Comparing `types-aiobotocore-glacier-2.5.0.post1/README.md` & `types-aiobotocore-glacier-2.5.1/README.md`

 * *Files 4% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-glacier"></a>
 
 # types-aiobotocore-glacier
 
 [![PyPI - types-aiobotocore-glacier](https://img.shields.io/pypi/v/types-aiobotocore-glacier.svg?color=blue)](https://pypi.org/project/types-aiobotocore-glacier)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-glacier.svg?color=blue)](https://pypi.org/project/types-aiobotocore-glacier)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glacier/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-glacier?color=blue)](https://pypistats.org/packages/types-aiobotocore-glacier)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Glacier 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glacier.html#Glacier)
+[aiobotocore.Glacier 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glacier.html#Glacier)
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
 [types-aiobotocore-glacier docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glacier/).
 
 See how it helps to find and fix potential bugs:
 
@@ -409,105 +409,95 @@
 `types_aiobotocore_glacier.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_glacier.type_defs import (
     AbortMultipartUploadInputRequestTypeDef,
     AbortVaultLockInputRequestTypeDef,
-    AccountVaultRequestTypeDef,
     AddTagsToVaultInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    ArchiveCreationOutputTypeDef,
     CSVInputTypeDef,
     CSVOutputTypeDef,
     CompleteMultipartUploadInputMultipartUploadCompleteTypeDef,
     CompleteMultipartUploadInputRequestTypeDef,
     CompleteVaultLockInputRequestTypeDef,
     CreateVaultInputAccountCreateVaultTypeDef,
     CreateVaultInputRequestTypeDef,
     CreateVaultInputServiceResourceCreateVaultTypeDef,
+    CreateVaultOutputTypeDef,
     DataRetrievalRuleTypeDef,
     DeleteArchiveInputRequestTypeDef,
     DeleteVaultAccessPolicyInputRequestTypeDef,
     DeleteVaultInputRequestTypeDef,
     DeleteVaultNotificationsInputRequestTypeDef,
     DescribeJobInputRequestTypeDef,
     DescribeVaultInputRequestTypeDef,
     WaiterConfigTypeDef,
+    DescribeVaultOutputResponseMetadataTypeDef,
     DescribeVaultOutputTypeDef,
+    EmptyResponseMetadataTypeDef,
     EncryptionTypeDef,
     GetDataRetrievalPolicyInputRequestTypeDef,
     GetJobOutputInputJobGetOutputTypeDef,
     GetJobOutputInputRequestTypeDef,
+    GetJobOutputOutputTypeDef,
     GetVaultAccessPolicyInputRequestTypeDef,
     VaultAccessPolicyTypeDef,
     GetVaultLockInputRequestTypeDef,
+    GetVaultLockOutputTypeDef,
     GetVaultNotificationsInputRequestTypeDef,
     VaultNotificationConfigTypeDef,
     InventoryRetrievalJobDescriptionTypeDef,
     GranteeTypeDef,
+    InitiateJobOutputTypeDef,
     InitiateMultipartUploadInputRequestTypeDef,
     InitiateMultipartUploadInputVaultInitiateMultipartUploadTypeDef,
+    InitiateMultipartUploadOutputTypeDef,
     VaultLockPolicyTypeDef,
+    InitiateVaultLockOutputTypeDef,
+    InventoryRetrievalJobDescriptionResponseMetadataTypeDef,
     InventoryRetrievalJobInputTypeDef,
-    PaginatorConfigTypeDef,
+    ListJobsInputListJobsPaginateTypeDef,
     ListJobsInputRequestTypeDef,
+    ListMultipartUploadsInputListMultipartUploadsPaginateTypeDef,
     ListMultipartUploadsInputRequestTypeDef,
     UploadListElementTypeDef,
+    ListPartsInputListPartsPaginateTypeDef,
     ListPartsInputMultipartUploadPartsTypeDef,
     ListPartsInputRequestTypeDef,
     PartListElementTypeDef,
     ListProvisionedCapacityInputRequestTypeDef,
     ProvisionedCapacityDescriptionTypeDef,
     ListTagsForVaultInputRequestTypeDef,
+    ListTagsForVaultOutputTypeDef,
+    ListVaultsInputListVaultsPaginateTypeDef,
     ListVaultsInputRequestTypeDef,
+    PaginatorConfigTypeDef,
     PurchaseProvisionedCapacityInputRequestTypeDef,
+    PurchaseProvisionedCapacityOutputTypeDef,
     RemoveTagsFromVaultInputRequestTypeDef,
-    ServiceResourceAccountRequestTypeDef,
-    ServiceResourceArchiveRequestTypeDef,
-    ServiceResourceJobRequestTypeDef,
-    ServiceResourceMultipartUploadRequestTypeDef,
-    ServiceResourceNotificationRequestTypeDef,
-    ServiceResourceVaultRequestTypeDef,
+    ResponseMetadataTypeDef,
     UploadArchiveInputRequestTypeDef,
     UploadArchiveInputVaultUploadArchiveTypeDef,
     UploadMultipartPartInputMultipartUploadUploadPartTypeDef,
     UploadMultipartPartInputRequestTypeDef,
-    VaultArchiveRequestTypeDef,
-    VaultJobRequestTypeDef,
-    VaultMultipartUploadRequestTypeDef,
-    ArchiveCreationOutputTypeDef,
-    CreateVaultOutputTypeDef,
-    DescribeVaultOutputResponseMetadataTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetJobOutputOutputTypeDef,
-    GetVaultLockOutputTypeDef,
-    InitiateJobOutputTypeDef,
-    InitiateMultipartUploadOutputTypeDef,
-    InitiateVaultLockOutputTypeDef,
-    InventoryRetrievalJobDescriptionResponseMetadataTypeDef,
-    ListTagsForVaultOutputTypeDef,
-    PurchaseProvisionedCapacityOutputTypeDef,
     UploadMultipartPartOutputTypeDef,
     InputSerializationTypeDef,
     OutputSerializationTypeDef,
     DataRetrievalPolicyTypeDef,
     DescribeVaultInputVaultExistsWaitTypeDef,
     DescribeVaultInputVaultNotExistsWaitTypeDef,
     ListVaultsOutputTypeDef,
     GetVaultAccessPolicyOutputTypeDef,
     SetVaultAccessPolicyInputRequestTypeDef,
     GetVaultNotificationsOutputTypeDef,
     SetVaultNotificationsInputNotificationSetTypeDef,
     SetVaultNotificationsInputRequestTypeDef,
     GrantTypeDef,
     InitiateVaultLockInputRequestTypeDef,
-    ListJobsInputListJobsPaginateTypeDef,
-    ListMultipartUploadsInputListMultipartUploadsPaginateTypeDef,
-    ListPartsInputListPartsPaginateTypeDef,
-    ListVaultsInputListVaultsPaginateTypeDef,
     ListMultipartUploadsOutputTypeDef,
     ListPartsOutputTypeDef,
     ListProvisionedCapacityOutputTypeDef,
     SelectParametersResponseMetadataTypeDef,
     SelectParametersTypeDef,
     GetDataRetrievalPolicyOutputTypeDef,
     SetDataRetrievalPolicyInputRequestTypeDef,
@@ -529,43 +519,43 @@
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

### Comparing `types-aiobotocore-glacier-2.5.0.post1/setup.py` & `types-aiobotocore-glacier-2.5.1/setup.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-glacier.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-glacier",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_glacier"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Glacier 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.Glacier 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glacier/"
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

### Comparing `types-aiobotocore-glacier-2.5.0.post1/types_aiobotocore_glacier/__init__.py` & `types-aiobotocore-glacier-2.5.1/types_aiobotocore_glacier/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-glacier-2.5.0.post1/types_aiobotocore_glacier/__init__.pyi` & `types-aiobotocore-glacier-2.5.1/types_aiobotocore_glacier/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-glacier-2.5.0.post1/types_aiobotocore_glacier/__main__.py` & `types-aiobotocore-glacier-2.5.1/types_aiobotocore_glacier/__main__.py`

 * *Files 16% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Glacier 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Glacier 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glacier//\nBoto3 docs:"
         "     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glacier.html#Glacier\nOther"
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

### Comparing `types-aiobotocore-glacier-2.5.0.post1/types_aiobotocore_glacier/client.py` & `types-aiobotocore-glacier-2.5.1/types_aiobotocore_glacier/client.py`

 * *Files 1% similar despite different names*

```diff
@@ -304,15 +304,16 @@
         """
 
     async def get_vault_lock(
         self, *, vaultName: str, accountId: str = "-"
     ) -> GetVaultLockOutputTypeDef:
         """
         This operation retrieves the following attributes from the `lock-policy`
-        subresource set on the specified vault * The vault lock policy set on the vault.
+        subresource set on the specified vault: * The vault lock policy set on the
+        vault.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glacier.html#Glacier.Client.get_vault_lock)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glacier/client/#get_vault_lock)
         """
 
     async def get_vault_notifications(
         self, *, vaultName: str, accountId: str = "-"
@@ -351,15 +352,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glacier/client/#initiate_multipart_upload)
         """
 
     async def initiate_vault_lock(
         self, *, vaultName: str, accountId: str = "-", policy: VaultLockPolicyTypeDef = ...
     ) -> InitiateVaultLockOutputTypeDef:
         """
-        This operation initiates the vault locking process by doing the following *
+        This operation initiates the vault locking process by doing the following: *
         Installing a vault lock policy on the specified vault.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glacier.html#Glacier.Client.initiate_vault_lock)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glacier/client/#initiate_vault_lock)
         """
 
     async def list_jobs(
```

### Comparing `types-aiobotocore-glacier-2.5.0.post1/types_aiobotocore_glacier/client.pyi` & `types-aiobotocore-glacier-2.5.1/types_aiobotocore_glacier/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -281,15 +281,16 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glacier/client/#get_vault_access_policy)
         """
     async def get_vault_lock(
         self, *, vaultName: str, accountId: str = "-"
     ) -> GetVaultLockOutputTypeDef:
         """
         This operation retrieves the following attributes from the `lock-policy`
-        subresource set on the specified vault * The vault lock policy set on the vault.
+        subresource set on the specified vault: * The vault lock policy set on the
+        vault.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glacier.html#Glacier.Client.get_vault_lock)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glacier/client/#get_vault_lock)
         """
     async def get_vault_notifications(
         self, *, vaultName: str, accountId: str = "-"
     ) -> GetVaultNotificationsOutputTypeDef:
@@ -324,15 +325,15 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glacier.html#Glacier.Client.initiate_multipart_upload)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glacier/client/#initiate_multipart_upload)
         """
     async def initiate_vault_lock(
         self, *, vaultName: str, accountId: str = "-", policy: VaultLockPolicyTypeDef = ...
     ) -> InitiateVaultLockOutputTypeDef:
         """
-        This operation initiates the vault locking process by doing the following *
+        This operation initiates the vault locking process by doing the following: *
         Installing a vault lock policy on the specified vault.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glacier.html#Glacier.Client.initiate_vault_lock)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glacier/client/#initiate_vault_lock)
         """
     async def list_jobs(
         self,
```

### Comparing `types-aiobotocore-glacier-2.5.0.post1/types_aiobotocore_glacier/literals.py` & `types-aiobotocore-glacier-2.5.1/types_aiobotocore_glacier/literals.py`

 * *Files 0% similar despite different names*

```diff
@@ -128,14 +128,15 @@
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
@@ -214,14 +215,15 @@
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
@@ -232,14 +234,15 @@
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
@@ -275,14 +278,15 @@
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
@@ -301,16 +305,19 @@
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
@@ -394,15 +401,17 @@
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

### Comparing `types-aiobotocore-glacier-2.5.0.post1/types_aiobotocore_glacier/literals.pyi` & `types-aiobotocore-glacier-2.5.1/types_aiobotocore_glacier/literals.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -126,14 +126,15 @@
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
@@ -212,14 +213,15 @@
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
@@ -230,14 +232,15 @@
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
@@ -273,14 +276,15 @@
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
@@ -299,16 +303,19 @@
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
@@ -392,15 +399,17 @@
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

### Comparing `types-aiobotocore-glacier-2.5.0.post1/types_aiobotocore_glacier/paginator.py` & `types-aiobotocore-glacier-2.5.1/types_aiobotocore_glacier/paginator.py`

 * *Files 5% similar despite different names*

```diff
@@ -22,34 +22,27 @@
 
         list_jobs_paginator: ListJobsPaginator = client.get_paginator("list_jobs")
         list_multipart_uploads_paginator: ListMultipartUploadsPaginator = client.get_paginator("list_multipart_uploads")
         list_parts_paginator: ListPartsPaginator = client.get_paginator("list_parts")
         list_vaults_paginator: ListVaultsPaginator = client.get_paginator("list_vaults")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListJobsOutputTypeDef,
     ListMultipartUploadsOutputTypeDef,
     ListPartsOutputTypeDef,
     ListVaultsOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListJobsPaginator",
     "ListMultipartUploadsPaginator",
     "ListPartsPaginator",
     "ListVaultsPaginator",
 )
 
@@ -73,30 +66,30 @@
     def paginate(
         self,
         *,
         accountId: str,
         vaultName: str,
         statuscode: str = ...,
         completed: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListJobsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glacier.html#Glacier.Paginator.ListJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glacier/paginators/#listjobspaginator)
         """
 
 
 class ListMultipartUploadsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glacier.html#Glacier.Paginator.ListMultipartUploads)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glacier/paginators/#listmultipartuploadspaginator)
     """
 
     def paginate(
-        self, *, accountId: str, vaultName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, accountId: str, vaultName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMultipartUploadsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glacier.html#Glacier.Paginator.ListMultipartUploads.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glacier/paginators/#listmultipartuploadspaginator)
         """
 
 
@@ -108,28 +101,28 @@
 
     def paginate(
         self,
         *,
         accountId: str,
         vaultName: str,
         uploadId: str,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPartsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glacier.html#Glacier.Paginator.ListParts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glacier/paginators/#listpartspaginator)
         """
 
 
 class ListVaultsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glacier.html#Glacier.Paginator.ListVaults)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glacier/paginators/#listvaultspaginator)
     """
 
     def paginate(
-        self, *, accountId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, accountId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListVaultsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glacier.html#Glacier.Paginator.ListVaults.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glacier/paginators/#listvaultspaginator)
         """
```

### Comparing `types-aiobotocore-glacier-2.5.0.post1/types_aiobotocore_glacier/paginator.pyi` & `types-aiobotocore-glacier-2.5.1/types_aiobotocore_glacier/paginator.pyi`

 * *Files 8% similar despite different names*

```diff
@@ -22,33 +22,27 @@
 
         list_jobs_paginator: ListJobsPaginator = client.get_paginator("list_jobs")
         list_multipart_uploads_paginator: ListMultipartUploadsPaginator = client.get_paginator("list_multipart_uploads")
         list_parts_paginator: ListPartsPaginator = client.get_paginator("list_parts")
         list_vaults_paginator: ListVaultsPaginator = client.get_paginator("list_vaults")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListJobsOutputTypeDef,
     ListMultipartUploadsOutputTypeDef,
     ListPartsOutputTypeDef,
     ListVaultsOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListJobsPaginator",
     "ListMultipartUploadsPaginator",
     "ListPartsPaginator",
     "ListVaultsPaginator",
 )
 
@@ -69,29 +63,29 @@
     def paginate(
         self,
         *,
         accountId: str,
         vaultName: str,
         statuscode: str = ...,
         completed: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListJobsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glacier.html#Glacier.Paginator.ListJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glacier/paginators/#listjobspaginator)
         """
 
 class ListMultipartUploadsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glacier.html#Glacier.Paginator.ListMultipartUploads)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glacier/paginators/#listmultipartuploadspaginator)
     """
 
     def paginate(
-        self, *, accountId: str, vaultName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, accountId: str, vaultName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMultipartUploadsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glacier.html#Glacier.Paginator.ListMultipartUploads.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glacier/paginators/#listmultipartuploadspaginator)
         """
 
 class ListPartsPaginator(AioPaginator):
@@ -102,27 +96,27 @@
 
     def paginate(
         self,
         *,
         accountId: str,
         vaultName: str,
         uploadId: str,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPartsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glacier.html#Glacier.Paginator.ListParts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glacier/paginators/#listpartspaginator)
         """
 
 class ListVaultsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glacier.html#Glacier.Paginator.ListVaults)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glacier/paginators/#listvaultspaginator)
     """
 
     def paginate(
-        self, *, accountId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, accountId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListVaultsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glacier.html#Glacier.Paginator.ListVaults.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glacier/paginators/#listvaultspaginator)
         """
```

### Comparing `types-aiobotocore-glacier-2.5.0.post1/types_aiobotocore_glacier/service_resource.py` & `types-aiobotocore-glacier-2.5.1/types_aiobotocore_glacier/service_resource.py`

 * *Files 0% similar despite different names*

```diff
@@ -19,16 +19,15 @@
         my_archive: glacier_resources.Archive = resource.Archive(...)
         my_job: glacier_resources.Job = resource.Job(...)
         my_multipart_upload: glacier_resources.MultipartUpload = resource.MultipartUpload(...)
         my_notification: glacier_resources.Notification = resource.Notification(...)
         my_vault: glacier_resources.Vault = resource.Vault(...)
 ```
 """
-import sys
-from typing import IO, Any, Awaitable, List, NoReturn, Sequence, Union
+from typing import IO, Any, AsyncIterator, Awaitable, List, NoReturn, Sequence, Union
 
 from aiobotocore.response import StreamingBody
 
 from .client import GlacierClient
 from .literals import ActionCodeType, StatusCodeType
 from .type_defs import (
     ArchiveCreationOutputTypeDef,
@@ -46,18 +45,14 @@
     from aioboto3.resources.base import AIOBoto3ServiceResource
 except (ModuleNotFoundError, ImportError):
     from builtins import object as AIOBoto3ServiceResource
 try:
     from aioboto3.resources.collection import AIOResourceCollection
 except (ModuleNotFoundError, ImportError):
     from builtins import object as AIOResourceCollection
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
 try:
     from boto3.resources.base import ResourceMeta
 except (ModuleNotFoundError, ImportError):
     from builtins import object as ResourceMeta
 
 
 __all__ = (
```

### Comparing `types-aiobotocore-glacier-2.5.0.post1/types_aiobotocore_glacier/service_resource.pyi` & `types-aiobotocore-glacier-2.5.1/types_aiobotocore_glacier/service_resource.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -19,16 +19,15 @@
         my_archive: glacier_resources.Archive = resource.Archive(...)
         my_job: glacier_resources.Job = resource.Job(...)
         my_multipart_upload: glacier_resources.MultipartUpload = resource.MultipartUpload(...)
         my_notification: glacier_resources.Notification = resource.Notification(...)
         my_vault: glacier_resources.Vault = resource.Vault(...)
 ```
 """
-import sys
-from typing import IO, Any, Awaitable, List, NoReturn, Sequence, Union
+from typing import IO, Any, AsyncIterator, Awaitable, List, NoReturn, Sequence, Union
 
 from aiobotocore.response import StreamingBody
 
 from .client import GlacierClient
 from .literals import ActionCodeType, StatusCodeType
 from .type_defs import (
     ArchiveCreationOutputTypeDef,
@@ -46,18 +45,14 @@
     from aioboto3.resources.base import AIOBoto3ServiceResource
 except (ModuleNotFoundError, ImportError):
     from builtins import object as AIOBoto3ServiceResource
 try:
     from aioboto3.resources.collection import AIOResourceCollection
 except (ModuleNotFoundError, ImportError):
     from builtins import object as AIOResourceCollection
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
 try:
     from boto3.resources.base import ResourceMeta
 except (ModuleNotFoundError, ImportError):
     from builtins import object as ResourceMeta
 
 __all__ = (
     "GlacierServiceResource",
```

### Comparing `types-aiobotocore-glacier-2.5.0.post1/types_aiobotocore_glacier/type_defs.py` & `types-aiobotocore-glacier-2.5.1/types_aiobotocore_glacier/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -33,109 +33,98 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "AbortMultipartUploadInputRequestTypeDef",
     "AbortVaultLockInputRequestTypeDef",
-    "AccountVaultRequestTypeDef",
     "AddTagsToVaultInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "ArchiveCreationOutputTypeDef",
     "CSVInputTypeDef",
     "CSVOutputTypeDef",
     "CompleteMultipartUploadInputMultipartUploadCompleteTypeDef",
     "CompleteMultipartUploadInputRequestTypeDef",
     "CompleteVaultLockInputRequestTypeDef",
     "CreateVaultInputAccountCreateVaultTypeDef",
     "CreateVaultInputRequestTypeDef",
     "CreateVaultInputServiceResourceCreateVaultTypeDef",
+    "CreateVaultOutputTypeDef",
     "DataRetrievalRuleTypeDef",
     "DeleteArchiveInputRequestTypeDef",
     "DeleteVaultAccessPolicyInputRequestTypeDef",
     "DeleteVaultInputRequestTypeDef",
     "DeleteVaultNotificationsInputRequestTypeDef",
     "DescribeJobInputRequestTypeDef",
     "DescribeVaultInputRequestTypeDef",
     "WaiterConfigTypeDef",
+    "DescribeVaultOutputResponseMetadataTypeDef",
     "DescribeVaultOutputTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EncryptionTypeDef",
     "GetDataRetrievalPolicyInputRequestTypeDef",
     "GetJobOutputInputJobGetOutputTypeDef",
     "GetJobOutputInputRequestTypeDef",
+    "GetJobOutputOutputTypeDef",
     "GetVaultAccessPolicyInputRequestTypeDef",
     "VaultAccessPolicyTypeDef",
     "GetVaultLockInputRequestTypeDef",
+    "GetVaultLockOutputTypeDef",
     "GetVaultNotificationsInputRequestTypeDef",
     "VaultNotificationConfigTypeDef",
     "InventoryRetrievalJobDescriptionTypeDef",
     "GranteeTypeDef",
+    "InitiateJobOutputTypeDef",
     "InitiateMultipartUploadInputRequestTypeDef",
     "InitiateMultipartUploadInputVaultInitiateMultipartUploadTypeDef",
+    "InitiateMultipartUploadOutputTypeDef",
     "VaultLockPolicyTypeDef",
+    "InitiateVaultLockOutputTypeDef",
+    "InventoryRetrievalJobDescriptionResponseMetadataTypeDef",
     "InventoryRetrievalJobInputTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListJobsInputListJobsPaginateTypeDef",
     "ListJobsInputRequestTypeDef",
+    "ListMultipartUploadsInputListMultipartUploadsPaginateTypeDef",
     "ListMultipartUploadsInputRequestTypeDef",
     "UploadListElementTypeDef",
+    "ListPartsInputListPartsPaginateTypeDef",
     "ListPartsInputMultipartUploadPartsTypeDef",
     "ListPartsInputRequestTypeDef",
     "PartListElementTypeDef",
     "ListProvisionedCapacityInputRequestTypeDef",
     "ProvisionedCapacityDescriptionTypeDef",
     "ListTagsForVaultInputRequestTypeDef",
+    "ListTagsForVaultOutputTypeDef",
+    "ListVaultsInputListVaultsPaginateTypeDef",
     "ListVaultsInputRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "PurchaseProvisionedCapacityInputRequestTypeDef",
+    "PurchaseProvisionedCapacityOutputTypeDef",
     "RemoveTagsFromVaultInputRequestTypeDef",
-    "ServiceResourceAccountRequestTypeDef",
-    "ServiceResourceArchiveRequestTypeDef",
-    "ServiceResourceJobRequestTypeDef",
-    "ServiceResourceMultipartUploadRequestTypeDef",
-    "ServiceResourceNotificationRequestTypeDef",
-    "ServiceResourceVaultRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "UploadArchiveInputRequestTypeDef",
     "UploadArchiveInputVaultUploadArchiveTypeDef",
     "UploadMultipartPartInputMultipartUploadUploadPartTypeDef",
     "UploadMultipartPartInputRequestTypeDef",
-    "VaultArchiveRequestTypeDef",
-    "VaultJobRequestTypeDef",
-    "VaultMultipartUploadRequestTypeDef",
-    "ArchiveCreationOutputTypeDef",
-    "CreateVaultOutputTypeDef",
-    "DescribeVaultOutputResponseMetadataTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetJobOutputOutputTypeDef",
-    "GetVaultLockOutputTypeDef",
-    "InitiateJobOutputTypeDef",
-    "InitiateMultipartUploadOutputTypeDef",
-    "InitiateVaultLockOutputTypeDef",
-    "InventoryRetrievalJobDescriptionResponseMetadataTypeDef",
-    "ListTagsForVaultOutputTypeDef",
-    "PurchaseProvisionedCapacityOutputTypeDef",
     "UploadMultipartPartOutputTypeDef",
     "InputSerializationTypeDef",
     "OutputSerializationTypeDef",
     "DataRetrievalPolicyTypeDef",
     "DescribeVaultInputVaultExistsWaitTypeDef",
     "DescribeVaultInputVaultNotExistsWaitTypeDef",
     "ListVaultsOutputTypeDef",
     "GetVaultAccessPolicyOutputTypeDef",
     "SetVaultAccessPolicyInputRequestTypeDef",
     "GetVaultNotificationsOutputTypeDef",
     "SetVaultNotificationsInputNotificationSetTypeDef",
     "SetVaultNotificationsInputRequestTypeDef",
     "GrantTypeDef",
     "InitiateVaultLockInputRequestTypeDef",
-    "ListJobsInputListJobsPaginateTypeDef",
-    "ListMultipartUploadsInputListMultipartUploadsPaginateTypeDef",
-    "ListPartsInputListPartsPaginateTypeDef",
-    "ListVaultsInputListVaultsPaginateTypeDef",
     "ListMultipartUploadsOutputTypeDef",
     "ListPartsOutputTypeDef",
     "ListProvisionedCapacityOutputTypeDef",
     "SelectParametersResponseMetadataTypeDef",
     "SelectParametersTypeDef",
     "GetDataRetrievalPolicyOutputTypeDef",
     "SetDataRetrievalPolicyInputRequestTypeDef",
@@ -160,50 +149,39 @@
     "_OptionalAbortMultipartUploadInputRequestTypeDef",
     {
         "accountId": str,
     },
     total=False,
 )
 
-
 class AbortMultipartUploadInputRequestTypeDef(
     _RequiredAbortMultipartUploadInputRequestTypeDef,
     _OptionalAbortMultipartUploadInputRequestTypeDef,
 ):
     pass
 
-
 _RequiredAbortVaultLockInputRequestTypeDef = TypedDict(
     "_RequiredAbortVaultLockInputRequestTypeDef",
     {
         "vaultName": str,
     },
 )
 _OptionalAbortVaultLockInputRequestTypeDef = TypedDict(
     "_OptionalAbortVaultLockInputRequestTypeDef",
     {
         "accountId": str,
     },
     total=False,
 )
 
-
 class AbortVaultLockInputRequestTypeDef(
     _RequiredAbortVaultLockInputRequestTypeDef, _OptionalAbortVaultLockInputRequestTypeDef
 ):
     pass
 
-
-AccountVaultRequestTypeDef = TypedDict(
-    "AccountVaultRequestTypeDef",
-    {
-        "name": str,
-    },
-)
-
 _RequiredAddTagsToVaultInputRequestTypeDef = TypedDict(
     "_RequiredAddTagsToVaultInputRequestTypeDef",
     {
         "vaultName": str,
     },
 )
 _OptionalAddTagsToVaultInputRequestTypeDef = TypedDict(
@@ -211,29 +189,26 @@
     {
         "accountId": str,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
-
 class AddTagsToVaultInputRequestTypeDef(
     _RequiredAddTagsToVaultInputRequestTypeDef, _OptionalAddTagsToVaultInputRequestTypeDef
 ):
     pass
 
-
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+ArchiveCreationOutputTypeDef = TypedDict(
+    "ArchiveCreationOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "location": str,
+        "checksum": str,
+        "archiveId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CSVInputTypeDef = TypedDict(
     "CSVInputTypeDef",
     {
         "FileHeaderInfo": FileHeaderInfoType,
@@ -280,22 +255,20 @@
         "accountId": str,
         "archiveSize": str,
         "checksum": str,
     },
     total=False,
 )
 
-
 class CompleteMultipartUploadInputRequestTypeDef(
     _RequiredCompleteMultipartUploadInputRequestTypeDef,
     _OptionalCompleteMultipartUploadInputRequestTypeDef,
 ):
     pass
 
-
 _RequiredCompleteVaultLockInputRequestTypeDef = TypedDict(
     "_RequiredCompleteVaultLockInputRequestTypeDef",
     {
         "vaultName": str,
         "lockId": str,
     },
 )
@@ -303,21 +276,19 @@
     "_OptionalCompleteVaultLockInputRequestTypeDef",
     {
         "accountId": str,
     },
     total=False,
 )
 
-
 class CompleteVaultLockInputRequestTypeDef(
     _RequiredCompleteVaultLockInputRequestTypeDef, _OptionalCompleteVaultLockInputRequestTypeDef
 ):
     pass
 
-
 CreateVaultInputAccountCreateVaultTypeDef = TypedDict(
     "CreateVaultInputAccountCreateVaultTypeDef",
     {
         "vaultName": str,
     },
 )
 
@@ -331,42 +302,46 @@
     "_OptionalCreateVaultInputRequestTypeDef",
     {
         "accountId": str,
     },
     total=False,
 )
 
-
 class CreateVaultInputRequestTypeDef(
     _RequiredCreateVaultInputRequestTypeDef, _OptionalCreateVaultInputRequestTypeDef
 ):
     pass
 
-
 _RequiredCreateVaultInputServiceResourceCreateVaultTypeDef = TypedDict(
     "_RequiredCreateVaultInputServiceResourceCreateVaultTypeDef",
     {
         "vaultName": str,
     },
 )
 _OptionalCreateVaultInputServiceResourceCreateVaultTypeDef = TypedDict(
     "_OptionalCreateVaultInputServiceResourceCreateVaultTypeDef",
     {
         "accountId": str,
     },
     total=False,
 )
 
-
 class CreateVaultInputServiceResourceCreateVaultTypeDef(
     _RequiredCreateVaultInputServiceResourceCreateVaultTypeDef,
     _OptionalCreateVaultInputServiceResourceCreateVaultTypeDef,
 ):
     pass
 
+CreateVaultOutputTypeDef = TypedDict(
+    "CreateVaultOutputTypeDef",
+    {
+        "location": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 DataRetrievalRuleTypeDef = TypedDict(
     "DataRetrievalRuleTypeDef",
     {
         "Strategy": str,
         "BytesPerHour": int,
     },
@@ -384,86 +359,78 @@
     "_OptionalDeleteArchiveInputRequestTypeDef",
     {
         "accountId": str,
     },
     total=False,
 )
 
-
 class DeleteArchiveInputRequestTypeDef(
     _RequiredDeleteArchiveInputRequestTypeDef, _OptionalDeleteArchiveInputRequestTypeDef
 ):
     pass
 
-
 _RequiredDeleteVaultAccessPolicyInputRequestTypeDef = TypedDict(
     "_RequiredDeleteVaultAccessPolicyInputRequestTypeDef",
     {
         "vaultName": str,
     },
 )
 _OptionalDeleteVaultAccessPolicyInputRequestTypeDef = TypedDict(
     "_OptionalDeleteVaultAccessPolicyInputRequestTypeDef",
     {
         "accountId": str,
     },
     total=False,
 )
 
-
 class DeleteVaultAccessPolicyInputRequestTypeDef(
     _RequiredDeleteVaultAccessPolicyInputRequestTypeDef,
     _OptionalDeleteVaultAccessPolicyInputRequestTypeDef,
 ):
     pass
 
-
 _RequiredDeleteVaultInputRequestTypeDef = TypedDict(
     "_RequiredDeleteVaultInputRequestTypeDef",
     {
         "vaultName": str,
     },
 )
 _OptionalDeleteVaultInputRequestTypeDef = TypedDict(
     "_OptionalDeleteVaultInputRequestTypeDef",
     {
         "accountId": str,
     },
     total=False,
 )
 
-
 class DeleteVaultInputRequestTypeDef(
     _RequiredDeleteVaultInputRequestTypeDef, _OptionalDeleteVaultInputRequestTypeDef
 ):
     pass
 
-
 _RequiredDeleteVaultNotificationsInputRequestTypeDef = TypedDict(
     "_RequiredDeleteVaultNotificationsInputRequestTypeDef",
     {
         "vaultName": str,
     },
 )
 _OptionalDeleteVaultNotificationsInputRequestTypeDef = TypedDict(
     "_OptionalDeleteVaultNotificationsInputRequestTypeDef",
     {
         "accountId": str,
     },
     total=False,
 )
 
-
 class DeleteVaultNotificationsInputRequestTypeDef(
     _RequiredDeleteVaultNotificationsInputRequestTypeDef,
     _OptionalDeleteVaultNotificationsInputRequestTypeDef,
 ):
     pass
 
-
 _RequiredDescribeJobInputRequestTypeDef = TypedDict(
     "_RequiredDescribeJobInputRequestTypeDef",
     {
         "vaultName": str,
         "jobId": str,
     },
 )
@@ -471,64 +438,80 @@
     "_OptionalDescribeJobInputRequestTypeDef",
     {
         "accountId": str,
     },
     total=False,
 )
 
-
 class DescribeJobInputRequestTypeDef(
     _RequiredDescribeJobInputRequestTypeDef, _OptionalDescribeJobInputRequestTypeDef
 ):
     pass
 
-
 _RequiredDescribeVaultInputRequestTypeDef = TypedDict(
     "_RequiredDescribeVaultInputRequestTypeDef",
     {
         "vaultName": str,
     },
 )
 _OptionalDescribeVaultInputRequestTypeDef = TypedDict(
     "_OptionalDescribeVaultInputRequestTypeDef",
     {
         "accountId": str,
     },
     total=False,
 )
 
-
 class DescribeVaultInputRequestTypeDef(
     _RequiredDescribeVaultInputRequestTypeDef, _OptionalDescribeVaultInputRequestTypeDef
 ):
     pass
 
-
 WaiterConfigTypeDef = TypedDict(
     "WaiterConfigTypeDef",
     {
         "Delay": int,
         "MaxAttempts": int,
     },
     total=False,
 )
 
+DescribeVaultOutputResponseMetadataTypeDef = TypedDict(
+    "DescribeVaultOutputResponseMetadataTypeDef",
+    {
+        "VaultARN": str,
+        "VaultName": str,
+        "CreationDate": str,
+        "LastInventoryDate": str,
+        "NumberOfArchives": int,
+        "SizeInBytes": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeVaultOutputTypeDef = TypedDict(
     "DescribeVaultOutputTypeDef",
     {
         "VaultARN": str,
         "VaultName": str,
         "CreationDate": str,
         "LastInventoryDate": str,
         "NumberOfArchives": int,
         "SizeInBytes": int,
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
 EncryptionTypeDef = TypedDict(
     "EncryptionTypeDef",
     {
         "EncryptionType": EncryptionTypeType,
         "KMSKeyId": str,
         "KMSContext": str,
     },
@@ -563,20 +546,32 @@
     {
         "accountId": str,
         "range": str,
     },
     total=False,
 )
 
-
 class GetJobOutputInputRequestTypeDef(
     _RequiredGetJobOutputInputRequestTypeDef, _OptionalGetJobOutputInputRequestTypeDef
 ):
     pass
 
+GetJobOutputOutputTypeDef = TypedDict(
+    "GetJobOutputOutputTypeDef",
+    {
+        "body": StreamingBody,
+        "checksum": str,
+        "status": int,
+        "contentRange": str,
+        "acceptRanges": str,
+        "contentType": str,
+        "archiveDescription": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredGetVaultAccessPolicyInputRequestTypeDef = TypedDict(
     "_RequiredGetVaultAccessPolicyInputRequestTypeDef",
     {
         "vaultName": str,
     },
 )
@@ -584,22 +579,20 @@
     "_OptionalGetVaultAccessPolicyInputRequestTypeDef",
     {
         "accountId": str,
     },
     total=False,
 )
 
-
 class GetVaultAccessPolicyInputRequestTypeDef(
     _RequiredGetVaultAccessPolicyInputRequestTypeDef,
     _OptionalGetVaultAccessPolicyInputRequestTypeDef,
 ):
     pass
 
-
 VaultAccessPolicyTypeDef = TypedDict(
     "VaultAccessPolicyTypeDef",
     {
         "Policy": str,
     },
     total=False,
 )
@@ -614,20 +607,29 @@
     "_OptionalGetVaultLockInputRequestTypeDef",
     {
         "accountId": str,
     },
     total=False,
 )
 
-
 class GetVaultLockInputRequestTypeDef(
     _RequiredGetVaultLockInputRequestTypeDef, _OptionalGetVaultLockInputRequestTypeDef
 ):
     pass
 
+GetVaultLockOutputTypeDef = TypedDict(
+    "GetVaultLockOutputTypeDef",
+    {
+        "Policy": str,
+        "State": str,
+        "ExpirationDate": str,
+        "CreationDate": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredGetVaultNotificationsInputRequestTypeDef = TypedDict(
     "_RequiredGetVaultNotificationsInputRequestTypeDef",
     {
         "vaultName": str,
     },
 )
@@ -635,22 +637,20 @@
     "_OptionalGetVaultNotificationsInputRequestTypeDef",
     {
         "accountId": str,
     },
     total=False,
 )
 
-
 class GetVaultNotificationsInputRequestTypeDef(
     _RequiredGetVaultNotificationsInputRequestTypeDef,
     _OptionalGetVaultNotificationsInputRequestTypeDef,
 ):
     pass
 
-
 VaultNotificationConfigTypeDef = TypedDict(
     "VaultNotificationConfigTypeDef",
     {
         "SNSTopic": str,
         "Events": List[str],
     },
     total=False,
@@ -681,18 +681,26 @@
         "URI": str,
         "ID": str,
         "EmailAddress": str,
     },
     total=False,
 )
 
-
 class GranteeTypeDef(_RequiredGranteeTypeDef, _OptionalGranteeTypeDef):
     pass
 
+InitiateJobOutputTypeDef = TypedDict(
+    "InitiateJobOutputTypeDef",
+    {
+        "location": str,
+        "jobId": str,
+        "jobOutputPath": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredInitiateMultipartUploadInputRequestTypeDef = TypedDict(
     "_RequiredInitiateMultipartUploadInputRequestTypeDef",
     {
         "vaultName": str,
     },
 )
@@ -702,60 +710,99 @@
         "accountId": str,
         "archiveDescription": str,
         "partSize": str,
     },
     total=False,
 )
 
-
 class InitiateMultipartUploadInputRequestTypeDef(
     _RequiredInitiateMultipartUploadInputRequestTypeDef,
     _OptionalInitiateMultipartUploadInputRequestTypeDef,
 ):
     pass
 
-
 InitiateMultipartUploadInputVaultInitiateMultipartUploadTypeDef = TypedDict(
     "InitiateMultipartUploadInputVaultInitiateMultipartUploadTypeDef",
     {
         "archiveDescription": str,
         "partSize": str,
     },
     total=False,
 )
 
+InitiateMultipartUploadOutputTypeDef = TypedDict(
+    "InitiateMultipartUploadOutputTypeDef",
+    {
+        "location": str,
+        "uploadId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 VaultLockPolicyTypeDef = TypedDict(
     "VaultLockPolicyTypeDef",
     {
         "Policy": str,
     },
     total=False,
 )
 
+InitiateVaultLockOutputTypeDef = TypedDict(
+    "InitiateVaultLockOutputTypeDef",
+    {
+        "lockId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+InventoryRetrievalJobDescriptionResponseMetadataTypeDef = TypedDict(
+    "InventoryRetrievalJobDescriptionResponseMetadataTypeDef",
+    {
+        "Format": str,
+        "StartDate": str,
+        "EndDate": str,
+        "Limit": str,
+        "Marker": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 InventoryRetrievalJobInputTypeDef = TypedDict(
     "InventoryRetrievalJobInputTypeDef",
     {
         "StartDate": str,
         "EndDate": str,
         "Limit": str,
         "Marker": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListJobsInputListJobsPaginateTypeDef = TypedDict(
+    "_RequiredListJobsInputListJobsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "accountId": str,
+        "vaultName": str,
+    },
+)
+_OptionalListJobsInputListJobsPaginateTypeDef = TypedDict(
+    "_OptionalListJobsInputListJobsPaginateTypeDef",
+    {
+        "statuscode": str,
+        "completed": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListJobsInputListJobsPaginateTypeDef(
+    _RequiredListJobsInputListJobsPaginateTypeDef, _OptionalListJobsInputListJobsPaginateTypeDef
+):
+    pass
+
 _RequiredListJobsInputRequestTypeDef = TypedDict(
     "_RequiredListJobsInputRequestTypeDef",
     {
         "vaultName": str,
     },
 )
 _OptionalListJobsInputRequestTypeDef = TypedDict(
@@ -766,20 +813,39 @@
         "marker": str,
         "statuscode": str,
         "completed": str,
     },
     total=False,
 )
 
-
 class ListJobsInputRequestTypeDef(
     _RequiredListJobsInputRequestTypeDef, _OptionalListJobsInputRequestTypeDef
 ):
     pass
 
+_RequiredListMultipartUploadsInputListMultipartUploadsPaginateTypeDef = TypedDict(
+    "_RequiredListMultipartUploadsInputListMultipartUploadsPaginateTypeDef",
+    {
+        "accountId": str,
+        "vaultName": str,
+    },
+)
+_OptionalListMultipartUploadsInputListMultipartUploadsPaginateTypeDef = TypedDict(
+    "_OptionalListMultipartUploadsInputListMultipartUploadsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListMultipartUploadsInputListMultipartUploadsPaginateTypeDef(
+    _RequiredListMultipartUploadsInputListMultipartUploadsPaginateTypeDef,
+    _OptionalListMultipartUploadsInputListMultipartUploadsPaginateTypeDef,
+):
+    pass
 
 _RequiredListMultipartUploadsInputRequestTypeDef = TypedDict(
     "_RequiredListMultipartUploadsInputRequestTypeDef",
     {
         "vaultName": str,
     },
 )
@@ -789,34 +855,53 @@
         "accountId": str,
         "marker": str,
         "limit": str,
     },
     total=False,
 )
 
-
 class ListMultipartUploadsInputRequestTypeDef(
     _RequiredListMultipartUploadsInputRequestTypeDef,
     _OptionalListMultipartUploadsInputRequestTypeDef,
 ):
     pass
 
-
 UploadListElementTypeDef = TypedDict(
     "UploadListElementTypeDef",
     {
         "MultipartUploadId": str,
         "VaultARN": str,
         "ArchiveDescription": str,
         "PartSizeInBytes": int,
         "CreationDate": str,
     },
     total=False,
 )
 
+_RequiredListPartsInputListPartsPaginateTypeDef = TypedDict(
+    "_RequiredListPartsInputListPartsPaginateTypeDef",
+    {
+        "accountId": str,
+        "vaultName": str,
+        "uploadId": str,
+    },
+)
+_OptionalListPartsInputListPartsPaginateTypeDef = TypedDict(
+    "_OptionalListPartsInputListPartsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListPartsInputListPartsPaginateTypeDef(
+    _RequiredListPartsInputListPartsPaginateTypeDef, _OptionalListPartsInputListPartsPaginateTypeDef
+):
+    pass
+
 ListPartsInputMultipartUploadPartsTypeDef = TypedDict(
     "ListPartsInputMultipartUploadPartsTypeDef",
     {
         "marker": str,
         "limit": str,
     },
     total=False,
@@ -835,21 +920,19 @@
         "accountId": str,
         "marker": str,
         "limit": str,
     },
     total=False,
 )
 
-
 class ListPartsInputRequestTypeDef(
     _RequiredListPartsInputRequestTypeDef, _OptionalListPartsInputRequestTypeDef
 ):
     pass
 
-
 PartListElementTypeDef = TypedDict(
     "PartListElementTypeDef",
     {
         "RangeInBytes": str,
         "SHA256TreeHash": str,
     },
     total=False,
@@ -883,39 +966,83 @@
     "_OptionalListTagsForVaultInputRequestTypeDef",
     {
         "accountId": str,
     },
     total=False,
 )
 
-
 class ListTagsForVaultInputRequestTypeDef(
     _RequiredListTagsForVaultInputRequestTypeDef, _OptionalListTagsForVaultInputRequestTypeDef
 ):
     pass
 
+ListTagsForVaultOutputTypeDef = TypedDict(
+    "ListTagsForVaultOutputTypeDef",
+    {
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListVaultsInputListVaultsPaginateTypeDef = TypedDict(
+    "_RequiredListVaultsInputListVaultsPaginateTypeDef",
+    {
+        "accountId": str,
+    },
+)
+_OptionalListVaultsInputListVaultsPaginateTypeDef = TypedDict(
+    "_OptionalListVaultsInputListVaultsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListVaultsInputListVaultsPaginateTypeDef(
+    _RequiredListVaultsInputListVaultsPaginateTypeDef,
+    _OptionalListVaultsInputListVaultsPaginateTypeDef,
+):
+    pass
 
 ListVaultsInputRequestTypeDef = TypedDict(
     "ListVaultsInputRequestTypeDef",
     {
         "accountId": str,
         "marker": str,
         "limit": str,
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
 PurchaseProvisionedCapacityInputRequestTypeDef = TypedDict(
     "PurchaseProvisionedCapacityInputRequestTypeDef",
     {
         "accountId": str,
     },
     total=False,
 )
 
+PurchaseProvisionedCapacityOutputTypeDef = TypedDict(
+    "PurchaseProvisionedCapacityOutputTypeDef",
+    {
+        "capacityId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredRemoveTagsFromVaultInputRequestTypeDef = TypedDict(
     "_RequiredRemoveTagsFromVaultInputRequestTypeDef",
     {
         "vaultName": str,
     },
 )
 _OptionalRemoveTagsFromVaultInputRequestTypeDef = TypedDict(
@@ -923,68 +1050,27 @@
     {
         "accountId": str,
         "TagKeys": Sequence[str],
     },
     total=False,
 )
 
-
 class RemoveTagsFromVaultInputRequestTypeDef(
     _RequiredRemoveTagsFromVaultInputRequestTypeDef, _OptionalRemoveTagsFromVaultInputRequestTypeDef
 ):
     pass
 
-
-ServiceResourceAccountRequestTypeDef = TypedDict(
-    "ServiceResourceAccountRequestTypeDef",
-    {
-        "id": str,
-    },
-)
-
-ServiceResourceArchiveRequestTypeDef = TypedDict(
-    "ServiceResourceArchiveRequestTypeDef",
-    {
-        "account_id": str,
-        "vault_name": str,
-        "id": str,
-    },
-)
-
-ServiceResourceJobRequestTypeDef = TypedDict(
-    "ServiceResourceJobRequestTypeDef",
-    {
-        "account_id": str,
-        "vault_name": str,
-        "id": str,
-    },
-)
-
-ServiceResourceMultipartUploadRequestTypeDef = TypedDict(
-    "ServiceResourceMultipartUploadRequestTypeDef",
-    {
-        "account_id": str,
-        "vault_name": str,
-        "id": str,
-    },
-)
-
-ServiceResourceNotificationRequestTypeDef = TypedDict(
-    "ServiceResourceNotificationRequestTypeDef",
-    {
-        "account_id": str,
-        "vault_name": str,
-    },
-)
-
-ServiceResourceVaultRequestTypeDef = TypedDict(
-    "ServiceResourceVaultRequestTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "account_id": str,
-        "name": str,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
 _RequiredUploadArchiveInputRequestTypeDef = TypedDict(
     "_RequiredUploadArchiveInputRequestTypeDef",
     {
         "vaultName": str,
@@ -997,21 +1083,19 @@
         "archiveDescription": str,
         "checksum": str,
         "body": Union[str, bytes, IO[Any], StreamingBody],
     },
     total=False,
 )
 
-
 class UploadArchiveInputRequestTypeDef(
     _RequiredUploadArchiveInputRequestTypeDef, _OptionalUploadArchiveInputRequestTypeDef
 ):
     pass
 
-
 UploadArchiveInputVaultUploadArchiveTypeDef = TypedDict(
     "UploadArchiveInputVaultUploadArchiveTypeDef",
     {
         "archiveDescription": str,
         "checksum": str,
         "body": Union[str, bytes, IO[Any], StreamingBody],
     },
@@ -1042,165 +1126,24 @@
         "checksum": str,
         "range": str,
         "body": Union[str, bytes, IO[Any], StreamingBody],
     },
     total=False,
 )
 
-
 class UploadMultipartPartInputRequestTypeDef(
     _RequiredUploadMultipartPartInputRequestTypeDef, _OptionalUploadMultipartPartInputRequestTypeDef
 ):
     pass
 
-
-VaultArchiveRequestTypeDef = TypedDict(
-    "VaultArchiveRequestTypeDef",
-    {
-        "id": str,
-    },
-)
-
-VaultJobRequestTypeDef = TypedDict(
-    "VaultJobRequestTypeDef",
-    {
-        "id": str,
-    },
-)
-
-VaultMultipartUploadRequestTypeDef = TypedDict(
-    "VaultMultipartUploadRequestTypeDef",
-    {
-        "id": str,
-    },
-)
-
-ArchiveCreationOutputTypeDef = TypedDict(
-    "ArchiveCreationOutputTypeDef",
-    {
-        "location": str,
-        "checksum": str,
-        "archiveId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateVaultOutputTypeDef = TypedDict(
-    "CreateVaultOutputTypeDef",
-    {
-        "location": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeVaultOutputResponseMetadataTypeDef = TypedDict(
-    "DescribeVaultOutputResponseMetadataTypeDef",
-    {
-        "VaultARN": str,
-        "VaultName": str,
-        "CreationDate": str,
-        "LastInventoryDate": str,
-        "NumberOfArchives": int,
-        "SizeInBytes": int,
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
-GetJobOutputOutputTypeDef = TypedDict(
-    "GetJobOutputOutputTypeDef",
-    {
-        "body": StreamingBody,
-        "checksum": str,
-        "status": int,
-        "contentRange": str,
-        "acceptRanges": str,
-        "contentType": str,
-        "archiveDescription": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetVaultLockOutputTypeDef = TypedDict(
-    "GetVaultLockOutputTypeDef",
-    {
-        "Policy": str,
-        "State": str,
-        "ExpirationDate": str,
-        "CreationDate": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-InitiateJobOutputTypeDef = TypedDict(
-    "InitiateJobOutputTypeDef",
-    {
-        "location": str,
-        "jobId": str,
-        "jobOutputPath": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-InitiateMultipartUploadOutputTypeDef = TypedDict(
-    "InitiateMultipartUploadOutputTypeDef",
-    {
-        "location": str,
-        "uploadId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-InitiateVaultLockOutputTypeDef = TypedDict(
-    "InitiateVaultLockOutputTypeDef",
-    {
-        "lockId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-InventoryRetrievalJobDescriptionResponseMetadataTypeDef = TypedDict(
-    "InventoryRetrievalJobDescriptionResponseMetadataTypeDef",
-    {
-        "Format": str,
-        "StartDate": str,
-        "EndDate": str,
-        "Limit": str,
-        "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForVaultOutputTypeDef = TypedDict(
-    "ListTagsForVaultOutputTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PurchaseProvisionedCapacityOutputTypeDef = TypedDict(
-    "PurchaseProvisionedCapacityOutputTypeDef",
-    {
-        "capacityId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 UploadMultipartPartOutputTypeDef = TypedDict(
     "UploadMultipartPartOutputTypeDef",
     {
         "checksum": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InputSerializationTypeDef = TypedDict(
     "InputSerializationTypeDef",
     {
         "csv": CSVInputTypeDef,
@@ -1235,22 +1178,20 @@
     "_OptionalDescribeVaultInputVaultExistsWaitTypeDef",
     {
         "WaiterConfig": WaiterConfigTypeDef,
     },
     total=False,
 )
 
-
 class DescribeVaultInputVaultExistsWaitTypeDef(
     _RequiredDescribeVaultInputVaultExistsWaitTypeDef,
     _OptionalDescribeVaultInputVaultExistsWaitTypeDef,
 ):
     pass
 
-
 _RequiredDescribeVaultInputVaultNotExistsWaitTypeDef = TypedDict(
     "_RequiredDescribeVaultInputVaultNotExistsWaitTypeDef",
     {
         "accountId": str,
         "vaultName": str,
     },
 )
@@ -1258,36 +1199,34 @@
     "_OptionalDescribeVaultInputVaultNotExistsWaitTypeDef",
     {
         "WaiterConfig": WaiterConfigTypeDef,
     },
     total=False,
 )
 
-
 class DescribeVaultInputVaultNotExistsWaitTypeDef(
     _RequiredDescribeVaultInputVaultNotExistsWaitTypeDef,
     _OptionalDescribeVaultInputVaultNotExistsWaitTypeDef,
 ):
     pass
 
-
 ListVaultsOutputTypeDef = TypedDict(
     "ListVaultsOutputTypeDef",
     {
         "VaultList": List[DescribeVaultOutputTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetVaultAccessPolicyOutputTypeDef = TypedDict(
     "GetVaultAccessPolicyOutputTypeDef",
     {
         "policy": VaultAccessPolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSetVaultAccessPolicyInputRequestTypeDef = TypedDict(
     "_RequiredSetVaultAccessPolicyInputRequestTypeDef",
     {
         "vaultName": str,
@@ -1298,27 +1237,25 @@
     {
         "accountId": str,
         "policy": VaultAccessPolicyTypeDef,
     },
     total=False,
 )
 
-
 class SetVaultAccessPolicyInputRequestTypeDef(
     _RequiredSetVaultAccessPolicyInputRequestTypeDef,
     _OptionalSetVaultAccessPolicyInputRequestTypeDef,
 ):
     pass
 
-
 GetVaultNotificationsOutputTypeDef = TypedDict(
     "GetVaultNotificationsOutputTypeDef",
     {
         "vaultNotificationConfig": VaultNotificationConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SetVaultNotificationsInputNotificationSetTypeDef = TypedDict(
     "SetVaultNotificationsInputNotificationSetTypeDef",
     {
         "vaultNotificationConfig": VaultNotificationConfigTypeDef,
@@ -1337,22 +1274,20 @@
     {
         "accountId": str,
         "vaultNotificationConfig": VaultNotificationConfigTypeDef,
     },
     total=False,
 )
 
-
 class SetVaultNotificationsInputRequestTypeDef(
     _RequiredSetVaultNotificationsInputRequestTypeDef,
     _OptionalSetVaultNotificationsInputRequestTypeDef,
 ):
     pass
 
-
 GrantTypeDef = TypedDict(
     "GrantTypeDef",
     {
         "Grantee": GranteeTypeDef,
         "Permission": PermissionType,
     },
     total=False,
@@ -1369,152 +1304,58 @@
     {
         "accountId": str,
         "policy": VaultLockPolicyTypeDef,
     },
     total=False,
 )
 
-
 class InitiateVaultLockInputRequestTypeDef(
     _RequiredInitiateVaultLockInputRequestTypeDef, _OptionalInitiateVaultLockInputRequestTypeDef
 ):
     pass
 
-
-_RequiredListJobsInputListJobsPaginateTypeDef = TypedDict(
-    "_RequiredListJobsInputListJobsPaginateTypeDef",
-    {
-        "accountId": str,
-        "vaultName": str,
-    },
-)
-_OptionalListJobsInputListJobsPaginateTypeDef = TypedDict(
-    "_OptionalListJobsInputListJobsPaginateTypeDef",
-    {
-        "statuscode": str,
-        "completed": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListJobsInputListJobsPaginateTypeDef(
-    _RequiredListJobsInputListJobsPaginateTypeDef, _OptionalListJobsInputListJobsPaginateTypeDef
-):
-    pass
-
-
-_RequiredListMultipartUploadsInputListMultipartUploadsPaginateTypeDef = TypedDict(
-    "_RequiredListMultipartUploadsInputListMultipartUploadsPaginateTypeDef",
-    {
-        "accountId": str,
-        "vaultName": str,
-    },
-)
-_OptionalListMultipartUploadsInputListMultipartUploadsPaginateTypeDef = TypedDict(
-    "_OptionalListMultipartUploadsInputListMultipartUploadsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListMultipartUploadsInputListMultipartUploadsPaginateTypeDef(
-    _RequiredListMultipartUploadsInputListMultipartUploadsPaginateTypeDef,
-    _OptionalListMultipartUploadsInputListMultipartUploadsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListPartsInputListPartsPaginateTypeDef = TypedDict(
-    "_RequiredListPartsInputListPartsPaginateTypeDef",
-    {
-        "accountId": str,
-        "vaultName": str,
-        "uploadId": str,
-    },
-)
-_OptionalListPartsInputListPartsPaginateTypeDef = TypedDict(
-    "_OptionalListPartsInputListPartsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListPartsInputListPartsPaginateTypeDef(
-    _RequiredListPartsInputListPartsPaginateTypeDef, _OptionalListPartsInputListPartsPaginateTypeDef
-):
-    pass
-
-
-_RequiredListVaultsInputListVaultsPaginateTypeDef = TypedDict(
-    "_RequiredListVaultsInputListVaultsPaginateTypeDef",
-    {
-        "accountId": str,
-    },
-)
-_OptionalListVaultsInputListVaultsPaginateTypeDef = TypedDict(
-    "_OptionalListVaultsInputListVaultsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListVaultsInputListVaultsPaginateTypeDef(
-    _RequiredListVaultsInputListVaultsPaginateTypeDef,
-    _OptionalListVaultsInputListVaultsPaginateTypeDef,
-):
-    pass
-
-
 ListMultipartUploadsOutputTypeDef = TypedDict(
     "ListMultipartUploadsOutputTypeDef",
     {
         "UploadsList": List[UploadListElementTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPartsOutputTypeDef = TypedDict(
     "ListPartsOutputTypeDef",
     {
         "MultipartUploadId": str,
         "VaultARN": str,
         "ArchiveDescription": str,
         "PartSizeInBytes": int,
         "CreationDate": str,
         "Parts": List[PartListElementTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProvisionedCapacityOutputTypeDef = TypedDict(
     "ListProvisionedCapacityOutputTypeDef",
     {
         "ProvisionedCapacityList": List[ProvisionedCapacityDescriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SelectParametersResponseMetadataTypeDef = TypedDict(
     "SelectParametersResponseMetadataTypeDef",
     {
         "InputSerialization": InputSerializationTypeDef,
         "ExpressionType": Literal["SQL"],
         "Expression": str,
         "OutputSerialization": OutputSerializationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SelectParametersTypeDef = TypedDict(
     "SelectParametersTypeDef",
     {
         "InputSerialization": InputSerializationTypeDef,
@@ -1525,15 +1366,15 @@
     total=False,
 )
 
 GetDataRetrievalPolicyOutputTypeDef = TypedDict(
     "GetDataRetrievalPolicyOutputTypeDef",
     {
         "Policy": DataRetrievalPolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SetDataRetrievalPolicyInputRequestTypeDef = TypedDict(
     "SetDataRetrievalPolicyInputRequestTypeDef",
     {
         "accountId": str,
@@ -1557,15 +1398,15 @@
     total=False,
 )
 
 OutputLocationResponseMetadataTypeDef = TypedDict(
     "OutputLocationResponseMetadataTypeDef",
     {
         "S3": S3LocationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OutputLocationTypeDef = TypedDict(
     "OutputLocationTypeDef",
     {
         "S3": S3LocationTypeDef,
@@ -1593,15 +1434,15 @@
         "ArchiveSHA256TreeHash": str,
         "RetrievalByteRange": str,
         "Tier": str,
         "InventoryRetrievalParameters": InventoryRetrievalJobDescriptionTypeDef,
         "JobOutputPath": str,
         "SelectParameters": SelectParametersTypeDef,
         "OutputLocation": OutputLocationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GlacierJobDescriptionTypeDef = TypedDict(
     "GlacierJobDescriptionTypeDef",
     {
         "JobId": str,
@@ -1647,15 +1488,15 @@
 )
 
 ListJobsOutputTypeDef = TypedDict(
     "ListJobsOutputTypeDef",
     {
         "JobList": List[GlacierJobDescriptionTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredInitiateJobInputRequestTypeDef = TypedDict(
     "_RequiredInitiateJobInputRequestTypeDef",
     {
         "vaultName": str,
@@ -1666,12 +1507,11 @@
     {
         "accountId": str,
         "jobParameters": JobParametersTypeDef,
     },
     total=False,
 )
 
-
 class InitiateJobInputRequestTypeDef(
     _RequiredInitiateJobInputRequestTypeDef, _OptionalInitiateJobInputRequestTypeDef
 ):
     pass
```

### Comparing `types-aiobotocore-glacier-2.5.0.post1/types_aiobotocore_glacier/type_defs.pyi` & `types-aiobotocore-glacier-2.5.1/types_aiobotocore_glacier/type_defs.py`

 * *Files 3% similar despite different names*

```diff
@@ -33,108 +33,99 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "AbortMultipartUploadInputRequestTypeDef",
     "AbortVaultLockInputRequestTypeDef",
-    "AccountVaultRequestTypeDef",
     "AddTagsToVaultInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "ArchiveCreationOutputTypeDef",
     "CSVInputTypeDef",
     "CSVOutputTypeDef",
     "CompleteMultipartUploadInputMultipartUploadCompleteTypeDef",
     "CompleteMultipartUploadInputRequestTypeDef",
     "CompleteVaultLockInputRequestTypeDef",
     "CreateVaultInputAccountCreateVaultTypeDef",
     "CreateVaultInputRequestTypeDef",
     "CreateVaultInputServiceResourceCreateVaultTypeDef",
+    "CreateVaultOutputTypeDef",
     "DataRetrievalRuleTypeDef",
     "DeleteArchiveInputRequestTypeDef",
     "DeleteVaultAccessPolicyInputRequestTypeDef",
     "DeleteVaultInputRequestTypeDef",
     "DeleteVaultNotificationsInputRequestTypeDef",
     "DescribeJobInputRequestTypeDef",
     "DescribeVaultInputRequestTypeDef",
     "WaiterConfigTypeDef",
+    "DescribeVaultOutputResponseMetadataTypeDef",
     "DescribeVaultOutputTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EncryptionTypeDef",
     "GetDataRetrievalPolicyInputRequestTypeDef",
     "GetJobOutputInputJobGetOutputTypeDef",
     "GetJobOutputInputRequestTypeDef",
+    "GetJobOutputOutputTypeDef",
     "GetVaultAccessPolicyInputRequestTypeDef",
     "VaultAccessPolicyTypeDef",
     "GetVaultLockInputRequestTypeDef",
+    "GetVaultLockOutputTypeDef",
     "GetVaultNotificationsInputRequestTypeDef",
     "VaultNotificationConfigTypeDef",
     "InventoryRetrievalJobDescriptionTypeDef",
     "GranteeTypeDef",
+    "InitiateJobOutputTypeDef",
     "InitiateMultipartUploadInputRequestTypeDef",
     "InitiateMultipartUploadInputVaultInitiateMultipartUploadTypeDef",
+    "InitiateMultipartUploadOutputTypeDef",
     "VaultLockPolicyTypeDef",
+    "InitiateVaultLockOutputTypeDef",
+    "InventoryRetrievalJobDescriptionResponseMetadataTypeDef",
     "InventoryRetrievalJobInputTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListJobsInputListJobsPaginateTypeDef",
     "ListJobsInputRequestTypeDef",
+    "ListMultipartUploadsInputListMultipartUploadsPaginateTypeDef",
     "ListMultipartUploadsInputRequestTypeDef",
     "UploadListElementTypeDef",
+    "ListPartsInputListPartsPaginateTypeDef",
     "ListPartsInputMultipartUploadPartsTypeDef",
     "ListPartsInputRequestTypeDef",
     "PartListElementTypeDef",
     "ListProvisionedCapacityInputRequestTypeDef",
     "ProvisionedCapacityDescriptionTypeDef",
     "ListTagsForVaultInputRequestTypeDef",
+    "ListTagsForVaultOutputTypeDef",
+    "ListVaultsInputListVaultsPaginateTypeDef",
     "ListVaultsInputRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "PurchaseProvisionedCapacityInputRequestTypeDef",
+    "PurchaseProvisionedCapacityOutputTypeDef",
     "RemoveTagsFromVaultInputRequestTypeDef",
-    "ServiceResourceAccountRequestTypeDef",
-    "ServiceResourceArchiveRequestTypeDef",
-    "ServiceResourceJobRequestTypeDef",
-    "ServiceResourceMultipartUploadRequestTypeDef",
-    "ServiceResourceNotificationRequestTypeDef",
-    "ServiceResourceVaultRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "UploadArchiveInputRequestTypeDef",
     "UploadArchiveInputVaultUploadArchiveTypeDef",
     "UploadMultipartPartInputMultipartUploadUploadPartTypeDef",
     "UploadMultipartPartInputRequestTypeDef",
-    "VaultArchiveRequestTypeDef",
-    "VaultJobRequestTypeDef",
-    "VaultMultipartUploadRequestTypeDef",
-    "ArchiveCreationOutputTypeDef",
-    "CreateVaultOutputTypeDef",
-    "DescribeVaultOutputResponseMetadataTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetJobOutputOutputTypeDef",
-    "GetVaultLockOutputTypeDef",
-    "InitiateJobOutputTypeDef",
-    "InitiateMultipartUploadOutputTypeDef",
-    "InitiateVaultLockOutputTypeDef",
-    "InventoryRetrievalJobDescriptionResponseMetadataTypeDef",
-    "ListTagsForVaultOutputTypeDef",
-    "PurchaseProvisionedCapacityOutputTypeDef",
     "UploadMultipartPartOutputTypeDef",
     "InputSerializationTypeDef",
     "OutputSerializationTypeDef",
     "DataRetrievalPolicyTypeDef",
     "DescribeVaultInputVaultExistsWaitTypeDef",
     "DescribeVaultInputVaultNotExistsWaitTypeDef",
     "ListVaultsOutputTypeDef",
     "GetVaultAccessPolicyOutputTypeDef",
     "SetVaultAccessPolicyInputRequestTypeDef",
     "GetVaultNotificationsOutputTypeDef",
     "SetVaultNotificationsInputNotificationSetTypeDef",
     "SetVaultNotificationsInputRequestTypeDef",
     "GrantTypeDef",
     "InitiateVaultLockInputRequestTypeDef",
-    "ListJobsInputListJobsPaginateTypeDef",
-    "ListMultipartUploadsInputListMultipartUploadsPaginateTypeDef",
-    "ListPartsInputListPartsPaginateTypeDef",
-    "ListVaultsInputListVaultsPaginateTypeDef",
     "ListMultipartUploadsOutputTypeDef",
     "ListPartsOutputTypeDef",
     "ListProvisionedCapacityOutputTypeDef",
     "SelectParametersResponseMetadataTypeDef",
     "SelectParametersTypeDef",
     "GetDataRetrievalPolicyOutputTypeDef",
     "SetDataRetrievalPolicyInputRequestTypeDef",
@@ -159,45 +150,42 @@
     "_OptionalAbortMultipartUploadInputRequestTypeDef",
     {
         "accountId": str,
     },
     total=False,
 )
 
+
 class AbortMultipartUploadInputRequestTypeDef(
     _RequiredAbortMultipartUploadInputRequestTypeDef,
     _OptionalAbortMultipartUploadInputRequestTypeDef,
 ):
     pass
 
+
 _RequiredAbortVaultLockInputRequestTypeDef = TypedDict(
     "_RequiredAbortVaultLockInputRequestTypeDef",
     {
         "vaultName": str,
     },
 )
 _OptionalAbortVaultLockInputRequestTypeDef = TypedDict(
     "_OptionalAbortVaultLockInputRequestTypeDef",
     {
         "accountId": str,
     },
     total=False,
 )
 
+
 class AbortVaultLockInputRequestTypeDef(
     _RequiredAbortVaultLockInputRequestTypeDef, _OptionalAbortVaultLockInputRequestTypeDef
 ):
     pass
 
-AccountVaultRequestTypeDef = TypedDict(
-    "AccountVaultRequestTypeDef",
-    {
-        "name": str,
-    },
-)
 
 _RequiredAddTagsToVaultInputRequestTypeDef = TypedDict(
     "_RequiredAddTagsToVaultInputRequestTypeDef",
     {
         "vaultName": str,
     },
 )
@@ -206,27 +194,28 @@
     {
         "accountId": str,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
+
 class AddTagsToVaultInputRequestTypeDef(
     _RequiredAddTagsToVaultInputRequestTypeDef, _OptionalAddTagsToVaultInputRequestTypeDef
 ):
     pass
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+
+ArchiveCreationOutputTypeDef = TypedDict(
+    "ArchiveCreationOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "location": str,
+        "checksum": str,
+        "archiveId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CSVInputTypeDef = TypedDict(
     "CSVInputTypeDef",
     {
         "FileHeaderInfo": FileHeaderInfoType,
@@ -273,20 +262,22 @@
         "accountId": str,
         "archiveSize": str,
         "checksum": str,
     },
     total=False,
 )
 
+
 class CompleteMultipartUploadInputRequestTypeDef(
     _RequiredCompleteMultipartUploadInputRequestTypeDef,
     _OptionalCompleteMultipartUploadInputRequestTypeDef,
 ):
     pass
 
+
 _RequiredCompleteVaultLockInputRequestTypeDef = TypedDict(
     "_RequiredCompleteVaultLockInputRequestTypeDef",
     {
         "vaultName": str,
         "lockId": str,
     },
 )
@@ -294,19 +285,21 @@
     "_OptionalCompleteVaultLockInputRequestTypeDef",
     {
         "accountId": str,
     },
     total=False,
 )
 
+
 class CompleteVaultLockInputRequestTypeDef(
     _RequiredCompleteVaultLockInputRequestTypeDef, _OptionalCompleteVaultLockInputRequestTypeDef
 ):
     pass
 
+
 CreateVaultInputAccountCreateVaultTypeDef = TypedDict(
     "CreateVaultInputAccountCreateVaultTypeDef",
     {
         "vaultName": str,
     },
 )
 
@@ -320,39 +313,51 @@
     "_OptionalCreateVaultInputRequestTypeDef",
     {
         "accountId": str,
     },
     total=False,
 )
 
+
 class CreateVaultInputRequestTypeDef(
     _RequiredCreateVaultInputRequestTypeDef, _OptionalCreateVaultInputRequestTypeDef
 ):
     pass
 
+
 _RequiredCreateVaultInputServiceResourceCreateVaultTypeDef = TypedDict(
     "_RequiredCreateVaultInputServiceResourceCreateVaultTypeDef",
     {
         "vaultName": str,
     },
 )
 _OptionalCreateVaultInputServiceResourceCreateVaultTypeDef = TypedDict(
     "_OptionalCreateVaultInputServiceResourceCreateVaultTypeDef",
     {
         "accountId": str,
     },
     total=False,
 )
 
+
 class CreateVaultInputServiceResourceCreateVaultTypeDef(
     _RequiredCreateVaultInputServiceResourceCreateVaultTypeDef,
     _OptionalCreateVaultInputServiceResourceCreateVaultTypeDef,
 ):
     pass
 
+
+CreateVaultOutputTypeDef = TypedDict(
+    "CreateVaultOutputTypeDef",
+    {
+        "location": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DataRetrievalRuleTypeDef = TypedDict(
     "DataRetrievalRuleTypeDef",
     {
         "Strategy": str,
         "BytesPerHour": int,
     },
     total=False,
@@ -369,78 +374,86 @@
     "_OptionalDeleteArchiveInputRequestTypeDef",
     {
         "accountId": str,
     },
     total=False,
 )
 
+
 class DeleteArchiveInputRequestTypeDef(
     _RequiredDeleteArchiveInputRequestTypeDef, _OptionalDeleteArchiveInputRequestTypeDef
 ):
     pass
 
+
 _RequiredDeleteVaultAccessPolicyInputRequestTypeDef = TypedDict(
     "_RequiredDeleteVaultAccessPolicyInputRequestTypeDef",
     {
         "vaultName": str,
     },
 )
 _OptionalDeleteVaultAccessPolicyInputRequestTypeDef = TypedDict(
     "_OptionalDeleteVaultAccessPolicyInputRequestTypeDef",
     {
         "accountId": str,
     },
     total=False,
 )
 
+
 class DeleteVaultAccessPolicyInputRequestTypeDef(
     _RequiredDeleteVaultAccessPolicyInputRequestTypeDef,
     _OptionalDeleteVaultAccessPolicyInputRequestTypeDef,
 ):
     pass
 
+
 _RequiredDeleteVaultInputRequestTypeDef = TypedDict(
     "_RequiredDeleteVaultInputRequestTypeDef",
     {
         "vaultName": str,
     },
 )
 _OptionalDeleteVaultInputRequestTypeDef = TypedDict(
     "_OptionalDeleteVaultInputRequestTypeDef",
     {
         "accountId": str,
     },
     total=False,
 )
 
+
 class DeleteVaultInputRequestTypeDef(
     _RequiredDeleteVaultInputRequestTypeDef, _OptionalDeleteVaultInputRequestTypeDef
 ):
     pass
 
+
 _RequiredDeleteVaultNotificationsInputRequestTypeDef = TypedDict(
     "_RequiredDeleteVaultNotificationsInputRequestTypeDef",
     {
         "vaultName": str,
     },
 )
 _OptionalDeleteVaultNotificationsInputRequestTypeDef = TypedDict(
     "_OptionalDeleteVaultNotificationsInputRequestTypeDef",
     {
         "accountId": str,
     },
     total=False,
 )
 
+
 class DeleteVaultNotificationsInputRequestTypeDef(
     _RequiredDeleteVaultNotificationsInputRequestTypeDef,
     _OptionalDeleteVaultNotificationsInputRequestTypeDef,
 ):
     pass
 
+
 _RequiredDescribeJobInputRequestTypeDef = TypedDict(
     "_RequiredDescribeJobInputRequestTypeDef",
     {
         "vaultName": str,
         "jobId": str,
     },
 )
@@ -448,60 +461,84 @@
     "_OptionalDescribeJobInputRequestTypeDef",
     {
         "accountId": str,
     },
     total=False,
 )
 
+
 class DescribeJobInputRequestTypeDef(
     _RequiredDescribeJobInputRequestTypeDef, _OptionalDescribeJobInputRequestTypeDef
 ):
     pass
 
+
 _RequiredDescribeVaultInputRequestTypeDef = TypedDict(
     "_RequiredDescribeVaultInputRequestTypeDef",
     {
         "vaultName": str,
     },
 )
 _OptionalDescribeVaultInputRequestTypeDef = TypedDict(
     "_OptionalDescribeVaultInputRequestTypeDef",
     {
         "accountId": str,
     },
     total=False,
 )
 
+
 class DescribeVaultInputRequestTypeDef(
     _RequiredDescribeVaultInputRequestTypeDef, _OptionalDescribeVaultInputRequestTypeDef
 ):
     pass
 
+
 WaiterConfigTypeDef = TypedDict(
     "WaiterConfigTypeDef",
     {
         "Delay": int,
         "MaxAttempts": int,
     },
     total=False,
 )
 
+DescribeVaultOutputResponseMetadataTypeDef = TypedDict(
+    "DescribeVaultOutputResponseMetadataTypeDef",
+    {
+        "VaultARN": str,
+        "VaultName": str,
+        "CreationDate": str,
+        "LastInventoryDate": str,
+        "NumberOfArchives": int,
+        "SizeInBytes": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeVaultOutputTypeDef = TypedDict(
     "DescribeVaultOutputTypeDef",
     {
         "VaultARN": str,
         "VaultName": str,
         "CreationDate": str,
         "LastInventoryDate": str,
         "NumberOfArchives": int,
         "SizeInBytes": int,
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
 EncryptionTypeDef = TypedDict(
     "EncryptionTypeDef",
     {
         "EncryptionType": EncryptionTypeType,
         "KMSKeyId": str,
         "KMSContext": str,
     },
@@ -536,39 +573,57 @@
     {
         "accountId": str,
         "range": str,
     },
     total=False,
 )
 
+
 class GetJobOutputInputRequestTypeDef(
     _RequiredGetJobOutputInputRequestTypeDef, _OptionalGetJobOutputInputRequestTypeDef
 ):
     pass
 
+
+GetJobOutputOutputTypeDef = TypedDict(
+    "GetJobOutputOutputTypeDef",
+    {
+        "body": StreamingBody,
+        "checksum": str,
+        "status": int,
+        "contentRange": str,
+        "acceptRanges": str,
+        "contentType": str,
+        "archiveDescription": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetVaultAccessPolicyInputRequestTypeDef = TypedDict(
     "_RequiredGetVaultAccessPolicyInputRequestTypeDef",
     {
         "vaultName": str,
     },
 )
 _OptionalGetVaultAccessPolicyInputRequestTypeDef = TypedDict(
     "_OptionalGetVaultAccessPolicyInputRequestTypeDef",
     {
         "accountId": str,
     },
     total=False,
 )
 
+
 class GetVaultAccessPolicyInputRequestTypeDef(
     _RequiredGetVaultAccessPolicyInputRequestTypeDef,
     _OptionalGetVaultAccessPolicyInputRequestTypeDef,
 ):
     pass
 
+
 VaultAccessPolicyTypeDef = TypedDict(
     "VaultAccessPolicyTypeDef",
     {
         "Policy": str,
     },
     total=False,
 )
@@ -583,39 +638,54 @@
     "_OptionalGetVaultLockInputRequestTypeDef",
     {
         "accountId": str,
     },
     total=False,
 )
 
+
 class GetVaultLockInputRequestTypeDef(
     _RequiredGetVaultLockInputRequestTypeDef, _OptionalGetVaultLockInputRequestTypeDef
 ):
     pass
 
+
+GetVaultLockOutputTypeDef = TypedDict(
+    "GetVaultLockOutputTypeDef",
+    {
+        "Policy": str,
+        "State": str,
+        "ExpirationDate": str,
+        "CreationDate": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetVaultNotificationsInputRequestTypeDef = TypedDict(
     "_RequiredGetVaultNotificationsInputRequestTypeDef",
     {
         "vaultName": str,
     },
 )
 _OptionalGetVaultNotificationsInputRequestTypeDef = TypedDict(
     "_OptionalGetVaultNotificationsInputRequestTypeDef",
     {
         "accountId": str,
     },
     total=False,
 )
 
+
 class GetVaultNotificationsInputRequestTypeDef(
     _RequiredGetVaultNotificationsInputRequestTypeDef,
     _OptionalGetVaultNotificationsInputRequestTypeDef,
 ):
     pass
 
+
 VaultNotificationConfigTypeDef = TypedDict(
     "VaultNotificationConfigTypeDef",
     {
         "SNSTopic": str,
         "Events": List[str],
     },
     total=False,
@@ -646,17 +716,29 @@
         "URI": str,
         "ID": str,
         "EmailAddress": str,
     },
     total=False,
 )
 
+
 class GranteeTypeDef(_RequiredGranteeTypeDef, _OptionalGranteeTypeDef):
     pass
 
+
+InitiateJobOutputTypeDef = TypedDict(
+    "InitiateJobOutputTypeDef",
+    {
+        "location": str,
+        "jobId": str,
+        "jobOutputPath": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredInitiateMultipartUploadInputRequestTypeDef = TypedDict(
     "_RequiredInitiateMultipartUploadInputRequestTypeDef",
     {
         "vaultName": str,
     },
 )
 _OptionalInitiateMultipartUploadInputRequestTypeDef = TypedDict(
@@ -665,58 +747,103 @@
         "accountId": str,
         "archiveDescription": str,
         "partSize": str,
     },
     total=False,
 )
 
+
 class InitiateMultipartUploadInputRequestTypeDef(
     _RequiredInitiateMultipartUploadInputRequestTypeDef,
     _OptionalInitiateMultipartUploadInputRequestTypeDef,
 ):
     pass
 
+
 InitiateMultipartUploadInputVaultInitiateMultipartUploadTypeDef = TypedDict(
     "InitiateMultipartUploadInputVaultInitiateMultipartUploadTypeDef",
     {
         "archiveDescription": str,
         "partSize": str,
     },
     total=False,
 )
 
+InitiateMultipartUploadOutputTypeDef = TypedDict(
+    "InitiateMultipartUploadOutputTypeDef",
+    {
+        "location": str,
+        "uploadId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 VaultLockPolicyTypeDef = TypedDict(
     "VaultLockPolicyTypeDef",
     {
         "Policy": str,
     },
     total=False,
 )
 
+InitiateVaultLockOutputTypeDef = TypedDict(
+    "InitiateVaultLockOutputTypeDef",
+    {
+        "lockId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+InventoryRetrievalJobDescriptionResponseMetadataTypeDef = TypedDict(
+    "InventoryRetrievalJobDescriptionResponseMetadataTypeDef",
+    {
+        "Format": str,
+        "StartDate": str,
+        "EndDate": str,
+        "Limit": str,
+        "Marker": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 InventoryRetrievalJobInputTypeDef = TypedDict(
     "InventoryRetrievalJobInputTypeDef",
     {
         "StartDate": str,
         "EndDate": str,
         "Limit": str,
         "Marker": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListJobsInputListJobsPaginateTypeDef = TypedDict(
+    "_RequiredListJobsInputListJobsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "accountId": str,
+        "vaultName": str,
+    },
+)
+_OptionalListJobsInputListJobsPaginateTypeDef = TypedDict(
+    "_OptionalListJobsInputListJobsPaginateTypeDef",
+    {
+        "statuscode": str,
+        "completed": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListJobsInputListJobsPaginateTypeDef(
+    _RequiredListJobsInputListJobsPaginateTypeDef, _OptionalListJobsInputListJobsPaginateTypeDef
+):
+    pass
+
+
 _RequiredListJobsInputRequestTypeDef = TypedDict(
     "_RequiredListJobsInputRequestTypeDef",
     {
         "vaultName": str,
     },
 )
 _OptionalListJobsInputRequestTypeDef = TypedDict(
@@ -727,19 +854,44 @@
         "marker": str,
         "statuscode": str,
         "completed": str,
     },
     total=False,
 )
 
+
 class ListJobsInputRequestTypeDef(
     _RequiredListJobsInputRequestTypeDef, _OptionalListJobsInputRequestTypeDef
 ):
     pass
 
+
+_RequiredListMultipartUploadsInputListMultipartUploadsPaginateTypeDef = TypedDict(
+    "_RequiredListMultipartUploadsInputListMultipartUploadsPaginateTypeDef",
+    {
+        "accountId": str,
+        "vaultName": str,
+    },
+)
+_OptionalListMultipartUploadsInputListMultipartUploadsPaginateTypeDef = TypedDict(
+    "_OptionalListMultipartUploadsInputListMultipartUploadsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListMultipartUploadsInputListMultipartUploadsPaginateTypeDef(
+    _RequiredListMultipartUploadsInputListMultipartUploadsPaginateTypeDef,
+    _OptionalListMultipartUploadsInputListMultipartUploadsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListMultipartUploadsInputRequestTypeDef = TypedDict(
     "_RequiredListMultipartUploadsInputRequestTypeDef",
     {
         "vaultName": str,
     },
 )
 _OptionalListMultipartUploadsInputRequestTypeDef = TypedDict(
@@ -748,32 +900,57 @@
         "accountId": str,
         "marker": str,
         "limit": str,
     },
     total=False,
 )
 
+
 class ListMultipartUploadsInputRequestTypeDef(
     _RequiredListMultipartUploadsInputRequestTypeDef,
     _OptionalListMultipartUploadsInputRequestTypeDef,
 ):
     pass
 
+
 UploadListElementTypeDef = TypedDict(
     "UploadListElementTypeDef",
     {
         "MultipartUploadId": str,
         "VaultARN": str,
         "ArchiveDescription": str,
         "PartSizeInBytes": int,
         "CreationDate": str,
     },
     total=False,
 )
 
+_RequiredListPartsInputListPartsPaginateTypeDef = TypedDict(
+    "_RequiredListPartsInputListPartsPaginateTypeDef",
+    {
+        "accountId": str,
+        "vaultName": str,
+        "uploadId": str,
+    },
+)
+_OptionalListPartsInputListPartsPaginateTypeDef = TypedDict(
+    "_OptionalListPartsInputListPartsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListPartsInputListPartsPaginateTypeDef(
+    _RequiredListPartsInputListPartsPaginateTypeDef, _OptionalListPartsInputListPartsPaginateTypeDef
+):
+    pass
+
+
 ListPartsInputMultipartUploadPartsTypeDef = TypedDict(
     "ListPartsInputMultipartUploadPartsTypeDef",
     {
         "marker": str,
         "limit": str,
     },
     total=False,
@@ -792,19 +969,21 @@
         "accountId": str,
         "marker": str,
         "limit": str,
     },
     total=False,
 )
 
+
 class ListPartsInputRequestTypeDef(
     _RequiredListPartsInputRequestTypeDef, _OptionalListPartsInputRequestTypeDef
 ):
     pass
 
+
 PartListElementTypeDef = TypedDict(
     "PartListElementTypeDef",
     {
         "RangeInBytes": str,
         "SHA256TreeHash": str,
     },
     total=False,
@@ -838,37 +1017,87 @@
     "_OptionalListTagsForVaultInputRequestTypeDef",
     {
         "accountId": str,
     },
     total=False,
 )
 
+
 class ListTagsForVaultInputRequestTypeDef(
     _RequiredListTagsForVaultInputRequestTypeDef, _OptionalListTagsForVaultInputRequestTypeDef
 ):
     pass
 
+
+ListTagsForVaultOutputTypeDef = TypedDict(
+    "ListTagsForVaultOutputTypeDef",
+    {
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListVaultsInputListVaultsPaginateTypeDef = TypedDict(
+    "_RequiredListVaultsInputListVaultsPaginateTypeDef",
+    {
+        "accountId": str,
+    },
+)
+_OptionalListVaultsInputListVaultsPaginateTypeDef = TypedDict(
+    "_OptionalListVaultsInputListVaultsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListVaultsInputListVaultsPaginateTypeDef(
+    _RequiredListVaultsInputListVaultsPaginateTypeDef,
+    _OptionalListVaultsInputListVaultsPaginateTypeDef,
+):
+    pass
+
+
 ListVaultsInputRequestTypeDef = TypedDict(
     "ListVaultsInputRequestTypeDef",
     {
         "accountId": str,
         "marker": str,
         "limit": str,
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
 PurchaseProvisionedCapacityInputRequestTypeDef = TypedDict(
     "PurchaseProvisionedCapacityInputRequestTypeDef",
     {
         "accountId": str,
     },
     total=False,
 )
 
+PurchaseProvisionedCapacityOutputTypeDef = TypedDict(
+    "PurchaseProvisionedCapacityOutputTypeDef",
+    {
+        "capacityId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredRemoveTagsFromVaultInputRequestTypeDef = TypedDict(
     "_RequiredRemoveTagsFromVaultInputRequestTypeDef",
     {
         "vaultName": str,
     },
 )
 _OptionalRemoveTagsFromVaultInputRequestTypeDef = TypedDict(
@@ -876,66 +1105,29 @@
     {
         "accountId": str,
         "TagKeys": Sequence[str],
     },
     total=False,
 )
 
+
 class RemoveTagsFromVaultInputRequestTypeDef(
     _RequiredRemoveTagsFromVaultInputRequestTypeDef, _OptionalRemoveTagsFromVaultInputRequestTypeDef
 ):
     pass
 
-ServiceResourceAccountRequestTypeDef = TypedDict(
-    "ServiceResourceAccountRequestTypeDef",
-    {
-        "id": str,
-    },
-)
-
-ServiceResourceArchiveRequestTypeDef = TypedDict(
-    "ServiceResourceArchiveRequestTypeDef",
-    {
-        "account_id": str,
-        "vault_name": str,
-        "id": str,
-    },
-)
 
-ServiceResourceJobRequestTypeDef = TypedDict(
-    "ServiceResourceJobRequestTypeDef",
-    {
-        "account_id": str,
-        "vault_name": str,
-        "id": str,
-    },
-)
-
-ServiceResourceMultipartUploadRequestTypeDef = TypedDict(
-    "ServiceResourceMultipartUploadRequestTypeDef",
-    {
-        "account_id": str,
-        "vault_name": str,
-        "id": str,
-    },
-)
-
-ServiceResourceNotificationRequestTypeDef = TypedDict(
-    "ServiceResourceNotificationRequestTypeDef",
-    {
-        "account_id": str,
-        "vault_name": str,
-    },
-)
-
-ServiceResourceVaultRequestTypeDef = TypedDict(
-    "ServiceResourceVaultRequestTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "account_id": str,
-        "name": str,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
 _RequiredUploadArchiveInputRequestTypeDef = TypedDict(
     "_RequiredUploadArchiveInputRequestTypeDef",
     {
         "vaultName": str,
@@ -948,19 +1140,21 @@
         "archiveDescription": str,
         "checksum": str,
         "body": Union[str, bytes, IO[Any], StreamingBody],
     },
     total=False,
 )
 
+
 class UploadArchiveInputRequestTypeDef(
     _RequiredUploadArchiveInputRequestTypeDef, _OptionalUploadArchiveInputRequestTypeDef
 ):
     pass
 
+
 UploadArchiveInputVaultUploadArchiveTypeDef = TypedDict(
     "UploadArchiveInputVaultUploadArchiveTypeDef",
     {
         "archiveDescription": str,
         "checksum": str,
         "body": Union[str, bytes, IO[Any], StreamingBody],
     },
@@ -991,163 +1185,26 @@
         "checksum": str,
         "range": str,
         "body": Union[str, bytes, IO[Any], StreamingBody],
     },
     total=False,
 )
 
+
 class UploadMultipartPartInputRequestTypeDef(
     _RequiredUploadMultipartPartInputRequestTypeDef, _OptionalUploadMultipartPartInputRequestTypeDef
 ):
     pass
 
-VaultArchiveRequestTypeDef = TypedDict(
-    "VaultArchiveRequestTypeDef",
-    {
-        "id": str,
-    },
-)
-
-VaultJobRequestTypeDef = TypedDict(
-    "VaultJobRequestTypeDef",
-    {
-        "id": str,
-    },
-)
-
-VaultMultipartUploadRequestTypeDef = TypedDict(
-    "VaultMultipartUploadRequestTypeDef",
-    {
-        "id": str,
-    },
-)
-
-ArchiveCreationOutputTypeDef = TypedDict(
-    "ArchiveCreationOutputTypeDef",
-    {
-        "location": str,
-        "checksum": str,
-        "archiveId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateVaultOutputTypeDef = TypedDict(
-    "CreateVaultOutputTypeDef",
-    {
-        "location": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeVaultOutputResponseMetadataTypeDef = TypedDict(
-    "DescribeVaultOutputResponseMetadataTypeDef",
-    {
-        "VaultARN": str,
-        "VaultName": str,
-        "CreationDate": str,
-        "LastInventoryDate": str,
-        "NumberOfArchives": int,
-        "SizeInBytes": int,
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
-GetJobOutputOutputTypeDef = TypedDict(
-    "GetJobOutputOutputTypeDef",
-    {
-        "body": StreamingBody,
-        "checksum": str,
-        "status": int,
-        "contentRange": str,
-        "acceptRanges": str,
-        "contentType": str,
-        "archiveDescription": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetVaultLockOutputTypeDef = TypedDict(
-    "GetVaultLockOutputTypeDef",
-    {
-        "Policy": str,
-        "State": str,
-        "ExpirationDate": str,
-        "CreationDate": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-InitiateJobOutputTypeDef = TypedDict(
-    "InitiateJobOutputTypeDef",
-    {
-        "location": str,
-        "jobId": str,
-        "jobOutputPath": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-InitiateMultipartUploadOutputTypeDef = TypedDict(
-    "InitiateMultipartUploadOutputTypeDef",
-    {
-        "location": str,
-        "uploadId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-InitiateVaultLockOutputTypeDef = TypedDict(
-    "InitiateVaultLockOutputTypeDef",
-    {
-        "lockId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-InventoryRetrievalJobDescriptionResponseMetadataTypeDef = TypedDict(
-    "InventoryRetrievalJobDescriptionResponseMetadataTypeDef",
-    {
-        "Format": str,
-        "StartDate": str,
-        "EndDate": str,
-        "Limit": str,
-        "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForVaultOutputTypeDef = TypedDict(
-    "ListTagsForVaultOutputTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PurchaseProvisionedCapacityOutputTypeDef = TypedDict(
-    "PurchaseProvisionedCapacityOutputTypeDef",
-    {
-        "capacityId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
 UploadMultipartPartOutputTypeDef = TypedDict(
     "UploadMultipartPartOutputTypeDef",
     {
         "checksum": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InputSerializationTypeDef = TypedDict(
     "InputSerializationTypeDef",
     {
         "csv": CSVInputTypeDef,
@@ -1182,20 +1239,22 @@
     "_OptionalDescribeVaultInputVaultExistsWaitTypeDef",
     {
         "WaiterConfig": WaiterConfigTypeDef,
     },
     total=False,
 )
 
+
 class DescribeVaultInputVaultExistsWaitTypeDef(
     _RequiredDescribeVaultInputVaultExistsWaitTypeDef,
     _OptionalDescribeVaultInputVaultExistsWaitTypeDef,
 ):
     pass
 
+
 _RequiredDescribeVaultInputVaultNotExistsWaitTypeDef = TypedDict(
     "_RequiredDescribeVaultInputVaultNotExistsWaitTypeDef",
     {
         "accountId": str,
         "vaultName": str,
     },
 )
@@ -1203,34 +1262,36 @@
     "_OptionalDescribeVaultInputVaultNotExistsWaitTypeDef",
     {
         "WaiterConfig": WaiterConfigTypeDef,
     },
     total=False,
 )
 
+
 class DescribeVaultInputVaultNotExistsWaitTypeDef(
     _RequiredDescribeVaultInputVaultNotExistsWaitTypeDef,
     _OptionalDescribeVaultInputVaultNotExistsWaitTypeDef,
 ):
     pass
 
+
 ListVaultsOutputTypeDef = TypedDict(
     "ListVaultsOutputTypeDef",
     {
         "VaultList": List[DescribeVaultOutputTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetVaultAccessPolicyOutputTypeDef = TypedDict(
     "GetVaultAccessPolicyOutputTypeDef",
     {
         "policy": VaultAccessPolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSetVaultAccessPolicyInputRequestTypeDef = TypedDict(
     "_RequiredSetVaultAccessPolicyInputRequestTypeDef",
     {
         "vaultName": str,
@@ -1241,25 +1302,27 @@
     {
         "accountId": str,
         "policy": VaultAccessPolicyTypeDef,
     },
     total=False,
 )
 
+
 class SetVaultAccessPolicyInputRequestTypeDef(
     _RequiredSetVaultAccessPolicyInputRequestTypeDef,
     _OptionalSetVaultAccessPolicyInputRequestTypeDef,
 ):
     pass
 
+
 GetVaultNotificationsOutputTypeDef = TypedDict(
     "GetVaultNotificationsOutputTypeDef",
     {
         "vaultNotificationConfig": VaultNotificationConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SetVaultNotificationsInputNotificationSetTypeDef = TypedDict(
     "SetVaultNotificationsInputNotificationSetTypeDef",
     {
         "vaultNotificationConfig": VaultNotificationConfigTypeDef,
@@ -1278,20 +1341,22 @@
     {
         "accountId": str,
         "vaultNotificationConfig": VaultNotificationConfigTypeDef,
     },
     total=False,
 )
 
+
 class SetVaultNotificationsInputRequestTypeDef(
     _RequiredSetVaultNotificationsInputRequestTypeDef,
     _OptionalSetVaultNotificationsInputRequestTypeDef,
 ):
     pass
 
+
 GrantTypeDef = TypedDict(
     "GrantTypeDef",
     {
         "Grantee": GranteeTypeDef,
         "Permission": PermissionType,
     },
     total=False,
@@ -1308,142 +1373,60 @@
     {
         "accountId": str,
         "policy": VaultLockPolicyTypeDef,
     },
     total=False,
 )
 
+
 class InitiateVaultLockInputRequestTypeDef(
     _RequiredInitiateVaultLockInputRequestTypeDef, _OptionalInitiateVaultLockInputRequestTypeDef
 ):
     pass
 
-_RequiredListJobsInputListJobsPaginateTypeDef = TypedDict(
-    "_RequiredListJobsInputListJobsPaginateTypeDef",
-    {
-        "accountId": str,
-        "vaultName": str,
-    },
-)
-_OptionalListJobsInputListJobsPaginateTypeDef = TypedDict(
-    "_OptionalListJobsInputListJobsPaginateTypeDef",
-    {
-        "statuscode": str,
-        "completed": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListJobsInputListJobsPaginateTypeDef(
-    _RequiredListJobsInputListJobsPaginateTypeDef, _OptionalListJobsInputListJobsPaginateTypeDef
-):
-    pass
-
-_RequiredListMultipartUploadsInputListMultipartUploadsPaginateTypeDef = TypedDict(
-    "_RequiredListMultipartUploadsInputListMultipartUploadsPaginateTypeDef",
-    {
-        "accountId": str,
-        "vaultName": str,
-    },
-)
-_OptionalListMultipartUploadsInputListMultipartUploadsPaginateTypeDef = TypedDict(
-    "_OptionalListMultipartUploadsInputListMultipartUploadsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListMultipartUploadsInputListMultipartUploadsPaginateTypeDef(
-    _RequiredListMultipartUploadsInputListMultipartUploadsPaginateTypeDef,
-    _OptionalListMultipartUploadsInputListMultipartUploadsPaginateTypeDef,
-):
-    pass
-
-_RequiredListPartsInputListPartsPaginateTypeDef = TypedDict(
-    "_RequiredListPartsInputListPartsPaginateTypeDef",
-    {
-        "accountId": str,
-        "vaultName": str,
-        "uploadId": str,
-    },
-)
-_OptionalListPartsInputListPartsPaginateTypeDef = TypedDict(
-    "_OptionalListPartsInputListPartsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListPartsInputListPartsPaginateTypeDef(
-    _RequiredListPartsInputListPartsPaginateTypeDef, _OptionalListPartsInputListPartsPaginateTypeDef
-):
-    pass
-
-_RequiredListVaultsInputListVaultsPaginateTypeDef = TypedDict(
-    "_RequiredListVaultsInputListVaultsPaginateTypeDef",
-    {
-        "accountId": str,
-    },
-)
-_OptionalListVaultsInputListVaultsPaginateTypeDef = TypedDict(
-    "_OptionalListVaultsInputListVaultsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListVaultsInputListVaultsPaginateTypeDef(
-    _RequiredListVaultsInputListVaultsPaginateTypeDef,
-    _OptionalListVaultsInputListVaultsPaginateTypeDef,
-):
-    pass
 
 ListMultipartUploadsOutputTypeDef = TypedDict(
     "ListMultipartUploadsOutputTypeDef",
     {
         "UploadsList": List[UploadListElementTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPartsOutputTypeDef = TypedDict(
     "ListPartsOutputTypeDef",
     {
         "MultipartUploadId": str,
         "VaultARN": str,
         "ArchiveDescription": str,
         "PartSizeInBytes": int,
         "CreationDate": str,
         "Parts": List[PartListElementTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProvisionedCapacityOutputTypeDef = TypedDict(
     "ListProvisionedCapacityOutputTypeDef",
     {
         "ProvisionedCapacityList": List[ProvisionedCapacityDescriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SelectParametersResponseMetadataTypeDef = TypedDict(
     "SelectParametersResponseMetadataTypeDef",
     {
         "InputSerialization": InputSerializationTypeDef,
         "ExpressionType": Literal["SQL"],
         "Expression": str,
         "OutputSerialization": OutputSerializationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SelectParametersTypeDef = TypedDict(
     "SelectParametersTypeDef",
     {
         "InputSerialization": InputSerializationTypeDef,
@@ -1454,15 +1437,15 @@
     total=False,
 )
 
 GetDataRetrievalPolicyOutputTypeDef = TypedDict(
     "GetDataRetrievalPolicyOutputTypeDef",
     {
         "Policy": DataRetrievalPolicyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SetDataRetrievalPolicyInputRequestTypeDef = TypedDict(
     "SetDataRetrievalPolicyInputRequestTypeDef",
     {
         "accountId": str,
@@ -1486,15 +1469,15 @@
     total=False,
 )
 
 OutputLocationResponseMetadataTypeDef = TypedDict(
     "OutputLocationResponseMetadataTypeDef",
     {
         "S3": S3LocationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OutputLocationTypeDef = TypedDict(
     "OutputLocationTypeDef",
     {
         "S3": S3LocationTypeDef,
@@ -1522,15 +1505,15 @@
         "ArchiveSHA256TreeHash": str,
         "RetrievalByteRange": str,
         "Tier": str,
         "InventoryRetrievalParameters": InventoryRetrievalJobDescriptionTypeDef,
         "JobOutputPath": str,
         "SelectParameters": SelectParametersTypeDef,
         "OutputLocation": OutputLocationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GlacierJobDescriptionTypeDef = TypedDict(
     "GlacierJobDescriptionTypeDef",
     {
         "JobId": str,
@@ -1576,15 +1559,15 @@
 )
 
 ListJobsOutputTypeDef = TypedDict(
     "ListJobsOutputTypeDef",
     {
         "JobList": List[GlacierJobDescriptionTypeDef],
         "Marker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredInitiateJobInputRequestTypeDef = TypedDict(
     "_RequiredInitiateJobInputRequestTypeDef",
     {
         "vaultName": str,
@@ -1595,11 +1578,12 @@
     {
         "accountId": str,
         "jobParameters": JobParametersTypeDef,
     },
     total=False,
 )
 
+
 class InitiateJobInputRequestTypeDef(
     _RequiredInitiateJobInputRequestTypeDef, _OptionalInitiateJobInputRequestTypeDef
 ):
     pass
```

### Comparing `types-aiobotocore-glacier-2.5.0.post1/types_aiobotocore_glacier/waiter.py` & `types-aiobotocore-glacier-2.5.1/types_aiobotocore_glacier/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-glacier-2.5.0.post1/types_aiobotocore_glacier/waiter.pyi` & `types-aiobotocore-glacier-2.5.1/types_aiobotocore_glacier/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-glacier-2.5.0.post1/types_aiobotocore_glacier.egg-info/PKG-INFO` & `types-aiobotocore-glacier-2.5.1/types_aiobotocore_glacier.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-glacier
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Glacier 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Glacier 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glacier/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-glacier"></a>
 
 # types-aiobotocore-glacier
 
 [![PyPI - types-aiobotocore-glacier](https://img.shields.io/pypi/v/types-aiobotocore-glacier.svg?color=blue)](https://pypi.org/project/types-aiobotocore-glacier)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-glacier.svg?color=blue)](https://pypi.org/project/types-aiobotocore-glacier)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glacier/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-glacier?color=blue)](https://pypistats.org/packages/types-aiobotocore-glacier)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Glacier 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glacier.html#Glacier)
+[aiobotocore.Glacier 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glacier.html#Glacier)
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
 [types-aiobotocore-glacier docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glacier/).
 
 See how it helps to find and fix potential bugs:
 
@@ -442,105 +442,95 @@
 `types_aiobotocore_glacier.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_glacier.type_defs import (
     AbortMultipartUploadInputRequestTypeDef,
     AbortVaultLockInputRequestTypeDef,
-    AccountVaultRequestTypeDef,
     AddTagsToVaultInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    ArchiveCreationOutputTypeDef,
     CSVInputTypeDef,
     CSVOutputTypeDef,
     CompleteMultipartUploadInputMultipartUploadCompleteTypeDef,
     CompleteMultipartUploadInputRequestTypeDef,
     CompleteVaultLockInputRequestTypeDef,
     CreateVaultInputAccountCreateVaultTypeDef,
     CreateVaultInputRequestTypeDef,
     CreateVaultInputServiceResourceCreateVaultTypeDef,
+    CreateVaultOutputTypeDef,
     DataRetrievalRuleTypeDef,
     DeleteArchiveInputRequestTypeDef,
     DeleteVaultAccessPolicyInputRequestTypeDef,
     DeleteVaultInputRequestTypeDef,
     DeleteVaultNotificationsInputRequestTypeDef,
     DescribeJobInputRequestTypeDef,
     DescribeVaultInputRequestTypeDef,
     WaiterConfigTypeDef,
+    DescribeVaultOutputResponseMetadataTypeDef,
     DescribeVaultOutputTypeDef,
+    EmptyResponseMetadataTypeDef,
     EncryptionTypeDef,
     GetDataRetrievalPolicyInputRequestTypeDef,
     GetJobOutputInputJobGetOutputTypeDef,
     GetJobOutputInputRequestTypeDef,
+    GetJobOutputOutputTypeDef,
     GetVaultAccessPolicyInputRequestTypeDef,
     VaultAccessPolicyTypeDef,
     GetVaultLockInputRequestTypeDef,
+    GetVaultLockOutputTypeDef,
     GetVaultNotificationsInputRequestTypeDef,
     VaultNotificationConfigTypeDef,
     InventoryRetrievalJobDescriptionTypeDef,
     GranteeTypeDef,
+    InitiateJobOutputTypeDef,
     InitiateMultipartUploadInputRequestTypeDef,
     InitiateMultipartUploadInputVaultInitiateMultipartUploadTypeDef,
+    InitiateMultipartUploadOutputTypeDef,
     VaultLockPolicyTypeDef,
+    InitiateVaultLockOutputTypeDef,
+    InventoryRetrievalJobDescriptionResponseMetadataTypeDef,
     InventoryRetrievalJobInputTypeDef,
-    PaginatorConfigTypeDef,
+    ListJobsInputListJobsPaginateTypeDef,
     ListJobsInputRequestTypeDef,
+    ListMultipartUploadsInputListMultipartUploadsPaginateTypeDef,
     ListMultipartUploadsInputRequestTypeDef,
     UploadListElementTypeDef,
+    ListPartsInputListPartsPaginateTypeDef,
     ListPartsInputMultipartUploadPartsTypeDef,
     ListPartsInputRequestTypeDef,
     PartListElementTypeDef,
     ListProvisionedCapacityInputRequestTypeDef,
     ProvisionedCapacityDescriptionTypeDef,
     ListTagsForVaultInputRequestTypeDef,
+    ListTagsForVaultOutputTypeDef,
+    ListVaultsInputListVaultsPaginateTypeDef,
     ListVaultsInputRequestTypeDef,
+    PaginatorConfigTypeDef,
     PurchaseProvisionedCapacityInputRequestTypeDef,
+    PurchaseProvisionedCapacityOutputTypeDef,
     RemoveTagsFromVaultInputRequestTypeDef,
-    ServiceResourceAccountRequestTypeDef,
-    ServiceResourceArchiveRequestTypeDef,
-    ServiceResourceJobRequestTypeDef,
-    ServiceResourceMultipartUploadRequestTypeDef,
-    ServiceResourceNotificationRequestTypeDef,
-    ServiceResourceVaultRequestTypeDef,
+    ResponseMetadataTypeDef,
     UploadArchiveInputRequestTypeDef,
     UploadArchiveInputVaultUploadArchiveTypeDef,
     UploadMultipartPartInputMultipartUploadUploadPartTypeDef,
     UploadMultipartPartInputRequestTypeDef,
-    VaultArchiveRequestTypeDef,
-    VaultJobRequestTypeDef,
-    VaultMultipartUploadRequestTypeDef,
-    ArchiveCreationOutputTypeDef,
-    CreateVaultOutputTypeDef,
-    DescribeVaultOutputResponseMetadataTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetJobOutputOutputTypeDef,
-    GetVaultLockOutputTypeDef,
-    InitiateJobOutputTypeDef,
-    InitiateMultipartUploadOutputTypeDef,
-    InitiateVaultLockOutputTypeDef,
-    InventoryRetrievalJobDescriptionResponseMetadataTypeDef,
-    ListTagsForVaultOutputTypeDef,
-    PurchaseProvisionedCapacityOutputTypeDef,
     UploadMultipartPartOutputTypeDef,
     InputSerializationTypeDef,
     OutputSerializationTypeDef,
     DataRetrievalPolicyTypeDef,
     DescribeVaultInputVaultExistsWaitTypeDef,
     DescribeVaultInputVaultNotExistsWaitTypeDef,
     ListVaultsOutputTypeDef,
     GetVaultAccessPolicyOutputTypeDef,
     SetVaultAccessPolicyInputRequestTypeDef,
     GetVaultNotificationsOutputTypeDef,
     SetVaultNotificationsInputNotificationSetTypeDef,
     SetVaultNotificationsInputRequestTypeDef,
     GrantTypeDef,
     InitiateVaultLockInputRequestTypeDef,
-    ListJobsInputListJobsPaginateTypeDef,
-    ListMultipartUploadsInputListMultipartUploadsPaginateTypeDef,
-    ListPartsInputListPartsPaginateTypeDef,
-    ListVaultsInputListVaultsPaginateTypeDef,
     ListMultipartUploadsOutputTypeDef,
     ListPartsOutputTypeDef,
     ListProvisionedCapacityOutputTypeDef,
     SelectParametersResponseMetadataTypeDef,
     SelectParametersTypeDef,
     GetDataRetrievalPolicyOutputTypeDef,
     SetDataRetrievalPolicyInputRequestTypeDef,
@@ -562,43 +552,43 @@
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

### Comparing `types-aiobotocore-glacier-2.5.0.post1/types_aiobotocore_glacier.egg-info/SOURCES.txt` & `types-aiobotocore-glacier-2.5.1/types_aiobotocore_glacier.egg-info/SOURCES.txt`

 * *Files identical despite different names*

