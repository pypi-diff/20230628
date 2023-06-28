# Comparing `tmp/types-aiobotocore-iotanalytics-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-iotanalytics-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-iotanalytics-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:46 2023, max compression
+gzip compressed data, was "types-aiobotocore-iotanalytics-2.5.1.tar", last modified: Wed Jun 28 01:43:38 2023, max compression
```

## Comparing `types-aiobotocore-iotanalytics-2.5.0.post1.tar` & `types-aiobotocore-iotanalytics-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:46.587296 types-aiobotocore-iotanalytics-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:16:13.000000 types-aiobotocore-iotanalytics-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    18941 2023-03-11 12:26:46.587296 types-aiobotocore-iotanalytics-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    17350 2023-03-11 12:16:13.000000 types-aiobotocore-iotanalytics-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:46.587296 types-aiobotocore-iotanalytics-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2159 2023-03-11 12:16:13.000000 types-aiobotocore-iotanalytics-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:46.587296 types-aiobotocore-iotanalytics-2.5.0.post1/types_aiobotocore_iotanalytics/
--rw-r--r--   0 runner    (1001) docker     (123)     1473 2023-03-11 12:16:13.000000 types-aiobotocore-iotanalytics-2.5.0.post1/types_aiobotocore_iotanalytics/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1472 2023-03-11 12:16:13.000000 types-aiobotocore-iotanalytics-2.5.0.post1/types_aiobotocore_iotanalytics/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      963 2023-03-11 12:16:13.000000 types-aiobotocore-iotanalytics-2.5.0.post1/types_aiobotocore_iotanalytics/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    28254 2023-03-11 12:16:14.000000 types-aiobotocore-iotanalytics-2.5.0.post1/types_aiobotocore_iotanalytics/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    28206 2023-03-11 12:16:14.000000 types-aiobotocore-iotanalytics-2.5.0.post1/types_aiobotocore_iotanalytics/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8897 2023-03-11 12:16:14.000000 types-aiobotocore-iotanalytics-2.5.0.post1/types_aiobotocore_iotanalytics/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8895 2023-03-11 12:16:14.000000 types-aiobotocore-iotanalytics-2.5.0.post1/types_aiobotocore_iotanalytics/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     6725 2023-03-11 12:16:14.000000 types-aiobotocore-iotanalytics-2.5.0.post1/types_aiobotocore_iotanalytics/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     6717 2023-03-11 12:16:14.000000 types-aiobotocore-iotanalytics-2.5.0.post1/types_aiobotocore_iotanalytics/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:16:13.000000 types-aiobotocore-iotanalytics-2.5.0.post1/types_aiobotocore_iotanalytics/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    46204 2023-03-11 12:16:16.000000 types-aiobotocore-iotanalytics-2.5.0.post1/types_aiobotocore_iotanalytics/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    46133 2023-03-11 12:16:16.000000 types-aiobotocore-iotanalytics-2.5.0.post1/types_aiobotocore_iotanalytics/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:16:13.000000 types-aiobotocore-iotanalytics-2.5.0.post1/types_aiobotocore_iotanalytics/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:46.587296 types-aiobotocore-iotanalytics-2.5.0.post1/types_aiobotocore_iotanalytics.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    18941 2023-03-11 12:26:46.000000 types-aiobotocore-iotanalytics-2.5.0.post1/types_aiobotocore_iotanalytics.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      908 2023-03-11 12:26:46.000000 types-aiobotocore-iotanalytics-2.5.0.post1/types_aiobotocore_iotanalytics.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:46.000000 types-aiobotocore-iotanalytics-2.5.0.post1/types_aiobotocore_iotanalytics.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:46.000000 types-aiobotocore-iotanalytics-2.5.0.post1/types_aiobotocore_iotanalytics.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:46.000000 types-aiobotocore-iotanalytics-2.5.0.post1/types_aiobotocore_iotanalytics.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       31 2023-03-11 12:26:46.000000 types-aiobotocore-iotanalytics-2.5.0.post1/types_aiobotocore_iotanalytics.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:38.170153 types-aiobotocore-iotanalytics-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:32:52.000000 types-aiobotocore-iotanalytics-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    18938 2023-06-28 01:43:38.170153 types-aiobotocore-iotanalytics-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    17353 2023-06-28 01:32:52.000000 types-aiobotocore-iotanalytics-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:38.170153 types-aiobotocore-iotanalytics-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2153 2023-06-28 01:32:52.000000 types-aiobotocore-iotanalytics-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:38.170153 types-aiobotocore-iotanalytics-2.5.1/types_aiobotocore_iotanalytics/
+-rw-r--r--   0 runner    (1001) docker     (123)     1473 2023-06-28 01:32:52.000000 types-aiobotocore-iotanalytics-2.5.1/types_aiobotocore_iotanalytics/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1472 2023-06-28 01:32:52.000000 types-aiobotocore-iotanalytics-2.5.1/types_aiobotocore_iotanalytics/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      951 2023-06-28 01:32:52.000000 types-aiobotocore-iotanalytics-2.5.1/types_aiobotocore_iotanalytics/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    28254 2023-06-28 01:32:52.000000 types-aiobotocore-iotanalytics-2.5.1/types_aiobotocore_iotanalytics/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    28206 2023-06-28 01:32:52.000000 types-aiobotocore-iotanalytics-2.5.1/types_aiobotocore_iotanalytics/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9106 2023-06-28 01:32:52.000000 types-aiobotocore-iotanalytics-2.5.1/types_aiobotocore_iotanalytics/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9104 2023-06-28 01:32:52.000000 types-aiobotocore-iotanalytics-2.5.1/types_aiobotocore_iotanalytics/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     6615 2023-06-28 01:32:52.000000 types-aiobotocore-iotanalytics-2.5.1/types_aiobotocore_iotanalytics/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6608 2023-06-28 01:32:52.000000 types-aiobotocore-iotanalytics-2.5.1/types_aiobotocore_iotanalytics/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:32:52.000000 types-aiobotocore-iotanalytics-2.5.1/types_aiobotocore_iotanalytics/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    46258 2023-06-28 01:32:54.000000 types-aiobotocore-iotanalytics-2.5.1/types_aiobotocore_iotanalytics/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    46187 2023-06-28 01:32:54.000000 types-aiobotocore-iotanalytics-2.5.1/types_aiobotocore_iotanalytics/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:32:52.000000 types-aiobotocore-iotanalytics-2.5.1/types_aiobotocore_iotanalytics/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:38.170153 types-aiobotocore-iotanalytics-2.5.1/types_aiobotocore_iotanalytics.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    18938 2023-06-28 01:43:38.000000 types-aiobotocore-iotanalytics-2.5.1/types_aiobotocore_iotanalytics.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      908 2023-06-28 01:43:38.000000 types-aiobotocore-iotanalytics-2.5.1/types_aiobotocore_iotanalytics.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:38.000000 types-aiobotocore-iotanalytics-2.5.1/types_aiobotocore_iotanalytics.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:38.000000 types-aiobotocore-iotanalytics-2.5.1/types_aiobotocore_iotanalytics.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:38.000000 types-aiobotocore-iotanalytics-2.5.1/types_aiobotocore_iotanalytics.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       31 2023-06-28 01:43:38.000000 types-aiobotocore-iotanalytics-2.5.1/types_aiobotocore_iotanalytics.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-iotanalytics-2.5.0.post1/LICENSE` & `types-aiobotocore-iotanalytics-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-iotanalytics-2.5.0.post1/PKG-INFO` & `types-aiobotocore-iotanalytics-2.5.1/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-iotanalytics
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.IoTAnalytics 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.IoTAnalytics 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotanalytics/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-iotanalytics"></a>
 
 # types-aiobotocore-iotanalytics
 
 [![PyPI - types-aiobotocore-iotanalytics](https://img.shields.io/pypi/v/types-aiobotocore-iotanalytics.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotanalytics)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iotanalytics.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotanalytics)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotanalytics/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iotanalytics?color=blue)](https://pypistats.org/packages/types-aiobotocore-iotanalytics)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoTAnalytics 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics)
+[aiobotocore.IoTAnalytics 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics)
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
 [types-aiobotocore-iotanalytics docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotanalytics/).
 
 See how it helps to find and fix potential bugs:
 
@@ -342,27 +342,28 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_iotanalytics.type_defs import (
     AddAttributesActivityTypeDef,
     BatchPutMessageErrorEntryTypeDef,
     MessageTypeDef,
-    ResponseMetadataTypeDef,
     CancelPipelineReprocessingRequestRequestTypeDef,
     ChannelActivityTypeDef,
     ChannelMessagesTypeDef,
     EstimatedResourceSizeTypeDef,
     CustomerManagedChannelS3StorageSummaryTypeDef,
     CustomerManagedChannelS3StorageTypeDef,
     RetentionPeriodTypeDef,
     ColumnTypeDef,
     ResourceConfigurationTypeDef,
     TagTypeDef,
     CreateDatasetContentRequestRequestTypeDef,
+    CreateDatasetContentResponseTypeDef,
     VersioningConfigurationTypeDef,
+    CreatePipelineResponseTypeDef,
     CustomerManagedDatastoreS3StorageSummaryTypeDef,
     CustomerManagedDatastoreS3StorageTypeDef,
     DatasetActionSummaryTypeDef,
     IotEventsDestinationConfigurationTypeDef,
     DatasetContentStatusTypeDef,
     DatasetContentVersionValueTypeDef,
     DatasetEntryTypeDef,
@@ -383,40 +384,44 @@
     DescribeChannelRequestRequestTypeDef,
     DescribeDatasetRequestRequestTypeDef,
     DescribeDatastoreRequestRequestTypeDef,
     LoggingOptionsTypeDef,
     DescribePipelineRequestRequestTypeDef,
     DeviceRegistryEnrichActivityTypeDef,
     DeviceShadowEnrichActivityTypeDef,
+    EmptyResponseMetadataTypeDef,
     FilterActivityTypeDef,
     GetDatasetContentRequestRequestTypeDef,
     GlueConfigurationTypeDef,
     LambdaActivityTypeDef,
-    PaginatorConfigTypeDef,
+    ListChannelsRequestListChannelsPaginateTypeDef,
     ListChannelsRequestRequestTypeDef,
+    ListDatasetContentsRequestListDatasetContentsPaginateTypeDef,
     ListDatasetContentsRequestRequestTypeDef,
+    ListDatasetsRequestListDatasetsPaginateTypeDef,
     ListDatasetsRequestRequestTypeDef,
+    ListDatastoresRequestListDatastoresPaginateTypeDef,
     ListDatastoresRequestRequestTypeDef,
+    ListPipelinesRequestListPipelinesPaginateTypeDef,
     ListPipelinesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     MathActivityTypeDef,
     OutputFileUriValueTypeDef,
+    PaginatorConfigTypeDef,
     RemoveAttributesActivityTypeDef,
     SelectAttributesActivityTypeDef,
     ReprocessingSummaryTypeDef,
-    SampleChannelDataRequestRequestTypeDef,
-    UntagResourceRequestRequestTypeDef,
-    BatchPutMessageRequestRequestTypeDef,
-    BatchPutMessageResponseTypeDef,
-    CreateDatasetContentResponseTypeDef,
-    CreatePipelineResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
+    ResponseMetadataTypeDef,
     RunPipelineActivityResponseTypeDef,
+    SampleChannelDataRequestRequestTypeDef,
     SampleChannelDataResponseTypeDef,
     StartPipelineReprocessingResponseTypeDef,
+    UntagResourceRequestRequestTypeDef,
+    BatchPutMessageResponseTypeDef,
+    BatchPutMessageRequestRequestTypeDef,
     StartPipelineReprocessingRequestRequestTypeDef,
     ChannelStatisticsTypeDef,
     DatastoreStatisticsTypeDef,
     ChannelStorageSummaryTypeDef,
     ChannelStorageTypeDef,
     CreateChannelResponseTypeDef,
     CreateDatasetResponseTypeDef,
@@ -431,19 +436,14 @@
     DatastoreIotSiteWiseMultiLayerStorageTypeDef,
     DatastorePartitionTypeDef,
     LateDataRuleConfigurationTypeDef,
     QueryFilterTypeDef,
     DescribeLoggingOptionsResponseTypeDef,
     PutLoggingOptionsRequestRequestTypeDef,
     S3DestinationConfigurationTypeDef,
-    ListChannelsRequestListChannelsPaginateTypeDef,
-    ListDatasetContentsRequestListDatasetContentsPaginateTypeDef,
-    ListDatasetsRequestListDatasetsPaginateTypeDef,
-    ListDatastoresRequestListDatastoresPaginateTypeDef,
-    ListPipelinesRequestListPipelinesPaginateTypeDef,
     VariableTypeDef,
     PipelineActivityTypeDef,
     PipelineSummaryTypeDef,
     ChannelSummaryTypeDef,
     ChannelTypeDef,
     CreateChannelRequestRequestTypeDef,
     UpdateChannelRequestRequestTypeDef,
@@ -489,43 +489,43 @@
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

### Comparing `types-aiobotocore-iotanalytics-2.5.0.post1/README.md` & `types-aiobotocore-iotanalytics-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-iotanalytics"></a>
 
 # types-aiobotocore-iotanalytics
 
 [![PyPI - types-aiobotocore-iotanalytics](https://img.shields.io/pypi/v/types-aiobotocore-iotanalytics.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotanalytics)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iotanalytics.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotanalytics)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotanalytics/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iotanalytics?color=blue)](https://pypistats.org/packages/types-aiobotocore-iotanalytics)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoTAnalytics 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics)
+[aiobotocore.IoTAnalytics 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics)
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
 [types-aiobotocore-iotanalytics docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotanalytics/).
 
 See how it helps to find and fix potential bugs:
 
@@ -309,27 +309,28 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_iotanalytics.type_defs import (
     AddAttributesActivityTypeDef,
     BatchPutMessageErrorEntryTypeDef,
     MessageTypeDef,
-    ResponseMetadataTypeDef,
     CancelPipelineReprocessingRequestRequestTypeDef,
     ChannelActivityTypeDef,
     ChannelMessagesTypeDef,
     EstimatedResourceSizeTypeDef,
     CustomerManagedChannelS3StorageSummaryTypeDef,
     CustomerManagedChannelS3StorageTypeDef,
     RetentionPeriodTypeDef,
     ColumnTypeDef,
     ResourceConfigurationTypeDef,
     TagTypeDef,
     CreateDatasetContentRequestRequestTypeDef,
+    CreateDatasetContentResponseTypeDef,
     VersioningConfigurationTypeDef,
+    CreatePipelineResponseTypeDef,
     CustomerManagedDatastoreS3StorageSummaryTypeDef,
     CustomerManagedDatastoreS3StorageTypeDef,
     DatasetActionSummaryTypeDef,
     IotEventsDestinationConfigurationTypeDef,
     DatasetContentStatusTypeDef,
     DatasetContentVersionValueTypeDef,
     DatasetEntryTypeDef,
@@ -350,40 +351,44 @@
     DescribeChannelRequestRequestTypeDef,
     DescribeDatasetRequestRequestTypeDef,
     DescribeDatastoreRequestRequestTypeDef,
     LoggingOptionsTypeDef,
     DescribePipelineRequestRequestTypeDef,
     DeviceRegistryEnrichActivityTypeDef,
     DeviceShadowEnrichActivityTypeDef,
+    EmptyResponseMetadataTypeDef,
     FilterActivityTypeDef,
     GetDatasetContentRequestRequestTypeDef,
     GlueConfigurationTypeDef,
     LambdaActivityTypeDef,
-    PaginatorConfigTypeDef,
+    ListChannelsRequestListChannelsPaginateTypeDef,
     ListChannelsRequestRequestTypeDef,
+    ListDatasetContentsRequestListDatasetContentsPaginateTypeDef,
     ListDatasetContentsRequestRequestTypeDef,
+    ListDatasetsRequestListDatasetsPaginateTypeDef,
     ListDatasetsRequestRequestTypeDef,
+    ListDatastoresRequestListDatastoresPaginateTypeDef,
     ListDatastoresRequestRequestTypeDef,
+    ListPipelinesRequestListPipelinesPaginateTypeDef,
     ListPipelinesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     MathActivityTypeDef,
     OutputFileUriValueTypeDef,
+    PaginatorConfigTypeDef,
     RemoveAttributesActivityTypeDef,
     SelectAttributesActivityTypeDef,
     ReprocessingSummaryTypeDef,
-    SampleChannelDataRequestRequestTypeDef,
-    UntagResourceRequestRequestTypeDef,
-    BatchPutMessageRequestRequestTypeDef,
-    BatchPutMessageResponseTypeDef,
-    CreateDatasetContentResponseTypeDef,
-    CreatePipelineResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
+    ResponseMetadataTypeDef,
     RunPipelineActivityResponseTypeDef,
+    SampleChannelDataRequestRequestTypeDef,
     SampleChannelDataResponseTypeDef,
     StartPipelineReprocessingResponseTypeDef,
+    UntagResourceRequestRequestTypeDef,
+    BatchPutMessageResponseTypeDef,
+    BatchPutMessageRequestRequestTypeDef,
     StartPipelineReprocessingRequestRequestTypeDef,
     ChannelStatisticsTypeDef,
     DatastoreStatisticsTypeDef,
     ChannelStorageSummaryTypeDef,
     ChannelStorageTypeDef,
     CreateChannelResponseTypeDef,
     CreateDatasetResponseTypeDef,
@@ -398,19 +403,14 @@
     DatastoreIotSiteWiseMultiLayerStorageTypeDef,
     DatastorePartitionTypeDef,
     LateDataRuleConfigurationTypeDef,
     QueryFilterTypeDef,
     DescribeLoggingOptionsResponseTypeDef,
     PutLoggingOptionsRequestRequestTypeDef,
     S3DestinationConfigurationTypeDef,
-    ListChannelsRequestListChannelsPaginateTypeDef,
-    ListDatasetContentsRequestListDatasetContentsPaginateTypeDef,
-    ListDatasetsRequestListDatasetsPaginateTypeDef,
-    ListDatastoresRequestListDatastoresPaginateTypeDef,
-    ListPipelinesRequestListPipelinesPaginateTypeDef,
     VariableTypeDef,
     PipelineActivityTypeDef,
     PipelineSummaryTypeDef,
     ChannelSummaryTypeDef,
     ChannelTypeDef,
     CreateChannelRequestRequestTypeDef,
     UpdateChannelRequestRequestTypeDef,
@@ -456,43 +456,43 @@
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

### Comparing `types-aiobotocore-iotanalytics-2.5.0.post1/setup.py` & `types-aiobotocore-iotanalytics-2.5.1/setup.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-iotanalytics.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-iotanalytics",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_iotanalytics"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.IoTAnalytics 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.IoTAnalytics 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotanalytics/"
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

### Comparing `types-aiobotocore-iotanalytics-2.5.0.post1/types_aiobotocore_iotanalytics/__init__.py` & `types-aiobotocore-iotanalytics-2.5.1/types_aiobotocore_iotanalytics/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iotanalytics-2.5.0.post1/types_aiobotocore_iotanalytics/__init__.pyi` & `types-aiobotocore-iotanalytics-2.5.1/types_aiobotocore_iotanalytics/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iotanalytics-2.5.0.post1/types_aiobotocore_iotanalytics/__main__.py` & `types-aiobotocore-iotanalytics-2.5.1/types_aiobotocore_iotanalytics/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.IoTAnalytics 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.IoTAnalytics 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotanalytics//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics\nOther"
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

### Comparing `types-aiobotocore-iotanalytics-2.5.0.post1/types_aiobotocore_iotanalytics/client.py` & `types-aiobotocore-iotanalytics-2.5.1/types_aiobotocore_iotanalytics/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iotanalytics-2.5.0.post1/types_aiobotocore_iotanalytics/client.pyi` & `types-aiobotocore-iotanalytics-2.5.1/types_aiobotocore_iotanalytics/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iotanalytics-2.5.0.post1/types_aiobotocore_iotanalytics/literals.py` & `types-aiobotocore-iotanalytics-2.5.1/types_aiobotocore_iotanalytics/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -115,14 +115,15 @@
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
@@ -201,14 +202,15 @@
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
@@ -219,14 +221,15 @@
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
@@ -262,14 +265,15 @@
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
@@ -288,16 +292,19 @@
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
@@ -381,15 +388,17 @@
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

### Comparing `types-aiobotocore-iotanalytics-2.5.0.post1/types_aiobotocore_iotanalytics/literals.pyi` & `types-aiobotocore-iotanalytics-2.5.1/types_aiobotocore_iotanalytics/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -113,14 +113,15 @@
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
@@ -199,14 +200,15 @@
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
@@ -217,14 +219,15 @@
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
@@ -260,14 +263,15 @@
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
@@ -286,16 +290,19 @@
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
@@ -379,15 +386,17 @@
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

### Comparing `types-aiobotocore-iotanalytics-2.5.0.post1/types_aiobotocore_iotanalytics/paginator.py` & `types-aiobotocore-iotanalytics-2.5.1/types_aiobotocore_iotanalytics/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -24,36 +24,29 @@
         list_channels_paginator: ListChannelsPaginator = client.get_paginator("list_channels")
         list_dataset_contents_paginator: ListDatasetContentsPaginator = client.get_paginator("list_dataset_contents")
         list_datasets_paginator: ListDatasetsPaginator = client.get_paginator("list_datasets")
         list_datastores_paginator: ListDatastoresPaginator = client.get_paginator("list_datastores")
         list_pipelines_paginator: ListPipelinesPaginator = client.get_paginator("list_pipelines")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListChannelsResponseTypeDef,
     ListDatasetContentsResponseTypeDef,
     ListDatasetsResponseTypeDef,
     ListDatastoresResponseTypeDef,
     ListPipelinesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListChannelsPaginator",
     "ListDatasetContentsPaginator",
     "ListDatasetsPaginator",
     "ListDatastoresPaginator",
     "ListPipelinesPaginator",
 )
@@ -72,15 +65,15 @@
 class ListChannelsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Paginator.ListChannels)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotanalytics/paginators/#listchannelspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListChannelsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Paginator.ListChannels.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotanalytics/paginators/#listchannelspaginator)
         """
 
 
@@ -92,58 +85,58 @@
 
     def paginate(
         self,
         *,
         datasetName: str,
         scheduledOnOrAfter: Union[datetime, str] = ...,
         scheduledBefore: Union[datetime, str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDatasetContentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Paginator.ListDatasetContents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotanalytics/paginators/#listdatasetcontentspaginator)
         """
 
 
 class ListDatasetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Paginator.ListDatasets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotanalytics/paginators/#listdatasetspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDatasetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Paginator.ListDatasets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotanalytics/paginators/#listdatasetspaginator)
         """
 
 
 class ListDatastoresPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Paginator.ListDatastores)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotanalytics/paginators/#listdatastorespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDatastoresResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Paginator.ListDatastores.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotanalytics/paginators/#listdatastorespaginator)
         """
 
 
 class ListPipelinesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Paginator.ListPipelines)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotanalytics/paginators/#listpipelinespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPipelinesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Paginator.ListPipelines.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotanalytics/paginators/#listpipelinespaginator)
         """
```

### Comparing `types-aiobotocore-iotanalytics-2.5.0.post1/types_aiobotocore_iotanalytics/paginator.pyi` & `types-aiobotocore-iotanalytics-2.5.1/types_aiobotocore_iotanalytics/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -24,35 +24,29 @@
         list_channels_paginator: ListChannelsPaginator = client.get_paginator("list_channels")
         list_dataset_contents_paginator: ListDatasetContentsPaginator = client.get_paginator("list_dataset_contents")
         list_datasets_paginator: ListDatasetsPaginator = client.get_paginator("list_datasets")
         list_datastores_paginator: ListDatastoresPaginator = client.get_paginator("list_datastores")
         list_pipelines_paginator: ListPipelinesPaginator = client.get_paginator("list_pipelines")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListChannelsResponseTypeDef,
     ListDatasetContentsResponseTypeDef,
     ListDatasetsResponseTypeDef,
     ListDatastoresResponseTypeDef,
     ListPipelinesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListChannelsPaginator",
     "ListDatasetContentsPaginator",
     "ListDatasetsPaginator",
     "ListDatastoresPaginator",
     "ListPipelinesPaginator",
 )
@@ -68,15 +62,15 @@
 class ListChannelsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Paginator.ListChannels)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotanalytics/paginators/#listchannelspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListChannelsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Paginator.ListChannels.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotanalytics/paginators/#listchannelspaginator)
         """
 
 class ListDatasetContentsPaginator(AioPaginator):
@@ -87,55 +81,55 @@
 
     def paginate(
         self,
         *,
         datasetName: str,
         scheduledOnOrAfter: Union[datetime, str] = ...,
         scheduledBefore: Union[datetime, str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDatasetContentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Paginator.ListDatasetContents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotanalytics/paginators/#listdatasetcontentspaginator)
         """
 
 class ListDatasetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Paginator.ListDatasets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotanalytics/paginators/#listdatasetspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDatasetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Paginator.ListDatasets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotanalytics/paginators/#listdatasetspaginator)
         """
 
 class ListDatastoresPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Paginator.ListDatastores)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotanalytics/paginators/#listdatastorespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDatastoresResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Paginator.ListDatastores.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotanalytics/paginators/#listdatastorespaginator)
         """
 
 class ListPipelinesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Paginator.ListPipelines)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotanalytics/paginators/#listpipelinespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPipelinesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics.Paginator.ListPipelines.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotanalytics/paginators/#listpipelinespaginator)
         """
```

### Comparing `types-aiobotocore-iotanalytics-2.5.0.post1/types_aiobotocore_iotanalytics/type_defs.py` & `types-aiobotocore-iotanalytics-2.5.1/types_aiobotocore_iotanalytics/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -38,27 +38,28 @@
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AddAttributesActivityTypeDef",
     "BatchPutMessageErrorEntryTypeDef",
     "MessageTypeDef",
-    "ResponseMetadataTypeDef",
     "CancelPipelineReprocessingRequestRequestTypeDef",
     "ChannelActivityTypeDef",
     "ChannelMessagesTypeDef",
     "EstimatedResourceSizeTypeDef",
     "CustomerManagedChannelS3StorageSummaryTypeDef",
     "CustomerManagedChannelS3StorageTypeDef",
     "RetentionPeriodTypeDef",
     "ColumnTypeDef",
     "ResourceConfigurationTypeDef",
     "TagTypeDef",
     "CreateDatasetContentRequestRequestTypeDef",
+    "CreateDatasetContentResponseTypeDef",
     "VersioningConfigurationTypeDef",
+    "CreatePipelineResponseTypeDef",
     "CustomerManagedDatastoreS3StorageSummaryTypeDef",
     "CustomerManagedDatastoreS3StorageTypeDef",
     "DatasetActionSummaryTypeDef",
     "IotEventsDestinationConfigurationTypeDef",
     "DatasetContentStatusTypeDef",
     "DatasetContentVersionValueTypeDef",
     "DatasetEntryTypeDef",
@@ -79,40 +80,44 @@
     "DescribeChannelRequestRequestTypeDef",
     "DescribeDatasetRequestRequestTypeDef",
     "DescribeDatastoreRequestRequestTypeDef",
     "LoggingOptionsTypeDef",
     "DescribePipelineRequestRequestTypeDef",
     "DeviceRegistryEnrichActivityTypeDef",
     "DeviceShadowEnrichActivityTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "FilterActivityTypeDef",
     "GetDatasetContentRequestRequestTypeDef",
     "GlueConfigurationTypeDef",
     "LambdaActivityTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListChannelsRequestListChannelsPaginateTypeDef",
     "ListChannelsRequestRequestTypeDef",
+    "ListDatasetContentsRequestListDatasetContentsPaginateTypeDef",
     "ListDatasetContentsRequestRequestTypeDef",
+    "ListDatasetsRequestListDatasetsPaginateTypeDef",
     "ListDatasetsRequestRequestTypeDef",
+    "ListDatastoresRequestListDatastoresPaginateTypeDef",
     "ListDatastoresRequestRequestTypeDef",
+    "ListPipelinesRequestListPipelinesPaginateTypeDef",
     "ListPipelinesRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "MathActivityTypeDef",
     "OutputFileUriValueTypeDef",
+    "PaginatorConfigTypeDef",
     "RemoveAttributesActivityTypeDef",
     "SelectAttributesActivityTypeDef",
     "ReprocessingSummaryTypeDef",
-    "SampleChannelDataRequestRequestTypeDef",
-    "UntagResourceRequestRequestTypeDef",
-    "BatchPutMessageRequestRequestTypeDef",
-    "BatchPutMessageResponseTypeDef",
-    "CreateDatasetContentResponseTypeDef",
-    "CreatePipelineResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
+    "ResponseMetadataTypeDef",
     "RunPipelineActivityResponseTypeDef",
+    "SampleChannelDataRequestRequestTypeDef",
     "SampleChannelDataResponseTypeDef",
     "StartPipelineReprocessingResponseTypeDef",
+    "UntagResourceRequestRequestTypeDef",
+    "BatchPutMessageResponseTypeDef",
+    "BatchPutMessageRequestRequestTypeDef",
     "StartPipelineReprocessingRequestRequestTypeDef",
     "ChannelStatisticsTypeDef",
     "DatastoreStatisticsTypeDef",
     "ChannelStorageSummaryTypeDef",
     "ChannelStorageTypeDef",
     "CreateChannelResponseTypeDef",
     "CreateDatasetResponseTypeDef",
@@ -127,19 +132,14 @@
     "DatastoreIotSiteWiseMultiLayerStorageTypeDef",
     "DatastorePartitionTypeDef",
     "LateDataRuleConfigurationTypeDef",
     "QueryFilterTypeDef",
     "DescribeLoggingOptionsResponseTypeDef",
     "PutLoggingOptionsRequestRequestTypeDef",
     "S3DestinationConfigurationTypeDef",
-    "ListChannelsRequestListChannelsPaginateTypeDef",
-    "ListDatasetContentsRequestListDatasetContentsPaginateTypeDef",
-    "ListDatasetsRequestListDatasetsPaginateTypeDef",
-    "ListDatastoresRequestListDatastoresPaginateTypeDef",
-    "ListPipelinesRequestListPipelinesPaginateTypeDef",
     "VariableTypeDef",
     "PipelineActivityTypeDef",
     "PipelineSummaryTypeDef",
     "ChannelSummaryTypeDef",
     "ChannelTypeDef",
     "CreateChannelRequestRequestTypeDef",
     "UpdateChannelRequestRequestTypeDef",
@@ -213,25 +213,14 @@
     "MessageTypeDef",
     {
         "messageId": str,
         "payload": Union[str, bytes, IO[Any], StreamingBody],
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
 CancelPipelineReprocessingRequestRequestTypeDef = TypedDict(
     "CancelPipelineReprocessingRequestRequestTypeDef",
     {
         "pipelineName": str,
         "reprocessingId": str,
     },
 )
@@ -356,23 +345,40 @@
 class CreateDatasetContentRequestRequestTypeDef(
     _RequiredCreateDatasetContentRequestRequestTypeDef,
     _OptionalCreateDatasetContentRequestRequestTypeDef,
 ):
     pass
 
 
+CreateDatasetContentResponseTypeDef = TypedDict(
+    "CreateDatasetContentResponseTypeDef",
+    {
+        "versionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 VersioningConfigurationTypeDef = TypedDict(
     "VersioningConfigurationTypeDef",
     {
         "unlimited": bool,
         "maxVersions": int,
     },
     total=False,
 )
 
+CreatePipelineResponseTypeDef = TypedDict(
+    "CreatePipelineResponseTypeDef",
+    {
+        "pipelineName": str,
+        "pipelineArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CustomerManagedDatastoreS3StorageSummaryTypeDef = TypedDict(
     "CustomerManagedDatastoreS3StorageSummaryTypeDef",
     {
         "bucket": str,
         "keyPrefix": str,
         "roleArn": str,
     },
@@ -700,14 +706,21 @@
 
 class DeviceShadowEnrichActivityTypeDef(
     _RequiredDeviceShadowEnrichActivityTypeDef, _OptionalDeviceShadowEnrichActivityTypeDef
 ):
     pass
 
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredFilterActivityTypeDef = TypedDict(
     "_RequiredFilterActivityTypeDef",
     {
         "name": str,
         "filter": str,
     },
 )
@@ -770,33 +783,55 @@
 )
 
 
 class LambdaActivityTypeDef(_RequiredLambdaActivityTypeDef, _OptionalLambdaActivityTypeDef):
     pass
 
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListChannelsRequestListChannelsPaginateTypeDef = TypedDict(
+    "ListChannelsRequestListChannelsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListChannelsRequestRequestTypeDef = TypedDict(
     "ListChannelsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+_RequiredListDatasetContentsRequestListDatasetContentsPaginateTypeDef = TypedDict(
+    "_RequiredListDatasetContentsRequestListDatasetContentsPaginateTypeDef",
+    {
+        "datasetName": str,
+    },
+)
+_OptionalListDatasetContentsRequestListDatasetContentsPaginateTypeDef = TypedDict(
+    "_OptionalListDatasetContentsRequestListDatasetContentsPaginateTypeDef",
+    {
+        "scheduledOnOrAfter": Union[datetime, str],
+        "scheduledBefore": Union[datetime, str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListDatasetContentsRequestListDatasetContentsPaginateTypeDef(
+    _RequiredListDatasetContentsRequestListDatasetContentsPaginateTypeDef,
+    _OptionalListDatasetContentsRequestListDatasetContentsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListDatasetContentsRequestRequestTypeDef = TypedDict(
     "_RequiredListDatasetContentsRequestRequestTypeDef",
     {
         "datasetName": str,
     },
 )
 _OptionalListDatasetContentsRequestRequestTypeDef = TypedDict(
@@ -814,32 +849,56 @@
 class ListDatasetContentsRequestRequestTypeDef(
     _RequiredListDatasetContentsRequestRequestTypeDef,
     _OptionalListDatasetContentsRequestRequestTypeDef,
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
 )
 
+ListDatastoresRequestListDatastoresPaginateTypeDef = TypedDict(
+    "ListDatastoresRequestListDatastoresPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDatastoresRequestRequestTypeDef = TypedDict(
     "ListDatastoresRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListPipelinesRequestListPipelinesPaginateTypeDef = TypedDict(
+    "ListPipelinesRequestListPipelinesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListPipelinesRequestRequestTypeDef = TypedDict(
     "ListPipelinesRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
@@ -876,14 +935,24 @@
 OutputFileUriValueTypeDef = TypedDict(
     "OutputFileUriValueTypeDef",
     {
         "fileName": str,
     },
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
 _RequiredRemoveAttributesActivityTypeDef = TypedDict(
     "_RequiredRemoveAttributesActivityTypeDef",
     {
         "name": str,
         "attributes": Sequence[str],
     },
 )
@@ -930,14 +999,34 @@
         "id": str,
         "status": ReprocessingStatusType,
         "creationTime": datetime,
     },
     total=False,
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
+RunPipelineActivityResponseTypeDef = TypedDict(
+    "RunPipelineActivityResponseTypeDef",
+    {
+        "payloads": List[bytes],
+        "logResult": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredSampleChannelDataRequestRequestTypeDef = TypedDict(
     "_RequiredSampleChannelDataRequestRequestTypeDef",
     {
         "channelName": str,
     },
 )
 _OptionalSampleChannelDataRequestRequestTypeDef = TypedDict(
@@ -953,84 +1042,51 @@
 
 class SampleChannelDataRequestRequestTypeDef(
     _RequiredSampleChannelDataRequestRequestTypeDef, _OptionalSampleChannelDataRequestRequestTypeDef
 ):
     pass
 
 
-UntagResourceRequestRequestTypeDef = TypedDict(
-    "UntagResourceRequestRequestTypeDef",
-    {
-        "resourceArn": str,
-        "tagKeys": Sequence[str],
-    },
-)
-
-BatchPutMessageRequestRequestTypeDef = TypedDict(
-    "BatchPutMessageRequestRequestTypeDef",
-    {
-        "channelName": str,
-        "messages": Sequence[MessageTypeDef],
-    },
-)
-
-BatchPutMessageResponseTypeDef = TypedDict(
-    "BatchPutMessageResponseTypeDef",
-    {
-        "batchPutMessageErrorEntries": List[BatchPutMessageErrorEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDatasetContentResponseTypeDef = TypedDict(
-    "CreateDatasetContentResponseTypeDef",
-    {
-        "versionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreatePipelineResponseTypeDef = TypedDict(
-    "CreatePipelineResponseTypeDef",
+SampleChannelDataResponseTypeDef = TypedDict(
+    "SampleChannelDataResponseTypeDef",
     {
-        "pipelineName": str,
-        "pipelineArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "payloads": List[bytes],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
+StartPipelineReprocessingResponseTypeDef = TypedDict(
+    "StartPipelineReprocessingResponseTypeDef",
     {
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "reprocessingId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-RunPipelineActivityResponseTypeDef = TypedDict(
-    "RunPipelineActivityResponseTypeDef",
+UntagResourceRequestRequestTypeDef = TypedDict(
+    "UntagResourceRequestRequestTypeDef",
     {
-        "payloads": List[bytes],
-        "logResult": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "resourceArn": str,
+        "tagKeys": Sequence[str],
     },
 )
 
-SampleChannelDataResponseTypeDef = TypedDict(
-    "SampleChannelDataResponseTypeDef",
+BatchPutMessageResponseTypeDef = TypedDict(
+    "BatchPutMessageResponseTypeDef",
     {
-        "payloads": List[bytes],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "batchPutMessageErrorEntries": List[BatchPutMessageErrorEntryTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StartPipelineReprocessingResponseTypeDef = TypedDict(
-    "StartPipelineReprocessingResponseTypeDef",
+BatchPutMessageRequestRequestTypeDef = TypedDict(
+    "BatchPutMessageRequestRequestTypeDef",
     {
-        "reprocessingId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "channelName": str,
+        "messages": Sequence[MessageTypeDef],
     },
 )
 
 _RequiredStartPipelineReprocessingRequestRequestTypeDef = TypedDict(
     "_RequiredStartPipelineReprocessingRequestRequestTypeDef",
     {
         "pipelineName": str,
@@ -1090,35 +1146,35 @@
 
 CreateChannelResponseTypeDef = TypedDict(
     "CreateChannelResponseTypeDef",
     {
         "channelName": str,
         "channelArn": str,
         "retentionPeriod": RetentionPeriodTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDatasetResponseTypeDef = TypedDict(
     "CreateDatasetResponseTypeDef",
     {
         "datasetName": str,
         "datasetArn": str,
         "retentionPeriod": RetentionPeriodTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDatastoreResponseTypeDef = TypedDict(
     "CreateDatastoreResponseTypeDef",
     {
         "datastoreName": str,
         "datastoreArn": str,
         "retentionPeriod": RetentionPeriodTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SchemaDefinitionTypeDef = TypedDict(
     "SchemaDefinitionTypeDef",
     {
         "columns": Sequence[ColumnTypeDef],
@@ -1126,15 +1182,15 @@
     total=False,
 )
 
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
@@ -1156,15 +1212,15 @@
 
 GetDatasetContentResponseTypeDef = TypedDict(
     "GetDatasetContentResponseTypeDef",
     {
         "entries": List[DatasetEntryTypeDef],
         "timestamp": datetime,
         "status": DatasetContentStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DatasetTriggerTypeDef = TypedDict(
     "DatasetTriggerTypeDef",
     {
         "schedule": ScheduleTypeDef,
@@ -1213,15 +1269,15 @@
     total=False,
 )
 
 DescribeLoggingOptionsResponseTypeDef = TypedDict(
     "DescribeLoggingOptionsResponseTypeDef",
     {
         "loggingOptions": LoggingOptionsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutLoggingOptionsRequestRequestTypeDef = TypedDict(
     "PutLoggingOptionsRequestRequestTypeDef",
     {
         "loggingOptions": LoggingOptionsTypeDef,
@@ -1247,70 +1303,14 @@
 
 class S3DestinationConfigurationTypeDef(
     _RequiredS3DestinationConfigurationTypeDef, _OptionalS3DestinationConfigurationTypeDef
 ):
     pass
 
 
-ListChannelsRequestListChannelsPaginateTypeDef = TypedDict(
-    "ListChannelsRequestListChannelsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListDatasetContentsRequestListDatasetContentsPaginateTypeDef = TypedDict(
-    "_RequiredListDatasetContentsRequestListDatasetContentsPaginateTypeDef",
-    {
-        "datasetName": str,
-    },
-)
-_OptionalListDatasetContentsRequestListDatasetContentsPaginateTypeDef = TypedDict(
-    "_OptionalListDatasetContentsRequestListDatasetContentsPaginateTypeDef",
-    {
-        "scheduledOnOrAfter": Union[datetime, str],
-        "scheduledBefore": Union[datetime, str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListDatasetContentsRequestListDatasetContentsPaginateTypeDef(
-    _RequiredListDatasetContentsRequestListDatasetContentsPaginateTypeDef,
-    _OptionalListDatasetContentsRequestListDatasetContentsPaginateTypeDef,
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
-ListDatastoresRequestListDatastoresPaginateTypeDef = TypedDict(
-    "ListDatastoresRequestListDatastoresPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListPipelinesRequestListPipelinesPaginateTypeDef = TypedDict(
-    "ListPipelinesRequestListPipelinesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 _RequiredVariableTypeDef = TypedDict(
     "_RequiredVariableTypeDef",
     {
         "name": str,
     },
 )
 _OptionalVariableTypeDef = TypedDict(
@@ -1439,15 +1439,15 @@
 )
 
 ListDatasetContentsResponseTypeDef = TypedDict(
     "ListDatasetContentsResponseTypeDef",
     {
         "datasetContentSummaries": List[DatasetContentSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DatasetSummaryTypeDef = TypedDict(
     "DatasetSummaryTypeDef",
     {
         "datasetName": str,
@@ -1612,33 +1612,33 @@
 )
 
 ListPipelinesResponseTypeDef = TypedDict(
     "ListPipelinesResponseTypeDef",
     {
         "pipelineSummaries": List[PipelineSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListChannelsResponseTypeDef = TypedDict(
     "ListChannelsResponseTypeDef",
     {
         "channelSummaries": List[ChannelSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeChannelResponseTypeDef = TypedDict(
     "DescribeChannelResponseTypeDef",
     {
         "channel": ChannelTypeDef,
         "statistics": ChannelStatisticsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FileFormatConfigurationTypeDef = TypedDict(
     "FileFormatConfigurationTypeDef",
     {
         "jsonConfiguration": Mapping[str, Any],
@@ -1648,15 +1648,15 @@
 )
 
 ListDatasetsResponseTypeDef = TypedDict(
     "ListDatasetsResponseTypeDef",
     {
         "datasetSummaries": List[DatasetSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DatastoreSummaryTypeDef = TypedDict(
     "DatastoreSummaryTypeDef",
     {
         "datastoreName": str,
@@ -1702,15 +1702,15 @@
     total=False,
 )
 
 DescribePipelineResponseTypeDef = TypedDict(
     "DescribePipelineResponseTypeDef",
     {
         "pipeline": PipelineTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateDatastoreRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDatastoreRequestRequestTypeDef",
     {
         "datastoreName": str,
@@ -1776,15 +1776,15 @@
 
 
 ListDatastoresResponseTypeDef = TypedDict(
     "ListDatastoresResponseTypeDef",
     {
         "datastoreSummaries": List[DatastoreSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateDatasetRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDatasetRequestRequestTypeDef",
     {
         "datasetName": str,
@@ -1856,18 +1856,18 @@
 
 
 DescribeDatastoreResponseTypeDef = TypedDict(
     "DescribeDatastoreResponseTypeDef",
     {
         "datastore": DatastoreTypeDef,
         "statistics": DatastoreStatisticsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDatasetResponseTypeDef = TypedDict(
     "DescribeDatasetResponseTypeDef",
     {
         "dataset": DatasetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-iotanalytics-2.5.0.post1/types_aiobotocore_iotanalytics/type_defs.pyi` & `types-aiobotocore-iotanalytics-2.5.1/types_aiobotocore_iotanalytics/type_defs.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -37,27 +37,28 @@
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AddAttributesActivityTypeDef",
     "BatchPutMessageErrorEntryTypeDef",
     "MessageTypeDef",
-    "ResponseMetadataTypeDef",
     "CancelPipelineReprocessingRequestRequestTypeDef",
     "ChannelActivityTypeDef",
     "ChannelMessagesTypeDef",
     "EstimatedResourceSizeTypeDef",
     "CustomerManagedChannelS3StorageSummaryTypeDef",
     "CustomerManagedChannelS3StorageTypeDef",
     "RetentionPeriodTypeDef",
     "ColumnTypeDef",
     "ResourceConfigurationTypeDef",
     "TagTypeDef",
     "CreateDatasetContentRequestRequestTypeDef",
+    "CreateDatasetContentResponseTypeDef",
     "VersioningConfigurationTypeDef",
+    "CreatePipelineResponseTypeDef",
     "CustomerManagedDatastoreS3StorageSummaryTypeDef",
     "CustomerManagedDatastoreS3StorageTypeDef",
     "DatasetActionSummaryTypeDef",
     "IotEventsDestinationConfigurationTypeDef",
     "DatasetContentStatusTypeDef",
     "DatasetContentVersionValueTypeDef",
     "DatasetEntryTypeDef",
@@ -78,40 +79,44 @@
     "DescribeChannelRequestRequestTypeDef",
     "DescribeDatasetRequestRequestTypeDef",
     "DescribeDatastoreRequestRequestTypeDef",
     "LoggingOptionsTypeDef",
     "DescribePipelineRequestRequestTypeDef",
     "DeviceRegistryEnrichActivityTypeDef",
     "DeviceShadowEnrichActivityTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "FilterActivityTypeDef",
     "GetDatasetContentRequestRequestTypeDef",
     "GlueConfigurationTypeDef",
     "LambdaActivityTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListChannelsRequestListChannelsPaginateTypeDef",
     "ListChannelsRequestRequestTypeDef",
+    "ListDatasetContentsRequestListDatasetContentsPaginateTypeDef",
     "ListDatasetContentsRequestRequestTypeDef",
+    "ListDatasetsRequestListDatasetsPaginateTypeDef",
     "ListDatasetsRequestRequestTypeDef",
+    "ListDatastoresRequestListDatastoresPaginateTypeDef",
     "ListDatastoresRequestRequestTypeDef",
+    "ListPipelinesRequestListPipelinesPaginateTypeDef",
     "ListPipelinesRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "MathActivityTypeDef",
     "OutputFileUriValueTypeDef",
+    "PaginatorConfigTypeDef",
     "RemoveAttributesActivityTypeDef",
     "SelectAttributesActivityTypeDef",
     "ReprocessingSummaryTypeDef",
-    "SampleChannelDataRequestRequestTypeDef",
-    "UntagResourceRequestRequestTypeDef",
-    "BatchPutMessageRequestRequestTypeDef",
-    "BatchPutMessageResponseTypeDef",
-    "CreateDatasetContentResponseTypeDef",
-    "CreatePipelineResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
+    "ResponseMetadataTypeDef",
     "RunPipelineActivityResponseTypeDef",
+    "SampleChannelDataRequestRequestTypeDef",
     "SampleChannelDataResponseTypeDef",
     "StartPipelineReprocessingResponseTypeDef",
+    "UntagResourceRequestRequestTypeDef",
+    "BatchPutMessageResponseTypeDef",
+    "BatchPutMessageRequestRequestTypeDef",
     "StartPipelineReprocessingRequestRequestTypeDef",
     "ChannelStatisticsTypeDef",
     "DatastoreStatisticsTypeDef",
     "ChannelStorageSummaryTypeDef",
     "ChannelStorageTypeDef",
     "CreateChannelResponseTypeDef",
     "CreateDatasetResponseTypeDef",
@@ -126,19 +131,14 @@
     "DatastoreIotSiteWiseMultiLayerStorageTypeDef",
     "DatastorePartitionTypeDef",
     "LateDataRuleConfigurationTypeDef",
     "QueryFilterTypeDef",
     "DescribeLoggingOptionsResponseTypeDef",
     "PutLoggingOptionsRequestRequestTypeDef",
     "S3DestinationConfigurationTypeDef",
-    "ListChannelsRequestListChannelsPaginateTypeDef",
-    "ListDatasetContentsRequestListDatasetContentsPaginateTypeDef",
-    "ListDatasetsRequestListDatasetsPaginateTypeDef",
-    "ListDatastoresRequestListDatastoresPaginateTypeDef",
-    "ListPipelinesRequestListPipelinesPaginateTypeDef",
     "VariableTypeDef",
     "PipelineActivityTypeDef",
     "PipelineSummaryTypeDef",
     "ChannelSummaryTypeDef",
     "ChannelTypeDef",
     "CreateChannelRequestRequestTypeDef",
     "UpdateChannelRequestRequestTypeDef",
@@ -210,25 +210,14 @@
     "MessageTypeDef",
     {
         "messageId": str,
         "payload": Union[str, bytes, IO[Any], StreamingBody],
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
 CancelPipelineReprocessingRequestRequestTypeDef = TypedDict(
     "CancelPipelineReprocessingRequestRequestTypeDef",
     {
         "pipelineName": str,
         "reprocessingId": str,
     },
 )
@@ -347,23 +336,40 @@
 
 class CreateDatasetContentRequestRequestTypeDef(
     _RequiredCreateDatasetContentRequestRequestTypeDef,
     _OptionalCreateDatasetContentRequestRequestTypeDef,
 ):
     pass
 
+CreateDatasetContentResponseTypeDef = TypedDict(
+    "CreateDatasetContentResponseTypeDef",
+    {
+        "versionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 VersioningConfigurationTypeDef = TypedDict(
     "VersioningConfigurationTypeDef",
     {
         "unlimited": bool,
         "maxVersions": int,
     },
     total=False,
 )
 
+CreatePipelineResponseTypeDef = TypedDict(
+    "CreatePipelineResponseTypeDef",
+    {
+        "pipelineName": str,
+        "pipelineArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CustomerManagedDatastoreS3StorageSummaryTypeDef = TypedDict(
     "CustomerManagedDatastoreS3StorageSummaryTypeDef",
     {
         "bucket": str,
         "keyPrefix": str,
         "roleArn": str,
     },
@@ -675,14 +681,21 @@
 )
 
 class DeviceShadowEnrichActivityTypeDef(
     _RequiredDeviceShadowEnrichActivityTypeDef, _OptionalDeviceShadowEnrichActivityTypeDef
 ):
     pass
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredFilterActivityTypeDef = TypedDict(
     "_RequiredFilterActivityTypeDef",
     {
         "name": str,
         "filter": str,
     },
 )
@@ -739,33 +752,53 @@
     },
     total=False,
 )
 
 class LambdaActivityTypeDef(_RequiredLambdaActivityTypeDef, _OptionalLambdaActivityTypeDef):
     pass
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListChannelsRequestListChannelsPaginateTypeDef = TypedDict(
+    "ListChannelsRequestListChannelsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListChannelsRequestRequestTypeDef = TypedDict(
     "ListChannelsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+_RequiredListDatasetContentsRequestListDatasetContentsPaginateTypeDef = TypedDict(
+    "_RequiredListDatasetContentsRequestListDatasetContentsPaginateTypeDef",
+    {
+        "datasetName": str,
+    },
+)
+_OptionalListDatasetContentsRequestListDatasetContentsPaginateTypeDef = TypedDict(
+    "_OptionalListDatasetContentsRequestListDatasetContentsPaginateTypeDef",
+    {
+        "scheduledOnOrAfter": Union[datetime, str],
+        "scheduledBefore": Union[datetime, str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListDatasetContentsRequestListDatasetContentsPaginateTypeDef(
+    _RequiredListDatasetContentsRequestListDatasetContentsPaginateTypeDef,
+    _OptionalListDatasetContentsRequestListDatasetContentsPaginateTypeDef,
+):
+    pass
+
 _RequiredListDatasetContentsRequestRequestTypeDef = TypedDict(
     "_RequiredListDatasetContentsRequestRequestTypeDef",
     {
         "datasetName": str,
     },
 )
 _OptionalListDatasetContentsRequestRequestTypeDef = TypedDict(
@@ -781,32 +814,56 @@
 
 class ListDatasetContentsRequestRequestTypeDef(
     _RequiredListDatasetContentsRequestRequestTypeDef,
     _OptionalListDatasetContentsRequestRequestTypeDef,
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
 )
 
+ListDatastoresRequestListDatastoresPaginateTypeDef = TypedDict(
+    "ListDatastoresRequestListDatastoresPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDatastoresRequestRequestTypeDef = TypedDict(
     "ListDatastoresRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListPipelinesRequestListPipelinesPaginateTypeDef = TypedDict(
+    "ListPipelinesRequestListPipelinesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListPipelinesRequestRequestTypeDef = TypedDict(
     "ListPipelinesRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
@@ -841,14 +898,24 @@
 OutputFileUriValueTypeDef = TypedDict(
     "OutputFileUriValueTypeDef",
     {
         "fileName": str,
     },
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
 _RequiredRemoveAttributesActivityTypeDef = TypedDict(
     "_RequiredRemoveAttributesActivityTypeDef",
     {
         "name": str,
         "attributes": Sequence[str],
     },
 )
@@ -891,14 +958,34 @@
         "id": str,
         "status": ReprocessingStatusType,
         "creationTime": datetime,
     },
     total=False,
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
+RunPipelineActivityResponseTypeDef = TypedDict(
+    "RunPipelineActivityResponseTypeDef",
+    {
+        "payloads": List[bytes],
+        "logResult": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredSampleChannelDataRequestRequestTypeDef = TypedDict(
     "_RequiredSampleChannelDataRequestRequestTypeDef",
     {
         "channelName": str,
     },
 )
 _OptionalSampleChannelDataRequestRequestTypeDef = TypedDict(
@@ -912,84 +999,51 @@
 )
 
 class SampleChannelDataRequestRequestTypeDef(
     _RequiredSampleChannelDataRequestRequestTypeDef, _OptionalSampleChannelDataRequestRequestTypeDef
 ):
     pass
 
-UntagResourceRequestRequestTypeDef = TypedDict(
-    "UntagResourceRequestRequestTypeDef",
-    {
-        "resourceArn": str,
-        "tagKeys": Sequence[str],
-    },
-)
-
-BatchPutMessageRequestRequestTypeDef = TypedDict(
-    "BatchPutMessageRequestRequestTypeDef",
-    {
-        "channelName": str,
-        "messages": Sequence[MessageTypeDef],
-    },
-)
-
-BatchPutMessageResponseTypeDef = TypedDict(
-    "BatchPutMessageResponseTypeDef",
-    {
-        "batchPutMessageErrorEntries": List[BatchPutMessageErrorEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDatasetContentResponseTypeDef = TypedDict(
-    "CreateDatasetContentResponseTypeDef",
-    {
-        "versionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreatePipelineResponseTypeDef = TypedDict(
-    "CreatePipelineResponseTypeDef",
+SampleChannelDataResponseTypeDef = TypedDict(
+    "SampleChannelDataResponseTypeDef",
     {
-        "pipelineName": str,
-        "pipelineArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "payloads": List[bytes],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
+StartPipelineReprocessingResponseTypeDef = TypedDict(
+    "StartPipelineReprocessingResponseTypeDef",
     {
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "reprocessingId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-RunPipelineActivityResponseTypeDef = TypedDict(
-    "RunPipelineActivityResponseTypeDef",
+UntagResourceRequestRequestTypeDef = TypedDict(
+    "UntagResourceRequestRequestTypeDef",
     {
-        "payloads": List[bytes],
-        "logResult": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "resourceArn": str,
+        "tagKeys": Sequence[str],
     },
 )
 
-SampleChannelDataResponseTypeDef = TypedDict(
-    "SampleChannelDataResponseTypeDef",
+BatchPutMessageResponseTypeDef = TypedDict(
+    "BatchPutMessageResponseTypeDef",
     {
-        "payloads": List[bytes],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "batchPutMessageErrorEntries": List[BatchPutMessageErrorEntryTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StartPipelineReprocessingResponseTypeDef = TypedDict(
-    "StartPipelineReprocessingResponseTypeDef",
+BatchPutMessageRequestRequestTypeDef = TypedDict(
+    "BatchPutMessageRequestRequestTypeDef",
     {
-        "reprocessingId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "channelName": str,
+        "messages": Sequence[MessageTypeDef],
     },
 )
 
 _RequiredStartPipelineReprocessingRequestRequestTypeDef = TypedDict(
     "_RequiredStartPipelineReprocessingRequestRequestTypeDef",
     {
         "pipelineName": str,
@@ -1047,35 +1101,35 @@
 
 CreateChannelResponseTypeDef = TypedDict(
     "CreateChannelResponseTypeDef",
     {
         "channelName": str,
         "channelArn": str,
         "retentionPeriod": RetentionPeriodTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDatasetResponseTypeDef = TypedDict(
     "CreateDatasetResponseTypeDef",
     {
         "datasetName": str,
         "datasetArn": str,
         "retentionPeriod": RetentionPeriodTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDatastoreResponseTypeDef = TypedDict(
     "CreateDatastoreResponseTypeDef",
     {
         "datastoreName": str,
         "datastoreArn": str,
         "retentionPeriod": RetentionPeriodTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SchemaDefinitionTypeDef = TypedDict(
     "SchemaDefinitionTypeDef",
     {
         "columns": Sequence[ColumnTypeDef],
@@ -1083,15 +1137,15 @@
     total=False,
 )
 
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
@@ -1113,15 +1167,15 @@
 
 GetDatasetContentResponseTypeDef = TypedDict(
     "GetDatasetContentResponseTypeDef",
     {
         "entries": List[DatasetEntryTypeDef],
         "timestamp": datetime,
         "status": DatasetContentStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DatasetTriggerTypeDef = TypedDict(
     "DatasetTriggerTypeDef",
     {
         "schedule": ScheduleTypeDef,
@@ -1170,15 +1224,15 @@
     total=False,
 )
 
 DescribeLoggingOptionsResponseTypeDef = TypedDict(
     "DescribeLoggingOptionsResponseTypeDef",
     {
         "loggingOptions": LoggingOptionsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutLoggingOptionsRequestRequestTypeDef = TypedDict(
     "PutLoggingOptionsRequestRequestTypeDef",
     {
         "loggingOptions": LoggingOptionsTypeDef,
@@ -1202,68 +1256,14 @@
 )
 
 class S3DestinationConfigurationTypeDef(
     _RequiredS3DestinationConfigurationTypeDef, _OptionalS3DestinationConfigurationTypeDef
 ):
     pass
 
-ListChannelsRequestListChannelsPaginateTypeDef = TypedDict(
-    "ListChannelsRequestListChannelsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListDatasetContentsRequestListDatasetContentsPaginateTypeDef = TypedDict(
-    "_RequiredListDatasetContentsRequestListDatasetContentsPaginateTypeDef",
-    {
-        "datasetName": str,
-    },
-)
-_OptionalListDatasetContentsRequestListDatasetContentsPaginateTypeDef = TypedDict(
-    "_OptionalListDatasetContentsRequestListDatasetContentsPaginateTypeDef",
-    {
-        "scheduledOnOrAfter": Union[datetime, str],
-        "scheduledBefore": Union[datetime, str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListDatasetContentsRequestListDatasetContentsPaginateTypeDef(
-    _RequiredListDatasetContentsRequestListDatasetContentsPaginateTypeDef,
-    _OptionalListDatasetContentsRequestListDatasetContentsPaginateTypeDef,
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
-ListDatastoresRequestListDatastoresPaginateTypeDef = TypedDict(
-    "ListDatastoresRequestListDatastoresPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListPipelinesRequestListPipelinesPaginateTypeDef = TypedDict(
-    "ListPipelinesRequestListPipelinesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 _RequiredVariableTypeDef = TypedDict(
     "_RequiredVariableTypeDef",
     {
         "name": str,
     },
 )
 _OptionalVariableTypeDef = TypedDict(
@@ -1386,15 +1386,15 @@
 )
 
 ListDatasetContentsResponseTypeDef = TypedDict(
     "ListDatasetContentsResponseTypeDef",
     {
         "datasetContentSummaries": List[DatasetContentSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DatasetSummaryTypeDef = TypedDict(
     "DatasetSummaryTypeDef",
     {
         "datasetName": str,
@@ -1551,33 +1551,33 @@
 )
 
 ListPipelinesResponseTypeDef = TypedDict(
     "ListPipelinesResponseTypeDef",
     {
         "pipelineSummaries": List[PipelineSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListChannelsResponseTypeDef = TypedDict(
     "ListChannelsResponseTypeDef",
     {
         "channelSummaries": List[ChannelSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeChannelResponseTypeDef = TypedDict(
     "DescribeChannelResponseTypeDef",
     {
         "channel": ChannelTypeDef,
         "statistics": ChannelStatisticsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FileFormatConfigurationTypeDef = TypedDict(
     "FileFormatConfigurationTypeDef",
     {
         "jsonConfiguration": Mapping[str, Any],
@@ -1587,15 +1587,15 @@
 )
 
 ListDatasetsResponseTypeDef = TypedDict(
     "ListDatasetsResponseTypeDef",
     {
         "datasetSummaries": List[DatasetSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DatastoreSummaryTypeDef = TypedDict(
     "DatastoreSummaryTypeDef",
     {
         "datastoreName": str,
@@ -1639,15 +1639,15 @@
     total=False,
 )
 
 DescribePipelineResponseTypeDef = TypedDict(
     "DescribePipelineResponseTypeDef",
     {
         "pipeline": PipelineTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateDatastoreRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDatastoreRequestRequestTypeDef",
     {
         "datastoreName": str,
@@ -1709,15 +1709,15 @@
     pass
 
 ListDatastoresResponseTypeDef = TypedDict(
     "ListDatastoresResponseTypeDef",
     {
         "datastoreSummaries": List[DatastoreSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateDatasetRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDatasetRequestRequestTypeDef",
     {
         "datasetName": str,
@@ -1785,18 +1785,18 @@
     pass
 
 DescribeDatastoreResponseTypeDef = TypedDict(
     "DescribeDatastoreResponseTypeDef",
     {
         "datastore": DatastoreTypeDef,
         "statistics": DatastoreStatisticsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDatasetResponseTypeDef = TypedDict(
     "DescribeDatasetResponseTypeDef",
     {
         "dataset": DatasetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-iotanalytics-2.5.0.post1/types_aiobotocore_iotanalytics.egg-info/PKG-INFO` & `types-aiobotocore-iotanalytics-2.5.1/types_aiobotocore_iotanalytics.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-iotanalytics
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.IoTAnalytics 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.IoTAnalytics 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotanalytics/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-iotanalytics"></a>
 
 # types-aiobotocore-iotanalytics
 
 [![PyPI - types-aiobotocore-iotanalytics](https://img.shields.io/pypi/v/types-aiobotocore-iotanalytics.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotanalytics)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iotanalytics.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotanalytics)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotanalytics/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iotanalytics?color=blue)](https://pypistats.org/packages/types-aiobotocore-iotanalytics)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoTAnalytics 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics)
+[aiobotocore.IoTAnalytics 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotanalytics.html#IoTAnalytics)
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
 [types-aiobotocore-iotanalytics docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotanalytics/).
 
 See how it helps to find and fix potential bugs:
 
@@ -342,27 +342,28 @@
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_iotanalytics.type_defs import (
     AddAttributesActivityTypeDef,
     BatchPutMessageErrorEntryTypeDef,
     MessageTypeDef,
-    ResponseMetadataTypeDef,
     CancelPipelineReprocessingRequestRequestTypeDef,
     ChannelActivityTypeDef,
     ChannelMessagesTypeDef,
     EstimatedResourceSizeTypeDef,
     CustomerManagedChannelS3StorageSummaryTypeDef,
     CustomerManagedChannelS3StorageTypeDef,
     RetentionPeriodTypeDef,
     ColumnTypeDef,
     ResourceConfigurationTypeDef,
     TagTypeDef,
     CreateDatasetContentRequestRequestTypeDef,
+    CreateDatasetContentResponseTypeDef,
     VersioningConfigurationTypeDef,
+    CreatePipelineResponseTypeDef,
     CustomerManagedDatastoreS3StorageSummaryTypeDef,
     CustomerManagedDatastoreS3StorageTypeDef,
     DatasetActionSummaryTypeDef,
     IotEventsDestinationConfigurationTypeDef,
     DatasetContentStatusTypeDef,
     DatasetContentVersionValueTypeDef,
     DatasetEntryTypeDef,
@@ -383,40 +384,44 @@
     DescribeChannelRequestRequestTypeDef,
     DescribeDatasetRequestRequestTypeDef,
     DescribeDatastoreRequestRequestTypeDef,
     LoggingOptionsTypeDef,
     DescribePipelineRequestRequestTypeDef,
     DeviceRegistryEnrichActivityTypeDef,
     DeviceShadowEnrichActivityTypeDef,
+    EmptyResponseMetadataTypeDef,
     FilterActivityTypeDef,
     GetDatasetContentRequestRequestTypeDef,
     GlueConfigurationTypeDef,
     LambdaActivityTypeDef,
-    PaginatorConfigTypeDef,
+    ListChannelsRequestListChannelsPaginateTypeDef,
     ListChannelsRequestRequestTypeDef,
+    ListDatasetContentsRequestListDatasetContentsPaginateTypeDef,
     ListDatasetContentsRequestRequestTypeDef,
+    ListDatasetsRequestListDatasetsPaginateTypeDef,
     ListDatasetsRequestRequestTypeDef,
+    ListDatastoresRequestListDatastoresPaginateTypeDef,
     ListDatastoresRequestRequestTypeDef,
+    ListPipelinesRequestListPipelinesPaginateTypeDef,
     ListPipelinesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     MathActivityTypeDef,
     OutputFileUriValueTypeDef,
+    PaginatorConfigTypeDef,
     RemoveAttributesActivityTypeDef,
     SelectAttributesActivityTypeDef,
     ReprocessingSummaryTypeDef,
-    SampleChannelDataRequestRequestTypeDef,
-    UntagResourceRequestRequestTypeDef,
-    BatchPutMessageRequestRequestTypeDef,
-    BatchPutMessageResponseTypeDef,
-    CreateDatasetContentResponseTypeDef,
-    CreatePipelineResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
+    ResponseMetadataTypeDef,
     RunPipelineActivityResponseTypeDef,
+    SampleChannelDataRequestRequestTypeDef,
     SampleChannelDataResponseTypeDef,
     StartPipelineReprocessingResponseTypeDef,
+    UntagResourceRequestRequestTypeDef,
+    BatchPutMessageResponseTypeDef,
+    BatchPutMessageRequestRequestTypeDef,
     StartPipelineReprocessingRequestRequestTypeDef,
     ChannelStatisticsTypeDef,
     DatastoreStatisticsTypeDef,
     ChannelStorageSummaryTypeDef,
     ChannelStorageTypeDef,
     CreateChannelResponseTypeDef,
     CreateDatasetResponseTypeDef,
@@ -431,19 +436,14 @@
     DatastoreIotSiteWiseMultiLayerStorageTypeDef,
     DatastorePartitionTypeDef,
     LateDataRuleConfigurationTypeDef,
     QueryFilterTypeDef,
     DescribeLoggingOptionsResponseTypeDef,
     PutLoggingOptionsRequestRequestTypeDef,
     S3DestinationConfigurationTypeDef,
-    ListChannelsRequestListChannelsPaginateTypeDef,
-    ListDatasetContentsRequestListDatasetContentsPaginateTypeDef,
-    ListDatasetsRequestListDatasetsPaginateTypeDef,
-    ListDatastoresRequestListDatastoresPaginateTypeDef,
-    ListPipelinesRequestListPipelinesPaginateTypeDef,
     VariableTypeDef,
     PipelineActivityTypeDef,
     PipelineSummaryTypeDef,
     ChannelSummaryTypeDef,
     ChannelTypeDef,
     CreateChannelRequestRequestTypeDef,
     UpdateChannelRequestRequestTypeDef,
@@ -489,43 +489,43 @@
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

### Comparing `types-aiobotocore-iotanalytics-2.5.0.post1/types_aiobotocore_iotanalytics.egg-info/SOURCES.txt` & `types-aiobotocore-iotanalytics-2.5.1/types_aiobotocore_iotanalytics.egg-info/SOURCES.txt`

 * *Files identical despite different names*

