# Comparing `tmp/types-aiobotocore-lexv2-models-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-lexv2-models-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-lexv2-models-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:53 2023, max compression
+gzip compressed data, was "types-aiobotocore-lexv2-models-2.5.1.tar", last modified: Wed Jun 28 01:43:45 2023, max compression
```

## Comparing `types-aiobotocore-lexv2-models-2.5.0.post1.tar` & `types-aiobotocore-lexv2-models-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:53.843368 types-aiobotocore-lexv2-models-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:17:25.000000 types-aiobotocore-lexv2-models-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    26524 2023-03-11 12:26:53.839368 types-aiobotocore-lexv2-models-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    24934 2023-03-11 12:17:25.000000 types-aiobotocore-lexv2-models-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:53.843368 types-aiobotocore-lexv2-models-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2158 2023-03-11 12:17:25.000000 types-aiobotocore-lexv2-models-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:53.835368 types-aiobotocore-lexv2-models-2.5.0.post1/types_aiobotocore_lexv2_models/
--rw-r--r--   0 runner    (1001) docker     (123)     2111 2023-03-11 12:17:25.000000 types-aiobotocore-lexv2-models-2.5.0.post1/types_aiobotocore_lexv2_models/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2110 2023-03-11 12:17:25.000000 types-aiobotocore-lexv2-models-2.5.0.post1/types_aiobotocore_lexv2_models/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      961 2023-03-11 12:17:25.000000 types-aiobotocore-lexv2-models-2.5.0.post1/types_aiobotocore_lexv2_models/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    60124 2023-03-11 12:17:28.000000 types-aiobotocore-lexv2-models-2.5.0.post1/types_aiobotocore_lexv2_models/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    60036 2023-03-11 12:17:26.000000 types-aiobotocore-lexv2-models-2.5.0.post1/types_aiobotocore_lexv2_models/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    14199 2023-03-11 12:17:28.000000 types-aiobotocore-lexv2-models-2.5.0.post1/types_aiobotocore_lexv2_models/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    14197 2023-03-11 12:17:28.000000 types-aiobotocore-lexv2-models-2.5.0.post1/types_aiobotocore_lexv2_models/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:17:25.000000 types-aiobotocore-lexv2-models-2.5.0.post1/types_aiobotocore_lexv2_models/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)   118606 2023-03-11 12:17:30.000000 types-aiobotocore-lexv2-models-2.5.0.post1/types_aiobotocore_lexv2_models/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)   118449 2023-03-11 12:17:29.000000 types-aiobotocore-lexv2-models-2.5.0.post1/types_aiobotocore_lexv2_models/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:17:25.000000 types-aiobotocore-lexv2-models-2.5.0.post1/types_aiobotocore_lexv2_models/version.py
--rw-r--r--   0 runner    (1001) docker     (123)     8873 2023-03-11 12:17:28.000000 types-aiobotocore-lexv2-models-2.5.0.post1/types_aiobotocore_lexv2_models/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)     8865 2023-03-11 12:17:28.000000 types-aiobotocore-lexv2-models-2.5.0.post1/types_aiobotocore_lexv2_models/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:53.839368 types-aiobotocore-lexv2-models-2.5.0.post1/types_aiobotocore_lexv2_models.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    26524 2023-03-11 12:26:53.000000 types-aiobotocore-lexv2-models-2.5.0.post1/types_aiobotocore_lexv2_models.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      902 2023-03-11 12:26:53.000000 types-aiobotocore-lexv2-models-2.5.0.post1/types_aiobotocore_lexv2_models.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:53.000000 types-aiobotocore-lexv2-models-2.5.0.post1/types_aiobotocore_lexv2_models.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:53.000000 types-aiobotocore-lexv2-models-2.5.0.post1/types_aiobotocore_lexv2_models.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:53.000000 types-aiobotocore-lexv2-models-2.5.0.post1/types_aiobotocore_lexv2_models.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       31 2023-03-11 12:26:53.000000 types-aiobotocore-lexv2-models-2.5.0.post1/types_aiobotocore_lexv2_models.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:45.098166 types-aiobotocore-lexv2-models-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:34:06.000000 types-aiobotocore-lexv2-models-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    30280 2023-06-28 01:43:45.098166 types-aiobotocore-lexv2-models-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    28696 2023-06-28 01:34:06.000000 types-aiobotocore-lexv2-models-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:45.098166 types-aiobotocore-lexv2-models-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2152 2023-06-28 01:34:06.000000 types-aiobotocore-lexv2-models-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:45.098166 types-aiobotocore-lexv2-models-2.5.1/types_aiobotocore_lexv2_models/
+-rw-r--r--   0 runner    (1001) docker     (123)     2111 2023-06-28 01:34:06.000000 types-aiobotocore-lexv2-models-2.5.1/types_aiobotocore_lexv2_models/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2110 2023-06-28 01:34:06.000000 types-aiobotocore-lexv2-models-2.5.1/types_aiobotocore_lexv2_models/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      949 2023-06-28 01:34:06.000000 types-aiobotocore-lexv2-models-2.5.1/types_aiobotocore_lexv2_models/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    69471 2023-06-28 01:34:07.000000 types-aiobotocore-lexv2-models-2.5.1/types_aiobotocore_lexv2_models/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    69369 2023-06-28 01:34:06.000000 types-aiobotocore-lexv2-models-2.5.1/types_aiobotocore_lexv2_models/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    15880 2023-06-28 01:34:07.000000 types-aiobotocore-lexv2-models-2.5.1/types_aiobotocore_lexv2_models/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15878 2023-06-28 01:34:07.000000 types-aiobotocore-lexv2-models-2.5.1/types_aiobotocore_lexv2_models/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:34:06.000000 types-aiobotocore-lexv2-models-2.5.1/types_aiobotocore_lexv2_models/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)   150439 2023-06-28 01:34:11.000000 types-aiobotocore-lexv2-models-2.5.1/types_aiobotocore_lexv2_models/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)   150242 2023-06-28 01:34:08.000000 types-aiobotocore-lexv2-models-2.5.1/types_aiobotocore_lexv2_models/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:34:06.000000 types-aiobotocore-lexv2-models-2.5.1/types_aiobotocore_lexv2_models/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8873 2023-06-28 01:34:07.000000 types-aiobotocore-lexv2-models-2.5.1/types_aiobotocore_lexv2_models/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8865 2023-06-28 01:34:07.000000 types-aiobotocore-lexv2-models-2.5.1/types_aiobotocore_lexv2_models/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:45.098166 types-aiobotocore-lexv2-models-2.5.1/types_aiobotocore_lexv2_models.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    30280 2023-06-28 01:43:44.000000 types-aiobotocore-lexv2-models-2.5.1/types_aiobotocore_lexv2_models.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      902 2023-06-28 01:43:44.000000 types-aiobotocore-lexv2-models-2.5.1/types_aiobotocore_lexv2_models.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:44.000000 types-aiobotocore-lexv2-models-2.5.1/types_aiobotocore_lexv2_models.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:44.000000 types-aiobotocore-lexv2-models-2.5.1/types_aiobotocore_lexv2_models.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:44.000000 types-aiobotocore-lexv2-models-2.5.1/types_aiobotocore_lexv2_models.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       31 2023-06-28 01:43:44.000000 types-aiobotocore-lexv2-models-2.5.1/types_aiobotocore_lexv2_models.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-lexv2-models-2.5.0.post1/LICENSE` & `types-aiobotocore-lexv2-models-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-lexv2-models-2.5.0.post1/README.md` & `types-aiobotocore-lexv2-models-2.5.1/PKG-INFO`

 * *Files 22% similar despite different names*

```diff
@@ -1,29 +1,62 @@
+Metadata-Version: 2.1
+Name: types-aiobotocore-lexv2-models
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.LexModelsV2 2.5.1 service generated with mypy-boto3-builder 7.14.5
+Home-page: https://github.com/youtype/mypy_boto3_builder
+Author: Vlad Emelianov
+Author-email: vlad.emelianov.nz@gmail.com
+License: MIT License
+Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/
+Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
+Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
+Keywords: aiobotocore lexv2-models type-annotations boto3-stubs mypy typeshed autocomplete
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
 <a id="types-aiobotocore-lexv2-models"></a>
 
 # types-aiobotocore-lexv2-models
 
 [![PyPI - types-aiobotocore-lexv2-models](https://img.shields.io/pypi/v/types-aiobotocore-lexv2-models.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lexv2-models)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-lexv2-models.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lexv2-models)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-lexv2-models?color=blue)](https://pypistats.org/packages/types-aiobotocore-lexv2-models)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.LexModelsV2 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2)
+[aiobotocore.LexModelsV2 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2)
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
 [types-aiobotocore-lexv2-models docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/).
 
 See how it helps to find and fix potential bugs:
 
@@ -310,14 +343,15 @@
     BotSortAttributeType,
     BotStatusType,
     BotTypeType,
     BotVersionAvailableWaiterName,
     BotVersionSortAttributeType,
     BuiltInIntentSortAttributeType,
     BuiltInSlotTypeSortAttributeType,
+    ConversationLogsInputModeFilterType,
     CustomVocabularyStatusType,
     DialogActionTypeType,
     EffectType,
     ErrorCodeType,
     ExportFilterNameType,
     ExportFilterOperatorType,
     ExportSortAttributeType,
@@ -343,14 +377,25 @@
     SlotSortAttributeType,
     SlotTypeCategoryType,
     SlotTypeFilterNameType,
     SlotTypeFilterOperatorType,
     SlotTypeSortAttributeType,
     SlotValueResolutionStrategyType,
     SortOrderType,
+    TestExecutionApiModeType,
+    TestExecutionModalityType,
+    TestExecutionSortAttributeType,
+    TestExecutionStatusType,
+    TestResultMatchStatusType,
+    TestResultTypeFilterType,
+    TestSetDiscrepancyReportStatusType,
+    TestSetGenerationStatusType,
+    TestSetModalityType,
+    TestSetSortAttributeType,
+    TestSetStatusType,
     TimeDimensionType,
     TranscriptFormatType,
     VoiceEngineType,
     LexModelsV2ServiceName,
     ServiceName,
     ResourceServiceName,
     WaiterName,
@@ -367,31 +412,34 @@
 ### Typed dictionaries
 
 `types_aiobotocore_lexv2_models.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_lexv2_models.type_defs import (
+    ActiveContextTypeDef,
     AdvancedRecognitionSettingTypeDef,
+    ExecutionErrorDetailsTypeDef,
+    AgentTurnSpecificationTypeDef,
     AggregatedUtterancesFilterTypeDef,
     AggregatedUtterancesSortByTypeDef,
     AggregatedUtterancesSummaryTypeDef,
     AllowedInputTypesTypeDef,
     AssociatedTranscriptFilterTypeDef,
     AssociatedTranscriptTypeDef,
     AudioSpecificationTypeDef,
     DTMFSpecificationTypeDef,
     S3BucketLogDestinationTypeDef,
     NewCustomVocabularyItemTypeDef,
     CustomVocabularyItemTypeDef,
     FailedCustomVocabularyItemTypeDef,
-    ResponseMetadataTypeDef,
     CustomVocabularyEntryIdTypeDef,
     BotAliasHistoryEventTypeDef,
     BotAliasSummaryTypeDef,
+    BotAliasTestExecutionTargetTypeDef,
     BotExportSpecificationTypeDef,
     BotFilterTypeDef,
     DataPrivacyTypeDef,
     BotLocaleExportSpecificationTypeDef,
     BotLocaleFilterTypeDef,
     BotLocaleHistoryEventTypeDef,
     VoiceSettingsTypeDef,
@@ -403,133 +451,166 @@
     BotRecommendationSummaryTypeDef,
     BotSortByTypeDef,
     BotSummaryTypeDef,
     BotVersionLocaleDetailsTypeDef,
     BotVersionSortByTypeDef,
     BotVersionSummaryTypeDef,
     BuildBotLocaleRequestRequestTypeDef,
+    BuildBotLocaleResponseTypeDef,
     BuiltInIntentSortByTypeDef,
     BuiltInIntentSummaryTypeDef,
     BuiltInSlotTypeSortByTypeDef,
     BuiltInSlotTypeSummaryTypeDef,
     ButtonTypeDef,
     CloudWatchLogGroupLogDestinationTypeDef,
     LambdaCodeHookTypeDef,
     SubSlotTypeCompositionTypeDef,
     ConditionTypeDef,
+    ConversationLevelIntentClassificationResultItemTypeDef,
+    ConversationLevelResultDetailTypeDef,
+    ConversationLevelSlotResolutionResultItemTypeDef,
+    ConversationLevelTestResultsFilterByTypeDef,
+    ConversationLogsDataSourceFilterByTypeDef,
     SentimentAnalysisSettingsTypeDef,
     DialogCodeHookSettingsTypeDef,
     InputContextTypeDef,
     KendraConfigurationTypeDef,
     OutputContextTypeDef,
     SampleUtteranceTypeDef,
     CreateResourcePolicyRequestRequestTypeDef,
+    CreateResourcePolicyResponseTypeDef,
     PrincipalTypeDef,
+    CreateResourcePolicyStatementResponseTypeDef,
     MultipleValuesSettingTypeDef,
     ObfuscationSettingTypeDef,
+    CreateUploadUrlResponseTypeDef,
     CustomPayloadTypeDef,
     CustomVocabularyExportSpecificationTypeDef,
     CustomVocabularyImportSpecificationTypeDef,
     DateRangeFilterTypeDef,
     DeleteBotAliasRequestRequestTypeDef,
+    DeleteBotAliasResponseTypeDef,
     DeleteBotLocaleRequestRequestTypeDef,
+    DeleteBotLocaleResponseTypeDef,
     DeleteBotRequestRequestTypeDef,
+    DeleteBotResponseTypeDef,
     DeleteBotVersionRequestRequestTypeDef,
+    DeleteBotVersionResponseTypeDef,
     DeleteCustomVocabularyRequestRequestTypeDef,
+    DeleteCustomVocabularyResponseTypeDef,
     DeleteExportRequestRequestTypeDef,
+    DeleteExportResponseTypeDef,
     DeleteImportRequestRequestTypeDef,
+    DeleteImportResponseTypeDef,
     DeleteIntentRequestRequestTypeDef,
     DeleteResourcePolicyRequestRequestTypeDef,
+    DeleteResourcePolicyResponseTypeDef,
     DeleteResourcePolicyStatementRequestRequestTypeDef,
+    DeleteResourcePolicyStatementResponseTypeDef,
     DeleteSlotRequestRequestTypeDef,
     DeleteSlotTypeRequestRequestTypeDef,
+    DeleteTestSetRequestRequestTypeDef,
     DeleteUtterancesRequestRequestTypeDef,
     WaiterConfigTypeDef,
     DescribeBotAliasRequestRequestTypeDef,
     ParentBotNetworkTypeDef,
     DescribeBotLocaleRequestRequestTypeDef,
     DescribeBotRecommendationRequestRequestTypeDef,
     EncryptionSettingTypeDef,
     DescribeBotRequestRequestTypeDef,
     DescribeBotVersionRequestRequestTypeDef,
     DescribeCustomVocabularyMetadataRequestRequestTypeDef,
+    DescribeCustomVocabularyMetadataResponseTypeDef,
     DescribeExportRequestRequestTypeDef,
     DescribeImportRequestRequestTypeDef,
     DescribeIntentRequestRequestTypeDef,
     SlotPriorityTypeDef,
     DescribeResourcePolicyRequestRequestTypeDef,
+    DescribeResourcePolicyResponseTypeDef,
     DescribeSlotRequestRequestTypeDef,
     DescribeSlotTypeRequestRequestTypeDef,
+    DescribeTestExecutionRequestRequestTypeDef,
+    DescribeTestSetDiscrepancyReportRequestRequestTypeDef,
+    DescribeTestSetGenerationRequestRequestTypeDef,
+    TestSetStorageLocationTypeDef,
+    DescribeTestSetRequestRequestTypeDef,
     DialogActionTypeDef,
     IntentOverrideTypeDef,
     ElicitationCodeHookInvocationSettingTypeDef,
+    EmptyResponseMetadataTypeDef,
     ExportFilterTypeDef,
+    TestSetExportSpecificationTypeDef,
     ExportSortByTypeDef,
+    GetTestExecutionArtifactsUrlRequestRequestTypeDef,
+    GetTestExecutionArtifactsUrlResponseTypeDef,
     GrammarSlotTypeSourceTypeDef,
     ImportFilterTypeDef,
     ImportSortByTypeDef,
     ImportSummaryTypeDef,
+    RuntimeHintsTypeDef,
+    IntentClassificationTestResultItemCountsTypeDef,
     IntentFilterTypeDef,
     IntentSortByTypeDef,
     ListBotAliasesRequestRequestTypeDef,
     ListBotRecommendationsRequestRequestTypeDef,
     ListCustomVocabularyItemsRequestRequestTypeDef,
     ListRecommendedIntentsRequestRequestTypeDef,
     RecommendedIntentSummaryTypeDef,
     SlotTypeFilterTypeDef,
     SlotTypeSortByTypeDef,
     SlotTypeSummaryTypeDef,
     SlotFilterTypeDef,
     SlotSortByTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    TestExecutionSortByTypeDef,
+    ListTestSetRecordsRequestRequestTypeDef,
+    TestSetSortByTypeDef,
     PlainTextMessageTypeDef,
     SSMLMessageTypeDef,
+    OverallTestResultItemTypeDef,
     PathFormatTypeDef,
     TextInputSpecificationTypeDef,
     RelativeAggregationDurationTypeDef,
+    ResponseMetadataTypeDef,
+    RuntimeHintValueTypeDef,
     SampleValueTypeDef,
     SlotDefaultValueTypeDef,
+    SlotResolutionTestResultItemCountsTypeDef,
     SlotValueTypeDef,
     SlotValueRegexFilterTypeDef,
     StopBotRecommendationRequestRequestTypeDef,
+    StopBotRecommendationResponseTypeDef,
     TagResourceRequestRequestTypeDef,
+    TestSetIntentDiscrepancyItemTypeDef,
+    TestSetSlotDiscrepancyItemTypeDef,
+    TestSetDiscrepancyReportBotAliasTargetTypeDef,
+    TestSetImportInputLocationTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateExportRequestRequestTypeDef,
     UpdateResourcePolicyRequestRequestTypeDef,
+    UpdateResourcePolicyResponseTypeDef,
+    UpdateTestSetRequestRequestTypeDef,
+    UserTurnIntentOutputTypeDef,
+    UserTurnSlotOutputTypeDef,
+    UtteranceAudioInputSpecificationTypeDef,
+    AgentTurnResultTypeDef,
     SearchAssociatedTranscriptsRequestRequestTypeDef,
+    SearchAssociatedTranscriptsResponseTypeDef,
     AudioAndDTMFInputSpecificationTypeDef,
     AudioLogDestinationTypeDef,
     BatchCreateCustomVocabularyItemRequestRequestTypeDef,
     BatchUpdateCustomVocabularyItemRequestRequestTypeDef,
+    ListCustomVocabularyItemsResponseTypeDef,
     BatchCreateCustomVocabularyItemResponseTypeDef,
     BatchDeleteCustomVocabularyItemResponseTypeDef,
     BatchUpdateCustomVocabularyItemResponseTypeDef,
-    BuildBotLocaleResponseTypeDef,
-    CreateResourcePolicyResponseTypeDef,
-    CreateResourcePolicyStatementResponseTypeDef,
-    CreateUploadUrlResponseTypeDef,
-    DeleteBotAliasResponseTypeDef,
-    DeleteBotLocaleResponseTypeDef,
-    DeleteBotResponseTypeDef,
-    DeleteBotVersionResponseTypeDef,
-    DeleteCustomVocabularyResponseTypeDef,
-    DeleteExportResponseTypeDef,
-    DeleteImportResponseTypeDef,
-    DeleteResourcePolicyResponseTypeDef,
-    DeleteResourcePolicyStatementResponseTypeDef,
-    DescribeCustomVocabularyMetadataResponseTypeDef,
-    DescribeResourcePolicyResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ListCustomVocabularyItemsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    SearchAssociatedTranscriptsResponseTypeDef,
-    StopBotRecommendationResponseTypeDef,
-    UpdateResourcePolicyResponseTypeDef,
     BatchDeleteCustomVocabularyItemRequestRequestTypeDef,
     ListBotAliasesResponseTypeDef,
+    TestExecutionTargetTypeDef,
     BotImportSpecificationTypeDef,
     BotLocaleImportSpecificationTypeDef,
     CreateBotLocaleRequestRequestTypeDef,
     CreateBotLocaleResponseTypeDef,
     DescribeBotLocaleResponseTypeDef,
     UpdateBotLocaleRequestRequestTypeDef,
     UpdateBotLocaleResponseTypeDef,
@@ -552,102 +633,149 @@
     ListBuiltInIntentsResponseTypeDef,
     ListBuiltInSlotTypesRequestRequestTypeDef,
     ListBuiltInSlotTypesResponseTypeDef,
     ImageResponseCardTypeDef,
     TextLogDestinationTypeDef,
     CodeHookSpecificationTypeDef,
     CompositeSlotTypeSettingTypeDef,
+    ConversationLevelTestResultItemTypeDef,
+    TestExecutionResultFilterByTypeDef,
+    ConversationLogsDataSourceTypeDef,
     IntentSummaryTypeDef,
     CreateResourcePolicyStatementRequestRequestTypeDef,
-    ExportResourceSpecificationTypeDef,
     LexTranscriptFilterTypeDef,
     DescribeBotAliasRequestBotAliasAvailableWaitTypeDef,
     DescribeBotLocaleRequestBotLocaleBuiltWaitTypeDef,
     DescribeBotLocaleRequestBotLocaleCreatedWaitTypeDef,
     DescribeBotLocaleRequestBotLocaleExpressTestingAvailableWaitTypeDef,
     DescribeBotRequestBotAvailableWaitTypeDef,
     DescribeBotVersionRequestBotVersionAvailableWaitTypeDef,
     DescribeExportRequestBotExportCompletedWaitTypeDef,
     DescribeImportRequestBotImportCompletedWaitTypeDef,
     DescribeBotVersionResponseTypeDef,
     UpdateBotRecommendationRequestRequestTypeDef,
+    DescribeTestSetResponseTypeDef,
+    TestSetSummaryTypeDef,
+    UpdateTestSetResponseTypeDef,
     DialogStateTypeDef,
+    ExportResourceSpecificationTypeDef,
     ListExportsRequestRequestTypeDef,
     GrammarSlotTypeSettingTypeDef,
     ListImportsRequestRequestTypeDef,
     ListImportsResponseTypeDef,
+    InputSessionStateSpecificationTypeDef,
+    IntentClassificationTestResultItemTypeDef,
     ListIntentsRequestRequestTypeDef,
     ListRecommendedIntentsResponseTypeDef,
     ListSlotTypesRequestRequestTypeDef,
     ListSlotTypesResponseTypeDef,
     ListSlotsRequestRequestTypeDef,
+    ListTestExecutionsRequestRequestTypeDef,
+    ListTestSetsRequestRequestTypeDef,
+    OverallTestResultsTypeDef,
     UtteranceAggregationDurationTypeDef,
+    RuntimeHintDetailsTypeDef,
     SlotTypeValueTypeDef,
     SlotDefaultValueSpecificationTypeDef,
+    SlotResolutionTestResultItemTypeDef,
     SlotValueOverrideTypeDef,
     SlotValueSelectionSettingTypeDef,
+    TestSetDiscrepancyErrorsTypeDef,
+    TestSetDiscrepancyReportResourceTargetTypeDef,
+    TestSetImportResourceSpecificationTypeDef,
+    UserTurnOutputSpecificationTypeDef,
+    UtteranceInputSpecificationTypeDef,
     PromptAttemptSpecificationTypeDef,
     AudioLogSettingTypeDef,
-    ImportResourceSpecificationTypeDef,
+    DescribeTestExecutionResponseTypeDef,
+    StartTestExecutionRequestRequestTypeDef,
+    StartTestExecutionResponseTypeDef,
+    TestExecutionSummaryTypeDef,
     BotRecommendationResultsTypeDef,
     MessageTypeDef,
     TextLogSettingTypeDef,
     BotAliasLocaleSettingsTypeDef,
+    ConversationLevelTestResultsTypeDef,
+    ListTestExecutionResultItemsRequestRequestTypeDef,
+    TestSetGenerationDataSourceTypeDef,
     ListIntentsResponseTypeDef,
+    TranscriptFilterTypeDef,
+    ListTestSetsResponseTypeDef,
     CreateExportRequestRequestTypeDef,
     CreateExportResponseTypeDef,
     DescribeExportResponseTypeDef,
     ExportSummaryTypeDef,
     UpdateExportResponseTypeDef,
-    TranscriptFilterTypeDef,
     ExternalSourceSettingTypeDef,
+    IntentClassificationTestResultsTypeDef,
     ListAggregatedUtterancesRequestRequestTypeDef,
     ListAggregatedUtterancesResponseTypeDef,
-    DescribeImportResponseTypeDef,
-    StartImportRequestRequestTypeDef,
-    StartImportResponseTypeDef,
+    IntentLevelSlotResolutionTestResultItemTypeDef,
+    CreateTestSetDiscrepancyReportRequestRequestTypeDef,
+    CreateTestSetDiscrepancyReportResponseTypeDef,
+    DescribeTestSetDiscrepancyReportResponseTypeDef,
+    ImportResourceSpecificationTypeDef,
+    UserTurnInputSpecificationTypeDef,
+    ListTestExecutionsResponseTypeDef,
     MessageGroupTypeDef,
     ConversationLogSettingsTypeDef,
-    ListExportsResponseTypeDef,
+    DescribeTestSetGenerationResponseTypeDef,
+    StartTestSetGenerationRequestRequestTypeDef,
+    StartTestSetGenerationResponseTypeDef,
     S3BucketTranscriptSourceTypeDef,
+    ListExportsResponseTypeDef,
     CreateSlotTypeRequestRequestTypeDef,
     CreateSlotTypeResponseTypeDef,
     DescribeSlotTypeResponseTypeDef,
     UpdateSlotTypeRequestRequestTypeDef,
     UpdateSlotTypeResponseTypeDef,
+    IntentLevelSlotResolutionTestResultsTypeDef,
+    DescribeImportResponseTypeDef,
+    StartImportRequestRequestTypeDef,
+    StartImportResponseTypeDef,
+    UserTurnResultTypeDef,
+    UserTurnSpecificationTypeDef,
     FulfillmentStartResponseSpecificationTypeDef,
     FulfillmentUpdateResponseSpecificationTypeDef,
     PromptSpecificationTypeDef,
     ResponseSpecificationTypeDef,
     StillWaitingResponseSpecificationTypeDef,
     CreateBotAliasRequestRequestTypeDef,
     CreateBotAliasResponseTypeDef,
     DescribeBotAliasResponseTypeDef,
     UpdateBotAliasRequestRequestTypeDef,
     UpdateBotAliasResponseTypeDef,
     TranscriptSourceSettingTypeDef,
+    TestSetTurnResultTypeDef,
+    TurnSpecificationTypeDef,
     FulfillmentUpdatesSpecificationTypeDef,
     SlotSummaryTypeDef,
     ConditionalBranchTypeDef,
     DefaultConditionalBranchTypeDef,
     WaitAndContinueSpecificationTypeDef,
     DescribeBotRecommendationResponseTypeDef,
     StartBotRecommendationRequestRequestTypeDef,
     StartBotRecommendationResponseTypeDef,
     UpdateBotRecommendationResponseTypeDef,
+    UtteranceLevelTestResultItemTypeDef,
+    TestSetTurnRecordTypeDef,
     ListSlotsResponseTypeDef,
     ConditionalSpecificationTypeDef,
     SubSlotValueElicitationSettingTypeDef,
+    UtteranceLevelTestResultsTypeDef,
+    ListTestSetRecordsResponseTypeDef,
     IntentClosingSettingTypeDef,
     PostDialogCodeHookInvocationSpecificationTypeDef,
     PostFulfillmentStatusSpecificationTypeDef,
     SpecificationsTypeDef,
+    TestExecutionResultItemsTypeDef,
     DialogCodeHookInvocationSettingTypeDef,
     FulfillmentCodeHookSettingsTypeDef,
     SubSlotSettingTypeDef,
+    ListTestExecutionResultItemsResponseTypeDef,
     InitialResponseSettingTypeDef,
     IntentConfirmationSettingTypeDef,
     SlotCaptureSettingTypeDef,
     CreateIntentRequestRequestTypeDef,
     CreateIntentResponseTypeDef,
     DescribeIntentResponseTypeDef,
     UpdateIntentRequestRequestTypeDef,
@@ -657,54 +785,54 @@
     CreateSlotResponseTypeDef,
     DescribeSlotResponseTypeDef,
     UpdateSlotRequestRequestTypeDef,
     UpdateSlotResponseTypeDef,
 )
 
 
-def get_structure() -> AdvancedRecognitionSettingTypeDef:
+def get_structure() -> ActiveContextTypeDef:
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

### Comparing `types-aiobotocore-lexv2-models-2.5.0.post1/setup.py` & `types-aiobotocore-lexv2-models-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-lexv2-models.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-lexv2-models",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_lexv2_models"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.LexModelsV2 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.LexModelsV2 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/"
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

### Comparing `types-aiobotocore-lexv2-models-2.5.0.post1/types_aiobotocore_lexv2_models/__init__.py` & `types-aiobotocore-lexv2-models-2.5.1/types_aiobotocore_lexv2_models/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-lexv2-models-2.5.0.post1/types_aiobotocore_lexv2_models/__init__.pyi` & `types-aiobotocore-lexv2-models-2.5.1/types_aiobotocore_lexv2_models/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-lexv2-models-2.5.0.post1/types_aiobotocore_lexv2_models/__main__.py` & `types-aiobotocore-lexv2-models-2.5.1/types_aiobotocore_lexv2_models/__main__.py`

 * *Files 26% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.LexModelsV2 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.LexModelsV2 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2\nOther"
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

### Comparing `types-aiobotocore-lexv2-models-2.5.0.post1/types_aiobotocore_lexv2_models/client.py` & `types-aiobotocore-lexv2-models-2.5.1/types_aiobotocore_lexv2_models/client.py`

 * *Files 8% similar despite different names*

```diff
@@ -22,14 +22,16 @@
 
 from .literals import (
     BotTypeType,
     EffectType,
     ImportExportFileFormatType,
     MergeStrategyType,
     SearchOrderType,
+    TestExecutionApiModeType,
+    TestExecutionModalityType,
 )
 from .type_defs import (
     AggregatedUtterancesFilterTypeDef,
     AggregatedUtterancesSortByTypeDef,
     AssociatedTranscriptFilterTypeDef,
     BatchCreateCustomVocabularyItemResponseTypeDef,
     BatchDeleteCustomVocabularyItemResponseTypeDef,
@@ -53,14 +55,15 @@
     CreateBotVersionResponseTypeDef,
     CreateExportResponseTypeDef,
     CreateIntentResponseTypeDef,
     CreateResourcePolicyResponseTypeDef,
     CreateResourcePolicyStatementResponseTypeDef,
     CreateSlotResponseTypeDef,
     CreateSlotTypeResponseTypeDef,
+    CreateTestSetDiscrepancyReportResponseTypeDef,
     CreateUploadUrlResponseTypeDef,
     CustomVocabularyEntryIdTypeDef,
     CustomVocabularyItemTypeDef,
     DataPrivacyTypeDef,
     DeleteBotAliasResponseTypeDef,
     DeleteBotLocaleResponseTypeDef,
     DeleteBotResponseTypeDef,
@@ -78,22 +81,27 @@
     DescribeCustomVocabularyMetadataResponseTypeDef,
     DescribeExportResponseTypeDef,
     DescribeImportResponseTypeDef,
     DescribeIntentResponseTypeDef,
     DescribeResourcePolicyResponseTypeDef,
     DescribeSlotResponseTypeDef,
     DescribeSlotTypeResponseTypeDef,
+    DescribeTestExecutionResponseTypeDef,
+    DescribeTestSetDiscrepancyReportResponseTypeDef,
+    DescribeTestSetGenerationResponseTypeDef,
+    DescribeTestSetResponseTypeDef,
     DialogCodeHookSettingsTypeDef,
     EmptyResponseMetadataTypeDef,
     EncryptionSettingTypeDef,
     ExportFilterTypeDef,
     ExportResourceSpecificationTypeDef,
     ExportSortByTypeDef,
     ExternalSourceSettingTypeDef,
     FulfillmentCodeHookSettingsTypeDef,
+    GetTestExecutionArtifactsUrlResponseTypeDef,
     ImportFilterTypeDef,
     ImportResourceSpecificationTypeDef,
     ImportSortByTypeDef,
     InitialResponseSettingTypeDef,
     InputContextTypeDef,
     IntentClosingSettingTypeDef,
     IntentConfirmationSettingTypeDef,
@@ -112,14 +120,18 @@
     ListExportsResponseTypeDef,
     ListImportsResponseTypeDef,
     ListIntentsResponseTypeDef,
     ListRecommendedIntentsResponseTypeDef,
     ListSlotsResponseTypeDef,
     ListSlotTypesResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
+    ListTestExecutionResultItemsResponseTypeDef,
+    ListTestExecutionsResponseTypeDef,
+    ListTestSetRecordsResponseTypeDef,
+    ListTestSetsResponseTypeDef,
     MultipleValuesSettingTypeDef,
     NewCustomVocabularyItemTypeDef,
     ObfuscationSettingTypeDef,
     OutputContextTypeDef,
     PrincipalTypeDef,
     SampleUtteranceTypeDef,
     SearchAssociatedTranscriptsResponseTypeDef,
@@ -130,26 +142,36 @@
     SlotTypeFilterTypeDef,
     SlotTypeSortByTypeDef,
     SlotTypeValueTypeDef,
     SlotValueElicitationSettingTypeDef,
     SlotValueSelectionSettingTypeDef,
     StartBotRecommendationResponseTypeDef,
     StartImportResponseTypeDef,
+    StartTestExecutionResponseTypeDef,
+    StartTestSetGenerationResponseTypeDef,
     StopBotRecommendationResponseTypeDef,
     SubSlotSettingTypeDef,
+    TestExecutionResultFilterByTypeDef,
+    TestExecutionSortByTypeDef,
+    TestExecutionTargetTypeDef,
+    TestSetDiscrepancyReportResourceTargetTypeDef,
+    TestSetGenerationDataSourceTypeDef,
+    TestSetSortByTypeDef,
+    TestSetStorageLocationTypeDef,
     TranscriptSourceSettingTypeDef,
     UpdateBotAliasResponseTypeDef,
     UpdateBotLocaleResponseTypeDef,
     UpdateBotRecommendationResponseTypeDef,
     UpdateBotResponseTypeDef,
     UpdateExportResponseTypeDef,
     UpdateIntentResponseTypeDef,
     UpdateResourcePolicyResponseTypeDef,
     UpdateSlotResponseTypeDef,
     UpdateSlotTypeResponseTypeDef,
+    UpdateTestSetResponseTypeDef,
     UtteranceAggregationDurationTypeDef,
     VoiceSettingsTypeDef,
 )
 from .waiter import (
     BotAliasAvailableWaiter,
     BotAvailableWaiter,
     BotExportCompletedWaiter,
@@ -458,14 +480,24 @@
         slot type and a set of enumeration values, the values that a slot of this type
         can assume.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.create_slot_type)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#create_slot_type)
         """
 
+    async def create_test_set_discrepancy_report(
+        self, *, testSetId: str, target: TestSetDiscrepancyReportResourceTargetTypeDef
+    ) -> CreateTestSetDiscrepancyReportResponseTypeDef:
+        """
+        Create a report that describes the differences between the bot and the test set.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.create_test_set_discrepancy_report)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#create_test_set_discrepancy_report)
+        """
+
     async def create_upload_url(self) -> CreateUploadUrlResponseTypeDef:
         """
         Gets a pre-signed S3 write URL that you use to upload the zip archive when
         importing a bot or a bot locale.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.create_upload_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#create_upload_url)
@@ -589,14 +621,22 @@
         """
         Deletes a slot type from a bot locale.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.delete_slot_type)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#delete_slot_type)
         """
 
+    async def delete_test_set(self, *, testSetId: str) -> EmptyResponseMetadataTypeDef:
+        """
+        The action to delete the selected test set.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.delete_test_set)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#delete_test_set)
+        """
+
     async def delete_utterances(
         self, *, botId: str, localeId: str = ..., sessionId: str = ...
     ) -> Dict[str, Any]:
         """
         Deletes stored utterances.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.delete_utterances)
@@ -713,28 +753,76 @@
         """
         Gets metadata information about a slot type.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.describe_slot_type)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#describe_slot_type)
         """
 
+    async def describe_test_execution(
+        self, *, testExecutionId: str
+    ) -> DescribeTestExecutionResponseTypeDef:
+        """
+        Gets metadata information about the test execution.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.describe_test_execution)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#describe_test_execution)
+        """
+
+    async def describe_test_set(self, *, testSetId: str) -> DescribeTestSetResponseTypeDef:
+        """
+        Gets metadata information about the test set.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.describe_test_set)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#describe_test_set)
+        """
+
+    async def describe_test_set_discrepancy_report(
+        self, *, testSetDiscrepancyReportId: str
+    ) -> DescribeTestSetDiscrepancyReportResponseTypeDef:
+        """
+        Gets metadata information about the test set discrepancy report.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.describe_test_set_discrepancy_report)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#describe_test_set_discrepancy_report)
+        """
+
+    async def describe_test_set_generation(
+        self, *, testSetGenerationId: str
+    ) -> DescribeTestSetGenerationResponseTypeDef:
+        """
+        Gets metadata information about the test set generation.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.describe_test_set_generation)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#describe_test_set_generation)
+        """
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
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#generate_presigned_url)
         """
 
+    async def get_test_execution_artifacts_url(
+        self, *, testExecutionId: str
+    ) -> GetTestExecutionArtifactsUrlResponseTypeDef:
+        """
+        The pre-signed Amazon S3 URL to download the test execution result artifacts.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.get_test_execution_artifacts_url)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#get_test_execution_artifacts_url)
+        """
+
     async def list_aggregated_utterances(
         self,
         *,
         botId: str,
         localeId: str,
         aggregationDuration: UtteranceAggregationDurationTypeDef,
         botAliasId: str = ...,
@@ -987,14 +1075,64 @@
         """
         Gets a list of tags associated with a resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#list_tags_for_resource)
         """
 
+    async def list_test_execution_result_items(
+        self,
+        *,
+        testExecutionId: str,
+        resultFilterBy: TestExecutionResultFilterByTypeDef,
+        maxResults: int = ...,
+        nextToken: str = ...
+    ) -> ListTestExecutionResultItemsResponseTypeDef:
+        """
+        Gets a list of test execution result items.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.list_test_execution_result_items)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#list_test_execution_result_items)
+        """
+
+    async def list_test_executions(
+        self,
+        *,
+        sortBy: TestExecutionSortByTypeDef = ...,
+        maxResults: int = ...,
+        nextToken: str = ...
+    ) -> ListTestExecutionsResponseTypeDef:
+        """
+        The list of test set executions.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.list_test_executions)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#list_test_executions)
+        """
+
+    async def list_test_set_records(
+        self, *, testSetId: str, maxResults: int = ..., nextToken: str = ...
+    ) -> ListTestSetRecordsResponseTypeDef:
+        """
+        The list of test set records.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.list_test_set_records)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#list_test_set_records)
+        """
+
+    async def list_test_sets(
+        self, *, sortBy: TestSetSortByTypeDef = ..., maxResults: int = ..., nextToken: str = ...
+    ) -> ListTestSetsResponseTypeDef:
+        """
+        The list of the test sets See also: [AWS API
+        Documentation](https://docs.aws.amazon.com/goto/WebAPI/models.lex.v2-2020-08-07/ListTestSets).
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.list_test_sets)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#list_test_sets)
+        """
+
     async def search_associated_transcripts(
         self,
         *,
         botId: str,
         botVersion: str,
         localeId: str,
         botRecommendationId: str,
@@ -1039,14 +1177,46 @@
         Starts importing a bot, bot locale, or custom vocabulary from a zip archive that
         you uploaded to an S3 bucket.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.start_import)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#start_import)
         """
 
+    async def start_test_execution(
+        self,
+        *,
+        testSetId: str,
+        target: TestExecutionTargetTypeDef,
+        apiMode: TestExecutionApiModeType,
+        testExecutionModality: TestExecutionModalityType = ...
+    ) -> StartTestExecutionResponseTypeDef:
+        """
+        The action to start test set execution.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.start_test_execution)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#start_test_execution)
+        """
+
+    async def start_test_set_generation(
+        self,
+        *,
+        testSetName: str,
+        storageLocation: TestSetStorageLocationTypeDef,
+        generationDataSource: TestSetGenerationDataSourceTypeDef,
+        roleArn: str,
+        description: str = ...,
+        testSetTags: Mapping[str, str] = ...
+    ) -> StartTestSetGenerationResponseTypeDef:
+        """
+        The action to start the generation of test set.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.start_test_set_generation)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#start_test_set_generation)
+        """
+
     async def stop_bot_recommendation(
         self, *, botId: str, botVersion: str, localeId: str, botRecommendationId: str
     ) -> StopBotRecommendationResponseTypeDef:
         """
         Stop an already running Bot Recommendation request.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.stop_bot_recommendation)
@@ -1229,14 +1399,24 @@
         """
         Updates the configuration of an existing slot type.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.update_slot_type)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#update_slot_type)
         """
 
+    async def update_test_set(
+        self, *, testSetId: str, testSetName: str, description: str = ...
+    ) -> UpdateTestSetResponseTypeDef:
+        """
+        The action to update the test set.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.update_test_set)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#update_test_set)
+        """
+
     @overload
     def get_waiter(self, waiter_name: Literal["bot_alias_available"]) -> BotAliasAvailableWaiter:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.get_waiter)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#get_waiter)
         """
```

### Comparing `types-aiobotocore-lexv2-models-2.5.0.post1/types_aiobotocore_lexv2_models/client.pyi` & `types-aiobotocore-lexv2-models-2.5.1/types_aiobotocore_lexv2_models/client.pyi`

 * *Files 8% similar despite different names*

```diff
@@ -22,14 +22,16 @@
 
 from .literals import (
     BotTypeType,
     EffectType,
     ImportExportFileFormatType,
     MergeStrategyType,
     SearchOrderType,
+    TestExecutionApiModeType,
+    TestExecutionModalityType,
 )
 from .type_defs import (
     AggregatedUtterancesFilterTypeDef,
     AggregatedUtterancesSortByTypeDef,
     AssociatedTranscriptFilterTypeDef,
     BatchCreateCustomVocabularyItemResponseTypeDef,
     BatchDeleteCustomVocabularyItemResponseTypeDef,
@@ -53,14 +55,15 @@
     CreateBotVersionResponseTypeDef,
     CreateExportResponseTypeDef,
     CreateIntentResponseTypeDef,
     CreateResourcePolicyResponseTypeDef,
     CreateResourcePolicyStatementResponseTypeDef,
     CreateSlotResponseTypeDef,
     CreateSlotTypeResponseTypeDef,
+    CreateTestSetDiscrepancyReportResponseTypeDef,
     CreateUploadUrlResponseTypeDef,
     CustomVocabularyEntryIdTypeDef,
     CustomVocabularyItemTypeDef,
     DataPrivacyTypeDef,
     DeleteBotAliasResponseTypeDef,
     DeleteBotLocaleResponseTypeDef,
     DeleteBotResponseTypeDef,
@@ -78,22 +81,27 @@
     DescribeCustomVocabularyMetadataResponseTypeDef,
     DescribeExportResponseTypeDef,
     DescribeImportResponseTypeDef,
     DescribeIntentResponseTypeDef,
     DescribeResourcePolicyResponseTypeDef,
     DescribeSlotResponseTypeDef,
     DescribeSlotTypeResponseTypeDef,
+    DescribeTestExecutionResponseTypeDef,
+    DescribeTestSetDiscrepancyReportResponseTypeDef,
+    DescribeTestSetGenerationResponseTypeDef,
+    DescribeTestSetResponseTypeDef,
     DialogCodeHookSettingsTypeDef,
     EmptyResponseMetadataTypeDef,
     EncryptionSettingTypeDef,
     ExportFilterTypeDef,
     ExportResourceSpecificationTypeDef,
     ExportSortByTypeDef,
     ExternalSourceSettingTypeDef,
     FulfillmentCodeHookSettingsTypeDef,
+    GetTestExecutionArtifactsUrlResponseTypeDef,
     ImportFilterTypeDef,
     ImportResourceSpecificationTypeDef,
     ImportSortByTypeDef,
     InitialResponseSettingTypeDef,
     InputContextTypeDef,
     IntentClosingSettingTypeDef,
     IntentConfirmationSettingTypeDef,
@@ -112,14 +120,18 @@
     ListExportsResponseTypeDef,
     ListImportsResponseTypeDef,
     ListIntentsResponseTypeDef,
     ListRecommendedIntentsResponseTypeDef,
     ListSlotsResponseTypeDef,
     ListSlotTypesResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
+    ListTestExecutionResultItemsResponseTypeDef,
+    ListTestExecutionsResponseTypeDef,
+    ListTestSetRecordsResponseTypeDef,
+    ListTestSetsResponseTypeDef,
     MultipleValuesSettingTypeDef,
     NewCustomVocabularyItemTypeDef,
     ObfuscationSettingTypeDef,
     OutputContextTypeDef,
     PrincipalTypeDef,
     SampleUtteranceTypeDef,
     SearchAssociatedTranscriptsResponseTypeDef,
@@ -130,26 +142,36 @@
     SlotTypeFilterTypeDef,
     SlotTypeSortByTypeDef,
     SlotTypeValueTypeDef,
     SlotValueElicitationSettingTypeDef,
     SlotValueSelectionSettingTypeDef,
     StartBotRecommendationResponseTypeDef,
     StartImportResponseTypeDef,
+    StartTestExecutionResponseTypeDef,
+    StartTestSetGenerationResponseTypeDef,
     StopBotRecommendationResponseTypeDef,
     SubSlotSettingTypeDef,
+    TestExecutionResultFilterByTypeDef,
+    TestExecutionSortByTypeDef,
+    TestExecutionTargetTypeDef,
+    TestSetDiscrepancyReportResourceTargetTypeDef,
+    TestSetGenerationDataSourceTypeDef,
+    TestSetSortByTypeDef,
+    TestSetStorageLocationTypeDef,
     TranscriptSourceSettingTypeDef,
     UpdateBotAliasResponseTypeDef,
     UpdateBotLocaleResponseTypeDef,
     UpdateBotRecommendationResponseTypeDef,
     UpdateBotResponseTypeDef,
     UpdateExportResponseTypeDef,
     UpdateIntentResponseTypeDef,
     UpdateResourcePolicyResponseTypeDef,
     UpdateSlotResponseTypeDef,
     UpdateSlotTypeResponseTypeDef,
+    UpdateTestSetResponseTypeDef,
     UtteranceAggregationDurationTypeDef,
     VoiceSettingsTypeDef,
 )
 from .waiter import (
     BotAliasAvailableWaiter,
     BotAvailableWaiter,
     BotExportCompletedWaiter,
@@ -437,14 +459,23 @@
         Creates a custom slot type To create a custom slot type, specify a name for the
         slot type and a set of enumeration values, the values that a slot of this type
         can assume.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.create_slot_type)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#create_slot_type)
         """
+    async def create_test_set_discrepancy_report(
+        self, *, testSetId: str, target: TestSetDiscrepancyReportResourceTargetTypeDef
+    ) -> CreateTestSetDiscrepancyReportResponseTypeDef:
+        """
+        Create a report that describes the differences between the bot and the test set.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.create_test_set_discrepancy_report)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#create_test_set_discrepancy_report)
+        """
     async def create_upload_url(self) -> CreateUploadUrlResponseTypeDef:
         """
         Gets a pre-signed S3 write URL that you use to upload the zip archive when
         importing a bot or a bot locale.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.create_upload_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#create_upload_url)
@@ -555,14 +586,21 @@
     ) -> EmptyResponseMetadataTypeDef:
         """
         Deletes a slot type from a bot locale.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.delete_slot_type)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#delete_slot_type)
         """
+    async def delete_test_set(self, *, testSetId: str) -> EmptyResponseMetadataTypeDef:
+        """
+        The action to delete the selected test set.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.delete_test_set)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#delete_test_set)
+        """
     async def delete_utterances(
         self, *, botId: str, localeId: str = ..., sessionId: str = ...
     ) -> Dict[str, Any]:
         """
         Deletes stored utterances.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.delete_utterances)
@@ -666,27 +704,70 @@
     ) -> DescribeSlotTypeResponseTypeDef:
         """
         Gets metadata information about a slot type.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.describe_slot_type)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#describe_slot_type)
         """
+    async def describe_test_execution(
+        self, *, testExecutionId: str
+    ) -> DescribeTestExecutionResponseTypeDef:
+        """
+        Gets metadata information about the test execution.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.describe_test_execution)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#describe_test_execution)
+        """
+    async def describe_test_set(self, *, testSetId: str) -> DescribeTestSetResponseTypeDef:
+        """
+        Gets metadata information about the test set.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.describe_test_set)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#describe_test_set)
+        """
+    async def describe_test_set_discrepancy_report(
+        self, *, testSetDiscrepancyReportId: str
+    ) -> DescribeTestSetDiscrepancyReportResponseTypeDef:
+        """
+        Gets metadata information about the test set discrepancy report.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.describe_test_set_discrepancy_report)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#describe_test_set_discrepancy_report)
+        """
+    async def describe_test_set_generation(
+        self, *, testSetGenerationId: str
+    ) -> DescribeTestSetGenerationResponseTypeDef:
+        """
+        Gets metadata information about the test set generation.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.describe_test_set_generation)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#describe_test_set_generation)
+        """
     async def generate_presigned_url(
         self,
         ClientMethod: str,
         Params: Mapping[str, Any] = ...,
         ExpiresIn: int = 3600,
         HttpMethod: str = ...,
     ) -> str:
         """
         Generate a presigned url given a client, its method, and arguments.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#generate_presigned_url)
         """
+    async def get_test_execution_artifacts_url(
+        self, *, testExecutionId: str
+    ) -> GetTestExecutionArtifactsUrlResponseTypeDef:
+        """
+        The pre-signed Amazon S3 URL to download the test execution result artifacts.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.get_test_execution_artifacts_url)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#get_test_execution_artifacts_url)
+        """
     async def list_aggregated_utterances(
         self,
         *,
         botId: str,
         localeId: str,
         aggregationDuration: UtteranceAggregationDurationTypeDef,
         botAliasId: str = ...,
@@ -923,14 +1004,60 @@
     ) -> ListTagsForResourceResponseTypeDef:
         """
         Gets a list of tags associated with a resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#list_tags_for_resource)
         """
+    async def list_test_execution_result_items(
+        self,
+        *,
+        testExecutionId: str,
+        resultFilterBy: TestExecutionResultFilterByTypeDef,
+        maxResults: int = ...,
+        nextToken: str = ...
+    ) -> ListTestExecutionResultItemsResponseTypeDef:
+        """
+        Gets a list of test execution result items.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.list_test_execution_result_items)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#list_test_execution_result_items)
+        """
+    async def list_test_executions(
+        self,
+        *,
+        sortBy: TestExecutionSortByTypeDef = ...,
+        maxResults: int = ...,
+        nextToken: str = ...
+    ) -> ListTestExecutionsResponseTypeDef:
+        """
+        The list of test set executions.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.list_test_executions)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#list_test_executions)
+        """
+    async def list_test_set_records(
+        self, *, testSetId: str, maxResults: int = ..., nextToken: str = ...
+    ) -> ListTestSetRecordsResponseTypeDef:
+        """
+        The list of test set records.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.list_test_set_records)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#list_test_set_records)
+        """
+    async def list_test_sets(
+        self, *, sortBy: TestSetSortByTypeDef = ..., maxResults: int = ..., nextToken: str = ...
+    ) -> ListTestSetsResponseTypeDef:
+        """
+        The list of the test sets See also: [AWS API
+        Documentation](https://docs.aws.amazon.com/goto/WebAPI/models.lex.v2-2020-08-07/ListTestSets).
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.list_test_sets)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#list_test_sets)
+        """
     async def search_associated_transcripts(
         self,
         *,
         botId: str,
         botVersion: str,
         localeId: str,
         botRecommendationId: str,
@@ -972,14 +1099,44 @@
         """
         Starts importing a bot, bot locale, or custom vocabulary from a zip archive that
         you uploaded to an S3 bucket.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.start_import)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#start_import)
         """
+    async def start_test_execution(
+        self,
+        *,
+        testSetId: str,
+        target: TestExecutionTargetTypeDef,
+        apiMode: TestExecutionApiModeType,
+        testExecutionModality: TestExecutionModalityType = ...
+    ) -> StartTestExecutionResponseTypeDef:
+        """
+        The action to start test set execution.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.start_test_execution)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#start_test_execution)
+        """
+    async def start_test_set_generation(
+        self,
+        *,
+        testSetName: str,
+        storageLocation: TestSetStorageLocationTypeDef,
+        generationDataSource: TestSetGenerationDataSourceTypeDef,
+        roleArn: str,
+        description: str = ...,
+        testSetTags: Mapping[str, str] = ...
+    ) -> StartTestSetGenerationResponseTypeDef:
+        """
+        The action to start the generation of test set.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.start_test_set_generation)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#start_test_set_generation)
+        """
     async def stop_bot_recommendation(
         self, *, botId: str, botVersion: str, localeId: str, botRecommendationId: str
     ) -> StopBotRecommendationResponseTypeDef:
         """
         Stop an already running Bot Recommendation request.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.stop_bot_recommendation)
@@ -1150,14 +1307,23 @@
     ) -> UpdateSlotTypeResponseTypeDef:
         """
         Updates the configuration of an existing slot type.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.update_slot_type)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#update_slot_type)
         """
+    async def update_test_set(
+        self, *, testSetId: str, testSetName: str, description: str = ...
+    ) -> UpdateTestSetResponseTypeDef:
+        """
+        The action to update the test set.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.update_test_set)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#update_test_set)
+        """
     @overload
     def get_waiter(self, waiter_name: Literal["bot_alias_available"]) -> BotAliasAvailableWaiter:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lexv2-models.html#LexModelsV2.Client.get_waiter)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/client/#get_waiter)
         """
     @overload
```

### Comparing `types-aiobotocore-lexv2-models-2.5.0.post1/types_aiobotocore_lexv2_models/literals.py` & `types-aiobotocore-lexv2-models-2.5.1/types_aiobotocore_lexv2_models/literals.py`

 * *Files 4% similar despite different names*

```diff
@@ -43,14 +43,15 @@
     "BotSortAttributeType",
     "BotStatusType",
     "BotTypeType",
     "BotVersionAvailableWaiterName",
     "BotVersionSortAttributeType",
     "BuiltInIntentSortAttributeType",
     "BuiltInSlotTypeSortAttributeType",
+    "ConversationLogsInputModeFilterType",
     "CustomVocabularyStatusType",
     "DialogActionTypeType",
     "EffectType",
     "ErrorCodeType",
     "ExportFilterNameType",
     "ExportFilterOperatorType",
     "ExportSortAttributeType",
@@ -76,14 +77,25 @@
     "SlotSortAttributeType",
     "SlotTypeCategoryType",
     "SlotTypeFilterNameType",
     "SlotTypeFilterOperatorType",
     "SlotTypeSortAttributeType",
     "SlotValueResolutionStrategyType",
     "SortOrderType",
+    "TestExecutionApiModeType",
+    "TestExecutionModalityType",
+    "TestExecutionSortAttributeType",
+    "TestExecutionStatusType",
+    "TestResultMatchStatusType",
+    "TestResultTypeFilterType",
+    "TestSetDiscrepancyReportStatusType",
+    "TestSetGenerationStatusType",
+    "TestSetModalityType",
+    "TestSetSortAttributeType",
+    "TestSetStatusType",
     "TimeDimensionType",
     "TranscriptFormatType",
     "VoiceEngineType",
     "LexModelsV2ServiceName",
     "ServiceName",
     "ResourceServiceName",
     "WaiterName",
@@ -136,14 +148,15 @@
     "Available", "Creating", "Deleting", "Failed", "Importing", "Inactive", "Updating", "Versioning"
 ]
 BotTypeType = Literal["Bot", "BotNetwork"]
 BotVersionAvailableWaiterName = Literal["bot_version_available"]
 BotVersionSortAttributeType = Literal["BotVersion"]
 BuiltInIntentSortAttributeType = Literal["IntentSignature"]
 BuiltInSlotTypeSortAttributeType = Literal["SlotTypeSignature"]
+ConversationLogsInputModeFilterType = Literal["Speech", "Text"]
 CustomVocabularyStatusType = Literal["Creating", "Deleting", "Exporting", "Importing", "Ready"]
 DialogActionTypeType = Literal[
     "CloseIntent",
     "ConfirmIntent",
     "ElicitIntent",
     "ElicitSlot",
     "EndConversation",
@@ -159,18 +172,18 @@
     "RESOURCE_ALREADY_EXISTS",
     "RESOURCE_DOES_NOT_EXIST",
 ]
 ExportFilterNameType = Literal["ExportResourceType"]
 ExportFilterOperatorType = Literal["CO", "EQ"]
 ExportSortAttributeType = Literal["LastUpdatedDateTime"]
 ExportStatusType = Literal["Completed", "Deleting", "Failed", "InProgress"]
-ImportExportFileFormatType = Literal["LexJson", "TSV"]
+ImportExportFileFormatType = Literal["CSV", "LexJson", "TSV"]
 ImportFilterNameType = Literal["ImportResourceType"]
 ImportFilterOperatorType = Literal["CO", "EQ"]
-ImportResourceTypeType = Literal["Bot", "BotLocale", "CustomVocabulary"]
+ImportResourceTypeType = Literal["Bot", "BotLocale", "CustomVocabulary", "TestSet"]
 ImportSortAttributeType = Literal["LastUpdatedDateTime"]
 ImportStatusType = Literal["Completed", "Deleting", "Failed", "InProgress"]
 IntentFilterNameType = Literal["IntentName"]
 IntentFilterOperatorType = Literal["CO", "EQ"]
 IntentSortAttributeType = Literal["IntentName", "LastUpdatedDateTime"]
 MergeStrategyType = Literal["Append", "FailOnConflict", "Overwrite"]
 MessageSelectionStrategyType = Literal["Ordered", "Random"]
@@ -184,14 +197,35 @@
 SlotSortAttributeType = Literal["LastUpdatedDateTime", "SlotName"]
 SlotTypeCategoryType = Literal["Composite", "Custom", "Extended", "ExternalGrammar"]
 SlotTypeFilterNameType = Literal["ExternalSourceType", "SlotTypeName"]
 SlotTypeFilterOperatorType = Literal["CO", "EQ"]
 SlotTypeSortAttributeType = Literal["LastUpdatedDateTime", "SlotTypeName"]
 SlotValueResolutionStrategyType = Literal["Concatenation", "OriginalValue", "TopResolution"]
 SortOrderType = Literal["Ascending", "Descending"]
+TestExecutionApiModeType = Literal["NonStreaming", "Streaming"]
+TestExecutionModalityType = Literal["Audio", "Text"]
+TestExecutionSortAttributeType = Literal["CreationDateTime", "TestSetName"]
+TestExecutionStatusType = Literal[
+    "Completed", "Failed", "InProgress", "Pending", "Stopped", "Stopping", "Waiting"
+]
+TestResultMatchStatusType = Literal["ExecutionError", "Matched", "Mismatched"]
+TestResultTypeFilterType = Literal[
+    "ConversationLevelTestResults",
+    "IntentClassificationTestResults",
+    "OverallTestResults",
+    "SlotResolutionTestResults",
+    "UtteranceLevelResults",
+]
+TestSetDiscrepancyReportStatusType = Literal["Completed", "Failed", "InProgress"]
+TestSetGenerationStatusType = Literal["Failed", "Generating", "Pending", "Ready"]
+TestSetModalityType = Literal["Audio", "Text"]
+TestSetSortAttributeType = Literal["LastUpdatedDateTime", "TestSetName"]
+TestSetStatusType = Literal[
+    "Deleting", "Importing", "PendingAnnotation", "Ready", "ValidationError"
+]
 TimeDimensionType = Literal["Days", "Hours", "Weeks"]
 TranscriptFormatType = Literal["Lex"]
 VoiceEngineType = Literal["neural", "standard"]
 LexModelsV2ServiceName = Literal["lexv2-models"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
@@ -250,14 +284,15 @@
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
@@ -336,14 +371,15 @@
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
@@ -354,14 +390,15 @@
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
@@ -397,14 +434,15 @@
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
@@ -423,16 +461,19 @@
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
@@ -516,15 +557,17 @@
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

### Comparing `types-aiobotocore-lexv2-models-2.5.0.post1/types_aiobotocore_lexv2_models/literals.pyi` & `types-aiobotocore-lexv2-models-2.5.1/types_aiobotocore_lexv2_models/literals.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -42,14 +42,15 @@
     "BotSortAttributeType",
     "BotStatusType",
     "BotTypeType",
     "BotVersionAvailableWaiterName",
     "BotVersionSortAttributeType",
     "BuiltInIntentSortAttributeType",
     "BuiltInSlotTypeSortAttributeType",
+    "ConversationLogsInputModeFilterType",
     "CustomVocabularyStatusType",
     "DialogActionTypeType",
     "EffectType",
     "ErrorCodeType",
     "ExportFilterNameType",
     "ExportFilterOperatorType",
     "ExportSortAttributeType",
@@ -75,14 +76,25 @@
     "SlotSortAttributeType",
     "SlotTypeCategoryType",
     "SlotTypeFilterNameType",
     "SlotTypeFilterOperatorType",
     "SlotTypeSortAttributeType",
     "SlotValueResolutionStrategyType",
     "SortOrderType",
+    "TestExecutionApiModeType",
+    "TestExecutionModalityType",
+    "TestExecutionSortAttributeType",
+    "TestExecutionStatusType",
+    "TestResultMatchStatusType",
+    "TestResultTypeFilterType",
+    "TestSetDiscrepancyReportStatusType",
+    "TestSetGenerationStatusType",
+    "TestSetModalityType",
+    "TestSetSortAttributeType",
+    "TestSetStatusType",
     "TimeDimensionType",
     "TranscriptFormatType",
     "VoiceEngineType",
     "LexModelsV2ServiceName",
     "ServiceName",
     "ResourceServiceName",
     "WaiterName",
@@ -134,14 +146,15 @@
     "Available", "Creating", "Deleting", "Failed", "Importing", "Inactive", "Updating", "Versioning"
 ]
 BotTypeType = Literal["Bot", "BotNetwork"]
 BotVersionAvailableWaiterName = Literal["bot_version_available"]
 BotVersionSortAttributeType = Literal["BotVersion"]
 BuiltInIntentSortAttributeType = Literal["IntentSignature"]
 BuiltInSlotTypeSortAttributeType = Literal["SlotTypeSignature"]
+ConversationLogsInputModeFilterType = Literal["Speech", "Text"]
 CustomVocabularyStatusType = Literal["Creating", "Deleting", "Exporting", "Importing", "Ready"]
 DialogActionTypeType = Literal[
     "CloseIntent",
     "ConfirmIntent",
     "ElicitIntent",
     "ElicitSlot",
     "EndConversation",
@@ -157,18 +170,18 @@
     "RESOURCE_ALREADY_EXISTS",
     "RESOURCE_DOES_NOT_EXIST",
 ]
 ExportFilterNameType = Literal["ExportResourceType"]
 ExportFilterOperatorType = Literal["CO", "EQ"]
 ExportSortAttributeType = Literal["LastUpdatedDateTime"]
 ExportStatusType = Literal["Completed", "Deleting", "Failed", "InProgress"]
-ImportExportFileFormatType = Literal["LexJson", "TSV"]
+ImportExportFileFormatType = Literal["CSV", "LexJson", "TSV"]
 ImportFilterNameType = Literal["ImportResourceType"]
 ImportFilterOperatorType = Literal["CO", "EQ"]
-ImportResourceTypeType = Literal["Bot", "BotLocale", "CustomVocabulary"]
+ImportResourceTypeType = Literal["Bot", "BotLocale", "CustomVocabulary", "TestSet"]
 ImportSortAttributeType = Literal["LastUpdatedDateTime"]
 ImportStatusType = Literal["Completed", "Deleting", "Failed", "InProgress"]
 IntentFilterNameType = Literal["IntentName"]
 IntentFilterOperatorType = Literal["CO", "EQ"]
 IntentSortAttributeType = Literal["IntentName", "LastUpdatedDateTime"]
 MergeStrategyType = Literal["Append", "FailOnConflict", "Overwrite"]
 MessageSelectionStrategyType = Literal["Ordered", "Random"]
@@ -182,14 +195,35 @@
 SlotSortAttributeType = Literal["LastUpdatedDateTime", "SlotName"]
 SlotTypeCategoryType = Literal["Composite", "Custom", "Extended", "ExternalGrammar"]
 SlotTypeFilterNameType = Literal["ExternalSourceType", "SlotTypeName"]
 SlotTypeFilterOperatorType = Literal["CO", "EQ"]
 SlotTypeSortAttributeType = Literal["LastUpdatedDateTime", "SlotTypeName"]
 SlotValueResolutionStrategyType = Literal["Concatenation", "OriginalValue", "TopResolution"]
 SortOrderType = Literal["Ascending", "Descending"]
+TestExecutionApiModeType = Literal["NonStreaming", "Streaming"]
+TestExecutionModalityType = Literal["Audio", "Text"]
+TestExecutionSortAttributeType = Literal["CreationDateTime", "TestSetName"]
+TestExecutionStatusType = Literal[
+    "Completed", "Failed", "InProgress", "Pending", "Stopped", "Stopping", "Waiting"
+]
+TestResultMatchStatusType = Literal["ExecutionError", "Matched", "Mismatched"]
+TestResultTypeFilterType = Literal[
+    "ConversationLevelTestResults",
+    "IntentClassificationTestResults",
+    "OverallTestResults",
+    "SlotResolutionTestResults",
+    "UtteranceLevelResults",
+]
+TestSetDiscrepancyReportStatusType = Literal["Completed", "Failed", "InProgress"]
+TestSetGenerationStatusType = Literal["Failed", "Generating", "Pending", "Ready"]
+TestSetModalityType = Literal["Audio", "Text"]
+TestSetSortAttributeType = Literal["LastUpdatedDateTime", "TestSetName"]
+TestSetStatusType = Literal[
+    "Deleting", "Importing", "PendingAnnotation", "Ready", "ValidationError"
+]
 TimeDimensionType = Literal["Days", "Hours", "Weeks"]
 TranscriptFormatType = Literal["Lex"]
 VoiceEngineType = Literal["neural", "standard"]
 LexModelsV2ServiceName = Literal["lexv2-models"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
@@ -248,14 +282,15 @@
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
@@ -334,14 +369,15 @@
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
@@ -352,14 +388,15 @@
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
@@ -395,14 +432,15 @@
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
@@ -421,16 +459,19 @@
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
@@ -514,15 +555,17 @@
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

### Comparing `types-aiobotocore-lexv2-models-2.5.0.post1/types_aiobotocore_lexv2_models/type_defs.py` & `types-aiobotocore-lexv2-models-2.5.1/types_aiobotocore_lexv2_models/type_defs.pyi`

 * *Files 10% similar despite different names*

```diff
@@ -2,17 +2,17 @@
 Type annotations for lexv2-models service type definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/type_defs/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_lexv2_models.type_defs import AdvancedRecognitionSettingTypeDef
+    from types_aiobotocore_lexv2_models.type_defs import ActiveContextTypeDef
 
-    data: AdvancedRecognitionSettingTypeDef = {...}
+    data: ActiveContextTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
 from typing import Any, Dict, List, Mapping, Sequence
 
 from .literals import (
@@ -23,14 +23,15 @@
     BotFilterNameType,
     BotFilterOperatorType,
     BotLocaleFilterOperatorType,
     BotLocaleStatusType,
     BotRecommendationStatusType,
     BotStatusType,
     BotTypeType,
+    ConversationLogsInputModeFilterType,
     CustomVocabularyStatusType,
     DialogActionTypeType,
     EffectType,
     ErrorCodeType,
     ExportFilterOperatorType,
     ExportStatusType,
     ImportExportFileFormatType,
@@ -50,46 +51,59 @@
     SlotSortAttributeType,
     SlotTypeCategoryType,
     SlotTypeFilterNameType,
     SlotTypeFilterOperatorType,
     SlotTypeSortAttributeType,
     SlotValueResolutionStrategyType,
     SortOrderType,
+    TestExecutionApiModeType,
+    TestExecutionModalityType,
+    TestExecutionSortAttributeType,
+    TestExecutionStatusType,
+    TestResultMatchStatusType,
+    TestResultTypeFilterType,
+    TestSetDiscrepancyReportStatusType,
+    TestSetGenerationStatusType,
+    TestSetModalityType,
+    TestSetSortAttributeType,
+    TestSetStatusType,
     TimeDimensionType,
     VoiceEngineType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
+    "ActiveContextTypeDef",
     "AdvancedRecognitionSettingTypeDef",
+    "ExecutionErrorDetailsTypeDef",
+    "AgentTurnSpecificationTypeDef",
     "AggregatedUtterancesFilterTypeDef",
     "AggregatedUtterancesSortByTypeDef",
     "AggregatedUtterancesSummaryTypeDef",
     "AllowedInputTypesTypeDef",
     "AssociatedTranscriptFilterTypeDef",
     "AssociatedTranscriptTypeDef",
     "AudioSpecificationTypeDef",
     "DTMFSpecificationTypeDef",
     "S3BucketLogDestinationTypeDef",
     "NewCustomVocabularyItemTypeDef",
     "CustomVocabularyItemTypeDef",
     "FailedCustomVocabularyItemTypeDef",
-    "ResponseMetadataTypeDef",
     "CustomVocabularyEntryIdTypeDef",
     "BotAliasHistoryEventTypeDef",
     "BotAliasSummaryTypeDef",
+    "BotAliasTestExecutionTargetTypeDef",
     "BotExportSpecificationTypeDef",
     "BotFilterTypeDef",
     "DataPrivacyTypeDef",
     "BotLocaleExportSpecificationTypeDef",
     "BotLocaleFilterTypeDef",
     "BotLocaleHistoryEventTypeDef",
     "VoiceSettingsTypeDef",
@@ -101,133 +115,166 @@
     "BotRecommendationSummaryTypeDef",
     "BotSortByTypeDef",
     "BotSummaryTypeDef",
     "BotVersionLocaleDetailsTypeDef",
     "BotVersionSortByTypeDef",
     "BotVersionSummaryTypeDef",
     "BuildBotLocaleRequestRequestTypeDef",
+    "BuildBotLocaleResponseTypeDef",
     "BuiltInIntentSortByTypeDef",
     "BuiltInIntentSummaryTypeDef",
     "BuiltInSlotTypeSortByTypeDef",
     "BuiltInSlotTypeSummaryTypeDef",
     "ButtonTypeDef",
     "CloudWatchLogGroupLogDestinationTypeDef",
     "LambdaCodeHookTypeDef",
     "SubSlotTypeCompositionTypeDef",
     "ConditionTypeDef",
+    "ConversationLevelIntentClassificationResultItemTypeDef",
+    "ConversationLevelResultDetailTypeDef",
+    "ConversationLevelSlotResolutionResultItemTypeDef",
+    "ConversationLevelTestResultsFilterByTypeDef",
+    "ConversationLogsDataSourceFilterByTypeDef",
     "SentimentAnalysisSettingsTypeDef",
     "DialogCodeHookSettingsTypeDef",
     "InputContextTypeDef",
     "KendraConfigurationTypeDef",
     "OutputContextTypeDef",
     "SampleUtteranceTypeDef",
     "CreateResourcePolicyRequestRequestTypeDef",
+    "CreateResourcePolicyResponseTypeDef",
     "PrincipalTypeDef",
+    "CreateResourcePolicyStatementResponseTypeDef",
     "MultipleValuesSettingTypeDef",
     "ObfuscationSettingTypeDef",
+    "CreateUploadUrlResponseTypeDef",
     "CustomPayloadTypeDef",
     "CustomVocabularyExportSpecificationTypeDef",
     "CustomVocabularyImportSpecificationTypeDef",
     "DateRangeFilterTypeDef",
     "DeleteBotAliasRequestRequestTypeDef",
+    "DeleteBotAliasResponseTypeDef",
     "DeleteBotLocaleRequestRequestTypeDef",
+    "DeleteBotLocaleResponseTypeDef",
     "DeleteBotRequestRequestTypeDef",
+    "DeleteBotResponseTypeDef",
     "DeleteBotVersionRequestRequestTypeDef",
+    "DeleteBotVersionResponseTypeDef",
     "DeleteCustomVocabularyRequestRequestTypeDef",
+    "DeleteCustomVocabularyResponseTypeDef",
     "DeleteExportRequestRequestTypeDef",
+    "DeleteExportResponseTypeDef",
     "DeleteImportRequestRequestTypeDef",
+    "DeleteImportResponseTypeDef",
     "DeleteIntentRequestRequestTypeDef",
     "DeleteResourcePolicyRequestRequestTypeDef",
+    "DeleteResourcePolicyResponseTypeDef",
     "DeleteResourcePolicyStatementRequestRequestTypeDef",
+    "DeleteResourcePolicyStatementResponseTypeDef",
     "DeleteSlotRequestRequestTypeDef",
     "DeleteSlotTypeRequestRequestTypeDef",
+    "DeleteTestSetRequestRequestTypeDef",
     "DeleteUtterancesRequestRequestTypeDef",
     "WaiterConfigTypeDef",
     "DescribeBotAliasRequestRequestTypeDef",
     "ParentBotNetworkTypeDef",
     "DescribeBotLocaleRequestRequestTypeDef",
     "DescribeBotRecommendationRequestRequestTypeDef",
     "EncryptionSettingTypeDef",
     "DescribeBotRequestRequestTypeDef",
     "DescribeBotVersionRequestRequestTypeDef",
     "DescribeCustomVocabularyMetadataRequestRequestTypeDef",
+    "DescribeCustomVocabularyMetadataResponseTypeDef",
     "DescribeExportRequestRequestTypeDef",
     "DescribeImportRequestRequestTypeDef",
     "DescribeIntentRequestRequestTypeDef",
     "SlotPriorityTypeDef",
     "DescribeResourcePolicyRequestRequestTypeDef",
+    "DescribeResourcePolicyResponseTypeDef",
     "DescribeSlotRequestRequestTypeDef",
     "DescribeSlotTypeRequestRequestTypeDef",
+    "DescribeTestExecutionRequestRequestTypeDef",
+    "DescribeTestSetDiscrepancyReportRequestRequestTypeDef",
+    "DescribeTestSetGenerationRequestRequestTypeDef",
+    "TestSetStorageLocationTypeDef",
+    "DescribeTestSetRequestRequestTypeDef",
     "DialogActionTypeDef",
     "IntentOverrideTypeDef",
     "ElicitationCodeHookInvocationSettingTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "ExportFilterTypeDef",
+    "TestSetExportSpecificationTypeDef",
     "ExportSortByTypeDef",
+    "GetTestExecutionArtifactsUrlRequestRequestTypeDef",
+    "GetTestExecutionArtifactsUrlResponseTypeDef",
     "GrammarSlotTypeSourceTypeDef",
     "ImportFilterTypeDef",
     "ImportSortByTypeDef",
     "ImportSummaryTypeDef",
+    "RuntimeHintsTypeDef",
+    "IntentClassificationTestResultItemCountsTypeDef",
     "IntentFilterTypeDef",
     "IntentSortByTypeDef",
     "ListBotAliasesRequestRequestTypeDef",
     "ListBotRecommendationsRequestRequestTypeDef",
     "ListCustomVocabularyItemsRequestRequestTypeDef",
     "ListRecommendedIntentsRequestRequestTypeDef",
     "RecommendedIntentSummaryTypeDef",
     "SlotTypeFilterTypeDef",
     "SlotTypeSortByTypeDef",
     "SlotTypeSummaryTypeDef",
     "SlotFilterTypeDef",
     "SlotSortByTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "TestExecutionSortByTypeDef",
+    "ListTestSetRecordsRequestRequestTypeDef",
+    "TestSetSortByTypeDef",
     "PlainTextMessageTypeDef",
     "SSMLMessageTypeDef",
+    "OverallTestResultItemTypeDef",
     "PathFormatTypeDef",
     "TextInputSpecificationTypeDef",
     "RelativeAggregationDurationTypeDef",
+    "ResponseMetadataTypeDef",
+    "RuntimeHintValueTypeDef",
     "SampleValueTypeDef",
     "SlotDefaultValueTypeDef",
+    "SlotResolutionTestResultItemCountsTypeDef",
     "SlotValueTypeDef",
     "SlotValueRegexFilterTypeDef",
     "StopBotRecommendationRequestRequestTypeDef",
+    "StopBotRecommendationResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
+    "TestSetIntentDiscrepancyItemTypeDef",
+    "TestSetSlotDiscrepancyItemTypeDef",
+    "TestSetDiscrepancyReportBotAliasTargetTypeDef",
+    "TestSetImportInputLocationTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateExportRequestRequestTypeDef",
     "UpdateResourcePolicyRequestRequestTypeDef",
+    "UpdateResourcePolicyResponseTypeDef",
+    "UpdateTestSetRequestRequestTypeDef",
+    "UserTurnIntentOutputTypeDef",
+    "UserTurnSlotOutputTypeDef",
+    "UtteranceAudioInputSpecificationTypeDef",
+    "AgentTurnResultTypeDef",
     "SearchAssociatedTranscriptsRequestRequestTypeDef",
+    "SearchAssociatedTranscriptsResponseTypeDef",
     "AudioAndDTMFInputSpecificationTypeDef",
     "AudioLogDestinationTypeDef",
     "BatchCreateCustomVocabularyItemRequestRequestTypeDef",
     "BatchUpdateCustomVocabularyItemRequestRequestTypeDef",
+    "ListCustomVocabularyItemsResponseTypeDef",
     "BatchCreateCustomVocabularyItemResponseTypeDef",
     "BatchDeleteCustomVocabularyItemResponseTypeDef",
     "BatchUpdateCustomVocabularyItemResponseTypeDef",
-    "BuildBotLocaleResponseTypeDef",
-    "CreateResourcePolicyResponseTypeDef",
-    "CreateResourcePolicyStatementResponseTypeDef",
-    "CreateUploadUrlResponseTypeDef",
-    "DeleteBotAliasResponseTypeDef",
-    "DeleteBotLocaleResponseTypeDef",
-    "DeleteBotResponseTypeDef",
-    "DeleteBotVersionResponseTypeDef",
-    "DeleteCustomVocabularyResponseTypeDef",
-    "DeleteExportResponseTypeDef",
-    "DeleteImportResponseTypeDef",
-    "DeleteResourcePolicyResponseTypeDef",
-    "DeleteResourcePolicyStatementResponseTypeDef",
-    "DescribeCustomVocabularyMetadataResponseTypeDef",
-    "DescribeResourcePolicyResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ListCustomVocabularyItemsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "SearchAssociatedTranscriptsResponseTypeDef",
-    "StopBotRecommendationResponseTypeDef",
-    "UpdateResourcePolicyResponseTypeDef",
     "BatchDeleteCustomVocabularyItemRequestRequestTypeDef",
     "ListBotAliasesResponseTypeDef",
+    "TestExecutionTargetTypeDef",
     "BotImportSpecificationTypeDef",
     "BotLocaleImportSpecificationTypeDef",
     "CreateBotLocaleRequestRequestTypeDef",
     "CreateBotLocaleResponseTypeDef",
     "DescribeBotLocaleResponseTypeDef",
     "UpdateBotLocaleRequestRequestTypeDef",
     "UpdateBotLocaleResponseTypeDef",
@@ -250,102 +297,149 @@
     "ListBuiltInIntentsResponseTypeDef",
     "ListBuiltInSlotTypesRequestRequestTypeDef",
     "ListBuiltInSlotTypesResponseTypeDef",
     "ImageResponseCardTypeDef",
     "TextLogDestinationTypeDef",
     "CodeHookSpecificationTypeDef",
     "CompositeSlotTypeSettingTypeDef",
+    "ConversationLevelTestResultItemTypeDef",
+    "TestExecutionResultFilterByTypeDef",
+    "ConversationLogsDataSourceTypeDef",
     "IntentSummaryTypeDef",
     "CreateResourcePolicyStatementRequestRequestTypeDef",
-    "ExportResourceSpecificationTypeDef",
     "LexTranscriptFilterTypeDef",
     "DescribeBotAliasRequestBotAliasAvailableWaitTypeDef",
     "DescribeBotLocaleRequestBotLocaleBuiltWaitTypeDef",
     "DescribeBotLocaleRequestBotLocaleCreatedWaitTypeDef",
     "DescribeBotLocaleRequestBotLocaleExpressTestingAvailableWaitTypeDef",
     "DescribeBotRequestBotAvailableWaitTypeDef",
     "DescribeBotVersionRequestBotVersionAvailableWaitTypeDef",
     "DescribeExportRequestBotExportCompletedWaitTypeDef",
     "DescribeImportRequestBotImportCompletedWaitTypeDef",
     "DescribeBotVersionResponseTypeDef",
     "UpdateBotRecommendationRequestRequestTypeDef",
+    "DescribeTestSetResponseTypeDef",
+    "TestSetSummaryTypeDef",
+    "UpdateTestSetResponseTypeDef",
     "DialogStateTypeDef",
+    "ExportResourceSpecificationTypeDef",
     "ListExportsRequestRequestTypeDef",
     "GrammarSlotTypeSettingTypeDef",
     "ListImportsRequestRequestTypeDef",
     "ListImportsResponseTypeDef",
+    "InputSessionStateSpecificationTypeDef",
+    "IntentClassificationTestResultItemTypeDef",
     "ListIntentsRequestRequestTypeDef",
     "ListRecommendedIntentsResponseTypeDef",
     "ListSlotTypesRequestRequestTypeDef",
     "ListSlotTypesResponseTypeDef",
     "ListSlotsRequestRequestTypeDef",
+    "ListTestExecutionsRequestRequestTypeDef",
+    "ListTestSetsRequestRequestTypeDef",
+    "OverallTestResultsTypeDef",
     "UtteranceAggregationDurationTypeDef",
+    "RuntimeHintDetailsTypeDef",
     "SlotTypeValueTypeDef",
     "SlotDefaultValueSpecificationTypeDef",
+    "SlotResolutionTestResultItemTypeDef",
     "SlotValueOverrideTypeDef",
     "SlotValueSelectionSettingTypeDef",
+    "TestSetDiscrepancyErrorsTypeDef",
+    "TestSetDiscrepancyReportResourceTargetTypeDef",
+    "TestSetImportResourceSpecificationTypeDef",
+    "UserTurnOutputSpecificationTypeDef",
+    "UtteranceInputSpecificationTypeDef",
     "PromptAttemptSpecificationTypeDef",
     "AudioLogSettingTypeDef",
-    "ImportResourceSpecificationTypeDef",
+    "DescribeTestExecutionResponseTypeDef",
+    "StartTestExecutionRequestRequestTypeDef",
+    "StartTestExecutionResponseTypeDef",
+    "TestExecutionSummaryTypeDef",
     "BotRecommendationResultsTypeDef",
     "MessageTypeDef",
     "TextLogSettingTypeDef",
     "BotAliasLocaleSettingsTypeDef",
+    "ConversationLevelTestResultsTypeDef",
+    "ListTestExecutionResultItemsRequestRequestTypeDef",
+    "TestSetGenerationDataSourceTypeDef",
     "ListIntentsResponseTypeDef",
+    "TranscriptFilterTypeDef",
+    "ListTestSetsResponseTypeDef",
     "CreateExportRequestRequestTypeDef",
     "CreateExportResponseTypeDef",
     "DescribeExportResponseTypeDef",
     "ExportSummaryTypeDef",
     "UpdateExportResponseTypeDef",
-    "TranscriptFilterTypeDef",
     "ExternalSourceSettingTypeDef",
+    "IntentClassificationTestResultsTypeDef",
     "ListAggregatedUtterancesRequestRequestTypeDef",
     "ListAggregatedUtterancesResponseTypeDef",
-    "DescribeImportResponseTypeDef",
-    "StartImportRequestRequestTypeDef",
-    "StartImportResponseTypeDef",
+    "IntentLevelSlotResolutionTestResultItemTypeDef",
+    "CreateTestSetDiscrepancyReportRequestRequestTypeDef",
+    "CreateTestSetDiscrepancyReportResponseTypeDef",
+    "DescribeTestSetDiscrepancyReportResponseTypeDef",
+    "ImportResourceSpecificationTypeDef",
+    "UserTurnInputSpecificationTypeDef",
+    "ListTestExecutionsResponseTypeDef",
     "MessageGroupTypeDef",
     "ConversationLogSettingsTypeDef",
-    "ListExportsResponseTypeDef",
+    "DescribeTestSetGenerationResponseTypeDef",
+    "StartTestSetGenerationRequestRequestTypeDef",
+    "StartTestSetGenerationResponseTypeDef",
     "S3BucketTranscriptSourceTypeDef",
+    "ListExportsResponseTypeDef",
     "CreateSlotTypeRequestRequestTypeDef",
     "CreateSlotTypeResponseTypeDef",
     "DescribeSlotTypeResponseTypeDef",
     "UpdateSlotTypeRequestRequestTypeDef",
     "UpdateSlotTypeResponseTypeDef",
+    "IntentLevelSlotResolutionTestResultsTypeDef",
+    "DescribeImportResponseTypeDef",
+    "StartImportRequestRequestTypeDef",
+    "StartImportResponseTypeDef",
+    "UserTurnResultTypeDef",
+    "UserTurnSpecificationTypeDef",
     "FulfillmentStartResponseSpecificationTypeDef",
     "FulfillmentUpdateResponseSpecificationTypeDef",
     "PromptSpecificationTypeDef",
     "ResponseSpecificationTypeDef",
     "StillWaitingResponseSpecificationTypeDef",
     "CreateBotAliasRequestRequestTypeDef",
     "CreateBotAliasResponseTypeDef",
     "DescribeBotAliasResponseTypeDef",
     "UpdateBotAliasRequestRequestTypeDef",
     "UpdateBotAliasResponseTypeDef",
     "TranscriptSourceSettingTypeDef",
+    "TestSetTurnResultTypeDef",
+    "TurnSpecificationTypeDef",
     "FulfillmentUpdatesSpecificationTypeDef",
     "SlotSummaryTypeDef",
     "ConditionalBranchTypeDef",
     "DefaultConditionalBranchTypeDef",
     "WaitAndContinueSpecificationTypeDef",
     "DescribeBotRecommendationResponseTypeDef",
     "StartBotRecommendationRequestRequestTypeDef",
     "StartBotRecommendationResponseTypeDef",
     "UpdateBotRecommendationResponseTypeDef",
+    "UtteranceLevelTestResultItemTypeDef",
+    "TestSetTurnRecordTypeDef",
     "ListSlotsResponseTypeDef",
     "ConditionalSpecificationTypeDef",
     "SubSlotValueElicitationSettingTypeDef",
+    "UtteranceLevelTestResultsTypeDef",
+    "ListTestSetRecordsResponseTypeDef",
     "IntentClosingSettingTypeDef",
     "PostDialogCodeHookInvocationSpecificationTypeDef",
     "PostFulfillmentStatusSpecificationTypeDef",
     "SpecificationsTypeDef",
+    "TestExecutionResultItemsTypeDef",
     "DialogCodeHookInvocationSettingTypeDef",
     "FulfillmentCodeHookSettingsTypeDef",
     "SubSlotSettingTypeDef",
+    "ListTestExecutionResultItemsResponseTypeDef",
     "InitialResponseSettingTypeDef",
     "IntentConfirmationSettingTypeDef",
     "SlotCaptureSettingTypeDef",
     "CreateIntentRequestRequestTypeDef",
     "CreateIntentResponseTypeDef",
     "DescribeIntentResponseTypeDef",
     "UpdateIntentRequestRequestTypeDef",
@@ -354,22 +448,44 @@
     "CreateSlotRequestRequestTypeDef",
     "CreateSlotResponseTypeDef",
     "DescribeSlotResponseTypeDef",
     "UpdateSlotRequestRequestTypeDef",
     "UpdateSlotResponseTypeDef",
 )
 
+ActiveContextTypeDef = TypedDict(
+    "ActiveContextTypeDef",
+    {
+        "name": str,
+    },
+)
+
 AdvancedRecognitionSettingTypeDef = TypedDict(
     "AdvancedRecognitionSettingTypeDef",
     {
         "audioRecognitionStrategy": Literal["UseSlotValuesAsCustomVocabulary"],
     },
     total=False,
 )
 
+ExecutionErrorDetailsTypeDef = TypedDict(
+    "ExecutionErrorDetailsTypeDef",
+    {
+        "errorCode": str,
+        "errorMessage": str,
+    },
+)
+
+AgentTurnSpecificationTypeDef = TypedDict(
+    "AgentTurnSpecificationTypeDef",
+    {
+        "agentPrompt": str,
+    },
+)
+
 AggregatedUtterancesFilterTypeDef = TypedDict(
     "AggregatedUtterancesFilterTypeDef",
     {
         "name": Literal["Utterance"],
         "values": Sequence[str],
         "operator": AggregatedUtterancesFilterOperatorType,
     },
@@ -449,21 +565,19 @@
     "_OptionalS3BucketLogDestinationTypeDef",
     {
         "kmsKeyArn": str,
     },
     total=False,
 )
 
-
 class S3BucketLogDestinationTypeDef(
     _RequiredS3BucketLogDestinationTypeDef, _OptionalS3BucketLogDestinationTypeDef
 ):
     pass
 
-
 _RequiredNewCustomVocabularyItemTypeDef = TypedDict(
     "_RequiredNewCustomVocabularyItemTypeDef",
     {
         "phrase": str,
     },
 )
 _OptionalNewCustomVocabularyItemTypeDef = TypedDict(
@@ -471,21 +585,19 @@
     {
         "weight": int,
         "displayAs": str,
     },
     total=False,
 )
 
-
 class NewCustomVocabularyItemTypeDef(
     _RequiredNewCustomVocabularyItemTypeDef, _OptionalNewCustomVocabularyItemTypeDef
 ):
     pass
 
-
 _RequiredCustomVocabularyItemTypeDef = TypedDict(
     "_RequiredCustomVocabularyItemTypeDef",
     {
         "itemId": str,
         "phrase": str,
     },
 )
@@ -494,42 +606,29 @@
     {
         "weight": int,
         "displayAs": str,
     },
     total=False,
 )
 
-
 class CustomVocabularyItemTypeDef(
     _RequiredCustomVocabularyItemTypeDef, _OptionalCustomVocabularyItemTypeDef
 ):
     pass
 
-
 FailedCustomVocabularyItemTypeDef = TypedDict(
     "FailedCustomVocabularyItemTypeDef",
     {
         "itemId": str,
         "errorMessage": str,
         "errorCode": ErrorCodeType,
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
 CustomVocabularyEntryIdTypeDef = TypedDict(
     "CustomVocabularyEntryIdTypeDef",
     {
         "itemId": str,
     },
 )
 
@@ -553,14 +652,23 @@
         "botAliasStatus": BotAliasStatusType,
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
     },
     total=False,
 )
 
+BotAliasTestExecutionTargetTypeDef = TypedDict(
+    "BotAliasTestExecutionTargetTypeDef",
+    {
+        "botId": str,
+        "botAliasId": str,
+        "localeId": str,
+    },
+)
+
 BotExportSpecificationTypeDef = TypedDict(
     "BotExportSpecificationTypeDef",
     {
         "botId": str,
         "botVersion": str,
     },
 )
@@ -617,19 +725,17 @@
     "_OptionalVoiceSettingsTypeDef",
     {
         "engine": VoiceEngineType,
     },
     total=False,
 )
 
-
 class VoiceSettingsTypeDef(_RequiredVoiceSettingsTypeDef, _OptionalVoiceSettingsTypeDef):
     pass
 
-
 BotLocaleSortByTypeDef = TypedDict(
     "BotLocaleSortByTypeDef",
     {
         "attribute": Literal["BotLocaleName"],
         "order": SortOrderType,
     },
 )
@@ -686,21 +792,19 @@
     {
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
     },
     total=False,
 )
 
-
 class BotRecommendationSummaryTypeDef(
     _RequiredBotRecommendationSummaryTypeDef, _OptionalBotRecommendationSummaryTypeDef
 ):
     pass
 
-
 BotSortByTypeDef = TypedDict(
     "BotSortByTypeDef",
     {
         "attribute": Literal["BotName"],
         "order": SortOrderType,
     },
 )
@@ -751,14 +855,26 @@
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
     },
 )
 
+BuildBotLocaleResponseTypeDef = TypedDict(
+    "BuildBotLocaleResponseTypeDef",
+    {
+        "botId": str,
+        "botVersion": str,
+        "localeId": str,
+        "botLocaleStatus": BotLocaleStatusType,
+        "lastBuildSubmittedDateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 BuiltInIntentSortByTypeDef = TypedDict(
     "BuiltInIntentSortByTypeDef",
     {
         "attribute": Literal["IntentSignature"],
         "order": SortOrderType,
     },
 )
@@ -824,14 +940,67 @@
 ConditionTypeDef = TypedDict(
     "ConditionTypeDef",
     {
         "expressionString": str,
     },
 )
 
+ConversationLevelIntentClassificationResultItemTypeDef = TypedDict(
+    "ConversationLevelIntentClassificationResultItemTypeDef",
+    {
+        "intentName": str,
+        "matchResult": TestResultMatchStatusType,
+    },
+)
+
+_RequiredConversationLevelResultDetailTypeDef = TypedDict(
+    "_RequiredConversationLevelResultDetailTypeDef",
+    {
+        "endToEndResult": TestResultMatchStatusType,
+    },
+)
+_OptionalConversationLevelResultDetailTypeDef = TypedDict(
+    "_OptionalConversationLevelResultDetailTypeDef",
+    {
+        "speechTranscriptionResult": TestResultMatchStatusType,
+    },
+    total=False,
+)
+
+class ConversationLevelResultDetailTypeDef(
+    _RequiredConversationLevelResultDetailTypeDef, _OptionalConversationLevelResultDetailTypeDef
+):
+    pass
+
+ConversationLevelSlotResolutionResultItemTypeDef = TypedDict(
+    "ConversationLevelSlotResolutionResultItemTypeDef",
+    {
+        "intentName": str,
+        "slotName": str,
+        "matchResult": TestResultMatchStatusType,
+    },
+)
+
+ConversationLevelTestResultsFilterByTypeDef = TypedDict(
+    "ConversationLevelTestResultsFilterByTypeDef",
+    {
+        "endToEndResult": TestResultMatchStatusType,
+    },
+    total=False,
+)
+
+ConversationLogsDataSourceFilterByTypeDef = TypedDict(
+    "ConversationLogsDataSourceFilterByTypeDef",
+    {
+        "startTime": datetime,
+        "endTime": datetime,
+        "inputMode": ConversationLogsInputModeFilterType,
+    },
+)
+
 SentimentAnalysisSettingsTypeDef = TypedDict(
     "SentimentAnalysisSettingsTypeDef",
     {
         "detectSentiment": bool,
     },
 )
 
@@ -860,21 +1029,19 @@
     {
         "queryFilterStringEnabled": bool,
         "queryFilterString": str,
     },
     total=False,
 )
 
-
 class KendraConfigurationTypeDef(
     _RequiredKendraConfigurationTypeDef, _OptionalKendraConfigurationTypeDef
 ):
     pass
 
-
 OutputContextTypeDef = TypedDict(
     "OutputContextTypeDef",
     {
         "name": str,
         "timeToLiveInSeconds": int,
         "turnsToLive": int,
     },
@@ -891,23 +1058,41 @@
     "CreateResourcePolicyRequestRequestTypeDef",
     {
         "resourceArn": str,
         "policy": str,
     },
 )
 
+CreateResourcePolicyResponseTypeDef = TypedDict(
+    "CreateResourcePolicyResponseTypeDef",
+    {
+        "resourceArn": str,
+        "revisionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 PrincipalTypeDef = TypedDict(
     "PrincipalTypeDef",
     {
         "service": str,
         "arn": str,
     },
     total=False,
 )
 
+CreateResourcePolicyStatementResponseTypeDef = TypedDict(
+    "CreateResourcePolicyStatementResponseTypeDef",
+    {
+        "resourceArn": str,
+        "revisionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 MultipleValuesSettingTypeDef = TypedDict(
     "MultipleValuesSettingTypeDef",
     {
         "allowMultipleValues": bool,
     },
     total=False,
 )
@@ -915,14 +1100,23 @@
 ObfuscationSettingTypeDef = TypedDict(
     "ObfuscationSettingTypeDef",
     {
         "obfuscationSettingType": ObfuscationSettingTypeType,
     },
 )
 
+CreateUploadUrlResponseTypeDef = TypedDict(
+    "CreateUploadUrlResponseTypeDef",
+    {
+        "importId": str,
+        "uploadUrl": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CustomPayloadTypeDef = TypedDict(
     "CustomPayloadTypeDef",
     {
         "value": str,
     },
 )
 
@@ -963,50 +1157,76 @@
     "_OptionalDeleteBotAliasRequestRequestTypeDef",
     {
         "skipResourceInUseCheck": bool,
     },
     total=False,
 )
 
-
 class DeleteBotAliasRequestRequestTypeDef(
     _RequiredDeleteBotAliasRequestRequestTypeDef, _OptionalDeleteBotAliasRequestRequestTypeDef
 ):
     pass
 
+DeleteBotAliasResponseTypeDef = TypedDict(
+    "DeleteBotAliasResponseTypeDef",
+    {
+        "botAliasId": str,
+        "botId": str,
+        "botAliasStatus": BotAliasStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 DeleteBotLocaleRequestRequestTypeDef = TypedDict(
     "DeleteBotLocaleRequestRequestTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
     },
 )
 
+DeleteBotLocaleResponseTypeDef = TypedDict(
+    "DeleteBotLocaleResponseTypeDef",
+    {
+        "botId": str,
+        "botVersion": str,
+        "localeId": str,
+        "botLocaleStatus": BotLocaleStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteBotRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteBotRequestRequestTypeDef",
     {
         "botId": str,
     },
 )
 _OptionalDeleteBotRequestRequestTypeDef = TypedDict(
     "_OptionalDeleteBotRequestRequestTypeDef",
     {
         "skipResourceInUseCheck": bool,
     },
     total=False,
 )
 
-
 class DeleteBotRequestRequestTypeDef(
     _RequiredDeleteBotRequestRequestTypeDef, _OptionalDeleteBotRequestRequestTypeDef
 ):
     pass
 
+DeleteBotResponseTypeDef = TypedDict(
+    "DeleteBotResponseTypeDef",
+    {
+        "botId": str,
+        "botStatus": BotStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredDeleteBotVersionRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteBotVersionRequestRequestTypeDef",
     {
         "botId": str,
         "botVersion": str,
     },
@@ -1015,44 +1235,81 @@
     "_OptionalDeleteBotVersionRequestRequestTypeDef",
     {
         "skipResourceInUseCheck": bool,
     },
     total=False,
 )
 
-
 class DeleteBotVersionRequestRequestTypeDef(
     _RequiredDeleteBotVersionRequestRequestTypeDef, _OptionalDeleteBotVersionRequestRequestTypeDef
 ):
     pass
 
+DeleteBotVersionResponseTypeDef = TypedDict(
+    "DeleteBotVersionResponseTypeDef",
+    {
+        "botId": str,
+        "botVersion": str,
+        "botStatus": BotStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 DeleteCustomVocabularyRequestRequestTypeDef = TypedDict(
     "DeleteCustomVocabularyRequestRequestTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
     },
 )
 
+DeleteCustomVocabularyResponseTypeDef = TypedDict(
+    "DeleteCustomVocabularyResponseTypeDef",
+    {
+        "botId": str,
+        "botVersion": str,
+        "localeId": str,
+        "customVocabularyStatus": CustomVocabularyStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteExportRequestRequestTypeDef = TypedDict(
     "DeleteExportRequestRequestTypeDef",
     {
         "exportId": str,
     },
 )
 
+DeleteExportResponseTypeDef = TypedDict(
+    "DeleteExportResponseTypeDef",
+    {
+        "exportId": str,
+        "exportStatus": ExportStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteImportRequestRequestTypeDef = TypedDict(
     "DeleteImportRequestRequestTypeDef",
     {
         "importId": str,
     },
 )
 
+DeleteImportResponseTypeDef = TypedDict(
+    "DeleteImportResponseTypeDef",
+    {
+        "importId": str,
+        "importStatus": ImportStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteIntentRequestRequestTypeDef = TypedDict(
     "DeleteIntentRequestRequestTypeDef",
     {
         "intentId": str,
         "botId": str,
         "botVersion": str,
         "localeId": str,
@@ -1069,21 +1326,28 @@
     "_OptionalDeleteResourcePolicyRequestRequestTypeDef",
     {
         "expectedRevisionId": str,
     },
     total=False,
 )
 
-
 class DeleteResourcePolicyRequestRequestTypeDef(
     _RequiredDeleteResourcePolicyRequestRequestTypeDef,
     _OptionalDeleteResourcePolicyRequestRequestTypeDef,
 ):
     pass
 
+DeleteResourcePolicyResponseTypeDef = TypedDict(
+    "DeleteResourcePolicyResponseTypeDef",
+    {
+        "resourceArn": str,
+        "revisionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredDeleteResourcePolicyStatementRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteResourcePolicyStatementRequestRequestTypeDef",
     {
         "resourceArn": str,
         "statementId": str,
     },
@@ -1092,21 +1356,28 @@
     "_OptionalDeleteResourcePolicyStatementRequestRequestTypeDef",
     {
         "expectedRevisionId": str,
     },
     total=False,
 )
 
-
 class DeleteResourcePolicyStatementRequestRequestTypeDef(
     _RequiredDeleteResourcePolicyStatementRequestRequestTypeDef,
     _OptionalDeleteResourcePolicyStatementRequestRequestTypeDef,
 ):
     pass
 
+DeleteResourcePolicyStatementResponseTypeDef = TypedDict(
+    "DeleteResourcePolicyStatementResponseTypeDef",
+    {
+        "resourceArn": str,
+        "revisionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 DeleteSlotRequestRequestTypeDef = TypedDict(
     "DeleteSlotRequestRequestTypeDef",
     {
         "slotId": str,
         "botId": str,
         "botVersion": str,
@@ -1128,20 +1399,25 @@
     "_OptionalDeleteSlotTypeRequestRequestTypeDef",
     {
         "skipResourceInUseCheck": bool,
     },
     total=False,
 )
 
-
 class DeleteSlotTypeRequestRequestTypeDef(
     _RequiredDeleteSlotTypeRequestRequestTypeDef, _OptionalDeleteSlotTypeRequestRequestTypeDef
 ):
     pass
 
+DeleteTestSetRequestRequestTypeDef = TypedDict(
+    "DeleteTestSetRequestRequestTypeDef",
+    {
+        "testSetId": str,
+    },
+)
 
 _RequiredDeleteUtterancesRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteUtterancesRequestRequestTypeDef",
     {
         "botId": str,
     },
 )
@@ -1150,21 +1426,19 @@
     {
         "localeId": str,
         "sessionId": str,
     },
     total=False,
 )
 
-
 class DeleteUtterancesRequestRequestTypeDef(
     _RequiredDeleteUtterancesRequestRequestTypeDef, _OptionalDeleteUtterancesRequestRequestTypeDef
 ):
     pass
 
-
 WaiterConfigTypeDef = TypedDict(
     "WaiterConfigTypeDef",
     {
         "Delay": int,
         "MaxAttempts": int,
     },
     total=False,
@@ -1235,14 +1509,27 @@
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
     },
 )
 
+DescribeCustomVocabularyMetadataResponseTypeDef = TypedDict(
+    "DescribeCustomVocabularyMetadataResponseTypeDef",
+    {
+        "botId": str,
+        "botVersion": str,
+        "localeId": str,
+        "customVocabularyStatus": CustomVocabularyStatusType,
+        "creationDateTime": datetime,
+        "lastUpdatedDateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeExportRequestRequestTypeDef = TypedDict(
     "DescribeExportRequestRequestTypeDef",
     {
         "exportId": str,
     },
 )
 
@@ -1274,14 +1561,24 @@
 DescribeResourcePolicyRequestRequestTypeDef = TypedDict(
     "DescribeResourcePolicyRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
+DescribeResourcePolicyResponseTypeDef = TypedDict(
+    "DescribeResourcePolicyResponseTypeDef",
+    {
+        "resourceArn": str,
+        "policy": str,
+        "revisionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeSlotRequestRequestTypeDef = TypedDict(
     "DescribeSlotRequestRequestTypeDef",
     {
         "slotId": str,
         "botId": str,
         "botVersion": str,
         "localeId": str,
@@ -1295,14 +1592,62 @@
         "slotTypeId": str,
         "botId": str,
         "botVersion": str,
         "localeId": str,
     },
 )
 
+DescribeTestExecutionRequestRequestTypeDef = TypedDict(
+    "DescribeTestExecutionRequestRequestTypeDef",
+    {
+        "testExecutionId": str,
+    },
+)
+
+DescribeTestSetDiscrepancyReportRequestRequestTypeDef = TypedDict(
+    "DescribeTestSetDiscrepancyReportRequestRequestTypeDef",
+    {
+        "testSetDiscrepancyReportId": str,
+    },
+)
+
+DescribeTestSetGenerationRequestRequestTypeDef = TypedDict(
+    "DescribeTestSetGenerationRequestRequestTypeDef",
+    {
+        "testSetGenerationId": str,
+    },
+)
+
+_RequiredTestSetStorageLocationTypeDef = TypedDict(
+    "_RequiredTestSetStorageLocationTypeDef",
+    {
+        "s3BucketName": str,
+        "s3Path": str,
+    },
+)
+_OptionalTestSetStorageLocationTypeDef = TypedDict(
+    "_OptionalTestSetStorageLocationTypeDef",
+    {
+        "kmsKeyArn": str,
+    },
+    total=False,
+)
+
+class TestSetStorageLocationTypeDef(
+    _RequiredTestSetStorageLocationTypeDef, _OptionalTestSetStorageLocationTypeDef
+):
+    pass
+
+DescribeTestSetRequestRequestTypeDef = TypedDict(
+    "DescribeTestSetRequestRequestTypeDef",
+    {
+        "testSetId": str,
+    },
+)
+
 _RequiredDialogActionTypeDef = TypedDict(
     "_RequiredDialogActionTypeDef",
     {
         "type": DialogActionTypeType,
     },
 )
 _OptionalDialogActionTypeDef = TypedDict(
@@ -1310,19 +1655,17 @@
     {
         "slotToElicit": str,
         "suppressNextMessage": bool,
     },
     total=False,
 )
 
-
 class DialogActionTypeDef(_RequiredDialogActionTypeDef, _OptionalDialogActionTypeDef):
     pass
 
-
 IntentOverrideTypeDef = TypedDict(
     "IntentOverrideTypeDef",
     {
         "name": str,
         "slots": Mapping[str, "SlotValueOverrideTypeDef"],
     },
     total=False,
@@ -1338,39 +1681,67 @@
     "_OptionalElicitationCodeHookInvocationSettingTypeDef",
     {
         "invocationLabel": str,
     },
     total=False,
 )
 
-
 class ElicitationCodeHookInvocationSettingTypeDef(
     _RequiredElicitationCodeHookInvocationSettingTypeDef,
     _OptionalElicitationCodeHookInvocationSettingTypeDef,
 ):
     pass
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 ExportFilterTypeDef = TypedDict(
     "ExportFilterTypeDef",
     {
         "name": Literal["ExportResourceType"],
         "values": Sequence[str],
         "operator": ExportFilterOperatorType,
     },
 )
 
+TestSetExportSpecificationTypeDef = TypedDict(
+    "TestSetExportSpecificationTypeDef",
+    {
+        "testSetId": str,
+    },
+)
+
 ExportSortByTypeDef = TypedDict(
     "ExportSortByTypeDef",
     {
         "attribute": Literal["LastUpdatedDateTime"],
         "order": SortOrderType,
     },
 )
 
+GetTestExecutionArtifactsUrlRequestRequestTypeDef = TypedDict(
+    "GetTestExecutionArtifactsUrlRequestRequestTypeDef",
+    {
+        "testExecutionId": str,
+    },
+)
+
+GetTestExecutionArtifactsUrlResponseTypeDef = TypedDict(
+    "GetTestExecutionArtifactsUrlResponseTypeDef",
+    {
+        "testExecutionId": str,
+        "downloadArtifactsUrl": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGrammarSlotTypeSourceTypeDef = TypedDict(
     "_RequiredGrammarSlotTypeSourceTypeDef",
     {
         "s3BucketName": str,
         "s3ObjectKey": str,
     },
 )
@@ -1378,21 +1749,19 @@
     "_OptionalGrammarSlotTypeSourceTypeDef",
     {
         "kmsKeyArn": str,
     },
     total=False,
 )
 
-
 class GrammarSlotTypeSourceTypeDef(
     _RequiredGrammarSlotTypeSourceTypeDef, _OptionalGrammarSlotTypeSourceTypeDef
 ):
     pass
 
-
 ImportFilterTypeDef = TypedDict(
     "ImportFilterTypeDef",
     {
         "name": Literal["ImportResourceType"],
         "values": Sequence[str],
         "operator": ImportFilterOperatorType,
     },
@@ -1417,14 +1786,43 @@
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
         "importedResourceType": ImportResourceTypeType,
     },
     total=False,
 )
 
+RuntimeHintsTypeDef = TypedDict(
+    "RuntimeHintsTypeDef",
+    {
+        "slotHints": Dict[str, Dict[str, "RuntimeHintDetailsTypeDef"]],
+    },
+    total=False,
+)
+
+_RequiredIntentClassificationTestResultItemCountsTypeDef = TypedDict(
+    "_RequiredIntentClassificationTestResultItemCountsTypeDef",
+    {
+        "totalResultCount": int,
+        "intentMatchResultCounts": Dict[TestResultMatchStatusType, int],
+    },
+)
+_OptionalIntentClassificationTestResultItemCountsTypeDef = TypedDict(
+    "_OptionalIntentClassificationTestResultItemCountsTypeDef",
+    {
+        "speechTranscriptionResultCounts": Dict[TestResultMatchStatusType, int],
+    },
+    total=False,
+)
+
+class IntentClassificationTestResultItemCountsTypeDef(
+    _RequiredIntentClassificationTestResultItemCountsTypeDef,
+    _OptionalIntentClassificationTestResultItemCountsTypeDef,
+):
+    pass
+
 IntentFilterTypeDef = TypedDict(
     "IntentFilterTypeDef",
     {
         "name": Literal["IntentName"],
         "values": Sequence[str],
         "operator": IntentFilterOperatorType,
     },
@@ -1449,21 +1847,19 @@
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
-
 class ListBotAliasesRequestRequestTypeDef(
     _RequiredListBotAliasesRequestRequestTypeDef, _OptionalListBotAliasesRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredListBotRecommendationsRequestRequestTypeDef = TypedDict(
     "_RequiredListBotRecommendationsRequestRequestTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
     },
@@ -1473,22 +1869,20 @@
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
-
 class ListBotRecommendationsRequestRequestTypeDef(
     _RequiredListBotRecommendationsRequestRequestTypeDef,
     _OptionalListBotRecommendationsRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredListCustomVocabularyItemsRequestRequestTypeDef = TypedDict(
     "_RequiredListCustomVocabularyItemsRequestRequestTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
     },
@@ -1498,22 +1892,20 @@
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
-
 class ListCustomVocabularyItemsRequestRequestTypeDef(
     _RequiredListCustomVocabularyItemsRequestRequestTypeDef,
     _OptionalListCustomVocabularyItemsRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredListRecommendedIntentsRequestRequestTypeDef = TypedDict(
     "_RequiredListRecommendedIntentsRequestRequestTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
         "botRecommendationId": str,
@@ -1524,22 +1916,20 @@
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
-
 class ListRecommendedIntentsRequestRequestTypeDef(
     _RequiredListRecommendedIntentsRequestRequestTypeDef,
     _OptionalListRecommendedIntentsRequestRequestTypeDef,
 ):
     pass
 
-
 RecommendedIntentSummaryTypeDef = TypedDict(
     "RecommendedIntentSummaryTypeDef",
     {
         "intentId": str,
         "intentName": str,
         "sampleUtterancesCount": int,
     },
@@ -1596,28 +1986,94 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "resourceARN": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+TestExecutionSortByTypeDef = TypedDict(
+    "TestExecutionSortByTypeDef",
+    {
+        "attribute": TestExecutionSortAttributeType,
+        "order": SortOrderType,
+    },
+)
+
+_RequiredListTestSetRecordsRequestRequestTypeDef = TypedDict(
+    "_RequiredListTestSetRecordsRequestRequestTypeDef",
+    {
+        "testSetId": str,
+    },
+)
+_OptionalListTestSetRecordsRequestRequestTypeDef = TypedDict(
+    "_OptionalListTestSetRecordsRequestRequestTypeDef",
+    {
+        "maxResults": int,
+        "nextToken": str,
+    },
+    total=False,
+)
+
+class ListTestSetRecordsRequestRequestTypeDef(
+    _RequiredListTestSetRecordsRequestRequestTypeDef,
+    _OptionalListTestSetRecordsRequestRequestTypeDef,
+):
+    pass
+
+TestSetSortByTypeDef = TypedDict(
+    "TestSetSortByTypeDef",
+    {
+        "attribute": TestSetSortAttributeType,
+        "order": SortOrderType,
+    },
+)
+
 PlainTextMessageTypeDef = TypedDict(
     "PlainTextMessageTypeDef",
     {
         "value": str,
     },
 )
 
 SSMLMessageTypeDef = TypedDict(
     "SSMLMessageTypeDef",
     {
         "value": str,
     },
 )
 
+_RequiredOverallTestResultItemTypeDef = TypedDict(
+    "_RequiredOverallTestResultItemTypeDef",
+    {
+        "multiTurnConversation": bool,
+        "totalResultCount": int,
+        "endToEndResultCounts": Dict[TestResultMatchStatusType, int],
+    },
+)
+_OptionalOverallTestResultItemTypeDef = TypedDict(
+    "_OptionalOverallTestResultItemTypeDef",
+    {
+        "speechTranscriptionResultCounts": Dict[TestResultMatchStatusType, int],
+    },
+    total=False,
+)
+
+class OverallTestResultItemTypeDef(
+    _RequiredOverallTestResultItemTypeDef, _OptionalOverallTestResultItemTypeDef
+):
+    pass
+
 PathFormatTypeDef = TypedDict(
     "PathFormatTypeDef",
     {
         "objectPrefixes": List[str],
     },
     total=False,
 )
@@ -1633,28 +2089,67 @@
     "RelativeAggregationDurationTypeDef",
     {
         "timeDimension": TimeDimensionType,
         "timeValue": int,
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
+RuntimeHintValueTypeDef = TypedDict(
+    "RuntimeHintValueTypeDef",
+    {
+        "phrase": str,
+    },
+)
+
 SampleValueTypeDef = TypedDict(
     "SampleValueTypeDef",
     {
         "value": str,
     },
 )
 
 SlotDefaultValueTypeDef = TypedDict(
     "SlotDefaultValueTypeDef",
     {
         "defaultValue": str,
     },
 )
 
+_RequiredSlotResolutionTestResultItemCountsTypeDef = TypedDict(
+    "_RequiredSlotResolutionTestResultItemCountsTypeDef",
+    {
+        "totalResultCount": int,
+        "slotMatchResultCounts": Dict[TestResultMatchStatusType, int],
+    },
+)
+_OptionalSlotResolutionTestResultItemCountsTypeDef = TypedDict(
+    "_OptionalSlotResolutionTestResultItemCountsTypeDef",
+    {
+        "speechTranscriptionResultCounts": Dict[TestResultMatchStatusType, int],
+    },
+    total=False,
+)
+
+class SlotResolutionTestResultItemCountsTypeDef(
+    _RequiredSlotResolutionTestResultItemCountsTypeDef,
+    _OptionalSlotResolutionTestResultItemCountsTypeDef,
+):
+    pass
+
 SlotValueTypeDef = TypedDict(
     "SlotValueTypeDef",
     {
         "interpretedValue": str,
     },
     total=False,
 )
@@ -1672,22 +2167,68 @@
         "botId": str,
         "botVersion": str,
         "localeId": str,
         "botRecommendationId": str,
     },
 )
 
+StopBotRecommendationResponseTypeDef = TypedDict(
+    "StopBotRecommendationResponseTypeDef",
+    {
+        "botId": str,
+        "botVersion": str,
+        "localeId": str,
+        "botRecommendationStatus": BotRecommendationStatusType,
+        "botRecommendationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceARN": str,
         "tags": Mapping[str, str],
     },
 )
 
+TestSetIntentDiscrepancyItemTypeDef = TypedDict(
+    "TestSetIntentDiscrepancyItemTypeDef",
+    {
+        "intentName": str,
+        "errorMessage": str,
+    },
+)
+
+TestSetSlotDiscrepancyItemTypeDef = TypedDict(
+    "TestSetSlotDiscrepancyItemTypeDef",
+    {
+        "intentName": str,
+        "slotName": str,
+        "errorMessage": str,
+    },
+)
+
+TestSetDiscrepancyReportBotAliasTargetTypeDef = TypedDict(
+    "TestSetDiscrepancyReportBotAliasTargetTypeDef",
+    {
+        "botId": str,
+        "botAliasId": str,
+        "localeId": str,
+    },
+)
+
+TestSetImportInputLocationTypeDef = TypedDict(
+    "TestSetImportInputLocationTypeDef",
+    {
+        "s3BucketName": str,
+        "s3Path": str,
+    },
+)
+
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceARN": str,
         "tagKeys": Sequence[str],
     },
 )
@@ -1702,21 +2243,19 @@
     "_OptionalUpdateExportRequestRequestTypeDef",
     {
         "filePassword": str,
     },
     total=False,
 )
 
-
 class UpdateExportRequestRequestTypeDef(
     _RequiredUpdateExportRequestRequestTypeDef, _OptionalUpdateExportRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredUpdateResourcePolicyRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateResourcePolicyRequestRequestTypeDef",
     {
         "resourceArn": str,
         "policy": str,
     },
 )
@@ -1724,343 +2263,237 @@
     "_OptionalUpdateResourcePolicyRequestRequestTypeDef",
     {
         "expectedRevisionId": str,
     },
     total=False,
 )
 
-
 class UpdateResourcePolicyRequestRequestTypeDef(
     _RequiredUpdateResourcePolicyRequestRequestTypeDef,
     _OptionalUpdateResourcePolicyRequestRequestTypeDef,
 ):
     pass
 
+UpdateResourcePolicyResponseTypeDef = TypedDict(
+    "UpdateResourcePolicyResponseTypeDef",
+    {
+        "resourceArn": str,
+        "revisionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
-_RequiredSearchAssociatedTranscriptsRequestRequestTypeDef = TypedDict(
-    "_RequiredSearchAssociatedTranscriptsRequestRequestTypeDef",
+_RequiredUpdateTestSetRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateTestSetRequestRequestTypeDef",
     {
-        "botId": str,
-        "botVersion": str,
-        "localeId": str,
-        "botRecommendationId": str,
-        "filters": Sequence[AssociatedTranscriptFilterTypeDef],
+        "testSetId": str,
+        "testSetName": str,
     },
 )
-_OptionalSearchAssociatedTranscriptsRequestRequestTypeDef = TypedDict(
-    "_OptionalSearchAssociatedTranscriptsRequestRequestTypeDef",
+_OptionalUpdateTestSetRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateTestSetRequestRequestTypeDef",
     {
-        "searchOrder": SearchOrderType,
-        "maxResults": int,
-        "nextIndex": int,
+        "description": str,
     },
     total=False,
 )
 
-
-class SearchAssociatedTranscriptsRequestRequestTypeDef(
-    _RequiredSearchAssociatedTranscriptsRequestRequestTypeDef,
-    _OptionalSearchAssociatedTranscriptsRequestRequestTypeDef,
+class UpdateTestSetRequestRequestTypeDef(
+    _RequiredUpdateTestSetRequestRequestTypeDef, _OptionalUpdateTestSetRequestRequestTypeDef
 ):
     pass
 
-
-_RequiredAudioAndDTMFInputSpecificationTypeDef = TypedDict(
-    "_RequiredAudioAndDTMFInputSpecificationTypeDef",
+_RequiredUserTurnIntentOutputTypeDef = TypedDict(
+    "_RequiredUserTurnIntentOutputTypeDef",
     {
-        "startTimeoutMs": int,
+        "name": str,
     },
 )
-_OptionalAudioAndDTMFInputSpecificationTypeDef = TypedDict(
-    "_OptionalAudioAndDTMFInputSpecificationTypeDef",
+_OptionalUserTurnIntentOutputTypeDef = TypedDict(
+    "_OptionalUserTurnIntentOutputTypeDef",
     {
-        "audioSpecification": AudioSpecificationTypeDef,
-        "dtmfSpecification": DTMFSpecificationTypeDef,
+        "slots": Dict[str, "UserTurnSlotOutputTypeDef"],
     },
     total=False,
 )
 
-
-class AudioAndDTMFInputSpecificationTypeDef(
-    _RequiredAudioAndDTMFInputSpecificationTypeDef, _OptionalAudioAndDTMFInputSpecificationTypeDef
+class UserTurnIntentOutputTypeDef(
+    _RequiredUserTurnIntentOutputTypeDef, _OptionalUserTurnIntentOutputTypeDef
 ):
     pass
 
-
-AudioLogDestinationTypeDef = TypedDict(
-    "AudioLogDestinationTypeDef",
+UserTurnSlotOutputTypeDef = TypedDict(
+    "UserTurnSlotOutputTypeDef",
     {
-        "s3Bucket": S3BucketLogDestinationTypeDef,
+        "value": str,
+        "values": List[Dict[str, Any]],
+        "subSlots": Dict[str, Dict[str, Any]],
     },
+    total=False,
 )
 
-BatchCreateCustomVocabularyItemRequestRequestTypeDef = TypedDict(
-    "BatchCreateCustomVocabularyItemRequestRequestTypeDef",
+UtteranceAudioInputSpecificationTypeDef = TypedDict(
+    "UtteranceAudioInputSpecificationTypeDef",
     {
-        "botId": str,
-        "botVersion": str,
-        "localeId": str,
-        "customVocabularyItemList": Sequence[NewCustomVocabularyItemTypeDef],
+        "audioFileS3Location": str,
     },
 )
 
-BatchUpdateCustomVocabularyItemRequestRequestTypeDef = TypedDict(
-    "BatchUpdateCustomVocabularyItemRequestRequestTypeDef",
+_RequiredAgentTurnResultTypeDef = TypedDict(
+    "_RequiredAgentTurnResultTypeDef",
     {
-        "botId": str,
-        "botVersion": str,
-        "localeId": str,
-        "customVocabularyItemList": Sequence[CustomVocabularyItemTypeDef],
+        "expectedAgentPrompt": str,
     },
 )
-
-BatchCreateCustomVocabularyItemResponseTypeDef = TypedDict(
-    "BatchCreateCustomVocabularyItemResponseTypeDef",
+_OptionalAgentTurnResultTypeDef = TypedDict(
+    "_OptionalAgentTurnResultTypeDef",
     {
-        "botId": str,
-        "botVersion": str,
-        "localeId": str,
-        "errors": List[FailedCustomVocabularyItemTypeDef],
-        "resources": List[CustomVocabularyItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "actualAgentPrompt": str,
+        "errorDetails": ExecutionErrorDetailsTypeDef,
+        "actualElicitedSlot": str,
+        "actualIntent": str,
     },
+    total=False,
 )
 
-BatchDeleteCustomVocabularyItemResponseTypeDef = TypedDict(
-    "BatchDeleteCustomVocabularyItemResponseTypeDef",
+class AgentTurnResultTypeDef(_RequiredAgentTurnResultTypeDef, _OptionalAgentTurnResultTypeDef):
+    pass
+
+_RequiredSearchAssociatedTranscriptsRequestRequestTypeDef = TypedDict(
+    "_RequiredSearchAssociatedTranscriptsRequestRequestTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
-        "errors": List[FailedCustomVocabularyItemTypeDef],
-        "resources": List[CustomVocabularyItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "botRecommendationId": str,
+        "filters": Sequence[AssociatedTranscriptFilterTypeDef],
     },
 )
-
-BatchUpdateCustomVocabularyItemResponseTypeDef = TypedDict(
-    "BatchUpdateCustomVocabularyItemResponseTypeDef",
+_OptionalSearchAssociatedTranscriptsRequestRequestTypeDef = TypedDict(
+    "_OptionalSearchAssociatedTranscriptsRequestRequestTypeDef",
     {
-        "botId": str,
-        "botVersion": str,
-        "localeId": str,
-        "errors": List[FailedCustomVocabularyItemTypeDef],
-        "resources": List[CustomVocabularyItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "searchOrder": SearchOrderType,
+        "maxResults": int,
+        "nextIndex": int,
     },
+    total=False,
 )
 
-BuildBotLocaleResponseTypeDef = TypedDict(
-    "BuildBotLocaleResponseTypeDef",
+class SearchAssociatedTranscriptsRequestRequestTypeDef(
+    _RequiredSearchAssociatedTranscriptsRequestRequestTypeDef,
+    _OptionalSearchAssociatedTranscriptsRequestRequestTypeDef,
+):
+    pass
+
+SearchAssociatedTranscriptsResponseTypeDef = TypedDict(
+    "SearchAssociatedTranscriptsResponseTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
-        "botLocaleStatus": BotLocaleStatusType,
-        "lastBuildSubmittedDateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateResourcePolicyResponseTypeDef = TypedDict(
-    "CreateResourcePolicyResponseTypeDef",
-    {
-        "resourceArn": str,
-        "revisionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateResourcePolicyStatementResponseTypeDef = TypedDict(
-    "CreateResourcePolicyStatementResponseTypeDef",
-    {
-        "resourceArn": str,
-        "revisionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateUploadUrlResponseTypeDef = TypedDict(
-    "CreateUploadUrlResponseTypeDef",
-    {
-        "importId": str,
-        "uploadUrl": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "botRecommendationId": str,
+        "nextIndex": int,
+        "associatedTranscripts": List[AssociatedTranscriptTypeDef],
+        "totalResults": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteBotAliasResponseTypeDef = TypedDict(
-    "DeleteBotAliasResponseTypeDef",
+_RequiredAudioAndDTMFInputSpecificationTypeDef = TypedDict(
+    "_RequiredAudioAndDTMFInputSpecificationTypeDef",
     {
-        "botAliasId": str,
-        "botId": str,
-        "botAliasStatus": BotAliasStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "startTimeoutMs": int,
     },
 )
-
-DeleteBotLocaleResponseTypeDef = TypedDict(
-    "DeleteBotLocaleResponseTypeDef",
+_OptionalAudioAndDTMFInputSpecificationTypeDef = TypedDict(
+    "_OptionalAudioAndDTMFInputSpecificationTypeDef",
     {
-        "botId": str,
-        "botVersion": str,
-        "localeId": str,
-        "botLocaleStatus": BotLocaleStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "audioSpecification": AudioSpecificationTypeDef,
+        "dtmfSpecification": DTMFSpecificationTypeDef,
     },
+    total=False,
 )
 
-DeleteBotResponseTypeDef = TypedDict(
-    "DeleteBotResponseTypeDef",
-    {
-        "botId": str,
-        "botStatus": BotStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class AudioAndDTMFInputSpecificationTypeDef(
+    _RequiredAudioAndDTMFInputSpecificationTypeDef, _OptionalAudioAndDTMFInputSpecificationTypeDef
+):
+    pass
 
-DeleteBotVersionResponseTypeDef = TypedDict(
-    "DeleteBotVersionResponseTypeDef",
+AudioLogDestinationTypeDef = TypedDict(
+    "AudioLogDestinationTypeDef",
     {
-        "botId": str,
-        "botVersion": str,
-        "botStatus": BotStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "s3Bucket": S3BucketLogDestinationTypeDef,
     },
 )
 
-DeleteCustomVocabularyResponseTypeDef = TypedDict(
-    "DeleteCustomVocabularyResponseTypeDef",
+BatchCreateCustomVocabularyItemRequestRequestTypeDef = TypedDict(
+    "BatchCreateCustomVocabularyItemRequestRequestTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
-        "customVocabularyStatus": CustomVocabularyStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteExportResponseTypeDef = TypedDict(
-    "DeleteExportResponseTypeDef",
-    {
-        "exportId": str,
-        "exportStatus": ExportStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteImportResponseTypeDef = TypedDict(
-    "DeleteImportResponseTypeDef",
-    {
-        "importId": str,
-        "importStatus": ImportStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteResourcePolicyResponseTypeDef = TypedDict(
-    "DeleteResourcePolicyResponseTypeDef",
-    {
-        "resourceArn": str,
-        "revisionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteResourcePolicyStatementResponseTypeDef = TypedDict(
-    "DeleteResourcePolicyStatementResponseTypeDef",
-    {
-        "resourceArn": str,
-        "revisionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "customVocabularyItemList": Sequence[NewCustomVocabularyItemTypeDef],
     },
 )
 
-DescribeCustomVocabularyMetadataResponseTypeDef = TypedDict(
-    "DescribeCustomVocabularyMetadataResponseTypeDef",
+BatchUpdateCustomVocabularyItemRequestRequestTypeDef = TypedDict(
+    "BatchUpdateCustomVocabularyItemRequestRequestTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
-        "customVocabularyStatus": CustomVocabularyStatusType,
-        "creationDateTime": datetime,
-        "lastUpdatedDateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeResourcePolicyResponseTypeDef = TypedDict(
-    "DescribeResourcePolicyResponseTypeDef",
-    {
-        "resourceArn": str,
-        "policy": str,
-        "revisionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "customVocabularyItemList": Sequence[CustomVocabularyItemTypeDef],
     },
 )
 
 ListCustomVocabularyItemsResponseTypeDef = TypedDict(
     "ListCustomVocabularyItemsResponseTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
         "customVocabularyItems": List[CustomVocabularyItemTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SearchAssociatedTranscriptsResponseTypeDef = TypedDict(
-    "SearchAssociatedTranscriptsResponseTypeDef",
+BatchCreateCustomVocabularyItemResponseTypeDef = TypedDict(
+    "BatchCreateCustomVocabularyItemResponseTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
-        "botRecommendationId": str,
-        "nextIndex": int,
-        "associatedTranscripts": List[AssociatedTranscriptTypeDef],
-        "totalResults": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "errors": List[FailedCustomVocabularyItemTypeDef],
+        "resources": List[CustomVocabularyItemTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StopBotRecommendationResponseTypeDef = TypedDict(
-    "StopBotRecommendationResponseTypeDef",
+BatchDeleteCustomVocabularyItemResponseTypeDef = TypedDict(
+    "BatchDeleteCustomVocabularyItemResponseTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
-        "botRecommendationStatus": BotRecommendationStatusType,
-        "botRecommendationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "errors": List[FailedCustomVocabularyItemTypeDef],
+        "resources": List[CustomVocabularyItemTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateResourcePolicyResponseTypeDef = TypedDict(
-    "UpdateResourcePolicyResponseTypeDef",
+BatchUpdateCustomVocabularyItemResponseTypeDef = TypedDict(
+    "BatchUpdateCustomVocabularyItemResponseTypeDef",
     {
-        "resourceArn": str,
-        "revisionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "botId": str,
+        "botVersion": str,
+        "localeId": str,
+        "errors": List[FailedCustomVocabularyItemTypeDef],
+        "resources": List[CustomVocabularyItemTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDeleteCustomVocabularyItemRequestRequestTypeDef = TypedDict(
     "BatchDeleteCustomVocabularyItemRequestRequestTypeDef",
     {
         "botId": str,
@@ -2072,16 +2505,24 @@
 
 ListBotAliasesResponseTypeDef = TypedDict(
     "ListBotAliasesResponseTypeDef",
     {
         "botAliasSummaries": List[BotAliasSummaryTypeDef],
         "nextToken": str,
         "botId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+TestExecutionTargetTypeDef = TypedDict(
+    "TestExecutionTargetTypeDef",
+    {
+        "botAliasTarget": BotAliasTestExecutionTargetTypeDef,
     },
+    total=False,
 )
 
 _RequiredBotImportSpecificationTypeDef = TypedDict(
     "_RequiredBotImportSpecificationTypeDef",
     {
         "botName": str,
         "roleArn": str,
@@ -2094,21 +2535,19 @@
         "idleSessionTTLInSeconds": int,
         "botTags": Dict[str, str],
         "testBotAliasTags": Dict[str, str],
     },
     total=False,
 )
 
-
 class BotImportSpecificationTypeDef(
     _RequiredBotImportSpecificationTypeDef, _OptionalBotImportSpecificationTypeDef
 ):
     pass
 
-
 _RequiredBotLocaleImportSpecificationTypeDef = TypedDict(
     "_RequiredBotLocaleImportSpecificationTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
     },
@@ -2118,21 +2557,19 @@
     {
         "nluIntentConfidenceThreshold": float,
         "voiceSettings": VoiceSettingsTypeDef,
     },
     total=False,
 )
 
-
 class BotLocaleImportSpecificationTypeDef(
     _RequiredBotLocaleImportSpecificationTypeDef, _OptionalBotLocaleImportSpecificationTypeDef
 ):
     pass
 
-
 _RequiredCreateBotLocaleRequestRequestTypeDef = TypedDict(
     "_RequiredCreateBotLocaleRequestRequestTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
         "nluIntentConfidenceThreshold": float,
@@ -2143,34 +2580,32 @@
     {
         "description": str,
         "voiceSettings": VoiceSettingsTypeDef,
     },
     total=False,
 )
 
-
 class CreateBotLocaleRequestRequestTypeDef(
     _RequiredCreateBotLocaleRequestRequestTypeDef, _OptionalCreateBotLocaleRequestRequestTypeDef
 ):
     pass
 
-
 CreateBotLocaleResponseTypeDef = TypedDict(
     "CreateBotLocaleResponseTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeName": str,
         "localeId": str,
         "description": str,
         "nluIntentConfidenceThreshold": float,
         "voiceSettings": VoiceSettingsTypeDef,
         "botLocaleStatus": BotLocaleStatusType,
         "creationDateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeBotLocaleResponseTypeDef = TypedDict(
     "DescribeBotLocaleResponseTypeDef",
     {
         "botId": str,
@@ -2185,15 +2620,15 @@
         "botLocaleStatus": BotLocaleStatusType,
         "failureReasons": List[str],
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
         "lastBuildSubmittedDateTime": datetime,
         "botLocaleHistoryEvents": List[BotLocaleHistoryEventTypeDef],
         "recommendedActions": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateBotLocaleRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateBotLocaleRequestRequestTypeDef",
     {
         "botId": str,
@@ -2207,21 +2642,19 @@
     {
         "description": str,
         "voiceSettings": VoiceSettingsTypeDef,
     },
     total=False,
 )
 
-
 class UpdateBotLocaleRequestRequestTypeDef(
     _RequiredUpdateBotLocaleRequestRequestTypeDef, _OptionalUpdateBotLocaleRequestRequestTypeDef
 ):
     pass
 
-
 UpdateBotLocaleResponseTypeDef = TypedDict(
     "UpdateBotLocaleResponseTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
         "localeName": str,
@@ -2229,15 +2662,15 @@
         "nluIntentConfidenceThreshold": float,
         "voiceSettings": VoiceSettingsTypeDef,
         "botLocaleStatus": BotLocaleStatusType,
         "failureReasons": List[str],
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
         "recommendedActions": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredListBotLocalesRequestRequestTypeDef = TypedDict(
     "_RequiredListBotLocalesRequestRequestTypeDef",
     {
         "botId": str,
@@ -2251,29 +2684,27 @@
         "filters": Sequence[BotLocaleFilterTypeDef],
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
-
 class ListBotLocalesRequestRequestTypeDef(
     _RequiredListBotLocalesRequestRequestTypeDef, _OptionalListBotLocalesRequestRequestTypeDef
 ):
     pass
 
-
 ListBotLocalesResponseTypeDef = TypedDict(
     "ListBotLocalesResponseTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "nextToken": str,
         "botLocaleSummaries": List[BotLocaleSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateBotRequestRequestTypeDef = TypedDict(
     "_RequiredCreateBotRequestRequestTypeDef",
     {
         "botName": str,
@@ -2290,21 +2721,19 @@
         "testBotAliasTags": Mapping[str, str],
         "botType": BotTypeType,
         "botMembers": Sequence[BotMemberTypeDef],
     },
     total=False,
 )
 
-
 class CreateBotRequestRequestTypeDef(
     _RequiredCreateBotRequestRequestTypeDef, _OptionalCreateBotRequestRequestTypeDef
 ):
     pass
 
-
 CreateBotResponseTypeDef = TypedDict(
     "CreateBotResponseTypeDef",
     {
         "botId": str,
         "botName": str,
         "description": str,
         "roleArn": str,
@@ -2312,15 +2741,15 @@
         "idleSessionTTLInSeconds": int,
         "botStatus": BotStatusType,
         "creationDateTime": datetime,
         "botTags": Dict[str, str],
         "testBotAliasTags": Dict[str, str],
         "botType": BotTypeType,
         "botMembers": List[BotMemberTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeBotResponseTypeDef = TypedDict(
     "DescribeBotResponseTypeDef",
     {
         "botId": str,
@@ -2331,15 +2760,15 @@
         "idleSessionTTLInSeconds": int,
         "botStatus": BotStatusType,
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
         "botType": BotTypeType,
         "botMembers": List[BotMemberTypeDef],
         "failureReasons": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateBotRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateBotRequestRequestTypeDef",
     {
         "botId": str,
@@ -2355,36 +2784,34 @@
         "description": str,
         "botType": BotTypeType,
         "botMembers": Sequence[BotMemberTypeDef],
     },
     total=False,
 )
 
-
 class UpdateBotRequestRequestTypeDef(
     _RequiredUpdateBotRequestRequestTypeDef, _OptionalUpdateBotRequestRequestTypeDef
 ):
     pass
 
-
 UpdateBotResponseTypeDef = TypedDict(
     "UpdateBotResponseTypeDef",
     {
         "botId": str,
         "botName": str,
         "description": str,
         "roleArn": str,
         "dataPrivacy": DataPrivacyTypeDef,
         "idleSessionTTLInSeconds": int,
         "botStatus": BotStatusType,
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
         "botType": BotTypeType,
         "botMembers": List[BotMemberTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BotRecommendationResultStatisticsTypeDef = TypedDict(
     "BotRecommendationResultStatisticsTypeDef",
     {
         "intents": IntentStatisticsTypeDef,
@@ -2397,15 +2824,15 @@
     "ListBotRecommendationsResponseTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
         "botRecommendationSummaries": List[BotRecommendationSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListBotsRequestRequestTypeDef = TypedDict(
     "ListBotsRequestRequestTypeDef",
     {
         "sortBy": BotSortByTypeDef,
@@ -2417,15 +2844,15 @@
 )
 
 ListBotsResponseTypeDef = TypedDict(
     "ListBotsResponseTypeDef",
     {
         "botSummaries": List[BotSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateBotVersionRequestRequestTypeDef = TypedDict(
     "_RequiredCreateBotVersionRequestRequestTypeDef",
     {
         "botId": str,
@@ -2436,31 +2863,29 @@
     "_OptionalCreateBotVersionRequestRequestTypeDef",
     {
         "description": str,
     },
     total=False,
 )
 
-
 class CreateBotVersionRequestRequestTypeDef(
     _RequiredCreateBotVersionRequestRequestTypeDef, _OptionalCreateBotVersionRequestRequestTypeDef
 ):
     pass
 
-
 CreateBotVersionResponseTypeDef = TypedDict(
     "CreateBotVersionResponseTypeDef",
     {
         "botId": str,
         "description": str,
         "botVersion": str,
         "botVersionLocaleSpecification": Dict[str, BotVersionLocaleDetailsTypeDef],
         "botStatus": BotStatusType,
         "creationDateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredListBotVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredListBotVersionsRequestRequestTypeDef",
     {
         "botId": str,
@@ -2472,28 +2897,26 @@
         "sortBy": BotVersionSortByTypeDef,
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
-
 class ListBotVersionsRequestRequestTypeDef(
     _RequiredListBotVersionsRequestRequestTypeDef, _OptionalListBotVersionsRequestRequestTypeDef
 ):
     pass
 
-
 ListBotVersionsResponseTypeDef = TypedDict(
     "ListBotVersionsResponseTypeDef",
     {
         "botId": str,
         "botVersionSummaries": List[BotVersionSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredListBuiltInIntentsRequestRequestTypeDef = TypedDict(
     "_RequiredListBuiltInIntentsRequestRequestTypeDef",
     {
         "localeId": str,
@@ -2505,29 +2928,27 @@
         "sortBy": BuiltInIntentSortByTypeDef,
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
-
 class ListBuiltInIntentsRequestRequestTypeDef(
     _RequiredListBuiltInIntentsRequestRequestTypeDef,
     _OptionalListBuiltInIntentsRequestRequestTypeDef,
 ):
     pass
 
-
 ListBuiltInIntentsResponseTypeDef = TypedDict(
     "ListBuiltInIntentsResponseTypeDef",
     {
         "builtInIntentSummaries": List[BuiltInIntentSummaryTypeDef],
         "nextToken": str,
         "localeId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredListBuiltInSlotTypesRequestRequestTypeDef = TypedDict(
     "_RequiredListBuiltInSlotTypesRequestRequestTypeDef",
     {
         "localeId": str,
@@ -2539,29 +2960,27 @@
         "sortBy": BuiltInSlotTypeSortByTypeDef,
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
-
 class ListBuiltInSlotTypesRequestRequestTypeDef(
     _RequiredListBuiltInSlotTypesRequestRequestTypeDef,
     _OptionalListBuiltInSlotTypesRequestRequestTypeDef,
 ):
     pass
 
-
 ListBuiltInSlotTypesResponseTypeDef = TypedDict(
     "ListBuiltInSlotTypesResponseTypeDef",
     {
         "builtInSlotTypeSummaries": List[BuiltInSlotTypeSummaryTypeDef],
         "nextToken": str,
         "localeId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredImageResponseCardTypeDef = TypedDict(
     "_RequiredImageResponseCardTypeDef",
     {
         "title": str,
@@ -2573,21 +2992,19 @@
         "subtitle": str,
         "imageUrl": str,
         "buttons": Sequence[ButtonTypeDef],
     },
     total=False,
 )
 
-
 class ImageResponseCardTypeDef(
     _RequiredImageResponseCardTypeDef, _OptionalImageResponseCardTypeDef
 ):
     pass
 
-
 TextLogDestinationTypeDef = TypedDict(
     "TextLogDestinationTypeDef",
     {
         "cloudWatch": CloudWatchLogGroupLogDestinationTypeDef,
     },
 )
 
@@ -2602,14 +3019,65 @@
     "CompositeSlotTypeSettingTypeDef",
     {
         "subSlots": Sequence[SubSlotTypeCompositionTypeDef],
     },
     total=False,
 )
 
+_RequiredConversationLevelTestResultItemTypeDef = TypedDict(
+    "_RequiredConversationLevelTestResultItemTypeDef",
+    {
+        "conversationId": str,
+        "endToEndResult": TestResultMatchStatusType,
+        "intentClassificationResults": List[ConversationLevelIntentClassificationResultItemTypeDef],
+        "slotResolutionResults": List[ConversationLevelSlotResolutionResultItemTypeDef],
+    },
+)
+_OptionalConversationLevelTestResultItemTypeDef = TypedDict(
+    "_OptionalConversationLevelTestResultItemTypeDef",
+    {
+        "speechTranscriptionResult": TestResultMatchStatusType,
+    },
+    total=False,
+)
+
+class ConversationLevelTestResultItemTypeDef(
+    _RequiredConversationLevelTestResultItemTypeDef, _OptionalConversationLevelTestResultItemTypeDef
+):
+    pass
+
+_RequiredTestExecutionResultFilterByTypeDef = TypedDict(
+    "_RequiredTestExecutionResultFilterByTypeDef",
+    {
+        "resultTypeFilter": TestResultTypeFilterType,
+    },
+)
+_OptionalTestExecutionResultFilterByTypeDef = TypedDict(
+    "_OptionalTestExecutionResultFilterByTypeDef",
+    {
+        "conversationLevelTestResultsFilterBy": ConversationLevelTestResultsFilterByTypeDef,
+    },
+    total=False,
+)
+
+class TestExecutionResultFilterByTypeDef(
+    _RequiredTestExecutionResultFilterByTypeDef, _OptionalTestExecutionResultFilterByTypeDef
+):
+    pass
+
+ConversationLogsDataSourceTypeDef = TypedDict(
+    "ConversationLogsDataSourceTypeDef",
+    {
+        "botId": str,
+        "botAliasId": str,
+        "localeId": str,
+        "filter": ConversationLogsDataSourceFilterByTypeDef,
+    },
+)
+
 IntentSummaryTypeDef = TypedDict(
     "IntentSummaryTypeDef",
     {
         "intentId": str,
         "intentName": str,
         "description": str,
         "parentIntentSignature": str,
@@ -2635,32 +3103,20 @@
     {
         "condition": Mapping[str, Mapping[str, str]],
         "expectedRevisionId": str,
     },
     total=False,
 )
 
-
 class CreateResourcePolicyStatementRequestRequestTypeDef(
     _RequiredCreateResourcePolicyStatementRequestRequestTypeDef,
     _OptionalCreateResourcePolicyStatementRequestRequestTypeDef,
 ):
     pass
 
-
-ExportResourceSpecificationTypeDef = TypedDict(
-    "ExportResourceSpecificationTypeDef",
-    {
-        "botExportSpecification": BotExportSpecificationTypeDef,
-        "botLocaleExportSpecification": BotLocaleExportSpecificationTypeDef,
-        "customVocabularyExportSpecification": CustomVocabularyExportSpecificationTypeDef,
-    },
-    total=False,
-)
-
 LexTranscriptFilterTypeDef = TypedDict(
     "LexTranscriptFilterTypeDef",
     {
         "dateRangeFilter": DateRangeFilterTypeDef,
     },
     total=False,
 )
@@ -2676,22 +3132,20 @@
     "_OptionalDescribeBotAliasRequestBotAliasAvailableWaitTypeDef",
     {
         "WaiterConfig": WaiterConfigTypeDef,
     },
     total=False,
 )
 
-
 class DescribeBotAliasRequestBotAliasAvailableWaitTypeDef(
     _RequiredDescribeBotAliasRequestBotAliasAvailableWaitTypeDef,
     _OptionalDescribeBotAliasRequestBotAliasAvailableWaitTypeDef,
 ):
     pass
 
-
 _RequiredDescribeBotLocaleRequestBotLocaleBuiltWaitTypeDef = TypedDict(
     "_RequiredDescribeBotLocaleRequestBotLocaleBuiltWaitTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
     },
@@ -2700,22 +3154,20 @@
     "_OptionalDescribeBotLocaleRequestBotLocaleBuiltWaitTypeDef",
     {
         "WaiterConfig": WaiterConfigTypeDef,
     },
     total=False,
 )
 
-
 class DescribeBotLocaleRequestBotLocaleBuiltWaitTypeDef(
     _RequiredDescribeBotLocaleRequestBotLocaleBuiltWaitTypeDef,
     _OptionalDescribeBotLocaleRequestBotLocaleBuiltWaitTypeDef,
 ):
     pass
 
-
 _RequiredDescribeBotLocaleRequestBotLocaleCreatedWaitTypeDef = TypedDict(
     "_RequiredDescribeBotLocaleRequestBotLocaleCreatedWaitTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
     },
@@ -2724,22 +3176,20 @@
     "_OptionalDescribeBotLocaleRequestBotLocaleCreatedWaitTypeDef",
     {
         "WaiterConfig": WaiterConfigTypeDef,
     },
     total=False,
 )
 
-
 class DescribeBotLocaleRequestBotLocaleCreatedWaitTypeDef(
     _RequiredDescribeBotLocaleRequestBotLocaleCreatedWaitTypeDef,
     _OptionalDescribeBotLocaleRequestBotLocaleCreatedWaitTypeDef,
 ):
     pass
 
-
 _RequiredDescribeBotLocaleRequestBotLocaleExpressTestingAvailableWaitTypeDef = TypedDict(
     "_RequiredDescribeBotLocaleRequestBotLocaleExpressTestingAvailableWaitTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
     },
@@ -2748,44 +3198,40 @@
     "_OptionalDescribeBotLocaleRequestBotLocaleExpressTestingAvailableWaitTypeDef",
     {
         "WaiterConfig": WaiterConfigTypeDef,
     },
     total=False,
 )
 
-
 class DescribeBotLocaleRequestBotLocaleExpressTestingAvailableWaitTypeDef(
     _RequiredDescribeBotLocaleRequestBotLocaleExpressTestingAvailableWaitTypeDef,
     _OptionalDescribeBotLocaleRequestBotLocaleExpressTestingAvailableWaitTypeDef,
 ):
     pass
 
-
 _RequiredDescribeBotRequestBotAvailableWaitTypeDef = TypedDict(
     "_RequiredDescribeBotRequestBotAvailableWaitTypeDef",
     {
         "botId": str,
     },
 )
 _OptionalDescribeBotRequestBotAvailableWaitTypeDef = TypedDict(
     "_OptionalDescribeBotRequestBotAvailableWaitTypeDef",
     {
         "WaiterConfig": WaiterConfigTypeDef,
     },
     total=False,
 )
 
-
 class DescribeBotRequestBotAvailableWaitTypeDef(
     _RequiredDescribeBotRequestBotAvailableWaitTypeDef,
     _OptionalDescribeBotRequestBotAvailableWaitTypeDef,
 ):
     pass
 
-
 _RequiredDescribeBotVersionRequestBotVersionAvailableWaitTypeDef = TypedDict(
     "_RequiredDescribeBotVersionRequestBotVersionAvailableWaitTypeDef",
     {
         "botId": str,
         "botVersion": str,
     },
 )
@@ -2793,66 +3239,60 @@
     "_OptionalDescribeBotVersionRequestBotVersionAvailableWaitTypeDef",
     {
         "WaiterConfig": WaiterConfigTypeDef,
     },
     total=False,
 )
 
-
 class DescribeBotVersionRequestBotVersionAvailableWaitTypeDef(
     _RequiredDescribeBotVersionRequestBotVersionAvailableWaitTypeDef,
     _OptionalDescribeBotVersionRequestBotVersionAvailableWaitTypeDef,
 ):
     pass
 
-
 _RequiredDescribeExportRequestBotExportCompletedWaitTypeDef = TypedDict(
     "_RequiredDescribeExportRequestBotExportCompletedWaitTypeDef",
     {
         "exportId": str,
     },
 )
 _OptionalDescribeExportRequestBotExportCompletedWaitTypeDef = TypedDict(
     "_OptionalDescribeExportRequestBotExportCompletedWaitTypeDef",
     {
         "WaiterConfig": WaiterConfigTypeDef,
     },
     total=False,
 )
 
-
 class DescribeExportRequestBotExportCompletedWaitTypeDef(
     _RequiredDescribeExportRequestBotExportCompletedWaitTypeDef,
     _OptionalDescribeExportRequestBotExportCompletedWaitTypeDef,
 ):
     pass
 
-
 _RequiredDescribeImportRequestBotImportCompletedWaitTypeDef = TypedDict(
     "_RequiredDescribeImportRequestBotImportCompletedWaitTypeDef",
     {
         "importId": str,
     },
 )
 _OptionalDescribeImportRequestBotImportCompletedWaitTypeDef = TypedDict(
     "_OptionalDescribeImportRequestBotImportCompletedWaitTypeDef",
     {
         "WaiterConfig": WaiterConfigTypeDef,
     },
     total=False,
 )
 
-
 class DescribeImportRequestBotImportCompletedWaitTypeDef(
     _RequiredDescribeImportRequestBotImportCompletedWaitTypeDef,
     _OptionalDescribeImportRequestBotImportCompletedWaitTypeDef,
 ):
     pass
 
-
 DescribeBotVersionResponseTypeDef = TypedDict(
     "DescribeBotVersionResponseTypeDef",
     {
         "botId": str,
         "botName": str,
         "botVersion": str,
         "description": str,
@@ -2861,39 +3301,101 @@
         "idleSessionTTLInSeconds": int,
         "botStatus": BotStatusType,
         "failureReasons": List[str],
         "creationDateTime": datetime,
         "parentBotNetworks": List[ParentBotNetworkTypeDef],
         "botType": BotTypeType,
         "botMembers": List[BotMemberTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateBotRecommendationRequestRequestTypeDef = TypedDict(
     "UpdateBotRecommendationRequestRequestTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
         "botRecommendationId": str,
         "encryptionSetting": EncryptionSettingTypeDef,
     },
 )
 
+DescribeTestSetResponseTypeDef = TypedDict(
+    "DescribeTestSetResponseTypeDef",
+    {
+        "testSetId": str,
+        "testSetName": str,
+        "description": str,
+        "modality": TestSetModalityType,
+        "status": TestSetStatusType,
+        "roleArn": str,
+        "numTurns": int,
+        "storageLocation": TestSetStorageLocationTypeDef,
+        "creationDateTime": datetime,
+        "lastUpdatedDateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+TestSetSummaryTypeDef = TypedDict(
+    "TestSetSummaryTypeDef",
+    {
+        "testSetId": str,
+        "testSetName": str,
+        "description": str,
+        "modality": TestSetModalityType,
+        "status": TestSetStatusType,
+        "roleArn": str,
+        "numTurns": int,
+        "storageLocation": TestSetStorageLocationTypeDef,
+        "creationDateTime": datetime,
+        "lastUpdatedDateTime": datetime,
+    },
+    total=False,
+)
+
+UpdateTestSetResponseTypeDef = TypedDict(
+    "UpdateTestSetResponseTypeDef",
+    {
+        "testSetId": str,
+        "testSetName": str,
+        "description": str,
+        "modality": TestSetModalityType,
+        "status": TestSetStatusType,
+        "roleArn": str,
+        "numTurns": int,
+        "storageLocation": TestSetStorageLocationTypeDef,
+        "creationDateTime": datetime,
+        "lastUpdatedDateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DialogStateTypeDef = TypedDict(
     "DialogStateTypeDef",
     {
         "dialogAction": DialogActionTypeDef,
         "intent": IntentOverrideTypeDef,
         "sessionAttributes": Mapping[str, str],
     },
     total=False,
 )
 
+ExportResourceSpecificationTypeDef = TypedDict(
+    "ExportResourceSpecificationTypeDef",
+    {
+        "botExportSpecification": BotExportSpecificationTypeDef,
+        "botLocaleExportSpecification": BotLocaleExportSpecificationTypeDef,
+        "customVocabularyExportSpecification": CustomVocabularyExportSpecificationTypeDef,
+        "testSetExportSpecification": TestSetExportSpecificationTypeDef,
+    },
+    total=False,
+)
+
 ListExportsRequestRequestTypeDef = TypedDict(
     "ListExportsRequestRequestTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "sortBy": ExportSortByTypeDef,
         "filters": Sequence[ExportFilterTypeDef],
@@ -2930,15 +3432,34 @@
     "ListImportsResponseTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "importSummaries": List[ImportSummaryTypeDef],
         "nextToken": str,
         "localeId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+InputSessionStateSpecificationTypeDef = TypedDict(
+    "InputSessionStateSpecificationTypeDef",
+    {
+        "sessionAttributes": Dict[str, str],
+        "activeContexts": List[ActiveContextTypeDef],
+        "runtimeHints": RuntimeHintsTypeDef,
+    },
+    total=False,
+)
+
+IntentClassificationTestResultItemTypeDef = TypedDict(
+    "IntentClassificationTestResultItemTypeDef",
+    {
+        "intentName": str,
+        "multiTurnConversation": bool,
+        "resultCounts": IntentClassificationTestResultItemCountsTypeDef,
     },
 )
 
 _RequiredListIntentsRequestRequestTypeDef = TypedDict(
     "_RequiredListIntentsRequestRequestTypeDef",
     {
         "botId": str,
@@ -2953,31 +3474,29 @@
         "filters": Sequence[IntentFilterTypeDef],
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
-
 class ListIntentsRequestRequestTypeDef(
     _RequiredListIntentsRequestRequestTypeDef, _OptionalListIntentsRequestRequestTypeDef
 ):
     pass
 
-
 ListRecommendedIntentsResponseTypeDef = TypedDict(
     "ListRecommendedIntentsResponseTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
         "botRecommendationId": str,
         "summaryList": List[RecommendedIntentSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredListSlotTypesRequestRequestTypeDef = TypedDict(
     "_RequiredListSlotTypesRequestRequestTypeDef",
     {
         "botId": str,
@@ -2992,30 +3511,28 @@
         "filters": Sequence[SlotTypeFilterTypeDef],
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
-
 class ListSlotTypesRequestRequestTypeDef(
     _RequiredListSlotTypesRequestRequestTypeDef, _OptionalListSlotTypesRequestRequestTypeDef
 ):
     pass
 
-
 ListSlotTypesResponseTypeDef = TypedDict(
     "ListSlotTypesResponseTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
         "slotTypeSummaries": List[SlotTypeSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredListSlotsRequestRequestTypeDef = TypedDict(
     "_RequiredListSlotsRequestRequestTypeDef",
     {
         "botId": str,
@@ -3031,28 +3548,62 @@
         "filters": Sequence[SlotFilterTypeDef],
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
-
 class ListSlotsRequestRequestTypeDef(
     _RequiredListSlotsRequestRequestTypeDef, _OptionalListSlotsRequestRequestTypeDef
 ):
     pass
 
+ListTestExecutionsRequestRequestTypeDef = TypedDict(
+    "ListTestExecutionsRequestRequestTypeDef",
+    {
+        "sortBy": TestExecutionSortByTypeDef,
+        "maxResults": int,
+        "nextToken": str,
+    },
+    total=False,
+)
+
+ListTestSetsRequestRequestTypeDef = TypedDict(
+    "ListTestSetsRequestRequestTypeDef",
+    {
+        "sortBy": TestSetSortByTypeDef,
+        "maxResults": int,
+        "nextToken": str,
+    },
+    total=False,
+)
+
+OverallTestResultsTypeDef = TypedDict(
+    "OverallTestResultsTypeDef",
+    {
+        "items": List[OverallTestResultItemTypeDef],
+    },
+)
 
 UtteranceAggregationDurationTypeDef = TypedDict(
     "UtteranceAggregationDurationTypeDef",
     {
         "relativeAggregationDuration": RelativeAggregationDurationTypeDef,
     },
 )
 
+RuntimeHintDetailsTypeDef = TypedDict(
+    "RuntimeHintDetailsTypeDef",
+    {
+        "runtimeHintValues": List[RuntimeHintValueTypeDef],
+        "subSlotHints": Dict[str, Dict[str, Any]],
+    },
+    total=False,
+)
+
 SlotTypeValueTypeDef = TypedDict(
     "SlotTypeValueTypeDef",
     {
         "sampleValue": SampleValueTypeDef,
         "synonyms": Sequence[SampleValueTypeDef],
     },
     total=False,
@@ -3061,14 +3612,22 @@
 SlotDefaultValueSpecificationTypeDef = TypedDict(
     "SlotDefaultValueSpecificationTypeDef",
     {
         "defaultValueList": Sequence[SlotDefaultValueTypeDef],
     },
 )
 
+SlotResolutionTestResultItemTypeDef = TypedDict(
+    "SlotResolutionTestResultItemTypeDef",
+    {
+        "slotName": str,
+        "resultCounts": SlotResolutionTestResultItemCountsTypeDef,
+    },
+)
+
 SlotValueOverrideTypeDef = TypedDict(
     "SlotValueOverrideTypeDef",
     {
         "shape": SlotShapeType,
         "value": SlotValueTypeDef,
         "values": Sequence[Dict[str, Any]],
     },
@@ -3086,20 +3645,88 @@
     {
         "regexFilter": SlotValueRegexFilterTypeDef,
         "advancedRecognitionSetting": AdvancedRecognitionSettingTypeDef,
     },
     total=False,
 )
 
-
 class SlotValueSelectionSettingTypeDef(
     _RequiredSlotValueSelectionSettingTypeDef, _OptionalSlotValueSelectionSettingTypeDef
 ):
     pass
 
+TestSetDiscrepancyErrorsTypeDef = TypedDict(
+    "TestSetDiscrepancyErrorsTypeDef",
+    {
+        "intentDiscrepancies": List[TestSetIntentDiscrepancyItemTypeDef],
+        "slotDiscrepancies": List[TestSetSlotDiscrepancyItemTypeDef],
+    },
+)
+
+TestSetDiscrepancyReportResourceTargetTypeDef = TypedDict(
+    "TestSetDiscrepancyReportResourceTargetTypeDef",
+    {
+        "botAliasTarget": TestSetDiscrepancyReportBotAliasTargetTypeDef,
+    },
+    total=False,
+)
+
+_RequiredTestSetImportResourceSpecificationTypeDef = TypedDict(
+    "_RequiredTestSetImportResourceSpecificationTypeDef",
+    {
+        "testSetName": str,
+        "roleArn": str,
+        "storageLocation": TestSetStorageLocationTypeDef,
+        "importInputLocation": TestSetImportInputLocationTypeDef,
+        "modality": TestSetModalityType,
+    },
+)
+_OptionalTestSetImportResourceSpecificationTypeDef = TypedDict(
+    "_OptionalTestSetImportResourceSpecificationTypeDef",
+    {
+        "description": str,
+        "testSetTags": Dict[str, str],
+    },
+    total=False,
+)
+
+class TestSetImportResourceSpecificationTypeDef(
+    _RequiredTestSetImportResourceSpecificationTypeDef,
+    _OptionalTestSetImportResourceSpecificationTypeDef,
+):
+    pass
+
+_RequiredUserTurnOutputSpecificationTypeDef = TypedDict(
+    "_RequiredUserTurnOutputSpecificationTypeDef",
+    {
+        "intent": UserTurnIntentOutputTypeDef,
+    },
+)
+_OptionalUserTurnOutputSpecificationTypeDef = TypedDict(
+    "_OptionalUserTurnOutputSpecificationTypeDef",
+    {
+        "activeContexts": List[ActiveContextTypeDef],
+        "transcript": str,
+    },
+    total=False,
+)
+
+class UserTurnOutputSpecificationTypeDef(
+    _RequiredUserTurnOutputSpecificationTypeDef, _OptionalUserTurnOutputSpecificationTypeDef
+):
+    pass
+
+UtteranceInputSpecificationTypeDef = TypedDict(
+    "UtteranceInputSpecificationTypeDef",
+    {
+        "textInput": str,
+        "audioInput": UtteranceAudioInputSpecificationTypeDef,
+    },
+    total=False,
+)
 
 _RequiredPromptAttemptSpecificationTypeDef = TypedDict(
     "_RequiredPromptAttemptSpecificationTypeDef",
     {
         "allowedInputTypes": AllowedInputTypesTypeDef,
     },
 )
@@ -3109,35 +3736,91 @@
         "allowInterrupt": bool,
         "audioAndDTMFInputSpecification": AudioAndDTMFInputSpecificationTypeDef,
         "textInputSpecification": TextInputSpecificationTypeDef,
     },
     total=False,
 )
 
-
 class PromptAttemptSpecificationTypeDef(
     _RequiredPromptAttemptSpecificationTypeDef, _OptionalPromptAttemptSpecificationTypeDef
 ):
     pass
 
-
 AudioLogSettingTypeDef = TypedDict(
     "AudioLogSettingTypeDef",
     {
         "enabled": bool,
         "destination": AudioLogDestinationTypeDef,
     },
 )
 
-ImportResourceSpecificationTypeDef = TypedDict(
-    "ImportResourceSpecificationTypeDef",
+DescribeTestExecutionResponseTypeDef = TypedDict(
+    "DescribeTestExecutionResponseTypeDef",
     {
-        "botImportSpecification": BotImportSpecificationTypeDef,
-        "botLocaleImportSpecification": BotLocaleImportSpecificationTypeDef,
-        "customVocabularyImportSpecification": CustomVocabularyImportSpecificationTypeDef,
+        "testExecutionId": str,
+        "creationDateTime": datetime,
+        "lastUpdatedDateTime": datetime,
+        "testExecutionStatus": TestExecutionStatusType,
+        "testSetId": str,
+        "testSetName": str,
+        "target": TestExecutionTargetTypeDef,
+        "apiMode": TestExecutionApiModeType,
+        "testExecutionModality": TestExecutionModalityType,
+        "failureReasons": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredStartTestExecutionRequestRequestTypeDef = TypedDict(
+    "_RequiredStartTestExecutionRequestRequestTypeDef",
+    {
+        "testSetId": str,
+        "target": TestExecutionTargetTypeDef,
+        "apiMode": TestExecutionApiModeType,
+    },
+)
+_OptionalStartTestExecutionRequestRequestTypeDef = TypedDict(
+    "_OptionalStartTestExecutionRequestRequestTypeDef",
+    {
+        "testExecutionModality": TestExecutionModalityType,
+    },
+    total=False,
+)
+
+class StartTestExecutionRequestRequestTypeDef(
+    _RequiredStartTestExecutionRequestRequestTypeDef,
+    _OptionalStartTestExecutionRequestRequestTypeDef,
+):
+    pass
+
+StartTestExecutionResponseTypeDef = TypedDict(
+    "StartTestExecutionResponseTypeDef",
+    {
+        "testExecutionId": str,
+        "creationDateTime": datetime,
+        "testSetId": str,
+        "target": TestExecutionTargetTypeDef,
+        "apiMode": TestExecutionApiModeType,
+        "testExecutionModality": TestExecutionModalityType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+TestExecutionSummaryTypeDef = TypedDict(
+    "TestExecutionSummaryTypeDef",
+    {
+        "testExecutionId": str,
+        "creationDateTime": datetime,
+        "lastUpdatedDateTime": datetime,
+        "testExecutionStatus": TestExecutionStatusType,
+        "testSetId": str,
+        "testSetName": str,
+        "target": TestExecutionTargetTypeDef,
+        "apiMode": TestExecutionApiModeType,
+        "testExecutionModality": TestExecutionModalityType,
     },
     total=False,
 )
 
 BotRecommendationResultsTypeDef = TypedDict(
     "BotRecommendationResultsTypeDef",
     {
@@ -3177,30 +3860,82 @@
     "_OptionalBotAliasLocaleSettingsTypeDef",
     {
         "codeHookSpecification": CodeHookSpecificationTypeDef,
     },
     total=False,
 )
 
-
 class BotAliasLocaleSettingsTypeDef(
     _RequiredBotAliasLocaleSettingsTypeDef, _OptionalBotAliasLocaleSettingsTypeDef
 ):
     pass
 
+ConversationLevelTestResultsTypeDef = TypedDict(
+    "ConversationLevelTestResultsTypeDef",
+    {
+        "items": List[ConversationLevelTestResultItemTypeDef],
+    },
+)
+
+_RequiredListTestExecutionResultItemsRequestRequestTypeDef = TypedDict(
+    "_RequiredListTestExecutionResultItemsRequestRequestTypeDef",
+    {
+        "testExecutionId": str,
+        "resultFilterBy": TestExecutionResultFilterByTypeDef,
+    },
+)
+_OptionalListTestExecutionResultItemsRequestRequestTypeDef = TypedDict(
+    "_OptionalListTestExecutionResultItemsRequestRequestTypeDef",
+    {
+        "maxResults": int,
+        "nextToken": str,
+    },
+    total=False,
+)
+
+class ListTestExecutionResultItemsRequestRequestTypeDef(
+    _RequiredListTestExecutionResultItemsRequestRequestTypeDef,
+    _OptionalListTestExecutionResultItemsRequestRequestTypeDef,
+):
+    pass
+
+TestSetGenerationDataSourceTypeDef = TypedDict(
+    "TestSetGenerationDataSourceTypeDef",
+    {
+        "conversationLogsDataSource": ConversationLogsDataSourceTypeDef,
+    },
+    total=False,
+)
 
 ListIntentsResponseTypeDef = TypedDict(
     "ListIntentsResponseTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
         "intentSummaries": List[IntentSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+TranscriptFilterTypeDef = TypedDict(
+    "TranscriptFilterTypeDef",
+    {
+        "lexTranscriptFilter": LexTranscriptFilterTypeDef,
+    },
+    total=False,
+)
+
+ListTestSetsResponseTypeDef = TypedDict(
+    "ListTestSetsResponseTypeDef",
+    {
+        "testSets": List[TestSetSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateExportRequestRequestTypeDef = TypedDict(
     "_RequiredCreateExportRequestRequestTypeDef",
     {
         "resourceSpecification": ExportResourceSpecificationTypeDef,
@@ -3211,45 +3946,43 @@
     "_OptionalCreateExportRequestRequestTypeDef",
     {
         "filePassword": str,
     },
     total=False,
 )
 
-
 class CreateExportRequestRequestTypeDef(
     _RequiredCreateExportRequestRequestTypeDef, _OptionalCreateExportRequestRequestTypeDef
 ):
     pass
 
-
 CreateExportResponseTypeDef = TypedDict(
     "CreateExportResponseTypeDef",
     {
         "exportId": str,
         "resourceSpecification": ExportResourceSpecificationTypeDef,
         "fileFormat": ImportExportFileFormatType,
         "exportStatus": ExportStatusType,
         "creationDateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeExportResponseTypeDef = TypedDict(
     "DescribeExportResponseTypeDef",
     {
         "exportId": str,
         "resourceSpecification": ExportResourceSpecificationTypeDef,
         "fileFormat": ImportExportFileFormatType,
         "exportStatus": ExportStatusType,
         "failureReasons": List[str],
         "downloadUrl": str,
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ExportSummaryTypeDef = TypedDict(
     "ExportSummaryTypeDef",
     {
         "exportId": str,
@@ -3267,32 +4000,31 @@
     {
         "exportId": str,
         "resourceSpecification": ExportResourceSpecificationTypeDef,
         "fileFormat": ImportExportFileFormatType,
         "exportStatus": ExportStatusType,
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-TranscriptFilterTypeDef = TypedDict(
-    "TranscriptFilterTypeDef",
+ExternalSourceSettingTypeDef = TypedDict(
+    "ExternalSourceSettingTypeDef",
     {
-        "lexTranscriptFilter": LexTranscriptFilterTypeDef,
+        "grammarSlotTypeSetting": GrammarSlotTypeSettingTypeDef,
     },
     total=False,
 )
 
-ExternalSourceSettingTypeDef = TypedDict(
-    "ExternalSourceSettingTypeDef",
+IntentClassificationTestResultsTypeDef = TypedDict(
+    "IntentClassificationTestResultsTypeDef",
     {
-        "grammarSlotTypeSetting": GrammarSlotTypeSettingTypeDef,
+        "items": List[IntentClassificationTestResultItemTypeDef],
     },
-    total=False,
 )
 
 _RequiredListAggregatedUtterancesRequestRequestTypeDef = TypedDict(
     "_RequiredListAggregatedUtterancesRequestRequestTypeDef",
     {
         "botId": str,
         "localeId": str,
@@ -3308,87 +4040,118 @@
         "filters": Sequence[AggregatedUtterancesFilterTypeDef],
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
-
 class ListAggregatedUtterancesRequestRequestTypeDef(
     _RequiredListAggregatedUtterancesRequestRequestTypeDef,
     _OptionalListAggregatedUtterancesRequestRequestTypeDef,
 ):
     pass
 
-
 ListAggregatedUtterancesResponseTypeDef = TypedDict(
     "ListAggregatedUtterancesResponseTypeDef",
     {
         "botId": str,
         "botAliasId": str,
         "botVersion": str,
         "localeId": str,
         "aggregationDuration": UtteranceAggregationDurationTypeDef,
         "aggregationWindowStartTime": datetime,
         "aggregationWindowEndTime": datetime,
         "aggregationLastRefreshedDateTime": datetime,
         "aggregatedUtterancesSummaries": List[AggregatedUtterancesSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DescribeImportResponseTypeDef = TypedDict(
-    "DescribeImportResponseTypeDef",
+IntentLevelSlotResolutionTestResultItemTypeDef = TypedDict(
+    "IntentLevelSlotResolutionTestResultItemTypeDef",
     {
-        "importId": str,
-        "resourceSpecification": ImportResourceSpecificationTypeDef,
-        "importedResourceId": str,
-        "importedResourceName": str,
-        "mergeStrategy": MergeStrategyType,
-        "importStatus": ImportStatusType,
-        "failureReasons": List[str],
+        "intentName": str,
+        "multiTurnConversation": bool,
+        "slotResolutionResults": List[SlotResolutionTestResultItemTypeDef],
+    },
+)
+
+CreateTestSetDiscrepancyReportRequestRequestTypeDef = TypedDict(
+    "CreateTestSetDiscrepancyReportRequestRequestTypeDef",
+    {
+        "testSetId": str,
+        "target": TestSetDiscrepancyReportResourceTargetTypeDef,
+    },
+)
+
+CreateTestSetDiscrepancyReportResponseTypeDef = TypedDict(
+    "CreateTestSetDiscrepancyReportResponseTypeDef",
+    {
+        "testSetDiscrepancyReportId": str,
         "creationDateTime": datetime,
-        "lastUpdatedDateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "testSetId": str,
+        "target": TestSetDiscrepancyReportResourceTargetTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-_RequiredStartImportRequestRequestTypeDef = TypedDict(
-    "_RequiredStartImportRequestRequestTypeDef",
+DescribeTestSetDiscrepancyReportResponseTypeDef = TypedDict(
+    "DescribeTestSetDiscrepancyReportResponseTypeDef",
     {
-        "importId": str,
-        "resourceSpecification": ImportResourceSpecificationTypeDef,
-        "mergeStrategy": MergeStrategyType,
+        "testSetDiscrepancyReportId": str,
+        "testSetId": str,
+        "creationDateTime": datetime,
+        "target": TestSetDiscrepancyReportResourceTargetTypeDef,
+        "testSetDiscrepancyReportStatus": TestSetDiscrepancyReportStatusType,
+        "lastUpdatedDataTime": datetime,
+        "testSetDiscrepancyTopErrors": TestSetDiscrepancyErrorsTypeDef,
+        "testSetDiscrepancyRawOutputUrl": str,
+        "failureReasons": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalStartImportRequestRequestTypeDef = TypedDict(
-    "_OptionalStartImportRequestRequestTypeDef",
+
+ImportResourceSpecificationTypeDef = TypedDict(
+    "ImportResourceSpecificationTypeDef",
     {
-        "filePassword": str,
+        "botImportSpecification": BotImportSpecificationTypeDef,
+        "botLocaleImportSpecification": BotLocaleImportSpecificationTypeDef,
+        "customVocabularyImportSpecification": CustomVocabularyImportSpecificationTypeDef,
+        "testSetImportResourceSpecification": TestSetImportResourceSpecificationTypeDef,
     },
     total=False,
 )
 
+_RequiredUserTurnInputSpecificationTypeDef = TypedDict(
+    "_RequiredUserTurnInputSpecificationTypeDef",
+    {
+        "utteranceInput": UtteranceInputSpecificationTypeDef,
+    },
+)
+_OptionalUserTurnInputSpecificationTypeDef = TypedDict(
+    "_OptionalUserTurnInputSpecificationTypeDef",
+    {
+        "requestAttributes": Dict[str, str],
+        "sessionState": InputSessionStateSpecificationTypeDef,
+    },
+    total=False,
+)
 
-class StartImportRequestRequestTypeDef(
-    _RequiredStartImportRequestRequestTypeDef, _OptionalStartImportRequestRequestTypeDef
+class UserTurnInputSpecificationTypeDef(
+    _RequiredUserTurnInputSpecificationTypeDef, _OptionalUserTurnInputSpecificationTypeDef
 ):
     pass
 
-
-StartImportResponseTypeDef = TypedDict(
-    "StartImportResponseTypeDef",
+ListTestExecutionsResponseTypeDef = TypedDict(
+    "ListTestExecutionsResponseTypeDef",
     {
-        "importId": str,
-        "resourceSpecification": ImportResourceSpecificationTypeDef,
-        "mergeStrategy": MergeStrategyType,
-        "importStatus": ImportStatusType,
-        "creationDateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "testExecutions": List[TestExecutionSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredMessageGroupTypeDef = TypedDict(
     "_RequiredMessageGroupTypeDef",
     {
         "message": MessageTypeDef,
@@ -3398,37 +4161,81 @@
     "_OptionalMessageGroupTypeDef",
     {
         "variations": Sequence[MessageTypeDef],
     },
     total=False,
 )
 
-
 class MessageGroupTypeDef(_RequiredMessageGroupTypeDef, _OptionalMessageGroupTypeDef):
     pass
 
-
 ConversationLogSettingsTypeDef = TypedDict(
     "ConversationLogSettingsTypeDef",
     {
         "textLogSettings": Sequence[TextLogSettingTypeDef],
         "audioLogSettings": Sequence[AudioLogSettingTypeDef],
     },
     total=False,
 )
 
-ListExportsResponseTypeDef = TypedDict(
-    "ListExportsResponseTypeDef",
+DescribeTestSetGenerationResponseTypeDef = TypedDict(
+    "DescribeTestSetGenerationResponseTypeDef",
     {
-        "botId": str,
-        "botVersion": str,
-        "exportSummaries": List[ExportSummaryTypeDef],
-        "nextToken": str,
-        "localeId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "testSetGenerationId": str,
+        "testSetGenerationStatus": TestSetGenerationStatusType,
+        "failureReasons": List[str],
+        "testSetId": str,
+        "testSetName": str,
+        "description": str,
+        "storageLocation": TestSetStorageLocationTypeDef,
+        "generationDataSource": TestSetGenerationDataSourceTypeDef,
+        "roleArn": str,
+        "creationDateTime": datetime,
+        "lastUpdatedDateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredStartTestSetGenerationRequestRequestTypeDef = TypedDict(
+    "_RequiredStartTestSetGenerationRequestRequestTypeDef",
+    {
+        "testSetName": str,
+        "storageLocation": TestSetStorageLocationTypeDef,
+        "generationDataSource": TestSetGenerationDataSourceTypeDef,
+        "roleArn": str,
+    },
+)
+_OptionalStartTestSetGenerationRequestRequestTypeDef = TypedDict(
+    "_OptionalStartTestSetGenerationRequestRequestTypeDef",
+    {
+        "description": str,
+        "testSetTags": Mapping[str, str],
+    },
+    total=False,
+)
+
+class StartTestSetGenerationRequestRequestTypeDef(
+    _RequiredStartTestSetGenerationRequestRequestTypeDef,
+    _OptionalStartTestSetGenerationRequestRequestTypeDef,
+):
+    pass
+
+StartTestSetGenerationResponseTypeDef = TypedDict(
+    "StartTestSetGenerationResponseTypeDef",
+    {
+        "testSetGenerationId": str,
+        "creationDateTime": datetime,
+        "testSetGenerationStatus": TestSetGenerationStatusType,
+        "testSetName": str,
+        "description": str,
+        "storageLocation": TestSetStorageLocationTypeDef,
+        "generationDataSource": TestSetGenerationDataSourceTypeDef,
+        "roleArn": str,
+        "testSetTags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredS3BucketTranscriptSourceTypeDef = TypedDict(
     "_RequiredS3BucketTranscriptSourceTypeDef",
     {
         "s3BucketName": str,
@@ -3441,20 +4248,30 @@
         "pathFormat": PathFormatTypeDef,
         "transcriptFilter": TranscriptFilterTypeDef,
         "kmsKeyArn": str,
     },
     total=False,
 )
 
-
 class S3BucketTranscriptSourceTypeDef(
     _RequiredS3BucketTranscriptSourceTypeDef, _OptionalS3BucketTranscriptSourceTypeDef
 ):
     pass
 
+ListExportsResponseTypeDef = TypedDict(
+    "ListExportsResponseTypeDef",
+    {
+        "botId": str,
+        "botVersion": str,
+        "exportSummaries": List[ExportSummaryTypeDef],
+        "nextToken": str,
+        "localeId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredCreateSlotTypeRequestRequestTypeDef = TypedDict(
     "_RequiredCreateSlotTypeRequestRequestTypeDef",
     {
         "slotTypeName": str,
         "botId": str,
         "botVersion": str,
@@ -3470,21 +4287,19 @@
         "parentSlotTypeSignature": str,
         "externalSourceSetting": ExternalSourceSettingTypeDef,
         "compositeSlotTypeSetting": CompositeSlotTypeSettingTypeDef,
     },
     total=False,
 )
 
-
 class CreateSlotTypeRequestRequestTypeDef(
     _RequiredCreateSlotTypeRequestRequestTypeDef, _OptionalCreateSlotTypeRequestRequestTypeDef
 ):
     pass
 
-
 CreateSlotTypeResponseTypeDef = TypedDict(
     "CreateSlotTypeResponseTypeDef",
     {
         "slotTypeId": str,
         "slotTypeName": str,
         "description": str,
         "slotTypeValues": List[SlotTypeValueTypeDef],
@@ -3492,15 +4307,15 @@
         "parentSlotTypeSignature": str,
         "botId": str,
         "botVersion": str,
         "localeId": str,
         "creationDateTime": datetime,
         "externalSourceSetting": ExternalSourceSettingTypeDef,
         "compositeSlotTypeSetting": CompositeSlotTypeSettingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSlotTypeResponseTypeDef = TypedDict(
     "DescribeSlotTypeResponseTypeDef",
     {
         "slotTypeId": str,
@@ -3512,15 +4327,15 @@
         "botId": str,
         "botVersion": str,
         "localeId": str,
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
         "externalSourceSetting": ExternalSourceSettingTypeDef,
         "compositeSlotTypeSetting": CompositeSlotTypeSettingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateSlotTypeRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateSlotTypeRequestRequestTypeDef",
     {
         "slotTypeId": str,
@@ -3539,21 +4354,19 @@
         "parentSlotTypeSignature": str,
         "externalSourceSetting": ExternalSourceSettingTypeDef,
         "compositeSlotTypeSetting": CompositeSlotTypeSettingTypeDef,
     },
     total=False,
 )
 
-
 class UpdateSlotTypeRequestRequestTypeDef(
     _RequiredUpdateSlotTypeRequestRequestTypeDef, _OptionalUpdateSlotTypeRequestRequestTypeDef
 ):
     pass
 
-
 UpdateSlotTypeResponseTypeDef = TypedDict(
     "UpdateSlotTypeResponseTypeDef",
     {
         "slotTypeId": str,
         "slotTypeName": str,
         "description": str,
         "slotTypeValues": List[SlotTypeValueTypeDef],
@@ -3562,15 +4375,103 @@
         "botId": str,
         "botVersion": str,
         "localeId": str,
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
         "externalSourceSetting": ExternalSourceSettingTypeDef,
         "compositeSlotTypeSetting": CompositeSlotTypeSettingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+IntentLevelSlotResolutionTestResultsTypeDef = TypedDict(
+    "IntentLevelSlotResolutionTestResultsTypeDef",
+    {
+        "items": List[IntentLevelSlotResolutionTestResultItemTypeDef],
+    },
+)
+
+DescribeImportResponseTypeDef = TypedDict(
+    "DescribeImportResponseTypeDef",
+    {
+        "importId": str,
+        "resourceSpecification": ImportResourceSpecificationTypeDef,
+        "importedResourceId": str,
+        "importedResourceName": str,
+        "mergeStrategy": MergeStrategyType,
+        "importStatus": ImportStatusType,
+        "failureReasons": List[str],
+        "creationDateTime": datetime,
+        "lastUpdatedDateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredStartImportRequestRequestTypeDef = TypedDict(
+    "_RequiredStartImportRequestRequestTypeDef",
+    {
+        "importId": str,
+        "resourceSpecification": ImportResourceSpecificationTypeDef,
+        "mergeStrategy": MergeStrategyType,
+    },
+)
+_OptionalStartImportRequestRequestTypeDef = TypedDict(
+    "_OptionalStartImportRequestRequestTypeDef",
+    {
+        "filePassword": str,
+    },
+    total=False,
+)
+
+class StartImportRequestRequestTypeDef(
+    _RequiredStartImportRequestRequestTypeDef, _OptionalStartImportRequestRequestTypeDef
+):
+    pass
+
+StartImportResponseTypeDef = TypedDict(
+    "StartImportResponseTypeDef",
+    {
+        "importId": str,
+        "resourceSpecification": ImportResourceSpecificationTypeDef,
+        "mergeStrategy": MergeStrategyType,
+        "importStatus": ImportStatusType,
+        "creationDateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredUserTurnResultTypeDef = TypedDict(
+    "_RequiredUserTurnResultTypeDef",
+    {
+        "input": UserTurnInputSpecificationTypeDef,
+        "expectedOutput": UserTurnOutputSpecificationTypeDef,
+    },
+)
+_OptionalUserTurnResultTypeDef = TypedDict(
+    "_OptionalUserTurnResultTypeDef",
+    {
+        "actualOutput": UserTurnOutputSpecificationTypeDef,
+        "errorDetails": ExecutionErrorDetailsTypeDef,
+        "endToEndResult": TestResultMatchStatusType,
+        "intentMatchResult": TestResultMatchStatusType,
+        "slotMatchResult": TestResultMatchStatusType,
+        "speechTranscriptionResult": TestResultMatchStatusType,
+        "conversationLevelResult": ConversationLevelResultDetailTypeDef,
+    },
+    total=False,
+)
+
+class UserTurnResultTypeDef(_RequiredUserTurnResultTypeDef, _OptionalUserTurnResultTypeDef):
+    pass
+
+UserTurnSpecificationTypeDef = TypedDict(
+    "UserTurnSpecificationTypeDef",
+    {
+        "input": UserTurnInputSpecificationTypeDef,
+        "expected": UserTurnOutputSpecificationTypeDef,
     },
 )
 
 _RequiredFulfillmentStartResponseSpecificationTypeDef = TypedDict(
     "_RequiredFulfillmentStartResponseSpecificationTypeDef",
     {
         "delayInSeconds": int,
@@ -3581,22 +4482,20 @@
     "_OptionalFulfillmentStartResponseSpecificationTypeDef",
     {
         "allowInterrupt": bool,
     },
     total=False,
 )
 
-
 class FulfillmentStartResponseSpecificationTypeDef(
     _RequiredFulfillmentStartResponseSpecificationTypeDef,
     _OptionalFulfillmentStartResponseSpecificationTypeDef,
 ):
     pass
 
-
 _RequiredFulfillmentUpdateResponseSpecificationTypeDef = TypedDict(
     "_RequiredFulfillmentUpdateResponseSpecificationTypeDef",
     {
         "frequencyInSeconds": int,
         "messageGroups": Sequence[MessageGroupTypeDef],
     },
 )
@@ -3604,22 +4503,20 @@
     "_OptionalFulfillmentUpdateResponseSpecificationTypeDef",
     {
         "allowInterrupt": bool,
     },
     total=False,
 )
 
-
 class FulfillmentUpdateResponseSpecificationTypeDef(
     _RequiredFulfillmentUpdateResponseSpecificationTypeDef,
     _OptionalFulfillmentUpdateResponseSpecificationTypeDef,
 ):
     pass
 
-
 _RequiredPromptSpecificationTypeDef = TypedDict(
     "_RequiredPromptSpecificationTypeDef",
     {
         "messageGroups": Sequence[MessageGroupTypeDef],
         "maxRetries": int,
     },
 )
@@ -3631,42 +4528,38 @@
         "promptAttemptsSpecification": Mapping[
             PromptAttemptType, PromptAttemptSpecificationTypeDef
         ],
     },
     total=False,
 )
 
-
 class PromptSpecificationTypeDef(
     _RequiredPromptSpecificationTypeDef, _OptionalPromptSpecificationTypeDef
 ):
     pass
 
-
 _RequiredResponseSpecificationTypeDef = TypedDict(
     "_RequiredResponseSpecificationTypeDef",
     {
         "messageGroups": Sequence[MessageGroupTypeDef],
     },
 )
 _OptionalResponseSpecificationTypeDef = TypedDict(
     "_OptionalResponseSpecificationTypeDef",
     {
         "allowInterrupt": bool,
     },
     total=False,
 )
 
-
 class ResponseSpecificationTypeDef(
     _RequiredResponseSpecificationTypeDef, _OptionalResponseSpecificationTypeDef
 ):
     pass
 
-
 _RequiredStillWaitingResponseSpecificationTypeDef = TypedDict(
     "_RequiredStillWaitingResponseSpecificationTypeDef",
     {
         "messageGroups": Sequence[MessageGroupTypeDef],
         "frequencyInSeconds": int,
         "timeoutInSeconds": int,
     },
@@ -3675,22 +4568,20 @@
     "_OptionalStillWaitingResponseSpecificationTypeDef",
     {
         "allowInterrupt": bool,
     },
     total=False,
 )
 
-
 class StillWaitingResponseSpecificationTypeDef(
     _RequiredStillWaitingResponseSpecificationTypeDef,
     _OptionalStillWaitingResponseSpecificationTypeDef,
 ):
     pass
 
-
 _RequiredCreateBotAliasRequestRequestTypeDef = TypedDict(
     "_RequiredCreateBotAliasRequestRequestTypeDef",
     {
         "botAliasName": str,
         "botId": str,
     },
 )
@@ -3703,36 +4594,34 @@
         "conversationLogSettings": ConversationLogSettingsTypeDef,
         "sentimentAnalysisSettings": SentimentAnalysisSettingsTypeDef,
         "tags": Mapping[str, str],
     },
     total=False,
 )
 
-
 class CreateBotAliasRequestRequestTypeDef(
     _RequiredCreateBotAliasRequestRequestTypeDef, _OptionalCreateBotAliasRequestRequestTypeDef
 ):
     pass
 
-
 CreateBotAliasResponseTypeDef = TypedDict(
     "CreateBotAliasResponseTypeDef",
     {
         "botAliasId": str,
         "botAliasName": str,
         "description": str,
         "botVersion": str,
         "botAliasLocaleSettings": Dict[str, BotAliasLocaleSettingsTypeDef],
         "conversationLogSettings": ConversationLogSettingsTypeDef,
         "sentimentAnalysisSettings": SentimentAnalysisSettingsTypeDef,
         "botAliasStatus": BotAliasStatusType,
         "botId": str,
         "creationDateTime": datetime,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeBotAliasResponseTypeDef = TypedDict(
     "DescribeBotAliasResponseTypeDef",
     {
         "botAliasId": str,
@@ -3744,15 +4633,15 @@
         "sentimentAnalysisSettings": SentimentAnalysisSettingsTypeDef,
         "botAliasHistoryEvents": List[BotAliasHistoryEventTypeDef],
         "botAliasStatus": BotAliasStatusType,
         "botId": str,
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
         "parentBotNetworks": List[ParentBotNetworkTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateBotAliasRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateBotAliasRequestRequestTypeDef",
     {
         "botAliasId": str,
@@ -3768,47 +4657,63 @@
         "botAliasLocaleSettings": Mapping[str, BotAliasLocaleSettingsTypeDef],
         "conversationLogSettings": ConversationLogSettingsTypeDef,
         "sentimentAnalysisSettings": SentimentAnalysisSettingsTypeDef,
     },
     total=False,
 )
 
-
 class UpdateBotAliasRequestRequestTypeDef(
     _RequiredUpdateBotAliasRequestRequestTypeDef, _OptionalUpdateBotAliasRequestRequestTypeDef
 ):
     pass
 
-
 UpdateBotAliasResponseTypeDef = TypedDict(
     "UpdateBotAliasResponseTypeDef",
     {
         "botAliasId": str,
         "botAliasName": str,
         "description": str,
         "botVersion": str,
         "botAliasLocaleSettings": Dict[str, BotAliasLocaleSettingsTypeDef],
         "conversationLogSettings": ConversationLogSettingsTypeDef,
         "sentimentAnalysisSettings": SentimentAnalysisSettingsTypeDef,
         "botAliasStatus": BotAliasStatusType,
         "botId": str,
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TranscriptSourceSettingTypeDef = TypedDict(
     "TranscriptSourceSettingTypeDef",
     {
         "s3BucketTranscriptSource": S3BucketTranscriptSourceTypeDef,
     },
     total=False,
 )
 
+TestSetTurnResultTypeDef = TypedDict(
+    "TestSetTurnResultTypeDef",
+    {
+        "agent": AgentTurnResultTypeDef,
+        "user": UserTurnResultTypeDef,
+    },
+    total=False,
+)
+
+TurnSpecificationTypeDef = TypedDict(
+    "TurnSpecificationTypeDef",
+    {
+        "agentTurn": AgentTurnSpecificationTypeDef,
+        "userTurn": UserTurnSpecificationTypeDef,
+    },
+    total=False,
+)
+
 _RequiredFulfillmentUpdatesSpecificationTypeDef = TypedDict(
     "_RequiredFulfillmentUpdatesSpecificationTypeDef",
     {
         "active": bool,
     },
 )
 _OptionalFulfillmentUpdatesSpecificationTypeDef = TypedDict(
@@ -3817,21 +4722,19 @@
         "startResponse": FulfillmentStartResponseSpecificationTypeDef,
         "updateResponse": FulfillmentUpdateResponseSpecificationTypeDef,
         "timeoutInSeconds": int,
     },
     total=False,
 )
 
-
 class FulfillmentUpdatesSpecificationTypeDef(
     _RequiredFulfillmentUpdatesSpecificationTypeDef, _OptionalFulfillmentUpdatesSpecificationTypeDef
 ):
     pass
 
-
 SlotSummaryTypeDef = TypedDict(
     "SlotSummaryTypeDef",
     {
         "slotId": str,
         "slotName": str,
         "description": str,
         "slotConstraint": SlotConstraintType,
@@ -3854,21 +4757,19 @@
     "_OptionalConditionalBranchTypeDef",
     {
         "response": ResponseSpecificationTypeDef,
     },
     total=False,
 )
 
-
 class ConditionalBranchTypeDef(
     _RequiredConditionalBranchTypeDef, _OptionalConditionalBranchTypeDef
 ):
     pass
 
-
 DefaultConditionalBranchTypeDef = TypedDict(
     "DefaultConditionalBranchTypeDef",
     {
         "nextStep": DialogStateTypeDef,
         "response": ResponseSpecificationTypeDef,
     },
     total=False,
@@ -3886,36 +4787,34 @@
     {
         "stillWaitingResponse": StillWaitingResponseSpecificationTypeDef,
         "active": bool,
     },
     total=False,
 )
 
-
 class WaitAndContinueSpecificationTypeDef(
     _RequiredWaitAndContinueSpecificationTypeDef, _OptionalWaitAndContinueSpecificationTypeDef
 ):
     pass
 
-
 DescribeBotRecommendationResponseTypeDef = TypedDict(
     "DescribeBotRecommendationResponseTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
         "botRecommendationStatus": BotRecommendationStatusType,
         "botRecommendationId": str,
         "failureReasons": List[str],
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
         "transcriptSourceSetting": TranscriptSourceSettingTypeDef,
         "encryptionSetting": EncryptionSettingTypeDef,
         "botRecommendationResults": BotRecommendationResultsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStartBotRecommendationRequestRequestTypeDef = TypedDict(
     "_RequiredStartBotRecommendationRequestRequestTypeDef",
     {
         "botId": str,
@@ -3928,34 +4827,32 @@
     "_OptionalStartBotRecommendationRequestRequestTypeDef",
     {
         "encryptionSetting": EncryptionSettingTypeDef,
     },
     total=False,
 )
 
-
 class StartBotRecommendationRequestRequestTypeDef(
     _RequiredStartBotRecommendationRequestRequestTypeDef,
     _OptionalStartBotRecommendationRequestRequestTypeDef,
 ):
     pass
 
-
 StartBotRecommendationResponseTypeDef = TypedDict(
     "StartBotRecommendationResponseTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
         "botRecommendationStatus": BotRecommendationStatusType,
         "botRecommendationId": str,
         "creationDateTime": datetime,
         "transcriptSourceSetting": TranscriptSourceSettingTypeDef,
         "encryptionSetting": EncryptionSettingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateBotRecommendationResponseTypeDef = TypedDict(
     "UpdateBotRecommendationResponseTypeDef",
     {
         "botId": str,
@@ -3963,28 +4860,69 @@
         "localeId": str,
         "botRecommendationStatus": BotRecommendationStatusType,
         "botRecommendationId": str,
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
         "transcriptSourceSetting": TranscriptSourceSettingTypeDef,
         "encryptionSetting": EncryptionSettingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredUtteranceLevelTestResultItemTypeDef = TypedDict(
+    "_RequiredUtteranceLevelTestResultItemTypeDef",
+    {
+        "recordNumber": int,
+        "turnResult": TestSetTurnResultTypeDef,
+    },
+)
+_OptionalUtteranceLevelTestResultItemTypeDef = TypedDict(
+    "_OptionalUtteranceLevelTestResultItemTypeDef",
+    {
+        "conversationId": str,
+    },
+    total=False,
+)
+
+class UtteranceLevelTestResultItemTypeDef(
+    _RequiredUtteranceLevelTestResultItemTypeDef, _OptionalUtteranceLevelTestResultItemTypeDef
+):
+    pass
+
+_RequiredTestSetTurnRecordTypeDef = TypedDict(
+    "_RequiredTestSetTurnRecordTypeDef",
+    {
+        "recordNumber": int,
+        "turnSpecification": TurnSpecificationTypeDef,
+    },
+)
+_OptionalTestSetTurnRecordTypeDef = TypedDict(
+    "_OptionalTestSetTurnRecordTypeDef",
+    {
+        "conversationId": str,
+        "turnNumber": int,
     },
+    total=False,
 )
 
+class TestSetTurnRecordTypeDef(
+    _RequiredTestSetTurnRecordTypeDef, _OptionalTestSetTurnRecordTypeDef
+):
+    pass
+
 ListSlotsResponseTypeDef = TypedDict(
     "ListSlotsResponseTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
         "intentId": str,
         "slotSummaries": List[SlotSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ConditionalSpecificationTypeDef = TypedDict(
     "ConditionalSpecificationTypeDef",
     {
         "active": bool,
@@ -4005,20 +4943,34 @@
         "defaultValueSpecification": SlotDefaultValueSpecificationTypeDef,
         "sampleUtterances": Sequence[SampleUtteranceTypeDef],
         "waitAndContinueSpecification": WaitAndContinueSpecificationTypeDef,
     },
     total=False,
 )
 
-
 class SubSlotValueElicitationSettingTypeDef(
     _RequiredSubSlotValueElicitationSettingTypeDef, _OptionalSubSlotValueElicitationSettingTypeDef
 ):
     pass
 
+UtteranceLevelTestResultsTypeDef = TypedDict(
+    "UtteranceLevelTestResultsTypeDef",
+    {
+        "items": List[UtteranceLevelTestResultItemTypeDef],
+    },
+)
+
+ListTestSetRecordsResponseTypeDef = TypedDict(
+    "ListTestSetRecordsResponseTypeDef",
+    {
+        "testSetRecords": List[TestSetTurnRecordTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 IntentClosingSettingTypeDef = TypedDict(
     "IntentClosingSettingTypeDef",
     {
         "closingResponse": ResponseSpecificationTypeDef,
         "active": bool,
         "nextStep": DialogStateTypeDef,
@@ -4063,14 +5015,26 @@
     "SpecificationsTypeDef",
     {
         "slotTypeId": str,
         "valueElicitationSetting": SubSlotValueElicitationSettingTypeDef,
     },
 )
 
+TestExecutionResultItemsTypeDef = TypedDict(
+    "TestExecutionResultItemsTypeDef",
+    {
+        "overallTestResults": OverallTestResultsTypeDef,
+        "conversationLevelTestResults": ConversationLevelTestResultsTypeDef,
+        "intentClassificationTestResults": IntentClassificationTestResultsTypeDef,
+        "intentLevelSlotResolutionTestResults": IntentLevelSlotResolutionTestResultsTypeDef,
+        "utteranceLevelTestResults": UtteranceLevelTestResultsTypeDef,
+    },
+    total=False,
+)
+
 _RequiredDialogCodeHookInvocationSettingTypeDef = TypedDict(
     "_RequiredDialogCodeHookInvocationSettingTypeDef",
     {
         "enableCodeHookInvocation": bool,
         "active": bool,
         "postCodeHookSpecification": PostDialogCodeHookInvocationSpecificationTypeDef,
     },
@@ -4079,21 +5043,19 @@
     "_OptionalDialogCodeHookInvocationSettingTypeDef",
     {
         "invocationLabel": str,
     },
     total=False,
 )
 
-
 class DialogCodeHookInvocationSettingTypeDef(
     _RequiredDialogCodeHookInvocationSettingTypeDef, _OptionalDialogCodeHookInvocationSettingTypeDef
 ):
     pass
 
-
 _RequiredFulfillmentCodeHookSettingsTypeDef = TypedDict(
     "_RequiredFulfillmentCodeHookSettingsTypeDef",
     {
         "enabled": bool,
     },
 )
 _OptionalFulfillmentCodeHookSettingsTypeDef = TypedDict(
@@ -4102,30 +5064,37 @@
         "postFulfillmentStatusSpecification": PostFulfillmentStatusSpecificationTypeDef,
         "fulfillmentUpdatesSpecification": FulfillmentUpdatesSpecificationTypeDef,
         "active": bool,
     },
     total=False,
 )
 
-
 class FulfillmentCodeHookSettingsTypeDef(
     _RequiredFulfillmentCodeHookSettingsTypeDef, _OptionalFulfillmentCodeHookSettingsTypeDef
 ):
     pass
 
-
 SubSlotSettingTypeDef = TypedDict(
     "SubSlotSettingTypeDef",
     {
         "expression": str,
         "slotSpecifications": Mapping[str, SpecificationsTypeDef],
     },
     total=False,
 )
 
+ListTestExecutionResultItemsResponseTypeDef = TypedDict(
+    "ListTestExecutionResultItemsResponseTypeDef",
+    {
+        "testExecutionResults": TestExecutionResultItemsTypeDef,
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 InitialResponseSettingTypeDef = TypedDict(
     "InitialResponseSettingTypeDef",
     {
         "initialResponse": ResponseSpecificationTypeDef,
         "nextStep": DialogStateTypeDef,
         "conditional": ConditionalSpecificationTypeDef,
         "codeHook": DialogCodeHookInvocationSettingTypeDef,
@@ -4154,21 +5123,19 @@
         "failureConditional": ConditionalSpecificationTypeDef,
         "codeHook": DialogCodeHookInvocationSettingTypeDef,
         "elicitationCodeHook": ElicitationCodeHookInvocationSettingTypeDef,
     },
     total=False,
 )
 
-
 class IntentConfirmationSettingTypeDef(
     _RequiredIntentConfirmationSettingTypeDef, _OptionalIntentConfirmationSettingTypeDef
 ):
     pass
 
-
 SlotCaptureSettingTypeDef = TypedDict(
     "SlotCaptureSettingTypeDef",
     {
         "captureResponse": ResponseSpecificationTypeDef,
         "captureNextStep": DialogStateTypeDef,
         "captureConditional": ConditionalSpecificationTypeDef,
         "failureResponse": ResponseSpecificationTypeDef,
@@ -4203,21 +5170,19 @@
         "outputContexts": Sequence[OutputContextTypeDef],
         "kendraConfiguration": KendraConfigurationTypeDef,
         "initialResponseSetting": InitialResponseSettingTypeDef,
     },
     total=False,
 )
 
-
 class CreateIntentRequestRequestTypeDef(
     _RequiredCreateIntentRequestRequestTypeDef, _OptionalCreateIntentRequestRequestTypeDef
 ):
     pass
 
-
 CreateIntentResponseTypeDef = TypedDict(
     "CreateIntentResponseTypeDef",
     {
         "intentId": str,
         "intentName": str,
         "description": str,
         "parentIntentSignature": str,
@@ -4230,15 +5195,15 @@
         "outputContexts": List[OutputContextTypeDef],
         "kendraConfiguration": KendraConfigurationTypeDef,
         "botId": str,
         "botVersion": str,
         "localeId": str,
         "creationDateTime": datetime,
         "initialResponseSetting": InitialResponseSettingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeIntentResponseTypeDef = TypedDict(
     "DescribeIntentResponseTypeDef",
     {
         "intentId": str,
@@ -4256,15 +5221,15 @@
         "kendraConfiguration": KendraConfigurationTypeDef,
         "botId": str,
         "botVersion": str,
         "localeId": str,
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
         "initialResponseSetting": InitialResponseSettingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateIntentRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateIntentRequestRequestTypeDef",
     {
         "intentId": str,
@@ -4289,21 +5254,19 @@
         "outputContexts": Sequence[OutputContextTypeDef],
         "kendraConfiguration": KendraConfigurationTypeDef,
         "initialResponseSetting": InitialResponseSettingTypeDef,
     },
     total=False,
 )
 
-
 class UpdateIntentRequestRequestTypeDef(
     _RequiredUpdateIntentRequestRequestTypeDef, _OptionalUpdateIntentRequestRequestTypeDef
 ):
     pass
 
-
 UpdateIntentResponseTypeDef = TypedDict(
     "UpdateIntentResponseTypeDef",
     {
         "intentId": str,
         "intentName": str,
         "description": str,
         "parentIntentSignature": str,
@@ -4318,15 +5281,15 @@
         "kendraConfiguration": KendraConfigurationTypeDef,
         "botId": str,
         "botVersion": str,
         "localeId": str,
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
         "initialResponseSetting": InitialResponseSettingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSlotValueElicitationSettingTypeDef = TypedDict(
     "_RequiredSlotValueElicitationSettingTypeDef",
     {
         "slotConstraint": SlotConstraintType,
@@ -4340,21 +5303,19 @@
         "sampleUtterances": Sequence[SampleUtteranceTypeDef],
         "waitAndContinueSpecification": WaitAndContinueSpecificationTypeDef,
         "slotCaptureSetting": SlotCaptureSettingTypeDef,
     },
     total=False,
 )
 
-
 class SlotValueElicitationSettingTypeDef(
     _RequiredSlotValueElicitationSettingTypeDef, _OptionalSlotValueElicitationSettingTypeDef
 ):
     pass
 
-
 _RequiredCreateSlotRequestRequestTypeDef = TypedDict(
     "_RequiredCreateSlotRequestRequestTypeDef",
     {
         "slotName": str,
         "valueElicitationSetting": SlotValueElicitationSettingTypeDef,
         "botId": str,
         "botVersion": str,
@@ -4370,21 +5331,19 @@
         "obfuscationSetting": ObfuscationSettingTypeDef,
         "multipleValuesSetting": MultipleValuesSettingTypeDef,
         "subSlotSetting": SubSlotSettingTypeDef,
     },
     total=False,
 )
 
-
 class CreateSlotRequestRequestTypeDef(
     _RequiredCreateSlotRequestRequestTypeDef, _OptionalCreateSlotRequestRequestTypeDef
 ):
     pass
 
-
 CreateSlotResponseTypeDef = TypedDict(
     "CreateSlotResponseTypeDef",
     {
         "slotId": str,
         "slotName": str,
         "description": str,
         "slotTypeId": str,
@@ -4393,15 +5352,15 @@
         "botId": str,
         "botVersion": str,
         "localeId": str,
         "intentId": str,
         "creationDateTime": datetime,
         "multipleValuesSetting": MultipleValuesSettingTypeDef,
         "subSlotSetting": SubSlotSettingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSlotResponseTypeDef = TypedDict(
     "DescribeSlotResponseTypeDef",
     {
         "slotId": str,
@@ -4414,15 +5373,15 @@
         "botVersion": str,
         "localeId": str,
         "intentId": str,
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
         "multipleValuesSetting": MultipleValuesSettingTypeDef,
         "subSlotSetting": SubSlotSettingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateSlotRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateSlotRequestRequestTypeDef",
     {
         "slotId": str,
@@ -4442,21 +5401,19 @@
         "obfuscationSetting": ObfuscationSettingTypeDef,
         "multipleValuesSetting": MultipleValuesSettingTypeDef,
         "subSlotSetting": SubSlotSettingTypeDef,
     },
     total=False,
 )
 
-
 class UpdateSlotRequestRequestTypeDef(
     _RequiredUpdateSlotRequestRequestTypeDef, _OptionalUpdateSlotRequestRequestTypeDef
 ):
     pass
 
-
 UpdateSlotResponseTypeDef = TypedDict(
     "UpdateSlotResponseTypeDef",
     {
         "slotId": str,
         "slotName": str,
         "description": str,
         "slotTypeId": str,
@@ -4466,10 +5423,10 @@
         "botVersion": str,
         "localeId": str,
         "intentId": str,
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
         "multipleValuesSetting": MultipleValuesSettingTypeDef,
         "subSlotSetting": SubSlotSettingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-lexv2-models-2.5.0.post1/types_aiobotocore_lexv2_models/type_defs.pyi` & `types-aiobotocore-lexv2-models-2.5.1/types_aiobotocore_lexv2_models/type_defs.py`

 * *Files 10% similar despite different names*

```diff
@@ -2,17 +2,17 @@
 Type annotations for lexv2-models service type definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lexv2_models/type_defs/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_lexv2_models.type_defs import AdvancedRecognitionSettingTypeDef
+    from types_aiobotocore_lexv2_models.type_defs import ActiveContextTypeDef
 
-    data: AdvancedRecognitionSettingTypeDef = {...}
+    data: ActiveContextTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
 from typing import Any, Dict, List, Mapping, Sequence
 
 from .literals import (
@@ -23,14 +23,15 @@
     BotFilterNameType,
     BotFilterOperatorType,
     BotLocaleFilterOperatorType,
     BotLocaleStatusType,
     BotRecommendationStatusType,
     BotStatusType,
     BotTypeType,
+    ConversationLogsInputModeFilterType,
     CustomVocabularyStatusType,
     DialogActionTypeType,
     EffectType,
     ErrorCodeType,
     ExportFilterOperatorType,
     ExportStatusType,
     ImportExportFileFormatType,
@@ -50,45 +51,60 @@
     SlotSortAttributeType,
     SlotTypeCategoryType,
     SlotTypeFilterNameType,
     SlotTypeFilterOperatorType,
     SlotTypeSortAttributeType,
     SlotValueResolutionStrategyType,
     SortOrderType,
+    TestExecutionApiModeType,
+    TestExecutionModalityType,
+    TestExecutionSortAttributeType,
+    TestExecutionStatusType,
+    TestResultMatchStatusType,
+    TestResultTypeFilterType,
+    TestSetDiscrepancyReportStatusType,
+    TestSetGenerationStatusType,
+    TestSetModalityType,
+    TestSetSortAttributeType,
+    TestSetStatusType,
     TimeDimensionType,
     VoiceEngineType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
+    "ActiveContextTypeDef",
     "AdvancedRecognitionSettingTypeDef",
+    "ExecutionErrorDetailsTypeDef",
+    "AgentTurnSpecificationTypeDef",
     "AggregatedUtterancesFilterTypeDef",
     "AggregatedUtterancesSortByTypeDef",
     "AggregatedUtterancesSummaryTypeDef",
     "AllowedInputTypesTypeDef",
     "AssociatedTranscriptFilterTypeDef",
     "AssociatedTranscriptTypeDef",
     "AudioSpecificationTypeDef",
     "DTMFSpecificationTypeDef",
     "S3BucketLogDestinationTypeDef",
     "NewCustomVocabularyItemTypeDef",
     "CustomVocabularyItemTypeDef",
     "FailedCustomVocabularyItemTypeDef",
-    "ResponseMetadataTypeDef",
     "CustomVocabularyEntryIdTypeDef",
     "BotAliasHistoryEventTypeDef",
     "BotAliasSummaryTypeDef",
+    "BotAliasTestExecutionTargetTypeDef",
     "BotExportSpecificationTypeDef",
     "BotFilterTypeDef",
     "DataPrivacyTypeDef",
     "BotLocaleExportSpecificationTypeDef",
     "BotLocaleFilterTypeDef",
     "BotLocaleHistoryEventTypeDef",
     "VoiceSettingsTypeDef",
@@ -100,133 +116,166 @@
     "BotRecommendationSummaryTypeDef",
     "BotSortByTypeDef",
     "BotSummaryTypeDef",
     "BotVersionLocaleDetailsTypeDef",
     "BotVersionSortByTypeDef",
     "BotVersionSummaryTypeDef",
     "BuildBotLocaleRequestRequestTypeDef",
+    "BuildBotLocaleResponseTypeDef",
     "BuiltInIntentSortByTypeDef",
     "BuiltInIntentSummaryTypeDef",
     "BuiltInSlotTypeSortByTypeDef",
     "BuiltInSlotTypeSummaryTypeDef",
     "ButtonTypeDef",
     "CloudWatchLogGroupLogDestinationTypeDef",
     "LambdaCodeHookTypeDef",
     "SubSlotTypeCompositionTypeDef",
     "ConditionTypeDef",
+    "ConversationLevelIntentClassificationResultItemTypeDef",
+    "ConversationLevelResultDetailTypeDef",
+    "ConversationLevelSlotResolutionResultItemTypeDef",
+    "ConversationLevelTestResultsFilterByTypeDef",
+    "ConversationLogsDataSourceFilterByTypeDef",
     "SentimentAnalysisSettingsTypeDef",
     "DialogCodeHookSettingsTypeDef",
     "InputContextTypeDef",
     "KendraConfigurationTypeDef",
     "OutputContextTypeDef",
     "SampleUtteranceTypeDef",
     "CreateResourcePolicyRequestRequestTypeDef",
+    "CreateResourcePolicyResponseTypeDef",
     "PrincipalTypeDef",
+    "CreateResourcePolicyStatementResponseTypeDef",
     "MultipleValuesSettingTypeDef",
     "ObfuscationSettingTypeDef",
+    "CreateUploadUrlResponseTypeDef",
     "CustomPayloadTypeDef",
     "CustomVocabularyExportSpecificationTypeDef",
     "CustomVocabularyImportSpecificationTypeDef",
     "DateRangeFilterTypeDef",
     "DeleteBotAliasRequestRequestTypeDef",
+    "DeleteBotAliasResponseTypeDef",
     "DeleteBotLocaleRequestRequestTypeDef",
+    "DeleteBotLocaleResponseTypeDef",
     "DeleteBotRequestRequestTypeDef",
+    "DeleteBotResponseTypeDef",
     "DeleteBotVersionRequestRequestTypeDef",
+    "DeleteBotVersionResponseTypeDef",
     "DeleteCustomVocabularyRequestRequestTypeDef",
+    "DeleteCustomVocabularyResponseTypeDef",
     "DeleteExportRequestRequestTypeDef",
+    "DeleteExportResponseTypeDef",
     "DeleteImportRequestRequestTypeDef",
+    "DeleteImportResponseTypeDef",
     "DeleteIntentRequestRequestTypeDef",
     "DeleteResourcePolicyRequestRequestTypeDef",
+    "DeleteResourcePolicyResponseTypeDef",
     "DeleteResourcePolicyStatementRequestRequestTypeDef",
+    "DeleteResourcePolicyStatementResponseTypeDef",
     "DeleteSlotRequestRequestTypeDef",
     "DeleteSlotTypeRequestRequestTypeDef",
+    "DeleteTestSetRequestRequestTypeDef",
     "DeleteUtterancesRequestRequestTypeDef",
     "WaiterConfigTypeDef",
     "DescribeBotAliasRequestRequestTypeDef",
     "ParentBotNetworkTypeDef",
     "DescribeBotLocaleRequestRequestTypeDef",
     "DescribeBotRecommendationRequestRequestTypeDef",
     "EncryptionSettingTypeDef",
     "DescribeBotRequestRequestTypeDef",
     "DescribeBotVersionRequestRequestTypeDef",
     "DescribeCustomVocabularyMetadataRequestRequestTypeDef",
+    "DescribeCustomVocabularyMetadataResponseTypeDef",
     "DescribeExportRequestRequestTypeDef",
     "DescribeImportRequestRequestTypeDef",
     "DescribeIntentRequestRequestTypeDef",
     "SlotPriorityTypeDef",
     "DescribeResourcePolicyRequestRequestTypeDef",
+    "DescribeResourcePolicyResponseTypeDef",
     "DescribeSlotRequestRequestTypeDef",
     "DescribeSlotTypeRequestRequestTypeDef",
+    "DescribeTestExecutionRequestRequestTypeDef",
+    "DescribeTestSetDiscrepancyReportRequestRequestTypeDef",
+    "DescribeTestSetGenerationRequestRequestTypeDef",
+    "TestSetStorageLocationTypeDef",
+    "DescribeTestSetRequestRequestTypeDef",
     "DialogActionTypeDef",
     "IntentOverrideTypeDef",
     "ElicitationCodeHookInvocationSettingTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "ExportFilterTypeDef",
+    "TestSetExportSpecificationTypeDef",
     "ExportSortByTypeDef",
+    "GetTestExecutionArtifactsUrlRequestRequestTypeDef",
+    "GetTestExecutionArtifactsUrlResponseTypeDef",
     "GrammarSlotTypeSourceTypeDef",
     "ImportFilterTypeDef",
     "ImportSortByTypeDef",
     "ImportSummaryTypeDef",
+    "RuntimeHintsTypeDef",
+    "IntentClassificationTestResultItemCountsTypeDef",
     "IntentFilterTypeDef",
     "IntentSortByTypeDef",
     "ListBotAliasesRequestRequestTypeDef",
     "ListBotRecommendationsRequestRequestTypeDef",
     "ListCustomVocabularyItemsRequestRequestTypeDef",
     "ListRecommendedIntentsRequestRequestTypeDef",
     "RecommendedIntentSummaryTypeDef",
     "SlotTypeFilterTypeDef",
     "SlotTypeSortByTypeDef",
     "SlotTypeSummaryTypeDef",
     "SlotFilterTypeDef",
     "SlotSortByTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "TestExecutionSortByTypeDef",
+    "ListTestSetRecordsRequestRequestTypeDef",
+    "TestSetSortByTypeDef",
     "PlainTextMessageTypeDef",
     "SSMLMessageTypeDef",
+    "OverallTestResultItemTypeDef",
     "PathFormatTypeDef",
     "TextInputSpecificationTypeDef",
     "RelativeAggregationDurationTypeDef",
+    "ResponseMetadataTypeDef",
+    "RuntimeHintValueTypeDef",
     "SampleValueTypeDef",
     "SlotDefaultValueTypeDef",
+    "SlotResolutionTestResultItemCountsTypeDef",
     "SlotValueTypeDef",
     "SlotValueRegexFilterTypeDef",
     "StopBotRecommendationRequestRequestTypeDef",
+    "StopBotRecommendationResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
+    "TestSetIntentDiscrepancyItemTypeDef",
+    "TestSetSlotDiscrepancyItemTypeDef",
+    "TestSetDiscrepancyReportBotAliasTargetTypeDef",
+    "TestSetImportInputLocationTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateExportRequestRequestTypeDef",
     "UpdateResourcePolicyRequestRequestTypeDef",
+    "UpdateResourcePolicyResponseTypeDef",
+    "UpdateTestSetRequestRequestTypeDef",
+    "UserTurnIntentOutputTypeDef",
+    "UserTurnSlotOutputTypeDef",
+    "UtteranceAudioInputSpecificationTypeDef",
+    "AgentTurnResultTypeDef",
     "SearchAssociatedTranscriptsRequestRequestTypeDef",
+    "SearchAssociatedTranscriptsResponseTypeDef",
     "AudioAndDTMFInputSpecificationTypeDef",
     "AudioLogDestinationTypeDef",
     "BatchCreateCustomVocabularyItemRequestRequestTypeDef",
     "BatchUpdateCustomVocabularyItemRequestRequestTypeDef",
+    "ListCustomVocabularyItemsResponseTypeDef",
     "BatchCreateCustomVocabularyItemResponseTypeDef",
     "BatchDeleteCustomVocabularyItemResponseTypeDef",
     "BatchUpdateCustomVocabularyItemResponseTypeDef",
-    "BuildBotLocaleResponseTypeDef",
-    "CreateResourcePolicyResponseTypeDef",
-    "CreateResourcePolicyStatementResponseTypeDef",
-    "CreateUploadUrlResponseTypeDef",
-    "DeleteBotAliasResponseTypeDef",
-    "DeleteBotLocaleResponseTypeDef",
-    "DeleteBotResponseTypeDef",
-    "DeleteBotVersionResponseTypeDef",
-    "DeleteCustomVocabularyResponseTypeDef",
-    "DeleteExportResponseTypeDef",
-    "DeleteImportResponseTypeDef",
-    "DeleteResourcePolicyResponseTypeDef",
-    "DeleteResourcePolicyStatementResponseTypeDef",
-    "DescribeCustomVocabularyMetadataResponseTypeDef",
-    "DescribeResourcePolicyResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ListCustomVocabularyItemsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "SearchAssociatedTranscriptsResponseTypeDef",
-    "StopBotRecommendationResponseTypeDef",
-    "UpdateResourcePolicyResponseTypeDef",
     "BatchDeleteCustomVocabularyItemRequestRequestTypeDef",
     "ListBotAliasesResponseTypeDef",
+    "TestExecutionTargetTypeDef",
     "BotImportSpecificationTypeDef",
     "BotLocaleImportSpecificationTypeDef",
     "CreateBotLocaleRequestRequestTypeDef",
     "CreateBotLocaleResponseTypeDef",
     "DescribeBotLocaleResponseTypeDef",
     "UpdateBotLocaleRequestRequestTypeDef",
     "UpdateBotLocaleResponseTypeDef",
@@ -249,102 +298,149 @@
     "ListBuiltInIntentsResponseTypeDef",
     "ListBuiltInSlotTypesRequestRequestTypeDef",
     "ListBuiltInSlotTypesResponseTypeDef",
     "ImageResponseCardTypeDef",
     "TextLogDestinationTypeDef",
     "CodeHookSpecificationTypeDef",
     "CompositeSlotTypeSettingTypeDef",
+    "ConversationLevelTestResultItemTypeDef",
+    "TestExecutionResultFilterByTypeDef",
+    "ConversationLogsDataSourceTypeDef",
     "IntentSummaryTypeDef",
     "CreateResourcePolicyStatementRequestRequestTypeDef",
-    "ExportResourceSpecificationTypeDef",
     "LexTranscriptFilterTypeDef",
     "DescribeBotAliasRequestBotAliasAvailableWaitTypeDef",
     "DescribeBotLocaleRequestBotLocaleBuiltWaitTypeDef",
     "DescribeBotLocaleRequestBotLocaleCreatedWaitTypeDef",
     "DescribeBotLocaleRequestBotLocaleExpressTestingAvailableWaitTypeDef",
     "DescribeBotRequestBotAvailableWaitTypeDef",
     "DescribeBotVersionRequestBotVersionAvailableWaitTypeDef",
     "DescribeExportRequestBotExportCompletedWaitTypeDef",
     "DescribeImportRequestBotImportCompletedWaitTypeDef",
     "DescribeBotVersionResponseTypeDef",
     "UpdateBotRecommendationRequestRequestTypeDef",
+    "DescribeTestSetResponseTypeDef",
+    "TestSetSummaryTypeDef",
+    "UpdateTestSetResponseTypeDef",
     "DialogStateTypeDef",
+    "ExportResourceSpecificationTypeDef",
     "ListExportsRequestRequestTypeDef",
     "GrammarSlotTypeSettingTypeDef",
     "ListImportsRequestRequestTypeDef",
     "ListImportsResponseTypeDef",
+    "InputSessionStateSpecificationTypeDef",
+    "IntentClassificationTestResultItemTypeDef",
     "ListIntentsRequestRequestTypeDef",
     "ListRecommendedIntentsResponseTypeDef",
     "ListSlotTypesRequestRequestTypeDef",
     "ListSlotTypesResponseTypeDef",
     "ListSlotsRequestRequestTypeDef",
+    "ListTestExecutionsRequestRequestTypeDef",
+    "ListTestSetsRequestRequestTypeDef",
+    "OverallTestResultsTypeDef",
     "UtteranceAggregationDurationTypeDef",
+    "RuntimeHintDetailsTypeDef",
     "SlotTypeValueTypeDef",
     "SlotDefaultValueSpecificationTypeDef",
+    "SlotResolutionTestResultItemTypeDef",
     "SlotValueOverrideTypeDef",
     "SlotValueSelectionSettingTypeDef",
+    "TestSetDiscrepancyErrorsTypeDef",
+    "TestSetDiscrepancyReportResourceTargetTypeDef",
+    "TestSetImportResourceSpecificationTypeDef",
+    "UserTurnOutputSpecificationTypeDef",
+    "UtteranceInputSpecificationTypeDef",
     "PromptAttemptSpecificationTypeDef",
     "AudioLogSettingTypeDef",
-    "ImportResourceSpecificationTypeDef",
+    "DescribeTestExecutionResponseTypeDef",
+    "StartTestExecutionRequestRequestTypeDef",
+    "StartTestExecutionResponseTypeDef",
+    "TestExecutionSummaryTypeDef",
     "BotRecommendationResultsTypeDef",
     "MessageTypeDef",
     "TextLogSettingTypeDef",
     "BotAliasLocaleSettingsTypeDef",
+    "ConversationLevelTestResultsTypeDef",
+    "ListTestExecutionResultItemsRequestRequestTypeDef",
+    "TestSetGenerationDataSourceTypeDef",
     "ListIntentsResponseTypeDef",
+    "TranscriptFilterTypeDef",
+    "ListTestSetsResponseTypeDef",
     "CreateExportRequestRequestTypeDef",
     "CreateExportResponseTypeDef",
     "DescribeExportResponseTypeDef",
     "ExportSummaryTypeDef",
     "UpdateExportResponseTypeDef",
-    "TranscriptFilterTypeDef",
     "ExternalSourceSettingTypeDef",
+    "IntentClassificationTestResultsTypeDef",
     "ListAggregatedUtterancesRequestRequestTypeDef",
     "ListAggregatedUtterancesResponseTypeDef",
-    "DescribeImportResponseTypeDef",
-    "StartImportRequestRequestTypeDef",
-    "StartImportResponseTypeDef",
+    "IntentLevelSlotResolutionTestResultItemTypeDef",
+    "CreateTestSetDiscrepancyReportRequestRequestTypeDef",
+    "CreateTestSetDiscrepancyReportResponseTypeDef",
+    "DescribeTestSetDiscrepancyReportResponseTypeDef",
+    "ImportResourceSpecificationTypeDef",
+    "UserTurnInputSpecificationTypeDef",
+    "ListTestExecutionsResponseTypeDef",
     "MessageGroupTypeDef",
     "ConversationLogSettingsTypeDef",
-    "ListExportsResponseTypeDef",
+    "DescribeTestSetGenerationResponseTypeDef",
+    "StartTestSetGenerationRequestRequestTypeDef",
+    "StartTestSetGenerationResponseTypeDef",
     "S3BucketTranscriptSourceTypeDef",
+    "ListExportsResponseTypeDef",
     "CreateSlotTypeRequestRequestTypeDef",
     "CreateSlotTypeResponseTypeDef",
     "DescribeSlotTypeResponseTypeDef",
     "UpdateSlotTypeRequestRequestTypeDef",
     "UpdateSlotTypeResponseTypeDef",
+    "IntentLevelSlotResolutionTestResultsTypeDef",
+    "DescribeImportResponseTypeDef",
+    "StartImportRequestRequestTypeDef",
+    "StartImportResponseTypeDef",
+    "UserTurnResultTypeDef",
+    "UserTurnSpecificationTypeDef",
     "FulfillmentStartResponseSpecificationTypeDef",
     "FulfillmentUpdateResponseSpecificationTypeDef",
     "PromptSpecificationTypeDef",
     "ResponseSpecificationTypeDef",
     "StillWaitingResponseSpecificationTypeDef",
     "CreateBotAliasRequestRequestTypeDef",
     "CreateBotAliasResponseTypeDef",
     "DescribeBotAliasResponseTypeDef",
     "UpdateBotAliasRequestRequestTypeDef",
     "UpdateBotAliasResponseTypeDef",
     "TranscriptSourceSettingTypeDef",
+    "TestSetTurnResultTypeDef",
+    "TurnSpecificationTypeDef",
     "FulfillmentUpdatesSpecificationTypeDef",
     "SlotSummaryTypeDef",
     "ConditionalBranchTypeDef",
     "DefaultConditionalBranchTypeDef",
     "WaitAndContinueSpecificationTypeDef",
     "DescribeBotRecommendationResponseTypeDef",
     "StartBotRecommendationRequestRequestTypeDef",
     "StartBotRecommendationResponseTypeDef",
     "UpdateBotRecommendationResponseTypeDef",
+    "UtteranceLevelTestResultItemTypeDef",
+    "TestSetTurnRecordTypeDef",
     "ListSlotsResponseTypeDef",
     "ConditionalSpecificationTypeDef",
     "SubSlotValueElicitationSettingTypeDef",
+    "UtteranceLevelTestResultsTypeDef",
+    "ListTestSetRecordsResponseTypeDef",
     "IntentClosingSettingTypeDef",
     "PostDialogCodeHookInvocationSpecificationTypeDef",
     "PostFulfillmentStatusSpecificationTypeDef",
     "SpecificationsTypeDef",
+    "TestExecutionResultItemsTypeDef",
     "DialogCodeHookInvocationSettingTypeDef",
     "FulfillmentCodeHookSettingsTypeDef",
     "SubSlotSettingTypeDef",
+    "ListTestExecutionResultItemsResponseTypeDef",
     "InitialResponseSettingTypeDef",
     "IntentConfirmationSettingTypeDef",
     "SlotCaptureSettingTypeDef",
     "CreateIntentRequestRequestTypeDef",
     "CreateIntentResponseTypeDef",
     "DescribeIntentResponseTypeDef",
     "UpdateIntentRequestRequestTypeDef",
@@ -353,22 +449,44 @@
     "CreateSlotRequestRequestTypeDef",
     "CreateSlotResponseTypeDef",
     "DescribeSlotResponseTypeDef",
     "UpdateSlotRequestRequestTypeDef",
     "UpdateSlotResponseTypeDef",
 )
 
+ActiveContextTypeDef = TypedDict(
+    "ActiveContextTypeDef",
+    {
+        "name": str,
+    },
+)
+
 AdvancedRecognitionSettingTypeDef = TypedDict(
     "AdvancedRecognitionSettingTypeDef",
     {
         "audioRecognitionStrategy": Literal["UseSlotValuesAsCustomVocabulary"],
     },
     total=False,
 )
 
+ExecutionErrorDetailsTypeDef = TypedDict(
+    "ExecutionErrorDetailsTypeDef",
+    {
+        "errorCode": str,
+        "errorMessage": str,
+    },
+)
+
+AgentTurnSpecificationTypeDef = TypedDict(
+    "AgentTurnSpecificationTypeDef",
+    {
+        "agentPrompt": str,
+    },
+)
+
 AggregatedUtterancesFilterTypeDef = TypedDict(
     "AggregatedUtterancesFilterTypeDef",
     {
         "name": Literal["Utterance"],
         "values": Sequence[str],
         "operator": AggregatedUtterancesFilterOperatorType,
     },
@@ -448,19 +566,21 @@
     "_OptionalS3BucketLogDestinationTypeDef",
     {
         "kmsKeyArn": str,
     },
     total=False,
 )
 
+
 class S3BucketLogDestinationTypeDef(
     _RequiredS3BucketLogDestinationTypeDef, _OptionalS3BucketLogDestinationTypeDef
 ):
     pass
 
+
 _RequiredNewCustomVocabularyItemTypeDef = TypedDict(
     "_RequiredNewCustomVocabularyItemTypeDef",
     {
         "phrase": str,
     },
 )
 _OptionalNewCustomVocabularyItemTypeDef = TypedDict(
@@ -468,19 +588,21 @@
     {
         "weight": int,
         "displayAs": str,
     },
     total=False,
 )
 
+
 class NewCustomVocabularyItemTypeDef(
     _RequiredNewCustomVocabularyItemTypeDef, _OptionalNewCustomVocabularyItemTypeDef
 ):
     pass
 
+
 _RequiredCustomVocabularyItemTypeDef = TypedDict(
     "_RequiredCustomVocabularyItemTypeDef",
     {
         "itemId": str,
         "phrase": str,
     },
 )
@@ -489,40 +611,31 @@
     {
         "weight": int,
         "displayAs": str,
     },
     total=False,
 )
 
+
 class CustomVocabularyItemTypeDef(
     _RequiredCustomVocabularyItemTypeDef, _OptionalCustomVocabularyItemTypeDef
 ):
     pass
 
+
 FailedCustomVocabularyItemTypeDef = TypedDict(
     "FailedCustomVocabularyItemTypeDef",
     {
         "itemId": str,
         "errorMessage": str,
         "errorCode": ErrorCodeType,
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
 CustomVocabularyEntryIdTypeDef = TypedDict(
     "CustomVocabularyEntryIdTypeDef",
     {
         "itemId": str,
     },
 )
 
@@ -546,14 +659,23 @@
         "botAliasStatus": BotAliasStatusType,
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
     },
     total=False,
 )
 
+BotAliasTestExecutionTargetTypeDef = TypedDict(
+    "BotAliasTestExecutionTargetTypeDef",
+    {
+        "botId": str,
+        "botAliasId": str,
+        "localeId": str,
+    },
+)
+
 BotExportSpecificationTypeDef = TypedDict(
     "BotExportSpecificationTypeDef",
     {
         "botId": str,
         "botVersion": str,
     },
 )
@@ -610,17 +732,19 @@
     "_OptionalVoiceSettingsTypeDef",
     {
         "engine": VoiceEngineType,
     },
     total=False,
 )
 
+
 class VoiceSettingsTypeDef(_RequiredVoiceSettingsTypeDef, _OptionalVoiceSettingsTypeDef):
     pass
 
+
 BotLocaleSortByTypeDef = TypedDict(
     "BotLocaleSortByTypeDef",
     {
         "attribute": Literal["BotLocaleName"],
         "order": SortOrderType,
     },
 )
@@ -677,19 +801,21 @@
     {
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
     },
     total=False,
 )
 
+
 class BotRecommendationSummaryTypeDef(
     _RequiredBotRecommendationSummaryTypeDef, _OptionalBotRecommendationSummaryTypeDef
 ):
     pass
 
+
 BotSortByTypeDef = TypedDict(
     "BotSortByTypeDef",
     {
         "attribute": Literal["BotName"],
         "order": SortOrderType,
     },
 )
@@ -740,14 +866,26 @@
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
     },
 )
 
+BuildBotLocaleResponseTypeDef = TypedDict(
+    "BuildBotLocaleResponseTypeDef",
+    {
+        "botId": str,
+        "botVersion": str,
+        "localeId": str,
+        "botLocaleStatus": BotLocaleStatusType,
+        "lastBuildSubmittedDateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 BuiltInIntentSortByTypeDef = TypedDict(
     "BuiltInIntentSortByTypeDef",
     {
         "attribute": Literal["IntentSignature"],
         "order": SortOrderType,
     },
 )
@@ -813,14 +951,69 @@
 ConditionTypeDef = TypedDict(
     "ConditionTypeDef",
     {
         "expressionString": str,
     },
 )
 
+ConversationLevelIntentClassificationResultItemTypeDef = TypedDict(
+    "ConversationLevelIntentClassificationResultItemTypeDef",
+    {
+        "intentName": str,
+        "matchResult": TestResultMatchStatusType,
+    },
+)
+
+_RequiredConversationLevelResultDetailTypeDef = TypedDict(
+    "_RequiredConversationLevelResultDetailTypeDef",
+    {
+        "endToEndResult": TestResultMatchStatusType,
+    },
+)
+_OptionalConversationLevelResultDetailTypeDef = TypedDict(
+    "_OptionalConversationLevelResultDetailTypeDef",
+    {
+        "speechTranscriptionResult": TestResultMatchStatusType,
+    },
+    total=False,
+)
+
+
+class ConversationLevelResultDetailTypeDef(
+    _RequiredConversationLevelResultDetailTypeDef, _OptionalConversationLevelResultDetailTypeDef
+):
+    pass
+
+
+ConversationLevelSlotResolutionResultItemTypeDef = TypedDict(
+    "ConversationLevelSlotResolutionResultItemTypeDef",
+    {
+        "intentName": str,
+        "slotName": str,
+        "matchResult": TestResultMatchStatusType,
+    },
+)
+
+ConversationLevelTestResultsFilterByTypeDef = TypedDict(
+    "ConversationLevelTestResultsFilterByTypeDef",
+    {
+        "endToEndResult": TestResultMatchStatusType,
+    },
+    total=False,
+)
+
+ConversationLogsDataSourceFilterByTypeDef = TypedDict(
+    "ConversationLogsDataSourceFilterByTypeDef",
+    {
+        "startTime": datetime,
+        "endTime": datetime,
+        "inputMode": ConversationLogsInputModeFilterType,
+    },
+)
+
 SentimentAnalysisSettingsTypeDef = TypedDict(
     "SentimentAnalysisSettingsTypeDef",
     {
         "detectSentiment": bool,
     },
 )
 
@@ -849,19 +1042,21 @@
     {
         "queryFilterStringEnabled": bool,
         "queryFilterString": str,
     },
     total=False,
 )
 
+
 class KendraConfigurationTypeDef(
     _RequiredKendraConfigurationTypeDef, _OptionalKendraConfigurationTypeDef
 ):
     pass
 
+
 OutputContextTypeDef = TypedDict(
     "OutputContextTypeDef",
     {
         "name": str,
         "timeToLiveInSeconds": int,
         "turnsToLive": int,
     },
@@ -878,23 +1073,41 @@
     "CreateResourcePolicyRequestRequestTypeDef",
     {
         "resourceArn": str,
         "policy": str,
     },
 )
 
+CreateResourcePolicyResponseTypeDef = TypedDict(
+    "CreateResourcePolicyResponseTypeDef",
+    {
+        "resourceArn": str,
+        "revisionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 PrincipalTypeDef = TypedDict(
     "PrincipalTypeDef",
     {
         "service": str,
         "arn": str,
     },
     total=False,
 )
 
+CreateResourcePolicyStatementResponseTypeDef = TypedDict(
+    "CreateResourcePolicyStatementResponseTypeDef",
+    {
+        "resourceArn": str,
+        "revisionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 MultipleValuesSettingTypeDef = TypedDict(
     "MultipleValuesSettingTypeDef",
     {
         "allowMultipleValues": bool,
     },
     total=False,
 )
@@ -902,14 +1115,23 @@
 ObfuscationSettingTypeDef = TypedDict(
     "ObfuscationSettingTypeDef",
     {
         "obfuscationSettingType": ObfuscationSettingTypeType,
     },
 )
 
+CreateUploadUrlResponseTypeDef = TypedDict(
+    "CreateUploadUrlResponseTypeDef",
+    {
+        "importId": str,
+        "uploadUrl": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CustomPayloadTypeDef = TypedDict(
     "CustomPayloadTypeDef",
     {
         "value": str,
     },
 )
 
@@ -950,47 +1172,81 @@
     "_OptionalDeleteBotAliasRequestRequestTypeDef",
     {
         "skipResourceInUseCheck": bool,
     },
     total=False,
 )
 
+
 class DeleteBotAliasRequestRequestTypeDef(
     _RequiredDeleteBotAliasRequestRequestTypeDef, _OptionalDeleteBotAliasRequestRequestTypeDef
 ):
     pass
 
+
+DeleteBotAliasResponseTypeDef = TypedDict(
+    "DeleteBotAliasResponseTypeDef",
+    {
+        "botAliasId": str,
+        "botId": str,
+        "botAliasStatus": BotAliasStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteBotLocaleRequestRequestTypeDef = TypedDict(
     "DeleteBotLocaleRequestRequestTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
     },
 )
 
+DeleteBotLocaleResponseTypeDef = TypedDict(
+    "DeleteBotLocaleResponseTypeDef",
+    {
+        "botId": str,
+        "botVersion": str,
+        "localeId": str,
+        "botLocaleStatus": BotLocaleStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteBotRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteBotRequestRequestTypeDef",
     {
         "botId": str,
     },
 )
 _OptionalDeleteBotRequestRequestTypeDef = TypedDict(
     "_OptionalDeleteBotRequestRequestTypeDef",
     {
         "skipResourceInUseCheck": bool,
     },
     total=False,
 )
 
+
 class DeleteBotRequestRequestTypeDef(
     _RequiredDeleteBotRequestRequestTypeDef, _OptionalDeleteBotRequestRequestTypeDef
 ):
     pass
 
+
+DeleteBotResponseTypeDef = TypedDict(
+    "DeleteBotResponseTypeDef",
+    {
+        "botId": str,
+        "botStatus": BotStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteBotVersionRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteBotVersionRequestRequestTypeDef",
     {
         "botId": str,
         "botVersion": str,
     },
 )
@@ -998,42 +1254,83 @@
     "_OptionalDeleteBotVersionRequestRequestTypeDef",
     {
         "skipResourceInUseCheck": bool,
     },
     total=False,
 )
 
+
 class DeleteBotVersionRequestRequestTypeDef(
     _RequiredDeleteBotVersionRequestRequestTypeDef, _OptionalDeleteBotVersionRequestRequestTypeDef
 ):
     pass
 
+
+DeleteBotVersionResponseTypeDef = TypedDict(
+    "DeleteBotVersionResponseTypeDef",
+    {
+        "botId": str,
+        "botVersion": str,
+        "botStatus": BotStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteCustomVocabularyRequestRequestTypeDef = TypedDict(
     "DeleteCustomVocabularyRequestRequestTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
     },
 )
 
+DeleteCustomVocabularyResponseTypeDef = TypedDict(
+    "DeleteCustomVocabularyResponseTypeDef",
+    {
+        "botId": str,
+        "botVersion": str,
+        "localeId": str,
+        "customVocabularyStatus": CustomVocabularyStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteExportRequestRequestTypeDef = TypedDict(
     "DeleteExportRequestRequestTypeDef",
     {
         "exportId": str,
     },
 )
 
+DeleteExportResponseTypeDef = TypedDict(
+    "DeleteExportResponseTypeDef",
+    {
+        "exportId": str,
+        "exportStatus": ExportStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteImportRequestRequestTypeDef = TypedDict(
     "DeleteImportRequestRequestTypeDef",
     {
         "importId": str,
     },
 )
 
+DeleteImportResponseTypeDef = TypedDict(
+    "DeleteImportResponseTypeDef",
+    {
+        "importId": str,
+        "importStatus": ImportStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteIntentRequestRequestTypeDef = TypedDict(
     "DeleteIntentRequestRequestTypeDef",
     {
         "intentId": str,
         "botId": str,
         "botVersion": str,
         "localeId": str,
@@ -1050,20 +1347,31 @@
     "_OptionalDeleteResourcePolicyRequestRequestTypeDef",
     {
         "expectedRevisionId": str,
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
+DeleteResourcePolicyResponseTypeDef = TypedDict(
+    "DeleteResourcePolicyResponseTypeDef",
+    {
+        "resourceArn": str,
+        "revisionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeleteResourcePolicyStatementRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteResourcePolicyStatementRequestRequestTypeDef",
     {
         "resourceArn": str,
         "statementId": str,
     },
 )
@@ -1071,20 +1379,31 @@
     "_OptionalDeleteResourcePolicyStatementRequestRequestTypeDef",
     {
         "expectedRevisionId": str,
     },
     total=False,
 )
 
+
 class DeleteResourcePolicyStatementRequestRequestTypeDef(
     _RequiredDeleteResourcePolicyStatementRequestRequestTypeDef,
     _OptionalDeleteResourcePolicyStatementRequestRequestTypeDef,
 ):
     pass
 
+
+DeleteResourcePolicyStatementResponseTypeDef = TypedDict(
+    "DeleteResourcePolicyStatementResponseTypeDef",
+    {
+        "resourceArn": str,
+        "revisionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteSlotRequestRequestTypeDef = TypedDict(
     "DeleteSlotRequestRequestTypeDef",
     {
         "slotId": str,
         "botId": str,
         "botVersion": str,
         "localeId": str,
@@ -1105,19 +1424,28 @@
     "_OptionalDeleteSlotTypeRequestRequestTypeDef",
     {
         "skipResourceInUseCheck": bool,
     },
     total=False,
 )
 
+
 class DeleteSlotTypeRequestRequestTypeDef(
     _RequiredDeleteSlotTypeRequestRequestTypeDef, _OptionalDeleteSlotTypeRequestRequestTypeDef
 ):
     pass
 
+
+DeleteTestSetRequestRequestTypeDef = TypedDict(
+    "DeleteTestSetRequestRequestTypeDef",
+    {
+        "testSetId": str,
+    },
+)
+
 _RequiredDeleteUtterancesRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteUtterancesRequestRequestTypeDef",
     {
         "botId": str,
     },
 )
 _OptionalDeleteUtterancesRequestRequestTypeDef = TypedDict(
@@ -1125,19 +1453,21 @@
     {
         "localeId": str,
         "sessionId": str,
     },
     total=False,
 )
 
+
 class DeleteUtterancesRequestRequestTypeDef(
     _RequiredDeleteUtterancesRequestRequestTypeDef, _OptionalDeleteUtterancesRequestRequestTypeDef
 ):
     pass
 
+
 WaiterConfigTypeDef = TypedDict(
     "WaiterConfigTypeDef",
     {
         "Delay": int,
         "MaxAttempts": int,
     },
     total=False,
@@ -1208,14 +1538,27 @@
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
     },
 )
 
+DescribeCustomVocabularyMetadataResponseTypeDef = TypedDict(
+    "DescribeCustomVocabularyMetadataResponseTypeDef",
+    {
+        "botId": str,
+        "botVersion": str,
+        "localeId": str,
+        "customVocabularyStatus": CustomVocabularyStatusType,
+        "creationDateTime": datetime,
+        "lastUpdatedDateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeExportRequestRequestTypeDef = TypedDict(
     "DescribeExportRequestRequestTypeDef",
     {
         "exportId": str,
     },
 )
 
@@ -1247,14 +1590,24 @@
 DescribeResourcePolicyRequestRequestTypeDef = TypedDict(
     "DescribeResourcePolicyRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
+DescribeResourcePolicyResponseTypeDef = TypedDict(
+    "DescribeResourcePolicyResponseTypeDef",
+    {
+        "resourceArn": str,
+        "policy": str,
+        "revisionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeSlotRequestRequestTypeDef = TypedDict(
     "DescribeSlotRequestRequestTypeDef",
     {
         "slotId": str,
         "botId": str,
         "botVersion": str,
         "localeId": str,
@@ -1268,14 +1621,64 @@
         "slotTypeId": str,
         "botId": str,
         "botVersion": str,
         "localeId": str,
     },
 )
 
+DescribeTestExecutionRequestRequestTypeDef = TypedDict(
+    "DescribeTestExecutionRequestRequestTypeDef",
+    {
+        "testExecutionId": str,
+    },
+)
+
+DescribeTestSetDiscrepancyReportRequestRequestTypeDef = TypedDict(
+    "DescribeTestSetDiscrepancyReportRequestRequestTypeDef",
+    {
+        "testSetDiscrepancyReportId": str,
+    },
+)
+
+DescribeTestSetGenerationRequestRequestTypeDef = TypedDict(
+    "DescribeTestSetGenerationRequestRequestTypeDef",
+    {
+        "testSetGenerationId": str,
+    },
+)
+
+_RequiredTestSetStorageLocationTypeDef = TypedDict(
+    "_RequiredTestSetStorageLocationTypeDef",
+    {
+        "s3BucketName": str,
+        "s3Path": str,
+    },
+)
+_OptionalTestSetStorageLocationTypeDef = TypedDict(
+    "_OptionalTestSetStorageLocationTypeDef",
+    {
+        "kmsKeyArn": str,
+    },
+    total=False,
+)
+
+
+class TestSetStorageLocationTypeDef(
+    _RequiredTestSetStorageLocationTypeDef, _OptionalTestSetStorageLocationTypeDef
+):
+    pass
+
+
+DescribeTestSetRequestRequestTypeDef = TypedDict(
+    "DescribeTestSetRequestRequestTypeDef",
+    {
+        "testSetId": str,
+    },
+)
+
 _RequiredDialogActionTypeDef = TypedDict(
     "_RequiredDialogActionTypeDef",
     {
         "type": DialogActionTypeType,
     },
 )
 _OptionalDialogActionTypeDef = TypedDict(
@@ -1283,17 +1686,19 @@
     {
         "slotToElicit": str,
         "suppressNextMessage": bool,
     },
     total=False,
 )
 
+
 class DialogActionTypeDef(_RequiredDialogActionTypeDef, _OptionalDialogActionTypeDef):
     pass
 
+
 IntentOverrideTypeDef = TypedDict(
     "IntentOverrideTypeDef",
     {
         "name": str,
         "slots": Mapping[str, "SlotValueOverrideTypeDef"],
     },
     total=False,
@@ -1309,37 +1714,69 @@
     "_OptionalElicitationCodeHookInvocationSettingTypeDef",
     {
         "invocationLabel": str,
     },
     total=False,
 )
 
+
 class ElicitationCodeHookInvocationSettingTypeDef(
     _RequiredElicitationCodeHookInvocationSettingTypeDef,
     _OptionalElicitationCodeHookInvocationSettingTypeDef,
 ):
     pass
 
+
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ExportFilterTypeDef = TypedDict(
     "ExportFilterTypeDef",
     {
         "name": Literal["ExportResourceType"],
         "values": Sequence[str],
         "operator": ExportFilterOperatorType,
     },
 )
 
+TestSetExportSpecificationTypeDef = TypedDict(
+    "TestSetExportSpecificationTypeDef",
+    {
+        "testSetId": str,
+    },
+)
+
 ExportSortByTypeDef = TypedDict(
     "ExportSortByTypeDef",
     {
         "attribute": Literal["LastUpdatedDateTime"],
         "order": SortOrderType,
     },
 )
 
+GetTestExecutionArtifactsUrlRequestRequestTypeDef = TypedDict(
+    "GetTestExecutionArtifactsUrlRequestRequestTypeDef",
+    {
+        "testExecutionId": str,
+    },
+)
+
+GetTestExecutionArtifactsUrlResponseTypeDef = TypedDict(
+    "GetTestExecutionArtifactsUrlResponseTypeDef",
+    {
+        "testExecutionId": str,
+        "downloadArtifactsUrl": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGrammarSlotTypeSourceTypeDef = TypedDict(
     "_RequiredGrammarSlotTypeSourceTypeDef",
     {
         "s3BucketName": str,
         "s3ObjectKey": str,
     },
 )
@@ -1347,19 +1784,21 @@
     "_OptionalGrammarSlotTypeSourceTypeDef",
     {
         "kmsKeyArn": str,
     },
     total=False,
 )
 
+
 class GrammarSlotTypeSourceTypeDef(
     _RequiredGrammarSlotTypeSourceTypeDef, _OptionalGrammarSlotTypeSourceTypeDef
 ):
     pass
 
+
 ImportFilterTypeDef = TypedDict(
     "ImportFilterTypeDef",
     {
         "name": Literal["ImportResourceType"],
         "values": Sequence[str],
         "operator": ImportFilterOperatorType,
     },
@@ -1384,14 +1823,45 @@
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
         "importedResourceType": ImportResourceTypeType,
     },
     total=False,
 )
 
+RuntimeHintsTypeDef = TypedDict(
+    "RuntimeHintsTypeDef",
+    {
+        "slotHints": Dict[str, Dict[str, "RuntimeHintDetailsTypeDef"]],
+    },
+    total=False,
+)
+
+_RequiredIntentClassificationTestResultItemCountsTypeDef = TypedDict(
+    "_RequiredIntentClassificationTestResultItemCountsTypeDef",
+    {
+        "totalResultCount": int,
+        "intentMatchResultCounts": Dict[TestResultMatchStatusType, int],
+    },
+)
+_OptionalIntentClassificationTestResultItemCountsTypeDef = TypedDict(
+    "_OptionalIntentClassificationTestResultItemCountsTypeDef",
+    {
+        "speechTranscriptionResultCounts": Dict[TestResultMatchStatusType, int],
+    },
+    total=False,
+)
+
+
+class IntentClassificationTestResultItemCountsTypeDef(
+    _RequiredIntentClassificationTestResultItemCountsTypeDef,
+    _OptionalIntentClassificationTestResultItemCountsTypeDef,
+):
+    pass
+
+
 IntentFilterTypeDef = TypedDict(
     "IntentFilterTypeDef",
     {
         "name": Literal["IntentName"],
         "values": Sequence[str],
         "operator": IntentFilterOperatorType,
     },
@@ -1416,19 +1886,21 @@
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+
 class ListBotAliasesRequestRequestTypeDef(
     _RequiredListBotAliasesRequestRequestTypeDef, _OptionalListBotAliasesRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredListBotRecommendationsRequestRequestTypeDef = TypedDict(
     "_RequiredListBotRecommendationsRequestRequestTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
     },
@@ -1438,20 +1910,22 @@
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+
 class ListBotRecommendationsRequestRequestTypeDef(
     _RequiredListBotRecommendationsRequestRequestTypeDef,
     _OptionalListBotRecommendationsRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredListCustomVocabularyItemsRequestRequestTypeDef = TypedDict(
     "_RequiredListCustomVocabularyItemsRequestRequestTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
     },
@@ -1461,20 +1935,22 @@
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+
 class ListCustomVocabularyItemsRequestRequestTypeDef(
     _RequiredListCustomVocabularyItemsRequestRequestTypeDef,
     _OptionalListCustomVocabularyItemsRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredListRecommendedIntentsRequestRequestTypeDef = TypedDict(
     "_RequiredListRecommendedIntentsRequestRequestTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
         "botRecommendationId": str,
@@ -1485,20 +1961,22 @@
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+
 class ListRecommendedIntentsRequestRequestTypeDef(
     _RequiredListRecommendedIntentsRequestRequestTypeDef,
     _OptionalListRecommendedIntentsRequestRequestTypeDef,
 ):
     pass
 
+
 RecommendedIntentSummaryTypeDef = TypedDict(
     "RecommendedIntentSummaryTypeDef",
     {
         "intentId": str,
         "intentName": str,
         "sampleUtterancesCount": int,
     },
@@ -1555,28 +2033,98 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "resourceARN": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+TestExecutionSortByTypeDef = TypedDict(
+    "TestExecutionSortByTypeDef",
+    {
+        "attribute": TestExecutionSortAttributeType,
+        "order": SortOrderType,
+    },
+)
+
+_RequiredListTestSetRecordsRequestRequestTypeDef = TypedDict(
+    "_RequiredListTestSetRecordsRequestRequestTypeDef",
+    {
+        "testSetId": str,
+    },
+)
+_OptionalListTestSetRecordsRequestRequestTypeDef = TypedDict(
+    "_OptionalListTestSetRecordsRequestRequestTypeDef",
+    {
+        "maxResults": int,
+        "nextToken": str,
+    },
+    total=False,
+)
+
+
+class ListTestSetRecordsRequestRequestTypeDef(
+    _RequiredListTestSetRecordsRequestRequestTypeDef,
+    _OptionalListTestSetRecordsRequestRequestTypeDef,
+):
+    pass
+
+
+TestSetSortByTypeDef = TypedDict(
+    "TestSetSortByTypeDef",
+    {
+        "attribute": TestSetSortAttributeType,
+        "order": SortOrderType,
+    },
+)
+
 PlainTextMessageTypeDef = TypedDict(
     "PlainTextMessageTypeDef",
     {
         "value": str,
     },
 )
 
 SSMLMessageTypeDef = TypedDict(
     "SSMLMessageTypeDef",
     {
         "value": str,
     },
 )
 
+_RequiredOverallTestResultItemTypeDef = TypedDict(
+    "_RequiredOverallTestResultItemTypeDef",
+    {
+        "multiTurnConversation": bool,
+        "totalResultCount": int,
+        "endToEndResultCounts": Dict[TestResultMatchStatusType, int],
+    },
+)
+_OptionalOverallTestResultItemTypeDef = TypedDict(
+    "_OptionalOverallTestResultItemTypeDef",
+    {
+        "speechTranscriptionResultCounts": Dict[TestResultMatchStatusType, int],
+    },
+    total=False,
+)
+
+
+class OverallTestResultItemTypeDef(
+    _RequiredOverallTestResultItemTypeDef, _OptionalOverallTestResultItemTypeDef
+):
+    pass
+
+
 PathFormatTypeDef = TypedDict(
     "PathFormatTypeDef",
     {
         "objectPrefixes": List[str],
     },
     total=False,
 )
@@ -1592,28 +2140,69 @@
     "RelativeAggregationDurationTypeDef",
     {
         "timeDimension": TimeDimensionType,
         "timeValue": int,
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
+RuntimeHintValueTypeDef = TypedDict(
+    "RuntimeHintValueTypeDef",
+    {
+        "phrase": str,
+    },
+)
+
 SampleValueTypeDef = TypedDict(
     "SampleValueTypeDef",
     {
         "value": str,
     },
 )
 
 SlotDefaultValueTypeDef = TypedDict(
     "SlotDefaultValueTypeDef",
     {
         "defaultValue": str,
     },
 )
 
+_RequiredSlotResolutionTestResultItemCountsTypeDef = TypedDict(
+    "_RequiredSlotResolutionTestResultItemCountsTypeDef",
+    {
+        "totalResultCount": int,
+        "slotMatchResultCounts": Dict[TestResultMatchStatusType, int],
+    },
+)
+_OptionalSlotResolutionTestResultItemCountsTypeDef = TypedDict(
+    "_OptionalSlotResolutionTestResultItemCountsTypeDef",
+    {
+        "speechTranscriptionResultCounts": Dict[TestResultMatchStatusType, int],
+    },
+    total=False,
+)
+
+
+class SlotResolutionTestResultItemCountsTypeDef(
+    _RequiredSlotResolutionTestResultItemCountsTypeDef,
+    _OptionalSlotResolutionTestResultItemCountsTypeDef,
+):
+    pass
+
+
 SlotValueTypeDef = TypedDict(
     "SlotValueTypeDef",
     {
         "interpretedValue": str,
     },
     total=False,
 )
@@ -1631,22 +2220,68 @@
         "botId": str,
         "botVersion": str,
         "localeId": str,
         "botRecommendationId": str,
     },
 )
 
+StopBotRecommendationResponseTypeDef = TypedDict(
+    "StopBotRecommendationResponseTypeDef",
+    {
+        "botId": str,
+        "botVersion": str,
+        "localeId": str,
+        "botRecommendationStatus": BotRecommendationStatusType,
+        "botRecommendationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceARN": str,
         "tags": Mapping[str, str],
     },
 )
 
+TestSetIntentDiscrepancyItemTypeDef = TypedDict(
+    "TestSetIntentDiscrepancyItemTypeDef",
+    {
+        "intentName": str,
+        "errorMessage": str,
+    },
+)
+
+TestSetSlotDiscrepancyItemTypeDef = TypedDict(
+    "TestSetSlotDiscrepancyItemTypeDef",
+    {
+        "intentName": str,
+        "slotName": str,
+        "errorMessage": str,
+    },
+)
+
+TestSetDiscrepancyReportBotAliasTargetTypeDef = TypedDict(
+    "TestSetDiscrepancyReportBotAliasTargetTypeDef",
+    {
+        "botId": str,
+        "botAliasId": str,
+        "localeId": str,
+    },
+)
+
+TestSetImportInputLocationTypeDef = TypedDict(
+    "TestSetImportInputLocationTypeDef",
+    {
+        "s3BucketName": str,
+        "s3Path": str,
+    },
+)
+
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceARN": str,
         "tagKeys": Sequence[str],
     },
 )
@@ -1661,19 +2296,21 @@
     "_OptionalUpdateExportRequestRequestTypeDef",
     {
         "filePassword": str,
     },
     total=False,
 )
 
+
 class UpdateExportRequestRequestTypeDef(
     _RequiredUpdateExportRequestRequestTypeDef, _OptionalUpdateExportRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredUpdateResourcePolicyRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateResourcePolicyRequestRequestTypeDef",
     {
         "resourceArn": str,
         "policy": str,
     },
 )
@@ -1681,337 +2318,249 @@
     "_OptionalUpdateResourcePolicyRequestRequestTypeDef",
     {
         "expectedRevisionId": str,
     },
     total=False,
 )
 
+
 class UpdateResourcePolicyRequestRequestTypeDef(
     _RequiredUpdateResourcePolicyRequestRequestTypeDef,
     _OptionalUpdateResourcePolicyRequestRequestTypeDef,
 ):
     pass
 
-_RequiredSearchAssociatedTranscriptsRequestRequestTypeDef = TypedDict(
-    "_RequiredSearchAssociatedTranscriptsRequestRequestTypeDef",
+
+UpdateResourcePolicyResponseTypeDef = TypedDict(
+    "UpdateResourcePolicyResponseTypeDef",
     {
-        "botId": str,
-        "botVersion": str,
-        "localeId": str,
-        "botRecommendationId": str,
-        "filters": Sequence[AssociatedTranscriptFilterTypeDef],
+        "resourceArn": str,
+        "revisionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalSearchAssociatedTranscriptsRequestRequestTypeDef = TypedDict(
-    "_OptionalSearchAssociatedTranscriptsRequestRequestTypeDef",
+
+_RequiredUpdateTestSetRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateTestSetRequestRequestTypeDef",
     {
-        "searchOrder": SearchOrderType,
-        "maxResults": int,
-        "nextIndex": int,
+        "testSetId": str,
+        "testSetName": str,
+    },
+)
+_OptionalUpdateTestSetRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateTestSetRequestRequestTypeDef",
+    {
+        "description": str,
     },
     total=False,
 )
 
-class SearchAssociatedTranscriptsRequestRequestTypeDef(
-    _RequiredSearchAssociatedTranscriptsRequestRequestTypeDef,
-    _OptionalSearchAssociatedTranscriptsRequestRequestTypeDef,
+
+class UpdateTestSetRequestRequestTypeDef(
+    _RequiredUpdateTestSetRequestRequestTypeDef, _OptionalUpdateTestSetRequestRequestTypeDef
 ):
     pass
 
-_RequiredAudioAndDTMFInputSpecificationTypeDef = TypedDict(
-    "_RequiredAudioAndDTMFInputSpecificationTypeDef",
+
+_RequiredUserTurnIntentOutputTypeDef = TypedDict(
+    "_RequiredUserTurnIntentOutputTypeDef",
     {
-        "startTimeoutMs": int,
+        "name": str,
     },
 )
-_OptionalAudioAndDTMFInputSpecificationTypeDef = TypedDict(
-    "_OptionalAudioAndDTMFInputSpecificationTypeDef",
+_OptionalUserTurnIntentOutputTypeDef = TypedDict(
+    "_OptionalUserTurnIntentOutputTypeDef",
     {
-        "audioSpecification": AudioSpecificationTypeDef,
-        "dtmfSpecification": DTMFSpecificationTypeDef,
+        "slots": Dict[str, "UserTurnSlotOutputTypeDef"],
     },
     total=False,
 )
 
-class AudioAndDTMFInputSpecificationTypeDef(
-    _RequiredAudioAndDTMFInputSpecificationTypeDef, _OptionalAudioAndDTMFInputSpecificationTypeDef
+
+class UserTurnIntentOutputTypeDef(
+    _RequiredUserTurnIntentOutputTypeDef, _OptionalUserTurnIntentOutputTypeDef
 ):
     pass
 
-AudioLogDestinationTypeDef = TypedDict(
-    "AudioLogDestinationTypeDef",
-    {
-        "s3Bucket": S3BucketLogDestinationTypeDef,
-    },
-)
 
-BatchCreateCustomVocabularyItemRequestRequestTypeDef = TypedDict(
-    "BatchCreateCustomVocabularyItemRequestRequestTypeDef",
+UserTurnSlotOutputTypeDef = TypedDict(
+    "UserTurnSlotOutputTypeDef",
     {
-        "botId": str,
-        "botVersion": str,
-        "localeId": str,
-        "customVocabularyItemList": Sequence[NewCustomVocabularyItemTypeDef],
+        "value": str,
+        "values": List[Dict[str, Any]],
+        "subSlots": Dict[str, Dict[str, Any]],
     },
+    total=False,
 )
 
-BatchUpdateCustomVocabularyItemRequestRequestTypeDef = TypedDict(
-    "BatchUpdateCustomVocabularyItemRequestRequestTypeDef",
+UtteranceAudioInputSpecificationTypeDef = TypedDict(
+    "UtteranceAudioInputSpecificationTypeDef",
     {
-        "botId": str,
-        "botVersion": str,
-        "localeId": str,
-        "customVocabularyItemList": Sequence[CustomVocabularyItemTypeDef],
+        "audioFileS3Location": str,
     },
 )
 
-BatchCreateCustomVocabularyItemResponseTypeDef = TypedDict(
-    "BatchCreateCustomVocabularyItemResponseTypeDef",
+_RequiredAgentTurnResultTypeDef = TypedDict(
+    "_RequiredAgentTurnResultTypeDef",
     {
-        "botId": str,
-        "botVersion": str,
-        "localeId": str,
-        "errors": List[FailedCustomVocabularyItemTypeDef],
-        "resources": List[CustomVocabularyItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "expectedAgentPrompt": str,
     },
 )
-
-BatchDeleteCustomVocabularyItemResponseTypeDef = TypedDict(
-    "BatchDeleteCustomVocabularyItemResponseTypeDef",
+_OptionalAgentTurnResultTypeDef = TypedDict(
+    "_OptionalAgentTurnResultTypeDef",
     {
-        "botId": str,
-        "botVersion": str,
-        "localeId": str,
-        "errors": List[FailedCustomVocabularyItemTypeDef],
-        "resources": List[CustomVocabularyItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "actualAgentPrompt": str,
+        "errorDetails": ExecutionErrorDetailsTypeDef,
+        "actualElicitedSlot": str,
+        "actualIntent": str,
     },
+    total=False,
 )
 
-BatchUpdateCustomVocabularyItemResponseTypeDef = TypedDict(
-    "BatchUpdateCustomVocabularyItemResponseTypeDef",
-    {
-        "botId": str,
-        "botVersion": str,
-        "localeId": str,
-        "errors": List[FailedCustomVocabularyItemTypeDef],
-        "resources": List[CustomVocabularyItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-BuildBotLocaleResponseTypeDef = TypedDict(
-    "BuildBotLocaleResponseTypeDef",
+class AgentTurnResultTypeDef(_RequiredAgentTurnResultTypeDef, _OptionalAgentTurnResultTypeDef):
+    pass
+
+
+_RequiredSearchAssociatedTranscriptsRequestRequestTypeDef = TypedDict(
+    "_RequiredSearchAssociatedTranscriptsRequestRequestTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
-        "botLocaleStatus": BotLocaleStatusType,
-        "lastBuildSubmittedDateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "botRecommendationId": str,
+        "filters": Sequence[AssociatedTranscriptFilterTypeDef],
     },
 )
-
-CreateResourcePolicyResponseTypeDef = TypedDict(
-    "CreateResourcePolicyResponseTypeDef",
+_OptionalSearchAssociatedTranscriptsRequestRequestTypeDef = TypedDict(
+    "_OptionalSearchAssociatedTranscriptsRequestRequestTypeDef",
     {
-        "resourceArn": str,
-        "revisionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "searchOrder": SearchOrderType,
+        "maxResults": int,
+        "nextIndex": int,
     },
+    total=False,
 )
 
-CreateResourcePolicyStatementResponseTypeDef = TypedDict(
-    "CreateResourcePolicyStatementResponseTypeDef",
-    {
-        "resourceArn": str,
-        "revisionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-CreateUploadUrlResponseTypeDef = TypedDict(
-    "CreateUploadUrlResponseTypeDef",
-    {
-        "importId": str,
-        "uploadUrl": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class SearchAssociatedTranscriptsRequestRequestTypeDef(
+    _RequiredSearchAssociatedTranscriptsRequestRequestTypeDef,
+    _OptionalSearchAssociatedTranscriptsRequestRequestTypeDef,
+):
+    pass
 
-DeleteBotAliasResponseTypeDef = TypedDict(
-    "DeleteBotAliasResponseTypeDef",
-    {
-        "botAliasId": str,
-        "botId": str,
-        "botAliasStatus": BotAliasStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-DeleteBotLocaleResponseTypeDef = TypedDict(
-    "DeleteBotLocaleResponseTypeDef",
+SearchAssociatedTranscriptsResponseTypeDef = TypedDict(
+    "SearchAssociatedTranscriptsResponseTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
-        "botLocaleStatus": BotLocaleStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteBotResponseTypeDef = TypedDict(
-    "DeleteBotResponseTypeDef",
-    {
-        "botId": str,
-        "botStatus": BotStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "botRecommendationId": str,
+        "nextIndex": int,
+        "associatedTranscripts": List[AssociatedTranscriptTypeDef],
+        "totalResults": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteBotVersionResponseTypeDef = TypedDict(
-    "DeleteBotVersionResponseTypeDef",
+_RequiredAudioAndDTMFInputSpecificationTypeDef = TypedDict(
+    "_RequiredAudioAndDTMFInputSpecificationTypeDef",
     {
-        "botId": str,
-        "botVersion": str,
-        "botStatus": BotStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "startTimeoutMs": int,
     },
 )
-
-DeleteCustomVocabularyResponseTypeDef = TypedDict(
-    "DeleteCustomVocabularyResponseTypeDef",
+_OptionalAudioAndDTMFInputSpecificationTypeDef = TypedDict(
+    "_OptionalAudioAndDTMFInputSpecificationTypeDef",
     {
-        "botId": str,
-        "botVersion": str,
-        "localeId": str,
-        "customVocabularyStatus": CustomVocabularyStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "audioSpecification": AudioSpecificationTypeDef,
+        "dtmfSpecification": DTMFSpecificationTypeDef,
     },
+    total=False,
 )
 
-DeleteExportResponseTypeDef = TypedDict(
-    "DeleteExportResponseTypeDef",
-    {
-        "exportId": str,
-        "exportStatus": ExportStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-DeleteImportResponseTypeDef = TypedDict(
-    "DeleteImportResponseTypeDef",
-    {
-        "importId": str,
-        "importStatus": ImportStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class AudioAndDTMFInputSpecificationTypeDef(
+    _RequiredAudioAndDTMFInputSpecificationTypeDef, _OptionalAudioAndDTMFInputSpecificationTypeDef
+):
+    pass
 
-DeleteResourcePolicyResponseTypeDef = TypedDict(
-    "DeleteResourcePolicyResponseTypeDef",
-    {
-        "resourceArn": str,
-        "revisionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-DeleteResourcePolicyStatementResponseTypeDef = TypedDict(
-    "DeleteResourcePolicyStatementResponseTypeDef",
+AudioLogDestinationTypeDef = TypedDict(
+    "AudioLogDestinationTypeDef",
     {
-        "resourceArn": str,
-        "revisionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "s3Bucket": S3BucketLogDestinationTypeDef,
     },
 )
 
-DescribeCustomVocabularyMetadataResponseTypeDef = TypedDict(
-    "DescribeCustomVocabularyMetadataResponseTypeDef",
+BatchCreateCustomVocabularyItemRequestRequestTypeDef = TypedDict(
+    "BatchCreateCustomVocabularyItemRequestRequestTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
-        "customVocabularyStatus": CustomVocabularyStatusType,
-        "creationDateTime": datetime,
-        "lastUpdatedDateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeResourcePolicyResponseTypeDef = TypedDict(
-    "DescribeResourcePolicyResponseTypeDef",
-    {
-        "resourceArn": str,
-        "policy": str,
-        "revisionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "customVocabularyItemList": Sequence[NewCustomVocabularyItemTypeDef],
     },
 )
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
+BatchUpdateCustomVocabularyItemRequestRequestTypeDef = TypedDict(
+    "BatchUpdateCustomVocabularyItemRequestRequestTypeDef",
     {
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "botId": str,
+        "botVersion": str,
+        "localeId": str,
+        "customVocabularyItemList": Sequence[CustomVocabularyItemTypeDef],
     },
 )
 
 ListCustomVocabularyItemsResponseTypeDef = TypedDict(
     "ListCustomVocabularyItemsResponseTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
         "customVocabularyItems": List[CustomVocabularyItemTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SearchAssociatedTranscriptsResponseTypeDef = TypedDict(
-    "SearchAssociatedTranscriptsResponseTypeDef",
+BatchCreateCustomVocabularyItemResponseTypeDef = TypedDict(
+    "BatchCreateCustomVocabularyItemResponseTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
-        "botRecommendationId": str,
-        "nextIndex": int,
-        "associatedTranscripts": List[AssociatedTranscriptTypeDef],
-        "totalResults": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "errors": List[FailedCustomVocabularyItemTypeDef],
+        "resources": List[CustomVocabularyItemTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-StopBotRecommendationResponseTypeDef = TypedDict(
-    "StopBotRecommendationResponseTypeDef",
+BatchDeleteCustomVocabularyItemResponseTypeDef = TypedDict(
+    "BatchDeleteCustomVocabularyItemResponseTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
-        "botRecommendationStatus": BotRecommendationStatusType,
-        "botRecommendationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "errors": List[FailedCustomVocabularyItemTypeDef],
+        "resources": List[CustomVocabularyItemTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateResourcePolicyResponseTypeDef = TypedDict(
-    "UpdateResourcePolicyResponseTypeDef",
+BatchUpdateCustomVocabularyItemResponseTypeDef = TypedDict(
+    "BatchUpdateCustomVocabularyItemResponseTypeDef",
     {
-        "resourceArn": str,
-        "revisionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "botId": str,
+        "botVersion": str,
+        "localeId": str,
+        "errors": List[FailedCustomVocabularyItemTypeDef],
+        "resources": List[CustomVocabularyItemTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDeleteCustomVocabularyItemRequestRequestTypeDef = TypedDict(
     "BatchDeleteCustomVocabularyItemRequestRequestTypeDef",
     {
         "botId": str,
@@ -2023,18 +2572,26 @@
 
 ListBotAliasesResponseTypeDef = TypedDict(
     "ListBotAliasesResponseTypeDef",
     {
         "botAliasSummaries": List[BotAliasSummaryTypeDef],
         "nextToken": str,
         "botId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
+TestExecutionTargetTypeDef = TypedDict(
+    "TestExecutionTargetTypeDef",
+    {
+        "botAliasTarget": BotAliasTestExecutionTargetTypeDef,
+    },
+    total=False,
+)
+
 _RequiredBotImportSpecificationTypeDef = TypedDict(
     "_RequiredBotImportSpecificationTypeDef",
     {
         "botName": str,
         "roleArn": str,
         "dataPrivacy": DataPrivacyTypeDef,
     },
@@ -2045,19 +2602,21 @@
         "idleSessionTTLInSeconds": int,
         "botTags": Dict[str, str],
         "testBotAliasTags": Dict[str, str],
     },
     total=False,
 )
 
+
 class BotImportSpecificationTypeDef(
     _RequiredBotImportSpecificationTypeDef, _OptionalBotImportSpecificationTypeDef
 ):
     pass
 
+
 _RequiredBotLocaleImportSpecificationTypeDef = TypedDict(
     "_RequiredBotLocaleImportSpecificationTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
     },
@@ -2067,19 +2626,21 @@
     {
         "nluIntentConfidenceThreshold": float,
         "voiceSettings": VoiceSettingsTypeDef,
     },
     total=False,
 )
 
+
 class BotLocaleImportSpecificationTypeDef(
     _RequiredBotLocaleImportSpecificationTypeDef, _OptionalBotLocaleImportSpecificationTypeDef
 ):
     pass
 
+
 _RequiredCreateBotLocaleRequestRequestTypeDef = TypedDict(
     "_RequiredCreateBotLocaleRequestRequestTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
         "nluIntentConfidenceThreshold": float,
@@ -2090,32 +2651,34 @@
     {
         "description": str,
         "voiceSettings": VoiceSettingsTypeDef,
     },
     total=False,
 )
 
+
 class CreateBotLocaleRequestRequestTypeDef(
     _RequiredCreateBotLocaleRequestRequestTypeDef, _OptionalCreateBotLocaleRequestRequestTypeDef
 ):
     pass
 
+
 CreateBotLocaleResponseTypeDef = TypedDict(
     "CreateBotLocaleResponseTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeName": str,
         "localeId": str,
         "description": str,
         "nluIntentConfidenceThreshold": float,
         "voiceSettings": VoiceSettingsTypeDef,
         "botLocaleStatus": BotLocaleStatusType,
         "creationDateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeBotLocaleResponseTypeDef = TypedDict(
     "DescribeBotLocaleResponseTypeDef",
     {
         "botId": str,
@@ -2130,15 +2693,15 @@
         "botLocaleStatus": BotLocaleStatusType,
         "failureReasons": List[str],
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
         "lastBuildSubmittedDateTime": datetime,
         "botLocaleHistoryEvents": List[BotLocaleHistoryEventTypeDef],
         "recommendedActions": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateBotLocaleRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateBotLocaleRequestRequestTypeDef",
     {
         "botId": str,
@@ -2152,19 +2715,21 @@
     {
         "description": str,
         "voiceSettings": VoiceSettingsTypeDef,
     },
     total=False,
 )
 
+
 class UpdateBotLocaleRequestRequestTypeDef(
     _RequiredUpdateBotLocaleRequestRequestTypeDef, _OptionalUpdateBotLocaleRequestRequestTypeDef
 ):
     pass
 
+
 UpdateBotLocaleResponseTypeDef = TypedDict(
     "UpdateBotLocaleResponseTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
         "localeName": str,
@@ -2172,15 +2737,15 @@
         "nluIntentConfidenceThreshold": float,
         "voiceSettings": VoiceSettingsTypeDef,
         "botLocaleStatus": BotLocaleStatusType,
         "failureReasons": List[str],
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
         "recommendedActions": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredListBotLocalesRequestRequestTypeDef = TypedDict(
     "_RequiredListBotLocalesRequestRequestTypeDef",
     {
         "botId": str,
@@ -2194,27 +2759,29 @@
         "filters": Sequence[BotLocaleFilterTypeDef],
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+
 class ListBotLocalesRequestRequestTypeDef(
     _RequiredListBotLocalesRequestRequestTypeDef, _OptionalListBotLocalesRequestRequestTypeDef
 ):
     pass
 
+
 ListBotLocalesResponseTypeDef = TypedDict(
     "ListBotLocalesResponseTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "nextToken": str,
         "botLocaleSummaries": List[BotLocaleSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateBotRequestRequestTypeDef = TypedDict(
     "_RequiredCreateBotRequestRequestTypeDef",
     {
         "botName": str,
@@ -2231,19 +2798,21 @@
         "testBotAliasTags": Mapping[str, str],
         "botType": BotTypeType,
         "botMembers": Sequence[BotMemberTypeDef],
     },
     total=False,
 )
 
+
 class CreateBotRequestRequestTypeDef(
     _RequiredCreateBotRequestRequestTypeDef, _OptionalCreateBotRequestRequestTypeDef
 ):
     pass
 
+
 CreateBotResponseTypeDef = TypedDict(
     "CreateBotResponseTypeDef",
     {
         "botId": str,
         "botName": str,
         "description": str,
         "roleArn": str,
@@ -2251,15 +2820,15 @@
         "idleSessionTTLInSeconds": int,
         "botStatus": BotStatusType,
         "creationDateTime": datetime,
         "botTags": Dict[str, str],
         "testBotAliasTags": Dict[str, str],
         "botType": BotTypeType,
         "botMembers": List[BotMemberTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeBotResponseTypeDef = TypedDict(
     "DescribeBotResponseTypeDef",
     {
         "botId": str,
@@ -2270,15 +2839,15 @@
         "idleSessionTTLInSeconds": int,
         "botStatus": BotStatusType,
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
         "botType": BotTypeType,
         "botMembers": List[BotMemberTypeDef],
         "failureReasons": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateBotRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateBotRequestRequestTypeDef",
     {
         "botId": str,
@@ -2294,34 +2863,36 @@
         "description": str,
         "botType": BotTypeType,
         "botMembers": Sequence[BotMemberTypeDef],
     },
     total=False,
 )
 
+
 class UpdateBotRequestRequestTypeDef(
     _RequiredUpdateBotRequestRequestTypeDef, _OptionalUpdateBotRequestRequestTypeDef
 ):
     pass
 
+
 UpdateBotResponseTypeDef = TypedDict(
     "UpdateBotResponseTypeDef",
     {
         "botId": str,
         "botName": str,
         "description": str,
         "roleArn": str,
         "dataPrivacy": DataPrivacyTypeDef,
         "idleSessionTTLInSeconds": int,
         "botStatus": BotStatusType,
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
         "botType": BotTypeType,
         "botMembers": List[BotMemberTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BotRecommendationResultStatisticsTypeDef = TypedDict(
     "BotRecommendationResultStatisticsTypeDef",
     {
         "intents": IntentStatisticsTypeDef,
@@ -2334,15 +2905,15 @@
     "ListBotRecommendationsResponseTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
         "botRecommendationSummaries": List[BotRecommendationSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListBotsRequestRequestTypeDef = TypedDict(
     "ListBotsRequestRequestTypeDef",
     {
         "sortBy": BotSortByTypeDef,
@@ -2354,15 +2925,15 @@
 )
 
 ListBotsResponseTypeDef = TypedDict(
     "ListBotsResponseTypeDef",
     {
         "botSummaries": List[BotSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateBotVersionRequestRequestTypeDef = TypedDict(
     "_RequiredCreateBotVersionRequestRequestTypeDef",
     {
         "botId": str,
@@ -2373,29 +2944,31 @@
     "_OptionalCreateBotVersionRequestRequestTypeDef",
     {
         "description": str,
     },
     total=False,
 )
 
+
 class CreateBotVersionRequestRequestTypeDef(
     _RequiredCreateBotVersionRequestRequestTypeDef, _OptionalCreateBotVersionRequestRequestTypeDef
 ):
     pass
 
+
 CreateBotVersionResponseTypeDef = TypedDict(
     "CreateBotVersionResponseTypeDef",
     {
         "botId": str,
         "description": str,
         "botVersion": str,
         "botVersionLocaleSpecification": Dict[str, BotVersionLocaleDetailsTypeDef],
         "botStatus": BotStatusType,
         "creationDateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredListBotVersionsRequestRequestTypeDef = TypedDict(
     "_RequiredListBotVersionsRequestRequestTypeDef",
     {
         "botId": str,
@@ -2407,26 +2980,28 @@
         "sortBy": BotVersionSortByTypeDef,
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+
 class ListBotVersionsRequestRequestTypeDef(
     _RequiredListBotVersionsRequestRequestTypeDef, _OptionalListBotVersionsRequestRequestTypeDef
 ):
     pass
 
+
 ListBotVersionsResponseTypeDef = TypedDict(
     "ListBotVersionsResponseTypeDef",
     {
         "botId": str,
         "botVersionSummaries": List[BotVersionSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredListBuiltInIntentsRequestRequestTypeDef = TypedDict(
     "_RequiredListBuiltInIntentsRequestRequestTypeDef",
     {
         "localeId": str,
@@ -2438,27 +3013,29 @@
         "sortBy": BuiltInIntentSortByTypeDef,
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+
 class ListBuiltInIntentsRequestRequestTypeDef(
     _RequiredListBuiltInIntentsRequestRequestTypeDef,
     _OptionalListBuiltInIntentsRequestRequestTypeDef,
 ):
     pass
 
+
 ListBuiltInIntentsResponseTypeDef = TypedDict(
     "ListBuiltInIntentsResponseTypeDef",
     {
         "builtInIntentSummaries": List[BuiltInIntentSummaryTypeDef],
         "nextToken": str,
         "localeId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredListBuiltInSlotTypesRequestRequestTypeDef = TypedDict(
     "_RequiredListBuiltInSlotTypesRequestRequestTypeDef",
     {
         "localeId": str,
@@ -2470,27 +3047,29 @@
         "sortBy": BuiltInSlotTypeSortByTypeDef,
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+
 class ListBuiltInSlotTypesRequestRequestTypeDef(
     _RequiredListBuiltInSlotTypesRequestRequestTypeDef,
     _OptionalListBuiltInSlotTypesRequestRequestTypeDef,
 ):
     pass
 
+
 ListBuiltInSlotTypesResponseTypeDef = TypedDict(
     "ListBuiltInSlotTypesResponseTypeDef",
     {
         "builtInSlotTypeSummaries": List[BuiltInSlotTypeSummaryTypeDef],
         "nextToken": str,
         "localeId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredImageResponseCardTypeDef = TypedDict(
     "_RequiredImageResponseCardTypeDef",
     {
         "title": str,
@@ -2502,19 +3081,21 @@
         "subtitle": str,
         "imageUrl": str,
         "buttons": Sequence[ButtonTypeDef],
     },
     total=False,
 )
 
+
 class ImageResponseCardTypeDef(
     _RequiredImageResponseCardTypeDef, _OptionalImageResponseCardTypeDef
 ):
     pass
 
+
 TextLogDestinationTypeDef = TypedDict(
     "TextLogDestinationTypeDef",
     {
         "cloudWatch": CloudWatchLogGroupLogDestinationTypeDef,
     },
 )
 
@@ -2529,14 +3110,69 @@
     "CompositeSlotTypeSettingTypeDef",
     {
         "subSlots": Sequence[SubSlotTypeCompositionTypeDef],
     },
     total=False,
 )
 
+_RequiredConversationLevelTestResultItemTypeDef = TypedDict(
+    "_RequiredConversationLevelTestResultItemTypeDef",
+    {
+        "conversationId": str,
+        "endToEndResult": TestResultMatchStatusType,
+        "intentClassificationResults": List[ConversationLevelIntentClassificationResultItemTypeDef],
+        "slotResolutionResults": List[ConversationLevelSlotResolutionResultItemTypeDef],
+    },
+)
+_OptionalConversationLevelTestResultItemTypeDef = TypedDict(
+    "_OptionalConversationLevelTestResultItemTypeDef",
+    {
+        "speechTranscriptionResult": TestResultMatchStatusType,
+    },
+    total=False,
+)
+
+
+class ConversationLevelTestResultItemTypeDef(
+    _RequiredConversationLevelTestResultItemTypeDef, _OptionalConversationLevelTestResultItemTypeDef
+):
+    pass
+
+
+_RequiredTestExecutionResultFilterByTypeDef = TypedDict(
+    "_RequiredTestExecutionResultFilterByTypeDef",
+    {
+        "resultTypeFilter": TestResultTypeFilterType,
+    },
+)
+_OptionalTestExecutionResultFilterByTypeDef = TypedDict(
+    "_OptionalTestExecutionResultFilterByTypeDef",
+    {
+        "conversationLevelTestResultsFilterBy": ConversationLevelTestResultsFilterByTypeDef,
+    },
+    total=False,
+)
+
+
+class TestExecutionResultFilterByTypeDef(
+    _RequiredTestExecutionResultFilterByTypeDef, _OptionalTestExecutionResultFilterByTypeDef
+):
+    pass
+
+
+ConversationLogsDataSourceTypeDef = TypedDict(
+    "ConversationLogsDataSourceTypeDef",
+    {
+        "botId": str,
+        "botAliasId": str,
+        "localeId": str,
+        "filter": ConversationLogsDataSourceFilterByTypeDef,
+    },
+)
+
 IntentSummaryTypeDef = TypedDict(
     "IntentSummaryTypeDef",
     {
         "intentId": str,
         "intentName": str,
         "description": str,
         "parentIntentSignature": str,
@@ -2562,29 +3198,21 @@
     {
         "condition": Mapping[str, Mapping[str, str]],
         "expectedRevisionId": str,
     },
     total=False,
 )
 
+
 class CreateResourcePolicyStatementRequestRequestTypeDef(
     _RequiredCreateResourcePolicyStatementRequestRequestTypeDef,
     _OptionalCreateResourcePolicyStatementRequestRequestTypeDef,
 ):
     pass
 
-ExportResourceSpecificationTypeDef = TypedDict(
-    "ExportResourceSpecificationTypeDef",
-    {
-        "botExportSpecification": BotExportSpecificationTypeDef,
-        "botLocaleExportSpecification": BotLocaleExportSpecificationTypeDef,
-        "customVocabularyExportSpecification": CustomVocabularyExportSpecificationTypeDef,
-    },
-    total=False,
-)
 
 LexTranscriptFilterTypeDef = TypedDict(
     "LexTranscriptFilterTypeDef",
     {
         "dateRangeFilter": DateRangeFilterTypeDef,
     },
     total=False,
@@ -2601,20 +3229,22 @@
     "_OptionalDescribeBotAliasRequestBotAliasAvailableWaitTypeDef",
     {
         "WaiterConfig": WaiterConfigTypeDef,
     },
     total=False,
 )
 
+
 class DescribeBotAliasRequestBotAliasAvailableWaitTypeDef(
     _RequiredDescribeBotAliasRequestBotAliasAvailableWaitTypeDef,
     _OptionalDescribeBotAliasRequestBotAliasAvailableWaitTypeDef,
 ):
     pass
 
+
 _RequiredDescribeBotLocaleRequestBotLocaleBuiltWaitTypeDef = TypedDict(
     "_RequiredDescribeBotLocaleRequestBotLocaleBuiltWaitTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
     },
@@ -2623,20 +3253,22 @@
     "_OptionalDescribeBotLocaleRequestBotLocaleBuiltWaitTypeDef",
     {
         "WaiterConfig": WaiterConfigTypeDef,
     },
     total=False,
 )
 
+
 class DescribeBotLocaleRequestBotLocaleBuiltWaitTypeDef(
     _RequiredDescribeBotLocaleRequestBotLocaleBuiltWaitTypeDef,
     _OptionalDescribeBotLocaleRequestBotLocaleBuiltWaitTypeDef,
 ):
     pass
 
+
 _RequiredDescribeBotLocaleRequestBotLocaleCreatedWaitTypeDef = TypedDict(
     "_RequiredDescribeBotLocaleRequestBotLocaleCreatedWaitTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
     },
@@ -2645,20 +3277,22 @@
     "_OptionalDescribeBotLocaleRequestBotLocaleCreatedWaitTypeDef",
     {
         "WaiterConfig": WaiterConfigTypeDef,
     },
     total=False,
 )
 
+
 class DescribeBotLocaleRequestBotLocaleCreatedWaitTypeDef(
     _RequiredDescribeBotLocaleRequestBotLocaleCreatedWaitTypeDef,
     _OptionalDescribeBotLocaleRequestBotLocaleCreatedWaitTypeDef,
 ):
     pass
 
+
 _RequiredDescribeBotLocaleRequestBotLocaleExpressTestingAvailableWaitTypeDef = TypedDict(
     "_RequiredDescribeBotLocaleRequestBotLocaleExpressTestingAvailableWaitTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
     },
@@ -2667,40 +3301,44 @@
     "_OptionalDescribeBotLocaleRequestBotLocaleExpressTestingAvailableWaitTypeDef",
     {
         "WaiterConfig": WaiterConfigTypeDef,
     },
     total=False,
 )
 
+
 class DescribeBotLocaleRequestBotLocaleExpressTestingAvailableWaitTypeDef(
     _RequiredDescribeBotLocaleRequestBotLocaleExpressTestingAvailableWaitTypeDef,
     _OptionalDescribeBotLocaleRequestBotLocaleExpressTestingAvailableWaitTypeDef,
 ):
     pass
 
+
 _RequiredDescribeBotRequestBotAvailableWaitTypeDef = TypedDict(
     "_RequiredDescribeBotRequestBotAvailableWaitTypeDef",
     {
         "botId": str,
     },
 )
 _OptionalDescribeBotRequestBotAvailableWaitTypeDef = TypedDict(
     "_OptionalDescribeBotRequestBotAvailableWaitTypeDef",
     {
         "WaiterConfig": WaiterConfigTypeDef,
     },
     total=False,
 )
 
+
 class DescribeBotRequestBotAvailableWaitTypeDef(
     _RequiredDescribeBotRequestBotAvailableWaitTypeDef,
     _OptionalDescribeBotRequestBotAvailableWaitTypeDef,
 ):
     pass
 
+
 _RequiredDescribeBotVersionRequestBotVersionAvailableWaitTypeDef = TypedDict(
     "_RequiredDescribeBotVersionRequestBotVersionAvailableWaitTypeDef",
     {
         "botId": str,
         "botVersion": str,
     },
 )
@@ -2708,60 +3346,66 @@
     "_OptionalDescribeBotVersionRequestBotVersionAvailableWaitTypeDef",
     {
         "WaiterConfig": WaiterConfigTypeDef,
     },
     total=False,
 )
 
+
 class DescribeBotVersionRequestBotVersionAvailableWaitTypeDef(
     _RequiredDescribeBotVersionRequestBotVersionAvailableWaitTypeDef,
     _OptionalDescribeBotVersionRequestBotVersionAvailableWaitTypeDef,
 ):
     pass
 
+
 _RequiredDescribeExportRequestBotExportCompletedWaitTypeDef = TypedDict(
     "_RequiredDescribeExportRequestBotExportCompletedWaitTypeDef",
     {
         "exportId": str,
     },
 )
 _OptionalDescribeExportRequestBotExportCompletedWaitTypeDef = TypedDict(
     "_OptionalDescribeExportRequestBotExportCompletedWaitTypeDef",
     {
         "WaiterConfig": WaiterConfigTypeDef,
     },
     total=False,
 )
 
+
 class DescribeExportRequestBotExportCompletedWaitTypeDef(
     _RequiredDescribeExportRequestBotExportCompletedWaitTypeDef,
     _OptionalDescribeExportRequestBotExportCompletedWaitTypeDef,
 ):
     pass
 
+
 _RequiredDescribeImportRequestBotImportCompletedWaitTypeDef = TypedDict(
     "_RequiredDescribeImportRequestBotImportCompletedWaitTypeDef",
     {
         "importId": str,
     },
 )
 _OptionalDescribeImportRequestBotImportCompletedWaitTypeDef = TypedDict(
     "_OptionalDescribeImportRequestBotImportCompletedWaitTypeDef",
     {
         "WaiterConfig": WaiterConfigTypeDef,
     },
     total=False,
 )
 
+
 class DescribeImportRequestBotImportCompletedWaitTypeDef(
     _RequiredDescribeImportRequestBotImportCompletedWaitTypeDef,
     _OptionalDescribeImportRequestBotImportCompletedWaitTypeDef,
 ):
     pass
 
+
 DescribeBotVersionResponseTypeDef = TypedDict(
     "DescribeBotVersionResponseTypeDef",
     {
         "botId": str,
         "botName": str,
         "botVersion": str,
         "description": str,
@@ -2770,39 +3414,101 @@
         "idleSessionTTLInSeconds": int,
         "botStatus": BotStatusType,
         "failureReasons": List[str],
         "creationDateTime": datetime,
         "parentBotNetworks": List[ParentBotNetworkTypeDef],
         "botType": BotTypeType,
         "botMembers": List[BotMemberTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateBotRecommendationRequestRequestTypeDef = TypedDict(
     "UpdateBotRecommendationRequestRequestTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
         "botRecommendationId": str,
         "encryptionSetting": EncryptionSettingTypeDef,
     },
 )
 
+DescribeTestSetResponseTypeDef = TypedDict(
+    "DescribeTestSetResponseTypeDef",
+    {
+        "testSetId": str,
+        "testSetName": str,
+        "description": str,
+        "modality": TestSetModalityType,
+        "status": TestSetStatusType,
+        "roleArn": str,
+        "numTurns": int,
+        "storageLocation": TestSetStorageLocationTypeDef,
+        "creationDateTime": datetime,
+        "lastUpdatedDateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+TestSetSummaryTypeDef = TypedDict(
+    "TestSetSummaryTypeDef",
+    {
+        "testSetId": str,
+        "testSetName": str,
+        "description": str,
+        "modality": TestSetModalityType,
+        "status": TestSetStatusType,
+        "roleArn": str,
+        "numTurns": int,
+        "storageLocation": TestSetStorageLocationTypeDef,
+        "creationDateTime": datetime,
+        "lastUpdatedDateTime": datetime,
+    },
+    total=False,
+)
+
+UpdateTestSetResponseTypeDef = TypedDict(
+    "UpdateTestSetResponseTypeDef",
+    {
+        "testSetId": str,
+        "testSetName": str,
+        "description": str,
+        "modality": TestSetModalityType,
+        "status": TestSetStatusType,
+        "roleArn": str,
+        "numTurns": int,
+        "storageLocation": TestSetStorageLocationTypeDef,
+        "creationDateTime": datetime,
+        "lastUpdatedDateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DialogStateTypeDef = TypedDict(
     "DialogStateTypeDef",
     {
         "dialogAction": DialogActionTypeDef,
         "intent": IntentOverrideTypeDef,
         "sessionAttributes": Mapping[str, str],
     },
     total=False,
 )
 
+ExportResourceSpecificationTypeDef = TypedDict(
+    "ExportResourceSpecificationTypeDef",
+    {
+        "botExportSpecification": BotExportSpecificationTypeDef,
+        "botLocaleExportSpecification": BotLocaleExportSpecificationTypeDef,
+        "customVocabularyExportSpecification": CustomVocabularyExportSpecificationTypeDef,
+        "testSetExportSpecification": TestSetExportSpecificationTypeDef,
+    },
+    total=False,
+)
+
 ListExportsRequestRequestTypeDef = TypedDict(
     "ListExportsRequestRequestTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "sortBy": ExportSortByTypeDef,
         "filters": Sequence[ExportFilterTypeDef],
@@ -2839,15 +3545,34 @@
     "ListImportsResponseTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "importSummaries": List[ImportSummaryTypeDef],
         "nextToken": str,
         "localeId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+InputSessionStateSpecificationTypeDef = TypedDict(
+    "InputSessionStateSpecificationTypeDef",
+    {
+        "sessionAttributes": Dict[str, str],
+        "activeContexts": List[ActiveContextTypeDef],
+        "runtimeHints": RuntimeHintsTypeDef,
+    },
+    total=False,
+)
+
+IntentClassificationTestResultItemTypeDef = TypedDict(
+    "IntentClassificationTestResultItemTypeDef",
+    {
+        "intentName": str,
+        "multiTurnConversation": bool,
+        "resultCounts": IntentClassificationTestResultItemCountsTypeDef,
     },
 )
 
 _RequiredListIntentsRequestRequestTypeDef = TypedDict(
     "_RequiredListIntentsRequestRequestTypeDef",
     {
         "botId": str,
@@ -2862,29 +3587,31 @@
         "filters": Sequence[IntentFilterTypeDef],
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+
 class ListIntentsRequestRequestTypeDef(
     _RequiredListIntentsRequestRequestTypeDef, _OptionalListIntentsRequestRequestTypeDef
 ):
     pass
 
+
 ListRecommendedIntentsResponseTypeDef = TypedDict(
     "ListRecommendedIntentsResponseTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
         "botRecommendationId": str,
         "summaryList": List[RecommendedIntentSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredListSlotTypesRequestRequestTypeDef = TypedDict(
     "_RequiredListSlotTypesRequestRequestTypeDef",
     {
         "botId": str,
@@ -2899,28 +3626,30 @@
         "filters": Sequence[SlotTypeFilterTypeDef],
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+
 class ListSlotTypesRequestRequestTypeDef(
     _RequiredListSlotTypesRequestRequestTypeDef, _OptionalListSlotTypesRequestRequestTypeDef
 ):
     pass
 
+
 ListSlotTypesResponseTypeDef = TypedDict(
     "ListSlotTypesResponseTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
         "slotTypeSummaries": List[SlotTypeSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredListSlotsRequestRequestTypeDef = TypedDict(
     "_RequiredListSlotsRequestRequestTypeDef",
     {
         "botId": str,
@@ -2936,26 +3665,64 @@
         "filters": Sequence[SlotFilterTypeDef],
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+
 class ListSlotsRequestRequestTypeDef(
     _RequiredListSlotsRequestRequestTypeDef, _OptionalListSlotsRequestRequestTypeDef
 ):
     pass
 
+
+ListTestExecutionsRequestRequestTypeDef = TypedDict(
+    "ListTestExecutionsRequestRequestTypeDef",
+    {
+        "sortBy": TestExecutionSortByTypeDef,
+        "maxResults": int,
+        "nextToken": str,
+    },
+    total=False,
+)
+
+ListTestSetsRequestRequestTypeDef = TypedDict(
+    "ListTestSetsRequestRequestTypeDef",
+    {
+        "sortBy": TestSetSortByTypeDef,
+        "maxResults": int,
+        "nextToken": str,
+    },
+    total=False,
+)
+
+OverallTestResultsTypeDef = TypedDict(
+    "OverallTestResultsTypeDef",
+    {
+        "items": List[OverallTestResultItemTypeDef],
+    },
+)
+
 UtteranceAggregationDurationTypeDef = TypedDict(
     "UtteranceAggregationDurationTypeDef",
     {
         "relativeAggregationDuration": RelativeAggregationDurationTypeDef,
     },
 )
 
+RuntimeHintDetailsTypeDef = TypedDict(
+    "RuntimeHintDetailsTypeDef",
+    {
+        "runtimeHintValues": List[RuntimeHintValueTypeDef],
+        "subSlotHints": Dict[str, Dict[str, Any]],
+    },
+    total=False,
+)
+
 SlotTypeValueTypeDef = TypedDict(
     "SlotTypeValueTypeDef",
     {
         "sampleValue": SampleValueTypeDef,
         "synonyms": Sequence[SampleValueTypeDef],
     },
     total=False,
@@ -2964,14 +3731,22 @@
 SlotDefaultValueSpecificationTypeDef = TypedDict(
     "SlotDefaultValueSpecificationTypeDef",
     {
         "defaultValueList": Sequence[SlotDefaultValueTypeDef],
     },
 )
 
+SlotResolutionTestResultItemTypeDef = TypedDict(
+    "SlotResolutionTestResultItemTypeDef",
+    {
+        "slotName": str,
+        "resultCounts": SlotResolutionTestResultItemCountsTypeDef,
+    },
+)
+
 SlotValueOverrideTypeDef = TypedDict(
     "SlotValueOverrideTypeDef",
     {
         "shape": SlotShapeType,
         "value": SlotValueTypeDef,
         "values": Sequence[Dict[str, Any]],
     },
@@ -2989,19 +3764,95 @@
     {
         "regexFilter": SlotValueRegexFilterTypeDef,
         "advancedRecognitionSetting": AdvancedRecognitionSettingTypeDef,
     },
     total=False,
 )
 
+
 class SlotValueSelectionSettingTypeDef(
     _RequiredSlotValueSelectionSettingTypeDef, _OptionalSlotValueSelectionSettingTypeDef
 ):
     pass
 
+
+TestSetDiscrepancyErrorsTypeDef = TypedDict(
+    "TestSetDiscrepancyErrorsTypeDef",
+    {
+        "intentDiscrepancies": List[TestSetIntentDiscrepancyItemTypeDef],
+        "slotDiscrepancies": List[TestSetSlotDiscrepancyItemTypeDef],
+    },
+)
+
+TestSetDiscrepancyReportResourceTargetTypeDef = TypedDict(
+    "TestSetDiscrepancyReportResourceTargetTypeDef",
+    {
+        "botAliasTarget": TestSetDiscrepancyReportBotAliasTargetTypeDef,
+    },
+    total=False,
+)
+
+_RequiredTestSetImportResourceSpecificationTypeDef = TypedDict(
+    "_RequiredTestSetImportResourceSpecificationTypeDef",
+    {
+        "testSetName": str,
+        "roleArn": str,
+        "storageLocation": TestSetStorageLocationTypeDef,
+        "importInputLocation": TestSetImportInputLocationTypeDef,
+        "modality": TestSetModalityType,
+    },
+)
+_OptionalTestSetImportResourceSpecificationTypeDef = TypedDict(
+    "_OptionalTestSetImportResourceSpecificationTypeDef",
+    {
+        "description": str,
+        "testSetTags": Dict[str, str],
+    },
+    total=False,
+)
+
+
+class TestSetImportResourceSpecificationTypeDef(
+    _RequiredTestSetImportResourceSpecificationTypeDef,
+    _OptionalTestSetImportResourceSpecificationTypeDef,
+):
+    pass
+
+
+_RequiredUserTurnOutputSpecificationTypeDef = TypedDict(
+    "_RequiredUserTurnOutputSpecificationTypeDef",
+    {
+        "intent": UserTurnIntentOutputTypeDef,
+    },
+)
+_OptionalUserTurnOutputSpecificationTypeDef = TypedDict(
+    "_OptionalUserTurnOutputSpecificationTypeDef",
+    {
+        "activeContexts": List[ActiveContextTypeDef],
+        "transcript": str,
+    },
+    total=False,
+)
+
+
+class UserTurnOutputSpecificationTypeDef(
+    _RequiredUserTurnOutputSpecificationTypeDef, _OptionalUserTurnOutputSpecificationTypeDef
+):
+    pass
+
+
+UtteranceInputSpecificationTypeDef = TypedDict(
+    "UtteranceInputSpecificationTypeDef",
+    {
+        "textInput": str,
+        "audioInput": UtteranceAudioInputSpecificationTypeDef,
+    },
+    total=False,
+)
+
 _RequiredPromptAttemptSpecificationTypeDef = TypedDict(
     "_RequiredPromptAttemptSpecificationTypeDef",
     {
         "allowedInputTypes": AllowedInputTypesTypeDef,
     },
 )
 _OptionalPromptAttemptSpecificationTypeDef = TypedDict(
@@ -3010,33 +3861,95 @@
         "allowInterrupt": bool,
         "audioAndDTMFInputSpecification": AudioAndDTMFInputSpecificationTypeDef,
         "textInputSpecification": TextInputSpecificationTypeDef,
     },
     total=False,
 )
 
+
 class PromptAttemptSpecificationTypeDef(
     _RequiredPromptAttemptSpecificationTypeDef, _OptionalPromptAttemptSpecificationTypeDef
 ):
     pass
 
+
 AudioLogSettingTypeDef = TypedDict(
     "AudioLogSettingTypeDef",
     {
         "enabled": bool,
         "destination": AudioLogDestinationTypeDef,
     },
 )
 
-ImportResourceSpecificationTypeDef = TypedDict(
-    "ImportResourceSpecificationTypeDef",
+DescribeTestExecutionResponseTypeDef = TypedDict(
+    "DescribeTestExecutionResponseTypeDef",
     {
-        "botImportSpecification": BotImportSpecificationTypeDef,
-        "botLocaleImportSpecification": BotLocaleImportSpecificationTypeDef,
-        "customVocabularyImportSpecification": CustomVocabularyImportSpecificationTypeDef,
+        "testExecutionId": str,
+        "creationDateTime": datetime,
+        "lastUpdatedDateTime": datetime,
+        "testExecutionStatus": TestExecutionStatusType,
+        "testSetId": str,
+        "testSetName": str,
+        "target": TestExecutionTargetTypeDef,
+        "apiMode": TestExecutionApiModeType,
+        "testExecutionModality": TestExecutionModalityType,
+        "failureReasons": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredStartTestExecutionRequestRequestTypeDef = TypedDict(
+    "_RequiredStartTestExecutionRequestRequestTypeDef",
+    {
+        "testSetId": str,
+        "target": TestExecutionTargetTypeDef,
+        "apiMode": TestExecutionApiModeType,
+    },
+)
+_OptionalStartTestExecutionRequestRequestTypeDef = TypedDict(
+    "_OptionalStartTestExecutionRequestRequestTypeDef",
+    {
+        "testExecutionModality": TestExecutionModalityType,
+    },
+    total=False,
+)
+
+
+class StartTestExecutionRequestRequestTypeDef(
+    _RequiredStartTestExecutionRequestRequestTypeDef,
+    _OptionalStartTestExecutionRequestRequestTypeDef,
+):
+    pass
+
+
+StartTestExecutionResponseTypeDef = TypedDict(
+    "StartTestExecutionResponseTypeDef",
+    {
+        "testExecutionId": str,
+        "creationDateTime": datetime,
+        "testSetId": str,
+        "target": TestExecutionTargetTypeDef,
+        "apiMode": TestExecutionApiModeType,
+        "testExecutionModality": TestExecutionModalityType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+TestExecutionSummaryTypeDef = TypedDict(
+    "TestExecutionSummaryTypeDef",
+    {
+        "testExecutionId": str,
+        "creationDateTime": datetime,
+        "lastUpdatedDateTime": datetime,
+        "testExecutionStatus": TestExecutionStatusType,
+        "testSetId": str,
+        "testSetName": str,
+        "target": TestExecutionTargetTypeDef,
+        "apiMode": TestExecutionApiModeType,
+        "testExecutionModality": TestExecutionModalityType,
     },
     total=False,
 )
 
 BotRecommendationResultsTypeDef = TypedDict(
     "BotRecommendationResultsTypeDef",
     {
@@ -3076,28 +3989,86 @@
     "_OptionalBotAliasLocaleSettingsTypeDef",
     {
         "codeHookSpecification": CodeHookSpecificationTypeDef,
     },
     total=False,
 )
 
+
 class BotAliasLocaleSettingsTypeDef(
     _RequiredBotAliasLocaleSettingsTypeDef, _OptionalBotAliasLocaleSettingsTypeDef
 ):
     pass
 
+
+ConversationLevelTestResultsTypeDef = TypedDict(
+    "ConversationLevelTestResultsTypeDef",
+    {
+        "items": List[ConversationLevelTestResultItemTypeDef],
+    },
+)
+
+_RequiredListTestExecutionResultItemsRequestRequestTypeDef = TypedDict(
+    "_RequiredListTestExecutionResultItemsRequestRequestTypeDef",
+    {
+        "testExecutionId": str,
+        "resultFilterBy": TestExecutionResultFilterByTypeDef,
+    },
+)
+_OptionalListTestExecutionResultItemsRequestRequestTypeDef = TypedDict(
+    "_OptionalListTestExecutionResultItemsRequestRequestTypeDef",
+    {
+        "maxResults": int,
+        "nextToken": str,
+    },
+    total=False,
+)
+
+
+class ListTestExecutionResultItemsRequestRequestTypeDef(
+    _RequiredListTestExecutionResultItemsRequestRequestTypeDef,
+    _OptionalListTestExecutionResultItemsRequestRequestTypeDef,
+):
+    pass
+
+
+TestSetGenerationDataSourceTypeDef = TypedDict(
+    "TestSetGenerationDataSourceTypeDef",
+    {
+        "conversationLogsDataSource": ConversationLogsDataSourceTypeDef,
+    },
+    total=False,
+)
+
 ListIntentsResponseTypeDef = TypedDict(
     "ListIntentsResponseTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
         "intentSummaries": List[IntentSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+TranscriptFilterTypeDef = TypedDict(
+    "TranscriptFilterTypeDef",
+    {
+        "lexTranscriptFilter": LexTranscriptFilterTypeDef,
+    },
+    total=False,
+)
+
+ListTestSetsResponseTypeDef = TypedDict(
+    "ListTestSetsResponseTypeDef",
+    {
+        "testSets": List[TestSetSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateExportRequestRequestTypeDef = TypedDict(
     "_RequiredCreateExportRequestRequestTypeDef",
     {
         "resourceSpecification": ExportResourceSpecificationTypeDef,
@@ -3108,43 +4079,45 @@
     "_OptionalCreateExportRequestRequestTypeDef",
     {
         "filePassword": str,
     },
     total=False,
 )
 
+
 class CreateExportRequestRequestTypeDef(
     _RequiredCreateExportRequestRequestTypeDef, _OptionalCreateExportRequestRequestTypeDef
 ):
     pass
 
+
 CreateExportResponseTypeDef = TypedDict(
     "CreateExportResponseTypeDef",
     {
         "exportId": str,
         "resourceSpecification": ExportResourceSpecificationTypeDef,
         "fileFormat": ImportExportFileFormatType,
         "exportStatus": ExportStatusType,
         "creationDateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeExportResponseTypeDef = TypedDict(
     "DescribeExportResponseTypeDef",
     {
         "exportId": str,
         "resourceSpecification": ExportResourceSpecificationTypeDef,
         "fileFormat": ImportExportFileFormatType,
         "exportStatus": ExportStatusType,
         "failureReasons": List[str],
         "downloadUrl": str,
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ExportSummaryTypeDef = TypedDict(
     "ExportSummaryTypeDef",
     {
         "exportId": str,
@@ -3162,32 +4135,31 @@
     {
         "exportId": str,
         "resourceSpecification": ExportResourceSpecificationTypeDef,
         "fileFormat": ImportExportFileFormatType,
         "exportStatus": ExportStatusType,
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-TranscriptFilterTypeDef = TypedDict(
-    "TranscriptFilterTypeDef",
+ExternalSourceSettingTypeDef = TypedDict(
+    "ExternalSourceSettingTypeDef",
     {
-        "lexTranscriptFilter": LexTranscriptFilterTypeDef,
+        "grammarSlotTypeSetting": GrammarSlotTypeSettingTypeDef,
     },
     total=False,
 )
 
-ExternalSourceSettingTypeDef = TypedDict(
-    "ExternalSourceSettingTypeDef",
+IntentClassificationTestResultsTypeDef = TypedDict(
+    "IntentClassificationTestResultsTypeDef",
     {
-        "grammarSlotTypeSetting": GrammarSlotTypeSettingTypeDef,
+        "items": List[IntentClassificationTestResultItemTypeDef],
     },
-    total=False,
 )
 
 _RequiredListAggregatedUtterancesRequestRequestTypeDef = TypedDict(
     "_RequiredListAggregatedUtterancesRequestRequestTypeDef",
     {
         "botId": str,
         "localeId": str,
@@ -3203,83 +4175,122 @@
         "filters": Sequence[AggregatedUtterancesFilterTypeDef],
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+
 class ListAggregatedUtterancesRequestRequestTypeDef(
     _RequiredListAggregatedUtterancesRequestRequestTypeDef,
     _OptionalListAggregatedUtterancesRequestRequestTypeDef,
 ):
     pass
 
+
 ListAggregatedUtterancesResponseTypeDef = TypedDict(
     "ListAggregatedUtterancesResponseTypeDef",
     {
         "botId": str,
         "botAliasId": str,
         "botVersion": str,
         "localeId": str,
         "aggregationDuration": UtteranceAggregationDurationTypeDef,
         "aggregationWindowStartTime": datetime,
         "aggregationWindowEndTime": datetime,
         "aggregationLastRefreshedDateTime": datetime,
         "aggregatedUtterancesSummaries": List[AggregatedUtterancesSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DescribeImportResponseTypeDef = TypedDict(
-    "DescribeImportResponseTypeDef",
+IntentLevelSlotResolutionTestResultItemTypeDef = TypedDict(
+    "IntentLevelSlotResolutionTestResultItemTypeDef",
     {
-        "importId": str,
-        "resourceSpecification": ImportResourceSpecificationTypeDef,
-        "importedResourceId": str,
-        "importedResourceName": str,
-        "mergeStrategy": MergeStrategyType,
-        "importStatus": ImportStatusType,
-        "failureReasons": List[str],
+        "intentName": str,
+        "multiTurnConversation": bool,
+        "slotResolutionResults": List[SlotResolutionTestResultItemTypeDef],
+    },
+)
+
+CreateTestSetDiscrepancyReportRequestRequestTypeDef = TypedDict(
+    "CreateTestSetDiscrepancyReportRequestRequestTypeDef",
+    {
+        "testSetId": str,
+        "target": TestSetDiscrepancyReportResourceTargetTypeDef,
+    },
+)
+
+CreateTestSetDiscrepancyReportResponseTypeDef = TypedDict(
+    "CreateTestSetDiscrepancyReportResponseTypeDef",
+    {
+        "testSetDiscrepancyReportId": str,
         "creationDateTime": datetime,
-        "lastUpdatedDateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "testSetId": str,
+        "target": TestSetDiscrepancyReportResourceTargetTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-_RequiredStartImportRequestRequestTypeDef = TypedDict(
-    "_RequiredStartImportRequestRequestTypeDef",
+DescribeTestSetDiscrepancyReportResponseTypeDef = TypedDict(
+    "DescribeTestSetDiscrepancyReportResponseTypeDef",
     {
-        "importId": str,
-        "resourceSpecification": ImportResourceSpecificationTypeDef,
-        "mergeStrategy": MergeStrategyType,
+        "testSetDiscrepancyReportId": str,
+        "testSetId": str,
+        "creationDateTime": datetime,
+        "target": TestSetDiscrepancyReportResourceTargetTypeDef,
+        "testSetDiscrepancyReportStatus": TestSetDiscrepancyReportStatusType,
+        "lastUpdatedDataTime": datetime,
+        "testSetDiscrepancyTopErrors": TestSetDiscrepancyErrorsTypeDef,
+        "testSetDiscrepancyRawOutputUrl": str,
+        "failureReasons": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalStartImportRequestRequestTypeDef = TypedDict(
-    "_OptionalStartImportRequestRequestTypeDef",
+
+ImportResourceSpecificationTypeDef = TypedDict(
+    "ImportResourceSpecificationTypeDef",
     {
-        "filePassword": str,
+        "botImportSpecification": BotImportSpecificationTypeDef,
+        "botLocaleImportSpecification": BotLocaleImportSpecificationTypeDef,
+        "customVocabularyImportSpecification": CustomVocabularyImportSpecificationTypeDef,
+        "testSetImportResourceSpecification": TestSetImportResourceSpecificationTypeDef,
     },
     total=False,
 )
 
-class StartImportRequestRequestTypeDef(
-    _RequiredStartImportRequestRequestTypeDef, _OptionalStartImportRequestRequestTypeDef
+_RequiredUserTurnInputSpecificationTypeDef = TypedDict(
+    "_RequiredUserTurnInputSpecificationTypeDef",
+    {
+        "utteranceInput": UtteranceInputSpecificationTypeDef,
+    },
+)
+_OptionalUserTurnInputSpecificationTypeDef = TypedDict(
+    "_OptionalUserTurnInputSpecificationTypeDef",
+    {
+        "requestAttributes": Dict[str, str],
+        "sessionState": InputSessionStateSpecificationTypeDef,
+    },
+    total=False,
+)
+
+
+class UserTurnInputSpecificationTypeDef(
+    _RequiredUserTurnInputSpecificationTypeDef, _OptionalUserTurnInputSpecificationTypeDef
 ):
     pass
 
-StartImportResponseTypeDef = TypedDict(
-    "StartImportResponseTypeDef",
+
+ListTestExecutionsResponseTypeDef = TypedDict(
+    "ListTestExecutionsResponseTypeDef",
     {
-        "importId": str,
-        "resourceSpecification": ImportResourceSpecificationTypeDef,
-        "mergeStrategy": MergeStrategyType,
-        "importStatus": ImportStatusType,
-        "creationDateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "testExecutions": List[TestExecutionSummaryTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredMessageGroupTypeDef = TypedDict(
     "_RequiredMessageGroupTypeDef",
     {
         "message": MessageTypeDef,
@@ -3289,35 +4300,85 @@
     "_OptionalMessageGroupTypeDef",
     {
         "variations": Sequence[MessageTypeDef],
     },
     total=False,
 )
 
+
 class MessageGroupTypeDef(_RequiredMessageGroupTypeDef, _OptionalMessageGroupTypeDef):
     pass
 
+
 ConversationLogSettingsTypeDef = TypedDict(
     "ConversationLogSettingsTypeDef",
     {
         "textLogSettings": Sequence[TextLogSettingTypeDef],
         "audioLogSettings": Sequence[AudioLogSettingTypeDef],
     },
     total=False,
 )
 
-ListExportsResponseTypeDef = TypedDict(
-    "ListExportsResponseTypeDef",
+DescribeTestSetGenerationResponseTypeDef = TypedDict(
+    "DescribeTestSetGenerationResponseTypeDef",
     {
-        "botId": str,
-        "botVersion": str,
-        "exportSummaries": List[ExportSummaryTypeDef],
-        "nextToken": str,
-        "localeId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "testSetGenerationId": str,
+        "testSetGenerationStatus": TestSetGenerationStatusType,
+        "failureReasons": List[str],
+        "testSetId": str,
+        "testSetName": str,
+        "description": str,
+        "storageLocation": TestSetStorageLocationTypeDef,
+        "generationDataSource": TestSetGenerationDataSourceTypeDef,
+        "roleArn": str,
+        "creationDateTime": datetime,
+        "lastUpdatedDateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredStartTestSetGenerationRequestRequestTypeDef = TypedDict(
+    "_RequiredStartTestSetGenerationRequestRequestTypeDef",
+    {
+        "testSetName": str,
+        "storageLocation": TestSetStorageLocationTypeDef,
+        "generationDataSource": TestSetGenerationDataSourceTypeDef,
+        "roleArn": str,
+    },
+)
+_OptionalStartTestSetGenerationRequestRequestTypeDef = TypedDict(
+    "_OptionalStartTestSetGenerationRequestRequestTypeDef",
+    {
+        "description": str,
+        "testSetTags": Mapping[str, str],
+    },
+    total=False,
+)
+
+
+class StartTestSetGenerationRequestRequestTypeDef(
+    _RequiredStartTestSetGenerationRequestRequestTypeDef,
+    _OptionalStartTestSetGenerationRequestRequestTypeDef,
+):
+    pass
+
+
+StartTestSetGenerationResponseTypeDef = TypedDict(
+    "StartTestSetGenerationResponseTypeDef",
+    {
+        "testSetGenerationId": str,
+        "creationDateTime": datetime,
+        "testSetGenerationStatus": TestSetGenerationStatusType,
+        "testSetName": str,
+        "description": str,
+        "storageLocation": TestSetStorageLocationTypeDef,
+        "generationDataSource": TestSetGenerationDataSourceTypeDef,
+        "roleArn": str,
+        "testSetTags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredS3BucketTranscriptSourceTypeDef = TypedDict(
     "_RequiredS3BucketTranscriptSourceTypeDef",
     {
         "s3BucketName": str,
@@ -3330,19 +4391,33 @@
         "pathFormat": PathFormatTypeDef,
         "transcriptFilter": TranscriptFilterTypeDef,
         "kmsKeyArn": str,
     },
     total=False,
 )
 
+
 class S3BucketTranscriptSourceTypeDef(
     _RequiredS3BucketTranscriptSourceTypeDef, _OptionalS3BucketTranscriptSourceTypeDef
 ):
     pass
 
+
+ListExportsResponseTypeDef = TypedDict(
+    "ListExportsResponseTypeDef",
+    {
+        "botId": str,
+        "botVersion": str,
+        "exportSummaries": List[ExportSummaryTypeDef],
+        "nextToken": str,
+        "localeId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateSlotTypeRequestRequestTypeDef = TypedDict(
     "_RequiredCreateSlotTypeRequestRequestTypeDef",
     {
         "slotTypeName": str,
         "botId": str,
         "botVersion": str,
         "localeId": str,
@@ -3357,19 +4432,21 @@
         "parentSlotTypeSignature": str,
         "externalSourceSetting": ExternalSourceSettingTypeDef,
         "compositeSlotTypeSetting": CompositeSlotTypeSettingTypeDef,
     },
     total=False,
 )
 
+
 class CreateSlotTypeRequestRequestTypeDef(
     _RequiredCreateSlotTypeRequestRequestTypeDef, _OptionalCreateSlotTypeRequestRequestTypeDef
 ):
     pass
 
+
 CreateSlotTypeResponseTypeDef = TypedDict(
     "CreateSlotTypeResponseTypeDef",
     {
         "slotTypeId": str,
         "slotTypeName": str,
         "description": str,
         "slotTypeValues": List[SlotTypeValueTypeDef],
@@ -3377,15 +4454,15 @@
         "parentSlotTypeSignature": str,
         "botId": str,
         "botVersion": str,
         "localeId": str,
         "creationDateTime": datetime,
         "externalSourceSetting": ExternalSourceSettingTypeDef,
         "compositeSlotTypeSetting": CompositeSlotTypeSettingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSlotTypeResponseTypeDef = TypedDict(
     "DescribeSlotTypeResponseTypeDef",
     {
         "slotTypeId": str,
@@ -3397,15 +4474,15 @@
         "botId": str,
         "botVersion": str,
         "localeId": str,
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
         "externalSourceSetting": ExternalSourceSettingTypeDef,
         "compositeSlotTypeSetting": CompositeSlotTypeSettingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateSlotTypeRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateSlotTypeRequestRequestTypeDef",
     {
         "slotTypeId": str,
@@ -3424,19 +4501,21 @@
         "parentSlotTypeSignature": str,
         "externalSourceSetting": ExternalSourceSettingTypeDef,
         "compositeSlotTypeSetting": CompositeSlotTypeSettingTypeDef,
     },
     total=False,
 )
 
+
 class UpdateSlotTypeRequestRequestTypeDef(
     _RequiredUpdateSlotTypeRequestRequestTypeDef, _OptionalUpdateSlotTypeRequestRequestTypeDef
 ):
     pass
 
+
 UpdateSlotTypeResponseTypeDef = TypedDict(
     "UpdateSlotTypeResponseTypeDef",
     {
         "slotTypeId": str,
         "slotTypeName": str,
         "description": str,
         "slotTypeValues": List[SlotTypeValueTypeDef],
@@ -3445,15 +4524,107 @@
         "botId": str,
         "botVersion": str,
         "localeId": str,
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
         "externalSourceSetting": ExternalSourceSettingTypeDef,
         "compositeSlotTypeSetting": CompositeSlotTypeSettingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+IntentLevelSlotResolutionTestResultsTypeDef = TypedDict(
+    "IntentLevelSlotResolutionTestResultsTypeDef",
+    {
+        "items": List[IntentLevelSlotResolutionTestResultItemTypeDef],
+    },
+)
+
+DescribeImportResponseTypeDef = TypedDict(
+    "DescribeImportResponseTypeDef",
+    {
+        "importId": str,
+        "resourceSpecification": ImportResourceSpecificationTypeDef,
+        "importedResourceId": str,
+        "importedResourceName": str,
+        "mergeStrategy": MergeStrategyType,
+        "importStatus": ImportStatusType,
+        "failureReasons": List[str],
+        "creationDateTime": datetime,
+        "lastUpdatedDateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredStartImportRequestRequestTypeDef = TypedDict(
+    "_RequiredStartImportRequestRequestTypeDef",
+    {
+        "importId": str,
+        "resourceSpecification": ImportResourceSpecificationTypeDef,
+        "mergeStrategy": MergeStrategyType,
+    },
+)
+_OptionalStartImportRequestRequestTypeDef = TypedDict(
+    "_OptionalStartImportRequestRequestTypeDef",
+    {
+        "filePassword": str,
+    },
+    total=False,
+)
+
+
+class StartImportRequestRequestTypeDef(
+    _RequiredStartImportRequestRequestTypeDef, _OptionalStartImportRequestRequestTypeDef
+):
+    pass
+
+
+StartImportResponseTypeDef = TypedDict(
+    "StartImportResponseTypeDef",
+    {
+        "importId": str,
+        "resourceSpecification": ImportResourceSpecificationTypeDef,
+        "mergeStrategy": MergeStrategyType,
+        "importStatus": ImportStatusType,
+        "creationDateTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredUserTurnResultTypeDef = TypedDict(
+    "_RequiredUserTurnResultTypeDef",
+    {
+        "input": UserTurnInputSpecificationTypeDef,
+        "expectedOutput": UserTurnOutputSpecificationTypeDef,
+    },
+)
+_OptionalUserTurnResultTypeDef = TypedDict(
+    "_OptionalUserTurnResultTypeDef",
+    {
+        "actualOutput": UserTurnOutputSpecificationTypeDef,
+        "errorDetails": ExecutionErrorDetailsTypeDef,
+        "endToEndResult": TestResultMatchStatusType,
+        "intentMatchResult": TestResultMatchStatusType,
+        "slotMatchResult": TestResultMatchStatusType,
+        "speechTranscriptionResult": TestResultMatchStatusType,
+        "conversationLevelResult": ConversationLevelResultDetailTypeDef,
+    },
+    total=False,
+)
+
+
+class UserTurnResultTypeDef(_RequiredUserTurnResultTypeDef, _OptionalUserTurnResultTypeDef):
+    pass
+
+
+UserTurnSpecificationTypeDef = TypedDict(
+    "UserTurnSpecificationTypeDef",
+    {
+        "input": UserTurnInputSpecificationTypeDef,
+        "expected": UserTurnOutputSpecificationTypeDef,
     },
 )
 
 _RequiredFulfillmentStartResponseSpecificationTypeDef = TypedDict(
     "_RequiredFulfillmentStartResponseSpecificationTypeDef",
     {
         "delayInSeconds": int,
@@ -3464,20 +4635,22 @@
     "_OptionalFulfillmentStartResponseSpecificationTypeDef",
     {
         "allowInterrupt": bool,
     },
     total=False,
 )
 
+
 class FulfillmentStartResponseSpecificationTypeDef(
     _RequiredFulfillmentStartResponseSpecificationTypeDef,
     _OptionalFulfillmentStartResponseSpecificationTypeDef,
 ):
     pass
 
+
 _RequiredFulfillmentUpdateResponseSpecificationTypeDef = TypedDict(
     "_RequiredFulfillmentUpdateResponseSpecificationTypeDef",
     {
         "frequencyInSeconds": int,
         "messageGroups": Sequence[MessageGroupTypeDef],
     },
 )
@@ -3485,20 +4658,22 @@
     "_OptionalFulfillmentUpdateResponseSpecificationTypeDef",
     {
         "allowInterrupt": bool,
     },
     total=False,
 )
 
+
 class FulfillmentUpdateResponseSpecificationTypeDef(
     _RequiredFulfillmentUpdateResponseSpecificationTypeDef,
     _OptionalFulfillmentUpdateResponseSpecificationTypeDef,
 ):
     pass
 
+
 _RequiredPromptSpecificationTypeDef = TypedDict(
     "_RequiredPromptSpecificationTypeDef",
     {
         "messageGroups": Sequence[MessageGroupTypeDef],
         "maxRetries": int,
     },
 )
@@ -3510,38 +4685,42 @@
         "promptAttemptsSpecification": Mapping[
             PromptAttemptType, PromptAttemptSpecificationTypeDef
         ],
     },
     total=False,
 )
 
+
 class PromptSpecificationTypeDef(
     _RequiredPromptSpecificationTypeDef, _OptionalPromptSpecificationTypeDef
 ):
     pass
 
+
 _RequiredResponseSpecificationTypeDef = TypedDict(
     "_RequiredResponseSpecificationTypeDef",
     {
         "messageGroups": Sequence[MessageGroupTypeDef],
     },
 )
 _OptionalResponseSpecificationTypeDef = TypedDict(
     "_OptionalResponseSpecificationTypeDef",
     {
         "allowInterrupt": bool,
     },
     total=False,
 )
 
+
 class ResponseSpecificationTypeDef(
     _RequiredResponseSpecificationTypeDef, _OptionalResponseSpecificationTypeDef
 ):
     pass
 
+
 _RequiredStillWaitingResponseSpecificationTypeDef = TypedDict(
     "_RequiredStillWaitingResponseSpecificationTypeDef",
     {
         "messageGroups": Sequence[MessageGroupTypeDef],
         "frequencyInSeconds": int,
         "timeoutInSeconds": int,
     },
@@ -3550,20 +4729,22 @@
     "_OptionalStillWaitingResponseSpecificationTypeDef",
     {
         "allowInterrupt": bool,
     },
     total=False,
 )
 
+
 class StillWaitingResponseSpecificationTypeDef(
     _RequiredStillWaitingResponseSpecificationTypeDef,
     _OptionalStillWaitingResponseSpecificationTypeDef,
 ):
     pass
 
+
 _RequiredCreateBotAliasRequestRequestTypeDef = TypedDict(
     "_RequiredCreateBotAliasRequestRequestTypeDef",
     {
         "botAliasName": str,
         "botId": str,
     },
 )
@@ -3576,34 +4757,36 @@
         "conversationLogSettings": ConversationLogSettingsTypeDef,
         "sentimentAnalysisSettings": SentimentAnalysisSettingsTypeDef,
         "tags": Mapping[str, str],
     },
     total=False,
 )
 
+
 class CreateBotAliasRequestRequestTypeDef(
     _RequiredCreateBotAliasRequestRequestTypeDef, _OptionalCreateBotAliasRequestRequestTypeDef
 ):
     pass
 
+
 CreateBotAliasResponseTypeDef = TypedDict(
     "CreateBotAliasResponseTypeDef",
     {
         "botAliasId": str,
         "botAliasName": str,
         "description": str,
         "botVersion": str,
         "botAliasLocaleSettings": Dict[str, BotAliasLocaleSettingsTypeDef],
         "conversationLogSettings": ConversationLogSettingsTypeDef,
         "sentimentAnalysisSettings": SentimentAnalysisSettingsTypeDef,
         "botAliasStatus": BotAliasStatusType,
         "botId": str,
         "creationDateTime": datetime,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeBotAliasResponseTypeDef = TypedDict(
     "DescribeBotAliasResponseTypeDef",
     {
         "botAliasId": str,
@@ -3615,15 +4798,15 @@
         "sentimentAnalysisSettings": SentimentAnalysisSettingsTypeDef,
         "botAliasHistoryEvents": List[BotAliasHistoryEventTypeDef],
         "botAliasStatus": BotAliasStatusType,
         "botId": str,
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
         "parentBotNetworks": List[ParentBotNetworkTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateBotAliasRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateBotAliasRequestRequestTypeDef",
     {
         "botAliasId": str,
@@ -3639,45 +4822,65 @@
         "botAliasLocaleSettings": Mapping[str, BotAliasLocaleSettingsTypeDef],
         "conversationLogSettings": ConversationLogSettingsTypeDef,
         "sentimentAnalysisSettings": SentimentAnalysisSettingsTypeDef,
     },
     total=False,
 )
 
+
 class UpdateBotAliasRequestRequestTypeDef(
     _RequiredUpdateBotAliasRequestRequestTypeDef, _OptionalUpdateBotAliasRequestRequestTypeDef
 ):
     pass
 
+
 UpdateBotAliasResponseTypeDef = TypedDict(
     "UpdateBotAliasResponseTypeDef",
     {
         "botAliasId": str,
         "botAliasName": str,
         "description": str,
         "botVersion": str,
         "botAliasLocaleSettings": Dict[str, BotAliasLocaleSettingsTypeDef],
         "conversationLogSettings": ConversationLogSettingsTypeDef,
         "sentimentAnalysisSettings": SentimentAnalysisSettingsTypeDef,
         "botAliasStatus": BotAliasStatusType,
         "botId": str,
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TranscriptSourceSettingTypeDef = TypedDict(
     "TranscriptSourceSettingTypeDef",
     {
         "s3BucketTranscriptSource": S3BucketTranscriptSourceTypeDef,
     },
     total=False,
 )
 
+TestSetTurnResultTypeDef = TypedDict(
+    "TestSetTurnResultTypeDef",
+    {
+        "agent": AgentTurnResultTypeDef,
+        "user": UserTurnResultTypeDef,
+    },
+    total=False,
+)
+
+TurnSpecificationTypeDef = TypedDict(
+    "TurnSpecificationTypeDef",
+    {
+        "agentTurn": AgentTurnSpecificationTypeDef,
+        "userTurn": UserTurnSpecificationTypeDef,
+    },
+    total=False,
+)
+
 _RequiredFulfillmentUpdatesSpecificationTypeDef = TypedDict(
     "_RequiredFulfillmentUpdatesSpecificationTypeDef",
     {
         "active": bool,
     },
 )
 _OptionalFulfillmentUpdatesSpecificationTypeDef = TypedDict(
@@ -3686,19 +4889,21 @@
         "startResponse": FulfillmentStartResponseSpecificationTypeDef,
         "updateResponse": FulfillmentUpdateResponseSpecificationTypeDef,
         "timeoutInSeconds": int,
     },
     total=False,
 )
 
+
 class FulfillmentUpdatesSpecificationTypeDef(
     _RequiredFulfillmentUpdatesSpecificationTypeDef, _OptionalFulfillmentUpdatesSpecificationTypeDef
 ):
     pass
 
+
 SlotSummaryTypeDef = TypedDict(
     "SlotSummaryTypeDef",
     {
         "slotId": str,
         "slotName": str,
         "description": str,
         "slotConstraint": SlotConstraintType,
@@ -3721,19 +4926,21 @@
     "_OptionalConditionalBranchTypeDef",
     {
         "response": ResponseSpecificationTypeDef,
     },
     total=False,
 )
 
+
 class ConditionalBranchTypeDef(
     _RequiredConditionalBranchTypeDef, _OptionalConditionalBranchTypeDef
 ):
     pass
 
+
 DefaultConditionalBranchTypeDef = TypedDict(
     "DefaultConditionalBranchTypeDef",
     {
         "nextStep": DialogStateTypeDef,
         "response": ResponseSpecificationTypeDef,
     },
     total=False,
@@ -3751,34 +4958,36 @@
     {
         "stillWaitingResponse": StillWaitingResponseSpecificationTypeDef,
         "active": bool,
     },
     total=False,
 )
 
+
 class WaitAndContinueSpecificationTypeDef(
     _RequiredWaitAndContinueSpecificationTypeDef, _OptionalWaitAndContinueSpecificationTypeDef
 ):
     pass
 
+
 DescribeBotRecommendationResponseTypeDef = TypedDict(
     "DescribeBotRecommendationResponseTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
         "botRecommendationStatus": BotRecommendationStatusType,
         "botRecommendationId": str,
         "failureReasons": List[str],
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
         "transcriptSourceSetting": TranscriptSourceSettingTypeDef,
         "encryptionSetting": EncryptionSettingTypeDef,
         "botRecommendationResults": BotRecommendationResultsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStartBotRecommendationRequestRequestTypeDef = TypedDict(
     "_RequiredStartBotRecommendationRequestRequestTypeDef",
     {
         "botId": str,
@@ -3791,32 +5000,34 @@
     "_OptionalStartBotRecommendationRequestRequestTypeDef",
     {
         "encryptionSetting": EncryptionSettingTypeDef,
     },
     total=False,
 )
 
+
 class StartBotRecommendationRequestRequestTypeDef(
     _RequiredStartBotRecommendationRequestRequestTypeDef,
     _OptionalStartBotRecommendationRequestRequestTypeDef,
 ):
     pass
 
+
 StartBotRecommendationResponseTypeDef = TypedDict(
     "StartBotRecommendationResponseTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
         "botRecommendationStatus": BotRecommendationStatusType,
         "botRecommendationId": str,
         "creationDateTime": datetime,
         "transcriptSourceSetting": TranscriptSourceSettingTypeDef,
         "encryptionSetting": EncryptionSettingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateBotRecommendationResponseTypeDef = TypedDict(
     "UpdateBotRecommendationResponseTypeDef",
     {
         "botId": str,
@@ -3824,28 +5035,73 @@
         "localeId": str,
         "botRecommendationStatus": BotRecommendationStatusType,
         "botRecommendationId": str,
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
         "transcriptSourceSetting": TranscriptSourceSettingTypeDef,
         "encryptionSetting": EncryptionSettingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
+_RequiredUtteranceLevelTestResultItemTypeDef = TypedDict(
+    "_RequiredUtteranceLevelTestResultItemTypeDef",
+    {
+        "recordNumber": int,
+        "turnResult": TestSetTurnResultTypeDef,
+    },
+)
+_OptionalUtteranceLevelTestResultItemTypeDef = TypedDict(
+    "_OptionalUtteranceLevelTestResultItemTypeDef",
+    {
+        "conversationId": str,
+    },
+    total=False,
+)
+
+
+class UtteranceLevelTestResultItemTypeDef(
+    _RequiredUtteranceLevelTestResultItemTypeDef, _OptionalUtteranceLevelTestResultItemTypeDef
+):
+    pass
+
+
+_RequiredTestSetTurnRecordTypeDef = TypedDict(
+    "_RequiredTestSetTurnRecordTypeDef",
+    {
+        "recordNumber": int,
+        "turnSpecification": TurnSpecificationTypeDef,
+    },
+)
+_OptionalTestSetTurnRecordTypeDef = TypedDict(
+    "_OptionalTestSetTurnRecordTypeDef",
+    {
+        "conversationId": str,
+        "turnNumber": int,
+    },
+    total=False,
+)
+
+
+class TestSetTurnRecordTypeDef(
+    _RequiredTestSetTurnRecordTypeDef, _OptionalTestSetTurnRecordTypeDef
+):
+    pass
+
+
 ListSlotsResponseTypeDef = TypedDict(
     "ListSlotsResponseTypeDef",
     {
         "botId": str,
         "botVersion": str,
         "localeId": str,
         "intentId": str,
         "slotSummaries": List[SlotSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ConditionalSpecificationTypeDef = TypedDict(
     "ConditionalSpecificationTypeDef",
     {
         "active": bool,
@@ -3866,19 +5122,37 @@
         "defaultValueSpecification": SlotDefaultValueSpecificationTypeDef,
         "sampleUtterances": Sequence[SampleUtteranceTypeDef],
         "waitAndContinueSpecification": WaitAndContinueSpecificationTypeDef,
     },
     total=False,
 )
 
+
 class SubSlotValueElicitationSettingTypeDef(
     _RequiredSubSlotValueElicitationSettingTypeDef, _OptionalSubSlotValueElicitationSettingTypeDef
 ):
     pass
 
+
+UtteranceLevelTestResultsTypeDef = TypedDict(
+    "UtteranceLevelTestResultsTypeDef",
+    {
+        "items": List[UtteranceLevelTestResultItemTypeDef],
+    },
+)
+
+ListTestSetRecordsResponseTypeDef = TypedDict(
+    "ListTestSetRecordsResponseTypeDef",
+    {
+        "testSetRecords": List[TestSetTurnRecordTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 IntentClosingSettingTypeDef = TypedDict(
     "IntentClosingSettingTypeDef",
     {
         "closingResponse": ResponseSpecificationTypeDef,
         "active": bool,
         "nextStep": DialogStateTypeDef,
         "conditional": ConditionalSpecificationTypeDef,
@@ -3922,14 +5196,26 @@
     "SpecificationsTypeDef",
     {
         "slotTypeId": str,
         "valueElicitationSetting": SubSlotValueElicitationSettingTypeDef,
     },
 )
 
+TestExecutionResultItemsTypeDef = TypedDict(
+    "TestExecutionResultItemsTypeDef",
+    {
+        "overallTestResults": OverallTestResultsTypeDef,
+        "conversationLevelTestResults": ConversationLevelTestResultsTypeDef,
+        "intentClassificationTestResults": IntentClassificationTestResultsTypeDef,
+        "intentLevelSlotResolutionTestResults": IntentLevelSlotResolutionTestResultsTypeDef,
+        "utteranceLevelTestResults": UtteranceLevelTestResultsTypeDef,
+    },
+    total=False,
+)
+
 _RequiredDialogCodeHookInvocationSettingTypeDef = TypedDict(
     "_RequiredDialogCodeHookInvocationSettingTypeDef",
     {
         "enableCodeHookInvocation": bool,
         "active": bool,
         "postCodeHookSpecification": PostDialogCodeHookInvocationSpecificationTypeDef,
     },
@@ -3938,19 +5224,21 @@
     "_OptionalDialogCodeHookInvocationSettingTypeDef",
     {
         "invocationLabel": str,
     },
     total=False,
 )
 
+
 class DialogCodeHookInvocationSettingTypeDef(
     _RequiredDialogCodeHookInvocationSettingTypeDef, _OptionalDialogCodeHookInvocationSettingTypeDef
 ):
     pass
 
+
 _RequiredFulfillmentCodeHookSettingsTypeDef = TypedDict(
     "_RequiredFulfillmentCodeHookSettingsTypeDef",
     {
         "enabled": bool,
     },
 )
 _OptionalFulfillmentCodeHookSettingsTypeDef = TypedDict(
@@ -3959,28 +5247,39 @@
         "postFulfillmentStatusSpecification": PostFulfillmentStatusSpecificationTypeDef,
         "fulfillmentUpdatesSpecification": FulfillmentUpdatesSpecificationTypeDef,
         "active": bool,
     },
     total=False,
 )
 
+
 class FulfillmentCodeHookSettingsTypeDef(
     _RequiredFulfillmentCodeHookSettingsTypeDef, _OptionalFulfillmentCodeHookSettingsTypeDef
 ):
     pass
 
+
 SubSlotSettingTypeDef = TypedDict(
     "SubSlotSettingTypeDef",
     {
         "expression": str,
         "slotSpecifications": Mapping[str, SpecificationsTypeDef],
     },
     total=False,
 )
 
+ListTestExecutionResultItemsResponseTypeDef = TypedDict(
+    "ListTestExecutionResultItemsResponseTypeDef",
+    {
+        "testExecutionResults": TestExecutionResultItemsTypeDef,
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 InitialResponseSettingTypeDef = TypedDict(
     "InitialResponseSettingTypeDef",
     {
         "initialResponse": ResponseSpecificationTypeDef,
         "nextStep": DialogStateTypeDef,
         "conditional": ConditionalSpecificationTypeDef,
         "codeHook": DialogCodeHookInvocationSettingTypeDef,
@@ -4009,19 +5308,21 @@
         "failureConditional": ConditionalSpecificationTypeDef,
         "codeHook": DialogCodeHookInvocationSettingTypeDef,
         "elicitationCodeHook": ElicitationCodeHookInvocationSettingTypeDef,
     },
     total=False,
 )
 
+
 class IntentConfirmationSettingTypeDef(
     _RequiredIntentConfirmationSettingTypeDef, _OptionalIntentConfirmationSettingTypeDef
 ):
     pass
 
+
 SlotCaptureSettingTypeDef = TypedDict(
     "SlotCaptureSettingTypeDef",
     {
         "captureResponse": ResponseSpecificationTypeDef,
         "captureNextStep": DialogStateTypeDef,
         "captureConditional": ConditionalSpecificationTypeDef,
         "failureResponse": ResponseSpecificationTypeDef,
@@ -4056,19 +5357,21 @@
         "outputContexts": Sequence[OutputContextTypeDef],
         "kendraConfiguration": KendraConfigurationTypeDef,
         "initialResponseSetting": InitialResponseSettingTypeDef,
     },
     total=False,
 )
 
+
 class CreateIntentRequestRequestTypeDef(
     _RequiredCreateIntentRequestRequestTypeDef, _OptionalCreateIntentRequestRequestTypeDef
 ):
     pass
 
+
 CreateIntentResponseTypeDef = TypedDict(
     "CreateIntentResponseTypeDef",
     {
         "intentId": str,
         "intentName": str,
         "description": str,
         "parentIntentSignature": str,
@@ -4081,15 +5384,15 @@
         "outputContexts": List[OutputContextTypeDef],
         "kendraConfiguration": KendraConfigurationTypeDef,
         "botId": str,
         "botVersion": str,
         "localeId": str,
         "creationDateTime": datetime,
         "initialResponseSetting": InitialResponseSettingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeIntentResponseTypeDef = TypedDict(
     "DescribeIntentResponseTypeDef",
     {
         "intentId": str,
@@ -4107,15 +5410,15 @@
         "kendraConfiguration": KendraConfigurationTypeDef,
         "botId": str,
         "botVersion": str,
         "localeId": str,
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
         "initialResponseSetting": InitialResponseSettingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateIntentRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateIntentRequestRequestTypeDef",
     {
         "intentId": str,
@@ -4140,19 +5443,21 @@
         "outputContexts": Sequence[OutputContextTypeDef],
         "kendraConfiguration": KendraConfigurationTypeDef,
         "initialResponseSetting": InitialResponseSettingTypeDef,
     },
     total=False,
 )
 
+
 class UpdateIntentRequestRequestTypeDef(
     _RequiredUpdateIntentRequestRequestTypeDef, _OptionalUpdateIntentRequestRequestTypeDef
 ):
     pass
 
+
 UpdateIntentResponseTypeDef = TypedDict(
     "UpdateIntentResponseTypeDef",
     {
         "intentId": str,
         "intentName": str,
         "description": str,
         "parentIntentSignature": str,
@@ -4167,15 +5472,15 @@
         "kendraConfiguration": KendraConfigurationTypeDef,
         "botId": str,
         "botVersion": str,
         "localeId": str,
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
         "initialResponseSetting": InitialResponseSettingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSlotValueElicitationSettingTypeDef = TypedDict(
     "_RequiredSlotValueElicitationSettingTypeDef",
     {
         "slotConstraint": SlotConstraintType,
@@ -4189,19 +5494,21 @@
         "sampleUtterances": Sequence[SampleUtteranceTypeDef],
         "waitAndContinueSpecification": WaitAndContinueSpecificationTypeDef,
         "slotCaptureSetting": SlotCaptureSettingTypeDef,
     },
     total=False,
 )
 
+
 class SlotValueElicitationSettingTypeDef(
     _RequiredSlotValueElicitationSettingTypeDef, _OptionalSlotValueElicitationSettingTypeDef
 ):
     pass
 
+
 _RequiredCreateSlotRequestRequestTypeDef = TypedDict(
     "_RequiredCreateSlotRequestRequestTypeDef",
     {
         "slotName": str,
         "valueElicitationSetting": SlotValueElicitationSettingTypeDef,
         "botId": str,
         "botVersion": str,
@@ -4217,19 +5524,21 @@
         "obfuscationSetting": ObfuscationSettingTypeDef,
         "multipleValuesSetting": MultipleValuesSettingTypeDef,
         "subSlotSetting": SubSlotSettingTypeDef,
     },
     total=False,
 )
 
+
 class CreateSlotRequestRequestTypeDef(
     _RequiredCreateSlotRequestRequestTypeDef, _OptionalCreateSlotRequestRequestTypeDef
 ):
     pass
 
+
 CreateSlotResponseTypeDef = TypedDict(
     "CreateSlotResponseTypeDef",
     {
         "slotId": str,
         "slotName": str,
         "description": str,
         "slotTypeId": str,
@@ -4238,15 +5547,15 @@
         "botId": str,
         "botVersion": str,
         "localeId": str,
         "intentId": str,
         "creationDateTime": datetime,
         "multipleValuesSetting": MultipleValuesSettingTypeDef,
         "subSlotSetting": SubSlotSettingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeSlotResponseTypeDef = TypedDict(
     "DescribeSlotResponseTypeDef",
     {
         "slotId": str,
@@ -4259,15 +5568,15 @@
         "botVersion": str,
         "localeId": str,
         "intentId": str,
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
         "multipleValuesSetting": MultipleValuesSettingTypeDef,
         "subSlotSetting": SubSlotSettingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateSlotRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateSlotRequestRequestTypeDef",
     {
         "slotId": str,
@@ -4287,19 +5596,21 @@
         "obfuscationSetting": ObfuscationSettingTypeDef,
         "multipleValuesSetting": MultipleValuesSettingTypeDef,
         "subSlotSetting": SubSlotSettingTypeDef,
     },
     total=False,
 )
 
+
 class UpdateSlotRequestRequestTypeDef(
     _RequiredUpdateSlotRequestRequestTypeDef, _OptionalUpdateSlotRequestRequestTypeDef
 ):
     pass
 
+
 UpdateSlotResponseTypeDef = TypedDict(
     "UpdateSlotResponseTypeDef",
     {
         "slotId": str,
         "slotName": str,
         "description": str,
         "slotTypeId": str,
@@ -4309,10 +5620,10 @@
         "botVersion": str,
         "localeId": str,
         "intentId": str,
         "creationDateTime": datetime,
         "lastUpdatedDateTime": datetime,
         "multipleValuesSetting": MultipleValuesSettingTypeDef,
         "subSlotSetting": SubSlotSettingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-lexv2-models-2.5.0.post1/types_aiobotocore_lexv2_models/waiter.py` & `types-aiobotocore-lexv2-models-2.5.1/types_aiobotocore_lexv2_models/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-lexv2-models-2.5.0.post1/types_aiobotocore_lexv2_models/waiter.pyi` & `types-aiobotocore-lexv2-models-2.5.1/types_aiobotocore_lexv2_models/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-lexv2-models-2.5.0.post1/types_aiobotocore_lexv2_models.egg-info/SOURCES.txt` & `types-aiobotocore-lexv2-models-2.5.1/types_aiobotocore_lexv2_models.egg-info/SOURCES.txt`

 * *Files identical despite different names*

