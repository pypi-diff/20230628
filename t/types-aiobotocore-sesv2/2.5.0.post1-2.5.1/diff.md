# Comparing `tmp/types-aiobotocore-sesv2-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-sesv2-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-sesv2-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:20 2023, max compression
+gzip compressed data, was "types-aiobotocore-sesv2-2.5.1.tar", last modified: Wed Jun 28 01:44:11 2023, max compression
```

## Comparing `types-aiobotocore-sesv2-2.5.0.post1.tar` & `types-aiobotocore-sesv2-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:20.719631 types-aiobotocore-sesv2-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:24:08.000000 types-aiobotocore-sesv2-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    21152 2023-03-11 12:27:20.719631 types-aiobotocore-sesv2-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    19589 2023-03-11 12:24:08.000000 types-aiobotocore-sesv2-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:20.719631 types-aiobotocore-sesv2-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2110 2023-03-11 12:24:08.000000 types-aiobotocore-sesv2-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:20.711631 types-aiobotocore-sesv2-2.5.0.post1/types_aiobotocore_sesv2/
--rw-r--r--   0 runner    (1001) docker     (123)      426 2023-03-11 12:24:08.000000 types-aiobotocore-sesv2-2.5.0.post1/types_aiobotocore_sesv2/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      425 2023-03-11 12:24:08.000000 types-aiobotocore-sesv2-2.5.0.post1/types_aiobotocore_sesv2/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      924 2023-03-11 12:24:08.000000 types-aiobotocore-sesv2-2.5.0.post1/types_aiobotocore_sesv2/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    59315 2023-03-11 12:24:09.000000 types-aiobotocore-sesv2-2.5.0.post1/types_aiobotocore_sesv2/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    59221 2023-03-11 12:24:09.000000 types-aiobotocore-sesv2-2.5.0.post1/types_aiobotocore_sesv2/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    11569 2023-03-11 12:24:09.000000 types-aiobotocore-sesv2-2.5.0.post1/types_aiobotocore_sesv2/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    11567 2023-03-11 12:24:09.000000 types-aiobotocore-sesv2-2.5.0.post1/types_aiobotocore_sesv2/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:24:08.000000 types-aiobotocore-sesv2-2.5.0.post1/types_aiobotocore_sesv2/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    68894 2023-03-11 12:24:13.000000 types-aiobotocore-sesv2-2.5.0.post1/types_aiobotocore_sesv2/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    68824 2023-03-11 12:24:13.000000 types-aiobotocore-sesv2-2.5.0.post1/types_aiobotocore_sesv2/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:24:08.000000 types-aiobotocore-sesv2-2.5.0.post1/types_aiobotocore_sesv2/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:20.719631 types-aiobotocore-sesv2-2.5.0.post1/types_aiobotocore_sesv2.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    21152 2023-03-11 12:27:20.000000 types-aiobotocore-sesv2-2.5.0.post1/types_aiobotocore_sesv2.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      700 2023-03-11 12:27:20.000000 types-aiobotocore-sesv2-2.5.0.post1/types_aiobotocore_sesv2.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:20.000000 types-aiobotocore-sesv2-2.5.0.post1/types_aiobotocore_sesv2.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:20.000000 types-aiobotocore-sesv2-2.5.0.post1/types_aiobotocore_sesv2.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:20.000000 types-aiobotocore-sesv2-2.5.0.post1/types_aiobotocore_sesv2.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       24 2023-03-11 12:27:20.000000 types-aiobotocore-sesv2-2.5.0.post1/types_aiobotocore_sesv2.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:11.670216 types-aiobotocore-sesv2-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:40:57.000000 types-aiobotocore-sesv2-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    21204 2023-06-28 01:44:11.670216 types-aiobotocore-sesv2-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    19647 2023-06-28 01:40:57.000000 types-aiobotocore-sesv2-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:11.670216 types-aiobotocore-sesv2-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2104 2023-06-28 01:40:57.000000 types-aiobotocore-sesv2-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:11.670216 types-aiobotocore-sesv2-2.5.1/types_aiobotocore_sesv2/
+-rw-r--r--   0 runner    (1001) docker     (123)      426 2023-06-28 01:40:57.000000 types-aiobotocore-sesv2-2.5.1/types_aiobotocore_sesv2/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      425 2023-06-28 01:40:57.000000 types-aiobotocore-sesv2-2.5.1/types_aiobotocore_sesv2/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      912 2023-06-28 01:40:57.000000 types-aiobotocore-sesv2-2.5.1/types_aiobotocore_sesv2/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    59902 2023-06-28 01:40:57.000000 types-aiobotocore-sesv2-2.5.1/types_aiobotocore_sesv2/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    59807 2023-06-28 01:40:57.000000 types-aiobotocore-sesv2-2.5.1/types_aiobotocore_sesv2/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    11786 2023-06-28 01:40:58.000000 types-aiobotocore-sesv2-2.5.1/types_aiobotocore_sesv2/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11784 2023-06-28 01:40:57.000000 types-aiobotocore-sesv2-2.5.1/types_aiobotocore_sesv2/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:40:57.000000 types-aiobotocore-sesv2-2.5.1/types_aiobotocore_sesv2/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    69255 2023-06-28 01:41:01.000000 types-aiobotocore-sesv2-2.5.1/types_aiobotocore_sesv2/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    69185 2023-06-28 01:40:58.000000 types-aiobotocore-sesv2-2.5.1/types_aiobotocore_sesv2/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:40:57.000000 types-aiobotocore-sesv2-2.5.1/types_aiobotocore_sesv2/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:11.670216 types-aiobotocore-sesv2-2.5.1/types_aiobotocore_sesv2.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    21204 2023-06-28 01:44:11.000000 types-aiobotocore-sesv2-2.5.1/types_aiobotocore_sesv2.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      700 2023-06-28 01:44:11.000000 types-aiobotocore-sesv2-2.5.1/types_aiobotocore_sesv2.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:11.000000 types-aiobotocore-sesv2-2.5.1/types_aiobotocore_sesv2.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:11.000000 types-aiobotocore-sesv2-2.5.1/types_aiobotocore_sesv2.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:11.000000 types-aiobotocore-sesv2-2.5.1/types_aiobotocore_sesv2.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       24 2023-06-28 01:44:11.000000 types-aiobotocore-sesv2-2.5.1/types_aiobotocore_sesv2.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-sesv2-2.5.0.post1/LICENSE` & `types-aiobotocore-sesv2-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-sesv2-2.5.0.post1/PKG-INFO` & `types-aiobotocore-sesv2-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-sesv2
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SESV2 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SESV2 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sesv2/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-sesv2"></a>
 
 # types-aiobotocore-sesv2
 
 [![PyPI - types-aiobotocore-sesv2](https://img.shields.io/pypi/v/types-aiobotocore-sesv2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sesv2)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-sesv2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sesv2)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sesv2/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-sesv2?color=blue)](https://pypistats.org/packages/types-aiobotocore-sesv2)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SESV2 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sesv2.html#SESV2)
+[aiobotocore.SESV2 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sesv2.html#SESV2)
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
 [types-aiobotocore-sesv2 docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sesv2/).
 
 See how it helps to find and fix potential bugs:
 
@@ -325,15 +325,14 @@
 
 ```python
 from types_aiobotocore_sesv2.type_defs import (
     ReviewDetailsTypeDef,
     BatchGetMetricDataQueryTypeDef,
     MetricDataErrorTypeDef,
     MetricDataResultTypeDef,
-    ResponseMetadataTypeDef,
     BlacklistEntryTypeDef,
     ContentTypeDef,
     TemplateTypeDef,
     BulkEmailEntryResultTypeDef,
     DestinationTypeDef,
     MessageTagTypeDef,
     CloudWatchDimensionConfigurationTypeDef,
@@ -344,19 +343,21 @@
     ReputationOptionsTypeDef,
     SendingOptionsTypeDef,
     SuppressionOptionsTypeDef,
     TagTypeDef,
     TrackingOptionsTypeDef,
     TopicTypeDef,
     CreateCustomVerificationEmailTemplateRequestRequestTypeDef,
+    CreateDeliverabilityTestReportResponseTypeDef,
     CreateEmailIdentityPolicyRequestRequestTypeDef,
     DkimSigningAttributesTypeDef,
     DkimAttributesTypeDef,
     EmailTemplateContentTypeDef,
     ImportDataSourceTypeDef,
+    CreateImportJobResponseTypeDef,
     CustomVerificationEmailTemplateMetadataTypeDef,
     DomainIspPlacementTypeDef,
     VolumeStatisticsTypeDef,
     DashboardAttributesTypeDef,
     DashboardOptionsTypeDef,
     DedicatedIpPoolTypeDef,
     DedicatedIpTypeDef,
@@ -383,36 +384,40 @@
     SuppressionAttributesTypeDef,
     GetBlacklistReportsRequestRequestTypeDef,
     GetConfigurationSetEventDestinationsRequestRequestTypeDef,
     GetConfigurationSetRequestRequestTypeDef,
     GetContactListRequestRequestTypeDef,
     GetContactRequestRequestTypeDef,
     GetCustomVerificationEmailTemplateRequestRequestTypeDef,
+    GetCustomVerificationEmailTemplateResponseTypeDef,
     GetDedicatedIpPoolRequestRequestTypeDef,
     GetDedicatedIpRequestRequestTypeDef,
     GetDedicatedIpsRequestRequestTypeDef,
     GetDeliverabilityTestReportRequestRequestTypeDef,
     PlacementStatisticsTypeDef,
     GetDomainDeliverabilityCampaignRequestRequestTypeDef,
     GetDomainStatisticsReportRequestRequestTypeDef,
     GetEmailIdentityPoliciesRequestRequestTypeDef,
+    GetEmailIdentityPoliciesResponseTypeDef,
     GetEmailIdentityRequestRequestTypeDef,
     MailFromAttributesTypeDef,
     GetEmailTemplateRequestRequestTypeDef,
     GetImportJobRequestRequestTypeDef,
     GetSuppressedDestinationRequestRequestTypeDef,
     GuardianAttributesTypeDef,
     GuardianOptionsTypeDef,
     IdentityInfoTypeDef,
     SuppressionListDestinationTypeDef,
     ListConfigurationSetsRequestRequestTypeDef,
+    ListConfigurationSetsResponseTypeDef,
     ListContactListsRequestRequestTypeDef,
     TopicFilterTypeDef,
     ListCustomVerificationEmailTemplatesRequestRequestTypeDef,
     ListDedicatedIpPoolsRequestRequestTypeDef,
+    ListDedicatedIpPoolsResponseTypeDef,
     ListDeliverabilityTestReportsRequestRequestTypeDef,
     ListDomainDeliverabilityCampaignsRequestRequestTypeDef,
     ListEmailIdentitiesRequestRequestTypeDef,
     ListEmailTemplatesRequestRequestTypeDef,
     ListImportJobsRequestRequestTypeDef,
     ListManagementOptionsTypeDef,
     ListRecommendationsRequestRequestTypeDef,
@@ -426,40 +431,36 @@
     PutAccountSuppressionAttributesRequestRequestTypeDef,
     PutConfigurationSetDeliveryOptionsRequestRequestTypeDef,
     PutConfigurationSetReputationOptionsRequestRequestTypeDef,
     PutConfigurationSetSendingOptionsRequestRequestTypeDef,
     PutConfigurationSetSuppressionOptionsRequestRequestTypeDef,
     PutConfigurationSetTrackingOptionsRequestRequestTypeDef,
     PutDedicatedIpInPoolRequestRequestTypeDef,
+    PutDedicatedIpPoolScalingAttributesRequestRequestTypeDef,
     PutDedicatedIpWarmupAttributesRequestRequestTypeDef,
     PutEmailIdentityConfigurationSetAttributesRequestRequestTypeDef,
     PutEmailIdentityDkimAttributesRequestRequestTypeDef,
+    PutEmailIdentityDkimSigningAttributesResponseTypeDef,
     PutEmailIdentityFeedbackAttributesRequestRequestTypeDef,
     PutEmailIdentityMailFromAttributesRequestRequestTypeDef,
     PutSuppressedDestinationRequestRequestTypeDef,
     ReplacementTemplateTypeDef,
+    ResponseMetadataTypeDef,
     SendCustomVerificationEmailRequestRequestTypeDef,
+    SendCustomVerificationEmailResponseTypeDef,
+    SendEmailResponseTypeDef,
     SuppressedDestinationAttributesTypeDef,
     TestRenderEmailTemplateRequestRequestTypeDef,
+    TestRenderEmailTemplateResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateCustomVerificationEmailTemplateRequestRequestTypeDef,
     UpdateEmailIdentityPolicyRequestRequestTypeDef,
     AccountDetailsTypeDef,
     BatchGetMetricDataRequestRequestTypeDef,
     BatchGetMetricDataResponseTypeDef,
-    CreateDeliverabilityTestReportResponseTypeDef,
-    CreateImportJobResponseTypeDef,
-    GetCustomVerificationEmailTemplateResponseTypeDef,
-    GetEmailIdentityPoliciesResponseTypeDef,
-    ListConfigurationSetsResponseTypeDef,
-    ListDedicatedIpPoolsResponseTypeDef,
-    PutEmailIdentityDkimSigningAttributesResponseTypeDef,
-    SendCustomVerificationEmailResponseTypeDef,
-    SendEmailResponseTypeDef,
-    TestRenderEmailTemplateResponseTypeDef,
     GetBlacklistReportsResponseTypeDef,
     BodyTypeDef,
     BulkEmailContentTypeDef,
     SendBulkEmailResponseTypeDef,
     CloudWatchDestinationTypeDef,
     ListContactListsResponseTypeDef,
     ContactTypeDef,
@@ -537,43 +538,43 @@
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

### Comparing `types-aiobotocore-sesv2-2.5.0.post1/README.md` & `types-aiobotocore-sesv2-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-sesv2"></a>
 
 # types-aiobotocore-sesv2
 
 [![PyPI - types-aiobotocore-sesv2](https://img.shields.io/pypi/v/types-aiobotocore-sesv2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sesv2)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-sesv2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sesv2)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sesv2/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-sesv2?color=blue)](https://pypistats.org/packages/types-aiobotocore-sesv2)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SESV2 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sesv2.html#SESV2)
+[aiobotocore.SESV2 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sesv2.html#SESV2)
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
 [types-aiobotocore-sesv2 docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sesv2/).
 
 See how it helps to find and fix potential bugs:
 
@@ -292,15 +292,14 @@
 
 ```python
 from types_aiobotocore_sesv2.type_defs import (
     ReviewDetailsTypeDef,
     BatchGetMetricDataQueryTypeDef,
     MetricDataErrorTypeDef,
     MetricDataResultTypeDef,
-    ResponseMetadataTypeDef,
     BlacklistEntryTypeDef,
     ContentTypeDef,
     TemplateTypeDef,
     BulkEmailEntryResultTypeDef,
     DestinationTypeDef,
     MessageTagTypeDef,
     CloudWatchDimensionConfigurationTypeDef,
@@ -311,19 +310,21 @@
     ReputationOptionsTypeDef,
     SendingOptionsTypeDef,
     SuppressionOptionsTypeDef,
     TagTypeDef,
     TrackingOptionsTypeDef,
     TopicTypeDef,
     CreateCustomVerificationEmailTemplateRequestRequestTypeDef,
+    CreateDeliverabilityTestReportResponseTypeDef,
     CreateEmailIdentityPolicyRequestRequestTypeDef,
     DkimSigningAttributesTypeDef,
     DkimAttributesTypeDef,
     EmailTemplateContentTypeDef,
     ImportDataSourceTypeDef,
+    CreateImportJobResponseTypeDef,
     CustomVerificationEmailTemplateMetadataTypeDef,
     DomainIspPlacementTypeDef,
     VolumeStatisticsTypeDef,
     DashboardAttributesTypeDef,
     DashboardOptionsTypeDef,
     DedicatedIpPoolTypeDef,
     DedicatedIpTypeDef,
@@ -350,36 +351,40 @@
     SuppressionAttributesTypeDef,
     GetBlacklistReportsRequestRequestTypeDef,
     GetConfigurationSetEventDestinationsRequestRequestTypeDef,
     GetConfigurationSetRequestRequestTypeDef,
     GetContactListRequestRequestTypeDef,
     GetContactRequestRequestTypeDef,
     GetCustomVerificationEmailTemplateRequestRequestTypeDef,
+    GetCustomVerificationEmailTemplateResponseTypeDef,
     GetDedicatedIpPoolRequestRequestTypeDef,
     GetDedicatedIpRequestRequestTypeDef,
     GetDedicatedIpsRequestRequestTypeDef,
     GetDeliverabilityTestReportRequestRequestTypeDef,
     PlacementStatisticsTypeDef,
     GetDomainDeliverabilityCampaignRequestRequestTypeDef,
     GetDomainStatisticsReportRequestRequestTypeDef,
     GetEmailIdentityPoliciesRequestRequestTypeDef,
+    GetEmailIdentityPoliciesResponseTypeDef,
     GetEmailIdentityRequestRequestTypeDef,
     MailFromAttributesTypeDef,
     GetEmailTemplateRequestRequestTypeDef,
     GetImportJobRequestRequestTypeDef,
     GetSuppressedDestinationRequestRequestTypeDef,
     GuardianAttributesTypeDef,
     GuardianOptionsTypeDef,
     IdentityInfoTypeDef,
     SuppressionListDestinationTypeDef,
     ListConfigurationSetsRequestRequestTypeDef,
+    ListConfigurationSetsResponseTypeDef,
     ListContactListsRequestRequestTypeDef,
     TopicFilterTypeDef,
     ListCustomVerificationEmailTemplatesRequestRequestTypeDef,
     ListDedicatedIpPoolsRequestRequestTypeDef,
+    ListDedicatedIpPoolsResponseTypeDef,
     ListDeliverabilityTestReportsRequestRequestTypeDef,
     ListDomainDeliverabilityCampaignsRequestRequestTypeDef,
     ListEmailIdentitiesRequestRequestTypeDef,
     ListEmailTemplatesRequestRequestTypeDef,
     ListImportJobsRequestRequestTypeDef,
     ListManagementOptionsTypeDef,
     ListRecommendationsRequestRequestTypeDef,
@@ -393,40 +398,36 @@
     PutAccountSuppressionAttributesRequestRequestTypeDef,
     PutConfigurationSetDeliveryOptionsRequestRequestTypeDef,
     PutConfigurationSetReputationOptionsRequestRequestTypeDef,
     PutConfigurationSetSendingOptionsRequestRequestTypeDef,
     PutConfigurationSetSuppressionOptionsRequestRequestTypeDef,
     PutConfigurationSetTrackingOptionsRequestRequestTypeDef,
     PutDedicatedIpInPoolRequestRequestTypeDef,
+    PutDedicatedIpPoolScalingAttributesRequestRequestTypeDef,
     PutDedicatedIpWarmupAttributesRequestRequestTypeDef,
     PutEmailIdentityConfigurationSetAttributesRequestRequestTypeDef,
     PutEmailIdentityDkimAttributesRequestRequestTypeDef,
+    PutEmailIdentityDkimSigningAttributesResponseTypeDef,
     PutEmailIdentityFeedbackAttributesRequestRequestTypeDef,
     PutEmailIdentityMailFromAttributesRequestRequestTypeDef,
     PutSuppressedDestinationRequestRequestTypeDef,
     ReplacementTemplateTypeDef,
+    ResponseMetadataTypeDef,
     SendCustomVerificationEmailRequestRequestTypeDef,
+    SendCustomVerificationEmailResponseTypeDef,
+    SendEmailResponseTypeDef,
     SuppressedDestinationAttributesTypeDef,
     TestRenderEmailTemplateRequestRequestTypeDef,
+    TestRenderEmailTemplateResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateCustomVerificationEmailTemplateRequestRequestTypeDef,
     UpdateEmailIdentityPolicyRequestRequestTypeDef,
     AccountDetailsTypeDef,
     BatchGetMetricDataRequestRequestTypeDef,
     BatchGetMetricDataResponseTypeDef,
-    CreateDeliverabilityTestReportResponseTypeDef,
-    CreateImportJobResponseTypeDef,
-    GetCustomVerificationEmailTemplateResponseTypeDef,
-    GetEmailIdentityPoliciesResponseTypeDef,
-    ListConfigurationSetsResponseTypeDef,
-    ListDedicatedIpPoolsResponseTypeDef,
-    PutEmailIdentityDkimSigningAttributesResponseTypeDef,
-    SendCustomVerificationEmailResponseTypeDef,
-    SendEmailResponseTypeDef,
-    TestRenderEmailTemplateResponseTypeDef,
     GetBlacklistReportsResponseTypeDef,
     BodyTypeDef,
     BulkEmailContentTypeDef,
     SendBulkEmailResponseTypeDef,
     CloudWatchDestinationTypeDef,
     ListContactListsResponseTypeDef,
     ContactTypeDef,
@@ -504,43 +505,43 @@
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

### Comparing `types-aiobotocore-sesv2-2.5.0.post1/setup.py` & `types-aiobotocore-sesv2-2.5.1/setup.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-sesv2.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-sesv2",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_sesv2"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.SESV2 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.SESV2 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sesv2/"
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

### Comparing `types-aiobotocore-sesv2-2.5.0.post1/types_aiobotocore_sesv2/__main__.py` & `types-aiobotocore-sesv2-2.5.1/types_aiobotocore_sesv2/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.SESV2 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.SESV2 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sesv2//\nBoto3 docs:  "
         "    https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sesv2.html#SESV2\nOther"
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

### Comparing `types-aiobotocore-sesv2-2.5.0.post1/types_aiobotocore_sesv2/client.py` & `types-aiobotocore-sesv2-2.5.1/types_aiobotocore_sesv2/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -914,14 +914,24 @@
         """
         Move a dedicated IP address to an existing dedicated IP pool.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sesv2.html#SESV2.Client.put_dedicated_ip_in_pool)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sesv2/client/#put_dedicated_ip_in_pool)
         """
 
+    async def put_dedicated_ip_pool_scaling_attributes(
+        self, *, PoolName: str, ScalingMode: ScalingModeType
+    ) -> Dict[str, Any]:
+        """
+        Used to convert a dedicated IP pool to a different scaling mode.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sesv2.html#SESV2.Client.put_dedicated_ip_pool_scaling_attributes)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sesv2/client/#put_dedicated_ip_pool_scaling_attributes)
+        """
+
     async def put_dedicated_ip_warmup_attributes(
         self, *, Ip: str, WarmupPercentage: int
     ) -> Dict[str, Any]:
         """
         See also: [AWS API
         Documentation](https://docs.aws.amazon.com/goto/WebAPI/sesv2-2019-09-27/PutDedicatedIpWarmupAttributes).
```

### Comparing `types-aiobotocore-sesv2-2.5.0.post1/types_aiobotocore_sesv2/client.pyi` & `types-aiobotocore-sesv2-2.5.1/types_aiobotocore_sesv2/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -841,14 +841,23 @@
     ) -> Dict[str, Any]:
         """
         Move a dedicated IP address to an existing dedicated IP pool.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sesv2.html#SESV2.Client.put_dedicated_ip_in_pool)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sesv2/client/#put_dedicated_ip_in_pool)
         """
+    async def put_dedicated_ip_pool_scaling_attributes(
+        self, *, PoolName: str, ScalingMode: ScalingModeType
+    ) -> Dict[str, Any]:
+        """
+        Used to convert a dedicated IP pool to a different scaling mode.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sesv2.html#SESV2.Client.put_dedicated_ip_pool_scaling_attributes)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sesv2/client/#put_dedicated_ip_pool_scaling_attributes)
+        """
     async def put_dedicated_ip_warmup_attributes(
         self, *, Ip: str, WarmupPercentage: int
     ) -> Dict[str, Any]:
         """
         See also: [AWS API
         Documentation](https://docs.aws.amazon.com/goto/WebAPI/sesv2-2019-09-27/PutDedicatedIpWarmupAttributes).
```

### Comparing `types-aiobotocore-sesv2-2.5.0.post1/types_aiobotocore_sesv2/literals.py` & `types-aiobotocore-sesv2-2.5.1/types_aiobotocore_sesv2/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -14,15 +14,14 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "BehaviorOnMxFailureType",
     "BulkEmailStatusType",
     "ContactLanguageType",
     "ContactListImportActionType",
     "DataFormatType",
     "DeliverabilityDashboardAccountStatusType",
@@ -56,15 +55,14 @@
     "WarmupStatusType",
     "SESV2ServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
-
 BehaviorOnMxFailureType = Literal["REJECT_MESSAGE", "USE_DEFAULT_VALUE"]
 BulkEmailStatusType = Literal[
     "ACCOUNT_DAILY_QUOTA_EXCEEDED",
     "ACCOUNT_SENDING_PAUSED",
     "ACCOUNT_SUSPENDED",
     "ACCOUNT_THROTTLED",
     "CONFIGURATION_SET_NOT_FOUND",
@@ -119,15 +117,15 @@
     "PERMANENT_BOUNCE",
     "SEND",
     "TRANSIENT_BOUNCE",
 ]
 QueryErrorCodeType = Literal["ACCESS_DENIED", "INTERNAL_FAILURE"]
 RecommendationImpactType = Literal["HIGH", "LOW"]
 RecommendationStatusType = Literal["FIXED", "OPEN"]
-RecommendationTypeType = Literal["DKIM", "DMARC", "SPF"]
+RecommendationTypeType = Literal["BIMI", "DKIM", "DMARC", "SPF"]
 ReviewStatusType = Literal["DENIED", "FAILED", "GRANTED", "PENDING"]
 ScalingModeType = Literal["MANAGED", "STANDARD"]
 SubscriptionStatusType = Literal["OPT_IN", "OPT_OUT"]
 SuppressionListImportActionType = Literal["DELETE", "PUT"]
 SuppressionListReasonType = Literal["BOUNCE", "COMPLAINT"]
 TlsPolicyType = Literal["OPTIONAL", "REQUIRE"]
 VerificationStatusType = Literal["FAILED", "NOT_STARTED", "PENDING", "SUCCESS", "TEMPORARY_FAILURE"]
@@ -191,14 +189,15 @@
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
@@ -277,14 +276,15 @@
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
@@ -295,14 +295,15 @@
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
@@ -338,14 +339,15 @@
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
@@ -364,16 +366,19 @@
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
@@ -457,15 +462,17 @@
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

### Comparing `types-aiobotocore-sesv2-2.5.0.post1/types_aiobotocore_sesv2/literals.pyi` & `types-aiobotocore-sesv2-2.5.1/types_aiobotocore_sesv2/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -14,14 +14,15 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "BehaviorOnMxFailureType",
     "BulkEmailStatusType",
     "ContactLanguageType",
     "ContactListImportActionType",
     "DataFormatType",
     "DeliverabilityDashboardAccountStatusType",
@@ -55,14 +56,15 @@
     "WarmupStatusType",
     "SESV2ServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
+
 BehaviorOnMxFailureType = Literal["REJECT_MESSAGE", "USE_DEFAULT_VALUE"]
 BulkEmailStatusType = Literal[
     "ACCOUNT_DAILY_QUOTA_EXCEEDED",
     "ACCOUNT_SENDING_PAUSED",
     "ACCOUNT_SUSPENDED",
     "ACCOUNT_THROTTLED",
     "CONFIGURATION_SET_NOT_FOUND",
@@ -117,15 +119,15 @@
     "PERMANENT_BOUNCE",
     "SEND",
     "TRANSIENT_BOUNCE",
 ]
 QueryErrorCodeType = Literal["ACCESS_DENIED", "INTERNAL_FAILURE"]
 RecommendationImpactType = Literal["HIGH", "LOW"]
 RecommendationStatusType = Literal["FIXED", "OPEN"]
-RecommendationTypeType = Literal["DKIM", "DMARC", "SPF"]
+RecommendationTypeType = Literal["BIMI", "DKIM", "DMARC", "SPF"]
 ReviewStatusType = Literal["DENIED", "FAILED", "GRANTED", "PENDING"]
 ScalingModeType = Literal["MANAGED", "STANDARD"]
 SubscriptionStatusType = Literal["OPT_IN", "OPT_OUT"]
 SuppressionListImportActionType = Literal["DELETE", "PUT"]
 SuppressionListReasonType = Literal["BOUNCE", "COMPLAINT"]
 TlsPolicyType = Literal["OPTIONAL", "REQUIRE"]
 VerificationStatusType = Literal["FAILED", "NOT_STARTED", "PENDING", "SUCCESS", "TEMPORARY_FAILURE"]
@@ -189,14 +191,15 @@
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
@@ -275,14 +278,15 @@
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
@@ -293,14 +297,15 @@
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
@@ -336,14 +341,15 @@
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
@@ -362,16 +368,19 @@
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
@@ -455,15 +464,17 @@
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

### Comparing `types-aiobotocore-sesv2-2.5.0.post1/types_aiobotocore_sesv2/type_defs.py` & `types-aiobotocore-sesv2-2.5.1/types_aiobotocore_sesv2/type_defs.py`

 * *Files 4% similar despite different names*

```diff
@@ -64,15 +64,14 @@
 
 
 __all__ = (
     "ReviewDetailsTypeDef",
     "BatchGetMetricDataQueryTypeDef",
     "MetricDataErrorTypeDef",
     "MetricDataResultTypeDef",
-    "ResponseMetadataTypeDef",
     "BlacklistEntryTypeDef",
     "ContentTypeDef",
     "TemplateTypeDef",
     "BulkEmailEntryResultTypeDef",
     "DestinationTypeDef",
     "MessageTagTypeDef",
     "CloudWatchDimensionConfigurationTypeDef",
@@ -83,19 +82,21 @@
     "ReputationOptionsTypeDef",
     "SendingOptionsTypeDef",
     "SuppressionOptionsTypeDef",
     "TagTypeDef",
     "TrackingOptionsTypeDef",
     "TopicTypeDef",
     "CreateCustomVerificationEmailTemplateRequestRequestTypeDef",
+    "CreateDeliverabilityTestReportResponseTypeDef",
     "CreateEmailIdentityPolicyRequestRequestTypeDef",
     "DkimSigningAttributesTypeDef",
     "DkimAttributesTypeDef",
     "EmailTemplateContentTypeDef",
     "ImportDataSourceTypeDef",
+    "CreateImportJobResponseTypeDef",
     "CustomVerificationEmailTemplateMetadataTypeDef",
     "DomainIspPlacementTypeDef",
     "VolumeStatisticsTypeDef",
     "DashboardAttributesTypeDef",
     "DashboardOptionsTypeDef",
     "DedicatedIpPoolTypeDef",
     "DedicatedIpTypeDef",
@@ -122,36 +123,40 @@
     "SuppressionAttributesTypeDef",
     "GetBlacklistReportsRequestRequestTypeDef",
     "GetConfigurationSetEventDestinationsRequestRequestTypeDef",
     "GetConfigurationSetRequestRequestTypeDef",
     "GetContactListRequestRequestTypeDef",
     "GetContactRequestRequestTypeDef",
     "GetCustomVerificationEmailTemplateRequestRequestTypeDef",
+    "GetCustomVerificationEmailTemplateResponseTypeDef",
     "GetDedicatedIpPoolRequestRequestTypeDef",
     "GetDedicatedIpRequestRequestTypeDef",
     "GetDedicatedIpsRequestRequestTypeDef",
     "GetDeliverabilityTestReportRequestRequestTypeDef",
     "PlacementStatisticsTypeDef",
     "GetDomainDeliverabilityCampaignRequestRequestTypeDef",
     "GetDomainStatisticsReportRequestRequestTypeDef",
     "GetEmailIdentityPoliciesRequestRequestTypeDef",
+    "GetEmailIdentityPoliciesResponseTypeDef",
     "GetEmailIdentityRequestRequestTypeDef",
     "MailFromAttributesTypeDef",
     "GetEmailTemplateRequestRequestTypeDef",
     "GetImportJobRequestRequestTypeDef",
     "GetSuppressedDestinationRequestRequestTypeDef",
     "GuardianAttributesTypeDef",
     "GuardianOptionsTypeDef",
     "IdentityInfoTypeDef",
     "SuppressionListDestinationTypeDef",
     "ListConfigurationSetsRequestRequestTypeDef",
+    "ListConfigurationSetsResponseTypeDef",
     "ListContactListsRequestRequestTypeDef",
     "TopicFilterTypeDef",
     "ListCustomVerificationEmailTemplatesRequestRequestTypeDef",
     "ListDedicatedIpPoolsRequestRequestTypeDef",
+    "ListDedicatedIpPoolsResponseTypeDef",
     "ListDeliverabilityTestReportsRequestRequestTypeDef",
     "ListDomainDeliverabilityCampaignsRequestRequestTypeDef",
     "ListEmailIdentitiesRequestRequestTypeDef",
     "ListEmailTemplatesRequestRequestTypeDef",
     "ListImportJobsRequestRequestTypeDef",
     "ListManagementOptionsTypeDef",
     "ListRecommendationsRequestRequestTypeDef",
@@ -165,40 +170,36 @@
     "PutAccountSuppressionAttributesRequestRequestTypeDef",
     "PutConfigurationSetDeliveryOptionsRequestRequestTypeDef",
     "PutConfigurationSetReputationOptionsRequestRequestTypeDef",
     "PutConfigurationSetSendingOptionsRequestRequestTypeDef",
     "PutConfigurationSetSuppressionOptionsRequestRequestTypeDef",
     "PutConfigurationSetTrackingOptionsRequestRequestTypeDef",
     "PutDedicatedIpInPoolRequestRequestTypeDef",
+    "PutDedicatedIpPoolScalingAttributesRequestRequestTypeDef",
     "PutDedicatedIpWarmupAttributesRequestRequestTypeDef",
     "PutEmailIdentityConfigurationSetAttributesRequestRequestTypeDef",
     "PutEmailIdentityDkimAttributesRequestRequestTypeDef",
+    "PutEmailIdentityDkimSigningAttributesResponseTypeDef",
     "PutEmailIdentityFeedbackAttributesRequestRequestTypeDef",
     "PutEmailIdentityMailFromAttributesRequestRequestTypeDef",
     "PutSuppressedDestinationRequestRequestTypeDef",
     "ReplacementTemplateTypeDef",
+    "ResponseMetadataTypeDef",
     "SendCustomVerificationEmailRequestRequestTypeDef",
+    "SendCustomVerificationEmailResponseTypeDef",
+    "SendEmailResponseTypeDef",
     "SuppressedDestinationAttributesTypeDef",
     "TestRenderEmailTemplateRequestRequestTypeDef",
+    "TestRenderEmailTemplateResponseTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateCustomVerificationEmailTemplateRequestRequestTypeDef",
     "UpdateEmailIdentityPolicyRequestRequestTypeDef",
     "AccountDetailsTypeDef",
     "BatchGetMetricDataRequestRequestTypeDef",
     "BatchGetMetricDataResponseTypeDef",
-    "CreateDeliverabilityTestReportResponseTypeDef",
-    "CreateImportJobResponseTypeDef",
-    "GetCustomVerificationEmailTemplateResponseTypeDef",
-    "GetEmailIdentityPoliciesResponseTypeDef",
-    "ListConfigurationSetsResponseTypeDef",
-    "ListDedicatedIpPoolsResponseTypeDef",
-    "PutEmailIdentityDkimSigningAttributesResponseTypeDef",
-    "SendCustomVerificationEmailResponseTypeDef",
-    "SendEmailResponseTypeDef",
-    "TestRenderEmailTemplateResponseTypeDef",
     "GetBlacklistReportsResponseTypeDef",
     "BodyTypeDef",
     "BulkEmailContentTypeDef",
     "SendBulkEmailResponseTypeDef",
     "CloudWatchDestinationTypeDef",
     "ListContactListsResponseTypeDef",
     "ContactTypeDef",
@@ -318,25 +319,14 @@
         "Id": str,
         "Timestamps": List[datetime],
         "Values": List[int],
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
 BlacklistEntryTypeDef = TypedDict(
     "BlacklistEntryTypeDef",
     {
         "RblName": str,
         "ListingTime": datetime,
         "Description": str,
     },
@@ -512,14 +502,23 @@
         "TemplateSubject": str,
         "TemplateContent": str,
         "SuccessRedirectionURL": str,
         "FailureRedirectionURL": str,
     },
 )
 
+CreateDeliverabilityTestReportResponseTypeDef = TypedDict(
+    "CreateDeliverabilityTestReportResponseTypeDef",
+    {
+        "ReportId": str,
+        "DeliverabilityTestStatus": DeliverabilityTestStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateEmailIdentityPolicyRequestRequestTypeDef = TypedDict(
     "CreateEmailIdentityPolicyRequestRequestTypeDef",
     {
         "EmailIdentity": str,
         "PolicyName": str,
         "Policy": str,
     },
@@ -563,14 +562,22 @@
     "ImportDataSourceTypeDef",
     {
         "S3Url": str,
         "DataFormat": DataFormatType,
     },
 )
 
+CreateImportJobResponseTypeDef = TypedDict(
+    "CreateImportJobResponseTypeDef",
+    {
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CustomVerificationEmailTemplateMetadataTypeDef = TypedDict(
     "CustomVerificationEmailTemplateMetadataTypeDef",
     {
         "TemplateName": str,
         "FromEmailAddress": str,
         "TemplateSubject": str,
         "SuccessRedirectionURL": str,
@@ -868,14 +875,27 @@
 GetCustomVerificationEmailTemplateRequestRequestTypeDef = TypedDict(
     "GetCustomVerificationEmailTemplateRequestRequestTypeDef",
     {
         "TemplateName": str,
     },
 )
 
+GetCustomVerificationEmailTemplateResponseTypeDef = TypedDict(
+    "GetCustomVerificationEmailTemplateResponseTypeDef",
+    {
+        "TemplateName": str,
+        "FromEmailAddress": str,
+        "TemplateSubject": str,
+        "TemplateContent": str,
+        "SuccessRedirectionURL": str,
+        "FailureRedirectionURL": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetDedicatedIpPoolRequestRequestTypeDef = TypedDict(
     "GetDedicatedIpPoolRequestRequestTypeDef",
     {
         "PoolName": str,
     },
 )
 
@@ -934,14 +954,22 @@
 GetEmailIdentityPoliciesRequestRequestTypeDef = TypedDict(
     "GetEmailIdentityPoliciesRequestRequestTypeDef",
     {
         "EmailIdentity": str,
     },
 )
 
+GetEmailIdentityPoliciesResponseTypeDef = TypedDict(
+    "GetEmailIdentityPoliciesResponseTypeDef",
+    {
+        "Policies": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetEmailIdentityRequestRequestTypeDef = TypedDict(
     "GetEmailIdentityRequestRequestTypeDef",
     {
         "EmailIdentity": str,
     },
 )
 
@@ -1014,14 +1042,23 @@
     {
         "NextToken": str,
         "PageSize": int,
     },
     total=False,
 )
 
+ListConfigurationSetsResponseTypeDef = TypedDict(
+    "ListConfigurationSetsResponseTypeDef",
+    {
+        "ConfigurationSets": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListContactListsRequestRequestTypeDef = TypedDict(
     "ListContactListsRequestRequestTypeDef",
     {
         "PageSize": int,
         "NextToken": str,
     },
     total=False,
@@ -1050,14 +1087,23 @@
     {
         "NextToken": str,
         "PageSize": int,
     },
     total=False,
 )
 
+ListDedicatedIpPoolsResponseTypeDef = TypedDict(
+    "ListDedicatedIpPoolsResponseTypeDef",
+    {
+        "DedicatedIpPools": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListDeliverabilityTestReportsRequestRequestTypeDef = TypedDict(
     "ListDeliverabilityTestReportsRequestRequestTypeDef",
     {
         "NextToken": str,
         "PageSize": int,
     },
     total=False,
@@ -1353,14 +1399,22 @@
     "PutDedicatedIpInPoolRequestRequestTypeDef",
     {
         "Ip": str,
         "DestinationPoolName": str,
     },
 )
 
+PutDedicatedIpPoolScalingAttributesRequestRequestTypeDef = TypedDict(
+    "PutDedicatedIpPoolScalingAttributesRequestRequestTypeDef",
+    {
+        "PoolName": str,
+        "ScalingMode": ScalingModeType,
+    },
+)
+
 PutDedicatedIpWarmupAttributesRequestRequestTypeDef = TypedDict(
     "PutDedicatedIpWarmupAttributesRequestRequestTypeDef",
     {
         "Ip": str,
         "WarmupPercentage": int,
     },
 )
@@ -1405,14 +1459,23 @@
 class PutEmailIdentityDkimAttributesRequestRequestTypeDef(
     _RequiredPutEmailIdentityDkimAttributesRequestRequestTypeDef,
     _OptionalPutEmailIdentityDkimAttributesRequestRequestTypeDef,
 ):
     pass
 
 
+PutEmailIdentityDkimSigningAttributesResponseTypeDef = TypedDict(
+    "PutEmailIdentityDkimSigningAttributesResponseTypeDef",
+    {
+        "DkimStatus": DkimStatusType,
+        "DkimTokens": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredPutEmailIdentityFeedbackAttributesRequestRequestTypeDef = TypedDict(
     "_RequiredPutEmailIdentityFeedbackAttributesRequestRequestTypeDef",
     {
         "EmailIdentity": str,
     },
 )
 _OptionalPutEmailIdentityFeedbackAttributesRequestRequestTypeDef = TypedDict(
@@ -1466,14 +1529,25 @@
     "ReplacementTemplateTypeDef",
     {
         "ReplacementTemplateData": str,
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
 _RequiredSendCustomVerificationEmailRequestRequestTypeDef = TypedDict(
     "_RequiredSendCustomVerificationEmailRequestRequestTypeDef",
     {
         "EmailAddress": str,
         "TemplateName": str,
     },
 )
@@ -1489,14 +1563,30 @@
 class SendCustomVerificationEmailRequestRequestTypeDef(
     _RequiredSendCustomVerificationEmailRequestRequestTypeDef,
     _OptionalSendCustomVerificationEmailRequestRequestTypeDef,
 ):
     pass
 
 
+SendCustomVerificationEmailResponseTypeDef = TypedDict(
+    "SendCustomVerificationEmailResponseTypeDef",
+    {
+        "MessageId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+SendEmailResponseTypeDef = TypedDict(
+    "SendEmailResponseTypeDef",
+    {
+        "MessageId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 SuppressedDestinationAttributesTypeDef = TypedDict(
     "SuppressedDestinationAttributesTypeDef",
     {
         "MessageId": str,
         "FeedbackId": str,
     },
     total=False,
@@ -1506,14 +1596,22 @@
     "TestRenderEmailTemplateRequestRequestTypeDef",
     {
         "TemplateName": str,
         "TemplateData": str,
     },
 )
 
+TestRenderEmailTemplateResponseTypeDef = TypedDict(
+    "TestRenderEmailTemplateResponseTypeDef",
+    {
+        "RenderedTemplate": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
@@ -1560,112 +1658,23 @@
 )
 
 BatchGetMetricDataResponseTypeDef = TypedDict(
     "BatchGetMetricDataResponseTypeDef",
     {
         "Results": List[MetricDataResultTypeDef],
         "Errors": List[MetricDataErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDeliverabilityTestReportResponseTypeDef = TypedDict(
-    "CreateDeliverabilityTestReportResponseTypeDef",
-    {
-        "ReportId": str,
-        "DeliverabilityTestStatus": DeliverabilityTestStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateImportJobResponseTypeDef = TypedDict(
-    "CreateImportJobResponseTypeDef",
-    {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetCustomVerificationEmailTemplateResponseTypeDef = TypedDict(
-    "GetCustomVerificationEmailTemplateResponseTypeDef",
-    {
-        "TemplateName": str,
-        "FromEmailAddress": str,
-        "TemplateSubject": str,
-        "TemplateContent": str,
-        "SuccessRedirectionURL": str,
-        "FailureRedirectionURL": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetEmailIdentityPoliciesResponseTypeDef = TypedDict(
-    "GetEmailIdentityPoliciesResponseTypeDef",
-    {
-        "Policies": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListConfigurationSetsResponseTypeDef = TypedDict(
-    "ListConfigurationSetsResponseTypeDef",
-    {
-        "ConfigurationSets": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDedicatedIpPoolsResponseTypeDef = TypedDict(
-    "ListDedicatedIpPoolsResponseTypeDef",
-    {
-        "DedicatedIpPools": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutEmailIdentityDkimSigningAttributesResponseTypeDef = TypedDict(
-    "PutEmailIdentityDkimSigningAttributesResponseTypeDef",
-    {
-        "DkimStatus": DkimStatusType,
-        "DkimTokens": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SendCustomVerificationEmailResponseTypeDef = TypedDict(
-    "SendCustomVerificationEmailResponseTypeDef",
-    {
-        "MessageId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SendEmailResponseTypeDef = TypedDict(
-    "SendEmailResponseTypeDef",
-    {
-        "MessageId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-TestRenderEmailTemplateResponseTypeDef = TypedDict(
-    "TestRenderEmailTemplateResponseTypeDef",
-    {
-        "RenderedTemplate": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetBlacklistReportsResponseTypeDef = TypedDict(
     "GetBlacklistReportsResponseTypeDef",
     {
         "BlacklistReport": Dict[str, List[BlacklistEntryTypeDef]],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BodyTypeDef = TypedDict(
     "BodyTypeDef",
     {
         "Text": ContentTypeDef,
@@ -1682,15 +1691,15 @@
     total=False,
 )
 
 SendBulkEmailResponseTypeDef = TypedDict(
     "SendBulkEmailResponseTypeDef",
     {
         "BulkEmailEntryResults": List[BulkEmailEntryResultTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CloudWatchDestinationTypeDef = TypedDict(
     "CloudWatchDestinationTypeDef",
     {
         "DimensionConfigurations": Sequence[CloudWatchDimensionConfigurationTypeDef],
@@ -1698,15 +1707,15 @@
 )
 
 ListContactListsResponseTypeDef = TypedDict(
     "ListContactListsResponseTypeDef",
     {
         "ContactLists": List[ContactListTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ContactTypeDef = TypedDict(
     "ContactTypeDef",
     {
         "EmailAddress": str,
@@ -1749,15 +1758,15 @@
         "EmailAddress": str,
         "TopicPreferences": List[TopicPreferenceTypeDef],
         "TopicDefaultPreferences": List[TopicPreferenceTypeDef],
         "UnsubscribeAll": bool,
         "AttributesData": str,
         "CreatedTimestamp": datetime,
         "LastUpdatedTimestamp": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateContactRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateContactRequestRequestTypeDef",
     {
         "ContactListName": str,
@@ -1804,15 +1813,15 @@
     pass
 
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
@@ -1848,15 +1857,15 @@
     {
         "ContactListName": str,
         "Topics": List[TopicTypeDef],
         "Description": str,
         "CreatedTimestamp": datetime,
         "LastUpdatedTimestamp": datetime,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateContactListRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateContactListRequestRequestTypeDef",
     {
         "ContactListName": str,
@@ -1927,15 +1936,15 @@
 
 CreateEmailIdentityResponseTypeDef = TypedDict(
     "CreateEmailIdentityResponseTypeDef",
     {
         "IdentityType": IdentityTypeType,
         "VerifiedForSendingStatus": bool,
         "DkimAttributes": DkimAttributesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateEmailTemplateRequestRequestTypeDef = TypedDict(
     "CreateEmailTemplateRequestRequestTypeDef",
     {
         "TemplateName": str,
@@ -1944,15 +1953,15 @@
 )
 
 GetEmailTemplateResponseTypeDef = TypedDict(
     "GetEmailTemplateResponseTypeDef",
     {
         "TemplateName": str,
         "TemplateContent": EmailTemplateContentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateEmailTemplateRequestRequestTypeDef = TypedDict(
     "UpdateEmailTemplateRequestRequestTypeDef",
     {
         "TemplateName": str,
@@ -1961,15 +1970,15 @@
 )
 
 ListCustomVerificationEmailTemplatesResponseTypeDef = TypedDict(
     "ListCustomVerificationEmailTemplatesResponseTypeDef",
     {
         "CustomVerificationEmailTemplates": List[CustomVerificationEmailTemplateMetadataTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DailyVolumeTypeDef = TypedDict(
     "DailyVolumeTypeDef",
     {
         "StartDate": datetime,
@@ -1989,58 +1998,58 @@
     total=False,
 )
 
 GetDedicatedIpPoolResponseTypeDef = TypedDict(
     "GetDedicatedIpPoolResponseTypeDef",
     {
         "DedicatedIpPool": DedicatedIpPoolTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDedicatedIpResponseTypeDef = TypedDict(
     "GetDedicatedIpResponseTypeDef",
     {
         "DedicatedIp": DedicatedIpTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDedicatedIpsResponseTypeDef = TypedDict(
     "GetDedicatedIpsResponseTypeDef",
     {
         "DedicatedIps": List[DedicatedIpTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDeliverabilityTestReportsResponseTypeDef = TypedDict(
     "ListDeliverabilityTestReportsResponseTypeDef",
     {
         "DeliverabilityTestReports": List[DeliverabilityTestReportTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDomainDeliverabilityCampaignResponseTypeDef = TypedDict(
     "GetDomainDeliverabilityCampaignResponseTypeDef",
     {
         "DomainDeliverabilityCampaign": DomainDeliverabilityCampaignTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDomainDeliverabilityCampaignsResponseTypeDef = TypedDict(
     "ListDomainDeliverabilityCampaignsResponseTypeDef",
     {
         "DomainDeliverabilityCampaigns": List[DomainDeliverabilityCampaignTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DomainDeliverabilityTrackingOptionTypeDef = TypedDict(
     "DomainDeliverabilityTrackingOptionTypeDef",
     {
         "Domain": str,
@@ -2051,15 +2060,15 @@
 )
 
 ListEmailTemplatesResponseTypeDef = TypedDict(
     "ListEmailTemplatesResponseTypeDef",
     {
         "TemplatesMetadata": List[EmailTemplateMetadataTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 IspPlacementTypeDef = TypedDict(
     "IspPlacementTypeDef",
     {
         "IspName": str,
@@ -2076,15 +2085,15 @@
         "VerifiedForSendingStatus": bool,
         "DkimAttributes": DkimAttributesTypeDef,
         "MailFromAttributes": MailFromAttributesTypeDef,
         "Policies": Dict[str, str],
         "Tags": List[TagTypeDef],
         "ConfigurationSetName": str,
         "VerificationStatus": VerificationStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredVdmAttributesTypeDef = TypedDict(
     "_RequiredVdmAttributesTypeDef",
     {
         "VdmEnabled": FeatureStatusType,
@@ -2114,15 +2123,15 @@
 )
 
 ListEmailIdentitiesResponseTypeDef = TypedDict(
     "ListEmailIdentitiesResponseTypeDef",
     {
         "EmailIdentities": List[IdentityInfoTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ImportDestinationTypeDef = TypedDict(
     "ImportDestinationTypeDef",
     {
         "SuppressionListDestination": SuppressionListDestinationTypeDef,
@@ -2141,24 +2150,24 @@
 )
 
 ListRecommendationsResponseTypeDef = TypedDict(
     "ListRecommendationsResponseTypeDef",
     {
         "Recommendations": List[RecommendationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSuppressedDestinationsResponseTypeDef = TypedDict(
     "ListSuppressedDestinationsResponseTypeDef",
     {
         "SuppressedDestinationSummaries": List[SuppressedDestinationSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReplacementEmailContentTypeDef = TypedDict(
     "ReplacementEmailContentTypeDef",
     {
         "ReplacementTemplate": ReplacementTemplateTypeDef,
@@ -2235,36 +2244,36 @@
 
 
 ListContactsResponseTypeDef = TypedDict(
     "ListContactsResponseTypeDef",
     {
         "Contacts": List[ContactTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDomainStatisticsReportResponseTypeDef = TypedDict(
     "GetDomainStatisticsReportResponseTypeDef",
     {
         "OverallVolume": OverallVolumeTypeDef,
         "DailyVolumes": List[DailyVolumeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDeliverabilityDashboardOptionsResponseTypeDef = TypedDict(
     "GetDeliverabilityDashboardOptionsResponseTypeDef",
     {
         "DashboardEnabled": bool,
         "SubscriptionExpiryDate": datetime,
         "AccountStatus": DeliverabilityDashboardAccountStatusType,
         "ActiveSubscribedDomains": List[DomainDeliverabilityTrackingOptionTypeDef],
         "PendingExpirationSubscribedDomains": List[DomainDeliverabilityTrackingOptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutDeliverabilityDashboardOptionRequestRequestTypeDef = TypedDict(
     "_RequiredPutDeliverabilityDashboardOptionRequestRequestTypeDef",
     {
         "DashboardEnabled": bool,
@@ -2290,30 +2299,30 @@
     "GetDeliverabilityTestReportResponseTypeDef",
     {
         "DeliverabilityTestReport": DeliverabilityTestReportTypeDef,
         "OverallPlacement": PlacementStatisticsTypeDef,
         "IspPlacements": List[IspPlacementTypeDef],
         "Message": str,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAccountResponseTypeDef = TypedDict(
     "GetAccountResponseTypeDef",
     {
         "DedicatedIpAutoWarmupEnabled": bool,
         "EnforcementStatus": str,
         "ProductionAccessEnabled": bool,
         "SendQuota": SendQuotaTypeDef,
         "SendingEnabled": bool,
         "SuppressionAttributes": SuppressionAttributesTypeDef,
         "Details": AccountDetailsTypeDef,
         "VdmAttributes": VdmAttributesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutAccountVdmAttributesRequestRequestTypeDef = TypedDict(
     "PutAccountVdmAttributesRequestRequestTypeDef",
     {
         "VdmAttributes": VdmAttributesTypeDef,
@@ -2355,15 +2364,15 @@
         "TrackingOptions": TrackingOptionsTypeDef,
         "DeliveryOptions": DeliveryOptionsTypeDef,
         "ReputationOptions": ReputationOptionsTypeDef,
         "SendingOptions": SendingOptionsTypeDef,
         "Tags": List[TagTypeDef],
         "SuppressionOptions": SuppressionOptionsTypeDef,
         "VdmOptions": VdmOptionsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutConfigurationSetVdmOptionsRequestRequestTypeDef = TypedDict(
     "_RequiredPutConfigurationSetVdmOptionsRequestRequestTypeDef",
     {
         "ConfigurationSetName": str,
@@ -2401,15 +2410,15 @@
         "ImportDataSource": ImportDataSourceTypeDef,
         "FailureInfo": FailureInfoTypeDef,
         "JobStatus": JobStatusType,
         "CreatedTimestamp": datetime,
         "CompletedTimestamp": datetime,
         "ProcessedRecordsCount": int,
         "FailedRecordsCount": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ImportJobSummaryTypeDef = TypedDict(
     "ImportJobSummaryTypeDef",
     {
         "JobId": str,
@@ -2465,15 +2474,15 @@
     pass
 
 
 GetSuppressedDestinationResponseTypeDef = TypedDict(
     "GetSuppressedDestinationResponseTypeDef",
     {
         "SuppressedDestination": SuppressedDestinationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EmailContentTypeDef = TypedDict(
     "EmailContentTypeDef",
     {
         "Simple": MessageTypeDef,
@@ -2501,24 +2510,24 @@
     },
 )
 
 GetConfigurationSetEventDestinationsResponseTypeDef = TypedDict(
     "GetConfigurationSetEventDestinationsResponseTypeDef",
     {
         "EventDestinations": List[EventDestinationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListImportJobsResponseTypeDef = TypedDict(
     "ListImportJobsResponseTypeDef",
     {
         "ImportJobs": List[ImportJobSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSendBulkEmailRequestRequestTypeDef = TypedDict(
     "_RequiredSendBulkEmailRequestRequestTypeDef",
     {
         "DefaultContent": BulkEmailContentTypeDef,
```

### Comparing `types-aiobotocore-sesv2-2.5.0.post1/types_aiobotocore_sesv2/type_defs.pyi` & `types-aiobotocore-sesv2-2.5.1/types_aiobotocore_sesv2/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -63,15 +63,14 @@
     from typing_extensions import TypedDict
 
 __all__ = (
     "ReviewDetailsTypeDef",
     "BatchGetMetricDataQueryTypeDef",
     "MetricDataErrorTypeDef",
     "MetricDataResultTypeDef",
-    "ResponseMetadataTypeDef",
     "BlacklistEntryTypeDef",
     "ContentTypeDef",
     "TemplateTypeDef",
     "BulkEmailEntryResultTypeDef",
     "DestinationTypeDef",
     "MessageTagTypeDef",
     "CloudWatchDimensionConfigurationTypeDef",
@@ -82,19 +81,21 @@
     "ReputationOptionsTypeDef",
     "SendingOptionsTypeDef",
     "SuppressionOptionsTypeDef",
     "TagTypeDef",
     "TrackingOptionsTypeDef",
     "TopicTypeDef",
     "CreateCustomVerificationEmailTemplateRequestRequestTypeDef",
+    "CreateDeliverabilityTestReportResponseTypeDef",
     "CreateEmailIdentityPolicyRequestRequestTypeDef",
     "DkimSigningAttributesTypeDef",
     "DkimAttributesTypeDef",
     "EmailTemplateContentTypeDef",
     "ImportDataSourceTypeDef",
+    "CreateImportJobResponseTypeDef",
     "CustomVerificationEmailTemplateMetadataTypeDef",
     "DomainIspPlacementTypeDef",
     "VolumeStatisticsTypeDef",
     "DashboardAttributesTypeDef",
     "DashboardOptionsTypeDef",
     "DedicatedIpPoolTypeDef",
     "DedicatedIpTypeDef",
@@ -121,36 +122,40 @@
     "SuppressionAttributesTypeDef",
     "GetBlacklistReportsRequestRequestTypeDef",
     "GetConfigurationSetEventDestinationsRequestRequestTypeDef",
     "GetConfigurationSetRequestRequestTypeDef",
     "GetContactListRequestRequestTypeDef",
     "GetContactRequestRequestTypeDef",
     "GetCustomVerificationEmailTemplateRequestRequestTypeDef",
+    "GetCustomVerificationEmailTemplateResponseTypeDef",
     "GetDedicatedIpPoolRequestRequestTypeDef",
     "GetDedicatedIpRequestRequestTypeDef",
     "GetDedicatedIpsRequestRequestTypeDef",
     "GetDeliverabilityTestReportRequestRequestTypeDef",
     "PlacementStatisticsTypeDef",
     "GetDomainDeliverabilityCampaignRequestRequestTypeDef",
     "GetDomainStatisticsReportRequestRequestTypeDef",
     "GetEmailIdentityPoliciesRequestRequestTypeDef",
+    "GetEmailIdentityPoliciesResponseTypeDef",
     "GetEmailIdentityRequestRequestTypeDef",
     "MailFromAttributesTypeDef",
     "GetEmailTemplateRequestRequestTypeDef",
     "GetImportJobRequestRequestTypeDef",
     "GetSuppressedDestinationRequestRequestTypeDef",
     "GuardianAttributesTypeDef",
     "GuardianOptionsTypeDef",
     "IdentityInfoTypeDef",
     "SuppressionListDestinationTypeDef",
     "ListConfigurationSetsRequestRequestTypeDef",
+    "ListConfigurationSetsResponseTypeDef",
     "ListContactListsRequestRequestTypeDef",
     "TopicFilterTypeDef",
     "ListCustomVerificationEmailTemplatesRequestRequestTypeDef",
     "ListDedicatedIpPoolsRequestRequestTypeDef",
+    "ListDedicatedIpPoolsResponseTypeDef",
     "ListDeliverabilityTestReportsRequestRequestTypeDef",
     "ListDomainDeliverabilityCampaignsRequestRequestTypeDef",
     "ListEmailIdentitiesRequestRequestTypeDef",
     "ListEmailTemplatesRequestRequestTypeDef",
     "ListImportJobsRequestRequestTypeDef",
     "ListManagementOptionsTypeDef",
     "ListRecommendationsRequestRequestTypeDef",
@@ -164,40 +169,36 @@
     "PutAccountSuppressionAttributesRequestRequestTypeDef",
     "PutConfigurationSetDeliveryOptionsRequestRequestTypeDef",
     "PutConfigurationSetReputationOptionsRequestRequestTypeDef",
     "PutConfigurationSetSendingOptionsRequestRequestTypeDef",
     "PutConfigurationSetSuppressionOptionsRequestRequestTypeDef",
     "PutConfigurationSetTrackingOptionsRequestRequestTypeDef",
     "PutDedicatedIpInPoolRequestRequestTypeDef",
+    "PutDedicatedIpPoolScalingAttributesRequestRequestTypeDef",
     "PutDedicatedIpWarmupAttributesRequestRequestTypeDef",
     "PutEmailIdentityConfigurationSetAttributesRequestRequestTypeDef",
     "PutEmailIdentityDkimAttributesRequestRequestTypeDef",
+    "PutEmailIdentityDkimSigningAttributesResponseTypeDef",
     "PutEmailIdentityFeedbackAttributesRequestRequestTypeDef",
     "PutEmailIdentityMailFromAttributesRequestRequestTypeDef",
     "PutSuppressedDestinationRequestRequestTypeDef",
     "ReplacementTemplateTypeDef",
+    "ResponseMetadataTypeDef",
     "SendCustomVerificationEmailRequestRequestTypeDef",
+    "SendCustomVerificationEmailResponseTypeDef",
+    "SendEmailResponseTypeDef",
     "SuppressedDestinationAttributesTypeDef",
     "TestRenderEmailTemplateRequestRequestTypeDef",
+    "TestRenderEmailTemplateResponseTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateCustomVerificationEmailTemplateRequestRequestTypeDef",
     "UpdateEmailIdentityPolicyRequestRequestTypeDef",
     "AccountDetailsTypeDef",
     "BatchGetMetricDataRequestRequestTypeDef",
     "BatchGetMetricDataResponseTypeDef",
-    "CreateDeliverabilityTestReportResponseTypeDef",
-    "CreateImportJobResponseTypeDef",
-    "GetCustomVerificationEmailTemplateResponseTypeDef",
-    "GetEmailIdentityPoliciesResponseTypeDef",
-    "ListConfigurationSetsResponseTypeDef",
-    "ListDedicatedIpPoolsResponseTypeDef",
-    "PutEmailIdentityDkimSigningAttributesResponseTypeDef",
-    "SendCustomVerificationEmailResponseTypeDef",
-    "SendEmailResponseTypeDef",
-    "TestRenderEmailTemplateResponseTypeDef",
     "GetBlacklistReportsResponseTypeDef",
     "BodyTypeDef",
     "BulkEmailContentTypeDef",
     "SendBulkEmailResponseTypeDef",
     "CloudWatchDestinationTypeDef",
     "ListContactListsResponseTypeDef",
     "ContactTypeDef",
@@ -315,25 +316,14 @@
         "Id": str,
         "Timestamps": List[datetime],
         "Values": List[int],
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
 BlacklistEntryTypeDef = TypedDict(
     "BlacklistEntryTypeDef",
     {
         "RblName": str,
         "ListingTime": datetime,
         "Description": str,
     },
@@ -505,14 +495,23 @@
         "TemplateSubject": str,
         "TemplateContent": str,
         "SuccessRedirectionURL": str,
         "FailureRedirectionURL": str,
     },
 )
 
+CreateDeliverabilityTestReportResponseTypeDef = TypedDict(
+    "CreateDeliverabilityTestReportResponseTypeDef",
+    {
+        "ReportId": str,
+        "DeliverabilityTestStatus": DeliverabilityTestStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateEmailIdentityPolicyRequestRequestTypeDef = TypedDict(
     "CreateEmailIdentityPolicyRequestRequestTypeDef",
     {
         "EmailIdentity": str,
         "PolicyName": str,
         "Policy": str,
     },
@@ -556,14 +555,22 @@
     "ImportDataSourceTypeDef",
     {
         "S3Url": str,
         "DataFormat": DataFormatType,
     },
 )
 
+CreateImportJobResponseTypeDef = TypedDict(
+    "CreateImportJobResponseTypeDef",
+    {
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CustomVerificationEmailTemplateMetadataTypeDef = TypedDict(
     "CustomVerificationEmailTemplateMetadataTypeDef",
     {
         "TemplateName": str,
         "FromEmailAddress": str,
         "TemplateSubject": str,
         "SuccessRedirectionURL": str,
@@ -859,14 +866,27 @@
 GetCustomVerificationEmailTemplateRequestRequestTypeDef = TypedDict(
     "GetCustomVerificationEmailTemplateRequestRequestTypeDef",
     {
         "TemplateName": str,
     },
 )
 
+GetCustomVerificationEmailTemplateResponseTypeDef = TypedDict(
+    "GetCustomVerificationEmailTemplateResponseTypeDef",
+    {
+        "TemplateName": str,
+        "FromEmailAddress": str,
+        "TemplateSubject": str,
+        "TemplateContent": str,
+        "SuccessRedirectionURL": str,
+        "FailureRedirectionURL": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetDedicatedIpPoolRequestRequestTypeDef = TypedDict(
     "GetDedicatedIpPoolRequestRequestTypeDef",
     {
         "PoolName": str,
     },
 )
 
@@ -925,14 +945,22 @@
 GetEmailIdentityPoliciesRequestRequestTypeDef = TypedDict(
     "GetEmailIdentityPoliciesRequestRequestTypeDef",
     {
         "EmailIdentity": str,
     },
 )
 
+GetEmailIdentityPoliciesResponseTypeDef = TypedDict(
+    "GetEmailIdentityPoliciesResponseTypeDef",
+    {
+        "Policies": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetEmailIdentityRequestRequestTypeDef = TypedDict(
     "GetEmailIdentityRequestRequestTypeDef",
     {
         "EmailIdentity": str,
     },
 )
 
@@ -1005,14 +1033,23 @@
     {
         "NextToken": str,
         "PageSize": int,
     },
     total=False,
 )
 
+ListConfigurationSetsResponseTypeDef = TypedDict(
+    "ListConfigurationSetsResponseTypeDef",
+    {
+        "ConfigurationSets": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListContactListsRequestRequestTypeDef = TypedDict(
     "ListContactListsRequestRequestTypeDef",
     {
         "PageSize": int,
         "NextToken": str,
     },
     total=False,
@@ -1041,14 +1078,23 @@
     {
         "NextToken": str,
         "PageSize": int,
     },
     total=False,
 )
 
+ListDedicatedIpPoolsResponseTypeDef = TypedDict(
+    "ListDedicatedIpPoolsResponseTypeDef",
+    {
+        "DedicatedIpPools": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListDeliverabilityTestReportsRequestRequestTypeDef = TypedDict(
     "ListDeliverabilityTestReportsRequestRequestTypeDef",
     {
         "NextToken": str,
         "PageSize": int,
     },
     total=False,
@@ -1328,14 +1374,22 @@
     "PutDedicatedIpInPoolRequestRequestTypeDef",
     {
         "Ip": str,
         "DestinationPoolName": str,
     },
 )
 
+PutDedicatedIpPoolScalingAttributesRequestRequestTypeDef = TypedDict(
+    "PutDedicatedIpPoolScalingAttributesRequestRequestTypeDef",
+    {
+        "PoolName": str,
+        "ScalingMode": ScalingModeType,
+    },
+)
+
 PutDedicatedIpWarmupAttributesRequestRequestTypeDef = TypedDict(
     "PutDedicatedIpWarmupAttributesRequestRequestTypeDef",
     {
         "Ip": str,
         "WarmupPercentage": int,
     },
 )
@@ -1376,14 +1430,23 @@
 
 class PutEmailIdentityDkimAttributesRequestRequestTypeDef(
     _RequiredPutEmailIdentityDkimAttributesRequestRequestTypeDef,
     _OptionalPutEmailIdentityDkimAttributesRequestRequestTypeDef,
 ):
     pass
 
+PutEmailIdentityDkimSigningAttributesResponseTypeDef = TypedDict(
+    "PutEmailIdentityDkimSigningAttributesResponseTypeDef",
+    {
+        "DkimStatus": DkimStatusType,
+        "DkimTokens": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredPutEmailIdentityFeedbackAttributesRequestRequestTypeDef = TypedDict(
     "_RequiredPutEmailIdentityFeedbackAttributesRequestRequestTypeDef",
     {
         "EmailIdentity": str,
     },
 )
 _OptionalPutEmailIdentityFeedbackAttributesRequestRequestTypeDef = TypedDict(
@@ -1433,14 +1496,25 @@
     "ReplacementTemplateTypeDef",
     {
         "ReplacementTemplateData": str,
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
 _RequiredSendCustomVerificationEmailRequestRequestTypeDef = TypedDict(
     "_RequiredSendCustomVerificationEmailRequestRequestTypeDef",
     {
         "EmailAddress": str,
         "TemplateName": str,
     },
 )
@@ -1454,14 +1528,30 @@
 
 class SendCustomVerificationEmailRequestRequestTypeDef(
     _RequiredSendCustomVerificationEmailRequestRequestTypeDef,
     _OptionalSendCustomVerificationEmailRequestRequestTypeDef,
 ):
     pass
 
+SendCustomVerificationEmailResponseTypeDef = TypedDict(
+    "SendCustomVerificationEmailResponseTypeDef",
+    {
+        "MessageId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+SendEmailResponseTypeDef = TypedDict(
+    "SendEmailResponseTypeDef",
+    {
+        "MessageId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 SuppressedDestinationAttributesTypeDef = TypedDict(
     "SuppressedDestinationAttributesTypeDef",
     {
         "MessageId": str,
         "FeedbackId": str,
     },
     total=False,
@@ -1471,14 +1561,22 @@
     "TestRenderEmailTemplateRequestRequestTypeDef",
     {
         "TemplateName": str,
         "TemplateData": str,
     },
 )
 
+TestRenderEmailTemplateResponseTypeDef = TypedDict(
+    "TestRenderEmailTemplateResponseTypeDef",
+    {
+        "RenderedTemplate": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
@@ -1525,112 +1623,23 @@
 )
 
 BatchGetMetricDataResponseTypeDef = TypedDict(
     "BatchGetMetricDataResponseTypeDef",
     {
         "Results": List[MetricDataResultTypeDef],
         "Errors": List[MetricDataErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDeliverabilityTestReportResponseTypeDef = TypedDict(
-    "CreateDeliverabilityTestReportResponseTypeDef",
-    {
-        "ReportId": str,
-        "DeliverabilityTestStatus": DeliverabilityTestStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateImportJobResponseTypeDef = TypedDict(
-    "CreateImportJobResponseTypeDef",
-    {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetCustomVerificationEmailTemplateResponseTypeDef = TypedDict(
-    "GetCustomVerificationEmailTemplateResponseTypeDef",
-    {
-        "TemplateName": str,
-        "FromEmailAddress": str,
-        "TemplateSubject": str,
-        "TemplateContent": str,
-        "SuccessRedirectionURL": str,
-        "FailureRedirectionURL": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetEmailIdentityPoliciesResponseTypeDef = TypedDict(
-    "GetEmailIdentityPoliciesResponseTypeDef",
-    {
-        "Policies": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListConfigurationSetsResponseTypeDef = TypedDict(
-    "ListConfigurationSetsResponseTypeDef",
-    {
-        "ConfigurationSets": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDedicatedIpPoolsResponseTypeDef = TypedDict(
-    "ListDedicatedIpPoolsResponseTypeDef",
-    {
-        "DedicatedIpPools": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutEmailIdentityDkimSigningAttributesResponseTypeDef = TypedDict(
-    "PutEmailIdentityDkimSigningAttributesResponseTypeDef",
-    {
-        "DkimStatus": DkimStatusType,
-        "DkimTokens": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SendCustomVerificationEmailResponseTypeDef = TypedDict(
-    "SendCustomVerificationEmailResponseTypeDef",
-    {
-        "MessageId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SendEmailResponseTypeDef = TypedDict(
-    "SendEmailResponseTypeDef",
-    {
-        "MessageId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-TestRenderEmailTemplateResponseTypeDef = TypedDict(
-    "TestRenderEmailTemplateResponseTypeDef",
-    {
-        "RenderedTemplate": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetBlacklistReportsResponseTypeDef = TypedDict(
     "GetBlacklistReportsResponseTypeDef",
     {
         "BlacklistReport": Dict[str, List[BlacklistEntryTypeDef]],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BodyTypeDef = TypedDict(
     "BodyTypeDef",
     {
         "Text": ContentTypeDef,
@@ -1647,15 +1656,15 @@
     total=False,
 )
 
 SendBulkEmailResponseTypeDef = TypedDict(
     "SendBulkEmailResponseTypeDef",
     {
         "BulkEmailEntryResults": List[BulkEmailEntryResultTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CloudWatchDestinationTypeDef = TypedDict(
     "CloudWatchDestinationTypeDef",
     {
         "DimensionConfigurations": Sequence[CloudWatchDimensionConfigurationTypeDef],
@@ -1663,15 +1672,15 @@
 )
 
 ListContactListsResponseTypeDef = TypedDict(
     "ListContactListsResponseTypeDef",
     {
         "ContactLists": List[ContactListTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ContactTypeDef = TypedDict(
     "ContactTypeDef",
     {
         "EmailAddress": str,
@@ -1712,15 +1721,15 @@
         "EmailAddress": str,
         "TopicPreferences": List[TopicPreferenceTypeDef],
         "TopicDefaultPreferences": List[TopicPreferenceTypeDef],
         "UnsubscribeAll": bool,
         "AttributesData": str,
         "CreatedTimestamp": datetime,
         "LastUpdatedTimestamp": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateContactRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateContactRequestRequestTypeDef",
     {
         "ContactListName": str,
@@ -1763,15 +1772,15 @@
 ):
     pass
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
@@ -1805,15 +1814,15 @@
     {
         "ContactListName": str,
         "Topics": List[TopicTypeDef],
         "Description": str,
         "CreatedTimestamp": datetime,
         "LastUpdatedTimestamp": datetime,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateContactListRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateContactListRequestRequestTypeDef",
     {
         "ContactListName": str,
@@ -1878,15 +1887,15 @@
 
 CreateEmailIdentityResponseTypeDef = TypedDict(
     "CreateEmailIdentityResponseTypeDef",
     {
         "IdentityType": IdentityTypeType,
         "VerifiedForSendingStatus": bool,
         "DkimAttributes": DkimAttributesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateEmailTemplateRequestRequestTypeDef = TypedDict(
     "CreateEmailTemplateRequestRequestTypeDef",
     {
         "TemplateName": str,
@@ -1895,15 +1904,15 @@
 )
 
 GetEmailTemplateResponseTypeDef = TypedDict(
     "GetEmailTemplateResponseTypeDef",
     {
         "TemplateName": str,
         "TemplateContent": EmailTemplateContentTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateEmailTemplateRequestRequestTypeDef = TypedDict(
     "UpdateEmailTemplateRequestRequestTypeDef",
     {
         "TemplateName": str,
@@ -1912,15 +1921,15 @@
 )
 
 ListCustomVerificationEmailTemplatesResponseTypeDef = TypedDict(
     "ListCustomVerificationEmailTemplatesResponseTypeDef",
     {
         "CustomVerificationEmailTemplates": List[CustomVerificationEmailTemplateMetadataTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DailyVolumeTypeDef = TypedDict(
     "DailyVolumeTypeDef",
     {
         "StartDate": datetime,
@@ -1940,58 +1949,58 @@
     total=False,
 )
 
 GetDedicatedIpPoolResponseTypeDef = TypedDict(
     "GetDedicatedIpPoolResponseTypeDef",
     {
         "DedicatedIpPool": DedicatedIpPoolTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDedicatedIpResponseTypeDef = TypedDict(
     "GetDedicatedIpResponseTypeDef",
     {
         "DedicatedIp": DedicatedIpTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDedicatedIpsResponseTypeDef = TypedDict(
     "GetDedicatedIpsResponseTypeDef",
     {
         "DedicatedIps": List[DedicatedIpTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDeliverabilityTestReportsResponseTypeDef = TypedDict(
     "ListDeliverabilityTestReportsResponseTypeDef",
     {
         "DeliverabilityTestReports": List[DeliverabilityTestReportTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDomainDeliverabilityCampaignResponseTypeDef = TypedDict(
     "GetDomainDeliverabilityCampaignResponseTypeDef",
     {
         "DomainDeliverabilityCampaign": DomainDeliverabilityCampaignTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDomainDeliverabilityCampaignsResponseTypeDef = TypedDict(
     "ListDomainDeliverabilityCampaignsResponseTypeDef",
     {
         "DomainDeliverabilityCampaigns": List[DomainDeliverabilityCampaignTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DomainDeliverabilityTrackingOptionTypeDef = TypedDict(
     "DomainDeliverabilityTrackingOptionTypeDef",
     {
         "Domain": str,
@@ -2002,15 +2011,15 @@
 )
 
 ListEmailTemplatesResponseTypeDef = TypedDict(
     "ListEmailTemplatesResponseTypeDef",
     {
         "TemplatesMetadata": List[EmailTemplateMetadataTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 IspPlacementTypeDef = TypedDict(
     "IspPlacementTypeDef",
     {
         "IspName": str,
@@ -2027,15 +2036,15 @@
         "VerifiedForSendingStatus": bool,
         "DkimAttributes": DkimAttributesTypeDef,
         "MailFromAttributes": MailFromAttributesTypeDef,
         "Policies": Dict[str, str],
         "Tags": List[TagTypeDef],
         "ConfigurationSetName": str,
         "VerificationStatus": VerificationStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredVdmAttributesTypeDef = TypedDict(
     "_RequiredVdmAttributesTypeDef",
     {
         "VdmEnabled": FeatureStatusType,
@@ -2063,15 +2072,15 @@
 )
 
 ListEmailIdentitiesResponseTypeDef = TypedDict(
     "ListEmailIdentitiesResponseTypeDef",
     {
         "EmailIdentities": List[IdentityInfoTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ImportDestinationTypeDef = TypedDict(
     "ImportDestinationTypeDef",
     {
         "SuppressionListDestination": SuppressionListDestinationTypeDef,
@@ -2090,24 +2099,24 @@
 )
 
 ListRecommendationsResponseTypeDef = TypedDict(
     "ListRecommendationsResponseTypeDef",
     {
         "Recommendations": List[RecommendationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSuppressedDestinationsResponseTypeDef = TypedDict(
     "ListSuppressedDestinationsResponseTypeDef",
     {
         "SuppressedDestinationSummaries": List[SuppressedDestinationSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReplacementEmailContentTypeDef = TypedDict(
     "ReplacementEmailContentTypeDef",
     {
         "ReplacementTemplate": ReplacementTemplateTypeDef,
@@ -2180,36 +2189,36 @@
     pass
 
 ListContactsResponseTypeDef = TypedDict(
     "ListContactsResponseTypeDef",
     {
         "Contacts": List[ContactTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDomainStatisticsReportResponseTypeDef = TypedDict(
     "GetDomainStatisticsReportResponseTypeDef",
     {
         "OverallVolume": OverallVolumeTypeDef,
         "DailyVolumes": List[DailyVolumeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDeliverabilityDashboardOptionsResponseTypeDef = TypedDict(
     "GetDeliverabilityDashboardOptionsResponseTypeDef",
     {
         "DashboardEnabled": bool,
         "SubscriptionExpiryDate": datetime,
         "AccountStatus": DeliverabilityDashboardAccountStatusType,
         "ActiveSubscribedDomains": List[DomainDeliverabilityTrackingOptionTypeDef],
         "PendingExpirationSubscribedDomains": List[DomainDeliverabilityTrackingOptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutDeliverabilityDashboardOptionRequestRequestTypeDef = TypedDict(
     "_RequiredPutDeliverabilityDashboardOptionRequestRequestTypeDef",
     {
         "DashboardEnabled": bool,
@@ -2233,30 +2242,30 @@
     "GetDeliverabilityTestReportResponseTypeDef",
     {
         "DeliverabilityTestReport": DeliverabilityTestReportTypeDef,
         "OverallPlacement": PlacementStatisticsTypeDef,
         "IspPlacements": List[IspPlacementTypeDef],
         "Message": str,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAccountResponseTypeDef = TypedDict(
     "GetAccountResponseTypeDef",
     {
         "DedicatedIpAutoWarmupEnabled": bool,
         "EnforcementStatus": str,
         "ProductionAccessEnabled": bool,
         "SendQuota": SendQuotaTypeDef,
         "SendingEnabled": bool,
         "SuppressionAttributes": SuppressionAttributesTypeDef,
         "Details": AccountDetailsTypeDef,
         "VdmAttributes": VdmAttributesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutAccountVdmAttributesRequestRequestTypeDef = TypedDict(
     "PutAccountVdmAttributesRequestRequestTypeDef",
     {
         "VdmAttributes": VdmAttributesTypeDef,
@@ -2296,15 +2305,15 @@
         "TrackingOptions": TrackingOptionsTypeDef,
         "DeliveryOptions": DeliveryOptionsTypeDef,
         "ReputationOptions": ReputationOptionsTypeDef,
         "SendingOptions": SendingOptionsTypeDef,
         "Tags": List[TagTypeDef],
         "SuppressionOptions": SuppressionOptionsTypeDef,
         "VdmOptions": VdmOptionsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutConfigurationSetVdmOptionsRequestRequestTypeDef = TypedDict(
     "_RequiredPutConfigurationSetVdmOptionsRequestRequestTypeDef",
     {
         "ConfigurationSetName": str,
@@ -2340,15 +2349,15 @@
         "ImportDataSource": ImportDataSourceTypeDef,
         "FailureInfo": FailureInfoTypeDef,
         "JobStatus": JobStatusType,
         "CreatedTimestamp": datetime,
         "CompletedTimestamp": datetime,
         "ProcessedRecordsCount": int,
         "FailedRecordsCount": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ImportJobSummaryTypeDef = TypedDict(
     "ImportJobSummaryTypeDef",
     {
         "JobId": str,
@@ -2400,15 +2409,15 @@
 class BulkEmailEntryTypeDef(_RequiredBulkEmailEntryTypeDef, _OptionalBulkEmailEntryTypeDef):
     pass
 
 GetSuppressedDestinationResponseTypeDef = TypedDict(
     "GetSuppressedDestinationResponseTypeDef",
     {
         "SuppressedDestination": SuppressedDestinationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EmailContentTypeDef = TypedDict(
     "EmailContentTypeDef",
     {
         "Simple": MessageTypeDef,
@@ -2436,24 +2445,24 @@
     },
 )
 
 GetConfigurationSetEventDestinationsResponseTypeDef = TypedDict(
     "GetConfigurationSetEventDestinationsResponseTypeDef",
     {
         "EventDestinations": List[EventDestinationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListImportJobsResponseTypeDef = TypedDict(
     "ListImportJobsResponseTypeDef",
     {
         "ImportJobs": List[ImportJobSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSendBulkEmailRequestRequestTypeDef = TypedDict(
     "_RequiredSendBulkEmailRequestRequestTypeDef",
     {
         "DefaultContent": BulkEmailContentTypeDef,
```

### Comparing `types-aiobotocore-sesv2-2.5.0.post1/types_aiobotocore_sesv2.egg-info/PKG-INFO` & `types-aiobotocore-sesv2-2.5.1/types_aiobotocore_sesv2.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-sesv2
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SESV2 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SESV2 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sesv2/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-sesv2"></a>
 
 # types-aiobotocore-sesv2
 
 [![PyPI - types-aiobotocore-sesv2](https://img.shields.io/pypi/v/types-aiobotocore-sesv2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sesv2)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-sesv2.svg?color=blue)](https://pypi.org/project/types-aiobotocore-sesv2)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sesv2/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-sesv2?color=blue)](https://pypistats.org/packages/types-aiobotocore-sesv2)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SESV2 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sesv2.html#SESV2)
+[aiobotocore.SESV2 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sesv2.html#SESV2)
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
 [types-aiobotocore-sesv2 docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_sesv2/).
 
 See how it helps to find and fix potential bugs:
 
@@ -325,15 +325,14 @@
 
 ```python
 from types_aiobotocore_sesv2.type_defs import (
     ReviewDetailsTypeDef,
     BatchGetMetricDataQueryTypeDef,
     MetricDataErrorTypeDef,
     MetricDataResultTypeDef,
-    ResponseMetadataTypeDef,
     BlacklistEntryTypeDef,
     ContentTypeDef,
     TemplateTypeDef,
     BulkEmailEntryResultTypeDef,
     DestinationTypeDef,
     MessageTagTypeDef,
     CloudWatchDimensionConfigurationTypeDef,
@@ -344,19 +343,21 @@
     ReputationOptionsTypeDef,
     SendingOptionsTypeDef,
     SuppressionOptionsTypeDef,
     TagTypeDef,
     TrackingOptionsTypeDef,
     TopicTypeDef,
     CreateCustomVerificationEmailTemplateRequestRequestTypeDef,
+    CreateDeliverabilityTestReportResponseTypeDef,
     CreateEmailIdentityPolicyRequestRequestTypeDef,
     DkimSigningAttributesTypeDef,
     DkimAttributesTypeDef,
     EmailTemplateContentTypeDef,
     ImportDataSourceTypeDef,
+    CreateImportJobResponseTypeDef,
     CustomVerificationEmailTemplateMetadataTypeDef,
     DomainIspPlacementTypeDef,
     VolumeStatisticsTypeDef,
     DashboardAttributesTypeDef,
     DashboardOptionsTypeDef,
     DedicatedIpPoolTypeDef,
     DedicatedIpTypeDef,
@@ -383,36 +384,40 @@
     SuppressionAttributesTypeDef,
     GetBlacklistReportsRequestRequestTypeDef,
     GetConfigurationSetEventDestinationsRequestRequestTypeDef,
     GetConfigurationSetRequestRequestTypeDef,
     GetContactListRequestRequestTypeDef,
     GetContactRequestRequestTypeDef,
     GetCustomVerificationEmailTemplateRequestRequestTypeDef,
+    GetCustomVerificationEmailTemplateResponseTypeDef,
     GetDedicatedIpPoolRequestRequestTypeDef,
     GetDedicatedIpRequestRequestTypeDef,
     GetDedicatedIpsRequestRequestTypeDef,
     GetDeliverabilityTestReportRequestRequestTypeDef,
     PlacementStatisticsTypeDef,
     GetDomainDeliverabilityCampaignRequestRequestTypeDef,
     GetDomainStatisticsReportRequestRequestTypeDef,
     GetEmailIdentityPoliciesRequestRequestTypeDef,
+    GetEmailIdentityPoliciesResponseTypeDef,
     GetEmailIdentityRequestRequestTypeDef,
     MailFromAttributesTypeDef,
     GetEmailTemplateRequestRequestTypeDef,
     GetImportJobRequestRequestTypeDef,
     GetSuppressedDestinationRequestRequestTypeDef,
     GuardianAttributesTypeDef,
     GuardianOptionsTypeDef,
     IdentityInfoTypeDef,
     SuppressionListDestinationTypeDef,
     ListConfigurationSetsRequestRequestTypeDef,
+    ListConfigurationSetsResponseTypeDef,
     ListContactListsRequestRequestTypeDef,
     TopicFilterTypeDef,
     ListCustomVerificationEmailTemplatesRequestRequestTypeDef,
     ListDedicatedIpPoolsRequestRequestTypeDef,
+    ListDedicatedIpPoolsResponseTypeDef,
     ListDeliverabilityTestReportsRequestRequestTypeDef,
     ListDomainDeliverabilityCampaignsRequestRequestTypeDef,
     ListEmailIdentitiesRequestRequestTypeDef,
     ListEmailTemplatesRequestRequestTypeDef,
     ListImportJobsRequestRequestTypeDef,
     ListManagementOptionsTypeDef,
     ListRecommendationsRequestRequestTypeDef,
@@ -426,40 +431,36 @@
     PutAccountSuppressionAttributesRequestRequestTypeDef,
     PutConfigurationSetDeliveryOptionsRequestRequestTypeDef,
     PutConfigurationSetReputationOptionsRequestRequestTypeDef,
     PutConfigurationSetSendingOptionsRequestRequestTypeDef,
     PutConfigurationSetSuppressionOptionsRequestRequestTypeDef,
     PutConfigurationSetTrackingOptionsRequestRequestTypeDef,
     PutDedicatedIpInPoolRequestRequestTypeDef,
+    PutDedicatedIpPoolScalingAttributesRequestRequestTypeDef,
     PutDedicatedIpWarmupAttributesRequestRequestTypeDef,
     PutEmailIdentityConfigurationSetAttributesRequestRequestTypeDef,
     PutEmailIdentityDkimAttributesRequestRequestTypeDef,
+    PutEmailIdentityDkimSigningAttributesResponseTypeDef,
     PutEmailIdentityFeedbackAttributesRequestRequestTypeDef,
     PutEmailIdentityMailFromAttributesRequestRequestTypeDef,
     PutSuppressedDestinationRequestRequestTypeDef,
     ReplacementTemplateTypeDef,
+    ResponseMetadataTypeDef,
     SendCustomVerificationEmailRequestRequestTypeDef,
+    SendCustomVerificationEmailResponseTypeDef,
+    SendEmailResponseTypeDef,
     SuppressedDestinationAttributesTypeDef,
     TestRenderEmailTemplateRequestRequestTypeDef,
+    TestRenderEmailTemplateResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateCustomVerificationEmailTemplateRequestRequestTypeDef,
     UpdateEmailIdentityPolicyRequestRequestTypeDef,
     AccountDetailsTypeDef,
     BatchGetMetricDataRequestRequestTypeDef,
     BatchGetMetricDataResponseTypeDef,
-    CreateDeliverabilityTestReportResponseTypeDef,
-    CreateImportJobResponseTypeDef,
-    GetCustomVerificationEmailTemplateResponseTypeDef,
-    GetEmailIdentityPoliciesResponseTypeDef,
-    ListConfigurationSetsResponseTypeDef,
-    ListDedicatedIpPoolsResponseTypeDef,
-    PutEmailIdentityDkimSigningAttributesResponseTypeDef,
-    SendCustomVerificationEmailResponseTypeDef,
-    SendEmailResponseTypeDef,
-    TestRenderEmailTemplateResponseTypeDef,
     GetBlacklistReportsResponseTypeDef,
     BodyTypeDef,
     BulkEmailContentTypeDef,
     SendBulkEmailResponseTypeDef,
     CloudWatchDestinationTypeDef,
     ListContactListsResponseTypeDef,
     ContactTypeDef,
@@ -537,43 +538,43 @@
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

### Comparing `types-aiobotocore-sesv2-2.5.0.post1/types_aiobotocore_sesv2.egg-info/SOURCES.txt` & `types-aiobotocore-sesv2-2.5.1/types_aiobotocore_sesv2.egg-info/SOURCES.txt`

 * *Files identical despite different names*

