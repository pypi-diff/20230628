# Comparing `tmp/types-aiobotocore-migrationhubstrategy-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-migrationhubstrategy-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-migrationhubstrategy-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:01 2023, max compression
+gzip compressed data, was "types-aiobotocore-migrationhubstrategy-2.5.1.tar", last modified: Wed Jun 28 01:43:53 2023, max compression
```

## Comparing `types-aiobotocore-migrationhubstrategy-2.5.0.post1.tar` & `types-aiobotocore-migrationhubstrategy-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:01.411443 types-aiobotocore-migrationhubstrategy-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:18:53.000000 types-aiobotocore-migrationhubstrategy-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    18975 2023-03-11 12:27:01.411443 types-aiobotocore-migrationhubstrategy-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    17337 2023-03-11 12:18:53.000000 types-aiobotocore-migrationhubstrategy-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:01.411443 types-aiobotocore-migrationhubstrategy-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2222 2023-03-11 12:18:52.000000 types-aiobotocore-migrationhubstrategy-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:01.411443 types-aiobotocore-migrationhubstrategy-2.5.0.post1/types_aiobotocore_migrationhubstrategy/
--rw-r--r--   0 runner    (1001) docker     (123)     1702 2023-03-11 12:18:53.000000 types-aiobotocore-migrationhubstrategy-2.5.0.post1/types_aiobotocore_migrationhubstrategy/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1701 2023-03-11 12:18:53.000000 types-aiobotocore-migrationhubstrategy-2.5.0.post1/types_aiobotocore_migrationhubstrategy/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     1025 2023-03-11 12:18:53.000000 types-aiobotocore-migrationhubstrategy-2.5.0.post1/types_aiobotocore_migrationhubstrategy/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    22477 2023-03-11 12:18:53.000000 types-aiobotocore-migrationhubstrategy-2.5.0.post1/types_aiobotocore_migrationhubstrategy/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    22442 2023-03-11 12:18:53.000000 types-aiobotocore-migrationhubstrategy-2.5.0.post1/types_aiobotocore_migrationhubstrategy/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    14878 2023-03-11 12:18:53.000000 types-aiobotocore-migrationhubstrategy-2.5.0.post1/types_aiobotocore_migrationhubstrategy/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    14876 2023-03-11 12:18:53.000000 types-aiobotocore-migrationhubstrategy-2.5.0.post1/types_aiobotocore_migrationhubstrategy/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7720 2023-03-11 12:18:53.000000 types-aiobotocore-migrationhubstrategy-2.5.0.post1/types_aiobotocore_migrationhubstrategy/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     7712 2023-03-11 12:18:53.000000 types-aiobotocore-migrationhubstrategy-2.5.0.post1/types_aiobotocore_migrationhubstrategy/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:18:53.000000 types-aiobotocore-migrationhubstrategy-2.5.0.post1/types_aiobotocore_migrationhubstrategy/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    30330 2023-03-11 12:18:54.000000 types-aiobotocore-migrationhubstrategy-2.5.0.post1/types_aiobotocore_migrationhubstrategy/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    30319 2023-03-11 12:18:53.000000 types-aiobotocore-migrationhubstrategy-2.5.0.post1/types_aiobotocore_migrationhubstrategy/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:18:53.000000 types-aiobotocore-migrationhubstrategy-2.5.0.post1/types_aiobotocore_migrationhubstrategy/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:01.411443 types-aiobotocore-migrationhubstrategy-2.5.0.post1/types_aiobotocore_migrationhubstrategy.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    18975 2023-03-11 12:27:01.000000 types-aiobotocore-migrationhubstrategy-2.5.0.post1/types_aiobotocore_migrationhubstrategy.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1060 2023-03-11 12:27:01.000000 types-aiobotocore-migrationhubstrategy-2.5.0.post1/types_aiobotocore_migrationhubstrategy.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:01.000000 types-aiobotocore-migrationhubstrategy-2.5.0.post1/types_aiobotocore_migrationhubstrategy.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:01.000000 types-aiobotocore-migrationhubstrategy-2.5.0.post1/types_aiobotocore_migrationhubstrategy.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:01.000000 types-aiobotocore-migrationhubstrategy-2.5.0.post1/types_aiobotocore_migrationhubstrategy.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       39 2023-03-11 12:27:01.000000 types-aiobotocore-migrationhubstrategy-2.5.0.post1/types_aiobotocore_migrationhubstrategy.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:53.378181 types-aiobotocore-migrationhubstrategy-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:35:36.000000 types-aiobotocore-migrationhubstrategy-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    19190 2023-06-28 01:43:53.378181 types-aiobotocore-migrationhubstrategy-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    17558 2023-06-28 01:35:36.000000 types-aiobotocore-migrationhubstrategy-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:53.378181 types-aiobotocore-migrationhubstrategy-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2216 2023-06-28 01:35:36.000000 types-aiobotocore-migrationhubstrategy-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:53.378181 types-aiobotocore-migrationhubstrategy-2.5.1/types_aiobotocore_migrationhubstrategy/
+-rw-r--r--   0 runner    (1001) docker     (123)     1702 2023-06-28 01:35:36.000000 types-aiobotocore-migrationhubstrategy-2.5.1/types_aiobotocore_migrationhubstrategy/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1701 2023-06-28 01:35:36.000000 types-aiobotocore-migrationhubstrategy-2.5.1/types_aiobotocore_migrationhubstrategy/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     1013 2023-06-28 01:35:36.000000 types-aiobotocore-migrationhubstrategy-2.5.1/types_aiobotocore_migrationhubstrategy/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22477 2023-06-28 01:35:37.000000 types-aiobotocore-migrationhubstrategy-2.5.1/types_aiobotocore_migrationhubstrategy/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22442 2023-06-28 01:35:37.000000 types-aiobotocore-migrationhubstrategy-2.5.1/types_aiobotocore_migrationhubstrategy/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    15664 2023-06-28 01:35:37.000000 types-aiobotocore-migrationhubstrategy-2.5.1/types_aiobotocore_migrationhubstrategy/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15662 2023-06-28 01:35:37.000000 types-aiobotocore-migrationhubstrategy-2.5.1/types_aiobotocore_migrationhubstrategy/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     7610 2023-06-28 01:35:37.000000 types-aiobotocore-migrationhubstrategy-2.5.1/types_aiobotocore_migrationhubstrategy/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7603 2023-06-28 01:35:37.000000 types-aiobotocore-migrationhubstrategy-2.5.1/types_aiobotocore_migrationhubstrategy/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:35:36.000000 types-aiobotocore-migrationhubstrategy-2.5.1/types_aiobotocore_migrationhubstrategy/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    31774 2023-06-28 01:35:38.000000 types-aiobotocore-migrationhubstrategy-2.5.1/types_aiobotocore_migrationhubstrategy/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    31763 2023-06-28 01:35:37.000000 types-aiobotocore-migrationhubstrategy-2.5.1/types_aiobotocore_migrationhubstrategy/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:35:36.000000 types-aiobotocore-migrationhubstrategy-2.5.1/types_aiobotocore_migrationhubstrategy/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:53.378181 types-aiobotocore-migrationhubstrategy-2.5.1/types_aiobotocore_migrationhubstrategy.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    19190 2023-06-28 01:43:53.000000 types-aiobotocore-migrationhubstrategy-2.5.1/types_aiobotocore_migrationhubstrategy.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1060 2023-06-28 01:43:53.000000 types-aiobotocore-migrationhubstrategy-2.5.1/types_aiobotocore_migrationhubstrategy.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:53.000000 types-aiobotocore-migrationhubstrategy-2.5.1/types_aiobotocore_migrationhubstrategy.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:53.000000 types-aiobotocore-migrationhubstrategy-2.5.1/types_aiobotocore_migrationhubstrategy.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:53.000000 types-aiobotocore-migrationhubstrategy-2.5.1/types_aiobotocore_migrationhubstrategy.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       39 2023-06-28 01:43:53.000000 types-aiobotocore-migrationhubstrategy-2.5.1/types_aiobotocore_migrationhubstrategy.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-migrationhubstrategy-2.5.0.post1/LICENSE` & `types-aiobotocore-migrationhubstrategy-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-migrationhubstrategy-2.5.0.post1/PKG-INFO` & `types-aiobotocore-migrationhubstrategy-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-migrationhubstrategy
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MigrationHubStrategyRecommendations 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MigrationHubStrategyRecommendations 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhubstrategy/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-migrationhubstrategy"></a>
 
 # types-aiobotocore-migrationhubstrategy
 
 [![PyPI - types-aiobotocore-migrationhubstrategy](https://img.shields.io/pypi/v/types-aiobotocore-migrationhubstrategy.svg?color=blue)](https://pypi.org/project/types-aiobotocore-migrationhubstrategy)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-migrationhubstrategy.svg?color=blue)](https://pypi.org/project/types-aiobotocore-migrationhubstrategy)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhubstrategy/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-migrationhubstrategy?color=blue)](https://pypistats.org/packages/types-aiobotocore-migrationhubstrategy)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MigrationHubStrategyRecommendations 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhubstrategy.html#MigrationHubStrategyRecommendations)
+[aiobotocore.MigrationHubStrategyRecommendations 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhubstrategy.html#MigrationHubStrategyRecommendations)
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
 [types-aiobotocore-migrationhubstrategy docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhubstrategy/).
 
 See how it helps to find and fix potential bugs:
 
@@ -308,22 +308,24 @@
 ### Literals
 
 `types_aiobotocore_migrationhubstrategy.literals` module contains literals
 extracted from shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_migrationhubstrategy.literals import (
+    AnalysisTypeType,
     AntipatternReportStatusType,
     AppTypeType,
     AppUnitErrorCategoryType,
     ApplicationComponentCriteriaType,
     ApplicationModeType,
     AssessmentStatusType,
     AuthTypeType,
     AwsManagedTargetDestinationType,
+    BinaryAnalyzerNameType,
     CollectorHealthType,
     ConditionType,
     DataSourceTypeType,
     DatabaseManagementPreferenceType,
     GetServerDetailsPaginatorName,
     GroupNameType,
     HeterogeneousTargetDatabaseEngineType,
@@ -336,22 +338,24 @@
     ListServersPaginatorName,
     NoPreferenceTargetDestinationType,
     OSTypeType,
     OutputFormatType,
     PipelineTypeType,
     RecommendationReportStatusType,
     ResourceSubTypeType,
+    RunTimeAnalyzerNameType,
     RunTimeAssessmentStatusType,
     RuntimeAnalysisStatusType,
     SelfManageTargetDestinationType,
     ServerCriteriaType,
     ServerErrorCategoryType,
     ServerOsTypeType,
     SeverityType,
     SortOrderType,
+    SourceCodeAnalyzerNameType,
     SrcCodeOrDbAnalysisStatusType,
     StrategyRecommendationType,
     StrategyType,
     TargetDatabaseEngineType,
     TargetDestinationType,
     TransformationToolNameType,
     VersionControlType,
@@ -360,31 +364,33 @@
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
 
 
-def check_value(value: AntipatternReportStatusType) -> bool:
+def check_value(value: AnalysisTypeType) -> bool:
     ...
 ```
 
 <a id="typed-dictionaries"></a>
 
 ### Typed dictionaries
 
 `types_aiobotocore_migrationhubstrategy.type_defs` module contains structures
 and shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_migrationhubstrategy.type_defs import (
+    AnalysisStatusUnionTypeDef,
+    AnalyzerNameUnionTypeDef,
+    S3ObjectTypeDef,
     AntipatternSeveritySummaryTypeDef,
     AppUnitErrorTypeDef,
     DatabaseConfigDetailTypeDef,
-    S3ObjectTypeDef,
     SourceCodeRepositoryTypeDef,
     ApplicationComponentStatusSummaryTypeDef,
     ApplicationComponentSummaryTypeDef,
     ServerStatusSummaryTypeDef,
     ServerSummaryTypeDef,
     StrategySummaryTypeDef,
     AssessmentTargetTypeDef,
@@ -397,123 +403,125 @@
     VcenterBasedRemoteInfoTypeDef,
     VersionControlInfoTypeDef,
     DataCollectionDetailsTypeDef,
     HeterogeneousTypeDef,
     HomogeneousTypeDef,
     NoDatabaseMigrationPreferenceTypeDef,
     GetApplicationComponentDetailsRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     GetApplicationComponentStrategiesRequestRequestTypeDef,
     GetAssessmentRequestRequestTypeDef,
     GetImportFileTaskRequestRequestTypeDef,
+    GetImportFileTaskResponseTypeDef,
+    GetLatestAssessmentIdResponseTypeDef,
     GetRecommendationReportDetailsRequestRequestTypeDef,
     RecommendationReportDetailsTypeDef,
-    PaginatorConfigTypeDef,
+    GetServerDetailsRequestGetServerDetailsPaginateTypeDef,
     GetServerDetailsRequestRequestTypeDef,
     GetServerStrategiesRequestRequestTypeDef,
     GroupTypeDef,
     ImportFileTaskInformationTypeDef,
+    ListCollectorsRequestListCollectorsPaginateTypeDef,
     ListCollectorsRequestRequestTypeDef,
+    ListImportFileTaskRequestListImportFileTaskPaginateTypeDef,
     ListImportFileTaskRequestRequestTypeDef,
     NoManagementPreferenceTypeDef,
     SelfManageResourcesTypeDef,
     NetworkInfoTypeDef,
     OSInfoTypeDef,
+    PaginatorConfigTypeDef,
     TransformationToolTypeDef,
+    ResponseMetadataTypeDef,
     ServerErrorTypeDef,
     SourceCodeTypeDef,
+    StartAssessmentResponseTypeDef,
+    StartImportFileTaskResponseTypeDef,
+    StartRecommendationReportGenerationResponseTypeDef,
     StopAssessmentRequestRequestTypeDef,
     StrategyOptionTypeDef,
+    AntipatternReportResultTypeDef,
     AssessmentSummaryTypeDef,
     StartAssessmentRequestRequestTypeDef,
     PrioritizeBusinessGoalsTypeDef,
     ConfigurationSummaryTypeDef,
-    DatabaseMigrationPreferenceTypeDef,
     GetAssessmentResponseTypeDef,
-    GetImportFileTaskResponseTypeDef,
-    GetLatestAssessmentIdResponseTypeDef,
-    StartAssessmentResponseTypeDef,
-    StartImportFileTaskResponseTypeDef,
-    StartRecommendationReportGenerationResponseTypeDef,
+    DatabaseMigrationPreferenceTypeDef,
     GetRecommendationReportDetailsResponseTypeDef,
-    GetServerDetailsRequestGetServerDetailsPaginateTypeDef,
-    ListCollectorsRequestListCollectorsPaginateTypeDef,
-    ListImportFileTaskRequestListImportFileTaskPaginateTypeDef,
     ListApplicationComponentsRequestListApplicationComponentsPaginateTypeDef,
     ListApplicationComponentsRequestRequestTypeDef,
     ListServersRequestListServersPaginateTypeDef,
     ListServersRequestRequestTypeDef,
     StartImportFileTaskRequestRequestTypeDef,
     StartRecommendationReportGenerationRequestRequestTypeDef,
     ListImportFileTaskResponseTypeDef,
     ManagementPreferenceTypeDef,
     SystemInfoTypeDef,
     RecommendationSetTypeDef,
     UpdateApplicationComponentConfigRequestRequestTypeDef,
     UpdateServerConfigRequestRequestTypeDef,
+    ResultTypeDef,
     GetPortfolioSummaryResponseTypeDef,
     CollectorTypeDef,
     DatabasePreferencesTypeDef,
     ApplicationPreferencesTypeDef,
-    ApplicationComponentDetailTypeDef,
     ApplicationComponentStrategyTypeDef,
     ServerDetailTypeDef,
     ServerStrategyTypeDef,
+    ApplicationComponentDetailTypeDef,
     ListCollectorsResponseTypeDef,
     GetPortfolioPreferencesResponseTypeDef,
     PutPortfolioPreferencesRequestRequestTypeDef,
-    GetApplicationComponentDetailsResponseTypeDef,
-    ListApplicationComponentsResponseTypeDef,
     GetApplicationComponentStrategiesResponseTypeDef,
     GetServerDetailsResponseTypeDef,
     ListServersResponseTypeDef,
     GetServerStrategiesResponseTypeDef,
+    GetApplicationComponentDetailsResponseTypeDef,
+    ListApplicationComponentsResponseTypeDef,
 )
 
 
-def get_structure() -> AntipatternSeveritySummaryTypeDef:
+def get_structure() -> AnalysisStatusUnionTypeDef:
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

### Comparing `types-aiobotocore-migrationhubstrategy-2.5.0.post1/README.md` & `types-aiobotocore-migrationhubstrategy-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-migrationhubstrategy"></a>
 
 # types-aiobotocore-migrationhubstrategy
 
 [![PyPI - types-aiobotocore-migrationhubstrategy](https://img.shields.io/pypi/v/types-aiobotocore-migrationhubstrategy.svg?color=blue)](https://pypi.org/project/types-aiobotocore-migrationhubstrategy)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-migrationhubstrategy.svg?color=blue)](https://pypi.org/project/types-aiobotocore-migrationhubstrategy)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhubstrategy/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-migrationhubstrategy?color=blue)](https://pypistats.org/packages/types-aiobotocore-migrationhubstrategy)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MigrationHubStrategyRecommendations 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhubstrategy.html#MigrationHubStrategyRecommendations)
+[aiobotocore.MigrationHubStrategyRecommendations 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhubstrategy.html#MigrationHubStrategyRecommendations)
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
 [types-aiobotocore-migrationhubstrategy docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhubstrategy/).
 
 See how it helps to find and fix potential bugs:
 
@@ -275,22 +275,24 @@
 ### Literals
 
 `types_aiobotocore_migrationhubstrategy.literals` module contains literals
 extracted from shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_migrationhubstrategy.literals import (
+    AnalysisTypeType,
     AntipatternReportStatusType,
     AppTypeType,
     AppUnitErrorCategoryType,
     ApplicationComponentCriteriaType,
     ApplicationModeType,
     AssessmentStatusType,
     AuthTypeType,
     AwsManagedTargetDestinationType,
+    BinaryAnalyzerNameType,
     CollectorHealthType,
     ConditionType,
     DataSourceTypeType,
     DatabaseManagementPreferenceType,
     GetServerDetailsPaginatorName,
     GroupNameType,
     HeterogeneousTargetDatabaseEngineType,
@@ -303,22 +305,24 @@
     ListServersPaginatorName,
     NoPreferenceTargetDestinationType,
     OSTypeType,
     OutputFormatType,
     PipelineTypeType,
     RecommendationReportStatusType,
     ResourceSubTypeType,
+    RunTimeAnalyzerNameType,
     RunTimeAssessmentStatusType,
     RuntimeAnalysisStatusType,
     SelfManageTargetDestinationType,
     ServerCriteriaType,
     ServerErrorCategoryType,
     ServerOsTypeType,
     SeverityType,
     SortOrderType,
+    SourceCodeAnalyzerNameType,
     SrcCodeOrDbAnalysisStatusType,
     StrategyRecommendationType,
     StrategyType,
     TargetDatabaseEngineType,
     TargetDestinationType,
     TransformationToolNameType,
     VersionControlType,
@@ -327,31 +331,33 @@
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
 
 
-def check_value(value: AntipatternReportStatusType) -> bool:
+def check_value(value: AnalysisTypeType) -> bool:
     ...
 ```
 
 <a id="typed-dictionaries"></a>
 
 ### Typed dictionaries
 
 `types_aiobotocore_migrationhubstrategy.type_defs` module contains structures
 and shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_migrationhubstrategy.type_defs import (
+    AnalysisStatusUnionTypeDef,
+    AnalyzerNameUnionTypeDef,
+    S3ObjectTypeDef,
     AntipatternSeveritySummaryTypeDef,
     AppUnitErrorTypeDef,
     DatabaseConfigDetailTypeDef,
-    S3ObjectTypeDef,
     SourceCodeRepositoryTypeDef,
     ApplicationComponentStatusSummaryTypeDef,
     ApplicationComponentSummaryTypeDef,
     ServerStatusSummaryTypeDef,
     ServerSummaryTypeDef,
     StrategySummaryTypeDef,
     AssessmentTargetTypeDef,
@@ -364,123 +370,125 @@
     VcenterBasedRemoteInfoTypeDef,
     VersionControlInfoTypeDef,
     DataCollectionDetailsTypeDef,
     HeterogeneousTypeDef,
     HomogeneousTypeDef,
     NoDatabaseMigrationPreferenceTypeDef,
     GetApplicationComponentDetailsRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     GetApplicationComponentStrategiesRequestRequestTypeDef,
     GetAssessmentRequestRequestTypeDef,
     GetImportFileTaskRequestRequestTypeDef,
+    GetImportFileTaskResponseTypeDef,
+    GetLatestAssessmentIdResponseTypeDef,
     GetRecommendationReportDetailsRequestRequestTypeDef,
     RecommendationReportDetailsTypeDef,
-    PaginatorConfigTypeDef,
+    GetServerDetailsRequestGetServerDetailsPaginateTypeDef,
     GetServerDetailsRequestRequestTypeDef,
     GetServerStrategiesRequestRequestTypeDef,
     GroupTypeDef,
     ImportFileTaskInformationTypeDef,
+    ListCollectorsRequestListCollectorsPaginateTypeDef,
     ListCollectorsRequestRequestTypeDef,
+    ListImportFileTaskRequestListImportFileTaskPaginateTypeDef,
     ListImportFileTaskRequestRequestTypeDef,
     NoManagementPreferenceTypeDef,
     SelfManageResourcesTypeDef,
     NetworkInfoTypeDef,
     OSInfoTypeDef,
+    PaginatorConfigTypeDef,
     TransformationToolTypeDef,
+    ResponseMetadataTypeDef,
     ServerErrorTypeDef,
     SourceCodeTypeDef,
+    StartAssessmentResponseTypeDef,
+    StartImportFileTaskResponseTypeDef,
+    StartRecommendationReportGenerationResponseTypeDef,
     StopAssessmentRequestRequestTypeDef,
     StrategyOptionTypeDef,
+    AntipatternReportResultTypeDef,
     AssessmentSummaryTypeDef,
     StartAssessmentRequestRequestTypeDef,
     PrioritizeBusinessGoalsTypeDef,
     ConfigurationSummaryTypeDef,
-    DatabaseMigrationPreferenceTypeDef,
     GetAssessmentResponseTypeDef,
-    GetImportFileTaskResponseTypeDef,
-    GetLatestAssessmentIdResponseTypeDef,
-    StartAssessmentResponseTypeDef,
-    StartImportFileTaskResponseTypeDef,
-    StartRecommendationReportGenerationResponseTypeDef,
+    DatabaseMigrationPreferenceTypeDef,
     GetRecommendationReportDetailsResponseTypeDef,
-    GetServerDetailsRequestGetServerDetailsPaginateTypeDef,
-    ListCollectorsRequestListCollectorsPaginateTypeDef,
-    ListImportFileTaskRequestListImportFileTaskPaginateTypeDef,
     ListApplicationComponentsRequestListApplicationComponentsPaginateTypeDef,
     ListApplicationComponentsRequestRequestTypeDef,
     ListServersRequestListServersPaginateTypeDef,
     ListServersRequestRequestTypeDef,
     StartImportFileTaskRequestRequestTypeDef,
     StartRecommendationReportGenerationRequestRequestTypeDef,
     ListImportFileTaskResponseTypeDef,
     ManagementPreferenceTypeDef,
     SystemInfoTypeDef,
     RecommendationSetTypeDef,
     UpdateApplicationComponentConfigRequestRequestTypeDef,
     UpdateServerConfigRequestRequestTypeDef,
+    ResultTypeDef,
     GetPortfolioSummaryResponseTypeDef,
     CollectorTypeDef,
     DatabasePreferencesTypeDef,
     ApplicationPreferencesTypeDef,
-    ApplicationComponentDetailTypeDef,
     ApplicationComponentStrategyTypeDef,
     ServerDetailTypeDef,
     ServerStrategyTypeDef,
+    ApplicationComponentDetailTypeDef,
     ListCollectorsResponseTypeDef,
     GetPortfolioPreferencesResponseTypeDef,
     PutPortfolioPreferencesRequestRequestTypeDef,
-    GetApplicationComponentDetailsResponseTypeDef,
-    ListApplicationComponentsResponseTypeDef,
     GetApplicationComponentStrategiesResponseTypeDef,
     GetServerDetailsResponseTypeDef,
     ListServersResponseTypeDef,
     GetServerStrategiesResponseTypeDef,
+    GetApplicationComponentDetailsResponseTypeDef,
+    ListApplicationComponentsResponseTypeDef,
 )
 
 
-def get_structure() -> AntipatternSeveritySummaryTypeDef:
+def get_structure() -> AnalysisStatusUnionTypeDef:
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

### Comparing `types-aiobotocore-migrationhubstrategy-2.5.0.post1/setup.py` & `types-aiobotocore-migrationhubstrategy-2.5.1/setup.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-migrationhubstrategy.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-migrationhubstrategy",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_migrationhubstrategy"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.MigrationHubStrategyRecommendations 2.5.0 service"
-        " generated with mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.MigrationHubStrategyRecommendations 2.5.1 service"
+        " generated with mypy-boto3-builder 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -48,11 +48,11 @@
     python_requires=">=3.7",
     project_urls={
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhubstrategy/",
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

### Comparing `types-aiobotocore-migrationhubstrategy-2.5.0.post1/types_aiobotocore_migrationhubstrategy/__init__.py` & `types-aiobotocore-migrationhubstrategy-2.5.1/types_aiobotocore_migrationhubstrategy/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-migrationhubstrategy-2.5.0.post1/types_aiobotocore_migrationhubstrategy/__init__.pyi` & `types-aiobotocore-migrationhubstrategy-2.5.1/types_aiobotocore_migrationhubstrategy/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-migrationhubstrategy-2.5.0.post1/types_aiobotocore_migrationhubstrategy/__main__.py` & `types-aiobotocore-migrationhubstrategy-2.5.1/types_aiobotocore_migrationhubstrategy/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.MigrationHubStrategyRecommendations 2.5.0\nVersion:      "
-        "   2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.MigrationHubStrategyRecommendations 2.5.1\nVersion:      "
+        "   2.5.1\nBuilder version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhubstrategy//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhubstrategy.html#MigrationHubStrategyRecommendations\nOther"
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

### Comparing `types-aiobotocore-migrationhubstrategy-2.5.0.post1/types_aiobotocore_migrationhubstrategy/client.py` & `types-aiobotocore-migrationhubstrategy-2.5.1/types_aiobotocore_migrationhubstrategy/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-migrationhubstrategy-2.5.0.post1/types_aiobotocore_migrationhubstrategy/client.pyi` & `types-aiobotocore-migrationhubstrategy-2.5.1/types_aiobotocore_migrationhubstrategy/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-migrationhubstrategy-2.5.0.post1/types_aiobotocore_migrationhubstrategy/literals.py` & `types-aiobotocore-migrationhubstrategy-2.5.1/types_aiobotocore_migrationhubstrategy/literals.py`

 * *Files 4% similar despite different names*

```diff
@@ -2,36 +2,38 @@
 Type annotations for migrationhubstrategy service literal definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhubstrategy/literals/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_migrationhubstrategy.literals import AntipatternReportStatusType
+    from types_aiobotocore_migrationhubstrategy.literals import AnalysisTypeType
 
-    data: AntipatternReportStatusType = "FAILED"
+    data: AnalysisTypeType = "BINARY_ANALYSIS"
     ```
 """
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 
 __all__ = (
+    "AnalysisTypeType",
     "AntipatternReportStatusType",
     "AppTypeType",
     "AppUnitErrorCategoryType",
     "ApplicationComponentCriteriaType",
     "ApplicationModeType",
     "AssessmentStatusType",
     "AuthTypeType",
     "AwsManagedTargetDestinationType",
+    "BinaryAnalyzerNameType",
     "CollectorHealthType",
     "ConditionType",
     "DataSourceTypeType",
     "DatabaseManagementPreferenceType",
     "GetServerDetailsPaginatorName",
     "GroupNameType",
     "HeterogeneousTargetDatabaseEngineType",
@@ -44,22 +46,24 @@
     "ListServersPaginatorName",
     "NoPreferenceTargetDestinationType",
     "OSTypeType",
     "OutputFormatType",
     "PipelineTypeType",
     "RecommendationReportStatusType",
     "ResourceSubTypeType",
+    "RunTimeAnalyzerNameType",
     "RunTimeAssessmentStatusType",
     "RuntimeAnalysisStatusType",
     "SelfManageTargetDestinationType",
     "ServerCriteriaType",
     "ServerErrorCategoryType",
     "ServerOsTypeType",
     "SeverityType",
     "SortOrderType",
+    "SourceCodeAnalyzerNameType",
     "SrcCodeOrDbAnalysisStatusType",
     "StrategyRecommendationType",
     "StrategyType",
     "TargetDatabaseEngineType",
     "TargetDestinationType",
     "TransformationToolNameType",
     "VersionControlType",
@@ -68,14 +72,17 @@
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
 
+AnalysisTypeType = Literal[
+    "BINARY_ANALYSIS", "DATABASE_ANALYSIS", "RUNTIME_ANALYSIS", "SOURCE_CODE_ANALYSIS"
+]
 AntipatternReportStatusType = Literal["FAILED", "IN_PROGRESS", "SUCCESS"]
 AppTypeType = Literal[
     "Cassandra",
     "DB2",
     "DotNetFramework",
     "Dotnet",
     "DotnetCore",
@@ -110,20 +117,21 @@
     "SERVER_ID",
     "STRATEGY",
 ]
 ApplicationModeType = Literal["ALL", "KNOWN", "UNKNOWN"]
 AssessmentStatusType = Literal["COMPLETE", "FAILED", "IN_PROGRESS", "STOPPED"]
 AuthTypeType = Literal["CERT", "NTLM", "SSH"]
 AwsManagedTargetDestinationType = Literal["AWS Elastic BeanStalk", "AWS Fargate", "None specified"]
+BinaryAnalyzerNameType = Literal["BYTECODE_ANALYZER", "DLL_ANALYZER"]
 CollectorHealthType = Literal["COLLECTOR_HEALTHY", "COLLECTOR_UNHEALTHY"]
 ConditionType = Literal["CONTAINS", "EQUALS", "NOT_CONTAINS", "NOT_EQUALS"]
-DataSourceTypeType = Literal["ApplicationDiscoveryService", "MPA"]
+DataSourceTypeType = Literal["ApplicationDiscoveryService", "Import", "MPA"]
 DatabaseManagementPreferenceType = Literal["AWS-managed", "No preference", "Self-manage"]
 GetServerDetailsPaginatorName = Literal["get_server_details"]
-GroupNameType = Literal["ExternalId"]
+GroupNameType = Literal["ExternalId", "ExternalSourceType"]
 HeterogeneousTargetDatabaseEngineType = Literal[
     "AWS PostgreSQL",
     "Amazon Aurora",
     "Db2 LUW",
     "MariaDB",
     "Microsoft SQL Server",
     "MongoDB",
@@ -157,14 +165,17 @@
     "None specified",
 ]
 OSTypeType = Literal["LINUX", "WINDOWS"]
 OutputFormatType = Literal["Excel", "Json"]
 PipelineTypeType = Literal["AZURE_DEVOPS"]
 RecommendationReportStatusType = Literal["FAILED", "IN_PROGRESS", "SUCCESS"]
 ResourceSubTypeType = Literal["Database", "DatabaseProcess", "Process"]
+RunTimeAnalyzerNameType = Literal[
+    "A2C_ANALYZER", "DATABASE_ANALYZER", "EMP_PA_ANALYZER", "REHOST_ANALYZER", "SCT_ANALYZER"
+]
 RunTimeAssessmentStatusType = Literal[
     "dataCollectionTaskFailed",
     "dataCollectionTaskPartialSuccess",
     "dataCollectionTaskScheduled",
     "dataCollectionTaskStarted",
     "dataCollectionTaskStopped",
     "dataCollectionTaskSuccess",
@@ -196,14 +207,17 @@
     "PERMISSION_ERROR",
 ]
 ServerOsTypeType = Literal[
     "AmazonLinux", "EndOfSupportWindowsServer", "Other", "Redhat", "WindowsServer"
 ]
 SeverityType = Literal["HIGH", "LOW", "MEDIUM"]
 SortOrderType = Literal["ASC", "DESC"]
+SourceCodeAnalyzerNameType = Literal[
+    "BYTECODE_ANALYZER", "CSHARP_ANALYZER", "JAVA_ANALYZER", "PORTING_ASSISTANT"
+]
 SrcCodeOrDbAnalysisStatusType = Literal[
     "ANALYSIS_FAILED",
     "ANALYSIS_PARTIAL_SUCCESS",
     "ANALYSIS_STARTED",
     "ANALYSIS_SUCCESS",
     "ANALYSIS_TO_BE_SCHEDULED",
     "CONFIGURED",
@@ -314,14 +328,15 @@
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
@@ -400,14 +415,15 @@
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
@@ -418,14 +434,15 @@
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
@@ -461,14 +478,15 @@
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
@@ -487,16 +505,19 @@
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
@@ -580,15 +601,17 @@
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

### Comparing `types-aiobotocore-migrationhubstrategy-2.5.0.post1/types_aiobotocore_migrationhubstrategy/literals.pyi` & `types-aiobotocore-migrationhubstrategy-2.5.1/types_aiobotocore_migrationhubstrategy/literals.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -2,35 +2,37 @@
 Type annotations for migrationhubstrategy service literal definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhubstrategy/literals/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_migrationhubstrategy.literals import AntipatternReportStatusType
+    from types_aiobotocore_migrationhubstrategy.literals import AnalysisTypeType
 
-    data: AntipatternReportStatusType = "FAILED"
+    data: AnalysisTypeType = "BINARY_ANALYSIS"
     ```
 """
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 __all__ = (
+    "AnalysisTypeType",
     "AntipatternReportStatusType",
     "AppTypeType",
     "AppUnitErrorCategoryType",
     "ApplicationComponentCriteriaType",
     "ApplicationModeType",
     "AssessmentStatusType",
     "AuthTypeType",
     "AwsManagedTargetDestinationType",
+    "BinaryAnalyzerNameType",
     "CollectorHealthType",
     "ConditionType",
     "DataSourceTypeType",
     "DatabaseManagementPreferenceType",
     "GetServerDetailsPaginatorName",
     "GroupNameType",
     "HeterogeneousTargetDatabaseEngineType",
@@ -43,22 +45,24 @@
     "ListServersPaginatorName",
     "NoPreferenceTargetDestinationType",
     "OSTypeType",
     "OutputFormatType",
     "PipelineTypeType",
     "RecommendationReportStatusType",
     "ResourceSubTypeType",
+    "RunTimeAnalyzerNameType",
     "RunTimeAssessmentStatusType",
     "RuntimeAnalysisStatusType",
     "SelfManageTargetDestinationType",
     "ServerCriteriaType",
     "ServerErrorCategoryType",
     "ServerOsTypeType",
     "SeverityType",
     "SortOrderType",
+    "SourceCodeAnalyzerNameType",
     "SrcCodeOrDbAnalysisStatusType",
     "StrategyRecommendationType",
     "StrategyType",
     "TargetDatabaseEngineType",
     "TargetDestinationType",
     "TransformationToolNameType",
     "VersionControlType",
@@ -66,14 +70,17 @@
     "MigrationHubStrategyRecommendationsServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
+AnalysisTypeType = Literal[
+    "BINARY_ANALYSIS", "DATABASE_ANALYSIS", "RUNTIME_ANALYSIS", "SOURCE_CODE_ANALYSIS"
+]
 AntipatternReportStatusType = Literal["FAILED", "IN_PROGRESS", "SUCCESS"]
 AppTypeType = Literal[
     "Cassandra",
     "DB2",
     "DotNetFramework",
     "Dotnet",
     "DotnetCore",
@@ -108,20 +115,21 @@
     "SERVER_ID",
     "STRATEGY",
 ]
 ApplicationModeType = Literal["ALL", "KNOWN", "UNKNOWN"]
 AssessmentStatusType = Literal["COMPLETE", "FAILED", "IN_PROGRESS", "STOPPED"]
 AuthTypeType = Literal["CERT", "NTLM", "SSH"]
 AwsManagedTargetDestinationType = Literal["AWS Elastic BeanStalk", "AWS Fargate", "None specified"]
+BinaryAnalyzerNameType = Literal["BYTECODE_ANALYZER", "DLL_ANALYZER"]
 CollectorHealthType = Literal["COLLECTOR_HEALTHY", "COLLECTOR_UNHEALTHY"]
 ConditionType = Literal["CONTAINS", "EQUALS", "NOT_CONTAINS", "NOT_EQUALS"]
-DataSourceTypeType = Literal["ApplicationDiscoveryService", "MPA"]
+DataSourceTypeType = Literal["ApplicationDiscoveryService", "Import", "MPA"]
 DatabaseManagementPreferenceType = Literal["AWS-managed", "No preference", "Self-manage"]
 GetServerDetailsPaginatorName = Literal["get_server_details"]
-GroupNameType = Literal["ExternalId"]
+GroupNameType = Literal["ExternalId", "ExternalSourceType"]
 HeterogeneousTargetDatabaseEngineType = Literal[
     "AWS PostgreSQL",
     "Amazon Aurora",
     "Db2 LUW",
     "MariaDB",
     "Microsoft SQL Server",
     "MongoDB",
@@ -155,14 +163,17 @@
     "None specified",
 ]
 OSTypeType = Literal["LINUX", "WINDOWS"]
 OutputFormatType = Literal["Excel", "Json"]
 PipelineTypeType = Literal["AZURE_DEVOPS"]
 RecommendationReportStatusType = Literal["FAILED", "IN_PROGRESS", "SUCCESS"]
 ResourceSubTypeType = Literal["Database", "DatabaseProcess", "Process"]
+RunTimeAnalyzerNameType = Literal[
+    "A2C_ANALYZER", "DATABASE_ANALYZER", "EMP_PA_ANALYZER", "REHOST_ANALYZER", "SCT_ANALYZER"
+]
 RunTimeAssessmentStatusType = Literal[
     "dataCollectionTaskFailed",
     "dataCollectionTaskPartialSuccess",
     "dataCollectionTaskScheduled",
     "dataCollectionTaskStarted",
     "dataCollectionTaskStopped",
     "dataCollectionTaskSuccess",
@@ -194,14 +205,17 @@
     "PERMISSION_ERROR",
 ]
 ServerOsTypeType = Literal[
     "AmazonLinux", "EndOfSupportWindowsServer", "Other", "Redhat", "WindowsServer"
 ]
 SeverityType = Literal["HIGH", "LOW", "MEDIUM"]
 SortOrderType = Literal["ASC", "DESC"]
+SourceCodeAnalyzerNameType = Literal[
+    "BYTECODE_ANALYZER", "CSHARP_ANALYZER", "JAVA_ANALYZER", "PORTING_ASSISTANT"
+]
 SrcCodeOrDbAnalysisStatusType = Literal[
     "ANALYSIS_FAILED",
     "ANALYSIS_PARTIAL_SUCCESS",
     "ANALYSIS_STARTED",
     "ANALYSIS_SUCCESS",
     "ANALYSIS_TO_BE_SCHEDULED",
     "CONFIGURED",
@@ -312,14 +326,15 @@
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
@@ -398,14 +413,15 @@
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
@@ -416,14 +432,15 @@
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
@@ -459,14 +476,15 @@
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
@@ -485,16 +503,19 @@
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
@@ -578,15 +599,17 @@
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

### Comparing `types-aiobotocore-migrationhubstrategy-2.5.0.post1/types_aiobotocore_migrationhubstrategy/paginator.py` & `types-aiobotocore-migrationhubstrategy-2.5.1/types_aiobotocore_migrationhubstrategy/paginator.py`

 * *Files 3% similar despite different names*

```diff
@@ -24,16 +24,15 @@
         get_server_details_paginator: GetServerDetailsPaginator = client.get_paginator("get_server_details")
         list_application_components_paginator: ListApplicationComponentsPaginator = client.get_paginator("list_application_components")
         list_collectors_paginator: ListCollectorsPaginator = client.get_paginator("list_collectors")
         list_import_file_task_paginator: ListImportFileTaskPaginator = client.get_paginator("list_import_file_task")
         list_servers_paginator: ListServersPaginator = client.get_paginator("list_servers")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ApplicationComponentCriteriaType, ServerCriteriaType, SortOrderType
 from .type_defs import (
     GetServerDetailsResponseTypeDef,
@@ -41,20 +40,14 @@
     ListApplicationComponentsResponseTypeDef,
     ListCollectorsResponseTypeDef,
     ListImportFileTaskResponseTypeDef,
     ListServersResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "GetServerDetailsPaginator",
     "ListApplicationComponentsPaginator",
     "ListCollectorsPaginator",
     "ListImportFileTaskPaginator",
     "ListServersPaginator",
 )
@@ -73,15 +66,15 @@
 class GetServerDetailsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhubstrategy.html#MigrationHubStrategyRecommendations.Paginator.GetServerDetails)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhubstrategy/paginators/#getserverdetailspaginator)
     """
 
     def paginate(
-        self, *, serverId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, serverId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetServerDetailsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhubstrategy.html#MigrationHubStrategyRecommendations.Paginator.GetServerDetails.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhubstrategy/paginators/#getserverdetailspaginator)
         """
 
 
@@ -94,45 +87,45 @@
     def paginate(
         self,
         *,
         applicationComponentCriteria: ApplicationComponentCriteriaType = ...,
         filterValue: str = ...,
         groupIdFilter: Sequence[GroupTypeDef] = ...,
         sort: SortOrderType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListApplicationComponentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhubstrategy.html#MigrationHubStrategyRecommendations.Paginator.ListApplicationComponents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhubstrategy/paginators/#listapplicationcomponentspaginator)
         """
 
 
 class ListCollectorsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhubstrategy.html#MigrationHubStrategyRecommendations.Paginator.ListCollectors)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhubstrategy/paginators/#listcollectorspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCollectorsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhubstrategy.html#MigrationHubStrategyRecommendations.Paginator.ListCollectors.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhubstrategy/paginators/#listcollectorspaginator)
         """
 
 
 class ListImportFileTaskPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhubstrategy.html#MigrationHubStrategyRecommendations.Paginator.ListImportFileTask)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhubstrategy/paginators/#listimportfiletaskpaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListImportFileTaskResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhubstrategy.html#MigrationHubStrategyRecommendations.Paginator.ListImportFileTask.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhubstrategy/paginators/#listimportfiletaskpaginator)
         """
 
 
@@ -145,13 +138,13 @@
     def paginate(
         self,
         *,
         filterValue: str = ...,
         groupIdFilter: Sequence[GroupTypeDef] = ...,
         serverCriteria: ServerCriteriaType = ...,
         sort: SortOrderType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListServersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhubstrategy.html#MigrationHubStrategyRecommendations.Paginator.ListServers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhubstrategy/paginators/#listserverspaginator)
         """
```

### Comparing `types-aiobotocore-migrationhubstrategy-2.5.0.post1/types_aiobotocore_migrationhubstrategy/paginator.pyi` & `types-aiobotocore-migrationhubstrategy-2.5.1/types_aiobotocore_migrationhubstrategy/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -24,16 +24,15 @@
         get_server_details_paginator: GetServerDetailsPaginator = client.get_paginator("get_server_details")
         list_application_components_paginator: ListApplicationComponentsPaginator = client.get_paginator("list_application_components")
         list_collectors_paginator: ListCollectorsPaginator = client.get_paginator("list_collectors")
         list_import_file_task_paginator: ListImportFileTaskPaginator = client.get_paginator("list_import_file_task")
         list_servers_paginator: ListServersPaginator = client.get_paginator("list_servers")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ApplicationComponentCriteriaType, ServerCriteriaType, SortOrderType
 from .type_defs import (
     GetServerDetailsResponseTypeDef,
@@ -41,19 +40,14 @@
     ListApplicationComponentsResponseTypeDef,
     ListCollectorsResponseTypeDef,
     ListImportFileTaskResponseTypeDef,
     ListServersResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "GetServerDetailsPaginator",
     "ListApplicationComponentsPaginator",
     "ListCollectorsPaginator",
     "ListImportFileTaskPaginator",
     "ListServersPaginator",
 )
@@ -69,15 +63,15 @@
 class GetServerDetailsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhubstrategy.html#MigrationHubStrategyRecommendations.Paginator.GetServerDetails)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhubstrategy/paginators/#getserverdetailspaginator)
     """
 
     def paginate(
-        self, *, serverId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, serverId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetServerDetailsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhubstrategy.html#MigrationHubStrategyRecommendations.Paginator.GetServerDetails.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhubstrategy/paginators/#getserverdetailspaginator)
         """
 
 class ListApplicationComponentsPaginator(AioPaginator):
@@ -89,43 +83,43 @@
     def paginate(
         self,
         *,
         applicationComponentCriteria: ApplicationComponentCriteriaType = ...,
         filterValue: str = ...,
         groupIdFilter: Sequence[GroupTypeDef] = ...,
         sort: SortOrderType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListApplicationComponentsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhubstrategy.html#MigrationHubStrategyRecommendations.Paginator.ListApplicationComponents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhubstrategy/paginators/#listapplicationcomponentspaginator)
         """
 
 class ListCollectorsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhubstrategy.html#MigrationHubStrategyRecommendations.Paginator.ListCollectors)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhubstrategy/paginators/#listcollectorspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCollectorsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhubstrategy.html#MigrationHubStrategyRecommendations.Paginator.ListCollectors.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhubstrategy/paginators/#listcollectorspaginator)
         """
 
 class ListImportFileTaskPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhubstrategy.html#MigrationHubStrategyRecommendations.Paginator.ListImportFileTask)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhubstrategy/paginators/#listimportfiletaskpaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListImportFileTaskResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhubstrategy.html#MigrationHubStrategyRecommendations.Paginator.ListImportFileTask.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhubstrategy/paginators/#listimportfiletaskpaginator)
         """
 
 class ListServersPaginator(AioPaginator):
@@ -137,13 +131,13 @@
     def paginate(
         self,
         *,
         filterValue: str = ...,
         groupIdFilter: Sequence[GroupTypeDef] = ...,
         serverCriteria: ServerCriteriaType = ...,
         sort: SortOrderType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListServersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhubstrategy.html#MigrationHubStrategyRecommendations.Paginator.ListServers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhubstrategy/paginators/#listserverspaginator)
         """
```

### Comparing `types-aiobotocore-migrationhubstrategy-2.5.0.post1/types_aiobotocore_migrationhubstrategy/type_defs.py` & `types-aiobotocore-migrationhubstrategy-2.5.1/types_aiobotocore_migrationhubstrategy/type_defs.py`

 * *Files 5% similar despite different names*

```diff
@@ -2,52 +2,57 @@
 Type annotations for migrationhubstrategy service type definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhubstrategy/type_defs/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_migrationhubstrategy.type_defs import AntipatternSeveritySummaryTypeDef
+    from types_aiobotocore_migrationhubstrategy.type_defs import AnalysisStatusUnionTypeDef
 
-    data: AntipatternSeveritySummaryTypeDef = {...}
+    data: AnalysisStatusUnionTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
 from typing import Dict, List, Sequence
 
 from .literals import (
+    AnalysisTypeType,
     AntipatternReportStatusType,
     ApplicationComponentCriteriaType,
     ApplicationModeType,
     AppTypeType,
     AppUnitErrorCategoryType,
     AssessmentStatusType,
     AuthTypeType,
     AwsManagedTargetDestinationType,
+    BinaryAnalyzerNameType,
     CollectorHealthType,
     ConditionType,
     DatabaseManagementPreferenceType,
     DataSourceTypeType,
+    GroupNameType,
     HeterogeneousTargetDatabaseEngineType,
     ImportFileTaskStatusType,
     InclusionStatusType,
     NoPreferenceTargetDestinationType,
     OSTypeType,
     OutputFormatType,
     RecommendationReportStatusType,
     ResourceSubTypeType,
     RuntimeAnalysisStatusType,
+    RunTimeAnalyzerNameType,
     RunTimeAssessmentStatusType,
     SelfManageTargetDestinationType,
     ServerCriteriaType,
     ServerErrorCategoryType,
     ServerOsTypeType,
     SeverityType,
     SortOrderType,
+    SourceCodeAnalyzerNameType,
     SrcCodeOrDbAnalysisStatusType,
     StrategyRecommendationType,
     StrategyType,
     TargetDatabaseEngineType,
     TargetDestinationType,
     TransformationToolNameType,
     VersionControlType,
@@ -61,18 +66,20 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
+    "AnalysisStatusUnionTypeDef",
+    "AnalyzerNameUnionTypeDef",
+    "S3ObjectTypeDef",
     "AntipatternSeveritySummaryTypeDef",
     "AppUnitErrorTypeDef",
     "DatabaseConfigDetailTypeDef",
-    "S3ObjectTypeDef",
     "SourceCodeRepositoryTypeDef",
     "ApplicationComponentStatusSummaryTypeDef",
     "ApplicationComponentSummaryTypeDef",
     "ServerStatusSummaryTypeDef",
     "ServerSummaryTypeDef",
     "StrategySummaryTypeDef",
     "AssessmentTargetTypeDef",
@@ -85,80 +92,110 @@
     "VcenterBasedRemoteInfoTypeDef",
     "VersionControlInfoTypeDef",
     "DataCollectionDetailsTypeDef",
     "HeterogeneousTypeDef",
     "HomogeneousTypeDef",
     "NoDatabaseMigrationPreferenceTypeDef",
     "GetApplicationComponentDetailsRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "GetApplicationComponentStrategiesRequestRequestTypeDef",
     "GetAssessmentRequestRequestTypeDef",
     "GetImportFileTaskRequestRequestTypeDef",
+    "GetImportFileTaskResponseTypeDef",
+    "GetLatestAssessmentIdResponseTypeDef",
     "GetRecommendationReportDetailsRequestRequestTypeDef",
     "RecommendationReportDetailsTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetServerDetailsRequestGetServerDetailsPaginateTypeDef",
     "GetServerDetailsRequestRequestTypeDef",
     "GetServerStrategiesRequestRequestTypeDef",
     "GroupTypeDef",
     "ImportFileTaskInformationTypeDef",
+    "ListCollectorsRequestListCollectorsPaginateTypeDef",
     "ListCollectorsRequestRequestTypeDef",
+    "ListImportFileTaskRequestListImportFileTaskPaginateTypeDef",
     "ListImportFileTaskRequestRequestTypeDef",
     "NoManagementPreferenceTypeDef",
     "SelfManageResourcesTypeDef",
     "NetworkInfoTypeDef",
     "OSInfoTypeDef",
+    "PaginatorConfigTypeDef",
     "TransformationToolTypeDef",
+    "ResponseMetadataTypeDef",
     "ServerErrorTypeDef",
     "SourceCodeTypeDef",
+    "StartAssessmentResponseTypeDef",
+    "StartImportFileTaskResponseTypeDef",
+    "StartRecommendationReportGenerationResponseTypeDef",
     "StopAssessmentRequestRequestTypeDef",
     "StrategyOptionTypeDef",
+    "AntipatternReportResultTypeDef",
     "AssessmentSummaryTypeDef",
     "StartAssessmentRequestRequestTypeDef",
     "PrioritizeBusinessGoalsTypeDef",
     "ConfigurationSummaryTypeDef",
-    "DatabaseMigrationPreferenceTypeDef",
     "GetAssessmentResponseTypeDef",
-    "GetImportFileTaskResponseTypeDef",
-    "GetLatestAssessmentIdResponseTypeDef",
-    "StartAssessmentResponseTypeDef",
-    "StartImportFileTaskResponseTypeDef",
-    "StartRecommendationReportGenerationResponseTypeDef",
+    "DatabaseMigrationPreferenceTypeDef",
     "GetRecommendationReportDetailsResponseTypeDef",
-    "GetServerDetailsRequestGetServerDetailsPaginateTypeDef",
-    "ListCollectorsRequestListCollectorsPaginateTypeDef",
-    "ListImportFileTaskRequestListImportFileTaskPaginateTypeDef",
     "ListApplicationComponentsRequestListApplicationComponentsPaginateTypeDef",
     "ListApplicationComponentsRequestRequestTypeDef",
     "ListServersRequestListServersPaginateTypeDef",
     "ListServersRequestRequestTypeDef",
     "StartImportFileTaskRequestRequestTypeDef",
     "StartRecommendationReportGenerationRequestRequestTypeDef",
     "ListImportFileTaskResponseTypeDef",
     "ManagementPreferenceTypeDef",
     "SystemInfoTypeDef",
     "RecommendationSetTypeDef",
     "UpdateApplicationComponentConfigRequestRequestTypeDef",
     "UpdateServerConfigRequestRequestTypeDef",
+    "ResultTypeDef",
     "GetPortfolioSummaryResponseTypeDef",
     "CollectorTypeDef",
     "DatabasePreferencesTypeDef",
     "ApplicationPreferencesTypeDef",
-    "ApplicationComponentDetailTypeDef",
     "ApplicationComponentStrategyTypeDef",
     "ServerDetailTypeDef",
     "ServerStrategyTypeDef",
+    "ApplicationComponentDetailTypeDef",
     "ListCollectorsResponseTypeDef",
     "GetPortfolioPreferencesResponseTypeDef",
     "PutPortfolioPreferencesRequestRequestTypeDef",
-    "GetApplicationComponentDetailsResponseTypeDef",
-    "ListApplicationComponentsResponseTypeDef",
     "GetApplicationComponentStrategiesResponseTypeDef",
     "GetServerDetailsResponseTypeDef",
     "ListServersResponseTypeDef",
     "GetServerStrategiesResponseTypeDef",
+    "GetApplicationComponentDetailsResponseTypeDef",
+    "ListApplicationComponentsResponseTypeDef",
+)
+
+AnalysisStatusUnionTypeDef = TypedDict(
+    "AnalysisStatusUnionTypeDef",
+    {
+        "runtimeAnalysisStatus": RuntimeAnalysisStatusType,
+        "srcCodeOrDbAnalysisStatus": SrcCodeOrDbAnalysisStatusType,
+    },
+    total=False,
+)
+
+AnalyzerNameUnionTypeDef = TypedDict(
+    "AnalyzerNameUnionTypeDef",
+    {
+        "binaryAnalyzerName": BinaryAnalyzerNameType,
+        "runTimeAnalyzerName": RunTimeAnalyzerNameType,
+        "sourceCodeAnalyzerName": SourceCodeAnalyzerNameType,
+    },
+    total=False,
+)
+
+S3ObjectTypeDef = TypedDict(
+    "S3ObjectTypeDef",
+    {
+        "s3Bucket": str,
+        "s3key": str,
+    },
+    total=False,
 )
 
 AntipatternSeveritySummaryTypeDef = TypedDict(
     "AntipatternSeveritySummaryTypeDef",
     {
         "count": int,
         "severity": SeverityType,
@@ -178,23 +215,14 @@
     "DatabaseConfigDetailTypeDef",
     {
         "secretName": str,
     },
     total=False,
 )
 
-S3ObjectTypeDef = TypedDict(
-    "S3ObjectTypeDef",
-    {
-        "s3Bucket": str,
-        "s3key": str,
-    },
-    total=False,
-)
-
 SourceCodeRepositoryTypeDef = TypedDict(
     "SourceCodeRepositoryTypeDef",
     {
         "branch": str,
         "projectName": str,
         "repository": str,
         "versionControlType": str,
@@ -368,25 +396,14 @@
 GetApplicationComponentDetailsRequestRequestTypeDef = TypedDict(
     "GetApplicationComponentDetailsRequestRequestTypeDef",
     {
         "applicationComponentId": str,
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
 GetApplicationComponentStrategiesRequestRequestTypeDef = TypedDict(
     "GetApplicationComponentStrategiesRequestRequestTypeDef",
     {
         "applicationComponentId": str,
     },
 )
 
@@ -400,14 +417,40 @@
 GetImportFileTaskRequestRequestTypeDef = TypedDict(
     "GetImportFileTaskRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
+GetImportFileTaskResponseTypeDef = TypedDict(
+    "GetImportFileTaskResponseTypeDef",
+    {
+        "completionTime": datetime,
+        "id": str,
+        "importName": str,
+        "inputS3Bucket": str,
+        "inputS3Key": str,
+        "numberOfRecordsFailed": int,
+        "numberOfRecordsSuccess": int,
+        "startTime": datetime,
+        "status": ImportFileTaskStatusType,
+        "statusReportS3Bucket": str,
+        "statusReportS3Key": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetLatestAssessmentIdResponseTypeDef = TypedDict(
+    "GetLatestAssessmentIdResponseTypeDef",
+    {
+        "id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetRecommendationReportDetailsRequestRequestTypeDef = TypedDict(
     "GetRecommendationReportDetailsRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
@@ -420,24 +463,36 @@
         "startTime": datetime,
         "status": RecommendationReportStatusType,
         "statusMessage": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredGetServerDetailsRequestGetServerDetailsPaginateTypeDef = TypedDict(
+    "_RequiredGetServerDetailsRequestGetServerDetailsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "serverId": str,
+    },
+)
+_OptionalGetServerDetailsRequestGetServerDetailsPaginateTypeDef = TypedDict(
+    "_OptionalGetServerDetailsRequestGetServerDetailsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class GetServerDetailsRequestGetServerDetailsPaginateTypeDef(
+    _RequiredGetServerDetailsRequestGetServerDetailsPaginateTypeDef,
+    _OptionalGetServerDetailsRequestGetServerDetailsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetServerDetailsRequestRequestTypeDef = TypedDict(
     "_RequiredGetServerDetailsRequestRequestTypeDef",
     {
         "serverId": str,
     },
 )
 _OptionalGetServerDetailsRequestRequestTypeDef = TypedDict(
@@ -462,15 +517,15 @@
         "serverId": str,
     },
 )
 
 GroupTypeDef = TypedDict(
     "GroupTypeDef",
     {
-        "name": Literal["ExternalId"],
+        "name": GroupNameType,
         "value": str,
     },
     total=False,
 )
 
 ImportFileTaskInformationTypeDef = TypedDict(
     "ImportFileTaskInformationTypeDef",
@@ -486,23 +541,39 @@
         "status": ImportFileTaskStatusType,
         "statusReportS3Bucket": str,
         "statusReportS3Key": str,
     },
     total=False,
 )
 
+ListCollectorsRequestListCollectorsPaginateTypeDef = TypedDict(
+    "ListCollectorsRequestListCollectorsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCollectorsRequestRequestTypeDef = TypedDict(
     "ListCollectorsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+ListImportFileTaskRequestListImportFileTaskPaginateTypeDef = TypedDict(
+    "ListImportFileTaskRequestListImportFileTaskPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListImportFileTaskRequestRequestTypeDef = TypedDict(
     "ListImportFileTaskRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -537,24 +608,45 @@
     {
         "type": OSTypeType,
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
 TransformationToolTypeDef = TypedDict(
     "TransformationToolTypeDef",
     {
         "description": str,
         "name": TransformationToolNameType,
         "tranformationToolInstallationLink": str,
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
 ServerErrorTypeDef = TypedDict(
     "ServerErrorTypeDef",
     {
         "serverErrorCategory": ServerErrorCategoryType,
     },
     total=False,
 )
@@ -566,14 +658,38 @@
         "projectName": str,
         "sourceVersion": str,
         "versionControl": VersionControlType,
     },
     total=False,
 )
 
+StartAssessmentResponseTypeDef = TypedDict(
+    "StartAssessmentResponseTypeDef",
+    {
+        "assessmentId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartImportFileTaskResponseTypeDef = TypedDict(
+    "StartImportFileTaskResponseTypeDef",
+    {
+        "id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartRecommendationReportGenerationResponseTypeDef = TypedDict(
+    "StartRecommendationReportGenerationResponseTypeDef",
+    {
+        "id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopAssessmentRequestRequestTypeDef = TypedDict(
     "StopAssessmentRequestRequestTypeDef",
     {
         "assessmentId": str,
     },
 )
 
@@ -584,14 +700,25 @@
         "strategy": StrategyType,
         "targetDestination": TargetDestinationType,
         "toolName": TransformationToolNameType,
     },
     total=False,
 )
 
+AntipatternReportResultTypeDef = TypedDict(
+    "AntipatternReportResultTypeDef",
+    {
+        "analyzerName": AnalyzerNameUnionTypeDef,
+        "antiPatternReportS3Object": S3ObjectTypeDef,
+        "antipatternReportStatus": AntipatternReportStatusType,
+        "antipatternReportStatusMessage": str,
+    },
+    total=False,
+)
+
 AssessmentSummaryTypeDef = TypedDict(
     "AssessmentSummaryTypeDef",
     {
         "antipatternReportS3Object": S3ObjectTypeDef,
         "antipatternReportStatus": AntipatternReportStatusType,
         "antipatternReportStatusMessage": str,
         "lastAnalyzedTimestamp": datetime,
@@ -632,139 +759,51 @@
         "remoteSourceCodeAnalysisServerInfo": RemoteSourceCodeAnalysisServerInfoTypeDef,
         "vcenterBasedRemoteInfoList": List[VcenterBasedRemoteInfoTypeDef],
         "versionControlInfoList": List[VersionControlInfoTypeDef],
     },
     total=False,
 )
 
-DatabaseMigrationPreferenceTypeDef = TypedDict(
-    "DatabaseMigrationPreferenceTypeDef",
-    {
-        "heterogeneous": HeterogeneousTypeDef,
-        "homogeneous": HomogeneousTypeDef,
-        "noPreference": NoDatabaseMigrationPreferenceTypeDef,
-    },
-    total=False,
-)
-
 GetAssessmentResponseTypeDef = TypedDict(
     "GetAssessmentResponseTypeDef",
     {
         "assessmentTargets": List[AssessmentTargetTypeDef],
         "dataCollectionDetails": DataCollectionDetailsTypeDef,
         "id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetImportFileTaskResponseTypeDef = TypedDict(
-    "GetImportFileTaskResponseTypeDef",
-    {
-        "completionTime": datetime,
-        "id": str,
-        "importName": str,
-        "inputS3Bucket": str,
-        "inputS3Key": str,
-        "numberOfRecordsFailed": int,
-        "numberOfRecordsSuccess": int,
-        "startTime": datetime,
-        "status": ImportFileTaskStatusType,
-        "statusReportS3Bucket": str,
-        "statusReportS3Key": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetLatestAssessmentIdResponseTypeDef = TypedDict(
-    "GetLatestAssessmentIdResponseTypeDef",
-    {
-        "id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartAssessmentResponseTypeDef = TypedDict(
-    "StartAssessmentResponseTypeDef",
-    {
-        "assessmentId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartImportFileTaskResponseTypeDef = TypedDict(
-    "StartImportFileTaskResponseTypeDef",
-    {
-        "id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartRecommendationReportGenerationResponseTypeDef = TypedDict(
-    "StartRecommendationReportGenerationResponseTypeDef",
+DatabaseMigrationPreferenceTypeDef = TypedDict(
+    "DatabaseMigrationPreferenceTypeDef",
     {
-        "id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "heterogeneous": HeterogeneousTypeDef,
+        "homogeneous": HomogeneousTypeDef,
+        "noPreference": NoDatabaseMigrationPreferenceTypeDef,
     },
+    total=False,
 )
 
 GetRecommendationReportDetailsResponseTypeDef = TypedDict(
     "GetRecommendationReportDetailsResponseTypeDef",
     {
         "id": str,
         "recommendationReportDetails": RecommendationReportDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredGetServerDetailsRequestGetServerDetailsPaginateTypeDef = TypedDict(
-    "_RequiredGetServerDetailsRequestGetServerDetailsPaginateTypeDef",
-    {
-        "serverId": str,
-    },
-)
-_OptionalGetServerDetailsRequestGetServerDetailsPaginateTypeDef = TypedDict(
-    "_OptionalGetServerDetailsRequestGetServerDetailsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetServerDetailsRequestGetServerDetailsPaginateTypeDef(
-    _RequiredGetServerDetailsRequestGetServerDetailsPaginateTypeDef,
-    _OptionalGetServerDetailsRequestGetServerDetailsPaginateTypeDef,
-):
-    pass
-
-
-ListCollectorsRequestListCollectorsPaginateTypeDef = TypedDict(
-    "ListCollectorsRequestListCollectorsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
-)
-
-ListImportFileTaskRequestListImportFileTaskPaginateTypeDef = TypedDict(
-    "ListImportFileTaskRequestListImportFileTaskPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
 )
 
 ListApplicationComponentsRequestListApplicationComponentsPaginateTypeDef = TypedDict(
     "ListApplicationComponentsRequestListApplicationComponentsPaginateTypeDef",
     {
         "applicationComponentCriteria": ApplicationComponentCriteriaType,
         "filterValue": str,
         "groupIdFilter": Sequence[GroupTypeDef],
         "sort": SortOrderType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListApplicationComponentsRequestRequestTypeDef = TypedDict(
     "ListApplicationComponentsRequestRequestTypeDef",
     {
@@ -781,15 +820,15 @@
 ListServersRequestListServersPaginateTypeDef = TypedDict(
     "ListServersRequestListServersPaginateTypeDef",
     {
         "filterValue": str,
         "groupIdFilter": Sequence[GroupTypeDef],
         "serverCriteria": ServerCriteriaType,
         "sort": SortOrderType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListServersRequestRequestTypeDef = TypedDict(
     "ListServersRequestRequestTypeDef",
     {
@@ -839,15 +878,15 @@
 )
 
 ListImportFileTaskResponseTypeDef = TypedDict(
     "ListImportFileTaskResponseTypeDef",
     {
         "nextToken": str,
         "taskInfos": List[ImportFileTaskInformationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ManagementPreferenceTypeDef = TypedDict(
     "ManagementPreferenceTypeDef",
     {
         "awsManagedResources": AwsManagedResourcesTypeDef,
@@ -923,19 +962,30 @@
 class UpdateServerConfigRequestRequestTypeDef(
     _RequiredUpdateServerConfigRequestRequestTypeDef,
     _OptionalUpdateServerConfigRequestRequestTypeDef,
 ):
     pass
 
 
+ResultTypeDef = TypedDict(
+    "ResultTypeDef",
+    {
+        "analysisStatus": AnalysisStatusUnionTypeDef,
+        "analysisType": AnalysisTypeType,
+        "antipatternReportResultList": List[AntipatternReportResultTypeDef],
+        "statusMessage": str,
+    },
+    total=False,
+)
+
 GetPortfolioSummaryResponseTypeDef = TypedDict(
     "GetPortfolioSummaryResponseTypeDef",
     {
         "assessmentSummary": AssessmentSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CollectorTypeDef = TypedDict(
     "CollectorTypeDef",
     {
         "collectorHealth": CollectorHealthType,
@@ -963,43 +1013,14 @@
     "ApplicationPreferencesTypeDef",
     {
         "managementPreference": ManagementPreferenceTypeDef,
     },
     total=False,
 )
 
-ApplicationComponentDetailTypeDef = TypedDict(
-    "ApplicationComponentDetailTypeDef",
-    {
-        "analysisStatus": SrcCodeOrDbAnalysisStatusType,
-        "antipatternReportS3Object": S3ObjectTypeDef,
-        "antipatternReportStatus": AntipatternReportStatusType,
-        "antipatternReportStatusMessage": str,
-        "appType": AppTypeType,
-        "appUnitError": AppUnitErrorTypeDef,
-        "associatedServerId": str,
-        "databaseConfigDetail": DatabaseConfigDetailTypeDef,
-        "id": str,
-        "inclusionStatus": InclusionStatusType,
-        "lastAnalyzedTimestamp": datetime,
-        "listAntipatternSeveritySummary": List[AntipatternSeveritySummaryTypeDef],
-        "moreServerAssociationExists": bool,
-        "name": str,
-        "osDriver": str,
-        "osVersion": str,
-        "recommendationSet": RecommendationSetTypeDef,
-        "resourceSubType": ResourceSubTypeType,
-        "runtimeStatus": RuntimeAnalysisStatusType,
-        "runtimeStatusMessage": str,
-        "sourceCodeRepositories": List[SourceCodeRepositoryTypeDef],
-        "statusMessage": str,
-    },
-    total=False,
-)
-
 ApplicationComponentStrategyTypeDef = TypedDict(
     "ApplicationComponentStrategyTypeDef",
     {
         "isPreferred": bool,
         "recommendation": RecommendationSetTypeDef,
         "status": StrategyRecommendationType,
     },
@@ -1034,92 +1055,122 @@
         "numberOfApplicationComponents": int,
         "recommendation": RecommendationSetTypeDef,
         "status": StrategyRecommendationType,
     },
     total=False,
 )
 
+ApplicationComponentDetailTypeDef = TypedDict(
+    "ApplicationComponentDetailTypeDef",
+    {
+        "analysisStatus": SrcCodeOrDbAnalysisStatusType,
+        "antipatternReportS3Object": S3ObjectTypeDef,
+        "antipatternReportStatus": AntipatternReportStatusType,
+        "antipatternReportStatusMessage": str,
+        "appType": AppTypeType,
+        "appUnitError": AppUnitErrorTypeDef,
+        "associatedServerId": str,
+        "databaseConfigDetail": DatabaseConfigDetailTypeDef,
+        "id": str,
+        "inclusionStatus": InclusionStatusType,
+        "lastAnalyzedTimestamp": datetime,
+        "listAntipatternSeveritySummary": List[AntipatternSeveritySummaryTypeDef],
+        "moreServerAssociationExists": bool,
+        "name": str,
+        "osDriver": str,
+        "osVersion": str,
+        "recommendationSet": RecommendationSetTypeDef,
+        "resourceSubType": ResourceSubTypeType,
+        "resultList": List[ResultTypeDef],
+        "runtimeStatus": RuntimeAnalysisStatusType,
+        "runtimeStatusMessage": str,
+        "sourceCodeRepositories": List[SourceCodeRepositoryTypeDef],
+        "statusMessage": str,
+    },
+    total=False,
+)
+
 ListCollectorsResponseTypeDef = TypedDict(
     "ListCollectorsResponseTypeDef",
     {
         "Collectors": List[CollectorTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetPortfolioPreferencesResponseTypeDef = TypedDict(
     "GetPortfolioPreferencesResponseTypeDef",
     {
         "applicationMode": ApplicationModeType,
         "applicationPreferences": ApplicationPreferencesTypeDef,
         "databasePreferences": DatabasePreferencesTypeDef,
         "prioritizeBusinessGoals": PrioritizeBusinessGoalsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutPortfolioPreferencesRequestRequestTypeDef = TypedDict(
     "PutPortfolioPreferencesRequestRequestTypeDef",
     {
         "applicationMode": ApplicationModeType,
         "applicationPreferences": ApplicationPreferencesTypeDef,
         "databasePreferences": DatabasePreferencesTypeDef,
         "prioritizeBusinessGoals": PrioritizeBusinessGoalsTypeDef,
     },
     total=False,
 )
 
-GetApplicationComponentDetailsResponseTypeDef = TypedDict(
-    "GetApplicationComponentDetailsResponseTypeDef",
-    {
-        "applicationComponentDetail": ApplicationComponentDetailTypeDef,
-        "associatedApplications": List[AssociatedApplicationTypeDef],
-        "associatedServerIds": List[str],
-        "moreApplicationResource": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListApplicationComponentsResponseTypeDef = TypedDict(
-    "ListApplicationComponentsResponseTypeDef",
-    {
-        "applicationComponentInfos": List[ApplicationComponentDetailTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 GetApplicationComponentStrategiesResponseTypeDef = TypedDict(
     "GetApplicationComponentStrategiesResponseTypeDef",
     {
         "applicationComponentStrategies": List[ApplicationComponentStrategyTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetServerDetailsResponseTypeDef = TypedDict(
     "GetServerDetailsResponseTypeDef",
     {
         "associatedApplications": List[AssociatedApplicationTypeDef],
         "nextToken": str,
         "serverDetail": ServerDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListServersResponseTypeDef = TypedDict(
     "ListServersResponseTypeDef",
     {
         "nextToken": str,
         "serverInfos": List[ServerDetailTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetServerStrategiesResponseTypeDef = TypedDict(
     "GetServerStrategiesResponseTypeDef",
     {
         "serverStrategies": List[ServerStrategyTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetApplicationComponentDetailsResponseTypeDef = TypedDict(
+    "GetApplicationComponentDetailsResponseTypeDef",
+    {
+        "applicationComponentDetail": ApplicationComponentDetailTypeDef,
+        "associatedApplications": List[AssociatedApplicationTypeDef],
+        "associatedServerIds": List[str],
+        "moreApplicationResource": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListApplicationComponentsResponseTypeDef = TypedDict(
+    "ListApplicationComponentsResponseTypeDef",
+    {
+        "applicationComponentInfos": List[ApplicationComponentDetailTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-migrationhubstrategy-2.5.0.post1/types_aiobotocore_migrationhubstrategy/type_defs.pyi` & `types-aiobotocore-migrationhubstrategy-2.5.1/types_aiobotocore_migrationhubstrategy/type_defs.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -2,52 +2,57 @@
 Type annotations for migrationhubstrategy service type definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhubstrategy/type_defs/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_migrationhubstrategy.type_defs import AntipatternSeveritySummaryTypeDef
+    from types_aiobotocore_migrationhubstrategy.type_defs import AnalysisStatusUnionTypeDef
 
-    data: AntipatternSeveritySummaryTypeDef = {...}
+    data: AnalysisStatusUnionTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
 from typing import Dict, List, Sequence
 
 from .literals import (
+    AnalysisTypeType,
     AntipatternReportStatusType,
     ApplicationComponentCriteriaType,
     ApplicationModeType,
     AppTypeType,
     AppUnitErrorCategoryType,
     AssessmentStatusType,
     AuthTypeType,
     AwsManagedTargetDestinationType,
+    BinaryAnalyzerNameType,
     CollectorHealthType,
     ConditionType,
     DatabaseManagementPreferenceType,
     DataSourceTypeType,
+    GroupNameType,
     HeterogeneousTargetDatabaseEngineType,
     ImportFileTaskStatusType,
     InclusionStatusType,
     NoPreferenceTargetDestinationType,
     OSTypeType,
     OutputFormatType,
     RecommendationReportStatusType,
     ResourceSubTypeType,
     RuntimeAnalysisStatusType,
+    RunTimeAnalyzerNameType,
     RunTimeAssessmentStatusType,
     SelfManageTargetDestinationType,
     ServerCriteriaType,
     ServerErrorCategoryType,
     ServerOsTypeType,
     SeverityType,
     SortOrderType,
+    SourceCodeAnalyzerNameType,
     SrcCodeOrDbAnalysisStatusType,
     StrategyRecommendationType,
     StrategyType,
     TargetDatabaseEngineType,
     TargetDestinationType,
     TransformationToolNameType,
     VersionControlType,
@@ -60,18 +65,20 @@
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
+    "AnalysisStatusUnionTypeDef",
+    "AnalyzerNameUnionTypeDef",
+    "S3ObjectTypeDef",
     "AntipatternSeveritySummaryTypeDef",
     "AppUnitErrorTypeDef",
     "DatabaseConfigDetailTypeDef",
-    "S3ObjectTypeDef",
     "SourceCodeRepositoryTypeDef",
     "ApplicationComponentStatusSummaryTypeDef",
     "ApplicationComponentSummaryTypeDef",
     "ServerStatusSummaryTypeDef",
     "ServerSummaryTypeDef",
     "StrategySummaryTypeDef",
     "AssessmentTargetTypeDef",
@@ -84,80 +91,110 @@
     "VcenterBasedRemoteInfoTypeDef",
     "VersionControlInfoTypeDef",
     "DataCollectionDetailsTypeDef",
     "HeterogeneousTypeDef",
     "HomogeneousTypeDef",
     "NoDatabaseMigrationPreferenceTypeDef",
     "GetApplicationComponentDetailsRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "GetApplicationComponentStrategiesRequestRequestTypeDef",
     "GetAssessmentRequestRequestTypeDef",
     "GetImportFileTaskRequestRequestTypeDef",
+    "GetImportFileTaskResponseTypeDef",
+    "GetLatestAssessmentIdResponseTypeDef",
     "GetRecommendationReportDetailsRequestRequestTypeDef",
     "RecommendationReportDetailsTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetServerDetailsRequestGetServerDetailsPaginateTypeDef",
     "GetServerDetailsRequestRequestTypeDef",
     "GetServerStrategiesRequestRequestTypeDef",
     "GroupTypeDef",
     "ImportFileTaskInformationTypeDef",
+    "ListCollectorsRequestListCollectorsPaginateTypeDef",
     "ListCollectorsRequestRequestTypeDef",
+    "ListImportFileTaskRequestListImportFileTaskPaginateTypeDef",
     "ListImportFileTaskRequestRequestTypeDef",
     "NoManagementPreferenceTypeDef",
     "SelfManageResourcesTypeDef",
     "NetworkInfoTypeDef",
     "OSInfoTypeDef",
+    "PaginatorConfigTypeDef",
     "TransformationToolTypeDef",
+    "ResponseMetadataTypeDef",
     "ServerErrorTypeDef",
     "SourceCodeTypeDef",
+    "StartAssessmentResponseTypeDef",
+    "StartImportFileTaskResponseTypeDef",
+    "StartRecommendationReportGenerationResponseTypeDef",
     "StopAssessmentRequestRequestTypeDef",
     "StrategyOptionTypeDef",
+    "AntipatternReportResultTypeDef",
     "AssessmentSummaryTypeDef",
     "StartAssessmentRequestRequestTypeDef",
     "PrioritizeBusinessGoalsTypeDef",
     "ConfigurationSummaryTypeDef",
-    "DatabaseMigrationPreferenceTypeDef",
     "GetAssessmentResponseTypeDef",
-    "GetImportFileTaskResponseTypeDef",
-    "GetLatestAssessmentIdResponseTypeDef",
-    "StartAssessmentResponseTypeDef",
-    "StartImportFileTaskResponseTypeDef",
-    "StartRecommendationReportGenerationResponseTypeDef",
+    "DatabaseMigrationPreferenceTypeDef",
     "GetRecommendationReportDetailsResponseTypeDef",
-    "GetServerDetailsRequestGetServerDetailsPaginateTypeDef",
-    "ListCollectorsRequestListCollectorsPaginateTypeDef",
-    "ListImportFileTaskRequestListImportFileTaskPaginateTypeDef",
     "ListApplicationComponentsRequestListApplicationComponentsPaginateTypeDef",
     "ListApplicationComponentsRequestRequestTypeDef",
     "ListServersRequestListServersPaginateTypeDef",
     "ListServersRequestRequestTypeDef",
     "StartImportFileTaskRequestRequestTypeDef",
     "StartRecommendationReportGenerationRequestRequestTypeDef",
     "ListImportFileTaskResponseTypeDef",
     "ManagementPreferenceTypeDef",
     "SystemInfoTypeDef",
     "RecommendationSetTypeDef",
     "UpdateApplicationComponentConfigRequestRequestTypeDef",
     "UpdateServerConfigRequestRequestTypeDef",
+    "ResultTypeDef",
     "GetPortfolioSummaryResponseTypeDef",
     "CollectorTypeDef",
     "DatabasePreferencesTypeDef",
     "ApplicationPreferencesTypeDef",
-    "ApplicationComponentDetailTypeDef",
     "ApplicationComponentStrategyTypeDef",
     "ServerDetailTypeDef",
     "ServerStrategyTypeDef",
+    "ApplicationComponentDetailTypeDef",
     "ListCollectorsResponseTypeDef",
     "GetPortfolioPreferencesResponseTypeDef",
     "PutPortfolioPreferencesRequestRequestTypeDef",
-    "GetApplicationComponentDetailsResponseTypeDef",
-    "ListApplicationComponentsResponseTypeDef",
     "GetApplicationComponentStrategiesResponseTypeDef",
     "GetServerDetailsResponseTypeDef",
     "ListServersResponseTypeDef",
     "GetServerStrategiesResponseTypeDef",
+    "GetApplicationComponentDetailsResponseTypeDef",
+    "ListApplicationComponentsResponseTypeDef",
+)
+
+AnalysisStatusUnionTypeDef = TypedDict(
+    "AnalysisStatusUnionTypeDef",
+    {
+        "runtimeAnalysisStatus": RuntimeAnalysisStatusType,
+        "srcCodeOrDbAnalysisStatus": SrcCodeOrDbAnalysisStatusType,
+    },
+    total=False,
+)
+
+AnalyzerNameUnionTypeDef = TypedDict(
+    "AnalyzerNameUnionTypeDef",
+    {
+        "binaryAnalyzerName": BinaryAnalyzerNameType,
+        "runTimeAnalyzerName": RunTimeAnalyzerNameType,
+        "sourceCodeAnalyzerName": SourceCodeAnalyzerNameType,
+    },
+    total=False,
+)
+
+S3ObjectTypeDef = TypedDict(
+    "S3ObjectTypeDef",
+    {
+        "s3Bucket": str,
+        "s3key": str,
+    },
+    total=False,
 )
 
 AntipatternSeveritySummaryTypeDef = TypedDict(
     "AntipatternSeveritySummaryTypeDef",
     {
         "count": int,
         "severity": SeverityType,
@@ -177,23 +214,14 @@
     "DatabaseConfigDetailTypeDef",
     {
         "secretName": str,
     },
     total=False,
 )
 
-S3ObjectTypeDef = TypedDict(
-    "S3ObjectTypeDef",
-    {
-        "s3Bucket": str,
-        "s3key": str,
-    },
-    total=False,
-)
-
 SourceCodeRepositoryTypeDef = TypedDict(
     "SourceCodeRepositoryTypeDef",
     {
         "branch": str,
         "projectName": str,
         "repository": str,
         "versionControlType": str,
@@ -367,25 +395,14 @@
 GetApplicationComponentDetailsRequestRequestTypeDef = TypedDict(
     "GetApplicationComponentDetailsRequestRequestTypeDef",
     {
         "applicationComponentId": str,
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
 GetApplicationComponentStrategiesRequestRequestTypeDef = TypedDict(
     "GetApplicationComponentStrategiesRequestRequestTypeDef",
     {
         "applicationComponentId": str,
     },
 )
 
@@ -399,14 +416,40 @@
 GetImportFileTaskRequestRequestTypeDef = TypedDict(
     "GetImportFileTaskRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
+GetImportFileTaskResponseTypeDef = TypedDict(
+    "GetImportFileTaskResponseTypeDef",
+    {
+        "completionTime": datetime,
+        "id": str,
+        "importName": str,
+        "inputS3Bucket": str,
+        "inputS3Key": str,
+        "numberOfRecordsFailed": int,
+        "numberOfRecordsSuccess": int,
+        "startTime": datetime,
+        "status": ImportFileTaskStatusType,
+        "statusReportS3Bucket": str,
+        "statusReportS3Key": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetLatestAssessmentIdResponseTypeDef = TypedDict(
+    "GetLatestAssessmentIdResponseTypeDef",
+    {
+        "id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetRecommendationReportDetailsRequestRequestTypeDef = TypedDict(
     "GetRecommendationReportDetailsRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
@@ -419,24 +462,34 @@
         "startTime": datetime,
         "status": RecommendationReportStatusType,
         "statusMessage": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredGetServerDetailsRequestGetServerDetailsPaginateTypeDef = TypedDict(
+    "_RequiredGetServerDetailsRequestGetServerDetailsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "serverId": str,
+    },
+)
+_OptionalGetServerDetailsRequestGetServerDetailsPaginateTypeDef = TypedDict(
+    "_OptionalGetServerDetailsRequestGetServerDetailsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class GetServerDetailsRequestGetServerDetailsPaginateTypeDef(
+    _RequiredGetServerDetailsRequestGetServerDetailsPaginateTypeDef,
+    _OptionalGetServerDetailsRequestGetServerDetailsPaginateTypeDef,
+):
+    pass
+
 _RequiredGetServerDetailsRequestRequestTypeDef = TypedDict(
     "_RequiredGetServerDetailsRequestRequestTypeDef",
     {
         "serverId": str,
     },
 )
 _OptionalGetServerDetailsRequestRequestTypeDef = TypedDict(
@@ -459,15 +512,15 @@
         "serverId": str,
     },
 )
 
 GroupTypeDef = TypedDict(
     "GroupTypeDef",
     {
-        "name": Literal["ExternalId"],
+        "name": GroupNameType,
         "value": str,
     },
     total=False,
 )
 
 ImportFileTaskInformationTypeDef = TypedDict(
     "ImportFileTaskInformationTypeDef",
@@ -483,23 +536,39 @@
         "status": ImportFileTaskStatusType,
         "statusReportS3Bucket": str,
         "statusReportS3Key": str,
     },
     total=False,
 )
 
+ListCollectorsRequestListCollectorsPaginateTypeDef = TypedDict(
+    "ListCollectorsRequestListCollectorsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCollectorsRequestRequestTypeDef = TypedDict(
     "ListCollectorsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+ListImportFileTaskRequestListImportFileTaskPaginateTypeDef = TypedDict(
+    "ListImportFileTaskRequestListImportFileTaskPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListImportFileTaskRequestRequestTypeDef = TypedDict(
     "ListImportFileTaskRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -534,24 +603,45 @@
     {
         "type": OSTypeType,
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
 TransformationToolTypeDef = TypedDict(
     "TransformationToolTypeDef",
     {
         "description": str,
         "name": TransformationToolNameType,
         "tranformationToolInstallationLink": str,
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
 ServerErrorTypeDef = TypedDict(
     "ServerErrorTypeDef",
     {
         "serverErrorCategory": ServerErrorCategoryType,
     },
     total=False,
 )
@@ -563,14 +653,38 @@
         "projectName": str,
         "sourceVersion": str,
         "versionControl": VersionControlType,
     },
     total=False,
 )
 
+StartAssessmentResponseTypeDef = TypedDict(
+    "StartAssessmentResponseTypeDef",
+    {
+        "assessmentId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartImportFileTaskResponseTypeDef = TypedDict(
+    "StartImportFileTaskResponseTypeDef",
+    {
+        "id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartRecommendationReportGenerationResponseTypeDef = TypedDict(
+    "StartRecommendationReportGenerationResponseTypeDef",
+    {
+        "id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopAssessmentRequestRequestTypeDef = TypedDict(
     "StopAssessmentRequestRequestTypeDef",
     {
         "assessmentId": str,
     },
 )
 
@@ -581,14 +695,25 @@
         "strategy": StrategyType,
         "targetDestination": TargetDestinationType,
         "toolName": TransformationToolNameType,
     },
     total=False,
 )
 
+AntipatternReportResultTypeDef = TypedDict(
+    "AntipatternReportResultTypeDef",
+    {
+        "analyzerName": AnalyzerNameUnionTypeDef,
+        "antiPatternReportS3Object": S3ObjectTypeDef,
+        "antipatternReportStatus": AntipatternReportStatusType,
+        "antipatternReportStatusMessage": str,
+    },
+    total=False,
+)
+
 AssessmentSummaryTypeDef = TypedDict(
     "AssessmentSummaryTypeDef",
     {
         "antipatternReportS3Object": S3ObjectTypeDef,
         "antipatternReportStatus": AntipatternReportStatusType,
         "antipatternReportStatusMessage": str,
         "lastAnalyzedTimestamp": datetime,
@@ -629,137 +754,51 @@
         "remoteSourceCodeAnalysisServerInfo": RemoteSourceCodeAnalysisServerInfoTypeDef,
         "vcenterBasedRemoteInfoList": List[VcenterBasedRemoteInfoTypeDef],
         "versionControlInfoList": List[VersionControlInfoTypeDef],
     },
     total=False,
 )
 
-DatabaseMigrationPreferenceTypeDef = TypedDict(
-    "DatabaseMigrationPreferenceTypeDef",
-    {
-        "heterogeneous": HeterogeneousTypeDef,
-        "homogeneous": HomogeneousTypeDef,
-        "noPreference": NoDatabaseMigrationPreferenceTypeDef,
-    },
-    total=False,
-)
-
 GetAssessmentResponseTypeDef = TypedDict(
     "GetAssessmentResponseTypeDef",
     {
         "assessmentTargets": List[AssessmentTargetTypeDef],
         "dataCollectionDetails": DataCollectionDetailsTypeDef,
         "id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetImportFileTaskResponseTypeDef = TypedDict(
-    "GetImportFileTaskResponseTypeDef",
-    {
-        "completionTime": datetime,
-        "id": str,
-        "importName": str,
-        "inputS3Bucket": str,
-        "inputS3Key": str,
-        "numberOfRecordsFailed": int,
-        "numberOfRecordsSuccess": int,
-        "startTime": datetime,
-        "status": ImportFileTaskStatusType,
-        "statusReportS3Bucket": str,
-        "statusReportS3Key": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetLatestAssessmentIdResponseTypeDef = TypedDict(
-    "GetLatestAssessmentIdResponseTypeDef",
-    {
-        "id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartAssessmentResponseTypeDef = TypedDict(
-    "StartAssessmentResponseTypeDef",
-    {
-        "assessmentId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StartImportFileTaskResponseTypeDef = TypedDict(
-    "StartImportFileTaskResponseTypeDef",
-    {
-        "id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartRecommendationReportGenerationResponseTypeDef = TypedDict(
-    "StartRecommendationReportGenerationResponseTypeDef",
+DatabaseMigrationPreferenceTypeDef = TypedDict(
+    "DatabaseMigrationPreferenceTypeDef",
     {
-        "id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "heterogeneous": HeterogeneousTypeDef,
+        "homogeneous": HomogeneousTypeDef,
+        "noPreference": NoDatabaseMigrationPreferenceTypeDef,
     },
+    total=False,
 )
 
 GetRecommendationReportDetailsResponseTypeDef = TypedDict(
     "GetRecommendationReportDetailsResponseTypeDef",
     {
         "id": str,
         "recommendationReportDetails": RecommendationReportDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredGetServerDetailsRequestGetServerDetailsPaginateTypeDef = TypedDict(
-    "_RequiredGetServerDetailsRequestGetServerDetailsPaginateTypeDef",
-    {
-        "serverId": str,
-    },
-)
-_OptionalGetServerDetailsRequestGetServerDetailsPaginateTypeDef = TypedDict(
-    "_OptionalGetServerDetailsRequestGetServerDetailsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetServerDetailsRequestGetServerDetailsPaginateTypeDef(
-    _RequiredGetServerDetailsRequestGetServerDetailsPaginateTypeDef,
-    _OptionalGetServerDetailsRequestGetServerDetailsPaginateTypeDef,
-):
-    pass
-
-ListCollectorsRequestListCollectorsPaginateTypeDef = TypedDict(
-    "ListCollectorsRequestListCollectorsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
-)
-
-ListImportFileTaskRequestListImportFileTaskPaginateTypeDef = TypedDict(
-    "ListImportFileTaskRequestListImportFileTaskPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
 )
 
 ListApplicationComponentsRequestListApplicationComponentsPaginateTypeDef = TypedDict(
     "ListApplicationComponentsRequestListApplicationComponentsPaginateTypeDef",
     {
         "applicationComponentCriteria": ApplicationComponentCriteriaType,
         "filterValue": str,
         "groupIdFilter": Sequence[GroupTypeDef],
         "sort": SortOrderType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListApplicationComponentsRequestRequestTypeDef = TypedDict(
     "ListApplicationComponentsRequestRequestTypeDef",
     {
@@ -776,15 +815,15 @@
 ListServersRequestListServersPaginateTypeDef = TypedDict(
     "ListServersRequestListServersPaginateTypeDef",
     {
         "filterValue": str,
         "groupIdFilter": Sequence[GroupTypeDef],
         "serverCriteria": ServerCriteriaType,
         "sort": SortOrderType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListServersRequestRequestTypeDef = TypedDict(
     "ListServersRequestRequestTypeDef",
     {
@@ -832,15 +871,15 @@
 )
 
 ListImportFileTaskResponseTypeDef = TypedDict(
     "ListImportFileTaskResponseTypeDef",
     {
         "nextToken": str,
         "taskInfos": List[ImportFileTaskInformationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ManagementPreferenceTypeDef = TypedDict(
     "ManagementPreferenceTypeDef",
     {
         "awsManagedResources": AwsManagedResourcesTypeDef,
@@ -912,19 +951,30 @@
 
 class UpdateServerConfigRequestRequestTypeDef(
     _RequiredUpdateServerConfigRequestRequestTypeDef,
     _OptionalUpdateServerConfigRequestRequestTypeDef,
 ):
     pass
 
+ResultTypeDef = TypedDict(
+    "ResultTypeDef",
+    {
+        "analysisStatus": AnalysisStatusUnionTypeDef,
+        "analysisType": AnalysisTypeType,
+        "antipatternReportResultList": List[AntipatternReportResultTypeDef],
+        "statusMessage": str,
+    },
+    total=False,
+)
+
 GetPortfolioSummaryResponseTypeDef = TypedDict(
     "GetPortfolioSummaryResponseTypeDef",
     {
         "assessmentSummary": AssessmentSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CollectorTypeDef = TypedDict(
     "CollectorTypeDef",
     {
         "collectorHealth": CollectorHealthType,
@@ -952,43 +1002,14 @@
     "ApplicationPreferencesTypeDef",
     {
         "managementPreference": ManagementPreferenceTypeDef,
     },
     total=False,
 )
 
-ApplicationComponentDetailTypeDef = TypedDict(
-    "ApplicationComponentDetailTypeDef",
-    {
-        "analysisStatus": SrcCodeOrDbAnalysisStatusType,
-        "antipatternReportS3Object": S3ObjectTypeDef,
-        "antipatternReportStatus": AntipatternReportStatusType,
-        "antipatternReportStatusMessage": str,
-        "appType": AppTypeType,
-        "appUnitError": AppUnitErrorTypeDef,
-        "associatedServerId": str,
-        "databaseConfigDetail": DatabaseConfigDetailTypeDef,
-        "id": str,
-        "inclusionStatus": InclusionStatusType,
-        "lastAnalyzedTimestamp": datetime,
-        "listAntipatternSeveritySummary": List[AntipatternSeveritySummaryTypeDef],
-        "moreServerAssociationExists": bool,
-        "name": str,
-        "osDriver": str,
-        "osVersion": str,
-        "recommendationSet": RecommendationSetTypeDef,
-        "resourceSubType": ResourceSubTypeType,
-        "runtimeStatus": RuntimeAnalysisStatusType,
-        "runtimeStatusMessage": str,
-        "sourceCodeRepositories": List[SourceCodeRepositoryTypeDef],
-        "statusMessage": str,
-    },
-    total=False,
-)
-
 ApplicationComponentStrategyTypeDef = TypedDict(
     "ApplicationComponentStrategyTypeDef",
     {
         "isPreferred": bool,
         "recommendation": RecommendationSetTypeDef,
         "status": StrategyRecommendationType,
     },
@@ -1023,92 +1044,122 @@
         "numberOfApplicationComponents": int,
         "recommendation": RecommendationSetTypeDef,
         "status": StrategyRecommendationType,
     },
     total=False,
 )
 
+ApplicationComponentDetailTypeDef = TypedDict(
+    "ApplicationComponentDetailTypeDef",
+    {
+        "analysisStatus": SrcCodeOrDbAnalysisStatusType,
+        "antipatternReportS3Object": S3ObjectTypeDef,
+        "antipatternReportStatus": AntipatternReportStatusType,
+        "antipatternReportStatusMessage": str,
+        "appType": AppTypeType,
+        "appUnitError": AppUnitErrorTypeDef,
+        "associatedServerId": str,
+        "databaseConfigDetail": DatabaseConfigDetailTypeDef,
+        "id": str,
+        "inclusionStatus": InclusionStatusType,
+        "lastAnalyzedTimestamp": datetime,
+        "listAntipatternSeveritySummary": List[AntipatternSeveritySummaryTypeDef],
+        "moreServerAssociationExists": bool,
+        "name": str,
+        "osDriver": str,
+        "osVersion": str,
+        "recommendationSet": RecommendationSetTypeDef,
+        "resourceSubType": ResourceSubTypeType,
+        "resultList": List[ResultTypeDef],
+        "runtimeStatus": RuntimeAnalysisStatusType,
+        "runtimeStatusMessage": str,
+        "sourceCodeRepositories": List[SourceCodeRepositoryTypeDef],
+        "statusMessage": str,
+    },
+    total=False,
+)
+
 ListCollectorsResponseTypeDef = TypedDict(
     "ListCollectorsResponseTypeDef",
     {
         "Collectors": List[CollectorTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetPortfolioPreferencesResponseTypeDef = TypedDict(
     "GetPortfolioPreferencesResponseTypeDef",
     {
         "applicationMode": ApplicationModeType,
         "applicationPreferences": ApplicationPreferencesTypeDef,
         "databasePreferences": DatabasePreferencesTypeDef,
         "prioritizeBusinessGoals": PrioritizeBusinessGoalsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutPortfolioPreferencesRequestRequestTypeDef = TypedDict(
     "PutPortfolioPreferencesRequestRequestTypeDef",
     {
         "applicationMode": ApplicationModeType,
         "applicationPreferences": ApplicationPreferencesTypeDef,
         "databasePreferences": DatabasePreferencesTypeDef,
         "prioritizeBusinessGoals": PrioritizeBusinessGoalsTypeDef,
     },
     total=False,
 )
 
-GetApplicationComponentDetailsResponseTypeDef = TypedDict(
-    "GetApplicationComponentDetailsResponseTypeDef",
-    {
-        "applicationComponentDetail": ApplicationComponentDetailTypeDef,
-        "associatedApplications": List[AssociatedApplicationTypeDef],
-        "associatedServerIds": List[str],
-        "moreApplicationResource": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListApplicationComponentsResponseTypeDef = TypedDict(
-    "ListApplicationComponentsResponseTypeDef",
-    {
-        "applicationComponentInfos": List[ApplicationComponentDetailTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 GetApplicationComponentStrategiesResponseTypeDef = TypedDict(
     "GetApplicationComponentStrategiesResponseTypeDef",
     {
         "applicationComponentStrategies": List[ApplicationComponentStrategyTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetServerDetailsResponseTypeDef = TypedDict(
     "GetServerDetailsResponseTypeDef",
     {
         "associatedApplications": List[AssociatedApplicationTypeDef],
         "nextToken": str,
         "serverDetail": ServerDetailTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListServersResponseTypeDef = TypedDict(
     "ListServersResponseTypeDef",
     {
         "nextToken": str,
         "serverInfos": List[ServerDetailTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetServerStrategiesResponseTypeDef = TypedDict(
     "GetServerStrategiesResponseTypeDef",
     {
         "serverStrategies": List[ServerStrategyTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetApplicationComponentDetailsResponseTypeDef = TypedDict(
+    "GetApplicationComponentDetailsResponseTypeDef",
+    {
+        "applicationComponentDetail": ApplicationComponentDetailTypeDef,
+        "associatedApplications": List[AssociatedApplicationTypeDef],
+        "associatedServerIds": List[str],
+        "moreApplicationResource": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListApplicationComponentsResponseTypeDef = TypedDict(
+    "ListApplicationComponentsResponseTypeDef",
+    {
+        "applicationComponentInfos": List[ApplicationComponentDetailTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-migrationhubstrategy-2.5.0.post1/types_aiobotocore_migrationhubstrategy.egg-info/PKG-INFO` & `types-aiobotocore-migrationhubstrategy-2.5.1/types_aiobotocore_migrationhubstrategy.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-migrationhubstrategy
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MigrationHubStrategyRecommendations 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MigrationHubStrategyRecommendations 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhubstrategy/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-migrationhubstrategy"></a>
 
 # types-aiobotocore-migrationhubstrategy
 
 [![PyPI - types-aiobotocore-migrationhubstrategy](https://img.shields.io/pypi/v/types-aiobotocore-migrationhubstrategy.svg?color=blue)](https://pypi.org/project/types-aiobotocore-migrationhubstrategy)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-migrationhubstrategy.svg?color=blue)](https://pypi.org/project/types-aiobotocore-migrationhubstrategy)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhubstrategy/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-migrationhubstrategy?color=blue)](https://pypistats.org/packages/types-aiobotocore-migrationhubstrategy)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MigrationHubStrategyRecommendations 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhubstrategy.html#MigrationHubStrategyRecommendations)
+[aiobotocore.MigrationHubStrategyRecommendations 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/migrationhubstrategy.html#MigrationHubStrategyRecommendations)
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
 [types-aiobotocore-migrationhubstrategy docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_migrationhubstrategy/).
 
 See how it helps to find and fix potential bugs:
 
@@ -308,22 +308,24 @@
 ### Literals
 
 `types_aiobotocore_migrationhubstrategy.literals` module contains literals
 extracted from shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_migrationhubstrategy.literals import (
+    AnalysisTypeType,
     AntipatternReportStatusType,
     AppTypeType,
     AppUnitErrorCategoryType,
     ApplicationComponentCriteriaType,
     ApplicationModeType,
     AssessmentStatusType,
     AuthTypeType,
     AwsManagedTargetDestinationType,
+    BinaryAnalyzerNameType,
     CollectorHealthType,
     ConditionType,
     DataSourceTypeType,
     DatabaseManagementPreferenceType,
     GetServerDetailsPaginatorName,
     GroupNameType,
     HeterogeneousTargetDatabaseEngineType,
@@ -336,22 +338,24 @@
     ListServersPaginatorName,
     NoPreferenceTargetDestinationType,
     OSTypeType,
     OutputFormatType,
     PipelineTypeType,
     RecommendationReportStatusType,
     ResourceSubTypeType,
+    RunTimeAnalyzerNameType,
     RunTimeAssessmentStatusType,
     RuntimeAnalysisStatusType,
     SelfManageTargetDestinationType,
     ServerCriteriaType,
     ServerErrorCategoryType,
     ServerOsTypeType,
     SeverityType,
     SortOrderType,
+    SourceCodeAnalyzerNameType,
     SrcCodeOrDbAnalysisStatusType,
     StrategyRecommendationType,
     StrategyType,
     TargetDatabaseEngineType,
     TargetDestinationType,
     TransformationToolNameType,
     VersionControlType,
@@ -360,31 +364,33 @@
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
 )
 
 
-def check_value(value: AntipatternReportStatusType) -> bool:
+def check_value(value: AnalysisTypeType) -> bool:
     ...
 ```
 
 <a id="typed-dictionaries"></a>
 
 ### Typed dictionaries
 
 `types_aiobotocore_migrationhubstrategy.type_defs` module contains structures
 and shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_migrationhubstrategy.type_defs import (
+    AnalysisStatusUnionTypeDef,
+    AnalyzerNameUnionTypeDef,
+    S3ObjectTypeDef,
     AntipatternSeveritySummaryTypeDef,
     AppUnitErrorTypeDef,
     DatabaseConfigDetailTypeDef,
-    S3ObjectTypeDef,
     SourceCodeRepositoryTypeDef,
     ApplicationComponentStatusSummaryTypeDef,
     ApplicationComponentSummaryTypeDef,
     ServerStatusSummaryTypeDef,
     ServerSummaryTypeDef,
     StrategySummaryTypeDef,
     AssessmentTargetTypeDef,
@@ -397,123 +403,125 @@
     VcenterBasedRemoteInfoTypeDef,
     VersionControlInfoTypeDef,
     DataCollectionDetailsTypeDef,
     HeterogeneousTypeDef,
     HomogeneousTypeDef,
     NoDatabaseMigrationPreferenceTypeDef,
     GetApplicationComponentDetailsRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     GetApplicationComponentStrategiesRequestRequestTypeDef,
     GetAssessmentRequestRequestTypeDef,
     GetImportFileTaskRequestRequestTypeDef,
+    GetImportFileTaskResponseTypeDef,
+    GetLatestAssessmentIdResponseTypeDef,
     GetRecommendationReportDetailsRequestRequestTypeDef,
     RecommendationReportDetailsTypeDef,
-    PaginatorConfigTypeDef,
+    GetServerDetailsRequestGetServerDetailsPaginateTypeDef,
     GetServerDetailsRequestRequestTypeDef,
     GetServerStrategiesRequestRequestTypeDef,
     GroupTypeDef,
     ImportFileTaskInformationTypeDef,
+    ListCollectorsRequestListCollectorsPaginateTypeDef,
     ListCollectorsRequestRequestTypeDef,
+    ListImportFileTaskRequestListImportFileTaskPaginateTypeDef,
     ListImportFileTaskRequestRequestTypeDef,
     NoManagementPreferenceTypeDef,
     SelfManageResourcesTypeDef,
     NetworkInfoTypeDef,
     OSInfoTypeDef,
+    PaginatorConfigTypeDef,
     TransformationToolTypeDef,
+    ResponseMetadataTypeDef,
     ServerErrorTypeDef,
     SourceCodeTypeDef,
+    StartAssessmentResponseTypeDef,
+    StartImportFileTaskResponseTypeDef,
+    StartRecommendationReportGenerationResponseTypeDef,
     StopAssessmentRequestRequestTypeDef,
     StrategyOptionTypeDef,
+    AntipatternReportResultTypeDef,
     AssessmentSummaryTypeDef,
     StartAssessmentRequestRequestTypeDef,
     PrioritizeBusinessGoalsTypeDef,
     ConfigurationSummaryTypeDef,
-    DatabaseMigrationPreferenceTypeDef,
     GetAssessmentResponseTypeDef,
-    GetImportFileTaskResponseTypeDef,
-    GetLatestAssessmentIdResponseTypeDef,
-    StartAssessmentResponseTypeDef,
-    StartImportFileTaskResponseTypeDef,
-    StartRecommendationReportGenerationResponseTypeDef,
+    DatabaseMigrationPreferenceTypeDef,
     GetRecommendationReportDetailsResponseTypeDef,
-    GetServerDetailsRequestGetServerDetailsPaginateTypeDef,
-    ListCollectorsRequestListCollectorsPaginateTypeDef,
-    ListImportFileTaskRequestListImportFileTaskPaginateTypeDef,
     ListApplicationComponentsRequestListApplicationComponentsPaginateTypeDef,
     ListApplicationComponentsRequestRequestTypeDef,
     ListServersRequestListServersPaginateTypeDef,
     ListServersRequestRequestTypeDef,
     StartImportFileTaskRequestRequestTypeDef,
     StartRecommendationReportGenerationRequestRequestTypeDef,
     ListImportFileTaskResponseTypeDef,
     ManagementPreferenceTypeDef,
     SystemInfoTypeDef,
     RecommendationSetTypeDef,
     UpdateApplicationComponentConfigRequestRequestTypeDef,
     UpdateServerConfigRequestRequestTypeDef,
+    ResultTypeDef,
     GetPortfolioSummaryResponseTypeDef,
     CollectorTypeDef,
     DatabasePreferencesTypeDef,
     ApplicationPreferencesTypeDef,
-    ApplicationComponentDetailTypeDef,
     ApplicationComponentStrategyTypeDef,
     ServerDetailTypeDef,
     ServerStrategyTypeDef,
+    ApplicationComponentDetailTypeDef,
     ListCollectorsResponseTypeDef,
     GetPortfolioPreferencesResponseTypeDef,
     PutPortfolioPreferencesRequestRequestTypeDef,
-    GetApplicationComponentDetailsResponseTypeDef,
-    ListApplicationComponentsResponseTypeDef,
     GetApplicationComponentStrategiesResponseTypeDef,
     GetServerDetailsResponseTypeDef,
     ListServersResponseTypeDef,
     GetServerStrategiesResponseTypeDef,
+    GetApplicationComponentDetailsResponseTypeDef,
+    ListApplicationComponentsResponseTypeDef,
 )
 
 
-def get_structure() -> AntipatternSeveritySummaryTypeDef:
+def get_structure() -> AnalysisStatusUnionTypeDef:
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

### Comparing `types-aiobotocore-migrationhubstrategy-2.5.0.post1/types_aiobotocore_migrationhubstrategy.egg-info/SOURCES.txt` & `types-aiobotocore-migrationhubstrategy-2.5.1/types_aiobotocore_migrationhubstrategy.egg-info/SOURCES.txt`

 * *Files identical despite different names*

