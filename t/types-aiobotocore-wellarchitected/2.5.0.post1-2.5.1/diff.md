# Comparing `tmp/types-aiobotocore-wellarchitected-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-wellarchitected-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-wellarchitected-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:29 2023, max compression
+gzip compressed data, was "types-aiobotocore-wellarchitected-2.5.1.tar", last modified: Wed Jun 28 01:44:19 2023, max compression
```

## Comparing `types-aiobotocore-wellarchitected-2.5.0.post1.tar` & `types-aiobotocore-wellarchitected-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:29.659715 types-aiobotocore-wellarchitected-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:25:31.000000 types-aiobotocore-wellarchitected-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    16751 2023-03-11 12:27:29.659715 types-aiobotocore-wellarchitected-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    15148 2023-03-11 12:25:31.000000 types-aiobotocore-wellarchitected-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:29.659715 types-aiobotocore-wellarchitected-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2180 2023-03-11 12:25:31.000000 types-aiobotocore-wellarchitected-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:29.655715 types-aiobotocore-wellarchitected-2.5.0.post1/types_aiobotocore_wellarchitected/
--rw-r--r--   0 runner    (1001) docker     (123)      506 2023-03-11 12:25:31.000000 types-aiobotocore-wellarchitected-2.5.0.post1/types_aiobotocore_wellarchitected/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      505 2023-03-11 12:25:31.000000 types-aiobotocore-wellarchitected-2.5.0.post1/types_aiobotocore_wellarchitected/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      975 2023-03-11 12:25:31.000000 types-aiobotocore-wellarchitected-2.5.0.post1/types_aiobotocore_wellarchitected/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    31479 2023-03-11 12:25:31.000000 types-aiobotocore-wellarchitected-2.5.0.post1/types_aiobotocore_wellarchitected/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    31429 2023-03-11 12:25:31.000000 types-aiobotocore-wellarchitected-2.5.0.post1/types_aiobotocore_wellarchitected/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10130 2023-03-11 12:25:31.000000 types-aiobotocore-wellarchitected-2.5.0.post1/types_aiobotocore_wellarchitected/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    10128 2023-03-11 12:25:31.000000 types-aiobotocore-wellarchitected-2.5.0.post1/types_aiobotocore_wellarchitected/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:25:31.000000 types-aiobotocore-wellarchitected-2.5.0.post1/types_aiobotocore_wellarchitected/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    39760 2023-03-11 12:25:32.000000 types-aiobotocore-wellarchitected-2.5.0.post1/types_aiobotocore_wellarchitected/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    39715 2023-03-11 12:25:32.000000 types-aiobotocore-wellarchitected-2.5.0.post1/types_aiobotocore_wellarchitected/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:25:31.000000 types-aiobotocore-wellarchitected-2.5.0.post1/types_aiobotocore_wellarchitected/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:29.659715 types-aiobotocore-wellarchitected-2.5.0.post1/types_aiobotocore_wellarchitected.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    16751 2023-03-11 12:27:29.000000 types-aiobotocore-wellarchitected-2.5.0.post1/types_aiobotocore_wellarchitected.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      870 2023-03-11 12:27:29.000000 types-aiobotocore-wellarchitected-2.5.0.post1/types_aiobotocore_wellarchitected.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:29.000000 types-aiobotocore-wellarchitected-2.5.0.post1/types_aiobotocore_wellarchitected.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:29.000000 types-aiobotocore-wellarchitected-2.5.0.post1/types_aiobotocore_wellarchitected.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:29.000000 types-aiobotocore-wellarchitected-2.5.0.post1/types_aiobotocore_wellarchitected.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       34 2023-03-11 12:27:29.000000 types-aiobotocore-wellarchitected-2.5.0.post1/types_aiobotocore_wellarchitected.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:19.582231 types-aiobotocore-wellarchitected-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:42:25.000000 types-aiobotocore-wellarchitected-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    18288 2023-06-28 01:44:19.582231 types-aiobotocore-wellarchitected-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    16691 2023-06-28 01:42:25.000000 types-aiobotocore-wellarchitected-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:19.582231 types-aiobotocore-wellarchitected-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2174 2023-06-28 01:42:25.000000 types-aiobotocore-wellarchitected-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:19.582231 types-aiobotocore-wellarchitected-2.5.1/types_aiobotocore_wellarchitected/
+-rw-r--r--   0 runner    (1001) docker     (123)      506 2023-06-28 01:42:25.000000 types-aiobotocore-wellarchitected-2.5.1/types_aiobotocore_wellarchitected/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      505 2023-06-28 01:42:25.000000 types-aiobotocore-wellarchitected-2.5.1/types_aiobotocore_wellarchitected/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      963 2023-06-28 01:42:25.000000 types-aiobotocore-wellarchitected-2.5.1/types_aiobotocore_wellarchitected/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    40458 2023-06-28 01:42:25.000000 types-aiobotocore-wellarchitected-2.5.1/types_aiobotocore_wellarchitected/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    40394 2023-06-28 01:42:25.000000 types-aiobotocore-wellarchitected-2.5.1/types_aiobotocore_wellarchitected/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    11032 2023-06-28 01:42:25.000000 types-aiobotocore-wellarchitected-2.5.1/types_aiobotocore_wellarchitected/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11030 2023-06-28 01:42:25.000000 types-aiobotocore-wellarchitected-2.5.1/types_aiobotocore_wellarchitected/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:42:25.000000 types-aiobotocore-wellarchitected-2.5.1/types_aiobotocore_wellarchitected/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    53133 2023-06-28 01:42:29.000000 types-aiobotocore-wellarchitected-2.5.1/types_aiobotocore_wellarchitected/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    53076 2023-06-28 01:42:29.000000 types-aiobotocore-wellarchitected-2.5.1/types_aiobotocore_wellarchitected/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:42:25.000000 types-aiobotocore-wellarchitected-2.5.1/types_aiobotocore_wellarchitected/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:19.582231 types-aiobotocore-wellarchitected-2.5.1/types_aiobotocore_wellarchitected.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    18288 2023-06-28 01:44:19.000000 types-aiobotocore-wellarchitected-2.5.1/types_aiobotocore_wellarchitected.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      870 2023-06-28 01:44:19.000000 types-aiobotocore-wellarchitected-2.5.1/types_aiobotocore_wellarchitected.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:19.000000 types-aiobotocore-wellarchitected-2.5.1/types_aiobotocore_wellarchitected.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:19.000000 types-aiobotocore-wellarchitected-2.5.1/types_aiobotocore_wellarchitected.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:19.000000 types-aiobotocore-wellarchitected-2.5.1/types_aiobotocore_wellarchitected.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       34 2023-06-28 01:44:19.000000 types-aiobotocore-wellarchitected-2.5.1/types_aiobotocore_wellarchitected.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-wellarchitected-2.5.0.post1/LICENSE` & `types-aiobotocore-wellarchitected-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-wellarchitected-2.5.0.post1/PKG-INFO` & `types-aiobotocore-wellarchitected-2.5.1/PKG-INFO`

 * *Files 24% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-wellarchitected
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.WellArchitected 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.WellArchitected 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-wellarchitected"></a>
 
 # types-aiobotocore-wellarchitected
 
 [![PyPI - types-aiobotocore-wellarchitected](https://img.shields.io/pypi/v/types-aiobotocore-wellarchitected.svg?color=blue)](https://pypi.org/project/types-aiobotocore-wellarchitected)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-wellarchitected.svg?color=blue)](https://pypi.org/project/types-aiobotocore-wellarchitected)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-wellarchitected?color=blue)](https://pypistats.org/packages/types-aiobotocore-wellarchitected)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.WellArchitected 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected)
+[aiobotocore.WellArchitected 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected)
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
 [types-aiobotocore-wellarchitected docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/).
 
 See how it helps to find and fix potential bugs:
 
@@ -276,22 +276,30 @@
     AdditionalResourceTypeType,
     AnswerReasonType,
     CheckFailureReasonType,
     CheckProviderType,
     CheckStatusType,
     ChoiceReasonType,
     ChoiceStatusType,
+    DefinitionTypeType,
     DifferenceStatusType,
+    DiscoveryIntegrationStatusType,
     ImportLensStatusType,
     LensStatusType,
     LensStatusTypeType,
     LensTypeType,
+    MetricTypeType,
     NotificationTypeType,
     OrganizationSharingStatusType,
     PermissionTypeType,
+    ProfileNotificationTypeType,
+    ProfileOwnerTypeType,
+    QuestionPriorityType,
+    QuestionTypeType,
+    ReportFormatType,
     RiskType,
     ShareInvitationActionType,
     ShareResourceTypeType,
     ShareStatusType,
     TrustedAdvisorIntegrationStatusType,
     WorkloadEnvironmentType,
     WorkloadImprovementStatusType,
@@ -315,162 +323,200 @@
 
 ```python
 from types_aiobotocore_wellarchitected.type_defs import (
     ChoiceContentTypeDef,
     ChoiceAnswerSummaryTypeDef,
     ChoiceAnswerTypeDef,
     AssociateLensesInputRequestTypeDef,
+    AssociateProfilesInputRequestTypeDef,
+    BestPracticeTypeDef,
     CheckDetailTypeDef,
     CheckSummaryTypeDef,
     ChoiceImprovementPlanTypeDef,
     ChoiceUpdateTypeDef,
     CreateLensShareInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CreateLensShareOutputTypeDef,
     CreateLensVersionInputRequestTypeDef,
+    CreateLensVersionOutputTypeDef,
     CreateMilestoneInputRequestTypeDef,
+    CreateMilestoneOutputTypeDef,
+    ProfileQuestionUpdateTypeDef,
+    CreateProfileOutputTypeDef,
+    CreateProfileShareInputRequestTypeDef,
+    CreateProfileShareOutputTypeDef,
     WorkloadDiscoveryConfigTypeDef,
+    CreateWorkloadOutputTypeDef,
     CreateWorkloadShareInputRequestTypeDef,
+    CreateWorkloadShareOutputTypeDef,
     DeleteLensInputRequestTypeDef,
     DeleteLensShareInputRequestTypeDef,
+    DeleteProfileInputRequestTypeDef,
+    DeleteProfileShareInputRequestTypeDef,
     DeleteWorkloadInputRequestTypeDef,
     DeleteWorkloadShareInputRequestTypeDef,
     DisassociateLensesInputRequestTypeDef,
+    DisassociateProfilesInputRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     ExportLensInputRequestTypeDef,
+    ExportLensOutputTypeDef,
     GetAnswerInputRequestTypeDef,
+    GetConsolidatedReportInputRequestTypeDef,
     GetLensInputRequestTypeDef,
     LensTypeDef,
     GetLensReviewInputRequestTypeDef,
     GetLensReviewReportInputRequestTypeDef,
     LensReviewReportTypeDef,
     GetLensVersionDifferenceInputRequestTypeDef,
     GetMilestoneInputRequestTypeDef,
+    GetProfileInputRequestTypeDef,
     GetWorkloadInputRequestTypeDef,
     ImportLensInputRequestTypeDef,
-    LensReviewSummaryTypeDef,
+    ImportLensOutputTypeDef,
+    WorkloadProfileTypeDef,
     PillarReviewSummaryTypeDef,
     LensShareSummaryTypeDef,
     LensSummaryTypeDef,
     LensUpgradeSummaryTypeDef,
     ListAnswersInputRequestTypeDef,
     ListCheckDetailsInputRequestTypeDef,
     ListCheckSummariesInputRequestTypeDef,
     ListLensReviewImprovementsInputRequestTypeDef,
     ListLensReviewsInputRequestTypeDef,
     ListLensSharesInputRequestTypeDef,
     ListLensesInputRequestTypeDef,
     ListMilestonesInputRequestTypeDef,
     ListNotificationsInputRequestTypeDef,
+    ListProfileNotificationsInputRequestTypeDef,
+    ProfileNotificationSummaryTypeDef,
+    ListProfileSharesInputRequestTypeDef,
+    ProfileShareSummaryTypeDef,
+    ListProfilesInputRequestTypeDef,
+    ProfileSummaryTypeDef,
     ListShareInvitationsInputRequestTypeDef,
     ShareInvitationSummaryTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    ListTagsForResourceOutputTypeDef,
     ListWorkloadSharesInputRequestTypeDef,
     WorkloadShareSummaryTypeDef,
     ListWorkloadsInputRequestTypeDef,
-    WorkloadSummaryTypeDef,
     QuestionDifferenceTypeDef,
+    ProfileChoiceTypeDef,
+    ProfileTemplateChoiceTypeDef,
+    ResponseMetadataTypeDef,
     ShareInvitationTypeDef,
     TagResourceInputRequestTypeDef,
     UntagResourceInputRequestTypeDef,
     UpdateGlobalSettingsInputRequestTypeDef,
     UpdateLensReviewInputRequestTypeDef,
     UpdateShareInvitationInputRequestTypeDef,
     UpdateWorkloadShareInputRequestTypeDef,
     WorkloadShareTypeDef,
     UpgradeLensReviewInputRequestTypeDef,
+    UpgradeProfileVersionInputRequestTypeDef,
     AdditionalResourcesTypeDef,
-    ImprovementSummaryTypeDef,
-    UpdateAnswerInputRequestTypeDef,
-    CreateLensShareOutputTypeDef,
-    CreateLensVersionOutputTypeDef,
-    CreateMilestoneOutputTypeDef,
-    CreateWorkloadOutputTypeDef,
-    CreateWorkloadShareOutputTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ExportLensOutputTypeDef,
-    ImportLensOutputTypeDef,
+    QuestionMetricTypeDef,
     ListCheckDetailsOutputTypeDef,
     ListCheckSummariesOutputTypeDef,
-    ListTagsForResourceOutputTypeDef,
+    ImprovementSummaryTypeDef,
+    UpdateAnswerInputRequestTypeDef,
+    CreateProfileInputRequestTypeDef,
+    UpdateProfileInputRequestTypeDef,
     CreateWorkloadInputRequestTypeDef,
     UpdateWorkloadInputRequestTypeDef,
-    WorkloadTypeDef,
     GetLensOutputTypeDef,
     GetLensReviewReportOutputTypeDef,
-    ListLensReviewsOutputTypeDef,
+    LensReviewSummaryTypeDef,
+    WorkloadSummaryTypeDef,
+    WorkloadTypeDef,
     LensReviewTypeDef,
     ListLensSharesOutputTypeDef,
     ListLensesOutputTypeDef,
     NotificationSummaryTypeDef,
+    ListProfileNotificationsOutputTypeDef,
+    ListProfileSharesOutputTypeDef,
+    ListProfilesOutputTypeDef,
     ListShareInvitationsOutputTypeDef,
     ListWorkloadSharesOutputTypeDef,
-    ListWorkloadsOutputTypeDef,
-    MilestoneSummaryTypeDef,
     PillarDifferenceTypeDef,
+    ProfileQuestionTypeDef,
+    ProfileTemplateQuestionTypeDef,
     UpdateShareInvitationOutputTypeDef,
     UpdateWorkloadShareOutputTypeDef,
     ChoiceTypeDef,
+    PillarMetricTypeDef,
     ListLensReviewImprovementsOutputTypeDef,
+    ListLensReviewsOutputTypeDef,
+    ListWorkloadsOutputTypeDef,
+    MilestoneSummaryTypeDef,
     GetWorkloadOutputTypeDef,
     MilestoneTypeDef,
     UpdateWorkloadOutputTypeDef,
     GetLensReviewOutputTypeDef,
     UpdateLensReviewOutputTypeDef,
     ListNotificationsOutputTypeDef,
-    ListMilestonesOutputTypeDef,
     VersionDifferencesTypeDef,
+    ProfileTypeDef,
+    ProfileTemplateTypeDef,
     AnswerSummaryTypeDef,
     AnswerTypeDef,
+    LensMetricTypeDef,
+    ListMilestonesOutputTypeDef,
     GetMilestoneOutputTypeDef,
     GetLensVersionDifferenceOutputTypeDef,
+    GetProfileOutputTypeDef,
+    UpdateProfileOutputTypeDef,
+    GetProfileTemplateOutputTypeDef,
     ListAnswersOutputTypeDef,
     GetAnswerOutputTypeDef,
     UpdateAnswerOutputTypeDef,
+    ConsolidatedReportMetricTypeDef,
+    GetConsolidatedReportOutputTypeDef,
 )
 
 
 def get_structure() -> ChoiceContentTypeDef:
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

### Comparing `types-aiobotocore-wellarchitected-2.5.0.post1/README.md` & `types-aiobotocore-wellarchitected-2.5.1/types_aiobotocore_wellarchitected.egg-info/PKG-INFO`

 * *Files 12% similar despite different names*

```diff
@@ -1,29 +1,62 @@
+Metadata-Version: 2.1
+Name: types-aiobotocore-wellarchitected
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.WellArchitected 2.5.1 service generated with mypy-boto3-builder 7.14.5
+Home-page: https://github.com/youtype/mypy_boto3_builder
+Author: Vlad Emelianov
+Author-email: vlad.emelianov.nz@gmail.com
+License: MIT License
+Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/
+Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
+Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
+Keywords: aiobotocore wellarchitected type-annotations boto3-stubs mypy typeshed autocomplete
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
 <a id="types-aiobotocore-wellarchitected"></a>
 
 # types-aiobotocore-wellarchitected
 
 [![PyPI - types-aiobotocore-wellarchitected](https://img.shields.io/pypi/v/types-aiobotocore-wellarchitected.svg?color=blue)](https://pypi.org/project/types-aiobotocore-wellarchitected)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-wellarchitected.svg?color=blue)](https://pypi.org/project/types-aiobotocore-wellarchitected)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-wellarchitected?color=blue)](https://pypistats.org/packages/types-aiobotocore-wellarchitected)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.WellArchitected 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected)
+[aiobotocore.WellArchitected 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected)
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
 [types-aiobotocore-wellarchitected docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/).
 
 See how it helps to find and fix potential bugs:
 
@@ -243,22 +276,30 @@
     AdditionalResourceTypeType,
     AnswerReasonType,
     CheckFailureReasonType,
     CheckProviderType,
     CheckStatusType,
     ChoiceReasonType,
     ChoiceStatusType,
+    DefinitionTypeType,
     DifferenceStatusType,
+    DiscoveryIntegrationStatusType,
     ImportLensStatusType,
     LensStatusType,
     LensStatusTypeType,
     LensTypeType,
+    MetricTypeType,
     NotificationTypeType,
     OrganizationSharingStatusType,
     PermissionTypeType,
+    ProfileNotificationTypeType,
+    ProfileOwnerTypeType,
+    QuestionPriorityType,
+    QuestionTypeType,
+    ReportFormatType,
     RiskType,
     ShareInvitationActionType,
     ShareResourceTypeType,
     ShareStatusType,
     TrustedAdvisorIntegrationStatusType,
     WorkloadEnvironmentType,
     WorkloadImprovementStatusType,
@@ -282,162 +323,200 @@
 
 ```python
 from types_aiobotocore_wellarchitected.type_defs import (
     ChoiceContentTypeDef,
     ChoiceAnswerSummaryTypeDef,
     ChoiceAnswerTypeDef,
     AssociateLensesInputRequestTypeDef,
+    AssociateProfilesInputRequestTypeDef,
+    BestPracticeTypeDef,
     CheckDetailTypeDef,
     CheckSummaryTypeDef,
     ChoiceImprovementPlanTypeDef,
     ChoiceUpdateTypeDef,
     CreateLensShareInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CreateLensShareOutputTypeDef,
     CreateLensVersionInputRequestTypeDef,
+    CreateLensVersionOutputTypeDef,
     CreateMilestoneInputRequestTypeDef,
+    CreateMilestoneOutputTypeDef,
+    ProfileQuestionUpdateTypeDef,
+    CreateProfileOutputTypeDef,
+    CreateProfileShareInputRequestTypeDef,
+    CreateProfileShareOutputTypeDef,
     WorkloadDiscoveryConfigTypeDef,
+    CreateWorkloadOutputTypeDef,
     CreateWorkloadShareInputRequestTypeDef,
+    CreateWorkloadShareOutputTypeDef,
     DeleteLensInputRequestTypeDef,
     DeleteLensShareInputRequestTypeDef,
+    DeleteProfileInputRequestTypeDef,
+    DeleteProfileShareInputRequestTypeDef,
     DeleteWorkloadInputRequestTypeDef,
     DeleteWorkloadShareInputRequestTypeDef,
     DisassociateLensesInputRequestTypeDef,
+    DisassociateProfilesInputRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     ExportLensInputRequestTypeDef,
+    ExportLensOutputTypeDef,
     GetAnswerInputRequestTypeDef,
+    GetConsolidatedReportInputRequestTypeDef,
     GetLensInputRequestTypeDef,
     LensTypeDef,
     GetLensReviewInputRequestTypeDef,
     GetLensReviewReportInputRequestTypeDef,
     LensReviewReportTypeDef,
     GetLensVersionDifferenceInputRequestTypeDef,
     GetMilestoneInputRequestTypeDef,
+    GetProfileInputRequestTypeDef,
     GetWorkloadInputRequestTypeDef,
     ImportLensInputRequestTypeDef,
-    LensReviewSummaryTypeDef,
+    ImportLensOutputTypeDef,
+    WorkloadProfileTypeDef,
     PillarReviewSummaryTypeDef,
     LensShareSummaryTypeDef,
     LensSummaryTypeDef,
     LensUpgradeSummaryTypeDef,
     ListAnswersInputRequestTypeDef,
     ListCheckDetailsInputRequestTypeDef,
     ListCheckSummariesInputRequestTypeDef,
     ListLensReviewImprovementsInputRequestTypeDef,
     ListLensReviewsInputRequestTypeDef,
     ListLensSharesInputRequestTypeDef,
     ListLensesInputRequestTypeDef,
     ListMilestonesInputRequestTypeDef,
     ListNotificationsInputRequestTypeDef,
+    ListProfileNotificationsInputRequestTypeDef,
+    ProfileNotificationSummaryTypeDef,
+    ListProfileSharesInputRequestTypeDef,
+    ProfileShareSummaryTypeDef,
+    ListProfilesInputRequestTypeDef,
+    ProfileSummaryTypeDef,
     ListShareInvitationsInputRequestTypeDef,
     ShareInvitationSummaryTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    ListTagsForResourceOutputTypeDef,
     ListWorkloadSharesInputRequestTypeDef,
     WorkloadShareSummaryTypeDef,
     ListWorkloadsInputRequestTypeDef,
-    WorkloadSummaryTypeDef,
     QuestionDifferenceTypeDef,
+    ProfileChoiceTypeDef,
+    ProfileTemplateChoiceTypeDef,
+    ResponseMetadataTypeDef,
     ShareInvitationTypeDef,
     TagResourceInputRequestTypeDef,
     UntagResourceInputRequestTypeDef,
     UpdateGlobalSettingsInputRequestTypeDef,
     UpdateLensReviewInputRequestTypeDef,
     UpdateShareInvitationInputRequestTypeDef,
     UpdateWorkloadShareInputRequestTypeDef,
     WorkloadShareTypeDef,
     UpgradeLensReviewInputRequestTypeDef,
+    UpgradeProfileVersionInputRequestTypeDef,
     AdditionalResourcesTypeDef,
-    ImprovementSummaryTypeDef,
-    UpdateAnswerInputRequestTypeDef,
-    CreateLensShareOutputTypeDef,
-    CreateLensVersionOutputTypeDef,
-    CreateMilestoneOutputTypeDef,
-    CreateWorkloadOutputTypeDef,
-    CreateWorkloadShareOutputTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ExportLensOutputTypeDef,
-    ImportLensOutputTypeDef,
+    QuestionMetricTypeDef,
     ListCheckDetailsOutputTypeDef,
     ListCheckSummariesOutputTypeDef,
-    ListTagsForResourceOutputTypeDef,
+    ImprovementSummaryTypeDef,
+    UpdateAnswerInputRequestTypeDef,
+    CreateProfileInputRequestTypeDef,
+    UpdateProfileInputRequestTypeDef,
     CreateWorkloadInputRequestTypeDef,
     UpdateWorkloadInputRequestTypeDef,
-    WorkloadTypeDef,
     GetLensOutputTypeDef,
     GetLensReviewReportOutputTypeDef,
-    ListLensReviewsOutputTypeDef,
+    LensReviewSummaryTypeDef,
+    WorkloadSummaryTypeDef,
+    WorkloadTypeDef,
     LensReviewTypeDef,
     ListLensSharesOutputTypeDef,
     ListLensesOutputTypeDef,
     NotificationSummaryTypeDef,
+    ListProfileNotificationsOutputTypeDef,
+    ListProfileSharesOutputTypeDef,
+    ListProfilesOutputTypeDef,
     ListShareInvitationsOutputTypeDef,
     ListWorkloadSharesOutputTypeDef,
-    ListWorkloadsOutputTypeDef,
-    MilestoneSummaryTypeDef,
     PillarDifferenceTypeDef,
+    ProfileQuestionTypeDef,
+    ProfileTemplateQuestionTypeDef,
     UpdateShareInvitationOutputTypeDef,
     UpdateWorkloadShareOutputTypeDef,
     ChoiceTypeDef,
+    PillarMetricTypeDef,
     ListLensReviewImprovementsOutputTypeDef,
+    ListLensReviewsOutputTypeDef,
+    ListWorkloadsOutputTypeDef,
+    MilestoneSummaryTypeDef,
     GetWorkloadOutputTypeDef,
     MilestoneTypeDef,
     UpdateWorkloadOutputTypeDef,
     GetLensReviewOutputTypeDef,
     UpdateLensReviewOutputTypeDef,
     ListNotificationsOutputTypeDef,
-    ListMilestonesOutputTypeDef,
     VersionDifferencesTypeDef,
+    ProfileTypeDef,
+    ProfileTemplateTypeDef,
     AnswerSummaryTypeDef,
     AnswerTypeDef,
+    LensMetricTypeDef,
+    ListMilestonesOutputTypeDef,
     GetMilestoneOutputTypeDef,
     GetLensVersionDifferenceOutputTypeDef,
+    GetProfileOutputTypeDef,
+    UpdateProfileOutputTypeDef,
+    GetProfileTemplateOutputTypeDef,
     ListAnswersOutputTypeDef,
     GetAnswerOutputTypeDef,
     UpdateAnswerOutputTypeDef,
+    ConsolidatedReportMetricTypeDef,
+    GetConsolidatedReportOutputTypeDef,
 )
 
 
 def get_structure() -> ChoiceContentTypeDef:
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

### Comparing `types-aiobotocore-wellarchitected-2.5.0.post1/setup.py` & `types-aiobotocore-wellarchitected-2.5.1/setup.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-wellarchitected.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-wellarchitected",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_wellarchitected"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.WellArchitected 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.WellArchitected 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/"
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

### Comparing `types-aiobotocore-wellarchitected-2.5.0.post1/types_aiobotocore_wellarchitected/__main__.py` & `types-aiobotocore-wellarchitected-2.5.1/types_aiobotocore_wellarchitected/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.WellArchitected 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.WellArchitected 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected\nOther"
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

### Comparing `types-aiobotocore-wellarchitected-2.5.0.post1/types_aiobotocore_wellarchitected/client.py` & `types-aiobotocore-wellarchitected-2.5.1/types_aiobotocore_wellarchitected/client.pyi`

 * *Files 10% similar despite different names*

```diff
@@ -17,84 +17,95 @@
 from typing import Any, Dict, Mapping, Sequence, Type
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import (
     AnswerReasonType,
+    DiscoveryIntegrationStatusType,
     LensStatusTypeType,
     LensTypeType,
     OrganizationSharingStatusType,
     PermissionTypeType,
+    ProfileOwnerTypeType,
+    QuestionPriorityType,
+    ReportFormatType,
     ShareInvitationActionType,
     ShareResourceTypeType,
     ShareStatusType,
     WorkloadEnvironmentType,
     WorkloadImprovementStatusType,
 )
 from .type_defs import (
     ChoiceUpdateTypeDef,
     CreateLensShareOutputTypeDef,
     CreateLensVersionOutputTypeDef,
     CreateMilestoneOutputTypeDef,
+    CreateProfileOutputTypeDef,
+    CreateProfileShareOutputTypeDef,
     CreateWorkloadOutputTypeDef,
     CreateWorkloadShareOutputTypeDef,
     EmptyResponseMetadataTypeDef,
     ExportLensOutputTypeDef,
     GetAnswerOutputTypeDef,
+    GetConsolidatedReportOutputTypeDef,
     GetLensOutputTypeDef,
     GetLensReviewOutputTypeDef,
     GetLensReviewReportOutputTypeDef,
     GetLensVersionDifferenceOutputTypeDef,
     GetMilestoneOutputTypeDef,
+    GetProfileOutputTypeDef,
+    GetProfileTemplateOutputTypeDef,
     GetWorkloadOutputTypeDef,
     ImportLensOutputTypeDef,
     ListAnswersOutputTypeDef,
     ListCheckDetailsOutputTypeDef,
     ListCheckSummariesOutputTypeDef,
     ListLensesOutputTypeDef,
     ListLensReviewImprovementsOutputTypeDef,
     ListLensReviewsOutputTypeDef,
     ListLensSharesOutputTypeDef,
     ListMilestonesOutputTypeDef,
     ListNotificationsOutputTypeDef,
+    ListProfileNotificationsOutputTypeDef,
+    ListProfileSharesOutputTypeDef,
+    ListProfilesOutputTypeDef,
     ListShareInvitationsOutputTypeDef,
     ListTagsForResourceOutputTypeDef,
     ListWorkloadSharesOutputTypeDef,
     ListWorkloadsOutputTypeDef,
+    ProfileQuestionUpdateTypeDef,
     UpdateAnswerOutputTypeDef,
     UpdateLensReviewOutputTypeDef,
+    UpdateProfileOutputTypeDef,
     UpdateShareInvitationOutputTypeDef,
     UpdateWorkloadOutputTypeDef,
     UpdateWorkloadShareOutputTypeDef,
     WorkloadDiscoveryConfigTypeDef,
 )
 
 __all__ = ("WellArchitectedClient",)
 
-
 class BotocoreClientError(BaseException):
     MSG_TEMPLATE: str
 
     def __init__(self, error_response: Mapping[str, Any], operation_name: str) -> None:
         self.response: Dict[str, Any]
         self.operation_name: str
 
-
 class Exceptions:
     AccessDeniedException: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
     ConflictException: Type[BotocoreClientError]
     InternalServerException: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
     ServiceQuotaExceededException: Type[BotocoreClientError]
     ThrottlingException: Type[BotocoreClientError]
     ValidationException: Type[BotocoreClientError]
 
-
 class WellArchitectedClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/)
     """
 
     meta: ClientMeta
@@ -103,76 +114,102 @@
     def exceptions(self) -> Exceptions:
         """
         WellArchitectedClient exceptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#exceptions)
         """
-
     async def associate_lenses(
         self, *, WorkloadId: str, LensAliases: Sequence[str]
     ) -> EmptyResponseMetadataTypeDef:
         """
         Associate a lens to a workload.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.associate_lenses)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#associate_lenses)
         """
+    async def associate_profiles(
+        self, *, WorkloadId: str, ProfileArns: Sequence[str]
+    ) -> EmptyResponseMetadataTypeDef:
+        """
+        Associate a profile with a workload.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.associate_profiles)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#associate_profiles)
+        """
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#can_paginate)
         """
-
     async def close(self) -> None:
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#close)
         """
-
     async def create_lens_share(
         self, *, LensAlias: str, SharedWith: str, ClientRequestToken: str
     ) -> CreateLensShareOutputTypeDef:
         """
         Create a lens share.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.create_lens_share)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#create_lens_share)
         """
-
     async def create_lens_version(
         self,
         *,
         LensAlias: str,
         LensVersion: str,
         ClientRequestToken: str,
         IsMajorVersion: bool = ...
     ) -> CreateLensVersionOutputTypeDef:
         """
         Create a new lens version.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.create_lens_version)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#create_lens_version)
         """
-
     async def create_milestone(
         self, *, WorkloadId: str, MilestoneName: str, ClientRequestToken: str
     ) -> CreateMilestoneOutputTypeDef:
         """
         Create a milestone for an existing workload.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.create_milestone)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#create_milestone)
         """
+    async def create_profile(
+        self,
+        *,
+        ProfileName: str,
+        ProfileDescription: str,
+        ProfileQuestions: Sequence[ProfileQuestionUpdateTypeDef],
+        ClientRequestToken: str,
+        Tags: Mapping[str, str] = ...
+    ) -> CreateProfileOutputTypeDef:
+        """
+        Create a profile.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.create_profile)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#create_profile)
+        """
+    async def create_profile_share(
+        self, *, ProfileArn: str, SharedWith: str, ClientRequestToken: str
+    ) -> CreateProfileShareOutputTypeDef:
+        """
+        Create a profile share.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.create_profile_share)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#create_profile_share)
+        """
     async def create_workload(
         self,
         *,
         WorkloadName: str,
         Description: str,
         Environment: WorkloadEnvironmentType,
         Lenses: Sequence[str],
@@ -184,210 +221,251 @@
         ArchitecturalDesign: str = ...,
         ReviewOwner: str = ...,
         IndustryType: str = ...,
         Industry: str = ...,
         Notes: str = ...,
         Tags: Mapping[str, str] = ...,
         DiscoveryConfig: WorkloadDiscoveryConfigTypeDef = ...,
-        Applications: Sequence[str] = ...
+        Applications: Sequence[str] = ...,
+        ProfileArns: Sequence[str] = ...
     ) -> CreateWorkloadOutputTypeDef:
         """
         Create a new workload.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.create_workload)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#create_workload)
         """
-
     async def create_workload_share(
         self,
         *,
         WorkloadId: str,
         SharedWith: str,
         PermissionType: PermissionTypeType,
         ClientRequestToken: str
     ) -> CreateWorkloadShareOutputTypeDef:
         """
         Create a workload share.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.create_workload_share)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#create_workload_share)
         """
-
     async def delete_lens(
         self, *, LensAlias: str, ClientRequestToken: str, LensStatus: LensStatusTypeType
     ) -> EmptyResponseMetadataTypeDef:
         """
         Delete an existing lens.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.delete_lens)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#delete_lens)
         """
-
     async def delete_lens_share(
         self, *, ShareId: str, LensAlias: str, ClientRequestToken: str
     ) -> EmptyResponseMetadataTypeDef:
         """
         Delete a lens share.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.delete_lens_share)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#delete_lens_share)
         """
+    async def delete_profile(
+        self, *, ProfileArn: str, ClientRequestToken: str
+    ) -> EmptyResponseMetadataTypeDef:
+        """
+        Delete a profile.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.delete_profile)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#delete_profile)
+        """
+    async def delete_profile_share(
+        self, *, ShareId: str, ProfileArn: str, ClientRequestToken: str
+    ) -> EmptyResponseMetadataTypeDef:
+        """
+        Delete a profile share.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.delete_profile_share)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#delete_profile_share)
+        """
     async def delete_workload(
         self, *, WorkloadId: str, ClientRequestToken: str
     ) -> EmptyResponseMetadataTypeDef:
         """
         Delete an existing workload.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.delete_workload)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#delete_workload)
         """
-
     async def delete_workload_share(
         self, *, ShareId: str, WorkloadId: str, ClientRequestToken: str
     ) -> EmptyResponseMetadataTypeDef:
         """
         Delete a workload share.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.delete_workload_share)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#delete_workload_share)
         """
-
     async def disassociate_lenses(
         self, *, WorkloadId: str, LensAliases: Sequence[str]
     ) -> EmptyResponseMetadataTypeDef:
         """
         Disassociate a lens from a workload.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.disassociate_lenses)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#disassociate_lenses)
         """
+    async def disassociate_profiles(
+        self, *, WorkloadId: str, ProfileArns: Sequence[str]
+    ) -> EmptyResponseMetadataTypeDef:
+        """
+        Disassociate a profile from a workload.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.disassociate_profiles)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#disassociate_profiles)
+        """
     async def export_lens(
         self, *, LensAlias: str, LensVersion: str = ...
     ) -> ExportLensOutputTypeDef:
         """
         Export an existing lens.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.export_lens)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#export_lens)
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
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#generate_presigned_url)
         """
-
     async def get_answer(
         self, *, WorkloadId: str, LensAlias: str, QuestionId: str, MilestoneNumber: int = ...
     ) -> GetAnswerOutputTypeDef:
         """
         Get the answer to a specific question in a workload review.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.get_answer)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#get_answer)
         """
+    async def get_consolidated_report(
+        self,
+        *,
+        Format: ReportFormatType,
+        IncludeSharedResources: bool = ...,
+        NextToken: str = ...,
+        MaxResults: int = ...
+    ) -> GetConsolidatedReportOutputTypeDef:
+        """
+        Get a consolidated report of your workloads.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.get_consolidated_report)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#get_consolidated_report)
+        """
     async def get_lens(self, *, LensAlias: str, LensVersion: str = ...) -> GetLensOutputTypeDef:
         """
         Get an existing lens.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.get_lens)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#get_lens)
         """
-
     async def get_lens_review(
         self, *, WorkloadId: str, LensAlias: str, MilestoneNumber: int = ...
     ) -> GetLensReviewOutputTypeDef:
         """
         Get lens review.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.get_lens_review)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#get_lens_review)
         """
-
     async def get_lens_review_report(
         self, *, WorkloadId: str, LensAlias: str, MilestoneNumber: int = ...
     ) -> GetLensReviewReportOutputTypeDef:
         """
         Get lens review report.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.get_lens_review_report)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#get_lens_review_report)
         """
-
     async def get_lens_version_difference(
         self, *, LensAlias: str, BaseLensVersion: str = ..., TargetLensVersion: str = ...
     ) -> GetLensVersionDifferenceOutputTypeDef:
         """
         Get lens version differences.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.get_lens_version_difference)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#get_lens_version_difference)
         """
-
     async def get_milestone(
         self, *, WorkloadId: str, MilestoneNumber: int
     ) -> GetMilestoneOutputTypeDef:
         """
         Get a milestone for an existing workload.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.get_milestone)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#get_milestone)
         """
+    async def get_profile(
+        self, *, ProfileArn: str, ProfileVersion: str = ...
+    ) -> GetProfileOutputTypeDef:
+        """
+        Get profile information.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.get_profile)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#get_profile)
+        """
+    async def get_profile_template(self) -> GetProfileTemplateOutputTypeDef:
+        """
+        Get profile template.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.get_profile_template)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#get_profile_template)
+        """
     async def get_workload(self, *, WorkloadId: str) -> GetWorkloadOutputTypeDef:
         """
         Get an existing workload.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.get_workload)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#get_workload)
         """
-
     async def import_lens(
         self,
         *,
         JSONString: str,
         ClientRequestToken: str,
         LensAlias: str = ...,
         Tags: Mapping[str, str] = ...
     ) -> ImportLensOutputTypeDef:
         """
-        Import a new lens.
+        Import a new custom lens or update an existing custom lens.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.import_lens)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#import_lens)
         """
-
     async def list_answers(
         self,
         *,
         WorkloadId: str,
         LensAlias: str,
         PillarId: str = ...,
         MilestoneNumber: int = ...,
         NextToken: str = ...,
-        MaxResults: int = ...
+        MaxResults: int = ...,
+        QuestionPriority: QuestionPriorityType = ...
     ) -> ListAnswersOutputTypeDef:
         """
-        List of answers.
+        List of answers for a particular workload and lens.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.list_answers)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#list_answers)
         """
-
     async def list_check_details(
         self,
         *,
         WorkloadId: str,
         LensArn: str,
         PillarId: str,
         QuestionId: str,
@@ -397,15 +475,14 @@
     ) -> ListCheckDetailsOutputTypeDef:
         """
         List of Trusted Advisor check details by account related to the workload.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.list_check_details)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#list_check_details)
         """
-
     async def list_check_summaries(
         self,
         *,
         WorkloadId: str,
         LensArn: str,
         PillarId: str,
         QuestionId: str,
@@ -416,47 +493,45 @@
         """
         List of Trusted Advisor checks summarized for all accounts related to the
         workload.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.list_check_summaries)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#list_check_summaries)
         """
-
     async def list_lens_review_improvements(
         self,
         *,
         WorkloadId: str,
         LensAlias: str,
         PillarId: str = ...,
         MilestoneNumber: int = ...,
         NextToken: str = ...,
-        MaxResults: int = ...
+        MaxResults: int = ...,
+        QuestionPriority: QuestionPriorityType = ...
     ) -> ListLensReviewImprovementsOutputTypeDef:
         """
         List lens review improvements.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.list_lens_review_improvements)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#list_lens_review_improvements)
         """
-
     async def list_lens_reviews(
         self,
         *,
         WorkloadId: str,
         MilestoneNumber: int = ...,
         NextToken: str = ...,
         MaxResults: int = ...
     ) -> ListLensReviewsOutputTypeDef:
         """
-        List lens reviews.
+        List lens reviews for a particular workload.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.list_lens_reviews)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#list_lens_reviews)
         """
-
     async def list_lens_shares(
         self,
         *,
         LensAlias: str,
         SharedWithPrefix: str = ...,
         NextToken: str = ...,
         MaxResults: int = ...,
@@ -464,15 +539,14 @@
     ) -> ListLensSharesOutputTypeDef:
         """
         List the lens shares associated with the lens.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.list_lens_shares)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#list_lens_shares)
         """
-
     async def list_lenses(
         self,
         *,
         NextToken: str = ...,
         MaxResults: int = ...,
         LensType: LensTypeType = ...,
         LensStatus: LensStatusTypeType = ...,
@@ -480,59 +554,93 @@
     ) -> ListLensesOutputTypeDef:
         """
         List the available lenses.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.list_lenses)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#list_lenses)
         """
-
     async def list_milestones(
         self, *, WorkloadId: str, NextToken: str = ..., MaxResults: int = ...
     ) -> ListMilestonesOutputTypeDef:
         """
         List all milestones for an existing workload.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.list_milestones)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#list_milestones)
         """
-
     async def list_notifications(
         self, *, WorkloadId: str = ..., NextToken: str = ..., MaxResults: int = ...
     ) -> ListNotificationsOutputTypeDef:
         """
         List lens notifications.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.list_notifications)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#list_notifications)
         """
+    async def list_profile_notifications(
+        self, *, WorkloadId: str = ..., NextToken: str = ..., MaxResults: int = ...
+    ) -> ListProfileNotificationsOutputTypeDef:
+        """
+        List profile notifications.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.list_profile_notifications)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#list_profile_notifications)
+        """
+    async def list_profile_shares(
+        self,
+        *,
+        ProfileArn: str,
+        SharedWithPrefix: str = ...,
+        NextToken: str = ...,
+        MaxResults: int = ...,
+        Status: ShareStatusType = ...
+    ) -> ListProfileSharesOutputTypeDef:
+        """
+        List profile shares.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.list_profile_shares)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#list_profile_shares)
+        """
+    async def list_profiles(
+        self,
+        *,
+        ProfileNamePrefix: str = ...,
+        ProfileOwnerType: ProfileOwnerTypeType = ...,
+        NextToken: str = ...,
+        MaxResults: int = ...
+    ) -> ListProfilesOutputTypeDef:
+        """
+        List profiles.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.list_profiles)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#list_profiles)
+        """
     async def list_share_invitations(
         self,
         *,
         WorkloadNamePrefix: str = ...,
         LensNamePrefix: str = ...,
         ShareResourceType: ShareResourceTypeType = ...,
         NextToken: str = ...,
-        MaxResults: int = ...
+        MaxResults: int = ...,
+        ProfileNamePrefix: str = ...
     ) -> ListShareInvitationsOutputTypeDef:
         """
         List the workload invitations.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.list_share_invitations)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#list_share_invitations)
         """
-
     async def list_tags_for_resource(self, *, WorkloadArn: str) -> ListTagsForResourceOutputTypeDef:
         """
         List the tags for a resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#list_tags_for_resource)
         """
-
     async def list_workload_shares(
         self,
         *,
         WorkloadId: str,
         SharedWithPrefix: str = ...,
         NextToken: str = ...,
         MaxResults: int = ...,
@@ -540,41 +648,37 @@
     ) -> ListWorkloadSharesOutputTypeDef:
         """
         List the workload shares associated with the workload.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.list_workload_shares)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#list_workload_shares)
         """
-
     async def list_workloads(
         self, *, WorkloadNamePrefix: str = ..., NextToken: str = ..., MaxResults: int = ...
     ) -> ListWorkloadsOutputTypeDef:
         """
-        List workloads.
+        Paginated list of workloads.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.list_workloads)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#list_workloads)
         """
-
     async def tag_resource(self, *, WorkloadArn: str, Tags: Mapping[str, str]) -> Dict[str, Any]:
         """
         Adds one or more tags to the specified resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#tag_resource)
         """
-
     async def untag_resource(self, *, WorkloadArn: str, TagKeys: Sequence[str]) -> Dict[str, Any]:
         """
         Deletes specified tags from a resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#untag_resource)
         """
-
     async def update_answer(
         self,
         *,
         WorkloadId: str,
         LensAlias: str,
         QuestionId: str,
         SelectedChoices: Sequence[str] = ...,
@@ -585,51 +689,63 @@
     ) -> UpdateAnswerOutputTypeDef:
         """
         Update the answer to a specific question in a workload review.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.update_answer)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#update_answer)
         """
-
     async def update_global_settings(
-        self, *, OrganizationSharingStatus: OrganizationSharingStatusType = ...
+        self,
+        *,
+        OrganizationSharingStatus: OrganizationSharingStatusType = ...,
+        DiscoveryIntegrationStatus: DiscoveryIntegrationStatusType = ...
     ) -> EmptyResponseMetadataTypeDef:
         """
         Updates whether the Amazon Web Services account is opted into organization
-        sharing features.
+        sharing and discovery integration features.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.update_global_settings)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#update_global_settings)
         """
-
     async def update_lens_review(
         self,
         *,
         WorkloadId: str,
         LensAlias: str,
         LensNotes: str = ...,
         PillarNotes: Mapping[str, str] = ...
     ) -> UpdateLensReviewOutputTypeDef:
         """
-        Update lens review.
+        Update lens review for a particular workload.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.update_lens_review)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#update_lens_review)
         """
+    async def update_profile(
+        self,
+        *,
+        ProfileArn: str,
+        ProfileDescription: str = ...,
+        ProfileQuestions: Sequence[ProfileQuestionUpdateTypeDef] = ...
+    ) -> UpdateProfileOutputTypeDef:
+        """
+        Update a profile.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.update_profile)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#update_profile)
+        """
     async def update_share_invitation(
         self, *, ShareInvitationId: str, ShareInvitationAction: ShareInvitationActionType
     ) -> UpdateShareInvitationOutputTypeDef:
         """
         Update a workload or custom lens share invitation.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.update_share_invitation)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#update_share_invitation)
         """
-
     async def update_workload(
         self,
         *,
         WorkloadId: str,
         WorkloadName: str = ...,
         Description: str = ...,
         Environment: WorkloadEnvironmentType = ...,
@@ -649,39 +765,49 @@
     ) -> UpdateWorkloadOutputTypeDef:
         """
         Update an existing workload.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.update_workload)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#update_workload)
         """
-
     async def update_workload_share(
         self, *, ShareId: str, WorkloadId: str, PermissionType: PermissionTypeType
     ) -> UpdateWorkloadShareOutputTypeDef:
         """
         Update a workload share.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.update_workload_share)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#update_workload_share)
         """
-
     async def upgrade_lens_review(
         self, *, WorkloadId: str, LensAlias: str, MilestoneName: str, ClientRequestToken: str = ...
     ) -> EmptyResponseMetadataTypeDef:
         """
-        Upgrade lens review.
+        Upgrade lens review for a particular workload.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.upgrade_lens_review)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#upgrade_lens_review)
         """
+    async def upgrade_profile_version(
+        self,
+        *,
+        WorkloadId: str,
+        ProfileArn: str,
+        MilestoneName: str = ...,
+        ClientRequestToken: str = ...
+    ) -> EmptyResponseMetadataTypeDef:
+        """
+        Upgrade a profile.
 
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.upgrade_profile_version)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#upgrade_profile_version)
+        """
     async def __aenter__(self) -> "WellArchitectedClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/)
         """
-
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/)
         """
```

### Comparing `types-aiobotocore-wellarchitected-2.5.0.post1/types_aiobotocore_wellarchitected/client.pyi` & `types-aiobotocore-wellarchitected-2.5.1/types_aiobotocore_wellarchitected/client.py`

 * *Files 9% similar despite different names*

```diff
@@ -17,81 +17,98 @@
 from typing import Any, Dict, Mapping, Sequence, Type
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import (
     AnswerReasonType,
+    DiscoveryIntegrationStatusType,
     LensStatusTypeType,
     LensTypeType,
     OrganizationSharingStatusType,
     PermissionTypeType,
+    ProfileOwnerTypeType,
+    QuestionPriorityType,
+    ReportFormatType,
     ShareInvitationActionType,
     ShareResourceTypeType,
     ShareStatusType,
     WorkloadEnvironmentType,
     WorkloadImprovementStatusType,
 )
 from .type_defs import (
     ChoiceUpdateTypeDef,
     CreateLensShareOutputTypeDef,
     CreateLensVersionOutputTypeDef,
     CreateMilestoneOutputTypeDef,
+    CreateProfileOutputTypeDef,
+    CreateProfileShareOutputTypeDef,
     CreateWorkloadOutputTypeDef,
     CreateWorkloadShareOutputTypeDef,
     EmptyResponseMetadataTypeDef,
     ExportLensOutputTypeDef,
     GetAnswerOutputTypeDef,
+    GetConsolidatedReportOutputTypeDef,
     GetLensOutputTypeDef,
     GetLensReviewOutputTypeDef,
     GetLensReviewReportOutputTypeDef,
     GetLensVersionDifferenceOutputTypeDef,
     GetMilestoneOutputTypeDef,
+    GetProfileOutputTypeDef,
+    GetProfileTemplateOutputTypeDef,
     GetWorkloadOutputTypeDef,
     ImportLensOutputTypeDef,
     ListAnswersOutputTypeDef,
     ListCheckDetailsOutputTypeDef,
     ListCheckSummariesOutputTypeDef,
     ListLensesOutputTypeDef,
     ListLensReviewImprovementsOutputTypeDef,
     ListLensReviewsOutputTypeDef,
     ListLensSharesOutputTypeDef,
     ListMilestonesOutputTypeDef,
     ListNotificationsOutputTypeDef,
+    ListProfileNotificationsOutputTypeDef,
+    ListProfileSharesOutputTypeDef,
+    ListProfilesOutputTypeDef,
     ListShareInvitationsOutputTypeDef,
     ListTagsForResourceOutputTypeDef,
     ListWorkloadSharesOutputTypeDef,
     ListWorkloadsOutputTypeDef,
+    ProfileQuestionUpdateTypeDef,
     UpdateAnswerOutputTypeDef,
     UpdateLensReviewOutputTypeDef,
+    UpdateProfileOutputTypeDef,
     UpdateShareInvitationOutputTypeDef,
     UpdateWorkloadOutputTypeDef,
     UpdateWorkloadShareOutputTypeDef,
     WorkloadDiscoveryConfigTypeDef,
 )
 
 __all__ = ("WellArchitectedClient",)
 
+
 class BotocoreClientError(BaseException):
     MSG_TEMPLATE: str
 
     def __init__(self, error_response: Mapping[str, Any], operation_name: str) -> None:
         self.response: Dict[str, Any]
         self.operation_name: str
 
+
 class Exceptions:
     AccessDeniedException: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
     ConflictException: Type[BotocoreClientError]
     InternalServerException: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
     ServiceQuotaExceededException: Type[BotocoreClientError]
     ThrottlingException: Type[BotocoreClientError]
     ValidationException: Type[BotocoreClientError]
 
+
 class WellArchitectedClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/)
     """
 
     meta: ClientMeta
@@ -100,69 +117,112 @@
     def exceptions(self) -> Exceptions:
         """
         WellArchitectedClient exceptions.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.exceptions)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#exceptions)
         """
+
     async def associate_lenses(
         self, *, WorkloadId: str, LensAliases: Sequence[str]
     ) -> EmptyResponseMetadataTypeDef:
         """
         Associate a lens to a workload.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.associate_lenses)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#associate_lenses)
         """
+
+    async def associate_profiles(
+        self, *, WorkloadId: str, ProfileArns: Sequence[str]
+    ) -> EmptyResponseMetadataTypeDef:
+        """
+        Associate a profile with a workload.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.associate_profiles)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#associate_profiles)
+        """
+
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#can_paginate)
         """
+
     async def close(self) -> None:
         """
         Closes underlying endpoint connections.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.close)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#close)
         """
+
     async def create_lens_share(
         self, *, LensAlias: str, SharedWith: str, ClientRequestToken: str
     ) -> CreateLensShareOutputTypeDef:
         """
         Create a lens share.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.create_lens_share)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#create_lens_share)
         """
+
     async def create_lens_version(
         self,
         *,
         LensAlias: str,
         LensVersion: str,
         ClientRequestToken: str,
         IsMajorVersion: bool = ...
     ) -> CreateLensVersionOutputTypeDef:
         """
         Create a new lens version.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.create_lens_version)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#create_lens_version)
         """
+
     async def create_milestone(
         self, *, WorkloadId: str, MilestoneName: str, ClientRequestToken: str
     ) -> CreateMilestoneOutputTypeDef:
         """
         Create a milestone for an existing workload.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.create_milestone)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#create_milestone)
         """
+
+    async def create_profile(
+        self,
+        *,
+        ProfileName: str,
+        ProfileDescription: str,
+        ProfileQuestions: Sequence[ProfileQuestionUpdateTypeDef],
+        ClientRequestToken: str,
+        Tags: Mapping[str, str] = ...
+    ) -> CreateProfileOutputTypeDef:
+        """
+        Create a profile.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.create_profile)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#create_profile)
+        """
+
+    async def create_profile_share(
+        self, *, ProfileArn: str, SharedWith: str, ClientRequestToken: str
+    ) -> CreateProfileShareOutputTypeDef:
+        """
+        Create a profile share.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.create_profile_share)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#create_profile_share)
+        """
+
     async def create_workload(
         self,
         *,
         WorkloadName: str,
         Description: str,
         Environment: WorkloadEnvironmentType,
         Lenses: Sequence[str],
@@ -174,192 +234,275 @@
         ArchitecturalDesign: str = ...,
         ReviewOwner: str = ...,
         IndustryType: str = ...,
         Industry: str = ...,
         Notes: str = ...,
         Tags: Mapping[str, str] = ...,
         DiscoveryConfig: WorkloadDiscoveryConfigTypeDef = ...,
-        Applications: Sequence[str] = ...
+        Applications: Sequence[str] = ...,
+        ProfileArns: Sequence[str] = ...
     ) -> CreateWorkloadOutputTypeDef:
         """
         Create a new workload.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.create_workload)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#create_workload)
         """
+
     async def create_workload_share(
         self,
         *,
         WorkloadId: str,
         SharedWith: str,
         PermissionType: PermissionTypeType,
         ClientRequestToken: str
     ) -> CreateWorkloadShareOutputTypeDef:
         """
         Create a workload share.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.create_workload_share)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#create_workload_share)
         """
+
     async def delete_lens(
         self, *, LensAlias: str, ClientRequestToken: str, LensStatus: LensStatusTypeType
     ) -> EmptyResponseMetadataTypeDef:
         """
         Delete an existing lens.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.delete_lens)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#delete_lens)
         """
+
     async def delete_lens_share(
         self, *, ShareId: str, LensAlias: str, ClientRequestToken: str
     ) -> EmptyResponseMetadataTypeDef:
         """
         Delete a lens share.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.delete_lens_share)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#delete_lens_share)
         """
+
+    async def delete_profile(
+        self, *, ProfileArn: str, ClientRequestToken: str
+    ) -> EmptyResponseMetadataTypeDef:
+        """
+        Delete a profile.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.delete_profile)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#delete_profile)
+        """
+
+    async def delete_profile_share(
+        self, *, ShareId: str, ProfileArn: str, ClientRequestToken: str
+    ) -> EmptyResponseMetadataTypeDef:
+        """
+        Delete a profile share.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.delete_profile_share)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#delete_profile_share)
+        """
+
     async def delete_workload(
         self, *, WorkloadId: str, ClientRequestToken: str
     ) -> EmptyResponseMetadataTypeDef:
         """
         Delete an existing workload.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.delete_workload)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#delete_workload)
         """
+
     async def delete_workload_share(
         self, *, ShareId: str, WorkloadId: str, ClientRequestToken: str
     ) -> EmptyResponseMetadataTypeDef:
         """
         Delete a workload share.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.delete_workload_share)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#delete_workload_share)
         """
+
     async def disassociate_lenses(
         self, *, WorkloadId: str, LensAliases: Sequence[str]
     ) -> EmptyResponseMetadataTypeDef:
         """
         Disassociate a lens from a workload.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.disassociate_lenses)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#disassociate_lenses)
         """
+
+    async def disassociate_profiles(
+        self, *, WorkloadId: str, ProfileArns: Sequence[str]
+    ) -> EmptyResponseMetadataTypeDef:
+        """
+        Disassociate a profile from a workload.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.disassociate_profiles)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#disassociate_profiles)
+        """
+
     async def export_lens(
         self, *, LensAlias: str, LensVersion: str = ...
     ) -> ExportLensOutputTypeDef:
         """
         Export an existing lens.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.export_lens)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#export_lens)
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
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#generate_presigned_url)
         """
+
     async def get_answer(
         self, *, WorkloadId: str, LensAlias: str, QuestionId: str, MilestoneNumber: int = ...
     ) -> GetAnswerOutputTypeDef:
         """
         Get the answer to a specific question in a workload review.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.get_answer)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#get_answer)
         """
+
+    async def get_consolidated_report(
+        self,
+        *,
+        Format: ReportFormatType,
+        IncludeSharedResources: bool = ...,
+        NextToken: str = ...,
+        MaxResults: int = ...
+    ) -> GetConsolidatedReportOutputTypeDef:
+        """
+        Get a consolidated report of your workloads.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.get_consolidated_report)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#get_consolidated_report)
+        """
+
     async def get_lens(self, *, LensAlias: str, LensVersion: str = ...) -> GetLensOutputTypeDef:
         """
         Get an existing lens.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.get_lens)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#get_lens)
         """
+
     async def get_lens_review(
         self, *, WorkloadId: str, LensAlias: str, MilestoneNumber: int = ...
     ) -> GetLensReviewOutputTypeDef:
         """
         Get lens review.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.get_lens_review)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#get_lens_review)
         """
+
     async def get_lens_review_report(
         self, *, WorkloadId: str, LensAlias: str, MilestoneNumber: int = ...
     ) -> GetLensReviewReportOutputTypeDef:
         """
         Get lens review report.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.get_lens_review_report)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#get_lens_review_report)
         """
+
     async def get_lens_version_difference(
         self, *, LensAlias: str, BaseLensVersion: str = ..., TargetLensVersion: str = ...
     ) -> GetLensVersionDifferenceOutputTypeDef:
         """
         Get lens version differences.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.get_lens_version_difference)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#get_lens_version_difference)
         """
+
     async def get_milestone(
         self, *, WorkloadId: str, MilestoneNumber: int
     ) -> GetMilestoneOutputTypeDef:
         """
         Get a milestone for an existing workload.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.get_milestone)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#get_milestone)
         """
+
+    async def get_profile(
+        self, *, ProfileArn: str, ProfileVersion: str = ...
+    ) -> GetProfileOutputTypeDef:
+        """
+        Get profile information.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.get_profile)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#get_profile)
+        """
+
+    async def get_profile_template(self) -> GetProfileTemplateOutputTypeDef:
+        """
+        Get profile template.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.get_profile_template)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#get_profile_template)
+        """
+
     async def get_workload(self, *, WorkloadId: str) -> GetWorkloadOutputTypeDef:
         """
         Get an existing workload.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.get_workload)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#get_workload)
         """
+
     async def import_lens(
         self,
         *,
         JSONString: str,
         ClientRequestToken: str,
         LensAlias: str = ...,
         Tags: Mapping[str, str] = ...
     ) -> ImportLensOutputTypeDef:
         """
-        Import a new lens.
+        Import a new custom lens or update an existing custom lens.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.import_lens)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#import_lens)
         """
+
     async def list_answers(
         self,
         *,
         WorkloadId: str,
         LensAlias: str,
         PillarId: str = ...,
         MilestoneNumber: int = ...,
         NextToken: str = ...,
-        MaxResults: int = ...
+        MaxResults: int = ...,
+        QuestionPriority: QuestionPriorityType = ...
     ) -> ListAnswersOutputTypeDef:
         """
-        List of answers.
+        List of answers for a particular workload and lens.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.list_answers)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#list_answers)
         """
+
     async def list_check_details(
         self,
         *,
         WorkloadId: str,
         LensArn: str,
         PillarId: str,
         QuestionId: str,
@@ -369,14 +512,15 @@
     ) -> ListCheckDetailsOutputTypeDef:
         """
         List of Trusted Advisor check details by account related to the workload.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.list_check_details)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#list_check_details)
         """
+
     async def list_check_summaries(
         self,
         *,
         WorkloadId: str,
         LensArn: str,
         PillarId: str,
         QuestionId: str,
@@ -387,44 +531,48 @@
         """
         List of Trusted Advisor checks summarized for all accounts related to the
         workload.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.list_check_summaries)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#list_check_summaries)
         """
+
     async def list_lens_review_improvements(
         self,
         *,
         WorkloadId: str,
         LensAlias: str,
         PillarId: str = ...,
         MilestoneNumber: int = ...,
         NextToken: str = ...,
-        MaxResults: int = ...
+        MaxResults: int = ...,
+        QuestionPriority: QuestionPriorityType = ...
     ) -> ListLensReviewImprovementsOutputTypeDef:
         """
         List lens review improvements.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.list_lens_review_improvements)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#list_lens_review_improvements)
         """
+
     async def list_lens_reviews(
         self,
         *,
         WorkloadId: str,
         MilestoneNumber: int = ...,
         NextToken: str = ...,
         MaxResults: int = ...
     ) -> ListLensReviewsOutputTypeDef:
         """
-        List lens reviews.
+        List lens reviews for a particular workload.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.list_lens_reviews)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#list_lens_reviews)
         """
+
     async def list_lens_shares(
         self,
         *,
         LensAlias: str,
         SharedWithPrefix: str = ...,
         NextToken: str = ...,
         MaxResults: int = ...,
@@ -432,14 +580,15 @@
     ) -> ListLensSharesOutputTypeDef:
         """
         List the lens shares associated with the lens.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.list_lens_shares)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#list_lens_shares)
         """
+
     async def list_lenses(
         self,
         *,
         NextToken: str = ...,
         MaxResults: int = ...,
         LensType: LensTypeType = ...,
         LensStatus: LensStatusTypeType = ...,
@@ -447,54 +596,101 @@
     ) -> ListLensesOutputTypeDef:
         """
         List the available lenses.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.list_lenses)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#list_lenses)
         """
+
     async def list_milestones(
         self, *, WorkloadId: str, NextToken: str = ..., MaxResults: int = ...
     ) -> ListMilestonesOutputTypeDef:
         """
         List all milestones for an existing workload.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.list_milestones)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#list_milestones)
         """
+
     async def list_notifications(
         self, *, WorkloadId: str = ..., NextToken: str = ..., MaxResults: int = ...
     ) -> ListNotificationsOutputTypeDef:
         """
         List lens notifications.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.list_notifications)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#list_notifications)
         """
+
+    async def list_profile_notifications(
+        self, *, WorkloadId: str = ..., NextToken: str = ..., MaxResults: int = ...
+    ) -> ListProfileNotificationsOutputTypeDef:
+        """
+        List profile notifications.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.list_profile_notifications)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#list_profile_notifications)
+        """
+
+    async def list_profile_shares(
+        self,
+        *,
+        ProfileArn: str,
+        SharedWithPrefix: str = ...,
+        NextToken: str = ...,
+        MaxResults: int = ...,
+        Status: ShareStatusType = ...
+    ) -> ListProfileSharesOutputTypeDef:
+        """
+        List profile shares.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.list_profile_shares)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#list_profile_shares)
+        """
+
+    async def list_profiles(
+        self,
+        *,
+        ProfileNamePrefix: str = ...,
+        ProfileOwnerType: ProfileOwnerTypeType = ...,
+        NextToken: str = ...,
+        MaxResults: int = ...
+    ) -> ListProfilesOutputTypeDef:
+        """
+        List profiles.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.list_profiles)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#list_profiles)
+        """
+
     async def list_share_invitations(
         self,
         *,
         WorkloadNamePrefix: str = ...,
         LensNamePrefix: str = ...,
         ShareResourceType: ShareResourceTypeType = ...,
         NextToken: str = ...,
-        MaxResults: int = ...
+        MaxResults: int = ...,
+        ProfileNamePrefix: str = ...
     ) -> ListShareInvitationsOutputTypeDef:
         """
         List the workload invitations.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.list_share_invitations)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#list_share_invitations)
         """
+
     async def list_tags_for_resource(self, *, WorkloadArn: str) -> ListTagsForResourceOutputTypeDef:
         """
         List the tags for a resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#list_tags_for_resource)
         """
+
     async def list_workload_shares(
         self,
         *,
         WorkloadId: str,
         SharedWithPrefix: str = ...,
         NextToken: str = ...,
         MaxResults: int = ...,
@@ -502,37 +698,41 @@
     ) -> ListWorkloadSharesOutputTypeDef:
         """
         List the workload shares associated with the workload.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.list_workload_shares)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#list_workload_shares)
         """
+
     async def list_workloads(
         self, *, WorkloadNamePrefix: str = ..., NextToken: str = ..., MaxResults: int = ...
     ) -> ListWorkloadsOutputTypeDef:
         """
-        List workloads.
+        Paginated list of workloads.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.list_workloads)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#list_workloads)
         """
+
     async def tag_resource(self, *, WorkloadArn: str, Tags: Mapping[str, str]) -> Dict[str, Any]:
         """
         Adds one or more tags to the specified resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#tag_resource)
         """
+
     async def untag_resource(self, *, WorkloadArn: str, TagKeys: Sequence[str]) -> Dict[str, Any]:
         """
         Deletes specified tags from a resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#untag_resource)
         """
+
     async def update_answer(
         self,
         *,
         WorkloadId: str,
         LensAlias: str,
         QuestionId: str,
         SelectedChoices: Sequence[str] = ...,
@@ -543,47 +743,68 @@
     ) -> UpdateAnswerOutputTypeDef:
         """
         Update the answer to a specific question in a workload review.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.update_answer)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#update_answer)
         """
+
     async def update_global_settings(
-        self, *, OrganizationSharingStatus: OrganizationSharingStatusType = ...
+        self,
+        *,
+        OrganizationSharingStatus: OrganizationSharingStatusType = ...,
+        DiscoveryIntegrationStatus: DiscoveryIntegrationStatusType = ...
     ) -> EmptyResponseMetadataTypeDef:
         """
         Updates whether the Amazon Web Services account is opted into organization
-        sharing features.
+        sharing and discovery integration features.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.update_global_settings)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#update_global_settings)
         """
+
     async def update_lens_review(
         self,
         *,
         WorkloadId: str,
         LensAlias: str,
         LensNotes: str = ...,
         PillarNotes: Mapping[str, str] = ...
     ) -> UpdateLensReviewOutputTypeDef:
         """
-        Update lens review.
+        Update lens review for a particular workload.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.update_lens_review)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#update_lens_review)
         """
+
+    async def update_profile(
+        self,
+        *,
+        ProfileArn: str,
+        ProfileDescription: str = ...,
+        ProfileQuestions: Sequence[ProfileQuestionUpdateTypeDef] = ...
+    ) -> UpdateProfileOutputTypeDef:
+        """
+        Update a profile.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.update_profile)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#update_profile)
+        """
+
     async def update_share_invitation(
         self, *, ShareInvitationId: str, ShareInvitationAction: ShareInvitationActionType
     ) -> UpdateShareInvitationOutputTypeDef:
         """
         Update a workload or custom lens share invitation.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.update_share_invitation)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#update_share_invitation)
         """
+
     async def update_workload(
         self,
         *,
         WorkloadId: str,
         WorkloadName: str = ...,
         Description: str = ...,
         Environment: WorkloadEnvironmentType = ...,
@@ -603,35 +824,54 @@
     ) -> UpdateWorkloadOutputTypeDef:
         """
         Update an existing workload.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.update_workload)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#update_workload)
         """
+
     async def update_workload_share(
         self, *, ShareId: str, WorkloadId: str, PermissionType: PermissionTypeType
     ) -> UpdateWorkloadShareOutputTypeDef:
         """
         Update a workload share.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.update_workload_share)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#update_workload_share)
         """
+
     async def upgrade_lens_review(
         self, *, WorkloadId: str, LensAlias: str, MilestoneName: str, ClientRequestToken: str = ...
     ) -> EmptyResponseMetadataTypeDef:
         """
-        Upgrade lens review.
+        Upgrade lens review for a particular workload.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.upgrade_lens_review)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#upgrade_lens_review)
         """
+
+    async def upgrade_profile_version(
+        self,
+        *,
+        WorkloadId: str,
+        ProfileArn: str,
+        MilestoneName: str = ...,
+        ClientRequestToken: str = ...
+    ) -> EmptyResponseMetadataTypeDef:
+        """
+        Upgrade a profile.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client.upgrade_profile_version)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/#upgrade_profile_version)
+        """
+
     async def __aenter__(self) -> "WellArchitectedClient":
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/)
         """
+
     async def __aexit__(self, exc_type: Any, exc_val: Any, exc_tb: Any) -> Any:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/wellarchitected.html#WellArchitected.Client)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_wellarchitected/client/)
         """
```

### Comparing `types-aiobotocore-wellarchitected-2.5.0.post1/types_aiobotocore_wellarchitected/literals.py` & `types-aiobotocore-wellarchitected-2.5.1/types_aiobotocore_wellarchitected/literals.py`

 * *Files 4% similar despite different names*

```diff
@@ -23,22 +23,30 @@
     "AdditionalResourceTypeType",
     "AnswerReasonType",
     "CheckFailureReasonType",
     "CheckProviderType",
     "CheckStatusType",
     "ChoiceReasonType",
     "ChoiceStatusType",
+    "DefinitionTypeType",
     "DifferenceStatusType",
+    "DiscoveryIntegrationStatusType",
     "ImportLensStatusType",
     "LensStatusType",
     "LensStatusTypeType",
     "LensTypeType",
+    "MetricTypeType",
     "NotificationTypeType",
     "OrganizationSharingStatusType",
     "PermissionTypeType",
+    "ProfileNotificationTypeType",
+    "ProfileOwnerTypeType",
+    "QuestionPriorityType",
+    "QuestionTypeType",
+    "ReportFormatType",
     "RiskType",
     "ShareInvitationActionType",
     "ShareResourceTypeType",
     "ShareStatusType",
     "TrustedAdvisorIntegrationStatusType",
     "WorkloadEnvironmentType",
     "WorkloadImprovementStatusType",
@@ -58,25 +66,33 @@
 ]
 CheckProviderType = Literal["TRUSTED_ADVISOR"]
 CheckStatusType = Literal["ERROR", "FETCH_FAILED", "NOT_AVAILABLE", "OKAY", "WARNING"]
 ChoiceReasonType = Literal[
     "ARCHITECTURE_CONSTRAINTS", "BUSINESS_PRIORITIES", "NONE", "OTHER", "OUT_OF_SCOPE"
 ]
 ChoiceStatusType = Literal["NOT_APPLICABLE", "SELECTED", "UNSELECTED"]
+DefinitionTypeType = Literal["APP_REGISTRY", "WORKLOAD_METADATA"]
 DifferenceStatusType = Literal["DELETED", "NEW", "UPDATED"]
+DiscoveryIntegrationStatusType = Literal["DISABLED", "ENABLED"]
 ImportLensStatusType = Literal["COMPLETE", "ERROR", "IN_PROGRESS"]
 LensStatusType = Literal["CURRENT", "DELETED", "DEPRECATED", "NOT_CURRENT", "UNSHARED"]
 LensStatusTypeType = Literal["ALL", "DRAFT", "PUBLISHED"]
 LensTypeType = Literal["AWS_OFFICIAL", "CUSTOM_SELF", "CUSTOM_SHARED"]
+MetricTypeType = Literal["WORKLOAD"]
 NotificationTypeType = Literal["LENS_VERSION_DEPRECATED", "LENS_VERSION_UPGRADED"]
 OrganizationSharingStatusType = Literal["DISABLED", "ENABLED"]
 PermissionTypeType = Literal["CONTRIBUTOR", "READONLY"]
+ProfileNotificationTypeType = Literal["PROFILE_ANSWERS_UPDATED", "PROFILE_DELETED"]
+ProfileOwnerTypeType = Literal["SELF", "SHARED"]
+QuestionPriorityType = Literal["NONE", "PRIORITIZED"]
+QuestionTypeType = Literal["NON_PRIORITIZED", "PRIORITIZED"]
+ReportFormatType = Literal["JSON", "PDF"]
 RiskType = Literal["HIGH", "MEDIUM", "NONE", "NOT_APPLICABLE", "UNANSWERED"]
 ShareInvitationActionType = Literal["ACCEPT", "REJECT"]
-ShareResourceTypeType = Literal["LENS", "WORKLOAD"]
+ShareResourceTypeType = Literal["LENS", "PROFILE", "WORKLOAD"]
 ShareStatusType = Literal[
     "ACCEPTED", "ASSOCIATED", "ASSOCIATING", "EXPIRED", "FAILED", "PENDING", "REJECTED", "REVOKED"
 ]
 TrustedAdvisorIntegrationStatusType = Literal["DISABLED", "ENABLED"]
 WorkloadEnvironmentType = Literal["PREPRODUCTION", "PRODUCTION"]
 WorkloadImprovementStatusType = Literal[
     "COMPLETE", "IN_PROGRESS", "NOT_APPLICABLE", "NOT_STARTED", "RISK_ACKNOWLEDGED"
@@ -140,14 +156,15 @@
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
@@ -226,14 +243,15 @@
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
@@ -244,14 +262,15 @@
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
@@ -287,14 +306,15 @@
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
@@ -313,16 +333,19 @@
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
@@ -406,15 +429,17 @@
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

### Comparing `types-aiobotocore-wellarchitected-2.5.0.post1/types_aiobotocore_wellarchitected/literals.pyi` & `types-aiobotocore-wellarchitected-2.5.1/types_aiobotocore_wellarchitected/literals.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -22,22 +22,30 @@
     "AdditionalResourceTypeType",
     "AnswerReasonType",
     "CheckFailureReasonType",
     "CheckProviderType",
     "CheckStatusType",
     "ChoiceReasonType",
     "ChoiceStatusType",
+    "DefinitionTypeType",
     "DifferenceStatusType",
+    "DiscoveryIntegrationStatusType",
     "ImportLensStatusType",
     "LensStatusType",
     "LensStatusTypeType",
     "LensTypeType",
+    "MetricTypeType",
     "NotificationTypeType",
     "OrganizationSharingStatusType",
     "PermissionTypeType",
+    "ProfileNotificationTypeType",
+    "ProfileOwnerTypeType",
+    "QuestionPriorityType",
+    "QuestionTypeType",
+    "ReportFormatType",
     "RiskType",
     "ShareInvitationActionType",
     "ShareResourceTypeType",
     "ShareStatusType",
     "TrustedAdvisorIntegrationStatusType",
     "WorkloadEnvironmentType",
     "WorkloadImprovementStatusType",
@@ -56,25 +64,33 @@
 ]
 CheckProviderType = Literal["TRUSTED_ADVISOR"]
 CheckStatusType = Literal["ERROR", "FETCH_FAILED", "NOT_AVAILABLE", "OKAY", "WARNING"]
 ChoiceReasonType = Literal[
     "ARCHITECTURE_CONSTRAINTS", "BUSINESS_PRIORITIES", "NONE", "OTHER", "OUT_OF_SCOPE"
 ]
 ChoiceStatusType = Literal["NOT_APPLICABLE", "SELECTED", "UNSELECTED"]
+DefinitionTypeType = Literal["APP_REGISTRY", "WORKLOAD_METADATA"]
 DifferenceStatusType = Literal["DELETED", "NEW", "UPDATED"]
+DiscoveryIntegrationStatusType = Literal["DISABLED", "ENABLED"]
 ImportLensStatusType = Literal["COMPLETE", "ERROR", "IN_PROGRESS"]
 LensStatusType = Literal["CURRENT", "DELETED", "DEPRECATED", "NOT_CURRENT", "UNSHARED"]
 LensStatusTypeType = Literal["ALL", "DRAFT", "PUBLISHED"]
 LensTypeType = Literal["AWS_OFFICIAL", "CUSTOM_SELF", "CUSTOM_SHARED"]
+MetricTypeType = Literal["WORKLOAD"]
 NotificationTypeType = Literal["LENS_VERSION_DEPRECATED", "LENS_VERSION_UPGRADED"]
 OrganizationSharingStatusType = Literal["DISABLED", "ENABLED"]
 PermissionTypeType = Literal["CONTRIBUTOR", "READONLY"]
+ProfileNotificationTypeType = Literal["PROFILE_ANSWERS_UPDATED", "PROFILE_DELETED"]
+ProfileOwnerTypeType = Literal["SELF", "SHARED"]
+QuestionPriorityType = Literal["NONE", "PRIORITIZED"]
+QuestionTypeType = Literal["NON_PRIORITIZED", "PRIORITIZED"]
+ReportFormatType = Literal["JSON", "PDF"]
 RiskType = Literal["HIGH", "MEDIUM", "NONE", "NOT_APPLICABLE", "UNANSWERED"]
 ShareInvitationActionType = Literal["ACCEPT", "REJECT"]
-ShareResourceTypeType = Literal["LENS", "WORKLOAD"]
+ShareResourceTypeType = Literal["LENS", "PROFILE", "WORKLOAD"]
 ShareStatusType = Literal[
     "ACCEPTED", "ASSOCIATED", "ASSOCIATING", "EXPIRED", "FAILED", "PENDING", "REJECTED", "REVOKED"
 ]
 TrustedAdvisorIntegrationStatusType = Literal["DISABLED", "ENABLED"]
 WorkloadEnvironmentType = Literal["PREPRODUCTION", "PRODUCTION"]
 WorkloadImprovementStatusType = Literal[
     "COMPLETE", "IN_PROGRESS", "NOT_APPLICABLE", "NOT_STARTED", "RISK_ACKNOWLEDGED"
@@ -138,14 +154,15 @@
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
@@ -224,14 +241,15 @@
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
@@ -242,14 +260,15 @@
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
@@ -285,14 +304,15 @@
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
@@ -311,16 +331,19 @@
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
@@ -404,15 +427,17 @@
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

### Comparing `types-aiobotocore-wellarchitected-2.5.0.post1/types_aiobotocore_wellarchitected/type_defs.py` & `types-aiobotocore-wellarchitected-2.5.1/types_aiobotocore_wellarchitected/type_defs.py`

 * *Files 19% similar despite different names*

```diff
@@ -18,22 +18,29 @@
 from .literals import (
     AdditionalResourceTypeType,
     AnswerReasonType,
     CheckFailureReasonType,
     CheckStatusType,
     ChoiceReasonType,
     ChoiceStatusType,
+    DefinitionTypeType,
     DifferenceStatusType,
+    DiscoveryIntegrationStatusType,
     ImportLensStatusType,
     LensStatusType,
     LensStatusTypeType,
     LensTypeType,
     NotificationTypeType,
     OrganizationSharingStatusType,
     PermissionTypeType,
+    ProfileNotificationTypeType,
+    ProfileOwnerTypeType,
+    QuestionPriorityType,
+    QuestionTypeType,
+    ReportFormatType,
     RiskType,
     ShareInvitationActionType,
     ShareResourceTypeType,
     ShareStatusType,
     TrustedAdvisorIntegrationStatusType,
     WorkloadEnvironmentType,
     WorkloadImprovementStatusType,
@@ -50,119 +57,157 @@
 
 
 __all__ = (
     "ChoiceContentTypeDef",
     "ChoiceAnswerSummaryTypeDef",
     "ChoiceAnswerTypeDef",
     "AssociateLensesInputRequestTypeDef",
+    "AssociateProfilesInputRequestTypeDef",
+    "BestPracticeTypeDef",
     "CheckDetailTypeDef",
     "CheckSummaryTypeDef",
     "ChoiceImprovementPlanTypeDef",
     "ChoiceUpdateTypeDef",
     "CreateLensShareInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateLensShareOutputTypeDef",
     "CreateLensVersionInputRequestTypeDef",
+    "CreateLensVersionOutputTypeDef",
     "CreateMilestoneInputRequestTypeDef",
+    "CreateMilestoneOutputTypeDef",
+    "ProfileQuestionUpdateTypeDef",
+    "CreateProfileOutputTypeDef",
+    "CreateProfileShareInputRequestTypeDef",
+    "CreateProfileShareOutputTypeDef",
     "WorkloadDiscoveryConfigTypeDef",
+    "CreateWorkloadOutputTypeDef",
     "CreateWorkloadShareInputRequestTypeDef",
+    "CreateWorkloadShareOutputTypeDef",
     "DeleteLensInputRequestTypeDef",
     "DeleteLensShareInputRequestTypeDef",
+    "DeleteProfileInputRequestTypeDef",
+    "DeleteProfileShareInputRequestTypeDef",
     "DeleteWorkloadInputRequestTypeDef",
     "DeleteWorkloadShareInputRequestTypeDef",
     "DisassociateLensesInputRequestTypeDef",
+    "DisassociateProfilesInputRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "ExportLensInputRequestTypeDef",
+    "ExportLensOutputTypeDef",
     "GetAnswerInputRequestTypeDef",
+    "GetConsolidatedReportInputRequestTypeDef",
     "GetLensInputRequestTypeDef",
     "LensTypeDef",
     "GetLensReviewInputRequestTypeDef",
     "GetLensReviewReportInputRequestTypeDef",
     "LensReviewReportTypeDef",
     "GetLensVersionDifferenceInputRequestTypeDef",
     "GetMilestoneInputRequestTypeDef",
+    "GetProfileInputRequestTypeDef",
     "GetWorkloadInputRequestTypeDef",
     "ImportLensInputRequestTypeDef",
-    "LensReviewSummaryTypeDef",
+    "ImportLensOutputTypeDef",
+    "WorkloadProfileTypeDef",
     "PillarReviewSummaryTypeDef",
     "LensShareSummaryTypeDef",
     "LensSummaryTypeDef",
     "LensUpgradeSummaryTypeDef",
     "ListAnswersInputRequestTypeDef",
     "ListCheckDetailsInputRequestTypeDef",
     "ListCheckSummariesInputRequestTypeDef",
     "ListLensReviewImprovementsInputRequestTypeDef",
     "ListLensReviewsInputRequestTypeDef",
     "ListLensSharesInputRequestTypeDef",
     "ListLensesInputRequestTypeDef",
     "ListMilestonesInputRequestTypeDef",
     "ListNotificationsInputRequestTypeDef",
+    "ListProfileNotificationsInputRequestTypeDef",
+    "ProfileNotificationSummaryTypeDef",
+    "ListProfileSharesInputRequestTypeDef",
+    "ProfileShareSummaryTypeDef",
+    "ListProfilesInputRequestTypeDef",
+    "ProfileSummaryTypeDef",
     "ListShareInvitationsInputRequestTypeDef",
     "ShareInvitationSummaryTypeDef",
     "ListTagsForResourceInputRequestTypeDef",
+    "ListTagsForResourceOutputTypeDef",
     "ListWorkloadSharesInputRequestTypeDef",
     "WorkloadShareSummaryTypeDef",
     "ListWorkloadsInputRequestTypeDef",
-    "WorkloadSummaryTypeDef",
     "QuestionDifferenceTypeDef",
+    "ProfileChoiceTypeDef",
+    "ProfileTemplateChoiceTypeDef",
+    "ResponseMetadataTypeDef",
     "ShareInvitationTypeDef",
     "TagResourceInputRequestTypeDef",
     "UntagResourceInputRequestTypeDef",
     "UpdateGlobalSettingsInputRequestTypeDef",
     "UpdateLensReviewInputRequestTypeDef",
     "UpdateShareInvitationInputRequestTypeDef",
     "UpdateWorkloadShareInputRequestTypeDef",
     "WorkloadShareTypeDef",
     "UpgradeLensReviewInputRequestTypeDef",
+    "UpgradeProfileVersionInputRequestTypeDef",
     "AdditionalResourcesTypeDef",
-    "ImprovementSummaryTypeDef",
-    "UpdateAnswerInputRequestTypeDef",
-    "CreateLensShareOutputTypeDef",
-    "CreateLensVersionOutputTypeDef",
-    "CreateMilestoneOutputTypeDef",
-    "CreateWorkloadOutputTypeDef",
-    "CreateWorkloadShareOutputTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ExportLensOutputTypeDef",
-    "ImportLensOutputTypeDef",
+    "QuestionMetricTypeDef",
     "ListCheckDetailsOutputTypeDef",
     "ListCheckSummariesOutputTypeDef",
-    "ListTagsForResourceOutputTypeDef",
+    "ImprovementSummaryTypeDef",
+    "UpdateAnswerInputRequestTypeDef",
+    "CreateProfileInputRequestTypeDef",
+    "UpdateProfileInputRequestTypeDef",
     "CreateWorkloadInputRequestTypeDef",
     "UpdateWorkloadInputRequestTypeDef",
-    "WorkloadTypeDef",
     "GetLensOutputTypeDef",
     "GetLensReviewReportOutputTypeDef",
-    "ListLensReviewsOutputTypeDef",
+    "LensReviewSummaryTypeDef",
+    "WorkloadSummaryTypeDef",
+    "WorkloadTypeDef",
     "LensReviewTypeDef",
     "ListLensSharesOutputTypeDef",
     "ListLensesOutputTypeDef",
     "NotificationSummaryTypeDef",
+    "ListProfileNotificationsOutputTypeDef",
+    "ListProfileSharesOutputTypeDef",
+    "ListProfilesOutputTypeDef",
     "ListShareInvitationsOutputTypeDef",
     "ListWorkloadSharesOutputTypeDef",
-    "ListWorkloadsOutputTypeDef",
-    "MilestoneSummaryTypeDef",
     "PillarDifferenceTypeDef",
+    "ProfileQuestionTypeDef",
+    "ProfileTemplateQuestionTypeDef",
     "UpdateShareInvitationOutputTypeDef",
     "UpdateWorkloadShareOutputTypeDef",
     "ChoiceTypeDef",
+    "PillarMetricTypeDef",
     "ListLensReviewImprovementsOutputTypeDef",
+    "ListLensReviewsOutputTypeDef",
+    "ListWorkloadsOutputTypeDef",
+    "MilestoneSummaryTypeDef",
     "GetWorkloadOutputTypeDef",
     "MilestoneTypeDef",
     "UpdateWorkloadOutputTypeDef",
     "GetLensReviewOutputTypeDef",
     "UpdateLensReviewOutputTypeDef",
     "ListNotificationsOutputTypeDef",
-    "ListMilestonesOutputTypeDef",
     "VersionDifferencesTypeDef",
+    "ProfileTypeDef",
+    "ProfileTemplateTypeDef",
     "AnswerSummaryTypeDef",
     "AnswerTypeDef",
+    "LensMetricTypeDef",
+    "ListMilestonesOutputTypeDef",
     "GetMilestoneOutputTypeDef",
     "GetLensVersionDifferenceOutputTypeDef",
+    "GetProfileOutputTypeDef",
+    "UpdateProfileOutputTypeDef",
+    "GetProfileTemplateOutputTypeDef",
     "ListAnswersOutputTypeDef",
     "GetAnswerOutputTypeDef",
     "UpdateAnswerOutputTypeDef",
+    "ConsolidatedReportMetricTypeDef",
+    "GetConsolidatedReportOutputTypeDef",
 )
 
 ChoiceContentTypeDef = TypedDict(
     "ChoiceContentTypeDef",
     {
         "DisplayText": str,
         "Url": str,
@@ -195,14 +240,31 @@
     "AssociateLensesInputRequestTypeDef",
     {
         "WorkloadId": str,
         "LensAliases": Sequence[str],
     },
 )
 
+AssociateProfilesInputRequestTypeDef = TypedDict(
+    "AssociateProfilesInputRequestTypeDef",
+    {
+        "WorkloadId": str,
+        "ProfileArns": Sequence[str],
+    },
+)
+
+BestPracticeTypeDef = TypedDict(
+    "BestPracticeTypeDef",
+    {
+        "ChoiceId": str,
+        "ChoiceTitle": str,
+    },
+    total=False,
+)
+
 CheckDetailTypeDef = TypedDict(
     "CheckDetailTypeDef",
     {
         "Id": str,
         "Name": str,
         "Description": str,
         "Provider": Literal["TRUSTED_ADVISOR"],
@@ -272,22 +334,19 @@
     {
         "LensAlias": str,
         "SharedWith": str,
         "ClientRequestToken": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateLensShareOutputTypeDef = TypedDict(
+    "CreateLensShareOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ShareId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateLensVersionInputRequestTypeDef = TypedDict(
     "_RequiredCreateLensVersionInputRequestTypeDef",
     {
         "LensAlias": str,
@@ -306,41 +365,114 @@
 
 class CreateLensVersionInputRequestTypeDef(
     _RequiredCreateLensVersionInputRequestTypeDef, _OptionalCreateLensVersionInputRequestTypeDef
 ):
     pass
 
 
+CreateLensVersionOutputTypeDef = TypedDict(
+    "CreateLensVersionOutputTypeDef",
+    {
+        "LensArn": str,
+        "LensVersion": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateMilestoneInputRequestTypeDef = TypedDict(
     "CreateMilestoneInputRequestTypeDef",
     {
         "WorkloadId": str,
         "MilestoneName": str,
         "ClientRequestToken": str,
     },
 )
 
+CreateMilestoneOutputTypeDef = TypedDict(
+    "CreateMilestoneOutputTypeDef",
+    {
+        "WorkloadId": str,
+        "MilestoneNumber": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ProfileQuestionUpdateTypeDef = TypedDict(
+    "ProfileQuestionUpdateTypeDef",
+    {
+        "QuestionId": str,
+        "SelectedChoiceIds": Sequence[str],
+    },
+    total=False,
+)
+
+CreateProfileOutputTypeDef = TypedDict(
+    "CreateProfileOutputTypeDef",
+    {
+        "ProfileArn": str,
+        "ProfileVersion": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateProfileShareInputRequestTypeDef = TypedDict(
+    "CreateProfileShareInputRequestTypeDef",
+    {
+        "ProfileArn": str,
+        "SharedWith": str,
+        "ClientRequestToken": str,
+    },
+)
+
+CreateProfileShareOutputTypeDef = TypedDict(
+    "CreateProfileShareOutputTypeDef",
+    {
+        "ShareId": str,
+        "ProfileArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 WorkloadDiscoveryConfigTypeDef = TypedDict(
     "WorkloadDiscoveryConfigTypeDef",
     {
         "TrustedAdvisorIntegrationStatus": TrustedAdvisorIntegrationStatusType,
+        "WorkloadResourceDefinition": Sequence[DefinitionTypeType],
     },
     total=False,
 )
 
+CreateWorkloadOutputTypeDef = TypedDict(
+    "CreateWorkloadOutputTypeDef",
+    {
+        "WorkloadId": str,
+        "WorkloadArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateWorkloadShareInputRequestTypeDef = TypedDict(
     "CreateWorkloadShareInputRequestTypeDef",
     {
         "WorkloadId": str,
         "SharedWith": str,
         "PermissionType": PermissionTypeType,
         "ClientRequestToken": str,
     },
 )
 
+CreateWorkloadShareOutputTypeDef = TypedDict(
+    "CreateWorkloadShareOutputTypeDef",
+    {
+        "WorkloadId": str,
+        "ShareId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteLensInputRequestTypeDef = TypedDict(
     "DeleteLensInputRequestTypeDef",
     {
         "LensAlias": str,
         "ClientRequestToken": str,
         "LensStatus": LensStatusTypeType,
     },
@@ -351,14 +483,31 @@
     {
         "ShareId": str,
         "LensAlias": str,
         "ClientRequestToken": str,
     },
 )
 
+DeleteProfileInputRequestTypeDef = TypedDict(
+    "DeleteProfileInputRequestTypeDef",
+    {
+        "ProfileArn": str,
+        "ClientRequestToken": str,
+    },
+)
+
+DeleteProfileShareInputRequestTypeDef = TypedDict(
+    "DeleteProfileShareInputRequestTypeDef",
+    {
+        "ShareId": str,
+        "ProfileArn": str,
+        "ClientRequestToken": str,
+    },
+)
+
 DeleteWorkloadInputRequestTypeDef = TypedDict(
     "DeleteWorkloadInputRequestTypeDef",
     {
         "WorkloadId": str,
         "ClientRequestToken": str,
     },
 )
@@ -376,14 +525,29 @@
     "DisassociateLensesInputRequestTypeDef",
     {
         "WorkloadId": str,
         "LensAliases": Sequence[str],
     },
 )
 
+DisassociateProfilesInputRequestTypeDef = TypedDict(
+    "DisassociateProfilesInputRequestTypeDef",
+    {
+        "WorkloadId": str,
+        "ProfileArns": Sequence[str],
+    },
+)
+
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredExportLensInputRequestTypeDef = TypedDict(
     "_RequiredExportLensInputRequestTypeDef",
     {
         "LensAlias": str,
     },
 )
 _OptionalExportLensInputRequestTypeDef = TypedDict(
@@ -397,14 +561,22 @@
 
 class ExportLensInputRequestTypeDef(
     _RequiredExportLensInputRequestTypeDef, _OptionalExportLensInputRequestTypeDef
 ):
     pass
 
 
+ExportLensOutputTypeDef = TypedDict(
+    "ExportLensOutputTypeDef",
+    {
+        "LensJSON": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetAnswerInputRequestTypeDef = TypedDict(
     "_RequiredGetAnswerInputRequestTypeDef",
     {
         "WorkloadId": str,
         "LensAlias": str,
         "QuestionId": str,
     },
@@ -420,14 +592,38 @@
 
 class GetAnswerInputRequestTypeDef(
     _RequiredGetAnswerInputRequestTypeDef, _OptionalGetAnswerInputRequestTypeDef
 ):
     pass
 
 
+_RequiredGetConsolidatedReportInputRequestTypeDef = TypedDict(
+    "_RequiredGetConsolidatedReportInputRequestTypeDef",
+    {
+        "Format": ReportFormatType,
+    },
+)
+_OptionalGetConsolidatedReportInputRequestTypeDef = TypedDict(
+    "_OptionalGetConsolidatedReportInputRequestTypeDef",
+    {
+        "IncludeSharedResources": bool,
+        "NextToken": str,
+        "MaxResults": int,
+    },
+    total=False,
+)
+
+
+class GetConsolidatedReportInputRequestTypeDef(
+    _RequiredGetConsolidatedReportInputRequestTypeDef,
+    _OptionalGetConsolidatedReportInputRequestTypeDef,
+):
+    pass
+
+
 _RequiredGetLensInputRequestTypeDef = TypedDict(
     "_RequiredGetLensInputRequestTypeDef",
     {
         "LensAlias": str,
     },
 )
 _OptionalGetLensInputRequestTypeDef = TypedDict(
@@ -540,14 +736,35 @@
     "GetMilestoneInputRequestTypeDef",
     {
         "WorkloadId": str,
         "MilestoneNumber": int,
     },
 )
 
+_RequiredGetProfileInputRequestTypeDef = TypedDict(
+    "_RequiredGetProfileInputRequestTypeDef",
+    {
+        "ProfileArn": str,
+    },
+)
+_OptionalGetProfileInputRequestTypeDef = TypedDict(
+    "_OptionalGetProfileInputRequestTypeDef",
+    {
+        "ProfileVersion": str,
+    },
+    total=False,
+)
+
+
+class GetProfileInputRequestTypeDef(
+    _RequiredGetProfileInputRequestTypeDef, _OptionalGetProfileInputRequestTypeDef
+):
+    pass
+
+
 GetWorkloadInputRequestTypeDef = TypedDict(
     "GetWorkloadInputRequestTypeDef",
     {
         "WorkloadId": str,
     },
 )
 
@@ -570,35 +787,40 @@
 
 class ImportLensInputRequestTypeDef(
     _RequiredImportLensInputRequestTypeDef, _OptionalImportLensInputRequestTypeDef
 ):
     pass
 
 
-LensReviewSummaryTypeDef = TypedDict(
-    "LensReviewSummaryTypeDef",
+ImportLensOutputTypeDef = TypedDict(
+    "ImportLensOutputTypeDef",
     {
-        "LensAlias": str,
         "LensArn": str,
-        "LensVersion": str,
-        "LensName": str,
-        "LensStatus": LensStatusType,
-        "UpdatedAt": datetime,
-        "RiskCounts": Dict[RiskType, int],
+        "Status": ImportLensStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+WorkloadProfileTypeDef = TypedDict(
+    "WorkloadProfileTypeDef",
+    {
+        "ProfileArn": str,
+        "ProfileVersion": str,
     },
     total=False,
 )
 
 PillarReviewSummaryTypeDef = TypedDict(
     "PillarReviewSummaryTypeDef",
     {
         "PillarId": str,
         "PillarName": str,
         "Notes": str,
         "RiskCounts": Dict[RiskType, int],
+        "PrioritizedRiskCounts": Dict[RiskType, int],
     },
     total=False,
 )
 
 LensShareSummaryTypeDef = TypedDict(
     "LensShareSummaryTypeDef",
     {
@@ -650,14 +872,15 @@
 _OptionalListAnswersInputRequestTypeDef = TypedDict(
     "_OptionalListAnswersInputRequestTypeDef",
     {
         "PillarId": str,
         "MilestoneNumber": int,
         "NextToken": str,
         "MaxResults": int,
+        "QuestionPriority": QuestionPriorityType,
     },
     total=False,
 )
 
 
 class ListAnswersInputRequestTypeDef(
     _RequiredListAnswersInputRequestTypeDef, _OptionalListAnswersInputRequestTypeDef
@@ -727,14 +950,15 @@
 _OptionalListLensReviewImprovementsInputRequestTypeDef = TypedDict(
     "_OptionalListLensReviewImprovementsInputRequestTypeDef",
     {
         "PillarId": str,
         "MilestoneNumber": int,
         "NextToken": str,
         "MaxResults": int,
+        "QuestionPriority": QuestionPriorityType,
     },
     total=False,
 )
 
 
 class ListLensReviewImprovementsInputRequestTypeDef(
     _RequiredListLensReviewImprovementsInputRequestTypeDef,
@@ -830,22 +1054,107 @@
         "WorkloadId": str,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListProfileNotificationsInputRequestTypeDef = TypedDict(
+    "ListProfileNotificationsInputRequestTypeDef",
+    {
+        "WorkloadId": str,
+        "NextToken": str,
+        "MaxResults": int,
+    },
+    total=False,
+)
+
+ProfileNotificationSummaryTypeDef = TypedDict(
+    "ProfileNotificationSummaryTypeDef",
+    {
+        "CurrentProfileVersion": str,
+        "LatestProfileVersion": str,
+        "Type": ProfileNotificationTypeType,
+        "ProfileArn": str,
+        "ProfileName": str,
+        "WorkloadId": str,
+        "WorkloadName": str,
+    },
+    total=False,
+)
+
+_RequiredListProfileSharesInputRequestTypeDef = TypedDict(
+    "_RequiredListProfileSharesInputRequestTypeDef",
+    {
+        "ProfileArn": str,
+    },
+)
+_OptionalListProfileSharesInputRequestTypeDef = TypedDict(
+    "_OptionalListProfileSharesInputRequestTypeDef",
+    {
+        "SharedWithPrefix": str,
+        "NextToken": str,
+        "MaxResults": int,
+        "Status": ShareStatusType,
+    },
+    total=False,
+)
+
+
+class ListProfileSharesInputRequestTypeDef(
+    _RequiredListProfileSharesInputRequestTypeDef, _OptionalListProfileSharesInputRequestTypeDef
+):
+    pass
+
+
+ProfileShareSummaryTypeDef = TypedDict(
+    "ProfileShareSummaryTypeDef",
+    {
+        "ShareId": str,
+        "SharedWith": str,
+        "Status": ShareStatusType,
+        "StatusMessage": str,
+    },
+    total=False,
+)
+
+ListProfilesInputRequestTypeDef = TypedDict(
+    "ListProfilesInputRequestTypeDef",
+    {
+        "ProfileNamePrefix": str,
+        "ProfileOwnerType": ProfileOwnerTypeType,
+        "NextToken": str,
+        "MaxResults": int,
+    },
+    total=False,
+)
+
+ProfileSummaryTypeDef = TypedDict(
+    "ProfileSummaryTypeDef",
+    {
+        "ProfileArn": str,
+        "ProfileVersion": str,
+        "ProfileName": str,
+        "ProfileDescription": str,
+        "Owner": str,
+        "CreatedAt": datetime,
+        "UpdatedAt": datetime,
+    },
+    total=False,
+)
+
 ListShareInvitationsInputRequestTypeDef = TypedDict(
     "ListShareInvitationsInputRequestTypeDef",
     {
         "WorkloadNamePrefix": str,
         "LensNamePrefix": str,
         "ShareResourceType": ShareResourceTypeType,
         "NextToken": str,
         "MaxResults": int,
+        "ProfileNamePrefix": str,
     },
     total=False,
 )
 
 ShareInvitationSummaryTypeDef = TypedDict(
     "ShareInvitationSummaryTypeDef",
     {
@@ -854,25 +1163,35 @@
         "SharedWith": str,
         "PermissionType": PermissionTypeType,
         "ShareResourceType": ShareResourceTypeType,
         "WorkloadName": str,
         "WorkloadId": str,
         "LensName": str,
         "LensArn": str,
+        "ProfileName": str,
+        "ProfileArn": str,
     },
     total=False,
 )
 
 ListTagsForResourceInputRequestTypeDef = TypedDict(
     "ListTagsForResourceInputRequestTypeDef",
     {
         "WorkloadArn": str,
     },
 )
 
+ListTagsForResourceOutputTypeDef = TypedDict(
+    "ListTagsForResourceOutputTypeDef",
+    {
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredListWorkloadSharesInputRequestTypeDef = TypedDict(
     "_RequiredListWorkloadSharesInputRequestTypeDef",
     {
         "WorkloadId": str,
     },
 )
 _OptionalListWorkloadSharesInputRequestTypeDef = TypedDict(
@@ -911,47 +1230,64 @@
         "WorkloadNamePrefix": str,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-WorkloadSummaryTypeDef = TypedDict(
-    "WorkloadSummaryTypeDef",
-    {
-        "WorkloadId": str,
-        "WorkloadArn": str,
-        "WorkloadName": str,
-        "Owner": str,
-        "UpdatedAt": datetime,
-        "Lenses": List[str],
-        "RiskCounts": Dict[RiskType, int],
-        "ImprovementStatus": WorkloadImprovementStatusType,
-    },
-    total=False,
-)
-
 QuestionDifferenceTypeDef = TypedDict(
     "QuestionDifferenceTypeDef",
     {
         "QuestionId": str,
         "QuestionTitle": str,
         "DifferenceStatus": DifferenceStatusType,
     },
     total=False,
 )
 
+ProfileChoiceTypeDef = TypedDict(
+    "ProfileChoiceTypeDef",
+    {
+        "ChoiceId": str,
+        "ChoiceTitle": str,
+        "ChoiceDescription": str,
+    },
+    total=False,
+)
+
+ProfileTemplateChoiceTypeDef = TypedDict(
+    "ProfileTemplateChoiceTypeDef",
+    {
+        "ChoiceId": str,
+        "ChoiceTitle": str,
+        "ChoiceDescription": str,
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
 ShareInvitationTypeDef = TypedDict(
     "ShareInvitationTypeDef",
     {
         "ShareInvitationId": str,
         "ShareResourceType": ShareResourceTypeType,
         "WorkloadId": str,
         "LensAlias": str,
         "LensArn": str,
+        "ProfileArn": str,
     },
     total=False,
 )
 
 TagResourceInputRequestTypeDef = TypedDict(
     "TagResourceInputRequestTypeDef",
     {
@@ -968,14 +1304,15 @@
     },
 )
 
 UpdateGlobalSettingsInputRequestTypeDef = TypedDict(
     "UpdateGlobalSettingsInputRequestTypeDef",
     {
         "OrganizationSharingStatus": OrganizationSharingStatusType,
+        "DiscoveryIntegrationStatus": DiscoveryIntegrationStatusType,
     },
     total=False,
 )
 
 _RequiredUpdateLensReviewInputRequestTypeDef = TypedDict(
     "_RequiredUpdateLensReviewInputRequestTypeDef",
     {
@@ -1049,23 +1386,75 @@
 
 class UpgradeLensReviewInputRequestTypeDef(
     _RequiredUpgradeLensReviewInputRequestTypeDef, _OptionalUpgradeLensReviewInputRequestTypeDef
 ):
     pass
 
 
+_RequiredUpgradeProfileVersionInputRequestTypeDef = TypedDict(
+    "_RequiredUpgradeProfileVersionInputRequestTypeDef",
+    {
+        "WorkloadId": str,
+        "ProfileArn": str,
+    },
+)
+_OptionalUpgradeProfileVersionInputRequestTypeDef = TypedDict(
+    "_OptionalUpgradeProfileVersionInputRequestTypeDef",
+    {
+        "MilestoneName": str,
+        "ClientRequestToken": str,
+    },
+    total=False,
+)
+
+
+class UpgradeProfileVersionInputRequestTypeDef(
+    _RequiredUpgradeProfileVersionInputRequestTypeDef,
+    _OptionalUpgradeProfileVersionInputRequestTypeDef,
+):
+    pass
+
+
 AdditionalResourcesTypeDef = TypedDict(
     "AdditionalResourcesTypeDef",
     {
         "Type": AdditionalResourceTypeType,
         "Content": List[ChoiceContentTypeDef],
     },
     total=False,
 )
 
+QuestionMetricTypeDef = TypedDict(
+    "QuestionMetricTypeDef",
+    {
+        "QuestionId": str,
+        "Risk": RiskType,
+        "BestPractices": List[BestPracticeTypeDef],
+    },
+    total=False,
+)
+
+ListCheckDetailsOutputTypeDef = TypedDict(
+    "ListCheckDetailsOutputTypeDef",
+    {
+        "CheckDetails": List[CheckDetailTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListCheckSummariesOutputTypeDef = TypedDict(
+    "ListCheckSummariesOutputTypeDef",
+    {
+        "CheckSummaries": List[CheckSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ImprovementSummaryTypeDef = TypedDict(
     "ImprovementSummaryTypeDef",
     {
         "QuestionId": str,
         "PillarId": str,
         "QuestionTitle": str,
         "Risk": RiskType,
@@ -1098,107 +1487,59 @@
 
 class UpdateAnswerInputRequestTypeDef(
     _RequiredUpdateAnswerInputRequestTypeDef, _OptionalUpdateAnswerInputRequestTypeDef
 ):
     pass
 
 
-CreateLensShareOutputTypeDef = TypedDict(
-    "CreateLensShareOutputTypeDef",
+_RequiredCreateProfileInputRequestTypeDef = TypedDict(
+    "_RequiredCreateProfileInputRequestTypeDef",
     {
-        "ShareId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ProfileName": str,
+        "ProfileDescription": str,
+        "ProfileQuestions": Sequence[ProfileQuestionUpdateTypeDef],
+        "ClientRequestToken": str,
     },
 )
-
-CreateLensVersionOutputTypeDef = TypedDict(
-    "CreateLensVersionOutputTypeDef",
+_OptionalCreateProfileInputRequestTypeDef = TypedDict(
+    "_OptionalCreateProfileInputRequestTypeDef",
     {
-        "LensArn": str,
-        "LensVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Tags": Mapping[str, str],
     },
+    total=False,
 )
 
-CreateMilestoneOutputTypeDef = TypedDict(
-    "CreateMilestoneOutputTypeDef",
-    {
-        "WorkloadId": str,
-        "MilestoneNumber": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-CreateWorkloadOutputTypeDef = TypedDict(
-    "CreateWorkloadOutputTypeDef",
-    {
-        "WorkloadId": str,
-        "WorkloadArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateWorkloadShareOutputTypeDef = TypedDict(
-    "CreateWorkloadShareOutputTypeDef",
-    {
-        "WorkloadId": str,
-        "ShareId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class CreateProfileInputRequestTypeDef(
+    _RequiredCreateProfileInputRequestTypeDef, _OptionalCreateProfileInputRequestTypeDef
+):
+    pass
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-ExportLensOutputTypeDef = TypedDict(
-    "ExportLensOutputTypeDef",
+_RequiredUpdateProfileInputRequestTypeDef = TypedDict(
+    "_RequiredUpdateProfileInputRequestTypeDef",
     {
-        "LensJSON": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ProfileArn": str,
     },
 )
-
-ImportLensOutputTypeDef = TypedDict(
-    "ImportLensOutputTypeDef",
+_OptionalUpdateProfileInputRequestTypeDef = TypedDict(
+    "_OptionalUpdateProfileInputRequestTypeDef",
     {
-        "LensArn": str,
-        "Status": ImportLensStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ProfileDescription": str,
+        "ProfileQuestions": Sequence[ProfileQuestionUpdateTypeDef],
     },
+    total=False,
 )
 
-ListCheckDetailsOutputTypeDef = TypedDict(
-    "ListCheckDetailsOutputTypeDef",
-    {
-        "CheckDetails": List[CheckDetailTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-ListCheckSummariesOutputTypeDef = TypedDict(
-    "ListCheckSummariesOutputTypeDef",
-    {
-        "CheckSummaries": List[CheckSummaryTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class UpdateProfileInputRequestTypeDef(
+    _RequiredUpdateProfileInputRequestTypeDef, _OptionalUpdateProfileInputRequestTypeDef
+):
+    pass
 
-ListTagsForResourceOutputTypeDef = TypedDict(
-    "ListTagsForResourceOutputTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
 _RequiredCreateWorkloadInputRequestTypeDef = TypedDict(
     "_RequiredCreateWorkloadInputRequestTypeDef",
     {
         "WorkloadName": str,
         "Description": str,
         "Environment": WorkloadEnvironmentType,
@@ -1217,14 +1558,15 @@
         "ReviewOwner": str,
         "IndustryType": str,
         "Industry": str,
         "Notes": str,
         "Tags": Mapping[str, str],
         "DiscoveryConfig": WorkloadDiscoveryConfigTypeDef,
         "Applications": Sequence[str],
+        "ProfileArns": Sequence[str],
     },
     total=False,
 )
 
 
 class CreateWorkloadInputRequestTypeDef(
     _RequiredCreateWorkloadInputRequestTypeDef, _OptionalCreateWorkloadInputRequestTypeDef
@@ -1264,14 +1606,65 @@
 
 class UpdateWorkloadInputRequestTypeDef(
     _RequiredUpdateWorkloadInputRequestTypeDef, _OptionalUpdateWorkloadInputRequestTypeDef
 ):
     pass
 
 
+GetLensOutputTypeDef = TypedDict(
+    "GetLensOutputTypeDef",
+    {
+        "Lens": LensTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetLensReviewReportOutputTypeDef = TypedDict(
+    "GetLensReviewReportOutputTypeDef",
+    {
+        "WorkloadId": str,
+        "MilestoneNumber": int,
+        "LensReviewReport": LensReviewReportTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+LensReviewSummaryTypeDef = TypedDict(
+    "LensReviewSummaryTypeDef",
+    {
+        "LensAlias": str,
+        "LensArn": str,
+        "LensVersion": str,
+        "LensName": str,
+        "LensStatus": LensStatusType,
+        "UpdatedAt": datetime,
+        "RiskCounts": Dict[RiskType, int],
+        "Profiles": List[WorkloadProfileTypeDef],
+        "PrioritizedRiskCounts": Dict[RiskType, int],
+    },
+    total=False,
+)
+
+WorkloadSummaryTypeDef = TypedDict(
+    "WorkloadSummaryTypeDef",
+    {
+        "WorkloadId": str,
+        "WorkloadArn": str,
+        "WorkloadName": str,
+        "Owner": str,
+        "UpdatedAt": datetime,
+        "Lenses": List[str],
+        "RiskCounts": Dict[RiskType, int],
+        "ImprovementStatus": WorkloadImprovementStatusType,
+        "Profiles": List[WorkloadProfileTypeDef],
+        "PrioritizedRiskCounts": Dict[RiskType, int],
+    },
+    total=False,
+)
+
 WorkloadTypeDef = TypedDict(
     "WorkloadTypeDef",
     {
         "WorkloadId": str,
         "WorkloadArn": str,
         "WorkloadName": str,
         "Description": str,
@@ -1292,155 +1685,164 @@
         "PillarPriorities": List[str],
         "Lenses": List[str],
         "Owner": str,
         "ShareInvitationId": str,
         "Tags": Dict[str, str],
         "DiscoveryConfig": WorkloadDiscoveryConfigTypeDef,
         "Applications": List[str],
+        "Profiles": List[WorkloadProfileTypeDef],
+        "PrioritizedRiskCounts": Dict[RiskType, int],
     },
     total=False,
 )
 
-GetLensOutputTypeDef = TypedDict(
-    "GetLensOutputTypeDef",
-    {
-        "Lens": LensTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetLensReviewReportOutputTypeDef = TypedDict(
-    "GetLensReviewReportOutputTypeDef",
-    {
-        "WorkloadId": str,
-        "MilestoneNumber": int,
-        "LensReviewReport": LensReviewReportTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListLensReviewsOutputTypeDef = TypedDict(
-    "ListLensReviewsOutputTypeDef",
-    {
-        "WorkloadId": str,
-        "MilestoneNumber": int,
-        "LensReviewSummaries": List[LensReviewSummaryTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 LensReviewTypeDef = TypedDict(
     "LensReviewTypeDef",
     {
         "LensAlias": str,
         "LensArn": str,
         "LensVersion": str,
         "LensName": str,
         "LensStatus": LensStatusType,
         "PillarReviewSummaries": List[PillarReviewSummaryTypeDef],
         "UpdatedAt": datetime,
         "Notes": str,
         "RiskCounts": Dict[RiskType, int],
         "NextToken": str,
+        "Profiles": List[WorkloadProfileTypeDef],
+        "PrioritizedRiskCounts": Dict[RiskType, int],
     },
     total=False,
 )
 
 ListLensSharesOutputTypeDef = TypedDict(
     "ListLensSharesOutputTypeDef",
     {
         "LensShareSummaries": List[LensShareSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListLensesOutputTypeDef = TypedDict(
     "ListLensesOutputTypeDef",
     {
         "LensSummaries": List[LensSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 NotificationSummaryTypeDef = TypedDict(
     "NotificationSummaryTypeDef",
     {
         "Type": NotificationTypeType,
         "LensUpgradeSummary": LensUpgradeSummaryTypeDef,
     },
     total=False,
 )
 
+ListProfileNotificationsOutputTypeDef = TypedDict(
+    "ListProfileNotificationsOutputTypeDef",
+    {
+        "NotificationSummaries": List[ProfileNotificationSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListProfileSharesOutputTypeDef = TypedDict(
+    "ListProfileSharesOutputTypeDef",
+    {
+        "ProfileShareSummaries": List[ProfileShareSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListProfilesOutputTypeDef = TypedDict(
+    "ListProfilesOutputTypeDef",
+    {
+        "ProfileSummaries": List[ProfileSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListShareInvitationsOutputTypeDef = TypedDict(
     "ListShareInvitationsOutputTypeDef",
     {
         "ShareInvitationSummaries": List[ShareInvitationSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListWorkloadSharesOutputTypeDef = TypedDict(
     "ListWorkloadSharesOutputTypeDef",
     {
         "WorkloadId": str,
         "WorkloadShareSummaries": List[WorkloadShareSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListWorkloadsOutputTypeDef = TypedDict(
-    "ListWorkloadsOutputTypeDef",
+PillarDifferenceTypeDef = TypedDict(
+    "PillarDifferenceTypeDef",
     {
-        "WorkloadSummaries": List[WorkloadSummaryTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "PillarId": str,
+        "PillarName": str,
+        "DifferenceStatus": DifferenceStatusType,
+        "QuestionDifferences": List[QuestionDifferenceTypeDef],
     },
+    total=False,
 )
 
-MilestoneSummaryTypeDef = TypedDict(
-    "MilestoneSummaryTypeDef",
+ProfileQuestionTypeDef = TypedDict(
+    "ProfileQuestionTypeDef",
     {
-        "MilestoneNumber": int,
-        "MilestoneName": str,
-        "RecordedAt": datetime,
-        "WorkloadSummary": WorkloadSummaryTypeDef,
+        "QuestionId": str,
+        "QuestionTitle": str,
+        "QuestionDescription": str,
+        "QuestionChoices": List[ProfileChoiceTypeDef],
+        "SelectedChoiceIds": List[str],
+        "MinSelectedChoices": int,
+        "MaxSelectedChoices": int,
     },
     total=False,
 )
 
-PillarDifferenceTypeDef = TypedDict(
-    "PillarDifferenceTypeDef",
+ProfileTemplateQuestionTypeDef = TypedDict(
+    "ProfileTemplateQuestionTypeDef",
     {
-        "PillarId": str,
-        "PillarName": str,
-        "DifferenceStatus": DifferenceStatusType,
-        "QuestionDifferences": List[QuestionDifferenceTypeDef],
+        "QuestionId": str,
+        "QuestionTitle": str,
+        "QuestionDescription": str,
+        "QuestionChoices": List[ProfileTemplateChoiceTypeDef],
+        "MinSelectedChoices": int,
+        "MaxSelectedChoices": int,
     },
     total=False,
 )
 
 UpdateShareInvitationOutputTypeDef = TypedDict(
     "UpdateShareInvitationOutputTypeDef",
     {
         "ShareInvitation": ShareInvitationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateWorkloadShareOutputTypeDef = TypedDict(
     "UpdateWorkloadShareOutputTypeDef",
     {
         "WorkloadId": str,
         "WorkloadShare": WorkloadShareTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ChoiceTypeDef = TypedDict(
     "ChoiceTypeDef",
     {
         "ChoiceId": str,
@@ -1449,32 +1851,73 @@
         "HelpfulResource": ChoiceContentTypeDef,
         "ImprovementPlan": ChoiceContentTypeDef,
         "AdditionalResources": List[AdditionalResourcesTypeDef],
     },
     total=False,
 )
 
+PillarMetricTypeDef = TypedDict(
+    "PillarMetricTypeDef",
+    {
+        "PillarId": str,
+        "RiskCounts": Dict[RiskType, int],
+        "Questions": List[QuestionMetricTypeDef],
+    },
+    total=False,
+)
+
 ListLensReviewImprovementsOutputTypeDef = TypedDict(
     "ListLensReviewImprovementsOutputTypeDef",
     {
         "WorkloadId": str,
         "MilestoneNumber": int,
         "LensAlias": str,
         "LensArn": str,
         "ImprovementSummaries": List[ImprovementSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListLensReviewsOutputTypeDef = TypedDict(
+    "ListLensReviewsOutputTypeDef",
+    {
+        "WorkloadId": str,
+        "MilestoneNumber": int,
+        "LensReviewSummaries": List[LensReviewSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
+ListWorkloadsOutputTypeDef = TypedDict(
+    "ListWorkloadsOutputTypeDef",
+    {
+        "WorkloadSummaries": List[WorkloadSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+MilestoneSummaryTypeDef = TypedDict(
+    "MilestoneSummaryTypeDef",
+    {
+        "MilestoneNumber": int,
+        "MilestoneName": str,
+        "RecordedAt": datetime,
+        "WorkloadSummary": WorkloadSummaryTypeDef,
+    },
+    total=False,
+)
+
 GetWorkloadOutputTypeDef = TypedDict(
     "GetWorkloadOutputTypeDef",
     {
         "Workload": WorkloadTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 MilestoneTypeDef = TypedDict(
     "MilestoneTypeDef",
     {
         "MilestoneNumber": int,
@@ -1485,60 +1928,78 @@
     total=False,
 )
 
 UpdateWorkloadOutputTypeDef = TypedDict(
     "UpdateWorkloadOutputTypeDef",
     {
         "Workload": WorkloadTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetLensReviewOutputTypeDef = TypedDict(
     "GetLensReviewOutputTypeDef",
     {
         "WorkloadId": str,
         "MilestoneNumber": int,
         "LensReview": LensReviewTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateLensReviewOutputTypeDef = TypedDict(
     "UpdateLensReviewOutputTypeDef",
     {
         "WorkloadId": str,
         "LensReview": LensReviewTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListNotificationsOutputTypeDef = TypedDict(
     "ListNotificationsOutputTypeDef",
     {
         "NotificationSummaries": List[NotificationSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListMilestonesOutputTypeDef = TypedDict(
-    "ListMilestonesOutputTypeDef",
+VersionDifferencesTypeDef = TypedDict(
+    "VersionDifferencesTypeDef",
     {
-        "WorkloadId": str,
-        "MilestoneSummaries": List[MilestoneSummaryTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "PillarDifferences": List[PillarDifferenceTypeDef],
     },
+    total=False,
 )
 
-VersionDifferencesTypeDef = TypedDict(
-    "VersionDifferencesTypeDef",
+ProfileTypeDef = TypedDict(
+    "ProfileTypeDef",
     {
-        "PillarDifferences": List[PillarDifferenceTypeDef],
+        "ProfileArn": str,
+        "ProfileVersion": str,
+        "ProfileName": str,
+        "ProfileDescription": str,
+        "ProfileQuestions": List[ProfileQuestionTypeDef],
+        "Owner": str,
+        "CreatedAt": datetime,
+        "UpdatedAt": datetime,
+        "ShareInvitationId": str,
+        "Tags": Dict[str, str],
+    },
+    total=False,
+)
+
+ProfileTemplateTypeDef = TypedDict(
+    "ProfileTemplateTypeDef",
+    {
+        "TemplateName": str,
+        "TemplateQuestions": List[ProfileTemplateQuestionTypeDef],
+        "CreatedAt": datetime,
+        "UpdatedAt": datetime,
     },
     total=False,
 )
 
 AnswerSummaryTypeDef = TypedDict(
     "AnswerSummaryTypeDef",
     {
@@ -1547,14 +2008,15 @@
         "QuestionTitle": str,
         "Choices": List[ChoiceTypeDef],
         "SelectedChoices": List[str],
         "ChoiceAnswerSummaries": List[ChoiceAnswerSummaryTypeDef],
         "IsApplicable": bool,
         "Risk": RiskType,
         "Reason": AnswerReasonType,
+        "QuestionType": QuestionTypeType,
     },
     total=False,
 )
 
 AnswerTypeDef = TypedDict(
     "AnswerTypeDef",
     {
@@ -1572,64 +2034,133 @@
         "Risk": RiskType,
         "Notes": str,
         "Reason": AnswerReasonType,
     },
     total=False,
 )
 
+LensMetricTypeDef = TypedDict(
+    "LensMetricTypeDef",
+    {
+        "LensArn": str,
+        "Pillars": List[PillarMetricTypeDef],
+        "RiskCounts": Dict[RiskType, int],
+    },
+    total=False,
+)
+
+ListMilestonesOutputTypeDef = TypedDict(
+    "ListMilestonesOutputTypeDef",
+    {
+        "WorkloadId": str,
+        "MilestoneSummaries": List[MilestoneSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetMilestoneOutputTypeDef = TypedDict(
     "GetMilestoneOutputTypeDef",
     {
         "WorkloadId": str,
         "Milestone": MilestoneTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetLensVersionDifferenceOutputTypeDef = TypedDict(
     "GetLensVersionDifferenceOutputTypeDef",
     {
         "LensAlias": str,
         "LensArn": str,
         "BaseLensVersion": str,
         "TargetLensVersion": str,
         "LatestLensVersion": str,
         "VersionDifferences": VersionDifferencesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetProfileOutputTypeDef = TypedDict(
+    "GetProfileOutputTypeDef",
+    {
+        "Profile": ProfileTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateProfileOutputTypeDef = TypedDict(
+    "UpdateProfileOutputTypeDef",
+    {
+        "Profile": ProfileTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetProfileTemplateOutputTypeDef = TypedDict(
+    "GetProfileTemplateOutputTypeDef",
+    {
+        "ProfileTemplate": ProfileTemplateTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAnswersOutputTypeDef = TypedDict(
     "ListAnswersOutputTypeDef",
     {
         "WorkloadId": str,
         "MilestoneNumber": int,
         "LensAlias": str,
         "LensArn": str,
         "AnswerSummaries": List[AnswerSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAnswerOutputTypeDef = TypedDict(
     "GetAnswerOutputTypeDef",
     {
         "WorkloadId": str,
         "MilestoneNumber": int,
         "LensAlias": str,
         "LensArn": str,
         "Answer": AnswerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAnswerOutputTypeDef = TypedDict(
     "UpdateAnswerOutputTypeDef",
     {
         "WorkloadId": str,
         "LensAlias": str,
         "LensArn": str,
         "Answer": AnswerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ConsolidatedReportMetricTypeDef = TypedDict(
+    "ConsolidatedReportMetricTypeDef",
+    {
+        "MetricType": Literal["WORKLOAD"],
+        "RiskCounts": Dict[RiskType, int],
+        "WorkloadId": str,
+        "WorkloadName": str,
+        "WorkloadArn": str,
+        "UpdatedAt": datetime,
+        "Lenses": List[LensMetricTypeDef],
+        "LensesAppliedCount": int,
+    },
+    total=False,
+)
+
+GetConsolidatedReportOutputTypeDef = TypedDict(
+    "GetConsolidatedReportOutputTypeDef",
+    {
+        "Metrics": List[ConsolidatedReportMetricTypeDef],
+        "NextToken": str,
+        "Base64String": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-wellarchitected-2.5.0.post1/types_aiobotocore_wellarchitected/type_defs.pyi` & `types-aiobotocore-wellarchitected-2.5.1/types_aiobotocore_wellarchitected/type_defs.pyi`

 * *Files 22% similar despite different names*

```diff
@@ -18,22 +18,29 @@
 from .literals import (
     AdditionalResourceTypeType,
     AnswerReasonType,
     CheckFailureReasonType,
     CheckStatusType,
     ChoiceReasonType,
     ChoiceStatusType,
+    DefinitionTypeType,
     DifferenceStatusType,
+    DiscoveryIntegrationStatusType,
     ImportLensStatusType,
     LensStatusType,
     LensStatusTypeType,
     LensTypeType,
     NotificationTypeType,
     OrganizationSharingStatusType,
     PermissionTypeType,
+    ProfileNotificationTypeType,
+    ProfileOwnerTypeType,
+    QuestionPriorityType,
+    QuestionTypeType,
+    ReportFormatType,
     RiskType,
     ShareInvitationActionType,
     ShareResourceTypeType,
     ShareStatusType,
     TrustedAdvisorIntegrationStatusType,
     WorkloadEnvironmentType,
     WorkloadImprovementStatusType,
@@ -49,119 +56,157 @@
     from typing_extensions import TypedDict
 
 __all__ = (
     "ChoiceContentTypeDef",
     "ChoiceAnswerSummaryTypeDef",
     "ChoiceAnswerTypeDef",
     "AssociateLensesInputRequestTypeDef",
+    "AssociateProfilesInputRequestTypeDef",
+    "BestPracticeTypeDef",
     "CheckDetailTypeDef",
     "CheckSummaryTypeDef",
     "ChoiceImprovementPlanTypeDef",
     "ChoiceUpdateTypeDef",
     "CreateLensShareInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateLensShareOutputTypeDef",
     "CreateLensVersionInputRequestTypeDef",
+    "CreateLensVersionOutputTypeDef",
     "CreateMilestoneInputRequestTypeDef",
+    "CreateMilestoneOutputTypeDef",
+    "ProfileQuestionUpdateTypeDef",
+    "CreateProfileOutputTypeDef",
+    "CreateProfileShareInputRequestTypeDef",
+    "CreateProfileShareOutputTypeDef",
     "WorkloadDiscoveryConfigTypeDef",
+    "CreateWorkloadOutputTypeDef",
     "CreateWorkloadShareInputRequestTypeDef",
+    "CreateWorkloadShareOutputTypeDef",
     "DeleteLensInputRequestTypeDef",
     "DeleteLensShareInputRequestTypeDef",
+    "DeleteProfileInputRequestTypeDef",
+    "DeleteProfileShareInputRequestTypeDef",
     "DeleteWorkloadInputRequestTypeDef",
     "DeleteWorkloadShareInputRequestTypeDef",
     "DisassociateLensesInputRequestTypeDef",
+    "DisassociateProfilesInputRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "ExportLensInputRequestTypeDef",
+    "ExportLensOutputTypeDef",
     "GetAnswerInputRequestTypeDef",
+    "GetConsolidatedReportInputRequestTypeDef",
     "GetLensInputRequestTypeDef",
     "LensTypeDef",
     "GetLensReviewInputRequestTypeDef",
     "GetLensReviewReportInputRequestTypeDef",
     "LensReviewReportTypeDef",
     "GetLensVersionDifferenceInputRequestTypeDef",
     "GetMilestoneInputRequestTypeDef",
+    "GetProfileInputRequestTypeDef",
     "GetWorkloadInputRequestTypeDef",
     "ImportLensInputRequestTypeDef",
-    "LensReviewSummaryTypeDef",
+    "ImportLensOutputTypeDef",
+    "WorkloadProfileTypeDef",
     "PillarReviewSummaryTypeDef",
     "LensShareSummaryTypeDef",
     "LensSummaryTypeDef",
     "LensUpgradeSummaryTypeDef",
     "ListAnswersInputRequestTypeDef",
     "ListCheckDetailsInputRequestTypeDef",
     "ListCheckSummariesInputRequestTypeDef",
     "ListLensReviewImprovementsInputRequestTypeDef",
     "ListLensReviewsInputRequestTypeDef",
     "ListLensSharesInputRequestTypeDef",
     "ListLensesInputRequestTypeDef",
     "ListMilestonesInputRequestTypeDef",
     "ListNotificationsInputRequestTypeDef",
+    "ListProfileNotificationsInputRequestTypeDef",
+    "ProfileNotificationSummaryTypeDef",
+    "ListProfileSharesInputRequestTypeDef",
+    "ProfileShareSummaryTypeDef",
+    "ListProfilesInputRequestTypeDef",
+    "ProfileSummaryTypeDef",
     "ListShareInvitationsInputRequestTypeDef",
     "ShareInvitationSummaryTypeDef",
     "ListTagsForResourceInputRequestTypeDef",
+    "ListTagsForResourceOutputTypeDef",
     "ListWorkloadSharesInputRequestTypeDef",
     "WorkloadShareSummaryTypeDef",
     "ListWorkloadsInputRequestTypeDef",
-    "WorkloadSummaryTypeDef",
     "QuestionDifferenceTypeDef",
+    "ProfileChoiceTypeDef",
+    "ProfileTemplateChoiceTypeDef",
+    "ResponseMetadataTypeDef",
     "ShareInvitationTypeDef",
     "TagResourceInputRequestTypeDef",
     "UntagResourceInputRequestTypeDef",
     "UpdateGlobalSettingsInputRequestTypeDef",
     "UpdateLensReviewInputRequestTypeDef",
     "UpdateShareInvitationInputRequestTypeDef",
     "UpdateWorkloadShareInputRequestTypeDef",
     "WorkloadShareTypeDef",
     "UpgradeLensReviewInputRequestTypeDef",
+    "UpgradeProfileVersionInputRequestTypeDef",
     "AdditionalResourcesTypeDef",
-    "ImprovementSummaryTypeDef",
-    "UpdateAnswerInputRequestTypeDef",
-    "CreateLensShareOutputTypeDef",
-    "CreateLensVersionOutputTypeDef",
-    "CreateMilestoneOutputTypeDef",
-    "CreateWorkloadOutputTypeDef",
-    "CreateWorkloadShareOutputTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ExportLensOutputTypeDef",
-    "ImportLensOutputTypeDef",
+    "QuestionMetricTypeDef",
     "ListCheckDetailsOutputTypeDef",
     "ListCheckSummariesOutputTypeDef",
-    "ListTagsForResourceOutputTypeDef",
+    "ImprovementSummaryTypeDef",
+    "UpdateAnswerInputRequestTypeDef",
+    "CreateProfileInputRequestTypeDef",
+    "UpdateProfileInputRequestTypeDef",
     "CreateWorkloadInputRequestTypeDef",
     "UpdateWorkloadInputRequestTypeDef",
-    "WorkloadTypeDef",
     "GetLensOutputTypeDef",
     "GetLensReviewReportOutputTypeDef",
-    "ListLensReviewsOutputTypeDef",
+    "LensReviewSummaryTypeDef",
+    "WorkloadSummaryTypeDef",
+    "WorkloadTypeDef",
     "LensReviewTypeDef",
     "ListLensSharesOutputTypeDef",
     "ListLensesOutputTypeDef",
     "NotificationSummaryTypeDef",
+    "ListProfileNotificationsOutputTypeDef",
+    "ListProfileSharesOutputTypeDef",
+    "ListProfilesOutputTypeDef",
     "ListShareInvitationsOutputTypeDef",
     "ListWorkloadSharesOutputTypeDef",
-    "ListWorkloadsOutputTypeDef",
-    "MilestoneSummaryTypeDef",
     "PillarDifferenceTypeDef",
+    "ProfileQuestionTypeDef",
+    "ProfileTemplateQuestionTypeDef",
     "UpdateShareInvitationOutputTypeDef",
     "UpdateWorkloadShareOutputTypeDef",
     "ChoiceTypeDef",
+    "PillarMetricTypeDef",
     "ListLensReviewImprovementsOutputTypeDef",
+    "ListLensReviewsOutputTypeDef",
+    "ListWorkloadsOutputTypeDef",
+    "MilestoneSummaryTypeDef",
     "GetWorkloadOutputTypeDef",
     "MilestoneTypeDef",
     "UpdateWorkloadOutputTypeDef",
     "GetLensReviewOutputTypeDef",
     "UpdateLensReviewOutputTypeDef",
     "ListNotificationsOutputTypeDef",
-    "ListMilestonesOutputTypeDef",
     "VersionDifferencesTypeDef",
+    "ProfileTypeDef",
+    "ProfileTemplateTypeDef",
     "AnswerSummaryTypeDef",
     "AnswerTypeDef",
+    "LensMetricTypeDef",
+    "ListMilestonesOutputTypeDef",
     "GetMilestoneOutputTypeDef",
     "GetLensVersionDifferenceOutputTypeDef",
+    "GetProfileOutputTypeDef",
+    "UpdateProfileOutputTypeDef",
+    "GetProfileTemplateOutputTypeDef",
     "ListAnswersOutputTypeDef",
     "GetAnswerOutputTypeDef",
     "UpdateAnswerOutputTypeDef",
+    "ConsolidatedReportMetricTypeDef",
+    "GetConsolidatedReportOutputTypeDef",
 )
 
 ChoiceContentTypeDef = TypedDict(
     "ChoiceContentTypeDef",
     {
         "DisplayText": str,
         "Url": str,
@@ -194,14 +239,31 @@
     "AssociateLensesInputRequestTypeDef",
     {
         "WorkloadId": str,
         "LensAliases": Sequence[str],
     },
 )
 
+AssociateProfilesInputRequestTypeDef = TypedDict(
+    "AssociateProfilesInputRequestTypeDef",
+    {
+        "WorkloadId": str,
+        "ProfileArns": Sequence[str],
+    },
+)
+
+BestPracticeTypeDef = TypedDict(
+    "BestPracticeTypeDef",
+    {
+        "ChoiceId": str,
+        "ChoiceTitle": str,
+    },
+    total=False,
+)
+
 CheckDetailTypeDef = TypedDict(
     "CheckDetailTypeDef",
     {
         "Id": str,
         "Name": str,
         "Description": str,
         "Provider": Literal["TRUSTED_ADVISOR"],
@@ -269,22 +331,19 @@
     {
         "LensAlias": str,
         "SharedWith": str,
         "ClientRequestToken": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateLensShareOutputTypeDef = TypedDict(
+    "CreateLensShareOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ShareId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateLensVersionInputRequestTypeDef = TypedDict(
     "_RequiredCreateLensVersionInputRequestTypeDef",
     {
         "LensAlias": str,
@@ -301,41 +360,114 @@
 )
 
 class CreateLensVersionInputRequestTypeDef(
     _RequiredCreateLensVersionInputRequestTypeDef, _OptionalCreateLensVersionInputRequestTypeDef
 ):
     pass
 
+CreateLensVersionOutputTypeDef = TypedDict(
+    "CreateLensVersionOutputTypeDef",
+    {
+        "LensArn": str,
+        "LensVersion": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateMilestoneInputRequestTypeDef = TypedDict(
     "CreateMilestoneInputRequestTypeDef",
     {
         "WorkloadId": str,
         "MilestoneName": str,
         "ClientRequestToken": str,
     },
 )
 
+CreateMilestoneOutputTypeDef = TypedDict(
+    "CreateMilestoneOutputTypeDef",
+    {
+        "WorkloadId": str,
+        "MilestoneNumber": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ProfileQuestionUpdateTypeDef = TypedDict(
+    "ProfileQuestionUpdateTypeDef",
+    {
+        "QuestionId": str,
+        "SelectedChoiceIds": Sequence[str],
+    },
+    total=False,
+)
+
+CreateProfileOutputTypeDef = TypedDict(
+    "CreateProfileOutputTypeDef",
+    {
+        "ProfileArn": str,
+        "ProfileVersion": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateProfileShareInputRequestTypeDef = TypedDict(
+    "CreateProfileShareInputRequestTypeDef",
+    {
+        "ProfileArn": str,
+        "SharedWith": str,
+        "ClientRequestToken": str,
+    },
+)
+
+CreateProfileShareOutputTypeDef = TypedDict(
+    "CreateProfileShareOutputTypeDef",
+    {
+        "ShareId": str,
+        "ProfileArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 WorkloadDiscoveryConfigTypeDef = TypedDict(
     "WorkloadDiscoveryConfigTypeDef",
     {
         "TrustedAdvisorIntegrationStatus": TrustedAdvisorIntegrationStatusType,
+        "WorkloadResourceDefinition": Sequence[DefinitionTypeType],
     },
     total=False,
 )
 
+CreateWorkloadOutputTypeDef = TypedDict(
+    "CreateWorkloadOutputTypeDef",
+    {
+        "WorkloadId": str,
+        "WorkloadArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateWorkloadShareInputRequestTypeDef = TypedDict(
     "CreateWorkloadShareInputRequestTypeDef",
     {
         "WorkloadId": str,
         "SharedWith": str,
         "PermissionType": PermissionTypeType,
         "ClientRequestToken": str,
     },
 )
 
+CreateWorkloadShareOutputTypeDef = TypedDict(
+    "CreateWorkloadShareOutputTypeDef",
+    {
+        "WorkloadId": str,
+        "ShareId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteLensInputRequestTypeDef = TypedDict(
     "DeleteLensInputRequestTypeDef",
     {
         "LensAlias": str,
         "ClientRequestToken": str,
         "LensStatus": LensStatusTypeType,
     },
@@ -346,14 +478,31 @@
     {
         "ShareId": str,
         "LensAlias": str,
         "ClientRequestToken": str,
     },
 )
 
+DeleteProfileInputRequestTypeDef = TypedDict(
+    "DeleteProfileInputRequestTypeDef",
+    {
+        "ProfileArn": str,
+        "ClientRequestToken": str,
+    },
+)
+
+DeleteProfileShareInputRequestTypeDef = TypedDict(
+    "DeleteProfileShareInputRequestTypeDef",
+    {
+        "ShareId": str,
+        "ProfileArn": str,
+        "ClientRequestToken": str,
+    },
+)
+
 DeleteWorkloadInputRequestTypeDef = TypedDict(
     "DeleteWorkloadInputRequestTypeDef",
     {
         "WorkloadId": str,
         "ClientRequestToken": str,
     },
 )
@@ -371,14 +520,29 @@
     "DisassociateLensesInputRequestTypeDef",
     {
         "WorkloadId": str,
         "LensAliases": Sequence[str],
     },
 )
 
+DisassociateProfilesInputRequestTypeDef = TypedDict(
+    "DisassociateProfilesInputRequestTypeDef",
+    {
+        "WorkloadId": str,
+        "ProfileArns": Sequence[str],
+    },
+)
+
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredExportLensInputRequestTypeDef = TypedDict(
     "_RequiredExportLensInputRequestTypeDef",
     {
         "LensAlias": str,
     },
 )
 _OptionalExportLensInputRequestTypeDef = TypedDict(
@@ -390,14 +554,22 @@
 )
 
 class ExportLensInputRequestTypeDef(
     _RequiredExportLensInputRequestTypeDef, _OptionalExportLensInputRequestTypeDef
 ):
     pass
 
+ExportLensOutputTypeDef = TypedDict(
+    "ExportLensOutputTypeDef",
+    {
+        "LensJSON": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetAnswerInputRequestTypeDef = TypedDict(
     "_RequiredGetAnswerInputRequestTypeDef",
     {
         "WorkloadId": str,
         "LensAlias": str,
         "QuestionId": str,
     },
@@ -411,14 +583,36 @@
 )
 
 class GetAnswerInputRequestTypeDef(
     _RequiredGetAnswerInputRequestTypeDef, _OptionalGetAnswerInputRequestTypeDef
 ):
     pass
 
+_RequiredGetConsolidatedReportInputRequestTypeDef = TypedDict(
+    "_RequiredGetConsolidatedReportInputRequestTypeDef",
+    {
+        "Format": ReportFormatType,
+    },
+)
+_OptionalGetConsolidatedReportInputRequestTypeDef = TypedDict(
+    "_OptionalGetConsolidatedReportInputRequestTypeDef",
+    {
+        "IncludeSharedResources": bool,
+        "NextToken": str,
+        "MaxResults": int,
+    },
+    total=False,
+)
+
+class GetConsolidatedReportInputRequestTypeDef(
+    _RequiredGetConsolidatedReportInputRequestTypeDef,
+    _OptionalGetConsolidatedReportInputRequestTypeDef,
+):
+    pass
+
 _RequiredGetLensInputRequestTypeDef = TypedDict(
     "_RequiredGetLensInputRequestTypeDef",
     {
         "LensAlias": str,
     },
 )
 _OptionalGetLensInputRequestTypeDef = TypedDict(
@@ -523,14 +717,33 @@
     "GetMilestoneInputRequestTypeDef",
     {
         "WorkloadId": str,
         "MilestoneNumber": int,
     },
 )
 
+_RequiredGetProfileInputRequestTypeDef = TypedDict(
+    "_RequiredGetProfileInputRequestTypeDef",
+    {
+        "ProfileArn": str,
+    },
+)
+_OptionalGetProfileInputRequestTypeDef = TypedDict(
+    "_OptionalGetProfileInputRequestTypeDef",
+    {
+        "ProfileVersion": str,
+    },
+    total=False,
+)
+
+class GetProfileInputRequestTypeDef(
+    _RequiredGetProfileInputRequestTypeDef, _OptionalGetProfileInputRequestTypeDef
+):
+    pass
+
 GetWorkloadInputRequestTypeDef = TypedDict(
     "GetWorkloadInputRequestTypeDef",
     {
         "WorkloadId": str,
     },
 )
 
@@ -551,35 +764,40 @@
 )
 
 class ImportLensInputRequestTypeDef(
     _RequiredImportLensInputRequestTypeDef, _OptionalImportLensInputRequestTypeDef
 ):
     pass
 
-LensReviewSummaryTypeDef = TypedDict(
-    "LensReviewSummaryTypeDef",
+ImportLensOutputTypeDef = TypedDict(
+    "ImportLensOutputTypeDef",
     {
-        "LensAlias": str,
         "LensArn": str,
-        "LensVersion": str,
-        "LensName": str,
-        "LensStatus": LensStatusType,
-        "UpdatedAt": datetime,
-        "RiskCounts": Dict[RiskType, int],
+        "Status": ImportLensStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+WorkloadProfileTypeDef = TypedDict(
+    "WorkloadProfileTypeDef",
+    {
+        "ProfileArn": str,
+        "ProfileVersion": str,
     },
     total=False,
 )
 
 PillarReviewSummaryTypeDef = TypedDict(
     "PillarReviewSummaryTypeDef",
     {
         "PillarId": str,
         "PillarName": str,
         "Notes": str,
         "RiskCounts": Dict[RiskType, int],
+        "PrioritizedRiskCounts": Dict[RiskType, int],
     },
     total=False,
 )
 
 LensShareSummaryTypeDef = TypedDict(
     "LensShareSummaryTypeDef",
     {
@@ -631,14 +849,15 @@
 _OptionalListAnswersInputRequestTypeDef = TypedDict(
     "_OptionalListAnswersInputRequestTypeDef",
     {
         "PillarId": str,
         "MilestoneNumber": int,
         "NextToken": str,
         "MaxResults": int,
+        "QuestionPriority": QuestionPriorityType,
     },
     total=False,
 )
 
 class ListAnswersInputRequestTypeDef(
     _RequiredListAnswersInputRequestTypeDef, _OptionalListAnswersInputRequestTypeDef
 ):
@@ -702,14 +921,15 @@
 _OptionalListLensReviewImprovementsInputRequestTypeDef = TypedDict(
     "_OptionalListLensReviewImprovementsInputRequestTypeDef",
     {
         "PillarId": str,
         "MilestoneNumber": int,
         "NextToken": str,
         "MaxResults": int,
+        "QuestionPriority": QuestionPriorityType,
     },
     total=False,
 )
 
 class ListLensReviewImprovementsInputRequestTypeDef(
     _RequiredListLensReviewImprovementsInputRequestTypeDef,
     _OptionalListLensReviewImprovementsInputRequestTypeDef,
@@ -797,22 +1017,105 @@
         "WorkloadId": str,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+ListProfileNotificationsInputRequestTypeDef = TypedDict(
+    "ListProfileNotificationsInputRequestTypeDef",
+    {
+        "WorkloadId": str,
+        "NextToken": str,
+        "MaxResults": int,
+    },
+    total=False,
+)
+
+ProfileNotificationSummaryTypeDef = TypedDict(
+    "ProfileNotificationSummaryTypeDef",
+    {
+        "CurrentProfileVersion": str,
+        "LatestProfileVersion": str,
+        "Type": ProfileNotificationTypeType,
+        "ProfileArn": str,
+        "ProfileName": str,
+        "WorkloadId": str,
+        "WorkloadName": str,
+    },
+    total=False,
+)
+
+_RequiredListProfileSharesInputRequestTypeDef = TypedDict(
+    "_RequiredListProfileSharesInputRequestTypeDef",
+    {
+        "ProfileArn": str,
+    },
+)
+_OptionalListProfileSharesInputRequestTypeDef = TypedDict(
+    "_OptionalListProfileSharesInputRequestTypeDef",
+    {
+        "SharedWithPrefix": str,
+        "NextToken": str,
+        "MaxResults": int,
+        "Status": ShareStatusType,
+    },
+    total=False,
+)
+
+class ListProfileSharesInputRequestTypeDef(
+    _RequiredListProfileSharesInputRequestTypeDef, _OptionalListProfileSharesInputRequestTypeDef
+):
+    pass
+
+ProfileShareSummaryTypeDef = TypedDict(
+    "ProfileShareSummaryTypeDef",
+    {
+        "ShareId": str,
+        "SharedWith": str,
+        "Status": ShareStatusType,
+        "StatusMessage": str,
+    },
+    total=False,
+)
+
+ListProfilesInputRequestTypeDef = TypedDict(
+    "ListProfilesInputRequestTypeDef",
+    {
+        "ProfileNamePrefix": str,
+        "ProfileOwnerType": ProfileOwnerTypeType,
+        "NextToken": str,
+        "MaxResults": int,
+    },
+    total=False,
+)
+
+ProfileSummaryTypeDef = TypedDict(
+    "ProfileSummaryTypeDef",
+    {
+        "ProfileArn": str,
+        "ProfileVersion": str,
+        "ProfileName": str,
+        "ProfileDescription": str,
+        "Owner": str,
+        "CreatedAt": datetime,
+        "UpdatedAt": datetime,
+    },
+    total=False,
+)
+
 ListShareInvitationsInputRequestTypeDef = TypedDict(
     "ListShareInvitationsInputRequestTypeDef",
     {
         "WorkloadNamePrefix": str,
         "LensNamePrefix": str,
         "ShareResourceType": ShareResourceTypeType,
         "NextToken": str,
         "MaxResults": int,
+        "ProfileNamePrefix": str,
     },
     total=False,
 )
 
 ShareInvitationSummaryTypeDef = TypedDict(
     "ShareInvitationSummaryTypeDef",
     {
@@ -821,25 +1124,35 @@
         "SharedWith": str,
         "PermissionType": PermissionTypeType,
         "ShareResourceType": ShareResourceTypeType,
         "WorkloadName": str,
         "WorkloadId": str,
         "LensName": str,
         "LensArn": str,
+        "ProfileName": str,
+        "ProfileArn": str,
     },
     total=False,
 )
 
 ListTagsForResourceInputRequestTypeDef = TypedDict(
     "ListTagsForResourceInputRequestTypeDef",
     {
         "WorkloadArn": str,
     },
 )
 
+ListTagsForResourceOutputTypeDef = TypedDict(
+    "ListTagsForResourceOutputTypeDef",
+    {
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredListWorkloadSharesInputRequestTypeDef = TypedDict(
     "_RequiredListWorkloadSharesInputRequestTypeDef",
     {
         "WorkloadId": str,
     },
 )
 _OptionalListWorkloadSharesInputRequestTypeDef = TypedDict(
@@ -876,47 +1189,64 @@
         "WorkloadNamePrefix": str,
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-WorkloadSummaryTypeDef = TypedDict(
-    "WorkloadSummaryTypeDef",
-    {
-        "WorkloadId": str,
-        "WorkloadArn": str,
-        "WorkloadName": str,
-        "Owner": str,
-        "UpdatedAt": datetime,
-        "Lenses": List[str],
-        "RiskCounts": Dict[RiskType, int],
-        "ImprovementStatus": WorkloadImprovementStatusType,
-    },
-    total=False,
-)
-
 QuestionDifferenceTypeDef = TypedDict(
     "QuestionDifferenceTypeDef",
     {
         "QuestionId": str,
         "QuestionTitle": str,
         "DifferenceStatus": DifferenceStatusType,
     },
     total=False,
 )
 
+ProfileChoiceTypeDef = TypedDict(
+    "ProfileChoiceTypeDef",
+    {
+        "ChoiceId": str,
+        "ChoiceTitle": str,
+        "ChoiceDescription": str,
+    },
+    total=False,
+)
+
+ProfileTemplateChoiceTypeDef = TypedDict(
+    "ProfileTemplateChoiceTypeDef",
+    {
+        "ChoiceId": str,
+        "ChoiceTitle": str,
+        "ChoiceDescription": str,
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
 ShareInvitationTypeDef = TypedDict(
     "ShareInvitationTypeDef",
     {
         "ShareInvitationId": str,
         "ShareResourceType": ShareResourceTypeType,
         "WorkloadId": str,
         "LensAlias": str,
         "LensArn": str,
+        "ProfileArn": str,
     },
     total=False,
 )
 
 TagResourceInputRequestTypeDef = TypedDict(
     "TagResourceInputRequestTypeDef",
     {
@@ -933,14 +1263,15 @@
     },
 )
 
 UpdateGlobalSettingsInputRequestTypeDef = TypedDict(
     "UpdateGlobalSettingsInputRequestTypeDef",
     {
         "OrganizationSharingStatus": OrganizationSharingStatusType,
+        "DiscoveryIntegrationStatus": DiscoveryIntegrationStatusType,
     },
     total=False,
 )
 
 _RequiredUpdateLensReviewInputRequestTypeDef = TypedDict(
     "_RequiredUpdateLensReviewInputRequestTypeDef",
     {
@@ -1010,23 +1341,73 @@
 )
 
 class UpgradeLensReviewInputRequestTypeDef(
     _RequiredUpgradeLensReviewInputRequestTypeDef, _OptionalUpgradeLensReviewInputRequestTypeDef
 ):
     pass
 
+_RequiredUpgradeProfileVersionInputRequestTypeDef = TypedDict(
+    "_RequiredUpgradeProfileVersionInputRequestTypeDef",
+    {
+        "WorkloadId": str,
+        "ProfileArn": str,
+    },
+)
+_OptionalUpgradeProfileVersionInputRequestTypeDef = TypedDict(
+    "_OptionalUpgradeProfileVersionInputRequestTypeDef",
+    {
+        "MilestoneName": str,
+        "ClientRequestToken": str,
+    },
+    total=False,
+)
+
+class UpgradeProfileVersionInputRequestTypeDef(
+    _RequiredUpgradeProfileVersionInputRequestTypeDef,
+    _OptionalUpgradeProfileVersionInputRequestTypeDef,
+):
+    pass
+
 AdditionalResourcesTypeDef = TypedDict(
     "AdditionalResourcesTypeDef",
     {
         "Type": AdditionalResourceTypeType,
         "Content": List[ChoiceContentTypeDef],
     },
     total=False,
 )
 
+QuestionMetricTypeDef = TypedDict(
+    "QuestionMetricTypeDef",
+    {
+        "QuestionId": str,
+        "Risk": RiskType,
+        "BestPractices": List[BestPracticeTypeDef],
+    },
+    total=False,
+)
+
+ListCheckDetailsOutputTypeDef = TypedDict(
+    "ListCheckDetailsOutputTypeDef",
+    {
+        "CheckDetails": List[CheckDetailTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListCheckSummariesOutputTypeDef = TypedDict(
+    "ListCheckSummariesOutputTypeDef",
+    {
+        "CheckSummaries": List[CheckSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ImprovementSummaryTypeDef = TypedDict(
     "ImprovementSummaryTypeDef",
     {
         "QuestionId": str,
         "PillarId": str,
         "QuestionTitle": str,
         "Risk": RiskType,
@@ -1057,107 +1438,55 @@
 )
 
 class UpdateAnswerInputRequestTypeDef(
     _RequiredUpdateAnswerInputRequestTypeDef, _OptionalUpdateAnswerInputRequestTypeDef
 ):
     pass
 
-CreateLensShareOutputTypeDef = TypedDict(
-    "CreateLensShareOutputTypeDef",
-    {
-        "ShareId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateLensVersionOutputTypeDef = TypedDict(
-    "CreateLensVersionOutputTypeDef",
+_RequiredCreateProfileInputRequestTypeDef = TypedDict(
+    "_RequiredCreateProfileInputRequestTypeDef",
     {
-        "LensArn": str,
-        "LensVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateMilestoneOutputTypeDef = TypedDict(
-    "CreateMilestoneOutputTypeDef",
-    {
-        "WorkloadId": str,
-        "MilestoneNumber": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateWorkloadOutputTypeDef = TypedDict(
-    "CreateWorkloadOutputTypeDef",
-    {
-        "WorkloadId": str,
-        "WorkloadArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateWorkloadShareOutputTypeDef = TypedDict(
-    "CreateWorkloadShareOutputTypeDef",
-    {
-        "WorkloadId": str,
-        "ShareId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ProfileName": str,
+        "ProfileDescription": str,
+        "ProfileQuestions": Sequence[ProfileQuestionUpdateTypeDef],
+        "ClientRequestToken": str,
     },
 )
-
-ExportLensOutputTypeDef = TypedDict(
-    "ExportLensOutputTypeDef",
+_OptionalCreateProfileInputRequestTypeDef = TypedDict(
+    "_OptionalCreateProfileInputRequestTypeDef",
     {
-        "LensJSON": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Tags": Mapping[str, str],
     },
+    total=False,
 )
 
-ImportLensOutputTypeDef = TypedDict(
-    "ImportLensOutputTypeDef",
-    {
-        "LensArn": str,
-        "Status": ImportLensStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class CreateProfileInputRequestTypeDef(
+    _RequiredCreateProfileInputRequestTypeDef, _OptionalCreateProfileInputRequestTypeDef
+):
+    pass
 
-ListCheckDetailsOutputTypeDef = TypedDict(
-    "ListCheckDetailsOutputTypeDef",
+_RequiredUpdateProfileInputRequestTypeDef = TypedDict(
+    "_RequiredUpdateProfileInputRequestTypeDef",
     {
-        "CheckDetails": List[CheckDetailTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ProfileArn": str,
     },
 )
-
-ListCheckSummariesOutputTypeDef = TypedDict(
-    "ListCheckSummariesOutputTypeDef",
+_OptionalUpdateProfileInputRequestTypeDef = TypedDict(
+    "_OptionalUpdateProfileInputRequestTypeDef",
     {
-        "CheckSummaries": List[CheckSummaryTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ProfileDescription": str,
+        "ProfileQuestions": Sequence[ProfileQuestionUpdateTypeDef],
     },
+    total=False,
 )
 
-ListTagsForResourceOutputTypeDef = TypedDict(
-    "ListTagsForResourceOutputTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class UpdateProfileInputRequestTypeDef(
+    _RequiredUpdateProfileInputRequestTypeDef, _OptionalUpdateProfileInputRequestTypeDef
+):
+    pass
 
 _RequiredCreateWorkloadInputRequestTypeDef = TypedDict(
     "_RequiredCreateWorkloadInputRequestTypeDef",
     {
         "WorkloadName": str,
         "Description": str,
         "Environment": WorkloadEnvironmentType,
@@ -1176,14 +1505,15 @@
         "ReviewOwner": str,
         "IndustryType": str,
         "Industry": str,
         "Notes": str,
         "Tags": Mapping[str, str],
         "DiscoveryConfig": WorkloadDiscoveryConfigTypeDef,
         "Applications": Sequence[str],
+        "ProfileArns": Sequence[str],
     },
     total=False,
 )
 
 class CreateWorkloadInputRequestTypeDef(
     _RequiredCreateWorkloadInputRequestTypeDef, _OptionalCreateWorkloadInputRequestTypeDef
 ):
@@ -1219,14 +1549,65 @@
 )
 
 class UpdateWorkloadInputRequestTypeDef(
     _RequiredUpdateWorkloadInputRequestTypeDef, _OptionalUpdateWorkloadInputRequestTypeDef
 ):
     pass
 
+GetLensOutputTypeDef = TypedDict(
+    "GetLensOutputTypeDef",
+    {
+        "Lens": LensTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetLensReviewReportOutputTypeDef = TypedDict(
+    "GetLensReviewReportOutputTypeDef",
+    {
+        "WorkloadId": str,
+        "MilestoneNumber": int,
+        "LensReviewReport": LensReviewReportTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+LensReviewSummaryTypeDef = TypedDict(
+    "LensReviewSummaryTypeDef",
+    {
+        "LensAlias": str,
+        "LensArn": str,
+        "LensVersion": str,
+        "LensName": str,
+        "LensStatus": LensStatusType,
+        "UpdatedAt": datetime,
+        "RiskCounts": Dict[RiskType, int],
+        "Profiles": List[WorkloadProfileTypeDef],
+        "PrioritizedRiskCounts": Dict[RiskType, int],
+    },
+    total=False,
+)
+
+WorkloadSummaryTypeDef = TypedDict(
+    "WorkloadSummaryTypeDef",
+    {
+        "WorkloadId": str,
+        "WorkloadArn": str,
+        "WorkloadName": str,
+        "Owner": str,
+        "UpdatedAt": datetime,
+        "Lenses": List[str],
+        "RiskCounts": Dict[RiskType, int],
+        "ImprovementStatus": WorkloadImprovementStatusType,
+        "Profiles": List[WorkloadProfileTypeDef],
+        "PrioritizedRiskCounts": Dict[RiskType, int],
+    },
+    total=False,
+)
+
 WorkloadTypeDef = TypedDict(
     "WorkloadTypeDef",
     {
         "WorkloadId": str,
         "WorkloadArn": str,
         "WorkloadName": str,
         "Description": str,
@@ -1247,155 +1628,164 @@
         "PillarPriorities": List[str],
         "Lenses": List[str],
         "Owner": str,
         "ShareInvitationId": str,
         "Tags": Dict[str, str],
         "DiscoveryConfig": WorkloadDiscoveryConfigTypeDef,
         "Applications": List[str],
+        "Profiles": List[WorkloadProfileTypeDef],
+        "PrioritizedRiskCounts": Dict[RiskType, int],
     },
     total=False,
 )
 
-GetLensOutputTypeDef = TypedDict(
-    "GetLensOutputTypeDef",
-    {
-        "Lens": LensTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetLensReviewReportOutputTypeDef = TypedDict(
-    "GetLensReviewReportOutputTypeDef",
-    {
-        "WorkloadId": str,
-        "MilestoneNumber": int,
-        "LensReviewReport": LensReviewReportTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListLensReviewsOutputTypeDef = TypedDict(
-    "ListLensReviewsOutputTypeDef",
-    {
-        "WorkloadId": str,
-        "MilestoneNumber": int,
-        "LensReviewSummaries": List[LensReviewSummaryTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 LensReviewTypeDef = TypedDict(
     "LensReviewTypeDef",
     {
         "LensAlias": str,
         "LensArn": str,
         "LensVersion": str,
         "LensName": str,
         "LensStatus": LensStatusType,
         "PillarReviewSummaries": List[PillarReviewSummaryTypeDef],
         "UpdatedAt": datetime,
         "Notes": str,
         "RiskCounts": Dict[RiskType, int],
         "NextToken": str,
+        "Profiles": List[WorkloadProfileTypeDef],
+        "PrioritizedRiskCounts": Dict[RiskType, int],
     },
     total=False,
 )
 
 ListLensSharesOutputTypeDef = TypedDict(
     "ListLensSharesOutputTypeDef",
     {
         "LensShareSummaries": List[LensShareSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListLensesOutputTypeDef = TypedDict(
     "ListLensesOutputTypeDef",
     {
         "LensSummaries": List[LensSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 NotificationSummaryTypeDef = TypedDict(
     "NotificationSummaryTypeDef",
     {
         "Type": NotificationTypeType,
         "LensUpgradeSummary": LensUpgradeSummaryTypeDef,
     },
     total=False,
 )
 
+ListProfileNotificationsOutputTypeDef = TypedDict(
+    "ListProfileNotificationsOutputTypeDef",
+    {
+        "NotificationSummaries": List[ProfileNotificationSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListProfileSharesOutputTypeDef = TypedDict(
+    "ListProfileSharesOutputTypeDef",
+    {
+        "ProfileShareSummaries": List[ProfileShareSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListProfilesOutputTypeDef = TypedDict(
+    "ListProfilesOutputTypeDef",
+    {
+        "ProfileSummaries": List[ProfileSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListShareInvitationsOutputTypeDef = TypedDict(
     "ListShareInvitationsOutputTypeDef",
     {
         "ShareInvitationSummaries": List[ShareInvitationSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListWorkloadSharesOutputTypeDef = TypedDict(
     "ListWorkloadSharesOutputTypeDef",
     {
         "WorkloadId": str,
         "WorkloadShareSummaries": List[WorkloadShareSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListWorkloadsOutputTypeDef = TypedDict(
-    "ListWorkloadsOutputTypeDef",
+PillarDifferenceTypeDef = TypedDict(
+    "PillarDifferenceTypeDef",
     {
-        "WorkloadSummaries": List[WorkloadSummaryTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "PillarId": str,
+        "PillarName": str,
+        "DifferenceStatus": DifferenceStatusType,
+        "QuestionDifferences": List[QuestionDifferenceTypeDef],
     },
+    total=False,
 )
 
-MilestoneSummaryTypeDef = TypedDict(
-    "MilestoneSummaryTypeDef",
+ProfileQuestionTypeDef = TypedDict(
+    "ProfileQuestionTypeDef",
     {
-        "MilestoneNumber": int,
-        "MilestoneName": str,
-        "RecordedAt": datetime,
-        "WorkloadSummary": WorkloadSummaryTypeDef,
+        "QuestionId": str,
+        "QuestionTitle": str,
+        "QuestionDescription": str,
+        "QuestionChoices": List[ProfileChoiceTypeDef],
+        "SelectedChoiceIds": List[str],
+        "MinSelectedChoices": int,
+        "MaxSelectedChoices": int,
     },
     total=False,
 )
 
-PillarDifferenceTypeDef = TypedDict(
-    "PillarDifferenceTypeDef",
+ProfileTemplateQuestionTypeDef = TypedDict(
+    "ProfileTemplateQuestionTypeDef",
     {
-        "PillarId": str,
-        "PillarName": str,
-        "DifferenceStatus": DifferenceStatusType,
-        "QuestionDifferences": List[QuestionDifferenceTypeDef],
+        "QuestionId": str,
+        "QuestionTitle": str,
+        "QuestionDescription": str,
+        "QuestionChoices": List[ProfileTemplateChoiceTypeDef],
+        "MinSelectedChoices": int,
+        "MaxSelectedChoices": int,
     },
     total=False,
 )
 
 UpdateShareInvitationOutputTypeDef = TypedDict(
     "UpdateShareInvitationOutputTypeDef",
     {
         "ShareInvitation": ShareInvitationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateWorkloadShareOutputTypeDef = TypedDict(
     "UpdateWorkloadShareOutputTypeDef",
     {
         "WorkloadId": str,
         "WorkloadShare": WorkloadShareTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ChoiceTypeDef = TypedDict(
     "ChoiceTypeDef",
     {
         "ChoiceId": str,
@@ -1404,32 +1794,73 @@
         "HelpfulResource": ChoiceContentTypeDef,
         "ImprovementPlan": ChoiceContentTypeDef,
         "AdditionalResources": List[AdditionalResourcesTypeDef],
     },
     total=False,
 )
 
+PillarMetricTypeDef = TypedDict(
+    "PillarMetricTypeDef",
+    {
+        "PillarId": str,
+        "RiskCounts": Dict[RiskType, int],
+        "Questions": List[QuestionMetricTypeDef],
+    },
+    total=False,
+)
+
 ListLensReviewImprovementsOutputTypeDef = TypedDict(
     "ListLensReviewImprovementsOutputTypeDef",
     {
         "WorkloadId": str,
         "MilestoneNumber": int,
         "LensAlias": str,
         "LensArn": str,
         "ImprovementSummaries": List[ImprovementSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListLensReviewsOutputTypeDef = TypedDict(
+    "ListLensReviewsOutputTypeDef",
+    {
+        "WorkloadId": str,
+        "MilestoneNumber": int,
+        "LensReviewSummaries": List[LensReviewSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListWorkloadsOutputTypeDef = TypedDict(
+    "ListWorkloadsOutputTypeDef",
+    {
+        "WorkloadSummaries": List[WorkloadSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+MilestoneSummaryTypeDef = TypedDict(
+    "MilestoneSummaryTypeDef",
+    {
+        "MilestoneNumber": int,
+        "MilestoneName": str,
+        "RecordedAt": datetime,
+        "WorkloadSummary": WorkloadSummaryTypeDef,
     },
+    total=False,
 )
 
 GetWorkloadOutputTypeDef = TypedDict(
     "GetWorkloadOutputTypeDef",
     {
         "Workload": WorkloadTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 MilestoneTypeDef = TypedDict(
     "MilestoneTypeDef",
     {
         "MilestoneNumber": int,
@@ -1440,60 +1871,78 @@
     total=False,
 )
 
 UpdateWorkloadOutputTypeDef = TypedDict(
     "UpdateWorkloadOutputTypeDef",
     {
         "Workload": WorkloadTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetLensReviewOutputTypeDef = TypedDict(
     "GetLensReviewOutputTypeDef",
     {
         "WorkloadId": str,
         "MilestoneNumber": int,
         "LensReview": LensReviewTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateLensReviewOutputTypeDef = TypedDict(
     "UpdateLensReviewOutputTypeDef",
     {
         "WorkloadId": str,
         "LensReview": LensReviewTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListNotificationsOutputTypeDef = TypedDict(
     "ListNotificationsOutputTypeDef",
     {
         "NotificationSummaries": List[NotificationSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListMilestonesOutputTypeDef = TypedDict(
-    "ListMilestonesOutputTypeDef",
+VersionDifferencesTypeDef = TypedDict(
+    "VersionDifferencesTypeDef",
     {
-        "WorkloadId": str,
-        "MilestoneSummaries": List[MilestoneSummaryTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "PillarDifferences": List[PillarDifferenceTypeDef],
     },
+    total=False,
 )
 
-VersionDifferencesTypeDef = TypedDict(
-    "VersionDifferencesTypeDef",
+ProfileTypeDef = TypedDict(
+    "ProfileTypeDef",
     {
-        "PillarDifferences": List[PillarDifferenceTypeDef],
+        "ProfileArn": str,
+        "ProfileVersion": str,
+        "ProfileName": str,
+        "ProfileDescription": str,
+        "ProfileQuestions": List[ProfileQuestionTypeDef],
+        "Owner": str,
+        "CreatedAt": datetime,
+        "UpdatedAt": datetime,
+        "ShareInvitationId": str,
+        "Tags": Dict[str, str],
+    },
+    total=False,
+)
+
+ProfileTemplateTypeDef = TypedDict(
+    "ProfileTemplateTypeDef",
+    {
+        "TemplateName": str,
+        "TemplateQuestions": List[ProfileTemplateQuestionTypeDef],
+        "CreatedAt": datetime,
+        "UpdatedAt": datetime,
     },
     total=False,
 )
 
 AnswerSummaryTypeDef = TypedDict(
     "AnswerSummaryTypeDef",
     {
@@ -1502,14 +1951,15 @@
         "QuestionTitle": str,
         "Choices": List[ChoiceTypeDef],
         "SelectedChoices": List[str],
         "ChoiceAnswerSummaries": List[ChoiceAnswerSummaryTypeDef],
         "IsApplicable": bool,
         "Risk": RiskType,
         "Reason": AnswerReasonType,
+        "QuestionType": QuestionTypeType,
     },
     total=False,
 )
 
 AnswerTypeDef = TypedDict(
     "AnswerTypeDef",
     {
@@ -1527,64 +1977,133 @@
         "Risk": RiskType,
         "Notes": str,
         "Reason": AnswerReasonType,
     },
     total=False,
 )
 
+LensMetricTypeDef = TypedDict(
+    "LensMetricTypeDef",
+    {
+        "LensArn": str,
+        "Pillars": List[PillarMetricTypeDef],
+        "RiskCounts": Dict[RiskType, int],
+    },
+    total=False,
+)
+
+ListMilestonesOutputTypeDef = TypedDict(
+    "ListMilestonesOutputTypeDef",
+    {
+        "WorkloadId": str,
+        "MilestoneSummaries": List[MilestoneSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetMilestoneOutputTypeDef = TypedDict(
     "GetMilestoneOutputTypeDef",
     {
         "WorkloadId": str,
         "Milestone": MilestoneTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetLensVersionDifferenceOutputTypeDef = TypedDict(
     "GetLensVersionDifferenceOutputTypeDef",
     {
         "LensAlias": str,
         "LensArn": str,
         "BaseLensVersion": str,
         "TargetLensVersion": str,
         "LatestLensVersion": str,
         "VersionDifferences": VersionDifferencesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetProfileOutputTypeDef = TypedDict(
+    "GetProfileOutputTypeDef",
+    {
+        "Profile": ProfileTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateProfileOutputTypeDef = TypedDict(
+    "UpdateProfileOutputTypeDef",
+    {
+        "Profile": ProfileTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetProfileTemplateOutputTypeDef = TypedDict(
+    "GetProfileTemplateOutputTypeDef",
+    {
+        "ProfileTemplate": ProfileTemplateTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAnswersOutputTypeDef = TypedDict(
     "ListAnswersOutputTypeDef",
     {
         "WorkloadId": str,
         "MilestoneNumber": int,
         "LensAlias": str,
         "LensArn": str,
         "AnswerSummaries": List[AnswerSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAnswerOutputTypeDef = TypedDict(
     "GetAnswerOutputTypeDef",
     {
         "WorkloadId": str,
         "MilestoneNumber": int,
         "LensAlias": str,
         "LensArn": str,
         "Answer": AnswerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAnswerOutputTypeDef = TypedDict(
     "UpdateAnswerOutputTypeDef",
     {
         "WorkloadId": str,
         "LensAlias": str,
         "LensArn": str,
         "Answer": AnswerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ConsolidatedReportMetricTypeDef = TypedDict(
+    "ConsolidatedReportMetricTypeDef",
+    {
+        "MetricType": Literal["WORKLOAD"],
+        "RiskCounts": Dict[RiskType, int],
+        "WorkloadId": str,
+        "WorkloadName": str,
+        "WorkloadArn": str,
+        "UpdatedAt": datetime,
+        "Lenses": List[LensMetricTypeDef],
+        "LensesAppliedCount": int,
+    },
+    total=False,
+)
+
+GetConsolidatedReportOutputTypeDef = TypedDict(
+    "GetConsolidatedReportOutputTypeDef",
+    {
+        "Metrics": List[ConsolidatedReportMetricTypeDef],
+        "NextToken": str,
+        "Base64String": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-wellarchitected-2.5.0.post1/types_aiobotocore_wellarchitected.egg-info/SOURCES.txt` & `types-aiobotocore-wellarchitected-2.5.1/types_aiobotocore_wellarchitected.egg-info/SOURCES.txt`

 * *Files identical despite different names*

