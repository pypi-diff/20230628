# Comparing `tmp/types-aiobotocore-pinpoint-email-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-pinpoint-email-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-pinpoint-email-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:06 2023, max compression
+gzip compressed data, was "types-aiobotocore-pinpoint-email-2.5.1.tar", last modified: Wed Jun 28 01:43:58 2023, max compression
```

## Comparing `types-aiobotocore-pinpoint-email-2.5.0.post1.tar` & `types-aiobotocore-pinpoint-email-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:06.639494 types-aiobotocore-pinpoint-email-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:19:56.000000 types-aiobotocore-pinpoint-email-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    18747 2023-03-11 12:27:06.639494 types-aiobotocore-pinpoint-email-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    17149 2023-03-11 12:19:56.000000 types-aiobotocore-pinpoint-email-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:06.639494 types-aiobotocore-pinpoint-email-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2172 2023-03-11 12:19:56.000000 types-aiobotocore-pinpoint-email-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:06.639494 types-aiobotocore-pinpoint-email-2.5.0.post1/types_aiobotocore_pinpoint_email/
--rw-r--r--   0 runner    (1001) docker     (123)     1700 2023-03-11 12:19:57.000000 types-aiobotocore-pinpoint-email-2.5.0.post1/types_aiobotocore_pinpoint_email/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1699 2023-03-11 12:19:56.000000 types-aiobotocore-pinpoint-email-2.5.0.post1/types_aiobotocore_pinpoint_email/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      969 2023-03-11 12:19:57.000000 types-aiobotocore-pinpoint-email-2.5.0.post1/types_aiobotocore_pinpoint_email/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    35123 2023-03-11 12:19:57.000000 types-aiobotocore-pinpoint-email-2.5.0.post1/types_aiobotocore_pinpoint_email/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    35067 2023-03-11 12:19:57.000000 types-aiobotocore-pinpoint-email-2.5.0.post1/types_aiobotocore_pinpoint_email/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9656 2023-03-11 12:19:57.000000 types-aiobotocore-pinpoint-email-2.5.0.post1/types_aiobotocore_pinpoint_email/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9654 2023-03-11 12:19:57.000000 types-aiobotocore-pinpoint-email-2.5.0.post1/types_aiobotocore_pinpoint_email/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7040 2023-03-11 12:19:57.000000 types-aiobotocore-pinpoint-email-2.5.0.post1/types_aiobotocore_pinpoint_email/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     7032 2023-03-11 12:19:57.000000 types-aiobotocore-pinpoint-email-2.5.0.post1/types_aiobotocore_pinpoint_email/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:19:57.000000 types-aiobotocore-pinpoint-email-2.5.0.post1/types_aiobotocore_pinpoint_email/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    34958 2023-03-11 12:19:58.000000 types-aiobotocore-pinpoint-email-2.5.0.post1/types_aiobotocore_pinpoint_email/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    34924 2023-03-11 12:19:57.000000 types-aiobotocore-pinpoint-email-2.5.0.post1/types_aiobotocore_pinpoint_email/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:19:56.000000 types-aiobotocore-pinpoint-email-2.5.0.post1/types_aiobotocore_pinpoint_email/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:06.639494 types-aiobotocore-pinpoint-email-2.5.0.post1/types_aiobotocore_pinpoint_email.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    18747 2023-03-11 12:27:06.000000 types-aiobotocore-pinpoint-email-2.5.0.post1/types_aiobotocore_pinpoint_email.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      946 2023-03-11 12:27:06.000000 types-aiobotocore-pinpoint-email-2.5.0.post1/types_aiobotocore_pinpoint_email.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:06.000000 types-aiobotocore-pinpoint-email-2.5.0.post1/types_aiobotocore_pinpoint_email.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:06.000000 types-aiobotocore-pinpoint-email-2.5.0.post1/types_aiobotocore_pinpoint_email.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:06.000000 types-aiobotocore-pinpoint-email-2.5.0.post1/types_aiobotocore_pinpoint_email.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       33 2023-03-11 12:27:06.000000 types-aiobotocore-pinpoint-email-2.5.0.post1/types_aiobotocore_pinpoint_email.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:58.766191 types-aiobotocore-pinpoint-email-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:36:43.000000 types-aiobotocore-pinpoint-email-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    18746 2023-06-28 01:43:58.758191 types-aiobotocore-pinpoint-email-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    17154 2023-06-28 01:36:43.000000 types-aiobotocore-pinpoint-email-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:58.766191 types-aiobotocore-pinpoint-email-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2166 2023-06-28 01:36:43.000000 types-aiobotocore-pinpoint-email-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:58.754191 types-aiobotocore-pinpoint-email-2.5.1/types_aiobotocore_pinpoint_email/
+-rw-r--r--   0 runner    (1001) docker     (123)     1700 2023-06-28 01:36:43.000000 types-aiobotocore-pinpoint-email-2.5.1/types_aiobotocore_pinpoint_email/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1699 2023-06-28 01:36:43.000000 types-aiobotocore-pinpoint-email-2.5.1/types_aiobotocore_pinpoint_email/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      957 2023-06-28 01:36:43.000000 types-aiobotocore-pinpoint-email-2.5.1/types_aiobotocore_pinpoint_email/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    35123 2023-06-28 01:36:44.000000 types-aiobotocore-pinpoint-email-2.5.1/types_aiobotocore_pinpoint_email/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    35067 2023-06-28 01:36:44.000000 types-aiobotocore-pinpoint-email-2.5.1/types_aiobotocore_pinpoint_email/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9865 2023-06-28 01:36:44.000000 types-aiobotocore-pinpoint-email-2.5.1/types_aiobotocore_pinpoint_email/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9863 2023-06-28 01:36:44.000000 types-aiobotocore-pinpoint-email-2.5.1/types_aiobotocore_pinpoint_email/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     6930 2023-06-28 01:36:44.000000 types-aiobotocore-pinpoint-email-2.5.1/types_aiobotocore_pinpoint_email/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6923 2023-06-28 01:36:44.000000 types-aiobotocore-pinpoint-email-2.5.1/types_aiobotocore_pinpoint_email/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:36:43.000000 types-aiobotocore-pinpoint-email-2.5.1/types_aiobotocore_pinpoint_email/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    35008 2023-06-28 01:36:45.000000 types-aiobotocore-pinpoint-email-2.5.1/types_aiobotocore_pinpoint_email/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    34974 2023-06-28 01:36:44.000000 types-aiobotocore-pinpoint-email-2.5.1/types_aiobotocore_pinpoint_email/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:36:43.000000 types-aiobotocore-pinpoint-email-2.5.1/types_aiobotocore_pinpoint_email/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:58.758191 types-aiobotocore-pinpoint-email-2.5.1/types_aiobotocore_pinpoint_email.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    18746 2023-06-28 01:43:58.000000 types-aiobotocore-pinpoint-email-2.5.1/types_aiobotocore_pinpoint_email.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      946 2023-06-28 01:43:58.000000 types-aiobotocore-pinpoint-email-2.5.1/types_aiobotocore_pinpoint_email.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:58.000000 types-aiobotocore-pinpoint-email-2.5.1/types_aiobotocore_pinpoint_email.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:58.000000 types-aiobotocore-pinpoint-email-2.5.1/types_aiobotocore_pinpoint_email.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:58.000000 types-aiobotocore-pinpoint-email-2.5.1/types_aiobotocore_pinpoint_email.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       33 2023-06-28 01:43:58.000000 types-aiobotocore-pinpoint-email-2.5.1/types_aiobotocore_pinpoint_email.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-pinpoint-email-2.5.0.post1/LICENSE` & `types-aiobotocore-pinpoint-email-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-pinpoint-email-2.5.0.post1/PKG-INFO` & `types-aiobotocore-pinpoint-email-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-pinpoint-email
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.PinpointEmail 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.PinpointEmail 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint_email/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-pinpoint-email"></a>
 
 # types-aiobotocore-pinpoint-email
 
 [![PyPI - types-aiobotocore-pinpoint-email](https://img.shields.io/pypi/v/types-aiobotocore-pinpoint-email.svg?color=blue)](https://pypi.org/project/types-aiobotocore-pinpoint-email)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-pinpoint-email.svg?color=blue)](https://pypi.org/project/types-aiobotocore-pinpoint-email)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint_email/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-pinpoint-email?color=blue)](https://pypistats.org/packages/types-aiobotocore-pinpoint-email)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.PinpointEmail 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail)
+[aiobotocore.PinpointEmail 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail)
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
 [types-aiobotocore-pinpoint-email docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint_email/).
 
 See how it helps to find and fix potential bugs:
 
@@ -356,15 +356,15 @@
     ContentTypeDef,
     CloudWatchDimensionConfigurationTypeDef,
     DeliveryOptionsTypeDef,
     ReputationOptionsTypeDef,
     SendingOptionsTypeDef,
     TagTypeDef,
     TrackingOptionsTypeDef,
-    ResponseMetadataTypeDef,
+    CreateDeliverabilityTestReportResponseTypeDef,
     DkimAttributesTypeDef,
     DomainIspPlacementTypeDef,
     VolumeStatisticsTypeDef,
     DedicatedIpTypeDef,
     DeleteConfigurationSetEventDestinationRequestRequestTypeDef,
     DeleteConfigurationSetRequestRequestTypeDef,
     DeleteDedicatedIpPoolRequestRequestTypeDef,
@@ -379,70 +379,70 @@
     PinpointDestinationTypeDef,
     SnsDestinationTypeDef,
     SendQuotaTypeDef,
     GetBlacklistReportsRequestRequestTypeDef,
     GetConfigurationSetEventDestinationsRequestRequestTypeDef,
     GetConfigurationSetRequestRequestTypeDef,
     GetDedicatedIpRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetDedicatedIpsRequestGetDedicatedIpsPaginateTypeDef,
     GetDedicatedIpsRequestRequestTypeDef,
     GetDeliverabilityTestReportRequestRequestTypeDef,
     PlacementStatisticsTypeDef,
     GetDomainDeliverabilityCampaignRequestRequestTypeDef,
     GetDomainStatisticsReportRequestRequestTypeDef,
     GetEmailIdentityRequestRequestTypeDef,
     MailFromAttributesTypeDef,
     IdentityInfoTypeDef,
+    ListConfigurationSetsRequestListConfigurationSetsPaginateTypeDef,
     ListConfigurationSetsRequestRequestTypeDef,
+    ListConfigurationSetsResponseTypeDef,
+    ListDedicatedIpPoolsRequestListDedicatedIpPoolsPaginateTypeDef,
     ListDedicatedIpPoolsRequestRequestTypeDef,
+    ListDedicatedIpPoolsResponseTypeDef,
+    ListDeliverabilityTestReportsRequestListDeliverabilityTestReportsPaginateTypeDef,
     ListDeliverabilityTestReportsRequestRequestTypeDef,
     ListDomainDeliverabilityCampaignsRequestRequestTypeDef,
+    ListEmailIdentitiesRequestListEmailIdentitiesPaginateTypeDef,
     ListEmailIdentitiesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     MessageTagTypeDef,
+    PaginatorConfigTypeDef,
     PutAccountDedicatedIpWarmupAttributesRequestRequestTypeDef,
     PutAccountSendingAttributesRequestRequestTypeDef,
     PutConfigurationSetDeliveryOptionsRequestRequestTypeDef,
     PutConfigurationSetReputationOptionsRequestRequestTypeDef,
     PutConfigurationSetSendingOptionsRequestRequestTypeDef,
     PutConfigurationSetTrackingOptionsRequestRequestTypeDef,
     PutDedicatedIpInPoolRequestRequestTypeDef,
     PutDedicatedIpWarmupAttributesRequestRequestTypeDef,
     PutEmailIdentityDkimAttributesRequestRequestTypeDef,
     PutEmailIdentityFeedbackAttributesRequestRequestTypeDef,
     PutEmailIdentityMailFromAttributesRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
+    SendEmailResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
+    GetBlacklistReportsResponseTypeDef,
     BodyTypeDef,
     CloudWatchDestinationTypeDef,
     CreateDedicatedIpPoolRequestRequestTypeDef,
     CreateEmailIdentityRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     CreateConfigurationSetRequestRequestTypeDef,
-    CreateDeliverabilityTestReportResponseTypeDef,
-    GetBlacklistReportsResponseTypeDef,
     GetConfigurationSetResponseTypeDef,
-    ListConfigurationSetsResponseTypeDef,
-    ListDedicatedIpPoolsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    SendEmailResponseTypeDef,
     CreateEmailIdentityResponseTypeDef,
     DailyVolumeTypeDef,
     OverallVolumeTypeDef,
     GetDedicatedIpResponseTypeDef,
     GetDedicatedIpsResponseTypeDef,
     ListDeliverabilityTestReportsResponseTypeDef,
     GetDomainDeliverabilityCampaignResponseTypeDef,
     ListDomainDeliverabilityCampaignsResponseTypeDef,
     DomainDeliverabilityTrackingOptionTypeDef,
     GetAccountResponseTypeDef,
-    GetDedicatedIpsRequestGetDedicatedIpsPaginateTypeDef,
-    ListConfigurationSetsRequestListConfigurationSetsPaginateTypeDef,
-    ListDedicatedIpPoolsRequestListDedicatedIpPoolsPaginateTypeDef,
-    ListDeliverabilityTestReportsRequestListDeliverabilityTestReportsPaginateTypeDef,
-    ListEmailIdentitiesRequestListEmailIdentitiesPaginateTypeDef,
     IspPlacementTypeDef,
     GetEmailIdentityResponseTypeDef,
     ListEmailIdentitiesResponseTypeDef,
     MessageTypeDef,
     EventDestinationDefinitionTypeDef,
     EventDestinationTypeDef,
     GetDomainStatisticsReportResponseTypeDef,
@@ -465,43 +465,43 @@
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

### Comparing `types-aiobotocore-pinpoint-email-2.5.0.post1/README.md` & `types-aiobotocore-pinpoint-email-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-pinpoint-email"></a>
 
 # types-aiobotocore-pinpoint-email
 
 [![PyPI - types-aiobotocore-pinpoint-email](https://img.shields.io/pypi/v/types-aiobotocore-pinpoint-email.svg?color=blue)](https://pypi.org/project/types-aiobotocore-pinpoint-email)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-pinpoint-email.svg?color=blue)](https://pypi.org/project/types-aiobotocore-pinpoint-email)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint_email/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-pinpoint-email?color=blue)](https://pypistats.org/packages/types-aiobotocore-pinpoint-email)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.PinpointEmail 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail)
+[aiobotocore.PinpointEmail 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail)
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
 [types-aiobotocore-pinpoint-email docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint_email/).
 
 See how it helps to find and fix potential bugs:
 
@@ -323,15 +323,15 @@
     ContentTypeDef,
     CloudWatchDimensionConfigurationTypeDef,
     DeliveryOptionsTypeDef,
     ReputationOptionsTypeDef,
     SendingOptionsTypeDef,
     TagTypeDef,
     TrackingOptionsTypeDef,
-    ResponseMetadataTypeDef,
+    CreateDeliverabilityTestReportResponseTypeDef,
     DkimAttributesTypeDef,
     DomainIspPlacementTypeDef,
     VolumeStatisticsTypeDef,
     DedicatedIpTypeDef,
     DeleteConfigurationSetEventDestinationRequestRequestTypeDef,
     DeleteConfigurationSetRequestRequestTypeDef,
     DeleteDedicatedIpPoolRequestRequestTypeDef,
@@ -346,70 +346,70 @@
     PinpointDestinationTypeDef,
     SnsDestinationTypeDef,
     SendQuotaTypeDef,
     GetBlacklistReportsRequestRequestTypeDef,
     GetConfigurationSetEventDestinationsRequestRequestTypeDef,
     GetConfigurationSetRequestRequestTypeDef,
     GetDedicatedIpRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetDedicatedIpsRequestGetDedicatedIpsPaginateTypeDef,
     GetDedicatedIpsRequestRequestTypeDef,
     GetDeliverabilityTestReportRequestRequestTypeDef,
     PlacementStatisticsTypeDef,
     GetDomainDeliverabilityCampaignRequestRequestTypeDef,
     GetDomainStatisticsReportRequestRequestTypeDef,
     GetEmailIdentityRequestRequestTypeDef,
     MailFromAttributesTypeDef,
     IdentityInfoTypeDef,
+    ListConfigurationSetsRequestListConfigurationSetsPaginateTypeDef,
     ListConfigurationSetsRequestRequestTypeDef,
+    ListConfigurationSetsResponseTypeDef,
+    ListDedicatedIpPoolsRequestListDedicatedIpPoolsPaginateTypeDef,
     ListDedicatedIpPoolsRequestRequestTypeDef,
+    ListDedicatedIpPoolsResponseTypeDef,
+    ListDeliverabilityTestReportsRequestListDeliverabilityTestReportsPaginateTypeDef,
     ListDeliverabilityTestReportsRequestRequestTypeDef,
     ListDomainDeliverabilityCampaignsRequestRequestTypeDef,
+    ListEmailIdentitiesRequestListEmailIdentitiesPaginateTypeDef,
     ListEmailIdentitiesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     MessageTagTypeDef,
+    PaginatorConfigTypeDef,
     PutAccountDedicatedIpWarmupAttributesRequestRequestTypeDef,
     PutAccountSendingAttributesRequestRequestTypeDef,
     PutConfigurationSetDeliveryOptionsRequestRequestTypeDef,
     PutConfigurationSetReputationOptionsRequestRequestTypeDef,
     PutConfigurationSetSendingOptionsRequestRequestTypeDef,
     PutConfigurationSetTrackingOptionsRequestRequestTypeDef,
     PutDedicatedIpInPoolRequestRequestTypeDef,
     PutDedicatedIpWarmupAttributesRequestRequestTypeDef,
     PutEmailIdentityDkimAttributesRequestRequestTypeDef,
     PutEmailIdentityFeedbackAttributesRequestRequestTypeDef,
     PutEmailIdentityMailFromAttributesRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
+    SendEmailResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
+    GetBlacklistReportsResponseTypeDef,
     BodyTypeDef,
     CloudWatchDestinationTypeDef,
     CreateDedicatedIpPoolRequestRequestTypeDef,
     CreateEmailIdentityRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     CreateConfigurationSetRequestRequestTypeDef,
-    CreateDeliverabilityTestReportResponseTypeDef,
-    GetBlacklistReportsResponseTypeDef,
     GetConfigurationSetResponseTypeDef,
-    ListConfigurationSetsResponseTypeDef,
-    ListDedicatedIpPoolsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    SendEmailResponseTypeDef,
     CreateEmailIdentityResponseTypeDef,
     DailyVolumeTypeDef,
     OverallVolumeTypeDef,
     GetDedicatedIpResponseTypeDef,
     GetDedicatedIpsResponseTypeDef,
     ListDeliverabilityTestReportsResponseTypeDef,
     GetDomainDeliverabilityCampaignResponseTypeDef,
     ListDomainDeliverabilityCampaignsResponseTypeDef,
     DomainDeliverabilityTrackingOptionTypeDef,
     GetAccountResponseTypeDef,
-    GetDedicatedIpsRequestGetDedicatedIpsPaginateTypeDef,
-    ListConfigurationSetsRequestListConfigurationSetsPaginateTypeDef,
-    ListDedicatedIpPoolsRequestListDedicatedIpPoolsPaginateTypeDef,
-    ListDeliverabilityTestReportsRequestListDeliverabilityTestReportsPaginateTypeDef,
-    ListEmailIdentitiesRequestListEmailIdentitiesPaginateTypeDef,
     IspPlacementTypeDef,
     GetEmailIdentityResponseTypeDef,
     ListEmailIdentitiesResponseTypeDef,
     MessageTypeDef,
     EventDestinationDefinitionTypeDef,
     EventDestinationTypeDef,
     GetDomainStatisticsReportResponseTypeDef,
@@ -432,43 +432,43 @@
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

### Comparing `types-aiobotocore-pinpoint-email-2.5.0.post1/setup.py` & `types-aiobotocore-pinpoint-email-2.5.1/setup.py`

 * *Files 19% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-pinpoint-email.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-pinpoint-email",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_pinpoint_email"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.PinpointEmail 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.PinpointEmail 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint_email/"
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

### Comparing `types-aiobotocore-pinpoint-email-2.5.0.post1/types_aiobotocore_pinpoint_email/__init__.py` & `types-aiobotocore-pinpoint-email-2.5.1/types_aiobotocore_pinpoint_email/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-pinpoint-email-2.5.0.post1/types_aiobotocore_pinpoint_email/__init__.pyi` & `types-aiobotocore-pinpoint-email-2.5.1/types_aiobotocore_pinpoint_email/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-pinpoint-email-2.5.0.post1/types_aiobotocore_pinpoint_email/client.py` & `types-aiobotocore-pinpoint-email-2.5.1/types_aiobotocore_pinpoint_email/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-pinpoint-email-2.5.0.post1/types_aiobotocore_pinpoint_email/client.pyi` & `types-aiobotocore-pinpoint-email-2.5.1/types_aiobotocore_pinpoint_email/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-pinpoint-email-2.5.0.post1/types_aiobotocore_pinpoint_email/literals.py` & `types-aiobotocore-pinpoint-email-2.5.1/types_aiobotocore_pinpoint_email/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -119,14 +119,15 @@
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
@@ -205,14 +206,15 @@
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
@@ -223,14 +225,15 @@
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
@@ -266,14 +269,15 @@
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
@@ -292,16 +296,19 @@
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
@@ -385,15 +392,17 @@
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

### Comparing `types-aiobotocore-pinpoint-email-2.5.0.post1/types_aiobotocore_pinpoint_email/literals.pyi` & `types-aiobotocore-pinpoint-email-2.5.1/types_aiobotocore_pinpoint_email/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -117,14 +117,15 @@
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
@@ -203,14 +204,15 @@
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
@@ -221,14 +223,15 @@
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
@@ -264,14 +267,15 @@
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
@@ -290,16 +294,19 @@
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
@@ -383,15 +390,17 @@
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

### Comparing `types-aiobotocore-pinpoint-email-2.5.0.post1/types_aiobotocore_pinpoint_email/paginator.py` & `types-aiobotocore-pinpoint-email-2.5.1/types_aiobotocore_pinpoint_email/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -24,35 +24,28 @@
         get_dedicated_ips_paginator: GetDedicatedIpsPaginator = client.get_paginator("get_dedicated_ips")
         list_configuration_sets_paginator: ListConfigurationSetsPaginator = client.get_paginator("list_configuration_sets")
         list_dedicated_ip_pools_paginator: ListDedicatedIpPoolsPaginator = client.get_paginator("list_dedicated_ip_pools")
         list_deliverability_test_reports_paginator: ListDeliverabilityTestReportsPaginator = client.get_paginator("list_deliverability_test_reports")
         list_email_identities_paginator: ListEmailIdentitiesPaginator = client.get_paginator("list_email_identities")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     GetDedicatedIpsResponseTypeDef,
     ListConfigurationSetsResponseTypeDef,
     ListDedicatedIpPoolsResponseTypeDef,
     ListDeliverabilityTestReportsResponseTypeDef,
     ListEmailIdentitiesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "GetDedicatedIpsPaginator",
     "ListConfigurationSetsPaginator",
     "ListDedicatedIpPoolsPaginator",
     "ListDeliverabilityTestReportsPaginator",
     "ListEmailIdentitiesPaginator",
 )
@@ -71,73 +64,73 @@
 class GetDedicatedIpsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Paginator.GetDedicatedIps)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint_email/paginators/#getdedicatedipspaginator)
     """
 
     def paginate(
-        self, *, PoolName: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PoolName: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetDedicatedIpsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Paginator.GetDedicatedIps.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint_email/paginators/#getdedicatedipspaginator)
         """
 
 
 class ListConfigurationSetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Paginator.ListConfigurationSets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint_email/paginators/#listconfigurationsetspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListConfigurationSetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Paginator.ListConfigurationSets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint_email/paginators/#listconfigurationsetspaginator)
         """
 
 
 class ListDedicatedIpPoolsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Paginator.ListDedicatedIpPools)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint_email/paginators/#listdedicatedippoolspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDedicatedIpPoolsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Paginator.ListDedicatedIpPools.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint_email/paginators/#listdedicatedippoolspaginator)
         """
 
 
 class ListDeliverabilityTestReportsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Paginator.ListDeliverabilityTestReports)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint_email/paginators/#listdeliverabilitytestreportspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDeliverabilityTestReportsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Paginator.ListDeliverabilityTestReports.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint_email/paginators/#listdeliverabilitytestreportspaginator)
         """
 
 
 class ListEmailIdentitiesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Paginator.ListEmailIdentities)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint_email/paginators/#listemailidentitiespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEmailIdentitiesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Paginator.ListEmailIdentities.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint_email/paginators/#listemailidentitiespaginator)
         """
```

### Comparing `types-aiobotocore-pinpoint-email-2.5.0.post1/types_aiobotocore_pinpoint_email/paginator.pyi` & `types-aiobotocore-pinpoint-email-2.5.1/types_aiobotocore_pinpoint_email/paginator.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -24,34 +24,28 @@
         get_dedicated_ips_paginator: GetDedicatedIpsPaginator = client.get_paginator("get_dedicated_ips")
         list_configuration_sets_paginator: ListConfigurationSetsPaginator = client.get_paginator("list_configuration_sets")
         list_dedicated_ip_pools_paginator: ListDedicatedIpPoolsPaginator = client.get_paginator("list_dedicated_ip_pools")
         list_deliverability_test_reports_paginator: ListDeliverabilityTestReportsPaginator = client.get_paginator("list_deliverability_test_reports")
         list_email_identities_paginator: ListEmailIdentitiesPaginator = client.get_paginator("list_email_identities")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     GetDedicatedIpsResponseTypeDef,
     ListConfigurationSetsResponseTypeDef,
     ListDedicatedIpPoolsResponseTypeDef,
     ListDeliverabilityTestReportsResponseTypeDef,
     ListEmailIdentitiesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "GetDedicatedIpsPaginator",
     "ListConfigurationSetsPaginator",
     "ListDedicatedIpPoolsPaginator",
     "ListDeliverabilityTestReportsPaginator",
     "ListEmailIdentitiesPaginator",
 )
@@ -67,69 +61,69 @@
 class GetDedicatedIpsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Paginator.GetDedicatedIps)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint_email/paginators/#getdedicatedipspaginator)
     """
 
     def paginate(
-        self, *, PoolName: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PoolName: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetDedicatedIpsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Paginator.GetDedicatedIps.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint_email/paginators/#getdedicatedipspaginator)
         """
 
 class ListConfigurationSetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Paginator.ListConfigurationSets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint_email/paginators/#listconfigurationsetspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListConfigurationSetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Paginator.ListConfigurationSets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint_email/paginators/#listconfigurationsetspaginator)
         """
 
 class ListDedicatedIpPoolsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Paginator.ListDedicatedIpPools)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint_email/paginators/#listdedicatedippoolspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDedicatedIpPoolsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Paginator.ListDedicatedIpPools.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint_email/paginators/#listdedicatedippoolspaginator)
         """
 
 class ListDeliverabilityTestReportsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Paginator.ListDeliverabilityTestReports)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint_email/paginators/#listdeliverabilitytestreportspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDeliverabilityTestReportsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Paginator.ListDeliverabilityTestReports.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint_email/paginators/#listdeliverabilitytestreportspaginator)
         """
 
 class ListEmailIdentitiesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Paginator.ListEmailIdentities)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint_email/paginators/#listemailidentitiespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListEmailIdentitiesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail.Paginator.ListEmailIdentities.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint_email/paginators/#listemailidentitiespaginator)
         """
```

### Comparing `types-aiobotocore-pinpoint-email-2.5.0.post1/types_aiobotocore_pinpoint_email/type_defs.py` & `types-aiobotocore-pinpoint-email-2.5.1/types_aiobotocore_pinpoint_email/type_defs.py`

 * *Files 3% similar despite different names*

```diff
@@ -41,15 +41,15 @@
     "ContentTypeDef",
     "CloudWatchDimensionConfigurationTypeDef",
     "DeliveryOptionsTypeDef",
     "ReputationOptionsTypeDef",
     "SendingOptionsTypeDef",
     "TagTypeDef",
     "TrackingOptionsTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateDeliverabilityTestReportResponseTypeDef",
     "DkimAttributesTypeDef",
     "DomainIspPlacementTypeDef",
     "VolumeStatisticsTypeDef",
     "DedicatedIpTypeDef",
     "DeleteConfigurationSetEventDestinationRequestRequestTypeDef",
     "DeleteConfigurationSetRequestRequestTypeDef",
     "DeleteDedicatedIpPoolRequestRequestTypeDef",
@@ -64,70 +64,70 @@
     "PinpointDestinationTypeDef",
     "SnsDestinationTypeDef",
     "SendQuotaTypeDef",
     "GetBlacklistReportsRequestRequestTypeDef",
     "GetConfigurationSetEventDestinationsRequestRequestTypeDef",
     "GetConfigurationSetRequestRequestTypeDef",
     "GetDedicatedIpRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetDedicatedIpsRequestGetDedicatedIpsPaginateTypeDef",
     "GetDedicatedIpsRequestRequestTypeDef",
     "GetDeliverabilityTestReportRequestRequestTypeDef",
     "PlacementStatisticsTypeDef",
     "GetDomainDeliverabilityCampaignRequestRequestTypeDef",
     "GetDomainStatisticsReportRequestRequestTypeDef",
     "GetEmailIdentityRequestRequestTypeDef",
     "MailFromAttributesTypeDef",
     "IdentityInfoTypeDef",
+    "ListConfigurationSetsRequestListConfigurationSetsPaginateTypeDef",
     "ListConfigurationSetsRequestRequestTypeDef",
+    "ListConfigurationSetsResponseTypeDef",
+    "ListDedicatedIpPoolsRequestListDedicatedIpPoolsPaginateTypeDef",
     "ListDedicatedIpPoolsRequestRequestTypeDef",
+    "ListDedicatedIpPoolsResponseTypeDef",
+    "ListDeliverabilityTestReportsRequestListDeliverabilityTestReportsPaginateTypeDef",
     "ListDeliverabilityTestReportsRequestRequestTypeDef",
     "ListDomainDeliverabilityCampaignsRequestRequestTypeDef",
+    "ListEmailIdentitiesRequestListEmailIdentitiesPaginateTypeDef",
     "ListEmailIdentitiesRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "MessageTagTypeDef",
+    "PaginatorConfigTypeDef",
     "PutAccountDedicatedIpWarmupAttributesRequestRequestTypeDef",
     "PutAccountSendingAttributesRequestRequestTypeDef",
     "PutConfigurationSetDeliveryOptionsRequestRequestTypeDef",
     "PutConfigurationSetReputationOptionsRequestRequestTypeDef",
     "PutConfigurationSetSendingOptionsRequestRequestTypeDef",
     "PutConfigurationSetTrackingOptionsRequestRequestTypeDef",
     "PutDedicatedIpInPoolRequestRequestTypeDef",
     "PutDedicatedIpWarmupAttributesRequestRequestTypeDef",
     "PutEmailIdentityDkimAttributesRequestRequestTypeDef",
     "PutEmailIdentityFeedbackAttributesRequestRequestTypeDef",
     "PutEmailIdentityMailFromAttributesRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
+    "SendEmailResponseTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "GetBlacklistReportsResponseTypeDef",
     "BodyTypeDef",
     "CloudWatchDestinationTypeDef",
     "CreateDedicatedIpPoolRequestRequestTypeDef",
     "CreateEmailIdentityRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "CreateConfigurationSetRequestRequestTypeDef",
-    "CreateDeliverabilityTestReportResponseTypeDef",
-    "GetBlacklistReportsResponseTypeDef",
     "GetConfigurationSetResponseTypeDef",
-    "ListConfigurationSetsResponseTypeDef",
-    "ListDedicatedIpPoolsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "SendEmailResponseTypeDef",
     "CreateEmailIdentityResponseTypeDef",
     "DailyVolumeTypeDef",
     "OverallVolumeTypeDef",
     "GetDedicatedIpResponseTypeDef",
     "GetDedicatedIpsResponseTypeDef",
     "ListDeliverabilityTestReportsResponseTypeDef",
     "GetDomainDeliverabilityCampaignResponseTypeDef",
     "ListDomainDeliverabilityCampaignsResponseTypeDef",
     "DomainDeliverabilityTrackingOptionTypeDef",
     "GetAccountResponseTypeDef",
-    "GetDedicatedIpsRequestGetDedicatedIpsPaginateTypeDef",
-    "ListConfigurationSetsRequestListConfigurationSetsPaginateTypeDef",
-    "ListDedicatedIpPoolsRequestListDedicatedIpPoolsPaginateTypeDef",
-    "ListDeliverabilityTestReportsRequestListDeliverabilityTestReportsPaginateTypeDef",
-    "ListEmailIdentitiesRequestListEmailIdentitiesPaginateTypeDef",
     "IspPlacementTypeDef",
     "GetEmailIdentityResponseTypeDef",
     "ListEmailIdentitiesResponseTypeDef",
     "MessageTypeDef",
     "EventDestinationDefinitionTypeDef",
     "EventDestinationTypeDef",
     "GetDomainStatisticsReportResponseTypeDef",
@@ -217,22 +217,20 @@
 TrackingOptionsTypeDef = TypedDict(
     "TrackingOptionsTypeDef",
     {
         "CustomRedirectDomain": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateDeliverabilityTestReportResponseTypeDef = TypedDict(
+    "CreateDeliverabilityTestReportResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ReportId": str,
+        "DeliverabilityTestStatus": DeliverabilityTestStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DkimAttributesTypeDef = TypedDict(
     "DkimAttributesTypeDef",
     {
         "SigningEnabled": bool,
@@ -441,20 +439,19 @@
 GetDedicatedIpRequestRequestTypeDef = TypedDict(
     "GetDedicatedIpRequestRequestTypeDef",
     {
         "Ip": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetDedicatedIpsRequestGetDedicatedIpsPaginateTypeDef = TypedDict(
+    "GetDedicatedIpsRequestGetDedicatedIpsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PoolName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 GetDedicatedIpsRequestRequestTypeDef = TypedDict(
     "GetDedicatedIpsRequestRequestTypeDef",
     {
@@ -522,32 +519,74 @@
         "IdentityType": IdentityTypeType,
         "IdentityName": str,
         "SendingEnabled": bool,
     },
     total=False,
 )
 
+ListConfigurationSetsRequestListConfigurationSetsPaginateTypeDef = TypedDict(
+    "ListConfigurationSetsRequestListConfigurationSetsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListConfigurationSetsRequestRequestTypeDef = TypedDict(
     "ListConfigurationSetsRequestRequestTypeDef",
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
+ListDedicatedIpPoolsRequestListDedicatedIpPoolsPaginateTypeDef = TypedDict(
+    "ListDedicatedIpPoolsRequestListDedicatedIpPoolsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDedicatedIpPoolsRequestRequestTypeDef = TypedDict(
     "ListDedicatedIpPoolsRequestRequestTypeDef",
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
+ListDeliverabilityTestReportsRequestListDeliverabilityTestReportsPaginateTypeDef = TypedDict(
+    "ListDeliverabilityTestReportsRequestListDeliverabilityTestReportsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDeliverabilityTestReportsRequestRequestTypeDef = TypedDict(
     "ListDeliverabilityTestReportsRequestRequestTypeDef",
     {
         "NextToken": str,
         "PageSize": int,
     },
     total=False,
@@ -574,14 +613,22 @@
 class ListDomainDeliverabilityCampaignsRequestRequestTypeDef(
     _RequiredListDomainDeliverabilityCampaignsRequestRequestTypeDef,
     _OptionalListDomainDeliverabilityCampaignsRequestRequestTypeDef,
 ):
     pass
 
 
+ListEmailIdentitiesRequestListEmailIdentitiesPaginateTypeDef = TypedDict(
+    "ListEmailIdentitiesRequestListEmailIdentitiesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListEmailIdentitiesRequestRequestTypeDef = TypedDict(
     "ListEmailIdentitiesRequestRequestTypeDef",
     {
         "NextToken": str,
         "PageSize": int,
     },
     total=False,
@@ -598,14 +645,24 @@
     "MessageTagTypeDef",
     {
         "Name": str,
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
 PutAccountDedicatedIpWarmupAttributesRequestRequestTypeDef = TypedDict(
     "PutAccountDedicatedIpWarmupAttributesRequestRequestTypeDef",
     {
         "AutoWarmupEnabled": bool,
     },
     total=False,
 )
@@ -786,22 +843,49 @@
 class PutEmailIdentityMailFromAttributesRequestRequestTypeDef(
     _RequiredPutEmailIdentityMailFromAttributesRequestRequestTypeDef,
     _OptionalPutEmailIdentityMailFromAttributesRequestRequestTypeDef,
 ):
     pass
 
 
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
+SendEmailResponseTypeDef = TypedDict(
+    "SendEmailResponseTypeDef",
+    {
+        "MessageId": str,
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
 
+GetBlacklistReportsResponseTypeDef = TypedDict(
+    "GetBlacklistReportsResponseTypeDef",
+    {
+        "BlacklistReport": Dict[str, List[BlacklistEntryTypeDef]],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 BodyTypeDef = TypedDict(
     "BodyTypeDef",
     {
         "Text": ContentTypeDef,
         "Html": ContentTypeDef,
     },
     total=False,
@@ -854,14 +938,22 @@
 class CreateEmailIdentityRequestRequestTypeDef(
     _RequiredCreateEmailIdentityRequestRequestTypeDef,
     _OptionalCreateEmailIdentityRequestRequestTypeDef,
 ):
     pass
 
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "Tags": List[TagTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "Tags": Sequence[TagTypeDef],
     },
 )
@@ -888,85 +980,34 @@
 class CreateConfigurationSetRequestRequestTypeDef(
     _RequiredCreateConfigurationSetRequestRequestTypeDef,
     _OptionalCreateConfigurationSetRequestRequestTypeDef,
 ):
     pass
 
 
-CreateDeliverabilityTestReportResponseTypeDef = TypedDict(
-    "CreateDeliverabilityTestReportResponseTypeDef",
-    {
-        "ReportId": str,
-        "DeliverabilityTestStatus": DeliverabilityTestStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetBlacklistReportsResponseTypeDef = TypedDict(
-    "GetBlacklistReportsResponseTypeDef",
-    {
-        "BlacklistReport": Dict[str, List[BlacklistEntryTypeDef]],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 GetConfigurationSetResponseTypeDef = TypedDict(
     "GetConfigurationSetResponseTypeDef",
     {
         "ConfigurationSetName": str,
         "TrackingOptions": TrackingOptionsTypeDef,
         "DeliveryOptions": DeliveryOptionsTypeDef,
         "ReputationOptions": ReputationOptionsTypeDef,
         "SendingOptions": SendingOptionsTypeDef,
         "Tags": List[TagTypeDef],
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
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SendEmailResponseTypeDef = TypedDict(
-    "SendEmailResponseTypeDef",
-    {
-        "MessageId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
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
 
 DailyVolumeTypeDef = TypedDict(
     "DailyVolumeTypeDef",
     {
         "StartDate": datetime,
@@ -986,50 +1027,50 @@
     total=False,
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
@@ -1043,59 +1084,18 @@
     "GetAccountResponseTypeDef",
     {
         "SendQuota": SendQuotaTypeDef,
         "SendingEnabled": bool,
         "DedicatedIpAutoWarmupEnabled": bool,
         "EnforcementStatus": str,
         "ProductionAccessEnabled": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetDedicatedIpsRequestGetDedicatedIpsPaginateTypeDef = TypedDict(
-    "GetDedicatedIpsRequestGetDedicatedIpsPaginateTypeDef",
-    {
-        "PoolName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListConfigurationSetsRequestListConfigurationSetsPaginateTypeDef = TypedDict(
-    "ListConfigurationSetsRequestListConfigurationSetsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListDedicatedIpPoolsRequestListDedicatedIpPoolsPaginateTypeDef = TypedDict(
-    "ListDedicatedIpPoolsRequestListDedicatedIpPoolsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListDeliverabilityTestReportsRequestListDeliverabilityTestReportsPaginateTypeDef = TypedDict(
-    "ListDeliverabilityTestReportsRequestListDeliverabilityTestReportsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListEmailIdentitiesRequestListEmailIdentitiesPaginateTypeDef = TypedDict(
-    "ListEmailIdentitiesRequestListEmailIdentitiesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 IspPlacementTypeDef = TypedDict(
     "IspPlacementTypeDef",
     {
         "IspName": str,
         "PlacementStatistics": PlacementStatisticsTypeDef,
     },
     total=False,
@@ -1106,24 +1106,24 @@
     {
         "IdentityType": IdentityTypeType,
         "FeedbackForwardingStatus": bool,
         "VerifiedForSendingStatus": bool,
         "DkimAttributes": DkimAttributesTypeDef,
         "MailFromAttributes": MailFromAttributesTypeDef,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
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
 
 MessageTypeDef = TypedDict(
     "MessageTypeDef",
     {
         "Subject": ContentTypeDef,
@@ -1169,27 +1169,27 @@
 
 
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
@@ -1215,15 +1215,15 @@
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
 
 EmailContentTypeDef = TypedDict(
     "EmailContentTypeDef",
     {
         "Simple": MessageTypeDef,
@@ -1251,15 +1251,15 @@
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
 
 _RequiredCreateDeliverabilityTestReportRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDeliverabilityTestReportRequestRequestTypeDef",
     {
         "FromEmailAddress": str,
```

### Comparing `types-aiobotocore-pinpoint-email-2.5.0.post1/types_aiobotocore_pinpoint_email/type_defs.pyi` & `types-aiobotocore-pinpoint-email-2.5.1/types_aiobotocore_pinpoint_email/type_defs.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -40,15 +40,15 @@
     "ContentTypeDef",
     "CloudWatchDimensionConfigurationTypeDef",
     "DeliveryOptionsTypeDef",
     "ReputationOptionsTypeDef",
     "SendingOptionsTypeDef",
     "TagTypeDef",
     "TrackingOptionsTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateDeliverabilityTestReportResponseTypeDef",
     "DkimAttributesTypeDef",
     "DomainIspPlacementTypeDef",
     "VolumeStatisticsTypeDef",
     "DedicatedIpTypeDef",
     "DeleteConfigurationSetEventDestinationRequestRequestTypeDef",
     "DeleteConfigurationSetRequestRequestTypeDef",
     "DeleteDedicatedIpPoolRequestRequestTypeDef",
@@ -63,70 +63,70 @@
     "PinpointDestinationTypeDef",
     "SnsDestinationTypeDef",
     "SendQuotaTypeDef",
     "GetBlacklistReportsRequestRequestTypeDef",
     "GetConfigurationSetEventDestinationsRequestRequestTypeDef",
     "GetConfigurationSetRequestRequestTypeDef",
     "GetDedicatedIpRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetDedicatedIpsRequestGetDedicatedIpsPaginateTypeDef",
     "GetDedicatedIpsRequestRequestTypeDef",
     "GetDeliverabilityTestReportRequestRequestTypeDef",
     "PlacementStatisticsTypeDef",
     "GetDomainDeliverabilityCampaignRequestRequestTypeDef",
     "GetDomainStatisticsReportRequestRequestTypeDef",
     "GetEmailIdentityRequestRequestTypeDef",
     "MailFromAttributesTypeDef",
     "IdentityInfoTypeDef",
+    "ListConfigurationSetsRequestListConfigurationSetsPaginateTypeDef",
     "ListConfigurationSetsRequestRequestTypeDef",
+    "ListConfigurationSetsResponseTypeDef",
+    "ListDedicatedIpPoolsRequestListDedicatedIpPoolsPaginateTypeDef",
     "ListDedicatedIpPoolsRequestRequestTypeDef",
+    "ListDedicatedIpPoolsResponseTypeDef",
+    "ListDeliverabilityTestReportsRequestListDeliverabilityTestReportsPaginateTypeDef",
     "ListDeliverabilityTestReportsRequestRequestTypeDef",
     "ListDomainDeliverabilityCampaignsRequestRequestTypeDef",
+    "ListEmailIdentitiesRequestListEmailIdentitiesPaginateTypeDef",
     "ListEmailIdentitiesRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "MessageTagTypeDef",
+    "PaginatorConfigTypeDef",
     "PutAccountDedicatedIpWarmupAttributesRequestRequestTypeDef",
     "PutAccountSendingAttributesRequestRequestTypeDef",
     "PutConfigurationSetDeliveryOptionsRequestRequestTypeDef",
     "PutConfigurationSetReputationOptionsRequestRequestTypeDef",
     "PutConfigurationSetSendingOptionsRequestRequestTypeDef",
     "PutConfigurationSetTrackingOptionsRequestRequestTypeDef",
     "PutDedicatedIpInPoolRequestRequestTypeDef",
     "PutDedicatedIpWarmupAttributesRequestRequestTypeDef",
     "PutEmailIdentityDkimAttributesRequestRequestTypeDef",
     "PutEmailIdentityFeedbackAttributesRequestRequestTypeDef",
     "PutEmailIdentityMailFromAttributesRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
+    "SendEmailResponseTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "GetBlacklistReportsResponseTypeDef",
     "BodyTypeDef",
     "CloudWatchDestinationTypeDef",
     "CreateDedicatedIpPoolRequestRequestTypeDef",
     "CreateEmailIdentityRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "CreateConfigurationSetRequestRequestTypeDef",
-    "CreateDeliverabilityTestReportResponseTypeDef",
-    "GetBlacklistReportsResponseTypeDef",
     "GetConfigurationSetResponseTypeDef",
-    "ListConfigurationSetsResponseTypeDef",
-    "ListDedicatedIpPoolsResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "SendEmailResponseTypeDef",
     "CreateEmailIdentityResponseTypeDef",
     "DailyVolumeTypeDef",
     "OverallVolumeTypeDef",
     "GetDedicatedIpResponseTypeDef",
     "GetDedicatedIpsResponseTypeDef",
     "ListDeliverabilityTestReportsResponseTypeDef",
     "GetDomainDeliverabilityCampaignResponseTypeDef",
     "ListDomainDeliverabilityCampaignsResponseTypeDef",
     "DomainDeliverabilityTrackingOptionTypeDef",
     "GetAccountResponseTypeDef",
-    "GetDedicatedIpsRequestGetDedicatedIpsPaginateTypeDef",
-    "ListConfigurationSetsRequestListConfigurationSetsPaginateTypeDef",
-    "ListDedicatedIpPoolsRequestListDedicatedIpPoolsPaginateTypeDef",
-    "ListDeliverabilityTestReportsRequestListDeliverabilityTestReportsPaginateTypeDef",
-    "ListEmailIdentitiesRequestListEmailIdentitiesPaginateTypeDef",
     "IspPlacementTypeDef",
     "GetEmailIdentityResponseTypeDef",
     "ListEmailIdentitiesResponseTypeDef",
     "MessageTypeDef",
     "EventDestinationDefinitionTypeDef",
     "EventDestinationTypeDef",
     "GetDomainStatisticsReportResponseTypeDef",
@@ -214,22 +214,20 @@
 TrackingOptionsTypeDef = TypedDict(
     "TrackingOptionsTypeDef",
     {
         "CustomRedirectDomain": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateDeliverabilityTestReportResponseTypeDef = TypedDict(
+    "CreateDeliverabilityTestReportResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ReportId": str,
+        "DeliverabilityTestStatus": DeliverabilityTestStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DkimAttributesTypeDef = TypedDict(
     "DkimAttributesTypeDef",
     {
         "SigningEnabled": bool,
@@ -436,20 +434,19 @@
 GetDedicatedIpRequestRequestTypeDef = TypedDict(
     "GetDedicatedIpRequestRequestTypeDef",
     {
         "Ip": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetDedicatedIpsRequestGetDedicatedIpsPaginateTypeDef = TypedDict(
+    "GetDedicatedIpsRequestGetDedicatedIpsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PoolName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 GetDedicatedIpsRequestRequestTypeDef = TypedDict(
     "GetDedicatedIpsRequestRequestTypeDef",
     {
@@ -517,32 +514,74 @@
         "IdentityType": IdentityTypeType,
         "IdentityName": str,
         "SendingEnabled": bool,
     },
     total=False,
 )
 
+ListConfigurationSetsRequestListConfigurationSetsPaginateTypeDef = TypedDict(
+    "ListConfigurationSetsRequestListConfigurationSetsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListConfigurationSetsRequestRequestTypeDef = TypedDict(
     "ListConfigurationSetsRequestRequestTypeDef",
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
+ListDedicatedIpPoolsRequestListDedicatedIpPoolsPaginateTypeDef = TypedDict(
+    "ListDedicatedIpPoolsRequestListDedicatedIpPoolsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDedicatedIpPoolsRequestRequestTypeDef = TypedDict(
     "ListDedicatedIpPoolsRequestRequestTypeDef",
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
+ListDeliverabilityTestReportsRequestListDeliverabilityTestReportsPaginateTypeDef = TypedDict(
+    "ListDeliverabilityTestReportsRequestListDeliverabilityTestReportsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDeliverabilityTestReportsRequestRequestTypeDef = TypedDict(
     "ListDeliverabilityTestReportsRequestRequestTypeDef",
     {
         "NextToken": str,
         "PageSize": int,
     },
     total=False,
@@ -567,14 +606,22 @@
 
 class ListDomainDeliverabilityCampaignsRequestRequestTypeDef(
     _RequiredListDomainDeliverabilityCampaignsRequestRequestTypeDef,
     _OptionalListDomainDeliverabilityCampaignsRequestRequestTypeDef,
 ):
     pass
 
+ListEmailIdentitiesRequestListEmailIdentitiesPaginateTypeDef = TypedDict(
+    "ListEmailIdentitiesRequestListEmailIdentitiesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListEmailIdentitiesRequestRequestTypeDef = TypedDict(
     "ListEmailIdentitiesRequestRequestTypeDef",
     {
         "NextToken": str,
         "PageSize": int,
     },
     total=False,
@@ -591,14 +638,24 @@
     "MessageTagTypeDef",
     {
         "Name": str,
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
 PutAccountDedicatedIpWarmupAttributesRequestRequestTypeDef = TypedDict(
     "PutAccountDedicatedIpWarmupAttributesRequestRequestTypeDef",
     {
         "AutoWarmupEnabled": bool,
     },
     total=False,
 )
@@ -765,22 +822,49 @@
 
 class PutEmailIdentityMailFromAttributesRequestRequestTypeDef(
     _RequiredPutEmailIdentityMailFromAttributesRequestRequestTypeDef,
     _OptionalPutEmailIdentityMailFromAttributesRequestRequestTypeDef,
 ):
     pass
 
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
+SendEmailResponseTypeDef = TypedDict(
+    "SendEmailResponseTypeDef",
+    {
+        "MessageId": str,
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
 
+GetBlacklistReportsResponseTypeDef = TypedDict(
+    "GetBlacklistReportsResponseTypeDef",
+    {
+        "BlacklistReport": Dict[str, List[BlacklistEntryTypeDef]],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 BodyTypeDef = TypedDict(
     "BodyTypeDef",
     {
         "Text": ContentTypeDef,
         "Html": ContentTypeDef,
     },
     total=False,
@@ -829,14 +913,22 @@
 
 class CreateEmailIdentityRequestRequestTypeDef(
     _RequiredCreateEmailIdentityRequestRequestTypeDef,
     _OptionalCreateEmailIdentityRequestRequestTypeDef,
 ):
     pass
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "Tags": List[TagTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "Tags": Sequence[TagTypeDef],
     },
 )
@@ -861,85 +953,34 @@
 
 class CreateConfigurationSetRequestRequestTypeDef(
     _RequiredCreateConfigurationSetRequestRequestTypeDef,
     _OptionalCreateConfigurationSetRequestRequestTypeDef,
 ):
     pass
 
-CreateDeliverabilityTestReportResponseTypeDef = TypedDict(
-    "CreateDeliverabilityTestReportResponseTypeDef",
-    {
-        "ReportId": str,
-        "DeliverabilityTestStatus": DeliverabilityTestStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetBlacklistReportsResponseTypeDef = TypedDict(
-    "GetBlacklistReportsResponseTypeDef",
-    {
-        "BlacklistReport": Dict[str, List[BlacklistEntryTypeDef]],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 GetConfigurationSetResponseTypeDef = TypedDict(
     "GetConfigurationSetResponseTypeDef",
     {
         "ConfigurationSetName": str,
         "TrackingOptions": TrackingOptionsTypeDef,
         "DeliveryOptions": DeliveryOptionsTypeDef,
         "ReputationOptions": ReputationOptionsTypeDef,
         "SendingOptions": SendingOptionsTypeDef,
         "Tags": List[TagTypeDef],
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
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SendEmailResponseTypeDef = TypedDict(
-    "SendEmailResponseTypeDef",
-    {
-        "MessageId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
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
 
 DailyVolumeTypeDef = TypedDict(
     "DailyVolumeTypeDef",
     {
         "StartDate": datetime,
@@ -959,50 +1000,50 @@
     total=False,
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
@@ -1016,59 +1057,18 @@
     "GetAccountResponseTypeDef",
     {
         "SendQuota": SendQuotaTypeDef,
         "SendingEnabled": bool,
         "DedicatedIpAutoWarmupEnabled": bool,
         "EnforcementStatus": str,
         "ProductionAccessEnabled": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetDedicatedIpsRequestGetDedicatedIpsPaginateTypeDef = TypedDict(
-    "GetDedicatedIpsRequestGetDedicatedIpsPaginateTypeDef",
-    {
-        "PoolName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListConfigurationSetsRequestListConfigurationSetsPaginateTypeDef = TypedDict(
-    "ListConfigurationSetsRequestListConfigurationSetsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListDedicatedIpPoolsRequestListDedicatedIpPoolsPaginateTypeDef = TypedDict(
-    "ListDedicatedIpPoolsRequestListDedicatedIpPoolsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListDeliverabilityTestReportsRequestListDeliverabilityTestReportsPaginateTypeDef = TypedDict(
-    "ListDeliverabilityTestReportsRequestListDeliverabilityTestReportsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListEmailIdentitiesRequestListEmailIdentitiesPaginateTypeDef = TypedDict(
-    "ListEmailIdentitiesRequestListEmailIdentitiesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 IspPlacementTypeDef = TypedDict(
     "IspPlacementTypeDef",
     {
         "IspName": str,
         "PlacementStatistics": PlacementStatisticsTypeDef,
     },
     total=False,
@@ -1079,24 +1079,24 @@
     {
         "IdentityType": IdentityTypeType,
         "FeedbackForwardingStatus": bool,
         "VerifiedForSendingStatus": bool,
         "DkimAttributes": DkimAttributesTypeDef,
         "MailFromAttributes": MailFromAttributesTypeDef,
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
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
 
 MessageTypeDef = TypedDict(
     "MessageTypeDef",
     {
         "Subject": ContentTypeDef,
@@ -1140,27 +1140,27 @@
     pass
 
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
@@ -1184,15 +1184,15 @@
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
 
 EmailContentTypeDef = TypedDict(
     "EmailContentTypeDef",
     {
         "Simple": MessageTypeDef,
@@ -1220,15 +1220,15 @@
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
 
 _RequiredCreateDeliverabilityTestReportRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDeliverabilityTestReportRequestRequestTypeDef",
     {
         "FromEmailAddress": str,
```

### Comparing `types-aiobotocore-pinpoint-email-2.5.0.post1/types_aiobotocore_pinpoint_email.egg-info/PKG-INFO` & `types-aiobotocore-pinpoint-email-2.5.1/types_aiobotocore_pinpoint_email.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-pinpoint-email
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.PinpointEmail 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.PinpointEmail 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint_email/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-pinpoint-email"></a>
 
 # types-aiobotocore-pinpoint-email
 
 [![PyPI - types-aiobotocore-pinpoint-email](https://img.shields.io/pypi/v/types-aiobotocore-pinpoint-email.svg?color=blue)](https://pypi.org/project/types-aiobotocore-pinpoint-email)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-pinpoint-email.svg?color=blue)](https://pypi.org/project/types-aiobotocore-pinpoint-email)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint_email/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-pinpoint-email?color=blue)](https://pypistats.org/packages/types-aiobotocore-pinpoint-email)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.PinpointEmail 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail)
+[aiobotocore.PinpointEmail 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/pinpoint-email.html#PinpointEmail)
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
 [types-aiobotocore-pinpoint-email docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_pinpoint_email/).
 
 See how it helps to find and fix potential bugs:
 
@@ -356,15 +356,15 @@
     ContentTypeDef,
     CloudWatchDimensionConfigurationTypeDef,
     DeliveryOptionsTypeDef,
     ReputationOptionsTypeDef,
     SendingOptionsTypeDef,
     TagTypeDef,
     TrackingOptionsTypeDef,
-    ResponseMetadataTypeDef,
+    CreateDeliverabilityTestReportResponseTypeDef,
     DkimAttributesTypeDef,
     DomainIspPlacementTypeDef,
     VolumeStatisticsTypeDef,
     DedicatedIpTypeDef,
     DeleteConfigurationSetEventDestinationRequestRequestTypeDef,
     DeleteConfigurationSetRequestRequestTypeDef,
     DeleteDedicatedIpPoolRequestRequestTypeDef,
@@ -379,70 +379,70 @@
     PinpointDestinationTypeDef,
     SnsDestinationTypeDef,
     SendQuotaTypeDef,
     GetBlacklistReportsRequestRequestTypeDef,
     GetConfigurationSetEventDestinationsRequestRequestTypeDef,
     GetConfigurationSetRequestRequestTypeDef,
     GetDedicatedIpRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetDedicatedIpsRequestGetDedicatedIpsPaginateTypeDef,
     GetDedicatedIpsRequestRequestTypeDef,
     GetDeliverabilityTestReportRequestRequestTypeDef,
     PlacementStatisticsTypeDef,
     GetDomainDeliverabilityCampaignRequestRequestTypeDef,
     GetDomainStatisticsReportRequestRequestTypeDef,
     GetEmailIdentityRequestRequestTypeDef,
     MailFromAttributesTypeDef,
     IdentityInfoTypeDef,
+    ListConfigurationSetsRequestListConfigurationSetsPaginateTypeDef,
     ListConfigurationSetsRequestRequestTypeDef,
+    ListConfigurationSetsResponseTypeDef,
+    ListDedicatedIpPoolsRequestListDedicatedIpPoolsPaginateTypeDef,
     ListDedicatedIpPoolsRequestRequestTypeDef,
+    ListDedicatedIpPoolsResponseTypeDef,
+    ListDeliverabilityTestReportsRequestListDeliverabilityTestReportsPaginateTypeDef,
     ListDeliverabilityTestReportsRequestRequestTypeDef,
     ListDomainDeliverabilityCampaignsRequestRequestTypeDef,
+    ListEmailIdentitiesRequestListEmailIdentitiesPaginateTypeDef,
     ListEmailIdentitiesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     MessageTagTypeDef,
+    PaginatorConfigTypeDef,
     PutAccountDedicatedIpWarmupAttributesRequestRequestTypeDef,
     PutAccountSendingAttributesRequestRequestTypeDef,
     PutConfigurationSetDeliveryOptionsRequestRequestTypeDef,
     PutConfigurationSetReputationOptionsRequestRequestTypeDef,
     PutConfigurationSetSendingOptionsRequestRequestTypeDef,
     PutConfigurationSetTrackingOptionsRequestRequestTypeDef,
     PutDedicatedIpInPoolRequestRequestTypeDef,
     PutDedicatedIpWarmupAttributesRequestRequestTypeDef,
     PutEmailIdentityDkimAttributesRequestRequestTypeDef,
     PutEmailIdentityFeedbackAttributesRequestRequestTypeDef,
     PutEmailIdentityMailFromAttributesRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
+    SendEmailResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
+    GetBlacklistReportsResponseTypeDef,
     BodyTypeDef,
     CloudWatchDestinationTypeDef,
     CreateDedicatedIpPoolRequestRequestTypeDef,
     CreateEmailIdentityRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     CreateConfigurationSetRequestRequestTypeDef,
-    CreateDeliverabilityTestReportResponseTypeDef,
-    GetBlacklistReportsResponseTypeDef,
     GetConfigurationSetResponseTypeDef,
-    ListConfigurationSetsResponseTypeDef,
-    ListDedicatedIpPoolsResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    SendEmailResponseTypeDef,
     CreateEmailIdentityResponseTypeDef,
     DailyVolumeTypeDef,
     OverallVolumeTypeDef,
     GetDedicatedIpResponseTypeDef,
     GetDedicatedIpsResponseTypeDef,
     ListDeliverabilityTestReportsResponseTypeDef,
     GetDomainDeliverabilityCampaignResponseTypeDef,
     ListDomainDeliverabilityCampaignsResponseTypeDef,
     DomainDeliverabilityTrackingOptionTypeDef,
     GetAccountResponseTypeDef,
-    GetDedicatedIpsRequestGetDedicatedIpsPaginateTypeDef,
-    ListConfigurationSetsRequestListConfigurationSetsPaginateTypeDef,
-    ListDedicatedIpPoolsRequestListDedicatedIpPoolsPaginateTypeDef,
-    ListDeliverabilityTestReportsRequestListDeliverabilityTestReportsPaginateTypeDef,
-    ListEmailIdentitiesRequestListEmailIdentitiesPaginateTypeDef,
     IspPlacementTypeDef,
     GetEmailIdentityResponseTypeDef,
     ListEmailIdentitiesResponseTypeDef,
     MessageTypeDef,
     EventDestinationDefinitionTypeDef,
     EventDestinationTypeDef,
     GetDomainStatisticsReportResponseTypeDef,
@@ -465,43 +465,43 @@
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

### Comparing `types-aiobotocore-pinpoint-email-2.5.0.post1/types_aiobotocore_pinpoint_email.egg-info/SOURCES.txt` & `types-aiobotocore-pinpoint-email-2.5.1/types_aiobotocore_pinpoint_email.egg-info/SOURCES.txt`

 * *Files identical despite different names*

