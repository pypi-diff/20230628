# Comparing `tmp/types-aiobotocore-dynamodb-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-dynamodb-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-dynamodb-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:32 2023, max compression
+gzip compressed data, was "types-aiobotocore-dynamodb-2.5.1.tar", last modified: Wed Jun 28 01:43:24 2023, max compression
```

## Comparing `types-aiobotocore-dynamodb-2.5.0.post1.tar` & `types-aiobotocore-dynamodb-2.5.1.tar`

### file list

```diff
@@ -1,31 +1,31 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:32.239149 types-aiobotocore-dynamodb-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:12:50.000000 types-aiobotocore-dynamodb-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    28365 2023-03-11 12:26:32.239149 types-aiobotocore-dynamodb-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    26790 2023-03-11 12:12:50.000000 types-aiobotocore-dynamodb-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:32.239149 types-aiobotocore-dynamodb-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2131 2023-03-11 12:12:49.000000 types-aiobotocore-dynamodb-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:32.215149 types-aiobotocore-dynamodb-2.5.0.post1/types_aiobotocore_dynamodb/
--rw-r--r--   0 runner    (1001) docker     (123)     1813 2023-03-11 12:12:50.000000 types-aiobotocore-dynamodb-2.5.0.post1/types_aiobotocore_dynamodb/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1812 2023-03-11 12:12:50.000000 types-aiobotocore-dynamodb-2.5.0.post1/types_aiobotocore_dynamodb/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      947 2023-03-11 12:12:50.000000 types-aiobotocore-dynamodb-2.5.0.post1/types_aiobotocore_dynamodb/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    56287 2023-03-11 12:12:50.000000 types-aiobotocore-dynamodb-2.5.0.post1/types_aiobotocore_dynamodb/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    56218 2023-03-11 12:12:50.000000 types-aiobotocore-dynamodb-2.5.0.post1/types_aiobotocore_dynamodb/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    12657 2023-03-11 12:12:52.000000 types-aiobotocore-dynamodb-2.5.0.post1/types_aiobotocore_dynamodb/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    12655 2023-03-11 12:12:52.000000 types-aiobotocore-dynamodb-2.5.0.post1/types_aiobotocore_dynamodb/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8825 2023-03-11 12:12:52.000000 types-aiobotocore-dynamodb-2.5.0.post1/types_aiobotocore_dynamodb/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     8817 2023-03-11 12:12:51.000000 types-aiobotocore-dynamodb-2.5.0.post1/types_aiobotocore_dynamodb/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:12:50.000000 types-aiobotocore-dynamodb-2.5.0.post1/types_aiobotocore_dynamodb/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    29142 2023-03-11 12:12:51.000000 types-aiobotocore-dynamodb-2.5.0.post1/types_aiobotocore_dynamodb/service_resource.py
--rw-r--r--   0 runner    (1001) docker     (123)    29113 2023-03-11 12:12:50.000000 types-aiobotocore-dynamodb-2.5.0.post1/types_aiobotocore_dynamodb/service_resource.pyi
--rw-r--r--   0 runner    (1001) docker     (123)   151935 2023-03-11 12:12:56.000000 types-aiobotocore-dynamodb-2.5.0.post1/types_aiobotocore_dynamodb/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)   151782 2023-03-11 12:12:53.000000 types-aiobotocore-dynamodb-2.5.0.post1/types_aiobotocore_dynamodb/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:12:50.000000 types-aiobotocore-dynamodb-2.5.0.post1/types_aiobotocore_dynamodb/version.py
--rw-r--r--   0 runner    (1001) docker     (123)     2442 2023-03-11 12:12:52.000000 types-aiobotocore-dynamodb-2.5.0.post1/types_aiobotocore_dynamodb/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)     2440 2023-03-11 12:12:52.000000 types-aiobotocore-dynamodb-2.5.0.post1/types_aiobotocore_dynamodb/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:32.239149 types-aiobotocore-dynamodb-2.5.0.post1/types_aiobotocore_dynamodb.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    28365 2023-03-11 12:26:32.000000 types-aiobotocore-dynamodb-2.5.0.post1/types_aiobotocore_dynamodb.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1002 2023-03-11 12:26:32.000000 types-aiobotocore-dynamodb-2.5.0.post1/types_aiobotocore_dynamodb.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:32.000000 types-aiobotocore-dynamodb-2.5.0.post1/types_aiobotocore_dynamodb.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:32.000000 types-aiobotocore-dynamodb-2.5.0.post1/types_aiobotocore_dynamodb.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:32.000000 types-aiobotocore-dynamodb-2.5.0.post1/types_aiobotocore_dynamodb.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       27 2023-03-11 12:26:32.000000 types-aiobotocore-dynamodb-2.5.0.post1/types_aiobotocore_dynamodb.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:24.850128 types-aiobotocore-dynamodb-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:29:29.000000 types-aiobotocore-dynamodb-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    28333 2023-06-28 01:43:24.850128 types-aiobotocore-dynamodb-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    26764 2023-06-28 01:29:29.000000 types-aiobotocore-dynamodb-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:24.850128 types-aiobotocore-dynamodb-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2125 2023-06-28 01:29:29.000000 types-aiobotocore-dynamodb-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:24.842128 types-aiobotocore-dynamodb-2.5.1/types_aiobotocore_dynamodb/
+-rw-r--r--   0 runner    (1001) docker     (123)     1813 2023-06-28 01:29:29.000000 types-aiobotocore-dynamodb-2.5.1/types_aiobotocore_dynamodb/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1812 2023-06-28 01:29:29.000000 types-aiobotocore-dynamodb-2.5.1/types_aiobotocore_dynamodb/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      935 2023-06-28 01:29:29.000000 types-aiobotocore-dynamodb-2.5.1/types_aiobotocore_dynamodb/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    56380 2023-06-28 01:29:30.000000 types-aiobotocore-dynamodb-2.5.1/types_aiobotocore_dynamodb/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    56311 2023-06-28 01:29:29.000000 types-aiobotocore-dynamodb-2.5.1/types_aiobotocore_dynamodb/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    12866 2023-06-28 01:29:31.000000 types-aiobotocore-dynamodb-2.5.1/types_aiobotocore_dynamodb/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12864 2023-06-28 01:29:31.000000 types-aiobotocore-dynamodb-2.5.1/types_aiobotocore_dynamodb/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8715 2023-06-28 01:29:30.000000 types-aiobotocore-dynamodb-2.5.1/types_aiobotocore_dynamodb/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8708 2023-06-28 01:29:30.000000 types-aiobotocore-dynamodb-2.5.1/types_aiobotocore_dynamodb/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:29:29.000000 types-aiobotocore-dynamodb-2.5.1/types_aiobotocore_dynamodb/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    29167 2023-06-28 01:29:30.000000 types-aiobotocore-dynamodb-2.5.1/types_aiobotocore_dynamodb/service_resource.py
+-rw-r--r--   0 runner    (1001) docker     (123)    29138 2023-06-28 01:29:30.000000 types-aiobotocore-dynamodb-2.5.1/types_aiobotocore_dynamodb/service_resource.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)   152204 2023-06-28 01:29:34.000000 types-aiobotocore-dynamodb-2.5.1/types_aiobotocore_dynamodb/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)   152051 2023-06-28 01:29:32.000000 types-aiobotocore-dynamodb-2.5.1/types_aiobotocore_dynamodb/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:29:29.000000 types-aiobotocore-dynamodb-2.5.1/types_aiobotocore_dynamodb/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2442 2023-06-28 01:29:30.000000 types-aiobotocore-dynamodb-2.5.1/types_aiobotocore_dynamodb/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2440 2023-06-28 01:29:30.000000 types-aiobotocore-dynamodb-2.5.1/types_aiobotocore_dynamodb/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:24.850128 types-aiobotocore-dynamodb-2.5.1/types_aiobotocore_dynamodb.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    28333 2023-06-28 01:43:24.000000 types-aiobotocore-dynamodb-2.5.1/types_aiobotocore_dynamodb.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1002 2023-06-28 01:43:24.000000 types-aiobotocore-dynamodb-2.5.1/types_aiobotocore_dynamodb.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:24.000000 types-aiobotocore-dynamodb-2.5.1/types_aiobotocore_dynamodb.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:24.000000 types-aiobotocore-dynamodb-2.5.1/types_aiobotocore_dynamodb.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:24.000000 types-aiobotocore-dynamodb-2.5.1/types_aiobotocore_dynamodb.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       27 2023-06-28 01:43:24.000000 types-aiobotocore-dynamodb-2.5.1/types_aiobotocore_dynamodb.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-dynamodb-2.5.0.post1/LICENSE` & `types-aiobotocore-dynamodb-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-dynamodb-2.5.0.post1/PKG-INFO` & `types-aiobotocore-dynamodb-2.5.1/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-dynamodb
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.DynamoDB 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.DynamoDB 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodb/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-dynamodb"></a>
 
 # types-aiobotocore-dynamodb
 
 [![PyPI - types-aiobotocore-dynamodb](https://img.shields.io/pypi/v/types-aiobotocore-dynamodb.svg?color=blue)](https://pypi.org/project/types-aiobotocore-dynamodb)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-dynamodb.svg?color=blue)](https://pypi.org/project/types-aiobotocore-dynamodb)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodb/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-dynamodb?color=blue)](https://pypistats.org/packages/types-aiobotocore-dynamodb)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.DynamoDB 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodb.html#DynamoDB)
+[aiobotocore.DynamoDB 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodb.html#DynamoDB)
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
 [types-aiobotocore-dynamodb docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodb/).
 
 See how it helps to find and fix potential bugs:
 
@@ -457,15 +457,15 @@
 ### Typed dictionaries
 
 `types_aiobotocore_dynamodb.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_dynamodb.type_defs import (
-    ResponseMetadataTypeDef,
+    ArchivalSummaryResponseMetadataTypeDef,
     ArchivalSummaryTableTypeDef,
     ArchivalSummaryTypeDef,
     AttributeDefinitionServiceResourceTypeDef,
     AttributeDefinitionTableTypeDef,
     AttributeDefinitionTypeDef,
     AttributeValueTypeDef,
     AttributeValueUpdateTableTypeDef,
@@ -473,14 +473,15 @@
     AutoScalingTargetTrackingScalingPolicyConfigurationUpdateTypeDef,
     BackupDetailsTypeDef,
     BackupSummaryTableTypeDef,
     BackupSummaryTypeDef,
     KeysAndAttributesServiceResourceTypeDef,
     BatchStatementErrorTypeDef,
     ItemCollectionMetricsServiceResourceTypeDef,
+    BillingModeSummaryResponseMetadataTypeDef,
     BillingModeSummaryTableTypeDef,
     BillingModeSummaryTypeDef,
     CapacityServiceResourceTypeDef,
     CapacityTableTypeDef,
     CapacityTypeDef,
     ConditionTableTypeDef,
     PointInTimeRecoveryDescriptionTypeDef,
@@ -523,63 +524,64 @@
     DescribeExportInputRequestTypeDef,
     ExportDescriptionTypeDef,
     DescribeGlobalTableInputRequestTypeDef,
     DescribeGlobalTableSettingsInputRequestTypeDef,
     DescribeImportInputRequestTypeDef,
     DescribeKinesisStreamingDestinationInputRequestTypeDef,
     KinesisDataStreamDestinationTypeDef,
+    DescribeLimitsOutputTypeDef,
     DescribeTableInputRequestTypeDef,
     WaiterConfigTypeDef,
     DescribeTableReplicaAutoScalingInputRequestTypeDef,
     DescribeTimeToLiveInputRequestTypeDef,
     TimeToLiveDescriptionTypeDef,
+    EmptyResponseMetadataTypeDef,
     ExportSummaryTypeDef,
     ExportTableToPointInTimeInputRequestTypeDef,
     GetItemInputTableGetItemTypeDef,
     ProvisionedThroughputDescriptionTableTypeDef,
     ProvisionedThroughputDescriptionTypeDef,
     ProjectionServiceResourceTypeDef,
     S3BucketSourceTypeDef,
     KinesisStreamingDestinationInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    KinesisStreamingDestinationOutputTypeDef,
+    ListBackupsInputListBackupsPaginateTypeDef,
     ListBackupsInputRequestTypeDef,
     ListContributorInsightsInputRequestTypeDef,
     ListExportsInputRequestTypeDef,
     ListGlobalTablesInputRequestTypeDef,
     ListImportsInputRequestTypeDef,
+    ListTablesInputListTablesPaginateTypeDef,
     ListTablesInputRequestTypeDef,
+    ListTablesOutputTableTypeDef,
+    ListTablesOutputTypeDef,
+    ListTagsOfResourceInputListTagsOfResourcePaginateTypeDef,
     ListTagsOfResourceInputRequestTypeDef,
     TagTableTypeDef,
+    PaginatorConfigTypeDef,
     PointInTimeRecoverySpecificationTypeDef,
+    ProvisionedThroughputDescriptionResponseMetadataTypeDef,
     PutRequestServiceResourceTypeDef,
     TableClassSummaryTableTypeDef,
     TableClassSummaryTypeDef,
+    ResponseMetadataTypeDef,
+    RestoreSummaryResponseMetadataTypeDef,
     RestoreSummaryTableTypeDef,
     RestoreSummaryTypeDef,
+    SSEDescriptionResponseMetadataTypeDef,
     SSEDescriptionTableTypeDef,
     SSEDescriptionTypeDef,
     SSESpecificationTableTypeDef,
-    ServiceResourceTableRequestTypeDef,
+    StreamSpecificationResponseMetadataTypeDef,
     StreamSpecificationTableTypeDef,
     TableBatchWriterRequestTypeDef,
+    TableClassSummaryResponseMetadataTypeDef,
     TimeToLiveSpecificationTypeDef,
     UntagResourceInputRequestTypeDef,
     UpdateContributorInsightsInputRequestTypeDef,
-    ArchivalSummaryResponseMetadataTypeDef,
-    BillingModeSummaryResponseMetadataTypeDef,
-    DescribeLimitsOutputTypeDef,
-    EmptyResponseMetadataTypeDef,
-    KinesisStreamingDestinationOutputTypeDef,
-    ListTablesOutputTableTypeDef,
-    ListTablesOutputTypeDef,
-    ProvisionedThroughputDescriptionResponseMetadataTypeDef,
-    RestoreSummaryResponseMetadataTypeDef,
-    SSEDescriptionResponseMetadataTypeDef,
-    StreamSpecificationResponseMetadataTypeDef,
-    TableClassSummaryResponseMetadataTypeDef,
     UpdateContributorInsightsOutputTypeDef,
     AttributeValueUpdateTypeDef,
     BatchStatementRequestTypeDef,
     ConditionCheckTypeDef,
     ConditionTypeDef,
     DeleteRequestTypeDef,
     DeleteTypeDef,
@@ -600,15 +602,17 @@
     ListBackupsOutputTableTypeDef,
     ListBackupsOutputTypeDef,
     BatchGetItemInputServiceResourceBatchGetItemTypeDef,
     BatchStatementResponseTypeDef,
     ConsumedCapacityServiceResourceTypeDef,
     ConsumedCapacityTableTypeDef,
     ConsumedCapacityTypeDef,
+    QueryInputQueryPaginateTypeDef,
     QueryInputTableQueryTypeDef,
+    ScanInputScanPaginateTypeDef,
     ScanInputTableScanTypeDef,
     ContinuousBackupsDescriptionTypeDef,
     ListContributorInsightsOutputTypeDef,
     LocalSecondaryIndexDescriptionTableTypeDef,
     CreateGlobalSecondaryIndexActionTableTypeDef,
     UpdateGlobalSecondaryIndexActionTableTypeDef,
     LocalSecondaryIndexDescriptionTypeDef,
@@ -642,19 +646,14 @@
     DescribeTimeToLiveOutputTypeDef,
     ListExportsOutputTypeDef,
     GlobalSecondaryIndexDescriptionTableTypeDef,
     GlobalSecondaryIndexDescriptionTypeDef,
     GlobalSecondaryIndexServiceResourceTypeDef,
     LocalSecondaryIndexServiceResourceTypeDef,
     ImportSummaryTypeDef,
-    ListBackupsInputListBackupsPaginateTypeDef,
-    ListTablesInputListTablesPaginateTypeDef,
-    ListTagsOfResourceInputListTagsOfResourcePaginateTypeDef,
-    QueryInputQueryPaginateTypeDef,
-    ScanInputScanPaginateTypeDef,
     ListTagsOfResourceOutputTableTypeDef,
     UpdateContinuousBackupsInputRequestTypeDef,
     WriteRequestServiceResourceTypeDef,
     UpdateTimeToLiveInputRequestTypeDef,
     UpdateTimeToLiveOutputTypeDef,
     BatchExecuteStatementInputRequestTypeDef,
     QueryInputRequestTypeDef,
@@ -753,54 +752,54 @@
     UpdateTableReplicaAutoScalingInputRequestTypeDef,
     UpdateGlobalTableSettingsInputRequestTypeDef,
     DescribeTableReplicaAutoScalingOutputTypeDef,
     UpdateTableReplicaAutoScalingOutputTypeDef,
 )
 
 
-def get_structure() -> ResponseMetadataTypeDef:
+def get_structure() -> ArchivalSummaryResponseMetadataTypeDef:
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

### Comparing `types-aiobotocore-dynamodb-2.5.0.post1/README.md` & `types-aiobotocore-dynamodb-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-dynamodb"></a>
 
 # types-aiobotocore-dynamodb
 
 [![PyPI - types-aiobotocore-dynamodb](https://img.shields.io/pypi/v/types-aiobotocore-dynamodb.svg?color=blue)](https://pypi.org/project/types-aiobotocore-dynamodb)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-dynamodb.svg?color=blue)](https://pypi.org/project/types-aiobotocore-dynamodb)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodb/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-dynamodb?color=blue)](https://pypistats.org/packages/types-aiobotocore-dynamodb)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.DynamoDB 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodb.html#DynamoDB)
+[aiobotocore.DynamoDB 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodb.html#DynamoDB)
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
 [types-aiobotocore-dynamodb docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodb/).
 
 See how it helps to find and fix potential bugs:
 
@@ -424,15 +424,15 @@
 ### Typed dictionaries
 
 `types_aiobotocore_dynamodb.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_dynamodb.type_defs import (
-    ResponseMetadataTypeDef,
+    ArchivalSummaryResponseMetadataTypeDef,
     ArchivalSummaryTableTypeDef,
     ArchivalSummaryTypeDef,
     AttributeDefinitionServiceResourceTypeDef,
     AttributeDefinitionTableTypeDef,
     AttributeDefinitionTypeDef,
     AttributeValueTypeDef,
     AttributeValueUpdateTableTypeDef,
@@ -440,14 +440,15 @@
     AutoScalingTargetTrackingScalingPolicyConfigurationUpdateTypeDef,
     BackupDetailsTypeDef,
     BackupSummaryTableTypeDef,
     BackupSummaryTypeDef,
     KeysAndAttributesServiceResourceTypeDef,
     BatchStatementErrorTypeDef,
     ItemCollectionMetricsServiceResourceTypeDef,
+    BillingModeSummaryResponseMetadataTypeDef,
     BillingModeSummaryTableTypeDef,
     BillingModeSummaryTypeDef,
     CapacityServiceResourceTypeDef,
     CapacityTableTypeDef,
     CapacityTypeDef,
     ConditionTableTypeDef,
     PointInTimeRecoveryDescriptionTypeDef,
@@ -490,63 +491,64 @@
     DescribeExportInputRequestTypeDef,
     ExportDescriptionTypeDef,
     DescribeGlobalTableInputRequestTypeDef,
     DescribeGlobalTableSettingsInputRequestTypeDef,
     DescribeImportInputRequestTypeDef,
     DescribeKinesisStreamingDestinationInputRequestTypeDef,
     KinesisDataStreamDestinationTypeDef,
+    DescribeLimitsOutputTypeDef,
     DescribeTableInputRequestTypeDef,
     WaiterConfigTypeDef,
     DescribeTableReplicaAutoScalingInputRequestTypeDef,
     DescribeTimeToLiveInputRequestTypeDef,
     TimeToLiveDescriptionTypeDef,
+    EmptyResponseMetadataTypeDef,
     ExportSummaryTypeDef,
     ExportTableToPointInTimeInputRequestTypeDef,
     GetItemInputTableGetItemTypeDef,
     ProvisionedThroughputDescriptionTableTypeDef,
     ProvisionedThroughputDescriptionTypeDef,
     ProjectionServiceResourceTypeDef,
     S3BucketSourceTypeDef,
     KinesisStreamingDestinationInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    KinesisStreamingDestinationOutputTypeDef,
+    ListBackupsInputListBackupsPaginateTypeDef,
     ListBackupsInputRequestTypeDef,
     ListContributorInsightsInputRequestTypeDef,
     ListExportsInputRequestTypeDef,
     ListGlobalTablesInputRequestTypeDef,
     ListImportsInputRequestTypeDef,
+    ListTablesInputListTablesPaginateTypeDef,
     ListTablesInputRequestTypeDef,
+    ListTablesOutputTableTypeDef,
+    ListTablesOutputTypeDef,
+    ListTagsOfResourceInputListTagsOfResourcePaginateTypeDef,
     ListTagsOfResourceInputRequestTypeDef,
     TagTableTypeDef,
+    PaginatorConfigTypeDef,
     PointInTimeRecoverySpecificationTypeDef,
+    ProvisionedThroughputDescriptionResponseMetadataTypeDef,
     PutRequestServiceResourceTypeDef,
     TableClassSummaryTableTypeDef,
     TableClassSummaryTypeDef,
+    ResponseMetadataTypeDef,
+    RestoreSummaryResponseMetadataTypeDef,
     RestoreSummaryTableTypeDef,
     RestoreSummaryTypeDef,
+    SSEDescriptionResponseMetadataTypeDef,
     SSEDescriptionTableTypeDef,
     SSEDescriptionTypeDef,
     SSESpecificationTableTypeDef,
-    ServiceResourceTableRequestTypeDef,
+    StreamSpecificationResponseMetadataTypeDef,
     StreamSpecificationTableTypeDef,
     TableBatchWriterRequestTypeDef,
+    TableClassSummaryResponseMetadataTypeDef,
     TimeToLiveSpecificationTypeDef,
     UntagResourceInputRequestTypeDef,
     UpdateContributorInsightsInputRequestTypeDef,
-    ArchivalSummaryResponseMetadataTypeDef,
-    BillingModeSummaryResponseMetadataTypeDef,
-    DescribeLimitsOutputTypeDef,
-    EmptyResponseMetadataTypeDef,
-    KinesisStreamingDestinationOutputTypeDef,
-    ListTablesOutputTableTypeDef,
-    ListTablesOutputTypeDef,
-    ProvisionedThroughputDescriptionResponseMetadataTypeDef,
-    RestoreSummaryResponseMetadataTypeDef,
-    SSEDescriptionResponseMetadataTypeDef,
-    StreamSpecificationResponseMetadataTypeDef,
-    TableClassSummaryResponseMetadataTypeDef,
     UpdateContributorInsightsOutputTypeDef,
     AttributeValueUpdateTypeDef,
     BatchStatementRequestTypeDef,
     ConditionCheckTypeDef,
     ConditionTypeDef,
     DeleteRequestTypeDef,
     DeleteTypeDef,
@@ -567,15 +569,17 @@
     ListBackupsOutputTableTypeDef,
     ListBackupsOutputTypeDef,
     BatchGetItemInputServiceResourceBatchGetItemTypeDef,
     BatchStatementResponseTypeDef,
     ConsumedCapacityServiceResourceTypeDef,
     ConsumedCapacityTableTypeDef,
     ConsumedCapacityTypeDef,
+    QueryInputQueryPaginateTypeDef,
     QueryInputTableQueryTypeDef,
+    ScanInputScanPaginateTypeDef,
     ScanInputTableScanTypeDef,
     ContinuousBackupsDescriptionTypeDef,
     ListContributorInsightsOutputTypeDef,
     LocalSecondaryIndexDescriptionTableTypeDef,
     CreateGlobalSecondaryIndexActionTableTypeDef,
     UpdateGlobalSecondaryIndexActionTableTypeDef,
     LocalSecondaryIndexDescriptionTypeDef,
@@ -609,19 +613,14 @@
     DescribeTimeToLiveOutputTypeDef,
     ListExportsOutputTypeDef,
     GlobalSecondaryIndexDescriptionTableTypeDef,
     GlobalSecondaryIndexDescriptionTypeDef,
     GlobalSecondaryIndexServiceResourceTypeDef,
     LocalSecondaryIndexServiceResourceTypeDef,
     ImportSummaryTypeDef,
-    ListBackupsInputListBackupsPaginateTypeDef,
-    ListTablesInputListTablesPaginateTypeDef,
-    ListTagsOfResourceInputListTagsOfResourcePaginateTypeDef,
-    QueryInputQueryPaginateTypeDef,
-    ScanInputScanPaginateTypeDef,
     ListTagsOfResourceOutputTableTypeDef,
     UpdateContinuousBackupsInputRequestTypeDef,
     WriteRequestServiceResourceTypeDef,
     UpdateTimeToLiveInputRequestTypeDef,
     UpdateTimeToLiveOutputTypeDef,
     BatchExecuteStatementInputRequestTypeDef,
     QueryInputRequestTypeDef,
@@ -720,54 +719,54 @@
     UpdateTableReplicaAutoScalingInputRequestTypeDef,
     UpdateGlobalTableSettingsInputRequestTypeDef,
     DescribeTableReplicaAutoScalingOutputTypeDef,
     UpdateTableReplicaAutoScalingOutputTypeDef,
 )
 
 
-def get_structure() -> ResponseMetadataTypeDef:
+def get_structure() -> ArchivalSummaryResponseMetadataTypeDef:
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

### Comparing `types-aiobotocore-dynamodb-2.5.0.post1/setup.py` & `types-aiobotocore-dynamodb-2.5.1/setup.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-dynamodb.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-dynamodb",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_dynamodb"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.DynamoDB 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.DynamoDB 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodb/"
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

### Comparing `types-aiobotocore-dynamodb-2.5.0.post1/types_aiobotocore_dynamodb/__init__.py` & `types-aiobotocore-dynamodb-2.5.1/types_aiobotocore_dynamodb/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-dynamodb-2.5.0.post1/types_aiobotocore_dynamodb/__init__.pyi` & `types-aiobotocore-dynamodb-2.5.1/types_aiobotocore_dynamodb/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-dynamodb-2.5.0.post1/types_aiobotocore_dynamodb/__main__.py` & `types-aiobotocore-dynamodb-2.5.1/types_aiobotocore_dynamodb/__main__.py`

 * *Files 27% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.DynamoDB 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.DynamoDB 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodb//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodb.html#DynamoDB\nOther"
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

### Comparing `types-aiobotocore-dynamodb-2.5.0.post1/types_aiobotocore_dynamodb/client.py` & `types-aiobotocore-dynamodb-2.5.1/types_aiobotocore_dynamodb/client.py`

 * *Files 1% similar despite different names*

```diff
@@ -286,15 +286,16 @@
         LocalSecondaryIndexes: Sequence[LocalSecondaryIndexTypeDef] = ...,
         GlobalSecondaryIndexes: Sequence[GlobalSecondaryIndexTypeDef] = ...,
         BillingMode: BillingModeType = ...,
         ProvisionedThroughput: ProvisionedThroughputTypeDef = ...,
         StreamSpecification: StreamSpecificationTypeDef = ...,
         SSESpecification: SSESpecificationTypeDef = ...,
         Tags: Sequence[TagTypeDef] = ...,
-        TableClass: TableClassType = ...
+        TableClass: TableClassType = ...,
+        DeletionProtectionEnabled: bool = ...
     ) -> CreateTableOutputTypeDef:
         """
         The `CreateTable` operation adds a new table to your account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodb.html#DynamoDB.Client.create_table)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodb/client/#create_table)
         """
@@ -397,15 +398,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodb/client/#describe_continuous_backups)
         """
 
     async def describe_contributor_insights(
         self, *, TableName: str, IndexName: str = ...
     ) -> DescribeContributorInsightsOutputTypeDef:
         """
-        Returns information about contributor insights, for a given table or global
+        Returns information about contributor insights for a given table or global
         secondary index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodb.html#DynamoDB.Client.describe_contributor_insights)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodb/client/#describe_contributor_insights)
         """
 
     async def describe_endpoints(self) -> DescribeEndpointsResponseTypeDef:
@@ -1168,15 +1169,16 @@
         AttributeDefinitions: Sequence[AttributeDefinitionTypeDef] = ...,
         BillingMode: BillingModeType = ...,
         ProvisionedThroughput: ProvisionedThroughputTypeDef = ...,
         GlobalSecondaryIndexUpdates: Sequence[GlobalSecondaryIndexUpdateTypeDef] = ...,
         StreamSpecification: StreamSpecificationTypeDef = ...,
         SSESpecification: SSESpecificationTypeDef = ...,
         ReplicaUpdates: Sequence[ReplicationGroupUpdateTypeDef] = ...,
-        TableClass: TableClassType = ...
+        TableClass: TableClassType = ...,
+        DeletionProtectionEnabled: bool = ...
     ) -> UpdateTableOutputTypeDef:
         """
         Modifies the provisioned throughput settings, global secondary indexes, or
         DynamoDB Streams settings for a given table.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodb.html#DynamoDB.Client.update_table)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodb/client/#update_table)
```

### Comparing `types-aiobotocore-dynamodb-2.5.0.post1/types_aiobotocore_dynamodb/client.pyi` & `types-aiobotocore-dynamodb-2.5.1/types_aiobotocore_dynamodb/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -274,15 +274,16 @@
         LocalSecondaryIndexes: Sequence[LocalSecondaryIndexTypeDef] = ...,
         GlobalSecondaryIndexes: Sequence[GlobalSecondaryIndexTypeDef] = ...,
         BillingMode: BillingModeType = ...,
         ProvisionedThroughput: ProvisionedThroughputTypeDef = ...,
         StreamSpecification: StreamSpecificationTypeDef = ...,
         SSESpecification: SSESpecificationTypeDef = ...,
         Tags: Sequence[TagTypeDef] = ...,
-        TableClass: TableClassType = ...
+        TableClass: TableClassType = ...,
+        DeletionProtectionEnabled: bool = ...
     ) -> CreateTableOutputTypeDef:
         """
         The `CreateTable` operation adds a new table to your account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodb.html#DynamoDB.Client.create_table)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodb/client/#create_table)
         """
@@ -379,15 +380,15 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodb.html#DynamoDB.Client.describe_continuous_backups)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodb/client/#describe_continuous_backups)
         """
     async def describe_contributor_insights(
         self, *, TableName: str, IndexName: str = ...
     ) -> DescribeContributorInsightsOutputTypeDef:
         """
-        Returns information about contributor insights, for a given table or global
+        Returns information about contributor insights for a given table or global
         secondary index.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodb.html#DynamoDB.Client.describe_contributor_insights)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodb/client/#describe_contributor_insights)
         """
     async def describe_endpoints(self) -> DescribeEndpointsResponseTypeDef:
         """
@@ -1110,15 +1111,16 @@
         AttributeDefinitions: Sequence[AttributeDefinitionTypeDef] = ...,
         BillingMode: BillingModeType = ...,
         ProvisionedThroughput: ProvisionedThroughputTypeDef = ...,
         GlobalSecondaryIndexUpdates: Sequence[GlobalSecondaryIndexUpdateTypeDef] = ...,
         StreamSpecification: StreamSpecificationTypeDef = ...,
         SSESpecification: SSESpecificationTypeDef = ...,
         ReplicaUpdates: Sequence[ReplicationGroupUpdateTypeDef] = ...,
-        TableClass: TableClassType = ...
+        TableClass: TableClassType = ...,
+        DeletionProtectionEnabled: bool = ...
     ) -> UpdateTableOutputTypeDef:
         """
         Modifies the provisioned throughput settings, global secondary indexes, or
         DynamoDB Streams settings for a given table.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodb.html#DynamoDB.Client.update_table)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodb/client/#update_table)
```

### Comparing `types-aiobotocore-dynamodb-2.5.0.post1/types_aiobotocore_dynamodb/literals.py` & `types-aiobotocore-dynamodb-2.5.1/types_aiobotocore_dynamodb/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -216,14 +216,15 @@
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
@@ -302,14 +303,15 @@
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
@@ -320,14 +322,15 @@
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
@@ -363,14 +366,15 @@
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
@@ -389,16 +393,19 @@
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
@@ -482,15 +489,17 @@
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

### Comparing `types-aiobotocore-dynamodb-2.5.0.post1/types_aiobotocore_dynamodb/literals.pyi` & `types-aiobotocore-dynamodb-2.5.1/types_aiobotocore_dynamodb/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -214,14 +214,15 @@
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
@@ -300,14 +301,15 @@
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
@@ -318,14 +320,15 @@
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
@@ -361,14 +364,15 @@
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
@@ -387,16 +391,19 @@
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
@@ -480,15 +487,17 @@
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

### Comparing `types-aiobotocore-dynamodb-2.5.0.post1/types_aiobotocore_dynamodb/paginator.py` & `types-aiobotocore-dynamodb-2.5.1/types_aiobotocore_dynamodb/paginator.py`

 * *Files 3% similar despite different names*

```diff
@@ -24,18 +24,17 @@
         list_backups_paginator: ListBackupsPaginator = client.get_paginator("list_backups")
         list_tables_paginator: ListTablesPaginator = client.get_paginator("list_tables")
         list_tags_of_resource_paginator: ListTagsOfResourcePaginator = client.get_paginator("list_tags_of_resource")
         query_paginator: QueryPaginator = client.get_paginator("query")
         scan_paginator: ScanPaginator = client.get_paginator("scan")
     ```
 """
-import sys
 from datetime import datetime
 from decimal import Decimal
-from typing import Any, Generic, Iterator, Mapping, Sequence, Set, TypeVar, Union
+from typing import Any, AsyncIterator, Generic, Iterator, Mapping, Sequence, Set, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     BackupTypeFilterType,
     ConditionalOperatorType,
@@ -48,20 +47,14 @@
     ListTablesOutputTableTypeDef,
     ListTagsOfResourceOutputTableTypeDef,
     PaginatorConfigTypeDef,
     QueryOutputTableTypeDef,
     ScanOutputTableTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListBackupsPaginator",
     "ListTablesPaginator",
     "ListTagsOfResourcePaginator",
     "QueryPaginator",
     "ScanPaginator",
 )
@@ -86,45 +79,45 @@
     def paginate(
         self,
         *,
         TableName: str = ...,
         TimeRangeLowerBound: Union[datetime, str] = ...,
         TimeRangeUpperBound: Union[datetime, str] = ...,
         BackupType: BackupTypeFilterType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBackupsOutputTableTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodb.html#DynamoDB.Paginator.ListBackups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodb/paginators/#listbackupspaginator)
         """
 
 
 class ListTablesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodb.html#DynamoDB.Paginator.ListTables)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodb/paginators/#listtablespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTablesOutputTableTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodb.html#DynamoDB.Paginator.ListTables.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodb/paginators/#listtablespaginator)
         """
 
 
 class ListTagsOfResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodb.html#DynamoDB.Paginator.ListTagsOfResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodb/paginators/#listtagsofresourcepaginator)
     """
 
     def paginate(
-        self, *, ResourceArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ResourceArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsOfResourceOutputTableTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodb.html#DynamoDB.Paginator.ListTagsOfResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodb/paginators/#listtagsofresourcepaginator)
         """
 
 
@@ -166,15 +159,15 @@
                 Set[bytes],
                 Set[bytearray],
                 Sequence[Any],
                 Mapping[str, Any],
                 None,
             ],
         ] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[QueryOutputTableTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodb.html#DynamoDB.Paginator.Query.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodb/paginators/#querypaginator)
         """
 
 
@@ -215,13 +208,13 @@
                 Set[bytearray],
                 Sequence[Any],
                 Mapping[str, Any],
                 None,
             ],
         ] = ...,
         ConsistentRead: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ScanOutputTableTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodb.html#DynamoDB.Paginator.Scan.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodb/paginators/#scanpaginator)
         """
```

### Comparing `types-aiobotocore-dynamodb-2.5.0.post1/types_aiobotocore_dynamodb/paginator.pyi` & `types-aiobotocore-dynamodb-2.5.1/types_aiobotocore_dynamodb/paginator.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -24,18 +24,17 @@
         list_backups_paginator: ListBackupsPaginator = client.get_paginator("list_backups")
         list_tables_paginator: ListTablesPaginator = client.get_paginator("list_tables")
         list_tags_of_resource_paginator: ListTagsOfResourcePaginator = client.get_paginator("list_tags_of_resource")
         query_paginator: QueryPaginator = client.get_paginator("query")
         scan_paginator: ScanPaginator = client.get_paginator("scan")
     ```
 """
-import sys
 from datetime import datetime
 from decimal import Decimal
-from typing import Any, Generic, Iterator, Mapping, Sequence, Set, TypeVar, Union
+from typing import Any, AsyncIterator, Generic, Iterator, Mapping, Sequence, Set, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     BackupTypeFilterType,
     ConditionalOperatorType,
@@ -48,19 +47,14 @@
     ListTablesOutputTableTypeDef,
     ListTagsOfResourceOutputTableTypeDef,
     PaginatorConfigTypeDef,
     QueryOutputTableTypeDef,
     ScanOutputTableTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListBackupsPaginator",
     "ListTablesPaginator",
     "ListTagsOfResourcePaginator",
     "QueryPaginator",
     "ScanPaginator",
 )
@@ -82,43 +76,43 @@
     def paginate(
         self,
         *,
         TableName: str = ...,
         TimeRangeLowerBound: Union[datetime, str] = ...,
         TimeRangeUpperBound: Union[datetime, str] = ...,
         BackupType: BackupTypeFilterType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBackupsOutputTableTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodb.html#DynamoDB.Paginator.ListBackups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodb/paginators/#listbackupspaginator)
         """
 
 class ListTablesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodb.html#DynamoDB.Paginator.ListTables)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodb/paginators/#listtablespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTablesOutputTableTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodb.html#DynamoDB.Paginator.ListTables.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodb/paginators/#listtablespaginator)
         """
 
 class ListTagsOfResourcePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodb.html#DynamoDB.Paginator.ListTagsOfResource)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodb/paginators/#listtagsofresourcepaginator)
     """
 
     def paginate(
-        self, *, ResourceArn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ResourceArn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTagsOfResourceOutputTableTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodb.html#DynamoDB.Paginator.ListTagsOfResource.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodb/paginators/#listtagsofresourcepaginator)
         """
 
 class QueryPaginator(AioPaginator):
@@ -159,15 +153,15 @@
                 Set[bytes],
                 Set[bytearray],
                 Sequence[Any],
                 Mapping[str, Any],
                 None,
             ],
         ] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[QueryOutputTableTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodb.html#DynamoDB.Paginator.Query.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodb/paginators/#querypaginator)
         """
 
 class ScanPaginator(AioPaginator):
@@ -207,13 +201,13 @@
                 Set[bytearray],
                 Sequence[Any],
                 Mapping[str, Any],
                 None,
             ],
         ] = ...,
         ConsistentRead: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ScanOutputTableTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodb.html#DynamoDB.Paginator.Scan.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodb/paginators/#scanpaginator)
         """
```

### Comparing `types-aiobotocore-dynamodb-2.5.0.post1/types_aiobotocore_dynamodb/service_resource.py` & `types-aiobotocore-dynamodb-2.5.1/types_aiobotocore_dynamodb/service_resource.py`

 * *Files 2% similar despite different names*

```diff
@@ -14,18 +14,17 @@
     session = get_session()
     async with session.resource("dynamodb") as resource:
         resource: DynamoDBServiceResource
 
         my_table: dynamodb_resources.Table = resource.Table(...)
 ```
 """
-import sys
 from datetime import datetime
 from decimal import Decimal
-from typing import Any, Awaitable, List, Mapping, NoReturn, Sequence, Set, Union
+from typing import Any, AsyncIterator, Awaitable, List, Mapping, NoReturn, Sequence, Set, Union
 
 from .client import DynamoDBClient
 from .literals import (
     BillingModeType,
     ConditionalOperatorType,
     ReturnConsumedCapacityType,
     ReturnItemCollectionMetricsType,
@@ -80,18 +79,14 @@
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
     from boto3.dynamodb.conditions import ConditionBase
 except (ModuleNotFoundError, ImportError):
     from builtins import object as ConditionBase
 try:
     from boto3.dynamodb.table import BatchWriter
 except (ModuleNotFoundError, ImportError):
@@ -194,14 +189,15 @@
     latest_stream_arn: Awaitable[str]
     global_table_version: Awaitable[str]
     replicas: Awaitable[List[ReplicaDescriptionTableTypeDef]]
     restore_summary: Awaitable[RestoreSummaryResponseMetadataTypeDef]
     sse_description: Awaitable[SSEDescriptionResponseMetadataTypeDef]
     archival_summary: Awaitable[ArchivalSummaryResponseMetadataTypeDef]
     table_class_summary: Awaitable[TableClassSummaryResponseMetadataTypeDef]
+    deletion_protection_enabled: Awaitable[bool]
     name: str
 
     async def batch_writer(self, overwrite_by_pkeys: List[str] = ...) -> BatchWriter:
         """
         Create a batch writer object.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodb.html#DynamoDB.Table.batch_writer)
@@ -523,15 +519,16 @@
         AttributeDefinitions: Sequence[AttributeDefinitionTableTypeDef] = ...,
         BillingMode: BillingModeType = ...,
         ProvisionedThroughput: ProvisionedThroughputTableTypeDef = ...,
         GlobalSecondaryIndexUpdates: Sequence[GlobalSecondaryIndexUpdateTableTypeDef] = ...,
         StreamSpecification: StreamSpecificationTableTypeDef = ...,
         SSESpecification: SSESpecificationTableTypeDef = ...,
         ReplicaUpdates: Sequence[ReplicationGroupUpdateTableTypeDef] = ...,
-        TableClass: TableClassType = ...
+        TableClass: TableClassType = ...,
+        DeletionProtectionEnabled: bool = ...
     ) -> "_Table":
         """
         Modifies the provisioned throughput settings, global secondary indexes, or
         DynamoDB Streams settings for a given table.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodb.html#DynamoDB.Table.update)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodb/service_resource/#tableupdate-method)
@@ -675,15 +672,16 @@
         LocalSecondaryIndexes: Sequence[LocalSecondaryIndexServiceResourceTypeDef] = ...,
         GlobalSecondaryIndexes: Sequence[GlobalSecondaryIndexServiceResourceTypeDef] = ...,
         BillingMode: BillingModeType = ...,
         ProvisionedThroughput: ProvisionedThroughputServiceResourceTypeDef = ...,
         StreamSpecification: StreamSpecificationServiceResourceTypeDef = ...,
         SSESpecification: SSESpecificationServiceResourceTypeDef = ...,
         Tags: Sequence[TagServiceResourceTypeDef] = ...,
-        TableClass: TableClassType = ...
+        TableClass: TableClassType = ...,
+        DeletionProtectionEnabled: bool = ...
     ) -> _Table:
         """
         The `CreateTable` operation adds a new table to your account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodb.html#DynamoDB.ServiceResource.create_table)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodb/service_resource/#dynamodbserviceresourcecreate_table-method)
         """
```

### Comparing `types-aiobotocore-dynamodb-2.5.0.post1/types_aiobotocore_dynamodb/service_resource.pyi` & `types-aiobotocore-dynamodb-2.5.1/types_aiobotocore_dynamodb/service_resource.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -14,18 +14,17 @@
     session = get_session()
     async with session.resource("dynamodb") as resource:
         resource: DynamoDBServiceResource
 
         my_table: dynamodb_resources.Table = resource.Table(...)
 ```
 """
-import sys
 from datetime import datetime
 from decimal import Decimal
-from typing import Any, Awaitable, List, Mapping, NoReturn, Sequence, Set, Union
+from typing import Any, AsyncIterator, Awaitable, List, Mapping, NoReturn, Sequence, Set, Union
 
 from .client import DynamoDBClient
 from .literals import (
     BillingModeType,
     ConditionalOperatorType,
     ReturnConsumedCapacityType,
     ReturnItemCollectionMetricsType,
@@ -80,18 +79,14 @@
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
     from boto3.dynamodb.conditions import ConditionBase
 except (ModuleNotFoundError, ImportError):
     from builtins import object as ConditionBase
 try:
     from boto3.dynamodb.table import BatchWriter
 except (ModuleNotFoundError, ImportError):
@@ -185,14 +180,15 @@
     latest_stream_arn: Awaitable[str]
     global_table_version: Awaitable[str]
     replicas: Awaitable[List[ReplicaDescriptionTableTypeDef]]
     restore_summary: Awaitable[RestoreSummaryResponseMetadataTypeDef]
     sse_description: Awaitable[SSEDescriptionResponseMetadataTypeDef]
     archival_summary: Awaitable[ArchivalSummaryResponseMetadataTypeDef]
     table_class_summary: Awaitable[TableClassSummaryResponseMetadataTypeDef]
+    deletion_protection_enabled: Awaitable[bool]
     name: str
 
     async def batch_writer(self, overwrite_by_pkeys: List[str] = ...) -> BatchWriter:
         """
         Create a batch writer object.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodb.html#DynamoDB.Table.batch_writer)
@@ -504,15 +500,16 @@
         AttributeDefinitions: Sequence[AttributeDefinitionTableTypeDef] = ...,
         BillingMode: BillingModeType = ...,
         ProvisionedThroughput: ProvisionedThroughputTableTypeDef = ...,
         GlobalSecondaryIndexUpdates: Sequence[GlobalSecondaryIndexUpdateTableTypeDef] = ...,
         StreamSpecification: StreamSpecificationTableTypeDef = ...,
         SSESpecification: SSESpecificationTableTypeDef = ...,
         ReplicaUpdates: Sequence[ReplicationGroupUpdateTableTypeDef] = ...,
-        TableClass: TableClassType = ...
+        TableClass: TableClassType = ...,
+        DeletionProtectionEnabled: bool = ...
     ) -> "_Table":
         """
         Modifies the provisioned throughput settings, global secondary indexes, or
         DynamoDB Streams settings for a given table.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodb.html#DynamoDB.Table.update)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodb/service_resource/#tableupdate-method)
@@ -647,15 +644,16 @@
         LocalSecondaryIndexes: Sequence[LocalSecondaryIndexServiceResourceTypeDef] = ...,
         GlobalSecondaryIndexes: Sequence[GlobalSecondaryIndexServiceResourceTypeDef] = ...,
         BillingMode: BillingModeType = ...,
         ProvisionedThroughput: ProvisionedThroughputServiceResourceTypeDef = ...,
         StreamSpecification: StreamSpecificationServiceResourceTypeDef = ...,
         SSESpecification: SSESpecificationServiceResourceTypeDef = ...,
         Tags: Sequence[TagServiceResourceTypeDef] = ...,
-        TableClass: TableClassType = ...
+        TableClass: TableClassType = ...,
+        DeletionProtectionEnabled: bool = ...
     ) -> _Table:
         """
         The `CreateTable` operation adds a new table to your account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodb.html#DynamoDB.ServiceResource.create_table)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodb/service_resource/#dynamodbserviceresourcecreate_table-method)
         """
```

### Comparing `types-aiobotocore-dynamodb-2.5.0.post1/types_aiobotocore_dynamodb/type_defs.py` & `types-aiobotocore-dynamodb-2.5.1/types_aiobotocore_dynamodb/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -2,17 +2,17 @@
 Type annotations for dynamodb service type definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodb/type_defs/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_dynamodb.type_defs import ResponseMetadataTypeDef
+    from types_aiobotocore_dynamodb.type_defs import ArchivalSummaryResponseMetadataTypeDef
 
-    data: ResponseMetadataTypeDef = {...}
+    data: ArchivalSummaryResponseMetadataTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
 from decimal import Decimal
 from typing import Any, Dict, List, Mapping, Sequence, Set, Union
 
@@ -62,15 +62,15 @@
 try:
     from boto3.dynamodb.conditions import ConditionBase
 except (ModuleNotFoundError, ImportError):
     from builtins import object as ConditionBase
 
 
 __all__ = (
-    "ResponseMetadataTypeDef",
+    "ArchivalSummaryResponseMetadataTypeDef",
     "ArchivalSummaryTableTypeDef",
     "ArchivalSummaryTypeDef",
     "AttributeDefinitionServiceResourceTypeDef",
     "AttributeDefinitionTableTypeDef",
     "AttributeDefinitionTypeDef",
     "AttributeValueTypeDef",
     "AttributeValueUpdateTableTypeDef",
@@ -78,14 +78,15 @@
     "AutoScalingTargetTrackingScalingPolicyConfigurationUpdateTypeDef",
     "BackupDetailsTypeDef",
     "BackupSummaryTableTypeDef",
     "BackupSummaryTypeDef",
     "KeysAndAttributesServiceResourceTypeDef",
     "BatchStatementErrorTypeDef",
     "ItemCollectionMetricsServiceResourceTypeDef",
+    "BillingModeSummaryResponseMetadataTypeDef",
     "BillingModeSummaryTableTypeDef",
     "BillingModeSummaryTypeDef",
     "CapacityServiceResourceTypeDef",
     "CapacityTableTypeDef",
     "CapacityTypeDef",
     "ConditionTableTypeDef",
     "PointInTimeRecoveryDescriptionTypeDef",
@@ -128,63 +129,64 @@
     "DescribeExportInputRequestTypeDef",
     "ExportDescriptionTypeDef",
     "DescribeGlobalTableInputRequestTypeDef",
     "DescribeGlobalTableSettingsInputRequestTypeDef",
     "DescribeImportInputRequestTypeDef",
     "DescribeKinesisStreamingDestinationInputRequestTypeDef",
     "KinesisDataStreamDestinationTypeDef",
+    "DescribeLimitsOutputTypeDef",
     "DescribeTableInputRequestTypeDef",
     "WaiterConfigTypeDef",
     "DescribeTableReplicaAutoScalingInputRequestTypeDef",
     "DescribeTimeToLiveInputRequestTypeDef",
     "TimeToLiveDescriptionTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "ExportSummaryTypeDef",
     "ExportTableToPointInTimeInputRequestTypeDef",
     "GetItemInputTableGetItemTypeDef",
     "ProvisionedThroughputDescriptionTableTypeDef",
     "ProvisionedThroughputDescriptionTypeDef",
     "ProjectionServiceResourceTypeDef",
     "S3BucketSourceTypeDef",
     "KinesisStreamingDestinationInputRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "KinesisStreamingDestinationOutputTypeDef",
+    "ListBackupsInputListBackupsPaginateTypeDef",
     "ListBackupsInputRequestTypeDef",
     "ListContributorInsightsInputRequestTypeDef",
     "ListExportsInputRequestTypeDef",
     "ListGlobalTablesInputRequestTypeDef",
     "ListImportsInputRequestTypeDef",
+    "ListTablesInputListTablesPaginateTypeDef",
     "ListTablesInputRequestTypeDef",
+    "ListTablesOutputTableTypeDef",
+    "ListTablesOutputTypeDef",
+    "ListTagsOfResourceInputListTagsOfResourcePaginateTypeDef",
     "ListTagsOfResourceInputRequestTypeDef",
     "TagTableTypeDef",
+    "PaginatorConfigTypeDef",
     "PointInTimeRecoverySpecificationTypeDef",
+    "ProvisionedThroughputDescriptionResponseMetadataTypeDef",
     "PutRequestServiceResourceTypeDef",
     "TableClassSummaryTableTypeDef",
     "TableClassSummaryTypeDef",
+    "ResponseMetadataTypeDef",
+    "RestoreSummaryResponseMetadataTypeDef",
     "RestoreSummaryTableTypeDef",
     "RestoreSummaryTypeDef",
+    "SSEDescriptionResponseMetadataTypeDef",
     "SSEDescriptionTableTypeDef",
     "SSEDescriptionTypeDef",
     "SSESpecificationTableTypeDef",
-    "ServiceResourceTableRequestTypeDef",
+    "StreamSpecificationResponseMetadataTypeDef",
     "StreamSpecificationTableTypeDef",
     "TableBatchWriterRequestTypeDef",
+    "TableClassSummaryResponseMetadataTypeDef",
     "TimeToLiveSpecificationTypeDef",
     "UntagResourceInputRequestTypeDef",
     "UpdateContributorInsightsInputRequestTypeDef",
-    "ArchivalSummaryResponseMetadataTypeDef",
-    "BillingModeSummaryResponseMetadataTypeDef",
-    "DescribeLimitsOutputTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "KinesisStreamingDestinationOutputTypeDef",
-    "ListTablesOutputTableTypeDef",
-    "ListTablesOutputTypeDef",
-    "ProvisionedThroughputDescriptionResponseMetadataTypeDef",
-    "RestoreSummaryResponseMetadataTypeDef",
-    "SSEDescriptionResponseMetadataTypeDef",
-    "StreamSpecificationResponseMetadataTypeDef",
-    "TableClassSummaryResponseMetadataTypeDef",
     "UpdateContributorInsightsOutputTypeDef",
     "AttributeValueUpdateTypeDef",
     "BatchStatementRequestTypeDef",
     "ConditionCheckTypeDef",
     "ConditionTypeDef",
     "DeleteRequestTypeDef",
     "DeleteTypeDef",
@@ -205,15 +207,17 @@
     "ListBackupsOutputTableTypeDef",
     "ListBackupsOutputTypeDef",
     "BatchGetItemInputServiceResourceBatchGetItemTypeDef",
     "BatchStatementResponseTypeDef",
     "ConsumedCapacityServiceResourceTypeDef",
     "ConsumedCapacityTableTypeDef",
     "ConsumedCapacityTypeDef",
+    "QueryInputQueryPaginateTypeDef",
     "QueryInputTableQueryTypeDef",
+    "ScanInputScanPaginateTypeDef",
     "ScanInputTableScanTypeDef",
     "ContinuousBackupsDescriptionTypeDef",
     "ListContributorInsightsOutputTypeDef",
     "LocalSecondaryIndexDescriptionTableTypeDef",
     "CreateGlobalSecondaryIndexActionTableTypeDef",
     "UpdateGlobalSecondaryIndexActionTableTypeDef",
     "LocalSecondaryIndexDescriptionTypeDef",
@@ -247,19 +251,14 @@
     "DescribeTimeToLiveOutputTypeDef",
     "ListExportsOutputTypeDef",
     "GlobalSecondaryIndexDescriptionTableTypeDef",
     "GlobalSecondaryIndexDescriptionTypeDef",
     "GlobalSecondaryIndexServiceResourceTypeDef",
     "LocalSecondaryIndexServiceResourceTypeDef",
     "ImportSummaryTypeDef",
-    "ListBackupsInputListBackupsPaginateTypeDef",
-    "ListTablesInputListTablesPaginateTypeDef",
-    "ListTagsOfResourceInputListTagsOfResourcePaginateTypeDef",
-    "QueryInputQueryPaginateTypeDef",
-    "ScanInputScanPaginateTypeDef",
     "ListTagsOfResourceOutputTableTypeDef",
     "UpdateContinuousBackupsInputRequestTypeDef",
     "WriteRequestServiceResourceTypeDef",
     "UpdateTimeToLiveInputRequestTypeDef",
     "UpdateTimeToLiveOutputTypeDef",
     "BatchExecuteStatementInputRequestTypeDef",
     "QueryInputRequestTypeDef",
@@ -357,22 +356,21 @@
     "UpdateGlobalTableSettingsOutputTypeDef",
     "UpdateTableReplicaAutoScalingInputRequestTypeDef",
     "UpdateGlobalTableSettingsInputRequestTypeDef",
     "DescribeTableReplicaAutoScalingOutputTypeDef",
     "UpdateTableReplicaAutoScalingOutputTypeDef",
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+ArchivalSummaryResponseMetadataTypeDef = TypedDict(
+    "ArchivalSummaryResponseMetadataTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ArchivalDateTime": datetime,
+        "ArchivalReason": str,
+        "ArchivalBackupArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ArchivalSummaryTableTypeDef = TypedDict(
     "ArchivalSummaryTableTypeDef",
     {
         "ArchivalDateTime": datetime,
@@ -640,14 +638,23 @@
             ],
         ],
         "SizeEstimateRangeGB": List[float],
     },
     total=False,
 )
 
+BillingModeSummaryResponseMetadataTypeDef = TypedDict(
+    "BillingModeSummaryResponseMetadataTypeDef",
+    {
+        "BillingMode": BillingModeType,
+        "LastUpdateToPayPerRequestDateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 BillingModeSummaryTableTypeDef = TypedDict(
     "BillingModeSummaryTableTypeDef",
     {
         "BillingMode": BillingModeType,
         "LastUpdateToPayPerRequestDateTime": datetime,
     },
     total=False,
@@ -1205,14 +1212,25 @@
         "StreamArn": str,
         "DestinationStatus": DestinationStatusType,
         "DestinationStatusDescription": str,
     },
     total=False,
 )
 
+DescribeLimitsOutputTypeDef = TypedDict(
+    "DescribeLimitsOutputTypeDef",
+    {
+        "AccountMaxReadCapacityUnits": int,
+        "AccountMaxWriteCapacityUnits": int,
+        "TableMaxReadCapacityUnits": int,
+        "TableMaxWriteCapacityUnits": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeTableInputRequestTypeDef = TypedDict(
     "DescribeTableInputRequestTypeDef",
     {
         "TableName": str,
     },
 )
 
@@ -1244,14 +1262,21 @@
     {
         "TimeToLiveStatus": TimeToLiveStatusType,
         "AttributeName": str,
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
 ExportSummaryTypeDef = TypedDict(
     "ExportSummaryTypeDef",
     {
         "ExportArn": str,
         "ExportStatus": ExportStatusType,
     },
     total=False,
@@ -1386,20 +1411,32 @@
     "KinesisStreamingDestinationInputRequestTypeDef",
     {
         "TableName": str,
         "StreamArn": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+KinesisStreamingDestinationOutputTypeDef = TypedDict(
+    "KinesisStreamingDestinationOutputTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "TableName": str,
+        "StreamArn": str,
+        "DestinationStatus": DestinationStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListBackupsInputListBackupsPaginateTypeDef = TypedDict(
+    "ListBackupsInputListBackupsPaginateTypeDef",
+    {
+        "TableName": str,
+        "TimeRangeLowerBound": Union[datetime, str],
+        "TimeRangeUpperBound": Union[datetime, str],
+        "BackupType": BackupTypeFilterType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListBackupsInputRequestTypeDef = TypedDict(
     "ListBackupsInputRequestTypeDef",
     {
@@ -1449,23 +1486,71 @@
         "TableArn": str,
         "PageSize": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListTablesInputListTablesPaginateTypeDef = TypedDict(
+    "ListTablesInputListTablesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListTablesInputRequestTypeDef = TypedDict(
     "ListTablesInputRequestTypeDef",
     {
         "ExclusiveStartTableName": str,
         "Limit": int,
     },
     total=False,
 )
 
+ListTablesOutputTableTypeDef = TypedDict(
+    "ListTablesOutputTableTypeDef",
+    {
+        "TableNames": List[str],
+        "LastEvaluatedTableName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListTablesOutputTypeDef = TypedDict(
+    "ListTablesOutputTypeDef",
+    {
+        "TableNames": List[str],
+        "LastEvaluatedTableName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListTagsOfResourceInputListTagsOfResourcePaginateTypeDef = TypedDict(
+    "_RequiredListTagsOfResourceInputListTagsOfResourcePaginateTypeDef",
+    {
+        "ResourceArn": str,
+    },
+)
+_OptionalListTagsOfResourceInputListTagsOfResourcePaginateTypeDef = TypedDict(
+    "_OptionalListTagsOfResourceInputListTagsOfResourcePaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListTagsOfResourceInputListTagsOfResourcePaginateTypeDef(
+    _RequiredListTagsOfResourceInputListTagsOfResourcePaginateTypeDef,
+    _OptionalListTagsOfResourceInputListTagsOfResourcePaginateTypeDef,
+):
+    pass
+
+
 _RequiredListTagsOfResourceInputRequestTypeDef = TypedDict(
     "_RequiredListTagsOfResourceInputRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 _OptionalListTagsOfResourceInputRequestTypeDef = TypedDict(
@@ -1487,21 +1572,43 @@
     "TagTableTypeDef",
     {
         "Key": str,
         "Value": str,
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
 PointInTimeRecoverySpecificationTypeDef = TypedDict(
     "PointInTimeRecoverySpecificationTypeDef",
     {
         "PointInTimeRecoveryEnabled": bool,
     },
 )
 
+ProvisionedThroughputDescriptionResponseMetadataTypeDef = TypedDict(
+    "ProvisionedThroughputDescriptionResponseMetadataTypeDef",
+    {
+        "LastIncreaseDateTime": datetime,
+        "LastDecreaseDateTime": datetime,
+        "NumberOfDecreasesToday": int,
+        "ReadCapacityUnits": int,
+        "WriteCapacityUnits": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 PutRequestServiceResourceTypeDef = TypedDict(
     "PutRequestServiceResourceTypeDef",
     {
         "Item": Mapping[
             str,
             Union[
                 bytes,
@@ -1537,14 +1644,36 @@
     {
         "TableClass": TableClassType,
         "LastUpdateDateTime": datetime,
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
+RestoreSummaryResponseMetadataTypeDef = TypedDict(
+    "RestoreSummaryResponseMetadataTypeDef",
+    {
+        "SourceBackupArn": str,
+        "SourceTableArn": str,
+        "RestoreDateTime": datetime,
+        "RestoreInProgress": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredRestoreSummaryTableTypeDef = TypedDict(
     "_RequiredRestoreSummaryTableTypeDef",
     {
         "RestoreDateTime": datetime,
         "RestoreInProgress": bool,
     },
 )
@@ -1581,14 +1710,25 @@
 )
 
 
 class RestoreSummaryTypeDef(_RequiredRestoreSummaryTypeDef, _OptionalRestoreSummaryTypeDef):
     pass
 
 
+SSEDescriptionResponseMetadataTypeDef = TypedDict(
+    "SSEDescriptionResponseMetadataTypeDef",
+    {
+        "Status": SSEStatusType,
+        "SSEType": SSETypeType,
+        "KMSMasterKeyArn": str,
+        "InaccessibleEncryptionDateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 SSEDescriptionTableTypeDef = TypedDict(
     "SSEDescriptionTableTypeDef",
     {
         "Status": SSEStatusType,
         "SSEType": SSETypeType,
         "KMSMasterKeyArn": str,
         "InaccessibleEncryptionDateTime": datetime,
@@ -1613,18 +1753,20 @@
         "Enabled": bool,
         "SSEType": SSETypeType,
         "KMSMasterKeyId": str,
     },
     total=False,
 )
 
-ServiceResourceTableRequestTypeDef = TypedDict(
-    "ServiceResourceTableRequestTypeDef",
+StreamSpecificationResponseMetadataTypeDef = TypedDict(
+    "StreamSpecificationResponseMetadataTypeDef",
     {
-        "name": str,
+        "StreamEnabled": bool,
+        "StreamViewType": StreamViewTypeType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStreamSpecificationTableTypeDef = TypedDict(
     "_RequiredStreamSpecificationTableTypeDef",
     {
         "StreamEnabled": bool,
@@ -1649,14 +1791,23 @@
     "TableBatchWriterRequestTypeDef",
     {
         "overwrite_by_pkeys": List[str],
     },
     total=False,
 )
 
+TableClassSummaryResponseMetadataTypeDef = TypedDict(
+    "TableClassSummaryResponseMetadataTypeDef",
+    {
+        "TableClass": TableClassType,
+        "LastUpdateDateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TimeToLiveSpecificationTypeDef = TypedDict(
     "TimeToLiveSpecificationTypeDef",
     {
         "Enabled": bool,
         "AttributeName": str,
     },
 )
@@ -1688,138 +1839,21 @@
 class UpdateContributorInsightsInputRequestTypeDef(
     _RequiredUpdateContributorInsightsInputRequestTypeDef,
     _OptionalUpdateContributorInsightsInputRequestTypeDef,
 ):
     pass
 
 
-ArchivalSummaryResponseMetadataTypeDef = TypedDict(
-    "ArchivalSummaryResponseMetadataTypeDef",
-    {
-        "ArchivalDateTime": datetime,
-        "ArchivalReason": str,
-        "ArchivalBackupArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-BillingModeSummaryResponseMetadataTypeDef = TypedDict(
-    "BillingModeSummaryResponseMetadataTypeDef",
-    {
-        "BillingMode": BillingModeType,
-        "LastUpdateToPayPerRequestDateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeLimitsOutputTypeDef = TypedDict(
-    "DescribeLimitsOutputTypeDef",
-    {
-        "AccountMaxReadCapacityUnits": int,
-        "AccountMaxWriteCapacityUnits": int,
-        "TableMaxReadCapacityUnits": int,
-        "TableMaxWriteCapacityUnits": int,
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
-KinesisStreamingDestinationOutputTypeDef = TypedDict(
-    "KinesisStreamingDestinationOutputTypeDef",
-    {
-        "TableName": str,
-        "StreamArn": str,
-        "DestinationStatus": DestinationStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTablesOutputTableTypeDef = TypedDict(
-    "ListTablesOutputTableTypeDef",
-    {
-        "TableNames": List[str],
-        "LastEvaluatedTableName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTablesOutputTypeDef = TypedDict(
-    "ListTablesOutputTypeDef",
-    {
-        "TableNames": List[str],
-        "LastEvaluatedTableName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ProvisionedThroughputDescriptionResponseMetadataTypeDef = TypedDict(
-    "ProvisionedThroughputDescriptionResponseMetadataTypeDef",
-    {
-        "LastIncreaseDateTime": datetime,
-        "LastDecreaseDateTime": datetime,
-        "NumberOfDecreasesToday": int,
-        "ReadCapacityUnits": int,
-        "WriteCapacityUnits": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RestoreSummaryResponseMetadataTypeDef = TypedDict(
-    "RestoreSummaryResponseMetadataTypeDef",
-    {
-        "SourceBackupArn": str,
-        "SourceTableArn": str,
-        "RestoreDateTime": datetime,
-        "RestoreInProgress": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SSEDescriptionResponseMetadataTypeDef = TypedDict(
-    "SSEDescriptionResponseMetadataTypeDef",
-    {
-        "Status": SSEStatusType,
-        "SSEType": SSETypeType,
-        "KMSMasterKeyArn": str,
-        "InaccessibleEncryptionDateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StreamSpecificationResponseMetadataTypeDef = TypedDict(
-    "StreamSpecificationResponseMetadataTypeDef",
-    {
-        "StreamEnabled": bool,
-        "StreamViewType": StreamViewTypeType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-TableClassSummaryResponseMetadataTypeDef = TypedDict(
-    "TableClassSummaryResponseMetadataTypeDef",
-    {
-        "TableClass": TableClassType,
-        "LastUpdateDateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 UpdateContributorInsightsOutputTypeDef = TypedDict(
     "UpdateContributorInsightsOutputTypeDef",
     {
         "TableName": str,
         "IndexName": str,
         "ContributorInsightsStatus": ContributorInsightsStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AttributeValueUpdateTypeDef = TypedDict(
     "AttributeValueUpdateTypeDef",
     {
         "Value": Union[
@@ -2566,33 +2600,33 @@
     pass
 
 
 CreateBackupOutputTypeDef = TypedDict(
     "CreateBackupOutputTypeDef",
     {
         "BackupDetails": BackupDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListBackupsOutputTableTypeDef = TypedDict(
     "ListBackupsOutputTableTypeDef",
     {
         "BackupSummaries": List[BackupSummaryTableTypeDef],
         "LastEvaluatedBackupArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListBackupsOutputTypeDef = TypedDict(
     "ListBackupsOutputTypeDef",
     {
         "BackupSummaries": List[BackupSummaryTypeDef],
         "LastEvaluatedBackupArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredBatchGetItemInputServiceResourceBatchGetItemTypeDef = TypedDict(
     "_RequiredBatchGetItemInputServiceResourceBatchGetItemTypeDef",
     {
         "RequestItems": Mapping[str, KeysAndAttributesServiceResourceTypeDef],
@@ -2662,14 +2696,67 @@
         "Table": CapacityTypeDef,
         "LocalSecondaryIndexes": Dict[str, CapacityTypeDef],
         "GlobalSecondaryIndexes": Dict[str, CapacityTypeDef],
     },
     total=False,
 )
 
+_RequiredQueryInputQueryPaginateTypeDef = TypedDict(
+    "_RequiredQueryInputQueryPaginateTypeDef",
+    {
+        "TableName": str,
+    },
+)
+_OptionalQueryInputQueryPaginateTypeDef = TypedDict(
+    "_OptionalQueryInputQueryPaginateTypeDef",
+    {
+        "IndexName": str,
+        "Select": SelectType,
+        "AttributesToGet": Sequence[str],
+        "ConsistentRead": bool,
+        "KeyConditions": Mapping[str, ConditionTableTypeDef],
+        "QueryFilter": Mapping[str, ConditionTableTypeDef],
+        "ConditionalOperator": ConditionalOperatorType,
+        "ScanIndexForward": bool,
+        "ReturnConsumedCapacity": ReturnConsumedCapacityType,
+        "ProjectionExpression": str,
+        "FilterExpression": str,
+        "KeyConditionExpression": str,
+        "ExpressionAttributeNames": Mapping[str, str],
+        "ExpressionAttributeValues": Mapping[
+            str,
+            Union[
+                bytes,
+                bytearray,
+                str,
+                int,
+                Decimal,
+                bool,
+                Set[int],
+                Set[Decimal],
+                Set[str],
+                Set[bytes],
+                Set[bytearray],
+                Sequence[Any],
+                Mapping[str, Any],
+                None,
+            ],
+        ],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class QueryInputQueryPaginateTypeDef(
+    _RequiredQueryInputQueryPaginateTypeDef, _OptionalQueryInputQueryPaginateTypeDef
+):
+    pass
+
+
 QueryInputTableQueryTypeDef = TypedDict(
     "QueryInputTableQueryTypeDef",
     {
         "IndexName": str,
         "Select": SelectType,
         "AttributesToGet": Sequence[str],
         "Limit": int,
@@ -2721,14 +2808,66 @@
                 None,
             ],
         ],
     },
     total=False,
 )
 
+_RequiredScanInputScanPaginateTypeDef = TypedDict(
+    "_RequiredScanInputScanPaginateTypeDef",
+    {
+        "TableName": str,
+    },
+)
+_OptionalScanInputScanPaginateTypeDef = TypedDict(
+    "_OptionalScanInputScanPaginateTypeDef",
+    {
+        "IndexName": str,
+        "AttributesToGet": Sequence[str],
+        "Select": SelectType,
+        "ScanFilter": Mapping[str, ConditionTableTypeDef],
+        "ConditionalOperator": ConditionalOperatorType,
+        "ReturnConsumedCapacity": ReturnConsumedCapacityType,
+        "TotalSegments": int,
+        "Segment": int,
+        "ProjectionExpression": str,
+        "FilterExpression": str,
+        "ExpressionAttributeNames": Mapping[str, str],
+        "ExpressionAttributeValues": Mapping[
+            str,
+            Union[
+                bytes,
+                bytearray,
+                str,
+                int,
+                Decimal,
+                bool,
+                Set[int],
+                Set[Decimal],
+                Set[str],
+                Set[bytes],
+                Set[bytearray],
+                Sequence[Any],
+                Mapping[str, Any],
+                None,
+            ],
+        ],
+        "ConsistentRead": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ScanInputScanPaginateTypeDef(
+    _RequiredScanInputScanPaginateTypeDef, _OptionalScanInputScanPaginateTypeDef
+):
+    pass
+
+
 ScanInputTableScanTypeDef = TypedDict(
     "ScanInputTableScanTypeDef",
     {
         "IndexName": str,
         "AttributesToGet": Sequence[str],
         "Limit": int,
         "Select": SelectType,
@@ -2805,15 +2944,15 @@
 
 
 ListContributorInsightsOutputTypeDef = TypedDict(
     "ListContributorInsightsOutputTypeDef",
     {
         "ContributorInsightsSummaries": List[ContributorInsightsSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LocalSecondaryIndexDescriptionTableTypeDef = TypedDict(
     "LocalSecondaryIndexDescriptionTableTypeDef",
     {
         "IndexName": str,
@@ -3063,15 +3202,15 @@
 
 
 ListTagsOfResourceOutputTypeDef = TypedDict(
     "ListTagsOfResourceOutputTypeDef",
     {
         "Tags": List[TagTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceInputRequestTypeDef = TypedDict(
     "TagResourceInputRequestTypeDef",
     {
         "ResourceArn": str,
@@ -3295,48 +3434,48 @@
     {
         "TableName": str,
         "IndexName": str,
         "ContributorInsightsRuleList": List[str],
         "ContributorInsightsStatus": ContributorInsightsStatusType,
         "LastUpdateDateTime": datetime,
         "FailureException": FailureExceptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEndpointsResponseTypeDef = TypedDict(
     "DescribeEndpointsResponseTypeDef",
     {
         "Endpoints": List[EndpointTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeExportOutputTypeDef = TypedDict(
     "DescribeExportOutputTypeDef",
     {
         "ExportDescription": ExportDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ExportTableToPointInTimeOutputTypeDef = TypedDict(
     "ExportTableToPointInTimeOutputTypeDef",
     {
         "ExportDescription": ExportDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeKinesisStreamingDestinationOutputTypeDef = TypedDict(
     "DescribeKinesisStreamingDestinationOutputTypeDef",
     {
         "TableName": str,
         "KinesisDataStreamDestinations": List[KinesisDataStreamDestinationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDescribeTableInputTableExistsWaitTypeDef = TypedDict(
     "_RequiredDescribeTableInputTableExistsWaitTypeDef",
     {
         "TableName": str,
@@ -3380,24 +3519,24 @@
     pass
 
 
 DescribeTimeToLiveOutputTypeDef = TypedDict(
     "DescribeTimeToLiveOutputTypeDef",
     {
         "TimeToLiveDescription": TimeToLiveDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListExportsOutputTypeDef = TypedDict(
     "ListExportsOutputTypeDef",
     {
         "ExportSummaries": List[ExportSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GlobalSecondaryIndexDescriptionTableTypeDef = TypedDict(
     "GlobalSecondaryIndexDescriptionTableTypeDef",
     {
         "IndexName": str,
@@ -3473,167 +3612,20 @@
         "InputFormat": InputFormatType,
         "StartTime": datetime,
         "EndTime": datetime,
     },
     total=False,
 )
 
-ListBackupsInputListBackupsPaginateTypeDef = TypedDict(
-    "ListBackupsInputListBackupsPaginateTypeDef",
-    {
-        "TableName": str,
-        "TimeRangeLowerBound": Union[datetime, str],
-        "TimeRangeUpperBound": Union[datetime, str],
-        "BackupType": BackupTypeFilterType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListTablesInputListTablesPaginateTypeDef = TypedDict(
-    "ListTablesInputListTablesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListTagsOfResourceInputListTagsOfResourcePaginateTypeDef = TypedDict(
-    "_RequiredListTagsOfResourceInputListTagsOfResourcePaginateTypeDef",
-    {
-        "ResourceArn": str,
-    },
-)
-_OptionalListTagsOfResourceInputListTagsOfResourcePaginateTypeDef = TypedDict(
-    "_OptionalListTagsOfResourceInputListTagsOfResourcePaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListTagsOfResourceInputListTagsOfResourcePaginateTypeDef(
-    _RequiredListTagsOfResourceInputListTagsOfResourcePaginateTypeDef,
-    _OptionalListTagsOfResourceInputListTagsOfResourcePaginateTypeDef,
-):
-    pass
-
-
-_RequiredQueryInputQueryPaginateTypeDef = TypedDict(
-    "_RequiredQueryInputQueryPaginateTypeDef",
-    {
-        "TableName": str,
-    },
-)
-_OptionalQueryInputQueryPaginateTypeDef = TypedDict(
-    "_OptionalQueryInputQueryPaginateTypeDef",
-    {
-        "IndexName": str,
-        "Select": SelectType,
-        "AttributesToGet": Sequence[str],
-        "ConsistentRead": bool,
-        "KeyConditions": Mapping[str, ConditionTableTypeDef],
-        "QueryFilter": Mapping[str, ConditionTableTypeDef],
-        "ConditionalOperator": ConditionalOperatorType,
-        "ScanIndexForward": bool,
-        "ReturnConsumedCapacity": ReturnConsumedCapacityType,
-        "ProjectionExpression": str,
-        "FilterExpression": str,
-        "KeyConditionExpression": str,
-        "ExpressionAttributeNames": Mapping[str, str],
-        "ExpressionAttributeValues": Mapping[
-            str,
-            Union[
-                bytes,
-                bytearray,
-                str,
-                int,
-                Decimal,
-                bool,
-                Set[int],
-                Set[Decimal],
-                Set[str],
-                Set[bytes],
-                Set[bytearray],
-                Sequence[Any],
-                Mapping[str, Any],
-                None,
-            ],
-        ],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class QueryInputQueryPaginateTypeDef(
-    _RequiredQueryInputQueryPaginateTypeDef, _OptionalQueryInputQueryPaginateTypeDef
-):
-    pass
-
-
-_RequiredScanInputScanPaginateTypeDef = TypedDict(
-    "_RequiredScanInputScanPaginateTypeDef",
-    {
-        "TableName": str,
-    },
-)
-_OptionalScanInputScanPaginateTypeDef = TypedDict(
-    "_OptionalScanInputScanPaginateTypeDef",
-    {
-        "IndexName": str,
-        "AttributesToGet": Sequence[str],
-        "Select": SelectType,
-        "ScanFilter": Mapping[str, ConditionTableTypeDef],
-        "ConditionalOperator": ConditionalOperatorType,
-        "ReturnConsumedCapacity": ReturnConsumedCapacityType,
-        "TotalSegments": int,
-        "Segment": int,
-        "ProjectionExpression": str,
-        "FilterExpression": str,
-        "ExpressionAttributeNames": Mapping[str, str],
-        "ExpressionAttributeValues": Mapping[
-            str,
-            Union[
-                bytes,
-                bytearray,
-                str,
-                int,
-                Decimal,
-                bool,
-                Set[int],
-                Set[Decimal],
-                Set[str],
-                Set[bytes],
-                Set[bytearray],
-                Sequence[Any],
-                Mapping[str, Any],
-                None,
-            ],
-        ],
-        "ConsistentRead": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ScanInputScanPaginateTypeDef(
-    _RequiredScanInputScanPaginateTypeDef, _OptionalScanInputScanPaginateTypeDef
-):
-    pass
-
-
 ListTagsOfResourceOutputTableTypeDef = TypedDict(
     "ListTagsOfResourceOutputTableTypeDef",
     {
         "Tags": List[TagTableTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateContinuousBackupsInputRequestTypeDef = TypedDict(
     "UpdateContinuousBackupsInputRequestTypeDef",
     {
         "TableName": str,
@@ -3658,15 +3650,15 @@
     },
 )
 
 UpdateTimeToLiveOutputTypeDef = TypedDict(
     "UpdateTimeToLiveOutputTypeDef",
     {
         "TimeToLiveSpecification": TimeToLiveSpecificationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredBatchExecuteStatementInputRequestTypeDef = TypedDict(
     "_RequiredBatchExecuteStatementInputRequestTypeDef",
     {
         "Statements": Sequence[BatchStatementRequestTypeDef],
@@ -4175,15 +4167,15 @@
                         None,
                     ],
                 ]
             ],
         ],
         "UnprocessedKeys": Dict[str, KeysAndAttributesServiceResourceTypeDef],
         "ConsumedCapacity": List[ConsumedCapacityServiceResourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteItemOutputTableTypeDef = TypedDict(
     "DeleteItemOutputTableTypeDef",
     {
         "Attributes": Dict[
@@ -4203,15 +4195,15 @@
                 Sequence[Any],
                 Mapping[str, Any],
                 None,
             ],
         ],
         "ConsumedCapacity": ConsumedCapacityTableTypeDef,
         "ItemCollectionMetrics": ItemCollectionMetricsTableTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetItemOutputTableTypeDef = TypedDict(
     "GetItemOutputTableTypeDef",
     {
         "Item": Dict[
@@ -4230,15 +4222,15 @@
                 Set[bytearray],
                 Sequence[Any],
                 Mapping[str, Any],
                 None,
             ],
         ],
         "ConsumedCapacity": ConsumedCapacityTableTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutItemOutputTableTypeDef = TypedDict(
     "PutItemOutputTableTypeDef",
     {
         "Attributes": Dict[
@@ -4258,15 +4250,15 @@
                 Sequence[Any],
                 Mapping[str, Any],
                 None,
             ],
         ],
         "ConsumedCapacity": ConsumedCapacityTableTypeDef,
         "ItemCollectionMetrics": ItemCollectionMetricsTableTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 QueryOutputTableTypeDef = TypedDict(
     "QueryOutputTableTypeDef",
     {
         "Items": List[
@@ -4308,15 +4300,15 @@
                 Set[bytearray],
                 Sequence[Any],
                 Mapping[str, Any],
                 None,
             ],
         ],
         "ConsumedCapacity": ConsumedCapacityTableTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ScanOutputTableTypeDef = TypedDict(
     "ScanOutputTableTypeDef",
     {
         "Items": List[
@@ -4358,15 +4350,15 @@
                 Set[bytearray],
                 Sequence[Any],
                 Mapping[str, Any],
                 None,
             ],
         ],
         "ConsumedCapacity": ConsumedCapacityTableTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateItemOutputTableTypeDef = TypedDict(
     "UpdateItemOutputTableTypeDef",
     {
         "Attributes": Dict[
@@ -4386,151 +4378,151 @@
                 Sequence[Any],
                 Mapping[str, Any],
                 None,
             ],
         ],
         "ConsumedCapacity": ConsumedCapacityTableTypeDef,
         "ItemCollectionMetrics": ItemCollectionMetricsTableTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchExecuteStatementOutputTypeDef = TypedDict(
     "BatchExecuteStatementOutputTypeDef",
     {
         "Responses": List[BatchStatementResponseTypeDef],
         "ConsumedCapacity": List[ConsumedCapacityTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetItemOutputTypeDef = TypedDict(
     "BatchGetItemOutputTypeDef",
     {
         "Responses": Dict[str, List[Dict[str, AttributeValueTypeDef]]],
         "UnprocessedKeys": Dict[str, KeysAndAttributesTypeDef],
         "ConsumedCapacity": List[ConsumedCapacityTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteItemOutputTypeDef = TypedDict(
     "DeleteItemOutputTypeDef",
     {
         "Attributes": Dict[str, AttributeValueTypeDef],
         "ConsumedCapacity": ConsumedCapacityTypeDef,
         "ItemCollectionMetrics": ItemCollectionMetricsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ExecuteStatementOutputTypeDef = TypedDict(
     "ExecuteStatementOutputTypeDef",
     {
         "Items": List[Dict[str, AttributeValueTypeDef]],
         "NextToken": str,
         "ConsumedCapacity": ConsumedCapacityTypeDef,
         "LastEvaluatedKey": Dict[str, AttributeValueTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ExecuteTransactionOutputTypeDef = TypedDict(
     "ExecuteTransactionOutputTypeDef",
     {
         "Responses": List[ItemResponseTypeDef],
         "ConsumedCapacity": List[ConsumedCapacityTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetItemOutputTypeDef = TypedDict(
     "GetItemOutputTypeDef",
     {
         "Item": Dict[str, AttributeValueTypeDef],
         "ConsumedCapacity": ConsumedCapacityTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutItemOutputTypeDef = TypedDict(
     "PutItemOutputTypeDef",
     {
         "Attributes": Dict[str, AttributeValueTypeDef],
         "ConsumedCapacity": ConsumedCapacityTypeDef,
         "ItemCollectionMetrics": ItemCollectionMetricsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 QueryOutputTypeDef = TypedDict(
     "QueryOutputTypeDef",
     {
         "Items": List[Dict[str, AttributeValueTypeDef]],
         "Count": int,
         "ScannedCount": int,
         "LastEvaluatedKey": Dict[str, AttributeValueTypeDef],
         "ConsumedCapacity": ConsumedCapacityTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ScanOutputTypeDef = TypedDict(
     "ScanOutputTypeDef",
     {
         "Items": List[Dict[str, AttributeValueTypeDef]],
         "Count": int,
         "ScannedCount": int,
         "LastEvaluatedKey": Dict[str, AttributeValueTypeDef],
         "ConsumedCapacity": ConsumedCapacityTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TransactGetItemsOutputTypeDef = TypedDict(
     "TransactGetItemsOutputTypeDef",
     {
         "ConsumedCapacity": List[ConsumedCapacityTypeDef],
         "Responses": List[ItemResponseTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TransactWriteItemsOutputTypeDef = TypedDict(
     "TransactWriteItemsOutputTypeDef",
     {
         "ConsumedCapacity": List[ConsumedCapacityTypeDef],
         "ItemCollectionMetrics": Dict[str, List[ItemCollectionMetricsTypeDef]],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateItemOutputTypeDef = TypedDict(
     "UpdateItemOutputTypeDef",
     {
         "Attributes": Dict[str, AttributeValueTypeDef],
         "ConsumedCapacity": ConsumedCapacityTypeDef,
         "ItemCollectionMetrics": ItemCollectionMetricsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeContinuousBackupsOutputTypeDef = TypedDict(
     "DescribeContinuousBackupsOutputTypeDef",
     {
         "ContinuousBackupsDescription": ContinuousBackupsDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateContinuousBackupsOutputTypeDef = TypedDict(
     "UpdateContinuousBackupsOutputTypeDef",
     {
         "ContinuousBackupsDescription": ContinuousBackupsDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GlobalSecondaryIndexUpdateTableTypeDef = TypedDict(
     "GlobalSecondaryIndexUpdateTableTypeDef",
     {
         "Update": UpdateGlobalSecondaryIndexActionTableTypeDef,
@@ -4567,14 +4559,15 @@
         "GlobalSecondaryIndexes": Sequence[GlobalSecondaryIndexTypeDef],
         "BillingMode": BillingModeType,
         "ProvisionedThroughput": ProvisionedThroughputTypeDef,
         "StreamSpecification": StreamSpecificationTypeDef,
         "SSESpecification": SSESpecificationTypeDef,
         "Tags": Sequence[TagTypeDef],
         "TableClass": TableClassType,
+        "DeletionProtectionEnabled": bool,
     },
     total=False,
 )
 
 
 class CreateTableInputRequestTypeDef(
     _RequiredCreateTableInputRequestTypeDef, _OptionalCreateTableInputRequestTypeDef
@@ -4676,15 +4669,15 @@
 )
 
 ListGlobalTablesOutputTypeDef = TypedDict(
     "ListGlobalTablesOutputTypeDef",
     {
         "GlobalTables": List[GlobalTableTypeDef],
         "LastEvaluatedGlobalTableName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReplicaDescriptionTableTypeDef = TypedDict(
     "ReplicaDescriptionTableTypeDef",
     {
         "RegionName": str,
@@ -4839,14 +4832,15 @@
         "GlobalSecondaryIndexes": Sequence[GlobalSecondaryIndexServiceResourceTypeDef],
         "BillingMode": BillingModeType,
         "ProvisionedThroughput": ProvisionedThroughputServiceResourceTypeDef,
         "StreamSpecification": StreamSpecificationServiceResourceTypeDef,
         "SSESpecification": SSESpecificationServiceResourceTypeDef,
         "Tags": Sequence[TagServiceResourceTypeDef],
         "TableClass": TableClassType,
+        "DeletionProtectionEnabled": bool,
     },
     total=False,
 )
 
 
 class CreateTableInputServiceResourceCreateTableTypeDef(
     _RequiredCreateTableInputServiceResourceCreateTableTypeDef,
@@ -4856,15 +4850,15 @@
 
 
 ListImportsOutputTypeDef = TypedDict(
     "ListImportsOutputTypeDef",
     {
         "ImportSummaryList": List[ImportSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredBatchWriteItemInputServiceResourceBatchWriteItemTypeDef = TypedDict(
     "_RequiredBatchWriteItemInputServiceResourceBatchWriteItemTypeDef",
     {
         "RequestItems": Mapping[str, Sequence[WriteRequestServiceResourceTypeDef]],
@@ -4889,15 +4883,15 @@
 
 BatchWriteItemOutputServiceResourceTypeDef = TypedDict(
     "BatchWriteItemOutputServiceResourceTypeDef",
     {
         "UnprocessedItems": Dict[str, List[WriteRequestServiceResourceTypeDef]],
         "ItemCollectionMetrics": Dict[str, List[ItemCollectionMetricsServiceResourceTypeDef]],
         "ConsumedCapacity": List[ConsumedCapacityServiceResourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredTransactGetItemsInputRequestTypeDef = TypedDict(
     "_RequiredTransactGetItemsInputRequestTypeDef",
     {
         "TransactItems": Sequence[TransactGetItemTypeDef],
@@ -4942,15 +4936,15 @@
 
 BatchWriteItemOutputTypeDef = TypedDict(
     "BatchWriteItemOutputTypeDef",
     {
         "UnprocessedItems": Dict[str, List[WriteRequestTypeDef]],
         "ItemCollectionMetrics": Dict[str, List[ItemCollectionMetricsTypeDef]],
         "ConsumedCapacity": List[ConsumedCapacityTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredTransactWriteItemsInputRequestTypeDef = TypedDict(
     "_RequiredTransactWriteItemsInputRequestTypeDef",
     {
         "TransactItems": Sequence[TransactWriteItemTypeDef],
@@ -5156,14 +5150,15 @@
         "LatestStreamArn": str,
         "GlobalTableVersion": str,
         "Replicas": List[ReplicaDescriptionTableTypeDef],
         "RestoreSummary": RestoreSummaryTableTypeDef,
         "SSEDescription": SSEDescriptionTableTypeDef,
         "ArchivalSummary": ArchivalSummaryTableTypeDef,
         "TableClassSummary": TableClassSummaryTableTypeDef,
+        "DeletionProtectionEnabled": bool,
     },
     total=False,
 )
 
 ReplicationGroupUpdateTableTypeDef = TypedDict(
     "ReplicationGroupUpdateTableTypeDef",
     {
@@ -5207,14 +5202,15 @@
         "LatestStreamArn": str,
         "GlobalTableVersion": str,
         "Replicas": List[ReplicaDescriptionTypeDef],
         "RestoreSummary": RestoreSummaryTypeDef,
         "SSEDescription": SSEDescriptionTypeDef,
         "ArchivalSummary": ArchivalSummaryTypeDef,
         "TableClassSummary": TableClassSummaryTypeDef,
+        "DeletionProtectionEnabled": bool,
     },
     total=False,
 )
 
 ReplicationGroupUpdateTypeDef = TypedDict(
     "ReplicationGroupUpdateTypeDef",
     {
@@ -5317,134 +5313,135 @@
     pass
 
 
 DeleteBackupOutputTypeDef = TypedDict(
     "DeleteBackupOutputTypeDef",
     {
         "BackupDescription": BackupDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeBackupOutputTypeDef = TypedDict(
     "DescribeBackupOutputTypeDef",
     {
         "BackupDescription": BackupDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeImportOutputTypeDef = TypedDict(
     "DescribeImportOutputTypeDef",
     {
         "ImportTableDescription": ImportTableDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ImportTableOutputTypeDef = TypedDict(
     "ImportTableOutputTypeDef",
     {
         "ImportTableDescription": ImportTableDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteTableOutputTableTypeDef = TypedDict(
     "DeleteTableOutputTableTypeDef",
     {
         "TableDescription": TableDescriptionTableTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateTableInputTableUpdateTypeDef = TypedDict(
     "UpdateTableInputTableUpdateTypeDef",
     {
         "AttributeDefinitions": Sequence[AttributeDefinitionTableTypeDef],
         "BillingMode": BillingModeType,
         "ProvisionedThroughput": ProvisionedThroughputTableTypeDef,
         "GlobalSecondaryIndexUpdates": Sequence[GlobalSecondaryIndexUpdateTableTypeDef],
         "StreamSpecification": StreamSpecificationTableTypeDef,
         "SSESpecification": SSESpecificationTableTypeDef,
         "ReplicaUpdates": Sequence[ReplicationGroupUpdateTableTypeDef],
         "TableClass": TableClassType,
+        "DeletionProtectionEnabled": bool,
     },
     total=False,
 )
 
 CreateGlobalTableOutputTypeDef = TypedDict(
     "CreateGlobalTableOutputTypeDef",
     {
         "GlobalTableDescription": GlobalTableDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeGlobalTableOutputTypeDef = TypedDict(
     "DescribeGlobalTableOutputTypeDef",
     {
         "GlobalTableDescription": GlobalTableDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateGlobalTableOutputTypeDef = TypedDict(
     "UpdateGlobalTableOutputTypeDef",
     {
         "GlobalTableDescription": GlobalTableDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateTableOutputTypeDef = TypedDict(
     "CreateTableOutputTypeDef",
     {
         "TableDescription": TableDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteTableOutputTypeDef = TypedDict(
     "DeleteTableOutputTypeDef",
     {
         "TableDescription": TableDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeTableOutputTypeDef = TypedDict(
     "DescribeTableOutputTypeDef",
     {
         "Table": TableDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RestoreTableFromBackupOutputTypeDef = TypedDict(
     "RestoreTableFromBackupOutputTypeDef",
     {
         "TableDescription": TableDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RestoreTableToPointInTimeOutputTypeDef = TypedDict(
     "RestoreTableToPointInTimeOutputTypeDef",
     {
         "TableDescription": TableDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateTableOutputTypeDef = TypedDict(
     "UpdateTableOutputTypeDef",
     {
         "TableDescription": TableDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateTableInputRequestTypeDef = TypedDict(
     "_RequiredUpdateTableInputRequestTypeDef",
     {
         "TableName": str,
@@ -5457,14 +5454,15 @@
         "BillingMode": BillingModeType,
         "ProvisionedThroughput": ProvisionedThroughputTypeDef,
         "GlobalSecondaryIndexUpdates": Sequence[GlobalSecondaryIndexUpdateTypeDef],
         "StreamSpecification": StreamSpecificationTypeDef,
         "SSESpecification": SSESpecificationTypeDef,
         "ReplicaUpdates": Sequence[ReplicationGroupUpdateTypeDef],
         "TableClass": TableClassType,
+        "DeletionProtectionEnabled": bool,
     },
     total=False,
 )
 
 
 class UpdateTableInputRequestTypeDef(
     _RequiredUpdateTableInputRequestTypeDef, _OptionalUpdateTableInputRequestTypeDef
@@ -5483,24 +5481,24 @@
 )
 
 DescribeGlobalTableSettingsOutputTypeDef = TypedDict(
     "DescribeGlobalTableSettingsOutputTypeDef",
     {
         "GlobalTableName": str,
         "ReplicaSettings": List[ReplicaSettingsDescriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateGlobalTableSettingsOutputTypeDef = TypedDict(
     "UpdateGlobalTableSettingsOutputTypeDef",
     {
         "GlobalTableName": str,
         "ReplicaSettings": List[ReplicaSettingsDescriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateTableReplicaAutoScalingInputRequestTypeDef = TypedDict(
     "_RequiredUpdateTableReplicaAutoScalingInputRequestTypeDef",
     {
         "TableName": str,
@@ -5554,18 +5552,18 @@
     pass
 
 
 DescribeTableReplicaAutoScalingOutputTypeDef = TypedDict(
     "DescribeTableReplicaAutoScalingOutputTypeDef",
     {
         "TableAutoScalingDescription": TableAutoScalingDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateTableReplicaAutoScalingOutputTypeDef = TypedDict(
     "UpdateTableReplicaAutoScalingOutputTypeDef",
     {
         "TableAutoScalingDescription": TableAutoScalingDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-dynamodb-2.5.0.post1/types_aiobotocore_dynamodb/type_defs.pyi` & `types-aiobotocore-dynamodb-2.5.1/types_aiobotocore_dynamodb/type_defs.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -2,17 +2,17 @@
 Type annotations for dynamodb service type definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodb/type_defs/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_dynamodb.type_defs import ResponseMetadataTypeDef
+    from types_aiobotocore_dynamodb.type_defs import ArchivalSummaryResponseMetadataTypeDef
 
-    data: ResponseMetadataTypeDef = {...}
+    data: ArchivalSummaryResponseMetadataTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
 from decimal import Decimal
 from typing import Any, Dict, List, Mapping, Sequence, Set, Union
 
@@ -61,15 +61,15 @@
     from typing_extensions import TypedDict
 try:
     from boto3.dynamodb.conditions import ConditionBase
 except (ModuleNotFoundError, ImportError):
     from builtins import object as ConditionBase
 
 __all__ = (
-    "ResponseMetadataTypeDef",
+    "ArchivalSummaryResponseMetadataTypeDef",
     "ArchivalSummaryTableTypeDef",
     "ArchivalSummaryTypeDef",
     "AttributeDefinitionServiceResourceTypeDef",
     "AttributeDefinitionTableTypeDef",
     "AttributeDefinitionTypeDef",
     "AttributeValueTypeDef",
     "AttributeValueUpdateTableTypeDef",
@@ -77,14 +77,15 @@
     "AutoScalingTargetTrackingScalingPolicyConfigurationUpdateTypeDef",
     "BackupDetailsTypeDef",
     "BackupSummaryTableTypeDef",
     "BackupSummaryTypeDef",
     "KeysAndAttributesServiceResourceTypeDef",
     "BatchStatementErrorTypeDef",
     "ItemCollectionMetricsServiceResourceTypeDef",
+    "BillingModeSummaryResponseMetadataTypeDef",
     "BillingModeSummaryTableTypeDef",
     "BillingModeSummaryTypeDef",
     "CapacityServiceResourceTypeDef",
     "CapacityTableTypeDef",
     "CapacityTypeDef",
     "ConditionTableTypeDef",
     "PointInTimeRecoveryDescriptionTypeDef",
@@ -127,63 +128,64 @@
     "DescribeExportInputRequestTypeDef",
     "ExportDescriptionTypeDef",
     "DescribeGlobalTableInputRequestTypeDef",
     "DescribeGlobalTableSettingsInputRequestTypeDef",
     "DescribeImportInputRequestTypeDef",
     "DescribeKinesisStreamingDestinationInputRequestTypeDef",
     "KinesisDataStreamDestinationTypeDef",
+    "DescribeLimitsOutputTypeDef",
     "DescribeTableInputRequestTypeDef",
     "WaiterConfigTypeDef",
     "DescribeTableReplicaAutoScalingInputRequestTypeDef",
     "DescribeTimeToLiveInputRequestTypeDef",
     "TimeToLiveDescriptionTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "ExportSummaryTypeDef",
     "ExportTableToPointInTimeInputRequestTypeDef",
     "GetItemInputTableGetItemTypeDef",
     "ProvisionedThroughputDescriptionTableTypeDef",
     "ProvisionedThroughputDescriptionTypeDef",
     "ProjectionServiceResourceTypeDef",
     "S3BucketSourceTypeDef",
     "KinesisStreamingDestinationInputRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "KinesisStreamingDestinationOutputTypeDef",
+    "ListBackupsInputListBackupsPaginateTypeDef",
     "ListBackupsInputRequestTypeDef",
     "ListContributorInsightsInputRequestTypeDef",
     "ListExportsInputRequestTypeDef",
     "ListGlobalTablesInputRequestTypeDef",
     "ListImportsInputRequestTypeDef",
+    "ListTablesInputListTablesPaginateTypeDef",
     "ListTablesInputRequestTypeDef",
+    "ListTablesOutputTableTypeDef",
+    "ListTablesOutputTypeDef",
+    "ListTagsOfResourceInputListTagsOfResourcePaginateTypeDef",
     "ListTagsOfResourceInputRequestTypeDef",
     "TagTableTypeDef",
+    "PaginatorConfigTypeDef",
     "PointInTimeRecoverySpecificationTypeDef",
+    "ProvisionedThroughputDescriptionResponseMetadataTypeDef",
     "PutRequestServiceResourceTypeDef",
     "TableClassSummaryTableTypeDef",
     "TableClassSummaryTypeDef",
+    "ResponseMetadataTypeDef",
+    "RestoreSummaryResponseMetadataTypeDef",
     "RestoreSummaryTableTypeDef",
     "RestoreSummaryTypeDef",
+    "SSEDescriptionResponseMetadataTypeDef",
     "SSEDescriptionTableTypeDef",
     "SSEDescriptionTypeDef",
     "SSESpecificationTableTypeDef",
-    "ServiceResourceTableRequestTypeDef",
+    "StreamSpecificationResponseMetadataTypeDef",
     "StreamSpecificationTableTypeDef",
     "TableBatchWriterRequestTypeDef",
+    "TableClassSummaryResponseMetadataTypeDef",
     "TimeToLiveSpecificationTypeDef",
     "UntagResourceInputRequestTypeDef",
     "UpdateContributorInsightsInputRequestTypeDef",
-    "ArchivalSummaryResponseMetadataTypeDef",
-    "BillingModeSummaryResponseMetadataTypeDef",
-    "DescribeLimitsOutputTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "KinesisStreamingDestinationOutputTypeDef",
-    "ListTablesOutputTableTypeDef",
-    "ListTablesOutputTypeDef",
-    "ProvisionedThroughputDescriptionResponseMetadataTypeDef",
-    "RestoreSummaryResponseMetadataTypeDef",
-    "SSEDescriptionResponseMetadataTypeDef",
-    "StreamSpecificationResponseMetadataTypeDef",
-    "TableClassSummaryResponseMetadataTypeDef",
     "UpdateContributorInsightsOutputTypeDef",
     "AttributeValueUpdateTypeDef",
     "BatchStatementRequestTypeDef",
     "ConditionCheckTypeDef",
     "ConditionTypeDef",
     "DeleteRequestTypeDef",
     "DeleteTypeDef",
@@ -204,15 +206,17 @@
     "ListBackupsOutputTableTypeDef",
     "ListBackupsOutputTypeDef",
     "BatchGetItemInputServiceResourceBatchGetItemTypeDef",
     "BatchStatementResponseTypeDef",
     "ConsumedCapacityServiceResourceTypeDef",
     "ConsumedCapacityTableTypeDef",
     "ConsumedCapacityTypeDef",
+    "QueryInputQueryPaginateTypeDef",
     "QueryInputTableQueryTypeDef",
+    "ScanInputScanPaginateTypeDef",
     "ScanInputTableScanTypeDef",
     "ContinuousBackupsDescriptionTypeDef",
     "ListContributorInsightsOutputTypeDef",
     "LocalSecondaryIndexDescriptionTableTypeDef",
     "CreateGlobalSecondaryIndexActionTableTypeDef",
     "UpdateGlobalSecondaryIndexActionTableTypeDef",
     "LocalSecondaryIndexDescriptionTypeDef",
@@ -246,19 +250,14 @@
     "DescribeTimeToLiveOutputTypeDef",
     "ListExportsOutputTypeDef",
     "GlobalSecondaryIndexDescriptionTableTypeDef",
     "GlobalSecondaryIndexDescriptionTypeDef",
     "GlobalSecondaryIndexServiceResourceTypeDef",
     "LocalSecondaryIndexServiceResourceTypeDef",
     "ImportSummaryTypeDef",
-    "ListBackupsInputListBackupsPaginateTypeDef",
-    "ListTablesInputListTablesPaginateTypeDef",
-    "ListTagsOfResourceInputListTagsOfResourcePaginateTypeDef",
-    "QueryInputQueryPaginateTypeDef",
-    "ScanInputScanPaginateTypeDef",
     "ListTagsOfResourceOutputTableTypeDef",
     "UpdateContinuousBackupsInputRequestTypeDef",
     "WriteRequestServiceResourceTypeDef",
     "UpdateTimeToLiveInputRequestTypeDef",
     "UpdateTimeToLiveOutputTypeDef",
     "BatchExecuteStatementInputRequestTypeDef",
     "QueryInputRequestTypeDef",
@@ -356,22 +355,21 @@
     "UpdateGlobalTableSettingsOutputTypeDef",
     "UpdateTableReplicaAutoScalingInputRequestTypeDef",
     "UpdateGlobalTableSettingsInputRequestTypeDef",
     "DescribeTableReplicaAutoScalingOutputTypeDef",
     "UpdateTableReplicaAutoScalingOutputTypeDef",
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+ArchivalSummaryResponseMetadataTypeDef = TypedDict(
+    "ArchivalSummaryResponseMetadataTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ArchivalDateTime": datetime,
+        "ArchivalReason": str,
+        "ArchivalBackupArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ArchivalSummaryTableTypeDef = TypedDict(
     "ArchivalSummaryTableTypeDef",
     {
         "ArchivalDateTime": datetime,
@@ -631,14 +629,23 @@
             ],
         ],
         "SizeEstimateRangeGB": List[float],
     },
     total=False,
 )
 
+BillingModeSummaryResponseMetadataTypeDef = TypedDict(
+    "BillingModeSummaryResponseMetadataTypeDef",
+    {
+        "BillingMode": BillingModeType,
+        "LastUpdateToPayPerRequestDateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 BillingModeSummaryTableTypeDef = TypedDict(
     "BillingModeSummaryTableTypeDef",
     {
         "BillingMode": BillingModeType,
         "LastUpdateToPayPerRequestDateTime": datetime,
     },
     total=False,
@@ -1188,14 +1195,25 @@
         "StreamArn": str,
         "DestinationStatus": DestinationStatusType,
         "DestinationStatusDescription": str,
     },
     total=False,
 )
 
+DescribeLimitsOutputTypeDef = TypedDict(
+    "DescribeLimitsOutputTypeDef",
+    {
+        "AccountMaxReadCapacityUnits": int,
+        "AccountMaxWriteCapacityUnits": int,
+        "TableMaxReadCapacityUnits": int,
+        "TableMaxWriteCapacityUnits": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeTableInputRequestTypeDef = TypedDict(
     "DescribeTableInputRequestTypeDef",
     {
         "TableName": str,
     },
 )
 
@@ -1227,14 +1245,21 @@
     {
         "TimeToLiveStatus": TimeToLiveStatusType,
         "AttributeName": str,
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
 ExportSummaryTypeDef = TypedDict(
     "ExportSummaryTypeDef",
     {
         "ExportArn": str,
         "ExportStatus": ExportStatusType,
     },
     total=False,
@@ -1363,20 +1388,32 @@
     "KinesisStreamingDestinationInputRequestTypeDef",
     {
         "TableName": str,
         "StreamArn": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+KinesisStreamingDestinationOutputTypeDef = TypedDict(
+    "KinesisStreamingDestinationOutputTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "TableName": str,
+        "StreamArn": str,
+        "DestinationStatus": DestinationStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListBackupsInputListBackupsPaginateTypeDef = TypedDict(
+    "ListBackupsInputListBackupsPaginateTypeDef",
+    {
+        "TableName": str,
+        "TimeRangeLowerBound": Union[datetime, str],
+        "TimeRangeUpperBound": Union[datetime, str],
+        "BackupType": BackupTypeFilterType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListBackupsInputRequestTypeDef = TypedDict(
     "ListBackupsInputRequestTypeDef",
     {
@@ -1426,23 +1463,69 @@
         "TableArn": str,
         "PageSize": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListTablesInputListTablesPaginateTypeDef = TypedDict(
+    "ListTablesInputListTablesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListTablesInputRequestTypeDef = TypedDict(
     "ListTablesInputRequestTypeDef",
     {
         "ExclusiveStartTableName": str,
         "Limit": int,
     },
     total=False,
 )
 
+ListTablesOutputTableTypeDef = TypedDict(
+    "ListTablesOutputTableTypeDef",
+    {
+        "TableNames": List[str],
+        "LastEvaluatedTableName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListTablesOutputTypeDef = TypedDict(
+    "ListTablesOutputTypeDef",
+    {
+        "TableNames": List[str],
+        "LastEvaluatedTableName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListTagsOfResourceInputListTagsOfResourcePaginateTypeDef = TypedDict(
+    "_RequiredListTagsOfResourceInputListTagsOfResourcePaginateTypeDef",
+    {
+        "ResourceArn": str,
+    },
+)
+_OptionalListTagsOfResourceInputListTagsOfResourcePaginateTypeDef = TypedDict(
+    "_OptionalListTagsOfResourceInputListTagsOfResourcePaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListTagsOfResourceInputListTagsOfResourcePaginateTypeDef(
+    _RequiredListTagsOfResourceInputListTagsOfResourcePaginateTypeDef,
+    _OptionalListTagsOfResourceInputListTagsOfResourcePaginateTypeDef,
+):
+    pass
+
 _RequiredListTagsOfResourceInputRequestTypeDef = TypedDict(
     "_RequiredListTagsOfResourceInputRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 _OptionalListTagsOfResourceInputRequestTypeDef = TypedDict(
@@ -1462,21 +1545,43 @@
     "TagTableTypeDef",
     {
         "Key": str,
         "Value": str,
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
 PointInTimeRecoverySpecificationTypeDef = TypedDict(
     "PointInTimeRecoverySpecificationTypeDef",
     {
         "PointInTimeRecoveryEnabled": bool,
     },
 )
 
+ProvisionedThroughputDescriptionResponseMetadataTypeDef = TypedDict(
+    "ProvisionedThroughputDescriptionResponseMetadataTypeDef",
+    {
+        "LastIncreaseDateTime": datetime,
+        "LastDecreaseDateTime": datetime,
+        "NumberOfDecreasesToday": int,
+        "ReadCapacityUnits": int,
+        "WriteCapacityUnits": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 PutRequestServiceResourceTypeDef = TypedDict(
     "PutRequestServiceResourceTypeDef",
     {
         "Item": Mapping[
             str,
             Union[
                 bytes,
@@ -1512,14 +1617,36 @@
     {
         "TableClass": TableClassType,
         "LastUpdateDateTime": datetime,
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
+RestoreSummaryResponseMetadataTypeDef = TypedDict(
+    "RestoreSummaryResponseMetadataTypeDef",
+    {
+        "SourceBackupArn": str,
+        "SourceTableArn": str,
+        "RestoreDateTime": datetime,
+        "RestoreInProgress": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredRestoreSummaryTableTypeDef = TypedDict(
     "_RequiredRestoreSummaryTableTypeDef",
     {
         "RestoreDateTime": datetime,
         "RestoreInProgress": bool,
     },
 )
@@ -1552,14 +1679,25 @@
     },
     total=False,
 )
 
 class RestoreSummaryTypeDef(_RequiredRestoreSummaryTypeDef, _OptionalRestoreSummaryTypeDef):
     pass
 
+SSEDescriptionResponseMetadataTypeDef = TypedDict(
+    "SSEDescriptionResponseMetadataTypeDef",
+    {
+        "Status": SSEStatusType,
+        "SSEType": SSETypeType,
+        "KMSMasterKeyArn": str,
+        "InaccessibleEncryptionDateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 SSEDescriptionTableTypeDef = TypedDict(
     "SSEDescriptionTableTypeDef",
     {
         "Status": SSEStatusType,
         "SSEType": SSETypeType,
         "KMSMasterKeyArn": str,
         "InaccessibleEncryptionDateTime": datetime,
@@ -1584,18 +1722,20 @@
         "Enabled": bool,
         "SSEType": SSETypeType,
         "KMSMasterKeyId": str,
     },
     total=False,
 )
 
-ServiceResourceTableRequestTypeDef = TypedDict(
-    "ServiceResourceTableRequestTypeDef",
+StreamSpecificationResponseMetadataTypeDef = TypedDict(
+    "StreamSpecificationResponseMetadataTypeDef",
     {
-        "name": str,
+        "StreamEnabled": bool,
+        "StreamViewType": StreamViewTypeType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStreamSpecificationTableTypeDef = TypedDict(
     "_RequiredStreamSpecificationTableTypeDef",
     {
         "StreamEnabled": bool,
@@ -1618,14 +1758,23 @@
     "TableBatchWriterRequestTypeDef",
     {
         "overwrite_by_pkeys": List[str],
     },
     total=False,
 )
 
+TableClassSummaryResponseMetadataTypeDef = TypedDict(
+    "TableClassSummaryResponseMetadataTypeDef",
+    {
+        "TableClass": TableClassType,
+        "LastUpdateDateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TimeToLiveSpecificationTypeDef = TypedDict(
     "TimeToLiveSpecificationTypeDef",
     {
         "Enabled": bool,
         "AttributeName": str,
     },
 )
@@ -1655,138 +1804,21 @@
 
 class UpdateContributorInsightsInputRequestTypeDef(
     _RequiredUpdateContributorInsightsInputRequestTypeDef,
     _OptionalUpdateContributorInsightsInputRequestTypeDef,
 ):
     pass
 
-ArchivalSummaryResponseMetadataTypeDef = TypedDict(
-    "ArchivalSummaryResponseMetadataTypeDef",
-    {
-        "ArchivalDateTime": datetime,
-        "ArchivalReason": str,
-        "ArchivalBackupArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-BillingModeSummaryResponseMetadataTypeDef = TypedDict(
-    "BillingModeSummaryResponseMetadataTypeDef",
-    {
-        "BillingMode": BillingModeType,
-        "LastUpdateToPayPerRequestDateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeLimitsOutputTypeDef = TypedDict(
-    "DescribeLimitsOutputTypeDef",
-    {
-        "AccountMaxReadCapacityUnits": int,
-        "AccountMaxWriteCapacityUnits": int,
-        "TableMaxReadCapacityUnits": int,
-        "TableMaxWriteCapacityUnits": int,
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
-KinesisStreamingDestinationOutputTypeDef = TypedDict(
-    "KinesisStreamingDestinationOutputTypeDef",
-    {
-        "TableName": str,
-        "StreamArn": str,
-        "DestinationStatus": DestinationStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTablesOutputTableTypeDef = TypedDict(
-    "ListTablesOutputTableTypeDef",
-    {
-        "TableNames": List[str],
-        "LastEvaluatedTableName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTablesOutputTypeDef = TypedDict(
-    "ListTablesOutputTypeDef",
-    {
-        "TableNames": List[str],
-        "LastEvaluatedTableName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ProvisionedThroughputDescriptionResponseMetadataTypeDef = TypedDict(
-    "ProvisionedThroughputDescriptionResponseMetadataTypeDef",
-    {
-        "LastIncreaseDateTime": datetime,
-        "LastDecreaseDateTime": datetime,
-        "NumberOfDecreasesToday": int,
-        "ReadCapacityUnits": int,
-        "WriteCapacityUnits": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RestoreSummaryResponseMetadataTypeDef = TypedDict(
-    "RestoreSummaryResponseMetadataTypeDef",
-    {
-        "SourceBackupArn": str,
-        "SourceTableArn": str,
-        "RestoreDateTime": datetime,
-        "RestoreInProgress": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SSEDescriptionResponseMetadataTypeDef = TypedDict(
-    "SSEDescriptionResponseMetadataTypeDef",
-    {
-        "Status": SSEStatusType,
-        "SSEType": SSETypeType,
-        "KMSMasterKeyArn": str,
-        "InaccessibleEncryptionDateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StreamSpecificationResponseMetadataTypeDef = TypedDict(
-    "StreamSpecificationResponseMetadataTypeDef",
-    {
-        "StreamEnabled": bool,
-        "StreamViewType": StreamViewTypeType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-TableClassSummaryResponseMetadataTypeDef = TypedDict(
-    "TableClassSummaryResponseMetadataTypeDef",
-    {
-        "TableClass": TableClassType,
-        "LastUpdateDateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 UpdateContributorInsightsOutputTypeDef = TypedDict(
     "UpdateContributorInsightsOutputTypeDef",
     {
         "TableName": str,
         "IndexName": str,
         "ContributorInsightsStatus": ContributorInsightsStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AttributeValueUpdateTypeDef = TypedDict(
     "AttributeValueUpdateTypeDef",
     {
         "Value": Union[
@@ -2509,33 +2541,33 @@
 ):
     pass
 
 CreateBackupOutputTypeDef = TypedDict(
     "CreateBackupOutputTypeDef",
     {
         "BackupDetails": BackupDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListBackupsOutputTableTypeDef = TypedDict(
     "ListBackupsOutputTableTypeDef",
     {
         "BackupSummaries": List[BackupSummaryTableTypeDef],
         "LastEvaluatedBackupArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListBackupsOutputTypeDef = TypedDict(
     "ListBackupsOutputTypeDef",
     {
         "BackupSummaries": List[BackupSummaryTypeDef],
         "LastEvaluatedBackupArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredBatchGetItemInputServiceResourceBatchGetItemTypeDef = TypedDict(
     "_RequiredBatchGetItemInputServiceResourceBatchGetItemTypeDef",
     {
         "RequestItems": Mapping[str, KeysAndAttributesServiceResourceTypeDef],
@@ -2603,14 +2635,65 @@
         "Table": CapacityTypeDef,
         "LocalSecondaryIndexes": Dict[str, CapacityTypeDef],
         "GlobalSecondaryIndexes": Dict[str, CapacityTypeDef],
     },
     total=False,
 )
 
+_RequiredQueryInputQueryPaginateTypeDef = TypedDict(
+    "_RequiredQueryInputQueryPaginateTypeDef",
+    {
+        "TableName": str,
+    },
+)
+_OptionalQueryInputQueryPaginateTypeDef = TypedDict(
+    "_OptionalQueryInputQueryPaginateTypeDef",
+    {
+        "IndexName": str,
+        "Select": SelectType,
+        "AttributesToGet": Sequence[str],
+        "ConsistentRead": bool,
+        "KeyConditions": Mapping[str, ConditionTableTypeDef],
+        "QueryFilter": Mapping[str, ConditionTableTypeDef],
+        "ConditionalOperator": ConditionalOperatorType,
+        "ScanIndexForward": bool,
+        "ReturnConsumedCapacity": ReturnConsumedCapacityType,
+        "ProjectionExpression": str,
+        "FilterExpression": str,
+        "KeyConditionExpression": str,
+        "ExpressionAttributeNames": Mapping[str, str],
+        "ExpressionAttributeValues": Mapping[
+            str,
+            Union[
+                bytes,
+                bytearray,
+                str,
+                int,
+                Decimal,
+                bool,
+                Set[int],
+                Set[Decimal],
+                Set[str],
+                Set[bytes],
+                Set[bytearray],
+                Sequence[Any],
+                Mapping[str, Any],
+                None,
+            ],
+        ],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class QueryInputQueryPaginateTypeDef(
+    _RequiredQueryInputQueryPaginateTypeDef, _OptionalQueryInputQueryPaginateTypeDef
+):
+    pass
+
 QueryInputTableQueryTypeDef = TypedDict(
     "QueryInputTableQueryTypeDef",
     {
         "IndexName": str,
         "Select": SelectType,
         "AttributesToGet": Sequence[str],
         "Limit": int,
@@ -2662,14 +2745,64 @@
                 None,
             ],
         ],
     },
     total=False,
 )
 
+_RequiredScanInputScanPaginateTypeDef = TypedDict(
+    "_RequiredScanInputScanPaginateTypeDef",
+    {
+        "TableName": str,
+    },
+)
+_OptionalScanInputScanPaginateTypeDef = TypedDict(
+    "_OptionalScanInputScanPaginateTypeDef",
+    {
+        "IndexName": str,
+        "AttributesToGet": Sequence[str],
+        "Select": SelectType,
+        "ScanFilter": Mapping[str, ConditionTableTypeDef],
+        "ConditionalOperator": ConditionalOperatorType,
+        "ReturnConsumedCapacity": ReturnConsumedCapacityType,
+        "TotalSegments": int,
+        "Segment": int,
+        "ProjectionExpression": str,
+        "FilterExpression": str,
+        "ExpressionAttributeNames": Mapping[str, str],
+        "ExpressionAttributeValues": Mapping[
+            str,
+            Union[
+                bytes,
+                bytearray,
+                str,
+                int,
+                Decimal,
+                bool,
+                Set[int],
+                Set[Decimal],
+                Set[str],
+                Set[bytes],
+                Set[bytearray],
+                Sequence[Any],
+                Mapping[str, Any],
+                None,
+            ],
+        ],
+        "ConsistentRead": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ScanInputScanPaginateTypeDef(
+    _RequiredScanInputScanPaginateTypeDef, _OptionalScanInputScanPaginateTypeDef
+):
+    pass
+
 ScanInputTableScanTypeDef = TypedDict(
     "ScanInputTableScanTypeDef",
     {
         "IndexName": str,
         "AttributesToGet": Sequence[str],
         "Limit": int,
         "Select": SelectType,
@@ -2744,15 +2877,15 @@
     pass
 
 ListContributorInsightsOutputTypeDef = TypedDict(
     "ListContributorInsightsOutputTypeDef",
     {
         "ContributorInsightsSummaries": List[ContributorInsightsSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LocalSecondaryIndexDescriptionTableTypeDef = TypedDict(
     "LocalSecondaryIndexDescriptionTableTypeDef",
     {
         "IndexName": str,
@@ -2990,15 +3123,15 @@
     pass
 
 ListTagsOfResourceOutputTypeDef = TypedDict(
     "ListTagsOfResourceOutputTypeDef",
     {
         "Tags": List[TagTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceInputRequestTypeDef = TypedDict(
     "TagResourceInputRequestTypeDef",
     {
         "ResourceArn": str,
@@ -3216,48 +3349,48 @@
     {
         "TableName": str,
         "IndexName": str,
         "ContributorInsightsRuleList": List[str],
         "ContributorInsightsStatus": ContributorInsightsStatusType,
         "LastUpdateDateTime": datetime,
         "FailureException": FailureExceptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEndpointsResponseTypeDef = TypedDict(
     "DescribeEndpointsResponseTypeDef",
     {
         "Endpoints": List[EndpointTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeExportOutputTypeDef = TypedDict(
     "DescribeExportOutputTypeDef",
     {
         "ExportDescription": ExportDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ExportTableToPointInTimeOutputTypeDef = TypedDict(
     "ExportTableToPointInTimeOutputTypeDef",
     {
         "ExportDescription": ExportDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeKinesisStreamingDestinationOutputTypeDef = TypedDict(
     "DescribeKinesisStreamingDestinationOutputTypeDef",
     {
         "TableName": str,
         "KinesisDataStreamDestinations": List[KinesisDataStreamDestinationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredDescribeTableInputTableExistsWaitTypeDef = TypedDict(
     "_RequiredDescribeTableInputTableExistsWaitTypeDef",
     {
         "TableName": str,
@@ -3297,24 +3430,24 @@
 ):
     pass
 
 DescribeTimeToLiveOutputTypeDef = TypedDict(
     "DescribeTimeToLiveOutputTypeDef",
     {
         "TimeToLiveDescription": TimeToLiveDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListExportsOutputTypeDef = TypedDict(
     "ListExportsOutputTypeDef",
     {
         "ExportSummaries": List[ExportSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GlobalSecondaryIndexDescriptionTableTypeDef = TypedDict(
     "GlobalSecondaryIndexDescriptionTableTypeDef",
     {
         "IndexName": str,
@@ -3388,161 +3521,20 @@
         "InputFormat": InputFormatType,
         "StartTime": datetime,
         "EndTime": datetime,
     },
     total=False,
 )
 
-ListBackupsInputListBackupsPaginateTypeDef = TypedDict(
-    "ListBackupsInputListBackupsPaginateTypeDef",
-    {
-        "TableName": str,
-        "TimeRangeLowerBound": Union[datetime, str],
-        "TimeRangeUpperBound": Union[datetime, str],
-        "BackupType": BackupTypeFilterType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListTablesInputListTablesPaginateTypeDef = TypedDict(
-    "ListTablesInputListTablesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListTagsOfResourceInputListTagsOfResourcePaginateTypeDef = TypedDict(
-    "_RequiredListTagsOfResourceInputListTagsOfResourcePaginateTypeDef",
-    {
-        "ResourceArn": str,
-    },
-)
-_OptionalListTagsOfResourceInputListTagsOfResourcePaginateTypeDef = TypedDict(
-    "_OptionalListTagsOfResourceInputListTagsOfResourcePaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListTagsOfResourceInputListTagsOfResourcePaginateTypeDef(
-    _RequiredListTagsOfResourceInputListTagsOfResourcePaginateTypeDef,
-    _OptionalListTagsOfResourceInputListTagsOfResourcePaginateTypeDef,
-):
-    pass
-
-_RequiredQueryInputQueryPaginateTypeDef = TypedDict(
-    "_RequiredQueryInputQueryPaginateTypeDef",
-    {
-        "TableName": str,
-    },
-)
-_OptionalQueryInputQueryPaginateTypeDef = TypedDict(
-    "_OptionalQueryInputQueryPaginateTypeDef",
-    {
-        "IndexName": str,
-        "Select": SelectType,
-        "AttributesToGet": Sequence[str],
-        "ConsistentRead": bool,
-        "KeyConditions": Mapping[str, ConditionTableTypeDef],
-        "QueryFilter": Mapping[str, ConditionTableTypeDef],
-        "ConditionalOperator": ConditionalOperatorType,
-        "ScanIndexForward": bool,
-        "ReturnConsumedCapacity": ReturnConsumedCapacityType,
-        "ProjectionExpression": str,
-        "FilterExpression": str,
-        "KeyConditionExpression": str,
-        "ExpressionAttributeNames": Mapping[str, str],
-        "ExpressionAttributeValues": Mapping[
-            str,
-            Union[
-                bytes,
-                bytearray,
-                str,
-                int,
-                Decimal,
-                bool,
-                Set[int],
-                Set[Decimal],
-                Set[str],
-                Set[bytes],
-                Set[bytearray],
-                Sequence[Any],
-                Mapping[str, Any],
-                None,
-            ],
-        ],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class QueryInputQueryPaginateTypeDef(
-    _RequiredQueryInputQueryPaginateTypeDef, _OptionalQueryInputQueryPaginateTypeDef
-):
-    pass
-
-_RequiredScanInputScanPaginateTypeDef = TypedDict(
-    "_RequiredScanInputScanPaginateTypeDef",
-    {
-        "TableName": str,
-    },
-)
-_OptionalScanInputScanPaginateTypeDef = TypedDict(
-    "_OptionalScanInputScanPaginateTypeDef",
-    {
-        "IndexName": str,
-        "AttributesToGet": Sequence[str],
-        "Select": SelectType,
-        "ScanFilter": Mapping[str, ConditionTableTypeDef],
-        "ConditionalOperator": ConditionalOperatorType,
-        "ReturnConsumedCapacity": ReturnConsumedCapacityType,
-        "TotalSegments": int,
-        "Segment": int,
-        "ProjectionExpression": str,
-        "FilterExpression": str,
-        "ExpressionAttributeNames": Mapping[str, str],
-        "ExpressionAttributeValues": Mapping[
-            str,
-            Union[
-                bytes,
-                bytearray,
-                str,
-                int,
-                Decimal,
-                bool,
-                Set[int],
-                Set[Decimal],
-                Set[str],
-                Set[bytes],
-                Set[bytearray],
-                Sequence[Any],
-                Mapping[str, Any],
-                None,
-            ],
-        ],
-        "ConsistentRead": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ScanInputScanPaginateTypeDef(
-    _RequiredScanInputScanPaginateTypeDef, _OptionalScanInputScanPaginateTypeDef
-):
-    pass
-
 ListTagsOfResourceOutputTableTypeDef = TypedDict(
     "ListTagsOfResourceOutputTableTypeDef",
     {
         "Tags": List[TagTableTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateContinuousBackupsInputRequestTypeDef = TypedDict(
     "UpdateContinuousBackupsInputRequestTypeDef",
     {
         "TableName": str,
@@ -3567,15 +3559,15 @@
     },
 )
 
 UpdateTimeToLiveOutputTypeDef = TypedDict(
     "UpdateTimeToLiveOutputTypeDef",
     {
         "TimeToLiveSpecification": TimeToLiveSpecificationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredBatchExecuteStatementInputRequestTypeDef = TypedDict(
     "_RequiredBatchExecuteStatementInputRequestTypeDef",
     {
         "Statements": Sequence[BatchStatementRequestTypeDef],
@@ -4068,15 +4060,15 @@
                         None,
                     ],
                 ]
             ],
         ],
         "UnprocessedKeys": Dict[str, KeysAndAttributesServiceResourceTypeDef],
         "ConsumedCapacity": List[ConsumedCapacityServiceResourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteItemOutputTableTypeDef = TypedDict(
     "DeleteItemOutputTableTypeDef",
     {
         "Attributes": Dict[
@@ -4096,15 +4088,15 @@
                 Sequence[Any],
                 Mapping[str, Any],
                 None,
             ],
         ],
         "ConsumedCapacity": ConsumedCapacityTableTypeDef,
         "ItemCollectionMetrics": ItemCollectionMetricsTableTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetItemOutputTableTypeDef = TypedDict(
     "GetItemOutputTableTypeDef",
     {
         "Item": Dict[
@@ -4123,15 +4115,15 @@
                 Set[bytearray],
                 Sequence[Any],
                 Mapping[str, Any],
                 None,
             ],
         ],
         "ConsumedCapacity": ConsumedCapacityTableTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutItemOutputTableTypeDef = TypedDict(
     "PutItemOutputTableTypeDef",
     {
         "Attributes": Dict[
@@ -4151,15 +4143,15 @@
                 Sequence[Any],
                 Mapping[str, Any],
                 None,
             ],
         ],
         "ConsumedCapacity": ConsumedCapacityTableTypeDef,
         "ItemCollectionMetrics": ItemCollectionMetricsTableTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 QueryOutputTableTypeDef = TypedDict(
     "QueryOutputTableTypeDef",
     {
         "Items": List[
@@ -4201,15 +4193,15 @@
                 Set[bytearray],
                 Sequence[Any],
                 Mapping[str, Any],
                 None,
             ],
         ],
         "ConsumedCapacity": ConsumedCapacityTableTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ScanOutputTableTypeDef = TypedDict(
     "ScanOutputTableTypeDef",
     {
         "Items": List[
@@ -4251,15 +4243,15 @@
                 Set[bytearray],
                 Sequence[Any],
                 Mapping[str, Any],
                 None,
             ],
         ],
         "ConsumedCapacity": ConsumedCapacityTableTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateItemOutputTableTypeDef = TypedDict(
     "UpdateItemOutputTableTypeDef",
     {
         "Attributes": Dict[
@@ -4279,151 +4271,151 @@
                 Sequence[Any],
                 Mapping[str, Any],
                 None,
             ],
         ],
         "ConsumedCapacity": ConsumedCapacityTableTypeDef,
         "ItemCollectionMetrics": ItemCollectionMetricsTableTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchExecuteStatementOutputTypeDef = TypedDict(
     "BatchExecuteStatementOutputTypeDef",
     {
         "Responses": List[BatchStatementResponseTypeDef],
         "ConsumedCapacity": List[ConsumedCapacityTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetItemOutputTypeDef = TypedDict(
     "BatchGetItemOutputTypeDef",
     {
         "Responses": Dict[str, List[Dict[str, AttributeValueTypeDef]]],
         "UnprocessedKeys": Dict[str, KeysAndAttributesTypeDef],
         "ConsumedCapacity": List[ConsumedCapacityTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteItemOutputTypeDef = TypedDict(
     "DeleteItemOutputTypeDef",
     {
         "Attributes": Dict[str, AttributeValueTypeDef],
         "ConsumedCapacity": ConsumedCapacityTypeDef,
         "ItemCollectionMetrics": ItemCollectionMetricsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ExecuteStatementOutputTypeDef = TypedDict(
     "ExecuteStatementOutputTypeDef",
     {
         "Items": List[Dict[str, AttributeValueTypeDef]],
         "NextToken": str,
         "ConsumedCapacity": ConsumedCapacityTypeDef,
         "LastEvaluatedKey": Dict[str, AttributeValueTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ExecuteTransactionOutputTypeDef = TypedDict(
     "ExecuteTransactionOutputTypeDef",
     {
         "Responses": List[ItemResponseTypeDef],
         "ConsumedCapacity": List[ConsumedCapacityTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetItemOutputTypeDef = TypedDict(
     "GetItemOutputTypeDef",
     {
         "Item": Dict[str, AttributeValueTypeDef],
         "ConsumedCapacity": ConsumedCapacityTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutItemOutputTypeDef = TypedDict(
     "PutItemOutputTypeDef",
     {
         "Attributes": Dict[str, AttributeValueTypeDef],
         "ConsumedCapacity": ConsumedCapacityTypeDef,
         "ItemCollectionMetrics": ItemCollectionMetricsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 QueryOutputTypeDef = TypedDict(
     "QueryOutputTypeDef",
     {
         "Items": List[Dict[str, AttributeValueTypeDef]],
         "Count": int,
         "ScannedCount": int,
         "LastEvaluatedKey": Dict[str, AttributeValueTypeDef],
         "ConsumedCapacity": ConsumedCapacityTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ScanOutputTypeDef = TypedDict(
     "ScanOutputTypeDef",
     {
         "Items": List[Dict[str, AttributeValueTypeDef]],
         "Count": int,
         "ScannedCount": int,
         "LastEvaluatedKey": Dict[str, AttributeValueTypeDef],
         "ConsumedCapacity": ConsumedCapacityTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TransactGetItemsOutputTypeDef = TypedDict(
     "TransactGetItemsOutputTypeDef",
     {
         "ConsumedCapacity": List[ConsumedCapacityTypeDef],
         "Responses": List[ItemResponseTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TransactWriteItemsOutputTypeDef = TypedDict(
     "TransactWriteItemsOutputTypeDef",
     {
         "ConsumedCapacity": List[ConsumedCapacityTypeDef],
         "ItemCollectionMetrics": Dict[str, List[ItemCollectionMetricsTypeDef]],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateItemOutputTypeDef = TypedDict(
     "UpdateItemOutputTypeDef",
     {
         "Attributes": Dict[str, AttributeValueTypeDef],
         "ConsumedCapacity": ConsumedCapacityTypeDef,
         "ItemCollectionMetrics": ItemCollectionMetricsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeContinuousBackupsOutputTypeDef = TypedDict(
     "DescribeContinuousBackupsOutputTypeDef",
     {
         "ContinuousBackupsDescription": ContinuousBackupsDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateContinuousBackupsOutputTypeDef = TypedDict(
     "UpdateContinuousBackupsOutputTypeDef",
     {
         "ContinuousBackupsDescription": ContinuousBackupsDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GlobalSecondaryIndexUpdateTableTypeDef = TypedDict(
     "GlobalSecondaryIndexUpdateTableTypeDef",
     {
         "Update": UpdateGlobalSecondaryIndexActionTableTypeDef,
@@ -4460,14 +4452,15 @@
         "GlobalSecondaryIndexes": Sequence[GlobalSecondaryIndexTypeDef],
         "BillingMode": BillingModeType,
         "ProvisionedThroughput": ProvisionedThroughputTypeDef,
         "StreamSpecification": StreamSpecificationTypeDef,
         "SSESpecification": SSESpecificationTypeDef,
         "Tags": Sequence[TagTypeDef],
         "TableClass": TableClassType,
+        "DeletionProtectionEnabled": bool,
     },
     total=False,
 )
 
 class CreateTableInputRequestTypeDef(
     _RequiredCreateTableInputRequestTypeDef, _OptionalCreateTableInputRequestTypeDef
 ):
@@ -4561,15 +4554,15 @@
 )
 
 ListGlobalTablesOutputTypeDef = TypedDict(
     "ListGlobalTablesOutputTypeDef",
     {
         "GlobalTables": List[GlobalTableTypeDef],
         "LastEvaluatedGlobalTableName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReplicaDescriptionTableTypeDef = TypedDict(
     "ReplicaDescriptionTableTypeDef",
     {
         "RegionName": str,
@@ -4716,14 +4709,15 @@
         "GlobalSecondaryIndexes": Sequence[GlobalSecondaryIndexServiceResourceTypeDef],
         "BillingMode": BillingModeType,
         "ProvisionedThroughput": ProvisionedThroughputServiceResourceTypeDef,
         "StreamSpecification": StreamSpecificationServiceResourceTypeDef,
         "SSESpecification": SSESpecificationServiceResourceTypeDef,
         "Tags": Sequence[TagServiceResourceTypeDef],
         "TableClass": TableClassType,
+        "DeletionProtectionEnabled": bool,
     },
     total=False,
 )
 
 class CreateTableInputServiceResourceCreateTableTypeDef(
     _RequiredCreateTableInputServiceResourceCreateTableTypeDef,
     _OptionalCreateTableInputServiceResourceCreateTableTypeDef,
@@ -4731,15 +4725,15 @@
     pass
 
 ListImportsOutputTypeDef = TypedDict(
     "ListImportsOutputTypeDef",
     {
         "ImportSummaryList": List[ImportSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredBatchWriteItemInputServiceResourceBatchWriteItemTypeDef = TypedDict(
     "_RequiredBatchWriteItemInputServiceResourceBatchWriteItemTypeDef",
     {
         "RequestItems": Mapping[str, Sequence[WriteRequestServiceResourceTypeDef]],
@@ -4762,15 +4756,15 @@
 
 BatchWriteItemOutputServiceResourceTypeDef = TypedDict(
     "BatchWriteItemOutputServiceResourceTypeDef",
     {
         "UnprocessedItems": Dict[str, List[WriteRequestServiceResourceTypeDef]],
         "ItemCollectionMetrics": Dict[str, List[ItemCollectionMetricsServiceResourceTypeDef]],
         "ConsumedCapacity": List[ConsumedCapacityServiceResourceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredTransactGetItemsInputRequestTypeDef = TypedDict(
     "_RequiredTransactGetItemsInputRequestTypeDef",
     {
         "TransactItems": Sequence[TransactGetItemTypeDef],
@@ -4811,15 +4805,15 @@
 
 BatchWriteItemOutputTypeDef = TypedDict(
     "BatchWriteItemOutputTypeDef",
     {
         "UnprocessedItems": Dict[str, List[WriteRequestTypeDef]],
         "ItemCollectionMetrics": Dict[str, List[ItemCollectionMetricsTypeDef]],
         "ConsumedCapacity": List[ConsumedCapacityTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredTransactWriteItemsInputRequestTypeDef = TypedDict(
     "_RequiredTransactWriteItemsInputRequestTypeDef",
     {
         "TransactItems": Sequence[TransactWriteItemTypeDef],
@@ -5015,14 +5009,15 @@
         "LatestStreamArn": str,
         "GlobalTableVersion": str,
         "Replicas": List[ReplicaDescriptionTableTypeDef],
         "RestoreSummary": RestoreSummaryTableTypeDef,
         "SSEDescription": SSEDescriptionTableTypeDef,
         "ArchivalSummary": ArchivalSummaryTableTypeDef,
         "TableClassSummary": TableClassSummaryTableTypeDef,
+        "DeletionProtectionEnabled": bool,
     },
     total=False,
 )
 
 ReplicationGroupUpdateTableTypeDef = TypedDict(
     "ReplicationGroupUpdateTableTypeDef",
     {
@@ -5066,14 +5061,15 @@
         "LatestStreamArn": str,
         "GlobalTableVersion": str,
         "Replicas": List[ReplicaDescriptionTypeDef],
         "RestoreSummary": RestoreSummaryTypeDef,
         "SSEDescription": SSEDescriptionTypeDef,
         "ArchivalSummary": ArchivalSummaryTypeDef,
         "TableClassSummary": TableClassSummaryTypeDef,
+        "DeletionProtectionEnabled": bool,
     },
     total=False,
 )
 
 ReplicationGroupUpdateTypeDef = TypedDict(
     "ReplicationGroupUpdateTypeDef",
     {
@@ -5170,134 +5166,135 @@
 ):
     pass
 
 DeleteBackupOutputTypeDef = TypedDict(
     "DeleteBackupOutputTypeDef",
     {
         "BackupDescription": BackupDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeBackupOutputTypeDef = TypedDict(
     "DescribeBackupOutputTypeDef",
     {
         "BackupDescription": BackupDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeImportOutputTypeDef = TypedDict(
     "DescribeImportOutputTypeDef",
     {
         "ImportTableDescription": ImportTableDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ImportTableOutputTypeDef = TypedDict(
     "ImportTableOutputTypeDef",
     {
         "ImportTableDescription": ImportTableDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteTableOutputTableTypeDef = TypedDict(
     "DeleteTableOutputTableTypeDef",
     {
         "TableDescription": TableDescriptionTableTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateTableInputTableUpdateTypeDef = TypedDict(
     "UpdateTableInputTableUpdateTypeDef",
     {
         "AttributeDefinitions": Sequence[AttributeDefinitionTableTypeDef],
         "BillingMode": BillingModeType,
         "ProvisionedThroughput": ProvisionedThroughputTableTypeDef,
         "GlobalSecondaryIndexUpdates": Sequence[GlobalSecondaryIndexUpdateTableTypeDef],
         "StreamSpecification": StreamSpecificationTableTypeDef,
         "SSESpecification": SSESpecificationTableTypeDef,
         "ReplicaUpdates": Sequence[ReplicationGroupUpdateTableTypeDef],
         "TableClass": TableClassType,
+        "DeletionProtectionEnabled": bool,
     },
     total=False,
 )
 
 CreateGlobalTableOutputTypeDef = TypedDict(
     "CreateGlobalTableOutputTypeDef",
     {
         "GlobalTableDescription": GlobalTableDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeGlobalTableOutputTypeDef = TypedDict(
     "DescribeGlobalTableOutputTypeDef",
     {
         "GlobalTableDescription": GlobalTableDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateGlobalTableOutputTypeDef = TypedDict(
     "UpdateGlobalTableOutputTypeDef",
     {
         "GlobalTableDescription": GlobalTableDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateTableOutputTypeDef = TypedDict(
     "CreateTableOutputTypeDef",
     {
         "TableDescription": TableDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteTableOutputTypeDef = TypedDict(
     "DeleteTableOutputTypeDef",
     {
         "TableDescription": TableDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeTableOutputTypeDef = TypedDict(
     "DescribeTableOutputTypeDef",
     {
         "Table": TableDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RestoreTableFromBackupOutputTypeDef = TypedDict(
     "RestoreTableFromBackupOutputTypeDef",
     {
         "TableDescription": TableDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RestoreTableToPointInTimeOutputTypeDef = TypedDict(
     "RestoreTableToPointInTimeOutputTypeDef",
     {
         "TableDescription": TableDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateTableOutputTypeDef = TypedDict(
     "UpdateTableOutputTypeDef",
     {
         "TableDescription": TableDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateTableInputRequestTypeDef = TypedDict(
     "_RequiredUpdateTableInputRequestTypeDef",
     {
         "TableName": str,
@@ -5310,14 +5307,15 @@
         "BillingMode": BillingModeType,
         "ProvisionedThroughput": ProvisionedThroughputTypeDef,
         "GlobalSecondaryIndexUpdates": Sequence[GlobalSecondaryIndexUpdateTypeDef],
         "StreamSpecification": StreamSpecificationTypeDef,
         "SSESpecification": SSESpecificationTypeDef,
         "ReplicaUpdates": Sequence[ReplicationGroupUpdateTypeDef],
         "TableClass": TableClassType,
+        "DeletionProtectionEnabled": bool,
     },
     total=False,
 )
 
 class UpdateTableInputRequestTypeDef(
     _RequiredUpdateTableInputRequestTypeDef, _OptionalUpdateTableInputRequestTypeDef
 ):
@@ -5334,24 +5332,24 @@
 )
 
 DescribeGlobalTableSettingsOutputTypeDef = TypedDict(
     "DescribeGlobalTableSettingsOutputTypeDef",
     {
         "GlobalTableName": str,
         "ReplicaSettings": List[ReplicaSettingsDescriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateGlobalTableSettingsOutputTypeDef = TypedDict(
     "UpdateGlobalTableSettingsOutputTypeDef",
     {
         "GlobalTableName": str,
         "ReplicaSettings": List[ReplicaSettingsDescriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateTableReplicaAutoScalingInputRequestTypeDef = TypedDict(
     "_RequiredUpdateTableReplicaAutoScalingInputRequestTypeDef",
     {
         "TableName": str,
@@ -5401,18 +5399,18 @@
 ):
     pass
 
 DescribeTableReplicaAutoScalingOutputTypeDef = TypedDict(
     "DescribeTableReplicaAutoScalingOutputTypeDef",
     {
         "TableAutoScalingDescription": TableAutoScalingDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateTableReplicaAutoScalingOutputTypeDef = TypedDict(
     "UpdateTableReplicaAutoScalingOutputTypeDef",
     {
         "TableAutoScalingDescription": TableAutoScalingDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-dynamodb-2.5.0.post1/types_aiobotocore_dynamodb/waiter.py` & `types-aiobotocore-dynamodb-2.5.1/types_aiobotocore_dynamodb/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-dynamodb-2.5.0.post1/types_aiobotocore_dynamodb/waiter.pyi` & `types-aiobotocore-dynamodb-2.5.1/types_aiobotocore_dynamodb/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-dynamodb-2.5.0.post1/types_aiobotocore_dynamodb.egg-info/PKG-INFO` & `types-aiobotocore-dynamodb-2.5.1/types_aiobotocore_dynamodb.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-dynamodb
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.DynamoDB 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.DynamoDB 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodb/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-dynamodb"></a>
 
 # types-aiobotocore-dynamodb
 
 [![PyPI - types-aiobotocore-dynamodb](https://img.shields.io/pypi/v/types-aiobotocore-dynamodb.svg?color=blue)](https://pypi.org/project/types-aiobotocore-dynamodb)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-dynamodb.svg?color=blue)](https://pypi.org/project/types-aiobotocore-dynamodb)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodb/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-dynamodb?color=blue)](https://pypistats.org/packages/types-aiobotocore-dynamodb)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.DynamoDB 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodb.html#DynamoDB)
+[aiobotocore.DynamoDB 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/dynamodb.html#DynamoDB)
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
 [types-aiobotocore-dynamodb docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodb/).
 
 See how it helps to find and fix potential bugs:
 
@@ -457,15 +457,15 @@
 ### Typed dictionaries
 
 `types_aiobotocore_dynamodb.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_dynamodb.type_defs import (
-    ResponseMetadataTypeDef,
+    ArchivalSummaryResponseMetadataTypeDef,
     ArchivalSummaryTableTypeDef,
     ArchivalSummaryTypeDef,
     AttributeDefinitionServiceResourceTypeDef,
     AttributeDefinitionTableTypeDef,
     AttributeDefinitionTypeDef,
     AttributeValueTypeDef,
     AttributeValueUpdateTableTypeDef,
@@ -473,14 +473,15 @@
     AutoScalingTargetTrackingScalingPolicyConfigurationUpdateTypeDef,
     BackupDetailsTypeDef,
     BackupSummaryTableTypeDef,
     BackupSummaryTypeDef,
     KeysAndAttributesServiceResourceTypeDef,
     BatchStatementErrorTypeDef,
     ItemCollectionMetricsServiceResourceTypeDef,
+    BillingModeSummaryResponseMetadataTypeDef,
     BillingModeSummaryTableTypeDef,
     BillingModeSummaryTypeDef,
     CapacityServiceResourceTypeDef,
     CapacityTableTypeDef,
     CapacityTypeDef,
     ConditionTableTypeDef,
     PointInTimeRecoveryDescriptionTypeDef,
@@ -523,63 +524,64 @@
     DescribeExportInputRequestTypeDef,
     ExportDescriptionTypeDef,
     DescribeGlobalTableInputRequestTypeDef,
     DescribeGlobalTableSettingsInputRequestTypeDef,
     DescribeImportInputRequestTypeDef,
     DescribeKinesisStreamingDestinationInputRequestTypeDef,
     KinesisDataStreamDestinationTypeDef,
+    DescribeLimitsOutputTypeDef,
     DescribeTableInputRequestTypeDef,
     WaiterConfigTypeDef,
     DescribeTableReplicaAutoScalingInputRequestTypeDef,
     DescribeTimeToLiveInputRequestTypeDef,
     TimeToLiveDescriptionTypeDef,
+    EmptyResponseMetadataTypeDef,
     ExportSummaryTypeDef,
     ExportTableToPointInTimeInputRequestTypeDef,
     GetItemInputTableGetItemTypeDef,
     ProvisionedThroughputDescriptionTableTypeDef,
     ProvisionedThroughputDescriptionTypeDef,
     ProjectionServiceResourceTypeDef,
     S3BucketSourceTypeDef,
     KinesisStreamingDestinationInputRequestTypeDef,
-    PaginatorConfigTypeDef,
+    KinesisStreamingDestinationOutputTypeDef,
+    ListBackupsInputListBackupsPaginateTypeDef,
     ListBackupsInputRequestTypeDef,
     ListContributorInsightsInputRequestTypeDef,
     ListExportsInputRequestTypeDef,
     ListGlobalTablesInputRequestTypeDef,
     ListImportsInputRequestTypeDef,
+    ListTablesInputListTablesPaginateTypeDef,
     ListTablesInputRequestTypeDef,
+    ListTablesOutputTableTypeDef,
+    ListTablesOutputTypeDef,
+    ListTagsOfResourceInputListTagsOfResourcePaginateTypeDef,
     ListTagsOfResourceInputRequestTypeDef,
     TagTableTypeDef,
+    PaginatorConfigTypeDef,
     PointInTimeRecoverySpecificationTypeDef,
+    ProvisionedThroughputDescriptionResponseMetadataTypeDef,
     PutRequestServiceResourceTypeDef,
     TableClassSummaryTableTypeDef,
     TableClassSummaryTypeDef,
+    ResponseMetadataTypeDef,
+    RestoreSummaryResponseMetadataTypeDef,
     RestoreSummaryTableTypeDef,
     RestoreSummaryTypeDef,
+    SSEDescriptionResponseMetadataTypeDef,
     SSEDescriptionTableTypeDef,
     SSEDescriptionTypeDef,
     SSESpecificationTableTypeDef,
-    ServiceResourceTableRequestTypeDef,
+    StreamSpecificationResponseMetadataTypeDef,
     StreamSpecificationTableTypeDef,
     TableBatchWriterRequestTypeDef,
+    TableClassSummaryResponseMetadataTypeDef,
     TimeToLiveSpecificationTypeDef,
     UntagResourceInputRequestTypeDef,
     UpdateContributorInsightsInputRequestTypeDef,
-    ArchivalSummaryResponseMetadataTypeDef,
-    BillingModeSummaryResponseMetadataTypeDef,
-    DescribeLimitsOutputTypeDef,
-    EmptyResponseMetadataTypeDef,
-    KinesisStreamingDestinationOutputTypeDef,
-    ListTablesOutputTableTypeDef,
-    ListTablesOutputTypeDef,
-    ProvisionedThroughputDescriptionResponseMetadataTypeDef,
-    RestoreSummaryResponseMetadataTypeDef,
-    SSEDescriptionResponseMetadataTypeDef,
-    StreamSpecificationResponseMetadataTypeDef,
-    TableClassSummaryResponseMetadataTypeDef,
     UpdateContributorInsightsOutputTypeDef,
     AttributeValueUpdateTypeDef,
     BatchStatementRequestTypeDef,
     ConditionCheckTypeDef,
     ConditionTypeDef,
     DeleteRequestTypeDef,
     DeleteTypeDef,
@@ -600,15 +602,17 @@
     ListBackupsOutputTableTypeDef,
     ListBackupsOutputTypeDef,
     BatchGetItemInputServiceResourceBatchGetItemTypeDef,
     BatchStatementResponseTypeDef,
     ConsumedCapacityServiceResourceTypeDef,
     ConsumedCapacityTableTypeDef,
     ConsumedCapacityTypeDef,
+    QueryInputQueryPaginateTypeDef,
     QueryInputTableQueryTypeDef,
+    ScanInputScanPaginateTypeDef,
     ScanInputTableScanTypeDef,
     ContinuousBackupsDescriptionTypeDef,
     ListContributorInsightsOutputTypeDef,
     LocalSecondaryIndexDescriptionTableTypeDef,
     CreateGlobalSecondaryIndexActionTableTypeDef,
     UpdateGlobalSecondaryIndexActionTableTypeDef,
     LocalSecondaryIndexDescriptionTypeDef,
@@ -642,19 +646,14 @@
     DescribeTimeToLiveOutputTypeDef,
     ListExportsOutputTypeDef,
     GlobalSecondaryIndexDescriptionTableTypeDef,
     GlobalSecondaryIndexDescriptionTypeDef,
     GlobalSecondaryIndexServiceResourceTypeDef,
     LocalSecondaryIndexServiceResourceTypeDef,
     ImportSummaryTypeDef,
-    ListBackupsInputListBackupsPaginateTypeDef,
-    ListTablesInputListTablesPaginateTypeDef,
-    ListTagsOfResourceInputListTagsOfResourcePaginateTypeDef,
-    QueryInputQueryPaginateTypeDef,
-    ScanInputScanPaginateTypeDef,
     ListTagsOfResourceOutputTableTypeDef,
     UpdateContinuousBackupsInputRequestTypeDef,
     WriteRequestServiceResourceTypeDef,
     UpdateTimeToLiveInputRequestTypeDef,
     UpdateTimeToLiveOutputTypeDef,
     BatchExecuteStatementInputRequestTypeDef,
     QueryInputRequestTypeDef,
@@ -753,54 +752,54 @@
     UpdateTableReplicaAutoScalingInputRequestTypeDef,
     UpdateGlobalTableSettingsInputRequestTypeDef,
     DescribeTableReplicaAutoScalingOutputTypeDef,
     UpdateTableReplicaAutoScalingOutputTypeDef,
 )
 
 
-def get_structure() -> ResponseMetadataTypeDef:
+def get_structure() -> ArchivalSummaryResponseMetadataTypeDef:
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

### Comparing `types-aiobotocore-dynamodb-2.5.0.post1/types_aiobotocore_dynamodb.egg-info/SOURCES.txt` & `types-aiobotocore-dynamodb-2.5.1/types_aiobotocore_dynamodb.egg-info/SOURCES.txt`

 * *Files identical despite different names*

