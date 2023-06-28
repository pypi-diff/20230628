# Comparing `tmp/types-aiobotocore-chime-sdk-messaging-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-chime-sdk-messaging-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-chime-sdk-messaging-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:18 2023, max compression
+gzip compressed data, was "types-aiobotocore-chime-sdk-messaging-2.5.1.tar", last modified: Wed Jun 28 01:43:11 2023, max compression
```

## Comparing `types-aiobotocore-chime-sdk-messaging-2.5.0.post1.tar` & `types-aiobotocore-chime-sdk-messaging-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:18.967013 types-aiobotocore-chime-sdk-messaging-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:10:29.000000 types-aiobotocore-chime-sdk-messaging-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    18000 2023-03-11 12:26:18.967013 types-aiobotocore-chime-sdk-messaging-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    16383 2023-03-11 12:10:29.000000 types-aiobotocore-chime-sdk-messaging-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:18.967013 types-aiobotocore-chime-sdk-messaging-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2198 2023-03-11 12:10:29.000000 types-aiobotocore-chime-sdk-messaging-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:18.955013 types-aiobotocore-chime-sdk-messaging-2.5.0.post1/types_aiobotocore_chime_sdk_messaging/
--rw-r--r--   0 runner    (1001) docker     (123)      528 2023-03-11 12:10:29.000000 types-aiobotocore-chime-sdk-messaging-2.5.0.post1/types_aiobotocore_chime_sdk_messaging/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      527 2023-03-11 12:10:29.000000 types-aiobotocore-chime-sdk-messaging-2.5.0.post1/types_aiobotocore_chime_sdk_messaging/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      987 2023-03-11 12:10:29.000000 types-aiobotocore-chime-sdk-messaging-2.5.0.post1/types_aiobotocore_chime_sdk_messaging/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    37351 2023-03-11 12:10:29.000000 types-aiobotocore-chime-sdk-messaging-2.5.0.post1/types_aiobotocore_chime_sdk_messaging/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    37296 2023-03-11 12:10:29.000000 types-aiobotocore-chime-sdk-messaging-2.5.0.post1/types_aiobotocore_chime_sdk_messaging/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8940 2023-03-11 12:10:29.000000 types-aiobotocore-chime-sdk-messaging-2.5.0.post1/types_aiobotocore_chime_sdk_messaging/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8938 2023-03-11 12:10:29.000000 types-aiobotocore-chime-sdk-messaging-2.5.0.post1/types_aiobotocore_chime_sdk_messaging/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:10:29.000000 types-aiobotocore-chime-sdk-messaging-2.5.0.post1/types_aiobotocore_chime_sdk_messaging/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    44899 2023-03-11 12:10:31.000000 types-aiobotocore-chime-sdk-messaging-2.5.0.post1/types_aiobotocore_chime_sdk_messaging/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    44840 2023-03-11 12:10:31.000000 types-aiobotocore-chime-sdk-messaging-2.5.0.post1/types_aiobotocore_chime_sdk_messaging/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:10:29.000000 types-aiobotocore-chime-sdk-messaging-2.5.0.post1/types_aiobotocore_chime_sdk_messaging/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:18.967013 types-aiobotocore-chime-sdk-messaging-2.5.0.post1/types_aiobotocore_chime_sdk_messaging.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    18000 2023-03-11 12:26:18.000000 types-aiobotocore-chime-sdk-messaging-2.5.0.post1/types_aiobotocore_chime_sdk_messaging.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      938 2023-03-11 12:26:18.000000 types-aiobotocore-chime-sdk-messaging-2.5.0.post1/types_aiobotocore_chime_sdk_messaging.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:18.000000 types-aiobotocore-chime-sdk-messaging-2.5.0.post1/types_aiobotocore_chime_sdk_messaging.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:18.000000 types-aiobotocore-chime-sdk-messaging-2.5.0.post1/types_aiobotocore_chime_sdk_messaging.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:18.000000 types-aiobotocore-chime-sdk-messaging-2.5.0.post1/types_aiobotocore_chime_sdk_messaging.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:18.000000 types-aiobotocore-chime-sdk-messaging-2.5.0.post1/types_aiobotocore_chime_sdk_messaging.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:11.214103 types-aiobotocore-chime-sdk-messaging-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:27:06.000000 types-aiobotocore-chime-sdk-messaging-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    18550 2023-06-28 01:43:11.210103 types-aiobotocore-chime-sdk-messaging-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    16939 2023-06-28 01:27:06.000000 types-aiobotocore-chime-sdk-messaging-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:11.214103 types-aiobotocore-chime-sdk-messaging-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2192 2023-06-28 01:27:06.000000 types-aiobotocore-chime-sdk-messaging-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:11.210103 types-aiobotocore-chime-sdk-messaging-2.5.1/types_aiobotocore_chime_sdk_messaging/
+-rw-r--r--   0 runner    (1001) docker     (123)      528 2023-06-28 01:27:06.000000 types-aiobotocore-chime-sdk-messaging-2.5.1/types_aiobotocore_chime_sdk_messaging/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      527 2023-06-28 01:27:06.000000 types-aiobotocore-chime-sdk-messaging-2.5.1/types_aiobotocore_chime_sdk_messaging/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      975 2023-06-28 01:27:06.000000 types-aiobotocore-chime-sdk-messaging-2.5.1/types_aiobotocore_chime_sdk_messaging/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    40511 2023-06-28 01:27:06.000000 types-aiobotocore-chime-sdk-messaging-2.5.1/types_aiobotocore_chime_sdk_messaging/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    40452 2023-06-28 01:27:06.000000 types-aiobotocore-chime-sdk-messaging-2.5.1/types_aiobotocore_chime_sdk_messaging/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9351 2023-06-28 01:27:07.000000 types-aiobotocore-chime-sdk-messaging-2.5.1/types_aiobotocore_chime_sdk_messaging/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9349 2023-06-28 01:27:06.000000 types-aiobotocore-chime-sdk-messaging-2.5.1/types_aiobotocore_chime_sdk_messaging/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:27:06.000000 types-aiobotocore-chime-sdk-messaging-2.5.1/types_aiobotocore_chime_sdk_messaging/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    47661 2023-06-28 01:27:07.000000 types-aiobotocore-chime-sdk-messaging-2.5.1/types_aiobotocore_chime_sdk_messaging/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    47604 2023-06-28 01:27:07.000000 types-aiobotocore-chime-sdk-messaging-2.5.1/types_aiobotocore_chime_sdk_messaging/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:27:06.000000 types-aiobotocore-chime-sdk-messaging-2.5.1/types_aiobotocore_chime_sdk_messaging/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:11.210103 types-aiobotocore-chime-sdk-messaging-2.5.1/types_aiobotocore_chime_sdk_messaging.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    18550 2023-06-28 01:43:11.000000 types-aiobotocore-chime-sdk-messaging-2.5.1/types_aiobotocore_chime_sdk_messaging.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      938 2023-06-28 01:43:11.000000 types-aiobotocore-chime-sdk-messaging-2.5.1/types_aiobotocore_chime_sdk_messaging.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:11.000000 types-aiobotocore-chime-sdk-messaging-2.5.1/types_aiobotocore_chime_sdk_messaging.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:11.000000 types-aiobotocore-chime-sdk-messaging-2.5.1/types_aiobotocore_chime_sdk_messaging.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:11.000000 types-aiobotocore-chime-sdk-messaging-2.5.1/types_aiobotocore_chime_sdk_messaging.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:11.000000 types-aiobotocore-chime-sdk-messaging-2.5.1/types_aiobotocore_chime_sdk_messaging.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-chime-sdk-messaging-2.5.0.post1/LICENSE` & `types-aiobotocore-chime-sdk-messaging-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-chime-sdk-messaging-2.5.0.post1/PKG-INFO` & `types-aiobotocore-chime-sdk-messaging-2.5.1/PKG-INFO`

 * *Files 11% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-chime-sdk-messaging
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ChimeSDKMessaging 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ChimeSDKMessaging 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-chime-sdk-messaging"></a>
 
 # types-aiobotocore-chime-sdk-messaging
 
 [![PyPI - types-aiobotocore-chime-sdk-messaging](https://img.shields.io/pypi/v/types-aiobotocore-chime-sdk-messaging.svg?color=blue)](https://pypi.org/project/types-aiobotocore-chime-sdk-messaging)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-chime-sdk-messaging.svg?color=blue)](https://pypi.org/project/types-aiobotocore-chime-sdk-messaging)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-chime-sdk-messaging?color=blue)](https://pypistats.org/packages/types-aiobotocore-chime-sdk-messaging)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ChimeSDKMessaging 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging)
+[aiobotocore.ChimeSDKMessaging 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging)
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
 [types-aiobotocore-chime-sdk-messaging docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/).
 
 See how it helps to find and fix potential bugs:
 
@@ -277,16 +277,18 @@
     ChannelMembershipTypeType,
     ChannelMessagePersistenceTypeType,
     ChannelMessageStatusType,
     ChannelMessageTypeType,
     ChannelModeType,
     ChannelPrivacyType,
     ErrorCodeType,
+    ExpirationCriterionType,
     FallbackActionType,
     InvocationTypeType,
+    MessagingDataTypeType,
     PushNotificationTypeType,
     SearchFieldKeyType,
     SearchFieldOperatorType,
     SortOrderType,
     ChimeSDKMessagingServiceName,
     ServiceName,
     ResourceServiceName,
@@ -308,99 +310,109 @@
 ```python
 from types_aiobotocore_chime_sdk_messaging.type_defs import (
     AppInstanceUserMembershipSummaryTypeDef,
     AssociateChannelFlowRequestRequestTypeDef,
     IdentityTypeDef,
     BatchCreateChannelMembershipErrorTypeDef,
     BatchCreateChannelMembershipRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     ChannelAssociatedWithFlowSummaryTypeDef,
+    ChannelFlowCallbackResponseTypeDef,
     ChannelSummaryTypeDef,
     PushNotificationPreferencesTypeDef,
     MessageAttributeValueTypeDef,
     PushNotificationConfigurationTypeDef,
     ChannelMessageStatusStructureTypeDef,
+    TargetTypeDef,
     ElasticChannelConfigurationTypeDef,
+    ExpirationSettingsTypeDef,
     CreateChannelBanRequestRequestTypeDef,
     TagTypeDef,
+    CreateChannelFlowResponseTypeDef,
     CreateChannelMembershipRequestRequestTypeDef,
     CreateChannelModeratorRequestRequestTypeDef,
+    CreateChannelResponseTypeDef,
     DeleteChannelBanRequestRequestTypeDef,
     DeleteChannelFlowRequestRequestTypeDef,
     DeleteChannelMembershipRequestRequestTypeDef,
     DeleteChannelMessageRequestRequestTypeDef,
     DeleteChannelModeratorRequestRequestTypeDef,
     DeleteChannelRequestRequestTypeDef,
+    DeleteMessagingStreamingConfigurationsRequestRequestTypeDef,
     DescribeChannelBanRequestRequestTypeDef,
     DescribeChannelFlowRequestRequestTypeDef,
     DescribeChannelMembershipForAppInstanceUserRequestRequestTypeDef,
     DescribeChannelMembershipRequestRequestTypeDef,
     DescribeChannelModeratedByAppInstanceUserRequestRequestTypeDef,
     DescribeChannelModeratorRequestRequestTypeDef,
     DescribeChannelRequestRequestTypeDef,
     DisassociateChannelFlowRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetChannelMembershipPreferencesRequestRequestTypeDef,
     GetChannelMessageRequestRequestTypeDef,
     GetChannelMessageStatusRequestRequestTypeDef,
     MessagingSessionEndpointTypeDef,
+    GetMessagingStreamingConfigurationsRequestRequestTypeDef,
+    StreamingConfigurationTypeDef,
     LambdaConfigurationTypeDef,
     ListChannelBansRequestRequestTypeDef,
     ListChannelFlowsRequestRequestTypeDef,
     ListChannelMembershipsForAppInstanceUserRequestRequestTypeDef,
     ListChannelMembershipsRequestRequestTypeDef,
     ListChannelMessagesRequestRequestTypeDef,
     ListChannelModeratorsRequestRequestTypeDef,
     ListChannelsAssociatedWithChannelFlowRequestRequestTypeDef,
     ListChannelsModeratedByAppInstanceUserRequestRequestTypeDef,
     ListChannelsRequestRequestTypeDef,
     ListSubChannelsRequestRequestTypeDef,
     SubChannelSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     RedactChannelMessageRequestRequestTypeDef,
+    RedactChannelMessageResponseTypeDef,
+    ResponseMetadataTypeDef,
     SearchFieldTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateChannelFlowResponseTypeDef,
     UpdateChannelMessageRequestRequestTypeDef,
     UpdateChannelReadMarkerRequestRequestTypeDef,
+    UpdateChannelReadMarkerResponseTypeDef,
     UpdateChannelRequestRequestTypeDef,
+    UpdateChannelResponseTypeDef,
     BatchChannelMembershipsTypeDef,
     ChannelBanSummaryTypeDef,
     ChannelBanTypeDef,
     ChannelMembershipSummaryTypeDef,
     ChannelMembershipTypeDef,
     ChannelModeratorSummaryTypeDef,
     ChannelModeratorTypeDef,
-    ChannelFlowCallbackResponseTypeDef,
     CreateChannelBanResponseTypeDef,
-    CreateChannelFlowResponseTypeDef,
     CreateChannelMembershipResponseTypeDef,
     CreateChannelModeratorResponseTypeDef,
-    CreateChannelResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    RedactChannelMessageResponseTypeDef,
-    UpdateChannelFlowResponseTypeDef,
-    UpdateChannelReadMarkerResponseTypeDef,
-    UpdateChannelResponseTypeDef,
     ListChannelsAssociatedWithChannelFlowResponseTypeDef,
     ChannelMembershipForAppInstanceUserSummaryTypeDef,
     ChannelModeratedByAppInstanceUserSummaryTypeDef,
     ListChannelsResponseTypeDef,
     SearchChannelsResponseTypeDef,
     ChannelMembershipPreferencesTypeDef,
     ChannelMessageCallbackTypeDef,
-    SendChannelMessageRequestRequestTypeDef,
-    ChannelMessageSummaryTypeDef,
-    ChannelMessageTypeDef,
     GetChannelMessageStatusResponseTypeDef,
     SendChannelMessageResponseTypeDef,
     UpdateChannelMessageResponseTypeDef,
+    ChannelMessageSummaryTypeDef,
+    ChannelMessageTypeDef,
+    SendChannelMessageRequestRequestTypeDef,
     ChannelTypeDef,
+    PutChannelExpirationSettingsRequestRequestTypeDef,
+    PutChannelExpirationSettingsResponseTypeDef,
     CreateChannelRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     GetMessagingSessionEndpointResponseTypeDef,
+    GetMessagingStreamingConfigurationsResponseTypeDef,
+    PutMessagingStreamingConfigurationsRequestRequestTypeDef,
+    PutMessagingStreamingConfigurationsResponseTypeDef,
     ProcessorConfigurationTypeDef,
     ListSubChannelsResponseTypeDef,
     SearchChannelsRequestRequestTypeDef,
     BatchCreateChannelMembershipResponseTypeDef,
     ListChannelBansResponseTypeDef,
     DescribeChannelBanResponseTypeDef,
     ListChannelMembershipsResponseTypeDef,
@@ -435,43 +447,43 @@
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

### Comparing `types-aiobotocore-chime-sdk-messaging-2.5.0.post1/README.md` & `types-aiobotocore-chime-sdk-messaging-2.5.1/types_aiobotocore_chime_sdk_messaging.egg-info/PKG-INFO`

 * *Files 7% similar despite different names*

```diff
@@ -1,29 +1,62 @@
+Metadata-Version: 2.1
+Name: types-aiobotocore-chime-sdk-messaging
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ChimeSDKMessaging 2.5.1 service generated with mypy-boto3-builder 7.14.5
+Home-page: https://github.com/youtype/mypy_boto3_builder
+Author: Vlad Emelianov
+Author-email: vlad.emelianov.nz@gmail.com
+License: MIT License
+Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/
+Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
+Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
+Keywords: aiobotocore chime-sdk-messaging type-annotations boto3-stubs mypy typeshed autocomplete
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
 <a id="types-aiobotocore-chime-sdk-messaging"></a>
 
 # types-aiobotocore-chime-sdk-messaging
 
 [![PyPI - types-aiobotocore-chime-sdk-messaging](https://img.shields.io/pypi/v/types-aiobotocore-chime-sdk-messaging.svg?color=blue)](https://pypi.org/project/types-aiobotocore-chime-sdk-messaging)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-chime-sdk-messaging.svg?color=blue)](https://pypi.org/project/types-aiobotocore-chime-sdk-messaging)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-chime-sdk-messaging?color=blue)](https://pypistats.org/packages/types-aiobotocore-chime-sdk-messaging)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ChimeSDKMessaging 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging)
+[aiobotocore.ChimeSDKMessaging 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging)
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
 [types-aiobotocore-chime-sdk-messaging docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/).
 
 See how it helps to find and fix potential bugs:
 
@@ -244,16 +277,18 @@
     ChannelMembershipTypeType,
     ChannelMessagePersistenceTypeType,
     ChannelMessageStatusType,
     ChannelMessageTypeType,
     ChannelModeType,
     ChannelPrivacyType,
     ErrorCodeType,
+    ExpirationCriterionType,
     FallbackActionType,
     InvocationTypeType,
+    MessagingDataTypeType,
     PushNotificationTypeType,
     SearchFieldKeyType,
     SearchFieldOperatorType,
     SortOrderType,
     ChimeSDKMessagingServiceName,
     ServiceName,
     ResourceServiceName,
@@ -275,99 +310,109 @@
 ```python
 from types_aiobotocore_chime_sdk_messaging.type_defs import (
     AppInstanceUserMembershipSummaryTypeDef,
     AssociateChannelFlowRequestRequestTypeDef,
     IdentityTypeDef,
     BatchCreateChannelMembershipErrorTypeDef,
     BatchCreateChannelMembershipRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     ChannelAssociatedWithFlowSummaryTypeDef,
+    ChannelFlowCallbackResponseTypeDef,
     ChannelSummaryTypeDef,
     PushNotificationPreferencesTypeDef,
     MessageAttributeValueTypeDef,
     PushNotificationConfigurationTypeDef,
     ChannelMessageStatusStructureTypeDef,
+    TargetTypeDef,
     ElasticChannelConfigurationTypeDef,
+    ExpirationSettingsTypeDef,
     CreateChannelBanRequestRequestTypeDef,
     TagTypeDef,
+    CreateChannelFlowResponseTypeDef,
     CreateChannelMembershipRequestRequestTypeDef,
     CreateChannelModeratorRequestRequestTypeDef,
+    CreateChannelResponseTypeDef,
     DeleteChannelBanRequestRequestTypeDef,
     DeleteChannelFlowRequestRequestTypeDef,
     DeleteChannelMembershipRequestRequestTypeDef,
     DeleteChannelMessageRequestRequestTypeDef,
     DeleteChannelModeratorRequestRequestTypeDef,
     DeleteChannelRequestRequestTypeDef,
+    DeleteMessagingStreamingConfigurationsRequestRequestTypeDef,
     DescribeChannelBanRequestRequestTypeDef,
     DescribeChannelFlowRequestRequestTypeDef,
     DescribeChannelMembershipForAppInstanceUserRequestRequestTypeDef,
     DescribeChannelMembershipRequestRequestTypeDef,
     DescribeChannelModeratedByAppInstanceUserRequestRequestTypeDef,
     DescribeChannelModeratorRequestRequestTypeDef,
     DescribeChannelRequestRequestTypeDef,
     DisassociateChannelFlowRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetChannelMembershipPreferencesRequestRequestTypeDef,
     GetChannelMessageRequestRequestTypeDef,
     GetChannelMessageStatusRequestRequestTypeDef,
     MessagingSessionEndpointTypeDef,
+    GetMessagingStreamingConfigurationsRequestRequestTypeDef,
+    StreamingConfigurationTypeDef,
     LambdaConfigurationTypeDef,
     ListChannelBansRequestRequestTypeDef,
     ListChannelFlowsRequestRequestTypeDef,
     ListChannelMembershipsForAppInstanceUserRequestRequestTypeDef,
     ListChannelMembershipsRequestRequestTypeDef,
     ListChannelMessagesRequestRequestTypeDef,
     ListChannelModeratorsRequestRequestTypeDef,
     ListChannelsAssociatedWithChannelFlowRequestRequestTypeDef,
     ListChannelsModeratedByAppInstanceUserRequestRequestTypeDef,
     ListChannelsRequestRequestTypeDef,
     ListSubChannelsRequestRequestTypeDef,
     SubChannelSummaryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     RedactChannelMessageRequestRequestTypeDef,
+    RedactChannelMessageResponseTypeDef,
+    ResponseMetadataTypeDef,
     SearchFieldTypeDef,
     UntagResourceRequestRequestTypeDef,
+    UpdateChannelFlowResponseTypeDef,
     UpdateChannelMessageRequestRequestTypeDef,
     UpdateChannelReadMarkerRequestRequestTypeDef,
+    UpdateChannelReadMarkerResponseTypeDef,
     UpdateChannelRequestRequestTypeDef,
+    UpdateChannelResponseTypeDef,
     BatchChannelMembershipsTypeDef,
     ChannelBanSummaryTypeDef,
     ChannelBanTypeDef,
     ChannelMembershipSummaryTypeDef,
     ChannelMembershipTypeDef,
     ChannelModeratorSummaryTypeDef,
     ChannelModeratorTypeDef,
-    ChannelFlowCallbackResponseTypeDef,
     CreateChannelBanResponseTypeDef,
-    CreateChannelFlowResponseTypeDef,
     CreateChannelMembershipResponseTypeDef,
     CreateChannelModeratorResponseTypeDef,
-    CreateChannelResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    RedactChannelMessageResponseTypeDef,
-    UpdateChannelFlowResponseTypeDef,
-    UpdateChannelReadMarkerResponseTypeDef,
-    UpdateChannelResponseTypeDef,
     ListChannelsAssociatedWithChannelFlowResponseTypeDef,
     ChannelMembershipForAppInstanceUserSummaryTypeDef,
     ChannelModeratedByAppInstanceUserSummaryTypeDef,
     ListChannelsResponseTypeDef,
     SearchChannelsResponseTypeDef,
     ChannelMembershipPreferencesTypeDef,
     ChannelMessageCallbackTypeDef,
-    SendChannelMessageRequestRequestTypeDef,
-    ChannelMessageSummaryTypeDef,
-    ChannelMessageTypeDef,
     GetChannelMessageStatusResponseTypeDef,
     SendChannelMessageResponseTypeDef,
     UpdateChannelMessageResponseTypeDef,
+    ChannelMessageSummaryTypeDef,
+    ChannelMessageTypeDef,
+    SendChannelMessageRequestRequestTypeDef,
     ChannelTypeDef,
+    PutChannelExpirationSettingsRequestRequestTypeDef,
+    PutChannelExpirationSettingsResponseTypeDef,
     CreateChannelRequestRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     GetMessagingSessionEndpointResponseTypeDef,
+    GetMessagingStreamingConfigurationsResponseTypeDef,
+    PutMessagingStreamingConfigurationsRequestRequestTypeDef,
+    PutMessagingStreamingConfigurationsResponseTypeDef,
     ProcessorConfigurationTypeDef,
     ListSubChannelsResponseTypeDef,
     SearchChannelsRequestRequestTypeDef,
     BatchCreateChannelMembershipResponseTypeDef,
     ListChannelBansResponseTypeDef,
     DescribeChannelBanResponseTypeDef,
     ListChannelMembershipsResponseTypeDef,
@@ -402,43 +447,43 @@
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

### Comparing `types-aiobotocore-chime-sdk-messaging-2.5.0.post1/setup.py` & `types-aiobotocore-chime-sdk-messaging-2.5.1/setup.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-chime-sdk-messaging.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-chime-sdk-messaging",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_chime_sdk_messaging"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.ChimeSDKMessaging 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.ChimeSDKMessaging 2.5.1 service generated with"
+        " mypy-boto3-builder 7.14.5"
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
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/",
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

### Comparing `types-aiobotocore-chime-sdk-messaging-2.5.0.post1/types_aiobotocore_chime_sdk_messaging/__init__.py` & `types-aiobotocore-chime-sdk-messaging-2.5.1/types_aiobotocore_chime_sdk_messaging/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-chime-sdk-messaging-2.5.0.post1/types_aiobotocore_chime_sdk_messaging/__init__.pyi` & `types-aiobotocore-chime-sdk-messaging-2.5.1/types_aiobotocore_chime_sdk_messaging/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-chime-sdk-messaging-2.5.0.post1/types_aiobotocore_chime_sdk_messaging/__main__.py` & `types-aiobotocore-chime-sdk-messaging-2.5.1/types_aiobotocore_chime_sdk_messaging/__main__.py`

 * *Files 24% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.ChimeSDKMessaging 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.ChimeSDKMessaging 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging\nOther"
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

### Comparing `types-aiobotocore-chime-sdk-messaging-2.5.0.post1/types_aiobotocore_chime_sdk_messaging/client.py` & `types-aiobotocore-chime-sdk-messaging-2.5.1/types_aiobotocore_chime_sdk_messaging/client.py`

 * *Files 2% similar despite different names*

```diff
@@ -43,38 +43,44 @@
     DescribeChannelMembershipForAppInstanceUserResponseTypeDef,
     DescribeChannelMembershipResponseTypeDef,
     DescribeChannelModeratedByAppInstanceUserResponseTypeDef,
     DescribeChannelModeratorResponseTypeDef,
     DescribeChannelResponseTypeDef,
     ElasticChannelConfigurationTypeDef,
     EmptyResponseMetadataTypeDef,
+    ExpirationSettingsTypeDef,
     GetChannelMembershipPreferencesResponseTypeDef,
     GetChannelMessageResponseTypeDef,
     GetChannelMessageStatusResponseTypeDef,
     GetMessagingSessionEndpointResponseTypeDef,
+    GetMessagingStreamingConfigurationsResponseTypeDef,
     ListChannelBansResponseTypeDef,
     ListChannelFlowsResponseTypeDef,
     ListChannelMembershipsForAppInstanceUserResponseTypeDef,
     ListChannelMembershipsResponseTypeDef,
     ListChannelMessagesResponseTypeDef,
     ListChannelModeratorsResponseTypeDef,
     ListChannelsAssociatedWithChannelFlowResponseTypeDef,
     ListChannelsModeratedByAppInstanceUserResponseTypeDef,
     ListChannelsResponseTypeDef,
     ListSubChannelsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     MessageAttributeValueTypeDef,
     ProcessorTypeDef,
     PushNotificationConfigurationTypeDef,
+    PutChannelExpirationSettingsResponseTypeDef,
     PutChannelMembershipPreferencesResponseTypeDef,
+    PutMessagingStreamingConfigurationsResponseTypeDef,
     RedactChannelMessageResponseTypeDef,
     SearchChannelsResponseTypeDef,
     SearchFieldTypeDef,
     SendChannelMessageResponseTypeDef,
+    StreamingConfigurationTypeDef,
     TagTypeDef,
+    TargetTypeDef,
     UpdateChannelFlowResponseTypeDef,
     UpdateChannelMessageResponseTypeDef,
     UpdateChannelReadMarkerResponseTypeDef,
     UpdateChannelResponseTypeDef,
 )
 
 __all__ = ("ChimeSDKMessagingClient",)
@@ -134,15 +140,15 @@
         ChannelArn: str,
         MemberArns: Sequence[str],
         ChimeBearer: str,
         Type: ChannelMembershipTypeType = ...,
         SubChannelId: str = ...
     ) -> BatchCreateChannelMembershipResponseTypeDef:
         """
-        Adds a specified number of users to a channel.
+        Adds a specified number of users and bots to a channel.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.batch_create_channel_membership)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#batch_create_channel_membership)
         """
 
     def can_paginate(self, operation_name: str) -> bool:
         """
@@ -157,15 +163,15 @@
         *,
         CallbackId: str,
         ChannelArn: str,
         ChannelMessage: ChannelMessageCallbackTypeDef,
         DeleteResource: bool = ...
     ) -> ChannelFlowCallbackResponseTypeDef:
         """
-        Calls back Chime SDK Messaging with a processing response message.
+        Calls back Amazon Chime SDK messaging with a processing response message.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.channel_flow_callback)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#channel_flow_callback)
         """
 
     async def close(self) -> None:
         """
@@ -185,15 +191,16 @@
         Mode: ChannelModeType = ...,
         Privacy: ChannelPrivacyType = ...,
         Metadata: str = ...,
         Tags: Sequence[TagTypeDef] = ...,
         ChannelId: str = ...,
         MemberArns: Sequence[str] = ...,
         ModeratorArns: Sequence[str] = ...,
-        ElasticChannelConfiguration: ElasticChannelConfigurationTypeDef = ...
+        ElasticChannelConfiguration: ElasticChannelConfigurationTypeDef = ...,
+        ExpirationSettings: ExpirationSettingsTypeDef = ...
     ) -> CreateChannelResponseTypeDef:
         """
         Creates a channel to which you can add users and send messages.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.create_channel)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#create_channel)
         """
@@ -230,15 +237,15 @@
         ChannelArn: str,
         MemberArn: str,
         Type: ChannelMembershipTypeType,
         ChimeBearer: str,
         SubChannelId: str = ...
     ) -> CreateChannelMembershipResponseTypeDef:
         """
-        Adds a user to a channel.
+        Adds a member to a channel.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.create_channel_membership)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#create_channel_membership)
         """
 
     async def create_channel_moderator(
         self, *, ChannelArn: str, ChannelModeratorArn: str, ChimeBearer: str
@@ -247,29 +254,29 @@
         Creates a new `ChannelModerator`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.create_channel_moderator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#create_channel_moderator)
         """
 
     async def delete_channel(
-        self, *, ChannelArn: str, ChimeBearer: str, SubChannelId: str = ...
+        self, *, ChannelArn: str, ChimeBearer: str
     ) -> EmptyResponseMetadataTypeDef:
         """
         Immediately makes a channel and its memberships inaccessible and marks them for
         deletion.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.delete_channel)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#delete_channel)
         """
 
     async def delete_channel_ban(
         self, *, ChannelArn: str, MemberArn: str, ChimeBearer: str
     ) -> EmptyResponseMetadataTypeDef:
         """
-        Removes a user from a channel's ban list.
+        Removes a member from a channel's ban list.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.delete_channel_ban)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#delete_channel_ban)
         """
 
     async def delete_channel_flow(self, *, ChannelFlowArn: str) -> EmptyResponseMetadataTypeDef:
         """
@@ -305,19 +312,29 @@
         """
         Deletes a channel moderator.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.delete_channel_moderator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#delete_channel_moderator)
         """
 
+    async def delete_messaging_streaming_configurations(
+        self, *, AppInstanceArn: str
+    ) -> EmptyResponseMetadataTypeDef:
+        """
+        Deletes the streaming configurations for an `AppInstance`.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.delete_messaging_streaming_configurations)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#delete_messaging_streaming_configurations)
+        """
+
     async def describe_channel(
         self, *, ChannelArn: str, ChimeBearer: str
     ) -> DescribeChannelResponseTypeDef:
         """
-        Returns the full details of a channel in an Amazon Chime `AppInstance` .
+        Returns the full details of a channel in an Amazon Chime `AppInstance`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.describe_channel)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#describe_channel)
         """
 
     async def describe_channel_ban(
         self, *, ChannelArn: str, MemberArn: str, ChimeBearer: str
@@ -350,26 +367,26 @@
         """
 
     async def describe_channel_membership_for_app_instance_user(
         self, *, ChannelArn: str, AppInstanceUserArn: str, ChimeBearer: str
     ) -> DescribeChannelMembershipForAppInstanceUserResponseTypeDef:
         """
         Returns the details of a channel based on the membership of the specified
-        `AppInstanceUser` .
+        `AppInstanceUser` or `AppInstanceBot`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.describe_channel_membership_for_app_instance_user)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#describe_channel_membership_for_app_instance_user)
         """
 
     async def describe_channel_moderated_by_app_instance_user(
         self, *, ChannelArn: str, AppInstanceUserArn: str, ChimeBearer: str
     ) -> DescribeChannelModeratedByAppInstanceUserResponseTypeDef:
         """
         Returns the full details of a channel moderated by the specified
-        `AppInstanceUser` .
+        `AppInstanceUser` or `AppInstanceBot`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.describe_channel_moderated_by_app_instance_user)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#describe_channel_moderated_by_app_instance_user)
         """
 
     async def describe_channel_moderator(
         self, *, ChannelArn: str, ChannelModeratorArn: str, ChimeBearer: str
@@ -405,16 +422,16 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#generate_presigned_url)
         """
 
     async def get_channel_membership_preferences(
         self, *, ChannelArn: str, MemberArn: str, ChimeBearer: str
     ) -> GetChannelMembershipPreferencesResponseTypeDef:
         """
-        Gets the membership preferences of an `AppInstanceUser` for the specified
-        channel.
+        Gets the membership preferences of an `AppInstanceUser` or `AppInstanceBot` for
+        the specified channel.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.get_channel_membership_preferences)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#get_channel_membership_preferences)
         """
 
     async def get_channel_message(
         self, *, ChannelArn: str, MessageId: str, ChimeBearer: str, SubChannelId: str = ...
@@ -440,19 +457,29 @@
         """
         The details of the endpoint for the messaging session.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.get_messaging_session_endpoint)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#get_messaging_session_endpoint)
         """
 
+    async def get_messaging_streaming_configurations(
+        self, *, AppInstanceArn: str
+    ) -> GetMessagingStreamingConfigurationsResponseTypeDef:
+        """
+        Retrieves the data streaming configuration for an `AppInstance`.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.get_messaging_streaming_configurations)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#get_messaging_streaming_configurations)
+        """
+
     async def list_channel_bans(
         self, *, ChannelArn: str, ChimeBearer: str, MaxResults: int = ..., NextToken: str = ...
     ) -> ListChannelBansResponseTypeDef:
         """
-        Lists all the users banned from a particular channel.
+        Lists all the users and bots banned from a particular channel.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.list_channel_bans)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#list_channel_bans)
         """
 
     async def list_channel_flows(
         self, *, AppInstanceArn: str, MaxResults: int = ..., NextToken: str = ...
@@ -486,15 +513,15 @@
         *,
         ChimeBearer: str,
         AppInstanceUserArn: str = ...,
         MaxResults: int = ...,
         NextToken: str = ...
     ) -> ListChannelMembershipsForAppInstanceUserResponseTypeDef:
         """
-        Lists all channels that a particular `AppInstanceUser` is a part of.
+        Lists all channels that an `AppInstanceUser` or `AppInstanceBot` is a part of.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.list_channel_memberships_for_app_instance_user)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#list_channel_memberships_for_app_instance_user)
         """
 
     async def list_channel_messages(
         self,
@@ -556,15 +583,15 @@
         *,
         ChimeBearer: str,
         AppInstanceUserArn: str = ...,
         MaxResults: int = ...,
         NextToken: str = ...
     ) -> ListChannelsModeratedByAppInstanceUserResponseTypeDef:
         """
-        A list of the channels moderated by an `AppInstanceUser` .
+        A list of the channels moderated by an `AppInstanceUser`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.list_channels_moderated_by_app_instance_user)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#list_channels_moderated_by_app_instance_user)
         """
 
     async def list_sub_channels(
         self, *, ChannelArn: str, ChimeBearer: str, MaxResults: int = ..., NextToken: str = ...
@@ -582,30 +609,57 @@
         """
         Lists the tags applied to an Amazon Chime SDK messaging resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#list_tags_for_resource)
         """
 
+    async def put_channel_expiration_settings(
+        self,
+        *,
+        ChannelArn: str,
+        ChimeBearer: str = ...,
+        ExpirationSettings: ExpirationSettingsTypeDef = ...
+    ) -> PutChannelExpirationSettingsResponseTypeDef:
+        """
+        Sets the number of days before the channel is automatically deleted.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.put_channel_expiration_settings)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#put_channel_expiration_settings)
+        """
+
     async def put_channel_membership_preferences(
         self,
         *,
         ChannelArn: str,
         MemberArn: str,
         ChimeBearer: str,
         Preferences: ChannelMembershipPreferencesTypeDef
     ) -> PutChannelMembershipPreferencesResponseTypeDef:
         """
-        Sets the membership preferences of an `AppInstanceUser` for the specified
-        channel.
+        Sets the membership preferences of an `AppInstanceUser` or `AppInstanceBot` for
+        the specified channel.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.put_channel_membership_preferences)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#put_channel_membership_preferences)
         """
 
+    async def put_messaging_streaming_configurations(
+        self,
+        *,
+        AppInstanceArn: str,
+        StreamingConfigurations: Sequence[StreamingConfigurationTypeDef]
+    ) -> PutMessagingStreamingConfigurationsResponseTypeDef:
+        """
+        Sets the data streaming configuration for an `AppInstance`.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.put_messaging_streaming_configurations)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#put_messaging_streaming_configurations)
+        """
+
     async def redact_channel_message(
         self, *, ChannelArn: str, MessageId: str, ChimeBearer: str, SubChannelId: str = ...
     ) -> RedactChannelMessageResponseTypeDef:
         """
         Redacts message content, but not metadata.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.redact_channel_message)
@@ -617,15 +671,15 @@
         *,
         Fields: Sequence[SearchFieldTypeDef],
         ChimeBearer: str = ...,
         MaxResults: int = ...,
         NextToken: str = ...
     ) -> SearchChannelsResponseTypeDef:
         """
-        Allows `ChimeBearer` to search channels by channel members.
+        Allows the `ChimeBearer` to search channels by channel members.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.search_channels)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#search_channels)
         """
 
     async def send_channel_message(
         self,
@@ -635,15 +689,17 @@
         Type: ChannelMessageTypeType,
         Persistence: ChannelMessagePersistenceTypeType,
         ClientRequestToken: str,
         ChimeBearer: str,
         Metadata: str = ...,
         PushNotification: PushNotificationConfigurationTypeDef = ...,
         MessageAttributes: Mapping[str, MessageAttributeValueTypeDef] = ...,
-        SubChannelId: str = ...
+        SubChannelId: str = ...,
+        ContentType: str = ...,
+        Target: Sequence[TargetTypeDef] = ...
     ) -> SendChannelMessageResponseTypeDef:
         """
         Sends a message to a particular channel that the member is a part of.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.send_channel_message)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#send_channel_message)
         """
@@ -696,28 +752,29 @@
         """
 
     async def update_channel_message(
         self,
         *,
         ChannelArn: str,
         MessageId: str,
+        Content: str,
         ChimeBearer: str,
-        Content: str = ...,
         Metadata: str = ...,
-        SubChannelId: str = ...
+        SubChannelId: str = ...,
+        ContentType: str = ...
     ) -> UpdateChannelMessageResponseTypeDef:
         """
         Updates the content of a message.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.update_channel_message)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#update_channel_message)
         """
 
     async def update_channel_read_marker(
-        self, *, ChannelArn: str, ChimeBearer: str, SubChannelId: str = ...
+        self, *, ChannelArn: str, ChimeBearer: str
     ) -> UpdateChannelReadMarkerResponseTypeDef:
         """
         The details of the time when a user last read messages in a channel.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.update_channel_read_marker)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#update_channel_read_marker)
         """
```

### Comparing `types-aiobotocore-chime-sdk-messaging-2.5.0.post1/types_aiobotocore_chime_sdk_messaging/client.pyi` & `types-aiobotocore-chime-sdk-messaging-2.5.1/types_aiobotocore_chime_sdk_messaging/client.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -43,38 +43,44 @@
     DescribeChannelMembershipForAppInstanceUserResponseTypeDef,
     DescribeChannelMembershipResponseTypeDef,
     DescribeChannelModeratedByAppInstanceUserResponseTypeDef,
     DescribeChannelModeratorResponseTypeDef,
     DescribeChannelResponseTypeDef,
     ElasticChannelConfigurationTypeDef,
     EmptyResponseMetadataTypeDef,
+    ExpirationSettingsTypeDef,
     GetChannelMembershipPreferencesResponseTypeDef,
     GetChannelMessageResponseTypeDef,
     GetChannelMessageStatusResponseTypeDef,
     GetMessagingSessionEndpointResponseTypeDef,
+    GetMessagingStreamingConfigurationsResponseTypeDef,
     ListChannelBansResponseTypeDef,
     ListChannelFlowsResponseTypeDef,
     ListChannelMembershipsForAppInstanceUserResponseTypeDef,
     ListChannelMembershipsResponseTypeDef,
     ListChannelMessagesResponseTypeDef,
     ListChannelModeratorsResponseTypeDef,
     ListChannelsAssociatedWithChannelFlowResponseTypeDef,
     ListChannelsModeratedByAppInstanceUserResponseTypeDef,
     ListChannelsResponseTypeDef,
     ListSubChannelsResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
     MessageAttributeValueTypeDef,
     ProcessorTypeDef,
     PushNotificationConfigurationTypeDef,
+    PutChannelExpirationSettingsResponseTypeDef,
     PutChannelMembershipPreferencesResponseTypeDef,
+    PutMessagingStreamingConfigurationsResponseTypeDef,
     RedactChannelMessageResponseTypeDef,
     SearchChannelsResponseTypeDef,
     SearchFieldTypeDef,
     SendChannelMessageResponseTypeDef,
+    StreamingConfigurationTypeDef,
     TagTypeDef,
+    TargetTypeDef,
     UpdateChannelFlowResponseTypeDef,
     UpdateChannelMessageResponseTypeDef,
     UpdateChannelReadMarkerResponseTypeDef,
     UpdateChannelResponseTypeDef,
 )
 
 __all__ = ("ChimeSDKMessagingClient",)
@@ -129,15 +135,15 @@
         ChannelArn: str,
         MemberArns: Sequence[str],
         ChimeBearer: str,
         Type: ChannelMembershipTypeType = ...,
         SubChannelId: str = ...
     ) -> BatchCreateChannelMembershipResponseTypeDef:
         """
-        Adds a specified number of users to a channel.
+        Adds a specified number of users and bots to a channel.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.batch_create_channel_membership)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#batch_create_channel_membership)
         """
     def can_paginate(self, operation_name: str) -> bool:
         """
         Check if an operation can be paginated.
@@ -150,15 +156,15 @@
         *,
         CallbackId: str,
         ChannelArn: str,
         ChannelMessage: ChannelMessageCallbackTypeDef,
         DeleteResource: bool = ...
     ) -> ChannelFlowCallbackResponseTypeDef:
         """
-        Calls back Chime SDK Messaging with a processing response message.
+        Calls back Amazon Chime SDK messaging with a processing response message.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.channel_flow_callback)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#channel_flow_callback)
         """
     async def close(self) -> None:
         """
         Closes underlying endpoint connections.
@@ -176,15 +182,16 @@
         Mode: ChannelModeType = ...,
         Privacy: ChannelPrivacyType = ...,
         Metadata: str = ...,
         Tags: Sequence[TagTypeDef] = ...,
         ChannelId: str = ...,
         MemberArns: Sequence[str] = ...,
         ModeratorArns: Sequence[str] = ...,
-        ElasticChannelConfiguration: ElasticChannelConfigurationTypeDef = ...
+        ElasticChannelConfiguration: ElasticChannelConfigurationTypeDef = ...,
+        ExpirationSettings: ExpirationSettingsTypeDef = ...
     ) -> CreateChannelResponseTypeDef:
         """
         Creates a channel to which you can add users and send messages.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.create_channel)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#create_channel)
         """
@@ -218,43 +225,43 @@
         ChannelArn: str,
         MemberArn: str,
         Type: ChannelMembershipTypeType,
         ChimeBearer: str,
         SubChannelId: str = ...
     ) -> CreateChannelMembershipResponseTypeDef:
         """
-        Adds a user to a channel.
+        Adds a member to a channel.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.create_channel_membership)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#create_channel_membership)
         """
     async def create_channel_moderator(
         self, *, ChannelArn: str, ChannelModeratorArn: str, ChimeBearer: str
     ) -> CreateChannelModeratorResponseTypeDef:
         """
         Creates a new `ChannelModerator`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.create_channel_moderator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#create_channel_moderator)
         """
     async def delete_channel(
-        self, *, ChannelArn: str, ChimeBearer: str, SubChannelId: str = ...
+        self, *, ChannelArn: str, ChimeBearer: str
     ) -> EmptyResponseMetadataTypeDef:
         """
         Immediately makes a channel and its memberships inaccessible and marks them for
         deletion.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.delete_channel)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#delete_channel)
         """
     async def delete_channel_ban(
         self, *, ChannelArn: str, MemberArn: str, ChimeBearer: str
     ) -> EmptyResponseMetadataTypeDef:
         """
-        Removes a user from a channel's ban list.
+        Removes a member from a channel's ban list.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.delete_channel_ban)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#delete_channel_ban)
         """
     async def delete_channel_flow(self, *, ChannelFlowArn: str) -> EmptyResponseMetadataTypeDef:
         """
         Deletes a channel flow, an irreversible process.
@@ -285,19 +292,28 @@
     ) -> EmptyResponseMetadataTypeDef:
         """
         Deletes a channel moderator.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.delete_channel_moderator)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#delete_channel_moderator)
         """
+    async def delete_messaging_streaming_configurations(
+        self, *, AppInstanceArn: str
+    ) -> EmptyResponseMetadataTypeDef:
+        """
+        Deletes the streaming configurations for an `AppInstance`.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.delete_messaging_streaming_configurations)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#delete_messaging_streaming_configurations)
+        """
     async def describe_channel(
         self, *, ChannelArn: str, ChimeBearer: str
     ) -> DescribeChannelResponseTypeDef:
         """
-        Returns the full details of a channel in an Amazon Chime `AppInstance` .
+        Returns the full details of a channel in an Amazon Chime `AppInstance`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.describe_channel)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#describe_channel)
         """
     async def describe_channel_ban(
         self, *, ChannelArn: str, MemberArn: str, ChimeBearer: str
     ) -> DescribeChannelBanResponseTypeDef:
@@ -326,25 +342,25 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#describe_channel_membership)
         """
     async def describe_channel_membership_for_app_instance_user(
         self, *, ChannelArn: str, AppInstanceUserArn: str, ChimeBearer: str
     ) -> DescribeChannelMembershipForAppInstanceUserResponseTypeDef:
         """
         Returns the details of a channel based on the membership of the specified
-        `AppInstanceUser` .
+        `AppInstanceUser` or `AppInstanceBot`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.describe_channel_membership_for_app_instance_user)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#describe_channel_membership_for_app_instance_user)
         """
     async def describe_channel_moderated_by_app_instance_user(
         self, *, ChannelArn: str, AppInstanceUserArn: str, ChimeBearer: str
     ) -> DescribeChannelModeratedByAppInstanceUserResponseTypeDef:
         """
         Returns the full details of a channel moderated by the specified
-        `AppInstanceUser` .
+        `AppInstanceUser` or `AppInstanceBot`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.describe_channel_moderated_by_app_instance_user)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#describe_channel_moderated_by_app_instance_user)
         """
     async def describe_channel_moderator(
         self, *, ChannelArn: str, ChannelModeratorArn: str, ChimeBearer: str
     ) -> DescribeChannelModeratorResponseTypeDef:
@@ -376,16 +392,16 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.generate_presigned_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#generate_presigned_url)
         """
     async def get_channel_membership_preferences(
         self, *, ChannelArn: str, MemberArn: str, ChimeBearer: str
     ) -> GetChannelMembershipPreferencesResponseTypeDef:
         """
-        Gets the membership preferences of an `AppInstanceUser` for the specified
-        channel.
+        Gets the membership preferences of an `AppInstanceUser` or `AppInstanceBot` for
+        the specified channel.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.get_channel_membership_preferences)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#get_channel_membership_preferences)
         """
     async def get_channel_message(
         self, *, ChannelArn: str, MessageId: str, ChimeBearer: str, SubChannelId: str = ...
     ) -> GetChannelMessageResponseTypeDef:
@@ -407,19 +423,28 @@
     async def get_messaging_session_endpoint(self) -> GetMessagingSessionEndpointResponseTypeDef:
         """
         The details of the endpoint for the messaging session.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.get_messaging_session_endpoint)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#get_messaging_session_endpoint)
         """
+    async def get_messaging_streaming_configurations(
+        self, *, AppInstanceArn: str
+    ) -> GetMessagingStreamingConfigurationsResponseTypeDef:
+        """
+        Retrieves the data streaming configuration for an `AppInstance`.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.get_messaging_streaming_configurations)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#get_messaging_streaming_configurations)
+        """
     async def list_channel_bans(
         self, *, ChannelArn: str, ChimeBearer: str, MaxResults: int = ..., NextToken: str = ...
     ) -> ListChannelBansResponseTypeDef:
         """
-        Lists all the users banned from a particular channel.
+        Lists all the users and bots banned from a particular channel.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.list_channel_bans)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#list_channel_bans)
         """
     async def list_channel_flows(
         self, *, AppInstanceArn: str, MaxResults: int = ..., NextToken: str = ...
     ) -> ListChannelFlowsResponseTypeDef:
@@ -450,15 +475,15 @@
         *,
         ChimeBearer: str,
         AppInstanceUserArn: str = ...,
         MaxResults: int = ...,
         NextToken: str = ...
     ) -> ListChannelMembershipsForAppInstanceUserResponseTypeDef:
         """
-        Lists all channels that a particular `AppInstanceUser` is a part of.
+        Lists all channels that an `AppInstanceUser` or `AppInstanceBot` is a part of.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.list_channel_memberships_for_app_instance_user)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#list_channel_memberships_for_app_instance_user)
         """
     async def list_channel_messages(
         self,
         *,
@@ -515,15 +540,15 @@
         *,
         ChimeBearer: str,
         AppInstanceUserArn: str = ...,
         MaxResults: int = ...,
         NextToken: str = ...
     ) -> ListChannelsModeratedByAppInstanceUserResponseTypeDef:
         """
-        A list of the channels moderated by an `AppInstanceUser` .
+        A list of the channels moderated by an `AppInstanceUser`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.list_channels_moderated_by_app_instance_user)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#list_channels_moderated_by_app_instance_user)
         """
     async def list_sub_channels(
         self, *, ChannelArn: str, ChimeBearer: str, MaxResults: int = ..., NextToken: str = ...
     ) -> ListSubChannelsResponseTypeDef:
@@ -538,29 +563,54 @@
     ) -> ListTagsForResourceResponseTypeDef:
         """
         Lists the tags applied to an Amazon Chime SDK messaging resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#list_tags_for_resource)
         """
+    async def put_channel_expiration_settings(
+        self,
+        *,
+        ChannelArn: str,
+        ChimeBearer: str = ...,
+        ExpirationSettings: ExpirationSettingsTypeDef = ...
+    ) -> PutChannelExpirationSettingsResponseTypeDef:
+        """
+        Sets the number of days before the channel is automatically deleted.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.put_channel_expiration_settings)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#put_channel_expiration_settings)
+        """
     async def put_channel_membership_preferences(
         self,
         *,
         ChannelArn: str,
         MemberArn: str,
         ChimeBearer: str,
         Preferences: ChannelMembershipPreferencesTypeDef
     ) -> PutChannelMembershipPreferencesResponseTypeDef:
         """
-        Sets the membership preferences of an `AppInstanceUser` for the specified
-        channel.
+        Sets the membership preferences of an `AppInstanceUser` or `AppInstanceBot` for
+        the specified channel.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.put_channel_membership_preferences)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#put_channel_membership_preferences)
         """
+    async def put_messaging_streaming_configurations(
+        self,
+        *,
+        AppInstanceArn: str,
+        StreamingConfigurations: Sequence[StreamingConfigurationTypeDef]
+    ) -> PutMessagingStreamingConfigurationsResponseTypeDef:
+        """
+        Sets the data streaming configuration for an `AppInstance`.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.put_messaging_streaming_configurations)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#put_messaging_streaming_configurations)
+        """
     async def redact_channel_message(
         self, *, ChannelArn: str, MessageId: str, ChimeBearer: str, SubChannelId: str = ...
     ) -> RedactChannelMessageResponseTypeDef:
         """
         Redacts message content, but not metadata.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.redact_channel_message)
@@ -571,15 +621,15 @@
         *,
         Fields: Sequence[SearchFieldTypeDef],
         ChimeBearer: str = ...,
         MaxResults: int = ...,
         NextToken: str = ...
     ) -> SearchChannelsResponseTypeDef:
         """
-        Allows `ChimeBearer` to search channels by channel members.
+        Allows the `ChimeBearer` to search channels by channel members.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.search_channels)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#search_channels)
         """
     async def send_channel_message(
         self,
         *,
@@ -588,15 +638,17 @@
         Type: ChannelMessageTypeType,
         Persistence: ChannelMessagePersistenceTypeType,
         ClientRequestToken: str,
         ChimeBearer: str,
         Metadata: str = ...,
         PushNotification: PushNotificationConfigurationTypeDef = ...,
         MessageAttributes: Mapping[str, MessageAttributeValueTypeDef] = ...,
-        SubChannelId: str = ...
+        SubChannelId: str = ...,
+        ContentType: str = ...,
+        Target: Sequence[TargetTypeDef] = ...
     ) -> SendChannelMessageResponseTypeDef:
         """
         Sends a message to a particular channel that the member is a part of.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.send_channel_message)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#send_channel_message)
         """
@@ -644,27 +696,28 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#update_channel_flow)
         """
     async def update_channel_message(
         self,
         *,
         ChannelArn: str,
         MessageId: str,
+        Content: str,
         ChimeBearer: str,
-        Content: str = ...,
         Metadata: str = ...,
-        SubChannelId: str = ...
+        SubChannelId: str = ...,
+        ContentType: str = ...
     ) -> UpdateChannelMessageResponseTypeDef:
         """
         Updates the content of a message.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.update_channel_message)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#update_channel_message)
         """
     async def update_channel_read_marker(
-        self, *, ChannelArn: str, ChimeBearer: str, SubChannelId: str = ...
+        self, *, ChannelArn: str, ChimeBearer: str
     ) -> UpdateChannelReadMarkerResponseTypeDef:
         """
         The details of the time when a user last read messages in a channel.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime-sdk-messaging.html#ChimeSDKMessaging.Client.update_channel_read_marker)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime_sdk_messaging/client/#update_channel_read_marker)
         """
```

### Comparing `types-aiobotocore-chime-sdk-messaging-2.5.0.post1/types_aiobotocore_chime_sdk_messaging/literals.py` & `types-aiobotocore-chime-sdk-messaging-2.5.1/types_aiobotocore_chime_sdk_messaging/literals.py`

 * *Files 3% similar despite different names*

```diff
@@ -24,16 +24,18 @@
     "ChannelMembershipTypeType",
     "ChannelMessagePersistenceTypeType",
     "ChannelMessageStatusType",
     "ChannelMessageTypeType",
     "ChannelModeType",
     "ChannelPrivacyType",
     "ErrorCodeType",
+    "ExpirationCriterionType",
     "FallbackActionType",
     "InvocationTypeType",
+    "MessagingDataTypeType",
     "PushNotificationTypeType",
     "SearchFieldKeyType",
     "SearchFieldOperatorType",
     "SortOrderType",
     "ChimeSDKMessagingServiceName",
     "ServiceName",
     "ResourceServiceName",
@@ -61,16 +63,18 @@
     "ServiceUnavailable",
     "Throttled",
     "Throttling",
     "Unauthorized",
     "Unprocessable",
     "VoiceConnectorGroupAssociationsExist",
 ]
+ExpirationCriterionType = Literal["CREATED_TIMESTAMP", "LAST_MESSAGE_TIMESTAMP"]
 FallbackActionType = Literal["ABORT", "CONTINUE"]
 InvocationTypeType = Literal["ASYNC"]
+MessagingDataTypeType = Literal["Channel", "ChannelMessage"]
 PushNotificationTypeType = Literal["DEFAULT", "VOIP"]
 SearchFieldKeyType = Literal["MEMBERS"]
 SearchFieldOperatorType = Literal["EQUALS", "INCLUDES"]
 SortOrderType = Literal["ASCENDING", "DESCENDING"]
 ChimeSDKMessagingServiceName = Literal["chime-sdk-messaging"]
 ServiceName = Literal[
     "accessanalyzer",
@@ -130,14 +134,15 @@
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
@@ -216,14 +221,15 @@
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
@@ -234,14 +240,15 @@
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
@@ -277,14 +284,15 @@
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
@@ -303,16 +311,19 @@
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
@@ -396,15 +407,17 @@
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

### Comparing `types-aiobotocore-chime-sdk-messaging-2.5.0.post1/types_aiobotocore_chime_sdk_messaging/literals.pyi` & `types-aiobotocore-chime-sdk-messaging-2.5.1/types_aiobotocore_chime_sdk_messaging/literals.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -23,16 +23,18 @@
     "ChannelMembershipTypeType",
     "ChannelMessagePersistenceTypeType",
     "ChannelMessageStatusType",
     "ChannelMessageTypeType",
     "ChannelModeType",
     "ChannelPrivacyType",
     "ErrorCodeType",
+    "ExpirationCriterionType",
     "FallbackActionType",
     "InvocationTypeType",
+    "MessagingDataTypeType",
     "PushNotificationTypeType",
     "SearchFieldKeyType",
     "SearchFieldOperatorType",
     "SortOrderType",
     "ChimeSDKMessagingServiceName",
     "ServiceName",
     "ResourceServiceName",
@@ -59,16 +61,18 @@
     "ServiceUnavailable",
     "Throttled",
     "Throttling",
     "Unauthorized",
     "Unprocessable",
     "VoiceConnectorGroupAssociationsExist",
 ]
+ExpirationCriterionType = Literal["CREATED_TIMESTAMP", "LAST_MESSAGE_TIMESTAMP"]
 FallbackActionType = Literal["ABORT", "CONTINUE"]
 InvocationTypeType = Literal["ASYNC"]
+MessagingDataTypeType = Literal["Channel", "ChannelMessage"]
 PushNotificationTypeType = Literal["DEFAULT", "VOIP"]
 SearchFieldKeyType = Literal["MEMBERS"]
 SearchFieldOperatorType = Literal["EQUALS", "INCLUDES"]
 SortOrderType = Literal["ASCENDING", "DESCENDING"]
 ChimeSDKMessagingServiceName = Literal["chime-sdk-messaging"]
 ServiceName = Literal[
     "accessanalyzer",
@@ -128,14 +132,15 @@
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
@@ -214,14 +219,15 @@
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
@@ -232,14 +238,15 @@
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
@@ -275,14 +282,15 @@
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
@@ -301,16 +309,19 @@
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
@@ -394,15 +405,17 @@
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

### Comparing `types-aiobotocore-chime-sdk-messaging-2.5.0.post1/types_aiobotocore_chime_sdk_messaging/type_defs.py` & `types-aiobotocore-chime-sdk-messaging-2.5.1/types_aiobotocore_chime_sdk_messaging/type_defs.py`

 * *Files 7% similar despite different names*

```diff
@@ -20,15 +20,17 @@
     ChannelMembershipTypeType,
     ChannelMessagePersistenceTypeType,
     ChannelMessageStatusType,
     ChannelMessageTypeType,
     ChannelModeType,
     ChannelPrivacyType,
     ErrorCodeType,
+    ExpirationCriterionType,
     FallbackActionType,
+    MessagingDataTypeType,
     PushNotificationTypeType,
     SearchFieldOperatorType,
     SortOrderType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
@@ -42,99 +44,109 @@
 
 __all__ = (
     "AppInstanceUserMembershipSummaryTypeDef",
     "AssociateChannelFlowRequestRequestTypeDef",
     "IdentityTypeDef",
     "BatchCreateChannelMembershipErrorTypeDef",
     "BatchCreateChannelMembershipRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "ChannelAssociatedWithFlowSummaryTypeDef",
+    "ChannelFlowCallbackResponseTypeDef",
     "ChannelSummaryTypeDef",
     "PushNotificationPreferencesTypeDef",
     "MessageAttributeValueTypeDef",
     "PushNotificationConfigurationTypeDef",
     "ChannelMessageStatusStructureTypeDef",
+    "TargetTypeDef",
     "ElasticChannelConfigurationTypeDef",
+    "ExpirationSettingsTypeDef",
     "CreateChannelBanRequestRequestTypeDef",
     "TagTypeDef",
+    "CreateChannelFlowResponseTypeDef",
     "CreateChannelMembershipRequestRequestTypeDef",
     "CreateChannelModeratorRequestRequestTypeDef",
+    "CreateChannelResponseTypeDef",
     "DeleteChannelBanRequestRequestTypeDef",
     "DeleteChannelFlowRequestRequestTypeDef",
     "DeleteChannelMembershipRequestRequestTypeDef",
     "DeleteChannelMessageRequestRequestTypeDef",
     "DeleteChannelModeratorRequestRequestTypeDef",
     "DeleteChannelRequestRequestTypeDef",
+    "DeleteMessagingStreamingConfigurationsRequestRequestTypeDef",
     "DescribeChannelBanRequestRequestTypeDef",
     "DescribeChannelFlowRequestRequestTypeDef",
     "DescribeChannelMembershipForAppInstanceUserRequestRequestTypeDef",
     "DescribeChannelMembershipRequestRequestTypeDef",
     "DescribeChannelModeratedByAppInstanceUserRequestRequestTypeDef",
     "DescribeChannelModeratorRequestRequestTypeDef",
     "DescribeChannelRequestRequestTypeDef",
     "DisassociateChannelFlowRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetChannelMembershipPreferencesRequestRequestTypeDef",
     "GetChannelMessageRequestRequestTypeDef",
     "GetChannelMessageStatusRequestRequestTypeDef",
     "MessagingSessionEndpointTypeDef",
+    "GetMessagingStreamingConfigurationsRequestRequestTypeDef",
+    "StreamingConfigurationTypeDef",
     "LambdaConfigurationTypeDef",
     "ListChannelBansRequestRequestTypeDef",
     "ListChannelFlowsRequestRequestTypeDef",
     "ListChannelMembershipsForAppInstanceUserRequestRequestTypeDef",
     "ListChannelMembershipsRequestRequestTypeDef",
     "ListChannelMessagesRequestRequestTypeDef",
     "ListChannelModeratorsRequestRequestTypeDef",
     "ListChannelsAssociatedWithChannelFlowRequestRequestTypeDef",
     "ListChannelsModeratedByAppInstanceUserRequestRequestTypeDef",
     "ListChannelsRequestRequestTypeDef",
     "ListSubChannelsRequestRequestTypeDef",
     "SubChannelSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "RedactChannelMessageRequestRequestTypeDef",
+    "RedactChannelMessageResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "SearchFieldTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "UpdateChannelFlowResponseTypeDef",
     "UpdateChannelMessageRequestRequestTypeDef",
     "UpdateChannelReadMarkerRequestRequestTypeDef",
+    "UpdateChannelReadMarkerResponseTypeDef",
     "UpdateChannelRequestRequestTypeDef",
+    "UpdateChannelResponseTypeDef",
     "BatchChannelMembershipsTypeDef",
     "ChannelBanSummaryTypeDef",
     "ChannelBanTypeDef",
     "ChannelMembershipSummaryTypeDef",
     "ChannelMembershipTypeDef",
     "ChannelModeratorSummaryTypeDef",
     "ChannelModeratorTypeDef",
-    "ChannelFlowCallbackResponseTypeDef",
     "CreateChannelBanResponseTypeDef",
-    "CreateChannelFlowResponseTypeDef",
     "CreateChannelMembershipResponseTypeDef",
     "CreateChannelModeratorResponseTypeDef",
-    "CreateChannelResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "RedactChannelMessageResponseTypeDef",
-    "UpdateChannelFlowResponseTypeDef",
-    "UpdateChannelReadMarkerResponseTypeDef",
-    "UpdateChannelResponseTypeDef",
     "ListChannelsAssociatedWithChannelFlowResponseTypeDef",
     "ChannelMembershipForAppInstanceUserSummaryTypeDef",
     "ChannelModeratedByAppInstanceUserSummaryTypeDef",
     "ListChannelsResponseTypeDef",
     "SearchChannelsResponseTypeDef",
     "ChannelMembershipPreferencesTypeDef",
     "ChannelMessageCallbackTypeDef",
-    "SendChannelMessageRequestRequestTypeDef",
-    "ChannelMessageSummaryTypeDef",
-    "ChannelMessageTypeDef",
     "GetChannelMessageStatusResponseTypeDef",
     "SendChannelMessageResponseTypeDef",
     "UpdateChannelMessageResponseTypeDef",
+    "ChannelMessageSummaryTypeDef",
+    "ChannelMessageTypeDef",
+    "SendChannelMessageRequestRequestTypeDef",
     "ChannelTypeDef",
+    "PutChannelExpirationSettingsRequestRequestTypeDef",
+    "PutChannelExpirationSettingsResponseTypeDef",
     "CreateChannelRequestRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "GetMessagingSessionEndpointResponseTypeDef",
+    "GetMessagingStreamingConfigurationsResponseTypeDef",
+    "PutMessagingStreamingConfigurationsRequestRequestTypeDef",
+    "PutMessagingStreamingConfigurationsResponseTypeDef",
     "ProcessorConfigurationTypeDef",
     "ListSubChannelsResponseTypeDef",
     "SearchChannelsRequestRequestTypeDef",
     "BatchCreateChannelMembershipResponseTypeDef",
     "ListChannelBansResponseTypeDef",
     "DescribeChannelBanResponseTypeDef",
     "ListChannelMembershipsResponseTypeDef",
@@ -220,37 +232,35 @@
 class BatchCreateChannelMembershipRequestRequestTypeDef(
     _RequiredBatchCreateChannelMembershipRequestRequestTypeDef,
     _OptionalBatchCreateChannelMembershipRequestRequestTypeDef,
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
-
 ChannelAssociatedWithFlowSummaryTypeDef = TypedDict(
     "ChannelAssociatedWithFlowSummaryTypeDef",
     {
         "Name": str,
         "ChannelArn": str,
         "Mode": ChannelModeType,
         "Privacy": ChannelPrivacyType,
         "Metadata": str,
     },
     total=False,
 )
 
+ChannelFlowCallbackResponseTypeDef = TypedDict(
+    "ChannelFlowCallbackResponseTypeDef",
+    {
+        "ChannelArn": str,
+        "CallbackId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ChannelSummaryTypeDef = TypedDict(
     "ChannelSummaryTypeDef",
     {
         "Name": str,
         "ChannelArn": str,
         "Mode": ChannelModeType,
         "Privacy": ChannelPrivacyType,
@@ -304,23 +314,39 @@
     {
         "Value": ChannelMessageStatusType,
         "Detail": str,
     },
     total=False,
 )
 
+TargetTypeDef = TypedDict(
+    "TargetTypeDef",
+    {
+        "MemberArn": str,
+    },
+    total=False,
+)
+
 ElasticChannelConfigurationTypeDef = TypedDict(
     "ElasticChannelConfigurationTypeDef",
     {
         "MaximumSubChannels": int,
         "TargetMembershipsPerSubChannel": int,
         "MinimumMembershipPercentage": int,
     },
 )
 
+ExpirationSettingsTypeDef = TypedDict(
+    "ExpirationSettingsTypeDef",
+    {
+        "ExpirationDays": int,
+        "ExpirationCriterion": ExpirationCriterionType,
+    },
+)
+
 CreateChannelBanRequestRequestTypeDef = TypedDict(
     "CreateChannelBanRequestRequestTypeDef",
     {
         "ChannelArn": str,
         "MemberArn": str,
         "ChimeBearer": str,
     },
@@ -330,14 +356,22 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
+CreateChannelFlowResponseTypeDef = TypedDict(
+    "CreateChannelFlowResponseTypeDef",
+    {
+        "ChannelFlowArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateChannelMembershipRequestRequestTypeDef = TypedDict(
     "_RequiredCreateChannelMembershipRequestRequestTypeDef",
     {
         "ChannelArn": str,
         "MemberArn": str,
         "Type": ChannelMembershipTypeType,
         "ChimeBearer": str,
@@ -364,14 +398,22 @@
     {
         "ChannelArn": str,
         "ChannelModeratorArn": str,
         "ChimeBearer": str,
     },
 )
 
+CreateChannelResponseTypeDef = TypedDict(
+    "CreateChannelResponseTypeDef",
+    {
+        "ChannelArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteChannelBanRequestRequestTypeDef = TypedDict(
     "DeleteChannelBanRequestRequestTypeDef",
     {
         "ChannelArn": str,
         "MemberArn": str,
         "ChimeBearer": str,
     },
@@ -437,36 +479,29 @@
     {
         "ChannelArn": str,
         "ChannelModeratorArn": str,
         "ChimeBearer": str,
     },
 )
 
-_RequiredDeleteChannelRequestRequestTypeDef = TypedDict(
-    "_RequiredDeleteChannelRequestRequestTypeDef",
+DeleteChannelRequestRequestTypeDef = TypedDict(
+    "DeleteChannelRequestRequestTypeDef",
     {
         "ChannelArn": str,
         "ChimeBearer": str,
     },
 )
-_OptionalDeleteChannelRequestRequestTypeDef = TypedDict(
-    "_OptionalDeleteChannelRequestRequestTypeDef",
+
+DeleteMessagingStreamingConfigurationsRequestRequestTypeDef = TypedDict(
+    "DeleteMessagingStreamingConfigurationsRequestRequestTypeDef",
     {
-        "SubChannelId": str,
+        "AppInstanceArn": str,
     },
-    total=False,
 )
 
-
-class DeleteChannelRequestRequestTypeDef(
-    _RequiredDeleteChannelRequestRequestTypeDef, _OptionalDeleteChannelRequestRequestTypeDef
-):
-    pass
-
-
 DescribeChannelBanRequestRequestTypeDef = TypedDict(
     "DescribeChannelBanRequestRequestTypeDef",
     {
         "ChannelArn": str,
         "MemberArn": str,
         "ChimeBearer": str,
     },
@@ -543,14 +578,21 @@
     {
         "ChannelArn": str,
         "ChannelFlowArn": str,
         "ChimeBearer": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetChannelMembershipPreferencesRequestRequestTypeDef = TypedDict(
     "GetChannelMembershipPreferencesRequestRequestTypeDef",
     {
         "ChannelArn": str,
         "MemberArn": str,
         "ChimeBearer": str,
     },
@@ -607,14 +649,29 @@
     "MessagingSessionEndpointTypeDef",
     {
         "Url": str,
     },
     total=False,
 )
 
+GetMessagingStreamingConfigurationsRequestRequestTypeDef = TypedDict(
+    "GetMessagingStreamingConfigurationsRequestRequestTypeDef",
+    {
+        "AppInstanceArn": str,
+    },
+)
+
+StreamingConfigurationTypeDef = TypedDict(
+    "StreamingConfigurationTypeDef",
+    {
+        "DataType": MessagingDataTypeType,
+        "ResourceArn": str,
+    },
+)
+
 LambdaConfigurationTypeDef = TypedDict(
     "LambdaConfigurationTypeDef",
     {
         "ResourceArn": str,
         "InvocationType": Literal["ASYNC"],
     },
 )
@@ -896,14 +953,35 @@
 class RedactChannelMessageRequestRequestTypeDef(
     _RequiredRedactChannelMessageRequestRequestTypeDef,
     _OptionalRedactChannelMessageRequestRequestTypeDef,
 ):
     pass
 
 
+RedactChannelMessageResponseTypeDef = TypedDict(
+    "RedactChannelMessageResponseTypeDef",
+    {
+        "ChannelArn": str,
+        "MessageId": str,
+        "SubChannelId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
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
 SearchFieldTypeDef = TypedDict(
     "SearchFieldTypeDef",
     {
         "Key": Literal["MEMBERS"],
         "Values": Sequence[str],
         "Operator": SearchFieldOperatorType,
     },
@@ -913,63 +991,65 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
         "TagKeys": Sequence[str],
     },
 )
 
+UpdateChannelFlowResponseTypeDef = TypedDict(
+    "UpdateChannelFlowResponseTypeDef",
+    {
+        "ChannelFlowArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateChannelMessageRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateChannelMessageRequestRequestTypeDef",
     {
         "ChannelArn": str,
         "MessageId": str,
+        "Content": str,
         "ChimeBearer": str,
     },
 )
 _OptionalUpdateChannelMessageRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateChannelMessageRequestRequestTypeDef",
     {
-        "Content": str,
         "Metadata": str,
         "SubChannelId": str,
+        "ContentType": str,
     },
     total=False,
 )
 
 
 class UpdateChannelMessageRequestRequestTypeDef(
     _RequiredUpdateChannelMessageRequestRequestTypeDef,
     _OptionalUpdateChannelMessageRequestRequestTypeDef,
 ):
     pass
 
 
-_RequiredUpdateChannelReadMarkerRequestRequestTypeDef = TypedDict(
-    "_RequiredUpdateChannelReadMarkerRequestRequestTypeDef",
+UpdateChannelReadMarkerRequestRequestTypeDef = TypedDict(
+    "UpdateChannelReadMarkerRequestRequestTypeDef",
     {
         "ChannelArn": str,
         "ChimeBearer": str,
     },
 )
-_OptionalUpdateChannelReadMarkerRequestRequestTypeDef = TypedDict(
-    "_OptionalUpdateChannelReadMarkerRequestRequestTypeDef",
+
+UpdateChannelReadMarkerResponseTypeDef = TypedDict(
+    "UpdateChannelReadMarkerResponseTypeDef",
     {
-        "SubChannelId": str,
+        "ChannelArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-
-class UpdateChannelReadMarkerRequestRequestTypeDef(
-    _RequiredUpdateChannelReadMarkerRequestRequestTypeDef,
-    _OptionalUpdateChannelReadMarkerRequestRequestTypeDef,
-):
-    pass
-
-
 _RequiredUpdateChannelRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateChannelRequestRequestTypeDef",
     {
         "ChannelArn": str,
         "ChimeBearer": str,
     },
 )
@@ -986,14 +1066,22 @@
 
 class UpdateChannelRequestRequestTypeDef(
     _RequiredUpdateChannelRequestRequestTypeDef, _OptionalUpdateChannelRequestRequestTypeDef
 ):
     pass
 
 
+UpdateChannelResponseTypeDef = TypedDict(
+    "UpdateChannelResponseTypeDef",
+    {
+        "ChannelArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 BatchChannelMembershipsTypeDef = TypedDict(
     "BatchChannelMembershipsTypeDef",
     {
         "InvitedBy": IdentityTypeDef,
         "Type": ChannelMembershipTypeType,
         "Members": List[IdentityTypeDef],
         "ChannelArn": str,
@@ -1058,115 +1146,48 @@
         "ChannelArn": str,
         "CreatedTimestamp": datetime,
         "CreatedBy": IdentityTypeDef,
     },
     total=False,
 )
 
-ChannelFlowCallbackResponseTypeDef = TypedDict(
-    "ChannelFlowCallbackResponseTypeDef",
-    {
-        "ChannelArn": str,
-        "CallbackId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 CreateChannelBanResponseTypeDef = TypedDict(
     "CreateChannelBanResponseTypeDef",
     {
         "ChannelArn": str,
         "Member": IdentityTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateChannelFlowResponseTypeDef = TypedDict(
-    "CreateChannelFlowResponseTypeDef",
-    {
-        "ChannelFlowArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateChannelMembershipResponseTypeDef = TypedDict(
     "CreateChannelMembershipResponseTypeDef",
     {
         "ChannelArn": str,
         "Member": IdentityTypeDef,
         "SubChannelId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateChannelModeratorResponseTypeDef = TypedDict(
     "CreateChannelModeratorResponseTypeDef",
     {
         "ChannelArn": str,
         "ChannelModerator": IdentityTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateChannelResponseTypeDef = TypedDict(
-    "CreateChannelResponseTypeDef",
-    {
-        "ChannelArn": str,
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
-RedactChannelMessageResponseTypeDef = TypedDict(
-    "RedactChannelMessageResponseTypeDef",
-    {
-        "ChannelArn": str,
-        "MessageId": str,
-        "SubChannelId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateChannelFlowResponseTypeDef = TypedDict(
-    "UpdateChannelFlowResponseTypeDef",
-    {
-        "ChannelFlowArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateChannelReadMarkerResponseTypeDef = TypedDict(
-    "UpdateChannelReadMarkerResponseTypeDef",
-    {
-        "ChannelArn": str,
-        "SubChannelId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateChannelResponseTypeDef = TypedDict(
-    "UpdateChannelResponseTypeDef",
-    {
-        "ChannelArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListChannelsAssociatedWithChannelFlowResponseTypeDef = TypedDict(
     "ListChannelsAssociatedWithChannelFlowResponseTypeDef",
     {
         "Channels": List[ChannelAssociatedWithFlowSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ChannelMembershipForAppInstanceUserSummaryTypeDef = TypedDict(
     "ChannelMembershipForAppInstanceUserSummaryTypeDef",
     {
         "ChannelSummary": ChannelSummaryTypeDef,
@@ -1184,24 +1205,24 @@
 )
 
 ListChannelsResponseTypeDef = TypedDict(
     "ListChannelsResponseTypeDef",
     {
         "Channels": List[ChannelSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SearchChannelsResponseTypeDef = TypedDict(
     "SearchChannelsResponseTypeDef",
     {
         "Channels": List[ChannelSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ChannelMembershipPreferencesTypeDef = TypedDict(
     "ChannelMembershipPreferencesTypeDef",
     {
         "PushNotifications": PushNotificationPreferencesTypeDef,
@@ -1219,54 +1240,55 @@
     "_OptionalChannelMessageCallbackTypeDef",
     {
         "Content": str,
         "Metadata": str,
         "PushNotification": PushNotificationConfigurationTypeDef,
         "MessageAttributes": Mapping[str, MessageAttributeValueTypeDef],
         "SubChannelId": str,
+        "ContentType": str,
     },
     total=False,
 )
 
 
 class ChannelMessageCallbackTypeDef(
     _RequiredChannelMessageCallbackTypeDef, _OptionalChannelMessageCallbackTypeDef
 ):
     pass
 
 
-_RequiredSendChannelMessageRequestRequestTypeDef = TypedDict(
-    "_RequiredSendChannelMessageRequestRequestTypeDef",
+GetChannelMessageStatusResponseTypeDef = TypedDict(
+    "GetChannelMessageStatusResponseTypeDef",
     {
-        "ChannelArn": str,
-        "Content": str,
-        "Type": ChannelMessageTypeType,
-        "Persistence": ChannelMessagePersistenceTypeType,
-        "ClientRequestToken": str,
-        "ChimeBearer": str,
+        "Status": ChannelMessageStatusStructureTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalSendChannelMessageRequestRequestTypeDef = TypedDict(
-    "_OptionalSendChannelMessageRequestRequestTypeDef",
+
+SendChannelMessageResponseTypeDef = TypedDict(
+    "SendChannelMessageResponseTypeDef",
     {
-        "Metadata": str,
-        "PushNotification": PushNotificationConfigurationTypeDef,
-        "MessageAttributes": Mapping[str, MessageAttributeValueTypeDef],
+        "ChannelArn": str,
+        "MessageId": str,
+        "Status": ChannelMessageStatusStructureTypeDef,
         "SubChannelId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-
-class SendChannelMessageRequestRequestTypeDef(
-    _RequiredSendChannelMessageRequestRequestTypeDef,
-    _OptionalSendChannelMessageRequestRequestTypeDef,
-):
-    pass
-
+UpdateChannelMessageResponseTypeDef = TypedDict(
+    "UpdateChannelMessageResponseTypeDef",
+    {
+        "ChannelArn": str,
+        "MessageId": str,
+        "Status": ChannelMessageStatusStructureTypeDef,
+        "SubChannelId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 ChannelMessageSummaryTypeDef = TypedDict(
     "ChannelMessageSummaryTypeDef",
     {
         "MessageId": str,
         "Content": str,
         "Metadata": str,
@@ -1274,14 +1296,16 @@
         "CreatedTimestamp": datetime,
         "LastUpdatedTimestamp": datetime,
         "LastEditedTimestamp": datetime,
         "Sender": IdentityTypeDef,
         "Redacted": bool,
         "Status": ChannelMessageStatusStructureTypeDef,
         "MessageAttributes": Dict[str, MessageAttributeValueTypeDef],
+        "ContentType": str,
+        "Target": List[TargetTypeDef],
     },
     total=False,
 )
 
 ChannelMessageTypeDef = TypedDict(
     "ChannelMessageTypeDef",
     {
@@ -1295,66 +1319,103 @@
         "LastUpdatedTimestamp": datetime,
         "Sender": IdentityTypeDef,
         "Redacted": bool,
         "Persistence": ChannelMessagePersistenceTypeType,
         "Status": ChannelMessageStatusStructureTypeDef,
         "MessageAttributes": Dict[str, MessageAttributeValueTypeDef],
         "SubChannelId": str,
+        "ContentType": str,
+        "Target": List[TargetTypeDef],
     },
     total=False,
 )
 
-GetChannelMessageStatusResponseTypeDef = TypedDict(
-    "GetChannelMessageStatusResponseTypeDef",
-    {
-        "Status": ChannelMessageStatusStructureTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SendChannelMessageResponseTypeDef = TypedDict(
-    "SendChannelMessageResponseTypeDef",
+_RequiredSendChannelMessageRequestRequestTypeDef = TypedDict(
+    "_RequiredSendChannelMessageRequestRequestTypeDef",
     {
         "ChannelArn": str,
-        "MessageId": str,
-        "Status": ChannelMessageStatusStructureTypeDef,
-        "SubChannelId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Content": str,
+        "Type": ChannelMessageTypeType,
+        "Persistence": ChannelMessagePersistenceTypeType,
+        "ClientRequestToken": str,
+        "ChimeBearer": str,
     },
 )
-
-UpdateChannelMessageResponseTypeDef = TypedDict(
-    "UpdateChannelMessageResponseTypeDef",
+_OptionalSendChannelMessageRequestRequestTypeDef = TypedDict(
+    "_OptionalSendChannelMessageRequestRequestTypeDef",
     {
-        "ChannelArn": str,
-        "MessageId": str,
-        "Status": ChannelMessageStatusStructureTypeDef,
+        "Metadata": str,
+        "PushNotification": PushNotificationConfigurationTypeDef,
+        "MessageAttributes": Mapping[str, MessageAttributeValueTypeDef],
         "SubChannelId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ContentType": str,
+        "Target": Sequence[TargetTypeDef],
     },
+    total=False,
 )
 
+
+class SendChannelMessageRequestRequestTypeDef(
+    _RequiredSendChannelMessageRequestRequestTypeDef,
+    _OptionalSendChannelMessageRequestRequestTypeDef,
+):
+    pass
+
+
 ChannelTypeDef = TypedDict(
     "ChannelTypeDef",
     {
         "Name": str,
         "ChannelArn": str,
         "Mode": ChannelModeType,
         "Privacy": ChannelPrivacyType,
         "Metadata": str,
         "CreatedBy": IdentityTypeDef,
         "CreatedTimestamp": datetime,
         "LastMessageTimestamp": datetime,
         "LastUpdatedTimestamp": datetime,
         "ChannelFlowArn": str,
         "ElasticChannelConfiguration": ElasticChannelConfigurationTypeDef,
+        "ExpirationSettings": ExpirationSettingsTypeDef,
     },
     total=False,
 )
 
+_RequiredPutChannelExpirationSettingsRequestRequestTypeDef = TypedDict(
+    "_RequiredPutChannelExpirationSettingsRequestRequestTypeDef",
+    {
+        "ChannelArn": str,
+    },
+)
+_OptionalPutChannelExpirationSettingsRequestRequestTypeDef = TypedDict(
+    "_OptionalPutChannelExpirationSettingsRequestRequestTypeDef",
+    {
+        "ChimeBearer": str,
+        "ExpirationSettings": ExpirationSettingsTypeDef,
+    },
+    total=False,
+)
+
+
+class PutChannelExpirationSettingsRequestRequestTypeDef(
+    _RequiredPutChannelExpirationSettingsRequestRequestTypeDef,
+    _OptionalPutChannelExpirationSettingsRequestRequestTypeDef,
+):
+    pass
+
+
+PutChannelExpirationSettingsResponseTypeDef = TypedDict(
+    "PutChannelExpirationSettingsResponseTypeDef",
+    {
+        "ChannelArn": str,
+        "ExpirationSettings": ExpirationSettingsTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateChannelRequestRequestTypeDef = TypedDict(
     "_RequiredCreateChannelRequestRequestTypeDef",
     {
         "AppInstanceArn": str,
         "Name": str,
         "ClientRequestToken": str,
         "ChimeBearer": str,
@@ -1367,14 +1428,15 @@
         "Privacy": ChannelPrivacyType,
         "Metadata": str,
         "Tags": Sequence[TagTypeDef],
         "ChannelId": str,
         "MemberArns": Sequence[str],
         "ModeratorArns": Sequence[str],
         "ElasticChannelConfiguration": ElasticChannelConfigurationTypeDef,
+        "ExpirationSettings": ExpirationSettingsTypeDef,
     },
     total=False,
 )
 
 
 class CreateChannelRequestRequestTypeDef(
     _RequiredCreateChannelRequestRequestTypeDef, _OptionalCreateChannelRequestRequestTypeDef
@@ -1382,15 +1444,15 @@
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
         "ResourceARN": str,
@@ -1398,15 +1460,39 @@
     },
 )
 
 GetMessagingSessionEndpointResponseTypeDef = TypedDict(
     "GetMessagingSessionEndpointResponseTypeDef",
     {
         "Endpoint": MessagingSessionEndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetMessagingStreamingConfigurationsResponseTypeDef = TypedDict(
+    "GetMessagingStreamingConfigurationsResponseTypeDef",
+    {
+        "StreamingConfigurations": List[StreamingConfigurationTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+PutMessagingStreamingConfigurationsRequestRequestTypeDef = TypedDict(
+    "PutMessagingStreamingConfigurationsRequestRequestTypeDef",
+    {
+        "AppInstanceArn": str,
+        "StreamingConfigurations": Sequence[StreamingConfigurationTypeDef],
+    },
+)
+
+PutMessagingStreamingConfigurationsResponseTypeDef = TypedDict(
+    "PutMessagingStreamingConfigurationsResponseTypeDef",
+    {
+        "StreamingConfigurations": List[StreamingConfigurationTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ProcessorConfigurationTypeDef = TypedDict(
     "ProcessorConfigurationTypeDef",
     {
         "Lambda": LambdaConfigurationTypeDef,
@@ -1415,15 +1501,15 @@
 
 ListSubChannelsResponseTypeDef = TypedDict(
     "ListSubChannelsResponseTypeDef",
     {
         "ChannelArn": str,
         "SubChannels": List[SubChannelSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSearchChannelsRequestRequestTypeDef = TypedDict(
     "_RequiredSearchChannelsRequestRequestTypeDef",
     {
         "Fields": Sequence[SearchFieldTypeDef],
@@ -1447,113 +1533,113 @@
 
 
 BatchCreateChannelMembershipResponseTypeDef = TypedDict(
     "BatchCreateChannelMembershipResponseTypeDef",
     {
         "BatchChannelMemberships": BatchChannelMembershipsTypeDef,
         "Errors": List[BatchCreateChannelMembershipErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListChannelBansResponseTypeDef = TypedDict(
     "ListChannelBansResponseTypeDef",
     {
         "ChannelArn": str,
         "NextToken": str,
         "ChannelBans": List[ChannelBanSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeChannelBanResponseTypeDef = TypedDict(
     "DescribeChannelBanResponseTypeDef",
     {
         "ChannelBan": ChannelBanTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListChannelMembershipsResponseTypeDef = TypedDict(
     "ListChannelMembershipsResponseTypeDef",
     {
         "ChannelArn": str,
         "ChannelMemberships": List[ChannelMembershipSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeChannelMembershipResponseTypeDef = TypedDict(
     "DescribeChannelMembershipResponseTypeDef",
     {
         "ChannelMembership": ChannelMembershipTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListChannelModeratorsResponseTypeDef = TypedDict(
     "ListChannelModeratorsResponseTypeDef",
     {
         "ChannelArn": str,
         "NextToken": str,
         "ChannelModerators": List[ChannelModeratorSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeChannelModeratorResponseTypeDef = TypedDict(
     "DescribeChannelModeratorResponseTypeDef",
     {
         "ChannelModerator": ChannelModeratorTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeChannelMembershipForAppInstanceUserResponseTypeDef = TypedDict(
     "DescribeChannelMembershipForAppInstanceUserResponseTypeDef",
     {
         "ChannelMembership": ChannelMembershipForAppInstanceUserSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListChannelMembershipsForAppInstanceUserResponseTypeDef = TypedDict(
     "ListChannelMembershipsForAppInstanceUserResponseTypeDef",
     {
         "ChannelMemberships": List[ChannelMembershipForAppInstanceUserSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeChannelModeratedByAppInstanceUserResponseTypeDef = TypedDict(
     "DescribeChannelModeratedByAppInstanceUserResponseTypeDef",
     {
         "Channel": ChannelModeratedByAppInstanceUserSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListChannelsModeratedByAppInstanceUserResponseTypeDef = TypedDict(
     "ListChannelsModeratedByAppInstanceUserResponseTypeDef",
     {
         "Channels": List[ChannelModeratedByAppInstanceUserSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetChannelMembershipPreferencesResponseTypeDef = TypedDict(
     "GetChannelMembershipPreferencesResponseTypeDef",
     {
         "ChannelArn": str,
         "Member": IdentityTypeDef,
         "Preferences": ChannelMembershipPreferencesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutChannelMembershipPreferencesRequestRequestTypeDef = TypedDict(
     "PutChannelMembershipPreferencesRequestRequestTypeDef",
     {
         "ChannelArn": str,
@@ -1565,15 +1651,15 @@
 
 PutChannelMembershipPreferencesResponseTypeDef = TypedDict(
     "PutChannelMembershipPreferencesResponseTypeDef",
     {
         "ChannelArn": str,
         "Member": IdentityTypeDef,
         "Preferences": ChannelMembershipPreferencesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredChannelFlowCallbackRequestRequestTypeDef = TypedDict(
     "_RequiredChannelFlowCallbackRequestRequestTypeDef",
     {
         "CallbackId": str,
@@ -1600,31 +1686,31 @@
 ListChannelMessagesResponseTypeDef = TypedDict(
     "ListChannelMessagesResponseTypeDef",
     {
         "ChannelArn": str,
         "NextToken": str,
         "ChannelMessages": List[ChannelMessageSummaryTypeDef],
         "SubChannelId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetChannelMessageResponseTypeDef = TypedDict(
     "GetChannelMessageResponseTypeDef",
     {
         "ChannelMessage": ChannelMessageTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeChannelResponseTypeDef = TypedDict(
     "DescribeChannelResponseTypeDef",
     {
         "Channel": ChannelTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ProcessorTypeDef = TypedDict(
     "ProcessorTypeDef",
     {
         "Name": str,
@@ -1690,18 +1776,18 @@
 )
 
 ListChannelFlowsResponseTypeDef = TypedDict(
     "ListChannelFlowsResponseTypeDef",
     {
         "ChannelFlows": List[ChannelFlowSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeChannelFlowResponseTypeDef = TypedDict(
     "DescribeChannelFlowResponseTypeDef",
     {
         "ChannelFlow": ChannelFlowTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-chime-sdk-messaging-2.5.0.post1/types_aiobotocore_chime_sdk_messaging/type_defs.pyi` & `types-aiobotocore-chime-sdk-messaging-2.5.1/types_aiobotocore_chime_sdk_messaging/type_defs.pyi`

 * *Files 4% similar despite different names*

```diff
@@ -20,15 +20,17 @@
     ChannelMembershipTypeType,
     ChannelMessagePersistenceTypeType,
     ChannelMessageStatusType,
     ChannelMessageTypeType,
     ChannelModeType,
     ChannelPrivacyType,
     ErrorCodeType,
+    ExpirationCriterionType,
     FallbackActionType,
+    MessagingDataTypeType,
     PushNotificationTypeType,
     SearchFieldOperatorType,
     SortOrderType,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
@@ -41,99 +43,109 @@
 
 __all__ = (
     "AppInstanceUserMembershipSummaryTypeDef",
     "AssociateChannelFlowRequestRequestTypeDef",
     "IdentityTypeDef",
     "BatchCreateChannelMembershipErrorTypeDef",
     "BatchCreateChannelMembershipRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "ChannelAssociatedWithFlowSummaryTypeDef",
+    "ChannelFlowCallbackResponseTypeDef",
     "ChannelSummaryTypeDef",
     "PushNotificationPreferencesTypeDef",
     "MessageAttributeValueTypeDef",
     "PushNotificationConfigurationTypeDef",
     "ChannelMessageStatusStructureTypeDef",
+    "TargetTypeDef",
     "ElasticChannelConfigurationTypeDef",
+    "ExpirationSettingsTypeDef",
     "CreateChannelBanRequestRequestTypeDef",
     "TagTypeDef",
+    "CreateChannelFlowResponseTypeDef",
     "CreateChannelMembershipRequestRequestTypeDef",
     "CreateChannelModeratorRequestRequestTypeDef",
+    "CreateChannelResponseTypeDef",
     "DeleteChannelBanRequestRequestTypeDef",
     "DeleteChannelFlowRequestRequestTypeDef",
     "DeleteChannelMembershipRequestRequestTypeDef",
     "DeleteChannelMessageRequestRequestTypeDef",
     "DeleteChannelModeratorRequestRequestTypeDef",
     "DeleteChannelRequestRequestTypeDef",
+    "DeleteMessagingStreamingConfigurationsRequestRequestTypeDef",
     "DescribeChannelBanRequestRequestTypeDef",
     "DescribeChannelFlowRequestRequestTypeDef",
     "DescribeChannelMembershipForAppInstanceUserRequestRequestTypeDef",
     "DescribeChannelMembershipRequestRequestTypeDef",
     "DescribeChannelModeratedByAppInstanceUserRequestRequestTypeDef",
     "DescribeChannelModeratorRequestRequestTypeDef",
     "DescribeChannelRequestRequestTypeDef",
     "DisassociateChannelFlowRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetChannelMembershipPreferencesRequestRequestTypeDef",
     "GetChannelMessageRequestRequestTypeDef",
     "GetChannelMessageStatusRequestRequestTypeDef",
     "MessagingSessionEndpointTypeDef",
+    "GetMessagingStreamingConfigurationsRequestRequestTypeDef",
+    "StreamingConfigurationTypeDef",
     "LambdaConfigurationTypeDef",
     "ListChannelBansRequestRequestTypeDef",
     "ListChannelFlowsRequestRequestTypeDef",
     "ListChannelMembershipsForAppInstanceUserRequestRequestTypeDef",
     "ListChannelMembershipsRequestRequestTypeDef",
     "ListChannelMessagesRequestRequestTypeDef",
     "ListChannelModeratorsRequestRequestTypeDef",
     "ListChannelsAssociatedWithChannelFlowRequestRequestTypeDef",
     "ListChannelsModeratedByAppInstanceUserRequestRequestTypeDef",
     "ListChannelsRequestRequestTypeDef",
     "ListSubChannelsRequestRequestTypeDef",
     "SubChannelSummaryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "RedactChannelMessageRequestRequestTypeDef",
+    "RedactChannelMessageResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "SearchFieldTypeDef",
     "UntagResourceRequestRequestTypeDef",
+    "UpdateChannelFlowResponseTypeDef",
     "UpdateChannelMessageRequestRequestTypeDef",
     "UpdateChannelReadMarkerRequestRequestTypeDef",
+    "UpdateChannelReadMarkerResponseTypeDef",
     "UpdateChannelRequestRequestTypeDef",
+    "UpdateChannelResponseTypeDef",
     "BatchChannelMembershipsTypeDef",
     "ChannelBanSummaryTypeDef",
     "ChannelBanTypeDef",
     "ChannelMembershipSummaryTypeDef",
     "ChannelMembershipTypeDef",
     "ChannelModeratorSummaryTypeDef",
     "ChannelModeratorTypeDef",
-    "ChannelFlowCallbackResponseTypeDef",
     "CreateChannelBanResponseTypeDef",
-    "CreateChannelFlowResponseTypeDef",
     "CreateChannelMembershipResponseTypeDef",
     "CreateChannelModeratorResponseTypeDef",
-    "CreateChannelResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "RedactChannelMessageResponseTypeDef",
-    "UpdateChannelFlowResponseTypeDef",
-    "UpdateChannelReadMarkerResponseTypeDef",
-    "UpdateChannelResponseTypeDef",
     "ListChannelsAssociatedWithChannelFlowResponseTypeDef",
     "ChannelMembershipForAppInstanceUserSummaryTypeDef",
     "ChannelModeratedByAppInstanceUserSummaryTypeDef",
     "ListChannelsResponseTypeDef",
     "SearchChannelsResponseTypeDef",
     "ChannelMembershipPreferencesTypeDef",
     "ChannelMessageCallbackTypeDef",
-    "SendChannelMessageRequestRequestTypeDef",
-    "ChannelMessageSummaryTypeDef",
-    "ChannelMessageTypeDef",
     "GetChannelMessageStatusResponseTypeDef",
     "SendChannelMessageResponseTypeDef",
     "UpdateChannelMessageResponseTypeDef",
+    "ChannelMessageSummaryTypeDef",
+    "ChannelMessageTypeDef",
+    "SendChannelMessageRequestRequestTypeDef",
     "ChannelTypeDef",
+    "PutChannelExpirationSettingsRequestRequestTypeDef",
+    "PutChannelExpirationSettingsResponseTypeDef",
     "CreateChannelRequestRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "GetMessagingSessionEndpointResponseTypeDef",
+    "GetMessagingStreamingConfigurationsResponseTypeDef",
+    "PutMessagingStreamingConfigurationsRequestRequestTypeDef",
+    "PutMessagingStreamingConfigurationsResponseTypeDef",
     "ProcessorConfigurationTypeDef",
     "ListSubChannelsResponseTypeDef",
     "SearchChannelsRequestRequestTypeDef",
     "BatchCreateChannelMembershipResponseTypeDef",
     "ListChannelBansResponseTypeDef",
     "DescribeChannelBanResponseTypeDef",
     "ListChannelMembershipsResponseTypeDef",
@@ -217,37 +229,35 @@
 
 class BatchCreateChannelMembershipRequestRequestTypeDef(
     _RequiredBatchCreateChannelMembershipRequestRequestTypeDef,
     _OptionalBatchCreateChannelMembershipRequestRequestTypeDef,
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
-
 ChannelAssociatedWithFlowSummaryTypeDef = TypedDict(
     "ChannelAssociatedWithFlowSummaryTypeDef",
     {
         "Name": str,
         "ChannelArn": str,
         "Mode": ChannelModeType,
         "Privacy": ChannelPrivacyType,
         "Metadata": str,
     },
     total=False,
 )
 
+ChannelFlowCallbackResponseTypeDef = TypedDict(
+    "ChannelFlowCallbackResponseTypeDef",
+    {
+        "ChannelArn": str,
+        "CallbackId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ChannelSummaryTypeDef = TypedDict(
     "ChannelSummaryTypeDef",
     {
         "Name": str,
         "ChannelArn": str,
         "Mode": ChannelModeType,
         "Privacy": ChannelPrivacyType,
@@ -299,23 +309,39 @@
     {
         "Value": ChannelMessageStatusType,
         "Detail": str,
     },
     total=False,
 )
 
+TargetTypeDef = TypedDict(
+    "TargetTypeDef",
+    {
+        "MemberArn": str,
+    },
+    total=False,
+)
+
 ElasticChannelConfigurationTypeDef = TypedDict(
     "ElasticChannelConfigurationTypeDef",
     {
         "MaximumSubChannels": int,
         "TargetMembershipsPerSubChannel": int,
         "MinimumMembershipPercentage": int,
     },
 )
 
+ExpirationSettingsTypeDef = TypedDict(
+    "ExpirationSettingsTypeDef",
+    {
+        "ExpirationDays": int,
+        "ExpirationCriterion": ExpirationCriterionType,
+    },
+)
+
 CreateChannelBanRequestRequestTypeDef = TypedDict(
     "CreateChannelBanRequestRequestTypeDef",
     {
         "ChannelArn": str,
         "MemberArn": str,
         "ChimeBearer": str,
     },
@@ -325,14 +351,22 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
+CreateChannelFlowResponseTypeDef = TypedDict(
+    "CreateChannelFlowResponseTypeDef",
+    {
+        "ChannelFlowArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateChannelMembershipRequestRequestTypeDef = TypedDict(
     "_RequiredCreateChannelMembershipRequestRequestTypeDef",
     {
         "ChannelArn": str,
         "MemberArn": str,
         "Type": ChannelMembershipTypeType,
         "ChimeBearer": str,
@@ -357,14 +391,22 @@
     {
         "ChannelArn": str,
         "ChannelModeratorArn": str,
         "ChimeBearer": str,
     },
 )
 
+CreateChannelResponseTypeDef = TypedDict(
+    "CreateChannelResponseTypeDef",
+    {
+        "ChannelArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteChannelBanRequestRequestTypeDef = TypedDict(
     "DeleteChannelBanRequestRequestTypeDef",
     {
         "ChannelArn": str,
         "MemberArn": str,
         "ChimeBearer": str,
     },
@@ -426,34 +468,29 @@
     {
         "ChannelArn": str,
         "ChannelModeratorArn": str,
         "ChimeBearer": str,
     },
 )
 
-_RequiredDeleteChannelRequestRequestTypeDef = TypedDict(
-    "_RequiredDeleteChannelRequestRequestTypeDef",
+DeleteChannelRequestRequestTypeDef = TypedDict(
+    "DeleteChannelRequestRequestTypeDef",
     {
         "ChannelArn": str,
         "ChimeBearer": str,
     },
 )
-_OptionalDeleteChannelRequestRequestTypeDef = TypedDict(
-    "_OptionalDeleteChannelRequestRequestTypeDef",
+
+DeleteMessagingStreamingConfigurationsRequestRequestTypeDef = TypedDict(
+    "DeleteMessagingStreamingConfigurationsRequestRequestTypeDef",
     {
-        "SubChannelId": str,
+        "AppInstanceArn": str,
     },
-    total=False,
 )
 
-class DeleteChannelRequestRequestTypeDef(
-    _RequiredDeleteChannelRequestRequestTypeDef, _OptionalDeleteChannelRequestRequestTypeDef
-):
-    pass
-
 DescribeChannelBanRequestRequestTypeDef = TypedDict(
     "DescribeChannelBanRequestRequestTypeDef",
     {
         "ChannelArn": str,
         "MemberArn": str,
         "ChimeBearer": str,
     },
@@ -528,14 +565,21 @@
     {
         "ChannelArn": str,
         "ChannelFlowArn": str,
         "ChimeBearer": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetChannelMembershipPreferencesRequestRequestTypeDef = TypedDict(
     "GetChannelMembershipPreferencesRequestRequestTypeDef",
     {
         "ChannelArn": str,
         "MemberArn": str,
         "ChimeBearer": str,
     },
@@ -588,14 +632,29 @@
     "MessagingSessionEndpointTypeDef",
     {
         "Url": str,
     },
     total=False,
 )
 
+GetMessagingStreamingConfigurationsRequestRequestTypeDef = TypedDict(
+    "GetMessagingStreamingConfigurationsRequestRequestTypeDef",
+    {
+        "AppInstanceArn": str,
+    },
+)
+
+StreamingConfigurationTypeDef = TypedDict(
+    "StreamingConfigurationTypeDef",
+    {
+        "DataType": MessagingDataTypeType,
+        "ResourceArn": str,
+    },
+)
+
 LambdaConfigurationTypeDef = TypedDict(
     "LambdaConfigurationTypeDef",
     {
         "ResourceArn": str,
         "InvocationType": Literal["ASYNC"],
     },
 )
@@ -855,14 +914,35 @@
 
 class RedactChannelMessageRequestRequestTypeDef(
     _RequiredRedactChannelMessageRequestRequestTypeDef,
     _OptionalRedactChannelMessageRequestRequestTypeDef,
 ):
     pass
 
+RedactChannelMessageResponseTypeDef = TypedDict(
+    "RedactChannelMessageResponseTypeDef",
+    {
+        "ChannelArn": str,
+        "MessageId": str,
+        "SubChannelId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
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
 SearchFieldTypeDef = TypedDict(
     "SearchFieldTypeDef",
     {
         "Key": Literal["MEMBERS"],
         "Values": Sequence[str],
         "Operator": SearchFieldOperatorType,
     },
@@ -872,59 +952,63 @@
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
         "TagKeys": Sequence[str],
     },
 )
 
+UpdateChannelFlowResponseTypeDef = TypedDict(
+    "UpdateChannelFlowResponseTypeDef",
+    {
+        "ChannelFlowArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateChannelMessageRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateChannelMessageRequestRequestTypeDef",
     {
         "ChannelArn": str,
         "MessageId": str,
+        "Content": str,
         "ChimeBearer": str,
     },
 )
 _OptionalUpdateChannelMessageRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateChannelMessageRequestRequestTypeDef",
     {
-        "Content": str,
         "Metadata": str,
         "SubChannelId": str,
+        "ContentType": str,
     },
     total=False,
 )
 
 class UpdateChannelMessageRequestRequestTypeDef(
     _RequiredUpdateChannelMessageRequestRequestTypeDef,
     _OptionalUpdateChannelMessageRequestRequestTypeDef,
 ):
     pass
 
-_RequiredUpdateChannelReadMarkerRequestRequestTypeDef = TypedDict(
-    "_RequiredUpdateChannelReadMarkerRequestRequestTypeDef",
+UpdateChannelReadMarkerRequestRequestTypeDef = TypedDict(
+    "UpdateChannelReadMarkerRequestRequestTypeDef",
     {
         "ChannelArn": str,
         "ChimeBearer": str,
     },
 )
-_OptionalUpdateChannelReadMarkerRequestRequestTypeDef = TypedDict(
-    "_OptionalUpdateChannelReadMarkerRequestRequestTypeDef",
+
+UpdateChannelReadMarkerResponseTypeDef = TypedDict(
+    "UpdateChannelReadMarkerResponseTypeDef",
     {
-        "SubChannelId": str,
+        "ChannelArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-class UpdateChannelReadMarkerRequestRequestTypeDef(
-    _RequiredUpdateChannelReadMarkerRequestRequestTypeDef,
-    _OptionalUpdateChannelReadMarkerRequestRequestTypeDef,
-):
-    pass
-
 _RequiredUpdateChannelRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateChannelRequestRequestTypeDef",
     {
         "ChannelArn": str,
         "ChimeBearer": str,
     },
 )
@@ -939,14 +1023,22 @@
 )
 
 class UpdateChannelRequestRequestTypeDef(
     _RequiredUpdateChannelRequestRequestTypeDef, _OptionalUpdateChannelRequestRequestTypeDef
 ):
     pass
 
+UpdateChannelResponseTypeDef = TypedDict(
+    "UpdateChannelResponseTypeDef",
+    {
+        "ChannelArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 BatchChannelMembershipsTypeDef = TypedDict(
     "BatchChannelMembershipsTypeDef",
     {
         "InvitedBy": IdentityTypeDef,
         "Type": ChannelMembershipTypeType,
         "Members": List[IdentityTypeDef],
         "ChannelArn": str,
@@ -1011,115 +1103,48 @@
         "ChannelArn": str,
         "CreatedTimestamp": datetime,
         "CreatedBy": IdentityTypeDef,
     },
     total=False,
 )
 
-ChannelFlowCallbackResponseTypeDef = TypedDict(
-    "ChannelFlowCallbackResponseTypeDef",
-    {
-        "ChannelArn": str,
-        "CallbackId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 CreateChannelBanResponseTypeDef = TypedDict(
     "CreateChannelBanResponseTypeDef",
     {
         "ChannelArn": str,
         "Member": IdentityTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateChannelFlowResponseTypeDef = TypedDict(
-    "CreateChannelFlowResponseTypeDef",
-    {
-        "ChannelFlowArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateChannelMembershipResponseTypeDef = TypedDict(
     "CreateChannelMembershipResponseTypeDef",
     {
         "ChannelArn": str,
         "Member": IdentityTypeDef,
         "SubChannelId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateChannelModeratorResponseTypeDef = TypedDict(
     "CreateChannelModeratorResponseTypeDef",
     {
         "ChannelArn": str,
         "ChannelModerator": IdentityTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateChannelResponseTypeDef = TypedDict(
-    "CreateChannelResponseTypeDef",
-    {
-        "ChannelArn": str,
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
-RedactChannelMessageResponseTypeDef = TypedDict(
-    "RedactChannelMessageResponseTypeDef",
-    {
-        "ChannelArn": str,
-        "MessageId": str,
-        "SubChannelId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateChannelFlowResponseTypeDef = TypedDict(
-    "UpdateChannelFlowResponseTypeDef",
-    {
-        "ChannelFlowArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateChannelReadMarkerResponseTypeDef = TypedDict(
-    "UpdateChannelReadMarkerResponseTypeDef",
-    {
-        "ChannelArn": str,
-        "SubChannelId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateChannelResponseTypeDef = TypedDict(
-    "UpdateChannelResponseTypeDef",
-    {
-        "ChannelArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListChannelsAssociatedWithChannelFlowResponseTypeDef = TypedDict(
     "ListChannelsAssociatedWithChannelFlowResponseTypeDef",
     {
         "Channels": List[ChannelAssociatedWithFlowSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ChannelMembershipForAppInstanceUserSummaryTypeDef = TypedDict(
     "ChannelMembershipForAppInstanceUserSummaryTypeDef",
     {
         "ChannelSummary": ChannelSummaryTypeDef,
@@ -1137,24 +1162,24 @@
 )
 
 ListChannelsResponseTypeDef = TypedDict(
     "ListChannelsResponseTypeDef",
     {
         "Channels": List[ChannelSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SearchChannelsResponseTypeDef = TypedDict(
     "SearchChannelsResponseTypeDef",
     {
         "Channels": List[ChannelSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ChannelMembershipPreferencesTypeDef = TypedDict(
     "ChannelMembershipPreferencesTypeDef",
     {
         "PushNotifications": PushNotificationPreferencesTypeDef,
@@ -1172,50 +1197,53 @@
     "_OptionalChannelMessageCallbackTypeDef",
     {
         "Content": str,
         "Metadata": str,
         "PushNotification": PushNotificationConfigurationTypeDef,
         "MessageAttributes": Mapping[str, MessageAttributeValueTypeDef],
         "SubChannelId": str,
+        "ContentType": str,
     },
     total=False,
 )
 
 class ChannelMessageCallbackTypeDef(
     _RequiredChannelMessageCallbackTypeDef, _OptionalChannelMessageCallbackTypeDef
 ):
     pass
 
-_RequiredSendChannelMessageRequestRequestTypeDef = TypedDict(
-    "_RequiredSendChannelMessageRequestRequestTypeDef",
+GetChannelMessageStatusResponseTypeDef = TypedDict(
+    "GetChannelMessageStatusResponseTypeDef",
     {
-        "ChannelArn": str,
-        "Content": str,
-        "Type": ChannelMessageTypeType,
-        "Persistence": ChannelMessagePersistenceTypeType,
-        "ClientRequestToken": str,
-        "ChimeBearer": str,
+        "Status": ChannelMessageStatusStructureTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalSendChannelMessageRequestRequestTypeDef = TypedDict(
-    "_OptionalSendChannelMessageRequestRequestTypeDef",
+
+SendChannelMessageResponseTypeDef = TypedDict(
+    "SendChannelMessageResponseTypeDef",
     {
-        "Metadata": str,
-        "PushNotification": PushNotificationConfigurationTypeDef,
-        "MessageAttributes": Mapping[str, MessageAttributeValueTypeDef],
+        "ChannelArn": str,
+        "MessageId": str,
+        "Status": ChannelMessageStatusStructureTypeDef,
         "SubChannelId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-class SendChannelMessageRequestRequestTypeDef(
-    _RequiredSendChannelMessageRequestRequestTypeDef,
-    _OptionalSendChannelMessageRequestRequestTypeDef,
-):
-    pass
+UpdateChannelMessageResponseTypeDef = TypedDict(
+    "UpdateChannelMessageResponseTypeDef",
+    {
+        "ChannelArn": str,
+        "MessageId": str,
+        "Status": ChannelMessageStatusStructureTypeDef,
+        "SubChannelId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 ChannelMessageSummaryTypeDef = TypedDict(
     "ChannelMessageSummaryTypeDef",
     {
         "MessageId": str,
         "Content": str,
         "Metadata": str,
@@ -1223,14 +1251,16 @@
         "CreatedTimestamp": datetime,
         "LastUpdatedTimestamp": datetime,
         "LastEditedTimestamp": datetime,
         "Sender": IdentityTypeDef,
         "Redacted": bool,
         "Status": ChannelMessageStatusStructureTypeDef,
         "MessageAttributes": Dict[str, MessageAttributeValueTypeDef],
+        "ContentType": str,
+        "Target": List[TargetTypeDef],
     },
     total=False,
 )
 
 ChannelMessageTypeDef = TypedDict(
     "ChannelMessageTypeDef",
     {
@@ -1244,66 +1274,99 @@
         "LastUpdatedTimestamp": datetime,
         "Sender": IdentityTypeDef,
         "Redacted": bool,
         "Persistence": ChannelMessagePersistenceTypeType,
         "Status": ChannelMessageStatusStructureTypeDef,
         "MessageAttributes": Dict[str, MessageAttributeValueTypeDef],
         "SubChannelId": str,
+        "ContentType": str,
+        "Target": List[TargetTypeDef],
     },
     total=False,
 )
 
-GetChannelMessageStatusResponseTypeDef = TypedDict(
-    "GetChannelMessageStatusResponseTypeDef",
-    {
-        "Status": ChannelMessageStatusStructureTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SendChannelMessageResponseTypeDef = TypedDict(
-    "SendChannelMessageResponseTypeDef",
+_RequiredSendChannelMessageRequestRequestTypeDef = TypedDict(
+    "_RequiredSendChannelMessageRequestRequestTypeDef",
     {
         "ChannelArn": str,
-        "MessageId": str,
-        "Status": ChannelMessageStatusStructureTypeDef,
-        "SubChannelId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Content": str,
+        "Type": ChannelMessageTypeType,
+        "Persistence": ChannelMessagePersistenceTypeType,
+        "ClientRequestToken": str,
+        "ChimeBearer": str,
     },
 )
-
-UpdateChannelMessageResponseTypeDef = TypedDict(
-    "UpdateChannelMessageResponseTypeDef",
+_OptionalSendChannelMessageRequestRequestTypeDef = TypedDict(
+    "_OptionalSendChannelMessageRequestRequestTypeDef",
     {
-        "ChannelArn": str,
-        "MessageId": str,
-        "Status": ChannelMessageStatusStructureTypeDef,
+        "Metadata": str,
+        "PushNotification": PushNotificationConfigurationTypeDef,
+        "MessageAttributes": Mapping[str, MessageAttributeValueTypeDef],
         "SubChannelId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ContentType": str,
+        "Target": Sequence[TargetTypeDef],
     },
+    total=False,
 )
 
+class SendChannelMessageRequestRequestTypeDef(
+    _RequiredSendChannelMessageRequestRequestTypeDef,
+    _OptionalSendChannelMessageRequestRequestTypeDef,
+):
+    pass
+
 ChannelTypeDef = TypedDict(
     "ChannelTypeDef",
     {
         "Name": str,
         "ChannelArn": str,
         "Mode": ChannelModeType,
         "Privacy": ChannelPrivacyType,
         "Metadata": str,
         "CreatedBy": IdentityTypeDef,
         "CreatedTimestamp": datetime,
         "LastMessageTimestamp": datetime,
         "LastUpdatedTimestamp": datetime,
         "ChannelFlowArn": str,
         "ElasticChannelConfiguration": ElasticChannelConfigurationTypeDef,
+        "ExpirationSettings": ExpirationSettingsTypeDef,
     },
     total=False,
 )
 
+_RequiredPutChannelExpirationSettingsRequestRequestTypeDef = TypedDict(
+    "_RequiredPutChannelExpirationSettingsRequestRequestTypeDef",
+    {
+        "ChannelArn": str,
+    },
+)
+_OptionalPutChannelExpirationSettingsRequestRequestTypeDef = TypedDict(
+    "_OptionalPutChannelExpirationSettingsRequestRequestTypeDef",
+    {
+        "ChimeBearer": str,
+        "ExpirationSettings": ExpirationSettingsTypeDef,
+    },
+    total=False,
+)
+
+class PutChannelExpirationSettingsRequestRequestTypeDef(
+    _RequiredPutChannelExpirationSettingsRequestRequestTypeDef,
+    _OptionalPutChannelExpirationSettingsRequestRequestTypeDef,
+):
+    pass
+
+PutChannelExpirationSettingsResponseTypeDef = TypedDict(
+    "PutChannelExpirationSettingsResponseTypeDef",
+    {
+        "ChannelArn": str,
+        "ExpirationSettings": ExpirationSettingsTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateChannelRequestRequestTypeDef = TypedDict(
     "_RequiredCreateChannelRequestRequestTypeDef",
     {
         "AppInstanceArn": str,
         "Name": str,
         "ClientRequestToken": str,
         "ChimeBearer": str,
@@ -1316,28 +1379,29 @@
         "Privacy": ChannelPrivacyType,
         "Metadata": str,
         "Tags": Sequence[TagTypeDef],
         "ChannelId": str,
         "MemberArns": Sequence[str],
         "ModeratorArns": Sequence[str],
         "ElasticChannelConfiguration": ElasticChannelConfigurationTypeDef,
+        "ExpirationSettings": ExpirationSettingsTypeDef,
     },
     total=False,
 )
 
 class CreateChannelRequestRequestTypeDef(
     _RequiredCreateChannelRequestRequestTypeDef, _OptionalCreateChannelRequestRequestTypeDef
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
         "ResourceARN": str,
@@ -1345,15 +1409,39 @@
     },
 )
 
 GetMessagingSessionEndpointResponseTypeDef = TypedDict(
     "GetMessagingSessionEndpointResponseTypeDef",
     {
         "Endpoint": MessagingSessionEndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetMessagingStreamingConfigurationsResponseTypeDef = TypedDict(
+    "GetMessagingStreamingConfigurationsResponseTypeDef",
+    {
+        "StreamingConfigurations": List[StreamingConfigurationTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+PutMessagingStreamingConfigurationsRequestRequestTypeDef = TypedDict(
+    "PutMessagingStreamingConfigurationsRequestRequestTypeDef",
+    {
+        "AppInstanceArn": str,
+        "StreamingConfigurations": Sequence[StreamingConfigurationTypeDef],
+    },
+)
+
+PutMessagingStreamingConfigurationsResponseTypeDef = TypedDict(
+    "PutMessagingStreamingConfigurationsResponseTypeDef",
+    {
+        "StreamingConfigurations": List[StreamingConfigurationTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ProcessorConfigurationTypeDef = TypedDict(
     "ProcessorConfigurationTypeDef",
     {
         "Lambda": LambdaConfigurationTypeDef,
@@ -1362,15 +1450,15 @@
 
 ListSubChannelsResponseTypeDef = TypedDict(
     "ListSubChannelsResponseTypeDef",
     {
         "ChannelArn": str,
         "SubChannels": List[SubChannelSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSearchChannelsRequestRequestTypeDef = TypedDict(
     "_RequiredSearchChannelsRequestRequestTypeDef",
     {
         "Fields": Sequence[SearchFieldTypeDef],
@@ -1392,113 +1480,113 @@
     pass
 
 BatchCreateChannelMembershipResponseTypeDef = TypedDict(
     "BatchCreateChannelMembershipResponseTypeDef",
     {
         "BatchChannelMemberships": BatchChannelMembershipsTypeDef,
         "Errors": List[BatchCreateChannelMembershipErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListChannelBansResponseTypeDef = TypedDict(
     "ListChannelBansResponseTypeDef",
     {
         "ChannelArn": str,
         "NextToken": str,
         "ChannelBans": List[ChannelBanSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeChannelBanResponseTypeDef = TypedDict(
     "DescribeChannelBanResponseTypeDef",
     {
         "ChannelBan": ChannelBanTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListChannelMembershipsResponseTypeDef = TypedDict(
     "ListChannelMembershipsResponseTypeDef",
     {
         "ChannelArn": str,
         "ChannelMemberships": List[ChannelMembershipSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeChannelMembershipResponseTypeDef = TypedDict(
     "DescribeChannelMembershipResponseTypeDef",
     {
         "ChannelMembership": ChannelMembershipTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListChannelModeratorsResponseTypeDef = TypedDict(
     "ListChannelModeratorsResponseTypeDef",
     {
         "ChannelArn": str,
         "NextToken": str,
         "ChannelModerators": List[ChannelModeratorSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeChannelModeratorResponseTypeDef = TypedDict(
     "DescribeChannelModeratorResponseTypeDef",
     {
         "ChannelModerator": ChannelModeratorTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeChannelMembershipForAppInstanceUserResponseTypeDef = TypedDict(
     "DescribeChannelMembershipForAppInstanceUserResponseTypeDef",
     {
         "ChannelMembership": ChannelMembershipForAppInstanceUserSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListChannelMembershipsForAppInstanceUserResponseTypeDef = TypedDict(
     "ListChannelMembershipsForAppInstanceUserResponseTypeDef",
     {
         "ChannelMemberships": List[ChannelMembershipForAppInstanceUserSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeChannelModeratedByAppInstanceUserResponseTypeDef = TypedDict(
     "DescribeChannelModeratedByAppInstanceUserResponseTypeDef",
     {
         "Channel": ChannelModeratedByAppInstanceUserSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListChannelsModeratedByAppInstanceUserResponseTypeDef = TypedDict(
     "ListChannelsModeratedByAppInstanceUserResponseTypeDef",
     {
         "Channels": List[ChannelModeratedByAppInstanceUserSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetChannelMembershipPreferencesResponseTypeDef = TypedDict(
     "GetChannelMembershipPreferencesResponseTypeDef",
     {
         "ChannelArn": str,
         "Member": IdentityTypeDef,
         "Preferences": ChannelMembershipPreferencesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutChannelMembershipPreferencesRequestRequestTypeDef = TypedDict(
     "PutChannelMembershipPreferencesRequestRequestTypeDef",
     {
         "ChannelArn": str,
@@ -1510,15 +1598,15 @@
 
 PutChannelMembershipPreferencesResponseTypeDef = TypedDict(
     "PutChannelMembershipPreferencesResponseTypeDef",
     {
         "ChannelArn": str,
         "Member": IdentityTypeDef,
         "Preferences": ChannelMembershipPreferencesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredChannelFlowCallbackRequestRequestTypeDef = TypedDict(
     "_RequiredChannelFlowCallbackRequestRequestTypeDef",
     {
         "CallbackId": str,
@@ -1543,31 +1631,31 @@
 ListChannelMessagesResponseTypeDef = TypedDict(
     "ListChannelMessagesResponseTypeDef",
     {
         "ChannelArn": str,
         "NextToken": str,
         "ChannelMessages": List[ChannelMessageSummaryTypeDef],
         "SubChannelId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetChannelMessageResponseTypeDef = TypedDict(
     "GetChannelMessageResponseTypeDef",
     {
         "ChannelMessage": ChannelMessageTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeChannelResponseTypeDef = TypedDict(
     "DescribeChannelResponseTypeDef",
     {
         "Channel": ChannelTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ProcessorTypeDef = TypedDict(
     "ProcessorTypeDef",
     {
         "Name": str,
@@ -1631,18 +1719,18 @@
 )
 
 ListChannelFlowsResponseTypeDef = TypedDict(
     "ListChannelFlowsResponseTypeDef",
     {
         "ChannelFlows": List[ChannelFlowSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeChannelFlowResponseTypeDef = TypedDict(
     "DescribeChannelFlowResponseTypeDef",
     {
         "ChannelFlow": ChannelFlowTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-chime-sdk-messaging-2.5.0.post1/types_aiobotocore_chime_sdk_messaging.egg-info/SOURCES.txt` & `types-aiobotocore-chime-sdk-messaging-2.5.1/types_aiobotocore_chime_sdk_messaging.egg-info/SOURCES.txt`

 * *Files identical despite different names*

