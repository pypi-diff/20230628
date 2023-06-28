# Comparing `tmp/types-aiobotocore-medialive-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-medialive-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-medialive-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:58 2023, max compression
+gzip compressed data, was "types-aiobotocore-medialive-2.5.1.tar", last modified: Wed Jun 28 01:43:49 2023, max compression
```

## Comparing `types-aiobotocore-medialive-2.5.0.post1.tar` & `types-aiobotocore-medialive-2.5.1.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:58.731417 types-aiobotocore-medialive-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:18:27.000000 types-aiobotocore-medialive-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    37646 2023-03-11 12:26:58.723417 types-aiobotocore-medialive-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    36067 2023-03-11 12:18:27.000000 types-aiobotocore-medialive-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:58.731417 types-aiobotocore-medialive-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2138 2023-03-11 12:18:26.000000 types-aiobotocore-medialive-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:58.715417 types-aiobotocore-medialive-2.5.0.post1/types_aiobotocore_medialive/
--rw-r--r--   0 runner    (1001) docker     (123)     4506 2023-03-11 12:18:27.000000 types-aiobotocore-medialive-2.5.0.post1/types_aiobotocore_medialive/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4505 2023-03-11 12:18:27.000000 types-aiobotocore-medialive-2.5.0.post1/types_aiobotocore_medialive/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      951 2023-03-11 12:18:27.000000 types-aiobotocore-medialive-2.5.0.post1/types_aiobotocore_medialive/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    53844 2023-03-11 12:18:27.000000 types-aiobotocore-medialive-2.5.0.post1/types_aiobotocore_medialive/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    53755 2023-03-11 12:18:27.000000 types-aiobotocore-medialive-2.5.0.post1/types_aiobotocore_medialive/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    38880 2023-03-11 12:18:28.000000 types-aiobotocore-medialive-2.5.0.post1/types_aiobotocore_medialive/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    38878 2023-03-11 12:18:27.000000 types-aiobotocore-medialive-2.5.0.post1/types_aiobotocore_medialive/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    12779 2023-03-11 12:18:27.000000 types-aiobotocore-medialive-2.5.0.post1/types_aiobotocore_medialive/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    12766 2023-03-11 12:18:27.000000 types-aiobotocore-medialive-2.5.0.post1/types_aiobotocore_medialive/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:18:27.000000 types-aiobotocore-medialive-2.5.0.post1/types_aiobotocore_medialive/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)   146539 2023-03-11 12:18:30.000000 types-aiobotocore-medialive-2.5.0.post1/types_aiobotocore_medialive/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)   146392 2023-03-11 12:18:29.000000 types-aiobotocore-medialive-2.5.0.post1/types_aiobotocore_medialive/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:18:27.000000 types-aiobotocore-medialive-2.5.0.post1/types_aiobotocore_medialive/version.py
--rw-r--r--   0 runner    (1001) docker     (123)    11083 2023-03-11 12:18:27.000000 types-aiobotocore-medialive-2.5.0.post1/types_aiobotocore_medialive/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)    11072 2023-03-11 12:18:27.000000 types-aiobotocore-medialive-2.5.0.post1/types_aiobotocore_medialive/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:58.719417 types-aiobotocore-medialive-2.5.0.post1/types_aiobotocore_medialive.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    37646 2023-03-11 12:26:58.000000 types-aiobotocore-medialive-2.5.0.post1/types_aiobotocore_medialive.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      928 2023-03-11 12:26:58.000000 types-aiobotocore-medialive-2.5.0.post1/types_aiobotocore_medialive.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:58.000000 types-aiobotocore-medialive-2.5.0.post1/types_aiobotocore_medialive.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:58.000000 types-aiobotocore-medialive-2.5.0.post1/types_aiobotocore_medialive.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:58.000000 types-aiobotocore-medialive-2.5.0.post1/types_aiobotocore_medialive.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       28 2023-03-11 12:26:58.000000 types-aiobotocore-medialive-2.5.0.post1/types_aiobotocore_medialive.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:49.722175 types-aiobotocore-medialive-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:35:07.000000 types-aiobotocore-medialive-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    37675 2023-06-28 01:43:49.722175 types-aiobotocore-medialive-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    36102 2023-06-28 01:35:07.000000 types-aiobotocore-medialive-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:49.722175 types-aiobotocore-medialive-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2132 2023-06-28 01:35:07.000000 types-aiobotocore-medialive-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:49.722175 types-aiobotocore-medialive-2.5.1/types_aiobotocore_medialive/
+-rw-r--r--   0 runner    (1001) docker     (123)     4506 2023-06-28 01:35:07.000000 types-aiobotocore-medialive-2.5.1/types_aiobotocore_medialive/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4505 2023-06-28 01:35:07.000000 types-aiobotocore-medialive-2.5.1/types_aiobotocore_medialive/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      939 2023-06-28 01:35:07.000000 types-aiobotocore-medialive-2.5.1/types_aiobotocore_medialive/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    53844 2023-06-28 01:35:08.000000 types-aiobotocore-medialive-2.5.1/types_aiobotocore_medialive/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    53755 2023-06-28 01:35:08.000000 types-aiobotocore-medialive-2.5.1/types_aiobotocore_medialive/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    39348 2023-06-28 01:35:10.000000 types-aiobotocore-medialive-2.5.1/types_aiobotocore_medialive/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    39346 2023-06-28 01:35:10.000000 types-aiobotocore-medialive-2.5.1/types_aiobotocore_medialive/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    12679 2023-06-28 01:35:08.000000 types-aiobotocore-medialive-2.5.1/types_aiobotocore_medialive/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12667 2023-06-28 01:35:08.000000 types-aiobotocore-medialive-2.5.1/types_aiobotocore_medialive/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:35:07.000000 types-aiobotocore-medialive-2.5.1/types_aiobotocore_medialive/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)   147116 2023-06-28 01:35:13.000000 types-aiobotocore-medialive-2.5.1/types_aiobotocore_medialive/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)   146967 2023-06-28 01:35:11.000000 types-aiobotocore-medialive-2.5.1/types_aiobotocore_medialive/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:35:07.000000 types-aiobotocore-medialive-2.5.1/types_aiobotocore_medialive/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11083 2023-06-28 01:35:08.000000 types-aiobotocore-medialive-2.5.1/types_aiobotocore_medialive/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11072 2023-06-28 01:35:08.000000 types-aiobotocore-medialive-2.5.1/types_aiobotocore_medialive/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:49.722175 types-aiobotocore-medialive-2.5.1/types_aiobotocore_medialive.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    37675 2023-06-28 01:43:49.000000 types-aiobotocore-medialive-2.5.1/types_aiobotocore_medialive.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      928 2023-06-28 01:43:49.000000 types-aiobotocore-medialive-2.5.1/types_aiobotocore_medialive.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:49.000000 types-aiobotocore-medialive-2.5.1/types_aiobotocore_medialive.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:49.000000 types-aiobotocore-medialive-2.5.1/types_aiobotocore_medialive.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:49.000000 types-aiobotocore-medialive-2.5.1/types_aiobotocore_medialive.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       28 2023-06-28 01:43:49.000000 types-aiobotocore-medialive-2.5.1/types_aiobotocore_medialive.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-medialive-2.5.0.post1/LICENSE` & `types-aiobotocore-medialive-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-medialive-2.5.0.post1/PKG-INFO` & `types-aiobotocore-medialive-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-medialive
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MediaLive 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MediaLive 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-medialive"></a>
 
 # types-aiobotocore-medialive
 
 [![PyPI - types-aiobotocore-medialive](https://img.shields.io/pypi/v/types-aiobotocore-medialive.svg?color=blue)](https://pypi.org/project/types-aiobotocore-medialive)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-medialive.svg?color=blue)](https://pypi.org/project/types-aiobotocore-medialive)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-medialive?color=blue)](https://pypistats.org/packages/types-aiobotocore-medialive)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MediaLive 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive)
+[aiobotocore.MediaLive 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive)
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
 [types-aiobotocore-medialive docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/).
 
 See how it helps to find and fix potential bugs:
 
@@ -599,14 +599,15 @@
     MultiplexCreatedWaiterName,
     MultiplexDeletedWaiterName,
     MultiplexRunningWaiterName,
     MultiplexStateType,
     MultiplexStoppedWaiterName,
     NetworkInputServerValidationType,
     NielsenPcmToId3TaggingStateType,
+    NielsenWatermarkTimezonesType,
     NielsenWatermarksCbetStepasideType,
     NielsenWatermarksDistributionTypesType,
     OfferingDurationUnitsType,
     OfferingTypeType,
     PipelineIdType,
     PreferredChannelPipelineType,
     RebootInputDeviceForceType,
@@ -701,15 +702,14 @@
     AudioTrackTypeDef,
     EsamTypeDef,
     Scte35SpliceInsertTypeDef,
     Scte35TimeSignalAposTypeDef,
     BatchDeleteRequestRequestTypeDef,
     BatchFailedResultModelTypeDef,
     BatchSuccessfulResultModelTypeDef,
-    ResponseMetadataTypeDef,
     BatchScheduleActionDeleteRequestTypeDef,
     BatchStartRequestRequestTypeDef,
     BatchStopRequestRequestTypeDef,
     CancelInputDeviceTransferRequestRequestTypeDef,
     EbuTtDDestinationSettingsTypeDef,
     TtmlDestinationSettingsTypeDef,
     WebvttDestinationSettingsTypeDef,
@@ -752,28 +752,30 @@
     WaiterConfigTypeDef,
     DescribeChannelRequestRequestTypeDef,
     DescribeInputDeviceRequestRequestTypeDef,
     InputDeviceHdSettingsTypeDef,
     InputDeviceNetworkSettingsTypeDef,
     InputDeviceUhdSettingsTypeDef,
     DescribeInputDeviceThumbnailRequestRequestTypeDef,
+    DescribeInputDeviceThumbnailResponseTypeDef,
     DescribeInputRequestRequestTypeDef,
     InputSourceTypeDef,
     MediaConnectFlowTypeDef,
     DescribeInputSecurityGroupRequestRequestTypeDef,
     InputWhitelistRuleTypeDef,
     DescribeMultiplexProgramRequestRequestTypeDef,
     DescribeMultiplexRequestRequestTypeDef,
     DescribeOfferingRequestRequestTypeDef,
     DescribeReservationRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeScheduleRequestDescribeSchedulePaginateTypeDef,
     DescribeScheduleRequestRequestTypeDef,
     DvbNitSettingsTypeDef,
     DvbSdtSettingsTypeDef,
     DvbTdtSettingsTypeDef,
+    EmptyResponseMetadataTypeDef,
     FeatureActivationsTypeDef,
     NielsenConfigurationTypeDef,
     TimecodeConfigTypeDef,
     InputLossFailoverSettingsTypeDef,
     VideoBlackFailoverSettingsTypeDef,
     FecOutputSettingsTypeDef,
     FixedModeScheduleActionStartSettingsTypeDef,
@@ -794,26 +796,36 @@
     HlsInputSettingsTypeDef,
     HlsTimedMetadataScheduleActionSettingsTypeDef,
     StartTimecodeTypeDef,
     StopTimecodeTypeDef,
     InputDestinationVpcTypeDef,
     InputDeviceConfigurableSettingsTypeDef,
     InputDeviceRequestTypeDef,
+    ListChannelsRequestListChannelsPaginateTypeDef,
     ListChannelsRequestRequestTypeDef,
+    ListInputDeviceTransfersRequestListInputDeviceTransfersPaginateTypeDef,
     ListInputDeviceTransfersRequestRequestTypeDef,
     TransferringInputDeviceSummaryTypeDef,
+    ListInputDevicesRequestListInputDevicesPaginateTypeDef,
     ListInputDevicesRequestRequestTypeDef,
+    ListInputSecurityGroupsRequestListInputSecurityGroupsPaginateTypeDef,
     ListInputSecurityGroupsRequestRequestTypeDef,
+    ListInputsRequestListInputsPaginateTypeDef,
     ListInputsRequestRequestTypeDef,
+    ListMultiplexProgramsRequestListMultiplexProgramsPaginateTypeDef,
     ListMultiplexProgramsRequestRequestTypeDef,
     MultiplexProgramSummaryTypeDef,
+    ListMultiplexesRequestListMultiplexesPaginateTypeDef,
     ListMultiplexesRequestRequestTypeDef,
+    ListOfferingsRequestListOfferingsPaginateTypeDef,
     ListOfferingsRequestRequestTypeDef,
+    ListReservationsRequestListReservationsPaginateTypeDef,
     ListReservationsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     M3u8SettingsTypeDef,
     MaintenanceUpdateSettingsTypeDef,
     MediaPackageOutputDestinationSettingsTypeDef,
     MotionGraphicsActivateScheduleActionSettingsTypeDef,
     MotionGraphicsSettingsTypeDef,
     MsSmoothOutputSettingsTypeDef,
     MultiplexMediaConnectOutputDestinationSettingsTypeDef,
@@ -822,17 +834,19 @@
     MultiplexSettingsSummaryTypeDef,
     MultiplexStatmuxVideoSettingsTypeDef,
     NielsenCBETTypeDef,
     NielsenNaesIiNwTypeDef,
     OutputDestinationSettingsTypeDef,
     RtmpGroupSettingsTypeDef,
     UdpGroupSettingsTypeDef,
+    PaginatorConfigTypeDef,
     PipelinePauseStateSettingsTypeDef,
     RebootInputDeviceRequestRequestTypeDef,
     RejectInputDeviceTransferRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     Scte35InputScheduleActionSettingsTypeDef,
     Scte35ReturnToNetworkScheduleActionSettingsTypeDef,
     Scte35SpliceInsertScheduleActionSettingsTypeDef,
     StaticImageDeactivateScheduleActionSettingsTypeDef,
     Scte35DeliveryRestrictionsTypeDef,
     StartChannelRequestRequestTypeDef,
     StartInputDeviceMaintenanceWindowRequestRequestTypeDef,
@@ -858,17 +872,14 @@
     StaticImageActivateScheduleActionSettingsTypeDef,
     StaticKeySettingsTypeDef,
     AudioTrackSelectionTypeDef,
     AvailSettingsTypeDef,
     BatchDeleteResponseTypeDef,
     BatchStartResponseTypeDef,
     BatchStopResponseTypeDef,
-    DescribeInputDeviceThumbnailResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ListTagsForResourceResponseTypeDef,
     TeletextSourceSettingsTypeDef,
     CreateInputRequestRequestTypeDef,
     CreateInputSecurityGroupRequestRequestTypeDef,
     UpdateInputSecurityGroupRequestRequestTypeDef,
     CreateMultiplexRequestRequestTypeDef,
     UpdateMultiplexRequestRequestTypeDef,
     PurchaseOfferingRequestRequestTypeDef,
@@ -890,24 +901,14 @@
     DescribeMultiplexRequestMultiplexRunningWaitTypeDef,
     DescribeMultiplexRequestMultiplexStoppedWaitTypeDef,
     DescribeInputDeviceResponseTypeDef,
     InputDeviceSummaryTypeDef,
     UpdateInputDeviceResponseTypeDef,
     DescribeInputSecurityGroupResponseTypeDef,
     InputSecurityGroupTypeDef,
-    DescribeScheduleRequestDescribeSchedulePaginateTypeDef,
-    ListChannelsRequestListChannelsPaginateTypeDef,
-    ListInputDeviceTransfersRequestListInputDeviceTransfersPaginateTypeDef,
-    ListInputDevicesRequestListInputDevicesPaginateTypeDef,
-    ListInputSecurityGroupsRequestListInputSecurityGroupsPaginateTypeDef,
-    ListInputsRequestListInputsPaginateTypeDef,
-    ListMultiplexProgramsRequestListMultiplexProgramsPaginateTypeDef,
-    ListMultiplexesRequestListMultiplexesPaginateTypeDef,
-    ListOfferingsRequestListOfferingsPaginateTypeDef,
-    ListReservationsRequestListReservationsPaginateTypeDef,
     M2tsSettingsTypeDef,
     FailoverConditionSettingsTypeDef,
     ScheduleActionStartSettingsTypeDef,
     FrameCaptureCdnSettingsTypeDef,
     FrameCaptureSettingsTypeDef,
     H264FilterSettingsTypeDef,
     H265FilterSettingsTypeDef,
@@ -1034,43 +1035,43 @@
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

### Comparing `types-aiobotocore-medialive-2.5.0.post1/README.md` & `types-aiobotocore-medialive-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-medialive"></a>
 
 # types-aiobotocore-medialive
 
 [![PyPI - types-aiobotocore-medialive](https://img.shields.io/pypi/v/types-aiobotocore-medialive.svg?color=blue)](https://pypi.org/project/types-aiobotocore-medialive)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-medialive.svg?color=blue)](https://pypi.org/project/types-aiobotocore-medialive)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-medialive?color=blue)](https://pypistats.org/packages/types-aiobotocore-medialive)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MediaLive 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive)
+[aiobotocore.MediaLive 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive)
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
 [types-aiobotocore-medialive docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/).
 
 See how it helps to find and fix potential bugs:
 
@@ -566,14 +566,15 @@
     MultiplexCreatedWaiterName,
     MultiplexDeletedWaiterName,
     MultiplexRunningWaiterName,
     MultiplexStateType,
     MultiplexStoppedWaiterName,
     NetworkInputServerValidationType,
     NielsenPcmToId3TaggingStateType,
+    NielsenWatermarkTimezonesType,
     NielsenWatermarksCbetStepasideType,
     NielsenWatermarksDistributionTypesType,
     OfferingDurationUnitsType,
     OfferingTypeType,
     PipelineIdType,
     PreferredChannelPipelineType,
     RebootInputDeviceForceType,
@@ -668,15 +669,14 @@
     AudioTrackTypeDef,
     EsamTypeDef,
     Scte35SpliceInsertTypeDef,
     Scte35TimeSignalAposTypeDef,
     BatchDeleteRequestRequestTypeDef,
     BatchFailedResultModelTypeDef,
     BatchSuccessfulResultModelTypeDef,
-    ResponseMetadataTypeDef,
     BatchScheduleActionDeleteRequestTypeDef,
     BatchStartRequestRequestTypeDef,
     BatchStopRequestRequestTypeDef,
     CancelInputDeviceTransferRequestRequestTypeDef,
     EbuTtDDestinationSettingsTypeDef,
     TtmlDestinationSettingsTypeDef,
     WebvttDestinationSettingsTypeDef,
@@ -719,28 +719,30 @@
     WaiterConfigTypeDef,
     DescribeChannelRequestRequestTypeDef,
     DescribeInputDeviceRequestRequestTypeDef,
     InputDeviceHdSettingsTypeDef,
     InputDeviceNetworkSettingsTypeDef,
     InputDeviceUhdSettingsTypeDef,
     DescribeInputDeviceThumbnailRequestRequestTypeDef,
+    DescribeInputDeviceThumbnailResponseTypeDef,
     DescribeInputRequestRequestTypeDef,
     InputSourceTypeDef,
     MediaConnectFlowTypeDef,
     DescribeInputSecurityGroupRequestRequestTypeDef,
     InputWhitelistRuleTypeDef,
     DescribeMultiplexProgramRequestRequestTypeDef,
     DescribeMultiplexRequestRequestTypeDef,
     DescribeOfferingRequestRequestTypeDef,
     DescribeReservationRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeScheduleRequestDescribeSchedulePaginateTypeDef,
     DescribeScheduleRequestRequestTypeDef,
     DvbNitSettingsTypeDef,
     DvbSdtSettingsTypeDef,
     DvbTdtSettingsTypeDef,
+    EmptyResponseMetadataTypeDef,
     FeatureActivationsTypeDef,
     NielsenConfigurationTypeDef,
     TimecodeConfigTypeDef,
     InputLossFailoverSettingsTypeDef,
     VideoBlackFailoverSettingsTypeDef,
     FecOutputSettingsTypeDef,
     FixedModeScheduleActionStartSettingsTypeDef,
@@ -761,26 +763,36 @@
     HlsInputSettingsTypeDef,
     HlsTimedMetadataScheduleActionSettingsTypeDef,
     StartTimecodeTypeDef,
     StopTimecodeTypeDef,
     InputDestinationVpcTypeDef,
     InputDeviceConfigurableSettingsTypeDef,
     InputDeviceRequestTypeDef,
+    ListChannelsRequestListChannelsPaginateTypeDef,
     ListChannelsRequestRequestTypeDef,
+    ListInputDeviceTransfersRequestListInputDeviceTransfersPaginateTypeDef,
     ListInputDeviceTransfersRequestRequestTypeDef,
     TransferringInputDeviceSummaryTypeDef,
+    ListInputDevicesRequestListInputDevicesPaginateTypeDef,
     ListInputDevicesRequestRequestTypeDef,
+    ListInputSecurityGroupsRequestListInputSecurityGroupsPaginateTypeDef,
     ListInputSecurityGroupsRequestRequestTypeDef,
+    ListInputsRequestListInputsPaginateTypeDef,
     ListInputsRequestRequestTypeDef,
+    ListMultiplexProgramsRequestListMultiplexProgramsPaginateTypeDef,
     ListMultiplexProgramsRequestRequestTypeDef,
     MultiplexProgramSummaryTypeDef,
+    ListMultiplexesRequestListMultiplexesPaginateTypeDef,
     ListMultiplexesRequestRequestTypeDef,
+    ListOfferingsRequestListOfferingsPaginateTypeDef,
     ListOfferingsRequestRequestTypeDef,
+    ListReservationsRequestListReservationsPaginateTypeDef,
     ListReservationsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     M3u8SettingsTypeDef,
     MaintenanceUpdateSettingsTypeDef,
     MediaPackageOutputDestinationSettingsTypeDef,
     MotionGraphicsActivateScheduleActionSettingsTypeDef,
     MotionGraphicsSettingsTypeDef,
     MsSmoothOutputSettingsTypeDef,
     MultiplexMediaConnectOutputDestinationSettingsTypeDef,
@@ -789,17 +801,19 @@
     MultiplexSettingsSummaryTypeDef,
     MultiplexStatmuxVideoSettingsTypeDef,
     NielsenCBETTypeDef,
     NielsenNaesIiNwTypeDef,
     OutputDestinationSettingsTypeDef,
     RtmpGroupSettingsTypeDef,
     UdpGroupSettingsTypeDef,
+    PaginatorConfigTypeDef,
     PipelinePauseStateSettingsTypeDef,
     RebootInputDeviceRequestRequestTypeDef,
     RejectInputDeviceTransferRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     Scte35InputScheduleActionSettingsTypeDef,
     Scte35ReturnToNetworkScheduleActionSettingsTypeDef,
     Scte35SpliceInsertScheduleActionSettingsTypeDef,
     StaticImageDeactivateScheduleActionSettingsTypeDef,
     Scte35DeliveryRestrictionsTypeDef,
     StartChannelRequestRequestTypeDef,
     StartInputDeviceMaintenanceWindowRequestRequestTypeDef,
@@ -825,17 +839,14 @@
     StaticImageActivateScheduleActionSettingsTypeDef,
     StaticKeySettingsTypeDef,
     AudioTrackSelectionTypeDef,
     AvailSettingsTypeDef,
     BatchDeleteResponseTypeDef,
     BatchStartResponseTypeDef,
     BatchStopResponseTypeDef,
-    DescribeInputDeviceThumbnailResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ListTagsForResourceResponseTypeDef,
     TeletextSourceSettingsTypeDef,
     CreateInputRequestRequestTypeDef,
     CreateInputSecurityGroupRequestRequestTypeDef,
     UpdateInputSecurityGroupRequestRequestTypeDef,
     CreateMultiplexRequestRequestTypeDef,
     UpdateMultiplexRequestRequestTypeDef,
     PurchaseOfferingRequestRequestTypeDef,
@@ -857,24 +868,14 @@
     DescribeMultiplexRequestMultiplexRunningWaitTypeDef,
     DescribeMultiplexRequestMultiplexStoppedWaitTypeDef,
     DescribeInputDeviceResponseTypeDef,
     InputDeviceSummaryTypeDef,
     UpdateInputDeviceResponseTypeDef,
     DescribeInputSecurityGroupResponseTypeDef,
     InputSecurityGroupTypeDef,
-    DescribeScheduleRequestDescribeSchedulePaginateTypeDef,
-    ListChannelsRequestListChannelsPaginateTypeDef,
-    ListInputDeviceTransfersRequestListInputDeviceTransfersPaginateTypeDef,
-    ListInputDevicesRequestListInputDevicesPaginateTypeDef,
-    ListInputSecurityGroupsRequestListInputSecurityGroupsPaginateTypeDef,
-    ListInputsRequestListInputsPaginateTypeDef,
-    ListMultiplexProgramsRequestListMultiplexProgramsPaginateTypeDef,
-    ListMultiplexesRequestListMultiplexesPaginateTypeDef,
-    ListOfferingsRequestListOfferingsPaginateTypeDef,
-    ListReservationsRequestListReservationsPaginateTypeDef,
     M2tsSettingsTypeDef,
     FailoverConditionSettingsTypeDef,
     ScheduleActionStartSettingsTypeDef,
     FrameCaptureCdnSettingsTypeDef,
     FrameCaptureSettingsTypeDef,
     H264FilterSettingsTypeDef,
     H265FilterSettingsTypeDef,
@@ -1001,43 +1002,43 @@
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

### Comparing `types-aiobotocore-medialive-2.5.0.post1/setup.py` & `types-aiobotocore-medialive-2.5.1/setup.py`

 * *Files 9% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-medialive.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-medialive",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_medialive"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.MediaLive 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.MediaLive 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/"
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

### Comparing `types-aiobotocore-medialive-2.5.0.post1/types_aiobotocore_medialive/__init__.py` & `types-aiobotocore-medialive-2.5.1/types_aiobotocore_medialive/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-medialive-2.5.0.post1/types_aiobotocore_medialive/__init__.pyi` & `types-aiobotocore-medialive-2.5.1/types_aiobotocore_medialive/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-medialive-2.5.0.post1/types_aiobotocore_medialive/__main__.py` & `types-aiobotocore-medialive-2.5.1/types_aiobotocore_medialive/__main__.py`

 * *Files 5% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.MediaLive 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.MediaLive 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive\nOther"
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

### Comparing `types-aiobotocore-medialive-2.5.0.post1/types_aiobotocore_medialive/client.py` & `types-aiobotocore-medialive-2.5.1/types_aiobotocore_medialive/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-medialive-2.5.0.post1/types_aiobotocore_medialive/client.pyi` & `types-aiobotocore-medialive-2.5.1/types_aiobotocore_medialive/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-medialive-2.5.0.post1/types_aiobotocore_medialive/literals.py` & `types-aiobotocore-medialive-2.5.1/types_aiobotocore_medialive/literals.pyi`

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
     "AacCodingModeType",
     "AacInputTypeType",
     "AacProfileType",
     "AacRateControlModeType",
     "AacRawFormatType",
     "AacSpecType",
@@ -246,14 +245,15 @@
     "MultiplexCreatedWaiterName",
     "MultiplexDeletedWaiterName",
     "MultiplexRunningWaiterName",
     "MultiplexStateType",
     "MultiplexStoppedWaiterName",
     "NetworkInputServerValidationType",
     "NielsenPcmToId3TaggingStateType",
+    "NielsenWatermarkTimezonesType",
     "NielsenWatermarksCbetStepasideType",
     "NielsenWatermarksDistributionTypesType",
     "OfferingDurationUnitsType",
     "OfferingTypeType",
     "PipelineIdType",
     "PreferredChannelPipelineType",
     "RebootInputDeviceForceType",
@@ -309,15 +309,14 @@
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "WaiterName",
     "RegionName",
 )
 
-
 AacCodingModeType = Literal[
     "AD_RECEIVER_MIX", "CODING_MODE_1_0", "CODING_MODE_1_1", "CODING_MODE_2_0", "CODING_MODE_5_1"
 ]
 AacInputTypeType = Literal["BROADCASTER_MIXED_AD", "NORMAL"]
 AacProfileType = Literal["HEV1", "HEV2", "LC"]
 AacRateControlModeType = Literal["CBR", "VBR"]
 AacRawFormatType = Literal["LATM_LOAS", "NONE"]
@@ -668,14 +667,26 @@
     "STOPPING",
 ]
 MultiplexStoppedWaiterName = Literal["multiplex_stopped"]
 NetworkInputServerValidationType = Literal[
     "CHECK_CRYPTOGRAPHY_AND_VALIDATE_NAME", "CHECK_CRYPTOGRAPHY_ONLY"
 ]
 NielsenPcmToId3TaggingStateType = Literal["DISABLED", "ENABLED"]
+NielsenWatermarkTimezonesType = Literal[
+    "AMERICA_PUERTO_RICO",
+    "US_ALASKA",
+    "US_ARIZONA",
+    "US_CENTRAL",
+    "US_EASTERN",
+    "US_HAWAII",
+    "US_MOUNTAIN",
+    "US_PACIFIC",
+    "US_SAMOA",
+    "UTC",
+]
 NielsenWatermarksCbetStepasideType = Literal["DISABLED", "ENABLED"]
 NielsenWatermarksDistributionTypesType = Literal["FINAL_DISTRIBUTOR", "PROGRAM_CONTENT"]
 OfferingDurationUnitsType = Literal["MONTHS"]
 OfferingTypeType = Literal["NO_UPFRONT"]
 PipelineIdType = Literal["PIPELINE_0", "PIPELINE_1"]
 PreferredChannelPipelineType = Literal["CURRENTLY_ACTIVE", "PIPELINE_0", "PIPELINE_1"]
 RebootInputDeviceForceType = Literal["NO", "YES"]
@@ -822,14 +833,15 @@
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
@@ -908,14 +920,15 @@
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
@@ -926,14 +939,15 @@
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
@@ -969,14 +983,15 @@
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
@@ -995,16 +1010,19 @@
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
@@ -1088,15 +1106,17 @@
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

### Comparing `types-aiobotocore-medialive-2.5.0.post1/types_aiobotocore_medialive/literals.pyi` & `types-aiobotocore-medialive-2.5.1/types_aiobotocore_medialive/literals.py`

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
     "AacCodingModeType",
     "AacInputTypeType",
     "AacProfileType",
     "AacRateControlModeType",
     "AacRawFormatType",
     "AacSpecType",
@@ -245,14 +246,15 @@
     "MultiplexCreatedWaiterName",
     "MultiplexDeletedWaiterName",
     "MultiplexRunningWaiterName",
     "MultiplexStateType",
     "MultiplexStoppedWaiterName",
     "NetworkInputServerValidationType",
     "NielsenPcmToId3TaggingStateType",
+    "NielsenWatermarkTimezonesType",
     "NielsenWatermarksCbetStepasideType",
     "NielsenWatermarksDistributionTypesType",
     "OfferingDurationUnitsType",
     "OfferingTypeType",
     "PipelineIdType",
     "PreferredChannelPipelineType",
     "RebootInputDeviceForceType",
@@ -308,14 +310,15 @@
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "WaiterName",
     "RegionName",
 )
 
+
 AacCodingModeType = Literal[
     "AD_RECEIVER_MIX", "CODING_MODE_1_0", "CODING_MODE_1_1", "CODING_MODE_2_0", "CODING_MODE_5_1"
 ]
 AacInputTypeType = Literal["BROADCASTER_MIXED_AD", "NORMAL"]
 AacProfileType = Literal["HEV1", "HEV2", "LC"]
 AacRateControlModeType = Literal["CBR", "VBR"]
 AacRawFormatType = Literal["LATM_LOAS", "NONE"]
@@ -666,14 +669,26 @@
     "STOPPING",
 ]
 MultiplexStoppedWaiterName = Literal["multiplex_stopped"]
 NetworkInputServerValidationType = Literal[
     "CHECK_CRYPTOGRAPHY_AND_VALIDATE_NAME", "CHECK_CRYPTOGRAPHY_ONLY"
 ]
 NielsenPcmToId3TaggingStateType = Literal["DISABLED", "ENABLED"]
+NielsenWatermarkTimezonesType = Literal[
+    "AMERICA_PUERTO_RICO",
+    "US_ALASKA",
+    "US_ARIZONA",
+    "US_CENTRAL",
+    "US_EASTERN",
+    "US_HAWAII",
+    "US_MOUNTAIN",
+    "US_PACIFIC",
+    "US_SAMOA",
+    "UTC",
+]
 NielsenWatermarksCbetStepasideType = Literal["DISABLED", "ENABLED"]
 NielsenWatermarksDistributionTypesType = Literal["FINAL_DISTRIBUTOR", "PROGRAM_CONTENT"]
 OfferingDurationUnitsType = Literal["MONTHS"]
 OfferingTypeType = Literal["NO_UPFRONT"]
 PipelineIdType = Literal["PIPELINE_0", "PIPELINE_1"]
 PreferredChannelPipelineType = Literal["CURRENTLY_ACTIVE", "PIPELINE_0", "PIPELINE_1"]
 RebootInputDeviceForceType = Literal["NO", "YES"]
@@ -820,14 +835,15 @@
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
@@ -906,14 +922,15 @@
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
@@ -924,14 +941,15 @@
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
@@ -967,14 +985,15 @@
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
@@ -993,16 +1012,19 @@
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
@@ -1086,15 +1108,17 @@
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

### Comparing `types-aiobotocore-medialive-2.5.0.post1/types_aiobotocore_medialive/paginator.py` & `types-aiobotocore-medialive-2.5.1/types_aiobotocore_medialive/paginator.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -34,16 +34,15 @@
         list_inputs_paginator: ListInputsPaginator = client.get_paginator("list_inputs")
         list_multiplex_programs_paginator: ListMultiplexProgramsPaginator = client.get_paginator("list_multiplex_programs")
         list_multiplexes_paginator: ListMultiplexesPaginator = client.get_paginator("list_multiplexes")
         list_offerings_paginator: ListOfferingsPaginator = client.get_paginator("list_offerings")
         list_reservations_paginator: ListReservationsPaginator = client.get_paginator("list_reservations")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DescribeScheduleResponseTypeDef,
     ListChannelsResponseTypeDef,
@@ -54,164 +53,147 @@
     ListMultiplexesResponseTypeDef,
     ListMultiplexProgramsResponseTypeDef,
     ListOfferingsResponseTypeDef,
     ListReservationsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "DescribeSchedulePaginator",
     "ListChannelsPaginator",
     "ListInputDeviceTransfersPaginator",
     "ListInputDevicesPaginator",
     "ListInputSecurityGroupsPaginator",
     "ListInputsPaginator",
     "ListMultiplexProgramsPaginator",
     "ListMultiplexesPaginator",
     "ListOfferingsPaginator",
     "ListReservationsPaginator",
 )
 
-
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
-
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
-
 class DescribeSchedulePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive.Paginator.DescribeSchedule)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/paginators/#describeschedulepaginator)
     """
 
     def paginate(
-        self, *, ChannelId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ChannelId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeScheduleResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive.Paginator.DescribeSchedule.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/paginators/#describeschedulepaginator)
         """
 
-
 class ListChannelsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive.Paginator.ListChannels)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/paginators/#listchannelspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListChannelsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive.Paginator.ListChannels.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/paginators/#listchannelspaginator)
         """
 
-
 class ListInputDeviceTransfersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive.Paginator.ListInputDeviceTransfers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/paginators/#listinputdevicetransferspaginator)
     """
 
     def paginate(
-        self, *, TransferType: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, TransferType: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListInputDeviceTransfersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive.Paginator.ListInputDeviceTransfers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/paginators/#listinputdevicetransferspaginator)
         """
 
-
 class ListInputDevicesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive.Paginator.ListInputDevices)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/paginators/#listinputdevicespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListInputDevicesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive.Paginator.ListInputDevices.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/paginators/#listinputdevicespaginator)
         """
 
-
 class ListInputSecurityGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive.Paginator.ListInputSecurityGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/paginators/#listinputsecuritygroupspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListInputSecurityGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive.Paginator.ListInputSecurityGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/paginators/#listinputsecuritygroupspaginator)
         """
 
-
 class ListInputsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive.Paginator.ListInputs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/paginators/#listinputspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListInputsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive.Paginator.ListInputs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/paginators/#listinputspaginator)
         """
 
-
 class ListMultiplexProgramsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive.Paginator.ListMultiplexPrograms)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/paginators/#listmultiplexprogramspaginator)
     """
 
     def paginate(
-        self, *, MultiplexId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, MultiplexId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMultiplexProgramsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive.Paginator.ListMultiplexPrograms.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/paginators/#listmultiplexprogramspaginator)
         """
 
-
 class ListMultiplexesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive.Paginator.ListMultiplexes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/paginators/#listmultiplexespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMultiplexesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive.Paginator.ListMultiplexes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/paginators/#listmultiplexespaginator)
         """
 
-
 class ListOfferingsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive.Paginator.ListOfferings)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/paginators/#listofferingspaginator)
     """
 
     def paginate(
@@ -223,22 +205,21 @@
         Duration: str = ...,
         MaximumBitrate: str = ...,
         MaximumFramerate: str = ...,
         Resolution: str = ...,
         ResourceType: str = ...,
         SpecialFeature: str = ...,
         VideoQuality: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOfferingsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive.Paginator.ListOfferings.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/paginators/#listofferingspaginator)
         """
 
-
 class ListReservationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive.Paginator.ListReservations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/paginators/#listreservationspaginator)
     """
 
     def paginate(
@@ -248,13 +229,13 @@
         Codec: str = ...,
         MaximumBitrate: str = ...,
         MaximumFramerate: str = ...,
         Resolution: str = ...,
         ResourceType: str = ...,
         SpecialFeature: str = ...,
         VideoQuality: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListReservationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive.Paginator.ListReservations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/paginators/#listreservationspaginator)
         """
```

### Comparing `types-aiobotocore-medialive-2.5.0.post1/types_aiobotocore_medialive/paginator.pyi` & `types-aiobotocore-medialive-2.5.1/types_aiobotocore_medialive/paginator.py`

 * *Files 8% similar despite different names*

```diff
@@ -34,16 +34,15 @@
         list_inputs_paginator: ListInputsPaginator = client.get_paginator("list_inputs")
         list_multiplex_programs_paginator: ListMultiplexProgramsPaginator = client.get_paginator("list_multiplex_programs")
         list_multiplexes_paginator: ListMultiplexesPaginator = client.get_paginator("list_multiplexes")
         list_offerings_paginator: ListOfferingsPaginator = client.get_paginator("list_offerings")
         list_reservations_paginator: ListReservationsPaginator = client.get_paginator("list_reservations")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DescribeScheduleResponseTypeDef,
     ListChannelsResponseTypeDef,
@@ -54,152 +53,158 @@
     ListMultiplexesResponseTypeDef,
     ListMultiplexProgramsResponseTypeDef,
     ListOfferingsResponseTypeDef,
     ListReservationsResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "DescribeSchedulePaginator",
     "ListChannelsPaginator",
     "ListInputDeviceTransfersPaginator",
     "ListInputDevicesPaginator",
     "ListInputSecurityGroupsPaginator",
     "ListInputsPaginator",
     "ListMultiplexProgramsPaginator",
     "ListMultiplexesPaginator",
     "ListOfferingsPaginator",
     "ListReservationsPaginator",
 )
 
+
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
+
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
+
 class DescribeSchedulePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive.Paginator.DescribeSchedule)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/paginators/#describeschedulepaginator)
     """
 
     def paginate(
-        self, *, ChannelId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ChannelId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeScheduleResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive.Paginator.DescribeSchedule.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/paginators/#describeschedulepaginator)
         """
 
+
 class ListChannelsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive.Paginator.ListChannels)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/paginators/#listchannelspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListChannelsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive.Paginator.ListChannels.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/paginators/#listchannelspaginator)
         """
 
+
 class ListInputDeviceTransfersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive.Paginator.ListInputDeviceTransfers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/paginators/#listinputdevicetransferspaginator)
     """
 
     def paginate(
-        self, *, TransferType: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, TransferType: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListInputDeviceTransfersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive.Paginator.ListInputDeviceTransfers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/paginators/#listinputdevicetransferspaginator)
         """
 
+
 class ListInputDevicesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive.Paginator.ListInputDevices)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/paginators/#listinputdevicespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListInputDevicesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive.Paginator.ListInputDevices.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/paginators/#listinputdevicespaginator)
         """
 
+
 class ListInputSecurityGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive.Paginator.ListInputSecurityGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/paginators/#listinputsecuritygroupspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListInputSecurityGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive.Paginator.ListInputSecurityGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/paginators/#listinputsecuritygroupspaginator)
         """
 
+
 class ListInputsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive.Paginator.ListInputs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/paginators/#listinputspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListInputsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive.Paginator.ListInputs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/paginators/#listinputspaginator)
         """
 
+
 class ListMultiplexProgramsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive.Paginator.ListMultiplexPrograms)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/paginators/#listmultiplexprogramspaginator)
     """
 
     def paginate(
-        self, *, MultiplexId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, MultiplexId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMultiplexProgramsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive.Paginator.ListMultiplexPrograms.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/paginators/#listmultiplexprogramspaginator)
         """
 
+
 class ListMultiplexesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive.Paginator.ListMultiplexes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/paginators/#listmultiplexespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListMultiplexesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive.Paginator.ListMultiplexes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/paginators/#listmultiplexespaginator)
         """
 
+
 class ListOfferingsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive.Paginator.ListOfferings)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/paginators/#listofferingspaginator)
     """
 
     def paginate(
@@ -211,21 +216,22 @@
         Duration: str = ...,
         MaximumBitrate: str = ...,
         MaximumFramerate: str = ...,
         Resolution: str = ...,
         ResourceType: str = ...,
         SpecialFeature: str = ...,
         VideoQuality: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOfferingsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive.Paginator.ListOfferings.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/paginators/#listofferingspaginator)
         """
 
+
 class ListReservationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive.Paginator.ListReservations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/paginators/#listreservationspaginator)
     """
 
     def paginate(
@@ -235,13 +241,13 @@
         Codec: str = ...,
         MaximumBitrate: str = ...,
         MaximumFramerate: str = ...,
         Resolution: str = ...,
         ResourceType: str = ...,
         SpecialFeature: str = ...,
         VideoQuality: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListReservationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive.Paginator.ListReservations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/paginators/#listreservationspaginator)
         """
```

### Comparing `types-aiobotocore-medialive-2.5.0.post1/types_aiobotocore_medialive/type_defs.py` & `types-aiobotocore-medialive-2.5.1/types_aiobotocore_medialive/type_defs.py`

 * *Files 0% similar despite different names*

```diff
@@ -221,14 +221,15 @@
     Mpeg2TimecodeInsertionBehaviorType,
     MsSmoothH265PackagingTypeType,
     MultiplexStateType,
     NetworkInputServerValidationType,
     NielsenPcmToId3TaggingStateType,
     NielsenWatermarksCbetStepasideType,
     NielsenWatermarksDistributionTypesType,
+    NielsenWatermarkTimezonesType,
     PipelineIdType,
     PreferredChannelPipelineType,
     RebootInputDeviceForceType,
     ReservationAutomaticRenewalType,
     ReservationCodecType,
     ReservationMaximumBitrateType,
     ReservationMaximumFramerateType,
@@ -309,15 +310,14 @@
     "AudioTrackTypeDef",
     "EsamTypeDef",
     "Scte35SpliceInsertTypeDef",
     "Scte35TimeSignalAposTypeDef",
     "BatchDeleteRequestRequestTypeDef",
     "BatchFailedResultModelTypeDef",
     "BatchSuccessfulResultModelTypeDef",
-    "ResponseMetadataTypeDef",
     "BatchScheduleActionDeleteRequestTypeDef",
     "BatchStartRequestRequestTypeDef",
     "BatchStopRequestRequestTypeDef",
     "CancelInputDeviceTransferRequestRequestTypeDef",
     "EbuTtDDestinationSettingsTypeDef",
     "TtmlDestinationSettingsTypeDef",
     "WebvttDestinationSettingsTypeDef",
@@ -360,28 +360,30 @@
     "WaiterConfigTypeDef",
     "DescribeChannelRequestRequestTypeDef",
     "DescribeInputDeviceRequestRequestTypeDef",
     "InputDeviceHdSettingsTypeDef",
     "InputDeviceNetworkSettingsTypeDef",
     "InputDeviceUhdSettingsTypeDef",
     "DescribeInputDeviceThumbnailRequestRequestTypeDef",
+    "DescribeInputDeviceThumbnailResponseTypeDef",
     "DescribeInputRequestRequestTypeDef",
     "InputSourceTypeDef",
     "MediaConnectFlowTypeDef",
     "DescribeInputSecurityGroupRequestRequestTypeDef",
     "InputWhitelistRuleTypeDef",
     "DescribeMultiplexProgramRequestRequestTypeDef",
     "DescribeMultiplexRequestRequestTypeDef",
     "DescribeOfferingRequestRequestTypeDef",
     "DescribeReservationRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeScheduleRequestDescribeSchedulePaginateTypeDef",
     "DescribeScheduleRequestRequestTypeDef",
     "DvbNitSettingsTypeDef",
     "DvbSdtSettingsTypeDef",
     "DvbTdtSettingsTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "FeatureActivationsTypeDef",
     "NielsenConfigurationTypeDef",
     "TimecodeConfigTypeDef",
     "InputLossFailoverSettingsTypeDef",
     "VideoBlackFailoverSettingsTypeDef",
     "FecOutputSettingsTypeDef",
     "FixedModeScheduleActionStartSettingsTypeDef",
@@ -402,26 +404,36 @@
     "HlsInputSettingsTypeDef",
     "HlsTimedMetadataScheduleActionSettingsTypeDef",
     "StartTimecodeTypeDef",
     "StopTimecodeTypeDef",
     "InputDestinationVpcTypeDef",
     "InputDeviceConfigurableSettingsTypeDef",
     "InputDeviceRequestTypeDef",
+    "ListChannelsRequestListChannelsPaginateTypeDef",
     "ListChannelsRequestRequestTypeDef",
+    "ListInputDeviceTransfersRequestListInputDeviceTransfersPaginateTypeDef",
     "ListInputDeviceTransfersRequestRequestTypeDef",
     "TransferringInputDeviceSummaryTypeDef",
+    "ListInputDevicesRequestListInputDevicesPaginateTypeDef",
     "ListInputDevicesRequestRequestTypeDef",
+    "ListInputSecurityGroupsRequestListInputSecurityGroupsPaginateTypeDef",
     "ListInputSecurityGroupsRequestRequestTypeDef",
+    "ListInputsRequestListInputsPaginateTypeDef",
     "ListInputsRequestRequestTypeDef",
+    "ListMultiplexProgramsRequestListMultiplexProgramsPaginateTypeDef",
     "ListMultiplexProgramsRequestRequestTypeDef",
     "MultiplexProgramSummaryTypeDef",
+    "ListMultiplexesRequestListMultiplexesPaginateTypeDef",
     "ListMultiplexesRequestRequestTypeDef",
+    "ListOfferingsRequestListOfferingsPaginateTypeDef",
     "ListOfferingsRequestRequestTypeDef",
+    "ListReservationsRequestListReservationsPaginateTypeDef",
     "ListReservationsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "M3u8SettingsTypeDef",
     "MaintenanceUpdateSettingsTypeDef",
     "MediaPackageOutputDestinationSettingsTypeDef",
     "MotionGraphicsActivateScheduleActionSettingsTypeDef",
     "MotionGraphicsSettingsTypeDef",
     "MsSmoothOutputSettingsTypeDef",
     "MultiplexMediaConnectOutputDestinationSettingsTypeDef",
@@ -430,17 +442,19 @@
     "MultiplexSettingsSummaryTypeDef",
     "MultiplexStatmuxVideoSettingsTypeDef",
     "NielsenCBETTypeDef",
     "NielsenNaesIiNwTypeDef",
     "OutputDestinationSettingsTypeDef",
     "RtmpGroupSettingsTypeDef",
     "UdpGroupSettingsTypeDef",
+    "PaginatorConfigTypeDef",
     "PipelinePauseStateSettingsTypeDef",
     "RebootInputDeviceRequestRequestTypeDef",
     "RejectInputDeviceTransferRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "Scte35InputScheduleActionSettingsTypeDef",
     "Scte35ReturnToNetworkScheduleActionSettingsTypeDef",
     "Scte35SpliceInsertScheduleActionSettingsTypeDef",
     "StaticImageDeactivateScheduleActionSettingsTypeDef",
     "Scte35DeliveryRestrictionsTypeDef",
     "StartChannelRequestRequestTypeDef",
     "StartInputDeviceMaintenanceWindowRequestRequestTypeDef",
@@ -466,17 +480,14 @@
     "StaticImageActivateScheduleActionSettingsTypeDef",
     "StaticKeySettingsTypeDef",
     "AudioTrackSelectionTypeDef",
     "AvailSettingsTypeDef",
     "BatchDeleteResponseTypeDef",
     "BatchStartResponseTypeDef",
     "BatchStopResponseTypeDef",
-    "DescribeInputDeviceThumbnailResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "TeletextSourceSettingsTypeDef",
     "CreateInputRequestRequestTypeDef",
     "CreateInputSecurityGroupRequestRequestTypeDef",
     "UpdateInputSecurityGroupRequestRequestTypeDef",
     "CreateMultiplexRequestRequestTypeDef",
     "UpdateMultiplexRequestRequestTypeDef",
     "PurchaseOfferingRequestRequestTypeDef",
@@ -498,24 +509,14 @@
     "DescribeMultiplexRequestMultiplexRunningWaitTypeDef",
     "DescribeMultiplexRequestMultiplexStoppedWaitTypeDef",
     "DescribeInputDeviceResponseTypeDef",
     "InputDeviceSummaryTypeDef",
     "UpdateInputDeviceResponseTypeDef",
     "DescribeInputSecurityGroupResponseTypeDef",
     "InputSecurityGroupTypeDef",
-    "DescribeScheduleRequestDescribeSchedulePaginateTypeDef",
-    "ListChannelsRequestListChannelsPaginateTypeDef",
-    "ListInputDeviceTransfersRequestListInputDeviceTransfersPaginateTypeDef",
-    "ListInputDevicesRequestListInputDevicesPaginateTypeDef",
-    "ListInputSecurityGroupsRequestListInputSecurityGroupsPaginateTypeDef",
-    "ListInputsRequestListInputsPaginateTypeDef",
-    "ListMultiplexProgramsRequestListMultiplexProgramsPaginateTypeDef",
-    "ListMultiplexesRequestListMultiplexesPaginateTypeDef",
-    "ListOfferingsRequestListOfferingsPaginateTypeDef",
-    "ListReservationsRequestListReservationsPaginateTypeDef",
     "M2tsSettingsTypeDef",
     "FailoverConditionSettingsTypeDef",
     "ScheduleActionStartSettingsTypeDef",
     "FrameCaptureCdnSettingsTypeDef",
     "FrameCaptureSettingsTypeDef",
     "H264FilterSettingsTypeDef",
     "H265FilterSettingsTypeDef",
@@ -936,25 +937,14 @@
         "Arn": str,
         "Id": str,
         "State": str,
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
 BatchScheduleActionDeleteRequestTypeDef = TypedDict(
     "BatchScheduleActionDeleteRequestTypeDef",
     {
         "ActionNames": Sequence[str],
     },
 )
 
@@ -1476,14 +1466,26 @@
     "DescribeInputDeviceThumbnailRequestRequestTypeDef",
     {
         "InputDeviceId": str,
         "Accept": Literal["image/jpeg"],
     },
 )
 
+DescribeInputDeviceThumbnailResponseTypeDef = TypedDict(
+    "DescribeInputDeviceThumbnailResponseTypeDef",
+    {
+        "Body": StreamingBody,
+        "ContentType": Literal["image/jpeg"],
+        "ContentLength": int,
+        "ETag": str,
+        "LastModified": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeInputRequestRequestTypeDef = TypedDict(
     "DescribeInputRequestRequestTypeDef",
     {
         "InputId": str,
     },
 )
 
@@ -1545,24 +1547,36 @@
 DescribeReservationRequestRequestTypeDef = TypedDict(
     "DescribeReservationRequestRequestTypeDef",
     {
         "ReservationId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredDescribeScheduleRequestDescribeSchedulePaginateTypeDef = TypedDict(
+    "_RequiredDescribeScheduleRequestDescribeSchedulePaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ChannelId": str,
+    },
+)
+_OptionalDescribeScheduleRequestDescribeSchedulePaginateTypeDef = TypedDict(
+    "_OptionalDescribeScheduleRequestDescribeSchedulePaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class DescribeScheduleRequestDescribeSchedulePaginateTypeDef(
+    _RequiredDescribeScheduleRequestDescribeSchedulePaginateTypeDef,
+    _OptionalDescribeScheduleRequestDescribeSchedulePaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeScheduleRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeScheduleRequestRequestTypeDef",
     {
         "ChannelId": str,
     },
 )
 _OptionalDescribeScheduleRequestRequestTypeDef = TypedDict(
@@ -1616,14 +1630,21 @@
     "DvbTdtSettingsTypeDef",
     {
         "RepInterval": int,
     },
     total=False,
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 FeatureActivationsTypeDef = TypedDict(
     "FeatureActivationsTypeDef",
     {
         "InputPrepareScheduleActions": FeatureActivationsInputPrepareScheduleActionsType,
     },
     total=False,
 )
@@ -1831,15 +1852,17 @@
     total=False,
 )
 
 HlsId3SegmentTaggingScheduleActionSettingsTypeDef = TypedDict(
     "HlsId3SegmentTaggingScheduleActionSettingsTypeDef",
     {
         "Tag": str,
+        "Id3": str,
     },
+    total=False,
 )
 
 HlsInputSettingsTypeDef = TypedDict(
     "HlsInputSettingsTypeDef",
     {
         "Bandwidth": int,
         "BufferSegments": int,
@@ -1897,23 +1920,53 @@
     "InputDeviceRequestTypeDef",
     {
         "Id": str,
     },
     total=False,
 )
 
+ListChannelsRequestListChannelsPaginateTypeDef = TypedDict(
+    "ListChannelsRequestListChannelsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListChannelsRequestRequestTypeDef = TypedDict(
     "ListChannelsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredListInputDeviceTransfersRequestListInputDeviceTransfersPaginateTypeDef = TypedDict(
+    "_RequiredListInputDeviceTransfersRequestListInputDeviceTransfersPaginateTypeDef",
+    {
+        "TransferType": str,
+    },
+)
+_OptionalListInputDeviceTransfersRequestListInputDeviceTransfersPaginateTypeDef = TypedDict(
+    "_OptionalListInputDeviceTransfersRequestListInputDeviceTransfersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListInputDeviceTransfersRequestListInputDeviceTransfersPaginateTypeDef(
+    _RequiredListInputDeviceTransfersRequestListInputDeviceTransfersPaginateTypeDef,
+    _OptionalListInputDeviceTransfersRequestListInputDeviceTransfersPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListInputDeviceTransfersRequestRequestTypeDef = TypedDict(
     "_RequiredListInputDeviceTransfersRequestRequestTypeDef",
     {
         "TransferType": str,
     },
 )
 _OptionalListInputDeviceTransfersRequestRequestTypeDef = TypedDict(
@@ -1940,41 +1993,87 @@
         "Message": str,
         "TargetCustomerId": str,
         "TransferType": InputDeviceTransferTypeType,
     },
     total=False,
 )
 
+ListInputDevicesRequestListInputDevicesPaginateTypeDef = TypedDict(
+    "ListInputDevicesRequestListInputDevicesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListInputDevicesRequestRequestTypeDef = TypedDict(
     "ListInputDevicesRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListInputSecurityGroupsRequestListInputSecurityGroupsPaginateTypeDef = TypedDict(
+    "ListInputSecurityGroupsRequestListInputSecurityGroupsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListInputSecurityGroupsRequestRequestTypeDef = TypedDict(
     "ListInputSecurityGroupsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListInputsRequestListInputsPaginateTypeDef = TypedDict(
+    "ListInputsRequestListInputsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListInputsRequestRequestTypeDef = TypedDict(
     "ListInputsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredListMultiplexProgramsRequestListMultiplexProgramsPaginateTypeDef = TypedDict(
+    "_RequiredListMultiplexProgramsRequestListMultiplexProgramsPaginateTypeDef",
+    {
+        "MultiplexId": str,
+    },
+)
+_OptionalListMultiplexProgramsRequestListMultiplexProgramsPaginateTypeDef = TypedDict(
+    "_OptionalListMultiplexProgramsRequestListMultiplexProgramsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListMultiplexProgramsRequestListMultiplexProgramsPaginateTypeDef(
+    _RequiredListMultiplexProgramsRequestListMultiplexProgramsPaginateTypeDef,
+    _OptionalListMultiplexProgramsRequestListMultiplexProgramsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListMultiplexProgramsRequestRequestTypeDef = TypedDict(
     "_RequiredListMultiplexProgramsRequestRequestTypeDef",
     {
         "MultiplexId": str,
     },
 )
 _OptionalListMultiplexProgramsRequestRequestTypeDef = TypedDict(
@@ -1999,23 +2098,49 @@
     {
         "ChannelId": str,
         "ProgramName": str,
     },
     total=False,
 )
 
+ListMultiplexesRequestListMultiplexesPaginateTypeDef = TypedDict(
+    "ListMultiplexesRequestListMultiplexesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListMultiplexesRequestRequestTypeDef = TypedDict(
     "ListMultiplexesRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListOfferingsRequestListOfferingsPaginateTypeDef = TypedDict(
+    "ListOfferingsRequestListOfferingsPaginateTypeDef",
+    {
+        "ChannelClass": str,
+        "ChannelConfiguration": str,
+        "Codec": str,
+        "Duration": str,
+        "MaximumBitrate": str,
+        "MaximumFramerate": str,
+        "Resolution": str,
+        "ResourceType": str,
+        "SpecialFeature": str,
+        "VideoQuality": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListOfferingsRequestRequestTypeDef = TypedDict(
     "ListOfferingsRequestRequestTypeDef",
     {
         "ChannelClass": str,
         "ChannelConfiguration": str,
         "Codec": str,
         "Duration": str,
@@ -2027,14 +2152,30 @@
         "ResourceType": str,
         "SpecialFeature": str,
         "VideoQuality": str,
     },
     total=False,
 )
 
+ListReservationsRequestListReservationsPaginateTypeDef = TypedDict(
+    "ListReservationsRequestListReservationsPaginateTypeDef",
+    {
+        "ChannelClass": str,
+        "Codec": str,
+        "MaximumBitrate": str,
+        "MaximumFramerate": str,
+        "Resolution": str,
+        "ResourceType": str,
+        "SpecialFeature": str,
+        "VideoQuality": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListReservationsRequestRequestTypeDef = TypedDict(
     "ListReservationsRequestRequestTypeDef",
     {
         "ChannelClass": str,
         "Codec": str,
         "MaxResults": int,
         "MaximumBitrate": str,
@@ -2051,14 +2192,22 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 M3u8SettingsTypeDef = TypedDict(
     "M3u8SettingsTypeDef",
     {
         "AudioFramesPerPes": int,
         "AudioPids": str,
         "EcmPid": str,
         "NielsenId3Behavior": M3u8NielsenId3BehaviorType,
@@ -2173,21 +2322,33 @@
     {
         "CbetCheckDigitString": str,
         "CbetStepaside": NielsenWatermarksCbetStepasideType,
         "Csid": str,
     },
 )
 
-NielsenNaesIiNwTypeDef = TypedDict(
-    "NielsenNaesIiNwTypeDef",
+_RequiredNielsenNaesIiNwTypeDef = TypedDict(
+    "_RequiredNielsenNaesIiNwTypeDef",
     {
         "CheckDigitString": str,
         "Sid": float,
     },
 )
+_OptionalNielsenNaesIiNwTypeDef = TypedDict(
+    "_OptionalNielsenNaesIiNwTypeDef",
+    {
+        "Timezone": NielsenWatermarkTimezonesType,
+    },
+    total=False,
+)
+
+
+class NielsenNaesIiNwTypeDef(_RequiredNielsenNaesIiNwTypeDef, _OptionalNielsenNaesIiNwTypeDef):
+    pass
+
 
 OutputDestinationSettingsTypeDef = TypedDict(
     "OutputDestinationSettingsTypeDef",
     {
         "PasswordParam": str,
         "StreamName": str,
         "Url": str,
@@ -2216,14 +2377,24 @@
         "InputLossAction": InputLossActionForUdpOutType,
         "TimedMetadataId3Frame": UdpTimedMetadataId3FrameType,
         "TimedMetadataId3Period": int,
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
 PipelinePauseStateSettingsTypeDef = TypedDict(
     "PipelinePauseStateSettingsTypeDef",
     {
         "PipelineId": PipelineIdType,
     },
 )
 
@@ -2251,14 +2422,25 @@
 RejectInputDeviceTransferRequestRequestTypeDef = TypedDict(
     "RejectInputDeviceTransferRequestRequestTypeDef",
     {
         "InputDeviceId": str,
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
 _RequiredScte35InputScheduleActionSettingsTypeDef = TypedDict(
     "_RequiredScte35InputScheduleActionSettingsTypeDef",
     {
         "Mode": Scte35InputModeType,
     },
 )
 _OptionalScte35InputScheduleActionSettingsTypeDef = TypedDict(
@@ -2680,60 +2862,33 @@
 )
 
 BatchDeleteResponseTypeDef = TypedDict(
     "BatchDeleteResponseTypeDef",
     {
         "Failed": List[BatchFailedResultModelTypeDef],
         "Successful": List[BatchSuccessfulResultModelTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchStartResponseTypeDef = TypedDict(
     "BatchStartResponseTypeDef",
     {
         "Failed": List[BatchFailedResultModelTypeDef],
         "Successful": List[BatchSuccessfulResultModelTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchStopResponseTypeDef = TypedDict(
     "BatchStopResponseTypeDef",
     {
         "Failed": List[BatchFailedResultModelTypeDef],
         "Successful": List[BatchSuccessfulResultModelTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeInputDeviceThumbnailResponseTypeDef = TypedDict(
-    "DescribeInputDeviceThumbnailResponseTypeDef",
-    {
-        "Body": StreamingBody,
-        "ContentType": Literal["image/jpeg"],
-        "ContentLength": int,
-        "ETag": str,
-        "LastModified": datetime,
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
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TeletextSourceSettingsTypeDef = TypedDict(
     "TeletextSourceSettingsTypeDef",
     {
         "OutputRectangle": CaptionRectangleTypeDef,
@@ -2904,15 +3059,15 @@
         "RenewalSettings": RenewalSettingsTypeDef,
         "ReservationId": str,
         "ResourceSpecification": ReservationResourceSpecificationTypeDef,
         "Start": str,
         "State": ReservationStateType,
         "Tags": Dict[str, str],
         "UsagePrice": float,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeOfferingResponseTypeDef = TypedDict(
     "DescribeOfferingResponseTypeDef",
     {
         "Arn": str,
@@ -2922,15 +3077,15 @@
         "FixedPrice": float,
         "OfferingDescription": str,
         "OfferingId": str,
         "OfferingType": Literal["NO_UPFRONT"],
         "Region": str,
         "ResourceSpecification": ReservationResourceSpecificationTypeDef,
         "UsagePrice": float,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeReservationResponseTypeDef = TypedDict(
     "DescribeReservationResponseTypeDef",
     {
         "Arn": str,
@@ -2948,15 +3103,15 @@
         "RenewalSettings": RenewalSettingsTypeDef,
         "ReservationId": str,
         "ResourceSpecification": ReservationResourceSpecificationTypeDef,
         "Start": str,
         "State": ReservationStateType,
         "Tags": Dict[str, str],
         "UsagePrice": float,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OfferingTypeDef = TypedDict(
     "OfferingTypeDef",
     {
         "Arn": str,
@@ -3253,15 +3408,16 @@
         "Id": str,
         "MacAddress": str,
         "Name": str,
         "NetworkSettings": InputDeviceNetworkSettingsTypeDef,
         "SerialNumber": str,
         "Type": InputDeviceTypeType,
         "UhdDeviceSettings": InputDeviceUhdSettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InputDeviceSummaryTypeDef = TypedDict(
     "InputDeviceSummaryTypeDef",
     {
         "Arn": str,
@@ -3272,14 +3428,15 @@
         "Id": str,
         "MacAddress": str,
         "Name": str,
         "NetworkSettings": InputDeviceNetworkSettingsTypeDef,
         "SerialNumber": str,
         "Type": InputDeviceTypeType,
         "UhdDeviceSettings": InputDeviceUhdSettingsTypeDef,
+        "Tags": Dict[str, str],
     },
     total=False,
 )
 
 UpdateInputDeviceResponseTypeDef = TypedDict(
     "UpdateInputDeviceResponseTypeDef",
     {
@@ -3291,28 +3448,29 @@
         "Id": str,
         "MacAddress": str,
         "Name": str,
         "NetworkSettings": InputDeviceNetworkSettingsTypeDef,
         "SerialNumber": str,
         "Type": InputDeviceTypeType,
         "UhdDeviceSettings": InputDeviceUhdSettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeInputSecurityGroupResponseTypeDef = TypedDict(
     "DescribeInputSecurityGroupResponseTypeDef",
     {
         "Arn": str,
         "Id": str,
         "Inputs": List[str],
         "State": InputSecurityGroupStateType,
         "Tags": Dict[str, str],
         "WhitelistRules": List[InputWhitelistRuleTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InputSecurityGroupTypeDef = TypedDict(
     "InputSecurityGroupTypeDef",
     {
         "Arn": str,
@@ -3321,154 +3479,14 @@
         "State": InputSecurityGroupStateType,
         "Tags": Dict[str, str],
         "WhitelistRules": List[InputWhitelistRuleTypeDef],
     },
     total=False,
 )
 
-_RequiredDescribeScheduleRequestDescribeSchedulePaginateTypeDef = TypedDict(
-    "_RequiredDescribeScheduleRequestDescribeSchedulePaginateTypeDef",
-    {
-        "ChannelId": str,
-    },
-)
-_OptionalDescribeScheduleRequestDescribeSchedulePaginateTypeDef = TypedDict(
-    "_OptionalDescribeScheduleRequestDescribeSchedulePaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeScheduleRequestDescribeSchedulePaginateTypeDef(
-    _RequiredDescribeScheduleRequestDescribeSchedulePaginateTypeDef,
-    _OptionalDescribeScheduleRequestDescribeSchedulePaginateTypeDef,
-):
-    pass
-
-
-ListChannelsRequestListChannelsPaginateTypeDef = TypedDict(
-    "ListChannelsRequestListChannelsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListInputDeviceTransfersRequestListInputDeviceTransfersPaginateTypeDef = TypedDict(
-    "_RequiredListInputDeviceTransfersRequestListInputDeviceTransfersPaginateTypeDef",
-    {
-        "TransferType": str,
-    },
-)
-_OptionalListInputDeviceTransfersRequestListInputDeviceTransfersPaginateTypeDef = TypedDict(
-    "_OptionalListInputDeviceTransfersRequestListInputDeviceTransfersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListInputDeviceTransfersRequestListInputDeviceTransfersPaginateTypeDef(
-    _RequiredListInputDeviceTransfersRequestListInputDeviceTransfersPaginateTypeDef,
-    _OptionalListInputDeviceTransfersRequestListInputDeviceTransfersPaginateTypeDef,
-):
-    pass
-
-
-ListInputDevicesRequestListInputDevicesPaginateTypeDef = TypedDict(
-    "ListInputDevicesRequestListInputDevicesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListInputSecurityGroupsRequestListInputSecurityGroupsPaginateTypeDef = TypedDict(
-    "ListInputSecurityGroupsRequestListInputSecurityGroupsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListInputsRequestListInputsPaginateTypeDef = TypedDict(
-    "ListInputsRequestListInputsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListMultiplexProgramsRequestListMultiplexProgramsPaginateTypeDef = TypedDict(
-    "_RequiredListMultiplexProgramsRequestListMultiplexProgramsPaginateTypeDef",
-    {
-        "MultiplexId": str,
-    },
-)
-_OptionalListMultiplexProgramsRequestListMultiplexProgramsPaginateTypeDef = TypedDict(
-    "_OptionalListMultiplexProgramsRequestListMultiplexProgramsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListMultiplexProgramsRequestListMultiplexProgramsPaginateTypeDef(
-    _RequiredListMultiplexProgramsRequestListMultiplexProgramsPaginateTypeDef,
-    _OptionalListMultiplexProgramsRequestListMultiplexProgramsPaginateTypeDef,
-):
-    pass
-
-
-ListMultiplexesRequestListMultiplexesPaginateTypeDef = TypedDict(
-    "ListMultiplexesRequestListMultiplexesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListOfferingsRequestListOfferingsPaginateTypeDef = TypedDict(
-    "ListOfferingsRequestListOfferingsPaginateTypeDef",
-    {
-        "ChannelClass": str,
-        "ChannelConfiguration": str,
-        "Codec": str,
-        "Duration": str,
-        "MaximumBitrate": str,
-        "MaximumFramerate": str,
-        "Resolution": str,
-        "ResourceType": str,
-        "SpecialFeature": str,
-        "VideoQuality": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListReservationsRequestListReservationsPaginateTypeDef = TypedDict(
-    "ListReservationsRequestListReservationsPaginateTypeDef",
-    {
-        "ChannelClass": str,
-        "Codec": str,
-        "MaximumBitrate": str,
-        "MaximumFramerate": str,
-        "Resolution": str,
-        "ResourceType": str,
-        "SpecialFeature": str,
-        "VideoQuality": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 M2tsSettingsTypeDef = TypedDict(
     "M2tsSettingsTypeDef",
     {
         "AbsentInputAudioBehavior": M2tsAbsentInputAudioBehaviorType,
         "Arib": M2tsAribType,
         "AribCaptionsPid": str,
         "AribCaptionsPidControl": M2tsAribCaptionsPidControlType,
@@ -3707,24 +3725,24 @@
 
 
 ListInputDeviceTransfersResponseTypeDef = TypedDict(
     "ListInputDeviceTransfersResponseTypeDef",
     {
         "InputDeviceTransfers": List[TransferringInputDeviceSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMultiplexProgramsResponseTypeDef = TypedDict(
     "ListMultiplexProgramsResponseTypeDef",
     {
         "MultiplexPrograms": List[MultiplexProgramSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStandardHlsSettingsTypeDef = TypedDict(
     "_RequiredStandardHlsSettingsTypeDef",
     {
         "M3u8Settings": M3u8SettingsTypeDef,
@@ -3984,74 +4002,74 @@
 )
 
 ListOfferingsResponseTypeDef = TypedDict(
     "ListOfferingsResponseTypeDef",
     {
         "NextToken": str,
         "Offerings": List[OfferingTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListReservationsResponseTypeDef = TypedDict(
     "ListReservationsResponseTypeDef",
     {
         "NextToken": str,
         "Reservations": List[ReservationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PurchaseOfferingResponseTypeDef = TypedDict(
     "PurchaseOfferingResponseTypeDef",
     {
         "Reservation": ReservationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateReservationResponseTypeDef = TypedDict(
     "UpdateReservationResponseTypeDef",
     {
         "Reservation": ReservationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListInputDevicesResponseTypeDef = TypedDict(
     "ListInputDevicesResponseTypeDef",
     {
         "InputDevices": List[InputDeviceSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateInputSecurityGroupResponseTypeDef = TypedDict(
     "CreateInputSecurityGroupResponseTypeDef",
     {
         "SecurityGroup": InputSecurityGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListInputSecurityGroupsResponseTypeDef = TypedDict(
     "ListInputSecurityGroupsResponseTypeDef",
     {
         "InputSecurityGroups": List[InputSecurityGroupTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateInputSecurityGroupResponseTypeDef = TypedDict(
     "UpdateInputSecurityGroupResponseTypeDef",
     {
         "SecurityGroup": InputSecurityGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ArchiveContainerSettingsTypeDef = TypedDict(
     "ArchiveContainerSettingsTypeDef",
     {
         "M2tsSettings": M2tsSettingsTypeDef,
@@ -4275,15 +4293,15 @@
         "Name": str,
         "RoleArn": str,
         "SecurityGroups": List[str],
         "Sources": List[InputSourceTypeDef],
         "State": InputStateType,
         "Tags": Dict[str, str],
         "Type": InputTypeType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InputTypeDef = TypedDict(
     "InputTypeDef",
     {
         "Arn": str,
@@ -4326,15 +4344,15 @@
         "Id": str,
         "MultiplexSettings": MultiplexSettingsTypeDef,
         "Name": str,
         "PipelinesRunningCount": int,
         "ProgramCount": int,
         "State": MultiplexStateType,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeMultiplexResponseTypeDef = TypedDict(
     "DescribeMultiplexResponseTypeDef",
     {
         "Arn": str,
@@ -4343,15 +4361,15 @@
         "Id": str,
         "MultiplexSettings": MultiplexSettingsTypeDef,
         "Name": str,
         "PipelinesRunningCount": int,
         "ProgramCount": int,
         "State": MultiplexStateType,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 MultiplexTypeDef = TypedDict(
     "MultiplexTypeDef",
     {
         "Arn": str,
@@ -4377,15 +4395,15 @@
         "Id": str,
         "MultiplexSettings": MultiplexSettingsTypeDef,
         "Name": str,
         "PipelinesRunningCount": int,
         "ProgramCount": int,
         "State": MultiplexStateType,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopMultiplexResponseTypeDef = TypedDict(
     "StopMultiplexResponseTypeDef",
     {
         "Arn": str,
@@ -4394,24 +4412,24 @@
         "Id": str,
         "MultiplexSettings": MultiplexSettingsTypeDef,
         "Name": str,
         "PipelinesRunningCount": int,
         "ProgramCount": int,
         "State": MultiplexStateType,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMultiplexesResponseTypeDef = TypedDict(
     "ListMultiplexesResponseTypeDef",
     {
         "Multiplexes": List[MultiplexSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredMultiplexProgramSettingsTypeDef = TypedDict(
     "_RequiredMultiplexProgramSettingsTypeDef",
     {
         "ProgramNumber": int,
@@ -4686,40 +4704,40 @@
     total=False,
 )
 
 CreateInputResponseTypeDef = TypedDict(
     "CreateInputResponseTypeDef",
     {
         "Input": InputTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreatePartnerInputResponseTypeDef = TypedDict(
     "CreatePartnerInputResponseTypeDef",
     {
         "Input": InputTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListInputsResponseTypeDef = TypedDict(
     "ListInputsResponseTypeDef",
     {
         "Inputs": List[InputTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateInputResponseTypeDef = TypedDict(
     "UpdateInputResponseTypeDef",
     {
         "Input": InputTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredHlsOutputSettingsTypeDef = TypedDict(
     "_RequiredHlsOutputSettingsTypeDef",
     {
         "HlsSettings": HlsSettingsTypeDef,
@@ -4742,23 +4760,23 @@
     pass
 
 
 CreateMultiplexResponseTypeDef = TypedDict(
     "CreateMultiplexResponseTypeDef",
     {
         "Multiplex": MultiplexTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateMultiplexResponseTypeDef = TypedDict(
     "UpdateMultiplexResponseTypeDef",
     {
         "Multiplex": MultiplexTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateMultiplexProgramRequestRequestTypeDef = TypedDict(
     "CreateMultiplexProgramRequestRequestTypeDef",
     {
         "MultiplexId": str,
@@ -4772,27 +4790,27 @@
     "DeleteMultiplexProgramResponseTypeDef",
     {
         "ChannelId": str,
         "MultiplexProgramSettings": MultiplexProgramSettingsTypeDef,
         "PacketIdentifiersMap": MultiplexProgramPacketIdentifiersMapTypeDef,
         "PipelineDetails": List[MultiplexProgramPipelineDetailTypeDef],
         "ProgramName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeMultiplexProgramResponseTypeDef = TypedDict(
     "DescribeMultiplexProgramResponseTypeDef",
     {
         "ChannelId": str,
         "MultiplexProgramSettings": MultiplexProgramSettingsTypeDef,
         "PacketIdentifiersMap": MultiplexProgramPacketIdentifiersMapTypeDef,
         "PipelineDetails": List[MultiplexProgramPipelineDetailTypeDef],
         "ProgramName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 MultiplexProgramTypeDef = TypedDict(
     "MultiplexProgramTypeDef",
     {
         "ChannelId": str,
@@ -4934,23 +4952,23 @@
     total=False,
 )
 
 CreateMultiplexProgramResponseTypeDef = TypedDict(
     "CreateMultiplexProgramResponseTypeDef",
     {
         "MultiplexProgram": MultiplexProgramTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateMultiplexProgramResponseTypeDef = TypedDict(
     "UpdateMultiplexProgramResponseTypeDef",
     {
         "MultiplexProgram": MultiplexProgramTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 Scte35TimeSignalScheduleActionSettingsTypeDef = TypedDict(
     "Scte35TimeSignalScheduleActionSettingsTypeDef",
     {
         "Scte35Descriptors": Sequence[Scte35DescriptorTypeDef],
@@ -5063,15 +5081,15 @@
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
 
 _RequiredEncoderSettingsTypeDef = TypedDict(
     "_RequiredEncoderSettingsTypeDef",
     {
         "AudioDescriptions": Sequence[AudioDescriptionTypeDef],
@@ -5122,15 +5140,15 @@
 )
 
 DescribeScheduleResponseTypeDef = TypedDict(
     "DescribeScheduleResponseTypeDef",
     {
         "NextToken": str,
         "ScheduleActions": List[ScheduleActionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ChannelTypeDef = TypedDict(
     "ChannelTypeDef",
     {
         "Arn": str,
@@ -5193,15 +5211,15 @@
         "Name": str,
         "PipelineDetails": List[PipelineDetailTypeDef],
         "PipelinesRunningCount": int,
         "RoleArn": str,
         "State": ChannelStateType,
         "Tags": Dict[str, str],
         "Vpc": VpcOutputSettingsDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeChannelResponseTypeDef = TypedDict(
     "DescribeChannelResponseTypeDef",
     {
         "Arn": str,
@@ -5218,15 +5236,15 @@
         "Name": str,
         "PipelineDetails": List[PipelineDetailTypeDef],
         "PipelinesRunningCount": int,
         "RoleArn": str,
         "State": ChannelStateType,
         "Tags": Dict[str, str],
         "Vpc": VpcOutputSettingsDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartChannelResponseTypeDef = TypedDict(
     "StartChannelResponseTypeDef",
     {
         "Arn": str,
@@ -5243,15 +5261,15 @@
         "Name": str,
         "PipelineDetails": List[PipelineDetailTypeDef],
         "PipelinesRunningCount": int,
         "RoleArn": str,
         "State": ChannelStateType,
         "Tags": Dict[str, str],
         "Vpc": VpcOutputSettingsDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopChannelResponseTypeDef = TypedDict(
     "StopChannelResponseTypeDef",
     {
         "Arn": str,
@@ -5268,15 +5286,15 @@
         "Name": str,
         "PipelineDetails": List[PipelineDetailTypeDef],
         "PipelinesRunningCount": int,
         "RoleArn": str,
         "State": ChannelStateType,
         "Tags": Dict[str, str],
         "Vpc": VpcOutputSettingsDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateChannelRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateChannelRequestRequestTypeDef",
     {
         "ChannelId": str,
@@ -5329,34 +5347,34 @@
 
 
 BatchUpdateScheduleResponseTypeDef = TypedDict(
     "BatchUpdateScheduleResponseTypeDef",
     {
         "Creates": BatchScheduleActionCreateResultTypeDef,
         "Deletes": BatchScheduleActionDeleteResultTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateChannelResponseTypeDef = TypedDict(
     "CreateChannelResponseTypeDef",
     {
         "Channel": ChannelTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateChannelClassResponseTypeDef = TypedDict(
     "UpdateChannelClassResponseTypeDef",
     {
         "Channel": ChannelTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateChannelResponseTypeDef = TypedDict(
     "UpdateChannelResponseTypeDef",
     {
         "Channel": ChannelTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-medialive-2.5.0.post1/types_aiobotocore_medialive/type_defs.pyi` & `types-aiobotocore-medialive-2.5.1/types_aiobotocore_medialive/type_defs.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -221,14 +221,15 @@
     Mpeg2TimecodeInsertionBehaviorType,
     MsSmoothH265PackagingTypeType,
     MultiplexStateType,
     NetworkInputServerValidationType,
     NielsenPcmToId3TaggingStateType,
     NielsenWatermarksCbetStepasideType,
     NielsenWatermarksDistributionTypesType,
+    NielsenWatermarkTimezonesType,
     PipelineIdType,
     PreferredChannelPipelineType,
     RebootInputDeviceForceType,
     ReservationAutomaticRenewalType,
     ReservationCodecType,
     ReservationMaximumBitrateType,
     ReservationMaximumFramerateType,
@@ -308,15 +309,14 @@
     "AudioTrackTypeDef",
     "EsamTypeDef",
     "Scte35SpliceInsertTypeDef",
     "Scte35TimeSignalAposTypeDef",
     "BatchDeleteRequestRequestTypeDef",
     "BatchFailedResultModelTypeDef",
     "BatchSuccessfulResultModelTypeDef",
-    "ResponseMetadataTypeDef",
     "BatchScheduleActionDeleteRequestTypeDef",
     "BatchStartRequestRequestTypeDef",
     "BatchStopRequestRequestTypeDef",
     "CancelInputDeviceTransferRequestRequestTypeDef",
     "EbuTtDDestinationSettingsTypeDef",
     "TtmlDestinationSettingsTypeDef",
     "WebvttDestinationSettingsTypeDef",
@@ -359,28 +359,30 @@
     "WaiterConfigTypeDef",
     "DescribeChannelRequestRequestTypeDef",
     "DescribeInputDeviceRequestRequestTypeDef",
     "InputDeviceHdSettingsTypeDef",
     "InputDeviceNetworkSettingsTypeDef",
     "InputDeviceUhdSettingsTypeDef",
     "DescribeInputDeviceThumbnailRequestRequestTypeDef",
+    "DescribeInputDeviceThumbnailResponseTypeDef",
     "DescribeInputRequestRequestTypeDef",
     "InputSourceTypeDef",
     "MediaConnectFlowTypeDef",
     "DescribeInputSecurityGroupRequestRequestTypeDef",
     "InputWhitelistRuleTypeDef",
     "DescribeMultiplexProgramRequestRequestTypeDef",
     "DescribeMultiplexRequestRequestTypeDef",
     "DescribeOfferingRequestRequestTypeDef",
     "DescribeReservationRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeScheduleRequestDescribeSchedulePaginateTypeDef",
     "DescribeScheduleRequestRequestTypeDef",
     "DvbNitSettingsTypeDef",
     "DvbSdtSettingsTypeDef",
     "DvbTdtSettingsTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "FeatureActivationsTypeDef",
     "NielsenConfigurationTypeDef",
     "TimecodeConfigTypeDef",
     "InputLossFailoverSettingsTypeDef",
     "VideoBlackFailoverSettingsTypeDef",
     "FecOutputSettingsTypeDef",
     "FixedModeScheduleActionStartSettingsTypeDef",
@@ -401,26 +403,36 @@
     "HlsInputSettingsTypeDef",
     "HlsTimedMetadataScheduleActionSettingsTypeDef",
     "StartTimecodeTypeDef",
     "StopTimecodeTypeDef",
     "InputDestinationVpcTypeDef",
     "InputDeviceConfigurableSettingsTypeDef",
     "InputDeviceRequestTypeDef",
+    "ListChannelsRequestListChannelsPaginateTypeDef",
     "ListChannelsRequestRequestTypeDef",
+    "ListInputDeviceTransfersRequestListInputDeviceTransfersPaginateTypeDef",
     "ListInputDeviceTransfersRequestRequestTypeDef",
     "TransferringInputDeviceSummaryTypeDef",
+    "ListInputDevicesRequestListInputDevicesPaginateTypeDef",
     "ListInputDevicesRequestRequestTypeDef",
+    "ListInputSecurityGroupsRequestListInputSecurityGroupsPaginateTypeDef",
     "ListInputSecurityGroupsRequestRequestTypeDef",
+    "ListInputsRequestListInputsPaginateTypeDef",
     "ListInputsRequestRequestTypeDef",
+    "ListMultiplexProgramsRequestListMultiplexProgramsPaginateTypeDef",
     "ListMultiplexProgramsRequestRequestTypeDef",
     "MultiplexProgramSummaryTypeDef",
+    "ListMultiplexesRequestListMultiplexesPaginateTypeDef",
     "ListMultiplexesRequestRequestTypeDef",
+    "ListOfferingsRequestListOfferingsPaginateTypeDef",
     "ListOfferingsRequestRequestTypeDef",
+    "ListReservationsRequestListReservationsPaginateTypeDef",
     "ListReservationsRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "M3u8SettingsTypeDef",
     "MaintenanceUpdateSettingsTypeDef",
     "MediaPackageOutputDestinationSettingsTypeDef",
     "MotionGraphicsActivateScheduleActionSettingsTypeDef",
     "MotionGraphicsSettingsTypeDef",
     "MsSmoothOutputSettingsTypeDef",
     "MultiplexMediaConnectOutputDestinationSettingsTypeDef",
@@ -429,17 +441,19 @@
     "MultiplexSettingsSummaryTypeDef",
     "MultiplexStatmuxVideoSettingsTypeDef",
     "NielsenCBETTypeDef",
     "NielsenNaesIiNwTypeDef",
     "OutputDestinationSettingsTypeDef",
     "RtmpGroupSettingsTypeDef",
     "UdpGroupSettingsTypeDef",
+    "PaginatorConfigTypeDef",
     "PipelinePauseStateSettingsTypeDef",
     "RebootInputDeviceRequestRequestTypeDef",
     "RejectInputDeviceTransferRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "Scte35InputScheduleActionSettingsTypeDef",
     "Scte35ReturnToNetworkScheduleActionSettingsTypeDef",
     "Scte35SpliceInsertScheduleActionSettingsTypeDef",
     "StaticImageDeactivateScheduleActionSettingsTypeDef",
     "Scte35DeliveryRestrictionsTypeDef",
     "StartChannelRequestRequestTypeDef",
     "StartInputDeviceMaintenanceWindowRequestRequestTypeDef",
@@ -465,17 +479,14 @@
     "StaticImageActivateScheduleActionSettingsTypeDef",
     "StaticKeySettingsTypeDef",
     "AudioTrackSelectionTypeDef",
     "AvailSettingsTypeDef",
     "BatchDeleteResponseTypeDef",
     "BatchStartResponseTypeDef",
     "BatchStopResponseTypeDef",
-    "DescribeInputDeviceThumbnailResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ListTagsForResourceResponseTypeDef",
     "TeletextSourceSettingsTypeDef",
     "CreateInputRequestRequestTypeDef",
     "CreateInputSecurityGroupRequestRequestTypeDef",
     "UpdateInputSecurityGroupRequestRequestTypeDef",
     "CreateMultiplexRequestRequestTypeDef",
     "UpdateMultiplexRequestRequestTypeDef",
     "PurchaseOfferingRequestRequestTypeDef",
@@ -497,24 +508,14 @@
     "DescribeMultiplexRequestMultiplexRunningWaitTypeDef",
     "DescribeMultiplexRequestMultiplexStoppedWaitTypeDef",
     "DescribeInputDeviceResponseTypeDef",
     "InputDeviceSummaryTypeDef",
     "UpdateInputDeviceResponseTypeDef",
     "DescribeInputSecurityGroupResponseTypeDef",
     "InputSecurityGroupTypeDef",
-    "DescribeScheduleRequestDescribeSchedulePaginateTypeDef",
-    "ListChannelsRequestListChannelsPaginateTypeDef",
-    "ListInputDeviceTransfersRequestListInputDeviceTransfersPaginateTypeDef",
-    "ListInputDevicesRequestListInputDevicesPaginateTypeDef",
-    "ListInputSecurityGroupsRequestListInputSecurityGroupsPaginateTypeDef",
-    "ListInputsRequestListInputsPaginateTypeDef",
-    "ListMultiplexProgramsRequestListMultiplexProgramsPaginateTypeDef",
-    "ListMultiplexesRequestListMultiplexesPaginateTypeDef",
-    "ListOfferingsRequestListOfferingsPaginateTypeDef",
-    "ListReservationsRequestListReservationsPaginateTypeDef",
     "M2tsSettingsTypeDef",
     "FailoverConditionSettingsTypeDef",
     "ScheduleActionStartSettingsTypeDef",
     "FrameCaptureCdnSettingsTypeDef",
     "FrameCaptureSettingsTypeDef",
     "H264FilterSettingsTypeDef",
     "H265FilterSettingsTypeDef",
@@ -927,25 +928,14 @@
         "Arn": str,
         "Id": str,
         "State": str,
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
 BatchScheduleActionDeleteRequestTypeDef = TypedDict(
     "BatchScheduleActionDeleteRequestTypeDef",
     {
         "ActionNames": Sequence[str],
     },
 )
 
@@ -1457,14 +1447,26 @@
     "DescribeInputDeviceThumbnailRequestRequestTypeDef",
     {
         "InputDeviceId": str,
         "Accept": Literal["image/jpeg"],
     },
 )
 
+DescribeInputDeviceThumbnailResponseTypeDef = TypedDict(
+    "DescribeInputDeviceThumbnailResponseTypeDef",
+    {
+        "Body": StreamingBody,
+        "ContentType": Literal["image/jpeg"],
+        "ContentLength": int,
+        "ETag": str,
+        "LastModified": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeInputRequestRequestTypeDef = TypedDict(
     "DescribeInputRequestRequestTypeDef",
     {
         "InputId": str,
     },
 )
 
@@ -1526,24 +1528,34 @@
 DescribeReservationRequestRequestTypeDef = TypedDict(
     "DescribeReservationRequestRequestTypeDef",
     {
         "ReservationId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredDescribeScheduleRequestDescribeSchedulePaginateTypeDef = TypedDict(
+    "_RequiredDescribeScheduleRequestDescribeSchedulePaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ChannelId": str,
+    },
+)
+_OptionalDescribeScheduleRequestDescribeSchedulePaginateTypeDef = TypedDict(
+    "_OptionalDescribeScheduleRequestDescribeSchedulePaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class DescribeScheduleRequestDescribeSchedulePaginateTypeDef(
+    _RequiredDescribeScheduleRequestDescribeSchedulePaginateTypeDef,
+    _OptionalDescribeScheduleRequestDescribeSchedulePaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeScheduleRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeScheduleRequestRequestTypeDef",
     {
         "ChannelId": str,
     },
 )
 _OptionalDescribeScheduleRequestRequestTypeDef = TypedDict(
@@ -1593,14 +1605,21 @@
     "DvbTdtSettingsTypeDef",
     {
         "RepInterval": int,
     },
     total=False,
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 FeatureActivationsTypeDef = TypedDict(
     "FeatureActivationsTypeDef",
     {
         "InputPrepareScheduleActions": FeatureActivationsInputPrepareScheduleActionsType,
     },
     total=False,
 )
@@ -1804,15 +1823,17 @@
     total=False,
 )
 
 HlsId3SegmentTaggingScheduleActionSettingsTypeDef = TypedDict(
     "HlsId3SegmentTaggingScheduleActionSettingsTypeDef",
     {
         "Tag": str,
+        "Id3": str,
     },
+    total=False,
 )
 
 HlsInputSettingsTypeDef = TypedDict(
     "HlsInputSettingsTypeDef",
     {
         "Bandwidth": int,
         "BufferSegments": int,
@@ -1870,23 +1891,51 @@
     "InputDeviceRequestTypeDef",
     {
         "Id": str,
     },
     total=False,
 )
 
+ListChannelsRequestListChannelsPaginateTypeDef = TypedDict(
+    "ListChannelsRequestListChannelsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListChannelsRequestRequestTypeDef = TypedDict(
     "ListChannelsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredListInputDeviceTransfersRequestListInputDeviceTransfersPaginateTypeDef = TypedDict(
+    "_RequiredListInputDeviceTransfersRequestListInputDeviceTransfersPaginateTypeDef",
+    {
+        "TransferType": str,
+    },
+)
+_OptionalListInputDeviceTransfersRequestListInputDeviceTransfersPaginateTypeDef = TypedDict(
+    "_OptionalListInputDeviceTransfersRequestListInputDeviceTransfersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListInputDeviceTransfersRequestListInputDeviceTransfersPaginateTypeDef(
+    _RequiredListInputDeviceTransfersRequestListInputDeviceTransfersPaginateTypeDef,
+    _OptionalListInputDeviceTransfersRequestListInputDeviceTransfersPaginateTypeDef,
+):
+    pass
+
 _RequiredListInputDeviceTransfersRequestRequestTypeDef = TypedDict(
     "_RequiredListInputDeviceTransfersRequestRequestTypeDef",
     {
         "TransferType": str,
     },
 )
 _OptionalListInputDeviceTransfersRequestRequestTypeDef = TypedDict(
@@ -1911,41 +1960,85 @@
         "Message": str,
         "TargetCustomerId": str,
         "TransferType": InputDeviceTransferTypeType,
     },
     total=False,
 )
 
+ListInputDevicesRequestListInputDevicesPaginateTypeDef = TypedDict(
+    "ListInputDevicesRequestListInputDevicesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListInputDevicesRequestRequestTypeDef = TypedDict(
     "ListInputDevicesRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListInputSecurityGroupsRequestListInputSecurityGroupsPaginateTypeDef = TypedDict(
+    "ListInputSecurityGroupsRequestListInputSecurityGroupsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListInputSecurityGroupsRequestRequestTypeDef = TypedDict(
     "ListInputSecurityGroupsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListInputsRequestListInputsPaginateTypeDef = TypedDict(
+    "ListInputsRequestListInputsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListInputsRequestRequestTypeDef = TypedDict(
     "ListInputsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredListMultiplexProgramsRequestListMultiplexProgramsPaginateTypeDef = TypedDict(
+    "_RequiredListMultiplexProgramsRequestListMultiplexProgramsPaginateTypeDef",
+    {
+        "MultiplexId": str,
+    },
+)
+_OptionalListMultiplexProgramsRequestListMultiplexProgramsPaginateTypeDef = TypedDict(
+    "_OptionalListMultiplexProgramsRequestListMultiplexProgramsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListMultiplexProgramsRequestListMultiplexProgramsPaginateTypeDef(
+    _RequiredListMultiplexProgramsRequestListMultiplexProgramsPaginateTypeDef,
+    _OptionalListMultiplexProgramsRequestListMultiplexProgramsPaginateTypeDef,
+):
+    pass
+
 _RequiredListMultiplexProgramsRequestRequestTypeDef = TypedDict(
     "_RequiredListMultiplexProgramsRequestRequestTypeDef",
     {
         "MultiplexId": str,
     },
 )
 _OptionalListMultiplexProgramsRequestRequestTypeDef = TypedDict(
@@ -1968,23 +2061,49 @@
     {
         "ChannelId": str,
         "ProgramName": str,
     },
     total=False,
 )
 
+ListMultiplexesRequestListMultiplexesPaginateTypeDef = TypedDict(
+    "ListMultiplexesRequestListMultiplexesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListMultiplexesRequestRequestTypeDef = TypedDict(
     "ListMultiplexesRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListOfferingsRequestListOfferingsPaginateTypeDef = TypedDict(
+    "ListOfferingsRequestListOfferingsPaginateTypeDef",
+    {
+        "ChannelClass": str,
+        "ChannelConfiguration": str,
+        "Codec": str,
+        "Duration": str,
+        "MaximumBitrate": str,
+        "MaximumFramerate": str,
+        "Resolution": str,
+        "ResourceType": str,
+        "SpecialFeature": str,
+        "VideoQuality": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListOfferingsRequestRequestTypeDef = TypedDict(
     "ListOfferingsRequestRequestTypeDef",
     {
         "ChannelClass": str,
         "ChannelConfiguration": str,
         "Codec": str,
         "Duration": str,
@@ -1996,14 +2115,30 @@
         "ResourceType": str,
         "SpecialFeature": str,
         "VideoQuality": str,
     },
     total=False,
 )
 
+ListReservationsRequestListReservationsPaginateTypeDef = TypedDict(
+    "ListReservationsRequestListReservationsPaginateTypeDef",
+    {
+        "ChannelClass": str,
+        "Codec": str,
+        "MaximumBitrate": str,
+        "MaximumFramerate": str,
+        "Resolution": str,
+        "ResourceType": str,
+        "SpecialFeature": str,
+        "VideoQuality": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListReservationsRequestRequestTypeDef = TypedDict(
     "ListReservationsRequestRequestTypeDef",
     {
         "ChannelClass": str,
         "Codec": str,
         "MaxResults": int,
         "MaximumBitrate": str,
@@ -2020,14 +2155,22 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 M3u8SettingsTypeDef = TypedDict(
     "M3u8SettingsTypeDef",
     {
         "AudioFramesPerPes": int,
         "AudioPids": str,
         "EcmPid": str,
         "NielsenId3Behavior": M3u8NielsenId3BehaviorType,
@@ -2142,21 +2285,31 @@
     {
         "CbetCheckDigitString": str,
         "CbetStepaside": NielsenWatermarksCbetStepasideType,
         "Csid": str,
     },
 )
 
-NielsenNaesIiNwTypeDef = TypedDict(
-    "NielsenNaesIiNwTypeDef",
+_RequiredNielsenNaesIiNwTypeDef = TypedDict(
+    "_RequiredNielsenNaesIiNwTypeDef",
     {
         "CheckDigitString": str,
         "Sid": float,
     },
 )
+_OptionalNielsenNaesIiNwTypeDef = TypedDict(
+    "_OptionalNielsenNaesIiNwTypeDef",
+    {
+        "Timezone": NielsenWatermarkTimezonesType,
+    },
+    total=False,
+)
+
+class NielsenNaesIiNwTypeDef(_RequiredNielsenNaesIiNwTypeDef, _OptionalNielsenNaesIiNwTypeDef):
+    pass
 
 OutputDestinationSettingsTypeDef = TypedDict(
     "OutputDestinationSettingsTypeDef",
     {
         "PasswordParam": str,
         "StreamName": str,
         "Url": str,
@@ -2185,14 +2338,24 @@
         "InputLossAction": InputLossActionForUdpOutType,
         "TimedMetadataId3Frame": UdpTimedMetadataId3FrameType,
         "TimedMetadataId3Period": int,
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
 PipelinePauseStateSettingsTypeDef = TypedDict(
     "PipelinePauseStateSettingsTypeDef",
     {
         "PipelineId": PipelineIdType,
     },
 )
 
@@ -2218,14 +2381,25 @@
 RejectInputDeviceTransferRequestRequestTypeDef = TypedDict(
     "RejectInputDeviceTransferRequestRequestTypeDef",
     {
         "InputDeviceId": str,
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
 _RequiredScte35InputScheduleActionSettingsTypeDef = TypedDict(
     "_RequiredScte35InputScheduleActionSettingsTypeDef",
     {
         "Mode": Scte35InputModeType,
     },
 )
 _OptionalScte35InputScheduleActionSettingsTypeDef = TypedDict(
@@ -2631,60 +2805,33 @@
 )
 
 BatchDeleteResponseTypeDef = TypedDict(
     "BatchDeleteResponseTypeDef",
     {
         "Failed": List[BatchFailedResultModelTypeDef],
         "Successful": List[BatchSuccessfulResultModelTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchStartResponseTypeDef = TypedDict(
     "BatchStartResponseTypeDef",
     {
         "Failed": List[BatchFailedResultModelTypeDef],
         "Successful": List[BatchSuccessfulResultModelTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchStopResponseTypeDef = TypedDict(
     "BatchStopResponseTypeDef",
     {
         "Failed": List[BatchFailedResultModelTypeDef],
         "Successful": List[BatchSuccessfulResultModelTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeInputDeviceThumbnailResponseTypeDef = TypedDict(
-    "DescribeInputDeviceThumbnailResponseTypeDef",
-    {
-        "Body": StreamingBody,
-        "ContentType": Literal["image/jpeg"],
-        "ContentLength": int,
-        "ETag": str,
-        "LastModified": datetime,
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
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TeletextSourceSettingsTypeDef = TypedDict(
     "TeletextSourceSettingsTypeDef",
     {
         "OutputRectangle": CaptionRectangleTypeDef,
@@ -2845,15 +2992,15 @@
         "RenewalSettings": RenewalSettingsTypeDef,
         "ReservationId": str,
         "ResourceSpecification": ReservationResourceSpecificationTypeDef,
         "Start": str,
         "State": ReservationStateType,
         "Tags": Dict[str, str],
         "UsagePrice": float,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeOfferingResponseTypeDef = TypedDict(
     "DescribeOfferingResponseTypeDef",
     {
         "Arn": str,
@@ -2863,15 +3010,15 @@
         "FixedPrice": float,
         "OfferingDescription": str,
         "OfferingId": str,
         "OfferingType": Literal["NO_UPFRONT"],
         "Region": str,
         "ResourceSpecification": ReservationResourceSpecificationTypeDef,
         "UsagePrice": float,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeReservationResponseTypeDef = TypedDict(
     "DescribeReservationResponseTypeDef",
     {
         "Arn": str,
@@ -2889,15 +3036,15 @@
         "RenewalSettings": RenewalSettingsTypeDef,
         "ReservationId": str,
         "ResourceSpecification": ReservationResourceSpecificationTypeDef,
         "Start": str,
         "State": ReservationStateType,
         "Tags": Dict[str, str],
         "UsagePrice": float,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OfferingTypeDef = TypedDict(
     "OfferingTypeDef",
     {
         "Arn": str,
@@ -3172,15 +3319,16 @@
         "Id": str,
         "MacAddress": str,
         "Name": str,
         "NetworkSettings": InputDeviceNetworkSettingsTypeDef,
         "SerialNumber": str,
         "Type": InputDeviceTypeType,
         "UhdDeviceSettings": InputDeviceUhdSettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InputDeviceSummaryTypeDef = TypedDict(
     "InputDeviceSummaryTypeDef",
     {
         "Arn": str,
@@ -3191,14 +3339,15 @@
         "Id": str,
         "MacAddress": str,
         "Name": str,
         "NetworkSettings": InputDeviceNetworkSettingsTypeDef,
         "SerialNumber": str,
         "Type": InputDeviceTypeType,
         "UhdDeviceSettings": InputDeviceUhdSettingsTypeDef,
+        "Tags": Dict[str, str],
     },
     total=False,
 )
 
 UpdateInputDeviceResponseTypeDef = TypedDict(
     "UpdateInputDeviceResponseTypeDef",
     {
@@ -3210,28 +3359,29 @@
         "Id": str,
         "MacAddress": str,
         "Name": str,
         "NetworkSettings": InputDeviceNetworkSettingsTypeDef,
         "SerialNumber": str,
         "Type": InputDeviceTypeType,
         "UhdDeviceSettings": InputDeviceUhdSettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeInputSecurityGroupResponseTypeDef = TypedDict(
     "DescribeInputSecurityGroupResponseTypeDef",
     {
         "Arn": str,
         "Id": str,
         "Inputs": List[str],
         "State": InputSecurityGroupStateType,
         "Tags": Dict[str, str],
         "WhitelistRules": List[InputWhitelistRuleTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InputSecurityGroupTypeDef = TypedDict(
     "InputSecurityGroupTypeDef",
     {
         "Arn": str,
@@ -3240,148 +3390,14 @@
         "State": InputSecurityGroupStateType,
         "Tags": Dict[str, str],
         "WhitelistRules": List[InputWhitelistRuleTypeDef],
     },
     total=False,
 )
 
-_RequiredDescribeScheduleRequestDescribeSchedulePaginateTypeDef = TypedDict(
-    "_RequiredDescribeScheduleRequestDescribeSchedulePaginateTypeDef",
-    {
-        "ChannelId": str,
-    },
-)
-_OptionalDescribeScheduleRequestDescribeSchedulePaginateTypeDef = TypedDict(
-    "_OptionalDescribeScheduleRequestDescribeSchedulePaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeScheduleRequestDescribeSchedulePaginateTypeDef(
-    _RequiredDescribeScheduleRequestDescribeSchedulePaginateTypeDef,
-    _OptionalDescribeScheduleRequestDescribeSchedulePaginateTypeDef,
-):
-    pass
-
-ListChannelsRequestListChannelsPaginateTypeDef = TypedDict(
-    "ListChannelsRequestListChannelsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListInputDeviceTransfersRequestListInputDeviceTransfersPaginateTypeDef = TypedDict(
-    "_RequiredListInputDeviceTransfersRequestListInputDeviceTransfersPaginateTypeDef",
-    {
-        "TransferType": str,
-    },
-)
-_OptionalListInputDeviceTransfersRequestListInputDeviceTransfersPaginateTypeDef = TypedDict(
-    "_OptionalListInputDeviceTransfersRequestListInputDeviceTransfersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListInputDeviceTransfersRequestListInputDeviceTransfersPaginateTypeDef(
-    _RequiredListInputDeviceTransfersRequestListInputDeviceTransfersPaginateTypeDef,
-    _OptionalListInputDeviceTransfersRequestListInputDeviceTransfersPaginateTypeDef,
-):
-    pass
-
-ListInputDevicesRequestListInputDevicesPaginateTypeDef = TypedDict(
-    "ListInputDevicesRequestListInputDevicesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListInputSecurityGroupsRequestListInputSecurityGroupsPaginateTypeDef = TypedDict(
-    "ListInputSecurityGroupsRequestListInputSecurityGroupsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListInputsRequestListInputsPaginateTypeDef = TypedDict(
-    "ListInputsRequestListInputsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListMultiplexProgramsRequestListMultiplexProgramsPaginateTypeDef = TypedDict(
-    "_RequiredListMultiplexProgramsRequestListMultiplexProgramsPaginateTypeDef",
-    {
-        "MultiplexId": str,
-    },
-)
-_OptionalListMultiplexProgramsRequestListMultiplexProgramsPaginateTypeDef = TypedDict(
-    "_OptionalListMultiplexProgramsRequestListMultiplexProgramsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListMultiplexProgramsRequestListMultiplexProgramsPaginateTypeDef(
-    _RequiredListMultiplexProgramsRequestListMultiplexProgramsPaginateTypeDef,
-    _OptionalListMultiplexProgramsRequestListMultiplexProgramsPaginateTypeDef,
-):
-    pass
-
-ListMultiplexesRequestListMultiplexesPaginateTypeDef = TypedDict(
-    "ListMultiplexesRequestListMultiplexesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListOfferingsRequestListOfferingsPaginateTypeDef = TypedDict(
-    "ListOfferingsRequestListOfferingsPaginateTypeDef",
-    {
-        "ChannelClass": str,
-        "ChannelConfiguration": str,
-        "Codec": str,
-        "Duration": str,
-        "MaximumBitrate": str,
-        "MaximumFramerate": str,
-        "Resolution": str,
-        "ResourceType": str,
-        "SpecialFeature": str,
-        "VideoQuality": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListReservationsRequestListReservationsPaginateTypeDef = TypedDict(
-    "ListReservationsRequestListReservationsPaginateTypeDef",
-    {
-        "ChannelClass": str,
-        "Codec": str,
-        "MaximumBitrate": str,
-        "MaximumFramerate": str,
-        "Resolution": str,
-        "ResourceType": str,
-        "SpecialFeature": str,
-        "VideoQuality": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 M2tsSettingsTypeDef = TypedDict(
     "M2tsSettingsTypeDef",
     {
         "AbsentInputAudioBehavior": M2tsAbsentInputAudioBehaviorType,
         "Arib": M2tsAribType,
         "AribCaptionsPid": str,
         "AribCaptionsPidControl": M2tsAribCaptionsPidControlType,
@@ -3614,24 +3630,24 @@
     pass
 
 ListInputDeviceTransfersResponseTypeDef = TypedDict(
     "ListInputDeviceTransfersResponseTypeDef",
     {
         "InputDeviceTransfers": List[TransferringInputDeviceSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMultiplexProgramsResponseTypeDef = TypedDict(
     "ListMultiplexProgramsResponseTypeDef",
     {
         "MultiplexPrograms": List[MultiplexProgramSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStandardHlsSettingsTypeDef = TypedDict(
     "_RequiredStandardHlsSettingsTypeDef",
     {
         "M3u8Settings": M3u8SettingsTypeDef,
@@ -3881,74 +3897,74 @@
 )
 
 ListOfferingsResponseTypeDef = TypedDict(
     "ListOfferingsResponseTypeDef",
     {
         "NextToken": str,
         "Offerings": List[OfferingTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListReservationsResponseTypeDef = TypedDict(
     "ListReservationsResponseTypeDef",
     {
         "NextToken": str,
         "Reservations": List[ReservationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PurchaseOfferingResponseTypeDef = TypedDict(
     "PurchaseOfferingResponseTypeDef",
     {
         "Reservation": ReservationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateReservationResponseTypeDef = TypedDict(
     "UpdateReservationResponseTypeDef",
     {
         "Reservation": ReservationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListInputDevicesResponseTypeDef = TypedDict(
     "ListInputDevicesResponseTypeDef",
     {
         "InputDevices": List[InputDeviceSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateInputSecurityGroupResponseTypeDef = TypedDict(
     "CreateInputSecurityGroupResponseTypeDef",
     {
         "SecurityGroup": InputSecurityGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListInputSecurityGroupsResponseTypeDef = TypedDict(
     "ListInputSecurityGroupsResponseTypeDef",
     {
         "InputSecurityGroups": List[InputSecurityGroupTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateInputSecurityGroupResponseTypeDef = TypedDict(
     "UpdateInputSecurityGroupResponseTypeDef",
     {
         "SecurityGroup": InputSecurityGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ArchiveContainerSettingsTypeDef = TypedDict(
     "ArchiveContainerSettingsTypeDef",
     {
         "M2tsSettings": M2tsSettingsTypeDef,
@@ -4164,15 +4180,15 @@
         "Name": str,
         "RoleArn": str,
         "SecurityGroups": List[str],
         "Sources": List[InputSourceTypeDef],
         "State": InputStateType,
         "Tags": Dict[str, str],
         "Type": InputTypeType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InputTypeDef = TypedDict(
     "InputTypeDef",
     {
         "Arn": str,
@@ -4215,15 +4231,15 @@
         "Id": str,
         "MultiplexSettings": MultiplexSettingsTypeDef,
         "Name": str,
         "PipelinesRunningCount": int,
         "ProgramCount": int,
         "State": MultiplexStateType,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeMultiplexResponseTypeDef = TypedDict(
     "DescribeMultiplexResponseTypeDef",
     {
         "Arn": str,
@@ -4232,15 +4248,15 @@
         "Id": str,
         "MultiplexSettings": MultiplexSettingsTypeDef,
         "Name": str,
         "PipelinesRunningCount": int,
         "ProgramCount": int,
         "State": MultiplexStateType,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 MultiplexTypeDef = TypedDict(
     "MultiplexTypeDef",
     {
         "Arn": str,
@@ -4266,15 +4282,15 @@
         "Id": str,
         "MultiplexSettings": MultiplexSettingsTypeDef,
         "Name": str,
         "PipelinesRunningCount": int,
         "ProgramCount": int,
         "State": MultiplexStateType,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopMultiplexResponseTypeDef = TypedDict(
     "StopMultiplexResponseTypeDef",
     {
         "Arn": str,
@@ -4283,24 +4299,24 @@
         "Id": str,
         "MultiplexSettings": MultiplexSettingsTypeDef,
         "Name": str,
         "PipelinesRunningCount": int,
         "ProgramCount": int,
         "State": MultiplexStateType,
         "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMultiplexesResponseTypeDef = TypedDict(
     "ListMultiplexesResponseTypeDef",
     {
         "Multiplexes": List[MultiplexSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredMultiplexProgramSettingsTypeDef = TypedDict(
     "_RequiredMultiplexProgramSettingsTypeDef",
     {
         "ProgramNumber": int,
@@ -4557,40 +4573,40 @@
     total=False,
 )
 
 CreateInputResponseTypeDef = TypedDict(
     "CreateInputResponseTypeDef",
     {
         "Input": InputTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreatePartnerInputResponseTypeDef = TypedDict(
     "CreatePartnerInputResponseTypeDef",
     {
         "Input": InputTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListInputsResponseTypeDef = TypedDict(
     "ListInputsResponseTypeDef",
     {
         "Inputs": List[InputTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateInputResponseTypeDef = TypedDict(
     "UpdateInputResponseTypeDef",
     {
         "Input": InputTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredHlsOutputSettingsTypeDef = TypedDict(
     "_RequiredHlsOutputSettingsTypeDef",
     {
         "HlsSettings": HlsSettingsTypeDef,
@@ -4611,23 +4627,23 @@
 ):
     pass
 
 CreateMultiplexResponseTypeDef = TypedDict(
     "CreateMultiplexResponseTypeDef",
     {
         "Multiplex": MultiplexTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateMultiplexResponseTypeDef = TypedDict(
     "UpdateMultiplexResponseTypeDef",
     {
         "Multiplex": MultiplexTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateMultiplexProgramRequestRequestTypeDef = TypedDict(
     "CreateMultiplexProgramRequestRequestTypeDef",
     {
         "MultiplexId": str,
@@ -4641,27 +4657,27 @@
     "DeleteMultiplexProgramResponseTypeDef",
     {
         "ChannelId": str,
         "MultiplexProgramSettings": MultiplexProgramSettingsTypeDef,
         "PacketIdentifiersMap": MultiplexProgramPacketIdentifiersMapTypeDef,
         "PipelineDetails": List[MultiplexProgramPipelineDetailTypeDef],
         "ProgramName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeMultiplexProgramResponseTypeDef = TypedDict(
     "DescribeMultiplexProgramResponseTypeDef",
     {
         "ChannelId": str,
         "MultiplexProgramSettings": MultiplexProgramSettingsTypeDef,
         "PacketIdentifiersMap": MultiplexProgramPacketIdentifiersMapTypeDef,
         "PipelineDetails": List[MultiplexProgramPipelineDetailTypeDef],
         "ProgramName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 MultiplexProgramTypeDef = TypedDict(
     "MultiplexProgramTypeDef",
     {
         "ChannelId": str,
@@ -4797,23 +4813,23 @@
     total=False,
 )
 
 CreateMultiplexProgramResponseTypeDef = TypedDict(
     "CreateMultiplexProgramResponseTypeDef",
     {
         "MultiplexProgram": MultiplexProgramTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateMultiplexProgramResponseTypeDef = TypedDict(
     "UpdateMultiplexProgramResponseTypeDef",
     {
         "MultiplexProgram": MultiplexProgramTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 Scte35TimeSignalScheduleActionSettingsTypeDef = TypedDict(
     "Scte35TimeSignalScheduleActionSettingsTypeDef",
     {
         "Scte35Descriptors": Sequence[Scte35DescriptorTypeDef],
@@ -4922,15 +4938,15 @@
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
 
 _RequiredEncoderSettingsTypeDef = TypedDict(
     "_RequiredEncoderSettingsTypeDef",
     {
         "AudioDescriptions": Sequence[AudioDescriptionTypeDef],
@@ -4979,15 +4995,15 @@
 )
 
 DescribeScheduleResponseTypeDef = TypedDict(
     "DescribeScheduleResponseTypeDef",
     {
         "NextToken": str,
         "ScheduleActions": List[ScheduleActionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ChannelTypeDef = TypedDict(
     "ChannelTypeDef",
     {
         "Arn": str,
@@ -5050,15 +5066,15 @@
         "Name": str,
         "PipelineDetails": List[PipelineDetailTypeDef],
         "PipelinesRunningCount": int,
         "RoleArn": str,
         "State": ChannelStateType,
         "Tags": Dict[str, str],
         "Vpc": VpcOutputSettingsDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeChannelResponseTypeDef = TypedDict(
     "DescribeChannelResponseTypeDef",
     {
         "Arn": str,
@@ -5075,15 +5091,15 @@
         "Name": str,
         "PipelineDetails": List[PipelineDetailTypeDef],
         "PipelinesRunningCount": int,
         "RoleArn": str,
         "State": ChannelStateType,
         "Tags": Dict[str, str],
         "Vpc": VpcOutputSettingsDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartChannelResponseTypeDef = TypedDict(
     "StartChannelResponseTypeDef",
     {
         "Arn": str,
@@ -5100,15 +5116,15 @@
         "Name": str,
         "PipelineDetails": List[PipelineDetailTypeDef],
         "PipelinesRunningCount": int,
         "RoleArn": str,
         "State": ChannelStateType,
         "Tags": Dict[str, str],
         "Vpc": VpcOutputSettingsDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopChannelResponseTypeDef = TypedDict(
     "StopChannelResponseTypeDef",
     {
         "Arn": str,
@@ -5125,15 +5141,15 @@
         "Name": str,
         "PipelineDetails": List[PipelineDetailTypeDef],
         "PipelinesRunningCount": int,
         "RoleArn": str,
         "State": ChannelStateType,
         "Tags": Dict[str, str],
         "Vpc": VpcOutputSettingsDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateChannelRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateChannelRequestRequestTypeDef",
     {
         "ChannelId": str,
@@ -5182,34 +5198,34 @@
     pass
 
 BatchUpdateScheduleResponseTypeDef = TypedDict(
     "BatchUpdateScheduleResponseTypeDef",
     {
         "Creates": BatchScheduleActionCreateResultTypeDef,
         "Deletes": BatchScheduleActionDeleteResultTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateChannelResponseTypeDef = TypedDict(
     "CreateChannelResponseTypeDef",
     {
         "Channel": ChannelTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateChannelClassResponseTypeDef = TypedDict(
     "UpdateChannelClassResponseTypeDef",
     {
         "Channel": ChannelTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateChannelResponseTypeDef = TypedDict(
     "UpdateChannelResponseTypeDef",
     {
         "Channel": ChannelTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-medialive-2.5.0.post1/types_aiobotocore_medialive/waiter.py` & `types-aiobotocore-medialive-2.5.1/types_aiobotocore_medialive/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-medialive-2.5.0.post1/types_aiobotocore_medialive/waiter.pyi` & `types-aiobotocore-medialive-2.5.1/types_aiobotocore_medialive/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-medialive-2.5.0.post1/types_aiobotocore_medialive.egg-info/PKG-INFO` & `types-aiobotocore-medialive-2.5.1/types_aiobotocore_medialive.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-medialive
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.MediaLive 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.MediaLive 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-medialive"></a>
 
 # types-aiobotocore-medialive
 
 [![PyPI - types-aiobotocore-medialive](https://img.shields.io/pypi/v/types-aiobotocore-medialive.svg?color=blue)](https://pypi.org/project/types-aiobotocore-medialive)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-medialive.svg?color=blue)](https://pypi.org/project/types-aiobotocore-medialive)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-medialive?color=blue)](https://pypistats.org/packages/types-aiobotocore-medialive)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.MediaLive 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive)
+[aiobotocore.MediaLive 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/medialive.html#MediaLive)
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
 [types-aiobotocore-medialive docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_medialive/).
 
 See how it helps to find and fix potential bugs:
 
@@ -599,14 +599,15 @@
     MultiplexCreatedWaiterName,
     MultiplexDeletedWaiterName,
     MultiplexRunningWaiterName,
     MultiplexStateType,
     MultiplexStoppedWaiterName,
     NetworkInputServerValidationType,
     NielsenPcmToId3TaggingStateType,
+    NielsenWatermarkTimezonesType,
     NielsenWatermarksCbetStepasideType,
     NielsenWatermarksDistributionTypesType,
     OfferingDurationUnitsType,
     OfferingTypeType,
     PipelineIdType,
     PreferredChannelPipelineType,
     RebootInputDeviceForceType,
@@ -701,15 +702,14 @@
     AudioTrackTypeDef,
     EsamTypeDef,
     Scte35SpliceInsertTypeDef,
     Scte35TimeSignalAposTypeDef,
     BatchDeleteRequestRequestTypeDef,
     BatchFailedResultModelTypeDef,
     BatchSuccessfulResultModelTypeDef,
-    ResponseMetadataTypeDef,
     BatchScheduleActionDeleteRequestTypeDef,
     BatchStartRequestRequestTypeDef,
     BatchStopRequestRequestTypeDef,
     CancelInputDeviceTransferRequestRequestTypeDef,
     EbuTtDDestinationSettingsTypeDef,
     TtmlDestinationSettingsTypeDef,
     WebvttDestinationSettingsTypeDef,
@@ -752,28 +752,30 @@
     WaiterConfigTypeDef,
     DescribeChannelRequestRequestTypeDef,
     DescribeInputDeviceRequestRequestTypeDef,
     InputDeviceHdSettingsTypeDef,
     InputDeviceNetworkSettingsTypeDef,
     InputDeviceUhdSettingsTypeDef,
     DescribeInputDeviceThumbnailRequestRequestTypeDef,
+    DescribeInputDeviceThumbnailResponseTypeDef,
     DescribeInputRequestRequestTypeDef,
     InputSourceTypeDef,
     MediaConnectFlowTypeDef,
     DescribeInputSecurityGroupRequestRequestTypeDef,
     InputWhitelistRuleTypeDef,
     DescribeMultiplexProgramRequestRequestTypeDef,
     DescribeMultiplexRequestRequestTypeDef,
     DescribeOfferingRequestRequestTypeDef,
     DescribeReservationRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeScheduleRequestDescribeSchedulePaginateTypeDef,
     DescribeScheduleRequestRequestTypeDef,
     DvbNitSettingsTypeDef,
     DvbSdtSettingsTypeDef,
     DvbTdtSettingsTypeDef,
+    EmptyResponseMetadataTypeDef,
     FeatureActivationsTypeDef,
     NielsenConfigurationTypeDef,
     TimecodeConfigTypeDef,
     InputLossFailoverSettingsTypeDef,
     VideoBlackFailoverSettingsTypeDef,
     FecOutputSettingsTypeDef,
     FixedModeScheduleActionStartSettingsTypeDef,
@@ -794,26 +796,36 @@
     HlsInputSettingsTypeDef,
     HlsTimedMetadataScheduleActionSettingsTypeDef,
     StartTimecodeTypeDef,
     StopTimecodeTypeDef,
     InputDestinationVpcTypeDef,
     InputDeviceConfigurableSettingsTypeDef,
     InputDeviceRequestTypeDef,
+    ListChannelsRequestListChannelsPaginateTypeDef,
     ListChannelsRequestRequestTypeDef,
+    ListInputDeviceTransfersRequestListInputDeviceTransfersPaginateTypeDef,
     ListInputDeviceTransfersRequestRequestTypeDef,
     TransferringInputDeviceSummaryTypeDef,
+    ListInputDevicesRequestListInputDevicesPaginateTypeDef,
     ListInputDevicesRequestRequestTypeDef,
+    ListInputSecurityGroupsRequestListInputSecurityGroupsPaginateTypeDef,
     ListInputSecurityGroupsRequestRequestTypeDef,
+    ListInputsRequestListInputsPaginateTypeDef,
     ListInputsRequestRequestTypeDef,
+    ListMultiplexProgramsRequestListMultiplexProgramsPaginateTypeDef,
     ListMultiplexProgramsRequestRequestTypeDef,
     MultiplexProgramSummaryTypeDef,
+    ListMultiplexesRequestListMultiplexesPaginateTypeDef,
     ListMultiplexesRequestRequestTypeDef,
+    ListOfferingsRequestListOfferingsPaginateTypeDef,
     ListOfferingsRequestRequestTypeDef,
+    ListReservationsRequestListReservationsPaginateTypeDef,
     ListReservationsRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     M3u8SettingsTypeDef,
     MaintenanceUpdateSettingsTypeDef,
     MediaPackageOutputDestinationSettingsTypeDef,
     MotionGraphicsActivateScheduleActionSettingsTypeDef,
     MotionGraphicsSettingsTypeDef,
     MsSmoothOutputSettingsTypeDef,
     MultiplexMediaConnectOutputDestinationSettingsTypeDef,
@@ -822,17 +834,19 @@
     MultiplexSettingsSummaryTypeDef,
     MultiplexStatmuxVideoSettingsTypeDef,
     NielsenCBETTypeDef,
     NielsenNaesIiNwTypeDef,
     OutputDestinationSettingsTypeDef,
     RtmpGroupSettingsTypeDef,
     UdpGroupSettingsTypeDef,
+    PaginatorConfigTypeDef,
     PipelinePauseStateSettingsTypeDef,
     RebootInputDeviceRequestRequestTypeDef,
     RejectInputDeviceTransferRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     Scte35InputScheduleActionSettingsTypeDef,
     Scte35ReturnToNetworkScheduleActionSettingsTypeDef,
     Scte35SpliceInsertScheduleActionSettingsTypeDef,
     StaticImageDeactivateScheduleActionSettingsTypeDef,
     Scte35DeliveryRestrictionsTypeDef,
     StartChannelRequestRequestTypeDef,
     StartInputDeviceMaintenanceWindowRequestRequestTypeDef,
@@ -858,17 +872,14 @@
     StaticImageActivateScheduleActionSettingsTypeDef,
     StaticKeySettingsTypeDef,
     AudioTrackSelectionTypeDef,
     AvailSettingsTypeDef,
     BatchDeleteResponseTypeDef,
     BatchStartResponseTypeDef,
     BatchStopResponseTypeDef,
-    DescribeInputDeviceThumbnailResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ListTagsForResourceResponseTypeDef,
     TeletextSourceSettingsTypeDef,
     CreateInputRequestRequestTypeDef,
     CreateInputSecurityGroupRequestRequestTypeDef,
     UpdateInputSecurityGroupRequestRequestTypeDef,
     CreateMultiplexRequestRequestTypeDef,
     UpdateMultiplexRequestRequestTypeDef,
     PurchaseOfferingRequestRequestTypeDef,
@@ -890,24 +901,14 @@
     DescribeMultiplexRequestMultiplexRunningWaitTypeDef,
     DescribeMultiplexRequestMultiplexStoppedWaitTypeDef,
     DescribeInputDeviceResponseTypeDef,
     InputDeviceSummaryTypeDef,
     UpdateInputDeviceResponseTypeDef,
     DescribeInputSecurityGroupResponseTypeDef,
     InputSecurityGroupTypeDef,
-    DescribeScheduleRequestDescribeSchedulePaginateTypeDef,
-    ListChannelsRequestListChannelsPaginateTypeDef,
-    ListInputDeviceTransfersRequestListInputDeviceTransfersPaginateTypeDef,
-    ListInputDevicesRequestListInputDevicesPaginateTypeDef,
-    ListInputSecurityGroupsRequestListInputSecurityGroupsPaginateTypeDef,
-    ListInputsRequestListInputsPaginateTypeDef,
-    ListMultiplexProgramsRequestListMultiplexProgramsPaginateTypeDef,
-    ListMultiplexesRequestListMultiplexesPaginateTypeDef,
-    ListOfferingsRequestListOfferingsPaginateTypeDef,
-    ListReservationsRequestListReservationsPaginateTypeDef,
     M2tsSettingsTypeDef,
     FailoverConditionSettingsTypeDef,
     ScheduleActionStartSettingsTypeDef,
     FrameCaptureCdnSettingsTypeDef,
     FrameCaptureSettingsTypeDef,
     H264FilterSettingsTypeDef,
     H265FilterSettingsTypeDef,
@@ -1034,43 +1035,43 @@
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

### Comparing `types-aiobotocore-medialive-2.5.0.post1/types_aiobotocore_medialive.egg-info/SOURCES.txt` & `types-aiobotocore-medialive-2.5.1/types_aiobotocore_medialive.egg-info/SOURCES.txt`

 * *Files identical despite different names*

