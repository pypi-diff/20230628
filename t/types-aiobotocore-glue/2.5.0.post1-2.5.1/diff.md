# Comparing `tmp/types-aiobotocore-glue-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-glue-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-glue-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:41 2023, max compression
+gzip compressed data, was "types-aiobotocore-glue-2.5.1.tar", last modified: Wed Jun 28 01:43:33 2023, max compression
```

## Comparing `types-aiobotocore-glue-2.5.0.post1.tar` & `types-aiobotocore-glue-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:41.475245 types-aiobotocore-glue-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:15:11.000000 types-aiobotocore-glue-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    42203 2023-03-11 12:26:41.471244 types-aiobotocore-glue-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    40644 2023-03-11 12:15:11.000000 types-aiobotocore-glue-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:41.475245 types-aiobotocore-glue-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2079 2023-03-11 12:15:11.000000 types-aiobotocore-glue-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:41.471244 types-aiobotocore-glue-2.5.0.post1/types_aiobotocore_glue/
--rw-r--r--   0 runner    (1001) docker     (123)     4159 2023-03-11 12:15:11.000000 types-aiobotocore-glue-2.5.0.post1/types_aiobotocore_glue/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4158 2023-03-11 12:15:11.000000 types-aiobotocore-glue-2.5.0.post1/types_aiobotocore_glue/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      920 2023-03-11 12:15:11.000000 types-aiobotocore-glue-2.5.0.post1/types_aiobotocore_glue/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)   143417 2023-03-11 12:15:12.000000 types-aiobotocore-glue-2.5.0.post1/types_aiobotocore_glue/client.py
--rw-r--r--   0 runner    (1001) docker     (123)   143187 2023-03-11 12:15:11.000000 types-aiobotocore-glue-2.5.0.post1/types_aiobotocore_glue/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    20338 2023-03-11 12:15:12.000000 types-aiobotocore-glue-2.5.0.post1/types_aiobotocore_glue/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    20336 2023-03-11 12:15:12.000000 types-aiobotocore-glue-2.5.0.post1/types_aiobotocore_glue/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    22330 2023-03-11 12:15:12.000000 types-aiobotocore-glue-2.5.0.post1/types_aiobotocore_glue/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    22308 2023-03-11 12:15:12.000000 types-aiobotocore-glue-2.5.0.post1/types_aiobotocore_glue/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:15:11.000000 types-aiobotocore-glue-2.5.0.post1/types_aiobotocore_glue/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)   248934 2023-03-11 12:15:19.000000 types-aiobotocore-glue-2.5.0.post1/types_aiobotocore_glue/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)   248563 2023-03-11 12:15:16.000000 types-aiobotocore-glue-2.5.0.post1/types_aiobotocore_glue/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:15:11.000000 types-aiobotocore-glue-2.5.0.post1/types_aiobotocore_glue/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:41.471244 types-aiobotocore-glue-2.5.0.post1/types_aiobotocore_glue.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    42203 2023-03-11 12:26:41.000000 types-aiobotocore-glue-2.5.0.post1/types_aiobotocore_glue.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      756 2023-03-11 12:26:41.000000 types-aiobotocore-glue-2.5.0.post1/types_aiobotocore_glue.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:41.000000 types-aiobotocore-glue-2.5.0.post1/types_aiobotocore_glue.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:41.000000 types-aiobotocore-glue-2.5.0.post1/types_aiobotocore_glue.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:41.000000 types-aiobotocore-glue-2.5.0.post1/types_aiobotocore_glue.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       23 2023-03-11 12:26:41.000000 types-aiobotocore-glue-2.5.0.post1/types_aiobotocore_glue.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:33.046143 types-aiobotocore-glue-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:31:46.000000 types-aiobotocore-glue-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    42491 2023-06-28 01:43:33.042143 types-aiobotocore-glue-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    40938 2023-06-28 01:31:46.000000 types-aiobotocore-glue-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:33.046143 types-aiobotocore-glue-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2073 2023-06-28 01:31:46.000000 types-aiobotocore-glue-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:33.042143 types-aiobotocore-glue-2.5.1/types_aiobotocore_glue/
+-rw-r--r--   0 runner    (1001) docker     (123)     4159 2023-06-28 01:31:46.000000 types-aiobotocore-glue-2.5.1/types_aiobotocore_glue/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4158 2023-06-28 01:31:46.000000 types-aiobotocore-glue-2.5.1/types_aiobotocore_glue/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      908 2023-06-28 01:31:46.000000 types-aiobotocore-glue-2.5.1/types_aiobotocore_glue/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)   143750 2023-06-28 01:31:47.000000 types-aiobotocore-glue-2.5.1/types_aiobotocore_glue/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)   143520 2023-06-28 01:31:47.000000 types-aiobotocore-glue-2.5.1/types_aiobotocore_glue/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    20771 2023-06-28 01:31:49.000000 types-aiobotocore-glue-2.5.1/types_aiobotocore_glue/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20769 2023-06-28 01:31:49.000000 types-aiobotocore-glue-2.5.1/types_aiobotocore_glue/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    22272 2023-06-28 01:31:48.000000 types-aiobotocore-glue-2.5.1/types_aiobotocore_glue/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22251 2023-06-28 01:31:48.000000 types-aiobotocore-glue-2.5.1/types_aiobotocore_glue/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:31:46.000000 types-aiobotocore-glue-2.5.1/types_aiobotocore_glue/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)   253451 2023-06-28 01:31:55.000000 types-aiobotocore-glue-2.5.1/types_aiobotocore_glue/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)   253076 2023-06-28 01:31:52.000000 types-aiobotocore-glue-2.5.1/types_aiobotocore_glue/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:31:46.000000 types-aiobotocore-glue-2.5.1/types_aiobotocore_glue/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:33.042143 types-aiobotocore-glue-2.5.1/types_aiobotocore_glue.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    42491 2023-06-28 01:43:32.000000 types-aiobotocore-glue-2.5.1/types_aiobotocore_glue.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      756 2023-06-28 01:43:32.000000 types-aiobotocore-glue-2.5.1/types_aiobotocore_glue.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:32.000000 types-aiobotocore-glue-2.5.1/types_aiobotocore_glue.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:32.000000 types-aiobotocore-glue-2.5.1/types_aiobotocore_glue.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:32.000000 types-aiobotocore-glue-2.5.1/types_aiobotocore_glue.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       23 2023-06-28 01:43:32.000000 types-aiobotocore-glue-2.5.1/types_aiobotocore_glue.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-glue-2.5.0.post1/LICENSE` & `types-aiobotocore-glue-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-glue-2.5.0.post1/PKG-INFO` & `types-aiobotocore-glue-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-glue
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Glue 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Glue 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-glue"></a>
 
 # types-aiobotocore-glue
 
 [![PyPI - types-aiobotocore-glue](https://img.shields.io/pypi/v/types-aiobotocore-glue.svg?color=blue)](https://pypi.org/project/types-aiobotocore-glue)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-glue.svg?color=blue)](https://pypi.org/project/types-aiobotocore-glue)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-glue?color=blue)](https://pypistats.org/packages/types-aiobotocore-glue)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Glue 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue)
+[aiobotocore.Glue 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue)
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
 [types-aiobotocore-glue docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/).
 
 See how it helps to find and fix potential bugs:
 
@@ -344,14 +344,15 @@
 ### Literals
 
 `types_aiobotocore_glue.literals` module contains literals extracted from
 shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_glue.literals import (
+    AdditionalOptionKeysType,
     AggFunctionType,
     BackfillErrorCodeType,
     BlueprintRunStateType,
     BlueprintStatusType,
     CatalogEncryptionModeType,
     CloudWatchEncryptionModeType,
     ColumnStatisticsTypeType,
@@ -455,34 +456,35 @@
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
 
 
-def check_value(value: AggFunctionType) -> bool:
+def check_value(value: AdditionalOptionKeysType) -> bool:
     ...
 ```
 
 <a id="typed-dictionaries"></a>
 
 ### Typed dictionaries
 
 `types_aiobotocore_glue.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_glue.type_defs import (
     NotificationPropertyTypeDef,
     AggregateOperationTypeDef,
+    AmazonRedshiftAdvancedOptionTypeDef,
+    OptionTypeDef,
     ApplyMappingTypeDef,
     AuditContextTypeDef,
     PartitionValueListTypeDef,
     BasicCatalogTargetTypeDef,
-    ResponseMetadataTypeDef,
     BatchDeleteConnectionRequestRequestTypeDef,
     ErrorDetailTypeDef,
     BatchDeleteTableRequestRequestTypeDef,
     BatchDeleteTableVersionRequestRequestTypeDef,
     BatchGetBlueprintsRequestRequestTypeDef,
     BatchGetCrawlersRequestRequestTypeDef,
     BatchGetCustomEntityTypesRequestRequestTypeDef,
@@ -499,24 +501,26 @@
     BlueprintDetailsTypeDef,
     BlueprintRunTypeDef,
     LastActiveDefinitionTypeDef,
     BooleanColumnStatisticsDataTypeDef,
     CancelDataQualityRuleRecommendationRunRequestRequestTypeDef,
     CancelDataQualityRulesetEvaluationRunRequestRequestTypeDef,
     CancelMLTaskRunRequestRequestTypeDef,
+    CancelMLTaskRunResponseTypeDef,
     CancelStatementRequestRequestTypeDef,
     CatalogEntryTypeDef,
     CatalogImportStatusTypeDef,
     KafkaStreamingSourceOptionsTypeDef,
     StreamingDataPreviewOptionsTypeDef,
     KinesisStreamingSourceOptionsTypeDef,
     CatalogSchemaChangePolicyTypeDef,
     CatalogSourceTypeDef,
     CatalogTargetTypeDef,
     CheckSchemaVersionValidityInputRequestTypeDef,
+    CheckSchemaVersionValidityResponseTypeDef,
     CsvClassifierTypeDef,
     GrokClassifierTypeDef,
     JsonClassifierTypeDef,
     XMLClassifierTypeDef,
     CloudWatchEncryptionTypeDef,
     DirectJDBCSourceTypeDef,
     DropDuplicatesTypeDef,
@@ -567,282 +571,299 @@
     LastCrawlInfoTypeDef,
     LineageConfigurationTypeDef,
     RecrawlPolicyTypeDef,
     ScheduleTypeDef,
     SchemaChangePolicyTypeDef,
     CrawlsFilterTypeDef,
     CreateBlueprintRequestRequestTypeDef,
+    CreateBlueprintResponseTypeDef,
     CreateCsvClassifierRequestTypeDef,
     CreateGrokClassifierRequestTypeDef,
     CreateJsonClassifierRequestTypeDef,
     CreateXMLClassifierRequestTypeDef,
     CreateCustomEntityTypeRequestRequestTypeDef,
+    CreateCustomEntityTypeResponseTypeDef,
     DataQualityTargetTableTypeDef,
+    CreateDataQualityRulesetResponseTypeDef,
     CreateDevEndpointRequestRequestTypeDef,
+    CreateDevEndpointResponseTypeDef,
     ExecutionPropertyTypeDef,
     JobCommandTypeDef,
     SourceControlDetailsTypeDef,
+    CreateJobResponseTypeDef,
     GlueTableTypeDef,
+    CreateMLTransformResponseTypeDef,
     PartitionIndexTypeDef,
     CreateRegistryInputRequestTypeDef,
+    CreateRegistryResponseTypeDef,
     RegistryIdTypeDef,
+    CreateSchemaResponseTypeDef,
+    CreateScriptResponseTypeDef,
+    CreateSecurityConfigurationResponseTypeDef,
     SessionCommandTypeDef,
     EventBatchingConditionTypeDef,
+    CreateTriggerResponseTypeDef,
     CreateWorkflowRequestRequestTypeDef,
+    CreateWorkflowResponseTypeDef,
     DQResultsPublishingOptionsTypeDef,
     DQStopJobOnFailureOptionsTypeDef,
     EncryptionAtRestTypeDef,
     DataLakePrincipalTypeDef,
     DataQualityEvaluationRunAdditionalRunOptionsTypeDef,
     DataQualityRuleResultTypeDef,
     DatabaseIdentifierTypeDef,
+    FederatedDatabaseTypeDef,
     DatatypeTypeDef,
     DecimalNumberTypeDef,
     DeleteBlueprintRequestRequestTypeDef,
+    DeleteBlueprintResponseTypeDef,
     DeleteClassifierRequestRequestTypeDef,
     DeleteColumnStatisticsForPartitionRequestRequestTypeDef,
     DeleteColumnStatisticsForTableRequestRequestTypeDef,
     DeleteConnectionRequestRequestTypeDef,
     DeleteCrawlerRequestRequestTypeDef,
     DeleteCustomEntityTypeRequestRequestTypeDef,
+    DeleteCustomEntityTypeResponseTypeDef,
     DeleteDataQualityRulesetRequestRequestTypeDef,
     DeleteDatabaseRequestRequestTypeDef,
     DeleteDevEndpointRequestRequestTypeDef,
     DeleteJobRequestRequestTypeDef,
+    DeleteJobResponseTypeDef,
     DeleteMLTransformRequestRequestTypeDef,
+    DeleteMLTransformResponseTypeDef,
     DeletePartitionIndexRequestRequestTypeDef,
     DeletePartitionRequestRequestTypeDef,
+    DeleteRegistryResponseTypeDef,
     DeleteResourcePolicyRequestRequestTypeDef,
     SchemaIdTypeDef,
+    DeleteSchemaResponseTypeDef,
     DeleteSecurityConfigurationRequestRequestTypeDef,
     DeleteSessionRequestRequestTypeDef,
+    DeleteSessionResponseTypeDef,
     DeleteTableRequestRequestTypeDef,
     DeleteTableVersionRequestRequestTypeDef,
     DeleteTriggerRequestRequestTypeDef,
+    DeleteTriggerResponseTypeDef,
     DeleteUserDefinedFunctionRequestRequestTypeDef,
     DeleteWorkflowRequestRequestTypeDef,
+    DeleteWorkflowResponseTypeDef,
     DevEndpointCustomLibrariesTypeDef,
     DirectSchemaChangePolicyTypeDef,
     NullCheckBoxListTypeDef,
     TransformConfigParameterTypeDef,
     EdgeTypeDef,
     JobBookmarksEncryptionTypeDef,
     S3EncryptionTypeDef,
     ErrorDetailsTypeDef,
     ExportLabelsTaskRunPropertiesTypeDef,
+    FederatedTableTypeDef,
     FilterValueTypeDef,
     FindMatchesParametersTypeDef,
     FindMatchesTaskRunPropertiesTypeDef,
     GetBlueprintRequestRequestTypeDef,
     GetBlueprintRunRequestRequestTypeDef,
     GetBlueprintRunsRequestRequestTypeDef,
     GetCatalogImportStatusRequestRequestTypeDef,
     GetClassifierRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetClassifiersRequestGetClassifiersPaginateTypeDef,
     GetClassifiersRequestRequestTypeDef,
     GetColumnStatisticsForPartitionRequestRequestTypeDef,
     GetColumnStatisticsForTableRequestRequestTypeDef,
     GetConnectionRequestRequestTypeDef,
     GetConnectionsFilterTypeDef,
+    GetCrawlerMetricsRequestGetCrawlerMetricsPaginateTypeDef,
     GetCrawlerMetricsRequestRequestTypeDef,
     GetCrawlerRequestRequestTypeDef,
+    GetCrawlersRequestGetCrawlersPaginateTypeDef,
     GetCrawlersRequestRequestTypeDef,
     GetCustomEntityTypeRequestRequestTypeDef,
+    GetCustomEntityTypeResponseTypeDef,
     GetDataCatalogEncryptionSettingsRequestRequestTypeDef,
     GetDataQualityResultRequestRequestTypeDef,
     GetDataQualityRuleRecommendationRunRequestRequestTypeDef,
     GetDataQualityRulesetEvaluationRunRequestRequestTypeDef,
     GetDataQualityRulesetRequestRequestTypeDef,
     GetDatabaseRequestRequestTypeDef,
+    GetDatabasesRequestGetDatabasesPaginateTypeDef,
     GetDatabasesRequestRequestTypeDef,
     GetDataflowGraphRequestRequestTypeDef,
     GetDevEndpointRequestRequestTypeDef,
+    GetDevEndpointsRequestGetDevEndpointsPaginateTypeDef,
     GetDevEndpointsRequestRequestTypeDef,
     GetJobBookmarkRequestRequestTypeDef,
     JobBookmarkEntryTypeDef,
     GetJobRequestRequestTypeDef,
     GetJobRunRequestRequestTypeDef,
+    GetJobRunsRequestGetJobRunsPaginateTypeDef,
     GetJobRunsRequestRequestTypeDef,
+    GetJobsRequestGetJobsPaginateTypeDef,
     GetJobsRequestRequestTypeDef,
     GetMLTaskRunRequestRequestTypeDef,
     TaskRunFilterCriteriaTypeDef,
     TaskRunSortCriteriaTypeDef,
     GetMLTransformRequestRequestTypeDef,
     SchemaColumnTypeDef,
     TransformSortCriteriaTypeDef,
     MappingEntryTypeDef,
+    GetPartitionIndexesRequestGetPartitionIndexesPaginateTypeDef,
     GetPartitionIndexesRequestRequestTypeDef,
     GetPartitionRequestRequestTypeDef,
     SegmentTypeDef,
+    GetPlanResponseTypeDef,
+    GetRegistryResponseTypeDef,
+    GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef,
     GetResourcePoliciesRequestRequestTypeDef,
     GluePolicyTypeDef,
     GetResourcePolicyRequestRequestTypeDef,
+    GetResourcePolicyResponseTypeDef,
+    GetSchemaByDefinitionResponseTypeDef,
+    GetSchemaResponseTypeDef,
     SchemaVersionNumberTypeDef,
+    GetSchemaVersionResponseTypeDef,
+    GetSchemaVersionsDiffResponseTypeDef,
     GetSecurityConfigurationRequestRequestTypeDef,
+    GetSecurityConfigurationsRequestGetSecurityConfigurationsPaginateTypeDef,
     GetSecurityConfigurationsRequestRequestTypeDef,
     GetSessionRequestRequestTypeDef,
     GetStatementRequestRequestTypeDef,
     GetTableRequestRequestTypeDef,
     GetTableVersionRequestRequestTypeDef,
+    GetTableVersionsRequestGetTableVersionsPaginateTypeDef,
     GetTableVersionsRequestRequestTypeDef,
+    GetTablesRequestGetTablesPaginateTypeDef,
     GetTablesRequestRequestTypeDef,
     GetTagsRequestRequestTypeDef,
+    GetTagsResponseTypeDef,
     GetTriggerRequestRequestTypeDef,
+    GetTriggersRequestGetTriggersPaginateTypeDef,
     GetTriggersRequestRequestTypeDef,
     GetUserDefinedFunctionRequestRequestTypeDef,
+    GetUserDefinedFunctionsRequestGetUserDefinedFunctionsPaginateTypeDef,
     GetUserDefinedFunctionsRequestRequestTypeDef,
     GetWorkflowRequestRequestTypeDef,
     GetWorkflowRunPropertiesRequestRequestTypeDef,
+    GetWorkflowRunPropertiesResponseTypeDef,
     GetWorkflowRunRequestRequestTypeDef,
     GetWorkflowRunsRequestRequestTypeDef,
     GlueStudioSchemaColumnTypeDef,
     S3SourceAdditionalOptionsTypeDef,
     ImportCatalogToGlueRequestRequestTypeDef,
     ImportLabelsTaskRunPropertiesTypeDef,
     JDBCConnectorOptionsTypeDef,
     PredecessorTypeDef,
     JoinColumnTypeDef,
     KeySchemaElementTypeDef,
     LabelingSetGenerationTaskRunPropertiesTypeDef,
     ListBlueprintsRequestRequestTypeDef,
+    ListBlueprintsResponseTypeDef,
     ListCrawlersRequestRequestTypeDef,
+    ListCrawlersResponseTypeDef,
     ListCustomEntityTypesRequestRequestTypeDef,
     ListDevEndpointsRequestRequestTypeDef,
+    ListDevEndpointsResponseTypeDef,
     ListJobsRequestRequestTypeDef,
+    ListJobsResponseTypeDef,
+    ListMLTransformsResponseTypeDef,
+    ListRegistriesInputListRegistriesPaginateTypeDef,
     ListRegistriesInputRequestTypeDef,
     RegistryListItemTypeDef,
     SchemaVersionListItemTypeDef,
     SchemaListItemTypeDef,
     ListSessionsRequestRequestTypeDef,
     ListStatementsRequestRequestTypeDef,
     ListTriggersRequestRequestTypeDef,
+    ListTriggersResponseTypeDef,
     ListWorkflowsRequestRequestTypeDef,
+    ListWorkflowsResponseTypeDef,
     MLUserDataEncryptionTypeDef,
     MappingTypeDef,
     OtherMetadataValueListItemTypeDef,
     MetadataKeyValuePairTypeDef,
     OrderTypeDef,
+    PaginatorConfigTypeDef,
     PropertyPredicateTypeDef,
     PutResourcePolicyRequestRequestTypeDef,
+    PutResourcePolicyResponseTypeDef,
+    PutSchemaVersionMetadataResponseTypeDef,
     PutWorkflowRunPropertiesRequestRequestTypeDef,
     UpsertRedshiftTargetOptionsTypeDef,
+    RegisterSchemaVersionResponseTypeDef,
+    RemoveSchemaVersionMetadataResponseTypeDef,
     ResetJobBookmarkRequestRequestTypeDef,
     ResourceUriTypeDef,
+    ResponseMetadataTypeDef,
     ResumeWorkflowRunRequestRequestTypeDef,
+    ResumeWorkflowRunResponseTypeDef,
     RunStatementRequestRequestTypeDef,
+    RunStatementResponseTypeDef,
     S3DirectSourceAdditionalOptionsTypeDef,
     SortCriterionTypeDef,
     SerDeInfoTypeDef,
     SkewedInfoTypeDef,
     SqlAliasTypeDef,
     StartBlueprintRunRequestRequestTypeDef,
+    StartBlueprintRunResponseTypeDef,
     StartCrawlerRequestRequestTypeDef,
     StartCrawlerScheduleRequestRequestTypeDef,
+    StartDataQualityRuleRecommendationRunResponseTypeDef,
+    StartDataQualityRulesetEvaluationRunResponseTypeDef,
     StartExportLabelsTaskRunRequestRequestTypeDef,
+    StartExportLabelsTaskRunResponseTypeDef,
     StartImportLabelsTaskRunRequestRequestTypeDef,
+    StartImportLabelsTaskRunResponseTypeDef,
+    StartJobRunResponseTypeDef,
     StartMLEvaluationTaskRunRequestRequestTypeDef,
+    StartMLEvaluationTaskRunResponseTypeDef,
     StartMLLabelingSetGenerationTaskRunRequestRequestTypeDef,
+    StartMLLabelingSetGenerationTaskRunResponseTypeDef,
     StartTriggerRequestRequestTypeDef,
+    StartTriggerResponseTypeDef,
     StartWorkflowRunRequestRequestTypeDef,
+    StartWorkflowRunResponseTypeDef,
     StartingEventBatchConditionTypeDef,
     StatementOutputDataTypeDef,
     StopCrawlerRequestRequestTypeDef,
     StopCrawlerScheduleRequestRequestTypeDef,
     StopSessionRequestRequestTypeDef,
+    StopSessionResponseTypeDef,
     StopTriggerRequestRequestTypeDef,
+    StopTriggerResponseTypeDef,
     StopWorkflowRunRequestRequestTypeDef,
     TableIdentifierTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateBlueprintRequestRequestTypeDef,
+    UpdateBlueprintResponseTypeDef,
     UpdateCsvClassifierRequestTypeDef,
     UpdateGrokClassifierRequestTypeDef,
     UpdateJsonClassifierRequestTypeDef,
     UpdateXMLClassifierRequestTypeDef,
     UpdateCrawlerScheduleRequestRequestTypeDef,
     UpdateDataQualityRulesetRequestRequestTypeDef,
+    UpdateDataQualityRulesetResponseTypeDef,
     UpdateJobFromSourceControlRequestRequestTypeDef,
+    UpdateJobFromSourceControlResponseTypeDef,
+    UpdateJobResponseTypeDef,
+    UpdateMLTransformResponseTypeDef,
+    UpdateRegistryResponseTypeDef,
+    UpdateSchemaResponseTypeDef,
     UpdateSourceControlFromJobRequestRequestTypeDef,
+    UpdateSourceControlFromJobResponseTypeDef,
     UpdateWorkflowRequestRequestTypeDef,
+    UpdateWorkflowResponseTypeDef,
     WorkflowRunStatisticsTypeDef,
     ActionTypeDef,
     StartJobRunRequestRequestTypeDef,
     AggregateTypeDef,
+    AmazonRedshiftNodeDataTypeDef,
     GetUnfilteredPartitionMetadataRequestRequestTypeDef,
     GetUnfilteredTableMetadataRequestRequestTypeDef,
     BackfillErrorTypeDef,
     BatchDeletePartitionRequestRequestTypeDef,
     BatchGetPartitionRequestRequestTypeDef,
-    CancelMLTaskRunResponseTypeDef,
-    CheckSchemaVersionValidityResponseTypeDef,
-    CreateBlueprintResponseTypeDef,
-    CreateCustomEntityTypeResponseTypeDef,
-    CreateDataQualityRulesetResponseTypeDef,
-    CreateDevEndpointResponseTypeDef,
-    CreateJobResponseTypeDef,
-    CreateMLTransformResponseTypeDef,
-    CreateRegistryResponseTypeDef,
-    CreateSchemaResponseTypeDef,
-    CreateScriptResponseTypeDef,
-    CreateSecurityConfigurationResponseTypeDef,
-    CreateTriggerResponseTypeDef,
-    CreateWorkflowResponseTypeDef,
-    DeleteBlueprintResponseTypeDef,
-    DeleteCustomEntityTypeResponseTypeDef,
-    DeleteJobResponseTypeDef,
-    DeleteMLTransformResponseTypeDef,
-    DeleteRegistryResponseTypeDef,
-    DeleteSchemaResponseTypeDef,
-    DeleteSessionResponseTypeDef,
-    DeleteTriggerResponseTypeDef,
-    DeleteWorkflowResponseTypeDef,
-    GetCustomEntityTypeResponseTypeDef,
-    GetPlanResponseTypeDef,
-    GetRegistryResponseTypeDef,
-    GetResourcePolicyResponseTypeDef,
-    GetSchemaByDefinitionResponseTypeDef,
-    GetSchemaResponseTypeDef,
-    GetSchemaVersionResponseTypeDef,
-    GetSchemaVersionsDiffResponseTypeDef,
-    GetTagsResponseTypeDef,
-    GetWorkflowRunPropertiesResponseTypeDef,
-    ListBlueprintsResponseTypeDef,
-    ListCrawlersResponseTypeDef,
-    ListDevEndpointsResponseTypeDef,
-    ListJobsResponseTypeDef,
-    ListMLTransformsResponseTypeDef,
-    ListTriggersResponseTypeDef,
-    ListWorkflowsResponseTypeDef,
-    PutResourcePolicyResponseTypeDef,
-    PutSchemaVersionMetadataResponseTypeDef,
-    RegisterSchemaVersionResponseTypeDef,
-    RemoveSchemaVersionMetadataResponseTypeDef,
-    ResumeWorkflowRunResponseTypeDef,
-    RunStatementResponseTypeDef,
-    StartBlueprintRunResponseTypeDef,
-    StartDataQualityRuleRecommendationRunResponseTypeDef,
-    StartDataQualityRulesetEvaluationRunResponseTypeDef,
-    StartExportLabelsTaskRunResponseTypeDef,
-    StartImportLabelsTaskRunResponseTypeDef,
-    StartJobRunResponseTypeDef,
-    StartMLEvaluationTaskRunResponseTypeDef,
-    StartMLLabelingSetGenerationTaskRunResponseTypeDef,
-    StartTriggerResponseTypeDef,
-    StartWorkflowRunResponseTypeDef,
-    StopSessionResponseTypeDef,
-    StopTriggerResponseTypeDef,
-    UpdateBlueprintResponseTypeDef,
-    UpdateDataQualityRulesetResponseTypeDef,
-    UpdateJobFromSourceControlResponseTypeDef,
-    UpdateJobResponseTypeDef,
-    UpdateMLTransformResponseTypeDef,
-    UpdateRegistryResponseTypeDef,
-    UpdateSchemaResponseTypeDef,
-    UpdateSourceControlFromJobResponseTypeDef,
-    UpdateWorkflowResponseTypeDef,
     BatchDeleteConnectionResponseTypeDef,
     BatchStopJobRunErrorTypeDef,
     BatchUpdatePartitionFailureEntryTypeDef,
     ColumnErrorTypeDef,
     PartitionErrorTypeDef,
     TableErrorTypeDef,
     TableVersionErrorTypeDef,
@@ -881,57 +902,42 @@
     DataQualityRulesetListDetailsTypeDef,
     GetDataQualityRulesetResponseTypeDef,
     DataSourceTypeDef,
     CreatePartitionIndexRequestRequestTypeDef,
     CreateSchemaInputRequestTypeDef,
     DeleteRegistryInputRequestTypeDef,
     GetRegistryInputRequestTypeDef,
+    ListSchemasInputListSchemasPaginateTypeDef,
     ListSchemasInputRequestTypeDef,
     UpdateRegistryInputRequestTypeDef,
     CreateSessionRequestRequestTypeDef,
     SessionTypeDef,
+    EvaluateDataQualityMultiFrameTypeDef,
     EvaluateDataQualityTypeDef,
     DataCatalogEncryptionSettingsTypeDef,
     PrincipalPermissionsTypeDef,
     NullValueFieldTypeDef,
     DecimalColumnStatisticsDataTypeDef,
     DeleteSchemaInputRequestTypeDef,
     DeleteSchemaVersionsInputRequestTypeDef,
     GetSchemaByDefinitionInputRequestTypeDef,
     GetSchemaInputRequestTypeDef,
+    ListSchemaVersionsInputListSchemaVersionsPaginateTypeDef,
     ListSchemaVersionsInputRequestTypeDef,
     RegisterSchemaVersionInputRequestTypeDef,
     SchemaReferenceTypeDef,
     UpdateDevEndpointRequestRequestTypeDef,
     S3DeltaDirectTargetTypeDef,
     S3DirectTargetTypeDef,
     S3GlueParquetTargetTypeDef,
     S3HudiDirectTargetTypeDef,
-    DynamicTransformTypeDef,
     EncryptionConfigurationTypeDef,
     SchemaVersionErrorItemTypeDef,
     FilterExpressionTypeDef,
     TransformParametersTypeDef,
-    GetClassifiersRequestGetClassifiersPaginateTypeDef,
-    GetCrawlerMetricsRequestGetCrawlerMetricsPaginateTypeDef,
-    GetCrawlersRequestGetCrawlersPaginateTypeDef,
-    GetDatabasesRequestGetDatabasesPaginateTypeDef,
-    GetDevEndpointsRequestGetDevEndpointsPaginateTypeDef,
-    GetJobRunsRequestGetJobRunsPaginateTypeDef,
-    GetJobsRequestGetJobsPaginateTypeDef,
-    GetPartitionIndexesRequestGetPartitionIndexesPaginateTypeDef,
-    GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef,
-    GetSecurityConfigurationsRequestGetSecurityConfigurationsPaginateTypeDef,
-    GetTableVersionsRequestGetTableVersionsPaginateTypeDef,
-    GetTablesRequestGetTablesPaginateTypeDef,
-    GetTriggersRequestGetTriggersPaginateTypeDef,
-    GetUserDefinedFunctionsRequestGetUserDefinedFunctionsPaginateTypeDef,
-    ListRegistriesInputListRegistriesPaginateTypeDef,
-    ListSchemaVersionsInputListSchemaVersionsPaginateTypeDef,
-    ListSchemasInputListSchemasPaginateTypeDef,
     GetConnectionsRequestGetConnectionsPaginateTypeDef,
     GetConnectionsRequestRequestTypeDef,
     GetJobBookmarkResponseTypeDef,
     ResetJobBookmarkResponseTypeDef,
     GetMLTaskRunsRequestRequestTypeDef,
     TransformFilterCriteriaTypeDef,
     GetMappingResponseTypeDef,
@@ -958,14 +964,16 @@
     RemoveSchemaVersionMetadataInputRequestTypeDef,
     RedshiftTargetTypeDef,
     UserDefinedFunctionInputTypeDef,
     UserDefinedFunctionTypeDef,
     SearchTablesRequestRequestTypeDef,
     StatementOutputTypeDef,
     UpdateClassifierRequestRequestTypeDef,
+    AmazonRedshiftSourceTypeDef,
+    AmazonRedshiftTargetTypeDef,
     PartitionIndexDescriptorTypeDef,
     BatchStopJobRunResponseTypeDef,
     BatchUpdatePartitionResponseTypeDef,
     BatchCreatePartitionResponseTypeDef,
     BatchDeletePartitionResponseTypeDef,
     BatchDeleteTableResponseTypeDef,
     BatchDeleteTableVersionResponseTypeDef,
@@ -1019,14 +1027,15 @@
     UpdateMLTransformRequestRequestTypeDef,
     GetMLTransformsRequestRequestTypeDef,
     ListMLTransformsRequestRequestTypeDef,
     AthenaConnectorSourceTypeDef,
     CatalogDeltaSourceTypeDef,
     CatalogHudiSourceTypeDef,
     CustomCodeTypeDef,
+    DynamicTransformTypeDef,
     JDBCConnectorSourceTypeDef,
     JDBCConnectorTargetTypeDef,
     S3CatalogDeltaSourceTypeDef,
     S3CatalogHudiSourceTypeDef,
     S3CsvSourceTypeDef,
     S3DeltaSourceTypeDef,
     S3HudiSourceTypeDef,
@@ -1134,43 +1143,43 @@
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

### Comparing `types-aiobotocore-glue-2.5.0.post1/README.md` & `types-aiobotocore-glue-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-glue"></a>
 
 # types-aiobotocore-glue
 
 [![PyPI - types-aiobotocore-glue](https://img.shields.io/pypi/v/types-aiobotocore-glue.svg?color=blue)](https://pypi.org/project/types-aiobotocore-glue)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-glue.svg?color=blue)](https://pypi.org/project/types-aiobotocore-glue)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-glue?color=blue)](https://pypistats.org/packages/types-aiobotocore-glue)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Glue 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue)
+[aiobotocore.Glue 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue)
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
 [types-aiobotocore-glue docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/).
 
 See how it helps to find and fix potential bugs:
 
@@ -311,14 +311,15 @@
 ### Literals
 
 `types_aiobotocore_glue.literals` module contains literals extracted from
 shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_glue.literals import (
+    AdditionalOptionKeysType,
     AggFunctionType,
     BackfillErrorCodeType,
     BlueprintRunStateType,
     BlueprintStatusType,
     CatalogEncryptionModeType,
     CloudWatchEncryptionModeType,
     ColumnStatisticsTypeType,
@@ -422,34 +423,35 @@
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
 
 
-def check_value(value: AggFunctionType) -> bool:
+def check_value(value: AdditionalOptionKeysType) -> bool:
     ...
 ```
 
 <a id="typed-dictionaries"></a>
 
 ### Typed dictionaries
 
 `types_aiobotocore_glue.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_glue.type_defs import (
     NotificationPropertyTypeDef,
     AggregateOperationTypeDef,
+    AmazonRedshiftAdvancedOptionTypeDef,
+    OptionTypeDef,
     ApplyMappingTypeDef,
     AuditContextTypeDef,
     PartitionValueListTypeDef,
     BasicCatalogTargetTypeDef,
-    ResponseMetadataTypeDef,
     BatchDeleteConnectionRequestRequestTypeDef,
     ErrorDetailTypeDef,
     BatchDeleteTableRequestRequestTypeDef,
     BatchDeleteTableVersionRequestRequestTypeDef,
     BatchGetBlueprintsRequestRequestTypeDef,
     BatchGetCrawlersRequestRequestTypeDef,
     BatchGetCustomEntityTypesRequestRequestTypeDef,
@@ -466,24 +468,26 @@
     BlueprintDetailsTypeDef,
     BlueprintRunTypeDef,
     LastActiveDefinitionTypeDef,
     BooleanColumnStatisticsDataTypeDef,
     CancelDataQualityRuleRecommendationRunRequestRequestTypeDef,
     CancelDataQualityRulesetEvaluationRunRequestRequestTypeDef,
     CancelMLTaskRunRequestRequestTypeDef,
+    CancelMLTaskRunResponseTypeDef,
     CancelStatementRequestRequestTypeDef,
     CatalogEntryTypeDef,
     CatalogImportStatusTypeDef,
     KafkaStreamingSourceOptionsTypeDef,
     StreamingDataPreviewOptionsTypeDef,
     KinesisStreamingSourceOptionsTypeDef,
     CatalogSchemaChangePolicyTypeDef,
     CatalogSourceTypeDef,
     CatalogTargetTypeDef,
     CheckSchemaVersionValidityInputRequestTypeDef,
+    CheckSchemaVersionValidityResponseTypeDef,
     CsvClassifierTypeDef,
     GrokClassifierTypeDef,
     JsonClassifierTypeDef,
     XMLClassifierTypeDef,
     CloudWatchEncryptionTypeDef,
     DirectJDBCSourceTypeDef,
     DropDuplicatesTypeDef,
@@ -534,282 +538,299 @@
     LastCrawlInfoTypeDef,
     LineageConfigurationTypeDef,
     RecrawlPolicyTypeDef,
     ScheduleTypeDef,
     SchemaChangePolicyTypeDef,
     CrawlsFilterTypeDef,
     CreateBlueprintRequestRequestTypeDef,
+    CreateBlueprintResponseTypeDef,
     CreateCsvClassifierRequestTypeDef,
     CreateGrokClassifierRequestTypeDef,
     CreateJsonClassifierRequestTypeDef,
     CreateXMLClassifierRequestTypeDef,
     CreateCustomEntityTypeRequestRequestTypeDef,
+    CreateCustomEntityTypeResponseTypeDef,
     DataQualityTargetTableTypeDef,
+    CreateDataQualityRulesetResponseTypeDef,
     CreateDevEndpointRequestRequestTypeDef,
+    CreateDevEndpointResponseTypeDef,
     ExecutionPropertyTypeDef,
     JobCommandTypeDef,
     SourceControlDetailsTypeDef,
+    CreateJobResponseTypeDef,
     GlueTableTypeDef,
+    CreateMLTransformResponseTypeDef,
     PartitionIndexTypeDef,
     CreateRegistryInputRequestTypeDef,
+    CreateRegistryResponseTypeDef,
     RegistryIdTypeDef,
+    CreateSchemaResponseTypeDef,
+    CreateScriptResponseTypeDef,
+    CreateSecurityConfigurationResponseTypeDef,
     SessionCommandTypeDef,
     EventBatchingConditionTypeDef,
+    CreateTriggerResponseTypeDef,
     CreateWorkflowRequestRequestTypeDef,
+    CreateWorkflowResponseTypeDef,
     DQResultsPublishingOptionsTypeDef,
     DQStopJobOnFailureOptionsTypeDef,
     EncryptionAtRestTypeDef,
     DataLakePrincipalTypeDef,
     DataQualityEvaluationRunAdditionalRunOptionsTypeDef,
     DataQualityRuleResultTypeDef,
     DatabaseIdentifierTypeDef,
+    FederatedDatabaseTypeDef,
     DatatypeTypeDef,
     DecimalNumberTypeDef,
     DeleteBlueprintRequestRequestTypeDef,
+    DeleteBlueprintResponseTypeDef,
     DeleteClassifierRequestRequestTypeDef,
     DeleteColumnStatisticsForPartitionRequestRequestTypeDef,
     DeleteColumnStatisticsForTableRequestRequestTypeDef,
     DeleteConnectionRequestRequestTypeDef,
     DeleteCrawlerRequestRequestTypeDef,
     DeleteCustomEntityTypeRequestRequestTypeDef,
+    DeleteCustomEntityTypeResponseTypeDef,
     DeleteDataQualityRulesetRequestRequestTypeDef,
     DeleteDatabaseRequestRequestTypeDef,
     DeleteDevEndpointRequestRequestTypeDef,
     DeleteJobRequestRequestTypeDef,
+    DeleteJobResponseTypeDef,
     DeleteMLTransformRequestRequestTypeDef,
+    DeleteMLTransformResponseTypeDef,
     DeletePartitionIndexRequestRequestTypeDef,
     DeletePartitionRequestRequestTypeDef,
+    DeleteRegistryResponseTypeDef,
     DeleteResourcePolicyRequestRequestTypeDef,
     SchemaIdTypeDef,
+    DeleteSchemaResponseTypeDef,
     DeleteSecurityConfigurationRequestRequestTypeDef,
     DeleteSessionRequestRequestTypeDef,
+    DeleteSessionResponseTypeDef,
     DeleteTableRequestRequestTypeDef,
     DeleteTableVersionRequestRequestTypeDef,
     DeleteTriggerRequestRequestTypeDef,
+    DeleteTriggerResponseTypeDef,
     DeleteUserDefinedFunctionRequestRequestTypeDef,
     DeleteWorkflowRequestRequestTypeDef,
+    DeleteWorkflowResponseTypeDef,
     DevEndpointCustomLibrariesTypeDef,
     DirectSchemaChangePolicyTypeDef,
     NullCheckBoxListTypeDef,
     TransformConfigParameterTypeDef,
     EdgeTypeDef,
     JobBookmarksEncryptionTypeDef,
     S3EncryptionTypeDef,
     ErrorDetailsTypeDef,
     ExportLabelsTaskRunPropertiesTypeDef,
+    FederatedTableTypeDef,
     FilterValueTypeDef,
     FindMatchesParametersTypeDef,
     FindMatchesTaskRunPropertiesTypeDef,
     GetBlueprintRequestRequestTypeDef,
     GetBlueprintRunRequestRequestTypeDef,
     GetBlueprintRunsRequestRequestTypeDef,
     GetCatalogImportStatusRequestRequestTypeDef,
     GetClassifierRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetClassifiersRequestGetClassifiersPaginateTypeDef,
     GetClassifiersRequestRequestTypeDef,
     GetColumnStatisticsForPartitionRequestRequestTypeDef,
     GetColumnStatisticsForTableRequestRequestTypeDef,
     GetConnectionRequestRequestTypeDef,
     GetConnectionsFilterTypeDef,
+    GetCrawlerMetricsRequestGetCrawlerMetricsPaginateTypeDef,
     GetCrawlerMetricsRequestRequestTypeDef,
     GetCrawlerRequestRequestTypeDef,
+    GetCrawlersRequestGetCrawlersPaginateTypeDef,
     GetCrawlersRequestRequestTypeDef,
     GetCustomEntityTypeRequestRequestTypeDef,
+    GetCustomEntityTypeResponseTypeDef,
     GetDataCatalogEncryptionSettingsRequestRequestTypeDef,
     GetDataQualityResultRequestRequestTypeDef,
     GetDataQualityRuleRecommendationRunRequestRequestTypeDef,
     GetDataQualityRulesetEvaluationRunRequestRequestTypeDef,
     GetDataQualityRulesetRequestRequestTypeDef,
     GetDatabaseRequestRequestTypeDef,
+    GetDatabasesRequestGetDatabasesPaginateTypeDef,
     GetDatabasesRequestRequestTypeDef,
     GetDataflowGraphRequestRequestTypeDef,
     GetDevEndpointRequestRequestTypeDef,
+    GetDevEndpointsRequestGetDevEndpointsPaginateTypeDef,
     GetDevEndpointsRequestRequestTypeDef,
     GetJobBookmarkRequestRequestTypeDef,
     JobBookmarkEntryTypeDef,
     GetJobRequestRequestTypeDef,
     GetJobRunRequestRequestTypeDef,
+    GetJobRunsRequestGetJobRunsPaginateTypeDef,
     GetJobRunsRequestRequestTypeDef,
+    GetJobsRequestGetJobsPaginateTypeDef,
     GetJobsRequestRequestTypeDef,
     GetMLTaskRunRequestRequestTypeDef,
     TaskRunFilterCriteriaTypeDef,
     TaskRunSortCriteriaTypeDef,
     GetMLTransformRequestRequestTypeDef,
     SchemaColumnTypeDef,
     TransformSortCriteriaTypeDef,
     MappingEntryTypeDef,
+    GetPartitionIndexesRequestGetPartitionIndexesPaginateTypeDef,
     GetPartitionIndexesRequestRequestTypeDef,
     GetPartitionRequestRequestTypeDef,
     SegmentTypeDef,
+    GetPlanResponseTypeDef,
+    GetRegistryResponseTypeDef,
+    GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef,
     GetResourcePoliciesRequestRequestTypeDef,
     GluePolicyTypeDef,
     GetResourcePolicyRequestRequestTypeDef,
+    GetResourcePolicyResponseTypeDef,
+    GetSchemaByDefinitionResponseTypeDef,
+    GetSchemaResponseTypeDef,
     SchemaVersionNumberTypeDef,
+    GetSchemaVersionResponseTypeDef,
+    GetSchemaVersionsDiffResponseTypeDef,
     GetSecurityConfigurationRequestRequestTypeDef,
+    GetSecurityConfigurationsRequestGetSecurityConfigurationsPaginateTypeDef,
     GetSecurityConfigurationsRequestRequestTypeDef,
     GetSessionRequestRequestTypeDef,
     GetStatementRequestRequestTypeDef,
     GetTableRequestRequestTypeDef,
     GetTableVersionRequestRequestTypeDef,
+    GetTableVersionsRequestGetTableVersionsPaginateTypeDef,
     GetTableVersionsRequestRequestTypeDef,
+    GetTablesRequestGetTablesPaginateTypeDef,
     GetTablesRequestRequestTypeDef,
     GetTagsRequestRequestTypeDef,
+    GetTagsResponseTypeDef,
     GetTriggerRequestRequestTypeDef,
+    GetTriggersRequestGetTriggersPaginateTypeDef,
     GetTriggersRequestRequestTypeDef,
     GetUserDefinedFunctionRequestRequestTypeDef,
+    GetUserDefinedFunctionsRequestGetUserDefinedFunctionsPaginateTypeDef,
     GetUserDefinedFunctionsRequestRequestTypeDef,
     GetWorkflowRequestRequestTypeDef,
     GetWorkflowRunPropertiesRequestRequestTypeDef,
+    GetWorkflowRunPropertiesResponseTypeDef,
     GetWorkflowRunRequestRequestTypeDef,
     GetWorkflowRunsRequestRequestTypeDef,
     GlueStudioSchemaColumnTypeDef,
     S3SourceAdditionalOptionsTypeDef,
     ImportCatalogToGlueRequestRequestTypeDef,
     ImportLabelsTaskRunPropertiesTypeDef,
     JDBCConnectorOptionsTypeDef,
     PredecessorTypeDef,
     JoinColumnTypeDef,
     KeySchemaElementTypeDef,
     LabelingSetGenerationTaskRunPropertiesTypeDef,
     ListBlueprintsRequestRequestTypeDef,
+    ListBlueprintsResponseTypeDef,
     ListCrawlersRequestRequestTypeDef,
+    ListCrawlersResponseTypeDef,
     ListCustomEntityTypesRequestRequestTypeDef,
     ListDevEndpointsRequestRequestTypeDef,
+    ListDevEndpointsResponseTypeDef,
     ListJobsRequestRequestTypeDef,
+    ListJobsResponseTypeDef,
+    ListMLTransformsResponseTypeDef,
+    ListRegistriesInputListRegistriesPaginateTypeDef,
     ListRegistriesInputRequestTypeDef,
     RegistryListItemTypeDef,
     SchemaVersionListItemTypeDef,
     SchemaListItemTypeDef,
     ListSessionsRequestRequestTypeDef,
     ListStatementsRequestRequestTypeDef,
     ListTriggersRequestRequestTypeDef,
+    ListTriggersResponseTypeDef,
     ListWorkflowsRequestRequestTypeDef,
+    ListWorkflowsResponseTypeDef,
     MLUserDataEncryptionTypeDef,
     MappingTypeDef,
     OtherMetadataValueListItemTypeDef,
     MetadataKeyValuePairTypeDef,
     OrderTypeDef,
+    PaginatorConfigTypeDef,
     PropertyPredicateTypeDef,
     PutResourcePolicyRequestRequestTypeDef,
+    PutResourcePolicyResponseTypeDef,
+    PutSchemaVersionMetadataResponseTypeDef,
     PutWorkflowRunPropertiesRequestRequestTypeDef,
     UpsertRedshiftTargetOptionsTypeDef,
+    RegisterSchemaVersionResponseTypeDef,
+    RemoveSchemaVersionMetadataResponseTypeDef,
     ResetJobBookmarkRequestRequestTypeDef,
     ResourceUriTypeDef,
+    ResponseMetadataTypeDef,
     ResumeWorkflowRunRequestRequestTypeDef,
+    ResumeWorkflowRunResponseTypeDef,
     RunStatementRequestRequestTypeDef,
+    RunStatementResponseTypeDef,
     S3DirectSourceAdditionalOptionsTypeDef,
     SortCriterionTypeDef,
     SerDeInfoTypeDef,
     SkewedInfoTypeDef,
     SqlAliasTypeDef,
     StartBlueprintRunRequestRequestTypeDef,
+    StartBlueprintRunResponseTypeDef,
     StartCrawlerRequestRequestTypeDef,
     StartCrawlerScheduleRequestRequestTypeDef,
+    StartDataQualityRuleRecommendationRunResponseTypeDef,
+    StartDataQualityRulesetEvaluationRunResponseTypeDef,
     StartExportLabelsTaskRunRequestRequestTypeDef,
+    StartExportLabelsTaskRunResponseTypeDef,
     StartImportLabelsTaskRunRequestRequestTypeDef,
+    StartImportLabelsTaskRunResponseTypeDef,
+    StartJobRunResponseTypeDef,
     StartMLEvaluationTaskRunRequestRequestTypeDef,
+    StartMLEvaluationTaskRunResponseTypeDef,
     StartMLLabelingSetGenerationTaskRunRequestRequestTypeDef,
+    StartMLLabelingSetGenerationTaskRunResponseTypeDef,
     StartTriggerRequestRequestTypeDef,
+    StartTriggerResponseTypeDef,
     StartWorkflowRunRequestRequestTypeDef,
+    StartWorkflowRunResponseTypeDef,
     StartingEventBatchConditionTypeDef,
     StatementOutputDataTypeDef,
     StopCrawlerRequestRequestTypeDef,
     StopCrawlerScheduleRequestRequestTypeDef,
     StopSessionRequestRequestTypeDef,
+    StopSessionResponseTypeDef,
     StopTriggerRequestRequestTypeDef,
+    StopTriggerResponseTypeDef,
     StopWorkflowRunRequestRequestTypeDef,
     TableIdentifierTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateBlueprintRequestRequestTypeDef,
+    UpdateBlueprintResponseTypeDef,
     UpdateCsvClassifierRequestTypeDef,
     UpdateGrokClassifierRequestTypeDef,
     UpdateJsonClassifierRequestTypeDef,
     UpdateXMLClassifierRequestTypeDef,
     UpdateCrawlerScheduleRequestRequestTypeDef,
     UpdateDataQualityRulesetRequestRequestTypeDef,
+    UpdateDataQualityRulesetResponseTypeDef,
     UpdateJobFromSourceControlRequestRequestTypeDef,
+    UpdateJobFromSourceControlResponseTypeDef,
+    UpdateJobResponseTypeDef,
+    UpdateMLTransformResponseTypeDef,
+    UpdateRegistryResponseTypeDef,
+    UpdateSchemaResponseTypeDef,
     UpdateSourceControlFromJobRequestRequestTypeDef,
+    UpdateSourceControlFromJobResponseTypeDef,
     UpdateWorkflowRequestRequestTypeDef,
+    UpdateWorkflowResponseTypeDef,
     WorkflowRunStatisticsTypeDef,
     ActionTypeDef,
     StartJobRunRequestRequestTypeDef,
     AggregateTypeDef,
+    AmazonRedshiftNodeDataTypeDef,
     GetUnfilteredPartitionMetadataRequestRequestTypeDef,
     GetUnfilteredTableMetadataRequestRequestTypeDef,
     BackfillErrorTypeDef,
     BatchDeletePartitionRequestRequestTypeDef,
     BatchGetPartitionRequestRequestTypeDef,
-    CancelMLTaskRunResponseTypeDef,
-    CheckSchemaVersionValidityResponseTypeDef,
-    CreateBlueprintResponseTypeDef,
-    CreateCustomEntityTypeResponseTypeDef,
-    CreateDataQualityRulesetResponseTypeDef,
-    CreateDevEndpointResponseTypeDef,
-    CreateJobResponseTypeDef,
-    CreateMLTransformResponseTypeDef,
-    CreateRegistryResponseTypeDef,
-    CreateSchemaResponseTypeDef,
-    CreateScriptResponseTypeDef,
-    CreateSecurityConfigurationResponseTypeDef,
-    CreateTriggerResponseTypeDef,
-    CreateWorkflowResponseTypeDef,
-    DeleteBlueprintResponseTypeDef,
-    DeleteCustomEntityTypeResponseTypeDef,
-    DeleteJobResponseTypeDef,
-    DeleteMLTransformResponseTypeDef,
-    DeleteRegistryResponseTypeDef,
-    DeleteSchemaResponseTypeDef,
-    DeleteSessionResponseTypeDef,
-    DeleteTriggerResponseTypeDef,
-    DeleteWorkflowResponseTypeDef,
-    GetCustomEntityTypeResponseTypeDef,
-    GetPlanResponseTypeDef,
-    GetRegistryResponseTypeDef,
-    GetResourcePolicyResponseTypeDef,
-    GetSchemaByDefinitionResponseTypeDef,
-    GetSchemaResponseTypeDef,
-    GetSchemaVersionResponseTypeDef,
-    GetSchemaVersionsDiffResponseTypeDef,
-    GetTagsResponseTypeDef,
-    GetWorkflowRunPropertiesResponseTypeDef,
-    ListBlueprintsResponseTypeDef,
-    ListCrawlersResponseTypeDef,
-    ListDevEndpointsResponseTypeDef,
-    ListJobsResponseTypeDef,
-    ListMLTransformsResponseTypeDef,
-    ListTriggersResponseTypeDef,
-    ListWorkflowsResponseTypeDef,
-    PutResourcePolicyResponseTypeDef,
-    PutSchemaVersionMetadataResponseTypeDef,
-    RegisterSchemaVersionResponseTypeDef,
-    RemoveSchemaVersionMetadataResponseTypeDef,
-    ResumeWorkflowRunResponseTypeDef,
-    RunStatementResponseTypeDef,
-    StartBlueprintRunResponseTypeDef,
-    StartDataQualityRuleRecommendationRunResponseTypeDef,
-    StartDataQualityRulesetEvaluationRunResponseTypeDef,
-    StartExportLabelsTaskRunResponseTypeDef,
-    StartImportLabelsTaskRunResponseTypeDef,
-    StartJobRunResponseTypeDef,
-    StartMLEvaluationTaskRunResponseTypeDef,
-    StartMLLabelingSetGenerationTaskRunResponseTypeDef,
-    StartTriggerResponseTypeDef,
-    StartWorkflowRunResponseTypeDef,
-    StopSessionResponseTypeDef,
-    StopTriggerResponseTypeDef,
-    UpdateBlueprintResponseTypeDef,
-    UpdateDataQualityRulesetResponseTypeDef,
-    UpdateJobFromSourceControlResponseTypeDef,
-    UpdateJobResponseTypeDef,
-    UpdateMLTransformResponseTypeDef,
-    UpdateRegistryResponseTypeDef,
-    UpdateSchemaResponseTypeDef,
-    UpdateSourceControlFromJobResponseTypeDef,
-    UpdateWorkflowResponseTypeDef,
     BatchDeleteConnectionResponseTypeDef,
     BatchStopJobRunErrorTypeDef,
     BatchUpdatePartitionFailureEntryTypeDef,
     ColumnErrorTypeDef,
     PartitionErrorTypeDef,
     TableErrorTypeDef,
     TableVersionErrorTypeDef,
@@ -848,57 +869,42 @@
     DataQualityRulesetListDetailsTypeDef,
     GetDataQualityRulesetResponseTypeDef,
     DataSourceTypeDef,
     CreatePartitionIndexRequestRequestTypeDef,
     CreateSchemaInputRequestTypeDef,
     DeleteRegistryInputRequestTypeDef,
     GetRegistryInputRequestTypeDef,
+    ListSchemasInputListSchemasPaginateTypeDef,
     ListSchemasInputRequestTypeDef,
     UpdateRegistryInputRequestTypeDef,
     CreateSessionRequestRequestTypeDef,
     SessionTypeDef,
+    EvaluateDataQualityMultiFrameTypeDef,
     EvaluateDataQualityTypeDef,
     DataCatalogEncryptionSettingsTypeDef,
     PrincipalPermissionsTypeDef,
     NullValueFieldTypeDef,
     DecimalColumnStatisticsDataTypeDef,
     DeleteSchemaInputRequestTypeDef,
     DeleteSchemaVersionsInputRequestTypeDef,
     GetSchemaByDefinitionInputRequestTypeDef,
     GetSchemaInputRequestTypeDef,
+    ListSchemaVersionsInputListSchemaVersionsPaginateTypeDef,
     ListSchemaVersionsInputRequestTypeDef,
     RegisterSchemaVersionInputRequestTypeDef,
     SchemaReferenceTypeDef,
     UpdateDevEndpointRequestRequestTypeDef,
     S3DeltaDirectTargetTypeDef,
     S3DirectTargetTypeDef,
     S3GlueParquetTargetTypeDef,
     S3HudiDirectTargetTypeDef,
-    DynamicTransformTypeDef,
     EncryptionConfigurationTypeDef,
     SchemaVersionErrorItemTypeDef,
     FilterExpressionTypeDef,
     TransformParametersTypeDef,
-    GetClassifiersRequestGetClassifiersPaginateTypeDef,
-    GetCrawlerMetricsRequestGetCrawlerMetricsPaginateTypeDef,
-    GetCrawlersRequestGetCrawlersPaginateTypeDef,
-    GetDatabasesRequestGetDatabasesPaginateTypeDef,
-    GetDevEndpointsRequestGetDevEndpointsPaginateTypeDef,
-    GetJobRunsRequestGetJobRunsPaginateTypeDef,
-    GetJobsRequestGetJobsPaginateTypeDef,
-    GetPartitionIndexesRequestGetPartitionIndexesPaginateTypeDef,
-    GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef,
-    GetSecurityConfigurationsRequestGetSecurityConfigurationsPaginateTypeDef,
-    GetTableVersionsRequestGetTableVersionsPaginateTypeDef,
-    GetTablesRequestGetTablesPaginateTypeDef,
-    GetTriggersRequestGetTriggersPaginateTypeDef,
-    GetUserDefinedFunctionsRequestGetUserDefinedFunctionsPaginateTypeDef,
-    ListRegistriesInputListRegistriesPaginateTypeDef,
-    ListSchemaVersionsInputListSchemaVersionsPaginateTypeDef,
-    ListSchemasInputListSchemasPaginateTypeDef,
     GetConnectionsRequestGetConnectionsPaginateTypeDef,
     GetConnectionsRequestRequestTypeDef,
     GetJobBookmarkResponseTypeDef,
     ResetJobBookmarkResponseTypeDef,
     GetMLTaskRunsRequestRequestTypeDef,
     TransformFilterCriteriaTypeDef,
     GetMappingResponseTypeDef,
@@ -925,14 +931,16 @@
     RemoveSchemaVersionMetadataInputRequestTypeDef,
     RedshiftTargetTypeDef,
     UserDefinedFunctionInputTypeDef,
     UserDefinedFunctionTypeDef,
     SearchTablesRequestRequestTypeDef,
     StatementOutputTypeDef,
     UpdateClassifierRequestRequestTypeDef,
+    AmazonRedshiftSourceTypeDef,
+    AmazonRedshiftTargetTypeDef,
     PartitionIndexDescriptorTypeDef,
     BatchStopJobRunResponseTypeDef,
     BatchUpdatePartitionResponseTypeDef,
     BatchCreatePartitionResponseTypeDef,
     BatchDeletePartitionResponseTypeDef,
     BatchDeleteTableResponseTypeDef,
     BatchDeleteTableVersionResponseTypeDef,
@@ -986,14 +994,15 @@
     UpdateMLTransformRequestRequestTypeDef,
     GetMLTransformsRequestRequestTypeDef,
     ListMLTransformsRequestRequestTypeDef,
     AthenaConnectorSourceTypeDef,
     CatalogDeltaSourceTypeDef,
     CatalogHudiSourceTypeDef,
     CustomCodeTypeDef,
+    DynamicTransformTypeDef,
     JDBCConnectorSourceTypeDef,
     JDBCConnectorTargetTypeDef,
     S3CatalogDeltaSourceTypeDef,
     S3CatalogHudiSourceTypeDef,
     S3CsvSourceTypeDef,
     S3DeltaSourceTypeDef,
     S3HudiSourceTypeDef,
@@ -1101,43 +1110,43 @@
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

### Comparing `types-aiobotocore-glue-2.5.0.post1/setup.py` & `types-aiobotocore-glue-2.5.1/setup.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-glue.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-glue",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_glue"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Glue 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.Glue 2.5.1 service generated with mypy-boto3-builder"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/",
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

### Comparing `types-aiobotocore-glue-2.5.0.post1/types_aiobotocore_glue/__init__.py` & `types-aiobotocore-glue-2.5.1/types_aiobotocore_glue/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-glue-2.5.0.post1/types_aiobotocore_glue/__init__.pyi` & `types-aiobotocore-glue-2.5.1/types_aiobotocore_glue/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-glue-2.5.0.post1/types_aiobotocore_glue/__main__.py` & `types-aiobotocore-glue-2.5.1/types_aiobotocore_glue/__main__.py`

 * *Files 5% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Glue 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Glue 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue//\nBoto3 docs:   "
         "   https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue\nOther"
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

### Comparing `types-aiobotocore-glue-2.5.0.post1/types_aiobotocore_glue/client.py` & `types-aiobotocore-glue-2.5.1/types_aiobotocore_glue/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -307,14 +307,17 @@
     ConcurrentRunsExceededException: Type[BotocoreClientError]
     ConditionCheckFailureException: Type[BotocoreClientError]
     ConflictException: Type[BotocoreClientError]
     CrawlerNotRunningException: Type[BotocoreClientError]
     CrawlerRunningException: Type[BotocoreClientError]
     CrawlerStoppingException: Type[BotocoreClientError]
     EntityNotFoundException: Type[BotocoreClientError]
+    FederatedResourceAlreadyExistsException: Type[BotocoreClientError]
+    FederationSourceException: Type[BotocoreClientError]
+    FederationSourceRetryableException: Type[BotocoreClientError]
     GlueEncryptionException: Type[BotocoreClientError]
     IdempotentParameterMismatchException: Type[BotocoreClientError]
     IllegalBlueprintStateException: Type[BotocoreClientError]
     IllegalSessionStateException: Type[BotocoreClientError]
     IllegalWorkflowStateException: Type[BotocoreClientError]
     InternalServiceException: Type[BotocoreClientError]
     InvalidInputException: Type[BotocoreClientError]
@@ -667,15 +670,20 @@
         schedule.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.create_crawler)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/client/#create_crawler)
         """
 
     async def create_custom_entity_type(
-        self, *, Name: str, RegexString: str, ContextWords: Sequence[str] = ...
+        self,
+        *,
+        Name: str,
+        RegexString: str,
+        ContextWords: Sequence[str] = ...,
+        Tags: Mapping[str, str] = ...
     ) -> CreateCustomEntityTypeResponseTypeDef:
         """
         Creates a custom pattern that is used to detect sensitive data across the
         columns and rows of your structured data.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.create_custom_entity_type)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/client/#create_custom_entity_type)
@@ -1022,15 +1030,15 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.delete_connection)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/client/#delete_connection)
         """
 
     async def delete_crawler(self, *, Name: str) -> Dict[str, Any]:
         """
         Removes a specified crawler from the Glue Data Catalog, unless the crawler state
-        is `RUNNING` .
+        is `RUNNING`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.delete_crawler)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/client/#delete_crawler)
         """
 
     async def delete_custom_entity_type(
         self, *, Name: str
@@ -1810,15 +1818,15 @@
         Expression: str = ...,
         NextToken: str = ...,
         MaxResults: int = ...,
         TransactionId: str = ...,
         QueryAsOfTime: Union[datetime, str] = ...
     ) -> GetTablesResponseTypeDef:
         """
-        Retrieves the definitions of some or all of the tables in a given `Database` .
+        Retrieves the definitions of some or all of the tables in a given `Database`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_tables)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/client/#get_tables)
         """
 
     async def get_tags(self, *, ResourceArn: str) -> GetTagsResponseTypeDef:
         """
@@ -2009,15 +2017,15 @@
         Returns all the crawls of a specified crawler.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.list_crawls)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/client/#list_crawls)
         """
 
     async def list_custom_entity_types(
-        self, *, NextToken: str = ..., MaxResults: int = ...
+        self, *, NextToken: str = ..., MaxResults: int = ..., Tags: Mapping[str, str] = ...
     ) -> ListCustomEntityTypesResponseTypeDef:
         """
         Lists all the custom patterns that have been created.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.list_custom_entity_types)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/client/#list_custom_entity_types)
         """
@@ -2366,16 +2374,16 @@
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.start_crawler)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/client/#start_crawler)
         """
 
     async def start_crawler_schedule(self, *, CrawlerName: str) -> Dict[str, Any]:
         """
-        Changes the schedule state of the specified crawler to `SCHEDULED` , unless the
-        crawler is already running or the schedule state is already `SCHEDULED` .
+        Changes the schedule state of the specified crawler to `SCHEDULED`, unless the
+        crawler is already running or the schedule state is already `SCHEDULED`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.start_crawler_schedule)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/client/#start_crawler_schedule)
         """
 
     async def start_data_quality_rule_recommendation_run(
         self,
@@ -2400,15 +2408,16 @@
         *,
         DataSource: DataSourceTypeDef,
         Role: str,
         RulesetNames: Sequence[str],
         NumberOfWorkers: int = ...,
         Timeout: int = ...,
         ClientToken: str = ...,
-        AdditionalRunOptions: DataQualityEvaluationRunAdditionalRunOptionsTypeDef = ...
+        AdditionalRunOptions: DataQualityEvaluationRunAdditionalRunOptionsTypeDef = ...,
+        AdditionalDataSources: Mapping[str, DataSourceTypeDef] = ...
     ) -> StartDataQualityRulesetEvaluationRunResponseTypeDef:
         """
         Once you have a ruleset definition (either recommended or your own), you call
         this operation to evaluate the ruleset against a data source (Glue table).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.start_data_quality_ruleset_evaluation_run)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/client/#start_data_quality_ruleset_evaluation_run)
@@ -2503,15 +2512,15 @@
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.stop_crawler)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/client/#stop_crawler)
         """
 
     async def stop_crawler_schedule(self, *, CrawlerName: str) -> Dict[str, Any]:
         """
-        Sets the schedule state of the specified crawler to `NOT_SCHEDULED` , but does
+        Sets the schedule state of the specified crawler to `NOT_SCHEDULED`, but does
         not stop the crawler if it is already running.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.stop_crawler_schedule)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/client/#stop_crawler_schedule)
         """
 
     async def stop_session(
@@ -2575,16 +2584,16 @@
         *,
         GrokClassifier: UpdateGrokClassifierRequestTypeDef = ...,
         XMLClassifier: UpdateXMLClassifierRequestTypeDef = ...,
         JsonClassifier: UpdateJsonClassifierRequestTypeDef = ...,
         CsvClassifier: UpdateCsvClassifierRequestTypeDef = ...
     ) -> Dict[str, Any]:
         """
-        Modifies an existing classifier (a `GrokClassifier` , an `XMLClassifier` , a
-        `JsonClassifier` , or a `CsvClassifier` , depending on which field is present).
+        Modifies an existing classifier (a `GrokClassifier`, an `XMLClassifier`, a
+        `JsonClassifier`, or a `CsvClassifier`, depending on which field is present).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.update_classifier)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/client/#update_classifier)
         """
 
     async def update_column_statistics_for_partition(
         self,
@@ -2659,15 +2668,15 @@
         Updates the schedule of a crawler using a `cron` expression.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.update_crawler_schedule)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/client/#update_crawler_schedule)
         """
 
     async def update_data_quality_ruleset(
-        self, *, Name: str, UpdatedName: str = ..., Description: str = ..., Ruleset: str = ...
+        self, *, Name: str, Description: str = ..., Ruleset: str = ...
     ) -> UpdateDataQualityRulesetResponseTypeDef:
         """
         Updates the specified data quality ruleset.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.update_data_quality_ruleset)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/client/#update_data_quality_ruleset)
         """
```

### Comparing `types-aiobotocore-glue-2.5.0.post1/types_aiobotocore_glue/client.pyi` & `types-aiobotocore-glue-2.5.1/types_aiobotocore_glue/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -304,14 +304,17 @@
     ConcurrentRunsExceededException: Type[BotocoreClientError]
     ConditionCheckFailureException: Type[BotocoreClientError]
     ConflictException: Type[BotocoreClientError]
     CrawlerNotRunningException: Type[BotocoreClientError]
     CrawlerRunningException: Type[BotocoreClientError]
     CrawlerStoppingException: Type[BotocoreClientError]
     EntityNotFoundException: Type[BotocoreClientError]
+    FederatedResourceAlreadyExistsException: Type[BotocoreClientError]
+    FederationSourceException: Type[BotocoreClientError]
+    FederationSourceRetryableException: Type[BotocoreClientError]
     GlueEncryptionException: Type[BotocoreClientError]
     IdempotentParameterMismatchException: Type[BotocoreClientError]
     IllegalBlueprintStateException: Type[BotocoreClientError]
     IllegalSessionStateException: Type[BotocoreClientError]
     IllegalWorkflowStateException: Type[BotocoreClientError]
     InternalServiceException: Type[BotocoreClientError]
     InvalidInputException: Type[BotocoreClientError]
@@ -635,15 +638,20 @@
         Creates a new crawler with specified targets, role, configuration, and optional
         schedule.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.create_crawler)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/client/#create_crawler)
         """
     async def create_custom_entity_type(
-        self, *, Name: str, RegexString: str, ContextWords: Sequence[str] = ...
+        self,
+        *,
+        Name: str,
+        RegexString: str,
+        ContextWords: Sequence[str] = ...,
+        Tags: Mapping[str, str] = ...
     ) -> CreateCustomEntityTypeResponseTypeDef:
         """
         Creates a custom pattern that is used to detect sensitive data across the
         columns and rows of your structured data.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.create_custom_entity_type)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/client/#create_custom_entity_type)
@@ -968,15 +976,15 @@
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.delete_connection)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/client/#delete_connection)
         """
     async def delete_crawler(self, *, Name: str) -> Dict[str, Any]:
         """
         Removes a specified crawler from the Glue Data Catalog, unless the crawler state
-        is `RUNNING` .
+        is `RUNNING`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.delete_crawler)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/client/#delete_crawler)
         """
     async def delete_custom_entity_type(
         self, *, Name: str
     ) -> DeleteCustomEntityTypeResponseTypeDef:
@@ -1683,15 +1691,15 @@
         Expression: str = ...,
         NextToken: str = ...,
         MaxResults: int = ...,
         TransactionId: str = ...,
         QueryAsOfTime: Union[datetime, str] = ...
     ) -> GetTablesResponseTypeDef:
         """
-        Retrieves the definitions of some or all of the tables in a given `Database` .
+        Retrieves the definitions of some or all of the tables in a given `Database`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.get_tables)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/client/#get_tables)
         """
     async def get_tags(self, *, ResourceArn: str) -> GetTagsResponseTypeDef:
         """
         Retrieves a list of tags associated with a resource.
@@ -1865,15 +1873,15 @@
         """
         Returns all the crawls of a specified crawler.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.list_crawls)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/client/#list_crawls)
         """
     async def list_custom_entity_types(
-        self, *, NextToken: str = ..., MaxResults: int = ...
+        self, *, NextToken: str = ..., MaxResults: int = ..., Tags: Mapping[str, str] = ...
     ) -> ListCustomEntityTypesResponseTypeDef:
         """
         Lists all the custom patterns that have been created.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.list_custom_entity_types)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/client/#list_custom_entity_types)
         """
@@ -2194,16 +2202,16 @@
         Starts a crawl using the specified crawler, regardless of what is scheduled.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.start_crawler)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/client/#start_crawler)
         """
     async def start_crawler_schedule(self, *, CrawlerName: str) -> Dict[str, Any]:
         """
-        Changes the schedule state of the specified crawler to `SCHEDULED` , unless the
-        crawler is already running or the schedule state is already `SCHEDULED` .
+        Changes the schedule state of the specified crawler to `SCHEDULED`, unless the
+        crawler is already running or the schedule state is already `SCHEDULED`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.start_crawler_schedule)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/client/#start_crawler_schedule)
         """
     async def start_data_quality_rule_recommendation_run(
         self,
         *,
@@ -2226,15 +2234,16 @@
         *,
         DataSource: DataSourceTypeDef,
         Role: str,
         RulesetNames: Sequence[str],
         NumberOfWorkers: int = ...,
         Timeout: int = ...,
         ClientToken: str = ...,
-        AdditionalRunOptions: DataQualityEvaluationRunAdditionalRunOptionsTypeDef = ...
+        AdditionalRunOptions: DataQualityEvaluationRunAdditionalRunOptionsTypeDef = ...,
+        AdditionalDataSources: Mapping[str, DataSourceTypeDef] = ...
     ) -> StartDataQualityRulesetEvaluationRunResponseTypeDef:
         """
         Once you have a ruleset definition (either recommended or your own), you call
         this operation to evaluate the ruleset against a data source (Glue table).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.start_data_quality_ruleset_evaluation_run)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/client/#start_data_quality_ruleset_evaluation_run)
@@ -2320,15 +2329,15 @@
         If the specified crawler is running, stops the crawl.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.stop_crawler)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/client/#stop_crawler)
         """
     async def stop_crawler_schedule(self, *, CrawlerName: str) -> Dict[str, Any]:
         """
-        Sets the schedule state of the specified crawler to `NOT_SCHEDULED` , but does
+        Sets the schedule state of the specified crawler to `NOT_SCHEDULED`, but does
         not stop the crawler if it is already running.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.stop_crawler_schedule)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/client/#stop_crawler_schedule)
         """
     async def stop_session(
         self, *, Id: str, RequestOrigin: str = ...
@@ -2385,16 +2394,16 @@
         *,
         GrokClassifier: UpdateGrokClassifierRequestTypeDef = ...,
         XMLClassifier: UpdateXMLClassifierRequestTypeDef = ...,
         JsonClassifier: UpdateJsonClassifierRequestTypeDef = ...,
         CsvClassifier: UpdateCsvClassifierRequestTypeDef = ...
     ) -> Dict[str, Any]:
         """
-        Modifies an existing classifier (a `GrokClassifier` , an `XMLClassifier` , a
-        `JsonClassifier` , or a `CsvClassifier` , depending on which field is present).
+        Modifies an existing classifier (a `GrokClassifier`, an `XMLClassifier`, a
+        `JsonClassifier`, or a `CsvClassifier`, depending on which field is present).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.update_classifier)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/client/#update_classifier)
         """
     async def update_column_statistics_for_partition(
         self,
         *,
@@ -2463,15 +2472,15 @@
         """
         Updates the schedule of a crawler using a `cron` expression.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.update_crawler_schedule)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/client/#update_crawler_schedule)
         """
     async def update_data_quality_ruleset(
-        self, *, Name: str, UpdatedName: str = ..., Description: str = ..., Ruleset: str = ...
+        self, *, Name: str, Description: str = ..., Ruleset: str = ...
     ) -> UpdateDataQualityRulesetResponseTypeDef:
         """
         Updates the specified data quality ruleset.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Client.update_data_quality_ruleset)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/client/#update_data_quality_ruleset)
         """
```

### Comparing `types-aiobotocore-glue-2.5.0.post1/types_aiobotocore_glue/literals.py` & `types-aiobotocore-glue-2.5.1/types_aiobotocore_glue/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -2,28 +2,29 @@
 Type annotations for glue service literal definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/literals/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_glue.literals import AggFunctionType
+    from types_aiobotocore_glue.literals import AdditionalOptionKeysType
 
-    data: AggFunctionType = "avg"
+    data: AdditionalOptionKeysType = "performanceTuning.caching"
     ```
 """
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 
 __all__ = (
+    "AdditionalOptionKeysType",
     "AggFunctionType",
     "BackfillErrorCodeType",
     "BlueprintRunStateType",
     "BlueprintStatusType",
     "CatalogEncryptionModeType",
     "CloudWatchEncryptionModeType",
     "ColumnStatisticsTypeType",
@@ -127,14 +128,15 @@
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
 
+AdditionalOptionKeysType = Literal["performanceTuning.caching"]
 AggFunctionType = Literal[
     "avg",
     "count",
     "countDistinct",
     "first",
     "kurtosis",
     "last",
@@ -322,28 +324,28 @@
 ]
 PermissionTypeType = Literal["CELL_FILTER_PERMISSION", "COLUMN_PERMISSION"]
 PiiTypeType = Literal["ColumnAudit", "ColumnMasking", "RowAudit", "RowMasking"]
 PrincipalTypeType = Literal["GROUP", "ROLE", "USER"]
 QuoteCharType = Literal["disabled", "quillemet", "quote", "single_quote"]
 RecrawlBehaviorType = Literal["CRAWL_EVENT_MODE", "CRAWL_EVERYTHING", "CRAWL_NEW_FOLDERS_ONLY"]
 RegistryStatusType = Literal["AVAILABLE", "DELETING"]
-ResourceShareTypeType = Literal["ALL", "FOREIGN"]
+ResourceShareTypeType = Literal["ALL", "FEDERATED", "FOREIGN"]
 ResourceTypeType = Literal["ARCHIVE", "FILE", "JAR"]
 S3EncryptionModeType = Literal["DISABLED", "SSE-KMS", "SSE-S3"]
 ScheduleStateType = Literal["NOT_SCHEDULED", "SCHEDULED", "TRANSITIONING"]
 SchemaDiffTypeType = Literal["SYNTAX_DIFF"]
 SchemaStatusType = Literal["AVAILABLE", "DELETING", "PENDING"]
 SchemaVersionStatusType = Literal["AVAILABLE", "DELETING", "FAILURE", "PENDING"]
 SeparatorType = Literal["comma", "ctrla", "pipe", "semicolon", "tab"]
 SessionStatusType = Literal["FAILED", "PROVISIONING", "READY", "STOPPED", "STOPPING", "TIMEOUT"]
 SortDirectionTypeType = Literal["ASCENDING", "DESCENDING"]
 SortType = Literal["ASC", "DESC"]
 SourceControlAuthStrategyType = Literal["AWS_SECRETS_MANAGER", "PERSONAL_ACCESS_TOKEN"]
 SourceControlProviderType = Literal["AWS_CODE_COMMIT", "GITHUB"]
-StartingPositionType = Literal["earliest", "latest", "trim_horizon"]
+StartingPositionType = Literal["earliest", "latest", "timestamp", "trim_horizon"]
 StatementStateType = Literal["AVAILABLE", "CANCELLED", "CANCELLING", "ERROR", "RUNNING", "WAITING"]
 TargetFormatType = Literal["avro", "csv", "delta", "hudi", "json", "orc", "parquet"]
 TaskRunSortColumnTypeType = Literal["STARTED", "STATUS", "TASK_RUN_TYPE"]
 TaskStatusTypeType = Literal[
     "FAILED", "RUNNING", "STARTING", "STOPPED", "STOPPING", "SUCCEEDED", "TIMEOUT"
 ]
 TaskTypeType = Literal[
@@ -364,15 +366,15 @@
     "DELETING",
     "UPDATING",
 ]
 TriggerTypeType = Literal["CONDITIONAL", "EVENT", "ON_DEMAND", "SCHEDULED"]
 UnionTypeType = Literal["ALL", "DISTINCT"]
 UpdateBehaviorType = Literal["LOG", "UPDATE_IN_DATABASE"]
 UpdateCatalogBehaviorType = Literal["LOG", "UPDATE_IN_DATABASE"]
-WorkerTypeType = Literal["G.025X", "G.1X", "G.2X", "Standard"]
+WorkerTypeType = Literal["G.025X", "G.1X", "G.2X", "G.4X", "G.8X", "Standard", "Z.2X"]
 WorkflowRunStatusType = Literal["COMPLETED", "ERROR", "RUNNING", "STOPPED", "STOPPING"]
 GlueServiceName = Literal["glue"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
@@ -429,14 +431,15 @@
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
@@ -515,14 +518,15 @@
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
@@ -533,14 +537,15 @@
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
@@ -576,14 +581,15 @@
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
@@ -602,16 +608,19 @@
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
@@ -695,15 +704,17 @@
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
@@ -754,16 +765,18 @@
     "ap-northeast-3",
     "ap-south-1",
     "ap-southeast-1",
     "ap-southeast-2",
     "ap-southeast-3",
     "ca-central-1",
     "eu-central-1",
+    "eu-central-2",
     "eu-north-1",
     "eu-south-1",
+    "eu-south-2",
     "eu-west-1",
     "eu-west-2",
     "eu-west-3",
     "me-central-1",
     "me-south-1",
     "sa-east-1",
     "us-east-1",
```

### Comparing `types-aiobotocore-glue-2.5.0.post1/types_aiobotocore_glue/literals.pyi` & `types-aiobotocore-glue-2.5.1/types_aiobotocore_glue/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -2,27 +2,28 @@
 Type annotations for glue service literal definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/literals/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_glue.literals import AggFunctionType
+    from types_aiobotocore_glue.literals import AdditionalOptionKeysType
 
-    data: AggFunctionType = "avg"
+    data: AdditionalOptionKeysType = "performanceTuning.caching"
     ```
 """
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 __all__ = (
+    "AdditionalOptionKeysType",
     "AggFunctionType",
     "BackfillErrorCodeType",
     "BlueprintRunStateType",
     "BlueprintStatusType",
     "CatalogEncryptionModeType",
     "CloudWatchEncryptionModeType",
     "ColumnStatisticsTypeType",
@@ -125,14 +126,15 @@
     "GlueServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
+AdditionalOptionKeysType = Literal["performanceTuning.caching"]
 AggFunctionType = Literal[
     "avg",
     "count",
     "countDistinct",
     "first",
     "kurtosis",
     "last",
@@ -320,28 +322,28 @@
 ]
 PermissionTypeType = Literal["CELL_FILTER_PERMISSION", "COLUMN_PERMISSION"]
 PiiTypeType = Literal["ColumnAudit", "ColumnMasking", "RowAudit", "RowMasking"]
 PrincipalTypeType = Literal["GROUP", "ROLE", "USER"]
 QuoteCharType = Literal["disabled", "quillemet", "quote", "single_quote"]
 RecrawlBehaviorType = Literal["CRAWL_EVENT_MODE", "CRAWL_EVERYTHING", "CRAWL_NEW_FOLDERS_ONLY"]
 RegistryStatusType = Literal["AVAILABLE", "DELETING"]
-ResourceShareTypeType = Literal["ALL", "FOREIGN"]
+ResourceShareTypeType = Literal["ALL", "FEDERATED", "FOREIGN"]
 ResourceTypeType = Literal["ARCHIVE", "FILE", "JAR"]
 S3EncryptionModeType = Literal["DISABLED", "SSE-KMS", "SSE-S3"]
 ScheduleStateType = Literal["NOT_SCHEDULED", "SCHEDULED", "TRANSITIONING"]
 SchemaDiffTypeType = Literal["SYNTAX_DIFF"]
 SchemaStatusType = Literal["AVAILABLE", "DELETING", "PENDING"]
 SchemaVersionStatusType = Literal["AVAILABLE", "DELETING", "FAILURE", "PENDING"]
 SeparatorType = Literal["comma", "ctrla", "pipe", "semicolon", "tab"]
 SessionStatusType = Literal["FAILED", "PROVISIONING", "READY", "STOPPED", "STOPPING", "TIMEOUT"]
 SortDirectionTypeType = Literal["ASCENDING", "DESCENDING"]
 SortType = Literal["ASC", "DESC"]
 SourceControlAuthStrategyType = Literal["AWS_SECRETS_MANAGER", "PERSONAL_ACCESS_TOKEN"]
 SourceControlProviderType = Literal["AWS_CODE_COMMIT", "GITHUB"]
-StartingPositionType = Literal["earliest", "latest", "trim_horizon"]
+StartingPositionType = Literal["earliest", "latest", "timestamp", "trim_horizon"]
 StatementStateType = Literal["AVAILABLE", "CANCELLED", "CANCELLING", "ERROR", "RUNNING", "WAITING"]
 TargetFormatType = Literal["avro", "csv", "delta", "hudi", "json", "orc", "parquet"]
 TaskRunSortColumnTypeType = Literal["STARTED", "STATUS", "TASK_RUN_TYPE"]
 TaskStatusTypeType = Literal[
     "FAILED", "RUNNING", "STARTING", "STOPPED", "STOPPING", "SUCCEEDED", "TIMEOUT"
 ]
 TaskTypeType = Literal[
@@ -362,15 +364,15 @@
     "DELETING",
     "UPDATING",
 ]
 TriggerTypeType = Literal["CONDITIONAL", "EVENT", "ON_DEMAND", "SCHEDULED"]
 UnionTypeType = Literal["ALL", "DISTINCT"]
 UpdateBehaviorType = Literal["LOG", "UPDATE_IN_DATABASE"]
 UpdateCatalogBehaviorType = Literal["LOG", "UPDATE_IN_DATABASE"]
-WorkerTypeType = Literal["G.025X", "G.1X", "G.2X", "Standard"]
+WorkerTypeType = Literal["G.025X", "G.1X", "G.2X", "G.4X", "G.8X", "Standard", "Z.2X"]
 WorkflowRunStatusType = Literal["COMPLETED", "ERROR", "RUNNING", "STOPPED", "STOPPING"]
 GlueServiceName = Literal["glue"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
@@ -427,14 +429,15 @@
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
@@ -513,14 +516,15 @@
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
@@ -531,14 +535,15 @@
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
@@ -574,14 +579,15 @@
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
@@ -600,16 +606,19 @@
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
@@ -693,15 +702,17 @@
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
@@ -752,16 +763,18 @@
     "ap-northeast-3",
     "ap-south-1",
     "ap-southeast-1",
     "ap-southeast-2",
     "ap-southeast-3",
     "ca-central-1",
     "eu-central-1",
+    "eu-central-2",
     "eu-north-1",
     "eu-south-1",
+    "eu-south-2",
     "eu-west-1",
     "eu-west-2",
     "eu-west-3",
     "me-central-1",
     "me-south-1",
     "sa-east-1",
     "us-east-1",
```

### Comparing `types-aiobotocore-glue-2.5.0.post1/types_aiobotocore_glue/paginator.py` & `types-aiobotocore-glue-2.5.1/types_aiobotocore_glue/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -52,17 +52,16 @@
         get_triggers_paginator: GetTriggersPaginator = client.get_paginator("get_triggers")
         get_user_defined_functions_paginator: GetUserDefinedFunctionsPaginator = client.get_paginator("get_user_defined_functions")
         list_registries_paginator: ListRegistriesPaginator = client.get_paginator("list_registries")
         list_schema_versions_paginator: ListSchemaVersionsPaginator = client.get_paginator("list_schema_versions")
         list_schemas_paginator: ListSchemasPaginator = client.get_paginator("list_schemas")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, Sequence, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ResourceShareTypeType
 from .type_defs import (
     GetClassifiersResponseTypeDef,
@@ -87,20 +86,14 @@
     ListSchemaVersionsResponseTypeDef,
     PaginatorConfigTypeDef,
     RegistryIdTypeDef,
     SchemaIdTypeDef,
     SegmentTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "GetClassifiersPaginator",
     "GetConnectionsPaginator",
     "GetCrawlerMetricsPaginator",
     "GetCrawlersPaginator",
     "GetDatabasesPaginator",
     "GetDevEndpointsPaginator",
@@ -115,177 +108,165 @@
     "GetTriggersPaginator",
     "GetUserDefinedFunctionsPaginator",
     "ListRegistriesPaginator",
     "ListSchemaVersionsPaginator",
     "ListSchemasPaginator",
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
 class GetClassifiersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetClassifiers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getclassifierspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetClassifiersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetClassifiers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getclassifierspaginator)
         """
 
-
 class GetConnectionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetConnections)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getconnectionspaginator)
     """
 
     def paginate(
         self,
         *,
         CatalogId: str = ...,
         Filter: GetConnectionsFilterTypeDef = ...,
         HidePassword: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetConnectionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetConnections.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getconnectionspaginator)
         """
 
-
 class GetCrawlerMetricsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetCrawlerMetrics)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getcrawlermetricspaginator)
     """
 
     def paginate(
         self,
         *,
         CrawlerNameList: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetCrawlerMetricsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetCrawlerMetrics.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getcrawlermetricspaginator)
         """
 
-
 class GetCrawlersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetCrawlers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getcrawlerspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetCrawlersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetCrawlers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getcrawlerspaginator)
         """
 
-
 class GetDatabasesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetDatabases)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getdatabasespaginator)
     """
 
     def paginate(
         self,
         *,
         CatalogId: str = ...,
         ResourceShareType: ResourceShareTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetDatabasesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetDatabases.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getdatabasespaginator)
         """
 
-
 class GetDevEndpointsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetDevEndpoints)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getdevendpointspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetDevEndpointsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetDevEndpoints.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getdevendpointspaginator)
         """
 
-
 class GetJobRunsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetJobRuns)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getjobrunspaginator)
     """
 
     def paginate(
-        self, *, JobName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, JobName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetJobRunsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetJobRuns.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getjobrunspaginator)
         """
 
-
 class GetJobsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getjobspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getjobspaginator)
         """
 
-
 class GetPartitionIndexesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetPartitionIndexes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getpartitionindexespaginator)
     """
 
     def paginate(
         self,
         *,
         DatabaseName: str,
         TableName: str,
         CatalogId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetPartitionIndexesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetPartitionIndexes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getpartitionindexespaginator)
         """
 
-
 class GetPartitionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetPartitions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getpartitionspaginator)
     """
 
     def paginate(
@@ -295,165 +276,159 @@
         TableName: str,
         CatalogId: str = ...,
         Expression: str = ...,
         Segment: SegmentTypeDef = ...,
         ExcludeColumnSchema: bool = ...,
         TransactionId: str = ...,
         QueryAsOfTime: Union[datetime, str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetPartitionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetPartitions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getpartitionspaginator)
         """
 
-
 class GetResourcePoliciesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetResourcePolicies)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getresourcepoliciespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetResourcePoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetResourcePolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getresourcepoliciespaginator)
         """
 
-
 class GetSecurityConfigurationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetSecurityConfigurations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getsecurityconfigurationspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetSecurityConfigurationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetSecurityConfigurations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getsecurityconfigurationspaginator)
         """
 
-
 class GetTableVersionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetTableVersions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#gettableversionspaginator)
     """
 
     def paginate(
         self,
         *,
         DatabaseName: str,
         TableName: str,
         CatalogId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetTableVersionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetTableVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#gettableversionspaginator)
         """
 
-
 class GetTablesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetTables)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#gettablespaginator)
     """
 
     def paginate(
         self,
         *,
         DatabaseName: str,
         CatalogId: str = ...,
         Expression: str = ...,
         TransactionId: str = ...,
         QueryAsOfTime: Union[datetime, str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetTablesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetTables.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#gettablespaginator)
         """
 
-
 class GetTriggersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetTriggers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#gettriggerspaginator)
     """
 
     def paginate(
-        self, *, DependentJobName: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, DependentJobName: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetTriggersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetTriggers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#gettriggerspaginator)
         """
 
-
 class GetUserDefinedFunctionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetUserDefinedFunctions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getuserdefinedfunctionspaginator)
     """
 
     def paginate(
         self,
         *,
         Pattern: str,
         CatalogId: str = ...,
         DatabaseName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetUserDefinedFunctionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetUserDefinedFunctions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getuserdefinedfunctionspaginator)
         """
 
-
 class ListRegistriesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.ListRegistries)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#listregistriespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRegistriesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.ListRegistries.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#listregistriespaginator)
         """
 
-
 class ListSchemaVersionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.ListSchemaVersions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#listschemaversionspaginator)
     """
 
     def paginate(
-        self, *, SchemaId: SchemaIdTypeDef, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, SchemaId: SchemaIdTypeDef, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSchemaVersionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.ListSchemaVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#listschemaversionspaginator)
         """
 
-
 class ListSchemasPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.ListSchemas)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#listschemaspaginator)
     """
 
     def paginate(
-        self, *, RegistryId: RegistryIdTypeDef = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        RegistryId: RegistryIdTypeDef = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSchemasResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.ListSchemas.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#listschemaspaginator)
         """
```

### Comparing `types-aiobotocore-glue-2.5.0.post1/types_aiobotocore_glue/paginator.pyi` & `types-aiobotocore-glue-2.5.1/types_aiobotocore_glue/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -52,17 +52,16 @@
         get_triggers_paginator: GetTriggersPaginator = client.get_paginator("get_triggers")
         get_user_defined_functions_paginator: GetUserDefinedFunctionsPaginator = client.get_paginator("get_user_defined_functions")
         list_registries_paginator: ListRegistriesPaginator = client.get_paginator("list_registries")
         list_schema_versions_paginator: ListSchemaVersionsPaginator = client.get_paginator("list_schema_versions")
         list_schemas_paginator: ListSchemasPaginator = client.get_paginator("list_schemas")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, Sequence, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ResourceShareTypeType
 from .type_defs import (
     GetClassifiersResponseTypeDef,
@@ -87,19 +86,14 @@
     ListSchemaVersionsResponseTypeDef,
     PaginatorConfigTypeDef,
     RegistryIdTypeDef,
     SchemaIdTypeDef,
     SegmentTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "GetClassifiersPaginator",
     "GetConnectionsPaginator",
     "GetCrawlerMetricsPaginator",
     "GetCrawlersPaginator",
     "GetDatabasesPaginator",
     "GetDevEndpointsPaginator",
@@ -114,165 +108,177 @@
     "GetTriggersPaginator",
     "GetUserDefinedFunctionsPaginator",
     "ListRegistriesPaginator",
     "ListSchemaVersionsPaginator",
     "ListSchemasPaginator",
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
 class GetClassifiersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetClassifiers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getclassifierspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetClassifiersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetClassifiers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getclassifierspaginator)
         """
 
+
 class GetConnectionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetConnections)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getconnectionspaginator)
     """
 
     def paginate(
         self,
         *,
         CatalogId: str = ...,
         Filter: GetConnectionsFilterTypeDef = ...,
         HidePassword: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetConnectionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetConnections.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getconnectionspaginator)
         """
 
+
 class GetCrawlerMetricsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetCrawlerMetrics)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getcrawlermetricspaginator)
     """
 
     def paginate(
         self,
         *,
         CrawlerNameList: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetCrawlerMetricsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetCrawlerMetrics.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getcrawlermetricspaginator)
         """
 
+
 class GetCrawlersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetCrawlers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getcrawlerspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetCrawlersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetCrawlers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getcrawlerspaginator)
         """
 
+
 class GetDatabasesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetDatabases)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getdatabasespaginator)
     """
 
     def paginate(
         self,
         *,
         CatalogId: str = ...,
         ResourceShareType: ResourceShareTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetDatabasesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetDatabases.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getdatabasespaginator)
         """
 
+
 class GetDevEndpointsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetDevEndpoints)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getdevendpointspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetDevEndpointsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetDevEndpoints.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getdevendpointspaginator)
         """
 
+
 class GetJobRunsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetJobRuns)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getjobrunspaginator)
     """
 
     def paginate(
-        self, *, JobName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, JobName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetJobRunsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetJobRuns.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getjobrunspaginator)
         """
 
+
 class GetJobsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getjobspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getjobspaginator)
         """
 
+
 class GetPartitionIndexesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetPartitionIndexes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getpartitionindexespaginator)
     """
 
     def paginate(
         self,
         *,
         DatabaseName: str,
         TableName: str,
         CatalogId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetPartitionIndexesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetPartitionIndexes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getpartitionindexespaginator)
         """
 
+
 class GetPartitionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetPartitions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getpartitionspaginator)
     """
 
     def paginate(
@@ -282,156 +288,168 @@
         TableName: str,
         CatalogId: str = ...,
         Expression: str = ...,
         Segment: SegmentTypeDef = ...,
         ExcludeColumnSchema: bool = ...,
         TransactionId: str = ...,
         QueryAsOfTime: Union[datetime, str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetPartitionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetPartitions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getpartitionspaginator)
         """
 
+
 class GetResourcePoliciesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetResourcePolicies)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getresourcepoliciespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetResourcePoliciesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetResourcePolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getresourcepoliciespaginator)
         """
 
+
 class GetSecurityConfigurationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetSecurityConfigurations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getsecurityconfigurationspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetSecurityConfigurationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetSecurityConfigurations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getsecurityconfigurationspaginator)
         """
 
+
 class GetTableVersionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetTableVersions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#gettableversionspaginator)
     """
 
     def paginate(
         self,
         *,
         DatabaseName: str,
         TableName: str,
         CatalogId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetTableVersionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetTableVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#gettableversionspaginator)
         """
 
+
 class GetTablesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetTables)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#gettablespaginator)
     """
 
     def paginate(
         self,
         *,
         DatabaseName: str,
         CatalogId: str = ...,
         Expression: str = ...,
         TransactionId: str = ...,
         QueryAsOfTime: Union[datetime, str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetTablesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetTables.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#gettablespaginator)
         """
 
+
 class GetTriggersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetTriggers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#gettriggerspaginator)
     """
 
     def paginate(
-        self, *, DependentJobName: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, DependentJobName: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetTriggersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetTriggers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#gettriggerspaginator)
         """
 
+
 class GetUserDefinedFunctionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetUserDefinedFunctions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getuserdefinedfunctionspaginator)
     """
 
     def paginate(
         self,
         *,
         Pattern: str,
         CatalogId: str = ...,
         DatabaseName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetUserDefinedFunctionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.GetUserDefinedFunctions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#getuserdefinedfunctionspaginator)
         """
 
+
 class ListRegistriesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.ListRegistries)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#listregistriespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRegistriesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.ListRegistries.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#listregistriespaginator)
         """
 
+
 class ListSchemaVersionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.ListSchemaVersions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#listschemaversionspaginator)
     """
 
     def paginate(
-        self, *, SchemaId: SchemaIdTypeDef, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, SchemaId: SchemaIdTypeDef, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSchemaVersionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.ListSchemaVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#listschemaversionspaginator)
         """
 
+
 class ListSchemasPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.ListSchemas)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#listschemaspaginator)
     """
 
     def paginate(
-        self, *, RegistryId: RegistryIdTypeDef = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        RegistryId: RegistryIdTypeDef = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSchemasResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue.Paginator.ListSchemas.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/paginators/#listschemaspaginator)
         """
```

### Comparing `types-aiobotocore-glue-2.5.0.post1/types_aiobotocore_glue/type_defs.py` & `types-aiobotocore-glue-2.5.1/types_aiobotocore_glue/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -108,19 +108,20 @@
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "NotificationPropertyTypeDef",
     "AggregateOperationTypeDef",
+    "AmazonRedshiftAdvancedOptionTypeDef",
+    "OptionTypeDef",
     "ApplyMappingTypeDef",
     "AuditContextTypeDef",
     "PartitionValueListTypeDef",
     "BasicCatalogTargetTypeDef",
-    "ResponseMetadataTypeDef",
     "BatchDeleteConnectionRequestRequestTypeDef",
     "ErrorDetailTypeDef",
     "BatchDeleteTableRequestRequestTypeDef",
     "BatchDeleteTableVersionRequestRequestTypeDef",
     "BatchGetBlueprintsRequestRequestTypeDef",
     "BatchGetCrawlersRequestRequestTypeDef",
     "BatchGetCustomEntityTypesRequestRequestTypeDef",
@@ -137,24 +138,26 @@
     "BlueprintDetailsTypeDef",
     "BlueprintRunTypeDef",
     "LastActiveDefinitionTypeDef",
     "BooleanColumnStatisticsDataTypeDef",
     "CancelDataQualityRuleRecommendationRunRequestRequestTypeDef",
     "CancelDataQualityRulesetEvaluationRunRequestRequestTypeDef",
     "CancelMLTaskRunRequestRequestTypeDef",
+    "CancelMLTaskRunResponseTypeDef",
     "CancelStatementRequestRequestTypeDef",
     "CatalogEntryTypeDef",
     "CatalogImportStatusTypeDef",
     "KafkaStreamingSourceOptionsTypeDef",
     "StreamingDataPreviewOptionsTypeDef",
     "KinesisStreamingSourceOptionsTypeDef",
     "CatalogSchemaChangePolicyTypeDef",
     "CatalogSourceTypeDef",
     "CatalogTargetTypeDef",
     "CheckSchemaVersionValidityInputRequestTypeDef",
+    "CheckSchemaVersionValidityResponseTypeDef",
     "CsvClassifierTypeDef",
     "GrokClassifierTypeDef",
     "JsonClassifierTypeDef",
     "XMLClassifierTypeDef",
     "CloudWatchEncryptionTypeDef",
     "DirectJDBCSourceTypeDef",
     "DropDuplicatesTypeDef",
@@ -205,282 +208,299 @@
     "LastCrawlInfoTypeDef",
     "LineageConfigurationTypeDef",
     "RecrawlPolicyTypeDef",
     "ScheduleTypeDef",
     "SchemaChangePolicyTypeDef",
     "CrawlsFilterTypeDef",
     "CreateBlueprintRequestRequestTypeDef",
+    "CreateBlueprintResponseTypeDef",
     "CreateCsvClassifierRequestTypeDef",
     "CreateGrokClassifierRequestTypeDef",
     "CreateJsonClassifierRequestTypeDef",
     "CreateXMLClassifierRequestTypeDef",
     "CreateCustomEntityTypeRequestRequestTypeDef",
+    "CreateCustomEntityTypeResponseTypeDef",
     "DataQualityTargetTableTypeDef",
+    "CreateDataQualityRulesetResponseTypeDef",
     "CreateDevEndpointRequestRequestTypeDef",
+    "CreateDevEndpointResponseTypeDef",
     "ExecutionPropertyTypeDef",
     "JobCommandTypeDef",
     "SourceControlDetailsTypeDef",
+    "CreateJobResponseTypeDef",
     "GlueTableTypeDef",
+    "CreateMLTransformResponseTypeDef",
     "PartitionIndexTypeDef",
     "CreateRegistryInputRequestTypeDef",
+    "CreateRegistryResponseTypeDef",
     "RegistryIdTypeDef",
+    "CreateSchemaResponseTypeDef",
+    "CreateScriptResponseTypeDef",
+    "CreateSecurityConfigurationResponseTypeDef",
     "SessionCommandTypeDef",
     "EventBatchingConditionTypeDef",
+    "CreateTriggerResponseTypeDef",
     "CreateWorkflowRequestRequestTypeDef",
+    "CreateWorkflowResponseTypeDef",
     "DQResultsPublishingOptionsTypeDef",
     "DQStopJobOnFailureOptionsTypeDef",
     "EncryptionAtRestTypeDef",
     "DataLakePrincipalTypeDef",
     "DataQualityEvaluationRunAdditionalRunOptionsTypeDef",
     "DataQualityRuleResultTypeDef",
     "DatabaseIdentifierTypeDef",
+    "FederatedDatabaseTypeDef",
     "DatatypeTypeDef",
     "DecimalNumberTypeDef",
     "DeleteBlueprintRequestRequestTypeDef",
+    "DeleteBlueprintResponseTypeDef",
     "DeleteClassifierRequestRequestTypeDef",
     "DeleteColumnStatisticsForPartitionRequestRequestTypeDef",
     "DeleteColumnStatisticsForTableRequestRequestTypeDef",
     "DeleteConnectionRequestRequestTypeDef",
     "DeleteCrawlerRequestRequestTypeDef",
     "DeleteCustomEntityTypeRequestRequestTypeDef",
+    "DeleteCustomEntityTypeResponseTypeDef",
     "DeleteDataQualityRulesetRequestRequestTypeDef",
     "DeleteDatabaseRequestRequestTypeDef",
     "DeleteDevEndpointRequestRequestTypeDef",
     "DeleteJobRequestRequestTypeDef",
+    "DeleteJobResponseTypeDef",
     "DeleteMLTransformRequestRequestTypeDef",
+    "DeleteMLTransformResponseTypeDef",
     "DeletePartitionIndexRequestRequestTypeDef",
     "DeletePartitionRequestRequestTypeDef",
+    "DeleteRegistryResponseTypeDef",
     "DeleteResourcePolicyRequestRequestTypeDef",
     "SchemaIdTypeDef",
+    "DeleteSchemaResponseTypeDef",
     "DeleteSecurityConfigurationRequestRequestTypeDef",
     "DeleteSessionRequestRequestTypeDef",
+    "DeleteSessionResponseTypeDef",
     "DeleteTableRequestRequestTypeDef",
     "DeleteTableVersionRequestRequestTypeDef",
     "DeleteTriggerRequestRequestTypeDef",
+    "DeleteTriggerResponseTypeDef",
     "DeleteUserDefinedFunctionRequestRequestTypeDef",
     "DeleteWorkflowRequestRequestTypeDef",
+    "DeleteWorkflowResponseTypeDef",
     "DevEndpointCustomLibrariesTypeDef",
     "DirectSchemaChangePolicyTypeDef",
     "NullCheckBoxListTypeDef",
     "TransformConfigParameterTypeDef",
     "EdgeTypeDef",
     "JobBookmarksEncryptionTypeDef",
     "S3EncryptionTypeDef",
     "ErrorDetailsTypeDef",
     "ExportLabelsTaskRunPropertiesTypeDef",
+    "FederatedTableTypeDef",
     "FilterValueTypeDef",
     "FindMatchesParametersTypeDef",
     "FindMatchesTaskRunPropertiesTypeDef",
     "GetBlueprintRequestRequestTypeDef",
     "GetBlueprintRunRequestRequestTypeDef",
     "GetBlueprintRunsRequestRequestTypeDef",
     "GetCatalogImportStatusRequestRequestTypeDef",
     "GetClassifierRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetClassifiersRequestGetClassifiersPaginateTypeDef",
     "GetClassifiersRequestRequestTypeDef",
     "GetColumnStatisticsForPartitionRequestRequestTypeDef",
     "GetColumnStatisticsForTableRequestRequestTypeDef",
     "GetConnectionRequestRequestTypeDef",
     "GetConnectionsFilterTypeDef",
+    "GetCrawlerMetricsRequestGetCrawlerMetricsPaginateTypeDef",
     "GetCrawlerMetricsRequestRequestTypeDef",
     "GetCrawlerRequestRequestTypeDef",
+    "GetCrawlersRequestGetCrawlersPaginateTypeDef",
     "GetCrawlersRequestRequestTypeDef",
     "GetCustomEntityTypeRequestRequestTypeDef",
+    "GetCustomEntityTypeResponseTypeDef",
     "GetDataCatalogEncryptionSettingsRequestRequestTypeDef",
     "GetDataQualityResultRequestRequestTypeDef",
     "GetDataQualityRuleRecommendationRunRequestRequestTypeDef",
     "GetDataQualityRulesetEvaluationRunRequestRequestTypeDef",
     "GetDataQualityRulesetRequestRequestTypeDef",
     "GetDatabaseRequestRequestTypeDef",
+    "GetDatabasesRequestGetDatabasesPaginateTypeDef",
     "GetDatabasesRequestRequestTypeDef",
     "GetDataflowGraphRequestRequestTypeDef",
     "GetDevEndpointRequestRequestTypeDef",
+    "GetDevEndpointsRequestGetDevEndpointsPaginateTypeDef",
     "GetDevEndpointsRequestRequestTypeDef",
     "GetJobBookmarkRequestRequestTypeDef",
     "JobBookmarkEntryTypeDef",
     "GetJobRequestRequestTypeDef",
     "GetJobRunRequestRequestTypeDef",
+    "GetJobRunsRequestGetJobRunsPaginateTypeDef",
     "GetJobRunsRequestRequestTypeDef",
+    "GetJobsRequestGetJobsPaginateTypeDef",
     "GetJobsRequestRequestTypeDef",
     "GetMLTaskRunRequestRequestTypeDef",
     "TaskRunFilterCriteriaTypeDef",
     "TaskRunSortCriteriaTypeDef",
     "GetMLTransformRequestRequestTypeDef",
     "SchemaColumnTypeDef",
     "TransformSortCriteriaTypeDef",
     "MappingEntryTypeDef",
+    "GetPartitionIndexesRequestGetPartitionIndexesPaginateTypeDef",
     "GetPartitionIndexesRequestRequestTypeDef",
     "GetPartitionRequestRequestTypeDef",
     "SegmentTypeDef",
+    "GetPlanResponseTypeDef",
+    "GetRegistryResponseTypeDef",
+    "GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef",
     "GetResourcePoliciesRequestRequestTypeDef",
     "GluePolicyTypeDef",
     "GetResourcePolicyRequestRequestTypeDef",
+    "GetResourcePolicyResponseTypeDef",
+    "GetSchemaByDefinitionResponseTypeDef",
+    "GetSchemaResponseTypeDef",
     "SchemaVersionNumberTypeDef",
+    "GetSchemaVersionResponseTypeDef",
+    "GetSchemaVersionsDiffResponseTypeDef",
     "GetSecurityConfigurationRequestRequestTypeDef",
+    "GetSecurityConfigurationsRequestGetSecurityConfigurationsPaginateTypeDef",
     "GetSecurityConfigurationsRequestRequestTypeDef",
     "GetSessionRequestRequestTypeDef",
     "GetStatementRequestRequestTypeDef",
     "GetTableRequestRequestTypeDef",
     "GetTableVersionRequestRequestTypeDef",
+    "GetTableVersionsRequestGetTableVersionsPaginateTypeDef",
     "GetTableVersionsRequestRequestTypeDef",
+    "GetTablesRequestGetTablesPaginateTypeDef",
     "GetTablesRequestRequestTypeDef",
     "GetTagsRequestRequestTypeDef",
+    "GetTagsResponseTypeDef",
     "GetTriggerRequestRequestTypeDef",
+    "GetTriggersRequestGetTriggersPaginateTypeDef",
     "GetTriggersRequestRequestTypeDef",
     "GetUserDefinedFunctionRequestRequestTypeDef",
+    "GetUserDefinedFunctionsRequestGetUserDefinedFunctionsPaginateTypeDef",
     "GetUserDefinedFunctionsRequestRequestTypeDef",
     "GetWorkflowRequestRequestTypeDef",
     "GetWorkflowRunPropertiesRequestRequestTypeDef",
+    "GetWorkflowRunPropertiesResponseTypeDef",
     "GetWorkflowRunRequestRequestTypeDef",
     "GetWorkflowRunsRequestRequestTypeDef",
     "GlueStudioSchemaColumnTypeDef",
     "S3SourceAdditionalOptionsTypeDef",
     "ImportCatalogToGlueRequestRequestTypeDef",
     "ImportLabelsTaskRunPropertiesTypeDef",
     "JDBCConnectorOptionsTypeDef",
     "PredecessorTypeDef",
     "JoinColumnTypeDef",
     "KeySchemaElementTypeDef",
     "LabelingSetGenerationTaskRunPropertiesTypeDef",
     "ListBlueprintsRequestRequestTypeDef",
+    "ListBlueprintsResponseTypeDef",
     "ListCrawlersRequestRequestTypeDef",
+    "ListCrawlersResponseTypeDef",
     "ListCustomEntityTypesRequestRequestTypeDef",
     "ListDevEndpointsRequestRequestTypeDef",
+    "ListDevEndpointsResponseTypeDef",
     "ListJobsRequestRequestTypeDef",
+    "ListJobsResponseTypeDef",
+    "ListMLTransformsResponseTypeDef",
+    "ListRegistriesInputListRegistriesPaginateTypeDef",
     "ListRegistriesInputRequestTypeDef",
     "RegistryListItemTypeDef",
     "SchemaVersionListItemTypeDef",
     "SchemaListItemTypeDef",
     "ListSessionsRequestRequestTypeDef",
     "ListStatementsRequestRequestTypeDef",
     "ListTriggersRequestRequestTypeDef",
+    "ListTriggersResponseTypeDef",
     "ListWorkflowsRequestRequestTypeDef",
+    "ListWorkflowsResponseTypeDef",
     "MLUserDataEncryptionTypeDef",
     "MappingTypeDef",
     "OtherMetadataValueListItemTypeDef",
     "MetadataKeyValuePairTypeDef",
     "OrderTypeDef",
+    "PaginatorConfigTypeDef",
     "PropertyPredicateTypeDef",
     "PutResourcePolicyRequestRequestTypeDef",
+    "PutResourcePolicyResponseTypeDef",
+    "PutSchemaVersionMetadataResponseTypeDef",
     "PutWorkflowRunPropertiesRequestRequestTypeDef",
     "UpsertRedshiftTargetOptionsTypeDef",
+    "RegisterSchemaVersionResponseTypeDef",
+    "RemoveSchemaVersionMetadataResponseTypeDef",
     "ResetJobBookmarkRequestRequestTypeDef",
     "ResourceUriTypeDef",
+    "ResponseMetadataTypeDef",
     "ResumeWorkflowRunRequestRequestTypeDef",
+    "ResumeWorkflowRunResponseTypeDef",
     "RunStatementRequestRequestTypeDef",
+    "RunStatementResponseTypeDef",
     "S3DirectSourceAdditionalOptionsTypeDef",
     "SortCriterionTypeDef",
     "SerDeInfoTypeDef",
     "SkewedInfoTypeDef",
     "SqlAliasTypeDef",
     "StartBlueprintRunRequestRequestTypeDef",
+    "StartBlueprintRunResponseTypeDef",
     "StartCrawlerRequestRequestTypeDef",
     "StartCrawlerScheduleRequestRequestTypeDef",
+    "StartDataQualityRuleRecommendationRunResponseTypeDef",
+    "StartDataQualityRulesetEvaluationRunResponseTypeDef",
     "StartExportLabelsTaskRunRequestRequestTypeDef",
+    "StartExportLabelsTaskRunResponseTypeDef",
     "StartImportLabelsTaskRunRequestRequestTypeDef",
+    "StartImportLabelsTaskRunResponseTypeDef",
+    "StartJobRunResponseTypeDef",
     "StartMLEvaluationTaskRunRequestRequestTypeDef",
+    "StartMLEvaluationTaskRunResponseTypeDef",
     "StartMLLabelingSetGenerationTaskRunRequestRequestTypeDef",
+    "StartMLLabelingSetGenerationTaskRunResponseTypeDef",
     "StartTriggerRequestRequestTypeDef",
+    "StartTriggerResponseTypeDef",
     "StartWorkflowRunRequestRequestTypeDef",
+    "StartWorkflowRunResponseTypeDef",
     "StartingEventBatchConditionTypeDef",
     "StatementOutputDataTypeDef",
     "StopCrawlerRequestRequestTypeDef",
     "StopCrawlerScheduleRequestRequestTypeDef",
     "StopSessionRequestRequestTypeDef",
+    "StopSessionResponseTypeDef",
     "StopTriggerRequestRequestTypeDef",
+    "StopTriggerResponseTypeDef",
     "StopWorkflowRunRequestRequestTypeDef",
     "TableIdentifierTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateBlueprintRequestRequestTypeDef",
+    "UpdateBlueprintResponseTypeDef",
     "UpdateCsvClassifierRequestTypeDef",
     "UpdateGrokClassifierRequestTypeDef",
     "UpdateJsonClassifierRequestTypeDef",
     "UpdateXMLClassifierRequestTypeDef",
     "UpdateCrawlerScheduleRequestRequestTypeDef",
     "UpdateDataQualityRulesetRequestRequestTypeDef",
+    "UpdateDataQualityRulesetResponseTypeDef",
     "UpdateJobFromSourceControlRequestRequestTypeDef",
+    "UpdateJobFromSourceControlResponseTypeDef",
+    "UpdateJobResponseTypeDef",
+    "UpdateMLTransformResponseTypeDef",
+    "UpdateRegistryResponseTypeDef",
+    "UpdateSchemaResponseTypeDef",
     "UpdateSourceControlFromJobRequestRequestTypeDef",
+    "UpdateSourceControlFromJobResponseTypeDef",
     "UpdateWorkflowRequestRequestTypeDef",
+    "UpdateWorkflowResponseTypeDef",
     "WorkflowRunStatisticsTypeDef",
     "ActionTypeDef",
     "StartJobRunRequestRequestTypeDef",
     "AggregateTypeDef",
+    "AmazonRedshiftNodeDataTypeDef",
     "GetUnfilteredPartitionMetadataRequestRequestTypeDef",
     "GetUnfilteredTableMetadataRequestRequestTypeDef",
     "BackfillErrorTypeDef",
     "BatchDeletePartitionRequestRequestTypeDef",
     "BatchGetPartitionRequestRequestTypeDef",
-    "CancelMLTaskRunResponseTypeDef",
-    "CheckSchemaVersionValidityResponseTypeDef",
-    "CreateBlueprintResponseTypeDef",
-    "CreateCustomEntityTypeResponseTypeDef",
-    "CreateDataQualityRulesetResponseTypeDef",
-    "CreateDevEndpointResponseTypeDef",
-    "CreateJobResponseTypeDef",
-    "CreateMLTransformResponseTypeDef",
-    "CreateRegistryResponseTypeDef",
-    "CreateSchemaResponseTypeDef",
-    "CreateScriptResponseTypeDef",
-    "CreateSecurityConfigurationResponseTypeDef",
-    "CreateTriggerResponseTypeDef",
-    "CreateWorkflowResponseTypeDef",
-    "DeleteBlueprintResponseTypeDef",
-    "DeleteCustomEntityTypeResponseTypeDef",
-    "DeleteJobResponseTypeDef",
-    "DeleteMLTransformResponseTypeDef",
-    "DeleteRegistryResponseTypeDef",
-    "DeleteSchemaResponseTypeDef",
-    "DeleteSessionResponseTypeDef",
-    "DeleteTriggerResponseTypeDef",
-    "DeleteWorkflowResponseTypeDef",
-    "GetCustomEntityTypeResponseTypeDef",
-    "GetPlanResponseTypeDef",
-    "GetRegistryResponseTypeDef",
-    "GetResourcePolicyResponseTypeDef",
-    "GetSchemaByDefinitionResponseTypeDef",
-    "GetSchemaResponseTypeDef",
-    "GetSchemaVersionResponseTypeDef",
-    "GetSchemaVersionsDiffResponseTypeDef",
-    "GetTagsResponseTypeDef",
-    "GetWorkflowRunPropertiesResponseTypeDef",
-    "ListBlueprintsResponseTypeDef",
-    "ListCrawlersResponseTypeDef",
-    "ListDevEndpointsResponseTypeDef",
-    "ListJobsResponseTypeDef",
-    "ListMLTransformsResponseTypeDef",
-    "ListTriggersResponseTypeDef",
-    "ListWorkflowsResponseTypeDef",
-    "PutResourcePolicyResponseTypeDef",
-    "PutSchemaVersionMetadataResponseTypeDef",
-    "RegisterSchemaVersionResponseTypeDef",
-    "RemoveSchemaVersionMetadataResponseTypeDef",
-    "ResumeWorkflowRunResponseTypeDef",
-    "RunStatementResponseTypeDef",
-    "StartBlueprintRunResponseTypeDef",
-    "StartDataQualityRuleRecommendationRunResponseTypeDef",
-    "StartDataQualityRulesetEvaluationRunResponseTypeDef",
-    "StartExportLabelsTaskRunResponseTypeDef",
-    "StartImportLabelsTaskRunResponseTypeDef",
-    "StartJobRunResponseTypeDef",
-    "StartMLEvaluationTaskRunResponseTypeDef",
-    "StartMLLabelingSetGenerationTaskRunResponseTypeDef",
-    "StartTriggerResponseTypeDef",
-    "StartWorkflowRunResponseTypeDef",
-    "StopSessionResponseTypeDef",
-    "StopTriggerResponseTypeDef",
-    "UpdateBlueprintResponseTypeDef",
-    "UpdateDataQualityRulesetResponseTypeDef",
-    "UpdateJobFromSourceControlResponseTypeDef",
-    "UpdateJobResponseTypeDef",
-    "UpdateMLTransformResponseTypeDef",
-    "UpdateRegistryResponseTypeDef",
-    "UpdateSchemaResponseTypeDef",
-    "UpdateSourceControlFromJobResponseTypeDef",
-    "UpdateWorkflowResponseTypeDef",
     "BatchDeleteConnectionResponseTypeDef",
     "BatchStopJobRunErrorTypeDef",
     "BatchUpdatePartitionFailureEntryTypeDef",
     "ColumnErrorTypeDef",
     "PartitionErrorTypeDef",
     "TableErrorTypeDef",
     "TableVersionErrorTypeDef",
@@ -519,57 +539,42 @@
     "DataQualityRulesetListDetailsTypeDef",
     "GetDataQualityRulesetResponseTypeDef",
     "DataSourceTypeDef",
     "CreatePartitionIndexRequestRequestTypeDef",
     "CreateSchemaInputRequestTypeDef",
     "DeleteRegistryInputRequestTypeDef",
     "GetRegistryInputRequestTypeDef",
+    "ListSchemasInputListSchemasPaginateTypeDef",
     "ListSchemasInputRequestTypeDef",
     "UpdateRegistryInputRequestTypeDef",
     "CreateSessionRequestRequestTypeDef",
     "SessionTypeDef",
+    "EvaluateDataQualityMultiFrameTypeDef",
     "EvaluateDataQualityTypeDef",
     "DataCatalogEncryptionSettingsTypeDef",
     "PrincipalPermissionsTypeDef",
     "NullValueFieldTypeDef",
     "DecimalColumnStatisticsDataTypeDef",
     "DeleteSchemaInputRequestTypeDef",
     "DeleteSchemaVersionsInputRequestTypeDef",
     "GetSchemaByDefinitionInputRequestTypeDef",
     "GetSchemaInputRequestTypeDef",
+    "ListSchemaVersionsInputListSchemaVersionsPaginateTypeDef",
     "ListSchemaVersionsInputRequestTypeDef",
     "RegisterSchemaVersionInputRequestTypeDef",
     "SchemaReferenceTypeDef",
     "UpdateDevEndpointRequestRequestTypeDef",
     "S3DeltaDirectTargetTypeDef",
     "S3DirectTargetTypeDef",
     "S3GlueParquetTargetTypeDef",
     "S3HudiDirectTargetTypeDef",
-    "DynamicTransformTypeDef",
     "EncryptionConfigurationTypeDef",
     "SchemaVersionErrorItemTypeDef",
     "FilterExpressionTypeDef",
     "TransformParametersTypeDef",
-    "GetClassifiersRequestGetClassifiersPaginateTypeDef",
-    "GetCrawlerMetricsRequestGetCrawlerMetricsPaginateTypeDef",
-    "GetCrawlersRequestGetCrawlersPaginateTypeDef",
-    "GetDatabasesRequestGetDatabasesPaginateTypeDef",
-    "GetDevEndpointsRequestGetDevEndpointsPaginateTypeDef",
-    "GetJobRunsRequestGetJobRunsPaginateTypeDef",
-    "GetJobsRequestGetJobsPaginateTypeDef",
-    "GetPartitionIndexesRequestGetPartitionIndexesPaginateTypeDef",
-    "GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef",
-    "GetSecurityConfigurationsRequestGetSecurityConfigurationsPaginateTypeDef",
-    "GetTableVersionsRequestGetTableVersionsPaginateTypeDef",
-    "GetTablesRequestGetTablesPaginateTypeDef",
-    "GetTriggersRequestGetTriggersPaginateTypeDef",
-    "GetUserDefinedFunctionsRequestGetUserDefinedFunctionsPaginateTypeDef",
-    "ListRegistriesInputListRegistriesPaginateTypeDef",
-    "ListSchemaVersionsInputListSchemaVersionsPaginateTypeDef",
-    "ListSchemasInputListSchemasPaginateTypeDef",
     "GetConnectionsRequestGetConnectionsPaginateTypeDef",
     "GetConnectionsRequestRequestTypeDef",
     "GetJobBookmarkResponseTypeDef",
     "ResetJobBookmarkResponseTypeDef",
     "GetMLTaskRunsRequestRequestTypeDef",
     "TransformFilterCriteriaTypeDef",
     "GetMappingResponseTypeDef",
@@ -596,14 +601,16 @@
     "RemoveSchemaVersionMetadataInputRequestTypeDef",
     "RedshiftTargetTypeDef",
     "UserDefinedFunctionInputTypeDef",
     "UserDefinedFunctionTypeDef",
     "SearchTablesRequestRequestTypeDef",
     "StatementOutputTypeDef",
     "UpdateClassifierRequestRequestTypeDef",
+    "AmazonRedshiftSourceTypeDef",
+    "AmazonRedshiftTargetTypeDef",
     "PartitionIndexDescriptorTypeDef",
     "BatchStopJobRunResponseTypeDef",
     "BatchUpdatePartitionResponseTypeDef",
     "BatchCreatePartitionResponseTypeDef",
     "BatchDeletePartitionResponseTypeDef",
     "BatchDeleteTableResponseTypeDef",
     "BatchDeleteTableVersionResponseTypeDef",
@@ -657,14 +664,15 @@
     "UpdateMLTransformRequestRequestTypeDef",
     "GetMLTransformsRequestRequestTypeDef",
     "ListMLTransformsRequestRequestTypeDef",
     "AthenaConnectorSourceTypeDef",
     "CatalogDeltaSourceTypeDef",
     "CatalogHudiSourceTypeDef",
     "CustomCodeTypeDef",
+    "DynamicTransformTypeDef",
     "JDBCConnectorSourceTypeDef",
     "JDBCConnectorTargetTypeDef",
     "S3CatalogDeltaSourceTypeDef",
     "S3CatalogHudiSourceTypeDef",
     "S3CsvSourceTypeDef",
     "S3DeltaSourceTypeDef",
     "S3HudiSourceTypeDef",
@@ -776,14 +784,33 @@
     "AggregateOperationTypeDef",
     {
         "Column": List[str],
         "AggFunc": AggFunctionType,
     },
 )
 
+AmazonRedshiftAdvancedOptionTypeDef = TypedDict(
+    "AmazonRedshiftAdvancedOptionTypeDef",
+    {
+        "Key": str,
+        "Value": str,
+    },
+    total=False,
+)
+
+OptionTypeDef = TypedDict(
+    "OptionTypeDef",
+    {
+        "Value": str,
+        "Label": str,
+        "Description": str,
+    },
+    total=False,
+)
+
 ApplyMappingTypeDef = TypedDict(
     "ApplyMappingTypeDef",
     {
         "Name": str,
         "Inputs": List[str],
         "Mapping": List["MappingTypeDef"],
     },
@@ -812,25 +839,14 @@
         "Name": str,
         "Inputs": List[str],
         "Database": str,
         "Table": str,
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
 _RequiredBatchDeleteConnectionRequestRequestTypeDef = TypedDict(
     "_RequiredBatchDeleteConnectionRequestRequestTypeDef",
     {
         "ConnectionNameList": Sequence[str],
     },
 )
 _OptionalBatchDeleteConnectionRequestRequestTypeDef = TypedDict(
@@ -1134,14 +1150,24 @@
     "CancelMLTaskRunRequestRequestTypeDef",
     {
         "TransformId": str,
         "TaskRunId": str,
     },
 )
 
+CancelMLTaskRunResponseTypeDef = TypedDict(
+    "CancelMLTaskRunResponseTypeDef",
+    {
+        "TransformId": str,
+        "TaskRunId": str,
+        "Status": TaskStatusTypeType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCancelStatementRequestRequestTypeDef = TypedDict(
     "_RequiredCancelStatementRequestRequestTypeDef",
     {
         "SessionId": str,
         "Id": int,
     },
 )
@@ -1195,14 +1221,15 @@
         "NumRetries": int,
         "RetryIntervalMs": int,
         "MaxOffsetsPerTrigger": int,
         "MinPartitions": int,
         "IncludeHeaders": bool,
         "AddRecordTimestamp": str,
         "EmitConsumerLagMetrics": str,
+        "StartingTimestamp": datetime,
     },
     total=False,
 )
 
 StreamingDataPreviewOptionsTypeDef = TypedDict(
     "StreamingDataPreviewOptionsTypeDef",
     {
@@ -1231,14 +1258,15 @@
         "MaxRetryIntervalMs": int,
         "AvoidEmptyBatches": bool,
         "StreamArn": str,
         "RoleArn": str,
         "RoleSessionName": str,
         "AddRecordTimestamp": str,
         "EmitConsumerLagMetrics": str,
+        "StartingTimestamp": datetime,
     },
     total=False,
 )
 
 CatalogSchemaChangePolicyTypeDef = TypedDict(
     "CatalogSchemaChangePolicyTypeDef",
     {
@@ -1283,14 +1311,23 @@
     "CheckSchemaVersionValidityInputRequestTypeDef",
     {
         "DataFormat": DataFormatType,
         "SchemaDefinition": str,
     },
 )
 
+CheckSchemaVersionValidityResponseTypeDef = TypedDict(
+    "CheckSchemaVersionValidityResponseTypeDef",
+    {
+        "Valid": bool,
+        "Error": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCsvClassifierTypeDef = TypedDict(
     "_RequiredCsvClassifierTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalCsvClassifierTypeDef = TypedDict(
@@ -2093,14 +2130,22 @@
 
 class CreateBlueprintRequestRequestTypeDef(
     _RequiredCreateBlueprintRequestRequestTypeDef, _OptionalCreateBlueprintRequestRequestTypeDef
 ):
     pass
 
 
+CreateBlueprintResponseTypeDef = TypedDict(
+    "CreateBlueprintResponseTypeDef",
+    {
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateCsvClassifierRequestTypeDef = TypedDict(
     "_RequiredCreateCsvClassifierRequestTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalCreateCsvClassifierRequestTypeDef = TypedDict(
@@ -2185,33 +2230,64 @@
         "RegexString": str,
     },
 )
 _OptionalCreateCustomEntityTypeRequestRequestTypeDef = TypedDict(
     "_OptionalCreateCustomEntityTypeRequestRequestTypeDef",
     {
         "ContextWords": Sequence[str],
+        "Tags": Mapping[str, str],
     },
     total=False,
 )
 
 
 class CreateCustomEntityTypeRequestRequestTypeDef(
     _RequiredCreateCustomEntityTypeRequestRequestTypeDef,
     _OptionalCreateCustomEntityTypeRequestRequestTypeDef,
 ):
     pass
 
 
-DataQualityTargetTableTypeDef = TypedDict(
-    "DataQualityTargetTableTypeDef",
+CreateCustomEntityTypeResponseTypeDef = TypedDict(
+    "CreateCustomEntityTypeResponseTypeDef",
+    {
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredDataQualityTargetTableTypeDef = TypedDict(
+    "_RequiredDataQualityTargetTableTypeDef",
     {
         "TableName": str,
         "DatabaseName": str,
     },
 )
+_OptionalDataQualityTargetTableTypeDef = TypedDict(
+    "_OptionalDataQualityTargetTableTypeDef",
+    {
+        "CatalogId": str,
+    },
+    total=False,
+)
+
+
+class DataQualityTargetTableTypeDef(
+    _RequiredDataQualityTargetTableTypeDef, _OptionalDataQualityTargetTableTypeDef
+):
+    pass
+
+
+CreateDataQualityRulesetResponseTypeDef = TypedDict(
+    "CreateDataQualityRulesetResponseTypeDef",
+    {
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredCreateDevEndpointRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDevEndpointRequestRequestTypeDef",
     {
         "EndpointName": str,
         "RoleArn": str,
     },
@@ -2239,28 +2315,55 @@
 
 class CreateDevEndpointRequestRequestTypeDef(
     _RequiredCreateDevEndpointRequestRequestTypeDef, _OptionalCreateDevEndpointRequestRequestTypeDef
 ):
     pass
 
 
+CreateDevEndpointResponseTypeDef = TypedDict(
+    "CreateDevEndpointResponseTypeDef",
+    {
+        "EndpointName": str,
+        "Status": str,
+        "SecurityGroupIds": List[str],
+        "SubnetId": str,
+        "RoleArn": str,
+        "YarnEndpointAddress": str,
+        "ZeppelinRemoteSparkInterpreterPort": int,
+        "NumberOfNodes": int,
+        "WorkerType": WorkerTypeType,
+        "GlueVersion": str,
+        "NumberOfWorkers": int,
+        "AvailabilityZone": str,
+        "VpcId": str,
+        "ExtraPythonLibsS3Path": str,
+        "ExtraJarsS3Path": str,
+        "FailureReason": str,
+        "SecurityConfiguration": str,
+        "CreatedTimestamp": datetime,
+        "Arguments": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ExecutionPropertyTypeDef = TypedDict(
     "ExecutionPropertyTypeDef",
     {
         "MaxConcurrentRuns": int,
     },
     total=False,
 )
 
 JobCommandTypeDef = TypedDict(
     "JobCommandTypeDef",
     {
         "Name": str,
         "ScriptLocation": str,
         "PythonVersion": str,
+        "Runtime": str,
     },
     total=False,
 )
 
 SourceControlDetailsTypeDef = TypedDict(
     "SourceControlDetailsTypeDef",
     {
@@ -2272,14 +2375,22 @@
         "LastCommitId": str,
         "AuthStrategy": SourceControlAuthStrategyType,
         "AuthToken": str,
     },
     total=False,
 )
 
+CreateJobResponseTypeDef = TypedDict(
+    "CreateJobResponseTypeDef",
+    {
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGlueTableTypeDef = TypedDict(
     "_RequiredGlueTableTypeDef",
     {
         "DatabaseName": str,
         "TableName": str,
     },
 )
@@ -2294,14 +2405,22 @@
 )
 
 
 class GlueTableTypeDef(_RequiredGlueTableTypeDef, _OptionalGlueTableTypeDef):
     pass
 
 
+CreateMLTransformResponseTypeDef = TypedDict(
+    "CreateMLTransformResponseTypeDef",
+    {
+        "TransformId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 PartitionIndexTypeDef = TypedDict(
     "PartitionIndexTypeDef",
     {
         "Keys": Sequence[str],
         "IndexName": str,
     },
 )
@@ -2324,23 +2443,73 @@
 
 class CreateRegistryInputRequestTypeDef(
     _RequiredCreateRegistryInputRequestTypeDef, _OptionalCreateRegistryInputRequestTypeDef
 ):
     pass
 
 
+CreateRegistryResponseTypeDef = TypedDict(
+    "CreateRegistryResponseTypeDef",
+    {
+        "RegistryArn": str,
+        "RegistryName": str,
+        "Description": str,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RegistryIdTypeDef = TypedDict(
     "RegistryIdTypeDef",
     {
         "RegistryName": str,
         "RegistryArn": str,
     },
     total=False,
 )
 
+CreateSchemaResponseTypeDef = TypedDict(
+    "CreateSchemaResponseTypeDef",
+    {
+        "RegistryName": str,
+        "RegistryArn": str,
+        "SchemaName": str,
+        "SchemaArn": str,
+        "Description": str,
+        "DataFormat": DataFormatType,
+        "Compatibility": CompatibilityType,
+        "SchemaCheckpoint": int,
+        "LatestSchemaVersion": int,
+        "NextSchemaVersion": int,
+        "SchemaStatus": SchemaStatusType,
+        "Tags": Dict[str, str],
+        "SchemaVersionId": str,
+        "SchemaVersionStatus": SchemaVersionStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateScriptResponseTypeDef = TypedDict(
+    "CreateScriptResponseTypeDef",
+    {
+        "PythonScript": str,
+        "ScalaCode": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateSecurityConfigurationResponseTypeDef = TypedDict(
+    "CreateSecurityConfigurationResponseTypeDef",
+    {
+        "Name": str,
+        "CreatedTimestamp": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 SessionCommandTypeDef = TypedDict(
     "SessionCommandTypeDef",
     {
         "Name": str,
         "PythonVersion": str,
     },
     total=False,
@@ -2363,14 +2532,22 @@
 
 class EventBatchingConditionTypeDef(
     _RequiredEventBatchingConditionTypeDef, _OptionalEventBatchingConditionTypeDef
 ):
     pass
 
 
+CreateTriggerResponseTypeDef = TypedDict(
+    "CreateTriggerResponseTypeDef",
+    {
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateWorkflowRequestRequestTypeDef = TypedDict(
     "_RequiredCreateWorkflowRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalCreateWorkflowRequestRequestTypeDef = TypedDict(
@@ -2387,14 +2564,22 @@
 
 class CreateWorkflowRequestRequestTypeDef(
     _RequiredCreateWorkflowRequestRequestTypeDef, _OptionalCreateWorkflowRequestRequestTypeDef
 ):
     pass
 
 
+CreateWorkflowResponseTypeDef = TypedDict(
+    "CreateWorkflowResponseTypeDef",
+    {
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DQResultsPublishingOptionsTypeDef = TypedDict(
     "DQResultsPublishingOptionsTypeDef",
     {
         "EvaluationContext": str,
         "ResultsS3Prefix": str,
         "CloudWatchMetricsEnabled": bool,
         "ResultsPublishingEnabled": bool,
@@ -2449,23 +2634,34 @@
 DataQualityRuleResultTypeDef = TypedDict(
     "DataQualityRuleResultTypeDef",
     {
         "Name": str,
         "Description": str,
         "EvaluationMessage": str,
         "Result": DataQualityRuleResultStatusType,
+        "EvaluatedMetrics": Dict[str, float],
     },
     total=False,
 )
 
 DatabaseIdentifierTypeDef = TypedDict(
     "DatabaseIdentifierTypeDef",
     {
         "CatalogId": str,
         "DatabaseName": str,
+        "Region": str,
+    },
+    total=False,
+)
+
+FederatedDatabaseTypeDef = TypedDict(
+    "FederatedDatabaseTypeDef",
+    {
+        "Identifier": str,
+        "ConnectionName": str,
     },
     total=False,
 )
 
 DatatypeTypeDef = TypedDict(
     "DatatypeTypeDef",
     {
@@ -2485,14 +2681,22 @@
 DeleteBlueprintRequestRequestTypeDef = TypedDict(
     "DeleteBlueprintRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+DeleteBlueprintResponseTypeDef = TypedDict(
+    "DeleteBlueprintResponseTypeDef",
+    {
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteClassifierRequestRequestTypeDef = TypedDict(
     "DeleteClassifierRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
@@ -2576,14 +2780,22 @@
 DeleteCustomEntityTypeRequestRequestTypeDef = TypedDict(
     "DeleteCustomEntityTypeRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+DeleteCustomEntityTypeResponseTypeDef = TypedDict(
+    "DeleteCustomEntityTypeResponseTypeDef",
+    {
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteDataQualityRulesetRequestRequestTypeDef = TypedDict(
     "DeleteDataQualityRulesetRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
@@ -2618,21 +2830,37 @@
 DeleteJobRequestRequestTypeDef = TypedDict(
     "DeleteJobRequestRequestTypeDef",
     {
         "JobName": str,
     },
 )
 
+DeleteJobResponseTypeDef = TypedDict(
+    "DeleteJobResponseTypeDef",
+    {
+        "JobName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteMLTransformRequestRequestTypeDef = TypedDict(
     "DeleteMLTransformRequestRequestTypeDef",
     {
         "TransformId": str,
     },
 )
 
+DeleteMLTransformResponseTypeDef = TypedDict(
+    "DeleteMLTransformResponseTypeDef",
+    {
+        "TransformId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeletePartitionIndexRequestRequestTypeDef = TypedDict(
     "_RequiredDeletePartitionIndexRequestRequestTypeDef",
     {
         "DatabaseName": str,
         "TableName": str,
         "IndexName": str,
     },
@@ -2672,14 +2900,24 @@
 
 class DeletePartitionRequestRequestTypeDef(
     _RequiredDeletePartitionRequestRequestTypeDef, _OptionalDeletePartitionRequestRequestTypeDef
 ):
     pass
 
 
+DeleteRegistryResponseTypeDef = TypedDict(
+    "DeleteRegistryResponseTypeDef",
+    {
+        "RegistryName": str,
+        "RegistryArn": str,
+        "Status": RegistryStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteResourcePolicyRequestRequestTypeDef = TypedDict(
     "DeleteResourcePolicyRequestRequestTypeDef",
     {
         "PolicyHashCondition": str,
         "ResourceArn": str,
     },
     total=False,
@@ -2691,14 +2929,24 @@
         "SchemaArn": str,
         "SchemaName": str,
         "RegistryName": str,
     },
     total=False,
 )
 
+DeleteSchemaResponseTypeDef = TypedDict(
+    "DeleteSchemaResponseTypeDef",
+    {
+        "SchemaArn": str,
+        "SchemaName": str,
+        "Status": SchemaStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteSecurityConfigurationRequestRequestTypeDef = TypedDict(
     "DeleteSecurityConfigurationRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
@@ -2719,14 +2967,22 @@
 
 class DeleteSessionRequestRequestTypeDef(
     _RequiredDeleteSessionRequestRequestTypeDef, _OptionalDeleteSessionRequestRequestTypeDef
 ):
     pass
 
 
+DeleteSessionResponseTypeDef = TypedDict(
+    "DeleteSessionResponseTypeDef",
+    {
+        "Id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteTableRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteTableRequestRequestTypeDef",
     {
         "DatabaseName": str,
         "Name": str,
     },
 )
@@ -2773,14 +3029,22 @@
 DeleteTriggerRequestRequestTypeDef = TypedDict(
     "DeleteTriggerRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+DeleteTriggerResponseTypeDef = TypedDict(
+    "DeleteTriggerResponseTypeDef",
+    {
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteUserDefinedFunctionRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteUserDefinedFunctionRequestRequestTypeDef",
     {
         "DatabaseName": str,
         "FunctionName": str,
     },
 )
@@ -2803,14 +3067,22 @@
 DeleteWorkflowRequestRequestTypeDef = TypedDict(
     "DeleteWorkflowRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+DeleteWorkflowResponseTypeDef = TypedDict(
+    "DeleteWorkflowResponseTypeDef",
+    {
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DevEndpointCustomLibrariesTypeDef = TypedDict(
     "DevEndpointCustomLibrariesTypeDef",
     {
         "ExtraPythonLibsS3Path": str,
         "ExtraJarsS3Path": str,
     },
     total=False,
@@ -2903,14 +3175,24 @@
     "ExportLabelsTaskRunPropertiesTypeDef",
     {
         "OutputS3Path": str,
     },
     total=False,
 )
 
+FederatedTableTypeDef = TypedDict(
+    "FederatedTableTypeDef",
+    {
+        "Identifier": str,
+        "DatabaseIdentifier": str,
+        "ConnectionName": str,
+    },
+    total=False,
+)
+
 FilterValueTypeDef = TypedDict(
     "FilterValueTypeDef",
     {
         "Type": FilterValueTypeType,
         "Value": List[str],
     },
 )
@@ -2999,20 +3281,18 @@
 GetClassifierRequestRequestTypeDef = TypedDict(
     "GetClassifierRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetClassifiersRequestGetClassifiersPaginateTypeDef = TypedDict(
+    "GetClassifiersRequestGetClassifiersPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 GetClassifiersRequestRequestTypeDef = TypedDict(
     "GetClassifiersRequestRequestTypeDef",
     {
@@ -3098,14 +3378,23 @@
     {
         "MatchCriteria": Sequence[str],
         "ConnectionType": ConnectionTypeType,
     },
     total=False,
 )
 
+GetCrawlerMetricsRequestGetCrawlerMetricsPaginateTypeDef = TypedDict(
+    "GetCrawlerMetricsRequestGetCrawlerMetricsPaginateTypeDef",
+    {
+        "CrawlerNameList": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetCrawlerMetricsRequestRequestTypeDef = TypedDict(
     "GetCrawlerMetricsRequestRequestTypeDef",
     {
         "CrawlerNameList": Sequence[str],
         "MaxResults": int,
         "NextToken": str,
     },
@@ -3115,14 +3404,22 @@
 GetCrawlerRequestRequestTypeDef = TypedDict(
     "GetCrawlerRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+GetCrawlersRequestGetCrawlersPaginateTypeDef = TypedDict(
+    "GetCrawlersRequestGetCrawlersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetCrawlersRequestRequestTypeDef = TypedDict(
     "GetCrawlersRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -3131,14 +3428,24 @@
 GetCustomEntityTypeRequestRequestTypeDef = TypedDict(
     "GetCustomEntityTypeRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+GetCustomEntityTypeResponseTypeDef = TypedDict(
+    "GetCustomEntityTypeResponseTypeDef",
+    {
+        "Name": str,
+        "RegexString": str,
+        "ContextWords": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetDataCatalogEncryptionSettingsRequestRequestTypeDef = TypedDict(
     "GetDataCatalogEncryptionSettingsRequestRequestTypeDef",
     {
         "CatalogId": str,
     },
     total=False,
 )
@@ -3188,14 +3495,24 @@
 
 class GetDatabaseRequestRequestTypeDef(
     _RequiredGetDatabaseRequestRequestTypeDef, _OptionalGetDatabaseRequestRequestTypeDef
 ):
     pass
 
 
+GetDatabasesRequestGetDatabasesPaginateTypeDef = TypedDict(
+    "GetDatabasesRequestGetDatabasesPaginateTypeDef",
+    {
+        "CatalogId": str,
+        "ResourceShareType": ResourceShareTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetDatabasesRequestRequestTypeDef = TypedDict(
     "GetDatabasesRequestRequestTypeDef",
     {
         "CatalogId": str,
         "NextToken": str,
         "MaxResults": int,
         "ResourceShareType": ResourceShareTypeType,
@@ -3214,14 +3531,22 @@
 GetDevEndpointRequestRequestTypeDef = TypedDict(
     "GetDevEndpointRequestRequestTypeDef",
     {
         "EndpointName": str,
     },
 )
 
+GetDevEndpointsRequestGetDevEndpointsPaginateTypeDef = TypedDict(
+    "GetDevEndpointsRequestGetDevEndpointsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetDevEndpointsRequestRequestTypeDef = TypedDict(
     "GetDevEndpointsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -3287,14 +3612,36 @@
 
 class GetJobRunRequestRequestTypeDef(
     _RequiredGetJobRunRequestRequestTypeDef, _OptionalGetJobRunRequestRequestTypeDef
 ):
     pass
 
 
+_RequiredGetJobRunsRequestGetJobRunsPaginateTypeDef = TypedDict(
+    "_RequiredGetJobRunsRequestGetJobRunsPaginateTypeDef",
+    {
+        "JobName": str,
+    },
+)
+_OptionalGetJobRunsRequestGetJobRunsPaginateTypeDef = TypedDict(
+    "_OptionalGetJobRunsRequestGetJobRunsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetJobRunsRequestGetJobRunsPaginateTypeDef(
+    _RequiredGetJobRunsRequestGetJobRunsPaginateTypeDef,
+    _OptionalGetJobRunsRequestGetJobRunsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetJobRunsRequestRequestTypeDef = TypedDict(
     "_RequiredGetJobRunsRequestRequestTypeDef",
     {
         "JobName": str,
     },
 )
 _OptionalGetJobRunsRequestRequestTypeDef = TypedDict(
@@ -3309,14 +3656,22 @@
 
 class GetJobRunsRequestRequestTypeDef(
     _RequiredGetJobRunsRequestRequestTypeDef, _OptionalGetJobRunsRequestRequestTypeDef
 ):
     pass
 
 
+GetJobsRequestGetJobsPaginateTypeDef = TypedDict(
+    "GetJobsRequestGetJobsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetJobsRequestRequestTypeDef = TypedDict(
     "GetJobsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
@@ -3382,14 +3737,38 @@
         "TargetTable": str,
         "TargetPath": str,
         "TargetType": str,
     },
     total=False,
 )
 
+_RequiredGetPartitionIndexesRequestGetPartitionIndexesPaginateTypeDef = TypedDict(
+    "_RequiredGetPartitionIndexesRequestGetPartitionIndexesPaginateTypeDef",
+    {
+        "DatabaseName": str,
+        "TableName": str,
+    },
+)
+_OptionalGetPartitionIndexesRequestGetPartitionIndexesPaginateTypeDef = TypedDict(
+    "_OptionalGetPartitionIndexesRequestGetPartitionIndexesPaginateTypeDef",
+    {
+        "CatalogId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetPartitionIndexesRequestGetPartitionIndexesPaginateTypeDef(
+    _RequiredGetPartitionIndexesRequestGetPartitionIndexesPaginateTypeDef,
+    _OptionalGetPartitionIndexesRequestGetPartitionIndexesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetPartitionIndexesRequestRequestTypeDef = TypedDict(
     "_RequiredGetPartitionIndexesRequestRequestTypeDef",
     {
         "DatabaseName": str,
         "TableName": str,
     },
 )
@@ -3437,14 +3816,44 @@
     "SegmentTypeDef",
     {
         "SegmentNumber": int,
         "TotalSegments": int,
     },
 )
 
+GetPlanResponseTypeDef = TypedDict(
+    "GetPlanResponseTypeDef",
+    {
+        "PythonScript": str,
+        "ScalaCode": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetRegistryResponseTypeDef = TypedDict(
+    "GetRegistryResponseTypeDef",
+    {
+        "RegistryName": str,
+        "RegistryArn": str,
+        "Description": str,
+        "Status": RegistryStatusType,
+        "CreatedTime": str,
+        "UpdatedTime": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef = TypedDict(
+    "GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetResourcePoliciesRequestRequestTypeDef = TypedDict(
     "GetResourcePoliciesRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
@@ -3465,30 +3874,103 @@
     "GetResourcePolicyRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
     total=False,
 )
 
+GetResourcePolicyResponseTypeDef = TypedDict(
+    "GetResourcePolicyResponseTypeDef",
+    {
+        "PolicyInJson": str,
+        "PolicyHash": str,
+        "CreateTime": datetime,
+        "UpdateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetSchemaByDefinitionResponseTypeDef = TypedDict(
+    "GetSchemaByDefinitionResponseTypeDef",
+    {
+        "SchemaVersionId": str,
+        "SchemaArn": str,
+        "DataFormat": DataFormatType,
+        "Status": SchemaVersionStatusType,
+        "CreatedTime": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetSchemaResponseTypeDef = TypedDict(
+    "GetSchemaResponseTypeDef",
+    {
+        "RegistryName": str,
+        "RegistryArn": str,
+        "SchemaName": str,
+        "SchemaArn": str,
+        "Description": str,
+        "DataFormat": DataFormatType,
+        "Compatibility": CompatibilityType,
+        "SchemaCheckpoint": int,
+        "LatestSchemaVersion": int,
+        "NextSchemaVersion": int,
+        "SchemaStatus": SchemaStatusType,
+        "CreatedTime": str,
+        "UpdatedTime": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 SchemaVersionNumberTypeDef = TypedDict(
     "SchemaVersionNumberTypeDef",
     {
         "LatestVersion": bool,
         "VersionNumber": int,
     },
     total=False,
 )
 
+GetSchemaVersionResponseTypeDef = TypedDict(
+    "GetSchemaVersionResponseTypeDef",
+    {
+        "SchemaVersionId": str,
+        "SchemaDefinition": str,
+        "DataFormat": DataFormatType,
+        "SchemaArn": str,
+        "VersionNumber": int,
+        "Status": SchemaVersionStatusType,
+        "CreatedTime": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetSchemaVersionsDiffResponseTypeDef = TypedDict(
+    "GetSchemaVersionsDiffResponseTypeDef",
+    {
+        "Diff": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetSecurityConfigurationRequestRequestTypeDef = TypedDict(
     "GetSecurityConfigurationRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+GetSecurityConfigurationsRequestGetSecurityConfigurationsPaginateTypeDef = TypedDict(
+    "GetSecurityConfigurationsRequestGetSecurityConfigurationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetSecurityConfigurationsRequestRequestTypeDef = TypedDict(
     "GetSecurityConfigurationsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -3580,14 +4062,38 @@
 
 class GetTableVersionRequestRequestTypeDef(
     _RequiredGetTableVersionRequestRequestTypeDef, _OptionalGetTableVersionRequestRequestTypeDef
 ):
     pass
 
 
+_RequiredGetTableVersionsRequestGetTableVersionsPaginateTypeDef = TypedDict(
+    "_RequiredGetTableVersionsRequestGetTableVersionsPaginateTypeDef",
+    {
+        "DatabaseName": str,
+        "TableName": str,
+    },
+)
+_OptionalGetTableVersionsRequestGetTableVersionsPaginateTypeDef = TypedDict(
+    "_OptionalGetTableVersionsRequestGetTableVersionsPaginateTypeDef",
+    {
+        "CatalogId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetTableVersionsRequestGetTableVersionsPaginateTypeDef(
+    _RequiredGetTableVersionsRequestGetTableVersionsPaginateTypeDef,
+    _OptionalGetTableVersionsRequestGetTableVersionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetTableVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredGetTableVersionsRequestRequestTypeDef",
     {
         "DatabaseName": str,
         "TableName": str,
     },
 )
@@ -3604,14 +4110,40 @@
 
 class GetTableVersionsRequestRequestTypeDef(
     _RequiredGetTableVersionsRequestRequestTypeDef, _OptionalGetTableVersionsRequestRequestTypeDef
 ):
     pass
 
 
+_RequiredGetTablesRequestGetTablesPaginateTypeDef = TypedDict(
+    "_RequiredGetTablesRequestGetTablesPaginateTypeDef",
+    {
+        "DatabaseName": str,
+    },
+)
+_OptionalGetTablesRequestGetTablesPaginateTypeDef = TypedDict(
+    "_OptionalGetTablesRequestGetTablesPaginateTypeDef",
+    {
+        "CatalogId": str,
+        "Expression": str,
+        "TransactionId": str,
+        "QueryAsOfTime": Union[datetime, str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetTablesRequestGetTablesPaginateTypeDef(
+    _RequiredGetTablesRequestGetTablesPaginateTypeDef,
+    _OptionalGetTablesRequestGetTablesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetTablesRequestRequestTypeDef = TypedDict(
     "_RequiredGetTablesRequestRequestTypeDef",
     {
         "DatabaseName": str,
     },
 )
 _OptionalGetTablesRequestRequestTypeDef = TypedDict(
@@ -3637,21 +4169,38 @@
 GetTagsRequestRequestTypeDef = TypedDict(
     "GetTagsRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+GetTagsResponseTypeDef = TypedDict(
+    "GetTagsResponseTypeDef",
+    {
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetTriggerRequestRequestTypeDef = TypedDict(
     "GetTriggerRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+GetTriggersRequestGetTriggersPaginateTypeDef = TypedDict(
+    "GetTriggersRequestGetTriggersPaginateTypeDef",
+    {
+        "DependentJobName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetTriggersRequestRequestTypeDef = TypedDict(
     "GetTriggersRequestRequestTypeDef",
     {
         "NextToken": str,
         "DependentJobName": str,
         "MaxResults": int,
     },
@@ -3677,14 +4226,38 @@
 class GetUserDefinedFunctionRequestRequestTypeDef(
     _RequiredGetUserDefinedFunctionRequestRequestTypeDef,
     _OptionalGetUserDefinedFunctionRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredGetUserDefinedFunctionsRequestGetUserDefinedFunctionsPaginateTypeDef = TypedDict(
+    "_RequiredGetUserDefinedFunctionsRequestGetUserDefinedFunctionsPaginateTypeDef",
+    {
+        "Pattern": str,
+    },
+)
+_OptionalGetUserDefinedFunctionsRequestGetUserDefinedFunctionsPaginateTypeDef = TypedDict(
+    "_OptionalGetUserDefinedFunctionsRequestGetUserDefinedFunctionsPaginateTypeDef",
+    {
+        "CatalogId": str,
+        "DatabaseName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetUserDefinedFunctionsRequestGetUserDefinedFunctionsPaginateTypeDef(
+    _RequiredGetUserDefinedFunctionsRequestGetUserDefinedFunctionsPaginateTypeDef,
+    _OptionalGetUserDefinedFunctionsRequestGetUserDefinedFunctionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetUserDefinedFunctionsRequestRequestTypeDef = TypedDict(
     "_RequiredGetUserDefinedFunctionsRequestRequestTypeDef",
     {
         "Pattern": str,
     },
 )
 _OptionalGetUserDefinedFunctionsRequestRequestTypeDef = TypedDict(
@@ -3731,14 +4304,22 @@
     "GetWorkflowRunPropertiesRequestRequestTypeDef",
     {
         "Name": str,
         "RunId": str,
     },
 )
 
+GetWorkflowRunPropertiesResponseTypeDef = TypedDict(
+    "GetWorkflowRunPropertiesResponseTypeDef",
+    {
+        "RunProperties": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetWorkflowRunRequestRequestTypeDef = TypedDict(
     "_RequiredGetWorkflowRunRequestRequestTypeDef",
     {
         "Name": str,
         "RunId": str,
     },
 )
@@ -3881,53 +4462,107 @@
         "NextToken": str,
         "MaxResults": int,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
+ListBlueprintsResponseTypeDef = TypedDict(
+    "ListBlueprintsResponseTypeDef",
+    {
+        "Blueprints": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListCrawlersRequestRequestTypeDef = TypedDict(
     "ListCrawlersRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
+ListCrawlersResponseTypeDef = TypedDict(
+    "ListCrawlersResponseTypeDef",
+    {
+        "CrawlerNames": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListCustomEntityTypesRequestRequestTypeDef = TypedDict(
     "ListCustomEntityTypesRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
+        "Tags": Mapping[str, str],
     },
     total=False,
 )
 
 ListDevEndpointsRequestRequestTypeDef = TypedDict(
     "ListDevEndpointsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
+ListDevEndpointsResponseTypeDef = TypedDict(
+    "ListDevEndpointsResponseTypeDef",
+    {
+        "DevEndpointNames": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListJobsRequestRequestTypeDef = TypedDict(
     "ListJobsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
+ListJobsResponseTypeDef = TypedDict(
+    "ListJobsResponseTypeDef",
+    {
+        "JobNames": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListMLTransformsResponseTypeDef = TypedDict(
+    "ListMLTransformsResponseTypeDef",
+    {
+        "TransformIds": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListRegistriesInputListRegistriesPaginateTypeDef = TypedDict(
+    "ListRegistriesInputListRegistriesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListRegistriesInputRequestTypeDef = TypedDict(
     "ListRegistriesInputRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -4012,23 +4647,41 @@
         "DependentJobName": str,
         "MaxResults": int,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
+ListTriggersResponseTypeDef = TypedDict(
+    "ListTriggersResponseTypeDef",
+    {
+        "TriggerNames": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListWorkflowsRequestRequestTypeDef = TypedDict(
     "ListWorkflowsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListWorkflowsResponseTypeDef = TypedDict(
+    "ListWorkflowsResponseTypeDef",
+    {
+        "Workflows": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredMLUserDataEncryptionTypeDef = TypedDict(
     "_RequiredMLUserDataEncryptionTypeDef",
     {
         "MlUserDataEncryptionMode": MLUserDataEncryptionModeStringType,
     },
 )
 _OptionalMLUserDataEncryptionTypeDef = TypedDict(
@@ -4081,14 +4734,24 @@
     "OrderTypeDef",
     {
         "Column": str,
         "SortOrder": int,
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
 PropertyPredicateTypeDef = TypedDict(
     "PropertyPredicateTypeDef",
     {
         "Key": str,
         "Value": str,
         "Comparator": ComparatorType,
     },
@@ -4115,14 +4778,37 @@
 
 class PutResourcePolicyRequestRequestTypeDef(
     _RequiredPutResourcePolicyRequestRequestTypeDef, _OptionalPutResourcePolicyRequestRequestTypeDef
 ):
     pass
 
 
+PutResourcePolicyResponseTypeDef = TypedDict(
+    "PutResourcePolicyResponseTypeDef",
+    {
+        "PolicyHash": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+PutSchemaVersionMetadataResponseTypeDef = TypedDict(
+    "PutSchemaVersionMetadataResponseTypeDef",
+    {
+        "SchemaArn": str,
+        "SchemaName": str,
+        "RegistryName": str,
+        "LatestVersion": bool,
+        "VersionNumber": int,
+        "SchemaVersionId": str,
+        "MetadataKey": str,
+        "MetadataValue": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 PutWorkflowRunPropertiesRequestRequestTypeDef = TypedDict(
     "PutWorkflowRunPropertiesRequestRequestTypeDef",
     {
         "Name": str,
         "RunId": str,
         "RunProperties": Mapping[str, str],
     },
@@ -4134,14 +4820,39 @@
         "TableLocation": str,
         "ConnectionName": str,
         "UpsertKeys": List[str],
     },
     total=False,
 )
 
+RegisterSchemaVersionResponseTypeDef = TypedDict(
+    "RegisterSchemaVersionResponseTypeDef",
+    {
+        "SchemaVersionId": str,
+        "VersionNumber": int,
+        "Status": SchemaVersionStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+RemoveSchemaVersionMetadataResponseTypeDef = TypedDict(
+    "RemoveSchemaVersionMetadataResponseTypeDef",
+    {
+        "SchemaArn": str,
+        "SchemaName": str,
+        "RegistryName": str,
+        "LatestVersion": bool,
+        "VersionNumber": int,
+        "SchemaVersionId": str,
+        "MetadataKey": str,
+        "MetadataValue": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredResetJobBookmarkRequestRequestTypeDef = TypedDict(
     "_RequiredResetJobBookmarkRequestRequestTypeDef",
     {
         "JobName": str,
     },
 )
 _OptionalResetJobBookmarkRequestRequestTypeDef = TypedDict(
@@ -4164,23 +4875,43 @@
     {
         "ResourceType": ResourceTypeType,
         "Uri": str,
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
 ResumeWorkflowRunRequestRequestTypeDef = TypedDict(
     "ResumeWorkflowRunRequestRequestTypeDef",
     {
         "Name": str,
         "RunId": str,
         "NodeIds": Sequence[str],
     },
 )
 
+ResumeWorkflowRunResponseTypeDef = TypedDict(
+    "ResumeWorkflowRunResponseTypeDef",
+    {
+        "RunId": str,
+        "NodeIds": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredRunStatementRequestRequestTypeDef = TypedDict(
     "_RequiredRunStatementRequestRequestTypeDef",
     {
         "SessionId": str,
         "Code": str,
     },
 )
@@ -4195,14 +4926,22 @@
 
 class RunStatementRequestRequestTypeDef(
     _RequiredRunStatementRequestRequestTypeDef, _OptionalRunStatementRequestRequestTypeDef
 ):
     pass
 
 
+RunStatementResponseTypeDef = TypedDict(
+    "RunStatementResponseTypeDef",
+    {
+        "Id": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 S3DirectSourceAdditionalOptionsTypeDef = TypedDict(
     "S3DirectSourceAdditionalOptionsTypeDef",
     {
         "BoundedSize": int,
         "BoundedFiles": int,
         "EnableSamplePath": bool,
         "SamplePath": str,
@@ -4265,36 +5004,68 @@
 
 class StartBlueprintRunRequestRequestTypeDef(
     _RequiredStartBlueprintRunRequestRequestTypeDef, _OptionalStartBlueprintRunRequestRequestTypeDef
 ):
     pass
 
 
+StartBlueprintRunResponseTypeDef = TypedDict(
+    "StartBlueprintRunResponseTypeDef",
+    {
+        "RunId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartCrawlerRequestRequestTypeDef = TypedDict(
     "StartCrawlerRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
 StartCrawlerScheduleRequestRequestTypeDef = TypedDict(
     "StartCrawlerScheduleRequestRequestTypeDef",
     {
         "CrawlerName": str,
     },
 )
 
+StartDataQualityRuleRecommendationRunResponseTypeDef = TypedDict(
+    "StartDataQualityRuleRecommendationRunResponseTypeDef",
+    {
+        "RunId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartDataQualityRulesetEvaluationRunResponseTypeDef = TypedDict(
+    "StartDataQualityRulesetEvaluationRunResponseTypeDef",
+    {
+        "RunId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartExportLabelsTaskRunRequestRequestTypeDef = TypedDict(
     "StartExportLabelsTaskRunRequestRequestTypeDef",
     {
         "TransformId": str,
         "OutputS3Path": str,
     },
 )
 
+StartExportLabelsTaskRunResponseTypeDef = TypedDict(
+    "StartExportLabelsTaskRunResponseTypeDef",
+    {
+        "TaskRunId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredStartImportLabelsTaskRunRequestRequestTypeDef = TypedDict(
     "_RequiredStartImportLabelsTaskRunRequestRequestTypeDef",
     {
         "TransformId": str,
         "InputS3Path": str,
     },
 )
@@ -4310,36 +5081,76 @@
 class StartImportLabelsTaskRunRequestRequestTypeDef(
     _RequiredStartImportLabelsTaskRunRequestRequestTypeDef,
     _OptionalStartImportLabelsTaskRunRequestRequestTypeDef,
 ):
     pass
 
 
+StartImportLabelsTaskRunResponseTypeDef = TypedDict(
+    "StartImportLabelsTaskRunResponseTypeDef",
+    {
+        "TaskRunId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartJobRunResponseTypeDef = TypedDict(
+    "StartJobRunResponseTypeDef",
+    {
+        "JobRunId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartMLEvaluationTaskRunRequestRequestTypeDef = TypedDict(
     "StartMLEvaluationTaskRunRequestRequestTypeDef",
     {
         "TransformId": str,
     },
 )
 
+StartMLEvaluationTaskRunResponseTypeDef = TypedDict(
+    "StartMLEvaluationTaskRunResponseTypeDef",
+    {
+        "TaskRunId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartMLLabelingSetGenerationTaskRunRequestRequestTypeDef = TypedDict(
     "StartMLLabelingSetGenerationTaskRunRequestRequestTypeDef",
     {
         "TransformId": str,
         "OutputS3Path": str,
     },
 )
 
+StartMLLabelingSetGenerationTaskRunResponseTypeDef = TypedDict(
+    "StartMLLabelingSetGenerationTaskRunResponseTypeDef",
+    {
+        "TaskRunId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartTriggerRequestRequestTypeDef = TypedDict(
     "StartTriggerRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+StartTriggerResponseTypeDef = TypedDict(
+    "StartTriggerResponseTypeDef",
+    {
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredStartWorkflowRunRequestRequestTypeDef = TypedDict(
     "_RequiredStartWorkflowRunRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalStartWorkflowRunRequestRequestTypeDef = TypedDict(
@@ -4353,14 +5164,22 @@
 
 class StartWorkflowRunRequestRequestTypeDef(
     _RequiredStartWorkflowRunRequestRequestTypeDef, _OptionalStartWorkflowRunRequestRequestTypeDef
 ):
     pass
 
 
+StartWorkflowRunResponseTypeDef = TypedDict(
+    "StartWorkflowRunResponseTypeDef",
+    {
+        "RunId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartingEventBatchConditionTypeDef = TypedDict(
     "StartingEventBatchConditionTypeDef",
     {
         "BatchSize": int,
         "BatchWindow": int,
     },
     total=False,
@@ -4405,35 +5224,52 @@
 
 class StopSessionRequestRequestTypeDef(
     _RequiredStopSessionRequestRequestTypeDef, _OptionalStopSessionRequestRequestTypeDef
 ):
     pass
 
 
+StopSessionResponseTypeDef = TypedDict(
+    "StopSessionResponseTypeDef",
+    {
+        "Id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopTriggerRequestRequestTypeDef = TypedDict(
     "StopTriggerRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+StopTriggerResponseTypeDef = TypedDict(
+    "StopTriggerResponseTypeDef",
+    {
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopWorkflowRunRequestRequestTypeDef = TypedDict(
     "StopWorkflowRunRequestRequestTypeDef",
     {
         "Name": str,
         "RunId": str,
     },
 )
 
 TableIdentifierTypeDef = TypedDict(
     "TableIdentifierTypeDef",
     {
         "CatalogId": str,
         "DatabaseName": str,
         "Name": str,
+        "Region": str,
     },
     total=False,
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
@@ -4468,14 +5304,22 @@
 
 class UpdateBlueprintRequestRequestTypeDef(
     _RequiredUpdateBlueprintRequestRequestTypeDef, _OptionalUpdateBlueprintRequestRequestTypeDef
 ):
     pass
 
 
+UpdateBlueprintResponseTypeDef = TypedDict(
+    "UpdateBlueprintResponseTypeDef",
+    {
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateCsvClassifierRequestTypeDef = TypedDict(
     "_RequiredUpdateCsvClassifierRequestTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalUpdateCsvClassifierRequestTypeDef = TypedDict(
@@ -4593,29 +5437,38 @@
     {
         "Name": str,
     },
 )
 _OptionalUpdateDataQualityRulesetRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateDataQualityRulesetRequestRequestTypeDef",
     {
-        "UpdatedName": str,
         "Description": str,
         "Ruleset": str,
     },
     total=False,
 )
 
 
 class UpdateDataQualityRulesetRequestRequestTypeDef(
     _RequiredUpdateDataQualityRulesetRequestRequestTypeDef,
     _OptionalUpdateDataQualityRulesetRequestRequestTypeDef,
 ):
     pass
 
 
+UpdateDataQualityRulesetResponseTypeDef = TypedDict(
+    "UpdateDataQualityRulesetResponseTypeDef",
+    {
+        "Name": str,
+        "Description": str,
+        "Ruleset": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateJobFromSourceControlRequestRequestTypeDef = TypedDict(
     "UpdateJobFromSourceControlRequestRequestTypeDef",
     {
         "JobName": str,
         "Provider": SourceControlProviderType,
         "RepositoryName": str,
         "RepositoryOwner": str,
@@ -4624,14 +5477,57 @@
         "CommitId": str,
         "AuthStrategy": SourceControlAuthStrategyType,
         "AuthToken": str,
     },
     total=False,
 )
 
+UpdateJobFromSourceControlResponseTypeDef = TypedDict(
+    "UpdateJobFromSourceControlResponseTypeDef",
+    {
+        "JobName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateJobResponseTypeDef = TypedDict(
+    "UpdateJobResponseTypeDef",
+    {
+        "JobName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateMLTransformResponseTypeDef = TypedDict(
+    "UpdateMLTransformResponseTypeDef",
+    {
+        "TransformId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateRegistryResponseTypeDef = TypedDict(
+    "UpdateRegistryResponseTypeDef",
+    {
+        "RegistryName": str,
+        "RegistryArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateSchemaResponseTypeDef = TypedDict(
+    "UpdateSchemaResponseTypeDef",
+    {
+        "SchemaArn": str,
+        "SchemaName": str,
+        "RegistryName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateSourceControlFromJobRequestRequestTypeDef = TypedDict(
     "UpdateSourceControlFromJobRequestRequestTypeDef",
     {
         "JobName": str,
         "Provider": SourceControlProviderType,
         "RepositoryName": str,
         "RepositoryOwner": str,
@@ -4640,14 +5536,22 @@
         "CommitId": str,
         "AuthStrategy": SourceControlAuthStrategyType,
         "AuthToken": str,
     },
     total=False,
 )
 
+UpdateSourceControlFromJobResponseTypeDef = TypedDict(
+    "UpdateSourceControlFromJobResponseTypeDef",
+    {
+        "JobName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateWorkflowRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateWorkflowRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalUpdateWorkflowRequestRequestTypeDef = TypedDict(
@@ -4663,14 +5567,22 @@
 
 class UpdateWorkflowRequestRequestTypeDef(
     _RequiredUpdateWorkflowRequestRequestTypeDef, _OptionalUpdateWorkflowRequestRequestTypeDef
 ):
     pass
 
 
+UpdateWorkflowResponseTypeDef = TypedDict(
+    "UpdateWorkflowResponseTypeDef",
+    {
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 WorkflowRunStatisticsTypeDef = TypedDict(
     "WorkflowRunStatisticsTypeDef",
     {
         "TotalActions": int,
         "TimeoutActions": int,
         "FailedActions": int,
         "StoppedActions": int,
@@ -4731,14 +5643,47 @@
         "Name": str,
         "Inputs": List[str],
         "Groups": List[List[str]],
         "Aggs": List[AggregateOperationTypeDef],
     },
 )
 
+AmazonRedshiftNodeDataTypeDef = TypedDict(
+    "AmazonRedshiftNodeDataTypeDef",
+    {
+        "AccessType": str,
+        "SourceType": str,
+        "Connection": OptionTypeDef,
+        "Schema": OptionTypeDef,
+        "Table": OptionTypeDef,
+        "CatalogDatabase": OptionTypeDef,
+        "CatalogTable": OptionTypeDef,
+        "CatalogRedshiftSchema": str,
+        "CatalogRedshiftTable": str,
+        "TempDir": str,
+        "IamRole": OptionTypeDef,
+        "AdvancedOptions": List[AmazonRedshiftAdvancedOptionTypeDef],
+        "SampleQuery": str,
+        "PreAction": str,
+        "PostAction": str,
+        "Action": str,
+        "TablePrefix": str,
+        "Upsert": bool,
+        "MergeAction": str,
+        "MergeWhenMatched": str,
+        "MergeWhenNotMatched": str,
+        "MergeClause": str,
+        "CrawlerConnection": str,
+        "TableSchema": List[OptionTypeDef],
+        "StagingTable": str,
+        "SelectedColumns": List[OptionTypeDef],
+    },
+    total=False,
+)
+
 _RequiredGetUnfilteredPartitionMetadataRequestRequestTypeDef = TypedDict(
     "_RequiredGetUnfilteredPartitionMetadataRequestRequestTypeDef",
     {
         "CatalogId": str,
         "DatabaseName": str,
         "TableName": str,
         "PartitionValues": Sequence[str],
@@ -4838,661 +5783,20 @@
 
 class BatchGetPartitionRequestRequestTypeDef(
     _RequiredBatchGetPartitionRequestRequestTypeDef, _OptionalBatchGetPartitionRequestRequestTypeDef
 ):
     pass
 
 
-CancelMLTaskRunResponseTypeDef = TypedDict(
-    "CancelMLTaskRunResponseTypeDef",
-    {
-        "TransformId": str,
-        "TaskRunId": str,
-        "Status": TaskStatusTypeType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CheckSchemaVersionValidityResponseTypeDef = TypedDict(
-    "CheckSchemaVersionValidityResponseTypeDef",
-    {
-        "Valid": bool,
-        "Error": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateBlueprintResponseTypeDef = TypedDict(
-    "CreateBlueprintResponseTypeDef",
-    {
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateCustomEntityTypeResponseTypeDef = TypedDict(
-    "CreateCustomEntityTypeResponseTypeDef",
-    {
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDataQualityRulesetResponseTypeDef = TypedDict(
-    "CreateDataQualityRulesetResponseTypeDef",
-    {
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDevEndpointResponseTypeDef = TypedDict(
-    "CreateDevEndpointResponseTypeDef",
-    {
-        "EndpointName": str,
-        "Status": str,
-        "SecurityGroupIds": List[str],
-        "SubnetId": str,
-        "RoleArn": str,
-        "YarnEndpointAddress": str,
-        "ZeppelinRemoteSparkInterpreterPort": int,
-        "NumberOfNodes": int,
-        "WorkerType": WorkerTypeType,
-        "GlueVersion": str,
-        "NumberOfWorkers": int,
-        "AvailabilityZone": str,
-        "VpcId": str,
-        "ExtraPythonLibsS3Path": str,
-        "ExtraJarsS3Path": str,
-        "FailureReason": str,
-        "SecurityConfiguration": str,
-        "CreatedTimestamp": datetime,
-        "Arguments": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateJobResponseTypeDef = TypedDict(
-    "CreateJobResponseTypeDef",
-    {
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateMLTransformResponseTypeDef = TypedDict(
-    "CreateMLTransformResponseTypeDef",
-    {
-        "TransformId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateRegistryResponseTypeDef = TypedDict(
-    "CreateRegistryResponseTypeDef",
-    {
-        "RegistryArn": str,
-        "RegistryName": str,
-        "Description": str,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateSchemaResponseTypeDef = TypedDict(
-    "CreateSchemaResponseTypeDef",
-    {
-        "RegistryName": str,
-        "RegistryArn": str,
-        "SchemaName": str,
-        "SchemaArn": str,
-        "Description": str,
-        "DataFormat": DataFormatType,
-        "Compatibility": CompatibilityType,
-        "SchemaCheckpoint": int,
-        "LatestSchemaVersion": int,
-        "NextSchemaVersion": int,
-        "SchemaStatus": SchemaStatusType,
-        "Tags": Dict[str, str],
-        "SchemaVersionId": str,
-        "SchemaVersionStatus": SchemaVersionStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateScriptResponseTypeDef = TypedDict(
-    "CreateScriptResponseTypeDef",
-    {
-        "PythonScript": str,
-        "ScalaCode": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateSecurityConfigurationResponseTypeDef = TypedDict(
-    "CreateSecurityConfigurationResponseTypeDef",
-    {
-        "Name": str,
-        "CreatedTimestamp": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateTriggerResponseTypeDef = TypedDict(
-    "CreateTriggerResponseTypeDef",
-    {
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateWorkflowResponseTypeDef = TypedDict(
-    "CreateWorkflowResponseTypeDef",
-    {
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteBlueprintResponseTypeDef = TypedDict(
-    "DeleteBlueprintResponseTypeDef",
-    {
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteCustomEntityTypeResponseTypeDef = TypedDict(
-    "DeleteCustomEntityTypeResponseTypeDef",
-    {
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteJobResponseTypeDef = TypedDict(
-    "DeleteJobResponseTypeDef",
-    {
-        "JobName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteMLTransformResponseTypeDef = TypedDict(
-    "DeleteMLTransformResponseTypeDef",
-    {
-        "TransformId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteRegistryResponseTypeDef = TypedDict(
-    "DeleteRegistryResponseTypeDef",
-    {
-        "RegistryName": str,
-        "RegistryArn": str,
-        "Status": RegistryStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteSchemaResponseTypeDef = TypedDict(
-    "DeleteSchemaResponseTypeDef",
-    {
-        "SchemaArn": str,
-        "SchemaName": str,
-        "Status": SchemaStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteSessionResponseTypeDef = TypedDict(
-    "DeleteSessionResponseTypeDef",
-    {
-        "Id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteTriggerResponseTypeDef = TypedDict(
-    "DeleteTriggerResponseTypeDef",
-    {
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteWorkflowResponseTypeDef = TypedDict(
-    "DeleteWorkflowResponseTypeDef",
-    {
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetCustomEntityTypeResponseTypeDef = TypedDict(
-    "GetCustomEntityTypeResponseTypeDef",
-    {
-        "Name": str,
-        "RegexString": str,
-        "ContextWords": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetPlanResponseTypeDef = TypedDict(
-    "GetPlanResponseTypeDef",
-    {
-        "PythonScript": str,
-        "ScalaCode": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetRegistryResponseTypeDef = TypedDict(
-    "GetRegistryResponseTypeDef",
-    {
-        "RegistryName": str,
-        "RegistryArn": str,
-        "Description": str,
-        "Status": RegistryStatusType,
-        "CreatedTime": str,
-        "UpdatedTime": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetResourcePolicyResponseTypeDef = TypedDict(
-    "GetResourcePolicyResponseTypeDef",
-    {
-        "PolicyInJson": str,
-        "PolicyHash": str,
-        "CreateTime": datetime,
-        "UpdateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSchemaByDefinitionResponseTypeDef = TypedDict(
-    "GetSchemaByDefinitionResponseTypeDef",
-    {
-        "SchemaVersionId": str,
-        "SchemaArn": str,
-        "DataFormat": DataFormatType,
-        "Status": SchemaVersionStatusType,
-        "CreatedTime": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSchemaResponseTypeDef = TypedDict(
-    "GetSchemaResponseTypeDef",
-    {
-        "RegistryName": str,
-        "RegistryArn": str,
-        "SchemaName": str,
-        "SchemaArn": str,
-        "Description": str,
-        "DataFormat": DataFormatType,
-        "Compatibility": CompatibilityType,
-        "SchemaCheckpoint": int,
-        "LatestSchemaVersion": int,
-        "NextSchemaVersion": int,
-        "SchemaStatus": SchemaStatusType,
-        "CreatedTime": str,
-        "UpdatedTime": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSchemaVersionResponseTypeDef = TypedDict(
-    "GetSchemaVersionResponseTypeDef",
-    {
-        "SchemaVersionId": str,
-        "SchemaDefinition": str,
-        "DataFormat": DataFormatType,
-        "SchemaArn": str,
-        "VersionNumber": int,
-        "Status": SchemaVersionStatusType,
-        "CreatedTime": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSchemaVersionsDiffResponseTypeDef = TypedDict(
-    "GetSchemaVersionsDiffResponseTypeDef",
-    {
-        "Diff": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetTagsResponseTypeDef = TypedDict(
-    "GetTagsResponseTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetWorkflowRunPropertiesResponseTypeDef = TypedDict(
-    "GetWorkflowRunPropertiesResponseTypeDef",
-    {
-        "RunProperties": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListBlueprintsResponseTypeDef = TypedDict(
-    "ListBlueprintsResponseTypeDef",
-    {
-        "Blueprints": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListCrawlersResponseTypeDef = TypedDict(
-    "ListCrawlersResponseTypeDef",
-    {
-        "CrawlerNames": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDevEndpointsResponseTypeDef = TypedDict(
-    "ListDevEndpointsResponseTypeDef",
-    {
-        "DevEndpointNames": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListJobsResponseTypeDef = TypedDict(
-    "ListJobsResponseTypeDef",
-    {
-        "JobNames": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListMLTransformsResponseTypeDef = TypedDict(
-    "ListMLTransformsResponseTypeDef",
-    {
-        "TransformIds": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTriggersResponseTypeDef = TypedDict(
-    "ListTriggersResponseTypeDef",
-    {
-        "TriggerNames": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListWorkflowsResponseTypeDef = TypedDict(
-    "ListWorkflowsResponseTypeDef",
-    {
-        "Workflows": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutResourcePolicyResponseTypeDef = TypedDict(
-    "PutResourcePolicyResponseTypeDef",
-    {
-        "PolicyHash": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutSchemaVersionMetadataResponseTypeDef = TypedDict(
-    "PutSchemaVersionMetadataResponseTypeDef",
-    {
-        "SchemaArn": str,
-        "SchemaName": str,
-        "RegistryName": str,
-        "LatestVersion": bool,
-        "VersionNumber": int,
-        "SchemaVersionId": str,
-        "MetadataKey": str,
-        "MetadataValue": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RegisterSchemaVersionResponseTypeDef = TypedDict(
-    "RegisterSchemaVersionResponseTypeDef",
-    {
-        "SchemaVersionId": str,
-        "VersionNumber": int,
-        "Status": SchemaVersionStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RemoveSchemaVersionMetadataResponseTypeDef = TypedDict(
-    "RemoveSchemaVersionMetadataResponseTypeDef",
-    {
-        "SchemaArn": str,
-        "SchemaName": str,
-        "RegistryName": str,
-        "LatestVersion": bool,
-        "VersionNumber": int,
-        "SchemaVersionId": str,
-        "MetadataKey": str,
-        "MetadataValue": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ResumeWorkflowRunResponseTypeDef = TypedDict(
-    "ResumeWorkflowRunResponseTypeDef",
-    {
-        "RunId": str,
-        "NodeIds": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RunStatementResponseTypeDef = TypedDict(
-    "RunStatementResponseTypeDef",
-    {
-        "Id": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartBlueprintRunResponseTypeDef = TypedDict(
-    "StartBlueprintRunResponseTypeDef",
-    {
-        "RunId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartDataQualityRuleRecommendationRunResponseTypeDef = TypedDict(
-    "StartDataQualityRuleRecommendationRunResponseTypeDef",
-    {
-        "RunId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartDataQualityRulesetEvaluationRunResponseTypeDef = TypedDict(
-    "StartDataQualityRulesetEvaluationRunResponseTypeDef",
-    {
-        "RunId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartExportLabelsTaskRunResponseTypeDef = TypedDict(
-    "StartExportLabelsTaskRunResponseTypeDef",
-    {
-        "TaskRunId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartImportLabelsTaskRunResponseTypeDef = TypedDict(
-    "StartImportLabelsTaskRunResponseTypeDef",
-    {
-        "TaskRunId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartJobRunResponseTypeDef = TypedDict(
-    "StartJobRunResponseTypeDef",
-    {
-        "JobRunId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartMLEvaluationTaskRunResponseTypeDef = TypedDict(
-    "StartMLEvaluationTaskRunResponseTypeDef",
-    {
-        "TaskRunId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartMLLabelingSetGenerationTaskRunResponseTypeDef = TypedDict(
-    "StartMLLabelingSetGenerationTaskRunResponseTypeDef",
-    {
-        "TaskRunId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartTriggerResponseTypeDef = TypedDict(
-    "StartTriggerResponseTypeDef",
-    {
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartWorkflowRunResponseTypeDef = TypedDict(
-    "StartWorkflowRunResponseTypeDef",
-    {
-        "RunId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StopSessionResponseTypeDef = TypedDict(
-    "StopSessionResponseTypeDef",
-    {
-        "Id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StopTriggerResponseTypeDef = TypedDict(
-    "StopTriggerResponseTypeDef",
-    {
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateBlueprintResponseTypeDef = TypedDict(
-    "UpdateBlueprintResponseTypeDef",
-    {
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateDataQualityRulesetResponseTypeDef = TypedDict(
-    "UpdateDataQualityRulesetResponseTypeDef",
-    {
-        "Name": str,
-        "Description": str,
-        "Ruleset": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateJobFromSourceControlResponseTypeDef = TypedDict(
-    "UpdateJobFromSourceControlResponseTypeDef",
-    {
-        "JobName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateJobResponseTypeDef = TypedDict(
-    "UpdateJobResponseTypeDef",
-    {
-        "JobName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateMLTransformResponseTypeDef = TypedDict(
-    "UpdateMLTransformResponseTypeDef",
-    {
-        "TransformId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateRegistryResponseTypeDef = TypedDict(
-    "UpdateRegistryResponseTypeDef",
-    {
-        "RegistryName": str,
-        "RegistryArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateSchemaResponseTypeDef = TypedDict(
-    "UpdateSchemaResponseTypeDef",
-    {
-        "SchemaArn": str,
-        "SchemaName": str,
-        "RegistryName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateSourceControlFromJobResponseTypeDef = TypedDict(
-    "UpdateSourceControlFromJobResponseTypeDef",
-    {
-        "JobName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateWorkflowResponseTypeDef = TypedDict(
-    "UpdateWorkflowResponseTypeDef",
-    {
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 BatchDeleteConnectionResponseTypeDef = TypedDict(
     "BatchDeleteConnectionResponseTypeDef",
     {
         "Succeeded": List[str],
         "Errors": Dict[str, ErrorDetailTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchStopJobRunErrorTypeDef = TypedDict(
     "BatchStopJobRunErrorTypeDef",
     {
         "JobName": str,
@@ -5549,67 +5853,67 @@
 )
 
 BatchGetCustomEntityTypesResponseTypeDef = TypedDict(
     "BatchGetCustomEntityTypesResponseTypeDef",
     {
         "CustomEntityTypes": List[CustomEntityTypeTypeDef],
         "CustomEntityTypesNotFound": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCustomEntityTypesResponseTypeDef = TypedDict(
     "ListCustomEntityTypesResponseTypeDef",
     {
         "CustomEntityTypes": List[CustomEntityTypeTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetDevEndpointsResponseTypeDef = TypedDict(
     "BatchGetDevEndpointsResponseTypeDef",
     {
         "DevEndpoints": List[DevEndpointTypeDef],
         "DevEndpointsNotFound": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDevEndpointResponseTypeDef = TypedDict(
     "GetDevEndpointResponseTypeDef",
     {
         "DevEndpoint": DevEndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDevEndpointsResponseTypeDef = TypedDict(
     "GetDevEndpointsResponseTypeDef",
     {
         "DevEndpoints": List[DevEndpointTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetBlueprintRunResponseTypeDef = TypedDict(
     "GetBlueprintRunResponseTypeDef",
     {
         "BlueprintRun": BlueprintRunTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetBlueprintRunsResponseTypeDef = TypedDict(
     "GetBlueprintRunsResponseTypeDef",
     {
         "BlueprintRuns": List[BlueprintRunTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BlueprintTypeDef = TypedDict(
     "BlueprintTypeDef",
     {
         "Name": str,
@@ -5626,15 +5930,15 @@
     total=False,
 )
 
 GetCatalogImportStatusResponseTypeDef = TypedDict(
     "GetCatalogImportStatusResponseTypeDef",
     {
         "ImportStatus": CatalogImportStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCatalogKafkaSourceTypeDef = TypedDict(
     "_RequiredCatalogKafkaSourceTypeDef",
     {
         "Name": str,
@@ -5946,24 +6250,24 @@
 )
 
 ListCrawlsResponseTypeDef = TypedDict(
     "ListCrawlsResponseTypeDef",
     {
         "Crawls": List[CrawlerHistoryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCrawlerMetricsResponseTypeDef = TypedDict(
     "GetCrawlerMetricsResponseTypeDef",
     {
         "CrawlerMetricsList": List[CrawlerMetricsTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CrawlerTargetsTypeDef = TypedDict(
     "CrawlerTargetsTypeDef",
     {
         "S3Targets": List[S3TargetTypeDef],
@@ -6070,15 +6374,15 @@
         "Name": str,
         "Description": str,
         "Ruleset": str,
         "TargetTable": DataQualityTargetTableTypeDef,
         "CreatedOn": datetime,
         "LastModifiedOn": datetime,
         "RecommendationRunId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DataSourceTypeDef = TypedDict(
     "DataSourceTypeDef",
     {
         "GlueTable": GlueTableTypeDef,
@@ -6145,14 +6449,23 @@
 GetRegistryInputRequestTypeDef = TypedDict(
     "GetRegistryInputRequestTypeDef",
     {
         "RegistryId": RegistryIdTypeDef,
     },
 )
 
+ListSchemasInputListSchemasPaginateTypeDef = TypedDict(
+    "ListSchemasInputListSchemasPaginateTypeDef",
+    {
+        "RegistryId": RegistryIdTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSchemasInputRequestTypeDef = TypedDict(
     "ListSchemasInputRequestTypeDef",
     {
         "RegistryId": RegistryIdTypeDef,
         "MaxResults": int,
         "NextToken": str,
     },
@@ -6217,14 +6530,40 @@
         "MaxCapacity": float,
         "SecurityConfiguration": str,
         "GlueVersion": str,
     },
     total=False,
 )
 
+_RequiredEvaluateDataQualityMultiFrameTypeDef = TypedDict(
+    "_RequiredEvaluateDataQualityMultiFrameTypeDef",
+    {
+        "Name": str,
+        "Inputs": List[str],
+        "Ruleset": str,
+    },
+)
+_OptionalEvaluateDataQualityMultiFrameTypeDef = TypedDict(
+    "_OptionalEvaluateDataQualityMultiFrameTypeDef",
+    {
+        "AdditionalDataSources": Dict[str, str],
+        "PublishingOptions": DQResultsPublishingOptionsTypeDef,
+        "AdditionalOptions": Dict[Literal["performanceTuning.caching"], str],
+        "StopJobOnFailureOptions": DQStopJobOnFailureOptionsTypeDef,
+    },
+    total=False,
+)
+
+
+class EvaluateDataQualityMultiFrameTypeDef(
+    _RequiredEvaluateDataQualityMultiFrameTypeDef, _OptionalEvaluateDataQualityMultiFrameTypeDef
+):
+    pass
+
+
 _RequiredEvaluateDataQualityTypeDef = TypedDict(
     "_RequiredEvaluateDataQualityTypeDef",
     {
         "Name": str,
         "Inputs": List[str],
         "Ruleset": str,
     },
@@ -6321,14 +6660,36 @@
 GetSchemaInputRequestTypeDef = TypedDict(
     "GetSchemaInputRequestTypeDef",
     {
         "SchemaId": SchemaIdTypeDef,
     },
 )
 
+_RequiredListSchemaVersionsInputListSchemaVersionsPaginateTypeDef = TypedDict(
+    "_RequiredListSchemaVersionsInputListSchemaVersionsPaginateTypeDef",
+    {
+        "SchemaId": SchemaIdTypeDef,
+    },
+)
+_OptionalListSchemaVersionsInputListSchemaVersionsPaginateTypeDef = TypedDict(
+    "_OptionalListSchemaVersionsInputListSchemaVersionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListSchemaVersionsInputListSchemaVersionsPaginateTypeDef(
+    _RequiredListSchemaVersionsInputListSchemaVersionsPaginateTypeDef,
+    _OptionalListSchemaVersionsInputListSchemaVersionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListSchemaVersionsInputRequestTypeDef = TypedDict(
     "_RequiredListSchemaVersionsInputRequestTypeDef",
     {
         "SchemaId": SchemaIdTypeDef,
     },
 )
 _OptionalListSchemaVersionsInputRequestTypeDef = TypedDict(
@@ -6491,38 +6852,14 @@
 
 class S3HudiDirectTargetTypeDef(
     _RequiredS3HudiDirectTargetTypeDef, _OptionalS3HudiDirectTargetTypeDef
 ):
     pass
 
 
-_RequiredDynamicTransformTypeDef = TypedDict(
-    "_RequiredDynamicTransformTypeDef",
-    {
-        "Name": str,
-        "TransformName": str,
-        "Inputs": List[str],
-        "FunctionName": str,
-        "Path": str,
-    },
-)
-_OptionalDynamicTransformTypeDef = TypedDict(
-    "_OptionalDynamicTransformTypeDef",
-    {
-        "Parameters": List[TransformConfigParameterTypeDef],
-        "Version": str,
-    },
-    total=False,
-)
-
-
-class DynamicTransformTypeDef(_RequiredDynamicTransformTypeDef, _OptionalDynamicTransformTypeDef):
-    pass
-
-
 EncryptionConfigurationTypeDef = TypedDict(
     "EncryptionConfigurationTypeDef",
     {
         "S3Encryption": Sequence[S3EncryptionTypeDef],
         "CloudWatchEncryption": CloudWatchEncryptionTypeDef,
         "JobBookmarksEncryption": JobBookmarksEncryptionTypeDef,
     },
@@ -6575,256 +6912,21 @@
 
 class TransformParametersTypeDef(
     _RequiredTransformParametersTypeDef, _OptionalTransformParametersTypeDef
 ):
     pass
 
 
-GetClassifiersRequestGetClassifiersPaginateTypeDef = TypedDict(
-    "GetClassifiersRequestGetClassifiersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetCrawlerMetricsRequestGetCrawlerMetricsPaginateTypeDef = TypedDict(
-    "GetCrawlerMetricsRequestGetCrawlerMetricsPaginateTypeDef",
-    {
-        "CrawlerNameList": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetCrawlersRequestGetCrawlersPaginateTypeDef = TypedDict(
-    "GetCrawlersRequestGetCrawlersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetDatabasesRequestGetDatabasesPaginateTypeDef = TypedDict(
-    "GetDatabasesRequestGetDatabasesPaginateTypeDef",
-    {
-        "CatalogId": str,
-        "ResourceShareType": ResourceShareTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetDevEndpointsRequestGetDevEndpointsPaginateTypeDef = TypedDict(
-    "GetDevEndpointsRequestGetDevEndpointsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredGetJobRunsRequestGetJobRunsPaginateTypeDef = TypedDict(
-    "_RequiredGetJobRunsRequestGetJobRunsPaginateTypeDef",
-    {
-        "JobName": str,
-    },
-)
-_OptionalGetJobRunsRequestGetJobRunsPaginateTypeDef = TypedDict(
-    "_OptionalGetJobRunsRequestGetJobRunsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetJobRunsRequestGetJobRunsPaginateTypeDef(
-    _RequiredGetJobRunsRequestGetJobRunsPaginateTypeDef,
-    _OptionalGetJobRunsRequestGetJobRunsPaginateTypeDef,
-):
-    pass
-
-
-GetJobsRequestGetJobsPaginateTypeDef = TypedDict(
-    "GetJobsRequestGetJobsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredGetPartitionIndexesRequestGetPartitionIndexesPaginateTypeDef = TypedDict(
-    "_RequiredGetPartitionIndexesRequestGetPartitionIndexesPaginateTypeDef",
-    {
-        "DatabaseName": str,
-        "TableName": str,
-    },
-)
-_OptionalGetPartitionIndexesRequestGetPartitionIndexesPaginateTypeDef = TypedDict(
-    "_OptionalGetPartitionIndexesRequestGetPartitionIndexesPaginateTypeDef",
-    {
-        "CatalogId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetPartitionIndexesRequestGetPartitionIndexesPaginateTypeDef(
-    _RequiredGetPartitionIndexesRequestGetPartitionIndexesPaginateTypeDef,
-    _OptionalGetPartitionIndexesRequestGetPartitionIndexesPaginateTypeDef,
-):
-    pass
-
-
-GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef = TypedDict(
-    "GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetSecurityConfigurationsRequestGetSecurityConfigurationsPaginateTypeDef = TypedDict(
-    "GetSecurityConfigurationsRequestGetSecurityConfigurationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredGetTableVersionsRequestGetTableVersionsPaginateTypeDef = TypedDict(
-    "_RequiredGetTableVersionsRequestGetTableVersionsPaginateTypeDef",
-    {
-        "DatabaseName": str,
-        "TableName": str,
-    },
-)
-_OptionalGetTableVersionsRequestGetTableVersionsPaginateTypeDef = TypedDict(
-    "_OptionalGetTableVersionsRequestGetTableVersionsPaginateTypeDef",
-    {
-        "CatalogId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetTableVersionsRequestGetTableVersionsPaginateTypeDef(
-    _RequiredGetTableVersionsRequestGetTableVersionsPaginateTypeDef,
-    _OptionalGetTableVersionsRequestGetTableVersionsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredGetTablesRequestGetTablesPaginateTypeDef = TypedDict(
-    "_RequiredGetTablesRequestGetTablesPaginateTypeDef",
-    {
-        "DatabaseName": str,
-    },
-)
-_OptionalGetTablesRequestGetTablesPaginateTypeDef = TypedDict(
-    "_OptionalGetTablesRequestGetTablesPaginateTypeDef",
-    {
-        "CatalogId": str,
-        "Expression": str,
-        "TransactionId": str,
-        "QueryAsOfTime": Union[datetime, str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetTablesRequestGetTablesPaginateTypeDef(
-    _RequiredGetTablesRequestGetTablesPaginateTypeDef,
-    _OptionalGetTablesRequestGetTablesPaginateTypeDef,
-):
-    pass
-
-
-GetTriggersRequestGetTriggersPaginateTypeDef = TypedDict(
-    "GetTriggersRequestGetTriggersPaginateTypeDef",
-    {
-        "DependentJobName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredGetUserDefinedFunctionsRequestGetUserDefinedFunctionsPaginateTypeDef = TypedDict(
-    "_RequiredGetUserDefinedFunctionsRequestGetUserDefinedFunctionsPaginateTypeDef",
-    {
-        "Pattern": str,
-    },
-)
-_OptionalGetUserDefinedFunctionsRequestGetUserDefinedFunctionsPaginateTypeDef = TypedDict(
-    "_OptionalGetUserDefinedFunctionsRequestGetUserDefinedFunctionsPaginateTypeDef",
-    {
-        "CatalogId": str,
-        "DatabaseName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetUserDefinedFunctionsRequestGetUserDefinedFunctionsPaginateTypeDef(
-    _RequiredGetUserDefinedFunctionsRequestGetUserDefinedFunctionsPaginateTypeDef,
-    _OptionalGetUserDefinedFunctionsRequestGetUserDefinedFunctionsPaginateTypeDef,
-):
-    pass
-
-
-ListRegistriesInputListRegistriesPaginateTypeDef = TypedDict(
-    "ListRegistriesInputListRegistriesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListSchemaVersionsInputListSchemaVersionsPaginateTypeDef = TypedDict(
-    "_RequiredListSchemaVersionsInputListSchemaVersionsPaginateTypeDef",
-    {
-        "SchemaId": SchemaIdTypeDef,
-    },
-)
-_OptionalListSchemaVersionsInputListSchemaVersionsPaginateTypeDef = TypedDict(
-    "_OptionalListSchemaVersionsInputListSchemaVersionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListSchemaVersionsInputListSchemaVersionsPaginateTypeDef(
-    _RequiredListSchemaVersionsInputListSchemaVersionsPaginateTypeDef,
-    _OptionalListSchemaVersionsInputListSchemaVersionsPaginateTypeDef,
-):
-    pass
-
-
-ListSchemasInputListSchemasPaginateTypeDef = TypedDict(
-    "ListSchemasInputListSchemasPaginateTypeDef",
-    {
-        "RegistryId": RegistryIdTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 GetConnectionsRequestGetConnectionsPaginateTypeDef = TypedDict(
     "GetConnectionsRequestGetConnectionsPaginateTypeDef",
     {
         "CatalogId": str,
         "Filter": GetConnectionsFilterTypeDef,
         "HidePassword": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 GetConnectionsRequestRequestTypeDef = TypedDict(
     "GetConnectionsRequestRequestTypeDef",
     {
@@ -6837,23 +6939,23 @@
     total=False,
 )
 
 GetJobBookmarkResponseTypeDef = TypedDict(
     "GetJobBookmarkResponseTypeDef",
     {
         "JobBookmarkEntry": JobBookmarkEntryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResetJobBookmarkResponseTypeDef = TypedDict(
     "ResetJobBookmarkResponseTypeDef",
     {
         "JobBookmarkEntry": JobBookmarkEntryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetMLTaskRunsRequestRequestTypeDef = TypedDict(
     "_RequiredGetMLTaskRunsRequestRequestTypeDef",
     {
         "TransformId": str,
@@ -6893,15 +6995,15 @@
     total=False,
 )
 
 GetMappingResponseTypeDef = TypedDict(
     "GetMappingResponseTypeDef",
     {
         "Mapping": List[MappingEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetPartitionsRequestGetPartitionsPaginateTypeDef = TypedDict(
     "_RequiredGetPartitionsRequestGetPartitionsPaginateTypeDef",
     {
         "DatabaseName": str,
@@ -6913,15 +7015,15 @@
     {
         "CatalogId": str,
         "Expression": str,
         "Segment": SegmentTypeDef,
         "ExcludeColumnSchema": bool,
         "TransactionId": str,
         "QueryAsOfTime": Union[datetime, str],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 
 class GetPartitionsRequestGetPartitionsPaginateTypeDef(
     _RequiredGetPartitionsRequestGetPartitionsPaginateTypeDef,
@@ -6989,15 +7091,15 @@
 
 
 GetResourcePoliciesResponseTypeDef = TypedDict(
     "GetResourcePoliciesResponseTypeDef",
     {
         "GetResourcePoliciesResponseList": List[GluePolicyTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSchemaVersionInputRequestTypeDef = TypedDict(
     "GetSchemaVersionInputRequestTypeDef",
     {
         "SchemaId": SchemaIdTypeDef,
@@ -7148,33 +7250,33 @@
 )
 
 ListRegistriesResponseTypeDef = TypedDict(
     "ListRegistriesResponseTypeDef",
     {
         "Registries": List[RegistryListItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSchemaVersionsResponseTypeDef = TypedDict(
     "ListSchemaVersionsResponseTypeDef",
     {
         "Schemas": List[SchemaVersionListItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSchemasResponseTypeDef = TypedDict(
     "ListSchemasResponseTypeDef",
     {
         "Schemas": List[SchemaListItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TransformEncryptionTypeDef = TypedDict(
     "TransformEncryptionTypeDef",
     {
         "MlUserDataEncryption": MLUserDataEncryptionTypeDef,
@@ -7339,14 +7441,33 @@
         "XMLClassifier": UpdateXMLClassifierRequestTypeDef,
         "JsonClassifier": UpdateJsonClassifierRequestTypeDef,
         "CsvClassifier": UpdateCsvClassifierRequestTypeDef,
     },
     total=False,
 )
 
+AmazonRedshiftSourceTypeDef = TypedDict(
+    "AmazonRedshiftSourceTypeDef",
+    {
+        "Name": str,
+        "Data": AmazonRedshiftNodeDataTypeDef,
+    },
+    total=False,
+)
+
+AmazonRedshiftTargetTypeDef = TypedDict(
+    "AmazonRedshiftTargetTypeDef",
+    {
+        "Name": str,
+        "Data": AmazonRedshiftNodeDataTypeDef,
+        "Inputs": List[str],
+    },
+    total=False,
+)
+
 _RequiredPartitionIndexDescriptorTypeDef = TypedDict(
     "_RequiredPartitionIndexDescriptorTypeDef",
     {
         "IndexName": str,
         "Keys": List[KeySchemaElementTypeDef],
         "IndexStatus": PartitionIndexStatusType,
     },
@@ -7367,89 +7488,89 @@
 
 
 BatchStopJobRunResponseTypeDef = TypedDict(
     "BatchStopJobRunResponseTypeDef",
     {
         "SuccessfulSubmissions": List[BatchStopJobRunSuccessfulSubmissionTypeDef],
         "Errors": List[BatchStopJobRunErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchUpdatePartitionResponseTypeDef = TypedDict(
     "BatchUpdatePartitionResponseTypeDef",
     {
         "Errors": List[BatchUpdatePartitionFailureEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchCreatePartitionResponseTypeDef = TypedDict(
     "BatchCreatePartitionResponseTypeDef",
     {
         "Errors": List[PartitionErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDeletePartitionResponseTypeDef = TypedDict(
     "BatchDeletePartitionResponseTypeDef",
     {
         "Errors": List[PartitionErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDeleteTableResponseTypeDef = TypedDict(
     "BatchDeleteTableResponseTypeDef",
     {
         "Errors": List[TableErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDeleteTableVersionResponseTypeDef = TypedDict(
     "BatchDeleteTableVersionResponseTypeDef",
     {
         "Errors": List[TableVersionErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetBlueprintsResponseTypeDef = TypedDict(
     "BatchGetBlueprintsResponseTypeDef",
     {
         "Blueprints": List[BlueprintTypeDef],
         "MissingBlueprints": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetBlueprintResponseTypeDef = TypedDict(
     "GetBlueprintResponseTypeDef",
     {
         "Blueprint": BlueprintTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetClassifierResponseTypeDef = TypedDict(
     "GetClassifierResponseTypeDef",
     {
         "Classifier": ClassifierTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetClassifiersResponseTypeDef = TypedDict(
     "GetClassifiersResponseTypeDef",
     {
         "Classifiers": List[ClassifierTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateScriptRequestRequestTypeDef = TypedDict(
     "CreateScriptRequestRequestTypeDef",
     {
         "DagNodes": Sequence[CodeGenNodeTypeDef],
@@ -7460,15 +7581,15 @@
 )
 
 GetDataflowGraphResponseTypeDef = TypedDict(
     "GetDataflowGraphResponseTypeDef",
     {
         "DagNodes": List[CodeGenNodeTypeDef],
         "DagEdges": List[CodeGenEdgeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetMappingRequestRequestTypeDef = TypedDict(
     "_RequiredGetMappingRequestRequestTypeDef",
     {
         "Source": CatalogEntryTypeDef,
@@ -7639,24 +7760,24 @@
     pass
 
 
 GetConnectionResponseTypeDef = TypedDict(
     "GetConnectionResponseTypeDef",
     {
         "Connection": ConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetConnectionsResponseTypeDef = TypedDict(
     "GetConnectionsResponseTypeDef",
     {
         "ConnectionList": List[ConnectionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CrawlerTypeDef = TypedDict(
     "CrawlerTypeDef",
     {
         "Name": str,
@@ -7762,15 +7883,15 @@
 )
 
 ListDataQualityRulesetsResponseTypeDef = TypedDict(
     "ListDataQualityRulesetsResponseTypeDef",
     {
         "Rulesets": List[DataQualityRulesetListDetailsTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DataQualityResultDescriptionTypeDef = TypedDict(
     "DataQualityResultDescriptionTypeDef",
     {
         "ResultId": str,
@@ -7890,15 +8011,15 @@
         "EvaluationContext": str,
         "StartedOn": datetime,
         "CompletedOn": datetime,
         "JobName": str,
         "JobRunId": str,
         "RulesetEvaluationRunId": str,
         "RuleResults": List[DataQualityRuleResultTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDataQualityRuleRecommendationRunResponseTypeDef = TypedDict(
     "GetDataQualityRuleRecommendationRunResponseTypeDef",
     {
         "RunId": str,
@@ -7910,15 +8031,15 @@
         "ErrorString": str,
         "StartedOn": datetime,
         "LastModifiedOn": datetime,
         "CompletedOn": datetime,
         "ExecutionTime": int,
         "RecommendedRuleset": str,
         "CreatedRulesetName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDataQualityRulesetEvaluationRunResponseTypeDef = TypedDict(
     "GetDataQualityRulesetEvaluationRunResponseTypeDef",
     {
         "RunId": str,
@@ -7931,15 +8052,16 @@
         "ErrorString": str,
         "StartedOn": datetime,
         "LastModifiedOn": datetime,
         "CompletedOn": datetime,
         "ExecutionTime": int,
         "RulesetNames": List[str],
         "ResultIds": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "AdditionalDataSources": Dict[str, DataSourceTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStartDataQualityRuleRecommendationRunRequestRequestTypeDef = TypedDict(
     "_RequiredStartDataQualityRuleRecommendationRunRequestRequestTypeDef",
     {
         "DataSource": DataSourceTypeDef,
@@ -7976,14 +8098,15 @@
 _OptionalStartDataQualityRulesetEvaluationRunRequestRequestTypeDef = TypedDict(
     "_OptionalStartDataQualityRulesetEvaluationRunRequestRequestTypeDef",
     {
         "NumberOfWorkers": int,
         "Timeout": int,
         "ClientToken": str,
         "AdditionalRunOptions": DataQualityEvaluationRunAdditionalRunOptionsTypeDef,
+        "AdditionalDataSources": Mapping[str, DataSourceTypeDef],
     },
     total=False,
 )
 
 
 class StartDataQualityRulesetEvaluationRunRequestRequestTypeDef(
     _RequiredStartDataQualityRulesetEvaluationRunRequestRequestTypeDef,
@@ -7992,41 +8115,41 @@
     pass
 
 
 CreateSessionResponseTypeDef = TypedDict(
     "CreateSessionResponseTypeDef",
     {
         "Session": SessionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSessionResponseTypeDef = TypedDict(
     "GetSessionResponseTypeDef",
     {
         "Session": SessionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSessionsResponseTypeDef = TypedDict(
     "ListSessionsResponseTypeDef",
     {
         "Ids": List[str],
         "Sessions": List[SessionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDataCatalogEncryptionSettingsResponseTypeDef = TypedDict(
     "GetDataCatalogEncryptionSettingsResponseTypeDef",
     {
         "DataCatalogEncryptionSettings": DataCatalogEncryptionSettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutDataCatalogEncryptionSettingsRequestRequestTypeDef = TypedDict(
     "_RequiredPutDataCatalogEncryptionSettingsRequestRequestTypeDef",
     {
         "DataCatalogEncryptionSettings": DataCatalogEncryptionSettingsTypeDef,
@@ -8058,14 +8181,15 @@
     "_OptionalDatabaseInputTypeDef",
     {
         "Description": str,
         "LocationUri": str,
         "Parameters": Mapping[str, str],
         "CreateTableDefaultPermissions": Sequence[PrincipalPermissionsTypeDef],
         "TargetDatabase": DatabaseIdentifierTypeDef,
+        "FederatedDatabase": FederatedDatabaseTypeDef,
     },
     total=False,
 )
 
 
 class DatabaseInputTypeDef(_RequiredDatabaseInputTypeDef, _OptionalDatabaseInputTypeDef):
     pass
@@ -8083,14 +8207,15 @@
         "Description": str,
         "LocationUri": str,
         "Parameters": Dict[str, str],
         "CreateTime": datetime,
         "CreateTableDefaultPermissions": List[PrincipalPermissionsTypeDef],
         "TargetDatabase": DatabaseIdentifierTypeDef,
         "CatalogId": str,
+        "FederatedDatabase": FederatedDatabaseTypeDef,
     },
     total=False,
 )
 
 
 class DatabaseTypeDef(_RequiredDatabaseTypeDef, _OptionalDatabaseTypeDef):
     pass
@@ -8183,15 +8308,15 @@
     total=False,
 )
 
 DeleteSchemaVersionsResponseTypeDef = TypedDict(
     "DeleteSchemaVersionsResponseTypeDef",
     {
         "SchemaVersionErrors": List[SchemaVersionErrorItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FilterTypeDef = TypedDict(
     "FilterTypeDef",
     {
         "Name": str,
@@ -8346,14 +8471,39 @@
 )
 
 
 class CustomCodeTypeDef(_RequiredCustomCodeTypeDef, _OptionalCustomCodeTypeDef):
     pass
 
 
+_RequiredDynamicTransformTypeDef = TypedDict(
+    "_RequiredDynamicTransformTypeDef",
+    {
+        "Name": str,
+        "TransformName": str,
+        "Inputs": List[str],
+        "FunctionName": str,
+        "Path": str,
+    },
+)
+_OptionalDynamicTransformTypeDef = TypedDict(
+    "_OptionalDynamicTransformTypeDef",
+    {
+        "Parameters": List[TransformConfigParameterTypeDef],
+        "Version": str,
+        "OutputSchemas": List[GlueSchemaTypeDef],
+    },
+    total=False,
+)
+
+
+class DynamicTransformTypeDef(_RequiredDynamicTransformTypeDef, _OptionalDynamicTransformTypeDef):
+    pass
+
+
 _RequiredJDBCConnectorSourceTypeDef = TypedDict(
     "_RequiredJDBCConnectorSourceTypeDef",
     {
         "Name": str,
         "ConnectionName": str,
         "ConnectorName": str,
         "ConnectionType": str,
@@ -8663,24 +8813,24 @@
     pass
 
 
 GetJobRunResponseTypeDef = TypedDict(
     "GetJobRunResponseTypeDef",
     {
         "JobRun": JobRunTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetJobRunsResponseTypeDef = TypedDict(
     "GetJobRunsResponseTypeDef",
     {
         "JobRuns": List[JobRunTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 JobNodeDetailsTypeDef = TypedDict(
     "JobNodeDetailsTypeDef",
     {
         "JobRuns": List[JobRunTypeDef],
@@ -8697,15 +8847,15 @@
         "LogGroupName": str,
         "Properties": TaskRunPropertiesTypeDef,
         "ErrorString": str,
         "StartedOn": datetime,
         "LastModifiedOn": datetime,
         "CompletedOn": datetime,
         "ExecutionTime": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TaskRunTypeDef = TypedDict(
     "TaskRunTypeDef",
     {
         "TransformId": str,
@@ -8756,15 +8906,15 @@
 
 QuerySchemaVersionMetadataResponseTypeDef = TypedDict(
     "QuerySchemaVersionMetadataResponseTypeDef",
     {
         "MetadataInfoMap": Dict[str, MetadataInfoTypeDef],
         "SchemaVersionId": str,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateUserDefinedFunctionRequestRequestTypeDef = TypedDict(
     "_RequiredCreateUserDefinedFunctionRequestRequestTypeDef",
     {
         "DatabaseName": str,
@@ -8811,24 +8961,24 @@
     pass
 
 
 GetUserDefinedFunctionResponseTypeDef = TypedDict(
     "GetUserDefinedFunctionResponseTypeDef",
     {
         "UserDefinedFunction": UserDefinedFunctionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetUserDefinedFunctionsResponseTypeDef = TypedDict(
     "GetUserDefinedFunctionsResponseTypeDef",
     {
         "UserDefinedFunctions": List[UserDefinedFunctionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StatementTypeDef = TypedDict(
     "StatementTypeDef",
     {
         "Id": int,
@@ -8843,41 +8993,41 @@
 )
 
 GetPartitionIndexesResponseTypeDef = TypedDict(
     "GetPartitionIndexesResponseTypeDef",
     {
         "PartitionIndexDescriptorList": List[PartitionIndexDescriptorTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetTriggersResponseTypeDef = TypedDict(
     "BatchGetTriggersResponseTypeDef",
     {
         "Triggers": List[TriggerTypeDef],
         "TriggersNotFound": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTriggerResponseTypeDef = TypedDict(
     "GetTriggerResponseTypeDef",
     {
         "Trigger": TriggerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTriggersResponseTypeDef = TypedDict(
     "GetTriggersResponseTypeDef",
     {
         "Triggers": List[TriggerTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TriggerNodeDetailsTypeDef = TypedDict(
     "TriggerNodeDetailsTypeDef",
     {
         "Trigger": TriggerTypeDef,
@@ -8885,15 +9035,15 @@
     total=False,
 )
 
 UpdateTriggerResponseTypeDef = TypedDict(
     "UpdateTriggerResponseTypeDef",
     {
         "Trigger": TriggerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateTriggerRequestRequestTypeDef = TypedDict(
     "UpdateTriggerRequestRequestTypeDef",
     {
         "Name": str,
@@ -8919,15 +9069,15 @@
         "GlueVersion": str,
         "MaxCapacity": float,
         "WorkerType": WorkerTypeType,
         "NumberOfWorkers": int,
         "Timeout": int,
         "MaxRetries": int,
         "TransformEncryption": TransformEncryptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 MLTransformTypeDef = TypedDict(
     "MLTransformTypeDef",
     {
         "TransformId": str,
@@ -8954,41 +9104,41 @@
 )
 
 BatchGetCrawlersResponseTypeDef = TypedDict(
     "BatchGetCrawlersResponseTypeDef",
     {
         "Crawlers": List[CrawlerTypeDef],
         "CrawlersNotFound": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCrawlerResponseTypeDef = TypedDict(
     "GetCrawlerResponseTypeDef",
     {
         "Crawler": CrawlerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCrawlersResponseTypeDef = TypedDict(
     "GetCrawlersResponseTypeDef",
     {
         "Crawlers": List[CrawlerTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDataQualityResultsResponseTypeDef = TypedDict(
     "ListDataQualityResultsResponseTypeDef",
     {
         "Results": List[DataQualityResultDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDataQualityResultsRequestRequestTypeDef = TypedDict(
     "ListDataQualityResultsRequestRequestTypeDef",
     {
         "Filter": DataQualityResultFilterCriteriaTypeDef,
@@ -8999,24 +9149,24 @@
 )
 
 BatchGetDataQualityResultResponseTypeDef = TypedDict(
     "BatchGetDataQualityResultResponseTypeDef",
     {
         "Results": List[DataQualityResultTypeDef],
         "ResultsNotFound": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDataQualityRuleRecommendationRunsResponseTypeDef = TypedDict(
     "ListDataQualityRuleRecommendationRunsResponseTypeDef",
     {
         "Runs": List[DataQualityRuleRecommendationRunDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDataQualityRuleRecommendationRunsRequestRequestTypeDef = TypedDict(
     "ListDataQualityRuleRecommendationRunsRequestRequestTypeDef",
     {
         "Filter": DataQualityRuleRecommendationRunFilterTypeDef,
@@ -9027,15 +9177,15 @@
 )
 
 ListDataQualityRulesetEvaluationRunsResponseTypeDef = TypedDict(
     "ListDataQualityRulesetEvaluationRunsResponseTypeDef",
     {
         "Runs": List[DataQualityRulesetEvaluationRunDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDataQualityRulesetEvaluationRunsRequestRequestTypeDef = TypedDict(
     "ListDataQualityRulesetEvaluationRunsRequestRequestTypeDef",
     {
         "Filter": DataQualityRulesetEvaluationRunFilterTypeDef,
@@ -9089,24 +9239,24 @@
     pass
 
 
 GetDatabaseResponseTypeDef = TypedDict(
     "GetDatabaseResponseTypeDef",
     {
         "Database": DatabaseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDatabasesResponseTypeDef = TypedDict(
     "GetDatabasesResponseTypeDef",
     {
         "DatabaseList": List[DatabaseTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ColumnStatisticsTypeDef = TypedDict(
     "ColumnStatisticsTypeDef",
     {
         "ColumnName": str,
@@ -9198,37 +9348,38 @@
         "TableType": str,
         "Parameters": Dict[str, str],
         "CreatedBy": str,
         "IsRegisteredWithLakeFormation": bool,
         "TargetTable": TableIdentifierTypeDef,
         "CatalogId": str,
         "VersionId": str,
+        "FederatedTable": FederatedTableTypeDef,
     },
     total=False,
 )
 
 
 class TableTypeDef(_RequiredTableTypeDef, _OptionalTableTypeDef):
     pass
 
 
 GetSecurityConfigurationResponseTypeDef = TypedDict(
     "GetSecurityConfigurationResponseTypeDef",
     {
         "SecurityConfiguration": SecurityConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSecurityConfigurationsResponseTypeDef = TypedDict(
     "GetSecurityConfigurationsResponseTypeDef",
     {
         "SecurityConfigurations": List[SecurityConfigurationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CodeGenConfigurationNodeTypeDef = TypedDict(
     "CodeGenConfigurationNodeTypeDef",
     {
         "AthenaConnectorSource": AthenaConnectorSourceTypeDef,
@@ -9290,41 +9441,44 @@
         "S3HudiDirectTarget": S3HudiDirectTargetTypeDef,
         "DirectJDBCSource": DirectJDBCSourceTypeDef,
         "S3CatalogDeltaSource": S3CatalogDeltaSourceTypeDef,
         "CatalogDeltaSource": CatalogDeltaSourceTypeDef,
         "S3DeltaSource": S3DeltaSourceTypeDef,
         "S3DeltaCatalogTarget": S3DeltaCatalogTargetTypeDef,
         "S3DeltaDirectTarget": S3DeltaDirectTargetTypeDef,
+        "AmazonRedshiftSource": AmazonRedshiftSourceTypeDef,
+        "AmazonRedshiftTarget": AmazonRedshiftTargetTypeDef,
+        "EvaluateDataQualityMultiFrame": EvaluateDataQualityMultiFrameTypeDef,
     },
     total=False,
 )
 
 GetMLTaskRunsResponseTypeDef = TypedDict(
     "GetMLTaskRunsResponseTypeDef",
     {
         "TaskRuns": List[TaskRunTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetStatementResponseTypeDef = TypedDict(
     "GetStatementResponseTypeDef",
     {
         "Statement": StatementTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStatementsResponseTypeDef = TypedDict(
     "ListStatementsResponseTypeDef",
     {
         "Statements": List[StatementTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 NodeTypeDef = TypedDict(
     "NodeTypeDef",
     {
         "Type": NodeTypeType,
@@ -9338,15 +9492,15 @@
 )
 
 GetMLTransformsResponseTypeDef = TypedDict(
     "GetMLTransformsResponseTypeDef",
     {
         "Transforms": List[MLTransformTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ColumnStatisticsErrorTypeDef = TypedDict(
     "ColumnStatisticsErrorTypeDef",
     {
         "ColumnStatistics": ColumnStatisticsTypeDef,
@@ -9356,24 +9510,24 @@
 )
 
 GetColumnStatisticsForPartitionResponseTypeDef = TypedDict(
     "GetColumnStatisticsForPartitionResponseTypeDef",
     {
         "ColumnStatisticsList": List[ColumnStatisticsTypeDef],
         "Errors": List[ColumnErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetColumnStatisticsForTableResponseTypeDef = TypedDict(
     "GetColumnStatisticsForTableResponseTypeDef",
     {
         "ColumnStatisticsList": List[ColumnStatisticsTypeDef],
         "Errors": List[ColumnErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateColumnStatisticsForPartitionRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateColumnStatisticsForPartitionRequestRequestTypeDef",
     {
         "DatabaseName": str,
@@ -9502,42 +9656,42 @@
 
 
 BatchGetPartitionResponseTypeDef = TypedDict(
     "BatchGetPartitionResponseTypeDef",
     {
         "Partitions": List[PartitionTypeDef],
         "UnprocessedKeys": List[PartitionValueListTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetPartitionResponseTypeDef = TypedDict(
     "GetPartitionResponseTypeDef",
     {
         "Partition": PartitionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetPartitionsResponseTypeDef = TypedDict(
     "GetPartitionsResponseTypeDef",
     {
         "Partitions": List[PartitionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetUnfilteredPartitionMetadataResponseTypeDef = TypedDict(
     "GetUnfilteredPartitionMetadataResponseTypeDef",
     {
         "Partition": PartitionTypeDef,
         "AuthorizedColumns": List[str],
         "IsRegisteredWithLakeFormation": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UnfilteredPartitionTypeDef = TypedDict(
     "UnfilteredPartitionTypeDef",
     {
         "Partition": PartitionTypeDef,
@@ -9596,44 +9750,44 @@
     pass
 
 
 GetTableResponseTypeDef = TypedDict(
     "GetTableResponseTypeDef",
     {
         "Table": TableTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTablesResponseTypeDef = TypedDict(
     "GetTablesResponseTypeDef",
     {
         "TableList": List[TableTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetUnfilteredTableMetadataResponseTypeDef = TypedDict(
     "GetUnfilteredTableMetadataResponseTypeDef",
     {
         "Table": TableTypeDef,
         "AuthorizedColumns": List[str],
         "IsRegisteredWithLakeFormation": bool,
         "CellFilters": List[ColumnRowFilterTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SearchTablesResponseTypeDef = TypedDict(
     "SearchTablesResponseTypeDef",
     {
         "NextToken": str,
         "TableList": List[TableTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TableVersionTypeDef = TypedDict(
     "TableVersionTypeDef",
     {
         "Table": TableTypeDef,
@@ -9749,23 +9903,23 @@
     total=False,
 )
 
 UpdateColumnStatisticsForPartitionResponseTypeDef = TypedDict(
     "UpdateColumnStatisticsForPartitionResponseTypeDef",
     {
         "Errors": List[ColumnStatisticsErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateColumnStatisticsForTableResponseTypeDef = TypedDict(
     "UpdateColumnStatisticsForTableResponseTypeDef",
     {
         "Errors": List[ColumnStatisticsErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredBatchUpdatePartitionRequestRequestTypeDef = TypedDict(
     "_RequiredBatchUpdatePartitionRequestRequestTypeDef",
     {
         "DatabaseName": str,
@@ -9790,58 +9944,58 @@
 
 
 GetUnfilteredPartitionsMetadataResponseTypeDef = TypedDict(
     "GetUnfilteredPartitionsMetadataResponseTypeDef",
     {
         "UnfilteredPartitions": List[UnfilteredPartitionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTableVersionResponseTypeDef = TypedDict(
     "GetTableVersionResponseTypeDef",
     {
         "TableVersion": TableVersionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTableVersionsResponseTypeDef = TypedDict(
     "GetTableVersionsResponseTypeDef",
     {
         "TableVersions": List[TableVersionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetJobsResponseTypeDef = TypedDict(
     "BatchGetJobsResponseTypeDef",
     {
         "Jobs": List[JobTypeDef],
         "JobsNotFound": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetJobResponseTypeDef = TypedDict(
     "GetJobResponseTypeDef",
     {
         "Job": JobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetJobsResponseTypeDef = TypedDict(
     "GetJobsResponseTypeDef",
     {
         "Jobs": List[JobTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateJobRequestRequestTypeDef = TypedDict(
     "UpdateJobRequestRequestTypeDef",
     {
         "JobName": str,
@@ -9867,24 +10021,24 @@
     total=False,
 )
 
 GetWorkflowRunResponseTypeDef = TypedDict(
     "GetWorkflowRunResponseTypeDef",
     {
         "Run": WorkflowRunTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetWorkflowRunsResponseTypeDef = TypedDict(
     "GetWorkflowRunsResponseTypeDef",
     {
         "Runs": List[WorkflowRunTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 WorkflowTypeDef = TypedDict(
     "WorkflowTypeDef",
     {
         "Name": str,
@@ -9901,18 +10055,18 @@
 )
 
 BatchGetWorkflowsResponseTypeDef = TypedDict(
     "BatchGetWorkflowsResponseTypeDef",
     {
         "Workflows": List[WorkflowTypeDef],
         "MissingWorkflows": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetWorkflowResponseTypeDef = TypedDict(
     "GetWorkflowResponseTypeDef",
     {
         "Workflow": WorkflowTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-glue-2.5.0.post1/types_aiobotocore_glue/type_defs.pyi` & `types-aiobotocore-glue-2.5.1/types_aiobotocore_glue/type_defs.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -107,19 +107,20 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "NotificationPropertyTypeDef",
     "AggregateOperationTypeDef",
+    "AmazonRedshiftAdvancedOptionTypeDef",
+    "OptionTypeDef",
     "ApplyMappingTypeDef",
     "AuditContextTypeDef",
     "PartitionValueListTypeDef",
     "BasicCatalogTargetTypeDef",
-    "ResponseMetadataTypeDef",
     "BatchDeleteConnectionRequestRequestTypeDef",
     "ErrorDetailTypeDef",
     "BatchDeleteTableRequestRequestTypeDef",
     "BatchDeleteTableVersionRequestRequestTypeDef",
     "BatchGetBlueprintsRequestRequestTypeDef",
     "BatchGetCrawlersRequestRequestTypeDef",
     "BatchGetCustomEntityTypesRequestRequestTypeDef",
@@ -136,24 +137,26 @@
     "BlueprintDetailsTypeDef",
     "BlueprintRunTypeDef",
     "LastActiveDefinitionTypeDef",
     "BooleanColumnStatisticsDataTypeDef",
     "CancelDataQualityRuleRecommendationRunRequestRequestTypeDef",
     "CancelDataQualityRulesetEvaluationRunRequestRequestTypeDef",
     "CancelMLTaskRunRequestRequestTypeDef",
+    "CancelMLTaskRunResponseTypeDef",
     "CancelStatementRequestRequestTypeDef",
     "CatalogEntryTypeDef",
     "CatalogImportStatusTypeDef",
     "KafkaStreamingSourceOptionsTypeDef",
     "StreamingDataPreviewOptionsTypeDef",
     "KinesisStreamingSourceOptionsTypeDef",
     "CatalogSchemaChangePolicyTypeDef",
     "CatalogSourceTypeDef",
     "CatalogTargetTypeDef",
     "CheckSchemaVersionValidityInputRequestTypeDef",
+    "CheckSchemaVersionValidityResponseTypeDef",
     "CsvClassifierTypeDef",
     "GrokClassifierTypeDef",
     "JsonClassifierTypeDef",
     "XMLClassifierTypeDef",
     "CloudWatchEncryptionTypeDef",
     "DirectJDBCSourceTypeDef",
     "DropDuplicatesTypeDef",
@@ -204,282 +207,299 @@
     "LastCrawlInfoTypeDef",
     "LineageConfigurationTypeDef",
     "RecrawlPolicyTypeDef",
     "ScheduleTypeDef",
     "SchemaChangePolicyTypeDef",
     "CrawlsFilterTypeDef",
     "CreateBlueprintRequestRequestTypeDef",
+    "CreateBlueprintResponseTypeDef",
     "CreateCsvClassifierRequestTypeDef",
     "CreateGrokClassifierRequestTypeDef",
     "CreateJsonClassifierRequestTypeDef",
     "CreateXMLClassifierRequestTypeDef",
     "CreateCustomEntityTypeRequestRequestTypeDef",
+    "CreateCustomEntityTypeResponseTypeDef",
     "DataQualityTargetTableTypeDef",
+    "CreateDataQualityRulesetResponseTypeDef",
     "CreateDevEndpointRequestRequestTypeDef",
+    "CreateDevEndpointResponseTypeDef",
     "ExecutionPropertyTypeDef",
     "JobCommandTypeDef",
     "SourceControlDetailsTypeDef",
+    "CreateJobResponseTypeDef",
     "GlueTableTypeDef",
+    "CreateMLTransformResponseTypeDef",
     "PartitionIndexTypeDef",
     "CreateRegistryInputRequestTypeDef",
+    "CreateRegistryResponseTypeDef",
     "RegistryIdTypeDef",
+    "CreateSchemaResponseTypeDef",
+    "CreateScriptResponseTypeDef",
+    "CreateSecurityConfigurationResponseTypeDef",
     "SessionCommandTypeDef",
     "EventBatchingConditionTypeDef",
+    "CreateTriggerResponseTypeDef",
     "CreateWorkflowRequestRequestTypeDef",
+    "CreateWorkflowResponseTypeDef",
     "DQResultsPublishingOptionsTypeDef",
     "DQStopJobOnFailureOptionsTypeDef",
     "EncryptionAtRestTypeDef",
     "DataLakePrincipalTypeDef",
     "DataQualityEvaluationRunAdditionalRunOptionsTypeDef",
     "DataQualityRuleResultTypeDef",
     "DatabaseIdentifierTypeDef",
+    "FederatedDatabaseTypeDef",
     "DatatypeTypeDef",
     "DecimalNumberTypeDef",
     "DeleteBlueprintRequestRequestTypeDef",
+    "DeleteBlueprintResponseTypeDef",
     "DeleteClassifierRequestRequestTypeDef",
     "DeleteColumnStatisticsForPartitionRequestRequestTypeDef",
     "DeleteColumnStatisticsForTableRequestRequestTypeDef",
     "DeleteConnectionRequestRequestTypeDef",
     "DeleteCrawlerRequestRequestTypeDef",
     "DeleteCustomEntityTypeRequestRequestTypeDef",
+    "DeleteCustomEntityTypeResponseTypeDef",
     "DeleteDataQualityRulesetRequestRequestTypeDef",
     "DeleteDatabaseRequestRequestTypeDef",
     "DeleteDevEndpointRequestRequestTypeDef",
     "DeleteJobRequestRequestTypeDef",
+    "DeleteJobResponseTypeDef",
     "DeleteMLTransformRequestRequestTypeDef",
+    "DeleteMLTransformResponseTypeDef",
     "DeletePartitionIndexRequestRequestTypeDef",
     "DeletePartitionRequestRequestTypeDef",
+    "DeleteRegistryResponseTypeDef",
     "DeleteResourcePolicyRequestRequestTypeDef",
     "SchemaIdTypeDef",
+    "DeleteSchemaResponseTypeDef",
     "DeleteSecurityConfigurationRequestRequestTypeDef",
     "DeleteSessionRequestRequestTypeDef",
+    "DeleteSessionResponseTypeDef",
     "DeleteTableRequestRequestTypeDef",
     "DeleteTableVersionRequestRequestTypeDef",
     "DeleteTriggerRequestRequestTypeDef",
+    "DeleteTriggerResponseTypeDef",
     "DeleteUserDefinedFunctionRequestRequestTypeDef",
     "DeleteWorkflowRequestRequestTypeDef",
+    "DeleteWorkflowResponseTypeDef",
     "DevEndpointCustomLibrariesTypeDef",
     "DirectSchemaChangePolicyTypeDef",
     "NullCheckBoxListTypeDef",
     "TransformConfigParameterTypeDef",
     "EdgeTypeDef",
     "JobBookmarksEncryptionTypeDef",
     "S3EncryptionTypeDef",
     "ErrorDetailsTypeDef",
     "ExportLabelsTaskRunPropertiesTypeDef",
+    "FederatedTableTypeDef",
     "FilterValueTypeDef",
     "FindMatchesParametersTypeDef",
     "FindMatchesTaskRunPropertiesTypeDef",
     "GetBlueprintRequestRequestTypeDef",
     "GetBlueprintRunRequestRequestTypeDef",
     "GetBlueprintRunsRequestRequestTypeDef",
     "GetCatalogImportStatusRequestRequestTypeDef",
     "GetClassifierRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetClassifiersRequestGetClassifiersPaginateTypeDef",
     "GetClassifiersRequestRequestTypeDef",
     "GetColumnStatisticsForPartitionRequestRequestTypeDef",
     "GetColumnStatisticsForTableRequestRequestTypeDef",
     "GetConnectionRequestRequestTypeDef",
     "GetConnectionsFilterTypeDef",
+    "GetCrawlerMetricsRequestGetCrawlerMetricsPaginateTypeDef",
     "GetCrawlerMetricsRequestRequestTypeDef",
     "GetCrawlerRequestRequestTypeDef",
+    "GetCrawlersRequestGetCrawlersPaginateTypeDef",
     "GetCrawlersRequestRequestTypeDef",
     "GetCustomEntityTypeRequestRequestTypeDef",
+    "GetCustomEntityTypeResponseTypeDef",
     "GetDataCatalogEncryptionSettingsRequestRequestTypeDef",
     "GetDataQualityResultRequestRequestTypeDef",
     "GetDataQualityRuleRecommendationRunRequestRequestTypeDef",
     "GetDataQualityRulesetEvaluationRunRequestRequestTypeDef",
     "GetDataQualityRulesetRequestRequestTypeDef",
     "GetDatabaseRequestRequestTypeDef",
+    "GetDatabasesRequestGetDatabasesPaginateTypeDef",
     "GetDatabasesRequestRequestTypeDef",
     "GetDataflowGraphRequestRequestTypeDef",
     "GetDevEndpointRequestRequestTypeDef",
+    "GetDevEndpointsRequestGetDevEndpointsPaginateTypeDef",
     "GetDevEndpointsRequestRequestTypeDef",
     "GetJobBookmarkRequestRequestTypeDef",
     "JobBookmarkEntryTypeDef",
     "GetJobRequestRequestTypeDef",
     "GetJobRunRequestRequestTypeDef",
+    "GetJobRunsRequestGetJobRunsPaginateTypeDef",
     "GetJobRunsRequestRequestTypeDef",
+    "GetJobsRequestGetJobsPaginateTypeDef",
     "GetJobsRequestRequestTypeDef",
     "GetMLTaskRunRequestRequestTypeDef",
     "TaskRunFilterCriteriaTypeDef",
     "TaskRunSortCriteriaTypeDef",
     "GetMLTransformRequestRequestTypeDef",
     "SchemaColumnTypeDef",
     "TransformSortCriteriaTypeDef",
     "MappingEntryTypeDef",
+    "GetPartitionIndexesRequestGetPartitionIndexesPaginateTypeDef",
     "GetPartitionIndexesRequestRequestTypeDef",
     "GetPartitionRequestRequestTypeDef",
     "SegmentTypeDef",
+    "GetPlanResponseTypeDef",
+    "GetRegistryResponseTypeDef",
+    "GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef",
     "GetResourcePoliciesRequestRequestTypeDef",
     "GluePolicyTypeDef",
     "GetResourcePolicyRequestRequestTypeDef",
+    "GetResourcePolicyResponseTypeDef",
+    "GetSchemaByDefinitionResponseTypeDef",
+    "GetSchemaResponseTypeDef",
     "SchemaVersionNumberTypeDef",
+    "GetSchemaVersionResponseTypeDef",
+    "GetSchemaVersionsDiffResponseTypeDef",
     "GetSecurityConfigurationRequestRequestTypeDef",
+    "GetSecurityConfigurationsRequestGetSecurityConfigurationsPaginateTypeDef",
     "GetSecurityConfigurationsRequestRequestTypeDef",
     "GetSessionRequestRequestTypeDef",
     "GetStatementRequestRequestTypeDef",
     "GetTableRequestRequestTypeDef",
     "GetTableVersionRequestRequestTypeDef",
+    "GetTableVersionsRequestGetTableVersionsPaginateTypeDef",
     "GetTableVersionsRequestRequestTypeDef",
+    "GetTablesRequestGetTablesPaginateTypeDef",
     "GetTablesRequestRequestTypeDef",
     "GetTagsRequestRequestTypeDef",
+    "GetTagsResponseTypeDef",
     "GetTriggerRequestRequestTypeDef",
+    "GetTriggersRequestGetTriggersPaginateTypeDef",
     "GetTriggersRequestRequestTypeDef",
     "GetUserDefinedFunctionRequestRequestTypeDef",
+    "GetUserDefinedFunctionsRequestGetUserDefinedFunctionsPaginateTypeDef",
     "GetUserDefinedFunctionsRequestRequestTypeDef",
     "GetWorkflowRequestRequestTypeDef",
     "GetWorkflowRunPropertiesRequestRequestTypeDef",
+    "GetWorkflowRunPropertiesResponseTypeDef",
     "GetWorkflowRunRequestRequestTypeDef",
     "GetWorkflowRunsRequestRequestTypeDef",
     "GlueStudioSchemaColumnTypeDef",
     "S3SourceAdditionalOptionsTypeDef",
     "ImportCatalogToGlueRequestRequestTypeDef",
     "ImportLabelsTaskRunPropertiesTypeDef",
     "JDBCConnectorOptionsTypeDef",
     "PredecessorTypeDef",
     "JoinColumnTypeDef",
     "KeySchemaElementTypeDef",
     "LabelingSetGenerationTaskRunPropertiesTypeDef",
     "ListBlueprintsRequestRequestTypeDef",
+    "ListBlueprintsResponseTypeDef",
     "ListCrawlersRequestRequestTypeDef",
+    "ListCrawlersResponseTypeDef",
     "ListCustomEntityTypesRequestRequestTypeDef",
     "ListDevEndpointsRequestRequestTypeDef",
+    "ListDevEndpointsResponseTypeDef",
     "ListJobsRequestRequestTypeDef",
+    "ListJobsResponseTypeDef",
+    "ListMLTransformsResponseTypeDef",
+    "ListRegistriesInputListRegistriesPaginateTypeDef",
     "ListRegistriesInputRequestTypeDef",
     "RegistryListItemTypeDef",
     "SchemaVersionListItemTypeDef",
     "SchemaListItemTypeDef",
     "ListSessionsRequestRequestTypeDef",
     "ListStatementsRequestRequestTypeDef",
     "ListTriggersRequestRequestTypeDef",
+    "ListTriggersResponseTypeDef",
     "ListWorkflowsRequestRequestTypeDef",
+    "ListWorkflowsResponseTypeDef",
     "MLUserDataEncryptionTypeDef",
     "MappingTypeDef",
     "OtherMetadataValueListItemTypeDef",
     "MetadataKeyValuePairTypeDef",
     "OrderTypeDef",
+    "PaginatorConfigTypeDef",
     "PropertyPredicateTypeDef",
     "PutResourcePolicyRequestRequestTypeDef",
+    "PutResourcePolicyResponseTypeDef",
+    "PutSchemaVersionMetadataResponseTypeDef",
     "PutWorkflowRunPropertiesRequestRequestTypeDef",
     "UpsertRedshiftTargetOptionsTypeDef",
+    "RegisterSchemaVersionResponseTypeDef",
+    "RemoveSchemaVersionMetadataResponseTypeDef",
     "ResetJobBookmarkRequestRequestTypeDef",
     "ResourceUriTypeDef",
+    "ResponseMetadataTypeDef",
     "ResumeWorkflowRunRequestRequestTypeDef",
+    "ResumeWorkflowRunResponseTypeDef",
     "RunStatementRequestRequestTypeDef",
+    "RunStatementResponseTypeDef",
     "S3DirectSourceAdditionalOptionsTypeDef",
     "SortCriterionTypeDef",
     "SerDeInfoTypeDef",
     "SkewedInfoTypeDef",
     "SqlAliasTypeDef",
     "StartBlueprintRunRequestRequestTypeDef",
+    "StartBlueprintRunResponseTypeDef",
     "StartCrawlerRequestRequestTypeDef",
     "StartCrawlerScheduleRequestRequestTypeDef",
+    "StartDataQualityRuleRecommendationRunResponseTypeDef",
+    "StartDataQualityRulesetEvaluationRunResponseTypeDef",
     "StartExportLabelsTaskRunRequestRequestTypeDef",
+    "StartExportLabelsTaskRunResponseTypeDef",
     "StartImportLabelsTaskRunRequestRequestTypeDef",
+    "StartImportLabelsTaskRunResponseTypeDef",
+    "StartJobRunResponseTypeDef",
     "StartMLEvaluationTaskRunRequestRequestTypeDef",
+    "StartMLEvaluationTaskRunResponseTypeDef",
     "StartMLLabelingSetGenerationTaskRunRequestRequestTypeDef",
+    "StartMLLabelingSetGenerationTaskRunResponseTypeDef",
     "StartTriggerRequestRequestTypeDef",
+    "StartTriggerResponseTypeDef",
     "StartWorkflowRunRequestRequestTypeDef",
+    "StartWorkflowRunResponseTypeDef",
     "StartingEventBatchConditionTypeDef",
     "StatementOutputDataTypeDef",
     "StopCrawlerRequestRequestTypeDef",
     "StopCrawlerScheduleRequestRequestTypeDef",
     "StopSessionRequestRequestTypeDef",
+    "StopSessionResponseTypeDef",
     "StopTriggerRequestRequestTypeDef",
+    "StopTriggerResponseTypeDef",
     "StopWorkflowRunRequestRequestTypeDef",
     "TableIdentifierTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateBlueprintRequestRequestTypeDef",
+    "UpdateBlueprintResponseTypeDef",
     "UpdateCsvClassifierRequestTypeDef",
     "UpdateGrokClassifierRequestTypeDef",
     "UpdateJsonClassifierRequestTypeDef",
     "UpdateXMLClassifierRequestTypeDef",
     "UpdateCrawlerScheduleRequestRequestTypeDef",
     "UpdateDataQualityRulesetRequestRequestTypeDef",
+    "UpdateDataQualityRulesetResponseTypeDef",
     "UpdateJobFromSourceControlRequestRequestTypeDef",
+    "UpdateJobFromSourceControlResponseTypeDef",
+    "UpdateJobResponseTypeDef",
+    "UpdateMLTransformResponseTypeDef",
+    "UpdateRegistryResponseTypeDef",
+    "UpdateSchemaResponseTypeDef",
     "UpdateSourceControlFromJobRequestRequestTypeDef",
+    "UpdateSourceControlFromJobResponseTypeDef",
     "UpdateWorkflowRequestRequestTypeDef",
+    "UpdateWorkflowResponseTypeDef",
     "WorkflowRunStatisticsTypeDef",
     "ActionTypeDef",
     "StartJobRunRequestRequestTypeDef",
     "AggregateTypeDef",
+    "AmazonRedshiftNodeDataTypeDef",
     "GetUnfilteredPartitionMetadataRequestRequestTypeDef",
     "GetUnfilteredTableMetadataRequestRequestTypeDef",
     "BackfillErrorTypeDef",
     "BatchDeletePartitionRequestRequestTypeDef",
     "BatchGetPartitionRequestRequestTypeDef",
-    "CancelMLTaskRunResponseTypeDef",
-    "CheckSchemaVersionValidityResponseTypeDef",
-    "CreateBlueprintResponseTypeDef",
-    "CreateCustomEntityTypeResponseTypeDef",
-    "CreateDataQualityRulesetResponseTypeDef",
-    "CreateDevEndpointResponseTypeDef",
-    "CreateJobResponseTypeDef",
-    "CreateMLTransformResponseTypeDef",
-    "CreateRegistryResponseTypeDef",
-    "CreateSchemaResponseTypeDef",
-    "CreateScriptResponseTypeDef",
-    "CreateSecurityConfigurationResponseTypeDef",
-    "CreateTriggerResponseTypeDef",
-    "CreateWorkflowResponseTypeDef",
-    "DeleteBlueprintResponseTypeDef",
-    "DeleteCustomEntityTypeResponseTypeDef",
-    "DeleteJobResponseTypeDef",
-    "DeleteMLTransformResponseTypeDef",
-    "DeleteRegistryResponseTypeDef",
-    "DeleteSchemaResponseTypeDef",
-    "DeleteSessionResponseTypeDef",
-    "DeleteTriggerResponseTypeDef",
-    "DeleteWorkflowResponseTypeDef",
-    "GetCustomEntityTypeResponseTypeDef",
-    "GetPlanResponseTypeDef",
-    "GetRegistryResponseTypeDef",
-    "GetResourcePolicyResponseTypeDef",
-    "GetSchemaByDefinitionResponseTypeDef",
-    "GetSchemaResponseTypeDef",
-    "GetSchemaVersionResponseTypeDef",
-    "GetSchemaVersionsDiffResponseTypeDef",
-    "GetTagsResponseTypeDef",
-    "GetWorkflowRunPropertiesResponseTypeDef",
-    "ListBlueprintsResponseTypeDef",
-    "ListCrawlersResponseTypeDef",
-    "ListDevEndpointsResponseTypeDef",
-    "ListJobsResponseTypeDef",
-    "ListMLTransformsResponseTypeDef",
-    "ListTriggersResponseTypeDef",
-    "ListWorkflowsResponseTypeDef",
-    "PutResourcePolicyResponseTypeDef",
-    "PutSchemaVersionMetadataResponseTypeDef",
-    "RegisterSchemaVersionResponseTypeDef",
-    "RemoveSchemaVersionMetadataResponseTypeDef",
-    "ResumeWorkflowRunResponseTypeDef",
-    "RunStatementResponseTypeDef",
-    "StartBlueprintRunResponseTypeDef",
-    "StartDataQualityRuleRecommendationRunResponseTypeDef",
-    "StartDataQualityRulesetEvaluationRunResponseTypeDef",
-    "StartExportLabelsTaskRunResponseTypeDef",
-    "StartImportLabelsTaskRunResponseTypeDef",
-    "StartJobRunResponseTypeDef",
-    "StartMLEvaluationTaskRunResponseTypeDef",
-    "StartMLLabelingSetGenerationTaskRunResponseTypeDef",
-    "StartTriggerResponseTypeDef",
-    "StartWorkflowRunResponseTypeDef",
-    "StopSessionResponseTypeDef",
-    "StopTriggerResponseTypeDef",
-    "UpdateBlueprintResponseTypeDef",
-    "UpdateDataQualityRulesetResponseTypeDef",
-    "UpdateJobFromSourceControlResponseTypeDef",
-    "UpdateJobResponseTypeDef",
-    "UpdateMLTransformResponseTypeDef",
-    "UpdateRegistryResponseTypeDef",
-    "UpdateSchemaResponseTypeDef",
-    "UpdateSourceControlFromJobResponseTypeDef",
-    "UpdateWorkflowResponseTypeDef",
     "BatchDeleteConnectionResponseTypeDef",
     "BatchStopJobRunErrorTypeDef",
     "BatchUpdatePartitionFailureEntryTypeDef",
     "ColumnErrorTypeDef",
     "PartitionErrorTypeDef",
     "TableErrorTypeDef",
     "TableVersionErrorTypeDef",
@@ -518,57 +538,42 @@
     "DataQualityRulesetListDetailsTypeDef",
     "GetDataQualityRulesetResponseTypeDef",
     "DataSourceTypeDef",
     "CreatePartitionIndexRequestRequestTypeDef",
     "CreateSchemaInputRequestTypeDef",
     "DeleteRegistryInputRequestTypeDef",
     "GetRegistryInputRequestTypeDef",
+    "ListSchemasInputListSchemasPaginateTypeDef",
     "ListSchemasInputRequestTypeDef",
     "UpdateRegistryInputRequestTypeDef",
     "CreateSessionRequestRequestTypeDef",
     "SessionTypeDef",
+    "EvaluateDataQualityMultiFrameTypeDef",
     "EvaluateDataQualityTypeDef",
     "DataCatalogEncryptionSettingsTypeDef",
     "PrincipalPermissionsTypeDef",
     "NullValueFieldTypeDef",
     "DecimalColumnStatisticsDataTypeDef",
     "DeleteSchemaInputRequestTypeDef",
     "DeleteSchemaVersionsInputRequestTypeDef",
     "GetSchemaByDefinitionInputRequestTypeDef",
     "GetSchemaInputRequestTypeDef",
+    "ListSchemaVersionsInputListSchemaVersionsPaginateTypeDef",
     "ListSchemaVersionsInputRequestTypeDef",
     "RegisterSchemaVersionInputRequestTypeDef",
     "SchemaReferenceTypeDef",
     "UpdateDevEndpointRequestRequestTypeDef",
     "S3DeltaDirectTargetTypeDef",
     "S3DirectTargetTypeDef",
     "S3GlueParquetTargetTypeDef",
     "S3HudiDirectTargetTypeDef",
-    "DynamicTransformTypeDef",
     "EncryptionConfigurationTypeDef",
     "SchemaVersionErrorItemTypeDef",
     "FilterExpressionTypeDef",
     "TransformParametersTypeDef",
-    "GetClassifiersRequestGetClassifiersPaginateTypeDef",
-    "GetCrawlerMetricsRequestGetCrawlerMetricsPaginateTypeDef",
-    "GetCrawlersRequestGetCrawlersPaginateTypeDef",
-    "GetDatabasesRequestGetDatabasesPaginateTypeDef",
-    "GetDevEndpointsRequestGetDevEndpointsPaginateTypeDef",
-    "GetJobRunsRequestGetJobRunsPaginateTypeDef",
-    "GetJobsRequestGetJobsPaginateTypeDef",
-    "GetPartitionIndexesRequestGetPartitionIndexesPaginateTypeDef",
-    "GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef",
-    "GetSecurityConfigurationsRequestGetSecurityConfigurationsPaginateTypeDef",
-    "GetTableVersionsRequestGetTableVersionsPaginateTypeDef",
-    "GetTablesRequestGetTablesPaginateTypeDef",
-    "GetTriggersRequestGetTriggersPaginateTypeDef",
-    "GetUserDefinedFunctionsRequestGetUserDefinedFunctionsPaginateTypeDef",
-    "ListRegistriesInputListRegistriesPaginateTypeDef",
-    "ListSchemaVersionsInputListSchemaVersionsPaginateTypeDef",
-    "ListSchemasInputListSchemasPaginateTypeDef",
     "GetConnectionsRequestGetConnectionsPaginateTypeDef",
     "GetConnectionsRequestRequestTypeDef",
     "GetJobBookmarkResponseTypeDef",
     "ResetJobBookmarkResponseTypeDef",
     "GetMLTaskRunsRequestRequestTypeDef",
     "TransformFilterCriteriaTypeDef",
     "GetMappingResponseTypeDef",
@@ -595,14 +600,16 @@
     "RemoveSchemaVersionMetadataInputRequestTypeDef",
     "RedshiftTargetTypeDef",
     "UserDefinedFunctionInputTypeDef",
     "UserDefinedFunctionTypeDef",
     "SearchTablesRequestRequestTypeDef",
     "StatementOutputTypeDef",
     "UpdateClassifierRequestRequestTypeDef",
+    "AmazonRedshiftSourceTypeDef",
+    "AmazonRedshiftTargetTypeDef",
     "PartitionIndexDescriptorTypeDef",
     "BatchStopJobRunResponseTypeDef",
     "BatchUpdatePartitionResponseTypeDef",
     "BatchCreatePartitionResponseTypeDef",
     "BatchDeletePartitionResponseTypeDef",
     "BatchDeleteTableResponseTypeDef",
     "BatchDeleteTableVersionResponseTypeDef",
@@ -656,14 +663,15 @@
     "UpdateMLTransformRequestRequestTypeDef",
     "GetMLTransformsRequestRequestTypeDef",
     "ListMLTransformsRequestRequestTypeDef",
     "AthenaConnectorSourceTypeDef",
     "CatalogDeltaSourceTypeDef",
     "CatalogHudiSourceTypeDef",
     "CustomCodeTypeDef",
+    "DynamicTransformTypeDef",
     "JDBCConnectorSourceTypeDef",
     "JDBCConnectorTargetTypeDef",
     "S3CatalogDeltaSourceTypeDef",
     "S3CatalogHudiSourceTypeDef",
     "S3CsvSourceTypeDef",
     "S3DeltaSourceTypeDef",
     "S3HudiSourceTypeDef",
@@ -775,14 +783,33 @@
     "AggregateOperationTypeDef",
     {
         "Column": List[str],
         "AggFunc": AggFunctionType,
     },
 )
 
+AmazonRedshiftAdvancedOptionTypeDef = TypedDict(
+    "AmazonRedshiftAdvancedOptionTypeDef",
+    {
+        "Key": str,
+        "Value": str,
+    },
+    total=False,
+)
+
+OptionTypeDef = TypedDict(
+    "OptionTypeDef",
+    {
+        "Value": str,
+        "Label": str,
+        "Description": str,
+    },
+    total=False,
+)
+
 ApplyMappingTypeDef = TypedDict(
     "ApplyMappingTypeDef",
     {
         "Name": str,
         "Inputs": List[str],
         "Mapping": List["MappingTypeDef"],
     },
@@ -811,25 +838,14 @@
         "Name": str,
         "Inputs": List[str],
         "Database": str,
         "Table": str,
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
 _RequiredBatchDeleteConnectionRequestRequestTypeDef = TypedDict(
     "_RequiredBatchDeleteConnectionRequestRequestTypeDef",
     {
         "ConnectionNameList": Sequence[str],
     },
 )
 _OptionalBatchDeleteConnectionRequestRequestTypeDef = TypedDict(
@@ -1121,14 +1137,24 @@
     "CancelMLTaskRunRequestRequestTypeDef",
     {
         "TransformId": str,
         "TaskRunId": str,
     },
 )
 
+CancelMLTaskRunResponseTypeDef = TypedDict(
+    "CancelMLTaskRunResponseTypeDef",
+    {
+        "TransformId": str,
+        "TaskRunId": str,
+        "Status": TaskStatusTypeType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCancelStatementRequestRequestTypeDef = TypedDict(
     "_RequiredCancelStatementRequestRequestTypeDef",
     {
         "SessionId": str,
         "Id": int,
     },
 )
@@ -1180,14 +1206,15 @@
         "NumRetries": int,
         "RetryIntervalMs": int,
         "MaxOffsetsPerTrigger": int,
         "MinPartitions": int,
         "IncludeHeaders": bool,
         "AddRecordTimestamp": str,
         "EmitConsumerLagMetrics": str,
+        "StartingTimestamp": datetime,
     },
     total=False,
 )
 
 StreamingDataPreviewOptionsTypeDef = TypedDict(
     "StreamingDataPreviewOptionsTypeDef",
     {
@@ -1216,14 +1243,15 @@
         "MaxRetryIntervalMs": int,
         "AvoidEmptyBatches": bool,
         "StreamArn": str,
         "RoleArn": str,
         "RoleSessionName": str,
         "AddRecordTimestamp": str,
         "EmitConsumerLagMetrics": str,
+        "StartingTimestamp": datetime,
     },
     total=False,
 )
 
 CatalogSchemaChangePolicyTypeDef = TypedDict(
     "CatalogSchemaChangePolicyTypeDef",
     {
@@ -1266,14 +1294,23 @@
     "CheckSchemaVersionValidityInputRequestTypeDef",
     {
         "DataFormat": DataFormatType,
         "SchemaDefinition": str,
     },
 )
 
+CheckSchemaVersionValidityResponseTypeDef = TypedDict(
+    "CheckSchemaVersionValidityResponseTypeDef",
+    {
+        "Valid": bool,
+        "Error": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCsvClassifierTypeDef = TypedDict(
     "_RequiredCsvClassifierTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalCsvClassifierTypeDef = TypedDict(
@@ -2040,14 +2077,22 @@
 )
 
 class CreateBlueprintRequestRequestTypeDef(
     _RequiredCreateBlueprintRequestRequestTypeDef, _OptionalCreateBlueprintRequestRequestTypeDef
 ):
     pass
 
+CreateBlueprintResponseTypeDef = TypedDict(
+    "CreateBlueprintResponseTypeDef",
+    {
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateCsvClassifierRequestTypeDef = TypedDict(
     "_RequiredCreateCsvClassifierRequestTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalCreateCsvClassifierRequestTypeDef = TypedDict(
@@ -2126,31 +2171,60 @@
         "RegexString": str,
     },
 )
 _OptionalCreateCustomEntityTypeRequestRequestTypeDef = TypedDict(
     "_OptionalCreateCustomEntityTypeRequestRequestTypeDef",
     {
         "ContextWords": Sequence[str],
+        "Tags": Mapping[str, str],
     },
     total=False,
 )
 
 class CreateCustomEntityTypeRequestRequestTypeDef(
     _RequiredCreateCustomEntityTypeRequestRequestTypeDef,
     _OptionalCreateCustomEntityTypeRequestRequestTypeDef,
 ):
     pass
 
-DataQualityTargetTableTypeDef = TypedDict(
-    "DataQualityTargetTableTypeDef",
+CreateCustomEntityTypeResponseTypeDef = TypedDict(
+    "CreateCustomEntityTypeResponseTypeDef",
+    {
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredDataQualityTargetTableTypeDef = TypedDict(
+    "_RequiredDataQualityTargetTableTypeDef",
     {
         "TableName": str,
         "DatabaseName": str,
     },
 )
+_OptionalDataQualityTargetTableTypeDef = TypedDict(
+    "_OptionalDataQualityTargetTableTypeDef",
+    {
+        "CatalogId": str,
+    },
+    total=False,
+)
+
+class DataQualityTargetTableTypeDef(
+    _RequiredDataQualityTargetTableTypeDef, _OptionalDataQualityTargetTableTypeDef
+):
+    pass
+
+CreateDataQualityRulesetResponseTypeDef = TypedDict(
+    "CreateDataQualityRulesetResponseTypeDef",
+    {
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredCreateDevEndpointRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDevEndpointRequestRequestTypeDef",
     {
         "EndpointName": str,
         "RoleArn": str,
     },
@@ -2176,28 +2250,55 @@
 )
 
 class CreateDevEndpointRequestRequestTypeDef(
     _RequiredCreateDevEndpointRequestRequestTypeDef, _OptionalCreateDevEndpointRequestRequestTypeDef
 ):
     pass
 
+CreateDevEndpointResponseTypeDef = TypedDict(
+    "CreateDevEndpointResponseTypeDef",
+    {
+        "EndpointName": str,
+        "Status": str,
+        "SecurityGroupIds": List[str],
+        "SubnetId": str,
+        "RoleArn": str,
+        "YarnEndpointAddress": str,
+        "ZeppelinRemoteSparkInterpreterPort": int,
+        "NumberOfNodes": int,
+        "WorkerType": WorkerTypeType,
+        "GlueVersion": str,
+        "NumberOfWorkers": int,
+        "AvailabilityZone": str,
+        "VpcId": str,
+        "ExtraPythonLibsS3Path": str,
+        "ExtraJarsS3Path": str,
+        "FailureReason": str,
+        "SecurityConfiguration": str,
+        "CreatedTimestamp": datetime,
+        "Arguments": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ExecutionPropertyTypeDef = TypedDict(
     "ExecutionPropertyTypeDef",
     {
         "MaxConcurrentRuns": int,
     },
     total=False,
 )
 
 JobCommandTypeDef = TypedDict(
     "JobCommandTypeDef",
     {
         "Name": str,
         "ScriptLocation": str,
         "PythonVersion": str,
+        "Runtime": str,
     },
     total=False,
 )
 
 SourceControlDetailsTypeDef = TypedDict(
     "SourceControlDetailsTypeDef",
     {
@@ -2209,14 +2310,22 @@
         "LastCommitId": str,
         "AuthStrategy": SourceControlAuthStrategyType,
         "AuthToken": str,
     },
     total=False,
 )
 
+CreateJobResponseTypeDef = TypedDict(
+    "CreateJobResponseTypeDef",
+    {
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGlueTableTypeDef = TypedDict(
     "_RequiredGlueTableTypeDef",
     {
         "DatabaseName": str,
         "TableName": str,
     },
 )
@@ -2229,14 +2338,22 @@
     },
     total=False,
 )
 
 class GlueTableTypeDef(_RequiredGlueTableTypeDef, _OptionalGlueTableTypeDef):
     pass
 
+CreateMLTransformResponseTypeDef = TypedDict(
+    "CreateMLTransformResponseTypeDef",
+    {
+        "TransformId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 PartitionIndexTypeDef = TypedDict(
     "PartitionIndexTypeDef",
     {
         "Keys": Sequence[str],
         "IndexName": str,
     },
 )
@@ -2257,23 +2374,73 @@
 )
 
 class CreateRegistryInputRequestTypeDef(
     _RequiredCreateRegistryInputRequestTypeDef, _OptionalCreateRegistryInputRequestTypeDef
 ):
     pass
 
+CreateRegistryResponseTypeDef = TypedDict(
+    "CreateRegistryResponseTypeDef",
+    {
+        "RegistryArn": str,
+        "RegistryName": str,
+        "Description": str,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RegistryIdTypeDef = TypedDict(
     "RegistryIdTypeDef",
     {
         "RegistryName": str,
         "RegistryArn": str,
     },
     total=False,
 )
 
+CreateSchemaResponseTypeDef = TypedDict(
+    "CreateSchemaResponseTypeDef",
+    {
+        "RegistryName": str,
+        "RegistryArn": str,
+        "SchemaName": str,
+        "SchemaArn": str,
+        "Description": str,
+        "DataFormat": DataFormatType,
+        "Compatibility": CompatibilityType,
+        "SchemaCheckpoint": int,
+        "LatestSchemaVersion": int,
+        "NextSchemaVersion": int,
+        "SchemaStatus": SchemaStatusType,
+        "Tags": Dict[str, str],
+        "SchemaVersionId": str,
+        "SchemaVersionStatus": SchemaVersionStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateScriptResponseTypeDef = TypedDict(
+    "CreateScriptResponseTypeDef",
+    {
+        "PythonScript": str,
+        "ScalaCode": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateSecurityConfigurationResponseTypeDef = TypedDict(
+    "CreateSecurityConfigurationResponseTypeDef",
+    {
+        "Name": str,
+        "CreatedTimestamp": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 SessionCommandTypeDef = TypedDict(
     "SessionCommandTypeDef",
     {
         "Name": str,
         "PythonVersion": str,
     },
     total=False,
@@ -2294,14 +2461,22 @@
 )
 
 class EventBatchingConditionTypeDef(
     _RequiredEventBatchingConditionTypeDef, _OptionalEventBatchingConditionTypeDef
 ):
     pass
 
+CreateTriggerResponseTypeDef = TypedDict(
+    "CreateTriggerResponseTypeDef",
+    {
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateWorkflowRequestRequestTypeDef = TypedDict(
     "_RequiredCreateWorkflowRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalCreateWorkflowRequestRequestTypeDef = TypedDict(
@@ -2316,14 +2491,22 @@
 )
 
 class CreateWorkflowRequestRequestTypeDef(
     _RequiredCreateWorkflowRequestRequestTypeDef, _OptionalCreateWorkflowRequestRequestTypeDef
 ):
     pass
 
+CreateWorkflowResponseTypeDef = TypedDict(
+    "CreateWorkflowResponseTypeDef",
+    {
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DQResultsPublishingOptionsTypeDef = TypedDict(
     "DQResultsPublishingOptionsTypeDef",
     {
         "EvaluationContext": str,
         "ResultsS3Prefix": str,
         "CloudWatchMetricsEnabled": bool,
         "ResultsPublishingEnabled": bool,
@@ -2376,23 +2559,34 @@
 DataQualityRuleResultTypeDef = TypedDict(
     "DataQualityRuleResultTypeDef",
     {
         "Name": str,
         "Description": str,
         "EvaluationMessage": str,
         "Result": DataQualityRuleResultStatusType,
+        "EvaluatedMetrics": Dict[str, float],
     },
     total=False,
 )
 
 DatabaseIdentifierTypeDef = TypedDict(
     "DatabaseIdentifierTypeDef",
     {
         "CatalogId": str,
         "DatabaseName": str,
+        "Region": str,
+    },
+    total=False,
+)
+
+FederatedDatabaseTypeDef = TypedDict(
+    "FederatedDatabaseTypeDef",
+    {
+        "Identifier": str,
+        "ConnectionName": str,
     },
     total=False,
 )
 
 DatatypeTypeDef = TypedDict(
     "DatatypeTypeDef",
     {
@@ -2412,14 +2606,22 @@
 DeleteBlueprintRequestRequestTypeDef = TypedDict(
     "DeleteBlueprintRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+DeleteBlueprintResponseTypeDef = TypedDict(
+    "DeleteBlueprintResponseTypeDef",
+    {
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteClassifierRequestRequestTypeDef = TypedDict(
     "DeleteClassifierRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
@@ -2497,14 +2699,22 @@
 DeleteCustomEntityTypeRequestRequestTypeDef = TypedDict(
     "DeleteCustomEntityTypeRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+DeleteCustomEntityTypeResponseTypeDef = TypedDict(
+    "DeleteCustomEntityTypeResponseTypeDef",
+    {
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteDataQualityRulesetRequestRequestTypeDef = TypedDict(
     "DeleteDataQualityRulesetRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
@@ -2537,21 +2747,37 @@
 DeleteJobRequestRequestTypeDef = TypedDict(
     "DeleteJobRequestRequestTypeDef",
     {
         "JobName": str,
     },
 )
 
+DeleteJobResponseTypeDef = TypedDict(
+    "DeleteJobResponseTypeDef",
+    {
+        "JobName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteMLTransformRequestRequestTypeDef = TypedDict(
     "DeleteMLTransformRequestRequestTypeDef",
     {
         "TransformId": str,
     },
 )
 
+DeleteMLTransformResponseTypeDef = TypedDict(
+    "DeleteMLTransformResponseTypeDef",
+    {
+        "TransformId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeletePartitionIndexRequestRequestTypeDef = TypedDict(
     "_RequiredDeletePartitionIndexRequestRequestTypeDef",
     {
         "DatabaseName": str,
         "TableName": str,
         "IndexName": str,
     },
@@ -2587,14 +2813,24 @@
 )
 
 class DeletePartitionRequestRequestTypeDef(
     _RequiredDeletePartitionRequestRequestTypeDef, _OptionalDeletePartitionRequestRequestTypeDef
 ):
     pass
 
+DeleteRegistryResponseTypeDef = TypedDict(
+    "DeleteRegistryResponseTypeDef",
+    {
+        "RegistryName": str,
+        "RegistryArn": str,
+        "Status": RegistryStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteResourcePolicyRequestRequestTypeDef = TypedDict(
     "DeleteResourcePolicyRequestRequestTypeDef",
     {
         "PolicyHashCondition": str,
         "ResourceArn": str,
     },
     total=False,
@@ -2606,14 +2842,24 @@
         "SchemaArn": str,
         "SchemaName": str,
         "RegistryName": str,
     },
     total=False,
 )
 
+DeleteSchemaResponseTypeDef = TypedDict(
+    "DeleteSchemaResponseTypeDef",
+    {
+        "SchemaArn": str,
+        "SchemaName": str,
+        "Status": SchemaStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteSecurityConfigurationRequestRequestTypeDef = TypedDict(
     "DeleteSecurityConfigurationRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
@@ -2632,14 +2878,22 @@
 )
 
 class DeleteSessionRequestRequestTypeDef(
     _RequiredDeleteSessionRequestRequestTypeDef, _OptionalDeleteSessionRequestRequestTypeDef
 ):
     pass
 
+DeleteSessionResponseTypeDef = TypedDict(
+    "DeleteSessionResponseTypeDef",
+    {
+        "Id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteTableRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteTableRequestRequestTypeDef",
     {
         "DatabaseName": str,
         "Name": str,
     },
 )
@@ -2682,14 +2936,22 @@
 DeleteTriggerRequestRequestTypeDef = TypedDict(
     "DeleteTriggerRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+DeleteTriggerResponseTypeDef = TypedDict(
+    "DeleteTriggerResponseTypeDef",
+    {
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteUserDefinedFunctionRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteUserDefinedFunctionRequestRequestTypeDef",
     {
         "DatabaseName": str,
         "FunctionName": str,
     },
 )
@@ -2710,14 +2972,22 @@
 DeleteWorkflowRequestRequestTypeDef = TypedDict(
     "DeleteWorkflowRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+DeleteWorkflowResponseTypeDef = TypedDict(
+    "DeleteWorkflowResponseTypeDef",
+    {
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DevEndpointCustomLibrariesTypeDef = TypedDict(
     "DevEndpointCustomLibrariesTypeDef",
     {
         "ExtraPythonLibsS3Path": str,
         "ExtraJarsS3Path": str,
     },
     total=False,
@@ -2808,14 +3078,24 @@
     "ExportLabelsTaskRunPropertiesTypeDef",
     {
         "OutputS3Path": str,
     },
     total=False,
 )
 
+FederatedTableTypeDef = TypedDict(
+    "FederatedTableTypeDef",
+    {
+        "Identifier": str,
+        "DatabaseIdentifier": str,
+        "ConnectionName": str,
+    },
+    total=False,
+)
+
 FilterValueTypeDef = TypedDict(
     "FilterValueTypeDef",
     {
         "Type": FilterValueTypeType,
         "Value": List[str],
     },
 )
@@ -2900,20 +3180,18 @@
 GetClassifierRequestRequestTypeDef = TypedDict(
     "GetClassifierRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetClassifiersRequestGetClassifiersPaginateTypeDef = TypedDict(
+    "GetClassifiersRequestGetClassifiersPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 GetClassifiersRequestRequestTypeDef = TypedDict(
     "GetClassifiersRequestRequestTypeDef",
     {
@@ -2993,14 +3271,23 @@
     {
         "MatchCriteria": Sequence[str],
         "ConnectionType": ConnectionTypeType,
     },
     total=False,
 )
 
+GetCrawlerMetricsRequestGetCrawlerMetricsPaginateTypeDef = TypedDict(
+    "GetCrawlerMetricsRequestGetCrawlerMetricsPaginateTypeDef",
+    {
+        "CrawlerNameList": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetCrawlerMetricsRequestRequestTypeDef = TypedDict(
     "GetCrawlerMetricsRequestRequestTypeDef",
     {
         "CrawlerNameList": Sequence[str],
         "MaxResults": int,
         "NextToken": str,
     },
@@ -3010,14 +3297,22 @@
 GetCrawlerRequestRequestTypeDef = TypedDict(
     "GetCrawlerRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+GetCrawlersRequestGetCrawlersPaginateTypeDef = TypedDict(
+    "GetCrawlersRequestGetCrawlersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetCrawlersRequestRequestTypeDef = TypedDict(
     "GetCrawlersRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -3026,14 +3321,24 @@
 GetCustomEntityTypeRequestRequestTypeDef = TypedDict(
     "GetCustomEntityTypeRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+GetCustomEntityTypeResponseTypeDef = TypedDict(
+    "GetCustomEntityTypeResponseTypeDef",
+    {
+        "Name": str,
+        "RegexString": str,
+        "ContextWords": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetDataCatalogEncryptionSettingsRequestRequestTypeDef = TypedDict(
     "GetDataCatalogEncryptionSettingsRequestRequestTypeDef",
     {
         "CatalogId": str,
     },
     total=False,
 )
@@ -3081,14 +3386,24 @@
 )
 
 class GetDatabaseRequestRequestTypeDef(
     _RequiredGetDatabaseRequestRequestTypeDef, _OptionalGetDatabaseRequestRequestTypeDef
 ):
     pass
 
+GetDatabasesRequestGetDatabasesPaginateTypeDef = TypedDict(
+    "GetDatabasesRequestGetDatabasesPaginateTypeDef",
+    {
+        "CatalogId": str,
+        "ResourceShareType": ResourceShareTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetDatabasesRequestRequestTypeDef = TypedDict(
     "GetDatabasesRequestRequestTypeDef",
     {
         "CatalogId": str,
         "NextToken": str,
         "MaxResults": int,
         "ResourceShareType": ResourceShareTypeType,
@@ -3107,14 +3422,22 @@
 GetDevEndpointRequestRequestTypeDef = TypedDict(
     "GetDevEndpointRequestRequestTypeDef",
     {
         "EndpointName": str,
     },
 )
 
+GetDevEndpointsRequestGetDevEndpointsPaginateTypeDef = TypedDict(
+    "GetDevEndpointsRequestGetDevEndpointsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetDevEndpointsRequestRequestTypeDef = TypedDict(
     "GetDevEndpointsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -3176,14 +3499,34 @@
 )
 
 class GetJobRunRequestRequestTypeDef(
     _RequiredGetJobRunRequestRequestTypeDef, _OptionalGetJobRunRequestRequestTypeDef
 ):
     pass
 
+_RequiredGetJobRunsRequestGetJobRunsPaginateTypeDef = TypedDict(
+    "_RequiredGetJobRunsRequestGetJobRunsPaginateTypeDef",
+    {
+        "JobName": str,
+    },
+)
+_OptionalGetJobRunsRequestGetJobRunsPaginateTypeDef = TypedDict(
+    "_OptionalGetJobRunsRequestGetJobRunsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetJobRunsRequestGetJobRunsPaginateTypeDef(
+    _RequiredGetJobRunsRequestGetJobRunsPaginateTypeDef,
+    _OptionalGetJobRunsRequestGetJobRunsPaginateTypeDef,
+):
+    pass
+
 _RequiredGetJobRunsRequestRequestTypeDef = TypedDict(
     "_RequiredGetJobRunsRequestRequestTypeDef",
     {
         "JobName": str,
     },
 )
 _OptionalGetJobRunsRequestRequestTypeDef = TypedDict(
@@ -3196,14 +3539,22 @@
 )
 
 class GetJobRunsRequestRequestTypeDef(
     _RequiredGetJobRunsRequestRequestTypeDef, _OptionalGetJobRunsRequestRequestTypeDef
 ):
     pass
 
+GetJobsRequestGetJobsPaginateTypeDef = TypedDict(
+    "GetJobsRequestGetJobsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetJobsRequestRequestTypeDef = TypedDict(
     "GetJobsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
@@ -3269,14 +3620,36 @@
         "TargetTable": str,
         "TargetPath": str,
         "TargetType": str,
     },
     total=False,
 )
 
+_RequiredGetPartitionIndexesRequestGetPartitionIndexesPaginateTypeDef = TypedDict(
+    "_RequiredGetPartitionIndexesRequestGetPartitionIndexesPaginateTypeDef",
+    {
+        "DatabaseName": str,
+        "TableName": str,
+    },
+)
+_OptionalGetPartitionIndexesRequestGetPartitionIndexesPaginateTypeDef = TypedDict(
+    "_OptionalGetPartitionIndexesRequestGetPartitionIndexesPaginateTypeDef",
+    {
+        "CatalogId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetPartitionIndexesRequestGetPartitionIndexesPaginateTypeDef(
+    _RequiredGetPartitionIndexesRequestGetPartitionIndexesPaginateTypeDef,
+    _OptionalGetPartitionIndexesRequestGetPartitionIndexesPaginateTypeDef,
+):
+    pass
+
 _RequiredGetPartitionIndexesRequestRequestTypeDef = TypedDict(
     "_RequiredGetPartitionIndexesRequestRequestTypeDef",
     {
         "DatabaseName": str,
         "TableName": str,
     },
 )
@@ -3320,14 +3693,44 @@
     "SegmentTypeDef",
     {
         "SegmentNumber": int,
         "TotalSegments": int,
     },
 )
 
+GetPlanResponseTypeDef = TypedDict(
+    "GetPlanResponseTypeDef",
+    {
+        "PythonScript": str,
+        "ScalaCode": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetRegistryResponseTypeDef = TypedDict(
+    "GetRegistryResponseTypeDef",
+    {
+        "RegistryName": str,
+        "RegistryArn": str,
+        "Description": str,
+        "Status": RegistryStatusType,
+        "CreatedTime": str,
+        "UpdatedTime": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef = TypedDict(
+    "GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetResourcePoliciesRequestRequestTypeDef = TypedDict(
     "GetResourcePoliciesRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
@@ -3348,30 +3751,103 @@
     "GetResourcePolicyRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
     total=False,
 )
 
+GetResourcePolicyResponseTypeDef = TypedDict(
+    "GetResourcePolicyResponseTypeDef",
+    {
+        "PolicyInJson": str,
+        "PolicyHash": str,
+        "CreateTime": datetime,
+        "UpdateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetSchemaByDefinitionResponseTypeDef = TypedDict(
+    "GetSchemaByDefinitionResponseTypeDef",
+    {
+        "SchemaVersionId": str,
+        "SchemaArn": str,
+        "DataFormat": DataFormatType,
+        "Status": SchemaVersionStatusType,
+        "CreatedTime": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetSchemaResponseTypeDef = TypedDict(
+    "GetSchemaResponseTypeDef",
+    {
+        "RegistryName": str,
+        "RegistryArn": str,
+        "SchemaName": str,
+        "SchemaArn": str,
+        "Description": str,
+        "DataFormat": DataFormatType,
+        "Compatibility": CompatibilityType,
+        "SchemaCheckpoint": int,
+        "LatestSchemaVersion": int,
+        "NextSchemaVersion": int,
+        "SchemaStatus": SchemaStatusType,
+        "CreatedTime": str,
+        "UpdatedTime": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 SchemaVersionNumberTypeDef = TypedDict(
     "SchemaVersionNumberTypeDef",
     {
         "LatestVersion": bool,
         "VersionNumber": int,
     },
     total=False,
 )
 
+GetSchemaVersionResponseTypeDef = TypedDict(
+    "GetSchemaVersionResponseTypeDef",
+    {
+        "SchemaVersionId": str,
+        "SchemaDefinition": str,
+        "DataFormat": DataFormatType,
+        "SchemaArn": str,
+        "VersionNumber": int,
+        "Status": SchemaVersionStatusType,
+        "CreatedTime": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetSchemaVersionsDiffResponseTypeDef = TypedDict(
+    "GetSchemaVersionsDiffResponseTypeDef",
+    {
+        "Diff": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetSecurityConfigurationRequestRequestTypeDef = TypedDict(
     "GetSecurityConfigurationRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+GetSecurityConfigurationsRequestGetSecurityConfigurationsPaginateTypeDef = TypedDict(
+    "GetSecurityConfigurationsRequestGetSecurityConfigurationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetSecurityConfigurationsRequestRequestTypeDef = TypedDict(
     "GetSecurityConfigurationsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -3455,14 +3931,36 @@
 )
 
 class GetTableVersionRequestRequestTypeDef(
     _RequiredGetTableVersionRequestRequestTypeDef, _OptionalGetTableVersionRequestRequestTypeDef
 ):
     pass
 
+_RequiredGetTableVersionsRequestGetTableVersionsPaginateTypeDef = TypedDict(
+    "_RequiredGetTableVersionsRequestGetTableVersionsPaginateTypeDef",
+    {
+        "DatabaseName": str,
+        "TableName": str,
+    },
+)
+_OptionalGetTableVersionsRequestGetTableVersionsPaginateTypeDef = TypedDict(
+    "_OptionalGetTableVersionsRequestGetTableVersionsPaginateTypeDef",
+    {
+        "CatalogId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetTableVersionsRequestGetTableVersionsPaginateTypeDef(
+    _RequiredGetTableVersionsRequestGetTableVersionsPaginateTypeDef,
+    _OptionalGetTableVersionsRequestGetTableVersionsPaginateTypeDef,
+):
+    pass
+
 _RequiredGetTableVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredGetTableVersionsRequestRequestTypeDef",
     {
         "DatabaseName": str,
         "TableName": str,
     },
 )
@@ -3477,14 +3975,38 @@
 )
 
 class GetTableVersionsRequestRequestTypeDef(
     _RequiredGetTableVersionsRequestRequestTypeDef, _OptionalGetTableVersionsRequestRequestTypeDef
 ):
     pass
 
+_RequiredGetTablesRequestGetTablesPaginateTypeDef = TypedDict(
+    "_RequiredGetTablesRequestGetTablesPaginateTypeDef",
+    {
+        "DatabaseName": str,
+    },
+)
+_OptionalGetTablesRequestGetTablesPaginateTypeDef = TypedDict(
+    "_OptionalGetTablesRequestGetTablesPaginateTypeDef",
+    {
+        "CatalogId": str,
+        "Expression": str,
+        "TransactionId": str,
+        "QueryAsOfTime": Union[datetime, str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetTablesRequestGetTablesPaginateTypeDef(
+    _RequiredGetTablesRequestGetTablesPaginateTypeDef,
+    _OptionalGetTablesRequestGetTablesPaginateTypeDef,
+):
+    pass
+
 _RequiredGetTablesRequestRequestTypeDef = TypedDict(
     "_RequiredGetTablesRequestRequestTypeDef",
     {
         "DatabaseName": str,
     },
 )
 _OptionalGetTablesRequestRequestTypeDef = TypedDict(
@@ -3508,21 +4030,38 @@
 GetTagsRequestRequestTypeDef = TypedDict(
     "GetTagsRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+GetTagsResponseTypeDef = TypedDict(
+    "GetTagsResponseTypeDef",
+    {
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetTriggerRequestRequestTypeDef = TypedDict(
     "GetTriggerRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+GetTriggersRequestGetTriggersPaginateTypeDef = TypedDict(
+    "GetTriggersRequestGetTriggersPaginateTypeDef",
+    {
+        "DependentJobName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetTriggersRequestRequestTypeDef = TypedDict(
     "GetTriggersRequestRequestTypeDef",
     {
         "NextToken": str,
         "DependentJobName": str,
         "MaxResults": int,
     },
@@ -3546,14 +4085,36 @@
 
 class GetUserDefinedFunctionRequestRequestTypeDef(
     _RequiredGetUserDefinedFunctionRequestRequestTypeDef,
     _OptionalGetUserDefinedFunctionRequestRequestTypeDef,
 ):
     pass
 
+_RequiredGetUserDefinedFunctionsRequestGetUserDefinedFunctionsPaginateTypeDef = TypedDict(
+    "_RequiredGetUserDefinedFunctionsRequestGetUserDefinedFunctionsPaginateTypeDef",
+    {
+        "Pattern": str,
+    },
+)
+_OptionalGetUserDefinedFunctionsRequestGetUserDefinedFunctionsPaginateTypeDef = TypedDict(
+    "_OptionalGetUserDefinedFunctionsRequestGetUserDefinedFunctionsPaginateTypeDef",
+    {
+        "CatalogId": str,
+        "DatabaseName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetUserDefinedFunctionsRequestGetUserDefinedFunctionsPaginateTypeDef(
+    _RequiredGetUserDefinedFunctionsRequestGetUserDefinedFunctionsPaginateTypeDef,
+    _OptionalGetUserDefinedFunctionsRequestGetUserDefinedFunctionsPaginateTypeDef,
+):
+    pass
+
 _RequiredGetUserDefinedFunctionsRequestRequestTypeDef = TypedDict(
     "_RequiredGetUserDefinedFunctionsRequestRequestTypeDef",
     {
         "Pattern": str,
     },
 )
 _OptionalGetUserDefinedFunctionsRequestRequestTypeDef = TypedDict(
@@ -3596,14 +4157,22 @@
     "GetWorkflowRunPropertiesRequestRequestTypeDef",
     {
         "Name": str,
         "RunId": str,
     },
 )
 
+GetWorkflowRunPropertiesResponseTypeDef = TypedDict(
+    "GetWorkflowRunPropertiesResponseTypeDef",
+    {
+        "RunProperties": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetWorkflowRunRequestRequestTypeDef = TypedDict(
     "_RequiredGetWorkflowRunRequestRequestTypeDef",
     {
         "Name": str,
         "RunId": str,
     },
 )
@@ -3740,53 +4309,107 @@
         "NextToken": str,
         "MaxResults": int,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
+ListBlueprintsResponseTypeDef = TypedDict(
+    "ListBlueprintsResponseTypeDef",
+    {
+        "Blueprints": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListCrawlersRequestRequestTypeDef = TypedDict(
     "ListCrawlersRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
+ListCrawlersResponseTypeDef = TypedDict(
+    "ListCrawlersResponseTypeDef",
+    {
+        "CrawlerNames": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListCustomEntityTypesRequestRequestTypeDef = TypedDict(
     "ListCustomEntityTypesRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
+        "Tags": Mapping[str, str],
     },
     total=False,
 )
 
 ListDevEndpointsRequestRequestTypeDef = TypedDict(
     "ListDevEndpointsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
+ListDevEndpointsResponseTypeDef = TypedDict(
+    "ListDevEndpointsResponseTypeDef",
+    {
+        "DevEndpointNames": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListJobsRequestRequestTypeDef = TypedDict(
     "ListJobsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
+ListJobsResponseTypeDef = TypedDict(
+    "ListJobsResponseTypeDef",
+    {
+        "JobNames": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListMLTransformsResponseTypeDef = TypedDict(
+    "ListMLTransformsResponseTypeDef",
+    {
+        "TransformIds": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListRegistriesInputListRegistriesPaginateTypeDef = TypedDict(
+    "ListRegistriesInputListRegistriesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListRegistriesInputRequestTypeDef = TypedDict(
     "ListRegistriesInputRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -3869,23 +4492,41 @@
         "DependentJobName": str,
         "MaxResults": int,
         "Tags": Mapping[str, str],
     },
     total=False,
 )
 
+ListTriggersResponseTypeDef = TypedDict(
+    "ListTriggersResponseTypeDef",
+    {
+        "TriggerNames": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListWorkflowsRequestRequestTypeDef = TypedDict(
     "ListWorkflowsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListWorkflowsResponseTypeDef = TypedDict(
+    "ListWorkflowsResponseTypeDef",
+    {
+        "Workflows": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredMLUserDataEncryptionTypeDef = TypedDict(
     "_RequiredMLUserDataEncryptionTypeDef",
     {
         "MlUserDataEncryptionMode": MLUserDataEncryptionModeStringType,
     },
 )
 _OptionalMLUserDataEncryptionTypeDef = TypedDict(
@@ -3936,14 +4577,24 @@
     "OrderTypeDef",
     {
         "Column": str,
         "SortOrder": int,
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
 PropertyPredicateTypeDef = TypedDict(
     "PropertyPredicateTypeDef",
     {
         "Key": str,
         "Value": str,
         "Comparator": ComparatorType,
     },
@@ -3968,14 +4619,37 @@
 )
 
 class PutResourcePolicyRequestRequestTypeDef(
     _RequiredPutResourcePolicyRequestRequestTypeDef, _OptionalPutResourcePolicyRequestRequestTypeDef
 ):
     pass
 
+PutResourcePolicyResponseTypeDef = TypedDict(
+    "PutResourcePolicyResponseTypeDef",
+    {
+        "PolicyHash": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+PutSchemaVersionMetadataResponseTypeDef = TypedDict(
+    "PutSchemaVersionMetadataResponseTypeDef",
+    {
+        "SchemaArn": str,
+        "SchemaName": str,
+        "RegistryName": str,
+        "LatestVersion": bool,
+        "VersionNumber": int,
+        "SchemaVersionId": str,
+        "MetadataKey": str,
+        "MetadataValue": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 PutWorkflowRunPropertiesRequestRequestTypeDef = TypedDict(
     "PutWorkflowRunPropertiesRequestRequestTypeDef",
     {
         "Name": str,
         "RunId": str,
         "RunProperties": Mapping[str, str],
     },
@@ -3987,14 +4661,39 @@
         "TableLocation": str,
         "ConnectionName": str,
         "UpsertKeys": List[str],
     },
     total=False,
 )
 
+RegisterSchemaVersionResponseTypeDef = TypedDict(
+    "RegisterSchemaVersionResponseTypeDef",
+    {
+        "SchemaVersionId": str,
+        "VersionNumber": int,
+        "Status": SchemaVersionStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+RemoveSchemaVersionMetadataResponseTypeDef = TypedDict(
+    "RemoveSchemaVersionMetadataResponseTypeDef",
+    {
+        "SchemaArn": str,
+        "SchemaName": str,
+        "RegistryName": str,
+        "LatestVersion": bool,
+        "VersionNumber": int,
+        "SchemaVersionId": str,
+        "MetadataKey": str,
+        "MetadataValue": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredResetJobBookmarkRequestRequestTypeDef = TypedDict(
     "_RequiredResetJobBookmarkRequestRequestTypeDef",
     {
         "JobName": str,
     },
 )
 _OptionalResetJobBookmarkRequestRequestTypeDef = TypedDict(
@@ -4015,23 +4714,43 @@
     {
         "ResourceType": ResourceTypeType,
         "Uri": str,
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
 ResumeWorkflowRunRequestRequestTypeDef = TypedDict(
     "ResumeWorkflowRunRequestRequestTypeDef",
     {
         "Name": str,
         "RunId": str,
         "NodeIds": Sequence[str],
     },
 )
 
+ResumeWorkflowRunResponseTypeDef = TypedDict(
+    "ResumeWorkflowRunResponseTypeDef",
+    {
+        "RunId": str,
+        "NodeIds": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredRunStatementRequestRequestTypeDef = TypedDict(
     "_RequiredRunStatementRequestRequestTypeDef",
     {
         "SessionId": str,
         "Code": str,
     },
 )
@@ -4044,14 +4763,22 @@
 )
 
 class RunStatementRequestRequestTypeDef(
     _RequiredRunStatementRequestRequestTypeDef, _OptionalRunStatementRequestRequestTypeDef
 ):
     pass
 
+RunStatementResponseTypeDef = TypedDict(
+    "RunStatementResponseTypeDef",
+    {
+        "Id": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 S3DirectSourceAdditionalOptionsTypeDef = TypedDict(
     "S3DirectSourceAdditionalOptionsTypeDef",
     {
         "BoundedSize": int,
         "BoundedFiles": int,
         "EnableSamplePath": bool,
         "SamplePath": str,
@@ -4112,36 +4839,68 @@
 )
 
 class StartBlueprintRunRequestRequestTypeDef(
     _RequiredStartBlueprintRunRequestRequestTypeDef, _OptionalStartBlueprintRunRequestRequestTypeDef
 ):
     pass
 
+StartBlueprintRunResponseTypeDef = TypedDict(
+    "StartBlueprintRunResponseTypeDef",
+    {
+        "RunId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartCrawlerRequestRequestTypeDef = TypedDict(
     "StartCrawlerRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
 StartCrawlerScheduleRequestRequestTypeDef = TypedDict(
     "StartCrawlerScheduleRequestRequestTypeDef",
     {
         "CrawlerName": str,
     },
 )
 
+StartDataQualityRuleRecommendationRunResponseTypeDef = TypedDict(
+    "StartDataQualityRuleRecommendationRunResponseTypeDef",
+    {
+        "RunId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartDataQualityRulesetEvaluationRunResponseTypeDef = TypedDict(
+    "StartDataQualityRulesetEvaluationRunResponseTypeDef",
+    {
+        "RunId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartExportLabelsTaskRunRequestRequestTypeDef = TypedDict(
     "StartExportLabelsTaskRunRequestRequestTypeDef",
     {
         "TransformId": str,
         "OutputS3Path": str,
     },
 )
 
+StartExportLabelsTaskRunResponseTypeDef = TypedDict(
+    "StartExportLabelsTaskRunResponseTypeDef",
+    {
+        "TaskRunId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredStartImportLabelsTaskRunRequestRequestTypeDef = TypedDict(
     "_RequiredStartImportLabelsTaskRunRequestRequestTypeDef",
     {
         "TransformId": str,
         "InputS3Path": str,
     },
 )
@@ -4155,36 +4914,76 @@
 
 class StartImportLabelsTaskRunRequestRequestTypeDef(
     _RequiredStartImportLabelsTaskRunRequestRequestTypeDef,
     _OptionalStartImportLabelsTaskRunRequestRequestTypeDef,
 ):
     pass
 
+StartImportLabelsTaskRunResponseTypeDef = TypedDict(
+    "StartImportLabelsTaskRunResponseTypeDef",
+    {
+        "TaskRunId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartJobRunResponseTypeDef = TypedDict(
+    "StartJobRunResponseTypeDef",
+    {
+        "JobRunId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartMLEvaluationTaskRunRequestRequestTypeDef = TypedDict(
     "StartMLEvaluationTaskRunRequestRequestTypeDef",
     {
         "TransformId": str,
     },
 )
 
+StartMLEvaluationTaskRunResponseTypeDef = TypedDict(
+    "StartMLEvaluationTaskRunResponseTypeDef",
+    {
+        "TaskRunId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartMLLabelingSetGenerationTaskRunRequestRequestTypeDef = TypedDict(
     "StartMLLabelingSetGenerationTaskRunRequestRequestTypeDef",
     {
         "TransformId": str,
         "OutputS3Path": str,
     },
 )
 
+StartMLLabelingSetGenerationTaskRunResponseTypeDef = TypedDict(
+    "StartMLLabelingSetGenerationTaskRunResponseTypeDef",
+    {
+        "TaskRunId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartTriggerRequestRequestTypeDef = TypedDict(
     "StartTriggerRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+StartTriggerResponseTypeDef = TypedDict(
+    "StartTriggerResponseTypeDef",
+    {
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredStartWorkflowRunRequestRequestTypeDef = TypedDict(
     "_RequiredStartWorkflowRunRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalStartWorkflowRunRequestRequestTypeDef = TypedDict(
@@ -4196,14 +4995,22 @@
 )
 
 class StartWorkflowRunRequestRequestTypeDef(
     _RequiredStartWorkflowRunRequestRequestTypeDef, _OptionalStartWorkflowRunRequestRequestTypeDef
 ):
     pass
 
+StartWorkflowRunResponseTypeDef = TypedDict(
+    "StartWorkflowRunResponseTypeDef",
+    {
+        "RunId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartingEventBatchConditionTypeDef = TypedDict(
     "StartingEventBatchConditionTypeDef",
     {
         "BatchSize": int,
         "BatchWindow": int,
     },
     total=False,
@@ -4246,35 +5053,52 @@
 )
 
 class StopSessionRequestRequestTypeDef(
     _RequiredStopSessionRequestRequestTypeDef, _OptionalStopSessionRequestRequestTypeDef
 ):
     pass
 
+StopSessionResponseTypeDef = TypedDict(
+    "StopSessionResponseTypeDef",
+    {
+        "Id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopTriggerRequestRequestTypeDef = TypedDict(
     "StopTriggerRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+StopTriggerResponseTypeDef = TypedDict(
+    "StopTriggerResponseTypeDef",
+    {
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopWorkflowRunRequestRequestTypeDef = TypedDict(
     "StopWorkflowRunRequestRequestTypeDef",
     {
         "Name": str,
         "RunId": str,
     },
 )
 
 TableIdentifierTypeDef = TypedDict(
     "TableIdentifierTypeDef",
     {
         "CatalogId": str,
         "DatabaseName": str,
         "Name": str,
+        "Region": str,
     },
     total=False,
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
@@ -4307,14 +5131,22 @@
 )
 
 class UpdateBlueprintRequestRequestTypeDef(
     _RequiredUpdateBlueprintRequestRequestTypeDef, _OptionalUpdateBlueprintRequestRequestTypeDef
 ):
     pass
 
+UpdateBlueprintResponseTypeDef = TypedDict(
+    "UpdateBlueprintResponseTypeDef",
+    {
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateCsvClassifierRequestTypeDef = TypedDict(
     "_RequiredUpdateCsvClassifierRequestTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalUpdateCsvClassifierRequestTypeDef = TypedDict(
@@ -4422,27 +5254,36 @@
     {
         "Name": str,
     },
 )
 _OptionalUpdateDataQualityRulesetRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateDataQualityRulesetRequestRequestTypeDef",
     {
-        "UpdatedName": str,
         "Description": str,
         "Ruleset": str,
     },
     total=False,
 )
 
 class UpdateDataQualityRulesetRequestRequestTypeDef(
     _RequiredUpdateDataQualityRulesetRequestRequestTypeDef,
     _OptionalUpdateDataQualityRulesetRequestRequestTypeDef,
 ):
     pass
 
+UpdateDataQualityRulesetResponseTypeDef = TypedDict(
+    "UpdateDataQualityRulesetResponseTypeDef",
+    {
+        "Name": str,
+        "Description": str,
+        "Ruleset": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateJobFromSourceControlRequestRequestTypeDef = TypedDict(
     "UpdateJobFromSourceControlRequestRequestTypeDef",
     {
         "JobName": str,
         "Provider": SourceControlProviderType,
         "RepositoryName": str,
         "RepositoryOwner": str,
@@ -4451,14 +5292,57 @@
         "CommitId": str,
         "AuthStrategy": SourceControlAuthStrategyType,
         "AuthToken": str,
     },
     total=False,
 )
 
+UpdateJobFromSourceControlResponseTypeDef = TypedDict(
+    "UpdateJobFromSourceControlResponseTypeDef",
+    {
+        "JobName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateJobResponseTypeDef = TypedDict(
+    "UpdateJobResponseTypeDef",
+    {
+        "JobName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateMLTransformResponseTypeDef = TypedDict(
+    "UpdateMLTransformResponseTypeDef",
+    {
+        "TransformId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateRegistryResponseTypeDef = TypedDict(
+    "UpdateRegistryResponseTypeDef",
+    {
+        "RegistryName": str,
+        "RegistryArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateSchemaResponseTypeDef = TypedDict(
+    "UpdateSchemaResponseTypeDef",
+    {
+        "SchemaArn": str,
+        "SchemaName": str,
+        "RegistryName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateSourceControlFromJobRequestRequestTypeDef = TypedDict(
     "UpdateSourceControlFromJobRequestRequestTypeDef",
     {
         "JobName": str,
         "Provider": SourceControlProviderType,
         "RepositoryName": str,
         "RepositoryOwner": str,
@@ -4467,14 +5351,22 @@
         "CommitId": str,
         "AuthStrategy": SourceControlAuthStrategyType,
         "AuthToken": str,
     },
     total=False,
 )
 
+UpdateSourceControlFromJobResponseTypeDef = TypedDict(
+    "UpdateSourceControlFromJobResponseTypeDef",
+    {
+        "JobName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateWorkflowRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateWorkflowRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalUpdateWorkflowRequestRequestTypeDef = TypedDict(
@@ -4488,14 +5380,22 @@
 )
 
 class UpdateWorkflowRequestRequestTypeDef(
     _RequiredUpdateWorkflowRequestRequestTypeDef, _OptionalUpdateWorkflowRequestRequestTypeDef
 ):
     pass
 
+UpdateWorkflowResponseTypeDef = TypedDict(
+    "UpdateWorkflowResponseTypeDef",
+    {
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 WorkflowRunStatisticsTypeDef = TypedDict(
     "WorkflowRunStatisticsTypeDef",
     {
         "TotalActions": int,
         "TimeoutActions": int,
         "FailedActions": int,
         "StoppedActions": int,
@@ -4554,14 +5454,47 @@
         "Name": str,
         "Inputs": List[str],
         "Groups": List[List[str]],
         "Aggs": List[AggregateOperationTypeDef],
     },
 )
 
+AmazonRedshiftNodeDataTypeDef = TypedDict(
+    "AmazonRedshiftNodeDataTypeDef",
+    {
+        "AccessType": str,
+        "SourceType": str,
+        "Connection": OptionTypeDef,
+        "Schema": OptionTypeDef,
+        "Table": OptionTypeDef,
+        "CatalogDatabase": OptionTypeDef,
+        "CatalogTable": OptionTypeDef,
+        "CatalogRedshiftSchema": str,
+        "CatalogRedshiftTable": str,
+        "TempDir": str,
+        "IamRole": OptionTypeDef,
+        "AdvancedOptions": List[AmazonRedshiftAdvancedOptionTypeDef],
+        "SampleQuery": str,
+        "PreAction": str,
+        "PostAction": str,
+        "Action": str,
+        "TablePrefix": str,
+        "Upsert": bool,
+        "MergeAction": str,
+        "MergeWhenMatched": str,
+        "MergeWhenNotMatched": str,
+        "MergeClause": str,
+        "CrawlerConnection": str,
+        "TableSchema": List[OptionTypeDef],
+        "StagingTable": str,
+        "SelectedColumns": List[OptionTypeDef],
+    },
+    total=False,
+)
+
 _RequiredGetUnfilteredPartitionMetadataRequestRequestTypeDef = TypedDict(
     "_RequiredGetUnfilteredPartitionMetadataRequestRequestTypeDef",
     {
         "CatalogId": str,
         "DatabaseName": str,
         "TableName": str,
         "PartitionValues": Sequence[str],
@@ -4653,661 +5586,20 @@
 )
 
 class BatchGetPartitionRequestRequestTypeDef(
     _RequiredBatchGetPartitionRequestRequestTypeDef, _OptionalBatchGetPartitionRequestRequestTypeDef
 ):
     pass
 
-CancelMLTaskRunResponseTypeDef = TypedDict(
-    "CancelMLTaskRunResponseTypeDef",
-    {
-        "TransformId": str,
-        "TaskRunId": str,
-        "Status": TaskStatusTypeType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CheckSchemaVersionValidityResponseTypeDef = TypedDict(
-    "CheckSchemaVersionValidityResponseTypeDef",
-    {
-        "Valid": bool,
-        "Error": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateBlueprintResponseTypeDef = TypedDict(
-    "CreateBlueprintResponseTypeDef",
-    {
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateCustomEntityTypeResponseTypeDef = TypedDict(
-    "CreateCustomEntityTypeResponseTypeDef",
-    {
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDataQualityRulesetResponseTypeDef = TypedDict(
-    "CreateDataQualityRulesetResponseTypeDef",
-    {
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDevEndpointResponseTypeDef = TypedDict(
-    "CreateDevEndpointResponseTypeDef",
-    {
-        "EndpointName": str,
-        "Status": str,
-        "SecurityGroupIds": List[str],
-        "SubnetId": str,
-        "RoleArn": str,
-        "YarnEndpointAddress": str,
-        "ZeppelinRemoteSparkInterpreterPort": int,
-        "NumberOfNodes": int,
-        "WorkerType": WorkerTypeType,
-        "GlueVersion": str,
-        "NumberOfWorkers": int,
-        "AvailabilityZone": str,
-        "VpcId": str,
-        "ExtraPythonLibsS3Path": str,
-        "ExtraJarsS3Path": str,
-        "FailureReason": str,
-        "SecurityConfiguration": str,
-        "CreatedTimestamp": datetime,
-        "Arguments": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateJobResponseTypeDef = TypedDict(
-    "CreateJobResponseTypeDef",
-    {
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateMLTransformResponseTypeDef = TypedDict(
-    "CreateMLTransformResponseTypeDef",
-    {
-        "TransformId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateRegistryResponseTypeDef = TypedDict(
-    "CreateRegistryResponseTypeDef",
-    {
-        "RegistryArn": str,
-        "RegistryName": str,
-        "Description": str,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateSchemaResponseTypeDef = TypedDict(
-    "CreateSchemaResponseTypeDef",
-    {
-        "RegistryName": str,
-        "RegistryArn": str,
-        "SchemaName": str,
-        "SchemaArn": str,
-        "Description": str,
-        "DataFormat": DataFormatType,
-        "Compatibility": CompatibilityType,
-        "SchemaCheckpoint": int,
-        "LatestSchemaVersion": int,
-        "NextSchemaVersion": int,
-        "SchemaStatus": SchemaStatusType,
-        "Tags": Dict[str, str],
-        "SchemaVersionId": str,
-        "SchemaVersionStatus": SchemaVersionStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateScriptResponseTypeDef = TypedDict(
-    "CreateScriptResponseTypeDef",
-    {
-        "PythonScript": str,
-        "ScalaCode": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateSecurityConfigurationResponseTypeDef = TypedDict(
-    "CreateSecurityConfigurationResponseTypeDef",
-    {
-        "Name": str,
-        "CreatedTimestamp": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateTriggerResponseTypeDef = TypedDict(
-    "CreateTriggerResponseTypeDef",
-    {
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateWorkflowResponseTypeDef = TypedDict(
-    "CreateWorkflowResponseTypeDef",
-    {
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteBlueprintResponseTypeDef = TypedDict(
-    "DeleteBlueprintResponseTypeDef",
-    {
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteCustomEntityTypeResponseTypeDef = TypedDict(
-    "DeleteCustomEntityTypeResponseTypeDef",
-    {
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteJobResponseTypeDef = TypedDict(
-    "DeleteJobResponseTypeDef",
-    {
-        "JobName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteMLTransformResponseTypeDef = TypedDict(
-    "DeleteMLTransformResponseTypeDef",
-    {
-        "TransformId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteRegistryResponseTypeDef = TypedDict(
-    "DeleteRegistryResponseTypeDef",
-    {
-        "RegistryName": str,
-        "RegistryArn": str,
-        "Status": RegistryStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteSchemaResponseTypeDef = TypedDict(
-    "DeleteSchemaResponseTypeDef",
-    {
-        "SchemaArn": str,
-        "SchemaName": str,
-        "Status": SchemaStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteSessionResponseTypeDef = TypedDict(
-    "DeleteSessionResponseTypeDef",
-    {
-        "Id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteTriggerResponseTypeDef = TypedDict(
-    "DeleteTriggerResponseTypeDef",
-    {
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteWorkflowResponseTypeDef = TypedDict(
-    "DeleteWorkflowResponseTypeDef",
-    {
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetCustomEntityTypeResponseTypeDef = TypedDict(
-    "GetCustomEntityTypeResponseTypeDef",
-    {
-        "Name": str,
-        "RegexString": str,
-        "ContextWords": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetPlanResponseTypeDef = TypedDict(
-    "GetPlanResponseTypeDef",
-    {
-        "PythonScript": str,
-        "ScalaCode": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetRegistryResponseTypeDef = TypedDict(
-    "GetRegistryResponseTypeDef",
-    {
-        "RegistryName": str,
-        "RegistryArn": str,
-        "Description": str,
-        "Status": RegistryStatusType,
-        "CreatedTime": str,
-        "UpdatedTime": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetResourcePolicyResponseTypeDef = TypedDict(
-    "GetResourcePolicyResponseTypeDef",
-    {
-        "PolicyInJson": str,
-        "PolicyHash": str,
-        "CreateTime": datetime,
-        "UpdateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSchemaByDefinitionResponseTypeDef = TypedDict(
-    "GetSchemaByDefinitionResponseTypeDef",
-    {
-        "SchemaVersionId": str,
-        "SchemaArn": str,
-        "DataFormat": DataFormatType,
-        "Status": SchemaVersionStatusType,
-        "CreatedTime": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSchemaResponseTypeDef = TypedDict(
-    "GetSchemaResponseTypeDef",
-    {
-        "RegistryName": str,
-        "RegistryArn": str,
-        "SchemaName": str,
-        "SchemaArn": str,
-        "Description": str,
-        "DataFormat": DataFormatType,
-        "Compatibility": CompatibilityType,
-        "SchemaCheckpoint": int,
-        "LatestSchemaVersion": int,
-        "NextSchemaVersion": int,
-        "SchemaStatus": SchemaStatusType,
-        "CreatedTime": str,
-        "UpdatedTime": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSchemaVersionResponseTypeDef = TypedDict(
-    "GetSchemaVersionResponseTypeDef",
-    {
-        "SchemaVersionId": str,
-        "SchemaDefinition": str,
-        "DataFormat": DataFormatType,
-        "SchemaArn": str,
-        "VersionNumber": int,
-        "Status": SchemaVersionStatusType,
-        "CreatedTime": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSchemaVersionsDiffResponseTypeDef = TypedDict(
-    "GetSchemaVersionsDiffResponseTypeDef",
-    {
-        "Diff": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetTagsResponseTypeDef = TypedDict(
-    "GetTagsResponseTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetWorkflowRunPropertiesResponseTypeDef = TypedDict(
-    "GetWorkflowRunPropertiesResponseTypeDef",
-    {
-        "RunProperties": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListBlueprintsResponseTypeDef = TypedDict(
-    "ListBlueprintsResponseTypeDef",
-    {
-        "Blueprints": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListCrawlersResponseTypeDef = TypedDict(
-    "ListCrawlersResponseTypeDef",
-    {
-        "CrawlerNames": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDevEndpointsResponseTypeDef = TypedDict(
-    "ListDevEndpointsResponseTypeDef",
-    {
-        "DevEndpointNames": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListJobsResponseTypeDef = TypedDict(
-    "ListJobsResponseTypeDef",
-    {
-        "JobNames": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListMLTransformsResponseTypeDef = TypedDict(
-    "ListMLTransformsResponseTypeDef",
-    {
-        "TransformIds": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTriggersResponseTypeDef = TypedDict(
-    "ListTriggersResponseTypeDef",
-    {
-        "TriggerNames": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListWorkflowsResponseTypeDef = TypedDict(
-    "ListWorkflowsResponseTypeDef",
-    {
-        "Workflows": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutResourcePolicyResponseTypeDef = TypedDict(
-    "PutResourcePolicyResponseTypeDef",
-    {
-        "PolicyHash": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutSchemaVersionMetadataResponseTypeDef = TypedDict(
-    "PutSchemaVersionMetadataResponseTypeDef",
-    {
-        "SchemaArn": str,
-        "SchemaName": str,
-        "RegistryName": str,
-        "LatestVersion": bool,
-        "VersionNumber": int,
-        "SchemaVersionId": str,
-        "MetadataKey": str,
-        "MetadataValue": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RegisterSchemaVersionResponseTypeDef = TypedDict(
-    "RegisterSchemaVersionResponseTypeDef",
-    {
-        "SchemaVersionId": str,
-        "VersionNumber": int,
-        "Status": SchemaVersionStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RemoveSchemaVersionMetadataResponseTypeDef = TypedDict(
-    "RemoveSchemaVersionMetadataResponseTypeDef",
-    {
-        "SchemaArn": str,
-        "SchemaName": str,
-        "RegistryName": str,
-        "LatestVersion": bool,
-        "VersionNumber": int,
-        "SchemaVersionId": str,
-        "MetadataKey": str,
-        "MetadataValue": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ResumeWorkflowRunResponseTypeDef = TypedDict(
-    "ResumeWorkflowRunResponseTypeDef",
-    {
-        "RunId": str,
-        "NodeIds": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RunStatementResponseTypeDef = TypedDict(
-    "RunStatementResponseTypeDef",
-    {
-        "Id": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartBlueprintRunResponseTypeDef = TypedDict(
-    "StartBlueprintRunResponseTypeDef",
-    {
-        "RunId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartDataQualityRuleRecommendationRunResponseTypeDef = TypedDict(
-    "StartDataQualityRuleRecommendationRunResponseTypeDef",
-    {
-        "RunId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartDataQualityRulesetEvaluationRunResponseTypeDef = TypedDict(
-    "StartDataQualityRulesetEvaluationRunResponseTypeDef",
-    {
-        "RunId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartExportLabelsTaskRunResponseTypeDef = TypedDict(
-    "StartExportLabelsTaskRunResponseTypeDef",
-    {
-        "TaskRunId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartImportLabelsTaskRunResponseTypeDef = TypedDict(
-    "StartImportLabelsTaskRunResponseTypeDef",
-    {
-        "TaskRunId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartJobRunResponseTypeDef = TypedDict(
-    "StartJobRunResponseTypeDef",
-    {
-        "JobRunId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartMLEvaluationTaskRunResponseTypeDef = TypedDict(
-    "StartMLEvaluationTaskRunResponseTypeDef",
-    {
-        "TaskRunId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartMLLabelingSetGenerationTaskRunResponseTypeDef = TypedDict(
-    "StartMLLabelingSetGenerationTaskRunResponseTypeDef",
-    {
-        "TaskRunId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartTriggerResponseTypeDef = TypedDict(
-    "StartTriggerResponseTypeDef",
-    {
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartWorkflowRunResponseTypeDef = TypedDict(
-    "StartWorkflowRunResponseTypeDef",
-    {
-        "RunId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StopSessionResponseTypeDef = TypedDict(
-    "StopSessionResponseTypeDef",
-    {
-        "Id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StopTriggerResponseTypeDef = TypedDict(
-    "StopTriggerResponseTypeDef",
-    {
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateBlueprintResponseTypeDef = TypedDict(
-    "UpdateBlueprintResponseTypeDef",
-    {
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateDataQualityRulesetResponseTypeDef = TypedDict(
-    "UpdateDataQualityRulesetResponseTypeDef",
-    {
-        "Name": str,
-        "Description": str,
-        "Ruleset": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateJobFromSourceControlResponseTypeDef = TypedDict(
-    "UpdateJobFromSourceControlResponseTypeDef",
-    {
-        "JobName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateJobResponseTypeDef = TypedDict(
-    "UpdateJobResponseTypeDef",
-    {
-        "JobName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateMLTransformResponseTypeDef = TypedDict(
-    "UpdateMLTransformResponseTypeDef",
-    {
-        "TransformId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateRegistryResponseTypeDef = TypedDict(
-    "UpdateRegistryResponseTypeDef",
-    {
-        "RegistryName": str,
-        "RegistryArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateSchemaResponseTypeDef = TypedDict(
-    "UpdateSchemaResponseTypeDef",
-    {
-        "SchemaArn": str,
-        "SchemaName": str,
-        "RegistryName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateSourceControlFromJobResponseTypeDef = TypedDict(
-    "UpdateSourceControlFromJobResponseTypeDef",
-    {
-        "JobName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateWorkflowResponseTypeDef = TypedDict(
-    "UpdateWorkflowResponseTypeDef",
-    {
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 BatchDeleteConnectionResponseTypeDef = TypedDict(
     "BatchDeleteConnectionResponseTypeDef",
     {
         "Succeeded": List[str],
         "Errors": Dict[str, ErrorDetailTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchStopJobRunErrorTypeDef = TypedDict(
     "BatchStopJobRunErrorTypeDef",
     {
         "JobName": str,
@@ -5364,67 +5656,67 @@
 )
 
 BatchGetCustomEntityTypesResponseTypeDef = TypedDict(
     "BatchGetCustomEntityTypesResponseTypeDef",
     {
         "CustomEntityTypes": List[CustomEntityTypeTypeDef],
         "CustomEntityTypesNotFound": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCustomEntityTypesResponseTypeDef = TypedDict(
     "ListCustomEntityTypesResponseTypeDef",
     {
         "CustomEntityTypes": List[CustomEntityTypeTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetDevEndpointsResponseTypeDef = TypedDict(
     "BatchGetDevEndpointsResponseTypeDef",
     {
         "DevEndpoints": List[DevEndpointTypeDef],
         "DevEndpointsNotFound": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDevEndpointResponseTypeDef = TypedDict(
     "GetDevEndpointResponseTypeDef",
     {
         "DevEndpoint": DevEndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDevEndpointsResponseTypeDef = TypedDict(
     "GetDevEndpointsResponseTypeDef",
     {
         "DevEndpoints": List[DevEndpointTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetBlueprintRunResponseTypeDef = TypedDict(
     "GetBlueprintRunResponseTypeDef",
     {
         "BlueprintRun": BlueprintRunTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetBlueprintRunsResponseTypeDef = TypedDict(
     "GetBlueprintRunsResponseTypeDef",
     {
         "BlueprintRuns": List[BlueprintRunTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BlueprintTypeDef = TypedDict(
     "BlueprintTypeDef",
     {
         "Name": str,
@@ -5441,15 +5733,15 @@
     total=False,
 )
 
 GetCatalogImportStatusResponseTypeDef = TypedDict(
     "GetCatalogImportStatusResponseTypeDef",
     {
         "ImportStatus": CatalogImportStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCatalogKafkaSourceTypeDef = TypedDict(
     "_RequiredCatalogKafkaSourceTypeDef",
     {
         "Name": str,
@@ -5741,24 +6033,24 @@
 )
 
 ListCrawlsResponseTypeDef = TypedDict(
     "ListCrawlsResponseTypeDef",
     {
         "Crawls": List[CrawlerHistoryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCrawlerMetricsResponseTypeDef = TypedDict(
     "GetCrawlerMetricsResponseTypeDef",
     {
         "CrawlerMetricsList": List[CrawlerMetricsTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CrawlerTargetsTypeDef = TypedDict(
     "CrawlerTargetsTypeDef",
     {
         "S3Targets": List[S3TargetTypeDef],
@@ -5861,15 +6153,15 @@
         "Name": str,
         "Description": str,
         "Ruleset": str,
         "TargetTable": DataQualityTargetTableTypeDef,
         "CreatedOn": datetime,
         "LastModifiedOn": datetime,
         "RecommendationRunId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DataSourceTypeDef = TypedDict(
     "DataSourceTypeDef",
     {
         "GlueTable": GlueTableTypeDef,
@@ -5932,14 +6224,23 @@
 GetRegistryInputRequestTypeDef = TypedDict(
     "GetRegistryInputRequestTypeDef",
     {
         "RegistryId": RegistryIdTypeDef,
     },
 )
 
+ListSchemasInputListSchemasPaginateTypeDef = TypedDict(
+    "ListSchemasInputListSchemasPaginateTypeDef",
+    {
+        "RegistryId": RegistryIdTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSchemasInputRequestTypeDef = TypedDict(
     "ListSchemasInputRequestTypeDef",
     {
         "RegistryId": RegistryIdTypeDef,
         "MaxResults": int,
         "NextToken": str,
     },
@@ -6002,14 +6303,38 @@
         "MaxCapacity": float,
         "SecurityConfiguration": str,
         "GlueVersion": str,
     },
     total=False,
 )
 
+_RequiredEvaluateDataQualityMultiFrameTypeDef = TypedDict(
+    "_RequiredEvaluateDataQualityMultiFrameTypeDef",
+    {
+        "Name": str,
+        "Inputs": List[str],
+        "Ruleset": str,
+    },
+)
+_OptionalEvaluateDataQualityMultiFrameTypeDef = TypedDict(
+    "_OptionalEvaluateDataQualityMultiFrameTypeDef",
+    {
+        "AdditionalDataSources": Dict[str, str],
+        "PublishingOptions": DQResultsPublishingOptionsTypeDef,
+        "AdditionalOptions": Dict[Literal["performanceTuning.caching"], str],
+        "StopJobOnFailureOptions": DQStopJobOnFailureOptionsTypeDef,
+    },
+    total=False,
+)
+
+class EvaluateDataQualityMultiFrameTypeDef(
+    _RequiredEvaluateDataQualityMultiFrameTypeDef, _OptionalEvaluateDataQualityMultiFrameTypeDef
+):
+    pass
+
 _RequiredEvaluateDataQualityTypeDef = TypedDict(
     "_RequiredEvaluateDataQualityTypeDef",
     {
         "Name": str,
         "Inputs": List[str],
         "Ruleset": str,
     },
@@ -6102,14 +6427,34 @@
 GetSchemaInputRequestTypeDef = TypedDict(
     "GetSchemaInputRequestTypeDef",
     {
         "SchemaId": SchemaIdTypeDef,
     },
 )
 
+_RequiredListSchemaVersionsInputListSchemaVersionsPaginateTypeDef = TypedDict(
+    "_RequiredListSchemaVersionsInputListSchemaVersionsPaginateTypeDef",
+    {
+        "SchemaId": SchemaIdTypeDef,
+    },
+)
+_OptionalListSchemaVersionsInputListSchemaVersionsPaginateTypeDef = TypedDict(
+    "_OptionalListSchemaVersionsInputListSchemaVersionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListSchemaVersionsInputListSchemaVersionsPaginateTypeDef(
+    _RequiredListSchemaVersionsInputListSchemaVersionsPaginateTypeDef,
+    _OptionalListSchemaVersionsInputListSchemaVersionsPaginateTypeDef,
+):
+    pass
+
 _RequiredListSchemaVersionsInputRequestTypeDef = TypedDict(
     "_RequiredListSchemaVersionsInputRequestTypeDef",
     {
         "SchemaId": SchemaIdTypeDef,
     },
 )
 _OptionalListSchemaVersionsInputRequestTypeDef = TypedDict(
@@ -6260,36 +6605,14 @@
 )
 
 class S3HudiDirectTargetTypeDef(
     _RequiredS3HudiDirectTargetTypeDef, _OptionalS3HudiDirectTargetTypeDef
 ):
     pass
 
-_RequiredDynamicTransformTypeDef = TypedDict(
-    "_RequiredDynamicTransformTypeDef",
-    {
-        "Name": str,
-        "TransformName": str,
-        "Inputs": List[str],
-        "FunctionName": str,
-        "Path": str,
-    },
-)
-_OptionalDynamicTransformTypeDef = TypedDict(
-    "_OptionalDynamicTransformTypeDef",
-    {
-        "Parameters": List[TransformConfigParameterTypeDef],
-        "Version": str,
-    },
-    total=False,
-)
-
-class DynamicTransformTypeDef(_RequiredDynamicTransformTypeDef, _OptionalDynamicTransformTypeDef):
-    pass
-
 EncryptionConfigurationTypeDef = TypedDict(
     "EncryptionConfigurationTypeDef",
     {
         "S3Encryption": Sequence[S3EncryptionTypeDef],
         "CloudWatchEncryption": CloudWatchEncryptionTypeDef,
         "JobBookmarksEncryption": JobBookmarksEncryptionTypeDef,
     },
@@ -6338,244 +6661,21 @@
 )
 
 class TransformParametersTypeDef(
     _RequiredTransformParametersTypeDef, _OptionalTransformParametersTypeDef
 ):
     pass
 
-GetClassifiersRequestGetClassifiersPaginateTypeDef = TypedDict(
-    "GetClassifiersRequestGetClassifiersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetCrawlerMetricsRequestGetCrawlerMetricsPaginateTypeDef = TypedDict(
-    "GetCrawlerMetricsRequestGetCrawlerMetricsPaginateTypeDef",
-    {
-        "CrawlerNameList": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetCrawlersRequestGetCrawlersPaginateTypeDef = TypedDict(
-    "GetCrawlersRequestGetCrawlersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetDatabasesRequestGetDatabasesPaginateTypeDef = TypedDict(
-    "GetDatabasesRequestGetDatabasesPaginateTypeDef",
-    {
-        "CatalogId": str,
-        "ResourceShareType": ResourceShareTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetDevEndpointsRequestGetDevEndpointsPaginateTypeDef = TypedDict(
-    "GetDevEndpointsRequestGetDevEndpointsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredGetJobRunsRequestGetJobRunsPaginateTypeDef = TypedDict(
-    "_RequiredGetJobRunsRequestGetJobRunsPaginateTypeDef",
-    {
-        "JobName": str,
-    },
-)
-_OptionalGetJobRunsRequestGetJobRunsPaginateTypeDef = TypedDict(
-    "_OptionalGetJobRunsRequestGetJobRunsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetJobRunsRequestGetJobRunsPaginateTypeDef(
-    _RequiredGetJobRunsRequestGetJobRunsPaginateTypeDef,
-    _OptionalGetJobRunsRequestGetJobRunsPaginateTypeDef,
-):
-    pass
-
-GetJobsRequestGetJobsPaginateTypeDef = TypedDict(
-    "GetJobsRequestGetJobsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredGetPartitionIndexesRequestGetPartitionIndexesPaginateTypeDef = TypedDict(
-    "_RequiredGetPartitionIndexesRequestGetPartitionIndexesPaginateTypeDef",
-    {
-        "DatabaseName": str,
-        "TableName": str,
-    },
-)
-_OptionalGetPartitionIndexesRequestGetPartitionIndexesPaginateTypeDef = TypedDict(
-    "_OptionalGetPartitionIndexesRequestGetPartitionIndexesPaginateTypeDef",
-    {
-        "CatalogId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetPartitionIndexesRequestGetPartitionIndexesPaginateTypeDef(
-    _RequiredGetPartitionIndexesRequestGetPartitionIndexesPaginateTypeDef,
-    _OptionalGetPartitionIndexesRequestGetPartitionIndexesPaginateTypeDef,
-):
-    pass
-
-GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef = TypedDict(
-    "GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetSecurityConfigurationsRequestGetSecurityConfigurationsPaginateTypeDef = TypedDict(
-    "GetSecurityConfigurationsRequestGetSecurityConfigurationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredGetTableVersionsRequestGetTableVersionsPaginateTypeDef = TypedDict(
-    "_RequiredGetTableVersionsRequestGetTableVersionsPaginateTypeDef",
-    {
-        "DatabaseName": str,
-        "TableName": str,
-    },
-)
-_OptionalGetTableVersionsRequestGetTableVersionsPaginateTypeDef = TypedDict(
-    "_OptionalGetTableVersionsRequestGetTableVersionsPaginateTypeDef",
-    {
-        "CatalogId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetTableVersionsRequestGetTableVersionsPaginateTypeDef(
-    _RequiredGetTableVersionsRequestGetTableVersionsPaginateTypeDef,
-    _OptionalGetTableVersionsRequestGetTableVersionsPaginateTypeDef,
-):
-    pass
-
-_RequiredGetTablesRequestGetTablesPaginateTypeDef = TypedDict(
-    "_RequiredGetTablesRequestGetTablesPaginateTypeDef",
-    {
-        "DatabaseName": str,
-    },
-)
-_OptionalGetTablesRequestGetTablesPaginateTypeDef = TypedDict(
-    "_OptionalGetTablesRequestGetTablesPaginateTypeDef",
-    {
-        "CatalogId": str,
-        "Expression": str,
-        "TransactionId": str,
-        "QueryAsOfTime": Union[datetime, str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetTablesRequestGetTablesPaginateTypeDef(
-    _RequiredGetTablesRequestGetTablesPaginateTypeDef,
-    _OptionalGetTablesRequestGetTablesPaginateTypeDef,
-):
-    pass
-
-GetTriggersRequestGetTriggersPaginateTypeDef = TypedDict(
-    "GetTriggersRequestGetTriggersPaginateTypeDef",
-    {
-        "DependentJobName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredGetUserDefinedFunctionsRequestGetUserDefinedFunctionsPaginateTypeDef = TypedDict(
-    "_RequiredGetUserDefinedFunctionsRequestGetUserDefinedFunctionsPaginateTypeDef",
-    {
-        "Pattern": str,
-    },
-)
-_OptionalGetUserDefinedFunctionsRequestGetUserDefinedFunctionsPaginateTypeDef = TypedDict(
-    "_OptionalGetUserDefinedFunctionsRequestGetUserDefinedFunctionsPaginateTypeDef",
-    {
-        "CatalogId": str,
-        "DatabaseName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetUserDefinedFunctionsRequestGetUserDefinedFunctionsPaginateTypeDef(
-    _RequiredGetUserDefinedFunctionsRequestGetUserDefinedFunctionsPaginateTypeDef,
-    _OptionalGetUserDefinedFunctionsRequestGetUserDefinedFunctionsPaginateTypeDef,
-):
-    pass
-
-ListRegistriesInputListRegistriesPaginateTypeDef = TypedDict(
-    "ListRegistriesInputListRegistriesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListSchemaVersionsInputListSchemaVersionsPaginateTypeDef = TypedDict(
-    "_RequiredListSchemaVersionsInputListSchemaVersionsPaginateTypeDef",
-    {
-        "SchemaId": SchemaIdTypeDef,
-    },
-)
-_OptionalListSchemaVersionsInputListSchemaVersionsPaginateTypeDef = TypedDict(
-    "_OptionalListSchemaVersionsInputListSchemaVersionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListSchemaVersionsInputListSchemaVersionsPaginateTypeDef(
-    _RequiredListSchemaVersionsInputListSchemaVersionsPaginateTypeDef,
-    _OptionalListSchemaVersionsInputListSchemaVersionsPaginateTypeDef,
-):
-    pass
-
-ListSchemasInputListSchemasPaginateTypeDef = TypedDict(
-    "ListSchemasInputListSchemasPaginateTypeDef",
-    {
-        "RegistryId": RegistryIdTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 GetConnectionsRequestGetConnectionsPaginateTypeDef = TypedDict(
     "GetConnectionsRequestGetConnectionsPaginateTypeDef",
     {
         "CatalogId": str,
         "Filter": GetConnectionsFilterTypeDef,
         "HidePassword": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 GetConnectionsRequestRequestTypeDef = TypedDict(
     "GetConnectionsRequestRequestTypeDef",
     {
@@ -6588,23 +6688,23 @@
     total=False,
 )
 
 GetJobBookmarkResponseTypeDef = TypedDict(
     "GetJobBookmarkResponseTypeDef",
     {
         "JobBookmarkEntry": JobBookmarkEntryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResetJobBookmarkResponseTypeDef = TypedDict(
     "ResetJobBookmarkResponseTypeDef",
     {
         "JobBookmarkEntry": JobBookmarkEntryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetMLTaskRunsRequestRequestTypeDef = TypedDict(
     "_RequiredGetMLTaskRunsRequestRequestTypeDef",
     {
         "TransformId": str,
@@ -6642,15 +6742,15 @@
     total=False,
 )
 
 GetMappingResponseTypeDef = TypedDict(
     "GetMappingResponseTypeDef",
     {
         "Mapping": List[MappingEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetPartitionsRequestGetPartitionsPaginateTypeDef = TypedDict(
     "_RequiredGetPartitionsRequestGetPartitionsPaginateTypeDef",
     {
         "DatabaseName": str,
@@ -6662,15 +6762,15 @@
     {
         "CatalogId": str,
         "Expression": str,
         "Segment": SegmentTypeDef,
         "ExcludeColumnSchema": bool,
         "TransactionId": str,
         "QueryAsOfTime": Union[datetime, str],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 class GetPartitionsRequestGetPartitionsPaginateTypeDef(
     _RequiredGetPartitionsRequestGetPartitionsPaginateTypeDef,
     _OptionalGetPartitionsRequestGetPartitionsPaginateTypeDef,
@@ -6732,15 +6832,15 @@
     pass
 
 GetResourcePoliciesResponseTypeDef = TypedDict(
     "GetResourcePoliciesResponseTypeDef",
     {
         "GetResourcePoliciesResponseList": List[GluePolicyTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSchemaVersionInputRequestTypeDef = TypedDict(
     "GetSchemaVersionInputRequestTypeDef",
     {
         "SchemaId": SchemaIdTypeDef,
@@ -6885,33 +6985,33 @@
 )
 
 ListRegistriesResponseTypeDef = TypedDict(
     "ListRegistriesResponseTypeDef",
     {
         "Registries": List[RegistryListItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSchemaVersionsResponseTypeDef = TypedDict(
     "ListSchemaVersionsResponseTypeDef",
     {
         "Schemas": List[SchemaVersionListItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSchemasResponseTypeDef = TypedDict(
     "ListSchemasResponseTypeDef",
     {
         "Schemas": List[SchemaListItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TransformEncryptionTypeDef = TypedDict(
     "TransformEncryptionTypeDef",
     {
         "MlUserDataEncryption": MLUserDataEncryptionTypeDef,
@@ -7070,14 +7170,33 @@
         "XMLClassifier": UpdateXMLClassifierRequestTypeDef,
         "JsonClassifier": UpdateJsonClassifierRequestTypeDef,
         "CsvClassifier": UpdateCsvClassifierRequestTypeDef,
     },
     total=False,
 )
 
+AmazonRedshiftSourceTypeDef = TypedDict(
+    "AmazonRedshiftSourceTypeDef",
+    {
+        "Name": str,
+        "Data": AmazonRedshiftNodeDataTypeDef,
+    },
+    total=False,
+)
+
+AmazonRedshiftTargetTypeDef = TypedDict(
+    "AmazonRedshiftTargetTypeDef",
+    {
+        "Name": str,
+        "Data": AmazonRedshiftNodeDataTypeDef,
+        "Inputs": List[str],
+    },
+    total=False,
+)
+
 _RequiredPartitionIndexDescriptorTypeDef = TypedDict(
     "_RequiredPartitionIndexDescriptorTypeDef",
     {
         "IndexName": str,
         "Keys": List[KeySchemaElementTypeDef],
         "IndexStatus": PartitionIndexStatusType,
     },
@@ -7096,89 +7215,89 @@
     pass
 
 BatchStopJobRunResponseTypeDef = TypedDict(
     "BatchStopJobRunResponseTypeDef",
     {
         "SuccessfulSubmissions": List[BatchStopJobRunSuccessfulSubmissionTypeDef],
         "Errors": List[BatchStopJobRunErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchUpdatePartitionResponseTypeDef = TypedDict(
     "BatchUpdatePartitionResponseTypeDef",
     {
         "Errors": List[BatchUpdatePartitionFailureEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchCreatePartitionResponseTypeDef = TypedDict(
     "BatchCreatePartitionResponseTypeDef",
     {
         "Errors": List[PartitionErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDeletePartitionResponseTypeDef = TypedDict(
     "BatchDeletePartitionResponseTypeDef",
     {
         "Errors": List[PartitionErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDeleteTableResponseTypeDef = TypedDict(
     "BatchDeleteTableResponseTypeDef",
     {
         "Errors": List[TableErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDeleteTableVersionResponseTypeDef = TypedDict(
     "BatchDeleteTableVersionResponseTypeDef",
     {
         "Errors": List[TableVersionErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetBlueprintsResponseTypeDef = TypedDict(
     "BatchGetBlueprintsResponseTypeDef",
     {
         "Blueprints": List[BlueprintTypeDef],
         "MissingBlueprints": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetBlueprintResponseTypeDef = TypedDict(
     "GetBlueprintResponseTypeDef",
     {
         "Blueprint": BlueprintTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetClassifierResponseTypeDef = TypedDict(
     "GetClassifierResponseTypeDef",
     {
         "Classifier": ClassifierTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetClassifiersResponseTypeDef = TypedDict(
     "GetClassifiersResponseTypeDef",
     {
         "Classifiers": List[ClassifierTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateScriptRequestRequestTypeDef = TypedDict(
     "CreateScriptRequestRequestTypeDef",
     {
         "DagNodes": Sequence[CodeGenNodeTypeDef],
@@ -7189,15 +7308,15 @@
 )
 
 GetDataflowGraphResponseTypeDef = TypedDict(
     "GetDataflowGraphResponseTypeDef",
     {
         "DagNodes": List[CodeGenNodeTypeDef],
         "DagEdges": List[CodeGenEdgeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredGetMappingRequestRequestTypeDef = TypedDict(
     "_RequiredGetMappingRequestRequestTypeDef",
     {
         "Source": CatalogEntryTypeDef,
@@ -7356,24 +7475,24 @@
 ):
     pass
 
 GetConnectionResponseTypeDef = TypedDict(
     "GetConnectionResponseTypeDef",
     {
         "Connection": ConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetConnectionsResponseTypeDef = TypedDict(
     "GetConnectionsResponseTypeDef",
     {
         "ConnectionList": List[ConnectionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CrawlerTypeDef = TypedDict(
     "CrawlerTypeDef",
     {
         "Name": str,
@@ -7475,15 +7594,15 @@
 )
 
 ListDataQualityRulesetsResponseTypeDef = TypedDict(
     "ListDataQualityRulesetsResponseTypeDef",
     {
         "Rulesets": List[DataQualityRulesetListDetailsTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DataQualityResultDescriptionTypeDef = TypedDict(
     "DataQualityResultDescriptionTypeDef",
     {
         "ResultId": str,
@@ -7599,15 +7718,15 @@
         "EvaluationContext": str,
         "StartedOn": datetime,
         "CompletedOn": datetime,
         "JobName": str,
         "JobRunId": str,
         "RulesetEvaluationRunId": str,
         "RuleResults": List[DataQualityRuleResultTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDataQualityRuleRecommendationRunResponseTypeDef = TypedDict(
     "GetDataQualityRuleRecommendationRunResponseTypeDef",
     {
         "RunId": str,
@@ -7619,15 +7738,15 @@
         "ErrorString": str,
         "StartedOn": datetime,
         "LastModifiedOn": datetime,
         "CompletedOn": datetime,
         "ExecutionTime": int,
         "RecommendedRuleset": str,
         "CreatedRulesetName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDataQualityRulesetEvaluationRunResponseTypeDef = TypedDict(
     "GetDataQualityRulesetEvaluationRunResponseTypeDef",
     {
         "RunId": str,
@@ -7640,15 +7759,16 @@
         "ErrorString": str,
         "StartedOn": datetime,
         "LastModifiedOn": datetime,
         "CompletedOn": datetime,
         "ExecutionTime": int,
         "RulesetNames": List[str],
         "ResultIds": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "AdditionalDataSources": Dict[str, DataSourceTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStartDataQualityRuleRecommendationRunRequestRequestTypeDef = TypedDict(
     "_RequiredStartDataQualityRuleRecommendationRunRequestRequestTypeDef",
     {
         "DataSource": DataSourceTypeDef,
@@ -7683,55 +7803,56 @@
 _OptionalStartDataQualityRulesetEvaluationRunRequestRequestTypeDef = TypedDict(
     "_OptionalStartDataQualityRulesetEvaluationRunRequestRequestTypeDef",
     {
         "NumberOfWorkers": int,
         "Timeout": int,
         "ClientToken": str,
         "AdditionalRunOptions": DataQualityEvaluationRunAdditionalRunOptionsTypeDef,
+        "AdditionalDataSources": Mapping[str, DataSourceTypeDef],
     },
     total=False,
 )
 
 class StartDataQualityRulesetEvaluationRunRequestRequestTypeDef(
     _RequiredStartDataQualityRulesetEvaluationRunRequestRequestTypeDef,
     _OptionalStartDataQualityRulesetEvaluationRunRequestRequestTypeDef,
 ):
     pass
 
 CreateSessionResponseTypeDef = TypedDict(
     "CreateSessionResponseTypeDef",
     {
         "Session": SessionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSessionResponseTypeDef = TypedDict(
     "GetSessionResponseTypeDef",
     {
         "Session": SessionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSessionsResponseTypeDef = TypedDict(
     "ListSessionsResponseTypeDef",
     {
         "Ids": List[str],
         "Sessions": List[SessionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDataCatalogEncryptionSettingsResponseTypeDef = TypedDict(
     "GetDataCatalogEncryptionSettingsResponseTypeDef",
     {
         "DataCatalogEncryptionSettings": DataCatalogEncryptionSettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutDataCatalogEncryptionSettingsRequestRequestTypeDef = TypedDict(
     "_RequiredPutDataCatalogEncryptionSettingsRequestRequestTypeDef",
     {
         "DataCatalogEncryptionSettings": DataCatalogEncryptionSettingsTypeDef,
@@ -7761,14 +7882,15 @@
     "_OptionalDatabaseInputTypeDef",
     {
         "Description": str,
         "LocationUri": str,
         "Parameters": Mapping[str, str],
         "CreateTableDefaultPermissions": Sequence[PrincipalPermissionsTypeDef],
         "TargetDatabase": DatabaseIdentifierTypeDef,
+        "FederatedDatabase": FederatedDatabaseTypeDef,
     },
     total=False,
 )
 
 class DatabaseInputTypeDef(_RequiredDatabaseInputTypeDef, _OptionalDatabaseInputTypeDef):
     pass
 
@@ -7784,14 +7906,15 @@
         "Description": str,
         "LocationUri": str,
         "Parameters": Dict[str, str],
         "CreateTime": datetime,
         "CreateTableDefaultPermissions": List[PrincipalPermissionsTypeDef],
         "TargetDatabase": DatabaseIdentifierTypeDef,
         "CatalogId": str,
+        "FederatedDatabase": FederatedDatabaseTypeDef,
     },
     total=False,
 )
 
 class DatabaseTypeDef(_RequiredDatabaseTypeDef, _OptionalDatabaseTypeDef):
     pass
 
@@ -7878,15 +8001,15 @@
     total=False,
 )
 
 DeleteSchemaVersionsResponseTypeDef = TypedDict(
     "DeleteSchemaVersionsResponseTypeDef",
     {
         "SchemaVersionErrors": List[SchemaVersionErrorItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FilterTypeDef = TypedDict(
     "FilterTypeDef",
     {
         "Name": str,
@@ -8031,14 +8154,37 @@
     },
     total=False,
 )
 
 class CustomCodeTypeDef(_RequiredCustomCodeTypeDef, _OptionalCustomCodeTypeDef):
     pass
 
+_RequiredDynamicTransformTypeDef = TypedDict(
+    "_RequiredDynamicTransformTypeDef",
+    {
+        "Name": str,
+        "TransformName": str,
+        "Inputs": List[str],
+        "FunctionName": str,
+        "Path": str,
+    },
+)
+_OptionalDynamicTransformTypeDef = TypedDict(
+    "_OptionalDynamicTransformTypeDef",
+    {
+        "Parameters": List[TransformConfigParameterTypeDef],
+        "Version": str,
+        "OutputSchemas": List[GlueSchemaTypeDef],
+    },
+    total=False,
+)
+
+class DynamicTransformTypeDef(_RequiredDynamicTransformTypeDef, _OptionalDynamicTransformTypeDef):
+    pass
+
 _RequiredJDBCConnectorSourceTypeDef = TypedDict(
     "_RequiredJDBCConnectorSourceTypeDef",
     {
         "Name": str,
         "ConnectionName": str,
         "ConnectorName": str,
         "ConnectionType": str,
@@ -8324,24 +8470,24 @@
 class SparkSQLTypeDef(_RequiredSparkSQLTypeDef, _OptionalSparkSQLTypeDef):
     pass
 
 GetJobRunResponseTypeDef = TypedDict(
     "GetJobRunResponseTypeDef",
     {
         "JobRun": JobRunTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetJobRunsResponseTypeDef = TypedDict(
     "GetJobRunsResponseTypeDef",
     {
         "JobRuns": List[JobRunTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 JobNodeDetailsTypeDef = TypedDict(
     "JobNodeDetailsTypeDef",
     {
         "JobRuns": List[JobRunTypeDef],
@@ -8358,15 +8504,15 @@
         "LogGroupName": str,
         "Properties": TaskRunPropertiesTypeDef,
         "ErrorString": str,
         "StartedOn": datetime,
         "LastModifiedOn": datetime,
         "CompletedOn": datetime,
         "ExecutionTime": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TaskRunTypeDef = TypedDict(
     "TaskRunTypeDef",
     {
         "TransformId": str,
@@ -8415,15 +8561,15 @@
 
 QuerySchemaVersionMetadataResponseTypeDef = TypedDict(
     "QuerySchemaVersionMetadataResponseTypeDef",
     {
         "MetadataInfoMap": Dict[str, MetadataInfoTypeDef],
         "SchemaVersionId": str,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateUserDefinedFunctionRequestRequestTypeDef = TypedDict(
     "_RequiredCreateUserDefinedFunctionRequestRequestTypeDef",
     {
         "DatabaseName": str,
@@ -8466,24 +8612,24 @@
 ):
     pass
 
 GetUserDefinedFunctionResponseTypeDef = TypedDict(
     "GetUserDefinedFunctionResponseTypeDef",
     {
         "UserDefinedFunction": UserDefinedFunctionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetUserDefinedFunctionsResponseTypeDef = TypedDict(
     "GetUserDefinedFunctionsResponseTypeDef",
     {
         "UserDefinedFunctions": List[UserDefinedFunctionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StatementTypeDef = TypedDict(
     "StatementTypeDef",
     {
         "Id": int,
@@ -8498,41 +8644,41 @@
 )
 
 GetPartitionIndexesResponseTypeDef = TypedDict(
     "GetPartitionIndexesResponseTypeDef",
     {
         "PartitionIndexDescriptorList": List[PartitionIndexDescriptorTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetTriggersResponseTypeDef = TypedDict(
     "BatchGetTriggersResponseTypeDef",
     {
         "Triggers": List[TriggerTypeDef],
         "TriggersNotFound": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTriggerResponseTypeDef = TypedDict(
     "GetTriggerResponseTypeDef",
     {
         "Trigger": TriggerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTriggersResponseTypeDef = TypedDict(
     "GetTriggersResponseTypeDef",
     {
         "Triggers": List[TriggerTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TriggerNodeDetailsTypeDef = TypedDict(
     "TriggerNodeDetailsTypeDef",
     {
         "Trigger": TriggerTypeDef,
@@ -8540,15 +8686,15 @@
     total=False,
 )
 
 UpdateTriggerResponseTypeDef = TypedDict(
     "UpdateTriggerResponseTypeDef",
     {
         "Trigger": TriggerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateTriggerRequestRequestTypeDef = TypedDict(
     "UpdateTriggerRequestRequestTypeDef",
     {
         "Name": str,
@@ -8574,15 +8720,15 @@
         "GlueVersion": str,
         "MaxCapacity": float,
         "WorkerType": WorkerTypeType,
         "NumberOfWorkers": int,
         "Timeout": int,
         "MaxRetries": int,
         "TransformEncryption": TransformEncryptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 MLTransformTypeDef = TypedDict(
     "MLTransformTypeDef",
     {
         "TransformId": str,
@@ -8609,41 +8755,41 @@
 )
 
 BatchGetCrawlersResponseTypeDef = TypedDict(
     "BatchGetCrawlersResponseTypeDef",
     {
         "Crawlers": List[CrawlerTypeDef],
         "CrawlersNotFound": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCrawlerResponseTypeDef = TypedDict(
     "GetCrawlerResponseTypeDef",
     {
         "Crawler": CrawlerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCrawlersResponseTypeDef = TypedDict(
     "GetCrawlersResponseTypeDef",
     {
         "Crawlers": List[CrawlerTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDataQualityResultsResponseTypeDef = TypedDict(
     "ListDataQualityResultsResponseTypeDef",
     {
         "Results": List[DataQualityResultDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDataQualityResultsRequestRequestTypeDef = TypedDict(
     "ListDataQualityResultsRequestRequestTypeDef",
     {
         "Filter": DataQualityResultFilterCriteriaTypeDef,
@@ -8654,24 +8800,24 @@
 )
 
 BatchGetDataQualityResultResponseTypeDef = TypedDict(
     "BatchGetDataQualityResultResponseTypeDef",
     {
         "Results": List[DataQualityResultTypeDef],
         "ResultsNotFound": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDataQualityRuleRecommendationRunsResponseTypeDef = TypedDict(
     "ListDataQualityRuleRecommendationRunsResponseTypeDef",
     {
         "Runs": List[DataQualityRuleRecommendationRunDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDataQualityRuleRecommendationRunsRequestRequestTypeDef = TypedDict(
     "ListDataQualityRuleRecommendationRunsRequestRequestTypeDef",
     {
         "Filter": DataQualityRuleRecommendationRunFilterTypeDef,
@@ -8682,15 +8828,15 @@
 )
 
 ListDataQualityRulesetEvaluationRunsResponseTypeDef = TypedDict(
     "ListDataQualityRulesetEvaluationRunsResponseTypeDef",
     {
         "Runs": List[DataQualityRulesetEvaluationRunDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDataQualityRulesetEvaluationRunsRequestRequestTypeDef = TypedDict(
     "ListDataQualityRulesetEvaluationRunsRequestRequestTypeDef",
     {
         "Filter": DataQualityRulesetEvaluationRunFilterTypeDef,
@@ -8740,24 +8886,24 @@
 ):
     pass
 
 GetDatabaseResponseTypeDef = TypedDict(
     "GetDatabaseResponseTypeDef",
     {
         "Database": DatabaseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDatabasesResponseTypeDef = TypedDict(
     "GetDatabasesResponseTypeDef",
     {
         "DatabaseList": List[DatabaseTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ColumnStatisticsTypeDef = TypedDict(
     "ColumnStatisticsTypeDef",
     {
         "ColumnName": str,
@@ -8847,35 +8993,36 @@
         "TableType": str,
         "Parameters": Dict[str, str],
         "CreatedBy": str,
         "IsRegisteredWithLakeFormation": bool,
         "TargetTable": TableIdentifierTypeDef,
         "CatalogId": str,
         "VersionId": str,
+        "FederatedTable": FederatedTableTypeDef,
     },
     total=False,
 )
 
 class TableTypeDef(_RequiredTableTypeDef, _OptionalTableTypeDef):
     pass
 
 GetSecurityConfigurationResponseTypeDef = TypedDict(
     "GetSecurityConfigurationResponseTypeDef",
     {
         "SecurityConfiguration": SecurityConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSecurityConfigurationsResponseTypeDef = TypedDict(
     "GetSecurityConfigurationsResponseTypeDef",
     {
         "SecurityConfigurations": List[SecurityConfigurationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CodeGenConfigurationNodeTypeDef = TypedDict(
     "CodeGenConfigurationNodeTypeDef",
     {
         "AthenaConnectorSource": AthenaConnectorSourceTypeDef,
@@ -8937,41 +9084,44 @@
         "S3HudiDirectTarget": S3HudiDirectTargetTypeDef,
         "DirectJDBCSource": DirectJDBCSourceTypeDef,
         "S3CatalogDeltaSource": S3CatalogDeltaSourceTypeDef,
         "CatalogDeltaSource": CatalogDeltaSourceTypeDef,
         "S3DeltaSource": S3DeltaSourceTypeDef,
         "S3DeltaCatalogTarget": S3DeltaCatalogTargetTypeDef,
         "S3DeltaDirectTarget": S3DeltaDirectTargetTypeDef,
+        "AmazonRedshiftSource": AmazonRedshiftSourceTypeDef,
+        "AmazonRedshiftTarget": AmazonRedshiftTargetTypeDef,
+        "EvaluateDataQualityMultiFrame": EvaluateDataQualityMultiFrameTypeDef,
     },
     total=False,
 )
 
 GetMLTaskRunsResponseTypeDef = TypedDict(
     "GetMLTaskRunsResponseTypeDef",
     {
         "TaskRuns": List[TaskRunTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetStatementResponseTypeDef = TypedDict(
     "GetStatementResponseTypeDef",
     {
         "Statement": StatementTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListStatementsResponseTypeDef = TypedDict(
     "ListStatementsResponseTypeDef",
     {
         "Statements": List[StatementTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 NodeTypeDef = TypedDict(
     "NodeTypeDef",
     {
         "Type": NodeTypeType,
@@ -8985,15 +9135,15 @@
 )
 
 GetMLTransformsResponseTypeDef = TypedDict(
     "GetMLTransformsResponseTypeDef",
     {
         "Transforms": List[MLTransformTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ColumnStatisticsErrorTypeDef = TypedDict(
     "ColumnStatisticsErrorTypeDef",
     {
         "ColumnStatistics": ColumnStatisticsTypeDef,
@@ -9003,24 +9153,24 @@
 )
 
 GetColumnStatisticsForPartitionResponseTypeDef = TypedDict(
     "GetColumnStatisticsForPartitionResponseTypeDef",
     {
         "ColumnStatisticsList": List[ColumnStatisticsTypeDef],
         "Errors": List[ColumnErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetColumnStatisticsForTableResponseTypeDef = TypedDict(
     "GetColumnStatisticsForTableResponseTypeDef",
     {
         "ColumnStatisticsList": List[ColumnStatisticsTypeDef],
         "Errors": List[ColumnErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateColumnStatisticsForPartitionRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateColumnStatisticsForPartitionRequestRequestTypeDef",
     {
         "DatabaseName": str,
@@ -9139,42 +9289,42 @@
     pass
 
 BatchGetPartitionResponseTypeDef = TypedDict(
     "BatchGetPartitionResponseTypeDef",
     {
         "Partitions": List[PartitionTypeDef],
         "UnprocessedKeys": List[PartitionValueListTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetPartitionResponseTypeDef = TypedDict(
     "GetPartitionResponseTypeDef",
     {
         "Partition": PartitionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetPartitionsResponseTypeDef = TypedDict(
     "GetPartitionsResponseTypeDef",
     {
         "Partitions": List[PartitionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetUnfilteredPartitionMetadataResponseTypeDef = TypedDict(
     "GetUnfilteredPartitionMetadataResponseTypeDef",
     {
         "Partition": PartitionTypeDef,
         "AuthorizedColumns": List[str],
         "IsRegisteredWithLakeFormation": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UnfilteredPartitionTypeDef = TypedDict(
     "UnfilteredPartitionTypeDef",
     {
         "Partition": PartitionTypeDef,
@@ -9229,44 +9379,44 @@
 ):
     pass
 
 GetTableResponseTypeDef = TypedDict(
     "GetTableResponseTypeDef",
     {
         "Table": TableTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTablesResponseTypeDef = TypedDict(
     "GetTablesResponseTypeDef",
     {
         "TableList": List[TableTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetUnfilteredTableMetadataResponseTypeDef = TypedDict(
     "GetUnfilteredTableMetadataResponseTypeDef",
     {
         "Table": TableTypeDef,
         "AuthorizedColumns": List[str],
         "IsRegisteredWithLakeFormation": bool,
         "CellFilters": List[ColumnRowFilterTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SearchTablesResponseTypeDef = TypedDict(
     "SearchTablesResponseTypeDef",
     {
         "NextToken": str,
         "TableList": List[TableTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TableVersionTypeDef = TypedDict(
     "TableVersionTypeDef",
     {
         "Table": TableTypeDef,
@@ -9380,23 +9530,23 @@
     total=False,
 )
 
 UpdateColumnStatisticsForPartitionResponseTypeDef = TypedDict(
     "UpdateColumnStatisticsForPartitionResponseTypeDef",
     {
         "Errors": List[ColumnStatisticsErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateColumnStatisticsForTableResponseTypeDef = TypedDict(
     "UpdateColumnStatisticsForTableResponseTypeDef",
     {
         "Errors": List[ColumnStatisticsErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredBatchUpdatePartitionRequestRequestTypeDef = TypedDict(
     "_RequiredBatchUpdatePartitionRequestRequestTypeDef",
     {
         "DatabaseName": str,
@@ -9419,58 +9569,58 @@
     pass
 
 GetUnfilteredPartitionsMetadataResponseTypeDef = TypedDict(
     "GetUnfilteredPartitionsMetadataResponseTypeDef",
     {
         "UnfilteredPartitions": List[UnfilteredPartitionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTableVersionResponseTypeDef = TypedDict(
     "GetTableVersionResponseTypeDef",
     {
         "TableVersion": TableVersionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTableVersionsResponseTypeDef = TypedDict(
     "GetTableVersionsResponseTypeDef",
     {
         "TableVersions": List[TableVersionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetJobsResponseTypeDef = TypedDict(
     "BatchGetJobsResponseTypeDef",
     {
         "Jobs": List[JobTypeDef],
         "JobsNotFound": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetJobResponseTypeDef = TypedDict(
     "GetJobResponseTypeDef",
     {
         "Job": JobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetJobsResponseTypeDef = TypedDict(
     "GetJobsResponseTypeDef",
     {
         "Jobs": List[JobTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateJobRequestRequestTypeDef = TypedDict(
     "UpdateJobRequestRequestTypeDef",
     {
         "JobName": str,
@@ -9496,24 +9646,24 @@
     total=False,
 )
 
 GetWorkflowRunResponseTypeDef = TypedDict(
     "GetWorkflowRunResponseTypeDef",
     {
         "Run": WorkflowRunTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetWorkflowRunsResponseTypeDef = TypedDict(
     "GetWorkflowRunsResponseTypeDef",
     {
         "Runs": List[WorkflowRunTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 WorkflowTypeDef = TypedDict(
     "WorkflowTypeDef",
     {
         "Name": str,
@@ -9530,18 +9680,18 @@
 )
 
 BatchGetWorkflowsResponseTypeDef = TypedDict(
     "BatchGetWorkflowsResponseTypeDef",
     {
         "Workflows": List[WorkflowTypeDef],
         "MissingWorkflows": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetWorkflowResponseTypeDef = TypedDict(
     "GetWorkflowResponseTypeDef",
     {
         "Workflow": WorkflowTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-glue-2.5.0.post1/types_aiobotocore_glue.egg-info/PKG-INFO` & `types-aiobotocore-glue-2.5.1/types_aiobotocore_glue.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-glue
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Glue 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Glue 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-glue"></a>
 
 # types-aiobotocore-glue
 
 [![PyPI - types-aiobotocore-glue](https://img.shields.io/pypi/v/types-aiobotocore-glue.svg?color=blue)](https://pypi.org/project/types-aiobotocore-glue)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-glue.svg?color=blue)](https://pypi.org/project/types-aiobotocore-glue)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-glue?color=blue)](https://pypistats.org/packages/types-aiobotocore-glue)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Glue 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue)
+[aiobotocore.Glue 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/glue.html#Glue)
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
 [types-aiobotocore-glue docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_glue/).
 
 See how it helps to find and fix potential bugs:
 
@@ -344,14 +344,15 @@
 ### Literals
 
 `types_aiobotocore_glue.literals` module contains literals extracted from
 shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_glue.literals import (
+    AdditionalOptionKeysType,
     AggFunctionType,
     BackfillErrorCodeType,
     BlueprintRunStateType,
     BlueprintStatusType,
     CatalogEncryptionModeType,
     CloudWatchEncryptionModeType,
     ColumnStatisticsTypeType,
@@ -455,34 +456,35 @@
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
 
 
-def check_value(value: AggFunctionType) -> bool:
+def check_value(value: AdditionalOptionKeysType) -> bool:
     ...
 ```
 
 <a id="typed-dictionaries"></a>
 
 ### Typed dictionaries
 
 `types_aiobotocore_glue.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_glue.type_defs import (
     NotificationPropertyTypeDef,
     AggregateOperationTypeDef,
+    AmazonRedshiftAdvancedOptionTypeDef,
+    OptionTypeDef,
     ApplyMappingTypeDef,
     AuditContextTypeDef,
     PartitionValueListTypeDef,
     BasicCatalogTargetTypeDef,
-    ResponseMetadataTypeDef,
     BatchDeleteConnectionRequestRequestTypeDef,
     ErrorDetailTypeDef,
     BatchDeleteTableRequestRequestTypeDef,
     BatchDeleteTableVersionRequestRequestTypeDef,
     BatchGetBlueprintsRequestRequestTypeDef,
     BatchGetCrawlersRequestRequestTypeDef,
     BatchGetCustomEntityTypesRequestRequestTypeDef,
@@ -499,24 +501,26 @@
     BlueprintDetailsTypeDef,
     BlueprintRunTypeDef,
     LastActiveDefinitionTypeDef,
     BooleanColumnStatisticsDataTypeDef,
     CancelDataQualityRuleRecommendationRunRequestRequestTypeDef,
     CancelDataQualityRulesetEvaluationRunRequestRequestTypeDef,
     CancelMLTaskRunRequestRequestTypeDef,
+    CancelMLTaskRunResponseTypeDef,
     CancelStatementRequestRequestTypeDef,
     CatalogEntryTypeDef,
     CatalogImportStatusTypeDef,
     KafkaStreamingSourceOptionsTypeDef,
     StreamingDataPreviewOptionsTypeDef,
     KinesisStreamingSourceOptionsTypeDef,
     CatalogSchemaChangePolicyTypeDef,
     CatalogSourceTypeDef,
     CatalogTargetTypeDef,
     CheckSchemaVersionValidityInputRequestTypeDef,
+    CheckSchemaVersionValidityResponseTypeDef,
     CsvClassifierTypeDef,
     GrokClassifierTypeDef,
     JsonClassifierTypeDef,
     XMLClassifierTypeDef,
     CloudWatchEncryptionTypeDef,
     DirectJDBCSourceTypeDef,
     DropDuplicatesTypeDef,
@@ -567,282 +571,299 @@
     LastCrawlInfoTypeDef,
     LineageConfigurationTypeDef,
     RecrawlPolicyTypeDef,
     ScheduleTypeDef,
     SchemaChangePolicyTypeDef,
     CrawlsFilterTypeDef,
     CreateBlueprintRequestRequestTypeDef,
+    CreateBlueprintResponseTypeDef,
     CreateCsvClassifierRequestTypeDef,
     CreateGrokClassifierRequestTypeDef,
     CreateJsonClassifierRequestTypeDef,
     CreateXMLClassifierRequestTypeDef,
     CreateCustomEntityTypeRequestRequestTypeDef,
+    CreateCustomEntityTypeResponseTypeDef,
     DataQualityTargetTableTypeDef,
+    CreateDataQualityRulesetResponseTypeDef,
     CreateDevEndpointRequestRequestTypeDef,
+    CreateDevEndpointResponseTypeDef,
     ExecutionPropertyTypeDef,
     JobCommandTypeDef,
     SourceControlDetailsTypeDef,
+    CreateJobResponseTypeDef,
     GlueTableTypeDef,
+    CreateMLTransformResponseTypeDef,
     PartitionIndexTypeDef,
     CreateRegistryInputRequestTypeDef,
+    CreateRegistryResponseTypeDef,
     RegistryIdTypeDef,
+    CreateSchemaResponseTypeDef,
+    CreateScriptResponseTypeDef,
+    CreateSecurityConfigurationResponseTypeDef,
     SessionCommandTypeDef,
     EventBatchingConditionTypeDef,
+    CreateTriggerResponseTypeDef,
     CreateWorkflowRequestRequestTypeDef,
+    CreateWorkflowResponseTypeDef,
     DQResultsPublishingOptionsTypeDef,
     DQStopJobOnFailureOptionsTypeDef,
     EncryptionAtRestTypeDef,
     DataLakePrincipalTypeDef,
     DataQualityEvaluationRunAdditionalRunOptionsTypeDef,
     DataQualityRuleResultTypeDef,
     DatabaseIdentifierTypeDef,
+    FederatedDatabaseTypeDef,
     DatatypeTypeDef,
     DecimalNumberTypeDef,
     DeleteBlueprintRequestRequestTypeDef,
+    DeleteBlueprintResponseTypeDef,
     DeleteClassifierRequestRequestTypeDef,
     DeleteColumnStatisticsForPartitionRequestRequestTypeDef,
     DeleteColumnStatisticsForTableRequestRequestTypeDef,
     DeleteConnectionRequestRequestTypeDef,
     DeleteCrawlerRequestRequestTypeDef,
     DeleteCustomEntityTypeRequestRequestTypeDef,
+    DeleteCustomEntityTypeResponseTypeDef,
     DeleteDataQualityRulesetRequestRequestTypeDef,
     DeleteDatabaseRequestRequestTypeDef,
     DeleteDevEndpointRequestRequestTypeDef,
     DeleteJobRequestRequestTypeDef,
+    DeleteJobResponseTypeDef,
     DeleteMLTransformRequestRequestTypeDef,
+    DeleteMLTransformResponseTypeDef,
     DeletePartitionIndexRequestRequestTypeDef,
     DeletePartitionRequestRequestTypeDef,
+    DeleteRegistryResponseTypeDef,
     DeleteResourcePolicyRequestRequestTypeDef,
     SchemaIdTypeDef,
+    DeleteSchemaResponseTypeDef,
     DeleteSecurityConfigurationRequestRequestTypeDef,
     DeleteSessionRequestRequestTypeDef,
+    DeleteSessionResponseTypeDef,
     DeleteTableRequestRequestTypeDef,
     DeleteTableVersionRequestRequestTypeDef,
     DeleteTriggerRequestRequestTypeDef,
+    DeleteTriggerResponseTypeDef,
     DeleteUserDefinedFunctionRequestRequestTypeDef,
     DeleteWorkflowRequestRequestTypeDef,
+    DeleteWorkflowResponseTypeDef,
     DevEndpointCustomLibrariesTypeDef,
     DirectSchemaChangePolicyTypeDef,
     NullCheckBoxListTypeDef,
     TransformConfigParameterTypeDef,
     EdgeTypeDef,
     JobBookmarksEncryptionTypeDef,
     S3EncryptionTypeDef,
     ErrorDetailsTypeDef,
     ExportLabelsTaskRunPropertiesTypeDef,
+    FederatedTableTypeDef,
     FilterValueTypeDef,
     FindMatchesParametersTypeDef,
     FindMatchesTaskRunPropertiesTypeDef,
     GetBlueprintRequestRequestTypeDef,
     GetBlueprintRunRequestRequestTypeDef,
     GetBlueprintRunsRequestRequestTypeDef,
     GetCatalogImportStatusRequestRequestTypeDef,
     GetClassifierRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetClassifiersRequestGetClassifiersPaginateTypeDef,
     GetClassifiersRequestRequestTypeDef,
     GetColumnStatisticsForPartitionRequestRequestTypeDef,
     GetColumnStatisticsForTableRequestRequestTypeDef,
     GetConnectionRequestRequestTypeDef,
     GetConnectionsFilterTypeDef,
+    GetCrawlerMetricsRequestGetCrawlerMetricsPaginateTypeDef,
     GetCrawlerMetricsRequestRequestTypeDef,
     GetCrawlerRequestRequestTypeDef,
+    GetCrawlersRequestGetCrawlersPaginateTypeDef,
     GetCrawlersRequestRequestTypeDef,
     GetCustomEntityTypeRequestRequestTypeDef,
+    GetCustomEntityTypeResponseTypeDef,
     GetDataCatalogEncryptionSettingsRequestRequestTypeDef,
     GetDataQualityResultRequestRequestTypeDef,
     GetDataQualityRuleRecommendationRunRequestRequestTypeDef,
     GetDataQualityRulesetEvaluationRunRequestRequestTypeDef,
     GetDataQualityRulesetRequestRequestTypeDef,
     GetDatabaseRequestRequestTypeDef,
+    GetDatabasesRequestGetDatabasesPaginateTypeDef,
     GetDatabasesRequestRequestTypeDef,
     GetDataflowGraphRequestRequestTypeDef,
     GetDevEndpointRequestRequestTypeDef,
+    GetDevEndpointsRequestGetDevEndpointsPaginateTypeDef,
     GetDevEndpointsRequestRequestTypeDef,
     GetJobBookmarkRequestRequestTypeDef,
     JobBookmarkEntryTypeDef,
     GetJobRequestRequestTypeDef,
     GetJobRunRequestRequestTypeDef,
+    GetJobRunsRequestGetJobRunsPaginateTypeDef,
     GetJobRunsRequestRequestTypeDef,
+    GetJobsRequestGetJobsPaginateTypeDef,
     GetJobsRequestRequestTypeDef,
     GetMLTaskRunRequestRequestTypeDef,
     TaskRunFilterCriteriaTypeDef,
     TaskRunSortCriteriaTypeDef,
     GetMLTransformRequestRequestTypeDef,
     SchemaColumnTypeDef,
     TransformSortCriteriaTypeDef,
     MappingEntryTypeDef,
+    GetPartitionIndexesRequestGetPartitionIndexesPaginateTypeDef,
     GetPartitionIndexesRequestRequestTypeDef,
     GetPartitionRequestRequestTypeDef,
     SegmentTypeDef,
+    GetPlanResponseTypeDef,
+    GetRegistryResponseTypeDef,
+    GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef,
     GetResourcePoliciesRequestRequestTypeDef,
     GluePolicyTypeDef,
     GetResourcePolicyRequestRequestTypeDef,
+    GetResourcePolicyResponseTypeDef,
+    GetSchemaByDefinitionResponseTypeDef,
+    GetSchemaResponseTypeDef,
     SchemaVersionNumberTypeDef,
+    GetSchemaVersionResponseTypeDef,
+    GetSchemaVersionsDiffResponseTypeDef,
     GetSecurityConfigurationRequestRequestTypeDef,
+    GetSecurityConfigurationsRequestGetSecurityConfigurationsPaginateTypeDef,
     GetSecurityConfigurationsRequestRequestTypeDef,
     GetSessionRequestRequestTypeDef,
     GetStatementRequestRequestTypeDef,
     GetTableRequestRequestTypeDef,
     GetTableVersionRequestRequestTypeDef,
+    GetTableVersionsRequestGetTableVersionsPaginateTypeDef,
     GetTableVersionsRequestRequestTypeDef,
+    GetTablesRequestGetTablesPaginateTypeDef,
     GetTablesRequestRequestTypeDef,
     GetTagsRequestRequestTypeDef,
+    GetTagsResponseTypeDef,
     GetTriggerRequestRequestTypeDef,
+    GetTriggersRequestGetTriggersPaginateTypeDef,
     GetTriggersRequestRequestTypeDef,
     GetUserDefinedFunctionRequestRequestTypeDef,
+    GetUserDefinedFunctionsRequestGetUserDefinedFunctionsPaginateTypeDef,
     GetUserDefinedFunctionsRequestRequestTypeDef,
     GetWorkflowRequestRequestTypeDef,
     GetWorkflowRunPropertiesRequestRequestTypeDef,
+    GetWorkflowRunPropertiesResponseTypeDef,
     GetWorkflowRunRequestRequestTypeDef,
     GetWorkflowRunsRequestRequestTypeDef,
     GlueStudioSchemaColumnTypeDef,
     S3SourceAdditionalOptionsTypeDef,
     ImportCatalogToGlueRequestRequestTypeDef,
     ImportLabelsTaskRunPropertiesTypeDef,
     JDBCConnectorOptionsTypeDef,
     PredecessorTypeDef,
     JoinColumnTypeDef,
     KeySchemaElementTypeDef,
     LabelingSetGenerationTaskRunPropertiesTypeDef,
     ListBlueprintsRequestRequestTypeDef,
+    ListBlueprintsResponseTypeDef,
     ListCrawlersRequestRequestTypeDef,
+    ListCrawlersResponseTypeDef,
     ListCustomEntityTypesRequestRequestTypeDef,
     ListDevEndpointsRequestRequestTypeDef,
+    ListDevEndpointsResponseTypeDef,
     ListJobsRequestRequestTypeDef,
+    ListJobsResponseTypeDef,
+    ListMLTransformsResponseTypeDef,
+    ListRegistriesInputListRegistriesPaginateTypeDef,
     ListRegistriesInputRequestTypeDef,
     RegistryListItemTypeDef,
     SchemaVersionListItemTypeDef,
     SchemaListItemTypeDef,
     ListSessionsRequestRequestTypeDef,
     ListStatementsRequestRequestTypeDef,
     ListTriggersRequestRequestTypeDef,
+    ListTriggersResponseTypeDef,
     ListWorkflowsRequestRequestTypeDef,
+    ListWorkflowsResponseTypeDef,
     MLUserDataEncryptionTypeDef,
     MappingTypeDef,
     OtherMetadataValueListItemTypeDef,
     MetadataKeyValuePairTypeDef,
     OrderTypeDef,
+    PaginatorConfigTypeDef,
     PropertyPredicateTypeDef,
     PutResourcePolicyRequestRequestTypeDef,
+    PutResourcePolicyResponseTypeDef,
+    PutSchemaVersionMetadataResponseTypeDef,
     PutWorkflowRunPropertiesRequestRequestTypeDef,
     UpsertRedshiftTargetOptionsTypeDef,
+    RegisterSchemaVersionResponseTypeDef,
+    RemoveSchemaVersionMetadataResponseTypeDef,
     ResetJobBookmarkRequestRequestTypeDef,
     ResourceUriTypeDef,
+    ResponseMetadataTypeDef,
     ResumeWorkflowRunRequestRequestTypeDef,
+    ResumeWorkflowRunResponseTypeDef,
     RunStatementRequestRequestTypeDef,
+    RunStatementResponseTypeDef,
     S3DirectSourceAdditionalOptionsTypeDef,
     SortCriterionTypeDef,
     SerDeInfoTypeDef,
     SkewedInfoTypeDef,
     SqlAliasTypeDef,
     StartBlueprintRunRequestRequestTypeDef,
+    StartBlueprintRunResponseTypeDef,
     StartCrawlerRequestRequestTypeDef,
     StartCrawlerScheduleRequestRequestTypeDef,
+    StartDataQualityRuleRecommendationRunResponseTypeDef,
+    StartDataQualityRulesetEvaluationRunResponseTypeDef,
     StartExportLabelsTaskRunRequestRequestTypeDef,
+    StartExportLabelsTaskRunResponseTypeDef,
     StartImportLabelsTaskRunRequestRequestTypeDef,
+    StartImportLabelsTaskRunResponseTypeDef,
+    StartJobRunResponseTypeDef,
     StartMLEvaluationTaskRunRequestRequestTypeDef,
+    StartMLEvaluationTaskRunResponseTypeDef,
     StartMLLabelingSetGenerationTaskRunRequestRequestTypeDef,
+    StartMLLabelingSetGenerationTaskRunResponseTypeDef,
     StartTriggerRequestRequestTypeDef,
+    StartTriggerResponseTypeDef,
     StartWorkflowRunRequestRequestTypeDef,
+    StartWorkflowRunResponseTypeDef,
     StartingEventBatchConditionTypeDef,
     StatementOutputDataTypeDef,
     StopCrawlerRequestRequestTypeDef,
     StopCrawlerScheduleRequestRequestTypeDef,
     StopSessionRequestRequestTypeDef,
+    StopSessionResponseTypeDef,
     StopTriggerRequestRequestTypeDef,
+    StopTriggerResponseTypeDef,
     StopWorkflowRunRequestRequestTypeDef,
     TableIdentifierTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateBlueprintRequestRequestTypeDef,
+    UpdateBlueprintResponseTypeDef,
     UpdateCsvClassifierRequestTypeDef,
     UpdateGrokClassifierRequestTypeDef,
     UpdateJsonClassifierRequestTypeDef,
     UpdateXMLClassifierRequestTypeDef,
     UpdateCrawlerScheduleRequestRequestTypeDef,
     UpdateDataQualityRulesetRequestRequestTypeDef,
+    UpdateDataQualityRulesetResponseTypeDef,
     UpdateJobFromSourceControlRequestRequestTypeDef,
+    UpdateJobFromSourceControlResponseTypeDef,
+    UpdateJobResponseTypeDef,
+    UpdateMLTransformResponseTypeDef,
+    UpdateRegistryResponseTypeDef,
+    UpdateSchemaResponseTypeDef,
     UpdateSourceControlFromJobRequestRequestTypeDef,
+    UpdateSourceControlFromJobResponseTypeDef,
     UpdateWorkflowRequestRequestTypeDef,
+    UpdateWorkflowResponseTypeDef,
     WorkflowRunStatisticsTypeDef,
     ActionTypeDef,
     StartJobRunRequestRequestTypeDef,
     AggregateTypeDef,
+    AmazonRedshiftNodeDataTypeDef,
     GetUnfilteredPartitionMetadataRequestRequestTypeDef,
     GetUnfilteredTableMetadataRequestRequestTypeDef,
     BackfillErrorTypeDef,
     BatchDeletePartitionRequestRequestTypeDef,
     BatchGetPartitionRequestRequestTypeDef,
-    CancelMLTaskRunResponseTypeDef,
-    CheckSchemaVersionValidityResponseTypeDef,
-    CreateBlueprintResponseTypeDef,
-    CreateCustomEntityTypeResponseTypeDef,
-    CreateDataQualityRulesetResponseTypeDef,
-    CreateDevEndpointResponseTypeDef,
-    CreateJobResponseTypeDef,
-    CreateMLTransformResponseTypeDef,
-    CreateRegistryResponseTypeDef,
-    CreateSchemaResponseTypeDef,
-    CreateScriptResponseTypeDef,
-    CreateSecurityConfigurationResponseTypeDef,
-    CreateTriggerResponseTypeDef,
-    CreateWorkflowResponseTypeDef,
-    DeleteBlueprintResponseTypeDef,
-    DeleteCustomEntityTypeResponseTypeDef,
-    DeleteJobResponseTypeDef,
-    DeleteMLTransformResponseTypeDef,
-    DeleteRegistryResponseTypeDef,
-    DeleteSchemaResponseTypeDef,
-    DeleteSessionResponseTypeDef,
-    DeleteTriggerResponseTypeDef,
-    DeleteWorkflowResponseTypeDef,
-    GetCustomEntityTypeResponseTypeDef,
-    GetPlanResponseTypeDef,
-    GetRegistryResponseTypeDef,
-    GetResourcePolicyResponseTypeDef,
-    GetSchemaByDefinitionResponseTypeDef,
-    GetSchemaResponseTypeDef,
-    GetSchemaVersionResponseTypeDef,
-    GetSchemaVersionsDiffResponseTypeDef,
-    GetTagsResponseTypeDef,
-    GetWorkflowRunPropertiesResponseTypeDef,
-    ListBlueprintsResponseTypeDef,
-    ListCrawlersResponseTypeDef,
-    ListDevEndpointsResponseTypeDef,
-    ListJobsResponseTypeDef,
-    ListMLTransformsResponseTypeDef,
-    ListTriggersResponseTypeDef,
-    ListWorkflowsResponseTypeDef,
-    PutResourcePolicyResponseTypeDef,
-    PutSchemaVersionMetadataResponseTypeDef,
-    RegisterSchemaVersionResponseTypeDef,
-    RemoveSchemaVersionMetadataResponseTypeDef,
-    ResumeWorkflowRunResponseTypeDef,
-    RunStatementResponseTypeDef,
-    StartBlueprintRunResponseTypeDef,
-    StartDataQualityRuleRecommendationRunResponseTypeDef,
-    StartDataQualityRulesetEvaluationRunResponseTypeDef,
-    StartExportLabelsTaskRunResponseTypeDef,
-    StartImportLabelsTaskRunResponseTypeDef,
-    StartJobRunResponseTypeDef,
-    StartMLEvaluationTaskRunResponseTypeDef,
-    StartMLLabelingSetGenerationTaskRunResponseTypeDef,
-    StartTriggerResponseTypeDef,
-    StartWorkflowRunResponseTypeDef,
-    StopSessionResponseTypeDef,
-    StopTriggerResponseTypeDef,
-    UpdateBlueprintResponseTypeDef,
-    UpdateDataQualityRulesetResponseTypeDef,
-    UpdateJobFromSourceControlResponseTypeDef,
-    UpdateJobResponseTypeDef,
-    UpdateMLTransformResponseTypeDef,
-    UpdateRegistryResponseTypeDef,
-    UpdateSchemaResponseTypeDef,
-    UpdateSourceControlFromJobResponseTypeDef,
-    UpdateWorkflowResponseTypeDef,
     BatchDeleteConnectionResponseTypeDef,
     BatchStopJobRunErrorTypeDef,
     BatchUpdatePartitionFailureEntryTypeDef,
     ColumnErrorTypeDef,
     PartitionErrorTypeDef,
     TableErrorTypeDef,
     TableVersionErrorTypeDef,
@@ -881,57 +902,42 @@
     DataQualityRulesetListDetailsTypeDef,
     GetDataQualityRulesetResponseTypeDef,
     DataSourceTypeDef,
     CreatePartitionIndexRequestRequestTypeDef,
     CreateSchemaInputRequestTypeDef,
     DeleteRegistryInputRequestTypeDef,
     GetRegistryInputRequestTypeDef,
+    ListSchemasInputListSchemasPaginateTypeDef,
     ListSchemasInputRequestTypeDef,
     UpdateRegistryInputRequestTypeDef,
     CreateSessionRequestRequestTypeDef,
     SessionTypeDef,
+    EvaluateDataQualityMultiFrameTypeDef,
     EvaluateDataQualityTypeDef,
     DataCatalogEncryptionSettingsTypeDef,
     PrincipalPermissionsTypeDef,
     NullValueFieldTypeDef,
     DecimalColumnStatisticsDataTypeDef,
     DeleteSchemaInputRequestTypeDef,
     DeleteSchemaVersionsInputRequestTypeDef,
     GetSchemaByDefinitionInputRequestTypeDef,
     GetSchemaInputRequestTypeDef,
+    ListSchemaVersionsInputListSchemaVersionsPaginateTypeDef,
     ListSchemaVersionsInputRequestTypeDef,
     RegisterSchemaVersionInputRequestTypeDef,
     SchemaReferenceTypeDef,
     UpdateDevEndpointRequestRequestTypeDef,
     S3DeltaDirectTargetTypeDef,
     S3DirectTargetTypeDef,
     S3GlueParquetTargetTypeDef,
     S3HudiDirectTargetTypeDef,
-    DynamicTransformTypeDef,
     EncryptionConfigurationTypeDef,
     SchemaVersionErrorItemTypeDef,
     FilterExpressionTypeDef,
     TransformParametersTypeDef,
-    GetClassifiersRequestGetClassifiersPaginateTypeDef,
-    GetCrawlerMetricsRequestGetCrawlerMetricsPaginateTypeDef,
-    GetCrawlersRequestGetCrawlersPaginateTypeDef,
-    GetDatabasesRequestGetDatabasesPaginateTypeDef,
-    GetDevEndpointsRequestGetDevEndpointsPaginateTypeDef,
-    GetJobRunsRequestGetJobRunsPaginateTypeDef,
-    GetJobsRequestGetJobsPaginateTypeDef,
-    GetPartitionIndexesRequestGetPartitionIndexesPaginateTypeDef,
-    GetResourcePoliciesRequestGetResourcePoliciesPaginateTypeDef,
-    GetSecurityConfigurationsRequestGetSecurityConfigurationsPaginateTypeDef,
-    GetTableVersionsRequestGetTableVersionsPaginateTypeDef,
-    GetTablesRequestGetTablesPaginateTypeDef,
-    GetTriggersRequestGetTriggersPaginateTypeDef,
-    GetUserDefinedFunctionsRequestGetUserDefinedFunctionsPaginateTypeDef,
-    ListRegistriesInputListRegistriesPaginateTypeDef,
-    ListSchemaVersionsInputListSchemaVersionsPaginateTypeDef,
-    ListSchemasInputListSchemasPaginateTypeDef,
     GetConnectionsRequestGetConnectionsPaginateTypeDef,
     GetConnectionsRequestRequestTypeDef,
     GetJobBookmarkResponseTypeDef,
     ResetJobBookmarkResponseTypeDef,
     GetMLTaskRunsRequestRequestTypeDef,
     TransformFilterCriteriaTypeDef,
     GetMappingResponseTypeDef,
@@ -958,14 +964,16 @@
     RemoveSchemaVersionMetadataInputRequestTypeDef,
     RedshiftTargetTypeDef,
     UserDefinedFunctionInputTypeDef,
     UserDefinedFunctionTypeDef,
     SearchTablesRequestRequestTypeDef,
     StatementOutputTypeDef,
     UpdateClassifierRequestRequestTypeDef,
+    AmazonRedshiftSourceTypeDef,
+    AmazonRedshiftTargetTypeDef,
     PartitionIndexDescriptorTypeDef,
     BatchStopJobRunResponseTypeDef,
     BatchUpdatePartitionResponseTypeDef,
     BatchCreatePartitionResponseTypeDef,
     BatchDeletePartitionResponseTypeDef,
     BatchDeleteTableResponseTypeDef,
     BatchDeleteTableVersionResponseTypeDef,
@@ -1019,14 +1027,15 @@
     UpdateMLTransformRequestRequestTypeDef,
     GetMLTransformsRequestRequestTypeDef,
     ListMLTransformsRequestRequestTypeDef,
     AthenaConnectorSourceTypeDef,
     CatalogDeltaSourceTypeDef,
     CatalogHudiSourceTypeDef,
     CustomCodeTypeDef,
+    DynamicTransformTypeDef,
     JDBCConnectorSourceTypeDef,
     JDBCConnectorTargetTypeDef,
     S3CatalogDeltaSourceTypeDef,
     S3CatalogHudiSourceTypeDef,
     S3CsvSourceTypeDef,
     S3DeltaSourceTypeDef,
     S3HudiSourceTypeDef,
@@ -1134,43 +1143,43 @@
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

### Comparing `types-aiobotocore-glue-2.5.0.post1/types_aiobotocore_glue.egg-info/SOURCES.txt` & `types-aiobotocore-glue-2.5.1/types_aiobotocore_glue.egg-info/SOURCES.txt`

 * *Files identical despite different names*

