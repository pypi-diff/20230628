# Comparing `tmp/types-aiobotocore-ecr-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-ecr-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-ecr-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:34 2023, max compression
+gzip compressed data, was "types-aiobotocore-ecr-2.5.1.tar", last modified: Wed Jun 28 01:43:26 2023, max compression
```

## Comparing `types-aiobotocore-ecr-2.5.0.post1.tar` & `types-aiobotocore-ecr-2.5.1.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:34.195170 types-aiobotocore-ecr-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:13:45.000000 types-aiobotocore-ecr-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    20523 2023-03-11 12:26:34.195170 types-aiobotocore-ecr-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    18968 2023-03-11 12:13:45.000000 types-aiobotocore-ecr-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:34.195170 types-aiobotocore-ecr-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2072 2023-03-11 12:13:45.000000 types-aiobotocore-ecr-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:34.187170 types-aiobotocore-ecr-2.5.0.post1/types_aiobotocore_ecr/
--rw-r--r--   0 runner    (1001) docker     (123)     2313 2023-03-11 12:13:45.000000 types-aiobotocore-ecr-2.5.0.post1/types_aiobotocore_ecr/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2312 2023-03-11 12:13:45.000000 types-aiobotocore-ecr-2.5.0.post1/types_aiobotocore_ecr/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      916 2023-03-11 12:13:45.000000 types-aiobotocore-ecr-2.5.0.post1/types_aiobotocore_ecr/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    35776 2023-03-11 12:13:45.000000 types-aiobotocore-ecr-2.5.0.post1/types_aiobotocore_ecr/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    35718 2023-03-11 12:13:45.000000 types-aiobotocore-ecr-2.5.0.post1/types_aiobotocore_ecr/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10901 2023-03-11 12:13:46.000000 types-aiobotocore-ecr-2.5.0.post1/types_aiobotocore_ecr/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    10899 2023-03-11 12:13:45.000000 types-aiobotocore-ecr-2.5.0.post1/types_aiobotocore_ecr/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8669 2023-03-11 12:13:45.000000 types-aiobotocore-ecr-2.5.0.post1/types_aiobotocore_ecr/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     8660 2023-03-11 12:13:45.000000 types-aiobotocore-ecr-2.5.0.post1/types_aiobotocore_ecr/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:13:45.000000 types-aiobotocore-ecr-2.5.0.post1/types_aiobotocore_ecr/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    51900 2023-03-11 12:13:47.000000 types-aiobotocore-ecr-2.5.0.post1/types_aiobotocore_ecr/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    51827 2023-03-11 12:13:46.000000 types-aiobotocore-ecr-2.5.0.post1/types_aiobotocore_ecr/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:13:45.000000 types-aiobotocore-ecr-2.5.0.post1/types_aiobotocore_ecr/version.py
--rw-r--r--   0 runner    (1001) docker     (123)     3106 2023-03-11 12:13:45.000000 types-aiobotocore-ecr-2.5.0.post1/types_aiobotocore_ecr/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)     3104 2023-03-11 12:13:45.000000 types-aiobotocore-ecr-2.5.0.post1/types_aiobotocore_ecr/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:34.195170 types-aiobotocore-ecr-2.5.0.post1/types_aiobotocore_ecr.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    20523 2023-03-11 12:26:34.000000 types-aiobotocore-ecr-2.5.0.post1/types_aiobotocore_ecr.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      802 2023-03-11 12:26:34.000000 types-aiobotocore-ecr-2.5.0.post1/types_aiobotocore_ecr.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:34.000000 types-aiobotocore-ecr-2.5.0.post1/types_aiobotocore_ecr.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:34.000000 types-aiobotocore-ecr-2.5.0.post1/types_aiobotocore_ecr.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:34.000000 types-aiobotocore-ecr-2.5.0.post1/types_aiobotocore_ecr.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-03-11 12:26:34.000000 types-aiobotocore-ecr-2.5.0.post1/types_aiobotocore_ecr.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:26.142130 types-aiobotocore-ecr-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:30:22.000000 types-aiobotocore-ecr-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    20511 2023-06-28 01:43:26.134130 types-aiobotocore-ecr-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    18962 2023-06-28 01:30:22.000000 types-aiobotocore-ecr-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:26.142130 types-aiobotocore-ecr-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2066 2023-06-28 01:30:22.000000 types-aiobotocore-ecr-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:26.134130 types-aiobotocore-ecr-2.5.1/types_aiobotocore_ecr/
+-rw-r--r--   0 runner    (1001) docker     (123)     2313 2023-06-28 01:30:22.000000 types-aiobotocore-ecr-2.5.1/types_aiobotocore_ecr/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2312 2023-06-28 01:30:22.000000 types-aiobotocore-ecr-2.5.1/types_aiobotocore_ecr/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      904 2023-06-28 01:30:22.000000 types-aiobotocore-ecr-2.5.1/types_aiobotocore_ecr/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    35776 2023-06-28 01:30:22.000000 types-aiobotocore-ecr-2.5.1/types_aiobotocore_ecr/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    35718 2023-06-28 01:30:22.000000 types-aiobotocore-ecr-2.5.1/types_aiobotocore_ecr/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    11110 2023-06-28 01:30:23.000000 types-aiobotocore-ecr-2.5.1/types_aiobotocore_ecr/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11108 2023-06-28 01:30:22.000000 types-aiobotocore-ecr-2.5.1/types_aiobotocore_ecr/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8561 2023-06-28 01:30:22.000000 types-aiobotocore-ecr-2.5.1/types_aiobotocore_ecr/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8553 2023-06-28 01:30:22.000000 types-aiobotocore-ecr-2.5.1/types_aiobotocore_ecr/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:30:22.000000 types-aiobotocore-ecr-2.5.1/types_aiobotocore_ecr/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    51990 2023-06-28 01:30:24.000000 types-aiobotocore-ecr-2.5.1/types_aiobotocore_ecr/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    51917 2023-06-28 01:30:23.000000 types-aiobotocore-ecr-2.5.1/types_aiobotocore_ecr/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:30:22.000000 types-aiobotocore-ecr-2.5.1/types_aiobotocore_ecr/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3106 2023-06-28 01:30:22.000000 types-aiobotocore-ecr-2.5.1/types_aiobotocore_ecr/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3104 2023-06-28 01:30:22.000000 types-aiobotocore-ecr-2.5.1/types_aiobotocore_ecr/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:26.134130 types-aiobotocore-ecr-2.5.1/types_aiobotocore_ecr.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    20511 2023-06-28 01:43:25.000000 types-aiobotocore-ecr-2.5.1/types_aiobotocore_ecr.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      802 2023-06-28 01:43:25.000000 types-aiobotocore-ecr-2.5.1/types_aiobotocore_ecr.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:25.000000 types-aiobotocore-ecr-2.5.1/types_aiobotocore_ecr.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:25.000000 types-aiobotocore-ecr-2.5.1/types_aiobotocore_ecr.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:25.000000 types-aiobotocore-ecr-2.5.1/types_aiobotocore_ecr.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 01:43:25.000000 types-aiobotocore-ecr-2.5.1/types_aiobotocore_ecr.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-ecr-2.5.0.post1/LICENSE` & `types-aiobotocore-ecr-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-ecr-2.5.0.post1/PKG-INFO` & `types-aiobotocore-ecr-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-ecr
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ECR 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ECR 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-ecr"></a>
 
 # types-aiobotocore-ecr
 
 [![PyPI - types-aiobotocore-ecr](https://img.shields.io/pypi/v/types-aiobotocore-ecr.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ecr)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-ecr.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ecr)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-ecr?color=blue)](https://pypistats.org/packages/types-aiobotocore-ecr)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ECR 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR)
+[aiobotocore.ECR 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR)
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
 [types-aiobotocore-ecr docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr/).
 
 See how it helps to find and fix potential bugs:
 
@@ -391,101 +391,101 @@
 from types_aiobotocore_ecr.type_defs import (
     AttributeTypeDef,
     AuthorizationDataTypeDef,
     AwsEcrContainerImageDetailsTypeDef,
     BatchCheckLayerAvailabilityRequestRequestTypeDef,
     LayerFailureTypeDef,
     LayerTypeDef,
-    ResponseMetadataTypeDef,
     ImageIdentifierTypeDef,
     BatchGetRepositoryScanningConfigurationRequestRequestTypeDef,
     RepositoryScanningConfigurationFailureTypeDef,
     CompleteLayerUploadRequestRequestTypeDef,
+    CompleteLayerUploadResponseTypeDef,
     CreatePullThroughCacheRuleRequestRequestTypeDef,
+    CreatePullThroughCacheRuleResponseTypeDef,
     EncryptionConfigurationTypeDef,
     ImageScanningConfigurationTypeDef,
     TagTypeDef,
     CvssScoreAdjustmentTypeDef,
     CvssScoreTypeDef,
     DeleteLifecyclePolicyRequestRequestTypeDef,
+    DeleteLifecyclePolicyResponseTypeDef,
     DeletePullThroughCacheRuleRequestRequestTypeDef,
+    DeletePullThroughCacheRuleResponseTypeDef,
+    DeleteRegistryPolicyResponseTypeDef,
     DeleteRepositoryPolicyRequestRequestTypeDef,
+    DeleteRepositoryPolicyResponseTypeDef,
     DeleteRepositoryRequestRequestTypeDef,
     ImageReplicationStatusTypeDef,
-    PaginatorConfigTypeDef,
     WaiterConfigTypeDef,
     ImageScanStatusTypeDef,
     DescribeImagesFilterTypeDef,
+    DescribePullThroughCacheRulesRequestDescribePullThroughCacheRulesPaginateTypeDef,
     DescribePullThroughCacheRulesRequestRequestTypeDef,
     PullThroughCacheRuleTypeDef,
+    DescribeRepositoriesRequestDescribeRepositoriesPaginateTypeDef,
     DescribeRepositoriesRequestRequestTypeDef,
     GetAuthorizationTokenRequestRequestTypeDef,
     GetDownloadUrlForLayerRequestRequestTypeDef,
+    GetDownloadUrlForLayerResponseTypeDef,
     LifecyclePolicyPreviewFilterTypeDef,
     LifecyclePolicyPreviewSummaryTypeDef,
     GetLifecyclePolicyRequestRequestTypeDef,
+    GetLifecyclePolicyResponseTypeDef,
+    GetRegistryPolicyResponseTypeDef,
     GetRepositoryPolicyRequestRequestTypeDef,
+    GetRepositoryPolicyResponseTypeDef,
     ImageScanFindingsSummaryTypeDef,
     InitiateLayerUploadRequestRequestTypeDef,
+    InitiateLayerUploadResponseTypeDef,
     LifecyclePolicyRuleActionTypeDef,
     ListImagesFilterTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     VulnerablePackageTypeDef,
+    PaginatorConfigTypeDef,
     PutImageRequestRequestTypeDef,
     PutImageTagMutabilityRequestRequestTypeDef,
+    PutImageTagMutabilityResponseTypeDef,
     PutLifecyclePolicyRequestRequestTypeDef,
+    PutLifecyclePolicyResponseTypeDef,
     PutRegistryPolicyRequestRequestTypeDef,
+    PutRegistryPolicyResponseTypeDef,
     RecommendationTypeDef,
     ScanningRepositoryFilterTypeDef,
     ReplicationDestinationTypeDef,
     RepositoryFilterTypeDef,
+    ResponseMetadataTypeDef,
     SetRepositoryPolicyRequestRequestTypeDef,
+    SetRepositoryPolicyResponseTypeDef,
     StartLifecyclePolicyPreviewRequestRequestTypeDef,
+    StartLifecyclePolicyPreviewResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UploadLayerPartRequestRequestTypeDef,
+    UploadLayerPartResponseTypeDef,
     ImageScanFindingTypeDef,
+    GetAuthorizationTokenResponseTypeDef,
     ResourceDetailsTypeDef,
     BatchCheckLayerAvailabilityResponseTypeDef,
-    CompleteLayerUploadResponseTypeDef,
-    CreatePullThroughCacheRuleResponseTypeDef,
-    DeleteLifecyclePolicyResponseTypeDef,
-    DeletePullThroughCacheRuleResponseTypeDef,
-    DeleteRegistryPolicyResponseTypeDef,
-    DeleteRepositoryPolicyResponseTypeDef,
-    GetAuthorizationTokenResponseTypeDef,
-    GetDownloadUrlForLayerResponseTypeDef,
-    GetLifecyclePolicyResponseTypeDef,
-    GetRegistryPolicyResponseTypeDef,
-    GetRepositoryPolicyResponseTypeDef,
-    InitiateLayerUploadResponseTypeDef,
-    PutImageTagMutabilityResponseTypeDef,
-    PutLifecyclePolicyResponseTypeDef,
-    PutRegistryPolicyResponseTypeDef,
-    SetRepositoryPolicyResponseTypeDef,
-    StartLifecyclePolicyPreviewResponseTypeDef,
-    UploadLayerPartResponseTypeDef,
     BatchDeleteImageRequestRequestTypeDef,
     BatchGetImageRequestRequestTypeDef,
     DescribeImageReplicationStatusRequestRequestTypeDef,
+    DescribeImageScanFindingsRequestDescribeImageScanFindingsPaginateTypeDef,
     DescribeImageScanFindingsRequestRequestTypeDef,
     ImageFailureTypeDef,
     ImageTypeDef,
     ListImagesResponseTypeDef,
     StartImageScanRequestRequestTypeDef,
     PutImageScanningConfigurationRequestRequestTypeDef,
     PutImageScanningConfigurationResponseTypeDef,
     RepositoryTypeDef,
     CreateRepositoryRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     CvssScoreDetailsTypeDef,
     DescribeImageReplicationStatusResponseTypeDef,
-    DescribeImageScanFindingsRequestDescribeImageScanFindingsPaginateTypeDef,
-    DescribePullThroughCacheRulesRequestDescribePullThroughCacheRulesPaginateTypeDef,
-    DescribeRepositoriesRequestDescribeRepositoriesPaginateTypeDef,
     DescribeImageScanFindingsRequestImageScanCompleteWaitTypeDef,
     StartImageScanResponseTypeDef,
     DescribeImagesRequestDescribeImagesPaginateTypeDef,
     DescribeImagesRequestRequestTypeDef,
     DescribePullThroughCacheRulesResponseTypeDef,
     GetLifecyclePolicyPreviewRequestGetLifecyclePolicyPreviewPaginateTypeDef,
     GetLifecyclePolicyPreviewRequestLifecyclePolicyPreviewCompleteWaitTypeDef,
@@ -531,43 +531,43 @@
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

### Comparing `types-aiobotocore-ecr-2.5.0.post1/README.md` & `types-aiobotocore-ecr-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-ecr"></a>
 
 # types-aiobotocore-ecr
 
 [![PyPI - types-aiobotocore-ecr](https://img.shields.io/pypi/v/types-aiobotocore-ecr.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ecr)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-ecr.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ecr)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-ecr?color=blue)](https://pypistats.org/packages/types-aiobotocore-ecr)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ECR 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR)
+[aiobotocore.ECR 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR)
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
 [types-aiobotocore-ecr docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr/).
 
 See how it helps to find and fix potential bugs:
 
@@ -358,101 +358,101 @@
 from types_aiobotocore_ecr.type_defs import (
     AttributeTypeDef,
     AuthorizationDataTypeDef,
     AwsEcrContainerImageDetailsTypeDef,
     BatchCheckLayerAvailabilityRequestRequestTypeDef,
     LayerFailureTypeDef,
     LayerTypeDef,
-    ResponseMetadataTypeDef,
     ImageIdentifierTypeDef,
     BatchGetRepositoryScanningConfigurationRequestRequestTypeDef,
     RepositoryScanningConfigurationFailureTypeDef,
     CompleteLayerUploadRequestRequestTypeDef,
+    CompleteLayerUploadResponseTypeDef,
     CreatePullThroughCacheRuleRequestRequestTypeDef,
+    CreatePullThroughCacheRuleResponseTypeDef,
     EncryptionConfigurationTypeDef,
     ImageScanningConfigurationTypeDef,
     TagTypeDef,
     CvssScoreAdjustmentTypeDef,
     CvssScoreTypeDef,
     DeleteLifecyclePolicyRequestRequestTypeDef,
+    DeleteLifecyclePolicyResponseTypeDef,
     DeletePullThroughCacheRuleRequestRequestTypeDef,
+    DeletePullThroughCacheRuleResponseTypeDef,
+    DeleteRegistryPolicyResponseTypeDef,
     DeleteRepositoryPolicyRequestRequestTypeDef,
+    DeleteRepositoryPolicyResponseTypeDef,
     DeleteRepositoryRequestRequestTypeDef,
     ImageReplicationStatusTypeDef,
-    PaginatorConfigTypeDef,
     WaiterConfigTypeDef,
     ImageScanStatusTypeDef,
     DescribeImagesFilterTypeDef,
+    DescribePullThroughCacheRulesRequestDescribePullThroughCacheRulesPaginateTypeDef,
     DescribePullThroughCacheRulesRequestRequestTypeDef,
     PullThroughCacheRuleTypeDef,
+    DescribeRepositoriesRequestDescribeRepositoriesPaginateTypeDef,
     DescribeRepositoriesRequestRequestTypeDef,
     GetAuthorizationTokenRequestRequestTypeDef,
     GetDownloadUrlForLayerRequestRequestTypeDef,
+    GetDownloadUrlForLayerResponseTypeDef,
     LifecyclePolicyPreviewFilterTypeDef,
     LifecyclePolicyPreviewSummaryTypeDef,
     GetLifecyclePolicyRequestRequestTypeDef,
+    GetLifecyclePolicyResponseTypeDef,
+    GetRegistryPolicyResponseTypeDef,
     GetRepositoryPolicyRequestRequestTypeDef,
+    GetRepositoryPolicyResponseTypeDef,
     ImageScanFindingsSummaryTypeDef,
     InitiateLayerUploadRequestRequestTypeDef,
+    InitiateLayerUploadResponseTypeDef,
     LifecyclePolicyRuleActionTypeDef,
     ListImagesFilterTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     VulnerablePackageTypeDef,
+    PaginatorConfigTypeDef,
     PutImageRequestRequestTypeDef,
     PutImageTagMutabilityRequestRequestTypeDef,
+    PutImageTagMutabilityResponseTypeDef,
     PutLifecyclePolicyRequestRequestTypeDef,
+    PutLifecyclePolicyResponseTypeDef,
     PutRegistryPolicyRequestRequestTypeDef,
+    PutRegistryPolicyResponseTypeDef,
     RecommendationTypeDef,
     ScanningRepositoryFilterTypeDef,
     ReplicationDestinationTypeDef,
     RepositoryFilterTypeDef,
+    ResponseMetadataTypeDef,
     SetRepositoryPolicyRequestRequestTypeDef,
+    SetRepositoryPolicyResponseTypeDef,
     StartLifecyclePolicyPreviewRequestRequestTypeDef,
+    StartLifecyclePolicyPreviewResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UploadLayerPartRequestRequestTypeDef,
+    UploadLayerPartResponseTypeDef,
     ImageScanFindingTypeDef,
+    GetAuthorizationTokenResponseTypeDef,
     ResourceDetailsTypeDef,
     BatchCheckLayerAvailabilityResponseTypeDef,
-    CompleteLayerUploadResponseTypeDef,
-    CreatePullThroughCacheRuleResponseTypeDef,
-    DeleteLifecyclePolicyResponseTypeDef,
-    DeletePullThroughCacheRuleResponseTypeDef,
-    DeleteRegistryPolicyResponseTypeDef,
-    DeleteRepositoryPolicyResponseTypeDef,
-    GetAuthorizationTokenResponseTypeDef,
-    GetDownloadUrlForLayerResponseTypeDef,
-    GetLifecyclePolicyResponseTypeDef,
-    GetRegistryPolicyResponseTypeDef,
-    GetRepositoryPolicyResponseTypeDef,
-    InitiateLayerUploadResponseTypeDef,
-    PutImageTagMutabilityResponseTypeDef,
-    PutLifecyclePolicyResponseTypeDef,
-    PutRegistryPolicyResponseTypeDef,
-    SetRepositoryPolicyResponseTypeDef,
-    StartLifecyclePolicyPreviewResponseTypeDef,
-    UploadLayerPartResponseTypeDef,
     BatchDeleteImageRequestRequestTypeDef,
     BatchGetImageRequestRequestTypeDef,
     DescribeImageReplicationStatusRequestRequestTypeDef,
+    DescribeImageScanFindingsRequestDescribeImageScanFindingsPaginateTypeDef,
     DescribeImageScanFindingsRequestRequestTypeDef,
     ImageFailureTypeDef,
     ImageTypeDef,
     ListImagesResponseTypeDef,
     StartImageScanRequestRequestTypeDef,
     PutImageScanningConfigurationRequestRequestTypeDef,
     PutImageScanningConfigurationResponseTypeDef,
     RepositoryTypeDef,
     CreateRepositoryRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     CvssScoreDetailsTypeDef,
     DescribeImageReplicationStatusResponseTypeDef,
-    DescribeImageScanFindingsRequestDescribeImageScanFindingsPaginateTypeDef,
-    DescribePullThroughCacheRulesRequestDescribePullThroughCacheRulesPaginateTypeDef,
-    DescribeRepositoriesRequestDescribeRepositoriesPaginateTypeDef,
     DescribeImageScanFindingsRequestImageScanCompleteWaitTypeDef,
     StartImageScanResponseTypeDef,
     DescribeImagesRequestDescribeImagesPaginateTypeDef,
     DescribeImagesRequestRequestTypeDef,
     DescribePullThroughCacheRulesResponseTypeDef,
     GetLifecyclePolicyPreviewRequestGetLifecyclePolicyPreviewPaginateTypeDef,
     GetLifecyclePolicyPreviewRequestLifecyclePolicyPreviewCompleteWaitTypeDef,
@@ -498,43 +498,43 @@
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

### Comparing `types-aiobotocore-ecr-2.5.0.post1/setup.py` & `types-aiobotocore-ecr-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-ecr.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-ecr",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_ecr"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.ECR 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.ECR 2.5.1 service generated with mypy-boto3-builder"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr/",
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

### Comparing `types-aiobotocore-ecr-2.5.0.post1/types_aiobotocore_ecr/__init__.py` & `types-aiobotocore-ecr-2.5.1/types_aiobotocore_ecr/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ecr-2.5.0.post1/types_aiobotocore_ecr/__init__.pyi` & `types-aiobotocore-ecr-2.5.1/types_aiobotocore_ecr/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ecr-2.5.0.post1/types_aiobotocore_ecr/__main__.py` & `types-aiobotocore-ecr-2.5.1/types_aiobotocore_ecr/__main__.py`

 * *Files 5% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.ECR 2.5.0\nVersion:         2.5.0.post1\nBuilder version:"
-        " 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.ECR 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr//\nBoto3 docs:    "
         "  https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR\nOther"
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

### Comparing `types-aiobotocore-ecr-2.5.0.post1/types_aiobotocore_ecr/client.py` & `types-aiobotocore-ecr-2.5.1/types_aiobotocore_ecr/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ecr-2.5.0.post1/types_aiobotocore_ecr/client.pyi` & `types-aiobotocore-ecr-2.5.1/types_aiobotocore_ecr/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ecr-2.5.0.post1/types_aiobotocore_ecr/literals.py` & `types-aiobotocore-ecr-2.5.1/types_aiobotocore_ecr/literals.py`

 * *Files 8% similar despite different names*

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

### Comparing `types-aiobotocore-ecr-2.5.0.post1/types_aiobotocore_ecr/literals.pyi` & `types-aiobotocore-ecr-2.5.1/types_aiobotocore_ecr/literals.pyi`

 * *Files 8% similar despite different names*

```diff
@@ -151,14 +151,15 @@
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
@@ -237,14 +238,15 @@
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
@@ -255,14 +257,15 @@
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
@@ -298,14 +301,15 @@
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
@@ -324,16 +328,19 @@
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
@@ -417,15 +424,17 @@
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

### Comparing `types-aiobotocore-ecr-2.5.0.post1/types_aiobotocore_ecr/paginator.py` & `types-aiobotocore-ecr-2.5.1/types_aiobotocore_ecr/paginator.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -26,16 +26,15 @@
         describe_images_paginator: DescribeImagesPaginator = client.get_paginator("describe_images")
         describe_pull_through_cache_rules_paginator: DescribePullThroughCacheRulesPaginator = client.get_paginator("describe_pull_through_cache_rules")
         describe_repositories_paginator: DescribeRepositoriesPaginator = client.get_paginator("describe_repositories")
         get_lifecycle_policy_preview_paginator: GetLifecyclePolicyPreviewPaginator = client.get_paginator("get_lifecycle_policy_preview")
         list_images_paginator: ListImagesPaginator = client.get_paginator("list_images")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DescribeImageScanFindingsResponseTypeDef,
     DescribeImagesFilterTypeDef,
@@ -46,151 +45,137 @@
     ImageIdentifierTypeDef,
     LifecyclePolicyPreviewFilterTypeDef,
     ListImagesFilterTypeDef,
     ListImagesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "DescribeImageScanFindingsPaginator",
     "DescribeImagesPaginator",
     "DescribePullThroughCacheRulesPaginator",
     "DescribeRepositoriesPaginator",
     "GetLifecyclePolicyPreviewPaginator",
     "ListImagesPaginator",
 )
 
-
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
-
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
-
 class DescribeImageScanFindingsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Paginator.DescribeImageScanFindings)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr/paginators/#describeimagescanfindingspaginator)
     """
 
     def paginate(
         self,
         *,
         repositoryName: str,
         imageId: ImageIdentifierTypeDef,
         registryId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeImageScanFindingsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Paginator.DescribeImageScanFindings.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr/paginators/#describeimagescanfindingspaginator)
         """
 
-
 class DescribeImagesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Paginator.DescribeImages)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr/paginators/#describeimagespaginator)
     """
 
     def paginate(
         self,
         *,
         repositoryName: str,
         registryId: str = ...,
         imageIds: Sequence[ImageIdentifierTypeDef] = ...,
         filter: DescribeImagesFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeImagesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Paginator.DescribeImages.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr/paginators/#describeimagespaginator)
         """
 
-
 class DescribePullThroughCacheRulesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Paginator.DescribePullThroughCacheRules)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr/paginators/#describepullthroughcacherulespaginator)
     """
 
     def paginate(
         self,
         *,
         registryId: str = ...,
         ecrRepositoryPrefixes: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribePullThroughCacheRulesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Paginator.DescribePullThroughCacheRules.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr/paginators/#describepullthroughcacherulespaginator)
         """
 
-
 class DescribeRepositoriesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Paginator.DescribeRepositories)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr/paginators/#describerepositoriespaginator)
     """
 
     def paginate(
         self,
         *,
         registryId: str = ...,
         repositoryNames: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeRepositoriesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Paginator.DescribeRepositories.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr/paginators/#describerepositoriespaginator)
         """
 
-
 class GetLifecyclePolicyPreviewPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Paginator.GetLifecyclePolicyPreview)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr/paginators/#getlifecyclepolicypreviewpaginator)
     """
 
     def paginate(
         self,
         *,
         repositoryName: str,
         registryId: str = ...,
         imageIds: Sequence[ImageIdentifierTypeDef] = ...,
         filter: LifecyclePolicyPreviewFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetLifecyclePolicyPreviewResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Paginator.GetLifecyclePolicyPreview.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr/paginators/#getlifecyclepolicypreviewpaginator)
         """
 
-
 class ListImagesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Paginator.ListImages)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr/paginators/#listimagespaginator)
     """
 
     def paginate(
         self,
         *,
         repositoryName: str,
         registryId: str = ...,
         filter: ListImagesFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListImagesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Paginator.ListImages.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr/paginators/#listimagespaginator)
         """
```

### Comparing `types-aiobotocore-ecr-2.5.0.post1/types_aiobotocore_ecr/paginator.pyi` & `types-aiobotocore-ecr-2.5.1/types_aiobotocore_ecr/paginator.py`

 * *Files 9% similar despite different names*

```diff
@@ -26,16 +26,15 @@
         describe_images_paginator: DescribeImagesPaginator = client.get_paginator("describe_images")
         describe_pull_through_cache_rules_paginator: DescribePullThroughCacheRulesPaginator = client.get_paginator("describe_pull_through_cache_rules")
         describe_repositories_paginator: DescribeRepositoriesPaginator = client.get_paginator("describe_repositories")
         get_lifecycle_policy_preview_paginator: GetLifecyclePolicyPreviewPaginator = client.get_paginator("get_lifecycle_policy_preview")
         list_images_paginator: ListImagesPaginator = client.get_paginator("list_images")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DescribeImageScanFindingsResponseTypeDef,
     DescribeImagesFilterTypeDef,
@@ -46,142 +45,145 @@
     ImageIdentifierTypeDef,
     LifecyclePolicyPreviewFilterTypeDef,
     ListImagesFilterTypeDef,
     ListImagesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "DescribeImageScanFindingsPaginator",
     "DescribeImagesPaginator",
     "DescribePullThroughCacheRulesPaginator",
     "DescribeRepositoriesPaginator",
     "GetLifecyclePolicyPreviewPaginator",
     "ListImagesPaginator",
 )
 
+
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
+
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
+
 class DescribeImageScanFindingsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Paginator.DescribeImageScanFindings)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr/paginators/#describeimagescanfindingspaginator)
     """
 
     def paginate(
         self,
         *,
         repositoryName: str,
         imageId: ImageIdentifierTypeDef,
         registryId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeImageScanFindingsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Paginator.DescribeImageScanFindings.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr/paginators/#describeimagescanfindingspaginator)
         """
 
+
 class DescribeImagesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Paginator.DescribeImages)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr/paginators/#describeimagespaginator)
     """
 
     def paginate(
         self,
         *,
         repositoryName: str,
         registryId: str = ...,
         imageIds: Sequence[ImageIdentifierTypeDef] = ...,
         filter: DescribeImagesFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeImagesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Paginator.DescribeImages.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr/paginators/#describeimagespaginator)
         """
 
+
 class DescribePullThroughCacheRulesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Paginator.DescribePullThroughCacheRules)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr/paginators/#describepullthroughcacherulespaginator)
     """
 
     def paginate(
         self,
         *,
         registryId: str = ...,
         ecrRepositoryPrefixes: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribePullThroughCacheRulesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Paginator.DescribePullThroughCacheRules.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr/paginators/#describepullthroughcacherulespaginator)
         """
 
+
 class DescribeRepositoriesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Paginator.DescribeRepositories)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr/paginators/#describerepositoriespaginator)
     """
 
     def paginate(
         self,
         *,
         registryId: str = ...,
         repositoryNames: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeRepositoriesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Paginator.DescribeRepositories.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr/paginators/#describerepositoriespaginator)
         """
 
+
 class GetLifecyclePolicyPreviewPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Paginator.GetLifecyclePolicyPreview)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr/paginators/#getlifecyclepolicypreviewpaginator)
     """
 
     def paginate(
         self,
         *,
         repositoryName: str,
         registryId: str = ...,
         imageIds: Sequence[ImageIdentifierTypeDef] = ...,
         filter: LifecyclePolicyPreviewFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetLifecyclePolicyPreviewResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Paginator.GetLifecyclePolicyPreview.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr/paginators/#getlifecyclepolicypreviewpaginator)
         """
 
+
 class ListImagesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Paginator.ListImages)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr/paginators/#listimagespaginator)
     """
 
     def paginate(
         self,
         *,
         repositoryName: str,
         registryId: str = ...,
         filter: ListImagesFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListImagesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR.Paginator.ListImages.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr/paginators/#listimagespaginator)
         """
```

### Comparing `types-aiobotocore-ecr-2.5.0.post1/types_aiobotocore_ecr/type_defs.py` & `types-aiobotocore-ecr-2.5.1/types_aiobotocore_ecr/type_defs.py`

 * *Files 4% similar despite different names*

```diff
@@ -45,101 +45,101 @@
 __all__ = (
     "AttributeTypeDef",
     "AuthorizationDataTypeDef",
     "AwsEcrContainerImageDetailsTypeDef",
     "BatchCheckLayerAvailabilityRequestRequestTypeDef",
     "LayerFailureTypeDef",
     "LayerTypeDef",
-    "ResponseMetadataTypeDef",
     "ImageIdentifierTypeDef",
     "BatchGetRepositoryScanningConfigurationRequestRequestTypeDef",
     "RepositoryScanningConfigurationFailureTypeDef",
     "CompleteLayerUploadRequestRequestTypeDef",
+    "CompleteLayerUploadResponseTypeDef",
     "CreatePullThroughCacheRuleRequestRequestTypeDef",
+    "CreatePullThroughCacheRuleResponseTypeDef",
     "EncryptionConfigurationTypeDef",
     "ImageScanningConfigurationTypeDef",
     "TagTypeDef",
     "CvssScoreAdjustmentTypeDef",
     "CvssScoreTypeDef",
     "DeleteLifecyclePolicyRequestRequestTypeDef",
+    "DeleteLifecyclePolicyResponseTypeDef",
     "DeletePullThroughCacheRuleRequestRequestTypeDef",
+    "DeletePullThroughCacheRuleResponseTypeDef",
+    "DeleteRegistryPolicyResponseTypeDef",
     "DeleteRepositoryPolicyRequestRequestTypeDef",
+    "DeleteRepositoryPolicyResponseTypeDef",
     "DeleteRepositoryRequestRequestTypeDef",
     "ImageReplicationStatusTypeDef",
-    "PaginatorConfigTypeDef",
     "WaiterConfigTypeDef",
     "ImageScanStatusTypeDef",
     "DescribeImagesFilterTypeDef",
+    "DescribePullThroughCacheRulesRequestDescribePullThroughCacheRulesPaginateTypeDef",
     "DescribePullThroughCacheRulesRequestRequestTypeDef",
     "PullThroughCacheRuleTypeDef",
+    "DescribeRepositoriesRequestDescribeRepositoriesPaginateTypeDef",
     "DescribeRepositoriesRequestRequestTypeDef",
     "GetAuthorizationTokenRequestRequestTypeDef",
     "GetDownloadUrlForLayerRequestRequestTypeDef",
+    "GetDownloadUrlForLayerResponseTypeDef",
     "LifecyclePolicyPreviewFilterTypeDef",
     "LifecyclePolicyPreviewSummaryTypeDef",
     "GetLifecyclePolicyRequestRequestTypeDef",
+    "GetLifecyclePolicyResponseTypeDef",
+    "GetRegistryPolicyResponseTypeDef",
     "GetRepositoryPolicyRequestRequestTypeDef",
+    "GetRepositoryPolicyResponseTypeDef",
     "ImageScanFindingsSummaryTypeDef",
     "InitiateLayerUploadRequestRequestTypeDef",
+    "InitiateLayerUploadResponseTypeDef",
     "LifecyclePolicyRuleActionTypeDef",
     "ListImagesFilterTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "VulnerablePackageTypeDef",
+    "PaginatorConfigTypeDef",
     "PutImageRequestRequestTypeDef",
     "PutImageTagMutabilityRequestRequestTypeDef",
+    "PutImageTagMutabilityResponseTypeDef",
     "PutLifecyclePolicyRequestRequestTypeDef",
+    "PutLifecyclePolicyResponseTypeDef",
     "PutRegistryPolicyRequestRequestTypeDef",
+    "PutRegistryPolicyResponseTypeDef",
     "RecommendationTypeDef",
     "ScanningRepositoryFilterTypeDef",
     "ReplicationDestinationTypeDef",
     "RepositoryFilterTypeDef",
+    "ResponseMetadataTypeDef",
     "SetRepositoryPolicyRequestRequestTypeDef",
+    "SetRepositoryPolicyResponseTypeDef",
     "StartLifecyclePolicyPreviewRequestRequestTypeDef",
+    "StartLifecyclePolicyPreviewResponseTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UploadLayerPartRequestRequestTypeDef",
+    "UploadLayerPartResponseTypeDef",
     "ImageScanFindingTypeDef",
+    "GetAuthorizationTokenResponseTypeDef",
     "ResourceDetailsTypeDef",
     "BatchCheckLayerAvailabilityResponseTypeDef",
-    "CompleteLayerUploadResponseTypeDef",
-    "CreatePullThroughCacheRuleResponseTypeDef",
-    "DeleteLifecyclePolicyResponseTypeDef",
-    "DeletePullThroughCacheRuleResponseTypeDef",
-    "DeleteRegistryPolicyResponseTypeDef",
-    "DeleteRepositoryPolicyResponseTypeDef",
-    "GetAuthorizationTokenResponseTypeDef",
-    "GetDownloadUrlForLayerResponseTypeDef",
-    "GetLifecyclePolicyResponseTypeDef",
-    "GetRegistryPolicyResponseTypeDef",
-    "GetRepositoryPolicyResponseTypeDef",
-    "InitiateLayerUploadResponseTypeDef",
-    "PutImageTagMutabilityResponseTypeDef",
-    "PutLifecyclePolicyResponseTypeDef",
-    "PutRegistryPolicyResponseTypeDef",
-    "SetRepositoryPolicyResponseTypeDef",
-    "StartLifecyclePolicyPreviewResponseTypeDef",
-    "UploadLayerPartResponseTypeDef",
     "BatchDeleteImageRequestRequestTypeDef",
     "BatchGetImageRequestRequestTypeDef",
     "DescribeImageReplicationStatusRequestRequestTypeDef",
+    "DescribeImageScanFindingsRequestDescribeImageScanFindingsPaginateTypeDef",
     "DescribeImageScanFindingsRequestRequestTypeDef",
     "ImageFailureTypeDef",
     "ImageTypeDef",
     "ListImagesResponseTypeDef",
     "StartImageScanRequestRequestTypeDef",
     "PutImageScanningConfigurationRequestRequestTypeDef",
     "PutImageScanningConfigurationResponseTypeDef",
     "RepositoryTypeDef",
     "CreateRepositoryRequestRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "CvssScoreDetailsTypeDef",
     "DescribeImageReplicationStatusResponseTypeDef",
-    "DescribeImageScanFindingsRequestDescribeImageScanFindingsPaginateTypeDef",
-    "DescribePullThroughCacheRulesRequestDescribePullThroughCacheRulesPaginateTypeDef",
-    "DescribeRepositoriesRequestDescribeRepositoriesPaginateTypeDef",
     "DescribeImageScanFindingsRequestImageScanCompleteWaitTypeDef",
     "StartImageScanResponseTypeDef",
     "DescribeImagesRequestDescribeImagesPaginateTypeDef",
     "DescribeImagesRequestRequestTypeDef",
     "DescribePullThroughCacheRulesResponseTypeDef",
     "GetLifecyclePolicyPreviewRequestGetLifecyclePolicyPreviewPaginateTypeDef",
     "GetLifecyclePolicyPreviewRequestLifecyclePolicyPreviewCompleteWaitTypeDef",
@@ -261,25 +261,14 @@
         "layerAvailability": LayerAvailabilityType,
         "layerSize": int,
         "mediaType": str,
     },
     total=False,
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
 ImageIdentifierTypeDef = TypedDict(
     "ImageIdentifierTypeDef",
     {
         "imageDigest": str,
         "imageTag": str,
     },
     total=False,
@@ -322,14 +311,25 @@
 class CompleteLayerUploadRequestRequestTypeDef(
     _RequiredCompleteLayerUploadRequestRequestTypeDef,
     _OptionalCompleteLayerUploadRequestRequestTypeDef,
 ):
     pass
 
 
+CompleteLayerUploadResponseTypeDef = TypedDict(
+    "CompleteLayerUploadResponseTypeDef",
+    {
+        "registryId": str,
+        "repositoryName": str,
+        "uploadId": str,
+        "layerDigest": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreatePullThroughCacheRuleRequestRequestTypeDef = TypedDict(
     "_RequiredCreatePullThroughCacheRuleRequestRequestTypeDef",
     {
         "ecrRepositoryPrefix": str,
         "upstreamRegistryUrl": str,
     },
 )
@@ -345,14 +345,25 @@
 class CreatePullThroughCacheRuleRequestRequestTypeDef(
     _RequiredCreatePullThroughCacheRuleRequestRequestTypeDef,
     _OptionalCreatePullThroughCacheRuleRequestRequestTypeDef,
 ):
     pass
 
 
+CreatePullThroughCacheRuleResponseTypeDef = TypedDict(
+    "CreatePullThroughCacheRuleResponseTypeDef",
+    {
+        "ecrRepositoryPrefix": str,
+        "upstreamRegistryUrl": str,
+        "createdAt": datetime,
+        "registryId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredEncryptionConfigurationTypeDef = TypedDict(
     "_RequiredEncryptionConfigurationTypeDef",
     {
         "encryptionType": EncryptionTypeType,
     },
 )
 _OptionalEncryptionConfigurationTypeDef = TypedDict(
@@ -425,14 +436,25 @@
 class DeleteLifecyclePolicyRequestRequestTypeDef(
     _RequiredDeleteLifecyclePolicyRequestRequestTypeDef,
     _OptionalDeleteLifecyclePolicyRequestRequestTypeDef,
 ):
     pass
 
 
+DeleteLifecyclePolicyResponseTypeDef = TypedDict(
+    "DeleteLifecyclePolicyResponseTypeDef",
+    {
+        "registryId": str,
+        "repositoryName": str,
+        "lifecyclePolicyText": str,
+        "lastEvaluatedAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeletePullThroughCacheRuleRequestRequestTypeDef = TypedDict(
     "_RequiredDeletePullThroughCacheRuleRequestRequestTypeDef",
     {
         "ecrRepositoryPrefix": str,
     },
 )
 _OptionalDeletePullThroughCacheRuleRequestRequestTypeDef = TypedDict(
@@ -447,14 +469,34 @@
 class DeletePullThroughCacheRuleRequestRequestTypeDef(
     _RequiredDeletePullThroughCacheRuleRequestRequestTypeDef,
     _OptionalDeletePullThroughCacheRuleRequestRequestTypeDef,
 ):
     pass
 
 
+DeletePullThroughCacheRuleResponseTypeDef = TypedDict(
+    "DeletePullThroughCacheRuleResponseTypeDef",
+    {
+        "ecrRepositoryPrefix": str,
+        "upstreamRegistryUrl": str,
+        "createdAt": datetime,
+        "registryId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DeleteRegistryPolicyResponseTypeDef = TypedDict(
+    "DeleteRegistryPolicyResponseTypeDef",
+    {
+        "registryId": str,
+        "policyText": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteRepositoryPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteRepositoryPolicyRequestRequestTypeDef",
     {
         "repositoryName": str,
     },
 )
 _OptionalDeleteRepositoryPolicyRequestRequestTypeDef = TypedDict(
@@ -469,14 +511,24 @@
 class DeleteRepositoryPolicyRequestRequestTypeDef(
     _RequiredDeleteRepositoryPolicyRequestRequestTypeDef,
     _OptionalDeleteRepositoryPolicyRequestRequestTypeDef,
 ):
     pass
 
 
+DeleteRepositoryPolicyResponseTypeDef = TypedDict(
+    "DeleteRepositoryPolicyResponseTypeDef",
+    {
+        "registryId": str,
+        "repositoryName": str,
+        "policyText": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteRepositoryRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteRepositoryRequestRequestTypeDef",
     {
         "repositoryName": str,
     },
 )
 _OptionalDeleteRepositoryRequestRequestTypeDef = TypedDict(
@@ -502,24 +554,14 @@
         "registryId": str,
         "status": ReplicationStatusType,
         "failureCode": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
-    {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
-    },
-    total=False,
-)
-
 WaiterConfigTypeDef = TypedDict(
     "WaiterConfigTypeDef",
     {
         "Delay": int,
         "MaxAttempts": int,
     },
     total=False,
@@ -538,14 +580,24 @@
     "DescribeImagesFilterTypeDef",
     {
         "tagStatus": TagStatusType,
     },
     total=False,
 )
 
+DescribePullThroughCacheRulesRequestDescribePullThroughCacheRulesPaginateTypeDef = TypedDict(
+    "DescribePullThroughCacheRulesRequestDescribePullThroughCacheRulesPaginateTypeDef",
+    {
+        "registryId": str,
+        "ecrRepositoryPrefixes": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribePullThroughCacheRulesRequestRequestTypeDef = TypedDict(
     "DescribePullThroughCacheRulesRequestRequestTypeDef",
     {
         "registryId": str,
         "ecrRepositoryPrefixes": Sequence[str],
         "nextToken": str,
         "maxResults": int,
@@ -560,14 +612,24 @@
         "upstreamRegistryUrl": str,
         "createdAt": datetime,
         "registryId": str,
     },
     total=False,
 )
 
+DescribeRepositoriesRequestDescribeRepositoriesPaginateTypeDef = TypedDict(
+    "DescribeRepositoriesRequestDescribeRepositoriesPaginateTypeDef",
+    {
+        "registryId": str,
+        "repositoryNames": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeRepositoriesRequestRequestTypeDef = TypedDict(
     "DescribeRepositoriesRequestRequestTypeDef",
     {
         "registryId": str,
         "repositoryNames": Sequence[str],
         "nextToken": str,
         "maxResults": int,
@@ -602,14 +664,23 @@
 class GetDownloadUrlForLayerRequestRequestTypeDef(
     _RequiredGetDownloadUrlForLayerRequestRequestTypeDef,
     _OptionalGetDownloadUrlForLayerRequestRequestTypeDef,
 ):
     pass
 
 
+GetDownloadUrlForLayerResponseTypeDef = TypedDict(
+    "GetDownloadUrlForLayerResponseTypeDef",
+    {
+        "downloadUrl": str,
+        "layerDigest": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 LifecyclePolicyPreviewFilterTypeDef = TypedDict(
     "LifecyclePolicyPreviewFilterTypeDef",
     {
         "tagStatus": TagStatusType,
     },
     total=False,
 )
@@ -640,14 +711,34 @@
 class GetLifecyclePolicyRequestRequestTypeDef(
     _RequiredGetLifecyclePolicyRequestRequestTypeDef,
     _OptionalGetLifecyclePolicyRequestRequestTypeDef,
 ):
     pass
 
 
+GetLifecyclePolicyResponseTypeDef = TypedDict(
+    "GetLifecyclePolicyResponseTypeDef",
+    {
+        "registryId": str,
+        "repositoryName": str,
+        "lifecyclePolicyText": str,
+        "lastEvaluatedAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetRegistryPolicyResponseTypeDef = TypedDict(
+    "GetRegistryPolicyResponseTypeDef",
+    {
+        "registryId": str,
+        "policyText": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetRepositoryPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredGetRepositoryPolicyRequestRequestTypeDef",
     {
         "repositoryName": str,
     },
 )
 _OptionalGetRepositoryPolicyRequestRequestTypeDef = TypedDict(
@@ -662,14 +753,24 @@
 class GetRepositoryPolicyRequestRequestTypeDef(
     _RequiredGetRepositoryPolicyRequestRequestTypeDef,
     _OptionalGetRepositoryPolicyRequestRequestTypeDef,
 ):
     pass
 
 
+GetRepositoryPolicyResponseTypeDef = TypedDict(
+    "GetRepositoryPolicyResponseTypeDef",
+    {
+        "registryId": str,
+        "repositoryName": str,
+        "policyText": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ImageScanFindingsSummaryTypeDef = TypedDict(
     "ImageScanFindingsSummaryTypeDef",
     {
         "imageScanCompletedAt": datetime,
         "vulnerabilitySourceUpdatedAt": datetime,
         "findingSeverityCounts": Dict[FindingSeverityType, int],
     },
@@ -694,14 +795,23 @@
 class InitiateLayerUploadRequestRequestTypeDef(
     _RequiredInitiateLayerUploadRequestRequestTypeDef,
     _OptionalInitiateLayerUploadRequestRequestTypeDef,
 ):
     pass
 
 
+InitiateLayerUploadResponseTypeDef = TypedDict(
+    "InitiateLayerUploadResponseTypeDef",
+    {
+        "uploadId": str,
+        "partSize": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 LifecyclePolicyRuleActionTypeDef = TypedDict(
     "LifecyclePolicyRuleActionTypeDef",
     {
         "type": Literal["EXPIRE"],
     },
     total=False,
 )
@@ -732,14 +842,24 @@
         "release": str,
         "sourceLayerHash": str,
         "version": str,
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
 _RequiredPutImageRequestRequestTypeDef = TypedDict(
     "_RequiredPutImageRequestRequestTypeDef",
     {
         "repositoryName": str,
         "imageManifest": str,
     },
 )
@@ -780,14 +900,24 @@
 class PutImageTagMutabilityRequestRequestTypeDef(
     _RequiredPutImageTagMutabilityRequestRequestTypeDef,
     _OptionalPutImageTagMutabilityRequestRequestTypeDef,
 ):
     pass
 
 
+PutImageTagMutabilityResponseTypeDef = TypedDict(
+    "PutImageTagMutabilityResponseTypeDef",
+    {
+        "registryId": str,
+        "repositoryName": str,
+        "imageTagMutability": ImageTagMutabilityType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredPutLifecyclePolicyRequestRequestTypeDef = TypedDict(
     "_RequiredPutLifecyclePolicyRequestRequestTypeDef",
     {
         "repositoryName": str,
         "lifecyclePolicyText": str,
     },
 )
@@ -803,21 +933,40 @@
 class PutLifecyclePolicyRequestRequestTypeDef(
     _RequiredPutLifecyclePolicyRequestRequestTypeDef,
     _OptionalPutLifecyclePolicyRequestRequestTypeDef,
 ):
     pass
 
 
+PutLifecyclePolicyResponseTypeDef = TypedDict(
+    "PutLifecyclePolicyResponseTypeDef",
+    {
+        "registryId": str,
+        "repositoryName": str,
+        "lifecyclePolicyText": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 PutRegistryPolicyRequestRequestTypeDef = TypedDict(
     "PutRegistryPolicyRequestRequestTypeDef",
     {
         "policyText": str,
     },
 )
 
+PutRegistryPolicyResponseTypeDef = TypedDict(
+    "PutRegistryPolicyResponseTypeDef",
+    {
+        "registryId": str,
+        "policyText": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RecommendationTypeDef = TypedDict(
     "RecommendationTypeDef",
     {
         "url": str,
         "text": str,
     },
     total=False,
@@ -843,14 +992,25 @@
     "RepositoryFilterTypeDef",
     {
         "filter": str,
         "filterType": Literal["PREFIX_MATCH"],
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
 _RequiredSetRepositoryPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredSetRepositoryPolicyRequestRequestTypeDef",
     {
         "repositoryName": str,
         "policyText": str,
     },
 )
@@ -867,14 +1027,24 @@
 class SetRepositoryPolicyRequestRequestTypeDef(
     _RequiredSetRepositoryPolicyRequestRequestTypeDef,
     _OptionalSetRepositoryPolicyRequestRequestTypeDef,
 ):
     pass
 
 
+SetRepositoryPolicyResponseTypeDef = TypedDict(
+    "SetRepositoryPolicyResponseTypeDef",
+    {
+        "registryId": str,
+        "repositoryName": str,
+        "policyText": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredStartLifecyclePolicyPreviewRequestRequestTypeDef = TypedDict(
     "_RequiredStartLifecyclePolicyPreviewRequestRequestTypeDef",
     {
         "repositoryName": str,
     },
 )
 _OptionalStartLifecyclePolicyPreviewRequestRequestTypeDef = TypedDict(
@@ -890,14 +1060,25 @@
 class StartLifecyclePolicyPreviewRequestRequestTypeDef(
     _RequiredStartLifecyclePolicyPreviewRequestRequestTypeDef,
     _OptionalStartLifecyclePolicyPreviewRequestRequestTypeDef,
 ):
     pass
 
 
+StartLifecyclePolicyPreviewResponseTypeDef = TypedDict(
+    "StartLifecyclePolicyPreviewResponseTypeDef",
+    {
+        "registryId": str,
+        "repositoryName": str,
+        "lifecyclePolicyText": str,
+        "status": LifecyclePolicyPreviewStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
@@ -923,220 +1104,59 @@
 
 class UploadLayerPartRequestRequestTypeDef(
     _RequiredUploadLayerPartRequestRequestTypeDef, _OptionalUploadLayerPartRequestRequestTypeDef
 ):
     pass
 
 
+UploadLayerPartResponseTypeDef = TypedDict(
+    "UploadLayerPartResponseTypeDef",
+    {
+        "registryId": str,
+        "repositoryName": str,
+        "uploadId": str,
+        "lastByteReceived": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ImageScanFindingTypeDef = TypedDict(
     "ImageScanFindingTypeDef",
     {
         "name": str,
         "description": str,
         "uri": str,
         "severity": FindingSeverityType,
         "attributes": List[AttributeTypeDef],
     },
     total=False,
 )
 
+GetAuthorizationTokenResponseTypeDef = TypedDict(
+    "GetAuthorizationTokenResponseTypeDef",
+    {
+        "authorizationData": List[AuthorizationDataTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ResourceDetailsTypeDef = TypedDict(
     "ResourceDetailsTypeDef",
     {
         "awsEcrContainerImage": AwsEcrContainerImageDetailsTypeDef,
     },
     total=False,
 )
 
 BatchCheckLayerAvailabilityResponseTypeDef = TypedDict(
     "BatchCheckLayerAvailabilityResponseTypeDef",
     {
         "layers": List[LayerTypeDef],
         "failures": List[LayerFailureTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CompleteLayerUploadResponseTypeDef = TypedDict(
-    "CompleteLayerUploadResponseTypeDef",
-    {
-        "registryId": str,
-        "repositoryName": str,
-        "uploadId": str,
-        "layerDigest": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreatePullThroughCacheRuleResponseTypeDef = TypedDict(
-    "CreatePullThroughCacheRuleResponseTypeDef",
-    {
-        "ecrRepositoryPrefix": str,
-        "upstreamRegistryUrl": str,
-        "createdAt": datetime,
-        "registryId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteLifecyclePolicyResponseTypeDef = TypedDict(
-    "DeleteLifecyclePolicyResponseTypeDef",
-    {
-        "registryId": str,
-        "repositoryName": str,
-        "lifecyclePolicyText": str,
-        "lastEvaluatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeletePullThroughCacheRuleResponseTypeDef = TypedDict(
-    "DeletePullThroughCacheRuleResponseTypeDef",
-    {
-        "ecrRepositoryPrefix": str,
-        "upstreamRegistryUrl": str,
-        "createdAt": datetime,
-        "registryId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteRegistryPolicyResponseTypeDef = TypedDict(
-    "DeleteRegistryPolicyResponseTypeDef",
-    {
-        "registryId": str,
-        "policyText": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteRepositoryPolicyResponseTypeDef = TypedDict(
-    "DeleteRepositoryPolicyResponseTypeDef",
-    {
-        "registryId": str,
-        "repositoryName": str,
-        "policyText": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetAuthorizationTokenResponseTypeDef = TypedDict(
-    "GetAuthorizationTokenResponseTypeDef",
-    {
-        "authorizationData": List[AuthorizationDataTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetDownloadUrlForLayerResponseTypeDef = TypedDict(
-    "GetDownloadUrlForLayerResponseTypeDef",
-    {
-        "downloadUrl": str,
-        "layerDigest": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetLifecyclePolicyResponseTypeDef = TypedDict(
-    "GetLifecyclePolicyResponseTypeDef",
-    {
-        "registryId": str,
-        "repositoryName": str,
-        "lifecyclePolicyText": str,
-        "lastEvaluatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetRegistryPolicyResponseTypeDef = TypedDict(
-    "GetRegistryPolicyResponseTypeDef",
-    {
-        "registryId": str,
-        "policyText": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetRepositoryPolicyResponseTypeDef = TypedDict(
-    "GetRepositoryPolicyResponseTypeDef",
-    {
-        "registryId": str,
-        "repositoryName": str,
-        "policyText": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-InitiateLayerUploadResponseTypeDef = TypedDict(
-    "InitiateLayerUploadResponseTypeDef",
-    {
-        "uploadId": str,
-        "partSize": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutImageTagMutabilityResponseTypeDef = TypedDict(
-    "PutImageTagMutabilityResponseTypeDef",
-    {
-        "registryId": str,
-        "repositoryName": str,
-        "imageTagMutability": ImageTagMutabilityType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutLifecyclePolicyResponseTypeDef = TypedDict(
-    "PutLifecyclePolicyResponseTypeDef",
-    {
-        "registryId": str,
-        "repositoryName": str,
-        "lifecyclePolicyText": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutRegistryPolicyResponseTypeDef = TypedDict(
-    "PutRegistryPolicyResponseTypeDef",
-    {
-        "registryId": str,
-        "policyText": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SetRepositoryPolicyResponseTypeDef = TypedDict(
-    "SetRepositoryPolicyResponseTypeDef",
-    {
-        "registryId": str,
-        "repositoryName": str,
-        "policyText": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartLifecyclePolicyPreviewResponseTypeDef = TypedDict(
-    "StartLifecyclePolicyPreviewResponseTypeDef",
-    {
-        "registryId": str,
-        "repositoryName": str,
-        "lifecyclePolicyText": str,
-        "status": LifecyclePolicyPreviewStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UploadLayerPartResponseTypeDef = TypedDict(
-    "UploadLayerPartResponseTypeDef",
-    {
-        "registryId": str,
-        "repositoryName": str,
-        "uploadId": str,
-        "lastByteReceived": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredBatchDeleteImageRequestRequestTypeDef = TypedDict(
     "_RequiredBatchDeleteImageRequestRequestTypeDef",
     {
         "repositoryName": str,
@@ -1200,14 +1220,38 @@
 class DescribeImageReplicationStatusRequestRequestTypeDef(
     _RequiredDescribeImageReplicationStatusRequestRequestTypeDef,
     _OptionalDescribeImageReplicationStatusRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredDescribeImageScanFindingsRequestDescribeImageScanFindingsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeImageScanFindingsRequestDescribeImageScanFindingsPaginateTypeDef",
+    {
+        "repositoryName": str,
+        "imageId": ImageIdentifierTypeDef,
+    },
+)
+_OptionalDescribeImageScanFindingsRequestDescribeImageScanFindingsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeImageScanFindingsRequestDescribeImageScanFindingsPaginateTypeDef",
+    {
+        "registryId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeImageScanFindingsRequestDescribeImageScanFindingsPaginateTypeDef(
+    _RequiredDescribeImageScanFindingsRequestDescribeImageScanFindingsPaginateTypeDef,
+    _OptionalDescribeImageScanFindingsRequestDescribeImageScanFindingsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeImageScanFindingsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeImageScanFindingsRequestRequestTypeDef",
     {
         "repositoryName": str,
         "imageId": ImageIdentifierTypeDef,
     },
 )
@@ -1252,15 +1296,15 @@
 )
 
 ListImagesResponseTypeDef = TypedDict(
     "ListImagesResponseTypeDef",
     {
         "imageIds": List[ImageIdentifierTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStartImageScanRequestRequestTypeDef = TypedDict(
     "_RequiredStartImageScanRequestRequestTypeDef",
     {
         "repositoryName": str,
@@ -1307,15 +1351,15 @@
 
 PutImageScanningConfigurationResponseTypeDef = TypedDict(
     "PutImageScanningConfigurationResponseTypeDef",
     {
         "registryId": str,
         "repositoryName": str,
         "imageScanningConfiguration": ImageScanningConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RepositoryTypeDef = TypedDict(
     "RepositoryTypeDef",
     {
         "repositoryArn": str,
@@ -1355,15 +1399,15 @@
     pass
 
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
@@ -1385,62 +1429,18 @@
 
 DescribeImageReplicationStatusResponseTypeDef = TypedDict(
     "DescribeImageReplicationStatusResponseTypeDef",
     {
         "repositoryName": str,
         "imageId": ImageIdentifierTypeDef,
         "replicationStatuses": List[ImageReplicationStatusTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-_RequiredDescribeImageScanFindingsRequestDescribeImageScanFindingsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeImageScanFindingsRequestDescribeImageScanFindingsPaginateTypeDef",
-    {
-        "repositoryName": str,
-        "imageId": ImageIdentifierTypeDef,
-    },
-)
-_OptionalDescribeImageScanFindingsRequestDescribeImageScanFindingsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeImageScanFindingsRequestDescribeImageScanFindingsPaginateTypeDef",
-    {
-        "registryId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeImageScanFindingsRequestDescribeImageScanFindingsPaginateTypeDef(
-    _RequiredDescribeImageScanFindingsRequestDescribeImageScanFindingsPaginateTypeDef,
-    _OptionalDescribeImageScanFindingsRequestDescribeImageScanFindingsPaginateTypeDef,
-):
-    pass
-
-
-DescribePullThroughCacheRulesRequestDescribePullThroughCacheRulesPaginateTypeDef = TypedDict(
-    "DescribePullThroughCacheRulesRequestDescribePullThroughCacheRulesPaginateTypeDef",
-    {
-        "registryId": str,
-        "ecrRepositoryPrefixes": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeRepositoriesRequestDescribeRepositoriesPaginateTypeDef = TypedDict(
-    "DescribeRepositoriesRequestDescribeRepositoriesPaginateTypeDef",
-    {
-        "registryId": str,
-        "repositoryNames": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 _RequiredDescribeImageScanFindingsRequestImageScanCompleteWaitTypeDef = TypedDict(
     "_RequiredDescribeImageScanFindingsRequestImageScanCompleteWaitTypeDef",
     {
         "repositoryName": str,
         "imageId": ImageIdentifierTypeDef,
     },
 )
@@ -1466,15 +1466,15 @@
 StartImageScanResponseTypeDef = TypedDict(
     "StartImageScanResponseTypeDef",
     {
         "registryId": str,
         "repositoryName": str,
         "imageId": ImageIdentifierTypeDef,
         "imageScanStatus": ImageScanStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDescribeImagesRequestDescribeImagesPaginateTypeDef = TypedDict(
     "_RequiredDescribeImagesRequestDescribeImagesPaginateTypeDef",
     {
         "repositoryName": str,
@@ -1482,15 +1482,15 @@
 )
 _OptionalDescribeImagesRequestDescribeImagesPaginateTypeDef = TypedDict(
     "_OptionalDescribeImagesRequestDescribeImagesPaginateTypeDef",
     {
         "registryId": str,
         "imageIds": Sequence[ImageIdentifierTypeDef],
         "filter": DescribeImagesFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
 class DescribeImagesRequestDescribeImagesPaginateTypeDef(
     _RequiredDescribeImagesRequestDescribeImagesPaginateTypeDef,
@@ -1525,15 +1525,15 @@
 
 
 DescribePullThroughCacheRulesResponseTypeDef = TypedDict(
     "DescribePullThroughCacheRulesResponseTypeDef",
     {
         "pullThroughCacheRules": List[PullThroughCacheRuleTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetLifecyclePolicyPreviewRequestGetLifecyclePolicyPreviewPaginateTypeDef = TypedDict(
     "_RequiredGetLifecyclePolicyPreviewRequestGetLifecyclePolicyPreviewPaginateTypeDef",
     {
         "repositoryName": str,
@@ -1541,15 +1541,15 @@
 )
 _OptionalGetLifecyclePolicyPreviewRequestGetLifecyclePolicyPreviewPaginateTypeDef = TypedDict(
     "_OptionalGetLifecyclePolicyPreviewRequestGetLifecyclePolicyPreviewPaginateTypeDef",
     {
         "registryId": str,
         "imageIds": Sequence[ImageIdentifierTypeDef],
         "filter": LifecyclePolicyPreviewFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
 class GetLifecyclePolicyPreviewRequestGetLifecyclePolicyPreviewPaginateTypeDef(
     _RequiredGetLifecyclePolicyPreviewRequestGetLifecyclePolicyPreviewPaginateTypeDef,
@@ -1648,15 +1648,15 @@
     },
 )
 _OptionalListImagesRequestListImagesPaginateTypeDef = TypedDict(
     "_OptionalListImagesRequestListImagesPaginateTypeDef",
     {
         "registryId": str,
         "filter": ListImagesFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
 class ListImagesRequestListImagesPaginateTypeDef(
     _RequiredListImagesRequestListImagesPaginateTypeDef,
@@ -1765,57 +1765,57 @@
 )
 
 BatchDeleteImageResponseTypeDef = TypedDict(
     "BatchDeleteImageResponseTypeDef",
     {
         "imageIds": List[ImageIdentifierTypeDef],
         "failures": List[ImageFailureTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetImageResponseTypeDef = TypedDict(
     "BatchGetImageResponseTypeDef",
     {
         "images": List[ImageTypeDef],
         "failures": List[ImageFailureTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutImageResponseTypeDef = TypedDict(
     "PutImageResponseTypeDef",
     {
         "image": ImageTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateRepositoryResponseTypeDef = TypedDict(
     "CreateRepositoryResponseTypeDef",
     {
         "repository": RepositoryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteRepositoryResponseTypeDef = TypedDict(
     "DeleteRepositoryResponseTypeDef",
     {
         "repository": RepositoryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeRepositoriesResponseTypeDef = TypedDict(
     "DescribeRepositoriesResponseTypeDef",
     {
         "repositories": List[RepositoryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ScoreDetailsTypeDef = TypedDict(
     "ScoreDetailsTypeDef",
     {
         "cvss": CvssScoreDetailsTypeDef,
@@ -1824,29 +1824,29 @@
 )
 
 DescribeImagesResponseTypeDef = TypedDict(
     "DescribeImagesResponseTypeDef",
     {
         "imageDetails": List[ImageDetailTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetLifecyclePolicyPreviewResponseTypeDef = TypedDict(
     "GetLifecyclePolicyPreviewResponseTypeDef",
     {
         "registryId": str,
         "repositoryName": str,
         "lifecyclePolicyText": str,
         "status": LifecyclePolicyPreviewStatusType,
         "nextToken": str,
         "previewResults": List[LifecyclePolicyPreviewResultTypeDef],
         "summary": LifecyclePolicyPreviewSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutRegistryScanningConfigurationRequestRequestTypeDef = TypedDict(
     "PutRegistryScanningConfigurationRequestRequestTypeDef",
     {
         "scanType": ScanTypeType,
@@ -1865,15 +1865,15 @@
 )
 
 BatchGetRepositoryScanningConfigurationResponseTypeDef = TypedDict(
     "BatchGetRepositoryScanningConfigurationResponseTypeDef",
     {
         "scanningConfigurations": List[RepositoryScanningConfigurationTypeDef],
         "failures": List[RepositoryScanningConfigurationFailureTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReplicationConfigurationTypeDef = TypedDict(
     "ReplicationConfigurationTypeDef",
     {
         "rules": List[ReplicationRuleTypeDef],
@@ -1903,47 +1903,47 @@
 )
 
 GetRegistryScanningConfigurationResponseTypeDef = TypedDict(
     "GetRegistryScanningConfigurationResponseTypeDef",
     {
         "registryId": str,
         "scanningConfiguration": RegistryScanningConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutRegistryScanningConfigurationResponseTypeDef = TypedDict(
     "PutRegistryScanningConfigurationResponseTypeDef",
     {
         "registryScanningConfiguration": RegistryScanningConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeRegistryResponseTypeDef = TypedDict(
     "DescribeRegistryResponseTypeDef",
     {
         "registryId": str,
         "replicationConfiguration": ReplicationConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutReplicationConfigurationRequestRequestTypeDef = TypedDict(
     "PutReplicationConfigurationRequestRequestTypeDef",
     {
         "replicationConfiguration": ReplicationConfigurationTypeDef,
     },
 )
 
 PutReplicationConfigurationResponseTypeDef = TypedDict(
     "PutReplicationConfigurationResponseTypeDef",
     {
         "replicationConfiguration": ReplicationConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ImageScanFindingsTypeDef = TypedDict(
     "ImageScanFindingsTypeDef",
     {
         "imageScanCompletedAt": datetime,
@@ -1960,10 +1960,10 @@
     {
         "registryId": str,
         "repositoryName": str,
         "imageId": ImageIdentifierTypeDef,
         "imageScanStatus": ImageScanStatusTypeDef,
         "imageScanFindings": ImageScanFindingsTypeDef,
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-ecr-2.5.0.post1/types_aiobotocore_ecr/type_defs.pyi` & `types-aiobotocore-ecr-2.5.1/types_aiobotocore_ecr/type_defs.pyi`

 * *Files 7% similar despite different names*

```diff
@@ -44,101 +44,101 @@
 __all__ = (
     "AttributeTypeDef",
     "AuthorizationDataTypeDef",
     "AwsEcrContainerImageDetailsTypeDef",
     "BatchCheckLayerAvailabilityRequestRequestTypeDef",
     "LayerFailureTypeDef",
     "LayerTypeDef",
-    "ResponseMetadataTypeDef",
     "ImageIdentifierTypeDef",
     "BatchGetRepositoryScanningConfigurationRequestRequestTypeDef",
     "RepositoryScanningConfigurationFailureTypeDef",
     "CompleteLayerUploadRequestRequestTypeDef",
+    "CompleteLayerUploadResponseTypeDef",
     "CreatePullThroughCacheRuleRequestRequestTypeDef",
+    "CreatePullThroughCacheRuleResponseTypeDef",
     "EncryptionConfigurationTypeDef",
     "ImageScanningConfigurationTypeDef",
     "TagTypeDef",
     "CvssScoreAdjustmentTypeDef",
     "CvssScoreTypeDef",
     "DeleteLifecyclePolicyRequestRequestTypeDef",
+    "DeleteLifecyclePolicyResponseTypeDef",
     "DeletePullThroughCacheRuleRequestRequestTypeDef",
+    "DeletePullThroughCacheRuleResponseTypeDef",
+    "DeleteRegistryPolicyResponseTypeDef",
     "DeleteRepositoryPolicyRequestRequestTypeDef",
+    "DeleteRepositoryPolicyResponseTypeDef",
     "DeleteRepositoryRequestRequestTypeDef",
     "ImageReplicationStatusTypeDef",
-    "PaginatorConfigTypeDef",
     "WaiterConfigTypeDef",
     "ImageScanStatusTypeDef",
     "DescribeImagesFilterTypeDef",
+    "DescribePullThroughCacheRulesRequestDescribePullThroughCacheRulesPaginateTypeDef",
     "DescribePullThroughCacheRulesRequestRequestTypeDef",
     "PullThroughCacheRuleTypeDef",
+    "DescribeRepositoriesRequestDescribeRepositoriesPaginateTypeDef",
     "DescribeRepositoriesRequestRequestTypeDef",
     "GetAuthorizationTokenRequestRequestTypeDef",
     "GetDownloadUrlForLayerRequestRequestTypeDef",
+    "GetDownloadUrlForLayerResponseTypeDef",
     "LifecyclePolicyPreviewFilterTypeDef",
     "LifecyclePolicyPreviewSummaryTypeDef",
     "GetLifecyclePolicyRequestRequestTypeDef",
+    "GetLifecyclePolicyResponseTypeDef",
+    "GetRegistryPolicyResponseTypeDef",
     "GetRepositoryPolicyRequestRequestTypeDef",
+    "GetRepositoryPolicyResponseTypeDef",
     "ImageScanFindingsSummaryTypeDef",
     "InitiateLayerUploadRequestRequestTypeDef",
+    "InitiateLayerUploadResponseTypeDef",
     "LifecyclePolicyRuleActionTypeDef",
     "ListImagesFilterTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "VulnerablePackageTypeDef",
+    "PaginatorConfigTypeDef",
     "PutImageRequestRequestTypeDef",
     "PutImageTagMutabilityRequestRequestTypeDef",
+    "PutImageTagMutabilityResponseTypeDef",
     "PutLifecyclePolicyRequestRequestTypeDef",
+    "PutLifecyclePolicyResponseTypeDef",
     "PutRegistryPolicyRequestRequestTypeDef",
+    "PutRegistryPolicyResponseTypeDef",
     "RecommendationTypeDef",
     "ScanningRepositoryFilterTypeDef",
     "ReplicationDestinationTypeDef",
     "RepositoryFilterTypeDef",
+    "ResponseMetadataTypeDef",
     "SetRepositoryPolicyRequestRequestTypeDef",
+    "SetRepositoryPolicyResponseTypeDef",
     "StartLifecyclePolicyPreviewRequestRequestTypeDef",
+    "StartLifecyclePolicyPreviewResponseTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UploadLayerPartRequestRequestTypeDef",
+    "UploadLayerPartResponseTypeDef",
     "ImageScanFindingTypeDef",
+    "GetAuthorizationTokenResponseTypeDef",
     "ResourceDetailsTypeDef",
     "BatchCheckLayerAvailabilityResponseTypeDef",
-    "CompleteLayerUploadResponseTypeDef",
-    "CreatePullThroughCacheRuleResponseTypeDef",
-    "DeleteLifecyclePolicyResponseTypeDef",
-    "DeletePullThroughCacheRuleResponseTypeDef",
-    "DeleteRegistryPolicyResponseTypeDef",
-    "DeleteRepositoryPolicyResponseTypeDef",
-    "GetAuthorizationTokenResponseTypeDef",
-    "GetDownloadUrlForLayerResponseTypeDef",
-    "GetLifecyclePolicyResponseTypeDef",
-    "GetRegistryPolicyResponseTypeDef",
-    "GetRepositoryPolicyResponseTypeDef",
-    "InitiateLayerUploadResponseTypeDef",
-    "PutImageTagMutabilityResponseTypeDef",
-    "PutLifecyclePolicyResponseTypeDef",
-    "PutRegistryPolicyResponseTypeDef",
-    "SetRepositoryPolicyResponseTypeDef",
-    "StartLifecyclePolicyPreviewResponseTypeDef",
-    "UploadLayerPartResponseTypeDef",
     "BatchDeleteImageRequestRequestTypeDef",
     "BatchGetImageRequestRequestTypeDef",
     "DescribeImageReplicationStatusRequestRequestTypeDef",
+    "DescribeImageScanFindingsRequestDescribeImageScanFindingsPaginateTypeDef",
     "DescribeImageScanFindingsRequestRequestTypeDef",
     "ImageFailureTypeDef",
     "ImageTypeDef",
     "ListImagesResponseTypeDef",
     "StartImageScanRequestRequestTypeDef",
     "PutImageScanningConfigurationRequestRequestTypeDef",
     "PutImageScanningConfigurationResponseTypeDef",
     "RepositoryTypeDef",
     "CreateRepositoryRequestRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "CvssScoreDetailsTypeDef",
     "DescribeImageReplicationStatusResponseTypeDef",
-    "DescribeImageScanFindingsRequestDescribeImageScanFindingsPaginateTypeDef",
-    "DescribePullThroughCacheRulesRequestDescribePullThroughCacheRulesPaginateTypeDef",
-    "DescribeRepositoriesRequestDescribeRepositoriesPaginateTypeDef",
     "DescribeImageScanFindingsRequestImageScanCompleteWaitTypeDef",
     "StartImageScanResponseTypeDef",
     "DescribeImagesRequestDescribeImagesPaginateTypeDef",
     "DescribeImagesRequestRequestTypeDef",
     "DescribePullThroughCacheRulesResponseTypeDef",
     "GetLifecyclePolicyPreviewRequestGetLifecyclePolicyPreviewPaginateTypeDef",
     "GetLifecyclePolicyPreviewRequestLifecyclePolicyPreviewCompleteWaitTypeDef",
@@ -256,25 +256,14 @@
         "layerAvailability": LayerAvailabilityType,
         "layerSize": int,
         "mediaType": str,
     },
     total=False,
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
 ImageIdentifierTypeDef = TypedDict(
     "ImageIdentifierTypeDef",
     {
         "imageDigest": str,
         "imageTag": str,
     },
     total=False,
@@ -315,14 +304,25 @@
 
 class CompleteLayerUploadRequestRequestTypeDef(
     _RequiredCompleteLayerUploadRequestRequestTypeDef,
     _OptionalCompleteLayerUploadRequestRequestTypeDef,
 ):
     pass
 
+CompleteLayerUploadResponseTypeDef = TypedDict(
+    "CompleteLayerUploadResponseTypeDef",
+    {
+        "registryId": str,
+        "repositoryName": str,
+        "uploadId": str,
+        "layerDigest": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreatePullThroughCacheRuleRequestRequestTypeDef = TypedDict(
     "_RequiredCreatePullThroughCacheRuleRequestRequestTypeDef",
     {
         "ecrRepositoryPrefix": str,
         "upstreamRegistryUrl": str,
     },
 )
@@ -336,14 +336,25 @@
 
 class CreatePullThroughCacheRuleRequestRequestTypeDef(
     _RequiredCreatePullThroughCacheRuleRequestRequestTypeDef,
     _OptionalCreatePullThroughCacheRuleRequestRequestTypeDef,
 ):
     pass
 
+CreatePullThroughCacheRuleResponseTypeDef = TypedDict(
+    "CreatePullThroughCacheRuleResponseTypeDef",
+    {
+        "ecrRepositoryPrefix": str,
+        "upstreamRegistryUrl": str,
+        "createdAt": datetime,
+        "registryId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredEncryptionConfigurationTypeDef = TypedDict(
     "_RequiredEncryptionConfigurationTypeDef",
     {
         "encryptionType": EncryptionTypeType,
     },
 )
 _OptionalEncryptionConfigurationTypeDef = TypedDict(
@@ -412,14 +423,25 @@
 
 class DeleteLifecyclePolicyRequestRequestTypeDef(
     _RequiredDeleteLifecyclePolicyRequestRequestTypeDef,
     _OptionalDeleteLifecyclePolicyRequestRequestTypeDef,
 ):
     pass
 
+DeleteLifecyclePolicyResponseTypeDef = TypedDict(
+    "DeleteLifecyclePolicyResponseTypeDef",
+    {
+        "registryId": str,
+        "repositoryName": str,
+        "lifecyclePolicyText": str,
+        "lastEvaluatedAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeletePullThroughCacheRuleRequestRequestTypeDef = TypedDict(
     "_RequiredDeletePullThroughCacheRuleRequestRequestTypeDef",
     {
         "ecrRepositoryPrefix": str,
     },
 )
 _OptionalDeletePullThroughCacheRuleRequestRequestTypeDef = TypedDict(
@@ -432,14 +454,34 @@
 
 class DeletePullThroughCacheRuleRequestRequestTypeDef(
     _RequiredDeletePullThroughCacheRuleRequestRequestTypeDef,
     _OptionalDeletePullThroughCacheRuleRequestRequestTypeDef,
 ):
     pass
 
+DeletePullThroughCacheRuleResponseTypeDef = TypedDict(
+    "DeletePullThroughCacheRuleResponseTypeDef",
+    {
+        "ecrRepositoryPrefix": str,
+        "upstreamRegistryUrl": str,
+        "createdAt": datetime,
+        "registryId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DeleteRegistryPolicyResponseTypeDef = TypedDict(
+    "DeleteRegistryPolicyResponseTypeDef",
+    {
+        "registryId": str,
+        "policyText": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteRepositoryPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteRepositoryPolicyRequestRequestTypeDef",
     {
         "repositoryName": str,
     },
 )
 _OptionalDeleteRepositoryPolicyRequestRequestTypeDef = TypedDict(
@@ -452,14 +494,24 @@
 
 class DeleteRepositoryPolicyRequestRequestTypeDef(
     _RequiredDeleteRepositoryPolicyRequestRequestTypeDef,
     _OptionalDeleteRepositoryPolicyRequestRequestTypeDef,
 ):
     pass
 
+DeleteRepositoryPolicyResponseTypeDef = TypedDict(
+    "DeleteRepositoryPolicyResponseTypeDef",
+    {
+        "registryId": str,
+        "repositoryName": str,
+        "policyText": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteRepositoryRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteRepositoryRequestRequestTypeDef",
     {
         "repositoryName": str,
     },
 )
 _OptionalDeleteRepositoryRequestRequestTypeDef = TypedDict(
@@ -483,24 +535,14 @@
         "registryId": str,
         "status": ReplicationStatusType,
         "failureCode": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
-    {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
-    },
-    total=False,
-)
-
 WaiterConfigTypeDef = TypedDict(
     "WaiterConfigTypeDef",
     {
         "Delay": int,
         "MaxAttempts": int,
     },
     total=False,
@@ -519,14 +561,24 @@
     "DescribeImagesFilterTypeDef",
     {
         "tagStatus": TagStatusType,
     },
     total=False,
 )
 
+DescribePullThroughCacheRulesRequestDescribePullThroughCacheRulesPaginateTypeDef = TypedDict(
+    "DescribePullThroughCacheRulesRequestDescribePullThroughCacheRulesPaginateTypeDef",
+    {
+        "registryId": str,
+        "ecrRepositoryPrefixes": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribePullThroughCacheRulesRequestRequestTypeDef = TypedDict(
     "DescribePullThroughCacheRulesRequestRequestTypeDef",
     {
         "registryId": str,
         "ecrRepositoryPrefixes": Sequence[str],
         "nextToken": str,
         "maxResults": int,
@@ -541,14 +593,24 @@
         "upstreamRegistryUrl": str,
         "createdAt": datetime,
         "registryId": str,
     },
     total=False,
 )
 
+DescribeRepositoriesRequestDescribeRepositoriesPaginateTypeDef = TypedDict(
+    "DescribeRepositoriesRequestDescribeRepositoriesPaginateTypeDef",
+    {
+        "registryId": str,
+        "repositoryNames": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeRepositoriesRequestRequestTypeDef = TypedDict(
     "DescribeRepositoriesRequestRequestTypeDef",
     {
         "registryId": str,
         "repositoryNames": Sequence[str],
         "nextToken": str,
         "maxResults": int,
@@ -581,14 +643,23 @@
 
 class GetDownloadUrlForLayerRequestRequestTypeDef(
     _RequiredGetDownloadUrlForLayerRequestRequestTypeDef,
     _OptionalGetDownloadUrlForLayerRequestRequestTypeDef,
 ):
     pass
 
+GetDownloadUrlForLayerResponseTypeDef = TypedDict(
+    "GetDownloadUrlForLayerResponseTypeDef",
+    {
+        "downloadUrl": str,
+        "layerDigest": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 LifecyclePolicyPreviewFilterTypeDef = TypedDict(
     "LifecyclePolicyPreviewFilterTypeDef",
     {
         "tagStatus": TagStatusType,
     },
     total=False,
 )
@@ -617,14 +688,34 @@
 
 class GetLifecyclePolicyRequestRequestTypeDef(
     _RequiredGetLifecyclePolicyRequestRequestTypeDef,
     _OptionalGetLifecyclePolicyRequestRequestTypeDef,
 ):
     pass
 
+GetLifecyclePolicyResponseTypeDef = TypedDict(
+    "GetLifecyclePolicyResponseTypeDef",
+    {
+        "registryId": str,
+        "repositoryName": str,
+        "lifecyclePolicyText": str,
+        "lastEvaluatedAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetRegistryPolicyResponseTypeDef = TypedDict(
+    "GetRegistryPolicyResponseTypeDef",
+    {
+        "registryId": str,
+        "policyText": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetRepositoryPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredGetRepositoryPolicyRequestRequestTypeDef",
     {
         "repositoryName": str,
     },
 )
 _OptionalGetRepositoryPolicyRequestRequestTypeDef = TypedDict(
@@ -637,14 +728,24 @@
 
 class GetRepositoryPolicyRequestRequestTypeDef(
     _RequiredGetRepositoryPolicyRequestRequestTypeDef,
     _OptionalGetRepositoryPolicyRequestRequestTypeDef,
 ):
     pass
 
+GetRepositoryPolicyResponseTypeDef = TypedDict(
+    "GetRepositoryPolicyResponseTypeDef",
+    {
+        "registryId": str,
+        "repositoryName": str,
+        "policyText": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ImageScanFindingsSummaryTypeDef = TypedDict(
     "ImageScanFindingsSummaryTypeDef",
     {
         "imageScanCompletedAt": datetime,
         "vulnerabilitySourceUpdatedAt": datetime,
         "findingSeverityCounts": Dict[FindingSeverityType, int],
     },
@@ -667,14 +768,23 @@
 
 class InitiateLayerUploadRequestRequestTypeDef(
     _RequiredInitiateLayerUploadRequestRequestTypeDef,
     _OptionalInitiateLayerUploadRequestRequestTypeDef,
 ):
     pass
 
+InitiateLayerUploadResponseTypeDef = TypedDict(
+    "InitiateLayerUploadResponseTypeDef",
+    {
+        "uploadId": str,
+        "partSize": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 LifecyclePolicyRuleActionTypeDef = TypedDict(
     "LifecyclePolicyRuleActionTypeDef",
     {
         "type": Literal["EXPIRE"],
     },
     total=False,
 )
@@ -705,14 +815,24 @@
         "release": str,
         "sourceLayerHash": str,
         "version": str,
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
 _RequiredPutImageRequestRequestTypeDef = TypedDict(
     "_RequiredPutImageRequestRequestTypeDef",
     {
         "repositoryName": str,
         "imageManifest": str,
     },
 )
@@ -749,14 +869,24 @@
 
 class PutImageTagMutabilityRequestRequestTypeDef(
     _RequiredPutImageTagMutabilityRequestRequestTypeDef,
     _OptionalPutImageTagMutabilityRequestRequestTypeDef,
 ):
     pass
 
+PutImageTagMutabilityResponseTypeDef = TypedDict(
+    "PutImageTagMutabilityResponseTypeDef",
+    {
+        "registryId": str,
+        "repositoryName": str,
+        "imageTagMutability": ImageTagMutabilityType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredPutLifecyclePolicyRequestRequestTypeDef = TypedDict(
     "_RequiredPutLifecyclePolicyRequestRequestTypeDef",
     {
         "repositoryName": str,
         "lifecyclePolicyText": str,
     },
 )
@@ -770,21 +900,40 @@
 
 class PutLifecyclePolicyRequestRequestTypeDef(
     _RequiredPutLifecyclePolicyRequestRequestTypeDef,
     _OptionalPutLifecyclePolicyRequestRequestTypeDef,
 ):
     pass
 
+PutLifecyclePolicyResponseTypeDef = TypedDict(
+    "PutLifecyclePolicyResponseTypeDef",
+    {
+        "registryId": str,
+        "repositoryName": str,
+        "lifecyclePolicyText": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 PutRegistryPolicyRequestRequestTypeDef = TypedDict(
     "PutRegistryPolicyRequestRequestTypeDef",
     {
         "policyText": str,
     },
 )
 
+PutRegistryPolicyResponseTypeDef = TypedDict(
+    "PutRegistryPolicyResponseTypeDef",
+    {
+        "registryId": str,
+        "policyText": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RecommendationTypeDef = TypedDict(
     "RecommendationTypeDef",
     {
         "url": str,
         "text": str,
     },
     total=False,
@@ -810,14 +959,25 @@
     "RepositoryFilterTypeDef",
     {
         "filter": str,
         "filterType": Literal["PREFIX_MATCH"],
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
 _RequiredSetRepositoryPolicyRequestRequestTypeDef = TypedDict(
     "_RequiredSetRepositoryPolicyRequestRequestTypeDef",
     {
         "repositoryName": str,
         "policyText": str,
     },
 )
@@ -832,14 +992,24 @@
 
 class SetRepositoryPolicyRequestRequestTypeDef(
     _RequiredSetRepositoryPolicyRequestRequestTypeDef,
     _OptionalSetRepositoryPolicyRequestRequestTypeDef,
 ):
     pass
 
+SetRepositoryPolicyResponseTypeDef = TypedDict(
+    "SetRepositoryPolicyResponseTypeDef",
+    {
+        "registryId": str,
+        "repositoryName": str,
+        "policyText": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredStartLifecyclePolicyPreviewRequestRequestTypeDef = TypedDict(
     "_RequiredStartLifecyclePolicyPreviewRequestRequestTypeDef",
     {
         "repositoryName": str,
     },
 )
 _OptionalStartLifecyclePolicyPreviewRequestRequestTypeDef = TypedDict(
@@ -853,14 +1023,25 @@
 
 class StartLifecyclePolicyPreviewRequestRequestTypeDef(
     _RequiredStartLifecyclePolicyPreviewRequestRequestTypeDef,
     _OptionalStartLifecyclePolicyPreviewRequestRequestTypeDef,
 ):
     pass
 
+StartLifecyclePolicyPreviewResponseTypeDef = TypedDict(
+    "StartLifecyclePolicyPreviewResponseTypeDef",
+    {
+        "registryId": str,
+        "repositoryName": str,
+        "lifecyclePolicyText": str,
+        "status": LifecyclePolicyPreviewStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
@@ -884,220 +1065,59 @@
 )
 
 class UploadLayerPartRequestRequestTypeDef(
     _RequiredUploadLayerPartRequestRequestTypeDef, _OptionalUploadLayerPartRequestRequestTypeDef
 ):
     pass
 
+UploadLayerPartResponseTypeDef = TypedDict(
+    "UploadLayerPartResponseTypeDef",
+    {
+        "registryId": str,
+        "repositoryName": str,
+        "uploadId": str,
+        "lastByteReceived": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ImageScanFindingTypeDef = TypedDict(
     "ImageScanFindingTypeDef",
     {
         "name": str,
         "description": str,
         "uri": str,
         "severity": FindingSeverityType,
         "attributes": List[AttributeTypeDef],
     },
     total=False,
 )
 
+GetAuthorizationTokenResponseTypeDef = TypedDict(
+    "GetAuthorizationTokenResponseTypeDef",
+    {
+        "authorizationData": List[AuthorizationDataTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ResourceDetailsTypeDef = TypedDict(
     "ResourceDetailsTypeDef",
     {
         "awsEcrContainerImage": AwsEcrContainerImageDetailsTypeDef,
     },
     total=False,
 )
 
 BatchCheckLayerAvailabilityResponseTypeDef = TypedDict(
     "BatchCheckLayerAvailabilityResponseTypeDef",
     {
         "layers": List[LayerTypeDef],
         "failures": List[LayerFailureTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CompleteLayerUploadResponseTypeDef = TypedDict(
-    "CompleteLayerUploadResponseTypeDef",
-    {
-        "registryId": str,
-        "repositoryName": str,
-        "uploadId": str,
-        "layerDigest": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreatePullThroughCacheRuleResponseTypeDef = TypedDict(
-    "CreatePullThroughCacheRuleResponseTypeDef",
-    {
-        "ecrRepositoryPrefix": str,
-        "upstreamRegistryUrl": str,
-        "createdAt": datetime,
-        "registryId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteLifecyclePolicyResponseTypeDef = TypedDict(
-    "DeleteLifecyclePolicyResponseTypeDef",
-    {
-        "registryId": str,
-        "repositoryName": str,
-        "lifecyclePolicyText": str,
-        "lastEvaluatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeletePullThroughCacheRuleResponseTypeDef = TypedDict(
-    "DeletePullThroughCacheRuleResponseTypeDef",
-    {
-        "ecrRepositoryPrefix": str,
-        "upstreamRegistryUrl": str,
-        "createdAt": datetime,
-        "registryId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteRegistryPolicyResponseTypeDef = TypedDict(
-    "DeleteRegistryPolicyResponseTypeDef",
-    {
-        "registryId": str,
-        "policyText": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteRepositoryPolicyResponseTypeDef = TypedDict(
-    "DeleteRepositoryPolicyResponseTypeDef",
-    {
-        "registryId": str,
-        "repositoryName": str,
-        "policyText": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetAuthorizationTokenResponseTypeDef = TypedDict(
-    "GetAuthorizationTokenResponseTypeDef",
-    {
-        "authorizationData": List[AuthorizationDataTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetDownloadUrlForLayerResponseTypeDef = TypedDict(
-    "GetDownloadUrlForLayerResponseTypeDef",
-    {
-        "downloadUrl": str,
-        "layerDigest": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetLifecyclePolicyResponseTypeDef = TypedDict(
-    "GetLifecyclePolicyResponseTypeDef",
-    {
-        "registryId": str,
-        "repositoryName": str,
-        "lifecyclePolicyText": str,
-        "lastEvaluatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetRegistryPolicyResponseTypeDef = TypedDict(
-    "GetRegistryPolicyResponseTypeDef",
-    {
-        "registryId": str,
-        "policyText": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetRepositoryPolicyResponseTypeDef = TypedDict(
-    "GetRepositoryPolicyResponseTypeDef",
-    {
-        "registryId": str,
-        "repositoryName": str,
-        "policyText": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-InitiateLayerUploadResponseTypeDef = TypedDict(
-    "InitiateLayerUploadResponseTypeDef",
-    {
-        "uploadId": str,
-        "partSize": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutImageTagMutabilityResponseTypeDef = TypedDict(
-    "PutImageTagMutabilityResponseTypeDef",
-    {
-        "registryId": str,
-        "repositoryName": str,
-        "imageTagMutability": ImageTagMutabilityType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutLifecyclePolicyResponseTypeDef = TypedDict(
-    "PutLifecyclePolicyResponseTypeDef",
-    {
-        "registryId": str,
-        "repositoryName": str,
-        "lifecyclePolicyText": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutRegistryPolicyResponseTypeDef = TypedDict(
-    "PutRegistryPolicyResponseTypeDef",
-    {
-        "registryId": str,
-        "policyText": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SetRepositoryPolicyResponseTypeDef = TypedDict(
-    "SetRepositoryPolicyResponseTypeDef",
-    {
-        "registryId": str,
-        "repositoryName": str,
-        "policyText": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartLifecyclePolicyPreviewResponseTypeDef = TypedDict(
-    "StartLifecyclePolicyPreviewResponseTypeDef",
-    {
-        "registryId": str,
-        "repositoryName": str,
-        "lifecyclePolicyText": str,
-        "status": LifecyclePolicyPreviewStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UploadLayerPartResponseTypeDef = TypedDict(
-    "UploadLayerPartResponseTypeDef",
-    {
-        "registryId": str,
-        "repositoryName": str,
-        "uploadId": str,
-        "lastByteReceived": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredBatchDeleteImageRequestRequestTypeDef = TypedDict(
     "_RequiredBatchDeleteImageRequestRequestTypeDef",
     {
         "repositoryName": str,
@@ -1155,14 +1175,36 @@
 
 class DescribeImageReplicationStatusRequestRequestTypeDef(
     _RequiredDescribeImageReplicationStatusRequestRequestTypeDef,
     _OptionalDescribeImageReplicationStatusRequestRequestTypeDef,
 ):
     pass
 
+_RequiredDescribeImageScanFindingsRequestDescribeImageScanFindingsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeImageScanFindingsRequestDescribeImageScanFindingsPaginateTypeDef",
+    {
+        "repositoryName": str,
+        "imageId": ImageIdentifierTypeDef,
+    },
+)
+_OptionalDescribeImageScanFindingsRequestDescribeImageScanFindingsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeImageScanFindingsRequestDescribeImageScanFindingsPaginateTypeDef",
+    {
+        "registryId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeImageScanFindingsRequestDescribeImageScanFindingsPaginateTypeDef(
+    _RequiredDescribeImageScanFindingsRequestDescribeImageScanFindingsPaginateTypeDef,
+    _OptionalDescribeImageScanFindingsRequestDescribeImageScanFindingsPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeImageScanFindingsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeImageScanFindingsRequestRequestTypeDef",
     {
         "repositoryName": str,
         "imageId": ImageIdentifierTypeDef,
     },
 )
@@ -1205,15 +1247,15 @@
 )
 
 ListImagesResponseTypeDef = TypedDict(
     "ListImagesResponseTypeDef",
     {
         "imageIds": List[ImageIdentifierTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStartImageScanRequestRequestTypeDef = TypedDict(
     "_RequiredStartImageScanRequestRequestTypeDef",
     {
         "repositoryName": str,
@@ -1256,15 +1298,15 @@
 
 PutImageScanningConfigurationResponseTypeDef = TypedDict(
     "PutImageScanningConfigurationResponseTypeDef",
     {
         "registryId": str,
         "repositoryName": str,
         "imageScanningConfiguration": ImageScanningConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RepositoryTypeDef = TypedDict(
     "RepositoryTypeDef",
     {
         "repositoryArn": str,
@@ -1302,15 +1344,15 @@
 ):
     pass
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
@@ -1332,60 +1374,18 @@
 
 DescribeImageReplicationStatusResponseTypeDef = TypedDict(
     "DescribeImageReplicationStatusResponseTypeDef",
     {
         "repositoryName": str,
         "imageId": ImageIdentifierTypeDef,
         "replicationStatuses": List[ImageReplicationStatusTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-_RequiredDescribeImageScanFindingsRequestDescribeImageScanFindingsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeImageScanFindingsRequestDescribeImageScanFindingsPaginateTypeDef",
-    {
-        "repositoryName": str,
-        "imageId": ImageIdentifierTypeDef,
-    },
-)
-_OptionalDescribeImageScanFindingsRequestDescribeImageScanFindingsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeImageScanFindingsRequestDescribeImageScanFindingsPaginateTypeDef",
-    {
-        "registryId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeImageScanFindingsRequestDescribeImageScanFindingsPaginateTypeDef(
-    _RequiredDescribeImageScanFindingsRequestDescribeImageScanFindingsPaginateTypeDef,
-    _OptionalDescribeImageScanFindingsRequestDescribeImageScanFindingsPaginateTypeDef,
-):
-    pass
-
-DescribePullThroughCacheRulesRequestDescribePullThroughCacheRulesPaginateTypeDef = TypedDict(
-    "DescribePullThroughCacheRulesRequestDescribePullThroughCacheRulesPaginateTypeDef",
-    {
-        "registryId": str,
-        "ecrRepositoryPrefixes": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeRepositoriesRequestDescribeRepositoriesPaginateTypeDef = TypedDict(
-    "DescribeRepositoriesRequestDescribeRepositoriesPaginateTypeDef",
-    {
-        "registryId": str,
-        "repositoryNames": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 _RequiredDescribeImageScanFindingsRequestImageScanCompleteWaitTypeDef = TypedDict(
     "_RequiredDescribeImageScanFindingsRequestImageScanCompleteWaitTypeDef",
     {
         "repositoryName": str,
         "imageId": ImageIdentifierTypeDef,
     },
 )
@@ -1409,15 +1409,15 @@
 StartImageScanResponseTypeDef = TypedDict(
     "StartImageScanResponseTypeDef",
     {
         "registryId": str,
         "repositoryName": str,
         "imageId": ImageIdentifierTypeDef,
         "imageScanStatus": ImageScanStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDescribeImagesRequestDescribeImagesPaginateTypeDef = TypedDict(
     "_RequiredDescribeImagesRequestDescribeImagesPaginateTypeDef",
     {
         "repositoryName": str,
@@ -1425,15 +1425,15 @@
 )
 _OptionalDescribeImagesRequestDescribeImagesPaginateTypeDef = TypedDict(
     "_OptionalDescribeImagesRequestDescribeImagesPaginateTypeDef",
     {
         "registryId": str,
         "imageIds": Sequence[ImageIdentifierTypeDef],
         "filter": DescribeImagesFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 class DescribeImagesRequestDescribeImagesPaginateTypeDef(
     _RequiredDescribeImagesRequestDescribeImagesPaginateTypeDef,
     _OptionalDescribeImagesRequestDescribeImagesPaginateTypeDef,
@@ -1464,15 +1464,15 @@
     pass
 
 DescribePullThroughCacheRulesResponseTypeDef = TypedDict(
     "DescribePullThroughCacheRulesResponseTypeDef",
     {
         "pullThroughCacheRules": List[PullThroughCacheRuleTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetLifecyclePolicyPreviewRequestGetLifecyclePolicyPreviewPaginateTypeDef = TypedDict(
     "_RequiredGetLifecyclePolicyPreviewRequestGetLifecyclePolicyPreviewPaginateTypeDef",
     {
         "repositoryName": str,
@@ -1480,15 +1480,15 @@
 )
 _OptionalGetLifecyclePolicyPreviewRequestGetLifecyclePolicyPreviewPaginateTypeDef = TypedDict(
     "_OptionalGetLifecyclePolicyPreviewRequestGetLifecyclePolicyPreviewPaginateTypeDef",
     {
         "registryId": str,
         "imageIds": Sequence[ImageIdentifierTypeDef],
         "filter": LifecyclePolicyPreviewFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 class GetLifecyclePolicyPreviewRequestGetLifecyclePolicyPreviewPaginateTypeDef(
     _RequiredGetLifecyclePolicyPreviewRequestGetLifecyclePolicyPreviewPaginateTypeDef,
     _OptionalGetLifecyclePolicyPreviewRequestGetLifecyclePolicyPreviewPaginateTypeDef,
@@ -1581,15 +1581,15 @@
     },
 )
 _OptionalListImagesRequestListImagesPaginateTypeDef = TypedDict(
     "_OptionalListImagesRequestListImagesPaginateTypeDef",
     {
         "registryId": str,
         "filter": ListImagesFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 class ListImagesRequestListImagesPaginateTypeDef(
     _RequiredListImagesRequestListImagesPaginateTypeDef,
     _OptionalListImagesRequestListImagesPaginateTypeDef,
@@ -1692,57 +1692,57 @@
 )
 
 BatchDeleteImageResponseTypeDef = TypedDict(
     "BatchDeleteImageResponseTypeDef",
     {
         "imageIds": List[ImageIdentifierTypeDef],
         "failures": List[ImageFailureTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetImageResponseTypeDef = TypedDict(
     "BatchGetImageResponseTypeDef",
     {
         "images": List[ImageTypeDef],
         "failures": List[ImageFailureTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutImageResponseTypeDef = TypedDict(
     "PutImageResponseTypeDef",
     {
         "image": ImageTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateRepositoryResponseTypeDef = TypedDict(
     "CreateRepositoryResponseTypeDef",
     {
         "repository": RepositoryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteRepositoryResponseTypeDef = TypedDict(
     "DeleteRepositoryResponseTypeDef",
     {
         "repository": RepositoryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeRepositoriesResponseTypeDef = TypedDict(
     "DescribeRepositoriesResponseTypeDef",
     {
         "repositories": List[RepositoryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ScoreDetailsTypeDef = TypedDict(
     "ScoreDetailsTypeDef",
     {
         "cvss": CvssScoreDetailsTypeDef,
@@ -1751,29 +1751,29 @@
 )
 
 DescribeImagesResponseTypeDef = TypedDict(
     "DescribeImagesResponseTypeDef",
     {
         "imageDetails": List[ImageDetailTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetLifecyclePolicyPreviewResponseTypeDef = TypedDict(
     "GetLifecyclePolicyPreviewResponseTypeDef",
     {
         "registryId": str,
         "repositoryName": str,
         "lifecyclePolicyText": str,
         "status": LifecyclePolicyPreviewStatusType,
         "nextToken": str,
         "previewResults": List[LifecyclePolicyPreviewResultTypeDef],
         "summary": LifecyclePolicyPreviewSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutRegistryScanningConfigurationRequestRequestTypeDef = TypedDict(
     "PutRegistryScanningConfigurationRequestRequestTypeDef",
     {
         "scanType": ScanTypeType,
@@ -1792,15 +1792,15 @@
 )
 
 BatchGetRepositoryScanningConfigurationResponseTypeDef = TypedDict(
     "BatchGetRepositoryScanningConfigurationResponseTypeDef",
     {
         "scanningConfigurations": List[RepositoryScanningConfigurationTypeDef],
         "failures": List[RepositoryScanningConfigurationFailureTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReplicationConfigurationTypeDef = TypedDict(
     "ReplicationConfigurationTypeDef",
     {
         "rules": List[ReplicationRuleTypeDef],
@@ -1830,47 +1830,47 @@
 )
 
 GetRegistryScanningConfigurationResponseTypeDef = TypedDict(
     "GetRegistryScanningConfigurationResponseTypeDef",
     {
         "registryId": str,
         "scanningConfiguration": RegistryScanningConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutRegistryScanningConfigurationResponseTypeDef = TypedDict(
     "PutRegistryScanningConfigurationResponseTypeDef",
     {
         "registryScanningConfiguration": RegistryScanningConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeRegistryResponseTypeDef = TypedDict(
     "DescribeRegistryResponseTypeDef",
     {
         "registryId": str,
         "replicationConfiguration": ReplicationConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutReplicationConfigurationRequestRequestTypeDef = TypedDict(
     "PutReplicationConfigurationRequestRequestTypeDef",
     {
         "replicationConfiguration": ReplicationConfigurationTypeDef,
     },
 )
 
 PutReplicationConfigurationResponseTypeDef = TypedDict(
     "PutReplicationConfigurationResponseTypeDef",
     {
         "replicationConfiguration": ReplicationConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ImageScanFindingsTypeDef = TypedDict(
     "ImageScanFindingsTypeDef",
     {
         "imageScanCompletedAt": datetime,
@@ -1887,10 +1887,10 @@
     {
         "registryId": str,
         "repositoryName": str,
         "imageId": ImageIdentifierTypeDef,
         "imageScanStatus": ImageScanStatusTypeDef,
         "imageScanFindings": ImageScanFindingsTypeDef,
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-ecr-2.5.0.post1/types_aiobotocore_ecr/waiter.py` & `types-aiobotocore-ecr-2.5.1/types_aiobotocore_ecr/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ecr-2.5.0.post1/types_aiobotocore_ecr/waiter.pyi` & `types-aiobotocore-ecr-2.5.1/types_aiobotocore_ecr/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ecr-2.5.0.post1/types_aiobotocore_ecr.egg-info/PKG-INFO` & `types-aiobotocore-ecr-2.5.1/types_aiobotocore_ecr.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-ecr
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ECR 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ECR 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-ecr"></a>
 
 # types-aiobotocore-ecr
 
 [![PyPI - types-aiobotocore-ecr](https://img.shields.io/pypi/v/types-aiobotocore-ecr.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ecr)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-ecr.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ecr)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-ecr?color=blue)](https://pypistats.org/packages/types-aiobotocore-ecr)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ECR 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR)
+[aiobotocore.ECR 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecr.html#ECR)
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
 [types-aiobotocore-ecr docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecr/).
 
 See how it helps to find and fix potential bugs:
 
@@ -391,101 +391,101 @@
 from types_aiobotocore_ecr.type_defs import (
     AttributeTypeDef,
     AuthorizationDataTypeDef,
     AwsEcrContainerImageDetailsTypeDef,
     BatchCheckLayerAvailabilityRequestRequestTypeDef,
     LayerFailureTypeDef,
     LayerTypeDef,
-    ResponseMetadataTypeDef,
     ImageIdentifierTypeDef,
     BatchGetRepositoryScanningConfigurationRequestRequestTypeDef,
     RepositoryScanningConfigurationFailureTypeDef,
     CompleteLayerUploadRequestRequestTypeDef,
+    CompleteLayerUploadResponseTypeDef,
     CreatePullThroughCacheRuleRequestRequestTypeDef,
+    CreatePullThroughCacheRuleResponseTypeDef,
     EncryptionConfigurationTypeDef,
     ImageScanningConfigurationTypeDef,
     TagTypeDef,
     CvssScoreAdjustmentTypeDef,
     CvssScoreTypeDef,
     DeleteLifecyclePolicyRequestRequestTypeDef,
+    DeleteLifecyclePolicyResponseTypeDef,
     DeletePullThroughCacheRuleRequestRequestTypeDef,
+    DeletePullThroughCacheRuleResponseTypeDef,
+    DeleteRegistryPolicyResponseTypeDef,
     DeleteRepositoryPolicyRequestRequestTypeDef,
+    DeleteRepositoryPolicyResponseTypeDef,
     DeleteRepositoryRequestRequestTypeDef,
     ImageReplicationStatusTypeDef,
-    PaginatorConfigTypeDef,
     WaiterConfigTypeDef,
     ImageScanStatusTypeDef,
     DescribeImagesFilterTypeDef,
+    DescribePullThroughCacheRulesRequestDescribePullThroughCacheRulesPaginateTypeDef,
     DescribePullThroughCacheRulesRequestRequestTypeDef,
     PullThroughCacheRuleTypeDef,
+    DescribeRepositoriesRequestDescribeRepositoriesPaginateTypeDef,
     DescribeRepositoriesRequestRequestTypeDef,
     GetAuthorizationTokenRequestRequestTypeDef,
     GetDownloadUrlForLayerRequestRequestTypeDef,
+    GetDownloadUrlForLayerResponseTypeDef,
     LifecyclePolicyPreviewFilterTypeDef,
     LifecyclePolicyPreviewSummaryTypeDef,
     GetLifecyclePolicyRequestRequestTypeDef,
+    GetLifecyclePolicyResponseTypeDef,
+    GetRegistryPolicyResponseTypeDef,
     GetRepositoryPolicyRequestRequestTypeDef,
+    GetRepositoryPolicyResponseTypeDef,
     ImageScanFindingsSummaryTypeDef,
     InitiateLayerUploadRequestRequestTypeDef,
+    InitiateLayerUploadResponseTypeDef,
     LifecyclePolicyRuleActionTypeDef,
     ListImagesFilterTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     VulnerablePackageTypeDef,
+    PaginatorConfigTypeDef,
     PutImageRequestRequestTypeDef,
     PutImageTagMutabilityRequestRequestTypeDef,
+    PutImageTagMutabilityResponseTypeDef,
     PutLifecyclePolicyRequestRequestTypeDef,
+    PutLifecyclePolicyResponseTypeDef,
     PutRegistryPolicyRequestRequestTypeDef,
+    PutRegistryPolicyResponseTypeDef,
     RecommendationTypeDef,
     ScanningRepositoryFilterTypeDef,
     ReplicationDestinationTypeDef,
     RepositoryFilterTypeDef,
+    ResponseMetadataTypeDef,
     SetRepositoryPolicyRequestRequestTypeDef,
+    SetRepositoryPolicyResponseTypeDef,
     StartLifecyclePolicyPreviewRequestRequestTypeDef,
+    StartLifecyclePolicyPreviewResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UploadLayerPartRequestRequestTypeDef,
+    UploadLayerPartResponseTypeDef,
     ImageScanFindingTypeDef,
+    GetAuthorizationTokenResponseTypeDef,
     ResourceDetailsTypeDef,
     BatchCheckLayerAvailabilityResponseTypeDef,
-    CompleteLayerUploadResponseTypeDef,
-    CreatePullThroughCacheRuleResponseTypeDef,
-    DeleteLifecyclePolicyResponseTypeDef,
-    DeletePullThroughCacheRuleResponseTypeDef,
-    DeleteRegistryPolicyResponseTypeDef,
-    DeleteRepositoryPolicyResponseTypeDef,
-    GetAuthorizationTokenResponseTypeDef,
-    GetDownloadUrlForLayerResponseTypeDef,
-    GetLifecyclePolicyResponseTypeDef,
-    GetRegistryPolicyResponseTypeDef,
-    GetRepositoryPolicyResponseTypeDef,
-    InitiateLayerUploadResponseTypeDef,
-    PutImageTagMutabilityResponseTypeDef,
-    PutLifecyclePolicyResponseTypeDef,
-    PutRegistryPolicyResponseTypeDef,
-    SetRepositoryPolicyResponseTypeDef,
-    StartLifecyclePolicyPreviewResponseTypeDef,
-    UploadLayerPartResponseTypeDef,
     BatchDeleteImageRequestRequestTypeDef,
     BatchGetImageRequestRequestTypeDef,
     DescribeImageReplicationStatusRequestRequestTypeDef,
+    DescribeImageScanFindingsRequestDescribeImageScanFindingsPaginateTypeDef,
     DescribeImageScanFindingsRequestRequestTypeDef,
     ImageFailureTypeDef,
     ImageTypeDef,
     ListImagesResponseTypeDef,
     StartImageScanRequestRequestTypeDef,
     PutImageScanningConfigurationRequestRequestTypeDef,
     PutImageScanningConfigurationResponseTypeDef,
     RepositoryTypeDef,
     CreateRepositoryRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     CvssScoreDetailsTypeDef,
     DescribeImageReplicationStatusResponseTypeDef,
-    DescribeImageScanFindingsRequestDescribeImageScanFindingsPaginateTypeDef,
-    DescribePullThroughCacheRulesRequestDescribePullThroughCacheRulesPaginateTypeDef,
-    DescribeRepositoriesRequestDescribeRepositoriesPaginateTypeDef,
     DescribeImageScanFindingsRequestImageScanCompleteWaitTypeDef,
     StartImageScanResponseTypeDef,
     DescribeImagesRequestDescribeImagesPaginateTypeDef,
     DescribeImagesRequestRequestTypeDef,
     DescribePullThroughCacheRulesResponseTypeDef,
     GetLifecyclePolicyPreviewRequestGetLifecyclePolicyPreviewPaginateTypeDef,
     GetLifecyclePolicyPreviewRequestLifecyclePolicyPreviewCompleteWaitTypeDef,
@@ -531,43 +531,43 @@
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

### Comparing `types-aiobotocore-ecr-2.5.0.post1/types_aiobotocore_ecr.egg-info/SOURCES.txt` & `types-aiobotocore-ecr-2.5.1/types_aiobotocore_ecr.egg-info/SOURCES.txt`

 * *Files identical despite different names*

