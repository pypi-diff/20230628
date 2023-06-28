# Comparing `tmp/types-aiobotocore-pinpoint-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-pinpoint-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-pinpoint-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:07 2023, max compression
+gzip compressed data, was "types-aiobotocore-pinpoint-2.5.1.tar", last modified: Wed Jun 28 01:43:58 2023, max compression
```

## Comparing `types-aiobotocore-pinpoint-2.5.0.post1.tar` & `types-aiobotocore-pinpoint-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:07.951506 types-aiobotocore-pinpoint-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:19:50.000000 types-aiobotocore-pinpoint-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    28738 2023-03-11 12:27:07.947506 types-aiobotocore-pinpoint-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    27163 2023-03-11 12:19:50.000000 types-aiobotocore-pinpoint-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:07.951506 types-aiobotocore-pinpoint-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2131 2023-03-11 12:19:50.000000 types-aiobotocore-pinpoint-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:07.935506 types-aiobotocore-pinpoint-2.5.0.post1/types_aiobotocore_pinpoint/
--rw-r--r--   0 runner    (1001) docker     (123)      450 2023-03-11 12:19:50.000000 types-aiobotocore-pinpoint-2.5.0.post1/types_aiobotocore_pinpoint/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      449 2023-03-11 12:19:50.000000 types-aiobotocore-pinpoint-2.5.0.post1/types_aiobotocore_pinpoint/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      947 2023-03-11 12:19:50.000000 types-aiobotocore-pinpoint-2.5.0.post1/types_aiobotocore_pinpoint/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    81634 2023-03-11 12:19:50.000000 types-aiobotocore-pinpoint-2.5.0.post1/types_aiobotocore_pinpoint/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    81507 2023-03-11 12:19:50.000000 types-aiobotocore-pinpoint-2.5.0.post1/types_aiobotocore_pinpoint/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10383 2023-03-11 12:19:51.000000 types-aiobotocore-pinpoint-2.5.0.post1/types_aiobotocore_pinpoint/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    10381 2023-03-11 12:19:51.000000 types-aiobotocore-pinpoint-2.5.0.post1/types_aiobotocore_pinpoint/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:19:50.000000 types-aiobotocore-pinpoint-2.5.0.post1/types_aiobotocore_pinpoint/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)   154300 2023-03-11 12:19:56.000000 types-aiobotocore-pinpoint-2.5.0.post1/types_aiobotocore_pinpoint/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)   154091 2023-03-11 12:19:52.000000 types-aiobotocore-pinpoint-2.5.0.post1/types_aiobotocore_pinpoint/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:19:50.000000 types-aiobotocore-pinpoint-2.5.0.post1/types_aiobotocore_pinpoint/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:07.947506 types-aiobotocore-pinpoint-2.5.0.post1/types_aiobotocore_pinpoint.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    28738 2023-03-11 12:27:07.000000 types-aiobotocore-pinpoint-2.5.0.post1/types_aiobotocore_pinpoint.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      751 2023-03-11 12:27:07.000000 types-aiobotocore-pinpoint-2.5.0.post1/types_aiobotocore_pinpoint.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:07.000000 types-aiobotocore-pinpoint-2.5.0.post1/types_aiobotocore_pinpoint.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:07.000000 types-aiobotocore-pinpoint-2.5.0.post1/types_aiobotocore_pinpoint.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:07.000000 types-aiobotocore-pinpoint-2.5.0.post1/types_aiobotocore_pinpoint.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       27 2023-03-11 12:27:07.000000 types-aiobotocore-pinpoint-2.5.0.post1/types_aiobotocore_pinpoint.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:58.902192 types-aiobotocore-pinpoint-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:36:38.000000 types-aiobotocore-pinpoint-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    29268 2023-06-28 01:43:58.902192 types-aiobotocore-pinpoint-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    27699 2023-06-28 01:36:38.000000 types-aiobotocore-pinpoint-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:58.902192 types-aiobotocore-pinpoint-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2125 2023-06-28 01:36:38.000000 types-aiobotocore-pinpoint-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:58.902192 types-aiobotocore-pinpoint-2.5.1/types_aiobotocore_pinpoint/
+-rw-r--r--   0 runner    (1001) docker     (123)      450 2023-06-28 01:36:38.000000 types-aiobotocore-pinpoint-2.5.1/types_aiobotocore_pinpoint/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      449 2023-06-28 01:36:38.000000 types-aiobotocore-pinpoint-2.5.1/types_aiobotocore_pinpoint/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      935 2023-06-28 01:36:38.000000 types-aiobotocore-pinpoint-2.5.1/types_aiobotocore_pinpoint/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    83896 2023-06-28 01:36:38.000000 types-aiobotocore-pinpoint-2.5.1/types_aiobotocore_pinpoint/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    83766 2023-06-28 01:36:38.000000 types-aiobotocore-pinpoint-2.5.1/types_aiobotocore_pinpoint/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10823 2023-06-28 01:36:38.000000 types-aiobotocore-pinpoint-2.5.1/types_aiobotocore_pinpoint/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10821 2023-06-28 01:36:38.000000 types-aiobotocore-pinpoint-2.5.1/types_aiobotocore_pinpoint/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:36:38.000000 types-aiobotocore-pinpoint-2.5.1/types_aiobotocore_pinpoint/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)   159299 2023-06-28 01:36:43.000000 types-aiobotocore-pinpoint-2.5.1/types_aiobotocore_pinpoint/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)   159082 2023-06-28 01:36:40.000000 types-aiobotocore-pinpoint-2.5.1/types_aiobotocore_pinpoint/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:36:38.000000 types-aiobotocore-pinpoint-2.5.1/types_aiobotocore_pinpoint/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:58.902192 types-aiobotocore-pinpoint-2.5.1/types_aiobotocore_pinpoint.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    29268 2023-06-28 01:43:58.000000 types-aiobotocore-pinpoint-2.5.1/types_aiobotocore_pinpoint.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      751 2023-06-28 01:43:58.000000 types-aiobotocore-pinpoint-2.5.1/types_aiobotocore_pinpoint.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:58.000000 types-aiobotocore-pinpoint-2.5.1/types_aiobotocore_pinpoint.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:58.000000 types-aiobotocore-pinpoint-2.5.1/types_aiobotocore_pinpoint.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:58.000000 types-aiobotocore-pinpoint-2.5.1/types_aiobotocore_pinpoint.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       27 2023-06-28 01:43:58.000000 types-aiobotocore-pinpoint-2.5.1/types_aiobotocore_pinpoint.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-pinpoint-2.5.0.post1/LICENSE` & `types-aiobotocore-pinpoint-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-pinpoint-2.5.0.post1/PKG-INFO` & `types-aiobotocore-pinpoint-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-pinpoint
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Pinpoint 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Pinpoint 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-pinpoint"></a>
 
 # types-aiobotocore-pinpoint
 
 [![PyPI - types-aiobotocore-pinpoint](https://img.shields.io/pypi/v/types-aiobotocore-pinpoint.svg?color=blue)](https://pypi.org/project/types-aiobotocore-pinpoint)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-pinpoint.svg?color=blue)](https://pypi.org/project/types-aiobotocore-pinpoint)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-pinpoint?color=blue)](https://pypistats.org/packages/types-aiobotocore-pinpoint)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Pinpoint 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint.html#Pinpoint)
+[aiobotocore.Pinpoint 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint.html#Pinpoint)
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
 [types-aiobotocore-pinpoint docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint/).
 
 See how it helps to find and fix potential bugs:
 
@@ -284,23 +284,25 @@
     DurationType,
     EndpointTypesElementType,
     FilterTypeType,
     FormatType,
     FrequencyType,
     IncludeType,
     JobStatusType,
+    JourneyRunStatusType,
     LayoutType,
     MessageTypeType,
     ModeType,
     OperatorType,
     RecencyTypeType,
     SegmentTypeType,
     SourceTypeType,
     StateType,
     TemplateTypeType,
+    TimezoneEstimationMethodsElementType,
     TypeType,
     PinpointServiceName,
     ServiceName,
     ResourceServiceName,
     RegionName,
 )
 
@@ -350,15 +352,14 @@
     CampaignStateTypeDef,
     CustomDeliveryConfigurationTypeDef,
     CampaignSmsMessageTypeDef,
     ChannelResponseTypeDef,
     ClosedDaysRuleTypeDef,
     WaitTimeTypeDef,
     CreateApplicationRequestTypeDef,
-    ResponseMetadataTypeDef,
     EmailTemplateRequestTypeDef,
     CreateTemplateMessageBodyTypeDef,
     ExportJobRequestTypeDef,
     ImportJobRequestTypeDef,
     TemplateCreateMessageBodyTypeDef,
     CreateRecommenderConfigurationTypeDef,
     RecommenderConfigurationResponseTypeDef,
@@ -401,14 +402,15 @@
     GCMMessageTypeDef,
     SMSMessageTypeDef,
     VoiceMessageTypeDef,
     EmailChannelRequestTypeDef,
     JourneyEmailMessageTypeDef,
     RawEmailTypeDef,
     EmailTemplateResponseTypeDef,
+    EmptyResponseMetadataTypeDef,
     EndpointDemographicTypeDef,
     EndpointLocationTypeDef,
     EndpointUserTypeDef,
     EndpointItemResponseTypeDef,
     EndpointMessageResultTypeDef,
     EndpointSendConfigurationTypeDef,
     MetricDimensionTypeDef,
@@ -448,14 +450,19 @@
     GetInAppTemplateRequestRequestTypeDef,
     GetJourneyDateRangeKpiRequestRequestTypeDef,
     GetJourneyExecutionActivityMetricsRequestRequestTypeDef,
     JourneyExecutionActivityMetricsResponseTypeDef,
     GetJourneyExecutionMetricsRequestRequestTypeDef,
     JourneyExecutionMetricsResponseTypeDef,
     GetJourneyRequestRequestTypeDef,
+    GetJourneyRunExecutionActivityMetricsRequestRequestTypeDef,
+    JourneyRunExecutionActivityMetricsResponseTypeDef,
+    GetJourneyRunExecutionMetricsRequestRequestTypeDef,
+    JourneyRunExecutionMetricsResponseTypeDef,
+    GetJourneyRunsRequestRequestTypeDef,
     GetPushTemplateRequestRequestTypeDef,
     GetRecommenderConfigurationRequestRequestTypeDef,
     GetRecommenderConfigurationsRequestRequestTypeDef,
     GetSegmentExportJobsRequestRequestTypeDef,
     GetSegmentImportJobsRequestRequestTypeDef,
     GetSegmentRequestRequestTypeDef,
     GetSegmentVersionRequestRequestTypeDef,
@@ -472,14 +479,15 @@
     InAppMessageBodyConfigTypeDef,
     OverrideButtonConfigurationTypeDef,
     InAppMessageHeaderConfigTypeDef,
     JourneyChannelSettingsTypeDef,
     JourneyLimitsTypeDef,
     JourneyPushMessageTypeDef,
     JourneyScheduleTypeDef,
+    JourneyRunResponseTypeDef,
     JourneySMSMessageTypeDef,
     JourneyStateRequestTypeDef,
     ListJourneysRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     TagsModelTypeDef,
     ListTemplateVersionsRequestRequestTypeDef,
     ListTemplatesRequestRequestTypeDef,
@@ -488,14 +496,15 @@
     NumberValidateRequestTypeDef,
     NumberValidateResponseTypeDef,
     OpenHoursRuleTypeDef,
     WriteEventStreamTypeDef,
     RandomSplitEntryTypeDef,
     RecencyDimensionTypeDef,
     UpdateAttributesRequestTypeDef,
+    ResponseMetadataTypeDef,
     ResultRowValueTypeDef,
     SMSChannelRequestTypeDef,
     SegmentConditionTypeDef,
     SegmentReferenceTypeDef,
     SegmentImportResourceTypeDef,
     SendOTPMessageRequestParametersTypeDef,
     SimpleEmailPartTypeDef,
@@ -505,50 +514,49 @@
     TemplateVersionResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateRecommenderConfigurationTypeDef,
     VoiceChannelRequestTypeDef,
     VerificationResponseTypeDef,
     VerifyOTPMessageRequestParametersTypeDef,
     UpdateAdmChannelRequestRequestTypeDef,
+    DeleteAdmChannelResponseTypeDef,
+    GetAdmChannelResponseTypeDef,
+    UpdateAdmChannelResponseTypeDef,
     UpdateApnsChannelRequestRequestTypeDef,
+    DeleteApnsChannelResponseTypeDef,
+    GetApnsChannelResponseTypeDef,
+    UpdateApnsChannelResponseTypeDef,
     UpdateApnsSandboxChannelRequestRequestTypeDef,
+    DeleteApnsSandboxChannelResponseTypeDef,
+    GetApnsSandboxChannelResponseTypeDef,
+    UpdateApnsSandboxChannelResponseTypeDef,
     UpdateApnsVoipChannelRequestRequestTypeDef,
+    DeleteApnsVoipChannelResponseTypeDef,
+    GetApnsVoipChannelResponseTypeDef,
+    UpdateApnsVoipChannelResponseTypeDef,
     UpdateApnsVoipSandboxChannelRequestRequestTypeDef,
+    DeleteApnsVoipSandboxChannelResponseTypeDef,
+    GetApnsVoipSandboxChannelResponseTypeDef,
+    UpdateApnsVoipSandboxChannelResponseTypeDef,
     ActivitiesResponseTypeDef,
     ApplicationsResponseTypeDef,
+    CreateAppResponseTypeDef,
+    DeleteAppResponseTypeDef,
+    GetAppResponseTypeDef,
     ApplicationSettingsResourceTypeDef,
     WriteApplicationSettingsRequestTypeDef,
+    RemoveAttributesResponseTypeDef,
     UpdateBaiduChannelRequestRequestTypeDef,
+    DeleteBaiduChannelResponseTypeDef,
+    GetBaiduChannelResponseTypeDef,
+    UpdateBaiduChannelResponseTypeDef,
     ChannelsResponseTypeDef,
     ClosedDaysTypeDef,
     WaitActivityTypeDef,
     CreateAppRequestRequestTypeDef,
-    CreateAppResponseTypeDef,
-    DeleteAdmChannelResponseTypeDef,
-    DeleteApnsChannelResponseTypeDef,
-    DeleteApnsSandboxChannelResponseTypeDef,
-    DeleteApnsVoipChannelResponseTypeDef,
-    DeleteApnsVoipSandboxChannelResponseTypeDef,
-    DeleteAppResponseTypeDef,
-    DeleteBaiduChannelResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetAdmChannelResponseTypeDef,
-    GetApnsChannelResponseTypeDef,
-    GetApnsSandboxChannelResponseTypeDef,
-    GetApnsVoipChannelResponseTypeDef,
-    GetApnsVoipSandboxChannelResponseTypeDef,
-    GetAppResponseTypeDef,
-    GetBaiduChannelResponseTypeDef,
-    RemoveAttributesResponseTypeDef,
-    UpdateAdmChannelResponseTypeDef,
-    UpdateApnsChannelResponseTypeDef,
-    UpdateApnsSandboxChannelResponseTypeDef,
-    UpdateApnsVoipChannelResponseTypeDef,
-    UpdateApnsVoipSandboxChannelResponseTypeDef,
-    UpdateBaiduChannelResponseTypeDef,
     CreateEmailTemplateRequestRequestTypeDef,
     UpdateEmailTemplateRequestRequestTypeDef,
     CreateEmailTemplateResponseTypeDef,
     CreatePushTemplateResponseTypeDef,
     CreateSmsTemplateResponseTypeDef,
     CreateVoiceTemplateResponseTypeDef,
     CreateExportJobRequestRequestTypeDef,
@@ -608,19 +616,22 @@
     ItemResponseTypeDef,
     EventTypeDef,
     ExportJobResponseTypeDef,
     UpdateGcmChannelRequestRequestTypeDef,
     GPSPointDimensionTypeDef,
     GetJourneyExecutionActivityMetricsResponseTypeDef,
     GetJourneyExecutionMetricsResponseTypeDef,
+    GetJourneyRunExecutionActivityMetricsResponseTypeDef,
+    GetJourneyRunExecutionMetricsResponseTypeDef,
     GetSmsTemplateResponseTypeDef,
     GetVoiceTemplateResponseTypeDef,
     ImportJobResponseTypeDef,
     InAppMessageButtonTypeDef,
     PushMessageActivityTypeDef,
+    JourneyRunsResponseTypeDef,
     SMSMessageActivityTypeDef,
     UpdateJourneyStateRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     MessageResponseTypeDef,
     PhoneNumberValidateRequestRequestTypeDef,
     PhoneNumberValidateResponseTypeDef,
@@ -666,14 +677,15 @@
     ExportJobsResponseTypeDef,
     GetExportJobResponseTypeDef,
     SegmentLocationTypeDef,
     CreateImportJobResponseTypeDef,
     GetImportJobResponseTypeDef,
     ImportJobsResponseTypeDef,
     InAppMessageContentTypeDef,
+    GetJourneyRunsResponseTypeDef,
     SendMessagesResponseTypeDef,
     SendOTPMessageResponseTypeDef,
     BaseKpiResultTypeDef,
     EmailMessageTypeDef,
     ListTemplatesResponseTypeDef,
     ListTemplateVersionsResponseTypeDef,
     UpdateEndpointsBatchRequestRequestTypeDef,
@@ -768,43 +780,43 @@
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

### Comparing `types-aiobotocore-pinpoint-2.5.0.post1/README.md` & `types-aiobotocore-pinpoint-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-pinpoint"></a>
 
 # types-aiobotocore-pinpoint
 
 [![PyPI - types-aiobotocore-pinpoint](https://img.shields.io/pypi/v/types-aiobotocore-pinpoint.svg?color=blue)](https://pypi.org/project/types-aiobotocore-pinpoint)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-pinpoint.svg?color=blue)](https://pypi.org/project/types-aiobotocore-pinpoint)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-pinpoint?color=blue)](https://pypistats.org/packages/types-aiobotocore-pinpoint)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Pinpoint 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint.html#Pinpoint)
+[aiobotocore.Pinpoint 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint.html#Pinpoint)
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
 [types-aiobotocore-pinpoint docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint/).
 
 See how it helps to find and fix potential bugs:
 
@@ -251,23 +251,25 @@
     DurationType,
     EndpointTypesElementType,
     FilterTypeType,
     FormatType,
     FrequencyType,
     IncludeType,
     JobStatusType,
+    JourneyRunStatusType,
     LayoutType,
     MessageTypeType,
     ModeType,
     OperatorType,
     RecencyTypeType,
     SegmentTypeType,
     SourceTypeType,
     StateType,
     TemplateTypeType,
+    TimezoneEstimationMethodsElementType,
     TypeType,
     PinpointServiceName,
     ServiceName,
     ResourceServiceName,
     RegionName,
 )
 
@@ -317,15 +319,14 @@
     CampaignStateTypeDef,
     CustomDeliveryConfigurationTypeDef,
     CampaignSmsMessageTypeDef,
     ChannelResponseTypeDef,
     ClosedDaysRuleTypeDef,
     WaitTimeTypeDef,
     CreateApplicationRequestTypeDef,
-    ResponseMetadataTypeDef,
     EmailTemplateRequestTypeDef,
     CreateTemplateMessageBodyTypeDef,
     ExportJobRequestTypeDef,
     ImportJobRequestTypeDef,
     TemplateCreateMessageBodyTypeDef,
     CreateRecommenderConfigurationTypeDef,
     RecommenderConfigurationResponseTypeDef,
@@ -368,14 +369,15 @@
     GCMMessageTypeDef,
     SMSMessageTypeDef,
     VoiceMessageTypeDef,
     EmailChannelRequestTypeDef,
     JourneyEmailMessageTypeDef,
     RawEmailTypeDef,
     EmailTemplateResponseTypeDef,
+    EmptyResponseMetadataTypeDef,
     EndpointDemographicTypeDef,
     EndpointLocationTypeDef,
     EndpointUserTypeDef,
     EndpointItemResponseTypeDef,
     EndpointMessageResultTypeDef,
     EndpointSendConfigurationTypeDef,
     MetricDimensionTypeDef,
@@ -415,14 +417,19 @@
     GetInAppTemplateRequestRequestTypeDef,
     GetJourneyDateRangeKpiRequestRequestTypeDef,
     GetJourneyExecutionActivityMetricsRequestRequestTypeDef,
     JourneyExecutionActivityMetricsResponseTypeDef,
     GetJourneyExecutionMetricsRequestRequestTypeDef,
     JourneyExecutionMetricsResponseTypeDef,
     GetJourneyRequestRequestTypeDef,
+    GetJourneyRunExecutionActivityMetricsRequestRequestTypeDef,
+    JourneyRunExecutionActivityMetricsResponseTypeDef,
+    GetJourneyRunExecutionMetricsRequestRequestTypeDef,
+    JourneyRunExecutionMetricsResponseTypeDef,
+    GetJourneyRunsRequestRequestTypeDef,
     GetPushTemplateRequestRequestTypeDef,
     GetRecommenderConfigurationRequestRequestTypeDef,
     GetRecommenderConfigurationsRequestRequestTypeDef,
     GetSegmentExportJobsRequestRequestTypeDef,
     GetSegmentImportJobsRequestRequestTypeDef,
     GetSegmentRequestRequestTypeDef,
     GetSegmentVersionRequestRequestTypeDef,
@@ -439,14 +446,15 @@
     InAppMessageBodyConfigTypeDef,
     OverrideButtonConfigurationTypeDef,
     InAppMessageHeaderConfigTypeDef,
     JourneyChannelSettingsTypeDef,
     JourneyLimitsTypeDef,
     JourneyPushMessageTypeDef,
     JourneyScheduleTypeDef,
+    JourneyRunResponseTypeDef,
     JourneySMSMessageTypeDef,
     JourneyStateRequestTypeDef,
     ListJourneysRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     TagsModelTypeDef,
     ListTemplateVersionsRequestRequestTypeDef,
     ListTemplatesRequestRequestTypeDef,
@@ -455,14 +463,15 @@
     NumberValidateRequestTypeDef,
     NumberValidateResponseTypeDef,
     OpenHoursRuleTypeDef,
     WriteEventStreamTypeDef,
     RandomSplitEntryTypeDef,
     RecencyDimensionTypeDef,
     UpdateAttributesRequestTypeDef,
+    ResponseMetadataTypeDef,
     ResultRowValueTypeDef,
     SMSChannelRequestTypeDef,
     SegmentConditionTypeDef,
     SegmentReferenceTypeDef,
     SegmentImportResourceTypeDef,
     SendOTPMessageRequestParametersTypeDef,
     SimpleEmailPartTypeDef,
@@ -472,50 +481,49 @@
     TemplateVersionResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateRecommenderConfigurationTypeDef,
     VoiceChannelRequestTypeDef,
     VerificationResponseTypeDef,
     VerifyOTPMessageRequestParametersTypeDef,
     UpdateAdmChannelRequestRequestTypeDef,
+    DeleteAdmChannelResponseTypeDef,
+    GetAdmChannelResponseTypeDef,
+    UpdateAdmChannelResponseTypeDef,
     UpdateApnsChannelRequestRequestTypeDef,
+    DeleteApnsChannelResponseTypeDef,
+    GetApnsChannelResponseTypeDef,
+    UpdateApnsChannelResponseTypeDef,
     UpdateApnsSandboxChannelRequestRequestTypeDef,
+    DeleteApnsSandboxChannelResponseTypeDef,
+    GetApnsSandboxChannelResponseTypeDef,
+    UpdateApnsSandboxChannelResponseTypeDef,
     UpdateApnsVoipChannelRequestRequestTypeDef,
+    DeleteApnsVoipChannelResponseTypeDef,
+    GetApnsVoipChannelResponseTypeDef,
+    UpdateApnsVoipChannelResponseTypeDef,
     UpdateApnsVoipSandboxChannelRequestRequestTypeDef,
+    DeleteApnsVoipSandboxChannelResponseTypeDef,
+    GetApnsVoipSandboxChannelResponseTypeDef,
+    UpdateApnsVoipSandboxChannelResponseTypeDef,
     ActivitiesResponseTypeDef,
     ApplicationsResponseTypeDef,
+    CreateAppResponseTypeDef,
+    DeleteAppResponseTypeDef,
+    GetAppResponseTypeDef,
     ApplicationSettingsResourceTypeDef,
     WriteApplicationSettingsRequestTypeDef,
+    RemoveAttributesResponseTypeDef,
     UpdateBaiduChannelRequestRequestTypeDef,
+    DeleteBaiduChannelResponseTypeDef,
+    GetBaiduChannelResponseTypeDef,
+    UpdateBaiduChannelResponseTypeDef,
     ChannelsResponseTypeDef,
     ClosedDaysTypeDef,
     WaitActivityTypeDef,
     CreateAppRequestRequestTypeDef,
-    CreateAppResponseTypeDef,
-    DeleteAdmChannelResponseTypeDef,
-    DeleteApnsChannelResponseTypeDef,
-    DeleteApnsSandboxChannelResponseTypeDef,
-    DeleteApnsVoipChannelResponseTypeDef,
-    DeleteApnsVoipSandboxChannelResponseTypeDef,
-    DeleteAppResponseTypeDef,
-    DeleteBaiduChannelResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetAdmChannelResponseTypeDef,
-    GetApnsChannelResponseTypeDef,
-    GetApnsSandboxChannelResponseTypeDef,
-    GetApnsVoipChannelResponseTypeDef,
-    GetApnsVoipSandboxChannelResponseTypeDef,
-    GetAppResponseTypeDef,
-    GetBaiduChannelResponseTypeDef,
-    RemoveAttributesResponseTypeDef,
-    UpdateAdmChannelResponseTypeDef,
-    UpdateApnsChannelResponseTypeDef,
-    UpdateApnsSandboxChannelResponseTypeDef,
-    UpdateApnsVoipChannelResponseTypeDef,
-    UpdateApnsVoipSandboxChannelResponseTypeDef,
-    UpdateBaiduChannelResponseTypeDef,
     CreateEmailTemplateRequestRequestTypeDef,
     UpdateEmailTemplateRequestRequestTypeDef,
     CreateEmailTemplateResponseTypeDef,
     CreatePushTemplateResponseTypeDef,
     CreateSmsTemplateResponseTypeDef,
     CreateVoiceTemplateResponseTypeDef,
     CreateExportJobRequestRequestTypeDef,
@@ -575,19 +583,22 @@
     ItemResponseTypeDef,
     EventTypeDef,
     ExportJobResponseTypeDef,
     UpdateGcmChannelRequestRequestTypeDef,
     GPSPointDimensionTypeDef,
     GetJourneyExecutionActivityMetricsResponseTypeDef,
     GetJourneyExecutionMetricsResponseTypeDef,
+    GetJourneyRunExecutionActivityMetricsResponseTypeDef,
+    GetJourneyRunExecutionMetricsResponseTypeDef,
     GetSmsTemplateResponseTypeDef,
     GetVoiceTemplateResponseTypeDef,
     ImportJobResponseTypeDef,
     InAppMessageButtonTypeDef,
     PushMessageActivityTypeDef,
+    JourneyRunsResponseTypeDef,
     SMSMessageActivityTypeDef,
     UpdateJourneyStateRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     MessageResponseTypeDef,
     PhoneNumberValidateRequestRequestTypeDef,
     PhoneNumberValidateResponseTypeDef,
@@ -633,14 +644,15 @@
     ExportJobsResponseTypeDef,
     GetExportJobResponseTypeDef,
     SegmentLocationTypeDef,
     CreateImportJobResponseTypeDef,
     GetImportJobResponseTypeDef,
     ImportJobsResponseTypeDef,
     InAppMessageContentTypeDef,
+    GetJourneyRunsResponseTypeDef,
     SendMessagesResponseTypeDef,
     SendOTPMessageResponseTypeDef,
     BaseKpiResultTypeDef,
     EmailMessageTypeDef,
     ListTemplatesResponseTypeDef,
     ListTemplateVersionsResponseTypeDef,
     UpdateEndpointsBatchRequestRequestTypeDef,
@@ -735,43 +747,43 @@
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

### Comparing `types-aiobotocore-pinpoint-2.5.0.post1/setup.py` & `types-aiobotocore-pinpoint-2.5.1/setup.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-pinpoint.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-pinpoint",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_pinpoint"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Pinpoint 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.Pinpoint 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint/"
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

### Comparing `types-aiobotocore-pinpoint-2.5.0.post1/types_aiobotocore_pinpoint/__main__.py` & `types-aiobotocore-pinpoint-2.5.1/types_aiobotocore_pinpoint/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Pinpoint 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Pinpoint 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint.html#Pinpoint\nOther"
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

### Comparing `types-aiobotocore-pinpoint-2.5.0.post1/types_aiobotocore_pinpoint/client.py` & `types-aiobotocore-pinpoint-2.5.1/types_aiobotocore_pinpoint/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -100,14 +100,17 @@
     GetImportJobsResponseTypeDef,
     GetInAppMessagesResponseTypeDef,
     GetInAppTemplateResponseTypeDef,
     GetJourneyDateRangeKpiResponseTypeDef,
     GetJourneyExecutionActivityMetricsResponseTypeDef,
     GetJourneyExecutionMetricsResponseTypeDef,
     GetJourneyResponseTypeDef,
+    GetJourneyRunExecutionActivityMetricsResponseTypeDef,
+    GetJourneyRunExecutionMetricsResponseTypeDef,
+    GetJourneyRunsResponseTypeDef,
     GetPushTemplateResponseTypeDef,
     GetRecommenderConfigurationResponseTypeDef,
     GetRecommenderConfigurationsResponseTypeDef,
     GetSegmentExportJobsResponseTypeDef,
     GetSegmentImportJobsResponseTypeDef,
     GetSegmentResponseTypeDef,
     GetSegmentsResponseTypeDef,
@@ -958,14 +961,59 @@
         Retrieves (queries) pre-aggregated data for a standard execution metric that
         applies to a journey.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint.html#Pinpoint.Client.get_journey_execution_metrics)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint/client/#get_journey_execution_metrics)
         """
 
+    async def get_journey_run_execution_activity_metrics(
+        self,
+        *,
+        ApplicationId: str,
+        JourneyActivityId: str,
+        JourneyId: str,
+        RunId: str,
+        NextToken: str = ...,
+        PageSize: str = ...
+    ) -> GetJourneyRunExecutionActivityMetricsResponseTypeDef:
+        """
+        Retrieves (queries) pre-aggregated data for a standard run execution metric that
+        applies to a journey activity.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint.html#Pinpoint.Client.get_journey_run_execution_activity_metrics)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint/client/#get_journey_run_execution_activity_metrics)
+        """
+
+    async def get_journey_run_execution_metrics(
+        self,
+        *,
+        ApplicationId: str,
+        JourneyId: str,
+        RunId: str,
+        NextToken: str = ...,
+        PageSize: str = ...
+    ) -> GetJourneyRunExecutionMetricsResponseTypeDef:
+        """
+        Retrieves (queries) pre-aggregated data for a standard run execution metric that
+        applies to a journey.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint.html#Pinpoint.Client.get_journey_run_execution_metrics)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint/client/#get_journey_run_execution_metrics)
+        """
+
+    async def get_journey_runs(
+        self, *, ApplicationId: str, JourneyId: str, PageSize: str = ..., Token: str = ...
+    ) -> GetJourneyRunsResponseTypeDef:
+        """
+        Provides information about the runs of a journey.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint.html#Pinpoint.Client.get_journey_runs)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint/client/#get_journey_runs)
+        """
+
     async def get_push_template(
         self, *, TemplateName: str, Version: str = ...
     ) -> GetPushTemplateResponseTypeDef:
         """
         Retrieves the content and settings of a message template for messages that are
         sent through a push notification channel.
 
@@ -1525,15 +1573,15 @@
         self,
         *,
         TemplateActiveVersionRequest: TemplateActiveVersionRequestTypeDef,
         TemplateName: str,
         TemplateType: str
     ) -> UpdateTemplateActiveVersionResponseTypeDef:
         """
-        Changes the status of a specific version of a message template to *active* .
+        Changes the status of a specific version of a message template to *active*.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint.html#Pinpoint.Client.update_template_active_version)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint/client/#update_template_active_version)
         """
 
     async def update_voice_channel(
         self, *, ApplicationId: str, VoiceChannelRequest: VoiceChannelRequestTypeDef
```

### Comparing `types-aiobotocore-pinpoint-2.5.0.post1/types_aiobotocore_pinpoint/client.pyi` & `types-aiobotocore-pinpoint-2.5.1/types_aiobotocore_pinpoint/client.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -100,14 +100,17 @@
     GetImportJobsResponseTypeDef,
     GetInAppMessagesResponseTypeDef,
     GetInAppTemplateResponseTypeDef,
     GetJourneyDateRangeKpiResponseTypeDef,
     GetJourneyExecutionActivityMetricsResponseTypeDef,
     GetJourneyExecutionMetricsResponseTypeDef,
     GetJourneyResponseTypeDef,
+    GetJourneyRunExecutionActivityMetricsResponseTypeDef,
+    GetJourneyRunExecutionMetricsResponseTypeDef,
+    GetJourneyRunsResponseTypeDef,
     GetPushTemplateResponseTypeDef,
     GetRecommenderConfigurationResponseTypeDef,
     GetRecommenderConfigurationsResponseTypeDef,
     GetSegmentExportJobsResponseTypeDef,
     GetSegmentImportJobsResponseTypeDef,
     GetSegmentResponseTypeDef,
     GetSegmentsResponseTypeDef,
@@ -884,14 +887,56 @@
         """
         Retrieves (queries) pre-aggregated data for a standard execution metric that
         applies to a journey.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint.html#Pinpoint.Client.get_journey_execution_metrics)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint/client/#get_journey_execution_metrics)
         """
+    async def get_journey_run_execution_activity_metrics(
+        self,
+        *,
+        ApplicationId: str,
+        JourneyActivityId: str,
+        JourneyId: str,
+        RunId: str,
+        NextToken: str = ...,
+        PageSize: str = ...
+    ) -> GetJourneyRunExecutionActivityMetricsResponseTypeDef:
+        """
+        Retrieves (queries) pre-aggregated data for a standard run execution metric that
+        applies to a journey activity.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint.html#Pinpoint.Client.get_journey_run_execution_activity_metrics)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint/client/#get_journey_run_execution_activity_metrics)
+        """
+    async def get_journey_run_execution_metrics(
+        self,
+        *,
+        ApplicationId: str,
+        JourneyId: str,
+        RunId: str,
+        NextToken: str = ...,
+        PageSize: str = ...
+    ) -> GetJourneyRunExecutionMetricsResponseTypeDef:
+        """
+        Retrieves (queries) pre-aggregated data for a standard run execution metric that
+        applies to a journey.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint.html#Pinpoint.Client.get_journey_run_execution_metrics)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint/client/#get_journey_run_execution_metrics)
+        """
+    async def get_journey_runs(
+        self, *, ApplicationId: str, JourneyId: str, PageSize: str = ..., Token: str = ...
+    ) -> GetJourneyRunsResponseTypeDef:
+        """
+        Provides information about the runs of a journey.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint.html#Pinpoint.Client.get_journey_runs)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint/client/#get_journey_runs)
+        """
     async def get_push_template(
         self, *, TemplateName: str, Version: str = ...
     ) -> GetPushTemplateResponseTypeDef:
         """
         Retrieves the content and settings of a message template for messages that are
         sent through a push notification channel.
 
@@ -1403,15 +1448,15 @@
         self,
         *,
         TemplateActiveVersionRequest: TemplateActiveVersionRequestTypeDef,
         TemplateName: str,
         TemplateType: str
     ) -> UpdateTemplateActiveVersionResponseTypeDef:
         """
-        Changes the status of a specific version of a message template to *active* .
+        Changes the status of a specific version of a message template to *active*.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint.html#Pinpoint.Client.update_template_active_version)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint/client/#update_template_active_version)
         """
     async def update_voice_channel(
         self, *, ApplicationId: str, VoiceChannelRequest: VoiceChannelRequestTypeDef
     ) -> UpdateVoiceChannelResponseTypeDef:
```

### Comparing `types-aiobotocore-pinpoint-2.5.0.post1/types_aiobotocore_pinpoint/literals.py` & `types-aiobotocore-pinpoint-2.5.1/types_aiobotocore_pinpoint/literals.py`

 * *Files 6% similar despite different names*

```diff
@@ -32,23 +32,25 @@
     "DurationType",
     "EndpointTypesElementType",
     "FilterTypeType",
     "FormatType",
     "FrequencyType",
     "IncludeType",
     "JobStatusType",
+    "JourneyRunStatusType",
     "LayoutType",
     "MessageTypeType",
     "ModeType",
     "OperatorType",
     "RecencyTypeType",
     "SegmentTypeType",
     "SourceTypeType",
     "StateType",
     "TemplateTypeType",
+    "TimezoneEstimationMethodsElementType",
     "TypeType",
     "PinpointServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
@@ -117,25 +119,27 @@
     "FAILED",
     "FAILING",
     "INITIALIZING",
     "PENDING_JOB",
     "PREPARING_FOR_INITIALIZATION",
     "PROCESSING",
 ]
+JourneyRunStatusType = Literal["CANCELLED", "COMPLETED", "RUNNING", "SCHEDULED"]
 LayoutType = Literal[
     "BOTTOM_BANNER", "CAROUSEL", "MIDDLE_BANNER", "MOBILE_FEED", "OVERLAYS", "TOP_BANNER"
 ]
 MessageTypeType = Literal["PROMOTIONAL", "TRANSACTIONAL"]
 ModeType = Literal["DELIVERY", "FILTER"]
 OperatorType = Literal["ALL", "ANY"]
 RecencyTypeType = Literal["ACTIVE", "INACTIVE"]
 SegmentTypeType = Literal["DIMENSIONAL", "IMPORT"]
 SourceTypeType = Literal["ALL", "ANY", "NONE"]
 StateType = Literal["ACTIVE", "CANCELLED", "CLOSED", "COMPLETED", "DRAFT", "PAUSED"]
 TemplateTypeType = Literal["EMAIL", "INAPP", "PUSH", "SMS", "VOICE"]
+TimezoneEstimationMethodsElementType = Literal["PHONE_NUMBER", "POSTAL_CODE"]
 TypeType = Literal["ALL", "ANY", "NONE"]
 PinpointServiceName = Literal["pinpoint"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
@@ -192,14 +196,15 @@
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
@@ -278,14 +283,15 @@
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
@@ -296,14 +302,15 @@
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
@@ -339,14 +346,15 @@
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
@@ -365,16 +373,19 @@
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
@@ -458,15 +469,17 @@
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

### Comparing `types-aiobotocore-pinpoint-2.5.0.post1/types_aiobotocore_pinpoint/literals.pyi` & `types-aiobotocore-pinpoint-2.5.1/types_aiobotocore_pinpoint/literals.pyi`

 * *Files 8% similar despite different names*

```diff
@@ -31,23 +31,25 @@
     "DurationType",
     "EndpointTypesElementType",
     "FilterTypeType",
     "FormatType",
     "FrequencyType",
     "IncludeType",
     "JobStatusType",
+    "JourneyRunStatusType",
     "LayoutType",
     "MessageTypeType",
     "ModeType",
     "OperatorType",
     "RecencyTypeType",
     "SegmentTypeType",
     "SourceTypeType",
     "StateType",
     "TemplateTypeType",
+    "TimezoneEstimationMethodsElementType",
     "TypeType",
     "PinpointServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
@@ -115,25 +117,27 @@
     "FAILED",
     "FAILING",
     "INITIALIZING",
     "PENDING_JOB",
     "PREPARING_FOR_INITIALIZATION",
     "PROCESSING",
 ]
+JourneyRunStatusType = Literal["CANCELLED", "COMPLETED", "RUNNING", "SCHEDULED"]
 LayoutType = Literal[
     "BOTTOM_BANNER", "CAROUSEL", "MIDDLE_BANNER", "MOBILE_FEED", "OVERLAYS", "TOP_BANNER"
 ]
 MessageTypeType = Literal["PROMOTIONAL", "TRANSACTIONAL"]
 ModeType = Literal["DELIVERY", "FILTER"]
 OperatorType = Literal["ALL", "ANY"]
 RecencyTypeType = Literal["ACTIVE", "INACTIVE"]
 SegmentTypeType = Literal["DIMENSIONAL", "IMPORT"]
 SourceTypeType = Literal["ALL", "ANY", "NONE"]
 StateType = Literal["ACTIVE", "CANCELLED", "CLOSED", "COMPLETED", "DRAFT", "PAUSED"]
 TemplateTypeType = Literal["EMAIL", "INAPP", "PUSH", "SMS", "VOICE"]
+TimezoneEstimationMethodsElementType = Literal["PHONE_NUMBER", "POSTAL_CODE"]
 TypeType = Literal["ALL", "ANY", "NONE"]
 PinpointServiceName = Literal["pinpoint"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
@@ -190,14 +194,15 @@
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
@@ -276,14 +281,15 @@
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
@@ -294,14 +300,15 @@
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
@@ -337,14 +344,15 @@
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
@@ -363,16 +371,19 @@
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
@@ -456,15 +467,17 @@
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

### Comparing `types-aiobotocore-pinpoint-2.5.0.post1/types_aiobotocore_pinpoint/type_defs.py` & `types-aiobotocore-pinpoint-2.5.1/types_aiobotocore_pinpoint/type_defs.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -30,32 +30,33 @@
     DurationType,
     EndpointTypesElementType,
     FilterTypeType,
     FormatType,
     FrequencyType,
     IncludeType,
     JobStatusType,
+    JourneyRunStatusType,
     LayoutType,
     MessageTypeType,
     ModeType,
     OperatorType,
     RecencyTypeType,
     SegmentTypeType,
     SourceTypeType,
     StateType,
     TemplateTypeType,
+    TimezoneEstimationMethodsElementType,
     TypeType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "ADMChannelRequestTypeDef",
     "ADMChannelResponseTypeDef",
     "ADMMessageTypeDef",
     "APNSChannelRequestTypeDef",
     "APNSChannelResponseTypeDef",
     "APNSMessageTypeDef",
@@ -85,15 +86,14 @@
     "CampaignStateTypeDef",
     "CustomDeliveryConfigurationTypeDef",
     "CampaignSmsMessageTypeDef",
     "ChannelResponseTypeDef",
     "ClosedDaysRuleTypeDef",
     "WaitTimeTypeDef",
     "CreateApplicationRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "EmailTemplateRequestTypeDef",
     "CreateTemplateMessageBodyTypeDef",
     "ExportJobRequestTypeDef",
     "ImportJobRequestTypeDef",
     "TemplateCreateMessageBodyTypeDef",
     "CreateRecommenderConfigurationTypeDef",
     "RecommenderConfigurationResponseTypeDef",
@@ -136,14 +136,15 @@
     "GCMMessageTypeDef",
     "SMSMessageTypeDef",
     "VoiceMessageTypeDef",
     "EmailChannelRequestTypeDef",
     "JourneyEmailMessageTypeDef",
     "RawEmailTypeDef",
     "EmailTemplateResponseTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EndpointDemographicTypeDef",
     "EndpointLocationTypeDef",
     "EndpointUserTypeDef",
     "EndpointItemResponseTypeDef",
     "EndpointMessageResultTypeDef",
     "EndpointSendConfigurationTypeDef",
     "MetricDimensionTypeDef",
@@ -183,14 +184,19 @@
     "GetInAppTemplateRequestRequestTypeDef",
     "GetJourneyDateRangeKpiRequestRequestTypeDef",
     "GetJourneyExecutionActivityMetricsRequestRequestTypeDef",
     "JourneyExecutionActivityMetricsResponseTypeDef",
     "GetJourneyExecutionMetricsRequestRequestTypeDef",
     "JourneyExecutionMetricsResponseTypeDef",
     "GetJourneyRequestRequestTypeDef",
+    "GetJourneyRunExecutionActivityMetricsRequestRequestTypeDef",
+    "JourneyRunExecutionActivityMetricsResponseTypeDef",
+    "GetJourneyRunExecutionMetricsRequestRequestTypeDef",
+    "JourneyRunExecutionMetricsResponseTypeDef",
+    "GetJourneyRunsRequestRequestTypeDef",
     "GetPushTemplateRequestRequestTypeDef",
     "GetRecommenderConfigurationRequestRequestTypeDef",
     "GetRecommenderConfigurationsRequestRequestTypeDef",
     "GetSegmentExportJobsRequestRequestTypeDef",
     "GetSegmentImportJobsRequestRequestTypeDef",
     "GetSegmentRequestRequestTypeDef",
     "GetSegmentVersionRequestRequestTypeDef",
@@ -207,14 +213,15 @@
     "InAppMessageBodyConfigTypeDef",
     "OverrideButtonConfigurationTypeDef",
     "InAppMessageHeaderConfigTypeDef",
     "JourneyChannelSettingsTypeDef",
     "JourneyLimitsTypeDef",
     "JourneyPushMessageTypeDef",
     "JourneyScheduleTypeDef",
+    "JourneyRunResponseTypeDef",
     "JourneySMSMessageTypeDef",
     "JourneyStateRequestTypeDef",
     "ListJourneysRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "TagsModelTypeDef",
     "ListTemplateVersionsRequestRequestTypeDef",
     "ListTemplatesRequestRequestTypeDef",
@@ -223,14 +230,15 @@
     "NumberValidateRequestTypeDef",
     "NumberValidateResponseTypeDef",
     "OpenHoursRuleTypeDef",
     "WriteEventStreamTypeDef",
     "RandomSplitEntryTypeDef",
     "RecencyDimensionTypeDef",
     "UpdateAttributesRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "ResultRowValueTypeDef",
     "SMSChannelRequestTypeDef",
     "SegmentConditionTypeDef",
     "SegmentReferenceTypeDef",
     "SegmentImportResourceTypeDef",
     "SendOTPMessageRequestParametersTypeDef",
     "SimpleEmailPartTypeDef",
@@ -240,50 +248,49 @@
     "TemplateVersionResponseTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateRecommenderConfigurationTypeDef",
     "VoiceChannelRequestTypeDef",
     "VerificationResponseTypeDef",
     "VerifyOTPMessageRequestParametersTypeDef",
     "UpdateAdmChannelRequestRequestTypeDef",
+    "DeleteAdmChannelResponseTypeDef",
+    "GetAdmChannelResponseTypeDef",
+    "UpdateAdmChannelResponseTypeDef",
     "UpdateApnsChannelRequestRequestTypeDef",
+    "DeleteApnsChannelResponseTypeDef",
+    "GetApnsChannelResponseTypeDef",
+    "UpdateApnsChannelResponseTypeDef",
     "UpdateApnsSandboxChannelRequestRequestTypeDef",
+    "DeleteApnsSandboxChannelResponseTypeDef",
+    "GetApnsSandboxChannelResponseTypeDef",
+    "UpdateApnsSandboxChannelResponseTypeDef",
     "UpdateApnsVoipChannelRequestRequestTypeDef",
+    "DeleteApnsVoipChannelResponseTypeDef",
+    "GetApnsVoipChannelResponseTypeDef",
+    "UpdateApnsVoipChannelResponseTypeDef",
     "UpdateApnsVoipSandboxChannelRequestRequestTypeDef",
+    "DeleteApnsVoipSandboxChannelResponseTypeDef",
+    "GetApnsVoipSandboxChannelResponseTypeDef",
+    "UpdateApnsVoipSandboxChannelResponseTypeDef",
     "ActivitiesResponseTypeDef",
     "ApplicationsResponseTypeDef",
+    "CreateAppResponseTypeDef",
+    "DeleteAppResponseTypeDef",
+    "GetAppResponseTypeDef",
     "ApplicationSettingsResourceTypeDef",
     "WriteApplicationSettingsRequestTypeDef",
+    "RemoveAttributesResponseTypeDef",
     "UpdateBaiduChannelRequestRequestTypeDef",
+    "DeleteBaiduChannelResponseTypeDef",
+    "GetBaiduChannelResponseTypeDef",
+    "UpdateBaiduChannelResponseTypeDef",
     "ChannelsResponseTypeDef",
     "ClosedDaysTypeDef",
     "WaitActivityTypeDef",
     "CreateAppRequestRequestTypeDef",
-    "CreateAppResponseTypeDef",
-    "DeleteAdmChannelResponseTypeDef",
-    "DeleteApnsChannelResponseTypeDef",
-    "DeleteApnsSandboxChannelResponseTypeDef",
-    "DeleteApnsVoipChannelResponseTypeDef",
-    "DeleteApnsVoipSandboxChannelResponseTypeDef",
-    "DeleteAppResponseTypeDef",
-    "DeleteBaiduChannelResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetAdmChannelResponseTypeDef",
-    "GetApnsChannelResponseTypeDef",
-    "GetApnsSandboxChannelResponseTypeDef",
-    "GetApnsVoipChannelResponseTypeDef",
-    "GetApnsVoipSandboxChannelResponseTypeDef",
-    "GetAppResponseTypeDef",
-    "GetBaiduChannelResponseTypeDef",
-    "RemoveAttributesResponseTypeDef",
-    "UpdateAdmChannelResponseTypeDef",
-    "UpdateApnsChannelResponseTypeDef",
-    "UpdateApnsSandboxChannelResponseTypeDef",
-    "UpdateApnsVoipChannelResponseTypeDef",
-    "UpdateApnsVoipSandboxChannelResponseTypeDef",
-    "UpdateBaiduChannelResponseTypeDef",
     "CreateEmailTemplateRequestRequestTypeDef",
     "UpdateEmailTemplateRequestRequestTypeDef",
     "CreateEmailTemplateResponseTypeDef",
     "CreatePushTemplateResponseTypeDef",
     "CreateSmsTemplateResponseTypeDef",
     "CreateVoiceTemplateResponseTypeDef",
     "CreateExportJobRequestRequestTypeDef",
@@ -343,19 +350,22 @@
     "ItemResponseTypeDef",
     "EventTypeDef",
     "ExportJobResponseTypeDef",
     "UpdateGcmChannelRequestRequestTypeDef",
     "GPSPointDimensionTypeDef",
     "GetJourneyExecutionActivityMetricsResponseTypeDef",
     "GetJourneyExecutionMetricsResponseTypeDef",
+    "GetJourneyRunExecutionActivityMetricsResponseTypeDef",
+    "GetJourneyRunExecutionMetricsResponseTypeDef",
     "GetSmsTemplateResponseTypeDef",
     "GetVoiceTemplateResponseTypeDef",
     "ImportJobResponseTypeDef",
     "InAppMessageButtonTypeDef",
     "PushMessageActivityTypeDef",
+    "JourneyRunsResponseTypeDef",
     "SMSMessageActivityTypeDef",
     "UpdateJourneyStateRequestRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "MessageResponseTypeDef",
     "PhoneNumberValidateRequestRequestTypeDef",
     "PhoneNumberValidateResponseTypeDef",
@@ -401,14 +411,15 @@
     "ExportJobsResponseTypeDef",
     "GetExportJobResponseTypeDef",
     "SegmentLocationTypeDef",
     "CreateImportJobResponseTypeDef",
     "GetImportJobResponseTypeDef",
     "ImportJobsResponseTypeDef",
     "InAppMessageContentTypeDef",
+    "GetJourneyRunsResponseTypeDef",
     "SendMessagesResponseTypeDef",
     "SendOTPMessageResponseTypeDef",
     "BaseKpiResultTypeDef",
     "EmailMessageTypeDef",
     "ListTemplatesResponseTypeDef",
     "ListTemplateVersionsResponseTypeDef",
     "UpdateEndpointsBatchRequestRequestTypeDef",
@@ -506,21 +517,19 @@
     "_OptionalADMChannelRequestTypeDef",
     {
         "Enabled": bool,
     },
     total=False,
 )
 
-
 class ADMChannelRequestTypeDef(
     _RequiredADMChannelRequestTypeDef, _OptionalADMChannelRequestTypeDef
 ):
     pass
 
-
 _RequiredADMChannelResponseTypeDef = TypedDict(
     "_RequiredADMChannelResponseTypeDef",
     {
         "Platform": str,
     },
 )
 _OptionalADMChannelResponseTypeDef = TypedDict(
@@ -535,21 +544,19 @@
         "LastModifiedBy": str,
         "LastModifiedDate": str,
         "Version": int,
     },
     total=False,
 )
 
-
 class ADMChannelResponseTypeDef(
     _RequiredADMChannelResponseTypeDef, _OptionalADMChannelResponseTypeDef
 ):
     pass
 
-
 ADMMessageTypeDef = TypedDict(
     "ADMMessageTypeDef",
     {
         "Action": ActionType,
         "Body": str,
         "ConsolidationKey": str,
         "Data": Mapping[str, str],
@@ -604,21 +611,19 @@
         "LastModifiedBy": str,
         "LastModifiedDate": str,
         "Version": int,
     },
     total=False,
 )
 
-
 class APNSChannelResponseTypeDef(
     _RequiredAPNSChannelResponseTypeDef, _OptionalAPNSChannelResponseTypeDef
 ):
     pass
 
-
 APNSMessageTypeDef = TypedDict(
     "APNSMessageTypeDef",
     {
         "APNSPushType": str,
         "Action": ActionType,
         "Badge": int,
         "Body": str,
@@ -689,21 +694,19 @@
         "LastModifiedBy": str,
         "LastModifiedDate": str,
         "Version": int,
     },
     total=False,
 )
 
-
 class APNSSandboxChannelResponseTypeDef(
     _RequiredAPNSSandboxChannelResponseTypeDef, _OptionalAPNSSandboxChannelResponseTypeDef
 ):
     pass
 
-
 APNSVoipChannelRequestTypeDef = TypedDict(
     "APNSVoipChannelRequestTypeDef",
     {
         "BundleId": str,
         "Certificate": str,
         "DefaultAuthenticationMethod": str,
         "Enabled": bool,
@@ -735,21 +738,19 @@
         "LastModifiedBy": str,
         "LastModifiedDate": str,
         "Version": int,
     },
     total=False,
 )
 
-
 class APNSVoipChannelResponseTypeDef(
     _RequiredAPNSVoipChannelResponseTypeDef, _OptionalAPNSVoipChannelResponseTypeDef
 ):
     pass
 
-
 APNSVoipSandboxChannelRequestTypeDef = TypedDict(
     "APNSVoipSandboxChannelRequestTypeDef",
     {
         "BundleId": str,
         "Certificate": str,
         "DefaultAuthenticationMethod": str,
         "Enabled": bool,
@@ -781,21 +782,19 @@
         "LastModifiedBy": str,
         "LastModifiedDate": str,
         "Version": int,
     },
     total=False,
 )
 
-
 class APNSVoipSandboxChannelResponseTypeDef(
     _RequiredAPNSVoipSandboxChannelResponseTypeDef, _OptionalAPNSVoipSandboxChannelResponseTypeDef
 ):
     pass
 
-
 _RequiredActivityResponseTypeDef = TypedDict(
     "_RequiredActivityResponseTypeDef",
     {
         "ApplicationId": str,
         "CampaignId": str,
         "Id": str,
     },
@@ -809,23 +808,22 @@
         "Start": str,
         "State": str,
         "SuccessfulEndpointCount": int,
         "TimezonesCompletedCount": int,
         "TimezonesTotalCount": int,
         "TotalEndpointCount": int,
         "TreatmentId": str,
+        "ExecutionMetrics": Dict[str, str],
     },
     total=False,
 )
 
-
 class ActivityResponseTypeDef(_RequiredActivityResponseTypeDef, _OptionalActivityResponseTypeDef):
     pass
 
-
 ContactCenterActivityTypeDef = TypedDict(
     "ContactCenterActivityTypeDef",
     {
         "NextActivity": str,
     },
     total=False,
 )
@@ -840,19 +838,17 @@
     "_OptionalHoldoutActivityTypeDef",
     {
         "NextActivity": str,
     },
     total=False,
 )
 
-
 class HoldoutActivityTypeDef(_RequiredHoldoutActivityTypeDef, _OptionalHoldoutActivityTypeDef):
     pass
 
-
 AddressConfigurationTypeDef = TypedDict(
     "AddressConfigurationTypeDef",
     {
         "BodyOverride": str,
         "ChannelType": ChannelTypeType,
         "Context": Mapping[str, str],
         "RawContent": str,
@@ -891,21 +887,19 @@
     {
         "tags": Dict[str, str],
         "CreationDate": str,
     },
     total=False,
 )
 
-
 class ApplicationResponseTypeDef(
     _RequiredApplicationResponseTypeDef, _OptionalApplicationResponseTypeDef
 ):
     pass
 
-
 CampaignHookTypeDef = TypedDict(
     "CampaignHookTypeDef",
     {
         "LambdaFunctionName": str,
         "Mode": ModeType,
         "WebUrl": str,
     },
@@ -943,21 +937,19 @@
     "_OptionalAttributeDimensionTypeDef",
     {
         "AttributeType": AttributeTypeType,
     },
     total=False,
 )
 
-
 class AttributeDimensionTypeDef(
     _RequiredAttributeDimensionTypeDef, _OptionalAttributeDimensionTypeDef
 ):
     pass
 
-
 _RequiredAttributesResourceTypeDef = TypedDict(
     "_RequiredAttributesResourceTypeDef",
     {
         "ApplicationId": str,
         "AttributeType": str,
     },
 )
@@ -965,21 +957,19 @@
     "_OptionalAttributesResourceTypeDef",
     {
         "Attributes": List[str],
     },
     total=False,
 )
 
-
 class AttributesResourceTypeDef(
     _RequiredAttributesResourceTypeDef, _OptionalAttributesResourceTypeDef
 ):
     pass
 
-
 _RequiredBaiduChannelRequestTypeDef = TypedDict(
     "_RequiredBaiduChannelRequestTypeDef",
     {
         "ApiKey": str,
         "SecretKey": str,
     },
 )
@@ -987,21 +977,19 @@
     "_OptionalBaiduChannelRequestTypeDef",
     {
         "Enabled": bool,
     },
     total=False,
 )
 
-
 class BaiduChannelRequestTypeDef(
     _RequiredBaiduChannelRequestTypeDef, _OptionalBaiduChannelRequestTypeDef
 ):
     pass
 
-
 _RequiredBaiduChannelResponseTypeDef = TypedDict(
     "_RequiredBaiduChannelResponseTypeDef",
     {
         "Credential": str,
         "Platform": str,
     },
 )
@@ -1017,21 +1005,19 @@
         "LastModifiedBy": str,
         "LastModifiedDate": str,
         "Version": int,
     },
     total=False,
 )
 
-
 class BaiduChannelResponseTypeDef(
     _RequiredBaiduChannelResponseTypeDef, _OptionalBaiduChannelResponseTypeDef
 ):
     pass
 
-
 BaiduMessageTypeDef = TypedDict(
     "BaiduMessageTypeDef",
     {
         "Action": ActionType,
         "Body": str,
         "Data": Mapping[str, str],
         "IconReference": str,
@@ -1086,21 +1072,19 @@
     "_OptionalCustomDeliveryConfigurationTypeDef",
     {
         "EndpointTypes": Sequence[EndpointTypesElementType],
     },
     total=False,
 )
 
-
 class CustomDeliveryConfigurationTypeDef(
     _RequiredCustomDeliveryConfigurationTypeDef, _OptionalCustomDeliveryConfigurationTypeDef
 ):
     pass
 
-
 CampaignSmsMessageTypeDef = TypedDict(
     "CampaignSmsMessageTypeDef",
     {
         "Body": str,
         "MessageType": MessageTypeType,
         "OriginationNumber": str,
         "SenderId": str,
@@ -1155,32 +1139,19 @@
     "_OptionalCreateApplicationRequestTypeDef",
     {
         "tags": Mapping[str, str],
     },
     total=False,
 )
 
-
 class CreateApplicationRequestTypeDef(
     _RequiredCreateApplicationRequestTypeDef, _OptionalCreateApplicationRequestTypeDef
 ):
     pass
 
-
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
 EmailTemplateRequestTypeDef = TypedDict(
     "EmailTemplateRequestTypeDef",
     {
         "DefaultSubstitutions": str,
         "HtmlPart": str,
         "RecommenderId": str,
         "Subject": str,
@@ -1213,19 +1184,17 @@
     {
         "SegmentId": str,
         "SegmentVersion": int,
     },
     total=False,
 )
 
-
 class ExportJobRequestTypeDef(_RequiredExportJobRequestTypeDef, _OptionalExportJobRequestTypeDef):
     pass
 
-
 _RequiredImportJobRequestTypeDef = TypedDict(
     "_RequiredImportJobRequestTypeDef",
     {
         "Format": FormatType,
         "RoleArn": str,
         "S3Url": str,
     },
@@ -1238,19 +1207,17 @@
         "RegisterEndpoints": bool,
         "SegmentId": str,
         "SegmentName": str,
     },
     total=False,
 )
 
-
 class ImportJobRequestTypeDef(_RequiredImportJobRequestTypeDef, _OptionalImportJobRequestTypeDef):
     pass
 
-
 TemplateCreateMessageBodyTypeDef = TypedDict(
     "TemplateCreateMessageBodyTypeDef",
     {
         "Arn": str,
         "Message": str,
         "RequestID": str,
     },
@@ -1274,21 +1241,19 @@
         "RecommendationTransformerUri": str,
         "RecommendationsDisplayName": str,
         "RecommendationsPerMessage": int,
     },
     total=False,
 )
 
-
 class CreateRecommenderConfigurationTypeDef(
     _RequiredCreateRecommenderConfigurationTypeDef, _OptionalCreateRecommenderConfigurationTypeDef
 ):
     pass
 
-
 _RequiredRecommenderConfigurationResponseTypeDef = TypedDict(
     "_RequiredRecommenderConfigurationResponseTypeDef",
     {
         "CreationDate": str,
         "Id": str,
         "LastModifiedDate": str,
         "RecommendationProviderRoleArn": str,
@@ -1305,22 +1270,20 @@
         "RecommendationTransformerUri": str,
         "RecommendationsDisplayName": str,
         "RecommendationsPerMessage": int,
     },
     total=False,
 )
 
-
 class RecommenderConfigurationResponseTypeDef(
     _RequiredRecommenderConfigurationResponseTypeDef,
     _OptionalRecommenderConfigurationResponseTypeDef,
 ):
     pass
 
-
 SMSTemplateRequestTypeDef = TypedDict(
     "SMSTemplateRequestTypeDef",
     {
         "Body": str,
         "DefaultSubstitutions": str,
         "RecommenderId": str,
         "tags": Mapping[str, str],
@@ -1364,21 +1327,19 @@
         "BorderRadius": int,
         "Link": str,
         "TextColor": str,
     },
     total=False,
 )
 
-
 class DefaultButtonConfigurationTypeDef(
     _RequiredDefaultButtonConfigurationTypeDef, _OptionalDefaultButtonConfigurationTypeDef
 ):
     pass
 
-
 DefaultMessageTypeDef = TypedDict(
     "DefaultMessageTypeDef",
     {
         "Body": str,
         "Substitutions": Mapping[str, Sequence[str]],
     },
     total=False,
@@ -1497,43 +1458,39 @@
         "MessagesPerSecond": int,
         "RoleArn": str,
         "Version": int,
     },
     total=False,
 )
 
-
 class EmailChannelResponseTypeDef(
     _RequiredEmailChannelResponseTypeDef, _OptionalEmailChannelResponseTypeDef
 ):
     pass
 
-
 _RequiredDeleteEmailTemplateRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteEmailTemplateRequestRequestTypeDef",
     {
         "TemplateName": str,
     },
 )
 _OptionalDeleteEmailTemplateRequestRequestTypeDef = TypedDict(
     "_OptionalDeleteEmailTemplateRequestRequestTypeDef",
     {
         "Version": str,
     },
     total=False,
 )
 
-
 class DeleteEmailTemplateRequestRequestTypeDef(
     _RequiredDeleteEmailTemplateRequestRequestTypeDef,
     _OptionalDeleteEmailTemplateRequestRequestTypeDef,
 ):
     pass
 
-
 MessageBodyTypeDef = TypedDict(
     "MessageBodyTypeDef",
     {
         "Message": str,
         "RequestID": str,
     },
     total=False,
@@ -1568,19 +1525,17 @@
         "ExternalId": str,
         "LastModifiedDate": str,
         "LastUpdatedBy": str,
     },
     total=False,
 )
 
-
 class EventStreamTypeDef(_RequiredEventStreamTypeDef, _OptionalEventStreamTypeDef):
     pass
 
-
 DeleteGcmChannelRequestRequestTypeDef = TypedDict(
     "DeleteGcmChannelRequestRequestTypeDef",
     {
         "ApplicationId": str,
     },
 )
 
@@ -1603,43 +1558,39 @@
         "LastModifiedBy": str,
         "LastModifiedDate": str,
         "Version": int,
     },
     total=False,
 )
 
-
 class GCMChannelResponseTypeDef(
     _RequiredGCMChannelResponseTypeDef, _OptionalGCMChannelResponseTypeDef
 ):
     pass
 
-
 _RequiredDeleteInAppTemplateRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteInAppTemplateRequestRequestTypeDef",
     {
         "TemplateName": str,
     },
 )
 _OptionalDeleteInAppTemplateRequestRequestTypeDef = TypedDict(
     "_OptionalDeleteInAppTemplateRequestRequestTypeDef",
     {
         "Version": str,
     },
     total=False,
 )
 
-
 class DeleteInAppTemplateRequestRequestTypeDef(
     _RequiredDeleteInAppTemplateRequestRequestTypeDef,
     _OptionalDeleteInAppTemplateRequestRequestTypeDef,
 ):
     pass
 
-
 DeleteJourneyRequestRequestTypeDef = TypedDict(
     "DeleteJourneyRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "JourneyId": str,
     },
 )
@@ -1654,22 +1605,20 @@
     "_OptionalDeletePushTemplateRequestRequestTypeDef",
     {
         "Version": str,
     },
     total=False,
 )
 
-
 class DeletePushTemplateRequestRequestTypeDef(
     _RequiredDeletePushTemplateRequestRequestTypeDef,
     _OptionalDeletePushTemplateRequestRequestTypeDef,
 ):
     pass
 
-
 DeleteRecommenderConfigurationRequestRequestTypeDef = TypedDict(
     "DeleteRecommenderConfigurationRequestRequestTypeDef",
     {
         "RecommenderId": str,
     },
 )
 
@@ -1710,42 +1659,38 @@
         "ShortCode": str,
         "TransactionalMessagesPerSecond": int,
         "Version": int,
     },
     total=False,
 )
 
-
 class SMSChannelResponseTypeDef(
     _RequiredSMSChannelResponseTypeDef, _OptionalSMSChannelResponseTypeDef
 ):
     pass
 
-
 _RequiredDeleteSmsTemplateRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteSmsTemplateRequestRequestTypeDef",
     {
         "TemplateName": str,
     },
 )
 _OptionalDeleteSmsTemplateRequestRequestTypeDef = TypedDict(
     "_OptionalDeleteSmsTemplateRequestRequestTypeDef",
     {
         "Version": str,
     },
     total=False,
 )
 
-
 class DeleteSmsTemplateRequestRequestTypeDef(
     _RequiredDeleteSmsTemplateRequestRequestTypeDef, _OptionalDeleteSmsTemplateRequestRequestTypeDef
 ):
     pass
 
-
 DeleteUserEndpointsRequestRequestTypeDef = TypedDict(
     "DeleteUserEndpointsRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "UserId": str,
     },
 )
@@ -1775,43 +1720,39 @@
         "LastModifiedBy": str,
         "LastModifiedDate": str,
         "Version": int,
     },
     total=False,
 )
 
-
 class VoiceChannelResponseTypeDef(
     _RequiredVoiceChannelResponseTypeDef, _OptionalVoiceChannelResponseTypeDef
 ):
     pass
 
-
 _RequiredDeleteVoiceTemplateRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteVoiceTemplateRequestRequestTypeDef",
     {
         "TemplateName": str,
     },
 )
 _OptionalDeleteVoiceTemplateRequestRequestTypeDef = TypedDict(
     "_OptionalDeleteVoiceTemplateRequestRequestTypeDef",
     {
         "Version": str,
     },
     total=False,
 )
 
-
 class DeleteVoiceTemplateRequestRequestTypeDef(
     _RequiredDeleteVoiceTemplateRequestRequestTypeDef,
     _OptionalDeleteVoiceTemplateRequestRequestTypeDef,
 ):
     pass
 
-
 GCMMessageTypeDef = TypedDict(
     "GCMMessageTypeDef",
     {
         "Action": ActionType,
         "Body": str,
         "CollapseKey": str,
         "Data": Mapping[str, str],
@@ -1873,21 +1814,19 @@
         "ConfigurationSet": str,
         "Enabled": bool,
         "RoleArn": str,
     },
     total=False,
 )
 
-
 class EmailChannelRequestTypeDef(
     _RequiredEmailChannelRequestTypeDef, _OptionalEmailChannelRequestTypeDef
 ):
     pass
 
-
 JourneyEmailMessageTypeDef = TypedDict(
     "JourneyEmailMessageTypeDef",
     {
         "FromAddress": str,
     },
     total=False,
 )
@@ -1921,20 +1860,25 @@
         "TemplateDescription": str,
         "TextPart": str,
         "Version": str,
     },
     total=False,
 )
 
-
 class EmailTemplateResponseTypeDef(
     _RequiredEmailTemplateResponseTypeDef, _OptionalEmailTemplateResponseTypeDef
 ):
     pass
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 EndpointDemographicTypeDef = TypedDict(
     "EndpointDemographicTypeDef",
     {
         "AppVersion": str,
         "Locale": str,
         "Make": str,
@@ -1992,21 +1936,19 @@
         "MessageId": str,
         "StatusMessage": str,
         "UpdatedToken": str,
     },
     total=False,
 )
 
-
 class EndpointMessageResultTypeDef(
     _RequiredEndpointMessageResultTypeDef, _OptionalEndpointMessageResultTypeDef
 ):
     pass
 
-
 EndpointSendConfigurationTypeDef = TypedDict(
     "EndpointSendConfigurationTypeDef",
     {
         "BodyOverride": str,
         "Context": Mapping[str, str],
         "RawContent": str,
         "Substitutions": Mapping[str, Sequence[str]],
@@ -2033,19 +1975,17 @@
     "_OptionalSetDimensionTypeDef",
     {
         "DimensionType": DimensionTypeType,
     },
     total=False,
 )
 
-
 class SetDimensionTypeDef(_RequiredSetDimensionTypeDef, _OptionalSetDimensionTypeDef):
     pass
 
-
 EventItemResponseTypeDef = TypedDict(
     "EventItemResponseTypeDef",
     {
         "Message": str,
         "StatusCode": int,
     },
     total=False,
@@ -2063,19 +2003,17 @@
     {
         "Duration": int,
         "StopTimestamp": str,
     },
     total=False,
 )
 
-
 class SessionTypeDef(_RequiredSessionTypeDef, _OptionalSessionTypeDef):
     pass
 
-
 _RequiredExportJobResourceTypeDef = TypedDict(
     "_RequiredExportJobResourceTypeDef",
     {
         "RoleArn": str,
         "S3UrlPrefix": str,
     },
 )
@@ -2084,42 +2022,38 @@
     {
         "SegmentId": str,
         "SegmentVersion": int,
     },
     total=False,
 )
 
-
 class ExportJobResourceTypeDef(
     _RequiredExportJobResourceTypeDef, _OptionalExportJobResourceTypeDef
 ):
     pass
 
-
 _RequiredGCMChannelRequestTypeDef = TypedDict(
     "_RequiredGCMChannelRequestTypeDef",
     {
         "ApiKey": str,
     },
 )
 _OptionalGCMChannelRequestTypeDef = TypedDict(
     "_OptionalGCMChannelRequestTypeDef",
     {
         "Enabled": bool,
     },
     total=False,
 )
 
-
 class GCMChannelRequestTypeDef(
     _RequiredGCMChannelRequestTypeDef, _OptionalGCMChannelRequestTypeDef
 ):
     pass
 
-
 GPSCoordinatesTypeDef = TypedDict(
     "GPSCoordinatesTypeDef",
     {
         "Latitude": float,
         "Longitude": float,
     },
 )
@@ -2180,22 +2114,20 @@
         "NextToken": str,
         "PageSize": str,
         "StartTime": Union[datetime, str],
     },
     total=False,
 )
 
-
 class GetApplicationDateRangeKpiRequestRequestTypeDef(
     _RequiredGetApplicationDateRangeKpiRequestRequestTypeDef,
     _OptionalGetApplicationDateRangeKpiRequestRequestTypeDef,
 ):
     pass
 
-
 GetApplicationSettingsRequestRequestTypeDef = TypedDict(
     "GetApplicationSettingsRequestRequestTypeDef",
     {
         "ApplicationId": str,
     },
 )
 
@@ -2227,22 +2159,20 @@
     {
         "PageSize": str,
         "Token": str,
     },
     total=False,
 )
 
-
 class GetCampaignActivitiesRequestRequestTypeDef(
     _RequiredGetCampaignActivitiesRequestRequestTypeDef,
     _OptionalGetCampaignActivitiesRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredGetCampaignDateRangeKpiRequestRequestTypeDef = TypedDict(
     "_RequiredGetCampaignDateRangeKpiRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "CampaignId": str,
         "KpiName": str,
     },
@@ -2254,22 +2184,20 @@
         "NextToken": str,
         "PageSize": str,
         "StartTime": Union[datetime, str],
     },
     total=False,
 )
 
-
 class GetCampaignDateRangeKpiRequestRequestTypeDef(
     _RequiredGetCampaignDateRangeKpiRequestRequestTypeDef,
     _OptionalGetCampaignDateRangeKpiRequestRequestTypeDef,
 ):
     pass
 
-
 GetCampaignRequestRequestTypeDef = TypedDict(
     "GetCampaignRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "CampaignId": str,
     },
 )
@@ -2295,22 +2223,20 @@
     {
         "PageSize": str,
         "Token": str,
     },
     total=False,
 )
 
-
 class GetCampaignVersionsRequestRequestTypeDef(
     _RequiredGetCampaignVersionsRequestRequestTypeDef,
     _OptionalGetCampaignVersionsRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredGetCampaignsRequestRequestTypeDef = TypedDict(
     "_RequiredGetCampaignsRequestRequestTypeDef",
     {
         "ApplicationId": str,
     },
 )
 _OptionalGetCampaignsRequestRequestTypeDef = TypedDict(
@@ -2318,21 +2244,19 @@
     {
         "PageSize": str,
         "Token": str,
     },
     total=False,
 )
 
-
 class GetCampaignsRequestRequestTypeDef(
     _RequiredGetCampaignsRequestRequestTypeDef, _OptionalGetCampaignsRequestRequestTypeDef
 ):
     pass
 
-
 GetChannelsRequestRequestTypeDef = TypedDict(
     "GetChannelsRequestRequestTypeDef",
     {
         "ApplicationId": str,
     },
 )
 
@@ -2353,21 +2277,19 @@
     "_OptionalGetEmailTemplateRequestRequestTypeDef",
     {
         "Version": str,
     },
     total=False,
 )
 
-
 class GetEmailTemplateRequestRequestTypeDef(
     _RequiredGetEmailTemplateRequestRequestTypeDef, _OptionalGetEmailTemplateRequestRequestTypeDef
 ):
     pass
 
-
 GetEndpointRequestRequestTypeDef = TypedDict(
     "GetEndpointRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "EndpointId": str,
     },
 )
@@ -2398,21 +2320,19 @@
     {
         "PageSize": str,
         "Token": str,
     },
     total=False,
 )
 
-
 class GetExportJobsRequestRequestTypeDef(
     _RequiredGetExportJobsRequestRequestTypeDef, _OptionalGetExportJobsRequestRequestTypeDef
 ):
     pass
 
-
 GetGcmChannelRequestRequestTypeDef = TypedDict(
     "GetGcmChannelRequestRequestTypeDef",
     {
         "ApplicationId": str,
     },
 )
 
@@ -2435,21 +2355,19 @@
     {
         "PageSize": str,
         "Token": str,
     },
     total=False,
 )
 
-
 class GetImportJobsRequestRequestTypeDef(
     _RequiredGetImportJobsRequestRequestTypeDef, _OptionalGetImportJobsRequestRequestTypeDef
 ):
     pass
 
-
 GetInAppMessagesRequestRequestTypeDef = TypedDict(
     "GetInAppMessagesRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "EndpointId": str,
     },
 )
@@ -2464,21 +2382,19 @@
     "_OptionalGetInAppTemplateRequestRequestTypeDef",
     {
         "Version": str,
     },
     total=False,
 )
 
-
 class GetInAppTemplateRequestRequestTypeDef(
     _RequiredGetInAppTemplateRequestRequestTypeDef, _OptionalGetInAppTemplateRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredGetJourneyDateRangeKpiRequestRequestTypeDef = TypedDict(
     "_RequiredGetJourneyDateRangeKpiRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "JourneyId": str,
         "KpiName": str,
     },
@@ -2490,22 +2406,20 @@
         "NextToken": str,
         "PageSize": str,
         "StartTime": Union[datetime, str],
     },
     total=False,
 )
 
-
 class GetJourneyDateRangeKpiRequestRequestTypeDef(
     _RequiredGetJourneyDateRangeKpiRequestRequestTypeDef,
     _OptionalGetJourneyDateRangeKpiRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredGetJourneyExecutionActivityMetricsRequestRequestTypeDef = TypedDict(
     "_RequiredGetJourneyExecutionActivityMetricsRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "JourneyActivityId": str,
         "JourneyId": str,
     },
@@ -2515,22 +2429,20 @@
     {
         "NextToken": str,
         "PageSize": str,
     },
     total=False,
 )
 
-
 class GetJourneyExecutionActivityMetricsRequestRequestTypeDef(
     _RequiredGetJourneyExecutionActivityMetricsRequestRequestTypeDef,
     _OptionalGetJourneyExecutionActivityMetricsRequestRequestTypeDef,
 ):
     pass
 
-
 JourneyExecutionActivityMetricsResponseTypeDef = TypedDict(
     "JourneyExecutionActivityMetricsResponseTypeDef",
     {
         "ActivityType": str,
         "ApplicationId": str,
         "JourneyActivityId": str,
         "JourneyId": str,
@@ -2551,22 +2463,20 @@
     {
         "NextToken": str,
         "PageSize": str,
     },
     total=False,
 )
 
-
 class GetJourneyExecutionMetricsRequestRequestTypeDef(
     _RequiredGetJourneyExecutionMetricsRequestRequestTypeDef,
     _OptionalGetJourneyExecutionMetricsRequestRequestTypeDef,
 ):
     pass
 
-
 JourneyExecutionMetricsResponseTypeDef = TypedDict(
     "JourneyExecutionMetricsResponseTypeDef",
     {
         "ApplicationId": str,
         "JourneyId": str,
         "LastEvaluatedTime": str,
         "Metrics": Dict[str, str],
@@ -2577,35 +2487,125 @@
     "GetJourneyRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "JourneyId": str,
     },
 )
 
+_RequiredGetJourneyRunExecutionActivityMetricsRequestRequestTypeDef = TypedDict(
+    "_RequiredGetJourneyRunExecutionActivityMetricsRequestRequestTypeDef",
+    {
+        "ApplicationId": str,
+        "JourneyActivityId": str,
+        "JourneyId": str,
+        "RunId": str,
+    },
+)
+_OptionalGetJourneyRunExecutionActivityMetricsRequestRequestTypeDef = TypedDict(
+    "_OptionalGetJourneyRunExecutionActivityMetricsRequestRequestTypeDef",
+    {
+        "NextToken": str,
+        "PageSize": str,
+    },
+    total=False,
+)
+
+class GetJourneyRunExecutionActivityMetricsRequestRequestTypeDef(
+    _RequiredGetJourneyRunExecutionActivityMetricsRequestRequestTypeDef,
+    _OptionalGetJourneyRunExecutionActivityMetricsRequestRequestTypeDef,
+):
+    pass
+
+JourneyRunExecutionActivityMetricsResponseTypeDef = TypedDict(
+    "JourneyRunExecutionActivityMetricsResponseTypeDef",
+    {
+        "ActivityType": str,
+        "ApplicationId": str,
+        "JourneyActivityId": str,
+        "JourneyId": str,
+        "LastEvaluatedTime": str,
+        "Metrics": Dict[str, str],
+        "RunId": str,
+    },
+)
+
+_RequiredGetJourneyRunExecutionMetricsRequestRequestTypeDef = TypedDict(
+    "_RequiredGetJourneyRunExecutionMetricsRequestRequestTypeDef",
+    {
+        "ApplicationId": str,
+        "JourneyId": str,
+        "RunId": str,
+    },
+)
+_OptionalGetJourneyRunExecutionMetricsRequestRequestTypeDef = TypedDict(
+    "_OptionalGetJourneyRunExecutionMetricsRequestRequestTypeDef",
+    {
+        "NextToken": str,
+        "PageSize": str,
+    },
+    total=False,
+)
+
+class GetJourneyRunExecutionMetricsRequestRequestTypeDef(
+    _RequiredGetJourneyRunExecutionMetricsRequestRequestTypeDef,
+    _OptionalGetJourneyRunExecutionMetricsRequestRequestTypeDef,
+):
+    pass
+
+JourneyRunExecutionMetricsResponseTypeDef = TypedDict(
+    "JourneyRunExecutionMetricsResponseTypeDef",
+    {
+        "ApplicationId": str,
+        "JourneyId": str,
+        "LastEvaluatedTime": str,
+        "Metrics": Dict[str, str],
+        "RunId": str,
+    },
+)
+
+_RequiredGetJourneyRunsRequestRequestTypeDef = TypedDict(
+    "_RequiredGetJourneyRunsRequestRequestTypeDef",
+    {
+        "ApplicationId": str,
+        "JourneyId": str,
+    },
+)
+_OptionalGetJourneyRunsRequestRequestTypeDef = TypedDict(
+    "_OptionalGetJourneyRunsRequestRequestTypeDef",
+    {
+        "PageSize": str,
+        "Token": str,
+    },
+    total=False,
+)
+
+class GetJourneyRunsRequestRequestTypeDef(
+    _RequiredGetJourneyRunsRequestRequestTypeDef, _OptionalGetJourneyRunsRequestRequestTypeDef
+):
+    pass
+
 _RequiredGetPushTemplateRequestRequestTypeDef = TypedDict(
     "_RequiredGetPushTemplateRequestRequestTypeDef",
     {
         "TemplateName": str,
     },
 )
 _OptionalGetPushTemplateRequestRequestTypeDef = TypedDict(
     "_OptionalGetPushTemplateRequestRequestTypeDef",
     {
         "Version": str,
     },
     total=False,
 )
 
-
 class GetPushTemplateRequestRequestTypeDef(
     _RequiredGetPushTemplateRequestRequestTypeDef, _OptionalGetPushTemplateRequestRequestTypeDef
 ):
     pass
 
-
 GetRecommenderConfigurationRequestRequestTypeDef = TypedDict(
     "GetRecommenderConfigurationRequestRequestTypeDef",
     {
         "RecommenderId": str,
     },
 )
 
@@ -2630,22 +2630,20 @@
     {
         "PageSize": str,
         "Token": str,
     },
     total=False,
 )
 
-
 class GetSegmentExportJobsRequestRequestTypeDef(
     _RequiredGetSegmentExportJobsRequestRequestTypeDef,
     _OptionalGetSegmentExportJobsRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredGetSegmentImportJobsRequestRequestTypeDef = TypedDict(
     "_RequiredGetSegmentImportJobsRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "SegmentId": str,
     },
 )
@@ -2654,22 +2652,20 @@
     {
         "PageSize": str,
         "Token": str,
     },
     total=False,
 )
 
-
 class GetSegmentImportJobsRequestRequestTypeDef(
     _RequiredGetSegmentImportJobsRequestRequestTypeDef,
     _OptionalGetSegmentImportJobsRequestRequestTypeDef,
 ):
     pass
 
-
 GetSegmentRequestRequestTypeDef = TypedDict(
     "GetSegmentRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "SegmentId": str,
     },
 )
@@ -2695,22 +2691,20 @@
     {
         "PageSize": str,
         "Token": str,
     },
     total=False,
 )
 
-
 class GetSegmentVersionsRequestRequestTypeDef(
     _RequiredGetSegmentVersionsRequestRequestTypeDef,
     _OptionalGetSegmentVersionsRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredGetSegmentsRequestRequestTypeDef = TypedDict(
     "_RequiredGetSegmentsRequestRequestTypeDef",
     {
         "ApplicationId": str,
     },
 )
 _OptionalGetSegmentsRequestRequestTypeDef = TypedDict(
@@ -2718,21 +2712,19 @@
     {
         "PageSize": str,
         "Token": str,
     },
     total=False,
 )
 
-
 class GetSegmentsRequestRequestTypeDef(
     _RequiredGetSegmentsRequestRequestTypeDef, _OptionalGetSegmentsRequestRequestTypeDef
 ):
     pass
 
-
 GetSmsChannelRequestRequestTypeDef = TypedDict(
     "GetSmsChannelRequestRequestTypeDef",
     {
         "ApplicationId": str,
     },
 )
 
@@ -2746,21 +2738,19 @@
     "_OptionalGetSmsTemplateRequestRequestTypeDef",
     {
         "Version": str,
     },
     total=False,
 )
 
-
 class GetSmsTemplateRequestRequestTypeDef(
     _RequiredGetSmsTemplateRequestRequestTypeDef, _OptionalGetSmsTemplateRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredSMSTemplateResponseTypeDef = TypedDict(
     "_RequiredSMSTemplateResponseTypeDef",
     {
         "CreationDate": str,
         "LastModifiedDate": str,
         "TemplateName": str,
         "TemplateType": TemplateTypeType,
@@ -2776,21 +2766,19 @@
         "tags": Dict[str, str],
         "TemplateDescription": str,
         "Version": str,
     },
     total=False,
 )
 
-
 class SMSTemplateResponseTypeDef(
     _RequiredSMSTemplateResponseTypeDef, _OptionalSMSTemplateResponseTypeDef
 ):
     pass
 
-
 GetUserEndpointsRequestRequestTypeDef = TypedDict(
     "GetUserEndpointsRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "UserId": str,
     },
 )
@@ -2812,21 +2800,19 @@
     "_OptionalGetVoiceTemplateRequestRequestTypeDef",
     {
         "Version": str,
     },
     total=False,
 )
 
-
 class GetVoiceTemplateRequestRequestTypeDef(
     _RequiredGetVoiceTemplateRequestRequestTypeDef, _OptionalGetVoiceTemplateRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredVoiceTemplateResponseTypeDef = TypedDict(
     "_RequiredVoiceTemplateResponseTypeDef",
     {
         "CreationDate": str,
         "LastModifiedDate": str,
         "TemplateName": str,
         "TemplateType": TemplateTypeType,
@@ -2843,21 +2829,19 @@
         "TemplateDescription": str,
         "Version": str,
         "VoiceId": str,
     },
     total=False,
 )
 
-
 class VoiceTemplateResponseTypeDef(
     _RequiredVoiceTemplateResponseTypeDef, _OptionalVoiceTemplateResponseTypeDef
 ):
     pass
 
-
 _RequiredImportJobResourceTypeDef = TypedDict(
     "_RequiredImportJobResourceTypeDef",
     {
         "Format": FormatType,
         "RoleArn": str,
         "S3Url": str,
     },
@@ -2870,21 +2854,19 @@
         "RegisterEndpoints": bool,
         "SegmentId": str,
         "SegmentName": str,
     },
     total=False,
 )
 
-
 class ImportJobResourceTypeDef(
     _RequiredImportJobResourceTypeDef, _OptionalImportJobResourceTypeDef
 ):
     pass
 
-
 InAppMessageBodyConfigTypeDef = TypedDict(
     "InAppMessageBodyConfigTypeDef",
     {
         "Alignment": AlignmentType,
         "Body": str,
         "TextColor": str,
     },
@@ -2900,21 +2882,19 @@
     "_OptionalOverrideButtonConfigurationTypeDef",
     {
         "Link": str,
     },
     total=False,
 )
 
-
 class OverrideButtonConfigurationTypeDef(
     _RequiredOverrideButtonConfigurationTypeDef, _OptionalOverrideButtonConfigurationTypeDef
 ):
     pass
 
-
 InAppMessageHeaderConfigTypeDef = TypedDict(
     "InAppMessageHeaderConfigTypeDef",
     {
         "Alignment": AlignmentType,
         "Header": str,
         "TextColor": str,
     },
@@ -2954,14 +2934,24 @@
         "EndTime": Union[datetime, str],
         "StartTime": Union[datetime, str],
         "Timezone": str,
     },
     total=False,
 )
 
+JourneyRunResponseTypeDef = TypedDict(
+    "JourneyRunResponseTypeDef",
+    {
+        "CreationTime": str,
+        "LastUpdateTime": str,
+        "RunId": str,
+        "Status": JourneyRunStatusType,
+    },
+)
+
 JourneySMSMessageTypeDef = TypedDict(
     "JourneySMSMessageTypeDef",
     {
         "MessageType": MessageTypeType,
         "OriginationNumber": str,
         "SenderId": str,
         "EntityId": str,
@@ -2989,21 +2979,19 @@
     {
         "PageSize": str,
         "Token": str,
     },
     total=False,
 )
 
-
 class ListJourneysRequestRequestTypeDef(
     _RequiredListJourneysRequestRequestTypeDef, _OptionalListJourneysRequestRequestTypeDef
 ):
     pass
 
-
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
@@ -3026,22 +3014,20 @@
     {
         "NextToken": str,
         "PageSize": str,
     },
     total=False,
 )
 
-
 class ListTemplateVersionsRequestRequestTypeDef(
     _RequiredListTemplateVersionsRequestRequestTypeDef,
     _OptionalListTemplateVersionsRequestRequestTypeDef,
 ):
     pass
 
-
 ListTemplatesRequestRequestTypeDef = TypedDict(
     "ListTemplatesRequestRequestTypeDef",
     {
         "NextToken": str,
         "PageSize": str,
         "Prefix": str,
         "TemplateType": str,
@@ -3081,19 +3067,17 @@
         "MessageId": str,
         "StatusMessage": str,
         "UpdatedToken": str,
     },
     total=False,
 )
 
-
 class MessageResultTypeDef(_RequiredMessageResultTypeDef, _OptionalMessageResultTypeDef):
     pass
 
-
 NumberValidateRequestTypeDef = TypedDict(
     "NumberValidateRequestTypeDef",
     {
         "IsoCountryCode": str,
         "PhoneNumber": str,
     },
     total=False,
@@ -3158,14 +3142,25 @@
     "UpdateAttributesRequestTypeDef",
     {
         "Blacklist": Sequence[str],
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
 ResultRowValueTypeDef = TypedDict(
     "ResultRowValueTypeDef",
     {
         "Key": str,
         "Type": str,
         "Value": str,
     },
@@ -3198,19 +3193,17 @@
     "_OptionalSegmentReferenceTypeDef",
     {
         "Version": int,
     },
     total=False,
 )
 
-
 class SegmentReferenceTypeDef(_RequiredSegmentReferenceTypeDef, _OptionalSegmentReferenceTypeDef):
     pass
 
-
 _RequiredSegmentImportResourceTypeDef = TypedDict(
     "_RequiredSegmentImportResourceTypeDef",
     {
         "ExternalId": str,
         "Format": FormatType,
         "RoleArn": str,
         "S3Url": str,
@@ -3221,21 +3214,19 @@
     "_OptionalSegmentImportResourceTypeDef",
     {
         "ChannelCounts": Dict[str, int],
     },
     total=False,
 )
 
-
 class SegmentImportResourceTypeDef(
     _RequiredSegmentImportResourceTypeDef, _OptionalSegmentImportResourceTypeDef
 ):
     pass
 
-
 _RequiredSendOTPMessageRequestParametersTypeDef = TypedDict(
     "_RequiredSendOTPMessageRequestParametersTypeDef",
     {
         "BrandName": str,
         "Channel": str,
         "DestinationIdentity": str,
         "OriginationIdentity": str,
@@ -3251,21 +3242,19 @@
         "Language": str,
         "TemplateId": str,
         "ValidityPeriod": int,
     },
     total=False,
 )
 
-
 class SendOTPMessageRequestParametersTypeDef(
     _RequiredSendOTPMessageRequestParametersTypeDef, _OptionalSendOTPMessageRequestParametersTypeDef
 ):
     pass
 
-
 SimpleEmailPartTypeDef = TypedDict(
     "SimpleEmailPartTypeDef",
     {
         "Charset": str,
         "Data": str,
     },
     total=False,
@@ -3305,19 +3294,17 @@
         "tags": Dict[str, str],
         "TemplateDescription": str,
         "Version": str,
     },
     total=False,
 )
 
-
 class TemplateResponseTypeDef(_RequiredTemplateResponseTypeDef, _OptionalTemplateResponseTypeDef):
     pass
 
-
 _RequiredTemplateVersionResponseTypeDef = TypedDict(
     "_RequiredTemplateVersionResponseTypeDef",
     {
         "CreationDate": str,
         "LastModifiedDate": str,
         "TemplateName": str,
         "TemplateType": str,
@@ -3329,21 +3316,19 @@
         "DefaultSubstitutions": str,
         "TemplateDescription": str,
         "Version": str,
     },
     total=False,
 )
 
-
 class TemplateVersionResponseTypeDef(
     _RequiredTemplateVersionResponseTypeDef, _OptionalTemplateVersionResponseTypeDef
 ):
     pass
 
-
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
@@ -3365,21 +3350,19 @@
         "RecommendationTransformerUri": str,
         "RecommendationsDisplayName": str,
         "RecommendationsPerMessage": int,
     },
     total=False,
 )
 
-
 class UpdateRecommenderConfigurationTypeDef(
     _RequiredUpdateRecommenderConfigurationTypeDef, _OptionalUpdateRecommenderConfigurationTypeDef
 ):
     pass
 
-
 VoiceChannelRequestTypeDef = TypedDict(
     "VoiceChannelRequestTypeDef",
     {
         "Enabled": bool,
     },
     total=False,
 )
@@ -3405,335 +3388,324 @@
     "UpdateAdmChannelRequestRequestTypeDef",
     {
         "ADMChannelRequest": ADMChannelRequestTypeDef,
         "ApplicationId": str,
     },
 )
 
-UpdateApnsChannelRequestRequestTypeDef = TypedDict(
-    "UpdateApnsChannelRequestRequestTypeDef",
+DeleteAdmChannelResponseTypeDef = TypedDict(
+    "DeleteAdmChannelResponseTypeDef",
     {
-        "APNSChannelRequest": APNSChannelRequestTypeDef,
-        "ApplicationId": str,
+        "ADMChannelResponse": ADMChannelResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateApnsSandboxChannelRequestRequestTypeDef = TypedDict(
-    "UpdateApnsSandboxChannelRequestRequestTypeDef",
+GetAdmChannelResponseTypeDef = TypedDict(
+    "GetAdmChannelResponseTypeDef",
     {
-        "APNSSandboxChannelRequest": APNSSandboxChannelRequestTypeDef,
-        "ApplicationId": str,
+        "ADMChannelResponse": ADMChannelResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateApnsVoipChannelRequestRequestTypeDef = TypedDict(
-    "UpdateApnsVoipChannelRequestRequestTypeDef",
+UpdateAdmChannelResponseTypeDef = TypedDict(
+    "UpdateAdmChannelResponseTypeDef",
     {
-        "APNSVoipChannelRequest": APNSVoipChannelRequestTypeDef,
-        "ApplicationId": str,
+        "ADMChannelResponse": ADMChannelResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateApnsVoipSandboxChannelRequestRequestTypeDef = TypedDict(
-    "UpdateApnsVoipSandboxChannelRequestRequestTypeDef",
+UpdateApnsChannelRequestRequestTypeDef = TypedDict(
+    "UpdateApnsChannelRequestRequestTypeDef",
     {
-        "APNSVoipSandboxChannelRequest": APNSVoipSandboxChannelRequestTypeDef,
+        "APNSChannelRequest": APNSChannelRequestTypeDef,
         "ApplicationId": str,
     },
 )
 
-_RequiredActivitiesResponseTypeDef = TypedDict(
-    "_RequiredActivitiesResponseTypeDef",
+DeleteApnsChannelResponseTypeDef = TypedDict(
+    "DeleteApnsChannelResponseTypeDef",
     {
-        "Item": List[ActivityResponseTypeDef],
+        "APNSChannelResponse": APNSChannelResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalActivitiesResponseTypeDef = TypedDict(
-    "_OptionalActivitiesResponseTypeDef",
+
+GetApnsChannelResponseTypeDef = TypedDict(
+    "GetApnsChannelResponseTypeDef",
     {
-        "NextToken": str,
+        "APNSChannelResponse": APNSChannelResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-
-class ActivitiesResponseTypeDef(
-    _RequiredActivitiesResponseTypeDef, _OptionalActivitiesResponseTypeDef
-):
-    pass
-
-
-ApplicationsResponseTypeDef = TypedDict(
-    "ApplicationsResponseTypeDef",
+UpdateApnsChannelResponseTypeDef = TypedDict(
+    "UpdateApnsChannelResponseTypeDef",
     {
-        "Item": List[ApplicationResponseTypeDef],
-        "NextToken": str,
+        "APNSChannelResponse": APNSChannelResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-_RequiredApplicationSettingsResourceTypeDef = TypedDict(
-    "_RequiredApplicationSettingsResourceTypeDef",
+UpdateApnsSandboxChannelRequestRequestTypeDef = TypedDict(
+    "UpdateApnsSandboxChannelRequestRequestTypeDef",
     {
+        "APNSSandboxChannelRequest": APNSSandboxChannelRequestTypeDef,
         "ApplicationId": str,
     },
 )
-_OptionalApplicationSettingsResourceTypeDef = TypedDict(
-    "_OptionalApplicationSettingsResourceTypeDef",
+
+DeleteApnsSandboxChannelResponseTypeDef = TypedDict(
+    "DeleteApnsSandboxChannelResponseTypeDef",
     {
-        "CampaignHook": CampaignHookTypeDef,
-        "LastModifiedDate": str,
-        "Limits": CampaignLimitsTypeDef,
-        "QuietTime": QuietTimeTypeDef,
+        "APNSSandboxChannelResponse": APNSSandboxChannelResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
+GetApnsSandboxChannelResponseTypeDef = TypedDict(
+    "GetApnsSandboxChannelResponseTypeDef",
+    {
+        "APNSSandboxChannelResponse": APNSSandboxChannelResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
-class ApplicationSettingsResourceTypeDef(
-    _RequiredApplicationSettingsResourceTypeDef, _OptionalApplicationSettingsResourceTypeDef
-):
-    pass
-
-
-WriteApplicationSettingsRequestTypeDef = TypedDict(
-    "WriteApplicationSettingsRequestTypeDef",
+UpdateApnsSandboxChannelResponseTypeDef = TypedDict(
+    "UpdateApnsSandboxChannelResponseTypeDef",
     {
-        "CampaignHook": CampaignHookTypeDef,
-        "CloudWatchMetricsEnabled": bool,
-        "EventTaggingEnabled": bool,
-        "Limits": CampaignLimitsTypeDef,
-        "QuietTime": QuietTimeTypeDef,
+        "APNSSandboxChannelResponse": APNSSandboxChannelResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-UpdateBaiduChannelRequestRequestTypeDef = TypedDict(
-    "UpdateBaiduChannelRequestRequestTypeDef",
+UpdateApnsVoipChannelRequestRequestTypeDef = TypedDict(
+    "UpdateApnsVoipChannelRequestRequestTypeDef",
     {
+        "APNSVoipChannelRequest": APNSVoipChannelRequestTypeDef,
         "ApplicationId": str,
-        "BaiduChannelRequest": BaiduChannelRequestTypeDef,
     },
 )
 
-ChannelsResponseTypeDef = TypedDict(
-    "ChannelsResponseTypeDef",
+DeleteApnsVoipChannelResponseTypeDef = TypedDict(
+    "DeleteApnsVoipChannelResponseTypeDef",
     {
-        "Channels": Dict[str, ChannelResponseTypeDef],
+        "APNSVoipChannelResponse": APNSVoipChannelResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ClosedDaysTypeDef = TypedDict(
-    "ClosedDaysTypeDef",
+GetApnsVoipChannelResponseTypeDef = TypedDict(
+    "GetApnsVoipChannelResponseTypeDef",
     {
-        "EMAIL": Sequence[ClosedDaysRuleTypeDef],
-        "SMS": Sequence[ClosedDaysRuleTypeDef],
-        "PUSH": Sequence[ClosedDaysRuleTypeDef],
-        "VOICE": Sequence[ClosedDaysRuleTypeDef],
-        "CUSTOM": Sequence[ClosedDaysRuleTypeDef],
+        "APNSVoipChannelResponse": APNSVoipChannelResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-WaitActivityTypeDef = TypedDict(
-    "WaitActivityTypeDef",
+UpdateApnsVoipChannelResponseTypeDef = TypedDict(
+    "UpdateApnsVoipChannelResponseTypeDef",
     {
-        "NextActivity": str,
-        "WaitTime": WaitTimeTypeDef,
+        "APNSVoipChannelResponse": APNSVoipChannelResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-CreateAppRequestRequestTypeDef = TypedDict(
-    "CreateAppRequestRequestTypeDef",
+UpdateApnsVoipSandboxChannelRequestRequestTypeDef = TypedDict(
+    "UpdateApnsVoipSandboxChannelRequestRequestTypeDef",
     {
-        "CreateApplicationRequest": CreateApplicationRequestTypeDef,
+        "APNSVoipSandboxChannelRequest": APNSVoipSandboxChannelRequestTypeDef,
+        "ApplicationId": str,
     },
 )
 
-CreateAppResponseTypeDef = TypedDict(
-    "CreateAppResponseTypeDef",
+DeleteApnsVoipSandboxChannelResponseTypeDef = TypedDict(
+    "DeleteApnsVoipSandboxChannelResponseTypeDef",
     {
-        "ApplicationResponse": ApplicationResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "APNSVoipSandboxChannelResponse": APNSVoipSandboxChannelResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteAdmChannelResponseTypeDef = TypedDict(
-    "DeleteAdmChannelResponseTypeDef",
+GetApnsVoipSandboxChannelResponseTypeDef = TypedDict(
+    "GetApnsVoipSandboxChannelResponseTypeDef",
     {
-        "ADMChannelResponse": ADMChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "APNSVoipSandboxChannelResponse": APNSVoipSandboxChannelResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteApnsChannelResponseTypeDef = TypedDict(
-    "DeleteApnsChannelResponseTypeDef",
+UpdateApnsVoipSandboxChannelResponseTypeDef = TypedDict(
+    "UpdateApnsVoipSandboxChannelResponseTypeDef",
     {
-        "APNSChannelResponse": APNSChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "APNSVoipSandboxChannelResponse": APNSVoipSandboxChannelResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteApnsSandboxChannelResponseTypeDef = TypedDict(
-    "DeleteApnsSandboxChannelResponseTypeDef",
+_RequiredActivitiesResponseTypeDef = TypedDict(
+    "_RequiredActivitiesResponseTypeDef",
     {
-        "APNSSandboxChannelResponse": APNSSandboxChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Item": List[ActivityResponseTypeDef],
     },
 )
-
-DeleteApnsVoipChannelResponseTypeDef = TypedDict(
-    "DeleteApnsVoipChannelResponseTypeDef",
+_OptionalActivitiesResponseTypeDef = TypedDict(
+    "_OptionalActivitiesResponseTypeDef",
     {
-        "APNSVoipChannelResponse": APNSVoipChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "NextToken": str,
     },
+    total=False,
 )
 
-DeleteApnsVoipSandboxChannelResponseTypeDef = TypedDict(
-    "DeleteApnsVoipSandboxChannelResponseTypeDef",
+class ActivitiesResponseTypeDef(
+    _RequiredActivitiesResponseTypeDef, _OptionalActivitiesResponseTypeDef
+):
+    pass
+
+ApplicationsResponseTypeDef = TypedDict(
+    "ApplicationsResponseTypeDef",
     {
-        "APNSVoipSandboxChannelResponse": APNSVoipSandboxChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Item": List[ApplicationResponseTypeDef],
+        "NextToken": str,
     },
+    total=False,
 )
 
-DeleteAppResponseTypeDef = TypedDict(
-    "DeleteAppResponseTypeDef",
+CreateAppResponseTypeDef = TypedDict(
+    "CreateAppResponseTypeDef",
     {
         "ApplicationResponse": ApplicationResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteBaiduChannelResponseTypeDef = TypedDict(
-    "DeleteBaiduChannelResponseTypeDef",
+DeleteAppResponseTypeDef = TypedDict(
+    "DeleteAppResponseTypeDef",
     {
-        "BaiduChannelResponse": BaiduChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ApplicationResponse": ApplicationResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
+GetAppResponseTypeDef = TypedDict(
+    "GetAppResponseTypeDef",
     {
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ApplicationResponse": ApplicationResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetAdmChannelResponseTypeDef = TypedDict(
-    "GetAdmChannelResponseTypeDef",
+_RequiredApplicationSettingsResourceTypeDef = TypedDict(
+    "_RequiredApplicationSettingsResourceTypeDef",
     {
-        "ADMChannelResponse": ADMChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ApplicationId": str,
     },
 )
-
-GetApnsChannelResponseTypeDef = TypedDict(
-    "GetApnsChannelResponseTypeDef",
+_OptionalApplicationSettingsResourceTypeDef = TypedDict(
+    "_OptionalApplicationSettingsResourceTypeDef",
     {
-        "APNSChannelResponse": APNSChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "CampaignHook": CampaignHookTypeDef,
+        "LastModifiedDate": str,
+        "Limits": CampaignLimitsTypeDef,
+        "QuietTime": QuietTimeTypeDef,
     },
+    total=False,
 )
 
-GetApnsSandboxChannelResponseTypeDef = TypedDict(
-    "GetApnsSandboxChannelResponseTypeDef",
+class ApplicationSettingsResourceTypeDef(
+    _RequiredApplicationSettingsResourceTypeDef, _OptionalApplicationSettingsResourceTypeDef
+):
+    pass
+
+WriteApplicationSettingsRequestTypeDef = TypedDict(
+    "WriteApplicationSettingsRequestTypeDef",
     {
-        "APNSSandboxChannelResponse": APNSSandboxChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "CampaignHook": CampaignHookTypeDef,
+        "CloudWatchMetricsEnabled": bool,
+        "EventTaggingEnabled": bool,
+        "Limits": CampaignLimitsTypeDef,
+        "QuietTime": QuietTimeTypeDef,
     },
+    total=False,
 )
 
-GetApnsVoipChannelResponseTypeDef = TypedDict(
-    "GetApnsVoipChannelResponseTypeDef",
+RemoveAttributesResponseTypeDef = TypedDict(
+    "RemoveAttributesResponseTypeDef",
     {
-        "APNSVoipChannelResponse": APNSVoipChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "AttributesResource": AttributesResourceTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetApnsVoipSandboxChannelResponseTypeDef = TypedDict(
-    "GetApnsVoipSandboxChannelResponseTypeDef",
+UpdateBaiduChannelRequestRequestTypeDef = TypedDict(
+    "UpdateBaiduChannelRequestRequestTypeDef",
     {
-        "APNSVoipSandboxChannelResponse": APNSVoipSandboxChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ApplicationId": str,
+        "BaiduChannelRequest": BaiduChannelRequestTypeDef,
     },
 )
 
-GetAppResponseTypeDef = TypedDict(
-    "GetAppResponseTypeDef",
+DeleteBaiduChannelResponseTypeDef = TypedDict(
+    "DeleteBaiduChannelResponseTypeDef",
     {
-        "ApplicationResponse": ApplicationResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "BaiduChannelResponse": BaiduChannelResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetBaiduChannelResponseTypeDef = TypedDict(
     "GetBaiduChannelResponseTypeDef",
     {
         "BaiduChannelResponse": BaiduChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RemoveAttributesResponseTypeDef = TypedDict(
-    "RemoveAttributesResponseTypeDef",
-    {
-        "AttributesResource": AttributesResourceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateAdmChannelResponseTypeDef = TypedDict(
-    "UpdateAdmChannelResponseTypeDef",
-    {
-        "ADMChannelResponse": ADMChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateApnsChannelResponseTypeDef = TypedDict(
-    "UpdateApnsChannelResponseTypeDef",
+UpdateBaiduChannelResponseTypeDef = TypedDict(
+    "UpdateBaiduChannelResponseTypeDef",
     {
-        "APNSChannelResponse": APNSChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "BaiduChannelResponse": BaiduChannelResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateApnsSandboxChannelResponseTypeDef = TypedDict(
-    "UpdateApnsSandboxChannelResponseTypeDef",
+ChannelsResponseTypeDef = TypedDict(
+    "ChannelsResponseTypeDef",
     {
-        "APNSSandboxChannelResponse": APNSSandboxChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Channels": Dict[str, ChannelResponseTypeDef],
     },
 )
 
-UpdateApnsVoipChannelResponseTypeDef = TypedDict(
-    "UpdateApnsVoipChannelResponseTypeDef",
+ClosedDaysTypeDef = TypedDict(
+    "ClosedDaysTypeDef",
     {
-        "APNSVoipChannelResponse": APNSVoipChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "EMAIL": Sequence[ClosedDaysRuleTypeDef],
+        "SMS": Sequence[ClosedDaysRuleTypeDef],
+        "PUSH": Sequence[ClosedDaysRuleTypeDef],
+        "VOICE": Sequence[ClosedDaysRuleTypeDef],
+        "CUSTOM": Sequence[ClosedDaysRuleTypeDef],
     },
+    total=False,
 )
 
-UpdateApnsVoipSandboxChannelResponseTypeDef = TypedDict(
-    "UpdateApnsVoipSandboxChannelResponseTypeDef",
+WaitActivityTypeDef = TypedDict(
+    "WaitActivityTypeDef",
     {
-        "APNSVoipSandboxChannelResponse": APNSVoipSandboxChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "NextActivity": str,
+        "WaitTime": WaitTimeTypeDef,
     },
+    total=False,
 )
 
-UpdateBaiduChannelResponseTypeDef = TypedDict(
-    "UpdateBaiduChannelResponseTypeDef",
+CreateAppRequestRequestTypeDef = TypedDict(
+    "CreateAppRequestRequestTypeDef",
     {
-        "BaiduChannelResponse": BaiduChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "CreateApplicationRequest": CreateApplicationRequestTypeDef,
     },
 )
 
 CreateEmailTemplateRequestRequestTypeDef = TypedDict(
     "CreateEmailTemplateRequestRequestTypeDef",
     {
         "EmailTemplateRequest": EmailTemplateRequestTypeDef,
@@ -3753,51 +3725,49 @@
     {
         "CreateNewVersion": bool,
         "Version": str,
     },
     total=False,
 )
 
-
 class UpdateEmailTemplateRequestRequestTypeDef(
     _RequiredUpdateEmailTemplateRequestRequestTypeDef,
     _OptionalUpdateEmailTemplateRequestRequestTypeDef,
 ):
     pass
 
-
 CreateEmailTemplateResponseTypeDef = TypedDict(
     "CreateEmailTemplateResponseTypeDef",
     {
         "CreateTemplateMessageBody": CreateTemplateMessageBodyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreatePushTemplateResponseTypeDef = TypedDict(
     "CreatePushTemplateResponseTypeDef",
     {
         "CreateTemplateMessageBody": CreateTemplateMessageBodyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateSmsTemplateResponseTypeDef = TypedDict(
     "CreateSmsTemplateResponseTypeDef",
     {
         "CreateTemplateMessageBody": CreateTemplateMessageBodyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateVoiceTemplateResponseTypeDef = TypedDict(
     "CreateVoiceTemplateResponseTypeDef",
     {
         "CreateTemplateMessageBody": CreateTemplateMessageBodyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateExportJobRequestRequestTypeDef = TypedDict(
     "CreateExportJobRequestRequestTypeDef",
     {
         "ApplicationId": str,
@@ -3813,46 +3783,46 @@
     },
 )
 
 CreateInAppTemplateResponseTypeDef = TypedDict(
     "CreateInAppTemplateResponseTypeDef",
     {
         "TemplateCreateMessageBody": TemplateCreateMessageBodyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateRecommenderConfigurationRequestRequestTypeDef = TypedDict(
     "CreateRecommenderConfigurationRequestRequestTypeDef",
     {
         "CreateRecommenderConfiguration": CreateRecommenderConfigurationTypeDef,
     },
 )
 
 CreateRecommenderConfigurationResponseTypeDef = TypedDict(
     "CreateRecommenderConfigurationResponseTypeDef",
     {
         "RecommenderConfigurationResponse": RecommenderConfigurationResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteRecommenderConfigurationResponseTypeDef = TypedDict(
     "DeleteRecommenderConfigurationResponseTypeDef",
     {
         "RecommenderConfigurationResponse": RecommenderConfigurationResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRecommenderConfigurationResponseTypeDef = TypedDict(
     "GetRecommenderConfigurationResponseTypeDef",
     {
         "RecommenderConfigurationResponse": RecommenderConfigurationResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredListRecommenderConfigurationsResponseTypeDef = TypedDict(
     "_RequiredListRecommenderConfigurationsResponseTypeDef",
     {
         "Item": List[RecommenderConfigurationResponseTypeDef],
@@ -3862,27 +3832,25 @@
     "_OptionalListRecommenderConfigurationsResponseTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
-
 class ListRecommenderConfigurationsResponseTypeDef(
     _RequiredListRecommenderConfigurationsResponseTypeDef,
     _OptionalListRecommenderConfigurationsResponseTypeDef,
 ):
     pass
 
-
 UpdateRecommenderConfigurationResponseTypeDef = TypedDict(
     "UpdateRecommenderConfigurationResponseTypeDef",
     {
         "RecommenderConfigurationResponse": RecommenderConfigurationResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateSmsTemplateRequestRequestTypeDef = TypedDict(
     "CreateSmsTemplateRequestRequestTypeDef",
     {
         "SMSTemplateRequest": SMSTemplateRequestTypeDef,
@@ -3902,21 +3870,19 @@
     {
         "CreateNewVersion": bool,
         "Version": str,
     },
     total=False,
 )
 
-
 class UpdateSmsTemplateRequestRequestTypeDef(
     _RequiredUpdateSmsTemplateRequestRequestTypeDef, _OptionalUpdateSmsTemplateRequestRequestTypeDef
 ):
     pass
 
-
 CreateVoiceTemplateRequestRequestTypeDef = TypedDict(
     "CreateVoiceTemplateRequestRequestTypeDef",
     {
         "TemplateName": str,
         "VoiceTemplateRequest": VoiceTemplateRequestTypeDef,
     },
 )
@@ -3933,22 +3899,20 @@
     {
         "CreateNewVersion": bool,
         "Version": str,
     },
     total=False,
 )
 
-
 class UpdateVoiceTemplateRequestRequestTypeDef(
     _RequiredUpdateVoiceTemplateRequestRequestTypeDef,
     _OptionalUpdateVoiceTemplateRequestRequestTypeDef,
 ):
     pass
 
-
 CustomMessageActivityTypeDef = TypedDict(
     "CustomMessageActivityTypeDef",
     {
         "DeliveryUri": str,
         "EndpointTypes": Sequence[EndpointTypesElementType],
         "MessageConfig": JourneyCustomMessageTypeDef,
         "NextActivity": str,
@@ -3997,243 +3961,241 @@
         "tags": Dict[str, str],
         "TemplateDescription": str,
         "Version": str,
     },
     total=False,
 )
 
-
 class PushNotificationTemplateResponseTypeDef(
     _RequiredPushNotificationTemplateResponseTypeDef,
     _OptionalPushNotificationTemplateResponseTypeDef,
 ):
     pass
 
-
 DeleteEmailChannelResponseTypeDef = TypedDict(
     "DeleteEmailChannelResponseTypeDef",
     {
         "EmailChannelResponse": EmailChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetEmailChannelResponseTypeDef = TypedDict(
     "GetEmailChannelResponseTypeDef",
     {
         "EmailChannelResponse": EmailChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateEmailChannelResponseTypeDef = TypedDict(
     "UpdateEmailChannelResponseTypeDef",
     {
         "EmailChannelResponse": EmailChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteEmailTemplateResponseTypeDef = TypedDict(
     "DeleteEmailTemplateResponseTypeDef",
     {
         "MessageBody": MessageBodyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteInAppTemplateResponseTypeDef = TypedDict(
     "DeleteInAppTemplateResponseTypeDef",
     {
         "MessageBody": MessageBodyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeletePushTemplateResponseTypeDef = TypedDict(
     "DeletePushTemplateResponseTypeDef",
     {
         "MessageBody": MessageBodyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteSmsTemplateResponseTypeDef = TypedDict(
     "DeleteSmsTemplateResponseTypeDef",
     {
         "MessageBody": MessageBodyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteVoiceTemplateResponseTypeDef = TypedDict(
     "DeleteVoiceTemplateResponseTypeDef",
     {
         "MessageBody": MessageBodyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateEmailTemplateResponseTypeDef = TypedDict(
     "UpdateEmailTemplateResponseTypeDef",
     {
         "MessageBody": MessageBodyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateEndpointResponseTypeDef = TypedDict(
     "UpdateEndpointResponseTypeDef",
     {
         "MessageBody": MessageBodyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateEndpointsBatchResponseTypeDef = TypedDict(
     "UpdateEndpointsBatchResponseTypeDef",
     {
         "MessageBody": MessageBodyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateInAppTemplateResponseTypeDef = TypedDict(
     "UpdateInAppTemplateResponseTypeDef",
     {
         "MessageBody": MessageBodyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdatePushTemplateResponseTypeDef = TypedDict(
     "UpdatePushTemplateResponseTypeDef",
     {
         "MessageBody": MessageBodyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateSmsTemplateResponseTypeDef = TypedDict(
     "UpdateSmsTemplateResponseTypeDef",
     {
         "MessageBody": MessageBodyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateTemplateActiveVersionResponseTypeDef = TypedDict(
     "UpdateTemplateActiveVersionResponseTypeDef",
     {
         "MessageBody": MessageBodyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateVoiceTemplateResponseTypeDef = TypedDict(
     "UpdateVoiceTemplateResponseTypeDef",
     {
         "MessageBody": MessageBodyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteEventStreamResponseTypeDef = TypedDict(
     "DeleteEventStreamResponseTypeDef",
     {
         "EventStream": EventStreamTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetEventStreamResponseTypeDef = TypedDict(
     "GetEventStreamResponseTypeDef",
     {
         "EventStream": EventStreamTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutEventStreamResponseTypeDef = TypedDict(
     "PutEventStreamResponseTypeDef",
     {
         "EventStream": EventStreamTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteGcmChannelResponseTypeDef = TypedDict(
     "DeleteGcmChannelResponseTypeDef",
     {
         "GCMChannelResponse": GCMChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetGcmChannelResponseTypeDef = TypedDict(
     "GetGcmChannelResponseTypeDef",
     {
         "GCMChannelResponse": GCMChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateGcmChannelResponseTypeDef = TypedDict(
     "UpdateGcmChannelResponseTypeDef",
     {
         "GCMChannelResponse": GCMChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteSmsChannelResponseTypeDef = TypedDict(
     "DeleteSmsChannelResponseTypeDef",
     {
         "SMSChannelResponse": SMSChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSmsChannelResponseTypeDef = TypedDict(
     "GetSmsChannelResponseTypeDef",
     {
         "SMSChannelResponse": SMSChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateSmsChannelResponseTypeDef = TypedDict(
     "UpdateSmsChannelResponseTypeDef",
     {
         "SMSChannelResponse": SMSChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteVoiceChannelResponseTypeDef = TypedDict(
     "DeleteVoiceChannelResponseTypeDef",
     {
         "VoiceChannelResponse": VoiceChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetVoiceChannelResponseTypeDef = TypedDict(
     "GetVoiceChannelResponseTypeDef",
     {
         "VoiceChannelResponse": VoiceChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateVoiceChannelResponseTypeDef = TypedDict(
     "UpdateVoiceChannelResponseTypeDef",
     {
         "VoiceChannelResponse": VoiceChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateEmailChannelRequestRequestTypeDef = TypedDict(
     "UpdateEmailChannelRequestRequestTypeDef",
     {
         "ApplicationId": str,
@@ -4252,15 +4214,15 @@
     total=False,
 )
 
 GetEmailTemplateResponseTypeDef = TypedDict(
     "GetEmailTemplateResponseTypeDef",
     {
         "EmailTemplateResponse": EmailTemplateResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EndpointBatchItemTypeDef = TypedDict(
     "EndpointBatchItemTypeDef",
     {
         "Address": str,
@@ -4348,21 +4310,19 @@
     {
         "RequestId": str,
         "Result": Dict[str, Dict[str, EndpointMessageResultTypeDef]],
     },
     total=False,
 )
 
-
 class SendUsersMessageResponseTypeDef(
     _RequiredSendUsersMessageResponseTypeDef, _OptionalSendUsersMessageResponseTypeDef
 ):
     pass
 
-
 EventDimensionsTypeDef = TypedDict(
     "EventDimensionsTypeDef",
     {
         "Attributes": Mapping[str, AttributeDimensionTypeDef],
         "EventType": SetDimensionTypeDef,
         "Metrics": Mapping[str, MetricDimensionTypeDef],
     },
@@ -4409,19 +4369,17 @@
         "Metrics": Mapping[str, float],
         "SdkName": str,
         "Session": SessionTypeDef,
     },
     total=False,
 )
 
-
 class EventTypeDef(_RequiredEventTypeDef, _OptionalEventTypeDef):
     pass
 
-
 _RequiredExportJobResponseTypeDef = TypedDict(
     "_RequiredExportJobResponseTypeDef",
     {
         "ApplicationId": str,
         "CreationDate": str,
         "Definition": ExportJobResourceTypeDef,
         "Id": str,
@@ -4439,21 +4397,19 @@
         "TotalFailures": int,
         "TotalPieces": int,
         "TotalProcessed": int,
     },
     total=False,
 )
 
-
 class ExportJobResponseTypeDef(
     _RequiredExportJobResponseTypeDef, _OptionalExportJobResponseTypeDef
 ):
     pass
 
-
 UpdateGcmChannelRequestRequestTypeDef = TypedDict(
     "UpdateGcmChannelRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "GCMChannelRequest": GCMChannelRequestTypeDef,
     },
 )
@@ -4468,50 +4424,66 @@
     "_OptionalGPSPointDimensionTypeDef",
     {
         "RangeInKilometers": float,
     },
     total=False,
 )
 
-
 class GPSPointDimensionTypeDef(
     _RequiredGPSPointDimensionTypeDef, _OptionalGPSPointDimensionTypeDef
 ):
     pass
 
-
 GetJourneyExecutionActivityMetricsResponseTypeDef = TypedDict(
     "GetJourneyExecutionActivityMetricsResponseTypeDef",
     {
         "JourneyExecutionActivityMetricsResponse": JourneyExecutionActivityMetricsResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetJourneyExecutionMetricsResponseTypeDef = TypedDict(
     "GetJourneyExecutionMetricsResponseTypeDef",
     {
         "JourneyExecutionMetricsResponse": JourneyExecutionMetricsResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetJourneyRunExecutionActivityMetricsResponseTypeDef = TypedDict(
+    "GetJourneyRunExecutionActivityMetricsResponseTypeDef",
+    {
+        "JourneyRunExecutionActivityMetricsResponse": (
+            JourneyRunExecutionActivityMetricsResponseTypeDef
+        ),
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetJourneyRunExecutionMetricsResponseTypeDef = TypedDict(
+    "GetJourneyRunExecutionMetricsResponseTypeDef",
+    {
+        "JourneyRunExecutionMetricsResponse": JourneyRunExecutionMetricsResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSmsTemplateResponseTypeDef = TypedDict(
     "GetSmsTemplateResponseTypeDef",
     {
         "SMSTemplateResponse": SMSTemplateResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetVoiceTemplateResponseTypeDef = TypedDict(
     "GetVoiceTemplateResponseTypeDef",
     {
         "VoiceTemplateResponse": VoiceTemplateResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredImportJobResponseTypeDef = TypedDict(
     "_RequiredImportJobResponseTypeDef",
     {
         "ApplicationId": str,
@@ -4532,21 +4504,19 @@
         "TotalFailures": int,
         "TotalPieces": int,
         "TotalProcessed": int,
     },
     total=False,
 )
 
-
 class ImportJobResponseTypeDef(
     _RequiredImportJobResponseTypeDef, _OptionalImportJobResponseTypeDef
 ):
     pass
 
-
 InAppMessageButtonTypeDef = TypedDict(
     "InAppMessageButtonTypeDef",
     {
         "Android": OverrideButtonConfigurationTypeDef,
         "DefaultConfig": DefaultButtonConfigurationTypeDef,
         "IOS": OverrideButtonConfigurationTypeDef,
         "Web": OverrideButtonConfigurationTypeDef,
@@ -4561,14 +4531,33 @@
         "NextActivity": str,
         "TemplateName": str,
         "TemplateVersion": str,
     },
     total=False,
 )
 
+_RequiredJourneyRunsResponseTypeDef = TypedDict(
+    "_RequiredJourneyRunsResponseTypeDef",
+    {
+        "Item": List[JourneyRunResponseTypeDef],
+    },
+)
+_OptionalJourneyRunsResponseTypeDef = TypedDict(
+    "_OptionalJourneyRunsResponseTypeDef",
+    {
+        "NextToken": str,
+    },
+    total=False,
+)
+
+class JourneyRunsResponseTypeDef(
+    _RequiredJourneyRunsResponseTypeDef, _OptionalJourneyRunsResponseTypeDef
+):
+    pass
+
 SMSMessageActivityTypeDef = TypedDict(
     "SMSMessageActivityTypeDef",
     {
         "MessageConfig": JourneySMSMessageTypeDef,
         "NextActivity": str,
         "TemplateName": str,
         "TemplateVersion": str,
@@ -4585,15 +4574,15 @@
     },
 )
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "TagsModel": TagsModelTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
@@ -4613,31 +4602,29 @@
         "EndpointResult": Dict[str, EndpointMessageResultTypeDef],
         "RequestId": str,
         "Result": Dict[str, MessageResultTypeDef],
     },
     total=False,
 )
 
-
 class MessageResponseTypeDef(_RequiredMessageResponseTypeDef, _OptionalMessageResponseTypeDef):
     pass
 
-
 PhoneNumberValidateRequestRequestTypeDef = TypedDict(
     "PhoneNumberValidateRequestRequestTypeDef",
     {
         "NumberValidateRequest": NumberValidateRequestTypeDef,
     },
 )
 
 PhoneNumberValidateResponseTypeDef = TypedDict(
     "PhoneNumberValidateResponseTypeDef",
     {
         "NumberValidateResponse": NumberValidateResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OpenHoursTypeDef = TypedDict(
     "OpenHoursTypeDef",
     {
         "EMAIL": Mapping[DayOfWeekType, Sequence[OpenHoursRuleTypeDef]],
@@ -4746,21 +4733,19 @@
     "_OptionalTemplatesResponseTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
-
 class TemplatesResponseTypeDef(
     _RequiredTemplatesResponseTypeDef, _OptionalTemplatesResponseTypeDef
 ):
     pass
 
-
 _RequiredTemplateVersionsResponseTypeDef = TypedDict(
     "_RequiredTemplateVersionsResponseTypeDef",
     {
         "Item": List[TemplateVersionResponseTypeDef],
     },
 )
 _OptionalTemplateVersionsResponseTypeDef = TypedDict(
@@ -4769,21 +4754,19 @@
         "Message": str,
         "NextToken": str,
         "RequestID": str,
     },
     total=False,
 )
 
-
 class TemplateVersionsResponseTypeDef(
     _RequiredTemplateVersionsResponseTypeDef, _OptionalTemplateVersionsResponseTypeDef
 ):
     pass
 
-
 UpdateRecommenderConfigurationRequestRequestTypeDef = TypedDict(
     "UpdateRecommenderConfigurationRequestRequestTypeDef",
     {
         "RecommenderId": str,
         "UpdateRecommenderConfiguration": UpdateRecommenderConfigurationTypeDef,
     },
 )
@@ -4796,15 +4779,15 @@
     },
 )
 
 VerifyOTPMessageResponseTypeDef = TypedDict(
     "VerifyOTPMessageResponseTypeDef",
     {
         "VerificationResponse": VerificationResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 VerifyOTPMessageRequestRequestTypeDef = TypedDict(
     "VerifyOTPMessageRequestRequestTypeDef",
     {
         "ApplicationId": str,
@@ -4812,39 +4795,39 @@
     },
 )
 
 GetCampaignActivitiesResponseTypeDef = TypedDict(
     "GetCampaignActivitiesResponseTypeDef",
     {
         "ActivitiesResponse": ActivitiesResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAppsResponseTypeDef = TypedDict(
     "GetAppsResponseTypeDef",
     {
         "ApplicationsResponse": ApplicationsResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetApplicationSettingsResponseTypeDef = TypedDict(
     "GetApplicationSettingsResponseTypeDef",
     {
         "ApplicationSettingsResource": ApplicationSettingsResourceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateApplicationSettingsResponseTypeDef = TypedDict(
     "UpdateApplicationSettingsResponseTypeDef",
     {
         "ApplicationSettingsResource": ApplicationSettingsResourceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateApplicationSettingsRequestRequestTypeDef = TypedDict(
     "UpdateApplicationSettingsRequestRequestTypeDef",
     {
         "ApplicationId": str,
@@ -4852,23 +4835,23 @@
     },
 )
 
 GetChannelsResponseTypeDef = TypedDict(
     "GetChannelsResponseTypeDef",
     {
         "ChannelsResponse": ChannelsResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRecommenderConfigurationsResponseTypeDef = TypedDict(
     "GetRecommenderConfigurationsResponseTypeDef",
     {
         "ListRecommenderConfigurationsResponse": ListRecommenderConfigurationsResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreatePushTemplateRequestRequestTypeDef = TypedDict(
     "CreatePushTemplateRequestRequestTypeDef",
     {
         "PushNotificationTemplateRequest": PushNotificationTemplateRequestTypeDef,
@@ -4888,27 +4871,25 @@
     {
         "CreateNewVersion": bool,
         "Version": str,
     },
     total=False,
 )
 
-
 class UpdatePushTemplateRequestRequestTypeDef(
     _RequiredUpdatePushTemplateRequestRequestTypeDef,
     _OptionalUpdatePushTemplateRequestRequestTypeDef,
 ):
     pass
 
-
 GetPushTemplateResponseTypeDef = TypedDict(
     "GetPushTemplateResponseTypeDef",
     {
         "PushNotificationTemplateResponse": PushNotificationTemplateResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EndpointBatchRequestTypeDef = TypedDict(
     "EndpointBatchRequestTypeDef",
     {
         "Item": Sequence[EndpointBatchItemTypeDef],
@@ -4924,38 +4905,38 @@
     },
 )
 
 DeleteEndpointResponseTypeDef = TypedDict(
     "DeleteEndpointResponseTypeDef",
     {
         "EndpointResponse": EndpointResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EndpointsResponseTypeDef = TypedDict(
     "EndpointsResponseTypeDef",
     {
         "Item": List[EndpointResponseTypeDef],
     },
 )
 
 GetEndpointResponseTypeDef = TypedDict(
     "GetEndpointResponseTypeDef",
     {
         "EndpointResponse": EndpointResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SendUsersMessagesResponseTypeDef = TypedDict(
     "SendUsersMessagesResponseTypeDef",
     {
         "SendUsersMessageResponse": SendUsersMessageResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CampaignEventFilterTypeDef = TypedDict(
     "CampaignEventFilterTypeDef",
     {
         "Dimensions": EventDimensionsTypeDef,
@@ -4996,15 +4977,15 @@
     },
 )
 
 CreateExportJobResponseTypeDef = TypedDict(
     "CreateExportJobResponseTypeDef",
     {
         "ExportJobResponse": ExportJobResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredExportJobsResponseTypeDef = TypedDict(
     "_RequiredExportJobsResponseTypeDef",
     {
         "Item": List[ExportJobResponseTypeDef],
@@ -5014,26 +4995,24 @@
     "_OptionalExportJobsResponseTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
-
 class ExportJobsResponseTypeDef(
     _RequiredExportJobsResponseTypeDef, _OptionalExportJobsResponseTypeDef
 ):
     pass
 
-
 GetExportJobResponseTypeDef = TypedDict(
     "GetExportJobResponseTypeDef",
     {
         "ExportJobResponse": ExportJobResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SegmentLocationTypeDef = TypedDict(
     "SegmentLocationTypeDef",
     {
         "Country": SetDimensionTypeDef,
@@ -5042,23 +5021,23 @@
     total=False,
 )
 
 CreateImportJobResponseTypeDef = TypedDict(
     "CreateImportJobResponseTypeDef",
     {
         "ImportJobResponse": ImportJobResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetImportJobResponseTypeDef = TypedDict(
     "GetImportJobResponseTypeDef",
     {
         "ImportJobResponse": ImportJobResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredImportJobsResponseTypeDef = TypedDict(
     "_RequiredImportJobsResponseTypeDef",
     {
         "Item": List[ImportJobResponseTypeDef],
@@ -5068,47 +5047,53 @@
     "_OptionalImportJobsResponseTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
-
 class ImportJobsResponseTypeDef(
     _RequiredImportJobsResponseTypeDef, _OptionalImportJobsResponseTypeDef
 ):
     pass
 
-
 InAppMessageContentTypeDef = TypedDict(
     "InAppMessageContentTypeDef",
     {
         "BackgroundColor": str,
         "BodyConfig": InAppMessageBodyConfigTypeDef,
         "HeaderConfig": InAppMessageHeaderConfigTypeDef,
         "ImageUrl": str,
         "PrimaryBtn": InAppMessageButtonTypeDef,
         "SecondaryBtn": InAppMessageButtonTypeDef,
     },
     total=False,
 )
 
+GetJourneyRunsResponseTypeDef = TypedDict(
+    "GetJourneyRunsResponseTypeDef",
+    {
+        "JourneyRunsResponse": JourneyRunsResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 SendMessagesResponseTypeDef = TypedDict(
     "SendMessagesResponseTypeDef",
     {
         "MessageResponse": MessageResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SendOTPMessageResponseTypeDef = TypedDict(
     "SendOTPMessageResponseTypeDef",
     {
         "MessageResponse": MessageResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BaseKpiResultTypeDef = TypedDict(
     "BaseKpiResultTypeDef",
     {
         "Rows": List[ResultRowTypeDef],
@@ -5129,23 +5114,23 @@
     total=False,
 )
 
 ListTemplatesResponseTypeDef = TypedDict(
     "ListTemplatesResponseTypeDef",
     {
         "TemplatesResponse": TemplatesResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTemplateVersionsResponseTypeDef = TypedDict(
     "ListTemplateVersionsResponseTypeDef",
     {
         "TemplateVersionsResponse": TemplateVersionsResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateEndpointsBatchRequestRequestTypeDef = TypedDict(
     "UpdateEndpointsBatchRequestRequestTypeDef",
     {
         "ApplicationId": str,
@@ -5153,23 +5138,23 @@
     },
 )
 
 DeleteUserEndpointsResponseTypeDef = TypedDict(
     "DeleteUserEndpointsResponseTypeDef",
     {
         "EndpointsResponse": EndpointsResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetUserEndpointsResponseTypeDef = TypedDict(
     "GetUserEndpointsResponseTypeDef",
     {
         "EndpointsResponse": EndpointsResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InAppCampaignScheduleTypeDef = TypedDict(
     "InAppCampaignScheduleTypeDef",
     {
         "EndDate": str,
@@ -5194,56 +5179,54 @@
         "IsLocalTime": bool,
         "QuietTime": QuietTimeTypeDef,
         "Timezone": str,
     },
     total=False,
 )
 
-
 class ScheduleTypeDef(_RequiredScheduleTypeDef, _OptionalScheduleTypeDef):
     pass
 
-
 EventStartConditionTypeDef = TypedDict(
     "EventStartConditionTypeDef",
     {
         "EventFilter": EventFilterTypeDef,
         "SegmentId": str,
     },
     total=False,
 )
 
 PutEventsResponseTypeDef = TypedDict(
     "PutEventsResponseTypeDef",
     {
         "EventsResponse": EventsResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EventsRequestTypeDef = TypedDict(
     "EventsRequestTypeDef",
     {
         "BatchItem": Mapping[str, EventsBatchTypeDef],
     },
 )
 
 GetExportJobsResponseTypeDef = TypedDict(
     "GetExportJobsResponseTypeDef",
     {
         "ExportJobsResponse": ExportJobsResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSegmentExportJobsResponseTypeDef = TypedDict(
     "GetSegmentExportJobsResponseTypeDef",
     {
         "ExportJobsResponse": ExportJobsResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SegmentDimensionsTypeDef = TypedDict(
     "SegmentDimensionsTypeDef",
     {
         "Attributes": Mapping[str, AttributeDimensionTypeDef],
@@ -5256,23 +5239,23 @@
     total=False,
 )
 
 GetImportJobsResponseTypeDef = TypedDict(
     "GetImportJobsResponseTypeDef",
     {
         "ImportJobsResponse": ImportJobsResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSegmentImportJobsResponseTypeDef = TypedDict(
     "GetSegmentImportJobsResponseTypeDef",
     {
         "ImportJobsResponse": ImportJobsResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CampaignInAppMessageTypeDef = TypedDict(
     "CampaignInAppMessageTypeDef",
     {
         "Body": str,
@@ -5324,21 +5307,19 @@
         "tags": Dict[str, str],
         "TemplateDescription": str,
         "Version": str,
     },
     total=False,
 )
 
-
 class InAppTemplateResponseTypeDef(
     _RequiredInAppTemplateResponseTypeDef, _OptionalInAppTemplateResponseTypeDef
 ):
     pass
 
-
 _RequiredApplicationDateRangeKpiResponseTypeDef = TypedDict(
     "_RequiredApplicationDateRangeKpiResponseTypeDef",
     {
         "ApplicationId": str,
         "EndTime": datetime,
         "KpiName": str,
         "KpiResult": BaseKpiResultTypeDef,
@@ -5349,21 +5330,19 @@
     "_OptionalApplicationDateRangeKpiResponseTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
-
 class ApplicationDateRangeKpiResponseTypeDef(
     _RequiredApplicationDateRangeKpiResponseTypeDef, _OptionalApplicationDateRangeKpiResponseTypeDef
 ):
     pass
 
-
 _RequiredCampaignDateRangeKpiResponseTypeDef = TypedDict(
     "_RequiredCampaignDateRangeKpiResponseTypeDef",
     {
         "ApplicationId": str,
         "CampaignId": str,
         "EndTime": datetime,
         "KpiName": str,
@@ -5375,21 +5354,19 @@
     "_OptionalCampaignDateRangeKpiResponseTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
-
 class CampaignDateRangeKpiResponseTypeDef(
     _RequiredCampaignDateRangeKpiResponseTypeDef, _OptionalCampaignDateRangeKpiResponseTypeDef
 ):
     pass
 
-
 _RequiredJourneyDateRangeKpiResponseTypeDef = TypedDict(
     "_RequiredJourneyDateRangeKpiResponseTypeDef",
     {
         "ApplicationId": str,
         "EndTime": datetime,
         "JourneyId": str,
         "KpiName": str,
@@ -5401,21 +5378,19 @@
     "_OptionalJourneyDateRangeKpiResponseTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
-
 class JourneyDateRangeKpiResponseTypeDef(
     _RequiredJourneyDateRangeKpiResponseTypeDef, _OptionalJourneyDateRangeKpiResponseTypeDef
 ):
     pass
 
-
 DirectMessageConfigurationTypeDef = TypedDict(
     "DirectMessageConfigurationTypeDef",
     {
         "ADMMessage": ADMMessageTypeDef,
         "APNSMessage": APNSMessageTypeDef,
         "BaiduMessage": BaiduMessageTypeDef,
         "DefaultMessage": DefaultMessageTypeDef,
@@ -5518,51 +5493,49 @@
     {
         "CreateNewVersion": bool,
         "Version": str,
     },
     total=False,
 )
 
-
 class UpdateInAppTemplateRequestRequestTypeDef(
     _RequiredUpdateInAppTemplateRequestRequestTypeDef,
     _OptionalUpdateInAppTemplateRequestRequestTypeDef,
 ):
     pass
 
-
 GetInAppTemplateResponseTypeDef = TypedDict(
     "GetInAppTemplateResponseTypeDef",
     {
         "InAppTemplateResponse": InAppTemplateResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetApplicationDateRangeKpiResponseTypeDef = TypedDict(
     "GetApplicationDateRangeKpiResponseTypeDef",
     {
         "ApplicationDateRangeKpiResponse": ApplicationDateRangeKpiResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCampaignDateRangeKpiResponseTypeDef = TypedDict(
     "GetCampaignDateRangeKpiResponseTypeDef",
     {
         "CampaignDateRangeKpiResponse": CampaignDateRangeKpiResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetJourneyDateRangeKpiResponseTypeDef = TypedDict(
     "GetJourneyDateRangeKpiResponseTypeDef",
     {
         "JourneyDateRangeKpiResponse": JourneyDateRangeKpiResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredMessageRequestTypeDef = TypedDict(
     "_RequiredMessageRequestTypeDef",
     {
         "MessageConfiguration": DirectMessageConfigurationTypeDef,
@@ -5576,19 +5549,17 @@
         "Endpoints": Mapping[str, EndpointSendConfigurationTypeDef],
         "TemplateConfiguration": TemplateConfigurationTypeDef,
         "TraceId": str,
     },
     total=False,
 )
 
-
 class MessageRequestTypeDef(_RequiredMessageRequestTypeDef, _OptionalMessageRequestTypeDef):
     pass
 
-
 _RequiredSendUsersMessageRequestTypeDef = TypedDict(
     "_RequiredSendUsersMessageRequestTypeDef",
     {
         "MessageConfiguration": DirectMessageConfigurationTypeDef,
         "Users": Mapping[str, EndpointSendConfigurationTypeDef],
     },
 )
@@ -5598,21 +5569,19 @@
         "Context": Mapping[str, str],
         "TemplateConfiguration": TemplateConfigurationTypeDef,
         "TraceId": str,
     },
     total=False,
 )
 
-
 class SendUsersMessageRequestTypeDef(
     _RequiredSendUsersMessageRequestTypeDef, _OptionalSendUsersMessageRequestTypeDef
 ):
     pass
 
-
 SegmentGroupListTypeDef = TypedDict(
     "SegmentGroupListTypeDef",
     {
         "Groups": Sequence[SegmentGroupTypeDef],
         "Include": IncludeType,
     },
     total=False,
@@ -5653,21 +5622,19 @@
         "TemplateConfiguration": TemplateConfigurationTypeDef,
         "TreatmentDescription": str,
         "TreatmentName": str,
     },
     total=False,
 )
 
-
 class TreatmentResourceTypeDef(
     _RequiredTreatmentResourceTypeDef, _OptionalTreatmentResourceTypeDef
 ):
     pass
 
-
 _RequiredWriteTreatmentResourceTypeDef = TypedDict(
     "_RequiredWriteTreatmentResourceTypeDef",
     {
         "SizePercent": int,
     },
 )
 _OptionalWriteTreatmentResourceTypeDef = TypedDict(
@@ -5679,21 +5646,19 @@
         "TemplateConfiguration": TemplateConfigurationTypeDef,
         "TreatmentDescription": str,
         "TreatmentName": str,
     },
     total=False,
 )
 
-
 class WriteTreatmentResourceTypeDef(
     _RequiredWriteTreatmentResourceTypeDef, _OptionalWriteTreatmentResourceTypeDef
 ):
     pass
 
-
 InAppMessagesResponseTypeDef = TypedDict(
     "InAppMessagesResponseTypeDef",
     {
         "InAppMessageCampaigns": List[InAppMessageCampaignTypeDef],
     },
     total=False,
 )
@@ -5734,19 +5699,17 @@
         "SegmentGroups": SegmentGroupListTypeDef,
         "tags": Dict[str, str],
         "Version": int,
     },
     total=False,
 )
 
-
 class SegmentResponseTypeDef(_RequiredSegmentResponseTypeDef, _OptionalSegmentResponseTypeDef):
     pass
 
-
 WriteSegmentRequestTypeDef = TypedDict(
     "WriteSegmentRequestTypeDef",
     {
         "Dimensions": SegmentDimensionsTypeDef,
         "Name": str,
         "SegmentGroups": SegmentGroupListTypeDef,
         "tags": Mapping[str, str],
@@ -5808,19 +5771,17 @@
         "TreatmentName": str,
         "Version": int,
         "Priority": int,
     },
     total=False,
 )
 
-
 class CampaignResponseTypeDef(_RequiredCampaignResponseTypeDef, _OptionalCampaignResponseTypeDef):
     pass
 
-
 WriteCampaignRequestTypeDef = TypedDict(
     "WriteCampaignRequestTypeDef",
     {
         "AdditionalTreatments": Sequence[WriteTreatmentResourceTypeDef],
         "CustomDeliveryConfiguration": CustomDeliveryConfigurationTypeDef,
         "Description": str,
         "HoldoutPercent": int,
@@ -5841,47 +5802,47 @@
     total=False,
 )
 
 GetInAppMessagesResponseTypeDef = TypedDict(
     "GetInAppMessagesResponseTypeDef",
     {
         "InAppMessagesResponse": InAppMessagesResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateSegmentResponseTypeDef = TypedDict(
     "CreateSegmentResponseTypeDef",
     {
         "SegmentResponse": SegmentResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteSegmentResponseTypeDef = TypedDict(
     "DeleteSegmentResponseTypeDef",
     {
         "SegmentResponse": SegmentResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSegmentResponseTypeDef = TypedDict(
     "GetSegmentResponseTypeDef",
     {
         "SegmentResponse": SegmentResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSegmentVersionResponseTypeDef = TypedDict(
     "GetSegmentVersionResponseTypeDef",
     {
         "SegmentResponse": SegmentResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSegmentsResponseTypeDef = TypedDict(
     "_RequiredSegmentsResponseTypeDef",
     {
         "Item": List[SegmentResponseTypeDef],
@@ -5891,24 +5852,22 @@
     "_OptionalSegmentsResponseTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
-
 class SegmentsResponseTypeDef(_RequiredSegmentsResponseTypeDef, _OptionalSegmentsResponseTypeDef):
     pass
 
-
 UpdateSegmentResponseTypeDef = TypedDict(
     "UpdateSegmentResponseTypeDef",
     {
         "SegmentResponse": SegmentResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateSegmentRequestRequestTypeDef = TypedDict(
     "CreateSegmentRequestRequestTypeDef",
     {
         "ApplicationId": str,
@@ -5953,58 +5912,56 @@
     "_OptionalCampaignsResponseTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
-
 class CampaignsResponseTypeDef(
     _RequiredCampaignsResponseTypeDef, _OptionalCampaignsResponseTypeDef
 ):
     pass
 
-
 CreateCampaignResponseTypeDef = TypedDict(
     "CreateCampaignResponseTypeDef",
     {
         "CampaignResponse": CampaignResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteCampaignResponseTypeDef = TypedDict(
     "DeleteCampaignResponseTypeDef",
     {
         "CampaignResponse": CampaignResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCampaignResponseTypeDef = TypedDict(
     "GetCampaignResponseTypeDef",
     {
         "CampaignResponse": CampaignResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCampaignVersionResponseTypeDef = TypedDict(
     "GetCampaignVersionResponseTypeDef",
     {
         "CampaignResponse": CampaignResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateCampaignResponseTypeDef = TypedDict(
     "UpdateCampaignResponseTypeDef",
     {
         "CampaignResponse": CampaignResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateCampaignRequestRequestTypeDef = TypedDict(
     "CreateCampaignRequestRequestTypeDef",
     {
         "ApplicationId": str,
@@ -6021,23 +5978,23 @@
     },
 )
 
 GetSegmentVersionsResponseTypeDef = TypedDict(
     "GetSegmentVersionsResponseTypeDef",
     {
         "SegmentsResponse": SegmentsResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSegmentsResponseTypeDef = TypedDict(
     "GetSegmentsResponseTypeDef",
     {
         "SegmentsResponse": SegmentsResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredJourneyResponseTypeDef = TypedDict(
     "_RequiredJourneyResponseTypeDef",
     {
         "ApplicationId": str,
@@ -6062,23 +6019,22 @@
         "tags": Dict[str, str],
         "WaitForQuietTime": bool,
         "RefreshOnSegmentUpdate": bool,
         "JourneyChannelSettings": JourneyChannelSettingsTypeDef,
         "SendingSchedule": bool,
         "OpenHours": OpenHoursTypeDef,
         "ClosedDays": ClosedDaysTypeDef,
+        "TimezoneEstimationMethods": List[TimezoneEstimationMethodsElementType],
     },
     total=False,
 )
 
-
 class JourneyResponseTypeDef(_RequiredJourneyResponseTypeDef, _OptionalJourneyResponseTypeDef):
     pass
 
-
 _RequiredWriteJourneyRequestTypeDef = TypedDict(
     "_RequiredWriteJourneyRequestTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalWriteJourneyRequestTypeDef = TypedDict(
@@ -6097,62 +6053,61 @@
         "State": StateType,
         "WaitForQuietTime": bool,
         "RefreshOnSegmentUpdate": bool,
         "JourneyChannelSettings": JourneyChannelSettingsTypeDef,
         "SendingSchedule": bool,
         "OpenHours": OpenHoursTypeDef,
         "ClosedDays": ClosedDaysTypeDef,
+        "TimezoneEstimationMethods": Sequence[TimezoneEstimationMethodsElementType],
     },
     total=False,
 )
 
-
 class WriteJourneyRequestTypeDef(
     _RequiredWriteJourneyRequestTypeDef, _OptionalWriteJourneyRequestTypeDef
 ):
     pass
 
-
 GetCampaignVersionsResponseTypeDef = TypedDict(
     "GetCampaignVersionsResponseTypeDef",
     {
         "CampaignsResponse": CampaignsResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCampaignsResponseTypeDef = TypedDict(
     "GetCampaignsResponseTypeDef",
     {
         "CampaignsResponse": CampaignsResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateJourneyResponseTypeDef = TypedDict(
     "CreateJourneyResponseTypeDef",
     {
         "JourneyResponse": JourneyResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteJourneyResponseTypeDef = TypedDict(
     "DeleteJourneyResponseTypeDef",
     {
         "JourneyResponse": JourneyResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetJourneyResponseTypeDef = TypedDict(
     "GetJourneyResponseTypeDef",
     {
         "JourneyResponse": JourneyResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredJourneysResponseTypeDef = TypedDict(
     "_RequiredJourneysResponseTypeDef",
     {
         "Item": List[JourneyResponseTypeDef],
@@ -6162,32 +6117,30 @@
     "_OptionalJourneysResponseTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
-
 class JourneysResponseTypeDef(_RequiredJourneysResponseTypeDef, _OptionalJourneysResponseTypeDef):
     pass
 
-
 UpdateJourneyResponseTypeDef = TypedDict(
     "UpdateJourneyResponseTypeDef",
     {
         "JourneyResponse": JourneyResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateJourneyStateResponseTypeDef = TypedDict(
     "UpdateJourneyStateResponseTypeDef",
     {
         "JourneyResponse": JourneyResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateJourneyRequestRequestTypeDef = TypedDict(
     "CreateJourneyRequestRequestTypeDef",
     {
         "ApplicationId": str,
@@ -6204,10 +6157,10 @@
     },
 )
 
 ListJourneysResponseTypeDef = TypedDict(
     "ListJourneysResponseTypeDef",
     {
         "JourneysResponse": JourneysResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-pinpoint-2.5.0.post1/types_aiobotocore_pinpoint/type_defs.pyi` & `types-aiobotocore-pinpoint-2.5.1/types_aiobotocore_pinpoint/type_defs.py`

 * *Files 5% similar despite different names*

```diff
@@ -30,31 +30,34 @@
     DurationType,
     EndpointTypesElementType,
     FilterTypeType,
     FormatType,
     FrequencyType,
     IncludeType,
     JobStatusType,
+    JourneyRunStatusType,
     LayoutType,
     MessageTypeType,
     ModeType,
     OperatorType,
     RecencyTypeType,
     SegmentTypeType,
     SourceTypeType,
     StateType,
     TemplateTypeType,
+    TimezoneEstimationMethodsElementType,
     TypeType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "ADMChannelRequestTypeDef",
     "ADMChannelResponseTypeDef",
     "ADMMessageTypeDef",
     "APNSChannelRequestTypeDef",
     "APNSChannelResponseTypeDef",
     "APNSMessageTypeDef",
@@ -84,15 +87,14 @@
     "CampaignStateTypeDef",
     "CustomDeliveryConfigurationTypeDef",
     "CampaignSmsMessageTypeDef",
     "ChannelResponseTypeDef",
     "ClosedDaysRuleTypeDef",
     "WaitTimeTypeDef",
     "CreateApplicationRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "EmailTemplateRequestTypeDef",
     "CreateTemplateMessageBodyTypeDef",
     "ExportJobRequestTypeDef",
     "ImportJobRequestTypeDef",
     "TemplateCreateMessageBodyTypeDef",
     "CreateRecommenderConfigurationTypeDef",
     "RecommenderConfigurationResponseTypeDef",
@@ -135,14 +137,15 @@
     "GCMMessageTypeDef",
     "SMSMessageTypeDef",
     "VoiceMessageTypeDef",
     "EmailChannelRequestTypeDef",
     "JourneyEmailMessageTypeDef",
     "RawEmailTypeDef",
     "EmailTemplateResponseTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EndpointDemographicTypeDef",
     "EndpointLocationTypeDef",
     "EndpointUserTypeDef",
     "EndpointItemResponseTypeDef",
     "EndpointMessageResultTypeDef",
     "EndpointSendConfigurationTypeDef",
     "MetricDimensionTypeDef",
@@ -182,14 +185,19 @@
     "GetInAppTemplateRequestRequestTypeDef",
     "GetJourneyDateRangeKpiRequestRequestTypeDef",
     "GetJourneyExecutionActivityMetricsRequestRequestTypeDef",
     "JourneyExecutionActivityMetricsResponseTypeDef",
     "GetJourneyExecutionMetricsRequestRequestTypeDef",
     "JourneyExecutionMetricsResponseTypeDef",
     "GetJourneyRequestRequestTypeDef",
+    "GetJourneyRunExecutionActivityMetricsRequestRequestTypeDef",
+    "JourneyRunExecutionActivityMetricsResponseTypeDef",
+    "GetJourneyRunExecutionMetricsRequestRequestTypeDef",
+    "JourneyRunExecutionMetricsResponseTypeDef",
+    "GetJourneyRunsRequestRequestTypeDef",
     "GetPushTemplateRequestRequestTypeDef",
     "GetRecommenderConfigurationRequestRequestTypeDef",
     "GetRecommenderConfigurationsRequestRequestTypeDef",
     "GetSegmentExportJobsRequestRequestTypeDef",
     "GetSegmentImportJobsRequestRequestTypeDef",
     "GetSegmentRequestRequestTypeDef",
     "GetSegmentVersionRequestRequestTypeDef",
@@ -206,14 +214,15 @@
     "InAppMessageBodyConfigTypeDef",
     "OverrideButtonConfigurationTypeDef",
     "InAppMessageHeaderConfigTypeDef",
     "JourneyChannelSettingsTypeDef",
     "JourneyLimitsTypeDef",
     "JourneyPushMessageTypeDef",
     "JourneyScheduleTypeDef",
+    "JourneyRunResponseTypeDef",
     "JourneySMSMessageTypeDef",
     "JourneyStateRequestTypeDef",
     "ListJourneysRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "TagsModelTypeDef",
     "ListTemplateVersionsRequestRequestTypeDef",
     "ListTemplatesRequestRequestTypeDef",
@@ -222,14 +231,15 @@
     "NumberValidateRequestTypeDef",
     "NumberValidateResponseTypeDef",
     "OpenHoursRuleTypeDef",
     "WriteEventStreamTypeDef",
     "RandomSplitEntryTypeDef",
     "RecencyDimensionTypeDef",
     "UpdateAttributesRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "ResultRowValueTypeDef",
     "SMSChannelRequestTypeDef",
     "SegmentConditionTypeDef",
     "SegmentReferenceTypeDef",
     "SegmentImportResourceTypeDef",
     "SendOTPMessageRequestParametersTypeDef",
     "SimpleEmailPartTypeDef",
@@ -239,50 +249,49 @@
     "TemplateVersionResponseTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateRecommenderConfigurationTypeDef",
     "VoiceChannelRequestTypeDef",
     "VerificationResponseTypeDef",
     "VerifyOTPMessageRequestParametersTypeDef",
     "UpdateAdmChannelRequestRequestTypeDef",
+    "DeleteAdmChannelResponseTypeDef",
+    "GetAdmChannelResponseTypeDef",
+    "UpdateAdmChannelResponseTypeDef",
     "UpdateApnsChannelRequestRequestTypeDef",
+    "DeleteApnsChannelResponseTypeDef",
+    "GetApnsChannelResponseTypeDef",
+    "UpdateApnsChannelResponseTypeDef",
     "UpdateApnsSandboxChannelRequestRequestTypeDef",
+    "DeleteApnsSandboxChannelResponseTypeDef",
+    "GetApnsSandboxChannelResponseTypeDef",
+    "UpdateApnsSandboxChannelResponseTypeDef",
     "UpdateApnsVoipChannelRequestRequestTypeDef",
+    "DeleteApnsVoipChannelResponseTypeDef",
+    "GetApnsVoipChannelResponseTypeDef",
+    "UpdateApnsVoipChannelResponseTypeDef",
     "UpdateApnsVoipSandboxChannelRequestRequestTypeDef",
+    "DeleteApnsVoipSandboxChannelResponseTypeDef",
+    "GetApnsVoipSandboxChannelResponseTypeDef",
+    "UpdateApnsVoipSandboxChannelResponseTypeDef",
     "ActivitiesResponseTypeDef",
     "ApplicationsResponseTypeDef",
+    "CreateAppResponseTypeDef",
+    "DeleteAppResponseTypeDef",
+    "GetAppResponseTypeDef",
     "ApplicationSettingsResourceTypeDef",
     "WriteApplicationSettingsRequestTypeDef",
+    "RemoveAttributesResponseTypeDef",
     "UpdateBaiduChannelRequestRequestTypeDef",
+    "DeleteBaiduChannelResponseTypeDef",
+    "GetBaiduChannelResponseTypeDef",
+    "UpdateBaiduChannelResponseTypeDef",
     "ChannelsResponseTypeDef",
     "ClosedDaysTypeDef",
     "WaitActivityTypeDef",
     "CreateAppRequestRequestTypeDef",
-    "CreateAppResponseTypeDef",
-    "DeleteAdmChannelResponseTypeDef",
-    "DeleteApnsChannelResponseTypeDef",
-    "DeleteApnsSandboxChannelResponseTypeDef",
-    "DeleteApnsVoipChannelResponseTypeDef",
-    "DeleteApnsVoipSandboxChannelResponseTypeDef",
-    "DeleteAppResponseTypeDef",
-    "DeleteBaiduChannelResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetAdmChannelResponseTypeDef",
-    "GetApnsChannelResponseTypeDef",
-    "GetApnsSandboxChannelResponseTypeDef",
-    "GetApnsVoipChannelResponseTypeDef",
-    "GetApnsVoipSandboxChannelResponseTypeDef",
-    "GetAppResponseTypeDef",
-    "GetBaiduChannelResponseTypeDef",
-    "RemoveAttributesResponseTypeDef",
-    "UpdateAdmChannelResponseTypeDef",
-    "UpdateApnsChannelResponseTypeDef",
-    "UpdateApnsSandboxChannelResponseTypeDef",
-    "UpdateApnsVoipChannelResponseTypeDef",
-    "UpdateApnsVoipSandboxChannelResponseTypeDef",
-    "UpdateBaiduChannelResponseTypeDef",
     "CreateEmailTemplateRequestRequestTypeDef",
     "UpdateEmailTemplateRequestRequestTypeDef",
     "CreateEmailTemplateResponseTypeDef",
     "CreatePushTemplateResponseTypeDef",
     "CreateSmsTemplateResponseTypeDef",
     "CreateVoiceTemplateResponseTypeDef",
     "CreateExportJobRequestRequestTypeDef",
@@ -342,19 +351,22 @@
     "ItemResponseTypeDef",
     "EventTypeDef",
     "ExportJobResponseTypeDef",
     "UpdateGcmChannelRequestRequestTypeDef",
     "GPSPointDimensionTypeDef",
     "GetJourneyExecutionActivityMetricsResponseTypeDef",
     "GetJourneyExecutionMetricsResponseTypeDef",
+    "GetJourneyRunExecutionActivityMetricsResponseTypeDef",
+    "GetJourneyRunExecutionMetricsResponseTypeDef",
     "GetSmsTemplateResponseTypeDef",
     "GetVoiceTemplateResponseTypeDef",
     "ImportJobResponseTypeDef",
     "InAppMessageButtonTypeDef",
     "PushMessageActivityTypeDef",
+    "JourneyRunsResponseTypeDef",
     "SMSMessageActivityTypeDef",
     "UpdateJourneyStateRequestRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "MessageResponseTypeDef",
     "PhoneNumberValidateRequestRequestTypeDef",
     "PhoneNumberValidateResponseTypeDef",
@@ -400,14 +412,15 @@
     "ExportJobsResponseTypeDef",
     "GetExportJobResponseTypeDef",
     "SegmentLocationTypeDef",
     "CreateImportJobResponseTypeDef",
     "GetImportJobResponseTypeDef",
     "ImportJobsResponseTypeDef",
     "InAppMessageContentTypeDef",
+    "GetJourneyRunsResponseTypeDef",
     "SendMessagesResponseTypeDef",
     "SendOTPMessageResponseTypeDef",
     "BaseKpiResultTypeDef",
     "EmailMessageTypeDef",
     "ListTemplatesResponseTypeDef",
     "ListTemplateVersionsResponseTypeDef",
     "UpdateEndpointsBatchRequestRequestTypeDef",
@@ -505,19 +518,21 @@
     "_OptionalADMChannelRequestTypeDef",
     {
         "Enabled": bool,
     },
     total=False,
 )
 
+
 class ADMChannelRequestTypeDef(
     _RequiredADMChannelRequestTypeDef, _OptionalADMChannelRequestTypeDef
 ):
     pass
 
+
 _RequiredADMChannelResponseTypeDef = TypedDict(
     "_RequiredADMChannelResponseTypeDef",
     {
         "Platform": str,
     },
 )
 _OptionalADMChannelResponseTypeDef = TypedDict(
@@ -532,19 +547,21 @@
         "LastModifiedBy": str,
         "LastModifiedDate": str,
         "Version": int,
     },
     total=False,
 )
 
+
 class ADMChannelResponseTypeDef(
     _RequiredADMChannelResponseTypeDef, _OptionalADMChannelResponseTypeDef
 ):
     pass
 
+
 ADMMessageTypeDef = TypedDict(
     "ADMMessageTypeDef",
     {
         "Action": ActionType,
         "Body": str,
         "ConsolidationKey": str,
         "Data": Mapping[str, str],
@@ -599,19 +616,21 @@
         "LastModifiedBy": str,
         "LastModifiedDate": str,
         "Version": int,
     },
     total=False,
 )
 
+
 class APNSChannelResponseTypeDef(
     _RequiredAPNSChannelResponseTypeDef, _OptionalAPNSChannelResponseTypeDef
 ):
     pass
 
+
 APNSMessageTypeDef = TypedDict(
     "APNSMessageTypeDef",
     {
         "APNSPushType": str,
         "Action": ActionType,
         "Badge": int,
         "Body": str,
@@ -682,19 +701,21 @@
         "LastModifiedBy": str,
         "LastModifiedDate": str,
         "Version": int,
     },
     total=False,
 )
 
+
 class APNSSandboxChannelResponseTypeDef(
     _RequiredAPNSSandboxChannelResponseTypeDef, _OptionalAPNSSandboxChannelResponseTypeDef
 ):
     pass
 
+
 APNSVoipChannelRequestTypeDef = TypedDict(
     "APNSVoipChannelRequestTypeDef",
     {
         "BundleId": str,
         "Certificate": str,
         "DefaultAuthenticationMethod": str,
         "Enabled": bool,
@@ -726,19 +747,21 @@
         "LastModifiedBy": str,
         "LastModifiedDate": str,
         "Version": int,
     },
     total=False,
 )
 
+
 class APNSVoipChannelResponseTypeDef(
     _RequiredAPNSVoipChannelResponseTypeDef, _OptionalAPNSVoipChannelResponseTypeDef
 ):
     pass
 
+
 APNSVoipSandboxChannelRequestTypeDef = TypedDict(
     "APNSVoipSandboxChannelRequestTypeDef",
     {
         "BundleId": str,
         "Certificate": str,
         "DefaultAuthenticationMethod": str,
         "Enabled": bool,
@@ -770,19 +793,21 @@
         "LastModifiedBy": str,
         "LastModifiedDate": str,
         "Version": int,
     },
     total=False,
 )
 
+
 class APNSVoipSandboxChannelResponseTypeDef(
     _RequiredAPNSVoipSandboxChannelResponseTypeDef, _OptionalAPNSVoipSandboxChannelResponseTypeDef
 ):
     pass
 
+
 _RequiredActivityResponseTypeDef = TypedDict(
     "_RequiredActivityResponseTypeDef",
     {
         "ApplicationId": str,
         "CampaignId": str,
         "Id": str,
     },
@@ -796,21 +821,24 @@
         "Start": str,
         "State": str,
         "SuccessfulEndpointCount": int,
         "TimezonesCompletedCount": int,
         "TimezonesTotalCount": int,
         "TotalEndpointCount": int,
         "TreatmentId": str,
+        "ExecutionMetrics": Dict[str, str],
     },
     total=False,
 )
 
+
 class ActivityResponseTypeDef(_RequiredActivityResponseTypeDef, _OptionalActivityResponseTypeDef):
     pass
 
+
 ContactCenterActivityTypeDef = TypedDict(
     "ContactCenterActivityTypeDef",
     {
         "NextActivity": str,
     },
     total=False,
 )
@@ -825,17 +853,19 @@
     "_OptionalHoldoutActivityTypeDef",
     {
         "NextActivity": str,
     },
     total=False,
 )
 
+
 class HoldoutActivityTypeDef(_RequiredHoldoutActivityTypeDef, _OptionalHoldoutActivityTypeDef):
     pass
 
+
 AddressConfigurationTypeDef = TypedDict(
     "AddressConfigurationTypeDef",
     {
         "BodyOverride": str,
         "ChannelType": ChannelTypeType,
         "Context": Mapping[str, str],
         "RawContent": str,
@@ -874,19 +904,21 @@
     {
         "tags": Dict[str, str],
         "CreationDate": str,
     },
     total=False,
 )
 
+
 class ApplicationResponseTypeDef(
     _RequiredApplicationResponseTypeDef, _OptionalApplicationResponseTypeDef
 ):
     pass
 
+
 CampaignHookTypeDef = TypedDict(
     "CampaignHookTypeDef",
     {
         "LambdaFunctionName": str,
         "Mode": ModeType,
         "WebUrl": str,
     },
@@ -924,19 +956,21 @@
     "_OptionalAttributeDimensionTypeDef",
     {
         "AttributeType": AttributeTypeType,
     },
     total=False,
 )
 
+
 class AttributeDimensionTypeDef(
     _RequiredAttributeDimensionTypeDef, _OptionalAttributeDimensionTypeDef
 ):
     pass
 
+
 _RequiredAttributesResourceTypeDef = TypedDict(
     "_RequiredAttributesResourceTypeDef",
     {
         "ApplicationId": str,
         "AttributeType": str,
     },
 )
@@ -944,19 +978,21 @@
     "_OptionalAttributesResourceTypeDef",
     {
         "Attributes": List[str],
     },
     total=False,
 )
 
+
 class AttributesResourceTypeDef(
     _RequiredAttributesResourceTypeDef, _OptionalAttributesResourceTypeDef
 ):
     pass
 
+
 _RequiredBaiduChannelRequestTypeDef = TypedDict(
     "_RequiredBaiduChannelRequestTypeDef",
     {
         "ApiKey": str,
         "SecretKey": str,
     },
 )
@@ -964,19 +1000,21 @@
     "_OptionalBaiduChannelRequestTypeDef",
     {
         "Enabled": bool,
     },
     total=False,
 )
 
+
 class BaiduChannelRequestTypeDef(
     _RequiredBaiduChannelRequestTypeDef, _OptionalBaiduChannelRequestTypeDef
 ):
     pass
 
+
 _RequiredBaiduChannelResponseTypeDef = TypedDict(
     "_RequiredBaiduChannelResponseTypeDef",
     {
         "Credential": str,
         "Platform": str,
     },
 )
@@ -992,19 +1030,21 @@
         "LastModifiedBy": str,
         "LastModifiedDate": str,
         "Version": int,
     },
     total=False,
 )
 
+
 class BaiduChannelResponseTypeDef(
     _RequiredBaiduChannelResponseTypeDef, _OptionalBaiduChannelResponseTypeDef
 ):
     pass
 
+
 BaiduMessageTypeDef = TypedDict(
     "BaiduMessageTypeDef",
     {
         "Action": ActionType,
         "Body": str,
         "Data": Mapping[str, str],
         "IconReference": str,
@@ -1059,19 +1099,21 @@
     "_OptionalCustomDeliveryConfigurationTypeDef",
     {
         "EndpointTypes": Sequence[EndpointTypesElementType],
     },
     total=False,
 )
 
+
 class CustomDeliveryConfigurationTypeDef(
     _RequiredCustomDeliveryConfigurationTypeDef, _OptionalCustomDeliveryConfigurationTypeDef
 ):
     pass
 
+
 CampaignSmsMessageTypeDef = TypedDict(
     "CampaignSmsMessageTypeDef",
     {
         "Body": str,
         "MessageType": MessageTypeType,
         "OriginationNumber": str,
         "SenderId": str,
@@ -1126,29 +1168,20 @@
     "_OptionalCreateApplicationRequestTypeDef",
     {
         "tags": Mapping[str, str],
     },
     total=False,
 )
 
+
 class CreateApplicationRequestTypeDef(
     _RequiredCreateApplicationRequestTypeDef, _OptionalCreateApplicationRequestTypeDef
 ):
     pass
 
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
 
 EmailTemplateRequestTypeDef = TypedDict(
     "EmailTemplateRequestTypeDef",
     {
         "DefaultSubstitutions": str,
         "HtmlPart": str,
         "RecommenderId": str,
@@ -1182,17 +1215,19 @@
     {
         "SegmentId": str,
         "SegmentVersion": int,
     },
     total=False,
 )
 
+
 class ExportJobRequestTypeDef(_RequiredExportJobRequestTypeDef, _OptionalExportJobRequestTypeDef):
     pass
 
+
 _RequiredImportJobRequestTypeDef = TypedDict(
     "_RequiredImportJobRequestTypeDef",
     {
         "Format": FormatType,
         "RoleArn": str,
         "S3Url": str,
     },
@@ -1205,17 +1240,19 @@
         "RegisterEndpoints": bool,
         "SegmentId": str,
         "SegmentName": str,
     },
     total=False,
 )
 
+
 class ImportJobRequestTypeDef(_RequiredImportJobRequestTypeDef, _OptionalImportJobRequestTypeDef):
     pass
 
+
 TemplateCreateMessageBodyTypeDef = TypedDict(
     "TemplateCreateMessageBodyTypeDef",
     {
         "Arn": str,
         "Message": str,
         "RequestID": str,
     },
@@ -1239,19 +1276,21 @@
         "RecommendationTransformerUri": str,
         "RecommendationsDisplayName": str,
         "RecommendationsPerMessage": int,
     },
     total=False,
 )
 
+
 class CreateRecommenderConfigurationTypeDef(
     _RequiredCreateRecommenderConfigurationTypeDef, _OptionalCreateRecommenderConfigurationTypeDef
 ):
     pass
 
+
 _RequiredRecommenderConfigurationResponseTypeDef = TypedDict(
     "_RequiredRecommenderConfigurationResponseTypeDef",
     {
         "CreationDate": str,
         "Id": str,
         "LastModifiedDate": str,
         "RecommendationProviderRoleArn": str,
@@ -1268,20 +1307,22 @@
         "RecommendationTransformerUri": str,
         "RecommendationsDisplayName": str,
         "RecommendationsPerMessage": int,
     },
     total=False,
 )
 
+
 class RecommenderConfigurationResponseTypeDef(
     _RequiredRecommenderConfigurationResponseTypeDef,
     _OptionalRecommenderConfigurationResponseTypeDef,
 ):
     pass
 
+
 SMSTemplateRequestTypeDef = TypedDict(
     "SMSTemplateRequestTypeDef",
     {
         "Body": str,
         "DefaultSubstitutions": str,
         "RecommenderId": str,
         "tags": Mapping[str, str],
@@ -1325,19 +1366,21 @@
         "BorderRadius": int,
         "Link": str,
         "TextColor": str,
     },
     total=False,
 )
 
+
 class DefaultButtonConfigurationTypeDef(
     _RequiredDefaultButtonConfigurationTypeDef, _OptionalDefaultButtonConfigurationTypeDef
 ):
     pass
 
+
 DefaultMessageTypeDef = TypedDict(
     "DefaultMessageTypeDef",
     {
         "Body": str,
         "Substitutions": Mapping[str, Sequence[str]],
     },
     total=False,
@@ -1456,39 +1499,43 @@
         "MessagesPerSecond": int,
         "RoleArn": str,
         "Version": int,
     },
     total=False,
 )
 
+
 class EmailChannelResponseTypeDef(
     _RequiredEmailChannelResponseTypeDef, _OptionalEmailChannelResponseTypeDef
 ):
     pass
 
+
 _RequiredDeleteEmailTemplateRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteEmailTemplateRequestRequestTypeDef",
     {
         "TemplateName": str,
     },
 )
 _OptionalDeleteEmailTemplateRequestRequestTypeDef = TypedDict(
     "_OptionalDeleteEmailTemplateRequestRequestTypeDef",
     {
         "Version": str,
     },
     total=False,
 )
 
+
 class DeleteEmailTemplateRequestRequestTypeDef(
     _RequiredDeleteEmailTemplateRequestRequestTypeDef,
     _OptionalDeleteEmailTemplateRequestRequestTypeDef,
 ):
     pass
 
+
 MessageBodyTypeDef = TypedDict(
     "MessageBodyTypeDef",
     {
         "Message": str,
         "RequestID": str,
     },
     total=False,
@@ -1523,17 +1570,19 @@
         "ExternalId": str,
         "LastModifiedDate": str,
         "LastUpdatedBy": str,
     },
     total=False,
 )
 
+
 class EventStreamTypeDef(_RequiredEventStreamTypeDef, _OptionalEventStreamTypeDef):
     pass
 
+
 DeleteGcmChannelRequestRequestTypeDef = TypedDict(
     "DeleteGcmChannelRequestRequestTypeDef",
     {
         "ApplicationId": str,
     },
 )
 
@@ -1556,39 +1605,43 @@
         "LastModifiedBy": str,
         "LastModifiedDate": str,
         "Version": int,
     },
     total=False,
 )
 
+
 class GCMChannelResponseTypeDef(
     _RequiredGCMChannelResponseTypeDef, _OptionalGCMChannelResponseTypeDef
 ):
     pass
 
+
 _RequiredDeleteInAppTemplateRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteInAppTemplateRequestRequestTypeDef",
     {
         "TemplateName": str,
     },
 )
 _OptionalDeleteInAppTemplateRequestRequestTypeDef = TypedDict(
     "_OptionalDeleteInAppTemplateRequestRequestTypeDef",
     {
         "Version": str,
     },
     total=False,
 )
 
+
 class DeleteInAppTemplateRequestRequestTypeDef(
     _RequiredDeleteInAppTemplateRequestRequestTypeDef,
     _OptionalDeleteInAppTemplateRequestRequestTypeDef,
 ):
     pass
 
+
 DeleteJourneyRequestRequestTypeDef = TypedDict(
     "DeleteJourneyRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "JourneyId": str,
     },
 )
@@ -1603,20 +1656,22 @@
     "_OptionalDeletePushTemplateRequestRequestTypeDef",
     {
         "Version": str,
     },
     total=False,
 )
 
+
 class DeletePushTemplateRequestRequestTypeDef(
     _RequiredDeletePushTemplateRequestRequestTypeDef,
     _OptionalDeletePushTemplateRequestRequestTypeDef,
 ):
     pass
 
+
 DeleteRecommenderConfigurationRequestRequestTypeDef = TypedDict(
     "DeleteRecommenderConfigurationRequestRequestTypeDef",
     {
         "RecommenderId": str,
     },
 )
 
@@ -1657,38 +1712,42 @@
         "ShortCode": str,
         "TransactionalMessagesPerSecond": int,
         "Version": int,
     },
     total=False,
 )
 
+
 class SMSChannelResponseTypeDef(
     _RequiredSMSChannelResponseTypeDef, _OptionalSMSChannelResponseTypeDef
 ):
     pass
 
+
 _RequiredDeleteSmsTemplateRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteSmsTemplateRequestRequestTypeDef",
     {
         "TemplateName": str,
     },
 )
 _OptionalDeleteSmsTemplateRequestRequestTypeDef = TypedDict(
     "_OptionalDeleteSmsTemplateRequestRequestTypeDef",
     {
         "Version": str,
     },
     total=False,
 )
 
+
 class DeleteSmsTemplateRequestRequestTypeDef(
     _RequiredDeleteSmsTemplateRequestRequestTypeDef, _OptionalDeleteSmsTemplateRequestRequestTypeDef
 ):
     pass
 
+
 DeleteUserEndpointsRequestRequestTypeDef = TypedDict(
     "DeleteUserEndpointsRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "UserId": str,
     },
 )
@@ -1718,39 +1777,43 @@
         "LastModifiedBy": str,
         "LastModifiedDate": str,
         "Version": int,
     },
     total=False,
 )
 
+
 class VoiceChannelResponseTypeDef(
     _RequiredVoiceChannelResponseTypeDef, _OptionalVoiceChannelResponseTypeDef
 ):
     pass
 
+
 _RequiredDeleteVoiceTemplateRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteVoiceTemplateRequestRequestTypeDef",
     {
         "TemplateName": str,
     },
 )
 _OptionalDeleteVoiceTemplateRequestRequestTypeDef = TypedDict(
     "_OptionalDeleteVoiceTemplateRequestRequestTypeDef",
     {
         "Version": str,
     },
     total=False,
 )
 
+
 class DeleteVoiceTemplateRequestRequestTypeDef(
     _RequiredDeleteVoiceTemplateRequestRequestTypeDef,
     _OptionalDeleteVoiceTemplateRequestRequestTypeDef,
 ):
     pass
 
+
 GCMMessageTypeDef = TypedDict(
     "GCMMessageTypeDef",
     {
         "Action": ActionType,
         "Body": str,
         "CollapseKey": str,
         "Data": Mapping[str, str],
@@ -1812,19 +1875,21 @@
         "ConfigurationSet": str,
         "Enabled": bool,
         "RoleArn": str,
     },
     total=False,
 )
 
+
 class EmailChannelRequestTypeDef(
     _RequiredEmailChannelRequestTypeDef, _OptionalEmailChannelRequestTypeDef
 ):
     pass
 
+
 JourneyEmailMessageTypeDef = TypedDict(
     "JourneyEmailMessageTypeDef",
     {
         "FromAddress": str,
     },
     total=False,
 )
@@ -1858,19 +1923,28 @@
         "TemplateDescription": str,
         "TextPart": str,
         "Version": str,
     },
     total=False,
 )
 
+
 class EmailTemplateResponseTypeDef(
     _RequiredEmailTemplateResponseTypeDef, _OptionalEmailTemplateResponseTypeDef
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
 EndpointDemographicTypeDef = TypedDict(
     "EndpointDemographicTypeDef",
     {
         "AppVersion": str,
         "Locale": str,
         "Make": str,
         "Model": str,
@@ -1927,19 +2001,21 @@
         "MessageId": str,
         "StatusMessage": str,
         "UpdatedToken": str,
     },
     total=False,
 )
 
+
 class EndpointMessageResultTypeDef(
     _RequiredEndpointMessageResultTypeDef, _OptionalEndpointMessageResultTypeDef
 ):
     pass
 
+
 EndpointSendConfigurationTypeDef = TypedDict(
     "EndpointSendConfigurationTypeDef",
     {
         "BodyOverride": str,
         "Context": Mapping[str, str],
         "RawContent": str,
         "Substitutions": Mapping[str, Sequence[str]],
@@ -1966,17 +2042,19 @@
     "_OptionalSetDimensionTypeDef",
     {
         "DimensionType": DimensionTypeType,
     },
     total=False,
 )
 
+
 class SetDimensionTypeDef(_RequiredSetDimensionTypeDef, _OptionalSetDimensionTypeDef):
     pass
 
+
 EventItemResponseTypeDef = TypedDict(
     "EventItemResponseTypeDef",
     {
         "Message": str,
         "StatusCode": int,
     },
     total=False,
@@ -1994,17 +2072,19 @@
     {
         "Duration": int,
         "StopTimestamp": str,
     },
     total=False,
 )
 
+
 class SessionTypeDef(_RequiredSessionTypeDef, _OptionalSessionTypeDef):
     pass
 
+
 _RequiredExportJobResourceTypeDef = TypedDict(
     "_RequiredExportJobResourceTypeDef",
     {
         "RoleArn": str,
         "S3UrlPrefix": str,
     },
 )
@@ -2013,38 +2093,42 @@
     {
         "SegmentId": str,
         "SegmentVersion": int,
     },
     total=False,
 )
 
+
 class ExportJobResourceTypeDef(
     _RequiredExportJobResourceTypeDef, _OptionalExportJobResourceTypeDef
 ):
     pass
 
+
 _RequiredGCMChannelRequestTypeDef = TypedDict(
     "_RequiredGCMChannelRequestTypeDef",
     {
         "ApiKey": str,
     },
 )
 _OptionalGCMChannelRequestTypeDef = TypedDict(
     "_OptionalGCMChannelRequestTypeDef",
     {
         "Enabled": bool,
     },
     total=False,
 )
 
+
 class GCMChannelRequestTypeDef(
     _RequiredGCMChannelRequestTypeDef, _OptionalGCMChannelRequestTypeDef
 ):
     pass
 
+
 GPSCoordinatesTypeDef = TypedDict(
     "GPSCoordinatesTypeDef",
     {
         "Latitude": float,
         "Longitude": float,
     },
 )
@@ -2105,20 +2189,22 @@
         "NextToken": str,
         "PageSize": str,
         "StartTime": Union[datetime, str],
     },
     total=False,
 )
 
+
 class GetApplicationDateRangeKpiRequestRequestTypeDef(
     _RequiredGetApplicationDateRangeKpiRequestRequestTypeDef,
     _OptionalGetApplicationDateRangeKpiRequestRequestTypeDef,
 ):
     pass
 
+
 GetApplicationSettingsRequestRequestTypeDef = TypedDict(
     "GetApplicationSettingsRequestRequestTypeDef",
     {
         "ApplicationId": str,
     },
 )
 
@@ -2150,20 +2236,22 @@
     {
         "PageSize": str,
         "Token": str,
     },
     total=False,
 )
 
+
 class GetCampaignActivitiesRequestRequestTypeDef(
     _RequiredGetCampaignActivitiesRequestRequestTypeDef,
     _OptionalGetCampaignActivitiesRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredGetCampaignDateRangeKpiRequestRequestTypeDef = TypedDict(
     "_RequiredGetCampaignDateRangeKpiRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "CampaignId": str,
         "KpiName": str,
     },
@@ -2175,20 +2263,22 @@
         "NextToken": str,
         "PageSize": str,
         "StartTime": Union[datetime, str],
     },
     total=False,
 )
 
+
 class GetCampaignDateRangeKpiRequestRequestTypeDef(
     _RequiredGetCampaignDateRangeKpiRequestRequestTypeDef,
     _OptionalGetCampaignDateRangeKpiRequestRequestTypeDef,
 ):
     pass
 
+
 GetCampaignRequestRequestTypeDef = TypedDict(
     "GetCampaignRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "CampaignId": str,
     },
 )
@@ -2214,20 +2304,22 @@
     {
         "PageSize": str,
         "Token": str,
     },
     total=False,
 )
 
+
 class GetCampaignVersionsRequestRequestTypeDef(
     _RequiredGetCampaignVersionsRequestRequestTypeDef,
     _OptionalGetCampaignVersionsRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredGetCampaignsRequestRequestTypeDef = TypedDict(
     "_RequiredGetCampaignsRequestRequestTypeDef",
     {
         "ApplicationId": str,
     },
 )
 _OptionalGetCampaignsRequestRequestTypeDef = TypedDict(
@@ -2235,19 +2327,21 @@
     {
         "PageSize": str,
         "Token": str,
     },
     total=False,
 )
 
+
 class GetCampaignsRequestRequestTypeDef(
     _RequiredGetCampaignsRequestRequestTypeDef, _OptionalGetCampaignsRequestRequestTypeDef
 ):
     pass
 
+
 GetChannelsRequestRequestTypeDef = TypedDict(
     "GetChannelsRequestRequestTypeDef",
     {
         "ApplicationId": str,
     },
 )
 
@@ -2268,19 +2362,21 @@
     "_OptionalGetEmailTemplateRequestRequestTypeDef",
     {
         "Version": str,
     },
     total=False,
 )
 
+
 class GetEmailTemplateRequestRequestTypeDef(
     _RequiredGetEmailTemplateRequestRequestTypeDef, _OptionalGetEmailTemplateRequestRequestTypeDef
 ):
     pass
 
+
 GetEndpointRequestRequestTypeDef = TypedDict(
     "GetEndpointRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "EndpointId": str,
     },
 )
@@ -2311,19 +2407,21 @@
     {
         "PageSize": str,
         "Token": str,
     },
     total=False,
 )
 
+
 class GetExportJobsRequestRequestTypeDef(
     _RequiredGetExportJobsRequestRequestTypeDef, _OptionalGetExportJobsRequestRequestTypeDef
 ):
     pass
 
+
 GetGcmChannelRequestRequestTypeDef = TypedDict(
     "GetGcmChannelRequestRequestTypeDef",
     {
         "ApplicationId": str,
     },
 )
 
@@ -2346,19 +2444,21 @@
     {
         "PageSize": str,
         "Token": str,
     },
     total=False,
 )
 
+
 class GetImportJobsRequestRequestTypeDef(
     _RequiredGetImportJobsRequestRequestTypeDef, _OptionalGetImportJobsRequestRequestTypeDef
 ):
     pass
 
+
 GetInAppMessagesRequestRequestTypeDef = TypedDict(
     "GetInAppMessagesRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "EndpointId": str,
     },
 )
@@ -2373,19 +2473,21 @@
     "_OptionalGetInAppTemplateRequestRequestTypeDef",
     {
         "Version": str,
     },
     total=False,
 )
 
+
 class GetInAppTemplateRequestRequestTypeDef(
     _RequiredGetInAppTemplateRequestRequestTypeDef, _OptionalGetInAppTemplateRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredGetJourneyDateRangeKpiRequestRequestTypeDef = TypedDict(
     "_RequiredGetJourneyDateRangeKpiRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "JourneyId": str,
         "KpiName": str,
     },
@@ -2397,20 +2499,22 @@
         "NextToken": str,
         "PageSize": str,
         "StartTime": Union[datetime, str],
     },
     total=False,
 )
 
+
 class GetJourneyDateRangeKpiRequestRequestTypeDef(
     _RequiredGetJourneyDateRangeKpiRequestRequestTypeDef,
     _OptionalGetJourneyDateRangeKpiRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredGetJourneyExecutionActivityMetricsRequestRequestTypeDef = TypedDict(
     "_RequiredGetJourneyExecutionActivityMetricsRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "JourneyActivityId": str,
         "JourneyId": str,
     },
@@ -2420,20 +2524,22 @@
     {
         "NextToken": str,
         "PageSize": str,
     },
     total=False,
 )
 
+
 class GetJourneyExecutionActivityMetricsRequestRequestTypeDef(
     _RequiredGetJourneyExecutionActivityMetricsRequestRequestTypeDef,
     _OptionalGetJourneyExecutionActivityMetricsRequestRequestTypeDef,
 ):
     pass
 
+
 JourneyExecutionActivityMetricsResponseTypeDef = TypedDict(
     "JourneyExecutionActivityMetricsResponseTypeDef",
     {
         "ActivityType": str,
         "ApplicationId": str,
         "JourneyActivityId": str,
         "JourneyId": str,
@@ -2454,20 +2560,22 @@
     {
         "NextToken": str,
         "PageSize": str,
     },
     total=False,
 )
 
+
 class GetJourneyExecutionMetricsRequestRequestTypeDef(
     _RequiredGetJourneyExecutionMetricsRequestRequestTypeDef,
     _OptionalGetJourneyExecutionMetricsRequestRequestTypeDef,
 ):
     pass
 
+
 JourneyExecutionMetricsResponseTypeDef = TypedDict(
     "JourneyExecutionMetricsResponseTypeDef",
     {
         "ApplicationId": str,
         "JourneyId": str,
         "LastEvaluatedTime": str,
         "Metrics": Dict[str, str],
@@ -2478,33 +2586,133 @@
     "GetJourneyRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "JourneyId": str,
     },
 )
 
+_RequiredGetJourneyRunExecutionActivityMetricsRequestRequestTypeDef = TypedDict(
+    "_RequiredGetJourneyRunExecutionActivityMetricsRequestRequestTypeDef",
+    {
+        "ApplicationId": str,
+        "JourneyActivityId": str,
+        "JourneyId": str,
+        "RunId": str,
+    },
+)
+_OptionalGetJourneyRunExecutionActivityMetricsRequestRequestTypeDef = TypedDict(
+    "_OptionalGetJourneyRunExecutionActivityMetricsRequestRequestTypeDef",
+    {
+        "NextToken": str,
+        "PageSize": str,
+    },
+    total=False,
+)
+
+
+class GetJourneyRunExecutionActivityMetricsRequestRequestTypeDef(
+    _RequiredGetJourneyRunExecutionActivityMetricsRequestRequestTypeDef,
+    _OptionalGetJourneyRunExecutionActivityMetricsRequestRequestTypeDef,
+):
+    pass
+
+
+JourneyRunExecutionActivityMetricsResponseTypeDef = TypedDict(
+    "JourneyRunExecutionActivityMetricsResponseTypeDef",
+    {
+        "ActivityType": str,
+        "ApplicationId": str,
+        "JourneyActivityId": str,
+        "JourneyId": str,
+        "LastEvaluatedTime": str,
+        "Metrics": Dict[str, str],
+        "RunId": str,
+    },
+)
+
+_RequiredGetJourneyRunExecutionMetricsRequestRequestTypeDef = TypedDict(
+    "_RequiredGetJourneyRunExecutionMetricsRequestRequestTypeDef",
+    {
+        "ApplicationId": str,
+        "JourneyId": str,
+        "RunId": str,
+    },
+)
+_OptionalGetJourneyRunExecutionMetricsRequestRequestTypeDef = TypedDict(
+    "_OptionalGetJourneyRunExecutionMetricsRequestRequestTypeDef",
+    {
+        "NextToken": str,
+        "PageSize": str,
+    },
+    total=False,
+)
+
+
+class GetJourneyRunExecutionMetricsRequestRequestTypeDef(
+    _RequiredGetJourneyRunExecutionMetricsRequestRequestTypeDef,
+    _OptionalGetJourneyRunExecutionMetricsRequestRequestTypeDef,
+):
+    pass
+
+
+JourneyRunExecutionMetricsResponseTypeDef = TypedDict(
+    "JourneyRunExecutionMetricsResponseTypeDef",
+    {
+        "ApplicationId": str,
+        "JourneyId": str,
+        "LastEvaluatedTime": str,
+        "Metrics": Dict[str, str],
+        "RunId": str,
+    },
+)
+
+_RequiredGetJourneyRunsRequestRequestTypeDef = TypedDict(
+    "_RequiredGetJourneyRunsRequestRequestTypeDef",
+    {
+        "ApplicationId": str,
+        "JourneyId": str,
+    },
+)
+_OptionalGetJourneyRunsRequestRequestTypeDef = TypedDict(
+    "_OptionalGetJourneyRunsRequestRequestTypeDef",
+    {
+        "PageSize": str,
+        "Token": str,
+    },
+    total=False,
+)
+
+
+class GetJourneyRunsRequestRequestTypeDef(
+    _RequiredGetJourneyRunsRequestRequestTypeDef, _OptionalGetJourneyRunsRequestRequestTypeDef
+):
+    pass
+
+
 _RequiredGetPushTemplateRequestRequestTypeDef = TypedDict(
     "_RequiredGetPushTemplateRequestRequestTypeDef",
     {
         "TemplateName": str,
     },
 )
 _OptionalGetPushTemplateRequestRequestTypeDef = TypedDict(
     "_OptionalGetPushTemplateRequestRequestTypeDef",
     {
         "Version": str,
     },
     total=False,
 )
 
+
 class GetPushTemplateRequestRequestTypeDef(
     _RequiredGetPushTemplateRequestRequestTypeDef, _OptionalGetPushTemplateRequestRequestTypeDef
 ):
     pass
 
+
 GetRecommenderConfigurationRequestRequestTypeDef = TypedDict(
     "GetRecommenderConfigurationRequestRequestTypeDef",
     {
         "RecommenderId": str,
     },
 )
 
@@ -2529,20 +2737,22 @@
     {
         "PageSize": str,
         "Token": str,
     },
     total=False,
 )
 
+
 class GetSegmentExportJobsRequestRequestTypeDef(
     _RequiredGetSegmentExportJobsRequestRequestTypeDef,
     _OptionalGetSegmentExportJobsRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredGetSegmentImportJobsRequestRequestTypeDef = TypedDict(
     "_RequiredGetSegmentImportJobsRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "SegmentId": str,
     },
 )
@@ -2551,20 +2761,22 @@
     {
         "PageSize": str,
         "Token": str,
     },
     total=False,
 )
 
+
 class GetSegmentImportJobsRequestRequestTypeDef(
     _RequiredGetSegmentImportJobsRequestRequestTypeDef,
     _OptionalGetSegmentImportJobsRequestRequestTypeDef,
 ):
     pass
 
+
 GetSegmentRequestRequestTypeDef = TypedDict(
     "GetSegmentRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "SegmentId": str,
     },
 )
@@ -2590,20 +2802,22 @@
     {
         "PageSize": str,
         "Token": str,
     },
     total=False,
 )
 
+
 class GetSegmentVersionsRequestRequestTypeDef(
     _RequiredGetSegmentVersionsRequestRequestTypeDef,
     _OptionalGetSegmentVersionsRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredGetSegmentsRequestRequestTypeDef = TypedDict(
     "_RequiredGetSegmentsRequestRequestTypeDef",
     {
         "ApplicationId": str,
     },
 )
 _OptionalGetSegmentsRequestRequestTypeDef = TypedDict(
@@ -2611,19 +2825,21 @@
     {
         "PageSize": str,
         "Token": str,
     },
     total=False,
 )
 
+
 class GetSegmentsRequestRequestTypeDef(
     _RequiredGetSegmentsRequestRequestTypeDef, _OptionalGetSegmentsRequestRequestTypeDef
 ):
     pass
 
+
 GetSmsChannelRequestRequestTypeDef = TypedDict(
     "GetSmsChannelRequestRequestTypeDef",
     {
         "ApplicationId": str,
     },
 )
 
@@ -2637,19 +2853,21 @@
     "_OptionalGetSmsTemplateRequestRequestTypeDef",
     {
         "Version": str,
     },
     total=False,
 )
 
+
 class GetSmsTemplateRequestRequestTypeDef(
     _RequiredGetSmsTemplateRequestRequestTypeDef, _OptionalGetSmsTemplateRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredSMSTemplateResponseTypeDef = TypedDict(
     "_RequiredSMSTemplateResponseTypeDef",
     {
         "CreationDate": str,
         "LastModifiedDate": str,
         "TemplateName": str,
         "TemplateType": TemplateTypeType,
@@ -2665,19 +2883,21 @@
         "tags": Dict[str, str],
         "TemplateDescription": str,
         "Version": str,
     },
     total=False,
 )
 
+
 class SMSTemplateResponseTypeDef(
     _RequiredSMSTemplateResponseTypeDef, _OptionalSMSTemplateResponseTypeDef
 ):
     pass
 
+
 GetUserEndpointsRequestRequestTypeDef = TypedDict(
     "GetUserEndpointsRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "UserId": str,
     },
 )
@@ -2699,19 +2919,21 @@
     "_OptionalGetVoiceTemplateRequestRequestTypeDef",
     {
         "Version": str,
     },
     total=False,
 )
 
+
 class GetVoiceTemplateRequestRequestTypeDef(
     _RequiredGetVoiceTemplateRequestRequestTypeDef, _OptionalGetVoiceTemplateRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredVoiceTemplateResponseTypeDef = TypedDict(
     "_RequiredVoiceTemplateResponseTypeDef",
     {
         "CreationDate": str,
         "LastModifiedDate": str,
         "TemplateName": str,
         "TemplateType": TemplateTypeType,
@@ -2728,19 +2950,21 @@
         "TemplateDescription": str,
         "Version": str,
         "VoiceId": str,
     },
     total=False,
 )
 
+
 class VoiceTemplateResponseTypeDef(
     _RequiredVoiceTemplateResponseTypeDef, _OptionalVoiceTemplateResponseTypeDef
 ):
     pass
 
+
 _RequiredImportJobResourceTypeDef = TypedDict(
     "_RequiredImportJobResourceTypeDef",
     {
         "Format": FormatType,
         "RoleArn": str,
         "S3Url": str,
     },
@@ -2753,19 +2977,21 @@
         "RegisterEndpoints": bool,
         "SegmentId": str,
         "SegmentName": str,
     },
     total=False,
 )
 
+
 class ImportJobResourceTypeDef(
     _RequiredImportJobResourceTypeDef, _OptionalImportJobResourceTypeDef
 ):
     pass
 
+
 InAppMessageBodyConfigTypeDef = TypedDict(
     "InAppMessageBodyConfigTypeDef",
     {
         "Alignment": AlignmentType,
         "Body": str,
         "TextColor": str,
     },
@@ -2781,19 +3007,21 @@
     "_OptionalOverrideButtonConfigurationTypeDef",
     {
         "Link": str,
     },
     total=False,
 )
 
+
 class OverrideButtonConfigurationTypeDef(
     _RequiredOverrideButtonConfigurationTypeDef, _OptionalOverrideButtonConfigurationTypeDef
 ):
     pass
 
+
 InAppMessageHeaderConfigTypeDef = TypedDict(
     "InAppMessageHeaderConfigTypeDef",
     {
         "Alignment": AlignmentType,
         "Header": str,
         "TextColor": str,
     },
@@ -2833,14 +3061,24 @@
         "EndTime": Union[datetime, str],
         "StartTime": Union[datetime, str],
         "Timezone": str,
     },
     total=False,
 )
 
+JourneyRunResponseTypeDef = TypedDict(
+    "JourneyRunResponseTypeDef",
+    {
+        "CreationTime": str,
+        "LastUpdateTime": str,
+        "RunId": str,
+        "Status": JourneyRunStatusType,
+    },
+)
+
 JourneySMSMessageTypeDef = TypedDict(
     "JourneySMSMessageTypeDef",
     {
         "MessageType": MessageTypeType,
         "OriginationNumber": str,
         "SenderId": str,
         "EntityId": str,
@@ -2868,19 +3106,21 @@
     {
         "PageSize": str,
         "Token": str,
     },
     total=False,
 )
 
+
 class ListJourneysRequestRequestTypeDef(
     _RequiredListJourneysRequestRequestTypeDef, _OptionalListJourneysRequestRequestTypeDef
 ):
     pass
 
+
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
@@ -2903,20 +3143,22 @@
     {
         "NextToken": str,
         "PageSize": str,
     },
     total=False,
 )
 
+
 class ListTemplateVersionsRequestRequestTypeDef(
     _RequiredListTemplateVersionsRequestRequestTypeDef,
     _OptionalListTemplateVersionsRequestRequestTypeDef,
 ):
     pass
 
+
 ListTemplatesRequestRequestTypeDef = TypedDict(
     "ListTemplatesRequestRequestTypeDef",
     {
         "NextToken": str,
         "PageSize": str,
         "Prefix": str,
         "TemplateType": str,
@@ -2956,17 +3198,19 @@
         "MessageId": str,
         "StatusMessage": str,
         "UpdatedToken": str,
     },
     total=False,
 )
 
+
 class MessageResultTypeDef(_RequiredMessageResultTypeDef, _OptionalMessageResultTypeDef):
     pass
 
+
 NumberValidateRequestTypeDef = TypedDict(
     "NumberValidateRequestTypeDef",
     {
         "IsoCountryCode": str,
         "PhoneNumber": str,
     },
     total=False,
@@ -3031,14 +3275,25 @@
     "UpdateAttributesRequestTypeDef",
     {
         "Blacklist": Sequence[str],
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
 ResultRowValueTypeDef = TypedDict(
     "ResultRowValueTypeDef",
     {
         "Key": str,
         "Type": str,
         "Value": str,
     },
@@ -3071,17 +3326,19 @@
     "_OptionalSegmentReferenceTypeDef",
     {
         "Version": int,
     },
     total=False,
 )
 
+
 class SegmentReferenceTypeDef(_RequiredSegmentReferenceTypeDef, _OptionalSegmentReferenceTypeDef):
     pass
 
+
 _RequiredSegmentImportResourceTypeDef = TypedDict(
     "_RequiredSegmentImportResourceTypeDef",
     {
         "ExternalId": str,
         "Format": FormatType,
         "RoleArn": str,
         "S3Url": str,
@@ -3092,19 +3349,21 @@
     "_OptionalSegmentImportResourceTypeDef",
     {
         "ChannelCounts": Dict[str, int],
     },
     total=False,
 )
 
+
 class SegmentImportResourceTypeDef(
     _RequiredSegmentImportResourceTypeDef, _OptionalSegmentImportResourceTypeDef
 ):
     pass
 
+
 _RequiredSendOTPMessageRequestParametersTypeDef = TypedDict(
     "_RequiredSendOTPMessageRequestParametersTypeDef",
     {
         "BrandName": str,
         "Channel": str,
         "DestinationIdentity": str,
         "OriginationIdentity": str,
@@ -3120,19 +3379,21 @@
         "Language": str,
         "TemplateId": str,
         "ValidityPeriod": int,
     },
     total=False,
 )
 
+
 class SendOTPMessageRequestParametersTypeDef(
     _RequiredSendOTPMessageRequestParametersTypeDef, _OptionalSendOTPMessageRequestParametersTypeDef
 ):
     pass
 
+
 SimpleEmailPartTypeDef = TypedDict(
     "SimpleEmailPartTypeDef",
     {
         "Charset": str,
         "Data": str,
     },
     total=False,
@@ -3172,17 +3433,19 @@
         "tags": Dict[str, str],
         "TemplateDescription": str,
         "Version": str,
     },
     total=False,
 )
 
+
 class TemplateResponseTypeDef(_RequiredTemplateResponseTypeDef, _OptionalTemplateResponseTypeDef):
     pass
 
+
 _RequiredTemplateVersionResponseTypeDef = TypedDict(
     "_RequiredTemplateVersionResponseTypeDef",
     {
         "CreationDate": str,
         "LastModifiedDate": str,
         "TemplateName": str,
         "TemplateType": str,
@@ -3194,19 +3457,21 @@
         "DefaultSubstitutions": str,
         "TemplateDescription": str,
         "Version": str,
     },
     total=False,
 )
 
+
 class TemplateVersionResponseTypeDef(
     _RequiredTemplateVersionResponseTypeDef, _OptionalTemplateVersionResponseTypeDef
 ):
     pass
 
+
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
@@ -3228,19 +3493,21 @@
         "RecommendationTransformerUri": str,
         "RecommendationsDisplayName": str,
         "RecommendationsPerMessage": int,
     },
     total=False,
 )
 
+
 class UpdateRecommenderConfigurationTypeDef(
     _RequiredUpdateRecommenderConfigurationTypeDef, _OptionalUpdateRecommenderConfigurationTypeDef
 ):
     pass
 
+
 VoiceChannelRequestTypeDef = TypedDict(
     "VoiceChannelRequestTypeDef",
     {
         "Enabled": bool,
     },
     total=False,
 )
@@ -3266,331 +3533,328 @@
     "UpdateAdmChannelRequestRequestTypeDef",
     {
         "ADMChannelRequest": ADMChannelRequestTypeDef,
         "ApplicationId": str,
     },
 )
 
-UpdateApnsChannelRequestRequestTypeDef = TypedDict(
-    "UpdateApnsChannelRequestRequestTypeDef",
+DeleteAdmChannelResponseTypeDef = TypedDict(
+    "DeleteAdmChannelResponseTypeDef",
     {
-        "APNSChannelRequest": APNSChannelRequestTypeDef,
-        "ApplicationId": str,
+        "ADMChannelResponse": ADMChannelResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateApnsSandboxChannelRequestRequestTypeDef = TypedDict(
-    "UpdateApnsSandboxChannelRequestRequestTypeDef",
+GetAdmChannelResponseTypeDef = TypedDict(
+    "GetAdmChannelResponseTypeDef",
     {
-        "APNSSandboxChannelRequest": APNSSandboxChannelRequestTypeDef,
-        "ApplicationId": str,
+        "ADMChannelResponse": ADMChannelResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateApnsVoipChannelRequestRequestTypeDef = TypedDict(
-    "UpdateApnsVoipChannelRequestRequestTypeDef",
+UpdateAdmChannelResponseTypeDef = TypedDict(
+    "UpdateAdmChannelResponseTypeDef",
     {
-        "APNSVoipChannelRequest": APNSVoipChannelRequestTypeDef,
-        "ApplicationId": str,
+        "ADMChannelResponse": ADMChannelResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateApnsVoipSandboxChannelRequestRequestTypeDef = TypedDict(
-    "UpdateApnsVoipSandboxChannelRequestRequestTypeDef",
+UpdateApnsChannelRequestRequestTypeDef = TypedDict(
+    "UpdateApnsChannelRequestRequestTypeDef",
     {
-        "APNSVoipSandboxChannelRequest": APNSVoipSandboxChannelRequestTypeDef,
+        "APNSChannelRequest": APNSChannelRequestTypeDef,
         "ApplicationId": str,
     },
 )
 
-_RequiredActivitiesResponseTypeDef = TypedDict(
-    "_RequiredActivitiesResponseTypeDef",
+DeleteApnsChannelResponseTypeDef = TypedDict(
+    "DeleteApnsChannelResponseTypeDef",
     {
-        "Item": List[ActivityResponseTypeDef],
+        "APNSChannelResponse": APNSChannelResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalActivitiesResponseTypeDef = TypedDict(
-    "_OptionalActivitiesResponseTypeDef",
+
+GetApnsChannelResponseTypeDef = TypedDict(
+    "GetApnsChannelResponseTypeDef",
     {
-        "NextToken": str,
+        "APNSChannelResponse": APNSChannelResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-class ActivitiesResponseTypeDef(
-    _RequiredActivitiesResponseTypeDef, _OptionalActivitiesResponseTypeDef
-):
-    pass
-
-ApplicationsResponseTypeDef = TypedDict(
-    "ApplicationsResponseTypeDef",
+UpdateApnsChannelResponseTypeDef = TypedDict(
+    "UpdateApnsChannelResponseTypeDef",
     {
-        "Item": List[ApplicationResponseTypeDef],
-        "NextToken": str,
+        "APNSChannelResponse": APNSChannelResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-_RequiredApplicationSettingsResourceTypeDef = TypedDict(
-    "_RequiredApplicationSettingsResourceTypeDef",
+UpdateApnsSandboxChannelRequestRequestTypeDef = TypedDict(
+    "UpdateApnsSandboxChannelRequestRequestTypeDef",
     {
+        "APNSSandboxChannelRequest": APNSSandboxChannelRequestTypeDef,
         "ApplicationId": str,
     },
 )
-_OptionalApplicationSettingsResourceTypeDef = TypedDict(
-    "_OptionalApplicationSettingsResourceTypeDef",
+
+DeleteApnsSandboxChannelResponseTypeDef = TypedDict(
+    "DeleteApnsSandboxChannelResponseTypeDef",
     {
-        "CampaignHook": CampaignHookTypeDef,
-        "LastModifiedDate": str,
-        "Limits": CampaignLimitsTypeDef,
-        "QuietTime": QuietTimeTypeDef,
+        "APNSSandboxChannelResponse": APNSSandboxChannelResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-class ApplicationSettingsResourceTypeDef(
-    _RequiredApplicationSettingsResourceTypeDef, _OptionalApplicationSettingsResourceTypeDef
-):
-    pass
+GetApnsSandboxChannelResponseTypeDef = TypedDict(
+    "GetApnsSandboxChannelResponseTypeDef",
+    {
+        "APNSSandboxChannelResponse": APNSSandboxChannelResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
-WriteApplicationSettingsRequestTypeDef = TypedDict(
-    "WriteApplicationSettingsRequestTypeDef",
+UpdateApnsSandboxChannelResponseTypeDef = TypedDict(
+    "UpdateApnsSandboxChannelResponseTypeDef",
     {
-        "CampaignHook": CampaignHookTypeDef,
-        "CloudWatchMetricsEnabled": bool,
-        "EventTaggingEnabled": bool,
-        "Limits": CampaignLimitsTypeDef,
-        "QuietTime": QuietTimeTypeDef,
+        "APNSSandboxChannelResponse": APNSSandboxChannelResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-UpdateBaiduChannelRequestRequestTypeDef = TypedDict(
-    "UpdateBaiduChannelRequestRequestTypeDef",
+UpdateApnsVoipChannelRequestRequestTypeDef = TypedDict(
+    "UpdateApnsVoipChannelRequestRequestTypeDef",
     {
+        "APNSVoipChannelRequest": APNSVoipChannelRequestTypeDef,
         "ApplicationId": str,
-        "BaiduChannelRequest": BaiduChannelRequestTypeDef,
     },
 )
 
-ChannelsResponseTypeDef = TypedDict(
-    "ChannelsResponseTypeDef",
+DeleteApnsVoipChannelResponseTypeDef = TypedDict(
+    "DeleteApnsVoipChannelResponseTypeDef",
     {
-        "Channels": Dict[str, ChannelResponseTypeDef],
+        "APNSVoipChannelResponse": APNSVoipChannelResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ClosedDaysTypeDef = TypedDict(
-    "ClosedDaysTypeDef",
+GetApnsVoipChannelResponseTypeDef = TypedDict(
+    "GetApnsVoipChannelResponseTypeDef",
     {
-        "EMAIL": Sequence[ClosedDaysRuleTypeDef],
-        "SMS": Sequence[ClosedDaysRuleTypeDef],
-        "PUSH": Sequence[ClosedDaysRuleTypeDef],
-        "VOICE": Sequence[ClosedDaysRuleTypeDef],
-        "CUSTOM": Sequence[ClosedDaysRuleTypeDef],
+        "APNSVoipChannelResponse": APNSVoipChannelResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-WaitActivityTypeDef = TypedDict(
-    "WaitActivityTypeDef",
+UpdateApnsVoipChannelResponseTypeDef = TypedDict(
+    "UpdateApnsVoipChannelResponseTypeDef",
     {
-        "NextActivity": str,
-        "WaitTime": WaitTimeTypeDef,
+        "APNSVoipChannelResponse": APNSVoipChannelResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-CreateAppRequestRequestTypeDef = TypedDict(
-    "CreateAppRequestRequestTypeDef",
+UpdateApnsVoipSandboxChannelRequestRequestTypeDef = TypedDict(
+    "UpdateApnsVoipSandboxChannelRequestRequestTypeDef",
     {
-        "CreateApplicationRequest": CreateApplicationRequestTypeDef,
+        "APNSVoipSandboxChannelRequest": APNSVoipSandboxChannelRequestTypeDef,
+        "ApplicationId": str,
     },
 )
 
-CreateAppResponseTypeDef = TypedDict(
-    "CreateAppResponseTypeDef",
+DeleteApnsVoipSandboxChannelResponseTypeDef = TypedDict(
+    "DeleteApnsVoipSandboxChannelResponseTypeDef",
     {
-        "ApplicationResponse": ApplicationResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "APNSVoipSandboxChannelResponse": APNSVoipSandboxChannelResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteAdmChannelResponseTypeDef = TypedDict(
-    "DeleteAdmChannelResponseTypeDef",
+GetApnsVoipSandboxChannelResponseTypeDef = TypedDict(
+    "GetApnsVoipSandboxChannelResponseTypeDef",
     {
-        "ADMChannelResponse": ADMChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "APNSVoipSandboxChannelResponse": APNSVoipSandboxChannelResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteApnsChannelResponseTypeDef = TypedDict(
-    "DeleteApnsChannelResponseTypeDef",
+UpdateApnsVoipSandboxChannelResponseTypeDef = TypedDict(
+    "UpdateApnsVoipSandboxChannelResponseTypeDef",
     {
-        "APNSChannelResponse": APNSChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "APNSVoipSandboxChannelResponse": APNSVoipSandboxChannelResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteApnsSandboxChannelResponseTypeDef = TypedDict(
-    "DeleteApnsSandboxChannelResponseTypeDef",
+_RequiredActivitiesResponseTypeDef = TypedDict(
+    "_RequiredActivitiesResponseTypeDef",
     {
-        "APNSSandboxChannelResponse": APNSSandboxChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Item": List[ActivityResponseTypeDef],
     },
 )
-
-DeleteApnsVoipChannelResponseTypeDef = TypedDict(
-    "DeleteApnsVoipChannelResponseTypeDef",
+_OptionalActivitiesResponseTypeDef = TypedDict(
+    "_OptionalActivitiesResponseTypeDef",
     {
-        "APNSVoipChannelResponse": APNSVoipChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "NextToken": str,
     },
+    total=False,
 )
 
-DeleteApnsVoipSandboxChannelResponseTypeDef = TypedDict(
-    "DeleteApnsVoipSandboxChannelResponseTypeDef",
+
+class ActivitiesResponseTypeDef(
+    _RequiredActivitiesResponseTypeDef, _OptionalActivitiesResponseTypeDef
+):
+    pass
+
+
+ApplicationsResponseTypeDef = TypedDict(
+    "ApplicationsResponseTypeDef",
     {
-        "APNSVoipSandboxChannelResponse": APNSVoipSandboxChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Item": List[ApplicationResponseTypeDef],
+        "NextToken": str,
     },
+    total=False,
 )
 
-DeleteAppResponseTypeDef = TypedDict(
-    "DeleteAppResponseTypeDef",
+CreateAppResponseTypeDef = TypedDict(
+    "CreateAppResponseTypeDef",
     {
         "ApplicationResponse": ApplicationResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DeleteBaiduChannelResponseTypeDef = TypedDict(
-    "DeleteBaiduChannelResponseTypeDef",
+DeleteAppResponseTypeDef = TypedDict(
+    "DeleteAppResponseTypeDef",
     {
-        "BaiduChannelResponse": BaiduChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ApplicationResponse": ApplicationResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
+GetAppResponseTypeDef = TypedDict(
+    "GetAppResponseTypeDef",
     {
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ApplicationResponse": ApplicationResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetAdmChannelResponseTypeDef = TypedDict(
-    "GetAdmChannelResponseTypeDef",
+_RequiredApplicationSettingsResourceTypeDef = TypedDict(
+    "_RequiredApplicationSettingsResourceTypeDef",
     {
-        "ADMChannelResponse": ADMChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ApplicationId": str,
     },
 )
-
-GetApnsChannelResponseTypeDef = TypedDict(
-    "GetApnsChannelResponseTypeDef",
+_OptionalApplicationSettingsResourceTypeDef = TypedDict(
+    "_OptionalApplicationSettingsResourceTypeDef",
     {
-        "APNSChannelResponse": APNSChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "CampaignHook": CampaignHookTypeDef,
+        "LastModifiedDate": str,
+        "Limits": CampaignLimitsTypeDef,
+        "QuietTime": QuietTimeTypeDef,
     },
+    total=False,
 )
 
-GetApnsSandboxChannelResponseTypeDef = TypedDict(
-    "GetApnsSandboxChannelResponseTypeDef",
+
+class ApplicationSettingsResourceTypeDef(
+    _RequiredApplicationSettingsResourceTypeDef, _OptionalApplicationSettingsResourceTypeDef
+):
+    pass
+
+
+WriteApplicationSettingsRequestTypeDef = TypedDict(
+    "WriteApplicationSettingsRequestTypeDef",
     {
-        "APNSSandboxChannelResponse": APNSSandboxChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "CampaignHook": CampaignHookTypeDef,
+        "CloudWatchMetricsEnabled": bool,
+        "EventTaggingEnabled": bool,
+        "Limits": CampaignLimitsTypeDef,
+        "QuietTime": QuietTimeTypeDef,
     },
+    total=False,
 )
 
-GetApnsVoipChannelResponseTypeDef = TypedDict(
-    "GetApnsVoipChannelResponseTypeDef",
+RemoveAttributesResponseTypeDef = TypedDict(
+    "RemoveAttributesResponseTypeDef",
     {
-        "APNSVoipChannelResponse": APNSVoipChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "AttributesResource": AttributesResourceTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetApnsVoipSandboxChannelResponseTypeDef = TypedDict(
-    "GetApnsVoipSandboxChannelResponseTypeDef",
+UpdateBaiduChannelRequestRequestTypeDef = TypedDict(
+    "UpdateBaiduChannelRequestRequestTypeDef",
     {
-        "APNSVoipSandboxChannelResponse": APNSVoipSandboxChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ApplicationId": str,
+        "BaiduChannelRequest": BaiduChannelRequestTypeDef,
     },
 )
 
-GetAppResponseTypeDef = TypedDict(
-    "GetAppResponseTypeDef",
+DeleteBaiduChannelResponseTypeDef = TypedDict(
+    "DeleteBaiduChannelResponseTypeDef",
     {
-        "ApplicationResponse": ApplicationResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "BaiduChannelResponse": BaiduChannelResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetBaiduChannelResponseTypeDef = TypedDict(
     "GetBaiduChannelResponseTypeDef",
     {
         "BaiduChannelResponse": BaiduChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RemoveAttributesResponseTypeDef = TypedDict(
-    "RemoveAttributesResponseTypeDef",
-    {
-        "AttributesResource": AttributesResourceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateAdmChannelResponseTypeDef = TypedDict(
-    "UpdateAdmChannelResponseTypeDef",
-    {
-        "ADMChannelResponse": ADMChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateApnsChannelResponseTypeDef = TypedDict(
-    "UpdateApnsChannelResponseTypeDef",
+UpdateBaiduChannelResponseTypeDef = TypedDict(
+    "UpdateBaiduChannelResponseTypeDef",
     {
-        "APNSChannelResponse": APNSChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "BaiduChannelResponse": BaiduChannelResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateApnsSandboxChannelResponseTypeDef = TypedDict(
-    "UpdateApnsSandboxChannelResponseTypeDef",
+ChannelsResponseTypeDef = TypedDict(
+    "ChannelsResponseTypeDef",
     {
-        "APNSSandboxChannelResponse": APNSSandboxChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Channels": Dict[str, ChannelResponseTypeDef],
     },
 )
 
-UpdateApnsVoipChannelResponseTypeDef = TypedDict(
-    "UpdateApnsVoipChannelResponseTypeDef",
+ClosedDaysTypeDef = TypedDict(
+    "ClosedDaysTypeDef",
     {
-        "APNSVoipChannelResponse": APNSVoipChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "EMAIL": Sequence[ClosedDaysRuleTypeDef],
+        "SMS": Sequence[ClosedDaysRuleTypeDef],
+        "PUSH": Sequence[ClosedDaysRuleTypeDef],
+        "VOICE": Sequence[ClosedDaysRuleTypeDef],
+        "CUSTOM": Sequence[ClosedDaysRuleTypeDef],
     },
+    total=False,
 )
 
-UpdateApnsVoipSandboxChannelResponseTypeDef = TypedDict(
-    "UpdateApnsVoipSandboxChannelResponseTypeDef",
+WaitActivityTypeDef = TypedDict(
+    "WaitActivityTypeDef",
     {
-        "APNSVoipSandboxChannelResponse": APNSVoipSandboxChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "NextActivity": str,
+        "WaitTime": WaitTimeTypeDef,
     },
+    total=False,
 )
 
-UpdateBaiduChannelResponseTypeDef = TypedDict(
-    "UpdateBaiduChannelResponseTypeDef",
+CreateAppRequestRequestTypeDef = TypedDict(
+    "CreateAppRequestRequestTypeDef",
     {
-        "BaiduChannelResponse": BaiduChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "CreateApplicationRequest": CreateApplicationRequestTypeDef,
     },
 )
 
 CreateEmailTemplateRequestRequestTypeDef = TypedDict(
     "CreateEmailTemplateRequestRequestTypeDef",
     {
         "EmailTemplateRequest": EmailTemplateRequestTypeDef,
@@ -3610,49 +3874,51 @@
     {
         "CreateNewVersion": bool,
         "Version": str,
     },
     total=False,
 )
 
+
 class UpdateEmailTemplateRequestRequestTypeDef(
     _RequiredUpdateEmailTemplateRequestRequestTypeDef,
     _OptionalUpdateEmailTemplateRequestRequestTypeDef,
 ):
     pass
 
+
 CreateEmailTemplateResponseTypeDef = TypedDict(
     "CreateEmailTemplateResponseTypeDef",
     {
         "CreateTemplateMessageBody": CreateTemplateMessageBodyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreatePushTemplateResponseTypeDef = TypedDict(
     "CreatePushTemplateResponseTypeDef",
     {
         "CreateTemplateMessageBody": CreateTemplateMessageBodyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateSmsTemplateResponseTypeDef = TypedDict(
     "CreateSmsTemplateResponseTypeDef",
     {
         "CreateTemplateMessageBody": CreateTemplateMessageBodyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateVoiceTemplateResponseTypeDef = TypedDict(
     "CreateVoiceTemplateResponseTypeDef",
     {
         "CreateTemplateMessageBody": CreateTemplateMessageBodyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateExportJobRequestRequestTypeDef = TypedDict(
     "CreateExportJobRequestRequestTypeDef",
     {
         "ApplicationId": str,
@@ -3668,46 +3934,46 @@
     },
 )
 
 CreateInAppTemplateResponseTypeDef = TypedDict(
     "CreateInAppTemplateResponseTypeDef",
     {
         "TemplateCreateMessageBody": TemplateCreateMessageBodyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateRecommenderConfigurationRequestRequestTypeDef = TypedDict(
     "CreateRecommenderConfigurationRequestRequestTypeDef",
     {
         "CreateRecommenderConfiguration": CreateRecommenderConfigurationTypeDef,
     },
 )
 
 CreateRecommenderConfigurationResponseTypeDef = TypedDict(
     "CreateRecommenderConfigurationResponseTypeDef",
     {
         "RecommenderConfigurationResponse": RecommenderConfigurationResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteRecommenderConfigurationResponseTypeDef = TypedDict(
     "DeleteRecommenderConfigurationResponseTypeDef",
     {
         "RecommenderConfigurationResponse": RecommenderConfigurationResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRecommenderConfigurationResponseTypeDef = TypedDict(
     "GetRecommenderConfigurationResponseTypeDef",
     {
         "RecommenderConfigurationResponse": RecommenderConfigurationResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredListRecommenderConfigurationsResponseTypeDef = TypedDict(
     "_RequiredListRecommenderConfigurationsResponseTypeDef",
     {
         "Item": List[RecommenderConfigurationResponseTypeDef],
@@ -3717,25 +3983,27 @@
     "_OptionalListRecommenderConfigurationsResponseTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
+
 class ListRecommenderConfigurationsResponseTypeDef(
     _RequiredListRecommenderConfigurationsResponseTypeDef,
     _OptionalListRecommenderConfigurationsResponseTypeDef,
 ):
     pass
 
+
 UpdateRecommenderConfigurationResponseTypeDef = TypedDict(
     "UpdateRecommenderConfigurationResponseTypeDef",
     {
         "RecommenderConfigurationResponse": RecommenderConfigurationResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateSmsTemplateRequestRequestTypeDef = TypedDict(
     "CreateSmsTemplateRequestRequestTypeDef",
     {
         "SMSTemplateRequest": SMSTemplateRequestTypeDef,
@@ -3755,19 +4023,21 @@
     {
         "CreateNewVersion": bool,
         "Version": str,
     },
     total=False,
 )
 
+
 class UpdateSmsTemplateRequestRequestTypeDef(
     _RequiredUpdateSmsTemplateRequestRequestTypeDef, _OptionalUpdateSmsTemplateRequestRequestTypeDef
 ):
     pass
 
+
 CreateVoiceTemplateRequestRequestTypeDef = TypedDict(
     "CreateVoiceTemplateRequestRequestTypeDef",
     {
         "TemplateName": str,
         "VoiceTemplateRequest": VoiceTemplateRequestTypeDef,
     },
 )
@@ -3784,20 +4054,22 @@
     {
         "CreateNewVersion": bool,
         "Version": str,
     },
     total=False,
 )
 
+
 class UpdateVoiceTemplateRequestRequestTypeDef(
     _RequiredUpdateVoiceTemplateRequestRequestTypeDef,
     _OptionalUpdateVoiceTemplateRequestRequestTypeDef,
 ):
     pass
 
+
 CustomMessageActivityTypeDef = TypedDict(
     "CustomMessageActivityTypeDef",
     {
         "DeliveryUri": str,
         "EndpointTypes": Sequence[EndpointTypesElementType],
         "MessageConfig": JourneyCustomMessageTypeDef,
         "NextActivity": str,
@@ -3846,241 +4118,243 @@
         "tags": Dict[str, str],
         "TemplateDescription": str,
         "Version": str,
     },
     total=False,
 )
 
+
 class PushNotificationTemplateResponseTypeDef(
     _RequiredPushNotificationTemplateResponseTypeDef,
     _OptionalPushNotificationTemplateResponseTypeDef,
 ):
     pass
 
+
 DeleteEmailChannelResponseTypeDef = TypedDict(
     "DeleteEmailChannelResponseTypeDef",
     {
         "EmailChannelResponse": EmailChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetEmailChannelResponseTypeDef = TypedDict(
     "GetEmailChannelResponseTypeDef",
     {
         "EmailChannelResponse": EmailChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateEmailChannelResponseTypeDef = TypedDict(
     "UpdateEmailChannelResponseTypeDef",
     {
         "EmailChannelResponse": EmailChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteEmailTemplateResponseTypeDef = TypedDict(
     "DeleteEmailTemplateResponseTypeDef",
     {
         "MessageBody": MessageBodyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteInAppTemplateResponseTypeDef = TypedDict(
     "DeleteInAppTemplateResponseTypeDef",
     {
         "MessageBody": MessageBodyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeletePushTemplateResponseTypeDef = TypedDict(
     "DeletePushTemplateResponseTypeDef",
     {
         "MessageBody": MessageBodyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteSmsTemplateResponseTypeDef = TypedDict(
     "DeleteSmsTemplateResponseTypeDef",
     {
         "MessageBody": MessageBodyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteVoiceTemplateResponseTypeDef = TypedDict(
     "DeleteVoiceTemplateResponseTypeDef",
     {
         "MessageBody": MessageBodyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateEmailTemplateResponseTypeDef = TypedDict(
     "UpdateEmailTemplateResponseTypeDef",
     {
         "MessageBody": MessageBodyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateEndpointResponseTypeDef = TypedDict(
     "UpdateEndpointResponseTypeDef",
     {
         "MessageBody": MessageBodyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateEndpointsBatchResponseTypeDef = TypedDict(
     "UpdateEndpointsBatchResponseTypeDef",
     {
         "MessageBody": MessageBodyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateInAppTemplateResponseTypeDef = TypedDict(
     "UpdateInAppTemplateResponseTypeDef",
     {
         "MessageBody": MessageBodyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdatePushTemplateResponseTypeDef = TypedDict(
     "UpdatePushTemplateResponseTypeDef",
     {
         "MessageBody": MessageBodyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateSmsTemplateResponseTypeDef = TypedDict(
     "UpdateSmsTemplateResponseTypeDef",
     {
         "MessageBody": MessageBodyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateTemplateActiveVersionResponseTypeDef = TypedDict(
     "UpdateTemplateActiveVersionResponseTypeDef",
     {
         "MessageBody": MessageBodyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateVoiceTemplateResponseTypeDef = TypedDict(
     "UpdateVoiceTemplateResponseTypeDef",
     {
         "MessageBody": MessageBodyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteEventStreamResponseTypeDef = TypedDict(
     "DeleteEventStreamResponseTypeDef",
     {
         "EventStream": EventStreamTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetEventStreamResponseTypeDef = TypedDict(
     "GetEventStreamResponseTypeDef",
     {
         "EventStream": EventStreamTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutEventStreamResponseTypeDef = TypedDict(
     "PutEventStreamResponseTypeDef",
     {
         "EventStream": EventStreamTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteGcmChannelResponseTypeDef = TypedDict(
     "DeleteGcmChannelResponseTypeDef",
     {
         "GCMChannelResponse": GCMChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetGcmChannelResponseTypeDef = TypedDict(
     "GetGcmChannelResponseTypeDef",
     {
         "GCMChannelResponse": GCMChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateGcmChannelResponseTypeDef = TypedDict(
     "UpdateGcmChannelResponseTypeDef",
     {
         "GCMChannelResponse": GCMChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteSmsChannelResponseTypeDef = TypedDict(
     "DeleteSmsChannelResponseTypeDef",
     {
         "SMSChannelResponse": SMSChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSmsChannelResponseTypeDef = TypedDict(
     "GetSmsChannelResponseTypeDef",
     {
         "SMSChannelResponse": SMSChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateSmsChannelResponseTypeDef = TypedDict(
     "UpdateSmsChannelResponseTypeDef",
     {
         "SMSChannelResponse": SMSChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteVoiceChannelResponseTypeDef = TypedDict(
     "DeleteVoiceChannelResponseTypeDef",
     {
         "VoiceChannelResponse": VoiceChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetVoiceChannelResponseTypeDef = TypedDict(
     "GetVoiceChannelResponseTypeDef",
     {
         "VoiceChannelResponse": VoiceChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateVoiceChannelResponseTypeDef = TypedDict(
     "UpdateVoiceChannelResponseTypeDef",
     {
         "VoiceChannelResponse": VoiceChannelResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateEmailChannelRequestRequestTypeDef = TypedDict(
     "UpdateEmailChannelRequestRequestTypeDef",
     {
         "ApplicationId": str,
@@ -4099,15 +4373,15 @@
     total=False,
 )
 
 GetEmailTemplateResponseTypeDef = TypedDict(
     "GetEmailTemplateResponseTypeDef",
     {
         "EmailTemplateResponse": EmailTemplateResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EndpointBatchItemTypeDef = TypedDict(
     "EndpointBatchItemTypeDef",
     {
         "Address": str,
@@ -4195,19 +4469,21 @@
     {
         "RequestId": str,
         "Result": Dict[str, Dict[str, EndpointMessageResultTypeDef]],
     },
     total=False,
 )
 
+
 class SendUsersMessageResponseTypeDef(
     _RequiredSendUsersMessageResponseTypeDef, _OptionalSendUsersMessageResponseTypeDef
 ):
     pass
 
+
 EventDimensionsTypeDef = TypedDict(
     "EventDimensionsTypeDef",
     {
         "Attributes": Mapping[str, AttributeDimensionTypeDef],
         "EventType": SetDimensionTypeDef,
         "Metrics": Mapping[str, MetricDimensionTypeDef],
     },
@@ -4254,17 +4530,19 @@
         "Metrics": Mapping[str, float],
         "SdkName": str,
         "Session": SessionTypeDef,
     },
     total=False,
 )
 
+
 class EventTypeDef(_RequiredEventTypeDef, _OptionalEventTypeDef):
     pass
 
+
 _RequiredExportJobResponseTypeDef = TypedDict(
     "_RequiredExportJobResponseTypeDef",
     {
         "ApplicationId": str,
         "CreationDate": str,
         "Definition": ExportJobResourceTypeDef,
         "Id": str,
@@ -4282,19 +4560,21 @@
         "TotalFailures": int,
         "TotalPieces": int,
         "TotalProcessed": int,
     },
     total=False,
 )
 
+
 class ExportJobResponseTypeDef(
     _RequiredExportJobResponseTypeDef, _OptionalExportJobResponseTypeDef
 ):
     pass
 
+
 UpdateGcmChannelRequestRequestTypeDef = TypedDict(
     "UpdateGcmChannelRequestRequestTypeDef",
     {
         "ApplicationId": str,
         "GCMChannelRequest": GCMChannelRequestTypeDef,
     },
 )
@@ -4309,48 +4589,68 @@
     "_OptionalGPSPointDimensionTypeDef",
     {
         "RangeInKilometers": float,
     },
     total=False,
 )
 
+
 class GPSPointDimensionTypeDef(
     _RequiredGPSPointDimensionTypeDef, _OptionalGPSPointDimensionTypeDef
 ):
     pass
 
+
 GetJourneyExecutionActivityMetricsResponseTypeDef = TypedDict(
     "GetJourneyExecutionActivityMetricsResponseTypeDef",
     {
         "JourneyExecutionActivityMetricsResponse": JourneyExecutionActivityMetricsResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetJourneyExecutionMetricsResponseTypeDef = TypedDict(
     "GetJourneyExecutionMetricsResponseTypeDef",
     {
         "JourneyExecutionMetricsResponse": JourneyExecutionMetricsResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetJourneyRunExecutionActivityMetricsResponseTypeDef = TypedDict(
+    "GetJourneyRunExecutionActivityMetricsResponseTypeDef",
+    {
+        "JourneyRunExecutionActivityMetricsResponse": (
+            JourneyRunExecutionActivityMetricsResponseTypeDef
+        ),
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetJourneyRunExecutionMetricsResponseTypeDef = TypedDict(
+    "GetJourneyRunExecutionMetricsResponseTypeDef",
+    {
+        "JourneyRunExecutionMetricsResponse": JourneyRunExecutionMetricsResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSmsTemplateResponseTypeDef = TypedDict(
     "GetSmsTemplateResponseTypeDef",
     {
         "SMSTemplateResponse": SMSTemplateResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetVoiceTemplateResponseTypeDef = TypedDict(
     "GetVoiceTemplateResponseTypeDef",
     {
         "VoiceTemplateResponse": VoiceTemplateResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredImportJobResponseTypeDef = TypedDict(
     "_RequiredImportJobResponseTypeDef",
     {
         "ApplicationId": str,
@@ -4371,19 +4671,21 @@
         "TotalFailures": int,
         "TotalPieces": int,
         "TotalProcessed": int,
     },
     total=False,
 )
 
+
 class ImportJobResponseTypeDef(
     _RequiredImportJobResponseTypeDef, _OptionalImportJobResponseTypeDef
 ):
     pass
 
+
 InAppMessageButtonTypeDef = TypedDict(
     "InAppMessageButtonTypeDef",
     {
         "Android": OverrideButtonConfigurationTypeDef,
         "DefaultConfig": DefaultButtonConfigurationTypeDef,
         "IOS": OverrideButtonConfigurationTypeDef,
         "Web": OverrideButtonConfigurationTypeDef,
@@ -4398,14 +4700,35 @@
         "NextActivity": str,
         "TemplateName": str,
         "TemplateVersion": str,
     },
     total=False,
 )
 
+_RequiredJourneyRunsResponseTypeDef = TypedDict(
+    "_RequiredJourneyRunsResponseTypeDef",
+    {
+        "Item": List[JourneyRunResponseTypeDef],
+    },
+)
+_OptionalJourneyRunsResponseTypeDef = TypedDict(
+    "_OptionalJourneyRunsResponseTypeDef",
+    {
+        "NextToken": str,
+    },
+    total=False,
+)
+
+
+class JourneyRunsResponseTypeDef(
+    _RequiredJourneyRunsResponseTypeDef, _OptionalJourneyRunsResponseTypeDef
+):
+    pass
+
+
 SMSMessageActivityTypeDef = TypedDict(
     "SMSMessageActivityTypeDef",
     {
         "MessageConfig": JourneySMSMessageTypeDef,
         "NextActivity": str,
         "TemplateName": str,
         "TemplateVersion": str,
@@ -4422,15 +4745,15 @@
     },
 )
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "TagsModel": TagsModelTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
@@ -4450,29 +4773,31 @@
         "EndpointResult": Dict[str, EndpointMessageResultTypeDef],
         "RequestId": str,
         "Result": Dict[str, MessageResultTypeDef],
     },
     total=False,
 )
 
+
 class MessageResponseTypeDef(_RequiredMessageResponseTypeDef, _OptionalMessageResponseTypeDef):
     pass
 
+
 PhoneNumberValidateRequestRequestTypeDef = TypedDict(
     "PhoneNumberValidateRequestRequestTypeDef",
     {
         "NumberValidateRequest": NumberValidateRequestTypeDef,
     },
 )
 
 PhoneNumberValidateResponseTypeDef = TypedDict(
     "PhoneNumberValidateResponseTypeDef",
     {
         "NumberValidateResponse": NumberValidateResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OpenHoursTypeDef = TypedDict(
     "OpenHoursTypeDef",
     {
         "EMAIL": Mapping[DayOfWeekType, Sequence[OpenHoursRuleTypeDef]],
@@ -4581,19 +4906,21 @@
     "_OptionalTemplatesResponseTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
+
 class TemplatesResponseTypeDef(
     _RequiredTemplatesResponseTypeDef, _OptionalTemplatesResponseTypeDef
 ):
     pass
 
+
 _RequiredTemplateVersionsResponseTypeDef = TypedDict(
     "_RequiredTemplateVersionsResponseTypeDef",
     {
         "Item": List[TemplateVersionResponseTypeDef],
     },
 )
 _OptionalTemplateVersionsResponseTypeDef = TypedDict(
@@ -4602,19 +4929,21 @@
         "Message": str,
         "NextToken": str,
         "RequestID": str,
     },
     total=False,
 )
 
+
 class TemplateVersionsResponseTypeDef(
     _RequiredTemplateVersionsResponseTypeDef, _OptionalTemplateVersionsResponseTypeDef
 ):
     pass
 
+
 UpdateRecommenderConfigurationRequestRequestTypeDef = TypedDict(
     "UpdateRecommenderConfigurationRequestRequestTypeDef",
     {
         "RecommenderId": str,
         "UpdateRecommenderConfiguration": UpdateRecommenderConfigurationTypeDef,
     },
 )
@@ -4627,15 +4956,15 @@
     },
 )
 
 VerifyOTPMessageResponseTypeDef = TypedDict(
     "VerifyOTPMessageResponseTypeDef",
     {
         "VerificationResponse": VerificationResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 VerifyOTPMessageRequestRequestTypeDef = TypedDict(
     "VerifyOTPMessageRequestRequestTypeDef",
     {
         "ApplicationId": str,
@@ -4643,39 +4972,39 @@
     },
 )
 
 GetCampaignActivitiesResponseTypeDef = TypedDict(
     "GetCampaignActivitiesResponseTypeDef",
     {
         "ActivitiesResponse": ActivitiesResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAppsResponseTypeDef = TypedDict(
     "GetAppsResponseTypeDef",
     {
         "ApplicationsResponse": ApplicationsResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetApplicationSettingsResponseTypeDef = TypedDict(
     "GetApplicationSettingsResponseTypeDef",
     {
         "ApplicationSettingsResource": ApplicationSettingsResourceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateApplicationSettingsResponseTypeDef = TypedDict(
     "UpdateApplicationSettingsResponseTypeDef",
     {
         "ApplicationSettingsResource": ApplicationSettingsResourceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateApplicationSettingsRequestRequestTypeDef = TypedDict(
     "UpdateApplicationSettingsRequestRequestTypeDef",
     {
         "ApplicationId": str,
@@ -4683,23 +5012,23 @@
     },
 )
 
 GetChannelsResponseTypeDef = TypedDict(
     "GetChannelsResponseTypeDef",
     {
         "ChannelsResponse": ChannelsResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRecommenderConfigurationsResponseTypeDef = TypedDict(
     "GetRecommenderConfigurationsResponseTypeDef",
     {
         "ListRecommenderConfigurationsResponse": ListRecommenderConfigurationsResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreatePushTemplateRequestRequestTypeDef = TypedDict(
     "CreatePushTemplateRequestRequestTypeDef",
     {
         "PushNotificationTemplateRequest": PushNotificationTemplateRequestTypeDef,
@@ -4719,25 +5048,27 @@
     {
         "CreateNewVersion": bool,
         "Version": str,
     },
     total=False,
 )
 
+
 class UpdatePushTemplateRequestRequestTypeDef(
     _RequiredUpdatePushTemplateRequestRequestTypeDef,
     _OptionalUpdatePushTemplateRequestRequestTypeDef,
 ):
     pass
 
+
 GetPushTemplateResponseTypeDef = TypedDict(
     "GetPushTemplateResponseTypeDef",
     {
         "PushNotificationTemplateResponse": PushNotificationTemplateResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EndpointBatchRequestTypeDef = TypedDict(
     "EndpointBatchRequestTypeDef",
     {
         "Item": Sequence[EndpointBatchItemTypeDef],
@@ -4753,38 +5084,38 @@
     },
 )
 
 DeleteEndpointResponseTypeDef = TypedDict(
     "DeleteEndpointResponseTypeDef",
     {
         "EndpointResponse": EndpointResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EndpointsResponseTypeDef = TypedDict(
     "EndpointsResponseTypeDef",
     {
         "Item": List[EndpointResponseTypeDef],
     },
 )
 
 GetEndpointResponseTypeDef = TypedDict(
     "GetEndpointResponseTypeDef",
     {
         "EndpointResponse": EndpointResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SendUsersMessagesResponseTypeDef = TypedDict(
     "SendUsersMessagesResponseTypeDef",
     {
         "SendUsersMessageResponse": SendUsersMessageResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CampaignEventFilterTypeDef = TypedDict(
     "CampaignEventFilterTypeDef",
     {
         "Dimensions": EventDimensionsTypeDef,
@@ -4825,15 +5156,15 @@
     },
 )
 
 CreateExportJobResponseTypeDef = TypedDict(
     "CreateExportJobResponseTypeDef",
     {
         "ExportJobResponse": ExportJobResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredExportJobsResponseTypeDef = TypedDict(
     "_RequiredExportJobsResponseTypeDef",
     {
         "Item": List[ExportJobResponseTypeDef],
@@ -4843,24 +5174,26 @@
     "_OptionalExportJobsResponseTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
+
 class ExportJobsResponseTypeDef(
     _RequiredExportJobsResponseTypeDef, _OptionalExportJobsResponseTypeDef
 ):
     pass
 
+
 GetExportJobResponseTypeDef = TypedDict(
     "GetExportJobResponseTypeDef",
     {
         "ExportJobResponse": ExportJobResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SegmentLocationTypeDef = TypedDict(
     "SegmentLocationTypeDef",
     {
         "Country": SetDimensionTypeDef,
@@ -4869,23 +5202,23 @@
     total=False,
 )
 
 CreateImportJobResponseTypeDef = TypedDict(
     "CreateImportJobResponseTypeDef",
     {
         "ImportJobResponse": ImportJobResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetImportJobResponseTypeDef = TypedDict(
     "GetImportJobResponseTypeDef",
     {
         "ImportJobResponse": ImportJobResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredImportJobsResponseTypeDef = TypedDict(
     "_RequiredImportJobsResponseTypeDef",
     {
         "Item": List[ImportJobResponseTypeDef],
@@ -4895,45 +5228,55 @@
     "_OptionalImportJobsResponseTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
+
 class ImportJobsResponseTypeDef(
     _RequiredImportJobsResponseTypeDef, _OptionalImportJobsResponseTypeDef
 ):
     pass
 
+
 InAppMessageContentTypeDef = TypedDict(
     "InAppMessageContentTypeDef",
     {
         "BackgroundColor": str,
         "BodyConfig": InAppMessageBodyConfigTypeDef,
         "HeaderConfig": InAppMessageHeaderConfigTypeDef,
         "ImageUrl": str,
         "PrimaryBtn": InAppMessageButtonTypeDef,
         "SecondaryBtn": InAppMessageButtonTypeDef,
     },
     total=False,
 )
 
+GetJourneyRunsResponseTypeDef = TypedDict(
+    "GetJourneyRunsResponseTypeDef",
+    {
+        "JourneyRunsResponse": JourneyRunsResponseTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 SendMessagesResponseTypeDef = TypedDict(
     "SendMessagesResponseTypeDef",
     {
         "MessageResponse": MessageResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SendOTPMessageResponseTypeDef = TypedDict(
     "SendOTPMessageResponseTypeDef",
     {
         "MessageResponse": MessageResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BaseKpiResultTypeDef = TypedDict(
     "BaseKpiResultTypeDef",
     {
         "Rows": List[ResultRowTypeDef],
@@ -4954,23 +5297,23 @@
     total=False,
 )
 
 ListTemplatesResponseTypeDef = TypedDict(
     "ListTemplatesResponseTypeDef",
     {
         "TemplatesResponse": TemplatesResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTemplateVersionsResponseTypeDef = TypedDict(
     "ListTemplateVersionsResponseTypeDef",
     {
         "TemplateVersionsResponse": TemplateVersionsResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateEndpointsBatchRequestRequestTypeDef = TypedDict(
     "UpdateEndpointsBatchRequestRequestTypeDef",
     {
         "ApplicationId": str,
@@ -4978,23 +5321,23 @@
     },
 )
 
 DeleteUserEndpointsResponseTypeDef = TypedDict(
     "DeleteUserEndpointsResponseTypeDef",
     {
         "EndpointsResponse": EndpointsResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetUserEndpointsResponseTypeDef = TypedDict(
     "GetUserEndpointsResponseTypeDef",
     {
         "EndpointsResponse": EndpointsResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InAppCampaignScheduleTypeDef = TypedDict(
     "InAppCampaignScheduleTypeDef",
     {
         "EndDate": str,
@@ -5019,54 +5362,56 @@
         "IsLocalTime": bool,
         "QuietTime": QuietTimeTypeDef,
         "Timezone": str,
     },
     total=False,
 )
 
+
 class ScheduleTypeDef(_RequiredScheduleTypeDef, _OptionalScheduleTypeDef):
     pass
 
+
 EventStartConditionTypeDef = TypedDict(
     "EventStartConditionTypeDef",
     {
         "EventFilter": EventFilterTypeDef,
         "SegmentId": str,
     },
     total=False,
 )
 
 PutEventsResponseTypeDef = TypedDict(
     "PutEventsResponseTypeDef",
     {
         "EventsResponse": EventsResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EventsRequestTypeDef = TypedDict(
     "EventsRequestTypeDef",
     {
         "BatchItem": Mapping[str, EventsBatchTypeDef],
     },
 )
 
 GetExportJobsResponseTypeDef = TypedDict(
     "GetExportJobsResponseTypeDef",
     {
         "ExportJobsResponse": ExportJobsResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSegmentExportJobsResponseTypeDef = TypedDict(
     "GetSegmentExportJobsResponseTypeDef",
     {
         "ExportJobsResponse": ExportJobsResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SegmentDimensionsTypeDef = TypedDict(
     "SegmentDimensionsTypeDef",
     {
         "Attributes": Mapping[str, AttributeDimensionTypeDef],
@@ -5079,23 +5424,23 @@
     total=False,
 )
 
 GetImportJobsResponseTypeDef = TypedDict(
     "GetImportJobsResponseTypeDef",
     {
         "ImportJobsResponse": ImportJobsResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSegmentImportJobsResponseTypeDef = TypedDict(
     "GetSegmentImportJobsResponseTypeDef",
     {
         "ImportJobsResponse": ImportJobsResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CampaignInAppMessageTypeDef = TypedDict(
     "CampaignInAppMessageTypeDef",
     {
         "Body": str,
@@ -5147,19 +5492,21 @@
         "tags": Dict[str, str],
         "TemplateDescription": str,
         "Version": str,
     },
     total=False,
 )
 
+
 class InAppTemplateResponseTypeDef(
     _RequiredInAppTemplateResponseTypeDef, _OptionalInAppTemplateResponseTypeDef
 ):
     pass
 
+
 _RequiredApplicationDateRangeKpiResponseTypeDef = TypedDict(
     "_RequiredApplicationDateRangeKpiResponseTypeDef",
     {
         "ApplicationId": str,
         "EndTime": datetime,
         "KpiName": str,
         "KpiResult": BaseKpiResultTypeDef,
@@ -5170,19 +5517,21 @@
     "_OptionalApplicationDateRangeKpiResponseTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
+
 class ApplicationDateRangeKpiResponseTypeDef(
     _RequiredApplicationDateRangeKpiResponseTypeDef, _OptionalApplicationDateRangeKpiResponseTypeDef
 ):
     pass
 
+
 _RequiredCampaignDateRangeKpiResponseTypeDef = TypedDict(
     "_RequiredCampaignDateRangeKpiResponseTypeDef",
     {
         "ApplicationId": str,
         "CampaignId": str,
         "EndTime": datetime,
         "KpiName": str,
@@ -5194,19 +5543,21 @@
     "_OptionalCampaignDateRangeKpiResponseTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
+
 class CampaignDateRangeKpiResponseTypeDef(
     _RequiredCampaignDateRangeKpiResponseTypeDef, _OptionalCampaignDateRangeKpiResponseTypeDef
 ):
     pass
 
+
 _RequiredJourneyDateRangeKpiResponseTypeDef = TypedDict(
     "_RequiredJourneyDateRangeKpiResponseTypeDef",
     {
         "ApplicationId": str,
         "EndTime": datetime,
         "JourneyId": str,
         "KpiName": str,
@@ -5218,19 +5569,21 @@
     "_OptionalJourneyDateRangeKpiResponseTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
+
 class JourneyDateRangeKpiResponseTypeDef(
     _RequiredJourneyDateRangeKpiResponseTypeDef, _OptionalJourneyDateRangeKpiResponseTypeDef
 ):
     pass
 
+
 DirectMessageConfigurationTypeDef = TypedDict(
     "DirectMessageConfigurationTypeDef",
     {
         "ADMMessage": ADMMessageTypeDef,
         "APNSMessage": APNSMessageTypeDef,
         "BaiduMessage": BaiduMessageTypeDef,
         "DefaultMessage": DefaultMessageTypeDef,
@@ -5333,49 +5686,51 @@
     {
         "CreateNewVersion": bool,
         "Version": str,
     },
     total=False,
 )
 
+
 class UpdateInAppTemplateRequestRequestTypeDef(
     _RequiredUpdateInAppTemplateRequestRequestTypeDef,
     _OptionalUpdateInAppTemplateRequestRequestTypeDef,
 ):
     pass
 
+
 GetInAppTemplateResponseTypeDef = TypedDict(
     "GetInAppTemplateResponseTypeDef",
     {
         "InAppTemplateResponse": InAppTemplateResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetApplicationDateRangeKpiResponseTypeDef = TypedDict(
     "GetApplicationDateRangeKpiResponseTypeDef",
     {
         "ApplicationDateRangeKpiResponse": ApplicationDateRangeKpiResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCampaignDateRangeKpiResponseTypeDef = TypedDict(
     "GetCampaignDateRangeKpiResponseTypeDef",
     {
         "CampaignDateRangeKpiResponse": CampaignDateRangeKpiResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetJourneyDateRangeKpiResponseTypeDef = TypedDict(
     "GetJourneyDateRangeKpiResponseTypeDef",
     {
         "JourneyDateRangeKpiResponse": JourneyDateRangeKpiResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredMessageRequestTypeDef = TypedDict(
     "_RequiredMessageRequestTypeDef",
     {
         "MessageConfiguration": DirectMessageConfigurationTypeDef,
@@ -5389,17 +5744,19 @@
         "Endpoints": Mapping[str, EndpointSendConfigurationTypeDef],
         "TemplateConfiguration": TemplateConfigurationTypeDef,
         "TraceId": str,
     },
     total=False,
 )
 
+
 class MessageRequestTypeDef(_RequiredMessageRequestTypeDef, _OptionalMessageRequestTypeDef):
     pass
 
+
 _RequiredSendUsersMessageRequestTypeDef = TypedDict(
     "_RequiredSendUsersMessageRequestTypeDef",
     {
         "MessageConfiguration": DirectMessageConfigurationTypeDef,
         "Users": Mapping[str, EndpointSendConfigurationTypeDef],
     },
 )
@@ -5409,19 +5766,21 @@
         "Context": Mapping[str, str],
         "TemplateConfiguration": TemplateConfigurationTypeDef,
         "TraceId": str,
     },
     total=False,
 )
 
+
 class SendUsersMessageRequestTypeDef(
     _RequiredSendUsersMessageRequestTypeDef, _OptionalSendUsersMessageRequestTypeDef
 ):
     pass
 
+
 SegmentGroupListTypeDef = TypedDict(
     "SegmentGroupListTypeDef",
     {
         "Groups": Sequence[SegmentGroupTypeDef],
         "Include": IncludeType,
     },
     total=False,
@@ -5462,19 +5821,21 @@
         "TemplateConfiguration": TemplateConfigurationTypeDef,
         "TreatmentDescription": str,
         "TreatmentName": str,
     },
     total=False,
 )
 
+
 class TreatmentResourceTypeDef(
     _RequiredTreatmentResourceTypeDef, _OptionalTreatmentResourceTypeDef
 ):
     pass
 
+
 _RequiredWriteTreatmentResourceTypeDef = TypedDict(
     "_RequiredWriteTreatmentResourceTypeDef",
     {
         "SizePercent": int,
     },
 )
 _OptionalWriteTreatmentResourceTypeDef = TypedDict(
@@ -5486,19 +5847,21 @@
         "TemplateConfiguration": TemplateConfigurationTypeDef,
         "TreatmentDescription": str,
         "TreatmentName": str,
     },
     total=False,
 )
 
+
 class WriteTreatmentResourceTypeDef(
     _RequiredWriteTreatmentResourceTypeDef, _OptionalWriteTreatmentResourceTypeDef
 ):
     pass
 
+
 InAppMessagesResponseTypeDef = TypedDict(
     "InAppMessagesResponseTypeDef",
     {
         "InAppMessageCampaigns": List[InAppMessageCampaignTypeDef],
     },
     total=False,
 )
@@ -5539,17 +5902,19 @@
         "SegmentGroups": SegmentGroupListTypeDef,
         "tags": Dict[str, str],
         "Version": int,
     },
     total=False,
 )
 
+
 class SegmentResponseTypeDef(_RequiredSegmentResponseTypeDef, _OptionalSegmentResponseTypeDef):
     pass
 
+
 WriteSegmentRequestTypeDef = TypedDict(
     "WriteSegmentRequestTypeDef",
     {
         "Dimensions": SegmentDimensionsTypeDef,
         "Name": str,
         "SegmentGroups": SegmentGroupListTypeDef,
         "tags": Mapping[str, str],
@@ -5611,17 +5976,19 @@
         "TreatmentName": str,
         "Version": int,
         "Priority": int,
     },
     total=False,
 )
 
+
 class CampaignResponseTypeDef(_RequiredCampaignResponseTypeDef, _OptionalCampaignResponseTypeDef):
     pass
 
+
 WriteCampaignRequestTypeDef = TypedDict(
     "WriteCampaignRequestTypeDef",
     {
         "AdditionalTreatments": Sequence[WriteTreatmentResourceTypeDef],
         "CustomDeliveryConfiguration": CustomDeliveryConfigurationTypeDef,
         "Description": str,
         "HoldoutPercent": int,
@@ -5642,47 +6009,47 @@
     total=False,
 )
 
 GetInAppMessagesResponseTypeDef = TypedDict(
     "GetInAppMessagesResponseTypeDef",
     {
         "InAppMessagesResponse": InAppMessagesResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateSegmentResponseTypeDef = TypedDict(
     "CreateSegmentResponseTypeDef",
     {
         "SegmentResponse": SegmentResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteSegmentResponseTypeDef = TypedDict(
     "DeleteSegmentResponseTypeDef",
     {
         "SegmentResponse": SegmentResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSegmentResponseTypeDef = TypedDict(
     "GetSegmentResponseTypeDef",
     {
         "SegmentResponse": SegmentResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSegmentVersionResponseTypeDef = TypedDict(
     "GetSegmentVersionResponseTypeDef",
     {
         "SegmentResponse": SegmentResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSegmentsResponseTypeDef = TypedDict(
     "_RequiredSegmentsResponseTypeDef",
     {
         "Item": List[SegmentResponseTypeDef],
@@ -5692,22 +6059,24 @@
     "_OptionalSegmentsResponseTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
+
 class SegmentsResponseTypeDef(_RequiredSegmentsResponseTypeDef, _OptionalSegmentsResponseTypeDef):
     pass
 
+
 UpdateSegmentResponseTypeDef = TypedDict(
     "UpdateSegmentResponseTypeDef",
     {
         "SegmentResponse": SegmentResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateSegmentRequestRequestTypeDef = TypedDict(
     "CreateSegmentRequestRequestTypeDef",
     {
         "ApplicationId": str,
@@ -5752,56 +6121,58 @@
     "_OptionalCampaignsResponseTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
+
 class CampaignsResponseTypeDef(
     _RequiredCampaignsResponseTypeDef, _OptionalCampaignsResponseTypeDef
 ):
     pass
 
+
 CreateCampaignResponseTypeDef = TypedDict(
     "CreateCampaignResponseTypeDef",
     {
         "CampaignResponse": CampaignResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteCampaignResponseTypeDef = TypedDict(
     "DeleteCampaignResponseTypeDef",
     {
         "CampaignResponse": CampaignResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCampaignResponseTypeDef = TypedDict(
     "GetCampaignResponseTypeDef",
     {
         "CampaignResponse": CampaignResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCampaignVersionResponseTypeDef = TypedDict(
     "GetCampaignVersionResponseTypeDef",
     {
         "CampaignResponse": CampaignResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateCampaignResponseTypeDef = TypedDict(
     "UpdateCampaignResponseTypeDef",
     {
         "CampaignResponse": CampaignResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateCampaignRequestRequestTypeDef = TypedDict(
     "CreateCampaignRequestRequestTypeDef",
     {
         "ApplicationId": str,
@@ -5818,23 +6189,23 @@
     },
 )
 
 GetSegmentVersionsResponseTypeDef = TypedDict(
     "GetSegmentVersionsResponseTypeDef",
     {
         "SegmentsResponse": SegmentsResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSegmentsResponseTypeDef = TypedDict(
     "GetSegmentsResponseTypeDef",
     {
         "SegmentsResponse": SegmentsResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredJourneyResponseTypeDef = TypedDict(
     "_RequiredJourneyResponseTypeDef",
     {
         "ApplicationId": str,
@@ -5859,21 +6230,24 @@
         "tags": Dict[str, str],
         "WaitForQuietTime": bool,
         "RefreshOnSegmentUpdate": bool,
         "JourneyChannelSettings": JourneyChannelSettingsTypeDef,
         "SendingSchedule": bool,
         "OpenHours": OpenHoursTypeDef,
         "ClosedDays": ClosedDaysTypeDef,
+        "TimezoneEstimationMethods": List[TimezoneEstimationMethodsElementType],
     },
     total=False,
 )
 
+
 class JourneyResponseTypeDef(_RequiredJourneyResponseTypeDef, _OptionalJourneyResponseTypeDef):
     pass
 
+
 _RequiredWriteJourneyRequestTypeDef = TypedDict(
     "_RequiredWriteJourneyRequestTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalWriteJourneyRequestTypeDef = TypedDict(
@@ -5892,60 +6266,63 @@
         "State": StateType,
         "WaitForQuietTime": bool,
         "RefreshOnSegmentUpdate": bool,
         "JourneyChannelSettings": JourneyChannelSettingsTypeDef,
         "SendingSchedule": bool,
         "OpenHours": OpenHoursTypeDef,
         "ClosedDays": ClosedDaysTypeDef,
+        "TimezoneEstimationMethods": Sequence[TimezoneEstimationMethodsElementType],
     },
     total=False,
 )
 
+
 class WriteJourneyRequestTypeDef(
     _RequiredWriteJourneyRequestTypeDef, _OptionalWriteJourneyRequestTypeDef
 ):
     pass
 
+
 GetCampaignVersionsResponseTypeDef = TypedDict(
     "GetCampaignVersionsResponseTypeDef",
     {
         "CampaignsResponse": CampaignsResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCampaignsResponseTypeDef = TypedDict(
     "GetCampaignsResponseTypeDef",
     {
         "CampaignsResponse": CampaignsResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateJourneyResponseTypeDef = TypedDict(
     "CreateJourneyResponseTypeDef",
     {
         "JourneyResponse": JourneyResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteJourneyResponseTypeDef = TypedDict(
     "DeleteJourneyResponseTypeDef",
     {
         "JourneyResponse": JourneyResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetJourneyResponseTypeDef = TypedDict(
     "GetJourneyResponseTypeDef",
     {
         "JourneyResponse": JourneyResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredJourneysResponseTypeDef = TypedDict(
     "_RequiredJourneysResponseTypeDef",
     {
         "Item": List[JourneyResponseTypeDef],
@@ -5955,30 +6332,32 @@
     "_OptionalJourneysResponseTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
+
 class JourneysResponseTypeDef(_RequiredJourneysResponseTypeDef, _OptionalJourneysResponseTypeDef):
     pass
 
+
 UpdateJourneyResponseTypeDef = TypedDict(
     "UpdateJourneyResponseTypeDef",
     {
         "JourneyResponse": JourneyResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateJourneyStateResponseTypeDef = TypedDict(
     "UpdateJourneyStateResponseTypeDef",
     {
         "JourneyResponse": JourneyResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateJourneyRequestRequestTypeDef = TypedDict(
     "CreateJourneyRequestRequestTypeDef",
     {
         "ApplicationId": str,
@@ -5995,10 +6374,10 @@
     },
 )
 
 ListJourneysResponseTypeDef = TypedDict(
     "ListJourneysResponseTypeDef",
     {
         "JourneysResponse": JourneysResponseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-pinpoint-2.5.0.post1/types_aiobotocore_pinpoint.egg-info/PKG-INFO` & `types-aiobotocore-pinpoint-2.5.1/types_aiobotocore_pinpoint.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-pinpoint
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Pinpoint 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Pinpoint 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-pinpoint"></a>
 
 # types-aiobotocore-pinpoint
 
 [![PyPI - types-aiobotocore-pinpoint](https://img.shields.io/pypi/v/types-aiobotocore-pinpoint.svg?color=blue)](https://pypi.org/project/types-aiobotocore-pinpoint)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-pinpoint.svg?color=blue)](https://pypi.org/project/types-aiobotocore-pinpoint)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-pinpoint?color=blue)](https://pypistats.org/packages/types-aiobotocore-pinpoint)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Pinpoint 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint.html#Pinpoint)
+[aiobotocore.Pinpoint 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint.html#Pinpoint)
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
 [types-aiobotocore-pinpoint docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint/).
 
 See how it helps to find and fix potential bugs:
 
@@ -284,23 +284,25 @@
     DurationType,
     EndpointTypesElementType,
     FilterTypeType,
     FormatType,
     FrequencyType,
     IncludeType,
     JobStatusType,
+    JourneyRunStatusType,
     LayoutType,
     MessageTypeType,
     ModeType,
     OperatorType,
     RecencyTypeType,
     SegmentTypeType,
     SourceTypeType,
     StateType,
     TemplateTypeType,
+    TimezoneEstimationMethodsElementType,
     TypeType,
     PinpointServiceName,
     ServiceName,
     ResourceServiceName,
     RegionName,
 )
 
@@ -350,15 +352,14 @@
     CampaignStateTypeDef,
     CustomDeliveryConfigurationTypeDef,
     CampaignSmsMessageTypeDef,
     ChannelResponseTypeDef,
     ClosedDaysRuleTypeDef,
     WaitTimeTypeDef,
     CreateApplicationRequestTypeDef,
-    ResponseMetadataTypeDef,
     EmailTemplateRequestTypeDef,
     CreateTemplateMessageBodyTypeDef,
     ExportJobRequestTypeDef,
     ImportJobRequestTypeDef,
     TemplateCreateMessageBodyTypeDef,
     CreateRecommenderConfigurationTypeDef,
     RecommenderConfigurationResponseTypeDef,
@@ -401,14 +402,15 @@
     GCMMessageTypeDef,
     SMSMessageTypeDef,
     VoiceMessageTypeDef,
     EmailChannelRequestTypeDef,
     JourneyEmailMessageTypeDef,
     RawEmailTypeDef,
     EmailTemplateResponseTypeDef,
+    EmptyResponseMetadataTypeDef,
     EndpointDemographicTypeDef,
     EndpointLocationTypeDef,
     EndpointUserTypeDef,
     EndpointItemResponseTypeDef,
     EndpointMessageResultTypeDef,
     EndpointSendConfigurationTypeDef,
     MetricDimensionTypeDef,
@@ -448,14 +450,19 @@
     GetInAppTemplateRequestRequestTypeDef,
     GetJourneyDateRangeKpiRequestRequestTypeDef,
     GetJourneyExecutionActivityMetricsRequestRequestTypeDef,
     JourneyExecutionActivityMetricsResponseTypeDef,
     GetJourneyExecutionMetricsRequestRequestTypeDef,
     JourneyExecutionMetricsResponseTypeDef,
     GetJourneyRequestRequestTypeDef,
+    GetJourneyRunExecutionActivityMetricsRequestRequestTypeDef,
+    JourneyRunExecutionActivityMetricsResponseTypeDef,
+    GetJourneyRunExecutionMetricsRequestRequestTypeDef,
+    JourneyRunExecutionMetricsResponseTypeDef,
+    GetJourneyRunsRequestRequestTypeDef,
     GetPushTemplateRequestRequestTypeDef,
     GetRecommenderConfigurationRequestRequestTypeDef,
     GetRecommenderConfigurationsRequestRequestTypeDef,
     GetSegmentExportJobsRequestRequestTypeDef,
     GetSegmentImportJobsRequestRequestTypeDef,
     GetSegmentRequestRequestTypeDef,
     GetSegmentVersionRequestRequestTypeDef,
@@ -472,14 +479,15 @@
     InAppMessageBodyConfigTypeDef,
     OverrideButtonConfigurationTypeDef,
     InAppMessageHeaderConfigTypeDef,
     JourneyChannelSettingsTypeDef,
     JourneyLimitsTypeDef,
     JourneyPushMessageTypeDef,
     JourneyScheduleTypeDef,
+    JourneyRunResponseTypeDef,
     JourneySMSMessageTypeDef,
     JourneyStateRequestTypeDef,
     ListJourneysRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     TagsModelTypeDef,
     ListTemplateVersionsRequestRequestTypeDef,
     ListTemplatesRequestRequestTypeDef,
@@ -488,14 +496,15 @@
     NumberValidateRequestTypeDef,
     NumberValidateResponseTypeDef,
     OpenHoursRuleTypeDef,
     WriteEventStreamTypeDef,
     RandomSplitEntryTypeDef,
     RecencyDimensionTypeDef,
     UpdateAttributesRequestTypeDef,
+    ResponseMetadataTypeDef,
     ResultRowValueTypeDef,
     SMSChannelRequestTypeDef,
     SegmentConditionTypeDef,
     SegmentReferenceTypeDef,
     SegmentImportResourceTypeDef,
     SendOTPMessageRequestParametersTypeDef,
     SimpleEmailPartTypeDef,
@@ -505,50 +514,49 @@
     TemplateVersionResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateRecommenderConfigurationTypeDef,
     VoiceChannelRequestTypeDef,
     VerificationResponseTypeDef,
     VerifyOTPMessageRequestParametersTypeDef,
     UpdateAdmChannelRequestRequestTypeDef,
+    DeleteAdmChannelResponseTypeDef,
+    GetAdmChannelResponseTypeDef,
+    UpdateAdmChannelResponseTypeDef,
     UpdateApnsChannelRequestRequestTypeDef,
+    DeleteApnsChannelResponseTypeDef,
+    GetApnsChannelResponseTypeDef,
+    UpdateApnsChannelResponseTypeDef,
     UpdateApnsSandboxChannelRequestRequestTypeDef,
+    DeleteApnsSandboxChannelResponseTypeDef,
+    GetApnsSandboxChannelResponseTypeDef,
+    UpdateApnsSandboxChannelResponseTypeDef,
     UpdateApnsVoipChannelRequestRequestTypeDef,
+    DeleteApnsVoipChannelResponseTypeDef,
+    GetApnsVoipChannelResponseTypeDef,
+    UpdateApnsVoipChannelResponseTypeDef,
     UpdateApnsVoipSandboxChannelRequestRequestTypeDef,
+    DeleteApnsVoipSandboxChannelResponseTypeDef,
+    GetApnsVoipSandboxChannelResponseTypeDef,
+    UpdateApnsVoipSandboxChannelResponseTypeDef,
     ActivitiesResponseTypeDef,
     ApplicationsResponseTypeDef,
+    CreateAppResponseTypeDef,
+    DeleteAppResponseTypeDef,
+    GetAppResponseTypeDef,
     ApplicationSettingsResourceTypeDef,
     WriteApplicationSettingsRequestTypeDef,
+    RemoveAttributesResponseTypeDef,
     UpdateBaiduChannelRequestRequestTypeDef,
+    DeleteBaiduChannelResponseTypeDef,
+    GetBaiduChannelResponseTypeDef,
+    UpdateBaiduChannelResponseTypeDef,
     ChannelsResponseTypeDef,
     ClosedDaysTypeDef,
     WaitActivityTypeDef,
     CreateAppRequestRequestTypeDef,
-    CreateAppResponseTypeDef,
-    DeleteAdmChannelResponseTypeDef,
-    DeleteApnsChannelResponseTypeDef,
-    DeleteApnsSandboxChannelResponseTypeDef,
-    DeleteApnsVoipChannelResponseTypeDef,
-    DeleteApnsVoipSandboxChannelResponseTypeDef,
-    DeleteAppResponseTypeDef,
-    DeleteBaiduChannelResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetAdmChannelResponseTypeDef,
-    GetApnsChannelResponseTypeDef,
-    GetApnsSandboxChannelResponseTypeDef,
-    GetApnsVoipChannelResponseTypeDef,
-    GetApnsVoipSandboxChannelResponseTypeDef,
-    GetAppResponseTypeDef,
-    GetBaiduChannelResponseTypeDef,
-    RemoveAttributesResponseTypeDef,
-    UpdateAdmChannelResponseTypeDef,
-    UpdateApnsChannelResponseTypeDef,
-    UpdateApnsSandboxChannelResponseTypeDef,
-    UpdateApnsVoipChannelResponseTypeDef,
-    UpdateApnsVoipSandboxChannelResponseTypeDef,
-    UpdateBaiduChannelResponseTypeDef,
     CreateEmailTemplateRequestRequestTypeDef,
     UpdateEmailTemplateRequestRequestTypeDef,
     CreateEmailTemplateResponseTypeDef,
     CreatePushTemplateResponseTypeDef,
     CreateSmsTemplateResponseTypeDef,
     CreateVoiceTemplateResponseTypeDef,
     CreateExportJobRequestRequestTypeDef,
@@ -608,19 +616,22 @@
     ItemResponseTypeDef,
     EventTypeDef,
     ExportJobResponseTypeDef,
     UpdateGcmChannelRequestRequestTypeDef,
     GPSPointDimensionTypeDef,
     GetJourneyExecutionActivityMetricsResponseTypeDef,
     GetJourneyExecutionMetricsResponseTypeDef,
+    GetJourneyRunExecutionActivityMetricsResponseTypeDef,
+    GetJourneyRunExecutionMetricsResponseTypeDef,
     GetSmsTemplateResponseTypeDef,
     GetVoiceTemplateResponseTypeDef,
     ImportJobResponseTypeDef,
     InAppMessageButtonTypeDef,
     PushMessageActivityTypeDef,
+    JourneyRunsResponseTypeDef,
     SMSMessageActivityTypeDef,
     UpdateJourneyStateRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     MessageResponseTypeDef,
     PhoneNumberValidateRequestRequestTypeDef,
     PhoneNumberValidateResponseTypeDef,
@@ -666,14 +677,15 @@
     ExportJobsResponseTypeDef,
     GetExportJobResponseTypeDef,
     SegmentLocationTypeDef,
     CreateImportJobResponseTypeDef,
     GetImportJobResponseTypeDef,
     ImportJobsResponseTypeDef,
     InAppMessageContentTypeDef,
+    GetJourneyRunsResponseTypeDef,
     SendMessagesResponseTypeDef,
     SendOTPMessageResponseTypeDef,
     BaseKpiResultTypeDef,
     EmailMessageTypeDef,
     ListTemplatesResponseTypeDef,
     ListTemplateVersionsResponseTypeDef,
     UpdateEndpointsBatchRequestRequestTypeDef,
@@ -768,43 +780,43 @@
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

### Comparing `types-aiobotocore-pinpoint-2.5.0.post1/types_aiobotocore_pinpoint.egg-info/SOURCES.txt` & `types-aiobotocore-pinpoint-2.5.1/types_aiobotocore_pinpoint.egg-info/SOURCES.txt`

 * *Files identical despite different names*

