# Comparing `tmp/types-aiobotocore-comprehend-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-comprehend-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-comprehend-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:24 2023, max compression
+gzip compressed data, was "types-aiobotocore-comprehend-2.5.1.tar", last modified: Wed Jun 28 01:43:18 2023, max compression
```

## Comparing `types-aiobotocore-comprehend-2.5.0.post1.tar` & `types-aiobotocore-comprehend-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:24.935074 types-aiobotocore-comprehend-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:11:36.000000 types-aiobotocore-comprehend-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    26056 2023-03-11 12:26:24.935074 types-aiobotocore-comprehend-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    24473 2023-03-11 12:11:36.000000 types-aiobotocore-comprehend-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:24.935074 types-aiobotocore-comprehend-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2145 2023-03-11 12:11:36.000000 types-aiobotocore-comprehend-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:24.935074 types-aiobotocore-comprehend-2.5.0.post1/types_aiobotocore_comprehend/
--rw-r--r--   0 runner    (1001) docker     (123)     3097 2023-03-11 12:11:36.000000 types-aiobotocore-comprehend-2.5.0.post1/types_aiobotocore_comprehend/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3096 2023-03-11 12:11:36.000000 types-aiobotocore-comprehend-2.5.0.post1/types_aiobotocore_comprehend/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      955 2023-03-11 12:11:36.000000 types-aiobotocore-comprehend-2.5.0.post1/types_aiobotocore_comprehend/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    62622 2023-03-11 12:11:38.000000 types-aiobotocore-comprehend-2.5.0.post1/types_aiobotocore_comprehend/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    62530 2023-03-11 12:11:38.000000 types-aiobotocore-comprehend-2.5.0.post1/types_aiobotocore_comprehend/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    13527 2023-03-11 12:11:38.000000 types-aiobotocore-comprehend-2.5.0.post1/types_aiobotocore_comprehend/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    13525 2023-03-11 12:11:38.000000 types-aiobotocore-comprehend-2.5.0.post1/types_aiobotocore_comprehend/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    14281 2023-03-11 12:11:38.000000 types-aiobotocore-comprehend-2.5.0.post1/types_aiobotocore_comprehend/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    14268 2023-03-11 12:11:38.000000 types-aiobotocore-comprehend-2.5.0.post1/types_aiobotocore_comprehend/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:11:36.000000 types-aiobotocore-comprehend-2.5.0.post1/types_aiobotocore_comprehend/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    80573 2023-03-11 12:11:40.000000 types-aiobotocore-comprehend-2.5.0.post1/types_aiobotocore_comprehend/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    80520 2023-03-11 12:11:39.000000 types-aiobotocore-comprehend-2.5.0.post1/types_aiobotocore_comprehend/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:11:36.000000 types-aiobotocore-comprehend-2.5.0.post1/types_aiobotocore_comprehend/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:24.935074 types-aiobotocore-comprehend-2.5.0.post1/types_aiobotocore_comprehend.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    26056 2023-03-11 12:26:24.000000 types-aiobotocore-comprehend-2.5.0.post1/types_aiobotocore_comprehend.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      870 2023-03-11 12:26:24.000000 types-aiobotocore-comprehend-2.5.0.post1/types_aiobotocore_comprehend.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:24.000000 types-aiobotocore-comprehend-2.5.0.post1/types_aiobotocore_comprehend.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:24.000000 types-aiobotocore-comprehend-2.5.0.post1/types_aiobotocore_comprehend.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:24.000000 types-aiobotocore-comprehend-2.5.0.post1/types_aiobotocore_comprehend.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       29 2023-03-11 12:26:24.000000 types-aiobotocore-comprehend-2.5.0.post1/types_aiobotocore_comprehend.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:18.070115 types-aiobotocore-comprehend-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:28:14.000000 types-aiobotocore-comprehend-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    28040 2023-06-28 01:43:18.070115 types-aiobotocore-comprehend-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    26463 2023-06-28 01:28:14.000000 types-aiobotocore-comprehend-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:18.070115 types-aiobotocore-comprehend-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2139 2023-06-28 01:28:14.000000 types-aiobotocore-comprehend-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:18.070115 types-aiobotocore-comprehend-2.5.1/types_aiobotocore_comprehend/
+-rw-r--r--   0 runner    (1001) docker     (123)     3097 2023-06-28 01:28:14.000000 types-aiobotocore-comprehend-2.5.1/types_aiobotocore_comprehend/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3096 2023-06-28 01:28:14.000000 types-aiobotocore-comprehend-2.5.1/types_aiobotocore_comprehend/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      943 2023-06-28 01:28:14.000000 types-aiobotocore-comprehend-2.5.1/types_aiobotocore_comprehend/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    70387 2023-06-28 01:28:14.000000 types-aiobotocore-comprehend-2.5.1/types_aiobotocore_comprehend/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    70284 2023-06-28 01:28:14.000000 types-aiobotocore-comprehend-2.5.1/types_aiobotocore_comprehend/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    14746 2023-06-28 01:28:16.000000 types-aiobotocore-comprehend-2.5.1/types_aiobotocore_comprehend/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14744 2023-06-28 01:28:15.000000 types-aiobotocore-comprehend-2.5.1/types_aiobotocore_comprehend/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    14205 2023-06-28 01:28:15.000000 types-aiobotocore-comprehend-2.5.1/types_aiobotocore_comprehend/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14193 2023-06-28 01:28:15.000000 types-aiobotocore-comprehend-2.5.1/types_aiobotocore_comprehend/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:28:14.000000 types-aiobotocore-comprehend-2.5.1/types_aiobotocore_comprehend/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    98662 2023-06-28 01:28:17.000000 types-aiobotocore-comprehend-2.5.1/types_aiobotocore_comprehend/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    98585 2023-06-28 01:28:16.000000 types-aiobotocore-comprehend-2.5.1/types_aiobotocore_comprehend/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:28:14.000000 types-aiobotocore-comprehend-2.5.1/types_aiobotocore_comprehend/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:18.070115 types-aiobotocore-comprehend-2.5.1/types_aiobotocore_comprehend.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    28040 2023-06-28 01:43:17.000000 types-aiobotocore-comprehend-2.5.1/types_aiobotocore_comprehend.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      870 2023-06-28 01:43:17.000000 types-aiobotocore-comprehend-2.5.1/types_aiobotocore_comprehend.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:17.000000 types-aiobotocore-comprehend-2.5.1/types_aiobotocore_comprehend.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:17.000000 types-aiobotocore-comprehend-2.5.1/types_aiobotocore_comprehend.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:17.000000 types-aiobotocore-comprehend-2.5.1/types_aiobotocore_comprehend.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       29 2023-06-28 01:43:17.000000 types-aiobotocore-comprehend-2.5.1/types_aiobotocore_comprehend.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-comprehend-2.5.0.post1/LICENSE` & `types-aiobotocore-comprehend-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-comprehend-2.5.0.post1/PKG-INFO` & `types-aiobotocore-comprehend-2.5.1/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-comprehend
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Comprehend 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Comprehend 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-comprehend"></a>
 
 # types-aiobotocore-comprehend
 
 [![PyPI - types-aiobotocore-comprehend](https://img.shields.io/pypi/v/types-aiobotocore-comprehend.svg?color=blue)](https://pypi.org/project/types-aiobotocore-comprehend)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-comprehend.svg?color=blue)](https://pypi.org/project/types-aiobotocore-comprehend)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-comprehend?color=blue)](https://pypistats.org/packages/types-aiobotocore-comprehend)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Comprehend 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend)
+[aiobotocore.Comprehend 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend)
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
 [types-aiobotocore-comprehend docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/).
 
 See how it helps to find and fix potential bugs:
 
@@ -332,38 +332,46 @@
 `types_aiobotocore_comprehend.literals` module contains literals extracted from
 shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_comprehend.literals import (
     AugmentedManifestsDocumentTypeFormatType,
     BlockTypeType,
+    DatasetDataFormatType,
+    DatasetStatusType,
+    DatasetTypeType,
     DocumentClassifierDataFormatType,
+    DocumentClassifierDocumentTypeFormatType,
     DocumentClassifierModeType,
     DocumentReadActionType,
     DocumentReadFeatureTypesType,
     DocumentReadModeType,
     DocumentTypeType,
     EndpointStatusType,
     EntityRecognizerDataFormatType,
     EntityTypeType,
+    FlywheelIterationStatusType,
+    FlywheelStatusType,
     InputFormatType,
     JobStatusType,
     LanguageCodeType,
     ListDocumentClassificationJobsPaginatorName,
     ListDocumentClassifiersPaginatorName,
     ListDominantLanguageDetectionJobsPaginatorName,
     ListEndpointsPaginatorName,
     ListEntitiesDetectionJobsPaginatorName,
     ListEntityRecognizersPaginatorName,
     ListKeyPhrasesDetectionJobsPaginatorName,
     ListPiiEntitiesDetectionJobsPaginatorName,
     ListSentimentDetectionJobsPaginatorName,
     ListTopicsDetectionJobsPaginatorName,
     ModelStatusType,
+    ModelTypeType,
     PageBasedErrorCodeType,
+    PageBasedWarningCodeType,
     PartOfSpeechTagTypeType,
     PiiEntitiesDetectionMaskModeType,
     PiiEntitiesDetectionModeType,
     PiiEntityTypeType,
     RelationshipTypeType,
     SentimentTypeType,
     SplitType,
@@ -390,15 +398,14 @@
 
 ```python
 from types_aiobotocore_comprehend.type_defs import (
     AugmentedManifestsListItemTypeDef,
     DominantLanguageTypeDef,
     BatchDetectDominantLanguageRequestRequestTypeDef,
     BatchItemErrorTypeDef,
-    ResponseMetadataTypeDef,
     BatchDetectEntitiesRequestRequestTypeDef,
     KeyPhraseTypeDef,
     BatchDetectKeyPhrasesRequestRequestTypeDef,
     SentimentScoreTypeDef,
     BatchDetectSentimentRequestRequestTypeDef,
     BatchDetectSyntaxRequestRequestTypeDef,
     BatchDetectTargetedSentimentRequestRequestTypeDef,
@@ -407,111 +414,135 @@
     BoundingBoxTypeDef,
     ClassifierEvaluationMetricsTypeDef,
     DocumentReaderConfigTypeDef,
     DocumentClassTypeDef,
     DocumentLabelTypeDef,
     DocumentTypeListItemTypeDef,
     ErrorsListItemTypeDef,
+    WarningsListItemTypeDef,
     ContainsPiiEntitiesRequestRequestTypeDef,
     EntityLabelTypeDef,
-    DocumentClassifierOutputDataConfigTypeDef,
     TagTypeDef,
+    CreateDatasetResponseTypeDef,
+    DocumentClassifierOutputDataConfigTypeDef,
     VpcConfigTypeDef,
+    CreateDocumentClassifierResponseTypeDef,
+    CreateEndpointResponseTypeDef,
+    CreateEntityRecognizerResponseTypeDef,
+    CreateFlywheelResponseTypeDef,
+    DatasetAugmentedManifestsListItemTypeDef,
+    DatasetDocumentClassifierInputDataConfigTypeDef,
+    DatasetEntityRecognizerAnnotationsTypeDef,
+    DatasetEntityRecognizerDocumentsTypeDef,
+    DatasetEntityRecognizerEntityListTypeDef,
+    DatasetFilterTypeDef,
+    DatasetPropertiesTypeDef,
     DeleteDocumentClassifierRequestRequestTypeDef,
     DeleteEndpointRequestRequestTypeDef,
     DeleteEntityRecognizerRequestRequestTypeDef,
+    DeleteFlywheelRequestRequestTypeDef,
     DeleteResourcePolicyRequestRequestTypeDef,
+    DescribeDatasetRequestRequestTypeDef,
     DescribeDocumentClassificationJobRequestRequestTypeDef,
     DescribeDocumentClassifierRequestRequestTypeDef,
     DescribeDominantLanguageDetectionJobRequestRequestTypeDef,
     DescribeEndpointRequestRequestTypeDef,
     EndpointPropertiesTypeDef,
     DescribeEntitiesDetectionJobRequestRequestTypeDef,
     DescribeEntityRecognizerRequestRequestTypeDef,
     DescribeEventsDetectionJobRequestRequestTypeDef,
+    DescribeFlywheelIterationRequestRequestTypeDef,
+    DescribeFlywheelRequestRequestTypeDef,
     DescribeKeyPhrasesDetectionJobRequestRequestTypeDef,
     DescribePiiEntitiesDetectionJobRequestRequestTypeDef,
     DescribeResourcePolicyRequestRequestTypeDef,
+    DescribeResourcePolicyResponseTypeDef,
     DescribeSentimentDetectionJobRequestRequestTypeDef,
     DescribeTargetedSentimentDetectionJobRequestRequestTypeDef,
     DescribeTopicsDetectionJobRequestRequestTypeDef,
     DetectDominantLanguageRequestRequestTypeDef,
     DetectKeyPhrasesRequestRequestTypeDef,
     DetectPiiEntitiesRequestRequestTypeDef,
     PiiEntityTypeDef,
     DetectSentimentRequestRequestTypeDef,
     DetectSyntaxRequestRequestTypeDef,
     DetectTargetedSentimentRequestRequestTypeDef,
+    DocumentClassificationConfigTypeDef,
     DocumentClassificationJobFilterTypeDef,
     OutputDataConfigTypeDef,
+    DocumentClassifierDocumentsTypeDef,
     DocumentClassifierFilterTypeDef,
     DocumentClassifierSummaryTypeDef,
     ExtractedCharactersListItemTypeDef,
     DominantLanguageDetectionJobFilterTypeDef,
     EndpointFilterTypeDef,
     EntitiesDetectionJobFilterTypeDef,
+    EntityTypesListItemTypeDef,
     EntityRecognizerAnnotationsTypeDef,
     EntityRecognizerDocumentsTypeDef,
     EntityRecognizerEntityListTypeDef,
     EntityRecognizerEvaluationMetricsTypeDef,
     EntityRecognizerFilterTypeDef,
-    EntityTypesListItemTypeDef,
     EntityTypesEvaluationMetricsTypeDef,
+    EntityRecognizerOutputDataConfigTypeDef,
     EntityRecognizerSummaryTypeDef,
     EventsDetectionJobFilterTypeDef,
+    FlywheelFilterTypeDef,
+    FlywheelIterationFilterTypeDef,
+    FlywheelModelEvaluationMetricsTypeDef,
+    FlywheelSummaryTypeDef,
     PointTypeDef,
+    ImportModelResponseTypeDef,
     KeyPhrasesDetectionJobFilterTypeDef,
-    PaginatorConfigTypeDef,
     ListDocumentClassifierSummariesRequestRequestTypeDef,
     ListEntityRecognizerSummariesRequestRequestTypeDef,
     PiiEntitiesDetectionJobFilterTypeDef,
     SentimentDetectionJobFilterTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     TargetedSentimentDetectionJobFilterTypeDef,
     TopicsDetectionJobFilterTypeDef,
+    PaginatorConfigTypeDef,
     PartOfSpeechTagTypeDef,
     PiiOutputDataConfigTypeDef,
     RedactionConfigTypeDef,
     PutResourcePolicyRequestRequestTypeDef,
-    StopDominantLanguageDetectionJobRequestRequestTypeDef,
-    StopEntitiesDetectionJobRequestRequestTypeDef,
-    StopEventsDetectionJobRequestRequestTypeDef,
-    StopKeyPhrasesDetectionJobRequestRequestTypeDef,
-    StopPiiEntitiesDetectionJobRequestRequestTypeDef,
-    StopSentimentDetectionJobRequestRequestTypeDef,
-    StopTargetedSentimentDetectionJobRequestRequestTypeDef,
-    StopTrainingDocumentClassifierRequestRequestTypeDef,
-    StopTrainingEntityRecognizerRequestRequestTypeDef,
-    UntagResourceRequestRequestTypeDef,
-    UpdateEndpointRequestRequestTypeDef,
-    DocumentClassifierInputDataConfigTypeDef,
-    BatchDetectDominantLanguageItemResultTypeDef,
-    CreateDocumentClassifierResponseTypeDef,
-    CreateEndpointResponseTypeDef,
-    CreateEntityRecognizerResponseTypeDef,
-    DescribeResourcePolicyResponseTypeDef,
-    DetectDominantLanguageResponseTypeDef,
-    ImportModelResponseTypeDef,
     PutResourcePolicyResponseTypeDef,
+    ResponseMetadataTypeDef,
     StartDocumentClassificationJobResponseTypeDef,
     StartDominantLanguageDetectionJobResponseTypeDef,
     StartEntitiesDetectionJobResponseTypeDef,
     StartEventsDetectionJobResponseTypeDef,
+    StartFlywheelIterationRequestRequestTypeDef,
+    StartFlywheelIterationResponseTypeDef,
     StartKeyPhrasesDetectionJobResponseTypeDef,
     StartPiiEntitiesDetectionJobResponseTypeDef,
     StartSentimentDetectionJobResponseTypeDef,
     StartTargetedSentimentDetectionJobResponseTypeDef,
     StartTopicsDetectionJobResponseTypeDef,
+    StopDominantLanguageDetectionJobRequestRequestTypeDef,
     StopDominantLanguageDetectionJobResponseTypeDef,
+    StopEntitiesDetectionJobRequestRequestTypeDef,
     StopEntitiesDetectionJobResponseTypeDef,
+    StopEventsDetectionJobRequestRequestTypeDef,
     StopEventsDetectionJobResponseTypeDef,
+    StopKeyPhrasesDetectionJobRequestRequestTypeDef,
     StopKeyPhrasesDetectionJobResponseTypeDef,
+    StopPiiEntitiesDetectionJobRequestRequestTypeDef,
     StopPiiEntitiesDetectionJobResponseTypeDef,
+    StopSentimentDetectionJobRequestRequestTypeDef,
     StopSentimentDetectionJobResponseTypeDef,
+    StopTargetedSentimentDetectionJobRequestRequestTypeDef,
     StopTargetedSentimentDetectionJobResponseTypeDef,
+    StopTrainingDocumentClassifierRequestRequestTypeDef,
+    StopTrainingEntityRecognizerRequestRequestTypeDef,
+    UntagResourceRequestRequestTypeDef,
+    UpdateEndpointRequestRequestTypeDef,
+    UpdateEndpointResponseTypeDef,
+    BatchDetectDominantLanguageItemResultTypeDef,
+    DetectDominantLanguageResponseTypeDef,
     BatchDetectKeyPhrasesItemResultTypeDef,
     DetectKeyPhrasesResponseTypeDef,
     BatchDetectSentimentItemResultTypeDef,
     DetectSentimentResponseTypeDef,
     MentionSentimentTypeDef,
     BlockReferenceTypeDef,
     ClassifierMetadataTypeDef,
@@ -519,53 +550,63 @@
     DetectEntitiesRequestRequestTypeDef,
     InputDataConfigTypeDef,
     ContainsPiiEntitiesResponseTypeDef,
     CreateEndpointRequestRequestTypeDef,
     ImportModelRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
+    DataSecurityConfigTypeDef,
+    UpdateDataSecurityConfigTypeDef,
+    DatasetEntityRecognizerInputDataConfigTypeDef,
+    ListDatasetsRequestRequestTypeDef,
+    DescribeDatasetResponseTypeDef,
+    ListDatasetsResponseTypeDef,
     DescribeEndpointResponseTypeDef,
     ListEndpointsResponseTypeDef,
     DetectPiiEntitiesResponseTypeDef,
+    ListDocumentClassificationJobsRequestListDocumentClassificationJobsPaginateTypeDef,
     ListDocumentClassificationJobsRequestRequestTypeDef,
+    DocumentClassifierInputDataConfigTypeDef,
+    ListDocumentClassifiersRequestListDocumentClassifiersPaginateTypeDef,
     ListDocumentClassifiersRequestRequestTypeDef,
     ListDocumentClassifierSummariesResponseTypeDef,
     DocumentMetadataTypeDef,
+    ListDominantLanguageDetectionJobsRequestListDominantLanguageDetectionJobsPaginateTypeDef,
     ListDominantLanguageDetectionJobsRequestRequestTypeDef,
+    ListEndpointsRequestListEndpointsPaginateTypeDef,
     ListEndpointsRequestRequestTypeDef,
+    ListEntitiesDetectionJobsRequestListEntitiesDetectionJobsPaginateTypeDef,
     ListEntitiesDetectionJobsRequestRequestTypeDef,
-    ListEntityRecognizersRequestRequestTypeDef,
+    EntityRecognitionConfigTypeDef,
     EntityRecognizerInputDataConfigTypeDef,
+    ListEntityRecognizersRequestListEntityRecognizersPaginateTypeDef,
+    ListEntityRecognizersRequestRequestTypeDef,
     EntityRecognizerMetadataEntityTypesListItemTypeDef,
     ListEntityRecognizerSummariesResponseTypeDef,
     ListEventsDetectionJobsRequestRequestTypeDef,
+    ListFlywheelsRequestRequestTypeDef,
+    ListFlywheelIterationHistoryRequestRequestTypeDef,
+    FlywheelIterationPropertiesTypeDef,
+    ListFlywheelsResponseTypeDef,
     GeometryTypeDef,
-    ListKeyPhrasesDetectionJobsRequestRequestTypeDef,
-    ListDocumentClassificationJobsRequestListDocumentClassificationJobsPaginateTypeDef,
-    ListDocumentClassifiersRequestListDocumentClassifiersPaginateTypeDef,
-    ListDominantLanguageDetectionJobsRequestListDominantLanguageDetectionJobsPaginateTypeDef,
-    ListEndpointsRequestListEndpointsPaginateTypeDef,
-    ListEntitiesDetectionJobsRequestListEntitiesDetectionJobsPaginateTypeDef,
-    ListEntityRecognizersRequestListEntityRecognizersPaginateTypeDef,
     ListKeyPhrasesDetectionJobsRequestListKeyPhrasesDetectionJobsPaginateTypeDef,
+    ListKeyPhrasesDetectionJobsRequestRequestTypeDef,
     ListPiiEntitiesDetectionJobsRequestListPiiEntitiesDetectionJobsPaginateTypeDef,
     ListPiiEntitiesDetectionJobsRequestRequestTypeDef,
     ListSentimentDetectionJobsRequestListSentimentDetectionJobsPaginateTypeDef,
     ListSentimentDetectionJobsRequestRequestTypeDef,
     ListTargetedSentimentDetectionJobsRequestRequestTypeDef,
     ListTopicsDetectionJobsRequestListTopicsDetectionJobsPaginateTypeDef,
     ListTopicsDetectionJobsRequestRequestTypeDef,
     SyntaxTokenTypeDef,
-    CreateDocumentClassifierRequestRequestTypeDef,
     BatchDetectDominantLanguageResponseTypeDef,
     BatchDetectKeyPhrasesResponseTypeDef,
     BatchDetectSentimentResponseTypeDef,
     TargetedSentimentMentionTypeDef,
     EntityTypeDef,
-    DocumentClassifierPropertiesTypeDef,
     DocumentClassificationJobPropertiesTypeDef,
     DominantLanguageDetectionJobPropertiesTypeDef,
     EntitiesDetectionJobPropertiesTypeDef,
     EventsDetectionJobPropertiesTypeDef,
     KeyPhrasesDetectionJobPropertiesTypeDef,
     PiiEntitiesDetectionJobPropertiesTypeDef,
     SentimentDetectionJobPropertiesTypeDef,
@@ -576,24 +617,29 @@
     StartKeyPhrasesDetectionJobRequestRequestTypeDef,
     StartPiiEntitiesDetectionJobRequestRequestTypeDef,
     StartSentimentDetectionJobRequestRequestTypeDef,
     StartTargetedSentimentDetectionJobRequestRequestTypeDef,
     StartTopicsDetectionJobRequestRequestTypeDef,
     TargetedSentimentDetectionJobPropertiesTypeDef,
     TopicsDetectionJobPropertiesTypeDef,
+    UpdateFlywheelRequestRequestTypeDef,
+    DatasetInputDataConfigTypeDef,
+    CreateDocumentClassifierRequestRequestTypeDef,
+    DocumentClassifierPropertiesTypeDef,
     ClassifyDocumentResponseTypeDef,
+    TaskConfigTypeDef,
     CreateEntityRecognizerRequestRequestTypeDef,
     EntityRecognizerMetadataTypeDef,
+    DescribeFlywheelIterationResponseTypeDef,
+    ListFlywheelIterationHistoryResponseTypeDef,
     BlockTypeDef,
     BatchDetectSyntaxItemResultTypeDef,
     DetectSyntaxResponseTypeDef,
     TargetedSentimentEntityTypeDef,
     BatchDetectEntitiesItemResultTypeDef,
-    DescribeDocumentClassifierResponseTypeDef,
-    ListDocumentClassifiersResponseTypeDef,
     DescribeDocumentClassificationJobResponseTypeDef,
     ListDocumentClassificationJobsResponseTypeDef,
     DescribeDominantLanguageDetectionJobResponseTypeDef,
     ListDominantLanguageDetectionJobsResponseTypeDef,
     DescribeEntitiesDetectionJobResponseTypeDef,
     ListEntitiesDetectionJobsResponseTypeDef,
     DescribeEventsDetectionJobResponseTypeDef,
@@ -604,20 +650,27 @@
     ListPiiEntitiesDetectionJobsResponseTypeDef,
     DescribeSentimentDetectionJobResponseTypeDef,
     ListSentimentDetectionJobsResponseTypeDef,
     DescribeTargetedSentimentDetectionJobResponseTypeDef,
     ListTargetedSentimentDetectionJobsResponseTypeDef,
     DescribeTopicsDetectionJobResponseTypeDef,
     ListTopicsDetectionJobsResponseTypeDef,
+    CreateDatasetRequestRequestTypeDef,
+    DescribeDocumentClassifierResponseTypeDef,
+    ListDocumentClassifiersResponseTypeDef,
+    CreateFlywheelRequestRequestTypeDef,
+    FlywheelPropertiesTypeDef,
     EntityRecognizerPropertiesTypeDef,
     DetectEntitiesResponseTypeDef,
     BatchDetectSyntaxResponseTypeDef,
     BatchDetectTargetedSentimentItemResultTypeDef,
     DetectTargetedSentimentResponseTypeDef,
     BatchDetectEntitiesResponseTypeDef,
+    DescribeFlywheelResponseTypeDef,
+    UpdateFlywheelResponseTypeDef,
     DescribeEntityRecognizerResponseTypeDef,
     ListEntityRecognizersResponseTypeDef,
     BatchDetectTargetedSentimentResponseTypeDef,
 )
 
 
 def get_structure() -> AugmentedManifestsListItemTypeDef:
@@ -627,43 +680,43 @@
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

### Comparing `types-aiobotocore-comprehend-2.5.0.post1/README.md` & `types-aiobotocore-comprehend-2.5.1/types_aiobotocore_comprehend.egg-info/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,29 +1,62 @@
+Metadata-Version: 2.1
+Name: types-aiobotocore-comprehend
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Comprehend 2.5.1 service generated with mypy-boto3-builder 7.14.5
+Home-page: https://github.com/youtype/mypy_boto3_builder
+Author: Vlad Emelianov
+Author-email: vlad.emelianov.nz@gmail.com
+License: MIT License
+Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/
+Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
+Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
+Keywords: aiobotocore comprehend type-annotations boto3-stubs mypy typeshed autocomplete
+Classifier: Development Status :: 5 - Production/Stable
+Classifier: Intended Audience :: Developers
+Classifier: Environment :: Console
+Classifier: License :: OSI Approved :: MIT License
+Classifier: Natural Language :: English
+Classifier: Operating System :: OS Independent
+Classifier: Programming Language :: Python :: 3
+Classifier: Programming Language :: Python :: 3.7
+Classifier: Programming Language :: Python :: 3.7
+Classifier: Programming Language :: Python :: 3.8
+Classifier: Programming Language :: Python :: 3.9
+Classifier: Programming Language :: Python :: 3.10
+Classifier: Programming Language :: Python :: 3.11
+Classifier: Programming Language :: Python :: 3.12
+Classifier: Programming Language :: Python :: 3 :: Only
+Classifier: Programming Language :: Python :: Implementation :: CPython
+Classifier: Typing :: Typed
+Requires-Python: >=3.7
+Description-Content-Type: text/markdown
+License-File: LICENSE
+
 <a id="types-aiobotocore-comprehend"></a>
 
 # types-aiobotocore-comprehend
 
 [![PyPI - types-aiobotocore-comprehend](https://img.shields.io/pypi/v/types-aiobotocore-comprehend.svg?color=blue)](https://pypi.org/project/types-aiobotocore-comprehend)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-comprehend.svg?color=blue)](https://pypi.org/project/types-aiobotocore-comprehend)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-comprehend?color=blue)](https://pypistats.org/packages/types-aiobotocore-comprehend)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Comprehend 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend)
+[aiobotocore.Comprehend 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend)
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
 [types-aiobotocore-comprehend docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/).
 
 See how it helps to find and fix potential bugs:
 
@@ -299,38 +332,46 @@
 `types_aiobotocore_comprehend.literals` module contains literals extracted from
 shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_comprehend.literals import (
     AugmentedManifestsDocumentTypeFormatType,
     BlockTypeType,
+    DatasetDataFormatType,
+    DatasetStatusType,
+    DatasetTypeType,
     DocumentClassifierDataFormatType,
+    DocumentClassifierDocumentTypeFormatType,
     DocumentClassifierModeType,
     DocumentReadActionType,
     DocumentReadFeatureTypesType,
     DocumentReadModeType,
     DocumentTypeType,
     EndpointStatusType,
     EntityRecognizerDataFormatType,
     EntityTypeType,
+    FlywheelIterationStatusType,
+    FlywheelStatusType,
     InputFormatType,
     JobStatusType,
     LanguageCodeType,
     ListDocumentClassificationJobsPaginatorName,
     ListDocumentClassifiersPaginatorName,
     ListDominantLanguageDetectionJobsPaginatorName,
     ListEndpointsPaginatorName,
     ListEntitiesDetectionJobsPaginatorName,
     ListEntityRecognizersPaginatorName,
     ListKeyPhrasesDetectionJobsPaginatorName,
     ListPiiEntitiesDetectionJobsPaginatorName,
     ListSentimentDetectionJobsPaginatorName,
     ListTopicsDetectionJobsPaginatorName,
     ModelStatusType,
+    ModelTypeType,
     PageBasedErrorCodeType,
+    PageBasedWarningCodeType,
     PartOfSpeechTagTypeType,
     PiiEntitiesDetectionMaskModeType,
     PiiEntitiesDetectionModeType,
     PiiEntityTypeType,
     RelationshipTypeType,
     SentimentTypeType,
     SplitType,
@@ -357,15 +398,14 @@
 
 ```python
 from types_aiobotocore_comprehend.type_defs import (
     AugmentedManifestsListItemTypeDef,
     DominantLanguageTypeDef,
     BatchDetectDominantLanguageRequestRequestTypeDef,
     BatchItemErrorTypeDef,
-    ResponseMetadataTypeDef,
     BatchDetectEntitiesRequestRequestTypeDef,
     KeyPhraseTypeDef,
     BatchDetectKeyPhrasesRequestRequestTypeDef,
     SentimentScoreTypeDef,
     BatchDetectSentimentRequestRequestTypeDef,
     BatchDetectSyntaxRequestRequestTypeDef,
     BatchDetectTargetedSentimentRequestRequestTypeDef,
@@ -374,111 +414,135 @@
     BoundingBoxTypeDef,
     ClassifierEvaluationMetricsTypeDef,
     DocumentReaderConfigTypeDef,
     DocumentClassTypeDef,
     DocumentLabelTypeDef,
     DocumentTypeListItemTypeDef,
     ErrorsListItemTypeDef,
+    WarningsListItemTypeDef,
     ContainsPiiEntitiesRequestRequestTypeDef,
     EntityLabelTypeDef,
-    DocumentClassifierOutputDataConfigTypeDef,
     TagTypeDef,
+    CreateDatasetResponseTypeDef,
+    DocumentClassifierOutputDataConfigTypeDef,
     VpcConfigTypeDef,
+    CreateDocumentClassifierResponseTypeDef,
+    CreateEndpointResponseTypeDef,
+    CreateEntityRecognizerResponseTypeDef,
+    CreateFlywheelResponseTypeDef,
+    DatasetAugmentedManifestsListItemTypeDef,
+    DatasetDocumentClassifierInputDataConfigTypeDef,
+    DatasetEntityRecognizerAnnotationsTypeDef,
+    DatasetEntityRecognizerDocumentsTypeDef,
+    DatasetEntityRecognizerEntityListTypeDef,
+    DatasetFilterTypeDef,
+    DatasetPropertiesTypeDef,
     DeleteDocumentClassifierRequestRequestTypeDef,
     DeleteEndpointRequestRequestTypeDef,
     DeleteEntityRecognizerRequestRequestTypeDef,
+    DeleteFlywheelRequestRequestTypeDef,
     DeleteResourcePolicyRequestRequestTypeDef,
+    DescribeDatasetRequestRequestTypeDef,
     DescribeDocumentClassificationJobRequestRequestTypeDef,
     DescribeDocumentClassifierRequestRequestTypeDef,
     DescribeDominantLanguageDetectionJobRequestRequestTypeDef,
     DescribeEndpointRequestRequestTypeDef,
     EndpointPropertiesTypeDef,
     DescribeEntitiesDetectionJobRequestRequestTypeDef,
     DescribeEntityRecognizerRequestRequestTypeDef,
     DescribeEventsDetectionJobRequestRequestTypeDef,
+    DescribeFlywheelIterationRequestRequestTypeDef,
+    DescribeFlywheelRequestRequestTypeDef,
     DescribeKeyPhrasesDetectionJobRequestRequestTypeDef,
     DescribePiiEntitiesDetectionJobRequestRequestTypeDef,
     DescribeResourcePolicyRequestRequestTypeDef,
+    DescribeResourcePolicyResponseTypeDef,
     DescribeSentimentDetectionJobRequestRequestTypeDef,
     DescribeTargetedSentimentDetectionJobRequestRequestTypeDef,
     DescribeTopicsDetectionJobRequestRequestTypeDef,
     DetectDominantLanguageRequestRequestTypeDef,
     DetectKeyPhrasesRequestRequestTypeDef,
     DetectPiiEntitiesRequestRequestTypeDef,
     PiiEntityTypeDef,
     DetectSentimentRequestRequestTypeDef,
     DetectSyntaxRequestRequestTypeDef,
     DetectTargetedSentimentRequestRequestTypeDef,
+    DocumentClassificationConfigTypeDef,
     DocumentClassificationJobFilterTypeDef,
     OutputDataConfigTypeDef,
+    DocumentClassifierDocumentsTypeDef,
     DocumentClassifierFilterTypeDef,
     DocumentClassifierSummaryTypeDef,
     ExtractedCharactersListItemTypeDef,
     DominantLanguageDetectionJobFilterTypeDef,
     EndpointFilterTypeDef,
     EntitiesDetectionJobFilterTypeDef,
+    EntityTypesListItemTypeDef,
     EntityRecognizerAnnotationsTypeDef,
     EntityRecognizerDocumentsTypeDef,
     EntityRecognizerEntityListTypeDef,
     EntityRecognizerEvaluationMetricsTypeDef,
     EntityRecognizerFilterTypeDef,
-    EntityTypesListItemTypeDef,
     EntityTypesEvaluationMetricsTypeDef,
+    EntityRecognizerOutputDataConfigTypeDef,
     EntityRecognizerSummaryTypeDef,
     EventsDetectionJobFilterTypeDef,
+    FlywheelFilterTypeDef,
+    FlywheelIterationFilterTypeDef,
+    FlywheelModelEvaluationMetricsTypeDef,
+    FlywheelSummaryTypeDef,
     PointTypeDef,
+    ImportModelResponseTypeDef,
     KeyPhrasesDetectionJobFilterTypeDef,
-    PaginatorConfigTypeDef,
     ListDocumentClassifierSummariesRequestRequestTypeDef,
     ListEntityRecognizerSummariesRequestRequestTypeDef,
     PiiEntitiesDetectionJobFilterTypeDef,
     SentimentDetectionJobFilterTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     TargetedSentimentDetectionJobFilterTypeDef,
     TopicsDetectionJobFilterTypeDef,
+    PaginatorConfigTypeDef,
     PartOfSpeechTagTypeDef,
     PiiOutputDataConfigTypeDef,
     RedactionConfigTypeDef,
     PutResourcePolicyRequestRequestTypeDef,
-    StopDominantLanguageDetectionJobRequestRequestTypeDef,
-    StopEntitiesDetectionJobRequestRequestTypeDef,
-    StopEventsDetectionJobRequestRequestTypeDef,
-    StopKeyPhrasesDetectionJobRequestRequestTypeDef,
-    StopPiiEntitiesDetectionJobRequestRequestTypeDef,
-    StopSentimentDetectionJobRequestRequestTypeDef,
-    StopTargetedSentimentDetectionJobRequestRequestTypeDef,
-    StopTrainingDocumentClassifierRequestRequestTypeDef,
-    StopTrainingEntityRecognizerRequestRequestTypeDef,
-    UntagResourceRequestRequestTypeDef,
-    UpdateEndpointRequestRequestTypeDef,
-    DocumentClassifierInputDataConfigTypeDef,
-    BatchDetectDominantLanguageItemResultTypeDef,
-    CreateDocumentClassifierResponseTypeDef,
-    CreateEndpointResponseTypeDef,
-    CreateEntityRecognizerResponseTypeDef,
-    DescribeResourcePolicyResponseTypeDef,
-    DetectDominantLanguageResponseTypeDef,
-    ImportModelResponseTypeDef,
     PutResourcePolicyResponseTypeDef,
+    ResponseMetadataTypeDef,
     StartDocumentClassificationJobResponseTypeDef,
     StartDominantLanguageDetectionJobResponseTypeDef,
     StartEntitiesDetectionJobResponseTypeDef,
     StartEventsDetectionJobResponseTypeDef,
+    StartFlywheelIterationRequestRequestTypeDef,
+    StartFlywheelIterationResponseTypeDef,
     StartKeyPhrasesDetectionJobResponseTypeDef,
     StartPiiEntitiesDetectionJobResponseTypeDef,
     StartSentimentDetectionJobResponseTypeDef,
     StartTargetedSentimentDetectionJobResponseTypeDef,
     StartTopicsDetectionJobResponseTypeDef,
+    StopDominantLanguageDetectionJobRequestRequestTypeDef,
     StopDominantLanguageDetectionJobResponseTypeDef,
+    StopEntitiesDetectionJobRequestRequestTypeDef,
     StopEntitiesDetectionJobResponseTypeDef,
+    StopEventsDetectionJobRequestRequestTypeDef,
     StopEventsDetectionJobResponseTypeDef,
+    StopKeyPhrasesDetectionJobRequestRequestTypeDef,
     StopKeyPhrasesDetectionJobResponseTypeDef,
+    StopPiiEntitiesDetectionJobRequestRequestTypeDef,
     StopPiiEntitiesDetectionJobResponseTypeDef,
+    StopSentimentDetectionJobRequestRequestTypeDef,
     StopSentimentDetectionJobResponseTypeDef,
+    StopTargetedSentimentDetectionJobRequestRequestTypeDef,
     StopTargetedSentimentDetectionJobResponseTypeDef,
+    StopTrainingDocumentClassifierRequestRequestTypeDef,
+    StopTrainingEntityRecognizerRequestRequestTypeDef,
+    UntagResourceRequestRequestTypeDef,
+    UpdateEndpointRequestRequestTypeDef,
+    UpdateEndpointResponseTypeDef,
+    BatchDetectDominantLanguageItemResultTypeDef,
+    DetectDominantLanguageResponseTypeDef,
     BatchDetectKeyPhrasesItemResultTypeDef,
     DetectKeyPhrasesResponseTypeDef,
     BatchDetectSentimentItemResultTypeDef,
     DetectSentimentResponseTypeDef,
     MentionSentimentTypeDef,
     BlockReferenceTypeDef,
     ClassifierMetadataTypeDef,
@@ -486,53 +550,63 @@
     DetectEntitiesRequestRequestTypeDef,
     InputDataConfigTypeDef,
     ContainsPiiEntitiesResponseTypeDef,
     CreateEndpointRequestRequestTypeDef,
     ImportModelRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
+    DataSecurityConfigTypeDef,
+    UpdateDataSecurityConfigTypeDef,
+    DatasetEntityRecognizerInputDataConfigTypeDef,
+    ListDatasetsRequestRequestTypeDef,
+    DescribeDatasetResponseTypeDef,
+    ListDatasetsResponseTypeDef,
     DescribeEndpointResponseTypeDef,
     ListEndpointsResponseTypeDef,
     DetectPiiEntitiesResponseTypeDef,
+    ListDocumentClassificationJobsRequestListDocumentClassificationJobsPaginateTypeDef,
     ListDocumentClassificationJobsRequestRequestTypeDef,
+    DocumentClassifierInputDataConfigTypeDef,
+    ListDocumentClassifiersRequestListDocumentClassifiersPaginateTypeDef,
     ListDocumentClassifiersRequestRequestTypeDef,
     ListDocumentClassifierSummariesResponseTypeDef,
     DocumentMetadataTypeDef,
+    ListDominantLanguageDetectionJobsRequestListDominantLanguageDetectionJobsPaginateTypeDef,
     ListDominantLanguageDetectionJobsRequestRequestTypeDef,
+    ListEndpointsRequestListEndpointsPaginateTypeDef,
     ListEndpointsRequestRequestTypeDef,
+    ListEntitiesDetectionJobsRequestListEntitiesDetectionJobsPaginateTypeDef,
     ListEntitiesDetectionJobsRequestRequestTypeDef,
-    ListEntityRecognizersRequestRequestTypeDef,
+    EntityRecognitionConfigTypeDef,
     EntityRecognizerInputDataConfigTypeDef,
+    ListEntityRecognizersRequestListEntityRecognizersPaginateTypeDef,
+    ListEntityRecognizersRequestRequestTypeDef,
     EntityRecognizerMetadataEntityTypesListItemTypeDef,
     ListEntityRecognizerSummariesResponseTypeDef,
     ListEventsDetectionJobsRequestRequestTypeDef,
+    ListFlywheelsRequestRequestTypeDef,
+    ListFlywheelIterationHistoryRequestRequestTypeDef,
+    FlywheelIterationPropertiesTypeDef,
+    ListFlywheelsResponseTypeDef,
     GeometryTypeDef,
-    ListKeyPhrasesDetectionJobsRequestRequestTypeDef,
-    ListDocumentClassificationJobsRequestListDocumentClassificationJobsPaginateTypeDef,
-    ListDocumentClassifiersRequestListDocumentClassifiersPaginateTypeDef,
-    ListDominantLanguageDetectionJobsRequestListDominantLanguageDetectionJobsPaginateTypeDef,
-    ListEndpointsRequestListEndpointsPaginateTypeDef,
-    ListEntitiesDetectionJobsRequestListEntitiesDetectionJobsPaginateTypeDef,
-    ListEntityRecognizersRequestListEntityRecognizersPaginateTypeDef,
     ListKeyPhrasesDetectionJobsRequestListKeyPhrasesDetectionJobsPaginateTypeDef,
+    ListKeyPhrasesDetectionJobsRequestRequestTypeDef,
     ListPiiEntitiesDetectionJobsRequestListPiiEntitiesDetectionJobsPaginateTypeDef,
     ListPiiEntitiesDetectionJobsRequestRequestTypeDef,
     ListSentimentDetectionJobsRequestListSentimentDetectionJobsPaginateTypeDef,
     ListSentimentDetectionJobsRequestRequestTypeDef,
     ListTargetedSentimentDetectionJobsRequestRequestTypeDef,
     ListTopicsDetectionJobsRequestListTopicsDetectionJobsPaginateTypeDef,
     ListTopicsDetectionJobsRequestRequestTypeDef,
     SyntaxTokenTypeDef,
-    CreateDocumentClassifierRequestRequestTypeDef,
     BatchDetectDominantLanguageResponseTypeDef,
     BatchDetectKeyPhrasesResponseTypeDef,
     BatchDetectSentimentResponseTypeDef,
     TargetedSentimentMentionTypeDef,
     EntityTypeDef,
-    DocumentClassifierPropertiesTypeDef,
     DocumentClassificationJobPropertiesTypeDef,
     DominantLanguageDetectionJobPropertiesTypeDef,
     EntitiesDetectionJobPropertiesTypeDef,
     EventsDetectionJobPropertiesTypeDef,
     KeyPhrasesDetectionJobPropertiesTypeDef,
     PiiEntitiesDetectionJobPropertiesTypeDef,
     SentimentDetectionJobPropertiesTypeDef,
@@ -543,24 +617,29 @@
     StartKeyPhrasesDetectionJobRequestRequestTypeDef,
     StartPiiEntitiesDetectionJobRequestRequestTypeDef,
     StartSentimentDetectionJobRequestRequestTypeDef,
     StartTargetedSentimentDetectionJobRequestRequestTypeDef,
     StartTopicsDetectionJobRequestRequestTypeDef,
     TargetedSentimentDetectionJobPropertiesTypeDef,
     TopicsDetectionJobPropertiesTypeDef,
+    UpdateFlywheelRequestRequestTypeDef,
+    DatasetInputDataConfigTypeDef,
+    CreateDocumentClassifierRequestRequestTypeDef,
+    DocumentClassifierPropertiesTypeDef,
     ClassifyDocumentResponseTypeDef,
+    TaskConfigTypeDef,
     CreateEntityRecognizerRequestRequestTypeDef,
     EntityRecognizerMetadataTypeDef,
+    DescribeFlywheelIterationResponseTypeDef,
+    ListFlywheelIterationHistoryResponseTypeDef,
     BlockTypeDef,
     BatchDetectSyntaxItemResultTypeDef,
     DetectSyntaxResponseTypeDef,
     TargetedSentimentEntityTypeDef,
     BatchDetectEntitiesItemResultTypeDef,
-    DescribeDocumentClassifierResponseTypeDef,
-    ListDocumentClassifiersResponseTypeDef,
     DescribeDocumentClassificationJobResponseTypeDef,
     ListDocumentClassificationJobsResponseTypeDef,
     DescribeDominantLanguageDetectionJobResponseTypeDef,
     ListDominantLanguageDetectionJobsResponseTypeDef,
     DescribeEntitiesDetectionJobResponseTypeDef,
     ListEntitiesDetectionJobsResponseTypeDef,
     DescribeEventsDetectionJobResponseTypeDef,
@@ -571,20 +650,27 @@
     ListPiiEntitiesDetectionJobsResponseTypeDef,
     DescribeSentimentDetectionJobResponseTypeDef,
     ListSentimentDetectionJobsResponseTypeDef,
     DescribeTargetedSentimentDetectionJobResponseTypeDef,
     ListTargetedSentimentDetectionJobsResponseTypeDef,
     DescribeTopicsDetectionJobResponseTypeDef,
     ListTopicsDetectionJobsResponseTypeDef,
+    CreateDatasetRequestRequestTypeDef,
+    DescribeDocumentClassifierResponseTypeDef,
+    ListDocumentClassifiersResponseTypeDef,
+    CreateFlywheelRequestRequestTypeDef,
+    FlywheelPropertiesTypeDef,
     EntityRecognizerPropertiesTypeDef,
     DetectEntitiesResponseTypeDef,
     BatchDetectSyntaxResponseTypeDef,
     BatchDetectTargetedSentimentItemResultTypeDef,
     DetectTargetedSentimentResponseTypeDef,
     BatchDetectEntitiesResponseTypeDef,
+    DescribeFlywheelResponseTypeDef,
+    UpdateFlywheelResponseTypeDef,
     DescribeEntityRecognizerResponseTypeDef,
     ListEntityRecognizersResponseTypeDef,
     BatchDetectTargetedSentimentResponseTypeDef,
 )
 
 
 def get_structure() -> AugmentedManifestsListItemTypeDef:
@@ -594,43 +680,43 @@
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

### Comparing `types-aiobotocore-comprehend-2.5.0.post1/setup.py` & `types-aiobotocore-comprehend-2.5.1/setup.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-comprehend.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-comprehend",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_comprehend"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Comprehend 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.Comprehend 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/"
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

### Comparing `types-aiobotocore-comprehend-2.5.0.post1/types_aiobotocore_comprehend/__init__.py` & `types-aiobotocore-comprehend-2.5.1/types_aiobotocore_comprehend/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-comprehend-2.5.0.post1/types_aiobotocore_comprehend/__init__.pyi` & `types-aiobotocore-comprehend-2.5.1/types_aiobotocore_comprehend/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-comprehend-2.5.0.post1/types_aiobotocore_comprehend/__main__.py` & `types-aiobotocore-comprehend-2.5.1/types_aiobotocore_comprehend/__main__.py`

 * *Files 27% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Comprehend 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Comprehend 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend\nOther"
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

### Comparing `types-aiobotocore-comprehend-2.5.0.post1/types_aiobotocore_comprehend/client.py` & `types-aiobotocore-comprehend-2.5.1/types_aiobotocore_comprehend/client.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -18,16 +18,18 @@
 from typing import IO, Any, Dict, Mapping, Sequence, Type, Union, overload
 
 from aiobotocore.client import AioBaseClient
 from aiobotocore.response import StreamingBody
 from botocore.client import ClientMeta
 
 from .literals import (
+    DatasetTypeType,
     DocumentClassifierModeType,
     LanguageCodeType,
+    ModelTypeType,
     PiiEntitiesDetectionModeType,
     SyntaxLanguageCodeType,
 )
 from .paginator import (
     ListDocumentClassificationJobsPaginator,
     ListDocumentClassifiersPaginator,
     ListDominantLanguageDetectionJobsPaginator,
@@ -44,24 +46,32 @@
     BatchDetectEntitiesResponseTypeDef,
     BatchDetectKeyPhrasesResponseTypeDef,
     BatchDetectSentimentResponseTypeDef,
     BatchDetectSyntaxResponseTypeDef,
     BatchDetectTargetedSentimentResponseTypeDef,
     ClassifyDocumentResponseTypeDef,
     ContainsPiiEntitiesResponseTypeDef,
+    CreateDatasetResponseTypeDef,
     CreateDocumentClassifierResponseTypeDef,
     CreateEndpointResponseTypeDef,
     CreateEntityRecognizerResponseTypeDef,
+    CreateFlywheelResponseTypeDef,
+    DataSecurityConfigTypeDef,
+    DatasetFilterTypeDef,
+    DatasetInputDataConfigTypeDef,
+    DescribeDatasetResponseTypeDef,
     DescribeDocumentClassificationJobResponseTypeDef,
     DescribeDocumentClassifierResponseTypeDef,
     DescribeDominantLanguageDetectionJobResponseTypeDef,
     DescribeEndpointResponseTypeDef,
     DescribeEntitiesDetectionJobResponseTypeDef,
     DescribeEntityRecognizerResponseTypeDef,
     DescribeEventsDetectionJobResponseTypeDef,
+    DescribeFlywheelIterationResponseTypeDef,
+    DescribeFlywheelResponseTypeDef,
     DescribeKeyPhrasesDetectionJobResponseTypeDef,
     DescribePiiEntitiesDetectionJobResponseTypeDef,
     DescribeResourcePolicyResponseTypeDef,
     DescribeSentimentDetectionJobResponseTypeDef,
     DescribeTargetedSentimentDetectionJobResponseTypeDef,
     DescribeTopicsDetectionJobResponseTypeDef,
     DetectDominantLanguageResponseTypeDef,
@@ -78,26 +88,31 @@
     DocumentReaderConfigTypeDef,
     DominantLanguageDetectionJobFilterTypeDef,
     EndpointFilterTypeDef,
     EntitiesDetectionJobFilterTypeDef,
     EntityRecognizerFilterTypeDef,
     EntityRecognizerInputDataConfigTypeDef,
     EventsDetectionJobFilterTypeDef,
+    FlywheelFilterTypeDef,
+    FlywheelIterationFilterTypeDef,
     ImportModelResponseTypeDef,
     InputDataConfigTypeDef,
     KeyPhrasesDetectionJobFilterTypeDef,
+    ListDatasetsResponseTypeDef,
     ListDocumentClassificationJobsResponseTypeDef,
     ListDocumentClassifiersResponseTypeDef,
     ListDocumentClassifierSummariesResponseTypeDef,
     ListDominantLanguageDetectionJobsResponseTypeDef,
     ListEndpointsResponseTypeDef,
     ListEntitiesDetectionJobsResponseTypeDef,
     ListEntityRecognizersResponseTypeDef,
     ListEntityRecognizerSummariesResponseTypeDef,
     ListEventsDetectionJobsResponseTypeDef,
+    ListFlywheelIterationHistoryResponseTypeDef,
+    ListFlywheelsResponseTypeDef,
     ListKeyPhrasesDetectionJobsResponseTypeDef,
     ListPiiEntitiesDetectionJobsResponseTypeDef,
     ListSentimentDetectionJobsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     ListTargetedSentimentDetectionJobsResponseTypeDef,
     ListTopicsDetectionJobsResponseTypeDef,
     OutputDataConfigTypeDef,
@@ -105,49 +120,51 @@
     PutResourcePolicyResponseTypeDef,
     RedactionConfigTypeDef,
     SentimentDetectionJobFilterTypeDef,
     StartDocumentClassificationJobResponseTypeDef,
     StartDominantLanguageDetectionJobResponseTypeDef,
     StartEntitiesDetectionJobResponseTypeDef,
     StartEventsDetectionJobResponseTypeDef,
+    StartFlywheelIterationResponseTypeDef,
     StartKeyPhrasesDetectionJobResponseTypeDef,
     StartPiiEntitiesDetectionJobResponseTypeDef,
     StartSentimentDetectionJobResponseTypeDef,
     StartTargetedSentimentDetectionJobResponseTypeDef,
     StartTopicsDetectionJobResponseTypeDef,
     StopDominantLanguageDetectionJobResponseTypeDef,
     StopEntitiesDetectionJobResponseTypeDef,
     StopEventsDetectionJobResponseTypeDef,
     StopKeyPhrasesDetectionJobResponseTypeDef,
     StopPiiEntitiesDetectionJobResponseTypeDef,
     StopSentimentDetectionJobResponseTypeDef,
     StopTargetedSentimentDetectionJobResponseTypeDef,
     TagTypeDef,
     TargetedSentimentDetectionJobFilterTypeDef,
+    TaskConfigTypeDef,
     TopicsDetectionJobFilterTypeDef,
+    UpdateDataSecurityConfigTypeDef,
+    UpdateEndpointResponseTypeDef,
+    UpdateFlywheelResponseTypeDef,
     VpcConfigTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = ("ComprehendClient",)
 
-
 class BotocoreClientError(BaseException):
     MSG_TEMPLATE: str
 
     def __init__(self, error_response: Mapping[str, Any], operation_name: str) -> None:
         self.response: Dict[str, Any]
         self.operation_name: str
 
-
 class Exceptions:
     BatchSizeLimitExceededException: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
     ConcurrentModificationException: Type[BotocoreClientError]
     InternalServerException: Type[BotocoreClientError]
     InvalidFilterException: Type[BotocoreClientError]
     InvalidRequestException: Type[BotocoreClientError]
@@ -159,15 +176,14 @@
     ResourceUnavailableException: Type[BotocoreClientError]
     TextSizeLimitExceededException: Type[BotocoreClientError]
     TooManyRequestsException: Type[BotocoreClientError]
     TooManyTagKeysException: Type[BotocoreClientError]
     TooManyTagsException: Type[BotocoreClientError]
     UnsupportedLanguageException: Type[BotocoreClientError]
 
-
 class ComprehendClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/)
     """
 
     meta: ClientMeta
@@ -176,87 +192,79 @@
     def exceptions(self) -> Exceptions:
         """
         ComprehendClient exceptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#exceptions)
         """
-
     async def batch_detect_dominant_language(
         self, *, TextList: Sequence[str]
     ) -> BatchDetectDominantLanguageResponseTypeDef:
         """
         Determines the dominant language of the input text for a batch of documents.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.batch_detect_dominant_language)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#batch_detect_dominant_language)
         """
-
     async def batch_detect_entities(
         self, *, TextList: Sequence[str], LanguageCode: LanguageCodeType
     ) -> BatchDetectEntitiesResponseTypeDef:
         """
         Inspects the text of a batch of documents for named entities and returns
         information about them.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.batch_detect_entities)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#batch_detect_entities)
         """
-
     async def batch_detect_key_phrases(
         self, *, TextList: Sequence[str], LanguageCode: LanguageCodeType
     ) -> BatchDetectKeyPhrasesResponseTypeDef:
         """
         Detects the key noun phrases found in a batch of documents.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.batch_detect_key_phrases)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#batch_detect_key_phrases)
         """
-
     async def batch_detect_sentiment(
         self, *, TextList: Sequence[str], LanguageCode: LanguageCodeType
     ) -> BatchDetectSentimentResponseTypeDef:
         """
         Inspects a batch of documents and returns an inference of the prevailing
-        sentiment, `POSITIVE` , `NEUTRAL` , `MIXED` , or `NEGATIVE` , in each one.
+        sentiment, `POSITIVE`, `NEUTRAL`, `MIXED`, or `NEGATIVE`, in each one.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.batch_detect_sentiment)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#batch_detect_sentiment)
         """
-
     async def batch_detect_syntax(
         self, *, TextList: Sequence[str], LanguageCode: SyntaxLanguageCodeType
     ) -> BatchDetectSyntaxResponseTypeDef:
         """
         Inspects the text of a batch of documents for the syntax and part of speech of
         the words in the document and returns information about them.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.batch_detect_syntax)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#batch_detect_syntax)
         """
-
     async def batch_detect_targeted_sentiment(
         self, *, TextList: Sequence[str], LanguageCode: LanguageCodeType
     ) -> BatchDetectTargetedSentimentResponseTypeDef:
         """
         Inspects a batch of documents and returns a sentiment analysis for each entity
         identified in the documents.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.batch_detect_targeted_sentiment)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#batch_detect_targeted_sentiment)
         """
-
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#can_paginate)
         """
-
     async def classify_document(
         self,
         *,
         EndpointArn: str,
         Text: str = ...,
         Bytes: Union[str, bytes, IO[Any], StreamingBody] = ...,
         DocumentReaderConfig: DocumentReaderConfigTypeDef = ...
@@ -264,35 +272,50 @@
         """
         Creates a new document classification request to analyze a single document in
         real-time, using a previously created and trained custom model and an endpoint.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.classify_document)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#classify_document)
         """
-
     async def close(self) -> None:
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#close)
         """
-
     async def contains_pii_entities(
         self, *, Text: str, LanguageCode: LanguageCodeType
     ) -> ContainsPiiEntitiesResponseTypeDef:
         """
         Analyzes input text for the presence of personally identifiable information
         (PII) and returns the labels of identified PII entity types such as name,
         address, bank account number, or phone number.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.contains_pii_entities)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#contains_pii_entities)
         """
+    async def create_dataset(
+        self,
+        *,
+        FlywheelArn: str,
+        DatasetName: str,
+        InputDataConfig: DatasetInputDataConfigTypeDef,
+        DatasetType: DatasetTypeType = ...,
+        Description: str = ...,
+        ClientRequestToken: str = ...,
+        Tags: Sequence[TagTypeDef] = ...
+    ) -> CreateDatasetResponseTypeDef:
+        """
+        Creates a dataset to upload training or test data for a model associated with a
+        flywheel.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.create_dataset)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#create_dataset)
+        """
     async def create_document_classifier(
         self,
         *,
         DocumentClassifierName: str,
         DataAccessRoleArn: str,
         InputDataConfig: DocumentClassifierInputDataConfigTypeDef,
         LanguageCode: LanguageCodeType,
@@ -308,35 +331,34 @@
     ) -> CreateDocumentClassifierResponseTypeDef:
         """
         Creates a new document classifier that you can use to categorize documents.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.create_document_classifier)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#create_document_classifier)
         """
-
     async def create_endpoint(
         self,
         *,
         EndpointName: str,
-        ModelArn: str,
         DesiredInferenceUnits: int,
+        ModelArn: str = ...,
         ClientRequestToken: str = ...,
         Tags: Sequence[TagTypeDef] = ...,
-        DataAccessRoleArn: str = ...
+        DataAccessRoleArn: str = ...,
+        FlywheelArn: str = ...
     ) -> CreateEndpointResponseTypeDef:
         """
         Creates a model-specific endpoint for synchronous inference for a previously
         trained custom model For information about endpoints, see [Managing
         endpoints](https://docs.aws.amazon.com/comprehend/latest/dg/manage-
         endpoints.html)_.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.create_endpoint)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#create_endpoint)
         """
-
     async def create_entity_recognizer(
         self,
         *,
         RecognizerName: str,
         DataAccessRoleArn: str,
         InputDataConfig: EntityRecognizerInputDataConfigTypeDef,
         LanguageCode: LanguageCodeType,
@@ -350,188 +372,219 @@
     ) -> CreateEntityRecognizerResponseTypeDef:
         """
         Creates an entity recognizer using submitted files.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.create_entity_recognizer)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#create_entity_recognizer)
         """
+    async def create_flywheel(
+        self,
+        *,
+        FlywheelName: str,
+        DataAccessRoleArn: str,
+        DataLakeS3Uri: str,
+        ActiveModelArn: str = ...,
+        TaskConfig: TaskConfigTypeDef = ...,
+        ModelType: ModelTypeType = ...,
+        DataSecurityConfig: DataSecurityConfigTypeDef = ...,
+        ClientRequestToken: str = ...,
+        Tags: Sequence[TagTypeDef] = ...
+    ) -> CreateFlywheelResponseTypeDef:
+        """
+        A flywheel is an Amazon Web Services resource that orchestrates the ongoing
+        training of a model for custom classification or custom entity recognition.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.create_flywheel)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#create_flywheel)
+        """
     async def delete_document_classifier(self, *, DocumentClassifierArn: str) -> Dict[str, Any]:
         """
         Deletes a previously created document classifier Only those classifiers that are
         in terminated states (IN_ERROR, TRAINED) will be deleted.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.delete_document_classifier)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#delete_document_classifier)
         """
-
     async def delete_endpoint(self, *, EndpointArn: str) -> Dict[str, Any]:
         """
         Deletes a model-specific endpoint for a previously-trained custom model.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.delete_endpoint)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#delete_endpoint)
         """
-
     async def delete_entity_recognizer(self, *, EntityRecognizerArn: str) -> Dict[str, Any]:
         """
         Deletes an entity recognizer.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.delete_entity_recognizer)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#delete_entity_recognizer)
         """
+    async def delete_flywheel(self, *, FlywheelArn: str) -> Dict[str, Any]:
+        """
+        Deletes a flywheel.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.delete_flywheel)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#delete_flywheel)
+        """
     async def delete_resource_policy(
         self, *, ResourceArn: str, PolicyRevisionId: str = ...
     ) -> Dict[str, Any]:
         """
         Deletes a resource-based policy that is attached to a custom model.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.delete_resource_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#delete_resource_policy)
         """
+    async def describe_dataset(self, *, DatasetArn: str) -> DescribeDatasetResponseTypeDef:
+        """
+        Returns information about the dataset that you specify.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.describe_dataset)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#describe_dataset)
+        """
     async def describe_document_classification_job(
         self, *, JobId: str
     ) -> DescribeDocumentClassificationJobResponseTypeDef:
         """
         Gets the properties associated with a document classification job.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.describe_document_classification_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#describe_document_classification_job)
         """
-
     async def describe_document_classifier(
         self, *, DocumentClassifierArn: str
     ) -> DescribeDocumentClassifierResponseTypeDef:
         """
         Gets the properties associated with a document classifier.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.describe_document_classifier)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#describe_document_classifier)
         """
-
     async def describe_dominant_language_detection_job(
         self, *, JobId: str
     ) -> DescribeDominantLanguageDetectionJobResponseTypeDef:
         """
         Gets the properties associated with a dominant language detection job.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.describe_dominant_language_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#describe_dominant_language_detection_job)
         """
-
     async def describe_endpoint(self, *, EndpointArn: str) -> DescribeEndpointResponseTypeDef:
         """
         Gets the properties associated with a specific endpoint.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.describe_endpoint)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#describe_endpoint)
         """
-
     async def describe_entities_detection_job(
         self, *, JobId: str
     ) -> DescribeEntitiesDetectionJobResponseTypeDef:
         """
         Gets the properties associated with an entities detection job.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.describe_entities_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#describe_entities_detection_job)
         """
-
     async def describe_entity_recognizer(
         self, *, EntityRecognizerArn: str
     ) -> DescribeEntityRecognizerResponseTypeDef:
         """
         Provides details about an entity recognizer including status, S3 buckets
         containing training data, recognizer metadata, metrics, and so on.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.describe_entity_recognizer)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#describe_entity_recognizer)
         """
-
     async def describe_events_detection_job(
         self, *, JobId: str
     ) -> DescribeEventsDetectionJobResponseTypeDef:
         """
         Gets the status and details of an events detection job.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.describe_events_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#describe_events_detection_job)
         """
+    async def describe_flywheel(self, *, FlywheelArn: str) -> DescribeFlywheelResponseTypeDef:
+        """
+        Provides configuration information about the flywheel.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.describe_flywheel)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#describe_flywheel)
+        """
+    async def describe_flywheel_iteration(
+        self, *, FlywheelArn: str, FlywheelIterationId: str
+    ) -> DescribeFlywheelIterationResponseTypeDef:
+        """
+        Retrieve the configuration properties of a flywheel iteration.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.describe_flywheel_iteration)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#describe_flywheel_iteration)
+        """
     async def describe_key_phrases_detection_job(
         self, *, JobId: str
     ) -> DescribeKeyPhrasesDetectionJobResponseTypeDef:
         """
         Gets the properties associated with a key phrases detection job.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.describe_key_phrases_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#describe_key_phrases_detection_job)
         """
-
     async def describe_pii_entities_detection_job(
         self, *, JobId: str
     ) -> DescribePiiEntitiesDetectionJobResponseTypeDef:
         """
         Gets the properties associated with a PII entities detection job.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.describe_pii_entities_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#describe_pii_entities_detection_job)
         """
-
     async def describe_resource_policy(
         self, *, ResourceArn: str
     ) -> DescribeResourcePolicyResponseTypeDef:
         """
         Gets the details of a resource-based policy that is attached to a custom model,
         including the JSON body of the policy.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.describe_resource_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#describe_resource_policy)
         """
-
     async def describe_sentiment_detection_job(
         self, *, JobId: str
     ) -> DescribeSentimentDetectionJobResponseTypeDef:
         """
         Gets the properties associated with a sentiment detection job.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.describe_sentiment_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#describe_sentiment_detection_job)
         """
-
     async def describe_targeted_sentiment_detection_job(
         self, *, JobId: str
     ) -> DescribeTargetedSentimentDetectionJobResponseTypeDef:
         """
         Gets the properties associated with a targeted sentiment detection job.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.describe_targeted_sentiment_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#describe_targeted_sentiment_detection_job)
         """
-
     async def describe_topics_detection_job(
         self, *, JobId: str
     ) -> DescribeTopicsDetectionJobResponseTypeDef:
         """
         Gets the properties associated with a topic detection job.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.describe_topics_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#describe_topics_detection_job)
         """
-
     async def detect_dominant_language(self, *, Text: str) -> DetectDominantLanguageResponseTypeDef:
         """
         Determines the dominant language of the input text.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.detect_dominant_language)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#detect_dominant_language)
         """
-
     async def detect_entities(
         self,
         *,
         Text: str = ...,
         LanguageCode: LanguageCodeType = ...,
         EndpointArn: str = ...,
         Bytes: Union[str, bytes, IO[Any], StreamingBody] = ...,
@@ -539,82 +592,75 @@
     ) -> DetectEntitiesResponseTypeDef:
         """
         Detects named entities in input text when you use the pre-trained model.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.detect_entities)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#detect_entities)
         """
-
     async def detect_key_phrases(
         self, *, Text: str, LanguageCode: LanguageCodeType
     ) -> DetectKeyPhrasesResponseTypeDef:
         """
         Detects the key noun phrases found in the text.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.detect_key_phrases)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#detect_key_phrases)
         """
-
     async def detect_pii_entities(
         self, *, Text: str, LanguageCode: LanguageCodeType
     ) -> DetectPiiEntitiesResponseTypeDef:
         """
         Inspects the input text for entities that contain personally identifiable
         information (PII) and returns information about them.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.detect_pii_entities)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#detect_pii_entities)
         """
-
     async def detect_sentiment(
         self, *, Text: str, LanguageCode: LanguageCodeType
     ) -> DetectSentimentResponseTypeDef:
         """
-        Inspects text and returns an inference of the prevailing sentiment ( `POSITIVE`
-        , `NEUTRAL` , `MIXED` , or `NEGATIVE` ).
+        Inspects text and returns an inference of the prevailing sentiment ( `POSITIVE`,
+        `NEUTRAL`, `MIXED`, or `NEGATIVE`).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.detect_sentiment)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#detect_sentiment)
         """
-
     async def detect_syntax(
         self, *, Text: str, LanguageCode: SyntaxLanguageCodeType
     ) -> DetectSyntaxResponseTypeDef:
         """
         Inspects text for syntax and the part of speech of words in the document.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.detect_syntax)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#detect_syntax)
         """
-
     async def detect_targeted_sentiment(
         self, *, Text: str, LanguageCode: LanguageCodeType
     ) -> DetectTargetedSentimentResponseTypeDef:
         """
         Inspects the input text and returns a sentiment analysis for each entity
         identified in the text.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.detect_targeted_sentiment)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#detect_targeted_sentiment)
         """
-
     async def generate_presigned_url(
         self,
         ClientMethod: str,
         Params: Mapping[str, Any] = ...,
         ExpiresIn: int = 3600,
         HttpMethod: str = ...,
     ) -> str:
         """
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#generate_presigned_url)
         """
-
     async def import_model(
         self,
         *,
         SourceModelArn: str,
         ModelName: str = ...,
         VersionName: str = ...,
         ModelKmsKeyId: str = ...,
@@ -624,242 +670,262 @@
         """
         Creates a new custom model that replicates a source custom model that you
         import.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.import_model)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#import_model)
         """
+    async def list_datasets(
+        self,
+        *,
+        FlywheelArn: str = ...,
+        Filter: DatasetFilterTypeDef = ...,
+        NextToken: str = ...,
+        MaxResults: int = ...
+    ) -> ListDatasetsResponseTypeDef:
+        """
+        List the datasets that you have configured in this Region.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.list_datasets)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#list_datasets)
+        """
     async def list_document_classification_jobs(
         self,
         *,
         Filter: DocumentClassificationJobFilterTypeDef = ...,
         NextToken: str = ...,
         MaxResults: int = ...
     ) -> ListDocumentClassificationJobsResponseTypeDef:
         """
         Gets a list of the documentation classification jobs that you have submitted.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.list_document_classification_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#list_document_classification_jobs)
         """
-
     async def list_document_classifier_summaries(
         self, *, NextToken: str = ..., MaxResults: int = ...
     ) -> ListDocumentClassifierSummariesResponseTypeDef:
         """
         Gets a list of summaries of the document classifiers that you have created See
         also: [AWS API
         Documentation](https://docs.aws.amazon.com/goto/WebAPI/comprehend-2017-11-27/ListDocumentClassifierSummaries).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.list_document_classifier_summaries)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#list_document_classifier_summaries)
         """
-
     async def list_document_classifiers(
         self,
         *,
         Filter: DocumentClassifierFilterTypeDef = ...,
         NextToken: str = ...,
         MaxResults: int = ...
     ) -> ListDocumentClassifiersResponseTypeDef:
         """
         Gets a list of the document classifiers that you have created.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.list_document_classifiers)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#list_document_classifiers)
         """
-
     async def list_dominant_language_detection_jobs(
         self,
         *,
         Filter: DominantLanguageDetectionJobFilterTypeDef = ...,
         NextToken: str = ...,
         MaxResults: int = ...
     ) -> ListDominantLanguageDetectionJobsResponseTypeDef:
         """
         Gets a list of the dominant language detection jobs that you have submitted.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.list_dominant_language_detection_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#list_dominant_language_detection_jobs)
         """
-
     async def list_endpoints(
         self, *, Filter: EndpointFilterTypeDef = ..., NextToken: str = ..., MaxResults: int = ...
     ) -> ListEndpointsResponseTypeDef:
         """
         Gets a list of all existing endpoints that you've created.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.list_endpoints)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#list_endpoints)
         """
-
     async def list_entities_detection_jobs(
         self,
         *,
         Filter: EntitiesDetectionJobFilterTypeDef = ...,
         NextToken: str = ...,
         MaxResults: int = ...
     ) -> ListEntitiesDetectionJobsResponseTypeDef:
         """
         Gets a list of the entity detection jobs that you have submitted.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.list_entities_detection_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#list_entities_detection_jobs)
         """
-
     async def list_entity_recognizer_summaries(
         self, *, NextToken: str = ..., MaxResults: int = ...
     ) -> ListEntityRecognizerSummariesResponseTypeDef:
         """
         Gets a list of summaries for the entity recognizers that you have created.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.list_entity_recognizer_summaries)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#list_entity_recognizer_summaries)
         """
-
     async def list_entity_recognizers(
         self,
         *,
         Filter: EntityRecognizerFilterTypeDef = ...,
         NextToken: str = ...,
         MaxResults: int = ...
     ) -> ListEntityRecognizersResponseTypeDef:
         """
         Gets a list of the properties of all entity recognizers that you created,
         including recognizers currently in training.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.list_entity_recognizers)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#list_entity_recognizers)
         """
-
     async def list_events_detection_jobs(
         self,
         *,
         Filter: EventsDetectionJobFilterTypeDef = ...,
         NextToken: str = ...,
         MaxResults: int = ...
     ) -> ListEventsDetectionJobsResponseTypeDef:
         """
         Gets a list of the events detection jobs that you have submitted.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.list_events_detection_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#list_events_detection_jobs)
         """
+    async def list_flywheel_iteration_history(
+        self,
+        *,
+        FlywheelArn: str,
+        Filter: FlywheelIterationFilterTypeDef = ...,
+        NextToken: str = ...,
+        MaxResults: int = ...
+    ) -> ListFlywheelIterationHistoryResponseTypeDef:
+        """
+        Information about the history of a flywheel iteration.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.list_flywheel_iteration_history)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#list_flywheel_iteration_history)
+        """
+    async def list_flywheels(
+        self, *, Filter: FlywheelFilterTypeDef = ..., NextToken: str = ..., MaxResults: int = ...
+    ) -> ListFlywheelsResponseTypeDef:
+        """
+        Gets a list of the flywheels that you have created.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.list_flywheels)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#list_flywheels)
+        """
     async def list_key_phrases_detection_jobs(
         self,
         *,
         Filter: KeyPhrasesDetectionJobFilterTypeDef = ...,
         NextToken: str = ...,
         MaxResults: int = ...
     ) -> ListKeyPhrasesDetectionJobsResponseTypeDef:
         """
         Get a list of key phrase detection jobs that you have submitted.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.list_key_phrases_detection_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#list_key_phrases_detection_jobs)
         """
-
     async def list_pii_entities_detection_jobs(
         self,
         *,
         Filter: PiiEntitiesDetectionJobFilterTypeDef = ...,
         NextToken: str = ...,
         MaxResults: int = ...
     ) -> ListPiiEntitiesDetectionJobsResponseTypeDef:
         """
         Gets a list of the PII entity detection jobs that you have submitted.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.list_pii_entities_detection_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#list_pii_entities_detection_jobs)
         """
-
     async def list_sentiment_detection_jobs(
         self,
         *,
         Filter: SentimentDetectionJobFilterTypeDef = ...,
         NextToken: str = ...,
         MaxResults: int = ...
     ) -> ListSentimentDetectionJobsResponseTypeDef:
         """
         Gets a list of sentiment detection jobs that you have submitted.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.list_sentiment_detection_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#list_sentiment_detection_jobs)
         """
-
     async def list_tags_for_resource(
         self, *, ResourceArn: str
     ) -> ListTagsForResourceResponseTypeDef:
         """
         Lists all tags associated with a given Amazon Comprehend resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#list_tags_for_resource)
         """
-
     async def list_targeted_sentiment_detection_jobs(
         self,
         *,
         Filter: TargetedSentimentDetectionJobFilterTypeDef = ...,
         NextToken: str = ...,
         MaxResults: int = ...
     ) -> ListTargetedSentimentDetectionJobsResponseTypeDef:
         """
         Gets a list of targeted sentiment detection jobs that you have submitted.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.list_targeted_sentiment_detection_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#list_targeted_sentiment_detection_jobs)
         """
-
     async def list_topics_detection_jobs(
         self,
         *,
         Filter: TopicsDetectionJobFilterTypeDef = ...,
         NextToken: str = ...,
         MaxResults: int = ...
     ) -> ListTopicsDetectionJobsResponseTypeDef:
         """
         Gets a list of the topic detection jobs that you have submitted.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.list_topics_detection_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#list_topics_detection_jobs)
         """
-
     async def put_resource_policy(
         self, *, ResourceArn: str, ResourcePolicy: str, PolicyRevisionId: str = ...
     ) -> PutResourcePolicyResponseTypeDef:
         """
         Attaches a resource-based policy to a custom model.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.put_resource_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#put_resource_policy)
         """
-
     async def start_document_classification_job(
         self,
         *,
-        DocumentClassifierArn: str,
         InputDataConfig: InputDataConfigTypeDef,
         OutputDataConfig: OutputDataConfigTypeDef,
         DataAccessRoleArn: str,
         JobName: str = ...,
+        DocumentClassifierArn: str = ...,
         ClientRequestToken: str = ...,
         VolumeKmsKeyId: str = ...,
         VpcConfig: VpcConfigTypeDef = ...,
-        Tags: Sequence[TagTypeDef] = ...
+        Tags: Sequence[TagTypeDef] = ...,
+        FlywheelArn: str = ...
     ) -> StartDocumentClassificationJobResponseTypeDef:
         """
         Starts an asynchronous document classification job.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.start_document_classification_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#start_document_classification_job)
         """
-
     async def start_dominant_language_detection_job(
         self,
         *,
         InputDataConfig: InputDataConfigTypeDef,
         OutputDataConfig: OutputDataConfigTypeDef,
         DataAccessRoleArn: str,
         JobName: str = ...,
@@ -871,36 +937,35 @@
         """
         Starts an asynchronous dominant language detection job for a collection of
         documents.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.start_dominant_language_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#start_dominant_language_detection_job)
         """
-
     async def start_entities_detection_job(
         self,
         *,
         InputDataConfig: InputDataConfigTypeDef,
         OutputDataConfig: OutputDataConfigTypeDef,
         DataAccessRoleArn: str,
         LanguageCode: LanguageCodeType,
         JobName: str = ...,
         EntityRecognizerArn: str = ...,
         ClientRequestToken: str = ...,
         VolumeKmsKeyId: str = ...,
         VpcConfig: VpcConfigTypeDef = ...,
-        Tags: Sequence[TagTypeDef] = ...
+        Tags: Sequence[TagTypeDef] = ...,
+        FlywheelArn: str = ...
     ) -> StartEntitiesDetectionJobResponseTypeDef:
         """
         Starts an asynchronous entity detection job for a collection of documents.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.start_entities_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#start_entities_detection_job)
         """
-
     async def start_events_detection_job(
         self,
         *,
         InputDataConfig: InputDataConfigTypeDef,
         OutputDataConfig: OutputDataConfigTypeDef,
         DataAccessRoleArn: str,
         LanguageCode: LanguageCodeType,
@@ -911,15 +976,24 @@
     ) -> StartEventsDetectionJobResponseTypeDef:
         """
         Starts an asynchronous event detection job for a collection of documents.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.start_events_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#start_events_detection_job)
         """
+    async def start_flywheel_iteration(
+        self, *, FlywheelArn: str, ClientRequestToken: str = ...
+    ) -> StartFlywheelIterationResponseTypeDef:
+        """
+        Start the flywheel iteration.This operation uses any new datasets to train a new
+        model version.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.start_flywheel_iteration)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#start_flywheel_iteration)
+        """
     async def start_key_phrases_detection_job(
         self,
         *,
         InputDataConfig: InputDataConfigTypeDef,
         OutputDataConfig: OutputDataConfigTypeDef,
         DataAccessRoleArn: str,
         LanguageCode: LanguageCodeType,
@@ -931,15 +1005,14 @@
     ) -> StartKeyPhrasesDetectionJobResponseTypeDef:
         """
         Starts an asynchronous key phrase detection job for a collection of documents.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.start_key_phrases_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#start_key_phrases_detection_job)
         """
-
     async def start_pii_entities_detection_job(
         self,
         *,
         InputDataConfig: InputDataConfigTypeDef,
         OutputDataConfig: OutputDataConfigTypeDef,
         Mode: PiiEntitiesDetectionModeType,
         DataAccessRoleArn: str,
@@ -951,15 +1024,14 @@
     ) -> StartPiiEntitiesDetectionJobResponseTypeDef:
         """
         Starts an asynchronous PII entity detection job for a collection of documents.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.start_pii_entities_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#start_pii_entities_detection_job)
         """
-
     async def start_sentiment_detection_job(
         self,
         *,
         InputDataConfig: InputDataConfigTypeDef,
         OutputDataConfig: OutputDataConfigTypeDef,
         DataAccessRoleArn: str,
         LanguageCode: LanguageCodeType,
@@ -971,15 +1043,14 @@
     ) -> StartSentimentDetectionJobResponseTypeDef:
         """
         Starts an asynchronous sentiment detection job for a collection of documents.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.start_sentiment_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#start_sentiment_detection_job)
         """
-
     async def start_targeted_sentiment_detection_job(
         self,
         *,
         InputDataConfig: InputDataConfigTypeDef,
         OutputDataConfig: OutputDataConfigTypeDef,
         DataAccessRoleArn: str,
         LanguageCode: LanguageCodeType,
@@ -992,15 +1063,14 @@
         """
         Starts an asynchronous targeted sentiment detection job for a collection of
         documents.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.start_targeted_sentiment_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#start_targeted_sentiment_detection_job)
         """
-
     async def start_topics_detection_job(
         self,
         *,
         InputDataConfig: InputDataConfigTypeDef,
         OutputDataConfig: OutputDataConfigTypeDef,
         DataAccessRoleArn: str,
         JobName: str = ...,
@@ -1012,226 +1082,217 @@
     ) -> StartTopicsDetectionJobResponseTypeDef:
         """
         Starts an asynchronous topic detection job.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.start_topics_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#start_topics_detection_job)
         """
-
     async def stop_dominant_language_detection_job(
         self, *, JobId: str
     ) -> StopDominantLanguageDetectionJobResponseTypeDef:
         """
         Stops a dominant language detection job in progress.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.stop_dominant_language_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#stop_dominant_language_detection_job)
         """
-
     async def stop_entities_detection_job(
         self, *, JobId: str
     ) -> StopEntitiesDetectionJobResponseTypeDef:
         """
         Stops an entities detection job in progress.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.stop_entities_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#stop_entities_detection_job)
         """
-
     async def stop_events_detection_job(
         self, *, JobId: str
     ) -> StopEventsDetectionJobResponseTypeDef:
         """
         Stops an events detection job in progress.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.stop_events_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#stop_events_detection_job)
         """
-
     async def stop_key_phrases_detection_job(
         self, *, JobId: str
     ) -> StopKeyPhrasesDetectionJobResponseTypeDef:
         """
         Stops a key phrases detection job in progress.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.stop_key_phrases_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#stop_key_phrases_detection_job)
         """
-
     async def stop_pii_entities_detection_job(
         self, *, JobId: str
     ) -> StopPiiEntitiesDetectionJobResponseTypeDef:
         """
         Stops a PII entities detection job in progress.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.stop_pii_entities_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#stop_pii_entities_detection_job)
         """
-
     async def stop_sentiment_detection_job(
         self, *, JobId: str
     ) -> StopSentimentDetectionJobResponseTypeDef:
         """
         Stops a sentiment detection job in progress.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.stop_sentiment_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#stop_sentiment_detection_job)
         """
-
     async def stop_targeted_sentiment_detection_job(
         self, *, JobId: str
     ) -> StopTargetedSentimentDetectionJobResponseTypeDef:
         """
         Stops a targeted sentiment detection job in progress.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.stop_targeted_sentiment_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#stop_targeted_sentiment_detection_job)
         """
-
     async def stop_training_document_classifier(
         self, *, DocumentClassifierArn: str
     ) -> Dict[str, Any]:
         """
         Stops a document classifier training job while in progress.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.stop_training_document_classifier)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#stop_training_document_classifier)
         """
-
     async def stop_training_entity_recognizer(self, *, EntityRecognizerArn: str) -> Dict[str, Any]:
         """
         Stops an entity recognizer training job while in progress.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.stop_training_entity_recognizer)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#stop_training_entity_recognizer)
         """
-
     async def tag_resource(self, *, ResourceArn: str, Tags: Sequence[TagTypeDef]) -> Dict[str, Any]:
         """
         Associates a specific tag with an Amazon Comprehend resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#tag_resource)
         """
-
     async def untag_resource(self, *, ResourceArn: str, TagKeys: Sequence[str]) -> Dict[str, Any]:
         """
         Removes a specific tag associated with an Amazon Comprehend resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#untag_resource)
         """
-
     async def update_endpoint(
         self,
         *,
         EndpointArn: str,
         DesiredModelArn: str = ...,
         DesiredInferenceUnits: int = ...,
-        DesiredDataAccessRoleArn: str = ...
-    ) -> Dict[str, Any]:
+        DesiredDataAccessRoleArn: str = ...,
+        FlywheelArn: str = ...
+    ) -> UpdateEndpointResponseTypeDef:
         """
         Updates information about the specified endpoint.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.update_endpoint)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#update_endpoint)
         """
+    async def update_flywheel(
+        self,
+        *,
+        FlywheelArn: str,
+        ActiveModelArn: str = ...,
+        DataAccessRoleArn: str = ...,
+        DataSecurityConfig: UpdateDataSecurityConfigTypeDef = ...
+    ) -> UpdateFlywheelResponseTypeDef:
+        """
+        Update the configuration information for an existing flywheel.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.update_flywheel)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#update_flywheel)
+        """
     @overload
     def get_paginator(
         self, operation_name: Literal["list_document_classification_jobs"]
     ) -> ListDocumentClassificationJobsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#get_paginator)
         """
-
     @overload
     def get_paginator(
         self, operation_name: Literal["list_document_classifiers"]
     ) -> ListDocumentClassifiersPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#get_paginator)
         """
-
     @overload
     def get_paginator(
         self, operation_name: Literal["list_dominant_language_detection_jobs"]
     ) -> ListDominantLanguageDetectionJobsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#get_paginator)
         """
-
     @overload
     def get_paginator(self, operation_name: Literal["list_endpoints"]) -> ListEndpointsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#get_paginator)
         """
-
     @overload
     def get_paginator(
         self, operation_name: Literal["list_entities_detection_jobs"]
     ) -> ListEntitiesDetectionJobsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#get_paginator)
         """
-
     @overload
     def get_paginator(
         self, operation_name: Literal["list_entity_recognizers"]
     ) -> ListEntityRecognizersPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#get_paginator)
         """
-
     @overload
     def get_paginator(
         self, operation_name: Literal["list_key_phrases_detection_jobs"]
     ) -> ListKeyPhrasesDetectionJobsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#get_paginator)
         """
-
     @overload
     def get_paginator(
         self, operation_name: Literal["list_pii_entities_detection_jobs"]
     ) -> ListPiiEntitiesDetectionJobsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#get_paginator)
         """
-
     @overload
     def get_paginator(
         self, operation_name: Literal["list_sentiment_detection_jobs"]
     ) -> ListSentimentDetectionJobsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#get_paginator)
         """
-
     @overload
     def get_paginator(
         self, operation_name: Literal["list_topics_detection_jobs"]
     ) -> ListTopicsDetectionJobsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#get_paginator)
         """
-
     async def __aenter__(self) -> "ComprehendClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/)
         """
-
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/)
         """
```

### Comparing `types-aiobotocore-comprehend-2.5.0.post1/types_aiobotocore_comprehend/client.pyi` & `types-aiobotocore-comprehend-2.5.1/types_aiobotocore_comprehend/client.py`

 * *Files 2% similar despite different names*

```diff
@@ -18,16 +18,18 @@
 from typing import IO, Any, Dict, Mapping, Sequence, Type, Union, overload
 
 from aiobotocore.client import AioBaseClient
 from aiobotocore.response import StreamingBody
 from botocore.client import ClientMeta
 
 from .literals import (
+    DatasetTypeType,
     DocumentClassifierModeType,
     LanguageCodeType,
+    ModelTypeType,
     PiiEntitiesDetectionModeType,
     SyntaxLanguageCodeType,
 )
 from .paginator import (
     ListDocumentClassificationJobsPaginator,
     ListDocumentClassifiersPaginator,
     ListDominantLanguageDetectionJobsPaginator,
@@ -44,24 +46,32 @@
     BatchDetectEntitiesResponseTypeDef,
     BatchDetectKeyPhrasesResponseTypeDef,
     BatchDetectSentimentResponseTypeDef,
     BatchDetectSyntaxResponseTypeDef,
     BatchDetectTargetedSentimentResponseTypeDef,
     ClassifyDocumentResponseTypeDef,
     ContainsPiiEntitiesResponseTypeDef,
+    CreateDatasetResponseTypeDef,
     CreateDocumentClassifierResponseTypeDef,
     CreateEndpointResponseTypeDef,
     CreateEntityRecognizerResponseTypeDef,
+    CreateFlywheelResponseTypeDef,
+    DataSecurityConfigTypeDef,
+    DatasetFilterTypeDef,
+    DatasetInputDataConfigTypeDef,
+    DescribeDatasetResponseTypeDef,
     DescribeDocumentClassificationJobResponseTypeDef,
     DescribeDocumentClassifierResponseTypeDef,
     DescribeDominantLanguageDetectionJobResponseTypeDef,
     DescribeEndpointResponseTypeDef,
     DescribeEntitiesDetectionJobResponseTypeDef,
     DescribeEntityRecognizerResponseTypeDef,
     DescribeEventsDetectionJobResponseTypeDef,
+    DescribeFlywheelIterationResponseTypeDef,
+    DescribeFlywheelResponseTypeDef,
     DescribeKeyPhrasesDetectionJobResponseTypeDef,
     DescribePiiEntitiesDetectionJobResponseTypeDef,
     DescribeResourcePolicyResponseTypeDef,
     DescribeSentimentDetectionJobResponseTypeDef,
     DescribeTargetedSentimentDetectionJobResponseTypeDef,
     DescribeTopicsDetectionJobResponseTypeDef,
     DetectDominantLanguageResponseTypeDef,
@@ -78,26 +88,31 @@
     DocumentReaderConfigTypeDef,
     DominantLanguageDetectionJobFilterTypeDef,
     EndpointFilterTypeDef,
     EntitiesDetectionJobFilterTypeDef,
     EntityRecognizerFilterTypeDef,
     EntityRecognizerInputDataConfigTypeDef,
     EventsDetectionJobFilterTypeDef,
+    FlywheelFilterTypeDef,
+    FlywheelIterationFilterTypeDef,
     ImportModelResponseTypeDef,
     InputDataConfigTypeDef,
     KeyPhrasesDetectionJobFilterTypeDef,
+    ListDatasetsResponseTypeDef,
     ListDocumentClassificationJobsResponseTypeDef,
     ListDocumentClassifiersResponseTypeDef,
     ListDocumentClassifierSummariesResponseTypeDef,
     ListDominantLanguageDetectionJobsResponseTypeDef,
     ListEndpointsResponseTypeDef,
     ListEntitiesDetectionJobsResponseTypeDef,
     ListEntityRecognizersResponseTypeDef,
     ListEntityRecognizerSummariesResponseTypeDef,
     ListEventsDetectionJobsResponseTypeDef,
+    ListFlywheelIterationHistoryResponseTypeDef,
+    ListFlywheelsResponseTypeDef,
     ListKeyPhrasesDetectionJobsResponseTypeDef,
     ListPiiEntitiesDetectionJobsResponseTypeDef,
     ListSentimentDetectionJobsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     ListTargetedSentimentDetectionJobsResponseTypeDef,
     ListTopicsDetectionJobsResponseTypeDef,
     OutputDataConfigTypeDef,
@@ -105,46 +120,54 @@
     PutResourcePolicyResponseTypeDef,
     RedactionConfigTypeDef,
     SentimentDetectionJobFilterTypeDef,
     StartDocumentClassificationJobResponseTypeDef,
     StartDominantLanguageDetectionJobResponseTypeDef,
     StartEntitiesDetectionJobResponseTypeDef,
     StartEventsDetectionJobResponseTypeDef,
+    StartFlywheelIterationResponseTypeDef,
     StartKeyPhrasesDetectionJobResponseTypeDef,
     StartPiiEntitiesDetectionJobResponseTypeDef,
     StartSentimentDetectionJobResponseTypeDef,
     StartTargetedSentimentDetectionJobResponseTypeDef,
     StartTopicsDetectionJobResponseTypeDef,
     StopDominantLanguageDetectionJobResponseTypeDef,
     StopEntitiesDetectionJobResponseTypeDef,
     StopEventsDetectionJobResponseTypeDef,
     StopKeyPhrasesDetectionJobResponseTypeDef,
     StopPiiEntitiesDetectionJobResponseTypeDef,
     StopSentimentDetectionJobResponseTypeDef,
     StopTargetedSentimentDetectionJobResponseTypeDef,
     TagTypeDef,
     TargetedSentimentDetectionJobFilterTypeDef,
+    TaskConfigTypeDef,
     TopicsDetectionJobFilterTypeDef,
+    UpdateDataSecurityConfigTypeDef,
+    UpdateEndpointResponseTypeDef,
+    UpdateFlywheelResponseTypeDef,
     VpcConfigTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = ("ComprehendClient",)
 
+
 class BotocoreClientError(BaseException):
     MSG_TEMPLATE: str
 
     def __init__(self, error_response: Mapping[str, Any], operation_name: str) -> None:
         self.response: Dict[str, Any]
         self.operation_name: str
 
+
 class Exceptions:
     BatchSizeLimitExceededException: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
     ConcurrentModificationException: Type[BotocoreClientError]
     InternalServerException: Type[BotocoreClientError]
     InvalidFilterException: Type[BotocoreClientError]
     InvalidRequestException: Type[BotocoreClientError]
@@ -156,14 +179,15 @@
     ResourceUnavailableException: Type[BotocoreClientError]
     TextSizeLimitExceededException: Type[BotocoreClientError]
     TooManyRequestsException: Type[BotocoreClientError]
     TooManyTagKeysException: Type[BotocoreClientError]
     TooManyTagsException: Type[BotocoreClientError]
     UnsupportedLanguageException: Type[BotocoreClientError]
 
+
 class ComprehendClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/)
     """
 
     meta: ClientMeta
@@ -172,79 +196,87 @@
     def exceptions(self) -> Exceptions:
         """
         ComprehendClient exceptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#exceptions)
         """
+
     async def batch_detect_dominant_language(
         self, *, TextList: Sequence[str]
     ) -> BatchDetectDominantLanguageResponseTypeDef:
         """
         Determines the dominant language of the input text for a batch of documents.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.batch_detect_dominant_language)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#batch_detect_dominant_language)
         """
+
     async def batch_detect_entities(
         self, *, TextList: Sequence[str], LanguageCode: LanguageCodeType
     ) -> BatchDetectEntitiesResponseTypeDef:
         """
         Inspects the text of a batch of documents for named entities and returns
         information about them.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.batch_detect_entities)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#batch_detect_entities)
         """
+
     async def batch_detect_key_phrases(
         self, *, TextList: Sequence[str], LanguageCode: LanguageCodeType
     ) -> BatchDetectKeyPhrasesResponseTypeDef:
         """
         Detects the key noun phrases found in a batch of documents.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.batch_detect_key_phrases)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#batch_detect_key_phrases)
         """
+
     async def batch_detect_sentiment(
         self, *, TextList: Sequence[str], LanguageCode: LanguageCodeType
     ) -> BatchDetectSentimentResponseTypeDef:
         """
         Inspects a batch of documents and returns an inference of the prevailing
-        sentiment, `POSITIVE` , `NEUTRAL` , `MIXED` , or `NEGATIVE` , in each one.
+        sentiment, `POSITIVE`, `NEUTRAL`, `MIXED`, or `NEGATIVE`, in each one.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.batch_detect_sentiment)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#batch_detect_sentiment)
         """
+
     async def batch_detect_syntax(
         self, *, TextList: Sequence[str], LanguageCode: SyntaxLanguageCodeType
     ) -> BatchDetectSyntaxResponseTypeDef:
         """
         Inspects the text of a batch of documents for the syntax and part of speech of
         the words in the document and returns information about them.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.batch_detect_syntax)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#batch_detect_syntax)
         """
+
     async def batch_detect_targeted_sentiment(
         self, *, TextList: Sequence[str], LanguageCode: LanguageCodeType
     ) -> BatchDetectTargetedSentimentResponseTypeDef:
         """
         Inspects a batch of documents and returns a sentiment analysis for each entity
         identified in the documents.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.batch_detect_targeted_sentiment)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#batch_detect_targeted_sentiment)
         """
+
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#can_paginate)
         """
+
     async def classify_document(
         self,
         *,
         EndpointArn: str,
         Text: str = ...,
         Bytes: Union[str, bytes, IO[Any], StreamingBody] = ...,
         DocumentReaderConfig: DocumentReaderConfigTypeDef = ...
@@ -252,32 +284,54 @@
         """
         Creates a new document classification request to analyze a single document in
         real-time, using a previously created and trained custom model and an endpoint.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.classify_document)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#classify_document)
         """
+
     async def close(self) -> None:
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#close)
         """
+
     async def contains_pii_entities(
         self, *, Text: str, LanguageCode: LanguageCodeType
     ) -> ContainsPiiEntitiesResponseTypeDef:
         """
         Analyzes input text for the presence of personally identifiable information
         (PII) and returns the labels of identified PII entity types such as name,
         address, bank account number, or phone number.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.contains_pii_entities)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#contains_pii_entities)
         """
+
+    async def create_dataset(
+        self,
+        *,
+        FlywheelArn: str,
+        DatasetName: str,
+        InputDataConfig: DatasetInputDataConfigTypeDef,
+        DatasetType: DatasetTypeType = ...,
+        Description: str = ...,
+        ClientRequestToken: str = ...,
+        Tags: Sequence[TagTypeDef] = ...
+    ) -> CreateDatasetResponseTypeDef:
+        """
+        Creates a dataset to upload training or test data for a model associated with a
+        flywheel.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.create_dataset)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#create_dataset)
+        """
+
     async def create_document_classifier(
         self,
         *,
         DocumentClassifierName: str,
         DataAccessRoleArn: str,
         InputDataConfig: DocumentClassifierInputDataConfigTypeDef,
         LanguageCode: LanguageCodeType,
@@ -293,33 +347,36 @@
     ) -> CreateDocumentClassifierResponseTypeDef:
         """
         Creates a new document classifier that you can use to categorize documents.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.create_document_classifier)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#create_document_classifier)
         """
+
     async def create_endpoint(
         self,
         *,
         EndpointName: str,
-        ModelArn: str,
         DesiredInferenceUnits: int,
+        ModelArn: str = ...,
         ClientRequestToken: str = ...,
         Tags: Sequence[TagTypeDef] = ...,
-        DataAccessRoleArn: str = ...
+        DataAccessRoleArn: str = ...,
+        FlywheelArn: str = ...
     ) -> CreateEndpointResponseTypeDef:
         """
         Creates a model-specific endpoint for synchronous inference for a previously
         trained custom model For information about endpoints, see [Managing
         endpoints](https://docs.aws.amazon.com/comprehend/latest/dg/manage-
         endpoints.html)_.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.create_endpoint)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#create_endpoint)
         """
+
     async def create_entity_recognizer(
         self,
         *,
         RecognizerName: str,
         DataAccessRoleArn: str,
         InputDataConfig: EntityRecognizerInputDataConfigTypeDef,
         LanguageCode: LanguageCodeType,
@@ -333,169 +390,243 @@
     ) -> CreateEntityRecognizerResponseTypeDef:
         """
         Creates an entity recognizer using submitted files.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.create_entity_recognizer)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#create_entity_recognizer)
         """
+
+    async def create_flywheel(
+        self,
+        *,
+        FlywheelName: str,
+        DataAccessRoleArn: str,
+        DataLakeS3Uri: str,
+        ActiveModelArn: str = ...,
+        TaskConfig: TaskConfigTypeDef = ...,
+        ModelType: ModelTypeType = ...,
+        DataSecurityConfig: DataSecurityConfigTypeDef = ...,
+        ClientRequestToken: str = ...,
+        Tags: Sequence[TagTypeDef] = ...
+    ) -> CreateFlywheelResponseTypeDef:
+        """
+        A flywheel is an Amazon Web Services resource that orchestrates the ongoing
+        training of a model for custom classification or custom entity recognition.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.create_flywheel)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#create_flywheel)
+        """
+
     async def delete_document_classifier(self, *, DocumentClassifierArn: str) -> Dict[str, Any]:
         """
         Deletes a previously created document classifier Only those classifiers that are
         in terminated states (IN_ERROR, TRAINED) will be deleted.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.delete_document_classifier)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#delete_document_classifier)
         """
+
     async def delete_endpoint(self, *, EndpointArn: str) -> Dict[str, Any]:
         """
         Deletes a model-specific endpoint for a previously-trained custom model.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.delete_endpoint)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#delete_endpoint)
         """
+
     async def delete_entity_recognizer(self, *, EntityRecognizerArn: str) -> Dict[str, Any]:
         """
         Deletes an entity recognizer.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.delete_entity_recognizer)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#delete_entity_recognizer)
         """
+
+    async def delete_flywheel(self, *, FlywheelArn: str) -> Dict[str, Any]:
+        """
+        Deletes a flywheel.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.delete_flywheel)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#delete_flywheel)
+        """
+
     async def delete_resource_policy(
         self, *, ResourceArn: str, PolicyRevisionId: str = ...
     ) -> Dict[str, Any]:
         """
         Deletes a resource-based policy that is attached to a custom model.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.delete_resource_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#delete_resource_policy)
         """
+
+    async def describe_dataset(self, *, DatasetArn: str) -> DescribeDatasetResponseTypeDef:
+        """
+        Returns information about the dataset that you specify.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.describe_dataset)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#describe_dataset)
+        """
+
     async def describe_document_classification_job(
         self, *, JobId: str
     ) -> DescribeDocumentClassificationJobResponseTypeDef:
         """
         Gets the properties associated with a document classification job.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.describe_document_classification_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#describe_document_classification_job)
         """
+
     async def describe_document_classifier(
         self, *, DocumentClassifierArn: str
     ) -> DescribeDocumentClassifierResponseTypeDef:
         """
         Gets the properties associated with a document classifier.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.describe_document_classifier)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#describe_document_classifier)
         """
+
     async def describe_dominant_language_detection_job(
         self, *, JobId: str
     ) -> DescribeDominantLanguageDetectionJobResponseTypeDef:
         """
         Gets the properties associated with a dominant language detection job.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.describe_dominant_language_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#describe_dominant_language_detection_job)
         """
+
     async def describe_endpoint(self, *, EndpointArn: str) -> DescribeEndpointResponseTypeDef:
         """
         Gets the properties associated with a specific endpoint.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.describe_endpoint)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#describe_endpoint)
         """
+
     async def describe_entities_detection_job(
         self, *, JobId: str
     ) -> DescribeEntitiesDetectionJobResponseTypeDef:
         """
         Gets the properties associated with an entities detection job.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.describe_entities_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#describe_entities_detection_job)
         """
+
     async def describe_entity_recognizer(
         self, *, EntityRecognizerArn: str
     ) -> DescribeEntityRecognizerResponseTypeDef:
         """
         Provides details about an entity recognizer including status, S3 buckets
         containing training data, recognizer metadata, metrics, and so on.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.describe_entity_recognizer)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#describe_entity_recognizer)
         """
+
     async def describe_events_detection_job(
         self, *, JobId: str
     ) -> DescribeEventsDetectionJobResponseTypeDef:
         """
         Gets the status and details of an events detection job.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.describe_events_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#describe_events_detection_job)
         """
+
+    async def describe_flywheel(self, *, FlywheelArn: str) -> DescribeFlywheelResponseTypeDef:
+        """
+        Provides configuration information about the flywheel.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.describe_flywheel)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#describe_flywheel)
+        """
+
+    async def describe_flywheel_iteration(
+        self, *, FlywheelArn: str, FlywheelIterationId: str
+    ) -> DescribeFlywheelIterationResponseTypeDef:
+        """
+        Retrieve the configuration properties of a flywheel iteration.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.describe_flywheel_iteration)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#describe_flywheel_iteration)
+        """
+
     async def describe_key_phrases_detection_job(
         self, *, JobId: str
     ) -> DescribeKeyPhrasesDetectionJobResponseTypeDef:
         """
         Gets the properties associated with a key phrases detection job.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.describe_key_phrases_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#describe_key_phrases_detection_job)
         """
+
     async def describe_pii_entities_detection_job(
         self, *, JobId: str
     ) -> DescribePiiEntitiesDetectionJobResponseTypeDef:
         """
         Gets the properties associated with a PII entities detection job.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.describe_pii_entities_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#describe_pii_entities_detection_job)
         """
+
     async def describe_resource_policy(
         self, *, ResourceArn: str
     ) -> DescribeResourcePolicyResponseTypeDef:
         """
         Gets the details of a resource-based policy that is attached to a custom model,
         including the JSON body of the policy.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.describe_resource_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#describe_resource_policy)
         """
+
     async def describe_sentiment_detection_job(
         self, *, JobId: str
     ) -> DescribeSentimentDetectionJobResponseTypeDef:
         """
         Gets the properties associated with a sentiment detection job.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.describe_sentiment_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#describe_sentiment_detection_job)
         """
+
     async def describe_targeted_sentiment_detection_job(
         self, *, JobId: str
     ) -> DescribeTargetedSentimentDetectionJobResponseTypeDef:
         """
         Gets the properties associated with a targeted sentiment detection job.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.describe_targeted_sentiment_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#describe_targeted_sentiment_detection_job)
         """
+
     async def describe_topics_detection_job(
         self, *, JobId: str
     ) -> DescribeTopicsDetectionJobResponseTypeDef:
         """
         Gets the properties associated with a topic detection job.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.describe_topics_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#describe_topics_detection_job)
         """
+
     async def detect_dominant_language(self, *, Text: str) -> DetectDominantLanguageResponseTypeDef:
         """
         Determines the dominant language of the input text.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.detect_dominant_language)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#detect_dominant_language)
         """
+
     async def detect_entities(
         self,
         *,
         Text: str = ...,
         LanguageCode: LanguageCodeType = ...,
         EndpointArn: str = ...,
         Bytes: Union[str, bytes, IO[Any], StreamingBody] = ...,
@@ -503,75 +634,82 @@
     ) -> DetectEntitiesResponseTypeDef:
         """
         Detects named entities in input text when you use the pre-trained model.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.detect_entities)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#detect_entities)
         """
+
     async def detect_key_phrases(
         self, *, Text: str, LanguageCode: LanguageCodeType
     ) -> DetectKeyPhrasesResponseTypeDef:
         """
         Detects the key noun phrases found in the text.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.detect_key_phrases)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#detect_key_phrases)
         """
+
     async def detect_pii_entities(
         self, *, Text: str, LanguageCode: LanguageCodeType
     ) -> DetectPiiEntitiesResponseTypeDef:
         """
         Inspects the input text for entities that contain personally identifiable
         information (PII) and returns information about them.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.detect_pii_entities)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#detect_pii_entities)
         """
+
     async def detect_sentiment(
         self, *, Text: str, LanguageCode: LanguageCodeType
     ) -> DetectSentimentResponseTypeDef:
         """
-        Inspects text and returns an inference of the prevailing sentiment ( `POSITIVE`
-        , `NEUTRAL` , `MIXED` , or `NEGATIVE` ).
+        Inspects text and returns an inference of the prevailing sentiment ( `POSITIVE`,
+        `NEUTRAL`, `MIXED`, or `NEGATIVE`).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.detect_sentiment)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#detect_sentiment)
         """
+
     async def detect_syntax(
         self, *, Text: str, LanguageCode: SyntaxLanguageCodeType
     ) -> DetectSyntaxResponseTypeDef:
         """
         Inspects text for syntax and the part of speech of words in the document.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.detect_syntax)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#detect_syntax)
         """
+
     async def detect_targeted_sentiment(
         self, *, Text: str, LanguageCode: LanguageCodeType
     ) -> DetectTargetedSentimentResponseTypeDef:
         """
         Inspects the input text and returns a sentiment analysis for each entity
         identified in the text.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.detect_targeted_sentiment)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#detect_targeted_sentiment)
         """
+
     async def generate_presigned_url(
         self,
         ClientMethod: str,
         Params: Mapping[str, Any] = ...,
         ExpiresIn: int = 3600,
         HttpMethod: str = ...,
     ) -> str:
         """
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#generate_presigned_url)
         """
+
     async def import_model(
         self,
         *,
         SourceModelArn: str,
         ModelName: str = ...,
         VersionName: str = ...,
         ModelKmsKeyId: str = ...,
@@ -581,224 +719,283 @@
         """
         Creates a new custom model that replicates a source custom model that you
         import.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.import_model)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#import_model)
         """
+
+    async def list_datasets(
+        self,
+        *,
+        FlywheelArn: str = ...,
+        Filter: DatasetFilterTypeDef = ...,
+        NextToken: str = ...,
+        MaxResults: int = ...
+    ) -> ListDatasetsResponseTypeDef:
+        """
+        List the datasets that you have configured in this Region.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.list_datasets)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#list_datasets)
+        """
+
     async def list_document_classification_jobs(
         self,
         *,
         Filter: DocumentClassificationJobFilterTypeDef = ...,
         NextToken: str = ...,
         MaxResults: int = ...
     ) -> ListDocumentClassificationJobsResponseTypeDef:
         """
         Gets a list of the documentation classification jobs that you have submitted.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.list_document_classification_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#list_document_classification_jobs)
         """
+
     async def list_document_classifier_summaries(
         self, *, NextToken: str = ..., MaxResults: int = ...
     ) -> ListDocumentClassifierSummariesResponseTypeDef:
         """
         Gets a list of summaries of the document classifiers that you have created See
         also: [AWS API
         Documentation](https://docs.aws.amazon.com/goto/WebAPI/comprehend-2017-11-27/ListDocumentClassifierSummaries).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.list_document_classifier_summaries)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#list_document_classifier_summaries)
         """
+
     async def list_document_classifiers(
         self,
         *,
         Filter: DocumentClassifierFilterTypeDef = ...,
         NextToken: str = ...,
         MaxResults: int = ...
     ) -> ListDocumentClassifiersResponseTypeDef:
         """
         Gets a list of the document classifiers that you have created.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.list_document_classifiers)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#list_document_classifiers)
         """
+
     async def list_dominant_language_detection_jobs(
         self,
         *,
         Filter: DominantLanguageDetectionJobFilterTypeDef = ...,
         NextToken: str = ...,
         MaxResults: int = ...
     ) -> ListDominantLanguageDetectionJobsResponseTypeDef:
         """
         Gets a list of the dominant language detection jobs that you have submitted.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.list_dominant_language_detection_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#list_dominant_language_detection_jobs)
         """
+
     async def list_endpoints(
         self, *, Filter: EndpointFilterTypeDef = ..., NextToken: str = ..., MaxResults: int = ...
     ) -> ListEndpointsResponseTypeDef:
         """
         Gets a list of all existing endpoints that you've created.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.list_endpoints)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#list_endpoints)
         """
+
     async def list_entities_detection_jobs(
         self,
         *,
         Filter: EntitiesDetectionJobFilterTypeDef = ...,
         NextToken: str = ...,
         MaxResults: int = ...
     ) -> ListEntitiesDetectionJobsResponseTypeDef:
         """
         Gets a list of the entity detection jobs that you have submitted.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.list_entities_detection_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#list_entities_detection_jobs)
         """
+
     async def list_entity_recognizer_summaries(
         self, *, NextToken: str = ..., MaxResults: int = ...
     ) -> ListEntityRecognizerSummariesResponseTypeDef:
         """
         Gets a list of summaries for the entity recognizers that you have created.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.list_entity_recognizer_summaries)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#list_entity_recognizer_summaries)
         """
+
     async def list_entity_recognizers(
         self,
         *,
         Filter: EntityRecognizerFilterTypeDef = ...,
         NextToken: str = ...,
         MaxResults: int = ...
     ) -> ListEntityRecognizersResponseTypeDef:
         """
         Gets a list of the properties of all entity recognizers that you created,
         including recognizers currently in training.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.list_entity_recognizers)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#list_entity_recognizers)
         """
+
     async def list_events_detection_jobs(
         self,
         *,
         Filter: EventsDetectionJobFilterTypeDef = ...,
         NextToken: str = ...,
         MaxResults: int = ...
     ) -> ListEventsDetectionJobsResponseTypeDef:
         """
         Gets a list of the events detection jobs that you have submitted.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.list_events_detection_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#list_events_detection_jobs)
         """
+
+    async def list_flywheel_iteration_history(
+        self,
+        *,
+        FlywheelArn: str,
+        Filter: FlywheelIterationFilterTypeDef = ...,
+        NextToken: str = ...,
+        MaxResults: int = ...
+    ) -> ListFlywheelIterationHistoryResponseTypeDef:
+        """
+        Information about the history of a flywheel iteration.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.list_flywheel_iteration_history)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#list_flywheel_iteration_history)
+        """
+
+    async def list_flywheels(
+        self, *, Filter: FlywheelFilterTypeDef = ..., NextToken: str = ..., MaxResults: int = ...
+    ) -> ListFlywheelsResponseTypeDef:
+        """
+        Gets a list of the flywheels that you have created.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.list_flywheels)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#list_flywheels)
+        """
+
     async def list_key_phrases_detection_jobs(
         self,
         *,
         Filter: KeyPhrasesDetectionJobFilterTypeDef = ...,
         NextToken: str = ...,
         MaxResults: int = ...
     ) -> ListKeyPhrasesDetectionJobsResponseTypeDef:
         """
         Get a list of key phrase detection jobs that you have submitted.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.list_key_phrases_detection_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#list_key_phrases_detection_jobs)
         """
+
     async def list_pii_entities_detection_jobs(
         self,
         *,
         Filter: PiiEntitiesDetectionJobFilterTypeDef = ...,
         NextToken: str = ...,
         MaxResults: int = ...
     ) -> ListPiiEntitiesDetectionJobsResponseTypeDef:
         """
         Gets a list of the PII entity detection jobs that you have submitted.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.list_pii_entities_detection_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#list_pii_entities_detection_jobs)
         """
+
     async def list_sentiment_detection_jobs(
         self,
         *,
         Filter: SentimentDetectionJobFilterTypeDef = ...,
         NextToken: str = ...,
         MaxResults: int = ...
     ) -> ListSentimentDetectionJobsResponseTypeDef:
         """
         Gets a list of sentiment detection jobs that you have submitted.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.list_sentiment_detection_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#list_sentiment_detection_jobs)
         """
+
     async def list_tags_for_resource(
         self, *, ResourceArn: str
     ) -> ListTagsForResourceResponseTypeDef:
         """
         Lists all tags associated with a given Amazon Comprehend resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#list_tags_for_resource)
         """
+
     async def list_targeted_sentiment_detection_jobs(
         self,
         *,
         Filter: TargetedSentimentDetectionJobFilterTypeDef = ...,
         NextToken: str = ...,
         MaxResults: int = ...
     ) -> ListTargetedSentimentDetectionJobsResponseTypeDef:
         """
         Gets a list of targeted sentiment detection jobs that you have submitted.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.list_targeted_sentiment_detection_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#list_targeted_sentiment_detection_jobs)
         """
+
     async def list_topics_detection_jobs(
         self,
         *,
         Filter: TopicsDetectionJobFilterTypeDef = ...,
         NextToken: str = ...,
         MaxResults: int = ...
     ) -> ListTopicsDetectionJobsResponseTypeDef:
         """
         Gets a list of the topic detection jobs that you have submitted.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.list_topics_detection_jobs)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#list_topics_detection_jobs)
         """
+
     async def put_resource_policy(
         self, *, ResourceArn: str, ResourcePolicy: str, PolicyRevisionId: str = ...
     ) -> PutResourcePolicyResponseTypeDef:
         """
         Attaches a resource-based policy to a custom model.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.put_resource_policy)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#put_resource_policy)
         """
+
     async def start_document_classification_job(
         self,
         *,
-        DocumentClassifierArn: str,
         InputDataConfig: InputDataConfigTypeDef,
         OutputDataConfig: OutputDataConfigTypeDef,
         DataAccessRoleArn: str,
         JobName: str = ...,
+        DocumentClassifierArn: str = ...,
         ClientRequestToken: str = ...,
         VolumeKmsKeyId: str = ...,
         VpcConfig: VpcConfigTypeDef = ...,
-        Tags: Sequence[TagTypeDef] = ...
+        Tags: Sequence[TagTypeDef] = ...,
+        FlywheelArn: str = ...
     ) -> StartDocumentClassificationJobResponseTypeDef:
         """
         Starts an asynchronous document classification job.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.start_document_classification_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#start_document_classification_job)
         """
+
     async def start_dominant_language_detection_job(
         self,
         *,
         InputDataConfig: InputDataConfigTypeDef,
         OutputDataConfig: OutputDataConfigTypeDef,
         DataAccessRoleArn: str,
         JobName: str = ...,
@@ -810,34 +1007,37 @@
         """
         Starts an asynchronous dominant language detection job for a collection of
         documents.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.start_dominant_language_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#start_dominant_language_detection_job)
         """
+
     async def start_entities_detection_job(
         self,
         *,
         InputDataConfig: InputDataConfigTypeDef,
         OutputDataConfig: OutputDataConfigTypeDef,
         DataAccessRoleArn: str,
         LanguageCode: LanguageCodeType,
         JobName: str = ...,
         EntityRecognizerArn: str = ...,
         ClientRequestToken: str = ...,
         VolumeKmsKeyId: str = ...,
         VpcConfig: VpcConfigTypeDef = ...,
-        Tags: Sequence[TagTypeDef] = ...
+        Tags: Sequence[TagTypeDef] = ...,
+        FlywheelArn: str = ...
     ) -> StartEntitiesDetectionJobResponseTypeDef:
         """
         Starts an asynchronous entity detection job for a collection of documents.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.start_entities_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#start_entities_detection_job)
         """
+
     async def start_events_detection_job(
         self,
         *,
         InputDataConfig: InputDataConfigTypeDef,
         OutputDataConfig: OutputDataConfigTypeDef,
         DataAccessRoleArn: str,
         LanguageCode: LanguageCodeType,
@@ -848,14 +1048,26 @@
     ) -> StartEventsDetectionJobResponseTypeDef:
         """
         Starts an asynchronous event detection job for a collection of documents.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.start_events_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#start_events_detection_job)
         """
+
+    async def start_flywheel_iteration(
+        self, *, FlywheelArn: str, ClientRequestToken: str = ...
+    ) -> StartFlywheelIterationResponseTypeDef:
+        """
+        Start the flywheel iteration.This operation uses any new datasets to train a new
+        model version.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.start_flywheel_iteration)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#start_flywheel_iteration)
+        """
+
     async def start_key_phrases_detection_job(
         self,
         *,
         InputDataConfig: InputDataConfigTypeDef,
         OutputDataConfig: OutputDataConfigTypeDef,
         DataAccessRoleArn: str,
         LanguageCode: LanguageCodeType,
@@ -867,14 +1079,15 @@
     ) -> StartKeyPhrasesDetectionJobResponseTypeDef:
         """
         Starts an asynchronous key phrase detection job for a collection of documents.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.start_key_phrases_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#start_key_phrases_detection_job)
         """
+
     async def start_pii_entities_detection_job(
         self,
         *,
         InputDataConfig: InputDataConfigTypeDef,
         OutputDataConfig: OutputDataConfigTypeDef,
         Mode: PiiEntitiesDetectionModeType,
         DataAccessRoleArn: str,
@@ -886,14 +1099,15 @@
     ) -> StartPiiEntitiesDetectionJobResponseTypeDef:
         """
         Starts an asynchronous PII entity detection job for a collection of documents.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.start_pii_entities_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#start_pii_entities_detection_job)
         """
+
     async def start_sentiment_detection_job(
         self,
         *,
         InputDataConfig: InputDataConfigTypeDef,
         OutputDataConfig: OutputDataConfigTypeDef,
         DataAccessRoleArn: str,
         LanguageCode: LanguageCodeType,
@@ -905,14 +1119,15 @@
     ) -> StartSentimentDetectionJobResponseTypeDef:
         """
         Starts an asynchronous sentiment detection job for a collection of documents.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.start_sentiment_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#start_sentiment_detection_job)
         """
+
     async def start_targeted_sentiment_detection_job(
         self,
         *,
         InputDataConfig: InputDataConfigTypeDef,
         OutputDataConfig: OutputDataConfigTypeDef,
         DataAccessRoleArn: str,
         LanguageCode: LanguageCodeType,
@@ -925,14 +1140,15 @@
         """
         Starts an asynchronous targeted sentiment detection job for a collection of
         documents.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.start_targeted_sentiment_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#start_targeted_sentiment_detection_job)
         """
+
     async def start_topics_detection_job(
         self,
         *,
         InputDataConfig: InputDataConfigTypeDef,
         OutputDataConfig: OutputDataConfigTypeDef,
         DataAccessRoleArn: str,
         JobName: str = ...,
@@ -944,202 +1160,242 @@
     ) -> StartTopicsDetectionJobResponseTypeDef:
         """
         Starts an asynchronous topic detection job.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.start_topics_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#start_topics_detection_job)
         """
+
     async def stop_dominant_language_detection_job(
         self, *, JobId: str
     ) -> StopDominantLanguageDetectionJobResponseTypeDef:
         """
         Stops a dominant language detection job in progress.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.stop_dominant_language_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#stop_dominant_language_detection_job)
         """
+
     async def stop_entities_detection_job(
         self, *, JobId: str
     ) -> StopEntitiesDetectionJobResponseTypeDef:
         """
         Stops an entities detection job in progress.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.stop_entities_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#stop_entities_detection_job)
         """
+
     async def stop_events_detection_job(
         self, *, JobId: str
     ) -> StopEventsDetectionJobResponseTypeDef:
         """
         Stops an events detection job in progress.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.stop_events_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#stop_events_detection_job)
         """
+
     async def stop_key_phrases_detection_job(
         self, *, JobId: str
     ) -> StopKeyPhrasesDetectionJobResponseTypeDef:
         """
         Stops a key phrases detection job in progress.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.stop_key_phrases_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#stop_key_phrases_detection_job)
         """
+
     async def stop_pii_entities_detection_job(
         self, *, JobId: str
     ) -> StopPiiEntitiesDetectionJobResponseTypeDef:
         """
         Stops a PII entities detection job in progress.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.stop_pii_entities_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#stop_pii_entities_detection_job)
         """
+
     async def stop_sentiment_detection_job(
         self, *, JobId: str
     ) -> StopSentimentDetectionJobResponseTypeDef:
         """
         Stops a sentiment detection job in progress.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.stop_sentiment_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#stop_sentiment_detection_job)
         """
+
     async def stop_targeted_sentiment_detection_job(
         self, *, JobId: str
     ) -> StopTargetedSentimentDetectionJobResponseTypeDef:
         """
         Stops a targeted sentiment detection job in progress.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.stop_targeted_sentiment_detection_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#stop_targeted_sentiment_detection_job)
         """
+
     async def stop_training_document_classifier(
         self, *, DocumentClassifierArn: str
     ) -> Dict[str, Any]:
         """
         Stops a document classifier training job while in progress.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.stop_training_document_classifier)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#stop_training_document_classifier)
         """
+
     async def stop_training_entity_recognizer(self, *, EntityRecognizerArn: str) -> Dict[str, Any]:
         """
         Stops an entity recognizer training job while in progress.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.stop_training_entity_recognizer)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#stop_training_entity_recognizer)
         """
+
     async def tag_resource(self, *, ResourceArn: str, Tags: Sequence[TagTypeDef]) -> Dict[str, Any]:
         """
         Associates a specific tag with an Amazon Comprehend resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#tag_resource)
         """
+
     async def untag_resource(self, *, ResourceArn: str, TagKeys: Sequence[str]) -> Dict[str, Any]:
         """
         Removes a specific tag associated with an Amazon Comprehend resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#untag_resource)
         """
+
     async def update_endpoint(
         self,
         *,
         EndpointArn: str,
         DesiredModelArn: str = ...,
         DesiredInferenceUnits: int = ...,
-        DesiredDataAccessRoleArn: str = ...
-    ) -> Dict[str, Any]:
+        DesiredDataAccessRoleArn: str = ...,
+        FlywheelArn: str = ...
+    ) -> UpdateEndpointResponseTypeDef:
         """
         Updates information about the specified endpoint.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.update_endpoint)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#update_endpoint)
         """
+
+    async def update_flywheel(
+        self,
+        *,
+        FlywheelArn: str,
+        ActiveModelArn: str = ...,
+        DataAccessRoleArn: str = ...,
+        DataSecurityConfig: UpdateDataSecurityConfigTypeDef = ...
+    ) -> UpdateFlywheelResponseTypeDef:
+        """
+        Update the configuration information for an existing flywheel.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.update_flywheel)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#update_flywheel)
+        """
+
     @overload
     def get_paginator(
         self, operation_name: Literal["list_document_classification_jobs"]
     ) -> ListDocumentClassificationJobsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#get_paginator)
         """
+
     @overload
     def get_paginator(
         self, operation_name: Literal["list_document_classifiers"]
     ) -> ListDocumentClassifiersPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#get_paginator)
         """
+
     @overload
     def get_paginator(
         self, operation_name: Literal["list_dominant_language_detection_jobs"]
     ) -> ListDominantLanguageDetectionJobsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#get_paginator)
         """
+
     @overload
     def get_paginator(self, operation_name: Literal["list_endpoints"]) -> ListEndpointsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#get_paginator)
         """
+
     @overload
     def get_paginator(
         self, operation_name: Literal["list_entities_detection_jobs"]
     ) -> ListEntitiesDetectionJobsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#get_paginator)
         """
+
     @overload
     def get_paginator(
         self, operation_name: Literal["list_entity_recognizers"]
     ) -> ListEntityRecognizersPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#get_paginator)
         """
+
     @overload
     def get_paginator(
         self, operation_name: Literal["list_key_phrases_detection_jobs"]
     ) -> ListKeyPhrasesDetectionJobsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#get_paginator)
         """
+
     @overload
     def get_paginator(
         self, operation_name: Literal["list_pii_entities_detection_jobs"]
     ) -> ListPiiEntitiesDetectionJobsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#get_paginator)
         """
+
     @overload
     def get_paginator(
         self, operation_name: Literal["list_sentiment_detection_jobs"]
     ) -> ListSentimentDetectionJobsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#get_paginator)
         """
+
     @overload
     def get_paginator(
         self, operation_name: Literal["list_topics_detection_jobs"]
     ) -> ListTopicsDetectionJobsPaginator:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client.get_paginator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/#get_paginator)
         """
+
     async def __aenter__(self) -> "ComprehendClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/)
         """
+
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/client/)
         """
```

### Comparing `types-aiobotocore-comprehend-2.5.0.post1/types_aiobotocore_comprehend/literals.py` & `types-aiobotocore-comprehend-2.5.1/types_aiobotocore_comprehend/literals.py`

 * *Files 8% similar despite different names*

```diff
@@ -18,38 +18,46 @@
 else:
     from typing_extensions import Literal
 
 
 __all__ = (
     "AugmentedManifestsDocumentTypeFormatType",
     "BlockTypeType",
+    "DatasetDataFormatType",
+    "DatasetStatusType",
+    "DatasetTypeType",
     "DocumentClassifierDataFormatType",
+    "DocumentClassifierDocumentTypeFormatType",
     "DocumentClassifierModeType",
     "DocumentReadActionType",
     "DocumentReadFeatureTypesType",
     "DocumentReadModeType",
     "DocumentTypeType",
     "EndpointStatusType",
     "EntityRecognizerDataFormatType",
     "EntityTypeType",
+    "FlywheelIterationStatusType",
+    "FlywheelStatusType",
     "InputFormatType",
     "JobStatusType",
     "LanguageCodeType",
     "ListDocumentClassificationJobsPaginatorName",
     "ListDocumentClassifiersPaginatorName",
     "ListDominantLanguageDetectionJobsPaginatorName",
     "ListEndpointsPaginatorName",
     "ListEntitiesDetectionJobsPaginatorName",
     "ListEntityRecognizersPaginatorName",
     "ListKeyPhrasesDetectionJobsPaginatorName",
     "ListPiiEntitiesDetectionJobsPaginatorName",
     "ListSentimentDetectionJobsPaginatorName",
     "ListTopicsDetectionJobsPaginatorName",
     "ModelStatusType",
+    "ModelTypeType",
     "PageBasedErrorCodeType",
+    "PageBasedWarningCodeType",
     "PartOfSpeechTagTypeType",
     "PiiEntitiesDetectionMaskModeType",
     "PiiEntitiesDetectionModeType",
     "PiiEntityTypeType",
     "RelationshipTypeType",
     "SentimentTypeType",
     "SplitType",
@@ -63,15 +71,21 @@
 )
 
 
 AugmentedManifestsDocumentTypeFormatType = Literal[
     "PLAIN_TEXT_DOCUMENT", "SEMI_STRUCTURED_DOCUMENT"
 ]
 BlockTypeType = Literal["LINE", "WORD"]
+DatasetDataFormatType = Literal["AUGMENTED_MANIFEST", "COMPREHEND_CSV"]
+DatasetStatusType = Literal["COMPLETED", "CREATING", "FAILED"]
+DatasetTypeType = Literal["TEST", "TRAIN"]
 DocumentClassifierDataFormatType = Literal["AUGMENTED_MANIFEST", "COMPREHEND_CSV"]
+DocumentClassifierDocumentTypeFormatType = Literal[
+    "PLAIN_TEXT_DOCUMENT", "SEMI_STRUCTURED_DOCUMENT"
+]
 DocumentClassifierModeType = Literal["MULTI_CLASS", "MULTI_LABEL"]
 DocumentReadActionType = Literal["TEXTRACT_ANALYZE_DOCUMENT", "TEXTRACT_DETECT_DOCUMENT_TEXT"]
 DocumentReadFeatureTypesType = Literal["FORMS", "TABLES"]
 DocumentReadModeType = Literal["FORCE_DOCUMENT_READ_ACTION", "SERVICE_DEFAULT"]
 DocumentTypeType = Literal[
     "IMAGE",
     "MS_WORD",
@@ -90,14 +104,18 @@
     "LOCATION",
     "ORGANIZATION",
     "OTHER",
     "PERSON",
     "QUANTITY",
     "TITLE",
 ]
+FlywheelIterationStatusType = Literal[
+    "COMPLETED", "EVALUATING", "FAILED", "STOPPED", "STOP_REQUESTED", "TRAINING"
+]
+FlywheelStatusType = Literal["ACTIVE", "CREATING", "DELETING", "FAILED", "UPDATING"]
 InputFormatType = Literal["ONE_DOC_PER_FILE", "ONE_DOC_PER_LINE"]
 JobStatusType = Literal[
     "COMPLETED", "FAILED", "IN_PROGRESS", "STOPPED", "STOP_REQUESTED", "SUBMITTED"
 ]
 LanguageCodeType = Literal[
     "ar", "de", "en", "es", "fr", "hi", "it", "ja", "ko", "pt", "zh", "zh-TW"
 ]
@@ -108,23 +126,35 @@
 ListEntitiesDetectionJobsPaginatorName = Literal["list_entities_detection_jobs"]
 ListEntityRecognizersPaginatorName = Literal["list_entity_recognizers"]
 ListKeyPhrasesDetectionJobsPaginatorName = Literal["list_key_phrases_detection_jobs"]
 ListPiiEntitiesDetectionJobsPaginatorName = Literal["list_pii_entities_detection_jobs"]
 ListSentimentDetectionJobsPaginatorName = Literal["list_sentiment_detection_jobs"]
 ListTopicsDetectionJobsPaginatorName = Literal["list_topics_detection_jobs"]
 ModelStatusType = Literal[
-    "DELETING", "IN_ERROR", "STOPPED", "STOP_REQUESTED", "SUBMITTED", "TRAINED", "TRAINING"
+    "DELETING",
+    "IN_ERROR",
+    "STOPPED",
+    "STOP_REQUESTED",
+    "SUBMITTED",
+    "TRAINED",
+    "TRAINED_WITH_WARNING",
+    "TRAINING",
 ]
+ModelTypeType = Literal["DOCUMENT_CLASSIFIER", "ENTITY_RECOGNIZER"]
 PageBasedErrorCodeType = Literal[
     "INTERNAL_SERVER_ERROR",
     "PAGE_CHARACTERS_EXCEEDED",
     "PAGE_SIZE_EXCEEDED",
     "TEXTRACT_BAD_PAGE",
     "TEXTRACT_PROVISIONED_THROUGHPUT_EXCEEDED",
 ]
+PageBasedWarningCodeType = Literal[
+    "INFERENCING_NATIVE_DOCUMENT_WITH_PLAINTEXT_TRAINED_MODEL",
+    "INFERENCING_PLAINTEXT_WITH_NATIVE_TRAINED_MODEL",
+]
 PartOfSpeechTagTypeType = Literal[
     "ADJ",
     "ADP",
     "ADV",
     "AUX",
     "CCONJ",
     "CONJ",
@@ -264,14 +294,15 @@
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
@@ -350,14 +381,15 @@
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
@@ -368,14 +400,15 @@
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
@@ -411,14 +444,15 @@
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
@@ -437,16 +471,19 @@
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
@@ -530,15 +567,17 @@
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

### Comparing `types-aiobotocore-comprehend-2.5.0.post1/types_aiobotocore_comprehend/literals.pyi` & `types-aiobotocore-comprehend-2.5.1/types_aiobotocore_comprehend/literals.pyi`

 * *Files 8% similar despite different names*

```diff
@@ -17,38 +17,46 @@
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 __all__ = (
     "AugmentedManifestsDocumentTypeFormatType",
     "BlockTypeType",
+    "DatasetDataFormatType",
+    "DatasetStatusType",
+    "DatasetTypeType",
     "DocumentClassifierDataFormatType",
+    "DocumentClassifierDocumentTypeFormatType",
     "DocumentClassifierModeType",
     "DocumentReadActionType",
     "DocumentReadFeatureTypesType",
     "DocumentReadModeType",
     "DocumentTypeType",
     "EndpointStatusType",
     "EntityRecognizerDataFormatType",
     "EntityTypeType",
+    "FlywheelIterationStatusType",
+    "FlywheelStatusType",
     "InputFormatType",
     "JobStatusType",
     "LanguageCodeType",
     "ListDocumentClassificationJobsPaginatorName",
     "ListDocumentClassifiersPaginatorName",
     "ListDominantLanguageDetectionJobsPaginatorName",
     "ListEndpointsPaginatorName",
     "ListEntitiesDetectionJobsPaginatorName",
     "ListEntityRecognizersPaginatorName",
     "ListKeyPhrasesDetectionJobsPaginatorName",
     "ListPiiEntitiesDetectionJobsPaginatorName",
     "ListSentimentDetectionJobsPaginatorName",
     "ListTopicsDetectionJobsPaginatorName",
     "ModelStatusType",
+    "ModelTypeType",
     "PageBasedErrorCodeType",
+    "PageBasedWarningCodeType",
     "PartOfSpeechTagTypeType",
     "PiiEntitiesDetectionMaskModeType",
     "PiiEntitiesDetectionModeType",
     "PiiEntityTypeType",
     "RelationshipTypeType",
     "SentimentTypeType",
     "SplitType",
@@ -61,15 +69,21 @@
     "RegionName",
 )
 
 AugmentedManifestsDocumentTypeFormatType = Literal[
     "PLAIN_TEXT_DOCUMENT", "SEMI_STRUCTURED_DOCUMENT"
 ]
 BlockTypeType = Literal["LINE", "WORD"]
+DatasetDataFormatType = Literal["AUGMENTED_MANIFEST", "COMPREHEND_CSV"]
+DatasetStatusType = Literal["COMPLETED", "CREATING", "FAILED"]
+DatasetTypeType = Literal["TEST", "TRAIN"]
 DocumentClassifierDataFormatType = Literal["AUGMENTED_MANIFEST", "COMPREHEND_CSV"]
+DocumentClassifierDocumentTypeFormatType = Literal[
+    "PLAIN_TEXT_DOCUMENT", "SEMI_STRUCTURED_DOCUMENT"
+]
 DocumentClassifierModeType = Literal["MULTI_CLASS", "MULTI_LABEL"]
 DocumentReadActionType = Literal["TEXTRACT_ANALYZE_DOCUMENT", "TEXTRACT_DETECT_DOCUMENT_TEXT"]
 DocumentReadFeatureTypesType = Literal["FORMS", "TABLES"]
 DocumentReadModeType = Literal["FORCE_DOCUMENT_READ_ACTION", "SERVICE_DEFAULT"]
 DocumentTypeType = Literal[
     "IMAGE",
     "MS_WORD",
@@ -88,14 +102,18 @@
     "LOCATION",
     "ORGANIZATION",
     "OTHER",
     "PERSON",
     "QUANTITY",
     "TITLE",
 ]
+FlywheelIterationStatusType = Literal[
+    "COMPLETED", "EVALUATING", "FAILED", "STOPPED", "STOP_REQUESTED", "TRAINING"
+]
+FlywheelStatusType = Literal["ACTIVE", "CREATING", "DELETING", "FAILED", "UPDATING"]
 InputFormatType = Literal["ONE_DOC_PER_FILE", "ONE_DOC_PER_LINE"]
 JobStatusType = Literal[
     "COMPLETED", "FAILED", "IN_PROGRESS", "STOPPED", "STOP_REQUESTED", "SUBMITTED"
 ]
 LanguageCodeType = Literal[
     "ar", "de", "en", "es", "fr", "hi", "it", "ja", "ko", "pt", "zh", "zh-TW"
 ]
@@ -106,23 +124,35 @@
 ListEntitiesDetectionJobsPaginatorName = Literal["list_entities_detection_jobs"]
 ListEntityRecognizersPaginatorName = Literal["list_entity_recognizers"]
 ListKeyPhrasesDetectionJobsPaginatorName = Literal["list_key_phrases_detection_jobs"]
 ListPiiEntitiesDetectionJobsPaginatorName = Literal["list_pii_entities_detection_jobs"]
 ListSentimentDetectionJobsPaginatorName = Literal["list_sentiment_detection_jobs"]
 ListTopicsDetectionJobsPaginatorName = Literal["list_topics_detection_jobs"]
 ModelStatusType = Literal[
-    "DELETING", "IN_ERROR", "STOPPED", "STOP_REQUESTED", "SUBMITTED", "TRAINED", "TRAINING"
+    "DELETING",
+    "IN_ERROR",
+    "STOPPED",
+    "STOP_REQUESTED",
+    "SUBMITTED",
+    "TRAINED",
+    "TRAINED_WITH_WARNING",
+    "TRAINING",
 ]
+ModelTypeType = Literal["DOCUMENT_CLASSIFIER", "ENTITY_RECOGNIZER"]
 PageBasedErrorCodeType = Literal[
     "INTERNAL_SERVER_ERROR",
     "PAGE_CHARACTERS_EXCEEDED",
     "PAGE_SIZE_EXCEEDED",
     "TEXTRACT_BAD_PAGE",
     "TEXTRACT_PROVISIONED_THROUGHPUT_EXCEEDED",
 ]
+PageBasedWarningCodeType = Literal[
+    "INFERENCING_NATIVE_DOCUMENT_WITH_PLAINTEXT_TRAINED_MODEL",
+    "INFERENCING_PLAINTEXT_WITH_NATIVE_TRAINED_MODEL",
+]
 PartOfSpeechTagTypeType = Literal[
     "ADJ",
     "ADP",
     "ADV",
     "AUX",
     "CCONJ",
     "CONJ",
@@ -262,14 +292,15 @@
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
@@ -348,14 +379,15 @@
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
@@ -366,14 +398,15 @@
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
@@ -409,14 +442,15 @@
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
@@ -435,16 +469,19 @@
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
@@ -528,15 +565,17 @@
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

### Comparing `types-aiobotocore-comprehend-2.5.0.post1/types_aiobotocore_comprehend/paginator.py` & `types-aiobotocore-comprehend-2.5.1/types_aiobotocore_comprehend/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -34,16 +34,15 @@
         list_entity_recognizers_paginator: ListEntityRecognizersPaginator = client.get_paginator("list_entity_recognizers")
         list_key_phrases_detection_jobs_paginator: ListKeyPhrasesDetectionJobsPaginator = client.get_paginator("list_key_phrases_detection_jobs")
         list_pii_entities_detection_jobs_paginator: ListPiiEntitiesDetectionJobsPaginator = client.get_paginator("list_pii_entities_detection_jobs")
         list_sentiment_detection_jobs_paginator: ListSentimentDetectionJobsPaginator = client.get_paginator("list_sentiment_detection_jobs")
         list_topics_detection_jobs_paginator: ListTopicsDetectionJobsPaginator = client.get_paginator("list_topics_detection_jobs")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DocumentClassificationJobFilterTypeDef,
     DocumentClassifierFilterTypeDef,
@@ -64,20 +63,14 @@
     ListTopicsDetectionJobsResponseTypeDef,
     PaginatorConfigTypeDef,
     PiiEntitiesDetectionJobFilterTypeDef,
     SentimentDetectionJobFilterTypeDef,
     TopicsDetectionJobFilterTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListDocumentClassificationJobsPaginator",
     "ListDocumentClassifiersPaginator",
     "ListDominantLanguageDetectionJobsPaginator",
     "ListEndpointsPaginator",
     "ListEntitiesDetectionJobsPaginator",
     "ListEntityRecognizersPaginator",
@@ -104,15 +97,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/paginators/#listdocumentclassificationjobspaginator)
     """
 
     def paginate(
         self,
         *,
         Filter: DocumentClassificationJobFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDocumentClassificationJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Paginator.ListDocumentClassificationJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/paginators/#listdocumentclassificationjobspaginator)
         """
 
 
@@ -122,15 +115,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/paginators/#listdocumentclassifierspaginator)
     """
 
     def paginate(
         self,
         *,
         Filter: DocumentClassifierFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDocumentClassifiersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Paginator.ListDocumentClassifiers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/paginators/#listdocumentclassifierspaginator)
         """
 
 
@@ -140,30 +133,33 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/paginators/#listdominantlanguagedetectionjobspaginator)
     """
 
     def paginate(
         self,
         *,
         Filter: DominantLanguageDetectionJobFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDominantLanguageDetectionJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Paginator.ListDominantLanguageDetectionJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/paginators/#listdominantlanguagedetectionjobspaginator)
         """
 
 
 class ListEndpointsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Paginator.ListEndpoints)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/paginators/#listendpointspaginator)
     """
 
     def paginate(
-        self, *, Filter: EndpointFilterTypeDef = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        Filter: EndpointFilterTypeDef = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEndpointsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Paginator.ListEndpoints.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/paginators/#listendpointspaginator)
         """
 
 
@@ -173,15 +169,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/paginators/#listentitiesdetectionjobspaginator)
     """
 
     def paginate(
         self,
         *,
         Filter: EntitiesDetectionJobFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEntitiesDetectionJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Paginator.ListEntitiesDetectionJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/paginators/#listentitiesdetectionjobspaginator)
         """
 
 
@@ -191,15 +187,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/paginators/#listentityrecognizerspaginator)
     """
 
     def paginate(
         self,
         *,
         Filter: EntityRecognizerFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEntityRecognizersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Paginator.ListEntityRecognizers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/paginators/#listentityrecognizerspaginator)
         """
 
 
@@ -209,15 +205,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/paginators/#listkeyphrasesdetectionjobspaginator)
     """
 
     def paginate(
         self,
         *,
         Filter: KeyPhrasesDetectionJobFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListKeyPhrasesDetectionJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Paginator.ListKeyPhrasesDetectionJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/paginators/#listkeyphrasesdetectionjobspaginator)
         """
 
 
@@ -227,15 +223,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/paginators/#listpiientitiesdetectionjobspaginator)
     """
 
     def paginate(
         self,
         *,
         Filter: PiiEntitiesDetectionJobFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPiiEntitiesDetectionJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Paginator.ListPiiEntitiesDetectionJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/paginators/#listpiientitiesdetectionjobspaginator)
         """
 
 
@@ -245,15 +241,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/paginators/#listsentimentdetectionjobspaginator)
     """
 
     def paginate(
         self,
         *,
         Filter: SentimentDetectionJobFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSentimentDetectionJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Paginator.ListSentimentDetectionJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/paginators/#listsentimentdetectionjobspaginator)
         """
 
 
@@ -263,13 +259,13 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/paginators/#listtopicsdetectionjobspaginator)
     """
 
     def paginate(
         self,
         *,
         Filter: TopicsDetectionJobFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTopicsDetectionJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Paginator.ListTopicsDetectionJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/paginators/#listtopicsdetectionjobspaginator)
         """
```

### Comparing `types-aiobotocore-comprehend-2.5.0.post1/types_aiobotocore_comprehend/paginator.pyi` & `types-aiobotocore-comprehend-2.5.1/types_aiobotocore_comprehend/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -34,16 +34,15 @@
         list_entity_recognizers_paginator: ListEntityRecognizersPaginator = client.get_paginator("list_entity_recognizers")
         list_key_phrases_detection_jobs_paginator: ListKeyPhrasesDetectionJobsPaginator = client.get_paginator("list_key_phrases_detection_jobs")
         list_pii_entities_detection_jobs_paginator: ListPiiEntitiesDetectionJobsPaginator = client.get_paginator("list_pii_entities_detection_jobs")
         list_sentiment_detection_jobs_paginator: ListSentimentDetectionJobsPaginator = client.get_paginator("list_sentiment_detection_jobs")
         list_topics_detection_jobs_paginator: ListTopicsDetectionJobsPaginator = client.get_paginator("list_topics_detection_jobs")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DocumentClassificationJobFilterTypeDef,
     DocumentClassifierFilterTypeDef,
@@ -64,19 +63,14 @@
     ListTopicsDetectionJobsResponseTypeDef,
     PaginatorConfigTypeDef,
     PiiEntitiesDetectionJobFilterTypeDef,
     SentimentDetectionJobFilterTypeDef,
     TopicsDetectionJobFilterTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListDocumentClassificationJobsPaginator",
     "ListDocumentClassifiersPaginator",
     "ListDominantLanguageDetectionJobsPaginator",
     "ListEndpointsPaginator",
     "ListEntitiesDetectionJobsPaginator",
     "ListEntityRecognizersPaginator",
@@ -100,15 +94,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/paginators/#listdocumentclassificationjobspaginator)
     """
 
     def paginate(
         self,
         *,
         Filter: DocumentClassificationJobFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDocumentClassificationJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Paginator.ListDocumentClassificationJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/paginators/#listdocumentclassificationjobspaginator)
         """
 
 class ListDocumentClassifiersPaginator(AioPaginator):
@@ -117,15 +111,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/paginators/#listdocumentclassifierspaginator)
     """
 
     def paginate(
         self,
         *,
         Filter: DocumentClassifierFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDocumentClassifiersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Paginator.ListDocumentClassifiers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/paginators/#listdocumentclassifierspaginator)
         """
 
 class ListDominantLanguageDetectionJobsPaginator(AioPaginator):
@@ -134,29 +128,32 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/paginators/#listdominantlanguagedetectionjobspaginator)
     """
 
     def paginate(
         self,
         *,
         Filter: DominantLanguageDetectionJobFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDominantLanguageDetectionJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Paginator.ListDominantLanguageDetectionJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/paginators/#listdominantlanguagedetectionjobspaginator)
         """
 
 class ListEndpointsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Paginator.ListEndpoints)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/paginators/#listendpointspaginator)
     """
 
     def paginate(
-        self, *, Filter: EndpointFilterTypeDef = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        Filter: EndpointFilterTypeDef = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEndpointsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Paginator.ListEndpoints.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/paginators/#listendpointspaginator)
         """
 
 class ListEntitiesDetectionJobsPaginator(AioPaginator):
@@ -165,15 +162,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/paginators/#listentitiesdetectionjobspaginator)
     """
 
     def paginate(
         self,
         *,
         Filter: EntitiesDetectionJobFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEntitiesDetectionJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Paginator.ListEntitiesDetectionJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/paginators/#listentitiesdetectionjobspaginator)
         """
 
 class ListEntityRecognizersPaginator(AioPaginator):
@@ -182,15 +179,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/paginators/#listentityrecognizerspaginator)
     """
 
     def paginate(
         self,
         *,
         Filter: EntityRecognizerFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEntityRecognizersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Paginator.ListEntityRecognizers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/paginators/#listentityrecognizerspaginator)
         """
 
 class ListKeyPhrasesDetectionJobsPaginator(AioPaginator):
@@ -199,15 +196,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/paginators/#listkeyphrasesdetectionjobspaginator)
     """
 
     def paginate(
         self,
         *,
         Filter: KeyPhrasesDetectionJobFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListKeyPhrasesDetectionJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Paginator.ListKeyPhrasesDetectionJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/paginators/#listkeyphrasesdetectionjobspaginator)
         """
 
 class ListPiiEntitiesDetectionJobsPaginator(AioPaginator):
@@ -216,15 +213,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/paginators/#listpiientitiesdetectionjobspaginator)
     """
 
     def paginate(
         self,
         *,
         Filter: PiiEntitiesDetectionJobFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPiiEntitiesDetectionJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Paginator.ListPiiEntitiesDetectionJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/paginators/#listpiientitiesdetectionjobspaginator)
         """
 
 class ListSentimentDetectionJobsPaginator(AioPaginator):
@@ -233,15 +230,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/paginators/#listsentimentdetectionjobspaginator)
     """
 
     def paginate(
         self,
         *,
         Filter: SentimentDetectionJobFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSentimentDetectionJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Paginator.ListSentimentDetectionJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/paginators/#listsentimentdetectionjobspaginator)
         """
 
 class ListTopicsDetectionJobsPaginator(AioPaginator):
@@ -250,13 +247,13 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/paginators/#listtopicsdetectionjobspaginator)
     """
 
     def paginate(
         self,
         *,
         Filter: TopicsDetectionJobFilterTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTopicsDetectionJobsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend.Paginator.ListTopicsDetectionJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/paginators/#listtopicsdetectionjobspaginator)
         """
```

### Comparing `types-aiobotocore-comprehend-2.5.0.post1/types_aiobotocore_comprehend/type_defs.py` & `types-aiobotocore-comprehend-2.5.1/types_aiobotocore_comprehend/type_defs.pyi`

 * *Files 13% similar despite different names*

```diff
@@ -16,28 +16,36 @@
 from typing import IO, Any, Dict, List, Sequence, Union
 
 from aiobotocore.response import StreamingBody
 
 from .literals import (
     AugmentedManifestsDocumentTypeFormatType,
     BlockTypeType,
+    DatasetDataFormatType,
+    DatasetStatusType,
+    DatasetTypeType,
     DocumentClassifierDataFormatType,
+    DocumentClassifierDocumentTypeFormatType,
     DocumentClassifierModeType,
     DocumentReadActionType,
     DocumentReadFeatureTypesType,
     DocumentReadModeType,
     DocumentTypeType,
     EndpointStatusType,
     EntityRecognizerDataFormatType,
     EntityTypeType,
+    FlywheelIterationStatusType,
+    FlywheelStatusType,
     InputFormatType,
     JobStatusType,
     LanguageCodeType,
     ModelStatusType,
+    ModelTypeType,
     PageBasedErrorCodeType,
+    PageBasedWarningCodeType,
     PartOfSpeechTagTypeType,
     PiiEntitiesDetectionMaskModeType,
     PiiEntitiesDetectionModeType,
     PiiEntityTypeType,
     SentimentTypeType,
     SplitType,
     SyntaxLanguageCodeType,
@@ -49,21 +57,19 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "AugmentedManifestsListItemTypeDef",
     "DominantLanguageTypeDef",
     "BatchDetectDominantLanguageRequestRequestTypeDef",
     "BatchItemErrorTypeDef",
-    "ResponseMetadataTypeDef",
     "BatchDetectEntitiesRequestRequestTypeDef",
     "KeyPhraseTypeDef",
     "BatchDetectKeyPhrasesRequestRequestTypeDef",
     "SentimentScoreTypeDef",
     "BatchDetectSentimentRequestRequestTypeDef",
     "BatchDetectSyntaxRequestRequestTypeDef",
     "BatchDetectTargetedSentimentRequestRequestTypeDef",
@@ -72,111 +78,135 @@
     "BoundingBoxTypeDef",
     "ClassifierEvaluationMetricsTypeDef",
     "DocumentReaderConfigTypeDef",
     "DocumentClassTypeDef",
     "DocumentLabelTypeDef",
     "DocumentTypeListItemTypeDef",
     "ErrorsListItemTypeDef",
+    "WarningsListItemTypeDef",
     "ContainsPiiEntitiesRequestRequestTypeDef",
     "EntityLabelTypeDef",
-    "DocumentClassifierOutputDataConfigTypeDef",
     "TagTypeDef",
+    "CreateDatasetResponseTypeDef",
+    "DocumentClassifierOutputDataConfigTypeDef",
     "VpcConfigTypeDef",
+    "CreateDocumentClassifierResponseTypeDef",
+    "CreateEndpointResponseTypeDef",
+    "CreateEntityRecognizerResponseTypeDef",
+    "CreateFlywheelResponseTypeDef",
+    "DatasetAugmentedManifestsListItemTypeDef",
+    "DatasetDocumentClassifierInputDataConfigTypeDef",
+    "DatasetEntityRecognizerAnnotationsTypeDef",
+    "DatasetEntityRecognizerDocumentsTypeDef",
+    "DatasetEntityRecognizerEntityListTypeDef",
+    "DatasetFilterTypeDef",
+    "DatasetPropertiesTypeDef",
     "DeleteDocumentClassifierRequestRequestTypeDef",
     "DeleteEndpointRequestRequestTypeDef",
     "DeleteEntityRecognizerRequestRequestTypeDef",
+    "DeleteFlywheelRequestRequestTypeDef",
     "DeleteResourcePolicyRequestRequestTypeDef",
+    "DescribeDatasetRequestRequestTypeDef",
     "DescribeDocumentClassificationJobRequestRequestTypeDef",
     "DescribeDocumentClassifierRequestRequestTypeDef",
     "DescribeDominantLanguageDetectionJobRequestRequestTypeDef",
     "DescribeEndpointRequestRequestTypeDef",
     "EndpointPropertiesTypeDef",
     "DescribeEntitiesDetectionJobRequestRequestTypeDef",
     "DescribeEntityRecognizerRequestRequestTypeDef",
     "DescribeEventsDetectionJobRequestRequestTypeDef",
+    "DescribeFlywheelIterationRequestRequestTypeDef",
+    "DescribeFlywheelRequestRequestTypeDef",
     "DescribeKeyPhrasesDetectionJobRequestRequestTypeDef",
     "DescribePiiEntitiesDetectionJobRequestRequestTypeDef",
     "DescribeResourcePolicyRequestRequestTypeDef",
+    "DescribeResourcePolicyResponseTypeDef",
     "DescribeSentimentDetectionJobRequestRequestTypeDef",
     "DescribeTargetedSentimentDetectionJobRequestRequestTypeDef",
     "DescribeTopicsDetectionJobRequestRequestTypeDef",
     "DetectDominantLanguageRequestRequestTypeDef",
     "DetectKeyPhrasesRequestRequestTypeDef",
     "DetectPiiEntitiesRequestRequestTypeDef",
     "PiiEntityTypeDef",
     "DetectSentimentRequestRequestTypeDef",
     "DetectSyntaxRequestRequestTypeDef",
     "DetectTargetedSentimentRequestRequestTypeDef",
+    "DocumentClassificationConfigTypeDef",
     "DocumentClassificationJobFilterTypeDef",
     "OutputDataConfigTypeDef",
+    "DocumentClassifierDocumentsTypeDef",
     "DocumentClassifierFilterTypeDef",
     "DocumentClassifierSummaryTypeDef",
     "ExtractedCharactersListItemTypeDef",
     "DominantLanguageDetectionJobFilterTypeDef",
     "EndpointFilterTypeDef",
     "EntitiesDetectionJobFilterTypeDef",
+    "EntityTypesListItemTypeDef",
     "EntityRecognizerAnnotationsTypeDef",
     "EntityRecognizerDocumentsTypeDef",
     "EntityRecognizerEntityListTypeDef",
     "EntityRecognizerEvaluationMetricsTypeDef",
     "EntityRecognizerFilterTypeDef",
-    "EntityTypesListItemTypeDef",
     "EntityTypesEvaluationMetricsTypeDef",
+    "EntityRecognizerOutputDataConfigTypeDef",
     "EntityRecognizerSummaryTypeDef",
     "EventsDetectionJobFilterTypeDef",
+    "FlywheelFilterTypeDef",
+    "FlywheelIterationFilterTypeDef",
+    "FlywheelModelEvaluationMetricsTypeDef",
+    "FlywheelSummaryTypeDef",
     "PointTypeDef",
+    "ImportModelResponseTypeDef",
     "KeyPhrasesDetectionJobFilterTypeDef",
-    "PaginatorConfigTypeDef",
     "ListDocumentClassifierSummariesRequestRequestTypeDef",
     "ListEntityRecognizerSummariesRequestRequestTypeDef",
     "PiiEntitiesDetectionJobFilterTypeDef",
     "SentimentDetectionJobFilterTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "TargetedSentimentDetectionJobFilterTypeDef",
     "TopicsDetectionJobFilterTypeDef",
+    "PaginatorConfigTypeDef",
     "PartOfSpeechTagTypeDef",
     "PiiOutputDataConfigTypeDef",
     "RedactionConfigTypeDef",
     "PutResourcePolicyRequestRequestTypeDef",
-    "StopDominantLanguageDetectionJobRequestRequestTypeDef",
-    "StopEntitiesDetectionJobRequestRequestTypeDef",
-    "StopEventsDetectionJobRequestRequestTypeDef",
-    "StopKeyPhrasesDetectionJobRequestRequestTypeDef",
-    "StopPiiEntitiesDetectionJobRequestRequestTypeDef",
-    "StopSentimentDetectionJobRequestRequestTypeDef",
-    "StopTargetedSentimentDetectionJobRequestRequestTypeDef",
-    "StopTrainingDocumentClassifierRequestRequestTypeDef",
-    "StopTrainingEntityRecognizerRequestRequestTypeDef",
-    "UntagResourceRequestRequestTypeDef",
-    "UpdateEndpointRequestRequestTypeDef",
-    "DocumentClassifierInputDataConfigTypeDef",
-    "BatchDetectDominantLanguageItemResultTypeDef",
-    "CreateDocumentClassifierResponseTypeDef",
-    "CreateEndpointResponseTypeDef",
-    "CreateEntityRecognizerResponseTypeDef",
-    "DescribeResourcePolicyResponseTypeDef",
-    "DetectDominantLanguageResponseTypeDef",
-    "ImportModelResponseTypeDef",
     "PutResourcePolicyResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "StartDocumentClassificationJobResponseTypeDef",
     "StartDominantLanguageDetectionJobResponseTypeDef",
     "StartEntitiesDetectionJobResponseTypeDef",
     "StartEventsDetectionJobResponseTypeDef",
+    "StartFlywheelIterationRequestRequestTypeDef",
+    "StartFlywheelIterationResponseTypeDef",
     "StartKeyPhrasesDetectionJobResponseTypeDef",
     "StartPiiEntitiesDetectionJobResponseTypeDef",
     "StartSentimentDetectionJobResponseTypeDef",
     "StartTargetedSentimentDetectionJobResponseTypeDef",
     "StartTopicsDetectionJobResponseTypeDef",
+    "StopDominantLanguageDetectionJobRequestRequestTypeDef",
     "StopDominantLanguageDetectionJobResponseTypeDef",
+    "StopEntitiesDetectionJobRequestRequestTypeDef",
     "StopEntitiesDetectionJobResponseTypeDef",
+    "StopEventsDetectionJobRequestRequestTypeDef",
     "StopEventsDetectionJobResponseTypeDef",
+    "StopKeyPhrasesDetectionJobRequestRequestTypeDef",
     "StopKeyPhrasesDetectionJobResponseTypeDef",
+    "StopPiiEntitiesDetectionJobRequestRequestTypeDef",
     "StopPiiEntitiesDetectionJobResponseTypeDef",
+    "StopSentimentDetectionJobRequestRequestTypeDef",
     "StopSentimentDetectionJobResponseTypeDef",
+    "StopTargetedSentimentDetectionJobRequestRequestTypeDef",
     "StopTargetedSentimentDetectionJobResponseTypeDef",
+    "StopTrainingDocumentClassifierRequestRequestTypeDef",
+    "StopTrainingEntityRecognizerRequestRequestTypeDef",
+    "UntagResourceRequestRequestTypeDef",
+    "UpdateEndpointRequestRequestTypeDef",
+    "UpdateEndpointResponseTypeDef",
+    "BatchDetectDominantLanguageItemResultTypeDef",
+    "DetectDominantLanguageResponseTypeDef",
     "BatchDetectKeyPhrasesItemResultTypeDef",
     "DetectKeyPhrasesResponseTypeDef",
     "BatchDetectSentimentItemResultTypeDef",
     "DetectSentimentResponseTypeDef",
     "MentionSentimentTypeDef",
     "BlockReferenceTypeDef",
     "ClassifierMetadataTypeDef",
@@ -184,53 +214,63 @@
     "DetectEntitiesRequestRequestTypeDef",
     "InputDataConfigTypeDef",
     "ContainsPiiEntitiesResponseTypeDef",
     "CreateEndpointRequestRequestTypeDef",
     "ImportModelRequestRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
+    "DataSecurityConfigTypeDef",
+    "UpdateDataSecurityConfigTypeDef",
+    "DatasetEntityRecognizerInputDataConfigTypeDef",
+    "ListDatasetsRequestRequestTypeDef",
+    "DescribeDatasetResponseTypeDef",
+    "ListDatasetsResponseTypeDef",
     "DescribeEndpointResponseTypeDef",
     "ListEndpointsResponseTypeDef",
     "DetectPiiEntitiesResponseTypeDef",
+    "ListDocumentClassificationJobsRequestListDocumentClassificationJobsPaginateTypeDef",
     "ListDocumentClassificationJobsRequestRequestTypeDef",
+    "DocumentClassifierInputDataConfigTypeDef",
+    "ListDocumentClassifiersRequestListDocumentClassifiersPaginateTypeDef",
     "ListDocumentClassifiersRequestRequestTypeDef",
     "ListDocumentClassifierSummariesResponseTypeDef",
     "DocumentMetadataTypeDef",
+    "ListDominantLanguageDetectionJobsRequestListDominantLanguageDetectionJobsPaginateTypeDef",
     "ListDominantLanguageDetectionJobsRequestRequestTypeDef",
+    "ListEndpointsRequestListEndpointsPaginateTypeDef",
     "ListEndpointsRequestRequestTypeDef",
+    "ListEntitiesDetectionJobsRequestListEntitiesDetectionJobsPaginateTypeDef",
     "ListEntitiesDetectionJobsRequestRequestTypeDef",
-    "ListEntityRecognizersRequestRequestTypeDef",
+    "EntityRecognitionConfigTypeDef",
     "EntityRecognizerInputDataConfigTypeDef",
+    "ListEntityRecognizersRequestListEntityRecognizersPaginateTypeDef",
+    "ListEntityRecognizersRequestRequestTypeDef",
     "EntityRecognizerMetadataEntityTypesListItemTypeDef",
     "ListEntityRecognizerSummariesResponseTypeDef",
     "ListEventsDetectionJobsRequestRequestTypeDef",
+    "ListFlywheelsRequestRequestTypeDef",
+    "ListFlywheelIterationHistoryRequestRequestTypeDef",
+    "FlywheelIterationPropertiesTypeDef",
+    "ListFlywheelsResponseTypeDef",
     "GeometryTypeDef",
-    "ListKeyPhrasesDetectionJobsRequestRequestTypeDef",
-    "ListDocumentClassificationJobsRequestListDocumentClassificationJobsPaginateTypeDef",
-    "ListDocumentClassifiersRequestListDocumentClassifiersPaginateTypeDef",
-    "ListDominantLanguageDetectionJobsRequestListDominantLanguageDetectionJobsPaginateTypeDef",
-    "ListEndpointsRequestListEndpointsPaginateTypeDef",
-    "ListEntitiesDetectionJobsRequestListEntitiesDetectionJobsPaginateTypeDef",
-    "ListEntityRecognizersRequestListEntityRecognizersPaginateTypeDef",
     "ListKeyPhrasesDetectionJobsRequestListKeyPhrasesDetectionJobsPaginateTypeDef",
+    "ListKeyPhrasesDetectionJobsRequestRequestTypeDef",
     "ListPiiEntitiesDetectionJobsRequestListPiiEntitiesDetectionJobsPaginateTypeDef",
     "ListPiiEntitiesDetectionJobsRequestRequestTypeDef",
     "ListSentimentDetectionJobsRequestListSentimentDetectionJobsPaginateTypeDef",
     "ListSentimentDetectionJobsRequestRequestTypeDef",
     "ListTargetedSentimentDetectionJobsRequestRequestTypeDef",
     "ListTopicsDetectionJobsRequestListTopicsDetectionJobsPaginateTypeDef",
     "ListTopicsDetectionJobsRequestRequestTypeDef",
     "SyntaxTokenTypeDef",
-    "CreateDocumentClassifierRequestRequestTypeDef",
     "BatchDetectDominantLanguageResponseTypeDef",
     "BatchDetectKeyPhrasesResponseTypeDef",
     "BatchDetectSentimentResponseTypeDef",
     "TargetedSentimentMentionTypeDef",
     "EntityTypeDef",
-    "DocumentClassifierPropertiesTypeDef",
     "DocumentClassificationJobPropertiesTypeDef",
     "DominantLanguageDetectionJobPropertiesTypeDef",
     "EntitiesDetectionJobPropertiesTypeDef",
     "EventsDetectionJobPropertiesTypeDef",
     "KeyPhrasesDetectionJobPropertiesTypeDef",
     "PiiEntitiesDetectionJobPropertiesTypeDef",
     "SentimentDetectionJobPropertiesTypeDef",
@@ -241,24 +281,29 @@
     "StartKeyPhrasesDetectionJobRequestRequestTypeDef",
     "StartPiiEntitiesDetectionJobRequestRequestTypeDef",
     "StartSentimentDetectionJobRequestRequestTypeDef",
     "StartTargetedSentimentDetectionJobRequestRequestTypeDef",
     "StartTopicsDetectionJobRequestRequestTypeDef",
     "TargetedSentimentDetectionJobPropertiesTypeDef",
     "TopicsDetectionJobPropertiesTypeDef",
+    "UpdateFlywheelRequestRequestTypeDef",
+    "DatasetInputDataConfigTypeDef",
+    "CreateDocumentClassifierRequestRequestTypeDef",
+    "DocumentClassifierPropertiesTypeDef",
     "ClassifyDocumentResponseTypeDef",
+    "TaskConfigTypeDef",
     "CreateEntityRecognizerRequestRequestTypeDef",
     "EntityRecognizerMetadataTypeDef",
+    "DescribeFlywheelIterationResponseTypeDef",
+    "ListFlywheelIterationHistoryResponseTypeDef",
     "BlockTypeDef",
     "BatchDetectSyntaxItemResultTypeDef",
     "DetectSyntaxResponseTypeDef",
     "TargetedSentimentEntityTypeDef",
     "BatchDetectEntitiesItemResultTypeDef",
-    "DescribeDocumentClassifierResponseTypeDef",
-    "ListDocumentClassifiersResponseTypeDef",
     "DescribeDocumentClassificationJobResponseTypeDef",
     "ListDocumentClassificationJobsResponseTypeDef",
     "DescribeDominantLanguageDetectionJobResponseTypeDef",
     "ListDominantLanguageDetectionJobsResponseTypeDef",
     "DescribeEntitiesDetectionJobResponseTypeDef",
     "ListEntitiesDetectionJobsResponseTypeDef",
     "DescribeEventsDetectionJobResponseTypeDef",
@@ -269,20 +314,27 @@
     "ListPiiEntitiesDetectionJobsResponseTypeDef",
     "DescribeSentimentDetectionJobResponseTypeDef",
     "ListSentimentDetectionJobsResponseTypeDef",
     "DescribeTargetedSentimentDetectionJobResponseTypeDef",
     "ListTargetedSentimentDetectionJobsResponseTypeDef",
     "DescribeTopicsDetectionJobResponseTypeDef",
     "ListTopicsDetectionJobsResponseTypeDef",
+    "CreateDatasetRequestRequestTypeDef",
+    "DescribeDocumentClassifierResponseTypeDef",
+    "ListDocumentClassifiersResponseTypeDef",
+    "CreateFlywheelRequestRequestTypeDef",
+    "FlywheelPropertiesTypeDef",
     "EntityRecognizerPropertiesTypeDef",
     "DetectEntitiesResponseTypeDef",
     "BatchDetectSyntaxResponseTypeDef",
     "BatchDetectTargetedSentimentItemResultTypeDef",
     "DetectTargetedSentimentResponseTypeDef",
     "BatchDetectEntitiesResponseTypeDef",
+    "DescribeFlywheelResponseTypeDef",
+    "UpdateFlywheelResponseTypeDef",
     "DescribeEntityRecognizerResponseTypeDef",
     "ListEntityRecognizersResponseTypeDef",
     "BatchDetectTargetedSentimentResponseTypeDef",
 )
 
 _RequiredAugmentedManifestsListItemTypeDef = TypedDict(
     "_RequiredAugmentedManifestsListItemTypeDef",
@@ -298,21 +350,19 @@
         "AnnotationDataS3Uri": str,
         "SourceDocumentsS3Uri": str,
         "DocumentType": AugmentedManifestsDocumentTypeFormatType,
     },
     total=False,
 )
 
-
 class AugmentedManifestsListItemTypeDef(
     _RequiredAugmentedManifestsListItemTypeDef, _OptionalAugmentedManifestsListItemTypeDef
 ):
     pass
 
-
 DominantLanguageTypeDef = TypedDict(
     "DominantLanguageTypeDef",
     {
         "LanguageCode": str,
         "Score": float,
     },
     total=False,
@@ -331,25 +381,14 @@
         "Index": int,
         "ErrorCode": str,
         "ErrorMessage": str,
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
 BatchDetectEntitiesRequestRequestTypeDef = TypedDict(
     "BatchDetectEntitiesRequestRequestTypeDef",
     {
         "TextList": Sequence[str],
         "LanguageCode": LanguageCodeType,
     },
 )
@@ -464,21 +503,19 @@
     {
         "DocumentReadMode": DocumentReadModeType,
         "FeatureTypes": Sequence[DocumentReadFeatureTypesType],
     },
     total=False,
 )
 
-
 class DocumentReaderConfigTypeDef(
     _RequiredDocumentReaderConfigTypeDef, _OptionalDocumentReaderConfigTypeDef
 ):
     pass
 
-
 DocumentClassTypeDef = TypedDict(
     "DocumentClassTypeDef",
     {
         "Name": str,
         "Score": float,
         "Page": int,
     },
@@ -510,14 +547,24 @@
         "Page": int,
         "ErrorCode": PageBasedErrorCodeType,
         "ErrorMessage": str,
     },
     total=False,
 )
 
+WarningsListItemTypeDef = TypedDict(
+    "WarningsListItemTypeDef",
+    {
+        "Page": int,
+        "WarnCode": PageBasedWarningCodeType,
+        "WarnMessage": str,
+    },
+    total=False,
+)
+
 ContainsPiiEntitiesRequestRequestTypeDef = TypedDict(
     "ContainsPiiEntitiesRequestRequestTypeDef",
     {
         "Text": str,
         "LanguageCode": LanguageCodeType,
     },
 )
@@ -527,50 +574,196 @@
     {
         "Name": PiiEntityTypeType,
         "Score": float,
     },
     total=False,
 )
 
-DocumentClassifierOutputDataConfigTypeDef = TypedDict(
-    "DocumentClassifierOutputDataConfigTypeDef",
-    {
-        "S3Uri": str,
-        "KmsKeyId": str,
-    },
-    total=False,
-)
-
 _RequiredTagTypeDef = TypedDict(
     "_RequiredTagTypeDef",
     {
         "Key": str,
     },
 )
 _OptionalTagTypeDef = TypedDict(
     "_OptionalTagTypeDef",
     {
         "Value": str,
     },
     total=False,
 )
 
-
 class TagTypeDef(_RequiredTagTypeDef, _OptionalTagTypeDef):
     pass
 
+CreateDatasetResponseTypeDef = TypedDict(
+    "CreateDatasetResponseTypeDef",
+    {
+        "DatasetArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DocumentClassifierOutputDataConfigTypeDef = TypedDict(
+    "DocumentClassifierOutputDataConfigTypeDef",
+    {
+        "S3Uri": str,
+        "KmsKeyId": str,
+        "FlywheelStatsS3Prefix": str,
+    },
+    total=False,
+)
 
 VpcConfigTypeDef = TypedDict(
     "VpcConfigTypeDef",
     {
         "SecurityGroupIds": Sequence[str],
         "Subnets": Sequence[str],
     },
 )
 
+CreateDocumentClassifierResponseTypeDef = TypedDict(
+    "CreateDocumentClassifierResponseTypeDef",
+    {
+        "DocumentClassifierArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateEndpointResponseTypeDef = TypedDict(
+    "CreateEndpointResponseTypeDef",
+    {
+        "EndpointArn": str,
+        "ModelArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateEntityRecognizerResponseTypeDef = TypedDict(
+    "CreateEntityRecognizerResponseTypeDef",
+    {
+        "EntityRecognizerArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateFlywheelResponseTypeDef = TypedDict(
+    "CreateFlywheelResponseTypeDef",
+    {
+        "FlywheelArn": str,
+        "ActiveModelArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredDatasetAugmentedManifestsListItemTypeDef = TypedDict(
+    "_RequiredDatasetAugmentedManifestsListItemTypeDef",
+    {
+        "AttributeNames": Sequence[str],
+        "S3Uri": str,
+    },
+)
+_OptionalDatasetAugmentedManifestsListItemTypeDef = TypedDict(
+    "_OptionalDatasetAugmentedManifestsListItemTypeDef",
+    {
+        "AnnotationDataS3Uri": str,
+        "SourceDocumentsS3Uri": str,
+        "DocumentType": AugmentedManifestsDocumentTypeFormatType,
+    },
+    total=False,
+)
+
+class DatasetAugmentedManifestsListItemTypeDef(
+    _RequiredDatasetAugmentedManifestsListItemTypeDef,
+    _OptionalDatasetAugmentedManifestsListItemTypeDef,
+):
+    pass
+
+_RequiredDatasetDocumentClassifierInputDataConfigTypeDef = TypedDict(
+    "_RequiredDatasetDocumentClassifierInputDataConfigTypeDef",
+    {
+        "S3Uri": str,
+    },
+)
+_OptionalDatasetDocumentClassifierInputDataConfigTypeDef = TypedDict(
+    "_OptionalDatasetDocumentClassifierInputDataConfigTypeDef",
+    {
+        "LabelDelimiter": str,
+    },
+    total=False,
+)
+
+class DatasetDocumentClassifierInputDataConfigTypeDef(
+    _RequiredDatasetDocumentClassifierInputDataConfigTypeDef,
+    _OptionalDatasetDocumentClassifierInputDataConfigTypeDef,
+):
+    pass
+
+DatasetEntityRecognizerAnnotationsTypeDef = TypedDict(
+    "DatasetEntityRecognizerAnnotationsTypeDef",
+    {
+        "S3Uri": str,
+    },
+)
+
+_RequiredDatasetEntityRecognizerDocumentsTypeDef = TypedDict(
+    "_RequiredDatasetEntityRecognizerDocumentsTypeDef",
+    {
+        "S3Uri": str,
+    },
+)
+_OptionalDatasetEntityRecognizerDocumentsTypeDef = TypedDict(
+    "_OptionalDatasetEntityRecognizerDocumentsTypeDef",
+    {
+        "InputFormat": InputFormatType,
+    },
+    total=False,
+)
+
+class DatasetEntityRecognizerDocumentsTypeDef(
+    _RequiredDatasetEntityRecognizerDocumentsTypeDef,
+    _OptionalDatasetEntityRecognizerDocumentsTypeDef,
+):
+    pass
+
+DatasetEntityRecognizerEntityListTypeDef = TypedDict(
+    "DatasetEntityRecognizerEntityListTypeDef",
+    {
+        "S3Uri": str,
+    },
+)
+
+DatasetFilterTypeDef = TypedDict(
+    "DatasetFilterTypeDef",
+    {
+        "Status": DatasetStatusType,
+        "DatasetType": DatasetTypeType,
+        "CreationTimeAfter": Union[datetime, str],
+        "CreationTimeBefore": Union[datetime, str],
+    },
+    total=False,
+)
+
+DatasetPropertiesTypeDef = TypedDict(
+    "DatasetPropertiesTypeDef",
+    {
+        "DatasetArn": str,
+        "DatasetName": str,
+        "DatasetType": DatasetTypeType,
+        "DatasetS3Uri": str,
+        "Description": str,
+        "Status": DatasetStatusType,
+        "Message": str,
+        "NumberOfDocuments": int,
+        "CreationTime": datetime,
+        "EndTime": datetime,
+    },
+    total=False,
+)
+
 DeleteDocumentClassifierRequestRequestTypeDef = TypedDict(
     "DeleteDocumentClassifierRequestRequestTypeDef",
     {
         "DocumentClassifierArn": str,
     },
 )
 
@@ -584,35 +777,47 @@
 DeleteEntityRecognizerRequestRequestTypeDef = TypedDict(
     "DeleteEntityRecognizerRequestRequestTypeDef",
     {
         "EntityRecognizerArn": str,
     },
 )
 
+DeleteFlywheelRequestRequestTypeDef = TypedDict(
+    "DeleteFlywheelRequestRequestTypeDef",
+    {
+        "FlywheelArn": str,
+    },
+)
+
 _RequiredDeleteResourcePolicyRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteResourcePolicyRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 _OptionalDeleteResourcePolicyRequestRequestTypeDef = TypedDict(
     "_OptionalDeleteResourcePolicyRequestRequestTypeDef",
     {
         "PolicyRevisionId": str,
     },
     total=False,
 )
 
-
 class DeleteResourcePolicyRequestRequestTypeDef(
     _RequiredDeleteResourcePolicyRequestRequestTypeDef,
     _OptionalDeleteResourcePolicyRequestRequestTypeDef,
 ):
     pass
 
+DescribeDatasetRequestRequestTypeDef = TypedDict(
+    "DescribeDatasetRequestRequestTypeDef",
+    {
+        "DatasetArn": str,
+    },
+)
 
 DescribeDocumentClassificationJobRequestRequestTypeDef = TypedDict(
     "DescribeDocumentClassificationJobRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
@@ -648,14 +853,15 @@
         "DesiredModelArn": str,
         "DesiredInferenceUnits": int,
         "CurrentInferenceUnits": int,
         "CreationTime": datetime,
         "LastModifiedTime": datetime,
         "DataAccessRoleArn": str,
         "DesiredDataAccessRoleArn": str,
+        "FlywheelArn": str,
     },
     total=False,
 )
 
 DescribeEntitiesDetectionJobRequestRequestTypeDef = TypedDict(
     "DescribeEntitiesDetectionJobRequestRequestTypeDef",
     {
@@ -673,14 +879,29 @@
 DescribeEventsDetectionJobRequestRequestTypeDef = TypedDict(
     "DescribeEventsDetectionJobRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 
+DescribeFlywheelIterationRequestRequestTypeDef = TypedDict(
+    "DescribeFlywheelIterationRequestRequestTypeDef",
+    {
+        "FlywheelArn": str,
+        "FlywheelIterationId": str,
+    },
+)
+
+DescribeFlywheelRequestRequestTypeDef = TypedDict(
+    "DescribeFlywheelRequestRequestTypeDef",
+    {
+        "FlywheelArn": str,
+    },
+)
+
 DescribeKeyPhrasesDetectionJobRequestRequestTypeDef = TypedDict(
     "DescribeKeyPhrasesDetectionJobRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 
@@ -694,14 +915,25 @@
 DescribeResourcePolicyRequestRequestTypeDef = TypedDict(
     "DescribeResourcePolicyRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+DescribeResourcePolicyResponseTypeDef = TypedDict(
+    "DescribeResourcePolicyResponseTypeDef",
+    {
+        "ResourcePolicy": str,
+        "CreationTime": datetime,
+        "LastModifiedTime": datetime,
+        "PolicyRevisionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeSentimentDetectionJobRequestRequestTypeDef = TypedDict(
     "DescribeSentimentDetectionJobRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 
@@ -773,14 +1005,33 @@
     "DetectTargetedSentimentRequestRequestTypeDef",
     {
         "Text": str,
         "LanguageCode": LanguageCodeType,
     },
 )
 
+_RequiredDocumentClassificationConfigTypeDef = TypedDict(
+    "_RequiredDocumentClassificationConfigTypeDef",
+    {
+        "Mode": DocumentClassifierModeType,
+    },
+)
+_OptionalDocumentClassificationConfigTypeDef = TypedDict(
+    "_OptionalDocumentClassificationConfigTypeDef",
+    {
+        "Labels": Sequence[str],
+    },
+    total=False,
+)
+
+class DocumentClassificationConfigTypeDef(
+    _RequiredDocumentClassificationConfigTypeDef, _OptionalDocumentClassificationConfigTypeDef
+):
+    pass
+
 DocumentClassificationJobFilterTypeDef = TypedDict(
     "DocumentClassificationJobFilterTypeDef",
     {
         "JobName": str,
         "JobStatus": JobStatusType,
         "SubmitTimeBefore": Union[datetime, str],
         "SubmitTimeAfter": Union[datetime, str],
@@ -798,18 +1049,35 @@
     "_OptionalOutputDataConfigTypeDef",
     {
         "KmsKeyId": str,
     },
     total=False,
 )
 
-
 class OutputDataConfigTypeDef(_RequiredOutputDataConfigTypeDef, _OptionalOutputDataConfigTypeDef):
     pass
 
+_RequiredDocumentClassifierDocumentsTypeDef = TypedDict(
+    "_RequiredDocumentClassifierDocumentsTypeDef",
+    {
+        "S3Uri": str,
+    },
+)
+_OptionalDocumentClassifierDocumentsTypeDef = TypedDict(
+    "_OptionalDocumentClassifierDocumentsTypeDef",
+    {
+        "TestS3Uri": str,
+    },
+    total=False,
+)
+
+class DocumentClassifierDocumentsTypeDef(
+    _RequiredDocumentClassifierDocumentsTypeDef, _OptionalDocumentClassifierDocumentsTypeDef
+):
+    pass
 
 DocumentClassifierFilterTypeDef = TypedDict(
     "DocumentClassifierFilterTypeDef",
     {
         "Status": ModelStatusType,
         "DocumentClassifierName": str,
         "SubmitTimeBefore": Union[datetime, str],
@@ -868,35 +1136,40 @@
         "JobStatus": JobStatusType,
         "SubmitTimeBefore": Union[datetime, str],
         "SubmitTimeAfter": Union[datetime, str],
     },
     total=False,
 )
 
+EntityTypesListItemTypeDef = TypedDict(
+    "EntityTypesListItemTypeDef",
+    {
+        "Type": str,
+    },
+)
+
 _RequiredEntityRecognizerAnnotationsTypeDef = TypedDict(
     "_RequiredEntityRecognizerAnnotationsTypeDef",
     {
         "S3Uri": str,
     },
 )
 _OptionalEntityRecognizerAnnotationsTypeDef = TypedDict(
     "_OptionalEntityRecognizerAnnotationsTypeDef",
     {
         "TestS3Uri": str,
     },
     total=False,
 )
 
-
 class EntityRecognizerAnnotationsTypeDef(
     _RequiredEntityRecognizerAnnotationsTypeDef, _OptionalEntityRecognizerAnnotationsTypeDef
 ):
     pass
 
-
 _RequiredEntityRecognizerDocumentsTypeDef = TypedDict(
     "_RequiredEntityRecognizerDocumentsTypeDef",
     {
         "S3Uri": str,
     },
 )
 _OptionalEntityRecognizerDocumentsTypeDef = TypedDict(
@@ -904,21 +1177,19 @@
     {
         "TestS3Uri": str,
         "InputFormat": InputFormatType,
     },
     total=False,
 )
 
-
 class EntityRecognizerDocumentsTypeDef(
     _RequiredEntityRecognizerDocumentsTypeDef, _OptionalEntityRecognizerDocumentsTypeDef
 ):
     pass
 
-
 EntityRecognizerEntityListTypeDef = TypedDict(
     "EntityRecognizerEntityListTypeDef",
     {
         "S3Uri": str,
     },
 )
 
@@ -939,31 +1210,32 @@
         "RecognizerName": str,
         "SubmitTimeBefore": Union[datetime, str],
         "SubmitTimeAfter": Union[datetime, str],
     },
     total=False,
 )
 
-EntityTypesListItemTypeDef = TypedDict(
-    "EntityTypesListItemTypeDef",
-    {
-        "Type": str,
-    },
-)
-
 EntityTypesEvaluationMetricsTypeDef = TypedDict(
     "EntityTypesEvaluationMetricsTypeDef",
     {
         "Precision": float,
         "Recall": float,
         "F1Score": float,
     },
     total=False,
 )
 
+EntityRecognizerOutputDataConfigTypeDef = TypedDict(
+    "EntityRecognizerOutputDataConfigTypeDef",
+    {
+        "FlywheelStatsS3Prefix": str,
+    },
+    total=False,
+)
+
 EntityRecognizerSummaryTypeDef = TypedDict(
     "EntityRecognizerSummaryTypeDef",
     {
         "RecognizerName": str,
         "NumberOfVersions": int,
         "LatestVersionCreatedAt": datetime,
         "LatestVersionName": str,
@@ -979,44 +1251,88 @@
         "JobStatus": JobStatusType,
         "SubmitTimeBefore": Union[datetime, str],
         "SubmitTimeAfter": Union[datetime, str],
     },
     total=False,
 )
 
+FlywheelFilterTypeDef = TypedDict(
+    "FlywheelFilterTypeDef",
+    {
+        "Status": FlywheelStatusType,
+        "CreationTimeAfter": Union[datetime, str],
+        "CreationTimeBefore": Union[datetime, str],
+    },
+    total=False,
+)
+
+FlywheelIterationFilterTypeDef = TypedDict(
+    "FlywheelIterationFilterTypeDef",
+    {
+        "CreationTimeAfter": Union[datetime, str],
+        "CreationTimeBefore": Union[datetime, str],
+    },
+    total=False,
+)
+
+FlywheelModelEvaluationMetricsTypeDef = TypedDict(
+    "FlywheelModelEvaluationMetricsTypeDef",
+    {
+        "AverageF1Score": float,
+        "AveragePrecision": float,
+        "AverageRecall": float,
+        "AverageAccuracy": float,
+    },
+    total=False,
+)
+
+FlywheelSummaryTypeDef = TypedDict(
+    "FlywheelSummaryTypeDef",
+    {
+        "FlywheelArn": str,
+        "ActiveModelArn": str,
+        "DataLakeS3Uri": str,
+        "Status": FlywheelStatusType,
+        "ModelType": ModelTypeType,
+        "Message": str,
+        "CreationTime": datetime,
+        "LastModifiedTime": datetime,
+        "LatestFlywheelIteration": str,
+    },
+    total=False,
+)
+
 PointTypeDef = TypedDict(
     "PointTypeDef",
     {
         "X": float,
         "Y": float,
     },
     total=False,
 )
 
+ImportModelResponseTypeDef = TypedDict(
+    "ImportModelResponseTypeDef",
+    {
+        "ModelArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 KeyPhrasesDetectionJobFilterTypeDef = TypedDict(
     "KeyPhrasesDetectionJobFilterTypeDef",
     {
         "JobName": str,
         "JobStatus": JobStatusType,
         "SubmitTimeBefore": Union[datetime, str],
         "SubmitTimeAfter": Union[datetime, str],
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
 ListDocumentClassifierSummariesRequestRequestTypeDef = TypedDict(
     "ListDocumentClassifierSummariesRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
@@ -1078,14 +1394,24 @@
         "JobStatus": JobStatusType,
         "SubmitTimeBefore": Union[datetime, str],
         "SubmitTimeAfter": Union[datetime, str],
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
 PartOfSpeechTagTypeDef = TypedDict(
     "PartOfSpeechTagTypeDef",
     {
         "Tag": PartOfSpeechTagTypeType,
         "Score": float,
     },
     total=False,
@@ -1101,21 +1427,19 @@
     "_OptionalPiiOutputDataConfigTypeDef",
     {
         "KmsKeyId": str,
     },
     total=False,
 )
 
-
 class PiiOutputDataConfigTypeDef(
     _RequiredPiiOutputDataConfigTypeDef, _OptionalPiiOutputDataConfigTypeDef
 ):
     pass
 
-
 RedactionConfigTypeDef = TypedDict(
     "RedactionConfigTypeDef",
     {
         "PiiEntityTypes": List[PiiEntityTypeType],
         "MaskMode": PiiEntitiesDetectionMaskModeType,
         "MaskCharacter": str,
     },
@@ -1133,345 +1457,337 @@
     "_OptionalPutResourcePolicyRequestRequestTypeDef",
     {
         "PolicyRevisionId": str,
     },
     total=False,
 )
 
-
 class PutResourcePolicyRequestRequestTypeDef(
     _RequiredPutResourcePolicyRequestRequestTypeDef, _OptionalPutResourcePolicyRequestRequestTypeDef
 ):
     pass
 
-
-StopDominantLanguageDetectionJobRequestRequestTypeDef = TypedDict(
-    "StopDominantLanguageDetectionJobRequestRequestTypeDef",
+PutResourcePolicyResponseTypeDef = TypedDict(
+    "PutResourcePolicyResponseTypeDef",
     {
-        "JobId": str,
+        "PolicyRevisionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StopEntitiesDetectionJobRequestRequestTypeDef = TypedDict(
-    "StopEntitiesDetectionJobRequestRequestTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "JobId": str,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
-StopEventsDetectionJobRequestRequestTypeDef = TypedDict(
-    "StopEventsDetectionJobRequestRequestTypeDef",
+StartDocumentClassificationJobResponseTypeDef = TypedDict(
+    "StartDocumentClassificationJobResponseTypeDef",
     {
         "JobId": str,
+        "JobArn": str,
+        "JobStatus": JobStatusType,
+        "DocumentClassifierArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StopKeyPhrasesDetectionJobRequestRequestTypeDef = TypedDict(
-    "StopKeyPhrasesDetectionJobRequestRequestTypeDef",
+StartDominantLanguageDetectionJobResponseTypeDef = TypedDict(
+    "StartDominantLanguageDetectionJobResponseTypeDef",
     {
         "JobId": str,
+        "JobArn": str,
+        "JobStatus": JobStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StopPiiEntitiesDetectionJobRequestRequestTypeDef = TypedDict(
-    "StopPiiEntitiesDetectionJobRequestRequestTypeDef",
+StartEntitiesDetectionJobResponseTypeDef = TypedDict(
+    "StartEntitiesDetectionJobResponseTypeDef",
     {
         "JobId": str,
+        "JobArn": str,
+        "JobStatus": JobStatusType,
+        "EntityRecognizerArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StopSentimentDetectionJobRequestRequestTypeDef = TypedDict(
-    "StopSentimentDetectionJobRequestRequestTypeDef",
+StartEventsDetectionJobResponseTypeDef = TypedDict(
+    "StartEventsDetectionJobResponseTypeDef",
     {
         "JobId": str,
+        "JobArn": str,
+        "JobStatus": JobStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StopTargetedSentimentDetectionJobRequestRequestTypeDef = TypedDict(
-    "StopTargetedSentimentDetectionJobRequestRequestTypeDef",
+_RequiredStartFlywheelIterationRequestRequestTypeDef = TypedDict(
+    "_RequiredStartFlywheelIterationRequestRequestTypeDef",
     {
-        "JobId": str,
+        "FlywheelArn": str,
     },
 )
-
-StopTrainingDocumentClassifierRequestRequestTypeDef = TypedDict(
-    "StopTrainingDocumentClassifierRequestRequestTypeDef",
+_OptionalStartFlywheelIterationRequestRequestTypeDef = TypedDict(
+    "_OptionalStartFlywheelIterationRequestRequestTypeDef",
     {
-        "DocumentClassifierArn": str,
+        "ClientRequestToken": str,
     },
+    total=False,
 )
 
-StopTrainingEntityRecognizerRequestRequestTypeDef = TypedDict(
-    "StopTrainingEntityRecognizerRequestRequestTypeDef",
-    {
-        "EntityRecognizerArn": str,
-    },
-)
+class StartFlywheelIterationRequestRequestTypeDef(
+    _RequiredStartFlywheelIterationRequestRequestTypeDef,
+    _OptionalStartFlywheelIterationRequestRequestTypeDef,
+):
+    pass
 
-UntagResourceRequestRequestTypeDef = TypedDict(
-    "UntagResourceRequestRequestTypeDef",
+StartFlywheelIterationResponseTypeDef = TypedDict(
+    "StartFlywheelIterationResponseTypeDef",
     {
-        "ResourceArn": str,
-        "TagKeys": Sequence[str],
+        "FlywheelArn": str,
+        "FlywheelIterationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-_RequiredUpdateEndpointRequestRequestTypeDef = TypedDict(
-    "_RequiredUpdateEndpointRequestRequestTypeDef",
-    {
-        "EndpointArn": str,
-    },
-)
-_OptionalUpdateEndpointRequestRequestTypeDef = TypedDict(
-    "_OptionalUpdateEndpointRequestRequestTypeDef",
+StartKeyPhrasesDetectionJobResponseTypeDef = TypedDict(
+    "StartKeyPhrasesDetectionJobResponseTypeDef",
     {
-        "DesiredModelArn": str,
-        "DesiredInferenceUnits": int,
-        "DesiredDataAccessRoleArn": str,
+        "JobId": str,
+        "JobArn": str,
+        "JobStatus": JobStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-
-class UpdateEndpointRequestRequestTypeDef(
-    _RequiredUpdateEndpointRequestRequestTypeDef, _OptionalUpdateEndpointRequestRequestTypeDef
-):
-    pass
-
-
-DocumentClassifierInputDataConfigTypeDef = TypedDict(
-    "DocumentClassifierInputDataConfigTypeDef",
+StartPiiEntitiesDetectionJobResponseTypeDef = TypedDict(
+    "StartPiiEntitiesDetectionJobResponseTypeDef",
     {
-        "DataFormat": DocumentClassifierDataFormatType,
-        "S3Uri": str,
-        "TestS3Uri": str,
-        "LabelDelimiter": str,
-        "AugmentedManifests": Sequence[AugmentedManifestsListItemTypeDef],
+        "JobId": str,
+        "JobArn": str,
+        "JobStatus": JobStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-BatchDetectDominantLanguageItemResultTypeDef = TypedDict(
-    "BatchDetectDominantLanguageItemResultTypeDef",
+StartSentimentDetectionJobResponseTypeDef = TypedDict(
+    "StartSentimentDetectionJobResponseTypeDef",
     {
-        "Index": int,
-        "Languages": List[DominantLanguageTypeDef],
+        "JobId": str,
+        "JobArn": str,
+        "JobStatus": JobStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-CreateDocumentClassifierResponseTypeDef = TypedDict(
-    "CreateDocumentClassifierResponseTypeDef",
+StartTargetedSentimentDetectionJobResponseTypeDef = TypedDict(
+    "StartTargetedSentimentDetectionJobResponseTypeDef",
     {
-        "DocumentClassifierArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "JobId": str,
+        "JobArn": str,
+        "JobStatus": JobStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateEndpointResponseTypeDef = TypedDict(
-    "CreateEndpointResponseTypeDef",
+StartTopicsDetectionJobResponseTypeDef = TypedDict(
+    "StartTopicsDetectionJobResponseTypeDef",
     {
-        "EndpointArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "JobId": str,
+        "JobArn": str,
+        "JobStatus": JobStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateEntityRecognizerResponseTypeDef = TypedDict(
-    "CreateEntityRecognizerResponseTypeDef",
+StopDominantLanguageDetectionJobRequestRequestTypeDef = TypedDict(
+    "StopDominantLanguageDetectionJobRequestRequestTypeDef",
     {
-        "EntityRecognizerArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "JobId": str,
     },
 )
 
-DescribeResourcePolicyResponseTypeDef = TypedDict(
-    "DescribeResourcePolicyResponseTypeDef",
+StopDominantLanguageDetectionJobResponseTypeDef = TypedDict(
+    "StopDominantLanguageDetectionJobResponseTypeDef",
     {
-        "ResourcePolicy": str,
-        "CreationTime": datetime,
-        "LastModifiedTime": datetime,
-        "PolicyRevisionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "JobId": str,
+        "JobStatus": JobStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DetectDominantLanguageResponseTypeDef = TypedDict(
-    "DetectDominantLanguageResponseTypeDef",
+StopEntitiesDetectionJobRequestRequestTypeDef = TypedDict(
+    "StopEntitiesDetectionJobRequestRequestTypeDef",
     {
-        "Languages": List[DominantLanguageTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "JobId": str,
     },
 )
 
-ImportModelResponseTypeDef = TypedDict(
-    "ImportModelResponseTypeDef",
+StopEntitiesDetectionJobResponseTypeDef = TypedDict(
+    "StopEntitiesDetectionJobResponseTypeDef",
     {
-        "ModelArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "JobId": str,
+        "JobStatus": JobStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-PutResourcePolicyResponseTypeDef = TypedDict(
-    "PutResourcePolicyResponseTypeDef",
+StopEventsDetectionJobRequestRequestTypeDef = TypedDict(
+    "StopEventsDetectionJobRequestRequestTypeDef",
     {
-        "PolicyRevisionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "JobId": str,
     },
 )
 
-StartDocumentClassificationJobResponseTypeDef = TypedDict(
-    "StartDocumentClassificationJobResponseTypeDef",
+StopEventsDetectionJobResponseTypeDef = TypedDict(
+    "StopEventsDetectionJobResponseTypeDef",
     {
         "JobId": str,
-        "JobArn": str,
         "JobStatus": JobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StartDominantLanguageDetectionJobResponseTypeDef = TypedDict(
-    "StartDominantLanguageDetectionJobResponseTypeDef",
+StopKeyPhrasesDetectionJobRequestRequestTypeDef = TypedDict(
+    "StopKeyPhrasesDetectionJobRequestRequestTypeDef",
     {
         "JobId": str,
-        "JobArn": str,
-        "JobStatus": JobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
 
-StartEntitiesDetectionJobResponseTypeDef = TypedDict(
-    "StartEntitiesDetectionJobResponseTypeDef",
+StopKeyPhrasesDetectionJobResponseTypeDef = TypedDict(
+    "StopKeyPhrasesDetectionJobResponseTypeDef",
     {
         "JobId": str,
-        "JobArn": str,
         "JobStatus": JobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StartEventsDetectionJobResponseTypeDef = TypedDict(
-    "StartEventsDetectionJobResponseTypeDef",
+StopPiiEntitiesDetectionJobRequestRequestTypeDef = TypedDict(
+    "StopPiiEntitiesDetectionJobRequestRequestTypeDef",
     {
         "JobId": str,
-        "JobArn": str,
-        "JobStatus": JobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
 
-StartKeyPhrasesDetectionJobResponseTypeDef = TypedDict(
-    "StartKeyPhrasesDetectionJobResponseTypeDef",
+StopPiiEntitiesDetectionJobResponseTypeDef = TypedDict(
+    "StopPiiEntitiesDetectionJobResponseTypeDef",
     {
         "JobId": str,
-        "JobArn": str,
         "JobStatus": JobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StartPiiEntitiesDetectionJobResponseTypeDef = TypedDict(
-    "StartPiiEntitiesDetectionJobResponseTypeDef",
+StopSentimentDetectionJobRequestRequestTypeDef = TypedDict(
+    "StopSentimentDetectionJobRequestRequestTypeDef",
     {
         "JobId": str,
-        "JobArn": str,
-        "JobStatus": JobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
 
-StartSentimentDetectionJobResponseTypeDef = TypedDict(
-    "StartSentimentDetectionJobResponseTypeDef",
+StopSentimentDetectionJobResponseTypeDef = TypedDict(
+    "StopSentimentDetectionJobResponseTypeDef",
     {
         "JobId": str,
-        "JobArn": str,
         "JobStatus": JobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StartTargetedSentimentDetectionJobResponseTypeDef = TypedDict(
-    "StartTargetedSentimentDetectionJobResponseTypeDef",
+StopTargetedSentimentDetectionJobRequestRequestTypeDef = TypedDict(
+    "StopTargetedSentimentDetectionJobRequestRequestTypeDef",
     {
         "JobId": str,
-        "JobArn": str,
-        "JobStatus": JobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
 
-StartTopicsDetectionJobResponseTypeDef = TypedDict(
-    "StartTopicsDetectionJobResponseTypeDef",
+StopTargetedSentimentDetectionJobResponseTypeDef = TypedDict(
+    "StopTargetedSentimentDetectionJobResponseTypeDef",
     {
         "JobId": str,
-        "JobArn": str,
         "JobStatus": JobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StopDominantLanguageDetectionJobResponseTypeDef = TypedDict(
-    "StopDominantLanguageDetectionJobResponseTypeDef",
+StopTrainingDocumentClassifierRequestRequestTypeDef = TypedDict(
+    "StopTrainingDocumentClassifierRequestRequestTypeDef",
     {
-        "JobId": str,
-        "JobStatus": JobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "DocumentClassifierArn": str,
     },
 )
 
-StopEntitiesDetectionJobResponseTypeDef = TypedDict(
-    "StopEntitiesDetectionJobResponseTypeDef",
+StopTrainingEntityRecognizerRequestRequestTypeDef = TypedDict(
+    "StopTrainingEntityRecognizerRequestRequestTypeDef",
     {
-        "JobId": str,
-        "JobStatus": JobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "EntityRecognizerArn": str,
     },
 )
 
-StopEventsDetectionJobResponseTypeDef = TypedDict(
-    "StopEventsDetectionJobResponseTypeDef",
+UntagResourceRequestRequestTypeDef = TypedDict(
+    "UntagResourceRequestRequestTypeDef",
     {
-        "JobId": str,
-        "JobStatus": JobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResourceArn": str,
+        "TagKeys": Sequence[str],
     },
 )
 
-StopKeyPhrasesDetectionJobResponseTypeDef = TypedDict(
-    "StopKeyPhrasesDetectionJobResponseTypeDef",
+_RequiredUpdateEndpointRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateEndpointRequestRequestTypeDef",
     {
-        "JobId": str,
-        "JobStatus": JobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "EndpointArn": str,
+    },
+)
+_OptionalUpdateEndpointRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateEndpointRequestRequestTypeDef",
+    {
+        "DesiredModelArn": str,
+        "DesiredInferenceUnits": int,
+        "DesiredDataAccessRoleArn": str,
+        "FlywheelArn": str,
     },
+    total=False,
 )
 
-StopPiiEntitiesDetectionJobResponseTypeDef = TypedDict(
-    "StopPiiEntitiesDetectionJobResponseTypeDef",
+class UpdateEndpointRequestRequestTypeDef(
+    _RequiredUpdateEndpointRequestRequestTypeDef, _OptionalUpdateEndpointRequestRequestTypeDef
+):
+    pass
+
+UpdateEndpointResponseTypeDef = TypedDict(
+    "UpdateEndpointResponseTypeDef",
     {
-        "JobId": str,
-        "JobStatus": JobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "DesiredModelArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StopSentimentDetectionJobResponseTypeDef = TypedDict(
-    "StopSentimentDetectionJobResponseTypeDef",
+BatchDetectDominantLanguageItemResultTypeDef = TypedDict(
+    "BatchDetectDominantLanguageItemResultTypeDef",
     {
-        "JobId": str,
-        "JobStatus": JobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Index": int,
+        "Languages": List[DominantLanguageTypeDef],
     },
+    total=False,
 )
 
-StopTargetedSentimentDetectionJobResponseTypeDef = TypedDict(
-    "StopTargetedSentimentDetectionJobResponseTypeDef",
+DetectDominantLanguageResponseTypeDef = TypedDict(
+    "DetectDominantLanguageResponseTypeDef",
     {
-        "JobId": str,
-        "JobStatus": JobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Languages": List[DominantLanguageTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDetectKeyPhrasesItemResultTypeDef = TypedDict(
     "BatchDetectKeyPhrasesItemResultTypeDef",
     {
         "Index": int,
@@ -1480,15 +1796,15 @@
     total=False,
 )
 
 DetectKeyPhrasesResponseTypeDef = TypedDict(
     "DetectKeyPhrasesResponseTypeDef",
     {
         "KeyPhrases": List[KeyPhraseTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDetectSentimentItemResultTypeDef = TypedDict(
     "BatchDetectSentimentItemResultTypeDef",
     {
         "Index": int,
@@ -1499,15 +1815,15 @@
 )
 
 DetectSentimentResponseTypeDef = TypedDict(
     "DetectSentimentResponseTypeDef",
     {
         "Sentiment": SentimentTypeType,
         "SentimentScore": SentimentScoreTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 MentionSentimentTypeDef = TypedDict(
     "MentionSentimentTypeDef",
     {
         "Sentiment": SentimentTypeType,
@@ -1550,21 +1866,19 @@
         "Text": str,
         "Bytes": Union[str, bytes, IO[Any], StreamingBody],
         "DocumentReaderConfig": DocumentReaderConfigTypeDef,
     },
     total=False,
 )
 
-
 class ClassifyDocumentRequestRequestTypeDef(
     _RequiredClassifyDocumentRequestRequestTypeDef, _OptionalClassifyDocumentRequestRequestTypeDef
 ):
     pass
 
-
 DetectEntitiesRequestRequestTypeDef = TypedDict(
     "DetectEntitiesRequestRequestTypeDef",
     {
         "Text": str,
         "LanguageCode": LanguageCodeType,
         "EndpointArn": str,
         "Bytes": Union[str, bytes, IO[Any], StreamingBody],
@@ -1584,52 +1898,49 @@
     {
         "InputFormat": InputFormatType,
         "DocumentReaderConfig": DocumentReaderConfigTypeDef,
     },
     total=False,
 )
 
-
 class InputDataConfigTypeDef(_RequiredInputDataConfigTypeDef, _OptionalInputDataConfigTypeDef):
     pass
 
-
 ContainsPiiEntitiesResponseTypeDef = TypedDict(
     "ContainsPiiEntitiesResponseTypeDef",
     {
         "Labels": List[EntityLabelTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateEndpointRequestRequestTypeDef = TypedDict(
     "_RequiredCreateEndpointRequestRequestTypeDef",
     {
         "EndpointName": str,
-        "ModelArn": str,
         "DesiredInferenceUnits": int,
     },
 )
 _OptionalCreateEndpointRequestRequestTypeDef = TypedDict(
     "_OptionalCreateEndpointRequestRequestTypeDef",
     {
+        "ModelArn": str,
         "ClientRequestToken": str,
         "Tags": Sequence[TagTypeDef],
         "DataAccessRoleArn": str,
+        "FlywheelArn": str,
     },
     total=False,
 )
 
-
 class CreateEndpointRequestRequestTypeDef(
     _RequiredCreateEndpointRequestRequestTypeDef, _OptionalCreateEndpointRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredImportModelRequestRequestTypeDef = TypedDict(
     "_RequiredImportModelRequestRequestTypeDef",
     {
         "SourceModelArn": str,
     },
 )
 _OptionalImportModelRequestRequestTypeDef = TypedDict(
@@ -1640,73 +1951,174 @@
         "ModelKmsKeyId": str,
         "DataAccessRoleArn": str,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class ImportModelRequestRequestTypeDef(
     _RequiredImportModelRequestRequestTypeDef, _OptionalImportModelRequestRequestTypeDef
 ):
     pass
 
-
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "ResourceArn": str,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "Tags": Sequence[TagTypeDef],
     },
 )
 
+DataSecurityConfigTypeDef = TypedDict(
+    "DataSecurityConfigTypeDef",
+    {
+        "ModelKmsKeyId": str,
+        "VolumeKmsKeyId": str,
+        "DataLakeKmsKeyId": str,
+        "VpcConfig": VpcConfigTypeDef,
+    },
+    total=False,
+)
+
+UpdateDataSecurityConfigTypeDef = TypedDict(
+    "UpdateDataSecurityConfigTypeDef",
+    {
+        "ModelKmsKeyId": str,
+        "VolumeKmsKeyId": str,
+        "VpcConfig": VpcConfigTypeDef,
+    },
+    total=False,
+)
+
+_RequiredDatasetEntityRecognizerInputDataConfigTypeDef = TypedDict(
+    "_RequiredDatasetEntityRecognizerInputDataConfigTypeDef",
+    {
+        "Documents": DatasetEntityRecognizerDocumentsTypeDef,
+    },
+)
+_OptionalDatasetEntityRecognizerInputDataConfigTypeDef = TypedDict(
+    "_OptionalDatasetEntityRecognizerInputDataConfigTypeDef",
+    {
+        "Annotations": DatasetEntityRecognizerAnnotationsTypeDef,
+        "EntityList": DatasetEntityRecognizerEntityListTypeDef,
+    },
+    total=False,
+)
+
+class DatasetEntityRecognizerInputDataConfigTypeDef(
+    _RequiredDatasetEntityRecognizerInputDataConfigTypeDef,
+    _OptionalDatasetEntityRecognizerInputDataConfigTypeDef,
+):
+    pass
+
+ListDatasetsRequestRequestTypeDef = TypedDict(
+    "ListDatasetsRequestRequestTypeDef",
+    {
+        "FlywheelArn": str,
+        "Filter": DatasetFilterTypeDef,
+        "NextToken": str,
+        "MaxResults": int,
+    },
+    total=False,
+)
+
+DescribeDatasetResponseTypeDef = TypedDict(
+    "DescribeDatasetResponseTypeDef",
+    {
+        "DatasetProperties": DatasetPropertiesTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListDatasetsResponseTypeDef = TypedDict(
+    "ListDatasetsResponseTypeDef",
+    {
+        "DatasetPropertiesList": List[DatasetPropertiesTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeEndpointResponseTypeDef = TypedDict(
     "DescribeEndpointResponseTypeDef",
     {
         "EndpointProperties": EndpointPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEndpointsResponseTypeDef = TypedDict(
     "ListEndpointsResponseTypeDef",
     {
         "EndpointPropertiesList": List[EndpointPropertiesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DetectPiiEntitiesResponseTypeDef = TypedDict(
     "DetectPiiEntitiesResponseTypeDef",
     {
         "Entities": List[PiiEntityTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
+ListDocumentClassificationJobsRequestListDocumentClassificationJobsPaginateTypeDef = TypedDict(
+    "ListDocumentClassificationJobsRequestListDocumentClassificationJobsPaginateTypeDef",
+    {
+        "Filter": DocumentClassificationJobFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDocumentClassificationJobsRequestRequestTypeDef = TypedDict(
     "ListDocumentClassificationJobsRequestRequestTypeDef",
     {
         "Filter": DocumentClassificationJobFilterTypeDef,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+DocumentClassifierInputDataConfigTypeDef = TypedDict(
+    "DocumentClassifierInputDataConfigTypeDef",
+    {
+        "DataFormat": DocumentClassifierDataFormatType,
+        "S3Uri": str,
+        "TestS3Uri": str,
+        "LabelDelimiter": str,
+        "AugmentedManifests": Sequence[AugmentedManifestsListItemTypeDef],
+        "DocumentType": DocumentClassifierDocumentTypeFormatType,
+        "Documents": DocumentClassifierDocumentsTypeDef,
+        "DocumentReaderConfig": DocumentReaderConfigTypeDef,
+    },
+    total=False,
+)
+
+ListDocumentClassifiersRequestListDocumentClassifiersPaginateTypeDef = TypedDict(
+    "ListDocumentClassifiersRequestListDocumentClassifiersPaginateTypeDef",
+    {
+        "Filter": DocumentClassifierFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDocumentClassifiersRequestRequestTypeDef = TypedDict(
     "ListDocumentClassifiersRequestRequestTypeDef",
     {
         "Filter": DocumentClassifierFilterTypeDef,
         "NextToken": str,
         "MaxResults": int,
     },
@@ -1714,65 +2126,91 @@
 )
 
 ListDocumentClassifierSummariesResponseTypeDef = TypedDict(
     "ListDocumentClassifierSummariesResponseTypeDef",
     {
         "DocumentClassifierSummariesList": List[DocumentClassifierSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DocumentMetadataTypeDef = TypedDict(
     "DocumentMetadataTypeDef",
     {
         "Pages": int,
         "ExtractedCharacters": List[ExtractedCharactersListItemTypeDef],
     },
     total=False,
 )
 
+ListDominantLanguageDetectionJobsRequestListDominantLanguageDetectionJobsPaginateTypeDef = (
+    TypedDict(
+        "ListDominantLanguageDetectionJobsRequestListDominantLanguageDetectionJobsPaginateTypeDef",
+        {
+            "Filter": DominantLanguageDetectionJobFilterTypeDef,
+            "PaginationConfig": "PaginatorConfigTypeDef",
+        },
+        total=False,
+    )
+)
+
 ListDominantLanguageDetectionJobsRequestRequestTypeDef = TypedDict(
     "ListDominantLanguageDetectionJobsRequestRequestTypeDef",
     {
         "Filter": DominantLanguageDetectionJobFilterTypeDef,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListEndpointsRequestListEndpointsPaginateTypeDef = TypedDict(
+    "ListEndpointsRequestListEndpointsPaginateTypeDef",
+    {
+        "Filter": EndpointFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListEndpointsRequestRequestTypeDef = TypedDict(
     "ListEndpointsRequestRequestTypeDef",
     {
         "Filter": EndpointFilterTypeDef,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListEntitiesDetectionJobsRequestListEntitiesDetectionJobsPaginateTypeDef = TypedDict(
+    "ListEntitiesDetectionJobsRequestListEntitiesDetectionJobsPaginateTypeDef",
+    {
+        "Filter": EntitiesDetectionJobFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListEntitiesDetectionJobsRequestRequestTypeDef = TypedDict(
     "ListEntitiesDetectionJobsRequestRequestTypeDef",
     {
         "Filter": EntitiesDetectionJobFilterTypeDef,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-ListEntityRecognizersRequestRequestTypeDef = TypedDict(
-    "ListEntityRecognizersRequestRequestTypeDef",
+EntityRecognitionConfigTypeDef = TypedDict(
+    "EntityRecognitionConfigTypeDef",
     {
-        "Filter": EntityRecognizerFilterTypeDef,
-        "NextToken": str,
-        "MaxResults": int,
+        "EntityTypes": Sequence[EntityTypesListItemTypeDef],
     },
-    total=False,
 )
 
 _RequiredEntityRecognizerInputDataConfigTypeDef = TypedDict(
     "_RequiredEntityRecognizerInputDataConfigTypeDef",
     {
         "EntityTypes": Sequence[EntityTypesListItemTypeDef],
     },
@@ -1785,20 +2223,37 @@
         "Annotations": EntityRecognizerAnnotationsTypeDef,
         "EntityList": EntityRecognizerEntityListTypeDef,
         "AugmentedManifests": Sequence[AugmentedManifestsListItemTypeDef],
     },
     total=False,
 )
 
-
 class EntityRecognizerInputDataConfigTypeDef(
     _RequiredEntityRecognizerInputDataConfigTypeDef, _OptionalEntityRecognizerInputDataConfigTypeDef
 ):
     pass
 
+ListEntityRecognizersRequestListEntityRecognizersPaginateTypeDef = TypedDict(
+    "ListEntityRecognizersRequestListEntityRecognizersPaginateTypeDef",
+    {
+        "Filter": EntityRecognizerFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+ListEntityRecognizersRequestRequestTypeDef = TypedDict(
+    "ListEntityRecognizersRequestRequestTypeDef",
+    {
+        "Filter": EntityRecognizerFilterTypeDef,
+        "NextToken": str,
+        "MaxResults": int,
+    },
+    total=False,
+)
 
 EntityRecognizerMetadataEntityTypesListItemTypeDef = TypedDict(
     "EntityRecognizerMetadataEntityTypesListItemTypeDef",
     {
         "Type": str,
         "EvaluationMetrics": EntityTypesEvaluationMetricsTypeDef,
         "NumberOfTrainMentions": int,
@@ -1807,117 +2262,120 @@
 )
 
 ListEntityRecognizerSummariesResponseTypeDef = TypedDict(
     "ListEntityRecognizerSummariesResponseTypeDef",
     {
         "EntityRecognizerSummariesList": List[EntityRecognizerSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEventsDetectionJobsRequestRequestTypeDef = TypedDict(
     "ListEventsDetectionJobsRequestRequestTypeDef",
     {
         "Filter": EventsDetectionJobFilterTypeDef,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-GeometryTypeDef = TypedDict(
-    "GeometryTypeDef",
-    {
-        "BoundingBox": BoundingBoxTypeDef,
-        "Polygon": List[PointTypeDef],
-    },
-    total=False,
-)
-
-ListKeyPhrasesDetectionJobsRequestRequestTypeDef = TypedDict(
-    "ListKeyPhrasesDetectionJobsRequestRequestTypeDef",
+ListFlywheelsRequestRequestTypeDef = TypedDict(
+    "ListFlywheelsRequestRequestTypeDef",
     {
-        "Filter": KeyPhrasesDetectionJobFilterTypeDef,
+        "Filter": FlywheelFilterTypeDef,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-ListDocumentClassificationJobsRequestListDocumentClassificationJobsPaginateTypeDef = TypedDict(
-    "ListDocumentClassificationJobsRequestListDocumentClassificationJobsPaginateTypeDef",
+_RequiredListFlywheelIterationHistoryRequestRequestTypeDef = TypedDict(
+    "_RequiredListFlywheelIterationHistoryRequestRequestTypeDef",
     {
-        "Filter": DocumentClassificationJobFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "FlywheelArn": str,
     },
-    total=False,
 )
-
-ListDocumentClassifiersRequestListDocumentClassifiersPaginateTypeDef = TypedDict(
-    "ListDocumentClassifiersRequestListDocumentClassifiersPaginateTypeDef",
+_OptionalListFlywheelIterationHistoryRequestRequestTypeDef = TypedDict(
+    "_OptionalListFlywheelIterationHistoryRequestRequestTypeDef",
     {
-        "Filter": DocumentClassifierFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "Filter": FlywheelIterationFilterTypeDef,
+        "NextToken": str,
+        "MaxResults": int,
     },
     total=False,
 )
 
-ListDominantLanguageDetectionJobsRequestListDominantLanguageDetectionJobsPaginateTypeDef = (
-    TypedDict(
-        "ListDominantLanguageDetectionJobsRequestListDominantLanguageDetectionJobsPaginateTypeDef",
-        {
-            "Filter": DominantLanguageDetectionJobFilterTypeDef,
-            "PaginationConfig": PaginatorConfigTypeDef,
-        },
-        total=False,
-    )
-)
+class ListFlywheelIterationHistoryRequestRequestTypeDef(
+    _RequiredListFlywheelIterationHistoryRequestRequestTypeDef,
+    _OptionalListFlywheelIterationHistoryRequestRequestTypeDef,
+):
+    pass
 
-ListEndpointsRequestListEndpointsPaginateTypeDef = TypedDict(
-    "ListEndpointsRequestListEndpointsPaginateTypeDef",
+FlywheelIterationPropertiesTypeDef = TypedDict(
+    "FlywheelIterationPropertiesTypeDef",
     {
-        "Filter": EndpointFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "FlywheelArn": str,
+        "FlywheelIterationId": str,
+        "CreationTime": datetime,
+        "EndTime": datetime,
+        "Status": FlywheelIterationStatusType,
+        "Message": str,
+        "EvaluatedModelArn": str,
+        "EvaluatedModelMetrics": FlywheelModelEvaluationMetricsTypeDef,
+        "TrainedModelArn": str,
+        "TrainedModelMetrics": FlywheelModelEvaluationMetricsTypeDef,
+        "EvaluationManifestS3Prefix": str,
     },
     total=False,
 )
 
-ListEntitiesDetectionJobsRequestListEntitiesDetectionJobsPaginateTypeDef = TypedDict(
-    "ListEntitiesDetectionJobsRequestListEntitiesDetectionJobsPaginateTypeDef",
+ListFlywheelsResponseTypeDef = TypedDict(
+    "ListFlywheelsResponseTypeDef",
     {
-        "Filter": EntitiesDetectionJobFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "FlywheelSummaryList": List[FlywheelSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-ListEntityRecognizersRequestListEntityRecognizersPaginateTypeDef = TypedDict(
-    "ListEntityRecognizersRequestListEntityRecognizersPaginateTypeDef",
+GeometryTypeDef = TypedDict(
+    "GeometryTypeDef",
     {
-        "Filter": EntityRecognizerFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "BoundingBox": BoundingBoxTypeDef,
+        "Polygon": List[PointTypeDef],
     },
     total=False,
 )
 
 ListKeyPhrasesDetectionJobsRequestListKeyPhrasesDetectionJobsPaginateTypeDef = TypedDict(
     "ListKeyPhrasesDetectionJobsRequestListKeyPhrasesDetectionJobsPaginateTypeDef",
     {
         "Filter": KeyPhrasesDetectionJobFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+ListKeyPhrasesDetectionJobsRequestRequestTypeDef = TypedDict(
+    "ListKeyPhrasesDetectionJobsRequestRequestTypeDef",
+    {
+        "Filter": KeyPhrasesDetectionJobFilterTypeDef,
+        "NextToken": str,
+        "MaxResults": int,
     },
     total=False,
 )
 
 ListPiiEntitiesDetectionJobsRequestListPiiEntitiesDetectionJobsPaginateTypeDef = TypedDict(
     "ListPiiEntitiesDetectionJobsRequestListPiiEntitiesDetectionJobsPaginateTypeDef",
     {
         "Filter": PiiEntitiesDetectionJobFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListPiiEntitiesDetectionJobsRequestRequestTypeDef = TypedDict(
     "ListPiiEntitiesDetectionJobsRequestRequestTypeDef",
     {
@@ -1928,15 +2386,15 @@
     total=False,
 )
 
 ListSentimentDetectionJobsRequestListSentimentDetectionJobsPaginateTypeDef = TypedDict(
     "ListSentimentDetectionJobsRequestListSentimentDetectionJobsPaginateTypeDef",
     {
         "Filter": SentimentDetectionJobFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListSentimentDetectionJobsRequestRequestTypeDef = TypedDict(
     "ListSentimentDetectionJobsRequestRequestTypeDef",
     {
@@ -1957,15 +2415,15 @@
     total=False,
 )
 
 ListTopicsDetectionJobsRequestListTopicsDetectionJobsPaginateTypeDef = TypedDict(
     "ListTopicsDetectionJobsRequestListTopicsDetectionJobsPaginateTypeDef",
     {
         "Filter": TopicsDetectionJobFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListTopicsDetectionJobsRequestRequestTypeDef = TypedDict(
     "ListTopicsDetectionJobsRequestRequestTypeDef",
     {
@@ -1984,71 +2442,38 @@
         "BeginOffset": int,
         "EndOffset": int,
         "PartOfSpeech": PartOfSpeechTagTypeDef,
     },
     total=False,
 )
 
-_RequiredCreateDocumentClassifierRequestRequestTypeDef = TypedDict(
-    "_RequiredCreateDocumentClassifierRequestRequestTypeDef",
-    {
-        "DocumentClassifierName": str,
-        "DataAccessRoleArn": str,
-        "InputDataConfig": DocumentClassifierInputDataConfigTypeDef,
-        "LanguageCode": LanguageCodeType,
-    },
-)
-_OptionalCreateDocumentClassifierRequestRequestTypeDef = TypedDict(
-    "_OptionalCreateDocumentClassifierRequestRequestTypeDef",
-    {
-        "VersionName": str,
-        "Tags": Sequence[TagTypeDef],
-        "OutputDataConfig": DocumentClassifierOutputDataConfigTypeDef,
-        "ClientRequestToken": str,
-        "VolumeKmsKeyId": str,
-        "VpcConfig": VpcConfigTypeDef,
-        "Mode": DocumentClassifierModeType,
-        "ModelKmsKeyId": str,
-        "ModelPolicy": str,
-    },
-    total=False,
-)
-
-
-class CreateDocumentClassifierRequestRequestTypeDef(
-    _RequiredCreateDocumentClassifierRequestRequestTypeDef,
-    _OptionalCreateDocumentClassifierRequestRequestTypeDef,
-):
-    pass
-
-
 BatchDetectDominantLanguageResponseTypeDef = TypedDict(
     "BatchDetectDominantLanguageResponseTypeDef",
     {
         "ResultList": List[BatchDetectDominantLanguageItemResultTypeDef],
         "ErrorList": List[BatchItemErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDetectKeyPhrasesResponseTypeDef = TypedDict(
     "BatchDetectKeyPhrasesResponseTypeDef",
     {
         "ResultList": List[BatchDetectKeyPhrasesItemResultTypeDef],
         "ErrorList": List[BatchItemErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDetectSentimentResponseTypeDef = TypedDict(
     "BatchDetectSentimentResponseTypeDef",
     {
         "ResultList": List[BatchDetectSentimentItemResultTypeDef],
         "ErrorList": List[BatchItemErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TargetedSentimentMentionTypeDef = TypedDict(
     "TargetedSentimentMentionTypeDef",
     {
         "Score": float,
@@ -2071,39 +2496,14 @@
         "BeginOffset": int,
         "EndOffset": int,
         "BlockReferences": List[BlockReferenceTypeDef],
     },
     total=False,
 )
 
-DocumentClassifierPropertiesTypeDef = TypedDict(
-    "DocumentClassifierPropertiesTypeDef",
-    {
-        "DocumentClassifierArn": str,
-        "LanguageCode": LanguageCodeType,
-        "Status": ModelStatusType,
-        "Message": str,
-        "SubmitTime": datetime,
-        "EndTime": datetime,
-        "TrainingStartTime": datetime,
-        "TrainingEndTime": datetime,
-        "InputDataConfig": DocumentClassifierInputDataConfigTypeDef,
-        "OutputDataConfig": DocumentClassifierOutputDataConfigTypeDef,
-        "ClassifierMetadata": ClassifierMetadataTypeDef,
-        "DataAccessRoleArn": str,
-        "VolumeKmsKeyId": str,
-        "VpcConfig": VpcConfigTypeDef,
-        "Mode": DocumentClassifierModeType,
-        "ModelKmsKeyId": str,
-        "VersionName": str,
-        "SourceModelArn": str,
-    },
-    total=False,
-)
-
 DocumentClassificationJobPropertiesTypeDef = TypedDict(
     "DocumentClassificationJobPropertiesTypeDef",
     {
         "JobId": str,
         "JobArn": str,
         "JobName": str,
         "JobStatus": JobStatusType,
@@ -2112,14 +2512,15 @@
         "EndTime": datetime,
         "DocumentClassifierArn": str,
         "InputDataConfig": InputDataConfigTypeDef,
         "OutputDataConfig": OutputDataConfigTypeDef,
         "DataAccessRoleArn": str,
         "VolumeKmsKeyId": str,
         "VpcConfig": VpcConfigTypeDef,
+        "FlywheelArn": str,
     },
     total=False,
 )
 
 DominantLanguageDetectionJobPropertiesTypeDef = TypedDict(
     "DominantLanguageDetectionJobPropertiesTypeDef",
     {
@@ -2152,14 +2553,15 @@
         "EntityRecognizerArn": str,
         "InputDataConfig": InputDataConfigTypeDef,
         "OutputDataConfig": OutputDataConfigTypeDef,
         "LanguageCode": LanguageCodeType,
         "DataAccessRoleArn": str,
         "VolumeKmsKeyId": str,
         "VpcConfig": VpcConfigTypeDef,
+        "FlywheelArn": str,
     },
     total=False,
 )
 
 EventsDetectionJobPropertiesTypeDef = TypedDict(
     "EventsDetectionJobPropertiesTypeDef",
     {
@@ -2238,40 +2640,39 @@
     },
     total=False,
 )
 
 _RequiredStartDocumentClassificationJobRequestRequestTypeDef = TypedDict(
     "_RequiredStartDocumentClassificationJobRequestRequestTypeDef",
     {
-        "DocumentClassifierArn": str,
         "InputDataConfig": InputDataConfigTypeDef,
         "OutputDataConfig": OutputDataConfigTypeDef,
         "DataAccessRoleArn": str,
     },
 )
 _OptionalStartDocumentClassificationJobRequestRequestTypeDef = TypedDict(
     "_OptionalStartDocumentClassificationJobRequestRequestTypeDef",
     {
         "JobName": str,
+        "DocumentClassifierArn": str,
         "ClientRequestToken": str,
         "VolumeKmsKeyId": str,
         "VpcConfig": VpcConfigTypeDef,
         "Tags": Sequence[TagTypeDef],
+        "FlywheelArn": str,
     },
     total=False,
 )
 
-
 class StartDocumentClassificationJobRequestRequestTypeDef(
     _RequiredStartDocumentClassificationJobRequestRequestTypeDef,
     _OptionalStartDocumentClassificationJobRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredStartDominantLanguageDetectionJobRequestRequestTypeDef = TypedDict(
     "_RequiredStartDominantLanguageDetectionJobRequestRequestTypeDef",
     {
         "InputDataConfig": InputDataConfigTypeDef,
         "OutputDataConfig": OutputDataConfigTypeDef,
         "DataAccessRoleArn": str,
     },
@@ -2284,22 +2685,20 @@
         "VolumeKmsKeyId": str,
         "VpcConfig": VpcConfigTypeDef,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class StartDominantLanguageDetectionJobRequestRequestTypeDef(
     _RequiredStartDominantLanguageDetectionJobRequestRequestTypeDef,
     _OptionalStartDominantLanguageDetectionJobRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredStartEntitiesDetectionJobRequestRequestTypeDef = TypedDict(
     "_RequiredStartEntitiesDetectionJobRequestRequestTypeDef",
     {
         "InputDataConfig": InputDataConfigTypeDef,
         "OutputDataConfig": OutputDataConfigTypeDef,
         "DataAccessRoleArn": str,
         "LanguageCode": LanguageCodeType,
@@ -2310,26 +2709,25 @@
     {
         "JobName": str,
         "EntityRecognizerArn": str,
         "ClientRequestToken": str,
         "VolumeKmsKeyId": str,
         "VpcConfig": VpcConfigTypeDef,
         "Tags": Sequence[TagTypeDef],
+        "FlywheelArn": str,
     },
     total=False,
 )
 
-
 class StartEntitiesDetectionJobRequestRequestTypeDef(
     _RequiredStartEntitiesDetectionJobRequestRequestTypeDef,
     _OptionalStartEntitiesDetectionJobRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredStartEventsDetectionJobRequestRequestTypeDef = TypedDict(
     "_RequiredStartEventsDetectionJobRequestRequestTypeDef",
     {
         "InputDataConfig": InputDataConfigTypeDef,
         "OutputDataConfig": OutputDataConfigTypeDef,
         "DataAccessRoleArn": str,
         "LanguageCode": LanguageCodeType,
@@ -2342,22 +2740,20 @@
         "JobName": str,
         "ClientRequestToken": str,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class StartEventsDetectionJobRequestRequestTypeDef(
     _RequiredStartEventsDetectionJobRequestRequestTypeDef,
     _OptionalStartEventsDetectionJobRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredStartKeyPhrasesDetectionJobRequestRequestTypeDef = TypedDict(
     "_RequiredStartKeyPhrasesDetectionJobRequestRequestTypeDef",
     {
         "InputDataConfig": InputDataConfigTypeDef,
         "OutputDataConfig": OutputDataConfigTypeDef,
         "DataAccessRoleArn": str,
         "LanguageCode": LanguageCodeType,
@@ -2371,22 +2767,20 @@
         "VolumeKmsKeyId": str,
         "VpcConfig": VpcConfigTypeDef,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class StartKeyPhrasesDetectionJobRequestRequestTypeDef(
     _RequiredStartKeyPhrasesDetectionJobRequestRequestTypeDef,
     _OptionalStartKeyPhrasesDetectionJobRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredStartPiiEntitiesDetectionJobRequestRequestTypeDef = TypedDict(
     "_RequiredStartPiiEntitiesDetectionJobRequestRequestTypeDef",
     {
         "InputDataConfig": InputDataConfigTypeDef,
         "OutputDataConfig": OutputDataConfigTypeDef,
         "Mode": PiiEntitiesDetectionModeType,
         "DataAccessRoleArn": str,
@@ -2400,22 +2794,20 @@
         "JobName": str,
         "ClientRequestToken": str,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class StartPiiEntitiesDetectionJobRequestRequestTypeDef(
     _RequiredStartPiiEntitiesDetectionJobRequestRequestTypeDef,
     _OptionalStartPiiEntitiesDetectionJobRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredStartSentimentDetectionJobRequestRequestTypeDef = TypedDict(
     "_RequiredStartSentimentDetectionJobRequestRequestTypeDef",
     {
         "InputDataConfig": InputDataConfigTypeDef,
         "OutputDataConfig": OutputDataConfigTypeDef,
         "DataAccessRoleArn": str,
         "LanguageCode": LanguageCodeType,
@@ -2429,22 +2821,20 @@
         "VolumeKmsKeyId": str,
         "VpcConfig": VpcConfigTypeDef,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class StartSentimentDetectionJobRequestRequestTypeDef(
     _RequiredStartSentimentDetectionJobRequestRequestTypeDef,
     _OptionalStartSentimentDetectionJobRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredStartTargetedSentimentDetectionJobRequestRequestTypeDef = TypedDict(
     "_RequiredStartTargetedSentimentDetectionJobRequestRequestTypeDef",
     {
         "InputDataConfig": InputDataConfigTypeDef,
         "OutputDataConfig": OutputDataConfigTypeDef,
         "DataAccessRoleArn": str,
         "LanguageCode": LanguageCodeType,
@@ -2458,22 +2848,20 @@
         "VolumeKmsKeyId": str,
         "VpcConfig": VpcConfigTypeDef,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class StartTargetedSentimentDetectionJobRequestRequestTypeDef(
     _RequiredStartTargetedSentimentDetectionJobRequestRequestTypeDef,
     _OptionalStartTargetedSentimentDetectionJobRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredStartTopicsDetectionJobRequestRequestTypeDef = TypedDict(
     "_RequiredStartTopicsDetectionJobRequestRequestTypeDef",
     {
         "InputDataConfig": InputDataConfigTypeDef,
         "OutputDataConfig": OutputDataConfigTypeDef,
         "DataAccessRoleArn": str,
     },
@@ -2487,22 +2875,20 @@
         "VolumeKmsKeyId": str,
         "VpcConfig": VpcConfigTypeDef,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class StartTopicsDetectionJobRequestRequestTypeDef(
     _RequiredStartTopicsDetectionJobRequestRequestTypeDef,
     _OptionalStartTopicsDetectionJobRequestRequestTypeDef,
 ):
     pass
 
-
 TargetedSentimentDetectionJobPropertiesTypeDef = TypedDict(
     "TargetedSentimentDetectionJobPropertiesTypeDef",
     {
         "JobId": str,
         "JobArn": str,
         "JobName": str,
         "JobStatus": JobStatusType,
@@ -2535,26 +2921,134 @@
         "DataAccessRoleArn": str,
         "VolumeKmsKeyId": str,
         "VpcConfig": VpcConfigTypeDef,
     },
     total=False,
 )
 
+_RequiredUpdateFlywheelRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateFlywheelRequestRequestTypeDef",
+    {
+        "FlywheelArn": str,
+    },
+)
+_OptionalUpdateFlywheelRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateFlywheelRequestRequestTypeDef",
+    {
+        "ActiveModelArn": str,
+        "DataAccessRoleArn": str,
+        "DataSecurityConfig": UpdateDataSecurityConfigTypeDef,
+    },
+    total=False,
+)
+
+class UpdateFlywheelRequestRequestTypeDef(
+    _RequiredUpdateFlywheelRequestRequestTypeDef, _OptionalUpdateFlywheelRequestRequestTypeDef
+):
+    pass
+
+DatasetInputDataConfigTypeDef = TypedDict(
+    "DatasetInputDataConfigTypeDef",
+    {
+        "AugmentedManifests": Sequence[DatasetAugmentedManifestsListItemTypeDef],
+        "DataFormat": DatasetDataFormatType,
+        "DocumentClassifierInputDataConfig": DatasetDocumentClassifierInputDataConfigTypeDef,
+        "EntityRecognizerInputDataConfig": DatasetEntityRecognizerInputDataConfigTypeDef,
+    },
+    total=False,
+)
+
+_RequiredCreateDocumentClassifierRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateDocumentClassifierRequestRequestTypeDef",
+    {
+        "DocumentClassifierName": str,
+        "DataAccessRoleArn": str,
+        "InputDataConfig": DocumentClassifierInputDataConfigTypeDef,
+        "LanguageCode": LanguageCodeType,
+    },
+)
+_OptionalCreateDocumentClassifierRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateDocumentClassifierRequestRequestTypeDef",
+    {
+        "VersionName": str,
+        "Tags": Sequence[TagTypeDef],
+        "OutputDataConfig": DocumentClassifierOutputDataConfigTypeDef,
+        "ClientRequestToken": str,
+        "VolumeKmsKeyId": str,
+        "VpcConfig": VpcConfigTypeDef,
+        "Mode": DocumentClassifierModeType,
+        "ModelKmsKeyId": str,
+        "ModelPolicy": str,
+    },
+    total=False,
+)
+
+class CreateDocumentClassifierRequestRequestTypeDef(
+    _RequiredCreateDocumentClassifierRequestRequestTypeDef,
+    _OptionalCreateDocumentClassifierRequestRequestTypeDef,
+):
+    pass
+
+DocumentClassifierPropertiesTypeDef = TypedDict(
+    "DocumentClassifierPropertiesTypeDef",
+    {
+        "DocumentClassifierArn": str,
+        "LanguageCode": LanguageCodeType,
+        "Status": ModelStatusType,
+        "Message": str,
+        "SubmitTime": datetime,
+        "EndTime": datetime,
+        "TrainingStartTime": datetime,
+        "TrainingEndTime": datetime,
+        "InputDataConfig": DocumentClassifierInputDataConfigTypeDef,
+        "OutputDataConfig": DocumentClassifierOutputDataConfigTypeDef,
+        "ClassifierMetadata": ClassifierMetadataTypeDef,
+        "DataAccessRoleArn": str,
+        "VolumeKmsKeyId": str,
+        "VpcConfig": VpcConfigTypeDef,
+        "Mode": DocumentClassifierModeType,
+        "ModelKmsKeyId": str,
+        "VersionName": str,
+        "SourceModelArn": str,
+        "FlywheelArn": str,
+    },
+    total=False,
+)
+
 ClassifyDocumentResponseTypeDef = TypedDict(
     "ClassifyDocumentResponseTypeDef",
     {
         "Classes": List[DocumentClassTypeDef],
         "Labels": List[DocumentLabelTypeDef],
         "DocumentMetadata": DocumentMetadataTypeDef,
         "DocumentType": List[DocumentTypeListItemTypeDef],
         "Errors": List[ErrorsListItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Warnings": List[WarningsListItemTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
+_RequiredTaskConfigTypeDef = TypedDict(
+    "_RequiredTaskConfigTypeDef",
+    {
+        "LanguageCode": LanguageCodeType,
+    },
+)
+_OptionalTaskConfigTypeDef = TypedDict(
+    "_OptionalTaskConfigTypeDef",
+    {
+        "DocumentClassificationConfig": DocumentClassificationConfigTypeDef,
+        "EntityRecognitionConfig": EntityRecognitionConfigTypeDef,
+    },
+    total=False,
+)
+
+class TaskConfigTypeDef(_RequiredTaskConfigTypeDef, _OptionalTaskConfigTypeDef):
+    pass
+
 _RequiredCreateEntityRecognizerRequestRequestTypeDef = TypedDict(
     "_RequiredCreateEntityRecognizerRequestRequestTypeDef",
     {
         "RecognizerName": str,
         "DataAccessRoleArn": str,
         "InputDataConfig": EntityRecognizerInputDataConfigTypeDef,
         "LanguageCode": LanguageCodeType,
@@ -2570,33 +3064,48 @@
         "VpcConfig": VpcConfigTypeDef,
         "ModelKmsKeyId": str,
         "ModelPolicy": str,
     },
     total=False,
 )
 
-
 class CreateEntityRecognizerRequestRequestTypeDef(
     _RequiredCreateEntityRecognizerRequestRequestTypeDef,
     _OptionalCreateEntityRecognizerRequestRequestTypeDef,
 ):
     pass
 
-
 EntityRecognizerMetadataTypeDef = TypedDict(
     "EntityRecognizerMetadataTypeDef",
     {
         "NumberOfTrainedDocuments": int,
         "NumberOfTestDocuments": int,
         "EvaluationMetrics": EntityRecognizerEvaluationMetricsTypeDef,
         "EntityTypes": List[EntityRecognizerMetadataEntityTypesListItemTypeDef],
     },
     total=False,
 )
 
+DescribeFlywheelIterationResponseTypeDef = TypedDict(
+    "DescribeFlywheelIterationResponseTypeDef",
+    {
+        "FlywheelIterationProperties": FlywheelIterationPropertiesTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListFlywheelIterationHistoryResponseTypeDef = TypedDict(
+    "ListFlywheelIterationHistoryResponseTypeDef",
+    {
+        "FlywheelIterationPropertiesList": List[FlywheelIterationPropertiesTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 BlockTypeDef = TypedDict(
     "BlockTypeDef",
     {
         "Id": str,
         "BlockType": BlockTypeType,
         "Text": str,
         "Page": int,
@@ -2615,15 +3124,15 @@
     total=False,
 )
 
 DetectSyntaxResponseTypeDef = TypedDict(
     "DetectSyntaxResponseTypeDef",
     {
         "SyntaxTokens": List[SyntaxTokenTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TargetedSentimentEntityTypeDef = TypedDict(
     "TargetedSentimentEntityTypeDef",
     {
         "DescriptiveMentionIndex": List[int],
@@ -2637,188 +3146,257 @@
     {
         "Index": int,
         "Entities": List[EntityTypeDef],
     },
     total=False,
 )
 
-DescribeDocumentClassifierResponseTypeDef = TypedDict(
-    "DescribeDocumentClassifierResponseTypeDef",
-    {
-        "DocumentClassifierProperties": DocumentClassifierPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDocumentClassifiersResponseTypeDef = TypedDict(
-    "ListDocumentClassifiersResponseTypeDef",
-    {
-        "DocumentClassifierPropertiesList": List[DocumentClassifierPropertiesTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 DescribeDocumentClassificationJobResponseTypeDef = TypedDict(
     "DescribeDocumentClassificationJobResponseTypeDef",
     {
         "DocumentClassificationJobProperties": DocumentClassificationJobPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDocumentClassificationJobsResponseTypeDef = TypedDict(
     "ListDocumentClassificationJobsResponseTypeDef",
     {
         "DocumentClassificationJobPropertiesList": List[DocumentClassificationJobPropertiesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDominantLanguageDetectionJobResponseTypeDef = TypedDict(
     "DescribeDominantLanguageDetectionJobResponseTypeDef",
     {
         "DominantLanguageDetectionJobProperties": DominantLanguageDetectionJobPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDominantLanguageDetectionJobsResponseTypeDef = TypedDict(
     "ListDominantLanguageDetectionJobsResponseTypeDef",
     {
         "DominantLanguageDetectionJobPropertiesList": List[
             DominantLanguageDetectionJobPropertiesTypeDef
         ],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEntitiesDetectionJobResponseTypeDef = TypedDict(
     "DescribeEntitiesDetectionJobResponseTypeDef",
     {
         "EntitiesDetectionJobProperties": EntitiesDetectionJobPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEntitiesDetectionJobsResponseTypeDef = TypedDict(
     "ListEntitiesDetectionJobsResponseTypeDef",
     {
         "EntitiesDetectionJobPropertiesList": List[EntitiesDetectionJobPropertiesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEventsDetectionJobResponseTypeDef = TypedDict(
     "DescribeEventsDetectionJobResponseTypeDef",
     {
         "EventsDetectionJobProperties": EventsDetectionJobPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEventsDetectionJobsResponseTypeDef = TypedDict(
     "ListEventsDetectionJobsResponseTypeDef",
     {
         "EventsDetectionJobPropertiesList": List[EventsDetectionJobPropertiesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeKeyPhrasesDetectionJobResponseTypeDef = TypedDict(
     "DescribeKeyPhrasesDetectionJobResponseTypeDef",
     {
         "KeyPhrasesDetectionJobProperties": KeyPhrasesDetectionJobPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListKeyPhrasesDetectionJobsResponseTypeDef = TypedDict(
     "ListKeyPhrasesDetectionJobsResponseTypeDef",
     {
         "KeyPhrasesDetectionJobPropertiesList": List[KeyPhrasesDetectionJobPropertiesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribePiiEntitiesDetectionJobResponseTypeDef = TypedDict(
     "DescribePiiEntitiesDetectionJobResponseTypeDef",
     {
         "PiiEntitiesDetectionJobProperties": PiiEntitiesDetectionJobPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPiiEntitiesDetectionJobsResponseTypeDef = TypedDict(
     "ListPiiEntitiesDetectionJobsResponseTypeDef",
     {
         "PiiEntitiesDetectionJobPropertiesList": List[PiiEntitiesDetectionJobPropertiesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSentimentDetectionJobResponseTypeDef = TypedDict(
     "DescribeSentimentDetectionJobResponseTypeDef",
     {
         "SentimentDetectionJobProperties": SentimentDetectionJobPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSentimentDetectionJobsResponseTypeDef = TypedDict(
     "ListSentimentDetectionJobsResponseTypeDef",
     {
         "SentimentDetectionJobPropertiesList": List[SentimentDetectionJobPropertiesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeTargetedSentimentDetectionJobResponseTypeDef = TypedDict(
     "DescribeTargetedSentimentDetectionJobResponseTypeDef",
     {
         "TargetedSentimentDetectionJobProperties": TargetedSentimentDetectionJobPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTargetedSentimentDetectionJobsResponseTypeDef = TypedDict(
     "ListTargetedSentimentDetectionJobsResponseTypeDef",
     {
         "TargetedSentimentDetectionJobPropertiesList": List[
             TargetedSentimentDetectionJobPropertiesTypeDef
         ],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeTopicsDetectionJobResponseTypeDef = TypedDict(
     "DescribeTopicsDetectionJobResponseTypeDef",
     {
         "TopicsDetectionJobProperties": TopicsDetectionJobPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTopicsDetectionJobsResponseTypeDef = TypedDict(
     "ListTopicsDetectionJobsResponseTypeDef",
     {
         "TopicsDetectionJobPropertiesList": List[TopicsDetectionJobPropertiesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
+_RequiredCreateDatasetRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateDatasetRequestRequestTypeDef",
+    {
+        "FlywheelArn": str,
+        "DatasetName": str,
+        "InputDataConfig": DatasetInputDataConfigTypeDef,
+    },
+)
+_OptionalCreateDatasetRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateDatasetRequestRequestTypeDef",
+    {
+        "DatasetType": DatasetTypeType,
+        "Description": str,
+        "ClientRequestToken": str,
+        "Tags": Sequence[TagTypeDef],
+    },
+    total=False,
+)
+
+class CreateDatasetRequestRequestTypeDef(
+    _RequiredCreateDatasetRequestRequestTypeDef, _OptionalCreateDatasetRequestRequestTypeDef
+):
+    pass
+
+DescribeDocumentClassifierResponseTypeDef = TypedDict(
+    "DescribeDocumentClassifierResponseTypeDef",
+    {
+        "DocumentClassifierProperties": DocumentClassifierPropertiesTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListDocumentClassifiersResponseTypeDef = TypedDict(
+    "ListDocumentClassifiersResponseTypeDef",
+    {
+        "DocumentClassifierPropertiesList": List[DocumentClassifierPropertiesTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredCreateFlywheelRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateFlywheelRequestRequestTypeDef",
+    {
+        "FlywheelName": str,
+        "DataAccessRoleArn": str,
+        "DataLakeS3Uri": str,
+    },
+)
+_OptionalCreateFlywheelRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateFlywheelRequestRequestTypeDef",
+    {
+        "ActiveModelArn": str,
+        "TaskConfig": TaskConfigTypeDef,
+        "ModelType": ModelTypeType,
+        "DataSecurityConfig": DataSecurityConfigTypeDef,
+        "ClientRequestToken": str,
+        "Tags": Sequence[TagTypeDef],
+    },
+    total=False,
+)
+
+class CreateFlywheelRequestRequestTypeDef(
+    _RequiredCreateFlywheelRequestRequestTypeDef, _OptionalCreateFlywheelRequestRequestTypeDef
+):
+    pass
+
+FlywheelPropertiesTypeDef = TypedDict(
+    "FlywheelPropertiesTypeDef",
+    {
+        "FlywheelArn": str,
+        "ActiveModelArn": str,
+        "DataAccessRoleArn": str,
+        "TaskConfig": TaskConfigTypeDef,
+        "DataLakeS3Uri": str,
+        "DataSecurityConfig": DataSecurityConfigTypeDef,
+        "Status": FlywheelStatusType,
+        "ModelType": ModelTypeType,
+        "Message": str,
+        "CreationTime": datetime,
+        "LastModifiedTime": datetime,
+        "LatestFlywheelIteration": str,
+    },
+    total=False,
+)
+
 EntityRecognizerPropertiesTypeDef = TypedDict(
     "EntityRecognizerPropertiesTypeDef",
     {
         "EntityRecognizerArn": str,
         "LanguageCode": LanguageCodeType,
         "Status": ModelStatusType,
         "Message": str,
@@ -2830,36 +3408,38 @@
         "RecognizerMetadata": EntityRecognizerMetadataTypeDef,
         "DataAccessRoleArn": str,
         "VolumeKmsKeyId": str,
         "VpcConfig": VpcConfigTypeDef,
         "ModelKmsKeyId": str,
         "VersionName": str,
         "SourceModelArn": str,
+        "FlywheelArn": str,
+        "OutputDataConfig": EntityRecognizerOutputDataConfigTypeDef,
     },
     total=False,
 )
 
 DetectEntitiesResponseTypeDef = TypedDict(
     "DetectEntitiesResponseTypeDef",
     {
         "Entities": List[EntityTypeDef],
         "DocumentMetadata": DocumentMetadataTypeDef,
         "DocumentType": List[DocumentTypeListItemTypeDef],
         "Blocks": List[BlockTypeDef],
         "Errors": List[ErrorsListItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDetectSyntaxResponseTypeDef = TypedDict(
     "BatchDetectSyntaxResponseTypeDef",
     {
         "ResultList": List[BatchDetectSyntaxItemResultTypeDef],
         "ErrorList": List[BatchItemErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDetectTargetedSentimentItemResultTypeDef = TypedDict(
     "BatchDetectTargetedSentimentItemResultTypeDef",
     {
         "Index": int,
@@ -2868,45 +3448,61 @@
     total=False,
 )
 
 DetectTargetedSentimentResponseTypeDef = TypedDict(
     "DetectTargetedSentimentResponseTypeDef",
     {
         "Entities": List[TargetedSentimentEntityTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDetectEntitiesResponseTypeDef = TypedDict(
     "BatchDetectEntitiesResponseTypeDef",
     {
         "ResultList": List[BatchDetectEntitiesItemResultTypeDef],
         "ErrorList": List[BatchItemErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeFlywheelResponseTypeDef = TypedDict(
+    "DescribeFlywheelResponseTypeDef",
+    {
+        "FlywheelProperties": FlywheelPropertiesTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateFlywheelResponseTypeDef = TypedDict(
+    "UpdateFlywheelResponseTypeDef",
+    {
+        "FlywheelProperties": FlywheelPropertiesTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEntityRecognizerResponseTypeDef = TypedDict(
     "DescribeEntityRecognizerResponseTypeDef",
     {
         "EntityRecognizerProperties": EntityRecognizerPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEntityRecognizersResponseTypeDef = TypedDict(
     "ListEntityRecognizersResponseTypeDef",
     {
         "EntityRecognizerPropertiesList": List[EntityRecognizerPropertiesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDetectTargetedSentimentResponseTypeDef = TypedDict(
     "BatchDetectTargetedSentimentResponseTypeDef",
     {
         "ResultList": List[BatchDetectTargetedSentimentItemResultTypeDef],
         "ErrorList": List[BatchItemErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-comprehend-2.5.0.post1/types_aiobotocore_comprehend/type_defs.pyi` & `types-aiobotocore-comprehend-2.5.1/types_aiobotocore_comprehend/type_defs.py`

 * *Files 14% similar despite different names*

```diff
@@ -16,28 +16,36 @@
 from typing import IO, Any, Dict, List, Sequence, Union
 
 from aiobotocore.response import StreamingBody
 
 from .literals import (
     AugmentedManifestsDocumentTypeFormatType,
     BlockTypeType,
+    DatasetDataFormatType,
+    DatasetStatusType,
+    DatasetTypeType,
     DocumentClassifierDataFormatType,
+    DocumentClassifierDocumentTypeFormatType,
     DocumentClassifierModeType,
     DocumentReadActionType,
     DocumentReadFeatureTypesType,
     DocumentReadModeType,
     DocumentTypeType,
     EndpointStatusType,
     EntityRecognizerDataFormatType,
     EntityTypeType,
+    FlywheelIterationStatusType,
+    FlywheelStatusType,
     InputFormatType,
     JobStatusType,
     LanguageCodeType,
     ModelStatusType,
+    ModelTypeType,
     PageBasedErrorCodeType,
+    PageBasedWarningCodeType,
     PartOfSpeechTagTypeType,
     PiiEntitiesDetectionMaskModeType,
     PiiEntitiesDetectionModeType,
     PiiEntityTypeType,
     SentimentTypeType,
     SplitType,
     SyntaxLanguageCodeType,
@@ -49,20 +57,20 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "AugmentedManifestsListItemTypeDef",
     "DominantLanguageTypeDef",
     "BatchDetectDominantLanguageRequestRequestTypeDef",
     "BatchItemErrorTypeDef",
-    "ResponseMetadataTypeDef",
     "BatchDetectEntitiesRequestRequestTypeDef",
     "KeyPhraseTypeDef",
     "BatchDetectKeyPhrasesRequestRequestTypeDef",
     "SentimentScoreTypeDef",
     "BatchDetectSentimentRequestRequestTypeDef",
     "BatchDetectSyntaxRequestRequestTypeDef",
     "BatchDetectTargetedSentimentRequestRequestTypeDef",
@@ -71,111 +79,135 @@
     "BoundingBoxTypeDef",
     "ClassifierEvaluationMetricsTypeDef",
     "DocumentReaderConfigTypeDef",
     "DocumentClassTypeDef",
     "DocumentLabelTypeDef",
     "DocumentTypeListItemTypeDef",
     "ErrorsListItemTypeDef",
+    "WarningsListItemTypeDef",
     "ContainsPiiEntitiesRequestRequestTypeDef",
     "EntityLabelTypeDef",
-    "DocumentClassifierOutputDataConfigTypeDef",
     "TagTypeDef",
+    "CreateDatasetResponseTypeDef",
+    "DocumentClassifierOutputDataConfigTypeDef",
     "VpcConfigTypeDef",
+    "CreateDocumentClassifierResponseTypeDef",
+    "CreateEndpointResponseTypeDef",
+    "CreateEntityRecognizerResponseTypeDef",
+    "CreateFlywheelResponseTypeDef",
+    "DatasetAugmentedManifestsListItemTypeDef",
+    "DatasetDocumentClassifierInputDataConfigTypeDef",
+    "DatasetEntityRecognizerAnnotationsTypeDef",
+    "DatasetEntityRecognizerDocumentsTypeDef",
+    "DatasetEntityRecognizerEntityListTypeDef",
+    "DatasetFilterTypeDef",
+    "DatasetPropertiesTypeDef",
     "DeleteDocumentClassifierRequestRequestTypeDef",
     "DeleteEndpointRequestRequestTypeDef",
     "DeleteEntityRecognizerRequestRequestTypeDef",
+    "DeleteFlywheelRequestRequestTypeDef",
     "DeleteResourcePolicyRequestRequestTypeDef",
+    "DescribeDatasetRequestRequestTypeDef",
     "DescribeDocumentClassificationJobRequestRequestTypeDef",
     "DescribeDocumentClassifierRequestRequestTypeDef",
     "DescribeDominantLanguageDetectionJobRequestRequestTypeDef",
     "DescribeEndpointRequestRequestTypeDef",
     "EndpointPropertiesTypeDef",
     "DescribeEntitiesDetectionJobRequestRequestTypeDef",
     "DescribeEntityRecognizerRequestRequestTypeDef",
     "DescribeEventsDetectionJobRequestRequestTypeDef",
+    "DescribeFlywheelIterationRequestRequestTypeDef",
+    "DescribeFlywheelRequestRequestTypeDef",
     "DescribeKeyPhrasesDetectionJobRequestRequestTypeDef",
     "DescribePiiEntitiesDetectionJobRequestRequestTypeDef",
     "DescribeResourcePolicyRequestRequestTypeDef",
+    "DescribeResourcePolicyResponseTypeDef",
     "DescribeSentimentDetectionJobRequestRequestTypeDef",
     "DescribeTargetedSentimentDetectionJobRequestRequestTypeDef",
     "DescribeTopicsDetectionJobRequestRequestTypeDef",
     "DetectDominantLanguageRequestRequestTypeDef",
     "DetectKeyPhrasesRequestRequestTypeDef",
     "DetectPiiEntitiesRequestRequestTypeDef",
     "PiiEntityTypeDef",
     "DetectSentimentRequestRequestTypeDef",
     "DetectSyntaxRequestRequestTypeDef",
     "DetectTargetedSentimentRequestRequestTypeDef",
+    "DocumentClassificationConfigTypeDef",
     "DocumentClassificationJobFilterTypeDef",
     "OutputDataConfigTypeDef",
+    "DocumentClassifierDocumentsTypeDef",
     "DocumentClassifierFilterTypeDef",
     "DocumentClassifierSummaryTypeDef",
     "ExtractedCharactersListItemTypeDef",
     "DominantLanguageDetectionJobFilterTypeDef",
     "EndpointFilterTypeDef",
     "EntitiesDetectionJobFilterTypeDef",
+    "EntityTypesListItemTypeDef",
     "EntityRecognizerAnnotationsTypeDef",
     "EntityRecognizerDocumentsTypeDef",
     "EntityRecognizerEntityListTypeDef",
     "EntityRecognizerEvaluationMetricsTypeDef",
     "EntityRecognizerFilterTypeDef",
-    "EntityTypesListItemTypeDef",
     "EntityTypesEvaluationMetricsTypeDef",
+    "EntityRecognizerOutputDataConfigTypeDef",
     "EntityRecognizerSummaryTypeDef",
     "EventsDetectionJobFilterTypeDef",
+    "FlywheelFilterTypeDef",
+    "FlywheelIterationFilterTypeDef",
+    "FlywheelModelEvaluationMetricsTypeDef",
+    "FlywheelSummaryTypeDef",
     "PointTypeDef",
+    "ImportModelResponseTypeDef",
     "KeyPhrasesDetectionJobFilterTypeDef",
-    "PaginatorConfigTypeDef",
     "ListDocumentClassifierSummariesRequestRequestTypeDef",
     "ListEntityRecognizerSummariesRequestRequestTypeDef",
     "PiiEntitiesDetectionJobFilterTypeDef",
     "SentimentDetectionJobFilterTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "TargetedSentimentDetectionJobFilterTypeDef",
     "TopicsDetectionJobFilterTypeDef",
+    "PaginatorConfigTypeDef",
     "PartOfSpeechTagTypeDef",
     "PiiOutputDataConfigTypeDef",
     "RedactionConfigTypeDef",
     "PutResourcePolicyRequestRequestTypeDef",
-    "StopDominantLanguageDetectionJobRequestRequestTypeDef",
-    "StopEntitiesDetectionJobRequestRequestTypeDef",
-    "StopEventsDetectionJobRequestRequestTypeDef",
-    "StopKeyPhrasesDetectionJobRequestRequestTypeDef",
-    "StopPiiEntitiesDetectionJobRequestRequestTypeDef",
-    "StopSentimentDetectionJobRequestRequestTypeDef",
-    "StopTargetedSentimentDetectionJobRequestRequestTypeDef",
-    "StopTrainingDocumentClassifierRequestRequestTypeDef",
-    "StopTrainingEntityRecognizerRequestRequestTypeDef",
-    "UntagResourceRequestRequestTypeDef",
-    "UpdateEndpointRequestRequestTypeDef",
-    "DocumentClassifierInputDataConfigTypeDef",
-    "BatchDetectDominantLanguageItemResultTypeDef",
-    "CreateDocumentClassifierResponseTypeDef",
-    "CreateEndpointResponseTypeDef",
-    "CreateEntityRecognizerResponseTypeDef",
-    "DescribeResourcePolicyResponseTypeDef",
-    "DetectDominantLanguageResponseTypeDef",
-    "ImportModelResponseTypeDef",
     "PutResourcePolicyResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "StartDocumentClassificationJobResponseTypeDef",
     "StartDominantLanguageDetectionJobResponseTypeDef",
     "StartEntitiesDetectionJobResponseTypeDef",
     "StartEventsDetectionJobResponseTypeDef",
+    "StartFlywheelIterationRequestRequestTypeDef",
+    "StartFlywheelIterationResponseTypeDef",
     "StartKeyPhrasesDetectionJobResponseTypeDef",
     "StartPiiEntitiesDetectionJobResponseTypeDef",
     "StartSentimentDetectionJobResponseTypeDef",
     "StartTargetedSentimentDetectionJobResponseTypeDef",
     "StartTopicsDetectionJobResponseTypeDef",
+    "StopDominantLanguageDetectionJobRequestRequestTypeDef",
     "StopDominantLanguageDetectionJobResponseTypeDef",
+    "StopEntitiesDetectionJobRequestRequestTypeDef",
     "StopEntitiesDetectionJobResponseTypeDef",
+    "StopEventsDetectionJobRequestRequestTypeDef",
     "StopEventsDetectionJobResponseTypeDef",
+    "StopKeyPhrasesDetectionJobRequestRequestTypeDef",
     "StopKeyPhrasesDetectionJobResponseTypeDef",
+    "StopPiiEntitiesDetectionJobRequestRequestTypeDef",
     "StopPiiEntitiesDetectionJobResponseTypeDef",
+    "StopSentimentDetectionJobRequestRequestTypeDef",
     "StopSentimentDetectionJobResponseTypeDef",
+    "StopTargetedSentimentDetectionJobRequestRequestTypeDef",
     "StopTargetedSentimentDetectionJobResponseTypeDef",
+    "StopTrainingDocumentClassifierRequestRequestTypeDef",
+    "StopTrainingEntityRecognizerRequestRequestTypeDef",
+    "UntagResourceRequestRequestTypeDef",
+    "UpdateEndpointRequestRequestTypeDef",
+    "UpdateEndpointResponseTypeDef",
+    "BatchDetectDominantLanguageItemResultTypeDef",
+    "DetectDominantLanguageResponseTypeDef",
     "BatchDetectKeyPhrasesItemResultTypeDef",
     "DetectKeyPhrasesResponseTypeDef",
     "BatchDetectSentimentItemResultTypeDef",
     "DetectSentimentResponseTypeDef",
     "MentionSentimentTypeDef",
     "BlockReferenceTypeDef",
     "ClassifierMetadataTypeDef",
@@ -183,53 +215,63 @@
     "DetectEntitiesRequestRequestTypeDef",
     "InputDataConfigTypeDef",
     "ContainsPiiEntitiesResponseTypeDef",
     "CreateEndpointRequestRequestTypeDef",
     "ImportModelRequestRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
+    "DataSecurityConfigTypeDef",
+    "UpdateDataSecurityConfigTypeDef",
+    "DatasetEntityRecognizerInputDataConfigTypeDef",
+    "ListDatasetsRequestRequestTypeDef",
+    "DescribeDatasetResponseTypeDef",
+    "ListDatasetsResponseTypeDef",
     "DescribeEndpointResponseTypeDef",
     "ListEndpointsResponseTypeDef",
     "DetectPiiEntitiesResponseTypeDef",
+    "ListDocumentClassificationJobsRequestListDocumentClassificationJobsPaginateTypeDef",
     "ListDocumentClassificationJobsRequestRequestTypeDef",
+    "DocumentClassifierInputDataConfigTypeDef",
+    "ListDocumentClassifiersRequestListDocumentClassifiersPaginateTypeDef",
     "ListDocumentClassifiersRequestRequestTypeDef",
     "ListDocumentClassifierSummariesResponseTypeDef",
     "DocumentMetadataTypeDef",
+    "ListDominantLanguageDetectionJobsRequestListDominantLanguageDetectionJobsPaginateTypeDef",
     "ListDominantLanguageDetectionJobsRequestRequestTypeDef",
+    "ListEndpointsRequestListEndpointsPaginateTypeDef",
     "ListEndpointsRequestRequestTypeDef",
+    "ListEntitiesDetectionJobsRequestListEntitiesDetectionJobsPaginateTypeDef",
     "ListEntitiesDetectionJobsRequestRequestTypeDef",
-    "ListEntityRecognizersRequestRequestTypeDef",
+    "EntityRecognitionConfigTypeDef",
     "EntityRecognizerInputDataConfigTypeDef",
+    "ListEntityRecognizersRequestListEntityRecognizersPaginateTypeDef",
+    "ListEntityRecognizersRequestRequestTypeDef",
     "EntityRecognizerMetadataEntityTypesListItemTypeDef",
     "ListEntityRecognizerSummariesResponseTypeDef",
     "ListEventsDetectionJobsRequestRequestTypeDef",
+    "ListFlywheelsRequestRequestTypeDef",
+    "ListFlywheelIterationHistoryRequestRequestTypeDef",
+    "FlywheelIterationPropertiesTypeDef",
+    "ListFlywheelsResponseTypeDef",
     "GeometryTypeDef",
-    "ListKeyPhrasesDetectionJobsRequestRequestTypeDef",
-    "ListDocumentClassificationJobsRequestListDocumentClassificationJobsPaginateTypeDef",
-    "ListDocumentClassifiersRequestListDocumentClassifiersPaginateTypeDef",
-    "ListDominantLanguageDetectionJobsRequestListDominantLanguageDetectionJobsPaginateTypeDef",
-    "ListEndpointsRequestListEndpointsPaginateTypeDef",
-    "ListEntitiesDetectionJobsRequestListEntitiesDetectionJobsPaginateTypeDef",
-    "ListEntityRecognizersRequestListEntityRecognizersPaginateTypeDef",
     "ListKeyPhrasesDetectionJobsRequestListKeyPhrasesDetectionJobsPaginateTypeDef",
+    "ListKeyPhrasesDetectionJobsRequestRequestTypeDef",
     "ListPiiEntitiesDetectionJobsRequestListPiiEntitiesDetectionJobsPaginateTypeDef",
     "ListPiiEntitiesDetectionJobsRequestRequestTypeDef",
     "ListSentimentDetectionJobsRequestListSentimentDetectionJobsPaginateTypeDef",
     "ListSentimentDetectionJobsRequestRequestTypeDef",
     "ListTargetedSentimentDetectionJobsRequestRequestTypeDef",
     "ListTopicsDetectionJobsRequestListTopicsDetectionJobsPaginateTypeDef",
     "ListTopicsDetectionJobsRequestRequestTypeDef",
     "SyntaxTokenTypeDef",
-    "CreateDocumentClassifierRequestRequestTypeDef",
     "BatchDetectDominantLanguageResponseTypeDef",
     "BatchDetectKeyPhrasesResponseTypeDef",
     "BatchDetectSentimentResponseTypeDef",
     "TargetedSentimentMentionTypeDef",
     "EntityTypeDef",
-    "DocumentClassifierPropertiesTypeDef",
     "DocumentClassificationJobPropertiesTypeDef",
     "DominantLanguageDetectionJobPropertiesTypeDef",
     "EntitiesDetectionJobPropertiesTypeDef",
     "EventsDetectionJobPropertiesTypeDef",
     "KeyPhrasesDetectionJobPropertiesTypeDef",
     "PiiEntitiesDetectionJobPropertiesTypeDef",
     "SentimentDetectionJobPropertiesTypeDef",
@@ -240,24 +282,29 @@
     "StartKeyPhrasesDetectionJobRequestRequestTypeDef",
     "StartPiiEntitiesDetectionJobRequestRequestTypeDef",
     "StartSentimentDetectionJobRequestRequestTypeDef",
     "StartTargetedSentimentDetectionJobRequestRequestTypeDef",
     "StartTopicsDetectionJobRequestRequestTypeDef",
     "TargetedSentimentDetectionJobPropertiesTypeDef",
     "TopicsDetectionJobPropertiesTypeDef",
+    "UpdateFlywheelRequestRequestTypeDef",
+    "DatasetInputDataConfigTypeDef",
+    "CreateDocumentClassifierRequestRequestTypeDef",
+    "DocumentClassifierPropertiesTypeDef",
     "ClassifyDocumentResponseTypeDef",
+    "TaskConfigTypeDef",
     "CreateEntityRecognizerRequestRequestTypeDef",
     "EntityRecognizerMetadataTypeDef",
+    "DescribeFlywheelIterationResponseTypeDef",
+    "ListFlywheelIterationHistoryResponseTypeDef",
     "BlockTypeDef",
     "BatchDetectSyntaxItemResultTypeDef",
     "DetectSyntaxResponseTypeDef",
     "TargetedSentimentEntityTypeDef",
     "BatchDetectEntitiesItemResultTypeDef",
-    "DescribeDocumentClassifierResponseTypeDef",
-    "ListDocumentClassifiersResponseTypeDef",
     "DescribeDocumentClassificationJobResponseTypeDef",
     "ListDocumentClassificationJobsResponseTypeDef",
     "DescribeDominantLanguageDetectionJobResponseTypeDef",
     "ListDominantLanguageDetectionJobsResponseTypeDef",
     "DescribeEntitiesDetectionJobResponseTypeDef",
     "ListEntitiesDetectionJobsResponseTypeDef",
     "DescribeEventsDetectionJobResponseTypeDef",
@@ -268,20 +315,27 @@
     "ListPiiEntitiesDetectionJobsResponseTypeDef",
     "DescribeSentimentDetectionJobResponseTypeDef",
     "ListSentimentDetectionJobsResponseTypeDef",
     "DescribeTargetedSentimentDetectionJobResponseTypeDef",
     "ListTargetedSentimentDetectionJobsResponseTypeDef",
     "DescribeTopicsDetectionJobResponseTypeDef",
     "ListTopicsDetectionJobsResponseTypeDef",
+    "CreateDatasetRequestRequestTypeDef",
+    "DescribeDocumentClassifierResponseTypeDef",
+    "ListDocumentClassifiersResponseTypeDef",
+    "CreateFlywheelRequestRequestTypeDef",
+    "FlywheelPropertiesTypeDef",
     "EntityRecognizerPropertiesTypeDef",
     "DetectEntitiesResponseTypeDef",
     "BatchDetectSyntaxResponseTypeDef",
     "BatchDetectTargetedSentimentItemResultTypeDef",
     "DetectTargetedSentimentResponseTypeDef",
     "BatchDetectEntitiesResponseTypeDef",
+    "DescribeFlywheelResponseTypeDef",
+    "UpdateFlywheelResponseTypeDef",
     "DescribeEntityRecognizerResponseTypeDef",
     "ListEntityRecognizersResponseTypeDef",
     "BatchDetectTargetedSentimentResponseTypeDef",
 )
 
 _RequiredAugmentedManifestsListItemTypeDef = TypedDict(
     "_RequiredAugmentedManifestsListItemTypeDef",
@@ -297,19 +351,21 @@
         "AnnotationDataS3Uri": str,
         "SourceDocumentsS3Uri": str,
         "DocumentType": AugmentedManifestsDocumentTypeFormatType,
     },
     total=False,
 )
 
+
 class AugmentedManifestsListItemTypeDef(
     _RequiredAugmentedManifestsListItemTypeDef, _OptionalAugmentedManifestsListItemTypeDef
 ):
     pass
 
+
 DominantLanguageTypeDef = TypedDict(
     "DominantLanguageTypeDef",
     {
         "LanguageCode": str,
         "Score": float,
     },
     total=False,
@@ -328,25 +384,14 @@
         "Index": int,
         "ErrorCode": str,
         "ErrorMessage": str,
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
 BatchDetectEntitiesRequestRequestTypeDef = TypedDict(
     "BatchDetectEntitiesRequestRequestTypeDef",
     {
         "TextList": Sequence[str],
         "LanguageCode": LanguageCodeType,
     },
 )
@@ -461,19 +506,21 @@
     {
         "DocumentReadMode": DocumentReadModeType,
         "FeatureTypes": Sequence[DocumentReadFeatureTypesType],
     },
     total=False,
 )
 
+
 class DocumentReaderConfigTypeDef(
     _RequiredDocumentReaderConfigTypeDef, _OptionalDocumentReaderConfigTypeDef
 ):
     pass
 
+
 DocumentClassTypeDef = TypedDict(
     "DocumentClassTypeDef",
     {
         "Name": str,
         "Score": float,
         "Page": int,
     },
@@ -505,14 +552,24 @@
         "Page": int,
         "ErrorCode": PageBasedErrorCodeType,
         "ErrorMessage": str,
     },
     total=False,
 )
 
+WarningsListItemTypeDef = TypedDict(
+    "WarningsListItemTypeDef",
+    {
+        "Page": int,
+        "WarnCode": PageBasedWarningCodeType,
+        "WarnMessage": str,
+    },
+    total=False,
+)
+
 ContainsPiiEntitiesRequestRequestTypeDef = TypedDict(
     "ContainsPiiEntitiesRequestRequestTypeDef",
     {
         "Text": str,
         "LanguageCode": LanguageCodeType,
     },
 )
@@ -522,48 +579,204 @@
     {
         "Name": PiiEntityTypeType,
         "Score": float,
     },
     total=False,
 )
 
-DocumentClassifierOutputDataConfigTypeDef = TypedDict(
-    "DocumentClassifierOutputDataConfigTypeDef",
-    {
-        "S3Uri": str,
-        "KmsKeyId": str,
-    },
-    total=False,
-)
-
 _RequiredTagTypeDef = TypedDict(
     "_RequiredTagTypeDef",
     {
         "Key": str,
     },
 )
 _OptionalTagTypeDef = TypedDict(
     "_OptionalTagTypeDef",
     {
         "Value": str,
     },
     total=False,
 )
 
+
 class TagTypeDef(_RequiredTagTypeDef, _OptionalTagTypeDef):
     pass
 
+
+CreateDatasetResponseTypeDef = TypedDict(
+    "CreateDatasetResponseTypeDef",
+    {
+        "DatasetArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DocumentClassifierOutputDataConfigTypeDef = TypedDict(
+    "DocumentClassifierOutputDataConfigTypeDef",
+    {
+        "S3Uri": str,
+        "KmsKeyId": str,
+        "FlywheelStatsS3Prefix": str,
+    },
+    total=False,
+)
+
 VpcConfigTypeDef = TypedDict(
     "VpcConfigTypeDef",
     {
         "SecurityGroupIds": Sequence[str],
         "Subnets": Sequence[str],
     },
 )
 
+CreateDocumentClassifierResponseTypeDef = TypedDict(
+    "CreateDocumentClassifierResponseTypeDef",
+    {
+        "DocumentClassifierArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateEndpointResponseTypeDef = TypedDict(
+    "CreateEndpointResponseTypeDef",
+    {
+        "EndpointArn": str,
+        "ModelArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateEntityRecognizerResponseTypeDef = TypedDict(
+    "CreateEntityRecognizerResponseTypeDef",
+    {
+        "EntityRecognizerArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateFlywheelResponseTypeDef = TypedDict(
+    "CreateFlywheelResponseTypeDef",
+    {
+        "FlywheelArn": str,
+        "ActiveModelArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredDatasetAugmentedManifestsListItemTypeDef = TypedDict(
+    "_RequiredDatasetAugmentedManifestsListItemTypeDef",
+    {
+        "AttributeNames": Sequence[str],
+        "S3Uri": str,
+    },
+)
+_OptionalDatasetAugmentedManifestsListItemTypeDef = TypedDict(
+    "_OptionalDatasetAugmentedManifestsListItemTypeDef",
+    {
+        "AnnotationDataS3Uri": str,
+        "SourceDocumentsS3Uri": str,
+        "DocumentType": AugmentedManifestsDocumentTypeFormatType,
+    },
+    total=False,
+)
+
+
+class DatasetAugmentedManifestsListItemTypeDef(
+    _RequiredDatasetAugmentedManifestsListItemTypeDef,
+    _OptionalDatasetAugmentedManifestsListItemTypeDef,
+):
+    pass
+
+
+_RequiredDatasetDocumentClassifierInputDataConfigTypeDef = TypedDict(
+    "_RequiredDatasetDocumentClassifierInputDataConfigTypeDef",
+    {
+        "S3Uri": str,
+    },
+)
+_OptionalDatasetDocumentClassifierInputDataConfigTypeDef = TypedDict(
+    "_OptionalDatasetDocumentClassifierInputDataConfigTypeDef",
+    {
+        "LabelDelimiter": str,
+    },
+    total=False,
+)
+
+
+class DatasetDocumentClassifierInputDataConfigTypeDef(
+    _RequiredDatasetDocumentClassifierInputDataConfigTypeDef,
+    _OptionalDatasetDocumentClassifierInputDataConfigTypeDef,
+):
+    pass
+
+
+DatasetEntityRecognizerAnnotationsTypeDef = TypedDict(
+    "DatasetEntityRecognizerAnnotationsTypeDef",
+    {
+        "S3Uri": str,
+    },
+)
+
+_RequiredDatasetEntityRecognizerDocumentsTypeDef = TypedDict(
+    "_RequiredDatasetEntityRecognizerDocumentsTypeDef",
+    {
+        "S3Uri": str,
+    },
+)
+_OptionalDatasetEntityRecognizerDocumentsTypeDef = TypedDict(
+    "_OptionalDatasetEntityRecognizerDocumentsTypeDef",
+    {
+        "InputFormat": InputFormatType,
+    },
+    total=False,
+)
+
+
+class DatasetEntityRecognizerDocumentsTypeDef(
+    _RequiredDatasetEntityRecognizerDocumentsTypeDef,
+    _OptionalDatasetEntityRecognizerDocumentsTypeDef,
+):
+    pass
+
+
+DatasetEntityRecognizerEntityListTypeDef = TypedDict(
+    "DatasetEntityRecognizerEntityListTypeDef",
+    {
+        "S3Uri": str,
+    },
+)
+
+DatasetFilterTypeDef = TypedDict(
+    "DatasetFilterTypeDef",
+    {
+        "Status": DatasetStatusType,
+        "DatasetType": DatasetTypeType,
+        "CreationTimeAfter": Union[datetime, str],
+        "CreationTimeBefore": Union[datetime, str],
+    },
+    total=False,
+)
+
+DatasetPropertiesTypeDef = TypedDict(
+    "DatasetPropertiesTypeDef",
+    {
+        "DatasetArn": str,
+        "DatasetName": str,
+        "DatasetType": DatasetTypeType,
+        "DatasetS3Uri": str,
+        "Description": str,
+        "Status": DatasetStatusType,
+        "Message": str,
+        "NumberOfDocuments": int,
+        "CreationTime": datetime,
+        "EndTime": datetime,
+    },
+    total=False,
+)
+
 DeleteDocumentClassifierRequestRequestTypeDef = TypedDict(
     "DeleteDocumentClassifierRequestRequestTypeDef",
     {
         "DocumentClassifierArn": str,
     },
 )
 
@@ -577,34 +790,50 @@
 DeleteEntityRecognizerRequestRequestTypeDef = TypedDict(
     "DeleteEntityRecognizerRequestRequestTypeDef",
     {
         "EntityRecognizerArn": str,
     },
 )
 
+DeleteFlywheelRequestRequestTypeDef = TypedDict(
+    "DeleteFlywheelRequestRequestTypeDef",
+    {
+        "FlywheelArn": str,
+    },
+)
+
 _RequiredDeleteResourcePolicyRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteResourcePolicyRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 _OptionalDeleteResourcePolicyRequestRequestTypeDef = TypedDict(
     "_OptionalDeleteResourcePolicyRequestRequestTypeDef",
     {
         "PolicyRevisionId": str,
     },
     total=False,
 )
 
+
 class DeleteResourcePolicyRequestRequestTypeDef(
     _RequiredDeleteResourcePolicyRequestRequestTypeDef,
     _OptionalDeleteResourcePolicyRequestRequestTypeDef,
 ):
     pass
 
+
+DescribeDatasetRequestRequestTypeDef = TypedDict(
+    "DescribeDatasetRequestRequestTypeDef",
+    {
+        "DatasetArn": str,
+    },
+)
+
 DescribeDocumentClassificationJobRequestRequestTypeDef = TypedDict(
     "DescribeDocumentClassificationJobRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 
@@ -639,14 +868,15 @@
         "DesiredModelArn": str,
         "DesiredInferenceUnits": int,
         "CurrentInferenceUnits": int,
         "CreationTime": datetime,
         "LastModifiedTime": datetime,
         "DataAccessRoleArn": str,
         "DesiredDataAccessRoleArn": str,
+        "FlywheelArn": str,
     },
     total=False,
 )
 
 DescribeEntitiesDetectionJobRequestRequestTypeDef = TypedDict(
     "DescribeEntitiesDetectionJobRequestRequestTypeDef",
     {
@@ -664,14 +894,29 @@
 DescribeEventsDetectionJobRequestRequestTypeDef = TypedDict(
     "DescribeEventsDetectionJobRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 
+DescribeFlywheelIterationRequestRequestTypeDef = TypedDict(
+    "DescribeFlywheelIterationRequestRequestTypeDef",
+    {
+        "FlywheelArn": str,
+        "FlywheelIterationId": str,
+    },
+)
+
+DescribeFlywheelRequestRequestTypeDef = TypedDict(
+    "DescribeFlywheelRequestRequestTypeDef",
+    {
+        "FlywheelArn": str,
+    },
+)
+
 DescribeKeyPhrasesDetectionJobRequestRequestTypeDef = TypedDict(
     "DescribeKeyPhrasesDetectionJobRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 
@@ -685,14 +930,25 @@
 DescribeResourcePolicyRequestRequestTypeDef = TypedDict(
     "DescribeResourcePolicyRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+DescribeResourcePolicyResponseTypeDef = TypedDict(
+    "DescribeResourcePolicyResponseTypeDef",
+    {
+        "ResourcePolicy": str,
+        "CreationTime": datetime,
+        "LastModifiedTime": datetime,
+        "PolicyRevisionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeSentimentDetectionJobRequestRequestTypeDef = TypedDict(
     "DescribeSentimentDetectionJobRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 
@@ -764,14 +1020,35 @@
     "DetectTargetedSentimentRequestRequestTypeDef",
     {
         "Text": str,
         "LanguageCode": LanguageCodeType,
     },
 )
 
+_RequiredDocumentClassificationConfigTypeDef = TypedDict(
+    "_RequiredDocumentClassificationConfigTypeDef",
+    {
+        "Mode": DocumentClassifierModeType,
+    },
+)
+_OptionalDocumentClassificationConfigTypeDef = TypedDict(
+    "_OptionalDocumentClassificationConfigTypeDef",
+    {
+        "Labels": Sequence[str],
+    },
+    total=False,
+)
+
+
+class DocumentClassificationConfigTypeDef(
+    _RequiredDocumentClassificationConfigTypeDef, _OptionalDocumentClassificationConfigTypeDef
+):
+    pass
+
+
 DocumentClassificationJobFilterTypeDef = TypedDict(
     "DocumentClassificationJobFilterTypeDef",
     {
         "JobName": str,
         "JobStatus": JobStatusType,
         "SubmitTimeBefore": Union[datetime, str],
         "SubmitTimeAfter": Union[datetime, str],
@@ -789,17 +1066,40 @@
     "_OptionalOutputDataConfigTypeDef",
     {
         "KmsKeyId": str,
     },
     total=False,
 )
 
+
 class OutputDataConfigTypeDef(_RequiredOutputDataConfigTypeDef, _OptionalOutputDataConfigTypeDef):
     pass
 
+
+_RequiredDocumentClassifierDocumentsTypeDef = TypedDict(
+    "_RequiredDocumentClassifierDocumentsTypeDef",
+    {
+        "S3Uri": str,
+    },
+)
+_OptionalDocumentClassifierDocumentsTypeDef = TypedDict(
+    "_OptionalDocumentClassifierDocumentsTypeDef",
+    {
+        "TestS3Uri": str,
+    },
+    total=False,
+)
+
+
+class DocumentClassifierDocumentsTypeDef(
+    _RequiredDocumentClassifierDocumentsTypeDef, _OptionalDocumentClassifierDocumentsTypeDef
+):
+    pass
+
+
 DocumentClassifierFilterTypeDef = TypedDict(
     "DocumentClassifierFilterTypeDef",
     {
         "Status": ModelStatusType,
         "DocumentClassifierName": str,
         "SubmitTimeBefore": Union[datetime, str],
         "SubmitTimeAfter": Union[datetime, str],
@@ -857,33 +1157,42 @@
         "JobStatus": JobStatusType,
         "SubmitTimeBefore": Union[datetime, str],
         "SubmitTimeAfter": Union[datetime, str],
     },
     total=False,
 )
 
+EntityTypesListItemTypeDef = TypedDict(
+    "EntityTypesListItemTypeDef",
+    {
+        "Type": str,
+    },
+)
+
 _RequiredEntityRecognizerAnnotationsTypeDef = TypedDict(
     "_RequiredEntityRecognizerAnnotationsTypeDef",
     {
         "S3Uri": str,
     },
 )
 _OptionalEntityRecognizerAnnotationsTypeDef = TypedDict(
     "_OptionalEntityRecognizerAnnotationsTypeDef",
     {
         "TestS3Uri": str,
     },
     total=False,
 )
 
+
 class EntityRecognizerAnnotationsTypeDef(
     _RequiredEntityRecognizerAnnotationsTypeDef, _OptionalEntityRecognizerAnnotationsTypeDef
 ):
     pass
 
+
 _RequiredEntityRecognizerDocumentsTypeDef = TypedDict(
     "_RequiredEntityRecognizerDocumentsTypeDef",
     {
         "S3Uri": str,
     },
 )
 _OptionalEntityRecognizerDocumentsTypeDef = TypedDict(
@@ -891,19 +1200,21 @@
     {
         "TestS3Uri": str,
         "InputFormat": InputFormatType,
     },
     total=False,
 )
 
+
 class EntityRecognizerDocumentsTypeDef(
     _RequiredEntityRecognizerDocumentsTypeDef, _OptionalEntityRecognizerDocumentsTypeDef
 ):
     pass
 
+
 EntityRecognizerEntityListTypeDef = TypedDict(
     "EntityRecognizerEntityListTypeDef",
     {
         "S3Uri": str,
     },
 )
 
@@ -924,31 +1235,32 @@
         "RecognizerName": str,
         "SubmitTimeBefore": Union[datetime, str],
         "SubmitTimeAfter": Union[datetime, str],
     },
     total=False,
 )
 
-EntityTypesListItemTypeDef = TypedDict(
-    "EntityTypesListItemTypeDef",
-    {
-        "Type": str,
-    },
-)
-
 EntityTypesEvaluationMetricsTypeDef = TypedDict(
     "EntityTypesEvaluationMetricsTypeDef",
     {
         "Precision": float,
         "Recall": float,
         "F1Score": float,
     },
     total=False,
 )
 
+EntityRecognizerOutputDataConfigTypeDef = TypedDict(
+    "EntityRecognizerOutputDataConfigTypeDef",
+    {
+        "FlywheelStatsS3Prefix": str,
+    },
+    total=False,
+)
+
 EntityRecognizerSummaryTypeDef = TypedDict(
     "EntityRecognizerSummaryTypeDef",
     {
         "RecognizerName": str,
         "NumberOfVersions": int,
         "LatestVersionCreatedAt": datetime,
         "LatestVersionName": str,
@@ -964,44 +1276,88 @@
         "JobStatus": JobStatusType,
         "SubmitTimeBefore": Union[datetime, str],
         "SubmitTimeAfter": Union[datetime, str],
     },
     total=False,
 )
 
+FlywheelFilterTypeDef = TypedDict(
+    "FlywheelFilterTypeDef",
+    {
+        "Status": FlywheelStatusType,
+        "CreationTimeAfter": Union[datetime, str],
+        "CreationTimeBefore": Union[datetime, str],
+    },
+    total=False,
+)
+
+FlywheelIterationFilterTypeDef = TypedDict(
+    "FlywheelIterationFilterTypeDef",
+    {
+        "CreationTimeAfter": Union[datetime, str],
+        "CreationTimeBefore": Union[datetime, str],
+    },
+    total=False,
+)
+
+FlywheelModelEvaluationMetricsTypeDef = TypedDict(
+    "FlywheelModelEvaluationMetricsTypeDef",
+    {
+        "AverageF1Score": float,
+        "AveragePrecision": float,
+        "AverageRecall": float,
+        "AverageAccuracy": float,
+    },
+    total=False,
+)
+
+FlywheelSummaryTypeDef = TypedDict(
+    "FlywheelSummaryTypeDef",
+    {
+        "FlywheelArn": str,
+        "ActiveModelArn": str,
+        "DataLakeS3Uri": str,
+        "Status": FlywheelStatusType,
+        "ModelType": ModelTypeType,
+        "Message": str,
+        "CreationTime": datetime,
+        "LastModifiedTime": datetime,
+        "LatestFlywheelIteration": str,
+    },
+    total=False,
+)
+
 PointTypeDef = TypedDict(
     "PointTypeDef",
     {
         "X": float,
         "Y": float,
     },
     total=False,
 )
 
+ImportModelResponseTypeDef = TypedDict(
+    "ImportModelResponseTypeDef",
+    {
+        "ModelArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 KeyPhrasesDetectionJobFilterTypeDef = TypedDict(
     "KeyPhrasesDetectionJobFilterTypeDef",
     {
         "JobName": str,
         "JobStatus": JobStatusType,
         "SubmitTimeBefore": Union[datetime, str],
         "SubmitTimeAfter": Union[datetime, str],
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
 ListDocumentClassifierSummariesRequestRequestTypeDef = TypedDict(
     "ListDocumentClassifierSummariesRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
@@ -1063,14 +1419,24 @@
         "JobStatus": JobStatusType,
         "SubmitTimeBefore": Union[datetime, str],
         "SubmitTimeAfter": Union[datetime, str],
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
 PartOfSpeechTagTypeDef = TypedDict(
     "PartOfSpeechTagTypeDef",
     {
         "Tag": PartOfSpeechTagTypeType,
         "Score": float,
     },
     total=False,
@@ -1086,19 +1452,21 @@
     "_OptionalPiiOutputDataConfigTypeDef",
     {
         "KmsKeyId": str,
     },
     total=False,
 )
 
+
 class PiiOutputDataConfigTypeDef(
     _RequiredPiiOutputDataConfigTypeDef, _OptionalPiiOutputDataConfigTypeDef
 ):
     pass
 
+
 RedactionConfigTypeDef = TypedDict(
     "RedactionConfigTypeDef",
     {
         "PiiEntityTypes": List[PiiEntityTypeType],
         "MaskMode": PiiEntitiesDetectionMaskModeType,
         "MaskCharacter": str,
     },
@@ -1116,341 +1484,343 @@
     "_OptionalPutResourcePolicyRequestRequestTypeDef",
     {
         "PolicyRevisionId": str,
     },
     total=False,
 )
 
+
 class PutResourcePolicyRequestRequestTypeDef(
     _RequiredPutResourcePolicyRequestRequestTypeDef, _OptionalPutResourcePolicyRequestRequestTypeDef
 ):
     pass
 
-StopDominantLanguageDetectionJobRequestRequestTypeDef = TypedDict(
-    "StopDominantLanguageDetectionJobRequestRequestTypeDef",
-    {
-        "JobId": str,
-    },
-)
 
-StopEntitiesDetectionJobRequestRequestTypeDef = TypedDict(
-    "StopEntitiesDetectionJobRequestRequestTypeDef",
+PutResourcePolicyResponseTypeDef = TypedDict(
+    "PutResourcePolicyResponseTypeDef",
     {
-        "JobId": str,
+        "PolicyRevisionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StopEventsDetectionJobRequestRequestTypeDef = TypedDict(
-    "StopEventsDetectionJobRequestRequestTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "JobId": str,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
-StopKeyPhrasesDetectionJobRequestRequestTypeDef = TypedDict(
-    "StopKeyPhrasesDetectionJobRequestRequestTypeDef",
+StartDocumentClassificationJobResponseTypeDef = TypedDict(
+    "StartDocumentClassificationJobResponseTypeDef",
     {
         "JobId": str,
+        "JobArn": str,
+        "JobStatus": JobStatusType,
+        "DocumentClassifierArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StopPiiEntitiesDetectionJobRequestRequestTypeDef = TypedDict(
-    "StopPiiEntitiesDetectionJobRequestRequestTypeDef",
+StartDominantLanguageDetectionJobResponseTypeDef = TypedDict(
+    "StartDominantLanguageDetectionJobResponseTypeDef",
     {
         "JobId": str,
+        "JobArn": str,
+        "JobStatus": JobStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StopSentimentDetectionJobRequestRequestTypeDef = TypedDict(
-    "StopSentimentDetectionJobRequestRequestTypeDef",
+StartEntitiesDetectionJobResponseTypeDef = TypedDict(
+    "StartEntitiesDetectionJobResponseTypeDef",
     {
         "JobId": str,
+        "JobArn": str,
+        "JobStatus": JobStatusType,
+        "EntityRecognizerArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StopTargetedSentimentDetectionJobRequestRequestTypeDef = TypedDict(
-    "StopTargetedSentimentDetectionJobRequestRequestTypeDef",
+StartEventsDetectionJobResponseTypeDef = TypedDict(
+    "StartEventsDetectionJobResponseTypeDef",
     {
         "JobId": str,
+        "JobArn": str,
+        "JobStatus": JobStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StopTrainingDocumentClassifierRequestRequestTypeDef = TypedDict(
-    "StopTrainingDocumentClassifierRequestRequestTypeDef",
+_RequiredStartFlywheelIterationRequestRequestTypeDef = TypedDict(
+    "_RequiredStartFlywheelIterationRequestRequestTypeDef",
     {
-        "DocumentClassifierArn": str,
+        "FlywheelArn": str,
     },
 )
-
-StopTrainingEntityRecognizerRequestRequestTypeDef = TypedDict(
-    "StopTrainingEntityRecognizerRequestRequestTypeDef",
+_OptionalStartFlywheelIterationRequestRequestTypeDef = TypedDict(
+    "_OptionalStartFlywheelIterationRequestRequestTypeDef",
     {
-        "EntityRecognizerArn": str,
+        "ClientRequestToken": str,
     },
+    total=False,
 )
 
-UntagResourceRequestRequestTypeDef = TypedDict(
-    "UntagResourceRequestRequestTypeDef",
-    {
-        "ResourceArn": str,
-        "TagKeys": Sequence[str],
-    },
-)
 
-_RequiredUpdateEndpointRequestRequestTypeDef = TypedDict(
-    "_RequiredUpdateEndpointRequestRequestTypeDef",
+class StartFlywheelIterationRequestRequestTypeDef(
+    _RequiredStartFlywheelIterationRequestRequestTypeDef,
+    _OptionalStartFlywheelIterationRequestRequestTypeDef,
+):
+    pass
+
+
+StartFlywheelIterationResponseTypeDef = TypedDict(
+    "StartFlywheelIterationResponseTypeDef",
     {
-        "EndpointArn": str,
+        "FlywheelArn": str,
+        "FlywheelIterationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalUpdateEndpointRequestRequestTypeDef = TypedDict(
-    "_OptionalUpdateEndpointRequestRequestTypeDef",
+
+StartKeyPhrasesDetectionJobResponseTypeDef = TypedDict(
+    "StartKeyPhrasesDetectionJobResponseTypeDef",
     {
-        "DesiredModelArn": str,
-        "DesiredInferenceUnits": int,
-        "DesiredDataAccessRoleArn": str,
+        "JobId": str,
+        "JobArn": str,
+        "JobStatus": JobStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-class UpdateEndpointRequestRequestTypeDef(
-    _RequiredUpdateEndpointRequestRequestTypeDef, _OptionalUpdateEndpointRequestRequestTypeDef
-):
-    pass
-
-DocumentClassifierInputDataConfigTypeDef = TypedDict(
-    "DocumentClassifierInputDataConfigTypeDef",
+StartPiiEntitiesDetectionJobResponseTypeDef = TypedDict(
+    "StartPiiEntitiesDetectionJobResponseTypeDef",
     {
-        "DataFormat": DocumentClassifierDataFormatType,
-        "S3Uri": str,
-        "TestS3Uri": str,
-        "LabelDelimiter": str,
-        "AugmentedManifests": Sequence[AugmentedManifestsListItemTypeDef],
+        "JobId": str,
+        "JobArn": str,
+        "JobStatus": JobStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-BatchDetectDominantLanguageItemResultTypeDef = TypedDict(
-    "BatchDetectDominantLanguageItemResultTypeDef",
+StartSentimentDetectionJobResponseTypeDef = TypedDict(
+    "StartSentimentDetectionJobResponseTypeDef",
     {
-        "Index": int,
-        "Languages": List[DominantLanguageTypeDef],
+        "JobId": str,
+        "JobArn": str,
+        "JobStatus": JobStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-CreateDocumentClassifierResponseTypeDef = TypedDict(
-    "CreateDocumentClassifierResponseTypeDef",
+StartTargetedSentimentDetectionJobResponseTypeDef = TypedDict(
+    "StartTargetedSentimentDetectionJobResponseTypeDef",
     {
-        "DocumentClassifierArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "JobId": str,
+        "JobArn": str,
+        "JobStatus": JobStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateEndpointResponseTypeDef = TypedDict(
-    "CreateEndpointResponseTypeDef",
+StartTopicsDetectionJobResponseTypeDef = TypedDict(
+    "StartTopicsDetectionJobResponseTypeDef",
     {
-        "EndpointArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "JobId": str,
+        "JobArn": str,
+        "JobStatus": JobStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateEntityRecognizerResponseTypeDef = TypedDict(
-    "CreateEntityRecognizerResponseTypeDef",
+StopDominantLanguageDetectionJobRequestRequestTypeDef = TypedDict(
+    "StopDominantLanguageDetectionJobRequestRequestTypeDef",
     {
-        "EntityRecognizerArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "JobId": str,
     },
 )
 
-DescribeResourcePolicyResponseTypeDef = TypedDict(
-    "DescribeResourcePolicyResponseTypeDef",
+StopDominantLanguageDetectionJobResponseTypeDef = TypedDict(
+    "StopDominantLanguageDetectionJobResponseTypeDef",
     {
-        "ResourcePolicy": str,
-        "CreationTime": datetime,
-        "LastModifiedTime": datetime,
-        "PolicyRevisionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "JobId": str,
+        "JobStatus": JobStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DetectDominantLanguageResponseTypeDef = TypedDict(
-    "DetectDominantLanguageResponseTypeDef",
+StopEntitiesDetectionJobRequestRequestTypeDef = TypedDict(
+    "StopEntitiesDetectionJobRequestRequestTypeDef",
     {
-        "Languages": List[DominantLanguageTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "JobId": str,
     },
 )
 
-ImportModelResponseTypeDef = TypedDict(
-    "ImportModelResponseTypeDef",
+StopEntitiesDetectionJobResponseTypeDef = TypedDict(
+    "StopEntitiesDetectionJobResponseTypeDef",
     {
-        "ModelArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "JobId": str,
+        "JobStatus": JobStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-PutResourcePolicyResponseTypeDef = TypedDict(
-    "PutResourcePolicyResponseTypeDef",
+StopEventsDetectionJobRequestRequestTypeDef = TypedDict(
+    "StopEventsDetectionJobRequestRequestTypeDef",
     {
-        "PolicyRevisionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "JobId": str,
     },
 )
 
-StartDocumentClassificationJobResponseTypeDef = TypedDict(
-    "StartDocumentClassificationJobResponseTypeDef",
+StopEventsDetectionJobResponseTypeDef = TypedDict(
+    "StopEventsDetectionJobResponseTypeDef",
     {
         "JobId": str,
-        "JobArn": str,
         "JobStatus": JobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StartDominantLanguageDetectionJobResponseTypeDef = TypedDict(
-    "StartDominantLanguageDetectionJobResponseTypeDef",
+StopKeyPhrasesDetectionJobRequestRequestTypeDef = TypedDict(
+    "StopKeyPhrasesDetectionJobRequestRequestTypeDef",
     {
         "JobId": str,
-        "JobArn": str,
-        "JobStatus": JobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
 
-StartEntitiesDetectionJobResponseTypeDef = TypedDict(
-    "StartEntitiesDetectionJobResponseTypeDef",
+StopKeyPhrasesDetectionJobResponseTypeDef = TypedDict(
+    "StopKeyPhrasesDetectionJobResponseTypeDef",
     {
         "JobId": str,
-        "JobArn": str,
         "JobStatus": JobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StartEventsDetectionJobResponseTypeDef = TypedDict(
-    "StartEventsDetectionJobResponseTypeDef",
+StopPiiEntitiesDetectionJobRequestRequestTypeDef = TypedDict(
+    "StopPiiEntitiesDetectionJobRequestRequestTypeDef",
     {
         "JobId": str,
-        "JobArn": str,
-        "JobStatus": JobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
 
-StartKeyPhrasesDetectionJobResponseTypeDef = TypedDict(
-    "StartKeyPhrasesDetectionJobResponseTypeDef",
+StopPiiEntitiesDetectionJobResponseTypeDef = TypedDict(
+    "StopPiiEntitiesDetectionJobResponseTypeDef",
     {
         "JobId": str,
-        "JobArn": str,
         "JobStatus": JobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StartPiiEntitiesDetectionJobResponseTypeDef = TypedDict(
-    "StartPiiEntitiesDetectionJobResponseTypeDef",
+StopSentimentDetectionJobRequestRequestTypeDef = TypedDict(
+    "StopSentimentDetectionJobRequestRequestTypeDef",
     {
         "JobId": str,
-        "JobArn": str,
-        "JobStatus": JobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
 
-StartSentimentDetectionJobResponseTypeDef = TypedDict(
-    "StartSentimentDetectionJobResponseTypeDef",
+StopSentimentDetectionJobResponseTypeDef = TypedDict(
+    "StopSentimentDetectionJobResponseTypeDef",
     {
         "JobId": str,
-        "JobArn": str,
         "JobStatus": JobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StartTargetedSentimentDetectionJobResponseTypeDef = TypedDict(
-    "StartTargetedSentimentDetectionJobResponseTypeDef",
+StopTargetedSentimentDetectionJobRequestRequestTypeDef = TypedDict(
+    "StopTargetedSentimentDetectionJobRequestRequestTypeDef",
     {
         "JobId": str,
-        "JobArn": str,
-        "JobStatus": JobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
 
-StartTopicsDetectionJobResponseTypeDef = TypedDict(
-    "StartTopicsDetectionJobResponseTypeDef",
+StopTargetedSentimentDetectionJobResponseTypeDef = TypedDict(
+    "StopTargetedSentimentDetectionJobResponseTypeDef",
     {
         "JobId": str,
-        "JobArn": str,
         "JobStatus": JobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StopDominantLanguageDetectionJobResponseTypeDef = TypedDict(
-    "StopDominantLanguageDetectionJobResponseTypeDef",
+StopTrainingDocumentClassifierRequestRequestTypeDef = TypedDict(
+    "StopTrainingDocumentClassifierRequestRequestTypeDef",
     {
-        "JobId": str,
-        "JobStatus": JobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "DocumentClassifierArn": str,
     },
 )
 
-StopEntitiesDetectionJobResponseTypeDef = TypedDict(
-    "StopEntitiesDetectionJobResponseTypeDef",
+StopTrainingEntityRecognizerRequestRequestTypeDef = TypedDict(
+    "StopTrainingEntityRecognizerRequestRequestTypeDef",
     {
-        "JobId": str,
-        "JobStatus": JobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "EntityRecognizerArn": str,
     },
 )
 
-StopEventsDetectionJobResponseTypeDef = TypedDict(
-    "StopEventsDetectionJobResponseTypeDef",
+UntagResourceRequestRequestTypeDef = TypedDict(
+    "UntagResourceRequestRequestTypeDef",
     {
-        "JobId": str,
-        "JobStatus": JobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResourceArn": str,
+        "TagKeys": Sequence[str],
     },
 )
 
-StopKeyPhrasesDetectionJobResponseTypeDef = TypedDict(
-    "StopKeyPhrasesDetectionJobResponseTypeDef",
+_RequiredUpdateEndpointRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateEndpointRequestRequestTypeDef",
     {
-        "JobId": str,
-        "JobStatus": JobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "EndpointArn": str,
     },
 )
+_OptionalUpdateEndpointRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateEndpointRequestRequestTypeDef",
+    {
+        "DesiredModelArn": str,
+        "DesiredInferenceUnits": int,
+        "DesiredDataAccessRoleArn": str,
+        "FlywheelArn": str,
+    },
+    total=False,
+)
 
-StopPiiEntitiesDetectionJobResponseTypeDef = TypedDict(
-    "StopPiiEntitiesDetectionJobResponseTypeDef",
+
+class UpdateEndpointRequestRequestTypeDef(
+    _RequiredUpdateEndpointRequestRequestTypeDef, _OptionalUpdateEndpointRequestRequestTypeDef
+):
+    pass
+
+
+UpdateEndpointResponseTypeDef = TypedDict(
+    "UpdateEndpointResponseTypeDef",
     {
-        "JobId": str,
-        "JobStatus": JobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "DesiredModelArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StopSentimentDetectionJobResponseTypeDef = TypedDict(
-    "StopSentimentDetectionJobResponseTypeDef",
+BatchDetectDominantLanguageItemResultTypeDef = TypedDict(
+    "BatchDetectDominantLanguageItemResultTypeDef",
     {
-        "JobId": str,
-        "JobStatus": JobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Index": int,
+        "Languages": List[DominantLanguageTypeDef],
     },
+    total=False,
 )
 
-StopTargetedSentimentDetectionJobResponseTypeDef = TypedDict(
-    "StopTargetedSentimentDetectionJobResponseTypeDef",
+DetectDominantLanguageResponseTypeDef = TypedDict(
+    "DetectDominantLanguageResponseTypeDef",
     {
-        "JobId": str,
-        "JobStatus": JobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Languages": List[DominantLanguageTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDetectKeyPhrasesItemResultTypeDef = TypedDict(
     "BatchDetectKeyPhrasesItemResultTypeDef",
     {
         "Index": int,
@@ -1459,15 +1829,15 @@
     total=False,
 )
 
 DetectKeyPhrasesResponseTypeDef = TypedDict(
     "DetectKeyPhrasesResponseTypeDef",
     {
         "KeyPhrases": List[KeyPhraseTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDetectSentimentItemResultTypeDef = TypedDict(
     "BatchDetectSentimentItemResultTypeDef",
     {
         "Index": int,
@@ -1478,15 +1848,15 @@
 )
 
 DetectSentimentResponseTypeDef = TypedDict(
     "DetectSentimentResponseTypeDef",
     {
         "Sentiment": SentimentTypeType,
         "SentimentScore": SentimentScoreTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 MentionSentimentTypeDef = TypedDict(
     "MentionSentimentTypeDef",
     {
         "Sentiment": SentimentTypeType,
@@ -1529,19 +1899,21 @@
         "Text": str,
         "Bytes": Union[str, bytes, IO[Any], StreamingBody],
         "DocumentReaderConfig": DocumentReaderConfigTypeDef,
     },
     total=False,
 )
 
+
 class ClassifyDocumentRequestRequestTypeDef(
     _RequiredClassifyDocumentRequestRequestTypeDef, _OptionalClassifyDocumentRequestRequestTypeDef
 ):
     pass
 
+
 DetectEntitiesRequestRequestTypeDef = TypedDict(
     "DetectEntitiesRequestRequestTypeDef",
     {
         "Text": str,
         "LanguageCode": LanguageCodeType,
         "EndpointArn": str,
         "Bytes": Union[str, bytes, IO[Any], StreamingBody],
@@ -1561,48 +1933,53 @@
     {
         "InputFormat": InputFormatType,
         "DocumentReaderConfig": DocumentReaderConfigTypeDef,
     },
     total=False,
 )
 
+
 class InputDataConfigTypeDef(_RequiredInputDataConfigTypeDef, _OptionalInputDataConfigTypeDef):
     pass
 
+
 ContainsPiiEntitiesResponseTypeDef = TypedDict(
     "ContainsPiiEntitiesResponseTypeDef",
     {
         "Labels": List[EntityLabelTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateEndpointRequestRequestTypeDef = TypedDict(
     "_RequiredCreateEndpointRequestRequestTypeDef",
     {
         "EndpointName": str,
-        "ModelArn": str,
         "DesiredInferenceUnits": int,
     },
 )
 _OptionalCreateEndpointRequestRequestTypeDef = TypedDict(
     "_OptionalCreateEndpointRequestRequestTypeDef",
     {
+        "ModelArn": str,
         "ClientRequestToken": str,
         "Tags": Sequence[TagTypeDef],
         "DataAccessRoleArn": str,
+        "FlywheelArn": str,
     },
     total=False,
 )
 
+
 class CreateEndpointRequestRequestTypeDef(
     _RequiredCreateEndpointRequestRequestTypeDef, _OptionalCreateEndpointRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredImportModelRequestRequestTypeDef = TypedDict(
     "_RequiredImportModelRequestRequestTypeDef",
     {
         "SourceModelArn": str,
     },
 )
 _OptionalImportModelRequestRequestTypeDef = TypedDict(
@@ -1613,71 +1990,178 @@
         "ModelKmsKeyId": str,
         "DataAccessRoleArn": str,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class ImportModelRequestRequestTypeDef(
     _RequiredImportModelRequestRequestTypeDef, _OptionalImportModelRequestRequestTypeDef
 ):
     pass
 
+
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "ResourceArn": str,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "Tags": Sequence[TagTypeDef],
     },
 )
 
+DataSecurityConfigTypeDef = TypedDict(
+    "DataSecurityConfigTypeDef",
+    {
+        "ModelKmsKeyId": str,
+        "VolumeKmsKeyId": str,
+        "DataLakeKmsKeyId": str,
+        "VpcConfig": VpcConfigTypeDef,
+    },
+    total=False,
+)
+
+UpdateDataSecurityConfigTypeDef = TypedDict(
+    "UpdateDataSecurityConfigTypeDef",
+    {
+        "ModelKmsKeyId": str,
+        "VolumeKmsKeyId": str,
+        "VpcConfig": VpcConfigTypeDef,
+    },
+    total=False,
+)
+
+_RequiredDatasetEntityRecognizerInputDataConfigTypeDef = TypedDict(
+    "_RequiredDatasetEntityRecognizerInputDataConfigTypeDef",
+    {
+        "Documents": DatasetEntityRecognizerDocumentsTypeDef,
+    },
+)
+_OptionalDatasetEntityRecognizerInputDataConfigTypeDef = TypedDict(
+    "_OptionalDatasetEntityRecognizerInputDataConfigTypeDef",
+    {
+        "Annotations": DatasetEntityRecognizerAnnotationsTypeDef,
+        "EntityList": DatasetEntityRecognizerEntityListTypeDef,
+    },
+    total=False,
+)
+
+
+class DatasetEntityRecognizerInputDataConfigTypeDef(
+    _RequiredDatasetEntityRecognizerInputDataConfigTypeDef,
+    _OptionalDatasetEntityRecognizerInputDataConfigTypeDef,
+):
+    pass
+
+
+ListDatasetsRequestRequestTypeDef = TypedDict(
+    "ListDatasetsRequestRequestTypeDef",
+    {
+        "FlywheelArn": str,
+        "Filter": DatasetFilterTypeDef,
+        "NextToken": str,
+        "MaxResults": int,
+    },
+    total=False,
+)
+
+DescribeDatasetResponseTypeDef = TypedDict(
+    "DescribeDatasetResponseTypeDef",
+    {
+        "DatasetProperties": DatasetPropertiesTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListDatasetsResponseTypeDef = TypedDict(
+    "ListDatasetsResponseTypeDef",
+    {
+        "DatasetPropertiesList": List[DatasetPropertiesTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeEndpointResponseTypeDef = TypedDict(
     "DescribeEndpointResponseTypeDef",
     {
         "EndpointProperties": EndpointPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEndpointsResponseTypeDef = TypedDict(
     "ListEndpointsResponseTypeDef",
     {
         "EndpointPropertiesList": List[EndpointPropertiesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DetectPiiEntitiesResponseTypeDef = TypedDict(
     "DetectPiiEntitiesResponseTypeDef",
     {
         "Entities": List[PiiEntityTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
+ListDocumentClassificationJobsRequestListDocumentClassificationJobsPaginateTypeDef = TypedDict(
+    "ListDocumentClassificationJobsRequestListDocumentClassificationJobsPaginateTypeDef",
+    {
+        "Filter": DocumentClassificationJobFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDocumentClassificationJobsRequestRequestTypeDef = TypedDict(
     "ListDocumentClassificationJobsRequestRequestTypeDef",
     {
         "Filter": DocumentClassificationJobFilterTypeDef,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+DocumentClassifierInputDataConfigTypeDef = TypedDict(
+    "DocumentClassifierInputDataConfigTypeDef",
+    {
+        "DataFormat": DocumentClassifierDataFormatType,
+        "S3Uri": str,
+        "TestS3Uri": str,
+        "LabelDelimiter": str,
+        "AugmentedManifests": Sequence[AugmentedManifestsListItemTypeDef],
+        "DocumentType": DocumentClassifierDocumentTypeFormatType,
+        "Documents": DocumentClassifierDocumentsTypeDef,
+        "DocumentReaderConfig": DocumentReaderConfigTypeDef,
+    },
+    total=False,
+)
+
+ListDocumentClassifiersRequestListDocumentClassifiersPaginateTypeDef = TypedDict(
+    "ListDocumentClassifiersRequestListDocumentClassifiersPaginateTypeDef",
+    {
+        "Filter": DocumentClassifierFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDocumentClassifiersRequestRequestTypeDef = TypedDict(
     "ListDocumentClassifiersRequestRequestTypeDef",
     {
         "Filter": DocumentClassifierFilterTypeDef,
         "NextToken": str,
         "MaxResults": int,
     },
@@ -1685,65 +2169,91 @@
 )
 
 ListDocumentClassifierSummariesResponseTypeDef = TypedDict(
     "ListDocumentClassifierSummariesResponseTypeDef",
     {
         "DocumentClassifierSummariesList": List[DocumentClassifierSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DocumentMetadataTypeDef = TypedDict(
     "DocumentMetadataTypeDef",
     {
         "Pages": int,
         "ExtractedCharacters": List[ExtractedCharactersListItemTypeDef],
     },
     total=False,
 )
 
+ListDominantLanguageDetectionJobsRequestListDominantLanguageDetectionJobsPaginateTypeDef = (
+    TypedDict(
+        "ListDominantLanguageDetectionJobsRequestListDominantLanguageDetectionJobsPaginateTypeDef",
+        {
+            "Filter": DominantLanguageDetectionJobFilterTypeDef,
+            "PaginationConfig": "PaginatorConfigTypeDef",
+        },
+        total=False,
+    )
+)
+
 ListDominantLanguageDetectionJobsRequestRequestTypeDef = TypedDict(
     "ListDominantLanguageDetectionJobsRequestRequestTypeDef",
     {
         "Filter": DominantLanguageDetectionJobFilterTypeDef,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListEndpointsRequestListEndpointsPaginateTypeDef = TypedDict(
+    "ListEndpointsRequestListEndpointsPaginateTypeDef",
+    {
+        "Filter": EndpointFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListEndpointsRequestRequestTypeDef = TypedDict(
     "ListEndpointsRequestRequestTypeDef",
     {
         "Filter": EndpointFilterTypeDef,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListEntitiesDetectionJobsRequestListEntitiesDetectionJobsPaginateTypeDef = TypedDict(
+    "ListEntitiesDetectionJobsRequestListEntitiesDetectionJobsPaginateTypeDef",
+    {
+        "Filter": EntitiesDetectionJobFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListEntitiesDetectionJobsRequestRequestTypeDef = TypedDict(
     "ListEntitiesDetectionJobsRequestRequestTypeDef",
     {
         "Filter": EntitiesDetectionJobFilterTypeDef,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-ListEntityRecognizersRequestRequestTypeDef = TypedDict(
-    "ListEntityRecognizersRequestRequestTypeDef",
+EntityRecognitionConfigTypeDef = TypedDict(
+    "EntityRecognitionConfigTypeDef",
     {
-        "Filter": EntityRecognizerFilterTypeDef,
-        "NextToken": str,
-        "MaxResults": int,
+        "EntityTypes": Sequence[EntityTypesListItemTypeDef],
     },
-    total=False,
 )
 
 _RequiredEntityRecognizerInputDataConfigTypeDef = TypedDict(
     "_RequiredEntityRecognizerInputDataConfigTypeDef",
     {
         "EntityTypes": Sequence[EntityTypesListItemTypeDef],
     },
@@ -1756,19 +2266,40 @@
         "Annotations": EntityRecognizerAnnotationsTypeDef,
         "EntityList": EntityRecognizerEntityListTypeDef,
         "AugmentedManifests": Sequence[AugmentedManifestsListItemTypeDef],
     },
     total=False,
 )
 
+
 class EntityRecognizerInputDataConfigTypeDef(
     _RequiredEntityRecognizerInputDataConfigTypeDef, _OptionalEntityRecognizerInputDataConfigTypeDef
 ):
     pass
 
+
+ListEntityRecognizersRequestListEntityRecognizersPaginateTypeDef = TypedDict(
+    "ListEntityRecognizersRequestListEntityRecognizersPaginateTypeDef",
+    {
+        "Filter": EntityRecognizerFilterTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+ListEntityRecognizersRequestRequestTypeDef = TypedDict(
+    "ListEntityRecognizersRequestRequestTypeDef",
+    {
+        "Filter": EntityRecognizerFilterTypeDef,
+        "NextToken": str,
+        "MaxResults": int,
+    },
+    total=False,
+)
+
 EntityRecognizerMetadataEntityTypesListItemTypeDef = TypedDict(
     "EntityRecognizerMetadataEntityTypesListItemTypeDef",
     {
         "Type": str,
         "EvaluationMetrics": EntityTypesEvaluationMetricsTypeDef,
         "NumberOfTrainMentions": int,
     },
@@ -1776,117 +2307,122 @@
 )
 
 ListEntityRecognizerSummariesResponseTypeDef = TypedDict(
     "ListEntityRecognizerSummariesResponseTypeDef",
     {
         "EntityRecognizerSummariesList": List[EntityRecognizerSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEventsDetectionJobsRequestRequestTypeDef = TypedDict(
     "ListEventsDetectionJobsRequestRequestTypeDef",
     {
         "Filter": EventsDetectionJobFilterTypeDef,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-GeometryTypeDef = TypedDict(
-    "GeometryTypeDef",
+ListFlywheelsRequestRequestTypeDef = TypedDict(
+    "ListFlywheelsRequestRequestTypeDef",
     {
-        "BoundingBox": BoundingBoxTypeDef,
-        "Polygon": List[PointTypeDef],
-    },
-    total=False,
-)
-
-ListKeyPhrasesDetectionJobsRequestRequestTypeDef = TypedDict(
-    "ListKeyPhrasesDetectionJobsRequestRequestTypeDef",
-    {
-        "Filter": KeyPhrasesDetectionJobFilterTypeDef,
+        "Filter": FlywheelFilterTypeDef,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-ListDocumentClassificationJobsRequestListDocumentClassificationJobsPaginateTypeDef = TypedDict(
-    "ListDocumentClassificationJobsRequestListDocumentClassificationJobsPaginateTypeDef",
+_RequiredListFlywheelIterationHistoryRequestRequestTypeDef = TypedDict(
+    "_RequiredListFlywheelIterationHistoryRequestRequestTypeDef",
     {
-        "Filter": DocumentClassificationJobFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "FlywheelArn": str,
     },
-    total=False,
 )
-
-ListDocumentClassifiersRequestListDocumentClassifiersPaginateTypeDef = TypedDict(
-    "ListDocumentClassifiersRequestListDocumentClassifiersPaginateTypeDef",
+_OptionalListFlywheelIterationHistoryRequestRequestTypeDef = TypedDict(
+    "_OptionalListFlywheelIterationHistoryRequestRequestTypeDef",
     {
-        "Filter": DocumentClassifierFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "Filter": FlywheelIterationFilterTypeDef,
+        "NextToken": str,
+        "MaxResults": int,
     },
     total=False,
 )
 
-ListDominantLanguageDetectionJobsRequestListDominantLanguageDetectionJobsPaginateTypeDef = (
-    TypedDict(
-        "ListDominantLanguageDetectionJobsRequestListDominantLanguageDetectionJobsPaginateTypeDef",
-        {
-            "Filter": DominantLanguageDetectionJobFilterTypeDef,
-            "PaginationConfig": PaginatorConfigTypeDef,
-        },
-        total=False,
-    )
-)
 
-ListEndpointsRequestListEndpointsPaginateTypeDef = TypedDict(
-    "ListEndpointsRequestListEndpointsPaginateTypeDef",
+class ListFlywheelIterationHistoryRequestRequestTypeDef(
+    _RequiredListFlywheelIterationHistoryRequestRequestTypeDef,
+    _OptionalListFlywheelIterationHistoryRequestRequestTypeDef,
+):
+    pass
+
+
+FlywheelIterationPropertiesTypeDef = TypedDict(
+    "FlywheelIterationPropertiesTypeDef",
     {
-        "Filter": EndpointFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "FlywheelArn": str,
+        "FlywheelIterationId": str,
+        "CreationTime": datetime,
+        "EndTime": datetime,
+        "Status": FlywheelIterationStatusType,
+        "Message": str,
+        "EvaluatedModelArn": str,
+        "EvaluatedModelMetrics": FlywheelModelEvaluationMetricsTypeDef,
+        "TrainedModelArn": str,
+        "TrainedModelMetrics": FlywheelModelEvaluationMetricsTypeDef,
+        "EvaluationManifestS3Prefix": str,
     },
     total=False,
 )
 
-ListEntitiesDetectionJobsRequestListEntitiesDetectionJobsPaginateTypeDef = TypedDict(
-    "ListEntitiesDetectionJobsRequestListEntitiesDetectionJobsPaginateTypeDef",
+ListFlywheelsResponseTypeDef = TypedDict(
+    "ListFlywheelsResponseTypeDef",
     {
-        "Filter": EntitiesDetectionJobFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "FlywheelSummaryList": List[FlywheelSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-ListEntityRecognizersRequestListEntityRecognizersPaginateTypeDef = TypedDict(
-    "ListEntityRecognizersRequestListEntityRecognizersPaginateTypeDef",
+GeometryTypeDef = TypedDict(
+    "GeometryTypeDef",
     {
-        "Filter": EntityRecognizerFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "BoundingBox": BoundingBoxTypeDef,
+        "Polygon": List[PointTypeDef],
     },
     total=False,
 )
 
 ListKeyPhrasesDetectionJobsRequestListKeyPhrasesDetectionJobsPaginateTypeDef = TypedDict(
     "ListKeyPhrasesDetectionJobsRequestListKeyPhrasesDetectionJobsPaginateTypeDef",
     {
         "Filter": KeyPhrasesDetectionJobFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+ListKeyPhrasesDetectionJobsRequestRequestTypeDef = TypedDict(
+    "ListKeyPhrasesDetectionJobsRequestRequestTypeDef",
+    {
+        "Filter": KeyPhrasesDetectionJobFilterTypeDef,
+        "NextToken": str,
+        "MaxResults": int,
     },
     total=False,
 )
 
 ListPiiEntitiesDetectionJobsRequestListPiiEntitiesDetectionJobsPaginateTypeDef = TypedDict(
     "ListPiiEntitiesDetectionJobsRequestListPiiEntitiesDetectionJobsPaginateTypeDef",
     {
         "Filter": PiiEntitiesDetectionJobFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListPiiEntitiesDetectionJobsRequestRequestTypeDef = TypedDict(
     "ListPiiEntitiesDetectionJobsRequestRequestTypeDef",
     {
@@ -1897,15 +2433,15 @@
     total=False,
 )
 
 ListSentimentDetectionJobsRequestListSentimentDetectionJobsPaginateTypeDef = TypedDict(
     "ListSentimentDetectionJobsRequestListSentimentDetectionJobsPaginateTypeDef",
     {
         "Filter": SentimentDetectionJobFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListSentimentDetectionJobsRequestRequestTypeDef = TypedDict(
     "ListSentimentDetectionJobsRequestRequestTypeDef",
     {
@@ -1926,15 +2462,15 @@
     total=False,
 )
 
 ListTopicsDetectionJobsRequestListTopicsDetectionJobsPaginateTypeDef = TypedDict(
     "ListTopicsDetectionJobsRequestListTopicsDetectionJobsPaginateTypeDef",
     {
         "Filter": TopicsDetectionJobFilterTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListTopicsDetectionJobsRequestRequestTypeDef = TypedDict(
     "ListTopicsDetectionJobsRequestRequestTypeDef",
     {
@@ -1953,69 +2489,38 @@
         "BeginOffset": int,
         "EndOffset": int,
         "PartOfSpeech": PartOfSpeechTagTypeDef,
     },
     total=False,
 )
 
-_RequiredCreateDocumentClassifierRequestRequestTypeDef = TypedDict(
-    "_RequiredCreateDocumentClassifierRequestRequestTypeDef",
-    {
-        "DocumentClassifierName": str,
-        "DataAccessRoleArn": str,
-        "InputDataConfig": DocumentClassifierInputDataConfigTypeDef,
-        "LanguageCode": LanguageCodeType,
-    },
-)
-_OptionalCreateDocumentClassifierRequestRequestTypeDef = TypedDict(
-    "_OptionalCreateDocumentClassifierRequestRequestTypeDef",
-    {
-        "VersionName": str,
-        "Tags": Sequence[TagTypeDef],
-        "OutputDataConfig": DocumentClassifierOutputDataConfigTypeDef,
-        "ClientRequestToken": str,
-        "VolumeKmsKeyId": str,
-        "VpcConfig": VpcConfigTypeDef,
-        "Mode": DocumentClassifierModeType,
-        "ModelKmsKeyId": str,
-        "ModelPolicy": str,
-    },
-    total=False,
-)
-
-class CreateDocumentClassifierRequestRequestTypeDef(
-    _RequiredCreateDocumentClassifierRequestRequestTypeDef,
-    _OptionalCreateDocumentClassifierRequestRequestTypeDef,
-):
-    pass
-
 BatchDetectDominantLanguageResponseTypeDef = TypedDict(
     "BatchDetectDominantLanguageResponseTypeDef",
     {
         "ResultList": List[BatchDetectDominantLanguageItemResultTypeDef],
         "ErrorList": List[BatchItemErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDetectKeyPhrasesResponseTypeDef = TypedDict(
     "BatchDetectKeyPhrasesResponseTypeDef",
     {
         "ResultList": List[BatchDetectKeyPhrasesItemResultTypeDef],
         "ErrorList": List[BatchItemErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDetectSentimentResponseTypeDef = TypedDict(
     "BatchDetectSentimentResponseTypeDef",
     {
         "ResultList": List[BatchDetectSentimentItemResultTypeDef],
         "ErrorList": List[BatchItemErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TargetedSentimentMentionTypeDef = TypedDict(
     "TargetedSentimentMentionTypeDef",
     {
         "Score": float,
@@ -2038,39 +2543,14 @@
         "BeginOffset": int,
         "EndOffset": int,
         "BlockReferences": List[BlockReferenceTypeDef],
     },
     total=False,
 )
 
-DocumentClassifierPropertiesTypeDef = TypedDict(
-    "DocumentClassifierPropertiesTypeDef",
-    {
-        "DocumentClassifierArn": str,
-        "LanguageCode": LanguageCodeType,
-        "Status": ModelStatusType,
-        "Message": str,
-        "SubmitTime": datetime,
-        "EndTime": datetime,
-        "TrainingStartTime": datetime,
-        "TrainingEndTime": datetime,
-        "InputDataConfig": DocumentClassifierInputDataConfigTypeDef,
-        "OutputDataConfig": DocumentClassifierOutputDataConfigTypeDef,
-        "ClassifierMetadata": ClassifierMetadataTypeDef,
-        "DataAccessRoleArn": str,
-        "VolumeKmsKeyId": str,
-        "VpcConfig": VpcConfigTypeDef,
-        "Mode": DocumentClassifierModeType,
-        "ModelKmsKeyId": str,
-        "VersionName": str,
-        "SourceModelArn": str,
-    },
-    total=False,
-)
-
 DocumentClassificationJobPropertiesTypeDef = TypedDict(
     "DocumentClassificationJobPropertiesTypeDef",
     {
         "JobId": str,
         "JobArn": str,
         "JobName": str,
         "JobStatus": JobStatusType,
@@ -2079,14 +2559,15 @@
         "EndTime": datetime,
         "DocumentClassifierArn": str,
         "InputDataConfig": InputDataConfigTypeDef,
         "OutputDataConfig": OutputDataConfigTypeDef,
         "DataAccessRoleArn": str,
         "VolumeKmsKeyId": str,
         "VpcConfig": VpcConfigTypeDef,
+        "FlywheelArn": str,
     },
     total=False,
 )
 
 DominantLanguageDetectionJobPropertiesTypeDef = TypedDict(
     "DominantLanguageDetectionJobPropertiesTypeDef",
     {
@@ -2119,14 +2600,15 @@
         "EntityRecognizerArn": str,
         "InputDataConfig": InputDataConfigTypeDef,
         "OutputDataConfig": OutputDataConfigTypeDef,
         "LanguageCode": LanguageCodeType,
         "DataAccessRoleArn": str,
         "VolumeKmsKeyId": str,
         "VpcConfig": VpcConfigTypeDef,
+        "FlywheelArn": str,
     },
     total=False,
 )
 
 EventsDetectionJobPropertiesTypeDef = TypedDict(
     "EventsDetectionJobPropertiesTypeDef",
     {
@@ -2205,38 +2687,41 @@
     },
     total=False,
 )
 
 _RequiredStartDocumentClassificationJobRequestRequestTypeDef = TypedDict(
     "_RequiredStartDocumentClassificationJobRequestRequestTypeDef",
     {
-        "DocumentClassifierArn": str,
         "InputDataConfig": InputDataConfigTypeDef,
         "OutputDataConfig": OutputDataConfigTypeDef,
         "DataAccessRoleArn": str,
     },
 )
 _OptionalStartDocumentClassificationJobRequestRequestTypeDef = TypedDict(
     "_OptionalStartDocumentClassificationJobRequestRequestTypeDef",
     {
         "JobName": str,
+        "DocumentClassifierArn": str,
         "ClientRequestToken": str,
         "VolumeKmsKeyId": str,
         "VpcConfig": VpcConfigTypeDef,
         "Tags": Sequence[TagTypeDef],
+        "FlywheelArn": str,
     },
     total=False,
 )
 
+
 class StartDocumentClassificationJobRequestRequestTypeDef(
     _RequiredStartDocumentClassificationJobRequestRequestTypeDef,
     _OptionalStartDocumentClassificationJobRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredStartDominantLanguageDetectionJobRequestRequestTypeDef = TypedDict(
     "_RequiredStartDominantLanguageDetectionJobRequestRequestTypeDef",
     {
         "InputDataConfig": InputDataConfigTypeDef,
         "OutputDataConfig": OutputDataConfigTypeDef,
         "DataAccessRoleArn": str,
     },
@@ -2249,20 +2734,22 @@
         "VolumeKmsKeyId": str,
         "VpcConfig": VpcConfigTypeDef,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class StartDominantLanguageDetectionJobRequestRequestTypeDef(
     _RequiredStartDominantLanguageDetectionJobRequestRequestTypeDef,
     _OptionalStartDominantLanguageDetectionJobRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredStartEntitiesDetectionJobRequestRequestTypeDef = TypedDict(
     "_RequiredStartEntitiesDetectionJobRequestRequestTypeDef",
     {
         "InputDataConfig": InputDataConfigTypeDef,
         "OutputDataConfig": OutputDataConfigTypeDef,
         "DataAccessRoleArn": str,
         "LanguageCode": LanguageCodeType,
@@ -2273,24 +2760,27 @@
     {
         "JobName": str,
         "EntityRecognizerArn": str,
         "ClientRequestToken": str,
         "VolumeKmsKeyId": str,
         "VpcConfig": VpcConfigTypeDef,
         "Tags": Sequence[TagTypeDef],
+        "FlywheelArn": str,
     },
     total=False,
 )
 
+
 class StartEntitiesDetectionJobRequestRequestTypeDef(
     _RequiredStartEntitiesDetectionJobRequestRequestTypeDef,
     _OptionalStartEntitiesDetectionJobRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredStartEventsDetectionJobRequestRequestTypeDef = TypedDict(
     "_RequiredStartEventsDetectionJobRequestRequestTypeDef",
     {
         "InputDataConfig": InputDataConfigTypeDef,
         "OutputDataConfig": OutputDataConfigTypeDef,
         "DataAccessRoleArn": str,
         "LanguageCode": LanguageCodeType,
@@ -2303,20 +2793,22 @@
         "JobName": str,
         "ClientRequestToken": str,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class StartEventsDetectionJobRequestRequestTypeDef(
     _RequiredStartEventsDetectionJobRequestRequestTypeDef,
     _OptionalStartEventsDetectionJobRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredStartKeyPhrasesDetectionJobRequestRequestTypeDef = TypedDict(
     "_RequiredStartKeyPhrasesDetectionJobRequestRequestTypeDef",
     {
         "InputDataConfig": InputDataConfigTypeDef,
         "OutputDataConfig": OutputDataConfigTypeDef,
         "DataAccessRoleArn": str,
         "LanguageCode": LanguageCodeType,
@@ -2330,20 +2822,22 @@
         "VolumeKmsKeyId": str,
         "VpcConfig": VpcConfigTypeDef,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class StartKeyPhrasesDetectionJobRequestRequestTypeDef(
     _RequiredStartKeyPhrasesDetectionJobRequestRequestTypeDef,
     _OptionalStartKeyPhrasesDetectionJobRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredStartPiiEntitiesDetectionJobRequestRequestTypeDef = TypedDict(
     "_RequiredStartPiiEntitiesDetectionJobRequestRequestTypeDef",
     {
         "InputDataConfig": InputDataConfigTypeDef,
         "OutputDataConfig": OutputDataConfigTypeDef,
         "Mode": PiiEntitiesDetectionModeType,
         "DataAccessRoleArn": str,
@@ -2357,20 +2851,22 @@
         "JobName": str,
         "ClientRequestToken": str,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class StartPiiEntitiesDetectionJobRequestRequestTypeDef(
     _RequiredStartPiiEntitiesDetectionJobRequestRequestTypeDef,
     _OptionalStartPiiEntitiesDetectionJobRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredStartSentimentDetectionJobRequestRequestTypeDef = TypedDict(
     "_RequiredStartSentimentDetectionJobRequestRequestTypeDef",
     {
         "InputDataConfig": InputDataConfigTypeDef,
         "OutputDataConfig": OutputDataConfigTypeDef,
         "DataAccessRoleArn": str,
         "LanguageCode": LanguageCodeType,
@@ -2384,20 +2880,22 @@
         "VolumeKmsKeyId": str,
         "VpcConfig": VpcConfigTypeDef,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class StartSentimentDetectionJobRequestRequestTypeDef(
     _RequiredStartSentimentDetectionJobRequestRequestTypeDef,
     _OptionalStartSentimentDetectionJobRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredStartTargetedSentimentDetectionJobRequestRequestTypeDef = TypedDict(
     "_RequiredStartTargetedSentimentDetectionJobRequestRequestTypeDef",
     {
         "InputDataConfig": InputDataConfigTypeDef,
         "OutputDataConfig": OutputDataConfigTypeDef,
         "DataAccessRoleArn": str,
         "LanguageCode": LanguageCodeType,
@@ -2411,20 +2909,22 @@
         "VolumeKmsKeyId": str,
         "VpcConfig": VpcConfigTypeDef,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class StartTargetedSentimentDetectionJobRequestRequestTypeDef(
     _RequiredStartTargetedSentimentDetectionJobRequestRequestTypeDef,
     _OptionalStartTargetedSentimentDetectionJobRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredStartTopicsDetectionJobRequestRequestTypeDef = TypedDict(
     "_RequiredStartTopicsDetectionJobRequestRequestTypeDef",
     {
         "InputDataConfig": InputDataConfigTypeDef,
         "OutputDataConfig": OutputDataConfigTypeDef,
         "DataAccessRoleArn": str,
     },
@@ -2438,20 +2938,22 @@
         "VolumeKmsKeyId": str,
         "VpcConfig": VpcConfigTypeDef,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class StartTopicsDetectionJobRequestRequestTypeDef(
     _RequiredStartTopicsDetectionJobRequestRequestTypeDef,
     _OptionalStartTopicsDetectionJobRequestRequestTypeDef,
 ):
     pass
 
+
 TargetedSentimentDetectionJobPropertiesTypeDef = TypedDict(
     "TargetedSentimentDetectionJobPropertiesTypeDef",
     {
         "JobId": str,
         "JobArn": str,
         "JobName": str,
         "JobStatus": JobStatusType,
@@ -2484,25 +2986,139 @@
         "DataAccessRoleArn": str,
         "VolumeKmsKeyId": str,
         "VpcConfig": VpcConfigTypeDef,
     },
     total=False,
 )
 
+_RequiredUpdateFlywheelRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateFlywheelRequestRequestTypeDef",
+    {
+        "FlywheelArn": str,
+    },
+)
+_OptionalUpdateFlywheelRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateFlywheelRequestRequestTypeDef",
+    {
+        "ActiveModelArn": str,
+        "DataAccessRoleArn": str,
+        "DataSecurityConfig": UpdateDataSecurityConfigTypeDef,
+    },
+    total=False,
+)
+
+
+class UpdateFlywheelRequestRequestTypeDef(
+    _RequiredUpdateFlywheelRequestRequestTypeDef, _OptionalUpdateFlywheelRequestRequestTypeDef
+):
+    pass
+
+
+DatasetInputDataConfigTypeDef = TypedDict(
+    "DatasetInputDataConfigTypeDef",
+    {
+        "AugmentedManifests": Sequence[DatasetAugmentedManifestsListItemTypeDef],
+        "DataFormat": DatasetDataFormatType,
+        "DocumentClassifierInputDataConfig": DatasetDocumentClassifierInputDataConfigTypeDef,
+        "EntityRecognizerInputDataConfig": DatasetEntityRecognizerInputDataConfigTypeDef,
+    },
+    total=False,
+)
+
+_RequiredCreateDocumentClassifierRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateDocumentClassifierRequestRequestTypeDef",
+    {
+        "DocumentClassifierName": str,
+        "DataAccessRoleArn": str,
+        "InputDataConfig": DocumentClassifierInputDataConfigTypeDef,
+        "LanguageCode": LanguageCodeType,
+    },
+)
+_OptionalCreateDocumentClassifierRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateDocumentClassifierRequestRequestTypeDef",
+    {
+        "VersionName": str,
+        "Tags": Sequence[TagTypeDef],
+        "OutputDataConfig": DocumentClassifierOutputDataConfigTypeDef,
+        "ClientRequestToken": str,
+        "VolumeKmsKeyId": str,
+        "VpcConfig": VpcConfigTypeDef,
+        "Mode": DocumentClassifierModeType,
+        "ModelKmsKeyId": str,
+        "ModelPolicy": str,
+    },
+    total=False,
+)
+
+
+class CreateDocumentClassifierRequestRequestTypeDef(
+    _RequiredCreateDocumentClassifierRequestRequestTypeDef,
+    _OptionalCreateDocumentClassifierRequestRequestTypeDef,
+):
+    pass
+
+
+DocumentClassifierPropertiesTypeDef = TypedDict(
+    "DocumentClassifierPropertiesTypeDef",
+    {
+        "DocumentClassifierArn": str,
+        "LanguageCode": LanguageCodeType,
+        "Status": ModelStatusType,
+        "Message": str,
+        "SubmitTime": datetime,
+        "EndTime": datetime,
+        "TrainingStartTime": datetime,
+        "TrainingEndTime": datetime,
+        "InputDataConfig": DocumentClassifierInputDataConfigTypeDef,
+        "OutputDataConfig": DocumentClassifierOutputDataConfigTypeDef,
+        "ClassifierMetadata": ClassifierMetadataTypeDef,
+        "DataAccessRoleArn": str,
+        "VolumeKmsKeyId": str,
+        "VpcConfig": VpcConfigTypeDef,
+        "Mode": DocumentClassifierModeType,
+        "ModelKmsKeyId": str,
+        "VersionName": str,
+        "SourceModelArn": str,
+        "FlywheelArn": str,
+    },
+    total=False,
+)
+
 ClassifyDocumentResponseTypeDef = TypedDict(
     "ClassifyDocumentResponseTypeDef",
     {
         "Classes": List[DocumentClassTypeDef],
         "Labels": List[DocumentLabelTypeDef],
         "DocumentMetadata": DocumentMetadataTypeDef,
         "DocumentType": List[DocumentTypeListItemTypeDef],
         "Errors": List[ErrorsListItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Warnings": List[WarningsListItemTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredTaskConfigTypeDef = TypedDict(
+    "_RequiredTaskConfigTypeDef",
+    {
+        "LanguageCode": LanguageCodeType,
     },
 )
+_OptionalTaskConfigTypeDef = TypedDict(
+    "_OptionalTaskConfigTypeDef",
+    {
+        "DocumentClassificationConfig": DocumentClassificationConfigTypeDef,
+        "EntityRecognitionConfig": EntityRecognitionConfigTypeDef,
+    },
+    total=False,
+)
+
+
+class TaskConfigTypeDef(_RequiredTaskConfigTypeDef, _OptionalTaskConfigTypeDef):
+    pass
+
 
 _RequiredCreateEntityRecognizerRequestRequestTypeDef = TypedDict(
     "_RequiredCreateEntityRecognizerRequestRequestTypeDef",
     {
         "RecognizerName": str,
         "DataAccessRoleArn": str,
         "InputDataConfig": EntityRecognizerInputDataConfigTypeDef,
@@ -2519,31 +3135,50 @@
         "VpcConfig": VpcConfigTypeDef,
         "ModelKmsKeyId": str,
         "ModelPolicy": str,
     },
     total=False,
 )
 
+
 class CreateEntityRecognizerRequestRequestTypeDef(
     _RequiredCreateEntityRecognizerRequestRequestTypeDef,
     _OptionalCreateEntityRecognizerRequestRequestTypeDef,
 ):
     pass
 
+
 EntityRecognizerMetadataTypeDef = TypedDict(
     "EntityRecognizerMetadataTypeDef",
     {
         "NumberOfTrainedDocuments": int,
         "NumberOfTestDocuments": int,
         "EvaluationMetrics": EntityRecognizerEvaluationMetricsTypeDef,
         "EntityTypes": List[EntityRecognizerMetadataEntityTypesListItemTypeDef],
     },
     total=False,
 )
 
+DescribeFlywheelIterationResponseTypeDef = TypedDict(
+    "DescribeFlywheelIterationResponseTypeDef",
+    {
+        "FlywheelIterationProperties": FlywheelIterationPropertiesTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListFlywheelIterationHistoryResponseTypeDef = TypedDict(
+    "ListFlywheelIterationHistoryResponseTypeDef",
+    {
+        "FlywheelIterationPropertiesList": List[FlywheelIterationPropertiesTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 BlockTypeDef = TypedDict(
     "BlockTypeDef",
     {
         "Id": str,
         "BlockType": BlockTypeType,
         "Text": str,
         "Page": int,
@@ -2562,15 +3197,15 @@
     total=False,
 )
 
 DetectSyntaxResponseTypeDef = TypedDict(
     "DetectSyntaxResponseTypeDef",
     {
         "SyntaxTokens": List[SyntaxTokenTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TargetedSentimentEntityTypeDef = TypedDict(
     "TargetedSentimentEntityTypeDef",
     {
         "DescriptiveMentionIndex": List[int],
@@ -2584,188 +3219,261 @@
     {
         "Index": int,
         "Entities": List[EntityTypeDef],
     },
     total=False,
 )
 
-DescribeDocumentClassifierResponseTypeDef = TypedDict(
-    "DescribeDocumentClassifierResponseTypeDef",
-    {
-        "DocumentClassifierProperties": DocumentClassifierPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDocumentClassifiersResponseTypeDef = TypedDict(
-    "ListDocumentClassifiersResponseTypeDef",
-    {
-        "DocumentClassifierPropertiesList": List[DocumentClassifierPropertiesTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 DescribeDocumentClassificationJobResponseTypeDef = TypedDict(
     "DescribeDocumentClassificationJobResponseTypeDef",
     {
         "DocumentClassificationJobProperties": DocumentClassificationJobPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDocumentClassificationJobsResponseTypeDef = TypedDict(
     "ListDocumentClassificationJobsResponseTypeDef",
     {
         "DocumentClassificationJobPropertiesList": List[DocumentClassificationJobPropertiesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDominantLanguageDetectionJobResponseTypeDef = TypedDict(
     "DescribeDominantLanguageDetectionJobResponseTypeDef",
     {
         "DominantLanguageDetectionJobProperties": DominantLanguageDetectionJobPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDominantLanguageDetectionJobsResponseTypeDef = TypedDict(
     "ListDominantLanguageDetectionJobsResponseTypeDef",
     {
         "DominantLanguageDetectionJobPropertiesList": List[
             DominantLanguageDetectionJobPropertiesTypeDef
         ],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEntitiesDetectionJobResponseTypeDef = TypedDict(
     "DescribeEntitiesDetectionJobResponseTypeDef",
     {
         "EntitiesDetectionJobProperties": EntitiesDetectionJobPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEntitiesDetectionJobsResponseTypeDef = TypedDict(
     "ListEntitiesDetectionJobsResponseTypeDef",
     {
         "EntitiesDetectionJobPropertiesList": List[EntitiesDetectionJobPropertiesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEventsDetectionJobResponseTypeDef = TypedDict(
     "DescribeEventsDetectionJobResponseTypeDef",
     {
         "EventsDetectionJobProperties": EventsDetectionJobPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEventsDetectionJobsResponseTypeDef = TypedDict(
     "ListEventsDetectionJobsResponseTypeDef",
     {
         "EventsDetectionJobPropertiesList": List[EventsDetectionJobPropertiesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeKeyPhrasesDetectionJobResponseTypeDef = TypedDict(
     "DescribeKeyPhrasesDetectionJobResponseTypeDef",
     {
         "KeyPhrasesDetectionJobProperties": KeyPhrasesDetectionJobPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListKeyPhrasesDetectionJobsResponseTypeDef = TypedDict(
     "ListKeyPhrasesDetectionJobsResponseTypeDef",
     {
         "KeyPhrasesDetectionJobPropertiesList": List[KeyPhrasesDetectionJobPropertiesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribePiiEntitiesDetectionJobResponseTypeDef = TypedDict(
     "DescribePiiEntitiesDetectionJobResponseTypeDef",
     {
         "PiiEntitiesDetectionJobProperties": PiiEntitiesDetectionJobPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPiiEntitiesDetectionJobsResponseTypeDef = TypedDict(
     "ListPiiEntitiesDetectionJobsResponseTypeDef",
     {
         "PiiEntitiesDetectionJobPropertiesList": List[PiiEntitiesDetectionJobPropertiesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSentimentDetectionJobResponseTypeDef = TypedDict(
     "DescribeSentimentDetectionJobResponseTypeDef",
     {
         "SentimentDetectionJobProperties": SentimentDetectionJobPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSentimentDetectionJobsResponseTypeDef = TypedDict(
     "ListSentimentDetectionJobsResponseTypeDef",
     {
         "SentimentDetectionJobPropertiesList": List[SentimentDetectionJobPropertiesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeTargetedSentimentDetectionJobResponseTypeDef = TypedDict(
     "DescribeTargetedSentimentDetectionJobResponseTypeDef",
     {
         "TargetedSentimentDetectionJobProperties": TargetedSentimentDetectionJobPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTargetedSentimentDetectionJobsResponseTypeDef = TypedDict(
     "ListTargetedSentimentDetectionJobsResponseTypeDef",
     {
         "TargetedSentimentDetectionJobPropertiesList": List[
             TargetedSentimentDetectionJobPropertiesTypeDef
         ],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeTopicsDetectionJobResponseTypeDef = TypedDict(
     "DescribeTopicsDetectionJobResponseTypeDef",
     {
         "TopicsDetectionJobProperties": TopicsDetectionJobPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTopicsDetectionJobsResponseTypeDef = TypedDict(
     "ListTopicsDetectionJobsResponseTypeDef",
     {
         "TopicsDetectionJobPropertiesList": List[TopicsDetectionJobPropertiesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredCreateDatasetRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateDatasetRequestRequestTypeDef",
+    {
+        "FlywheelArn": str,
+        "DatasetName": str,
+        "InputDataConfig": DatasetInputDataConfigTypeDef,
+    },
+)
+_OptionalCreateDatasetRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateDatasetRequestRequestTypeDef",
+    {
+        "DatasetType": DatasetTypeType,
+        "Description": str,
+        "ClientRequestToken": str,
+        "Tags": Sequence[TagTypeDef],
+    },
+    total=False,
+)
+
+
+class CreateDatasetRequestRequestTypeDef(
+    _RequiredCreateDatasetRequestRequestTypeDef, _OptionalCreateDatasetRequestRequestTypeDef
+):
+    pass
+
+
+DescribeDocumentClassifierResponseTypeDef = TypedDict(
+    "DescribeDocumentClassifierResponseTypeDef",
+    {
+        "DocumentClassifierProperties": DocumentClassifierPropertiesTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListDocumentClassifiersResponseTypeDef = TypedDict(
+    "ListDocumentClassifiersResponseTypeDef",
+    {
+        "DocumentClassifierPropertiesList": List[DocumentClassifierPropertiesTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
+_RequiredCreateFlywheelRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateFlywheelRequestRequestTypeDef",
+    {
+        "FlywheelName": str,
+        "DataAccessRoleArn": str,
+        "DataLakeS3Uri": str,
+    },
+)
+_OptionalCreateFlywheelRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateFlywheelRequestRequestTypeDef",
+    {
+        "ActiveModelArn": str,
+        "TaskConfig": TaskConfigTypeDef,
+        "ModelType": ModelTypeType,
+        "DataSecurityConfig": DataSecurityConfigTypeDef,
+        "ClientRequestToken": str,
+        "Tags": Sequence[TagTypeDef],
+    },
+    total=False,
+)
+
+
+class CreateFlywheelRequestRequestTypeDef(
+    _RequiredCreateFlywheelRequestRequestTypeDef, _OptionalCreateFlywheelRequestRequestTypeDef
+):
+    pass
+
+
+FlywheelPropertiesTypeDef = TypedDict(
+    "FlywheelPropertiesTypeDef",
+    {
+        "FlywheelArn": str,
+        "ActiveModelArn": str,
+        "DataAccessRoleArn": str,
+        "TaskConfig": TaskConfigTypeDef,
+        "DataLakeS3Uri": str,
+        "DataSecurityConfig": DataSecurityConfigTypeDef,
+        "Status": FlywheelStatusType,
+        "ModelType": ModelTypeType,
+        "Message": str,
+        "CreationTime": datetime,
+        "LastModifiedTime": datetime,
+        "LatestFlywheelIteration": str,
+    },
+    total=False,
+)
+
 EntityRecognizerPropertiesTypeDef = TypedDict(
     "EntityRecognizerPropertiesTypeDef",
     {
         "EntityRecognizerArn": str,
         "LanguageCode": LanguageCodeType,
         "Status": ModelStatusType,
         "Message": str,
@@ -2777,36 +3485,38 @@
         "RecognizerMetadata": EntityRecognizerMetadataTypeDef,
         "DataAccessRoleArn": str,
         "VolumeKmsKeyId": str,
         "VpcConfig": VpcConfigTypeDef,
         "ModelKmsKeyId": str,
         "VersionName": str,
         "SourceModelArn": str,
+        "FlywheelArn": str,
+        "OutputDataConfig": EntityRecognizerOutputDataConfigTypeDef,
     },
     total=False,
 )
 
 DetectEntitiesResponseTypeDef = TypedDict(
     "DetectEntitiesResponseTypeDef",
     {
         "Entities": List[EntityTypeDef],
         "DocumentMetadata": DocumentMetadataTypeDef,
         "DocumentType": List[DocumentTypeListItemTypeDef],
         "Blocks": List[BlockTypeDef],
         "Errors": List[ErrorsListItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDetectSyntaxResponseTypeDef = TypedDict(
     "BatchDetectSyntaxResponseTypeDef",
     {
         "ResultList": List[BatchDetectSyntaxItemResultTypeDef],
         "ErrorList": List[BatchItemErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDetectTargetedSentimentItemResultTypeDef = TypedDict(
     "BatchDetectTargetedSentimentItemResultTypeDef",
     {
         "Index": int,
@@ -2815,45 +3525,61 @@
     total=False,
 )
 
 DetectTargetedSentimentResponseTypeDef = TypedDict(
     "DetectTargetedSentimentResponseTypeDef",
     {
         "Entities": List[TargetedSentimentEntityTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDetectEntitiesResponseTypeDef = TypedDict(
     "BatchDetectEntitiesResponseTypeDef",
     {
         "ResultList": List[BatchDetectEntitiesItemResultTypeDef],
         "ErrorList": List[BatchItemErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeFlywheelResponseTypeDef = TypedDict(
+    "DescribeFlywheelResponseTypeDef",
+    {
+        "FlywheelProperties": FlywheelPropertiesTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateFlywheelResponseTypeDef = TypedDict(
+    "UpdateFlywheelResponseTypeDef",
+    {
+        "FlywheelProperties": FlywheelPropertiesTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEntityRecognizerResponseTypeDef = TypedDict(
     "DescribeEntityRecognizerResponseTypeDef",
     {
         "EntityRecognizerProperties": EntityRecognizerPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListEntityRecognizersResponseTypeDef = TypedDict(
     "ListEntityRecognizersResponseTypeDef",
     {
         "EntityRecognizerPropertiesList": List[EntityRecognizerPropertiesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDetectTargetedSentimentResponseTypeDef = TypedDict(
     "BatchDetectTargetedSentimentResponseTypeDef",
     {
         "ResultList": List[BatchDetectTargetedSentimentItemResultTypeDef],
         "ErrorList": List[BatchItemErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-comprehend-2.5.0.post1/types_aiobotocore_comprehend.egg-info/PKG-INFO` & `types-aiobotocore-comprehend-2.5.1/README.md`

 * *Files 5% similar despite different names*

```diff
@@ -1,62 +1,29 @@
-Metadata-Version: 2.1
-Name: types-aiobotocore-comprehend
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Comprehend 2.5.0 service generated with mypy-boto3-builder 7.13.0
-Home-page: https://github.com/youtype/mypy_boto3_builder
-Author: Vlad Emelianov
-Author-email: vlad.emelianov.nz@gmail.com
-License: MIT License
-Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/
-Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
-Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
-Keywords: aiobotocore comprehend type-annotations boto3-stubs mypy typeshed autocomplete
-Classifier: Development Status :: 5 - Production/Stable
-Classifier: Intended Audience :: Developers
-Classifier: Environment :: Console
-Classifier: License :: OSI Approved :: MIT License
-Classifier: Natural Language :: English
-Classifier: Operating System :: OS Independent
-Classifier: Programming Language :: Python :: 3
-Classifier: Programming Language :: Python :: 3.7
-Classifier: Programming Language :: Python :: 3.7
-Classifier: Programming Language :: Python :: 3.8
-Classifier: Programming Language :: Python :: 3.9
-Classifier: Programming Language :: Python :: 3.10
-Classifier: Programming Language :: Python :: 3.11
-Classifier: Programming Language :: Python :: 3.12
-Classifier: Programming Language :: Python :: 3 :: Only
-Classifier: Programming Language :: Python :: Implementation :: CPython
-Classifier: Typing :: Typed
-Requires-Python: >=3.7
-Description-Content-Type: text/markdown
-License-File: LICENSE
-
 <a id="types-aiobotocore-comprehend"></a>
 
 # types-aiobotocore-comprehend
 
 [![PyPI - types-aiobotocore-comprehend](https://img.shields.io/pypi/v/types-aiobotocore-comprehend.svg?color=blue)](https://pypi.org/project/types-aiobotocore-comprehend)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-comprehend.svg?color=blue)](https://pypi.org/project/types-aiobotocore-comprehend)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-comprehend?color=blue)](https://pypistats.org/packages/types-aiobotocore-comprehend)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Comprehend 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend)
+[aiobotocore.Comprehend 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/comprehend.html#Comprehend)
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
 [types-aiobotocore-comprehend docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_comprehend/).
 
 See how it helps to find and fix potential bugs:
 
@@ -332,38 +299,46 @@
 `types_aiobotocore_comprehend.literals` module contains literals extracted from
 shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_comprehend.literals import (
     AugmentedManifestsDocumentTypeFormatType,
     BlockTypeType,
+    DatasetDataFormatType,
+    DatasetStatusType,
+    DatasetTypeType,
     DocumentClassifierDataFormatType,
+    DocumentClassifierDocumentTypeFormatType,
     DocumentClassifierModeType,
     DocumentReadActionType,
     DocumentReadFeatureTypesType,
     DocumentReadModeType,
     DocumentTypeType,
     EndpointStatusType,
     EntityRecognizerDataFormatType,
     EntityTypeType,
+    FlywheelIterationStatusType,
+    FlywheelStatusType,
     InputFormatType,
     JobStatusType,
     LanguageCodeType,
     ListDocumentClassificationJobsPaginatorName,
     ListDocumentClassifiersPaginatorName,
     ListDominantLanguageDetectionJobsPaginatorName,
     ListEndpointsPaginatorName,
     ListEntitiesDetectionJobsPaginatorName,
     ListEntityRecognizersPaginatorName,
     ListKeyPhrasesDetectionJobsPaginatorName,
     ListPiiEntitiesDetectionJobsPaginatorName,
     ListSentimentDetectionJobsPaginatorName,
     ListTopicsDetectionJobsPaginatorName,
     ModelStatusType,
+    ModelTypeType,
     PageBasedErrorCodeType,
+    PageBasedWarningCodeType,
     PartOfSpeechTagTypeType,
     PiiEntitiesDetectionMaskModeType,
     PiiEntitiesDetectionModeType,
     PiiEntityTypeType,
     RelationshipTypeType,
     SentimentTypeType,
     SplitType,
@@ -390,15 +365,14 @@
 
 ```python
 from types_aiobotocore_comprehend.type_defs import (
     AugmentedManifestsListItemTypeDef,
     DominantLanguageTypeDef,
     BatchDetectDominantLanguageRequestRequestTypeDef,
     BatchItemErrorTypeDef,
-    ResponseMetadataTypeDef,
     BatchDetectEntitiesRequestRequestTypeDef,
     KeyPhraseTypeDef,
     BatchDetectKeyPhrasesRequestRequestTypeDef,
     SentimentScoreTypeDef,
     BatchDetectSentimentRequestRequestTypeDef,
     BatchDetectSyntaxRequestRequestTypeDef,
     BatchDetectTargetedSentimentRequestRequestTypeDef,
@@ -407,111 +381,135 @@
     BoundingBoxTypeDef,
     ClassifierEvaluationMetricsTypeDef,
     DocumentReaderConfigTypeDef,
     DocumentClassTypeDef,
     DocumentLabelTypeDef,
     DocumentTypeListItemTypeDef,
     ErrorsListItemTypeDef,
+    WarningsListItemTypeDef,
     ContainsPiiEntitiesRequestRequestTypeDef,
     EntityLabelTypeDef,
-    DocumentClassifierOutputDataConfigTypeDef,
     TagTypeDef,
+    CreateDatasetResponseTypeDef,
+    DocumentClassifierOutputDataConfigTypeDef,
     VpcConfigTypeDef,
+    CreateDocumentClassifierResponseTypeDef,
+    CreateEndpointResponseTypeDef,
+    CreateEntityRecognizerResponseTypeDef,
+    CreateFlywheelResponseTypeDef,
+    DatasetAugmentedManifestsListItemTypeDef,
+    DatasetDocumentClassifierInputDataConfigTypeDef,
+    DatasetEntityRecognizerAnnotationsTypeDef,
+    DatasetEntityRecognizerDocumentsTypeDef,
+    DatasetEntityRecognizerEntityListTypeDef,
+    DatasetFilterTypeDef,
+    DatasetPropertiesTypeDef,
     DeleteDocumentClassifierRequestRequestTypeDef,
     DeleteEndpointRequestRequestTypeDef,
     DeleteEntityRecognizerRequestRequestTypeDef,
+    DeleteFlywheelRequestRequestTypeDef,
     DeleteResourcePolicyRequestRequestTypeDef,
+    DescribeDatasetRequestRequestTypeDef,
     DescribeDocumentClassificationJobRequestRequestTypeDef,
     DescribeDocumentClassifierRequestRequestTypeDef,
     DescribeDominantLanguageDetectionJobRequestRequestTypeDef,
     DescribeEndpointRequestRequestTypeDef,
     EndpointPropertiesTypeDef,
     DescribeEntitiesDetectionJobRequestRequestTypeDef,
     DescribeEntityRecognizerRequestRequestTypeDef,
     DescribeEventsDetectionJobRequestRequestTypeDef,
+    DescribeFlywheelIterationRequestRequestTypeDef,
+    DescribeFlywheelRequestRequestTypeDef,
     DescribeKeyPhrasesDetectionJobRequestRequestTypeDef,
     DescribePiiEntitiesDetectionJobRequestRequestTypeDef,
     DescribeResourcePolicyRequestRequestTypeDef,
+    DescribeResourcePolicyResponseTypeDef,
     DescribeSentimentDetectionJobRequestRequestTypeDef,
     DescribeTargetedSentimentDetectionJobRequestRequestTypeDef,
     DescribeTopicsDetectionJobRequestRequestTypeDef,
     DetectDominantLanguageRequestRequestTypeDef,
     DetectKeyPhrasesRequestRequestTypeDef,
     DetectPiiEntitiesRequestRequestTypeDef,
     PiiEntityTypeDef,
     DetectSentimentRequestRequestTypeDef,
     DetectSyntaxRequestRequestTypeDef,
     DetectTargetedSentimentRequestRequestTypeDef,
+    DocumentClassificationConfigTypeDef,
     DocumentClassificationJobFilterTypeDef,
     OutputDataConfigTypeDef,
+    DocumentClassifierDocumentsTypeDef,
     DocumentClassifierFilterTypeDef,
     DocumentClassifierSummaryTypeDef,
     ExtractedCharactersListItemTypeDef,
     DominantLanguageDetectionJobFilterTypeDef,
     EndpointFilterTypeDef,
     EntitiesDetectionJobFilterTypeDef,
+    EntityTypesListItemTypeDef,
     EntityRecognizerAnnotationsTypeDef,
     EntityRecognizerDocumentsTypeDef,
     EntityRecognizerEntityListTypeDef,
     EntityRecognizerEvaluationMetricsTypeDef,
     EntityRecognizerFilterTypeDef,
-    EntityTypesListItemTypeDef,
     EntityTypesEvaluationMetricsTypeDef,
+    EntityRecognizerOutputDataConfigTypeDef,
     EntityRecognizerSummaryTypeDef,
     EventsDetectionJobFilterTypeDef,
+    FlywheelFilterTypeDef,
+    FlywheelIterationFilterTypeDef,
+    FlywheelModelEvaluationMetricsTypeDef,
+    FlywheelSummaryTypeDef,
     PointTypeDef,
+    ImportModelResponseTypeDef,
     KeyPhrasesDetectionJobFilterTypeDef,
-    PaginatorConfigTypeDef,
     ListDocumentClassifierSummariesRequestRequestTypeDef,
     ListEntityRecognizerSummariesRequestRequestTypeDef,
     PiiEntitiesDetectionJobFilterTypeDef,
     SentimentDetectionJobFilterTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     TargetedSentimentDetectionJobFilterTypeDef,
     TopicsDetectionJobFilterTypeDef,
+    PaginatorConfigTypeDef,
     PartOfSpeechTagTypeDef,
     PiiOutputDataConfigTypeDef,
     RedactionConfigTypeDef,
     PutResourcePolicyRequestRequestTypeDef,
-    StopDominantLanguageDetectionJobRequestRequestTypeDef,
-    StopEntitiesDetectionJobRequestRequestTypeDef,
-    StopEventsDetectionJobRequestRequestTypeDef,
-    StopKeyPhrasesDetectionJobRequestRequestTypeDef,
-    StopPiiEntitiesDetectionJobRequestRequestTypeDef,
-    StopSentimentDetectionJobRequestRequestTypeDef,
-    StopTargetedSentimentDetectionJobRequestRequestTypeDef,
-    StopTrainingDocumentClassifierRequestRequestTypeDef,
-    StopTrainingEntityRecognizerRequestRequestTypeDef,
-    UntagResourceRequestRequestTypeDef,
-    UpdateEndpointRequestRequestTypeDef,
-    DocumentClassifierInputDataConfigTypeDef,
-    BatchDetectDominantLanguageItemResultTypeDef,
-    CreateDocumentClassifierResponseTypeDef,
-    CreateEndpointResponseTypeDef,
-    CreateEntityRecognizerResponseTypeDef,
-    DescribeResourcePolicyResponseTypeDef,
-    DetectDominantLanguageResponseTypeDef,
-    ImportModelResponseTypeDef,
     PutResourcePolicyResponseTypeDef,
+    ResponseMetadataTypeDef,
     StartDocumentClassificationJobResponseTypeDef,
     StartDominantLanguageDetectionJobResponseTypeDef,
     StartEntitiesDetectionJobResponseTypeDef,
     StartEventsDetectionJobResponseTypeDef,
+    StartFlywheelIterationRequestRequestTypeDef,
+    StartFlywheelIterationResponseTypeDef,
     StartKeyPhrasesDetectionJobResponseTypeDef,
     StartPiiEntitiesDetectionJobResponseTypeDef,
     StartSentimentDetectionJobResponseTypeDef,
     StartTargetedSentimentDetectionJobResponseTypeDef,
     StartTopicsDetectionJobResponseTypeDef,
+    StopDominantLanguageDetectionJobRequestRequestTypeDef,
     StopDominantLanguageDetectionJobResponseTypeDef,
+    StopEntitiesDetectionJobRequestRequestTypeDef,
     StopEntitiesDetectionJobResponseTypeDef,
+    StopEventsDetectionJobRequestRequestTypeDef,
     StopEventsDetectionJobResponseTypeDef,
+    StopKeyPhrasesDetectionJobRequestRequestTypeDef,
     StopKeyPhrasesDetectionJobResponseTypeDef,
+    StopPiiEntitiesDetectionJobRequestRequestTypeDef,
     StopPiiEntitiesDetectionJobResponseTypeDef,
+    StopSentimentDetectionJobRequestRequestTypeDef,
     StopSentimentDetectionJobResponseTypeDef,
+    StopTargetedSentimentDetectionJobRequestRequestTypeDef,
     StopTargetedSentimentDetectionJobResponseTypeDef,
+    StopTrainingDocumentClassifierRequestRequestTypeDef,
+    StopTrainingEntityRecognizerRequestRequestTypeDef,
+    UntagResourceRequestRequestTypeDef,
+    UpdateEndpointRequestRequestTypeDef,
+    UpdateEndpointResponseTypeDef,
+    BatchDetectDominantLanguageItemResultTypeDef,
+    DetectDominantLanguageResponseTypeDef,
     BatchDetectKeyPhrasesItemResultTypeDef,
     DetectKeyPhrasesResponseTypeDef,
     BatchDetectSentimentItemResultTypeDef,
     DetectSentimentResponseTypeDef,
     MentionSentimentTypeDef,
     BlockReferenceTypeDef,
     ClassifierMetadataTypeDef,
@@ -519,53 +517,63 @@
     DetectEntitiesRequestRequestTypeDef,
     InputDataConfigTypeDef,
     ContainsPiiEntitiesResponseTypeDef,
     CreateEndpointRequestRequestTypeDef,
     ImportModelRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
+    DataSecurityConfigTypeDef,
+    UpdateDataSecurityConfigTypeDef,
+    DatasetEntityRecognizerInputDataConfigTypeDef,
+    ListDatasetsRequestRequestTypeDef,
+    DescribeDatasetResponseTypeDef,
+    ListDatasetsResponseTypeDef,
     DescribeEndpointResponseTypeDef,
     ListEndpointsResponseTypeDef,
     DetectPiiEntitiesResponseTypeDef,
+    ListDocumentClassificationJobsRequestListDocumentClassificationJobsPaginateTypeDef,
     ListDocumentClassificationJobsRequestRequestTypeDef,
+    DocumentClassifierInputDataConfigTypeDef,
+    ListDocumentClassifiersRequestListDocumentClassifiersPaginateTypeDef,
     ListDocumentClassifiersRequestRequestTypeDef,
     ListDocumentClassifierSummariesResponseTypeDef,
     DocumentMetadataTypeDef,
+    ListDominantLanguageDetectionJobsRequestListDominantLanguageDetectionJobsPaginateTypeDef,
     ListDominantLanguageDetectionJobsRequestRequestTypeDef,
+    ListEndpointsRequestListEndpointsPaginateTypeDef,
     ListEndpointsRequestRequestTypeDef,
+    ListEntitiesDetectionJobsRequestListEntitiesDetectionJobsPaginateTypeDef,
     ListEntitiesDetectionJobsRequestRequestTypeDef,
-    ListEntityRecognizersRequestRequestTypeDef,
+    EntityRecognitionConfigTypeDef,
     EntityRecognizerInputDataConfigTypeDef,
+    ListEntityRecognizersRequestListEntityRecognizersPaginateTypeDef,
+    ListEntityRecognizersRequestRequestTypeDef,
     EntityRecognizerMetadataEntityTypesListItemTypeDef,
     ListEntityRecognizerSummariesResponseTypeDef,
     ListEventsDetectionJobsRequestRequestTypeDef,
+    ListFlywheelsRequestRequestTypeDef,
+    ListFlywheelIterationHistoryRequestRequestTypeDef,
+    FlywheelIterationPropertiesTypeDef,
+    ListFlywheelsResponseTypeDef,
     GeometryTypeDef,
-    ListKeyPhrasesDetectionJobsRequestRequestTypeDef,
-    ListDocumentClassificationJobsRequestListDocumentClassificationJobsPaginateTypeDef,
-    ListDocumentClassifiersRequestListDocumentClassifiersPaginateTypeDef,
-    ListDominantLanguageDetectionJobsRequestListDominantLanguageDetectionJobsPaginateTypeDef,
-    ListEndpointsRequestListEndpointsPaginateTypeDef,
-    ListEntitiesDetectionJobsRequestListEntitiesDetectionJobsPaginateTypeDef,
-    ListEntityRecognizersRequestListEntityRecognizersPaginateTypeDef,
     ListKeyPhrasesDetectionJobsRequestListKeyPhrasesDetectionJobsPaginateTypeDef,
+    ListKeyPhrasesDetectionJobsRequestRequestTypeDef,
     ListPiiEntitiesDetectionJobsRequestListPiiEntitiesDetectionJobsPaginateTypeDef,
     ListPiiEntitiesDetectionJobsRequestRequestTypeDef,
     ListSentimentDetectionJobsRequestListSentimentDetectionJobsPaginateTypeDef,
     ListSentimentDetectionJobsRequestRequestTypeDef,
     ListTargetedSentimentDetectionJobsRequestRequestTypeDef,
     ListTopicsDetectionJobsRequestListTopicsDetectionJobsPaginateTypeDef,
     ListTopicsDetectionJobsRequestRequestTypeDef,
     SyntaxTokenTypeDef,
-    CreateDocumentClassifierRequestRequestTypeDef,
     BatchDetectDominantLanguageResponseTypeDef,
     BatchDetectKeyPhrasesResponseTypeDef,
     BatchDetectSentimentResponseTypeDef,
     TargetedSentimentMentionTypeDef,
     EntityTypeDef,
-    DocumentClassifierPropertiesTypeDef,
     DocumentClassificationJobPropertiesTypeDef,
     DominantLanguageDetectionJobPropertiesTypeDef,
     EntitiesDetectionJobPropertiesTypeDef,
     EventsDetectionJobPropertiesTypeDef,
     KeyPhrasesDetectionJobPropertiesTypeDef,
     PiiEntitiesDetectionJobPropertiesTypeDef,
     SentimentDetectionJobPropertiesTypeDef,
@@ -576,24 +584,29 @@
     StartKeyPhrasesDetectionJobRequestRequestTypeDef,
     StartPiiEntitiesDetectionJobRequestRequestTypeDef,
     StartSentimentDetectionJobRequestRequestTypeDef,
     StartTargetedSentimentDetectionJobRequestRequestTypeDef,
     StartTopicsDetectionJobRequestRequestTypeDef,
     TargetedSentimentDetectionJobPropertiesTypeDef,
     TopicsDetectionJobPropertiesTypeDef,
+    UpdateFlywheelRequestRequestTypeDef,
+    DatasetInputDataConfigTypeDef,
+    CreateDocumentClassifierRequestRequestTypeDef,
+    DocumentClassifierPropertiesTypeDef,
     ClassifyDocumentResponseTypeDef,
+    TaskConfigTypeDef,
     CreateEntityRecognizerRequestRequestTypeDef,
     EntityRecognizerMetadataTypeDef,
+    DescribeFlywheelIterationResponseTypeDef,
+    ListFlywheelIterationHistoryResponseTypeDef,
     BlockTypeDef,
     BatchDetectSyntaxItemResultTypeDef,
     DetectSyntaxResponseTypeDef,
     TargetedSentimentEntityTypeDef,
     BatchDetectEntitiesItemResultTypeDef,
-    DescribeDocumentClassifierResponseTypeDef,
-    ListDocumentClassifiersResponseTypeDef,
     DescribeDocumentClassificationJobResponseTypeDef,
     ListDocumentClassificationJobsResponseTypeDef,
     DescribeDominantLanguageDetectionJobResponseTypeDef,
     ListDominantLanguageDetectionJobsResponseTypeDef,
     DescribeEntitiesDetectionJobResponseTypeDef,
     ListEntitiesDetectionJobsResponseTypeDef,
     DescribeEventsDetectionJobResponseTypeDef,
@@ -604,20 +617,27 @@
     ListPiiEntitiesDetectionJobsResponseTypeDef,
     DescribeSentimentDetectionJobResponseTypeDef,
     ListSentimentDetectionJobsResponseTypeDef,
     DescribeTargetedSentimentDetectionJobResponseTypeDef,
     ListTargetedSentimentDetectionJobsResponseTypeDef,
     DescribeTopicsDetectionJobResponseTypeDef,
     ListTopicsDetectionJobsResponseTypeDef,
+    CreateDatasetRequestRequestTypeDef,
+    DescribeDocumentClassifierResponseTypeDef,
+    ListDocumentClassifiersResponseTypeDef,
+    CreateFlywheelRequestRequestTypeDef,
+    FlywheelPropertiesTypeDef,
     EntityRecognizerPropertiesTypeDef,
     DetectEntitiesResponseTypeDef,
     BatchDetectSyntaxResponseTypeDef,
     BatchDetectTargetedSentimentItemResultTypeDef,
     DetectTargetedSentimentResponseTypeDef,
     BatchDetectEntitiesResponseTypeDef,
+    DescribeFlywheelResponseTypeDef,
+    UpdateFlywheelResponseTypeDef,
     DescribeEntityRecognizerResponseTypeDef,
     ListEntityRecognizersResponseTypeDef,
     BatchDetectTargetedSentimentResponseTypeDef,
 )
 
 
 def get_structure() -> AugmentedManifestsListItemTypeDef:
@@ -627,43 +647,43 @@
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

### Comparing `types-aiobotocore-comprehend-2.5.0.post1/types_aiobotocore_comprehend.egg-info/SOURCES.txt` & `types-aiobotocore-comprehend-2.5.1/types_aiobotocore_comprehend.egg-info/SOURCES.txt`

 * *Files identical despite different names*

