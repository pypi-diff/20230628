# Comparing `tmp/types-aiobotocore-frauddetector-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-frauddetector-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-frauddetector-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:39 2023, max compression
+gzip compressed data, was "types-aiobotocore-frauddetector-2.5.1.tar", last modified: Wed Jun 28 01:43:31 2023, max compression
```

## Comparing `types-aiobotocore-frauddetector-2.5.0.post1.tar` & `types-aiobotocore-frauddetector-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:39.435224 types-aiobotocore-frauddetector-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:14:46.000000 types-aiobotocore-frauddetector-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    19059 2023-03-11 12:26:39.431224 types-aiobotocore-frauddetector-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    17464 2023-03-11 12:14:46.000000 types-aiobotocore-frauddetector-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:39.435224 types-aiobotocore-frauddetector-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2166 2023-03-11 12:14:46.000000 types-aiobotocore-frauddetector-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:39.423224 types-aiobotocore-frauddetector-2.5.0.post1/types_aiobotocore_frauddetector/
--rw-r--r--   0 runner    (1001) docker     (123)      490 2023-03-11 12:14:46.000000 types-aiobotocore-frauddetector-2.5.0.post1/types_aiobotocore_frauddetector/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      489 2023-03-11 12:14:46.000000 types-aiobotocore-frauddetector-2.5.0.post1/types_aiobotocore_frauddetector/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      967 2023-03-11 12:14:46.000000 types-aiobotocore-frauddetector-2.5.0.post1/types_aiobotocore_frauddetector/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    49058 2023-03-11 12:14:46.000000 types-aiobotocore-frauddetector-2.5.0.post1/types_aiobotocore_frauddetector/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    48976 2023-03-11 12:14:46.000000 types-aiobotocore-frauddetector-2.5.0.post1/types_aiobotocore_frauddetector/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9096 2023-03-11 12:14:46.000000 types-aiobotocore-frauddetector-2.5.0.post1/types_aiobotocore_frauddetector/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9094 2023-03-11 12:14:46.000000 types-aiobotocore-frauddetector-2.5.0.post1/types_aiobotocore_frauddetector/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:14:46.000000 types-aiobotocore-frauddetector-2.5.0.post1/types_aiobotocore_frauddetector/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    59086 2023-03-11 12:14:48.000000 types-aiobotocore-frauddetector-2.5.0.post1/types_aiobotocore_frauddetector/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    59019 2023-03-11 12:14:47.000000 types-aiobotocore-frauddetector-2.5.0.post1/types_aiobotocore_frauddetector/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:14:46.000000 types-aiobotocore-frauddetector-2.5.0.post1/types_aiobotocore_frauddetector/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:39.431224 types-aiobotocore-frauddetector-2.5.0.post1/types_aiobotocore_frauddetector.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    19059 2023-03-11 12:26:39.000000 types-aiobotocore-frauddetector-2.5.0.post1/types_aiobotocore_frauddetector.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      836 2023-03-11 12:26:39.000000 types-aiobotocore-frauddetector-2.5.0.post1/types_aiobotocore_frauddetector.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:39.000000 types-aiobotocore-frauddetector-2.5.0.post1/types_aiobotocore_frauddetector.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:39.000000 types-aiobotocore-frauddetector-2.5.0.post1/types_aiobotocore_frauddetector.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:39.000000 types-aiobotocore-frauddetector-2.5.0.post1/types_aiobotocore_frauddetector.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       32 2023-03-11 12:26:39.000000 types-aiobotocore-frauddetector-2.5.0.post1/types_aiobotocore_frauddetector.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:31.546140 types-aiobotocore-frauddetector-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:31:22.000000 types-aiobotocore-frauddetector-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    19088 2023-06-28 01:43:31.538140 types-aiobotocore-frauddetector-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    17499 2023-06-28 01:31:22.000000 types-aiobotocore-frauddetector-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:31.546140 types-aiobotocore-frauddetector-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2160 2023-06-28 01:31:22.000000 types-aiobotocore-frauddetector-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:31.538140 types-aiobotocore-frauddetector-2.5.1/types_aiobotocore_frauddetector/
+-rw-r--r--   0 runner    (1001) docker     (123)      490 2023-06-28 01:31:22.000000 types-aiobotocore-frauddetector-2.5.1/types_aiobotocore_frauddetector/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      489 2023-06-28 01:31:22.000000 types-aiobotocore-frauddetector-2.5.1/types_aiobotocore_frauddetector/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      955 2023-06-28 01:31:22.000000 types-aiobotocore-frauddetector-2.5.1/types_aiobotocore_frauddetector/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    49150 2023-06-28 01:31:23.000000 types-aiobotocore-frauddetector-2.5.1/types_aiobotocore_frauddetector/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    49068 2023-06-28 01:31:22.000000 types-aiobotocore-frauddetector-2.5.1/types_aiobotocore_frauddetector/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9317 2023-06-28 01:31:23.000000 types-aiobotocore-frauddetector-2.5.1/types_aiobotocore_frauddetector/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9315 2023-06-28 01:31:23.000000 types-aiobotocore-frauddetector-2.5.1/types_aiobotocore_frauddetector/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:31:22.000000 types-aiobotocore-frauddetector-2.5.1/types_aiobotocore_frauddetector/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    59421 2023-06-28 01:31:25.000000 types-aiobotocore-frauddetector-2.5.1/types_aiobotocore_frauddetector/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    59354 2023-06-28 01:31:24.000000 types-aiobotocore-frauddetector-2.5.1/types_aiobotocore_frauddetector/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:31:22.000000 types-aiobotocore-frauddetector-2.5.1/types_aiobotocore_frauddetector/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:31.538140 types-aiobotocore-frauddetector-2.5.1/types_aiobotocore_frauddetector.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    19088 2023-06-28 01:43:31.000000 types-aiobotocore-frauddetector-2.5.1/types_aiobotocore_frauddetector.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      836 2023-06-28 01:43:31.000000 types-aiobotocore-frauddetector-2.5.1/types_aiobotocore_frauddetector.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:31.000000 types-aiobotocore-frauddetector-2.5.1/types_aiobotocore_frauddetector.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:31.000000 types-aiobotocore-frauddetector-2.5.1/types_aiobotocore_frauddetector.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:31.000000 types-aiobotocore-frauddetector-2.5.1/types_aiobotocore_frauddetector.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       32 2023-06-28 01:43:31.000000 types-aiobotocore-frauddetector-2.5.1/types_aiobotocore_frauddetector.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-frauddetector-2.5.0.post1/LICENSE` & `types-aiobotocore-frauddetector-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-frauddetector-2.5.0.post1/PKG-INFO` & `types-aiobotocore-frauddetector-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-frauddetector
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.FraudDetector 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.FraudDetector 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_frauddetector/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-frauddetector"></a>
 
 # types-aiobotocore-frauddetector
 
 [![PyPI - types-aiobotocore-frauddetector](https://img.shields.io/pypi/v/types-aiobotocore-frauddetector.svg?color=blue)](https://pypi.org/project/types-aiobotocore-frauddetector)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-frauddetector.svg?color=blue)](https://pypi.org/project/types-aiobotocore-frauddetector)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_frauddetector/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-frauddetector?color=blue)](https://pypistats.org/packages/types-aiobotocore-frauddetector)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.FraudDetector 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/frauddetector.html#FraudDetector)
+[aiobotocore.FraudDetector 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/frauddetector.html#FraudDetector)
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
 [types-aiobotocore-frauddetector docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_frauddetector/).
 
 See how it helps to find and fix potential bugs:
 
@@ -313,35 +313,37 @@
     ATIModelPerformanceTypeDef,
     AggregatedLogOddsMetricTypeDef,
     AggregatedVariablesImpactExplanationTypeDef,
     AllowDenyListTypeDef,
     BatchCreateVariableErrorTypeDef,
     TagTypeDef,
     VariableEntryTypeDef,
-    ResponseMetadataTypeDef,
     BatchGetVariableErrorTypeDef,
     BatchGetVariableRequestRequestTypeDef,
     VariableTypeDef,
     BatchImportTypeDef,
     BatchPredictionTypeDef,
     CancelBatchImportJobRequestRequestTypeDef,
     CancelBatchPredictionJobRequestRequestTypeDef,
     ModelVersionTypeDef,
     RuleTypeDef,
+    CreateDetectorVersionResultTypeDef,
     ExternalEventsDetailTypeDef,
+    CreateModelVersionResultTypeDef,
     FieldValidationMessageTypeDef,
     FileValidationMessageTypeDef,
     DeleteBatchImportJobRequestRequestTypeDef,
     DeleteBatchPredictionJobRequestRequestTypeDef,
     DeleteDetectorRequestRequestTypeDef,
     DeleteDetectorVersionRequestRequestTypeDef,
     DeleteEntityTypeRequestRequestTypeDef,
     DeleteEventRequestRequestTypeDef,
     DeleteEventTypeRequestRequestTypeDef,
     DeleteEventsByEventTypeRequestRequestTypeDef,
+    DeleteEventsByEventTypeResultTypeDef,
     DeleteExternalModelRequestRequestTypeDef,
     DeleteLabelRequestRequestTypeDef,
     DeleteListRequestRequestTypeDef,
     DeleteModelRequestRequestTypeDef,
     DeleteModelVersionRequestRequestTypeDef,
     DeleteOutcomeRequestRequestTypeDef,
     DeleteVariableRequestRequestTypeDef,
@@ -349,37 +351,40 @@
     DetectorVersionSummaryTypeDef,
     DescribeModelVersionsRequestRequestTypeDef,
     DetectorTypeDef,
     EntityTypeDef,
     EntityTypeTypeDef,
     EvaluatedExternalModelTypeDef,
     EvaluatedRuleTypeDef,
+    EventOrchestrationTypeDef,
     EventPredictionSummaryTypeDef,
     IngestedEventStatisticsTypeDef,
     EventVariableSummaryTypeDef,
     ExternalModelSummaryTypeDef,
     ModelInputConfigurationTypeDef,
     ModelOutputConfigurationTypeDef,
     FilterConditionTypeDef,
     GetBatchImportJobsRequestRequestTypeDef,
     GetBatchPredictionJobsRequestRequestTypeDef,
     GetDeleteEventsByEventTypeStatusRequestRequestTypeDef,
+    GetDeleteEventsByEventTypeStatusResultTypeDef,
     GetDetectorVersionRequestRequestTypeDef,
     GetDetectorsRequestRequestTypeDef,
     GetEntityTypesRequestRequestTypeDef,
     GetEventPredictionMetadataRequestRequestTypeDef,
     ModelEndpointDataBlobTypeDef,
     RuleResultTypeDef,
     GetEventRequestRequestTypeDef,
     GetEventTypesRequestRequestTypeDef,
     GetExternalModelsRequestRequestTypeDef,
     KMSKeyTypeDef,
     GetLabelsRequestRequestTypeDef,
     LabelTypeDef,
     GetListElementsRequestRequestTypeDef,
+    GetListElementsResultTypeDef,
     GetListsMetadataRequestRequestTypeDef,
     GetModelVersionRequestRequestTypeDef,
     GetModelsRequestRequestTypeDef,
     ModelTypeDef,
     GetOutcomesRequestRequestTypeDef,
     OutcomeTypeDef,
     GetRulesRequestRequestTypeDef,
@@ -391,47 +396,42 @@
     ListTagsForResourceRequestRequestTypeDef,
     LogOddsMetricTypeDef,
     MetricDataPointTypeDef,
     OFIMetricDataPointTypeDef,
     UncertaintyRangeTypeDef,
     VariableImpactExplanationTypeDef,
     PutKMSEncryptionKeyRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     TFIMetricDataPointTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateDetectorVersionMetadataRequestRequestTypeDef,
     UpdateDetectorVersionStatusRequestRequestTypeDef,
     UpdateEventLabelRequestRequestTypeDef,
     UpdateListRequestRequestTypeDef,
     UpdateModelRequestRequestTypeDef,
+    UpdateModelVersionResultTypeDef,
     UpdateModelVersionStatusRequestRequestTypeDef,
     UpdateVariableRequestRequestTypeDef,
     ATITrainingMetricsValueTypeDef,
     AggregatedVariablesImportanceMetricsTypeDef,
+    GetListsMetadataResultTypeDef,
+    BatchCreateVariableResultTypeDef,
     CreateBatchImportJobRequestRequestTypeDef,
     CreateBatchPredictionJobRequestRequestTypeDef,
     CreateListRequestRequestTypeDef,
     CreateModelRequestRequestTypeDef,
     CreateRuleRequestRequestTypeDef,
     CreateVariableRequestRequestTypeDef,
+    ListTagsForResourceResultTypeDef,
     PutDetectorRequestRequestTypeDef,
     PutEntityTypeRequestRequestTypeDef,
-    PutEventTypeRequestRequestTypeDef,
     PutLabelRequestRequestTypeDef,
     PutOutcomeRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     BatchCreateVariableRequestRequestTypeDef,
-    BatchCreateVariableResultTypeDef,
-    CreateDetectorVersionResultTypeDef,
-    CreateModelVersionResultTypeDef,
-    DeleteEventsByEventTypeResultTypeDef,
-    GetDeleteEventsByEventTypeStatusResultTypeDef,
-    GetListElementsResultTypeDef,
-    GetListsMetadataResultTypeDef,
-    ListTagsForResourceResultTypeDef,
-    UpdateModelVersionResultTypeDef,
     BatchGetVariableResultTypeDef,
     GetVariablesResultTypeDef,
     GetBatchImportJobsResultTypeDef,
     GetBatchPredictionJobsResultTypeDef,
     ModelScoresTypeDef,
     CreateDetectorVersionRequestRequestTypeDef,
     CreateRuleResultTypeDef,
@@ -443,14 +443,15 @@
     UpdateRuleVersionResultTypeDef,
     DataValidationMetricsTypeDef,
     DescribeDetectorResultTypeDef,
     GetDetectorsResultTypeDef,
     EventTypeDef,
     SendEventRequestRequestTypeDef,
     GetEntityTypesResultTypeDef,
+    PutEventTypeRequestRequestTypeDef,
     ListEventPredictionsResultTypeDef,
     EventTypeTypeDef,
     ExternalModelOutputsTypeDef,
     ExternalModelTypeDef,
     PutExternalModelRequestRequestTypeDef,
     GetEventPredictionRequestRequestTypeDef,
     GetKMSEncryptionKeyResultTypeDef,
@@ -493,43 +494,43 @@
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

### Comparing `types-aiobotocore-frauddetector-2.5.0.post1/README.md` & `types-aiobotocore-frauddetector-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-frauddetector"></a>
 
 # types-aiobotocore-frauddetector
 
 [![PyPI - types-aiobotocore-frauddetector](https://img.shields.io/pypi/v/types-aiobotocore-frauddetector.svg?color=blue)](https://pypi.org/project/types-aiobotocore-frauddetector)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-frauddetector.svg?color=blue)](https://pypi.org/project/types-aiobotocore-frauddetector)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_frauddetector/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-frauddetector?color=blue)](https://pypistats.org/packages/types-aiobotocore-frauddetector)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.FraudDetector 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/frauddetector.html#FraudDetector)
+[aiobotocore.FraudDetector 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/frauddetector.html#FraudDetector)
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
 [types-aiobotocore-frauddetector docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_frauddetector/).
 
 See how it helps to find and fix potential bugs:
 
@@ -280,35 +280,37 @@
     ATIModelPerformanceTypeDef,
     AggregatedLogOddsMetricTypeDef,
     AggregatedVariablesImpactExplanationTypeDef,
     AllowDenyListTypeDef,
     BatchCreateVariableErrorTypeDef,
     TagTypeDef,
     VariableEntryTypeDef,
-    ResponseMetadataTypeDef,
     BatchGetVariableErrorTypeDef,
     BatchGetVariableRequestRequestTypeDef,
     VariableTypeDef,
     BatchImportTypeDef,
     BatchPredictionTypeDef,
     CancelBatchImportJobRequestRequestTypeDef,
     CancelBatchPredictionJobRequestRequestTypeDef,
     ModelVersionTypeDef,
     RuleTypeDef,
+    CreateDetectorVersionResultTypeDef,
     ExternalEventsDetailTypeDef,
+    CreateModelVersionResultTypeDef,
     FieldValidationMessageTypeDef,
     FileValidationMessageTypeDef,
     DeleteBatchImportJobRequestRequestTypeDef,
     DeleteBatchPredictionJobRequestRequestTypeDef,
     DeleteDetectorRequestRequestTypeDef,
     DeleteDetectorVersionRequestRequestTypeDef,
     DeleteEntityTypeRequestRequestTypeDef,
     DeleteEventRequestRequestTypeDef,
     DeleteEventTypeRequestRequestTypeDef,
     DeleteEventsByEventTypeRequestRequestTypeDef,
+    DeleteEventsByEventTypeResultTypeDef,
     DeleteExternalModelRequestRequestTypeDef,
     DeleteLabelRequestRequestTypeDef,
     DeleteListRequestRequestTypeDef,
     DeleteModelRequestRequestTypeDef,
     DeleteModelVersionRequestRequestTypeDef,
     DeleteOutcomeRequestRequestTypeDef,
     DeleteVariableRequestRequestTypeDef,
@@ -316,37 +318,40 @@
     DetectorVersionSummaryTypeDef,
     DescribeModelVersionsRequestRequestTypeDef,
     DetectorTypeDef,
     EntityTypeDef,
     EntityTypeTypeDef,
     EvaluatedExternalModelTypeDef,
     EvaluatedRuleTypeDef,
+    EventOrchestrationTypeDef,
     EventPredictionSummaryTypeDef,
     IngestedEventStatisticsTypeDef,
     EventVariableSummaryTypeDef,
     ExternalModelSummaryTypeDef,
     ModelInputConfigurationTypeDef,
     ModelOutputConfigurationTypeDef,
     FilterConditionTypeDef,
     GetBatchImportJobsRequestRequestTypeDef,
     GetBatchPredictionJobsRequestRequestTypeDef,
     GetDeleteEventsByEventTypeStatusRequestRequestTypeDef,
+    GetDeleteEventsByEventTypeStatusResultTypeDef,
     GetDetectorVersionRequestRequestTypeDef,
     GetDetectorsRequestRequestTypeDef,
     GetEntityTypesRequestRequestTypeDef,
     GetEventPredictionMetadataRequestRequestTypeDef,
     ModelEndpointDataBlobTypeDef,
     RuleResultTypeDef,
     GetEventRequestRequestTypeDef,
     GetEventTypesRequestRequestTypeDef,
     GetExternalModelsRequestRequestTypeDef,
     KMSKeyTypeDef,
     GetLabelsRequestRequestTypeDef,
     LabelTypeDef,
     GetListElementsRequestRequestTypeDef,
+    GetListElementsResultTypeDef,
     GetListsMetadataRequestRequestTypeDef,
     GetModelVersionRequestRequestTypeDef,
     GetModelsRequestRequestTypeDef,
     ModelTypeDef,
     GetOutcomesRequestRequestTypeDef,
     OutcomeTypeDef,
     GetRulesRequestRequestTypeDef,
@@ -358,47 +363,42 @@
     ListTagsForResourceRequestRequestTypeDef,
     LogOddsMetricTypeDef,
     MetricDataPointTypeDef,
     OFIMetricDataPointTypeDef,
     UncertaintyRangeTypeDef,
     VariableImpactExplanationTypeDef,
     PutKMSEncryptionKeyRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     TFIMetricDataPointTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateDetectorVersionMetadataRequestRequestTypeDef,
     UpdateDetectorVersionStatusRequestRequestTypeDef,
     UpdateEventLabelRequestRequestTypeDef,
     UpdateListRequestRequestTypeDef,
     UpdateModelRequestRequestTypeDef,
+    UpdateModelVersionResultTypeDef,
     UpdateModelVersionStatusRequestRequestTypeDef,
     UpdateVariableRequestRequestTypeDef,
     ATITrainingMetricsValueTypeDef,
     AggregatedVariablesImportanceMetricsTypeDef,
+    GetListsMetadataResultTypeDef,
+    BatchCreateVariableResultTypeDef,
     CreateBatchImportJobRequestRequestTypeDef,
     CreateBatchPredictionJobRequestRequestTypeDef,
     CreateListRequestRequestTypeDef,
     CreateModelRequestRequestTypeDef,
     CreateRuleRequestRequestTypeDef,
     CreateVariableRequestRequestTypeDef,
+    ListTagsForResourceResultTypeDef,
     PutDetectorRequestRequestTypeDef,
     PutEntityTypeRequestRequestTypeDef,
-    PutEventTypeRequestRequestTypeDef,
     PutLabelRequestRequestTypeDef,
     PutOutcomeRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     BatchCreateVariableRequestRequestTypeDef,
-    BatchCreateVariableResultTypeDef,
-    CreateDetectorVersionResultTypeDef,
-    CreateModelVersionResultTypeDef,
-    DeleteEventsByEventTypeResultTypeDef,
-    GetDeleteEventsByEventTypeStatusResultTypeDef,
-    GetListElementsResultTypeDef,
-    GetListsMetadataResultTypeDef,
-    ListTagsForResourceResultTypeDef,
-    UpdateModelVersionResultTypeDef,
     BatchGetVariableResultTypeDef,
     GetVariablesResultTypeDef,
     GetBatchImportJobsResultTypeDef,
     GetBatchPredictionJobsResultTypeDef,
     ModelScoresTypeDef,
     CreateDetectorVersionRequestRequestTypeDef,
     CreateRuleResultTypeDef,
@@ -410,14 +410,15 @@
     UpdateRuleVersionResultTypeDef,
     DataValidationMetricsTypeDef,
     DescribeDetectorResultTypeDef,
     GetDetectorsResultTypeDef,
     EventTypeDef,
     SendEventRequestRequestTypeDef,
     GetEntityTypesResultTypeDef,
+    PutEventTypeRequestRequestTypeDef,
     ListEventPredictionsResultTypeDef,
     EventTypeTypeDef,
     ExternalModelOutputsTypeDef,
     ExternalModelTypeDef,
     PutExternalModelRequestRequestTypeDef,
     GetEventPredictionRequestRequestTypeDef,
     GetKMSEncryptionKeyResultTypeDef,
@@ -460,43 +461,43 @@
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

### Comparing `types-aiobotocore-frauddetector-2.5.0.post1/setup.py` & `types-aiobotocore-frauddetector-2.5.1/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-frauddetector.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-frauddetector",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_frauddetector"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.FraudDetector 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.FraudDetector 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_frauddetector/"
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

### Comparing `types-aiobotocore-frauddetector-2.5.0.post1/types_aiobotocore_frauddetector/__main__.py` & `types-aiobotocore-frauddetector-2.5.1/types_aiobotocore_frauddetector/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.FraudDetector 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.FraudDetector 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_frauddetector//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/frauddetector.html#FraudDetector\nOther"
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

### Comparing `types-aiobotocore-frauddetector-2.5.0.post1/types_aiobotocore_frauddetector/client.py` & `types-aiobotocore-frauddetector-2.5.1/types_aiobotocore_frauddetector/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -38,14 +38,15 @@
     CreateDetectorVersionResultTypeDef,
     CreateModelVersionResultTypeDef,
     CreateRuleResultTypeDef,
     DeleteEventsByEventTypeResultTypeDef,
     DescribeDetectorResultTypeDef,
     DescribeModelVersionsResultTypeDef,
     EntityTypeDef,
+    EventOrchestrationTypeDef,
     ExternalEventsDetailTypeDef,
     FilterConditionTypeDef,
     GetBatchImportJobsResultTypeDef,
     GetBatchPredictionJobsResultTypeDef,
     GetDeleteEventsByEventTypeStatusResultTypeDef,
     GetDetectorsResultTypeDef,
     GetDetectorVersionResultTypeDef,
@@ -778,15 +779,16 @@
         *,
         name: str,
         eventVariables: Sequence[str],
         entityTypes: Sequence[str],
         description: str = ...,
         labels: Sequence[str] = ...,
         eventIngestion: EventIngestionType = ...,
-        tags: Sequence[TagTypeDef] = ...
+        tags: Sequence[TagTypeDef] = ...,
+        eventOrchestration: EventOrchestrationTypeDef = ...
     ) -> Dict[str, Any]:
         """
         Creates or updates an event type.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/frauddetector.html#FraudDetector.Client.put_event_type)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_frauddetector/client/#put_event_type)
         """
```

### Comparing `types-aiobotocore-frauddetector-2.5.0.post1/types_aiobotocore_frauddetector/client.pyi` & `types-aiobotocore-frauddetector-2.5.1/types_aiobotocore_frauddetector/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -38,14 +38,15 @@
     CreateDetectorVersionResultTypeDef,
     CreateModelVersionResultTypeDef,
     CreateRuleResultTypeDef,
     DeleteEventsByEventTypeResultTypeDef,
     DescribeDetectorResultTypeDef,
     DescribeModelVersionsResultTypeDef,
     EntityTypeDef,
+    EventOrchestrationTypeDef,
     ExternalEventsDetailTypeDef,
     FilterConditionTypeDef,
     GetBatchImportJobsResultTypeDef,
     GetBatchPredictionJobsResultTypeDef,
     GetDeleteEventsByEventTypeStatusResultTypeDef,
     GetDetectorsResultTypeDef,
     GetDetectorVersionResultTypeDef,
@@ -716,15 +717,16 @@
         *,
         name: str,
         eventVariables: Sequence[str],
         entityTypes: Sequence[str],
         description: str = ...,
         labels: Sequence[str] = ...,
         eventIngestion: EventIngestionType = ...,
-        tags: Sequence[TagTypeDef] = ...
+        tags: Sequence[TagTypeDef] = ...,
+        eventOrchestration: EventOrchestrationTypeDef = ...
     ) -> Dict[str, Any]:
         """
         Creates or updates an event type.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/frauddetector.html#FraudDetector.Client.put_event_type)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_frauddetector/client/#put_event_type)
         """
```

### Comparing `types-aiobotocore-frauddetector-2.5.0.post1/types_aiobotocore_frauddetector/literals.py` & `types-aiobotocore-frauddetector-2.5.1/types_aiobotocore_frauddetector/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -48,15 +48,15 @@
     "CANCEL_IN_PROGRESS",
     "COMPLETE",
     "FAILED",
     "IN_PROGRESS",
     "IN_PROGRESS_INITIALIZING",
 ]
 DataSourceType = Literal["EVENT", "EXTERNAL_MODEL_SCORE", "MODEL_SCORE"]
-DataTypeType = Literal["BOOLEAN", "FLOAT", "INTEGER", "STRING"]
+DataTypeType = Literal["BOOLEAN", "DATETIME", "FLOAT", "INTEGER", "STRING"]
 DetectorVersionStatusType = Literal["ACTIVE", "DRAFT", "INACTIVE"]
 EventIngestionType = Literal["DISABLED", "ENABLED"]
 LanguageType = Literal["DETECTORPL"]
 ListUpdateModeType = Literal["APPEND", "REMOVE", "REPLACE"]
 ModelEndpointStatusType = Literal["ASSOCIATED", "DISSOCIATED"]
 ModelInputDataFormatType = Literal["APPLICATION_JSON", "TEXT_CSV"]
 ModelOutputDataFormatType = Literal["APPLICATION_JSONLINES", "TEXT_CSV"]
@@ -127,14 +127,15 @@
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
@@ -213,14 +214,15 @@
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
@@ -231,14 +233,15 @@
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
@@ -274,14 +277,15 @@
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
@@ -300,16 +304,19 @@
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
@@ -393,15 +400,17 @@
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

### Comparing `types-aiobotocore-frauddetector-2.5.0.post1/types_aiobotocore_frauddetector/literals.pyi` & `types-aiobotocore-frauddetector-2.5.1/types_aiobotocore_frauddetector/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -46,15 +46,15 @@
     "CANCEL_IN_PROGRESS",
     "COMPLETE",
     "FAILED",
     "IN_PROGRESS",
     "IN_PROGRESS_INITIALIZING",
 ]
 DataSourceType = Literal["EVENT", "EXTERNAL_MODEL_SCORE", "MODEL_SCORE"]
-DataTypeType = Literal["BOOLEAN", "FLOAT", "INTEGER", "STRING"]
+DataTypeType = Literal["BOOLEAN", "DATETIME", "FLOAT", "INTEGER", "STRING"]
 DetectorVersionStatusType = Literal["ACTIVE", "DRAFT", "INACTIVE"]
 EventIngestionType = Literal["DISABLED", "ENABLED"]
 LanguageType = Literal["DETECTORPL"]
 ListUpdateModeType = Literal["APPEND", "REMOVE", "REPLACE"]
 ModelEndpointStatusType = Literal["ASSOCIATED", "DISSOCIATED"]
 ModelInputDataFormatType = Literal["APPLICATION_JSON", "TEXT_CSV"]
 ModelOutputDataFormatType = Literal["APPLICATION_JSONLINES", "TEXT_CSV"]
@@ -125,14 +125,15 @@
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
@@ -211,14 +212,15 @@
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
@@ -229,14 +231,15 @@
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
@@ -272,14 +275,15 @@
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
@@ -298,16 +302,19 @@
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
@@ -391,15 +398,17 @@
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

### Comparing `types-aiobotocore-frauddetector-2.5.0.post1/types_aiobotocore_frauddetector/type_defs.py` & `types-aiobotocore-frauddetector-2.5.1/types_aiobotocore_frauddetector/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -48,35 +48,37 @@
     "ATIModelPerformanceTypeDef",
     "AggregatedLogOddsMetricTypeDef",
     "AggregatedVariablesImpactExplanationTypeDef",
     "AllowDenyListTypeDef",
     "BatchCreateVariableErrorTypeDef",
     "TagTypeDef",
     "VariableEntryTypeDef",
-    "ResponseMetadataTypeDef",
     "BatchGetVariableErrorTypeDef",
     "BatchGetVariableRequestRequestTypeDef",
     "VariableTypeDef",
     "BatchImportTypeDef",
     "BatchPredictionTypeDef",
     "CancelBatchImportJobRequestRequestTypeDef",
     "CancelBatchPredictionJobRequestRequestTypeDef",
     "ModelVersionTypeDef",
     "RuleTypeDef",
+    "CreateDetectorVersionResultTypeDef",
     "ExternalEventsDetailTypeDef",
+    "CreateModelVersionResultTypeDef",
     "FieldValidationMessageTypeDef",
     "FileValidationMessageTypeDef",
     "DeleteBatchImportJobRequestRequestTypeDef",
     "DeleteBatchPredictionJobRequestRequestTypeDef",
     "DeleteDetectorRequestRequestTypeDef",
     "DeleteDetectorVersionRequestRequestTypeDef",
     "DeleteEntityTypeRequestRequestTypeDef",
     "DeleteEventRequestRequestTypeDef",
     "DeleteEventTypeRequestRequestTypeDef",
     "DeleteEventsByEventTypeRequestRequestTypeDef",
+    "DeleteEventsByEventTypeResultTypeDef",
     "DeleteExternalModelRequestRequestTypeDef",
     "DeleteLabelRequestRequestTypeDef",
     "DeleteListRequestRequestTypeDef",
     "DeleteModelRequestRequestTypeDef",
     "DeleteModelVersionRequestRequestTypeDef",
     "DeleteOutcomeRequestRequestTypeDef",
     "DeleteVariableRequestRequestTypeDef",
@@ -84,37 +86,40 @@
     "DetectorVersionSummaryTypeDef",
     "DescribeModelVersionsRequestRequestTypeDef",
     "DetectorTypeDef",
     "EntityTypeDef",
     "EntityTypeTypeDef",
     "EvaluatedExternalModelTypeDef",
     "EvaluatedRuleTypeDef",
+    "EventOrchestrationTypeDef",
     "EventPredictionSummaryTypeDef",
     "IngestedEventStatisticsTypeDef",
     "EventVariableSummaryTypeDef",
     "ExternalModelSummaryTypeDef",
     "ModelInputConfigurationTypeDef",
     "ModelOutputConfigurationTypeDef",
     "FilterConditionTypeDef",
     "GetBatchImportJobsRequestRequestTypeDef",
     "GetBatchPredictionJobsRequestRequestTypeDef",
     "GetDeleteEventsByEventTypeStatusRequestRequestTypeDef",
+    "GetDeleteEventsByEventTypeStatusResultTypeDef",
     "GetDetectorVersionRequestRequestTypeDef",
     "GetDetectorsRequestRequestTypeDef",
     "GetEntityTypesRequestRequestTypeDef",
     "GetEventPredictionMetadataRequestRequestTypeDef",
     "ModelEndpointDataBlobTypeDef",
     "RuleResultTypeDef",
     "GetEventRequestRequestTypeDef",
     "GetEventTypesRequestRequestTypeDef",
     "GetExternalModelsRequestRequestTypeDef",
     "KMSKeyTypeDef",
     "GetLabelsRequestRequestTypeDef",
     "LabelTypeDef",
     "GetListElementsRequestRequestTypeDef",
+    "GetListElementsResultTypeDef",
     "GetListsMetadataRequestRequestTypeDef",
     "GetModelVersionRequestRequestTypeDef",
     "GetModelsRequestRequestTypeDef",
     "ModelTypeDef",
     "GetOutcomesRequestRequestTypeDef",
     "OutcomeTypeDef",
     "GetRulesRequestRequestTypeDef",
@@ -126,47 +131,42 @@
     "ListTagsForResourceRequestRequestTypeDef",
     "LogOddsMetricTypeDef",
     "MetricDataPointTypeDef",
     "OFIMetricDataPointTypeDef",
     "UncertaintyRangeTypeDef",
     "VariableImpactExplanationTypeDef",
     "PutKMSEncryptionKeyRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "TFIMetricDataPointTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateDetectorVersionMetadataRequestRequestTypeDef",
     "UpdateDetectorVersionStatusRequestRequestTypeDef",
     "UpdateEventLabelRequestRequestTypeDef",
     "UpdateListRequestRequestTypeDef",
     "UpdateModelRequestRequestTypeDef",
+    "UpdateModelVersionResultTypeDef",
     "UpdateModelVersionStatusRequestRequestTypeDef",
     "UpdateVariableRequestRequestTypeDef",
     "ATITrainingMetricsValueTypeDef",
     "AggregatedVariablesImportanceMetricsTypeDef",
+    "GetListsMetadataResultTypeDef",
+    "BatchCreateVariableResultTypeDef",
     "CreateBatchImportJobRequestRequestTypeDef",
     "CreateBatchPredictionJobRequestRequestTypeDef",
     "CreateListRequestRequestTypeDef",
     "CreateModelRequestRequestTypeDef",
     "CreateRuleRequestRequestTypeDef",
     "CreateVariableRequestRequestTypeDef",
+    "ListTagsForResourceResultTypeDef",
     "PutDetectorRequestRequestTypeDef",
     "PutEntityTypeRequestRequestTypeDef",
-    "PutEventTypeRequestRequestTypeDef",
     "PutLabelRequestRequestTypeDef",
     "PutOutcomeRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "BatchCreateVariableRequestRequestTypeDef",
-    "BatchCreateVariableResultTypeDef",
-    "CreateDetectorVersionResultTypeDef",
-    "CreateModelVersionResultTypeDef",
-    "DeleteEventsByEventTypeResultTypeDef",
-    "GetDeleteEventsByEventTypeStatusResultTypeDef",
-    "GetListElementsResultTypeDef",
-    "GetListsMetadataResultTypeDef",
-    "ListTagsForResourceResultTypeDef",
-    "UpdateModelVersionResultTypeDef",
     "BatchGetVariableResultTypeDef",
     "GetVariablesResultTypeDef",
     "GetBatchImportJobsResultTypeDef",
     "GetBatchPredictionJobsResultTypeDef",
     "ModelScoresTypeDef",
     "CreateDetectorVersionRequestRequestTypeDef",
     "CreateRuleResultTypeDef",
@@ -178,14 +178,15 @@
     "UpdateRuleVersionResultTypeDef",
     "DataValidationMetricsTypeDef",
     "DescribeDetectorResultTypeDef",
     "GetDetectorsResultTypeDef",
     "EventTypeDef",
     "SendEventRequestRequestTypeDef",
     "GetEntityTypesResultTypeDef",
+    "PutEventTypeRequestRequestTypeDef",
     "ListEventPredictionsResultTypeDef",
     "EventTypeTypeDef",
     "ExternalModelOutputsTypeDef",
     "ExternalModelTypeDef",
     "PutExternalModelRequestRequestTypeDef",
     "GetEventPredictionRequestRequestTypeDef",
     "GetKMSEncryptionKeyResultTypeDef",
@@ -307,25 +308,14 @@
         "defaultValue": str,
         "description": str,
         "variableType": str,
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
 BatchGetVariableErrorTypeDef = TypedDict(
     "BatchGetVariableErrorTypeDef",
     {
         "name": str,
         "code": int,
         "message": str,
     },
@@ -437,22 +427,43 @@
     {
         "detectorId": str,
         "ruleId": str,
         "ruleVersion": str,
     },
 )
 
+CreateDetectorVersionResultTypeDef = TypedDict(
+    "CreateDetectorVersionResultTypeDef",
+    {
+        "detectorId": str,
+        "detectorVersionId": str,
+        "status": DetectorVersionStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ExternalEventsDetailTypeDef = TypedDict(
     "ExternalEventsDetailTypeDef",
     {
         "dataLocation": str,
         "dataAccessRoleArn": str,
     },
 )
 
+CreateModelVersionResultTypeDef = TypedDict(
+    "CreateModelVersionResultTypeDef",
+    {
+        "modelId": str,
+        "modelType": ModelTypeEnumType,
+        "modelVersionNumber": str,
+        "status": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 FieldValidationMessageTypeDef = TypedDict(
     "FieldValidationMessageTypeDef",
     {
         "fieldName": str,
         "identifier": str,
         "title": str,
         "content": str,
@@ -539,14 +550,23 @@
 DeleteEventsByEventTypeRequestRequestTypeDef = TypedDict(
     "DeleteEventsByEventTypeRequestRequestTypeDef",
     {
         "eventTypeName": str,
     },
 )
 
+DeleteEventsByEventTypeResultTypeDef = TypedDict(
+    "DeleteEventsByEventTypeResultTypeDef",
+    {
+        "eventTypeName": str,
+        "eventsDeletionStatus": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteExternalModelRequestRequestTypeDef = TypedDict(
     "DeleteExternalModelRequestRequestTypeDef",
     {
         "modelEndpoint": str,
     },
 )
 
@@ -694,14 +714,21 @@
         "outcomes": List[str],
         "evaluated": bool,
         "matched": bool,
     },
     total=False,
 )
 
+EventOrchestrationTypeDef = TypedDict(
+    "EventOrchestrationTypeDef",
+    {
+        "eventBridgeEnabled": bool,
+    },
+)
+
 EventPredictionSummaryTypeDef = TypedDict(
     "EventPredictionSummaryTypeDef",
     {
         "eventId": str,
         "eventTypeName": str,
         "eventTimestamp": str,
         "predictionTimestamp": str,
@@ -819,14 +846,23 @@
 GetDeleteEventsByEventTypeStatusRequestRequestTypeDef = TypedDict(
     "GetDeleteEventsByEventTypeStatusRequestRequestTypeDef",
     {
         "eventTypeName": str,
     },
 )
 
+GetDeleteEventsByEventTypeStatusResultTypeDef = TypedDict(
+    "GetDeleteEventsByEventTypeStatusResultTypeDef",
+    {
+        "eventTypeName": str,
+        "eventsDeletionStatus": AsyncJobStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetDetectorVersionRequestRequestTypeDef = TypedDict(
     "GetDetectorVersionRequestRequestTypeDef",
     {
         "detectorId": str,
         "detectorVersionId": str,
     },
 )
@@ -956,14 +992,23 @@
 
 class GetListElementsRequestRequestTypeDef(
     _RequiredGetListElementsRequestRequestTypeDef, _OptionalGetListElementsRequestRequestTypeDef
 ):
     pass
 
 
+GetListElementsResultTypeDef = TypedDict(
+    "GetListElementsResultTypeDef",
+    {
+        "elements": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetListsMetadataRequestRequestTypeDef = TypedDict(
     "GetListsMetadataRequestRequestTypeDef",
     {
         "name": str,
         "nextToken": str,
         "maxResults": int,
     },
@@ -1177,14 +1222,25 @@
 PutKMSEncryptionKeyRequestRequestTypeDef = TypedDict(
     "PutKMSEncryptionKeyRequestRequestTypeDef",
     {
         "kmsEncryptionKeyArn": str,
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
 TFIMetricDataPointTypeDef = TypedDict(
     "TFIMetricDataPointTypeDef",
     {
         "fpr": float,
         "precision": float,
         "tpr": float,
         "threshold": float,
@@ -1270,14 +1326,25 @@
 
 class UpdateModelRequestRequestTypeDef(
     _RequiredUpdateModelRequestRequestTypeDef, _OptionalUpdateModelRequestRequestTypeDef
 ):
     pass
 
 
+UpdateModelVersionResultTypeDef = TypedDict(
+    "UpdateModelVersionResultTypeDef",
+    {
+        "modelId": str,
+        "modelType": ModelTypeEnumType,
+        "modelVersionNumber": str,
+        "status": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateModelVersionStatusRequestRequestTypeDef = TypedDict(
     "UpdateModelVersionStatusRequestRequestTypeDef",
     {
         "modelId": str,
         "modelType": ModelTypeEnumType,
         "modelVersionNumber": str,
         "status": ModelVersionStatusType,
@@ -1320,14 +1387,31 @@
     "AggregatedVariablesImportanceMetricsTypeDef",
     {
         "logOddsMetrics": List[AggregatedLogOddsMetricTypeDef],
     },
     total=False,
 )
 
+GetListsMetadataResultTypeDef = TypedDict(
+    "GetListsMetadataResultTypeDef",
+    {
+        "lists": List[AllowDenyListTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+BatchCreateVariableResultTypeDef = TypedDict(
+    "BatchCreateVariableResultTypeDef",
+    {
+        "errors": List[BatchCreateVariableErrorTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateBatchImportJobRequestRequestTypeDef = TypedDict(
     "_RequiredCreateBatchImportJobRequestRequestTypeDef",
     {
         "jobId": str,
         "inputPath": str,
         "outputPath": str,
         "eventTypeName": str,
@@ -1474,14 +1558,23 @@
 
 class CreateVariableRequestRequestTypeDef(
     _RequiredCreateVariableRequestRequestTypeDef, _OptionalCreateVariableRequestRequestTypeDef
 ):
     pass
 
 
+ListTagsForResourceResultTypeDef = TypedDict(
+    "ListTagsForResourceResultTypeDef",
+    {
+        "tags": List[TagTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredPutDetectorRequestRequestTypeDef = TypedDict(
     "_RequiredPutDetectorRequestRequestTypeDef",
     {
         "detectorId": str,
         "eventTypeName": str,
     },
 )
@@ -1519,40 +1612,14 @@
 
 class PutEntityTypeRequestRequestTypeDef(
     _RequiredPutEntityTypeRequestRequestTypeDef, _OptionalPutEntityTypeRequestRequestTypeDef
 ):
     pass
 
 
-_RequiredPutEventTypeRequestRequestTypeDef = TypedDict(
-    "_RequiredPutEventTypeRequestRequestTypeDef",
-    {
-        "name": str,
-        "eventVariables": Sequence[str],
-        "entityTypes": Sequence[str],
-    },
-)
-_OptionalPutEventTypeRequestRequestTypeDef = TypedDict(
-    "_OptionalPutEventTypeRequestRequestTypeDef",
-    {
-        "description": str,
-        "labels": Sequence[str],
-        "eventIngestion": EventIngestionType,
-        "tags": Sequence[TagTypeDef],
-    },
-    total=False,
-)
-
-
-class PutEventTypeRequestRequestTypeDef(
-    _RequiredPutEventTypeRequestRequestTypeDef, _OptionalPutEventTypeRequestRequestTypeDef
-):
-    pass
-
-
 _RequiredPutLabelRequestRequestTypeDef = TypedDict(
     "_RequiredPutLabelRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalPutLabelRequestRequestTypeDef = TypedDict(
@@ -1619,132 +1686,47 @@
 class BatchCreateVariableRequestRequestTypeDef(
     _RequiredBatchCreateVariableRequestRequestTypeDef,
     _OptionalBatchCreateVariableRequestRequestTypeDef,
 ):
     pass
 
 
-BatchCreateVariableResultTypeDef = TypedDict(
-    "BatchCreateVariableResultTypeDef",
-    {
-        "errors": List[BatchCreateVariableErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDetectorVersionResultTypeDef = TypedDict(
-    "CreateDetectorVersionResultTypeDef",
-    {
-        "detectorId": str,
-        "detectorVersionId": str,
-        "status": DetectorVersionStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateModelVersionResultTypeDef = TypedDict(
-    "CreateModelVersionResultTypeDef",
-    {
-        "modelId": str,
-        "modelType": ModelTypeEnumType,
-        "modelVersionNumber": str,
-        "status": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteEventsByEventTypeResultTypeDef = TypedDict(
-    "DeleteEventsByEventTypeResultTypeDef",
-    {
-        "eventTypeName": str,
-        "eventsDeletionStatus": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetDeleteEventsByEventTypeStatusResultTypeDef = TypedDict(
-    "GetDeleteEventsByEventTypeStatusResultTypeDef",
-    {
-        "eventTypeName": str,
-        "eventsDeletionStatus": AsyncJobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetListElementsResultTypeDef = TypedDict(
-    "GetListElementsResultTypeDef",
-    {
-        "elements": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetListsMetadataResultTypeDef = TypedDict(
-    "GetListsMetadataResultTypeDef",
-    {
-        "lists": List[AllowDenyListTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResultTypeDef = TypedDict(
-    "ListTagsForResourceResultTypeDef",
-    {
-        "tags": List[TagTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateModelVersionResultTypeDef = TypedDict(
-    "UpdateModelVersionResultTypeDef",
-    {
-        "modelId": str,
-        "modelType": ModelTypeEnumType,
-        "modelVersionNumber": str,
-        "status": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 BatchGetVariableResultTypeDef = TypedDict(
     "BatchGetVariableResultTypeDef",
     {
         "variables": List[VariableTypeDef],
         "errors": List[BatchGetVariableErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetVariablesResultTypeDef = TypedDict(
     "GetVariablesResultTypeDef",
     {
         "variables": List[VariableTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetBatchImportJobsResultTypeDef = TypedDict(
     "GetBatchImportJobsResultTypeDef",
     {
         "batchImports": List[BatchImportTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetBatchPredictionJobsResultTypeDef = TypedDict(
     "GetBatchPredictionJobsResultTypeDef",
     {
         "batchPredictions": List[BatchPredictionTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModelScoresTypeDef = TypedDict(
     "ModelScoresTypeDef",
     {
         "modelVersion": ModelVersionTypeDef,
@@ -1780,15 +1762,15 @@
     pass
 
 
 CreateRuleResultTypeDef = TypedDict(
     "CreateRuleResultTypeDef",
     {
         "rule": RuleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteRuleRequestRequestTypeDef = TypedDict(
     "DeleteRuleRequestRequestTypeDef",
     {
         "rule": RuleTypeDef,
@@ -1805,15 +1787,15 @@
         "modelVersions": List[ModelVersionTypeDef],
         "rules": List[RuleTypeDef],
         "status": DetectorVersionStatusType,
         "lastUpdatedTime": str,
         "createdTime": str,
         "ruleExecutionMode": RuleExecutionModeType,
         "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateDetectorVersionRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateDetectorVersionRequestRequestTypeDef",
     {
         "detectorId": str,
@@ -1873,15 +1855,15 @@
     pass
 
 
 UpdateRuleVersionResultTypeDef = TypedDict(
     "UpdateRuleVersionResultTypeDef",
     {
         "rule": RuleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DataValidationMetricsTypeDef = TypedDict(
     "DataValidationMetricsTypeDef",
     {
         "fileLevelMessages": List[FileValidationMessageTypeDef],
@@ -1893,24 +1875,24 @@
 DescribeDetectorResultTypeDef = TypedDict(
     "DescribeDetectorResultTypeDef",
     {
         "detectorId": str,
         "detectorVersionSummaries": List[DetectorVersionSummaryTypeDef],
         "nextToken": str,
         "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDetectorsResultTypeDef = TypedDict(
     "GetDetectorsResultTypeDef",
     {
         "detectors": List[DetectorTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EventTypeDef = TypedDict(
     "EventTypeDef",
     {
         "eventId": str,
@@ -1951,24 +1933,51 @@
 
 
 GetEntityTypesResultTypeDef = TypedDict(
     "GetEntityTypesResultTypeDef",
     {
         "entityTypes": List[EntityTypeTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredPutEventTypeRequestRequestTypeDef = TypedDict(
+    "_RequiredPutEventTypeRequestRequestTypeDef",
+    {
+        "name": str,
+        "eventVariables": Sequence[str],
+        "entityTypes": Sequence[str],
     },
 )
+_OptionalPutEventTypeRequestRequestTypeDef = TypedDict(
+    "_OptionalPutEventTypeRequestRequestTypeDef",
+    {
+        "description": str,
+        "labels": Sequence[str],
+        "eventIngestion": EventIngestionType,
+        "tags": Sequence[TagTypeDef],
+        "eventOrchestration": EventOrchestrationTypeDef,
+    },
+    total=False,
+)
+
+
+class PutEventTypeRequestRequestTypeDef(
+    _RequiredPutEventTypeRequestRequestTypeDef, _OptionalPutEventTypeRequestRequestTypeDef
+):
+    pass
+
 
 ListEventPredictionsResultTypeDef = TypedDict(
     "ListEventPredictionsResultTypeDef",
     {
         "eventPredictionSummaries": List[EventPredictionSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EventTypeTypeDef = TypedDict(
     "EventTypeTypeDef",
     {
         "name": str,
@@ -1977,14 +1986,15 @@
         "labels": List[str],
         "entityTypes": List[str],
         "eventIngestion": EventIngestionType,
         "ingestedEventStatistics": IngestedEventStatisticsTypeDef,
         "lastUpdatedTime": str,
         "createdTime": str,
         "arn": str,
+        "eventOrchestration": EventOrchestrationTypeDef,
     },
     total=False,
 )
 
 ExternalModelOutputsTypeDef = TypedDict(
     "ExternalModelOutputsTypeDef",
     {
@@ -2064,51 +2074,51 @@
     pass
 
 
 GetKMSEncryptionKeyResultTypeDef = TypedDict(
     "GetKMSEncryptionKeyResultTypeDef",
     {
         "kmsKey": KMSKeyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetLabelsResultTypeDef = TypedDict(
     "GetLabelsResultTypeDef",
     {
         "labels": List[LabelTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetModelsResultTypeDef = TypedDict(
     "GetModelsResultTypeDef",
     {
         "nextToken": str,
         "models": List[ModelTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetOutcomesResultTypeDef = TypedDict(
     "GetOutcomesResultTypeDef",
     {
         "outcomes": List[OutcomeTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRulesResultTypeDef = TypedDict(
     "GetRulesResultTypeDef",
     {
         "ruleDetails": List[RuleDetailTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 IngestedEventsDetailTypeDef = TypedDict(
     "IngestedEventsDetailTypeDef",
     {
         "ingestedEventsTimeWindow": IngestedEventsTimeWindowTypeDef,
@@ -2194,43 +2204,43 @@
     total=False,
 )
 
 GetEventResultTypeDef = TypedDict(
     "GetEventResultTypeDef",
     {
         "event": EventTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetEventTypesResultTypeDef = TypedDict(
     "GetEventTypesResultTypeDef",
     {
         "eventTypes": List[EventTypeTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetEventPredictionResultTypeDef = TypedDict(
     "GetEventPredictionResultTypeDef",
     {
         "modelScores": List[ModelScoresTypeDef],
         "ruleResults": List[RuleResultTypeDef],
         "externalModelOutputs": List[ExternalModelOutputsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetExternalModelsResultTypeDef = TypedDict(
     "GetExternalModelsResultTypeDef",
     {
         "externalModels": List[ExternalModelTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateModelVersionRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateModelVersionRequestRequestTypeDef",
     {
         "modelId": str,
@@ -2291,15 +2301,15 @@
         "modelVersionNumber": str,
         "trainingDataSource": TrainingDataSourceEnumType,
         "trainingDataSchema": TrainingDataSchemaTypeDef,
         "externalEventsDetail": ExternalEventsDetailTypeDef,
         "ingestedEventsDetail": IngestedEventsDetailTypeDef,
         "status": str,
         "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TrainingResultTypeDef = TypedDict(
     "TrainingResultTypeDef",
     {
         "dataValidationMetrics": DataValidationMetricsTypeDef,
@@ -2383,15 +2393,15 @@
         "eventVariables": List[EventVariableSummaryTypeDef],
         "rules": List[EvaluatedRuleTypeDef],
         "ruleExecutionMode": RuleExecutionModeType,
         "outcomes": List[str],
         "evaluatedModelVersions": List[EvaluatedModelVersionTypeDef],
         "evaluatedExternalModels": List[EvaluatedExternalModelTypeDef],
         "predictionTimestamp": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModelVersionDetailTypeDef = TypedDict(
     "ModelVersionDetailTypeDef",
     {
         "modelId": str,
@@ -2412,10 +2422,10 @@
 )
 
 DescribeModelVersionsResultTypeDef = TypedDict(
     "DescribeModelVersionsResultTypeDef",
     {
         "modelVersionDetails": List[ModelVersionDetailTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-frauddetector-2.5.0.post1/types_aiobotocore_frauddetector/type_defs.pyi` & `types-aiobotocore-frauddetector-2.5.1/types_aiobotocore_frauddetector/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -47,35 +47,37 @@
     "ATIModelPerformanceTypeDef",
     "AggregatedLogOddsMetricTypeDef",
     "AggregatedVariablesImpactExplanationTypeDef",
     "AllowDenyListTypeDef",
     "BatchCreateVariableErrorTypeDef",
     "TagTypeDef",
     "VariableEntryTypeDef",
-    "ResponseMetadataTypeDef",
     "BatchGetVariableErrorTypeDef",
     "BatchGetVariableRequestRequestTypeDef",
     "VariableTypeDef",
     "BatchImportTypeDef",
     "BatchPredictionTypeDef",
     "CancelBatchImportJobRequestRequestTypeDef",
     "CancelBatchPredictionJobRequestRequestTypeDef",
     "ModelVersionTypeDef",
     "RuleTypeDef",
+    "CreateDetectorVersionResultTypeDef",
     "ExternalEventsDetailTypeDef",
+    "CreateModelVersionResultTypeDef",
     "FieldValidationMessageTypeDef",
     "FileValidationMessageTypeDef",
     "DeleteBatchImportJobRequestRequestTypeDef",
     "DeleteBatchPredictionJobRequestRequestTypeDef",
     "DeleteDetectorRequestRequestTypeDef",
     "DeleteDetectorVersionRequestRequestTypeDef",
     "DeleteEntityTypeRequestRequestTypeDef",
     "DeleteEventRequestRequestTypeDef",
     "DeleteEventTypeRequestRequestTypeDef",
     "DeleteEventsByEventTypeRequestRequestTypeDef",
+    "DeleteEventsByEventTypeResultTypeDef",
     "DeleteExternalModelRequestRequestTypeDef",
     "DeleteLabelRequestRequestTypeDef",
     "DeleteListRequestRequestTypeDef",
     "DeleteModelRequestRequestTypeDef",
     "DeleteModelVersionRequestRequestTypeDef",
     "DeleteOutcomeRequestRequestTypeDef",
     "DeleteVariableRequestRequestTypeDef",
@@ -83,37 +85,40 @@
     "DetectorVersionSummaryTypeDef",
     "DescribeModelVersionsRequestRequestTypeDef",
     "DetectorTypeDef",
     "EntityTypeDef",
     "EntityTypeTypeDef",
     "EvaluatedExternalModelTypeDef",
     "EvaluatedRuleTypeDef",
+    "EventOrchestrationTypeDef",
     "EventPredictionSummaryTypeDef",
     "IngestedEventStatisticsTypeDef",
     "EventVariableSummaryTypeDef",
     "ExternalModelSummaryTypeDef",
     "ModelInputConfigurationTypeDef",
     "ModelOutputConfigurationTypeDef",
     "FilterConditionTypeDef",
     "GetBatchImportJobsRequestRequestTypeDef",
     "GetBatchPredictionJobsRequestRequestTypeDef",
     "GetDeleteEventsByEventTypeStatusRequestRequestTypeDef",
+    "GetDeleteEventsByEventTypeStatusResultTypeDef",
     "GetDetectorVersionRequestRequestTypeDef",
     "GetDetectorsRequestRequestTypeDef",
     "GetEntityTypesRequestRequestTypeDef",
     "GetEventPredictionMetadataRequestRequestTypeDef",
     "ModelEndpointDataBlobTypeDef",
     "RuleResultTypeDef",
     "GetEventRequestRequestTypeDef",
     "GetEventTypesRequestRequestTypeDef",
     "GetExternalModelsRequestRequestTypeDef",
     "KMSKeyTypeDef",
     "GetLabelsRequestRequestTypeDef",
     "LabelTypeDef",
     "GetListElementsRequestRequestTypeDef",
+    "GetListElementsResultTypeDef",
     "GetListsMetadataRequestRequestTypeDef",
     "GetModelVersionRequestRequestTypeDef",
     "GetModelsRequestRequestTypeDef",
     "ModelTypeDef",
     "GetOutcomesRequestRequestTypeDef",
     "OutcomeTypeDef",
     "GetRulesRequestRequestTypeDef",
@@ -125,47 +130,42 @@
     "ListTagsForResourceRequestRequestTypeDef",
     "LogOddsMetricTypeDef",
     "MetricDataPointTypeDef",
     "OFIMetricDataPointTypeDef",
     "UncertaintyRangeTypeDef",
     "VariableImpactExplanationTypeDef",
     "PutKMSEncryptionKeyRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "TFIMetricDataPointTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateDetectorVersionMetadataRequestRequestTypeDef",
     "UpdateDetectorVersionStatusRequestRequestTypeDef",
     "UpdateEventLabelRequestRequestTypeDef",
     "UpdateListRequestRequestTypeDef",
     "UpdateModelRequestRequestTypeDef",
+    "UpdateModelVersionResultTypeDef",
     "UpdateModelVersionStatusRequestRequestTypeDef",
     "UpdateVariableRequestRequestTypeDef",
     "ATITrainingMetricsValueTypeDef",
     "AggregatedVariablesImportanceMetricsTypeDef",
+    "GetListsMetadataResultTypeDef",
+    "BatchCreateVariableResultTypeDef",
     "CreateBatchImportJobRequestRequestTypeDef",
     "CreateBatchPredictionJobRequestRequestTypeDef",
     "CreateListRequestRequestTypeDef",
     "CreateModelRequestRequestTypeDef",
     "CreateRuleRequestRequestTypeDef",
     "CreateVariableRequestRequestTypeDef",
+    "ListTagsForResourceResultTypeDef",
     "PutDetectorRequestRequestTypeDef",
     "PutEntityTypeRequestRequestTypeDef",
-    "PutEventTypeRequestRequestTypeDef",
     "PutLabelRequestRequestTypeDef",
     "PutOutcomeRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "BatchCreateVariableRequestRequestTypeDef",
-    "BatchCreateVariableResultTypeDef",
-    "CreateDetectorVersionResultTypeDef",
-    "CreateModelVersionResultTypeDef",
-    "DeleteEventsByEventTypeResultTypeDef",
-    "GetDeleteEventsByEventTypeStatusResultTypeDef",
-    "GetListElementsResultTypeDef",
-    "GetListsMetadataResultTypeDef",
-    "ListTagsForResourceResultTypeDef",
-    "UpdateModelVersionResultTypeDef",
     "BatchGetVariableResultTypeDef",
     "GetVariablesResultTypeDef",
     "GetBatchImportJobsResultTypeDef",
     "GetBatchPredictionJobsResultTypeDef",
     "ModelScoresTypeDef",
     "CreateDetectorVersionRequestRequestTypeDef",
     "CreateRuleResultTypeDef",
@@ -177,14 +177,15 @@
     "UpdateRuleVersionResultTypeDef",
     "DataValidationMetricsTypeDef",
     "DescribeDetectorResultTypeDef",
     "GetDetectorsResultTypeDef",
     "EventTypeDef",
     "SendEventRequestRequestTypeDef",
     "GetEntityTypesResultTypeDef",
+    "PutEventTypeRequestRequestTypeDef",
     "ListEventPredictionsResultTypeDef",
     "EventTypeTypeDef",
     "ExternalModelOutputsTypeDef",
     "ExternalModelTypeDef",
     "PutExternalModelRequestRequestTypeDef",
     "GetEventPredictionRequestRequestTypeDef",
     "GetKMSEncryptionKeyResultTypeDef",
@@ -304,25 +305,14 @@
         "defaultValue": str,
         "description": str,
         "variableType": str,
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
 BatchGetVariableErrorTypeDef = TypedDict(
     "BatchGetVariableErrorTypeDef",
     {
         "name": str,
         "code": int,
         "message": str,
     },
@@ -432,22 +422,43 @@
     {
         "detectorId": str,
         "ruleId": str,
         "ruleVersion": str,
     },
 )
 
+CreateDetectorVersionResultTypeDef = TypedDict(
+    "CreateDetectorVersionResultTypeDef",
+    {
+        "detectorId": str,
+        "detectorVersionId": str,
+        "status": DetectorVersionStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ExternalEventsDetailTypeDef = TypedDict(
     "ExternalEventsDetailTypeDef",
     {
         "dataLocation": str,
         "dataAccessRoleArn": str,
     },
 )
 
+CreateModelVersionResultTypeDef = TypedDict(
+    "CreateModelVersionResultTypeDef",
+    {
+        "modelId": str,
+        "modelType": ModelTypeEnumType,
+        "modelVersionNumber": str,
+        "status": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 FieldValidationMessageTypeDef = TypedDict(
     "FieldValidationMessageTypeDef",
     {
         "fieldName": str,
         "identifier": str,
         "title": str,
         "content": str,
@@ -532,14 +543,23 @@
 DeleteEventsByEventTypeRequestRequestTypeDef = TypedDict(
     "DeleteEventsByEventTypeRequestRequestTypeDef",
     {
         "eventTypeName": str,
     },
 )
 
+DeleteEventsByEventTypeResultTypeDef = TypedDict(
+    "DeleteEventsByEventTypeResultTypeDef",
+    {
+        "eventTypeName": str,
+        "eventsDeletionStatus": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteExternalModelRequestRequestTypeDef = TypedDict(
     "DeleteExternalModelRequestRequestTypeDef",
     {
         "modelEndpoint": str,
     },
 )
 
@@ -685,14 +705,21 @@
         "outcomes": List[str],
         "evaluated": bool,
         "matched": bool,
     },
     total=False,
 )
 
+EventOrchestrationTypeDef = TypedDict(
+    "EventOrchestrationTypeDef",
+    {
+        "eventBridgeEnabled": bool,
+    },
+)
+
 EventPredictionSummaryTypeDef = TypedDict(
     "EventPredictionSummaryTypeDef",
     {
         "eventId": str,
         "eventTypeName": str,
         "eventTimestamp": str,
         "predictionTimestamp": str,
@@ -806,14 +833,23 @@
 GetDeleteEventsByEventTypeStatusRequestRequestTypeDef = TypedDict(
     "GetDeleteEventsByEventTypeStatusRequestRequestTypeDef",
     {
         "eventTypeName": str,
     },
 )
 
+GetDeleteEventsByEventTypeStatusResultTypeDef = TypedDict(
+    "GetDeleteEventsByEventTypeStatusResultTypeDef",
+    {
+        "eventTypeName": str,
+        "eventsDeletionStatus": AsyncJobStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetDetectorVersionRequestRequestTypeDef = TypedDict(
     "GetDetectorVersionRequestRequestTypeDef",
     {
         "detectorId": str,
         "detectorVersionId": str,
     },
 )
@@ -941,14 +977,23 @@
 )
 
 class GetListElementsRequestRequestTypeDef(
     _RequiredGetListElementsRequestRequestTypeDef, _OptionalGetListElementsRequestRequestTypeDef
 ):
     pass
 
+GetListElementsResultTypeDef = TypedDict(
+    "GetListElementsResultTypeDef",
+    {
+        "elements": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetListsMetadataRequestRequestTypeDef = TypedDict(
     "GetListsMetadataRequestRequestTypeDef",
     {
         "name": str,
         "nextToken": str,
         "maxResults": int,
     },
@@ -1158,14 +1203,25 @@
 PutKMSEncryptionKeyRequestRequestTypeDef = TypedDict(
     "PutKMSEncryptionKeyRequestRequestTypeDef",
     {
         "kmsEncryptionKeyArn": str,
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
 TFIMetricDataPointTypeDef = TypedDict(
     "TFIMetricDataPointTypeDef",
     {
         "fpr": float,
         "precision": float,
         "tpr": float,
         "threshold": float,
@@ -1247,14 +1303,25 @@
 )
 
 class UpdateModelRequestRequestTypeDef(
     _RequiredUpdateModelRequestRequestTypeDef, _OptionalUpdateModelRequestRequestTypeDef
 ):
     pass
 
+UpdateModelVersionResultTypeDef = TypedDict(
+    "UpdateModelVersionResultTypeDef",
+    {
+        "modelId": str,
+        "modelType": ModelTypeEnumType,
+        "modelVersionNumber": str,
+        "status": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateModelVersionStatusRequestRequestTypeDef = TypedDict(
     "UpdateModelVersionStatusRequestRequestTypeDef",
     {
         "modelId": str,
         "modelType": ModelTypeEnumType,
         "modelVersionNumber": str,
         "status": ModelVersionStatusType,
@@ -1295,14 +1362,31 @@
     "AggregatedVariablesImportanceMetricsTypeDef",
     {
         "logOddsMetrics": List[AggregatedLogOddsMetricTypeDef],
     },
     total=False,
 )
 
+GetListsMetadataResultTypeDef = TypedDict(
+    "GetListsMetadataResultTypeDef",
+    {
+        "lists": List[AllowDenyListTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+BatchCreateVariableResultTypeDef = TypedDict(
+    "BatchCreateVariableResultTypeDef",
+    {
+        "errors": List[BatchCreateVariableErrorTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateBatchImportJobRequestRequestTypeDef = TypedDict(
     "_RequiredCreateBatchImportJobRequestRequestTypeDef",
     {
         "jobId": str,
         "inputPath": str,
         "outputPath": str,
         "eventTypeName": str,
@@ -1437,14 +1521,23 @@
 )
 
 class CreateVariableRequestRequestTypeDef(
     _RequiredCreateVariableRequestRequestTypeDef, _OptionalCreateVariableRequestRequestTypeDef
 ):
     pass
 
+ListTagsForResourceResultTypeDef = TypedDict(
+    "ListTagsForResourceResultTypeDef",
+    {
+        "tags": List[TagTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredPutDetectorRequestRequestTypeDef = TypedDict(
     "_RequiredPutDetectorRequestRequestTypeDef",
     {
         "detectorId": str,
         "eventTypeName": str,
     },
 )
@@ -1478,38 +1571,14 @@
 )
 
 class PutEntityTypeRequestRequestTypeDef(
     _RequiredPutEntityTypeRequestRequestTypeDef, _OptionalPutEntityTypeRequestRequestTypeDef
 ):
     pass
 
-_RequiredPutEventTypeRequestRequestTypeDef = TypedDict(
-    "_RequiredPutEventTypeRequestRequestTypeDef",
-    {
-        "name": str,
-        "eventVariables": Sequence[str],
-        "entityTypes": Sequence[str],
-    },
-)
-_OptionalPutEventTypeRequestRequestTypeDef = TypedDict(
-    "_OptionalPutEventTypeRequestRequestTypeDef",
-    {
-        "description": str,
-        "labels": Sequence[str],
-        "eventIngestion": EventIngestionType,
-        "tags": Sequence[TagTypeDef],
-    },
-    total=False,
-)
-
-class PutEventTypeRequestRequestTypeDef(
-    _RequiredPutEventTypeRequestRequestTypeDef, _OptionalPutEventTypeRequestRequestTypeDef
-):
-    pass
-
 _RequiredPutLabelRequestRequestTypeDef = TypedDict(
     "_RequiredPutLabelRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalPutLabelRequestRequestTypeDef = TypedDict(
@@ -1570,132 +1639,47 @@
 
 class BatchCreateVariableRequestRequestTypeDef(
     _RequiredBatchCreateVariableRequestRequestTypeDef,
     _OptionalBatchCreateVariableRequestRequestTypeDef,
 ):
     pass
 
-BatchCreateVariableResultTypeDef = TypedDict(
-    "BatchCreateVariableResultTypeDef",
-    {
-        "errors": List[BatchCreateVariableErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDetectorVersionResultTypeDef = TypedDict(
-    "CreateDetectorVersionResultTypeDef",
-    {
-        "detectorId": str,
-        "detectorVersionId": str,
-        "status": DetectorVersionStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateModelVersionResultTypeDef = TypedDict(
-    "CreateModelVersionResultTypeDef",
-    {
-        "modelId": str,
-        "modelType": ModelTypeEnumType,
-        "modelVersionNumber": str,
-        "status": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteEventsByEventTypeResultTypeDef = TypedDict(
-    "DeleteEventsByEventTypeResultTypeDef",
-    {
-        "eventTypeName": str,
-        "eventsDeletionStatus": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetDeleteEventsByEventTypeStatusResultTypeDef = TypedDict(
-    "GetDeleteEventsByEventTypeStatusResultTypeDef",
-    {
-        "eventTypeName": str,
-        "eventsDeletionStatus": AsyncJobStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetListElementsResultTypeDef = TypedDict(
-    "GetListElementsResultTypeDef",
-    {
-        "elements": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetListsMetadataResultTypeDef = TypedDict(
-    "GetListsMetadataResultTypeDef",
-    {
-        "lists": List[AllowDenyListTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResultTypeDef = TypedDict(
-    "ListTagsForResourceResultTypeDef",
-    {
-        "tags": List[TagTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateModelVersionResultTypeDef = TypedDict(
-    "UpdateModelVersionResultTypeDef",
-    {
-        "modelId": str,
-        "modelType": ModelTypeEnumType,
-        "modelVersionNumber": str,
-        "status": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 BatchGetVariableResultTypeDef = TypedDict(
     "BatchGetVariableResultTypeDef",
     {
         "variables": List[VariableTypeDef],
         "errors": List[BatchGetVariableErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetVariablesResultTypeDef = TypedDict(
     "GetVariablesResultTypeDef",
     {
         "variables": List[VariableTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetBatchImportJobsResultTypeDef = TypedDict(
     "GetBatchImportJobsResultTypeDef",
     {
         "batchImports": List[BatchImportTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetBatchPredictionJobsResultTypeDef = TypedDict(
     "GetBatchPredictionJobsResultTypeDef",
     {
         "batchPredictions": List[BatchPredictionTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModelScoresTypeDef = TypedDict(
     "ModelScoresTypeDef",
     {
         "modelVersion": ModelVersionTypeDef,
@@ -1729,15 +1713,15 @@
 ):
     pass
 
 CreateRuleResultTypeDef = TypedDict(
     "CreateRuleResultTypeDef",
     {
         "rule": RuleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteRuleRequestRequestTypeDef = TypedDict(
     "DeleteRuleRequestRequestTypeDef",
     {
         "rule": RuleTypeDef,
@@ -1754,15 +1738,15 @@
         "modelVersions": List[ModelVersionTypeDef],
         "rules": List[RuleTypeDef],
         "status": DetectorVersionStatusType,
         "lastUpdatedTime": str,
         "createdTime": str,
         "ruleExecutionMode": RuleExecutionModeType,
         "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateDetectorVersionRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateDetectorVersionRequestRequestTypeDef",
     {
         "detectorId": str,
@@ -1818,15 +1802,15 @@
 ):
     pass
 
 UpdateRuleVersionResultTypeDef = TypedDict(
     "UpdateRuleVersionResultTypeDef",
     {
         "rule": RuleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DataValidationMetricsTypeDef = TypedDict(
     "DataValidationMetricsTypeDef",
     {
         "fileLevelMessages": List[FileValidationMessageTypeDef],
@@ -1838,24 +1822,24 @@
 DescribeDetectorResultTypeDef = TypedDict(
     "DescribeDetectorResultTypeDef",
     {
         "detectorId": str,
         "detectorVersionSummaries": List[DetectorVersionSummaryTypeDef],
         "nextToken": str,
         "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDetectorsResultTypeDef = TypedDict(
     "GetDetectorsResultTypeDef",
     {
         "detectors": List[DetectorTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EventTypeDef = TypedDict(
     "EventTypeDef",
     {
         "eventId": str,
@@ -1894,24 +1878,49 @@
     pass
 
 GetEntityTypesResultTypeDef = TypedDict(
     "GetEntityTypesResultTypeDef",
     {
         "entityTypes": List[EntityTypeTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredPutEventTypeRequestRequestTypeDef = TypedDict(
+    "_RequiredPutEventTypeRequestRequestTypeDef",
+    {
+        "name": str,
+        "eventVariables": Sequence[str],
+        "entityTypes": Sequence[str],
     },
 )
+_OptionalPutEventTypeRequestRequestTypeDef = TypedDict(
+    "_OptionalPutEventTypeRequestRequestTypeDef",
+    {
+        "description": str,
+        "labels": Sequence[str],
+        "eventIngestion": EventIngestionType,
+        "tags": Sequence[TagTypeDef],
+        "eventOrchestration": EventOrchestrationTypeDef,
+    },
+    total=False,
+)
+
+class PutEventTypeRequestRequestTypeDef(
+    _RequiredPutEventTypeRequestRequestTypeDef, _OptionalPutEventTypeRequestRequestTypeDef
+):
+    pass
 
 ListEventPredictionsResultTypeDef = TypedDict(
     "ListEventPredictionsResultTypeDef",
     {
         "eventPredictionSummaries": List[EventPredictionSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EventTypeTypeDef = TypedDict(
     "EventTypeTypeDef",
     {
         "name": str,
@@ -1920,14 +1929,15 @@
         "labels": List[str],
         "entityTypes": List[str],
         "eventIngestion": EventIngestionType,
         "ingestedEventStatistics": IngestedEventStatisticsTypeDef,
         "lastUpdatedTime": str,
         "createdTime": str,
         "arn": str,
+        "eventOrchestration": EventOrchestrationTypeDef,
     },
     total=False,
 )
 
 ExternalModelOutputsTypeDef = TypedDict(
     "ExternalModelOutputsTypeDef",
     {
@@ -2003,51 +2013,51 @@
 ):
     pass
 
 GetKMSEncryptionKeyResultTypeDef = TypedDict(
     "GetKMSEncryptionKeyResultTypeDef",
     {
         "kmsKey": KMSKeyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetLabelsResultTypeDef = TypedDict(
     "GetLabelsResultTypeDef",
     {
         "labels": List[LabelTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetModelsResultTypeDef = TypedDict(
     "GetModelsResultTypeDef",
     {
         "nextToken": str,
         "models": List[ModelTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetOutcomesResultTypeDef = TypedDict(
     "GetOutcomesResultTypeDef",
     {
         "outcomes": List[OutcomeTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRulesResultTypeDef = TypedDict(
     "GetRulesResultTypeDef",
     {
         "ruleDetails": List[RuleDetailTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 IngestedEventsDetailTypeDef = TypedDict(
     "IngestedEventsDetailTypeDef",
     {
         "ingestedEventsTimeWindow": IngestedEventsTimeWindowTypeDef,
@@ -2131,43 +2141,43 @@
     total=False,
 )
 
 GetEventResultTypeDef = TypedDict(
     "GetEventResultTypeDef",
     {
         "event": EventTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetEventTypesResultTypeDef = TypedDict(
     "GetEventTypesResultTypeDef",
     {
         "eventTypes": List[EventTypeTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetEventPredictionResultTypeDef = TypedDict(
     "GetEventPredictionResultTypeDef",
     {
         "modelScores": List[ModelScoresTypeDef],
         "ruleResults": List[RuleResultTypeDef],
         "externalModelOutputs": List[ExternalModelOutputsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetExternalModelsResultTypeDef = TypedDict(
     "GetExternalModelsResultTypeDef",
     {
         "externalModels": List[ExternalModelTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateModelVersionRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateModelVersionRequestRequestTypeDef",
     {
         "modelId": str,
@@ -2224,15 +2234,15 @@
         "modelVersionNumber": str,
         "trainingDataSource": TrainingDataSourceEnumType,
         "trainingDataSchema": TrainingDataSchemaTypeDef,
         "externalEventsDetail": ExternalEventsDetailTypeDef,
         "ingestedEventsDetail": IngestedEventsDetailTypeDef,
         "status": str,
         "arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TrainingResultTypeDef = TypedDict(
     "TrainingResultTypeDef",
     {
         "dataValidationMetrics": DataValidationMetricsTypeDef,
@@ -2316,15 +2326,15 @@
         "eventVariables": List[EventVariableSummaryTypeDef],
         "rules": List[EvaluatedRuleTypeDef],
         "ruleExecutionMode": RuleExecutionModeType,
         "outcomes": List[str],
         "evaluatedModelVersions": List[EvaluatedModelVersionTypeDef],
         "evaluatedExternalModels": List[EvaluatedExternalModelTypeDef],
         "predictionTimestamp": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ModelVersionDetailTypeDef = TypedDict(
     "ModelVersionDetailTypeDef",
     {
         "modelId": str,
@@ -2345,10 +2355,10 @@
 )
 
 DescribeModelVersionsResultTypeDef = TypedDict(
     "DescribeModelVersionsResultTypeDef",
     {
         "modelVersionDetails": List[ModelVersionDetailTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-frauddetector-2.5.0.post1/types_aiobotocore_frauddetector.egg-info/PKG-INFO` & `types-aiobotocore-frauddetector-2.5.1/types_aiobotocore_frauddetector.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-frauddetector
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.FraudDetector 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.FraudDetector 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_frauddetector/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-frauddetector"></a>
 
 # types-aiobotocore-frauddetector
 
 [![PyPI - types-aiobotocore-frauddetector](https://img.shields.io/pypi/v/types-aiobotocore-frauddetector.svg?color=blue)](https://pypi.org/project/types-aiobotocore-frauddetector)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-frauddetector.svg?color=blue)](https://pypi.org/project/types-aiobotocore-frauddetector)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_frauddetector/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-frauddetector?color=blue)](https://pypistats.org/packages/types-aiobotocore-frauddetector)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.FraudDetector 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/frauddetector.html#FraudDetector)
+[aiobotocore.FraudDetector 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/frauddetector.html#FraudDetector)
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
 [types-aiobotocore-frauddetector docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_frauddetector/).
 
 See how it helps to find and fix potential bugs:
 
@@ -313,35 +313,37 @@
     ATIModelPerformanceTypeDef,
     AggregatedLogOddsMetricTypeDef,
     AggregatedVariablesImpactExplanationTypeDef,
     AllowDenyListTypeDef,
     BatchCreateVariableErrorTypeDef,
     TagTypeDef,
     VariableEntryTypeDef,
-    ResponseMetadataTypeDef,
     BatchGetVariableErrorTypeDef,
     BatchGetVariableRequestRequestTypeDef,
     VariableTypeDef,
     BatchImportTypeDef,
     BatchPredictionTypeDef,
     CancelBatchImportJobRequestRequestTypeDef,
     CancelBatchPredictionJobRequestRequestTypeDef,
     ModelVersionTypeDef,
     RuleTypeDef,
+    CreateDetectorVersionResultTypeDef,
     ExternalEventsDetailTypeDef,
+    CreateModelVersionResultTypeDef,
     FieldValidationMessageTypeDef,
     FileValidationMessageTypeDef,
     DeleteBatchImportJobRequestRequestTypeDef,
     DeleteBatchPredictionJobRequestRequestTypeDef,
     DeleteDetectorRequestRequestTypeDef,
     DeleteDetectorVersionRequestRequestTypeDef,
     DeleteEntityTypeRequestRequestTypeDef,
     DeleteEventRequestRequestTypeDef,
     DeleteEventTypeRequestRequestTypeDef,
     DeleteEventsByEventTypeRequestRequestTypeDef,
+    DeleteEventsByEventTypeResultTypeDef,
     DeleteExternalModelRequestRequestTypeDef,
     DeleteLabelRequestRequestTypeDef,
     DeleteListRequestRequestTypeDef,
     DeleteModelRequestRequestTypeDef,
     DeleteModelVersionRequestRequestTypeDef,
     DeleteOutcomeRequestRequestTypeDef,
     DeleteVariableRequestRequestTypeDef,
@@ -349,37 +351,40 @@
     DetectorVersionSummaryTypeDef,
     DescribeModelVersionsRequestRequestTypeDef,
     DetectorTypeDef,
     EntityTypeDef,
     EntityTypeTypeDef,
     EvaluatedExternalModelTypeDef,
     EvaluatedRuleTypeDef,
+    EventOrchestrationTypeDef,
     EventPredictionSummaryTypeDef,
     IngestedEventStatisticsTypeDef,
     EventVariableSummaryTypeDef,
     ExternalModelSummaryTypeDef,
     ModelInputConfigurationTypeDef,
     ModelOutputConfigurationTypeDef,
     FilterConditionTypeDef,
     GetBatchImportJobsRequestRequestTypeDef,
     GetBatchPredictionJobsRequestRequestTypeDef,
     GetDeleteEventsByEventTypeStatusRequestRequestTypeDef,
+    GetDeleteEventsByEventTypeStatusResultTypeDef,
     GetDetectorVersionRequestRequestTypeDef,
     GetDetectorsRequestRequestTypeDef,
     GetEntityTypesRequestRequestTypeDef,
     GetEventPredictionMetadataRequestRequestTypeDef,
     ModelEndpointDataBlobTypeDef,
     RuleResultTypeDef,
     GetEventRequestRequestTypeDef,
     GetEventTypesRequestRequestTypeDef,
     GetExternalModelsRequestRequestTypeDef,
     KMSKeyTypeDef,
     GetLabelsRequestRequestTypeDef,
     LabelTypeDef,
     GetListElementsRequestRequestTypeDef,
+    GetListElementsResultTypeDef,
     GetListsMetadataRequestRequestTypeDef,
     GetModelVersionRequestRequestTypeDef,
     GetModelsRequestRequestTypeDef,
     ModelTypeDef,
     GetOutcomesRequestRequestTypeDef,
     OutcomeTypeDef,
     GetRulesRequestRequestTypeDef,
@@ -391,47 +396,42 @@
     ListTagsForResourceRequestRequestTypeDef,
     LogOddsMetricTypeDef,
     MetricDataPointTypeDef,
     OFIMetricDataPointTypeDef,
     UncertaintyRangeTypeDef,
     VariableImpactExplanationTypeDef,
     PutKMSEncryptionKeyRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     TFIMetricDataPointTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateDetectorVersionMetadataRequestRequestTypeDef,
     UpdateDetectorVersionStatusRequestRequestTypeDef,
     UpdateEventLabelRequestRequestTypeDef,
     UpdateListRequestRequestTypeDef,
     UpdateModelRequestRequestTypeDef,
+    UpdateModelVersionResultTypeDef,
     UpdateModelVersionStatusRequestRequestTypeDef,
     UpdateVariableRequestRequestTypeDef,
     ATITrainingMetricsValueTypeDef,
     AggregatedVariablesImportanceMetricsTypeDef,
+    GetListsMetadataResultTypeDef,
+    BatchCreateVariableResultTypeDef,
     CreateBatchImportJobRequestRequestTypeDef,
     CreateBatchPredictionJobRequestRequestTypeDef,
     CreateListRequestRequestTypeDef,
     CreateModelRequestRequestTypeDef,
     CreateRuleRequestRequestTypeDef,
     CreateVariableRequestRequestTypeDef,
+    ListTagsForResourceResultTypeDef,
     PutDetectorRequestRequestTypeDef,
     PutEntityTypeRequestRequestTypeDef,
-    PutEventTypeRequestRequestTypeDef,
     PutLabelRequestRequestTypeDef,
     PutOutcomeRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     BatchCreateVariableRequestRequestTypeDef,
-    BatchCreateVariableResultTypeDef,
-    CreateDetectorVersionResultTypeDef,
-    CreateModelVersionResultTypeDef,
-    DeleteEventsByEventTypeResultTypeDef,
-    GetDeleteEventsByEventTypeStatusResultTypeDef,
-    GetListElementsResultTypeDef,
-    GetListsMetadataResultTypeDef,
-    ListTagsForResourceResultTypeDef,
-    UpdateModelVersionResultTypeDef,
     BatchGetVariableResultTypeDef,
     GetVariablesResultTypeDef,
     GetBatchImportJobsResultTypeDef,
     GetBatchPredictionJobsResultTypeDef,
     ModelScoresTypeDef,
     CreateDetectorVersionRequestRequestTypeDef,
     CreateRuleResultTypeDef,
@@ -443,14 +443,15 @@
     UpdateRuleVersionResultTypeDef,
     DataValidationMetricsTypeDef,
     DescribeDetectorResultTypeDef,
     GetDetectorsResultTypeDef,
     EventTypeDef,
     SendEventRequestRequestTypeDef,
     GetEntityTypesResultTypeDef,
+    PutEventTypeRequestRequestTypeDef,
     ListEventPredictionsResultTypeDef,
     EventTypeTypeDef,
     ExternalModelOutputsTypeDef,
     ExternalModelTypeDef,
     PutExternalModelRequestRequestTypeDef,
     GetEventPredictionRequestRequestTypeDef,
     GetKMSEncryptionKeyResultTypeDef,
@@ -493,43 +494,43 @@
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

### Comparing `types-aiobotocore-frauddetector-2.5.0.post1/types_aiobotocore_frauddetector.egg-info/SOURCES.txt` & `types-aiobotocore-frauddetector-2.5.1/types_aiobotocore_frauddetector.egg-info/SOURCES.txt`

 * *Files identical despite different names*

