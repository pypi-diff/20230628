# Comparing `tmp/types-aiobotocore-iotwireless-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-iotwireless-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-iotwireless-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:49 2023, max compression
+gzip compressed data, was "types-aiobotocore-iotwireless-2.5.1.tar", last modified: Wed Jun 28 01:43:40 2023, max compression
```

## Comparing `types-aiobotocore-iotwireless-2.5.0.post1.tar` & `types-aiobotocore-iotwireless-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:49.003320 types-aiobotocore-iotwireless-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:16:36.000000 types-aiobotocore-iotwireless-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    24383 2023-03-11 12:26:49.003320 types-aiobotocore-iotwireless-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    22796 2023-03-11 12:16:36.000000 types-aiobotocore-iotwireless-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:49.003320 types-aiobotocore-iotwireless-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2152 2023-03-11 12:16:36.000000 types-aiobotocore-iotwireless-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:48.995320 types-aiobotocore-iotwireless-2.5.0.post1/types_aiobotocore_iotwireless/
--rw-r--r--   0 runner    (1001) docker     (123)      474 2023-03-11 12:16:36.000000 types-aiobotocore-iotwireless-2.5.0.post1/types_aiobotocore_iotwireless/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      473 2023-03-11 12:16:36.000000 types-aiobotocore-iotwireless-2.5.0.post1/types_aiobotocore_iotwireless/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      959 2023-03-11 12:16:36.000000 types-aiobotocore-iotwireless-2.5.0.post1/types_aiobotocore_iotwireless/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    69668 2023-03-11 12:16:36.000000 types-aiobotocore-iotwireless-2.5.0.post1/types_aiobotocore_iotwireless/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    69558 2023-03-11 12:16:36.000000 types-aiobotocore-iotwireless-2.5.0.post1/types_aiobotocore_iotwireless/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    11339 2023-03-11 12:16:37.000000 types-aiobotocore-iotwireless-2.5.0.post1/types_aiobotocore_iotwireless/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    11337 2023-03-11 12:16:37.000000 types-aiobotocore-iotwireless-2.5.0.post1/types_aiobotocore_iotwireless/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:16:36.000000 types-aiobotocore-iotwireless-2.5.0.post1/types_aiobotocore_iotwireless/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    86976 2023-03-11 12:16:38.000000 types-aiobotocore-iotwireless-2.5.0.post1/types_aiobotocore_iotwireless/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    86897 2023-03-11 12:16:37.000000 types-aiobotocore-iotwireless-2.5.0.post1/types_aiobotocore_iotwireless/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:16:36.000000 types-aiobotocore-iotwireless-2.5.0.post1/types_aiobotocore_iotwireless/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:49.003320 types-aiobotocore-iotwireless-2.5.0.post1/types_aiobotocore_iotwireless.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    24383 2023-03-11 12:26:48.000000 types-aiobotocore-iotwireless-2.5.0.post1/types_aiobotocore_iotwireless.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      802 2023-03-11 12:26:48.000000 types-aiobotocore-iotwireless-2.5.0.post1/types_aiobotocore_iotwireless.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:48.000000 types-aiobotocore-iotwireless-2.5.0.post1/types_aiobotocore_iotwireless.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:48.000000 types-aiobotocore-iotwireless-2.5.0.post1/types_aiobotocore_iotwireless.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:48.000000 types-aiobotocore-iotwireless-2.5.0.post1/types_aiobotocore_iotwireless.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       30 2023-03-11 12:26:48.000000 types-aiobotocore-iotwireless-2.5.0.post1/types_aiobotocore_iotwireless.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:40.514157 types-aiobotocore-iotwireless-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:33:14.000000 types-aiobotocore-iotwireless-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    25602 2023-06-28 01:43:40.514157 types-aiobotocore-iotwireless-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    24021 2023-06-28 01:33:14.000000 types-aiobotocore-iotwireless-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:40.514157 types-aiobotocore-iotwireless-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2146 2023-06-28 01:33:14.000000 types-aiobotocore-iotwireless-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:40.506157 types-aiobotocore-iotwireless-2.5.1/types_aiobotocore_iotwireless/
+-rw-r--r--   0 runner    (1001) docker     (123)      474 2023-06-28 01:33:14.000000 types-aiobotocore-iotwireless-2.5.1/types_aiobotocore_iotwireless/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      473 2023-06-28 01:33:14.000000 types-aiobotocore-iotwireless-2.5.1/types_aiobotocore_iotwireless/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      947 2023-06-28 01:33:14.000000 types-aiobotocore-iotwireless-2.5.1/types_aiobotocore_iotwireless/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    75909 2023-06-28 01:33:15.000000 types-aiobotocore-iotwireless-2.5.1/types_aiobotocore_iotwireless/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    75791 2023-06-28 01:33:15.000000 types-aiobotocore-iotwireless-2.5.1/types_aiobotocore_iotwireless/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    12239 2023-06-28 01:33:15.000000 types-aiobotocore-iotwireless-2.5.1/types_aiobotocore_iotwireless/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12237 2023-06-28 01:33:15.000000 types-aiobotocore-iotwireless-2.5.1/types_aiobotocore_iotwireless/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:33:14.000000 types-aiobotocore-iotwireless-2.5.1/types_aiobotocore_iotwireless/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    97162 2023-06-28 01:33:18.000000 types-aiobotocore-iotwireless-2.5.1/types_aiobotocore_iotwireless/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    97073 2023-06-28 01:33:16.000000 types-aiobotocore-iotwireless-2.5.1/types_aiobotocore_iotwireless/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:33:14.000000 types-aiobotocore-iotwireless-2.5.1/types_aiobotocore_iotwireless/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:40.514157 types-aiobotocore-iotwireless-2.5.1/types_aiobotocore_iotwireless.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    25602 2023-06-28 01:43:40.000000 types-aiobotocore-iotwireless-2.5.1/types_aiobotocore_iotwireless.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      802 2023-06-28 01:43:40.000000 types-aiobotocore-iotwireless-2.5.1/types_aiobotocore_iotwireless.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:40.000000 types-aiobotocore-iotwireless-2.5.1/types_aiobotocore_iotwireless.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:40.000000 types-aiobotocore-iotwireless-2.5.1/types_aiobotocore_iotwireless.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:40.000000 types-aiobotocore-iotwireless-2.5.1/types_aiobotocore_iotwireless.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       30 2023-06-28 01:43:40.000000 types-aiobotocore-iotwireless-2.5.1/types_aiobotocore_iotwireless.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-iotwireless-2.5.0.post1/LICENSE` & `types-aiobotocore-iotwireless-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-iotwireless-2.5.0.post1/PKG-INFO` & `types-aiobotocore-iotwireless-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-iotwireless
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.IoTWireless 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.IoTWireless 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-iotwireless"></a>
 
 # types-aiobotocore-iotwireless
 
 [![PyPI - types-aiobotocore-iotwireless](https://img.shields.io/pypi/v/types-aiobotocore-iotwireless.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotwireless)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iotwireless.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotwireless)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iotwireless?color=blue)](https://pypistats.org/packages/types-aiobotocore-iotwireless)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoTWireless 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless)
+[aiobotocore.IoTWireless 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless)
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
 [types-aiobotocore-iotwireless docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/).
 
 See how it helps to find and fix potential bugs:
 
@@ -272,39 +272,44 @@
 from shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_iotwireless.literals import (
     ApplicationConfigTypeType,
     BatteryLevelType,
     ConnectionStatusType,
+    DeviceProfileTypeType,
     DeviceStateType,
     DlClassType,
     DownlinkModeType,
     EventNotificationPartnerTypeType,
     EventNotificationResourceTypeType,
     EventNotificationTopicStatusType,
     EventType,
     ExpressionTypeType,
     FuotaDeviceStatusType,
     FuotaTaskStatusType,
     IdentifierTypeType,
+    ImportTaskStatusType,
     LogLevelType,
     MessageTypeType,
+    MulticastFrameInfoType,
+    OnboardStatusType,
     PartnerTypeType,
     PositionConfigurationFecType,
     PositionConfigurationStatusType,
     PositionResourceTypeType,
     PositionSolverProviderType,
     PositionSolverTypeType,
     PositioningConfigStatusType,
     SigningAlgType,
     SupportedRfRegionType,
     WirelessDeviceEventType,
     WirelessDeviceFrameInfoType,
     WirelessDeviceIdTypeType,
+    WirelessDeviceSidewalkStatusType,
     WirelessDeviceTypeType,
     WirelessGatewayEventType,
     WirelessGatewayIdTypeType,
     WirelessGatewayServiceTypeType,
     WirelessGatewayTaskDefinitionTypeType,
     WirelessGatewayTaskStatusType,
     WirelessGatewayTypeType,
@@ -324,51 +329,65 @@
 ### Typed dictionaries
 
 `types_aiobotocore_iotwireless.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_iotwireless.type_defs import (
-    SessionKeysAbpV1_0_xTypeDef,
-    SessionKeysAbpV1_1TypeDef,
+    SessionKeysAbpV10XTypeDef,
+    SessionKeysAbpV11TypeDef,
     AccuracyTypeDef,
     ApplicationConfigTypeDef,
     SidewalkAccountInfoTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
     AssociateMulticastGroupWithFuotaTaskRequestRequestTypeDef,
     AssociateWirelessDeviceWithFuotaTaskRequestRequestTypeDef,
     AssociateWirelessDeviceWithMulticastGroupRequestRequestTypeDef,
     AssociateWirelessDeviceWithThingRequestRequestTypeDef,
     AssociateWirelessGatewayWithCertificateRequestRequestTypeDef,
+    AssociateWirelessGatewayWithCertificateResponseTypeDef,
     AssociateWirelessGatewayWithThingRequestRequestTypeDef,
     BeaconingTypeDef,
     CancelMulticastGroupSessionRequestRequestTypeDef,
     CdmaLocalIdTypeDef,
     CdmaNmrObjTypeDef,
     CertificateListTypeDef,
     LoRaWANConnectionStatusEventNotificationConfigurationsTypeDef,
     LoRaWANConnectionStatusResourceTypeEventConfigurationTypeDef,
+    CreateDestinationResponseTypeDef,
     LoRaWANDeviceProfileTypeDef,
+    CreateDeviceProfileResponseTypeDef,
     LoRaWANFuotaTaskTypeDef,
+    CreateFuotaTaskResponseTypeDef,
     LoRaWANMulticastTypeDef,
+    CreateMulticastGroupResponseTypeDef,
     TraceContentTypeDef,
+    CreateNetworkAnalyzerConfigurationResponseTypeDef,
     LoRaWANServiceProfileTypeDef,
+    CreateServiceProfileResponseTypeDef,
+    SidewalkCreateWirelessDeviceTypeDef,
+    CreateWirelessDeviceResponseTypeDef,
+    CreateWirelessGatewayResponseTypeDef,
+    CreateWirelessGatewayTaskDefinitionResponseTypeDef,
     CreateWirelessGatewayTaskRequestRequestTypeDef,
+    CreateWirelessGatewayTaskResponseTypeDef,
+    DakCertificateMetadataTypeDef,
     DeleteDestinationRequestRequestTypeDef,
     DeleteDeviceProfileRequestRequestTypeDef,
     DeleteFuotaTaskRequestRequestTypeDef,
     DeleteMulticastGroupRequestRequestTypeDef,
     DeleteNetworkAnalyzerConfigurationRequestRequestTypeDef,
     DeleteQueuedMessagesRequestRequestTypeDef,
     DeleteServiceProfileRequestRequestTypeDef,
+    DeleteWirelessDeviceImportTaskRequestRequestTypeDef,
     DeleteWirelessDeviceRequestRequestTypeDef,
     DeleteWirelessGatewayRequestRequestTypeDef,
     DeleteWirelessGatewayTaskDefinitionRequestRequestTypeDef,
     DeleteWirelessGatewayTaskRequestRequestTypeDef,
+    DeregisterWirelessDeviceRequestRequestTypeDef,
     DestinationsTypeDef,
     DeviceProfileTypeDef,
     SidewalkEventNotificationConfigurationsTypeDef,
     SidewalkResourceTypeEventConfigurationTypeDef,
     DisassociateAwsAccountFromPartnerAccountRequestRequestTypeDef,
     DisassociateMulticastGroupFromFuotaTaskRequestRequestTypeDef,
     DisassociateWirelessDeviceFromFuotaTaskRequestRequestTypeDef,
@@ -376,144 +395,144 @@
     DisassociateWirelessDeviceFromThingRequestRequestTypeDef,
     DisassociateWirelessGatewayFromCertificateRequestRequestTypeDef,
     DisassociateWirelessGatewayFromThingRequestRequestTypeDef,
     PositioningTypeDef,
     FuotaTaskTypeDef,
     GatewayListItemTypeDef,
     GetDestinationRequestRequestTypeDef,
+    GetDestinationResponseTypeDef,
     GetDeviceProfileRequestRequestTypeDef,
     GetFuotaTaskRequestRequestTypeDef,
     LoRaWANFuotaTaskGetInfoTypeDef,
     GetMulticastGroupRequestRequestTypeDef,
     LoRaWANMulticastGetTypeDef,
     GetMulticastGroupSessionRequestRequestTypeDef,
     LoRaWANMulticastSessionTypeDef,
     GetNetworkAnalyzerConfigurationRequestRequestTypeDef,
     GetPartnerAccountRequestRequestTypeDef,
     SidewalkAccountInfoWithFingerprintTypeDef,
     GetPositionConfigurationRequestRequestTypeDef,
     GnssTypeDef,
     IpTypeDef,
     WiFiAccessPointTypeDef,
+    GetPositionEstimateResponseTypeDef,
     GetPositionRequestRequestTypeDef,
     GetResourceEventConfigurationRequestRequestTypeDef,
     GetResourceLogLevelRequestRequestTypeDef,
+    GetResourceLogLevelResponseTypeDef,
     GetResourcePositionRequestRequestTypeDef,
+    GetResourcePositionResponseTypeDef,
     GetServiceEndpointRequestRequestTypeDef,
+    GetServiceEndpointResponseTypeDef,
     GetServiceProfileRequestRequestTypeDef,
     LoRaWANGetServiceProfileInfoTypeDef,
+    GetWirelessDeviceImportTaskRequestRequestTypeDef,
+    SidewalkGetStartImportInfoTypeDef,
     GetWirelessDeviceRequestRequestTypeDef,
     GetWirelessDeviceStatisticsRequestRequestTypeDef,
     SidewalkDeviceMetadataTypeDef,
     GetWirelessGatewayCertificateRequestRequestTypeDef,
+    GetWirelessGatewayCertificateResponseTypeDef,
     GetWirelessGatewayFirmwareInformationRequestRequestTypeDef,
     GetWirelessGatewayRequestRequestTypeDef,
     GetWirelessGatewayStatisticsRequestRequestTypeDef,
+    GetWirelessGatewayStatisticsResponseTypeDef,
     GetWirelessGatewayTaskDefinitionRequestRequestTypeDef,
     GetWirelessGatewayTaskRequestRequestTypeDef,
+    GetWirelessGatewayTaskResponseTypeDef,
     GlobalIdentityTypeDef,
     GsmLocalIdTypeDef,
+    ImportedSidewalkDeviceTypeDef,
     LoRaWANJoinEventNotificationConfigurationsTypeDef,
     LoRaWANJoinResourceTypeEventConfigurationTypeDef,
     ListDestinationsRequestRequestTypeDef,
     ListDeviceProfilesRequestRequestTypeDef,
+    ListDevicesForWirelessDeviceImportTaskRequestRequestTypeDef,
     ListEventConfigurationsRequestRequestTypeDef,
     ListFuotaTasksRequestRequestTypeDef,
     ListMulticastGroupsByFuotaTaskRequestRequestTypeDef,
     MulticastGroupByFuotaTaskTypeDef,
     ListMulticastGroupsRequestRequestTypeDef,
     MulticastGroupTypeDef,
     ListNetworkAnalyzerConfigurationsRequestRequestTypeDef,
     NetworkAnalyzerConfigurationsTypeDef,
     ListPartnerAccountsRequestRequestTypeDef,
     ListPositionConfigurationsRequestRequestTypeDef,
     ListQueuedMessagesRequestRequestTypeDef,
     ListServiceProfilesRequestRequestTypeDef,
     ServiceProfileTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListWirelessDeviceImportTasksRequestRequestTypeDef,
     ListWirelessDevicesRequestRequestTypeDef,
     ListWirelessGatewayTaskDefinitionsRequestRequestTypeDef,
     ListWirelessGatewaysRequestRequestTypeDef,
     LoRaWANGatewayMetadataTypeDef,
-    OtaaV1_0_xTypeDef,
-    OtaaV1_1TypeDef,
+    OtaaV10XTypeDef,
+    OtaaV11TypeDef,
     LoRaWANGatewayVersionTypeDef,
     LoRaWANListDeviceTypeDef,
     LoRaWANMulticastMetadataTypeDef,
     LoRaWANStartFuotaTaskTypeDef,
-    UpdateAbpV1_0_xTypeDef,
-    UpdateAbpV1_1TypeDef,
+    UpdateAbpV10XTypeDef,
+    UpdateAbpV11TypeDef,
     LteLocalIdTypeDef,
     LteNmrObjTypeDef,
     SemtechGnssConfigurationTypeDef,
     SemtechGnssDetailTypeDef,
     PutResourceLogLevelRequestRequestTypeDef,
     ResetResourceLogLevelRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
+    SendDataToMulticastGroupResponseTypeDef,
+    SendDataToWirelessDeviceResponseTypeDef,
     SidewalkSendDataToDeviceTypeDef,
+    SidewalkSingleStartImportInfoTypeDef,
+    SidewalkStartImportInfoTypeDef,
     SidewalkUpdateAccountTypeDef,
+    SidewalkUpdateImportInfoTypeDef,
+    StartSingleWirelessDeviceImportTaskResponseTypeDef,
+    StartWirelessDeviceImportTaskResponseTypeDef,
     TdscdmaLocalIdTypeDef,
     TdscdmaNmrObjTypeDef,
     TestWirelessDeviceRequestRequestTypeDef,
+    TestWirelessDeviceResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateDestinationRequestRequestTypeDef,
     UpdatePositionRequestRequestTypeDef,
     UpdateResourcePositionRequestRequestTypeDef,
     UpdateWirelessGatewayRequestRequestTypeDef,
     WcdmaLocalIdTypeDef,
     WcdmaNmrObjTypeDef,
     WirelessDeviceEventLogOptionTypeDef,
     WirelessGatewayEventLogOptionTypeDef,
-    AbpV1_0_xTypeDef,
-    AbpV1_1TypeDef,
+    AbpV10XTypeDef,
+    AbpV11TypeDef,
+    GetPositionResponseTypeDef,
+    AssociateAwsAccountWithPartnerAccountResponseTypeDef,
     AssociateAwsAccountWithPartnerAccountRequestRequestTypeDef,
     CreateDestinationRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     StartBulkAssociateWirelessDeviceWithMulticastGroupRequestRequestTypeDef,
     StartBulkDisassociateWirelessDeviceFromMulticastGroupRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
-    AssociateAwsAccountWithPartnerAccountResponseTypeDef,
-    AssociateWirelessGatewayWithCertificateResponseTypeDef,
-    CreateDestinationResponseTypeDef,
-    CreateDeviceProfileResponseTypeDef,
-    CreateFuotaTaskResponseTypeDef,
-    CreateMulticastGroupResponseTypeDef,
-    CreateNetworkAnalyzerConfigurationResponseTypeDef,
-    CreateServiceProfileResponseTypeDef,
-    CreateWirelessDeviceResponseTypeDef,
-    CreateWirelessGatewayResponseTypeDef,
-    CreateWirelessGatewayTaskDefinitionResponseTypeDef,
-    CreateWirelessGatewayTaskResponseTypeDef,
-    GetDestinationResponseTypeDef,
-    GetPositionEstimateResponseTypeDef,
-    GetPositionResponseTypeDef,
-    GetResourceLogLevelResponseTypeDef,
-    GetResourcePositionResponseTypeDef,
-    GetServiceEndpointResponseTypeDef,
-    GetWirelessGatewayCertificateResponseTypeDef,
-    GetWirelessGatewayStatisticsResponseTypeDef,
-    GetWirelessGatewayTaskResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    SendDataToMulticastGroupResponseTypeDef,
-    SendDataToWirelessDeviceResponseTypeDef,
-    TestWirelessDeviceResponseTypeDef,
     LoRaWANGatewayTypeDef,
     CdmaObjTypeDef,
     SidewalkDeviceTypeDef,
     SidewalkListDeviceTypeDef,
     ConnectionStatusEventConfigurationTypeDef,
     ConnectionStatusResourceTypeEventConfigurationTypeDef,
     CreateDeviceProfileRequestRequestTypeDef,
-    GetDeviceProfileResponseTypeDef,
     CreateFuotaTaskRequestRequestTypeDef,
     UpdateFuotaTaskRequestRequestTypeDef,
     CreateMulticastGroupRequestRequestTypeDef,
     UpdateMulticastGroupRequestRequestTypeDef,
     CreateNetworkAnalyzerConfigurationRequestRequestTypeDef,
     GetNetworkAnalyzerConfigurationResponseTypeDef,
     UpdateNetworkAnalyzerConfigurationRequestRequestTypeDef,
     CreateServiceProfileRequestRequestTypeDef,
+    SidewalkGetDeviceProfileTypeDef,
     ListDestinationsResponseTypeDef,
     ListDeviceProfilesResponseTypeDef,
     DeviceRegistrationStateEventConfigurationTypeDef,
     MessageDeliveryStatusEventConfigurationTypeDef,
     ProximityEventConfigurationTypeDef,
     DeviceRegistrationStateResourceTypeEventConfigurationTypeDef,
     MessageDeliveryStatusResourceTypeEventConfigurationTypeDef,
@@ -525,15 +544,18 @@
     GetFuotaTaskResponseTypeDef,
     GetMulticastGroupResponseTypeDef,
     GetMulticastGroupSessionResponseTypeDef,
     StartMulticastGroupSessionRequestRequestTypeDef,
     GetPartnerAccountResponseTypeDef,
     ListPartnerAccountsResponseTypeDef,
     GetServiceProfileResponseTypeDef,
+    GetWirelessDeviceImportTaskResponseTypeDef,
+    WirelessDeviceImportTaskTypeDef,
     GsmNmrObjTypeDef,
+    ImportedWirelessDeviceTypeDef,
     JoinEventConfigurationTypeDef,
     JoinResourceTypeEventConfigurationTypeDef,
     ListMulticastGroupsByFuotaTaskResponseTypeDef,
     ListMulticastGroupsResponseTypeDef,
     ListNetworkAnalyzerConfigurationsResponseTypeDef,
     ListServiceProfilesResponseTypeDef,
     LoRaWANDeviceMetadataTypeDef,
@@ -541,27 +563,33 @@
     LoRaWANUpdateGatewayTaskCreateTypeDef,
     LoRaWANUpdateGatewayTaskEntryTypeDef,
     MulticastWirelessMetadataTypeDef,
     StartFuotaTaskRequestRequestTypeDef,
     LteObjTypeDef,
     PositionSolverConfigurationsTypeDef,
     PositionSolverDetailsTypeDef,
+    StartSingleWirelessDeviceImportTaskRequestRequestTypeDef,
+    StartWirelessDeviceImportTaskRequestRequestTypeDef,
     UpdatePartnerAccountRequestRequestTypeDef,
+    UpdateWirelessDeviceImportTaskRequestRequestTypeDef,
     TdscdmaObjTypeDef,
     WcdmaObjTypeDef,
     WirelessDeviceLogOptionTypeDef,
     WirelessGatewayLogOptionTypeDef,
     CreateWirelessGatewayRequestRequestTypeDef,
     GetWirelessGatewayResponseTypeDef,
     WirelessGatewayStatisticsTypeDef,
     WirelessDeviceStatisticsTypeDef,
+    GetDeviceProfileResponseTypeDef,
     LoRaWANDeviceTypeDef,
     LoRaWANUpdateDeviceTypeDef,
     LoRaWANSendDataToDeviceTypeDef,
+    ListWirelessDeviceImportTasksResponseTypeDef,
     GsmObjTypeDef,
+    ListDevicesForWirelessDeviceImportTaskResponseTypeDef,
     EventNotificationItemConfigurationsTypeDef,
     GetResourceEventConfigurationResponseTypeDef,
     UpdateResourceEventConfigurationRequestRequestTypeDef,
     GetEventConfigurationByResourceTypesResponseTypeDef,
     UpdateEventConfigurationByResourceTypesRequestRequestTypeDef,
     GetWirelessDeviceStatisticsResponseTypeDef,
     GetWirelessGatewayFirmwareInformationResponseTypeDef,
@@ -589,54 +617,54 @@
     ListQueuedMessagesResponseTypeDef,
     SendDataToWirelessDeviceRequestRequestTypeDef,
     GetPositionEstimateRequestRequestTypeDef,
     ListEventConfigurationsResponseTypeDef,
 )
 
 
-def get_structure() -> SessionKeysAbpV1_0_xTypeDef:
+def get_structure() -> SessionKeysAbpV10XTypeDef:
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

### Comparing `types-aiobotocore-iotwireless-2.5.0.post1/README.md` & `types-aiobotocore-iotwireless-2.5.1/README.md`

 * *Files 6% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-iotwireless"></a>
 
 # types-aiobotocore-iotwireless
 
 [![PyPI - types-aiobotocore-iotwireless](https://img.shields.io/pypi/v/types-aiobotocore-iotwireless.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotwireless)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iotwireless.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotwireless)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iotwireless?color=blue)](https://pypistats.org/packages/types-aiobotocore-iotwireless)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoTWireless 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless)
+[aiobotocore.IoTWireless 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless)
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
 [types-aiobotocore-iotwireless docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/).
 
 See how it helps to find and fix potential bugs:
 
@@ -239,39 +239,44 @@
 from shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_iotwireless.literals import (
     ApplicationConfigTypeType,
     BatteryLevelType,
     ConnectionStatusType,
+    DeviceProfileTypeType,
     DeviceStateType,
     DlClassType,
     DownlinkModeType,
     EventNotificationPartnerTypeType,
     EventNotificationResourceTypeType,
     EventNotificationTopicStatusType,
     EventType,
     ExpressionTypeType,
     FuotaDeviceStatusType,
     FuotaTaskStatusType,
     IdentifierTypeType,
+    ImportTaskStatusType,
     LogLevelType,
     MessageTypeType,
+    MulticastFrameInfoType,
+    OnboardStatusType,
     PartnerTypeType,
     PositionConfigurationFecType,
     PositionConfigurationStatusType,
     PositionResourceTypeType,
     PositionSolverProviderType,
     PositionSolverTypeType,
     PositioningConfigStatusType,
     SigningAlgType,
     SupportedRfRegionType,
     WirelessDeviceEventType,
     WirelessDeviceFrameInfoType,
     WirelessDeviceIdTypeType,
+    WirelessDeviceSidewalkStatusType,
     WirelessDeviceTypeType,
     WirelessGatewayEventType,
     WirelessGatewayIdTypeType,
     WirelessGatewayServiceTypeType,
     WirelessGatewayTaskDefinitionTypeType,
     WirelessGatewayTaskStatusType,
     WirelessGatewayTypeType,
@@ -291,51 +296,65 @@
 ### Typed dictionaries
 
 `types_aiobotocore_iotwireless.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_iotwireless.type_defs import (
-    SessionKeysAbpV1_0_xTypeDef,
-    SessionKeysAbpV1_1TypeDef,
+    SessionKeysAbpV10XTypeDef,
+    SessionKeysAbpV11TypeDef,
     AccuracyTypeDef,
     ApplicationConfigTypeDef,
     SidewalkAccountInfoTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
     AssociateMulticastGroupWithFuotaTaskRequestRequestTypeDef,
     AssociateWirelessDeviceWithFuotaTaskRequestRequestTypeDef,
     AssociateWirelessDeviceWithMulticastGroupRequestRequestTypeDef,
     AssociateWirelessDeviceWithThingRequestRequestTypeDef,
     AssociateWirelessGatewayWithCertificateRequestRequestTypeDef,
+    AssociateWirelessGatewayWithCertificateResponseTypeDef,
     AssociateWirelessGatewayWithThingRequestRequestTypeDef,
     BeaconingTypeDef,
     CancelMulticastGroupSessionRequestRequestTypeDef,
     CdmaLocalIdTypeDef,
     CdmaNmrObjTypeDef,
     CertificateListTypeDef,
     LoRaWANConnectionStatusEventNotificationConfigurationsTypeDef,
     LoRaWANConnectionStatusResourceTypeEventConfigurationTypeDef,
+    CreateDestinationResponseTypeDef,
     LoRaWANDeviceProfileTypeDef,
+    CreateDeviceProfileResponseTypeDef,
     LoRaWANFuotaTaskTypeDef,
+    CreateFuotaTaskResponseTypeDef,
     LoRaWANMulticastTypeDef,
+    CreateMulticastGroupResponseTypeDef,
     TraceContentTypeDef,
+    CreateNetworkAnalyzerConfigurationResponseTypeDef,
     LoRaWANServiceProfileTypeDef,
+    CreateServiceProfileResponseTypeDef,
+    SidewalkCreateWirelessDeviceTypeDef,
+    CreateWirelessDeviceResponseTypeDef,
+    CreateWirelessGatewayResponseTypeDef,
+    CreateWirelessGatewayTaskDefinitionResponseTypeDef,
     CreateWirelessGatewayTaskRequestRequestTypeDef,
+    CreateWirelessGatewayTaskResponseTypeDef,
+    DakCertificateMetadataTypeDef,
     DeleteDestinationRequestRequestTypeDef,
     DeleteDeviceProfileRequestRequestTypeDef,
     DeleteFuotaTaskRequestRequestTypeDef,
     DeleteMulticastGroupRequestRequestTypeDef,
     DeleteNetworkAnalyzerConfigurationRequestRequestTypeDef,
     DeleteQueuedMessagesRequestRequestTypeDef,
     DeleteServiceProfileRequestRequestTypeDef,
+    DeleteWirelessDeviceImportTaskRequestRequestTypeDef,
     DeleteWirelessDeviceRequestRequestTypeDef,
     DeleteWirelessGatewayRequestRequestTypeDef,
     DeleteWirelessGatewayTaskDefinitionRequestRequestTypeDef,
     DeleteWirelessGatewayTaskRequestRequestTypeDef,
+    DeregisterWirelessDeviceRequestRequestTypeDef,
     DestinationsTypeDef,
     DeviceProfileTypeDef,
     SidewalkEventNotificationConfigurationsTypeDef,
     SidewalkResourceTypeEventConfigurationTypeDef,
     DisassociateAwsAccountFromPartnerAccountRequestRequestTypeDef,
     DisassociateMulticastGroupFromFuotaTaskRequestRequestTypeDef,
     DisassociateWirelessDeviceFromFuotaTaskRequestRequestTypeDef,
@@ -343,144 +362,144 @@
     DisassociateWirelessDeviceFromThingRequestRequestTypeDef,
     DisassociateWirelessGatewayFromCertificateRequestRequestTypeDef,
     DisassociateWirelessGatewayFromThingRequestRequestTypeDef,
     PositioningTypeDef,
     FuotaTaskTypeDef,
     GatewayListItemTypeDef,
     GetDestinationRequestRequestTypeDef,
+    GetDestinationResponseTypeDef,
     GetDeviceProfileRequestRequestTypeDef,
     GetFuotaTaskRequestRequestTypeDef,
     LoRaWANFuotaTaskGetInfoTypeDef,
     GetMulticastGroupRequestRequestTypeDef,
     LoRaWANMulticastGetTypeDef,
     GetMulticastGroupSessionRequestRequestTypeDef,
     LoRaWANMulticastSessionTypeDef,
     GetNetworkAnalyzerConfigurationRequestRequestTypeDef,
     GetPartnerAccountRequestRequestTypeDef,
     SidewalkAccountInfoWithFingerprintTypeDef,
     GetPositionConfigurationRequestRequestTypeDef,
     GnssTypeDef,
     IpTypeDef,
     WiFiAccessPointTypeDef,
+    GetPositionEstimateResponseTypeDef,
     GetPositionRequestRequestTypeDef,
     GetResourceEventConfigurationRequestRequestTypeDef,
     GetResourceLogLevelRequestRequestTypeDef,
+    GetResourceLogLevelResponseTypeDef,
     GetResourcePositionRequestRequestTypeDef,
+    GetResourcePositionResponseTypeDef,
     GetServiceEndpointRequestRequestTypeDef,
+    GetServiceEndpointResponseTypeDef,
     GetServiceProfileRequestRequestTypeDef,
     LoRaWANGetServiceProfileInfoTypeDef,
+    GetWirelessDeviceImportTaskRequestRequestTypeDef,
+    SidewalkGetStartImportInfoTypeDef,
     GetWirelessDeviceRequestRequestTypeDef,
     GetWirelessDeviceStatisticsRequestRequestTypeDef,
     SidewalkDeviceMetadataTypeDef,
     GetWirelessGatewayCertificateRequestRequestTypeDef,
+    GetWirelessGatewayCertificateResponseTypeDef,
     GetWirelessGatewayFirmwareInformationRequestRequestTypeDef,
     GetWirelessGatewayRequestRequestTypeDef,
     GetWirelessGatewayStatisticsRequestRequestTypeDef,
+    GetWirelessGatewayStatisticsResponseTypeDef,
     GetWirelessGatewayTaskDefinitionRequestRequestTypeDef,
     GetWirelessGatewayTaskRequestRequestTypeDef,
+    GetWirelessGatewayTaskResponseTypeDef,
     GlobalIdentityTypeDef,
     GsmLocalIdTypeDef,
+    ImportedSidewalkDeviceTypeDef,
     LoRaWANJoinEventNotificationConfigurationsTypeDef,
     LoRaWANJoinResourceTypeEventConfigurationTypeDef,
     ListDestinationsRequestRequestTypeDef,
     ListDeviceProfilesRequestRequestTypeDef,
+    ListDevicesForWirelessDeviceImportTaskRequestRequestTypeDef,
     ListEventConfigurationsRequestRequestTypeDef,
     ListFuotaTasksRequestRequestTypeDef,
     ListMulticastGroupsByFuotaTaskRequestRequestTypeDef,
     MulticastGroupByFuotaTaskTypeDef,
     ListMulticastGroupsRequestRequestTypeDef,
     MulticastGroupTypeDef,
     ListNetworkAnalyzerConfigurationsRequestRequestTypeDef,
     NetworkAnalyzerConfigurationsTypeDef,
     ListPartnerAccountsRequestRequestTypeDef,
     ListPositionConfigurationsRequestRequestTypeDef,
     ListQueuedMessagesRequestRequestTypeDef,
     ListServiceProfilesRequestRequestTypeDef,
     ServiceProfileTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListWirelessDeviceImportTasksRequestRequestTypeDef,
     ListWirelessDevicesRequestRequestTypeDef,
     ListWirelessGatewayTaskDefinitionsRequestRequestTypeDef,
     ListWirelessGatewaysRequestRequestTypeDef,
     LoRaWANGatewayMetadataTypeDef,
-    OtaaV1_0_xTypeDef,
-    OtaaV1_1TypeDef,
+    OtaaV10XTypeDef,
+    OtaaV11TypeDef,
     LoRaWANGatewayVersionTypeDef,
     LoRaWANListDeviceTypeDef,
     LoRaWANMulticastMetadataTypeDef,
     LoRaWANStartFuotaTaskTypeDef,
-    UpdateAbpV1_0_xTypeDef,
-    UpdateAbpV1_1TypeDef,
+    UpdateAbpV10XTypeDef,
+    UpdateAbpV11TypeDef,
     LteLocalIdTypeDef,
     LteNmrObjTypeDef,
     SemtechGnssConfigurationTypeDef,
     SemtechGnssDetailTypeDef,
     PutResourceLogLevelRequestRequestTypeDef,
     ResetResourceLogLevelRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
+    SendDataToMulticastGroupResponseTypeDef,
+    SendDataToWirelessDeviceResponseTypeDef,
     SidewalkSendDataToDeviceTypeDef,
+    SidewalkSingleStartImportInfoTypeDef,
+    SidewalkStartImportInfoTypeDef,
     SidewalkUpdateAccountTypeDef,
+    SidewalkUpdateImportInfoTypeDef,
+    StartSingleWirelessDeviceImportTaskResponseTypeDef,
+    StartWirelessDeviceImportTaskResponseTypeDef,
     TdscdmaLocalIdTypeDef,
     TdscdmaNmrObjTypeDef,
     TestWirelessDeviceRequestRequestTypeDef,
+    TestWirelessDeviceResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateDestinationRequestRequestTypeDef,
     UpdatePositionRequestRequestTypeDef,
     UpdateResourcePositionRequestRequestTypeDef,
     UpdateWirelessGatewayRequestRequestTypeDef,
     WcdmaLocalIdTypeDef,
     WcdmaNmrObjTypeDef,
     WirelessDeviceEventLogOptionTypeDef,
     WirelessGatewayEventLogOptionTypeDef,
-    AbpV1_0_xTypeDef,
-    AbpV1_1TypeDef,
+    AbpV10XTypeDef,
+    AbpV11TypeDef,
+    GetPositionResponseTypeDef,
+    AssociateAwsAccountWithPartnerAccountResponseTypeDef,
     AssociateAwsAccountWithPartnerAccountRequestRequestTypeDef,
     CreateDestinationRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     StartBulkAssociateWirelessDeviceWithMulticastGroupRequestRequestTypeDef,
     StartBulkDisassociateWirelessDeviceFromMulticastGroupRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
-    AssociateAwsAccountWithPartnerAccountResponseTypeDef,
-    AssociateWirelessGatewayWithCertificateResponseTypeDef,
-    CreateDestinationResponseTypeDef,
-    CreateDeviceProfileResponseTypeDef,
-    CreateFuotaTaskResponseTypeDef,
-    CreateMulticastGroupResponseTypeDef,
-    CreateNetworkAnalyzerConfigurationResponseTypeDef,
-    CreateServiceProfileResponseTypeDef,
-    CreateWirelessDeviceResponseTypeDef,
-    CreateWirelessGatewayResponseTypeDef,
-    CreateWirelessGatewayTaskDefinitionResponseTypeDef,
-    CreateWirelessGatewayTaskResponseTypeDef,
-    GetDestinationResponseTypeDef,
-    GetPositionEstimateResponseTypeDef,
-    GetPositionResponseTypeDef,
-    GetResourceLogLevelResponseTypeDef,
-    GetResourcePositionResponseTypeDef,
-    GetServiceEndpointResponseTypeDef,
-    GetWirelessGatewayCertificateResponseTypeDef,
-    GetWirelessGatewayStatisticsResponseTypeDef,
-    GetWirelessGatewayTaskResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    SendDataToMulticastGroupResponseTypeDef,
-    SendDataToWirelessDeviceResponseTypeDef,
-    TestWirelessDeviceResponseTypeDef,
     LoRaWANGatewayTypeDef,
     CdmaObjTypeDef,
     SidewalkDeviceTypeDef,
     SidewalkListDeviceTypeDef,
     ConnectionStatusEventConfigurationTypeDef,
     ConnectionStatusResourceTypeEventConfigurationTypeDef,
     CreateDeviceProfileRequestRequestTypeDef,
-    GetDeviceProfileResponseTypeDef,
     CreateFuotaTaskRequestRequestTypeDef,
     UpdateFuotaTaskRequestRequestTypeDef,
     CreateMulticastGroupRequestRequestTypeDef,
     UpdateMulticastGroupRequestRequestTypeDef,
     CreateNetworkAnalyzerConfigurationRequestRequestTypeDef,
     GetNetworkAnalyzerConfigurationResponseTypeDef,
     UpdateNetworkAnalyzerConfigurationRequestRequestTypeDef,
     CreateServiceProfileRequestRequestTypeDef,
+    SidewalkGetDeviceProfileTypeDef,
     ListDestinationsResponseTypeDef,
     ListDeviceProfilesResponseTypeDef,
     DeviceRegistrationStateEventConfigurationTypeDef,
     MessageDeliveryStatusEventConfigurationTypeDef,
     ProximityEventConfigurationTypeDef,
     DeviceRegistrationStateResourceTypeEventConfigurationTypeDef,
     MessageDeliveryStatusResourceTypeEventConfigurationTypeDef,
@@ -492,15 +511,18 @@
     GetFuotaTaskResponseTypeDef,
     GetMulticastGroupResponseTypeDef,
     GetMulticastGroupSessionResponseTypeDef,
     StartMulticastGroupSessionRequestRequestTypeDef,
     GetPartnerAccountResponseTypeDef,
     ListPartnerAccountsResponseTypeDef,
     GetServiceProfileResponseTypeDef,
+    GetWirelessDeviceImportTaskResponseTypeDef,
+    WirelessDeviceImportTaskTypeDef,
     GsmNmrObjTypeDef,
+    ImportedWirelessDeviceTypeDef,
     JoinEventConfigurationTypeDef,
     JoinResourceTypeEventConfigurationTypeDef,
     ListMulticastGroupsByFuotaTaskResponseTypeDef,
     ListMulticastGroupsResponseTypeDef,
     ListNetworkAnalyzerConfigurationsResponseTypeDef,
     ListServiceProfilesResponseTypeDef,
     LoRaWANDeviceMetadataTypeDef,
@@ -508,27 +530,33 @@
     LoRaWANUpdateGatewayTaskCreateTypeDef,
     LoRaWANUpdateGatewayTaskEntryTypeDef,
     MulticastWirelessMetadataTypeDef,
     StartFuotaTaskRequestRequestTypeDef,
     LteObjTypeDef,
     PositionSolverConfigurationsTypeDef,
     PositionSolverDetailsTypeDef,
+    StartSingleWirelessDeviceImportTaskRequestRequestTypeDef,
+    StartWirelessDeviceImportTaskRequestRequestTypeDef,
     UpdatePartnerAccountRequestRequestTypeDef,
+    UpdateWirelessDeviceImportTaskRequestRequestTypeDef,
     TdscdmaObjTypeDef,
     WcdmaObjTypeDef,
     WirelessDeviceLogOptionTypeDef,
     WirelessGatewayLogOptionTypeDef,
     CreateWirelessGatewayRequestRequestTypeDef,
     GetWirelessGatewayResponseTypeDef,
     WirelessGatewayStatisticsTypeDef,
     WirelessDeviceStatisticsTypeDef,
+    GetDeviceProfileResponseTypeDef,
     LoRaWANDeviceTypeDef,
     LoRaWANUpdateDeviceTypeDef,
     LoRaWANSendDataToDeviceTypeDef,
+    ListWirelessDeviceImportTasksResponseTypeDef,
     GsmObjTypeDef,
+    ListDevicesForWirelessDeviceImportTaskResponseTypeDef,
     EventNotificationItemConfigurationsTypeDef,
     GetResourceEventConfigurationResponseTypeDef,
     UpdateResourceEventConfigurationRequestRequestTypeDef,
     GetEventConfigurationByResourceTypesResponseTypeDef,
     UpdateEventConfigurationByResourceTypesRequestRequestTypeDef,
     GetWirelessDeviceStatisticsResponseTypeDef,
     GetWirelessGatewayFirmwareInformationResponseTypeDef,
@@ -556,54 +584,54 @@
     ListQueuedMessagesResponseTypeDef,
     SendDataToWirelessDeviceRequestRequestTypeDef,
     GetPositionEstimateRequestRequestTypeDef,
     ListEventConfigurationsResponseTypeDef,
 )
 
 
-def get_structure() -> SessionKeysAbpV1_0_xTypeDef:
+def get_structure() -> SessionKeysAbpV10XTypeDef:
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

### Comparing `types-aiobotocore-iotwireless-2.5.0.post1/setup.py` & `types-aiobotocore-iotwireless-2.5.1/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-iotwireless.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-iotwireless",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_iotwireless"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.IoTWireless 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.IoTWireless 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/"
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

### Comparing `types-aiobotocore-iotwireless-2.5.0.post1/types_aiobotocore_iotwireless/__main__.py` & `types-aiobotocore-iotwireless-2.5.1/types_aiobotocore_iotwireless/__main__.py`

 * *Files 25% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.IoTWireless 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.IoTWireless 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless\nOther"
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

### Comparing `types-aiobotocore-iotwireless-2.5.0.post1/types_aiobotocore_iotwireless/client.py` & `types-aiobotocore-iotwireless-2.5.1/types_aiobotocore_iotwireless/client.py`

 * *Files 2% similar despite different names*

```diff
@@ -19,18 +19,20 @@
 from typing import IO, Any, Dict, Mapping, Sequence, Type, Union
 
 from aiobotocore.client import AioBaseClient
 from aiobotocore.response import StreamingBody
 from botocore.client import ClientMeta
 
 from .literals import (
+    DeviceProfileTypeType,
     EventNotificationResourceTypeType,
     ExpressionTypeType,
     IdentifierTypeType,
     LogLevelType,
+    OnboardStatusType,
     PositioningConfigStatusType,
     PositionResourceTypeType,
     WirelessDeviceIdTypeType,
     WirelessDeviceTypeType,
     WirelessGatewayIdTypeType,
     WirelessGatewayServiceTypeType,
 )
@@ -65,38 +67,41 @@
     GetPositionEstimateResponseTypeDef,
     GetPositionResponseTypeDef,
     GetResourceEventConfigurationResponseTypeDef,
     GetResourceLogLevelResponseTypeDef,
     GetResourcePositionResponseTypeDef,
     GetServiceEndpointResponseTypeDef,
     GetServiceProfileResponseTypeDef,
+    GetWirelessDeviceImportTaskResponseTypeDef,
     GetWirelessDeviceResponseTypeDef,
     GetWirelessDeviceStatisticsResponseTypeDef,
     GetWirelessGatewayCertificateResponseTypeDef,
     GetWirelessGatewayFirmwareInformationResponseTypeDef,
     GetWirelessGatewayResponseTypeDef,
     GetWirelessGatewayStatisticsResponseTypeDef,
     GetWirelessGatewayTaskDefinitionResponseTypeDef,
     GetWirelessGatewayTaskResponseTypeDef,
     GnssTypeDef,
     IpTypeDef,
     JoinEventConfigurationTypeDef,
     JoinResourceTypeEventConfigurationTypeDef,
     ListDestinationsResponseTypeDef,
     ListDeviceProfilesResponseTypeDef,
+    ListDevicesForWirelessDeviceImportTaskResponseTypeDef,
     ListEventConfigurationsResponseTypeDef,
     ListFuotaTasksResponseTypeDef,
     ListMulticastGroupsByFuotaTaskResponseTypeDef,
     ListMulticastGroupsResponseTypeDef,
     ListNetworkAnalyzerConfigurationsResponseTypeDef,
     ListPartnerAccountsResponseTypeDef,
     ListPositionConfigurationsResponseTypeDef,
     ListQueuedMessagesResponseTypeDef,
     ListServiceProfilesResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
+    ListWirelessDeviceImportTasksResponseTypeDef,
     ListWirelessDevicesResponseTypeDef,
     ListWirelessGatewaysResponseTypeDef,
     ListWirelessGatewayTaskDefinitionsResponseTypeDef,
     LoRaWANDeviceProfileTypeDef,
     LoRaWANDeviceTypeDef,
     LoRaWANFuotaTaskTypeDef,
     LoRaWANGatewayTypeDef,
@@ -110,15 +115,21 @@
     MulticastWirelessMetadataTypeDef,
     PositionSolverConfigurationsTypeDef,
     ProximityEventConfigurationTypeDef,
     ProximityResourceTypeEventConfigurationTypeDef,
     SendDataToMulticastGroupResponseTypeDef,
     SendDataToWirelessDeviceResponseTypeDef,
     SidewalkAccountInfoTypeDef,
+    SidewalkCreateWirelessDeviceTypeDef,
+    SidewalkSingleStartImportInfoTypeDef,
+    SidewalkStartImportInfoTypeDef,
     SidewalkUpdateAccountTypeDef,
+    SidewalkUpdateImportInfoTypeDef,
+    StartSingleWirelessDeviceImportTaskResponseTypeDef,
+    StartWirelessDeviceImportTaskResponseTypeDef,
     TagTypeDef,
     TestWirelessDeviceResponseTypeDef,
     TraceContentTypeDef,
     UpdateWirelessGatewayTaskCreateTypeDef,
     WiFiAccessPointTypeDef,
     WirelessDeviceLogOptionTypeDef,
     WirelessGatewayLogOptionTypeDef,
@@ -288,15 +299,16 @@
 
     async def create_device_profile(
         self,
         *,
         Name: str = ...,
         LoRaWAN: LoRaWANDeviceProfileTypeDef = ...,
         Tags: Sequence[TagTypeDef] = ...,
-        ClientRequestToken: str = ...
+        ClientRequestToken: str = ...,
+        Sidewalk: Mapping[str, Any] = ...
     ) -> CreateDeviceProfileResponseTypeDef:
         """
         Creates a new device profile.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.create_device_profile)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#create_device_profile)
         """
@@ -306,15 +318,18 @@
         *,
         FirmwareUpdateImage: str,
         FirmwareUpdateRole: str,
         Name: str = ...,
         Description: str = ...,
         ClientRequestToken: str = ...,
         LoRaWAN: LoRaWANFuotaTaskTypeDef = ...,
-        Tags: Sequence[TagTypeDef] = ...
+        Tags: Sequence[TagTypeDef] = ...,
+        RedundancyPercent: int = ...,
+        FragmentSizeBytes: int = ...,
+        FragmentIntervalMS: int = ...
     ) -> CreateFuotaTaskResponseTypeDef:
         """
         Creates a FUOTA task.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.create_fuota_task)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#create_fuota_task)
         """
@@ -340,15 +355,16 @@
         *,
         Name: str,
         TraceContent: TraceContentTypeDef = ...,
         WirelessDevices: Sequence[str] = ...,
         WirelessGateways: Sequence[str] = ...,
         Description: str = ...,
         Tags: Sequence[TagTypeDef] = ...,
-        ClientRequestToken: str = ...
+        ClientRequestToken: str = ...,
+        MulticastGroups: Sequence[str] = ...
     ) -> CreateNetworkAnalyzerConfigurationResponseTypeDef:
         """
         Creates a new network analyzer configuration.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.create_network_analyzer_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#create_network_analyzer_configuration)
         """
@@ -374,15 +390,16 @@
         Type: WirelessDeviceTypeType,
         DestinationName: str,
         Name: str = ...,
         Description: str = ...,
         ClientRequestToken: str = ...,
         LoRaWAN: LoRaWANDeviceTypeDef = ...,
         Tags: Sequence[TagTypeDef] = ...,
-        Positioning: PositioningConfigStatusType = ...
+        Positioning: PositioningConfigStatusType = ...,
+        Sidewalk: SidewalkCreateWirelessDeviceTypeDef = ...
     ) -> CreateWirelessDeviceResponseTypeDef:
         """
         Provisions a wireless device.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.create_wireless_device)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#create_wireless_device)
         """
@@ -493,14 +510,22 @@
         """
         Deletes a wireless device.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.delete_wireless_device)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#delete_wireless_device)
         """
 
+    async def delete_wireless_device_import_task(self, *, Id: str) -> Dict[str, Any]:
+        """
+        Delete an import task.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.delete_wireless_device_import_task)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#delete_wireless_device_import_task)
+        """
+
     async def delete_wireless_gateway(self, *, Id: str) -> Dict[str, Any]:
         """
         Deletes a wireless gateway.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.delete_wireless_gateway)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#delete_wireless_gateway)
         """
@@ -517,14 +542,24 @@
         """
         Deletes a wireless gateway task definition.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.delete_wireless_gateway_task_definition)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#delete_wireless_gateway_task_definition)
         """
 
+    async def deregister_wireless_device(
+        self, *, Identifier: str, WirelessDeviceType: WirelessDeviceTypeType = ...
+    ) -> Dict[str, Any]:
+        """
+        Deregister a wireless device from AWS IoT Wireless.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.deregister_wireless_device)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#deregister_wireless_device)
+        """
+
     async def disassociate_aws_account_from_partner_account(
         self, *, PartnerAccountId: str, PartnerType: Literal["Sidewalk"]
     ) -> Dict[str, Any]:
         """
         Disassociates your AWS account from a partner account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.disassociate_aws_account_from_partner_account)
@@ -776,14 +811,25 @@
         """
         Gets information about a wireless device.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.get_wireless_device)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#get_wireless_device)
         """
 
+    async def get_wireless_device_import_task(
+        self, *, Id: str
+    ) -> GetWirelessDeviceImportTaskResponseTypeDef:
+        """
+        Get information about an import task and count of device onboarding summary
+        information for the import task.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.get_wireless_device_import_task)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#get_wireless_device_import_task)
+        """
+
     async def get_wireless_device_statistics(
         self, *, WirelessDeviceId: str
     ) -> GetWirelessDeviceStatisticsResponseTypeDef:
         """
         Gets operating information about a wireless device.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.get_wireless_device_statistics)
@@ -856,23 +902,42 @@
         Lists the destinations registered to your AWS account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.list_destinations)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#list_destinations)
         """
 
     async def list_device_profiles(
-        self, *, NextToken: str = ..., MaxResults: int = ...
+        self,
+        *,
+        NextToken: str = ...,
+        MaxResults: int = ...,
+        DeviceProfileType: DeviceProfileTypeType = ...
     ) -> ListDeviceProfilesResponseTypeDef:
         """
         Lists the device profiles registered to your AWS account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.list_device_profiles)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#list_device_profiles)
         """
 
+    async def list_devices_for_wireless_device_import_task(
+        self,
+        *,
+        Id: str,
+        MaxResults: int = ...,
+        NextToken: str = ...,
+        Status: OnboardStatusType = ...
+    ) -> ListDevicesForWirelessDeviceImportTaskResponseTypeDef:
+        """
+        List the Sidewalk devices in an import task and their onboarding status.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.list_devices_for_wireless_device_import_task)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#list_devices_for_wireless_device_import_task)
+        """
+
     async def list_event_configurations(
         self,
         *,
         ResourceType: EventNotificationResourceTypeType,
         MaxResults: int = ...,
         NextToken: str = ...
     ) -> ListEventConfigurationsResponseTypeDef:
@@ -978,14 +1043,24 @@
         """
         Lists the tags (metadata) you have assigned to the resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#list_tags_for_resource)
         """
 
+    async def list_wireless_device_import_tasks(
+        self, *, MaxResults: int = ..., NextToken: str = ...
+    ) -> ListWirelessDeviceImportTasksResponseTypeDef:
+        """
+        List wireless devices that have been added to an import task.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.list_wireless_device_import_tasks)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#list_wireless_device_import_tasks)
+        """
+
     async def list_wireless_devices(
         self,
         *,
         MaxResults: int = ...,
         NextToken: str = ...,
         DestinationName: str = ...,
         DeviceProfileId: str = ...,
@@ -1133,25 +1208,57 @@
         """
         Starts a multicast group session.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.start_multicast_group_session)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#start_multicast_group_session)
         """
 
+    async def start_single_wireless_device_import_task(
+        self,
+        *,
+        DestinationName: str,
+        Sidewalk: SidewalkSingleStartImportInfoTypeDef,
+        ClientRequestToken: str = ...,
+        DeviceName: str = ...,
+        Tags: Sequence[TagTypeDef] = ...
+    ) -> StartSingleWirelessDeviceImportTaskResponseTypeDef:
+        """
+        Start import task for a single wireless device.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.start_single_wireless_device_import_task)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#start_single_wireless_device_import_task)
+        """
+
+    async def start_wireless_device_import_task(
+        self,
+        *,
+        DestinationName: str,
+        Sidewalk: SidewalkStartImportInfoTypeDef,
+        ClientRequestToken: str = ...,
+        Tags: Sequence[TagTypeDef] = ...
+    ) -> StartWirelessDeviceImportTaskResponseTypeDef:
+        """
+        Start import task for provisioning Sidewalk devices in bulk using an S3 CSV
+        file.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.start_wireless_device_import_task)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#start_wireless_device_import_task)
+        """
+
     async def tag_resource(self, *, ResourceArn: str, Tags: Sequence[TagTypeDef]) -> Dict[str, Any]:
         """
         Adds a tag to a resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#tag_resource)
         """
 
     async def test_wireless_device(self, *, Id: str) -> TestWirelessDeviceResponseTypeDef:
         """
-        Simulates a provisioned device by sending an uplink data payload of `Hello` .
+        Simulates a provisioned device by sending an uplink data payload of `Hello`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.test_wireless_device)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#test_wireless_device)
         """
 
     async def untag_resource(self, *, ResourceArn: str, TagKeys: Sequence[str]) -> Dict[str, Any]:
         """
@@ -1197,15 +1304,18 @@
         self,
         *,
         Id: str,
         Name: str = ...,
         Description: str = ...,
         LoRaWAN: LoRaWANFuotaTaskTypeDef = ...,
         FirmwareUpdateImage: str = ...,
-        FirmwareUpdateRole: str = ...
+        FirmwareUpdateRole: str = ...,
+        RedundancyPercent: int = ...,
+        FragmentSizeBytes: int = ...,
+        FragmentIntervalMS: int = ...
     ) -> Dict[str, Any]:
         """
         Updates properties of a FUOTA task.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.update_fuota_task)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#update_fuota_task)
         """
@@ -1244,15 +1354,17 @@
         *,
         ConfigurationName: str,
         TraceContent: TraceContentTypeDef = ...,
         WirelessDevicesToAdd: Sequence[str] = ...,
         WirelessDevicesToRemove: Sequence[str] = ...,
         WirelessGatewaysToAdd: Sequence[str] = ...,
         WirelessGatewaysToRemove: Sequence[str] = ...,
-        Description: str = ...
+        Description: str = ...,
+        MulticastGroupsToAdd: Sequence[str] = ...,
+        MulticastGroupsToRemove: Sequence[str] = ...
     ) -> Dict[str, Any]:
         """
         Update network analyzer configuration.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.update_network_analyzer_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#update_network_analyzer_configuration)
         """
@@ -1332,22 +1444,33 @@
         """
         Updates properties of a wireless device.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.update_wireless_device)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#update_wireless_device)
         """
 
+    async def update_wireless_device_import_task(
+        self, *, Id: str, Sidewalk: SidewalkUpdateImportInfoTypeDef
+    ) -> Dict[str, Any]:
+        """
+        Update an import task to add more devices to the task.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.update_wireless_device_import_task)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#update_wireless_device_import_task)
+        """
+
     async def update_wireless_gateway(
         self,
         *,
         Id: str,
         Name: str = ...,
         Description: str = ...,
         JoinEuiFilters: Sequence[Sequence[str]] = ...,
-        NetIdFilters: Sequence[str] = ...
+        NetIdFilters: Sequence[str] = ...,
+        MaxEirp: float = ...
     ) -> Dict[str, Any]:
         """
         Updates properties of a wireless gateway.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.update_wireless_gateway)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#update_wireless_gateway)
         """
```

### Comparing `types-aiobotocore-iotwireless-2.5.0.post1/types_aiobotocore_iotwireless/client.pyi` & `types-aiobotocore-iotwireless-2.5.1/types_aiobotocore_iotwireless/client.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -19,18 +19,20 @@
 from typing import IO, Any, Dict, Mapping, Sequence, Type, Union
 
 from aiobotocore.client import AioBaseClient
 from aiobotocore.response import StreamingBody
 from botocore.client import ClientMeta
 
 from .literals import (
+    DeviceProfileTypeType,
     EventNotificationResourceTypeType,
     ExpressionTypeType,
     IdentifierTypeType,
     LogLevelType,
+    OnboardStatusType,
     PositioningConfigStatusType,
     PositionResourceTypeType,
     WirelessDeviceIdTypeType,
     WirelessDeviceTypeType,
     WirelessGatewayIdTypeType,
     WirelessGatewayServiceTypeType,
 )
@@ -65,38 +67,41 @@
     GetPositionEstimateResponseTypeDef,
     GetPositionResponseTypeDef,
     GetResourceEventConfigurationResponseTypeDef,
     GetResourceLogLevelResponseTypeDef,
     GetResourcePositionResponseTypeDef,
     GetServiceEndpointResponseTypeDef,
     GetServiceProfileResponseTypeDef,
+    GetWirelessDeviceImportTaskResponseTypeDef,
     GetWirelessDeviceResponseTypeDef,
     GetWirelessDeviceStatisticsResponseTypeDef,
     GetWirelessGatewayCertificateResponseTypeDef,
     GetWirelessGatewayFirmwareInformationResponseTypeDef,
     GetWirelessGatewayResponseTypeDef,
     GetWirelessGatewayStatisticsResponseTypeDef,
     GetWirelessGatewayTaskDefinitionResponseTypeDef,
     GetWirelessGatewayTaskResponseTypeDef,
     GnssTypeDef,
     IpTypeDef,
     JoinEventConfigurationTypeDef,
     JoinResourceTypeEventConfigurationTypeDef,
     ListDestinationsResponseTypeDef,
     ListDeviceProfilesResponseTypeDef,
+    ListDevicesForWirelessDeviceImportTaskResponseTypeDef,
     ListEventConfigurationsResponseTypeDef,
     ListFuotaTasksResponseTypeDef,
     ListMulticastGroupsByFuotaTaskResponseTypeDef,
     ListMulticastGroupsResponseTypeDef,
     ListNetworkAnalyzerConfigurationsResponseTypeDef,
     ListPartnerAccountsResponseTypeDef,
     ListPositionConfigurationsResponseTypeDef,
     ListQueuedMessagesResponseTypeDef,
     ListServiceProfilesResponseTypeDef,
     ListTagsForResourceResponseTypeDef,
+    ListWirelessDeviceImportTasksResponseTypeDef,
     ListWirelessDevicesResponseTypeDef,
     ListWirelessGatewaysResponseTypeDef,
     ListWirelessGatewayTaskDefinitionsResponseTypeDef,
     LoRaWANDeviceProfileTypeDef,
     LoRaWANDeviceTypeDef,
     LoRaWANFuotaTaskTypeDef,
     LoRaWANGatewayTypeDef,
@@ -110,15 +115,21 @@
     MulticastWirelessMetadataTypeDef,
     PositionSolverConfigurationsTypeDef,
     ProximityEventConfigurationTypeDef,
     ProximityResourceTypeEventConfigurationTypeDef,
     SendDataToMulticastGroupResponseTypeDef,
     SendDataToWirelessDeviceResponseTypeDef,
     SidewalkAccountInfoTypeDef,
+    SidewalkCreateWirelessDeviceTypeDef,
+    SidewalkSingleStartImportInfoTypeDef,
+    SidewalkStartImportInfoTypeDef,
     SidewalkUpdateAccountTypeDef,
+    SidewalkUpdateImportInfoTypeDef,
+    StartSingleWirelessDeviceImportTaskResponseTypeDef,
+    StartWirelessDeviceImportTaskResponseTypeDef,
     TagTypeDef,
     TestWirelessDeviceResponseTypeDef,
     TraceContentTypeDef,
     UpdateWirelessGatewayTaskCreateTypeDef,
     WiFiAccessPointTypeDef,
     WirelessDeviceLogOptionTypeDef,
     WirelessGatewayLogOptionTypeDef,
@@ -272,15 +283,16 @@
         """
     async def create_device_profile(
         self,
         *,
         Name: str = ...,
         LoRaWAN: LoRaWANDeviceProfileTypeDef = ...,
         Tags: Sequence[TagTypeDef] = ...,
-        ClientRequestToken: str = ...
+        ClientRequestToken: str = ...,
+        Sidewalk: Mapping[str, Any] = ...
     ) -> CreateDeviceProfileResponseTypeDef:
         """
         Creates a new device profile.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.create_device_profile)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#create_device_profile)
         """
@@ -289,15 +301,18 @@
         *,
         FirmwareUpdateImage: str,
         FirmwareUpdateRole: str,
         Name: str = ...,
         Description: str = ...,
         ClientRequestToken: str = ...,
         LoRaWAN: LoRaWANFuotaTaskTypeDef = ...,
-        Tags: Sequence[TagTypeDef] = ...
+        Tags: Sequence[TagTypeDef] = ...,
+        RedundancyPercent: int = ...,
+        FragmentSizeBytes: int = ...,
+        FragmentIntervalMS: int = ...
     ) -> CreateFuotaTaskResponseTypeDef:
         """
         Creates a FUOTA task.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.create_fuota_task)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#create_fuota_task)
         """
@@ -321,15 +336,16 @@
         *,
         Name: str,
         TraceContent: TraceContentTypeDef = ...,
         WirelessDevices: Sequence[str] = ...,
         WirelessGateways: Sequence[str] = ...,
         Description: str = ...,
         Tags: Sequence[TagTypeDef] = ...,
-        ClientRequestToken: str = ...
+        ClientRequestToken: str = ...,
+        MulticastGroups: Sequence[str] = ...
     ) -> CreateNetworkAnalyzerConfigurationResponseTypeDef:
         """
         Creates a new network analyzer configuration.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.create_network_analyzer_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#create_network_analyzer_configuration)
         """
@@ -353,15 +369,16 @@
         Type: WirelessDeviceTypeType,
         DestinationName: str,
         Name: str = ...,
         Description: str = ...,
         ClientRequestToken: str = ...,
         LoRaWAN: LoRaWANDeviceTypeDef = ...,
         Tags: Sequence[TagTypeDef] = ...,
-        Positioning: PositioningConfigStatusType = ...
+        Positioning: PositioningConfigStatusType = ...,
+        Sidewalk: SidewalkCreateWirelessDeviceTypeDef = ...
     ) -> CreateWirelessDeviceResponseTypeDef:
         """
         Provisions a wireless device.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.create_wireless_device)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#create_wireless_device)
         """
@@ -460,14 +477,21 @@
     async def delete_wireless_device(self, *, Id: str) -> Dict[str, Any]:
         """
         Deletes a wireless device.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.delete_wireless_device)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#delete_wireless_device)
         """
+    async def delete_wireless_device_import_task(self, *, Id: str) -> Dict[str, Any]:
+        """
+        Delete an import task.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.delete_wireless_device_import_task)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#delete_wireless_device_import_task)
+        """
     async def delete_wireless_gateway(self, *, Id: str) -> Dict[str, Any]:
         """
         Deletes a wireless gateway.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.delete_wireless_gateway)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#delete_wireless_gateway)
         """
@@ -481,14 +505,23 @@
     async def delete_wireless_gateway_task_definition(self, *, Id: str) -> Dict[str, Any]:
         """
         Deletes a wireless gateway task definition.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.delete_wireless_gateway_task_definition)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#delete_wireless_gateway_task_definition)
         """
+    async def deregister_wireless_device(
+        self, *, Identifier: str, WirelessDeviceType: WirelessDeviceTypeType = ...
+    ) -> Dict[str, Any]:
+        """
+        Deregister a wireless device from AWS IoT Wireless.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.deregister_wireless_device)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#deregister_wireless_device)
+        """
     async def disassociate_aws_account_from_partner_account(
         self, *, PartnerAccountId: str, PartnerType: Literal["Sidewalk"]
     ) -> Dict[str, Any]:
         """
         Disassociates your AWS account from a partner account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.disassociate_aws_account_from_partner_account)
@@ -714,14 +747,24 @@
     ) -> GetWirelessDeviceResponseTypeDef:
         """
         Gets information about a wireless device.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.get_wireless_device)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#get_wireless_device)
         """
+    async def get_wireless_device_import_task(
+        self, *, Id: str
+    ) -> GetWirelessDeviceImportTaskResponseTypeDef:
+        """
+        Get information about an import task and count of device onboarding summary
+        information for the import task.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.get_wireless_device_import_task)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#get_wireless_device_import_task)
+        """
     async def get_wireless_device_statistics(
         self, *, WirelessDeviceId: str
     ) -> GetWirelessDeviceStatisticsResponseTypeDef:
         """
         Gets operating information about a wireless device.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.get_wireless_device_statistics)
@@ -786,22 +829,40 @@
         """
         Lists the destinations registered to your AWS account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.list_destinations)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#list_destinations)
         """
     async def list_device_profiles(
-        self, *, NextToken: str = ..., MaxResults: int = ...
+        self,
+        *,
+        NextToken: str = ...,
+        MaxResults: int = ...,
+        DeviceProfileType: DeviceProfileTypeType = ...
     ) -> ListDeviceProfilesResponseTypeDef:
         """
         Lists the device profiles registered to your AWS account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.list_device_profiles)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#list_device_profiles)
         """
+    async def list_devices_for_wireless_device_import_task(
+        self,
+        *,
+        Id: str,
+        MaxResults: int = ...,
+        NextToken: str = ...,
+        Status: OnboardStatusType = ...
+    ) -> ListDevicesForWirelessDeviceImportTaskResponseTypeDef:
+        """
+        List the Sidewalk devices in an import task and their onboarding status.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.list_devices_for_wireless_device_import_task)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#list_devices_for_wireless_device_import_task)
+        """
     async def list_event_configurations(
         self,
         *,
         ResourceType: EventNotificationResourceTypeType,
         MaxResults: int = ...,
         NextToken: str = ...
     ) -> ListEventConfigurationsResponseTypeDef:
@@ -897,14 +958,23 @@
     ) -> ListTagsForResourceResponseTypeDef:
         """
         Lists the tags (metadata) you have assigned to the resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#list_tags_for_resource)
         """
+    async def list_wireless_device_import_tasks(
+        self, *, MaxResults: int = ..., NextToken: str = ...
+    ) -> ListWirelessDeviceImportTasksResponseTypeDef:
+        """
+        List wireless devices that have been added to an import task.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.list_wireless_device_import_tasks)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#list_wireless_device_import_tasks)
+        """
     async def list_wireless_devices(
         self,
         *,
         MaxResults: int = ...,
         NextToken: str = ...,
         DestinationName: str = ...,
         DeviceProfileId: str = ...,
@@ -1039,24 +1109,54 @@
     ) -> Dict[str, Any]:
         """
         Starts a multicast group session.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.start_multicast_group_session)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#start_multicast_group_session)
         """
+    async def start_single_wireless_device_import_task(
+        self,
+        *,
+        DestinationName: str,
+        Sidewalk: SidewalkSingleStartImportInfoTypeDef,
+        ClientRequestToken: str = ...,
+        DeviceName: str = ...,
+        Tags: Sequence[TagTypeDef] = ...
+    ) -> StartSingleWirelessDeviceImportTaskResponseTypeDef:
+        """
+        Start import task for a single wireless device.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.start_single_wireless_device_import_task)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#start_single_wireless_device_import_task)
+        """
+    async def start_wireless_device_import_task(
+        self,
+        *,
+        DestinationName: str,
+        Sidewalk: SidewalkStartImportInfoTypeDef,
+        ClientRequestToken: str = ...,
+        Tags: Sequence[TagTypeDef] = ...
+    ) -> StartWirelessDeviceImportTaskResponseTypeDef:
+        """
+        Start import task for provisioning Sidewalk devices in bulk using an S3 CSV
+        file.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.start_wireless_device_import_task)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#start_wireless_device_import_task)
+        """
     async def tag_resource(self, *, ResourceArn: str, Tags: Sequence[TagTypeDef]) -> Dict[str, Any]:
         """
         Adds a tag to a resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#tag_resource)
         """
     async def test_wireless_device(self, *, Id: str) -> TestWirelessDeviceResponseTypeDef:
         """
-        Simulates a provisioned device by sending an uplink data payload of `Hello` .
+        Simulates a provisioned device by sending an uplink data payload of `Hello`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.test_wireless_device)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#test_wireless_device)
         """
     async def untag_resource(self, *, ResourceArn: str, TagKeys: Sequence[str]) -> Dict[str, Any]:
         """
         Removes one or more tags from a resource.
@@ -1098,15 +1198,18 @@
         self,
         *,
         Id: str,
         Name: str = ...,
         Description: str = ...,
         LoRaWAN: LoRaWANFuotaTaskTypeDef = ...,
         FirmwareUpdateImage: str = ...,
-        FirmwareUpdateRole: str = ...
+        FirmwareUpdateRole: str = ...,
+        RedundancyPercent: int = ...,
+        FragmentSizeBytes: int = ...,
+        FragmentIntervalMS: int = ...
     ) -> Dict[str, Any]:
         """
         Updates properties of a FUOTA task.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.update_fuota_task)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#update_fuota_task)
         """
@@ -1142,15 +1245,17 @@
         *,
         ConfigurationName: str,
         TraceContent: TraceContentTypeDef = ...,
         WirelessDevicesToAdd: Sequence[str] = ...,
         WirelessDevicesToRemove: Sequence[str] = ...,
         WirelessGatewaysToAdd: Sequence[str] = ...,
         WirelessGatewaysToRemove: Sequence[str] = ...,
-        Description: str = ...
+        Description: str = ...,
+        MulticastGroupsToAdd: Sequence[str] = ...,
+        MulticastGroupsToRemove: Sequence[str] = ...
     ) -> Dict[str, Any]:
         """
         Update network analyzer configuration.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.update_network_analyzer_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#update_network_analyzer_configuration)
         """
@@ -1224,22 +1329,32 @@
     ) -> Dict[str, Any]:
         """
         Updates properties of a wireless device.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.update_wireless_device)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#update_wireless_device)
         """
+    async def update_wireless_device_import_task(
+        self, *, Id: str, Sidewalk: SidewalkUpdateImportInfoTypeDef
+    ) -> Dict[str, Any]:
+        """
+        Update an import task to add more devices to the task.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.update_wireless_device_import_task)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#update_wireless_device_import_task)
+        """
     async def update_wireless_gateway(
         self,
         *,
         Id: str,
         Name: str = ...,
         Description: str = ...,
         JoinEuiFilters: Sequence[Sequence[str]] = ...,
-        NetIdFilters: Sequence[str] = ...
+        NetIdFilters: Sequence[str] = ...,
+        MaxEirp: float = ...
     ) -> Dict[str, Any]:
         """
         Updates properties of a wireless gateway.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless.Client.update_wireless_gateway)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/client/#update_wireless_gateway)
         """
```

### Comparing `types-aiobotocore-iotwireless-2.5.0.post1/types_aiobotocore_iotwireless/literals.py` & `types-aiobotocore-iotwireless-2.5.1/types_aiobotocore_iotwireless/literals.py`

 * *Files 7% similar despite different names*

```diff
@@ -19,39 +19,44 @@
     from typing_extensions import Literal
 
 
 __all__ = (
     "ApplicationConfigTypeType",
     "BatteryLevelType",
     "ConnectionStatusType",
+    "DeviceProfileTypeType",
     "DeviceStateType",
     "DlClassType",
     "DownlinkModeType",
     "EventNotificationPartnerTypeType",
     "EventNotificationResourceTypeType",
     "EventNotificationTopicStatusType",
     "EventType",
     "ExpressionTypeType",
     "FuotaDeviceStatusType",
     "FuotaTaskStatusType",
     "IdentifierTypeType",
+    "ImportTaskStatusType",
     "LogLevelType",
     "MessageTypeType",
+    "MulticastFrameInfoType",
+    "OnboardStatusType",
     "PartnerTypeType",
     "PositionConfigurationFecType",
     "PositionConfigurationStatusType",
     "PositionResourceTypeType",
     "PositionSolverProviderType",
     "PositionSolverTypeType",
     "PositioningConfigStatusType",
     "SigningAlgType",
     "SupportedRfRegionType",
     "WirelessDeviceEventType",
     "WirelessDeviceFrameInfoType",
     "WirelessDeviceIdTypeType",
+    "WirelessDeviceSidewalkStatusType",
     "WirelessDeviceTypeType",
     "WirelessGatewayEventType",
     "WirelessGatewayIdTypeType",
     "WirelessGatewayServiceTypeType",
     "WirelessGatewayTaskDefinitionTypeType",
     "WirelessGatewayTaskStatusType",
     "WirelessGatewayTypeType",
@@ -61,14 +66,15 @@
     "RegionName",
 )
 
 
 ApplicationConfigTypeType = Literal["SemtechGeolocation"]
 BatteryLevelType = Literal["critical", "low", "normal"]
 ConnectionStatusType = Literal["Connected", "Disconnected"]
+DeviceProfileTypeType = Literal["LoRaWAN", "Sidewalk"]
 DeviceStateType = Literal[
     "Provisioned", "RegisteredNotSeen", "RegisteredReachable", "RegisteredUnreachable"
 ]
 DlClassType = Literal["ClassB", "ClassC"]
 DownlinkModeType = Literal["CONCURRENT", "SEQUENTIAL", "USING_UPLINK_GATEWAY"]
 EventNotificationPartnerTypeType = Literal["Sidewalk"]
 EventNotificationResourceTypeType = Literal["SidewalkAccount", "WirelessDevice", "WirelessGateway"]
@@ -90,35 +96,55 @@
 ]
 FuotaTaskStatusType = Literal[
     "Delete_Waiting", "FuotaDone", "FuotaSession_Waiting", "In_FuotaSession", "Pending"
 ]
 IdentifierTypeType = Literal[
     "DevEui", "GatewayEui", "PartnerAccountId", "WirelessDeviceId", "WirelessGatewayId"
 ]
+ImportTaskStatusType = Literal[
+    "COMPLETE", "DELETING", "FAILED", "INITIALIZED", "INITIALIZING", "PENDING"
+]
 LogLevelType = Literal["DISABLED", "ERROR", "INFO"]
 MessageTypeType = Literal[
     "CUSTOM_COMMAND_ID_GET",
     "CUSTOM_COMMAND_ID_NOTIFY",
     "CUSTOM_COMMAND_ID_RESP",
     "CUSTOM_COMMAND_ID_SET",
 ]
+MulticastFrameInfoType = Literal["DISABLED", "ENABLED"]
+OnboardStatusType = Literal["FAILED", "INITIALIZED", "ONBOARDED", "PENDING"]
 PartnerTypeType = Literal["Sidewalk"]
 PositionConfigurationFecType = Literal["NONE", "ROSE"]
 PositionConfigurationStatusType = Literal["Disabled", "Enabled"]
 PositionResourceTypeType = Literal["WirelessDevice", "WirelessGateway"]
 PositionSolverProviderType = Literal["Semtech"]
 PositionSolverTypeType = Literal["GNSS"]
 PositioningConfigStatusType = Literal["Disabled", "Enabled"]
 SigningAlgType = Literal["Ed25519", "P256r1"]
-SupportedRfRegionType = Literal["AS923-1", "AU915", "EU868", "US915"]
+SupportedRfRegionType = Literal[
+    "AS923-1",
+    "AS923-2",
+    "AS923-3",
+    "AS923-4",
+    "AU915",
+    "CN470",
+    "CN779",
+    "EU433",
+    "EU868",
+    "IN865",
+    "KR920",
+    "RU864",
+    "US915",
+]
 WirelessDeviceEventType = Literal["Downlink_Data", "Join", "Registration", "Rejoin", "Uplink_Data"]
 WirelessDeviceFrameInfoType = Literal["DISABLED", "ENABLED"]
 WirelessDeviceIdTypeType = Literal[
     "DevEui", "SidewalkManufacturingSn", "ThingName", "WirelessDeviceId"
 ]
+WirelessDeviceSidewalkStatusType = Literal["ACTIVATED", "PROVISIONED", "REGISTERED", "UNKNOWN"]
 WirelessDeviceTypeType = Literal["LoRaWAN", "Sidewalk"]
 WirelessGatewayEventType = Literal["CUPS_Request", "Certificate"]
 WirelessGatewayIdTypeType = Literal["GatewayEui", "ThingName", "WirelessGatewayId"]
 WirelessGatewayServiceTypeType = Literal["CUPS", "LNS"]
 WirelessGatewayTaskDefinitionTypeType = Literal["UPDATE"]
 WirelessGatewayTaskStatusType = Literal[
     "COMPLETED", "FAILED", "FIRST_RETRY", "IN_PROGRESS", "PENDING", "SECOND_RETRY"
@@ -183,14 +209,15 @@
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
@@ -269,14 +296,15 @@
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
@@ -287,14 +315,15 @@
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
@@ -330,14 +359,15 @@
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
@@ -356,16 +386,19 @@
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
@@ -449,15 +482,17 @@
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

### Comparing `types-aiobotocore-iotwireless-2.5.0.post1/types_aiobotocore_iotwireless/literals.pyi` & `types-aiobotocore-iotwireless-2.5.1/types_aiobotocore_iotwireless/literals.pyi`

 * *Files 7% similar despite different names*

```diff
@@ -18,39 +18,44 @@
 else:
     from typing_extensions import Literal
 
 __all__ = (
     "ApplicationConfigTypeType",
     "BatteryLevelType",
     "ConnectionStatusType",
+    "DeviceProfileTypeType",
     "DeviceStateType",
     "DlClassType",
     "DownlinkModeType",
     "EventNotificationPartnerTypeType",
     "EventNotificationResourceTypeType",
     "EventNotificationTopicStatusType",
     "EventType",
     "ExpressionTypeType",
     "FuotaDeviceStatusType",
     "FuotaTaskStatusType",
     "IdentifierTypeType",
+    "ImportTaskStatusType",
     "LogLevelType",
     "MessageTypeType",
+    "MulticastFrameInfoType",
+    "OnboardStatusType",
     "PartnerTypeType",
     "PositionConfigurationFecType",
     "PositionConfigurationStatusType",
     "PositionResourceTypeType",
     "PositionSolverProviderType",
     "PositionSolverTypeType",
     "PositioningConfigStatusType",
     "SigningAlgType",
     "SupportedRfRegionType",
     "WirelessDeviceEventType",
     "WirelessDeviceFrameInfoType",
     "WirelessDeviceIdTypeType",
+    "WirelessDeviceSidewalkStatusType",
     "WirelessDeviceTypeType",
     "WirelessGatewayEventType",
     "WirelessGatewayIdTypeType",
     "WirelessGatewayServiceTypeType",
     "WirelessGatewayTaskDefinitionTypeType",
     "WirelessGatewayTaskStatusType",
     "WirelessGatewayTypeType",
@@ -59,14 +64,15 @@
     "ResourceServiceName",
     "RegionName",
 )
 
 ApplicationConfigTypeType = Literal["SemtechGeolocation"]
 BatteryLevelType = Literal["critical", "low", "normal"]
 ConnectionStatusType = Literal["Connected", "Disconnected"]
+DeviceProfileTypeType = Literal["LoRaWAN", "Sidewalk"]
 DeviceStateType = Literal[
     "Provisioned", "RegisteredNotSeen", "RegisteredReachable", "RegisteredUnreachable"
 ]
 DlClassType = Literal["ClassB", "ClassC"]
 DownlinkModeType = Literal["CONCURRENT", "SEQUENTIAL", "USING_UPLINK_GATEWAY"]
 EventNotificationPartnerTypeType = Literal["Sidewalk"]
 EventNotificationResourceTypeType = Literal["SidewalkAccount", "WirelessDevice", "WirelessGateway"]
@@ -88,35 +94,55 @@
 ]
 FuotaTaskStatusType = Literal[
     "Delete_Waiting", "FuotaDone", "FuotaSession_Waiting", "In_FuotaSession", "Pending"
 ]
 IdentifierTypeType = Literal[
     "DevEui", "GatewayEui", "PartnerAccountId", "WirelessDeviceId", "WirelessGatewayId"
 ]
+ImportTaskStatusType = Literal[
+    "COMPLETE", "DELETING", "FAILED", "INITIALIZED", "INITIALIZING", "PENDING"
+]
 LogLevelType = Literal["DISABLED", "ERROR", "INFO"]
 MessageTypeType = Literal[
     "CUSTOM_COMMAND_ID_GET",
     "CUSTOM_COMMAND_ID_NOTIFY",
     "CUSTOM_COMMAND_ID_RESP",
     "CUSTOM_COMMAND_ID_SET",
 ]
+MulticastFrameInfoType = Literal["DISABLED", "ENABLED"]
+OnboardStatusType = Literal["FAILED", "INITIALIZED", "ONBOARDED", "PENDING"]
 PartnerTypeType = Literal["Sidewalk"]
 PositionConfigurationFecType = Literal["NONE", "ROSE"]
 PositionConfigurationStatusType = Literal["Disabled", "Enabled"]
 PositionResourceTypeType = Literal["WirelessDevice", "WirelessGateway"]
 PositionSolverProviderType = Literal["Semtech"]
 PositionSolverTypeType = Literal["GNSS"]
 PositioningConfigStatusType = Literal["Disabled", "Enabled"]
 SigningAlgType = Literal["Ed25519", "P256r1"]
-SupportedRfRegionType = Literal["AS923-1", "AU915", "EU868", "US915"]
+SupportedRfRegionType = Literal[
+    "AS923-1",
+    "AS923-2",
+    "AS923-3",
+    "AS923-4",
+    "AU915",
+    "CN470",
+    "CN779",
+    "EU433",
+    "EU868",
+    "IN865",
+    "KR920",
+    "RU864",
+    "US915",
+]
 WirelessDeviceEventType = Literal["Downlink_Data", "Join", "Registration", "Rejoin", "Uplink_Data"]
 WirelessDeviceFrameInfoType = Literal["DISABLED", "ENABLED"]
 WirelessDeviceIdTypeType = Literal[
     "DevEui", "SidewalkManufacturingSn", "ThingName", "WirelessDeviceId"
 ]
+WirelessDeviceSidewalkStatusType = Literal["ACTIVATED", "PROVISIONED", "REGISTERED", "UNKNOWN"]
 WirelessDeviceTypeType = Literal["LoRaWAN", "Sidewalk"]
 WirelessGatewayEventType = Literal["CUPS_Request", "Certificate"]
 WirelessGatewayIdTypeType = Literal["GatewayEui", "ThingName", "WirelessGatewayId"]
 WirelessGatewayServiceTypeType = Literal["CUPS", "LNS"]
 WirelessGatewayTaskDefinitionTypeType = Literal["UPDATE"]
 WirelessGatewayTaskStatusType = Literal[
     "COMPLETED", "FAILED", "FIRST_RETRY", "IN_PROGRESS", "PENDING", "SECOND_RETRY"
@@ -181,14 +207,15 @@
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
@@ -267,14 +294,15 @@
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
@@ -285,14 +313,15 @@
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
@@ -328,14 +357,15 @@
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
@@ -354,16 +384,19 @@
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
@@ -447,15 +480,17 @@
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

### Comparing `types-aiobotocore-iotwireless-2.5.0.post1/types_aiobotocore_iotwireless/type_defs.py` & `types-aiobotocore-iotwireless-2.5.1/types_aiobotocore_iotwireless/type_defs.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -2,49 +2,54 @@
 Type annotations for iotwireless service type definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/type_defs/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_iotwireless.type_defs import SessionKeysAbpV1_0_xTypeDef
+    from types_aiobotocore_iotwireless.type_defs import SessionKeysAbpV10XTypeDef
 
-    data: SessionKeysAbpV1_0_xTypeDef = {...}
+    data: SessionKeysAbpV10XTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
-from typing import IO, Any, Dict, List, Sequence, Union
+from typing import IO, Any, Dict, List, Mapping, Sequence, Union
 
 from aiobotocore.response import StreamingBody
 
 from .literals import (
     BatteryLevelType,
     ConnectionStatusType,
+    DeviceProfileTypeType,
     DeviceStateType,
     DlClassType,
     DownlinkModeType,
     EventNotificationResourceTypeType,
     EventNotificationTopicStatusType,
     EventType,
     ExpressionTypeType,
     FuotaDeviceStatusType,
     FuotaTaskStatusType,
     IdentifierTypeType,
+    ImportTaskStatusType,
     LogLevelType,
     MessageTypeType,
+    MulticastFrameInfoType,
+    OnboardStatusType,
     PositionConfigurationFecType,
     PositionConfigurationStatusType,
     PositioningConfigStatusType,
     PositionResourceTypeType,
     SigningAlgType,
     SupportedRfRegionType,
     WirelessDeviceEventType,
     WirelessDeviceFrameInfoType,
     WirelessDeviceIdTypeType,
+    WirelessDeviceSidewalkStatusType,
     WirelessDeviceTypeType,
     WirelessGatewayEventType,
     WirelessGatewayIdTypeType,
     WirelessGatewayServiceTypeType,
     WirelessGatewayTaskStatusType,
 )
 
@@ -53,53 +58,66 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
-    "SessionKeysAbpV1_0_xTypeDef",
-    "SessionKeysAbpV1_1TypeDef",
+    "SessionKeysAbpV10XTypeDef",
+    "SessionKeysAbpV11TypeDef",
     "AccuracyTypeDef",
     "ApplicationConfigTypeDef",
     "SidewalkAccountInfoTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
     "AssociateMulticastGroupWithFuotaTaskRequestRequestTypeDef",
     "AssociateWirelessDeviceWithFuotaTaskRequestRequestTypeDef",
     "AssociateWirelessDeviceWithMulticastGroupRequestRequestTypeDef",
     "AssociateWirelessDeviceWithThingRequestRequestTypeDef",
     "AssociateWirelessGatewayWithCertificateRequestRequestTypeDef",
+    "AssociateWirelessGatewayWithCertificateResponseTypeDef",
     "AssociateWirelessGatewayWithThingRequestRequestTypeDef",
     "BeaconingTypeDef",
     "CancelMulticastGroupSessionRequestRequestTypeDef",
     "CdmaLocalIdTypeDef",
     "CdmaNmrObjTypeDef",
     "CertificateListTypeDef",
     "LoRaWANConnectionStatusEventNotificationConfigurationsTypeDef",
     "LoRaWANConnectionStatusResourceTypeEventConfigurationTypeDef",
+    "CreateDestinationResponseTypeDef",
     "LoRaWANDeviceProfileTypeDef",
+    "CreateDeviceProfileResponseTypeDef",
     "LoRaWANFuotaTaskTypeDef",
+    "CreateFuotaTaskResponseTypeDef",
     "LoRaWANMulticastTypeDef",
+    "CreateMulticastGroupResponseTypeDef",
     "TraceContentTypeDef",
+    "CreateNetworkAnalyzerConfigurationResponseTypeDef",
     "LoRaWANServiceProfileTypeDef",
+    "CreateServiceProfileResponseTypeDef",
+    "SidewalkCreateWirelessDeviceTypeDef",
+    "CreateWirelessDeviceResponseTypeDef",
+    "CreateWirelessGatewayResponseTypeDef",
+    "CreateWirelessGatewayTaskDefinitionResponseTypeDef",
     "CreateWirelessGatewayTaskRequestRequestTypeDef",
+    "CreateWirelessGatewayTaskResponseTypeDef",
+    "DakCertificateMetadataTypeDef",
     "DeleteDestinationRequestRequestTypeDef",
     "DeleteDeviceProfileRequestRequestTypeDef",
     "DeleteFuotaTaskRequestRequestTypeDef",
     "DeleteMulticastGroupRequestRequestTypeDef",
     "DeleteNetworkAnalyzerConfigurationRequestRequestTypeDef",
     "DeleteQueuedMessagesRequestRequestTypeDef",
     "DeleteServiceProfileRequestRequestTypeDef",
+    "DeleteWirelessDeviceImportTaskRequestRequestTypeDef",
     "DeleteWirelessDeviceRequestRequestTypeDef",
     "DeleteWirelessGatewayRequestRequestTypeDef",
     "DeleteWirelessGatewayTaskDefinitionRequestRequestTypeDef",
     "DeleteWirelessGatewayTaskRequestRequestTypeDef",
+    "DeregisterWirelessDeviceRequestRequestTypeDef",
     "DestinationsTypeDef",
     "DeviceProfileTypeDef",
     "SidewalkEventNotificationConfigurationsTypeDef",
     "SidewalkResourceTypeEventConfigurationTypeDef",
     "DisassociateAwsAccountFromPartnerAccountRequestRequestTypeDef",
     "DisassociateMulticastGroupFromFuotaTaskRequestRequestTypeDef",
     "DisassociateWirelessDeviceFromFuotaTaskRequestRequestTypeDef",
@@ -107,144 +125,144 @@
     "DisassociateWirelessDeviceFromThingRequestRequestTypeDef",
     "DisassociateWirelessGatewayFromCertificateRequestRequestTypeDef",
     "DisassociateWirelessGatewayFromThingRequestRequestTypeDef",
     "PositioningTypeDef",
     "FuotaTaskTypeDef",
     "GatewayListItemTypeDef",
     "GetDestinationRequestRequestTypeDef",
+    "GetDestinationResponseTypeDef",
     "GetDeviceProfileRequestRequestTypeDef",
     "GetFuotaTaskRequestRequestTypeDef",
     "LoRaWANFuotaTaskGetInfoTypeDef",
     "GetMulticastGroupRequestRequestTypeDef",
     "LoRaWANMulticastGetTypeDef",
     "GetMulticastGroupSessionRequestRequestTypeDef",
     "LoRaWANMulticastSessionTypeDef",
     "GetNetworkAnalyzerConfigurationRequestRequestTypeDef",
     "GetPartnerAccountRequestRequestTypeDef",
     "SidewalkAccountInfoWithFingerprintTypeDef",
     "GetPositionConfigurationRequestRequestTypeDef",
     "GnssTypeDef",
     "IpTypeDef",
     "WiFiAccessPointTypeDef",
+    "GetPositionEstimateResponseTypeDef",
     "GetPositionRequestRequestTypeDef",
     "GetResourceEventConfigurationRequestRequestTypeDef",
     "GetResourceLogLevelRequestRequestTypeDef",
+    "GetResourceLogLevelResponseTypeDef",
     "GetResourcePositionRequestRequestTypeDef",
+    "GetResourcePositionResponseTypeDef",
     "GetServiceEndpointRequestRequestTypeDef",
+    "GetServiceEndpointResponseTypeDef",
     "GetServiceProfileRequestRequestTypeDef",
     "LoRaWANGetServiceProfileInfoTypeDef",
+    "GetWirelessDeviceImportTaskRequestRequestTypeDef",
+    "SidewalkGetStartImportInfoTypeDef",
     "GetWirelessDeviceRequestRequestTypeDef",
     "GetWirelessDeviceStatisticsRequestRequestTypeDef",
     "SidewalkDeviceMetadataTypeDef",
     "GetWirelessGatewayCertificateRequestRequestTypeDef",
+    "GetWirelessGatewayCertificateResponseTypeDef",
     "GetWirelessGatewayFirmwareInformationRequestRequestTypeDef",
     "GetWirelessGatewayRequestRequestTypeDef",
     "GetWirelessGatewayStatisticsRequestRequestTypeDef",
+    "GetWirelessGatewayStatisticsResponseTypeDef",
     "GetWirelessGatewayTaskDefinitionRequestRequestTypeDef",
     "GetWirelessGatewayTaskRequestRequestTypeDef",
+    "GetWirelessGatewayTaskResponseTypeDef",
     "GlobalIdentityTypeDef",
     "GsmLocalIdTypeDef",
+    "ImportedSidewalkDeviceTypeDef",
     "LoRaWANJoinEventNotificationConfigurationsTypeDef",
     "LoRaWANJoinResourceTypeEventConfigurationTypeDef",
     "ListDestinationsRequestRequestTypeDef",
     "ListDeviceProfilesRequestRequestTypeDef",
+    "ListDevicesForWirelessDeviceImportTaskRequestRequestTypeDef",
     "ListEventConfigurationsRequestRequestTypeDef",
     "ListFuotaTasksRequestRequestTypeDef",
     "ListMulticastGroupsByFuotaTaskRequestRequestTypeDef",
     "MulticastGroupByFuotaTaskTypeDef",
     "ListMulticastGroupsRequestRequestTypeDef",
     "MulticastGroupTypeDef",
     "ListNetworkAnalyzerConfigurationsRequestRequestTypeDef",
     "NetworkAnalyzerConfigurationsTypeDef",
     "ListPartnerAccountsRequestRequestTypeDef",
     "ListPositionConfigurationsRequestRequestTypeDef",
     "ListQueuedMessagesRequestRequestTypeDef",
     "ListServiceProfilesRequestRequestTypeDef",
     "ServiceProfileTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListWirelessDeviceImportTasksRequestRequestTypeDef",
     "ListWirelessDevicesRequestRequestTypeDef",
     "ListWirelessGatewayTaskDefinitionsRequestRequestTypeDef",
     "ListWirelessGatewaysRequestRequestTypeDef",
     "LoRaWANGatewayMetadataTypeDef",
-    "OtaaV1_0_xTypeDef",
-    "OtaaV1_1TypeDef",
+    "OtaaV10XTypeDef",
+    "OtaaV11TypeDef",
     "LoRaWANGatewayVersionTypeDef",
     "LoRaWANListDeviceTypeDef",
     "LoRaWANMulticastMetadataTypeDef",
     "LoRaWANStartFuotaTaskTypeDef",
-    "UpdateAbpV1_0_xTypeDef",
-    "UpdateAbpV1_1TypeDef",
+    "UpdateAbpV10XTypeDef",
+    "UpdateAbpV11TypeDef",
     "LteLocalIdTypeDef",
     "LteNmrObjTypeDef",
     "SemtechGnssConfigurationTypeDef",
     "SemtechGnssDetailTypeDef",
     "PutResourceLogLevelRequestRequestTypeDef",
     "ResetResourceLogLevelRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
+    "SendDataToMulticastGroupResponseTypeDef",
+    "SendDataToWirelessDeviceResponseTypeDef",
     "SidewalkSendDataToDeviceTypeDef",
+    "SidewalkSingleStartImportInfoTypeDef",
+    "SidewalkStartImportInfoTypeDef",
     "SidewalkUpdateAccountTypeDef",
+    "SidewalkUpdateImportInfoTypeDef",
+    "StartSingleWirelessDeviceImportTaskResponseTypeDef",
+    "StartWirelessDeviceImportTaskResponseTypeDef",
     "TdscdmaLocalIdTypeDef",
     "TdscdmaNmrObjTypeDef",
     "TestWirelessDeviceRequestRequestTypeDef",
+    "TestWirelessDeviceResponseTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateDestinationRequestRequestTypeDef",
     "UpdatePositionRequestRequestTypeDef",
     "UpdateResourcePositionRequestRequestTypeDef",
     "UpdateWirelessGatewayRequestRequestTypeDef",
     "WcdmaLocalIdTypeDef",
     "WcdmaNmrObjTypeDef",
     "WirelessDeviceEventLogOptionTypeDef",
     "WirelessGatewayEventLogOptionTypeDef",
-    "AbpV1_0_xTypeDef",
-    "AbpV1_1TypeDef",
+    "AbpV10XTypeDef",
+    "AbpV11TypeDef",
+    "GetPositionResponseTypeDef",
+    "AssociateAwsAccountWithPartnerAccountResponseTypeDef",
     "AssociateAwsAccountWithPartnerAccountRequestRequestTypeDef",
     "CreateDestinationRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "StartBulkAssociateWirelessDeviceWithMulticastGroupRequestRequestTypeDef",
     "StartBulkDisassociateWirelessDeviceFromMulticastGroupRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
-    "AssociateAwsAccountWithPartnerAccountResponseTypeDef",
-    "AssociateWirelessGatewayWithCertificateResponseTypeDef",
-    "CreateDestinationResponseTypeDef",
-    "CreateDeviceProfileResponseTypeDef",
-    "CreateFuotaTaskResponseTypeDef",
-    "CreateMulticastGroupResponseTypeDef",
-    "CreateNetworkAnalyzerConfigurationResponseTypeDef",
-    "CreateServiceProfileResponseTypeDef",
-    "CreateWirelessDeviceResponseTypeDef",
-    "CreateWirelessGatewayResponseTypeDef",
-    "CreateWirelessGatewayTaskDefinitionResponseTypeDef",
-    "CreateWirelessGatewayTaskResponseTypeDef",
-    "GetDestinationResponseTypeDef",
-    "GetPositionEstimateResponseTypeDef",
-    "GetPositionResponseTypeDef",
-    "GetResourceLogLevelResponseTypeDef",
-    "GetResourcePositionResponseTypeDef",
-    "GetServiceEndpointResponseTypeDef",
-    "GetWirelessGatewayCertificateResponseTypeDef",
-    "GetWirelessGatewayStatisticsResponseTypeDef",
-    "GetWirelessGatewayTaskResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "SendDataToMulticastGroupResponseTypeDef",
-    "SendDataToWirelessDeviceResponseTypeDef",
-    "TestWirelessDeviceResponseTypeDef",
     "LoRaWANGatewayTypeDef",
     "CdmaObjTypeDef",
     "SidewalkDeviceTypeDef",
     "SidewalkListDeviceTypeDef",
     "ConnectionStatusEventConfigurationTypeDef",
     "ConnectionStatusResourceTypeEventConfigurationTypeDef",
     "CreateDeviceProfileRequestRequestTypeDef",
-    "GetDeviceProfileResponseTypeDef",
     "CreateFuotaTaskRequestRequestTypeDef",
     "UpdateFuotaTaskRequestRequestTypeDef",
     "CreateMulticastGroupRequestRequestTypeDef",
     "UpdateMulticastGroupRequestRequestTypeDef",
     "CreateNetworkAnalyzerConfigurationRequestRequestTypeDef",
     "GetNetworkAnalyzerConfigurationResponseTypeDef",
     "UpdateNetworkAnalyzerConfigurationRequestRequestTypeDef",
     "CreateServiceProfileRequestRequestTypeDef",
+    "SidewalkGetDeviceProfileTypeDef",
     "ListDestinationsResponseTypeDef",
     "ListDeviceProfilesResponseTypeDef",
     "DeviceRegistrationStateEventConfigurationTypeDef",
     "MessageDeliveryStatusEventConfigurationTypeDef",
     "ProximityEventConfigurationTypeDef",
     "DeviceRegistrationStateResourceTypeEventConfigurationTypeDef",
     "MessageDeliveryStatusResourceTypeEventConfigurationTypeDef",
@@ -256,15 +274,18 @@
     "GetFuotaTaskResponseTypeDef",
     "GetMulticastGroupResponseTypeDef",
     "GetMulticastGroupSessionResponseTypeDef",
     "StartMulticastGroupSessionRequestRequestTypeDef",
     "GetPartnerAccountResponseTypeDef",
     "ListPartnerAccountsResponseTypeDef",
     "GetServiceProfileResponseTypeDef",
+    "GetWirelessDeviceImportTaskResponseTypeDef",
+    "WirelessDeviceImportTaskTypeDef",
     "GsmNmrObjTypeDef",
+    "ImportedWirelessDeviceTypeDef",
     "JoinEventConfigurationTypeDef",
     "JoinResourceTypeEventConfigurationTypeDef",
     "ListMulticastGroupsByFuotaTaskResponseTypeDef",
     "ListMulticastGroupsResponseTypeDef",
     "ListNetworkAnalyzerConfigurationsResponseTypeDef",
     "ListServiceProfilesResponseTypeDef",
     "LoRaWANDeviceMetadataTypeDef",
@@ -272,27 +293,33 @@
     "LoRaWANUpdateGatewayTaskCreateTypeDef",
     "LoRaWANUpdateGatewayTaskEntryTypeDef",
     "MulticastWirelessMetadataTypeDef",
     "StartFuotaTaskRequestRequestTypeDef",
     "LteObjTypeDef",
     "PositionSolverConfigurationsTypeDef",
     "PositionSolverDetailsTypeDef",
+    "StartSingleWirelessDeviceImportTaskRequestRequestTypeDef",
+    "StartWirelessDeviceImportTaskRequestRequestTypeDef",
     "UpdatePartnerAccountRequestRequestTypeDef",
+    "UpdateWirelessDeviceImportTaskRequestRequestTypeDef",
     "TdscdmaObjTypeDef",
     "WcdmaObjTypeDef",
     "WirelessDeviceLogOptionTypeDef",
     "WirelessGatewayLogOptionTypeDef",
     "CreateWirelessGatewayRequestRequestTypeDef",
     "GetWirelessGatewayResponseTypeDef",
     "WirelessGatewayStatisticsTypeDef",
     "WirelessDeviceStatisticsTypeDef",
+    "GetDeviceProfileResponseTypeDef",
     "LoRaWANDeviceTypeDef",
     "LoRaWANUpdateDeviceTypeDef",
     "LoRaWANSendDataToDeviceTypeDef",
+    "ListWirelessDeviceImportTasksResponseTypeDef",
     "GsmObjTypeDef",
+    "ListDevicesForWirelessDeviceImportTaskResponseTypeDef",
     "EventNotificationItemConfigurationsTypeDef",
     "GetResourceEventConfigurationResponseTypeDef",
     "UpdateResourceEventConfigurationRequestRequestTypeDef",
     "GetEventConfigurationByResourceTypesResponseTypeDef",
     "UpdateEventConfigurationByResourceTypesRequestRequestTypeDef",
     "GetWirelessDeviceStatisticsResponseTypeDef",
     "GetWirelessGatewayFirmwareInformationResponseTypeDef",
@@ -319,25 +346,25 @@
     "ListPositionConfigurationsResponseTypeDef",
     "ListQueuedMessagesResponseTypeDef",
     "SendDataToWirelessDeviceRequestRequestTypeDef",
     "GetPositionEstimateRequestRequestTypeDef",
     "ListEventConfigurationsResponseTypeDef",
 )
 
-SessionKeysAbpV1_0_xTypeDef = TypedDict(
-    "SessionKeysAbpV1_0_xTypeDef",
+SessionKeysAbpV10XTypeDef = TypedDict(
+    "SessionKeysAbpV10XTypeDef",
     {
         "NwkSKey": str,
         "AppSKey": str,
     },
     total=False,
 )
 
-SessionKeysAbpV1_1TypeDef = TypedDict(
-    "SessionKeysAbpV1_1TypeDef",
+SessionKeysAbpV11TypeDef = TypedDict(
+    "SessionKeysAbpV11TypeDef",
     {
         "FNwkSIntKey": str,
         "SNwkSIntKey": str,
         "NwkSEncKey": str,
         "AppSKey": str,
     },
     total=False,
@@ -375,25 +402,14 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
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
 AssociateMulticastGroupWithFuotaTaskRequestRequestTypeDef = TypedDict(
     "AssociateMulticastGroupWithFuotaTaskRequestRequestTypeDef",
     {
         "Id": str,
         "MulticastGroupId": str,
     },
 )
@@ -426,14 +442,22 @@
     "AssociateWirelessGatewayWithCertificateRequestRequestTypeDef",
     {
         "Id": str,
         "IotCertificateId": str,
     },
 )
 
+AssociateWirelessGatewayWithCertificateResponseTypeDef = TypedDict(
+    "AssociateWirelessGatewayWithCertificateResponseTypeDef",
+    {
+        "IotCertificateId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AssociateWirelessGatewayWithThingRequestRequestTypeDef = TypedDict(
     "AssociateWirelessGatewayWithThingRequestRequestTypeDef",
     {
         "Id": str,
         "ThingArn": str,
     },
 )
@@ -474,19 +498,17 @@
     {
         "PilotPower": int,
         "BaseStationId": int,
     },
     total=False,
 )
 
-
 class CdmaNmrObjTypeDef(_RequiredCdmaNmrObjTypeDef, _OptionalCdmaNmrObjTypeDef):
     pass
 
-
 CertificateListTypeDef = TypedDict(
     "CertificateListTypeDef",
     {
         "SigningAlg": SigningAlgType,
         "Value": str,
     },
 )
@@ -503,14 +525,23 @@
     "LoRaWANConnectionStatusResourceTypeEventConfigurationTypeDef",
     {
         "WirelessGatewayEventTopic": EventNotificationTopicStatusType,
     },
     total=False,
 )
 
+CreateDestinationResponseTypeDef = TypedDict(
+    "CreateDestinationResponseTypeDef",
+    {
+        "Arn": str,
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 LoRaWANDeviceProfileTypeDef = TypedDict(
     "LoRaWANDeviceProfileTypeDef",
     {
         "SupportsClassB": bool,
         "ClassBTimeout": int,
         "PingSlotPeriod": int,
         "PingSlotDr": int,
@@ -529,58 +560,172 @@
         "RfRegion": str,
         "SupportsJoin": bool,
         "Supports32BitFCnt": bool,
     },
     total=False,
 )
 
+CreateDeviceProfileResponseTypeDef = TypedDict(
+    "CreateDeviceProfileResponseTypeDef",
+    {
+        "Arn": str,
+        "Id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 LoRaWANFuotaTaskTypeDef = TypedDict(
     "LoRaWANFuotaTaskTypeDef",
     {
         "RfRegion": SupportedRfRegionType,
     },
     total=False,
 )
 
+CreateFuotaTaskResponseTypeDef = TypedDict(
+    "CreateFuotaTaskResponseTypeDef",
+    {
+        "Arn": str,
+        "Id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 LoRaWANMulticastTypeDef = TypedDict(
     "LoRaWANMulticastTypeDef",
     {
         "RfRegion": SupportedRfRegionType,
         "DlClass": DlClassType,
     },
     total=False,
 )
 
+CreateMulticastGroupResponseTypeDef = TypedDict(
+    "CreateMulticastGroupResponseTypeDef",
+    {
+        "Arn": str,
+        "Id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TraceContentTypeDef = TypedDict(
     "TraceContentTypeDef",
     {
         "WirelessDeviceFrameInfo": WirelessDeviceFrameInfoType,
         "LogLevel": LogLevelType,
+        "MulticastFrameInfo": MulticastFrameInfoType,
     },
     total=False,
 )
 
+CreateNetworkAnalyzerConfigurationResponseTypeDef = TypedDict(
+    "CreateNetworkAnalyzerConfigurationResponseTypeDef",
+    {
+        "Arn": str,
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 LoRaWANServiceProfileTypeDef = TypedDict(
     "LoRaWANServiceProfileTypeDef",
     {
         "AddGwMetadata": bool,
         "DrMin": int,
         "DrMax": int,
+        "PrAllowed": bool,
+        "RaAllowed": bool,
     },
     total=False,
 )
 
+CreateServiceProfileResponseTypeDef = TypedDict(
+    "CreateServiceProfileResponseTypeDef",
+    {
+        "Arn": str,
+        "Id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+SidewalkCreateWirelessDeviceTypeDef = TypedDict(
+    "SidewalkCreateWirelessDeviceTypeDef",
+    {
+        "DeviceProfileId": str,
+    },
+    total=False,
+)
+
+CreateWirelessDeviceResponseTypeDef = TypedDict(
+    "CreateWirelessDeviceResponseTypeDef",
+    {
+        "Arn": str,
+        "Id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateWirelessGatewayResponseTypeDef = TypedDict(
+    "CreateWirelessGatewayResponseTypeDef",
+    {
+        "Arn": str,
+        "Id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateWirelessGatewayTaskDefinitionResponseTypeDef = TypedDict(
+    "CreateWirelessGatewayTaskDefinitionResponseTypeDef",
+    {
+        "Id": str,
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateWirelessGatewayTaskRequestRequestTypeDef = TypedDict(
     "CreateWirelessGatewayTaskRequestRequestTypeDef",
     {
         "Id": str,
         "WirelessGatewayTaskDefinitionId": str,
     },
 )
 
+CreateWirelessGatewayTaskResponseTypeDef = TypedDict(
+    "CreateWirelessGatewayTaskResponseTypeDef",
+    {
+        "WirelessGatewayTaskDefinitionId": str,
+        "Status": WirelessGatewayTaskStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredDakCertificateMetadataTypeDef = TypedDict(
+    "_RequiredDakCertificateMetadataTypeDef",
+    {
+        "CertificateId": str,
+    },
+)
+_OptionalDakCertificateMetadataTypeDef = TypedDict(
+    "_OptionalDakCertificateMetadataTypeDef",
+    {
+        "MaxAllowedSignature": int,
+        "FactorySupport": bool,
+        "ApId": str,
+        "DeviceTypeId": str,
+    },
+    total=False,
+)
+
+class DakCertificateMetadataTypeDef(
+    _RequiredDakCertificateMetadataTypeDef, _OptionalDakCertificateMetadataTypeDef
+):
+    pass
+
 DeleteDestinationRequestRequestTypeDef = TypedDict(
     "DeleteDestinationRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
@@ -623,29 +768,34 @@
     "_OptionalDeleteQueuedMessagesRequestRequestTypeDef",
     {
         "WirelessDeviceType": WirelessDeviceTypeType,
     },
     total=False,
 )
 
-
 class DeleteQueuedMessagesRequestRequestTypeDef(
     _RequiredDeleteQueuedMessagesRequestRequestTypeDef,
     _OptionalDeleteQueuedMessagesRequestRequestTypeDef,
 ):
     pass
 
-
 DeleteServiceProfileRequestRequestTypeDef = TypedDict(
     "DeleteServiceProfileRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 
+DeleteWirelessDeviceImportTaskRequestRequestTypeDef = TypedDict(
+    "DeleteWirelessDeviceImportTaskRequestRequestTypeDef",
+    {
+        "Id": str,
+    },
+)
+
 DeleteWirelessDeviceRequestRequestTypeDef = TypedDict(
     "DeleteWirelessDeviceRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 
@@ -666,14 +816,34 @@
 DeleteWirelessGatewayTaskRequestRequestTypeDef = TypedDict(
     "DeleteWirelessGatewayTaskRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 
+_RequiredDeregisterWirelessDeviceRequestRequestTypeDef = TypedDict(
+    "_RequiredDeregisterWirelessDeviceRequestRequestTypeDef",
+    {
+        "Identifier": str,
+    },
+)
+_OptionalDeregisterWirelessDeviceRequestRequestTypeDef = TypedDict(
+    "_OptionalDeregisterWirelessDeviceRequestRequestTypeDef",
+    {
+        "WirelessDeviceType": WirelessDeviceTypeType,
+    },
+    total=False,
+)
+
+class DeregisterWirelessDeviceRequestRequestTypeDef(
+    _RequiredDeregisterWirelessDeviceRequestRequestTypeDef,
+    _OptionalDeregisterWirelessDeviceRequestRequestTypeDef,
+):
+    pass
+
 DestinationsTypeDef = TypedDict(
     "DestinationsTypeDef",
     {
         "Arn": str,
         "Name": str,
         "ExpressionType": ExpressionTypeType,
         "Expression": str,
@@ -793,14 +963,27 @@
 GetDestinationRequestRequestTypeDef = TypedDict(
     "GetDestinationRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+GetDestinationResponseTypeDef = TypedDict(
+    "GetDestinationResponseTypeDef",
+    {
+        "Arn": str,
+        "Name": str,
+        "Expression": str,
+        "ExpressionType": ExpressionTypeType,
+        "Description": str,
+        "RoleArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetDeviceProfileRequestRequestTypeDef = TypedDict(
     "GetDeviceProfileRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 
@@ -848,14 +1031,15 @@
 LoRaWANMulticastSessionTypeDef = TypedDict(
     "LoRaWANMulticastSessionTypeDef",
     {
         "DlDr": int,
         "DlFreq": int,
         "SessionStartTime": datetime,
         "SessionTimeout": int,
+        "PingSlotPeriod": int,
     },
     total=False,
 )
 
 GetNetworkAnalyzerConfigurationRequestRequestTypeDef = TypedDict(
     "GetNetworkAnalyzerConfigurationRequestRequestTypeDef",
     {
@@ -903,19 +1087,17 @@
         "AssistPosition": Sequence[float],
         "AssistAltitude": float,
         "Use2DSolver": bool,
     },
     total=False,
 )
 
-
 class GnssTypeDef(_RequiredGnssTypeDef, _OptionalGnssTypeDef):
     pass
 
-
 IpTypeDef = TypedDict(
     "IpTypeDef",
     {
         "IpAddress": str,
     },
 )
 
@@ -923,14 +1105,22 @@
     "WiFiAccessPointTypeDef",
     {
         "MacAddress": str,
         "Rss": int,
     },
 )
 
+GetPositionEstimateResponseTypeDef = TypedDict(
+    "GetPositionEstimateResponseTypeDef",
+    {
+        "GeoJsonPayload": StreamingBody,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetPositionRequestRequestTypeDef = TypedDict(
     "GetPositionRequestRequestTypeDef",
     {
         "ResourceIdentifier": str,
         "ResourceType": PositionResourceTypeType,
     },
 )
@@ -946,46 +1136,70 @@
     "_OptionalGetResourceEventConfigurationRequestRequestTypeDef",
     {
         "PartnerType": Literal["Sidewalk"],
     },
     total=False,
 )
 
-
 class GetResourceEventConfigurationRequestRequestTypeDef(
     _RequiredGetResourceEventConfigurationRequestRequestTypeDef,
     _OptionalGetResourceEventConfigurationRequestRequestTypeDef,
 ):
     pass
 
-
 GetResourceLogLevelRequestRequestTypeDef = TypedDict(
     "GetResourceLogLevelRequestRequestTypeDef",
     {
         "ResourceIdentifier": str,
         "ResourceType": str,
     },
 )
 
+GetResourceLogLevelResponseTypeDef = TypedDict(
+    "GetResourceLogLevelResponseTypeDef",
+    {
+        "LogLevel": LogLevelType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetResourcePositionRequestRequestTypeDef = TypedDict(
     "GetResourcePositionRequestRequestTypeDef",
     {
         "ResourceIdentifier": str,
         "ResourceType": PositionResourceTypeType,
     },
 )
 
+GetResourcePositionResponseTypeDef = TypedDict(
+    "GetResourcePositionResponseTypeDef",
+    {
+        "GeoJsonPayload": StreamingBody,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetServiceEndpointRequestRequestTypeDef = TypedDict(
     "GetServiceEndpointRequestRequestTypeDef",
     {
         "ServiceType": WirelessGatewayServiceTypeType,
     },
     total=False,
 )
 
+GetServiceEndpointResponseTypeDef = TypedDict(
+    "GetServiceEndpointResponseTypeDef",
+    {
+        "ServiceType": WirelessGatewayServiceTypeType,
+        "ServiceEndpoint": str,
+        "ServerTrust": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetServiceProfileRequestRequestTypeDef = TypedDict(
     "GetServiceProfileRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 
@@ -1011,14 +1225,30 @@
         "NwkGeoLoc": bool,
         "TargetPer": int,
         "MinGwDiversity": int,
     },
     total=False,
 )
 
+GetWirelessDeviceImportTaskRequestRequestTypeDef = TypedDict(
+    "GetWirelessDeviceImportTaskRequestRequestTypeDef",
+    {
+        "Id": str,
+    },
+)
+
+SidewalkGetStartImportInfoTypeDef = TypedDict(
+    "SidewalkGetStartImportInfoTypeDef",
+    {
+        "DeviceCreationFileList": List[str],
+        "Role": str,
+    },
+    total=False,
+)
+
 GetWirelessDeviceRequestRequestTypeDef = TypedDict(
     "GetWirelessDeviceRequestRequestTypeDef",
     {
         "Identifier": str,
         "IdentifierType": WirelessDeviceIdTypeType,
     },
 )
@@ -1044,14 +1274,23 @@
 GetWirelessGatewayCertificateRequestRequestTypeDef = TypedDict(
     "GetWirelessGatewayCertificateRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 
+GetWirelessGatewayCertificateResponseTypeDef = TypedDict(
+    "GetWirelessGatewayCertificateResponseTypeDef",
+    {
+        "IotCertificateId": str,
+        "LoRaWANNetworkServerCertificateId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetWirelessGatewayFirmwareInformationRequestRequestTypeDef = TypedDict(
     "GetWirelessGatewayFirmwareInformationRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 
@@ -1066,28 +1305,50 @@
 GetWirelessGatewayStatisticsRequestRequestTypeDef = TypedDict(
     "GetWirelessGatewayStatisticsRequestRequestTypeDef",
     {
         "WirelessGatewayId": str,
     },
 )
 
+GetWirelessGatewayStatisticsResponseTypeDef = TypedDict(
+    "GetWirelessGatewayStatisticsResponseTypeDef",
+    {
+        "WirelessGatewayId": str,
+        "LastUplinkReceivedAt": str,
+        "ConnectionStatus": ConnectionStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetWirelessGatewayTaskDefinitionRequestRequestTypeDef = TypedDict(
     "GetWirelessGatewayTaskDefinitionRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 
 GetWirelessGatewayTaskRequestRequestTypeDef = TypedDict(
     "GetWirelessGatewayTaskRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 
+GetWirelessGatewayTaskResponseTypeDef = TypedDict(
+    "GetWirelessGatewayTaskResponseTypeDef",
+    {
+        "WirelessGatewayId": str,
+        "WirelessGatewayTaskDefinitionId": str,
+        "LastUplinkReceivedAt": str,
+        "TaskCreatedAt": str,
+        "Status": WirelessGatewayTaskStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GlobalIdentityTypeDef = TypedDict(
     "GlobalIdentityTypeDef",
     {
         "Lac": int,
         "GeranCid": int,
     },
 )
@@ -1096,14 +1357,25 @@
     "GsmLocalIdTypeDef",
     {
         "Bsic": int,
         "Bcch": int,
     },
 )
 
+ImportedSidewalkDeviceTypeDef = TypedDict(
+    "ImportedSidewalkDeviceTypeDef",
+    {
+        "SidewalkManufacturingSn": str,
+        "OnboardingStatus": OnboardStatusType,
+        "OnboardingStatusReason": str,
+        "LastUpdateTime": datetime,
+    },
+    total=False,
+)
+
 LoRaWANJoinEventNotificationConfigurationsTypeDef = TypedDict(
     "LoRaWANJoinEventNotificationConfigurationsTypeDef",
     {
         "DevEuiEventTopic": EventNotificationTopicStatusType,
     },
     total=False,
 )
@@ -1126,18 +1398,41 @@
 )
 
 ListDeviceProfilesRequestRequestTypeDef = TypedDict(
     "ListDeviceProfilesRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
+        "DeviceProfileType": DeviceProfileTypeType,
+    },
+    total=False,
+)
+
+_RequiredListDevicesForWirelessDeviceImportTaskRequestRequestTypeDef = TypedDict(
+    "_RequiredListDevicesForWirelessDeviceImportTaskRequestRequestTypeDef",
+    {
+        "Id": str,
+    },
+)
+_OptionalListDevicesForWirelessDeviceImportTaskRequestRequestTypeDef = TypedDict(
+    "_OptionalListDevicesForWirelessDeviceImportTaskRequestRequestTypeDef",
+    {
+        "MaxResults": int,
+        "NextToken": str,
+        "Status": OnboardStatusType,
     },
     total=False,
 )
 
+class ListDevicesForWirelessDeviceImportTaskRequestRequestTypeDef(
+    _RequiredListDevicesForWirelessDeviceImportTaskRequestRequestTypeDef,
+    _OptionalListDevicesForWirelessDeviceImportTaskRequestRequestTypeDef,
+):
+    pass
+
 _RequiredListEventConfigurationsRequestRequestTypeDef = TypedDict(
     "_RequiredListEventConfigurationsRequestRequestTypeDef",
     {
         "ResourceType": EventNotificationResourceTypeType,
     },
 )
 _OptionalListEventConfigurationsRequestRequestTypeDef = TypedDict(
@@ -1145,22 +1440,20 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class ListEventConfigurationsRequestRequestTypeDef(
     _RequiredListEventConfigurationsRequestRequestTypeDef,
     _OptionalListEventConfigurationsRequestRequestTypeDef,
 ):
     pass
 
-
 ListFuotaTasksRequestRequestTypeDef = TypedDict(
     "ListFuotaTasksRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
@@ -1177,22 +1470,20 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
-
 class ListMulticastGroupsByFuotaTaskRequestRequestTypeDef(
     _RequiredListMulticastGroupsByFuotaTaskRequestRequestTypeDef,
     _OptionalListMulticastGroupsByFuotaTaskRequestRequestTypeDef,
 ):
     pass
 
-
 MulticastGroupByFuotaTaskTypeDef = TypedDict(
     "MulticastGroupByFuotaTaskTypeDef",
     {
         "Id": str,
     },
     total=False,
 )
@@ -1265,22 +1556,20 @@
         "NextToken": str,
         "MaxResults": int,
         "WirelessDeviceType": WirelessDeviceTypeType,
     },
     total=False,
 )
 
-
 class ListQueuedMessagesRequestRequestTypeDef(
     _RequiredListQueuedMessagesRequestRequestTypeDef,
     _OptionalListQueuedMessagesRequestRequestTypeDef,
 ):
     pass
 
-
 ListServiceProfilesRequestRequestTypeDef = TypedDict(
     "ListServiceProfilesRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
@@ -1299,14 +1588,23 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+ListWirelessDeviceImportTasksRequestRequestTypeDef = TypedDict(
+    "ListWirelessDeviceImportTasksRequestRequestTypeDef",
+    {
+        "MaxResults": int,
+        "NextToken": str,
+    },
+    total=False,
+)
+
 ListWirelessDevicesRequestRequestTypeDef = TypedDict(
     "ListWirelessDevicesRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
         "DestinationName": str,
         "DeviceProfileId": str,
@@ -1343,26 +1641,26 @@
         "GatewayEui": str,
         "Snr": float,
         "Rssi": float,
     },
     total=False,
 )
 
-OtaaV1_0_xTypeDef = TypedDict(
-    "OtaaV1_0_xTypeDef",
+OtaaV10XTypeDef = TypedDict(
+    "OtaaV10XTypeDef",
     {
         "AppKey": str,
         "AppEui": str,
         "GenAppKey": str,
     },
     total=False,
 )
 
-OtaaV1_1TypeDef = TypedDict(
-    "OtaaV1_1TypeDef",
+OtaaV11TypeDef = TypedDict(
+    "OtaaV11TypeDef",
     {
         "AppKey": str,
         "NwkKey": str,
         "JoinEui": str,
     },
     total=False,
 )
@@ -1397,24 +1695,24 @@
     "LoRaWANStartFuotaTaskTypeDef",
     {
         "StartTime": Union[datetime, str],
     },
     total=False,
 )
 
-UpdateAbpV1_0_xTypeDef = TypedDict(
-    "UpdateAbpV1_0_xTypeDef",
+UpdateAbpV10XTypeDef = TypedDict(
+    "UpdateAbpV10XTypeDef",
     {
         "FCntStart": int,
     },
     total=False,
 )
 
-UpdateAbpV1_1TypeDef = TypedDict(
-    "UpdateAbpV1_1TypeDef",
+UpdateAbpV11TypeDef = TypedDict(
+    "UpdateAbpV11TypeDef",
     {
         "FCntStart": int,
     },
     total=False,
 )
 
 LteLocalIdTypeDef = TypedDict(
@@ -1438,19 +1736,17 @@
     {
         "Rsrp": int,
         "Rsrq": float,
     },
     total=False,
 )
 
-
 class LteNmrObjTypeDef(_RequiredLteNmrObjTypeDef, _OptionalLteNmrObjTypeDef):
     pass
 
-
 SemtechGnssConfigurationTypeDef = TypedDict(
     "SemtechGnssConfigurationTypeDef",
     {
         "Status": PositionConfigurationStatusType,
         "Fec": PositionConfigurationFecType,
     },
 )
@@ -1479,32 +1775,102 @@
     "ResetResourceLogLevelRequestRequestTypeDef",
     {
         "ResourceIdentifier": str,
         "ResourceType": str,
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
+SendDataToMulticastGroupResponseTypeDef = TypedDict(
+    "SendDataToMulticastGroupResponseTypeDef",
+    {
+        "MessageId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+SendDataToWirelessDeviceResponseTypeDef = TypedDict(
+    "SendDataToWirelessDeviceResponseTypeDef",
+    {
+        "MessageId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 SidewalkSendDataToDeviceTypeDef = TypedDict(
     "SidewalkSendDataToDeviceTypeDef",
     {
         "Seq": int,
         "MessageType": MessageTypeType,
         "AckModeRetryDurationSecs": int,
     },
     total=False,
 )
 
+SidewalkSingleStartImportInfoTypeDef = TypedDict(
+    "SidewalkSingleStartImportInfoTypeDef",
+    {
+        "SidewalkManufacturingSn": str,
+    },
+    total=False,
+)
+
+SidewalkStartImportInfoTypeDef = TypedDict(
+    "SidewalkStartImportInfoTypeDef",
+    {
+        "DeviceCreationFile": str,
+        "Role": str,
+    },
+    total=False,
+)
+
 SidewalkUpdateAccountTypeDef = TypedDict(
     "SidewalkUpdateAccountTypeDef",
     {
         "AppServerPrivateKey": str,
     },
     total=False,
 )
 
+SidewalkUpdateImportInfoTypeDef = TypedDict(
+    "SidewalkUpdateImportInfoTypeDef",
+    {
+        "DeviceCreationFile": str,
+    },
+    total=False,
+)
+
+StartSingleWirelessDeviceImportTaskResponseTypeDef = TypedDict(
+    "StartSingleWirelessDeviceImportTaskResponseTypeDef",
+    {
+        "Id": str,
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartWirelessDeviceImportTaskResponseTypeDef = TypedDict(
+    "StartWirelessDeviceImportTaskResponseTypeDef",
+    {
+        "Id": str,
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TdscdmaLocalIdTypeDef = TypedDict(
     "TdscdmaLocalIdTypeDef",
     {
         "Uarfcn": int,
         "CellParams": int,
     },
 )
@@ -1522,26 +1888,32 @@
         "UtranCid": int,
         "Rscp": int,
         "PathLoss": int,
     },
     total=False,
 )
 
-
 class TdscdmaNmrObjTypeDef(_RequiredTdscdmaNmrObjTypeDef, _OptionalTdscdmaNmrObjTypeDef):
     pass
 
-
 TestWirelessDeviceRequestRequestTypeDef = TypedDict(
     "TestWirelessDeviceRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 
+TestWirelessDeviceResponseTypeDef = TypedDict(
+    "TestWirelessDeviceResponseTypeDef",
+    {
+        "Result": str,
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
@@ -1559,21 +1931,19 @@
         "Expression": str,
         "Description": str,
         "RoleArn": str,
     },
     total=False,
 )
 
-
 class UpdateDestinationRequestRequestTypeDef(
     _RequiredUpdateDestinationRequestRequestTypeDef, _OptionalUpdateDestinationRequestRequestTypeDef
 ):
     pass
 
-
 UpdatePositionRequestRequestTypeDef = TypedDict(
     "UpdatePositionRequestRequestTypeDef",
     {
         "ResourceIdentifier": str,
         "ResourceType": PositionResourceTypeType,
         "Position": Sequence[float],
     },
@@ -1590,47 +1960,44 @@
     "_OptionalUpdateResourcePositionRequestRequestTypeDef",
     {
         "GeoJsonPayload": Union[str, bytes, IO[Any], StreamingBody],
     },
     total=False,
 )
 
-
 class UpdateResourcePositionRequestRequestTypeDef(
     _RequiredUpdateResourcePositionRequestRequestTypeDef,
     _OptionalUpdateResourcePositionRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredUpdateWirelessGatewayRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateWirelessGatewayRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 _OptionalUpdateWirelessGatewayRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateWirelessGatewayRequestRequestTypeDef",
     {
         "Name": str,
         "Description": str,
         "JoinEuiFilters": Sequence[Sequence[str]],
         "NetIdFilters": Sequence[str],
+        "MaxEirp": float,
     },
     total=False,
 )
 
-
 class UpdateWirelessGatewayRequestRequestTypeDef(
     _RequiredUpdateWirelessGatewayRequestRequestTypeDef,
     _OptionalUpdateWirelessGatewayRequestRequestTypeDef,
 ):
     pass
 
-
 WcdmaLocalIdTypeDef = TypedDict(
     "WcdmaLocalIdTypeDef",
     {
         "Uarfcndl": int,
         "Psc": int,
     },
 )
@@ -1648,19 +2015,17 @@
     {
         "Rscp": int,
         "PathLoss": int,
     },
     total=False,
 )
 
-
 class WcdmaNmrObjTypeDef(_RequiredWcdmaNmrObjTypeDef, _OptionalWcdmaNmrObjTypeDef):
     pass
 
-
 WirelessDeviceEventLogOptionTypeDef = TypedDict(
     "WirelessDeviceEventLogOptionTypeDef",
     {
         "Event": WirelessDeviceEventType,
         "LogLevel": LogLevelType,
     },
 )
@@ -1669,34 +2034,56 @@
     "WirelessGatewayEventLogOptionTypeDef",
     {
         "Event": WirelessGatewayEventType,
         "LogLevel": LogLevelType,
     },
 )
 
-AbpV1_0_xTypeDef = TypedDict(
-    "AbpV1_0_xTypeDef",
+AbpV10XTypeDef = TypedDict(
+    "AbpV10XTypeDef",
     {
         "DevAddr": str,
-        "SessionKeys": SessionKeysAbpV1_0_xTypeDef,
+        "SessionKeys": SessionKeysAbpV10XTypeDef,
         "FCntStart": int,
     },
     total=False,
 )
 
-AbpV1_1TypeDef = TypedDict(
-    "AbpV1_1TypeDef",
+AbpV11TypeDef = TypedDict(
+    "AbpV11TypeDef",
     {
         "DevAddr": str,
-        "SessionKeys": SessionKeysAbpV1_1TypeDef,
+        "SessionKeys": SessionKeysAbpV11TypeDef,
         "FCntStart": int,
     },
     total=False,
 )
 
+GetPositionResponseTypeDef = TypedDict(
+    "GetPositionResponseTypeDef",
+    {
+        "Position": List[float],
+        "Accuracy": AccuracyTypeDef,
+        "SolverType": Literal["GNSS"],
+        "SolverProvider": Literal["Semtech"],
+        "SolverVersion": str,
+        "Timestamp": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+AssociateAwsAccountWithPartnerAccountResponseTypeDef = TypedDict(
+    "AssociateAwsAccountWithPartnerAccountResponseTypeDef",
+    {
+        "Sidewalk": SidewalkAccountInfoTypeDef,
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredAssociateAwsAccountWithPartnerAccountRequestRequestTypeDef = TypedDict(
     "_RequiredAssociateAwsAccountWithPartnerAccountRequestRequestTypeDef",
     {
         "Sidewalk": SidewalkAccountInfoTypeDef,
     },
 )
 _OptionalAssociateAwsAccountWithPartnerAccountRequestRequestTypeDef = TypedDict(
@@ -1704,22 +2091,20 @@
     {
         "ClientRequestToken": str,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class AssociateAwsAccountWithPartnerAccountRequestRequestTypeDef(
     _RequiredAssociateAwsAccountWithPartnerAccountRequestRequestTypeDef,
     _OptionalAssociateAwsAccountWithPartnerAccountRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredCreateDestinationRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDestinationRequestRequestTypeDef",
     {
         "Name": str,
         "ExpressionType": ExpressionTypeType,
         "Expression": str,
         "RoleArn": str,
@@ -1731,20 +2116,26 @@
         "Description": str,
         "Tags": Sequence[TagTypeDef],
         "ClientRequestToken": str,
     },
     total=False,
 )
 
-
 class CreateDestinationRequestRequestTypeDef(
     _RequiredCreateDestinationRequestRequestTypeDef, _OptionalCreateDestinationRequestRequestTypeDef
 ):
     pass
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "Tags": List[TagTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredStartBulkAssociateWirelessDeviceWithMulticastGroupRequestRequestTypeDef = TypedDict(
     "_RequiredStartBulkAssociateWirelessDeviceWithMulticastGroupRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
@@ -1753,22 +2144,20 @@
     {
         "QueryString": str,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class StartBulkAssociateWirelessDeviceWithMulticastGroupRequestRequestTypeDef(
     _RequiredStartBulkAssociateWirelessDeviceWithMulticastGroupRequestRequestTypeDef,
     _OptionalStartBulkAssociateWirelessDeviceWithMulticastGroupRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredStartBulkDisassociateWirelessDeviceFromMulticastGroupRequestRequestTypeDef = TypedDict(
     "_RequiredStartBulkDisassociateWirelessDeviceFromMulticastGroupRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 _OptionalStartBulkDisassociateWirelessDeviceFromMulticastGroupRequestRequestTypeDef = TypedDict(
@@ -1776,269 +2165,38 @@
     {
         "QueryString": str,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class StartBulkDisassociateWirelessDeviceFromMulticastGroupRequestRequestTypeDef(
     _RequiredStartBulkDisassociateWirelessDeviceFromMulticastGroupRequestRequestTypeDef,
     _OptionalStartBulkDisassociateWirelessDeviceFromMulticastGroupRequestRequestTypeDef,
 ):
     pass
 
-
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "Tags": Sequence[TagTypeDef],
     },
 )
 
-AssociateAwsAccountWithPartnerAccountResponseTypeDef = TypedDict(
-    "AssociateAwsAccountWithPartnerAccountResponseTypeDef",
-    {
-        "Sidewalk": SidewalkAccountInfoTypeDef,
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-AssociateWirelessGatewayWithCertificateResponseTypeDef = TypedDict(
-    "AssociateWirelessGatewayWithCertificateResponseTypeDef",
-    {
-        "IotCertificateId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDestinationResponseTypeDef = TypedDict(
-    "CreateDestinationResponseTypeDef",
-    {
-        "Arn": str,
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDeviceProfileResponseTypeDef = TypedDict(
-    "CreateDeviceProfileResponseTypeDef",
-    {
-        "Arn": str,
-        "Id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateFuotaTaskResponseTypeDef = TypedDict(
-    "CreateFuotaTaskResponseTypeDef",
-    {
-        "Arn": str,
-        "Id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateMulticastGroupResponseTypeDef = TypedDict(
-    "CreateMulticastGroupResponseTypeDef",
-    {
-        "Arn": str,
-        "Id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateNetworkAnalyzerConfigurationResponseTypeDef = TypedDict(
-    "CreateNetworkAnalyzerConfigurationResponseTypeDef",
-    {
-        "Arn": str,
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateServiceProfileResponseTypeDef = TypedDict(
-    "CreateServiceProfileResponseTypeDef",
-    {
-        "Arn": str,
-        "Id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateWirelessDeviceResponseTypeDef = TypedDict(
-    "CreateWirelessDeviceResponseTypeDef",
-    {
-        "Arn": str,
-        "Id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateWirelessGatewayResponseTypeDef = TypedDict(
-    "CreateWirelessGatewayResponseTypeDef",
-    {
-        "Arn": str,
-        "Id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateWirelessGatewayTaskDefinitionResponseTypeDef = TypedDict(
-    "CreateWirelessGatewayTaskDefinitionResponseTypeDef",
-    {
-        "Id": str,
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateWirelessGatewayTaskResponseTypeDef = TypedDict(
-    "CreateWirelessGatewayTaskResponseTypeDef",
-    {
-        "WirelessGatewayTaskDefinitionId": str,
-        "Status": WirelessGatewayTaskStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetDestinationResponseTypeDef = TypedDict(
-    "GetDestinationResponseTypeDef",
-    {
-        "Arn": str,
-        "Name": str,
-        "Expression": str,
-        "ExpressionType": ExpressionTypeType,
-        "Description": str,
-        "RoleArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetPositionEstimateResponseTypeDef = TypedDict(
-    "GetPositionEstimateResponseTypeDef",
-    {
-        "GeoJsonPayload": StreamingBody,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetPositionResponseTypeDef = TypedDict(
-    "GetPositionResponseTypeDef",
-    {
-        "Position": List[float],
-        "Accuracy": AccuracyTypeDef,
-        "SolverType": Literal["GNSS"],
-        "SolverProvider": Literal["Semtech"],
-        "SolverVersion": str,
-        "Timestamp": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetResourceLogLevelResponseTypeDef = TypedDict(
-    "GetResourceLogLevelResponseTypeDef",
-    {
-        "LogLevel": LogLevelType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetResourcePositionResponseTypeDef = TypedDict(
-    "GetResourcePositionResponseTypeDef",
-    {
-        "GeoJsonPayload": StreamingBody,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetServiceEndpointResponseTypeDef = TypedDict(
-    "GetServiceEndpointResponseTypeDef",
-    {
-        "ServiceType": WirelessGatewayServiceTypeType,
-        "ServiceEndpoint": str,
-        "ServerTrust": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetWirelessGatewayCertificateResponseTypeDef = TypedDict(
-    "GetWirelessGatewayCertificateResponseTypeDef",
-    {
-        "IotCertificateId": str,
-        "LoRaWANNetworkServerCertificateId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetWirelessGatewayStatisticsResponseTypeDef = TypedDict(
-    "GetWirelessGatewayStatisticsResponseTypeDef",
-    {
-        "WirelessGatewayId": str,
-        "LastUplinkReceivedAt": str,
-        "ConnectionStatus": ConnectionStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetWirelessGatewayTaskResponseTypeDef = TypedDict(
-    "GetWirelessGatewayTaskResponseTypeDef",
-    {
-        "WirelessGatewayId": str,
-        "WirelessGatewayTaskDefinitionId": str,
-        "LastUplinkReceivedAt": str,
-        "TaskCreatedAt": str,
-        "Status": WirelessGatewayTaskStatusType,
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
-SendDataToMulticastGroupResponseTypeDef = TypedDict(
-    "SendDataToMulticastGroupResponseTypeDef",
-    {
-        "MessageId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SendDataToWirelessDeviceResponseTypeDef = TypedDict(
-    "SendDataToWirelessDeviceResponseTypeDef",
-    {
-        "MessageId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-TestWirelessDeviceResponseTypeDef = TypedDict(
-    "TestWirelessDeviceResponseTypeDef",
-    {
-        "Result": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 LoRaWANGatewayTypeDef = TypedDict(
     "LoRaWANGatewayTypeDef",
     {
         "GatewayEui": str,
         "RfRegion": str,
         "JoinEuiFilters": Sequence[Sequence[str]],
         "NetIdFilters": Sequence[str],
         "SubBands": Sequence[int],
         "Beaconing": BeaconingTypeDef,
+        "MaxEirp": float,
     },
     total=False,
 )
 
 _RequiredCdmaObjTypeDef = TypedDict(
     "_RequiredCdmaObjTypeDef",
     {
@@ -2056,37 +2214,41 @@
         "BaseLat": float,
         "BaseLng": float,
         "CdmaNmr": Sequence[CdmaNmrObjTypeDef],
     },
     total=False,
 )
 
-
 class CdmaObjTypeDef(_RequiredCdmaObjTypeDef, _OptionalCdmaObjTypeDef):
     pass
 
-
 SidewalkDeviceTypeDef = TypedDict(
     "SidewalkDeviceTypeDef",
     {
         "AmazonId": str,
         "SidewalkId": str,
         "SidewalkManufacturingSn": str,
         "DeviceCertificates": List[CertificateListTypeDef],
+        "PrivateKeys": List[CertificateListTypeDef],
+        "DeviceProfileId": str,
+        "CertificateId": str,
+        "Status": WirelessDeviceSidewalkStatusType,
     },
     total=False,
 )
 
 SidewalkListDeviceTypeDef = TypedDict(
     "SidewalkListDeviceTypeDef",
     {
         "AmazonId": str,
         "SidewalkId": str,
         "SidewalkManufacturingSn": str,
         "DeviceCertificates": List[CertificateListTypeDef],
+        "DeviceProfileId": str,
+        "Status": WirelessDeviceSidewalkStatusType,
     },
     total=False,
 )
 
 ConnectionStatusEventConfigurationTypeDef = TypedDict(
     "ConnectionStatusEventConfigurationTypeDef",
     {
@@ -2107,29 +2269,19 @@
 CreateDeviceProfileRequestRequestTypeDef = TypedDict(
     "CreateDeviceProfileRequestRequestTypeDef",
     {
         "Name": str,
         "LoRaWAN": LoRaWANDeviceProfileTypeDef,
         "Tags": Sequence[TagTypeDef],
         "ClientRequestToken": str,
+        "Sidewalk": Mapping[str, Any],
     },
     total=False,
 )
 
-GetDeviceProfileResponseTypeDef = TypedDict(
-    "GetDeviceProfileResponseTypeDef",
-    {
-        "Arn": str,
-        "Name": str,
-        "Id": str,
-        "LoRaWAN": LoRaWANDeviceProfileTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 _RequiredCreateFuotaTaskRequestRequestTypeDef = TypedDict(
     "_RequiredCreateFuotaTaskRequestRequestTypeDef",
     {
         "FirmwareUpdateImage": str,
         "FirmwareUpdateRole": str,
     },
 )
@@ -2137,50 +2289,52 @@
     "_OptionalCreateFuotaTaskRequestRequestTypeDef",
     {
         "Name": str,
         "Description": str,
         "ClientRequestToken": str,
         "LoRaWAN": LoRaWANFuotaTaskTypeDef,
         "Tags": Sequence[TagTypeDef],
+        "RedundancyPercent": int,
+        "FragmentSizeBytes": int,
+        "FragmentIntervalMS": int,
     },
     total=False,
 )
 
-
 class CreateFuotaTaskRequestRequestTypeDef(
     _RequiredCreateFuotaTaskRequestRequestTypeDef, _OptionalCreateFuotaTaskRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredUpdateFuotaTaskRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateFuotaTaskRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 _OptionalUpdateFuotaTaskRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateFuotaTaskRequestRequestTypeDef",
     {
         "Name": str,
         "Description": str,
         "LoRaWAN": LoRaWANFuotaTaskTypeDef,
         "FirmwareUpdateImage": str,
         "FirmwareUpdateRole": str,
+        "RedundancyPercent": int,
+        "FragmentSizeBytes": int,
+        "FragmentIntervalMS": int,
     },
     total=False,
 )
 
-
 class UpdateFuotaTaskRequestRequestTypeDef(
     _RequiredUpdateFuotaTaskRequestRequestTypeDef, _OptionalUpdateFuotaTaskRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredCreateMulticastGroupRequestRequestTypeDef = TypedDict(
     "_RequiredCreateMulticastGroupRequestRequestTypeDef",
     {
         "LoRaWAN": LoRaWANMulticastTypeDef,
     },
 )
 _OptionalCreateMulticastGroupRequestRequestTypeDef = TypedDict(
@@ -2190,22 +2344,20 @@
         "Description": str,
         "ClientRequestToken": str,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateMulticastGroupRequestRequestTypeDef(
     _RequiredCreateMulticastGroupRequestRequestTypeDef,
     _OptionalCreateMulticastGroupRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredUpdateMulticastGroupRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateMulticastGroupRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 _OptionalUpdateMulticastGroupRequestRequestTypeDef = TypedDict(
@@ -2214,22 +2366,20 @@
         "Name": str,
         "Description": str,
         "LoRaWAN": LoRaWANMulticastTypeDef,
     },
     total=False,
 )
 
-
 class UpdateMulticastGroupRequestRequestTypeDef(
     _RequiredUpdateMulticastGroupRequestRequestTypeDef,
     _OptionalUpdateMulticastGroupRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredCreateNetworkAnalyzerConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredCreateNetworkAnalyzerConfigurationRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalCreateNetworkAnalyzerConfigurationRequestRequestTypeDef = TypedDict(
@@ -2237,36 +2387,36 @@
     {
         "TraceContent": TraceContentTypeDef,
         "WirelessDevices": Sequence[str],
         "WirelessGateways": Sequence[str],
         "Description": str,
         "Tags": Sequence[TagTypeDef],
         "ClientRequestToken": str,
+        "MulticastGroups": Sequence[str],
     },
     total=False,
 )
 
-
 class CreateNetworkAnalyzerConfigurationRequestRequestTypeDef(
     _RequiredCreateNetworkAnalyzerConfigurationRequestRequestTypeDef,
     _OptionalCreateNetworkAnalyzerConfigurationRequestRequestTypeDef,
 ):
     pass
 
-
 GetNetworkAnalyzerConfigurationResponseTypeDef = TypedDict(
     "GetNetworkAnalyzerConfigurationResponseTypeDef",
     {
         "TraceContent": TraceContentTypeDef,
         "WirelessDevices": List[str],
         "WirelessGateways": List[str],
         "Description": str,
         "Arn": str,
         "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "MulticastGroups": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateNetworkAnalyzerConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateNetworkAnalyzerConfigurationRequestRequestTypeDef",
     {
         "ConfigurationName": str,
@@ -2277,52 +2427,62 @@
     {
         "TraceContent": TraceContentTypeDef,
         "WirelessDevicesToAdd": Sequence[str],
         "WirelessDevicesToRemove": Sequence[str],
         "WirelessGatewaysToAdd": Sequence[str],
         "WirelessGatewaysToRemove": Sequence[str],
         "Description": str,
+        "MulticastGroupsToAdd": Sequence[str],
+        "MulticastGroupsToRemove": Sequence[str],
     },
     total=False,
 )
 
-
 class UpdateNetworkAnalyzerConfigurationRequestRequestTypeDef(
     _RequiredUpdateNetworkAnalyzerConfigurationRequestRequestTypeDef,
     _OptionalUpdateNetworkAnalyzerConfigurationRequestRequestTypeDef,
 ):
     pass
 
-
 CreateServiceProfileRequestRequestTypeDef = TypedDict(
     "CreateServiceProfileRequestRequestTypeDef",
     {
         "Name": str,
         "LoRaWAN": LoRaWANServiceProfileTypeDef,
         "Tags": Sequence[TagTypeDef],
         "ClientRequestToken": str,
     },
     total=False,
 )
 
+SidewalkGetDeviceProfileTypeDef = TypedDict(
+    "SidewalkGetDeviceProfileTypeDef",
+    {
+        "ApplicationServerPublicKey": str,
+        "QualificationStatus": bool,
+        "DakCertificateMetadata": List[DakCertificateMetadataTypeDef],
+    },
+    total=False,
+)
+
 ListDestinationsResponseTypeDef = TypedDict(
     "ListDestinationsResponseTypeDef",
     {
         "NextToken": str,
         "DestinationList": List[DestinationsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDeviceProfilesResponseTypeDef = TypedDict(
     "ListDeviceProfilesResponseTypeDef",
     {
         "NextToken": str,
         "DeviceProfileList": List[DeviceProfileTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeviceRegistrationStateEventConfigurationTypeDef = TypedDict(
     "DeviceRegistrationStateEventConfigurationTypeDef",
     {
         "Sidewalk": SidewalkEventNotificationConfigurationsTypeDef,
@@ -2395,15 +2555,15 @@
 )
 
 ListFuotaTasksResponseTypeDef = TypedDict(
     "ListFuotaTasksResponseTypeDef",
     {
         "NextToken": str,
         "FuotaTaskList": List[FuotaTaskTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ParticipatingGatewaysTypeDef = TypedDict(
     "ParticipatingGatewaysTypeDef",
     {
         "DownlinkMode": DownlinkModeType,
@@ -2420,37 +2580,40 @@
         "Status": FuotaTaskStatusType,
         "Name": str,
         "Description": str,
         "LoRaWAN": LoRaWANFuotaTaskGetInfoTypeDef,
         "FirmwareUpdateImage": str,
         "FirmwareUpdateRole": str,
         "CreatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RedundancyPercent": int,
+        "FragmentSizeBytes": int,
+        "FragmentIntervalMS": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMulticastGroupResponseTypeDef = TypedDict(
     "GetMulticastGroupResponseTypeDef",
     {
         "Arn": str,
         "Id": str,
         "Name": str,
         "Description": str,
         "Status": str,
         "LoRaWAN": LoRaWANMulticastGetTypeDef,
         "CreatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMulticastGroupSessionResponseTypeDef = TypedDict(
     "GetMulticastGroupSessionResponseTypeDef",
     {
         "LoRaWAN": LoRaWANMulticastSessionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartMulticastGroupSessionRequestRequestTypeDef = TypedDict(
     "StartMulticastGroupSessionRequestRequestTypeDef",
     {
         "Id": str,
@@ -2459,36 +2622,72 @@
 )
 
 GetPartnerAccountResponseTypeDef = TypedDict(
     "GetPartnerAccountResponseTypeDef",
     {
         "Sidewalk": SidewalkAccountInfoWithFingerprintTypeDef,
         "AccountLinked": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPartnerAccountsResponseTypeDef = TypedDict(
     "ListPartnerAccountsResponseTypeDef",
     {
         "NextToken": str,
         "Sidewalk": List[SidewalkAccountInfoWithFingerprintTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetServiceProfileResponseTypeDef = TypedDict(
     "GetServiceProfileResponseTypeDef",
     {
         "Arn": str,
         "Name": str,
         "Id": str,
         "LoRaWAN": LoRaWANGetServiceProfileInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetWirelessDeviceImportTaskResponseTypeDef = TypedDict(
+    "GetWirelessDeviceImportTaskResponseTypeDef",
+    {
+        "Id": str,
+        "Arn": str,
+        "DestinationName": str,
+        "Sidewalk": SidewalkGetStartImportInfoTypeDef,
+        "CreationTime": datetime,
+        "Status": ImportTaskStatusType,
+        "StatusReason": str,
+        "InitializedImportedDeviceCount": int,
+        "PendingImportedDeviceCount": int,
+        "OnboardedImportedDeviceCount": int,
+        "FailedImportedDeviceCount": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+WirelessDeviceImportTaskTypeDef = TypedDict(
+    "WirelessDeviceImportTaskTypeDef",
+    {
+        "Id": str,
+        "Arn": str,
+        "DestinationName": str,
+        "Sidewalk": SidewalkGetStartImportInfoTypeDef,
+        "CreationTime": datetime,
+        "Status": ImportTaskStatusType,
+        "StatusReason": str,
+        "InitializedImportedDeviceCount": int,
+        "PendingImportedDeviceCount": int,
+        "OnboardedImportedDeviceCount": int,
+        "FailedImportedDeviceCount": int,
     },
+    total=False,
 )
 
 _RequiredGsmNmrObjTypeDef = TypedDict(
     "_RequiredGsmNmrObjTypeDef",
     {
         "Bsic": int,
         "Bcch": int,
@@ -2499,18 +2698,24 @@
     {
         "RxLevel": int,
         "GlobalIdentity": GlobalIdentityTypeDef,
     },
     total=False,
 )
 
-
 class GsmNmrObjTypeDef(_RequiredGsmNmrObjTypeDef, _OptionalGsmNmrObjTypeDef):
     pass
 
+ImportedWirelessDeviceTypeDef = TypedDict(
+    "ImportedWirelessDeviceTypeDef",
+    {
+        "Sidewalk": ImportedSidewalkDeviceTypeDef,
+    },
+    total=False,
+)
 
 JoinEventConfigurationTypeDef = TypedDict(
     "JoinEventConfigurationTypeDef",
     {
         "LoRaWAN": LoRaWANJoinEventNotificationConfigurationsTypeDef,
         "WirelessDeviceIdEventTopic": EventNotificationTopicStatusType,
     },
@@ -2526,42 +2731,42 @@
 )
 
 ListMulticastGroupsByFuotaTaskResponseTypeDef = TypedDict(
     "ListMulticastGroupsByFuotaTaskResponseTypeDef",
     {
         "NextToken": str,
         "MulticastGroupList": List[MulticastGroupByFuotaTaskTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMulticastGroupsResponseTypeDef = TypedDict(
     "ListMulticastGroupsResponseTypeDef",
     {
         "NextToken": str,
         "MulticastGroupList": List[MulticastGroupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListNetworkAnalyzerConfigurationsResponseTypeDef = TypedDict(
     "ListNetworkAnalyzerConfigurationsResponseTypeDef",
     {
         "NextToken": str,
         "NetworkAnalyzerConfigurationList": List[NetworkAnalyzerConfigurationsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListServiceProfilesResponseTypeDef = TypedDict(
     "ListServiceProfilesResponseTypeDef",
     {
         "NextToken": str,
         "ServiceProfileList": List[ServiceProfileTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LoRaWANDeviceMetadataTypeDef = TypedDict(
     "LoRaWANDeviceMetadataTypeDef",
     {
         "DevEui": str,
@@ -2620,21 +2825,19 @@
     "_OptionalStartFuotaTaskRequestRequestTypeDef",
     {
         "LoRaWAN": LoRaWANStartFuotaTaskTypeDef,
     },
     total=False,
 )
 
-
 class StartFuotaTaskRequestRequestTypeDef(
     _RequiredStartFuotaTaskRequestRequestTypeDef, _OptionalStartFuotaTaskRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredLteObjTypeDef = TypedDict(
     "_RequiredLteObjTypeDef",
     {
         "Mcc": int,
         "Mnc": int,
         "EutranCid": int,
     },
@@ -2649,19 +2852,17 @@
         "Rsrq": float,
         "NrCapable": bool,
         "LteNmr": Sequence[LteNmrObjTypeDef],
     },
     total=False,
 )
 
-
 class LteObjTypeDef(_RequiredLteObjTypeDef, _OptionalLteObjTypeDef):
     pass
 
-
 PositionSolverConfigurationsTypeDef = TypedDict(
     "PositionSolverConfigurationsTypeDef",
     {
         "SemtechGnss": SemtechGnssConfigurationTypeDef,
     },
     total=False,
 )
@@ -2670,23 +2871,76 @@
     "PositionSolverDetailsTypeDef",
     {
         "SemtechGnss": SemtechGnssDetailTypeDef,
     },
     total=False,
 )
 
+_RequiredStartSingleWirelessDeviceImportTaskRequestRequestTypeDef = TypedDict(
+    "_RequiredStartSingleWirelessDeviceImportTaskRequestRequestTypeDef",
+    {
+        "DestinationName": str,
+        "Sidewalk": SidewalkSingleStartImportInfoTypeDef,
+    },
+)
+_OptionalStartSingleWirelessDeviceImportTaskRequestRequestTypeDef = TypedDict(
+    "_OptionalStartSingleWirelessDeviceImportTaskRequestRequestTypeDef",
+    {
+        "ClientRequestToken": str,
+        "DeviceName": str,
+        "Tags": Sequence[TagTypeDef],
+    },
+    total=False,
+)
+
+class StartSingleWirelessDeviceImportTaskRequestRequestTypeDef(
+    _RequiredStartSingleWirelessDeviceImportTaskRequestRequestTypeDef,
+    _OptionalStartSingleWirelessDeviceImportTaskRequestRequestTypeDef,
+):
+    pass
+
+_RequiredStartWirelessDeviceImportTaskRequestRequestTypeDef = TypedDict(
+    "_RequiredStartWirelessDeviceImportTaskRequestRequestTypeDef",
+    {
+        "DestinationName": str,
+        "Sidewalk": SidewalkStartImportInfoTypeDef,
+    },
+)
+_OptionalStartWirelessDeviceImportTaskRequestRequestTypeDef = TypedDict(
+    "_OptionalStartWirelessDeviceImportTaskRequestRequestTypeDef",
+    {
+        "ClientRequestToken": str,
+        "Tags": Sequence[TagTypeDef],
+    },
+    total=False,
+)
+
+class StartWirelessDeviceImportTaskRequestRequestTypeDef(
+    _RequiredStartWirelessDeviceImportTaskRequestRequestTypeDef,
+    _OptionalStartWirelessDeviceImportTaskRequestRequestTypeDef,
+):
+    pass
+
 UpdatePartnerAccountRequestRequestTypeDef = TypedDict(
     "UpdatePartnerAccountRequestRequestTypeDef",
     {
         "Sidewalk": SidewalkUpdateAccountTypeDef,
         "PartnerAccountId": str,
         "PartnerType": Literal["Sidewalk"],
     },
 )
 
+UpdateWirelessDeviceImportTaskRequestRequestTypeDef = TypedDict(
+    "UpdateWirelessDeviceImportTaskRequestRequestTypeDef",
+    {
+        "Id": str,
+        "Sidewalk": SidewalkUpdateImportInfoTypeDef,
+    },
+)
+
 _RequiredTdscdmaObjTypeDef = TypedDict(
     "_RequiredTdscdmaObjTypeDef",
     {
         "Mcc": int,
         "Mnc": int,
         "UtranCid": int,
     },
@@ -2700,19 +2954,17 @@
         "Rscp": int,
         "PathLoss": int,
         "TdscdmaNmr": Sequence[TdscdmaNmrObjTypeDef],
     },
     total=False,
 )
 
-
 class TdscdmaObjTypeDef(_RequiredTdscdmaObjTypeDef, _OptionalTdscdmaObjTypeDef):
     pass
 
-
 _RequiredWcdmaObjTypeDef = TypedDict(
     "_RequiredWcdmaObjTypeDef",
     {
         "Mcc": int,
         "Mnc": int,
         "UtranCid": int,
     },
@@ -2725,19 +2977,17 @@
         "Rscp": int,
         "PathLoss": int,
         "WcdmaNmr": Sequence[WcdmaNmrObjTypeDef],
     },
     total=False,
 )
 
-
 class WcdmaObjTypeDef(_RequiredWcdmaObjTypeDef, _OptionalWcdmaObjTypeDef):
     pass
 
-
 _RequiredWirelessDeviceLogOptionTypeDef = TypedDict(
     "_RequiredWirelessDeviceLogOptionTypeDef",
     {
         "Type": WirelessDeviceTypeType,
         "LogLevel": LogLevelType,
     },
 )
@@ -2745,21 +2995,19 @@
     "_OptionalWirelessDeviceLogOptionTypeDef",
     {
         "Events": List[WirelessDeviceEventLogOptionTypeDef],
     },
     total=False,
 )
 
-
 class WirelessDeviceLogOptionTypeDef(
     _RequiredWirelessDeviceLogOptionTypeDef, _OptionalWirelessDeviceLogOptionTypeDef
 ):
     pass
 
-
 _RequiredWirelessGatewayLogOptionTypeDef = TypedDict(
     "_RequiredWirelessGatewayLogOptionTypeDef",
     {
         "Type": Literal["LoRaWAN"],
         "LogLevel": LogLevelType,
     },
 )
@@ -2767,21 +3015,19 @@
     "_OptionalWirelessGatewayLogOptionTypeDef",
     {
         "Events": List[WirelessGatewayEventLogOptionTypeDef],
     },
     total=False,
 )
 
-
 class WirelessGatewayLogOptionTypeDef(
     _RequiredWirelessGatewayLogOptionTypeDef, _OptionalWirelessGatewayLogOptionTypeDef
 ):
     pass
 
-
 _RequiredCreateWirelessGatewayRequestRequestTypeDef = TypedDict(
     "_RequiredCreateWirelessGatewayRequestRequestTypeDef",
     {
         "LoRaWAN": LoRaWANGatewayTypeDef,
     },
 )
 _OptionalCreateWirelessGatewayRequestRequestTypeDef = TypedDict(
@@ -2791,33 +3037,31 @@
         "Description": str,
         "Tags": Sequence[TagTypeDef],
         "ClientRequestToken": str,
     },
     total=False,
 )
 
-
 class CreateWirelessGatewayRequestRequestTypeDef(
     _RequiredCreateWirelessGatewayRequestRequestTypeDef,
     _OptionalCreateWirelessGatewayRequestRequestTypeDef,
 ):
     pass
 
-
 GetWirelessGatewayResponseTypeDef = TypedDict(
     "GetWirelessGatewayResponseTypeDef",
     {
         "Name": str,
         "Id": str,
         "Description": str,
         "LoRaWAN": LoRaWANGatewayTypeDef,
         "Arn": str,
         "ThingName": str,
         "ThingArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 WirelessGatewayStatisticsTypeDef = TypedDict(
     "WirelessGatewayStatisticsTypeDef",
     {
         "Arn": str,
@@ -2844,50 +3088,71 @@
         "FuotaDeviceStatus": FuotaDeviceStatusType,
         "MulticastDeviceStatus": str,
         "McGroupId": int,
     },
     total=False,
 )
 
+GetDeviceProfileResponseTypeDef = TypedDict(
+    "GetDeviceProfileResponseTypeDef",
+    {
+        "Arn": str,
+        "Name": str,
+        "Id": str,
+        "LoRaWAN": LoRaWANDeviceProfileTypeDef,
+        "Sidewalk": SidewalkGetDeviceProfileTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 LoRaWANDeviceTypeDef = TypedDict(
     "LoRaWANDeviceTypeDef",
     {
         "DevEui": str,
         "DeviceProfileId": str,
         "ServiceProfileId": str,
-        "OtaaV1_1": OtaaV1_1TypeDef,
-        "OtaaV1_0_x": OtaaV1_0_xTypeDef,
-        "AbpV1_1": AbpV1_1TypeDef,
-        "AbpV1_0_x": AbpV1_0_xTypeDef,
+        "OtaaV1_1": OtaaV11TypeDef,
+        "OtaaV1_0_x": OtaaV10XTypeDef,
+        "AbpV1_1": AbpV11TypeDef,
+        "AbpV1_0_x": AbpV10XTypeDef,
         "FPorts": FPortsTypeDef,
     },
     total=False,
 )
 
 LoRaWANUpdateDeviceTypeDef = TypedDict(
     "LoRaWANUpdateDeviceTypeDef",
     {
         "DeviceProfileId": str,
         "ServiceProfileId": str,
-        "AbpV1_1": UpdateAbpV1_1TypeDef,
-        "AbpV1_0_x": UpdateAbpV1_0_xTypeDef,
+        "AbpV1_1": UpdateAbpV11TypeDef,
+        "AbpV1_0_x": UpdateAbpV10XTypeDef,
         "FPorts": UpdateFPortsTypeDef,
     },
     total=False,
 )
 
 LoRaWANSendDataToDeviceTypeDef = TypedDict(
     "LoRaWANSendDataToDeviceTypeDef",
     {
         "FPort": int,
         "ParticipatingGateways": ParticipatingGatewaysTypeDef,
     },
     total=False,
 )
 
+ListWirelessDeviceImportTasksResponseTypeDef = TypedDict(
+    "ListWirelessDeviceImportTasksResponseTypeDef",
+    {
+        "NextToken": str,
+        "WirelessDeviceImportTaskList": List[WirelessDeviceImportTaskTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGsmObjTypeDef = TypedDict(
     "_RequiredGsmObjTypeDef",
     {
         "Mcc": int,
         "Mnc": int,
         "Lac": int,
         "GeranCid": int,
@@ -2900,18 +3165,26 @@
         "GsmTimingAdvance": int,
         "RxLevel": int,
         "GsmNmr": Sequence[GsmNmrObjTypeDef],
     },
     total=False,
 )
 
-
 class GsmObjTypeDef(_RequiredGsmObjTypeDef, _OptionalGsmObjTypeDef):
     pass
 
+ListDevicesForWirelessDeviceImportTaskResponseTypeDef = TypedDict(
+    "ListDevicesForWirelessDeviceImportTaskResponseTypeDef",
+    {
+        "NextToken": str,
+        "DestinationName": str,
+        "ImportedWirelessDeviceList": List[ImportedWirelessDeviceTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 EventNotificationItemConfigurationsTypeDef = TypedDict(
     "EventNotificationItemConfigurationsTypeDef",
     {
         "DeviceRegistrationState": DeviceRegistrationStateEventConfigurationTypeDef,
         "Proximity": ProximityEventConfigurationTypeDef,
         "Join": JoinEventConfigurationTypeDef,
@@ -2925,15 +3198,15 @@
     "GetResourceEventConfigurationResponseTypeDef",
     {
         "DeviceRegistrationState": DeviceRegistrationStateEventConfigurationTypeDef,
         "Proximity": ProximityEventConfigurationTypeDef,
         "Join": JoinEventConfigurationTypeDef,
         "ConnectionStatus": ConnectionStatusEventConfigurationTypeDef,
         "MessageDeliveryStatus": MessageDeliveryStatusEventConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateResourceEventConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateResourceEventConfigurationRequestRequestTypeDef",
     {
         "Identifier": str,
@@ -2949,31 +3222,29 @@
         "Join": JoinEventConfigurationTypeDef,
         "ConnectionStatus": ConnectionStatusEventConfigurationTypeDef,
         "MessageDeliveryStatus": MessageDeliveryStatusEventConfigurationTypeDef,
     },
     total=False,
 )
 
-
 class UpdateResourceEventConfigurationRequestRequestTypeDef(
     _RequiredUpdateResourceEventConfigurationRequestRequestTypeDef,
     _OptionalUpdateResourceEventConfigurationRequestRequestTypeDef,
 ):
     pass
 
-
 GetEventConfigurationByResourceTypesResponseTypeDef = TypedDict(
     "GetEventConfigurationByResourceTypesResponseTypeDef",
     {
         "DeviceRegistrationState": DeviceRegistrationStateResourceTypeEventConfigurationTypeDef,
         "Proximity": ProximityResourceTypeEventConfigurationTypeDef,
         "Join": JoinResourceTypeEventConfigurationTypeDef,
         "ConnectionStatus": ConnectionStatusResourceTypeEventConfigurationTypeDef,
         "MessageDeliveryStatus": MessageDeliveryStatusResourceTypeEventConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateEventConfigurationByResourceTypesRequestRequestTypeDef = TypedDict(
     "UpdateEventConfigurationByResourceTypesRequestRequestTypeDef",
     {
         "DeviceRegistrationState": DeviceRegistrationStateResourceTypeEventConfigurationTypeDef,
@@ -2988,23 +3259,23 @@
 GetWirelessDeviceStatisticsResponseTypeDef = TypedDict(
     "GetWirelessDeviceStatisticsResponseTypeDef",
     {
         "WirelessDeviceId": str,
         "LastUplinkReceivedAt": str,
         "LoRaWAN": LoRaWANDeviceMetadataTypeDef,
         "Sidewalk": SidewalkDeviceMetadataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetWirelessGatewayFirmwareInformationResponseTypeDef = TypedDict(
     "GetWirelessGatewayFirmwareInformationResponseTypeDef",
     {
         "LoRaWAN": LoRaWANGatewayCurrentVersionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateWirelessGatewayTaskCreateTypeDef = TypedDict(
     "UpdateWirelessGatewayTaskCreateTypeDef",
     {
         "UpdateDataSource": str,
@@ -3045,28 +3316,26 @@
     {
         "Solvers": PositionSolverConfigurationsTypeDef,
         "Destination": str,
     },
     total=False,
 )
 
-
 class PutPositionConfigurationRequestRequestTypeDef(
     _RequiredPutPositionConfigurationRequestRequestTypeDef,
     _OptionalPutPositionConfigurationRequestRequestTypeDef,
 ):
     pass
 
-
 GetPositionConfigurationResponseTypeDef = TypedDict(
     "GetPositionConfigurationResponseTypeDef",
     {
         "Solvers": PositionSolverDetailsTypeDef,
         "Destination": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PositionConfigurationItemTypeDef = TypedDict(
     "PositionConfigurationItemTypeDef",
     {
         "ResourceIdentifier": str,
@@ -3079,15 +3348,15 @@
 
 GetLogLevelsByResourceTypesResponseTypeDef = TypedDict(
     "GetLogLevelsByResourceTypesResponseTypeDef",
     {
         "DefaultLogLevel": LogLevelType,
         "WirelessGatewayLogOptions": List[WirelessGatewayLogOptionTypeDef],
         "WirelessDeviceLogOptions": List[WirelessDeviceLogOptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateLogLevelsByResourceTypesRequestRequestTypeDef = TypedDict(
     "UpdateLogLevelsByResourceTypesRequestRequestTypeDef",
     {
         "DefaultLogLevel": LogLevelType,
@@ -3098,24 +3367,24 @@
 )
 
 ListWirelessGatewaysResponseTypeDef = TypedDict(
     "ListWirelessGatewaysResponseTypeDef",
     {
         "NextToken": str,
         "WirelessGatewayList": List[WirelessGatewayStatisticsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListWirelessDevicesResponseTypeDef = TypedDict(
     "ListWirelessDevicesResponseTypeDef",
     {
         "NextToken": str,
         "WirelessDeviceList": List[WirelessDeviceStatisticsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateWirelessDeviceRequestRequestTypeDef = TypedDict(
     "_RequiredCreateWirelessDeviceRequestRequestTypeDef",
     {
         "Type": WirelessDeviceTypeType,
@@ -3127,41 +3396,40 @@
     {
         "Name": str,
         "Description": str,
         "ClientRequestToken": str,
         "LoRaWAN": LoRaWANDeviceTypeDef,
         "Tags": Sequence[TagTypeDef],
         "Positioning": PositioningConfigStatusType,
+        "Sidewalk": SidewalkCreateWirelessDeviceTypeDef,
     },
     total=False,
 )
 
-
 class CreateWirelessDeviceRequestRequestTypeDef(
     _RequiredCreateWirelessDeviceRequestRequestTypeDef,
     _OptionalCreateWirelessDeviceRequestRequestTypeDef,
 ):
     pass
 
-
 GetWirelessDeviceResponseTypeDef = TypedDict(
     "GetWirelessDeviceResponseTypeDef",
     {
         "Type": WirelessDeviceTypeType,
         "Name": str,
         "Description": str,
         "DestinationName": str,
         "Id": str,
         "Arn": str,
         "ThingName": str,
         "ThingArn": str,
         "LoRaWAN": LoRaWANDeviceTypeDef,
         "Sidewalk": SidewalkDeviceTypeDef,
         "Positioning": PositioningConfigStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateWirelessDeviceRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateWirelessDeviceRequestRequestTypeDef",
     {
         "Id": str,
@@ -3175,22 +3443,20 @@
         "Description": str,
         "LoRaWAN": LoRaWANUpdateDeviceTypeDef,
         "Positioning": PositioningConfigStatusType,
     },
     total=False,
 )
 
-
 class UpdateWirelessDeviceRequestRequestTypeDef(
     _RequiredUpdateWirelessDeviceRequestRequestTypeDef,
     _OptionalUpdateWirelessDeviceRequestRequestTypeDef,
 ):
     pass
 
-
 DownlinkQueueMessageTypeDef = TypedDict(
     "DownlinkQueueMessageTypeDef",
     {
         "MessageId": str,
         "TransmitMode": int,
         "ReceivedAt": str,
         "LoRaWAN": LoRaWANSendDataToDeviceTypeDef,
@@ -3243,57 +3509,55 @@
         "Update": UpdateWirelessGatewayTaskCreateTypeDef,
         "ClientRequestToken": str,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateWirelessGatewayTaskDefinitionRequestRequestTypeDef(
     _RequiredCreateWirelessGatewayTaskDefinitionRequestRequestTypeDef,
     _OptionalCreateWirelessGatewayTaskDefinitionRequestRequestTypeDef,
 ):
     pass
 
-
 GetWirelessGatewayTaskDefinitionResponseTypeDef = TypedDict(
     "GetWirelessGatewayTaskDefinitionResponseTypeDef",
     {
         "AutoCreateTasks": bool,
         "Name": str,
         "Update": UpdateWirelessGatewayTaskCreateTypeDef,
         "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListWirelessGatewayTaskDefinitionsResponseTypeDef = TypedDict(
     "ListWirelessGatewayTaskDefinitionsResponseTypeDef",
     {
         "NextToken": str,
         "TaskDefinitions": List[UpdateWirelessGatewayTaskEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPositionConfigurationsResponseTypeDef = TypedDict(
     "ListPositionConfigurationsResponseTypeDef",
     {
         "PositionConfigurationList": List[PositionConfigurationItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListQueuedMessagesResponseTypeDef = TypedDict(
     "ListQueuedMessagesResponseTypeDef",
     {
         "NextToken": str,
         "DownlinkQueueMessagesList": List[DownlinkQueueMessageTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSendDataToWirelessDeviceRequestRequestTypeDef = TypedDict(
     "_RequiredSendDataToWirelessDeviceRequestRequestTypeDef",
     {
         "Id": str,
@@ -3305,22 +3569,20 @@
     "_OptionalSendDataToWirelessDeviceRequestRequestTypeDef",
     {
         "WirelessMetadata": WirelessMetadataTypeDef,
     },
     total=False,
 )
 
-
 class SendDataToWirelessDeviceRequestRequestTypeDef(
     _RequiredSendDataToWirelessDeviceRequestRequestTypeDef,
     _OptionalSendDataToWirelessDeviceRequestRequestTypeDef,
 ):
     pass
 
-
 GetPositionEstimateRequestRequestTypeDef = TypedDict(
     "GetPositionEstimateRequestRequestTypeDef",
     {
         "WiFiAccessPoints": Sequence[WiFiAccessPointTypeDef],
         "CellTowers": CellTowersTypeDef,
         "Ip": IpTypeDef,
         "Gnss": GnssTypeDef,
@@ -3330,10 +3592,10 @@
 )
 
 ListEventConfigurationsResponseTypeDef = TypedDict(
     "ListEventConfigurationsResponseTypeDef",
     {
         "NextToken": str,
         "EventConfigurationsList": List[EventConfigurationItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-iotwireless-2.5.0.post1/types_aiobotocore_iotwireless/type_defs.pyi` & `types-aiobotocore-iotwireless-2.5.1/types_aiobotocore_iotwireless/type_defs.py`

 * *Files 6% similar despite different names*

```diff
@@ -2,49 +2,54 @@
 Type annotations for iotwireless service type definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/type_defs/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_iotwireless.type_defs import SessionKeysAbpV1_0_xTypeDef
+    from types_aiobotocore_iotwireless.type_defs import SessionKeysAbpV10XTypeDef
 
-    data: SessionKeysAbpV1_0_xTypeDef = {...}
+    data: SessionKeysAbpV10XTypeDef = {...}
     ```
 """
 import sys
 from datetime import datetime
-from typing import IO, Any, Dict, List, Sequence, Union
+from typing import IO, Any, Dict, List, Mapping, Sequence, Union
 
 from aiobotocore.response import StreamingBody
 
 from .literals import (
     BatteryLevelType,
     ConnectionStatusType,
+    DeviceProfileTypeType,
     DeviceStateType,
     DlClassType,
     DownlinkModeType,
     EventNotificationResourceTypeType,
     EventNotificationTopicStatusType,
     EventType,
     ExpressionTypeType,
     FuotaDeviceStatusType,
     FuotaTaskStatusType,
     IdentifierTypeType,
+    ImportTaskStatusType,
     LogLevelType,
     MessageTypeType,
+    MulticastFrameInfoType,
+    OnboardStatusType,
     PositionConfigurationFecType,
     PositionConfigurationStatusType,
     PositioningConfigStatusType,
     PositionResourceTypeType,
     SigningAlgType,
     SupportedRfRegionType,
     WirelessDeviceEventType,
     WirelessDeviceFrameInfoType,
     WirelessDeviceIdTypeType,
+    WirelessDeviceSidewalkStatusType,
     WirelessDeviceTypeType,
     WirelessGatewayEventType,
     WirelessGatewayIdTypeType,
     WirelessGatewayServiceTypeType,
     WirelessGatewayTaskStatusType,
 )
 
@@ -53,52 +58,67 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
-    "SessionKeysAbpV1_0_xTypeDef",
-    "SessionKeysAbpV1_1TypeDef",
+    "SessionKeysAbpV10XTypeDef",
+    "SessionKeysAbpV11TypeDef",
     "AccuracyTypeDef",
     "ApplicationConfigTypeDef",
     "SidewalkAccountInfoTypeDef",
     "TagTypeDef",
-    "ResponseMetadataTypeDef",
     "AssociateMulticastGroupWithFuotaTaskRequestRequestTypeDef",
     "AssociateWirelessDeviceWithFuotaTaskRequestRequestTypeDef",
     "AssociateWirelessDeviceWithMulticastGroupRequestRequestTypeDef",
     "AssociateWirelessDeviceWithThingRequestRequestTypeDef",
     "AssociateWirelessGatewayWithCertificateRequestRequestTypeDef",
+    "AssociateWirelessGatewayWithCertificateResponseTypeDef",
     "AssociateWirelessGatewayWithThingRequestRequestTypeDef",
     "BeaconingTypeDef",
     "CancelMulticastGroupSessionRequestRequestTypeDef",
     "CdmaLocalIdTypeDef",
     "CdmaNmrObjTypeDef",
     "CertificateListTypeDef",
     "LoRaWANConnectionStatusEventNotificationConfigurationsTypeDef",
     "LoRaWANConnectionStatusResourceTypeEventConfigurationTypeDef",
+    "CreateDestinationResponseTypeDef",
     "LoRaWANDeviceProfileTypeDef",
+    "CreateDeviceProfileResponseTypeDef",
     "LoRaWANFuotaTaskTypeDef",
+    "CreateFuotaTaskResponseTypeDef",
     "LoRaWANMulticastTypeDef",
+    "CreateMulticastGroupResponseTypeDef",
     "TraceContentTypeDef",
+    "CreateNetworkAnalyzerConfigurationResponseTypeDef",
     "LoRaWANServiceProfileTypeDef",
+    "CreateServiceProfileResponseTypeDef",
+    "SidewalkCreateWirelessDeviceTypeDef",
+    "CreateWirelessDeviceResponseTypeDef",
+    "CreateWirelessGatewayResponseTypeDef",
+    "CreateWirelessGatewayTaskDefinitionResponseTypeDef",
     "CreateWirelessGatewayTaskRequestRequestTypeDef",
+    "CreateWirelessGatewayTaskResponseTypeDef",
+    "DakCertificateMetadataTypeDef",
     "DeleteDestinationRequestRequestTypeDef",
     "DeleteDeviceProfileRequestRequestTypeDef",
     "DeleteFuotaTaskRequestRequestTypeDef",
     "DeleteMulticastGroupRequestRequestTypeDef",
     "DeleteNetworkAnalyzerConfigurationRequestRequestTypeDef",
     "DeleteQueuedMessagesRequestRequestTypeDef",
     "DeleteServiceProfileRequestRequestTypeDef",
+    "DeleteWirelessDeviceImportTaskRequestRequestTypeDef",
     "DeleteWirelessDeviceRequestRequestTypeDef",
     "DeleteWirelessGatewayRequestRequestTypeDef",
     "DeleteWirelessGatewayTaskDefinitionRequestRequestTypeDef",
     "DeleteWirelessGatewayTaskRequestRequestTypeDef",
+    "DeregisterWirelessDeviceRequestRequestTypeDef",
     "DestinationsTypeDef",
     "DeviceProfileTypeDef",
     "SidewalkEventNotificationConfigurationsTypeDef",
     "SidewalkResourceTypeEventConfigurationTypeDef",
     "DisassociateAwsAccountFromPartnerAccountRequestRequestTypeDef",
     "DisassociateMulticastGroupFromFuotaTaskRequestRequestTypeDef",
     "DisassociateWirelessDeviceFromFuotaTaskRequestRequestTypeDef",
@@ -106,144 +126,144 @@
     "DisassociateWirelessDeviceFromThingRequestRequestTypeDef",
     "DisassociateWirelessGatewayFromCertificateRequestRequestTypeDef",
     "DisassociateWirelessGatewayFromThingRequestRequestTypeDef",
     "PositioningTypeDef",
     "FuotaTaskTypeDef",
     "GatewayListItemTypeDef",
     "GetDestinationRequestRequestTypeDef",
+    "GetDestinationResponseTypeDef",
     "GetDeviceProfileRequestRequestTypeDef",
     "GetFuotaTaskRequestRequestTypeDef",
     "LoRaWANFuotaTaskGetInfoTypeDef",
     "GetMulticastGroupRequestRequestTypeDef",
     "LoRaWANMulticastGetTypeDef",
     "GetMulticastGroupSessionRequestRequestTypeDef",
     "LoRaWANMulticastSessionTypeDef",
     "GetNetworkAnalyzerConfigurationRequestRequestTypeDef",
     "GetPartnerAccountRequestRequestTypeDef",
     "SidewalkAccountInfoWithFingerprintTypeDef",
     "GetPositionConfigurationRequestRequestTypeDef",
     "GnssTypeDef",
     "IpTypeDef",
     "WiFiAccessPointTypeDef",
+    "GetPositionEstimateResponseTypeDef",
     "GetPositionRequestRequestTypeDef",
     "GetResourceEventConfigurationRequestRequestTypeDef",
     "GetResourceLogLevelRequestRequestTypeDef",
+    "GetResourceLogLevelResponseTypeDef",
     "GetResourcePositionRequestRequestTypeDef",
+    "GetResourcePositionResponseTypeDef",
     "GetServiceEndpointRequestRequestTypeDef",
+    "GetServiceEndpointResponseTypeDef",
     "GetServiceProfileRequestRequestTypeDef",
     "LoRaWANGetServiceProfileInfoTypeDef",
+    "GetWirelessDeviceImportTaskRequestRequestTypeDef",
+    "SidewalkGetStartImportInfoTypeDef",
     "GetWirelessDeviceRequestRequestTypeDef",
     "GetWirelessDeviceStatisticsRequestRequestTypeDef",
     "SidewalkDeviceMetadataTypeDef",
     "GetWirelessGatewayCertificateRequestRequestTypeDef",
+    "GetWirelessGatewayCertificateResponseTypeDef",
     "GetWirelessGatewayFirmwareInformationRequestRequestTypeDef",
     "GetWirelessGatewayRequestRequestTypeDef",
     "GetWirelessGatewayStatisticsRequestRequestTypeDef",
+    "GetWirelessGatewayStatisticsResponseTypeDef",
     "GetWirelessGatewayTaskDefinitionRequestRequestTypeDef",
     "GetWirelessGatewayTaskRequestRequestTypeDef",
+    "GetWirelessGatewayTaskResponseTypeDef",
     "GlobalIdentityTypeDef",
     "GsmLocalIdTypeDef",
+    "ImportedSidewalkDeviceTypeDef",
     "LoRaWANJoinEventNotificationConfigurationsTypeDef",
     "LoRaWANJoinResourceTypeEventConfigurationTypeDef",
     "ListDestinationsRequestRequestTypeDef",
     "ListDeviceProfilesRequestRequestTypeDef",
+    "ListDevicesForWirelessDeviceImportTaskRequestRequestTypeDef",
     "ListEventConfigurationsRequestRequestTypeDef",
     "ListFuotaTasksRequestRequestTypeDef",
     "ListMulticastGroupsByFuotaTaskRequestRequestTypeDef",
     "MulticastGroupByFuotaTaskTypeDef",
     "ListMulticastGroupsRequestRequestTypeDef",
     "MulticastGroupTypeDef",
     "ListNetworkAnalyzerConfigurationsRequestRequestTypeDef",
     "NetworkAnalyzerConfigurationsTypeDef",
     "ListPartnerAccountsRequestRequestTypeDef",
     "ListPositionConfigurationsRequestRequestTypeDef",
     "ListQueuedMessagesRequestRequestTypeDef",
     "ListServiceProfilesRequestRequestTypeDef",
     "ServiceProfileTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListWirelessDeviceImportTasksRequestRequestTypeDef",
     "ListWirelessDevicesRequestRequestTypeDef",
     "ListWirelessGatewayTaskDefinitionsRequestRequestTypeDef",
     "ListWirelessGatewaysRequestRequestTypeDef",
     "LoRaWANGatewayMetadataTypeDef",
-    "OtaaV1_0_xTypeDef",
-    "OtaaV1_1TypeDef",
+    "OtaaV10XTypeDef",
+    "OtaaV11TypeDef",
     "LoRaWANGatewayVersionTypeDef",
     "LoRaWANListDeviceTypeDef",
     "LoRaWANMulticastMetadataTypeDef",
     "LoRaWANStartFuotaTaskTypeDef",
-    "UpdateAbpV1_0_xTypeDef",
-    "UpdateAbpV1_1TypeDef",
+    "UpdateAbpV10XTypeDef",
+    "UpdateAbpV11TypeDef",
     "LteLocalIdTypeDef",
     "LteNmrObjTypeDef",
     "SemtechGnssConfigurationTypeDef",
     "SemtechGnssDetailTypeDef",
     "PutResourceLogLevelRequestRequestTypeDef",
     "ResetResourceLogLevelRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
+    "SendDataToMulticastGroupResponseTypeDef",
+    "SendDataToWirelessDeviceResponseTypeDef",
     "SidewalkSendDataToDeviceTypeDef",
+    "SidewalkSingleStartImportInfoTypeDef",
+    "SidewalkStartImportInfoTypeDef",
     "SidewalkUpdateAccountTypeDef",
+    "SidewalkUpdateImportInfoTypeDef",
+    "StartSingleWirelessDeviceImportTaskResponseTypeDef",
+    "StartWirelessDeviceImportTaskResponseTypeDef",
     "TdscdmaLocalIdTypeDef",
     "TdscdmaNmrObjTypeDef",
     "TestWirelessDeviceRequestRequestTypeDef",
+    "TestWirelessDeviceResponseTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateDestinationRequestRequestTypeDef",
     "UpdatePositionRequestRequestTypeDef",
     "UpdateResourcePositionRequestRequestTypeDef",
     "UpdateWirelessGatewayRequestRequestTypeDef",
     "WcdmaLocalIdTypeDef",
     "WcdmaNmrObjTypeDef",
     "WirelessDeviceEventLogOptionTypeDef",
     "WirelessGatewayEventLogOptionTypeDef",
-    "AbpV1_0_xTypeDef",
-    "AbpV1_1TypeDef",
+    "AbpV10XTypeDef",
+    "AbpV11TypeDef",
+    "GetPositionResponseTypeDef",
+    "AssociateAwsAccountWithPartnerAccountResponseTypeDef",
     "AssociateAwsAccountWithPartnerAccountRequestRequestTypeDef",
     "CreateDestinationRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "StartBulkAssociateWirelessDeviceWithMulticastGroupRequestRequestTypeDef",
     "StartBulkDisassociateWirelessDeviceFromMulticastGroupRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
-    "AssociateAwsAccountWithPartnerAccountResponseTypeDef",
-    "AssociateWirelessGatewayWithCertificateResponseTypeDef",
-    "CreateDestinationResponseTypeDef",
-    "CreateDeviceProfileResponseTypeDef",
-    "CreateFuotaTaskResponseTypeDef",
-    "CreateMulticastGroupResponseTypeDef",
-    "CreateNetworkAnalyzerConfigurationResponseTypeDef",
-    "CreateServiceProfileResponseTypeDef",
-    "CreateWirelessDeviceResponseTypeDef",
-    "CreateWirelessGatewayResponseTypeDef",
-    "CreateWirelessGatewayTaskDefinitionResponseTypeDef",
-    "CreateWirelessGatewayTaskResponseTypeDef",
-    "GetDestinationResponseTypeDef",
-    "GetPositionEstimateResponseTypeDef",
-    "GetPositionResponseTypeDef",
-    "GetResourceLogLevelResponseTypeDef",
-    "GetResourcePositionResponseTypeDef",
-    "GetServiceEndpointResponseTypeDef",
-    "GetWirelessGatewayCertificateResponseTypeDef",
-    "GetWirelessGatewayStatisticsResponseTypeDef",
-    "GetWirelessGatewayTaskResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "SendDataToMulticastGroupResponseTypeDef",
-    "SendDataToWirelessDeviceResponseTypeDef",
-    "TestWirelessDeviceResponseTypeDef",
     "LoRaWANGatewayTypeDef",
     "CdmaObjTypeDef",
     "SidewalkDeviceTypeDef",
     "SidewalkListDeviceTypeDef",
     "ConnectionStatusEventConfigurationTypeDef",
     "ConnectionStatusResourceTypeEventConfigurationTypeDef",
     "CreateDeviceProfileRequestRequestTypeDef",
-    "GetDeviceProfileResponseTypeDef",
     "CreateFuotaTaskRequestRequestTypeDef",
     "UpdateFuotaTaskRequestRequestTypeDef",
     "CreateMulticastGroupRequestRequestTypeDef",
     "UpdateMulticastGroupRequestRequestTypeDef",
     "CreateNetworkAnalyzerConfigurationRequestRequestTypeDef",
     "GetNetworkAnalyzerConfigurationResponseTypeDef",
     "UpdateNetworkAnalyzerConfigurationRequestRequestTypeDef",
     "CreateServiceProfileRequestRequestTypeDef",
+    "SidewalkGetDeviceProfileTypeDef",
     "ListDestinationsResponseTypeDef",
     "ListDeviceProfilesResponseTypeDef",
     "DeviceRegistrationStateEventConfigurationTypeDef",
     "MessageDeliveryStatusEventConfigurationTypeDef",
     "ProximityEventConfigurationTypeDef",
     "DeviceRegistrationStateResourceTypeEventConfigurationTypeDef",
     "MessageDeliveryStatusResourceTypeEventConfigurationTypeDef",
@@ -255,15 +275,18 @@
     "GetFuotaTaskResponseTypeDef",
     "GetMulticastGroupResponseTypeDef",
     "GetMulticastGroupSessionResponseTypeDef",
     "StartMulticastGroupSessionRequestRequestTypeDef",
     "GetPartnerAccountResponseTypeDef",
     "ListPartnerAccountsResponseTypeDef",
     "GetServiceProfileResponseTypeDef",
+    "GetWirelessDeviceImportTaskResponseTypeDef",
+    "WirelessDeviceImportTaskTypeDef",
     "GsmNmrObjTypeDef",
+    "ImportedWirelessDeviceTypeDef",
     "JoinEventConfigurationTypeDef",
     "JoinResourceTypeEventConfigurationTypeDef",
     "ListMulticastGroupsByFuotaTaskResponseTypeDef",
     "ListMulticastGroupsResponseTypeDef",
     "ListNetworkAnalyzerConfigurationsResponseTypeDef",
     "ListServiceProfilesResponseTypeDef",
     "LoRaWANDeviceMetadataTypeDef",
@@ -271,27 +294,33 @@
     "LoRaWANUpdateGatewayTaskCreateTypeDef",
     "LoRaWANUpdateGatewayTaskEntryTypeDef",
     "MulticastWirelessMetadataTypeDef",
     "StartFuotaTaskRequestRequestTypeDef",
     "LteObjTypeDef",
     "PositionSolverConfigurationsTypeDef",
     "PositionSolverDetailsTypeDef",
+    "StartSingleWirelessDeviceImportTaskRequestRequestTypeDef",
+    "StartWirelessDeviceImportTaskRequestRequestTypeDef",
     "UpdatePartnerAccountRequestRequestTypeDef",
+    "UpdateWirelessDeviceImportTaskRequestRequestTypeDef",
     "TdscdmaObjTypeDef",
     "WcdmaObjTypeDef",
     "WirelessDeviceLogOptionTypeDef",
     "WirelessGatewayLogOptionTypeDef",
     "CreateWirelessGatewayRequestRequestTypeDef",
     "GetWirelessGatewayResponseTypeDef",
     "WirelessGatewayStatisticsTypeDef",
     "WirelessDeviceStatisticsTypeDef",
+    "GetDeviceProfileResponseTypeDef",
     "LoRaWANDeviceTypeDef",
     "LoRaWANUpdateDeviceTypeDef",
     "LoRaWANSendDataToDeviceTypeDef",
+    "ListWirelessDeviceImportTasksResponseTypeDef",
     "GsmObjTypeDef",
+    "ListDevicesForWirelessDeviceImportTaskResponseTypeDef",
     "EventNotificationItemConfigurationsTypeDef",
     "GetResourceEventConfigurationResponseTypeDef",
     "UpdateResourceEventConfigurationRequestRequestTypeDef",
     "GetEventConfigurationByResourceTypesResponseTypeDef",
     "UpdateEventConfigurationByResourceTypesRequestRequestTypeDef",
     "GetWirelessDeviceStatisticsResponseTypeDef",
     "GetWirelessGatewayFirmwareInformationResponseTypeDef",
@@ -318,25 +347,25 @@
     "ListPositionConfigurationsResponseTypeDef",
     "ListQueuedMessagesResponseTypeDef",
     "SendDataToWirelessDeviceRequestRequestTypeDef",
     "GetPositionEstimateRequestRequestTypeDef",
     "ListEventConfigurationsResponseTypeDef",
 )
 
-SessionKeysAbpV1_0_xTypeDef = TypedDict(
-    "SessionKeysAbpV1_0_xTypeDef",
+SessionKeysAbpV10XTypeDef = TypedDict(
+    "SessionKeysAbpV10XTypeDef",
     {
         "NwkSKey": str,
         "AppSKey": str,
     },
     total=False,
 )
 
-SessionKeysAbpV1_1TypeDef = TypedDict(
-    "SessionKeysAbpV1_1TypeDef",
+SessionKeysAbpV11TypeDef = TypedDict(
+    "SessionKeysAbpV11TypeDef",
     {
         "FNwkSIntKey": str,
         "SNwkSIntKey": str,
         "NwkSEncKey": str,
         "AppSKey": str,
     },
     total=False,
@@ -374,25 +403,14 @@
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
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
 AssociateMulticastGroupWithFuotaTaskRequestRequestTypeDef = TypedDict(
     "AssociateMulticastGroupWithFuotaTaskRequestRequestTypeDef",
     {
         "Id": str,
         "MulticastGroupId": str,
     },
 )
@@ -425,14 +443,22 @@
     "AssociateWirelessGatewayWithCertificateRequestRequestTypeDef",
     {
         "Id": str,
         "IotCertificateId": str,
     },
 )
 
+AssociateWirelessGatewayWithCertificateResponseTypeDef = TypedDict(
+    "AssociateWirelessGatewayWithCertificateResponseTypeDef",
+    {
+        "IotCertificateId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AssociateWirelessGatewayWithThingRequestRequestTypeDef = TypedDict(
     "AssociateWirelessGatewayWithThingRequestRequestTypeDef",
     {
         "Id": str,
         "ThingArn": str,
     },
 )
@@ -473,17 +499,19 @@
     {
         "PilotPower": int,
         "BaseStationId": int,
     },
     total=False,
 )
 
+
 class CdmaNmrObjTypeDef(_RequiredCdmaNmrObjTypeDef, _OptionalCdmaNmrObjTypeDef):
     pass
 
+
 CertificateListTypeDef = TypedDict(
     "CertificateListTypeDef",
     {
         "SigningAlg": SigningAlgType,
         "Value": str,
     },
 )
@@ -500,14 +528,23 @@
     "LoRaWANConnectionStatusResourceTypeEventConfigurationTypeDef",
     {
         "WirelessGatewayEventTopic": EventNotificationTopicStatusType,
     },
     total=False,
 )
 
+CreateDestinationResponseTypeDef = TypedDict(
+    "CreateDestinationResponseTypeDef",
+    {
+        "Arn": str,
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 LoRaWANDeviceProfileTypeDef = TypedDict(
     "LoRaWANDeviceProfileTypeDef",
     {
         "SupportsClassB": bool,
         "ClassBTimeout": int,
         "PingSlotPeriod": int,
         "PingSlotDr": int,
@@ -526,58 +563,174 @@
         "RfRegion": str,
         "SupportsJoin": bool,
         "Supports32BitFCnt": bool,
     },
     total=False,
 )
 
+CreateDeviceProfileResponseTypeDef = TypedDict(
+    "CreateDeviceProfileResponseTypeDef",
+    {
+        "Arn": str,
+        "Id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 LoRaWANFuotaTaskTypeDef = TypedDict(
     "LoRaWANFuotaTaskTypeDef",
     {
         "RfRegion": SupportedRfRegionType,
     },
     total=False,
 )
 
+CreateFuotaTaskResponseTypeDef = TypedDict(
+    "CreateFuotaTaskResponseTypeDef",
+    {
+        "Arn": str,
+        "Id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 LoRaWANMulticastTypeDef = TypedDict(
     "LoRaWANMulticastTypeDef",
     {
         "RfRegion": SupportedRfRegionType,
         "DlClass": DlClassType,
     },
     total=False,
 )
 
+CreateMulticastGroupResponseTypeDef = TypedDict(
+    "CreateMulticastGroupResponseTypeDef",
+    {
+        "Arn": str,
+        "Id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TraceContentTypeDef = TypedDict(
     "TraceContentTypeDef",
     {
         "WirelessDeviceFrameInfo": WirelessDeviceFrameInfoType,
         "LogLevel": LogLevelType,
+        "MulticastFrameInfo": MulticastFrameInfoType,
     },
     total=False,
 )
 
+CreateNetworkAnalyzerConfigurationResponseTypeDef = TypedDict(
+    "CreateNetworkAnalyzerConfigurationResponseTypeDef",
+    {
+        "Arn": str,
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 LoRaWANServiceProfileTypeDef = TypedDict(
     "LoRaWANServiceProfileTypeDef",
     {
         "AddGwMetadata": bool,
         "DrMin": int,
         "DrMax": int,
+        "PrAllowed": bool,
+        "RaAllowed": bool,
+    },
+    total=False,
+)
+
+CreateServiceProfileResponseTypeDef = TypedDict(
+    "CreateServiceProfileResponseTypeDef",
+    {
+        "Arn": str,
+        "Id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+SidewalkCreateWirelessDeviceTypeDef = TypedDict(
+    "SidewalkCreateWirelessDeviceTypeDef",
+    {
+        "DeviceProfileId": str,
     },
     total=False,
 )
 
+CreateWirelessDeviceResponseTypeDef = TypedDict(
+    "CreateWirelessDeviceResponseTypeDef",
+    {
+        "Arn": str,
+        "Id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateWirelessGatewayResponseTypeDef = TypedDict(
+    "CreateWirelessGatewayResponseTypeDef",
+    {
+        "Arn": str,
+        "Id": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateWirelessGatewayTaskDefinitionResponseTypeDef = TypedDict(
+    "CreateWirelessGatewayTaskDefinitionResponseTypeDef",
+    {
+        "Id": str,
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateWirelessGatewayTaskRequestRequestTypeDef = TypedDict(
     "CreateWirelessGatewayTaskRequestRequestTypeDef",
     {
         "Id": str,
         "WirelessGatewayTaskDefinitionId": str,
     },
 )
 
+CreateWirelessGatewayTaskResponseTypeDef = TypedDict(
+    "CreateWirelessGatewayTaskResponseTypeDef",
+    {
+        "WirelessGatewayTaskDefinitionId": str,
+        "Status": WirelessGatewayTaskStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredDakCertificateMetadataTypeDef = TypedDict(
+    "_RequiredDakCertificateMetadataTypeDef",
+    {
+        "CertificateId": str,
+    },
+)
+_OptionalDakCertificateMetadataTypeDef = TypedDict(
+    "_OptionalDakCertificateMetadataTypeDef",
+    {
+        "MaxAllowedSignature": int,
+        "FactorySupport": bool,
+        "ApId": str,
+        "DeviceTypeId": str,
+    },
+    total=False,
+)
+
+
+class DakCertificateMetadataTypeDef(
+    _RequiredDakCertificateMetadataTypeDef, _OptionalDakCertificateMetadataTypeDef
+):
+    pass
+
+
 DeleteDestinationRequestRequestTypeDef = TypedDict(
     "DeleteDestinationRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
@@ -620,27 +773,36 @@
     "_OptionalDeleteQueuedMessagesRequestRequestTypeDef",
     {
         "WirelessDeviceType": WirelessDeviceTypeType,
     },
     total=False,
 )
 
+
 class DeleteQueuedMessagesRequestRequestTypeDef(
     _RequiredDeleteQueuedMessagesRequestRequestTypeDef,
     _OptionalDeleteQueuedMessagesRequestRequestTypeDef,
 ):
     pass
 
+
 DeleteServiceProfileRequestRequestTypeDef = TypedDict(
     "DeleteServiceProfileRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 
+DeleteWirelessDeviceImportTaskRequestRequestTypeDef = TypedDict(
+    "DeleteWirelessDeviceImportTaskRequestRequestTypeDef",
+    {
+        "Id": str,
+    },
+)
+
 DeleteWirelessDeviceRequestRequestTypeDef = TypedDict(
     "DeleteWirelessDeviceRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 
@@ -661,14 +823,36 @@
 DeleteWirelessGatewayTaskRequestRequestTypeDef = TypedDict(
     "DeleteWirelessGatewayTaskRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 
+_RequiredDeregisterWirelessDeviceRequestRequestTypeDef = TypedDict(
+    "_RequiredDeregisterWirelessDeviceRequestRequestTypeDef",
+    {
+        "Identifier": str,
+    },
+)
+_OptionalDeregisterWirelessDeviceRequestRequestTypeDef = TypedDict(
+    "_OptionalDeregisterWirelessDeviceRequestRequestTypeDef",
+    {
+        "WirelessDeviceType": WirelessDeviceTypeType,
+    },
+    total=False,
+)
+
+
+class DeregisterWirelessDeviceRequestRequestTypeDef(
+    _RequiredDeregisterWirelessDeviceRequestRequestTypeDef,
+    _OptionalDeregisterWirelessDeviceRequestRequestTypeDef,
+):
+    pass
+
+
 DestinationsTypeDef = TypedDict(
     "DestinationsTypeDef",
     {
         "Arn": str,
         "Name": str,
         "ExpressionType": ExpressionTypeType,
         "Expression": str,
@@ -788,14 +972,27 @@
 GetDestinationRequestRequestTypeDef = TypedDict(
     "GetDestinationRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 
+GetDestinationResponseTypeDef = TypedDict(
+    "GetDestinationResponseTypeDef",
+    {
+        "Arn": str,
+        "Name": str,
+        "Expression": str,
+        "ExpressionType": ExpressionTypeType,
+        "Description": str,
+        "RoleArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetDeviceProfileRequestRequestTypeDef = TypedDict(
     "GetDeviceProfileRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 
@@ -843,14 +1040,15 @@
 LoRaWANMulticastSessionTypeDef = TypedDict(
     "LoRaWANMulticastSessionTypeDef",
     {
         "DlDr": int,
         "DlFreq": int,
         "SessionStartTime": datetime,
         "SessionTimeout": int,
+        "PingSlotPeriod": int,
     },
     total=False,
 )
 
 GetNetworkAnalyzerConfigurationRequestRequestTypeDef = TypedDict(
     "GetNetworkAnalyzerConfigurationRequestRequestTypeDef",
     {
@@ -898,17 +1096,19 @@
         "AssistPosition": Sequence[float],
         "AssistAltitude": float,
         "Use2DSolver": bool,
     },
     total=False,
 )
 
+
 class GnssTypeDef(_RequiredGnssTypeDef, _OptionalGnssTypeDef):
     pass
 
+
 IpTypeDef = TypedDict(
     "IpTypeDef",
     {
         "IpAddress": str,
     },
 )
 
@@ -916,14 +1116,22 @@
     "WiFiAccessPointTypeDef",
     {
         "MacAddress": str,
         "Rss": int,
     },
 )
 
+GetPositionEstimateResponseTypeDef = TypedDict(
+    "GetPositionEstimateResponseTypeDef",
+    {
+        "GeoJsonPayload": StreamingBody,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetPositionRequestRequestTypeDef = TypedDict(
     "GetPositionRequestRequestTypeDef",
     {
         "ResourceIdentifier": str,
         "ResourceType": PositionResourceTypeType,
     },
 )
@@ -939,44 +1147,72 @@
     "_OptionalGetResourceEventConfigurationRequestRequestTypeDef",
     {
         "PartnerType": Literal["Sidewalk"],
     },
     total=False,
 )
 
+
 class GetResourceEventConfigurationRequestRequestTypeDef(
     _RequiredGetResourceEventConfigurationRequestRequestTypeDef,
     _OptionalGetResourceEventConfigurationRequestRequestTypeDef,
 ):
     pass
 
+
 GetResourceLogLevelRequestRequestTypeDef = TypedDict(
     "GetResourceLogLevelRequestRequestTypeDef",
     {
         "ResourceIdentifier": str,
         "ResourceType": str,
     },
 )
 
+GetResourceLogLevelResponseTypeDef = TypedDict(
+    "GetResourceLogLevelResponseTypeDef",
+    {
+        "LogLevel": LogLevelType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetResourcePositionRequestRequestTypeDef = TypedDict(
     "GetResourcePositionRequestRequestTypeDef",
     {
         "ResourceIdentifier": str,
         "ResourceType": PositionResourceTypeType,
     },
 )
 
+GetResourcePositionResponseTypeDef = TypedDict(
+    "GetResourcePositionResponseTypeDef",
+    {
+        "GeoJsonPayload": StreamingBody,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetServiceEndpointRequestRequestTypeDef = TypedDict(
     "GetServiceEndpointRequestRequestTypeDef",
     {
         "ServiceType": WirelessGatewayServiceTypeType,
     },
     total=False,
 )
 
+GetServiceEndpointResponseTypeDef = TypedDict(
+    "GetServiceEndpointResponseTypeDef",
+    {
+        "ServiceType": WirelessGatewayServiceTypeType,
+        "ServiceEndpoint": str,
+        "ServerTrust": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetServiceProfileRequestRequestTypeDef = TypedDict(
     "GetServiceProfileRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 
@@ -1002,14 +1238,30 @@
         "NwkGeoLoc": bool,
         "TargetPer": int,
         "MinGwDiversity": int,
     },
     total=False,
 )
 
+GetWirelessDeviceImportTaskRequestRequestTypeDef = TypedDict(
+    "GetWirelessDeviceImportTaskRequestRequestTypeDef",
+    {
+        "Id": str,
+    },
+)
+
+SidewalkGetStartImportInfoTypeDef = TypedDict(
+    "SidewalkGetStartImportInfoTypeDef",
+    {
+        "DeviceCreationFileList": List[str],
+        "Role": str,
+    },
+    total=False,
+)
+
 GetWirelessDeviceRequestRequestTypeDef = TypedDict(
     "GetWirelessDeviceRequestRequestTypeDef",
     {
         "Identifier": str,
         "IdentifierType": WirelessDeviceIdTypeType,
     },
 )
@@ -1035,14 +1287,23 @@
 GetWirelessGatewayCertificateRequestRequestTypeDef = TypedDict(
     "GetWirelessGatewayCertificateRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 
+GetWirelessGatewayCertificateResponseTypeDef = TypedDict(
+    "GetWirelessGatewayCertificateResponseTypeDef",
+    {
+        "IotCertificateId": str,
+        "LoRaWANNetworkServerCertificateId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetWirelessGatewayFirmwareInformationRequestRequestTypeDef = TypedDict(
     "GetWirelessGatewayFirmwareInformationRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 
@@ -1057,28 +1318,50 @@
 GetWirelessGatewayStatisticsRequestRequestTypeDef = TypedDict(
     "GetWirelessGatewayStatisticsRequestRequestTypeDef",
     {
         "WirelessGatewayId": str,
     },
 )
 
+GetWirelessGatewayStatisticsResponseTypeDef = TypedDict(
+    "GetWirelessGatewayStatisticsResponseTypeDef",
+    {
+        "WirelessGatewayId": str,
+        "LastUplinkReceivedAt": str,
+        "ConnectionStatus": ConnectionStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetWirelessGatewayTaskDefinitionRequestRequestTypeDef = TypedDict(
     "GetWirelessGatewayTaskDefinitionRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 
 GetWirelessGatewayTaskRequestRequestTypeDef = TypedDict(
     "GetWirelessGatewayTaskRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 
+GetWirelessGatewayTaskResponseTypeDef = TypedDict(
+    "GetWirelessGatewayTaskResponseTypeDef",
+    {
+        "WirelessGatewayId": str,
+        "WirelessGatewayTaskDefinitionId": str,
+        "LastUplinkReceivedAt": str,
+        "TaskCreatedAt": str,
+        "Status": WirelessGatewayTaskStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GlobalIdentityTypeDef = TypedDict(
     "GlobalIdentityTypeDef",
     {
         "Lac": int,
         "GeranCid": int,
     },
 )
@@ -1087,14 +1370,25 @@
     "GsmLocalIdTypeDef",
     {
         "Bsic": int,
         "Bcch": int,
     },
 )
 
+ImportedSidewalkDeviceTypeDef = TypedDict(
+    "ImportedSidewalkDeviceTypeDef",
+    {
+        "SidewalkManufacturingSn": str,
+        "OnboardingStatus": OnboardStatusType,
+        "OnboardingStatusReason": str,
+        "LastUpdateTime": datetime,
+    },
+    total=False,
+)
+
 LoRaWANJoinEventNotificationConfigurationsTypeDef = TypedDict(
     "LoRaWANJoinEventNotificationConfigurationsTypeDef",
     {
         "DevEuiEventTopic": EventNotificationTopicStatusType,
     },
     total=False,
 )
@@ -1117,18 +1411,43 @@
 )
 
 ListDeviceProfilesRequestRequestTypeDef = TypedDict(
     "ListDeviceProfilesRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
+        "DeviceProfileType": DeviceProfileTypeType,
     },
     total=False,
 )
 
+_RequiredListDevicesForWirelessDeviceImportTaskRequestRequestTypeDef = TypedDict(
+    "_RequiredListDevicesForWirelessDeviceImportTaskRequestRequestTypeDef",
+    {
+        "Id": str,
+    },
+)
+_OptionalListDevicesForWirelessDeviceImportTaskRequestRequestTypeDef = TypedDict(
+    "_OptionalListDevicesForWirelessDeviceImportTaskRequestRequestTypeDef",
+    {
+        "MaxResults": int,
+        "NextToken": str,
+        "Status": OnboardStatusType,
+    },
+    total=False,
+)
+
+
+class ListDevicesForWirelessDeviceImportTaskRequestRequestTypeDef(
+    _RequiredListDevicesForWirelessDeviceImportTaskRequestRequestTypeDef,
+    _OptionalListDevicesForWirelessDeviceImportTaskRequestRequestTypeDef,
+):
+    pass
+
+
 _RequiredListEventConfigurationsRequestRequestTypeDef = TypedDict(
     "_RequiredListEventConfigurationsRequestRequestTypeDef",
     {
         "ResourceType": EventNotificationResourceTypeType,
     },
 )
 _OptionalListEventConfigurationsRequestRequestTypeDef = TypedDict(
@@ -1136,20 +1455,22 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class ListEventConfigurationsRequestRequestTypeDef(
     _RequiredListEventConfigurationsRequestRequestTypeDef,
     _OptionalListEventConfigurationsRequestRequestTypeDef,
 ):
     pass
 
+
 ListFuotaTasksRequestRequestTypeDef = TypedDict(
     "ListFuotaTasksRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
@@ -1166,20 +1487,22 @@
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
 )
 
+
 class ListMulticastGroupsByFuotaTaskRequestRequestTypeDef(
     _RequiredListMulticastGroupsByFuotaTaskRequestRequestTypeDef,
     _OptionalListMulticastGroupsByFuotaTaskRequestRequestTypeDef,
 ):
     pass
 
+
 MulticastGroupByFuotaTaskTypeDef = TypedDict(
     "MulticastGroupByFuotaTaskTypeDef",
     {
         "Id": str,
     },
     total=False,
 )
@@ -1252,20 +1575,22 @@
         "NextToken": str,
         "MaxResults": int,
         "WirelessDeviceType": WirelessDeviceTypeType,
     },
     total=False,
 )
 
+
 class ListQueuedMessagesRequestRequestTypeDef(
     _RequiredListQueuedMessagesRequestRequestTypeDef,
     _OptionalListQueuedMessagesRequestRequestTypeDef,
 ):
     pass
 
+
 ListServiceProfilesRequestRequestTypeDef = TypedDict(
     "ListServiceProfilesRequestRequestTypeDef",
     {
         "NextToken": str,
         "MaxResults": int,
     },
     total=False,
@@ -1284,14 +1609,23 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+ListWirelessDeviceImportTasksRequestRequestTypeDef = TypedDict(
+    "ListWirelessDeviceImportTasksRequestRequestTypeDef",
+    {
+        "MaxResults": int,
+        "NextToken": str,
+    },
+    total=False,
+)
+
 ListWirelessDevicesRequestRequestTypeDef = TypedDict(
     "ListWirelessDevicesRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
         "DestinationName": str,
         "DeviceProfileId": str,
@@ -1328,26 +1662,26 @@
         "GatewayEui": str,
         "Snr": float,
         "Rssi": float,
     },
     total=False,
 )
 
-OtaaV1_0_xTypeDef = TypedDict(
-    "OtaaV1_0_xTypeDef",
+OtaaV10XTypeDef = TypedDict(
+    "OtaaV10XTypeDef",
     {
         "AppKey": str,
         "AppEui": str,
         "GenAppKey": str,
     },
     total=False,
 )
 
-OtaaV1_1TypeDef = TypedDict(
-    "OtaaV1_1TypeDef",
+OtaaV11TypeDef = TypedDict(
+    "OtaaV11TypeDef",
     {
         "AppKey": str,
         "NwkKey": str,
         "JoinEui": str,
     },
     total=False,
 )
@@ -1382,24 +1716,24 @@
     "LoRaWANStartFuotaTaskTypeDef",
     {
         "StartTime": Union[datetime, str],
     },
     total=False,
 )
 
-UpdateAbpV1_0_xTypeDef = TypedDict(
-    "UpdateAbpV1_0_xTypeDef",
+UpdateAbpV10XTypeDef = TypedDict(
+    "UpdateAbpV10XTypeDef",
     {
         "FCntStart": int,
     },
     total=False,
 )
 
-UpdateAbpV1_1TypeDef = TypedDict(
-    "UpdateAbpV1_1TypeDef",
+UpdateAbpV11TypeDef = TypedDict(
+    "UpdateAbpV11TypeDef",
     {
         "FCntStart": int,
     },
     total=False,
 )
 
 LteLocalIdTypeDef = TypedDict(
@@ -1423,17 +1757,19 @@
     {
         "Rsrp": int,
         "Rsrq": float,
     },
     total=False,
 )
 
+
 class LteNmrObjTypeDef(_RequiredLteNmrObjTypeDef, _OptionalLteNmrObjTypeDef):
     pass
 
+
 SemtechGnssConfigurationTypeDef = TypedDict(
     "SemtechGnssConfigurationTypeDef",
     {
         "Status": PositionConfigurationStatusType,
         "Fec": PositionConfigurationFecType,
     },
 )
@@ -1462,32 +1798,102 @@
     "ResetResourceLogLevelRequestRequestTypeDef",
     {
         "ResourceIdentifier": str,
         "ResourceType": str,
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
+SendDataToMulticastGroupResponseTypeDef = TypedDict(
+    "SendDataToMulticastGroupResponseTypeDef",
+    {
+        "MessageId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+SendDataToWirelessDeviceResponseTypeDef = TypedDict(
+    "SendDataToWirelessDeviceResponseTypeDef",
+    {
+        "MessageId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 SidewalkSendDataToDeviceTypeDef = TypedDict(
     "SidewalkSendDataToDeviceTypeDef",
     {
         "Seq": int,
         "MessageType": MessageTypeType,
         "AckModeRetryDurationSecs": int,
     },
     total=False,
 )
 
+SidewalkSingleStartImportInfoTypeDef = TypedDict(
+    "SidewalkSingleStartImportInfoTypeDef",
+    {
+        "SidewalkManufacturingSn": str,
+    },
+    total=False,
+)
+
+SidewalkStartImportInfoTypeDef = TypedDict(
+    "SidewalkStartImportInfoTypeDef",
+    {
+        "DeviceCreationFile": str,
+        "Role": str,
+    },
+    total=False,
+)
+
 SidewalkUpdateAccountTypeDef = TypedDict(
     "SidewalkUpdateAccountTypeDef",
     {
         "AppServerPrivateKey": str,
     },
     total=False,
 )
 
+SidewalkUpdateImportInfoTypeDef = TypedDict(
+    "SidewalkUpdateImportInfoTypeDef",
+    {
+        "DeviceCreationFile": str,
+    },
+    total=False,
+)
+
+StartSingleWirelessDeviceImportTaskResponseTypeDef = TypedDict(
+    "StartSingleWirelessDeviceImportTaskResponseTypeDef",
+    {
+        "Id": str,
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartWirelessDeviceImportTaskResponseTypeDef = TypedDict(
+    "StartWirelessDeviceImportTaskResponseTypeDef",
+    {
+        "Id": str,
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TdscdmaLocalIdTypeDef = TypedDict(
     "TdscdmaLocalIdTypeDef",
     {
         "Uarfcn": int,
         "CellParams": int,
     },
 )
@@ -1505,24 +1911,34 @@
         "UtranCid": int,
         "Rscp": int,
         "PathLoss": int,
     },
     total=False,
 )
 
+
 class TdscdmaNmrObjTypeDef(_RequiredTdscdmaNmrObjTypeDef, _OptionalTdscdmaNmrObjTypeDef):
     pass
 
+
 TestWirelessDeviceRequestRequestTypeDef = TypedDict(
     "TestWirelessDeviceRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 
+TestWirelessDeviceResponseTypeDef = TypedDict(
+    "TestWirelessDeviceResponseTypeDef",
+    {
+        "Result": str,
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
@@ -1540,19 +1956,21 @@
         "Expression": str,
         "Description": str,
         "RoleArn": str,
     },
     total=False,
 )
 
+
 class UpdateDestinationRequestRequestTypeDef(
     _RequiredUpdateDestinationRequestRequestTypeDef, _OptionalUpdateDestinationRequestRequestTypeDef
 ):
     pass
 
+
 UpdatePositionRequestRequestTypeDef = TypedDict(
     "UpdatePositionRequestRequestTypeDef",
     {
         "ResourceIdentifier": str,
         "ResourceType": PositionResourceTypeType,
         "Position": Sequence[float],
     },
@@ -1569,43 +1987,48 @@
     "_OptionalUpdateResourcePositionRequestRequestTypeDef",
     {
         "GeoJsonPayload": Union[str, bytes, IO[Any], StreamingBody],
     },
     total=False,
 )
 
+
 class UpdateResourcePositionRequestRequestTypeDef(
     _RequiredUpdateResourcePositionRequestRequestTypeDef,
     _OptionalUpdateResourcePositionRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredUpdateWirelessGatewayRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateWirelessGatewayRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 _OptionalUpdateWirelessGatewayRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateWirelessGatewayRequestRequestTypeDef",
     {
         "Name": str,
         "Description": str,
         "JoinEuiFilters": Sequence[Sequence[str]],
         "NetIdFilters": Sequence[str],
+        "MaxEirp": float,
     },
     total=False,
 )
 
+
 class UpdateWirelessGatewayRequestRequestTypeDef(
     _RequiredUpdateWirelessGatewayRequestRequestTypeDef,
     _OptionalUpdateWirelessGatewayRequestRequestTypeDef,
 ):
     pass
 
+
 WcdmaLocalIdTypeDef = TypedDict(
     "WcdmaLocalIdTypeDef",
     {
         "Uarfcndl": int,
         "Psc": int,
     },
 )
@@ -1623,17 +2046,19 @@
     {
         "Rscp": int,
         "PathLoss": int,
     },
     total=False,
 )
 
+
 class WcdmaNmrObjTypeDef(_RequiredWcdmaNmrObjTypeDef, _OptionalWcdmaNmrObjTypeDef):
     pass
 
+
 WirelessDeviceEventLogOptionTypeDef = TypedDict(
     "WirelessDeviceEventLogOptionTypeDef",
     {
         "Event": WirelessDeviceEventType,
         "LogLevel": LogLevelType,
     },
 )
@@ -1642,34 +2067,56 @@
     "WirelessGatewayEventLogOptionTypeDef",
     {
         "Event": WirelessGatewayEventType,
         "LogLevel": LogLevelType,
     },
 )
 
-AbpV1_0_xTypeDef = TypedDict(
-    "AbpV1_0_xTypeDef",
+AbpV10XTypeDef = TypedDict(
+    "AbpV10XTypeDef",
     {
         "DevAddr": str,
-        "SessionKeys": SessionKeysAbpV1_0_xTypeDef,
+        "SessionKeys": SessionKeysAbpV10XTypeDef,
         "FCntStart": int,
     },
     total=False,
 )
 
-AbpV1_1TypeDef = TypedDict(
-    "AbpV1_1TypeDef",
+AbpV11TypeDef = TypedDict(
+    "AbpV11TypeDef",
     {
         "DevAddr": str,
-        "SessionKeys": SessionKeysAbpV1_1TypeDef,
+        "SessionKeys": SessionKeysAbpV11TypeDef,
         "FCntStart": int,
     },
     total=False,
 )
 
+GetPositionResponseTypeDef = TypedDict(
+    "GetPositionResponseTypeDef",
+    {
+        "Position": List[float],
+        "Accuracy": AccuracyTypeDef,
+        "SolverType": Literal["GNSS"],
+        "SolverProvider": Literal["Semtech"],
+        "SolverVersion": str,
+        "Timestamp": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+AssociateAwsAccountWithPartnerAccountResponseTypeDef = TypedDict(
+    "AssociateAwsAccountWithPartnerAccountResponseTypeDef",
+    {
+        "Sidewalk": SidewalkAccountInfoTypeDef,
+        "Arn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredAssociateAwsAccountWithPartnerAccountRequestRequestTypeDef = TypedDict(
     "_RequiredAssociateAwsAccountWithPartnerAccountRequestRequestTypeDef",
     {
         "Sidewalk": SidewalkAccountInfoTypeDef,
     },
 )
 _OptionalAssociateAwsAccountWithPartnerAccountRequestRequestTypeDef = TypedDict(
@@ -1677,20 +2124,22 @@
     {
         "ClientRequestToken": str,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class AssociateAwsAccountWithPartnerAccountRequestRequestTypeDef(
     _RequiredAssociateAwsAccountWithPartnerAccountRequestRequestTypeDef,
     _OptionalAssociateAwsAccountWithPartnerAccountRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredCreateDestinationRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDestinationRequestRequestTypeDef",
     {
         "Name": str,
         "ExpressionType": ExpressionTypeType,
         "Expression": str,
         "RoleArn": str,
@@ -1702,19 +2151,29 @@
         "Description": str,
         "Tags": Sequence[TagTypeDef],
         "ClientRequestToken": str,
     },
     total=False,
 )
 
+
 class CreateDestinationRequestRequestTypeDef(
     _RequiredCreateDestinationRequestRequestTypeDef, _OptionalCreateDestinationRequestRequestTypeDef
 ):
     pass
 
+
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "Tags": List[TagTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredStartBulkAssociateWirelessDeviceWithMulticastGroupRequestRequestTypeDef = TypedDict(
     "_RequiredStartBulkAssociateWirelessDeviceWithMulticastGroupRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 _OptionalStartBulkAssociateWirelessDeviceWithMulticastGroupRequestRequestTypeDef = TypedDict(
@@ -1722,20 +2181,22 @@
     {
         "QueryString": str,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class StartBulkAssociateWirelessDeviceWithMulticastGroupRequestRequestTypeDef(
     _RequiredStartBulkAssociateWirelessDeviceWithMulticastGroupRequestRequestTypeDef,
     _OptionalStartBulkAssociateWirelessDeviceWithMulticastGroupRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredStartBulkDisassociateWirelessDeviceFromMulticastGroupRequestRequestTypeDef = TypedDict(
     "_RequiredStartBulkDisassociateWirelessDeviceFromMulticastGroupRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 _OptionalStartBulkDisassociateWirelessDeviceFromMulticastGroupRequestRequestTypeDef = TypedDict(
@@ -1743,267 +2204,40 @@
     {
         "QueryString": str,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class StartBulkDisassociateWirelessDeviceFromMulticastGroupRequestRequestTypeDef(
     _RequiredStartBulkDisassociateWirelessDeviceFromMulticastGroupRequestRequestTypeDef,
     _OptionalStartBulkDisassociateWirelessDeviceFromMulticastGroupRequestRequestTypeDef,
 ):
     pass
 
+
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "Tags": Sequence[TagTypeDef],
     },
 )
 
-AssociateAwsAccountWithPartnerAccountResponseTypeDef = TypedDict(
-    "AssociateAwsAccountWithPartnerAccountResponseTypeDef",
-    {
-        "Sidewalk": SidewalkAccountInfoTypeDef,
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-AssociateWirelessGatewayWithCertificateResponseTypeDef = TypedDict(
-    "AssociateWirelessGatewayWithCertificateResponseTypeDef",
-    {
-        "IotCertificateId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDestinationResponseTypeDef = TypedDict(
-    "CreateDestinationResponseTypeDef",
-    {
-        "Arn": str,
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDeviceProfileResponseTypeDef = TypedDict(
-    "CreateDeviceProfileResponseTypeDef",
-    {
-        "Arn": str,
-        "Id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateFuotaTaskResponseTypeDef = TypedDict(
-    "CreateFuotaTaskResponseTypeDef",
-    {
-        "Arn": str,
-        "Id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateMulticastGroupResponseTypeDef = TypedDict(
-    "CreateMulticastGroupResponseTypeDef",
-    {
-        "Arn": str,
-        "Id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateNetworkAnalyzerConfigurationResponseTypeDef = TypedDict(
-    "CreateNetworkAnalyzerConfigurationResponseTypeDef",
-    {
-        "Arn": str,
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateServiceProfileResponseTypeDef = TypedDict(
-    "CreateServiceProfileResponseTypeDef",
-    {
-        "Arn": str,
-        "Id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateWirelessDeviceResponseTypeDef = TypedDict(
-    "CreateWirelessDeviceResponseTypeDef",
-    {
-        "Arn": str,
-        "Id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateWirelessGatewayResponseTypeDef = TypedDict(
-    "CreateWirelessGatewayResponseTypeDef",
-    {
-        "Arn": str,
-        "Id": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateWirelessGatewayTaskDefinitionResponseTypeDef = TypedDict(
-    "CreateWirelessGatewayTaskDefinitionResponseTypeDef",
-    {
-        "Id": str,
-        "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateWirelessGatewayTaskResponseTypeDef = TypedDict(
-    "CreateWirelessGatewayTaskResponseTypeDef",
-    {
-        "WirelessGatewayTaskDefinitionId": str,
-        "Status": WirelessGatewayTaskStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetDestinationResponseTypeDef = TypedDict(
-    "GetDestinationResponseTypeDef",
-    {
-        "Arn": str,
-        "Name": str,
-        "Expression": str,
-        "ExpressionType": ExpressionTypeType,
-        "Description": str,
-        "RoleArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetPositionEstimateResponseTypeDef = TypedDict(
-    "GetPositionEstimateResponseTypeDef",
-    {
-        "GeoJsonPayload": StreamingBody,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetPositionResponseTypeDef = TypedDict(
-    "GetPositionResponseTypeDef",
-    {
-        "Position": List[float],
-        "Accuracy": AccuracyTypeDef,
-        "SolverType": Literal["GNSS"],
-        "SolverProvider": Literal["Semtech"],
-        "SolverVersion": str,
-        "Timestamp": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetResourceLogLevelResponseTypeDef = TypedDict(
-    "GetResourceLogLevelResponseTypeDef",
-    {
-        "LogLevel": LogLevelType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetResourcePositionResponseTypeDef = TypedDict(
-    "GetResourcePositionResponseTypeDef",
-    {
-        "GeoJsonPayload": StreamingBody,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetServiceEndpointResponseTypeDef = TypedDict(
-    "GetServiceEndpointResponseTypeDef",
-    {
-        "ServiceType": WirelessGatewayServiceTypeType,
-        "ServiceEndpoint": str,
-        "ServerTrust": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetWirelessGatewayCertificateResponseTypeDef = TypedDict(
-    "GetWirelessGatewayCertificateResponseTypeDef",
-    {
-        "IotCertificateId": str,
-        "LoRaWANNetworkServerCertificateId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetWirelessGatewayStatisticsResponseTypeDef = TypedDict(
-    "GetWirelessGatewayStatisticsResponseTypeDef",
-    {
-        "WirelessGatewayId": str,
-        "LastUplinkReceivedAt": str,
-        "ConnectionStatus": ConnectionStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetWirelessGatewayTaskResponseTypeDef = TypedDict(
-    "GetWirelessGatewayTaskResponseTypeDef",
-    {
-        "WirelessGatewayId": str,
-        "WirelessGatewayTaskDefinitionId": str,
-        "LastUplinkReceivedAt": str,
-        "TaskCreatedAt": str,
-        "Status": WirelessGatewayTaskStatusType,
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
-SendDataToMulticastGroupResponseTypeDef = TypedDict(
-    "SendDataToMulticastGroupResponseTypeDef",
-    {
-        "MessageId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SendDataToWirelessDeviceResponseTypeDef = TypedDict(
-    "SendDataToWirelessDeviceResponseTypeDef",
-    {
-        "MessageId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-TestWirelessDeviceResponseTypeDef = TypedDict(
-    "TestWirelessDeviceResponseTypeDef",
-    {
-        "Result": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 LoRaWANGatewayTypeDef = TypedDict(
     "LoRaWANGatewayTypeDef",
     {
         "GatewayEui": str,
         "RfRegion": str,
         "JoinEuiFilters": Sequence[Sequence[str]],
         "NetIdFilters": Sequence[str],
         "SubBands": Sequence[int],
         "Beaconing": BeaconingTypeDef,
+        "MaxEirp": float,
     },
     total=False,
 )
 
 _RequiredCdmaObjTypeDef = TypedDict(
     "_RequiredCdmaObjTypeDef",
     {
@@ -2021,35 +2255,43 @@
         "BaseLat": float,
         "BaseLng": float,
         "CdmaNmr": Sequence[CdmaNmrObjTypeDef],
     },
     total=False,
 )
 
+
 class CdmaObjTypeDef(_RequiredCdmaObjTypeDef, _OptionalCdmaObjTypeDef):
     pass
 
+
 SidewalkDeviceTypeDef = TypedDict(
     "SidewalkDeviceTypeDef",
     {
         "AmazonId": str,
         "SidewalkId": str,
         "SidewalkManufacturingSn": str,
         "DeviceCertificates": List[CertificateListTypeDef],
+        "PrivateKeys": List[CertificateListTypeDef],
+        "DeviceProfileId": str,
+        "CertificateId": str,
+        "Status": WirelessDeviceSidewalkStatusType,
     },
     total=False,
 )
 
 SidewalkListDeviceTypeDef = TypedDict(
     "SidewalkListDeviceTypeDef",
     {
         "AmazonId": str,
         "SidewalkId": str,
         "SidewalkManufacturingSn": str,
         "DeviceCertificates": List[CertificateListTypeDef],
+        "DeviceProfileId": str,
+        "Status": WirelessDeviceSidewalkStatusType,
     },
     total=False,
 )
 
 ConnectionStatusEventConfigurationTypeDef = TypedDict(
     "ConnectionStatusEventConfigurationTypeDef",
     {
@@ -2070,29 +2312,19 @@
 CreateDeviceProfileRequestRequestTypeDef = TypedDict(
     "CreateDeviceProfileRequestRequestTypeDef",
     {
         "Name": str,
         "LoRaWAN": LoRaWANDeviceProfileTypeDef,
         "Tags": Sequence[TagTypeDef],
         "ClientRequestToken": str,
+        "Sidewalk": Mapping[str, Any],
     },
     total=False,
 )
 
-GetDeviceProfileResponseTypeDef = TypedDict(
-    "GetDeviceProfileResponseTypeDef",
-    {
-        "Arn": str,
-        "Name": str,
-        "Id": str,
-        "LoRaWAN": LoRaWANDeviceProfileTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 _RequiredCreateFuotaTaskRequestRequestTypeDef = TypedDict(
     "_RequiredCreateFuotaTaskRequestRequestTypeDef",
     {
         "FirmwareUpdateImage": str,
         "FirmwareUpdateRole": str,
     },
 )
@@ -2100,46 +2332,56 @@
     "_OptionalCreateFuotaTaskRequestRequestTypeDef",
     {
         "Name": str,
         "Description": str,
         "ClientRequestToken": str,
         "LoRaWAN": LoRaWANFuotaTaskTypeDef,
         "Tags": Sequence[TagTypeDef],
+        "RedundancyPercent": int,
+        "FragmentSizeBytes": int,
+        "FragmentIntervalMS": int,
     },
     total=False,
 )
 
+
 class CreateFuotaTaskRequestRequestTypeDef(
     _RequiredCreateFuotaTaskRequestRequestTypeDef, _OptionalCreateFuotaTaskRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredUpdateFuotaTaskRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateFuotaTaskRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 _OptionalUpdateFuotaTaskRequestRequestTypeDef = TypedDict(
     "_OptionalUpdateFuotaTaskRequestRequestTypeDef",
     {
         "Name": str,
         "Description": str,
         "LoRaWAN": LoRaWANFuotaTaskTypeDef,
         "FirmwareUpdateImage": str,
         "FirmwareUpdateRole": str,
+        "RedundancyPercent": int,
+        "FragmentSizeBytes": int,
+        "FragmentIntervalMS": int,
     },
     total=False,
 )
 
+
 class UpdateFuotaTaskRequestRequestTypeDef(
     _RequiredUpdateFuotaTaskRequestRequestTypeDef, _OptionalUpdateFuotaTaskRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredCreateMulticastGroupRequestRequestTypeDef = TypedDict(
     "_RequiredCreateMulticastGroupRequestRequestTypeDef",
     {
         "LoRaWAN": LoRaWANMulticastTypeDef,
     },
 )
 _OptionalCreateMulticastGroupRequestRequestTypeDef = TypedDict(
@@ -2149,20 +2391,22 @@
         "Description": str,
         "ClientRequestToken": str,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateMulticastGroupRequestRequestTypeDef(
     _RequiredCreateMulticastGroupRequestRequestTypeDef,
     _OptionalCreateMulticastGroupRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredUpdateMulticastGroupRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateMulticastGroupRequestRequestTypeDef",
     {
         "Id": str,
     },
 )
 _OptionalUpdateMulticastGroupRequestRequestTypeDef = TypedDict(
@@ -2171,20 +2415,22 @@
         "Name": str,
         "Description": str,
         "LoRaWAN": LoRaWANMulticastTypeDef,
     },
     total=False,
 )
 
+
 class UpdateMulticastGroupRequestRequestTypeDef(
     _RequiredUpdateMulticastGroupRequestRequestTypeDef,
     _OptionalUpdateMulticastGroupRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredCreateNetworkAnalyzerConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredCreateNetworkAnalyzerConfigurationRequestRequestTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalCreateNetworkAnalyzerConfigurationRequestRequestTypeDef = TypedDict(
@@ -2192,34 +2438,38 @@
     {
         "TraceContent": TraceContentTypeDef,
         "WirelessDevices": Sequence[str],
         "WirelessGateways": Sequence[str],
         "Description": str,
         "Tags": Sequence[TagTypeDef],
         "ClientRequestToken": str,
+        "MulticastGroups": Sequence[str],
     },
     total=False,
 )
 
+
 class CreateNetworkAnalyzerConfigurationRequestRequestTypeDef(
     _RequiredCreateNetworkAnalyzerConfigurationRequestRequestTypeDef,
     _OptionalCreateNetworkAnalyzerConfigurationRequestRequestTypeDef,
 ):
     pass
 
+
 GetNetworkAnalyzerConfigurationResponseTypeDef = TypedDict(
     "GetNetworkAnalyzerConfigurationResponseTypeDef",
     {
         "TraceContent": TraceContentTypeDef,
         "WirelessDevices": List[str],
         "WirelessGateways": List[str],
         "Description": str,
         "Arn": str,
         "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "MulticastGroups": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateNetworkAnalyzerConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateNetworkAnalyzerConfigurationRequestRequestTypeDef",
     {
         "ConfigurationName": str,
@@ -2230,50 +2480,64 @@
     {
         "TraceContent": TraceContentTypeDef,
         "WirelessDevicesToAdd": Sequence[str],
         "WirelessDevicesToRemove": Sequence[str],
         "WirelessGatewaysToAdd": Sequence[str],
         "WirelessGatewaysToRemove": Sequence[str],
         "Description": str,
+        "MulticastGroupsToAdd": Sequence[str],
+        "MulticastGroupsToRemove": Sequence[str],
     },
     total=False,
 )
 
+
 class UpdateNetworkAnalyzerConfigurationRequestRequestTypeDef(
     _RequiredUpdateNetworkAnalyzerConfigurationRequestRequestTypeDef,
     _OptionalUpdateNetworkAnalyzerConfigurationRequestRequestTypeDef,
 ):
     pass
 
+
 CreateServiceProfileRequestRequestTypeDef = TypedDict(
     "CreateServiceProfileRequestRequestTypeDef",
     {
         "Name": str,
         "LoRaWAN": LoRaWANServiceProfileTypeDef,
         "Tags": Sequence[TagTypeDef],
         "ClientRequestToken": str,
     },
     total=False,
 )
 
+SidewalkGetDeviceProfileTypeDef = TypedDict(
+    "SidewalkGetDeviceProfileTypeDef",
+    {
+        "ApplicationServerPublicKey": str,
+        "QualificationStatus": bool,
+        "DakCertificateMetadata": List[DakCertificateMetadataTypeDef],
+    },
+    total=False,
+)
+
 ListDestinationsResponseTypeDef = TypedDict(
     "ListDestinationsResponseTypeDef",
     {
         "NextToken": str,
         "DestinationList": List[DestinationsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDeviceProfilesResponseTypeDef = TypedDict(
     "ListDeviceProfilesResponseTypeDef",
     {
         "NextToken": str,
         "DeviceProfileList": List[DeviceProfileTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeviceRegistrationStateEventConfigurationTypeDef = TypedDict(
     "DeviceRegistrationStateEventConfigurationTypeDef",
     {
         "Sidewalk": SidewalkEventNotificationConfigurationsTypeDef,
@@ -2346,15 +2610,15 @@
 )
 
 ListFuotaTasksResponseTypeDef = TypedDict(
     "ListFuotaTasksResponseTypeDef",
     {
         "NextToken": str,
         "FuotaTaskList": List[FuotaTaskTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ParticipatingGatewaysTypeDef = TypedDict(
     "ParticipatingGatewaysTypeDef",
     {
         "DownlinkMode": DownlinkModeType,
@@ -2371,37 +2635,40 @@
         "Status": FuotaTaskStatusType,
         "Name": str,
         "Description": str,
         "LoRaWAN": LoRaWANFuotaTaskGetInfoTypeDef,
         "FirmwareUpdateImage": str,
         "FirmwareUpdateRole": str,
         "CreatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RedundancyPercent": int,
+        "FragmentSizeBytes": int,
+        "FragmentIntervalMS": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMulticastGroupResponseTypeDef = TypedDict(
     "GetMulticastGroupResponseTypeDef",
     {
         "Arn": str,
         "Id": str,
         "Name": str,
         "Description": str,
         "Status": str,
         "LoRaWAN": LoRaWANMulticastGetTypeDef,
         "CreatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetMulticastGroupSessionResponseTypeDef = TypedDict(
     "GetMulticastGroupSessionResponseTypeDef",
     {
         "LoRaWAN": LoRaWANMulticastSessionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartMulticastGroupSessionRequestRequestTypeDef = TypedDict(
     "StartMulticastGroupSessionRequestRequestTypeDef",
     {
         "Id": str,
@@ -2410,36 +2677,72 @@
 )
 
 GetPartnerAccountResponseTypeDef = TypedDict(
     "GetPartnerAccountResponseTypeDef",
     {
         "Sidewalk": SidewalkAccountInfoWithFingerprintTypeDef,
         "AccountLinked": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPartnerAccountsResponseTypeDef = TypedDict(
     "ListPartnerAccountsResponseTypeDef",
     {
         "NextToken": str,
         "Sidewalk": List[SidewalkAccountInfoWithFingerprintTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetServiceProfileResponseTypeDef = TypedDict(
     "GetServiceProfileResponseTypeDef",
     {
         "Arn": str,
         "Name": str,
         "Id": str,
         "LoRaWAN": LoRaWANGetServiceProfileInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetWirelessDeviceImportTaskResponseTypeDef = TypedDict(
+    "GetWirelessDeviceImportTaskResponseTypeDef",
+    {
+        "Id": str,
+        "Arn": str,
+        "DestinationName": str,
+        "Sidewalk": SidewalkGetStartImportInfoTypeDef,
+        "CreationTime": datetime,
+        "Status": ImportTaskStatusType,
+        "StatusReason": str,
+        "InitializedImportedDeviceCount": int,
+        "PendingImportedDeviceCount": int,
+        "OnboardedImportedDeviceCount": int,
+        "FailedImportedDeviceCount": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+WirelessDeviceImportTaskTypeDef = TypedDict(
+    "WirelessDeviceImportTaskTypeDef",
+    {
+        "Id": str,
+        "Arn": str,
+        "DestinationName": str,
+        "Sidewalk": SidewalkGetStartImportInfoTypeDef,
+        "CreationTime": datetime,
+        "Status": ImportTaskStatusType,
+        "StatusReason": str,
+        "InitializedImportedDeviceCount": int,
+        "PendingImportedDeviceCount": int,
+        "OnboardedImportedDeviceCount": int,
+        "FailedImportedDeviceCount": int,
     },
+    total=False,
 )
 
 _RequiredGsmNmrObjTypeDef = TypedDict(
     "_RequiredGsmNmrObjTypeDef",
     {
         "Bsic": int,
         "Bcch": int,
@@ -2450,17 +2753,27 @@
     {
         "RxLevel": int,
         "GlobalIdentity": GlobalIdentityTypeDef,
     },
     total=False,
 )
 
+
 class GsmNmrObjTypeDef(_RequiredGsmNmrObjTypeDef, _OptionalGsmNmrObjTypeDef):
     pass
 
+
+ImportedWirelessDeviceTypeDef = TypedDict(
+    "ImportedWirelessDeviceTypeDef",
+    {
+        "Sidewalk": ImportedSidewalkDeviceTypeDef,
+    },
+    total=False,
+)
+
 JoinEventConfigurationTypeDef = TypedDict(
     "JoinEventConfigurationTypeDef",
     {
         "LoRaWAN": LoRaWANJoinEventNotificationConfigurationsTypeDef,
         "WirelessDeviceIdEventTopic": EventNotificationTopicStatusType,
     },
     total=False,
@@ -2475,42 +2788,42 @@
 )
 
 ListMulticastGroupsByFuotaTaskResponseTypeDef = TypedDict(
     "ListMulticastGroupsByFuotaTaskResponseTypeDef",
     {
         "NextToken": str,
         "MulticastGroupList": List[MulticastGroupByFuotaTaskTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListMulticastGroupsResponseTypeDef = TypedDict(
     "ListMulticastGroupsResponseTypeDef",
     {
         "NextToken": str,
         "MulticastGroupList": List[MulticastGroupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListNetworkAnalyzerConfigurationsResponseTypeDef = TypedDict(
     "ListNetworkAnalyzerConfigurationsResponseTypeDef",
     {
         "NextToken": str,
         "NetworkAnalyzerConfigurationList": List[NetworkAnalyzerConfigurationsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListServiceProfilesResponseTypeDef = TypedDict(
     "ListServiceProfilesResponseTypeDef",
     {
         "NextToken": str,
         "ServiceProfileList": List[ServiceProfileTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LoRaWANDeviceMetadataTypeDef = TypedDict(
     "LoRaWANDeviceMetadataTypeDef",
     {
         "DevEui": str,
@@ -2569,19 +2882,21 @@
     "_OptionalStartFuotaTaskRequestRequestTypeDef",
     {
         "LoRaWAN": LoRaWANStartFuotaTaskTypeDef,
     },
     total=False,
 )
 
+
 class StartFuotaTaskRequestRequestTypeDef(
     _RequiredStartFuotaTaskRequestRequestTypeDef, _OptionalStartFuotaTaskRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredLteObjTypeDef = TypedDict(
     "_RequiredLteObjTypeDef",
     {
         "Mcc": int,
         "Mnc": int,
         "EutranCid": int,
     },
@@ -2596,17 +2911,19 @@
         "Rsrq": float,
         "NrCapable": bool,
         "LteNmr": Sequence[LteNmrObjTypeDef],
     },
     total=False,
 )
 
+
 class LteObjTypeDef(_RequiredLteObjTypeDef, _OptionalLteObjTypeDef):
     pass
 
+
 PositionSolverConfigurationsTypeDef = TypedDict(
     "PositionSolverConfigurationsTypeDef",
     {
         "SemtechGnss": SemtechGnssConfigurationTypeDef,
     },
     total=False,
 )
@@ -2615,23 +2932,80 @@
     "PositionSolverDetailsTypeDef",
     {
         "SemtechGnss": SemtechGnssDetailTypeDef,
     },
     total=False,
 )
 
+_RequiredStartSingleWirelessDeviceImportTaskRequestRequestTypeDef = TypedDict(
+    "_RequiredStartSingleWirelessDeviceImportTaskRequestRequestTypeDef",
+    {
+        "DestinationName": str,
+        "Sidewalk": SidewalkSingleStartImportInfoTypeDef,
+    },
+)
+_OptionalStartSingleWirelessDeviceImportTaskRequestRequestTypeDef = TypedDict(
+    "_OptionalStartSingleWirelessDeviceImportTaskRequestRequestTypeDef",
+    {
+        "ClientRequestToken": str,
+        "DeviceName": str,
+        "Tags": Sequence[TagTypeDef],
+    },
+    total=False,
+)
+
+
+class StartSingleWirelessDeviceImportTaskRequestRequestTypeDef(
+    _RequiredStartSingleWirelessDeviceImportTaskRequestRequestTypeDef,
+    _OptionalStartSingleWirelessDeviceImportTaskRequestRequestTypeDef,
+):
+    pass
+
+
+_RequiredStartWirelessDeviceImportTaskRequestRequestTypeDef = TypedDict(
+    "_RequiredStartWirelessDeviceImportTaskRequestRequestTypeDef",
+    {
+        "DestinationName": str,
+        "Sidewalk": SidewalkStartImportInfoTypeDef,
+    },
+)
+_OptionalStartWirelessDeviceImportTaskRequestRequestTypeDef = TypedDict(
+    "_OptionalStartWirelessDeviceImportTaskRequestRequestTypeDef",
+    {
+        "ClientRequestToken": str,
+        "Tags": Sequence[TagTypeDef],
+    },
+    total=False,
+)
+
+
+class StartWirelessDeviceImportTaskRequestRequestTypeDef(
+    _RequiredStartWirelessDeviceImportTaskRequestRequestTypeDef,
+    _OptionalStartWirelessDeviceImportTaskRequestRequestTypeDef,
+):
+    pass
+
+
 UpdatePartnerAccountRequestRequestTypeDef = TypedDict(
     "UpdatePartnerAccountRequestRequestTypeDef",
     {
         "Sidewalk": SidewalkUpdateAccountTypeDef,
         "PartnerAccountId": str,
         "PartnerType": Literal["Sidewalk"],
     },
 )
 
+UpdateWirelessDeviceImportTaskRequestRequestTypeDef = TypedDict(
+    "UpdateWirelessDeviceImportTaskRequestRequestTypeDef",
+    {
+        "Id": str,
+        "Sidewalk": SidewalkUpdateImportInfoTypeDef,
+    },
+)
+
 _RequiredTdscdmaObjTypeDef = TypedDict(
     "_RequiredTdscdmaObjTypeDef",
     {
         "Mcc": int,
         "Mnc": int,
         "UtranCid": int,
     },
@@ -2645,17 +3019,19 @@
         "Rscp": int,
         "PathLoss": int,
         "TdscdmaNmr": Sequence[TdscdmaNmrObjTypeDef],
     },
     total=False,
 )
 
+
 class TdscdmaObjTypeDef(_RequiredTdscdmaObjTypeDef, _OptionalTdscdmaObjTypeDef):
     pass
 
+
 _RequiredWcdmaObjTypeDef = TypedDict(
     "_RequiredWcdmaObjTypeDef",
     {
         "Mcc": int,
         "Mnc": int,
         "UtranCid": int,
     },
@@ -2668,17 +3044,19 @@
         "Rscp": int,
         "PathLoss": int,
         "WcdmaNmr": Sequence[WcdmaNmrObjTypeDef],
     },
     total=False,
 )
 
+
 class WcdmaObjTypeDef(_RequiredWcdmaObjTypeDef, _OptionalWcdmaObjTypeDef):
     pass
 
+
 _RequiredWirelessDeviceLogOptionTypeDef = TypedDict(
     "_RequiredWirelessDeviceLogOptionTypeDef",
     {
         "Type": WirelessDeviceTypeType,
         "LogLevel": LogLevelType,
     },
 )
@@ -2686,19 +3064,21 @@
     "_OptionalWirelessDeviceLogOptionTypeDef",
     {
         "Events": List[WirelessDeviceEventLogOptionTypeDef],
     },
     total=False,
 )
 
+
 class WirelessDeviceLogOptionTypeDef(
     _RequiredWirelessDeviceLogOptionTypeDef, _OptionalWirelessDeviceLogOptionTypeDef
 ):
     pass
 
+
 _RequiredWirelessGatewayLogOptionTypeDef = TypedDict(
     "_RequiredWirelessGatewayLogOptionTypeDef",
     {
         "Type": Literal["LoRaWAN"],
         "LogLevel": LogLevelType,
     },
 )
@@ -2706,19 +3086,21 @@
     "_OptionalWirelessGatewayLogOptionTypeDef",
     {
         "Events": List[WirelessGatewayEventLogOptionTypeDef],
     },
     total=False,
 )
 
+
 class WirelessGatewayLogOptionTypeDef(
     _RequiredWirelessGatewayLogOptionTypeDef, _OptionalWirelessGatewayLogOptionTypeDef
 ):
     pass
 
+
 _RequiredCreateWirelessGatewayRequestRequestTypeDef = TypedDict(
     "_RequiredCreateWirelessGatewayRequestRequestTypeDef",
     {
         "LoRaWAN": LoRaWANGatewayTypeDef,
     },
 )
 _OptionalCreateWirelessGatewayRequestRequestTypeDef = TypedDict(
@@ -2728,31 +3110,33 @@
         "Description": str,
         "Tags": Sequence[TagTypeDef],
         "ClientRequestToken": str,
     },
     total=False,
 )
 
+
 class CreateWirelessGatewayRequestRequestTypeDef(
     _RequiredCreateWirelessGatewayRequestRequestTypeDef,
     _OptionalCreateWirelessGatewayRequestRequestTypeDef,
 ):
     pass
 
+
 GetWirelessGatewayResponseTypeDef = TypedDict(
     "GetWirelessGatewayResponseTypeDef",
     {
         "Name": str,
         "Id": str,
         "Description": str,
         "LoRaWAN": LoRaWANGatewayTypeDef,
         "Arn": str,
         "ThingName": str,
         "ThingArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 WirelessGatewayStatisticsTypeDef = TypedDict(
     "WirelessGatewayStatisticsTypeDef",
     {
         "Arn": str,
@@ -2779,50 +3163,71 @@
         "FuotaDeviceStatus": FuotaDeviceStatusType,
         "MulticastDeviceStatus": str,
         "McGroupId": int,
     },
     total=False,
 )
 
+GetDeviceProfileResponseTypeDef = TypedDict(
+    "GetDeviceProfileResponseTypeDef",
+    {
+        "Arn": str,
+        "Name": str,
+        "Id": str,
+        "LoRaWAN": LoRaWANDeviceProfileTypeDef,
+        "Sidewalk": SidewalkGetDeviceProfileTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 LoRaWANDeviceTypeDef = TypedDict(
     "LoRaWANDeviceTypeDef",
     {
         "DevEui": str,
         "DeviceProfileId": str,
         "ServiceProfileId": str,
-        "OtaaV1_1": OtaaV1_1TypeDef,
-        "OtaaV1_0_x": OtaaV1_0_xTypeDef,
-        "AbpV1_1": AbpV1_1TypeDef,
-        "AbpV1_0_x": AbpV1_0_xTypeDef,
+        "OtaaV1_1": OtaaV11TypeDef,
+        "OtaaV1_0_x": OtaaV10XTypeDef,
+        "AbpV1_1": AbpV11TypeDef,
+        "AbpV1_0_x": AbpV10XTypeDef,
         "FPorts": FPortsTypeDef,
     },
     total=False,
 )
 
 LoRaWANUpdateDeviceTypeDef = TypedDict(
     "LoRaWANUpdateDeviceTypeDef",
     {
         "DeviceProfileId": str,
         "ServiceProfileId": str,
-        "AbpV1_1": UpdateAbpV1_1TypeDef,
-        "AbpV1_0_x": UpdateAbpV1_0_xTypeDef,
+        "AbpV1_1": UpdateAbpV11TypeDef,
+        "AbpV1_0_x": UpdateAbpV10XTypeDef,
         "FPorts": UpdateFPortsTypeDef,
     },
     total=False,
 )
 
 LoRaWANSendDataToDeviceTypeDef = TypedDict(
     "LoRaWANSendDataToDeviceTypeDef",
     {
         "FPort": int,
         "ParticipatingGateways": ParticipatingGatewaysTypeDef,
     },
     total=False,
 )
 
+ListWirelessDeviceImportTasksResponseTypeDef = TypedDict(
+    "ListWirelessDeviceImportTasksResponseTypeDef",
+    {
+        "NextToken": str,
+        "WirelessDeviceImportTaskList": List[WirelessDeviceImportTaskTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGsmObjTypeDef = TypedDict(
     "_RequiredGsmObjTypeDef",
     {
         "Mcc": int,
         "Mnc": int,
         "Lac": int,
         "GeranCid": int,
@@ -2835,17 +3240,29 @@
         "GsmTimingAdvance": int,
         "RxLevel": int,
         "GsmNmr": Sequence[GsmNmrObjTypeDef],
     },
     total=False,
 )
 
+
 class GsmObjTypeDef(_RequiredGsmObjTypeDef, _OptionalGsmObjTypeDef):
     pass
 
+
+ListDevicesForWirelessDeviceImportTaskResponseTypeDef = TypedDict(
+    "ListDevicesForWirelessDeviceImportTaskResponseTypeDef",
+    {
+        "NextToken": str,
+        "DestinationName": str,
+        "ImportedWirelessDeviceList": List[ImportedWirelessDeviceTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EventNotificationItemConfigurationsTypeDef = TypedDict(
     "EventNotificationItemConfigurationsTypeDef",
     {
         "DeviceRegistrationState": DeviceRegistrationStateEventConfigurationTypeDef,
         "Proximity": ProximityEventConfigurationTypeDef,
         "Join": JoinEventConfigurationTypeDef,
         "ConnectionStatus": ConnectionStatusEventConfigurationTypeDef,
@@ -2858,15 +3275,15 @@
     "GetResourceEventConfigurationResponseTypeDef",
     {
         "DeviceRegistrationState": DeviceRegistrationStateEventConfigurationTypeDef,
         "Proximity": ProximityEventConfigurationTypeDef,
         "Join": JoinEventConfigurationTypeDef,
         "ConnectionStatus": ConnectionStatusEventConfigurationTypeDef,
         "MessageDeliveryStatus": MessageDeliveryStatusEventConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateResourceEventConfigurationRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateResourceEventConfigurationRequestRequestTypeDef",
     {
         "Identifier": str,
@@ -2882,29 +3299,31 @@
         "Join": JoinEventConfigurationTypeDef,
         "ConnectionStatus": ConnectionStatusEventConfigurationTypeDef,
         "MessageDeliveryStatus": MessageDeliveryStatusEventConfigurationTypeDef,
     },
     total=False,
 )
 
+
 class UpdateResourceEventConfigurationRequestRequestTypeDef(
     _RequiredUpdateResourceEventConfigurationRequestRequestTypeDef,
     _OptionalUpdateResourceEventConfigurationRequestRequestTypeDef,
 ):
     pass
 
+
 GetEventConfigurationByResourceTypesResponseTypeDef = TypedDict(
     "GetEventConfigurationByResourceTypesResponseTypeDef",
     {
         "DeviceRegistrationState": DeviceRegistrationStateResourceTypeEventConfigurationTypeDef,
         "Proximity": ProximityResourceTypeEventConfigurationTypeDef,
         "Join": JoinResourceTypeEventConfigurationTypeDef,
         "ConnectionStatus": ConnectionStatusResourceTypeEventConfigurationTypeDef,
         "MessageDeliveryStatus": MessageDeliveryStatusResourceTypeEventConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateEventConfigurationByResourceTypesRequestRequestTypeDef = TypedDict(
     "UpdateEventConfigurationByResourceTypesRequestRequestTypeDef",
     {
         "DeviceRegistrationState": DeviceRegistrationStateResourceTypeEventConfigurationTypeDef,
@@ -2919,23 +3338,23 @@
 GetWirelessDeviceStatisticsResponseTypeDef = TypedDict(
     "GetWirelessDeviceStatisticsResponseTypeDef",
     {
         "WirelessDeviceId": str,
         "LastUplinkReceivedAt": str,
         "LoRaWAN": LoRaWANDeviceMetadataTypeDef,
         "Sidewalk": SidewalkDeviceMetadataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetWirelessGatewayFirmwareInformationResponseTypeDef = TypedDict(
     "GetWirelessGatewayFirmwareInformationResponseTypeDef",
     {
         "LoRaWAN": LoRaWANGatewayCurrentVersionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateWirelessGatewayTaskCreateTypeDef = TypedDict(
     "UpdateWirelessGatewayTaskCreateTypeDef",
     {
         "UpdateDataSource": str,
@@ -2976,26 +3395,28 @@
     {
         "Solvers": PositionSolverConfigurationsTypeDef,
         "Destination": str,
     },
     total=False,
 )
 
+
 class PutPositionConfigurationRequestRequestTypeDef(
     _RequiredPutPositionConfigurationRequestRequestTypeDef,
     _OptionalPutPositionConfigurationRequestRequestTypeDef,
 ):
     pass
 
+
 GetPositionConfigurationResponseTypeDef = TypedDict(
     "GetPositionConfigurationResponseTypeDef",
     {
         "Solvers": PositionSolverDetailsTypeDef,
         "Destination": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PositionConfigurationItemTypeDef = TypedDict(
     "PositionConfigurationItemTypeDef",
     {
         "ResourceIdentifier": str,
@@ -3008,15 +3429,15 @@
 
 GetLogLevelsByResourceTypesResponseTypeDef = TypedDict(
     "GetLogLevelsByResourceTypesResponseTypeDef",
     {
         "DefaultLogLevel": LogLevelType,
         "WirelessGatewayLogOptions": List[WirelessGatewayLogOptionTypeDef],
         "WirelessDeviceLogOptions": List[WirelessDeviceLogOptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateLogLevelsByResourceTypesRequestRequestTypeDef = TypedDict(
     "UpdateLogLevelsByResourceTypesRequestRequestTypeDef",
     {
         "DefaultLogLevel": LogLevelType,
@@ -3027,24 +3448,24 @@
 )
 
 ListWirelessGatewaysResponseTypeDef = TypedDict(
     "ListWirelessGatewaysResponseTypeDef",
     {
         "NextToken": str,
         "WirelessGatewayList": List[WirelessGatewayStatisticsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListWirelessDevicesResponseTypeDef = TypedDict(
     "ListWirelessDevicesResponseTypeDef",
     {
         "NextToken": str,
         "WirelessDeviceList": List[WirelessDeviceStatisticsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateWirelessDeviceRequestRequestTypeDef = TypedDict(
     "_RequiredCreateWirelessDeviceRequestRequestTypeDef",
     {
         "Type": WirelessDeviceTypeType,
@@ -3056,39 +3477,42 @@
     {
         "Name": str,
         "Description": str,
         "ClientRequestToken": str,
         "LoRaWAN": LoRaWANDeviceTypeDef,
         "Tags": Sequence[TagTypeDef],
         "Positioning": PositioningConfigStatusType,
+        "Sidewalk": SidewalkCreateWirelessDeviceTypeDef,
     },
     total=False,
 )
 
+
 class CreateWirelessDeviceRequestRequestTypeDef(
     _RequiredCreateWirelessDeviceRequestRequestTypeDef,
     _OptionalCreateWirelessDeviceRequestRequestTypeDef,
 ):
     pass
 
+
 GetWirelessDeviceResponseTypeDef = TypedDict(
     "GetWirelessDeviceResponseTypeDef",
     {
         "Type": WirelessDeviceTypeType,
         "Name": str,
         "Description": str,
         "DestinationName": str,
         "Id": str,
         "Arn": str,
         "ThingName": str,
         "ThingArn": str,
         "LoRaWAN": LoRaWANDeviceTypeDef,
         "Sidewalk": SidewalkDeviceTypeDef,
         "Positioning": PositioningConfigStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateWirelessDeviceRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateWirelessDeviceRequestRequestTypeDef",
     {
         "Id": str,
@@ -3102,20 +3526,22 @@
         "Description": str,
         "LoRaWAN": LoRaWANUpdateDeviceTypeDef,
         "Positioning": PositioningConfigStatusType,
     },
     total=False,
 )
 
+
 class UpdateWirelessDeviceRequestRequestTypeDef(
     _RequiredUpdateWirelessDeviceRequestRequestTypeDef,
     _OptionalUpdateWirelessDeviceRequestRequestTypeDef,
 ):
     pass
 
+
 DownlinkQueueMessageTypeDef = TypedDict(
     "DownlinkQueueMessageTypeDef",
     {
         "MessageId": str,
         "TransmitMode": int,
         "ReceivedAt": str,
         "LoRaWAN": LoRaWANSendDataToDeviceTypeDef,
@@ -3168,55 +3594,57 @@
         "Update": UpdateWirelessGatewayTaskCreateTypeDef,
         "ClientRequestToken": str,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateWirelessGatewayTaskDefinitionRequestRequestTypeDef(
     _RequiredCreateWirelessGatewayTaskDefinitionRequestRequestTypeDef,
     _OptionalCreateWirelessGatewayTaskDefinitionRequestRequestTypeDef,
 ):
     pass
 
+
 GetWirelessGatewayTaskDefinitionResponseTypeDef = TypedDict(
     "GetWirelessGatewayTaskDefinitionResponseTypeDef",
     {
         "AutoCreateTasks": bool,
         "Name": str,
         "Update": UpdateWirelessGatewayTaskCreateTypeDef,
         "Arn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListWirelessGatewayTaskDefinitionsResponseTypeDef = TypedDict(
     "ListWirelessGatewayTaskDefinitionsResponseTypeDef",
     {
         "NextToken": str,
         "TaskDefinitions": List[UpdateWirelessGatewayTaskEntryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPositionConfigurationsResponseTypeDef = TypedDict(
     "ListPositionConfigurationsResponseTypeDef",
     {
         "PositionConfigurationList": List[PositionConfigurationItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListQueuedMessagesResponseTypeDef = TypedDict(
     "ListQueuedMessagesResponseTypeDef",
     {
         "NextToken": str,
         "DownlinkQueueMessagesList": List[DownlinkQueueMessageTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredSendDataToWirelessDeviceRequestRequestTypeDef = TypedDict(
     "_RequiredSendDataToWirelessDeviceRequestRequestTypeDef",
     {
         "Id": str,
@@ -3228,20 +3656,22 @@
     "_OptionalSendDataToWirelessDeviceRequestRequestTypeDef",
     {
         "WirelessMetadata": WirelessMetadataTypeDef,
     },
     total=False,
 )
 
+
 class SendDataToWirelessDeviceRequestRequestTypeDef(
     _RequiredSendDataToWirelessDeviceRequestRequestTypeDef,
     _OptionalSendDataToWirelessDeviceRequestRequestTypeDef,
 ):
     pass
 
+
 GetPositionEstimateRequestRequestTypeDef = TypedDict(
     "GetPositionEstimateRequestRequestTypeDef",
     {
         "WiFiAccessPoints": Sequence[WiFiAccessPointTypeDef],
         "CellTowers": CellTowersTypeDef,
         "Ip": IpTypeDef,
         "Gnss": GnssTypeDef,
@@ -3251,10 +3681,10 @@
 )
 
 ListEventConfigurationsResponseTypeDef = TypedDict(
     "ListEventConfigurationsResponseTypeDef",
     {
         "NextToken": str,
         "EventConfigurationsList": List[EventConfigurationItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-iotwireless-2.5.0.post1/types_aiobotocore_iotwireless.egg-info/PKG-INFO` & `types-aiobotocore-iotwireless-2.5.1/types_aiobotocore_iotwireless.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-iotwireless
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.IoTWireless 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.IoTWireless 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-iotwireless"></a>
 
 # types-aiobotocore-iotwireless
 
 [![PyPI - types-aiobotocore-iotwireless](https://img.shields.io/pypi/v/types-aiobotocore-iotwireless.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotwireless)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iotwireless.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iotwireless)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iotwireless?color=blue)](https://pypistats.org/packages/types-aiobotocore-iotwireless)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoTWireless 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless)
+[aiobotocore.IoTWireless 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iotwireless.html#IoTWireless)
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
 [types-aiobotocore-iotwireless docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/).
 
 See how it helps to find and fix potential bugs:
 
@@ -272,39 +272,44 @@
 from shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_iotwireless.literals import (
     ApplicationConfigTypeType,
     BatteryLevelType,
     ConnectionStatusType,
+    DeviceProfileTypeType,
     DeviceStateType,
     DlClassType,
     DownlinkModeType,
     EventNotificationPartnerTypeType,
     EventNotificationResourceTypeType,
     EventNotificationTopicStatusType,
     EventType,
     ExpressionTypeType,
     FuotaDeviceStatusType,
     FuotaTaskStatusType,
     IdentifierTypeType,
+    ImportTaskStatusType,
     LogLevelType,
     MessageTypeType,
+    MulticastFrameInfoType,
+    OnboardStatusType,
     PartnerTypeType,
     PositionConfigurationFecType,
     PositionConfigurationStatusType,
     PositionResourceTypeType,
     PositionSolverProviderType,
     PositionSolverTypeType,
     PositioningConfigStatusType,
     SigningAlgType,
     SupportedRfRegionType,
     WirelessDeviceEventType,
     WirelessDeviceFrameInfoType,
     WirelessDeviceIdTypeType,
+    WirelessDeviceSidewalkStatusType,
     WirelessDeviceTypeType,
     WirelessGatewayEventType,
     WirelessGatewayIdTypeType,
     WirelessGatewayServiceTypeType,
     WirelessGatewayTaskDefinitionTypeType,
     WirelessGatewayTaskStatusType,
     WirelessGatewayTypeType,
@@ -324,51 +329,65 @@
 ### Typed dictionaries
 
 `types_aiobotocore_iotwireless.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_iotwireless.type_defs import (
-    SessionKeysAbpV1_0_xTypeDef,
-    SessionKeysAbpV1_1TypeDef,
+    SessionKeysAbpV10XTypeDef,
+    SessionKeysAbpV11TypeDef,
     AccuracyTypeDef,
     ApplicationConfigTypeDef,
     SidewalkAccountInfoTypeDef,
     TagTypeDef,
-    ResponseMetadataTypeDef,
     AssociateMulticastGroupWithFuotaTaskRequestRequestTypeDef,
     AssociateWirelessDeviceWithFuotaTaskRequestRequestTypeDef,
     AssociateWirelessDeviceWithMulticastGroupRequestRequestTypeDef,
     AssociateWirelessDeviceWithThingRequestRequestTypeDef,
     AssociateWirelessGatewayWithCertificateRequestRequestTypeDef,
+    AssociateWirelessGatewayWithCertificateResponseTypeDef,
     AssociateWirelessGatewayWithThingRequestRequestTypeDef,
     BeaconingTypeDef,
     CancelMulticastGroupSessionRequestRequestTypeDef,
     CdmaLocalIdTypeDef,
     CdmaNmrObjTypeDef,
     CertificateListTypeDef,
     LoRaWANConnectionStatusEventNotificationConfigurationsTypeDef,
     LoRaWANConnectionStatusResourceTypeEventConfigurationTypeDef,
+    CreateDestinationResponseTypeDef,
     LoRaWANDeviceProfileTypeDef,
+    CreateDeviceProfileResponseTypeDef,
     LoRaWANFuotaTaskTypeDef,
+    CreateFuotaTaskResponseTypeDef,
     LoRaWANMulticastTypeDef,
+    CreateMulticastGroupResponseTypeDef,
     TraceContentTypeDef,
+    CreateNetworkAnalyzerConfigurationResponseTypeDef,
     LoRaWANServiceProfileTypeDef,
+    CreateServiceProfileResponseTypeDef,
+    SidewalkCreateWirelessDeviceTypeDef,
+    CreateWirelessDeviceResponseTypeDef,
+    CreateWirelessGatewayResponseTypeDef,
+    CreateWirelessGatewayTaskDefinitionResponseTypeDef,
     CreateWirelessGatewayTaskRequestRequestTypeDef,
+    CreateWirelessGatewayTaskResponseTypeDef,
+    DakCertificateMetadataTypeDef,
     DeleteDestinationRequestRequestTypeDef,
     DeleteDeviceProfileRequestRequestTypeDef,
     DeleteFuotaTaskRequestRequestTypeDef,
     DeleteMulticastGroupRequestRequestTypeDef,
     DeleteNetworkAnalyzerConfigurationRequestRequestTypeDef,
     DeleteQueuedMessagesRequestRequestTypeDef,
     DeleteServiceProfileRequestRequestTypeDef,
+    DeleteWirelessDeviceImportTaskRequestRequestTypeDef,
     DeleteWirelessDeviceRequestRequestTypeDef,
     DeleteWirelessGatewayRequestRequestTypeDef,
     DeleteWirelessGatewayTaskDefinitionRequestRequestTypeDef,
     DeleteWirelessGatewayTaskRequestRequestTypeDef,
+    DeregisterWirelessDeviceRequestRequestTypeDef,
     DestinationsTypeDef,
     DeviceProfileTypeDef,
     SidewalkEventNotificationConfigurationsTypeDef,
     SidewalkResourceTypeEventConfigurationTypeDef,
     DisassociateAwsAccountFromPartnerAccountRequestRequestTypeDef,
     DisassociateMulticastGroupFromFuotaTaskRequestRequestTypeDef,
     DisassociateWirelessDeviceFromFuotaTaskRequestRequestTypeDef,
@@ -376,144 +395,144 @@
     DisassociateWirelessDeviceFromThingRequestRequestTypeDef,
     DisassociateWirelessGatewayFromCertificateRequestRequestTypeDef,
     DisassociateWirelessGatewayFromThingRequestRequestTypeDef,
     PositioningTypeDef,
     FuotaTaskTypeDef,
     GatewayListItemTypeDef,
     GetDestinationRequestRequestTypeDef,
+    GetDestinationResponseTypeDef,
     GetDeviceProfileRequestRequestTypeDef,
     GetFuotaTaskRequestRequestTypeDef,
     LoRaWANFuotaTaskGetInfoTypeDef,
     GetMulticastGroupRequestRequestTypeDef,
     LoRaWANMulticastGetTypeDef,
     GetMulticastGroupSessionRequestRequestTypeDef,
     LoRaWANMulticastSessionTypeDef,
     GetNetworkAnalyzerConfigurationRequestRequestTypeDef,
     GetPartnerAccountRequestRequestTypeDef,
     SidewalkAccountInfoWithFingerprintTypeDef,
     GetPositionConfigurationRequestRequestTypeDef,
     GnssTypeDef,
     IpTypeDef,
     WiFiAccessPointTypeDef,
+    GetPositionEstimateResponseTypeDef,
     GetPositionRequestRequestTypeDef,
     GetResourceEventConfigurationRequestRequestTypeDef,
     GetResourceLogLevelRequestRequestTypeDef,
+    GetResourceLogLevelResponseTypeDef,
     GetResourcePositionRequestRequestTypeDef,
+    GetResourcePositionResponseTypeDef,
     GetServiceEndpointRequestRequestTypeDef,
+    GetServiceEndpointResponseTypeDef,
     GetServiceProfileRequestRequestTypeDef,
     LoRaWANGetServiceProfileInfoTypeDef,
+    GetWirelessDeviceImportTaskRequestRequestTypeDef,
+    SidewalkGetStartImportInfoTypeDef,
     GetWirelessDeviceRequestRequestTypeDef,
     GetWirelessDeviceStatisticsRequestRequestTypeDef,
     SidewalkDeviceMetadataTypeDef,
     GetWirelessGatewayCertificateRequestRequestTypeDef,
+    GetWirelessGatewayCertificateResponseTypeDef,
     GetWirelessGatewayFirmwareInformationRequestRequestTypeDef,
     GetWirelessGatewayRequestRequestTypeDef,
     GetWirelessGatewayStatisticsRequestRequestTypeDef,
+    GetWirelessGatewayStatisticsResponseTypeDef,
     GetWirelessGatewayTaskDefinitionRequestRequestTypeDef,
     GetWirelessGatewayTaskRequestRequestTypeDef,
+    GetWirelessGatewayTaskResponseTypeDef,
     GlobalIdentityTypeDef,
     GsmLocalIdTypeDef,
+    ImportedSidewalkDeviceTypeDef,
     LoRaWANJoinEventNotificationConfigurationsTypeDef,
     LoRaWANJoinResourceTypeEventConfigurationTypeDef,
     ListDestinationsRequestRequestTypeDef,
     ListDeviceProfilesRequestRequestTypeDef,
+    ListDevicesForWirelessDeviceImportTaskRequestRequestTypeDef,
     ListEventConfigurationsRequestRequestTypeDef,
     ListFuotaTasksRequestRequestTypeDef,
     ListMulticastGroupsByFuotaTaskRequestRequestTypeDef,
     MulticastGroupByFuotaTaskTypeDef,
     ListMulticastGroupsRequestRequestTypeDef,
     MulticastGroupTypeDef,
     ListNetworkAnalyzerConfigurationsRequestRequestTypeDef,
     NetworkAnalyzerConfigurationsTypeDef,
     ListPartnerAccountsRequestRequestTypeDef,
     ListPositionConfigurationsRequestRequestTypeDef,
     ListQueuedMessagesRequestRequestTypeDef,
     ListServiceProfilesRequestRequestTypeDef,
     ServiceProfileTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListWirelessDeviceImportTasksRequestRequestTypeDef,
     ListWirelessDevicesRequestRequestTypeDef,
     ListWirelessGatewayTaskDefinitionsRequestRequestTypeDef,
     ListWirelessGatewaysRequestRequestTypeDef,
     LoRaWANGatewayMetadataTypeDef,
-    OtaaV1_0_xTypeDef,
-    OtaaV1_1TypeDef,
+    OtaaV10XTypeDef,
+    OtaaV11TypeDef,
     LoRaWANGatewayVersionTypeDef,
     LoRaWANListDeviceTypeDef,
     LoRaWANMulticastMetadataTypeDef,
     LoRaWANStartFuotaTaskTypeDef,
-    UpdateAbpV1_0_xTypeDef,
-    UpdateAbpV1_1TypeDef,
+    UpdateAbpV10XTypeDef,
+    UpdateAbpV11TypeDef,
     LteLocalIdTypeDef,
     LteNmrObjTypeDef,
     SemtechGnssConfigurationTypeDef,
     SemtechGnssDetailTypeDef,
     PutResourceLogLevelRequestRequestTypeDef,
     ResetResourceLogLevelRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
+    SendDataToMulticastGroupResponseTypeDef,
+    SendDataToWirelessDeviceResponseTypeDef,
     SidewalkSendDataToDeviceTypeDef,
+    SidewalkSingleStartImportInfoTypeDef,
+    SidewalkStartImportInfoTypeDef,
     SidewalkUpdateAccountTypeDef,
+    SidewalkUpdateImportInfoTypeDef,
+    StartSingleWirelessDeviceImportTaskResponseTypeDef,
+    StartWirelessDeviceImportTaskResponseTypeDef,
     TdscdmaLocalIdTypeDef,
     TdscdmaNmrObjTypeDef,
     TestWirelessDeviceRequestRequestTypeDef,
+    TestWirelessDeviceResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateDestinationRequestRequestTypeDef,
     UpdatePositionRequestRequestTypeDef,
     UpdateResourcePositionRequestRequestTypeDef,
     UpdateWirelessGatewayRequestRequestTypeDef,
     WcdmaLocalIdTypeDef,
     WcdmaNmrObjTypeDef,
     WirelessDeviceEventLogOptionTypeDef,
     WirelessGatewayEventLogOptionTypeDef,
-    AbpV1_0_xTypeDef,
-    AbpV1_1TypeDef,
+    AbpV10XTypeDef,
+    AbpV11TypeDef,
+    GetPositionResponseTypeDef,
+    AssociateAwsAccountWithPartnerAccountResponseTypeDef,
     AssociateAwsAccountWithPartnerAccountRequestRequestTypeDef,
     CreateDestinationRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     StartBulkAssociateWirelessDeviceWithMulticastGroupRequestRequestTypeDef,
     StartBulkDisassociateWirelessDeviceFromMulticastGroupRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
-    AssociateAwsAccountWithPartnerAccountResponseTypeDef,
-    AssociateWirelessGatewayWithCertificateResponseTypeDef,
-    CreateDestinationResponseTypeDef,
-    CreateDeviceProfileResponseTypeDef,
-    CreateFuotaTaskResponseTypeDef,
-    CreateMulticastGroupResponseTypeDef,
-    CreateNetworkAnalyzerConfigurationResponseTypeDef,
-    CreateServiceProfileResponseTypeDef,
-    CreateWirelessDeviceResponseTypeDef,
-    CreateWirelessGatewayResponseTypeDef,
-    CreateWirelessGatewayTaskDefinitionResponseTypeDef,
-    CreateWirelessGatewayTaskResponseTypeDef,
-    GetDestinationResponseTypeDef,
-    GetPositionEstimateResponseTypeDef,
-    GetPositionResponseTypeDef,
-    GetResourceLogLevelResponseTypeDef,
-    GetResourcePositionResponseTypeDef,
-    GetServiceEndpointResponseTypeDef,
-    GetWirelessGatewayCertificateResponseTypeDef,
-    GetWirelessGatewayStatisticsResponseTypeDef,
-    GetWirelessGatewayTaskResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    SendDataToMulticastGroupResponseTypeDef,
-    SendDataToWirelessDeviceResponseTypeDef,
-    TestWirelessDeviceResponseTypeDef,
     LoRaWANGatewayTypeDef,
     CdmaObjTypeDef,
     SidewalkDeviceTypeDef,
     SidewalkListDeviceTypeDef,
     ConnectionStatusEventConfigurationTypeDef,
     ConnectionStatusResourceTypeEventConfigurationTypeDef,
     CreateDeviceProfileRequestRequestTypeDef,
-    GetDeviceProfileResponseTypeDef,
     CreateFuotaTaskRequestRequestTypeDef,
     UpdateFuotaTaskRequestRequestTypeDef,
     CreateMulticastGroupRequestRequestTypeDef,
     UpdateMulticastGroupRequestRequestTypeDef,
     CreateNetworkAnalyzerConfigurationRequestRequestTypeDef,
     GetNetworkAnalyzerConfigurationResponseTypeDef,
     UpdateNetworkAnalyzerConfigurationRequestRequestTypeDef,
     CreateServiceProfileRequestRequestTypeDef,
+    SidewalkGetDeviceProfileTypeDef,
     ListDestinationsResponseTypeDef,
     ListDeviceProfilesResponseTypeDef,
     DeviceRegistrationStateEventConfigurationTypeDef,
     MessageDeliveryStatusEventConfigurationTypeDef,
     ProximityEventConfigurationTypeDef,
     DeviceRegistrationStateResourceTypeEventConfigurationTypeDef,
     MessageDeliveryStatusResourceTypeEventConfigurationTypeDef,
@@ -525,15 +544,18 @@
     GetFuotaTaskResponseTypeDef,
     GetMulticastGroupResponseTypeDef,
     GetMulticastGroupSessionResponseTypeDef,
     StartMulticastGroupSessionRequestRequestTypeDef,
     GetPartnerAccountResponseTypeDef,
     ListPartnerAccountsResponseTypeDef,
     GetServiceProfileResponseTypeDef,
+    GetWirelessDeviceImportTaskResponseTypeDef,
+    WirelessDeviceImportTaskTypeDef,
     GsmNmrObjTypeDef,
+    ImportedWirelessDeviceTypeDef,
     JoinEventConfigurationTypeDef,
     JoinResourceTypeEventConfigurationTypeDef,
     ListMulticastGroupsByFuotaTaskResponseTypeDef,
     ListMulticastGroupsResponseTypeDef,
     ListNetworkAnalyzerConfigurationsResponseTypeDef,
     ListServiceProfilesResponseTypeDef,
     LoRaWANDeviceMetadataTypeDef,
@@ -541,27 +563,33 @@
     LoRaWANUpdateGatewayTaskCreateTypeDef,
     LoRaWANUpdateGatewayTaskEntryTypeDef,
     MulticastWirelessMetadataTypeDef,
     StartFuotaTaskRequestRequestTypeDef,
     LteObjTypeDef,
     PositionSolverConfigurationsTypeDef,
     PositionSolverDetailsTypeDef,
+    StartSingleWirelessDeviceImportTaskRequestRequestTypeDef,
+    StartWirelessDeviceImportTaskRequestRequestTypeDef,
     UpdatePartnerAccountRequestRequestTypeDef,
+    UpdateWirelessDeviceImportTaskRequestRequestTypeDef,
     TdscdmaObjTypeDef,
     WcdmaObjTypeDef,
     WirelessDeviceLogOptionTypeDef,
     WirelessGatewayLogOptionTypeDef,
     CreateWirelessGatewayRequestRequestTypeDef,
     GetWirelessGatewayResponseTypeDef,
     WirelessGatewayStatisticsTypeDef,
     WirelessDeviceStatisticsTypeDef,
+    GetDeviceProfileResponseTypeDef,
     LoRaWANDeviceTypeDef,
     LoRaWANUpdateDeviceTypeDef,
     LoRaWANSendDataToDeviceTypeDef,
+    ListWirelessDeviceImportTasksResponseTypeDef,
     GsmObjTypeDef,
+    ListDevicesForWirelessDeviceImportTaskResponseTypeDef,
     EventNotificationItemConfigurationsTypeDef,
     GetResourceEventConfigurationResponseTypeDef,
     UpdateResourceEventConfigurationRequestRequestTypeDef,
     GetEventConfigurationByResourceTypesResponseTypeDef,
     UpdateEventConfigurationByResourceTypesRequestRequestTypeDef,
     GetWirelessDeviceStatisticsResponseTypeDef,
     GetWirelessGatewayFirmwareInformationResponseTypeDef,
@@ -589,54 +617,54 @@
     ListQueuedMessagesResponseTypeDef,
     SendDataToWirelessDeviceRequestRequestTypeDef,
     GetPositionEstimateRequestRequestTypeDef,
     ListEventConfigurationsResponseTypeDef,
 )
 
 
-def get_structure() -> SessionKeysAbpV1_0_xTypeDef:
+def get_structure() -> SessionKeysAbpV10XTypeDef:
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

### Comparing `types-aiobotocore-iotwireless-2.5.0.post1/types_aiobotocore_iotwireless.egg-info/SOURCES.txt` & `types-aiobotocore-iotwireless-2.5.1/types_aiobotocore_iotwireless.egg-info/SOURCES.txt`

 * *Files identical despite different names*

