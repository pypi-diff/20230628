# Comparing `tmp/types-aiobotocore-lambda-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-lambda-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-lambda-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:53 2023, max compression
+gzip compressed data, was "types-aiobotocore-lambda-2.5.1.tar", last modified: Wed Jun 28 01:43:44 2023, max compression
```

## Comparing `types-aiobotocore-lambda-2.5.0.post1.tar` & `types-aiobotocore-lambda-2.5.1.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:53.671366 types-aiobotocore-lambda-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:17:10.000000 types-aiobotocore-lambda-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    24430 2023-03-11 12:26:53.671366 types-aiobotocore-lambda-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    22863 2023-03-11 12:17:10.000000 types-aiobotocore-lambda-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:53.671366 types-aiobotocore-lambda-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2117 2023-03-11 12:17:10.000000 types-aiobotocore-lambda-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:53.667366 types-aiobotocore-lambda-2.5.0.post1/types_aiobotocore_lambda/
--rw-r--r--   0 runner    (1001) docker     (123)     4232 2023-03-11 12:17:10.000000 types-aiobotocore-lambda-2.5.0.post1/types_aiobotocore_lambda/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4231 2023-03-11 12:17:10.000000 types-aiobotocore-lambda-2.5.0.post1/types_aiobotocore_lambda/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      928 2023-03-11 12:17:10.000000 types-aiobotocore-lambda-2.5.0.post1/types_aiobotocore_lambda/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    61559 2023-03-11 12:17:12.000000 types-aiobotocore-lambda-2.5.0.post1/types_aiobotocore_lambda/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    61468 2023-03-11 12:17:10.000000 types-aiobotocore-lambda-2.5.0.post1/types_aiobotocore_lambda/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    13750 2023-03-11 12:17:13.000000 types-aiobotocore-lambda-2.5.0.post1/types_aiobotocore_lambda/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    13748 2023-03-11 12:17:13.000000 types-aiobotocore-lambda-2.5.0.post1/types_aiobotocore_lambda/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    14417 2023-03-11 12:17:12.000000 types-aiobotocore-lambda-2.5.0.post1/types_aiobotocore_lambda/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    14403 2023-03-11 12:17:12.000000 types-aiobotocore-lambda-2.5.0.post1/types_aiobotocore_lambda/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:17:10.000000 types-aiobotocore-lambda-2.5.0.post1/types_aiobotocore_lambda/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    75713 2023-03-11 12:17:14.000000 types-aiobotocore-lambda-2.5.0.post1/types_aiobotocore_lambda/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    75608 2023-03-11 12:17:13.000000 types-aiobotocore-lambda-2.5.0.post1/types_aiobotocore_lambda/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:17:10.000000 types-aiobotocore-lambda-2.5.0.post1/types_aiobotocore_lambda/version.py
--rw-r--r--   0 runner    (1001) docker     (123)     6547 2023-03-11 12:17:12.000000 types-aiobotocore-lambda-2.5.0.post1/types_aiobotocore_lambda/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)     6541 2023-03-11 12:17:12.000000 types-aiobotocore-lambda-2.5.0.post1/types_aiobotocore_lambda/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:53.671366 types-aiobotocore-lambda-2.5.0.post1/types_aiobotocore_lambda.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    24430 2023-03-11 12:26:53.000000 types-aiobotocore-lambda-2.5.0.post1/types_aiobotocore_lambda.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      865 2023-03-11 12:26:53.000000 types-aiobotocore-lambda-2.5.0.post1/types_aiobotocore_lambda.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:53.000000 types-aiobotocore-lambda-2.5.0.post1/types_aiobotocore_lambda.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:53.000000 types-aiobotocore-lambda-2.5.0.post1/types_aiobotocore_lambda.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:53.000000 types-aiobotocore-lambda-2.5.0.post1/types_aiobotocore_lambda.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:53.000000 types-aiobotocore-lambda-2.5.0.post1/types_aiobotocore_lambda.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:44.902166 types-aiobotocore-lambda-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:33:51.000000 types-aiobotocore-lambda-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    24779 2023-06-28 01:43:44.902166 types-aiobotocore-lambda-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    23218 2023-06-28 01:33:51.000000 types-aiobotocore-lambda-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:44.902166 types-aiobotocore-lambda-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2111 2023-06-28 01:33:51.000000 types-aiobotocore-lambda-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:44.902166 types-aiobotocore-lambda-2.5.1/types_aiobotocore_lambda/
+-rw-r--r--   0 runner    (1001) docker     (123)     4232 2023-06-28 01:33:51.000000 types-aiobotocore-lambda-2.5.1/types_aiobotocore_lambda/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4231 2023-06-28 01:33:51.000000 types-aiobotocore-lambda-2.5.1/types_aiobotocore_lambda/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      916 2023-06-28 01:33:51.000000 types-aiobotocore-lambda-2.5.1/types_aiobotocore_lambda/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    62818 2023-06-28 01:33:52.000000 types-aiobotocore-lambda-2.5.1/types_aiobotocore_lambda/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    62726 2023-06-28 01:33:52.000000 types-aiobotocore-lambda-2.5.1/types_aiobotocore_lambda/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    14280 2023-06-28 01:33:52.000000 types-aiobotocore-lambda-2.5.1/types_aiobotocore_lambda/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14278 2023-06-28 01:33:52.000000 types-aiobotocore-lambda-2.5.1/types_aiobotocore_lambda/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    14332 2023-06-28 01:33:52.000000 types-aiobotocore-lambda-2.5.1/types_aiobotocore_lambda/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14318 2023-06-28 01:33:52.000000 types-aiobotocore-lambda-2.5.1/types_aiobotocore_lambda/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:33:51.000000 types-aiobotocore-lambda-2.5.1/types_aiobotocore_lambda/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    78692 2023-06-28 01:33:55.000000 types-aiobotocore-lambda-2.5.1/types_aiobotocore_lambda/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    78585 2023-06-28 01:33:54.000000 types-aiobotocore-lambda-2.5.1/types_aiobotocore_lambda/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:33:51.000000 types-aiobotocore-lambda-2.5.1/types_aiobotocore_lambda/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6547 2023-06-28 01:33:52.000000 types-aiobotocore-lambda-2.5.1/types_aiobotocore_lambda/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6541 2023-06-28 01:33:52.000000 types-aiobotocore-lambda-2.5.1/types_aiobotocore_lambda/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:44.902166 types-aiobotocore-lambda-2.5.1/types_aiobotocore_lambda.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    24779 2023-06-28 01:43:44.000000 types-aiobotocore-lambda-2.5.1/types_aiobotocore_lambda.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      865 2023-06-28 01:43:44.000000 types-aiobotocore-lambda-2.5.1/types_aiobotocore_lambda.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:44.000000 types-aiobotocore-lambda-2.5.1/types_aiobotocore_lambda.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:44.000000 types-aiobotocore-lambda-2.5.1/types_aiobotocore_lambda.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:44.000000 types-aiobotocore-lambda-2.5.1/types_aiobotocore_lambda.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       25 2023-06-28 01:43:44.000000 types-aiobotocore-lambda-2.5.1/types_aiobotocore_lambda.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-lambda-2.5.0.post1/LICENSE` & `types-aiobotocore-lambda-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-lambda-2.5.0.post1/PKG-INFO` & `types-aiobotocore-lambda-2.5.1/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-lambda
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Lambda 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Lambda 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-lambda"></a>
 
 # types-aiobotocore-lambda
 
 [![PyPI - types-aiobotocore-lambda](https://img.shields.io/pypi/v/types-aiobotocore-lambda.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lambda)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-lambda.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lambda)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-lambda?color=blue)](https://pypistats.org/packages/types-aiobotocore-lambda)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Lambda 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda)
+[aiobotocore.Lambda 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda)
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
 [types-aiobotocore-lambda docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/).
 
 See how it helps to find and fix potential bugs:
 
@@ -370,23 +370,25 @@
 
 ```python
 from types_aiobotocore_lambda.literals import (
     ArchitectureType,
     CodeSigningPolicyType,
     EndPointTypeType,
     EventSourcePositionType,
+    FullDocumentType,
     FunctionActiveV2WaiterName,
     FunctionActiveWaiterName,
     FunctionExistsWaiterName,
     FunctionResponseTypeType,
     FunctionUpdatedV2WaiterName,
     FunctionUpdatedWaiterName,
     FunctionUrlAuthTypeType,
     FunctionVersionType,
     InvocationTypeType,
+    InvokeModeType,
     LastUpdateStatusReasonCodeType,
     LastUpdateStatusType,
     ListAliasesPaginatorName,
     ListCodeSigningConfigsPaginatorName,
     ListEventSourceMappingsPaginatorName,
     ListFunctionEventInvokeConfigsPaginatorName,
     ListFunctionUrlConfigsPaginatorName,
@@ -396,14 +398,15 @@
     ListLayersPaginatorName,
     ListProvisionedConcurrencyConfigsPaginatorName,
     ListVersionsByFunctionPaginatorName,
     LogTypeType,
     PackageTypeType,
     ProvisionedConcurrencyStatusEnumType,
     PublishedVersionActiveWaiterName,
+    ResponseStreamingInvocationTypeType,
     RuntimeType,
     SnapStartApplyOnType,
     SnapStartOptimizationStatusType,
     SourceAccessTypeType,
     StateReasonCodeType,
     StateType,
     TracingModeType,
@@ -429,22 +432,25 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_lambda.type_defs import (
     AccountLimitTypeDef,
     AccountUsageTypeDef,
     AddLayerVersionPermissionRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AddLayerVersionPermissionResponseTypeDef,
     AddPermissionRequestRequestTypeDef,
+    AddPermissionResponseTypeDef,
     AliasRoutingConfigurationTypeDef,
     AllowedPublishersTypeDef,
     AmazonManagedKafkaEventSourceConfigTypeDef,
     CodeSigningPoliciesTypeDef,
+    ConcurrencyResponseMetadataTypeDef,
     ConcurrencyTypeDef,
     CorsTypeDef,
+    DocumentDBEventSourceConfigTypeDef,
     ScalingConfigTypeDef,
     SelfManagedEventSourceTypeDef,
     SelfManagedKafkaEventSourceConfigTypeDef,
     SourceAccessConfigurationTypeDef,
     DeadLetterConfigTypeDef,
     EnvironmentTypeDef,
     EphemeralStorageTypeDef,
@@ -462,86 +468,98 @@
     DeleteFunctionEventInvokeConfigRequestRequestTypeDef,
     DeleteFunctionRequestRequestTypeDef,
     DeleteFunctionUrlConfigRequestRequestTypeDef,
     DeleteLayerVersionRequestRequestTypeDef,
     DeleteProvisionedConcurrencyConfigRequestRequestTypeDef,
     OnFailureTypeDef,
     OnSuccessTypeDef,
+    EmptyResponseMetadataTypeDef,
     EnvironmentErrorTypeDef,
     FilterTypeDef,
     FunctionCodeLocationTypeDef,
     LayerTypeDef,
     SnapStartResponseTypeDef,
     TracingConfigResponseTypeDef,
     VpcConfigResponseTypeDef,
     GetAliasRequestRequestTypeDef,
     GetCodeSigningConfigRequestRequestTypeDef,
     GetEventSourceMappingRequestRequestTypeDef,
     GetFunctionCodeSigningConfigRequestRequestTypeDef,
+    GetFunctionCodeSigningConfigResponseTypeDef,
     GetFunctionConcurrencyRequestRequestTypeDef,
+    GetFunctionConcurrencyResponseTypeDef,
     WaiterConfigTypeDef,
     GetFunctionConfigurationRequestRequestTypeDef,
     GetFunctionEventInvokeConfigRequestRequestTypeDef,
     GetFunctionRequestRequestTypeDef,
     GetFunctionUrlConfigRequestRequestTypeDef,
     GetLayerVersionByArnRequestRequestTypeDef,
     GetLayerVersionPolicyRequestRequestTypeDef,
+    GetLayerVersionPolicyResponseTypeDef,
     GetLayerVersionRequestRequestTypeDef,
     LayerVersionContentOutputTypeDef,
     GetPolicyRequestRequestTypeDef,
+    GetPolicyResponseTypeDef,
     GetProvisionedConcurrencyConfigRequestRequestTypeDef,
+    GetProvisionedConcurrencyConfigResponseTypeDef,
     GetRuntimeManagementConfigRequestRequestTypeDef,
+    GetRuntimeManagementConfigResponseTypeDef,
     ImageConfigErrorTypeDef,
     InvocationRequestRequestTypeDef,
+    InvocationResponseTypeDef,
     InvokeAsyncRequestRequestTypeDef,
+    InvokeAsyncResponseTypeDef,
+    InvokeResponseStreamUpdateTypeDef,
+    InvokeWithResponseStreamCompleteEventTypeDef,
+    InvokeWithResponseStreamRequestRequestTypeDef,
     LayerVersionContentInputTypeDef,
     LayerVersionsListItemTypeDef,
-    PaginatorConfigTypeDef,
+    ListAliasesRequestListAliasesPaginateTypeDef,
     ListAliasesRequestRequestTypeDef,
+    ListCodeSigningConfigsRequestListCodeSigningConfigsPaginateTypeDef,
     ListCodeSigningConfigsRequestRequestTypeDef,
+    ListEventSourceMappingsRequestListEventSourceMappingsPaginateTypeDef,
     ListEventSourceMappingsRequestRequestTypeDef,
+    ListFunctionEventInvokeConfigsRequestListFunctionEventInvokeConfigsPaginateTypeDef,
     ListFunctionEventInvokeConfigsRequestRequestTypeDef,
+    ListFunctionUrlConfigsRequestListFunctionUrlConfigsPaginateTypeDef,
     ListFunctionUrlConfigsRequestRequestTypeDef,
+    ListFunctionsByCodeSigningConfigRequestListFunctionsByCodeSigningConfigPaginateTypeDef,
     ListFunctionsByCodeSigningConfigRequestRequestTypeDef,
+    ListFunctionsByCodeSigningConfigResponseTypeDef,
+    ListFunctionsRequestListFunctionsPaginateTypeDef,
     ListFunctionsRequestRequestTypeDef,
+    ListLayerVersionsRequestListLayerVersionsPaginateTypeDef,
     ListLayerVersionsRequestRequestTypeDef,
+    ListLayersRequestListLayersPaginateTypeDef,
     ListLayersRequestRequestTypeDef,
+    ListProvisionedConcurrencyConfigsRequestListProvisionedConcurrencyConfigsPaginateTypeDef,
     ListProvisionedConcurrencyConfigsRequestRequestTypeDef,
     ProvisionedConcurrencyConfigListItemTypeDef,
     ListTagsRequestRequestTypeDef,
+    ListTagsResponseTypeDef,
+    ListVersionsByFunctionRequestListVersionsByFunctionPaginateTypeDef,
     ListVersionsByFunctionRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     PublishVersionRequestRequestTypeDef,
     PutFunctionCodeSigningConfigRequestRequestTypeDef,
+    PutFunctionCodeSigningConfigResponseTypeDef,
     PutFunctionConcurrencyRequestRequestTypeDef,
     PutProvisionedConcurrencyConfigRequestRequestTypeDef,
+    PutProvisionedConcurrencyConfigResponseTypeDef,
     PutRuntimeManagementConfigRequestRequestTypeDef,
+    PutRuntimeManagementConfigResponseTypeDef,
     RemoveLayerVersionPermissionRequestRequestTypeDef,
     RemovePermissionRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     RuntimeVersionErrorTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateFunctionCodeRequestRequestTypeDef,
-    AddLayerVersionPermissionResponseTypeDef,
-    AddPermissionResponseTypeDef,
-    ConcurrencyResponseMetadataTypeDef,
-    EmptyResponseMetadataTypeDef,
     GetAccountSettingsResponseTypeDef,
-    GetFunctionCodeSigningConfigResponseTypeDef,
-    GetFunctionConcurrencyResponseTypeDef,
-    GetLayerVersionPolicyResponseTypeDef,
-    GetPolicyResponseTypeDef,
-    GetProvisionedConcurrencyConfigResponseTypeDef,
-    GetRuntimeManagementConfigResponseTypeDef,
-    InvocationResponseTypeDef,
-    InvokeAsyncResponseTypeDef,
-    ListFunctionsByCodeSigningConfigResponseTypeDef,
-    ListTagsResponseTypeDef,
-    PutFunctionCodeSigningConfigResponseTypeDef,
-    PutProvisionedConcurrencyConfigResponseTypeDef,
-    PutRuntimeManagementConfigResponseTypeDef,
     AliasConfigurationResponseMetadataTypeDef,
     AliasConfigurationTypeDef,
     CreateAliasRequestRequestTypeDef,
     UpdateAliasRequestRequestTypeDef,
     CodeSigningConfigTypeDef,
     CreateCodeSigningConfigRequestRequestTypeDef,
     UpdateCodeSigningConfigRequestRequestTypeDef,
@@ -561,28 +579,18 @@
     GetFunctionConfigurationRequestPublishedVersionActiveWaitTypeDef,
     GetFunctionRequestFunctionActiveV2WaitTypeDef,
     GetFunctionRequestFunctionExistsWaitTypeDef,
     GetFunctionRequestFunctionUpdatedV2WaitTypeDef,
     GetLayerVersionResponseTypeDef,
     PublishLayerVersionResponseTypeDef,
     ImageConfigResponseTypeDef,
+    InvokeWithResponseStreamResponseEventTypeDef,
     PublishLayerVersionRequestRequestTypeDef,
     LayersListItemTypeDef,
     ListLayerVersionsResponseTypeDef,
-    ListAliasesRequestListAliasesPaginateTypeDef,
-    ListCodeSigningConfigsRequestListCodeSigningConfigsPaginateTypeDef,
-    ListEventSourceMappingsRequestListEventSourceMappingsPaginateTypeDef,
-    ListFunctionEventInvokeConfigsRequestListFunctionEventInvokeConfigsPaginateTypeDef,
-    ListFunctionUrlConfigsRequestListFunctionUrlConfigsPaginateTypeDef,
-    ListFunctionsByCodeSigningConfigRequestListFunctionsByCodeSigningConfigPaginateTypeDef,
-    ListFunctionsRequestListFunctionsPaginateTypeDef,
-    ListLayerVersionsRequestListLayerVersionsPaginateTypeDef,
-    ListLayersRequestListLayersPaginateTypeDef,
-    ListProvisionedConcurrencyConfigsRequestListProvisionedConcurrencyConfigsPaginateTypeDef,
-    ListVersionsByFunctionRequestListVersionsByFunctionPaginateTypeDef,
     ListProvisionedConcurrencyConfigsResponseTypeDef,
     RuntimeVersionConfigTypeDef,
     ListAliasesResponseTypeDef,
     CreateCodeSigningConfigResponseTypeDef,
     GetCodeSigningConfigResponseTypeDef,
     ListCodeSigningConfigsResponseTypeDef,
     UpdateCodeSigningConfigResponseTypeDef,
@@ -591,14 +599,15 @@
     FunctionEventInvokeConfigTypeDef,
     PutFunctionEventInvokeConfigRequestRequestTypeDef,
     UpdateFunctionEventInvokeConfigRequestRequestTypeDef,
     CreateEventSourceMappingRequestRequestTypeDef,
     EventSourceMappingConfigurationResponseMetadataTypeDef,
     EventSourceMappingConfigurationTypeDef,
     UpdateEventSourceMappingRequestRequestTypeDef,
+    InvokeWithResponseStreamResponseTypeDef,
     ListLayersResponseTypeDef,
     FunctionConfigurationResponseMetadataTypeDef,
     FunctionConfigurationTypeDef,
     ListFunctionEventInvokeConfigsResponseTypeDef,
     ListEventSourceMappingsResponseTypeDef,
     GetFunctionResponseTypeDef,
     ListFunctionsResponseTypeDef,
@@ -613,43 +622,43 @@
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

### Comparing `types-aiobotocore-lambda-2.5.0.post1/README.md` & `types-aiobotocore-lambda-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-lambda"></a>
 
 # types-aiobotocore-lambda
 
 [![PyPI - types-aiobotocore-lambda](https://img.shields.io/pypi/v/types-aiobotocore-lambda.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lambda)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-lambda.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lambda)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-lambda?color=blue)](https://pypistats.org/packages/types-aiobotocore-lambda)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Lambda 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda)
+[aiobotocore.Lambda 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda)
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
 [types-aiobotocore-lambda docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/).
 
 See how it helps to find and fix potential bugs:
 
@@ -337,23 +337,25 @@
 
 ```python
 from types_aiobotocore_lambda.literals import (
     ArchitectureType,
     CodeSigningPolicyType,
     EndPointTypeType,
     EventSourcePositionType,
+    FullDocumentType,
     FunctionActiveV2WaiterName,
     FunctionActiveWaiterName,
     FunctionExistsWaiterName,
     FunctionResponseTypeType,
     FunctionUpdatedV2WaiterName,
     FunctionUpdatedWaiterName,
     FunctionUrlAuthTypeType,
     FunctionVersionType,
     InvocationTypeType,
+    InvokeModeType,
     LastUpdateStatusReasonCodeType,
     LastUpdateStatusType,
     ListAliasesPaginatorName,
     ListCodeSigningConfigsPaginatorName,
     ListEventSourceMappingsPaginatorName,
     ListFunctionEventInvokeConfigsPaginatorName,
     ListFunctionUrlConfigsPaginatorName,
@@ -363,14 +365,15 @@
     ListLayersPaginatorName,
     ListProvisionedConcurrencyConfigsPaginatorName,
     ListVersionsByFunctionPaginatorName,
     LogTypeType,
     PackageTypeType,
     ProvisionedConcurrencyStatusEnumType,
     PublishedVersionActiveWaiterName,
+    ResponseStreamingInvocationTypeType,
     RuntimeType,
     SnapStartApplyOnType,
     SnapStartOptimizationStatusType,
     SourceAccessTypeType,
     StateReasonCodeType,
     StateType,
     TracingModeType,
@@ -396,22 +399,25 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_lambda.type_defs import (
     AccountLimitTypeDef,
     AccountUsageTypeDef,
     AddLayerVersionPermissionRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AddLayerVersionPermissionResponseTypeDef,
     AddPermissionRequestRequestTypeDef,
+    AddPermissionResponseTypeDef,
     AliasRoutingConfigurationTypeDef,
     AllowedPublishersTypeDef,
     AmazonManagedKafkaEventSourceConfigTypeDef,
     CodeSigningPoliciesTypeDef,
+    ConcurrencyResponseMetadataTypeDef,
     ConcurrencyTypeDef,
     CorsTypeDef,
+    DocumentDBEventSourceConfigTypeDef,
     ScalingConfigTypeDef,
     SelfManagedEventSourceTypeDef,
     SelfManagedKafkaEventSourceConfigTypeDef,
     SourceAccessConfigurationTypeDef,
     DeadLetterConfigTypeDef,
     EnvironmentTypeDef,
     EphemeralStorageTypeDef,
@@ -429,86 +435,98 @@
     DeleteFunctionEventInvokeConfigRequestRequestTypeDef,
     DeleteFunctionRequestRequestTypeDef,
     DeleteFunctionUrlConfigRequestRequestTypeDef,
     DeleteLayerVersionRequestRequestTypeDef,
     DeleteProvisionedConcurrencyConfigRequestRequestTypeDef,
     OnFailureTypeDef,
     OnSuccessTypeDef,
+    EmptyResponseMetadataTypeDef,
     EnvironmentErrorTypeDef,
     FilterTypeDef,
     FunctionCodeLocationTypeDef,
     LayerTypeDef,
     SnapStartResponseTypeDef,
     TracingConfigResponseTypeDef,
     VpcConfigResponseTypeDef,
     GetAliasRequestRequestTypeDef,
     GetCodeSigningConfigRequestRequestTypeDef,
     GetEventSourceMappingRequestRequestTypeDef,
     GetFunctionCodeSigningConfigRequestRequestTypeDef,
+    GetFunctionCodeSigningConfigResponseTypeDef,
     GetFunctionConcurrencyRequestRequestTypeDef,
+    GetFunctionConcurrencyResponseTypeDef,
     WaiterConfigTypeDef,
     GetFunctionConfigurationRequestRequestTypeDef,
     GetFunctionEventInvokeConfigRequestRequestTypeDef,
     GetFunctionRequestRequestTypeDef,
     GetFunctionUrlConfigRequestRequestTypeDef,
     GetLayerVersionByArnRequestRequestTypeDef,
     GetLayerVersionPolicyRequestRequestTypeDef,
+    GetLayerVersionPolicyResponseTypeDef,
     GetLayerVersionRequestRequestTypeDef,
     LayerVersionContentOutputTypeDef,
     GetPolicyRequestRequestTypeDef,
+    GetPolicyResponseTypeDef,
     GetProvisionedConcurrencyConfigRequestRequestTypeDef,
+    GetProvisionedConcurrencyConfigResponseTypeDef,
     GetRuntimeManagementConfigRequestRequestTypeDef,
+    GetRuntimeManagementConfigResponseTypeDef,
     ImageConfigErrorTypeDef,
     InvocationRequestRequestTypeDef,
+    InvocationResponseTypeDef,
     InvokeAsyncRequestRequestTypeDef,
+    InvokeAsyncResponseTypeDef,
+    InvokeResponseStreamUpdateTypeDef,
+    InvokeWithResponseStreamCompleteEventTypeDef,
+    InvokeWithResponseStreamRequestRequestTypeDef,
     LayerVersionContentInputTypeDef,
     LayerVersionsListItemTypeDef,
-    PaginatorConfigTypeDef,
+    ListAliasesRequestListAliasesPaginateTypeDef,
     ListAliasesRequestRequestTypeDef,
+    ListCodeSigningConfigsRequestListCodeSigningConfigsPaginateTypeDef,
     ListCodeSigningConfigsRequestRequestTypeDef,
+    ListEventSourceMappingsRequestListEventSourceMappingsPaginateTypeDef,
     ListEventSourceMappingsRequestRequestTypeDef,
+    ListFunctionEventInvokeConfigsRequestListFunctionEventInvokeConfigsPaginateTypeDef,
     ListFunctionEventInvokeConfigsRequestRequestTypeDef,
+    ListFunctionUrlConfigsRequestListFunctionUrlConfigsPaginateTypeDef,
     ListFunctionUrlConfigsRequestRequestTypeDef,
+    ListFunctionsByCodeSigningConfigRequestListFunctionsByCodeSigningConfigPaginateTypeDef,
     ListFunctionsByCodeSigningConfigRequestRequestTypeDef,
+    ListFunctionsByCodeSigningConfigResponseTypeDef,
+    ListFunctionsRequestListFunctionsPaginateTypeDef,
     ListFunctionsRequestRequestTypeDef,
+    ListLayerVersionsRequestListLayerVersionsPaginateTypeDef,
     ListLayerVersionsRequestRequestTypeDef,
+    ListLayersRequestListLayersPaginateTypeDef,
     ListLayersRequestRequestTypeDef,
+    ListProvisionedConcurrencyConfigsRequestListProvisionedConcurrencyConfigsPaginateTypeDef,
     ListProvisionedConcurrencyConfigsRequestRequestTypeDef,
     ProvisionedConcurrencyConfigListItemTypeDef,
     ListTagsRequestRequestTypeDef,
+    ListTagsResponseTypeDef,
+    ListVersionsByFunctionRequestListVersionsByFunctionPaginateTypeDef,
     ListVersionsByFunctionRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     PublishVersionRequestRequestTypeDef,
     PutFunctionCodeSigningConfigRequestRequestTypeDef,
+    PutFunctionCodeSigningConfigResponseTypeDef,
     PutFunctionConcurrencyRequestRequestTypeDef,
     PutProvisionedConcurrencyConfigRequestRequestTypeDef,
+    PutProvisionedConcurrencyConfigResponseTypeDef,
     PutRuntimeManagementConfigRequestRequestTypeDef,
+    PutRuntimeManagementConfigResponseTypeDef,
     RemoveLayerVersionPermissionRequestRequestTypeDef,
     RemovePermissionRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     RuntimeVersionErrorTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateFunctionCodeRequestRequestTypeDef,
-    AddLayerVersionPermissionResponseTypeDef,
-    AddPermissionResponseTypeDef,
-    ConcurrencyResponseMetadataTypeDef,
-    EmptyResponseMetadataTypeDef,
     GetAccountSettingsResponseTypeDef,
-    GetFunctionCodeSigningConfigResponseTypeDef,
-    GetFunctionConcurrencyResponseTypeDef,
-    GetLayerVersionPolicyResponseTypeDef,
-    GetPolicyResponseTypeDef,
-    GetProvisionedConcurrencyConfigResponseTypeDef,
-    GetRuntimeManagementConfigResponseTypeDef,
-    InvocationResponseTypeDef,
-    InvokeAsyncResponseTypeDef,
-    ListFunctionsByCodeSigningConfigResponseTypeDef,
-    ListTagsResponseTypeDef,
-    PutFunctionCodeSigningConfigResponseTypeDef,
-    PutProvisionedConcurrencyConfigResponseTypeDef,
-    PutRuntimeManagementConfigResponseTypeDef,
     AliasConfigurationResponseMetadataTypeDef,
     AliasConfigurationTypeDef,
     CreateAliasRequestRequestTypeDef,
     UpdateAliasRequestRequestTypeDef,
     CodeSigningConfigTypeDef,
     CreateCodeSigningConfigRequestRequestTypeDef,
     UpdateCodeSigningConfigRequestRequestTypeDef,
@@ -528,28 +546,18 @@
     GetFunctionConfigurationRequestPublishedVersionActiveWaitTypeDef,
     GetFunctionRequestFunctionActiveV2WaitTypeDef,
     GetFunctionRequestFunctionExistsWaitTypeDef,
     GetFunctionRequestFunctionUpdatedV2WaitTypeDef,
     GetLayerVersionResponseTypeDef,
     PublishLayerVersionResponseTypeDef,
     ImageConfigResponseTypeDef,
+    InvokeWithResponseStreamResponseEventTypeDef,
     PublishLayerVersionRequestRequestTypeDef,
     LayersListItemTypeDef,
     ListLayerVersionsResponseTypeDef,
-    ListAliasesRequestListAliasesPaginateTypeDef,
-    ListCodeSigningConfigsRequestListCodeSigningConfigsPaginateTypeDef,
-    ListEventSourceMappingsRequestListEventSourceMappingsPaginateTypeDef,
-    ListFunctionEventInvokeConfigsRequestListFunctionEventInvokeConfigsPaginateTypeDef,
-    ListFunctionUrlConfigsRequestListFunctionUrlConfigsPaginateTypeDef,
-    ListFunctionsByCodeSigningConfigRequestListFunctionsByCodeSigningConfigPaginateTypeDef,
-    ListFunctionsRequestListFunctionsPaginateTypeDef,
-    ListLayerVersionsRequestListLayerVersionsPaginateTypeDef,
-    ListLayersRequestListLayersPaginateTypeDef,
-    ListProvisionedConcurrencyConfigsRequestListProvisionedConcurrencyConfigsPaginateTypeDef,
-    ListVersionsByFunctionRequestListVersionsByFunctionPaginateTypeDef,
     ListProvisionedConcurrencyConfigsResponseTypeDef,
     RuntimeVersionConfigTypeDef,
     ListAliasesResponseTypeDef,
     CreateCodeSigningConfigResponseTypeDef,
     GetCodeSigningConfigResponseTypeDef,
     ListCodeSigningConfigsResponseTypeDef,
     UpdateCodeSigningConfigResponseTypeDef,
@@ -558,14 +566,15 @@
     FunctionEventInvokeConfigTypeDef,
     PutFunctionEventInvokeConfigRequestRequestTypeDef,
     UpdateFunctionEventInvokeConfigRequestRequestTypeDef,
     CreateEventSourceMappingRequestRequestTypeDef,
     EventSourceMappingConfigurationResponseMetadataTypeDef,
     EventSourceMappingConfigurationTypeDef,
     UpdateEventSourceMappingRequestRequestTypeDef,
+    InvokeWithResponseStreamResponseTypeDef,
     ListLayersResponseTypeDef,
     FunctionConfigurationResponseMetadataTypeDef,
     FunctionConfigurationTypeDef,
     ListFunctionEventInvokeConfigsResponseTypeDef,
     ListEventSourceMappingsResponseTypeDef,
     GetFunctionResponseTypeDef,
     ListFunctionsResponseTypeDef,
@@ -580,43 +589,43 @@
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

### Comparing `types-aiobotocore-lambda-2.5.0.post1/setup.py` & `types-aiobotocore-lambda-2.5.1/setup.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-lambda.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-lambda",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_lambda"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Lambda 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.Lambda 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/"
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

### Comparing `types-aiobotocore-lambda-2.5.0.post1/types_aiobotocore_lambda/__init__.py` & `types-aiobotocore-lambda-2.5.1/types_aiobotocore_lambda/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-lambda-2.5.0.post1/types_aiobotocore_lambda/__init__.pyi` & `types-aiobotocore-lambda-2.5.1/types_aiobotocore_lambda/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-lambda-2.5.0.post1/types_aiobotocore_lambda/__main__.py` & `types-aiobotocore-lambda-2.5.1/types_aiobotocore_lambda/__main__.py`

 * *Files 24% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Lambda 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Lambda 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda//\nBoto3 docs: "
         "     https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda\nOther"
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

### Comparing `types-aiobotocore-lambda-2.5.0.post1/types_aiobotocore_lambda/client.py` & `types-aiobotocore-lambda-2.5.1/types_aiobotocore_lambda/client.py`

 * *Files 1% similar despite different names*

```diff
@@ -23,16 +23,18 @@
 from botocore.client import ClientMeta
 
 from .literals import (
     ArchitectureType,
     EventSourcePositionType,
     FunctionUrlAuthTypeType,
     InvocationTypeType,
+    InvokeModeType,
     LogTypeType,
     PackageTypeType,
+    ResponseStreamingInvocationTypeType,
     RuntimeType,
     UpdateRuntimeOnType,
 )
 from .paginator import (
     ListAliasesPaginator,
     ListCodeSigningConfigsPaginator,
     ListEventSourceMappingsPaginator,
@@ -55,14 +57,15 @@
     CodeSigningPoliciesTypeDef,
     ConcurrencyResponseMetadataTypeDef,
     CorsTypeDef,
     CreateCodeSigningConfigResponseTypeDef,
     CreateFunctionUrlConfigResponseTypeDef,
     DeadLetterConfigTypeDef,
     DestinationConfigTypeDef,
+    DocumentDBEventSourceConfigTypeDef,
     EmptyResponseMetadataTypeDef,
     EnvironmentTypeDef,
     EphemeralStorageTypeDef,
     EventSourceMappingConfigurationResponseMetadataTypeDef,
     FileSystemConfigTypeDef,
     FilterCriteriaTypeDef,
     FunctionCodeTypeDef,
@@ -78,14 +81,15 @@
     GetLayerVersionResponseTypeDef,
     GetPolicyResponseTypeDef,
     GetProvisionedConcurrencyConfigResponseTypeDef,
     GetRuntimeManagementConfigResponseTypeDef,
     ImageConfigTypeDef,
     InvocationResponseTypeDef,
     InvokeAsyncResponseTypeDef,
+    InvokeWithResponseStreamResponseTypeDef,
     LayerVersionContentInputTypeDef,
     ListAliasesResponseTypeDef,
     ListCodeSigningConfigsResponseTypeDef,
     ListEventSourceMappingsResponseTypeDef,
     ListFunctionEventInvokeConfigsResponseTypeDef,
     ListFunctionsByCodeSigningConfigResponseTypeDef,
     ListFunctionsResponseTypeDef,
@@ -158,14 +162,15 @@
     KMSAccessDeniedException: Type[BotocoreClientError]
     KMSDisabledException: Type[BotocoreClientError]
     KMSInvalidStateException: Type[BotocoreClientError]
     KMSNotFoundException: Type[BotocoreClientError]
     PolicyLengthExceededException: Type[BotocoreClientError]
     PreconditionFailedException: Type[BotocoreClientError]
     ProvisionedConcurrencyConfigNotFoundException: Type[BotocoreClientError]
+    RecursiveInvocationException: Type[BotocoreClientError]
     RequestTooLargeException: Type[BotocoreClientError]
     ResourceConflictException: Type[BotocoreClientError]
     ResourceInUseException: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
     ResourceNotReadyException: Type[BotocoreClientError]
     ServiceException: Type[BotocoreClientError]
     SnapStartException: Type[BotocoreClientError]
@@ -302,15 +307,16 @@
         Topics: Sequence[str] = ...,
         Queues: Sequence[str] = ...,
         SourceAccessConfigurations: Sequence[SourceAccessConfigurationTypeDef] = ...,
         SelfManagedEventSource: SelfManagedEventSourceTypeDef = ...,
         FunctionResponseTypes: Sequence[Literal["ReportBatchItemFailures"]] = ...,
         AmazonManagedKafkaEventSourceConfig: AmazonManagedKafkaEventSourceConfigTypeDef = ...,
         SelfManagedKafkaEventSourceConfig: SelfManagedKafkaEventSourceConfigTypeDef = ...,
-        ScalingConfig: ScalingConfigTypeDef = ...
+        ScalingConfig: ScalingConfigTypeDef = ...,
+        DocumentDBEventSourceConfig: DocumentDBEventSourceConfigTypeDef = ...
     ) -> EventSourceMappingConfigurationResponseMetadataTypeDef:
         """
         Creates a mapping between an event source and an Lambda function.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Client.create_event_source_mapping)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/client/#create_event_source_mapping)
         """
@@ -351,15 +357,16 @@
 
     async def create_function_url_config(
         self,
         *,
         FunctionName: str,
         AuthType: FunctionUrlAuthTypeType,
         Qualifier: str = ...,
-        Cors: CorsTypeDef = ...
+        Cors: CorsTypeDef = ...,
+        InvokeMode: InvokeModeType = ...
     ) -> CreateFunctionUrlConfigResponseTypeDef:
         """
         Creates a Lambda function URL with the specified configuration parameters.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Client.create_function_url_config)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/client/#create_function_url_config)
         """
@@ -673,14 +680,31 @@
         """
         .
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Client.invoke_async)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/client/#invoke_async)
         """
 
+    async def invoke_with_response_stream(
+        self,
+        *,
+        FunctionName: str,
+        InvocationType: ResponseStreamingInvocationTypeType = ...,
+        LogType: LogTypeType = ...,
+        ClientContext: str = ...,
+        Qualifier: str = ...,
+        Payload: Union[str, bytes, IO[Any], StreamingBody] = ...
+    ) -> InvokeWithResponseStreamResponseTypeDef:
+        """
+        Configure your Lambda functions to stream response payloads back to clients.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Client.invoke_with_response_stream)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/client/#invoke_with_response_stream)
+        """
+
     async def list_aliases(
         self,
         *,
         FunctionName: str,
         FunctionVersion: str = ...,
         Marker: str = ...,
         MaxItems: int = ...
@@ -1021,15 +1045,16 @@
         MaximumRecordAgeInSeconds: int = ...,
         BisectBatchOnFunctionError: bool = ...,
         MaximumRetryAttempts: int = ...,
         ParallelizationFactor: int = ...,
         SourceAccessConfigurations: Sequence[SourceAccessConfigurationTypeDef] = ...,
         TumblingWindowInSeconds: int = ...,
         FunctionResponseTypes: Sequence[Literal["ReportBatchItemFailures"]] = ...,
-        ScalingConfig: ScalingConfigTypeDef = ...
+        ScalingConfig: ScalingConfigTypeDef = ...,
+        DocumentDBEventSourceConfig: DocumentDBEventSourceConfigTypeDef = ...
     ) -> EventSourceMappingConfigurationResponseMetadataTypeDef:
         """
         Updates an event source mapping.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Client.update_event_source_mapping)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/client/#update_event_source_mapping)
         """
@@ -1103,15 +1128,16 @@
 
     async def update_function_url_config(
         self,
         *,
         FunctionName: str,
         Qualifier: str = ...,
         AuthType: FunctionUrlAuthTypeType = ...,
-        Cors: CorsTypeDef = ...
+        Cors: CorsTypeDef = ...,
+        InvokeMode: InvokeModeType = ...
     ) -> UpdateFunctionUrlConfigResponseTypeDef:
         """
         Updates the configuration for a Lambda function URL.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Client.update_function_url_config)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/client/#update_function_url_config)
         """
```

### Comparing `types-aiobotocore-lambda-2.5.0.post1/types_aiobotocore_lambda/client.pyi` & `types-aiobotocore-lambda-2.5.1/types_aiobotocore_lambda/client.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -23,16 +23,18 @@
 from botocore.client import ClientMeta
 
 from .literals import (
     ArchitectureType,
     EventSourcePositionType,
     FunctionUrlAuthTypeType,
     InvocationTypeType,
+    InvokeModeType,
     LogTypeType,
     PackageTypeType,
+    ResponseStreamingInvocationTypeType,
     RuntimeType,
     UpdateRuntimeOnType,
 )
 from .paginator import (
     ListAliasesPaginator,
     ListCodeSigningConfigsPaginator,
     ListEventSourceMappingsPaginator,
@@ -55,14 +57,15 @@
     CodeSigningPoliciesTypeDef,
     ConcurrencyResponseMetadataTypeDef,
     CorsTypeDef,
     CreateCodeSigningConfigResponseTypeDef,
     CreateFunctionUrlConfigResponseTypeDef,
     DeadLetterConfigTypeDef,
     DestinationConfigTypeDef,
+    DocumentDBEventSourceConfigTypeDef,
     EmptyResponseMetadataTypeDef,
     EnvironmentTypeDef,
     EphemeralStorageTypeDef,
     EventSourceMappingConfigurationResponseMetadataTypeDef,
     FileSystemConfigTypeDef,
     FilterCriteriaTypeDef,
     FunctionCodeTypeDef,
@@ -78,14 +81,15 @@
     GetLayerVersionResponseTypeDef,
     GetPolicyResponseTypeDef,
     GetProvisionedConcurrencyConfigResponseTypeDef,
     GetRuntimeManagementConfigResponseTypeDef,
     ImageConfigTypeDef,
     InvocationResponseTypeDef,
     InvokeAsyncResponseTypeDef,
+    InvokeWithResponseStreamResponseTypeDef,
     LayerVersionContentInputTypeDef,
     ListAliasesResponseTypeDef,
     ListCodeSigningConfigsResponseTypeDef,
     ListEventSourceMappingsResponseTypeDef,
     ListFunctionEventInvokeConfigsResponseTypeDef,
     ListFunctionsByCodeSigningConfigResponseTypeDef,
     ListFunctionsResponseTypeDef,
@@ -155,14 +159,15 @@
     KMSAccessDeniedException: Type[BotocoreClientError]
     KMSDisabledException: Type[BotocoreClientError]
     KMSInvalidStateException: Type[BotocoreClientError]
     KMSNotFoundException: Type[BotocoreClientError]
     PolicyLengthExceededException: Type[BotocoreClientError]
     PreconditionFailedException: Type[BotocoreClientError]
     ProvisionedConcurrencyConfigNotFoundException: Type[BotocoreClientError]
+    RecursiveInvocationException: Type[BotocoreClientError]
     RequestTooLargeException: Type[BotocoreClientError]
     ResourceConflictException: Type[BotocoreClientError]
     ResourceInUseException: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
     ResourceNotReadyException: Type[BotocoreClientError]
     ServiceException: Type[BotocoreClientError]
     SnapStartException: Type[BotocoreClientError]
@@ -291,15 +296,16 @@
         Topics: Sequence[str] = ...,
         Queues: Sequence[str] = ...,
         SourceAccessConfigurations: Sequence[SourceAccessConfigurationTypeDef] = ...,
         SelfManagedEventSource: SelfManagedEventSourceTypeDef = ...,
         FunctionResponseTypes: Sequence[Literal["ReportBatchItemFailures"]] = ...,
         AmazonManagedKafkaEventSourceConfig: AmazonManagedKafkaEventSourceConfigTypeDef = ...,
         SelfManagedKafkaEventSourceConfig: SelfManagedKafkaEventSourceConfigTypeDef = ...,
-        ScalingConfig: ScalingConfigTypeDef = ...
+        ScalingConfig: ScalingConfigTypeDef = ...,
+        DocumentDBEventSourceConfig: DocumentDBEventSourceConfigTypeDef = ...
     ) -> EventSourceMappingConfigurationResponseMetadataTypeDef:
         """
         Creates a mapping between an event source and an Lambda function.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Client.create_event_source_mapping)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/client/#create_event_source_mapping)
         """
@@ -338,15 +344,16 @@
         """
     async def create_function_url_config(
         self,
         *,
         FunctionName: str,
         AuthType: FunctionUrlAuthTypeType,
         Qualifier: str = ...,
-        Cors: CorsTypeDef = ...
+        Cors: CorsTypeDef = ...,
+        InvokeMode: InvokeModeType = ...
     ) -> CreateFunctionUrlConfigResponseTypeDef:
         """
         Creates a Lambda function URL with the specified configuration parameters.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Client.create_function_url_config)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/client/#create_function_url_config)
         """
@@ -630,14 +637,30 @@
     ) -> InvokeAsyncResponseTypeDef:
         """
         .
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Client.invoke_async)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/client/#invoke_async)
         """
+    async def invoke_with_response_stream(
+        self,
+        *,
+        FunctionName: str,
+        InvocationType: ResponseStreamingInvocationTypeType = ...,
+        LogType: LogTypeType = ...,
+        ClientContext: str = ...,
+        Qualifier: str = ...,
+        Payload: Union[str, bytes, IO[Any], StreamingBody] = ...
+    ) -> InvokeWithResponseStreamResponseTypeDef:
+        """
+        Configure your Lambda functions to stream response payloads back to clients.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Client.invoke_with_response_stream)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/client/#invoke_with_response_stream)
+        """
     async def list_aliases(
         self,
         *,
         FunctionName: str,
         FunctionVersion: str = ...,
         Marker: str = ...,
         MaxItems: int = ...
@@ -953,15 +976,16 @@
         MaximumRecordAgeInSeconds: int = ...,
         BisectBatchOnFunctionError: bool = ...,
         MaximumRetryAttempts: int = ...,
         ParallelizationFactor: int = ...,
         SourceAccessConfigurations: Sequence[SourceAccessConfigurationTypeDef] = ...,
         TumblingWindowInSeconds: int = ...,
         FunctionResponseTypes: Sequence[Literal["ReportBatchItemFailures"]] = ...,
-        ScalingConfig: ScalingConfigTypeDef = ...
+        ScalingConfig: ScalingConfigTypeDef = ...,
+        DocumentDBEventSourceConfig: DocumentDBEventSourceConfigTypeDef = ...
     ) -> EventSourceMappingConfigurationResponseMetadataTypeDef:
         """
         Updates an event source mapping.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Client.update_event_source_mapping)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/client/#update_event_source_mapping)
         """
@@ -1031,15 +1055,16 @@
         """
     async def update_function_url_config(
         self,
         *,
         FunctionName: str,
         Qualifier: str = ...,
         AuthType: FunctionUrlAuthTypeType = ...,
-        Cors: CorsTypeDef = ...
+        Cors: CorsTypeDef = ...,
+        InvokeMode: InvokeModeType = ...
     ) -> UpdateFunctionUrlConfigResponseTypeDef:
         """
         Updates the configuration for a Lambda function URL.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Client.update_function_url_config)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/client/#update_function_url_config)
         """
```

### Comparing `types-aiobotocore-lambda-2.5.0.post1/types_aiobotocore_lambda/literals.py` & `types-aiobotocore-lambda-2.5.1/types_aiobotocore_lambda/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -20,23 +20,25 @@
 
 
 __all__ = (
     "ArchitectureType",
     "CodeSigningPolicyType",
     "EndPointTypeType",
     "EventSourcePositionType",
+    "FullDocumentType",
     "FunctionActiveV2WaiterName",
     "FunctionActiveWaiterName",
     "FunctionExistsWaiterName",
     "FunctionResponseTypeType",
     "FunctionUpdatedV2WaiterName",
     "FunctionUpdatedWaiterName",
     "FunctionUrlAuthTypeType",
     "FunctionVersionType",
     "InvocationTypeType",
+    "InvokeModeType",
     "LastUpdateStatusReasonCodeType",
     "LastUpdateStatusType",
     "ListAliasesPaginatorName",
     "ListCodeSigningConfigsPaginatorName",
     "ListEventSourceMappingsPaginatorName",
     "ListFunctionEventInvokeConfigsPaginatorName",
     "ListFunctionUrlConfigsPaginatorName",
@@ -46,14 +48,15 @@
     "ListLayersPaginatorName",
     "ListProvisionedConcurrencyConfigsPaginatorName",
     "ListVersionsByFunctionPaginatorName",
     "LogTypeType",
     "PackageTypeType",
     "ProvisionedConcurrencyStatusEnumType",
     "PublishedVersionActiveWaiterName",
+    "ResponseStreamingInvocationTypeType",
     "RuntimeType",
     "SnapStartApplyOnType",
     "SnapStartOptimizationStatusType",
     "SourceAccessTypeType",
     "StateReasonCodeType",
     "StateType",
     "TracingModeType",
@@ -67,23 +70,25 @@
 )
 
 
 ArchitectureType = Literal["arm64", "x86_64"]
 CodeSigningPolicyType = Literal["Enforce", "Warn"]
 EndPointTypeType = Literal["KAFKA_BOOTSTRAP_SERVERS"]
 EventSourcePositionType = Literal["AT_TIMESTAMP", "LATEST", "TRIM_HORIZON"]
+FullDocumentType = Literal["Default", "UpdateLookup"]
 FunctionActiveV2WaiterName = Literal["function_active_v2"]
 FunctionActiveWaiterName = Literal["function_active"]
 FunctionExistsWaiterName = Literal["function_exists"]
 FunctionResponseTypeType = Literal["ReportBatchItemFailures"]
 FunctionUpdatedV2WaiterName = Literal["function_updated_v2"]
 FunctionUpdatedWaiterName = Literal["function_updated"]
 FunctionUrlAuthTypeType = Literal["AWS_IAM", "NONE"]
 FunctionVersionType = Literal["ALL"]
 InvocationTypeType = Literal["DryRun", "Event", "RequestResponse"]
+InvokeModeType = Literal["BUFFERED", "RESPONSE_STREAM"]
 LastUpdateStatusReasonCodeType = Literal[
     "DisabledKMSKey",
     "EFSIOError",
     "EFSMountConnectivityError",
     "EFSMountFailure",
     "EFSMountTimeout",
     "EniLimitExceeded",
@@ -115,22 +120,24 @@
 ListLayersPaginatorName = Literal["list_layers"]
 ListProvisionedConcurrencyConfigsPaginatorName = Literal["list_provisioned_concurrency_configs"]
 ListVersionsByFunctionPaginatorName = Literal["list_versions_by_function"]
 LogTypeType = Literal["None", "Tail"]
 PackageTypeType = Literal["Image", "Zip"]
 ProvisionedConcurrencyStatusEnumType = Literal["FAILED", "IN_PROGRESS", "READY"]
 PublishedVersionActiveWaiterName = Literal["published_version_active"]
+ResponseStreamingInvocationTypeType = Literal["DryRun", "RequestResponse"]
 RuntimeType = Literal[
     "dotnet6",
     "dotnetcore1.0",
     "dotnetcore2.0",
     "dotnetcore2.1",
     "dotnetcore3.1",
     "go1.x",
     "java11",
+    "java17",
     "java8",
     "java8.al2",
     "nodejs",
     "nodejs10.x",
     "nodejs12.x",
     "nodejs14.x",
     "nodejs16.x",
@@ -138,20 +145,22 @@
     "nodejs4.3",
     "nodejs4.3-edge",
     "nodejs6.10",
     "nodejs8.10",
     "provided",
     "provided.al2",
     "python2.7",
+    "python3.10",
     "python3.6",
     "python3.7",
     "python3.8",
     "python3.9",
     "ruby2.5",
     "ruby2.7",
+    "ruby3.2",
 ]
 SnapStartApplyOnType = Literal["None", "PublishedVersions"]
 SnapStartOptimizationStatusType = Literal["Off", "On"]
 SourceAccessTypeType = Literal[
     "BASIC_AUTH",
     "CLIENT_CERTIFICATE_TLS_AUTH",
     "SASL_SCRAM_256_AUTH",
@@ -249,14 +258,15 @@
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
@@ -335,14 +345,15 @@
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
@@ -353,14 +364,15 @@
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
@@ -396,14 +408,15 @@
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
@@ -422,16 +435,19 @@
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
@@ -515,15 +531,17 @@
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

### Comparing `types-aiobotocore-lambda-2.5.0.post1/types_aiobotocore_lambda/literals.pyi` & `types-aiobotocore-lambda-2.5.1/types_aiobotocore_lambda/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -19,23 +19,25 @@
     from typing_extensions import Literal
 
 __all__ = (
     "ArchitectureType",
     "CodeSigningPolicyType",
     "EndPointTypeType",
     "EventSourcePositionType",
+    "FullDocumentType",
     "FunctionActiveV2WaiterName",
     "FunctionActiveWaiterName",
     "FunctionExistsWaiterName",
     "FunctionResponseTypeType",
     "FunctionUpdatedV2WaiterName",
     "FunctionUpdatedWaiterName",
     "FunctionUrlAuthTypeType",
     "FunctionVersionType",
     "InvocationTypeType",
+    "InvokeModeType",
     "LastUpdateStatusReasonCodeType",
     "LastUpdateStatusType",
     "ListAliasesPaginatorName",
     "ListCodeSigningConfigsPaginatorName",
     "ListEventSourceMappingsPaginatorName",
     "ListFunctionEventInvokeConfigsPaginatorName",
     "ListFunctionUrlConfigsPaginatorName",
@@ -45,14 +47,15 @@
     "ListLayersPaginatorName",
     "ListProvisionedConcurrencyConfigsPaginatorName",
     "ListVersionsByFunctionPaginatorName",
     "LogTypeType",
     "PackageTypeType",
     "ProvisionedConcurrencyStatusEnumType",
     "PublishedVersionActiveWaiterName",
+    "ResponseStreamingInvocationTypeType",
     "RuntimeType",
     "SnapStartApplyOnType",
     "SnapStartOptimizationStatusType",
     "SourceAccessTypeType",
     "StateReasonCodeType",
     "StateType",
     "TracingModeType",
@@ -65,23 +68,25 @@
     "RegionName",
 )
 
 ArchitectureType = Literal["arm64", "x86_64"]
 CodeSigningPolicyType = Literal["Enforce", "Warn"]
 EndPointTypeType = Literal["KAFKA_BOOTSTRAP_SERVERS"]
 EventSourcePositionType = Literal["AT_TIMESTAMP", "LATEST", "TRIM_HORIZON"]
+FullDocumentType = Literal["Default", "UpdateLookup"]
 FunctionActiveV2WaiterName = Literal["function_active_v2"]
 FunctionActiveWaiterName = Literal["function_active"]
 FunctionExistsWaiterName = Literal["function_exists"]
 FunctionResponseTypeType = Literal["ReportBatchItemFailures"]
 FunctionUpdatedV2WaiterName = Literal["function_updated_v2"]
 FunctionUpdatedWaiterName = Literal["function_updated"]
 FunctionUrlAuthTypeType = Literal["AWS_IAM", "NONE"]
 FunctionVersionType = Literal["ALL"]
 InvocationTypeType = Literal["DryRun", "Event", "RequestResponse"]
+InvokeModeType = Literal["BUFFERED", "RESPONSE_STREAM"]
 LastUpdateStatusReasonCodeType = Literal[
     "DisabledKMSKey",
     "EFSIOError",
     "EFSMountConnectivityError",
     "EFSMountFailure",
     "EFSMountTimeout",
     "EniLimitExceeded",
@@ -113,22 +118,24 @@
 ListLayersPaginatorName = Literal["list_layers"]
 ListProvisionedConcurrencyConfigsPaginatorName = Literal["list_provisioned_concurrency_configs"]
 ListVersionsByFunctionPaginatorName = Literal["list_versions_by_function"]
 LogTypeType = Literal["None", "Tail"]
 PackageTypeType = Literal["Image", "Zip"]
 ProvisionedConcurrencyStatusEnumType = Literal["FAILED", "IN_PROGRESS", "READY"]
 PublishedVersionActiveWaiterName = Literal["published_version_active"]
+ResponseStreamingInvocationTypeType = Literal["DryRun", "RequestResponse"]
 RuntimeType = Literal[
     "dotnet6",
     "dotnetcore1.0",
     "dotnetcore2.0",
     "dotnetcore2.1",
     "dotnetcore3.1",
     "go1.x",
     "java11",
+    "java17",
     "java8",
     "java8.al2",
     "nodejs",
     "nodejs10.x",
     "nodejs12.x",
     "nodejs14.x",
     "nodejs16.x",
@@ -136,20 +143,22 @@
     "nodejs4.3",
     "nodejs4.3-edge",
     "nodejs6.10",
     "nodejs8.10",
     "provided",
     "provided.al2",
     "python2.7",
+    "python3.10",
     "python3.6",
     "python3.7",
     "python3.8",
     "python3.9",
     "ruby2.5",
     "ruby2.7",
+    "ruby3.2",
 ]
 SnapStartApplyOnType = Literal["None", "PublishedVersions"]
 SnapStartOptimizationStatusType = Literal["Off", "On"]
 SourceAccessTypeType = Literal[
     "BASIC_AUTH",
     "CLIENT_CERTIFICATE_TLS_AUTH",
     "SASL_SCRAM_256_AUTH",
@@ -247,14 +256,15 @@
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
@@ -333,14 +343,15 @@
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
@@ -351,14 +362,15 @@
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
@@ -394,14 +406,15 @@
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
@@ -420,16 +433,19 @@
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
@@ -513,15 +529,17 @@
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

### Comparing `types-aiobotocore-lambda-2.5.0.post1/types_aiobotocore_lambda/paginator.py` & `types-aiobotocore-lambda-2.5.1/types_aiobotocore_lambda/paginator.py`

 * *Files 5% similar despite different names*

```diff
@@ -37,15 +37,15 @@
         list_layer_versions_paginator: ListLayerVersionsPaginator = client.get_paginator("list_layer_versions")
         list_layers_paginator: ListLayersPaginator = client.get_paginator("list_layers")
         list_provisioned_concurrency_configs_paginator: ListProvisionedConcurrencyConfigsPaginator = client.get_paginator("list_provisioned_concurrency_configs")
         list_versions_by_function_paginator: ListVersionsByFunctionPaginator = client.get_paginator("list_versions_by_function")
     ```
 """
 import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ArchitectureType, RuntimeType
 from .type_defs import (
     ListAliasesResponseTypeDef,
@@ -58,18 +58,14 @@
     ListLayersResponseTypeDef,
     ListLayerVersionsResponseTypeDef,
     ListProvisionedConcurrencyConfigsResponseTypeDef,
     ListVersionsByFunctionResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 
 __all__ = (
@@ -104,30 +100,30 @@
     """
 
     def paginate(
         self,
         *,
         FunctionName: str,
         FunctionVersion: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAliasesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Paginator.ListAliases.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/paginators/#listaliasespaginator)
         """
 
 
 class ListCodeSigningConfigsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Paginator.ListCodeSigningConfigs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/paginators/#listcodesigningconfigspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCodeSigningConfigsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Paginator.ListCodeSigningConfigs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/paginators/#listcodesigningconfigspaginator)
         """
 
 
@@ -138,45 +134,45 @@
     """
 
     def paginate(
         self,
         *,
         EventSourceArn: str = ...,
         FunctionName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEventSourceMappingsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Paginator.ListEventSourceMappings.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/paginators/#listeventsourcemappingspaginator)
         """
 
 
 class ListFunctionEventInvokeConfigsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Paginator.ListFunctionEventInvokeConfigs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/paginators/#listfunctioneventinvokeconfigspaginator)
     """
 
     def paginate(
-        self, *, FunctionName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, FunctionName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFunctionEventInvokeConfigsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Paginator.ListFunctionEventInvokeConfigs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/paginators/#listfunctioneventinvokeconfigspaginator)
         """
 
 
 class ListFunctionUrlConfigsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Paginator.ListFunctionUrlConfigs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/paginators/#listfunctionurlconfigspaginator)
     """
 
     def paginate(
-        self, *, FunctionName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, FunctionName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFunctionUrlConfigsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Paginator.ListFunctionUrlConfigs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/paginators/#listfunctionurlconfigspaginator)
         """
 
 
@@ -187,30 +183,30 @@
     """
 
     def paginate(
         self,
         *,
         MasterRegion: str = ...,
         FunctionVersion: Literal["ALL"] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFunctionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Paginator.ListFunctions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/paginators/#listfunctionspaginator)
         """
 
 
 class ListFunctionsByCodeSigningConfigPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Paginator.ListFunctionsByCodeSigningConfig)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/paginators/#listfunctionsbycodesigningconfigpaginator)
     """
 
     def paginate(
-        self, *, CodeSigningConfigArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, CodeSigningConfigArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFunctionsByCodeSigningConfigResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Paginator.ListFunctionsByCodeSigningConfig.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/paginators/#listfunctionsbycodesigningconfigpaginator)
         """
 
 
@@ -222,15 +218,15 @@
 
     def paginate(
         self,
         *,
         LayerName: str,
         CompatibleRuntime: RuntimeType = ...,
         CompatibleArchitecture: ArchitectureType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListLayerVersionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Paginator.ListLayerVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/paginators/#listlayerversionspaginator)
         """
 
 
@@ -241,43 +237,43 @@
     """
 
     def paginate(
         self,
         *,
         CompatibleRuntime: RuntimeType = ...,
         CompatibleArchitecture: ArchitectureType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListLayersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Paginator.ListLayers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/paginators/#listlayerspaginator)
         """
 
 
 class ListProvisionedConcurrencyConfigsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Paginator.ListProvisionedConcurrencyConfigs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/paginators/#listprovisionedconcurrencyconfigspaginator)
     """
 
     def paginate(
-        self, *, FunctionName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, FunctionName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProvisionedConcurrencyConfigsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Paginator.ListProvisionedConcurrencyConfigs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/paginators/#listprovisionedconcurrencyconfigspaginator)
         """
 
 
 class ListVersionsByFunctionPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Paginator.ListVersionsByFunction)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/paginators/#listversionsbyfunctionpaginator)
     """
 
     def paginate(
-        self, *, FunctionName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, FunctionName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListVersionsByFunctionResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Paginator.ListVersionsByFunction.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/paginators/#listversionsbyfunctionpaginator)
         """
```

### Comparing `types-aiobotocore-lambda-2.5.0.post1/types_aiobotocore_lambda/paginator.pyi` & `types-aiobotocore-lambda-2.5.1/types_aiobotocore_lambda/paginator.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -37,15 +37,15 @@
         list_layer_versions_paginator: ListLayerVersionsPaginator = client.get_paginator("list_layer_versions")
         list_layers_paginator: ListLayersPaginator = client.get_paginator("list_layers")
         list_provisioned_concurrency_configs_paginator: ListProvisionedConcurrencyConfigsPaginator = client.get_paginator("list_provisioned_concurrency_configs")
         list_versions_by_function_paginator: ListVersionsByFunctionPaginator = client.get_paginator("list_versions_by_function")
     ```
 """
 import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ArchitectureType, RuntimeType
 from .type_defs import (
     ListAliasesResponseTypeDef,
@@ -58,18 +58,14 @@
     ListLayersResponseTypeDef,
     ListLayerVersionsResponseTypeDef,
     ListProvisionedConcurrencyConfigsResponseTypeDef,
     ListVersionsByFunctionResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 __all__ = (
     "ListAliasesPaginator",
@@ -100,29 +96,29 @@
     """
 
     def paginate(
         self,
         *,
         FunctionName: str,
         FunctionVersion: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAliasesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Paginator.ListAliases.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/paginators/#listaliasespaginator)
         """
 
 class ListCodeSigningConfigsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Paginator.ListCodeSigningConfigs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/paginators/#listcodesigningconfigspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCodeSigningConfigsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Paginator.ListCodeSigningConfigs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/paginators/#listcodesigningconfigspaginator)
         """
 
 class ListEventSourceMappingsPaginator(AioPaginator):
@@ -132,43 +128,43 @@
     """
 
     def paginate(
         self,
         *,
         EventSourceArn: str = ...,
         FunctionName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEventSourceMappingsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Paginator.ListEventSourceMappings.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/paginators/#listeventsourcemappingspaginator)
         """
 
 class ListFunctionEventInvokeConfigsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Paginator.ListFunctionEventInvokeConfigs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/paginators/#listfunctioneventinvokeconfigspaginator)
     """
 
     def paginate(
-        self, *, FunctionName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, FunctionName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFunctionEventInvokeConfigsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Paginator.ListFunctionEventInvokeConfigs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/paginators/#listfunctioneventinvokeconfigspaginator)
         """
 
 class ListFunctionUrlConfigsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Paginator.ListFunctionUrlConfigs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/paginators/#listfunctionurlconfigspaginator)
     """
 
     def paginate(
-        self, *, FunctionName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, FunctionName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFunctionUrlConfigsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Paginator.ListFunctionUrlConfigs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/paginators/#listfunctionurlconfigspaginator)
         """
 
 class ListFunctionsPaginator(AioPaginator):
@@ -178,29 +174,29 @@
     """
 
     def paginate(
         self,
         *,
         MasterRegion: str = ...,
         FunctionVersion: Literal["ALL"] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFunctionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Paginator.ListFunctions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/paginators/#listfunctionspaginator)
         """
 
 class ListFunctionsByCodeSigningConfigPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Paginator.ListFunctionsByCodeSigningConfig)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/paginators/#listfunctionsbycodesigningconfigpaginator)
     """
 
     def paginate(
-        self, *, CodeSigningConfigArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, CodeSigningConfigArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFunctionsByCodeSigningConfigResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Paginator.ListFunctionsByCodeSigningConfig.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/paginators/#listfunctionsbycodesigningconfigpaginator)
         """
 
 class ListLayerVersionsPaginator(AioPaginator):
@@ -211,15 +207,15 @@
 
     def paginate(
         self,
         *,
         LayerName: str,
         CompatibleRuntime: RuntimeType = ...,
         CompatibleArchitecture: ArchitectureType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListLayerVersionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Paginator.ListLayerVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/paginators/#listlayerversionspaginator)
         """
 
 class ListLayersPaginator(AioPaginator):
@@ -229,41 +225,41 @@
     """
 
     def paginate(
         self,
         *,
         CompatibleRuntime: RuntimeType = ...,
         CompatibleArchitecture: ArchitectureType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListLayersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Paginator.ListLayers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/paginators/#listlayerspaginator)
         """
 
 class ListProvisionedConcurrencyConfigsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Paginator.ListProvisionedConcurrencyConfigs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/paginators/#listprovisionedconcurrencyconfigspaginator)
     """
 
     def paginate(
-        self, *, FunctionName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, FunctionName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProvisionedConcurrencyConfigsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Paginator.ListProvisionedConcurrencyConfigs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/paginators/#listprovisionedconcurrencyconfigspaginator)
         """
 
 class ListVersionsByFunctionPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Paginator.ListVersionsByFunction)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/paginators/#listversionsbyfunctionpaginator)
     """
 
     def paginate(
-        self, *, FunctionName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, FunctionName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListVersionsByFunctionResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda.Paginator.ListVersionsByFunction.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/paginators/#listversionsbyfunctionpaginator)
         """
```

### Comparing `types-aiobotocore-lambda-2.5.0.post1/types_aiobotocore_lambda/type_defs.py` & `types-aiobotocore-lambda-2.5.1/types_aiobotocore_lambda/type_defs.py`

 * *Files 6% similar despite different names*

```diff
@@ -17,21 +17,24 @@
 
 from aiobotocore.response import StreamingBody
 
 from .literals import (
     ArchitectureType,
     CodeSigningPolicyType,
     EventSourcePositionType,
+    FullDocumentType,
     FunctionUrlAuthTypeType,
     InvocationTypeType,
+    InvokeModeType,
     LastUpdateStatusReasonCodeType,
     LastUpdateStatusType,
     LogTypeType,
     PackageTypeType,
     ProvisionedConcurrencyStatusEnumType,
+    ResponseStreamingInvocationTypeType,
     RuntimeType,
     SnapStartApplyOnType,
     SnapStartOptimizationStatusType,
     SourceAccessTypeType,
     StateReasonCodeType,
     StateType,
     TracingModeType,
@@ -48,22 +51,25 @@
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AccountLimitTypeDef",
     "AccountUsageTypeDef",
     "AddLayerVersionPermissionRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "AddLayerVersionPermissionResponseTypeDef",
     "AddPermissionRequestRequestTypeDef",
+    "AddPermissionResponseTypeDef",
     "AliasRoutingConfigurationTypeDef",
     "AllowedPublishersTypeDef",
     "AmazonManagedKafkaEventSourceConfigTypeDef",
     "CodeSigningPoliciesTypeDef",
+    "ConcurrencyResponseMetadataTypeDef",
     "ConcurrencyTypeDef",
     "CorsTypeDef",
+    "DocumentDBEventSourceConfigTypeDef",
     "ScalingConfigTypeDef",
     "SelfManagedEventSourceTypeDef",
     "SelfManagedKafkaEventSourceConfigTypeDef",
     "SourceAccessConfigurationTypeDef",
     "DeadLetterConfigTypeDef",
     "EnvironmentTypeDef",
     "EphemeralStorageTypeDef",
@@ -81,86 +87,98 @@
     "DeleteFunctionEventInvokeConfigRequestRequestTypeDef",
     "DeleteFunctionRequestRequestTypeDef",
     "DeleteFunctionUrlConfigRequestRequestTypeDef",
     "DeleteLayerVersionRequestRequestTypeDef",
     "DeleteProvisionedConcurrencyConfigRequestRequestTypeDef",
     "OnFailureTypeDef",
     "OnSuccessTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EnvironmentErrorTypeDef",
     "FilterTypeDef",
     "FunctionCodeLocationTypeDef",
     "LayerTypeDef",
     "SnapStartResponseTypeDef",
     "TracingConfigResponseTypeDef",
     "VpcConfigResponseTypeDef",
     "GetAliasRequestRequestTypeDef",
     "GetCodeSigningConfigRequestRequestTypeDef",
     "GetEventSourceMappingRequestRequestTypeDef",
     "GetFunctionCodeSigningConfigRequestRequestTypeDef",
+    "GetFunctionCodeSigningConfigResponseTypeDef",
     "GetFunctionConcurrencyRequestRequestTypeDef",
+    "GetFunctionConcurrencyResponseTypeDef",
     "WaiterConfigTypeDef",
     "GetFunctionConfigurationRequestRequestTypeDef",
     "GetFunctionEventInvokeConfigRequestRequestTypeDef",
     "GetFunctionRequestRequestTypeDef",
     "GetFunctionUrlConfigRequestRequestTypeDef",
     "GetLayerVersionByArnRequestRequestTypeDef",
     "GetLayerVersionPolicyRequestRequestTypeDef",
+    "GetLayerVersionPolicyResponseTypeDef",
     "GetLayerVersionRequestRequestTypeDef",
     "LayerVersionContentOutputTypeDef",
     "GetPolicyRequestRequestTypeDef",
+    "GetPolicyResponseTypeDef",
     "GetProvisionedConcurrencyConfigRequestRequestTypeDef",
+    "GetProvisionedConcurrencyConfigResponseTypeDef",
     "GetRuntimeManagementConfigRequestRequestTypeDef",
+    "GetRuntimeManagementConfigResponseTypeDef",
     "ImageConfigErrorTypeDef",
     "InvocationRequestRequestTypeDef",
+    "InvocationResponseTypeDef",
     "InvokeAsyncRequestRequestTypeDef",
+    "InvokeAsyncResponseTypeDef",
+    "InvokeResponseStreamUpdateTypeDef",
+    "InvokeWithResponseStreamCompleteEventTypeDef",
+    "InvokeWithResponseStreamRequestRequestTypeDef",
     "LayerVersionContentInputTypeDef",
     "LayerVersionsListItemTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListAliasesRequestListAliasesPaginateTypeDef",
     "ListAliasesRequestRequestTypeDef",
+    "ListCodeSigningConfigsRequestListCodeSigningConfigsPaginateTypeDef",
     "ListCodeSigningConfigsRequestRequestTypeDef",
+    "ListEventSourceMappingsRequestListEventSourceMappingsPaginateTypeDef",
     "ListEventSourceMappingsRequestRequestTypeDef",
+    "ListFunctionEventInvokeConfigsRequestListFunctionEventInvokeConfigsPaginateTypeDef",
     "ListFunctionEventInvokeConfigsRequestRequestTypeDef",
+    "ListFunctionUrlConfigsRequestListFunctionUrlConfigsPaginateTypeDef",
     "ListFunctionUrlConfigsRequestRequestTypeDef",
+    "ListFunctionsByCodeSigningConfigRequestListFunctionsByCodeSigningConfigPaginateTypeDef",
     "ListFunctionsByCodeSigningConfigRequestRequestTypeDef",
+    "ListFunctionsByCodeSigningConfigResponseTypeDef",
+    "ListFunctionsRequestListFunctionsPaginateTypeDef",
     "ListFunctionsRequestRequestTypeDef",
+    "ListLayerVersionsRequestListLayerVersionsPaginateTypeDef",
     "ListLayerVersionsRequestRequestTypeDef",
+    "ListLayersRequestListLayersPaginateTypeDef",
     "ListLayersRequestRequestTypeDef",
+    "ListProvisionedConcurrencyConfigsRequestListProvisionedConcurrencyConfigsPaginateTypeDef",
     "ListProvisionedConcurrencyConfigsRequestRequestTypeDef",
     "ProvisionedConcurrencyConfigListItemTypeDef",
     "ListTagsRequestRequestTypeDef",
+    "ListTagsResponseTypeDef",
+    "ListVersionsByFunctionRequestListVersionsByFunctionPaginateTypeDef",
     "ListVersionsByFunctionRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "PublishVersionRequestRequestTypeDef",
     "PutFunctionCodeSigningConfigRequestRequestTypeDef",
+    "PutFunctionCodeSigningConfigResponseTypeDef",
     "PutFunctionConcurrencyRequestRequestTypeDef",
     "PutProvisionedConcurrencyConfigRequestRequestTypeDef",
+    "PutProvisionedConcurrencyConfigResponseTypeDef",
     "PutRuntimeManagementConfigRequestRequestTypeDef",
+    "PutRuntimeManagementConfigResponseTypeDef",
     "RemoveLayerVersionPermissionRequestRequestTypeDef",
     "RemovePermissionRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "RuntimeVersionErrorTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateFunctionCodeRequestRequestTypeDef",
-    "AddLayerVersionPermissionResponseTypeDef",
-    "AddPermissionResponseTypeDef",
-    "ConcurrencyResponseMetadataTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "GetAccountSettingsResponseTypeDef",
-    "GetFunctionCodeSigningConfigResponseTypeDef",
-    "GetFunctionConcurrencyResponseTypeDef",
-    "GetLayerVersionPolicyResponseTypeDef",
-    "GetPolicyResponseTypeDef",
-    "GetProvisionedConcurrencyConfigResponseTypeDef",
-    "GetRuntimeManagementConfigResponseTypeDef",
-    "InvocationResponseTypeDef",
-    "InvokeAsyncResponseTypeDef",
-    "ListFunctionsByCodeSigningConfigResponseTypeDef",
-    "ListTagsResponseTypeDef",
-    "PutFunctionCodeSigningConfigResponseTypeDef",
-    "PutProvisionedConcurrencyConfigResponseTypeDef",
-    "PutRuntimeManagementConfigResponseTypeDef",
     "AliasConfigurationResponseMetadataTypeDef",
     "AliasConfigurationTypeDef",
     "CreateAliasRequestRequestTypeDef",
     "UpdateAliasRequestRequestTypeDef",
     "CodeSigningConfigTypeDef",
     "CreateCodeSigningConfigRequestRequestTypeDef",
     "UpdateCodeSigningConfigRequestRequestTypeDef",
@@ -180,28 +198,18 @@
     "GetFunctionConfigurationRequestPublishedVersionActiveWaitTypeDef",
     "GetFunctionRequestFunctionActiveV2WaitTypeDef",
     "GetFunctionRequestFunctionExistsWaitTypeDef",
     "GetFunctionRequestFunctionUpdatedV2WaitTypeDef",
     "GetLayerVersionResponseTypeDef",
     "PublishLayerVersionResponseTypeDef",
     "ImageConfigResponseTypeDef",
+    "InvokeWithResponseStreamResponseEventTypeDef",
     "PublishLayerVersionRequestRequestTypeDef",
     "LayersListItemTypeDef",
     "ListLayerVersionsResponseTypeDef",
-    "ListAliasesRequestListAliasesPaginateTypeDef",
-    "ListCodeSigningConfigsRequestListCodeSigningConfigsPaginateTypeDef",
-    "ListEventSourceMappingsRequestListEventSourceMappingsPaginateTypeDef",
-    "ListFunctionEventInvokeConfigsRequestListFunctionEventInvokeConfigsPaginateTypeDef",
-    "ListFunctionUrlConfigsRequestListFunctionUrlConfigsPaginateTypeDef",
-    "ListFunctionsByCodeSigningConfigRequestListFunctionsByCodeSigningConfigPaginateTypeDef",
-    "ListFunctionsRequestListFunctionsPaginateTypeDef",
-    "ListLayerVersionsRequestListLayerVersionsPaginateTypeDef",
-    "ListLayersRequestListLayersPaginateTypeDef",
-    "ListProvisionedConcurrencyConfigsRequestListProvisionedConcurrencyConfigsPaginateTypeDef",
-    "ListVersionsByFunctionRequestListVersionsByFunctionPaginateTypeDef",
     "ListProvisionedConcurrencyConfigsResponseTypeDef",
     "RuntimeVersionConfigTypeDef",
     "ListAliasesResponseTypeDef",
     "CreateCodeSigningConfigResponseTypeDef",
     "GetCodeSigningConfigResponseTypeDef",
     "ListCodeSigningConfigsResponseTypeDef",
     "UpdateCodeSigningConfigResponseTypeDef",
@@ -210,14 +218,15 @@
     "FunctionEventInvokeConfigTypeDef",
     "PutFunctionEventInvokeConfigRequestRequestTypeDef",
     "UpdateFunctionEventInvokeConfigRequestRequestTypeDef",
     "CreateEventSourceMappingRequestRequestTypeDef",
     "EventSourceMappingConfigurationResponseMetadataTypeDef",
     "EventSourceMappingConfigurationTypeDef",
     "UpdateEventSourceMappingRequestRequestTypeDef",
+    "InvokeWithResponseStreamResponseTypeDef",
     "ListLayersResponseTypeDef",
     "FunctionConfigurationResponseMetadataTypeDef",
     "FunctionConfigurationTypeDef",
     "ListFunctionEventInvokeConfigsResponseTypeDef",
     "ListEventSourceMappingsResponseTypeDef",
     "GetFunctionResponseTypeDef",
     "ListFunctionsResponseTypeDef",
@@ -268,22 +277,20 @@
 class AddLayerVersionPermissionRequestRequestTypeDef(
     _RequiredAddLayerVersionPermissionRequestRequestTypeDef,
     _OptionalAddLayerVersionPermissionRequestRequestTypeDef,
 ):
     pass
 
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AddLayerVersionPermissionResponseTypeDef = TypedDict(
+    "AddLayerVersionPermissionResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "Statement": str,
+        "RevisionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAddPermissionRequestRequestTypeDef = TypedDict(
     "_RequiredAddPermissionRequestRequestTypeDef",
     {
         "FunctionName": str,
@@ -309,14 +316,22 @@
 
 class AddPermissionRequestRequestTypeDef(
     _RequiredAddPermissionRequestRequestTypeDef, _OptionalAddPermissionRequestRequestTypeDef
 ):
     pass
 
 
+AddPermissionResponseTypeDef = TypedDict(
+    "AddPermissionResponseTypeDef",
+    {
+        "Statement": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AliasRoutingConfigurationTypeDef = TypedDict(
     "AliasRoutingConfigurationTypeDef",
     {
         "AdditionalVersionWeights": Mapping[str, float],
     },
     total=False,
 )
@@ -340,14 +355,22 @@
     "CodeSigningPoliciesTypeDef",
     {
         "UntrustedArtifactOnDeployment": CodeSigningPolicyType,
     },
     total=False,
 )
 
+ConcurrencyResponseMetadataTypeDef = TypedDict(
+    "ConcurrencyResponseMetadataTypeDef",
+    {
+        "ReservedConcurrentExecutions": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ConcurrencyTypeDef = TypedDict(
     "ConcurrencyTypeDef",
     {
         "ReservedConcurrentExecutions": int,
     },
     total=False,
 )
@@ -361,14 +384,24 @@
         "AllowOrigins": Sequence[str],
         "ExposeHeaders": Sequence[str],
         "MaxAge": int,
     },
     total=False,
 )
 
+DocumentDBEventSourceConfigTypeDef = TypedDict(
+    "DocumentDBEventSourceConfigTypeDef",
+    {
+        "DatabaseName": str,
+        "CollectionName": str,
+        "FullDocument": FullDocumentType,
+    },
+    total=False,
+)
+
 ScalingConfigTypeDef = TypedDict(
     "ScalingConfigTypeDef",
     {
         "MaximumConcurrency": int,
     },
     total=False,
 )
@@ -605,14 +638,21 @@
     "OnSuccessTypeDef",
     {
         "Destination": str,
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
 EnvironmentErrorTypeDef = TypedDict(
     "EnvironmentErrorTypeDef",
     {
         "ErrorCode": str,
         "Message": str,
     },
     total=False,
@@ -700,21 +740,38 @@
 GetFunctionCodeSigningConfigRequestRequestTypeDef = TypedDict(
     "GetFunctionCodeSigningConfigRequestRequestTypeDef",
     {
         "FunctionName": str,
     },
 )
 
+GetFunctionCodeSigningConfigResponseTypeDef = TypedDict(
+    "GetFunctionCodeSigningConfigResponseTypeDef",
+    {
+        "CodeSigningConfigArn": str,
+        "FunctionName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetFunctionConcurrencyRequestRequestTypeDef = TypedDict(
     "GetFunctionConcurrencyRequestRequestTypeDef",
     {
         "FunctionName": str,
     },
 )
 
+GetFunctionConcurrencyResponseTypeDef = TypedDict(
+    "GetFunctionConcurrencyResponseTypeDef",
+    {
+        "ReservedConcurrentExecutions": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 WaiterConfigTypeDef = TypedDict(
     "WaiterConfigTypeDef",
     {
         "Delay": int,
         "MaxAttempts": int,
     },
     total=False,
@@ -818,14 +875,23 @@
     "GetLayerVersionPolicyRequestRequestTypeDef",
     {
         "LayerName": str,
         "VersionNumber": int,
     },
 )
 
+GetLayerVersionPolicyResponseTypeDef = TypedDict(
+    "GetLayerVersionPolicyResponseTypeDef",
+    {
+        "Policy": str,
+        "RevisionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetLayerVersionRequestRequestTypeDef = TypedDict(
     "GetLayerVersionRequestRequestTypeDef",
     {
         "LayerName": str,
         "VersionNumber": int,
     },
 )
@@ -859,22 +925,44 @@
 
 class GetPolicyRequestRequestTypeDef(
     _RequiredGetPolicyRequestRequestTypeDef, _OptionalGetPolicyRequestRequestTypeDef
 ):
     pass
 
 
+GetPolicyResponseTypeDef = TypedDict(
+    "GetPolicyResponseTypeDef",
+    {
+        "Policy": str,
+        "RevisionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetProvisionedConcurrencyConfigRequestRequestTypeDef = TypedDict(
     "GetProvisionedConcurrencyConfigRequestRequestTypeDef",
     {
         "FunctionName": str,
         "Qualifier": str,
     },
 )
 
+GetProvisionedConcurrencyConfigResponseTypeDef = TypedDict(
+    "GetProvisionedConcurrencyConfigResponseTypeDef",
+    {
+        "RequestedProvisionedConcurrentExecutions": int,
+        "AvailableProvisionedConcurrentExecutions": int,
+        "AllocatedProvisionedConcurrentExecutions": int,
+        "Status": ProvisionedConcurrencyStatusEnumType,
+        "StatusReason": str,
+        "LastModified": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetRuntimeManagementConfigRequestRequestTypeDef = TypedDict(
     "_RequiredGetRuntimeManagementConfigRequestRequestTypeDef",
     {
         "FunctionName": str,
     },
 )
 _OptionalGetRuntimeManagementConfigRequestRequestTypeDef = TypedDict(
@@ -889,14 +977,24 @@
 class GetRuntimeManagementConfigRequestRequestTypeDef(
     _RequiredGetRuntimeManagementConfigRequestRequestTypeDef,
     _OptionalGetRuntimeManagementConfigRequestRequestTypeDef,
 ):
     pass
 
 
+GetRuntimeManagementConfigResponseTypeDef = TypedDict(
+    "GetRuntimeManagementConfigResponseTypeDef",
+    {
+        "UpdateRuntimeOn": UpdateRuntimeOnType,
+        "RuntimeVersionArn": str,
+        "FunctionArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ImageConfigErrorTypeDef = TypedDict(
     "ImageConfigErrorTypeDef",
     {
         "ErrorCode": str,
         "Message": str,
     },
     total=False,
@@ -923,22 +1021,86 @@
 
 class InvocationRequestRequestTypeDef(
     _RequiredInvocationRequestRequestTypeDef, _OptionalInvocationRequestRequestTypeDef
 ):
     pass
 
 
+InvocationResponseTypeDef = TypedDict(
+    "InvocationResponseTypeDef",
+    {
+        "StatusCode": int,
+        "FunctionError": str,
+        "LogResult": str,
+        "Payload": StreamingBody,
+        "ExecutedVersion": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 InvokeAsyncRequestRequestTypeDef = TypedDict(
     "InvokeAsyncRequestRequestTypeDef",
     {
         "FunctionName": str,
         "InvokeArgs": Union[str, bytes, IO[Any], StreamingBody],
     },
 )
 
+InvokeAsyncResponseTypeDef = TypedDict(
+    "InvokeAsyncResponseTypeDef",
+    {
+        "Status": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+InvokeResponseStreamUpdateTypeDef = TypedDict(
+    "InvokeResponseStreamUpdateTypeDef",
+    {
+        "Payload": bytes,
+    },
+    total=False,
+)
+
+InvokeWithResponseStreamCompleteEventTypeDef = TypedDict(
+    "InvokeWithResponseStreamCompleteEventTypeDef",
+    {
+        "ErrorCode": str,
+        "ErrorDetails": str,
+        "LogResult": str,
+    },
+    total=False,
+)
+
+_RequiredInvokeWithResponseStreamRequestRequestTypeDef = TypedDict(
+    "_RequiredInvokeWithResponseStreamRequestRequestTypeDef",
+    {
+        "FunctionName": str,
+    },
+)
+_OptionalInvokeWithResponseStreamRequestRequestTypeDef = TypedDict(
+    "_OptionalInvokeWithResponseStreamRequestRequestTypeDef",
+    {
+        "InvocationType": ResponseStreamingInvocationTypeType,
+        "LogType": LogTypeType,
+        "ClientContext": str,
+        "Qualifier": str,
+        "Payload": Union[str, bytes, IO[Any], StreamingBody],
+    },
+    total=False,
+)
+
+
+class InvokeWithResponseStreamRequestRequestTypeDef(
+    _RequiredInvokeWithResponseStreamRequestRequestTypeDef,
+    _OptionalInvokeWithResponseStreamRequestRequestTypeDef,
+):
+    pass
+
+
 LayerVersionContentInputTypeDef = TypedDict(
     "LayerVersionContentInputTypeDef",
     {
         "S3Bucket": str,
         "S3Key": str,
         "S3ObjectVersion": str,
         "ZipFile": Union[str, bytes, IO[Any], StreamingBody],
@@ -956,24 +1118,37 @@
         "CompatibleRuntimes": List[RuntimeType],
         "LicenseInfo": str,
         "CompatibleArchitectures": List[ArchitectureType],
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListAliasesRequestListAliasesPaginateTypeDef = TypedDict(
+    "_RequiredListAliasesRequestListAliasesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "FunctionName": str,
+    },
+)
+_OptionalListAliasesRequestListAliasesPaginateTypeDef = TypedDict(
+    "_OptionalListAliasesRequestListAliasesPaginateTypeDef",
+    {
+        "FunctionVersion": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListAliasesRequestListAliasesPaginateTypeDef(
+    _RequiredListAliasesRequestListAliasesPaginateTypeDef,
+    _OptionalListAliasesRequestListAliasesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListAliasesRequestRequestTypeDef = TypedDict(
     "_RequiredListAliasesRequestRequestTypeDef",
     {
         "FunctionName": str,
     },
 )
 _OptionalListAliasesRequestRequestTypeDef = TypedDict(
@@ -989,34 +1164,74 @@
 
 class ListAliasesRequestRequestTypeDef(
     _RequiredListAliasesRequestRequestTypeDef, _OptionalListAliasesRequestRequestTypeDef
 ):
     pass
 
 
+ListCodeSigningConfigsRequestListCodeSigningConfigsPaginateTypeDef = TypedDict(
+    "ListCodeSigningConfigsRequestListCodeSigningConfigsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCodeSigningConfigsRequestRequestTypeDef = TypedDict(
     "ListCodeSigningConfigsRequestRequestTypeDef",
     {
         "Marker": str,
         "MaxItems": int,
     },
     total=False,
 )
 
+ListEventSourceMappingsRequestListEventSourceMappingsPaginateTypeDef = TypedDict(
+    "ListEventSourceMappingsRequestListEventSourceMappingsPaginateTypeDef",
+    {
+        "EventSourceArn": str,
+        "FunctionName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListEventSourceMappingsRequestRequestTypeDef = TypedDict(
     "ListEventSourceMappingsRequestRequestTypeDef",
     {
         "EventSourceArn": str,
         "FunctionName": str,
         "Marker": str,
         "MaxItems": int,
     },
     total=False,
 )
 
+_RequiredListFunctionEventInvokeConfigsRequestListFunctionEventInvokeConfigsPaginateTypeDef = TypedDict(
+    "_RequiredListFunctionEventInvokeConfigsRequestListFunctionEventInvokeConfigsPaginateTypeDef",
+    {
+        "FunctionName": str,
+    },
+)
+_OptionalListFunctionEventInvokeConfigsRequestListFunctionEventInvokeConfigsPaginateTypeDef = TypedDict(
+    "_OptionalListFunctionEventInvokeConfigsRequestListFunctionEventInvokeConfigsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListFunctionEventInvokeConfigsRequestListFunctionEventInvokeConfigsPaginateTypeDef(
+    _RequiredListFunctionEventInvokeConfigsRequestListFunctionEventInvokeConfigsPaginateTypeDef,
+    _OptionalListFunctionEventInvokeConfigsRequestListFunctionEventInvokeConfigsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListFunctionEventInvokeConfigsRequestRequestTypeDef = TypedDict(
     "_RequiredListFunctionEventInvokeConfigsRequestRequestTypeDef",
     {
         "FunctionName": str,
     },
 )
 _OptionalListFunctionEventInvokeConfigsRequestRequestTypeDef = TypedDict(
@@ -1032,14 +1247,36 @@
 class ListFunctionEventInvokeConfigsRequestRequestTypeDef(
     _RequiredListFunctionEventInvokeConfigsRequestRequestTypeDef,
     _OptionalListFunctionEventInvokeConfigsRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListFunctionUrlConfigsRequestListFunctionUrlConfigsPaginateTypeDef = TypedDict(
+    "_RequiredListFunctionUrlConfigsRequestListFunctionUrlConfigsPaginateTypeDef",
+    {
+        "FunctionName": str,
+    },
+)
+_OptionalListFunctionUrlConfigsRequestListFunctionUrlConfigsPaginateTypeDef = TypedDict(
+    "_OptionalListFunctionUrlConfigsRequestListFunctionUrlConfigsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListFunctionUrlConfigsRequestListFunctionUrlConfigsPaginateTypeDef(
+    _RequiredListFunctionUrlConfigsRequestListFunctionUrlConfigsPaginateTypeDef,
+    _OptionalListFunctionUrlConfigsRequestListFunctionUrlConfigsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListFunctionUrlConfigsRequestRequestTypeDef = TypedDict(
     "_RequiredListFunctionUrlConfigsRequestRequestTypeDef",
     {
         "FunctionName": str,
     },
 )
 _OptionalListFunctionUrlConfigsRequestRequestTypeDef = TypedDict(
@@ -1055,14 +1292,36 @@
 class ListFunctionUrlConfigsRequestRequestTypeDef(
     _RequiredListFunctionUrlConfigsRequestRequestTypeDef,
     _OptionalListFunctionUrlConfigsRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListFunctionsByCodeSigningConfigRequestListFunctionsByCodeSigningConfigPaginateTypeDef = TypedDict(
+    "_RequiredListFunctionsByCodeSigningConfigRequestListFunctionsByCodeSigningConfigPaginateTypeDef",
+    {
+        "CodeSigningConfigArn": str,
+    },
+)
+_OptionalListFunctionsByCodeSigningConfigRequestListFunctionsByCodeSigningConfigPaginateTypeDef = TypedDict(
+    "_OptionalListFunctionsByCodeSigningConfigRequestListFunctionsByCodeSigningConfigPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListFunctionsByCodeSigningConfigRequestListFunctionsByCodeSigningConfigPaginateTypeDef(
+    _RequiredListFunctionsByCodeSigningConfigRequestListFunctionsByCodeSigningConfigPaginateTypeDef,
+    _OptionalListFunctionsByCodeSigningConfigRequestListFunctionsByCodeSigningConfigPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListFunctionsByCodeSigningConfigRequestRequestTypeDef = TypedDict(
     "_RequiredListFunctionsByCodeSigningConfigRequestRequestTypeDef",
     {
         "CodeSigningConfigArn": str,
     },
 )
 _OptionalListFunctionsByCodeSigningConfigRequestRequestTypeDef = TypedDict(
@@ -1078,25 +1337,68 @@
 class ListFunctionsByCodeSigningConfigRequestRequestTypeDef(
     _RequiredListFunctionsByCodeSigningConfigRequestRequestTypeDef,
     _OptionalListFunctionsByCodeSigningConfigRequestRequestTypeDef,
 ):
     pass
 
 
+ListFunctionsByCodeSigningConfigResponseTypeDef = TypedDict(
+    "ListFunctionsByCodeSigningConfigResponseTypeDef",
+    {
+        "NextMarker": str,
+        "FunctionArns": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListFunctionsRequestListFunctionsPaginateTypeDef = TypedDict(
+    "ListFunctionsRequestListFunctionsPaginateTypeDef",
+    {
+        "MasterRegion": str,
+        "FunctionVersion": Literal["ALL"],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListFunctionsRequestRequestTypeDef = TypedDict(
     "ListFunctionsRequestRequestTypeDef",
     {
         "MasterRegion": str,
         "FunctionVersion": Literal["ALL"],
         "Marker": str,
         "MaxItems": int,
     },
     total=False,
 )
 
+_RequiredListLayerVersionsRequestListLayerVersionsPaginateTypeDef = TypedDict(
+    "_RequiredListLayerVersionsRequestListLayerVersionsPaginateTypeDef",
+    {
+        "LayerName": str,
+    },
+)
+_OptionalListLayerVersionsRequestListLayerVersionsPaginateTypeDef = TypedDict(
+    "_OptionalListLayerVersionsRequestListLayerVersionsPaginateTypeDef",
+    {
+        "CompatibleRuntime": RuntimeType,
+        "CompatibleArchitecture": ArchitectureType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListLayerVersionsRequestListLayerVersionsPaginateTypeDef(
+    _RequiredListLayerVersionsRequestListLayerVersionsPaginateTypeDef,
+    _OptionalListLayerVersionsRequestListLayerVersionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListLayerVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredListLayerVersionsRequestRequestTypeDef",
     {
         "LayerName": str,
     },
 )
 _OptionalListLayerVersionsRequestRequestTypeDef = TypedDict(
@@ -1113,25 +1415,57 @@
 
 class ListLayerVersionsRequestRequestTypeDef(
     _RequiredListLayerVersionsRequestRequestTypeDef, _OptionalListLayerVersionsRequestRequestTypeDef
 ):
     pass
 
 
+ListLayersRequestListLayersPaginateTypeDef = TypedDict(
+    "ListLayersRequestListLayersPaginateTypeDef",
+    {
+        "CompatibleRuntime": RuntimeType,
+        "CompatibleArchitecture": ArchitectureType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListLayersRequestRequestTypeDef = TypedDict(
     "ListLayersRequestRequestTypeDef",
     {
         "CompatibleRuntime": RuntimeType,
         "Marker": str,
         "MaxItems": int,
         "CompatibleArchitecture": ArchitectureType,
     },
     total=False,
 )
 
+_RequiredListProvisionedConcurrencyConfigsRequestListProvisionedConcurrencyConfigsPaginateTypeDef = TypedDict(
+    "_RequiredListProvisionedConcurrencyConfigsRequestListProvisionedConcurrencyConfigsPaginateTypeDef",
+    {
+        "FunctionName": str,
+    },
+)
+_OptionalListProvisionedConcurrencyConfigsRequestListProvisionedConcurrencyConfigsPaginateTypeDef = TypedDict(
+    "_OptionalListProvisionedConcurrencyConfigsRequestListProvisionedConcurrencyConfigsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListProvisionedConcurrencyConfigsRequestListProvisionedConcurrencyConfigsPaginateTypeDef(
+    _RequiredListProvisionedConcurrencyConfigsRequestListProvisionedConcurrencyConfigsPaginateTypeDef,
+    _OptionalListProvisionedConcurrencyConfigsRequestListProvisionedConcurrencyConfigsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListProvisionedConcurrencyConfigsRequestRequestTypeDef = TypedDict(
     "_RequiredListProvisionedConcurrencyConfigsRequestRequestTypeDef",
     {
         "FunctionName": str,
     },
 )
 _OptionalListProvisionedConcurrencyConfigsRequestRequestTypeDef = TypedDict(
@@ -1168,14 +1502,44 @@
 ListTagsRequestRequestTypeDef = TypedDict(
     "ListTagsRequestRequestTypeDef",
     {
         "Resource": str,
     },
 )
 
+ListTagsResponseTypeDef = TypedDict(
+    "ListTagsResponseTypeDef",
+    {
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListVersionsByFunctionRequestListVersionsByFunctionPaginateTypeDef = TypedDict(
+    "_RequiredListVersionsByFunctionRequestListVersionsByFunctionPaginateTypeDef",
+    {
+        "FunctionName": str,
+    },
+)
+_OptionalListVersionsByFunctionRequestListVersionsByFunctionPaginateTypeDef = TypedDict(
+    "_OptionalListVersionsByFunctionRequestListVersionsByFunctionPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListVersionsByFunctionRequestListVersionsByFunctionPaginateTypeDef(
+    _RequiredListVersionsByFunctionRequestListVersionsByFunctionPaginateTypeDef,
+    _OptionalListVersionsByFunctionRequestListVersionsByFunctionPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListVersionsByFunctionRequestRequestTypeDef = TypedDict(
     "_RequiredListVersionsByFunctionRequestRequestTypeDef",
     {
         "FunctionName": str,
     },
 )
 _OptionalListVersionsByFunctionRequestRequestTypeDef = TypedDict(
@@ -1191,14 +1555,24 @@
 class ListVersionsByFunctionRequestRequestTypeDef(
     _RequiredListVersionsByFunctionRequestRequestTypeDef,
     _OptionalListVersionsByFunctionRequestRequestTypeDef,
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
 _RequiredPublishVersionRequestRequestTypeDef = TypedDict(
     "_RequiredPublishVersionRequestRequestTypeDef",
     {
         "FunctionName": str,
     },
 )
 _OptionalPublishVersionRequestRequestTypeDef = TypedDict(
@@ -1222,14 +1596,23 @@
     "PutFunctionCodeSigningConfigRequestRequestTypeDef",
     {
         "CodeSigningConfigArn": str,
         "FunctionName": str,
     },
 )
 
+PutFunctionCodeSigningConfigResponseTypeDef = TypedDict(
+    "PutFunctionCodeSigningConfigResponseTypeDef",
+    {
+        "CodeSigningConfigArn": str,
+        "FunctionName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 PutFunctionConcurrencyRequestRequestTypeDef = TypedDict(
     "PutFunctionConcurrencyRequestRequestTypeDef",
     {
         "FunctionName": str,
         "ReservedConcurrentExecutions": int,
     },
 )
@@ -1239,14 +1622,27 @@
     {
         "FunctionName": str,
         "Qualifier": str,
         "ProvisionedConcurrentExecutions": int,
     },
 )
 
+PutProvisionedConcurrencyConfigResponseTypeDef = TypedDict(
+    "PutProvisionedConcurrencyConfigResponseTypeDef",
+    {
+        "RequestedProvisionedConcurrentExecutions": int,
+        "AvailableProvisionedConcurrentExecutions": int,
+        "AllocatedProvisionedConcurrentExecutions": int,
+        "Status": ProvisionedConcurrencyStatusEnumType,
+        "StatusReason": str,
+        "LastModified": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredPutRuntimeManagementConfigRequestRequestTypeDef = TypedDict(
     "_RequiredPutRuntimeManagementConfigRequestRequestTypeDef",
     {
         "FunctionName": str,
         "UpdateRuntimeOn": UpdateRuntimeOnType,
     },
 )
@@ -1263,14 +1659,24 @@
 class PutRuntimeManagementConfigRequestRequestTypeDef(
     _RequiredPutRuntimeManagementConfigRequestRequestTypeDef,
     _OptionalPutRuntimeManagementConfigRequestRequestTypeDef,
 ):
     pass
 
 
+PutRuntimeManagementConfigResponseTypeDef = TypedDict(
+    "PutRuntimeManagementConfigResponseTypeDef",
+    {
+        "UpdateRuntimeOn": UpdateRuntimeOnType,
+        "FunctionArn": str,
+        "RuntimeVersionArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredRemoveLayerVersionPermissionRequestRequestTypeDef = TypedDict(
     "_RequiredRemoveLayerVersionPermissionRequestRequestTypeDef",
     {
         "LayerName": str,
         "VersionNumber": int,
         "StatementId": str,
     },
@@ -1310,14 +1716,25 @@
 
 class RemovePermissionRequestRequestTypeDef(
     _RequiredRemovePermissionRequestRequestTypeDef, _OptionalRemovePermissionRequestRequestTypeDef
 ):
     pass
 
 
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
 RuntimeVersionErrorTypeDef = TypedDict(
     "RuntimeVersionErrorTypeDef",
     {
         "ErrorCode": str,
         "Message": str,
     },
     total=False,
@@ -1365,191 +1782,33 @@
 class UpdateFunctionCodeRequestRequestTypeDef(
     _RequiredUpdateFunctionCodeRequestRequestTypeDef,
     _OptionalUpdateFunctionCodeRequestRequestTypeDef,
 ):
     pass
 
 
-AddLayerVersionPermissionResponseTypeDef = TypedDict(
-    "AddLayerVersionPermissionResponseTypeDef",
-    {
-        "Statement": str,
-        "RevisionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-AddPermissionResponseTypeDef = TypedDict(
-    "AddPermissionResponseTypeDef",
-    {
-        "Statement": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ConcurrencyResponseMetadataTypeDef = TypedDict(
-    "ConcurrencyResponseMetadataTypeDef",
-    {
-        "ReservedConcurrentExecutions": int,
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
 GetAccountSettingsResponseTypeDef = TypedDict(
     "GetAccountSettingsResponseTypeDef",
     {
         "AccountLimit": AccountLimitTypeDef,
         "AccountUsage": AccountUsageTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetFunctionCodeSigningConfigResponseTypeDef = TypedDict(
-    "GetFunctionCodeSigningConfigResponseTypeDef",
-    {
-        "CodeSigningConfigArn": str,
-        "FunctionName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetFunctionConcurrencyResponseTypeDef = TypedDict(
-    "GetFunctionConcurrencyResponseTypeDef",
-    {
-        "ReservedConcurrentExecutions": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetLayerVersionPolicyResponseTypeDef = TypedDict(
-    "GetLayerVersionPolicyResponseTypeDef",
-    {
-        "Policy": str,
-        "RevisionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetPolicyResponseTypeDef = TypedDict(
-    "GetPolicyResponseTypeDef",
-    {
-        "Policy": str,
-        "RevisionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetProvisionedConcurrencyConfigResponseTypeDef = TypedDict(
-    "GetProvisionedConcurrencyConfigResponseTypeDef",
-    {
-        "RequestedProvisionedConcurrentExecutions": int,
-        "AvailableProvisionedConcurrentExecutions": int,
-        "AllocatedProvisionedConcurrentExecutions": int,
-        "Status": ProvisionedConcurrencyStatusEnumType,
-        "StatusReason": str,
-        "LastModified": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetRuntimeManagementConfigResponseTypeDef = TypedDict(
-    "GetRuntimeManagementConfigResponseTypeDef",
-    {
-        "UpdateRuntimeOn": UpdateRuntimeOnType,
-        "RuntimeVersionArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-InvocationResponseTypeDef = TypedDict(
-    "InvocationResponseTypeDef",
-    {
-        "StatusCode": int,
-        "FunctionError": str,
-        "LogResult": str,
-        "Payload": StreamingBody,
-        "ExecutedVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-InvokeAsyncResponseTypeDef = TypedDict(
-    "InvokeAsyncResponseTypeDef",
-    {
-        "Status": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListFunctionsByCodeSigningConfigResponseTypeDef = TypedDict(
-    "ListFunctionsByCodeSigningConfigResponseTypeDef",
-    {
-        "NextMarker": str,
-        "FunctionArns": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsResponseTypeDef = TypedDict(
-    "ListTagsResponseTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutFunctionCodeSigningConfigResponseTypeDef = TypedDict(
-    "PutFunctionCodeSigningConfigResponseTypeDef",
-    {
-        "CodeSigningConfigArn": str,
-        "FunctionName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutProvisionedConcurrencyConfigResponseTypeDef = TypedDict(
-    "PutProvisionedConcurrencyConfigResponseTypeDef",
-    {
-        "RequestedProvisionedConcurrentExecutions": int,
-        "AvailableProvisionedConcurrentExecutions": int,
-        "AllocatedProvisionedConcurrentExecutions": int,
-        "Status": ProvisionedConcurrencyStatusEnumType,
-        "StatusReason": str,
-        "LastModified": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutRuntimeManagementConfigResponseTypeDef = TypedDict(
-    "PutRuntimeManagementConfigResponseTypeDef",
-    {
-        "UpdateRuntimeOn": UpdateRuntimeOnType,
-        "FunctionArn": str,
-        "RuntimeVersionArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AliasConfigurationResponseMetadataTypeDef = TypedDict(
     "AliasConfigurationResponseMetadataTypeDef",
     {
         "AliasArn": str,
         "Name": str,
         "FunctionVersion": str,
         "Description": str,
         "RoutingConfig": AliasRoutingConfigurationTypeDef,
         "RevisionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AliasConfigurationTypeDef = TypedDict(
     "AliasConfigurationTypeDef",
     {
         "AliasArn": str,
@@ -1691,14 +1950,15 @@
     },
 )
 _OptionalCreateFunctionUrlConfigRequestRequestTypeDef = TypedDict(
     "_OptionalCreateFunctionUrlConfigRequestRequestTypeDef",
     {
         "Qualifier": str,
         "Cors": CorsTypeDef,
+        "InvokeMode": InvokeModeType,
     },
     total=False,
 )
 
 
 class CreateFunctionUrlConfigRequestRequestTypeDef(
     _RequiredCreateFunctionUrlConfigRequestRequestTypeDef,
@@ -1711,15 +1971,16 @@
     "CreateFunctionUrlConfigResponseTypeDef",
     {
         "FunctionUrl": str,
         "FunctionArn": str,
         "AuthType": FunctionUrlAuthTypeType,
         "Cors": CorsTypeDef,
         "CreationTime": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "InvokeMode": InvokeModeType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredFunctionUrlConfigTypeDef = TypedDict(
     "_RequiredFunctionUrlConfigTypeDef",
     {
         "FunctionUrl": str,
@@ -1729,14 +1990,15 @@
         "AuthType": FunctionUrlAuthTypeType,
     },
 )
 _OptionalFunctionUrlConfigTypeDef = TypedDict(
     "_OptionalFunctionUrlConfigTypeDef",
     {
         "Cors": CorsTypeDef,
+        "InvokeMode": InvokeModeType,
     },
     total=False,
 )
 
 
 class FunctionUrlConfigTypeDef(
     _RequiredFunctionUrlConfigTypeDef, _OptionalFunctionUrlConfigTypeDef
@@ -1749,15 +2011,16 @@
     {
         "FunctionUrl": str,
         "FunctionArn": str,
         "AuthType": FunctionUrlAuthTypeType,
         "Cors": CorsTypeDef,
         "CreationTime": str,
         "LastModifiedTime": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "InvokeMode": InvokeModeType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateFunctionUrlConfigRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateFunctionUrlConfigRequestRequestTypeDef",
     {
         "FunctionName": str,
@@ -1765,14 +2028,15 @@
 )
 _OptionalUpdateFunctionUrlConfigRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateFunctionUrlConfigRequestRequestTypeDef",
     {
         "Qualifier": str,
         "AuthType": FunctionUrlAuthTypeType,
         "Cors": CorsTypeDef,
+        "InvokeMode": InvokeModeType,
     },
     total=False,
 )
 
 
 class UpdateFunctionUrlConfigRequestRequestTypeDef(
     _RequiredUpdateFunctionUrlConfigRequestRequestTypeDef,
@@ -1786,15 +2050,16 @@
     {
         "FunctionUrl": str,
         "FunctionArn": str,
         "AuthType": FunctionUrlAuthTypeType,
         "Cors": CorsTypeDef,
         "CreationTime": str,
         "LastModifiedTime": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "InvokeMode": InvokeModeType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateFunctionRequestRequestTypeDef = TypedDict(
     "_RequiredCreateFunctionRequestRequestTypeDef",
     {
         "FunctionName": str,
@@ -2046,15 +2311,15 @@
         "LayerVersionArn": str,
         "Description": str,
         "CreatedDate": str,
         "Version": int,
         "CompatibleRuntimes": List[RuntimeType],
         "LicenseInfo": str,
         "CompatibleArchitectures": List[ArchitectureType],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PublishLayerVersionResponseTypeDef = TypedDict(
     "PublishLayerVersionResponseTypeDef",
     {
         "Content": LayerVersionContentOutputTypeDef,
@@ -2062,27 +2327,36 @@
         "LayerVersionArn": str,
         "Description": str,
         "CreatedDate": str,
         "Version": int,
         "CompatibleRuntimes": List[RuntimeType],
         "LicenseInfo": str,
         "CompatibleArchitectures": List[ArchitectureType],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ImageConfigResponseTypeDef = TypedDict(
     "ImageConfigResponseTypeDef",
     {
         "ImageConfig": ImageConfigTypeDef,
         "Error": ImageConfigErrorTypeDef,
     },
     total=False,
 )
 
+InvokeWithResponseStreamResponseEventTypeDef = TypedDict(
+    "InvokeWithResponseStreamResponseEventTypeDef",
+    {
+        "PayloadChunk": InvokeResponseStreamUpdateTypeDef,
+        "InvokeComplete": InvokeWithResponseStreamCompleteEventTypeDef,
+    },
+    total=False,
+)
+
 _RequiredPublishLayerVersionRequestRequestTypeDef = TypedDict(
     "_RequiredPublishLayerVersionRequestRequestTypeDef",
     {
         "LayerName": str,
         "Content": LayerVersionContentInputTypeDef,
     },
 )
@@ -2116,219 +2390,24 @@
 )
 
 ListLayerVersionsResponseTypeDef = TypedDict(
     "ListLayerVersionsResponseTypeDef",
     {
         "NextMarker": str,
         "LayerVersions": List[LayerVersionsListItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredListAliasesRequestListAliasesPaginateTypeDef = TypedDict(
-    "_RequiredListAliasesRequestListAliasesPaginateTypeDef",
-    {
-        "FunctionName": str,
-    },
-)
-_OptionalListAliasesRequestListAliasesPaginateTypeDef = TypedDict(
-    "_OptionalListAliasesRequestListAliasesPaginateTypeDef",
-    {
-        "FunctionVersion": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListAliasesRequestListAliasesPaginateTypeDef(
-    _RequiredListAliasesRequestListAliasesPaginateTypeDef,
-    _OptionalListAliasesRequestListAliasesPaginateTypeDef,
-):
-    pass
-
-
-ListCodeSigningConfigsRequestListCodeSigningConfigsPaginateTypeDef = TypedDict(
-    "ListCodeSigningConfigsRequestListCodeSigningConfigsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListEventSourceMappingsRequestListEventSourceMappingsPaginateTypeDef = TypedDict(
-    "ListEventSourceMappingsRequestListEventSourceMappingsPaginateTypeDef",
-    {
-        "EventSourceArn": str,
-        "FunctionName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListFunctionEventInvokeConfigsRequestListFunctionEventInvokeConfigsPaginateTypeDef = TypedDict(
-    "_RequiredListFunctionEventInvokeConfigsRequestListFunctionEventInvokeConfigsPaginateTypeDef",
-    {
-        "FunctionName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalListFunctionEventInvokeConfigsRequestListFunctionEventInvokeConfigsPaginateTypeDef = TypedDict(
-    "_OptionalListFunctionEventInvokeConfigsRequestListFunctionEventInvokeConfigsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListFunctionEventInvokeConfigsRequestListFunctionEventInvokeConfigsPaginateTypeDef(
-    _RequiredListFunctionEventInvokeConfigsRequestListFunctionEventInvokeConfigsPaginateTypeDef,
-    _OptionalListFunctionEventInvokeConfigsRequestListFunctionEventInvokeConfigsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListFunctionUrlConfigsRequestListFunctionUrlConfigsPaginateTypeDef = TypedDict(
-    "_RequiredListFunctionUrlConfigsRequestListFunctionUrlConfigsPaginateTypeDef",
-    {
-        "FunctionName": str,
-    },
-)
-_OptionalListFunctionUrlConfigsRequestListFunctionUrlConfigsPaginateTypeDef = TypedDict(
-    "_OptionalListFunctionUrlConfigsRequestListFunctionUrlConfigsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListFunctionUrlConfigsRequestListFunctionUrlConfigsPaginateTypeDef(
-    _RequiredListFunctionUrlConfigsRequestListFunctionUrlConfigsPaginateTypeDef,
-    _OptionalListFunctionUrlConfigsRequestListFunctionUrlConfigsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListFunctionsByCodeSigningConfigRequestListFunctionsByCodeSigningConfigPaginateTypeDef = TypedDict(
-    "_RequiredListFunctionsByCodeSigningConfigRequestListFunctionsByCodeSigningConfigPaginateTypeDef",
-    {
-        "CodeSigningConfigArn": str,
-    },
-)
-_OptionalListFunctionsByCodeSigningConfigRequestListFunctionsByCodeSigningConfigPaginateTypeDef = TypedDict(
-    "_OptionalListFunctionsByCodeSigningConfigRequestListFunctionsByCodeSigningConfigPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListFunctionsByCodeSigningConfigRequestListFunctionsByCodeSigningConfigPaginateTypeDef(
-    _RequiredListFunctionsByCodeSigningConfigRequestListFunctionsByCodeSigningConfigPaginateTypeDef,
-    _OptionalListFunctionsByCodeSigningConfigRequestListFunctionsByCodeSigningConfigPaginateTypeDef,
-):
-    pass
-
-
-ListFunctionsRequestListFunctionsPaginateTypeDef = TypedDict(
-    "ListFunctionsRequestListFunctionsPaginateTypeDef",
-    {
-        "MasterRegion": str,
-        "FunctionVersion": Literal["ALL"],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListLayerVersionsRequestListLayerVersionsPaginateTypeDef = TypedDict(
-    "_RequiredListLayerVersionsRequestListLayerVersionsPaginateTypeDef",
-    {
-        "LayerName": str,
-    },
-)
-_OptionalListLayerVersionsRequestListLayerVersionsPaginateTypeDef = TypedDict(
-    "_OptionalListLayerVersionsRequestListLayerVersionsPaginateTypeDef",
-    {
-        "CompatibleRuntime": RuntimeType,
-        "CompatibleArchitecture": ArchitectureType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListLayerVersionsRequestListLayerVersionsPaginateTypeDef(
-    _RequiredListLayerVersionsRequestListLayerVersionsPaginateTypeDef,
-    _OptionalListLayerVersionsRequestListLayerVersionsPaginateTypeDef,
-):
-    pass
-
-
-ListLayersRequestListLayersPaginateTypeDef = TypedDict(
-    "ListLayersRequestListLayersPaginateTypeDef",
-    {
-        "CompatibleRuntime": RuntimeType,
-        "CompatibleArchitecture": ArchitectureType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListProvisionedConcurrencyConfigsRequestListProvisionedConcurrencyConfigsPaginateTypeDef = TypedDict(
-    "_RequiredListProvisionedConcurrencyConfigsRequestListProvisionedConcurrencyConfigsPaginateTypeDef",
-    {
-        "FunctionName": str,
-    },
-)
-_OptionalListProvisionedConcurrencyConfigsRequestListProvisionedConcurrencyConfigsPaginateTypeDef = TypedDict(
-    "_OptionalListProvisionedConcurrencyConfigsRequestListProvisionedConcurrencyConfigsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListProvisionedConcurrencyConfigsRequestListProvisionedConcurrencyConfigsPaginateTypeDef(
-    _RequiredListProvisionedConcurrencyConfigsRequestListProvisionedConcurrencyConfigsPaginateTypeDef,
-    _OptionalListProvisionedConcurrencyConfigsRequestListProvisionedConcurrencyConfigsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListVersionsByFunctionRequestListVersionsByFunctionPaginateTypeDef = TypedDict(
-    "_RequiredListVersionsByFunctionRequestListVersionsByFunctionPaginateTypeDef",
-    {
-        "FunctionName": str,
-    },
-)
-_OptionalListVersionsByFunctionRequestListVersionsByFunctionPaginateTypeDef = TypedDict(
-    "_OptionalListVersionsByFunctionRequestListVersionsByFunctionPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListVersionsByFunctionRequestListVersionsByFunctionPaginateTypeDef(
-    _RequiredListVersionsByFunctionRequestListVersionsByFunctionPaginateTypeDef,
-    _OptionalListVersionsByFunctionRequestListVersionsByFunctionPaginateTypeDef,
-):
-    pass
-
 
 ListProvisionedConcurrencyConfigsResponseTypeDef = TypedDict(
     "ListProvisionedConcurrencyConfigsResponseTypeDef",
     {
         "ProvisionedConcurrencyConfigs": List[ProvisionedConcurrencyConfigListItemTypeDef],
         "NextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RuntimeVersionConfigTypeDef = TypedDict(
     "RuntimeVersionConfigTypeDef",
     {
         "RuntimeVersionArn": str,
@@ -2338,69 +2417,69 @@
 )
 
 ListAliasesResponseTypeDef = TypedDict(
     "ListAliasesResponseTypeDef",
     {
         "NextMarker": str,
         "Aliases": List[AliasConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateCodeSigningConfigResponseTypeDef = TypedDict(
     "CreateCodeSigningConfigResponseTypeDef",
     {
         "CodeSigningConfig": CodeSigningConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCodeSigningConfigResponseTypeDef = TypedDict(
     "GetCodeSigningConfigResponseTypeDef",
     {
         "CodeSigningConfig": CodeSigningConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCodeSigningConfigsResponseTypeDef = TypedDict(
     "ListCodeSigningConfigsResponseTypeDef",
     {
         "NextMarker": str,
         "CodeSigningConfigs": List[CodeSigningConfigTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateCodeSigningConfigResponseTypeDef = TypedDict(
     "UpdateCodeSigningConfigResponseTypeDef",
     {
         "CodeSigningConfig": CodeSigningConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListFunctionUrlConfigsResponseTypeDef = TypedDict(
     "ListFunctionUrlConfigsResponseTypeDef",
     {
         "FunctionUrlConfigs": List[FunctionUrlConfigTypeDef],
         "NextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FunctionEventInvokeConfigResponseMetadataTypeDef = TypedDict(
     "FunctionEventInvokeConfigResponseMetadataTypeDef",
     {
         "LastModified": datetime,
         "FunctionArn": str,
         "MaximumRetryAttempts": int,
         "MaximumEventAgeInSeconds": int,
         "DestinationConfig": DestinationConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FunctionEventInvokeConfigTypeDef = TypedDict(
     "FunctionEventInvokeConfigTypeDef",
     {
         "LastModified": datetime,
@@ -2488,14 +2567,15 @@
         "Queues": Sequence[str],
         "SourceAccessConfigurations": Sequence[SourceAccessConfigurationTypeDef],
         "SelfManagedEventSource": SelfManagedEventSourceTypeDef,
         "FunctionResponseTypes": Sequence[Literal["ReportBatchItemFailures"]],
         "AmazonManagedKafkaEventSourceConfig": AmazonManagedKafkaEventSourceConfigTypeDef,
         "SelfManagedKafkaEventSourceConfig": SelfManagedKafkaEventSourceConfigTypeDef,
         "ScalingConfig": ScalingConfigTypeDef,
+        "DocumentDBEventSourceConfig": DocumentDBEventSourceConfigTypeDef,
     },
     total=False,
 )
 
 
 class CreateEventSourceMappingRequestRequestTypeDef(
     _RequiredCreateEventSourceMappingRequestRequestTypeDef,
@@ -2529,15 +2609,16 @@
         "BisectBatchOnFunctionError": bool,
         "MaximumRetryAttempts": int,
         "TumblingWindowInSeconds": int,
         "FunctionResponseTypes": List[Literal["ReportBatchItemFailures"]],
         "AmazonManagedKafkaEventSourceConfig": AmazonManagedKafkaEventSourceConfigTypeDef,
         "SelfManagedKafkaEventSourceConfig": SelfManagedKafkaEventSourceConfigTypeDef,
         "ScalingConfig": ScalingConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "DocumentDBEventSourceConfig": DocumentDBEventSourceConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EventSourceMappingConfigurationTypeDef = TypedDict(
     "EventSourceMappingConfigurationTypeDef",
     {
         "UUID": str,
@@ -2562,14 +2643,15 @@
         "BisectBatchOnFunctionError": bool,
         "MaximumRetryAttempts": int,
         "TumblingWindowInSeconds": int,
         "FunctionResponseTypes": List[Literal["ReportBatchItemFailures"]],
         "AmazonManagedKafkaEventSourceConfig": AmazonManagedKafkaEventSourceConfigTypeDef,
         "SelfManagedKafkaEventSourceConfig": SelfManagedKafkaEventSourceConfigTypeDef,
         "ScalingConfig": ScalingConfigTypeDef,
+        "DocumentDBEventSourceConfig": DocumentDBEventSourceConfigTypeDef,
     },
     total=False,
 )
 
 _RequiredUpdateEventSourceMappingRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateEventSourceMappingRequestRequestTypeDef",
     {
@@ -2589,32 +2671,44 @@
         "BisectBatchOnFunctionError": bool,
         "MaximumRetryAttempts": int,
         "ParallelizationFactor": int,
         "SourceAccessConfigurations": Sequence[SourceAccessConfigurationTypeDef],
         "TumblingWindowInSeconds": int,
         "FunctionResponseTypes": Sequence[Literal["ReportBatchItemFailures"]],
         "ScalingConfig": ScalingConfigTypeDef,
+        "DocumentDBEventSourceConfig": DocumentDBEventSourceConfigTypeDef,
     },
     total=False,
 )
 
 
 class UpdateEventSourceMappingRequestRequestTypeDef(
     _RequiredUpdateEventSourceMappingRequestRequestTypeDef,
     _OptionalUpdateEventSourceMappingRequestRequestTypeDef,
 ):
     pass
 
 
+InvokeWithResponseStreamResponseTypeDef = TypedDict(
+    "InvokeWithResponseStreamResponseTypeDef",
+    {
+        "StatusCode": int,
+        "ExecutedVersion": str,
+        "EventStream": InvokeWithResponseStreamResponseEventTypeDef,
+        "ResponseStreamContentType": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListLayersResponseTypeDef = TypedDict(
     "ListLayersResponseTypeDef",
     {
         "NextMarker": str,
         "Layers": List[LayersListItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FunctionConfigurationResponseMetadataTypeDef = TypedDict(
     "FunctionConfigurationResponseMetadataTypeDef",
     {
         "FunctionName": str,
@@ -2648,15 +2742,15 @@
         "ImageConfigResponse": ImageConfigResponseTypeDef,
         "SigningProfileVersionArn": str,
         "SigningJobArn": str,
         "Architectures": List[ArchitectureType],
         "EphemeralStorage": EphemeralStorageTypeDef,
         "SnapStart": SnapStartResponseTypeDef,
         "RuntimeVersionConfig": RuntimeVersionConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FunctionConfigurationTypeDef = TypedDict(
     "FunctionConfigurationTypeDef",
     {
         "FunctionName": str,
@@ -2699,48 +2793,48 @@
 )
 
 ListFunctionEventInvokeConfigsResponseTypeDef = TypedDict(
     "ListFunctionEventInvokeConfigsResponseTypeDef",
     {
         "FunctionEventInvokeConfigs": List[FunctionEventInvokeConfigTypeDef],
         "NextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEventSourceMappingsResponseTypeDef = TypedDict(
     "ListEventSourceMappingsResponseTypeDef",
     {
         "NextMarker": str,
         "EventSourceMappings": List[EventSourceMappingConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetFunctionResponseTypeDef = TypedDict(
     "GetFunctionResponseTypeDef",
     {
         "Configuration": FunctionConfigurationTypeDef,
         "Code": FunctionCodeLocationTypeDef,
         "Tags": Dict[str, str],
         "Concurrency": ConcurrencyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListFunctionsResponseTypeDef = TypedDict(
     "ListFunctionsResponseTypeDef",
     {
         "NextMarker": str,
         "Functions": List[FunctionConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVersionsByFunctionResponseTypeDef = TypedDict(
     "ListVersionsByFunctionResponseTypeDef",
     {
         "NextMarker": str,
         "Versions": List[FunctionConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-lambda-2.5.0.post1/types_aiobotocore_lambda/type_defs.pyi` & `types-aiobotocore-lambda-2.5.1/types_aiobotocore_lambda/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -17,21 +17,24 @@
 
 from aiobotocore.response import StreamingBody
 
 from .literals import (
     ArchitectureType,
     CodeSigningPolicyType,
     EventSourcePositionType,
+    FullDocumentType,
     FunctionUrlAuthTypeType,
     InvocationTypeType,
+    InvokeModeType,
     LastUpdateStatusReasonCodeType,
     LastUpdateStatusType,
     LogTypeType,
     PackageTypeType,
     ProvisionedConcurrencyStatusEnumType,
+    ResponseStreamingInvocationTypeType,
     RuntimeType,
     SnapStartApplyOnType,
     SnapStartOptimizationStatusType,
     SourceAccessTypeType,
     StateReasonCodeType,
     StateType,
     TracingModeType,
@@ -47,22 +50,25 @@
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AccountLimitTypeDef",
     "AccountUsageTypeDef",
     "AddLayerVersionPermissionRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "AddLayerVersionPermissionResponseTypeDef",
     "AddPermissionRequestRequestTypeDef",
+    "AddPermissionResponseTypeDef",
     "AliasRoutingConfigurationTypeDef",
     "AllowedPublishersTypeDef",
     "AmazonManagedKafkaEventSourceConfigTypeDef",
     "CodeSigningPoliciesTypeDef",
+    "ConcurrencyResponseMetadataTypeDef",
     "ConcurrencyTypeDef",
     "CorsTypeDef",
+    "DocumentDBEventSourceConfigTypeDef",
     "ScalingConfigTypeDef",
     "SelfManagedEventSourceTypeDef",
     "SelfManagedKafkaEventSourceConfigTypeDef",
     "SourceAccessConfigurationTypeDef",
     "DeadLetterConfigTypeDef",
     "EnvironmentTypeDef",
     "EphemeralStorageTypeDef",
@@ -80,86 +86,98 @@
     "DeleteFunctionEventInvokeConfigRequestRequestTypeDef",
     "DeleteFunctionRequestRequestTypeDef",
     "DeleteFunctionUrlConfigRequestRequestTypeDef",
     "DeleteLayerVersionRequestRequestTypeDef",
     "DeleteProvisionedConcurrencyConfigRequestRequestTypeDef",
     "OnFailureTypeDef",
     "OnSuccessTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EnvironmentErrorTypeDef",
     "FilterTypeDef",
     "FunctionCodeLocationTypeDef",
     "LayerTypeDef",
     "SnapStartResponseTypeDef",
     "TracingConfigResponseTypeDef",
     "VpcConfigResponseTypeDef",
     "GetAliasRequestRequestTypeDef",
     "GetCodeSigningConfigRequestRequestTypeDef",
     "GetEventSourceMappingRequestRequestTypeDef",
     "GetFunctionCodeSigningConfigRequestRequestTypeDef",
+    "GetFunctionCodeSigningConfigResponseTypeDef",
     "GetFunctionConcurrencyRequestRequestTypeDef",
+    "GetFunctionConcurrencyResponseTypeDef",
     "WaiterConfigTypeDef",
     "GetFunctionConfigurationRequestRequestTypeDef",
     "GetFunctionEventInvokeConfigRequestRequestTypeDef",
     "GetFunctionRequestRequestTypeDef",
     "GetFunctionUrlConfigRequestRequestTypeDef",
     "GetLayerVersionByArnRequestRequestTypeDef",
     "GetLayerVersionPolicyRequestRequestTypeDef",
+    "GetLayerVersionPolicyResponseTypeDef",
     "GetLayerVersionRequestRequestTypeDef",
     "LayerVersionContentOutputTypeDef",
     "GetPolicyRequestRequestTypeDef",
+    "GetPolicyResponseTypeDef",
     "GetProvisionedConcurrencyConfigRequestRequestTypeDef",
+    "GetProvisionedConcurrencyConfigResponseTypeDef",
     "GetRuntimeManagementConfigRequestRequestTypeDef",
+    "GetRuntimeManagementConfigResponseTypeDef",
     "ImageConfigErrorTypeDef",
     "InvocationRequestRequestTypeDef",
+    "InvocationResponseTypeDef",
     "InvokeAsyncRequestRequestTypeDef",
+    "InvokeAsyncResponseTypeDef",
+    "InvokeResponseStreamUpdateTypeDef",
+    "InvokeWithResponseStreamCompleteEventTypeDef",
+    "InvokeWithResponseStreamRequestRequestTypeDef",
     "LayerVersionContentInputTypeDef",
     "LayerVersionsListItemTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListAliasesRequestListAliasesPaginateTypeDef",
     "ListAliasesRequestRequestTypeDef",
+    "ListCodeSigningConfigsRequestListCodeSigningConfigsPaginateTypeDef",
     "ListCodeSigningConfigsRequestRequestTypeDef",
+    "ListEventSourceMappingsRequestListEventSourceMappingsPaginateTypeDef",
     "ListEventSourceMappingsRequestRequestTypeDef",
+    "ListFunctionEventInvokeConfigsRequestListFunctionEventInvokeConfigsPaginateTypeDef",
     "ListFunctionEventInvokeConfigsRequestRequestTypeDef",
+    "ListFunctionUrlConfigsRequestListFunctionUrlConfigsPaginateTypeDef",
     "ListFunctionUrlConfigsRequestRequestTypeDef",
+    "ListFunctionsByCodeSigningConfigRequestListFunctionsByCodeSigningConfigPaginateTypeDef",
     "ListFunctionsByCodeSigningConfigRequestRequestTypeDef",
+    "ListFunctionsByCodeSigningConfigResponseTypeDef",
+    "ListFunctionsRequestListFunctionsPaginateTypeDef",
     "ListFunctionsRequestRequestTypeDef",
+    "ListLayerVersionsRequestListLayerVersionsPaginateTypeDef",
     "ListLayerVersionsRequestRequestTypeDef",
+    "ListLayersRequestListLayersPaginateTypeDef",
     "ListLayersRequestRequestTypeDef",
+    "ListProvisionedConcurrencyConfigsRequestListProvisionedConcurrencyConfigsPaginateTypeDef",
     "ListProvisionedConcurrencyConfigsRequestRequestTypeDef",
     "ProvisionedConcurrencyConfigListItemTypeDef",
     "ListTagsRequestRequestTypeDef",
+    "ListTagsResponseTypeDef",
+    "ListVersionsByFunctionRequestListVersionsByFunctionPaginateTypeDef",
     "ListVersionsByFunctionRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "PublishVersionRequestRequestTypeDef",
     "PutFunctionCodeSigningConfigRequestRequestTypeDef",
+    "PutFunctionCodeSigningConfigResponseTypeDef",
     "PutFunctionConcurrencyRequestRequestTypeDef",
     "PutProvisionedConcurrencyConfigRequestRequestTypeDef",
+    "PutProvisionedConcurrencyConfigResponseTypeDef",
     "PutRuntimeManagementConfigRequestRequestTypeDef",
+    "PutRuntimeManagementConfigResponseTypeDef",
     "RemoveLayerVersionPermissionRequestRequestTypeDef",
     "RemovePermissionRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "RuntimeVersionErrorTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateFunctionCodeRequestRequestTypeDef",
-    "AddLayerVersionPermissionResponseTypeDef",
-    "AddPermissionResponseTypeDef",
-    "ConcurrencyResponseMetadataTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "GetAccountSettingsResponseTypeDef",
-    "GetFunctionCodeSigningConfigResponseTypeDef",
-    "GetFunctionConcurrencyResponseTypeDef",
-    "GetLayerVersionPolicyResponseTypeDef",
-    "GetPolicyResponseTypeDef",
-    "GetProvisionedConcurrencyConfigResponseTypeDef",
-    "GetRuntimeManagementConfigResponseTypeDef",
-    "InvocationResponseTypeDef",
-    "InvokeAsyncResponseTypeDef",
-    "ListFunctionsByCodeSigningConfigResponseTypeDef",
-    "ListTagsResponseTypeDef",
-    "PutFunctionCodeSigningConfigResponseTypeDef",
-    "PutProvisionedConcurrencyConfigResponseTypeDef",
-    "PutRuntimeManagementConfigResponseTypeDef",
     "AliasConfigurationResponseMetadataTypeDef",
     "AliasConfigurationTypeDef",
     "CreateAliasRequestRequestTypeDef",
     "UpdateAliasRequestRequestTypeDef",
     "CodeSigningConfigTypeDef",
     "CreateCodeSigningConfigRequestRequestTypeDef",
     "UpdateCodeSigningConfigRequestRequestTypeDef",
@@ -179,28 +197,18 @@
     "GetFunctionConfigurationRequestPublishedVersionActiveWaitTypeDef",
     "GetFunctionRequestFunctionActiveV2WaitTypeDef",
     "GetFunctionRequestFunctionExistsWaitTypeDef",
     "GetFunctionRequestFunctionUpdatedV2WaitTypeDef",
     "GetLayerVersionResponseTypeDef",
     "PublishLayerVersionResponseTypeDef",
     "ImageConfigResponseTypeDef",
+    "InvokeWithResponseStreamResponseEventTypeDef",
     "PublishLayerVersionRequestRequestTypeDef",
     "LayersListItemTypeDef",
     "ListLayerVersionsResponseTypeDef",
-    "ListAliasesRequestListAliasesPaginateTypeDef",
-    "ListCodeSigningConfigsRequestListCodeSigningConfigsPaginateTypeDef",
-    "ListEventSourceMappingsRequestListEventSourceMappingsPaginateTypeDef",
-    "ListFunctionEventInvokeConfigsRequestListFunctionEventInvokeConfigsPaginateTypeDef",
-    "ListFunctionUrlConfigsRequestListFunctionUrlConfigsPaginateTypeDef",
-    "ListFunctionsByCodeSigningConfigRequestListFunctionsByCodeSigningConfigPaginateTypeDef",
-    "ListFunctionsRequestListFunctionsPaginateTypeDef",
-    "ListLayerVersionsRequestListLayerVersionsPaginateTypeDef",
-    "ListLayersRequestListLayersPaginateTypeDef",
-    "ListProvisionedConcurrencyConfigsRequestListProvisionedConcurrencyConfigsPaginateTypeDef",
-    "ListVersionsByFunctionRequestListVersionsByFunctionPaginateTypeDef",
     "ListProvisionedConcurrencyConfigsResponseTypeDef",
     "RuntimeVersionConfigTypeDef",
     "ListAliasesResponseTypeDef",
     "CreateCodeSigningConfigResponseTypeDef",
     "GetCodeSigningConfigResponseTypeDef",
     "ListCodeSigningConfigsResponseTypeDef",
     "UpdateCodeSigningConfigResponseTypeDef",
@@ -209,14 +217,15 @@
     "FunctionEventInvokeConfigTypeDef",
     "PutFunctionEventInvokeConfigRequestRequestTypeDef",
     "UpdateFunctionEventInvokeConfigRequestRequestTypeDef",
     "CreateEventSourceMappingRequestRequestTypeDef",
     "EventSourceMappingConfigurationResponseMetadataTypeDef",
     "EventSourceMappingConfigurationTypeDef",
     "UpdateEventSourceMappingRequestRequestTypeDef",
+    "InvokeWithResponseStreamResponseTypeDef",
     "ListLayersResponseTypeDef",
     "FunctionConfigurationResponseMetadataTypeDef",
     "FunctionConfigurationTypeDef",
     "ListFunctionEventInvokeConfigsResponseTypeDef",
     "ListEventSourceMappingsResponseTypeDef",
     "GetFunctionResponseTypeDef",
     "ListFunctionsResponseTypeDef",
@@ -265,22 +274,20 @@
 
 class AddLayerVersionPermissionRequestRequestTypeDef(
     _RequiredAddLayerVersionPermissionRequestRequestTypeDef,
     _OptionalAddLayerVersionPermissionRequestRequestTypeDef,
 ):
     pass
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+AddLayerVersionPermissionResponseTypeDef = TypedDict(
+    "AddLayerVersionPermissionResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "Statement": str,
+        "RevisionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredAddPermissionRequestRequestTypeDef = TypedDict(
     "_RequiredAddPermissionRequestRequestTypeDef",
     {
         "FunctionName": str,
@@ -304,14 +311,22 @@
 )
 
 class AddPermissionRequestRequestTypeDef(
     _RequiredAddPermissionRequestRequestTypeDef, _OptionalAddPermissionRequestRequestTypeDef
 ):
     pass
 
+AddPermissionResponseTypeDef = TypedDict(
+    "AddPermissionResponseTypeDef",
+    {
+        "Statement": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AliasRoutingConfigurationTypeDef = TypedDict(
     "AliasRoutingConfigurationTypeDef",
     {
         "AdditionalVersionWeights": Mapping[str, float],
     },
     total=False,
 )
@@ -335,14 +350,22 @@
     "CodeSigningPoliciesTypeDef",
     {
         "UntrustedArtifactOnDeployment": CodeSigningPolicyType,
     },
     total=False,
 )
 
+ConcurrencyResponseMetadataTypeDef = TypedDict(
+    "ConcurrencyResponseMetadataTypeDef",
+    {
+        "ReservedConcurrentExecutions": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ConcurrencyTypeDef = TypedDict(
     "ConcurrencyTypeDef",
     {
         "ReservedConcurrentExecutions": int,
     },
     total=False,
 )
@@ -356,14 +379,24 @@
         "AllowOrigins": Sequence[str],
         "ExposeHeaders": Sequence[str],
         "MaxAge": int,
     },
     total=False,
 )
 
+DocumentDBEventSourceConfigTypeDef = TypedDict(
+    "DocumentDBEventSourceConfigTypeDef",
+    {
+        "DatabaseName": str,
+        "CollectionName": str,
+        "FullDocument": FullDocumentType,
+    },
+    total=False,
+)
+
 ScalingConfigTypeDef = TypedDict(
     "ScalingConfigTypeDef",
     {
         "MaximumConcurrency": int,
     },
     total=False,
 )
@@ -594,14 +627,21 @@
     "OnSuccessTypeDef",
     {
         "Destination": str,
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
 EnvironmentErrorTypeDef = TypedDict(
     "EnvironmentErrorTypeDef",
     {
         "ErrorCode": str,
         "Message": str,
     },
     total=False,
@@ -689,21 +729,38 @@
 GetFunctionCodeSigningConfigRequestRequestTypeDef = TypedDict(
     "GetFunctionCodeSigningConfigRequestRequestTypeDef",
     {
         "FunctionName": str,
     },
 )
 
+GetFunctionCodeSigningConfigResponseTypeDef = TypedDict(
+    "GetFunctionCodeSigningConfigResponseTypeDef",
+    {
+        "CodeSigningConfigArn": str,
+        "FunctionName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetFunctionConcurrencyRequestRequestTypeDef = TypedDict(
     "GetFunctionConcurrencyRequestRequestTypeDef",
     {
         "FunctionName": str,
     },
 )
 
+GetFunctionConcurrencyResponseTypeDef = TypedDict(
+    "GetFunctionConcurrencyResponseTypeDef",
+    {
+        "ReservedConcurrentExecutions": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 WaiterConfigTypeDef = TypedDict(
     "WaiterConfigTypeDef",
     {
         "Delay": int,
         "MaxAttempts": int,
     },
     total=False,
@@ -799,14 +856,23 @@
     "GetLayerVersionPolicyRequestRequestTypeDef",
     {
         "LayerName": str,
         "VersionNumber": int,
     },
 )
 
+GetLayerVersionPolicyResponseTypeDef = TypedDict(
+    "GetLayerVersionPolicyResponseTypeDef",
+    {
+        "Policy": str,
+        "RevisionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetLayerVersionRequestRequestTypeDef = TypedDict(
     "GetLayerVersionRequestRequestTypeDef",
     {
         "LayerName": str,
         "VersionNumber": int,
     },
 )
@@ -838,22 +904,44 @@
 )
 
 class GetPolicyRequestRequestTypeDef(
     _RequiredGetPolicyRequestRequestTypeDef, _OptionalGetPolicyRequestRequestTypeDef
 ):
     pass
 
+GetPolicyResponseTypeDef = TypedDict(
+    "GetPolicyResponseTypeDef",
+    {
+        "Policy": str,
+        "RevisionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetProvisionedConcurrencyConfigRequestRequestTypeDef = TypedDict(
     "GetProvisionedConcurrencyConfigRequestRequestTypeDef",
     {
         "FunctionName": str,
         "Qualifier": str,
     },
 )
 
+GetProvisionedConcurrencyConfigResponseTypeDef = TypedDict(
+    "GetProvisionedConcurrencyConfigResponseTypeDef",
+    {
+        "RequestedProvisionedConcurrentExecutions": int,
+        "AvailableProvisionedConcurrentExecutions": int,
+        "AllocatedProvisionedConcurrentExecutions": int,
+        "Status": ProvisionedConcurrencyStatusEnumType,
+        "StatusReason": str,
+        "LastModified": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetRuntimeManagementConfigRequestRequestTypeDef = TypedDict(
     "_RequiredGetRuntimeManagementConfigRequestRequestTypeDef",
     {
         "FunctionName": str,
     },
 )
 _OptionalGetRuntimeManagementConfigRequestRequestTypeDef = TypedDict(
@@ -866,14 +954,24 @@
 
 class GetRuntimeManagementConfigRequestRequestTypeDef(
     _RequiredGetRuntimeManagementConfigRequestRequestTypeDef,
     _OptionalGetRuntimeManagementConfigRequestRequestTypeDef,
 ):
     pass
 
+GetRuntimeManagementConfigResponseTypeDef = TypedDict(
+    "GetRuntimeManagementConfigResponseTypeDef",
+    {
+        "UpdateRuntimeOn": UpdateRuntimeOnType,
+        "RuntimeVersionArn": str,
+        "FunctionArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ImageConfigErrorTypeDef = TypedDict(
     "ImageConfigErrorTypeDef",
     {
         "ErrorCode": str,
         "Message": str,
     },
     total=False,
@@ -898,22 +996,84 @@
 )
 
 class InvocationRequestRequestTypeDef(
     _RequiredInvocationRequestRequestTypeDef, _OptionalInvocationRequestRequestTypeDef
 ):
     pass
 
+InvocationResponseTypeDef = TypedDict(
+    "InvocationResponseTypeDef",
+    {
+        "StatusCode": int,
+        "FunctionError": str,
+        "LogResult": str,
+        "Payload": StreamingBody,
+        "ExecutedVersion": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 InvokeAsyncRequestRequestTypeDef = TypedDict(
     "InvokeAsyncRequestRequestTypeDef",
     {
         "FunctionName": str,
         "InvokeArgs": Union[str, bytes, IO[Any], StreamingBody],
     },
 )
 
+InvokeAsyncResponseTypeDef = TypedDict(
+    "InvokeAsyncResponseTypeDef",
+    {
+        "Status": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+InvokeResponseStreamUpdateTypeDef = TypedDict(
+    "InvokeResponseStreamUpdateTypeDef",
+    {
+        "Payload": bytes,
+    },
+    total=False,
+)
+
+InvokeWithResponseStreamCompleteEventTypeDef = TypedDict(
+    "InvokeWithResponseStreamCompleteEventTypeDef",
+    {
+        "ErrorCode": str,
+        "ErrorDetails": str,
+        "LogResult": str,
+    },
+    total=False,
+)
+
+_RequiredInvokeWithResponseStreamRequestRequestTypeDef = TypedDict(
+    "_RequiredInvokeWithResponseStreamRequestRequestTypeDef",
+    {
+        "FunctionName": str,
+    },
+)
+_OptionalInvokeWithResponseStreamRequestRequestTypeDef = TypedDict(
+    "_OptionalInvokeWithResponseStreamRequestRequestTypeDef",
+    {
+        "InvocationType": ResponseStreamingInvocationTypeType,
+        "LogType": LogTypeType,
+        "ClientContext": str,
+        "Qualifier": str,
+        "Payload": Union[str, bytes, IO[Any], StreamingBody],
+    },
+    total=False,
+)
+
+class InvokeWithResponseStreamRequestRequestTypeDef(
+    _RequiredInvokeWithResponseStreamRequestRequestTypeDef,
+    _OptionalInvokeWithResponseStreamRequestRequestTypeDef,
+):
+    pass
+
 LayerVersionContentInputTypeDef = TypedDict(
     "LayerVersionContentInputTypeDef",
     {
         "S3Bucket": str,
         "S3Key": str,
         "S3ObjectVersion": str,
         "ZipFile": Union[str, bytes, IO[Any], StreamingBody],
@@ -931,24 +1091,35 @@
         "CompatibleRuntimes": List[RuntimeType],
         "LicenseInfo": str,
         "CompatibleArchitectures": List[ArchitectureType],
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListAliasesRequestListAliasesPaginateTypeDef = TypedDict(
+    "_RequiredListAliasesRequestListAliasesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "FunctionName": str,
+    },
+)
+_OptionalListAliasesRequestListAliasesPaginateTypeDef = TypedDict(
+    "_OptionalListAliasesRequestListAliasesPaginateTypeDef",
+    {
+        "FunctionVersion": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListAliasesRequestListAliasesPaginateTypeDef(
+    _RequiredListAliasesRequestListAliasesPaginateTypeDef,
+    _OptionalListAliasesRequestListAliasesPaginateTypeDef,
+):
+    pass
+
 _RequiredListAliasesRequestRequestTypeDef = TypedDict(
     "_RequiredListAliasesRequestRequestTypeDef",
     {
         "FunctionName": str,
     },
 )
 _OptionalListAliasesRequestRequestTypeDef = TypedDict(
@@ -962,34 +1133,72 @@
 )
 
 class ListAliasesRequestRequestTypeDef(
     _RequiredListAliasesRequestRequestTypeDef, _OptionalListAliasesRequestRequestTypeDef
 ):
     pass
 
+ListCodeSigningConfigsRequestListCodeSigningConfigsPaginateTypeDef = TypedDict(
+    "ListCodeSigningConfigsRequestListCodeSigningConfigsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCodeSigningConfigsRequestRequestTypeDef = TypedDict(
     "ListCodeSigningConfigsRequestRequestTypeDef",
     {
         "Marker": str,
         "MaxItems": int,
     },
     total=False,
 )
 
+ListEventSourceMappingsRequestListEventSourceMappingsPaginateTypeDef = TypedDict(
+    "ListEventSourceMappingsRequestListEventSourceMappingsPaginateTypeDef",
+    {
+        "EventSourceArn": str,
+        "FunctionName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListEventSourceMappingsRequestRequestTypeDef = TypedDict(
     "ListEventSourceMappingsRequestRequestTypeDef",
     {
         "EventSourceArn": str,
         "FunctionName": str,
         "Marker": str,
         "MaxItems": int,
     },
     total=False,
 )
 
+_RequiredListFunctionEventInvokeConfigsRequestListFunctionEventInvokeConfigsPaginateTypeDef = TypedDict(
+    "_RequiredListFunctionEventInvokeConfigsRequestListFunctionEventInvokeConfigsPaginateTypeDef",
+    {
+        "FunctionName": str,
+    },
+)
+_OptionalListFunctionEventInvokeConfigsRequestListFunctionEventInvokeConfigsPaginateTypeDef = TypedDict(
+    "_OptionalListFunctionEventInvokeConfigsRequestListFunctionEventInvokeConfigsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListFunctionEventInvokeConfigsRequestListFunctionEventInvokeConfigsPaginateTypeDef(
+    _RequiredListFunctionEventInvokeConfigsRequestListFunctionEventInvokeConfigsPaginateTypeDef,
+    _OptionalListFunctionEventInvokeConfigsRequestListFunctionEventInvokeConfigsPaginateTypeDef,
+):
+    pass
+
 _RequiredListFunctionEventInvokeConfigsRequestRequestTypeDef = TypedDict(
     "_RequiredListFunctionEventInvokeConfigsRequestRequestTypeDef",
     {
         "FunctionName": str,
     },
 )
 _OptionalListFunctionEventInvokeConfigsRequestRequestTypeDef = TypedDict(
@@ -1003,14 +1212,34 @@
 
 class ListFunctionEventInvokeConfigsRequestRequestTypeDef(
     _RequiredListFunctionEventInvokeConfigsRequestRequestTypeDef,
     _OptionalListFunctionEventInvokeConfigsRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListFunctionUrlConfigsRequestListFunctionUrlConfigsPaginateTypeDef = TypedDict(
+    "_RequiredListFunctionUrlConfigsRequestListFunctionUrlConfigsPaginateTypeDef",
+    {
+        "FunctionName": str,
+    },
+)
+_OptionalListFunctionUrlConfigsRequestListFunctionUrlConfigsPaginateTypeDef = TypedDict(
+    "_OptionalListFunctionUrlConfigsRequestListFunctionUrlConfigsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListFunctionUrlConfigsRequestListFunctionUrlConfigsPaginateTypeDef(
+    _RequiredListFunctionUrlConfigsRequestListFunctionUrlConfigsPaginateTypeDef,
+    _OptionalListFunctionUrlConfigsRequestListFunctionUrlConfigsPaginateTypeDef,
+):
+    pass
+
 _RequiredListFunctionUrlConfigsRequestRequestTypeDef = TypedDict(
     "_RequiredListFunctionUrlConfigsRequestRequestTypeDef",
     {
         "FunctionName": str,
     },
 )
 _OptionalListFunctionUrlConfigsRequestRequestTypeDef = TypedDict(
@@ -1024,14 +1253,34 @@
 
 class ListFunctionUrlConfigsRequestRequestTypeDef(
     _RequiredListFunctionUrlConfigsRequestRequestTypeDef,
     _OptionalListFunctionUrlConfigsRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListFunctionsByCodeSigningConfigRequestListFunctionsByCodeSigningConfigPaginateTypeDef = TypedDict(
+    "_RequiredListFunctionsByCodeSigningConfigRequestListFunctionsByCodeSigningConfigPaginateTypeDef",
+    {
+        "CodeSigningConfigArn": str,
+    },
+)
+_OptionalListFunctionsByCodeSigningConfigRequestListFunctionsByCodeSigningConfigPaginateTypeDef = TypedDict(
+    "_OptionalListFunctionsByCodeSigningConfigRequestListFunctionsByCodeSigningConfigPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListFunctionsByCodeSigningConfigRequestListFunctionsByCodeSigningConfigPaginateTypeDef(
+    _RequiredListFunctionsByCodeSigningConfigRequestListFunctionsByCodeSigningConfigPaginateTypeDef,
+    _OptionalListFunctionsByCodeSigningConfigRequestListFunctionsByCodeSigningConfigPaginateTypeDef,
+):
+    pass
+
 _RequiredListFunctionsByCodeSigningConfigRequestRequestTypeDef = TypedDict(
     "_RequiredListFunctionsByCodeSigningConfigRequestRequestTypeDef",
     {
         "CodeSigningConfigArn": str,
     },
 )
 _OptionalListFunctionsByCodeSigningConfigRequestRequestTypeDef = TypedDict(
@@ -1045,25 +1294,66 @@
 
 class ListFunctionsByCodeSigningConfigRequestRequestTypeDef(
     _RequiredListFunctionsByCodeSigningConfigRequestRequestTypeDef,
     _OptionalListFunctionsByCodeSigningConfigRequestRequestTypeDef,
 ):
     pass
 
+ListFunctionsByCodeSigningConfigResponseTypeDef = TypedDict(
+    "ListFunctionsByCodeSigningConfigResponseTypeDef",
+    {
+        "NextMarker": str,
+        "FunctionArns": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListFunctionsRequestListFunctionsPaginateTypeDef = TypedDict(
+    "ListFunctionsRequestListFunctionsPaginateTypeDef",
+    {
+        "MasterRegion": str,
+        "FunctionVersion": Literal["ALL"],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListFunctionsRequestRequestTypeDef = TypedDict(
     "ListFunctionsRequestRequestTypeDef",
     {
         "MasterRegion": str,
         "FunctionVersion": Literal["ALL"],
         "Marker": str,
         "MaxItems": int,
     },
     total=False,
 )
 
+_RequiredListLayerVersionsRequestListLayerVersionsPaginateTypeDef = TypedDict(
+    "_RequiredListLayerVersionsRequestListLayerVersionsPaginateTypeDef",
+    {
+        "LayerName": str,
+    },
+)
+_OptionalListLayerVersionsRequestListLayerVersionsPaginateTypeDef = TypedDict(
+    "_OptionalListLayerVersionsRequestListLayerVersionsPaginateTypeDef",
+    {
+        "CompatibleRuntime": RuntimeType,
+        "CompatibleArchitecture": ArchitectureType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListLayerVersionsRequestListLayerVersionsPaginateTypeDef(
+    _RequiredListLayerVersionsRequestListLayerVersionsPaginateTypeDef,
+    _OptionalListLayerVersionsRequestListLayerVersionsPaginateTypeDef,
+):
+    pass
+
 _RequiredListLayerVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredListLayerVersionsRequestRequestTypeDef",
     {
         "LayerName": str,
     },
 )
 _OptionalListLayerVersionsRequestRequestTypeDef = TypedDict(
@@ -1078,25 +1368,55 @@
 )
 
 class ListLayerVersionsRequestRequestTypeDef(
     _RequiredListLayerVersionsRequestRequestTypeDef, _OptionalListLayerVersionsRequestRequestTypeDef
 ):
     pass
 
+ListLayersRequestListLayersPaginateTypeDef = TypedDict(
+    "ListLayersRequestListLayersPaginateTypeDef",
+    {
+        "CompatibleRuntime": RuntimeType,
+        "CompatibleArchitecture": ArchitectureType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListLayersRequestRequestTypeDef = TypedDict(
     "ListLayersRequestRequestTypeDef",
     {
         "CompatibleRuntime": RuntimeType,
         "Marker": str,
         "MaxItems": int,
         "CompatibleArchitecture": ArchitectureType,
     },
     total=False,
 )
 
+_RequiredListProvisionedConcurrencyConfigsRequestListProvisionedConcurrencyConfigsPaginateTypeDef = TypedDict(
+    "_RequiredListProvisionedConcurrencyConfigsRequestListProvisionedConcurrencyConfigsPaginateTypeDef",
+    {
+        "FunctionName": str,
+    },
+)
+_OptionalListProvisionedConcurrencyConfigsRequestListProvisionedConcurrencyConfigsPaginateTypeDef = TypedDict(
+    "_OptionalListProvisionedConcurrencyConfigsRequestListProvisionedConcurrencyConfigsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListProvisionedConcurrencyConfigsRequestListProvisionedConcurrencyConfigsPaginateTypeDef(
+    _RequiredListProvisionedConcurrencyConfigsRequestListProvisionedConcurrencyConfigsPaginateTypeDef,
+    _OptionalListProvisionedConcurrencyConfigsRequestListProvisionedConcurrencyConfigsPaginateTypeDef,
+):
+    pass
+
 _RequiredListProvisionedConcurrencyConfigsRequestRequestTypeDef = TypedDict(
     "_RequiredListProvisionedConcurrencyConfigsRequestRequestTypeDef",
     {
         "FunctionName": str,
     },
 )
 _OptionalListProvisionedConcurrencyConfigsRequestRequestTypeDef = TypedDict(
@@ -1131,14 +1451,42 @@
 ListTagsRequestRequestTypeDef = TypedDict(
     "ListTagsRequestRequestTypeDef",
     {
         "Resource": str,
     },
 )
 
+ListTagsResponseTypeDef = TypedDict(
+    "ListTagsResponseTypeDef",
+    {
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListVersionsByFunctionRequestListVersionsByFunctionPaginateTypeDef = TypedDict(
+    "_RequiredListVersionsByFunctionRequestListVersionsByFunctionPaginateTypeDef",
+    {
+        "FunctionName": str,
+    },
+)
+_OptionalListVersionsByFunctionRequestListVersionsByFunctionPaginateTypeDef = TypedDict(
+    "_OptionalListVersionsByFunctionRequestListVersionsByFunctionPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListVersionsByFunctionRequestListVersionsByFunctionPaginateTypeDef(
+    _RequiredListVersionsByFunctionRequestListVersionsByFunctionPaginateTypeDef,
+    _OptionalListVersionsByFunctionRequestListVersionsByFunctionPaginateTypeDef,
+):
+    pass
+
 _RequiredListVersionsByFunctionRequestRequestTypeDef = TypedDict(
     "_RequiredListVersionsByFunctionRequestRequestTypeDef",
     {
         "FunctionName": str,
     },
 )
 _OptionalListVersionsByFunctionRequestRequestTypeDef = TypedDict(
@@ -1152,14 +1500,24 @@
 
 class ListVersionsByFunctionRequestRequestTypeDef(
     _RequiredListVersionsByFunctionRequestRequestTypeDef,
     _OptionalListVersionsByFunctionRequestRequestTypeDef,
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
 _RequiredPublishVersionRequestRequestTypeDef = TypedDict(
     "_RequiredPublishVersionRequestRequestTypeDef",
     {
         "FunctionName": str,
     },
 )
 _OptionalPublishVersionRequestRequestTypeDef = TypedDict(
@@ -1181,14 +1539,23 @@
     "PutFunctionCodeSigningConfigRequestRequestTypeDef",
     {
         "CodeSigningConfigArn": str,
         "FunctionName": str,
     },
 )
 
+PutFunctionCodeSigningConfigResponseTypeDef = TypedDict(
+    "PutFunctionCodeSigningConfigResponseTypeDef",
+    {
+        "CodeSigningConfigArn": str,
+        "FunctionName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 PutFunctionConcurrencyRequestRequestTypeDef = TypedDict(
     "PutFunctionConcurrencyRequestRequestTypeDef",
     {
         "FunctionName": str,
         "ReservedConcurrentExecutions": int,
     },
 )
@@ -1198,14 +1565,27 @@
     {
         "FunctionName": str,
         "Qualifier": str,
         "ProvisionedConcurrentExecutions": int,
     },
 )
 
+PutProvisionedConcurrencyConfigResponseTypeDef = TypedDict(
+    "PutProvisionedConcurrencyConfigResponseTypeDef",
+    {
+        "RequestedProvisionedConcurrentExecutions": int,
+        "AvailableProvisionedConcurrentExecutions": int,
+        "AllocatedProvisionedConcurrentExecutions": int,
+        "Status": ProvisionedConcurrencyStatusEnumType,
+        "StatusReason": str,
+        "LastModified": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredPutRuntimeManagementConfigRequestRequestTypeDef = TypedDict(
     "_RequiredPutRuntimeManagementConfigRequestRequestTypeDef",
     {
         "FunctionName": str,
         "UpdateRuntimeOn": UpdateRuntimeOnType,
     },
 )
@@ -1220,14 +1600,24 @@
 
 class PutRuntimeManagementConfigRequestRequestTypeDef(
     _RequiredPutRuntimeManagementConfigRequestRequestTypeDef,
     _OptionalPutRuntimeManagementConfigRequestRequestTypeDef,
 ):
     pass
 
+PutRuntimeManagementConfigResponseTypeDef = TypedDict(
+    "PutRuntimeManagementConfigResponseTypeDef",
+    {
+        "UpdateRuntimeOn": UpdateRuntimeOnType,
+        "FunctionArn": str,
+        "RuntimeVersionArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredRemoveLayerVersionPermissionRequestRequestTypeDef = TypedDict(
     "_RequiredRemoveLayerVersionPermissionRequestRequestTypeDef",
     {
         "LayerName": str,
         "VersionNumber": int,
         "StatementId": str,
     },
@@ -1263,14 +1653,25 @@
 )
 
 class RemovePermissionRequestRequestTypeDef(
     _RequiredRemovePermissionRequestRequestTypeDef, _OptionalRemovePermissionRequestRequestTypeDef
 ):
     pass
 
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
 RuntimeVersionErrorTypeDef = TypedDict(
     "RuntimeVersionErrorTypeDef",
     {
         "ErrorCode": str,
         "Message": str,
     },
     total=False,
@@ -1316,191 +1717,33 @@
 
 class UpdateFunctionCodeRequestRequestTypeDef(
     _RequiredUpdateFunctionCodeRequestRequestTypeDef,
     _OptionalUpdateFunctionCodeRequestRequestTypeDef,
 ):
     pass
 
-AddLayerVersionPermissionResponseTypeDef = TypedDict(
-    "AddLayerVersionPermissionResponseTypeDef",
-    {
-        "Statement": str,
-        "RevisionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-AddPermissionResponseTypeDef = TypedDict(
-    "AddPermissionResponseTypeDef",
-    {
-        "Statement": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ConcurrencyResponseMetadataTypeDef = TypedDict(
-    "ConcurrencyResponseMetadataTypeDef",
-    {
-        "ReservedConcurrentExecutions": int,
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
 GetAccountSettingsResponseTypeDef = TypedDict(
     "GetAccountSettingsResponseTypeDef",
     {
         "AccountLimit": AccountLimitTypeDef,
         "AccountUsage": AccountUsageTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetFunctionCodeSigningConfigResponseTypeDef = TypedDict(
-    "GetFunctionCodeSigningConfigResponseTypeDef",
-    {
-        "CodeSigningConfigArn": str,
-        "FunctionName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetFunctionConcurrencyResponseTypeDef = TypedDict(
-    "GetFunctionConcurrencyResponseTypeDef",
-    {
-        "ReservedConcurrentExecutions": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetLayerVersionPolicyResponseTypeDef = TypedDict(
-    "GetLayerVersionPolicyResponseTypeDef",
-    {
-        "Policy": str,
-        "RevisionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetPolicyResponseTypeDef = TypedDict(
-    "GetPolicyResponseTypeDef",
-    {
-        "Policy": str,
-        "RevisionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetProvisionedConcurrencyConfigResponseTypeDef = TypedDict(
-    "GetProvisionedConcurrencyConfigResponseTypeDef",
-    {
-        "RequestedProvisionedConcurrentExecutions": int,
-        "AvailableProvisionedConcurrentExecutions": int,
-        "AllocatedProvisionedConcurrentExecutions": int,
-        "Status": ProvisionedConcurrencyStatusEnumType,
-        "StatusReason": str,
-        "LastModified": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetRuntimeManagementConfigResponseTypeDef = TypedDict(
-    "GetRuntimeManagementConfigResponseTypeDef",
-    {
-        "UpdateRuntimeOn": UpdateRuntimeOnType,
-        "RuntimeVersionArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-InvocationResponseTypeDef = TypedDict(
-    "InvocationResponseTypeDef",
-    {
-        "StatusCode": int,
-        "FunctionError": str,
-        "LogResult": str,
-        "Payload": StreamingBody,
-        "ExecutedVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-InvokeAsyncResponseTypeDef = TypedDict(
-    "InvokeAsyncResponseTypeDef",
-    {
-        "Status": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListFunctionsByCodeSigningConfigResponseTypeDef = TypedDict(
-    "ListFunctionsByCodeSigningConfigResponseTypeDef",
-    {
-        "NextMarker": str,
-        "FunctionArns": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsResponseTypeDef = TypedDict(
-    "ListTagsResponseTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutFunctionCodeSigningConfigResponseTypeDef = TypedDict(
-    "PutFunctionCodeSigningConfigResponseTypeDef",
-    {
-        "CodeSigningConfigArn": str,
-        "FunctionName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutProvisionedConcurrencyConfigResponseTypeDef = TypedDict(
-    "PutProvisionedConcurrencyConfigResponseTypeDef",
-    {
-        "RequestedProvisionedConcurrentExecutions": int,
-        "AvailableProvisionedConcurrentExecutions": int,
-        "AllocatedProvisionedConcurrentExecutions": int,
-        "Status": ProvisionedConcurrencyStatusEnumType,
-        "StatusReason": str,
-        "LastModified": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutRuntimeManagementConfigResponseTypeDef = TypedDict(
-    "PutRuntimeManagementConfigResponseTypeDef",
-    {
-        "UpdateRuntimeOn": UpdateRuntimeOnType,
-        "FunctionArn": str,
-        "RuntimeVersionArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AliasConfigurationResponseMetadataTypeDef = TypedDict(
     "AliasConfigurationResponseMetadataTypeDef",
     {
         "AliasArn": str,
         "Name": str,
         "FunctionVersion": str,
         "Description": str,
         "RoutingConfig": AliasRoutingConfigurationTypeDef,
         "RevisionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AliasConfigurationTypeDef = TypedDict(
     "AliasConfigurationTypeDef",
     {
         "AliasArn": str,
@@ -1632,14 +1875,15 @@
     },
 )
 _OptionalCreateFunctionUrlConfigRequestRequestTypeDef = TypedDict(
     "_OptionalCreateFunctionUrlConfigRequestRequestTypeDef",
     {
         "Qualifier": str,
         "Cors": CorsTypeDef,
+        "InvokeMode": InvokeModeType,
     },
     total=False,
 )
 
 class CreateFunctionUrlConfigRequestRequestTypeDef(
     _RequiredCreateFunctionUrlConfigRequestRequestTypeDef,
     _OptionalCreateFunctionUrlConfigRequestRequestTypeDef,
@@ -1650,15 +1894,16 @@
     "CreateFunctionUrlConfigResponseTypeDef",
     {
         "FunctionUrl": str,
         "FunctionArn": str,
         "AuthType": FunctionUrlAuthTypeType,
         "Cors": CorsTypeDef,
         "CreationTime": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "InvokeMode": InvokeModeType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredFunctionUrlConfigTypeDef = TypedDict(
     "_RequiredFunctionUrlConfigTypeDef",
     {
         "FunctionUrl": str,
@@ -1668,14 +1913,15 @@
         "AuthType": FunctionUrlAuthTypeType,
     },
 )
 _OptionalFunctionUrlConfigTypeDef = TypedDict(
     "_OptionalFunctionUrlConfigTypeDef",
     {
         "Cors": CorsTypeDef,
+        "InvokeMode": InvokeModeType,
     },
     total=False,
 )
 
 class FunctionUrlConfigTypeDef(
     _RequiredFunctionUrlConfigTypeDef, _OptionalFunctionUrlConfigTypeDef
 ):
@@ -1686,15 +1932,16 @@
     {
         "FunctionUrl": str,
         "FunctionArn": str,
         "AuthType": FunctionUrlAuthTypeType,
         "Cors": CorsTypeDef,
         "CreationTime": str,
         "LastModifiedTime": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "InvokeMode": InvokeModeType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateFunctionUrlConfigRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateFunctionUrlConfigRequestRequestTypeDef",
     {
         "FunctionName": str,
@@ -1702,14 +1949,15 @@
 )
 _OptionalUpdateFunctionUrlConfigRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateFunctionUrlConfigRequestRequestTypeDef",
     {
         "Qualifier": str,
         "AuthType": FunctionUrlAuthTypeType,
         "Cors": CorsTypeDef,
+        "InvokeMode": InvokeModeType,
     },
     total=False,
 )
 
 class UpdateFunctionUrlConfigRequestRequestTypeDef(
     _RequiredUpdateFunctionUrlConfigRequestRequestTypeDef,
     _OptionalUpdateFunctionUrlConfigRequestRequestTypeDef,
@@ -1721,15 +1969,16 @@
     {
         "FunctionUrl": str,
         "FunctionArn": str,
         "AuthType": FunctionUrlAuthTypeType,
         "Cors": CorsTypeDef,
         "CreationTime": str,
         "LastModifiedTime": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "InvokeMode": InvokeModeType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateFunctionRequestRequestTypeDef = TypedDict(
     "_RequiredCreateFunctionRequestRequestTypeDef",
     {
         "FunctionName": str,
@@ -1965,15 +2214,15 @@
         "LayerVersionArn": str,
         "Description": str,
         "CreatedDate": str,
         "Version": int,
         "CompatibleRuntimes": List[RuntimeType],
         "LicenseInfo": str,
         "CompatibleArchitectures": List[ArchitectureType],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PublishLayerVersionResponseTypeDef = TypedDict(
     "PublishLayerVersionResponseTypeDef",
     {
         "Content": LayerVersionContentOutputTypeDef,
@@ -1981,27 +2230,36 @@
         "LayerVersionArn": str,
         "Description": str,
         "CreatedDate": str,
         "Version": int,
         "CompatibleRuntimes": List[RuntimeType],
         "LicenseInfo": str,
         "CompatibleArchitectures": List[ArchitectureType],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ImageConfigResponseTypeDef = TypedDict(
     "ImageConfigResponseTypeDef",
     {
         "ImageConfig": ImageConfigTypeDef,
         "Error": ImageConfigErrorTypeDef,
     },
     total=False,
 )
 
+InvokeWithResponseStreamResponseEventTypeDef = TypedDict(
+    "InvokeWithResponseStreamResponseEventTypeDef",
+    {
+        "PayloadChunk": InvokeResponseStreamUpdateTypeDef,
+        "InvokeComplete": InvokeWithResponseStreamCompleteEventTypeDef,
+    },
+    total=False,
+)
+
 _RequiredPublishLayerVersionRequestRequestTypeDef = TypedDict(
     "_RequiredPublishLayerVersionRequestRequestTypeDef",
     {
         "LayerName": str,
         "Content": LayerVersionContentInputTypeDef,
     },
 )
@@ -2033,205 +2291,24 @@
 )
 
 ListLayerVersionsResponseTypeDef = TypedDict(
     "ListLayerVersionsResponseTypeDef",
     {
         "NextMarker": str,
         "LayerVersions": List[LayerVersionsListItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredListAliasesRequestListAliasesPaginateTypeDef = TypedDict(
-    "_RequiredListAliasesRequestListAliasesPaginateTypeDef",
-    {
-        "FunctionName": str,
-    },
-)
-_OptionalListAliasesRequestListAliasesPaginateTypeDef = TypedDict(
-    "_OptionalListAliasesRequestListAliasesPaginateTypeDef",
-    {
-        "FunctionVersion": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListAliasesRequestListAliasesPaginateTypeDef(
-    _RequiredListAliasesRequestListAliasesPaginateTypeDef,
-    _OptionalListAliasesRequestListAliasesPaginateTypeDef,
-):
-    pass
-
-ListCodeSigningConfigsRequestListCodeSigningConfigsPaginateTypeDef = TypedDict(
-    "ListCodeSigningConfigsRequestListCodeSigningConfigsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListEventSourceMappingsRequestListEventSourceMappingsPaginateTypeDef = TypedDict(
-    "ListEventSourceMappingsRequestListEventSourceMappingsPaginateTypeDef",
-    {
-        "EventSourceArn": str,
-        "FunctionName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListFunctionEventInvokeConfigsRequestListFunctionEventInvokeConfigsPaginateTypeDef = TypedDict(
-    "_RequiredListFunctionEventInvokeConfigsRequestListFunctionEventInvokeConfigsPaginateTypeDef",
-    {
-        "FunctionName": str,
-    },
-)
-_OptionalListFunctionEventInvokeConfigsRequestListFunctionEventInvokeConfigsPaginateTypeDef = TypedDict(
-    "_OptionalListFunctionEventInvokeConfigsRequestListFunctionEventInvokeConfigsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-class ListFunctionEventInvokeConfigsRequestListFunctionEventInvokeConfigsPaginateTypeDef(
-    _RequiredListFunctionEventInvokeConfigsRequestListFunctionEventInvokeConfigsPaginateTypeDef,
-    _OptionalListFunctionEventInvokeConfigsRequestListFunctionEventInvokeConfigsPaginateTypeDef,
-):
-    pass
-
-_RequiredListFunctionUrlConfigsRequestListFunctionUrlConfigsPaginateTypeDef = TypedDict(
-    "_RequiredListFunctionUrlConfigsRequestListFunctionUrlConfigsPaginateTypeDef",
-    {
-        "FunctionName": str,
-    },
-)
-_OptionalListFunctionUrlConfigsRequestListFunctionUrlConfigsPaginateTypeDef = TypedDict(
-    "_OptionalListFunctionUrlConfigsRequestListFunctionUrlConfigsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListFunctionUrlConfigsRequestListFunctionUrlConfigsPaginateTypeDef(
-    _RequiredListFunctionUrlConfigsRequestListFunctionUrlConfigsPaginateTypeDef,
-    _OptionalListFunctionUrlConfigsRequestListFunctionUrlConfigsPaginateTypeDef,
-):
-    pass
-
-_RequiredListFunctionsByCodeSigningConfigRequestListFunctionsByCodeSigningConfigPaginateTypeDef = TypedDict(
-    "_RequiredListFunctionsByCodeSigningConfigRequestListFunctionsByCodeSigningConfigPaginateTypeDef",
-    {
-        "CodeSigningConfigArn": str,
-    },
-)
-_OptionalListFunctionsByCodeSigningConfigRequestListFunctionsByCodeSigningConfigPaginateTypeDef = TypedDict(
-    "_OptionalListFunctionsByCodeSigningConfigRequestListFunctionsByCodeSigningConfigPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListFunctionsByCodeSigningConfigRequestListFunctionsByCodeSigningConfigPaginateTypeDef(
-    _RequiredListFunctionsByCodeSigningConfigRequestListFunctionsByCodeSigningConfigPaginateTypeDef,
-    _OptionalListFunctionsByCodeSigningConfigRequestListFunctionsByCodeSigningConfigPaginateTypeDef,
-):
-    pass
-
-ListFunctionsRequestListFunctionsPaginateTypeDef = TypedDict(
-    "ListFunctionsRequestListFunctionsPaginateTypeDef",
-    {
-        "MasterRegion": str,
-        "FunctionVersion": Literal["ALL"],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListLayerVersionsRequestListLayerVersionsPaginateTypeDef = TypedDict(
-    "_RequiredListLayerVersionsRequestListLayerVersionsPaginateTypeDef",
-    {
-        "LayerName": str,
-    },
-)
-_OptionalListLayerVersionsRequestListLayerVersionsPaginateTypeDef = TypedDict(
-    "_OptionalListLayerVersionsRequestListLayerVersionsPaginateTypeDef",
-    {
-        "CompatibleRuntime": RuntimeType,
-        "CompatibleArchitecture": ArchitectureType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListLayerVersionsRequestListLayerVersionsPaginateTypeDef(
-    _RequiredListLayerVersionsRequestListLayerVersionsPaginateTypeDef,
-    _OptionalListLayerVersionsRequestListLayerVersionsPaginateTypeDef,
-):
-    pass
-
-ListLayersRequestListLayersPaginateTypeDef = TypedDict(
-    "ListLayersRequestListLayersPaginateTypeDef",
-    {
-        "CompatibleRuntime": RuntimeType,
-        "CompatibleArchitecture": ArchitectureType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListProvisionedConcurrencyConfigsRequestListProvisionedConcurrencyConfigsPaginateTypeDef = TypedDict(
-    "_RequiredListProvisionedConcurrencyConfigsRequestListProvisionedConcurrencyConfigsPaginateTypeDef",
-    {
-        "FunctionName": str,
-    },
-)
-_OptionalListProvisionedConcurrencyConfigsRequestListProvisionedConcurrencyConfigsPaginateTypeDef = TypedDict(
-    "_OptionalListProvisionedConcurrencyConfigsRequestListProvisionedConcurrencyConfigsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListProvisionedConcurrencyConfigsRequestListProvisionedConcurrencyConfigsPaginateTypeDef(
-    _RequiredListProvisionedConcurrencyConfigsRequestListProvisionedConcurrencyConfigsPaginateTypeDef,
-    _OptionalListProvisionedConcurrencyConfigsRequestListProvisionedConcurrencyConfigsPaginateTypeDef,
-):
-    pass
-
-_RequiredListVersionsByFunctionRequestListVersionsByFunctionPaginateTypeDef = TypedDict(
-    "_RequiredListVersionsByFunctionRequestListVersionsByFunctionPaginateTypeDef",
-    {
-        "FunctionName": str,
-    },
-)
-_OptionalListVersionsByFunctionRequestListVersionsByFunctionPaginateTypeDef = TypedDict(
-    "_OptionalListVersionsByFunctionRequestListVersionsByFunctionPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListVersionsByFunctionRequestListVersionsByFunctionPaginateTypeDef(
-    _RequiredListVersionsByFunctionRequestListVersionsByFunctionPaginateTypeDef,
-    _OptionalListVersionsByFunctionRequestListVersionsByFunctionPaginateTypeDef,
-):
-    pass
-
 ListProvisionedConcurrencyConfigsResponseTypeDef = TypedDict(
     "ListProvisionedConcurrencyConfigsResponseTypeDef",
     {
         "ProvisionedConcurrencyConfigs": List[ProvisionedConcurrencyConfigListItemTypeDef],
         "NextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RuntimeVersionConfigTypeDef = TypedDict(
     "RuntimeVersionConfigTypeDef",
     {
         "RuntimeVersionArn": str,
@@ -2241,69 +2318,69 @@
 )
 
 ListAliasesResponseTypeDef = TypedDict(
     "ListAliasesResponseTypeDef",
     {
         "NextMarker": str,
         "Aliases": List[AliasConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateCodeSigningConfigResponseTypeDef = TypedDict(
     "CreateCodeSigningConfigResponseTypeDef",
     {
         "CodeSigningConfig": CodeSigningConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCodeSigningConfigResponseTypeDef = TypedDict(
     "GetCodeSigningConfigResponseTypeDef",
     {
         "CodeSigningConfig": CodeSigningConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCodeSigningConfigsResponseTypeDef = TypedDict(
     "ListCodeSigningConfigsResponseTypeDef",
     {
         "NextMarker": str,
         "CodeSigningConfigs": List[CodeSigningConfigTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateCodeSigningConfigResponseTypeDef = TypedDict(
     "UpdateCodeSigningConfigResponseTypeDef",
     {
         "CodeSigningConfig": CodeSigningConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListFunctionUrlConfigsResponseTypeDef = TypedDict(
     "ListFunctionUrlConfigsResponseTypeDef",
     {
         "FunctionUrlConfigs": List[FunctionUrlConfigTypeDef],
         "NextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FunctionEventInvokeConfigResponseMetadataTypeDef = TypedDict(
     "FunctionEventInvokeConfigResponseMetadataTypeDef",
     {
         "LastModified": datetime,
         "FunctionArn": str,
         "MaximumRetryAttempts": int,
         "MaximumEventAgeInSeconds": int,
         "DestinationConfig": DestinationConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FunctionEventInvokeConfigTypeDef = TypedDict(
     "FunctionEventInvokeConfigTypeDef",
     {
         "LastModified": datetime,
@@ -2387,14 +2464,15 @@
         "Queues": Sequence[str],
         "SourceAccessConfigurations": Sequence[SourceAccessConfigurationTypeDef],
         "SelfManagedEventSource": SelfManagedEventSourceTypeDef,
         "FunctionResponseTypes": Sequence[Literal["ReportBatchItemFailures"]],
         "AmazonManagedKafkaEventSourceConfig": AmazonManagedKafkaEventSourceConfigTypeDef,
         "SelfManagedKafkaEventSourceConfig": SelfManagedKafkaEventSourceConfigTypeDef,
         "ScalingConfig": ScalingConfigTypeDef,
+        "DocumentDBEventSourceConfig": DocumentDBEventSourceConfigTypeDef,
     },
     total=False,
 )
 
 class CreateEventSourceMappingRequestRequestTypeDef(
     _RequiredCreateEventSourceMappingRequestRequestTypeDef,
     _OptionalCreateEventSourceMappingRequestRequestTypeDef,
@@ -2426,15 +2504,16 @@
         "BisectBatchOnFunctionError": bool,
         "MaximumRetryAttempts": int,
         "TumblingWindowInSeconds": int,
         "FunctionResponseTypes": List[Literal["ReportBatchItemFailures"]],
         "AmazonManagedKafkaEventSourceConfig": AmazonManagedKafkaEventSourceConfigTypeDef,
         "SelfManagedKafkaEventSourceConfig": SelfManagedKafkaEventSourceConfigTypeDef,
         "ScalingConfig": ScalingConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "DocumentDBEventSourceConfig": DocumentDBEventSourceConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EventSourceMappingConfigurationTypeDef = TypedDict(
     "EventSourceMappingConfigurationTypeDef",
     {
         "UUID": str,
@@ -2459,14 +2538,15 @@
         "BisectBatchOnFunctionError": bool,
         "MaximumRetryAttempts": int,
         "TumblingWindowInSeconds": int,
         "FunctionResponseTypes": List[Literal["ReportBatchItemFailures"]],
         "AmazonManagedKafkaEventSourceConfig": AmazonManagedKafkaEventSourceConfigTypeDef,
         "SelfManagedKafkaEventSourceConfig": SelfManagedKafkaEventSourceConfigTypeDef,
         "ScalingConfig": ScalingConfigTypeDef,
+        "DocumentDBEventSourceConfig": DocumentDBEventSourceConfigTypeDef,
     },
     total=False,
 )
 
 _RequiredUpdateEventSourceMappingRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateEventSourceMappingRequestRequestTypeDef",
     {
@@ -2486,30 +2566,42 @@
         "BisectBatchOnFunctionError": bool,
         "MaximumRetryAttempts": int,
         "ParallelizationFactor": int,
         "SourceAccessConfigurations": Sequence[SourceAccessConfigurationTypeDef],
         "TumblingWindowInSeconds": int,
         "FunctionResponseTypes": Sequence[Literal["ReportBatchItemFailures"]],
         "ScalingConfig": ScalingConfigTypeDef,
+        "DocumentDBEventSourceConfig": DocumentDBEventSourceConfigTypeDef,
     },
     total=False,
 )
 
 class UpdateEventSourceMappingRequestRequestTypeDef(
     _RequiredUpdateEventSourceMappingRequestRequestTypeDef,
     _OptionalUpdateEventSourceMappingRequestRequestTypeDef,
 ):
     pass
 
+InvokeWithResponseStreamResponseTypeDef = TypedDict(
+    "InvokeWithResponseStreamResponseTypeDef",
+    {
+        "StatusCode": int,
+        "ExecutedVersion": str,
+        "EventStream": InvokeWithResponseStreamResponseEventTypeDef,
+        "ResponseStreamContentType": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListLayersResponseTypeDef = TypedDict(
     "ListLayersResponseTypeDef",
     {
         "NextMarker": str,
         "Layers": List[LayersListItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FunctionConfigurationResponseMetadataTypeDef = TypedDict(
     "FunctionConfigurationResponseMetadataTypeDef",
     {
         "FunctionName": str,
@@ -2543,15 +2635,15 @@
         "ImageConfigResponse": ImageConfigResponseTypeDef,
         "SigningProfileVersionArn": str,
         "SigningJobArn": str,
         "Architectures": List[ArchitectureType],
         "EphemeralStorage": EphemeralStorageTypeDef,
         "SnapStart": SnapStartResponseTypeDef,
         "RuntimeVersionConfig": RuntimeVersionConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FunctionConfigurationTypeDef = TypedDict(
     "FunctionConfigurationTypeDef",
     {
         "FunctionName": str,
@@ -2594,48 +2686,48 @@
 )
 
 ListFunctionEventInvokeConfigsResponseTypeDef = TypedDict(
     "ListFunctionEventInvokeConfigsResponseTypeDef",
     {
         "FunctionEventInvokeConfigs": List[FunctionEventInvokeConfigTypeDef],
         "NextMarker": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEventSourceMappingsResponseTypeDef = TypedDict(
     "ListEventSourceMappingsResponseTypeDef",
     {
         "NextMarker": str,
         "EventSourceMappings": List[EventSourceMappingConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetFunctionResponseTypeDef = TypedDict(
     "GetFunctionResponseTypeDef",
     {
         "Configuration": FunctionConfigurationTypeDef,
         "Code": FunctionCodeLocationTypeDef,
         "Tags": Dict[str, str],
         "Concurrency": ConcurrencyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListFunctionsResponseTypeDef = TypedDict(
     "ListFunctionsResponseTypeDef",
     {
         "NextMarker": str,
         "Functions": List[FunctionConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVersionsByFunctionResponseTypeDef = TypedDict(
     "ListVersionsByFunctionResponseTypeDef",
     {
         "NextMarker": str,
         "Versions": List[FunctionConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-lambda-2.5.0.post1/types_aiobotocore_lambda/waiter.py` & `types-aiobotocore-lambda-2.5.1/types_aiobotocore_lambda/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-lambda-2.5.0.post1/types_aiobotocore_lambda/waiter.pyi` & `types-aiobotocore-lambda-2.5.1/types_aiobotocore_lambda/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-lambda-2.5.0.post1/types_aiobotocore_lambda.egg-info/PKG-INFO` & `types-aiobotocore-lambda-2.5.1/types_aiobotocore_lambda.egg-info/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-lambda
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Lambda 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Lambda 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-lambda"></a>
 
 # types-aiobotocore-lambda
 
 [![PyPI - types-aiobotocore-lambda](https://img.shields.io/pypi/v/types-aiobotocore-lambda.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lambda)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-lambda.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lambda)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-lambda?color=blue)](https://pypistats.org/packages/types-aiobotocore-lambda)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Lambda 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda)
+[aiobotocore.Lambda 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lambda.html#Lambda)
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
 [types-aiobotocore-lambda docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/).
 
 See how it helps to find and fix potential bugs:
 
@@ -370,23 +370,25 @@
 
 ```python
 from types_aiobotocore_lambda.literals import (
     ArchitectureType,
     CodeSigningPolicyType,
     EndPointTypeType,
     EventSourcePositionType,
+    FullDocumentType,
     FunctionActiveV2WaiterName,
     FunctionActiveWaiterName,
     FunctionExistsWaiterName,
     FunctionResponseTypeType,
     FunctionUpdatedV2WaiterName,
     FunctionUpdatedWaiterName,
     FunctionUrlAuthTypeType,
     FunctionVersionType,
     InvocationTypeType,
+    InvokeModeType,
     LastUpdateStatusReasonCodeType,
     LastUpdateStatusType,
     ListAliasesPaginatorName,
     ListCodeSigningConfigsPaginatorName,
     ListEventSourceMappingsPaginatorName,
     ListFunctionEventInvokeConfigsPaginatorName,
     ListFunctionUrlConfigsPaginatorName,
@@ -396,14 +398,15 @@
     ListLayersPaginatorName,
     ListProvisionedConcurrencyConfigsPaginatorName,
     ListVersionsByFunctionPaginatorName,
     LogTypeType,
     PackageTypeType,
     ProvisionedConcurrencyStatusEnumType,
     PublishedVersionActiveWaiterName,
+    ResponseStreamingInvocationTypeType,
     RuntimeType,
     SnapStartApplyOnType,
     SnapStartOptimizationStatusType,
     SourceAccessTypeType,
     StateReasonCodeType,
     StateType,
     TracingModeType,
@@ -429,22 +432,25 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_lambda.type_defs import (
     AccountLimitTypeDef,
     AccountUsageTypeDef,
     AddLayerVersionPermissionRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    AddLayerVersionPermissionResponseTypeDef,
     AddPermissionRequestRequestTypeDef,
+    AddPermissionResponseTypeDef,
     AliasRoutingConfigurationTypeDef,
     AllowedPublishersTypeDef,
     AmazonManagedKafkaEventSourceConfigTypeDef,
     CodeSigningPoliciesTypeDef,
+    ConcurrencyResponseMetadataTypeDef,
     ConcurrencyTypeDef,
     CorsTypeDef,
+    DocumentDBEventSourceConfigTypeDef,
     ScalingConfigTypeDef,
     SelfManagedEventSourceTypeDef,
     SelfManagedKafkaEventSourceConfigTypeDef,
     SourceAccessConfigurationTypeDef,
     DeadLetterConfigTypeDef,
     EnvironmentTypeDef,
     EphemeralStorageTypeDef,
@@ -462,86 +468,98 @@
     DeleteFunctionEventInvokeConfigRequestRequestTypeDef,
     DeleteFunctionRequestRequestTypeDef,
     DeleteFunctionUrlConfigRequestRequestTypeDef,
     DeleteLayerVersionRequestRequestTypeDef,
     DeleteProvisionedConcurrencyConfigRequestRequestTypeDef,
     OnFailureTypeDef,
     OnSuccessTypeDef,
+    EmptyResponseMetadataTypeDef,
     EnvironmentErrorTypeDef,
     FilterTypeDef,
     FunctionCodeLocationTypeDef,
     LayerTypeDef,
     SnapStartResponseTypeDef,
     TracingConfigResponseTypeDef,
     VpcConfigResponseTypeDef,
     GetAliasRequestRequestTypeDef,
     GetCodeSigningConfigRequestRequestTypeDef,
     GetEventSourceMappingRequestRequestTypeDef,
     GetFunctionCodeSigningConfigRequestRequestTypeDef,
+    GetFunctionCodeSigningConfigResponseTypeDef,
     GetFunctionConcurrencyRequestRequestTypeDef,
+    GetFunctionConcurrencyResponseTypeDef,
     WaiterConfigTypeDef,
     GetFunctionConfigurationRequestRequestTypeDef,
     GetFunctionEventInvokeConfigRequestRequestTypeDef,
     GetFunctionRequestRequestTypeDef,
     GetFunctionUrlConfigRequestRequestTypeDef,
     GetLayerVersionByArnRequestRequestTypeDef,
     GetLayerVersionPolicyRequestRequestTypeDef,
+    GetLayerVersionPolicyResponseTypeDef,
     GetLayerVersionRequestRequestTypeDef,
     LayerVersionContentOutputTypeDef,
     GetPolicyRequestRequestTypeDef,
+    GetPolicyResponseTypeDef,
     GetProvisionedConcurrencyConfigRequestRequestTypeDef,
+    GetProvisionedConcurrencyConfigResponseTypeDef,
     GetRuntimeManagementConfigRequestRequestTypeDef,
+    GetRuntimeManagementConfigResponseTypeDef,
     ImageConfigErrorTypeDef,
     InvocationRequestRequestTypeDef,
+    InvocationResponseTypeDef,
     InvokeAsyncRequestRequestTypeDef,
+    InvokeAsyncResponseTypeDef,
+    InvokeResponseStreamUpdateTypeDef,
+    InvokeWithResponseStreamCompleteEventTypeDef,
+    InvokeWithResponseStreamRequestRequestTypeDef,
     LayerVersionContentInputTypeDef,
     LayerVersionsListItemTypeDef,
-    PaginatorConfigTypeDef,
+    ListAliasesRequestListAliasesPaginateTypeDef,
     ListAliasesRequestRequestTypeDef,
+    ListCodeSigningConfigsRequestListCodeSigningConfigsPaginateTypeDef,
     ListCodeSigningConfigsRequestRequestTypeDef,
+    ListEventSourceMappingsRequestListEventSourceMappingsPaginateTypeDef,
     ListEventSourceMappingsRequestRequestTypeDef,
+    ListFunctionEventInvokeConfigsRequestListFunctionEventInvokeConfigsPaginateTypeDef,
     ListFunctionEventInvokeConfigsRequestRequestTypeDef,
+    ListFunctionUrlConfigsRequestListFunctionUrlConfigsPaginateTypeDef,
     ListFunctionUrlConfigsRequestRequestTypeDef,
+    ListFunctionsByCodeSigningConfigRequestListFunctionsByCodeSigningConfigPaginateTypeDef,
     ListFunctionsByCodeSigningConfigRequestRequestTypeDef,
+    ListFunctionsByCodeSigningConfigResponseTypeDef,
+    ListFunctionsRequestListFunctionsPaginateTypeDef,
     ListFunctionsRequestRequestTypeDef,
+    ListLayerVersionsRequestListLayerVersionsPaginateTypeDef,
     ListLayerVersionsRequestRequestTypeDef,
+    ListLayersRequestListLayersPaginateTypeDef,
     ListLayersRequestRequestTypeDef,
+    ListProvisionedConcurrencyConfigsRequestListProvisionedConcurrencyConfigsPaginateTypeDef,
     ListProvisionedConcurrencyConfigsRequestRequestTypeDef,
     ProvisionedConcurrencyConfigListItemTypeDef,
     ListTagsRequestRequestTypeDef,
+    ListTagsResponseTypeDef,
+    ListVersionsByFunctionRequestListVersionsByFunctionPaginateTypeDef,
     ListVersionsByFunctionRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     PublishVersionRequestRequestTypeDef,
     PutFunctionCodeSigningConfigRequestRequestTypeDef,
+    PutFunctionCodeSigningConfigResponseTypeDef,
     PutFunctionConcurrencyRequestRequestTypeDef,
     PutProvisionedConcurrencyConfigRequestRequestTypeDef,
+    PutProvisionedConcurrencyConfigResponseTypeDef,
     PutRuntimeManagementConfigRequestRequestTypeDef,
+    PutRuntimeManagementConfigResponseTypeDef,
     RemoveLayerVersionPermissionRequestRequestTypeDef,
     RemovePermissionRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     RuntimeVersionErrorTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateFunctionCodeRequestRequestTypeDef,
-    AddLayerVersionPermissionResponseTypeDef,
-    AddPermissionResponseTypeDef,
-    ConcurrencyResponseMetadataTypeDef,
-    EmptyResponseMetadataTypeDef,
     GetAccountSettingsResponseTypeDef,
-    GetFunctionCodeSigningConfigResponseTypeDef,
-    GetFunctionConcurrencyResponseTypeDef,
-    GetLayerVersionPolicyResponseTypeDef,
-    GetPolicyResponseTypeDef,
-    GetProvisionedConcurrencyConfigResponseTypeDef,
-    GetRuntimeManagementConfigResponseTypeDef,
-    InvocationResponseTypeDef,
-    InvokeAsyncResponseTypeDef,
-    ListFunctionsByCodeSigningConfigResponseTypeDef,
-    ListTagsResponseTypeDef,
-    PutFunctionCodeSigningConfigResponseTypeDef,
-    PutProvisionedConcurrencyConfigResponseTypeDef,
-    PutRuntimeManagementConfigResponseTypeDef,
     AliasConfigurationResponseMetadataTypeDef,
     AliasConfigurationTypeDef,
     CreateAliasRequestRequestTypeDef,
     UpdateAliasRequestRequestTypeDef,
     CodeSigningConfigTypeDef,
     CreateCodeSigningConfigRequestRequestTypeDef,
     UpdateCodeSigningConfigRequestRequestTypeDef,
@@ -561,28 +579,18 @@
     GetFunctionConfigurationRequestPublishedVersionActiveWaitTypeDef,
     GetFunctionRequestFunctionActiveV2WaitTypeDef,
     GetFunctionRequestFunctionExistsWaitTypeDef,
     GetFunctionRequestFunctionUpdatedV2WaitTypeDef,
     GetLayerVersionResponseTypeDef,
     PublishLayerVersionResponseTypeDef,
     ImageConfigResponseTypeDef,
+    InvokeWithResponseStreamResponseEventTypeDef,
     PublishLayerVersionRequestRequestTypeDef,
     LayersListItemTypeDef,
     ListLayerVersionsResponseTypeDef,
-    ListAliasesRequestListAliasesPaginateTypeDef,
-    ListCodeSigningConfigsRequestListCodeSigningConfigsPaginateTypeDef,
-    ListEventSourceMappingsRequestListEventSourceMappingsPaginateTypeDef,
-    ListFunctionEventInvokeConfigsRequestListFunctionEventInvokeConfigsPaginateTypeDef,
-    ListFunctionUrlConfigsRequestListFunctionUrlConfigsPaginateTypeDef,
-    ListFunctionsByCodeSigningConfigRequestListFunctionsByCodeSigningConfigPaginateTypeDef,
-    ListFunctionsRequestListFunctionsPaginateTypeDef,
-    ListLayerVersionsRequestListLayerVersionsPaginateTypeDef,
-    ListLayersRequestListLayersPaginateTypeDef,
-    ListProvisionedConcurrencyConfigsRequestListProvisionedConcurrencyConfigsPaginateTypeDef,
-    ListVersionsByFunctionRequestListVersionsByFunctionPaginateTypeDef,
     ListProvisionedConcurrencyConfigsResponseTypeDef,
     RuntimeVersionConfigTypeDef,
     ListAliasesResponseTypeDef,
     CreateCodeSigningConfigResponseTypeDef,
     GetCodeSigningConfigResponseTypeDef,
     ListCodeSigningConfigsResponseTypeDef,
     UpdateCodeSigningConfigResponseTypeDef,
@@ -591,14 +599,15 @@
     FunctionEventInvokeConfigTypeDef,
     PutFunctionEventInvokeConfigRequestRequestTypeDef,
     UpdateFunctionEventInvokeConfigRequestRequestTypeDef,
     CreateEventSourceMappingRequestRequestTypeDef,
     EventSourceMappingConfigurationResponseMetadataTypeDef,
     EventSourceMappingConfigurationTypeDef,
     UpdateEventSourceMappingRequestRequestTypeDef,
+    InvokeWithResponseStreamResponseTypeDef,
     ListLayersResponseTypeDef,
     FunctionConfigurationResponseMetadataTypeDef,
     FunctionConfigurationTypeDef,
     ListFunctionEventInvokeConfigsResponseTypeDef,
     ListEventSourceMappingsResponseTypeDef,
     GetFunctionResponseTypeDef,
     ListFunctionsResponseTypeDef,
@@ -613,43 +622,43 @@
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

### Comparing `types-aiobotocore-lambda-2.5.0.post1/types_aiobotocore_lambda.egg-info/SOURCES.txt` & `types-aiobotocore-lambda-2.5.1/types_aiobotocore_lambda.egg-info/SOURCES.txt`

 * *Files identical despite different names*

