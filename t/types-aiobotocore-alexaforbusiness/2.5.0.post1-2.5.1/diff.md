# Comparing `tmp/types-aiobotocore-alexaforbusiness-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-alexaforbusiness-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-alexaforbusiness-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:07 2023, max compression
+gzip compressed data, was "types-aiobotocore-alexaforbusiness-2.5.1.tar", last modified: Wed Jun 28 01:43:01 2023, max compression
```

## Comparing `types-aiobotocore-alexaforbusiness-2.5.0.post1.tar` & `types-aiobotocore-alexaforbusiness-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:07.786903 types-aiobotocore-alexaforbusiness-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:09:08.000000 types-aiobotocore-alexaforbusiness-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    24578 2023-03-11 12:26:07.786903 types-aiobotocore-alexaforbusiness-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    22971 2023-03-11 12:09:08.000000 types-aiobotocore-alexaforbusiness-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:07.786903 types-aiobotocore-alexaforbusiness-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2187 2023-03-11 12:09:08.000000 types-aiobotocore-alexaforbusiness-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:07.778904 types-aiobotocore-alexaforbusiness-2.5.0.post1/types_aiobotocore_alexaforbusiness/
--rw-r--r--   0 runner    (1001) docker     (123)     3331 2023-03-11 12:09:08.000000 types-aiobotocore-alexaforbusiness-2.5.0.post1/types_aiobotocore_alexaforbusiness/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3330 2023-03-11 12:09:08.000000 types-aiobotocore-alexaforbusiness-2.5.0.post1/types_aiobotocore_alexaforbusiness/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      979 2023-03-11 12:09:08.000000 types-aiobotocore-alexaforbusiness-2.5.0.post1/types_aiobotocore_alexaforbusiness/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    71050 2023-03-11 12:09:08.000000 types-aiobotocore-alexaforbusiness-2.5.0.post1/types_aiobotocore_alexaforbusiness/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    70935 2023-03-11 12:09:08.000000 types-aiobotocore-alexaforbusiness-2.5.0.post1/types_aiobotocore_alexaforbusiness/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    12396 2023-03-11 12:09:09.000000 types-aiobotocore-alexaforbusiness-2.5.0.post1/types_aiobotocore_alexaforbusiness/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    12394 2023-03-11 12:09:08.000000 types-aiobotocore-alexaforbusiness-2.5.0.post1/types_aiobotocore_alexaforbusiness/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    17158 2023-03-11 12:09:08.000000 types-aiobotocore-alexaforbusiness-2.5.0.post1/types_aiobotocore_alexaforbusiness/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    17142 2023-03-11 12:09:08.000000 types-aiobotocore-alexaforbusiness-2.5.0.post1/types_aiobotocore_alexaforbusiness/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:09:08.000000 types-aiobotocore-alexaforbusiness-2.5.0.post1/types_aiobotocore_alexaforbusiness/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    70800 2023-03-11 12:09:10.000000 types-aiobotocore-alexaforbusiness-2.5.0.post1/types_aiobotocore_alexaforbusiness/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    70725 2023-03-11 12:09:10.000000 types-aiobotocore-alexaforbusiness-2.5.0.post1/types_aiobotocore_alexaforbusiness/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:09:08.000000 types-aiobotocore-alexaforbusiness-2.5.0.post1/types_aiobotocore_alexaforbusiness/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:07.786903 types-aiobotocore-alexaforbusiness-2.5.0.post1/types_aiobotocore_alexaforbusiness.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    24578 2023-03-11 12:26:07.000000 types-aiobotocore-alexaforbusiness-2.5.0.post1/types_aiobotocore_alexaforbusiness.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      984 2023-03-11 12:26:07.000000 types-aiobotocore-alexaforbusiness-2.5.0.post1/types_aiobotocore_alexaforbusiness.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:07.000000 types-aiobotocore-alexaforbusiness-2.5.0.post1/types_aiobotocore_alexaforbusiness.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:07.000000 types-aiobotocore-alexaforbusiness-2.5.0.post1/types_aiobotocore_alexaforbusiness.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:07.000000 types-aiobotocore-alexaforbusiness-2.5.0.post1/types_aiobotocore_alexaforbusiness.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       35 2023-03-11 12:26:07.000000 types-aiobotocore-alexaforbusiness-2.5.0.post1/types_aiobotocore_alexaforbusiness.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:01.694085 types-aiobotocore-alexaforbusiness-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:25:45.000000 types-aiobotocore-alexaforbusiness-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    24669 2023-06-28 01:43:01.694085 types-aiobotocore-alexaforbusiness-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    23068 2023-06-28 01:25:45.000000 types-aiobotocore-alexaforbusiness-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:01.694085 types-aiobotocore-alexaforbusiness-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2181 2023-06-28 01:25:45.000000 types-aiobotocore-alexaforbusiness-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:01.686085 types-aiobotocore-alexaforbusiness-2.5.1/types_aiobotocore_alexaforbusiness/
+-rw-r--r--   0 runner    (1001) docker     (123)     3331 2023-06-28 01:25:45.000000 types-aiobotocore-alexaforbusiness-2.5.1/types_aiobotocore_alexaforbusiness/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3330 2023-06-28 01:25:45.000000 types-aiobotocore-alexaforbusiness-2.5.1/types_aiobotocore_alexaforbusiness/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      967 2023-06-28 01:25:45.000000 types-aiobotocore-alexaforbusiness-2.5.1/types_aiobotocore_alexaforbusiness/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    71050 2023-06-28 01:25:45.000000 types-aiobotocore-alexaforbusiness-2.5.1/types_aiobotocore_alexaforbusiness/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    70935 2023-06-28 01:25:45.000000 types-aiobotocore-alexaforbusiness-2.5.1/types_aiobotocore_alexaforbusiness/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    12605 2023-06-28 01:25:46.000000 types-aiobotocore-alexaforbusiness-2.5.1/types_aiobotocore_alexaforbusiness/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12603 2023-06-28 01:25:45.000000 types-aiobotocore-alexaforbusiness-2.5.1/types_aiobotocore_alexaforbusiness/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    17038 2023-06-28 01:25:45.000000 types-aiobotocore-alexaforbusiness-2.5.1/types_aiobotocore_alexaforbusiness/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17023 2023-06-28 01:25:45.000000 types-aiobotocore-alexaforbusiness-2.5.1/types_aiobotocore_alexaforbusiness/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:25:45.000000 types-aiobotocore-alexaforbusiness-2.5.1/types_aiobotocore_alexaforbusiness/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    71423 2023-06-28 01:25:47.000000 types-aiobotocore-alexaforbusiness-2.5.1/types_aiobotocore_alexaforbusiness/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    71348 2023-06-28 01:25:47.000000 types-aiobotocore-alexaforbusiness-2.5.1/types_aiobotocore_alexaforbusiness/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:25:45.000000 types-aiobotocore-alexaforbusiness-2.5.1/types_aiobotocore_alexaforbusiness/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:01.694085 types-aiobotocore-alexaforbusiness-2.5.1/types_aiobotocore_alexaforbusiness.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    24669 2023-06-28 01:43:01.000000 types-aiobotocore-alexaforbusiness-2.5.1/types_aiobotocore_alexaforbusiness.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      984 2023-06-28 01:43:01.000000 types-aiobotocore-alexaforbusiness-2.5.1/types_aiobotocore_alexaforbusiness.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:01.000000 types-aiobotocore-alexaforbusiness-2.5.1/types_aiobotocore_alexaforbusiness.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:01.000000 types-aiobotocore-alexaforbusiness-2.5.1/types_aiobotocore_alexaforbusiness.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:01.000000 types-aiobotocore-alexaforbusiness-2.5.1/types_aiobotocore_alexaforbusiness.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       35 2023-06-28 01:43:01.000000 types-aiobotocore-alexaforbusiness-2.5.1/types_aiobotocore_alexaforbusiness.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-alexaforbusiness-2.5.0.post1/LICENSE` & `types-aiobotocore-alexaforbusiness-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-alexaforbusiness-2.5.0.post1/PKG-INFO` & `types-aiobotocore-alexaforbusiness-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-alexaforbusiness
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.AlexaForBusiness 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.AlexaForBusiness 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_alexaforbusiness/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-alexaforbusiness"></a>
 
 # types-aiobotocore-alexaforbusiness
 
 [![PyPI - types-aiobotocore-alexaforbusiness](https://img.shields.io/pypi/v/types-aiobotocore-alexaforbusiness.svg?color=blue)](https://pypi.org/project/types-aiobotocore-alexaforbusiness)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-alexaforbusiness.svg?color=blue)](https://pypi.org/project/types-aiobotocore-alexaforbusiness)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_alexaforbusiness/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-alexaforbusiness?color=blue)](https://pypistats.org/packages/types-aiobotocore-alexaforbusiness)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.AlexaForBusiness 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/alexaforbusiness.html#AlexaForBusiness)
+[aiobotocore.AlexaForBusiness 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/alexaforbusiness.html#AlexaForBusiness)
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
 [types-aiobotocore-alexaforbusiness docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_alexaforbusiness/).
 
 See how it helps to find and fix potential bugs:
 
@@ -420,14 +420,15 @@
     SipAddressTypeDef,
     SsmlTypeDef,
     TextTypeDef,
     TagTypeDef,
     ResponseMetadataTypeDef,
     CreateEndOfMeetingReminderTypeDef,
     CreateInstantBookingTypeDef,
+    CreateProactiveJoinTypeDef,
     CreateRequireCheckInTypeDef,
     DeleteAddressBookRequestRequestTypeDef,
     DeleteBusinessReportScheduleRequestRequestTypeDef,
     DeleteConferenceProviderRequestRequestTypeDef,
     DeleteContactRequestRequestTypeDef,
     DeleteDeviceRequestRequestTypeDef,
     DeleteDeviceUsageDataRequestRequestTypeDef,
@@ -480,14 +481,15 @@
     ListSkillsRequestRequestTypeDef,
     SkillSummaryTypeDef,
     ListSkillsStoreCategoriesRequestRequestTypeDef,
     ListSkillsStoreSkillsByCategoryRequestRequestTypeDef,
     ListSmartHomeAppliancesRequestRequestTypeDef,
     SmartHomeApplianceTypeDef,
     ListTagsRequestRequestTypeDef,
+    ProactiveJoinTypeDef,
     RequireCheckInTypeDef,
     NetworkProfileDataTypeDef,
     ProfileDataTypeDef,
     PutInvitationConfigurationRequestRequestTypeDef,
     PutSkillAuthorizationRequestRequestTypeDef,
     RejectSkillRequestRequestTypeDef,
     ResolveRoomRequestRequestTypeDef,
@@ -502,14 +504,15 @@
     UntagResourceRequestRequestTypeDef,
     UpdateAddressBookRequestRequestTypeDef,
     UpdateDeviceRequestRequestTypeDef,
     UpdateEndOfMeetingReminderTypeDef,
     UpdateGatewayGroupRequestRequestTypeDef,
     UpdateGatewayRequestRequestTypeDef,
     UpdateInstantBookingTypeDef,
+    UpdateProactiveJoinTypeDef,
     UpdateRequireCheckInTypeDef,
     UpdateNetworkProfileRequestRequestTypeDef,
     UpdateRoomRequestRequestTypeDef,
     UpdateSkillGroupRequestRequestTypeDef,
     UpdateBusinessReportScheduleRequestRequestTypeDef,
     BusinessReportTypeDef,
     PutConferencePreferenceRequestRequestTypeDef,
@@ -619,43 +622,43 @@
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

### Comparing `types-aiobotocore-alexaforbusiness-2.5.0.post1/README.md` & `types-aiobotocore-alexaforbusiness-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-alexaforbusiness"></a>
 
 # types-aiobotocore-alexaforbusiness
 
 [![PyPI - types-aiobotocore-alexaforbusiness](https://img.shields.io/pypi/v/types-aiobotocore-alexaforbusiness.svg?color=blue)](https://pypi.org/project/types-aiobotocore-alexaforbusiness)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-alexaforbusiness.svg?color=blue)](https://pypi.org/project/types-aiobotocore-alexaforbusiness)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_alexaforbusiness/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-alexaforbusiness?color=blue)](https://pypistats.org/packages/types-aiobotocore-alexaforbusiness)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.AlexaForBusiness 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/alexaforbusiness.html#AlexaForBusiness)
+[aiobotocore.AlexaForBusiness 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/alexaforbusiness.html#AlexaForBusiness)
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
 [types-aiobotocore-alexaforbusiness docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_alexaforbusiness/).
 
 See how it helps to find and fix potential bugs:
 
@@ -387,14 +387,15 @@
     SipAddressTypeDef,
     SsmlTypeDef,
     TextTypeDef,
     TagTypeDef,
     ResponseMetadataTypeDef,
     CreateEndOfMeetingReminderTypeDef,
     CreateInstantBookingTypeDef,
+    CreateProactiveJoinTypeDef,
     CreateRequireCheckInTypeDef,
     DeleteAddressBookRequestRequestTypeDef,
     DeleteBusinessReportScheduleRequestRequestTypeDef,
     DeleteConferenceProviderRequestRequestTypeDef,
     DeleteContactRequestRequestTypeDef,
     DeleteDeviceRequestRequestTypeDef,
     DeleteDeviceUsageDataRequestRequestTypeDef,
@@ -447,14 +448,15 @@
     ListSkillsRequestRequestTypeDef,
     SkillSummaryTypeDef,
     ListSkillsStoreCategoriesRequestRequestTypeDef,
     ListSkillsStoreSkillsByCategoryRequestRequestTypeDef,
     ListSmartHomeAppliancesRequestRequestTypeDef,
     SmartHomeApplianceTypeDef,
     ListTagsRequestRequestTypeDef,
+    ProactiveJoinTypeDef,
     RequireCheckInTypeDef,
     NetworkProfileDataTypeDef,
     ProfileDataTypeDef,
     PutInvitationConfigurationRequestRequestTypeDef,
     PutSkillAuthorizationRequestRequestTypeDef,
     RejectSkillRequestRequestTypeDef,
     ResolveRoomRequestRequestTypeDef,
@@ -469,14 +471,15 @@
     UntagResourceRequestRequestTypeDef,
     UpdateAddressBookRequestRequestTypeDef,
     UpdateDeviceRequestRequestTypeDef,
     UpdateEndOfMeetingReminderTypeDef,
     UpdateGatewayGroupRequestRequestTypeDef,
     UpdateGatewayRequestRequestTypeDef,
     UpdateInstantBookingTypeDef,
+    UpdateProactiveJoinTypeDef,
     UpdateRequireCheckInTypeDef,
     UpdateNetworkProfileRequestRequestTypeDef,
     UpdateRoomRequestRequestTypeDef,
     UpdateSkillGroupRequestRequestTypeDef,
     UpdateBusinessReportScheduleRequestRequestTypeDef,
     BusinessReportTypeDef,
     PutConferencePreferenceRequestRequestTypeDef,
@@ -586,43 +589,43 @@
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

### Comparing `types-aiobotocore-alexaforbusiness-2.5.0.post1/setup.py` & `types-aiobotocore-alexaforbusiness-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-alexaforbusiness.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-alexaforbusiness",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_alexaforbusiness"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.AlexaForBusiness 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.AlexaForBusiness 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_alexaforbusiness/"
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

### Comparing `types-aiobotocore-alexaforbusiness-2.5.0.post1/types_aiobotocore_alexaforbusiness/__init__.py` & `types-aiobotocore-alexaforbusiness-2.5.1/types_aiobotocore_alexaforbusiness/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-alexaforbusiness-2.5.0.post1/types_aiobotocore_alexaforbusiness/__init__.pyi` & `types-aiobotocore-alexaforbusiness-2.5.1/types_aiobotocore_alexaforbusiness/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-alexaforbusiness-2.5.0.post1/types_aiobotocore_alexaforbusiness/__main__.py` & `types-aiobotocore-alexaforbusiness-2.5.1/types_aiobotocore_alexaforbusiness/__main__.py`

 * *Files 22% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.AlexaForBusiness 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.AlexaForBusiness 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_alexaforbusiness//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/alexaforbusiness.html#AlexaForBusiness\nOther"
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

### Comparing `types-aiobotocore-alexaforbusiness-2.5.0.post1/types_aiobotocore_alexaforbusiness/client.py` & `types-aiobotocore-alexaforbusiness-2.5.1/types_aiobotocore_alexaforbusiness/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-alexaforbusiness-2.5.0.post1/types_aiobotocore_alexaforbusiness/client.pyi` & `types-aiobotocore-alexaforbusiness-2.5.1/types_aiobotocore_alexaforbusiness/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-alexaforbusiness-2.5.0.post1/types_aiobotocore_alexaforbusiness/literals.py` & `types-aiobotocore-alexaforbusiness-2.5.1/types_aiobotocore_alexaforbusiness/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -204,14 +204,15 @@
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
@@ -290,14 +291,15 @@
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
@@ -308,14 +310,15 @@
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
@@ -351,14 +354,15 @@
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
@@ -377,16 +381,19 @@
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
@@ -470,15 +477,17 @@
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

### Comparing `types-aiobotocore-alexaforbusiness-2.5.0.post1/types_aiobotocore_alexaforbusiness/literals.pyi` & `types-aiobotocore-alexaforbusiness-2.5.1/types_aiobotocore_alexaforbusiness/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -202,14 +202,15 @@
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
@@ -288,14 +289,15 @@
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
@@ -306,14 +308,15 @@
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
@@ -349,14 +352,15 @@
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
@@ -375,16 +379,19 @@
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
@@ -468,15 +475,17 @@
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

### Comparing `types-aiobotocore-alexaforbusiness-2.5.0.post1/types_aiobotocore_alexaforbusiness/paginator.py` & `types-aiobotocore-alexaforbusiness-2.5.1/types_aiobotocore_alexaforbusiness/paginator.py`

 * *Files 1% similar despite different names*

```diff
@@ -40,16 +40,15 @@
         search_devices_paginator: SearchDevicesPaginator = client.get_paginator("search_devices")
         search_profiles_paginator: SearchProfilesPaginator = client.get_paginator("search_profiles")
         search_rooms_paginator: SearchRoomsPaginator = client.get_paginator("search_rooms")
         search_skill_groups_paginator: SearchSkillGroupsPaginator = client.get_paginator("search_skill_groups")
         search_users_paginator: SearchUsersPaginator = client.get_paginator("search_users")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import DeviceEventTypeType, EnablementTypeFilterType, SkillTypeFilterType
 from .type_defs import (
     FilterTypeDef,
@@ -66,20 +65,14 @@
     SearchProfilesResponseTypeDef,
     SearchRoomsResponseTypeDef,
     SearchSkillGroupsResponseTypeDef,
     SearchUsersResponseTypeDef,
     SortTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListBusinessReportSchedulesPaginator",
     "ListConferenceProvidersPaginator",
     "ListDeviceEventsPaginator",
     "ListSkillsPaginator",
     "ListSkillsStoreCategoriesPaginator",
     "ListSkillsStoreSkillsByCategoryPaginator",
```

### Comparing `types-aiobotocore-alexaforbusiness-2.5.0.post1/types_aiobotocore_alexaforbusiness/paginator.pyi` & `types-aiobotocore-alexaforbusiness-2.5.1/types_aiobotocore_alexaforbusiness/paginator.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -40,16 +40,15 @@
         search_devices_paginator: SearchDevicesPaginator = client.get_paginator("search_devices")
         search_profiles_paginator: SearchProfilesPaginator = client.get_paginator("search_profiles")
         search_rooms_paginator: SearchRoomsPaginator = client.get_paginator("search_rooms")
         search_skill_groups_paginator: SearchSkillGroupsPaginator = client.get_paginator("search_skill_groups")
         search_users_paginator: SearchUsersPaginator = client.get_paginator("search_users")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import DeviceEventTypeType, EnablementTypeFilterType, SkillTypeFilterType
 from .type_defs import (
     FilterTypeDef,
@@ -66,19 +65,14 @@
     SearchProfilesResponseTypeDef,
     SearchRoomsResponseTypeDef,
     SearchSkillGroupsResponseTypeDef,
     SearchUsersResponseTypeDef,
     SortTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListBusinessReportSchedulesPaginator",
     "ListConferenceProvidersPaginator",
     "ListDeviceEventsPaginator",
     "ListSkillsPaginator",
     "ListSkillsStoreCategoriesPaginator",
     "ListSkillsStoreSkillsByCategoryPaginator",
```

### Comparing `types-aiobotocore-alexaforbusiness-2.5.0.post1/types_aiobotocore_alexaforbusiness/type_defs.py` & `types-aiobotocore-alexaforbusiness-2.5.1/types_aiobotocore_alexaforbusiness/type_defs.py`

 * *Files 0% similar despite different names*

```diff
@@ -75,14 +75,15 @@
     "SipAddressTypeDef",
     "SsmlTypeDef",
     "TextTypeDef",
     "TagTypeDef",
     "ResponseMetadataTypeDef",
     "CreateEndOfMeetingReminderTypeDef",
     "CreateInstantBookingTypeDef",
+    "CreateProactiveJoinTypeDef",
     "CreateRequireCheckInTypeDef",
     "DeleteAddressBookRequestRequestTypeDef",
     "DeleteBusinessReportScheduleRequestRequestTypeDef",
     "DeleteConferenceProviderRequestRequestTypeDef",
     "DeleteContactRequestRequestTypeDef",
     "DeleteDeviceRequestRequestTypeDef",
     "DeleteDeviceUsageDataRequestRequestTypeDef",
@@ -135,14 +136,15 @@
     "ListSkillsRequestRequestTypeDef",
     "SkillSummaryTypeDef",
     "ListSkillsStoreCategoriesRequestRequestTypeDef",
     "ListSkillsStoreSkillsByCategoryRequestRequestTypeDef",
     "ListSmartHomeAppliancesRequestRequestTypeDef",
     "SmartHomeApplianceTypeDef",
     "ListTagsRequestRequestTypeDef",
+    "ProactiveJoinTypeDef",
     "RequireCheckInTypeDef",
     "NetworkProfileDataTypeDef",
     "ProfileDataTypeDef",
     "PutInvitationConfigurationRequestRequestTypeDef",
     "PutSkillAuthorizationRequestRequestTypeDef",
     "RejectSkillRequestRequestTypeDef",
     "ResolveRoomRequestRequestTypeDef",
@@ -157,14 +159,15 @@
     "UntagResourceRequestRequestTypeDef",
     "UpdateAddressBookRequestRequestTypeDef",
     "UpdateDeviceRequestRequestTypeDef",
     "UpdateEndOfMeetingReminderTypeDef",
     "UpdateGatewayGroupRequestRequestTypeDef",
     "UpdateGatewayRequestRequestTypeDef",
     "UpdateInstantBookingTypeDef",
+    "UpdateProactiveJoinTypeDef",
     "UpdateRequireCheckInTypeDef",
     "UpdateNetworkProfileRequestRequestTypeDef",
     "UpdateRoomRequestRequestTypeDef",
     "UpdateSkillGroupRequestRequestTypeDef",
     "UpdateBusinessReportScheduleRequestRequestTypeDef",
     "BusinessReportTypeDef",
     "PutConferencePreferenceRequestRequestTypeDef",
@@ -494,14 +497,21 @@
     "CreateInstantBookingTypeDef",
     {
         "DurationInMinutes": int,
         "Enabled": bool,
     },
 )
 
+CreateProactiveJoinTypeDef = TypedDict(
+    "CreateProactiveJoinTypeDef",
+    {
+        "EnabledByMotion": bool,
+    },
+)
+
 CreateRequireCheckInTypeDef = TypedDict(
     "CreateRequireCheckInTypeDef",
     {
         "ReleaseAfterMinutes": int,
         "Enabled": bool,
     },
 )
@@ -1146,14 +1156,22 @@
 
 class ListTagsRequestRequestTypeDef(
     _RequiredListTagsRequestRequestTypeDef, _OptionalListTagsRequestRequestTypeDef
 ):
     pass
 
 
+ProactiveJoinTypeDef = TypedDict(
+    "ProactiveJoinTypeDef",
+    {
+        "EnabledByMotion": bool,
+    },
+    total=False,
+)
+
 RequireCheckInTypeDef = TypedDict(
     "RequireCheckInTypeDef",
     {
         "ReleaseAfterMinutes": int,
         "Enabled": bool,
     },
     total=False,
@@ -1440,14 +1458,21 @@
     {
         "DurationInMinutes": int,
         "Enabled": bool,
     },
     total=False,
 )
 
+UpdateProactiveJoinTypeDef = TypedDict(
+    "UpdateProactiveJoinTypeDef",
+    {
+        "EnabledByMotion": bool,
+    },
+)
+
 UpdateRequireCheckInTypeDef = TypedDict(
     "UpdateRequireCheckInTypeDef",
     {
         "ReleaseAfterMinutes": int,
         "Enabled": bool,
     },
     total=False,
@@ -2069,14 +2094,15 @@
 CreateMeetingRoomConfigurationTypeDef = TypedDict(
     "CreateMeetingRoomConfigurationTypeDef",
     {
         "RoomUtilizationMetricsEnabled": bool,
         "EndOfMeetingReminder": CreateEndOfMeetingReminderTypeDef,
         "InstantBooking": CreateInstantBookingTypeDef,
         "RequireCheckIn": CreateRequireCheckInTypeDef,
+        "ProactiveJoin": CreateProactiveJoinTypeDef,
     },
     total=False,
 )
 
 SkillDetailsTypeDef = TypedDict(
     "SkillDetailsTypeDef",
     {
@@ -2356,14 +2382,15 @@
 MeetingRoomConfigurationTypeDef = TypedDict(
     "MeetingRoomConfigurationTypeDef",
     {
         "RoomUtilizationMetricsEnabled": bool,
         "EndOfMeetingReminder": EndOfMeetingReminderTypeDef,
         "InstantBooking": InstantBookingTypeDef,
         "RequireCheckIn": RequireCheckInTypeDef,
+        "ProactiveJoin": ProactiveJoinTypeDef,
     },
     total=False,
 )
 
 SearchNetworkProfilesResponseTypeDef = TypedDict(
     "SearchNetworkProfilesResponseTypeDef",
     {
@@ -2555,14 +2582,15 @@
 UpdateMeetingRoomConfigurationTypeDef = TypedDict(
     "UpdateMeetingRoomConfigurationTypeDef",
     {
         "RoomUtilizationMetricsEnabled": bool,
         "EndOfMeetingReminder": UpdateEndOfMeetingReminderTypeDef,
         "InstantBooking": UpdateInstantBookingTypeDef,
         "RequireCheckIn": UpdateRequireCheckInTypeDef,
+        "ProactiveJoin": UpdateProactiveJoinTypeDef,
     },
     total=False,
 )
 
 BusinessReportScheduleTypeDef = TypedDict(
     "BusinessReportScheduleTypeDef",
     {
```

### Comparing `types-aiobotocore-alexaforbusiness-2.5.0.post1/types_aiobotocore_alexaforbusiness/type_defs.pyi` & `types-aiobotocore-alexaforbusiness-2.5.1/types_aiobotocore_alexaforbusiness/type_defs.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -74,14 +74,15 @@
     "SipAddressTypeDef",
     "SsmlTypeDef",
     "TextTypeDef",
     "TagTypeDef",
     "ResponseMetadataTypeDef",
     "CreateEndOfMeetingReminderTypeDef",
     "CreateInstantBookingTypeDef",
+    "CreateProactiveJoinTypeDef",
     "CreateRequireCheckInTypeDef",
     "DeleteAddressBookRequestRequestTypeDef",
     "DeleteBusinessReportScheduleRequestRequestTypeDef",
     "DeleteConferenceProviderRequestRequestTypeDef",
     "DeleteContactRequestRequestTypeDef",
     "DeleteDeviceRequestRequestTypeDef",
     "DeleteDeviceUsageDataRequestRequestTypeDef",
@@ -134,14 +135,15 @@
     "ListSkillsRequestRequestTypeDef",
     "SkillSummaryTypeDef",
     "ListSkillsStoreCategoriesRequestRequestTypeDef",
     "ListSkillsStoreSkillsByCategoryRequestRequestTypeDef",
     "ListSmartHomeAppliancesRequestRequestTypeDef",
     "SmartHomeApplianceTypeDef",
     "ListTagsRequestRequestTypeDef",
+    "ProactiveJoinTypeDef",
     "RequireCheckInTypeDef",
     "NetworkProfileDataTypeDef",
     "ProfileDataTypeDef",
     "PutInvitationConfigurationRequestRequestTypeDef",
     "PutSkillAuthorizationRequestRequestTypeDef",
     "RejectSkillRequestRequestTypeDef",
     "ResolveRoomRequestRequestTypeDef",
@@ -156,14 +158,15 @@
     "UntagResourceRequestRequestTypeDef",
     "UpdateAddressBookRequestRequestTypeDef",
     "UpdateDeviceRequestRequestTypeDef",
     "UpdateEndOfMeetingReminderTypeDef",
     "UpdateGatewayGroupRequestRequestTypeDef",
     "UpdateGatewayRequestRequestTypeDef",
     "UpdateInstantBookingTypeDef",
+    "UpdateProactiveJoinTypeDef",
     "UpdateRequireCheckInTypeDef",
     "UpdateNetworkProfileRequestRequestTypeDef",
     "UpdateRoomRequestRequestTypeDef",
     "UpdateSkillGroupRequestRequestTypeDef",
     "UpdateBusinessReportScheduleRequestRequestTypeDef",
     "BusinessReportTypeDef",
     "PutConferencePreferenceRequestRequestTypeDef",
@@ -491,14 +494,21 @@
     "CreateInstantBookingTypeDef",
     {
         "DurationInMinutes": int,
         "Enabled": bool,
     },
 )
 
+CreateProactiveJoinTypeDef = TypedDict(
+    "CreateProactiveJoinTypeDef",
+    {
+        "EnabledByMotion": bool,
+    },
+)
+
 CreateRequireCheckInTypeDef = TypedDict(
     "CreateRequireCheckInTypeDef",
     {
         "ReleaseAfterMinutes": int,
         "Enabled": bool,
     },
 )
@@ -1125,14 +1135,22 @@
 )
 
 class ListTagsRequestRequestTypeDef(
     _RequiredListTagsRequestRequestTypeDef, _OptionalListTagsRequestRequestTypeDef
 ):
     pass
 
+ProactiveJoinTypeDef = TypedDict(
+    "ProactiveJoinTypeDef",
+    {
+        "EnabledByMotion": bool,
+    },
+    total=False,
+)
+
 RequireCheckInTypeDef = TypedDict(
     "RequireCheckInTypeDef",
     {
         "ReleaseAfterMinutes": int,
         "Enabled": bool,
     },
     total=False,
@@ -1407,14 +1425,21 @@
     {
         "DurationInMinutes": int,
         "Enabled": bool,
     },
     total=False,
 )
 
+UpdateProactiveJoinTypeDef = TypedDict(
+    "UpdateProactiveJoinTypeDef",
+    {
+        "EnabledByMotion": bool,
+    },
+)
+
 UpdateRequireCheckInTypeDef = TypedDict(
     "UpdateRequireCheckInTypeDef",
     {
         "ReleaseAfterMinutes": int,
         "Enabled": bool,
     },
     total=False,
@@ -2008,14 +2033,15 @@
 CreateMeetingRoomConfigurationTypeDef = TypedDict(
     "CreateMeetingRoomConfigurationTypeDef",
     {
         "RoomUtilizationMetricsEnabled": bool,
         "EndOfMeetingReminder": CreateEndOfMeetingReminderTypeDef,
         "InstantBooking": CreateInstantBookingTypeDef,
         "RequireCheckIn": CreateRequireCheckInTypeDef,
+        "ProactiveJoin": CreateProactiveJoinTypeDef,
     },
     total=False,
 )
 
 SkillDetailsTypeDef = TypedDict(
     "SkillDetailsTypeDef",
     {
@@ -2285,14 +2311,15 @@
 MeetingRoomConfigurationTypeDef = TypedDict(
     "MeetingRoomConfigurationTypeDef",
     {
         "RoomUtilizationMetricsEnabled": bool,
         "EndOfMeetingReminder": EndOfMeetingReminderTypeDef,
         "InstantBooking": InstantBookingTypeDef,
         "RequireCheckIn": RequireCheckInTypeDef,
+        "ProactiveJoin": ProactiveJoinTypeDef,
     },
     total=False,
 )
 
 SearchNetworkProfilesResponseTypeDef = TypedDict(
     "SearchNetworkProfilesResponseTypeDef",
     {
@@ -2484,14 +2511,15 @@
 UpdateMeetingRoomConfigurationTypeDef = TypedDict(
     "UpdateMeetingRoomConfigurationTypeDef",
     {
         "RoomUtilizationMetricsEnabled": bool,
         "EndOfMeetingReminder": UpdateEndOfMeetingReminderTypeDef,
         "InstantBooking": UpdateInstantBookingTypeDef,
         "RequireCheckIn": UpdateRequireCheckInTypeDef,
+        "ProactiveJoin": UpdateProactiveJoinTypeDef,
     },
     total=False,
 )
 
 BusinessReportScheduleTypeDef = TypedDict(
     "BusinessReportScheduleTypeDef",
     {
```

### Comparing `types-aiobotocore-alexaforbusiness-2.5.0.post1/types_aiobotocore_alexaforbusiness.egg-info/PKG-INFO` & `types-aiobotocore-alexaforbusiness-2.5.1/types_aiobotocore_alexaforbusiness.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-alexaforbusiness
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.AlexaForBusiness 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.AlexaForBusiness 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_alexaforbusiness/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-alexaforbusiness"></a>
 
 # types-aiobotocore-alexaforbusiness
 
 [![PyPI - types-aiobotocore-alexaforbusiness](https://img.shields.io/pypi/v/types-aiobotocore-alexaforbusiness.svg?color=blue)](https://pypi.org/project/types-aiobotocore-alexaforbusiness)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-alexaforbusiness.svg?color=blue)](https://pypi.org/project/types-aiobotocore-alexaforbusiness)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_alexaforbusiness/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-alexaforbusiness?color=blue)](https://pypistats.org/packages/types-aiobotocore-alexaforbusiness)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.AlexaForBusiness 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/alexaforbusiness.html#AlexaForBusiness)
+[aiobotocore.AlexaForBusiness 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/alexaforbusiness.html#AlexaForBusiness)
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
 [types-aiobotocore-alexaforbusiness docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_alexaforbusiness/).
 
 See how it helps to find and fix potential bugs:
 
@@ -420,14 +420,15 @@
     SipAddressTypeDef,
     SsmlTypeDef,
     TextTypeDef,
     TagTypeDef,
     ResponseMetadataTypeDef,
     CreateEndOfMeetingReminderTypeDef,
     CreateInstantBookingTypeDef,
+    CreateProactiveJoinTypeDef,
     CreateRequireCheckInTypeDef,
     DeleteAddressBookRequestRequestTypeDef,
     DeleteBusinessReportScheduleRequestRequestTypeDef,
     DeleteConferenceProviderRequestRequestTypeDef,
     DeleteContactRequestRequestTypeDef,
     DeleteDeviceRequestRequestTypeDef,
     DeleteDeviceUsageDataRequestRequestTypeDef,
@@ -480,14 +481,15 @@
     ListSkillsRequestRequestTypeDef,
     SkillSummaryTypeDef,
     ListSkillsStoreCategoriesRequestRequestTypeDef,
     ListSkillsStoreSkillsByCategoryRequestRequestTypeDef,
     ListSmartHomeAppliancesRequestRequestTypeDef,
     SmartHomeApplianceTypeDef,
     ListTagsRequestRequestTypeDef,
+    ProactiveJoinTypeDef,
     RequireCheckInTypeDef,
     NetworkProfileDataTypeDef,
     ProfileDataTypeDef,
     PutInvitationConfigurationRequestRequestTypeDef,
     PutSkillAuthorizationRequestRequestTypeDef,
     RejectSkillRequestRequestTypeDef,
     ResolveRoomRequestRequestTypeDef,
@@ -502,14 +504,15 @@
     UntagResourceRequestRequestTypeDef,
     UpdateAddressBookRequestRequestTypeDef,
     UpdateDeviceRequestRequestTypeDef,
     UpdateEndOfMeetingReminderTypeDef,
     UpdateGatewayGroupRequestRequestTypeDef,
     UpdateGatewayRequestRequestTypeDef,
     UpdateInstantBookingTypeDef,
+    UpdateProactiveJoinTypeDef,
     UpdateRequireCheckInTypeDef,
     UpdateNetworkProfileRequestRequestTypeDef,
     UpdateRoomRequestRequestTypeDef,
     UpdateSkillGroupRequestRequestTypeDef,
     UpdateBusinessReportScheduleRequestRequestTypeDef,
     BusinessReportTypeDef,
     PutConferencePreferenceRequestRequestTypeDef,
@@ -619,43 +622,43 @@
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

### Comparing `types-aiobotocore-alexaforbusiness-2.5.0.post1/types_aiobotocore_alexaforbusiness.egg-info/SOURCES.txt` & `types-aiobotocore-alexaforbusiness-2.5.1/types_aiobotocore_alexaforbusiness.egg-info/SOURCES.txt`

 * *Files identical despite different names*

