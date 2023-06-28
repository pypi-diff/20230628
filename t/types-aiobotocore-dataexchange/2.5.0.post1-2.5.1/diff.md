# Comparing `tmp/types-aiobotocore-dataexchange-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-dataexchange-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-dataexchange-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:29 2023, max compression
+gzip compressed data, was "types-aiobotocore-dataexchange-2.5.1.tar", last modified: Wed Jun 28 01:43:21 2023, max compression
```

## Comparing `types-aiobotocore-dataexchange-2.5.0.post1.tar` & `types-aiobotocore-dataexchange-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:29.291118 types-aiobotocore-dataexchange-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:12:10.000000 types-aiobotocore-dataexchange-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    18492 2023-03-11 12:26:29.291118 types-aiobotocore-dataexchange-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    16901 2023-03-11 12:12:10.000000 types-aiobotocore-dataexchange-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:29.291118 types-aiobotocore-dataexchange-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2159 2023-03-11 12:12:10.000000 types-aiobotocore-dataexchange-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:29.283118 types-aiobotocore-dataexchange-2.5.0.post1/types_aiobotocore_dataexchange/
--rw-r--r--   0 runner    (1001) docker     (123)     1505 2023-03-11 12:12:10.000000 types-aiobotocore-dataexchange-2.5.0.post1/types_aiobotocore_dataexchange/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1504 2023-03-11 12:12:10.000000 types-aiobotocore-dataexchange-2.5.0.post1/types_aiobotocore_dataexchange/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      963 2023-03-11 12:12:10.000000 types-aiobotocore-dataexchange-2.5.0.post1/types_aiobotocore_dataexchange/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    23279 2023-03-11 12:12:10.000000 types-aiobotocore-dataexchange-2.5.0.post1/types_aiobotocore_dataexchange/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    23236 2023-03-11 12:12:10.000000 types-aiobotocore-dataexchange-2.5.0.post1/types_aiobotocore_dataexchange/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10220 2023-03-11 12:12:11.000000 types-aiobotocore-dataexchange-2.5.0.post1/types_aiobotocore_dataexchange/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    10218 2023-03-11 12:12:11.000000 types-aiobotocore-dataexchange-2.5.0.post1/types_aiobotocore_dataexchange/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     6764 2023-03-11 12:12:10.000000 types-aiobotocore-dataexchange-2.5.0.post1/types_aiobotocore_dataexchange/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     6756 2023-03-11 12:12:10.000000 types-aiobotocore-dataexchange-2.5.0.post1/types_aiobotocore_dataexchange/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:12:10.000000 types-aiobotocore-dataexchange-2.5.0.post1/types_aiobotocore_dataexchange/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    44934 2023-03-11 12:12:12.000000 types-aiobotocore-dataexchange-2.5.0.post1/types_aiobotocore_dataexchange/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    44867 2023-03-11 12:12:11.000000 types-aiobotocore-dataexchange-2.5.0.post1/types_aiobotocore_dataexchange/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:12:10.000000 types-aiobotocore-dataexchange-2.5.0.post1/types_aiobotocore_dataexchange/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:29.291118 types-aiobotocore-dataexchange-2.5.0.post1/types_aiobotocore_dataexchange.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    18492 2023-03-11 12:26:29.000000 types-aiobotocore-dataexchange-2.5.0.post1/types_aiobotocore_dataexchange.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      908 2023-03-11 12:26:29.000000 types-aiobotocore-dataexchange-2.5.0.post1/types_aiobotocore_dataexchange.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:29.000000 types-aiobotocore-dataexchange-2.5.0.post1/types_aiobotocore_dataexchange.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:29.000000 types-aiobotocore-dataexchange-2.5.0.post1/types_aiobotocore_dataexchange.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:29.000000 types-aiobotocore-dataexchange-2.5.0.post1/types_aiobotocore_dataexchange.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       31 2023-03-11 12:26:29.000000 types-aiobotocore-dataexchange-2.5.0.post1/types_aiobotocore_dataexchange.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:21.598122 types-aiobotocore-dataexchange-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:28:49.000000 types-aiobotocore-dataexchange-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    18515 2023-06-28 01:43:21.594122 types-aiobotocore-dataexchange-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    16930 2023-06-28 01:28:49.000000 types-aiobotocore-dataexchange-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:21.598122 types-aiobotocore-dataexchange-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2153 2023-06-28 01:28:49.000000 types-aiobotocore-dataexchange-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:21.594122 types-aiobotocore-dataexchange-2.5.1/types_aiobotocore_dataexchange/
+-rw-r--r--   0 runner    (1001) docker     (123)     1505 2023-06-28 01:28:49.000000 types-aiobotocore-dataexchange-2.5.1/types_aiobotocore_dataexchange/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1504 2023-06-28 01:28:49.000000 types-aiobotocore-dataexchange-2.5.1/types_aiobotocore_dataexchange/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      951 2023-06-28 01:28:49.000000 types-aiobotocore-dataexchange-2.5.1/types_aiobotocore_dataexchange/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23279 2023-06-28 01:28:49.000000 types-aiobotocore-dataexchange-2.5.1/types_aiobotocore_dataexchange/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23236 2023-06-28 01:28:49.000000 types-aiobotocore-dataexchange-2.5.1/types_aiobotocore_dataexchange/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10429 2023-06-28 01:28:50.000000 types-aiobotocore-dataexchange-2.5.1/types_aiobotocore_dataexchange/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10427 2023-06-28 01:28:49.000000 types-aiobotocore-dataexchange-2.5.1/types_aiobotocore_dataexchange/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     6654 2023-06-28 01:28:49.000000 types-aiobotocore-dataexchange-2.5.1/types_aiobotocore_dataexchange/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6647 2023-06-28 01:28:49.000000 types-aiobotocore-dataexchange-2.5.1/types_aiobotocore_dataexchange/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:28:49.000000 types-aiobotocore-dataexchange-2.5.1/types_aiobotocore_dataexchange/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    45232 2023-06-28 01:28:50.000000 types-aiobotocore-dataexchange-2.5.1/types_aiobotocore_dataexchange/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    45165 2023-06-28 01:28:50.000000 types-aiobotocore-dataexchange-2.5.1/types_aiobotocore_dataexchange/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:28:49.000000 types-aiobotocore-dataexchange-2.5.1/types_aiobotocore_dataexchange/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:21.594122 types-aiobotocore-dataexchange-2.5.1/types_aiobotocore_dataexchange.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    18515 2023-06-28 01:43:21.000000 types-aiobotocore-dataexchange-2.5.1/types_aiobotocore_dataexchange.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      908 2023-06-28 01:43:21.000000 types-aiobotocore-dataexchange-2.5.1/types_aiobotocore_dataexchange.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:21.000000 types-aiobotocore-dataexchange-2.5.1/types_aiobotocore_dataexchange.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:21.000000 types-aiobotocore-dataexchange-2.5.1/types_aiobotocore_dataexchange.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:21.000000 types-aiobotocore-dataexchange-2.5.1/types_aiobotocore_dataexchange.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       31 2023-06-28 01:43:21.000000 types-aiobotocore-dataexchange-2.5.1/types_aiobotocore_dataexchange.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-dataexchange-2.5.0.post1/LICENSE` & `types-aiobotocore-dataexchange-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-dataexchange-2.5.0.post1/PKG-INFO` & `types-aiobotocore-dataexchange-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-dataexchange
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.DataExchange 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.DataExchange 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dataexchange/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-dataexchange"></a>
 
 # types-aiobotocore-dataexchange
 
 [![PyPI - types-aiobotocore-dataexchange](https://img.shields.io/pypi/v/types-aiobotocore-dataexchange.svg?color=blue)](https://pypi.org/project/types-aiobotocore-dataexchange)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-dataexchange.svg?color=blue)](https://pypi.org/project/types-aiobotocore-dataexchange)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dataexchange/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-dataexchange?color=blue)](https://pypistats.org/packages/types-aiobotocore-dataexchange)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.DataExchange 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dataexchange.html#DataExchange)
+[aiobotocore.DataExchange 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dataexchange.html#DataExchange)
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
 [types-aiobotocore-dataexchange docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dataexchange/).
 
 See how it helps to find and fix potential bugs:
 
@@ -351,118 +351,119 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_dataexchange.type_defs import (
     ApiGatewayApiAssetTypeDef,
     AssetDestinationEntryTypeDef,
     RedshiftDataShareAssetTypeDef,
-    S3DataAccessAssetTypeDef,
     S3SnapshotAssetTypeDef,
     AssetSourceEntryTypeDef,
     AutoExportRevisionDestinationEntryTypeDef,
     ExportServerSideEncryptionTypeDef,
     CancelJobRequestRequestTypeDef,
     CreateDataSetRequestRequestTypeDef,
     OriginDetailsTypeDef,
-    ResponseMetadataTypeDef,
     CreateRevisionRequestRequestTypeDef,
-    S3DataAccessAssetSourceEntryTypeDef,
+    CreateRevisionResponseTypeDef,
     LFTagTypeDef,
     DeleteAssetRequestRequestTypeDef,
     DeleteDataSetRequestRequestTypeDef,
     DeleteEventActionRequestRequestTypeDef,
     DeleteRevisionRequestRequestTypeDef,
     ImportAssetFromSignedUrlJobErrorDetailsTypeDef,
+    EmptyResponseMetadataTypeDef,
     RevisionPublishedTypeDef,
     ExportAssetToSignedUrlRequestDetailsTypeDef,
     ExportAssetToSignedUrlResponseDetailsTypeDef,
     RevisionDestinationEntryTypeDef,
     GetAssetRequestRequestTypeDef,
     GetDataSetRequestRequestTypeDef,
     GetEventActionRequestRequestTypeDef,
     GetJobRequestRequestTypeDef,
     GetRevisionRequestRequestTypeDef,
+    GetRevisionResponseTypeDef,
     ImportAssetFromApiGatewayApiRequestDetailsTypeDef,
     ImportAssetFromApiGatewayApiResponseDetailsTypeDef,
     ImportAssetFromSignedUrlRequestDetailsTypeDef,
     ImportAssetFromSignedUrlResponseDetailsTypeDef,
     RedshiftDataShareAssetSourceEntryTypeDef,
-    PaginatorConfigTypeDef,
+    KmsKeyToGrantTypeDef,
+    ListDataSetRevisionsRequestListDataSetRevisionsPaginateTypeDef,
     ListDataSetRevisionsRequestRequestTypeDef,
     RevisionEntryTypeDef,
+    ListDataSetsRequestListDataSetsPaginateTypeDef,
     ListDataSetsRequestRequestTypeDef,
+    ListEventActionsRequestListEventActionsPaginateTypeDef,
     ListEventActionsRequestRequestTypeDef,
+    ListJobsRequestListJobsPaginateTypeDef,
     ListJobsRequestRequestTypeDef,
+    ListRevisionAssetsRequestListRevisionAssetsPaginateTypeDef,
     ListRevisionAssetsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     RevokeRevisionRequestRequestTypeDef,
+    RevokeRevisionResponseTypeDef,
     SendApiAssetRequestRequestTypeDef,
+    SendApiAssetResponseTypeDef,
     StartJobRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateAssetRequestRequestTypeDef,
     UpdateDataSetRequestRequestTypeDef,
     UpdateRevisionRequestRequestTypeDef,
+    UpdateRevisionResponseTypeDef,
     ImportAssetsFromS3RequestDetailsTypeDef,
     ImportAssetsFromS3ResponseDetailsTypeDef,
     AutoExportRevisionToS3RequestDetailsTypeDef,
     ExportAssetsToS3RequestDetailsTypeDef,
     ExportAssetsToS3ResponseDetailsTypeDef,
-    DataSetEntryTypeDef,
     CreateDataSetResponseTypeDef,
-    CreateRevisionResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
+    DataSetEntryTypeDef,
     GetDataSetResponseTypeDef,
-    GetRevisionResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    RevokeRevisionResponseTypeDef,
-    SendApiAssetResponseTypeDef,
     UpdateDataSetResponseTypeDef,
-    UpdateRevisionResponseTypeDef,
-    CreateS3DataAccessFromS3BucketRequestDetailsTypeDef,
-    CreateS3DataAccessFromS3BucketResponseDetailsTypeDef,
     DatabaseLFTagPolicyAndPermissionsTypeDef,
     DatabaseLFTagPolicyTypeDef,
     TableLFTagPolicyAndPermissionsTypeDef,
     TableLFTagPolicyTypeDef,
     DetailsTypeDef,
     EventTypeDef,
     ExportRevisionsToS3RequestDetailsTypeDef,
     ExportRevisionsToS3ResponseDetailsTypeDef,
     ImportAssetsFromRedshiftDataSharesRequestDetailsTypeDef,
     ImportAssetsFromRedshiftDataSharesResponseDetailsTypeDef,
-    ListDataSetRevisionsRequestListDataSetRevisionsPaginateTypeDef,
-    ListDataSetsRequestListDataSetsPaginateTypeDef,
-    ListEventActionsRequestListEventActionsPaginateTypeDef,
-    ListJobsRequestListJobsPaginateTypeDef,
-    ListRevisionAssetsRequestListRevisionAssetsPaginateTypeDef,
+    S3DataAccessAssetSourceEntryTypeDef,
+    S3DataAccessAssetTypeDef,
     ListDataSetRevisionsResponseTypeDef,
     ActionTypeDef,
     ListDataSetsResponseTypeDef,
     ImportAssetsFromLakeFormationTagPolicyRequestDetailsTypeDef,
     ImportAssetsFromLakeFormationTagPolicyResponseDetailsTypeDef,
     LFResourceDetailsTypeDef,
     JobErrorTypeDef,
+    CreateS3DataAccessFromS3BucketRequestDetailsTypeDef,
+    CreateS3DataAccessFromS3BucketResponseDetailsTypeDef,
     CreateEventActionRequestRequestTypeDef,
     CreateEventActionResponseTypeDef,
     EventActionEntryTypeDef,
     GetEventActionResponseTypeDef,
     UpdateEventActionRequestRequestTypeDef,
     UpdateEventActionResponseTypeDef,
+    LFTagPolicyDetailsTypeDef,
     RequestDetailsTypeDef,
     ResponseDetailsTypeDef,
-    LFTagPolicyDetailsTypeDef,
     ListEventActionsResponseTypeDef,
+    LakeFormationDataPermissionDetailsTypeDef,
     CreateJobRequestRequestTypeDef,
     CreateJobResponseTypeDef,
     GetJobResponseTypeDef,
     JobEntryTypeDef,
-    LakeFormationDataPermissionDetailsTypeDef,
-    ListJobsResponseTypeDef,
     LakeFormationDataPermissionAssetTypeDef,
+    ListJobsResponseTypeDef,
     AssetDetailsTypeDef,
     AssetEntryTypeDef,
     GetAssetResponseTypeDef,
     UpdateAssetResponseTypeDef,
     ListRevisionAssetsResponseTypeDef,
 )
 
@@ -474,43 +475,43 @@
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

### Comparing `types-aiobotocore-dataexchange-2.5.0.post1/README.md` & `types-aiobotocore-dataexchange-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-dataexchange"></a>
 
 # types-aiobotocore-dataexchange
 
 [![PyPI - types-aiobotocore-dataexchange](https://img.shields.io/pypi/v/types-aiobotocore-dataexchange.svg?color=blue)](https://pypi.org/project/types-aiobotocore-dataexchange)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-dataexchange.svg?color=blue)](https://pypi.org/project/types-aiobotocore-dataexchange)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dataexchange/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-dataexchange?color=blue)](https://pypistats.org/packages/types-aiobotocore-dataexchange)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.DataExchange 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dataexchange.html#DataExchange)
+[aiobotocore.DataExchange 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dataexchange.html#DataExchange)
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
 [types-aiobotocore-dataexchange docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dataexchange/).
 
 See how it helps to find and fix potential bugs:
 
@@ -318,118 +318,119 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_dataexchange.type_defs import (
     ApiGatewayApiAssetTypeDef,
     AssetDestinationEntryTypeDef,
     RedshiftDataShareAssetTypeDef,
-    S3DataAccessAssetTypeDef,
     S3SnapshotAssetTypeDef,
     AssetSourceEntryTypeDef,
     AutoExportRevisionDestinationEntryTypeDef,
     ExportServerSideEncryptionTypeDef,
     CancelJobRequestRequestTypeDef,
     CreateDataSetRequestRequestTypeDef,
     OriginDetailsTypeDef,
-    ResponseMetadataTypeDef,
     CreateRevisionRequestRequestTypeDef,
-    S3DataAccessAssetSourceEntryTypeDef,
+    CreateRevisionResponseTypeDef,
     LFTagTypeDef,
     DeleteAssetRequestRequestTypeDef,
     DeleteDataSetRequestRequestTypeDef,
     DeleteEventActionRequestRequestTypeDef,
     DeleteRevisionRequestRequestTypeDef,
     ImportAssetFromSignedUrlJobErrorDetailsTypeDef,
+    EmptyResponseMetadataTypeDef,
     RevisionPublishedTypeDef,
     ExportAssetToSignedUrlRequestDetailsTypeDef,
     ExportAssetToSignedUrlResponseDetailsTypeDef,
     RevisionDestinationEntryTypeDef,
     GetAssetRequestRequestTypeDef,
     GetDataSetRequestRequestTypeDef,
     GetEventActionRequestRequestTypeDef,
     GetJobRequestRequestTypeDef,
     GetRevisionRequestRequestTypeDef,
+    GetRevisionResponseTypeDef,
     ImportAssetFromApiGatewayApiRequestDetailsTypeDef,
     ImportAssetFromApiGatewayApiResponseDetailsTypeDef,
     ImportAssetFromSignedUrlRequestDetailsTypeDef,
     ImportAssetFromSignedUrlResponseDetailsTypeDef,
     RedshiftDataShareAssetSourceEntryTypeDef,
-    PaginatorConfigTypeDef,
+    KmsKeyToGrantTypeDef,
+    ListDataSetRevisionsRequestListDataSetRevisionsPaginateTypeDef,
     ListDataSetRevisionsRequestRequestTypeDef,
     RevisionEntryTypeDef,
+    ListDataSetsRequestListDataSetsPaginateTypeDef,
     ListDataSetsRequestRequestTypeDef,
+    ListEventActionsRequestListEventActionsPaginateTypeDef,
     ListEventActionsRequestRequestTypeDef,
+    ListJobsRequestListJobsPaginateTypeDef,
     ListJobsRequestRequestTypeDef,
+    ListRevisionAssetsRequestListRevisionAssetsPaginateTypeDef,
     ListRevisionAssetsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     RevokeRevisionRequestRequestTypeDef,
+    RevokeRevisionResponseTypeDef,
     SendApiAssetRequestRequestTypeDef,
+    SendApiAssetResponseTypeDef,
     StartJobRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateAssetRequestRequestTypeDef,
     UpdateDataSetRequestRequestTypeDef,
     UpdateRevisionRequestRequestTypeDef,
+    UpdateRevisionResponseTypeDef,
     ImportAssetsFromS3RequestDetailsTypeDef,
     ImportAssetsFromS3ResponseDetailsTypeDef,
     AutoExportRevisionToS3RequestDetailsTypeDef,
     ExportAssetsToS3RequestDetailsTypeDef,
     ExportAssetsToS3ResponseDetailsTypeDef,
-    DataSetEntryTypeDef,
     CreateDataSetResponseTypeDef,
-    CreateRevisionResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
+    DataSetEntryTypeDef,
     GetDataSetResponseTypeDef,
-    GetRevisionResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    RevokeRevisionResponseTypeDef,
-    SendApiAssetResponseTypeDef,
     UpdateDataSetResponseTypeDef,
-    UpdateRevisionResponseTypeDef,
-    CreateS3DataAccessFromS3BucketRequestDetailsTypeDef,
-    CreateS3DataAccessFromS3BucketResponseDetailsTypeDef,
     DatabaseLFTagPolicyAndPermissionsTypeDef,
     DatabaseLFTagPolicyTypeDef,
     TableLFTagPolicyAndPermissionsTypeDef,
     TableLFTagPolicyTypeDef,
     DetailsTypeDef,
     EventTypeDef,
     ExportRevisionsToS3RequestDetailsTypeDef,
     ExportRevisionsToS3ResponseDetailsTypeDef,
     ImportAssetsFromRedshiftDataSharesRequestDetailsTypeDef,
     ImportAssetsFromRedshiftDataSharesResponseDetailsTypeDef,
-    ListDataSetRevisionsRequestListDataSetRevisionsPaginateTypeDef,
-    ListDataSetsRequestListDataSetsPaginateTypeDef,
-    ListEventActionsRequestListEventActionsPaginateTypeDef,
-    ListJobsRequestListJobsPaginateTypeDef,
-    ListRevisionAssetsRequestListRevisionAssetsPaginateTypeDef,
+    S3DataAccessAssetSourceEntryTypeDef,
+    S3DataAccessAssetTypeDef,
     ListDataSetRevisionsResponseTypeDef,
     ActionTypeDef,
     ListDataSetsResponseTypeDef,
     ImportAssetsFromLakeFormationTagPolicyRequestDetailsTypeDef,
     ImportAssetsFromLakeFormationTagPolicyResponseDetailsTypeDef,
     LFResourceDetailsTypeDef,
     JobErrorTypeDef,
+    CreateS3DataAccessFromS3BucketRequestDetailsTypeDef,
+    CreateS3DataAccessFromS3BucketResponseDetailsTypeDef,
     CreateEventActionRequestRequestTypeDef,
     CreateEventActionResponseTypeDef,
     EventActionEntryTypeDef,
     GetEventActionResponseTypeDef,
     UpdateEventActionRequestRequestTypeDef,
     UpdateEventActionResponseTypeDef,
+    LFTagPolicyDetailsTypeDef,
     RequestDetailsTypeDef,
     ResponseDetailsTypeDef,
-    LFTagPolicyDetailsTypeDef,
     ListEventActionsResponseTypeDef,
+    LakeFormationDataPermissionDetailsTypeDef,
     CreateJobRequestRequestTypeDef,
     CreateJobResponseTypeDef,
     GetJobResponseTypeDef,
     JobEntryTypeDef,
-    LakeFormationDataPermissionDetailsTypeDef,
-    ListJobsResponseTypeDef,
     LakeFormationDataPermissionAssetTypeDef,
+    ListJobsResponseTypeDef,
     AssetDetailsTypeDef,
     AssetEntryTypeDef,
     GetAssetResponseTypeDef,
     UpdateAssetResponseTypeDef,
     ListRevisionAssetsResponseTypeDef,
 )
 
@@ -441,43 +442,43 @@
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

### Comparing `types-aiobotocore-dataexchange-2.5.0.post1/setup.py` & `types-aiobotocore-dataexchange-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-dataexchange.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-dataexchange",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_dataexchange"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.DataExchange 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.DataExchange 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dataexchange/"
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

### Comparing `types-aiobotocore-dataexchange-2.5.0.post1/types_aiobotocore_dataexchange/__init__.py` & `types-aiobotocore-dataexchange-2.5.1/types_aiobotocore_dataexchange/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-dataexchange-2.5.0.post1/types_aiobotocore_dataexchange/__init__.pyi` & `types-aiobotocore-dataexchange-2.5.1/types_aiobotocore_dataexchange/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-dataexchange-2.5.0.post1/types_aiobotocore_dataexchange/__main__.py` & `types-aiobotocore-dataexchange-2.5.1/types_aiobotocore_dataexchange/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.DataExchange 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.DataExchange 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dataexchange//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dataexchange.html#DataExchange\nOther"
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

### Comparing `types-aiobotocore-dataexchange-2.5.0.post1/types_aiobotocore_dataexchange/client.py` & `types-aiobotocore-dataexchange-2.5.1/types_aiobotocore_dataexchange/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-dataexchange-2.5.0.post1/types_aiobotocore_dataexchange/client.pyi` & `types-aiobotocore-dataexchange-2.5.1/types_aiobotocore_dataexchange/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-dataexchange-2.5.0.post1/types_aiobotocore_dataexchange/literals.py` & `types-aiobotocore-dataexchange-2.5.1/types_aiobotocore_dataexchange/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -155,14 +155,15 @@
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
@@ -241,14 +242,15 @@
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
@@ -259,14 +261,15 @@
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
@@ -302,14 +305,15 @@
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
@@ -328,16 +332,19 @@
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
@@ -421,15 +428,17 @@
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

### Comparing `types-aiobotocore-dataexchange-2.5.0.post1/types_aiobotocore_dataexchange/literals.pyi` & `types-aiobotocore-dataexchange-2.5.1/types_aiobotocore_dataexchange/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -153,14 +153,15 @@
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
@@ -239,14 +240,15 @@
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
@@ -257,14 +259,15 @@
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
@@ -300,14 +303,15 @@
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
@@ -326,16 +330,19 @@
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
@@ -419,15 +426,17 @@
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

### Comparing `types-aiobotocore-dataexchange-2.5.0.post1/types_aiobotocore_dataexchange/paginator.py` & `types-aiobotocore-dataexchange-2.5.1/types_aiobotocore_dataexchange/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -24,35 +24,28 @@
         list_data_set_revisions_paginator: ListDataSetRevisionsPaginator = client.get_paginator("list_data_set_revisions")
         list_data_sets_paginator: ListDataSetsPaginator = client.get_paginator("list_data_sets")
         list_event_actions_paginator: ListEventActionsPaginator = client.get_paginator("list_event_actions")
         list_jobs_paginator: ListJobsPaginator = client.get_paginator("list_jobs")
         list_revision_assets_paginator: ListRevisionAssetsPaginator = client.get_paginator("list_revision_assets")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListDataSetRevisionsResponseTypeDef,
     ListDataSetsResponseTypeDef,
     ListEventActionsResponseTypeDef,
     ListJobsResponseTypeDef,
     ListRevisionAssetsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListDataSetRevisionsPaginator",
     "ListDataSetsPaginator",
     "ListEventActionsPaginator",
     "ListJobsPaginator",
     "ListRevisionAssetsPaginator",
 )
@@ -71,45 +64,45 @@
 class ListDataSetRevisionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dataexchange.html#DataExchange.Paginator.ListDataSetRevisions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dataexchange/paginators/#listdatasetrevisionspaginator)
     """
 
     def paginate(
-        self, *, DataSetId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, DataSetId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDataSetRevisionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dataexchange.html#DataExchange.Paginator.ListDataSetRevisions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dataexchange/paginators/#listdatasetrevisionspaginator)
         """
 
 
 class ListDataSetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dataexchange.html#DataExchange.Paginator.ListDataSets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dataexchange/paginators/#listdatasetspaginator)
     """
 
     def paginate(
-        self, *, Origin: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Origin: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDataSetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dataexchange.html#DataExchange.Paginator.ListDataSets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dataexchange/paginators/#listdatasetspaginator)
         """
 
 
 class ListEventActionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dataexchange.html#DataExchange.Paginator.ListEventActions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dataexchange/paginators/#listeventactionspaginator)
     """
 
     def paginate(
-        self, *, EventSourceId: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, EventSourceId: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEventActionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dataexchange.html#DataExchange.Paginator.ListEventActions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dataexchange/paginators/#listeventactionspaginator)
         """
 
 
@@ -120,28 +113,28 @@
     """
 
     def paginate(
         self,
         *,
         DataSetId: str = ...,
         RevisionId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dataexchange.html#DataExchange.Paginator.ListJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dataexchange/paginators/#listjobspaginator)
         """
 
 
 class ListRevisionAssetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dataexchange.html#DataExchange.Paginator.ListRevisionAssets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dataexchange/paginators/#listrevisionassetspaginator)
     """
 
     def paginate(
-        self, *, DataSetId: str, RevisionId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, DataSetId: str, RevisionId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRevisionAssetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dataexchange.html#DataExchange.Paginator.ListRevisionAssets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dataexchange/paginators/#listrevisionassetspaginator)
         """
```

### Comparing `types-aiobotocore-dataexchange-2.5.0.post1/types_aiobotocore_dataexchange/paginator.pyi` & `types-aiobotocore-dataexchange-2.5.1/types_aiobotocore_dataexchange/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -24,34 +24,28 @@
         list_data_set_revisions_paginator: ListDataSetRevisionsPaginator = client.get_paginator("list_data_set_revisions")
         list_data_sets_paginator: ListDataSetsPaginator = client.get_paginator("list_data_sets")
         list_event_actions_paginator: ListEventActionsPaginator = client.get_paginator("list_event_actions")
         list_jobs_paginator: ListJobsPaginator = client.get_paginator("list_jobs")
         list_revision_assets_paginator: ListRevisionAssetsPaginator = client.get_paginator("list_revision_assets")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListDataSetRevisionsResponseTypeDef,
     ListDataSetsResponseTypeDef,
     ListEventActionsResponseTypeDef,
     ListJobsResponseTypeDef,
     ListRevisionAssetsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListDataSetRevisionsPaginator",
     "ListDataSetsPaginator",
     "ListEventActionsPaginator",
     "ListJobsPaginator",
     "ListRevisionAssetsPaginator",
 )
@@ -67,43 +61,43 @@
 class ListDataSetRevisionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dataexchange.html#DataExchange.Paginator.ListDataSetRevisions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dataexchange/paginators/#listdatasetrevisionspaginator)
     """
 
     def paginate(
-        self, *, DataSetId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, DataSetId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDataSetRevisionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dataexchange.html#DataExchange.Paginator.ListDataSetRevisions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dataexchange/paginators/#listdatasetrevisionspaginator)
         """
 
 class ListDataSetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dataexchange.html#DataExchange.Paginator.ListDataSets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dataexchange/paginators/#listdatasetspaginator)
     """
 
     def paginate(
-        self, *, Origin: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Origin: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDataSetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dataexchange.html#DataExchange.Paginator.ListDataSets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dataexchange/paginators/#listdatasetspaginator)
         """
 
 class ListEventActionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dataexchange.html#DataExchange.Paginator.ListEventActions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dataexchange/paginators/#listeventactionspaginator)
     """
 
     def paginate(
-        self, *, EventSourceId: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, EventSourceId: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEventActionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dataexchange.html#DataExchange.Paginator.ListEventActions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dataexchange/paginators/#listeventactionspaginator)
         """
 
 class ListJobsPaginator(AioPaginator):
@@ -113,27 +107,27 @@
     """
 
     def paginate(
         self,
         *,
         DataSetId: str = ...,
         RevisionId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dataexchange.html#DataExchange.Paginator.ListJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dataexchange/paginators/#listjobspaginator)
         """
 
 class ListRevisionAssetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dataexchange.html#DataExchange.Paginator.ListRevisionAssets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dataexchange/paginators/#listrevisionassetspaginator)
     """
 
     def paginate(
-        self, *, DataSetId: str, RevisionId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, DataSetId: str, RevisionId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRevisionAssetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dataexchange.html#DataExchange.Paginator.ListRevisionAssets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dataexchange/paginators/#listrevisionassetspaginator)
         """
```

### Comparing `types-aiobotocore-dataexchange-2.5.0.post1/types_aiobotocore_dataexchange/type_defs.py` & `types-aiobotocore-dataexchange-2.5.1/types_aiobotocore_dataexchange/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -39,118 +39,119 @@
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "ApiGatewayApiAssetTypeDef",
     "AssetDestinationEntryTypeDef",
     "RedshiftDataShareAssetTypeDef",
-    "S3DataAccessAssetTypeDef",
     "S3SnapshotAssetTypeDef",
     "AssetSourceEntryTypeDef",
     "AutoExportRevisionDestinationEntryTypeDef",
     "ExportServerSideEncryptionTypeDef",
     "CancelJobRequestRequestTypeDef",
     "CreateDataSetRequestRequestTypeDef",
     "OriginDetailsTypeDef",
-    "ResponseMetadataTypeDef",
     "CreateRevisionRequestRequestTypeDef",
-    "S3DataAccessAssetSourceEntryTypeDef",
+    "CreateRevisionResponseTypeDef",
     "LFTagTypeDef",
     "DeleteAssetRequestRequestTypeDef",
     "DeleteDataSetRequestRequestTypeDef",
     "DeleteEventActionRequestRequestTypeDef",
     "DeleteRevisionRequestRequestTypeDef",
     "ImportAssetFromSignedUrlJobErrorDetailsTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "RevisionPublishedTypeDef",
     "ExportAssetToSignedUrlRequestDetailsTypeDef",
     "ExportAssetToSignedUrlResponseDetailsTypeDef",
     "RevisionDestinationEntryTypeDef",
     "GetAssetRequestRequestTypeDef",
     "GetDataSetRequestRequestTypeDef",
     "GetEventActionRequestRequestTypeDef",
     "GetJobRequestRequestTypeDef",
     "GetRevisionRequestRequestTypeDef",
+    "GetRevisionResponseTypeDef",
     "ImportAssetFromApiGatewayApiRequestDetailsTypeDef",
     "ImportAssetFromApiGatewayApiResponseDetailsTypeDef",
     "ImportAssetFromSignedUrlRequestDetailsTypeDef",
     "ImportAssetFromSignedUrlResponseDetailsTypeDef",
     "RedshiftDataShareAssetSourceEntryTypeDef",
-    "PaginatorConfigTypeDef",
+    "KmsKeyToGrantTypeDef",
+    "ListDataSetRevisionsRequestListDataSetRevisionsPaginateTypeDef",
     "ListDataSetRevisionsRequestRequestTypeDef",
     "RevisionEntryTypeDef",
+    "ListDataSetsRequestListDataSetsPaginateTypeDef",
     "ListDataSetsRequestRequestTypeDef",
+    "ListEventActionsRequestListEventActionsPaginateTypeDef",
     "ListEventActionsRequestRequestTypeDef",
+    "ListJobsRequestListJobsPaginateTypeDef",
     "ListJobsRequestRequestTypeDef",
+    "ListRevisionAssetsRequestListRevisionAssetsPaginateTypeDef",
     "ListRevisionAssetsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "RevokeRevisionRequestRequestTypeDef",
+    "RevokeRevisionResponseTypeDef",
     "SendApiAssetRequestRequestTypeDef",
+    "SendApiAssetResponseTypeDef",
     "StartJobRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateAssetRequestRequestTypeDef",
     "UpdateDataSetRequestRequestTypeDef",
     "UpdateRevisionRequestRequestTypeDef",
+    "UpdateRevisionResponseTypeDef",
     "ImportAssetsFromS3RequestDetailsTypeDef",
     "ImportAssetsFromS3ResponseDetailsTypeDef",
     "AutoExportRevisionToS3RequestDetailsTypeDef",
     "ExportAssetsToS3RequestDetailsTypeDef",
     "ExportAssetsToS3ResponseDetailsTypeDef",
-    "DataSetEntryTypeDef",
     "CreateDataSetResponseTypeDef",
-    "CreateRevisionResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
+    "DataSetEntryTypeDef",
     "GetDataSetResponseTypeDef",
-    "GetRevisionResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "RevokeRevisionResponseTypeDef",
-    "SendApiAssetResponseTypeDef",
     "UpdateDataSetResponseTypeDef",
-    "UpdateRevisionResponseTypeDef",
-    "CreateS3DataAccessFromS3BucketRequestDetailsTypeDef",
-    "CreateS3DataAccessFromS3BucketResponseDetailsTypeDef",
     "DatabaseLFTagPolicyAndPermissionsTypeDef",
     "DatabaseLFTagPolicyTypeDef",
     "TableLFTagPolicyAndPermissionsTypeDef",
     "TableLFTagPolicyTypeDef",
     "DetailsTypeDef",
     "EventTypeDef",
     "ExportRevisionsToS3RequestDetailsTypeDef",
     "ExportRevisionsToS3ResponseDetailsTypeDef",
     "ImportAssetsFromRedshiftDataSharesRequestDetailsTypeDef",
     "ImportAssetsFromRedshiftDataSharesResponseDetailsTypeDef",
-    "ListDataSetRevisionsRequestListDataSetRevisionsPaginateTypeDef",
-    "ListDataSetsRequestListDataSetsPaginateTypeDef",
-    "ListEventActionsRequestListEventActionsPaginateTypeDef",
-    "ListJobsRequestListJobsPaginateTypeDef",
-    "ListRevisionAssetsRequestListRevisionAssetsPaginateTypeDef",
+    "S3DataAccessAssetSourceEntryTypeDef",
+    "S3DataAccessAssetTypeDef",
     "ListDataSetRevisionsResponseTypeDef",
     "ActionTypeDef",
     "ListDataSetsResponseTypeDef",
     "ImportAssetsFromLakeFormationTagPolicyRequestDetailsTypeDef",
     "ImportAssetsFromLakeFormationTagPolicyResponseDetailsTypeDef",
     "LFResourceDetailsTypeDef",
     "JobErrorTypeDef",
+    "CreateS3DataAccessFromS3BucketRequestDetailsTypeDef",
+    "CreateS3DataAccessFromS3BucketResponseDetailsTypeDef",
     "CreateEventActionRequestRequestTypeDef",
     "CreateEventActionResponseTypeDef",
     "EventActionEntryTypeDef",
     "GetEventActionResponseTypeDef",
     "UpdateEventActionRequestRequestTypeDef",
     "UpdateEventActionResponseTypeDef",
+    "LFTagPolicyDetailsTypeDef",
     "RequestDetailsTypeDef",
     "ResponseDetailsTypeDef",
-    "LFTagPolicyDetailsTypeDef",
     "ListEventActionsResponseTypeDef",
+    "LakeFormationDataPermissionDetailsTypeDef",
     "CreateJobRequestRequestTypeDef",
     "CreateJobResponseTypeDef",
     "GetJobResponseTypeDef",
     "JobEntryTypeDef",
-    "LakeFormationDataPermissionDetailsTypeDef",
-    "ListJobsResponseTypeDef",
     "LakeFormationDataPermissionAssetTypeDef",
+    "ListJobsResponseTypeDef",
     "AssetDetailsTypeDef",
     "AssetEntryTypeDef",
     "GetAssetResponseTypeDef",
     "UpdateAssetResponseTypeDef",
     "ListRevisionAssetsResponseTypeDef",
 )
 
@@ -195,38 +196,14 @@
 RedshiftDataShareAssetTypeDef = TypedDict(
     "RedshiftDataShareAssetTypeDef",
     {
         "Arn": str,
     },
 )
 
-_RequiredS3DataAccessAssetTypeDef = TypedDict(
-    "_RequiredS3DataAccessAssetTypeDef",
-    {
-        "Bucket": str,
-    },
-)
-_OptionalS3DataAccessAssetTypeDef = TypedDict(
-    "_OptionalS3DataAccessAssetTypeDef",
-    {
-        "KeyPrefixes": List[str],
-        "Keys": List[str],
-        "S3AccessPointAlias": str,
-        "S3AccessPointArn": str,
-    },
-    total=False,
-)
-
-
-class S3DataAccessAssetTypeDef(
-    _RequiredS3DataAccessAssetTypeDef, _OptionalS3DataAccessAssetTypeDef
-):
-    pass
-
-
 S3SnapshotAssetTypeDef = TypedDict(
     "S3SnapshotAssetTypeDef",
     {
         "Size": float,
     },
 )
 
@@ -314,25 +291,14 @@
 OriginDetailsTypeDef = TypedDict(
     "OriginDetailsTypeDef",
     {
         "ProductId": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
-    {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
-    },
-)
-
 _RequiredCreateRevisionRequestRequestTypeDef = TypedDict(
     "_RequiredCreateRevisionRequestRequestTypeDef",
     {
         "DataSetId": str,
     },
 )
 _OptionalCreateRevisionRequestRequestTypeDef = TypedDict(
@@ -347,36 +313,33 @@
 
 class CreateRevisionRequestRequestTypeDef(
     _RequiredCreateRevisionRequestRequestTypeDef, _OptionalCreateRevisionRequestRequestTypeDef
 ):
     pass
 
 
-_RequiredS3DataAccessAssetSourceEntryTypeDef = TypedDict(
-    "_RequiredS3DataAccessAssetSourceEntryTypeDef",
-    {
-        "Bucket": str,
-    },
-)
-_OptionalS3DataAccessAssetSourceEntryTypeDef = TypedDict(
-    "_OptionalS3DataAccessAssetSourceEntryTypeDef",
+CreateRevisionResponseTypeDef = TypedDict(
+    "CreateRevisionResponseTypeDef",
     {
-        "KeyPrefixes": Sequence[str],
-        "Keys": Sequence[str],
+        "Arn": str,
+        "Comment": str,
+        "CreatedAt": datetime,
+        "DataSetId": str,
+        "Finalized": bool,
+        "Id": str,
+        "SourceId": str,
+        "Tags": Dict[str, str],
+        "UpdatedAt": datetime,
+        "RevocationComment": str,
+        "Revoked": bool,
+        "RevokedAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-
-class S3DataAccessAssetSourceEntryTypeDef(
-    _RequiredS3DataAccessAssetSourceEntryTypeDef, _OptionalS3DataAccessAssetSourceEntryTypeDef
-):
-    pass
-
-
 LFTagTypeDef = TypedDict(
     "LFTagTypeDef",
     {
         "TagKey": str,
         "TagValues": Sequence[str],
     },
 )
@@ -415,14 +378,21 @@
 ImportAssetFromSignedUrlJobErrorDetailsTypeDef = TypedDict(
     "ImportAssetFromSignedUrlJobErrorDetailsTypeDef",
     {
         "AssetName": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RevisionPublishedTypeDef = TypedDict(
     "RevisionPublishedTypeDef",
     {
         "DataSetId": str,
     },
 )
 
@@ -516,14 +486,33 @@
     "GetRevisionRequestRequestTypeDef",
     {
         "DataSetId": str,
         "RevisionId": str,
     },
 )
 
+GetRevisionResponseTypeDef = TypedDict(
+    "GetRevisionResponseTypeDef",
+    {
+        "Arn": str,
+        "Comment": str,
+        "CreatedAt": datetime,
+        "DataSetId": str,
+        "Finalized": bool,
+        "Id": str,
+        "SourceId": str,
+        "Tags": Dict[str, str],
+        "UpdatedAt": datetime,
+        "RevocationComment": str,
+        "Revoked": bool,
+        "RevokedAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredImportAssetFromApiGatewayApiRequestDetailsTypeDef = TypedDict(
     "_RequiredImportAssetFromApiGatewayApiRequestDetailsTypeDef",
     {
         "ApiId": str,
         "ApiName": str,
         "ApiSpecificationMd5Hash": str,
         "DataSetId": str,
@@ -619,24 +608,43 @@
 RedshiftDataShareAssetSourceEntryTypeDef = TypedDict(
     "RedshiftDataShareAssetSourceEntryTypeDef",
     {
         "DataShareArn": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+KmsKeyToGrantTypeDef = TypedDict(
+    "KmsKeyToGrantTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "KmsKeyArn": str,
+    },
+)
+
+_RequiredListDataSetRevisionsRequestListDataSetRevisionsPaginateTypeDef = TypedDict(
+    "_RequiredListDataSetRevisionsRequestListDataSetRevisionsPaginateTypeDef",
+    {
+        "DataSetId": str,
+    },
+)
+_OptionalListDataSetRevisionsRequestListDataSetRevisionsPaginateTypeDef = TypedDict(
+    "_OptionalListDataSetRevisionsRequestListDataSetRevisionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListDataSetRevisionsRequestListDataSetRevisionsPaginateTypeDef(
+    _RequiredListDataSetRevisionsRequestListDataSetRevisionsPaginateTypeDef,
+    _OptionalListDataSetRevisionsRequestListDataSetRevisionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListDataSetRevisionsRequestRequestTypeDef = TypedDict(
     "_RequiredListDataSetRevisionsRequestRequestTypeDef",
     {
         "DataSetId": str,
     },
 )
 _OptionalListDataSetRevisionsRequestRequestTypeDef = TypedDict(
@@ -680,45 +688,96 @@
 )
 
 
 class RevisionEntryTypeDef(_RequiredRevisionEntryTypeDef, _OptionalRevisionEntryTypeDef):
     pass
 
 
+ListDataSetsRequestListDataSetsPaginateTypeDef = TypedDict(
+    "ListDataSetsRequestListDataSetsPaginateTypeDef",
+    {
+        "Origin": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDataSetsRequestRequestTypeDef = TypedDict(
     "ListDataSetsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
         "Origin": str,
     },
     total=False,
 )
 
+ListEventActionsRequestListEventActionsPaginateTypeDef = TypedDict(
+    "ListEventActionsRequestListEventActionsPaginateTypeDef",
+    {
+        "EventSourceId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListEventActionsRequestRequestTypeDef = TypedDict(
     "ListEventActionsRequestRequestTypeDef",
     {
         "EventSourceId": str,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListJobsRequestListJobsPaginateTypeDef = TypedDict(
+    "ListJobsRequestListJobsPaginateTypeDef",
+    {
+        "DataSetId": str,
+        "RevisionId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListJobsRequestRequestTypeDef = TypedDict(
     "ListJobsRequestRequestTypeDef",
     {
         "DataSetId": str,
         "MaxResults": int,
         "NextToken": str,
         "RevisionId": str,
     },
     total=False,
 )
 
+_RequiredListRevisionAssetsRequestListRevisionAssetsPaginateTypeDef = TypedDict(
+    "_RequiredListRevisionAssetsRequestListRevisionAssetsPaginateTypeDef",
+    {
+        "DataSetId": str,
+        "RevisionId": str,
+    },
+)
+_OptionalListRevisionAssetsRequestListRevisionAssetsPaginateTypeDef = TypedDict(
+    "_OptionalListRevisionAssetsRequestListRevisionAssetsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListRevisionAssetsRequestListRevisionAssetsPaginateTypeDef(
+    _RequiredListRevisionAssetsRequestListRevisionAssetsPaginateTypeDef,
+    _OptionalListRevisionAssetsRequestListRevisionAssetsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListRevisionAssetsRequestRequestTypeDef = TypedDict(
     "_RequiredListRevisionAssetsRequestRequestTypeDef",
     {
         "DataSetId": str,
         "RevisionId": str,
     },
 )
@@ -742,23 +801,70 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "Tags": Dict[str, str],
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
 RevokeRevisionRequestRequestTypeDef = TypedDict(
     "RevokeRevisionRequestRequestTypeDef",
     {
         "DataSetId": str,
         "RevisionId": str,
         "RevocationComment": str,
     },
 )
 
+RevokeRevisionResponseTypeDef = TypedDict(
+    "RevokeRevisionResponseTypeDef",
+    {
+        "Arn": str,
+        "Comment": str,
+        "CreatedAt": datetime,
+        "DataSetId": str,
+        "Finalized": bool,
+        "Id": str,
+        "SourceId": str,
+        "UpdatedAt": datetime,
+        "RevocationComment": str,
+        "Revoked": bool,
+        "RevokedAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredSendApiAssetRequestRequestTypeDef = TypedDict(
     "_RequiredSendApiAssetRequestRequestTypeDef",
     {
         "AssetId": str,
         "DataSetId": str,
         "RevisionId": str,
     },
@@ -778,14 +884,23 @@
 
 class SendApiAssetRequestRequestTypeDef(
     _RequiredSendApiAssetRequestRequestTypeDef, _OptionalSendApiAssetRequestRequestTypeDef
 ):
     pass
 
 
+SendApiAssetResponseTypeDef = TypedDict(
+    "SendApiAssetResponseTypeDef",
+    {
+        "Body": str,
+        "ResponseHeaders": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartJobRequestRequestTypeDef = TypedDict(
     "StartJobRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 
@@ -856,14 +971,32 @@
 
 class UpdateRevisionRequestRequestTypeDef(
     _RequiredUpdateRevisionRequestRequestTypeDef, _OptionalUpdateRevisionRequestRequestTypeDef
 ):
     pass
 
 
+UpdateRevisionResponseTypeDef = TypedDict(
+    "UpdateRevisionResponseTypeDef",
+    {
+        "Arn": str,
+        "Comment": str,
+        "CreatedAt": datetime,
+        "DataSetId": str,
+        "Finalized": bool,
+        "Id": str,
+        "SourceId": str,
+        "UpdatedAt": datetime,
+        "RevocationComment": str,
+        "Revoked": bool,
+        "RevokedAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ImportAssetsFromS3RequestDetailsTypeDef = TypedDict(
     "ImportAssetsFromS3RequestDetailsTypeDef",
     {
         "AssetSources": Sequence[AssetSourceEntryTypeDef],
         "DataSetId": str,
         "RevisionId": str,
     },
@@ -942,84 +1075,58 @@
 
 class ExportAssetsToS3ResponseDetailsTypeDef(
     _RequiredExportAssetsToS3ResponseDetailsTypeDef, _OptionalExportAssetsToS3ResponseDetailsTypeDef
 ):
     pass
 
 
-_RequiredDataSetEntryTypeDef = TypedDict(
-    "_RequiredDataSetEntryTypeDef",
+CreateDataSetResponseTypeDef = TypedDict(
+    "CreateDataSetResponseTypeDef",
     {
         "Arn": str,
         "AssetType": AssetTypeType,
         "CreatedAt": datetime,
         "Description": str,
         "Id": str,
         "Name": str,
         "Origin": OriginType,
-        "UpdatedAt": datetime,
-    },
-)
-_OptionalDataSetEntryTypeDef = TypedDict(
-    "_OptionalDataSetEntryTypeDef",
-    {
         "OriginDetails": OriginDetailsTypeDef,
         "SourceId": str,
+        "Tags": Dict[str, str],
+        "UpdatedAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-
-class DataSetEntryTypeDef(_RequiredDataSetEntryTypeDef, _OptionalDataSetEntryTypeDef):
-    pass
-
-
-CreateDataSetResponseTypeDef = TypedDict(
-    "CreateDataSetResponseTypeDef",
+_RequiredDataSetEntryTypeDef = TypedDict(
+    "_RequiredDataSetEntryTypeDef",
     {
         "Arn": str,
         "AssetType": AssetTypeType,
         "CreatedAt": datetime,
         "Description": str,
         "Id": str,
         "Name": str,
         "Origin": OriginType,
-        "OriginDetails": OriginDetailsTypeDef,
-        "SourceId": str,
-        "Tags": Dict[str, str],
         "UpdatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
-
-CreateRevisionResponseTypeDef = TypedDict(
-    "CreateRevisionResponseTypeDef",
+_OptionalDataSetEntryTypeDef = TypedDict(
+    "_OptionalDataSetEntryTypeDef",
     {
-        "Arn": str,
-        "Comment": str,
-        "CreatedAt": datetime,
-        "DataSetId": str,
-        "Finalized": bool,
-        "Id": str,
+        "OriginDetails": OriginDetailsTypeDef,
         "SourceId": str,
-        "Tags": Dict[str, str],
-        "UpdatedAt": datetime,
-        "RevocationComment": str,
-        "Revoked": bool,
-        "RevokedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
+    total=False,
 )
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+
+class DataSetEntryTypeDef(_RequiredDataSetEntryTypeDef, _OptionalDataSetEntryTypeDef):
+    pass
+
 
 GetDataSetResponseTypeDef = TypedDict(
     "GetDataSetResponseTypeDef",
     {
         "Arn": str,
         "AssetType": AssetTypeType,
         "CreatedAt": datetime,
@@ -1027,69 +1134,15 @@
         "Id": str,
         "Name": str,
         "Origin": OriginType,
         "OriginDetails": OriginDetailsTypeDef,
         "SourceId": str,
         "Tags": Dict[str, str],
         "UpdatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetRevisionResponseTypeDef = TypedDict(
-    "GetRevisionResponseTypeDef",
-    {
-        "Arn": str,
-        "Comment": str,
-        "CreatedAt": datetime,
-        "DataSetId": str,
-        "Finalized": bool,
-        "Id": str,
-        "SourceId": str,
-        "Tags": Dict[str, str],
-        "UpdatedAt": datetime,
-        "RevocationComment": str,
-        "Revoked": bool,
-        "RevokedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RevokeRevisionResponseTypeDef = TypedDict(
-    "RevokeRevisionResponseTypeDef",
-    {
-        "Arn": str,
-        "Comment": str,
-        "CreatedAt": datetime,
-        "DataSetId": str,
-        "Finalized": bool,
-        "Id": str,
-        "SourceId": str,
-        "UpdatedAt": datetime,
-        "RevocationComment": str,
-        "Revoked": bool,
-        "RevokedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SendApiAssetResponseTypeDef = TypedDict(
-    "SendApiAssetResponseTypeDef",
-    {
-        "Body": str,
-        "ResponseHeaders": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDataSetResponseTypeDef = TypedDict(
     "UpdateDataSetResponseTypeDef",
     {
         "Arn": str,
@@ -1098,51 +1151,15 @@
         "Description": str,
         "Id": str,
         "Name": str,
         "Origin": OriginType,
         "OriginDetails": OriginDetailsTypeDef,
         "SourceId": str,
         "UpdatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateRevisionResponseTypeDef = TypedDict(
-    "UpdateRevisionResponseTypeDef",
-    {
-        "Arn": str,
-        "Comment": str,
-        "CreatedAt": datetime,
-        "DataSetId": str,
-        "Finalized": bool,
-        "Id": str,
-        "SourceId": str,
-        "UpdatedAt": datetime,
-        "RevocationComment": str,
-        "Revoked": bool,
-        "RevokedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateS3DataAccessFromS3BucketRequestDetailsTypeDef = TypedDict(
-    "CreateS3DataAccessFromS3BucketRequestDetailsTypeDef",
-    {
-        "AssetSource": S3DataAccessAssetSourceEntryTypeDef,
-        "DataSetId": str,
-        "RevisionId": str,
-    },
-)
-
-CreateS3DataAccessFromS3BucketResponseDetailsTypeDef = TypedDict(
-    "CreateS3DataAccessFromS3BucketResponseDetailsTypeDef",
-    {
-        "AssetSource": S3DataAccessAssetSourceEntryTypeDef,
-        "DataSetId": str,
-        "RevisionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DatabaseLFTagPolicyAndPermissionsTypeDef = TypedDict(
     "DatabaseLFTagPolicyAndPermissionsTypeDef",
     {
         "Expression": Sequence[LFTagTypeDef],
@@ -1250,93 +1267,68 @@
     {
         "AssetSources": List[RedshiftDataShareAssetSourceEntryTypeDef],
         "DataSetId": str,
         "RevisionId": str,
     },
 )
 
-_RequiredListDataSetRevisionsRequestListDataSetRevisionsPaginateTypeDef = TypedDict(
-    "_RequiredListDataSetRevisionsRequestListDataSetRevisionsPaginateTypeDef",
+_RequiredS3DataAccessAssetSourceEntryTypeDef = TypedDict(
+    "_RequiredS3DataAccessAssetSourceEntryTypeDef",
     {
-        "DataSetId": str,
+        "Bucket": str,
     },
 )
-_OptionalListDataSetRevisionsRequestListDataSetRevisionsPaginateTypeDef = TypedDict(
-    "_OptionalListDataSetRevisionsRequestListDataSetRevisionsPaginateTypeDef",
+_OptionalS3DataAccessAssetSourceEntryTypeDef = TypedDict(
+    "_OptionalS3DataAccessAssetSourceEntryTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "KeyPrefixes": Sequence[str],
+        "Keys": Sequence[str],
+        "KmsKeysToGrant": Sequence[KmsKeyToGrantTypeDef],
     },
     total=False,
 )
 
 
-class ListDataSetRevisionsRequestListDataSetRevisionsPaginateTypeDef(
-    _RequiredListDataSetRevisionsRequestListDataSetRevisionsPaginateTypeDef,
-    _OptionalListDataSetRevisionsRequestListDataSetRevisionsPaginateTypeDef,
+class S3DataAccessAssetSourceEntryTypeDef(
+    _RequiredS3DataAccessAssetSourceEntryTypeDef, _OptionalS3DataAccessAssetSourceEntryTypeDef
 ):
     pass
 
 
-ListDataSetsRequestListDataSetsPaginateTypeDef = TypedDict(
-    "ListDataSetsRequestListDataSetsPaginateTypeDef",
-    {
-        "Origin": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListEventActionsRequestListEventActionsPaginateTypeDef = TypedDict(
-    "ListEventActionsRequestListEventActionsPaginateTypeDef",
-    {
-        "EventSourceId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListJobsRequestListJobsPaginateTypeDef = TypedDict(
-    "ListJobsRequestListJobsPaginateTypeDef",
-    {
-        "DataSetId": str,
-        "RevisionId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListRevisionAssetsRequestListRevisionAssetsPaginateTypeDef = TypedDict(
-    "_RequiredListRevisionAssetsRequestListRevisionAssetsPaginateTypeDef",
+_RequiredS3DataAccessAssetTypeDef = TypedDict(
+    "_RequiredS3DataAccessAssetTypeDef",
     {
-        "DataSetId": str,
-        "RevisionId": str,
+        "Bucket": str,
     },
 )
-_OptionalListRevisionAssetsRequestListRevisionAssetsPaginateTypeDef = TypedDict(
-    "_OptionalListRevisionAssetsRequestListRevisionAssetsPaginateTypeDef",
+_OptionalS3DataAccessAssetTypeDef = TypedDict(
+    "_OptionalS3DataAccessAssetTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "KeyPrefixes": List[str],
+        "Keys": List[str],
+        "S3AccessPointAlias": str,
+        "S3AccessPointArn": str,
+        "KmsKeysToGrant": List[KmsKeyToGrantTypeDef],
     },
     total=False,
 )
 
 
-class ListRevisionAssetsRequestListRevisionAssetsPaginateTypeDef(
-    _RequiredListRevisionAssetsRequestListRevisionAssetsPaginateTypeDef,
-    _OptionalListRevisionAssetsRequestListRevisionAssetsPaginateTypeDef,
+class S3DataAccessAssetTypeDef(
+    _RequiredS3DataAccessAssetTypeDef, _OptionalS3DataAccessAssetTypeDef
 ):
     pass
 
 
 ListDataSetRevisionsResponseTypeDef = TypedDict(
     "ListDataSetRevisionsResponseTypeDef",
     {
         "NextToken": str,
         "Revisions": List[RevisionEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ActionTypeDef = TypedDict(
     "ActionTypeDef",
     {
         "ExportRevisionToS3": AutoExportRevisionToS3RequestDetailsTypeDef,
@@ -1345,15 +1337,15 @@
 )
 
 ListDataSetsResponseTypeDef = TypedDict(
     "ListDataSetsResponseTypeDef",
     {
         "DataSets": List[DataSetEntryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredImportAssetsFromLakeFormationTagPolicyRequestDetailsTypeDef = TypedDict(
     "_RequiredImportAssetsFromLakeFormationTagPolicyRequestDetailsTypeDef",
     {
         "CatalogId": str,
@@ -1434,14 +1426,32 @@
 )
 
 
 class JobErrorTypeDef(_RequiredJobErrorTypeDef, _OptionalJobErrorTypeDef):
     pass
 
 
+CreateS3DataAccessFromS3BucketRequestDetailsTypeDef = TypedDict(
+    "CreateS3DataAccessFromS3BucketRequestDetailsTypeDef",
+    {
+        "AssetSource": S3DataAccessAssetSourceEntryTypeDef,
+        "DataSetId": str,
+        "RevisionId": str,
+    },
+)
+
+CreateS3DataAccessFromS3BucketResponseDetailsTypeDef = TypedDict(
+    "CreateS3DataAccessFromS3BucketResponseDetailsTypeDef",
+    {
+        "AssetSource": S3DataAccessAssetSourceEntryTypeDef,
+        "DataSetId": str,
+        "RevisionId": str,
+    },
+)
+
 CreateEventActionRequestRequestTypeDef = TypedDict(
     "CreateEventActionRequestRequestTypeDef",
     {
         "Action": ActionTypeDef,
         "Event": EventTypeDef,
     },
 )
@@ -1451,15 +1461,15 @@
     {
         "Action": ActionTypeDef,
         "Arn": str,
         "CreatedAt": datetime,
         "Event": EventTypeDef,
         "Id": str,
         "UpdatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EventActionEntryTypeDef = TypedDict(
     "EventActionEntryTypeDef",
     {
         "Action": ActionTypeDef,
@@ -1476,15 +1486,15 @@
     {
         "Action": ActionTypeDef,
         "Arn": str,
         "CreatedAt": datetime,
         "Event": EventTypeDef,
         "Id": str,
         "UpdatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateEventActionRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateEventActionRequestRequestTypeDef",
     {
         "EventActionId": str,
@@ -1510,15 +1520,24 @@
     {
         "Action": ActionTypeDef,
         "Arn": str,
         "CreatedAt": datetime,
         "Event": EventTypeDef,
         "Id": str,
         "UpdatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+LFTagPolicyDetailsTypeDef = TypedDict(
+    "LFTagPolicyDetailsTypeDef",
+    {
+        "CatalogId": str,
+        "ResourceType": LFResourceTypeType,
+        "ResourceDetails": LFResourceDetailsTypeDef,
     },
 )
 
 RequestDetailsTypeDef = TypedDict(
     "RequestDetailsTypeDef",
     {
         "ExportAssetToSignedUrl": ExportAssetToSignedUrlRequestDetailsTypeDef,
@@ -1554,32 +1573,31 @@
         "ImportAssetsFromLakeFormationTagPolicy": (
             ImportAssetsFromLakeFormationTagPolicyResponseDetailsTypeDef
         ),
     },
     total=False,
 )
 
-LFTagPolicyDetailsTypeDef = TypedDict(
-    "LFTagPolicyDetailsTypeDef",
-    {
-        "CatalogId": str,
-        "ResourceType": LFResourceTypeType,
-        "ResourceDetails": LFResourceDetailsTypeDef,
-    },
-)
-
 ListEventActionsResponseTypeDef = TypedDict(
     "ListEventActionsResponseTypeDef",
     {
         "EventActions": List[EventActionEntryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
+LakeFormationDataPermissionDetailsTypeDef = TypedDict(
+    "LakeFormationDataPermissionDetailsTypeDef",
+    {
+        "LFTagPolicy": LFTagPolicyDetailsTypeDef,
+    },
+    total=False,
+)
+
 CreateJobRequestRequestTypeDef = TypedDict(
     "CreateJobRequestRequestTypeDef",
     {
         "Details": RequestDetailsTypeDef,
         "Type": TypeType,
     },
 )
@@ -1591,30 +1609,30 @@
         "CreatedAt": datetime,
         "Details": ResponseDetailsTypeDef,
         "Errors": List[JobErrorTypeDef],
         "Id": str,
         "State": StateType,
         "Type": TypeType,
         "UpdatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetJobResponseTypeDef = TypedDict(
     "GetJobResponseTypeDef",
     {
         "Arn": str,
         "CreatedAt": datetime,
         "Details": ResponseDetailsTypeDef,
         "Errors": List[JobErrorTypeDef],
         "Id": str,
         "State": StateType,
         "Type": TypeType,
         "UpdatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredJobEntryTypeDef = TypedDict(
     "_RequiredJobEntryTypeDef",
     {
         "Arn": str,
@@ -1635,31 +1653,14 @@
 )
 
 
 class JobEntryTypeDef(_RequiredJobEntryTypeDef, _OptionalJobEntryTypeDef):
     pass
 
 
-LakeFormationDataPermissionDetailsTypeDef = TypedDict(
-    "LakeFormationDataPermissionDetailsTypeDef",
-    {
-        "LFTagPolicy": LFTagPolicyDetailsTypeDef,
-    },
-    total=False,
-)
-
-ListJobsResponseTypeDef = TypedDict(
-    "ListJobsResponseTypeDef",
-    {
-        "Jobs": List[JobEntryTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 _RequiredLakeFormationDataPermissionAssetTypeDef = TypedDict(
     "_RequiredLakeFormationDataPermissionAssetTypeDef",
     {
         "LakeFormationDataPermissionDetails": LakeFormationDataPermissionDetailsTypeDef,
         "LakeFormationDataPermissionType": Literal["LFTagPolicy"],
         "Permissions": List[LFPermissionType],
     },
@@ -1676,14 +1677,23 @@
 class LakeFormationDataPermissionAssetTypeDef(
     _RequiredLakeFormationDataPermissionAssetTypeDef,
     _OptionalLakeFormationDataPermissionAssetTypeDef,
 ):
     pass
 
 
+ListJobsResponseTypeDef = TypedDict(
+    "ListJobsResponseTypeDef",
+    {
+        "Jobs": List[JobEntryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AssetDetailsTypeDef = TypedDict(
     "AssetDetailsTypeDef",
     {
         "S3SnapshotAsset": S3SnapshotAssetTypeDef,
         "RedshiftDataShareAsset": RedshiftDataShareAssetTypeDef,
         "ApiGatewayApiAsset": ApiGatewayApiAssetTypeDef,
         "S3DataAccessAsset": S3DataAccessAssetTypeDef,
@@ -1728,15 +1738,15 @@
         "CreatedAt": datetime,
         "DataSetId": str,
         "Id": str,
         "Name": str,
         "RevisionId": str,
         "SourceId": str,
         "UpdatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAssetResponseTypeDef = TypedDict(
     "UpdateAssetResponseTypeDef",
     {
         "Arn": str,
@@ -1745,19 +1755,19 @@
         "CreatedAt": datetime,
         "DataSetId": str,
         "Id": str,
         "Name": str,
         "RevisionId": str,
         "SourceId": str,
         "UpdatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRevisionAssetsResponseTypeDef = TypedDict(
     "ListRevisionAssetsResponseTypeDef",
     {
         "Assets": List[AssetEntryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-dataexchange-2.5.0.post1/types_aiobotocore_dataexchange/type_defs.pyi` & `types-aiobotocore-dataexchange-2.5.1/types_aiobotocore_dataexchange/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -38,118 +38,119 @@
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "ApiGatewayApiAssetTypeDef",
     "AssetDestinationEntryTypeDef",
     "RedshiftDataShareAssetTypeDef",
-    "S3DataAccessAssetTypeDef",
     "S3SnapshotAssetTypeDef",
     "AssetSourceEntryTypeDef",
     "AutoExportRevisionDestinationEntryTypeDef",
     "ExportServerSideEncryptionTypeDef",
     "CancelJobRequestRequestTypeDef",
     "CreateDataSetRequestRequestTypeDef",
     "OriginDetailsTypeDef",
-    "ResponseMetadataTypeDef",
     "CreateRevisionRequestRequestTypeDef",
-    "S3DataAccessAssetSourceEntryTypeDef",
+    "CreateRevisionResponseTypeDef",
     "LFTagTypeDef",
     "DeleteAssetRequestRequestTypeDef",
     "DeleteDataSetRequestRequestTypeDef",
     "DeleteEventActionRequestRequestTypeDef",
     "DeleteRevisionRequestRequestTypeDef",
     "ImportAssetFromSignedUrlJobErrorDetailsTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "RevisionPublishedTypeDef",
     "ExportAssetToSignedUrlRequestDetailsTypeDef",
     "ExportAssetToSignedUrlResponseDetailsTypeDef",
     "RevisionDestinationEntryTypeDef",
     "GetAssetRequestRequestTypeDef",
     "GetDataSetRequestRequestTypeDef",
     "GetEventActionRequestRequestTypeDef",
     "GetJobRequestRequestTypeDef",
     "GetRevisionRequestRequestTypeDef",
+    "GetRevisionResponseTypeDef",
     "ImportAssetFromApiGatewayApiRequestDetailsTypeDef",
     "ImportAssetFromApiGatewayApiResponseDetailsTypeDef",
     "ImportAssetFromSignedUrlRequestDetailsTypeDef",
     "ImportAssetFromSignedUrlResponseDetailsTypeDef",
     "RedshiftDataShareAssetSourceEntryTypeDef",
-    "PaginatorConfigTypeDef",
+    "KmsKeyToGrantTypeDef",
+    "ListDataSetRevisionsRequestListDataSetRevisionsPaginateTypeDef",
     "ListDataSetRevisionsRequestRequestTypeDef",
     "RevisionEntryTypeDef",
+    "ListDataSetsRequestListDataSetsPaginateTypeDef",
     "ListDataSetsRequestRequestTypeDef",
+    "ListEventActionsRequestListEventActionsPaginateTypeDef",
     "ListEventActionsRequestRequestTypeDef",
+    "ListJobsRequestListJobsPaginateTypeDef",
     "ListJobsRequestRequestTypeDef",
+    "ListRevisionAssetsRequestListRevisionAssetsPaginateTypeDef",
     "ListRevisionAssetsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "RevokeRevisionRequestRequestTypeDef",
+    "RevokeRevisionResponseTypeDef",
     "SendApiAssetRequestRequestTypeDef",
+    "SendApiAssetResponseTypeDef",
     "StartJobRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateAssetRequestRequestTypeDef",
     "UpdateDataSetRequestRequestTypeDef",
     "UpdateRevisionRequestRequestTypeDef",
+    "UpdateRevisionResponseTypeDef",
     "ImportAssetsFromS3RequestDetailsTypeDef",
     "ImportAssetsFromS3ResponseDetailsTypeDef",
     "AutoExportRevisionToS3RequestDetailsTypeDef",
     "ExportAssetsToS3RequestDetailsTypeDef",
     "ExportAssetsToS3ResponseDetailsTypeDef",
-    "DataSetEntryTypeDef",
     "CreateDataSetResponseTypeDef",
-    "CreateRevisionResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
+    "DataSetEntryTypeDef",
     "GetDataSetResponseTypeDef",
-    "GetRevisionResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "RevokeRevisionResponseTypeDef",
-    "SendApiAssetResponseTypeDef",
     "UpdateDataSetResponseTypeDef",
-    "UpdateRevisionResponseTypeDef",
-    "CreateS3DataAccessFromS3BucketRequestDetailsTypeDef",
-    "CreateS3DataAccessFromS3BucketResponseDetailsTypeDef",
     "DatabaseLFTagPolicyAndPermissionsTypeDef",
     "DatabaseLFTagPolicyTypeDef",
     "TableLFTagPolicyAndPermissionsTypeDef",
     "TableLFTagPolicyTypeDef",
     "DetailsTypeDef",
     "EventTypeDef",
     "ExportRevisionsToS3RequestDetailsTypeDef",
     "ExportRevisionsToS3ResponseDetailsTypeDef",
     "ImportAssetsFromRedshiftDataSharesRequestDetailsTypeDef",
     "ImportAssetsFromRedshiftDataSharesResponseDetailsTypeDef",
-    "ListDataSetRevisionsRequestListDataSetRevisionsPaginateTypeDef",
-    "ListDataSetsRequestListDataSetsPaginateTypeDef",
-    "ListEventActionsRequestListEventActionsPaginateTypeDef",
-    "ListJobsRequestListJobsPaginateTypeDef",
-    "ListRevisionAssetsRequestListRevisionAssetsPaginateTypeDef",
+    "S3DataAccessAssetSourceEntryTypeDef",
+    "S3DataAccessAssetTypeDef",
     "ListDataSetRevisionsResponseTypeDef",
     "ActionTypeDef",
     "ListDataSetsResponseTypeDef",
     "ImportAssetsFromLakeFormationTagPolicyRequestDetailsTypeDef",
     "ImportAssetsFromLakeFormationTagPolicyResponseDetailsTypeDef",
     "LFResourceDetailsTypeDef",
     "JobErrorTypeDef",
+    "CreateS3DataAccessFromS3BucketRequestDetailsTypeDef",
+    "CreateS3DataAccessFromS3BucketResponseDetailsTypeDef",
     "CreateEventActionRequestRequestTypeDef",
     "CreateEventActionResponseTypeDef",
     "EventActionEntryTypeDef",
     "GetEventActionResponseTypeDef",
     "UpdateEventActionRequestRequestTypeDef",
     "UpdateEventActionResponseTypeDef",
+    "LFTagPolicyDetailsTypeDef",
     "RequestDetailsTypeDef",
     "ResponseDetailsTypeDef",
-    "LFTagPolicyDetailsTypeDef",
     "ListEventActionsResponseTypeDef",
+    "LakeFormationDataPermissionDetailsTypeDef",
     "CreateJobRequestRequestTypeDef",
     "CreateJobResponseTypeDef",
     "GetJobResponseTypeDef",
     "JobEntryTypeDef",
-    "LakeFormationDataPermissionDetailsTypeDef",
-    "ListJobsResponseTypeDef",
     "LakeFormationDataPermissionAssetTypeDef",
+    "ListJobsResponseTypeDef",
     "AssetDetailsTypeDef",
     "AssetEntryTypeDef",
     "GetAssetResponseTypeDef",
     "UpdateAssetResponseTypeDef",
     "ListRevisionAssetsResponseTypeDef",
 )
 
@@ -192,36 +193,14 @@
 RedshiftDataShareAssetTypeDef = TypedDict(
     "RedshiftDataShareAssetTypeDef",
     {
         "Arn": str,
     },
 )
 
-_RequiredS3DataAccessAssetTypeDef = TypedDict(
-    "_RequiredS3DataAccessAssetTypeDef",
-    {
-        "Bucket": str,
-    },
-)
-_OptionalS3DataAccessAssetTypeDef = TypedDict(
-    "_OptionalS3DataAccessAssetTypeDef",
-    {
-        "KeyPrefixes": List[str],
-        "Keys": List[str],
-        "S3AccessPointAlias": str,
-        "S3AccessPointArn": str,
-    },
-    total=False,
-)
-
-class S3DataAccessAssetTypeDef(
-    _RequiredS3DataAccessAssetTypeDef, _OptionalS3DataAccessAssetTypeDef
-):
-    pass
-
 S3SnapshotAssetTypeDef = TypedDict(
     "S3SnapshotAssetTypeDef",
     {
         "Size": float,
     },
 )
 
@@ -303,25 +282,14 @@
 OriginDetailsTypeDef = TypedDict(
     "OriginDetailsTypeDef",
     {
         "ProductId": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
-    {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
-    },
-)
-
 _RequiredCreateRevisionRequestRequestTypeDef = TypedDict(
     "_RequiredCreateRevisionRequestRequestTypeDef",
     {
         "DataSetId": str,
     },
 )
 _OptionalCreateRevisionRequestRequestTypeDef = TypedDict(
@@ -334,33 +302,32 @@
 )
 
 class CreateRevisionRequestRequestTypeDef(
     _RequiredCreateRevisionRequestRequestTypeDef, _OptionalCreateRevisionRequestRequestTypeDef
 ):
     pass
 
-_RequiredS3DataAccessAssetSourceEntryTypeDef = TypedDict(
-    "_RequiredS3DataAccessAssetSourceEntryTypeDef",
+CreateRevisionResponseTypeDef = TypedDict(
+    "CreateRevisionResponseTypeDef",
     {
-        "Bucket": str,
+        "Arn": str,
+        "Comment": str,
+        "CreatedAt": datetime,
+        "DataSetId": str,
+        "Finalized": bool,
+        "Id": str,
+        "SourceId": str,
+        "Tags": Dict[str, str],
+        "UpdatedAt": datetime,
+        "RevocationComment": str,
+        "Revoked": bool,
+        "RevokedAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalS3DataAccessAssetSourceEntryTypeDef = TypedDict(
-    "_OptionalS3DataAccessAssetSourceEntryTypeDef",
-    {
-        "KeyPrefixes": Sequence[str],
-        "Keys": Sequence[str],
-    },
-    total=False,
-)
-
-class S3DataAccessAssetSourceEntryTypeDef(
-    _RequiredS3DataAccessAssetSourceEntryTypeDef, _OptionalS3DataAccessAssetSourceEntryTypeDef
-):
-    pass
 
 LFTagTypeDef = TypedDict(
     "LFTagTypeDef",
     {
         "TagKey": str,
         "TagValues": Sequence[str],
     },
@@ -400,14 +367,21 @@
 ImportAssetFromSignedUrlJobErrorDetailsTypeDef = TypedDict(
     "ImportAssetFromSignedUrlJobErrorDetailsTypeDef",
     {
         "AssetName": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RevisionPublishedTypeDef = TypedDict(
     "RevisionPublishedTypeDef",
     {
         "DataSetId": str,
     },
 )
 
@@ -497,14 +471,33 @@
     "GetRevisionRequestRequestTypeDef",
     {
         "DataSetId": str,
         "RevisionId": str,
     },
 )
 
+GetRevisionResponseTypeDef = TypedDict(
+    "GetRevisionResponseTypeDef",
+    {
+        "Arn": str,
+        "Comment": str,
+        "CreatedAt": datetime,
+        "DataSetId": str,
+        "Finalized": bool,
+        "Id": str,
+        "SourceId": str,
+        "Tags": Dict[str, str],
+        "UpdatedAt": datetime,
+        "RevocationComment": str,
+        "Revoked": bool,
+        "RevokedAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredImportAssetFromApiGatewayApiRequestDetailsTypeDef = TypedDict(
     "_RequiredImportAssetFromApiGatewayApiRequestDetailsTypeDef",
     {
         "ApiId": str,
         "ApiName": str,
         "ApiSpecificationMd5Hash": str,
         "DataSetId": str,
@@ -594,24 +587,41 @@
 RedshiftDataShareAssetSourceEntryTypeDef = TypedDict(
     "RedshiftDataShareAssetSourceEntryTypeDef",
     {
         "DataShareArn": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+KmsKeyToGrantTypeDef = TypedDict(
+    "KmsKeyToGrantTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "KmsKeyArn": str,
+    },
+)
+
+_RequiredListDataSetRevisionsRequestListDataSetRevisionsPaginateTypeDef = TypedDict(
+    "_RequiredListDataSetRevisionsRequestListDataSetRevisionsPaginateTypeDef",
+    {
+        "DataSetId": str,
+    },
+)
+_OptionalListDataSetRevisionsRequestListDataSetRevisionsPaginateTypeDef = TypedDict(
+    "_OptionalListDataSetRevisionsRequestListDataSetRevisionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListDataSetRevisionsRequestListDataSetRevisionsPaginateTypeDef(
+    _RequiredListDataSetRevisionsRequestListDataSetRevisionsPaginateTypeDef,
+    _OptionalListDataSetRevisionsRequestListDataSetRevisionsPaginateTypeDef,
+):
+    pass
+
 _RequiredListDataSetRevisionsRequestRequestTypeDef = TypedDict(
     "_RequiredListDataSetRevisionsRequestRequestTypeDef",
     {
         "DataSetId": str,
     },
 )
 _OptionalListDataSetRevisionsRequestRequestTypeDef = TypedDict(
@@ -651,45 +661,94 @@
     },
     total=False,
 )
 
 class RevisionEntryTypeDef(_RequiredRevisionEntryTypeDef, _OptionalRevisionEntryTypeDef):
     pass
 
+ListDataSetsRequestListDataSetsPaginateTypeDef = TypedDict(
+    "ListDataSetsRequestListDataSetsPaginateTypeDef",
+    {
+        "Origin": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDataSetsRequestRequestTypeDef = TypedDict(
     "ListDataSetsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
         "Origin": str,
     },
     total=False,
 )
 
+ListEventActionsRequestListEventActionsPaginateTypeDef = TypedDict(
+    "ListEventActionsRequestListEventActionsPaginateTypeDef",
+    {
+        "EventSourceId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListEventActionsRequestRequestTypeDef = TypedDict(
     "ListEventActionsRequestRequestTypeDef",
     {
         "EventSourceId": str,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListJobsRequestListJobsPaginateTypeDef = TypedDict(
+    "ListJobsRequestListJobsPaginateTypeDef",
+    {
+        "DataSetId": str,
+        "RevisionId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListJobsRequestRequestTypeDef = TypedDict(
     "ListJobsRequestRequestTypeDef",
     {
         "DataSetId": str,
         "MaxResults": int,
         "NextToken": str,
         "RevisionId": str,
     },
     total=False,
 )
 
+_RequiredListRevisionAssetsRequestListRevisionAssetsPaginateTypeDef = TypedDict(
+    "_RequiredListRevisionAssetsRequestListRevisionAssetsPaginateTypeDef",
+    {
+        "DataSetId": str,
+        "RevisionId": str,
+    },
+)
+_OptionalListRevisionAssetsRequestListRevisionAssetsPaginateTypeDef = TypedDict(
+    "_OptionalListRevisionAssetsRequestListRevisionAssetsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListRevisionAssetsRequestListRevisionAssetsPaginateTypeDef(
+    _RequiredListRevisionAssetsRequestListRevisionAssetsPaginateTypeDef,
+    _OptionalListRevisionAssetsRequestListRevisionAssetsPaginateTypeDef,
+):
+    pass
+
 _RequiredListRevisionAssetsRequestRequestTypeDef = TypedDict(
     "_RequiredListRevisionAssetsRequestRequestTypeDef",
     {
         "DataSetId": str,
         "RevisionId": str,
     },
 )
@@ -711,23 +770,70 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "Tags": Dict[str, str],
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
 RevokeRevisionRequestRequestTypeDef = TypedDict(
     "RevokeRevisionRequestRequestTypeDef",
     {
         "DataSetId": str,
         "RevisionId": str,
         "RevocationComment": str,
     },
 )
 
+RevokeRevisionResponseTypeDef = TypedDict(
+    "RevokeRevisionResponseTypeDef",
+    {
+        "Arn": str,
+        "Comment": str,
+        "CreatedAt": datetime,
+        "DataSetId": str,
+        "Finalized": bool,
+        "Id": str,
+        "SourceId": str,
+        "UpdatedAt": datetime,
+        "RevocationComment": str,
+        "Revoked": bool,
+        "RevokedAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredSendApiAssetRequestRequestTypeDef = TypedDict(
     "_RequiredSendApiAssetRequestRequestTypeDef",
     {
         "AssetId": str,
         "DataSetId": str,
         "RevisionId": str,
     },
@@ -745,14 +851,23 @@
 )
 
 class SendApiAssetRequestRequestTypeDef(
     _RequiredSendApiAssetRequestRequestTypeDef, _OptionalSendApiAssetRequestRequestTypeDef
 ):
     pass
 
+SendApiAssetResponseTypeDef = TypedDict(
+    "SendApiAssetResponseTypeDef",
+    {
+        "Body": str,
+        "ResponseHeaders": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartJobRequestRequestTypeDef = TypedDict(
     "StartJobRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 
@@ -819,14 +934,32 @@
 )
 
 class UpdateRevisionRequestRequestTypeDef(
     _RequiredUpdateRevisionRequestRequestTypeDef, _OptionalUpdateRevisionRequestRequestTypeDef
 ):
     pass
 
+UpdateRevisionResponseTypeDef = TypedDict(
+    "UpdateRevisionResponseTypeDef",
+    {
+        "Arn": str,
+        "Comment": str,
+        "CreatedAt": datetime,
+        "DataSetId": str,
+        "Finalized": bool,
+        "Id": str,
+        "SourceId": str,
+        "UpdatedAt": datetime,
+        "RevocationComment": str,
+        "Revoked": bool,
+        "RevokedAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ImportAssetsFromS3RequestDetailsTypeDef = TypedDict(
     "ImportAssetsFromS3RequestDetailsTypeDef",
     {
         "AssetSources": Sequence[AssetSourceEntryTypeDef],
         "DataSetId": str,
         "RevisionId": str,
     },
@@ -899,82 +1032,56 @@
 )
 
 class ExportAssetsToS3ResponseDetailsTypeDef(
     _RequiredExportAssetsToS3ResponseDetailsTypeDef, _OptionalExportAssetsToS3ResponseDetailsTypeDef
 ):
     pass
 
-_RequiredDataSetEntryTypeDef = TypedDict(
-    "_RequiredDataSetEntryTypeDef",
+CreateDataSetResponseTypeDef = TypedDict(
+    "CreateDataSetResponseTypeDef",
     {
         "Arn": str,
         "AssetType": AssetTypeType,
         "CreatedAt": datetime,
         "Description": str,
         "Id": str,
         "Name": str,
         "Origin": OriginType,
-        "UpdatedAt": datetime,
-    },
-)
-_OptionalDataSetEntryTypeDef = TypedDict(
-    "_OptionalDataSetEntryTypeDef",
-    {
         "OriginDetails": OriginDetailsTypeDef,
         "SourceId": str,
+        "Tags": Dict[str, str],
+        "UpdatedAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-class DataSetEntryTypeDef(_RequiredDataSetEntryTypeDef, _OptionalDataSetEntryTypeDef):
-    pass
-
-CreateDataSetResponseTypeDef = TypedDict(
-    "CreateDataSetResponseTypeDef",
+_RequiredDataSetEntryTypeDef = TypedDict(
+    "_RequiredDataSetEntryTypeDef",
     {
         "Arn": str,
         "AssetType": AssetTypeType,
         "CreatedAt": datetime,
         "Description": str,
         "Id": str,
         "Name": str,
         "Origin": OriginType,
-        "OriginDetails": OriginDetailsTypeDef,
-        "SourceId": str,
-        "Tags": Dict[str, str],
         "UpdatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
-
-CreateRevisionResponseTypeDef = TypedDict(
-    "CreateRevisionResponseTypeDef",
+_OptionalDataSetEntryTypeDef = TypedDict(
+    "_OptionalDataSetEntryTypeDef",
     {
-        "Arn": str,
-        "Comment": str,
-        "CreatedAt": datetime,
-        "DataSetId": str,
-        "Finalized": bool,
-        "Id": str,
+        "OriginDetails": OriginDetailsTypeDef,
         "SourceId": str,
-        "Tags": Dict[str, str],
-        "UpdatedAt": datetime,
-        "RevocationComment": str,
-        "Revoked": bool,
-        "RevokedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
+    total=False,
 )
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class DataSetEntryTypeDef(_RequiredDataSetEntryTypeDef, _OptionalDataSetEntryTypeDef):
+    pass
 
 GetDataSetResponseTypeDef = TypedDict(
     "GetDataSetResponseTypeDef",
     {
         "Arn": str,
         "AssetType": AssetTypeType,
         "CreatedAt": datetime,
@@ -982,69 +1089,15 @@
         "Id": str,
         "Name": str,
         "Origin": OriginType,
         "OriginDetails": OriginDetailsTypeDef,
         "SourceId": str,
         "Tags": Dict[str, str],
         "UpdatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetRevisionResponseTypeDef = TypedDict(
-    "GetRevisionResponseTypeDef",
-    {
-        "Arn": str,
-        "Comment": str,
-        "CreatedAt": datetime,
-        "DataSetId": str,
-        "Finalized": bool,
-        "Id": str,
-        "SourceId": str,
-        "Tags": Dict[str, str],
-        "UpdatedAt": datetime,
-        "RevocationComment": str,
-        "Revoked": bool,
-        "RevokedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RevokeRevisionResponseTypeDef = TypedDict(
-    "RevokeRevisionResponseTypeDef",
-    {
-        "Arn": str,
-        "Comment": str,
-        "CreatedAt": datetime,
-        "DataSetId": str,
-        "Finalized": bool,
-        "Id": str,
-        "SourceId": str,
-        "UpdatedAt": datetime,
-        "RevocationComment": str,
-        "Revoked": bool,
-        "RevokedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SendApiAssetResponseTypeDef = TypedDict(
-    "SendApiAssetResponseTypeDef",
-    {
-        "Body": str,
-        "ResponseHeaders": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDataSetResponseTypeDef = TypedDict(
     "UpdateDataSetResponseTypeDef",
     {
         "Arn": str,
@@ -1053,51 +1106,15 @@
         "Description": str,
         "Id": str,
         "Name": str,
         "Origin": OriginType,
         "OriginDetails": OriginDetailsTypeDef,
         "SourceId": str,
         "UpdatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateRevisionResponseTypeDef = TypedDict(
-    "UpdateRevisionResponseTypeDef",
-    {
-        "Arn": str,
-        "Comment": str,
-        "CreatedAt": datetime,
-        "DataSetId": str,
-        "Finalized": bool,
-        "Id": str,
-        "SourceId": str,
-        "UpdatedAt": datetime,
-        "RevocationComment": str,
-        "Revoked": bool,
-        "RevokedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateS3DataAccessFromS3BucketRequestDetailsTypeDef = TypedDict(
-    "CreateS3DataAccessFromS3BucketRequestDetailsTypeDef",
-    {
-        "AssetSource": S3DataAccessAssetSourceEntryTypeDef,
-        "DataSetId": str,
-        "RevisionId": str,
-    },
-)
-
-CreateS3DataAccessFromS3BucketResponseDetailsTypeDef = TypedDict(
-    "CreateS3DataAccessFromS3BucketResponseDetailsTypeDef",
-    {
-        "AssetSource": S3DataAccessAssetSourceEntryTypeDef,
-        "DataSetId": str,
-        "RevisionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DatabaseLFTagPolicyAndPermissionsTypeDef = TypedDict(
     "DatabaseLFTagPolicyAndPermissionsTypeDef",
     {
         "Expression": Sequence[LFTagTypeDef],
@@ -1201,89 +1218,64 @@
     {
         "AssetSources": List[RedshiftDataShareAssetSourceEntryTypeDef],
         "DataSetId": str,
         "RevisionId": str,
     },
 )
 
-_RequiredListDataSetRevisionsRequestListDataSetRevisionsPaginateTypeDef = TypedDict(
-    "_RequiredListDataSetRevisionsRequestListDataSetRevisionsPaginateTypeDef",
+_RequiredS3DataAccessAssetSourceEntryTypeDef = TypedDict(
+    "_RequiredS3DataAccessAssetSourceEntryTypeDef",
     {
-        "DataSetId": str,
+        "Bucket": str,
     },
 )
-_OptionalListDataSetRevisionsRequestListDataSetRevisionsPaginateTypeDef = TypedDict(
-    "_OptionalListDataSetRevisionsRequestListDataSetRevisionsPaginateTypeDef",
+_OptionalS3DataAccessAssetSourceEntryTypeDef = TypedDict(
+    "_OptionalS3DataAccessAssetSourceEntryTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "KeyPrefixes": Sequence[str],
+        "Keys": Sequence[str],
+        "KmsKeysToGrant": Sequence[KmsKeyToGrantTypeDef],
     },
     total=False,
 )
 
-class ListDataSetRevisionsRequestListDataSetRevisionsPaginateTypeDef(
-    _RequiredListDataSetRevisionsRequestListDataSetRevisionsPaginateTypeDef,
-    _OptionalListDataSetRevisionsRequestListDataSetRevisionsPaginateTypeDef,
+class S3DataAccessAssetSourceEntryTypeDef(
+    _RequiredS3DataAccessAssetSourceEntryTypeDef, _OptionalS3DataAccessAssetSourceEntryTypeDef
 ):
     pass
 
-ListDataSetsRequestListDataSetsPaginateTypeDef = TypedDict(
-    "ListDataSetsRequestListDataSetsPaginateTypeDef",
-    {
-        "Origin": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListEventActionsRequestListEventActionsPaginateTypeDef = TypedDict(
-    "ListEventActionsRequestListEventActionsPaginateTypeDef",
-    {
-        "EventSourceId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListJobsRequestListJobsPaginateTypeDef = TypedDict(
-    "ListJobsRequestListJobsPaginateTypeDef",
-    {
-        "DataSetId": str,
-        "RevisionId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListRevisionAssetsRequestListRevisionAssetsPaginateTypeDef = TypedDict(
-    "_RequiredListRevisionAssetsRequestListRevisionAssetsPaginateTypeDef",
+_RequiredS3DataAccessAssetTypeDef = TypedDict(
+    "_RequiredS3DataAccessAssetTypeDef",
     {
-        "DataSetId": str,
-        "RevisionId": str,
+        "Bucket": str,
     },
 )
-_OptionalListRevisionAssetsRequestListRevisionAssetsPaginateTypeDef = TypedDict(
-    "_OptionalListRevisionAssetsRequestListRevisionAssetsPaginateTypeDef",
+_OptionalS3DataAccessAssetTypeDef = TypedDict(
+    "_OptionalS3DataAccessAssetTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "KeyPrefixes": List[str],
+        "Keys": List[str],
+        "S3AccessPointAlias": str,
+        "S3AccessPointArn": str,
+        "KmsKeysToGrant": List[KmsKeyToGrantTypeDef],
     },
     total=False,
 )
 
-class ListRevisionAssetsRequestListRevisionAssetsPaginateTypeDef(
-    _RequiredListRevisionAssetsRequestListRevisionAssetsPaginateTypeDef,
-    _OptionalListRevisionAssetsRequestListRevisionAssetsPaginateTypeDef,
+class S3DataAccessAssetTypeDef(
+    _RequiredS3DataAccessAssetTypeDef, _OptionalS3DataAccessAssetTypeDef
 ):
     pass
 
 ListDataSetRevisionsResponseTypeDef = TypedDict(
     "ListDataSetRevisionsResponseTypeDef",
     {
         "NextToken": str,
         "Revisions": List[RevisionEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ActionTypeDef = TypedDict(
     "ActionTypeDef",
     {
         "ExportRevisionToS3": AutoExportRevisionToS3RequestDetailsTypeDef,
@@ -1292,15 +1284,15 @@
 )
 
 ListDataSetsResponseTypeDef = TypedDict(
     "ListDataSetsResponseTypeDef",
     {
         "DataSets": List[DataSetEntryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredImportAssetsFromLakeFormationTagPolicyRequestDetailsTypeDef = TypedDict(
     "_RequiredImportAssetsFromLakeFormationTagPolicyRequestDetailsTypeDef",
     {
         "CatalogId": str,
@@ -1375,14 +1367,32 @@
     },
     total=False,
 )
 
 class JobErrorTypeDef(_RequiredJobErrorTypeDef, _OptionalJobErrorTypeDef):
     pass
 
+CreateS3DataAccessFromS3BucketRequestDetailsTypeDef = TypedDict(
+    "CreateS3DataAccessFromS3BucketRequestDetailsTypeDef",
+    {
+        "AssetSource": S3DataAccessAssetSourceEntryTypeDef,
+        "DataSetId": str,
+        "RevisionId": str,
+    },
+)
+
+CreateS3DataAccessFromS3BucketResponseDetailsTypeDef = TypedDict(
+    "CreateS3DataAccessFromS3BucketResponseDetailsTypeDef",
+    {
+        "AssetSource": S3DataAccessAssetSourceEntryTypeDef,
+        "DataSetId": str,
+        "RevisionId": str,
+    },
+)
+
 CreateEventActionRequestRequestTypeDef = TypedDict(
     "CreateEventActionRequestRequestTypeDef",
     {
         "Action": ActionTypeDef,
         "Event": EventTypeDef,
     },
 )
@@ -1392,15 +1402,15 @@
     {
         "Action": ActionTypeDef,
         "Arn": str,
         "CreatedAt": datetime,
         "Event": EventTypeDef,
         "Id": str,
         "UpdatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EventActionEntryTypeDef = TypedDict(
     "EventActionEntryTypeDef",
     {
         "Action": ActionTypeDef,
@@ -1417,15 +1427,15 @@
     {
         "Action": ActionTypeDef,
         "Arn": str,
         "CreatedAt": datetime,
         "Event": EventTypeDef,
         "Id": str,
         "UpdatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateEventActionRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateEventActionRequestRequestTypeDef",
     {
         "EventActionId": str,
@@ -1449,15 +1459,24 @@
     {
         "Action": ActionTypeDef,
         "Arn": str,
         "CreatedAt": datetime,
         "Event": EventTypeDef,
         "Id": str,
         "UpdatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+LFTagPolicyDetailsTypeDef = TypedDict(
+    "LFTagPolicyDetailsTypeDef",
+    {
+        "CatalogId": str,
+        "ResourceType": LFResourceTypeType,
+        "ResourceDetails": LFResourceDetailsTypeDef,
     },
 )
 
 RequestDetailsTypeDef = TypedDict(
     "RequestDetailsTypeDef",
     {
         "ExportAssetToSignedUrl": ExportAssetToSignedUrlRequestDetailsTypeDef,
@@ -1493,32 +1512,31 @@
         "ImportAssetsFromLakeFormationTagPolicy": (
             ImportAssetsFromLakeFormationTagPolicyResponseDetailsTypeDef
         ),
     },
     total=False,
 )
 
-LFTagPolicyDetailsTypeDef = TypedDict(
-    "LFTagPolicyDetailsTypeDef",
-    {
-        "CatalogId": str,
-        "ResourceType": LFResourceTypeType,
-        "ResourceDetails": LFResourceDetailsTypeDef,
-    },
-)
-
 ListEventActionsResponseTypeDef = TypedDict(
     "ListEventActionsResponseTypeDef",
     {
         "EventActions": List[EventActionEntryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
+LakeFormationDataPermissionDetailsTypeDef = TypedDict(
+    "LakeFormationDataPermissionDetailsTypeDef",
+    {
+        "LFTagPolicy": LFTagPolicyDetailsTypeDef,
+    },
+    total=False,
+)
+
 CreateJobRequestRequestTypeDef = TypedDict(
     "CreateJobRequestRequestTypeDef",
     {
         "Details": RequestDetailsTypeDef,
         "Type": TypeType,
     },
 )
@@ -1530,30 +1548,30 @@
         "CreatedAt": datetime,
         "Details": ResponseDetailsTypeDef,
         "Errors": List[JobErrorTypeDef],
         "Id": str,
         "State": StateType,
         "Type": TypeType,
         "UpdatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetJobResponseTypeDef = TypedDict(
     "GetJobResponseTypeDef",
     {
         "Arn": str,
         "CreatedAt": datetime,
         "Details": ResponseDetailsTypeDef,
         "Errors": List[JobErrorTypeDef],
         "Id": str,
         "State": StateType,
         "Type": TypeType,
         "UpdatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredJobEntryTypeDef = TypedDict(
     "_RequiredJobEntryTypeDef",
     {
         "Arn": str,
@@ -1572,31 +1590,14 @@
     },
     total=False,
 )
 
 class JobEntryTypeDef(_RequiredJobEntryTypeDef, _OptionalJobEntryTypeDef):
     pass
 
-LakeFormationDataPermissionDetailsTypeDef = TypedDict(
-    "LakeFormationDataPermissionDetailsTypeDef",
-    {
-        "LFTagPolicy": LFTagPolicyDetailsTypeDef,
-    },
-    total=False,
-)
-
-ListJobsResponseTypeDef = TypedDict(
-    "ListJobsResponseTypeDef",
-    {
-        "Jobs": List[JobEntryTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 _RequiredLakeFormationDataPermissionAssetTypeDef = TypedDict(
     "_RequiredLakeFormationDataPermissionAssetTypeDef",
     {
         "LakeFormationDataPermissionDetails": LakeFormationDataPermissionDetailsTypeDef,
         "LakeFormationDataPermissionType": Literal["LFTagPolicy"],
         "Permissions": List[LFPermissionType],
     },
@@ -1611,14 +1612,23 @@
 
 class LakeFormationDataPermissionAssetTypeDef(
     _RequiredLakeFormationDataPermissionAssetTypeDef,
     _OptionalLakeFormationDataPermissionAssetTypeDef,
 ):
     pass
 
+ListJobsResponseTypeDef = TypedDict(
+    "ListJobsResponseTypeDef",
+    {
+        "Jobs": List[JobEntryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AssetDetailsTypeDef = TypedDict(
     "AssetDetailsTypeDef",
     {
         "S3SnapshotAsset": S3SnapshotAssetTypeDef,
         "RedshiftDataShareAsset": RedshiftDataShareAssetTypeDef,
         "ApiGatewayApiAsset": ApiGatewayApiAssetTypeDef,
         "S3DataAccessAsset": S3DataAccessAssetTypeDef,
@@ -1661,15 +1671,15 @@
         "CreatedAt": datetime,
         "DataSetId": str,
         "Id": str,
         "Name": str,
         "RevisionId": str,
         "SourceId": str,
         "UpdatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAssetResponseTypeDef = TypedDict(
     "UpdateAssetResponseTypeDef",
     {
         "Arn": str,
@@ -1678,19 +1688,19 @@
         "CreatedAt": datetime,
         "DataSetId": str,
         "Id": str,
         "Name": str,
         "RevisionId": str,
         "SourceId": str,
         "UpdatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRevisionAssetsResponseTypeDef = TypedDict(
     "ListRevisionAssetsResponseTypeDef",
     {
         "Assets": List[AssetEntryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-dataexchange-2.5.0.post1/types_aiobotocore_dataexchange.egg-info/PKG-INFO` & `types-aiobotocore-dataexchange-2.5.1/types_aiobotocore_dataexchange.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-dataexchange
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.DataExchange 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.DataExchange 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dataexchange/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-dataexchange"></a>
 
 # types-aiobotocore-dataexchange
 
 [![PyPI - types-aiobotocore-dataexchange](https://img.shields.io/pypi/v/types-aiobotocore-dataexchange.svg?color=blue)](https://pypi.org/project/types-aiobotocore-dataexchange)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-dataexchange.svg?color=blue)](https://pypi.org/project/types-aiobotocore-dataexchange)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dataexchange/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-dataexchange?color=blue)](https://pypistats.org/packages/types-aiobotocore-dataexchange)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.DataExchange 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dataexchange.html#DataExchange)
+[aiobotocore.DataExchange 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dataexchange.html#DataExchange)
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
 [types-aiobotocore-dataexchange docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dataexchange/).
 
 See how it helps to find and fix potential bugs:
 
@@ -351,118 +351,119 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_dataexchange.type_defs import (
     ApiGatewayApiAssetTypeDef,
     AssetDestinationEntryTypeDef,
     RedshiftDataShareAssetTypeDef,
-    S3DataAccessAssetTypeDef,
     S3SnapshotAssetTypeDef,
     AssetSourceEntryTypeDef,
     AutoExportRevisionDestinationEntryTypeDef,
     ExportServerSideEncryptionTypeDef,
     CancelJobRequestRequestTypeDef,
     CreateDataSetRequestRequestTypeDef,
     OriginDetailsTypeDef,
-    ResponseMetadataTypeDef,
     CreateRevisionRequestRequestTypeDef,
-    S3DataAccessAssetSourceEntryTypeDef,
+    CreateRevisionResponseTypeDef,
     LFTagTypeDef,
     DeleteAssetRequestRequestTypeDef,
     DeleteDataSetRequestRequestTypeDef,
     DeleteEventActionRequestRequestTypeDef,
     DeleteRevisionRequestRequestTypeDef,
     ImportAssetFromSignedUrlJobErrorDetailsTypeDef,
+    EmptyResponseMetadataTypeDef,
     RevisionPublishedTypeDef,
     ExportAssetToSignedUrlRequestDetailsTypeDef,
     ExportAssetToSignedUrlResponseDetailsTypeDef,
     RevisionDestinationEntryTypeDef,
     GetAssetRequestRequestTypeDef,
     GetDataSetRequestRequestTypeDef,
     GetEventActionRequestRequestTypeDef,
     GetJobRequestRequestTypeDef,
     GetRevisionRequestRequestTypeDef,
+    GetRevisionResponseTypeDef,
     ImportAssetFromApiGatewayApiRequestDetailsTypeDef,
     ImportAssetFromApiGatewayApiResponseDetailsTypeDef,
     ImportAssetFromSignedUrlRequestDetailsTypeDef,
     ImportAssetFromSignedUrlResponseDetailsTypeDef,
     RedshiftDataShareAssetSourceEntryTypeDef,
-    PaginatorConfigTypeDef,
+    KmsKeyToGrantTypeDef,
+    ListDataSetRevisionsRequestListDataSetRevisionsPaginateTypeDef,
     ListDataSetRevisionsRequestRequestTypeDef,
     RevisionEntryTypeDef,
+    ListDataSetsRequestListDataSetsPaginateTypeDef,
     ListDataSetsRequestRequestTypeDef,
+    ListEventActionsRequestListEventActionsPaginateTypeDef,
     ListEventActionsRequestRequestTypeDef,
+    ListJobsRequestListJobsPaginateTypeDef,
     ListJobsRequestRequestTypeDef,
+    ListRevisionAssetsRequestListRevisionAssetsPaginateTypeDef,
     ListRevisionAssetsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     RevokeRevisionRequestRequestTypeDef,
+    RevokeRevisionResponseTypeDef,
     SendApiAssetRequestRequestTypeDef,
+    SendApiAssetResponseTypeDef,
     StartJobRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateAssetRequestRequestTypeDef,
     UpdateDataSetRequestRequestTypeDef,
     UpdateRevisionRequestRequestTypeDef,
+    UpdateRevisionResponseTypeDef,
     ImportAssetsFromS3RequestDetailsTypeDef,
     ImportAssetsFromS3ResponseDetailsTypeDef,
     AutoExportRevisionToS3RequestDetailsTypeDef,
     ExportAssetsToS3RequestDetailsTypeDef,
     ExportAssetsToS3ResponseDetailsTypeDef,
-    DataSetEntryTypeDef,
     CreateDataSetResponseTypeDef,
-    CreateRevisionResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
+    DataSetEntryTypeDef,
     GetDataSetResponseTypeDef,
-    GetRevisionResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    RevokeRevisionResponseTypeDef,
-    SendApiAssetResponseTypeDef,
     UpdateDataSetResponseTypeDef,
-    UpdateRevisionResponseTypeDef,
-    CreateS3DataAccessFromS3BucketRequestDetailsTypeDef,
-    CreateS3DataAccessFromS3BucketResponseDetailsTypeDef,
     DatabaseLFTagPolicyAndPermissionsTypeDef,
     DatabaseLFTagPolicyTypeDef,
     TableLFTagPolicyAndPermissionsTypeDef,
     TableLFTagPolicyTypeDef,
     DetailsTypeDef,
     EventTypeDef,
     ExportRevisionsToS3RequestDetailsTypeDef,
     ExportRevisionsToS3ResponseDetailsTypeDef,
     ImportAssetsFromRedshiftDataSharesRequestDetailsTypeDef,
     ImportAssetsFromRedshiftDataSharesResponseDetailsTypeDef,
-    ListDataSetRevisionsRequestListDataSetRevisionsPaginateTypeDef,
-    ListDataSetsRequestListDataSetsPaginateTypeDef,
-    ListEventActionsRequestListEventActionsPaginateTypeDef,
-    ListJobsRequestListJobsPaginateTypeDef,
-    ListRevisionAssetsRequestListRevisionAssetsPaginateTypeDef,
+    S3DataAccessAssetSourceEntryTypeDef,
+    S3DataAccessAssetTypeDef,
     ListDataSetRevisionsResponseTypeDef,
     ActionTypeDef,
     ListDataSetsResponseTypeDef,
     ImportAssetsFromLakeFormationTagPolicyRequestDetailsTypeDef,
     ImportAssetsFromLakeFormationTagPolicyResponseDetailsTypeDef,
     LFResourceDetailsTypeDef,
     JobErrorTypeDef,
+    CreateS3DataAccessFromS3BucketRequestDetailsTypeDef,
+    CreateS3DataAccessFromS3BucketResponseDetailsTypeDef,
     CreateEventActionRequestRequestTypeDef,
     CreateEventActionResponseTypeDef,
     EventActionEntryTypeDef,
     GetEventActionResponseTypeDef,
     UpdateEventActionRequestRequestTypeDef,
     UpdateEventActionResponseTypeDef,
+    LFTagPolicyDetailsTypeDef,
     RequestDetailsTypeDef,
     ResponseDetailsTypeDef,
-    LFTagPolicyDetailsTypeDef,
     ListEventActionsResponseTypeDef,
+    LakeFormationDataPermissionDetailsTypeDef,
     CreateJobRequestRequestTypeDef,
     CreateJobResponseTypeDef,
     GetJobResponseTypeDef,
     JobEntryTypeDef,
-    LakeFormationDataPermissionDetailsTypeDef,
-    ListJobsResponseTypeDef,
     LakeFormationDataPermissionAssetTypeDef,
+    ListJobsResponseTypeDef,
     AssetDetailsTypeDef,
     AssetEntryTypeDef,
     GetAssetResponseTypeDef,
     UpdateAssetResponseTypeDef,
     ListRevisionAssetsResponseTypeDef,
 )
 
@@ -474,43 +475,43 @@
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

### Comparing `types-aiobotocore-dataexchange-2.5.0.post1/types_aiobotocore_dataexchange.egg-info/SOURCES.txt` & `types-aiobotocore-dataexchange-2.5.1/types_aiobotocore_dataexchange.egg-info/SOURCES.txt`

 * *Files identical despite different names*

