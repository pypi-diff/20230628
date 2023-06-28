# Comparing `tmp/types-aiobotocore-chime-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-chime-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-chime-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:17 2023, max compression
+gzip compressed data, was "types-aiobotocore-chime-2.5.1.tar", last modified: Wed Jun 28 01:43:11 2023, max compression
```

## Comparing `types-aiobotocore-chime-2.5.0.post1.tar` & `types-aiobotocore-chime-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:17.510998 types-aiobotocore-chime-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:10:20.000000 types-aiobotocore-chime-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    32890 2023-03-11 12:26:17.506998 types-aiobotocore-chime-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    31327 2023-03-11 12:10:20.000000 types-aiobotocore-chime-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:17.510998 types-aiobotocore-chime-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2110 2023-03-11 12:10:20.000000 types-aiobotocore-chime-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:17.506998 types-aiobotocore-chime-2.5.0.post1/types_aiobotocore_chime/
--rw-r--r--   0 runner    (1001) docker     (123)      771 2023-03-11 12:10:20.000000 types-aiobotocore-chime-2.5.0.post1/types_aiobotocore_chime/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      770 2023-03-11 12:10:20.000000 types-aiobotocore-chime-2.5.0.post1/types_aiobotocore_chime/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      924 2023-03-11 12:10:20.000000 types-aiobotocore-chime-2.5.0.post1/types_aiobotocore_chime/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)   127548 2023-03-11 12:10:21.000000 types-aiobotocore-chime-2.5.0.post1/types_aiobotocore_chime/client.py
--rw-r--r--   0 runner    (1001) docker     (123)   127346 2023-03-11 12:10:21.000000 types-aiobotocore-chime-2.5.0.post1/types_aiobotocore_chime/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    13268 2023-03-11 12:10:21.000000 types-aiobotocore-chime-2.5.0.post1/types_aiobotocore_chime/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    13266 2023-03-11 12:10:21.000000 types-aiobotocore-chime-2.5.0.post1/types_aiobotocore_chime/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     3240 2023-03-11 12:10:21.000000 types-aiobotocore-chime-2.5.0.post1/types_aiobotocore_chime/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     3235 2023-03-11 12:10:21.000000 types-aiobotocore-chime-2.5.0.post1/types_aiobotocore_chime/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:10:20.000000 types-aiobotocore-chime-2.5.0.post1/types_aiobotocore_chime/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)   144539 2023-03-11 12:10:25.000000 types-aiobotocore-chime-2.5.0.post1/types_aiobotocore_chime/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)   144378 2023-03-11 12:10:23.000000 types-aiobotocore-chime-2.5.0.post1/types_aiobotocore_chime/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:10:20.000000 types-aiobotocore-chime-2.5.0.post1/types_aiobotocore_chime/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:17.506998 types-aiobotocore-chime-2.5.0.post1/types_aiobotocore_chime.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    32890 2023-03-11 12:26:17.000000 types-aiobotocore-chime-2.5.0.post1/types_aiobotocore_chime.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      775 2023-03-11 12:26:17.000000 types-aiobotocore-chime-2.5.0.post1/types_aiobotocore_chime.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:17.000000 types-aiobotocore-chime-2.5.0.post1/types_aiobotocore_chime.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:17.000000 types-aiobotocore-chime-2.5.0.post1/types_aiobotocore_chime.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:17.000000 types-aiobotocore-chime-2.5.0.post1/types_aiobotocore_chime.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       24 2023-03-11 12:26:17.000000 types-aiobotocore-chime-2.5.0.post1/types_aiobotocore_chime.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:11.038102 types-aiobotocore-chime-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:26:56.000000 types-aiobotocore-chime-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    32880 2023-06-28 01:43:11.030103 types-aiobotocore-chime-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    31323 2023-06-28 01:26:56.000000 types-aiobotocore-chime-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:11.038102 types-aiobotocore-chime-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2104 2023-06-28 01:26:56.000000 types-aiobotocore-chime-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:11.026103 types-aiobotocore-chime-2.5.1/types_aiobotocore_chime/
+-rw-r--r--   0 runner    (1001) docker     (123)      771 2023-06-28 01:26:56.000000 types-aiobotocore-chime-2.5.1/types_aiobotocore_chime/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      770 2023-06-28 01:26:56.000000 types-aiobotocore-chime-2.5.1/types_aiobotocore_chime/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      912 2023-06-28 01:26:56.000000 types-aiobotocore-chime-2.5.1/types_aiobotocore_chime/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)   127528 2023-06-28 01:26:57.000000 types-aiobotocore-chime-2.5.1/types_aiobotocore_chime/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)   127326 2023-06-28 01:26:57.000000 types-aiobotocore-chime-2.5.1/types_aiobotocore_chime/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    13503 2023-06-28 01:26:57.000000 types-aiobotocore-chime-2.5.1/types_aiobotocore_chime/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13501 2023-06-28 01:26:57.000000 types-aiobotocore-chime-2.5.1/types_aiobotocore_chime/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     3124 2023-06-28 01:26:57.000000 types-aiobotocore-chime-2.5.1/types_aiobotocore_chime/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3120 2023-06-28 01:26:57.000000 types-aiobotocore-chime-2.5.1/types_aiobotocore_chime/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:26:56.000000 types-aiobotocore-chime-2.5.1/types_aiobotocore_chime/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)   144748 2023-06-28 01:27:01.000000 types-aiobotocore-chime-2.5.1/types_aiobotocore_chime/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)   144589 2023-06-28 01:26:59.000000 types-aiobotocore-chime-2.5.1/types_aiobotocore_chime/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:26:56.000000 types-aiobotocore-chime-2.5.1/types_aiobotocore_chime/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:11.026103 types-aiobotocore-chime-2.5.1/types_aiobotocore_chime.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    32880 2023-06-28 01:43:10.000000 types-aiobotocore-chime-2.5.1/types_aiobotocore_chime.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      775 2023-06-28 01:43:10.000000 types-aiobotocore-chime-2.5.1/types_aiobotocore_chime.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:10.000000 types-aiobotocore-chime-2.5.1/types_aiobotocore_chime.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:10.000000 types-aiobotocore-chime-2.5.1/types_aiobotocore_chime.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:10.000000 types-aiobotocore-chime-2.5.1/types_aiobotocore_chime.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       24 2023-06-28 01:43:10.000000 types-aiobotocore-chime-2.5.1/types_aiobotocore_chime.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-chime-2.5.0.post1/LICENSE` & `types-aiobotocore-chime-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-chime-2.5.0.post1/PKG-INFO` & `types-aiobotocore-chime-2.5.1/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-chime
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Chime 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Chime 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-chime"></a>
 
 # types-aiobotocore-chime
 
 [![PyPI - types-aiobotocore-chime](https://img.shields.io/pypi/v/types-aiobotocore-chime.svg?color=blue)](https://pypi.org/project/types-aiobotocore-chime)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-chime.svg?color=blue)](https://pypi.org/project/types-aiobotocore-chime)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-chime?color=blue)](https://pypistats.org/packages/types-aiobotocore-chime)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Chime 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime)
+[aiobotocore.Chime 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime)
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
 [types-aiobotocore-chime docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/).
 
 See how it helps to find and fix potential bugs:
 
@@ -382,15 +382,14 @@
     AppInstanceUserTypeDef,
     AudioArtifactsConfigurationTypeDef,
     ContentArtifactsConfigurationTypeDef,
     VideoArtifactsConfigurationTypeDef,
     AssociatePhoneNumberWithUserRequestRequestTypeDef,
     AssociatePhoneNumbersWithVoiceConnectorGroupRequestRequestTypeDef,
     PhoneNumberErrorTypeDef,
-    ResponseMetadataTypeDef,
     AssociatePhoneNumbersWithVoiceConnectorRequestRequestTypeDef,
     AttendeeTypeDef,
     CreateAttendeeErrorTypeDef,
     BatchCreateChannelMembershipErrorTypeDef,
     BatchCreateChannelMembershipRequestRequestTypeDef,
     MembershipItemTypeDef,
     MemberErrorTypeDef,
@@ -403,19 +402,23 @@
     BusinessCallingSettingsTypeDef,
     CandidateAddressTypeDef,
     ChannelSummaryTypeDef,
     ConversationRetentionSettingsTypeDef,
     CreateAccountRequestRequestTypeDef,
     CreateAppInstanceAdminRequestRequestTypeDef,
     TagTypeDef,
+    CreateAppInstanceResponseTypeDef,
+    CreateAppInstanceUserResponseTypeDef,
     CreateBotRequestRequestTypeDef,
     CreateChannelBanRequestRequestTypeDef,
     CreateChannelMembershipRequestRequestTypeDef,
     CreateChannelModeratorRequestRequestTypeDef,
+    CreateChannelResponseTypeDef,
     CreateMeetingDialOutRequestRequestTypeDef,
+    CreateMeetingDialOutResponseTypeDef,
     MeetingNotificationConfigurationTypeDef,
     CreatePhoneNumberOrderRequestRequestTypeDef,
     GeoMatchParamsTypeDef,
     CreateRoomMembershipRequestRequestTypeDef,
     CreateRoomRequestRequestTypeDef,
     RoomTypeDef,
     CreateSipMediaApplicationCallRequestRequestTypeDef,
@@ -465,14 +468,15 @@
     DescribeChannelModeratedByAppInstanceUserRequestRequestTypeDef,
     DescribeChannelModeratorRequestRequestTypeDef,
     DescribeChannelRequestRequestTypeDef,
     DisassociatePhoneNumberFromUserRequestRequestTypeDef,
     DisassociatePhoneNumbersFromVoiceConnectorGroupRequestRequestTypeDef,
     DisassociatePhoneNumbersFromVoiceConnectorRequestRequestTypeDef,
     DisassociateSigninDelegateGroupsFromAccountRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EngineTranscribeMedicalSettingsTypeDef,
     EngineTranscribeSettingsTypeDef,
     EventsConfigurationTypeDef,
     GetAccountRequestRequestTypeDef,
     GetAccountSettingsRequestRequestTypeDef,
     GetAppInstanceRetentionSettingsRequestRequestTypeDef,
     GetAppInstanceStreamingConfigurationsRequestRequestTypeDef,
@@ -482,14 +486,15 @@
     GetEventsConfigurationRequestRequestTypeDef,
     VoiceConnectorSettingsTypeDef,
     GetMediaCapturePipelineRequestRequestTypeDef,
     GetMeetingRequestRequestTypeDef,
     MessagingSessionEndpointTypeDef,
     GetPhoneNumberOrderRequestRequestTypeDef,
     GetPhoneNumberRequestRequestTypeDef,
+    GetPhoneNumberSettingsResponseTypeDef,
     GetProxySessionRequestRequestTypeDef,
     GetRetentionSettingsRequestRequestTypeDef,
     GetRoomRequestRequestTypeDef,
     GetSipMediaApplicationLoggingConfigurationRequestRequestTypeDef,
     SipMediaApplicationLoggingConfigurationTypeDef,
     GetSipMediaApplicationRequestRequestTypeDef,
     GetSipRuleRequestRequestTypeDef,
@@ -506,15 +511,15 @@
     GetVoiceConnectorStreamingConfigurationRequestRequestTypeDef,
     GetVoiceConnectorTerminationHealthRequestRequestTypeDef,
     TerminationHealthTypeDef,
     GetVoiceConnectorTerminationRequestRequestTypeDef,
     TerminationTypeDef,
     InviteTypeDef,
     InviteUsersRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListAccountsRequestListAccountsPaginateTypeDef,
     ListAccountsRequestRequestTypeDef,
     ListAppInstanceAdminsRequestRequestTypeDef,
     ListAppInstanceUsersRequestRequestTypeDef,
     ListAppInstancesRequestRequestTypeDef,
     ListAttendeeTagsRequestRequestTypeDef,
     ListAttendeesRequestRequestTypeDef,
     ListBotsRequestRequestTypeDef,
@@ -534,59 +539,72 @@
     ListRoomMembershipsRequestRequestTypeDef,
     ListRoomsRequestRequestTypeDef,
     ListSipMediaApplicationsRequestRequestTypeDef,
     ListSipRulesRequestRequestTypeDef,
     ListSupportedPhoneNumberCountriesRequestRequestTypeDef,
     PhoneNumberCountryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListUsersRequestListUsersPaginateTypeDef,
     ListUsersRequestRequestTypeDef,
     ListVoiceConnectorGroupsRequestRequestTypeDef,
     ListVoiceConnectorTerminationCredentialsRequestRequestTypeDef,
+    ListVoiceConnectorTerminationCredentialsResponseTypeDef,
     ListVoiceConnectorsRequestRequestTypeDef,
     LogoutUserRequestRequestTypeDef,
     MediaPlacementTypeDef,
     MemberTypeDef,
     OrderedPhoneNumberTypeDef,
     OriginationRouteTypeDef,
+    PaginatorConfigTypeDef,
     ParticipantTypeDef,
     PhoneNumberAssociationTypeDef,
     PhoneNumberCapabilitiesTypeDef,
     PutEventsConfigurationRequestRequestTypeDef,
     PutVoiceConnectorProxyRequestRequestTypeDef,
     RedactChannelMessageRequestRequestTypeDef,
+    RedactChannelMessageResponseTypeDef,
     RedactConversationMessageRequestRequestTypeDef,
     RedactRoomMessageRequestRequestTypeDef,
     RegenerateSecurityTokenRequestRequestTypeDef,
     ResetPersonalPINRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     RestorePhoneNumberRequestRequestTypeDef,
     RoomRetentionSettingsTypeDef,
     SearchAvailablePhoneNumbersRequestRequestTypeDef,
+    SearchAvailablePhoneNumbersResponseTypeDef,
     SelectedVideoStreamsTypeDef,
     SendChannelMessageRequestRequestTypeDef,
+    SendChannelMessageResponseTypeDef,
     StopMeetingTranscriptionRequestRequestTypeDef,
     StreamingNotificationTargetTypeDef,
     TelephonySettingsTypeDef,
     UntagAttendeeRequestRequestTypeDef,
     UntagMeetingRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateAccountRequestRequestTypeDef,
     UpdateAppInstanceRequestRequestTypeDef,
+    UpdateAppInstanceResponseTypeDef,
     UpdateAppInstanceUserRequestRequestTypeDef,
+    UpdateAppInstanceUserResponseTypeDef,
     UpdateBotRequestRequestTypeDef,
     UpdateChannelMessageRequestRequestTypeDef,
+    UpdateChannelMessageResponseTypeDef,
     UpdateChannelReadMarkerRequestRequestTypeDef,
+    UpdateChannelReadMarkerResponseTypeDef,
     UpdateChannelRequestRequestTypeDef,
+    UpdateChannelResponseTypeDef,
     UpdatePhoneNumberRequestRequestTypeDef,
     UpdatePhoneNumberSettingsRequestRequestTypeDef,
     UpdateProxySessionRequestRequestTypeDef,
     UpdateRoomMembershipRequestRequestTypeDef,
     UpdateRoomRequestRequestTypeDef,
     UpdateSipMediaApplicationCallRequestRequestTypeDef,
     UpdateVoiceConnectorRequestRequestTypeDef,
     ValidateE911AddressRequestRequestTypeDef,
+    GetAccountSettingsResponseTypeDef,
     UpdateAccountSettingsRequestRequestTypeDef,
     AccountTypeDef,
     AssociateSigninDelegateGroupsWithAccountRequestRequestTypeDef,
     UpdateUserRequestItemTypeDef,
     UpdateUserRequestRequestTypeDef,
     UserTypeDef,
     AppInstanceAdminSummaryTypeDef,
@@ -597,49 +615,33 @@
     ChannelMembershipSummaryTypeDef,
     ChannelMembershipTypeDef,
     ChannelMessageSummaryTypeDef,
     ChannelMessageTypeDef,
     ChannelModeratorSummaryTypeDef,
     ChannelModeratorTypeDef,
     ChannelTypeDef,
+    CreateAppInstanceAdminResponseTypeDef,
+    CreateChannelBanResponseTypeDef,
+    CreateChannelMembershipResponseTypeDef,
+    CreateChannelModeratorResponseTypeDef,
     AppInstanceRetentionSettingsTypeDef,
+    GetAppInstanceStreamingConfigurationsResponseTypeDef,
     PutAppInstanceStreamingConfigurationsRequestRequestTypeDef,
+    PutAppInstanceStreamingConfigurationsResponseTypeDef,
+    ListAppInstancesResponseTypeDef,
+    DescribeAppInstanceResponseTypeDef,
+    ListAppInstanceUsersResponseTypeDef,
+    DescribeAppInstanceUserResponseTypeDef,
     ArtifactsConfigurationTypeDef,
     AssociatePhoneNumbersWithVoiceConnectorGroupResponseTypeDef,
     AssociatePhoneNumbersWithVoiceConnectorResponseTypeDef,
     BatchDeletePhoneNumberResponseTypeDef,
     BatchUpdatePhoneNumberResponseTypeDef,
-    CreateAppInstanceAdminResponseTypeDef,
-    CreateAppInstanceResponseTypeDef,
-    CreateAppInstanceUserResponseTypeDef,
-    CreateChannelBanResponseTypeDef,
-    CreateChannelMembershipResponseTypeDef,
-    CreateChannelModeratorResponseTypeDef,
-    CreateChannelResponseTypeDef,
-    CreateMeetingDialOutResponseTypeDef,
-    DescribeAppInstanceResponseTypeDef,
-    DescribeAppInstanceUserResponseTypeDef,
     DisassociatePhoneNumbersFromVoiceConnectorGroupResponseTypeDef,
     DisassociatePhoneNumbersFromVoiceConnectorResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetAccountSettingsResponseTypeDef,
-    GetAppInstanceStreamingConfigurationsResponseTypeDef,
-    GetPhoneNumberSettingsResponseTypeDef,
-    ListAppInstanceUsersResponseTypeDef,
-    ListAppInstancesResponseTypeDef,
-    ListVoiceConnectorTerminationCredentialsResponseTypeDef,
-    PutAppInstanceStreamingConfigurationsResponseTypeDef,
-    RedactChannelMessageResponseTypeDef,
-    SearchAvailablePhoneNumbersResponseTypeDef,
-    SendChannelMessageResponseTypeDef,
-    UpdateAppInstanceResponseTypeDef,
-    UpdateAppInstanceUserResponseTypeDef,
-    UpdateChannelMessageResponseTypeDef,
-    UpdateChannelReadMarkerResponseTypeDef,
-    UpdateChannelResponseTypeDef,
     CreateAttendeeResponseTypeDef,
     GetAttendeeResponseTypeDef,
     ListAttendeesResponseTypeDef,
     BatchCreateAttendeeResponseTypeDef,
     BatchCreateRoomMembershipRequestRequestTypeDef,
     BatchCreateRoomMembershipResponseTypeDef,
     BatchSuspendUserResponseTypeDef,
@@ -704,16 +706,14 @@
     GetVoiceConnectorProxyResponseTypeDef,
     PutVoiceConnectorProxyResponseTypeDef,
     GetVoiceConnectorTerminationHealthResponseTypeDef,
     GetVoiceConnectorTerminationResponseTypeDef,
     PutVoiceConnectorTerminationRequestRequestTypeDef,
     PutVoiceConnectorTerminationResponseTypeDef,
     InviteUsersResponseTypeDef,
-    ListAccountsRequestListAccountsPaginateTypeDef,
-    ListUsersRequestListUsersPaginateTypeDef,
     ListSupportedPhoneNumberCountriesResponseTypeDef,
     MeetingTypeDef,
     RoomMembershipTypeDef,
     PhoneNumberOrderTypeDef,
     OriginationTypeDef,
     ProxySessionTypeDef,
     PhoneNumberTypeDef,
@@ -813,43 +813,43 @@
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

### Comparing `types-aiobotocore-chime-2.5.0.post1/README.md` & `types-aiobotocore-chime-2.5.1/README.md`

 * *Files 0% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-chime"></a>
 
 # types-aiobotocore-chime
 
 [![PyPI - types-aiobotocore-chime](https://img.shields.io/pypi/v/types-aiobotocore-chime.svg?color=blue)](https://pypi.org/project/types-aiobotocore-chime)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-chime.svg?color=blue)](https://pypi.org/project/types-aiobotocore-chime)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-chime?color=blue)](https://pypistats.org/packages/types-aiobotocore-chime)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Chime 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime)
+[aiobotocore.Chime 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime)
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
 [types-aiobotocore-chime docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/).
 
 See how it helps to find and fix potential bugs:
 
@@ -349,15 +349,14 @@
     AppInstanceUserTypeDef,
     AudioArtifactsConfigurationTypeDef,
     ContentArtifactsConfigurationTypeDef,
     VideoArtifactsConfigurationTypeDef,
     AssociatePhoneNumberWithUserRequestRequestTypeDef,
     AssociatePhoneNumbersWithVoiceConnectorGroupRequestRequestTypeDef,
     PhoneNumberErrorTypeDef,
-    ResponseMetadataTypeDef,
     AssociatePhoneNumbersWithVoiceConnectorRequestRequestTypeDef,
     AttendeeTypeDef,
     CreateAttendeeErrorTypeDef,
     BatchCreateChannelMembershipErrorTypeDef,
     BatchCreateChannelMembershipRequestRequestTypeDef,
     MembershipItemTypeDef,
     MemberErrorTypeDef,
@@ -370,19 +369,23 @@
     BusinessCallingSettingsTypeDef,
     CandidateAddressTypeDef,
     ChannelSummaryTypeDef,
     ConversationRetentionSettingsTypeDef,
     CreateAccountRequestRequestTypeDef,
     CreateAppInstanceAdminRequestRequestTypeDef,
     TagTypeDef,
+    CreateAppInstanceResponseTypeDef,
+    CreateAppInstanceUserResponseTypeDef,
     CreateBotRequestRequestTypeDef,
     CreateChannelBanRequestRequestTypeDef,
     CreateChannelMembershipRequestRequestTypeDef,
     CreateChannelModeratorRequestRequestTypeDef,
+    CreateChannelResponseTypeDef,
     CreateMeetingDialOutRequestRequestTypeDef,
+    CreateMeetingDialOutResponseTypeDef,
     MeetingNotificationConfigurationTypeDef,
     CreatePhoneNumberOrderRequestRequestTypeDef,
     GeoMatchParamsTypeDef,
     CreateRoomMembershipRequestRequestTypeDef,
     CreateRoomRequestRequestTypeDef,
     RoomTypeDef,
     CreateSipMediaApplicationCallRequestRequestTypeDef,
@@ -432,14 +435,15 @@
     DescribeChannelModeratedByAppInstanceUserRequestRequestTypeDef,
     DescribeChannelModeratorRequestRequestTypeDef,
     DescribeChannelRequestRequestTypeDef,
     DisassociatePhoneNumberFromUserRequestRequestTypeDef,
     DisassociatePhoneNumbersFromVoiceConnectorGroupRequestRequestTypeDef,
     DisassociatePhoneNumbersFromVoiceConnectorRequestRequestTypeDef,
     DisassociateSigninDelegateGroupsFromAccountRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EngineTranscribeMedicalSettingsTypeDef,
     EngineTranscribeSettingsTypeDef,
     EventsConfigurationTypeDef,
     GetAccountRequestRequestTypeDef,
     GetAccountSettingsRequestRequestTypeDef,
     GetAppInstanceRetentionSettingsRequestRequestTypeDef,
     GetAppInstanceStreamingConfigurationsRequestRequestTypeDef,
@@ -449,14 +453,15 @@
     GetEventsConfigurationRequestRequestTypeDef,
     VoiceConnectorSettingsTypeDef,
     GetMediaCapturePipelineRequestRequestTypeDef,
     GetMeetingRequestRequestTypeDef,
     MessagingSessionEndpointTypeDef,
     GetPhoneNumberOrderRequestRequestTypeDef,
     GetPhoneNumberRequestRequestTypeDef,
+    GetPhoneNumberSettingsResponseTypeDef,
     GetProxySessionRequestRequestTypeDef,
     GetRetentionSettingsRequestRequestTypeDef,
     GetRoomRequestRequestTypeDef,
     GetSipMediaApplicationLoggingConfigurationRequestRequestTypeDef,
     SipMediaApplicationLoggingConfigurationTypeDef,
     GetSipMediaApplicationRequestRequestTypeDef,
     GetSipRuleRequestRequestTypeDef,
@@ -473,15 +478,15 @@
     GetVoiceConnectorStreamingConfigurationRequestRequestTypeDef,
     GetVoiceConnectorTerminationHealthRequestRequestTypeDef,
     TerminationHealthTypeDef,
     GetVoiceConnectorTerminationRequestRequestTypeDef,
     TerminationTypeDef,
     InviteTypeDef,
     InviteUsersRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListAccountsRequestListAccountsPaginateTypeDef,
     ListAccountsRequestRequestTypeDef,
     ListAppInstanceAdminsRequestRequestTypeDef,
     ListAppInstanceUsersRequestRequestTypeDef,
     ListAppInstancesRequestRequestTypeDef,
     ListAttendeeTagsRequestRequestTypeDef,
     ListAttendeesRequestRequestTypeDef,
     ListBotsRequestRequestTypeDef,
@@ -501,59 +506,72 @@
     ListRoomMembershipsRequestRequestTypeDef,
     ListRoomsRequestRequestTypeDef,
     ListSipMediaApplicationsRequestRequestTypeDef,
     ListSipRulesRequestRequestTypeDef,
     ListSupportedPhoneNumberCountriesRequestRequestTypeDef,
     PhoneNumberCountryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListUsersRequestListUsersPaginateTypeDef,
     ListUsersRequestRequestTypeDef,
     ListVoiceConnectorGroupsRequestRequestTypeDef,
     ListVoiceConnectorTerminationCredentialsRequestRequestTypeDef,
+    ListVoiceConnectorTerminationCredentialsResponseTypeDef,
     ListVoiceConnectorsRequestRequestTypeDef,
     LogoutUserRequestRequestTypeDef,
     MediaPlacementTypeDef,
     MemberTypeDef,
     OrderedPhoneNumberTypeDef,
     OriginationRouteTypeDef,
+    PaginatorConfigTypeDef,
     ParticipantTypeDef,
     PhoneNumberAssociationTypeDef,
     PhoneNumberCapabilitiesTypeDef,
     PutEventsConfigurationRequestRequestTypeDef,
     PutVoiceConnectorProxyRequestRequestTypeDef,
     RedactChannelMessageRequestRequestTypeDef,
+    RedactChannelMessageResponseTypeDef,
     RedactConversationMessageRequestRequestTypeDef,
     RedactRoomMessageRequestRequestTypeDef,
     RegenerateSecurityTokenRequestRequestTypeDef,
     ResetPersonalPINRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     RestorePhoneNumberRequestRequestTypeDef,
     RoomRetentionSettingsTypeDef,
     SearchAvailablePhoneNumbersRequestRequestTypeDef,
+    SearchAvailablePhoneNumbersResponseTypeDef,
     SelectedVideoStreamsTypeDef,
     SendChannelMessageRequestRequestTypeDef,
+    SendChannelMessageResponseTypeDef,
     StopMeetingTranscriptionRequestRequestTypeDef,
     StreamingNotificationTargetTypeDef,
     TelephonySettingsTypeDef,
     UntagAttendeeRequestRequestTypeDef,
     UntagMeetingRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateAccountRequestRequestTypeDef,
     UpdateAppInstanceRequestRequestTypeDef,
+    UpdateAppInstanceResponseTypeDef,
     UpdateAppInstanceUserRequestRequestTypeDef,
+    UpdateAppInstanceUserResponseTypeDef,
     UpdateBotRequestRequestTypeDef,
     UpdateChannelMessageRequestRequestTypeDef,
+    UpdateChannelMessageResponseTypeDef,
     UpdateChannelReadMarkerRequestRequestTypeDef,
+    UpdateChannelReadMarkerResponseTypeDef,
     UpdateChannelRequestRequestTypeDef,
+    UpdateChannelResponseTypeDef,
     UpdatePhoneNumberRequestRequestTypeDef,
     UpdatePhoneNumberSettingsRequestRequestTypeDef,
     UpdateProxySessionRequestRequestTypeDef,
     UpdateRoomMembershipRequestRequestTypeDef,
     UpdateRoomRequestRequestTypeDef,
     UpdateSipMediaApplicationCallRequestRequestTypeDef,
     UpdateVoiceConnectorRequestRequestTypeDef,
     ValidateE911AddressRequestRequestTypeDef,
+    GetAccountSettingsResponseTypeDef,
     UpdateAccountSettingsRequestRequestTypeDef,
     AccountTypeDef,
     AssociateSigninDelegateGroupsWithAccountRequestRequestTypeDef,
     UpdateUserRequestItemTypeDef,
     UpdateUserRequestRequestTypeDef,
     UserTypeDef,
     AppInstanceAdminSummaryTypeDef,
@@ -564,49 +582,33 @@
     ChannelMembershipSummaryTypeDef,
     ChannelMembershipTypeDef,
     ChannelMessageSummaryTypeDef,
     ChannelMessageTypeDef,
     ChannelModeratorSummaryTypeDef,
     ChannelModeratorTypeDef,
     ChannelTypeDef,
+    CreateAppInstanceAdminResponseTypeDef,
+    CreateChannelBanResponseTypeDef,
+    CreateChannelMembershipResponseTypeDef,
+    CreateChannelModeratorResponseTypeDef,
     AppInstanceRetentionSettingsTypeDef,
+    GetAppInstanceStreamingConfigurationsResponseTypeDef,
     PutAppInstanceStreamingConfigurationsRequestRequestTypeDef,
+    PutAppInstanceStreamingConfigurationsResponseTypeDef,
+    ListAppInstancesResponseTypeDef,
+    DescribeAppInstanceResponseTypeDef,
+    ListAppInstanceUsersResponseTypeDef,
+    DescribeAppInstanceUserResponseTypeDef,
     ArtifactsConfigurationTypeDef,
     AssociatePhoneNumbersWithVoiceConnectorGroupResponseTypeDef,
     AssociatePhoneNumbersWithVoiceConnectorResponseTypeDef,
     BatchDeletePhoneNumberResponseTypeDef,
     BatchUpdatePhoneNumberResponseTypeDef,
-    CreateAppInstanceAdminResponseTypeDef,
-    CreateAppInstanceResponseTypeDef,
-    CreateAppInstanceUserResponseTypeDef,
-    CreateChannelBanResponseTypeDef,
-    CreateChannelMembershipResponseTypeDef,
-    CreateChannelModeratorResponseTypeDef,
-    CreateChannelResponseTypeDef,
-    CreateMeetingDialOutResponseTypeDef,
-    DescribeAppInstanceResponseTypeDef,
-    DescribeAppInstanceUserResponseTypeDef,
     DisassociatePhoneNumbersFromVoiceConnectorGroupResponseTypeDef,
     DisassociatePhoneNumbersFromVoiceConnectorResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetAccountSettingsResponseTypeDef,
-    GetAppInstanceStreamingConfigurationsResponseTypeDef,
-    GetPhoneNumberSettingsResponseTypeDef,
-    ListAppInstanceUsersResponseTypeDef,
-    ListAppInstancesResponseTypeDef,
-    ListVoiceConnectorTerminationCredentialsResponseTypeDef,
-    PutAppInstanceStreamingConfigurationsResponseTypeDef,
-    RedactChannelMessageResponseTypeDef,
-    SearchAvailablePhoneNumbersResponseTypeDef,
-    SendChannelMessageResponseTypeDef,
-    UpdateAppInstanceResponseTypeDef,
-    UpdateAppInstanceUserResponseTypeDef,
-    UpdateChannelMessageResponseTypeDef,
-    UpdateChannelReadMarkerResponseTypeDef,
-    UpdateChannelResponseTypeDef,
     CreateAttendeeResponseTypeDef,
     GetAttendeeResponseTypeDef,
     ListAttendeesResponseTypeDef,
     BatchCreateAttendeeResponseTypeDef,
     BatchCreateRoomMembershipRequestRequestTypeDef,
     BatchCreateRoomMembershipResponseTypeDef,
     BatchSuspendUserResponseTypeDef,
@@ -671,16 +673,14 @@
     GetVoiceConnectorProxyResponseTypeDef,
     PutVoiceConnectorProxyResponseTypeDef,
     GetVoiceConnectorTerminationHealthResponseTypeDef,
     GetVoiceConnectorTerminationResponseTypeDef,
     PutVoiceConnectorTerminationRequestRequestTypeDef,
     PutVoiceConnectorTerminationResponseTypeDef,
     InviteUsersResponseTypeDef,
-    ListAccountsRequestListAccountsPaginateTypeDef,
-    ListUsersRequestListUsersPaginateTypeDef,
     ListSupportedPhoneNumberCountriesResponseTypeDef,
     MeetingTypeDef,
     RoomMembershipTypeDef,
     PhoneNumberOrderTypeDef,
     OriginationTypeDef,
     ProxySessionTypeDef,
     PhoneNumberTypeDef,
@@ -780,43 +780,43 @@
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

### Comparing `types-aiobotocore-chime-2.5.0.post1/setup.py` & `types-aiobotocore-chime-2.5.1/setup.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-chime.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-chime",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_chime"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Chime 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.Chime 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/"
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

### Comparing `types-aiobotocore-chime-2.5.0.post1/types_aiobotocore_chime/__init__.py` & `types-aiobotocore-chime-2.5.1/types_aiobotocore_chime/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-chime-2.5.0.post1/types_aiobotocore_chime/__init__.pyi` & `types-aiobotocore-chime-2.5.1/types_aiobotocore_chime/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-chime-2.5.0.post1/types_aiobotocore_chime/__main__.py` & `types-aiobotocore-chime-2.5.1/types_aiobotocore_chime/__main__.py`

 * *Files 15% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Chime 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Chime 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime//\nBoto3 docs:  "
         "    https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime\nOther"
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

### Comparing `types-aiobotocore-chime-2.5.0.post1/types_aiobotocore_chime/client.py` & `types-aiobotocore-chime-2.5.1/types_aiobotocore_chime/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -672,15 +672,15 @@
         ToPhoneNumber: str,
         SipMediaApplicationId: str,
         SipHeaders: Mapping[str, str] = ...
     ) -> CreateSipMediaApplicationCallResponseTypeDef:
         """
         Creates an outbound call to a phone number from the phone number specified in
         the request, and it invokes the endpoint of the specified
-        `sipMediaApplicationId` .
+        `sipMediaApplicationId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.create_sip_media_application_call)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#create_sip_media_application_call)
         """
 
     async def create_sip_rule(
         self,
@@ -756,25 +756,25 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#delete_app_instance_admin)
         """
 
     async def delete_app_instance_streaming_configurations(
         self, *, AppInstanceArn: str
     ) -> EmptyResponseMetadataTypeDef:
         """
-        Deletes the streaming configurations of an `AppInstance` .
+        Deletes the streaming configurations of an `AppInstance`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.delete_app_instance_streaming_configurations)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#delete_app_instance_streaming_configurations)
         """
 
     async def delete_app_instance_user(
         self, *, AppInstanceUserArn: str
     ) -> EmptyResponseMetadataTypeDef:
         """
-        Deletes an `AppInstanceUser` .
+        Deletes an `AppInstanceUser`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.delete_app_instance_user)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#delete_app_instance_user)
         """
 
     async def delete_attendee(
         self, *, MeetingId: str, AttendeeId: str
@@ -1004,45 +1004,45 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#delete_voice_connector_termination_credentials)
         """
 
     async def describe_app_instance(
         self, *, AppInstanceArn: str
     ) -> DescribeAppInstanceResponseTypeDef:
         """
-        Returns the full details of an `AppInstance` .
+        Returns the full details of an `AppInstance`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.describe_app_instance)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#describe_app_instance)
         """
 
     async def describe_app_instance_admin(
         self, *, AppInstanceAdminArn: str, AppInstanceArn: str
     ) -> DescribeAppInstanceAdminResponseTypeDef:
         """
-        Returns the full details of an `AppInstanceAdmin` .
+        Returns the full details of an `AppInstanceAdmin`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.describe_app_instance_admin)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#describe_app_instance_admin)
         """
 
     async def describe_app_instance_user(
         self, *, AppInstanceUserArn: str
     ) -> DescribeAppInstanceUserResponseTypeDef:
         """
-        Returns the full details of an `AppInstanceUser` .
+        Returns the full details of an `AppInstanceUser`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.describe_app_instance_user)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#describe_app_instance_user)
         """
 
     async def describe_channel(
         self, *, ChannelArn: str, ChimeBearer: str = ...
     ) -> DescribeChannelResponseTypeDef:
         """
-        Returns the full details of a channel in an Amazon Chime `AppInstance` .
+        Returns the full details of a channel in an Amazon Chime `AppInstance`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.describe_channel)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#describe_channel)
         """
 
     async def describe_channel_ban(
         self, *, ChannelArn: str, MemberArn: str, ChimeBearer: str = ...
@@ -1065,26 +1065,26 @@
         """
 
     async def describe_channel_membership_for_app_instance_user(
         self, *, ChannelArn: str, AppInstanceUserArn: str, ChimeBearer: str = ...
     ) -> DescribeChannelMembershipForAppInstanceUserResponseTypeDef:
         """
         Returns the details of a channel based on the membership of the specified
-        `AppInstanceUser` .
+        `AppInstanceUser`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.describe_channel_membership_for_app_instance_user)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#describe_channel_membership_for_app_instance_user)
         """
 
     async def describe_channel_moderated_by_app_instance_user(
         self, *, ChannelArn: str, AppInstanceUserArn: str, ChimeBearer: str = ...
     ) -> DescribeChannelModeratedByAppInstanceUserResponseTypeDef:
         """
         Returns the full details of a channel moderated by the specified
-        `AppInstanceUser` .
+        `AppInstanceUser`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.describe_channel_moderated_by_app_instance_user)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#describe_channel_moderated_by_app_instance_user)
         """
 
     async def describe_channel_moderator(
         self, *, ChannelArn: str, ChannelModeratorArn: str, ChimeBearer: str = ...
@@ -1172,25 +1172,25 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#get_account_settings)
         """
 
     async def get_app_instance_retention_settings(
         self, *, AppInstanceArn: str
     ) -> GetAppInstanceRetentionSettingsResponseTypeDef:
         """
-        Gets the retention settings for an `AppInstance` .
+        Gets the retention settings for an `AppInstance`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.get_app_instance_retention_settings)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#get_app_instance_retention_settings)
         """
 
     async def get_app_instance_streaming_configurations(
         self, *, AppInstanceArn: str
     ) -> GetAppInstanceStreamingConfigurationsResponseTypeDef:
         """
-        Gets the streaming settings for an `AppInstance` .
+        Gets the streaming settings for an `AppInstance`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.get_app_instance_streaming_configurations)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#get_app_instance_streaming_configurations)
         """
 
     async def get_attendee(self, *, MeetingId: str, AttendeeId: str) -> GetAttendeeResponseTypeDef:
         """
@@ -1399,15 +1399,15 @@
         """
 
     async def get_voice_connector_group(
         self, *, VoiceConnectorGroupId: str
     ) -> GetVoiceConnectorGroupResponseTypeDef:
         """
         Retrieves details for the specified Amazon Chime Voice Connector group, such as
-        timestamps,name, and associated `VoiceConnectorItems` .
+        timestamps,name, and associated `VoiceConnectorItems`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.get_voice_connector_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#get_voice_connector_group)
         """
 
     async def get_voice_connector_logging_configuration(
         self, *, VoiceConnectorId: str
@@ -1496,35 +1496,35 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#list_accounts)
         """
 
     async def list_app_instance_admins(
         self, *, AppInstanceArn: str, MaxResults: int = ..., NextToken: str = ...
     ) -> ListAppInstanceAdminsResponseTypeDef:
         """
-        Returns a list of the administrators in the `AppInstance` .
+        Returns a list of the administrators in the `AppInstance`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.list_app_instance_admins)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#list_app_instance_admins)
         """
 
     async def list_app_instance_users(
         self, *, AppInstanceArn: str, MaxResults: int = ..., NextToken: str = ...
     ) -> ListAppInstanceUsersResponseTypeDef:
         """
-        List all `AppInstanceUsers` created under a single `AppInstance` .
+        List all `AppInstanceUsers` created under a single `AppInstance`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.list_app_instance_users)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#list_app_instance_users)
         """
 
     async def list_app_instances(
         self, *, MaxResults: int = ..., NextToken: str = ...
     ) -> ListAppInstancesResponseTypeDef:
         """
-        Lists all Amazon Chime `AppInstance` s created under a single AWS account.
+        Lists all Amazon Chime `AppInstance`s created under a single AWS account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.list_app_instances)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#list_app_instances)
         """
 
     async def list_attendee_tags(
         self, *, MeetingId: str, AttendeeId: str
@@ -1657,15 +1657,15 @@
         *,
         AppInstanceUserArn: str = ...,
         MaxResults: int = ...,
         NextToken: str = ...,
         ChimeBearer: str = ...
     ) -> ListChannelsModeratedByAppInstanceUserResponseTypeDef:
         """
-        A list of the channels moderated by an `AppInstanceUser` .
+        A list of the channels moderated by an `AppInstanceUser`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.list_channels_moderated_by_app_instance_user)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#list_channels_moderated_by_app_instance_user)
         """
 
     async def list_media_capture_pipelines(
         self, *, NextToken: str = ..., MaxResults: int = ...
@@ -1871,15 +1871,15 @@
     async def put_app_instance_streaming_configurations(
         self,
         *,
         AppInstanceArn: str,
         AppInstanceStreamingConfigurations: Sequence[AppInstanceStreamingConfigurationTypeDef]
     ) -> PutAppInstanceStreamingConfigurationsResponseTypeDef:
         """
-        The data streaming configurations of an `AppInstance` .
+        The data streaming configurations of an `AppInstance`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.put_app_instance_streaming_configurations)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#put_app_instance_streaming_configurations)
         """
 
     async def put_events_configuration(
         self,
@@ -2053,15 +2053,15 @@
         """
 
     async def restore_phone_number(
         self, *, PhoneNumberId: str
     ) -> RestorePhoneNumberResponseTypeDef:
         """
         Moves a phone number from the **Deletion queue** back into the phone number
-        **Inventory** .
+        **Inventory**.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.restore_phone_number)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#restore_phone_number)
         """
 
     async def search_available_phone_numbers(
         self,
@@ -2100,23 +2100,23 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#send_channel_message)
         """
 
     async def start_meeting_transcription(
         self, *, MeetingId: str, TranscriptionConfiguration: TranscriptionConfigurationTypeDef
     ) -> Dict[str, Any]:
         """
-        Starts transcription for the specified `meetingId` .
+        Starts transcription for the specified `meetingId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.start_meeting_transcription)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#start_meeting_transcription)
         """
 
     async def stop_meeting_transcription(self, *, MeetingId: str) -> Dict[str, Any]:
         """
-        Stops transcription for the specified `meetingId` .
+        Stops transcription for the specified `meetingId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.stop_meeting_transcription)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#stop_meeting_transcription)
         """
 
     async def tag_attendee(
         self, *, MeetingId: str, AttendeeId: str, Tags: Sequence[TagTypeDef]
```

### Comparing `types-aiobotocore-chime-2.5.0.post1/types_aiobotocore_chime/client.pyi` & `types-aiobotocore-chime-2.5.1/types_aiobotocore_chime/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -634,15 +634,15 @@
         ToPhoneNumber: str,
         SipMediaApplicationId: str,
         SipHeaders: Mapping[str, str] = ...
     ) -> CreateSipMediaApplicationCallResponseTypeDef:
         """
         Creates an outbound call to a phone number from the phone number specified in
         the request, and it invokes the endpoint of the specified
-        `sipMediaApplicationId` .
+        `sipMediaApplicationId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.create_sip_media_application_call)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#create_sip_media_application_call)
         """
     async def create_sip_rule(
         self,
         *,
@@ -710,24 +710,24 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.delete_app_instance_admin)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#delete_app_instance_admin)
         """
     async def delete_app_instance_streaming_configurations(
         self, *, AppInstanceArn: str
     ) -> EmptyResponseMetadataTypeDef:
         """
-        Deletes the streaming configurations of an `AppInstance` .
+        Deletes the streaming configurations of an `AppInstance`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.delete_app_instance_streaming_configurations)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#delete_app_instance_streaming_configurations)
         """
     async def delete_app_instance_user(
         self, *, AppInstanceUserArn: str
     ) -> EmptyResponseMetadataTypeDef:
         """
-        Deletes an `AppInstanceUser` .
+        Deletes an `AppInstanceUser`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.delete_app_instance_user)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#delete_app_instance_user)
         """
     async def delete_attendee(
         self, *, MeetingId: str, AttendeeId: str
     ) -> EmptyResponseMetadataTypeDef:
@@ -933,42 +933,42 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.delete_voice_connector_termination_credentials)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#delete_voice_connector_termination_credentials)
         """
     async def describe_app_instance(
         self, *, AppInstanceArn: str
     ) -> DescribeAppInstanceResponseTypeDef:
         """
-        Returns the full details of an `AppInstance` .
+        Returns the full details of an `AppInstance`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.describe_app_instance)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#describe_app_instance)
         """
     async def describe_app_instance_admin(
         self, *, AppInstanceAdminArn: str, AppInstanceArn: str
     ) -> DescribeAppInstanceAdminResponseTypeDef:
         """
-        Returns the full details of an `AppInstanceAdmin` .
+        Returns the full details of an `AppInstanceAdmin`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.describe_app_instance_admin)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#describe_app_instance_admin)
         """
     async def describe_app_instance_user(
         self, *, AppInstanceUserArn: str
     ) -> DescribeAppInstanceUserResponseTypeDef:
         """
-        Returns the full details of an `AppInstanceUser` .
+        Returns the full details of an `AppInstanceUser`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.describe_app_instance_user)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#describe_app_instance_user)
         """
     async def describe_channel(
         self, *, ChannelArn: str, ChimeBearer: str = ...
     ) -> DescribeChannelResponseTypeDef:
         """
-        Returns the full details of a channel in an Amazon Chime `AppInstance` .
+        Returns the full details of a channel in an Amazon Chime `AppInstance`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.describe_channel)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#describe_channel)
         """
     async def describe_channel_ban(
         self, *, ChannelArn: str, MemberArn: str, ChimeBearer: str = ...
     ) -> DescribeChannelBanResponseTypeDef:
@@ -988,25 +988,25 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#describe_channel_membership)
         """
     async def describe_channel_membership_for_app_instance_user(
         self, *, ChannelArn: str, AppInstanceUserArn: str, ChimeBearer: str = ...
     ) -> DescribeChannelMembershipForAppInstanceUserResponseTypeDef:
         """
         Returns the details of a channel based on the membership of the specified
-        `AppInstanceUser` .
+        `AppInstanceUser`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.describe_channel_membership_for_app_instance_user)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#describe_channel_membership_for_app_instance_user)
         """
     async def describe_channel_moderated_by_app_instance_user(
         self, *, ChannelArn: str, AppInstanceUserArn: str, ChimeBearer: str = ...
     ) -> DescribeChannelModeratedByAppInstanceUserResponseTypeDef:
         """
         Returns the full details of a channel moderated by the specified
-        `AppInstanceUser` .
+        `AppInstanceUser`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.describe_channel_moderated_by_app_instance_user)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#describe_channel_moderated_by_app_instance_user)
         """
     async def describe_channel_moderator(
         self, *, ChannelArn: str, ChannelModeratorArn: str, ChimeBearer: str = ...
     ) -> DescribeChannelModeratorResponseTypeDef:
@@ -1085,24 +1085,24 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.get_account_settings)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#get_account_settings)
         """
     async def get_app_instance_retention_settings(
         self, *, AppInstanceArn: str
     ) -> GetAppInstanceRetentionSettingsResponseTypeDef:
         """
-        Gets the retention settings for an `AppInstance` .
+        Gets the retention settings for an `AppInstance`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.get_app_instance_retention_settings)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#get_app_instance_retention_settings)
         """
     async def get_app_instance_streaming_configurations(
         self, *, AppInstanceArn: str
     ) -> GetAppInstanceStreamingConfigurationsResponseTypeDef:
         """
-        Gets the streaming settings for an `AppInstance` .
+        Gets the streaming settings for an `AppInstance`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.get_app_instance_streaming_configurations)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#get_app_instance_streaming_configurations)
         """
     async def get_attendee(self, *, MeetingId: str, AttendeeId: str) -> GetAttendeeResponseTypeDef:
         """
         Gets the Amazon Chime SDK attendee details for a specified meeting ID and
@@ -1289,15 +1289,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#get_voice_connector_emergency_calling_configuration)
         """
     async def get_voice_connector_group(
         self, *, VoiceConnectorGroupId: str
     ) -> GetVoiceConnectorGroupResponseTypeDef:
         """
         Retrieves details for the specified Amazon Chime Voice Connector group, such as
-        timestamps,name, and associated `VoiceConnectorItems` .
+        timestamps,name, and associated `VoiceConnectorItems`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.get_voice_connector_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#get_voice_connector_group)
         """
     async def get_voice_connector_logging_configuration(
         self, *, VoiceConnectorId: str
     ) -> GetVoiceConnectorLoggingConfigurationResponseTypeDef:
@@ -1377,33 +1377,33 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.list_accounts)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#list_accounts)
         """
     async def list_app_instance_admins(
         self, *, AppInstanceArn: str, MaxResults: int = ..., NextToken: str = ...
     ) -> ListAppInstanceAdminsResponseTypeDef:
         """
-        Returns a list of the administrators in the `AppInstance` .
+        Returns a list of the administrators in the `AppInstance`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.list_app_instance_admins)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#list_app_instance_admins)
         """
     async def list_app_instance_users(
         self, *, AppInstanceArn: str, MaxResults: int = ..., NextToken: str = ...
     ) -> ListAppInstanceUsersResponseTypeDef:
         """
-        List all `AppInstanceUsers` created under a single `AppInstance` .
+        List all `AppInstanceUsers` created under a single `AppInstance`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.list_app_instance_users)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#list_app_instance_users)
         """
     async def list_app_instances(
         self, *, MaxResults: int = ..., NextToken: str = ...
     ) -> ListAppInstancesResponseTypeDef:
         """
-        Lists all Amazon Chime `AppInstance` s created under a single AWS account.
+        Lists all Amazon Chime `AppInstance`s created under a single AWS account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.list_app_instances)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#list_app_instances)
         """
     async def list_attendee_tags(
         self, *, MeetingId: str, AttendeeId: str
     ) -> ListAttendeeTagsResponseTypeDef:
@@ -1526,15 +1526,15 @@
         *,
         AppInstanceUserArn: str = ...,
         MaxResults: int = ...,
         NextToken: str = ...,
         ChimeBearer: str = ...
     ) -> ListChannelsModeratedByAppInstanceUserResponseTypeDef:
         """
-        A list of the channels moderated by an `AppInstanceUser` .
+        A list of the channels moderated by an `AppInstanceUser`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.list_channels_moderated_by_app_instance_user)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#list_channels_moderated_by_app_instance_user)
         """
     async def list_media_capture_pipelines(
         self, *, NextToken: str = ..., MaxResults: int = ...
     ) -> ListMediaCapturePipelinesResponseTypeDef:
@@ -1721,15 +1721,15 @@
     async def put_app_instance_streaming_configurations(
         self,
         *,
         AppInstanceArn: str,
         AppInstanceStreamingConfigurations: Sequence[AppInstanceStreamingConfigurationTypeDef]
     ) -> PutAppInstanceStreamingConfigurationsResponseTypeDef:
         """
-        The data streaming configurations of an `AppInstance` .
+        The data streaming configurations of an `AppInstance`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.put_app_instance_streaming_configurations)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#put_app_instance_streaming_configurations)
         """
     async def put_events_configuration(
         self,
         *,
@@ -1887,15 +1887,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#reset_personal_pin)
         """
     async def restore_phone_number(
         self, *, PhoneNumberId: str
     ) -> RestorePhoneNumberResponseTypeDef:
         """
         Moves a phone number from the **Deletion queue** back into the phone number
-        **Inventory** .
+        **Inventory**.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.restore_phone_number)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#restore_phone_number)
         """
     async def search_available_phone_numbers(
         self,
         *,
@@ -1931,22 +1931,22 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.send_channel_message)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#send_channel_message)
         """
     async def start_meeting_transcription(
         self, *, MeetingId: str, TranscriptionConfiguration: TranscriptionConfigurationTypeDef
     ) -> Dict[str, Any]:
         """
-        Starts transcription for the specified `meetingId` .
+        Starts transcription for the specified `meetingId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.start_meeting_transcription)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#start_meeting_transcription)
         """
     async def stop_meeting_transcription(self, *, MeetingId: str) -> Dict[str, Any]:
         """
-        Stops transcription for the specified `meetingId` .
+        Stops transcription for the specified `meetingId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Client.stop_meeting_transcription)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/client/#stop_meeting_transcription)
         """
     async def tag_attendee(
         self, *, MeetingId: str, AttendeeId: str, Tags: Sequence[TagTypeDef]
     ) -> EmptyResponseMetadataTypeDef:
```

### Comparing `types-aiobotocore-chime-2.5.0.post1/types_aiobotocore_chime/literals.py` & `types-aiobotocore-chime-2.5.1/types_aiobotocore_chime/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -154,18 +154,20 @@
     "de-DE",
     "en-AU",
     "en-GB",
     "en-US",
     "es-US",
     "fr-CA",
     "fr-FR",
+    "hi-IN",
     "it-IT",
     "ja-JP",
     "ko-KR",
     "pt-BR",
+    "th-TH",
     "zh-CN",
 ]
 TranscribeMedicalContentIdentificationTypeType = Literal["PHI"]
 TranscribeMedicalLanguageCodeType = Literal["en-US"]
 TranscribeMedicalRegionType = Literal[
     "ap-southeast-2", "auto", "ca-central-1", "eu-west-1", "us-east-1", "us-east-2", "us-west-2"
 ]
@@ -251,14 +253,15 @@
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
@@ -337,14 +340,15 @@
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
@@ -355,14 +359,15 @@
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
@@ -398,14 +403,15 @@
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
@@ -424,16 +430,19 @@
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
@@ -517,15 +526,17 @@
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

### Comparing `types-aiobotocore-chime-2.5.0.post1/types_aiobotocore_chime/literals.pyi` & `types-aiobotocore-chime-2.5.1/types_aiobotocore_chime/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -152,18 +152,20 @@
     "de-DE",
     "en-AU",
     "en-GB",
     "en-US",
     "es-US",
     "fr-CA",
     "fr-FR",
+    "hi-IN",
     "it-IT",
     "ja-JP",
     "ko-KR",
     "pt-BR",
+    "th-TH",
     "zh-CN",
 ]
 TranscribeMedicalContentIdentificationTypeType = Literal["PHI"]
 TranscribeMedicalLanguageCodeType = Literal["en-US"]
 TranscribeMedicalRegionType = Literal[
     "ap-southeast-2", "auto", "ca-central-1", "eu-west-1", "us-east-1", "us-east-2", "us-west-2"
 ]
@@ -249,14 +251,15 @@
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
@@ -335,14 +338,15 @@
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
@@ -353,14 +357,15 @@
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
@@ -396,14 +401,15 @@
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
@@ -422,16 +428,19 @@
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
@@ -515,15 +524,17 @@
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

### Comparing `types-aiobotocore-chime-2.5.0.post1/types_aiobotocore_chime/paginator.py` & `types-aiobotocore-chime-2.5.1/types_aiobotocore_chime/paginator.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -18,72 +18,61 @@
     with session.create_client("chime") as client:
         client: ChimeClient
 
         list_accounts_paginator: ListAccountsPaginator = client.get_paginator("list_accounts")
         list_users_paginator: ListUsersPaginator = client.get_paginator("list_users")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import UserTypeType
 from .type_defs import ListAccountsResponseTypeDef, ListUsersResponseTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListAccountsPaginator", "ListUsersPaginator")
 
-
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
-
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
-
 class ListAccountsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Paginator.ListAccounts)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/paginators/#listaccountspaginator)
     """
 
     def paginate(
         self,
         *,
         Name: str = ...,
         UserEmail: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAccountsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Paginator.ListAccounts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/paginators/#listaccountspaginator)
         """
 
-
 class ListUsersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Paginator.ListUsers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/paginators/#listuserspaginator)
     """
 
     def paginate(
         self,
         *,
         AccountId: str,
         UserEmail: str = ...,
         UserType: UserTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListUsersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Paginator.ListUsers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/paginators/#listuserspaginator)
         """
```

### Comparing `types-aiobotocore-chime-2.5.0.post1/types_aiobotocore_chime/paginator.pyi` & `types-aiobotocore-chime-2.5.1/types_aiobotocore_chime/paginator.py`

 * *Files 6% similar despite different names*

```diff
@@ -18,67 +18,65 @@
     with session.create_client("chime") as client:
         client: ChimeClient
 
         list_accounts_paginator: ListAccountsPaginator = client.get_paginator("list_accounts")
         list_users_paginator: ListUsersPaginator = client.get_paginator("list_users")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import UserTypeType
 from .type_defs import ListAccountsResponseTypeDef, ListUsersResponseTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListAccountsPaginator", "ListUsersPaginator")
 
+
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
+
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
+
 class ListAccountsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Paginator.ListAccounts)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/paginators/#listaccountspaginator)
     """
 
     def paginate(
         self,
         *,
         Name: str = ...,
         UserEmail: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAccountsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Paginator.ListAccounts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/paginators/#listaccountspaginator)
         """
 
+
 class ListUsersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Paginator.ListUsers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/paginators/#listuserspaginator)
     """
 
     def paginate(
         self,
         *,
         AccountId: str,
         UserEmail: str = ...,
         UserType: UserTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListUsersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime.Paginator.ListUsers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/paginators/#listuserspaginator)
         """
```

### Comparing `types-aiobotocore-chime-2.5.0.post1/types_aiobotocore_chime/type_defs.py` & `types-aiobotocore-chime-2.5.1/types_aiobotocore_chime/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -85,15 +85,14 @@
     "AppInstanceUserTypeDef",
     "AudioArtifactsConfigurationTypeDef",
     "ContentArtifactsConfigurationTypeDef",
     "VideoArtifactsConfigurationTypeDef",
     "AssociatePhoneNumberWithUserRequestRequestTypeDef",
     "AssociatePhoneNumbersWithVoiceConnectorGroupRequestRequestTypeDef",
     "PhoneNumberErrorTypeDef",
-    "ResponseMetadataTypeDef",
     "AssociatePhoneNumbersWithVoiceConnectorRequestRequestTypeDef",
     "AttendeeTypeDef",
     "CreateAttendeeErrorTypeDef",
     "BatchCreateChannelMembershipErrorTypeDef",
     "BatchCreateChannelMembershipRequestRequestTypeDef",
     "MembershipItemTypeDef",
     "MemberErrorTypeDef",
@@ -106,19 +105,23 @@
     "BusinessCallingSettingsTypeDef",
     "CandidateAddressTypeDef",
     "ChannelSummaryTypeDef",
     "ConversationRetentionSettingsTypeDef",
     "CreateAccountRequestRequestTypeDef",
     "CreateAppInstanceAdminRequestRequestTypeDef",
     "TagTypeDef",
+    "CreateAppInstanceResponseTypeDef",
+    "CreateAppInstanceUserResponseTypeDef",
     "CreateBotRequestRequestTypeDef",
     "CreateChannelBanRequestRequestTypeDef",
     "CreateChannelMembershipRequestRequestTypeDef",
     "CreateChannelModeratorRequestRequestTypeDef",
+    "CreateChannelResponseTypeDef",
     "CreateMeetingDialOutRequestRequestTypeDef",
+    "CreateMeetingDialOutResponseTypeDef",
     "MeetingNotificationConfigurationTypeDef",
     "CreatePhoneNumberOrderRequestRequestTypeDef",
     "GeoMatchParamsTypeDef",
     "CreateRoomMembershipRequestRequestTypeDef",
     "CreateRoomRequestRequestTypeDef",
     "RoomTypeDef",
     "CreateSipMediaApplicationCallRequestRequestTypeDef",
@@ -168,14 +171,15 @@
     "DescribeChannelModeratedByAppInstanceUserRequestRequestTypeDef",
     "DescribeChannelModeratorRequestRequestTypeDef",
     "DescribeChannelRequestRequestTypeDef",
     "DisassociatePhoneNumberFromUserRequestRequestTypeDef",
     "DisassociatePhoneNumbersFromVoiceConnectorGroupRequestRequestTypeDef",
     "DisassociatePhoneNumbersFromVoiceConnectorRequestRequestTypeDef",
     "DisassociateSigninDelegateGroupsFromAccountRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EngineTranscribeMedicalSettingsTypeDef",
     "EngineTranscribeSettingsTypeDef",
     "EventsConfigurationTypeDef",
     "GetAccountRequestRequestTypeDef",
     "GetAccountSettingsRequestRequestTypeDef",
     "GetAppInstanceRetentionSettingsRequestRequestTypeDef",
     "GetAppInstanceStreamingConfigurationsRequestRequestTypeDef",
@@ -185,14 +189,15 @@
     "GetEventsConfigurationRequestRequestTypeDef",
     "VoiceConnectorSettingsTypeDef",
     "GetMediaCapturePipelineRequestRequestTypeDef",
     "GetMeetingRequestRequestTypeDef",
     "MessagingSessionEndpointTypeDef",
     "GetPhoneNumberOrderRequestRequestTypeDef",
     "GetPhoneNumberRequestRequestTypeDef",
+    "GetPhoneNumberSettingsResponseTypeDef",
     "GetProxySessionRequestRequestTypeDef",
     "GetRetentionSettingsRequestRequestTypeDef",
     "GetRoomRequestRequestTypeDef",
     "GetSipMediaApplicationLoggingConfigurationRequestRequestTypeDef",
     "SipMediaApplicationLoggingConfigurationTypeDef",
     "GetSipMediaApplicationRequestRequestTypeDef",
     "GetSipRuleRequestRequestTypeDef",
@@ -209,15 +214,15 @@
     "GetVoiceConnectorStreamingConfigurationRequestRequestTypeDef",
     "GetVoiceConnectorTerminationHealthRequestRequestTypeDef",
     "TerminationHealthTypeDef",
     "GetVoiceConnectorTerminationRequestRequestTypeDef",
     "TerminationTypeDef",
     "InviteTypeDef",
     "InviteUsersRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListAccountsRequestListAccountsPaginateTypeDef",
     "ListAccountsRequestRequestTypeDef",
     "ListAppInstanceAdminsRequestRequestTypeDef",
     "ListAppInstanceUsersRequestRequestTypeDef",
     "ListAppInstancesRequestRequestTypeDef",
     "ListAttendeeTagsRequestRequestTypeDef",
     "ListAttendeesRequestRequestTypeDef",
     "ListBotsRequestRequestTypeDef",
@@ -237,59 +242,72 @@
     "ListRoomMembershipsRequestRequestTypeDef",
     "ListRoomsRequestRequestTypeDef",
     "ListSipMediaApplicationsRequestRequestTypeDef",
     "ListSipRulesRequestRequestTypeDef",
     "ListSupportedPhoneNumberCountriesRequestRequestTypeDef",
     "PhoneNumberCountryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListUsersRequestListUsersPaginateTypeDef",
     "ListUsersRequestRequestTypeDef",
     "ListVoiceConnectorGroupsRequestRequestTypeDef",
     "ListVoiceConnectorTerminationCredentialsRequestRequestTypeDef",
+    "ListVoiceConnectorTerminationCredentialsResponseTypeDef",
     "ListVoiceConnectorsRequestRequestTypeDef",
     "LogoutUserRequestRequestTypeDef",
     "MediaPlacementTypeDef",
     "MemberTypeDef",
     "OrderedPhoneNumberTypeDef",
     "OriginationRouteTypeDef",
+    "PaginatorConfigTypeDef",
     "ParticipantTypeDef",
     "PhoneNumberAssociationTypeDef",
     "PhoneNumberCapabilitiesTypeDef",
     "PutEventsConfigurationRequestRequestTypeDef",
     "PutVoiceConnectorProxyRequestRequestTypeDef",
     "RedactChannelMessageRequestRequestTypeDef",
+    "RedactChannelMessageResponseTypeDef",
     "RedactConversationMessageRequestRequestTypeDef",
     "RedactRoomMessageRequestRequestTypeDef",
     "RegenerateSecurityTokenRequestRequestTypeDef",
     "ResetPersonalPINRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "RestorePhoneNumberRequestRequestTypeDef",
     "RoomRetentionSettingsTypeDef",
     "SearchAvailablePhoneNumbersRequestRequestTypeDef",
+    "SearchAvailablePhoneNumbersResponseTypeDef",
     "SelectedVideoStreamsTypeDef",
     "SendChannelMessageRequestRequestTypeDef",
+    "SendChannelMessageResponseTypeDef",
     "StopMeetingTranscriptionRequestRequestTypeDef",
     "StreamingNotificationTargetTypeDef",
     "TelephonySettingsTypeDef",
     "UntagAttendeeRequestRequestTypeDef",
     "UntagMeetingRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateAccountRequestRequestTypeDef",
     "UpdateAppInstanceRequestRequestTypeDef",
+    "UpdateAppInstanceResponseTypeDef",
     "UpdateAppInstanceUserRequestRequestTypeDef",
+    "UpdateAppInstanceUserResponseTypeDef",
     "UpdateBotRequestRequestTypeDef",
     "UpdateChannelMessageRequestRequestTypeDef",
+    "UpdateChannelMessageResponseTypeDef",
     "UpdateChannelReadMarkerRequestRequestTypeDef",
+    "UpdateChannelReadMarkerResponseTypeDef",
     "UpdateChannelRequestRequestTypeDef",
+    "UpdateChannelResponseTypeDef",
     "UpdatePhoneNumberRequestRequestTypeDef",
     "UpdatePhoneNumberSettingsRequestRequestTypeDef",
     "UpdateProxySessionRequestRequestTypeDef",
     "UpdateRoomMembershipRequestRequestTypeDef",
     "UpdateRoomRequestRequestTypeDef",
     "UpdateSipMediaApplicationCallRequestRequestTypeDef",
     "UpdateVoiceConnectorRequestRequestTypeDef",
     "ValidateE911AddressRequestRequestTypeDef",
+    "GetAccountSettingsResponseTypeDef",
     "UpdateAccountSettingsRequestRequestTypeDef",
     "AccountTypeDef",
     "AssociateSigninDelegateGroupsWithAccountRequestRequestTypeDef",
     "UpdateUserRequestItemTypeDef",
     "UpdateUserRequestRequestTypeDef",
     "UserTypeDef",
     "AppInstanceAdminSummaryTypeDef",
@@ -300,49 +318,33 @@
     "ChannelMembershipSummaryTypeDef",
     "ChannelMembershipTypeDef",
     "ChannelMessageSummaryTypeDef",
     "ChannelMessageTypeDef",
     "ChannelModeratorSummaryTypeDef",
     "ChannelModeratorTypeDef",
     "ChannelTypeDef",
+    "CreateAppInstanceAdminResponseTypeDef",
+    "CreateChannelBanResponseTypeDef",
+    "CreateChannelMembershipResponseTypeDef",
+    "CreateChannelModeratorResponseTypeDef",
     "AppInstanceRetentionSettingsTypeDef",
+    "GetAppInstanceStreamingConfigurationsResponseTypeDef",
     "PutAppInstanceStreamingConfigurationsRequestRequestTypeDef",
+    "PutAppInstanceStreamingConfigurationsResponseTypeDef",
+    "ListAppInstancesResponseTypeDef",
+    "DescribeAppInstanceResponseTypeDef",
+    "ListAppInstanceUsersResponseTypeDef",
+    "DescribeAppInstanceUserResponseTypeDef",
     "ArtifactsConfigurationTypeDef",
     "AssociatePhoneNumbersWithVoiceConnectorGroupResponseTypeDef",
     "AssociatePhoneNumbersWithVoiceConnectorResponseTypeDef",
     "BatchDeletePhoneNumberResponseTypeDef",
     "BatchUpdatePhoneNumberResponseTypeDef",
-    "CreateAppInstanceAdminResponseTypeDef",
-    "CreateAppInstanceResponseTypeDef",
-    "CreateAppInstanceUserResponseTypeDef",
-    "CreateChannelBanResponseTypeDef",
-    "CreateChannelMembershipResponseTypeDef",
-    "CreateChannelModeratorResponseTypeDef",
-    "CreateChannelResponseTypeDef",
-    "CreateMeetingDialOutResponseTypeDef",
-    "DescribeAppInstanceResponseTypeDef",
-    "DescribeAppInstanceUserResponseTypeDef",
     "DisassociatePhoneNumbersFromVoiceConnectorGroupResponseTypeDef",
     "DisassociatePhoneNumbersFromVoiceConnectorResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetAccountSettingsResponseTypeDef",
-    "GetAppInstanceStreamingConfigurationsResponseTypeDef",
-    "GetPhoneNumberSettingsResponseTypeDef",
-    "ListAppInstanceUsersResponseTypeDef",
-    "ListAppInstancesResponseTypeDef",
-    "ListVoiceConnectorTerminationCredentialsResponseTypeDef",
-    "PutAppInstanceStreamingConfigurationsResponseTypeDef",
-    "RedactChannelMessageResponseTypeDef",
-    "SearchAvailablePhoneNumbersResponseTypeDef",
-    "SendChannelMessageResponseTypeDef",
-    "UpdateAppInstanceResponseTypeDef",
-    "UpdateAppInstanceUserResponseTypeDef",
-    "UpdateChannelMessageResponseTypeDef",
-    "UpdateChannelReadMarkerResponseTypeDef",
-    "UpdateChannelResponseTypeDef",
     "CreateAttendeeResponseTypeDef",
     "GetAttendeeResponseTypeDef",
     "ListAttendeesResponseTypeDef",
     "BatchCreateAttendeeResponseTypeDef",
     "BatchCreateRoomMembershipRequestRequestTypeDef",
     "BatchCreateRoomMembershipResponseTypeDef",
     "BatchSuspendUserResponseTypeDef",
@@ -407,16 +409,14 @@
     "GetVoiceConnectorProxyResponseTypeDef",
     "PutVoiceConnectorProxyResponseTypeDef",
     "GetVoiceConnectorTerminationHealthResponseTypeDef",
     "GetVoiceConnectorTerminationResponseTypeDef",
     "PutVoiceConnectorTerminationRequestRequestTypeDef",
     "PutVoiceConnectorTerminationResponseTypeDef",
     "InviteUsersResponseTypeDef",
-    "ListAccountsRequestListAccountsPaginateTypeDef",
-    "ListUsersRequestListUsersPaginateTypeDef",
     "ListSupportedPhoneNumberCountriesResponseTypeDef",
     "MeetingTypeDef",
     "RoomMembershipTypeDef",
     "PhoneNumberOrderTypeDef",
     "OriginationTypeDef",
     "ProxySessionTypeDef",
     "PhoneNumberTypeDef",
@@ -716,25 +716,14 @@
         "PhoneNumberId": str,
         "ErrorCode": ErrorCodeType,
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
 _RequiredAssociatePhoneNumbersWithVoiceConnectorRequestRequestTypeDef = TypedDict(
     "_RequiredAssociatePhoneNumbersWithVoiceConnectorRequestRequestTypeDef",
     {
         "VoiceConnectorId": str,
         "E164PhoneNumbers": Sequence[str],
     },
 )
@@ -960,14 +949,30 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
+CreateAppInstanceResponseTypeDef = TypedDict(
+    "CreateAppInstanceResponseTypeDef",
+    {
+        "AppInstanceArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateAppInstanceUserResponseTypeDef = TypedDict(
+    "CreateAppInstanceUserResponseTypeDef",
+    {
+        "AppInstanceUserArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateBotRequestRequestTypeDef = TypedDict(
     "_RequiredCreateBotRequestRequestTypeDef",
     {
         "AccountId": str,
         "DisplayName": str,
     },
 )
@@ -1051,24 +1056,40 @@
 class CreateChannelModeratorRequestRequestTypeDef(
     _RequiredCreateChannelModeratorRequestRequestTypeDef,
     _OptionalCreateChannelModeratorRequestRequestTypeDef,
 ):
     pass
 
 
+CreateChannelResponseTypeDef = TypedDict(
+    "CreateChannelResponseTypeDef",
+    {
+        "ChannelArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateMeetingDialOutRequestRequestTypeDef = TypedDict(
     "CreateMeetingDialOutRequestRequestTypeDef",
     {
         "MeetingId": str,
         "FromPhoneNumber": str,
         "ToPhoneNumber": str,
         "JoinToken": str,
     },
 )
 
+CreateMeetingDialOutResponseTypeDef = TypedDict(
+    "CreateMeetingDialOutResponseTypeDef",
+    {
+        "TransactionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 MeetingNotificationConfigurationTypeDef = TypedDict(
     "MeetingNotificationConfigurationTypeDef",
     {
         "SnsTopicArn": str,
         "SqsQueueArn": str,
     },
     total=False,
@@ -1767,14 +1788,21 @@
     "DisassociateSigninDelegateGroupsFromAccountRequestRequestTypeDef",
     {
         "AccountId": str,
         "GroupNames": Sequence[str],
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredEngineTranscribeMedicalSettingsTypeDef = TypedDict(
     "_RequiredEngineTranscribeMedicalSettingsTypeDef",
     {
         "LanguageCode": Literal["en-US"],
         "Specialty": TranscribeMedicalSpecialtyType,
         "Type": TranscribeMedicalTypeType,
     },
@@ -1792,44 +1820,37 @@
 
 class EngineTranscribeMedicalSettingsTypeDef(
     _RequiredEngineTranscribeMedicalSettingsTypeDef, _OptionalEngineTranscribeMedicalSettingsTypeDef
 ):
     pass
 
 
-_RequiredEngineTranscribeSettingsTypeDef = TypedDict(
-    "_RequiredEngineTranscribeSettingsTypeDef",
+EngineTranscribeSettingsTypeDef = TypedDict(
+    "EngineTranscribeSettingsTypeDef",
     {
         "LanguageCode": TranscribeLanguageCodeType,
-    },
-)
-_OptionalEngineTranscribeSettingsTypeDef = TypedDict(
-    "_OptionalEngineTranscribeSettingsTypeDef",
-    {
         "VocabularyFilterMethod": TranscribeVocabularyFilterMethodType,
         "VocabularyFilterName": str,
         "VocabularyName": str,
         "Region": TranscribeRegionType,
         "EnablePartialResultsStabilization": bool,
         "PartialResultsStability": TranscribePartialResultsStabilityType,
         "ContentIdentificationType": Literal["PII"],
         "ContentRedactionType": Literal["PII"],
         "PiiEntityTypes": str,
         "LanguageModelName": str,
+        "IdentifyLanguage": bool,
+        "LanguageOptions": str,
+        "PreferredLanguage": TranscribeLanguageCodeType,
+        "VocabularyNames": str,
+        "VocabularyFilterNames": str,
     },
     total=False,
 )
 
-
-class EngineTranscribeSettingsTypeDef(
-    _RequiredEngineTranscribeSettingsTypeDef, _OptionalEngineTranscribeSettingsTypeDef
-):
-    pass
-
-
 EventsConfigurationTypeDef = TypedDict(
     "EventsConfigurationTypeDef",
     {
         "BotId": str,
         "OutboundEventsHTTPSEndpoint": str,
         "LambdaFunctionArn": str,
     },
@@ -1950,14 +1971,23 @@
 GetPhoneNumberRequestRequestTypeDef = TypedDict(
     "GetPhoneNumberRequestRequestTypeDef",
     {
         "PhoneNumberId": str,
     },
 )
 
+GetPhoneNumberSettingsResponseTypeDef = TypedDict(
+    "GetPhoneNumberSettingsResponseTypeDef",
+    {
+        "CallingName": str,
+        "CallingNameUpdatedTimestamp": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetProxySessionRequestRequestTypeDef = TypedDict(
     "GetProxySessionRequestRequestTypeDef",
     {
         "VoiceConnectorId": str,
         "ProxySessionId": str,
     },
 )
@@ -2155,20 +2185,20 @@
 
 class InviteUsersRequestRequestTypeDef(
     _RequiredInviteUsersRequestRequestTypeDef, _OptionalInviteUsersRequestRequestTypeDef
 ):
     pass
 
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListAccountsRequestListAccountsPaginateTypeDef = TypedDict(
+    "ListAccountsRequestListAccountsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "Name": str,
+        "UserEmail": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListAccountsRequestRequestTypeDef = TypedDict(
     "ListAccountsRequestRequestTypeDef",
     {
@@ -2587,14 +2617,38 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
     },
 )
 
+_RequiredListUsersRequestListUsersPaginateTypeDef = TypedDict(
+    "_RequiredListUsersRequestListUsersPaginateTypeDef",
+    {
+        "AccountId": str,
+    },
+)
+_OptionalListUsersRequestListUsersPaginateTypeDef = TypedDict(
+    "_OptionalListUsersRequestListUsersPaginateTypeDef",
+    {
+        "UserEmail": str,
+        "UserType": UserTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListUsersRequestListUsersPaginateTypeDef(
+    _RequiredListUsersRequestListUsersPaginateTypeDef,
+    _OptionalListUsersRequestListUsersPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListUsersRequestRequestTypeDef = TypedDict(
     "_RequiredListUsersRequestRequestTypeDef",
     {
         "AccountId": str,
     },
 )
 _OptionalListUsersRequestRequestTypeDef = TypedDict(
@@ -2627,14 +2681,22 @@
 ListVoiceConnectorTerminationCredentialsRequestRequestTypeDef = TypedDict(
     "ListVoiceConnectorTerminationCredentialsRequestRequestTypeDef",
     {
         "VoiceConnectorId": str,
     },
 )
 
+ListVoiceConnectorTerminationCredentialsResponseTypeDef = TypedDict(
+    "ListVoiceConnectorTerminationCredentialsResponseTypeDef",
+    {
+        "Usernames": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListVoiceConnectorsRequestRequestTypeDef = TypedDict(
     "ListVoiceConnectorsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
@@ -2692,14 +2754,24 @@
         "Protocol": OriginationRouteProtocolType,
         "Priority": int,
         "Weight": int,
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
 ParticipantTypeDef = TypedDict(
     "ParticipantTypeDef",
     {
         "PhoneNumber": str,
         "ProxyPhoneNumber": str,
     },
     total=False,
@@ -2796,14 +2868,23 @@
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
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RedactConversationMessageRequestRequestTypeDef = TypedDict(
     "RedactConversationMessageRequestRequestTypeDef",
     {
         "AccountId": str,
         "ConversationId": str,
         "MessageId": str,
     },
@@ -2830,14 +2911,25 @@
     "ResetPersonalPINRequestRequestTypeDef",
     {
         "AccountId": str,
         "UserId": str,
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
 RestorePhoneNumberRequestRequestTypeDef = TypedDict(
     "RestorePhoneNumberRequestRequestTypeDef",
     {
         "PhoneNumberId": str,
     },
 )
 
@@ -2860,14 +2952,23 @@
         "PhoneNumberType": PhoneNumberTypeType,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+SearchAvailablePhoneNumbersResponseTypeDef = TypedDict(
+    "SearchAvailablePhoneNumbersResponseTypeDef",
+    {
+        "E164PhoneNumbers": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 SelectedVideoStreamsTypeDef = TypedDict(
     "SelectedVideoStreamsTypeDef",
     {
         "AttendeeIds": Sequence[str],
         "ExternalUserIds": Sequence[str],
     },
     total=False,
@@ -2896,14 +2997,23 @@
 class SendChannelMessageRequestRequestTypeDef(
     _RequiredSendChannelMessageRequestRequestTypeDef,
     _OptionalSendChannelMessageRequestRequestTypeDef,
 ):
     pass
 
 
+SendChannelMessageResponseTypeDef = TypedDict(
+    "SendChannelMessageResponseTypeDef",
+    {
+        "ChannelArn": str,
+        "MessageId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopMeetingTranscriptionRequestRequestTypeDef = TypedDict(
     "StopMeetingTranscriptionRequestRequestTypeDef",
     {
         "MeetingId": str,
     },
 )
 
@@ -2988,14 +3098,22 @@
 
 class UpdateAppInstanceRequestRequestTypeDef(
     _RequiredUpdateAppInstanceRequestRequestTypeDef, _OptionalUpdateAppInstanceRequestRequestTypeDef
 ):
     pass
 
 
+UpdateAppInstanceResponseTypeDef = TypedDict(
+    "UpdateAppInstanceResponseTypeDef",
+    {
+        "AppInstanceArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateAppInstanceUserRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateAppInstanceUserRequestRequestTypeDef",
     {
         "AppInstanceUserArn": str,
         "Name": str,
     },
 )
@@ -3011,14 +3129,22 @@
 class UpdateAppInstanceUserRequestRequestTypeDef(
     _RequiredUpdateAppInstanceUserRequestRequestTypeDef,
     _OptionalUpdateAppInstanceUserRequestRequestTypeDef,
 ):
     pass
 
 
+UpdateAppInstanceUserResponseTypeDef = TypedDict(
+    "UpdateAppInstanceUserResponseTypeDef",
+    {
+        "AppInstanceUserArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateBotRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateBotRequestRequestTypeDef",
     {
         "AccountId": str,
         "BotId": str,
     },
 )
@@ -3058,14 +3184,23 @@
 class UpdateChannelMessageRequestRequestTypeDef(
     _RequiredUpdateChannelMessageRequestRequestTypeDef,
     _OptionalUpdateChannelMessageRequestRequestTypeDef,
 ):
     pass
 
 
+UpdateChannelMessageResponseTypeDef = TypedDict(
+    "UpdateChannelMessageResponseTypeDef",
+    {
+        "ChannelArn": str,
+        "MessageId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateChannelReadMarkerRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateChannelReadMarkerRequestRequestTypeDef",
     {
         "ChannelArn": str,
     },
 )
 _OptionalUpdateChannelReadMarkerRequestRequestTypeDef = TypedDict(
@@ -3080,14 +3215,22 @@
 class UpdateChannelReadMarkerRequestRequestTypeDef(
     _RequiredUpdateChannelReadMarkerRequestRequestTypeDef,
     _OptionalUpdateChannelReadMarkerRequestRequestTypeDef,
 ):
     pass
 
 
+UpdateChannelReadMarkerResponseTypeDef = TypedDict(
+    "UpdateChannelReadMarkerResponseTypeDef",
+    {
+        "ChannelArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateChannelRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateChannelRequestRequestTypeDef",
     {
         "ChannelArn": str,
         "Name": str,
         "Mode": ChannelModeType,
     },
@@ -3104,14 +3247,22 @@
 
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
 _RequiredUpdatePhoneNumberRequestRequestTypeDef = TypedDict(
     "_RequiredUpdatePhoneNumberRequestRequestTypeDef",
     {
         "PhoneNumberId": str,
     },
 )
 _OptionalUpdatePhoneNumberRequestRequestTypeDef = TypedDict(
@@ -3234,14 +3385,22 @@
         "City": str,
         "State": str,
         "Country": str,
         "PostalCode": str,
     },
 )
 
+GetAccountSettingsResponseTypeDef = TypedDict(
+    "GetAccountSettingsResponseTypeDef",
+    {
+        "AccountSettings": AccountSettingsTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateAccountSettingsRequestRequestTypeDef = TypedDict(
     "UpdateAccountSettingsRequestRequestTypeDef",
     {
         "AccountId": str,
         "AccountSettings": AccountSettingsTypeDef,
     },
 )
@@ -3491,337 +3650,205 @@
         "CreatedTimestamp": datetime,
         "LastMessageTimestamp": datetime,
         "LastUpdatedTimestamp": datetime,
     },
     total=False,
 )
 
-AppInstanceRetentionSettingsTypeDef = TypedDict(
-    "AppInstanceRetentionSettingsTypeDef",
-    {
-        "ChannelRetentionSettings": ChannelRetentionSettingsTypeDef,
-    },
-    total=False,
-)
-
-PutAppInstanceStreamingConfigurationsRequestRequestTypeDef = TypedDict(
-    "PutAppInstanceStreamingConfigurationsRequestRequestTypeDef",
-    {
-        "AppInstanceArn": str,
-        "AppInstanceStreamingConfigurations": Sequence[AppInstanceStreamingConfigurationTypeDef],
-    },
-)
-
-ArtifactsConfigurationTypeDef = TypedDict(
-    "ArtifactsConfigurationTypeDef",
-    {
-        "Audio": AudioArtifactsConfigurationTypeDef,
-        "Video": VideoArtifactsConfigurationTypeDef,
-        "Content": ContentArtifactsConfigurationTypeDef,
-    },
-)
-
-AssociatePhoneNumbersWithVoiceConnectorGroupResponseTypeDef = TypedDict(
-    "AssociatePhoneNumbersWithVoiceConnectorGroupResponseTypeDef",
-    {
-        "PhoneNumberErrors": List[PhoneNumberErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-AssociatePhoneNumbersWithVoiceConnectorResponseTypeDef = TypedDict(
-    "AssociatePhoneNumbersWithVoiceConnectorResponseTypeDef",
-    {
-        "PhoneNumberErrors": List[PhoneNumberErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-BatchDeletePhoneNumberResponseTypeDef = TypedDict(
-    "BatchDeletePhoneNumberResponseTypeDef",
-    {
-        "PhoneNumberErrors": List[PhoneNumberErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-BatchUpdatePhoneNumberResponseTypeDef = TypedDict(
-    "BatchUpdatePhoneNumberResponseTypeDef",
-    {
-        "PhoneNumberErrors": List[PhoneNumberErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 CreateAppInstanceAdminResponseTypeDef = TypedDict(
     "CreateAppInstanceAdminResponseTypeDef",
     {
         "AppInstanceAdmin": IdentityTypeDef,
         "AppInstanceArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateAppInstanceResponseTypeDef = TypedDict(
-    "CreateAppInstanceResponseTypeDef",
-    {
-        "AppInstanceArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateAppInstanceUserResponseTypeDef = TypedDict(
-    "CreateAppInstanceUserResponseTypeDef",
-    {
-        "AppInstanceUserArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateChannelBanResponseTypeDef = TypedDict(
     "CreateChannelBanResponseTypeDef",
     {
         "ChannelArn": str,
         "Member": IdentityTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateChannelMembershipResponseTypeDef = TypedDict(
     "CreateChannelMembershipResponseTypeDef",
     {
         "ChannelArn": str,
         "Member": IdentityTypeDef,
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
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-CreateChannelResponseTypeDef = TypedDict(
-    "CreateChannelResponseTypeDef",
-    {
-        "ChannelArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateMeetingDialOutResponseTypeDef = TypedDict(
-    "CreateMeetingDialOutResponseTypeDef",
-    {
-        "TransactionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeAppInstanceResponseTypeDef = TypedDict(
-    "DescribeAppInstanceResponseTypeDef",
-    {
-        "AppInstance": AppInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeAppInstanceUserResponseTypeDef = TypedDict(
-    "DescribeAppInstanceUserResponseTypeDef",
-    {
-        "AppInstanceUser": AppInstanceUserTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DisassociatePhoneNumbersFromVoiceConnectorGroupResponseTypeDef = TypedDict(
-    "DisassociatePhoneNumbersFromVoiceConnectorGroupResponseTypeDef",
-    {
-        "PhoneNumberErrors": List[PhoneNumberErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DisassociatePhoneNumbersFromVoiceConnectorResponseTypeDef = TypedDict(
-    "DisassociatePhoneNumbersFromVoiceConnectorResponseTypeDef",
-    {
-        "PhoneNumberErrors": List[PhoneNumberErrorTypeDef],
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
-GetAccountSettingsResponseTypeDef = TypedDict(
-    "GetAccountSettingsResponseTypeDef",
+AppInstanceRetentionSettingsTypeDef = TypedDict(
+    "AppInstanceRetentionSettingsTypeDef",
     {
-        "AccountSettings": AccountSettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ChannelRetentionSettings": ChannelRetentionSettingsTypeDef,
     },
+    total=False,
 )
 
 GetAppInstanceStreamingConfigurationsResponseTypeDef = TypedDict(
     "GetAppInstanceStreamingConfigurationsResponseTypeDef",
     {
         "AppInstanceStreamingConfigurations": List[AppInstanceStreamingConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetPhoneNumberSettingsResponseTypeDef = TypedDict(
-    "GetPhoneNumberSettingsResponseTypeDef",
+PutAppInstanceStreamingConfigurationsRequestRequestTypeDef = TypedDict(
+    "PutAppInstanceStreamingConfigurationsRequestRequestTypeDef",
     {
-        "CallingName": str,
-        "CallingNameUpdatedTimestamp": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "AppInstanceArn": str,
+        "AppInstanceStreamingConfigurations": Sequence[AppInstanceStreamingConfigurationTypeDef],
     },
 )
 
-ListAppInstanceUsersResponseTypeDef = TypedDict(
-    "ListAppInstanceUsersResponseTypeDef",
+PutAppInstanceStreamingConfigurationsResponseTypeDef = TypedDict(
+    "PutAppInstanceStreamingConfigurationsResponseTypeDef",
     {
-        "AppInstanceArn": str,
-        "AppInstanceUsers": List[AppInstanceUserSummaryTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "AppInstanceStreamingConfigurations": List[AppInstanceStreamingConfigurationTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAppInstancesResponseTypeDef = TypedDict(
     "ListAppInstancesResponseTypeDef",
     {
         "AppInstances": List[AppInstanceSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListVoiceConnectorTerminationCredentialsResponseTypeDef = TypedDict(
-    "ListVoiceConnectorTerminationCredentialsResponseTypeDef",
+DescribeAppInstanceResponseTypeDef = TypedDict(
+    "DescribeAppInstanceResponseTypeDef",
     {
-        "Usernames": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "AppInstance": AppInstanceTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-PutAppInstanceStreamingConfigurationsResponseTypeDef = TypedDict(
-    "PutAppInstanceStreamingConfigurationsResponseTypeDef",
+ListAppInstanceUsersResponseTypeDef = TypedDict(
+    "ListAppInstanceUsersResponseTypeDef",
     {
-        "AppInstanceStreamingConfigurations": List[AppInstanceStreamingConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "AppInstanceArn": str,
+        "AppInstanceUsers": List[AppInstanceUserSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-RedactChannelMessageResponseTypeDef = TypedDict(
-    "RedactChannelMessageResponseTypeDef",
+DescribeAppInstanceUserResponseTypeDef = TypedDict(
+    "DescribeAppInstanceUserResponseTypeDef",
     {
-        "ChannelArn": str,
-        "MessageId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "AppInstanceUser": AppInstanceUserTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-SearchAvailablePhoneNumbersResponseTypeDef = TypedDict(
-    "SearchAvailablePhoneNumbersResponseTypeDef",
+ArtifactsConfigurationTypeDef = TypedDict(
+    "ArtifactsConfigurationTypeDef",
     {
-        "E164PhoneNumbers": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Audio": AudioArtifactsConfigurationTypeDef,
+        "Video": VideoArtifactsConfigurationTypeDef,
+        "Content": ContentArtifactsConfigurationTypeDef,
     },
 )
 
-SendChannelMessageResponseTypeDef = TypedDict(
-    "SendChannelMessageResponseTypeDef",
+AssociatePhoneNumbersWithVoiceConnectorGroupResponseTypeDef = TypedDict(
+    "AssociatePhoneNumbersWithVoiceConnectorGroupResponseTypeDef",
     {
-        "ChannelArn": str,
-        "MessageId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "PhoneNumberErrors": List[PhoneNumberErrorTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateAppInstanceResponseTypeDef = TypedDict(
-    "UpdateAppInstanceResponseTypeDef",
+AssociatePhoneNumbersWithVoiceConnectorResponseTypeDef = TypedDict(
+    "AssociatePhoneNumbersWithVoiceConnectorResponseTypeDef",
     {
-        "AppInstanceArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "PhoneNumberErrors": List[PhoneNumberErrorTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateAppInstanceUserResponseTypeDef = TypedDict(
-    "UpdateAppInstanceUserResponseTypeDef",
+BatchDeletePhoneNumberResponseTypeDef = TypedDict(
+    "BatchDeletePhoneNumberResponseTypeDef",
     {
-        "AppInstanceUserArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "PhoneNumberErrors": List[PhoneNumberErrorTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateChannelMessageResponseTypeDef = TypedDict(
-    "UpdateChannelMessageResponseTypeDef",
+BatchUpdatePhoneNumberResponseTypeDef = TypedDict(
+    "BatchUpdatePhoneNumberResponseTypeDef",
     {
-        "ChannelArn": str,
-        "MessageId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "PhoneNumberErrors": List[PhoneNumberErrorTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateChannelReadMarkerResponseTypeDef = TypedDict(
-    "UpdateChannelReadMarkerResponseTypeDef",
+DisassociatePhoneNumbersFromVoiceConnectorGroupResponseTypeDef = TypedDict(
+    "DisassociatePhoneNumbersFromVoiceConnectorGroupResponseTypeDef",
     {
-        "ChannelArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "PhoneNumberErrors": List[PhoneNumberErrorTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateChannelResponseTypeDef = TypedDict(
-    "UpdateChannelResponseTypeDef",
+DisassociatePhoneNumbersFromVoiceConnectorResponseTypeDef = TypedDict(
+    "DisassociatePhoneNumbersFromVoiceConnectorResponseTypeDef",
     {
-        "ChannelArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "PhoneNumberErrors": List[PhoneNumberErrorTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateAttendeeResponseTypeDef = TypedDict(
     "CreateAttendeeResponseTypeDef",
     {
         "Attendee": AttendeeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAttendeeResponseTypeDef = TypedDict(
     "GetAttendeeResponseTypeDef",
     {
         "Attendee": AttendeeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAttendeesResponseTypeDef = TypedDict(
     "ListAttendeesResponseTypeDef",
     {
         "Attendees": List[AttendeeTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchCreateAttendeeResponseTypeDef = TypedDict(
     "BatchCreateAttendeeResponseTypeDef",
     {
         "Attendees": List[AttendeeTypeDef],
         "Errors": List[CreateAttendeeErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchCreateRoomMembershipRequestRequestTypeDef = TypedDict(
     "BatchCreateRoomMembershipRequestRequestTypeDef",
     {
         "AccountId": str,
@@ -3830,98 +3857,98 @@
     },
 )
 
 BatchCreateRoomMembershipResponseTypeDef = TypedDict(
     "BatchCreateRoomMembershipResponseTypeDef",
     {
         "Errors": List[MemberErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchSuspendUserResponseTypeDef = TypedDict(
     "BatchSuspendUserResponseTypeDef",
     {
         "UserErrors": List[UserErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchUnsuspendUserResponseTypeDef = TypedDict(
     "BatchUnsuspendUserResponseTypeDef",
     {
         "UserErrors": List[UserErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchUpdateUserResponseTypeDef = TypedDict(
     "BatchUpdateUserResponseTypeDef",
     {
         "UserErrors": List[UserErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchUpdatePhoneNumberRequestRequestTypeDef = TypedDict(
     "BatchUpdatePhoneNumberRequestRequestTypeDef",
     {
         "UpdatePhoneNumberRequestItems": Sequence[UpdatePhoneNumberRequestItemTypeDef],
     },
 )
 
 CreateBotResponseTypeDef = TypedDict(
     "CreateBotResponseTypeDef",
     {
         "Bot": BotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetBotResponseTypeDef = TypedDict(
     "GetBotResponseTypeDef",
     {
         "Bot": BotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListBotsResponseTypeDef = TypedDict(
     "ListBotsResponseTypeDef",
     {
         "Bots": List[BotTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RegenerateSecurityTokenResponseTypeDef = TypedDict(
     "RegenerateSecurityTokenResponseTypeDef",
     {
         "Bot": BotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateBotResponseTypeDef = TypedDict(
     "UpdateBotResponseTypeDef",
     {
         "Bot": BotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ValidateE911AddressResponseTypeDef = TypedDict(
     "ValidateE911AddressResponseTypeDef",
     {
         "ValidationResult": int,
         "AddressExternalId": str,
         "Address": AddressTypeDef,
         "CandidateAddressList": List[CandidateAddressTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ChannelMembershipForAppInstanceUserSummaryTypeDef = TypedDict(
     "ChannelMembershipForAppInstanceUserSummaryTypeDef",
     {
         "ChannelSummary": ChannelSummaryTypeDef,
@@ -3939,15 +3966,15 @@
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
 
 _RequiredCreateAppInstanceRequestRequestTypeDef = TypedDict(
     "_RequiredCreateAppInstanceRequestRequestTypeDef",
     {
         "Name": str,
@@ -4066,31 +4093,31 @@
     pass
 
 
 ListAttendeeTagsResponseTypeDef = TypedDict(
     "ListAttendeeTagsResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMeetingTagsResponseTypeDef = TypedDict(
     "ListMeetingTagsResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagAttendeeRequestRequestTypeDef = TypedDict(
     "TagAttendeeRequestRequestTypeDef",
     {
         "MeetingId": str,
@@ -4168,56 +4195,56 @@
     pass
 
 
 CreateRoomResponseTypeDef = TypedDict(
     "CreateRoomResponseTypeDef",
     {
         "Room": RoomTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRoomResponseTypeDef = TypedDict(
     "GetRoomResponseTypeDef",
     {
         "Room": RoomTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRoomsResponseTypeDef = TypedDict(
     "ListRoomsResponseTypeDef",
     {
         "Rooms": List[RoomTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateRoomResponseTypeDef = TypedDict(
     "UpdateRoomResponseTypeDef",
     {
         "Room": RoomTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateSipMediaApplicationCallResponseTypeDef = TypedDict(
     "CreateSipMediaApplicationCallResponseTypeDef",
     {
         "SipMediaApplicationCall": SipMediaApplicationCallTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateSipMediaApplicationCallResponseTypeDef = TypedDict(
     "UpdateSipMediaApplicationCallResponseTypeDef",
     {
         "SipMediaApplicationCall": SipMediaApplicationCallTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateSipMediaApplicationRequestRequestTypeDef = TypedDict(
     "CreateSipMediaApplicationRequestRequestTypeDef",
     {
         "AwsRegion": str,
@@ -4368,40 +4395,40 @@
     total=False,
 )
 
 CreateVoiceConnectorResponseTypeDef = TypedDict(
     "CreateVoiceConnectorResponseTypeDef",
     {
         "VoiceConnector": VoiceConnectorTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetVoiceConnectorResponseTypeDef = TypedDict(
     "GetVoiceConnectorResponseTypeDef",
     {
         "VoiceConnector": VoiceConnectorTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVoiceConnectorsResponseTypeDef = TypedDict(
     "ListVoiceConnectorsResponseTypeDef",
     {
         "VoiceConnectors": List[VoiceConnectorTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateVoiceConnectorResponseTypeDef = TypedDict(
     "UpdateVoiceConnectorResponseTypeDef",
     {
         "VoiceConnector": VoiceConnectorTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutVoiceConnectorTerminationCredentialsRequestRequestTypeDef = TypedDict(
     "_RequiredPutVoiceConnectorTerminationCredentialsRequestRequestTypeDef",
     {
         "VoiceConnectorId": str,
@@ -4440,32 +4467,32 @@
     total=False,
 )
 
 GetEventsConfigurationResponseTypeDef = TypedDict(
     "GetEventsConfigurationResponseTypeDef",
     {
         "EventsConfiguration": EventsConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutEventsConfigurationResponseTypeDef = TypedDict(
     "PutEventsConfigurationResponseTypeDef",
     {
         "EventsConfiguration": EventsConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetGlobalSettingsResponseTypeDef = TypedDict(
     "GetGlobalSettingsResponseTypeDef",
     {
         "BusinessCalling": BusinessCallingSettingsTypeDef,
         "VoiceConnector": VoiceConnectorSettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateGlobalSettingsRequestRequestTypeDef = TypedDict(
     "UpdateGlobalSettingsRequestRequestTypeDef",
     {
         "BusinessCalling": BusinessCallingSettingsTypeDef,
@@ -4474,23 +4501,23 @@
     total=False,
 )
 
 GetMessagingSessionEndpointResponseTypeDef = TypedDict(
     "GetMessagingSessionEndpointResponseTypeDef",
     {
         "Endpoint": MessagingSessionEndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSipMediaApplicationLoggingConfigurationResponseTypeDef = TypedDict(
     "GetSipMediaApplicationLoggingConfigurationResponseTypeDef",
     {
         "SipMediaApplicationLoggingConfiguration": SipMediaApplicationLoggingConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutSipMediaApplicationLoggingConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredPutSipMediaApplicationLoggingConfigurationRequestRequestTypeDef",
     {
         "SipMediaApplicationId": str,
@@ -4512,23 +4539,23 @@
     pass
 
 
 PutSipMediaApplicationLoggingConfigurationResponseTypeDef = TypedDict(
     "PutSipMediaApplicationLoggingConfigurationResponseTypeDef",
     {
         "SipMediaApplicationLoggingConfiguration": SipMediaApplicationLoggingConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetVoiceConnectorLoggingConfigurationResponseTypeDef = TypedDict(
     "GetVoiceConnectorLoggingConfigurationResponseTypeDef",
     {
         "LoggingConfiguration": LoggingConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutVoiceConnectorLoggingConfigurationRequestRequestTypeDef = TypedDict(
     "PutVoiceConnectorLoggingConfigurationRequestRequestTypeDef",
     {
         "VoiceConnectorId": str,
@@ -4536,47 +4563,47 @@
     },
 )
 
 PutVoiceConnectorLoggingConfigurationResponseTypeDef = TypedDict(
     "PutVoiceConnectorLoggingConfigurationResponseTypeDef",
     {
         "LoggingConfiguration": LoggingConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetVoiceConnectorProxyResponseTypeDef = TypedDict(
     "GetVoiceConnectorProxyResponseTypeDef",
     {
         "Proxy": ProxyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutVoiceConnectorProxyResponseTypeDef = TypedDict(
     "PutVoiceConnectorProxyResponseTypeDef",
     {
         "Proxy": ProxyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetVoiceConnectorTerminationHealthResponseTypeDef = TypedDict(
     "GetVoiceConnectorTerminationHealthResponseTypeDef",
     {
         "TerminationHealth": TerminationHealthTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetVoiceConnectorTerminationResponseTypeDef = TypedDict(
     "GetVoiceConnectorTerminationResponseTypeDef",
     {
         "Termination": TerminationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutVoiceConnectorTerminationRequestRequestTypeDef = TypedDict(
     "PutVoiceConnectorTerminationRequestRequestTypeDef",
     {
         "VoiceConnectorId": str,
@@ -4584,65 +4611,31 @@
     },
 )
 
 PutVoiceConnectorTerminationResponseTypeDef = TypedDict(
     "PutVoiceConnectorTerminationResponseTypeDef",
     {
         "Termination": TerminationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InviteUsersResponseTypeDef = TypedDict(
     "InviteUsersResponseTypeDef",
     {
         "Invites": List[InviteTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAccountsRequestListAccountsPaginateTypeDef = TypedDict(
-    "ListAccountsRequestListAccountsPaginateTypeDef",
-    {
-        "Name": str,
-        "UserEmail": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListUsersRequestListUsersPaginateTypeDef = TypedDict(
-    "_RequiredListUsersRequestListUsersPaginateTypeDef",
-    {
-        "AccountId": str,
-    },
-)
-_OptionalListUsersRequestListUsersPaginateTypeDef = TypedDict(
-    "_OptionalListUsersRequestListUsersPaginateTypeDef",
-    {
-        "UserEmail": str,
-        "UserType": UserTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-
-class ListUsersRequestListUsersPaginateTypeDef(
-    _RequiredListUsersRequestListUsersPaginateTypeDef,
-    _OptionalListUsersRequestListUsersPaginateTypeDef,
-):
-    pass
-
-
 ListSupportedPhoneNumberCountriesResponseTypeDef = TypedDict(
     "ListSupportedPhoneNumberCountriesResponseTypeDef",
     {
         "PhoneNumberCountries": List[PhoneNumberCountryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 MeetingTypeDef = TypedDict(
     "MeetingTypeDef",
     {
         "MeetingId": str,
@@ -4773,40 +4766,40 @@
     },
 )
 
 CreateAccountResponseTypeDef = TypedDict(
     "CreateAccountResponseTypeDef",
     {
         "Account": AccountTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAccountResponseTypeDef = TypedDict(
     "GetAccountResponseTypeDef",
     {
         "Account": AccountTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAccountsResponseTypeDef = TypedDict(
     "ListAccountsResponseTypeDef",
     {
         "Accounts": List[AccountTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAccountResponseTypeDef = TypedDict(
     "UpdateAccountResponseTypeDef",
     {
         "Account": AccountTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchUpdateUserRequestRequestTypeDef = TypedDict(
     "BatchUpdateUserRequestRequestTypeDef",
     {
         "AccountId": str,
@@ -4814,164 +4807,164 @@
     },
 )
 
 CreateUserResponseTypeDef = TypedDict(
     "CreateUserResponseTypeDef",
     {
         "User": UserTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetUserResponseTypeDef = TypedDict(
     "GetUserResponseTypeDef",
     {
         "User": UserTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListUsersResponseTypeDef = TypedDict(
     "ListUsersResponseTypeDef",
     {
         "Users": List[UserTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResetPersonalPINResponseTypeDef = TypedDict(
     "ResetPersonalPINResponseTypeDef",
     {
         "User": UserTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateUserResponseTypeDef = TypedDict(
     "UpdateUserResponseTypeDef",
     {
         "User": UserTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAppInstanceAdminsResponseTypeDef = TypedDict(
     "ListAppInstanceAdminsResponseTypeDef",
     {
         "AppInstanceArn": str,
         "AppInstanceAdmins": List[AppInstanceAdminSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAppInstanceAdminResponseTypeDef = TypedDict(
     "DescribeAppInstanceAdminResponseTypeDef",
     {
         "AppInstanceAdmin": AppInstanceAdminTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
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
 
 ListChannelMessagesResponseTypeDef = TypedDict(
     "ListChannelMessagesResponseTypeDef",
     {
         "ChannelArn": str,
         "NextToken": str,
         "ChannelMessages": List[ChannelMessageSummaryTypeDef],
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
 
 DescribeChannelResponseTypeDef = TypedDict(
     "DescribeChannelResponseTypeDef",
     {
         "Channel": ChannelTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAppInstanceRetentionSettingsResponseTypeDef = TypedDict(
     "GetAppInstanceRetentionSettingsResponseTypeDef",
     {
         "AppInstanceRetentionSettings": AppInstanceRetentionSettingsTypeDef,
         "InitiateDeletionTimestamp": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutAppInstanceRetentionSettingsRequestRequestTypeDef = TypedDict(
     "PutAppInstanceRetentionSettingsRequestRequestTypeDef",
     {
         "AppInstanceArn": str,
@@ -4980,49 +4973,49 @@
 )
 
 PutAppInstanceRetentionSettingsResponseTypeDef = TypedDict(
     "PutAppInstanceRetentionSettingsResponseTypeDef",
     {
         "AppInstanceRetentionSettings": AppInstanceRetentionSettingsTypeDef,
         "InitiateDeletionTimestamp": datetime,
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
 
 BatchCreateAttendeeRequestRequestTypeDef = TypedDict(
     "BatchCreateAttendeeRequestRequestTypeDef",
     {
         "MeetingId": str,
@@ -5057,114 +5050,114 @@
     pass
 
 
 CreateSipMediaApplicationResponseTypeDef = TypedDict(
     "CreateSipMediaApplicationResponseTypeDef",
     {
         "SipMediaApplication": SipMediaApplicationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSipMediaApplicationResponseTypeDef = TypedDict(
     "GetSipMediaApplicationResponseTypeDef",
     {
         "SipMediaApplication": SipMediaApplicationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSipMediaApplicationsResponseTypeDef = TypedDict(
     "ListSipMediaApplicationsResponseTypeDef",
     {
         "SipMediaApplications": List[SipMediaApplicationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateSipMediaApplicationResponseTypeDef = TypedDict(
     "UpdateSipMediaApplicationResponseTypeDef",
     {
         "SipMediaApplication": SipMediaApplicationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateSipRuleResponseTypeDef = TypedDict(
     "CreateSipRuleResponseTypeDef",
     {
         "SipRule": SipRuleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSipRuleResponseTypeDef = TypedDict(
     "GetSipRuleResponseTypeDef",
     {
         "SipRule": SipRuleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSipRulesResponseTypeDef = TypedDict(
     "ListSipRulesResponseTypeDef",
     {
         "SipRules": List[SipRuleTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateSipRuleResponseTypeDef = TypedDict(
     "UpdateSipRuleResponseTypeDef",
     {
         "SipRule": SipRuleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateVoiceConnectorGroupResponseTypeDef = TypedDict(
     "CreateVoiceConnectorGroupResponseTypeDef",
     {
         "VoiceConnectorGroup": VoiceConnectorGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetVoiceConnectorGroupResponseTypeDef = TypedDict(
     "GetVoiceConnectorGroupResponseTypeDef",
     {
         "VoiceConnectorGroup": VoiceConnectorGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVoiceConnectorGroupsResponseTypeDef = TypedDict(
     "ListVoiceConnectorGroupsResponseTypeDef",
     {
         "VoiceConnectorGroups": List[VoiceConnectorGroupTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateVoiceConnectorGroupResponseTypeDef = TypedDict(
     "UpdateVoiceConnectorGroupResponseTypeDef",
     {
         "VoiceConnectorGroup": VoiceConnectorGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetVoiceConnectorEmergencyCallingConfigurationResponseTypeDef = TypedDict(
     "GetVoiceConnectorEmergencyCallingConfigurationResponseTypeDef",
     {
         "EmergencyCallingConfiguration": EmergencyCallingConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutVoiceConnectorEmergencyCallingConfigurationRequestRequestTypeDef = TypedDict(
     "PutVoiceConnectorEmergencyCallingConfigurationRequestRequestTypeDef",
     {
         "VoiceConnectorId": str,
@@ -5172,15 +5165,15 @@
     },
 )
 
 PutVoiceConnectorEmergencyCallingConfigurationResponseTypeDef = TypedDict(
     "PutVoiceConnectorEmergencyCallingConfigurationResponseTypeDef",
     {
         "EmergencyCallingConfiguration": EmergencyCallingConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartMeetingTranscriptionRequestRequestTypeDef = TypedDict(
     "StartMeetingTranscriptionRequestRequestTypeDef",
     {
         "MeetingId": str,
@@ -5188,100 +5181,100 @@
     },
 )
 
 CreateMeetingResponseTypeDef = TypedDict(
     "CreateMeetingResponseTypeDef",
     {
         "Meeting": MeetingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateMeetingWithAttendeesResponseTypeDef = TypedDict(
     "CreateMeetingWithAttendeesResponseTypeDef",
     {
         "Meeting": MeetingTypeDef,
         "Attendees": List[AttendeeTypeDef],
         "Errors": List[CreateAttendeeErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMeetingResponseTypeDef = TypedDict(
     "GetMeetingResponseTypeDef",
     {
         "Meeting": MeetingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMeetingsResponseTypeDef = TypedDict(
     "ListMeetingsResponseTypeDef",
     {
         "Meetings": List[MeetingTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateRoomMembershipResponseTypeDef = TypedDict(
     "CreateRoomMembershipResponseTypeDef",
     {
         "RoomMembership": RoomMembershipTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRoomMembershipsResponseTypeDef = TypedDict(
     "ListRoomMembershipsResponseTypeDef",
     {
         "RoomMemberships": List[RoomMembershipTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateRoomMembershipResponseTypeDef = TypedDict(
     "UpdateRoomMembershipResponseTypeDef",
     {
         "RoomMembership": RoomMembershipTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreatePhoneNumberOrderResponseTypeDef = TypedDict(
     "CreatePhoneNumberOrderResponseTypeDef",
     {
         "PhoneNumberOrder": PhoneNumberOrderTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetPhoneNumberOrderResponseTypeDef = TypedDict(
     "GetPhoneNumberOrderResponseTypeDef",
     {
         "PhoneNumberOrder": PhoneNumberOrderTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPhoneNumberOrdersResponseTypeDef = TypedDict(
     "ListPhoneNumberOrdersResponseTypeDef",
     {
         "PhoneNumberOrders": List[PhoneNumberOrderTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetVoiceConnectorOriginationResponseTypeDef = TypedDict(
     "GetVoiceConnectorOriginationResponseTypeDef",
     {
         "Origination": OriginationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutVoiceConnectorOriginationRequestRequestTypeDef = TypedDict(
     "PutVoiceConnectorOriginationRequestRequestTypeDef",
     {
         "VoiceConnectorId": str,
@@ -5289,90 +5282,90 @@
     },
 )
 
 PutVoiceConnectorOriginationResponseTypeDef = TypedDict(
     "PutVoiceConnectorOriginationResponseTypeDef",
     {
         "Origination": OriginationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateProxySessionResponseTypeDef = TypedDict(
     "CreateProxySessionResponseTypeDef",
     {
         "ProxySession": ProxySessionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetProxySessionResponseTypeDef = TypedDict(
     "GetProxySessionResponseTypeDef",
     {
         "ProxySession": ProxySessionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProxySessionsResponseTypeDef = TypedDict(
     "ListProxySessionsResponseTypeDef",
     {
         "ProxySessions": List[ProxySessionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateProxySessionResponseTypeDef = TypedDict(
     "UpdateProxySessionResponseTypeDef",
     {
         "ProxySession": ProxySessionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetPhoneNumberResponseTypeDef = TypedDict(
     "GetPhoneNumberResponseTypeDef",
     {
         "PhoneNumber": PhoneNumberTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPhoneNumbersResponseTypeDef = TypedDict(
     "ListPhoneNumbersResponseTypeDef",
     {
         "PhoneNumbers": List[PhoneNumberTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RestorePhoneNumberResponseTypeDef = TypedDict(
     "RestorePhoneNumberResponseTypeDef",
     {
         "PhoneNumber": PhoneNumberTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdatePhoneNumberResponseTypeDef = TypedDict(
     "UpdatePhoneNumberResponseTypeDef",
     {
         "PhoneNumber": PhoneNumberTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRetentionSettingsResponseTypeDef = TypedDict(
     "GetRetentionSettingsResponseTypeDef",
     {
         "RetentionSettings": RetentionSettingsTypeDef,
         "InitiateDeletionTimestamp": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutRetentionSettingsRequestRequestTypeDef = TypedDict(
     "PutRetentionSettingsRequestRequestTypeDef",
     {
         "AccountId": str,
@@ -5381,15 +5374,15 @@
 )
 
 PutRetentionSettingsResponseTypeDef = TypedDict(
     "PutRetentionSettingsResponseTypeDef",
     {
         "RetentionSettings": RetentionSettingsTypeDef,
         "InitiateDeletionTimestamp": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ChimeSdkMeetingConfigurationTypeDef = TypedDict(
     "ChimeSdkMeetingConfigurationTypeDef",
     {
         "SourceConfiguration": SourceConfigurationTypeDef,
@@ -5398,15 +5391,15 @@
     total=False,
 )
 
 GetVoiceConnectorStreamingConfigurationResponseTypeDef = TypedDict(
     "GetVoiceConnectorStreamingConfigurationResponseTypeDef",
     {
         "StreamingConfiguration": StreamingConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutVoiceConnectorStreamingConfigurationRequestRequestTypeDef = TypedDict(
     "PutVoiceConnectorStreamingConfigurationRequestRequestTypeDef",
     {
         "VoiceConnectorId": str,
@@ -5414,23 +5407,23 @@
     },
 )
 
 PutVoiceConnectorStreamingConfigurationResponseTypeDef = TypedDict(
     "PutVoiceConnectorStreamingConfigurationResponseTypeDef",
     {
         "StreamingConfiguration": StreamingConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetUserSettingsResponseTypeDef = TypedDict(
     "GetUserSettingsResponseTypeDef",
     {
         "UserSettings": UserSettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateUserSettingsRequestRequestTypeDef = TypedDict(
     "UpdateUserSettingsRequestRequestTypeDef",
     {
         "AccountId": str,
@@ -5481,27 +5474,27 @@
     total=False,
 )
 
 CreateMediaCapturePipelineResponseTypeDef = TypedDict(
     "CreateMediaCapturePipelineResponseTypeDef",
     {
         "MediaCapturePipeline": MediaCapturePipelineTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMediaCapturePipelineResponseTypeDef = TypedDict(
     "GetMediaCapturePipelineResponseTypeDef",
     {
         "MediaCapturePipeline": MediaCapturePipelineTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMediaCapturePipelinesResponseTypeDef = TypedDict(
     "ListMediaCapturePipelinesResponseTypeDef",
     {
         "MediaCapturePipelines": List[MediaCapturePipelineTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-chime-2.5.0.post1/types_aiobotocore_chime/type_defs.pyi` & `types-aiobotocore-chime-2.5.1/types_aiobotocore_chime/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -84,15 +84,14 @@
     "AppInstanceUserTypeDef",
     "AudioArtifactsConfigurationTypeDef",
     "ContentArtifactsConfigurationTypeDef",
     "VideoArtifactsConfigurationTypeDef",
     "AssociatePhoneNumberWithUserRequestRequestTypeDef",
     "AssociatePhoneNumbersWithVoiceConnectorGroupRequestRequestTypeDef",
     "PhoneNumberErrorTypeDef",
-    "ResponseMetadataTypeDef",
     "AssociatePhoneNumbersWithVoiceConnectorRequestRequestTypeDef",
     "AttendeeTypeDef",
     "CreateAttendeeErrorTypeDef",
     "BatchCreateChannelMembershipErrorTypeDef",
     "BatchCreateChannelMembershipRequestRequestTypeDef",
     "MembershipItemTypeDef",
     "MemberErrorTypeDef",
@@ -105,19 +104,23 @@
     "BusinessCallingSettingsTypeDef",
     "CandidateAddressTypeDef",
     "ChannelSummaryTypeDef",
     "ConversationRetentionSettingsTypeDef",
     "CreateAccountRequestRequestTypeDef",
     "CreateAppInstanceAdminRequestRequestTypeDef",
     "TagTypeDef",
+    "CreateAppInstanceResponseTypeDef",
+    "CreateAppInstanceUserResponseTypeDef",
     "CreateBotRequestRequestTypeDef",
     "CreateChannelBanRequestRequestTypeDef",
     "CreateChannelMembershipRequestRequestTypeDef",
     "CreateChannelModeratorRequestRequestTypeDef",
+    "CreateChannelResponseTypeDef",
     "CreateMeetingDialOutRequestRequestTypeDef",
+    "CreateMeetingDialOutResponseTypeDef",
     "MeetingNotificationConfigurationTypeDef",
     "CreatePhoneNumberOrderRequestRequestTypeDef",
     "GeoMatchParamsTypeDef",
     "CreateRoomMembershipRequestRequestTypeDef",
     "CreateRoomRequestRequestTypeDef",
     "RoomTypeDef",
     "CreateSipMediaApplicationCallRequestRequestTypeDef",
@@ -167,14 +170,15 @@
     "DescribeChannelModeratedByAppInstanceUserRequestRequestTypeDef",
     "DescribeChannelModeratorRequestRequestTypeDef",
     "DescribeChannelRequestRequestTypeDef",
     "DisassociatePhoneNumberFromUserRequestRequestTypeDef",
     "DisassociatePhoneNumbersFromVoiceConnectorGroupRequestRequestTypeDef",
     "DisassociatePhoneNumbersFromVoiceConnectorRequestRequestTypeDef",
     "DisassociateSigninDelegateGroupsFromAccountRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EngineTranscribeMedicalSettingsTypeDef",
     "EngineTranscribeSettingsTypeDef",
     "EventsConfigurationTypeDef",
     "GetAccountRequestRequestTypeDef",
     "GetAccountSettingsRequestRequestTypeDef",
     "GetAppInstanceRetentionSettingsRequestRequestTypeDef",
     "GetAppInstanceStreamingConfigurationsRequestRequestTypeDef",
@@ -184,14 +188,15 @@
     "GetEventsConfigurationRequestRequestTypeDef",
     "VoiceConnectorSettingsTypeDef",
     "GetMediaCapturePipelineRequestRequestTypeDef",
     "GetMeetingRequestRequestTypeDef",
     "MessagingSessionEndpointTypeDef",
     "GetPhoneNumberOrderRequestRequestTypeDef",
     "GetPhoneNumberRequestRequestTypeDef",
+    "GetPhoneNumberSettingsResponseTypeDef",
     "GetProxySessionRequestRequestTypeDef",
     "GetRetentionSettingsRequestRequestTypeDef",
     "GetRoomRequestRequestTypeDef",
     "GetSipMediaApplicationLoggingConfigurationRequestRequestTypeDef",
     "SipMediaApplicationLoggingConfigurationTypeDef",
     "GetSipMediaApplicationRequestRequestTypeDef",
     "GetSipRuleRequestRequestTypeDef",
@@ -208,15 +213,15 @@
     "GetVoiceConnectorStreamingConfigurationRequestRequestTypeDef",
     "GetVoiceConnectorTerminationHealthRequestRequestTypeDef",
     "TerminationHealthTypeDef",
     "GetVoiceConnectorTerminationRequestRequestTypeDef",
     "TerminationTypeDef",
     "InviteTypeDef",
     "InviteUsersRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListAccountsRequestListAccountsPaginateTypeDef",
     "ListAccountsRequestRequestTypeDef",
     "ListAppInstanceAdminsRequestRequestTypeDef",
     "ListAppInstanceUsersRequestRequestTypeDef",
     "ListAppInstancesRequestRequestTypeDef",
     "ListAttendeeTagsRequestRequestTypeDef",
     "ListAttendeesRequestRequestTypeDef",
     "ListBotsRequestRequestTypeDef",
@@ -236,59 +241,72 @@
     "ListRoomMembershipsRequestRequestTypeDef",
     "ListRoomsRequestRequestTypeDef",
     "ListSipMediaApplicationsRequestRequestTypeDef",
     "ListSipRulesRequestRequestTypeDef",
     "ListSupportedPhoneNumberCountriesRequestRequestTypeDef",
     "PhoneNumberCountryTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListUsersRequestListUsersPaginateTypeDef",
     "ListUsersRequestRequestTypeDef",
     "ListVoiceConnectorGroupsRequestRequestTypeDef",
     "ListVoiceConnectorTerminationCredentialsRequestRequestTypeDef",
+    "ListVoiceConnectorTerminationCredentialsResponseTypeDef",
     "ListVoiceConnectorsRequestRequestTypeDef",
     "LogoutUserRequestRequestTypeDef",
     "MediaPlacementTypeDef",
     "MemberTypeDef",
     "OrderedPhoneNumberTypeDef",
     "OriginationRouteTypeDef",
+    "PaginatorConfigTypeDef",
     "ParticipantTypeDef",
     "PhoneNumberAssociationTypeDef",
     "PhoneNumberCapabilitiesTypeDef",
     "PutEventsConfigurationRequestRequestTypeDef",
     "PutVoiceConnectorProxyRequestRequestTypeDef",
     "RedactChannelMessageRequestRequestTypeDef",
+    "RedactChannelMessageResponseTypeDef",
     "RedactConversationMessageRequestRequestTypeDef",
     "RedactRoomMessageRequestRequestTypeDef",
     "RegenerateSecurityTokenRequestRequestTypeDef",
     "ResetPersonalPINRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "RestorePhoneNumberRequestRequestTypeDef",
     "RoomRetentionSettingsTypeDef",
     "SearchAvailablePhoneNumbersRequestRequestTypeDef",
+    "SearchAvailablePhoneNumbersResponseTypeDef",
     "SelectedVideoStreamsTypeDef",
     "SendChannelMessageRequestRequestTypeDef",
+    "SendChannelMessageResponseTypeDef",
     "StopMeetingTranscriptionRequestRequestTypeDef",
     "StreamingNotificationTargetTypeDef",
     "TelephonySettingsTypeDef",
     "UntagAttendeeRequestRequestTypeDef",
     "UntagMeetingRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateAccountRequestRequestTypeDef",
     "UpdateAppInstanceRequestRequestTypeDef",
+    "UpdateAppInstanceResponseTypeDef",
     "UpdateAppInstanceUserRequestRequestTypeDef",
+    "UpdateAppInstanceUserResponseTypeDef",
     "UpdateBotRequestRequestTypeDef",
     "UpdateChannelMessageRequestRequestTypeDef",
+    "UpdateChannelMessageResponseTypeDef",
     "UpdateChannelReadMarkerRequestRequestTypeDef",
+    "UpdateChannelReadMarkerResponseTypeDef",
     "UpdateChannelRequestRequestTypeDef",
+    "UpdateChannelResponseTypeDef",
     "UpdatePhoneNumberRequestRequestTypeDef",
     "UpdatePhoneNumberSettingsRequestRequestTypeDef",
     "UpdateProxySessionRequestRequestTypeDef",
     "UpdateRoomMembershipRequestRequestTypeDef",
     "UpdateRoomRequestRequestTypeDef",
     "UpdateSipMediaApplicationCallRequestRequestTypeDef",
     "UpdateVoiceConnectorRequestRequestTypeDef",
     "ValidateE911AddressRequestRequestTypeDef",
+    "GetAccountSettingsResponseTypeDef",
     "UpdateAccountSettingsRequestRequestTypeDef",
     "AccountTypeDef",
     "AssociateSigninDelegateGroupsWithAccountRequestRequestTypeDef",
     "UpdateUserRequestItemTypeDef",
     "UpdateUserRequestRequestTypeDef",
     "UserTypeDef",
     "AppInstanceAdminSummaryTypeDef",
@@ -299,49 +317,33 @@
     "ChannelMembershipSummaryTypeDef",
     "ChannelMembershipTypeDef",
     "ChannelMessageSummaryTypeDef",
     "ChannelMessageTypeDef",
     "ChannelModeratorSummaryTypeDef",
     "ChannelModeratorTypeDef",
     "ChannelTypeDef",
+    "CreateAppInstanceAdminResponseTypeDef",
+    "CreateChannelBanResponseTypeDef",
+    "CreateChannelMembershipResponseTypeDef",
+    "CreateChannelModeratorResponseTypeDef",
     "AppInstanceRetentionSettingsTypeDef",
+    "GetAppInstanceStreamingConfigurationsResponseTypeDef",
     "PutAppInstanceStreamingConfigurationsRequestRequestTypeDef",
+    "PutAppInstanceStreamingConfigurationsResponseTypeDef",
+    "ListAppInstancesResponseTypeDef",
+    "DescribeAppInstanceResponseTypeDef",
+    "ListAppInstanceUsersResponseTypeDef",
+    "DescribeAppInstanceUserResponseTypeDef",
     "ArtifactsConfigurationTypeDef",
     "AssociatePhoneNumbersWithVoiceConnectorGroupResponseTypeDef",
     "AssociatePhoneNumbersWithVoiceConnectorResponseTypeDef",
     "BatchDeletePhoneNumberResponseTypeDef",
     "BatchUpdatePhoneNumberResponseTypeDef",
-    "CreateAppInstanceAdminResponseTypeDef",
-    "CreateAppInstanceResponseTypeDef",
-    "CreateAppInstanceUserResponseTypeDef",
-    "CreateChannelBanResponseTypeDef",
-    "CreateChannelMembershipResponseTypeDef",
-    "CreateChannelModeratorResponseTypeDef",
-    "CreateChannelResponseTypeDef",
-    "CreateMeetingDialOutResponseTypeDef",
-    "DescribeAppInstanceResponseTypeDef",
-    "DescribeAppInstanceUserResponseTypeDef",
     "DisassociatePhoneNumbersFromVoiceConnectorGroupResponseTypeDef",
     "DisassociatePhoneNumbersFromVoiceConnectorResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetAccountSettingsResponseTypeDef",
-    "GetAppInstanceStreamingConfigurationsResponseTypeDef",
-    "GetPhoneNumberSettingsResponseTypeDef",
-    "ListAppInstanceUsersResponseTypeDef",
-    "ListAppInstancesResponseTypeDef",
-    "ListVoiceConnectorTerminationCredentialsResponseTypeDef",
-    "PutAppInstanceStreamingConfigurationsResponseTypeDef",
-    "RedactChannelMessageResponseTypeDef",
-    "SearchAvailablePhoneNumbersResponseTypeDef",
-    "SendChannelMessageResponseTypeDef",
-    "UpdateAppInstanceResponseTypeDef",
-    "UpdateAppInstanceUserResponseTypeDef",
-    "UpdateChannelMessageResponseTypeDef",
-    "UpdateChannelReadMarkerResponseTypeDef",
-    "UpdateChannelResponseTypeDef",
     "CreateAttendeeResponseTypeDef",
     "GetAttendeeResponseTypeDef",
     "ListAttendeesResponseTypeDef",
     "BatchCreateAttendeeResponseTypeDef",
     "BatchCreateRoomMembershipRequestRequestTypeDef",
     "BatchCreateRoomMembershipResponseTypeDef",
     "BatchSuspendUserResponseTypeDef",
@@ -406,16 +408,14 @@
     "GetVoiceConnectorProxyResponseTypeDef",
     "PutVoiceConnectorProxyResponseTypeDef",
     "GetVoiceConnectorTerminationHealthResponseTypeDef",
     "GetVoiceConnectorTerminationResponseTypeDef",
     "PutVoiceConnectorTerminationRequestRequestTypeDef",
     "PutVoiceConnectorTerminationResponseTypeDef",
     "InviteUsersResponseTypeDef",
-    "ListAccountsRequestListAccountsPaginateTypeDef",
-    "ListUsersRequestListUsersPaginateTypeDef",
     "ListSupportedPhoneNumberCountriesResponseTypeDef",
     "MeetingTypeDef",
     "RoomMembershipTypeDef",
     "PhoneNumberOrderTypeDef",
     "OriginationTypeDef",
     "ProxySessionTypeDef",
     "PhoneNumberTypeDef",
@@ -709,25 +709,14 @@
         "PhoneNumberId": str,
         "ErrorCode": ErrorCodeType,
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
 _RequiredAssociatePhoneNumbersWithVoiceConnectorRequestRequestTypeDef = TypedDict(
     "_RequiredAssociatePhoneNumbersWithVoiceConnectorRequestRequestTypeDef",
     {
         "VoiceConnectorId": str,
         "E164PhoneNumbers": Sequence[str],
     },
 )
@@ -947,14 +936,30 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
 
+CreateAppInstanceResponseTypeDef = TypedDict(
+    "CreateAppInstanceResponseTypeDef",
+    {
+        "AppInstanceArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateAppInstanceUserResponseTypeDef = TypedDict(
+    "CreateAppInstanceUserResponseTypeDef",
+    {
+        "AppInstanceUserArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateBotRequestRequestTypeDef = TypedDict(
     "_RequiredCreateBotRequestRequestTypeDef",
     {
         "AccountId": str,
         "DisplayName": str,
     },
 )
@@ -1030,24 +1035,40 @@
 
 class CreateChannelModeratorRequestRequestTypeDef(
     _RequiredCreateChannelModeratorRequestRequestTypeDef,
     _OptionalCreateChannelModeratorRequestRequestTypeDef,
 ):
     pass
 
+CreateChannelResponseTypeDef = TypedDict(
+    "CreateChannelResponseTypeDef",
+    {
+        "ChannelArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateMeetingDialOutRequestRequestTypeDef = TypedDict(
     "CreateMeetingDialOutRequestRequestTypeDef",
     {
         "MeetingId": str,
         "FromPhoneNumber": str,
         "ToPhoneNumber": str,
         "JoinToken": str,
     },
 )
 
+CreateMeetingDialOutResponseTypeDef = TypedDict(
+    "CreateMeetingDialOutResponseTypeDef",
+    {
+        "TransactionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 MeetingNotificationConfigurationTypeDef = TypedDict(
     "MeetingNotificationConfigurationTypeDef",
     {
         "SnsTopicArn": str,
         "SqsQueueArn": str,
     },
     total=False,
@@ -1712,14 +1733,21 @@
     "DisassociateSigninDelegateGroupsFromAccountRequestRequestTypeDef",
     {
         "AccountId": str,
         "GroupNames": Sequence[str],
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredEngineTranscribeMedicalSettingsTypeDef = TypedDict(
     "_RequiredEngineTranscribeMedicalSettingsTypeDef",
     {
         "LanguageCode": Literal["en-US"],
         "Specialty": TranscribeMedicalSpecialtyType,
         "Type": TranscribeMedicalTypeType,
     },
@@ -1735,42 +1763,37 @@
 )
 
 class EngineTranscribeMedicalSettingsTypeDef(
     _RequiredEngineTranscribeMedicalSettingsTypeDef, _OptionalEngineTranscribeMedicalSettingsTypeDef
 ):
     pass
 
-_RequiredEngineTranscribeSettingsTypeDef = TypedDict(
-    "_RequiredEngineTranscribeSettingsTypeDef",
+EngineTranscribeSettingsTypeDef = TypedDict(
+    "EngineTranscribeSettingsTypeDef",
     {
         "LanguageCode": TranscribeLanguageCodeType,
-    },
-)
-_OptionalEngineTranscribeSettingsTypeDef = TypedDict(
-    "_OptionalEngineTranscribeSettingsTypeDef",
-    {
         "VocabularyFilterMethod": TranscribeVocabularyFilterMethodType,
         "VocabularyFilterName": str,
         "VocabularyName": str,
         "Region": TranscribeRegionType,
         "EnablePartialResultsStabilization": bool,
         "PartialResultsStability": TranscribePartialResultsStabilityType,
         "ContentIdentificationType": Literal["PII"],
         "ContentRedactionType": Literal["PII"],
         "PiiEntityTypes": str,
         "LanguageModelName": str,
+        "IdentifyLanguage": bool,
+        "LanguageOptions": str,
+        "PreferredLanguage": TranscribeLanguageCodeType,
+        "VocabularyNames": str,
+        "VocabularyFilterNames": str,
     },
     total=False,
 )
 
-class EngineTranscribeSettingsTypeDef(
-    _RequiredEngineTranscribeSettingsTypeDef, _OptionalEngineTranscribeSettingsTypeDef
-):
-    pass
-
 EventsConfigurationTypeDef = TypedDict(
     "EventsConfigurationTypeDef",
     {
         "BotId": str,
         "OutboundEventsHTTPSEndpoint": str,
         "LambdaFunctionArn": str,
     },
@@ -1889,14 +1912,23 @@
 GetPhoneNumberRequestRequestTypeDef = TypedDict(
     "GetPhoneNumberRequestRequestTypeDef",
     {
         "PhoneNumberId": str,
     },
 )
 
+GetPhoneNumberSettingsResponseTypeDef = TypedDict(
+    "GetPhoneNumberSettingsResponseTypeDef",
+    {
+        "CallingName": str,
+        "CallingNameUpdatedTimestamp": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetProxySessionRequestRequestTypeDef = TypedDict(
     "GetProxySessionRequestRequestTypeDef",
     {
         "VoiceConnectorId": str,
         "ProxySessionId": str,
     },
 )
@@ -2092,20 +2124,20 @@
 )
 
 class InviteUsersRequestRequestTypeDef(
     _RequiredInviteUsersRequestRequestTypeDef, _OptionalInviteUsersRequestRequestTypeDef
 ):
     pass
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListAccountsRequestListAccountsPaginateTypeDef = TypedDict(
+    "ListAccountsRequestListAccountsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "Name": str,
+        "UserEmail": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListAccountsRequestRequestTypeDef = TypedDict(
     "ListAccountsRequestRequestTypeDef",
     {
@@ -2500,14 +2532,36 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
     },
 )
 
+_RequiredListUsersRequestListUsersPaginateTypeDef = TypedDict(
+    "_RequiredListUsersRequestListUsersPaginateTypeDef",
+    {
+        "AccountId": str,
+    },
+)
+_OptionalListUsersRequestListUsersPaginateTypeDef = TypedDict(
+    "_OptionalListUsersRequestListUsersPaginateTypeDef",
+    {
+        "UserEmail": str,
+        "UserType": UserTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListUsersRequestListUsersPaginateTypeDef(
+    _RequiredListUsersRequestListUsersPaginateTypeDef,
+    _OptionalListUsersRequestListUsersPaginateTypeDef,
+):
+    pass
+
 _RequiredListUsersRequestRequestTypeDef = TypedDict(
     "_RequiredListUsersRequestRequestTypeDef",
     {
         "AccountId": str,
     },
 )
 _OptionalListUsersRequestRequestTypeDef = TypedDict(
@@ -2538,14 +2592,22 @@
 ListVoiceConnectorTerminationCredentialsRequestRequestTypeDef = TypedDict(
     "ListVoiceConnectorTerminationCredentialsRequestRequestTypeDef",
     {
         "VoiceConnectorId": str,
     },
 )
 
+ListVoiceConnectorTerminationCredentialsResponseTypeDef = TypedDict(
+    "ListVoiceConnectorTerminationCredentialsResponseTypeDef",
+    {
+        "Usernames": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListVoiceConnectorsRequestRequestTypeDef = TypedDict(
     "ListVoiceConnectorsRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
@@ -2603,14 +2665,24 @@
         "Protocol": OriginationRouteProtocolType,
         "Priority": int,
         "Weight": int,
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
 ParticipantTypeDef = TypedDict(
     "ParticipantTypeDef",
     {
         "PhoneNumber": str,
         "ProxyPhoneNumber": str,
     },
     total=False,
@@ -2701,14 +2773,23 @@
 
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
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RedactConversationMessageRequestRequestTypeDef = TypedDict(
     "RedactConversationMessageRequestRequestTypeDef",
     {
         "AccountId": str,
         "ConversationId": str,
         "MessageId": str,
     },
@@ -2735,14 +2816,25 @@
     "ResetPersonalPINRequestRequestTypeDef",
     {
         "AccountId": str,
         "UserId": str,
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
 RestorePhoneNumberRequestRequestTypeDef = TypedDict(
     "RestorePhoneNumberRequestRequestTypeDef",
     {
         "PhoneNumberId": str,
     },
 )
 
@@ -2765,14 +2857,23 @@
         "PhoneNumberType": PhoneNumberTypeType,
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+SearchAvailablePhoneNumbersResponseTypeDef = TypedDict(
+    "SearchAvailablePhoneNumbersResponseTypeDef",
+    {
+        "E164PhoneNumbers": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 SelectedVideoStreamsTypeDef = TypedDict(
     "SelectedVideoStreamsTypeDef",
     {
         "AttendeeIds": Sequence[str],
         "ExternalUserIds": Sequence[str],
     },
     total=False,
@@ -2799,14 +2900,23 @@
 
 class SendChannelMessageRequestRequestTypeDef(
     _RequiredSendChannelMessageRequestRequestTypeDef,
     _OptionalSendChannelMessageRequestRequestTypeDef,
 ):
     pass
 
+SendChannelMessageResponseTypeDef = TypedDict(
+    "SendChannelMessageResponseTypeDef",
+    {
+        "ChannelArn": str,
+        "MessageId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopMeetingTranscriptionRequestRequestTypeDef = TypedDict(
     "StopMeetingTranscriptionRequestRequestTypeDef",
     {
         "MeetingId": str,
     },
 )
 
@@ -2887,14 +2997,22 @@
 )
 
 class UpdateAppInstanceRequestRequestTypeDef(
     _RequiredUpdateAppInstanceRequestRequestTypeDef, _OptionalUpdateAppInstanceRequestRequestTypeDef
 ):
     pass
 
+UpdateAppInstanceResponseTypeDef = TypedDict(
+    "UpdateAppInstanceResponseTypeDef",
+    {
+        "AppInstanceArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateAppInstanceUserRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateAppInstanceUserRequestRequestTypeDef",
     {
         "AppInstanceUserArn": str,
         "Name": str,
     },
 )
@@ -2908,14 +3026,22 @@
 
 class UpdateAppInstanceUserRequestRequestTypeDef(
     _RequiredUpdateAppInstanceUserRequestRequestTypeDef,
     _OptionalUpdateAppInstanceUserRequestRequestTypeDef,
 ):
     pass
 
+UpdateAppInstanceUserResponseTypeDef = TypedDict(
+    "UpdateAppInstanceUserResponseTypeDef",
+    {
+        "AppInstanceUserArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateBotRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateBotRequestRequestTypeDef",
     {
         "AccountId": str,
         "BotId": str,
     },
 )
@@ -2951,14 +3077,23 @@
 
 class UpdateChannelMessageRequestRequestTypeDef(
     _RequiredUpdateChannelMessageRequestRequestTypeDef,
     _OptionalUpdateChannelMessageRequestRequestTypeDef,
 ):
     pass
 
+UpdateChannelMessageResponseTypeDef = TypedDict(
+    "UpdateChannelMessageResponseTypeDef",
+    {
+        "ChannelArn": str,
+        "MessageId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateChannelReadMarkerRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateChannelReadMarkerRequestRequestTypeDef",
     {
         "ChannelArn": str,
     },
 )
 _OptionalUpdateChannelReadMarkerRequestRequestTypeDef = TypedDict(
@@ -2971,14 +3106,22 @@
 
 class UpdateChannelReadMarkerRequestRequestTypeDef(
     _RequiredUpdateChannelReadMarkerRequestRequestTypeDef,
     _OptionalUpdateChannelReadMarkerRequestRequestTypeDef,
 ):
     pass
 
+UpdateChannelReadMarkerResponseTypeDef = TypedDict(
+    "UpdateChannelReadMarkerResponseTypeDef",
+    {
+        "ChannelArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateChannelRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateChannelRequestRequestTypeDef",
     {
         "ChannelArn": str,
         "Name": str,
         "Mode": ChannelModeType,
     },
@@ -2993,14 +3136,22 @@
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
 _RequiredUpdatePhoneNumberRequestRequestTypeDef = TypedDict(
     "_RequiredUpdatePhoneNumberRequestRequestTypeDef",
     {
         "PhoneNumberId": str,
     },
 )
 _OptionalUpdatePhoneNumberRequestRequestTypeDef = TypedDict(
@@ -3115,14 +3266,22 @@
         "City": str,
         "State": str,
         "Country": str,
         "PostalCode": str,
     },
 )
 
+GetAccountSettingsResponseTypeDef = TypedDict(
+    "GetAccountSettingsResponseTypeDef",
+    {
+        "AccountSettings": AccountSettingsTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UpdateAccountSettingsRequestRequestTypeDef = TypedDict(
     "UpdateAccountSettingsRequestRequestTypeDef",
     {
         "AccountId": str,
         "AccountSettings": AccountSettingsTypeDef,
     },
 )
@@ -3364,337 +3523,205 @@
         "CreatedTimestamp": datetime,
         "LastMessageTimestamp": datetime,
         "LastUpdatedTimestamp": datetime,
     },
     total=False,
 )
 
-AppInstanceRetentionSettingsTypeDef = TypedDict(
-    "AppInstanceRetentionSettingsTypeDef",
-    {
-        "ChannelRetentionSettings": ChannelRetentionSettingsTypeDef,
-    },
-    total=False,
-)
-
-PutAppInstanceStreamingConfigurationsRequestRequestTypeDef = TypedDict(
-    "PutAppInstanceStreamingConfigurationsRequestRequestTypeDef",
-    {
-        "AppInstanceArn": str,
-        "AppInstanceStreamingConfigurations": Sequence[AppInstanceStreamingConfigurationTypeDef],
-    },
-)
-
-ArtifactsConfigurationTypeDef = TypedDict(
-    "ArtifactsConfigurationTypeDef",
-    {
-        "Audio": AudioArtifactsConfigurationTypeDef,
-        "Video": VideoArtifactsConfigurationTypeDef,
-        "Content": ContentArtifactsConfigurationTypeDef,
-    },
-)
-
-AssociatePhoneNumbersWithVoiceConnectorGroupResponseTypeDef = TypedDict(
-    "AssociatePhoneNumbersWithVoiceConnectorGroupResponseTypeDef",
-    {
-        "PhoneNumberErrors": List[PhoneNumberErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-AssociatePhoneNumbersWithVoiceConnectorResponseTypeDef = TypedDict(
-    "AssociatePhoneNumbersWithVoiceConnectorResponseTypeDef",
-    {
-        "PhoneNumberErrors": List[PhoneNumberErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-BatchDeletePhoneNumberResponseTypeDef = TypedDict(
-    "BatchDeletePhoneNumberResponseTypeDef",
-    {
-        "PhoneNumberErrors": List[PhoneNumberErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-BatchUpdatePhoneNumberResponseTypeDef = TypedDict(
-    "BatchUpdatePhoneNumberResponseTypeDef",
-    {
-        "PhoneNumberErrors": List[PhoneNumberErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 CreateAppInstanceAdminResponseTypeDef = TypedDict(
     "CreateAppInstanceAdminResponseTypeDef",
     {
         "AppInstanceAdmin": IdentityTypeDef,
         "AppInstanceArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateAppInstanceResponseTypeDef = TypedDict(
-    "CreateAppInstanceResponseTypeDef",
-    {
-        "AppInstanceArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateAppInstanceUserResponseTypeDef = TypedDict(
-    "CreateAppInstanceUserResponseTypeDef",
-    {
-        "AppInstanceUserArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateChannelBanResponseTypeDef = TypedDict(
     "CreateChannelBanResponseTypeDef",
     {
         "ChannelArn": str,
         "Member": IdentityTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateChannelMembershipResponseTypeDef = TypedDict(
     "CreateChannelMembershipResponseTypeDef",
     {
         "ChannelArn": str,
         "Member": IdentityTypeDef,
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
-CreateMeetingDialOutResponseTypeDef = TypedDict(
-    "CreateMeetingDialOutResponseTypeDef",
-    {
-        "TransactionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeAppInstanceResponseTypeDef = TypedDict(
-    "DescribeAppInstanceResponseTypeDef",
-    {
-        "AppInstance": AppInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeAppInstanceUserResponseTypeDef = TypedDict(
-    "DescribeAppInstanceUserResponseTypeDef",
-    {
-        "AppInstanceUser": AppInstanceUserTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DisassociatePhoneNumbersFromVoiceConnectorGroupResponseTypeDef = TypedDict(
-    "DisassociatePhoneNumbersFromVoiceConnectorGroupResponseTypeDef",
-    {
-        "PhoneNumberErrors": List[PhoneNumberErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DisassociatePhoneNumbersFromVoiceConnectorResponseTypeDef = TypedDict(
-    "DisassociatePhoneNumbersFromVoiceConnectorResponseTypeDef",
-    {
-        "PhoneNumberErrors": List[PhoneNumberErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetAccountSettingsResponseTypeDef = TypedDict(
-    "GetAccountSettingsResponseTypeDef",
+AppInstanceRetentionSettingsTypeDef = TypedDict(
+    "AppInstanceRetentionSettingsTypeDef",
     {
-        "AccountSettings": AccountSettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ChannelRetentionSettings": ChannelRetentionSettingsTypeDef,
     },
+    total=False,
 )
 
 GetAppInstanceStreamingConfigurationsResponseTypeDef = TypedDict(
     "GetAppInstanceStreamingConfigurationsResponseTypeDef",
     {
         "AppInstanceStreamingConfigurations": List[AppInstanceStreamingConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetPhoneNumberSettingsResponseTypeDef = TypedDict(
-    "GetPhoneNumberSettingsResponseTypeDef",
+PutAppInstanceStreamingConfigurationsRequestRequestTypeDef = TypedDict(
+    "PutAppInstanceStreamingConfigurationsRequestRequestTypeDef",
     {
-        "CallingName": str,
-        "CallingNameUpdatedTimestamp": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "AppInstanceArn": str,
+        "AppInstanceStreamingConfigurations": Sequence[AppInstanceStreamingConfigurationTypeDef],
     },
 )
 
-ListAppInstanceUsersResponseTypeDef = TypedDict(
-    "ListAppInstanceUsersResponseTypeDef",
+PutAppInstanceStreamingConfigurationsResponseTypeDef = TypedDict(
+    "PutAppInstanceStreamingConfigurationsResponseTypeDef",
     {
-        "AppInstanceArn": str,
-        "AppInstanceUsers": List[AppInstanceUserSummaryTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "AppInstanceStreamingConfigurations": List[AppInstanceStreamingConfigurationTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAppInstancesResponseTypeDef = TypedDict(
     "ListAppInstancesResponseTypeDef",
     {
         "AppInstances": List[AppInstanceSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListVoiceConnectorTerminationCredentialsResponseTypeDef = TypedDict(
-    "ListVoiceConnectorTerminationCredentialsResponseTypeDef",
+DescribeAppInstanceResponseTypeDef = TypedDict(
+    "DescribeAppInstanceResponseTypeDef",
     {
-        "Usernames": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "AppInstance": AppInstanceTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-PutAppInstanceStreamingConfigurationsResponseTypeDef = TypedDict(
-    "PutAppInstanceStreamingConfigurationsResponseTypeDef",
+ListAppInstanceUsersResponseTypeDef = TypedDict(
+    "ListAppInstanceUsersResponseTypeDef",
     {
-        "AppInstanceStreamingConfigurations": List[AppInstanceStreamingConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "AppInstanceArn": str,
+        "AppInstanceUsers": List[AppInstanceUserSummaryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-RedactChannelMessageResponseTypeDef = TypedDict(
-    "RedactChannelMessageResponseTypeDef",
+DescribeAppInstanceUserResponseTypeDef = TypedDict(
+    "DescribeAppInstanceUserResponseTypeDef",
     {
-        "ChannelArn": str,
-        "MessageId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "AppInstanceUser": AppInstanceUserTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-SearchAvailablePhoneNumbersResponseTypeDef = TypedDict(
-    "SearchAvailablePhoneNumbersResponseTypeDef",
+ArtifactsConfigurationTypeDef = TypedDict(
+    "ArtifactsConfigurationTypeDef",
     {
-        "E164PhoneNumbers": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Audio": AudioArtifactsConfigurationTypeDef,
+        "Video": VideoArtifactsConfigurationTypeDef,
+        "Content": ContentArtifactsConfigurationTypeDef,
     },
 )
 
-SendChannelMessageResponseTypeDef = TypedDict(
-    "SendChannelMessageResponseTypeDef",
+AssociatePhoneNumbersWithVoiceConnectorGroupResponseTypeDef = TypedDict(
+    "AssociatePhoneNumbersWithVoiceConnectorGroupResponseTypeDef",
     {
-        "ChannelArn": str,
-        "MessageId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "PhoneNumberErrors": List[PhoneNumberErrorTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateAppInstanceResponseTypeDef = TypedDict(
-    "UpdateAppInstanceResponseTypeDef",
+AssociatePhoneNumbersWithVoiceConnectorResponseTypeDef = TypedDict(
+    "AssociatePhoneNumbersWithVoiceConnectorResponseTypeDef",
     {
-        "AppInstanceArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "PhoneNumberErrors": List[PhoneNumberErrorTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateAppInstanceUserResponseTypeDef = TypedDict(
-    "UpdateAppInstanceUserResponseTypeDef",
+BatchDeletePhoneNumberResponseTypeDef = TypedDict(
+    "BatchDeletePhoneNumberResponseTypeDef",
     {
-        "AppInstanceUserArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "PhoneNumberErrors": List[PhoneNumberErrorTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateChannelMessageResponseTypeDef = TypedDict(
-    "UpdateChannelMessageResponseTypeDef",
+BatchUpdatePhoneNumberResponseTypeDef = TypedDict(
+    "BatchUpdatePhoneNumberResponseTypeDef",
     {
-        "ChannelArn": str,
-        "MessageId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "PhoneNumberErrors": List[PhoneNumberErrorTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateChannelReadMarkerResponseTypeDef = TypedDict(
-    "UpdateChannelReadMarkerResponseTypeDef",
+DisassociatePhoneNumbersFromVoiceConnectorGroupResponseTypeDef = TypedDict(
+    "DisassociatePhoneNumbersFromVoiceConnectorGroupResponseTypeDef",
     {
-        "ChannelArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "PhoneNumberErrors": List[PhoneNumberErrorTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateChannelResponseTypeDef = TypedDict(
-    "UpdateChannelResponseTypeDef",
+DisassociatePhoneNumbersFromVoiceConnectorResponseTypeDef = TypedDict(
+    "DisassociatePhoneNumbersFromVoiceConnectorResponseTypeDef",
     {
-        "ChannelArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "PhoneNumberErrors": List[PhoneNumberErrorTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateAttendeeResponseTypeDef = TypedDict(
     "CreateAttendeeResponseTypeDef",
     {
         "Attendee": AttendeeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAttendeeResponseTypeDef = TypedDict(
     "GetAttendeeResponseTypeDef",
     {
         "Attendee": AttendeeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAttendeesResponseTypeDef = TypedDict(
     "ListAttendeesResponseTypeDef",
     {
         "Attendees": List[AttendeeTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchCreateAttendeeResponseTypeDef = TypedDict(
     "BatchCreateAttendeeResponseTypeDef",
     {
         "Attendees": List[AttendeeTypeDef],
         "Errors": List[CreateAttendeeErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchCreateRoomMembershipRequestRequestTypeDef = TypedDict(
     "BatchCreateRoomMembershipRequestRequestTypeDef",
     {
         "AccountId": str,
@@ -3703,98 +3730,98 @@
     },
 )
 
 BatchCreateRoomMembershipResponseTypeDef = TypedDict(
     "BatchCreateRoomMembershipResponseTypeDef",
     {
         "Errors": List[MemberErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchSuspendUserResponseTypeDef = TypedDict(
     "BatchSuspendUserResponseTypeDef",
     {
         "UserErrors": List[UserErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchUnsuspendUserResponseTypeDef = TypedDict(
     "BatchUnsuspendUserResponseTypeDef",
     {
         "UserErrors": List[UserErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchUpdateUserResponseTypeDef = TypedDict(
     "BatchUpdateUserResponseTypeDef",
     {
         "UserErrors": List[UserErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchUpdatePhoneNumberRequestRequestTypeDef = TypedDict(
     "BatchUpdatePhoneNumberRequestRequestTypeDef",
     {
         "UpdatePhoneNumberRequestItems": Sequence[UpdatePhoneNumberRequestItemTypeDef],
     },
 )
 
 CreateBotResponseTypeDef = TypedDict(
     "CreateBotResponseTypeDef",
     {
         "Bot": BotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetBotResponseTypeDef = TypedDict(
     "GetBotResponseTypeDef",
     {
         "Bot": BotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListBotsResponseTypeDef = TypedDict(
     "ListBotsResponseTypeDef",
     {
         "Bots": List[BotTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RegenerateSecurityTokenResponseTypeDef = TypedDict(
     "RegenerateSecurityTokenResponseTypeDef",
     {
         "Bot": BotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateBotResponseTypeDef = TypedDict(
     "UpdateBotResponseTypeDef",
     {
         "Bot": BotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ValidateE911AddressResponseTypeDef = TypedDict(
     "ValidateE911AddressResponseTypeDef",
     {
         "ValidationResult": int,
         "AddressExternalId": str,
         "Address": AddressTypeDef,
         "CandidateAddressList": List[CandidateAddressTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ChannelMembershipForAppInstanceUserSummaryTypeDef = TypedDict(
     "ChannelMembershipForAppInstanceUserSummaryTypeDef",
     {
         "ChannelSummary": ChannelSummaryTypeDef,
@@ -3812,15 +3839,15 @@
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
 
 _RequiredCreateAppInstanceRequestRequestTypeDef = TypedDict(
     "_RequiredCreateAppInstanceRequestRequestTypeDef",
     {
         "Name": str,
@@ -3929,31 +3956,31 @@
 ):
     pass
 
 ListAttendeeTagsResponseTypeDef = TypedDict(
     "ListAttendeeTagsResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMeetingTagsResponseTypeDef = TypedDict(
     "ListMeetingTagsResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTagsForResourceResponseTypeDef = TypedDict(
     "ListTagsForResourceResponseTypeDef",
     {
         "Tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagAttendeeRequestRequestTypeDef = TypedDict(
     "TagAttendeeRequestRequestTypeDef",
     {
         "MeetingId": str,
@@ -4027,56 +4054,56 @@
 ):
     pass
 
 CreateRoomResponseTypeDef = TypedDict(
     "CreateRoomResponseTypeDef",
     {
         "Room": RoomTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRoomResponseTypeDef = TypedDict(
     "GetRoomResponseTypeDef",
     {
         "Room": RoomTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRoomsResponseTypeDef = TypedDict(
     "ListRoomsResponseTypeDef",
     {
         "Rooms": List[RoomTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateRoomResponseTypeDef = TypedDict(
     "UpdateRoomResponseTypeDef",
     {
         "Room": RoomTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateSipMediaApplicationCallResponseTypeDef = TypedDict(
     "CreateSipMediaApplicationCallResponseTypeDef",
     {
         "SipMediaApplicationCall": SipMediaApplicationCallTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateSipMediaApplicationCallResponseTypeDef = TypedDict(
     "UpdateSipMediaApplicationCallResponseTypeDef",
     {
         "SipMediaApplicationCall": SipMediaApplicationCallTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateSipMediaApplicationRequestRequestTypeDef = TypedDict(
     "CreateSipMediaApplicationRequestRequestTypeDef",
     {
         "AwsRegion": str,
@@ -4219,40 +4246,40 @@
     total=False,
 )
 
 CreateVoiceConnectorResponseTypeDef = TypedDict(
     "CreateVoiceConnectorResponseTypeDef",
     {
         "VoiceConnector": VoiceConnectorTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetVoiceConnectorResponseTypeDef = TypedDict(
     "GetVoiceConnectorResponseTypeDef",
     {
         "VoiceConnector": VoiceConnectorTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVoiceConnectorsResponseTypeDef = TypedDict(
     "ListVoiceConnectorsResponseTypeDef",
     {
         "VoiceConnectors": List[VoiceConnectorTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateVoiceConnectorResponseTypeDef = TypedDict(
     "UpdateVoiceConnectorResponseTypeDef",
     {
         "VoiceConnector": VoiceConnectorTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutVoiceConnectorTerminationCredentialsRequestRequestTypeDef = TypedDict(
     "_RequiredPutVoiceConnectorTerminationCredentialsRequestRequestTypeDef",
     {
         "VoiceConnectorId": str,
@@ -4289,32 +4316,32 @@
     total=False,
 )
 
 GetEventsConfigurationResponseTypeDef = TypedDict(
     "GetEventsConfigurationResponseTypeDef",
     {
         "EventsConfiguration": EventsConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutEventsConfigurationResponseTypeDef = TypedDict(
     "PutEventsConfigurationResponseTypeDef",
     {
         "EventsConfiguration": EventsConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetGlobalSettingsResponseTypeDef = TypedDict(
     "GetGlobalSettingsResponseTypeDef",
     {
         "BusinessCalling": BusinessCallingSettingsTypeDef,
         "VoiceConnector": VoiceConnectorSettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateGlobalSettingsRequestRequestTypeDef = TypedDict(
     "UpdateGlobalSettingsRequestRequestTypeDef",
     {
         "BusinessCalling": BusinessCallingSettingsTypeDef,
@@ -4323,23 +4350,23 @@
     total=False,
 )
 
 GetMessagingSessionEndpointResponseTypeDef = TypedDict(
     "GetMessagingSessionEndpointResponseTypeDef",
     {
         "Endpoint": MessagingSessionEndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSipMediaApplicationLoggingConfigurationResponseTypeDef = TypedDict(
     "GetSipMediaApplicationLoggingConfigurationResponseTypeDef",
     {
         "SipMediaApplicationLoggingConfiguration": SipMediaApplicationLoggingConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutSipMediaApplicationLoggingConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredPutSipMediaApplicationLoggingConfigurationRequestRequestTypeDef",
     {
         "SipMediaApplicationId": str,
@@ -4359,23 +4386,23 @@
 ):
     pass
 
 PutSipMediaApplicationLoggingConfigurationResponseTypeDef = TypedDict(
     "PutSipMediaApplicationLoggingConfigurationResponseTypeDef",
     {
         "SipMediaApplicationLoggingConfiguration": SipMediaApplicationLoggingConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetVoiceConnectorLoggingConfigurationResponseTypeDef = TypedDict(
     "GetVoiceConnectorLoggingConfigurationResponseTypeDef",
     {
         "LoggingConfiguration": LoggingConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutVoiceConnectorLoggingConfigurationRequestRequestTypeDef = TypedDict(
     "PutVoiceConnectorLoggingConfigurationRequestRequestTypeDef",
     {
         "VoiceConnectorId": str,
@@ -4383,47 +4410,47 @@
     },
 )
 
 PutVoiceConnectorLoggingConfigurationResponseTypeDef = TypedDict(
     "PutVoiceConnectorLoggingConfigurationResponseTypeDef",
     {
         "LoggingConfiguration": LoggingConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetVoiceConnectorProxyResponseTypeDef = TypedDict(
     "GetVoiceConnectorProxyResponseTypeDef",
     {
         "Proxy": ProxyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutVoiceConnectorProxyResponseTypeDef = TypedDict(
     "PutVoiceConnectorProxyResponseTypeDef",
     {
         "Proxy": ProxyTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetVoiceConnectorTerminationHealthResponseTypeDef = TypedDict(
     "GetVoiceConnectorTerminationHealthResponseTypeDef",
     {
         "TerminationHealth": TerminationHealthTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetVoiceConnectorTerminationResponseTypeDef = TypedDict(
     "GetVoiceConnectorTerminationResponseTypeDef",
     {
         "Termination": TerminationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutVoiceConnectorTerminationRequestRequestTypeDef = TypedDict(
     "PutVoiceConnectorTerminationRequestRequestTypeDef",
     {
         "VoiceConnectorId": str,
@@ -4431,63 +4458,31 @@
     },
 )
 
 PutVoiceConnectorTerminationResponseTypeDef = TypedDict(
     "PutVoiceConnectorTerminationResponseTypeDef",
     {
         "Termination": TerminationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InviteUsersResponseTypeDef = TypedDict(
     "InviteUsersResponseTypeDef",
     {
         "Invites": List[InviteTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListAccountsRequestListAccountsPaginateTypeDef = TypedDict(
-    "ListAccountsRequestListAccountsPaginateTypeDef",
-    {
-        "Name": str,
-        "UserEmail": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListUsersRequestListUsersPaginateTypeDef = TypedDict(
-    "_RequiredListUsersRequestListUsersPaginateTypeDef",
-    {
-        "AccountId": str,
-    },
-)
-_OptionalListUsersRequestListUsersPaginateTypeDef = TypedDict(
-    "_OptionalListUsersRequestListUsersPaginateTypeDef",
-    {
-        "UserEmail": str,
-        "UserType": UserTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListUsersRequestListUsersPaginateTypeDef(
-    _RequiredListUsersRequestListUsersPaginateTypeDef,
-    _OptionalListUsersRequestListUsersPaginateTypeDef,
-):
-    pass
-
 ListSupportedPhoneNumberCountriesResponseTypeDef = TypedDict(
     "ListSupportedPhoneNumberCountriesResponseTypeDef",
     {
         "PhoneNumberCountries": List[PhoneNumberCountryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 MeetingTypeDef = TypedDict(
     "MeetingTypeDef",
     {
         "MeetingId": str,
@@ -4616,40 +4611,40 @@
     },
 )
 
 CreateAccountResponseTypeDef = TypedDict(
     "CreateAccountResponseTypeDef",
     {
         "Account": AccountTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAccountResponseTypeDef = TypedDict(
     "GetAccountResponseTypeDef",
     {
         "Account": AccountTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAccountsResponseTypeDef = TypedDict(
     "ListAccountsResponseTypeDef",
     {
         "Accounts": List[AccountTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAccountResponseTypeDef = TypedDict(
     "UpdateAccountResponseTypeDef",
     {
         "Account": AccountTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchUpdateUserRequestRequestTypeDef = TypedDict(
     "BatchUpdateUserRequestRequestTypeDef",
     {
         "AccountId": str,
@@ -4657,164 +4652,164 @@
     },
 )
 
 CreateUserResponseTypeDef = TypedDict(
     "CreateUserResponseTypeDef",
     {
         "User": UserTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetUserResponseTypeDef = TypedDict(
     "GetUserResponseTypeDef",
     {
         "User": UserTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListUsersResponseTypeDef = TypedDict(
     "ListUsersResponseTypeDef",
     {
         "Users": List[UserTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResetPersonalPINResponseTypeDef = TypedDict(
     "ResetPersonalPINResponseTypeDef",
     {
         "User": UserTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateUserResponseTypeDef = TypedDict(
     "UpdateUserResponseTypeDef",
     {
         "User": UserTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAppInstanceAdminsResponseTypeDef = TypedDict(
     "ListAppInstanceAdminsResponseTypeDef",
     {
         "AppInstanceArn": str,
         "AppInstanceAdmins": List[AppInstanceAdminSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAppInstanceAdminResponseTypeDef = TypedDict(
     "DescribeAppInstanceAdminResponseTypeDef",
     {
         "AppInstanceAdmin": AppInstanceAdminTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
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
 
 ListChannelMessagesResponseTypeDef = TypedDict(
     "ListChannelMessagesResponseTypeDef",
     {
         "ChannelArn": str,
         "NextToken": str,
         "ChannelMessages": List[ChannelMessageSummaryTypeDef],
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
 
 DescribeChannelResponseTypeDef = TypedDict(
     "DescribeChannelResponseTypeDef",
     {
         "Channel": ChannelTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAppInstanceRetentionSettingsResponseTypeDef = TypedDict(
     "GetAppInstanceRetentionSettingsResponseTypeDef",
     {
         "AppInstanceRetentionSettings": AppInstanceRetentionSettingsTypeDef,
         "InitiateDeletionTimestamp": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutAppInstanceRetentionSettingsRequestRequestTypeDef = TypedDict(
     "PutAppInstanceRetentionSettingsRequestRequestTypeDef",
     {
         "AppInstanceArn": str,
@@ -4823,49 +4818,49 @@
 )
 
 PutAppInstanceRetentionSettingsResponseTypeDef = TypedDict(
     "PutAppInstanceRetentionSettingsResponseTypeDef",
     {
         "AppInstanceRetentionSettings": AppInstanceRetentionSettingsTypeDef,
         "InitiateDeletionTimestamp": datetime,
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
 
 BatchCreateAttendeeRequestRequestTypeDef = TypedDict(
     "BatchCreateAttendeeRequestRequestTypeDef",
     {
         "MeetingId": str,
@@ -4898,114 +4893,114 @@
 ):
     pass
 
 CreateSipMediaApplicationResponseTypeDef = TypedDict(
     "CreateSipMediaApplicationResponseTypeDef",
     {
         "SipMediaApplication": SipMediaApplicationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSipMediaApplicationResponseTypeDef = TypedDict(
     "GetSipMediaApplicationResponseTypeDef",
     {
         "SipMediaApplication": SipMediaApplicationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSipMediaApplicationsResponseTypeDef = TypedDict(
     "ListSipMediaApplicationsResponseTypeDef",
     {
         "SipMediaApplications": List[SipMediaApplicationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateSipMediaApplicationResponseTypeDef = TypedDict(
     "UpdateSipMediaApplicationResponseTypeDef",
     {
         "SipMediaApplication": SipMediaApplicationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateSipRuleResponseTypeDef = TypedDict(
     "CreateSipRuleResponseTypeDef",
     {
         "SipRule": SipRuleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetSipRuleResponseTypeDef = TypedDict(
     "GetSipRuleResponseTypeDef",
     {
         "SipRule": SipRuleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSipRulesResponseTypeDef = TypedDict(
     "ListSipRulesResponseTypeDef",
     {
         "SipRules": List[SipRuleTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateSipRuleResponseTypeDef = TypedDict(
     "UpdateSipRuleResponseTypeDef",
     {
         "SipRule": SipRuleTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateVoiceConnectorGroupResponseTypeDef = TypedDict(
     "CreateVoiceConnectorGroupResponseTypeDef",
     {
         "VoiceConnectorGroup": VoiceConnectorGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetVoiceConnectorGroupResponseTypeDef = TypedDict(
     "GetVoiceConnectorGroupResponseTypeDef",
     {
         "VoiceConnectorGroup": VoiceConnectorGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVoiceConnectorGroupsResponseTypeDef = TypedDict(
     "ListVoiceConnectorGroupsResponseTypeDef",
     {
         "VoiceConnectorGroups": List[VoiceConnectorGroupTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateVoiceConnectorGroupResponseTypeDef = TypedDict(
     "UpdateVoiceConnectorGroupResponseTypeDef",
     {
         "VoiceConnectorGroup": VoiceConnectorGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetVoiceConnectorEmergencyCallingConfigurationResponseTypeDef = TypedDict(
     "GetVoiceConnectorEmergencyCallingConfigurationResponseTypeDef",
     {
         "EmergencyCallingConfiguration": EmergencyCallingConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutVoiceConnectorEmergencyCallingConfigurationRequestRequestTypeDef = TypedDict(
     "PutVoiceConnectorEmergencyCallingConfigurationRequestRequestTypeDef",
     {
         "VoiceConnectorId": str,
@@ -5013,15 +5008,15 @@
     },
 )
 
 PutVoiceConnectorEmergencyCallingConfigurationResponseTypeDef = TypedDict(
     "PutVoiceConnectorEmergencyCallingConfigurationResponseTypeDef",
     {
         "EmergencyCallingConfiguration": EmergencyCallingConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartMeetingTranscriptionRequestRequestTypeDef = TypedDict(
     "StartMeetingTranscriptionRequestRequestTypeDef",
     {
         "MeetingId": str,
@@ -5029,100 +5024,100 @@
     },
 )
 
 CreateMeetingResponseTypeDef = TypedDict(
     "CreateMeetingResponseTypeDef",
     {
         "Meeting": MeetingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateMeetingWithAttendeesResponseTypeDef = TypedDict(
     "CreateMeetingWithAttendeesResponseTypeDef",
     {
         "Meeting": MeetingTypeDef,
         "Attendees": List[AttendeeTypeDef],
         "Errors": List[CreateAttendeeErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMeetingResponseTypeDef = TypedDict(
     "GetMeetingResponseTypeDef",
     {
         "Meeting": MeetingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMeetingsResponseTypeDef = TypedDict(
     "ListMeetingsResponseTypeDef",
     {
         "Meetings": List[MeetingTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateRoomMembershipResponseTypeDef = TypedDict(
     "CreateRoomMembershipResponseTypeDef",
     {
         "RoomMembership": RoomMembershipTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRoomMembershipsResponseTypeDef = TypedDict(
     "ListRoomMembershipsResponseTypeDef",
     {
         "RoomMemberships": List[RoomMembershipTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateRoomMembershipResponseTypeDef = TypedDict(
     "UpdateRoomMembershipResponseTypeDef",
     {
         "RoomMembership": RoomMembershipTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreatePhoneNumberOrderResponseTypeDef = TypedDict(
     "CreatePhoneNumberOrderResponseTypeDef",
     {
         "PhoneNumberOrder": PhoneNumberOrderTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetPhoneNumberOrderResponseTypeDef = TypedDict(
     "GetPhoneNumberOrderResponseTypeDef",
     {
         "PhoneNumberOrder": PhoneNumberOrderTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPhoneNumberOrdersResponseTypeDef = TypedDict(
     "ListPhoneNumberOrdersResponseTypeDef",
     {
         "PhoneNumberOrders": List[PhoneNumberOrderTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetVoiceConnectorOriginationResponseTypeDef = TypedDict(
     "GetVoiceConnectorOriginationResponseTypeDef",
     {
         "Origination": OriginationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutVoiceConnectorOriginationRequestRequestTypeDef = TypedDict(
     "PutVoiceConnectorOriginationRequestRequestTypeDef",
     {
         "VoiceConnectorId": str,
@@ -5130,90 +5125,90 @@
     },
 )
 
 PutVoiceConnectorOriginationResponseTypeDef = TypedDict(
     "PutVoiceConnectorOriginationResponseTypeDef",
     {
         "Origination": OriginationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateProxySessionResponseTypeDef = TypedDict(
     "CreateProxySessionResponseTypeDef",
     {
         "ProxySession": ProxySessionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetProxySessionResponseTypeDef = TypedDict(
     "GetProxySessionResponseTypeDef",
     {
         "ProxySession": ProxySessionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProxySessionsResponseTypeDef = TypedDict(
     "ListProxySessionsResponseTypeDef",
     {
         "ProxySessions": List[ProxySessionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateProxySessionResponseTypeDef = TypedDict(
     "UpdateProxySessionResponseTypeDef",
     {
         "ProxySession": ProxySessionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetPhoneNumberResponseTypeDef = TypedDict(
     "GetPhoneNumberResponseTypeDef",
     {
         "PhoneNumber": PhoneNumberTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPhoneNumbersResponseTypeDef = TypedDict(
     "ListPhoneNumbersResponseTypeDef",
     {
         "PhoneNumbers": List[PhoneNumberTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RestorePhoneNumberResponseTypeDef = TypedDict(
     "RestorePhoneNumberResponseTypeDef",
     {
         "PhoneNumber": PhoneNumberTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdatePhoneNumberResponseTypeDef = TypedDict(
     "UpdatePhoneNumberResponseTypeDef",
     {
         "PhoneNumber": PhoneNumberTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRetentionSettingsResponseTypeDef = TypedDict(
     "GetRetentionSettingsResponseTypeDef",
     {
         "RetentionSettings": RetentionSettingsTypeDef,
         "InitiateDeletionTimestamp": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutRetentionSettingsRequestRequestTypeDef = TypedDict(
     "PutRetentionSettingsRequestRequestTypeDef",
     {
         "AccountId": str,
@@ -5222,15 +5217,15 @@
 )
 
 PutRetentionSettingsResponseTypeDef = TypedDict(
     "PutRetentionSettingsResponseTypeDef",
     {
         "RetentionSettings": RetentionSettingsTypeDef,
         "InitiateDeletionTimestamp": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ChimeSdkMeetingConfigurationTypeDef = TypedDict(
     "ChimeSdkMeetingConfigurationTypeDef",
     {
         "SourceConfiguration": SourceConfigurationTypeDef,
@@ -5239,15 +5234,15 @@
     total=False,
 )
 
 GetVoiceConnectorStreamingConfigurationResponseTypeDef = TypedDict(
     "GetVoiceConnectorStreamingConfigurationResponseTypeDef",
     {
         "StreamingConfiguration": StreamingConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutVoiceConnectorStreamingConfigurationRequestRequestTypeDef = TypedDict(
     "PutVoiceConnectorStreamingConfigurationRequestRequestTypeDef",
     {
         "VoiceConnectorId": str,
@@ -5255,23 +5250,23 @@
     },
 )
 
 PutVoiceConnectorStreamingConfigurationResponseTypeDef = TypedDict(
     "PutVoiceConnectorStreamingConfigurationResponseTypeDef",
     {
         "StreamingConfiguration": StreamingConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetUserSettingsResponseTypeDef = TypedDict(
     "GetUserSettingsResponseTypeDef",
     {
         "UserSettings": UserSettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateUserSettingsRequestRequestTypeDef = TypedDict(
     "UpdateUserSettingsRequestRequestTypeDef",
     {
         "AccountId": str,
@@ -5320,27 +5315,27 @@
     total=False,
 )
 
 CreateMediaCapturePipelineResponseTypeDef = TypedDict(
     "CreateMediaCapturePipelineResponseTypeDef",
     {
         "MediaCapturePipeline": MediaCapturePipelineTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMediaCapturePipelineResponseTypeDef = TypedDict(
     "GetMediaCapturePipelineResponseTypeDef",
     {
         "MediaCapturePipeline": MediaCapturePipelineTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMediaCapturePipelinesResponseTypeDef = TypedDict(
     "ListMediaCapturePipelinesResponseTypeDef",
     {
         "MediaCapturePipelines": List[MediaCapturePipelineTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-chime-2.5.0.post1/types_aiobotocore_chime.egg-info/PKG-INFO` & `types-aiobotocore-chime-2.5.1/types_aiobotocore_chime.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-chime
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Chime 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Chime 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-chime"></a>
 
 # types-aiobotocore-chime
 
 [![PyPI - types-aiobotocore-chime](https://img.shields.io/pypi/v/types-aiobotocore-chime.svg?color=blue)](https://pypi.org/project/types-aiobotocore-chime)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-chime.svg?color=blue)](https://pypi.org/project/types-aiobotocore-chime)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-chime?color=blue)](https://pypistats.org/packages/types-aiobotocore-chime)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Chime 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime)
+[aiobotocore.Chime 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/chime.html#Chime)
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
 [types-aiobotocore-chime docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_chime/).
 
 See how it helps to find and fix potential bugs:
 
@@ -382,15 +382,14 @@
     AppInstanceUserTypeDef,
     AudioArtifactsConfigurationTypeDef,
     ContentArtifactsConfigurationTypeDef,
     VideoArtifactsConfigurationTypeDef,
     AssociatePhoneNumberWithUserRequestRequestTypeDef,
     AssociatePhoneNumbersWithVoiceConnectorGroupRequestRequestTypeDef,
     PhoneNumberErrorTypeDef,
-    ResponseMetadataTypeDef,
     AssociatePhoneNumbersWithVoiceConnectorRequestRequestTypeDef,
     AttendeeTypeDef,
     CreateAttendeeErrorTypeDef,
     BatchCreateChannelMembershipErrorTypeDef,
     BatchCreateChannelMembershipRequestRequestTypeDef,
     MembershipItemTypeDef,
     MemberErrorTypeDef,
@@ -403,19 +402,23 @@
     BusinessCallingSettingsTypeDef,
     CandidateAddressTypeDef,
     ChannelSummaryTypeDef,
     ConversationRetentionSettingsTypeDef,
     CreateAccountRequestRequestTypeDef,
     CreateAppInstanceAdminRequestRequestTypeDef,
     TagTypeDef,
+    CreateAppInstanceResponseTypeDef,
+    CreateAppInstanceUserResponseTypeDef,
     CreateBotRequestRequestTypeDef,
     CreateChannelBanRequestRequestTypeDef,
     CreateChannelMembershipRequestRequestTypeDef,
     CreateChannelModeratorRequestRequestTypeDef,
+    CreateChannelResponseTypeDef,
     CreateMeetingDialOutRequestRequestTypeDef,
+    CreateMeetingDialOutResponseTypeDef,
     MeetingNotificationConfigurationTypeDef,
     CreatePhoneNumberOrderRequestRequestTypeDef,
     GeoMatchParamsTypeDef,
     CreateRoomMembershipRequestRequestTypeDef,
     CreateRoomRequestRequestTypeDef,
     RoomTypeDef,
     CreateSipMediaApplicationCallRequestRequestTypeDef,
@@ -465,14 +468,15 @@
     DescribeChannelModeratedByAppInstanceUserRequestRequestTypeDef,
     DescribeChannelModeratorRequestRequestTypeDef,
     DescribeChannelRequestRequestTypeDef,
     DisassociatePhoneNumberFromUserRequestRequestTypeDef,
     DisassociatePhoneNumbersFromVoiceConnectorGroupRequestRequestTypeDef,
     DisassociatePhoneNumbersFromVoiceConnectorRequestRequestTypeDef,
     DisassociateSigninDelegateGroupsFromAccountRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EngineTranscribeMedicalSettingsTypeDef,
     EngineTranscribeSettingsTypeDef,
     EventsConfigurationTypeDef,
     GetAccountRequestRequestTypeDef,
     GetAccountSettingsRequestRequestTypeDef,
     GetAppInstanceRetentionSettingsRequestRequestTypeDef,
     GetAppInstanceStreamingConfigurationsRequestRequestTypeDef,
@@ -482,14 +486,15 @@
     GetEventsConfigurationRequestRequestTypeDef,
     VoiceConnectorSettingsTypeDef,
     GetMediaCapturePipelineRequestRequestTypeDef,
     GetMeetingRequestRequestTypeDef,
     MessagingSessionEndpointTypeDef,
     GetPhoneNumberOrderRequestRequestTypeDef,
     GetPhoneNumberRequestRequestTypeDef,
+    GetPhoneNumberSettingsResponseTypeDef,
     GetProxySessionRequestRequestTypeDef,
     GetRetentionSettingsRequestRequestTypeDef,
     GetRoomRequestRequestTypeDef,
     GetSipMediaApplicationLoggingConfigurationRequestRequestTypeDef,
     SipMediaApplicationLoggingConfigurationTypeDef,
     GetSipMediaApplicationRequestRequestTypeDef,
     GetSipRuleRequestRequestTypeDef,
@@ -506,15 +511,15 @@
     GetVoiceConnectorStreamingConfigurationRequestRequestTypeDef,
     GetVoiceConnectorTerminationHealthRequestRequestTypeDef,
     TerminationHealthTypeDef,
     GetVoiceConnectorTerminationRequestRequestTypeDef,
     TerminationTypeDef,
     InviteTypeDef,
     InviteUsersRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListAccountsRequestListAccountsPaginateTypeDef,
     ListAccountsRequestRequestTypeDef,
     ListAppInstanceAdminsRequestRequestTypeDef,
     ListAppInstanceUsersRequestRequestTypeDef,
     ListAppInstancesRequestRequestTypeDef,
     ListAttendeeTagsRequestRequestTypeDef,
     ListAttendeesRequestRequestTypeDef,
     ListBotsRequestRequestTypeDef,
@@ -534,59 +539,72 @@
     ListRoomMembershipsRequestRequestTypeDef,
     ListRoomsRequestRequestTypeDef,
     ListSipMediaApplicationsRequestRequestTypeDef,
     ListSipRulesRequestRequestTypeDef,
     ListSupportedPhoneNumberCountriesRequestRequestTypeDef,
     PhoneNumberCountryTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListUsersRequestListUsersPaginateTypeDef,
     ListUsersRequestRequestTypeDef,
     ListVoiceConnectorGroupsRequestRequestTypeDef,
     ListVoiceConnectorTerminationCredentialsRequestRequestTypeDef,
+    ListVoiceConnectorTerminationCredentialsResponseTypeDef,
     ListVoiceConnectorsRequestRequestTypeDef,
     LogoutUserRequestRequestTypeDef,
     MediaPlacementTypeDef,
     MemberTypeDef,
     OrderedPhoneNumberTypeDef,
     OriginationRouteTypeDef,
+    PaginatorConfigTypeDef,
     ParticipantTypeDef,
     PhoneNumberAssociationTypeDef,
     PhoneNumberCapabilitiesTypeDef,
     PutEventsConfigurationRequestRequestTypeDef,
     PutVoiceConnectorProxyRequestRequestTypeDef,
     RedactChannelMessageRequestRequestTypeDef,
+    RedactChannelMessageResponseTypeDef,
     RedactConversationMessageRequestRequestTypeDef,
     RedactRoomMessageRequestRequestTypeDef,
     RegenerateSecurityTokenRequestRequestTypeDef,
     ResetPersonalPINRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     RestorePhoneNumberRequestRequestTypeDef,
     RoomRetentionSettingsTypeDef,
     SearchAvailablePhoneNumbersRequestRequestTypeDef,
+    SearchAvailablePhoneNumbersResponseTypeDef,
     SelectedVideoStreamsTypeDef,
     SendChannelMessageRequestRequestTypeDef,
+    SendChannelMessageResponseTypeDef,
     StopMeetingTranscriptionRequestRequestTypeDef,
     StreamingNotificationTargetTypeDef,
     TelephonySettingsTypeDef,
     UntagAttendeeRequestRequestTypeDef,
     UntagMeetingRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateAccountRequestRequestTypeDef,
     UpdateAppInstanceRequestRequestTypeDef,
+    UpdateAppInstanceResponseTypeDef,
     UpdateAppInstanceUserRequestRequestTypeDef,
+    UpdateAppInstanceUserResponseTypeDef,
     UpdateBotRequestRequestTypeDef,
     UpdateChannelMessageRequestRequestTypeDef,
+    UpdateChannelMessageResponseTypeDef,
     UpdateChannelReadMarkerRequestRequestTypeDef,
+    UpdateChannelReadMarkerResponseTypeDef,
     UpdateChannelRequestRequestTypeDef,
+    UpdateChannelResponseTypeDef,
     UpdatePhoneNumberRequestRequestTypeDef,
     UpdatePhoneNumberSettingsRequestRequestTypeDef,
     UpdateProxySessionRequestRequestTypeDef,
     UpdateRoomMembershipRequestRequestTypeDef,
     UpdateRoomRequestRequestTypeDef,
     UpdateSipMediaApplicationCallRequestRequestTypeDef,
     UpdateVoiceConnectorRequestRequestTypeDef,
     ValidateE911AddressRequestRequestTypeDef,
+    GetAccountSettingsResponseTypeDef,
     UpdateAccountSettingsRequestRequestTypeDef,
     AccountTypeDef,
     AssociateSigninDelegateGroupsWithAccountRequestRequestTypeDef,
     UpdateUserRequestItemTypeDef,
     UpdateUserRequestRequestTypeDef,
     UserTypeDef,
     AppInstanceAdminSummaryTypeDef,
@@ -597,49 +615,33 @@
     ChannelMembershipSummaryTypeDef,
     ChannelMembershipTypeDef,
     ChannelMessageSummaryTypeDef,
     ChannelMessageTypeDef,
     ChannelModeratorSummaryTypeDef,
     ChannelModeratorTypeDef,
     ChannelTypeDef,
+    CreateAppInstanceAdminResponseTypeDef,
+    CreateChannelBanResponseTypeDef,
+    CreateChannelMembershipResponseTypeDef,
+    CreateChannelModeratorResponseTypeDef,
     AppInstanceRetentionSettingsTypeDef,
+    GetAppInstanceStreamingConfigurationsResponseTypeDef,
     PutAppInstanceStreamingConfigurationsRequestRequestTypeDef,
+    PutAppInstanceStreamingConfigurationsResponseTypeDef,
+    ListAppInstancesResponseTypeDef,
+    DescribeAppInstanceResponseTypeDef,
+    ListAppInstanceUsersResponseTypeDef,
+    DescribeAppInstanceUserResponseTypeDef,
     ArtifactsConfigurationTypeDef,
     AssociatePhoneNumbersWithVoiceConnectorGroupResponseTypeDef,
     AssociatePhoneNumbersWithVoiceConnectorResponseTypeDef,
     BatchDeletePhoneNumberResponseTypeDef,
     BatchUpdatePhoneNumberResponseTypeDef,
-    CreateAppInstanceAdminResponseTypeDef,
-    CreateAppInstanceResponseTypeDef,
-    CreateAppInstanceUserResponseTypeDef,
-    CreateChannelBanResponseTypeDef,
-    CreateChannelMembershipResponseTypeDef,
-    CreateChannelModeratorResponseTypeDef,
-    CreateChannelResponseTypeDef,
-    CreateMeetingDialOutResponseTypeDef,
-    DescribeAppInstanceResponseTypeDef,
-    DescribeAppInstanceUserResponseTypeDef,
     DisassociatePhoneNumbersFromVoiceConnectorGroupResponseTypeDef,
     DisassociatePhoneNumbersFromVoiceConnectorResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetAccountSettingsResponseTypeDef,
-    GetAppInstanceStreamingConfigurationsResponseTypeDef,
-    GetPhoneNumberSettingsResponseTypeDef,
-    ListAppInstanceUsersResponseTypeDef,
-    ListAppInstancesResponseTypeDef,
-    ListVoiceConnectorTerminationCredentialsResponseTypeDef,
-    PutAppInstanceStreamingConfigurationsResponseTypeDef,
-    RedactChannelMessageResponseTypeDef,
-    SearchAvailablePhoneNumbersResponseTypeDef,
-    SendChannelMessageResponseTypeDef,
-    UpdateAppInstanceResponseTypeDef,
-    UpdateAppInstanceUserResponseTypeDef,
-    UpdateChannelMessageResponseTypeDef,
-    UpdateChannelReadMarkerResponseTypeDef,
-    UpdateChannelResponseTypeDef,
     CreateAttendeeResponseTypeDef,
     GetAttendeeResponseTypeDef,
     ListAttendeesResponseTypeDef,
     BatchCreateAttendeeResponseTypeDef,
     BatchCreateRoomMembershipRequestRequestTypeDef,
     BatchCreateRoomMembershipResponseTypeDef,
     BatchSuspendUserResponseTypeDef,
@@ -704,16 +706,14 @@
     GetVoiceConnectorProxyResponseTypeDef,
     PutVoiceConnectorProxyResponseTypeDef,
     GetVoiceConnectorTerminationHealthResponseTypeDef,
     GetVoiceConnectorTerminationResponseTypeDef,
     PutVoiceConnectorTerminationRequestRequestTypeDef,
     PutVoiceConnectorTerminationResponseTypeDef,
     InviteUsersResponseTypeDef,
-    ListAccountsRequestListAccountsPaginateTypeDef,
-    ListUsersRequestListUsersPaginateTypeDef,
     ListSupportedPhoneNumberCountriesResponseTypeDef,
     MeetingTypeDef,
     RoomMembershipTypeDef,
     PhoneNumberOrderTypeDef,
     OriginationTypeDef,
     ProxySessionTypeDef,
     PhoneNumberTypeDef,
@@ -813,43 +813,43 @@
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

### Comparing `types-aiobotocore-chime-2.5.0.post1/types_aiobotocore_chime.egg-info/SOURCES.txt` & `types-aiobotocore-chime-2.5.1/types_aiobotocore_chime.egg-info/SOURCES.txt`

 * *Files identical despite different names*

