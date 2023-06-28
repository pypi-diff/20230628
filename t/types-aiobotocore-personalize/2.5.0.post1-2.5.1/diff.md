# Comparing `tmp/types-aiobotocore-personalize-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-personalize-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-personalize-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:06 2023, max compression
+gzip compressed data, was "types-aiobotocore-personalize-2.5.1.tar", last modified: Wed Jun 28 01:43:58 2023, max compression
```

## Comparing `types-aiobotocore-personalize-2.5.0.post1.tar` & `types-aiobotocore-personalize-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:06.199489 types-aiobotocore-personalize-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:19:40.000000 types-aiobotocore-personalize-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    24076 2023-03-11 12:27:06.187489 types-aiobotocore-personalize-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    22489 2023-03-11 12:19:40.000000 types-aiobotocore-personalize-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:06.199489 types-aiobotocore-personalize-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2152 2023-03-11 12:19:39.000000 types-aiobotocore-personalize-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:06.183489 types-aiobotocore-personalize-2.5.0.post1/types_aiobotocore_personalize/
--rw-r--r--   0 runner    (1001) docker     (123)     3887 2023-03-11 12:19:40.000000 types-aiobotocore-personalize-2.5.0.post1/types_aiobotocore_personalize/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3886 2023-03-11 12:19:40.000000 types-aiobotocore-personalize-2.5.0.post1/types_aiobotocore_personalize/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      959 2023-03-11 12:19:40.000000 types-aiobotocore-personalize-2.5.0.post1/types_aiobotocore_personalize/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    53958 2023-03-11 12:19:40.000000 types-aiobotocore-personalize-2.5.0.post1/types_aiobotocore_personalize/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    53867 2023-03-11 12:19:40.000000 types-aiobotocore-personalize-2.5.0.post1/types_aiobotocore_personalize/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10147 2023-03-11 12:19:40.000000 types-aiobotocore-personalize-2.5.0.post1/types_aiobotocore_personalize/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    10145 2023-03-11 12:19:40.000000 types-aiobotocore-personalize-2.5.0.post1/types_aiobotocore_personalize/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    19640 2023-03-11 12:19:40.000000 types-aiobotocore-personalize-2.5.0.post1/types_aiobotocore_personalize/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    19621 2023-03-11 12:19:40.000000 types-aiobotocore-personalize-2.5.0.post1/types_aiobotocore_personalize/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:19:40.000000 types-aiobotocore-personalize-2.5.0.post1/types_aiobotocore_personalize/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    62201 2023-03-11 12:19:44.000000 types-aiobotocore-personalize-2.5.0.post1/types_aiobotocore_personalize/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    62166 2023-03-11 12:19:41.000000 types-aiobotocore-personalize-2.5.0.post1/types_aiobotocore_personalize/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:19:40.000000 types-aiobotocore-personalize-2.5.0.post1/types_aiobotocore_personalize/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:06.187489 types-aiobotocore-personalize-2.5.0.post1/types_aiobotocore_personalize.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    24076 2023-03-11 12:27:06.000000 types-aiobotocore-personalize-2.5.0.post1/types_aiobotocore_personalize.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      889 2023-03-11 12:27:06.000000 types-aiobotocore-personalize-2.5.0.post1/types_aiobotocore_personalize.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:06.000000 types-aiobotocore-personalize-2.5.0.post1/types_aiobotocore_personalize.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:06.000000 types-aiobotocore-personalize-2.5.0.post1/types_aiobotocore_personalize.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:06.000000 types-aiobotocore-personalize-2.5.0.post1/types_aiobotocore_personalize.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       30 2023-03-11 12:27:06.000000 types-aiobotocore-personalize-2.5.0.post1/types_aiobotocore_personalize.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:58.298190 types-aiobotocore-personalize-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:36:29.000000 types-aiobotocore-personalize-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    24103 2023-06-28 01:43:58.298190 types-aiobotocore-personalize-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    22522 2023-06-28 01:36:29.000000 types-aiobotocore-personalize-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:58.298190 types-aiobotocore-personalize-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2146 2023-06-28 01:36:28.000000 types-aiobotocore-personalize-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:58.298190 types-aiobotocore-personalize-2.5.1/types_aiobotocore_personalize/
+-rw-r--r--   0 runner    (1001) docker     (123)     3887 2023-06-28 01:36:29.000000 types-aiobotocore-personalize-2.5.1/types_aiobotocore_personalize/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3886 2023-06-28 01:36:29.000000 types-aiobotocore-personalize-2.5.1/types_aiobotocore_personalize/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      947 2023-06-28 01:36:29.000000 types-aiobotocore-personalize-2.5.1/types_aiobotocore_personalize/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    53956 2023-06-28 01:36:29.000000 types-aiobotocore-personalize-2.5.1/types_aiobotocore_personalize/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    53865 2023-06-28 01:36:29.000000 types-aiobotocore-personalize-2.5.1/types_aiobotocore_personalize/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10356 2023-06-28 01:36:29.000000 types-aiobotocore-personalize-2.5.1/types_aiobotocore_personalize/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10354 2023-06-28 01:36:29.000000 types-aiobotocore-personalize-2.5.1/types_aiobotocore_personalize/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    19565 2023-06-28 01:36:29.000000 types-aiobotocore-personalize-2.5.1/types_aiobotocore_personalize/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19546 2023-06-28 01:36:29.000000 types-aiobotocore-personalize-2.5.1/types_aiobotocore_personalize/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:36:29.000000 types-aiobotocore-personalize-2.5.1/types_aiobotocore_personalize/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    62658 2023-06-28 01:36:30.000000 types-aiobotocore-personalize-2.5.1/types_aiobotocore_personalize/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    62623 2023-06-28 01:36:30.000000 types-aiobotocore-personalize-2.5.1/types_aiobotocore_personalize/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:36:29.000000 types-aiobotocore-personalize-2.5.1/types_aiobotocore_personalize/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:58.298190 types-aiobotocore-personalize-2.5.1/types_aiobotocore_personalize.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    24103 2023-06-28 01:43:58.000000 types-aiobotocore-personalize-2.5.1/types_aiobotocore_personalize.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      889 2023-06-28 01:43:58.000000 types-aiobotocore-personalize-2.5.1/types_aiobotocore_personalize.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:58.000000 types-aiobotocore-personalize-2.5.1/types_aiobotocore_personalize.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:58.000000 types-aiobotocore-personalize-2.5.1/types_aiobotocore_personalize.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:58.000000 types-aiobotocore-personalize-2.5.1/types_aiobotocore_personalize.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       30 2023-06-28 01:43:58.000000 types-aiobotocore-personalize-2.5.1/types_aiobotocore_personalize.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-personalize-2.5.0.post1/LICENSE` & `types-aiobotocore-personalize-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-personalize-2.5.0.post1/PKG-INFO` & `types-aiobotocore-personalize-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-personalize
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Personalize 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Personalize 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-personalize"></a>
 
 # types-aiobotocore-personalize
 
 [![PyPI - types-aiobotocore-personalize](https://img.shields.io/pypi/v/types-aiobotocore-personalize.svg?color=blue)](https://pypi.org/project/types-aiobotocore-personalize)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-personalize.svg?color=blue)](https://pypi.org/project/types-aiobotocore-personalize)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-personalize?color=blue)](https://pypistats.org/packages/types-aiobotocore-personalize)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Personalize 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize)
+[aiobotocore.Personalize 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize)
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
 [types-aiobotocore-personalize docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/).
 
 See how it helps to find and fix potential bugs:
 
@@ -399,19 +399,31 @@
     BatchInferenceJobSummaryTypeDef,
     BatchSegmentJobSummaryTypeDef,
     CampaignConfigTypeDef,
     CampaignSummaryTypeDef,
     CategoricalHyperParameterRangeTypeDef,
     ContinuousHyperParameterRangeTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateBatchInferenceJobResponseTypeDef,
+    CreateBatchSegmentJobResponseTypeDef,
+    CreateCampaignResponseTypeDef,
+    CreateDatasetExportJobResponseTypeDef,
+    CreateDatasetGroupResponseTypeDef,
     DataSourceTypeDef,
+    CreateDatasetImportJobResponseTypeDef,
+    CreateDatasetResponseTypeDef,
+    CreateEventTrackerResponseTypeDef,
+    CreateFilterResponseTypeDef,
     MetricAttributeTypeDef,
-    RecommenderConfigTypeDef,
+    CreateMetricAttributionResponseTypeDef,
+    CreateRecommenderResponseTypeDef,
     CreateSchemaRequestRequestTypeDef,
+    CreateSchemaResponseTypeDef,
+    CreateSolutionResponseTypeDef,
+    CreateSolutionVersionResponseTypeDef,
     DatasetExportJobSummaryTypeDef,
     DatasetGroupSummaryTypeDef,
     DatasetGroupTypeDef,
     DatasetImportJobSummaryTypeDef,
     DatasetSchemaSummaryTypeDef,
     DatasetSchemaTypeDef,
     DatasetSummaryTypeDef,
@@ -445,95 +457,95 @@
     DescribeMetricAttributionRequestRequestTypeDef,
     DescribeRecipeRequestRequestTypeDef,
     RecipeTypeDef,
     DescribeRecommenderRequestRequestTypeDef,
     DescribeSchemaRequestRequestTypeDef,
     DescribeSolutionRequestRequestTypeDef,
     DescribeSolutionVersionRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EventTrackerSummaryTypeDef,
     FilterSummaryTypeDef,
     GetSolutionMetricsRequestRequestTypeDef,
+    GetSolutionMetricsResponseTypeDef,
     HPOObjectiveTypeDef,
     HPOResourceConfigTypeDef,
     IntegerHyperParameterRangeTypeDef,
-    PaginatorConfigTypeDef,
+    ListBatchInferenceJobsRequestListBatchInferenceJobsPaginateTypeDef,
     ListBatchInferenceJobsRequestRequestTypeDef,
+    ListBatchSegmentJobsRequestListBatchSegmentJobsPaginateTypeDef,
     ListBatchSegmentJobsRequestRequestTypeDef,
+    ListCampaignsRequestListCampaignsPaginateTypeDef,
     ListCampaignsRequestRequestTypeDef,
+    ListDatasetExportJobsRequestListDatasetExportJobsPaginateTypeDef,
     ListDatasetExportJobsRequestRequestTypeDef,
+    ListDatasetGroupsRequestListDatasetGroupsPaginateTypeDef,
     ListDatasetGroupsRequestRequestTypeDef,
+    ListDatasetImportJobsRequestListDatasetImportJobsPaginateTypeDef,
     ListDatasetImportJobsRequestRequestTypeDef,
+    ListDatasetsRequestListDatasetsPaginateTypeDef,
     ListDatasetsRequestRequestTypeDef,
+    ListEventTrackersRequestListEventTrackersPaginateTypeDef,
     ListEventTrackersRequestRequestTypeDef,
+    ListFiltersRequestListFiltersPaginateTypeDef,
     ListFiltersRequestRequestTypeDef,
+    ListMetricAttributionMetricsRequestListMetricAttributionMetricsPaginateTypeDef,
     ListMetricAttributionMetricsRequestRequestTypeDef,
+    ListMetricAttributionsRequestListMetricAttributionsPaginateTypeDef,
     ListMetricAttributionsRequestRequestTypeDef,
     MetricAttributionSummaryTypeDef,
+    ListRecipesRequestListRecipesPaginateTypeDef,
     ListRecipesRequestRequestTypeDef,
     RecipeSummaryTypeDef,
+    ListRecommendersRequestListRecommendersPaginateTypeDef,
     ListRecommendersRequestRequestTypeDef,
+    ListSchemasRequestListSchemasPaginateTypeDef,
     ListSchemasRequestRequestTypeDef,
+    ListSolutionVersionsRequestListSolutionVersionsPaginateTypeDef,
     ListSolutionVersionsRequestRequestTypeDef,
     SolutionVersionSummaryTypeDef,
+    ListSolutionsRequestListSolutionsPaginateTypeDef,
     ListSolutionsRequestRequestTypeDef,
     SolutionSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     OptimizationObjectiveTypeDef,
+    PaginatorConfigTypeDef,
+    TrainingDataConfigTypeDef,
+    ResponseMetadataTypeDef,
     TunedHPOParamsTypeDef,
     StartRecommenderRequestRequestTypeDef,
+    StartRecommenderResponseTypeDef,
     StopRecommenderRequestRequestTypeDef,
+    StopRecommenderResponseTypeDef,
     StopSolutionVersionCreationRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateCampaignResponseTypeDef,
+    UpdateMetricAttributionResponseTypeDef,
+    UpdateRecommenderResponseTypeDef,
     BatchInferenceJobInputTypeDef,
     BatchInferenceJobOutputTypeDef,
     BatchSegmentJobInputTypeDef,
     BatchSegmentJobOutputTypeDef,
     DatasetExportJobOutputTypeDef,
     MetricAttributionOutputTypeDef,
+    ListBatchInferenceJobsResponseTypeDef,
+    ListBatchSegmentJobsResponseTypeDef,
     CampaignUpdateSummaryTypeDef,
     UpdateCampaignRequestRequestTypeDef,
+    ListCampaignsResponseTypeDef,
     CreateCampaignRequestRequestTypeDef,
     CreateDatasetGroupRequestRequestTypeDef,
     CreateDatasetRequestRequestTypeDef,
     CreateEventTrackerRequestRequestTypeDef,
     CreateFilterRequestRequestTypeDef,
     CreateSolutionVersionRequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
-    CreateBatchInferenceJobResponseTypeDef,
-    CreateBatchSegmentJobResponseTypeDef,
-    CreateCampaignResponseTypeDef,
-    CreateDatasetExportJobResponseTypeDef,
-    CreateDatasetGroupResponseTypeDef,
-    CreateDatasetImportJobResponseTypeDef,
-    CreateDatasetResponseTypeDef,
-    CreateEventTrackerResponseTypeDef,
-    CreateFilterResponseTypeDef,
-    CreateMetricAttributionResponseTypeDef,
-    CreateRecommenderResponseTypeDef,
-    CreateSchemaResponseTypeDef,
-    CreateSolutionResponseTypeDef,
-    CreateSolutionVersionResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetSolutionMetricsResponseTypeDef,
-    ListBatchInferenceJobsResponseTypeDef,
-    ListBatchSegmentJobsResponseTypeDef,
-    ListCampaignsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
-    StartRecommenderResponseTypeDef,
-    StopRecommenderResponseTypeDef,
-    UpdateCampaignResponseTypeDef,
-    UpdateMetricAttributionResponseTypeDef,
-    UpdateRecommenderResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
     CreateDatasetImportJobRequestRequestTypeDef,
     DatasetImportJobTypeDef,
     ListMetricAttributionMetricsResponseTypeDef,
-    CreateRecommenderRequestRequestTypeDef,
-    RecommenderSummaryTypeDef,
-    RecommenderUpdateSummaryTypeDef,
-    UpdateRecommenderRequestRequestTypeDef,
     ListDatasetExportJobsResponseTypeDef,
     ListDatasetGroupsResponseTypeDef,
     DescribeDatasetGroupResponseTypeDef,
     ListDatasetImportJobsResponseTypeDef,
     ListSchemasResponseTypeDef,
     DescribeSchemaResponseTypeDef,
     ListDatasetsResponseTypeDef,
@@ -542,60 +554,49 @@
     DescribeEventTrackerResponseTypeDef,
     DescribeFeatureTransformationResponseTypeDef,
     DescribeFilterResponseTypeDef,
     DescribeRecipeResponseTypeDef,
     ListEventTrackersResponseTypeDef,
     ListFiltersResponseTypeDef,
     HyperParameterRangesTypeDef,
-    ListBatchInferenceJobsRequestListBatchInferenceJobsPaginateTypeDef,
-    ListBatchSegmentJobsRequestListBatchSegmentJobsPaginateTypeDef,
-    ListCampaignsRequestListCampaignsPaginateTypeDef,
-    ListDatasetExportJobsRequestListDatasetExportJobsPaginateTypeDef,
-    ListDatasetGroupsRequestListDatasetGroupsPaginateTypeDef,
-    ListDatasetImportJobsRequestListDatasetImportJobsPaginateTypeDef,
-    ListDatasetsRequestListDatasetsPaginateTypeDef,
-    ListEventTrackersRequestListEventTrackersPaginateTypeDef,
-    ListFiltersRequestListFiltersPaginateTypeDef,
-    ListMetricAttributionMetricsRequestListMetricAttributionMetricsPaginateTypeDef,
-    ListMetricAttributionsRequestListMetricAttributionsPaginateTypeDef,
-    ListRecipesRequestListRecipesPaginateTypeDef,
-    ListRecommendersRequestListRecommendersPaginateTypeDef,
-    ListSchemasRequestListSchemasPaginateTypeDef,
-    ListSolutionVersionsRequestListSolutionVersionsPaginateTypeDef,
-    ListSolutionsRequestListSolutionsPaginateTypeDef,
     ListMetricAttributionsResponseTypeDef,
     ListRecipesResponseTypeDef,
     ListSolutionVersionsResponseTypeDef,
     ListSolutionsResponseTypeDef,
+    RecommenderConfigTypeDef,
     BatchInferenceJobTypeDef,
     CreateBatchInferenceJobRequestRequestTypeDef,
     BatchSegmentJobTypeDef,
     CreateBatchSegmentJobRequestRequestTypeDef,
     CreateDatasetExportJobRequestRequestTypeDef,
     DatasetExportJobTypeDef,
     CreateMetricAttributionRequestRequestTypeDef,
     MetricAttributionTypeDef,
     UpdateMetricAttributionRequestRequestTypeDef,
     CampaignTypeDef,
     DescribeDatasetImportJobResponseTypeDef,
-    ListRecommendersResponseTypeDef,
-    RecommenderTypeDef,
     AlgorithmTypeDef,
     HPOConfigTypeDef,
+    CreateRecommenderRequestRequestTypeDef,
+    RecommenderSummaryTypeDef,
+    RecommenderUpdateSummaryTypeDef,
+    UpdateRecommenderRequestRequestTypeDef,
     DescribeBatchInferenceJobResponseTypeDef,
     DescribeBatchSegmentJobResponseTypeDef,
     DescribeDatasetExportJobResponseTypeDef,
     DescribeMetricAttributionResponseTypeDef,
     DescribeCampaignResponseTypeDef,
-    DescribeRecommenderResponseTypeDef,
     DescribeAlgorithmResponseTypeDef,
     SolutionConfigTypeDef,
+    ListRecommendersResponseTypeDef,
+    RecommenderTypeDef,
     CreateSolutionRequestRequestTypeDef,
     SolutionTypeDef,
     SolutionVersionTypeDef,
+    DescribeRecommenderResponseTypeDef,
     DescribeSolutionResponseTypeDef,
     DescribeSolutionVersionResponseTypeDef,
 )
 
 
 def get_structure() -> AlgorithmImageTypeDef:
     return {...}
@@ -604,43 +605,43 @@
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

### Comparing `types-aiobotocore-personalize-2.5.0.post1/README.md` & `types-aiobotocore-personalize-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-personalize"></a>
 
 # types-aiobotocore-personalize
 
 [![PyPI - types-aiobotocore-personalize](https://img.shields.io/pypi/v/types-aiobotocore-personalize.svg?color=blue)](https://pypi.org/project/types-aiobotocore-personalize)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-personalize.svg?color=blue)](https://pypi.org/project/types-aiobotocore-personalize)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-personalize?color=blue)](https://pypistats.org/packages/types-aiobotocore-personalize)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Personalize 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize)
+[aiobotocore.Personalize 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize)
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
 [types-aiobotocore-personalize docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/).
 
 See how it helps to find and fix potential bugs:
 
@@ -366,19 +366,31 @@
     BatchInferenceJobSummaryTypeDef,
     BatchSegmentJobSummaryTypeDef,
     CampaignConfigTypeDef,
     CampaignSummaryTypeDef,
     CategoricalHyperParameterRangeTypeDef,
     ContinuousHyperParameterRangeTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateBatchInferenceJobResponseTypeDef,
+    CreateBatchSegmentJobResponseTypeDef,
+    CreateCampaignResponseTypeDef,
+    CreateDatasetExportJobResponseTypeDef,
+    CreateDatasetGroupResponseTypeDef,
     DataSourceTypeDef,
+    CreateDatasetImportJobResponseTypeDef,
+    CreateDatasetResponseTypeDef,
+    CreateEventTrackerResponseTypeDef,
+    CreateFilterResponseTypeDef,
     MetricAttributeTypeDef,
-    RecommenderConfigTypeDef,
+    CreateMetricAttributionResponseTypeDef,
+    CreateRecommenderResponseTypeDef,
     CreateSchemaRequestRequestTypeDef,
+    CreateSchemaResponseTypeDef,
+    CreateSolutionResponseTypeDef,
+    CreateSolutionVersionResponseTypeDef,
     DatasetExportJobSummaryTypeDef,
     DatasetGroupSummaryTypeDef,
     DatasetGroupTypeDef,
     DatasetImportJobSummaryTypeDef,
     DatasetSchemaSummaryTypeDef,
     DatasetSchemaTypeDef,
     DatasetSummaryTypeDef,
@@ -412,95 +424,95 @@
     DescribeMetricAttributionRequestRequestTypeDef,
     DescribeRecipeRequestRequestTypeDef,
     RecipeTypeDef,
     DescribeRecommenderRequestRequestTypeDef,
     DescribeSchemaRequestRequestTypeDef,
     DescribeSolutionRequestRequestTypeDef,
     DescribeSolutionVersionRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EventTrackerSummaryTypeDef,
     FilterSummaryTypeDef,
     GetSolutionMetricsRequestRequestTypeDef,
+    GetSolutionMetricsResponseTypeDef,
     HPOObjectiveTypeDef,
     HPOResourceConfigTypeDef,
     IntegerHyperParameterRangeTypeDef,
-    PaginatorConfigTypeDef,
+    ListBatchInferenceJobsRequestListBatchInferenceJobsPaginateTypeDef,
     ListBatchInferenceJobsRequestRequestTypeDef,
+    ListBatchSegmentJobsRequestListBatchSegmentJobsPaginateTypeDef,
     ListBatchSegmentJobsRequestRequestTypeDef,
+    ListCampaignsRequestListCampaignsPaginateTypeDef,
     ListCampaignsRequestRequestTypeDef,
+    ListDatasetExportJobsRequestListDatasetExportJobsPaginateTypeDef,
     ListDatasetExportJobsRequestRequestTypeDef,
+    ListDatasetGroupsRequestListDatasetGroupsPaginateTypeDef,
     ListDatasetGroupsRequestRequestTypeDef,
+    ListDatasetImportJobsRequestListDatasetImportJobsPaginateTypeDef,
     ListDatasetImportJobsRequestRequestTypeDef,
+    ListDatasetsRequestListDatasetsPaginateTypeDef,
     ListDatasetsRequestRequestTypeDef,
+    ListEventTrackersRequestListEventTrackersPaginateTypeDef,
     ListEventTrackersRequestRequestTypeDef,
+    ListFiltersRequestListFiltersPaginateTypeDef,
     ListFiltersRequestRequestTypeDef,
+    ListMetricAttributionMetricsRequestListMetricAttributionMetricsPaginateTypeDef,
     ListMetricAttributionMetricsRequestRequestTypeDef,
+    ListMetricAttributionsRequestListMetricAttributionsPaginateTypeDef,
     ListMetricAttributionsRequestRequestTypeDef,
     MetricAttributionSummaryTypeDef,
+    ListRecipesRequestListRecipesPaginateTypeDef,
     ListRecipesRequestRequestTypeDef,
     RecipeSummaryTypeDef,
+    ListRecommendersRequestListRecommendersPaginateTypeDef,
     ListRecommendersRequestRequestTypeDef,
+    ListSchemasRequestListSchemasPaginateTypeDef,
     ListSchemasRequestRequestTypeDef,
+    ListSolutionVersionsRequestListSolutionVersionsPaginateTypeDef,
     ListSolutionVersionsRequestRequestTypeDef,
     SolutionVersionSummaryTypeDef,
+    ListSolutionsRequestListSolutionsPaginateTypeDef,
     ListSolutionsRequestRequestTypeDef,
     SolutionSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     OptimizationObjectiveTypeDef,
+    PaginatorConfigTypeDef,
+    TrainingDataConfigTypeDef,
+    ResponseMetadataTypeDef,
     TunedHPOParamsTypeDef,
     StartRecommenderRequestRequestTypeDef,
+    StartRecommenderResponseTypeDef,
     StopRecommenderRequestRequestTypeDef,
+    StopRecommenderResponseTypeDef,
     StopSolutionVersionCreationRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateCampaignResponseTypeDef,
+    UpdateMetricAttributionResponseTypeDef,
+    UpdateRecommenderResponseTypeDef,
     BatchInferenceJobInputTypeDef,
     BatchInferenceJobOutputTypeDef,
     BatchSegmentJobInputTypeDef,
     BatchSegmentJobOutputTypeDef,
     DatasetExportJobOutputTypeDef,
     MetricAttributionOutputTypeDef,
+    ListBatchInferenceJobsResponseTypeDef,
+    ListBatchSegmentJobsResponseTypeDef,
     CampaignUpdateSummaryTypeDef,
     UpdateCampaignRequestRequestTypeDef,
+    ListCampaignsResponseTypeDef,
     CreateCampaignRequestRequestTypeDef,
     CreateDatasetGroupRequestRequestTypeDef,
     CreateDatasetRequestRequestTypeDef,
     CreateEventTrackerRequestRequestTypeDef,
     CreateFilterRequestRequestTypeDef,
     CreateSolutionVersionRequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
-    CreateBatchInferenceJobResponseTypeDef,
-    CreateBatchSegmentJobResponseTypeDef,
-    CreateCampaignResponseTypeDef,
-    CreateDatasetExportJobResponseTypeDef,
-    CreateDatasetGroupResponseTypeDef,
-    CreateDatasetImportJobResponseTypeDef,
-    CreateDatasetResponseTypeDef,
-    CreateEventTrackerResponseTypeDef,
-    CreateFilterResponseTypeDef,
-    CreateMetricAttributionResponseTypeDef,
-    CreateRecommenderResponseTypeDef,
-    CreateSchemaResponseTypeDef,
-    CreateSolutionResponseTypeDef,
-    CreateSolutionVersionResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetSolutionMetricsResponseTypeDef,
-    ListBatchInferenceJobsResponseTypeDef,
-    ListBatchSegmentJobsResponseTypeDef,
-    ListCampaignsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
-    StartRecommenderResponseTypeDef,
-    StopRecommenderResponseTypeDef,
-    UpdateCampaignResponseTypeDef,
-    UpdateMetricAttributionResponseTypeDef,
-    UpdateRecommenderResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
     CreateDatasetImportJobRequestRequestTypeDef,
     DatasetImportJobTypeDef,
     ListMetricAttributionMetricsResponseTypeDef,
-    CreateRecommenderRequestRequestTypeDef,
-    RecommenderSummaryTypeDef,
-    RecommenderUpdateSummaryTypeDef,
-    UpdateRecommenderRequestRequestTypeDef,
     ListDatasetExportJobsResponseTypeDef,
     ListDatasetGroupsResponseTypeDef,
     DescribeDatasetGroupResponseTypeDef,
     ListDatasetImportJobsResponseTypeDef,
     ListSchemasResponseTypeDef,
     DescribeSchemaResponseTypeDef,
     ListDatasetsResponseTypeDef,
@@ -509,60 +521,49 @@
     DescribeEventTrackerResponseTypeDef,
     DescribeFeatureTransformationResponseTypeDef,
     DescribeFilterResponseTypeDef,
     DescribeRecipeResponseTypeDef,
     ListEventTrackersResponseTypeDef,
     ListFiltersResponseTypeDef,
     HyperParameterRangesTypeDef,
-    ListBatchInferenceJobsRequestListBatchInferenceJobsPaginateTypeDef,
-    ListBatchSegmentJobsRequestListBatchSegmentJobsPaginateTypeDef,
-    ListCampaignsRequestListCampaignsPaginateTypeDef,
-    ListDatasetExportJobsRequestListDatasetExportJobsPaginateTypeDef,
-    ListDatasetGroupsRequestListDatasetGroupsPaginateTypeDef,
-    ListDatasetImportJobsRequestListDatasetImportJobsPaginateTypeDef,
-    ListDatasetsRequestListDatasetsPaginateTypeDef,
-    ListEventTrackersRequestListEventTrackersPaginateTypeDef,
-    ListFiltersRequestListFiltersPaginateTypeDef,
-    ListMetricAttributionMetricsRequestListMetricAttributionMetricsPaginateTypeDef,
-    ListMetricAttributionsRequestListMetricAttributionsPaginateTypeDef,
-    ListRecipesRequestListRecipesPaginateTypeDef,
-    ListRecommendersRequestListRecommendersPaginateTypeDef,
-    ListSchemasRequestListSchemasPaginateTypeDef,
-    ListSolutionVersionsRequestListSolutionVersionsPaginateTypeDef,
-    ListSolutionsRequestListSolutionsPaginateTypeDef,
     ListMetricAttributionsResponseTypeDef,
     ListRecipesResponseTypeDef,
     ListSolutionVersionsResponseTypeDef,
     ListSolutionsResponseTypeDef,
+    RecommenderConfigTypeDef,
     BatchInferenceJobTypeDef,
     CreateBatchInferenceJobRequestRequestTypeDef,
     BatchSegmentJobTypeDef,
     CreateBatchSegmentJobRequestRequestTypeDef,
     CreateDatasetExportJobRequestRequestTypeDef,
     DatasetExportJobTypeDef,
     CreateMetricAttributionRequestRequestTypeDef,
     MetricAttributionTypeDef,
     UpdateMetricAttributionRequestRequestTypeDef,
     CampaignTypeDef,
     DescribeDatasetImportJobResponseTypeDef,
-    ListRecommendersResponseTypeDef,
-    RecommenderTypeDef,
     AlgorithmTypeDef,
     HPOConfigTypeDef,
+    CreateRecommenderRequestRequestTypeDef,
+    RecommenderSummaryTypeDef,
+    RecommenderUpdateSummaryTypeDef,
+    UpdateRecommenderRequestRequestTypeDef,
     DescribeBatchInferenceJobResponseTypeDef,
     DescribeBatchSegmentJobResponseTypeDef,
     DescribeDatasetExportJobResponseTypeDef,
     DescribeMetricAttributionResponseTypeDef,
     DescribeCampaignResponseTypeDef,
-    DescribeRecommenderResponseTypeDef,
     DescribeAlgorithmResponseTypeDef,
     SolutionConfigTypeDef,
+    ListRecommendersResponseTypeDef,
+    RecommenderTypeDef,
     CreateSolutionRequestRequestTypeDef,
     SolutionTypeDef,
     SolutionVersionTypeDef,
+    DescribeRecommenderResponseTypeDef,
     DescribeSolutionResponseTypeDef,
     DescribeSolutionVersionResponseTypeDef,
 )
 
 
 def get_structure() -> AlgorithmImageTypeDef:
     return {...}
@@ -571,43 +572,43 @@
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

### Comparing `types-aiobotocore-personalize-2.5.0.post1/setup.py` & `types-aiobotocore-personalize-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-personalize.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-personalize",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_personalize"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Personalize 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.Personalize 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/"
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

### Comparing `types-aiobotocore-personalize-2.5.0.post1/types_aiobotocore_personalize/__init__.py` & `types-aiobotocore-personalize-2.5.1/types_aiobotocore_personalize/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-personalize-2.5.0.post1/types_aiobotocore_personalize/__init__.pyi` & `types-aiobotocore-personalize-2.5.1/types_aiobotocore_personalize/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-personalize-2.5.0.post1/types_aiobotocore_personalize/__main__.py` & `types-aiobotocore-personalize-2.5.1/types_aiobotocore_personalize/__main__.py`

 * *Files 27% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Personalize 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Personalize 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize\nOther"
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

### Comparing `types-aiobotocore-personalize-2.5.0.post1/types_aiobotocore_personalize/client.py` & `types-aiobotocore-personalize-2.5.1/types_aiobotocore_personalize/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -828,15 +828,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/client/#list_solutions)
         """
 
     async def list_tags_for_resource(
         self, *, resourceArn: str
     ) -> ListTagsForResourceResponseTypeDef:
         """
-        Get a list of [tags](https://docs.aws.amazon.com/personalize/latest/dev/tagging-
+        Get a list of [tags](https://docs.aws.amazon.com/personalize/latest/dg/tagging-
         resources.html)_ attached to a resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/client/#list_tags_for_resource)
         """
 
     async def start_recommender(self, *, recommenderArn: str) -> StartRecommenderResponseTypeDef:
@@ -872,15 +872,15 @@
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/client/#tag_resource)
         """
 
     async def untag_resource(self, *, resourceArn: str, tagKeys: Sequence[str]) -> Dict[str, Any]:
         """
-        Remove [tags](https://docs.aws.amazon.com/personalize/latest/dev/tagging-
+        Remove [tags](https://docs.aws.amazon.com/personalize/latest/dg/tagging-
         resources.html)_ that are attached to a resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/client/#untag_resource)
         """
 
     async def update_campaign(
```

### Comparing `types-aiobotocore-personalize-2.5.0.post1/types_aiobotocore_personalize/client.pyi` & `types-aiobotocore-personalize-2.5.1/types_aiobotocore_personalize/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -763,15 +763,15 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Client.list_solutions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/client/#list_solutions)
         """
     async def list_tags_for_resource(
         self, *, resourceArn: str
     ) -> ListTagsForResourceResponseTypeDef:
         """
-        Get a list of [tags](https://docs.aws.amazon.com/personalize/latest/dev/tagging-
+        Get a list of [tags](https://docs.aws.amazon.com/personalize/latest/dg/tagging-
         resources.html)_ attached to a resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/client/#list_tags_for_resource)
         """
     async def start_recommender(self, *, recommenderArn: str) -> StartRecommenderResponseTypeDef:
         """
@@ -802,15 +802,15 @@
         Add a list of tags to a resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/client/#tag_resource)
         """
     async def untag_resource(self, *, resourceArn: str, tagKeys: Sequence[str]) -> Dict[str, Any]:
         """
-        Remove [tags](https://docs.aws.amazon.com/personalize/latest/dev/tagging-
+        Remove [tags](https://docs.aws.amazon.com/personalize/latest/dg/tagging-
         resources.html)_ that are attached to a resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/client/#untag_resource)
         """
     async def update_campaign(
         self,
```

### Comparing `types-aiobotocore-personalize-2.5.0.post1/types_aiobotocore_personalize/literals.py` & `types-aiobotocore-personalize-2.5.1/types_aiobotocore_personalize/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -131,14 +131,15 @@
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
@@ -217,14 +218,15 @@
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
@@ -235,14 +237,15 @@
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
@@ -278,14 +281,15 @@
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
@@ -304,16 +308,19 @@
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
@@ -397,15 +404,17 @@
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

### Comparing `types-aiobotocore-personalize-2.5.0.post1/types_aiobotocore_personalize/literals.pyi` & `types-aiobotocore-personalize-2.5.1/types_aiobotocore_personalize/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -129,14 +129,15 @@
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
@@ -215,14 +216,15 @@
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
@@ -233,14 +235,15 @@
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
@@ -276,14 +279,15 @@
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
@@ -302,16 +306,19 @@
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
@@ -395,15 +402,17 @@
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

### Comparing `types-aiobotocore-personalize-2.5.0.post1/types_aiobotocore_personalize/paginator.py` & `types-aiobotocore-personalize-2.5.1/types_aiobotocore_personalize/paginator.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -47,15 +47,15 @@
         list_recommenders_paginator: ListRecommendersPaginator = client.get_paginator("list_recommenders")
         list_schemas_paginator: ListSchemasPaginator = client.get_paginator("list_schemas")
         list_solution_versions_paginator: ListSolutionVersionsPaginator = client.get_paginator("list_solution_versions")
         list_solutions_paginator: ListSolutionsPaginator = client.get_paginator("list_solutions")
     ```
 """
 import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import DomainType
 from .type_defs import (
     ListBatchInferenceJobsResponseTypeDef,
@@ -73,24 +73,19 @@
     ListRecommendersResponseTypeDef,
     ListSchemasResponseTypeDef,
     ListSolutionsResponseTypeDef,
     ListSolutionVersionsResponseTypeDef,
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
 
-
 __all__ = (
     "ListBatchInferenceJobsPaginator",
     "ListBatchSegmentJobsPaginator",
     "ListCampaignsPaginator",
     "ListDatasetExportJobsPaginator",
     "ListDatasetGroupsPaginator",
     "ListDatasetImportJobsPaginator",
@@ -102,260 +97,242 @@
     "ListRecipesPaginator",
     "ListRecommendersPaginator",
     "ListSchemasPaginator",
     "ListSolutionVersionsPaginator",
     "ListSolutionsPaginator",
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
 class ListBatchInferenceJobsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListBatchInferenceJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listbatchinferencejobspaginator)
     """
 
     def paginate(
-        self, *, solutionVersionArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, solutionVersionArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBatchInferenceJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListBatchInferenceJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listbatchinferencejobspaginator)
         """
 
-
 class ListBatchSegmentJobsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListBatchSegmentJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listbatchsegmentjobspaginator)
     """
 
     def paginate(
-        self, *, solutionVersionArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, solutionVersionArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBatchSegmentJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListBatchSegmentJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listbatchsegmentjobspaginator)
         """
 
-
 class ListCampaignsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListCampaigns)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listcampaignspaginator)
     """
 
     def paginate(
-        self, *, solutionArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, solutionArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCampaignsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListCampaigns.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listcampaignspaginator)
         """
 
-
 class ListDatasetExportJobsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListDatasetExportJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listdatasetexportjobspaginator)
     """
 
     def paginate(
-        self, *, datasetArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, datasetArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDatasetExportJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListDatasetExportJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listdatasetexportjobspaginator)
         """
 
-
 class ListDatasetGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListDatasetGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listdatasetgroupspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDatasetGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListDatasetGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listdatasetgroupspaginator)
         """
 
-
 class ListDatasetImportJobsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListDatasetImportJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listdatasetimportjobspaginator)
     """
 
     def paginate(
-        self, *, datasetArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, datasetArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDatasetImportJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListDatasetImportJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listdatasetimportjobspaginator)
         """
 
-
 class ListDatasetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListDatasets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listdatasetspaginator)
     """
 
     def paginate(
-        self, *, datasetGroupArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, datasetGroupArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDatasetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListDatasets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listdatasetspaginator)
         """
 
-
 class ListEventTrackersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListEventTrackers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listeventtrackerspaginator)
     """
 
     def paginate(
-        self, *, datasetGroupArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, datasetGroupArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEventTrackersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListEventTrackers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listeventtrackerspaginator)
         """
 
-
 class ListFiltersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListFilters)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listfilterspaginator)
     """
 
     def paginate(
-        self, *, datasetGroupArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, datasetGroupArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFiltersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListFilters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listfilterspaginator)
         """
 
-
 class ListMetricAttributionMetricsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListMetricAttributionMetrics)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listmetricattributionmetricspaginator)
     """
 
     def paginate(
-        self, *, metricAttributionArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, metricAttributionArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMetricAttributionMetricsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListMetricAttributionMetrics.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listmetricattributionmetricspaginator)
         """
 
-
 class ListMetricAttributionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListMetricAttributions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listmetricattributionspaginator)
     """
 
     def paginate(
-        self, *, datasetGroupArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, datasetGroupArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMetricAttributionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListMetricAttributions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listmetricattributionspaginator)
         """
 
-
 class ListRecipesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListRecipes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listrecipespaginator)
     """
 
     def paginate(
         self,
         *,
         recipeProvider: Literal["SERVICE"] = ...,
         domain: DomainType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRecipesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListRecipes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listrecipespaginator)
         """
 
-
 class ListRecommendersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListRecommenders)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listrecommenderspaginator)
     """
 
     def paginate(
-        self, *, datasetGroupArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, datasetGroupArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRecommendersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListRecommenders.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listrecommenderspaginator)
         """
 
-
 class ListSchemasPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListSchemas)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listschemaspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSchemasResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListSchemas.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listschemaspaginator)
         """
 
-
 class ListSolutionVersionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListSolutionVersions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listsolutionversionspaginator)
     """
 
     def paginate(
-        self, *, solutionArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, solutionArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSolutionVersionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListSolutionVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listsolutionversionspaginator)
         """
 
-
 class ListSolutionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListSolutions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listsolutionspaginator)
     """
 
     def paginate(
-        self, *, datasetGroupArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, datasetGroupArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSolutionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListSolutions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listsolutionspaginator)
         """
```

### Comparing `types-aiobotocore-personalize-2.5.0.post1/types_aiobotocore_personalize/paginator.pyi` & `types-aiobotocore-personalize-2.5.1/types_aiobotocore_personalize/paginator.py`

 * *Files 4% similar despite different names*

```diff
@@ -47,15 +47,15 @@
         list_recommenders_paginator: ListRecommendersPaginator = client.get_paginator("list_recommenders")
         list_schemas_paginator: ListSchemasPaginator = client.get_paginator("list_schemas")
         list_solution_versions_paginator: ListSolutionVersionsPaginator = client.get_paginator("list_solution_versions")
         list_solutions_paginator: ListSolutionsPaginator = client.get_paginator("list_solutions")
     ```
 """
 import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import DomainType
 from .type_defs import (
     ListBatchInferenceJobsResponseTypeDef,
@@ -73,23 +73,20 @@
     ListRecommendersResponseTypeDef,
     ListSchemasResponseTypeDef,
     ListSolutionsResponseTypeDef,
     ListSolutionVersionsResponseTypeDef,
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
 
+
 __all__ = (
     "ListBatchInferenceJobsPaginator",
     "ListBatchSegmentJobsPaginator",
     "ListCampaignsPaginator",
     "ListDatasetExportJobsPaginator",
     "ListDatasetGroupsPaginator",
     "ListDatasetImportJobsPaginator",
@@ -101,242 +98,260 @@
     "ListRecipesPaginator",
     "ListRecommendersPaginator",
     "ListSchemasPaginator",
     "ListSolutionVersionsPaginator",
     "ListSolutionsPaginator",
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
 class ListBatchInferenceJobsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListBatchInferenceJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listbatchinferencejobspaginator)
     """
 
     def paginate(
-        self, *, solutionVersionArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, solutionVersionArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBatchInferenceJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListBatchInferenceJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listbatchinferencejobspaginator)
         """
 
+
 class ListBatchSegmentJobsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListBatchSegmentJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listbatchsegmentjobspaginator)
     """
 
     def paginate(
-        self, *, solutionVersionArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, solutionVersionArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBatchSegmentJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListBatchSegmentJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listbatchsegmentjobspaginator)
         """
 
+
 class ListCampaignsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListCampaigns)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listcampaignspaginator)
     """
 
     def paginate(
-        self, *, solutionArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, solutionArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCampaignsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListCampaigns.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listcampaignspaginator)
         """
 
+
 class ListDatasetExportJobsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListDatasetExportJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listdatasetexportjobspaginator)
     """
 
     def paginate(
-        self, *, datasetArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, datasetArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDatasetExportJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListDatasetExportJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listdatasetexportjobspaginator)
         """
 
+
 class ListDatasetGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListDatasetGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listdatasetgroupspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDatasetGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListDatasetGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listdatasetgroupspaginator)
         """
 
+
 class ListDatasetImportJobsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListDatasetImportJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listdatasetimportjobspaginator)
     """
 
     def paginate(
-        self, *, datasetArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, datasetArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDatasetImportJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListDatasetImportJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listdatasetimportjobspaginator)
         """
 
+
 class ListDatasetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListDatasets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listdatasetspaginator)
     """
 
     def paginate(
-        self, *, datasetGroupArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, datasetGroupArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDatasetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListDatasets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listdatasetspaginator)
         """
 
+
 class ListEventTrackersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListEventTrackers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listeventtrackerspaginator)
     """
 
     def paginate(
-        self, *, datasetGroupArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, datasetGroupArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEventTrackersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListEventTrackers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listeventtrackerspaginator)
         """
 
+
 class ListFiltersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListFilters)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listfilterspaginator)
     """
 
     def paginate(
-        self, *, datasetGroupArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, datasetGroupArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFiltersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListFilters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listfilterspaginator)
         """
 
+
 class ListMetricAttributionMetricsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListMetricAttributionMetrics)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listmetricattributionmetricspaginator)
     """
 
     def paginate(
-        self, *, metricAttributionArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, metricAttributionArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMetricAttributionMetricsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListMetricAttributionMetrics.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listmetricattributionmetricspaginator)
         """
 
+
 class ListMetricAttributionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListMetricAttributions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listmetricattributionspaginator)
     """
 
     def paginate(
-        self, *, datasetGroupArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, datasetGroupArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMetricAttributionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListMetricAttributions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listmetricattributionspaginator)
         """
 
+
 class ListRecipesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListRecipes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listrecipespaginator)
     """
 
     def paginate(
         self,
         *,
         recipeProvider: Literal["SERVICE"] = ...,
         domain: DomainType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRecipesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListRecipes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listrecipespaginator)
         """
 
+
 class ListRecommendersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListRecommenders)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listrecommenderspaginator)
     """
 
     def paginate(
-        self, *, datasetGroupArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, datasetGroupArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRecommendersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListRecommenders.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listrecommenderspaginator)
         """
 
+
 class ListSchemasPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListSchemas)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listschemaspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSchemasResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListSchemas.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listschemaspaginator)
         """
 
+
 class ListSolutionVersionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListSolutionVersions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listsolutionversionspaginator)
     """
 
     def paginate(
-        self, *, solutionArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, solutionArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSolutionVersionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListSolutionVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listsolutionversionspaginator)
         """
 
+
 class ListSolutionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListSolutions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listsolutionspaginator)
     """
 
     def paginate(
-        self, *, datasetGroupArn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, datasetGroupArn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSolutionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize.Paginator.ListSolutions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/paginators/#listsolutionspaginator)
         """
```

### Comparing `types-aiobotocore-personalize-2.5.0.post1/types_aiobotocore_personalize/type_defs.py` & `types-aiobotocore-personalize-2.5.1/types_aiobotocore_personalize/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -28,33 +28,44 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "AlgorithmImageTypeDef",
     "AutoMLConfigTypeDef",
     "AutoMLResultTypeDef",
     "BatchInferenceJobConfigTypeDef",
     "S3DataConfigTypeDef",
     "BatchInferenceJobSummaryTypeDef",
     "BatchSegmentJobSummaryTypeDef",
     "CampaignConfigTypeDef",
     "CampaignSummaryTypeDef",
     "CategoricalHyperParameterRangeTypeDef",
     "ContinuousHyperParameterRangeTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateBatchInferenceJobResponseTypeDef",
+    "CreateBatchSegmentJobResponseTypeDef",
+    "CreateCampaignResponseTypeDef",
+    "CreateDatasetExportJobResponseTypeDef",
+    "CreateDatasetGroupResponseTypeDef",
     "DataSourceTypeDef",
+    "CreateDatasetImportJobResponseTypeDef",
+    "CreateDatasetResponseTypeDef",
+    "CreateEventTrackerResponseTypeDef",
+    "CreateFilterResponseTypeDef",
     "MetricAttributeTypeDef",
-    "RecommenderConfigTypeDef",
+    "CreateMetricAttributionResponseTypeDef",
+    "CreateRecommenderResponseTypeDef",
     "CreateSchemaRequestRequestTypeDef",
+    "CreateSchemaResponseTypeDef",
+    "CreateSolutionResponseTypeDef",
+    "CreateSolutionVersionResponseTypeDef",
     "DatasetExportJobSummaryTypeDef",
     "DatasetGroupSummaryTypeDef",
     "DatasetGroupTypeDef",
     "DatasetImportJobSummaryTypeDef",
     "DatasetSchemaSummaryTypeDef",
     "DatasetSchemaTypeDef",
     "DatasetSummaryTypeDef",
@@ -88,95 +99,95 @@
     "DescribeMetricAttributionRequestRequestTypeDef",
     "DescribeRecipeRequestRequestTypeDef",
     "RecipeTypeDef",
     "DescribeRecommenderRequestRequestTypeDef",
     "DescribeSchemaRequestRequestTypeDef",
     "DescribeSolutionRequestRequestTypeDef",
     "DescribeSolutionVersionRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EventTrackerSummaryTypeDef",
     "FilterSummaryTypeDef",
     "GetSolutionMetricsRequestRequestTypeDef",
+    "GetSolutionMetricsResponseTypeDef",
     "HPOObjectiveTypeDef",
     "HPOResourceConfigTypeDef",
     "IntegerHyperParameterRangeTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListBatchInferenceJobsRequestListBatchInferenceJobsPaginateTypeDef",
     "ListBatchInferenceJobsRequestRequestTypeDef",
+    "ListBatchSegmentJobsRequestListBatchSegmentJobsPaginateTypeDef",
     "ListBatchSegmentJobsRequestRequestTypeDef",
+    "ListCampaignsRequestListCampaignsPaginateTypeDef",
     "ListCampaignsRequestRequestTypeDef",
+    "ListDatasetExportJobsRequestListDatasetExportJobsPaginateTypeDef",
     "ListDatasetExportJobsRequestRequestTypeDef",
+    "ListDatasetGroupsRequestListDatasetGroupsPaginateTypeDef",
     "ListDatasetGroupsRequestRequestTypeDef",
+    "ListDatasetImportJobsRequestListDatasetImportJobsPaginateTypeDef",
     "ListDatasetImportJobsRequestRequestTypeDef",
+    "ListDatasetsRequestListDatasetsPaginateTypeDef",
     "ListDatasetsRequestRequestTypeDef",
+    "ListEventTrackersRequestListEventTrackersPaginateTypeDef",
     "ListEventTrackersRequestRequestTypeDef",
+    "ListFiltersRequestListFiltersPaginateTypeDef",
     "ListFiltersRequestRequestTypeDef",
+    "ListMetricAttributionMetricsRequestListMetricAttributionMetricsPaginateTypeDef",
     "ListMetricAttributionMetricsRequestRequestTypeDef",
+    "ListMetricAttributionsRequestListMetricAttributionsPaginateTypeDef",
     "ListMetricAttributionsRequestRequestTypeDef",
     "MetricAttributionSummaryTypeDef",
+    "ListRecipesRequestListRecipesPaginateTypeDef",
     "ListRecipesRequestRequestTypeDef",
     "RecipeSummaryTypeDef",
+    "ListRecommendersRequestListRecommendersPaginateTypeDef",
     "ListRecommendersRequestRequestTypeDef",
+    "ListSchemasRequestListSchemasPaginateTypeDef",
     "ListSchemasRequestRequestTypeDef",
+    "ListSolutionVersionsRequestListSolutionVersionsPaginateTypeDef",
     "ListSolutionVersionsRequestRequestTypeDef",
     "SolutionVersionSummaryTypeDef",
+    "ListSolutionsRequestListSolutionsPaginateTypeDef",
     "ListSolutionsRequestRequestTypeDef",
     "SolutionSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "OptimizationObjectiveTypeDef",
+    "PaginatorConfigTypeDef",
+    "TrainingDataConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "TunedHPOParamsTypeDef",
     "StartRecommenderRequestRequestTypeDef",
+    "StartRecommenderResponseTypeDef",
     "StopRecommenderRequestRequestTypeDef",
+    "StopRecommenderResponseTypeDef",
     "StopSolutionVersionCreationRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "UpdateCampaignResponseTypeDef",
+    "UpdateMetricAttributionResponseTypeDef",
+    "UpdateRecommenderResponseTypeDef",
     "BatchInferenceJobInputTypeDef",
     "BatchInferenceJobOutputTypeDef",
     "BatchSegmentJobInputTypeDef",
     "BatchSegmentJobOutputTypeDef",
     "DatasetExportJobOutputTypeDef",
     "MetricAttributionOutputTypeDef",
+    "ListBatchInferenceJobsResponseTypeDef",
+    "ListBatchSegmentJobsResponseTypeDef",
     "CampaignUpdateSummaryTypeDef",
     "UpdateCampaignRequestRequestTypeDef",
+    "ListCampaignsResponseTypeDef",
     "CreateCampaignRequestRequestTypeDef",
     "CreateDatasetGroupRequestRequestTypeDef",
     "CreateDatasetRequestRequestTypeDef",
     "CreateEventTrackerRequestRequestTypeDef",
     "CreateFilterRequestRequestTypeDef",
     "CreateSolutionVersionRequestRequestTypeDef",
-    "TagResourceRequestRequestTypeDef",
-    "CreateBatchInferenceJobResponseTypeDef",
-    "CreateBatchSegmentJobResponseTypeDef",
-    "CreateCampaignResponseTypeDef",
-    "CreateDatasetExportJobResponseTypeDef",
-    "CreateDatasetGroupResponseTypeDef",
-    "CreateDatasetImportJobResponseTypeDef",
-    "CreateDatasetResponseTypeDef",
-    "CreateEventTrackerResponseTypeDef",
-    "CreateFilterResponseTypeDef",
-    "CreateMetricAttributionResponseTypeDef",
-    "CreateRecommenderResponseTypeDef",
-    "CreateSchemaResponseTypeDef",
-    "CreateSolutionResponseTypeDef",
-    "CreateSolutionVersionResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetSolutionMetricsResponseTypeDef",
-    "ListBatchInferenceJobsResponseTypeDef",
-    "ListBatchSegmentJobsResponseTypeDef",
-    "ListCampaignsResponseTypeDef",
     "ListTagsForResourceResponseTypeDef",
-    "StartRecommenderResponseTypeDef",
-    "StopRecommenderResponseTypeDef",
-    "UpdateCampaignResponseTypeDef",
-    "UpdateMetricAttributionResponseTypeDef",
-    "UpdateRecommenderResponseTypeDef",
+    "TagResourceRequestRequestTypeDef",
     "CreateDatasetImportJobRequestRequestTypeDef",
     "DatasetImportJobTypeDef",
     "ListMetricAttributionMetricsResponseTypeDef",
-    "CreateRecommenderRequestRequestTypeDef",
-    "RecommenderSummaryTypeDef",
-    "RecommenderUpdateSummaryTypeDef",
-    "UpdateRecommenderRequestRequestTypeDef",
     "ListDatasetExportJobsResponseTypeDef",
     "ListDatasetGroupsResponseTypeDef",
     "DescribeDatasetGroupResponseTypeDef",
     "ListDatasetImportJobsResponseTypeDef",
     "ListSchemasResponseTypeDef",
     "DescribeSchemaResponseTypeDef",
     "ListDatasetsResponseTypeDef",
@@ -185,60 +196,49 @@
     "DescribeEventTrackerResponseTypeDef",
     "DescribeFeatureTransformationResponseTypeDef",
     "DescribeFilterResponseTypeDef",
     "DescribeRecipeResponseTypeDef",
     "ListEventTrackersResponseTypeDef",
     "ListFiltersResponseTypeDef",
     "HyperParameterRangesTypeDef",
-    "ListBatchInferenceJobsRequestListBatchInferenceJobsPaginateTypeDef",
-    "ListBatchSegmentJobsRequestListBatchSegmentJobsPaginateTypeDef",
-    "ListCampaignsRequestListCampaignsPaginateTypeDef",
-    "ListDatasetExportJobsRequestListDatasetExportJobsPaginateTypeDef",
-    "ListDatasetGroupsRequestListDatasetGroupsPaginateTypeDef",
-    "ListDatasetImportJobsRequestListDatasetImportJobsPaginateTypeDef",
-    "ListDatasetsRequestListDatasetsPaginateTypeDef",
-    "ListEventTrackersRequestListEventTrackersPaginateTypeDef",
-    "ListFiltersRequestListFiltersPaginateTypeDef",
-    "ListMetricAttributionMetricsRequestListMetricAttributionMetricsPaginateTypeDef",
-    "ListMetricAttributionsRequestListMetricAttributionsPaginateTypeDef",
-    "ListRecipesRequestListRecipesPaginateTypeDef",
-    "ListRecommendersRequestListRecommendersPaginateTypeDef",
-    "ListSchemasRequestListSchemasPaginateTypeDef",
-    "ListSolutionVersionsRequestListSolutionVersionsPaginateTypeDef",
-    "ListSolutionsRequestListSolutionsPaginateTypeDef",
     "ListMetricAttributionsResponseTypeDef",
     "ListRecipesResponseTypeDef",
     "ListSolutionVersionsResponseTypeDef",
     "ListSolutionsResponseTypeDef",
+    "RecommenderConfigTypeDef",
     "BatchInferenceJobTypeDef",
     "CreateBatchInferenceJobRequestRequestTypeDef",
     "BatchSegmentJobTypeDef",
     "CreateBatchSegmentJobRequestRequestTypeDef",
     "CreateDatasetExportJobRequestRequestTypeDef",
     "DatasetExportJobTypeDef",
     "CreateMetricAttributionRequestRequestTypeDef",
     "MetricAttributionTypeDef",
     "UpdateMetricAttributionRequestRequestTypeDef",
     "CampaignTypeDef",
     "DescribeDatasetImportJobResponseTypeDef",
-    "ListRecommendersResponseTypeDef",
-    "RecommenderTypeDef",
     "AlgorithmTypeDef",
     "HPOConfigTypeDef",
+    "CreateRecommenderRequestRequestTypeDef",
+    "RecommenderSummaryTypeDef",
+    "RecommenderUpdateSummaryTypeDef",
+    "UpdateRecommenderRequestRequestTypeDef",
     "DescribeBatchInferenceJobResponseTypeDef",
     "DescribeBatchSegmentJobResponseTypeDef",
     "DescribeDatasetExportJobResponseTypeDef",
     "DescribeMetricAttributionResponseTypeDef",
     "DescribeCampaignResponseTypeDef",
-    "DescribeRecommenderResponseTypeDef",
     "DescribeAlgorithmResponseTypeDef",
     "SolutionConfigTypeDef",
+    "ListRecommendersResponseTypeDef",
+    "RecommenderTypeDef",
     "CreateSolutionRequestRequestTypeDef",
     "SolutionTypeDef",
     "SolutionVersionTypeDef",
+    "DescribeRecommenderResponseTypeDef",
     "DescribeSolutionResponseTypeDef",
     "DescribeSolutionVersionResponseTypeDef",
 )
 
 _RequiredAlgorithmImageTypeDef = TypedDict(
     "_RequiredAlgorithmImageTypeDef",
     {
@@ -249,19 +249,17 @@
     "_OptionalAlgorithmImageTypeDef",
     {
         "name": str,
     },
     total=False,
 )
 
-
 class AlgorithmImageTypeDef(_RequiredAlgorithmImageTypeDef, _OptionalAlgorithmImageTypeDef):
     pass
 
-
 AutoMLConfigTypeDef = TypedDict(
     "AutoMLConfigTypeDef",
     {
         "metricName": str,
         "recipeList": Sequence[str],
     },
     total=False,
@@ -293,19 +291,17 @@
     "_OptionalS3DataConfigTypeDef",
     {
         "kmsKeyArn": str,
     },
     total=False,
 )
 
-
 class S3DataConfigTypeDef(_RequiredS3DataConfigTypeDef, _OptionalS3DataConfigTypeDef):
     pass
 
-
 BatchInferenceJobSummaryTypeDef = TypedDict(
     "BatchInferenceJobSummaryTypeDef",
     {
         "batchInferenceJobArn": str,
         "jobName": str,
         "status": str,
         "creationDateTime": datetime,
@@ -374,49 +370,119 @@
     "TagTypeDef",
     {
         "tagKey": str,
         "tagValue": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateBatchInferenceJobResponseTypeDef = TypedDict(
+    "CreateBatchInferenceJobResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "batchInferenceJobArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateBatchSegmentJobResponseTypeDef = TypedDict(
+    "CreateBatchSegmentJobResponseTypeDef",
+    {
+        "batchSegmentJobArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateCampaignResponseTypeDef = TypedDict(
+    "CreateCampaignResponseTypeDef",
+    {
+        "campaignArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateDatasetExportJobResponseTypeDef = TypedDict(
+    "CreateDatasetExportJobResponseTypeDef",
+    {
+        "datasetExportJobArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateDatasetGroupResponseTypeDef = TypedDict(
+    "CreateDatasetGroupResponseTypeDef",
+    {
+        "datasetGroupArn": str,
+        "domain": DomainType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DataSourceTypeDef = TypedDict(
     "DataSourceTypeDef",
     {
         "dataLocation": str,
     },
     total=False,
 )
 
+CreateDatasetImportJobResponseTypeDef = TypedDict(
+    "CreateDatasetImportJobResponseTypeDef",
+    {
+        "datasetImportJobArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateDatasetResponseTypeDef = TypedDict(
+    "CreateDatasetResponseTypeDef",
+    {
+        "datasetArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateEventTrackerResponseTypeDef = TypedDict(
+    "CreateEventTrackerResponseTypeDef",
+    {
+        "eventTrackerArn": str,
+        "trackingId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateFilterResponseTypeDef = TypedDict(
+    "CreateFilterResponseTypeDef",
+    {
+        "filterArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 MetricAttributeTypeDef = TypedDict(
     "MetricAttributeTypeDef",
     {
         "eventType": str,
         "metricName": str,
         "expression": str,
     },
 )
 
-RecommenderConfigTypeDef = TypedDict(
-    "RecommenderConfigTypeDef",
+CreateMetricAttributionResponseTypeDef = TypedDict(
+    "CreateMetricAttributionResponseTypeDef",
     {
-        "itemExplorationConfig": Mapping[str, str],
-        "minRecommendationRequestsPerSecond": int,
+        "metricAttributionArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateRecommenderResponseTypeDef = TypedDict(
+    "CreateRecommenderResponseTypeDef",
+    {
+        "recommenderArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
 _RequiredCreateSchemaRequestRequestTypeDef = TypedDict(
     "_RequiredCreateSchemaRequestRequestTypeDef",
     {
         "name": str,
         "schema": str,
@@ -426,20 +492,42 @@
     "_OptionalCreateSchemaRequestRequestTypeDef",
     {
         "domain": DomainType,
     },
     total=False,
 )
 
-
 class CreateSchemaRequestRequestTypeDef(
     _RequiredCreateSchemaRequestRequestTypeDef, _OptionalCreateSchemaRequestRequestTypeDef
 ):
     pass
 
+CreateSchemaResponseTypeDef = TypedDict(
+    "CreateSchemaResponseTypeDef",
+    {
+        "schemaArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateSolutionResponseTypeDef = TypedDict(
+    "CreateSolutionResponseTypeDef",
+    {
+        "solutionArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateSolutionVersionResponseTypeDef = TypedDict(
+    "CreateSolutionVersionResponseTypeDef",
+    {
+        "solutionVersionArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 DatasetExportJobSummaryTypeDef = TypedDict(
     "DatasetExportJobSummaryTypeDef",
     {
         "datasetExportJobArn": str,
         "jobName": str,
         "status": str,
@@ -816,14 +904,21 @@
 DescribeSolutionVersionRequestRequestTypeDef = TypedDict(
     "DescribeSolutionVersionRequestRequestTypeDef",
     {
         "solutionVersionArn": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EventTrackerSummaryTypeDef = TypedDict(
     "EventTrackerSummaryTypeDef",
     {
         "name": str,
         "eventTrackerArn": str,
         "status": str,
         "creationDateTime": datetime,
@@ -849,14 +944,23 @@
 GetSolutionMetricsRequestRequestTypeDef = TypedDict(
     "GetSolutionMetricsRequestRequestTypeDef",
     {
         "solutionVersionArn": str,
     },
 )
 
+GetSolutionMetricsResponseTypeDef = TypedDict(
+    "GetSolutionMetricsResponseTypeDef",
+    {
+        "solutionVersionArn": str,
+        "metrics": Dict[str, float],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 HPOObjectiveTypeDef = TypedDict(
     "HPOObjectiveTypeDef",
     {
         "type": str,
         "metricName": str,
         "metricRegex": str,
     },
@@ -878,123 +982,211 @@
         "name": str,
         "minValue": int,
         "maxValue": int,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListBatchInferenceJobsRequestListBatchInferenceJobsPaginateTypeDef = TypedDict(
+    "ListBatchInferenceJobsRequestListBatchInferenceJobsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "solutionVersionArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListBatchInferenceJobsRequestRequestTypeDef = TypedDict(
     "ListBatchInferenceJobsRequestRequestTypeDef",
     {
         "solutionVersionArn": str,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListBatchSegmentJobsRequestListBatchSegmentJobsPaginateTypeDef = TypedDict(
+    "ListBatchSegmentJobsRequestListBatchSegmentJobsPaginateTypeDef",
+    {
+        "solutionVersionArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListBatchSegmentJobsRequestRequestTypeDef = TypedDict(
     "ListBatchSegmentJobsRequestRequestTypeDef",
     {
         "solutionVersionArn": str,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListCampaignsRequestListCampaignsPaginateTypeDef = TypedDict(
+    "ListCampaignsRequestListCampaignsPaginateTypeDef",
+    {
+        "solutionArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCampaignsRequestRequestTypeDef = TypedDict(
     "ListCampaignsRequestRequestTypeDef",
     {
         "solutionArn": str,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListDatasetExportJobsRequestListDatasetExportJobsPaginateTypeDef = TypedDict(
+    "ListDatasetExportJobsRequestListDatasetExportJobsPaginateTypeDef",
+    {
+        "datasetArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDatasetExportJobsRequestRequestTypeDef = TypedDict(
     "ListDatasetExportJobsRequestRequestTypeDef",
     {
         "datasetArn": str,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListDatasetGroupsRequestListDatasetGroupsPaginateTypeDef = TypedDict(
+    "ListDatasetGroupsRequestListDatasetGroupsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDatasetGroupsRequestRequestTypeDef = TypedDict(
     "ListDatasetGroupsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListDatasetImportJobsRequestListDatasetImportJobsPaginateTypeDef = TypedDict(
+    "ListDatasetImportJobsRequestListDatasetImportJobsPaginateTypeDef",
+    {
+        "datasetArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDatasetImportJobsRequestRequestTypeDef = TypedDict(
     "ListDatasetImportJobsRequestRequestTypeDef",
     {
         "datasetArn": str,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListDatasetsRequestListDatasetsPaginateTypeDef = TypedDict(
+    "ListDatasetsRequestListDatasetsPaginateTypeDef",
+    {
+        "datasetGroupArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDatasetsRequestRequestTypeDef = TypedDict(
     "ListDatasetsRequestRequestTypeDef",
     {
         "datasetGroupArn": str,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListEventTrackersRequestListEventTrackersPaginateTypeDef = TypedDict(
+    "ListEventTrackersRequestListEventTrackersPaginateTypeDef",
+    {
+        "datasetGroupArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListEventTrackersRequestRequestTypeDef = TypedDict(
     "ListEventTrackersRequestRequestTypeDef",
     {
         "datasetGroupArn": str,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListFiltersRequestListFiltersPaginateTypeDef = TypedDict(
+    "ListFiltersRequestListFiltersPaginateTypeDef",
+    {
+        "datasetGroupArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListFiltersRequestRequestTypeDef = TypedDict(
     "ListFiltersRequestRequestTypeDef",
     {
         "datasetGroupArn": str,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListMetricAttributionMetricsRequestListMetricAttributionMetricsPaginateTypeDef = TypedDict(
+    "ListMetricAttributionMetricsRequestListMetricAttributionMetricsPaginateTypeDef",
+    {
+        "metricAttributionArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListMetricAttributionMetricsRequestRequestTypeDef = TypedDict(
     "ListMetricAttributionMetricsRequestRequestTypeDef",
     {
         "metricAttributionArn": str,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListMetricAttributionsRequestListMetricAttributionsPaginateTypeDef = TypedDict(
+    "ListMetricAttributionsRequestListMetricAttributionsPaginateTypeDef",
+    {
+        "datasetGroupArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListMetricAttributionsRequestRequestTypeDef = TypedDict(
     "ListMetricAttributionsRequestRequestTypeDef",
     {
         "datasetGroupArn": str,
         "nextToken": str,
         "maxResults": int,
     },
@@ -1010,14 +1202,24 @@
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
         "failureReason": str,
     },
     total=False,
 )
 
+ListRecipesRequestListRecipesPaginateTypeDef = TypedDict(
+    "ListRecipesRequestListRecipesPaginateTypeDef",
+    {
+        "recipeProvider": Literal["SERVICE"],
+        "domain": DomainType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListRecipesRequestRequestTypeDef = TypedDict(
     "ListRecipesRequestRequestTypeDef",
     {
         "recipeProvider": Literal["SERVICE"],
         "nextToken": str,
         "maxResults": int,
         "domain": DomainType,
@@ -1034,33 +1236,59 @@
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
         "domain": DomainType,
     },
     total=False,
 )
 
+ListRecommendersRequestListRecommendersPaginateTypeDef = TypedDict(
+    "ListRecommendersRequestListRecommendersPaginateTypeDef",
+    {
+        "datasetGroupArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListRecommendersRequestRequestTypeDef = TypedDict(
     "ListRecommendersRequestRequestTypeDef",
     {
         "datasetGroupArn": str,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListSchemasRequestListSchemasPaginateTypeDef = TypedDict(
+    "ListSchemasRequestListSchemasPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSchemasRequestRequestTypeDef = TypedDict(
     "ListSchemasRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListSolutionVersionsRequestListSolutionVersionsPaginateTypeDef = TypedDict(
+    "ListSolutionVersionsRequestListSolutionVersionsPaginateTypeDef",
+    {
+        "solutionArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSolutionVersionsRequestRequestTypeDef = TypedDict(
     "ListSolutionVersionsRequestRequestTypeDef",
     {
         "solutionArn": str,
         "nextToken": str,
         "maxResults": int,
     },
@@ -1075,14 +1303,23 @@
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
         "failureReason": str,
     },
     total=False,
 )
 
+ListSolutionsRequestListSolutionsPaginateTypeDef = TypedDict(
+    "ListSolutionsRequestListSolutionsPaginateTypeDef",
+    {
+        "datasetGroupArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSolutionsRequestRequestTypeDef = TypedDict(
     "ListSolutionsRequestRequestTypeDef",
     {
         "datasetGroupArn": str,
         "nextToken": str,
         "maxResults": int,
     },
@@ -1114,14 +1351,43 @@
     {
         "itemAttribute": str,
         "objectiveSensitivity": ObjectiveSensitivityType,
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
+TrainingDataConfigTypeDef = TypedDict(
+    "TrainingDataConfigTypeDef",
+    {
+        "excludedDatasetColumns": Mapping[str, Sequence[str]],
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
 TunedHPOParamsTypeDef = TypedDict(
     "TunedHPOParamsTypeDef",
     {
         "algorithmHyperParameters": Dict[str, str],
     },
     total=False,
 )
@@ -1129,21 +1395,37 @@
 StartRecommenderRequestRequestTypeDef = TypedDict(
     "StartRecommenderRequestRequestTypeDef",
     {
         "recommenderArn": str,
     },
 )
 
+StartRecommenderResponseTypeDef = TypedDict(
+    "StartRecommenderResponseTypeDef",
+    {
+        "recommenderArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopRecommenderRequestRequestTypeDef = TypedDict(
     "StopRecommenderRequestRequestTypeDef",
     {
         "recommenderArn": str,
     },
 )
 
+StopRecommenderResponseTypeDef = TypedDict(
+    "StopRecommenderResponseTypeDef",
+    {
+        "recommenderArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopSolutionVersionCreationRequestRequestTypeDef = TypedDict(
     "StopSolutionVersionCreationRequestRequestTypeDef",
     {
         "solutionVersionArn": str,
     },
 )
 
@@ -1151,14 +1433,38 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
 
+UpdateCampaignResponseTypeDef = TypedDict(
+    "UpdateCampaignResponseTypeDef",
+    {
+        "campaignArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateMetricAttributionResponseTypeDef = TypedDict(
+    "UpdateMetricAttributionResponseTypeDef",
+    {
+        "metricAttributionArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateRecommenderResponseTypeDef = TypedDict(
+    "UpdateRecommenderResponseTypeDef",
+    {
+        "recommenderArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 BatchInferenceJobInputTypeDef = TypedDict(
     "BatchInferenceJobInputTypeDef",
     {
         "s3DataSource": S3DataConfigTypeDef,
     },
 )
 
@@ -1200,20 +1506,36 @@
     "_OptionalMetricAttributionOutputTypeDef",
     {
         "s3DataDestination": S3DataConfigTypeDef,
     },
     total=False,
 )
 
-
 class MetricAttributionOutputTypeDef(
     _RequiredMetricAttributionOutputTypeDef, _OptionalMetricAttributionOutputTypeDef
 ):
     pass
 
+ListBatchInferenceJobsResponseTypeDef = TypedDict(
+    "ListBatchInferenceJobsResponseTypeDef",
+    {
+        "batchInferenceJobs": List[BatchInferenceJobSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListBatchSegmentJobsResponseTypeDef = TypedDict(
+    "ListBatchSegmentJobsResponseTypeDef",
+    {
+        "batchSegmentJobs": List[BatchSegmentJobSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 CampaignUpdateSummaryTypeDef = TypedDict(
     "CampaignUpdateSummaryTypeDef",
     {
         "solutionVersionArn": str,
         "minProvisionedTPS": int,
         "campaignConfig": CampaignConfigTypeDef,
@@ -1237,20 +1559,27 @@
         "solutionVersionArn": str,
         "minProvisionedTPS": int,
         "campaignConfig": CampaignConfigTypeDef,
     },
     total=False,
 )
 
-
 class UpdateCampaignRequestRequestTypeDef(
     _RequiredUpdateCampaignRequestRequestTypeDef, _OptionalUpdateCampaignRequestRequestTypeDef
 ):
     pass
 
+ListCampaignsResponseTypeDef = TypedDict(
+    "ListCampaignsResponseTypeDef",
+    {
+        "campaigns": List[CampaignSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredCreateCampaignRequestRequestTypeDef = TypedDict(
     "_RequiredCreateCampaignRequestRequestTypeDef",
     {
         "name": str,
         "solutionVersionArn": str,
     },
@@ -1261,21 +1590,19 @@
         "minProvisionedTPS": int,
         "campaignConfig": CampaignConfigTypeDef,
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateCampaignRequestRequestTypeDef(
     _RequiredCreateCampaignRequestRequestTypeDef, _OptionalCreateCampaignRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredCreateDatasetGroupRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDatasetGroupRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalCreateDatasetGroupRequestRequestTypeDef = TypedDict(
@@ -1285,22 +1612,20 @@
         "kmsKeyArn": str,
         "domain": DomainType,
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateDatasetGroupRequestRequestTypeDef(
     _RequiredCreateDatasetGroupRequestRequestTypeDef,
     _OptionalCreateDatasetGroupRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredCreateDatasetRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDatasetRequestRequestTypeDef",
     {
         "name": str,
         "schemaArn": str,
         "datasetGroupArn": str,
         "datasetType": str,
@@ -1310,21 +1635,19 @@
     "_OptionalCreateDatasetRequestRequestTypeDef",
     {
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateDatasetRequestRequestTypeDef(
     _RequiredCreateDatasetRequestRequestTypeDef, _OptionalCreateDatasetRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredCreateEventTrackerRequestRequestTypeDef = TypedDict(
     "_RequiredCreateEventTrackerRequestRequestTypeDef",
     {
         "name": str,
         "datasetGroupArn": str,
     },
 )
@@ -1332,22 +1655,20 @@
     "_OptionalCreateEventTrackerRequestRequestTypeDef",
     {
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateEventTrackerRequestRequestTypeDef(
     _RequiredCreateEventTrackerRequestRequestTypeDef,
     _OptionalCreateEventTrackerRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredCreateFilterRequestRequestTypeDef = TypedDict(
     "_RequiredCreateFilterRequestRequestTypeDef",
     {
         "name": str,
         "datasetGroupArn": str,
         "filterExpression": str,
     },
@@ -1356,21 +1677,19 @@
     "_OptionalCreateFilterRequestRequestTypeDef",
     {
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateFilterRequestRequestTypeDef(
     _RequiredCreateFilterRequestRequestTypeDef, _OptionalCreateFilterRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredCreateSolutionVersionRequestRequestTypeDef = TypedDict(
     "_RequiredCreateSolutionVersionRequestRequestTypeDef",
     {
         "solutionArn": str,
     },
 )
 _OptionalCreateSolutionVersionRequestRequestTypeDef = TypedDict(
@@ -1379,232 +1698,33 @@
         "name": str,
         "trainingMode": TrainingModeType,
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateSolutionVersionRequestRequestTypeDef(
     _RequiredCreateSolutionVersionRequestRequestTypeDef,
     _OptionalCreateSolutionVersionRequestRequestTypeDef,
 ):
     pass
 
-
-TagResourceRequestRequestTypeDef = TypedDict(
-    "TagResourceRequestRequestTypeDef",
-    {
-        "resourceArn": str,
-        "tags": Sequence[TagTypeDef],
-    },
-)
-
-CreateBatchInferenceJobResponseTypeDef = TypedDict(
-    "CreateBatchInferenceJobResponseTypeDef",
-    {
-        "batchInferenceJobArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateBatchSegmentJobResponseTypeDef = TypedDict(
-    "CreateBatchSegmentJobResponseTypeDef",
-    {
-        "batchSegmentJobArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateCampaignResponseTypeDef = TypedDict(
-    "CreateCampaignResponseTypeDef",
-    {
-        "campaignArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDatasetExportJobResponseTypeDef = TypedDict(
-    "CreateDatasetExportJobResponseTypeDef",
-    {
-        "datasetExportJobArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDatasetGroupResponseTypeDef = TypedDict(
-    "CreateDatasetGroupResponseTypeDef",
-    {
-        "datasetGroupArn": str,
-        "domain": DomainType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDatasetImportJobResponseTypeDef = TypedDict(
-    "CreateDatasetImportJobResponseTypeDef",
-    {
-        "datasetImportJobArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDatasetResponseTypeDef = TypedDict(
-    "CreateDatasetResponseTypeDef",
-    {
-        "datasetArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateEventTrackerResponseTypeDef = TypedDict(
-    "CreateEventTrackerResponseTypeDef",
-    {
-        "eventTrackerArn": str,
-        "trackingId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateFilterResponseTypeDef = TypedDict(
-    "CreateFilterResponseTypeDef",
-    {
-        "filterArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateMetricAttributionResponseTypeDef = TypedDict(
-    "CreateMetricAttributionResponseTypeDef",
-    {
-        "metricAttributionArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateRecommenderResponseTypeDef = TypedDict(
-    "CreateRecommenderResponseTypeDef",
-    {
-        "recommenderArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateSchemaResponseTypeDef = TypedDict(
-    "CreateSchemaResponseTypeDef",
-    {
-        "schemaArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateSolutionResponseTypeDef = TypedDict(
-    "CreateSolutionResponseTypeDef",
-    {
-        "solutionArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateSolutionVersionResponseTypeDef = TypedDict(
-    "CreateSolutionVersionResponseTypeDef",
-    {
-        "solutionVersionArn": str,
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
-GetSolutionMetricsResponseTypeDef = TypedDict(
-    "GetSolutionMetricsResponseTypeDef",
-    {
-        "solutionVersionArn": str,
-        "metrics": Dict[str, float],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListBatchInferenceJobsResponseTypeDef = TypedDict(
-    "ListBatchInferenceJobsResponseTypeDef",
-    {
-        "batchInferenceJobs": List[BatchInferenceJobSummaryTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListBatchSegmentJobsResponseTypeDef = TypedDict(
-    "ListBatchSegmentJobsResponseTypeDef",
-    {
-        "batchSegmentJobs": List[BatchSegmentJobSummaryTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListCampaignsResponseTypeDef = TypedDict(
-    "ListCampaignsResponseTypeDef",
-    {
-        "campaigns": List[CampaignSummaryTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartRecommenderResponseTypeDef = TypedDict(
-    "StartRecommenderResponseTypeDef",
-    {
-        "recommenderArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StopRecommenderResponseTypeDef = TypedDict(
-    "StopRecommenderResponseTypeDef",
-    {
-        "recommenderArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateCampaignResponseTypeDef = TypedDict(
-    "UpdateCampaignResponseTypeDef",
-    {
-        "campaignArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateMetricAttributionResponseTypeDef = TypedDict(
-    "UpdateMetricAttributionResponseTypeDef",
-    {
-        "metricAttributionArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateRecommenderResponseTypeDef = TypedDict(
-    "UpdateRecommenderResponseTypeDef",
+TagResourceRequestRequestTypeDef = TypedDict(
+    "TagResourceRequestRequestTypeDef",
     {
-        "recommenderArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "resourceArn": str,
+        "tags": Sequence[TagTypeDef],
     },
 )
 
 _RequiredCreateDatasetImportJobRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDatasetImportJobRequestRequestTypeDef",
     {
         "jobName": str,
@@ -1619,22 +1739,20 @@
         "tags": Sequence[TagTypeDef],
         "importMode": ImportModeType,
         "publishAttributionMetricsToS3": bool,
     },
     total=False,
 )
 
-
 class CreateDatasetImportJobRequestRequestTypeDef(
     _RequiredCreateDatasetImportJobRequestRequestTypeDef,
     _OptionalCreateDatasetImportJobRequestRequestTypeDef,
 ):
     pass
 
-
 DatasetImportJobTypeDef = TypedDict(
     "DatasetImportJobTypeDef",
     {
         "jobName": str,
         "datasetImportJobArn": str,
         "datasetArn": str,
         "dataSource": DataSourceTypeDef,
@@ -1650,143 +1768,84 @@
 )
 
 ListMetricAttributionMetricsResponseTypeDef = TypedDict(
     "ListMetricAttributionMetricsResponseTypeDef",
     {
         "metrics": List[MetricAttributeTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredCreateRecommenderRequestRequestTypeDef = TypedDict(
-    "_RequiredCreateRecommenderRequestRequestTypeDef",
-    {
-        "name": str,
-        "datasetGroupArn": str,
-        "recipeArn": str,
-    },
-)
-_OptionalCreateRecommenderRequestRequestTypeDef = TypedDict(
-    "_OptionalCreateRecommenderRequestRequestTypeDef",
-    {
-        "recommenderConfig": RecommenderConfigTypeDef,
-        "tags": Sequence[TagTypeDef],
-    },
-    total=False,
-)
-
-
-class CreateRecommenderRequestRequestTypeDef(
-    _RequiredCreateRecommenderRequestRequestTypeDef, _OptionalCreateRecommenderRequestRequestTypeDef
-):
-    pass
-
-
-RecommenderSummaryTypeDef = TypedDict(
-    "RecommenderSummaryTypeDef",
-    {
-        "name": str,
-        "recommenderArn": str,
-        "datasetGroupArn": str,
-        "recipeArn": str,
-        "recommenderConfig": RecommenderConfigTypeDef,
-        "status": str,
-        "creationDateTime": datetime,
-        "lastUpdatedDateTime": datetime,
-    },
-    total=False,
-)
-
-RecommenderUpdateSummaryTypeDef = TypedDict(
-    "RecommenderUpdateSummaryTypeDef",
-    {
-        "recommenderConfig": RecommenderConfigTypeDef,
-        "creationDateTime": datetime,
-        "lastUpdatedDateTime": datetime,
-        "status": str,
-        "failureReason": str,
-    },
-    total=False,
-)
-
-UpdateRecommenderRequestRequestTypeDef = TypedDict(
-    "UpdateRecommenderRequestRequestTypeDef",
-    {
-        "recommenderArn": str,
-        "recommenderConfig": RecommenderConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDatasetExportJobsResponseTypeDef = TypedDict(
     "ListDatasetExportJobsResponseTypeDef",
     {
         "datasetExportJobs": List[DatasetExportJobSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDatasetGroupsResponseTypeDef = TypedDict(
     "ListDatasetGroupsResponseTypeDef",
     {
         "datasetGroups": List[DatasetGroupSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDatasetGroupResponseTypeDef = TypedDict(
     "DescribeDatasetGroupResponseTypeDef",
     {
         "datasetGroup": DatasetGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDatasetImportJobsResponseTypeDef = TypedDict(
     "ListDatasetImportJobsResponseTypeDef",
     {
         "datasetImportJobs": List[DatasetImportJobSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSchemasResponseTypeDef = TypedDict(
     "ListSchemasResponseTypeDef",
     {
         "schemas": List[DatasetSchemaSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSchemaResponseTypeDef = TypedDict(
     "DescribeSchemaResponseTypeDef",
     {
         "schema": DatasetSchemaTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDatasetsResponseTypeDef = TypedDict(
     "ListDatasetsResponseTypeDef",
     {
         "datasets": List[DatasetSummaryTypeDef],
         "nextToken": str,
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
 
 DefaultHyperParameterRangesTypeDef = TypedDict(
     "DefaultHyperParameterRangesTypeDef",
     {
         "integerHyperParameterRanges": List[DefaultIntegerHyperParameterRangeTypeDef],
@@ -1796,247 +1855,114 @@
     total=False,
 )
 
 DescribeEventTrackerResponseTypeDef = TypedDict(
     "DescribeEventTrackerResponseTypeDef",
     {
         "eventTracker": EventTrackerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFeatureTransformationResponseTypeDef = TypedDict(
     "DescribeFeatureTransformationResponseTypeDef",
     {
         "featureTransformation": FeatureTransformationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFilterResponseTypeDef = TypedDict(
     "DescribeFilterResponseTypeDef",
     {
         "filter": FilterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeRecipeResponseTypeDef = TypedDict(
     "DescribeRecipeResponseTypeDef",
     {
         "recipe": RecipeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEventTrackersResponseTypeDef = TypedDict(
     "ListEventTrackersResponseTypeDef",
     {
         "eventTrackers": List[EventTrackerSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListFiltersResponseTypeDef = TypedDict(
     "ListFiltersResponseTypeDef",
     {
         "Filters": List[FilterSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 HyperParameterRangesTypeDef = TypedDict(
     "HyperParameterRangesTypeDef",
     {
         "integerHyperParameterRanges": Sequence[IntegerHyperParameterRangeTypeDef],
         "continuousHyperParameterRanges": Sequence[ContinuousHyperParameterRangeTypeDef],
         "categoricalHyperParameterRanges": Sequence[CategoricalHyperParameterRangeTypeDef],
     },
     total=False,
 )
 
-ListBatchInferenceJobsRequestListBatchInferenceJobsPaginateTypeDef = TypedDict(
-    "ListBatchInferenceJobsRequestListBatchInferenceJobsPaginateTypeDef",
-    {
-        "solutionVersionArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListBatchSegmentJobsRequestListBatchSegmentJobsPaginateTypeDef = TypedDict(
-    "ListBatchSegmentJobsRequestListBatchSegmentJobsPaginateTypeDef",
-    {
-        "solutionVersionArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListCampaignsRequestListCampaignsPaginateTypeDef = TypedDict(
-    "ListCampaignsRequestListCampaignsPaginateTypeDef",
-    {
-        "solutionArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListDatasetExportJobsRequestListDatasetExportJobsPaginateTypeDef = TypedDict(
-    "ListDatasetExportJobsRequestListDatasetExportJobsPaginateTypeDef",
-    {
-        "datasetArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListDatasetGroupsRequestListDatasetGroupsPaginateTypeDef = TypedDict(
-    "ListDatasetGroupsRequestListDatasetGroupsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListDatasetImportJobsRequestListDatasetImportJobsPaginateTypeDef = TypedDict(
-    "ListDatasetImportJobsRequestListDatasetImportJobsPaginateTypeDef",
-    {
-        "datasetArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListDatasetsRequestListDatasetsPaginateTypeDef = TypedDict(
-    "ListDatasetsRequestListDatasetsPaginateTypeDef",
-    {
-        "datasetGroupArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListEventTrackersRequestListEventTrackersPaginateTypeDef = TypedDict(
-    "ListEventTrackersRequestListEventTrackersPaginateTypeDef",
-    {
-        "datasetGroupArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListFiltersRequestListFiltersPaginateTypeDef = TypedDict(
-    "ListFiltersRequestListFiltersPaginateTypeDef",
-    {
-        "datasetGroupArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListMetricAttributionMetricsRequestListMetricAttributionMetricsPaginateTypeDef = TypedDict(
-    "ListMetricAttributionMetricsRequestListMetricAttributionMetricsPaginateTypeDef",
-    {
-        "metricAttributionArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListMetricAttributionsRequestListMetricAttributionsPaginateTypeDef = TypedDict(
-    "ListMetricAttributionsRequestListMetricAttributionsPaginateTypeDef",
-    {
-        "datasetGroupArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListRecipesRequestListRecipesPaginateTypeDef = TypedDict(
-    "ListRecipesRequestListRecipesPaginateTypeDef",
-    {
-        "recipeProvider": Literal["SERVICE"],
-        "domain": DomainType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListRecommendersRequestListRecommendersPaginateTypeDef = TypedDict(
-    "ListRecommendersRequestListRecommendersPaginateTypeDef",
-    {
-        "datasetGroupArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListSchemasRequestListSchemasPaginateTypeDef = TypedDict(
-    "ListSchemasRequestListSchemasPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListSolutionVersionsRequestListSolutionVersionsPaginateTypeDef = TypedDict(
-    "ListSolutionVersionsRequestListSolutionVersionsPaginateTypeDef",
-    {
-        "solutionArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListSolutionsRequestListSolutionsPaginateTypeDef = TypedDict(
-    "ListSolutionsRequestListSolutionsPaginateTypeDef",
-    {
-        "datasetGroupArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListMetricAttributionsResponseTypeDef = TypedDict(
     "ListMetricAttributionsResponseTypeDef",
     {
         "metricAttributions": List[MetricAttributionSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRecipesResponseTypeDef = TypedDict(
     "ListRecipesResponseTypeDef",
     {
         "recipes": List[RecipeSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSolutionVersionsResponseTypeDef = TypedDict(
     "ListSolutionVersionsResponseTypeDef",
     {
         "solutionVersions": List[SolutionVersionSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSolutionsResponseTypeDef = TypedDict(
     "ListSolutionsResponseTypeDef",
     {
         "solutions": List[SolutionSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+RecommenderConfigTypeDef = TypedDict(
+    "RecommenderConfigTypeDef",
+    {
+        "itemExplorationConfig": Mapping[str, str],
+        "minRecommendationRequestsPerSecond": int,
+        "trainingDataConfig": TrainingDataConfigTypeDef,
     },
+    total=False,
 )
 
 BatchInferenceJobTypeDef = TypedDict(
     "BatchInferenceJobTypeDef",
     {
         "jobName": str,
         "batchInferenceJobArn": str,
@@ -2072,22 +1998,20 @@
         "numResults": int,
         "batchInferenceJobConfig": BatchInferenceJobConfigTypeDef,
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateBatchInferenceJobRequestRequestTypeDef(
     _RequiredCreateBatchInferenceJobRequestRequestTypeDef,
     _OptionalCreateBatchInferenceJobRequestRequestTypeDef,
 ):
     pass
 
-
 BatchSegmentJobTypeDef = TypedDict(
     "BatchSegmentJobTypeDef",
     {
         "jobName": str,
         "batchSegmentJobArn": str,
         "filterArn": str,
         "failureReason": str,
@@ -2119,22 +2043,20 @@
         "filterArn": str,
         "numResults": int,
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateBatchSegmentJobRequestRequestTypeDef(
     _RequiredCreateBatchSegmentJobRequestRequestTypeDef,
     _OptionalCreateBatchSegmentJobRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredCreateDatasetExportJobRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDatasetExportJobRequestRequestTypeDef",
     {
         "jobName": str,
         "datasetArn": str,
         "roleArn": str,
         "jobOutput": DatasetExportJobOutputTypeDef,
@@ -2145,22 +2067,20 @@
     {
         "ingestionMode": IngestionModeType,
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateDatasetExportJobRequestRequestTypeDef(
     _RequiredCreateDatasetExportJobRequestRequestTypeDef,
     _OptionalCreateDatasetExportJobRequestRequestTypeDef,
 ):
     pass
 
-
 DatasetExportJobTypeDef = TypedDict(
     "DatasetExportJobTypeDef",
     {
         "jobName": str,
         "datasetExportJobArn": str,
         "datasetArn": str,
         "ingestionMode": IngestionModeType,
@@ -2227,45 +2147,18 @@
     total=False,
 )
 
 DescribeDatasetImportJobResponseTypeDef = TypedDict(
     "DescribeDatasetImportJobResponseTypeDef",
     {
         "datasetImportJob": DatasetImportJobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListRecommendersResponseTypeDef = TypedDict(
-    "ListRecommendersResponseTypeDef",
-    {
-        "recommenders": List[RecommenderSummaryTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RecommenderTypeDef = TypedDict(
-    "RecommenderTypeDef",
-    {
-        "recommenderArn": str,
-        "datasetGroupArn": str,
-        "name": str,
-        "recipeArn": str,
-        "recommenderConfig": RecommenderConfigTypeDef,
-        "creationDateTime": datetime,
-        "lastUpdatedDateTime": datetime,
-        "status": str,
-        "failureReason": str,
-        "latestRecommenderUpdate": RecommenderUpdateSummaryTypeDef,
-        "modelMetrics": Dict[str, float],
-    },
-    total=False,
-)
-
 AlgorithmTypeDef = TypedDict(
     "AlgorithmTypeDef",
     {
         "name": str,
         "algorithmArn": str,
         "algorithmImage": AlgorithmImageTypeDef,
         "defaultHyperParameters": Dict[str, str],
@@ -2285,79 +2178,156 @@
         "hpoObjective": HPOObjectiveTypeDef,
         "hpoResourceConfig": HPOResourceConfigTypeDef,
         "algorithmHyperParameterRanges": HyperParameterRangesTypeDef,
     },
     total=False,
 )
 
+_RequiredCreateRecommenderRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateRecommenderRequestRequestTypeDef",
+    {
+        "name": str,
+        "datasetGroupArn": str,
+        "recipeArn": str,
+    },
+)
+_OptionalCreateRecommenderRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateRecommenderRequestRequestTypeDef",
+    {
+        "recommenderConfig": RecommenderConfigTypeDef,
+        "tags": Sequence[TagTypeDef],
+    },
+    total=False,
+)
+
+class CreateRecommenderRequestRequestTypeDef(
+    _RequiredCreateRecommenderRequestRequestTypeDef, _OptionalCreateRecommenderRequestRequestTypeDef
+):
+    pass
+
+RecommenderSummaryTypeDef = TypedDict(
+    "RecommenderSummaryTypeDef",
+    {
+        "name": str,
+        "recommenderArn": str,
+        "datasetGroupArn": str,
+        "recipeArn": str,
+        "recommenderConfig": RecommenderConfigTypeDef,
+        "status": str,
+        "creationDateTime": datetime,
+        "lastUpdatedDateTime": datetime,
+    },
+    total=False,
+)
+
+RecommenderUpdateSummaryTypeDef = TypedDict(
+    "RecommenderUpdateSummaryTypeDef",
+    {
+        "recommenderConfig": RecommenderConfigTypeDef,
+        "creationDateTime": datetime,
+        "lastUpdatedDateTime": datetime,
+        "status": str,
+        "failureReason": str,
+    },
+    total=False,
+)
+
+UpdateRecommenderRequestRequestTypeDef = TypedDict(
+    "UpdateRecommenderRequestRequestTypeDef",
+    {
+        "recommenderArn": str,
+        "recommenderConfig": RecommenderConfigTypeDef,
+    },
+)
+
 DescribeBatchInferenceJobResponseTypeDef = TypedDict(
     "DescribeBatchInferenceJobResponseTypeDef",
     {
         "batchInferenceJob": BatchInferenceJobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeBatchSegmentJobResponseTypeDef = TypedDict(
     "DescribeBatchSegmentJobResponseTypeDef",
     {
         "batchSegmentJob": BatchSegmentJobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDatasetExportJobResponseTypeDef = TypedDict(
     "DescribeDatasetExportJobResponseTypeDef",
     {
         "datasetExportJob": DatasetExportJobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeMetricAttributionResponseTypeDef = TypedDict(
     "DescribeMetricAttributionResponseTypeDef",
     {
         "metricAttribution": MetricAttributionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeCampaignResponseTypeDef = TypedDict(
     "DescribeCampaignResponseTypeDef",
     {
         "campaign": CampaignTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeRecommenderResponseTypeDef = TypedDict(
-    "DescribeRecommenderResponseTypeDef",
-    {
-        "recommender": RecommenderTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAlgorithmResponseTypeDef = TypedDict(
     "DescribeAlgorithmResponseTypeDef",
     {
         "algorithm": AlgorithmTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SolutionConfigTypeDef = TypedDict(
     "SolutionConfigTypeDef",
     {
         "eventValueThreshold": str,
         "hpoConfig": HPOConfigTypeDef,
         "algorithmHyperParameters": Mapping[str, str],
         "featureTransformationParameters": Mapping[str, str],
         "autoMLConfig": AutoMLConfigTypeDef,
         "optimizationObjective": OptimizationObjectiveTypeDef,
+        "trainingDataConfig": TrainingDataConfigTypeDef,
+    },
+    total=False,
+)
+
+ListRecommendersResponseTypeDef = TypedDict(
+    "ListRecommendersResponseTypeDef",
+    {
+        "recommenders": List[RecommenderSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+RecommenderTypeDef = TypedDict(
+    "RecommenderTypeDef",
+    {
+        "recommenderArn": str,
+        "datasetGroupArn": str,
+        "name": str,
+        "recipeArn": str,
+        "recommenderConfig": RecommenderConfigTypeDef,
+        "creationDateTime": datetime,
+        "lastUpdatedDateTime": datetime,
+        "status": str,
+        "failureReason": str,
+        "latestRecommenderUpdate": RecommenderUpdateSummaryTypeDef,
+        "modelMetrics": Dict[str, float],
     },
     total=False,
 )
 
 _RequiredCreateSolutionRequestRequestTypeDef = TypedDict(
     "_RequiredCreateSolutionRequestRequestTypeDef",
     {
@@ -2374,21 +2344,19 @@
         "eventType": str,
         "solutionConfig": SolutionConfigTypeDef,
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateSolutionRequestRequestTypeDef(
     _RequiredCreateSolutionRequestRequestTypeDef, _OptionalCreateSolutionRequestRequestTypeDef
 ):
     pass
 
-
 SolutionTypeDef = TypedDict(
     "SolutionTypeDef",
     {
         "name": str,
         "solutionArn": str,
         "performHPO": bool,
         "performAutoML": bool,
@@ -2424,22 +2392,30 @@
         "failureReason": str,
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
     },
     total=False,
 )
 
+DescribeRecommenderResponseTypeDef = TypedDict(
+    "DescribeRecommenderResponseTypeDef",
+    {
+        "recommender": RecommenderTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeSolutionResponseTypeDef = TypedDict(
     "DescribeSolutionResponseTypeDef",
     {
         "solution": SolutionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSolutionVersionResponseTypeDef = TypedDict(
     "DescribeSolutionVersionResponseTypeDef",
     {
         "solutionVersion": SolutionVersionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-personalize-2.5.0.post1/types_aiobotocore_personalize/type_defs.pyi` & `types-aiobotocore-personalize-2.5.1/types_aiobotocore_personalize/type_defs.py`

 * *Files 4% similar despite different names*

```diff
@@ -28,32 +28,45 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "AlgorithmImageTypeDef",
     "AutoMLConfigTypeDef",
     "AutoMLResultTypeDef",
     "BatchInferenceJobConfigTypeDef",
     "S3DataConfigTypeDef",
     "BatchInferenceJobSummaryTypeDef",
     "BatchSegmentJobSummaryTypeDef",
     "CampaignConfigTypeDef",
     "CampaignSummaryTypeDef",
     "CategoricalHyperParameterRangeTypeDef",
     "ContinuousHyperParameterRangeTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateBatchInferenceJobResponseTypeDef",
+    "CreateBatchSegmentJobResponseTypeDef",
+    "CreateCampaignResponseTypeDef",
+    "CreateDatasetExportJobResponseTypeDef",
+    "CreateDatasetGroupResponseTypeDef",
     "DataSourceTypeDef",
+    "CreateDatasetImportJobResponseTypeDef",
+    "CreateDatasetResponseTypeDef",
+    "CreateEventTrackerResponseTypeDef",
+    "CreateFilterResponseTypeDef",
     "MetricAttributeTypeDef",
-    "RecommenderConfigTypeDef",
+    "CreateMetricAttributionResponseTypeDef",
+    "CreateRecommenderResponseTypeDef",
     "CreateSchemaRequestRequestTypeDef",
+    "CreateSchemaResponseTypeDef",
+    "CreateSolutionResponseTypeDef",
+    "CreateSolutionVersionResponseTypeDef",
     "DatasetExportJobSummaryTypeDef",
     "DatasetGroupSummaryTypeDef",
     "DatasetGroupTypeDef",
     "DatasetImportJobSummaryTypeDef",
     "DatasetSchemaSummaryTypeDef",
     "DatasetSchemaTypeDef",
     "DatasetSummaryTypeDef",
@@ -87,95 +100,95 @@
     "DescribeMetricAttributionRequestRequestTypeDef",
     "DescribeRecipeRequestRequestTypeDef",
     "RecipeTypeDef",
     "DescribeRecommenderRequestRequestTypeDef",
     "DescribeSchemaRequestRequestTypeDef",
     "DescribeSolutionRequestRequestTypeDef",
     "DescribeSolutionVersionRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EventTrackerSummaryTypeDef",
     "FilterSummaryTypeDef",
     "GetSolutionMetricsRequestRequestTypeDef",
+    "GetSolutionMetricsResponseTypeDef",
     "HPOObjectiveTypeDef",
     "HPOResourceConfigTypeDef",
     "IntegerHyperParameterRangeTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListBatchInferenceJobsRequestListBatchInferenceJobsPaginateTypeDef",
     "ListBatchInferenceJobsRequestRequestTypeDef",
+    "ListBatchSegmentJobsRequestListBatchSegmentJobsPaginateTypeDef",
     "ListBatchSegmentJobsRequestRequestTypeDef",
+    "ListCampaignsRequestListCampaignsPaginateTypeDef",
     "ListCampaignsRequestRequestTypeDef",
+    "ListDatasetExportJobsRequestListDatasetExportJobsPaginateTypeDef",
     "ListDatasetExportJobsRequestRequestTypeDef",
+    "ListDatasetGroupsRequestListDatasetGroupsPaginateTypeDef",
     "ListDatasetGroupsRequestRequestTypeDef",
+    "ListDatasetImportJobsRequestListDatasetImportJobsPaginateTypeDef",
     "ListDatasetImportJobsRequestRequestTypeDef",
+    "ListDatasetsRequestListDatasetsPaginateTypeDef",
     "ListDatasetsRequestRequestTypeDef",
+    "ListEventTrackersRequestListEventTrackersPaginateTypeDef",
     "ListEventTrackersRequestRequestTypeDef",
+    "ListFiltersRequestListFiltersPaginateTypeDef",
     "ListFiltersRequestRequestTypeDef",
+    "ListMetricAttributionMetricsRequestListMetricAttributionMetricsPaginateTypeDef",
     "ListMetricAttributionMetricsRequestRequestTypeDef",
+    "ListMetricAttributionsRequestListMetricAttributionsPaginateTypeDef",
     "ListMetricAttributionsRequestRequestTypeDef",
     "MetricAttributionSummaryTypeDef",
+    "ListRecipesRequestListRecipesPaginateTypeDef",
     "ListRecipesRequestRequestTypeDef",
     "RecipeSummaryTypeDef",
+    "ListRecommendersRequestListRecommendersPaginateTypeDef",
     "ListRecommendersRequestRequestTypeDef",
+    "ListSchemasRequestListSchemasPaginateTypeDef",
     "ListSchemasRequestRequestTypeDef",
+    "ListSolutionVersionsRequestListSolutionVersionsPaginateTypeDef",
     "ListSolutionVersionsRequestRequestTypeDef",
     "SolutionVersionSummaryTypeDef",
+    "ListSolutionsRequestListSolutionsPaginateTypeDef",
     "ListSolutionsRequestRequestTypeDef",
     "SolutionSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "OptimizationObjectiveTypeDef",
+    "PaginatorConfigTypeDef",
+    "TrainingDataConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "TunedHPOParamsTypeDef",
     "StartRecommenderRequestRequestTypeDef",
+    "StartRecommenderResponseTypeDef",
     "StopRecommenderRequestRequestTypeDef",
+    "StopRecommenderResponseTypeDef",
     "StopSolutionVersionCreationRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "UpdateCampaignResponseTypeDef",
+    "UpdateMetricAttributionResponseTypeDef",
+    "UpdateRecommenderResponseTypeDef",
     "BatchInferenceJobInputTypeDef",
     "BatchInferenceJobOutputTypeDef",
     "BatchSegmentJobInputTypeDef",
     "BatchSegmentJobOutputTypeDef",
     "DatasetExportJobOutputTypeDef",
     "MetricAttributionOutputTypeDef",
+    "ListBatchInferenceJobsResponseTypeDef",
+    "ListBatchSegmentJobsResponseTypeDef",
     "CampaignUpdateSummaryTypeDef",
     "UpdateCampaignRequestRequestTypeDef",
+    "ListCampaignsResponseTypeDef",
     "CreateCampaignRequestRequestTypeDef",
     "CreateDatasetGroupRequestRequestTypeDef",
     "CreateDatasetRequestRequestTypeDef",
     "CreateEventTrackerRequestRequestTypeDef",
     "CreateFilterRequestRequestTypeDef",
     "CreateSolutionVersionRequestRequestTypeDef",
-    "TagResourceRequestRequestTypeDef",
-    "CreateBatchInferenceJobResponseTypeDef",
-    "CreateBatchSegmentJobResponseTypeDef",
-    "CreateCampaignResponseTypeDef",
-    "CreateDatasetExportJobResponseTypeDef",
-    "CreateDatasetGroupResponseTypeDef",
-    "CreateDatasetImportJobResponseTypeDef",
-    "CreateDatasetResponseTypeDef",
-    "CreateEventTrackerResponseTypeDef",
-    "CreateFilterResponseTypeDef",
-    "CreateMetricAttributionResponseTypeDef",
-    "CreateRecommenderResponseTypeDef",
-    "CreateSchemaResponseTypeDef",
-    "CreateSolutionResponseTypeDef",
-    "CreateSolutionVersionResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetSolutionMetricsResponseTypeDef",
-    "ListBatchInferenceJobsResponseTypeDef",
-    "ListBatchSegmentJobsResponseTypeDef",
-    "ListCampaignsResponseTypeDef",
     "ListTagsForResourceResponseTypeDef",
-    "StartRecommenderResponseTypeDef",
-    "StopRecommenderResponseTypeDef",
-    "UpdateCampaignResponseTypeDef",
-    "UpdateMetricAttributionResponseTypeDef",
-    "UpdateRecommenderResponseTypeDef",
+    "TagResourceRequestRequestTypeDef",
     "CreateDatasetImportJobRequestRequestTypeDef",
     "DatasetImportJobTypeDef",
     "ListMetricAttributionMetricsResponseTypeDef",
-    "CreateRecommenderRequestRequestTypeDef",
-    "RecommenderSummaryTypeDef",
-    "RecommenderUpdateSummaryTypeDef",
-    "UpdateRecommenderRequestRequestTypeDef",
     "ListDatasetExportJobsResponseTypeDef",
     "ListDatasetGroupsResponseTypeDef",
     "DescribeDatasetGroupResponseTypeDef",
     "ListDatasetImportJobsResponseTypeDef",
     "ListSchemasResponseTypeDef",
     "DescribeSchemaResponseTypeDef",
     "ListDatasetsResponseTypeDef",
@@ -184,60 +197,49 @@
     "DescribeEventTrackerResponseTypeDef",
     "DescribeFeatureTransformationResponseTypeDef",
     "DescribeFilterResponseTypeDef",
     "DescribeRecipeResponseTypeDef",
     "ListEventTrackersResponseTypeDef",
     "ListFiltersResponseTypeDef",
     "HyperParameterRangesTypeDef",
-    "ListBatchInferenceJobsRequestListBatchInferenceJobsPaginateTypeDef",
-    "ListBatchSegmentJobsRequestListBatchSegmentJobsPaginateTypeDef",
-    "ListCampaignsRequestListCampaignsPaginateTypeDef",
-    "ListDatasetExportJobsRequestListDatasetExportJobsPaginateTypeDef",
-    "ListDatasetGroupsRequestListDatasetGroupsPaginateTypeDef",
-    "ListDatasetImportJobsRequestListDatasetImportJobsPaginateTypeDef",
-    "ListDatasetsRequestListDatasetsPaginateTypeDef",
-    "ListEventTrackersRequestListEventTrackersPaginateTypeDef",
-    "ListFiltersRequestListFiltersPaginateTypeDef",
-    "ListMetricAttributionMetricsRequestListMetricAttributionMetricsPaginateTypeDef",
-    "ListMetricAttributionsRequestListMetricAttributionsPaginateTypeDef",
-    "ListRecipesRequestListRecipesPaginateTypeDef",
-    "ListRecommendersRequestListRecommendersPaginateTypeDef",
-    "ListSchemasRequestListSchemasPaginateTypeDef",
-    "ListSolutionVersionsRequestListSolutionVersionsPaginateTypeDef",
-    "ListSolutionsRequestListSolutionsPaginateTypeDef",
     "ListMetricAttributionsResponseTypeDef",
     "ListRecipesResponseTypeDef",
     "ListSolutionVersionsResponseTypeDef",
     "ListSolutionsResponseTypeDef",
+    "RecommenderConfigTypeDef",
     "BatchInferenceJobTypeDef",
     "CreateBatchInferenceJobRequestRequestTypeDef",
     "BatchSegmentJobTypeDef",
     "CreateBatchSegmentJobRequestRequestTypeDef",
     "CreateDatasetExportJobRequestRequestTypeDef",
     "DatasetExportJobTypeDef",
     "CreateMetricAttributionRequestRequestTypeDef",
     "MetricAttributionTypeDef",
     "UpdateMetricAttributionRequestRequestTypeDef",
     "CampaignTypeDef",
     "DescribeDatasetImportJobResponseTypeDef",
-    "ListRecommendersResponseTypeDef",
-    "RecommenderTypeDef",
     "AlgorithmTypeDef",
     "HPOConfigTypeDef",
+    "CreateRecommenderRequestRequestTypeDef",
+    "RecommenderSummaryTypeDef",
+    "RecommenderUpdateSummaryTypeDef",
+    "UpdateRecommenderRequestRequestTypeDef",
     "DescribeBatchInferenceJobResponseTypeDef",
     "DescribeBatchSegmentJobResponseTypeDef",
     "DescribeDatasetExportJobResponseTypeDef",
     "DescribeMetricAttributionResponseTypeDef",
     "DescribeCampaignResponseTypeDef",
-    "DescribeRecommenderResponseTypeDef",
     "DescribeAlgorithmResponseTypeDef",
     "SolutionConfigTypeDef",
+    "ListRecommendersResponseTypeDef",
+    "RecommenderTypeDef",
     "CreateSolutionRequestRequestTypeDef",
     "SolutionTypeDef",
     "SolutionVersionTypeDef",
+    "DescribeRecommenderResponseTypeDef",
     "DescribeSolutionResponseTypeDef",
     "DescribeSolutionVersionResponseTypeDef",
 )
 
 _RequiredAlgorithmImageTypeDef = TypedDict(
     "_RequiredAlgorithmImageTypeDef",
     {
@@ -248,17 +250,19 @@
     "_OptionalAlgorithmImageTypeDef",
     {
         "name": str,
     },
     total=False,
 )
 
+
 class AlgorithmImageTypeDef(_RequiredAlgorithmImageTypeDef, _OptionalAlgorithmImageTypeDef):
     pass
 
+
 AutoMLConfigTypeDef = TypedDict(
     "AutoMLConfigTypeDef",
     {
         "metricName": str,
         "recipeList": Sequence[str],
     },
     total=False,
@@ -290,17 +294,19 @@
     "_OptionalS3DataConfigTypeDef",
     {
         "kmsKeyArn": str,
     },
     total=False,
 )
 
+
 class S3DataConfigTypeDef(_RequiredS3DataConfigTypeDef, _OptionalS3DataConfigTypeDef):
     pass
 
+
 BatchInferenceJobSummaryTypeDef = TypedDict(
     "BatchInferenceJobSummaryTypeDef",
     {
         "batchInferenceJobArn": str,
         "jobName": str,
         "status": str,
         "creationDateTime": datetime,
@@ -369,49 +375,119 @@
     "TagTypeDef",
     {
         "tagKey": str,
         "tagValue": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateBatchInferenceJobResponseTypeDef = TypedDict(
+    "CreateBatchInferenceJobResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "batchInferenceJobArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateBatchSegmentJobResponseTypeDef = TypedDict(
+    "CreateBatchSegmentJobResponseTypeDef",
+    {
+        "batchSegmentJobArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateCampaignResponseTypeDef = TypedDict(
+    "CreateCampaignResponseTypeDef",
+    {
+        "campaignArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateDatasetExportJobResponseTypeDef = TypedDict(
+    "CreateDatasetExportJobResponseTypeDef",
+    {
+        "datasetExportJobArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateDatasetGroupResponseTypeDef = TypedDict(
+    "CreateDatasetGroupResponseTypeDef",
+    {
+        "datasetGroupArn": str,
+        "domain": DomainType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DataSourceTypeDef = TypedDict(
     "DataSourceTypeDef",
     {
         "dataLocation": str,
     },
     total=False,
 )
 
+CreateDatasetImportJobResponseTypeDef = TypedDict(
+    "CreateDatasetImportJobResponseTypeDef",
+    {
+        "datasetImportJobArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateDatasetResponseTypeDef = TypedDict(
+    "CreateDatasetResponseTypeDef",
+    {
+        "datasetArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateEventTrackerResponseTypeDef = TypedDict(
+    "CreateEventTrackerResponseTypeDef",
+    {
+        "eventTrackerArn": str,
+        "trackingId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateFilterResponseTypeDef = TypedDict(
+    "CreateFilterResponseTypeDef",
+    {
+        "filterArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 MetricAttributeTypeDef = TypedDict(
     "MetricAttributeTypeDef",
     {
         "eventType": str,
         "metricName": str,
         "expression": str,
     },
 )
 
-RecommenderConfigTypeDef = TypedDict(
-    "RecommenderConfigTypeDef",
+CreateMetricAttributionResponseTypeDef = TypedDict(
+    "CreateMetricAttributionResponseTypeDef",
     {
-        "itemExplorationConfig": Mapping[str, str],
-        "minRecommendationRequestsPerSecond": int,
+        "metricAttributionArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateRecommenderResponseTypeDef = TypedDict(
+    "CreateRecommenderResponseTypeDef",
+    {
+        "recommenderArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
 _RequiredCreateSchemaRequestRequestTypeDef = TypedDict(
     "_RequiredCreateSchemaRequestRequestTypeDef",
     {
         "name": str,
         "schema": str,
@@ -421,19 +497,45 @@
     "_OptionalCreateSchemaRequestRequestTypeDef",
     {
         "domain": DomainType,
     },
     total=False,
 )
 
+
 class CreateSchemaRequestRequestTypeDef(
     _RequiredCreateSchemaRequestRequestTypeDef, _OptionalCreateSchemaRequestRequestTypeDef
 ):
     pass
 
+
+CreateSchemaResponseTypeDef = TypedDict(
+    "CreateSchemaResponseTypeDef",
+    {
+        "schemaArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateSolutionResponseTypeDef = TypedDict(
+    "CreateSolutionResponseTypeDef",
+    {
+        "solutionArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateSolutionVersionResponseTypeDef = TypedDict(
+    "CreateSolutionVersionResponseTypeDef",
+    {
+        "solutionVersionArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DatasetExportJobSummaryTypeDef = TypedDict(
     "DatasetExportJobSummaryTypeDef",
     {
         "datasetExportJobArn": str,
         "jobName": str,
         "status": str,
         "creationDateTime": datetime,
@@ -809,14 +911,21 @@
 DescribeSolutionVersionRequestRequestTypeDef = TypedDict(
     "DescribeSolutionVersionRequestRequestTypeDef",
     {
         "solutionVersionArn": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EventTrackerSummaryTypeDef = TypedDict(
     "EventTrackerSummaryTypeDef",
     {
         "name": str,
         "eventTrackerArn": str,
         "status": str,
         "creationDateTime": datetime,
@@ -842,14 +951,23 @@
 GetSolutionMetricsRequestRequestTypeDef = TypedDict(
     "GetSolutionMetricsRequestRequestTypeDef",
     {
         "solutionVersionArn": str,
     },
 )
 
+GetSolutionMetricsResponseTypeDef = TypedDict(
+    "GetSolutionMetricsResponseTypeDef",
+    {
+        "solutionVersionArn": str,
+        "metrics": Dict[str, float],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 HPOObjectiveTypeDef = TypedDict(
     "HPOObjectiveTypeDef",
     {
         "type": str,
         "metricName": str,
         "metricRegex": str,
     },
@@ -871,123 +989,211 @@
         "name": str,
         "minValue": int,
         "maxValue": int,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListBatchInferenceJobsRequestListBatchInferenceJobsPaginateTypeDef = TypedDict(
+    "ListBatchInferenceJobsRequestListBatchInferenceJobsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "solutionVersionArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListBatchInferenceJobsRequestRequestTypeDef = TypedDict(
     "ListBatchInferenceJobsRequestRequestTypeDef",
     {
         "solutionVersionArn": str,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListBatchSegmentJobsRequestListBatchSegmentJobsPaginateTypeDef = TypedDict(
+    "ListBatchSegmentJobsRequestListBatchSegmentJobsPaginateTypeDef",
+    {
+        "solutionVersionArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListBatchSegmentJobsRequestRequestTypeDef = TypedDict(
     "ListBatchSegmentJobsRequestRequestTypeDef",
     {
         "solutionVersionArn": str,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListCampaignsRequestListCampaignsPaginateTypeDef = TypedDict(
+    "ListCampaignsRequestListCampaignsPaginateTypeDef",
+    {
+        "solutionArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCampaignsRequestRequestTypeDef = TypedDict(
     "ListCampaignsRequestRequestTypeDef",
     {
         "solutionArn": str,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListDatasetExportJobsRequestListDatasetExportJobsPaginateTypeDef = TypedDict(
+    "ListDatasetExportJobsRequestListDatasetExportJobsPaginateTypeDef",
+    {
+        "datasetArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDatasetExportJobsRequestRequestTypeDef = TypedDict(
     "ListDatasetExportJobsRequestRequestTypeDef",
     {
         "datasetArn": str,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListDatasetGroupsRequestListDatasetGroupsPaginateTypeDef = TypedDict(
+    "ListDatasetGroupsRequestListDatasetGroupsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDatasetGroupsRequestRequestTypeDef = TypedDict(
     "ListDatasetGroupsRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListDatasetImportJobsRequestListDatasetImportJobsPaginateTypeDef = TypedDict(
+    "ListDatasetImportJobsRequestListDatasetImportJobsPaginateTypeDef",
+    {
+        "datasetArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDatasetImportJobsRequestRequestTypeDef = TypedDict(
     "ListDatasetImportJobsRequestRequestTypeDef",
     {
         "datasetArn": str,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListDatasetsRequestListDatasetsPaginateTypeDef = TypedDict(
+    "ListDatasetsRequestListDatasetsPaginateTypeDef",
+    {
+        "datasetGroupArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDatasetsRequestRequestTypeDef = TypedDict(
     "ListDatasetsRequestRequestTypeDef",
     {
         "datasetGroupArn": str,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListEventTrackersRequestListEventTrackersPaginateTypeDef = TypedDict(
+    "ListEventTrackersRequestListEventTrackersPaginateTypeDef",
+    {
+        "datasetGroupArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListEventTrackersRequestRequestTypeDef = TypedDict(
     "ListEventTrackersRequestRequestTypeDef",
     {
         "datasetGroupArn": str,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListFiltersRequestListFiltersPaginateTypeDef = TypedDict(
+    "ListFiltersRequestListFiltersPaginateTypeDef",
+    {
+        "datasetGroupArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListFiltersRequestRequestTypeDef = TypedDict(
     "ListFiltersRequestRequestTypeDef",
     {
         "datasetGroupArn": str,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListMetricAttributionMetricsRequestListMetricAttributionMetricsPaginateTypeDef = TypedDict(
+    "ListMetricAttributionMetricsRequestListMetricAttributionMetricsPaginateTypeDef",
+    {
+        "metricAttributionArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListMetricAttributionMetricsRequestRequestTypeDef = TypedDict(
     "ListMetricAttributionMetricsRequestRequestTypeDef",
     {
         "metricAttributionArn": str,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListMetricAttributionsRequestListMetricAttributionsPaginateTypeDef = TypedDict(
+    "ListMetricAttributionsRequestListMetricAttributionsPaginateTypeDef",
+    {
+        "datasetGroupArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListMetricAttributionsRequestRequestTypeDef = TypedDict(
     "ListMetricAttributionsRequestRequestTypeDef",
     {
         "datasetGroupArn": str,
         "nextToken": str,
         "maxResults": int,
     },
@@ -1003,14 +1209,24 @@
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
         "failureReason": str,
     },
     total=False,
 )
 
+ListRecipesRequestListRecipesPaginateTypeDef = TypedDict(
+    "ListRecipesRequestListRecipesPaginateTypeDef",
+    {
+        "recipeProvider": Literal["SERVICE"],
+        "domain": DomainType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListRecipesRequestRequestTypeDef = TypedDict(
     "ListRecipesRequestRequestTypeDef",
     {
         "recipeProvider": Literal["SERVICE"],
         "nextToken": str,
         "maxResults": int,
         "domain": DomainType,
@@ -1027,33 +1243,59 @@
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
         "domain": DomainType,
     },
     total=False,
 )
 
+ListRecommendersRequestListRecommendersPaginateTypeDef = TypedDict(
+    "ListRecommendersRequestListRecommendersPaginateTypeDef",
+    {
+        "datasetGroupArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListRecommendersRequestRequestTypeDef = TypedDict(
     "ListRecommendersRequestRequestTypeDef",
     {
         "datasetGroupArn": str,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListSchemasRequestListSchemasPaginateTypeDef = TypedDict(
+    "ListSchemasRequestListSchemasPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSchemasRequestRequestTypeDef = TypedDict(
     "ListSchemasRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListSolutionVersionsRequestListSolutionVersionsPaginateTypeDef = TypedDict(
+    "ListSolutionVersionsRequestListSolutionVersionsPaginateTypeDef",
+    {
+        "solutionArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSolutionVersionsRequestRequestTypeDef = TypedDict(
     "ListSolutionVersionsRequestRequestTypeDef",
     {
         "solutionArn": str,
         "nextToken": str,
         "maxResults": int,
     },
@@ -1068,14 +1310,23 @@
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
         "failureReason": str,
     },
     total=False,
 )
 
+ListSolutionsRequestListSolutionsPaginateTypeDef = TypedDict(
+    "ListSolutionsRequestListSolutionsPaginateTypeDef",
+    {
+        "datasetGroupArn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSolutionsRequestRequestTypeDef = TypedDict(
     "ListSolutionsRequestRequestTypeDef",
     {
         "datasetGroupArn": str,
         "nextToken": str,
         "maxResults": int,
     },
@@ -1107,14 +1358,43 @@
     {
         "itemAttribute": str,
         "objectiveSensitivity": ObjectiveSensitivityType,
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
+TrainingDataConfigTypeDef = TypedDict(
+    "TrainingDataConfigTypeDef",
+    {
+        "excludedDatasetColumns": Mapping[str, Sequence[str]],
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
 TunedHPOParamsTypeDef = TypedDict(
     "TunedHPOParamsTypeDef",
     {
         "algorithmHyperParameters": Dict[str, str],
     },
     total=False,
 )
@@ -1122,21 +1402,37 @@
 StartRecommenderRequestRequestTypeDef = TypedDict(
     "StartRecommenderRequestRequestTypeDef",
     {
         "recommenderArn": str,
     },
 )
 
+StartRecommenderResponseTypeDef = TypedDict(
+    "StartRecommenderResponseTypeDef",
+    {
+        "recommenderArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopRecommenderRequestRequestTypeDef = TypedDict(
     "StopRecommenderRequestRequestTypeDef",
     {
         "recommenderArn": str,
     },
 )
 
+StopRecommenderResponseTypeDef = TypedDict(
+    "StopRecommenderResponseTypeDef",
+    {
+        "recommenderArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopSolutionVersionCreationRequestRequestTypeDef = TypedDict(
     "StopSolutionVersionCreationRequestRequestTypeDef",
     {
         "solutionVersionArn": str,
     },
 )
 
@@ -1144,14 +1440,38 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
 
+UpdateCampaignResponseTypeDef = TypedDict(
+    "UpdateCampaignResponseTypeDef",
+    {
+        "campaignArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateMetricAttributionResponseTypeDef = TypedDict(
+    "UpdateMetricAttributionResponseTypeDef",
+    {
+        "metricAttributionArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateRecommenderResponseTypeDef = TypedDict(
+    "UpdateRecommenderResponseTypeDef",
+    {
+        "recommenderArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 BatchInferenceJobInputTypeDef = TypedDict(
     "BatchInferenceJobInputTypeDef",
     {
         "s3DataSource": S3DataConfigTypeDef,
     },
 )
 
@@ -1193,19 +1513,39 @@
     "_OptionalMetricAttributionOutputTypeDef",
     {
         "s3DataDestination": S3DataConfigTypeDef,
     },
     total=False,
 )
 
+
 class MetricAttributionOutputTypeDef(
     _RequiredMetricAttributionOutputTypeDef, _OptionalMetricAttributionOutputTypeDef
 ):
     pass
 
+
+ListBatchInferenceJobsResponseTypeDef = TypedDict(
+    "ListBatchInferenceJobsResponseTypeDef",
+    {
+        "batchInferenceJobs": List[BatchInferenceJobSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListBatchSegmentJobsResponseTypeDef = TypedDict(
+    "ListBatchSegmentJobsResponseTypeDef",
+    {
+        "batchSegmentJobs": List[BatchSegmentJobSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CampaignUpdateSummaryTypeDef = TypedDict(
     "CampaignUpdateSummaryTypeDef",
     {
         "solutionVersionArn": str,
         "minProvisionedTPS": int,
         "campaignConfig": CampaignConfigTypeDef,
         "status": str,
@@ -1228,19 +1568,30 @@
         "solutionVersionArn": str,
         "minProvisionedTPS": int,
         "campaignConfig": CampaignConfigTypeDef,
     },
     total=False,
 )
 
+
 class UpdateCampaignRequestRequestTypeDef(
     _RequiredUpdateCampaignRequestRequestTypeDef, _OptionalUpdateCampaignRequestRequestTypeDef
 ):
     pass
 
+
+ListCampaignsResponseTypeDef = TypedDict(
+    "ListCampaignsResponseTypeDef",
+    {
+        "campaigns": List[CampaignSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateCampaignRequestRequestTypeDef = TypedDict(
     "_RequiredCreateCampaignRequestRequestTypeDef",
     {
         "name": str,
         "solutionVersionArn": str,
     },
 )
@@ -1250,19 +1601,21 @@
         "minProvisionedTPS": int,
         "campaignConfig": CampaignConfigTypeDef,
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateCampaignRequestRequestTypeDef(
     _RequiredCreateCampaignRequestRequestTypeDef, _OptionalCreateCampaignRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredCreateDatasetGroupRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDatasetGroupRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalCreateDatasetGroupRequestRequestTypeDef = TypedDict(
@@ -1272,20 +1625,22 @@
         "kmsKeyArn": str,
         "domain": DomainType,
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateDatasetGroupRequestRequestTypeDef(
     _RequiredCreateDatasetGroupRequestRequestTypeDef,
     _OptionalCreateDatasetGroupRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredCreateDatasetRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDatasetRequestRequestTypeDef",
     {
         "name": str,
         "schemaArn": str,
         "datasetGroupArn": str,
         "datasetType": str,
@@ -1295,19 +1650,21 @@
     "_OptionalCreateDatasetRequestRequestTypeDef",
     {
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateDatasetRequestRequestTypeDef(
     _RequiredCreateDatasetRequestRequestTypeDef, _OptionalCreateDatasetRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredCreateEventTrackerRequestRequestTypeDef = TypedDict(
     "_RequiredCreateEventTrackerRequestRequestTypeDef",
     {
         "name": str,
         "datasetGroupArn": str,
     },
 )
@@ -1315,20 +1672,22 @@
     "_OptionalCreateEventTrackerRequestRequestTypeDef",
     {
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateEventTrackerRequestRequestTypeDef(
     _RequiredCreateEventTrackerRequestRequestTypeDef,
     _OptionalCreateEventTrackerRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredCreateFilterRequestRequestTypeDef = TypedDict(
     "_RequiredCreateFilterRequestRequestTypeDef",
     {
         "name": str,
         "datasetGroupArn": str,
         "filterExpression": str,
     },
@@ -1337,19 +1696,21 @@
     "_OptionalCreateFilterRequestRequestTypeDef",
     {
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateFilterRequestRequestTypeDef(
     _RequiredCreateFilterRequestRequestTypeDef, _OptionalCreateFilterRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredCreateSolutionVersionRequestRequestTypeDef = TypedDict(
     "_RequiredCreateSolutionVersionRequestRequestTypeDef",
     {
         "solutionArn": str,
     },
 )
 _OptionalCreateSolutionVersionRequestRequestTypeDef = TypedDict(
@@ -1358,230 +1719,35 @@
         "name": str,
         "trainingMode": TrainingModeType,
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateSolutionVersionRequestRequestTypeDef(
     _RequiredCreateSolutionVersionRequestRequestTypeDef,
     _OptionalCreateSolutionVersionRequestRequestTypeDef,
 ):
     pass
 
-TagResourceRequestRequestTypeDef = TypedDict(
-    "TagResourceRequestRequestTypeDef",
-    {
-        "resourceArn": str,
-        "tags": Sequence[TagTypeDef],
-    },
-)
-
-CreateBatchInferenceJobResponseTypeDef = TypedDict(
-    "CreateBatchInferenceJobResponseTypeDef",
-    {
-        "batchInferenceJobArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateBatchSegmentJobResponseTypeDef = TypedDict(
-    "CreateBatchSegmentJobResponseTypeDef",
-    {
-        "batchSegmentJobArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateCampaignResponseTypeDef = TypedDict(
-    "CreateCampaignResponseTypeDef",
-    {
-        "campaignArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDatasetExportJobResponseTypeDef = TypedDict(
-    "CreateDatasetExportJobResponseTypeDef",
-    {
-        "datasetExportJobArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDatasetGroupResponseTypeDef = TypedDict(
-    "CreateDatasetGroupResponseTypeDef",
-    {
-        "datasetGroupArn": str,
-        "domain": DomainType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDatasetImportJobResponseTypeDef = TypedDict(
-    "CreateDatasetImportJobResponseTypeDef",
-    {
-        "datasetImportJobArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDatasetResponseTypeDef = TypedDict(
-    "CreateDatasetResponseTypeDef",
-    {
-        "datasetArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateEventTrackerResponseTypeDef = TypedDict(
-    "CreateEventTrackerResponseTypeDef",
-    {
-        "eventTrackerArn": str,
-        "trackingId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateFilterResponseTypeDef = TypedDict(
-    "CreateFilterResponseTypeDef",
-    {
-        "filterArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateMetricAttributionResponseTypeDef = TypedDict(
-    "CreateMetricAttributionResponseTypeDef",
-    {
-        "metricAttributionArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateRecommenderResponseTypeDef = TypedDict(
-    "CreateRecommenderResponseTypeDef",
-    {
-        "recommenderArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateSchemaResponseTypeDef = TypedDict(
-    "CreateSchemaResponseTypeDef",
-    {
-        "schemaArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateSolutionResponseTypeDef = TypedDict(
-    "CreateSolutionResponseTypeDef",
-    {
-        "solutionArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateSolutionVersionResponseTypeDef = TypedDict(
-    "CreateSolutionVersionResponseTypeDef",
-    {
-        "solutionVersionArn": str,
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
-GetSolutionMetricsResponseTypeDef = TypedDict(
-    "GetSolutionMetricsResponseTypeDef",
-    {
-        "solutionVersionArn": str,
-        "metrics": Dict[str, float],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListBatchInferenceJobsResponseTypeDef = TypedDict(
-    "ListBatchInferenceJobsResponseTypeDef",
-    {
-        "batchInferenceJobs": List[BatchInferenceJobSummaryTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListBatchSegmentJobsResponseTypeDef = TypedDict(
-    "ListBatchSegmentJobsResponseTypeDef",
-    {
-        "batchSegmentJobs": List[BatchSegmentJobSummaryTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListCampaignsResponseTypeDef = TypedDict(
-    "ListCampaignsResponseTypeDef",
-    {
-        "campaigns": List[CampaignSummaryTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StartRecommenderResponseTypeDef = TypedDict(
-    "StartRecommenderResponseTypeDef",
-    {
-        "recommenderArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StopRecommenderResponseTypeDef = TypedDict(
-    "StopRecommenderResponseTypeDef",
-    {
-        "recommenderArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateCampaignResponseTypeDef = TypedDict(
-    "UpdateCampaignResponseTypeDef",
-    {
-        "campaignArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateMetricAttributionResponseTypeDef = TypedDict(
-    "UpdateMetricAttributionResponseTypeDef",
-    {
-        "metricAttributionArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateRecommenderResponseTypeDef = TypedDict(
-    "UpdateRecommenderResponseTypeDef",
+TagResourceRequestRequestTypeDef = TypedDict(
+    "TagResourceRequestRequestTypeDef",
     {
-        "recommenderArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "resourceArn": str,
+        "tags": Sequence[TagTypeDef],
     },
 )
 
 _RequiredCreateDatasetImportJobRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDatasetImportJobRequestRequestTypeDef",
     {
         "jobName": str,
@@ -1596,20 +1762,22 @@
         "tags": Sequence[TagTypeDef],
         "importMode": ImportModeType,
         "publishAttributionMetricsToS3": bool,
     },
     total=False,
 )
 
+
 class CreateDatasetImportJobRequestRequestTypeDef(
     _RequiredCreateDatasetImportJobRequestRequestTypeDef,
     _OptionalCreateDatasetImportJobRequestRequestTypeDef,
 ):
     pass
 
+
 DatasetImportJobTypeDef = TypedDict(
     "DatasetImportJobTypeDef",
     {
         "jobName": str,
         "datasetImportJobArn": str,
         "datasetArn": str,
         "dataSource": DataSourceTypeDef,
@@ -1625,141 +1793,84 @@
 )
 
 ListMetricAttributionMetricsResponseTypeDef = TypedDict(
     "ListMetricAttributionMetricsResponseTypeDef",
     {
         "metrics": List[MetricAttributeTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredCreateRecommenderRequestRequestTypeDef = TypedDict(
-    "_RequiredCreateRecommenderRequestRequestTypeDef",
-    {
-        "name": str,
-        "datasetGroupArn": str,
-        "recipeArn": str,
-    },
-)
-_OptionalCreateRecommenderRequestRequestTypeDef = TypedDict(
-    "_OptionalCreateRecommenderRequestRequestTypeDef",
-    {
-        "recommenderConfig": RecommenderConfigTypeDef,
-        "tags": Sequence[TagTypeDef],
-    },
-    total=False,
-)
-
-class CreateRecommenderRequestRequestTypeDef(
-    _RequiredCreateRecommenderRequestRequestTypeDef, _OptionalCreateRecommenderRequestRequestTypeDef
-):
-    pass
-
-RecommenderSummaryTypeDef = TypedDict(
-    "RecommenderSummaryTypeDef",
-    {
-        "name": str,
-        "recommenderArn": str,
-        "datasetGroupArn": str,
-        "recipeArn": str,
-        "recommenderConfig": RecommenderConfigTypeDef,
-        "status": str,
-        "creationDateTime": datetime,
-        "lastUpdatedDateTime": datetime,
-    },
-    total=False,
-)
-
-RecommenderUpdateSummaryTypeDef = TypedDict(
-    "RecommenderUpdateSummaryTypeDef",
-    {
-        "recommenderConfig": RecommenderConfigTypeDef,
-        "creationDateTime": datetime,
-        "lastUpdatedDateTime": datetime,
-        "status": str,
-        "failureReason": str,
-    },
-    total=False,
-)
-
-UpdateRecommenderRequestRequestTypeDef = TypedDict(
-    "UpdateRecommenderRequestRequestTypeDef",
-    {
-        "recommenderArn": str,
-        "recommenderConfig": RecommenderConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDatasetExportJobsResponseTypeDef = TypedDict(
     "ListDatasetExportJobsResponseTypeDef",
     {
         "datasetExportJobs": List[DatasetExportJobSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDatasetGroupsResponseTypeDef = TypedDict(
     "ListDatasetGroupsResponseTypeDef",
     {
         "datasetGroups": List[DatasetGroupSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDatasetGroupResponseTypeDef = TypedDict(
     "DescribeDatasetGroupResponseTypeDef",
     {
         "datasetGroup": DatasetGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDatasetImportJobsResponseTypeDef = TypedDict(
     "ListDatasetImportJobsResponseTypeDef",
     {
         "datasetImportJobs": List[DatasetImportJobSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSchemasResponseTypeDef = TypedDict(
     "ListSchemasResponseTypeDef",
     {
         "schemas": List[DatasetSchemaSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSchemaResponseTypeDef = TypedDict(
     "DescribeSchemaResponseTypeDef",
     {
         "schema": DatasetSchemaTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDatasetsResponseTypeDef = TypedDict(
     "ListDatasetsResponseTypeDef",
     {
         "datasets": List[DatasetSummaryTypeDef],
         "nextToken": str,
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
 
 DefaultHyperParameterRangesTypeDef = TypedDict(
     "DefaultHyperParameterRangesTypeDef",
     {
         "integerHyperParameterRanges": List[DefaultIntegerHyperParameterRangeTypeDef],
@@ -1769,247 +1880,114 @@
     total=False,
 )
 
 DescribeEventTrackerResponseTypeDef = TypedDict(
     "DescribeEventTrackerResponseTypeDef",
     {
         "eventTracker": EventTrackerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFeatureTransformationResponseTypeDef = TypedDict(
     "DescribeFeatureTransformationResponseTypeDef",
     {
         "featureTransformation": FeatureTransformationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFilterResponseTypeDef = TypedDict(
     "DescribeFilterResponseTypeDef",
     {
         "filter": FilterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeRecipeResponseTypeDef = TypedDict(
     "DescribeRecipeResponseTypeDef",
     {
         "recipe": RecipeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEventTrackersResponseTypeDef = TypedDict(
     "ListEventTrackersResponseTypeDef",
     {
         "eventTrackers": List[EventTrackerSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListFiltersResponseTypeDef = TypedDict(
     "ListFiltersResponseTypeDef",
     {
         "Filters": List[FilterSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 HyperParameterRangesTypeDef = TypedDict(
     "HyperParameterRangesTypeDef",
     {
         "integerHyperParameterRanges": Sequence[IntegerHyperParameterRangeTypeDef],
         "continuousHyperParameterRanges": Sequence[ContinuousHyperParameterRangeTypeDef],
         "categoricalHyperParameterRanges": Sequence[CategoricalHyperParameterRangeTypeDef],
     },
     total=False,
 )
 
-ListBatchInferenceJobsRequestListBatchInferenceJobsPaginateTypeDef = TypedDict(
-    "ListBatchInferenceJobsRequestListBatchInferenceJobsPaginateTypeDef",
-    {
-        "solutionVersionArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListBatchSegmentJobsRequestListBatchSegmentJobsPaginateTypeDef = TypedDict(
-    "ListBatchSegmentJobsRequestListBatchSegmentJobsPaginateTypeDef",
-    {
-        "solutionVersionArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListCampaignsRequestListCampaignsPaginateTypeDef = TypedDict(
-    "ListCampaignsRequestListCampaignsPaginateTypeDef",
-    {
-        "solutionArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListDatasetExportJobsRequestListDatasetExportJobsPaginateTypeDef = TypedDict(
-    "ListDatasetExportJobsRequestListDatasetExportJobsPaginateTypeDef",
-    {
-        "datasetArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListDatasetGroupsRequestListDatasetGroupsPaginateTypeDef = TypedDict(
-    "ListDatasetGroupsRequestListDatasetGroupsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListDatasetImportJobsRequestListDatasetImportJobsPaginateTypeDef = TypedDict(
-    "ListDatasetImportJobsRequestListDatasetImportJobsPaginateTypeDef",
-    {
-        "datasetArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListDatasetsRequestListDatasetsPaginateTypeDef = TypedDict(
-    "ListDatasetsRequestListDatasetsPaginateTypeDef",
-    {
-        "datasetGroupArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListEventTrackersRequestListEventTrackersPaginateTypeDef = TypedDict(
-    "ListEventTrackersRequestListEventTrackersPaginateTypeDef",
-    {
-        "datasetGroupArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListFiltersRequestListFiltersPaginateTypeDef = TypedDict(
-    "ListFiltersRequestListFiltersPaginateTypeDef",
-    {
-        "datasetGroupArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListMetricAttributionMetricsRequestListMetricAttributionMetricsPaginateTypeDef = TypedDict(
-    "ListMetricAttributionMetricsRequestListMetricAttributionMetricsPaginateTypeDef",
-    {
-        "metricAttributionArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListMetricAttributionsRequestListMetricAttributionsPaginateTypeDef = TypedDict(
-    "ListMetricAttributionsRequestListMetricAttributionsPaginateTypeDef",
-    {
-        "datasetGroupArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListRecipesRequestListRecipesPaginateTypeDef = TypedDict(
-    "ListRecipesRequestListRecipesPaginateTypeDef",
-    {
-        "recipeProvider": Literal["SERVICE"],
-        "domain": DomainType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListRecommendersRequestListRecommendersPaginateTypeDef = TypedDict(
-    "ListRecommendersRequestListRecommendersPaginateTypeDef",
-    {
-        "datasetGroupArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListSchemasRequestListSchemasPaginateTypeDef = TypedDict(
-    "ListSchemasRequestListSchemasPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListSolutionVersionsRequestListSolutionVersionsPaginateTypeDef = TypedDict(
-    "ListSolutionVersionsRequestListSolutionVersionsPaginateTypeDef",
-    {
-        "solutionArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListSolutionsRequestListSolutionsPaginateTypeDef = TypedDict(
-    "ListSolutionsRequestListSolutionsPaginateTypeDef",
-    {
-        "datasetGroupArn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListMetricAttributionsResponseTypeDef = TypedDict(
     "ListMetricAttributionsResponseTypeDef",
     {
         "metricAttributions": List[MetricAttributionSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRecipesResponseTypeDef = TypedDict(
     "ListRecipesResponseTypeDef",
     {
         "recipes": List[RecipeSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSolutionVersionsResponseTypeDef = TypedDict(
     "ListSolutionVersionsResponseTypeDef",
     {
         "solutionVersions": List[SolutionVersionSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSolutionsResponseTypeDef = TypedDict(
     "ListSolutionsResponseTypeDef",
     {
         "solutions": List[SolutionSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+RecommenderConfigTypeDef = TypedDict(
+    "RecommenderConfigTypeDef",
+    {
+        "itemExplorationConfig": Mapping[str, str],
+        "minRecommendationRequestsPerSecond": int,
+        "trainingDataConfig": TrainingDataConfigTypeDef,
     },
+    total=False,
 )
 
 BatchInferenceJobTypeDef = TypedDict(
     "BatchInferenceJobTypeDef",
     {
         "jobName": str,
         "batchInferenceJobArn": str,
@@ -2045,20 +2023,22 @@
         "numResults": int,
         "batchInferenceJobConfig": BatchInferenceJobConfigTypeDef,
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateBatchInferenceJobRequestRequestTypeDef(
     _RequiredCreateBatchInferenceJobRequestRequestTypeDef,
     _OptionalCreateBatchInferenceJobRequestRequestTypeDef,
 ):
     pass
 
+
 BatchSegmentJobTypeDef = TypedDict(
     "BatchSegmentJobTypeDef",
     {
         "jobName": str,
         "batchSegmentJobArn": str,
         "filterArn": str,
         "failureReason": str,
@@ -2090,20 +2070,22 @@
         "filterArn": str,
         "numResults": int,
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateBatchSegmentJobRequestRequestTypeDef(
     _RequiredCreateBatchSegmentJobRequestRequestTypeDef,
     _OptionalCreateBatchSegmentJobRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredCreateDatasetExportJobRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDatasetExportJobRequestRequestTypeDef",
     {
         "jobName": str,
         "datasetArn": str,
         "roleArn": str,
         "jobOutput": DatasetExportJobOutputTypeDef,
@@ -2114,20 +2096,22 @@
     {
         "ingestionMode": IngestionModeType,
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateDatasetExportJobRequestRequestTypeDef(
     _RequiredCreateDatasetExportJobRequestRequestTypeDef,
     _OptionalCreateDatasetExportJobRequestRequestTypeDef,
 ):
     pass
 
+
 DatasetExportJobTypeDef = TypedDict(
     "DatasetExportJobTypeDef",
     {
         "jobName": str,
         "datasetExportJobArn": str,
         "datasetArn": str,
         "ingestionMode": IngestionModeType,
@@ -2194,43 +2178,16 @@
     total=False,
 )
 
 DescribeDatasetImportJobResponseTypeDef = TypedDict(
     "DescribeDatasetImportJobResponseTypeDef",
     {
         "datasetImportJob": DatasetImportJobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListRecommendersResponseTypeDef = TypedDict(
-    "ListRecommendersResponseTypeDef",
-    {
-        "recommenders": List[RecommenderSummaryTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RecommenderTypeDef = TypedDict(
-    "RecommenderTypeDef",
-    {
-        "recommenderArn": str,
-        "datasetGroupArn": str,
-        "name": str,
-        "recipeArn": str,
-        "recommenderConfig": RecommenderConfigTypeDef,
-        "creationDateTime": datetime,
-        "lastUpdatedDateTime": datetime,
-        "status": str,
-        "failureReason": str,
-        "latestRecommenderUpdate": RecommenderUpdateSummaryTypeDef,
-        "modelMetrics": Dict[str, float],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
 AlgorithmTypeDef = TypedDict(
     "AlgorithmTypeDef",
     {
         "name": str,
         "algorithmArn": str,
@@ -2252,79 +2209,158 @@
         "hpoObjective": HPOObjectiveTypeDef,
         "hpoResourceConfig": HPOResourceConfigTypeDef,
         "algorithmHyperParameterRanges": HyperParameterRangesTypeDef,
     },
     total=False,
 )
 
+_RequiredCreateRecommenderRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateRecommenderRequestRequestTypeDef",
+    {
+        "name": str,
+        "datasetGroupArn": str,
+        "recipeArn": str,
+    },
+)
+_OptionalCreateRecommenderRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateRecommenderRequestRequestTypeDef",
+    {
+        "recommenderConfig": RecommenderConfigTypeDef,
+        "tags": Sequence[TagTypeDef],
+    },
+    total=False,
+)
+
+
+class CreateRecommenderRequestRequestTypeDef(
+    _RequiredCreateRecommenderRequestRequestTypeDef, _OptionalCreateRecommenderRequestRequestTypeDef
+):
+    pass
+
+
+RecommenderSummaryTypeDef = TypedDict(
+    "RecommenderSummaryTypeDef",
+    {
+        "name": str,
+        "recommenderArn": str,
+        "datasetGroupArn": str,
+        "recipeArn": str,
+        "recommenderConfig": RecommenderConfigTypeDef,
+        "status": str,
+        "creationDateTime": datetime,
+        "lastUpdatedDateTime": datetime,
+    },
+    total=False,
+)
+
+RecommenderUpdateSummaryTypeDef = TypedDict(
+    "RecommenderUpdateSummaryTypeDef",
+    {
+        "recommenderConfig": RecommenderConfigTypeDef,
+        "creationDateTime": datetime,
+        "lastUpdatedDateTime": datetime,
+        "status": str,
+        "failureReason": str,
+    },
+    total=False,
+)
+
+UpdateRecommenderRequestRequestTypeDef = TypedDict(
+    "UpdateRecommenderRequestRequestTypeDef",
+    {
+        "recommenderArn": str,
+        "recommenderConfig": RecommenderConfigTypeDef,
+    },
+)
+
 DescribeBatchInferenceJobResponseTypeDef = TypedDict(
     "DescribeBatchInferenceJobResponseTypeDef",
     {
         "batchInferenceJob": BatchInferenceJobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeBatchSegmentJobResponseTypeDef = TypedDict(
     "DescribeBatchSegmentJobResponseTypeDef",
     {
         "batchSegmentJob": BatchSegmentJobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDatasetExportJobResponseTypeDef = TypedDict(
     "DescribeDatasetExportJobResponseTypeDef",
     {
         "datasetExportJob": DatasetExportJobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeMetricAttributionResponseTypeDef = TypedDict(
     "DescribeMetricAttributionResponseTypeDef",
     {
         "metricAttribution": MetricAttributionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeCampaignResponseTypeDef = TypedDict(
     "DescribeCampaignResponseTypeDef",
     {
         "campaign": CampaignTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeRecommenderResponseTypeDef = TypedDict(
-    "DescribeRecommenderResponseTypeDef",
-    {
-        "recommender": RecommenderTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAlgorithmResponseTypeDef = TypedDict(
     "DescribeAlgorithmResponseTypeDef",
     {
         "algorithm": AlgorithmTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SolutionConfigTypeDef = TypedDict(
     "SolutionConfigTypeDef",
     {
         "eventValueThreshold": str,
         "hpoConfig": HPOConfigTypeDef,
         "algorithmHyperParameters": Mapping[str, str],
         "featureTransformationParameters": Mapping[str, str],
         "autoMLConfig": AutoMLConfigTypeDef,
         "optimizationObjective": OptimizationObjectiveTypeDef,
+        "trainingDataConfig": TrainingDataConfigTypeDef,
+    },
+    total=False,
+)
+
+ListRecommendersResponseTypeDef = TypedDict(
+    "ListRecommendersResponseTypeDef",
+    {
+        "recommenders": List[RecommenderSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+RecommenderTypeDef = TypedDict(
+    "RecommenderTypeDef",
+    {
+        "recommenderArn": str,
+        "datasetGroupArn": str,
+        "name": str,
+        "recipeArn": str,
+        "recommenderConfig": RecommenderConfigTypeDef,
+        "creationDateTime": datetime,
+        "lastUpdatedDateTime": datetime,
+        "status": str,
+        "failureReason": str,
+        "latestRecommenderUpdate": RecommenderUpdateSummaryTypeDef,
+        "modelMetrics": Dict[str, float],
     },
     total=False,
 )
 
 _RequiredCreateSolutionRequestRequestTypeDef = TypedDict(
     "_RequiredCreateSolutionRequestRequestTypeDef",
     {
@@ -2341,19 +2377,21 @@
         "eventType": str,
         "solutionConfig": SolutionConfigTypeDef,
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateSolutionRequestRequestTypeDef(
     _RequiredCreateSolutionRequestRequestTypeDef, _OptionalCreateSolutionRequestRequestTypeDef
 ):
     pass
 
+
 SolutionTypeDef = TypedDict(
     "SolutionTypeDef",
     {
         "name": str,
         "solutionArn": str,
         "performHPO": bool,
         "performAutoML": bool,
@@ -2389,22 +2427,30 @@
         "failureReason": str,
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
     },
     total=False,
 )
 
+DescribeRecommenderResponseTypeDef = TypedDict(
+    "DescribeRecommenderResponseTypeDef",
+    {
+        "recommender": RecommenderTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeSolutionResponseTypeDef = TypedDict(
     "DescribeSolutionResponseTypeDef",
     {
         "solution": SolutionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSolutionVersionResponseTypeDef = TypedDict(
     "DescribeSolutionVersionResponseTypeDef",
     {
         "solutionVersion": SolutionVersionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-personalize-2.5.0.post1/types_aiobotocore_personalize.egg-info/PKG-INFO` & `types-aiobotocore-personalize-2.5.1/types_aiobotocore_personalize.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-personalize
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Personalize 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Personalize 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-personalize"></a>
 
 # types-aiobotocore-personalize
 
 [![PyPI - types-aiobotocore-personalize](https://img.shields.io/pypi/v/types-aiobotocore-personalize.svg?color=blue)](https://pypi.org/project/types-aiobotocore-personalize)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-personalize.svg?color=blue)](https://pypi.org/project/types-aiobotocore-personalize)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-personalize?color=blue)](https://pypistats.org/packages/types-aiobotocore-personalize)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Personalize 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize)
+[aiobotocore.Personalize 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/personalize.html#Personalize)
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
 [types-aiobotocore-personalize docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/).
 
 See how it helps to find and fix potential bugs:
 
@@ -399,19 +399,31 @@
     BatchInferenceJobSummaryTypeDef,
     BatchSegmentJobSummaryTypeDef,
     CampaignConfigTypeDef,
     CampaignSummaryTypeDef,
     CategoricalHyperParameterRangeTypeDef,
     ContinuousHyperParameterRangeTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
+    CreateBatchInferenceJobResponseTypeDef,
+    CreateBatchSegmentJobResponseTypeDef,
+    CreateCampaignResponseTypeDef,
+    CreateDatasetExportJobResponseTypeDef,
+    CreateDatasetGroupResponseTypeDef,
     DataSourceTypeDef,
+    CreateDatasetImportJobResponseTypeDef,
+    CreateDatasetResponseTypeDef,
+    CreateEventTrackerResponseTypeDef,
+    CreateFilterResponseTypeDef,
     MetricAttributeTypeDef,
-    RecommenderConfigTypeDef,
+    CreateMetricAttributionResponseTypeDef,
+    CreateRecommenderResponseTypeDef,
     CreateSchemaRequestRequestTypeDef,
+    CreateSchemaResponseTypeDef,
+    CreateSolutionResponseTypeDef,
+    CreateSolutionVersionResponseTypeDef,
     DatasetExportJobSummaryTypeDef,
     DatasetGroupSummaryTypeDef,
     DatasetGroupTypeDef,
     DatasetImportJobSummaryTypeDef,
     DatasetSchemaSummaryTypeDef,
     DatasetSchemaTypeDef,
     DatasetSummaryTypeDef,
@@ -445,95 +457,95 @@
     DescribeMetricAttributionRequestRequestTypeDef,
     DescribeRecipeRequestRequestTypeDef,
     RecipeTypeDef,
     DescribeRecommenderRequestRequestTypeDef,
     DescribeSchemaRequestRequestTypeDef,
     DescribeSolutionRequestRequestTypeDef,
     DescribeSolutionVersionRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EventTrackerSummaryTypeDef,
     FilterSummaryTypeDef,
     GetSolutionMetricsRequestRequestTypeDef,
+    GetSolutionMetricsResponseTypeDef,
     HPOObjectiveTypeDef,
     HPOResourceConfigTypeDef,
     IntegerHyperParameterRangeTypeDef,
-    PaginatorConfigTypeDef,
+    ListBatchInferenceJobsRequestListBatchInferenceJobsPaginateTypeDef,
     ListBatchInferenceJobsRequestRequestTypeDef,
+    ListBatchSegmentJobsRequestListBatchSegmentJobsPaginateTypeDef,
     ListBatchSegmentJobsRequestRequestTypeDef,
+    ListCampaignsRequestListCampaignsPaginateTypeDef,
     ListCampaignsRequestRequestTypeDef,
+    ListDatasetExportJobsRequestListDatasetExportJobsPaginateTypeDef,
     ListDatasetExportJobsRequestRequestTypeDef,
+    ListDatasetGroupsRequestListDatasetGroupsPaginateTypeDef,
     ListDatasetGroupsRequestRequestTypeDef,
+    ListDatasetImportJobsRequestListDatasetImportJobsPaginateTypeDef,
     ListDatasetImportJobsRequestRequestTypeDef,
+    ListDatasetsRequestListDatasetsPaginateTypeDef,
     ListDatasetsRequestRequestTypeDef,
+    ListEventTrackersRequestListEventTrackersPaginateTypeDef,
     ListEventTrackersRequestRequestTypeDef,
+    ListFiltersRequestListFiltersPaginateTypeDef,
     ListFiltersRequestRequestTypeDef,
+    ListMetricAttributionMetricsRequestListMetricAttributionMetricsPaginateTypeDef,
     ListMetricAttributionMetricsRequestRequestTypeDef,
+    ListMetricAttributionsRequestListMetricAttributionsPaginateTypeDef,
     ListMetricAttributionsRequestRequestTypeDef,
     MetricAttributionSummaryTypeDef,
+    ListRecipesRequestListRecipesPaginateTypeDef,
     ListRecipesRequestRequestTypeDef,
     RecipeSummaryTypeDef,
+    ListRecommendersRequestListRecommendersPaginateTypeDef,
     ListRecommendersRequestRequestTypeDef,
+    ListSchemasRequestListSchemasPaginateTypeDef,
     ListSchemasRequestRequestTypeDef,
+    ListSolutionVersionsRequestListSolutionVersionsPaginateTypeDef,
     ListSolutionVersionsRequestRequestTypeDef,
     SolutionVersionSummaryTypeDef,
+    ListSolutionsRequestListSolutionsPaginateTypeDef,
     ListSolutionsRequestRequestTypeDef,
     SolutionSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     OptimizationObjectiveTypeDef,
+    PaginatorConfigTypeDef,
+    TrainingDataConfigTypeDef,
+    ResponseMetadataTypeDef,
     TunedHPOParamsTypeDef,
     StartRecommenderRequestRequestTypeDef,
+    StartRecommenderResponseTypeDef,
     StopRecommenderRequestRequestTypeDef,
+    StopRecommenderResponseTypeDef,
     StopSolutionVersionCreationRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateCampaignResponseTypeDef,
+    UpdateMetricAttributionResponseTypeDef,
+    UpdateRecommenderResponseTypeDef,
     BatchInferenceJobInputTypeDef,
     BatchInferenceJobOutputTypeDef,
     BatchSegmentJobInputTypeDef,
     BatchSegmentJobOutputTypeDef,
     DatasetExportJobOutputTypeDef,
     MetricAttributionOutputTypeDef,
+    ListBatchInferenceJobsResponseTypeDef,
+    ListBatchSegmentJobsResponseTypeDef,
     CampaignUpdateSummaryTypeDef,
     UpdateCampaignRequestRequestTypeDef,
+    ListCampaignsResponseTypeDef,
     CreateCampaignRequestRequestTypeDef,
     CreateDatasetGroupRequestRequestTypeDef,
     CreateDatasetRequestRequestTypeDef,
     CreateEventTrackerRequestRequestTypeDef,
     CreateFilterRequestRequestTypeDef,
     CreateSolutionVersionRequestRequestTypeDef,
-    TagResourceRequestRequestTypeDef,
-    CreateBatchInferenceJobResponseTypeDef,
-    CreateBatchSegmentJobResponseTypeDef,
-    CreateCampaignResponseTypeDef,
-    CreateDatasetExportJobResponseTypeDef,
-    CreateDatasetGroupResponseTypeDef,
-    CreateDatasetImportJobResponseTypeDef,
-    CreateDatasetResponseTypeDef,
-    CreateEventTrackerResponseTypeDef,
-    CreateFilterResponseTypeDef,
-    CreateMetricAttributionResponseTypeDef,
-    CreateRecommenderResponseTypeDef,
-    CreateSchemaResponseTypeDef,
-    CreateSolutionResponseTypeDef,
-    CreateSolutionVersionResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetSolutionMetricsResponseTypeDef,
-    ListBatchInferenceJobsResponseTypeDef,
-    ListBatchSegmentJobsResponseTypeDef,
-    ListCampaignsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
-    StartRecommenderResponseTypeDef,
-    StopRecommenderResponseTypeDef,
-    UpdateCampaignResponseTypeDef,
-    UpdateMetricAttributionResponseTypeDef,
-    UpdateRecommenderResponseTypeDef,
+    TagResourceRequestRequestTypeDef,
     CreateDatasetImportJobRequestRequestTypeDef,
     DatasetImportJobTypeDef,
     ListMetricAttributionMetricsResponseTypeDef,
-    CreateRecommenderRequestRequestTypeDef,
-    RecommenderSummaryTypeDef,
-    RecommenderUpdateSummaryTypeDef,
-    UpdateRecommenderRequestRequestTypeDef,
     ListDatasetExportJobsResponseTypeDef,
     ListDatasetGroupsResponseTypeDef,
     DescribeDatasetGroupResponseTypeDef,
     ListDatasetImportJobsResponseTypeDef,
     ListSchemasResponseTypeDef,
     DescribeSchemaResponseTypeDef,
     ListDatasetsResponseTypeDef,
@@ -542,60 +554,49 @@
     DescribeEventTrackerResponseTypeDef,
     DescribeFeatureTransformationResponseTypeDef,
     DescribeFilterResponseTypeDef,
     DescribeRecipeResponseTypeDef,
     ListEventTrackersResponseTypeDef,
     ListFiltersResponseTypeDef,
     HyperParameterRangesTypeDef,
-    ListBatchInferenceJobsRequestListBatchInferenceJobsPaginateTypeDef,
-    ListBatchSegmentJobsRequestListBatchSegmentJobsPaginateTypeDef,
-    ListCampaignsRequestListCampaignsPaginateTypeDef,
-    ListDatasetExportJobsRequestListDatasetExportJobsPaginateTypeDef,
-    ListDatasetGroupsRequestListDatasetGroupsPaginateTypeDef,
-    ListDatasetImportJobsRequestListDatasetImportJobsPaginateTypeDef,
-    ListDatasetsRequestListDatasetsPaginateTypeDef,
-    ListEventTrackersRequestListEventTrackersPaginateTypeDef,
-    ListFiltersRequestListFiltersPaginateTypeDef,
-    ListMetricAttributionMetricsRequestListMetricAttributionMetricsPaginateTypeDef,
-    ListMetricAttributionsRequestListMetricAttributionsPaginateTypeDef,
-    ListRecipesRequestListRecipesPaginateTypeDef,
-    ListRecommendersRequestListRecommendersPaginateTypeDef,
-    ListSchemasRequestListSchemasPaginateTypeDef,
-    ListSolutionVersionsRequestListSolutionVersionsPaginateTypeDef,
-    ListSolutionsRequestListSolutionsPaginateTypeDef,
     ListMetricAttributionsResponseTypeDef,
     ListRecipesResponseTypeDef,
     ListSolutionVersionsResponseTypeDef,
     ListSolutionsResponseTypeDef,
+    RecommenderConfigTypeDef,
     BatchInferenceJobTypeDef,
     CreateBatchInferenceJobRequestRequestTypeDef,
     BatchSegmentJobTypeDef,
     CreateBatchSegmentJobRequestRequestTypeDef,
     CreateDatasetExportJobRequestRequestTypeDef,
     DatasetExportJobTypeDef,
     CreateMetricAttributionRequestRequestTypeDef,
     MetricAttributionTypeDef,
     UpdateMetricAttributionRequestRequestTypeDef,
     CampaignTypeDef,
     DescribeDatasetImportJobResponseTypeDef,
-    ListRecommendersResponseTypeDef,
-    RecommenderTypeDef,
     AlgorithmTypeDef,
     HPOConfigTypeDef,
+    CreateRecommenderRequestRequestTypeDef,
+    RecommenderSummaryTypeDef,
+    RecommenderUpdateSummaryTypeDef,
+    UpdateRecommenderRequestRequestTypeDef,
     DescribeBatchInferenceJobResponseTypeDef,
     DescribeBatchSegmentJobResponseTypeDef,
     DescribeDatasetExportJobResponseTypeDef,
     DescribeMetricAttributionResponseTypeDef,
     DescribeCampaignResponseTypeDef,
-    DescribeRecommenderResponseTypeDef,
     DescribeAlgorithmResponseTypeDef,
     SolutionConfigTypeDef,
+    ListRecommendersResponseTypeDef,
+    RecommenderTypeDef,
     CreateSolutionRequestRequestTypeDef,
     SolutionTypeDef,
     SolutionVersionTypeDef,
+    DescribeRecommenderResponseTypeDef,
     DescribeSolutionResponseTypeDef,
     DescribeSolutionVersionResponseTypeDef,
 )
 
 
 def get_structure() -> AlgorithmImageTypeDef:
     return {...}
@@ -604,43 +605,43 @@
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

### Comparing `types-aiobotocore-personalize-2.5.0.post1/types_aiobotocore_personalize.egg-info/SOURCES.txt` & `types-aiobotocore-personalize-2.5.1/types_aiobotocore_personalize.egg-info/SOURCES.txt`

 * *Files identical despite different names*

