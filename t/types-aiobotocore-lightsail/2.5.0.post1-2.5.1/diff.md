# Comparing `tmp/types-aiobotocore-lightsail-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-lightsail-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-lightsail-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:54 2023, max compression
+gzip compressed data, was "types-aiobotocore-lightsail-2.5.1.tar", last modified: Wed Jun 28 01:43:46 2023, max compression
```

## Comparing `types-aiobotocore-lightsail-2.5.0.post1.tar` & `types-aiobotocore-lightsail-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:54.283372 types-aiobotocore-lightsail-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:17:38.000000 types-aiobotocore-lightsail-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    36413 2023-03-11 12:26:54.279372 types-aiobotocore-lightsail-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    34834 2023-03-11 12:17:38.000000 types-aiobotocore-lightsail-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:54.283372 types-aiobotocore-lightsail-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2138 2023-03-11 12:17:38.000000 types-aiobotocore-lightsail-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:54.271372 types-aiobotocore-lightsail-2.5.0.post1/types_aiobotocore_lightsail/
--rw-r--r--   0 runner    (1001) docker     (123)     4923 2023-03-11 12:17:38.000000 types-aiobotocore-lightsail-2.5.0.post1/types_aiobotocore_lightsail/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4922 2023-03-11 12:17:38.000000 types-aiobotocore-lightsail-2.5.0.post1/types_aiobotocore_lightsail/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      951 2023-03-11 12:17:38.000000 types-aiobotocore-lightsail-2.5.0.post1/types_aiobotocore_lightsail/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)   116652 2023-03-11 12:17:39.000000 types-aiobotocore-lightsail-2.5.0.post1/types_aiobotocore_lightsail/client.py
--rw-r--r--   0 runner    (1001) docker     (123)   116468 2023-03-11 12:17:38.000000 types-aiobotocore-lightsail-2.5.0.post1/types_aiobotocore_lightsail/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    24401 2023-03-11 12:17:41.000000 types-aiobotocore-lightsail-2.5.0.post1/types_aiobotocore_lightsail/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    24399 2023-03-11 12:17:39.000000 types-aiobotocore-lightsail-2.5.0.post1/types_aiobotocore_lightsail/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    23844 2023-03-11 12:17:39.000000 types-aiobotocore-lightsail-2.5.0.post1/types_aiobotocore_lightsail/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    23821 2023-03-11 12:17:39.000000 types-aiobotocore-lightsail-2.5.0.post1/types_aiobotocore_lightsail/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:17:38.000000 types-aiobotocore-lightsail-2.5.0.post1/types_aiobotocore_lightsail/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)   142111 2023-03-11 12:17:44.000000 types-aiobotocore-lightsail-2.5.0.post1/types_aiobotocore_lightsail/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)   142014 2023-03-11 12:17:42.000000 types-aiobotocore-lightsail-2.5.0.post1/types_aiobotocore_lightsail/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:17:38.000000 types-aiobotocore-lightsail-2.5.0.post1/types_aiobotocore_lightsail/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:54.279372 types-aiobotocore-lightsail-2.5.0.post1/types_aiobotocore_lightsail.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    36413 2023-03-11 12:26:54.000000 types-aiobotocore-lightsail-2.5.0.post1/types_aiobotocore_lightsail.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      851 2023-03-11 12:26:54.000000 types-aiobotocore-lightsail-2.5.0.post1/types_aiobotocore_lightsail.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:54.000000 types-aiobotocore-lightsail-2.5.0.post1/types_aiobotocore_lightsail.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:54.000000 types-aiobotocore-lightsail-2.5.0.post1/types_aiobotocore_lightsail.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:54.000000 types-aiobotocore-lightsail-2.5.0.post1/types_aiobotocore_lightsail.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       28 2023-03-11 12:26:54.000000 types-aiobotocore-lightsail-2.5.0.post1/types_aiobotocore_lightsail.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:46.506168 types-aiobotocore-lightsail-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:34:19.000000 types-aiobotocore-lightsail-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    37006 2023-06-28 01:43:46.502169 types-aiobotocore-lightsail-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    35433 2023-06-28 01:34:19.000000 types-aiobotocore-lightsail-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:46.506168 types-aiobotocore-lightsail-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2132 2023-06-28 01:34:19.000000 types-aiobotocore-lightsail-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:46.502169 types-aiobotocore-lightsail-2.5.1/types_aiobotocore_lightsail/
+-rw-r--r--   0 runner    (1001) docker     (123)     4923 2023-06-28 01:34:19.000000 types-aiobotocore-lightsail-2.5.1/types_aiobotocore_lightsail/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4922 2023-06-28 01:34:19.000000 types-aiobotocore-lightsail-2.5.1/types_aiobotocore_lightsail/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      939 2023-06-28 01:34:19.000000 types-aiobotocore-lightsail-2.5.1/types_aiobotocore_lightsail/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)   119354 2023-06-28 01:34:21.000000 types-aiobotocore-lightsail-2.5.1/types_aiobotocore_lightsail/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)   119166 2023-06-28 01:34:19.000000 types-aiobotocore-lightsail-2.5.1/types_aiobotocore_lightsail/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    25240 2023-06-28 01:34:21.000000 types-aiobotocore-lightsail-2.5.1/types_aiobotocore_lightsail/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25238 2023-06-28 01:34:21.000000 types-aiobotocore-lightsail-2.5.1/types_aiobotocore_lightsail/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    24021 2023-06-28 01:34:21.000000 types-aiobotocore-lightsail-2.5.1/types_aiobotocore_lightsail/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23998 2023-06-28 01:34:21.000000 types-aiobotocore-lightsail-2.5.1/types_aiobotocore_lightsail/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:34:19.000000 types-aiobotocore-lightsail-2.5.1/types_aiobotocore_lightsail/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)   146658 2023-06-28 01:34:24.000000 types-aiobotocore-lightsail-2.5.1/types_aiobotocore_lightsail/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)   146559 2023-06-28 01:34:23.000000 types-aiobotocore-lightsail-2.5.1/types_aiobotocore_lightsail/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:34:19.000000 types-aiobotocore-lightsail-2.5.1/types_aiobotocore_lightsail/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:46.502169 types-aiobotocore-lightsail-2.5.1/types_aiobotocore_lightsail.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    37006 2023-06-28 01:43:46.000000 types-aiobotocore-lightsail-2.5.1/types_aiobotocore_lightsail.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      851 2023-06-28 01:43:46.000000 types-aiobotocore-lightsail-2.5.1/types_aiobotocore_lightsail.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:46.000000 types-aiobotocore-lightsail-2.5.1/types_aiobotocore_lightsail.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:46.000000 types-aiobotocore-lightsail-2.5.1/types_aiobotocore_lightsail.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:46.000000 types-aiobotocore-lightsail-2.5.1/types_aiobotocore_lightsail.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       28 2023-06-28 01:43:46.000000 types-aiobotocore-lightsail-2.5.1/types_aiobotocore_lightsail.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-lightsail-2.5.0.post1/LICENSE` & `types-aiobotocore-lightsail-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-lightsail-2.5.0.post1/PKG-INFO` & `types-aiobotocore-lightsail-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-lightsail
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Lightsail 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Lightsail 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-lightsail"></a>
 
 # types-aiobotocore-lightsail
 
 [![PyPI - types-aiobotocore-lightsail](https://img.shields.io/pypi/v/types-aiobotocore-lightsail.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lightsail)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-lightsail.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lightsail)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-lightsail?color=blue)](https://pypistats.org/packages/types-aiobotocore-lightsail)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Lightsail 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail)
+[aiobotocore.Lightsail 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail)
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
 [types-aiobotocore-lightsail docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/).
 
 See how it helps to find and fix potential bugs:
 
@@ -359,14 +359,16 @@
 ```python
 from types_aiobotocore_lightsail.literals import (
     AccessDirectionType,
     AccessTypeType,
     AccountLevelBpaSyncStatusType,
     AddOnTypeType,
     AlarmStateType,
+    AppCategoryType,
+    AutoMountStatusType,
     AutoSnapshotStatusType,
     BPAStatusMessageType,
     BehaviorEnumType,
     BlueprintTypeType,
     BucketMetricNameType,
     CertificateDomainValidationStatusType,
     CertificateStatusType,
@@ -377,14 +379,15 @@
     ContactProtocolType,
     ContainerServiceDeploymentStateType,
     ContainerServiceMetricNameType,
     ContainerServicePowerNameType,
     ContainerServiceProtocolType,
     ContainerServiceStateDetailCodeType,
     ContainerServiceStateType,
+    CurrencyType,
     DiskSnapshotStateType,
     DiskStateType,
     DistributionMetricNameType,
     DnsRecordCreationStateCodeType,
     ExportSnapshotRecordSourceTypeType,
     ForwardValuesType,
     GetActiveNamesPaginatorName,
@@ -436,23 +439,25 @@
     NetworkProtocolType,
     OperationStatusType,
     OperationTypeType,
     OriginProtocolPolicyEnumType,
     PortAccessTypeType,
     PortInfoSourceTypeType,
     PortStateType,
+    PricingUnitType,
     R53HostedZoneDeletionStateCodeType,
     RecordStateType,
     RegionNameType,
     RelationalDatabaseEngineType,
     RelationalDatabaseMetricNameType,
     RelationalDatabasePasswordVersionType,
     RenewalStatusType,
     ResourceBucketAccessType,
     ResourceTypeType,
+    StatusType,
     StatusTypeType,
     TreatMissingDataType,
     LightsailServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
@@ -472,19 +477,19 @@
 
 ```python
 from types_aiobotocore_lightsail.type_defs import (
     AccessKeyLastUsedTypeDef,
     AccessRulesTypeDef,
     AccountLevelBpaSyncTypeDef,
     AutoSnapshotAddOnRequestTypeDef,
+    StopInstanceOnIdleRequestTypeDef,
     AddOnTypeDef,
     MonitoredResourceInfoTypeDef,
     ResourceLocationTypeDef,
     AllocateStaticIpRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     AttachCertificateToDistributionRequestRequestTypeDef,
     AttachDiskRequestRequestTypeDef,
     AttachInstancesToLoadBalancerRequestRequestTypeDef,
     AttachLoadBalancerTlsCertificateRequestRequestTypeDef,
     AttachStaticIpRequestRequestTypeDef,
     AttachedDiskTypeDef,
     AvailabilityZoneTypeDef,
@@ -514,14 +519,16 @@
     ContainerServiceStateDetailTypeDef,
     CopySnapshotRequestRequestTypeDef,
     CreateBucketAccessKeyRequestRequestTypeDef,
     InstanceEntryTypeDef,
     CreateContactMethodRequestRequestTypeDef,
     InputOriginTypeDef,
     DomainEntryTypeDef,
+    CreateGUISessionAccessDetailsRequestRequestTypeDef,
+    SessionTypeDef,
     DiskMapTypeDef,
     DeleteAlarmRequestRequestTypeDef,
     DeleteAutoSnapshotRequestRequestTypeDef,
     DeleteBucketAccessKeyRequestRequestTypeDef,
     DeleteBucketRequestRequestTypeDef,
     DeleteCertificateRequestRequestTypeDef,
     DeleteContactMethodRequestRequestTypeDef,
@@ -545,113 +552,145 @@
     DetachStaticIpRequestRequestTypeDef,
     DisableAddOnRequestRequestTypeDef,
     DiskInfoTypeDef,
     DiskSnapshotInfoTypeDef,
     DistributionBundleTypeDef,
     DnsRecordCreationStateTypeDef,
     ResourceRecordTypeDef,
+    DownloadDefaultKeyPairResultTypeDef,
+    TimePeriodTypeDef,
     ExportSnapshotRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetActiveNamesRequestGetActiveNamesPaginateTypeDef,
     GetActiveNamesRequestRequestTypeDef,
+    GetActiveNamesResultTypeDef,
     GetAlarmsRequestRequestTypeDef,
     GetAutoSnapshotsRequestRequestTypeDef,
+    GetBlueprintsRequestGetBlueprintsPaginateTypeDef,
     GetBlueprintsRequestRequestTypeDef,
     GetBucketAccessKeysRequestRequestTypeDef,
     GetBucketBundlesRequestRequestTypeDef,
     GetBucketMetricDataRequestRequestTypeDef,
     MetricDatapointTypeDef,
     GetBucketsRequestRequestTypeDef,
+    GetBundlesRequestGetBundlesPaginateTypeDef,
     GetBundlesRequestRequestTypeDef,
     GetCertificatesRequestRequestTypeDef,
+    GetCloudFormationStackRecordsRequestGetCloudFormationStackRecordsPaginateTypeDef,
     GetCloudFormationStackRecordsRequestRequestTypeDef,
     GetContactMethodsRequestRequestTypeDef,
+    GetContainerAPIMetadataResultTypeDef,
     GetContainerImagesRequestRequestTypeDef,
     GetContainerLogRequestRequestTypeDef,
     GetContainerServiceDeploymentsRequestRequestTypeDef,
     GetContainerServiceMetricDataRequestRequestTypeDef,
     GetContainerServicesRequestRequestTypeDef,
+    GetCostEstimateRequestRequestTypeDef,
     GetDiskRequestRequestTypeDef,
     GetDiskSnapshotRequestRequestTypeDef,
+    GetDiskSnapshotsRequestGetDiskSnapshotsPaginateTypeDef,
     GetDiskSnapshotsRequestRequestTypeDef,
+    GetDisksRequestGetDisksPaginateTypeDef,
     GetDisksRequestRequestTypeDef,
     GetDistributionLatestCacheResetRequestRequestTypeDef,
+    GetDistributionLatestCacheResetResultTypeDef,
     GetDistributionMetricDataRequestRequestTypeDef,
     GetDistributionsRequestRequestTypeDef,
     GetDomainRequestRequestTypeDef,
+    GetDomainsRequestGetDomainsPaginateTypeDef,
     GetDomainsRequestRequestTypeDef,
+    GetExportSnapshotRecordsRequestGetExportSnapshotRecordsPaginateTypeDef,
     GetExportSnapshotRecordsRequestRequestTypeDef,
     GetInstanceAccessDetailsRequestRequestTypeDef,
     GetInstanceMetricDataRequestRequestTypeDef,
     GetInstancePortStatesRequestRequestTypeDef,
     InstancePortStateTypeDef,
     GetInstanceRequestRequestTypeDef,
     GetInstanceSnapshotRequestRequestTypeDef,
+    GetInstanceSnapshotsRequestGetInstanceSnapshotsPaginateTypeDef,
     GetInstanceSnapshotsRequestRequestTypeDef,
     GetInstanceStateRequestRequestTypeDef,
     InstanceStateTypeDef,
+    GetInstancesRequestGetInstancesPaginateTypeDef,
     GetInstancesRequestRequestTypeDef,
     GetKeyPairRequestRequestTypeDef,
+    GetKeyPairsRequestGetKeyPairsPaginateTypeDef,
     GetKeyPairsRequestRequestTypeDef,
     GetLoadBalancerMetricDataRequestRequestTypeDef,
     GetLoadBalancerRequestRequestTypeDef,
     GetLoadBalancerTlsCertificatesRequestRequestTypeDef,
     GetLoadBalancerTlsPoliciesRequestRequestTypeDef,
     LoadBalancerTlsPolicyTypeDef,
+    GetLoadBalancersRequestGetLoadBalancersPaginateTypeDef,
     GetLoadBalancersRequestRequestTypeDef,
     GetOperationRequestRequestTypeDef,
     GetOperationsForResourceRequestRequestTypeDef,
+    GetOperationsRequestGetOperationsPaginateTypeDef,
     GetOperationsRequestRequestTypeDef,
     GetRegionsRequestRequestTypeDef,
+    GetRelationalDatabaseBlueprintsRequestGetRelationalDatabaseBlueprintsPaginateTypeDef,
     GetRelationalDatabaseBlueprintsRequestRequestTypeDef,
     RelationalDatabaseBlueprintTypeDef,
+    GetRelationalDatabaseBundlesRequestGetRelationalDatabaseBundlesPaginateTypeDef,
     GetRelationalDatabaseBundlesRequestRequestTypeDef,
     RelationalDatabaseBundleTypeDef,
+    GetRelationalDatabaseEventsRequestGetRelationalDatabaseEventsPaginateTypeDef,
     GetRelationalDatabaseEventsRequestRequestTypeDef,
     RelationalDatabaseEventTypeDef,
     GetRelationalDatabaseLogEventsRequestRequestTypeDef,
     LogEventTypeDef,
     GetRelationalDatabaseLogStreamsRequestRequestTypeDef,
+    GetRelationalDatabaseLogStreamsResultTypeDef,
     GetRelationalDatabaseMasterUserPasswordRequestRequestTypeDef,
+    GetRelationalDatabaseMasterUserPasswordResultTypeDef,
     GetRelationalDatabaseMetricDataRequestRequestTypeDef,
+    GetRelationalDatabaseParametersRequestGetRelationalDatabaseParametersPaginateTypeDef,
     GetRelationalDatabaseParametersRequestRequestTypeDef,
     RelationalDatabaseParameterTypeDef,
     GetRelationalDatabaseRequestRequestTypeDef,
     GetRelationalDatabaseSnapshotRequestRequestTypeDef,
+    GetRelationalDatabaseSnapshotsRequestGetRelationalDatabaseSnapshotsPaginateTypeDef,
     GetRelationalDatabaseSnapshotsRequestRequestTypeDef,
+    GetRelationalDatabasesRequestGetRelationalDatabasesPaginateTypeDef,
     GetRelationalDatabasesRequestRequestTypeDef,
     GetStaticIpRequestRequestTypeDef,
+    GetStaticIpsRequestGetStaticIpsPaginateTypeDef,
     GetStaticIpsRequestRequestTypeDef,
     HostKeyAttributesTypeDef,
     ImportKeyPairRequestRequestTypeDef,
     PasswordDataTypeDef,
     InstanceHealthSummaryTypeDef,
     InstanceMetadataOptionsTypeDef,
     InstancePortInfoTypeDef,
     MonthlyTransferTypeDef,
+    IsVpcPeeredResultTypeDef,
     OriginTypeDef,
     LoadBalancerTlsCertificateDnsRecordCreationStateTypeDef,
     LoadBalancerTlsCertificateDomainValidationOptionTypeDef,
     LoadBalancerTlsCertificateSummaryTypeDef,
     NameServersUpdateStateTypeDef,
+    PaginatorConfigTypeDef,
     PendingMaintenanceActionTypeDef,
     PendingModifiedRelationalDatabaseValuesTypeDef,
     PutAlarmRequestRequestTypeDef,
     R53HostedZoneDeletionStateTypeDef,
     RebootInstanceRequestRequestTypeDef,
     RebootRelationalDatabaseRequestRequestTypeDef,
     RegisterContainerImageRequestRequestTypeDef,
     RelationalDatabaseEndpointTypeDef,
     RelationalDatabaseHardwareTypeDef,
     ReleaseStaticIpRequestRequestTypeDef,
     ResetDistributionCacheRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     SendContactMethodVerificationRequestRequestTypeDef,
     SetIpAddressTypeRequestRequestTypeDef,
     SetResourceAccessForBucketRequestRequestTypeDef,
+    StartGUISessionRequestRequestTypeDef,
     StartInstanceRequestRequestTypeDef,
     StartRelationalDatabaseRequestRequestTypeDef,
+    StopGUISessionRequestRequestTypeDef,
     StopInstanceRequestRequestTypeDef,
     StopRelationalDatabaseRequestRequestTypeDef,
     TestAlarmRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateBucketBundleRequestRequestTypeDef,
     UpdateDistributionBundleRequestRequestTypeDef,
     UpdateInstanceMetadataOptionsRequestRequestTypeDef,
@@ -659,21 +698,14 @@
     UpdateRelationalDatabaseRequestRequestTypeDef,
     AccessKeyTypeDef,
     AddOnRequestTypeDef,
     AlarmTypeDef,
     ContactMethodTypeDef,
     OperationTypeDef,
     StaticIpTypeDef,
-    DownloadDefaultKeyPairResultTypeDef,
-    GetActiveNamesResultTypeDef,
-    GetContainerAPIMetadataResultTypeDef,
-    GetDistributionLatestCacheResetResultTypeDef,
-    GetRelationalDatabaseLogStreamsResultTypeDef,
-    GetRelationalDatabaseMasterUserPasswordResultTypeDef,
-    IsVpcPeeredResultTypeDef,
     AutoSnapshotDetailsTypeDef,
     RegionTypeDef,
     GetBlueprintsResultTypeDef,
     UpdateBucketRequestRequestTypeDef,
     GetBucketBundlesResultTypeDef,
     BucketTypeDef,
     CreateBucketRequestRequestTypeDef,
@@ -707,37 +739,19 @@
     GetContainerLogResultTypeDef,
     GetContainerServicePowersResultTypeDef,
     CreateContainerServiceRegistryLoginResultTypeDef,
     CreateCloudFormationStackRequestRequestTypeDef,
     CreateDomainEntryRequestRequestTypeDef,
     DeleteDomainEntryRequestRequestTypeDef,
     UpdateDomainEntryRequestRequestTypeDef,
+    CreateGUISessionAccessDetailsResultTypeDef,
     InstanceSnapshotInfoTypeDef,
     GetDistributionBundlesResultTypeDef,
     DomainValidationRecordTypeDef,
-    GetActiveNamesRequestGetActiveNamesPaginateTypeDef,
-    GetBlueprintsRequestGetBlueprintsPaginateTypeDef,
-    GetBundlesRequestGetBundlesPaginateTypeDef,
-    GetCloudFormationStackRecordsRequestGetCloudFormationStackRecordsPaginateTypeDef,
-    GetDiskSnapshotsRequestGetDiskSnapshotsPaginateTypeDef,
-    GetDisksRequestGetDisksPaginateTypeDef,
-    GetDomainsRequestGetDomainsPaginateTypeDef,
-    GetExportSnapshotRecordsRequestGetExportSnapshotRecordsPaginateTypeDef,
-    GetInstanceSnapshotsRequestGetInstanceSnapshotsPaginateTypeDef,
-    GetInstancesRequestGetInstancesPaginateTypeDef,
-    GetKeyPairsRequestGetKeyPairsPaginateTypeDef,
-    GetLoadBalancersRequestGetLoadBalancersPaginateTypeDef,
-    GetOperationsRequestGetOperationsPaginateTypeDef,
-    GetRelationalDatabaseBlueprintsRequestGetRelationalDatabaseBlueprintsPaginateTypeDef,
-    GetRelationalDatabaseBundlesRequestGetRelationalDatabaseBundlesPaginateTypeDef,
-    GetRelationalDatabaseEventsRequestGetRelationalDatabaseEventsPaginateTypeDef,
-    GetRelationalDatabaseParametersRequestGetRelationalDatabaseParametersPaginateTypeDef,
-    GetRelationalDatabaseSnapshotsRequestGetRelationalDatabaseSnapshotsPaginateTypeDef,
-    GetRelationalDatabasesRequestGetRelationalDatabasesPaginateTypeDef,
-    GetStaticIpsRequestGetStaticIpsPaginateTypeDef,
+    EstimateByTimeTypeDef,
     GetBucketMetricDataResultTypeDef,
     GetContainerServiceMetricDataResultTypeDef,
     GetDistributionMetricDataResultTypeDef,
     GetInstanceMetricDataResultTypeDef,
     GetLoadBalancerMetricDataResultTypeDef,
     GetRelationalDatabaseMetricDataResultTypeDef,
     GetInstancePortStatesResultTypeDef,
@@ -825,16 +839,18 @@
     RebootInstanceResultTypeDef,
     RebootRelationalDatabaseResultTypeDef,
     ReleaseStaticIpResultTypeDef,
     ResetDistributionCacheResultTypeDef,
     SendContactMethodVerificationResultTypeDef,
     SetIpAddressTypeResultTypeDef,
     SetResourceAccessForBucketResultTypeDef,
+    StartGUISessionResultTypeDef,
     StartInstanceResultTypeDef,
     StartRelationalDatabaseResultTypeDef,
+    StopGUISessionResultTypeDef,
     StopInstanceResultTypeDef,
     StopRelationalDatabaseResultTypeDef,
     TagResourceResultTypeDef,
     TestAlarmResultTypeDef,
     UnpeerVpcResultTypeDef,
     UntagResourceResultTypeDef,
     UpdateBucketBundleResultTypeDef,
@@ -869,14 +885,15 @@
     GetCloudFormationStackRecordsResultTypeDef,
     UpdateContainerServiceRequestRequestTypeDef,
     ContainerServiceDeploymentTypeDef,
     ContainerServiceDeploymentRequestTypeDef,
     CreateContainerServiceDeploymentRequestRequestTypeDef,
     ExportSnapshotRecordSourceInfoTypeDef,
     RenewalSummaryTypeDef,
+    CostEstimateTypeDef,
     GetInstanceAccessDetailsResultTypeDef,
     LoadBalancerTlsCertificateTypeDef,
     GetLoadBalancerResultTypeDef,
     GetLoadBalancersResultTypeDef,
     DomainTypeDef,
     GetRelationalDatabaseResultTypeDef,
     GetRelationalDatabasesResultTypeDef,
@@ -886,25 +903,27 @@
     CreateDistributionResultTypeDef,
     GetDistributionsResultTypeDef,
     ContainerServiceTypeDef,
     GetContainerServiceDeploymentsResultTypeDef,
     CreateContainerServiceRequestRequestTypeDef,
     ExportSnapshotRecordTypeDef,
     CertificateTypeDef,
+    ResourceBudgetEstimateTypeDef,
     GetLoadBalancerTlsCertificatesResultTypeDef,
     GetDomainResultTypeDef,
     GetDomainsResultTypeDef,
     GetInstanceResultTypeDef,
     GetInstancesResultTypeDef,
     ContainerServicesListResultTypeDef,
     CreateContainerServiceDeploymentResultTypeDef,
     CreateContainerServiceResultTypeDef,
     UpdateContainerServiceResultTypeDef,
     GetExportSnapshotRecordsResultTypeDef,
     CertificateSummaryTypeDef,
+    GetCostEstimateResultTypeDef,
     CreateCertificateResultTypeDef,
     GetCertificatesResultTypeDef,
 )
 
 
 def get_structure() -> AccessKeyLastUsedTypeDef:
     return {...}
@@ -913,43 +932,43 @@
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

### Comparing `types-aiobotocore-lightsail-2.5.0.post1/README.md` & `types-aiobotocore-lightsail-2.5.1/types_aiobotocore_lightsail.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,62 @@
+Metadata-Version: 2.1
+Name: types-aiobotocore-lightsail
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Lightsail 2.5.1 service generated with mypy-boto3-builder 7.14.5
+Home-page: https://github.com/youtype/mypy_boto3_builder
+Author: Vlad Emelianov
+Author-email: vlad.emelianov.nz@gmail.com
+License: MIT License
+Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/
+Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
+Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
+Keywords: aiobotocore lightsail type-annotations boto3-stubs mypy typeshed autocomplete
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
 <a id="types-aiobotocore-lightsail"></a>
 
 # types-aiobotocore-lightsail
 
 [![PyPI - types-aiobotocore-lightsail](https://img.shields.io/pypi/v/types-aiobotocore-lightsail.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lightsail)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-lightsail.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lightsail)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-lightsail?color=blue)](https://pypistats.org/packages/types-aiobotocore-lightsail)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Lightsail 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail)
+[aiobotocore.Lightsail 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail)
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
 [types-aiobotocore-lightsail docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/).
 
 See how it helps to find and fix potential bugs:
 
@@ -326,14 +359,16 @@
 ```python
 from types_aiobotocore_lightsail.literals import (
     AccessDirectionType,
     AccessTypeType,
     AccountLevelBpaSyncStatusType,
     AddOnTypeType,
     AlarmStateType,
+    AppCategoryType,
+    AutoMountStatusType,
     AutoSnapshotStatusType,
     BPAStatusMessageType,
     BehaviorEnumType,
     BlueprintTypeType,
     BucketMetricNameType,
     CertificateDomainValidationStatusType,
     CertificateStatusType,
@@ -344,14 +379,15 @@
     ContactProtocolType,
     ContainerServiceDeploymentStateType,
     ContainerServiceMetricNameType,
     ContainerServicePowerNameType,
     ContainerServiceProtocolType,
     ContainerServiceStateDetailCodeType,
     ContainerServiceStateType,
+    CurrencyType,
     DiskSnapshotStateType,
     DiskStateType,
     DistributionMetricNameType,
     DnsRecordCreationStateCodeType,
     ExportSnapshotRecordSourceTypeType,
     ForwardValuesType,
     GetActiveNamesPaginatorName,
@@ -403,23 +439,25 @@
     NetworkProtocolType,
     OperationStatusType,
     OperationTypeType,
     OriginProtocolPolicyEnumType,
     PortAccessTypeType,
     PortInfoSourceTypeType,
     PortStateType,
+    PricingUnitType,
     R53HostedZoneDeletionStateCodeType,
     RecordStateType,
     RegionNameType,
     RelationalDatabaseEngineType,
     RelationalDatabaseMetricNameType,
     RelationalDatabasePasswordVersionType,
     RenewalStatusType,
     ResourceBucketAccessType,
     ResourceTypeType,
+    StatusType,
     StatusTypeType,
     TreatMissingDataType,
     LightsailServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
@@ -439,19 +477,19 @@
 
 ```python
 from types_aiobotocore_lightsail.type_defs import (
     AccessKeyLastUsedTypeDef,
     AccessRulesTypeDef,
     AccountLevelBpaSyncTypeDef,
     AutoSnapshotAddOnRequestTypeDef,
+    StopInstanceOnIdleRequestTypeDef,
     AddOnTypeDef,
     MonitoredResourceInfoTypeDef,
     ResourceLocationTypeDef,
     AllocateStaticIpRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     AttachCertificateToDistributionRequestRequestTypeDef,
     AttachDiskRequestRequestTypeDef,
     AttachInstancesToLoadBalancerRequestRequestTypeDef,
     AttachLoadBalancerTlsCertificateRequestRequestTypeDef,
     AttachStaticIpRequestRequestTypeDef,
     AttachedDiskTypeDef,
     AvailabilityZoneTypeDef,
@@ -481,14 +519,16 @@
     ContainerServiceStateDetailTypeDef,
     CopySnapshotRequestRequestTypeDef,
     CreateBucketAccessKeyRequestRequestTypeDef,
     InstanceEntryTypeDef,
     CreateContactMethodRequestRequestTypeDef,
     InputOriginTypeDef,
     DomainEntryTypeDef,
+    CreateGUISessionAccessDetailsRequestRequestTypeDef,
+    SessionTypeDef,
     DiskMapTypeDef,
     DeleteAlarmRequestRequestTypeDef,
     DeleteAutoSnapshotRequestRequestTypeDef,
     DeleteBucketAccessKeyRequestRequestTypeDef,
     DeleteBucketRequestRequestTypeDef,
     DeleteCertificateRequestRequestTypeDef,
     DeleteContactMethodRequestRequestTypeDef,
@@ -512,113 +552,145 @@
     DetachStaticIpRequestRequestTypeDef,
     DisableAddOnRequestRequestTypeDef,
     DiskInfoTypeDef,
     DiskSnapshotInfoTypeDef,
     DistributionBundleTypeDef,
     DnsRecordCreationStateTypeDef,
     ResourceRecordTypeDef,
+    DownloadDefaultKeyPairResultTypeDef,
+    TimePeriodTypeDef,
     ExportSnapshotRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetActiveNamesRequestGetActiveNamesPaginateTypeDef,
     GetActiveNamesRequestRequestTypeDef,
+    GetActiveNamesResultTypeDef,
     GetAlarmsRequestRequestTypeDef,
     GetAutoSnapshotsRequestRequestTypeDef,
+    GetBlueprintsRequestGetBlueprintsPaginateTypeDef,
     GetBlueprintsRequestRequestTypeDef,
     GetBucketAccessKeysRequestRequestTypeDef,
     GetBucketBundlesRequestRequestTypeDef,
     GetBucketMetricDataRequestRequestTypeDef,
     MetricDatapointTypeDef,
     GetBucketsRequestRequestTypeDef,
+    GetBundlesRequestGetBundlesPaginateTypeDef,
     GetBundlesRequestRequestTypeDef,
     GetCertificatesRequestRequestTypeDef,
+    GetCloudFormationStackRecordsRequestGetCloudFormationStackRecordsPaginateTypeDef,
     GetCloudFormationStackRecordsRequestRequestTypeDef,
     GetContactMethodsRequestRequestTypeDef,
+    GetContainerAPIMetadataResultTypeDef,
     GetContainerImagesRequestRequestTypeDef,
     GetContainerLogRequestRequestTypeDef,
     GetContainerServiceDeploymentsRequestRequestTypeDef,
     GetContainerServiceMetricDataRequestRequestTypeDef,
     GetContainerServicesRequestRequestTypeDef,
+    GetCostEstimateRequestRequestTypeDef,
     GetDiskRequestRequestTypeDef,
     GetDiskSnapshotRequestRequestTypeDef,
+    GetDiskSnapshotsRequestGetDiskSnapshotsPaginateTypeDef,
     GetDiskSnapshotsRequestRequestTypeDef,
+    GetDisksRequestGetDisksPaginateTypeDef,
     GetDisksRequestRequestTypeDef,
     GetDistributionLatestCacheResetRequestRequestTypeDef,
+    GetDistributionLatestCacheResetResultTypeDef,
     GetDistributionMetricDataRequestRequestTypeDef,
     GetDistributionsRequestRequestTypeDef,
     GetDomainRequestRequestTypeDef,
+    GetDomainsRequestGetDomainsPaginateTypeDef,
     GetDomainsRequestRequestTypeDef,
+    GetExportSnapshotRecordsRequestGetExportSnapshotRecordsPaginateTypeDef,
     GetExportSnapshotRecordsRequestRequestTypeDef,
     GetInstanceAccessDetailsRequestRequestTypeDef,
     GetInstanceMetricDataRequestRequestTypeDef,
     GetInstancePortStatesRequestRequestTypeDef,
     InstancePortStateTypeDef,
     GetInstanceRequestRequestTypeDef,
     GetInstanceSnapshotRequestRequestTypeDef,
+    GetInstanceSnapshotsRequestGetInstanceSnapshotsPaginateTypeDef,
     GetInstanceSnapshotsRequestRequestTypeDef,
     GetInstanceStateRequestRequestTypeDef,
     InstanceStateTypeDef,
+    GetInstancesRequestGetInstancesPaginateTypeDef,
     GetInstancesRequestRequestTypeDef,
     GetKeyPairRequestRequestTypeDef,
+    GetKeyPairsRequestGetKeyPairsPaginateTypeDef,
     GetKeyPairsRequestRequestTypeDef,
     GetLoadBalancerMetricDataRequestRequestTypeDef,
     GetLoadBalancerRequestRequestTypeDef,
     GetLoadBalancerTlsCertificatesRequestRequestTypeDef,
     GetLoadBalancerTlsPoliciesRequestRequestTypeDef,
     LoadBalancerTlsPolicyTypeDef,
+    GetLoadBalancersRequestGetLoadBalancersPaginateTypeDef,
     GetLoadBalancersRequestRequestTypeDef,
     GetOperationRequestRequestTypeDef,
     GetOperationsForResourceRequestRequestTypeDef,
+    GetOperationsRequestGetOperationsPaginateTypeDef,
     GetOperationsRequestRequestTypeDef,
     GetRegionsRequestRequestTypeDef,
+    GetRelationalDatabaseBlueprintsRequestGetRelationalDatabaseBlueprintsPaginateTypeDef,
     GetRelationalDatabaseBlueprintsRequestRequestTypeDef,
     RelationalDatabaseBlueprintTypeDef,
+    GetRelationalDatabaseBundlesRequestGetRelationalDatabaseBundlesPaginateTypeDef,
     GetRelationalDatabaseBundlesRequestRequestTypeDef,
     RelationalDatabaseBundleTypeDef,
+    GetRelationalDatabaseEventsRequestGetRelationalDatabaseEventsPaginateTypeDef,
     GetRelationalDatabaseEventsRequestRequestTypeDef,
     RelationalDatabaseEventTypeDef,
     GetRelationalDatabaseLogEventsRequestRequestTypeDef,
     LogEventTypeDef,
     GetRelationalDatabaseLogStreamsRequestRequestTypeDef,
+    GetRelationalDatabaseLogStreamsResultTypeDef,
     GetRelationalDatabaseMasterUserPasswordRequestRequestTypeDef,
+    GetRelationalDatabaseMasterUserPasswordResultTypeDef,
     GetRelationalDatabaseMetricDataRequestRequestTypeDef,
+    GetRelationalDatabaseParametersRequestGetRelationalDatabaseParametersPaginateTypeDef,
     GetRelationalDatabaseParametersRequestRequestTypeDef,
     RelationalDatabaseParameterTypeDef,
     GetRelationalDatabaseRequestRequestTypeDef,
     GetRelationalDatabaseSnapshotRequestRequestTypeDef,
+    GetRelationalDatabaseSnapshotsRequestGetRelationalDatabaseSnapshotsPaginateTypeDef,
     GetRelationalDatabaseSnapshotsRequestRequestTypeDef,
+    GetRelationalDatabasesRequestGetRelationalDatabasesPaginateTypeDef,
     GetRelationalDatabasesRequestRequestTypeDef,
     GetStaticIpRequestRequestTypeDef,
+    GetStaticIpsRequestGetStaticIpsPaginateTypeDef,
     GetStaticIpsRequestRequestTypeDef,
     HostKeyAttributesTypeDef,
     ImportKeyPairRequestRequestTypeDef,
     PasswordDataTypeDef,
     InstanceHealthSummaryTypeDef,
     InstanceMetadataOptionsTypeDef,
     InstancePortInfoTypeDef,
     MonthlyTransferTypeDef,
+    IsVpcPeeredResultTypeDef,
     OriginTypeDef,
     LoadBalancerTlsCertificateDnsRecordCreationStateTypeDef,
     LoadBalancerTlsCertificateDomainValidationOptionTypeDef,
     LoadBalancerTlsCertificateSummaryTypeDef,
     NameServersUpdateStateTypeDef,
+    PaginatorConfigTypeDef,
     PendingMaintenanceActionTypeDef,
     PendingModifiedRelationalDatabaseValuesTypeDef,
     PutAlarmRequestRequestTypeDef,
     R53HostedZoneDeletionStateTypeDef,
     RebootInstanceRequestRequestTypeDef,
     RebootRelationalDatabaseRequestRequestTypeDef,
     RegisterContainerImageRequestRequestTypeDef,
     RelationalDatabaseEndpointTypeDef,
     RelationalDatabaseHardwareTypeDef,
     ReleaseStaticIpRequestRequestTypeDef,
     ResetDistributionCacheRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     SendContactMethodVerificationRequestRequestTypeDef,
     SetIpAddressTypeRequestRequestTypeDef,
     SetResourceAccessForBucketRequestRequestTypeDef,
+    StartGUISessionRequestRequestTypeDef,
     StartInstanceRequestRequestTypeDef,
     StartRelationalDatabaseRequestRequestTypeDef,
+    StopGUISessionRequestRequestTypeDef,
     StopInstanceRequestRequestTypeDef,
     StopRelationalDatabaseRequestRequestTypeDef,
     TestAlarmRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateBucketBundleRequestRequestTypeDef,
     UpdateDistributionBundleRequestRequestTypeDef,
     UpdateInstanceMetadataOptionsRequestRequestTypeDef,
@@ -626,21 +698,14 @@
     UpdateRelationalDatabaseRequestRequestTypeDef,
     AccessKeyTypeDef,
     AddOnRequestTypeDef,
     AlarmTypeDef,
     ContactMethodTypeDef,
     OperationTypeDef,
     StaticIpTypeDef,
-    DownloadDefaultKeyPairResultTypeDef,
-    GetActiveNamesResultTypeDef,
-    GetContainerAPIMetadataResultTypeDef,
-    GetDistributionLatestCacheResetResultTypeDef,
-    GetRelationalDatabaseLogStreamsResultTypeDef,
-    GetRelationalDatabaseMasterUserPasswordResultTypeDef,
-    IsVpcPeeredResultTypeDef,
     AutoSnapshotDetailsTypeDef,
     RegionTypeDef,
     GetBlueprintsResultTypeDef,
     UpdateBucketRequestRequestTypeDef,
     GetBucketBundlesResultTypeDef,
     BucketTypeDef,
     CreateBucketRequestRequestTypeDef,
@@ -674,37 +739,19 @@
     GetContainerLogResultTypeDef,
     GetContainerServicePowersResultTypeDef,
     CreateContainerServiceRegistryLoginResultTypeDef,
     CreateCloudFormationStackRequestRequestTypeDef,
     CreateDomainEntryRequestRequestTypeDef,
     DeleteDomainEntryRequestRequestTypeDef,
     UpdateDomainEntryRequestRequestTypeDef,
+    CreateGUISessionAccessDetailsResultTypeDef,
     InstanceSnapshotInfoTypeDef,
     GetDistributionBundlesResultTypeDef,
     DomainValidationRecordTypeDef,
-    GetActiveNamesRequestGetActiveNamesPaginateTypeDef,
-    GetBlueprintsRequestGetBlueprintsPaginateTypeDef,
-    GetBundlesRequestGetBundlesPaginateTypeDef,
-    GetCloudFormationStackRecordsRequestGetCloudFormationStackRecordsPaginateTypeDef,
-    GetDiskSnapshotsRequestGetDiskSnapshotsPaginateTypeDef,
-    GetDisksRequestGetDisksPaginateTypeDef,
-    GetDomainsRequestGetDomainsPaginateTypeDef,
-    GetExportSnapshotRecordsRequestGetExportSnapshotRecordsPaginateTypeDef,
-    GetInstanceSnapshotsRequestGetInstanceSnapshotsPaginateTypeDef,
-    GetInstancesRequestGetInstancesPaginateTypeDef,
-    GetKeyPairsRequestGetKeyPairsPaginateTypeDef,
-    GetLoadBalancersRequestGetLoadBalancersPaginateTypeDef,
-    GetOperationsRequestGetOperationsPaginateTypeDef,
-    GetRelationalDatabaseBlueprintsRequestGetRelationalDatabaseBlueprintsPaginateTypeDef,
-    GetRelationalDatabaseBundlesRequestGetRelationalDatabaseBundlesPaginateTypeDef,
-    GetRelationalDatabaseEventsRequestGetRelationalDatabaseEventsPaginateTypeDef,
-    GetRelationalDatabaseParametersRequestGetRelationalDatabaseParametersPaginateTypeDef,
-    GetRelationalDatabaseSnapshotsRequestGetRelationalDatabaseSnapshotsPaginateTypeDef,
-    GetRelationalDatabasesRequestGetRelationalDatabasesPaginateTypeDef,
-    GetStaticIpsRequestGetStaticIpsPaginateTypeDef,
+    EstimateByTimeTypeDef,
     GetBucketMetricDataResultTypeDef,
     GetContainerServiceMetricDataResultTypeDef,
     GetDistributionMetricDataResultTypeDef,
     GetInstanceMetricDataResultTypeDef,
     GetLoadBalancerMetricDataResultTypeDef,
     GetRelationalDatabaseMetricDataResultTypeDef,
     GetInstancePortStatesResultTypeDef,
@@ -792,16 +839,18 @@
     RebootInstanceResultTypeDef,
     RebootRelationalDatabaseResultTypeDef,
     ReleaseStaticIpResultTypeDef,
     ResetDistributionCacheResultTypeDef,
     SendContactMethodVerificationResultTypeDef,
     SetIpAddressTypeResultTypeDef,
     SetResourceAccessForBucketResultTypeDef,
+    StartGUISessionResultTypeDef,
     StartInstanceResultTypeDef,
     StartRelationalDatabaseResultTypeDef,
+    StopGUISessionResultTypeDef,
     StopInstanceResultTypeDef,
     StopRelationalDatabaseResultTypeDef,
     TagResourceResultTypeDef,
     TestAlarmResultTypeDef,
     UnpeerVpcResultTypeDef,
     UntagResourceResultTypeDef,
     UpdateBucketBundleResultTypeDef,
@@ -836,14 +885,15 @@
     GetCloudFormationStackRecordsResultTypeDef,
     UpdateContainerServiceRequestRequestTypeDef,
     ContainerServiceDeploymentTypeDef,
     ContainerServiceDeploymentRequestTypeDef,
     CreateContainerServiceDeploymentRequestRequestTypeDef,
     ExportSnapshotRecordSourceInfoTypeDef,
     RenewalSummaryTypeDef,
+    CostEstimateTypeDef,
     GetInstanceAccessDetailsResultTypeDef,
     LoadBalancerTlsCertificateTypeDef,
     GetLoadBalancerResultTypeDef,
     GetLoadBalancersResultTypeDef,
     DomainTypeDef,
     GetRelationalDatabaseResultTypeDef,
     GetRelationalDatabasesResultTypeDef,
@@ -853,25 +903,27 @@
     CreateDistributionResultTypeDef,
     GetDistributionsResultTypeDef,
     ContainerServiceTypeDef,
     GetContainerServiceDeploymentsResultTypeDef,
     CreateContainerServiceRequestRequestTypeDef,
     ExportSnapshotRecordTypeDef,
     CertificateTypeDef,
+    ResourceBudgetEstimateTypeDef,
     GetLoadBalancerTlsCertificatesResultTypeDef,
     GetDomainResultTypeDef,
     GetDomainsResultTypeDef,
     GetInstanceResultTypeDef,
     GetInstancesResultTypeDef,
     ContainerServicesListResultTypeDef,
     CreateContainerServiceDeploymentResultTypeDef,
     CreateContainerServiceResultTypeDef,
     UpdateContainerServiceResultTypeDef,
     GetExportSnapshotRecordsResultTypeDef,
     CertificateSummaryTypeDef,
+    GetCostEstimateResultTypeDef,
     CreateCertificateResultTypeDef,
     GetCertificatesResultTypeDef,
 )
 
 
 def get_structure() -> AccessKeyLastUsedTypeDef:
     return {...}
@@ -880,43 +932,43 @@
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

### Comparing `types-aiobotocore-lightsail-2.5.0.post1/setup.py` & `types-aiobotocore-lightsail-2.5.1/setup.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-lightsail.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-lightsail",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_lightsail"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Lightsail 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.Lightsail 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/"
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

### Comparing `types-aiobotocore-lightsail-2.5.0.post1/types_aiobotocore_lightsail/__init__.py` & `types-aiobotocore-lightsail-2.5.1/types_aiobotocore_lightsail/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-lightsail-2.5.0.post1/types_aiobotocore_lightsail/__init__.pyi` & `types-aiobotocore-lightsail-2.5.1/types_aiobotocore_lightsail/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-lightsail-2.5.0.post1/types_aiobotocore_lightsail/__main__.py` & `types-aiobotocore-lightsail-2.5.1/types_aiobotocore_lightsail/__main__.py`

 * *Files 15% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Lightsail 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Lightsail 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail\nOther"
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

### Comparing `types-aiobotocore-lightsail-2.5.0.post1/types_aiobotocore_lightsail/client.py` & `types-aiobotocore-lightsail-2.5.1/types_aiobotocore_lightsail/client.py`

 * *Files 1% similar despite different names*

```diff
@@ -18,14 +18,15 @@
 from datetime import datetime
 from typing import Any, Dict, Mapping, Sequence, Type, Union, overload
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import (
+    AddOnTypeType,
     AlarmStateType,
     BucketMetricNameType,
     CertificateStatusType,
     ComparisonOperatorType,
     ContactProtocolType,
     ContainerServiceMetricNameType,
     ContainerServicePowerNameType,
@@ -98,14 +99,15 @@
     CreateContainerServiceResultTypeDef,
     CreateDiskFromSnapshotResultTypeDef,
     CreateDiskResultTypeDef,
     CreateDiskSnapshotResultTypeDef,
     CreateDistributionResultTypeDef,
     CreateDomainEntryResultTypeDef,
     CreateDomainResultTypeDef,
+    CreateGUISessionAccessDetailsResultTypeDef,
     CreateInstancesFromSnapshotResultTypeDef,
     CreateInstanceSnapshotResultTypeDef,
     CreateInstancesResultTypeDef,
     CreateKeyPairResultTypeDef,
     CreateLoadBalancerResultTypeDef,
     CreateLoadBalancerTlsCertificateResultTypeDef,
     CreateRelationalDatabaseFromSnapshotResultTypeDef,
@@ -155,14 +157,15 @@
     GetContactMethodsResultTypeDef,
     GetContainerAPIMetadataResultTypeDef,
     GetContainerImagesResultTypeDef,
     GetContainerLogResultTypeDef,
     GetContainerServiceDeploymentsResultTypeDef,
     GetContainerServiceMetricDataResultTypeDef,
     GetContainerServicePowersResultTypeDef,
+    GetCostEstimateResultTypeDef,
     GetDiskResultTypeDef,
     GetDiskSnapshotResultTypeDef,
     GetDiskSnapshotsResultTypeDef,
     GetDisksResultTypeDef,
     GetDistributionBundlesResultTypeDef,
     GetDistributionLatestCacheResetResultTypeDef,
     GetDistributionMetricDataResultTypeDef,
@@ -218,16 +221,18 @@
     RegisterContainerImageResultTypeDef,
     RelationalDatabaseParameterTypeDef,
     ReleaseStaticIpResultTypeDef,
     ResetDistributionCacheResultTypeDef,
     SendContactMethodVerificationResultTypeDef,
     SetIpAddressTypeResultTypeDef,
     SetResourceAccessForBucketResultTypeDef,
+    StartGUISessionResultTypeDef,
     StartInstanceResultTypeDef,
     StartRelationalDatabaseResultTypeDef,
+    StopGUISessionResultTypeDef,
     StopInstanceResultTypeDef,
     StopRelationalDatabaseResultTypeDef,
     TagResourceResultTypeDef,
     TagTypeDef,
     TestAlarmResultTypeDef,
     UnpeerVpcResultTypeDef,
     UntagResourceResultTypeDef,
@@ -304,15 +309,15 @@
         network (CDN) distribution.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.attach_certificate_to_distribution)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#attach_certificate_to_distribution)
         """
 
     async def attach_disk(
-        self, *, diskName: str, instanceName: str, diskPath: str
+        self, *, diskName: str, instanceName: str, diskPath: str, autoMounting: bool = ...
     ) -> AttachDiskResultTypeDef:
         """
         Attaches a block storage disk to a running or stopped Lightsail instance and
         exposes it to the instance with the specified disk name.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.attach_disk)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#attach_disk)
@@ -504,15 +509,15 @@
         availabilityZone: str,
         sizeInGb: int,
         tags: Sequence[TagTypeDef] = ...,
         addOns: Sequence[AddOnRequestTypeDef] = ...
     ) -> CreateDiskResultTypeDef:
         """
         Creates a block storage disk that can be attached to an Amazon Lightsail
-        instance in the same Availability Zone (e.g., `us-east-2a` ).
+        instance in the same Availability Zone (e.g., `us-east-2a`).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.create_disk)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#create_disk)
         """
 
     async def create_disk_from_snapshot(
         self,
@@ -586,14 +591,25 @@
         zone: Address (A), canonical name (CNAME), mail exchanger (MX), name server
         (NS), start of authority (SOA), service locator (SRV), or text (TXT).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.create_domain_entry)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#create_domain_entry)
         """
 
+    async def create_gui_session_access_details(
+        self, *, resourceName: str
+    ) -> CreateGUISessionAccessDetailsResultTypeDef:
+        """
+        Creates two URLs that are used to access a virtual computer’s graphical user
+        interface (GUI) session.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.create_gui_session_access_details)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#create_gui_session_access_details)
+        """
+
     async def create_instance_snapshot(
         self, *, instanceSnapshotName: str, instanceName: str, tags: Sequence[TagTypeDef] = ...
     ) -> CreateInstanceSnapshotResultTypeDef:
         """
         Creates a snapshot of a specific virtual private server, or *instance*.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.create_instance_snapshot)
@@ -881,15 +897,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#delete_instance)
         """
 
     async def delete_instance_snapshot(
         self, *, instanceSnapshotName: str
     ) -> DeleteInstanceSnapshotResultTypeDef:
         """
-        Deletes a specific snapshot of a virtual private server (or *instance* ).
+        Deletes a specific snapshot of a virtual private server (or *instance*).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.delete_instance_snapshot)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#delete_instance_snapshot)
         """
 
     async def delete_key_pair(
         self, *, keyPairName: str, expectedFingerprint: str = ...
@@ -990,15 +1006,15 @@
         Detaches a static IP from the Amazon Lightsail instance to which it is attached.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.detach_static_ip)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#detach_static_ip)
         """
 
     async def disable_add_on(
-        self, *, addOnType: Literal["AutoSnapshot"], resourceName: str
+        self, *, addOnType: AddOnTypeType, resourceName: str
     ) -> DisableAddOnResultTypeDef:
         """
         Disables an add-on for an Amazon Lightsail resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.disable_add_on)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#disable_add_on)
         """
@@ -1067,15 +1083,19 @@
         Returns the available automatic snapshots for an instance or disk.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.get_auto_snapshots)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#get_auto_snapshots)
         """
 
     async def get_blueprints(
-        self, *, includeInactive: bool = ..., pageToken: str = ...
+        self,
+        *,
+        includeInactive: bool = ...,
+        pageToken: str = ...,
+        appCategory: Literal["LfR"] = ...
     ) -> GetBlueprintsResultTypeDef:
         """
         Returns the list of available instance images, or *blueprints*.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.get_blueprints)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#get_blueprints)
         """
@@ -1123,30 +1143,35 @@
         Returns information about one or more Amazon Lightsail buckets.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.get_buckets)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#get_buckets)
         """
 
     async def get_bundles(
-        self, *, includeInactive: bool = ..., pageToken: str = ...
+        self,
+        *,
+        includeInactive: bool = ...,
+        pageToken: str = ...,
+        appCategory: Literal["LfR"] = ...
     ) -> GetBundlesResultTypeDef:
         """
         Returns the bundles that you can apply to an Amazon Lightsail instance when you
         create it.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.get_bundles)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#get_bundles)
         """
 
     async def get_certificates(
         self,
         *,
         certificateStatuses: Sequence[CertificateStatusType] = ...,
         includeCertificateDetails: bool = ...,
-        certificateName: str = ...
+        certificateName: str = ...,
+        pageToken: str = ...
     ) -> GetCertificatesResultTypeDef:
         """
         Returns information about one or more Amazon Lightsail SSL/TLS certificates.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.get_certificates)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#get_certificates)
         """
@@ -1254,14 +1279,24 @@
         Returns information about one or more of your Amazon Lightsail container
         services.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.get_container_services)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#get_container_services)
         """
 
+    async def get_cost_estimate(
+        self, *, resourceName: str, startTime: Union[datetime, str], endTime: Union[datetime, str]
+    ) -> GetCostEstimateResultTypeDef:
+        """
+        Retrieves information about the cost estimate for a specified resource.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.get_cost_estimate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#get_cost_estimate)
+        """
+
     async def get_disk(self, *, diskName: str) -> GetDiskResultTypeDef:
         """
         Returns information about a specific block storage disk.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.get_disk)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#get_disk)
         """
@@ -1379,15 +1414,15 @@
         """
 
     async def get_instance_access_details(
         self, *, instanceName: str, protocol: InstanceAccessProtocolType = ...
     ) -> GetInstanceAccessDetailsResultTypeDef:
         """
         Returns temporary SSH keys you can use to connect to a specific virtual private
-        server, or *instance* .
+        server, or *instance*.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.get_instance_access_details)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#get_instance_access_details)
         """
 
     async def get_instance_metric_data(
         self,
@@ -1447,15 +1482,15 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.get_instance_state)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#get_instance_state)
         """
 
     async def get_instances(self, *, pageToken: str = ...) -> GetInstancesResultTypeDef:
         """
         Returns information about all Amazon Lightsail virtual private servers, or
-        *instances* .
+        *instances*.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.get_instances)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#get_instances)
         """
 
     async def get_key_pair(self, *, keyPairName: str) -> GetKeyPairResultTypeDef:
         """
@@ -1875,14 +1910,23 @@
         Sets the Amazon Lightsail resources that can access the specified Lightsail
         bucket.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.set_resource_access_for_bucket)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#set_resource_access_for_bucket)
         """
 
+    async def start_gui_session(self, *, resourceName: str) -> StartGUISessionResultTypeDef:
+        """
+        Initiates a graphical user interface (GUI) session that’s used to access a
+        virtual computer’s operating system and application.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.start_gui_session)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#start_gui_session)
+        """
+
     async def start_instance(self, *, instanceName: str) -> StartInstanceResultTypeDef:
         """
         Starts a specific Amazon Lightsail instance from a stopped state.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.start_instance)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#start_instance)
         """
@@ -1893,14 +1937,23 @@
         """
         Starts a specific database from a stopped state in Amazon Lightsail.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.start_relational_database)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#start_relational_database)
         """
 
+    async def stop_gui_session(self, *, resourceName: str) -> StopGUISessionResultTypeDef:
+        """
+        Terminates a web-based NICE DCV session that’s used to access a virtual
+        computer’s operating system or application.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.stop_gui_session)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#stop_gui_session)
+        """
+
     async def stop_instance(
         self, *, instanceName: str, force: bool = ...
     ) -> StopInstanceResultTypeDef:
         """
         Stops a specific Amazon Lightsail instance that is currently running.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.stop_instance)
```

#### encoding

```diff
@@ -1 +1 @@
-us-ascii
+utf-8
```

### Comparing `types-aiobotocore-lightsail-2.5.0.post1/types_aiobotocore_lightsail/client.pyi` & `types-aiobotocore-lightsail-2.5.1/types_aiobotocore_lightsail/client.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -18,14 +18,15 @@
 from datetime import datetime
 from typing import Any, Dict, Mapping, Sequence, Type, Union, overload
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import (
+    AddOnTypeType,
     AlarmStateType,
     BucketMetricNameType,
     CertificateStatusType,
     ComparisonOperatorType,
     ContactProtocolType,
     ContainerServiceMetricNameType,
     ContainerServicePowerNameType,
@@ -98,14 +99,15 @@
     CreateContainerServiceResultTypeDef,
     CreateDiskFromSnapshotResultTypeDef,
     CreateDiskResultTypeDef,
     CreateDiskSnapshotResultTypeDef,
     CreateDistributionResultTypeDef,
     CreateDomainEntryResultTypeDef,
     CreateDomainResultTypeDef,
+    CreateGUISessionAccessDetailsResultTypeDef,
     CreateInstancesFromSnapshotResultTypeDef,
     CreateInstanceSnapshotResultTypeDef,
     CreateInstancesResultTypeDef,
     CreateKeyPairResultTypeDef,
     CreateLoadBalancerResultTypeDef,
     CreateLoadBalancerTlsCertificateResultTypeDef,
     CreateRelationalDatabaseFromSnapshotResultTypeDef,
@@ -155,14 +157,15 @@
     GetContactMethodsResultTypeDef,
     GetContainerAPIMetadataResultTypeDef,
     GetContainerImagesResultTypeDef,
     GetContainerLogResultTypeDef,
     GetContainerServiceDeploymentsResultTypeDef,
     GetContainerServiceMetricDataResultTypeDef,
     GetContainerServicePowersResultTypeDef,
+    GetCostEstimateResultTypeDef,
     GetDiskResultTypeDef,
     GetDiskSnapshotResultTypeDef,
     GetDiskSnapshotsResultTypeDef,
     GetDisksResultTypeDef,
     GetDistributionBundlesResultTypeDef,
     GetDistributionLatestCacheResetResultTypeDef,
     GetDistributionMetricDataResultTypeDef,
@@ -218,16 +221,18 @@
     RegisterContainerImageResultTypeDef,
     RelationalDatabaseParameterTypeDef,
     ReleaseStaticIpResultTypeDef,
     ResetDistributionCacheResultTypeDef,
     SendContactMethodVerificationResultTypeDef,
     SetIpAddressTypeResultTypeDef,
     SetResourceAccessForBucketResultTypeDef,
+    StartGUISessionResultTypeDef,
     StartInstanceResultTypeDef,
     StartRelationalDatabaseResultTypeDef,
+    StopGUISessionResultTypeDef,
     StopInstanceResultTypeDef,
     StopRelationalDatabaseResultTypeDef,
     TagResourceResultTypeDef,
     TagTypeDef,
     TestAlarmResultTypeDef,
     UnpeerVpcResultTypeDef,
     UntagResourceResultTypeDef,
@@ -297,15 +302,15 @@
         Attaches an SSL/TLS certificate to your Amazon Lightsail content delivery
         network (CDN) distribution.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.attach_certificate_to_distribution)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#attach_certificate_to_distribution)
         """
     async def attach_disk(
-        self, *, diskName: str, instanceName: str, diskPath: str
+        self, *, diskName: str, instanceName: str, diskPath: str, autoMounting: bool = ...
     ) -> AttachDiskResultTypeDef:
         """
         Attaches a block storage disk to a running or stopped Lightsail instance and
         exposes it to the instance with the specified disk name.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.attach_disk)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#attach_disk)
@@ -481,15 +486,15 @@
         availabilityZone: str,
         sizeInGb: int,
         tags: Sequence[TagTypeDef] = ...,
         addOns: Sequence[AddOnRequestTypeDef] = ...
     ) -> CreateDiskResultTypeDef:
         """
         Creates a block storage disk that can be attached to an Amazon Lightsail
-        instance in the same Availability Zone (e.g., `us-east-2a` ).
+        instance in the same Availability Zone (e.g., `us-east-2a`).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.create_disk)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#create_disk)
         """
     async def create_disk_from_snapshot(
         self,
         *,
@@ -557,14 +562,24 @@
         Creates one of the following domain name system (DNS) records in a domain DNS
         zone: Address (A), canonical name (CNAME), mail exchanger (MX), name server
         (NS), start of authority (SOA), service locator (SRV), or text (TXT).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.create_domain_entry)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#create_domain_entry)
         """
+    async def create_gui_session_access_details(
+        self, *, resourceName: str
+    ) -> CreateGUISessionAccessDetailsResultTypeDef:
+        """
+        Creates two URLs that are used to access a virtual computer’s graphical user
+        interface (GUI) session.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.create_gui_session_access_details)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#create_gui_session_access_details)
+        """
     async def create_instance_snapshot(
         self, *, instanceSnapshotName: str, instanceName: str, tags: Sequence[TagTypeDef] = ...
     ) -> CreateInstanceSnapshotResultTypeDef:
         """
         Creates a snapshot of a specific virtual private server, or *instance*.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.create_instance_snapshot)
@@ -829,15 +844,15 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.delete_instance)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#delete_instance)
         """
     async def delete_instance_snapshot(
         self, *, instanceSnapshotName: str
     ) -> DeleteInstanceSnapshotResultTypeDef:
         """
-        Deletes a specific snapshot of a virtual private server (or *instance* ).
+        Deletes a specific snapshot of a virtual private server (or *instance*).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.delete_instance_snapshot)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#delete_instance_snapshot)
         """
     async def delete_key_pair(
         self, *, keyPairName: str, expectedFingerprint: str = ...
     ) -> DeleteKeyPairResultTypeDef:
@@ -927,15 +942,15 @@
         """
         Detaches a static IP from the Amazon Lightsail instance to which it is attached.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.detach_static_ip)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#detach_static_ip)
         """
     async def disable_add_on(
-        self, *, addOnType: Literal["AutoSnapshot"], resourceName: str
+        self, *, addOnType: AddOnTypeType, resourceName: str
     ) -> DisableAddOnResultTypeDef:
         """
         Disables an add-on for an Amazon Lightsail resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.disable_add_on)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#disable_add_on)
         """
@@ -996,15 +1011,19 @@
         """
         Returns the available automatic snapshots for an instance or disk.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.get_auto_snapshots)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#get_auto_snapshots)
         """
     async def get_blueprints(
-        self, *, includeInactive: bool = ..., pageToken: str = ...
+        self,
+        *,
+        includeInactive: bool = ...,
+        pageToken: str = ...,
+        appCategory: Literal["LfR"] = ...
     ) -> GetBlueprintsResultTypeDef:
         """
         Returns the list of available instance images, or *blueprints*.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.get_blueprints)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#get_blueprints)
         """
@@ -1047,29 +1066,34 @@
         """
         Returns information about one or more Amazon Lightsail buckets.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.get_buckets)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#get_buckets)
         """
     async def get_bundles(
-        self, *, includeInactive: bool = ..., pageToken: str = ...
+        self,
+        *,
+        includeInactive: bool = ...,
+        pageToken: str = ...,
+        appCategory: Literal["LfR"] = ...
     ) -> GetBundlesResultTypeDef:
         """
         Returns the bundles that you can apply to an Amazon Lightsail instance when you
         create it.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.get_bundles)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#get_bundles)
         """
     async def get_certificates(
         self,
         *,
         certificateStatuses: Sequence[CertificateStatusType] = ...,
         includeCertificateDetails: bool = ...,
-        certificateName: str = ...
+        certificateName: str = ...,
+        pageToken: str = ...
     ) -> GetCertificatesResultTypeDef:
         """
         Returns information about one or more Amazon Lightsail SSL/TLS certificates.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.get_certificates)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#get_certificates)
         """
@@ -1167,14 +1191,23 @@
         """
         Returns information about one or more of your Amazon Lightsail container
         services.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.get_container_services)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#get_container_services)
         """
+    async def get_cost_estimate(
+        self, *, resourceName: str, startTime: Union[datetime, str], endTime: Union[datetime, str]
+    ) -> GetCostEstimateResultTypeDef:
+        """
+        Retrieves information about the cost estimate for a specified resource.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.get_cost_estimate)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#get_cost_estimate)
+        """
     async def get_disk(self, *, diskName: str) -> GetDiskResultTypeDef:
         """
         Returns information about a specific block storage disk.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.get_disk)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#get_disk)
         """
@@ -1280,15 +1313,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#get_instance)
         """
     async def get_instance_access_details(
         self, *, instanceName: str, protocol: InstanceAccessProtocolType = ...
     ) -> GetInstanceAccessDetailsResultTypeDef:
         """
         Returns temporary SSH keys you can use to connect to a specific virtual private
-        server, or *instance* .
+        server, or *instance*.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.get_instance_access_details)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#get_instance_access_details)
         """
     async def get_instance_metric_data(
         self,
         *,
@@ -1342,15 +1375,15 @@
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.get_instance_state)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#get_instance_state)
         """
     async def get_instances(self, *, pageToken: str = ...) -> GetInstancesResultTypeDef:
         """
         Returns information about all Amazon Lightsail virtual private servers, or
-        *instances* .
+        *instances*.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.get_instances)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#get_instances)
         """
     async def get_key_pair(self, *, keyPairName: str) -> GetKeyPairResultTypeDef:
         """
         Returns information about a specific key pair.
@@ -1730,14 +1763,22 @@
         """
         Sets the Amazon Lightsail resources that can access the specified Lightsail
         bucket.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.set_resource_access_for_bucket)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#set_resource_access_for_bucket)
         """
+    async def start_gui_session(self, *, resourceName: str) -> StartGUISessionResultTypeDef:
+        """
+        Initiates a graphical user interface (GUI) session that’s used to access a
+        virtual computer’s operating system and application.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.start_gui_session)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#start_gui_session)
+        """
     async def start_instance(self, *, instanceName: str) -> StartInstanceResultTypeDef:
         """
         Starts a specific Amazon Lightsail instance from a stopped state.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.start_instance)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#start_instance)
         """
@@ -1746,14 +1787,22 @@
     ) -> StartRelationalDatabaseResultTypeDef:
         """
         Starts a specific database from a stopped state in Amazon Lightsail.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.start_relational_database)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#start_relational_database)
         """
+    async def stop_gui_session(self, *, resourceName: str) -> StopGUISessionResultTypeDef:
+        """
+        Terminates a web-based NICE DCV session that’s used to access a virtual
+        computer’s operating system or application.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.stop_gui_session)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/client/#stop_gui_session)
+        """
     async def stop_instance(
         self, *, instanceName: str, force: bool = ...
     ) -> StopInstanceResultTypeDef:
         """
         Stops a specific Amazon Lightsail instance that is currently running.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Client.stop_instance)
```

#### encoding

```diff
@@ -1 +1 @@
-us-ascii
+utf-8
```

### Comparing `types-aiobotocore-lightsail-2.5.0.post1/types_aiobotocore_lightsail/literals.py` & `types-aiobotocore-lightsail-2.5.1/types_aiobotocore_lightsail/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -21,14 +21,16 @@
 
 __all__ = (
     "AccessDirectionType",
     "AccessTypeType",
     "AccountLevelBpaSyncStatusType",
     "AddOnTypeType",
     "AlarmStateType",
+    "AppCategoryType",
+    "AutoMountStatusType",
     "AutoSnapshotStatusType",
     "BPAStatusMessageType",
     "BehaviorEnumType",
     "BlueprintTypeType",
     "BucketMetricNameType",
     "CertificateDomainValidationStatusType",
     "CertificateStatusType",
@@ -39,14 +41,15 @@
     "ContactProtocolType",
     "ContainerServiceDeploymentStateType",
     "ContainerServiceMetricNameType",
     "ContainerServicePowerNameType",
     "ContainerServiceProtocolType",
     "ContainerServiceStateDetailCodeType",
     "ContainerServiceStateType",
+    "CurrencyType",
     "DiskSnapshotStateType",
     "DiskStateType",
     "DistributionMetricNameType",
     "DnsRecordCreationStateCodeType",
     "ExportSnapshotRecordSourceTypeType",
     "ForwardValuesType",
     "GetActiveNamesPaginatorName",
@@ -98,38 +101,42 @@
     "NetworkProtocolType",
     "OperationStatusType",
     "OperationTypeType",
     "OriginProtocolPolicyEnumType",
     "PortAccessTypeType",
     "PortInfoSourceTypeType",
     "PortStateType",
+    "PricingUnitType",
     "R53HostedZoneDeletionStateCodeType",
     "RecordStateType",
     "RegionNameType",
     "RelationalDatabaseEngineType",
     "RelationalDatabaseMetricNameType",
     "RelationalDatabasePasswordVersionType",
     "RenewalStatusType",
     "ResourceBucketAccessType",
     "ResourceTypeType",
+    "StatusType",
     "StatusTypeType",
     "TreatMissingDataType",
     "LightsailServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
 
 AccessDirectionType = Literal["inbound", "outbound"]
 AccessTypeType = Literal["private", "public"]
 AccountLevelBpaSyncStatusType = Literal["Defaulted", "Failed", "InSync", "NeverSynced"]
-AddOnTypeType = Literal["AutoSnapshot"]
+AddOnTypeType = Literal["AutoSnapshot", "StopInstanceOnIdle"]
 AlarmStateType = Literal["ALARM", "INSUFFICIENT_DATA", "OK"]
+AppCategoryType = Literal["LfR"]
+AutoMountStatusType = Literal["Failed", "Mounted", "NotMounted", "Pending"]
 AutoSnapshotStatusType = Literal["Failed", "InProgress", "NotFound", "Success"]
 BPAStatusMessageType = Literal[
     "DEFAULTED_FOR_SLR_MISSING", "DEFAULTED_FOR_SLR_MISSING_ON_HOLD", "SYNC_ON_HOLD", "Unknown"
 ]
 BehaviorEnumType = Literal["cache", "dont-cache"]
 BlueprintTypeType = Literal["app", "os"]
 BucketMetricNameType = Literal["BucketSizeBytes", "NumberOfObjects"]
@@ -167,14 +174,15 @@
     "PROVISIONING_CERTIFICATE",
     "PROVISIONING_SERVICE",
     "UNKNOWN_ERROR",
 ]
 ContainerServiceStateType = Literal[
     "DELETING", "DEPLOYING", "DISABLED", "PENDING", "READY", "RUNNING", "UPDATING"
 ]
+CurrencyType = Literal["USD"]
 DiskSnapshotStateType = Literal["completed", "error", "pending", "unknown"]
 DiskStateType = Literal["available", "error", "in-use", "pending", "unknown"]
 DistributionMetricNameType = Literal[
     "BytesDownloaded",
     "BytesUploaded",
     "Http4xxErrorRate",
     "Http5xxErrorRate",
@@ -435,16 +443,18 @@
     "RebootRelationalDatabase",
     "RegisterContainerImage",
     "ReleaseStaticIp",
     "ResetDistributionCache",
     "SendContactMethodVerification",
     "SetIpAddressType",
     "SetResourceAccessForBucket",
+    "StartGUISession",
     "StartInstance",
     "StartRelationalDatabase",
+    "StopGUISession",
     "StopInstance",
     "StopRelationalDatabase",
     "TestAlarm",
     "UpdateBucket",
     "UpdateBucketBundle",
     "UpdateContainerService",
     "UpdateDistribution",
@@ -455,14 +465,15 @@
     "UpdateRelationalDatabase",
     "UpdateRelationalDatabaseParameters",
 ]
 OriginProtocolPolicyEnumType = Literal["http-only", "https-only"]
 PortAccessTypeType = Literal["Private", "Public"]
 PortInfoSourceTypeType = Literal["CLOSED", "DEFAULT", "INSTANCE", "NONE"]
 PortStateType = Literal["closed", "open"]
+PricingUnitType = Literal["Bundles", "GB", "GB-Mo", "Hrs", "Queries"]
 R53HostedZoneDeletionStateCodeType = Literal["FAILED", "PENDING", "STARTED", "SUCCEEDED"]
 RecordStateType = Literal["Failed", "Started", "Succeeded"]
 RegionNameType = Literal[
     "ap-northeast-1",
     "ap-northeast-2",
     "ap-south-1",
     "ap-southeast-1",
@@ -508,14 +519,26 @@
     "LoadBalancer",
     "LoadBalancerTlsCertificate",
     "PeeredVpc",
     "RelationalDatabase",
     "RelationalDatabaseSnapshot",
     "StaticIp",
 ]
+StatusType = Literal[
+    "failedInstanceCreation",
+    "failedStartingGUISession",
+    "failedStoppingGUISession",
+    "notStarted",
+    "settingUpInstance",
+    "startExpired",
+    "started",
+    "starting",
+    "stopped",
+    "stopping",
+]
 StatusTypeType = Literal["Active", "Inactive"]
 TreatMissingDataType = Literal["breaching", "ignore", "missing", "notBreaching"]
 LightsailServiceName = Literal["lightsail"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
@@ -573,14 +596,15 @@
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
@@ -659,14 +683,15 @@
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
@@ -677,14 +702,15 @@
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
@@ -720,14 +746,15 @@
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
@@ -746,16 +773,19 @@
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
@@ -839,15 +869,17 @@
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

### Comparing `types-aiobotocore-lightsail-2.5.0.post1/types_aiobotocore_lightsail/literals.pyi` & `types-aiobotocore-lightsail-2.5.1/types_aiobotocore_lightsail/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -20,14 +20,16 @@
 
 __all__ = (
     "AccessDirectionType",
     "AccessTypeType",
     "AccountLevelBpaSyncStatusType",
     "AddOnTypeType",
     "AlarmStateType",
+    "AppCategoryType",
+    "AutoMountStatusType",
     "AutoSnapshotStatusType",
     "BPAStatusMessageType",
     "BehaviorEnumType",
     "BlueprintTypeType",
     "BucketMetricNameType",
     "CertificateDomainValidationStatusType",
     "CertificateStatusType",
@@ -38,14 +40,15 @@
     "ContactProtocolType",
     "ContainerServiceDeploymentStateType",
     "ContainerServiceMetricNameType",
     "ContainerServicePowerNameType",
     "ContainerServiceProtocolType",
     "ContainerServiceStateDetailCodeType",
     "ContainerServiceStateType",
+    "CurrencyType",
     "DiskSnapshotStateType",
     "DiskStateType",
     "DistributionMetricNameType",
     "DnsRecordCreationStateCodeType",
     "ExportSnapshotRecordSourceTypeType",
     "ForwardValuesType",
     "GetActiveNamesPaginatorName",
@@ -97,37 +100,41 @@
     "NetworkProtocolType",
     "OperationStatusType",
     "OperationTypeType",
     "OriginProtocolPolicyEnumType",
     "PortAccessTypeType",
     "PortInfoSourceTypeType",
     "PortStateType",
+    "PricingUnitType",
     "R53HostedZoneDeletionStateCodeType",
     "RecordStateType",
     "RegionNameType",
     "RelationalDatabaseEngineType",
     "RelationalDatabaseMetricNameType",
     "RelationalDatabasePasswordVersionType",
     "RenewalStatusType",
     "ResourceBucketAccessType",
     "ResourceTypeType",
+    "StatusType",
     "StatusTypeType",
     "TreatMissingDataType",
     "LightsailServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
 AccessDirectionType = Literal["inbound", "outbound"]
 AccessTypeType = Literal["private", "public"]
 AccountLevelBpaSyncStatusType = Literal["Defaulted", "Failed", "InSync", "NeverSynced"]
-AddOnTypeType = Literal["AutoSnapshot"]
+AddOnTypeType = Literal["AutoSnapshot", "StopInstanceOnIdle"]
 AlarmStateType = Literal["ALARM", "INSUFFICIENT_DATA", "OK"]
+AppCategoryType = Literal["LfR"]
+AutoMountStatusType = Literal["Failed", "Mounted", "NotMounted", "Pending"]
 AutoSnapshotStatusType = Literal["Failed", "InProgress", "NotFound", "Success"]
 BPAStatusMessageType = Literal[
     "DEFAULTED_FOR_SLR_MISSING", "DEFAULTED_FOR_SLR_MISSING_ON_HOLD", "SYNC_ON_HOLD", "Unknown"
 ]
 BehaviorEnumType = Literal["cache", "dont-cache"]
 BlueprintTypeType = Literal["app", "os"]
 BucketMetricNameType = Literal["BucketSizeBytes", "NumberOfObjects"]
@@ -165,14 +172,15 @@
     "PROVISIONING_CERTIFICATE",
     "PROVISIONING_SERVICE",
     "UNKNOWN_ERROR",
 ]
 ContainerServiceStateType = Literal[
     "DELETING", "DEPLOYING", "DISABLED", "PENDING", "READY", "RUNNING", "UPDATING"
 ]
+CurrencyType = Literal["USD"]
 DiskSnapshotStateType = Literal["completed", "error", "pending", "unknown"]
 DiskStateType = Literal["available", "error", "in-use", "pending", "unknown"]
 DistributionMetricNameType = Literal[
     "BytesDownloaded",
     "BytesUploaded",
     "Http4xxErrorRate",
     "Http5xxErrorRate",
@@ -433,16 +441,18 @@
     "RebootRelationalDatabase",
     "RegisterContainerImage",
     "ReleaseStaticIp",
     "ResetDistributionCache",
     "SendContactMethodVerification",
     "SetIpAddressType",
     "SetResourceAccessForBucket",
+    "StartGUISession",
     "StartInstance",
     "StartRelationalDatabase",
+    "StopGUISession",
     "StopInstance",
     "StopRelationalDatabase",
     "TestAlarm",
     "UpdateBucket",
     "UpdateBucketBundle",
     "UpdateContainerService",
     "UpdateDistribution",
@@ -453,14 +463,15 @@
     "UpdateRelationalDatabase",
     "UpdateRelationalDatabaseParameters",
 ]
 OriginProtocolPolicyEnumType = Literal["http-only", "https-only"]
 PortAccessTypeType = Literal["Private", "Public"]
 PortInfoSourceTypeType = Literal["CLOSED", "DEFAULT", "INSTANCE", "NONE"]
 PortStateType = Literal["closed", "open"]
+PricingUnitType = Literal["Bundles", "GB", "GB-Mo", "Hrs", "Queries"]
 R53HostedZoneDeletionStateCodeType = Literal["FAILED", "PENDING", "STARTED", "SUCCEEDED"]
 RecordStateType = Literal["Failed", "Started", "Succeeded"]
 RegionNameType = Literal[
     "ap-northeast-1",
     "ap-northeast-2",
     "ap-south-1",
     "ap-southeast-1",
@@ -506,14 +517,26 @@
     "LoadBalancer",
     "LoadBalancerTlsCertificate",
     "PeeredVpc",
     "RelationalDatabase",
     "RelationalDatabaseSnapshot",
     "StaticIp",
 ]
+StatusType = Literal[
+    "failedInstanceCreation",
+    "failedStartingGUISession",
+    "failedStoppingGUISession",
+    "notStarted",
+    "settingUpInstance",
+    "startExpired",
+    "started",
+    "starting",
+    "stopped",
+    "stopping",
+]
 StatusTypeType = Literal["Active", "Inactive"]
 TreatMissingDataType = Literal["breaching", "ignore", "missing", "notBreaching"]
 LightsailServiceName = Literal["lightsail"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
@@ -571,14 +594,15 @@
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
@@ -657,14 +681,15 @@
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
@@ -675,14 +700,15 @@
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
@@ -718,14 +744,15 @@
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
@@ -744,16 +771,19 @@
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
@@ -837,15 +867,17 @@
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

### Comparing `types-aiobotocore-lightsail-2.5.0.post1/types_aiobotocore_lightsail/paginator.py` & `types-aiobotocore-lightsail-2.5.1/types_aiobotocore_lightsail/paginator.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -55,15 +55,15 @@
         get_relational_database_parameters_paginator: GetRelationalDatabaseParametersPaginator = client.get_paginator("get_relational_database_parameters")
         get_relational_database_snapshots_paginator: GetRelationalDatabaseSnapshotsPaginator = client.get_paginator("get_relational_database_snapshots")
         get_relational_databases_paginator: GetRelationalDatabasesPaginator = client.get_paginator("get_relational_databases")
         get_static_ips_paginator: GetStaticIpsPaginator = client.get_paginator("get_static_ips")
     ```
 """
 import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     GetActiveNamesResultTypeDef,
     GetBlueprintsResultTypeDef,
@@ -84,19 +84,18 @@
     GetRelationalDatabaseParametersResultTypeDef,
     GetRelationalDatabaseSnapshotsResultTypeDef,
     GetRelationalDatabasesResultTypeDef,
     GetStaticIpsResultTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
+if sys.version_info >= (3, 9):
+    from typing import Literal
 else:
-    from typing_extensions import AsyncIterator
-
+    from typing_extensions import Literal
 
 __all__ = (
     "GetActiveNamesPaginator",
     "GetBlueprintsPaginator",
     "GetBundlesPaginator",
     "GetCloudFormationStackRecordsPaginator",
     "GetDiskSnapshotsPaginator",
@@ -113,320 +112,306 @@
     "GetRelationalDatabaseEventsPaginator",
     "GetRelationalDatabaseParametersPaginator",
     "GetRelationalDatabaseSnapshotsPaginator",
     "GetRelationalDatabasesPaginator",
     "GetStaticIpsPaginator",
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
 class GetActiveNamesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetActiveNames)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getactivenamespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetActiveNamesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetActiveNames.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getactivenamespaginator)
         """
 
-
 class GetBlueprintsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetBlueprints)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getblueprintspaginator)
     """
 
     def paginate(
-        self, *, includeInactive: bool = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        includeInactive: bool = ...,
+        appCategory: Literal["LfR"] = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetBlueprintsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetBlueprints.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getblueprintspaginator)
         """
 
-
 class GetBundlesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetBundles)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getbundlespaginator)
     """
 
     def paginate(
-        self, *, includeInactive: bool = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        includeInactive: bool = ...,
+        appCategory: Literal["LfR"] = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetBundlesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetBundles.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getbundlespaginator)
         """
 
-
 class GetCloudFormationStackRecordsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetCloudFormationStackRecords)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getcloudformationstackrecordspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetCloudFormationStackRecordsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetCloudFormationStackRecords.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getcloudformationstackrecordspaginator)
         """
 
-
 class GetDiskSnapshotsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetDiskSnapshots)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getdisksnapshotspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetDiskSnapshotsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetDiskSnapshots.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getdisksnapshotspaginator)
         """
 
-
 class GetDisksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetDisks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getdiskspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetDisksResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetDisks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getdiskspaginator)
         """
 
-
 class GetDomainsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetDomains)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getdomainspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetDomainsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetDomains.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getdomainspaginator)
         """
 
-
 class GetExportSnapshotRecordsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetExportSnapshotRecords)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getexportsnapshotrecordspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetExportSnapshotRecordsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetExportSnapshotRecords.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getexportsnapshotrecordspaginator)
         """
 
-
 class GetInstanceSnapshotsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetInstanceSnapshots)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getinstancesnapshotspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetInstanceSnapshotsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetInstanceSnapshots.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getinstancesnapshotspaginator)
         """
 
-
 class GetInstancesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetInstances)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getinstancespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetInstancesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getinstancespaginator)
         """
 
-
 class GetKeyPairsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetKeyPairs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getkeypairspaginator)
     """
 
     def paginate(
-        self, *, includeDefaultKeyPair: bool = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, includeDefaultKeyPair: bool = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetKeyPairsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetKeyPairs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getkeypairspaginator)
         """
 
-
 class GetLoadBalancersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetLoadBalancers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getloadbalancerspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetLoadBalancersResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetLoadBalancers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getloadbalancerspaginator)
         """
 
-
 class GetOperationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetOperations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getoperationspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetOperationsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetOperations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getoperationspaginator)
         """
 
-
 class GetRelationalDatabaseBlueprintsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetRelationalDatabaseBlueprints)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getrelationaldatabaseblueprintspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetRelationalDatabaseBlueprintsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetRelationalDatabaseBlueprints.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getrelationaldatabaseblueprintspaginator)
         """
 
-
 class GetRelationalDatabaseBundlesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetRelationalDatabaseBundles)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getrelationaldatabasebundlespaginator)
     """
 
     def paginate(
-        self, *, includeInactive: bool = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, includeInactive: bool = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetRelationalDatabaseBundlesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetRelationalDatabaseBundles.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getrelationaldatabasebundlespaginator)
         """
 
-
 class GetRelationalDatabaseEventsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetRelationalDatabaseEvents)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getrelationaldatabaseeventspaginator)
     """
 
     def paginate(
         self,
         *,
         relationalDatabaseName: str,
         durationInMinutes: int = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetRelationalDatabaseEventsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetRelationalDatabaseEvents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getrelationaldatabaseeventspaginator)
         """
 
-
 class GetRelationalDatabaseParametersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetRelationalDatabaseParameters)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getrelationaldatabaseparameterspaginator)
     """
 
     def paginate(
-        self, *, relationalDatabaseName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, relationalDatabaseName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetRelationalDatabaseParametersResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetRelationalDatabaseParameters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getrelationaldatabaseparameterspaginator)
         """
 
-
 class GetRelationalDatabaseSnapshotsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetRelationalDatabaseSnapshots)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getrelationaldatabasesnapshotspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetRelationalDatabaseSnapshotsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetRelationalDatabaseSnapshots.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getrelationaldatabasesnapshotspaginator)
         """
 
-
 class GetRelationalDatabasesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetRelationalDatabases)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getrelationaldatabasespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetRelationalDatabasesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetRelationalDatabases.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getrelationaldatabasespaginator)
         """
 
-
 class GetStaticIpsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetStaticIps)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getstaticipspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetStaticIpsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetStaticIps.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getstaticipspaginator)
         """
```

### Comparing `types-aiobotocore-lightsail-2.5.0.post1/types_aiobotocore_lightsail/paginator.pyi` & `types-aiobotocore-lightsail-2.5.1/types_aiobotocore_lightsail/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -55,15 +55,15 @@
         get_relational_database_parameters_paginator: GetRelationalDatabaseParametersPaginator = client.get_paginator("get_relational_database_parameters")
         get_relational_database_snapshots_paginator: GetRelationalDatabaseSnapshotsPaginator = client.get_paginator("get_relational_database_snapshots")
         get_relational_databases_paginator: GetRelationalDatabasesPaginator = client.get_paginator("get_relational_databases")
         get_static_ips_paginator: GetStaticIpsPaginator = client.get_paginator("get_static_ips")
     ```
 """
 import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     GetActiveNamesResultTypeDef,
     GetBlueprintsResultTypeDef,
@@ -84,18 +84,19 @@
     GetRelationalDatabaseParametersResultTypeDef,
     GetRelationalDatabaseSnapshotsResultTypeDef,
     GetRelationalDatabasesResultTypeDef,
     GetStaticIpsResultTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
+if sys.version_info >= (3, 9):
+    from typing import Literal
 else:
-    from typing_extensions import AsyncIterator
+    from typing_extensions import Literal
+
 
 __all__ = (
     "GetActiveNamesPaginator",
     "GetBlueprintsPaginator",
     "GetBundlesPaginator",
     "GetCloudFormationStackRecordsPaginator",
     "GetDiskSnapshotsPaginator",
@@ -112,298 +113,328 @@
     "GetRelationalDatabaseEventsPaginator",
     "GetRelationalDatabaseParametersPaginator",
     "GetRelationalDatabaseSnapshotsPaginator",
     "GetRelationalDatabasesPaginator",
     "GetStaticIpsPaginator",
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
 class GetActiveNamesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetActiveNames)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getactivenamespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetActiveNamesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetActiveNames.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getactivenamespaginator)
         """
 
+
 class GetBlueprintsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetBlueprints)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getblueprintspaginator)
     """
 
     def paginate(
-        self, *, includeInactive: bool = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        includeInactive: bool = ...,
+        appCategory: Literal["LfR"] = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetBlueprintsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetBlueprints.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getblueprintspaginator)
         """
 
+
 class GetBundlesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetBundles)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getbundlespaginator)
     """
 
     def paginate(
-        self, *, includeInactive: bool = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self,
+        *,
+        includeInactive: bool = ...,
+        appCategory: Literal["LfR"] = ...,
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetBundlesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetBundles.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getbundlespaginator)
         """
 
+
 class GetCloudFormationStackRecordsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetCloudFormationStackRecords)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getcloudformationstackrecordspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetCloudFormationStackRecordsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetCloudFormationStackRecords.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getcloudformationstackrecordspaginator)
         """
 
+
 class GetDiskSnapshotsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetDiskSnapshots)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getdisksnapshotspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetDiskSnapshotsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetDiskSnapshots.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getdisksnapshotspaginator)
         """
 
+
 class GetDisksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetDisks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getdiskspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetDisksResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetDisks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getdiskspaginator)
         """
 
+
 class GetDomainsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetDomains)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getdomainspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetDomainsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetDomains.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getdomainspaginator)
         """
 
+
 class GetExportSnapshotRecordsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetExportSnapshotRecords)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getexportsnapshotrecordspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetExportSnapshotRecordsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetExportSnapshotRecords.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getexportsnapshotrecordspaginator)
         """
 
+
 class GetInstanceSnapshotsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetInstanceSnapshots)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getinstancesnapshotspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetInstanceSnapshotsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetInstanceSnapshots.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getinstancesnapshotspaginator)
         """
 
+
 class GetInstancesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetInstances)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getinstancespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetInstancesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getinstancespaginator)
         """
 
+
 class GetKeyPairsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetKeyPairs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getkeypairspaginator)
     """
 
     def paginate(
-        self, *, includeDefaultKeyPair: bool = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, includeDefaultKeyPair: bool = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetKeyPairsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetKeyPairs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getkeypairspaginator)
         """
 
+
 class GetLoadBalancersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetLoadBalancers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getloadbalancerspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetLoadBalancersResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetLoadBalancers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getloadbalancerspaginator)
         """
 
+
 class GetOperationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetOperations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getoperationspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetOperationsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetOperations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getoperationspaginator)
         """
 
+
 class GetRelationalDatabaseBlueprintsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetRelationalDatabaseBlueprints)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getrelationaldatabaseblueprintspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetRelationalDatabaseBlueprintsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetRelationalDatabaseBlueprints.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getrelationaldatabaseblueprintspaginator)
         """
 
+
 class GetRelationalDatabaseBundlesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetRelationalDatabaseBundles)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getrelationaldatabasebundlespaginator)
     """
 
     def paginate(
-        self, *, includeInactive: bool = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, includeInactive: bool = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetRelationalDatabaseBundlesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetRelationalDatabaseBundles.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getrelationaldatabasebundlespaginator)
         """
 
+
 class GetRelationalDatabaseEventsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetRelationalDatabaseEvents)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getrelationaldatabaseeventspaginator)
     """
 
     def paginate(
         self,
         *,
         relationalDatabaseName: str,
         durationInMinutes: int = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetRelationalDatabaseEventsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetRelationalDatabaseEvents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getrelationaldatabaseeventspaginator)
         """
 
+
 class GetRelationalDatabaseParametersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetRelationalDatabaseParameters)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getrelationaldatabaseparameterspaginator)
     """
 
     def paginate(
-        self, *, relationalDatabaseName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, relationalDatabaseName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetRelationalDatabaseParametersResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetRelationalDatabaseParameters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getrelationaldatabaseparameterspaginator)
         """
 
+
 class GetRelationalDatabaseSnapshotsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetRelationalDatabaseSnapshots)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getrelationaldatabasesnapshotspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetRelationalDatabaseSnapshotsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetRelationalDatabaseSnapshots.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getrelationaldatabasesnapshotspaginator)
         """
 
+
 class GetRelationalDatabasesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetRelationalDatabases)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getrelationaldatabasespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetRelationalDatabasesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetRelationalDatabases.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getrelationaldatabasespaginator)
         """
 
+
 class GetStaticIpsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetStaticIps)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getstaticipspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetStaticIpsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail.Paginator.GetStaticIps.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/paginators/#getstaticipspaginator)
         """
```

### Comparing `types-aiobotocore-lightsail-2.5.0.post1/types_aiobotocore_lightsail/type_defs.py` & `types-aiobotocore-lightsail-2.5.1/types_aiobotocore_lightsail/type_defs.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -15,15 +15,17 @@
 from datetime import datetime
 from typing import Dict, List, Mapping, Sequence, Union
 
 from .literals import (
     AccessDirectionType,
     AccessTypeType,
     AccountLevelBpaSyncStatusType,
+    AddOnTypeType,
     AlarmStateType,
+    AutoMountStatusType,
     AutoSnapshotStatusType,
     BehaviorEnumType,
     BlueprintTypeType,
     BPAStatusMessageType,
     BucketMetricNameType,
     CertificateDomainValidationStatusType,
     CertificateStatusType,
@@ -71,46 +73,47 @@
     NetworkProtocolType,
     OperationStatusType,
     OperationTypeType,
     OriginProtocolPolicyEnumType,
     PortAccessTypeType,
     PortInfoSourceTypeType,
     PortStateType,
+    PricingUnitType,
     R53HostedZoneDeletionStateCodeType,
     RecordStateType,
     RegionNameType,
     RelationalDatabaseMetricNameType,
     RelationalDatabasePasswordVersionType,
     RenewalStatusType,
     ResourceBucketAccessType,
     ResourceTypeType,
+    StatusType,
     StatusTypeType,
     TreatMissingDataType,
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
     "AccessKeyLastUsedTypeDef",
     "AccessRulesTypeDef",
     "AccountLevelBpaSyncTypeDef",
     "AutoSnapshotAddOnRequestTypeDef",
+    "StopInstanceOnIdleRequestTypeDef",
     "AddOnTypeDef",
     "MonitoredResourceInfoTypeDef",
     "ResourceLocationTypeDef",
     "AllocateStaticIpRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "AttachCertificateToDistributionRequestRequestTypeDef",
     "AttachDiskRequestRequestTypeDef",
     "AttachInstancesToLoadBalancerRequestRequestTypeDef",
     "AttachLoadBalancerTlsCertificateRequestRequestTypeDef",
     "AttachStaticIpRequestRequestTypeDef",
     "AttachedDiskTypeDef",
     "AvailabilityZoneTypeDef",
@@ -140,14 +143,16 @@
     "ContainerServiceStateDetailTypeDef",
     "CopySnapshotRequestRequestTypeDef",
     "CreateBucketAccessKeyRequestRequestTypeDef",
     "InstanceEntryTypeDef",
     "CreateContactMethodRequestRequestTypeDef",
     "InputOriginTypeDef",
     "DomainEntryTypeDef",
+    "CreateGUISessionAccessDetailsRequestRequestTypeDef",
+    "SessionTypeDef",
     "DiskMapTypeDef",
     "DeleteAlarmRequestRequestTypeDef",
     "DeleteAutoSnapshotRequestRequestTypeDef",
     "DeleteBucketAccessKeyRequestRequestTypeDef",
     "DeleteBucketRequestRequestTypeDef",
     "DeleteCertificateRequestRequestTypeDef",
     "DeleteContactMethodRequestRequestTypeDef",
@@ -171,113 +176,145 @@
     "DetachStaticIpRequestRequestTypeDef",
     "DisableAddOnRequestRequestTypeDef",
     "DiskInfoTypeDef",
     "DiskSnapshotInfoTypeDef",
     "DistributionBundleTypeDef",
     "DnsRecordCreationStateTypeDef",
     "ResourceRecordTypeDef",
+    "DownloadDefaultKeyPairResultTypeDef",
+    "TimePeriodTypeDef",
     "ExportSnapshotRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetActiveNamesRequestGetActiveNamesPaginateTypeDef",
     "GetActiveNamesRequestRequestTypeDef",
+    "GetActiveNamesResultTypeDef",
     "GetAlarmsRequestRequestTypeDef",
     "GetAutoSnapshotsRequestRequestTypeDef",
+    "GetBlueprintsRequestGetBlueprintsPaginateTypeDef",
     "GetBlueprintsRequestRequestTypeDef",
     "GetBucketAccessKeysRequestRequestTypeDef",
     "GetBucketBundlesRequestRequestTypeDef",
     "GetBucketMetricDataRequestRequestTypeDef",
     "MetricDatapointTypeDef",
     "GetBucketsRequestRequestTypeDef",
+    "GetBundlesRequestGetBundlesPaginateTypeDef",
     "GetBundlesRequestRequestTypeDef",
     "GetCertificatesRequestRequestTypeDef",
+    "GetCloudFormationStackRecordsRequestGetCloudFormationStackRecordsPaginateTypeDef",
     "GetCloudFormationStackRecordsRequestRequestTypeDef",
     "GetContactMethodsRequestRequestTypeDef",
+    "GetContainerAPIMetadataResultTypeDef",
     "GetContainerImagesRequestRequestTypeDef",
     "GetContainerLogRequestRequestTypeDef",
     "GetContainerServiceDeploymentsRequestRequestTypeDef",
     "GetContainerServiceMetricDataRequestRequestTypeDef",
     "GetContainerServicesRequestRequestTypeDef",
+    "GetCostEstimateRequestRequestTypeDef",
     "GetDiskRequestRequestTypeDef",
     "GetDiskSnapshotRequestRequestTypeDef",
+    "GetDiskSnapshotsRequestGetDiskSnapshotsPaginateTypeDef",
     "GetDiskSnapshotsRequestRequestTypeDef",
+    "GetDisksRequestGetDisksPaginateTypeDef",
     "GetDisksRequestRequestTypeDef",
     "GetDistributionLatestCacheResetRequestRequestTypeDef",
+    "GetDistributionLatestCacheResetResultTypeDef",
     "GetDistributionMetricDataRequestRequestTypeDef",
     "GetDistributionsRequestRequestTypeDef",
     "GetDomainRequestRequestTypeDef",
+    "GetDomainsRequestGetDomainsPaginateTypeDef",
     "GetDomainsRequestRequestTypeDef",
+    "GetExportSnapshotRecordsRequestGetExportSnapshotRecordsPaginateTypeDef",
     "GetExportSnapshotRecordsRequestRequestTypeDef",
     "GetInstanceAccessDetailsRequestRequestTypeDef",
     "GetInstanceMetricDataRequestRequestTypeDef",
     "GetInstancePortStatesRequestRequestTypeDef",
     "InstancePortStateTypeDef",
     "GetInstanceRequestRequestTypeDef",
     "GetInstanceSnapshotRequestRequestTypeDef",
+    "GetInstanceSnapshotsRequestGetInstanceSnapshotsPaginateTypeDef",
     "GetInstanceSnapshotsRequestRequestTypeDef",
     "GetInstanceStateRequestRequestTypeDef",
     "InstanceStateTypeDef",
+    "GetInstancesRequestGetInstancesPaginateTypeDef",
     "GetInstancesRequestRequestTypeDef",
     "GetKeyPairRequestRequestTypeDef",
+    "GetKeyPairsRequestGetKeyPairsPaginateTypeDef",
     "GetKeyPairsRequestRequestTypeDef",
     "GetLoadBalancerMetricDataRequestRequestTypeDef",
     "GetLoadBalancerRequestRequestTypeDef",
     "GetLoadBalancerTlsCertificatesRequestRequestTypeDef",
     "GetLoadBalancerTlsPoliciesRequestRequestTypeDef",
     "LoadBalancerTlsPolicyTypeDef",
+    "GetLoadBalancersRequestGetLoadBalancersPaginateTypeDef",
     "GetLoadBalancersRequestRequestTypeDef",
     "GetOperationRequestRequestTypeDef",
     "GetOperationsForResourceRequestRequestTypeDef",
+    "GetOperationsRequestGetOperationsPaginateTypeDef",
     "GetOperationsRequestRequestTypeDef",
     "GetRegionsRequestRequestTypeDef",
+    "GetRelationalDatabaseBlueprintsRequestGetRelationalDatabaseBlueprintsPaginateTypeDef",
     "GetRelationalDatabaseBlueprintsRequestRequestTypeDef",
     "RelationalDatabaseBlueprintTypeDef",
+    "GetRelationalDatabaseBundlesRequestGetRelationalDatabaseBundlesPaginateTypeDef",
     "GetRelationalDatabaseBundlesRequestRequestTypeDef",
     "RelationalDatabaseBundleTypeDef",
+    "GetRelationalDatabaseEventsRequestGetRelationalDatabaseEventsPaginateTypeDef",
     "GetRelationalDatabaseEventsRequestRequestTypeDef",
     "RelationalDatabaseEventTypeDef",
     "GetRelationalDatabaseLogEventsRequestRequestTypeDef",
     "LogEventTypeDef",
     "GetRelationalDatabaseLogStreamsRequestRequestTypeDef",
+    "GetRelationalDatabaseLogStreamsResultTypeDef",
     "GetRelationalDatabaseMasterUserPasswordRequestRequestTypeDef",
+    "GetRelationalDatabaseMasterUserPasswordResultTypeDef",
     "GetRelationalDatabaseMetricDataRequestRequestTypeDef",
+    "GetRelationalDatabaseParametersRequestGetRelationalDatabaseParametersPaginateTypeDef",
     "GetRelationalDatabaseParametersRequestRequestTypeDef",
     "RelationalDatabaseParameterTypeDef",
     "GetRelationalDatabaseRequestRequestTypeDef",
     "GetRelationalDatabaseSnapshotRequestRequestTypeDef",
+    "GetRelationalDatabaseSnapshotsRequestGetRelationalDatabaseSnapshotsPaginateTypeDef",
     "GetRelationalDatabaseSnapshotsRequestRequestTypeDef",
+    "GetRelationalDatabasesRequestGetRelationalDatabasesPaginateTypeDef",
     "GetRelationalDatabasesRequestRequestTypeDef",
     "GetStaticIpRequestRequestTypeDef",
+    "GetStaticIpsRequestGetStaticIpsPaginateTypeDef",
     "GetStaticIpsRequestRequestTypeDef",
     "HostKeyAttributesTypeDef",
     "ImportKeyPairRequestRequestTypeDef",
     "PasswordDataTypeDef",
     "InstanceHealthSummaryTypeDef",
     "InstanceMetadataOptionsTypeDef",
     "InstancePortInfoTypeDef",
     "MonthlyTransferTypeDef",
+    "IsVpcPeeredResultTypeDef",
     "OriginTypeDef",
     "LoadBalancerTlsCertificateDnsRecordCreationStateTypeDef",
     "LoadBalancerTlsCertificateDomainValidationOptionTypeDef",
     "LoadBalancerTlsCertificateSummaryTypeDef",
     "NameServersUpdateStateTypeDef",
+    "PaginatorConfigTypeDef",
     "PendingMaintenanceActionTypeDef",
     "PendingModifiedRelationalDatabaseValuesTypeDef",
     "PutAlarmRequestRequestTypeDef",
     "R53HostedZoneDeletionStateTypeDef",
     "RebootInstanceRequestRequestTypeDef",
     "RebootRelationalDatabaseRequestRequestTypeDef",
     "RegisterContainerImageRequestRequestTypeDef",
     "RelationalDatabaseEndpointTypeDef",
     "RelationalDatabaseHardwareTypeDef",
     "ReleaseStaticIpRequestRequestTypeDef",
     "ResetDistributionCacheRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "SendContactMethodVerificationRequestRequestTypeDef",
     "SetIpAddressTypeRequestRequestTypeDef",
     "SetResourceAccessForBucketRequestRequestTypeDef",
+    "StartGUISessionRequestRequestTypeDef",
     "StartInstanceRequestRequestTypeDef",
     "StartRelationalDatabaseRequestRequestTypeDef",
+    "StopGUISessionRequestRequestTypeDef",
     "StopInstanceRequestRequestTypeDef",
     "StopRelationalDatabaseRequestRequestTypeDef",
     "TestAlarmRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateBucketBundleRequestRequestTypeDef",
     "UpdateDistributionBundleRequestRequestTypeDef",
     "UpdateInstanceMetadataOptionsRequestRequestTypeDef",
@@ -285,21 +322,14 @@
     "UpdateRelationalDatabaseRequestRequestTypeDef",
     "AccessKeyTypeDef",
     "AddOnRequestTypeDef",
     "AlarmTypeDef",
     "ContactMethodTypeDef",
     "OperationTypeDef",
     "StaticIpTypeDef",
-    "DownloadDefaultKeyPairResultTypeDef",
-    "GetActiveNamesResultTypeDef",
-    "GetContainerAPIMetadataResultTypeDef",
-    "GetDistributionLatestCacheResetResultTypeDef",
-    "GetRelationalDatabaseLogStreamsResultTypeDef",
-    "GetRelationalDatabaseMasterUserPasswordResultTypeDef",
-    "IsVpcPeeredResultTypeDef",
     "AutoSnapshotDetailsTypeDef",
     "RegionTypeDef",
     "GetBlueprintsResultTypeDef",
     "UpdateBucketRequestRequestTypeDef",
     "GetBucketBundlesResultTypeDef",
     "BucketTypeDef",
     "CreateBucketRequestRequestTypeDef",
@@ -333,37 +363,19 @@
     "GetContainerLogResultTypeDef",
     "GetContainerServicePowersResultTypeDef",
     "CreateContainerServiceRegistryLoginResultTypeDef",
     "CreateCloudFormationStackRequestRequestTypeDef",
     "CreateDomainEntryRequestRequestTypeDef",
     "DeleteDomainEntryRequestRequestTypeDef",
     "UpdateDomainEntryRequestRequestTypeDef",
+    "CreateGUISessionAccessDetailsResultTypeDef",
     "InstanceSnapshotInfoTypeDef",
     "GetDistributionBundlesResultTypeDef",
     "DomainValidationRecordTypeDef",
-    "GetActiveNamesRequestGetActiveNamesPaginateTypeDef",
-    "GetBlueprintsRequestGetBlueprintsPaginateTypeDef",
-    "GetBundlesRequestGetBundlesPaginateTypeDef",
-    "GetCloudFormationStackRecordsRequestGetCloudFormationStackRecordsPaginateTypeDef",
-    "GetDiskSnapshotsRequestGetDiskSnapshotsPaginateTypeDef",
-    "GetDisksRequestGetDisksPaginateTypeDef",
-    "GetDomainsRequestGetDomainsPaginateTypeDef",
-    "GetExportSnapshotRecordsRequestGetExportSnapshotRecordsPaginateTypeDef",
-    "GetInstanceSnapshotsRequestGetInstanceSnapshotsPaginateTypeDef",
-    "GetInstancesRequestGetInstancesPaginateTypeDef",
-    "GetKeyPairsRequestGetKeyPairsPaginateTypeDef",
-    "GetLoadBalancersRequestGetLoadBalancersPaginateTypeDef",
-    "GetOperationsRequestGetOperationsPaginateTypeDef",
-    "GetRelationalDatabaseBlueprintsRequestGetRelationalDatabaseBlueprintsPaginateTypeDef",
-    "GetRelationalDatabaseBundlesRequestGetRelationalDatabaseBundlesPaginateTypeDef",
-    "GetRelationalDatabaseEventsRequestGetRelationalDatabaseEventsPaginateTypeDef",
-    "GetRelationalDatabaseParametersRequestGetRelationalDatabaseParametersPaginateTypeDef",
-    "GetRelationalDatabaseSnapshotsRequestGetRelationalDatabaseSnapshotsPaginateTypeDef",
-    "GetRelationalDatabasesRequestGetRelationalDatabasesPaginateTypeDef",
-    "GetStaticIpsRequestGetStaticIpsPaginateTypeDef",
+    "EstimateByTimeTypeDef",
     "GetBucketMetricDataResultTypeDef",
     "GetContainerServiceMetricDataResultTypeDef",
     "GetDistributionMetricDataResultTypeDef",
     "GetInstanceMetricDataResultTypeDef",
     "GetLoadBalancerMetricDataResultTypeDef",
     "GetRelationalDatabaseMetricDataResultTypeDef",
     "GetInstancePortStatesResultTypeDef",
@@ -451,16 +463,18 @@
     "RebootInstanceResultTypeDef",
     "RebootRelationalDatabaseResultTypeDef",
     "ReleaseStaticIpResultTypeDef",
     "ResetDistributionCacheResultTypeDef",
     "SendContactMethodVerificationResultTypeDef",
     "SetIpAddressTypeResultTypeDef",
     "SetResourceAccessForBucketResultTypeDef",
+    "StartGUISessionResultTypeDef",
     "StartInstanceResultTypeDef",
     "StartRelationalDatabaseResultTypeDef",
+    "StopGUISessionResultTypeDef",
     "StopInstanceResultTypeDef",
     "StopRelationalDatabaseResultTypeDef",
     "TagResourceResultTypeDef",
     "TestAlarmResultTypeDef",
     "UnpeerVpcResultTypeDef",
     "UntagResourceResultTypeDef",
     "UpdateBucketBundleResultTypeDef",
@@ -495,14 +509,15 @@
     "GetCloudFormationStackRecordsResultTypeDef",
     "UpdateContainerServiceRequestRequestTypeDef",
     "ContainerServiceDeploymentTypeDef",
     "ContainerServiceDeploymentRequestTypeDef",
     "CreateContainerServiceDeploymentRequestRequestTypeDef",
     "ExportSnapshotRecordSourceInfoTypeDef",
     "RenewalSummaryTypeDef",
+    "CostEstimateTypeDef",
     "GetInstanceAccessDetailsResultTypeDef",
     "LoadBalancerTlsCertificateTypeDef",
     "GetLoadBalancerResultTypeDef",
     "GetLoadBalancersResultTypeDef",
     "DomainTypeDef",
     "GetRelationalDatabaseResultTypeDef",
     "GetRelationalDatabasesResultTypeDef",
@@ -512,25 +527,27 @@
     "CreateDistributionResultTypeDef",
     "GetDistributionsResultTypeDef",
     "ContainerServiceTypeDef",
     "GetContainerServiceDeploymentsResultTypeDef",
     "CreateContainerServiceRequestRequestTypeDef",
     "ExportSnapshotRecordTypeDef",
     "CertificateTypeDef",
+    "ResourceBudgetEstimateTypeDef",
     "GetLoadBalancerTlsCertificatesResultTypeDef",
     "GetDomainResultTypeDef",
     "GetDomainsResultTypeDef",
     "GetInstanceResultTypeDef",
     "GetInstancesResultTypeDef",
     "ContainerServicesListResultTypeDef",
     "CreateContainerServiceDeploymentResultTypeDef",
     "CreateContainerServiceResultTypeDef",
     "UpdateContainerServiceResultTypeDef",
     "GetExportSnapshotRecordsResultTypeDef",
     "CertificateSummaryTypeDef",
+    "GetCostEstimateResultTypeDef",
     "CreateCertificateResultTypeDef",
     "GetCertificatesResultTypeDef",
 )
 
 AccessKeyLastUsedTypeDef = TypedDict(
     "AccessKeyLastUsedTypeDef",
     {
@@ -565,21 +582,32 @@
     "AutoSnapshotAddOnRequestTypeDef",
     {
         "snapshotTimeOfDay": str,
     },
     total=False,
 )
 
+StopInstanceOnIdleRequestTypeDef = TypedDict(
+    "StopInstanceOnIdleRequestTypeDef",
+    {
+        "threshold": str,
+        "duration": str,
+    },
+    total=False,
+)
+
 AddOnTypeDef = TypedDict(
     "AddOnTypeDef",
     {
         "name": str,
         "status": str,
         "snapshotTimeOfDay": str,
         "nextSnapshotTimeOfDay": str,
+        "threshold": str,
+        "duration": str,
     },
     total=False,
 )
 
 MonitoredResourceInfoTypeDef = TypedDict(
     "MonitoredResourceInfoTypeDef",
     {
@@ -602,41 +630,42 @@
 AllocateStaticIpRequestRequestTypeDef = TypedDict(
     "AllocateStaticIpRequestRequestTypeDef",
     {
         "staticIpName": str,
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
 AttachCertificateToDistributionRequestRequestTypeDef = TypedDict(
     "AttachCertificateToDistributionRequestRequestTypeDef",
     {
         "distributionName": str,
         "certificateName": str,
     },
 )
 
-AttachDiskRequestRequestTypeDef = TypedDict(
-    "AttachDiskRequestRequestTypeDef",
+_RequiredAttachDiskRequestRequestTypeDef = TypedDict(
+    "_RequiredAttachDiskRequestRequestTypeDef",
     {
         "diskName": str,
         "instanceName": str,
         "diskPath": str,
     },
 )
+_OptionalAttachDiskRequestRequestTypeDef = TypedDict(
+    "_OptionalAttachDiskRequestRequestTypeDef",
+    {
+        "autoMounting": bool,
+    },
+    total=False,
+)
+
+class AttachDiskRequestRequestTypeDef(
+    _RequiredAttachDiskRequestRequestTypeDef, _OptionalAttachDiskRequestRequestTypeDef
+):
+    pass
 
 AttachInstancesToLoadBalancerRequestRequestTypeDef = TypedDict(
     "AttachInstancesToLoadBalancerRequestRequestTypeDef",
     {
         "loadBalancerName": str,
         "instanceNames": Sequence[str],
     },
@@ -687,14 +716,15 @@
         "isActive": bool,
         "minPower": int,
         "version": str,
         "versionCode": str,
         "productUrl": str,
         "licenseUrl": str,
         "platform": InstancePlatformType,
+        "appCategory": Literal["LfR"],
     },
     total=False,
 )
 
 _RequiredBucketAccessLogConfigTypeDef = TypedDict(
     "_RequiredBucketAccessLogConfigTypeDef",
     {
@@ -706,21 +736,19 @@
     {
         "destination": str,
         "prefix": str,
     },
     total=False,
 )
 
-
 class BucketAccessLogConfigTypeDef(
     _RequiredBucketAccessLogConfigTypeDef, _OptionalBucketAccessLogConfigTypeDef
 ):
     pass
 
-
 BucketBundleTypeDef = TypedDict(
     "BucketBundleTypeDef",
     {
         "bundleId": str,
         "name": str,
         "price": float,
         "storagePerMonthInGb": int,
@@ -767,14 +795,15 @@
         "instanceType": str,
         "isActive": bool,
         "name": str,
         "power": int,
         "ramSizeInGb": float,
         "transferPerMonthInGb": int,
         "supportedPlatforms": List[InstancePlatformType],
+        "supportedAppCategories": List[Literal["LfR"]],
     },
     total=False,
 )
 
 CacheBehaviorPerPathTypeDef = TypedDict(
     "CacheBehaviorPerPathTypeDef",
     {
@@ -958,21 +987,19 @@
         "sourceResourceName": str,
         "restoreDate": str,
         "useLatestRestorableAutoSnapshot": bool,
     },
     total=False,
 )
 
-
 class CopySnapshotRequestRequestTypeDef(
     _RequiredCopySnapshotRequestRequestTypeDef, _OptionalCopySnapshotRequestRequestTypeDef
 ):
     pass
 
-
 CreateBucketAccessKeyRequestRequestTypeDef = TypedDict(
     "CreateBucketAccessKeyRequestRequestTypeDef",
     {
         "bucketName": str,
     },
 )
 
@@ -989,19 +1016,17 @@
     "_OptionalInstanceEntryTypeDef",
     {
         "userData": str,
     },
     total=False,
 )
 
-
 class InstanceEntryTypeDef(_RequiredInstanceEntryTypeDef, _OptionalInstanceEntryTypeDef):
     pass
 
-
 CreateContactMethodRequestRequestTypeDef = TypedDict(
     "CreateContactMethodRequestRequestTypeDef",
     {
         "protocol": ContactProtocolType,
         "contactEndpoint": str,
     },
 )
@@ -1025,14 +1050,31 @@
         "isAlias": bool,
         "type": str,
         "options": Mapping[str, str],
     },
     total=False,
 )
 
+CreateGUISessionAccessDetailsRequestRequestTypeDef = TypedDict(
+    "CreateGUISessionAccessDetailsRequestRequestTypeDef",
+    {
+        "resourceName": str,
+    },
+)
+
+SessionTypeDef = TypedDict(
+    "SessionTypeDef",
+    {
+        "name": str,
+        "url": str,
+        "isPrimary": bool,
+    },
+    total=False,
+)
+
 DiskMapTypeDef = TypedDict(
     "DiskMapTypeDef",
     {
         "originalDiskPath": str,
         "newDiskName": str,
     },
     total=False,
@@ -1071,21 +1113,19 @@
     "_OptionalDeleteBucketRequestRequestTypeDef",
     {
         "forceDelete": bool,
     },
     total=False,
 )
 
-
 class DeleteBucketRequestRequestTypeDef(
     _RequiredDeleteBucketRequestRequestTypeDef, _OptionalDeleteBucketRequestRequestTypeDef
 ):
     pass
 
-
 DeleteCertificateRequestRequestTypeDef = TypedDict(
     "DeleteCertificateRequestRequestTypeDef",
     {
         "certificateName": str,
     },
 )
 
@@ -1121,21 +1161,19 @@
     "_OptionalDeleteDiskRequestRequestTypeDef",
     {
         "forceDeleteAddOns": bool,
     },
     total=False,
 )
 
-
 class DeleteDiskRequestRequestTypeDef(
     _RequiredDeleteDiskRequestRequestTypeDef, _OptionalDeleteDiskRequestRequestTypeDef
 ):
     pass
 
-
 DeleteDiskSnapshotRequestRequestTypeDef = TypedDict(
     "DeleteDiskSnapshotRequestRequestTypeDef",
     {
         "diskSnapshotName": str,
     },
 )
 
@@ -1164,21 +1202,19 @@
     "_OptionalDeleteInstanceRequestRequestTypeDef",
     {
         "forceDeleteAddOns": bool,
     },
     total=False,
 )
 
-
 class DeleteInstanceRequestRequestTypeDef(
     _RequiredDeleteInstanceRequestRequestTypeDef, _OptionalDeleteInstanceRequestRequestTypeDef
 ):
     pass
 
-
 DeleteInstanceSnapshotRequestRequestTypeDef = TypedDict(
     "DeleteInstanceSnapshotRequestRequestTypeDef",
     {
         "instanceSnapshotName": str,
     },
 )
 
@@ -1192,21 +1228,19 @@
     "_OptionalDeleteKeyPairRequestRequestTypeDef",
     {
         "expectedFingerprint": str,
     },
     total=False,
 )
 
-
 class DeleteKeyPairRequestRequestTypeDef(
     _RequiredDeleteKeyPairRequestRequestTypeDef, _OptionalDeleteKeyPairRequestRequestTypeDef
 ):
     pass
 
-
 DeleteKnownHostKeysRequestRequestTypeDef = TypedDict(
     "DeleteKnownHostKeysRequestRequestTypeDef",
     {
         "instanceName": str,
     },
 )
 
@@ -1228,22 +1262,20 @@
     "_OptionalDeleteLoadBalancerTlsCertificateRequestRequestTypeDef",
     {
         "force": bool,
     },
     total=False,
 )
 
-
 class DeleteLoadBalancerTlsCertificateRequestRequestTypeDef(
     _RequiredDeleteLoadBalancerTlsCertificateRequestRequestTypeDef,
     _OptionalDeleteLoadBalancerTlsCertificateRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredDeleteRelationalDatabaseRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteRelationalDatabaseRequestRequestTypeDef",
     {
         "relationalDatabaseName": str,
     },
 )
 _OptionalDeleteRelationalDatabaseRequestRequestTypeDef = TypedDict(
@@ -1251,22 +1283,20 @@
     {
         "skipFinalSnapshot": bool,
         "finalRelationalDatabaseSnapshotName": str,
     },
     total=False,
 )
 
-
 class DeleteRelationalDatabaseRequestRequestTypeDef(
     _RequiredDeleteRelationalDatabaseRequestRequestTypeDef,
     _OptionalDeleteRelationalDatabaseRequestRequestTypeDef,
 ):
     pass
 
-
 DeleteRelationalDatabaseSnapshotRequestRequestTypeDef = TypedDict(
     "DeleteRelationalDatabaseSnapshotRequestRequestTypeDef",
     {
         "relationalDatabaseSnapshotName": str,
     },
 )
 
@@ -1298,15 +1328,15 @@
         "staticIpName": str,
     },
 )
 
 DisableAddOnRequestRequestTypeDef = TypedDict(
     "DisableAddOnRequestRequestTypeDef",
     {
-        "addOnType": Literal["AutoSnapshot"],
+        "addOnType": AddOnTypeType,
         "resourceName": str,
     },
 )
 
 DiskInfoTypeDef = TypedDict(
     "DiskInfoTypeDef",
     {
@@ -1353,39 +1383,65 @@
         "name": str,
         "type": str,
         "value": str,
     },
     total=False,
 )
 
+DownloadDefaultKeyPairResultTypeDef = TypedDict(
+    "DownloadDefaultKeyPairResultTypeDef",
+    {
+        "publicKeyBase64": str,
+        "privateKeyBase64": str,
+        "createdAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+TimePeriodTypeDef = TypedDict(
+    "TimePeriodTypeDef",
+    {
+        "start": datetime,
+        "end": datetime,
+    },
+    total=False,
+)
+
 ExportSnapshotRequestRequestTypeDef = TypedDict(
     "ExportSnapshotRequestRequestTypeDef",
     {
         "sourceSnapshotName": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetActiveNamesRequestGetActiveNamesPaginateTypeDef = TypedDict(
+    "GetActiveNamesRequestGetActiveNamesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 GetActiveNamesRequestRequestTypeDef = TypedDict(
     "GetActiveNamesRequestRequestTypeDef",
     {
         "pageToken": str,
     },
     total=False,
 )
 
+GetActiveNamesResultTypeDef = TypedDict(
+    "GetActiveNamesResultTypeDef",
+    {
+        "activeNames": List[str],
+        "nextPageToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetAlarmsRequestRequestTypeDef = TypedDict(
     "GetAlarmsRequestRequestTypeDef",
     {
         "alarmName": str,
         "pageToken": str,
         "monitoredResourceName": str,
     },
@@ -1395,19 +1451,30 @@
 GetAutoSnapshotsRequestRequestTypeDef = TypedDict(
     "GetAutoSnapshotsRequestRequestTypeDef",
     {
         "resourceName": str,
     },
 )
 
+GetBlueprintsRequestGetBlueprintsPaginateTypeDef = TypedDict(
+    "GetBlueprintsRequestGetBlueprintsPaginateTypeDef",
+    {
+        "includeInactive": bool,
+        "appCategory": Literal["LfR"],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetBlueprintsRequestRequestTypeDef = TypedDict(
     "GetBlueprintsRequestRequestTypeDef",
     {
         "includeInactive": bool,
         "pageToken": str,
+        "appCategory": Literal["LfR"],
     },
     total=False,
 )
 
 GetBucketAccessKeysRequestRequestTypeDef = TypedDict(
     "GetBucketAccessKeysRequestRequestTypeDef",
     {
@@ -1456,29 +1523,49 @@
         "bucketName": str,
         "pageToken": str,
         "includeConnectedResources": bool,
     },
     total=False,
 )
 
+GetBundlesRequestGetBundlesPaginateTypeDef = TypedDict(
+    "GetBundlesRequestGetBundlesPaginateTypeDef",
+    {
+        "includeInactive": bool,
+        "appCategory": Literal["LfR"],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetBundlesRequestRequestTypeDef = TypedDict(
     "GetBundlesRequestRequestTypeDef",
     {
         "includeInactive": bool,
         "pageToken": str,
+        "appCategory": Literal["LfR"],
     },
     total=False,
 )
 
 GetCertificatesRequestRequestTypeDef = TypedDict(
     "GetCertificatesRequestRequestTypeDef",
     {
         "certificateStatuses": Sequence[CertificateStatusType],
         "includeCertificateDetails": bool,
         "certificateName": str,
+        "pageToken": str,
+    },
+    total=False,
+)
+
+GetCloudFormationStackRecordsRequestGetCloudFormationStackRecordsPaginateTypeDef = TypedDict(
+    "GetCloudFormationStackRecordsRequestGetCloudFormationStackRecordsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 GetCloudFormationStackRecordsRequestRequestTypeDef = TypedDict(
     "GetCloudFormationStackRecordsRequestRequestTypeDef",
     {
@@ -1491,14 +1578,22 @@
     "GetContactMethodsRequestRequestTypeDef",
     {
         "protocols": Sequence[ContactProtocolType],
     },
     total=False,
 )
 
+GetContainerAPIMetadataResultTypeDef = TypedDict(
+    "GetContainerAPIMetadataResultTypeDef",
+    {
+        "metadata": List[Dict[str, str]],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetContainerImagesRequestRequestTypeDef = TypedDict(
     "GetContainerImagesRequestRequestTypeDef",
     {
         "serviceName": str,
     },
 )
 
@@ -1516,21 +1611,19 @@
         "endTime": Union[datetime, str],
         "filterPattern": str,
         "pageToken": str,
     },
     total=False,
 )
 
-
 class GetContainerLogRequestRequestTypeDef(
     _RequiredGetContainerLogRequestRequestTypeDef, _OptionalGetContainerLogRequestRequestTypeDef
 ):
     pass
 
-
 GetContainerServiceDeploymentsRequestRequestTypeDef = TypedDict(
     "GetContainerServiceDeploymentsRequestRequestTypeDef",
     {
         "serviceName": str,
     },
 )
 
@@ -1550,36 +1643,61 @@
     "GetContainerServicesRequestRequestTypeDef",
     {
         "serviceName": str,
     },
     total=False,
 )
 
+GetCostEstimateRequestRequestTypeDef = TypedDict(
+    "GetCostEstimateRequestRequestTypeDef",
+    {
+        "resourceName": str,
+        "startTime": Union[datetime, str],
+        "endTime": Union[datetime, str],
+    },
+)
+
 GetDiskRequestRequestTypeDef = TypedDict(
     "GetDiskRequestRequestTypeDef",
     {
         "diskName": str,
     },
 )
 
 GetDiskSnapshotRequestRequestTypeDef = TypedDict(
     "GetDiskSnapshotRequestRequestTypeDef",
     {
         "diskSnapshotName": str,
     },
 )
 
+GetDiskSnapshotsRequestGetDiskSnapshotsPaginateTypeDef = TypedDict(
+    "GetDiskSnapshotsRequestGetDiskSnapshotsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetDiskSnapshotsRequestRequestTypeDef = TypedDict(
     "GetDiskSnapshotsRequestRequestTypeDef",
     {
         "pageToken": str,
     },
     total=False,
 )
 
+GetDisksRequestGetDisksPaginateTypeDef = TypedDict(
+    "GetDisksRequestGetDisksPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetDisksRequestRequestTypeDef = TypedDict(
     "GetDisksRequestRequestTypeDef",
     {
         "pageToken": str,
     },
     total=False,
 )
@@ -1588,14 +1706,23 @@
     "GetDistributionLatestCacheResetRequestRequestTypeDef",
     {
         "distributionName": str,
     },
     total=False,
 )
 
+GetDistributionLatestCacheResetResultTypeDef = TypedDict(
+    "GetDistributionLatestCacheResetResultTypeDef",
+    {
+        "status": str,
+        "createTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetDistributionMetricDataRequestRequestTypeDef = TypedDict(
     "GetDistributionMetricDataRequestRequestTypeDef",
     {
         "distributionName": str,
         "metricName": DistributionMetricNameType,
         "startTime": Union[datetime, str],
         "endTime": Union[datetime, str],
@@ -1617,22 +1744,38 @@
 GetDomainRequestRequestTypeDef = TypedDict(
     "GetDomainRequestRequestTypeDef",
     {
         "domainName": str,
     },
 )
 
+GetDomainsRequestGetDomainsPaginateTypeDef = TypedDict(
+    "GetDomainsRequestGetDomainsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetDomainsRequestRequestTypeDef = TypedDict(
     "GetDomainsRequestRequestTypeDef",
     {
         "pageToken": str,
     },
     total=False,
 )
 
+GetExportSnapshotRecordsRequestGetExportSnapshotRecordsPaginateTypeDef = TypedDict(
+    "GetExportSnapshotRecordsRequestGetExportSnapshotRecordsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetExportSnapshotRecordsRequestRequestTypeDef = TypedDict(
     "GetExportSnapshotRecordsRequestRequestTypeDef",
     {
         "pageToken": str,
     },
     total=False,
 )
@@ -1647,22 +1790,20 @@
     "_OptionalGetInstanceAccessDetailsRequestRequestTypeDef",
     {
         "protocol": InstanceAccessProtocolType,
     },
     total=False,
 )
 
-
 class GetInstanceAccessDetailsRequestRequestTypeDef(
     _RequiredGetInstanceAccessDetailsRequestRequestTypeDef,
     _OptionalGetInstanceAccessDetailsRequestRequestTypeDef,
 ):
     pass
 
-
 GetInstanceMetricDataRequestRequestTypeDef = TypedDict(
     "GetInstanceMetricDataRequestRequestTypeDef",
     {
         "instanceName": str,
         "metricName": InstanceMetricNameType,
         "period": int,
         "startTime": Union[datetime, str],
@@ -1703,14 +1844,22 @@
 GetInstanceSnapshotRequestRequestTypeDef = TypedDict(
     "GetInstanceSnapshotRequestRequestTypeDef",
     {
         "instanceSnapshotName": str,
     },
 )
 
+GetInstanceSnapshotsRequestGetInstanceSnapshotsPaginateTypeDef = TypedDict(
+    "GetInstanceSnapshotsRequestGetInstanceSnapshotsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetInstanceSnapshotsRequestRequestTypeDef = TypedDict(
     "GetInstanceSnapshotsRequestRequestTypeDef",
     {
         "pageToken": str,
     },
     total=False,
 )
@@ -1727,14 +1876,22 @@
     {
         "code": int,
         "name": str,
     },
     total=False,
 )
 
+GetInstancesRequestGetInstancesPaginateTypeDef = TypedDict(
+    "GetInstancesRequestGetInstancesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetInstancesRequestRequestTypeDef = TypedDict(
     "GetInstancesRequestRequestTypeDef",
     {
         "pageToken": str,
     },
     total=False,
 )
@@ -1742,14 +1899,23 @@
 GetKeyPairRequestRequestTypeDef = TypedDict(
     "GetKeyPairRequestRequestTypeDef",
     {
         "keyPairName": str,
     },
 )
 
+GetKeyPairsRequestGetKeyPairsPaginateTypeDef = TypedDict(
+    "GetKeyPairsRequestGetKeyPairsPaginateTypeDef",
+    {
+        "includeDefaultKeyPair": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetKeyPairsRequestRequestTypeDef = TypedDict(
     "GetKeyPairsRequestRequestTypeDef",
     {
         "pageToken": str,
         "includeDefaultKeyPair": bool,
     },
     total=False,
@@ -1798,14 +1964,22 @@
         "description": str,
         "protocols": List[str],
         "ciphers": List[str],
     },
     total=False,
 )
 
+GetLoadBalancersRequestGetLoadBalancersPaginateTypeDef = TypedDict(
+    "GetLoadBalancersRequestGetLoadBalancersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetLoadBalancersRequestRequestTypeDef = TypedDict(
     "GetLoadBalancersRequestRequestTypeDef",
     {
         "pageToken": str,
     },
     total=False,
 )
@@ -1827,21 +2001,27 @@
     "_OptionalGetOperationsForResourceRequestRequestTypeDef",
     {
         "pageToken": str,
     },
     total=False,
 )
 
-
 class GetOperationsForResourceRequestRequestTypeDef(
     _RequiredGetOperationsForResourceRequestRequestTypeDef,
     _OptionalGetOperationsForResourceRequestRequestTypeDef,
 ):
     pass
 
+GetOperationsRequestGetOperationsPaginateTypeDef = TypedDict(
+    "GetOperationsRequestGetOperationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
 
 GetOperationsRequestRequestTypeDef = TypedDict(
     "GetOperationsRequestRequestTypeDef",
     {
         "pageToken": str,
     },
     total=False,
@@ -1852,14 +2032,22 @@
     {
         "includeAvailabilityZones": bool,
         "includeRelationalDatabaseAvailabilityZones": bool,
     },
     total=False,
 )
 
+GetRelationalDatabaseBlueprintsRequestGetRelationalDatabaseBlueprintsPaginateTypeDef = TypedDict(
+    "GetRelationalDatabaseBlueprintsRequestGetRelationalDatabaseBlueprintsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetRelationalDatabaseBlueprintsRequestRequestTypeDef = TypedDict(
     "GetRelationalDatabaseBlueprintsRequestRequestTypeDef",
     {
         "pageToken": str,
     },
     total=False,
 )
@@ -1873,14 +2061,23 @@
         "engineDescription": str,
         "engineVersionDescription": str,
         "isEngineDefault": bool,
     },
     total=False,
 )
 
+GetRelationalDatabaseBundlesRequestGetRelationalDatabaseBundlesPaginateTypeDef = TypedDict(
+    "GetRelationalDatabaseBundlesRequestGetRelationalDatabaseBundlesPaginateTypeDef",
+    {
+        "includeInactive": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetRelationalDatabaseBundlesRequestRequestTypeDef = TypedDict(
     "GetRelationalDatabaseBundlesRequestRequestTypeDef",
     {
         "pageToken": str,
         "includeInactive": bool,
     },
     total=False,
@@ -1898,14 +2095,35 @@
         "cpuCount": int,
         "isEncrypted": bool,
         "isActive": bool,
     },
     total=False,
 )
 
+_RequiredGetRelationalDatabaseEventsRequestGetRelationalDatabaseEventsPaginateTypeDef = TypedDict(
+    "_RequiredGetRelationalDatabaseEventsRequestGetRelationalDatabaseEventsPaginateTypeDef",
+    {
+        "relationalDatabaseName": str,
+    },
+)
+_OptionalGetRelationalDatabaseEventsRequestGetRelationalDatabaseEventsPaginateTypeDef = TypedDict(
+    "_OptionalGetRelationalDatabaseEventsRequestGetRelationalDatabaseEventsPaginateTypeDef",
+    {
+        "durationInMinutes": int,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetRelationalDatabaseEventsRequestGetRelationalDatabaseEventsPaginateTypeDef(
+    _RequiredGetRelationalDatabaseEventsRequestGetRelationalDatabaseEventsPaginateTypeDef,
+    _OptionalGetRelationalDatabaseEventsRequestGetRelationalDatabaseEventsPaginateTypeDef,
+):
+    pass
+
 _RequiredGetRelationalDatabaseEventsRequestRequestTypeDef = TypedDict(
     "_RequiredGetRelationalDatabaseEventsRequestRequestTypeDef",
     {
         "relationalDatabaseName": str,
     },
 )
 _OptionalGetRelationalDatabaseEventsRequestRequestTypeDef = TypedDict(
@@ -1913,22 +2131,20 @@
     {
         "durationInMinutes": int,
         "pageToken": str,
     },
     total=False,
 )
 
-
 class GetRelationalDatabaseEventsRequestRequestTypeDef(
     _RequiredGetRelationalDatabaseEventsRequestRequestTypeDef,
     _OptionalGetRelationalDatabaseEventsRequestRequestTypeDef,
 ):
     pass
 
-
 RelationalDatabaseEventTypeDef = TypedDict(
     "RelationalDatabaseEventTypeDef",
     {
         "resource": str,
         "createdAt": datetime,
         "message": str,
         "eventCategories": List[str],
@@ -1950,22 +2166,20 @@
         "endTime": Union[datetime, str],
         "startFromHead": bool,
         "pageToken": str,
     },
     total=False,
 )
 
-
 class GetRelationalDatabaseLogEventsRequestRequestTypeDef(
     _RequiredGetRelationalDatabaseLogEventsRequestRequestTypeDef,
     _OptionalGetRelationalDatabaseLogEventsRequestRequestTypeDef,
 ):
     pass
 
-
 LogEventTypeDef = TypedDict(
     "LogEventTypeDef",
     {
         "createdAt": datetime,
         "message": str,
     },
     total=False,
@@ -1974,71 +2188,104 @@
 GetRelationalDatabaseLogStreamsRequestRequestTypeDef = TypedDict(
     "GetRelationalDatabaseLogStreamsRequestRequestTypeDef",
     {
         "relationalDatabaseName": str,
     },
 )
 
+GetRelationalDatabaseLogStreamsResultTypeDef = TypedDict(
+    "GetRelationalDatabaseLogStreamsResultTypeDef",
+    {
+        "logStreams": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetRelationalDatabaseMasterUserPasswordRequestRequestTypeDef = TypedDict(
     "_RequiredGetRelationalDatabaseMasterUserPasswordRequestRequestTypeDef",
     {
         "relationalDatabaseName": str,
     },
 )
 _OptionalGetRelationalDatabaseMasterUserPasswordRequestRequestTypeDef = TypedDict(
     "_OptionalGetRelationalDatabaseMasterUserPasswordRequestRequestTypeDef",
     {
         "passwordVersion": RelationalDatabasePasswordVersionType,
     },
     total=False,
 )
 
-
 class GetRelationalDatabaseMasterUserPasswordRequestRequestTypeDef(
     _RequiredGetRelationalDatabaseMasterUserPasswordRequestRequestTypeDef,
     _OptionalGetRelationalDatabaseMasterUserPasswordRequestRequestTypeDef,
 ):
     pass
 
+GetRelationalDatabaseMasterUserPasswordResultTypeDef = TypedDict(
+    "GetRelationalDatabaseMasterUserPasswordResultTypeDef",
+    {
+        "masterUserPassword": str,
+        "createdAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 GetRelationalDatabaseMetricDataRequestRequestTypeDef = TypedDict(
     "GetRelationalDatabaseMetricDataRequestRequestTypeDef",
     {
         "relationalDatabaseName": str,
         "metricName": RelationalDatabaseMetricNameType,
         "period": int,
         "startTime": Union[datetime, str],
         "endTime": Union[datetime, str],
         "unit": MetricUnitType,
         "statistics": Sequence[MetricStatisticType],
     },
 )
 
+_RequiredGetRelationalDatabaseParametersRequestGetRelationalDatabaseParametersPaginateTypeDef = TypedDict(
+    "_RequiredGetRelationalDatabaseParametersRequestGetRelationalDatabaseParametersPaginateTypeDef",
+    {
+        "relationalDatabaseName": str,
+    },
+)
+_OptionalGetRelationalDatabaseParametersRequestGetRelationalDatabaseParametersPaginateTypeDef = TypedDict(
+    "_OptionalGetRelationalDatabaseParametersRequestGetRelationalDatabaseParametersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class GetRelationalDatabaseParametersRequestGetRelationalDatabaseParametersPaginateTypeDef(
+    _RequiredGetRelationalDatabaseParametersRequestGetRelationalDatabaseParametersPaginateTypeDef,
+    _OptionalGetRelationalDatabaseParametersRequestGetRelationalDatabaseParametersPaginateTypeDef,
+):
+    pass
+
 _RequiredGetRelationalDatabaseParametersRequestRequestTypeDef = TypedDict(
     "_RequiredGetRelationalDatabaseParametersRequestRequestTypeDef",
     {
         "relationalDatabaseName": str,
     },
 )
 _OptionalGetRelationalDatabaseParametersRequestRequestTypeDef = TypedDict(
     "_OptionalGetRelationalDatabaseParametersRequestRequestTypeDef",
     {
         "pageToken": str,
     },
     total=False,
 )
 
-
 class GetRelationalDatabaseParametersRequestRequestTypeDef(
     _RequiredGetRelationalDatabaseParametersRequestRequestTypeDef,
     _OptionalGetRelationalDatabaseParametersRequestRequestTypeDef,
 ):
     pass
 
-
 RelationalDatabaseParameterTypeDef = TypedDict(
     "RelationalDatabaseParameterTypeDef",
     {
         "allowedValues": str,
         "applyMethod": str,
         "applyType": str,
         "dataType": str,
@@ -2060,22 +2307,38 @@
 GetRelationalDatabaseSnapshotRequestRequestTypeDef = TypedDict(
     "GetRelationalDatabaseSnapshotRequestRequestTypeDef",
     {
         "relationalDatabaseSnapshotName": str,
     },
 )
 
+GetRelationalDatabaseSnapshotsRequestGetRelationalDatabaseSnapshotsPaginateTypeDef = TypedDict(
+    "GetRelationalDatabaseSnapshotsRequestGetRelationalDatabaseSnapshotsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetRelationalDatabaseSnapshotsRequestRequestTypeDef = TypedDict(
     "GetRelationalDatabaseSnapshotsRequestRequestTypeDef",
     {
         "pageToken": str,
     },
     total=False,
 )
 
+GetRelationalDatabasesRequestGetRelationalDatabasesPaginateTypeDef = TypedDict(
+    "GetRelationalDatabasesRequestGetRelationalDatabasesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetRelationalDatabasesRequestRequestTypeDef = TypedDict(
     "GetRelationalDatabasesRequestRequestTypeDef",
     {
         "pageToken": str,
     },
     total=False,
 )
@@ -2083,14 +2346,22 @@
 GetStaticIpRequestRequestTypeDef = TypedDict(
     "GetStaticIpRequestRequestTypeDef",
     {
         "staticIpName": str,
     },
 )
 
+GetStaticIpsRequestGetStaticIpsPaginateTypeDef = TypedDict(
+    "GetStaticIpsRequestGetStaticIpsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetStaticIpsRequestRequestTypeDef = TypedDict(
     "GetStaticIpsRequestRequestTypeDef",
     {
         "pageToken": str,
     },
     total=False,
 )
@@ -2169,14 +2440,22 @@
     "MonthlyTransferTypeDef",
     {
         "gbPerMonthAllocated": int,
     },
     total=False,
 )
 
+IsVpcPeeredResultTypeDef = TypedDict(
+    "IsVpcPeeredResultTypeDef",
+    {
+        "isPeered": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 OriginTypeDef = TypedDict(
     "OriginTypeDef",
     {
         "name": str,
         "resourceType": ResourceTypeType,
         "regionName": RegionNameType,
         "protocolPolicy": OriginProtocolPolicyEnumType,
@@ -2216,14 +2495,24 @@
     {
         "code": NameServersUpdateStateCodeType,
         "message": str,
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
 PendingMaintenanceActionTypeDef = TypedDict(
     "PendingMaintenanceActionTypeDef",
     {
         "action": str,
         "description": str,
         "currentApplyDate": datetime,
     },
@@ -2259,21 +2548,19 @@
         "contactProtocols": Sequence[ContactProtocolType],
         "notificationTriggers": Sequence[AlarmStateType],
         "notificationEnabled": bool,
     },
     total=False,
 )
 
-
 class PutAlarmRequestRequestTypeDef(
     _RequiredPutAlarmRequestRequestTypeDef, _OptionalPutAlarmRequestRequestTypeDef
 ):
     pass
 
-
 R53HostedZoneDeletionStateTypeDef = TypedDict(
     "R53HostedZoneDeletionStateTypeDef",
     {
         "code": R53HostedZoneDeletionStateCodeType,
         "message": str,
     },
     total=False,
@@ -2332,14 +2619,25 @@
     "ResetDistributionCacheRequestRequestTypeDef",
     {
         "distributionName": str,
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
 SendContactMethodVerificationRequestRequestTypeDef = TypedDict(
     "SendContactMethodVerificationRequestRequestTypeDef",
     {
         "protocol": Literal["Email"],
     },
 )
 
@@ -2357,71 +2655,81 @@
     {
         "resourceName": str,
         "bucketName": str,
         "access": ResourceBucketAccessType,
     },
 )
 
+StartGUISessionRequestRequestTypeDef = TypedDict(
+    "StartGUISessionRequestRequestTypeDef",
+    {
+        "resourceName": str,
+    },
+)
+
 StartInstanceRequestRequestTypeDef = TypedDict(
     "StartInstanceRequestRequestTypeDef",
     {
         "instanceName": str,
     },
 )
 
 StartRelationalDatabaseRequestRequestTypeDef = TypedDict(
     "StartRelationalDatabaseRequestRequestTypeDef",
     {
         "relationalDatabaseName": str,
     },
 )
 
+StopGUISessionRequestRequestTypeDef = TypedDict(
+    "StopGUISessionRequestRequestTypeDef",
+    {
+        "resourceName": str,
+    },
+)
+
 _RequiredStopInstanceRequestRequestTypeDef = TypedDict(
     "_RequiredStopInstanceRequestRequestTypeDef",
     {
         "instanceName": str,
     },
 )
 _OptionalStopInstanceRequestRequestTypeDef = TypedDict(
     "_OptionalStopInstanceRequestRequestTypeDef",
     {
         "force": bool,
     },
     total=False,
 )
 
-
 class StopInstanceRequestRequestTypeDef(
     _RequiredStopInstanceRequestRequestTypeDef, _OptionalStopInstanceRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredStopRelationalDatabaseRequestRequestTypeDef = TypedDict(
     "_RequiredStopRelationalDatabaseRequestRequestTypeDef",
     {
         "relationalDatabaseName": str,
     },
 )
 _OptionalStopRelationalDatabaseRequestRequestTypeDef = TypedDict(
     "_OptionalStopRelationalDatabaseRequestRequestTypeDef",
     {
         "relationalDatabaseSnapshotName": str,
     },
     total=False,
 )
 
-
 class StopRelationalDatabaseRequestRequestTypeDef(
     _RequiredStopRelationalDatabaseRequestRequestTypeDef,
     _OptionalStopRelationalDatabaseRequestRequestTypeDef,
 ):
     pass
 
-
 TestAlarmRequestRequestTypeDef = TypedDict(
     "TestAlarmRequestRequestTypeDef",
     {
         "alarmName": str,
         "state": AlarmStateType,
     },
 )
@@ -2437,21 +2745,19 @@
     "_OptionalUntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
     total=False,
 )
 
-
 class UntagResourceRequestRequestTypeDef(
     _RequiredUntagResourceRequestRequestTypeDef, _OptionalUntagResourceRequestRequestTypeDef
 ):
     pass
 
-
 UpdateBucketBundleRequestRequestTypeDef = TypedDict(
     "UpdateBucketBundleRequestRequestTypeDef",
     {
         "bucketName": str,
         "bundleId": str,
     },
 )
@@ -2478,22 +2784,20 @@
         "httpEndpoint": HttpEndpointType,
         "httpPutResponseHopLimit": int,
         "httpProtocolIpv6": HttpProtocolIpv6Type,
     },
     total=False,
 )
 
-
 class UpdateInstanceMetadataOptionsRequestRequestTypeDef(
     _RequiredUpdateInstanceMetadataOptionsRequestRequestTypeDef,
     _OptionalUpdateInstanceMetadataOptionsRequestRequestTypeDef,
 ):
     pass
 
-
 UpdateLoadBalancerAttributeRequestRequestTypeDef = TypedDict(
     "UpdateLoadBalancerAttributeRequestRequestTypeDef",
     {
         "loadBalancerName": str,
         "attributeName": LoadBalancerAttributeNameType,
         "attributeValue": str,
     },
@@ -2517,22 +2821,20 @@
         "publiclyAccessible": bool,
         "applyImmediately": bool,
         "caCertificateIdentifier": str,
     },
     total=False,
 )
 
-
 class UpdateRelationalDatabaseRequestRequestTypeDef(
     _RequiredUpdateRelationalDatabaseRequestRequestTypeDef,
     _OptionalUpdateRelationalDatabaseRequestRequestTypeDef,
 ):
     pass
 
-
 AccessKeyTypeDef = TypedDict(
     "AccessKeyTypeDef",
     {
         "accessKeyId": str,
         "secretAccessKey": str,
         "status": StatusTypeType,
         "createdAt": datetime,
@@ -2540,30 +2842,29 @@
     },
     total=False,
 )
 
 _RequiredAddOnRequestTypeDef = TypedDict(
     "_RequiredAddOnRequestTypeDef",
     {
-        "addOnType": Literal["AutoSnapshot"],
+        "addOnType": AddOnTypeType,
     },
 )
 _OptionalAddOnRequestTypeDef = TypedDict(
     "_OptionalAddOnRequestTypeDef",
     {
         "autoSnapshotAddOnRequest": AutoSnapshotAddOnRequestTypeDef,
+        "stopInstanceOnIdleRequest": StopInstanceOnIdleRequestTypeDef,
     },
     total=False,
 )
 
-
 class AddOnRequestTypeDef(_RequiredAddOnRequestTypeDef, _OptionalAddOnRequestTypeDef):
     pass
 
-
 AlarmTypeDef = TypedDict(
     "AlarmTypeDef",
     {
         "name": str,
         "arn": str,
         "createdAt": datetime,
         "location": ResourceLocationTypeDef,
@@ -2634,75 +2935,14 @@
         "ipAddress": str,
         "attachedTo": str,
         "isAttached": bool,
     },
     total=False,
 )
 
-DownloadDefaultKeyPairResultTypeDef = TypedDict(
-    "DownloadDefaultKeyPairResultTypeDef",
-    {
-        "publicKeyBase64": str,
-        "privateKeyBase64": str,
-        "createdAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetActiveNamesResultTypeDef = TypedDict(
-    "GetActiveNamesResultTypeDef",
-    {
-        "activeNames": List[str],
-        "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetContainerAPIMetadataResultTypeDef = TypedDict(
-    "GetContainerAPIMetadataResultTypeDef",
-    {
-        "metadata": List[Dict[str, str]],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetDistributionLatestCacheResetResultTypeDef = TypedDict(
-    "GetDistributionLatestCacheResetResultTypeDef",
-    {
-        "status": str,
-        "createTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetRelationalDatabaseLogStreamsResultTypeDef = TypedDict(
-    "GetRelationalDatabaseLogStreamsResultTypeDef",
-    {
-        "logStreams": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetRelationalDatabaseMasterUserPasswordResultTypeDef = TypedDict(
-    "GetRelationalDatabaseMasterUserPasswordResultTypeDef",
-    {
-        "masterUserPassword": str,
-        "createdAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-IsVpcPeeredResultTypeDef = TypedDict(
-    "IsVpcPeeredResultTypeDef",
-    {
-        "isPeered": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 AutoSnapshotDetailsTypeDef = TypedDict(
     "AutoSnapshotDetailsTypeDef",
     {
         "date": str,
         "createdAt": datetime,
         "status": AutoSnapshotStatusType,
         "fromAttachedDisks": List[AttachedDiskTypeDef],
@@ -2724,15 +2964,15 @@
 )
 
 GetBlueprintsResultTypeDef = TypedDict(
     "GetBlueprintsResultTypeDef",
     {
         "blueprints": List[BlueprintTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateBucketRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateBucketRequestRequestTypeDef",
     {
         "bucketName": str,
@@ -2745,26 +2985,24 @@
         "versioning": str,
         "readonlyAccessAccounts": Sequence[str],
         "accessLogConfig": BucketAccessLogConfigTypeDef,
     },
     total=False,
 )
 
-
 class UpdateBucketRequestRequestTypeDef(
     _RequiredUpdateBucketRequestRequestTypeDef, _OptionalUpdateBucketRequestRequestTypeDef
 ):
     pass
 
-
 GetBucketBundlesResultTypeDef = TypedDict(
     "GetBucketBundlesResultTypeDef",
     {
         "bundles": List[BucketBundleTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BucketTypeDef = TypedDict(
     "BucketTypeDef",
     {
         "resourceType": str,
@@ -2799,21 +3037,19 @@
     {
         "tags": Sequence[TagTypeDef],
         "enableObjectVersioning": bool,
     },
     total=False,
 )
 
-
 class CreateBucketRequestRequestTypeDef(
     _RequiredCreateBucketRequestRequestTypeDef, _OptionalCreateBucketRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredCreateCertificateRequestRequestTypeDef = TypedDict(
     "_RequiredCreateCertificateRequestRequestTypeDef",
     {
         "certificateName": str,
         "domainName": str,
     },
 )
@@ -2822,21 +3058,19 @@
     {
         "subjectAlternativeNames": Sequence[str],
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateCertificateRequestRequestTypeDef(
     _RequiredCreateCertificateRequestRequestTypeDef, _OptionalCreateCertificateRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredCreateDiskSnapshotRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDiskSnapshotRequestRequestTypeDef",
     {
         "diskSnapshotName": str,
     },
 )
 _OptionalCreateDiskSnapshotRequestRequestTypeDef = TypedDict(
@@ -2845,43 +3079,39 @@
         "diskName": str,
         "instanceName": str,
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateDiskSnapshotRequestRequestTypeDef(
     _RequiredCreateDiskSnapshotRequestRequestTypeDef,
     _OptionalCreateDiskSnapshotRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredCreateDomainRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDomainRequestRequestTypeDef",
     {
         "domainName": str,
     },
 )
 _OptionalCreateDomainRequestRequestTypeDef = TypedDict(
     "_OptionalCreateDomainRequestRequestTypeDef",
     {
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateDomainRequestRequestTypeDef(
     _RequiredCreateDomainRequestRequestTypeDef, _OptionalCreateDomainRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredCreateInstanceSnapshotRequestRequestTypeDef = TypedDict(
     "_RequiredCreateInstanceSnapshotRequestRequestTypeDef",
     {
         "instanceSnapshotName": str,
         "instanceName": str,
     },
 )
@@ -2889,43 +3119,39 @@
     "_OptionalCreateInstanceSnapshotRequestRequestTypeDef",
     {
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateInstanceSnapshotRequestRequestTypeDef(
     _RequiredCreateInstanceSnapshotRequestRequestTypeDef,
     _OptionalCreateInstanceSnapshotRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredCreateKeyPairRequestRequestTypeDef = TypedDict(
     "_RequiredCreateKeyPairRequestRequestTypeDef",
     {
         "keyPairName": str,
     },
 )
 _OptionalCreateKeyPairRequestRequestTypeDef = TypedDict(
     "_OptionalCreateKeyPairRequestRequestTypeDef",
     {
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateKeyPairRequestRequestTypeDef(
     _RequiredCreateKeyPairRequestRequestTypeDef, _OptionalCreateKeyPairRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredCreateLoadBalancerRequestRequestTypeDef = TypedDict(
     "_RequiredCreateLoadBalancerRequestRequestTypeDef",
     {
         "loadBalancerName": str,
         "instancePort": int,
     },
 )
@@ -2939,22 +3165,20 @@
         "tags": Sequence[TagTypeDef],
         "ipAddressType": IpAddressTypeType,
         "tlsPolicyName": str,
     },
     total=False,
 )
 
-
 class CreateLoadBalancerRequestRequestTypeDef(
     _RequiredCreateLoadBalancerRequestRequestTypeDef,
     _OptionalCreateLoadBalancerRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredCreateLoadBalancerTlsCertificateRequestRequestTypeDef = TypedDict(
     "_RequiredCreateLoadBalancerTlsCertificateRequestRequestTypeDef",
     {
         "loadBalancerName": str,
         "certificateName": str,
         "certificateDomainName": str,
     },
@@ -2964,22 +3188,20 @@
     {
         "certificateAlternativeNames": Sequence[str],
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateLoadBalancerTlsCertificateRequestRequestTypeDef(
     _RequiredCreateLoadBalancerTlsCertificateRequestRequestTypeDef,
     _OptionalCreateLoadBalancerTlsCertificateRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredCreateRelationalDatabaseFromSnapshotRequestRequestTypeDef = TypedDict(
     "_RequiredCreateRelationalDatabaseFromSnapshotRequestRequestTypeDef",
     {
         "relationalDatabaseName": str,
     },
 )
 _OptionalCreateRelationalDatabaseFromSnapshotRequestRequestTypeDef = TypedDict(
@@ -2993,22 +3215,20 @@
         "restoreTime": Union[datetime, str],
         "useLatestRestorableTime": bool,
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateRelationalDatabaseFromSnapshotRequestRequestTypeDef(
     _RequiredCreateRelationalDatabaseFromSnapshotRequestRequestTypeDef,
     _OptionalCreateRelationalDatabaseFromSnapshotRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredCreateRelationalDatabaseRequestRequestTypeDef = TypedDict(
     "_RequiredCreateRelationalDatabaseRequestRequestTypeDef",
     {
         "relationalDatabaseName": str,
         "relationalDatabaseBlueprintId": str,
         "relationalDatabaseBundleId": str,
         "masterDatabaseName": str,
@@ -3024,22 +3244,20 @@
         "preferredMaintenanceWindow": str,
         "publiclyAccessible": bool,
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateRelationalDatabaseRequestRequestTypeDef(
     _RequiredCreateRelationalDatabaseRequestRequestTypeDef,
     _OptionalCreateRelationalDatabaseRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredCreateRelationalDatabaseSnapshotRequestRequestTypeDef = TypedDict(
     "_RequiredCreateRelationalDatabaseSnapshotRequestRequestTypeDef",
     {
         "relationalDatabaseName": str,
         "relationalDatabaseSnapshotName": str,
     },
 )
@@ -3047,22 +3265,20 @@
     "_OptionalCreateRelationalDatabaseSnapshotRequestRequestTypeDef",
     {
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateRelationalDatabaseSnapshotRequestRequestTypeDef(
     _RequiredCreateRelationalDatabaseSnapshotRequestRequestTypeDef,
     _OptionalCreateRelationalDatabaseSnapshotRequestRequestTypeDef,
 ):
     pass
 
-
 DiskSnapshotTypeDef = TypedDict(
     "DiskSnapshotTypeDef",
     {
         "name": str,
         "arn": str,
         "supportCode": str,
         "createdAt": datetime,
@@ -3097,14 +3313,15 @@
         "iops": int,
         "path": str,
         "state": DiskStateType,
         "attachedTo": str,
         "isAttached": bool,
         "attachmentState": str,
         "gbInUse": int,
+        "autoMountStatus": AutoMountStatusType,
     },
     total=False,
 )
 
 KeyPairTypeDef = TypedDict(
     "KeyPairTypeDef",
     {
@@ -3153,27 +3370,25 @@
     "_OptionalTagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
     total=False,
 )
 
-
 class TagResourceRequestRequestTypeDef(
     _RequiredTagResourceRequestRequestTypeDef, _OptionalTagResourceRequestRequestTypeDef
 ):
     pass
 
-
 GetBundlesResultTypeDef = TypedDict(
     "GetBundlesResultTypeDef",
     {
         "bundles": List[BundleTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CacheSettingsTypeDef = TypedDict(
     "CacheSettingsTypeDef",
     {
         "defaultTTL": int,
@@ -3227,23 +3442,23 @@
     total=False,
 )
 
 GetContainerImagesResultTypeDef = TypedDict(
     "GetContainerImagesResultTypeDef",
     {
         "containerImages": List[ContainerImageTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RegisterContainerImageResultTypeDef = TypedDict(
     "RegisterContainerImageResultTypeDef",
     {
         "containerImage": ContainerImageTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PrivateRegistryAccessRequestTypeDef = TypedDict(
     "PrivateRegistryAccessRequestTypeDef",
     {
         "ecrImagePullerRole": ContainerServiceECRImagePullerRoleRequestTypeDef,
@@ -3280,41 +3495,39 @@
     "_OptionalEndpointRequestTypeDef",
     {
         "healthCheck": ContainerServiceHealthCheckConfigTypeDef,
     },
     total=False,
 )
 
-
 class EndpointRequestTypeDef(_RequiredEndpointRequestTypeDef, _OptionalEndpointRequestTypeDef):
     pass
 
-
 GetContainerLogResultTypeDef = TypedDict(
     "GetContainerLogResultTypeDef",
     {
         "logEvents": List[ContainerServiceLogEventTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetContainerServicePowersResultTypeDef = TypedDict(
     "GetContainerServicePowersResultTypeDef",
     {
         "powers": List[ContainerServicePowerTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateContainerServiceRegistryLoginResultTypeDef = TypedDict(
     "CreateContainerServiceRegistryLoginResultTypeDef",
     {
         "registryLogin": ContainerServiceRegistryLoginTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateCloudFormationStackRequestRequestTypeDef = TypedDict(
     "CreateCloudFormationStackRequestRequestTypeDef",
     {
         "instances": Sequence[InstanceEntryTypeDef],
@@ -3341,358 +3554,189 @@
     "UpdateDomainEntryRequestRequestTypeDef",
     {
         "domainName": str,
         "domainEntry": DomainEntryTypeDef,
     },
 )
 
+CreateGUISessionAccessDetailsResultTypeDef = TypedDict(
+    "CreateGUISessionAccessDetailsResultTypeDef",
+    {
+        "resourceName": str,
+        "status": StatusType,
+        "percentageComplete": int,
+        "failureReason": str,
+        "sessions": List[SessionTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 InstanceSnapshotInfoTypeDef = TypedDict(
     "InstanceSnapshotInfoTypeDef",
     {
         "fromBundleId": str,
         "fromBlueprintId": str,
         "fromDiskInfo": List[DiskInfoTypeDef],
     },
     total=False,
 )
 
 GetDistributionBundlesResultTypeDef = TypedDict(
     "GetDistributionBundlesResultTypeDef",
     {
         "bundles": List[DistributionBundleTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DomainValidationRecordTypeDef = TypedDict(
     "DomainValidationRecordTypeDef",
     {
         "domainName": str,
         "resourceRecord": ResourceRecordTypeDef,
         "dnsRecordCreationState": DnsRecordCreationStateTypeDef,
         "validationStatus": CertificateDomainValidationStatusType,
     },
     total=False,
 )
 
-GetActiveNamesRequestGetActiveNamesPaginateTypeDef = TypedDict(
-    "GetActiveNamesRequestGetActiveNamesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetBlueprintsRequestGetBlueprintsPaginateTypeDef = TypedDict(
-    "GetBlueprintsRequestGetBlueprintsPaginateTypeDef",
-    {
-        "includeInactive": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetBundlesRequestGetBundlesPaginateTypeDef = TypedDict(
-    "GetBundlesRequestGetBundlesPaginateTypeDef",
-    {
-        "includeInactive": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetCloudFormationStackRecordsRequestGetCloudFormationStackRecordsPaginateTypeDef = TypedDict(
-    "GetCloudFormationStackRecordsRequestGetCloudFormationStackRecordsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetDiskSnapshotsRequestGetDiskSnapshotsPaginateTypeDef = TypedDict(
-    "GetDiskSnapshotsRequestGetDiskSnapshotsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetDisksRequestGetDisksPaginateTypeDef = TypedDict(
-    "GetDisksRequestGetDisksPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetDomainsRequestGetDomainsPaginateTypeDef = TypedDict(
-    "GetDomainsRequestGetDomainsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetExportSnapshotRecordsRequestGetExportSnapshotRecordsPaginateTypeDef = TypedDict(
-    "GetExportSnapshotRecordsRequestGetExportSnapshotRecordsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetInstanceSnapshotsRequestGetInstanceSnapshotsPaginateTypeDef = TypedDict(
-    "GetInstanceSnapshotsRequestGetInstanceSnapshotsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetInstancesRequestGetInstancesPaginateTypeDef = TypedDict(
-    "GetInstancesRequestGetInstancesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetKeyPairsRequestGetKeyPairsPaginateTypeDef = TypedDict(
-    "GetKeyPairsRequestGetKeyPairsPaginateTypeDef",
-    {
-        "includeDefaultKeyPair": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetLoadBalancersRequestGetLoadBalancersPaginateTypeDef = TypedDict(
-    "GetLoadBalancersRequestGetLoadBalancersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetOperationsRequestGetOperationsPaginateTypeDef = TypedDict(
-    "GetOperationsRequestGetOperationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetRelationalDatabaseBlueprintsRequestGetRelationalDatabaseBlueprintsPaginateTypeDef = TypedDict(
-    "GetRelationalDatabaseBlueprintsRequestGetRelationalDatabaseBlueprintsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetRelationalDatabaseBundlesRequestGetRelationalDatabaseBundlesPaginateTypeDef = TypedDict(
-    "GetRelationalDatabaseBundlesRequestGetRelationalDatabaseBundlesPaginateTypeDef",
-    {
-        "includeInactive": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredGetRelationalDatabaseEventsRequestGetRelationalDatabaseEventsPaginateTypeDef = TypedDict(
-    "_RequiredGetRelationalDatabaseEventsRequestGetRelationalDatabaseEventsPaginateTypeDef",
-    {
-        "relationalDatabaseName": str,
-    },
-)
-_OptionalGetRelationalDatabaseEventsRequestGetRelationalDatabaseEventsPaginateTypeDef = TypedDict(
-    "_OptionalGetRelationalDatabaseEventsRequestGetRelationalDatabaseEventsPaginateTypeDef",
-    {
-        "durationInMinutes": int,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetRelationalDatabaseEventsRequestGetRelationalDatabaseEventsPaginateTypeDef(
-    _RequiredGetRelationalDatabaseEventsRequestGetRelationalDatabaseEventsPaginateTypeDef,
-    _OptionalGetRelationalDatabaseEventsRequestGetRelationalDatabaseEventsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredGetRelationalDatabaseParametersRequestGetRelationalDatabaseParametersPaginateTypeDef = TypedDict(
-    "_RequiredGetRelationalDatabaseParametersRequestGetRelationalDatabaseParametersPaginateTypeDef",
-    {
-        "relationalDatabaseName": str,
-    },
-)
-_OptionalGetRelationalDatabaseParametersRequestGetRelationalDatabaseParametersPaginateTypeDef = TypedDict(
-    "_OptionalGetRelationalDatabaseParametersRequestGetRelationalDatabaseParametersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class GetRelationalDatabaseParametersRequestGetRelationalDatabaseParametersPaginateTypeDef(
-    _RequiredGetRelationalDatabaseParametersRequestGetRelationalDatabaseParametersPaginateTypeDef,
-    _OptionalGetRelationalDatabaseParametersRequestGetRelationalDatabaseParametersPaginateTypeDef,
-):
-    pass
-
-
-GetRelationalDatabaseSnapshotsRequestGetRelationalDatabaseSnapshotsPaginateTypeDef = TypedDict(
-    "GetRelationalDatabaseSnapshotsRequestGetRelationalDatabaseSnapshotsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetRelationalDatabasesRequestGetRelationalDatabasesPaginateTypeDef = TypedDict(
-    "GetRelationalDatabasesRequestGetRelationalDatabasesPaginateTypeDef",
+EstimateByTimeTypeDef = TypedDict(
+    "EstimateByTimeTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetStaticIpsRequestGetStaticIpsPaginateTypeDef = TypedDict(
-    "GetStaticIpsRequestGetStaticIpsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "usageCost": float,
+        "pricingUnit": PricingUnitType,
+        "unit": float,
+        "currency": Literal["USD"],
+        "timePeriod": TimePeriodTypeDef,
     },
     total=False,
 )
 
 GetBucketMetricDataResultTypeDef = TypedDict(
     "GetBucketMetricDataResultTypeDef",
     {
         "metricName": BucketMetricNameType,
         "metricData": List[MetricDatapointTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetContainerServiceMetricDataResultTypeDef = TypedDict(
     "GetContainerServiceMetricDataResultTypeDef",
     {
         "metricName": ContainerServiceMetricNameType,
         "metricData": List[MetricDatapointTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDistributionMetricDataResultTypeDef = TypedDict(
     "GetDistributionMetricDataResultTypeDef",
     {
         "metricName": DistributionMetricNameType,
         "metricData": List[MetricDatapointTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetInstanceMetricDataResultTypeDef = TypedDict(
     "GetInstanceMetricDataResultTypeDef",
     {
         "metricName": InstanceMetricNameType,
         "metricData": List[MetricDatapointTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetLoadBalancerMetricDataResultTypeDef = TypedDict(
     "GetLoadBalancerMetricDataResultTypeDef",
     {
         "metricName": LoadBalancerMetricNameType,
         "metricData": List[MetricDatapointTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRelationalDatabaseMetricDataResultTypeDef = TypedDict(
     "GetRelationalDatabaseMetricDataResultTypeDef",
     {
         "metricName": RelationalDatabaseMetricNameType,
         "metricData": List[MetricDatapointTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetInstancePortStatesResultTypeDef = TypedDict(
     "GetInstancePortStatesResultTypeDef",
     {
         "portStates": List[InstancePortStateTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetInstanceStateResultTypeDef = TypedDict(
     "GetInstanceStateResultTypeDef",
     {
         "state": InstanceStateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetLoadBalancerTlsPoliciesResultTypeDef = TypedDict(
     "GetLoadBalancerTlsPoliciesResultTypeDef",
     {
         "tlsPolicies": List[LoadBalancerTlsPolicyTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRelationalDatabaseBlueprintsResultTypeDef = TypedDict(
     "GetRelationalDatabaseBlueprintsResultTypeDef",
     {
         "blueprints": List[RelationalDatabaseBlueprintTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRelationalDatabaseBundlesResultTypeDef = TypedDict(
     "GetRelationalDatabaseBundlesResultTypeDef",
     {
         "bundles": List[RelationalDatabaseBundleTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRelationalDatabaseEventsResultTypeDef = TypedDict(
     "GetRelationalDatabaseEventsResultTypeDef",
     {
         "relationalDatabaseEvents": List[RelationalDatabaseEventTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRelationalDatabaseLogEventsResultTypeDef = TypedDict(
     "GetRelationalDatabaseLogEventsResultTypeDef",
     {
         "resourceLogEvents": List[LogEventTypeDef],
         "nextBackwardToken": str,
         "nextForwardToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRelationalDatabaseParametersResultTypeDef = TypedDict(
     "GetRelationalDatabaseParametersResultTypeDef",
     {
         "parameters": List[RelationalDatabaseParameterTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateRelationalDatabaseParametersRequestRequestTypeDef = TypedDict(
     "UpdateRelationalDatabaseParametersRequestRequestTypeDef",
     {
         "relationalDatabaseName": str,
@@ -3816,15 +3860,15 @@
     total=False,
 )
 
 GetBucketAccessKeysResultTypeDef = TypedDict(
     "GetBucketAccessKeysResultTypeDef",
     {
         "accessKeys": List[AccessKeyTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateDiskFromSnapshotRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDiskFromSnapshotRequestRequestTypeDef",
     {
         "diskName": str,
@@ -3841,22 +3885,20 @@
         "sourceDiskName": str,
         "restoreDate": str,
         "useLatestRestorableAutoSnapshot": bool,
     },
     total=False,
 )
 
-
 class CreateDiskFromSnapshotRequestRequestTypeDef(
     _RequiredCreateDiskFromSnapshotRequestRequestTypeDef,
     _OptionalCreateDiskFromSnapshotRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredCreateDiskRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDiskRequestRequestTypeDef",
     {
         "diskName": str,
         "availabilityZone": str,
         "sizeInGb": int,
     },
@@ -3866,21 +3908,19 @@
     {
         "tags": Sequence[TagTypeDef],
         "addOns": Sequence[AddOnRequestTypeDef],
     },
     total=False,
 )
 
-
 class CreateDiskRequestRequestTypeDef(
     _RequiredCreateDiskRequestRequestTypeDef, _OptionalCreateDiskRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredCreateInstancesFromSnapshotRequestRequestTypeDef = TypedDict(
     "_RequiredCreateInstancesFromSnapshotRequestRequestTypeDef",
     {
         "instanceNames": Sequence[str],
         "availabilityZone": str,
         "bundleId": str,
     },
@@ -3898,22 +3938,20 @@
         "sourceInstanceName": str,
         "restoreDate": str,
         "useLatestRestorableAutoSnapshot": bool,
     },
     total=False,
 )
 
-
 class CreateInstancesFromSnapshotRequestRequestTypeDef(
     _RequiredCreateInstancesFromSnapshotRequestRequestTypeDef,
     _OptionalCreateInstancesFromSnapshotRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredCreateInstancesRequestRequestTypeDef = TypedDict(
     "_RequiredCreateInstancesRequestRequestTypeDef",
     {
         "instanceNames": Sequence[str],
         "availabilityZone": str,
         "blueprintId": str,
         "bundleId": str,
@@ -3928,794 +3966,808 @@
         "tags": Sequence[TagTypeDef],
         "addOns": Sequence[AddOnRequestTypeDef],
         "ipAddressType": IpAddressTypeType,
     },
     total=False,
 )
 
-
 class CreateInstancesRequestRequestTypeDef(
     _RequiredCreateInstancesRequestRequestTypeDef, _OptionalCreateInstancesRequestRequestTypeDef
 ):
     pass
 
-
 EnableAddOnRequestRequestTypeDef = TypedDict(
     "EnableAddOnRequestRequestTypeDef",
     {
         "resourceName": str,
         "addOnRequest": AddOnRequestTypeDef,
     },
 )
 
 GetAlarmsResultTypeDef = TypedDict(
     "GetAlarmsResultTypeDef",
     {
         "alarms": List[AlarmTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetContactMethodsResultTypeDef = TypedDict(
     "GetContactMethodsResultTypeDef",
     {
         "contactMethods": List[ContactMethodTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AllocateStaticIpResultTypeDef = TypedDict(
     "AllocateStaticIpResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AttachCertificateToDistributionResultTypeDef = TypedDict(
     "AttachCertificateToDistributionResultTypeDef",
     {
         "operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AttachDiskResultTypeDef = TypedDict(
     "AttachDiskResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AttachInstancesToLoadBalancerResultTypeDef = TypedDict(
     "AttachInstancesToLoadBalancerResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AttachLoadBalancerTlsCertificateResultTypeDef = TypedDict(
     "AttachLoadBalancerTlsCertificateResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AttachStaticIpResultTypeDef = TypedDict(
     "AttachStaticIpResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CloseInstancePublicPortsResultTypeDef = TypedDict(
     "CloseInstancePublicPortsResultTypeDef",
     {
         "operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CopySnapshotResultTypeDef = TypedDict(
     "CopySnapshotResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateBucketAccessKeyResultTypeDef = TypedDict(
     "CreateBucketAccessKeyResultTypeDef",
     {
         "accessKey": AccessKeyTypeDef,
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateCloudFormationStackResultTypeDef = TypedDict(
     "CreateCloudFormationStackResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateContactMethodResultTypeDef = TypedDict(
     "CreateContactMethodResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDiskFromSnapshotResultTypeDef = TypedDict(
     "CreateDiskFromSnapshotResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDiskResultTypeDef = TypedDict(
     "CreateDiskResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDiskSnapshotResultTypeDef = TypedDict(
     "CreateDiskSnapshotResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDomainEntryResultTypeDef = TypedDict(
     "CreateDomainEntryResultTypeDef",
     {
         "operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDomainResultTypeDef = TypedDict(
     "CreateDomainResultTypeDef",
     {
         "operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateInstanceSnapshotResultTypeDef = TypedDict(
     "CreateInstanceSnapshotResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateInstancesFromSnapshotResultTypeDef = TypedDict(
     "CreateInstancesFromSnapshotResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateInstancesResultTypeDef = TypedDict(
     "CreateInstancesResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateLoadBalancerResultTypeDef = TypedDict(
     "CreateLoadBalancerResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateLoadBalancerTlsCertificateResultTypeDef = TypedDict(
     "CreateLoadBalancerTlsCertificateResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateRelationalDatabaseFromSnapshotResultTypeDef = TypedDict(
     "CreateRelationalDatabaseFromSnapshotResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateRelationalDatabaseResultTypeDef = TypedDict(
     "CreateRelationalDatabaseResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateRelationalDatabaseSnapshotResultTypeDef = TypedDict(
     "CreateRelationalDatabaseSnapshotResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteAlarmResultTypeDef = TypedDict(
     "DeleteAlarmResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteAutoSnapshotResultTypeDef = TypedDict(
     "DeleteAutoSnapshotResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteBucketAccessKeyResultTypeDef = TypedDict(
     "DeleteBucketAccessKeyResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteBucketResultTypeDef = TypedDict(
     "DeleteBucketResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteCertificateResultTypeDef = TypedDict(
     "DeleteCertificateResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteContactMethodResultTypeDef = TypedDict(
     "DeleteContactMethodResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteDiskResultTypeDef = TypedDict(
     "DeleteDiskResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteDiskSnapshotResultTypeDef = TypedDict(
     "DeleteDiskSnapshotResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteDistributionResultTypeDef = TypedDict(
     "DeleteDistributionResultTypeDef",
     {
         "operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteDomainEntryResultTypeDef = TypedDict(
     "DeleteDomainEntryResultTypeDef",
     {
         "operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteDomainResultTypeDef = TypedDict(
     "DeleteDomainResultTypeDef",
     {
         "operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteInstanceResultTypeDef = TypedDict(
     "DeleteInstanceResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteInstanceSnapshotResultTypeDef = TypedDict(
     "DeleteInstanceSnapshotResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteKeyPairResultTypeDef = TypedDict(
     "DeleteKeyPairResultTypeDef",
     {
         "operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteKnownHostKeysResultTypeDef = TypedDict(
     "DeleteKnownHostKeysResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteLoadBalancerResultTypeDef = TypedDict(
     "DeleteLoadBalancerResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteLoadBalancerTlsCertificateResultTypeDef = TypedDict(
     "DeleteLoadBalancerTlsCertificateResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteRelationalDatabaseResultTypeDef = TypedDict(
     "DeleteRelationalDatabaseResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteRelationalDatabaseSnapshotResultTypeDef = TypedDict(
     "DeleteRelationalDatabaseSnapshotResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DetachCertificateFromDistributionResultTypeDef = TypedDict(
     "DetachCertificateFromDistributionResultTypeDef",
     {
         "operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DetachDiskResultTypeDef = TypedDict(
     "DetachDiskResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DetachInstancesFromLoadBalancerResultTypeDef = TypedDict(
     "DetachInstancesFromLoadBalancerResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DetachStaticIpResultTypeDef = TypedDict(
     "DetachStaticIpResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisableAddOnResultTypeDef = TypedDict(
     "DisableAddOnResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EnableAddOnResultTypeDef = TypedDict(
     "EnableAddOnResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ExportSnapshotResultTypeDef = TypedDict(
     "ExportSnapshotResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetOperationResultTypeDef = TypedDict(
     "GetOperationResultTypeDef",
     {
         "operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetOperationsForResourceResultTypeDef = TypedDict(
     "GetOperationsForResourceResultTypeDef",
     {
         "operations": List[OperationTypeDef],
         "nextPageCount": str,
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetOperationsResultTypeDef = TypedDict(
     "GetOperationsResultTypeDef",
     {
         "operations": List[OperationTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ImportKeyPairResultTypeDef = TypedDict(
     "ImportKeyPairResultTypeDef",
     {
         "operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OpenInstancePublicPortsResultTypeDef = TypedDict(
     "OpenInstancePublicPortsResultTypeDef",
     {
         "operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PeerVpcResultTypeDef = TypedDict(
     "PeerVpcResultTypeDef",
     {
         "operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutAlarmResultTypeDef = TypedDict(
     "PutAlarmResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutInstancePublicPortsResultTypeDef = TypedDict(
     "PutInstancePublicPortsResultTypeDef",
     {
         "operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RebootInstanceResultTypeDef = TypedDict(
     "RebootInstanceResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RebootRelationalDatabaseResultTypeDef = TypedDict(
     "RebootRelationalDatabaseResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReleaseStaticIpResultTypeDef = TypedDict(
     "ReleaseStaticIpResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResetDistributionCacheResultTypeDef = TypedDict(
     "ResetDistributionCacheResultTypeDef",
     {
         "status": str,
         "createTime": datetime,
         "operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SendContactMethodVerificationResultTypeDef = TypedDict(
     "SendContactMethodVerificationResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SetIpAddressTypeResultTypeDef = TypedDict(
     "SetIpAddressTypeResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SetResourceAccessForBucketResultTypeDef = TypedDict(
     "SetResourceAccessForBucketResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartGUISessionResultTypeDef = TypedDict(
+    "StartGUISessionResultTypeDef",
+    {
+        "operations": List[OperationTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartInstanceResultTypeDef = TypedDict(
     "StartInstanceResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartRelationalDatabaseResultTypeDef = TypedDict(
     "StartRelationalDatabaseResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StopGUISessionResultTypeDef = TypedDict(
+    "StopGUISessionResultTypeDef",
+    {
+        "operations": List[OperationTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopInstanceResultTypeDef = TypedDict(
     "StopInstanceResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopRelationalDatabaseResultTypeDef = TypedDict(
     "StopRelationalDatabaseResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceResultTypeDef = TypedDict(
     "TagResourceResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TestAlarmResultTypeDef = TypedDict(
     "TestAlarmResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UnpeerVpcResultTypeDef = TypedDict(
     "UnpeerVpcResultTypeDef",
     {
         "operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UntagResourceResultTypeDef = TypedDict(
     "UntagResourceResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateBucketBundleResultTypeDef = TypedDict(
     "UpdateBucketBundleResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDistributionBundleResultTypeDef = TypedDict(
     "UpdateDistributionBundleResultTypeDef",
     {
         "operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDistributionResultTypeDef = TypedDict(
     "UpdateDistributionResultTypeDef",
     {
         "operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDomainEntryResultTypeDef = TypedDict(
     "UpdateDomainEntryResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateInstanceMetadataOptionsResultTypeDef = TypedDict(
     "UpdateInstanceMetadataOptionsResultTypeDef",
     {
         "operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateLoadBalancerAttributeResultTypeDef = TypedDict(
     "UpdateLoadBalancerAttributeResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateRelationalDatabaseParametersResultTypeDef = TypedDict(
     "UpdateRelationalDatabaseParametersResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateRelationalDatabaseResultTypeDef = TypedDict(
     "UpdateRelationalDatabaseResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetStaticIpResultTypeDef = TypedDict(
     "GetStaticIpResultTypeDef",
     {
         "staticIp": StaticIpTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetStaticIpsResultTypeDef = TypedDict(
     "GetStaticIpsResultTypeDef",
     {
         "staticIps": List[StaticIpTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAutoSnapshotsResultTypeDef = TypedDict(
     "GetAutoSnapshotsResultTypeDef",
     {
         "resourceName": str,
         "resourceType": ResourceTypeType,
         "autoSnapshots": List[AutoSnapshotDetailsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRegionsResultTypeDef = TypedDict(
     "GetRegionsResultTypeDef",
     {
         "regions": List[RegionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateBucketResultTypeDef = TypedDict(
     "CreateBucketResultTypeDef",
     {
         "bucket": BucketTypeDef,
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetBucketsResultTypeDef = TypedDict(
     "GetBucketsResultTypeDef",
     {
         "buckets": List[BucketTypeDef],
         "nextPageToken": str,
         "accountLevelBpaSync": AccountLevelBpaSyncTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateBucketResultTypeDef = TypedDict(
     "UpdateBucketResultTypeDef",
     {
         "bucket": BucketTypeDef,
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDiskSnapshotResultTypeDef = TypedDict(
     "GetDiskSnapshotResultTypeDef",
     {
         "diskSnapshot": DiskSnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDiskSnapshotsResultTypeDef = TypedDict(
     "GetDiskSnapshotsResultTypeDef",
     {
         "diskSnapshots": List[DiskSnapshotTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDiskResultTypeDef = TypedDict(
     "GetDiskResultTypeDef",
     {
         "disk": DiskTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDisksResultTypeDef = TypedDict(
     "GetDisksResultTypeDef",
     {
         "disks": List[DiskTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InstanceHardwareTypeDef = TypedDict(
     "InstanceHardwareTypeDef",
     {
         "cpuCount": int,
@@ -4751,49 +4803,49 @@
 CreateKeyPairResultTypeDef = TypedDict(
     "CreateKeyPairResultTypeDef",
     {
         "keyPair": KeyPairTypeDef,
         "publicKeyBase64": str,
         "privateKeyBase64": str,
         "operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetKeyPairResultTypeDef = TypedDict(
     "GetKeyPairResultTypeDef",
     {
         "keyPair": KeyPairTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetKeyPairsResultTypeDef = TypedDict(
     "GetKeyPairsResultTypeDef",
     {
         "keyPairs": List[KeyPairTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRelationalDatabaseSnapshotResultTypeDef = TypedDict(
     "GetRelationalDatabaseSnapshotResultTypeDef",
     {
         "relationalDatabaseSnapshot": RelationalDatabaseSnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRelationalDatabaseSnapshotsResultTypeDef = TypedDict(
     "GetRelationalDatabaseSnapshotsResultTypeDef",
     {
         "relationalDatabaseSnapshots": List[RelationalDatabaseSnapshotTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateDistributionRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDistributionRequestRequestTypeDef",
     {
         "distributionName": str,
@@ -4809,22 +4861,20 @@
         "cacheBehaviors": Sequence[CacheBehaviorPerPathTypeDef],
         "ipAddressType": IpAddressTypeType,
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateDistributionRequestRequestTypeDef(
     _RequiredCreateDistributionRequestRequestTypeDef,
     _OptionalCreateDistributionRequestRequestTypeDef,
 ):
     pass
 
-
 LightsailDistributionTypeDef = TypedDict(
     "LightsailDistributionTypeDef",
     {
         "name": str,
         "arn": str,
         "supportCode": str,
         "createdAt": datetime,
@@ -4862,28 +4912,26 @@
         "cacheBehaviorSettings": CacheSettingsTypeDef,
         "cacheBehaviors": Sequence[CacheBehaviorPerPathTypeDef],
         "isEnabled": bool,
     },
     total=False,
 )
 
-
 class UpdateDistributionRequestRequestTypeDef(
     _RequiredUpdateDistributionRequestRequestTypeDef,
     _OptionalUpdateDistributionRequestRequestTypeDef,
 ):
     pass
 
-
 GetCloudFormationStackRecordsResultTypeDef = TypedDict(
     "GetCloudFormationStackRecordsResultTypeDef",
     {
         "cloudFormationStackRecords": List[CloudFormationStackRecordTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateContainerServiceRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateContainerServiceRequestRequestTypeDef",
     {
         "serviceName": str,
@@ -4897,22 +4945,20 @@
         "isDisabled": bool,
         "publicDomainNames": Mapping[str, Sequence[str]],
         "privateRegistryAccess": PrivateRegistryAccessRequestTypeDef,
     },
     total=False,
 )
 
-
 class UpdateContainerServiceRequestRequestTypeDef(
     _RequiredUpdateContainerServiceRequestRequestTypeDef,
     _OptionalUpdateContainerServiceRequestRequestTypeDef,
 ):
     pass
 
-
 ContainerServiceDeploymentTypeDef = TypedDict(
     "ContainerServiceDeploymentTypeDef",
     {
         "version": int,
         "state": ContainerServiceDeploymentStateType,
         "containers": Dict[str, ContainerTypeDef],
         "publicEndpoint": ContainerServiceEndpointTypeDef,
@@ -4941,22 +4987,20 @@
     {
         "containers": Mapping[str, ContainerTypeDef],
         "publicEndpoint": EndpointRequestTypeDef,
     },
     total=False,
 )
 
-
 class CreateContainerServiceDeploymentRequestRequestTypeDef(
     _RequiredCreateContainerServiceDeploymentRequestRequestTypeDef,
     _OptionalCreateContainerServiceDeploymentRequestRequestTypeDef,
 ):
     pass
 
-
 ExportSnapshotRecordSourceInfoTypeDef = TypedDict(
     "ExportSnapshotRecordSourceInfoTypeDef",
     {
         "resourceType": ExportSnapshotRecordSourceTypeType,
         "createdAt": datetime,
         "name": str,
         "arn": str,
@@ -4975,19 +5019,28 @@
         "renewalStatus": RenewalStatusType,
         "renewalStatusReason": str,
         "updatedAt": datetime,
     },
     total=False,
 )
 
+CostEstimateTypeDef = TypedDict(
+    "CostEstimateTypeDef",
+    {
+        "usageType": str,
+        "resultsByTime": List[EstimateByTimeTypeDef],
+    },
+    total=False,
+)
+
 GetInstanceAccessDetailsResultTypeDef = TypedDict(
     "GetInstanceAccessDetailsResultTypeDef",
     {
         "accessDetails": InstanceAccessDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LoadBalancerTlsCertificateTypeDef = TypedDict(
     "LoadBalancerTlsCertificateTypeDef",
     {
         "name": str,
@@ -5019,24 +5072,24 @@
     total=False,
 )
 
 GetLoadBalancerResultTypeDef = TypedDict(
     "GetLoadBalancerResultTypeDef",
     {
         "loadBalancer": LoadBalancerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetLoadBalancersResultTypeDef = TypedDict(
     "GetLoadBalancersResultTypeDef",
     {
         "loadBalancers": List[LoadBalancerTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DomainTypeDef = TypedDict(
     "DomainTypeDef",
     {
         "name": str,
@@ -5052,24 +5105,24 @@
     total=False,
 )
 
 GetRelationalDatabaseResultTypeDef = TypedDict(
     "GetRelationalDatabaseResultTypeDef",
     {
         "relationalDatabase": RelationalDatabaseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRelationalDatabasesResultTypeDef = TypedDict(
     "GetRelationalDatabasesResultTypeDef",
     {
         "relationalDatabases": List[RelationalDatabaseTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InstanceTypeDef = TypedDict(
     "InstanceTypeDef",
     {
         "name": str,
@@ -5098,42 +5151,42 @@
     total=False,
 )
 
 GetInstanceSnapshotResultTypeDef = TypedDict(
     "GetInstanceSnapshotResultTypeDef",
     {
         "instanceSnapshot": InstanceSnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetInstanceSnapshotsResultTypeDef = TypedDict(
     "GetInstanceSnapshotsResultTypeDef",
     {
         "instanceSnapshots": List[InstanceSnapshotTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDistributionResultTypeDef = TypedDict(
     "CreateDistributionResultTypeDef",
     {
         "distribution": LightsailDistributionTypeDef,
         "operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDistributionsResultTypeDef = TypedDict(
     "GetDistributionsResultTypeDef",
     {
         "distributions": List[LightsailDistributionTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ContainerServiceTypeDef = TypedDict(
     "ContainerServiceTypeDef",
     {
         "containerServiceName": str,
@@ -5159,15 +5212,15 @@
     total=False,
 )
 
 GetContainerServiceDeploymentsResultTypeDef = TypedDict(
     "GetContainerServiceDeploymentsResultTypeDef",
     {
         "deployments": List[ContainerServiceDeploymentTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateContainerServiceRequestRequestTypeDef = TypedDict(
     "_RequiredCreateContainerServiceRequestRequestTypeDef",
     {
         "serviceName": str,
@@ -5182,22 +5235,20 @@
         "publicDomainNames": Mapping[str, Sequence[str]],
         "deployment": ContainerServiceDeploymentRequestTypeDef,
         "privateRegistryAccess": PrivateRegistryAccessRequestTypeDef,
     },
     total=False,
 )
 
-
 class CreateContainerServiceRequestRequestTypeDef(
     _RequiredCreateContainerServiceRequestRequestTypeDef,
     _OptionalCreateContainerServiceRequestRequestTypeDef,
 ):
     pass
 
-
 ExportSnapshotRecordTypeDef = TypedDict(
     "ExportSnapshotRecordTypeDef",
     {
         "name": str,
         "arn": str,
         "createdAt": datetime,
         "location": ResourceLocationTypeDef,
@@ -5233,94 +5284,106 @@
         "revocationReason": str,
         "tags": List[TagTypeDef],
         "supportCode": str,
     },
     total=False,
 )
 
+ResourceBudgetEstimateTypeDef = TypedDict(
+    "ResourceBudgetEstimateTypeDef",
+    {
+        "resourceName": str,
+        "resourceType": ResourceTypeType,
+        "costEstimates": List[CostEstimateTypeDef],
+        "startTime": datetime,
+        "endTime": datetime,
+    },
+    total=False,
+)
+
 GetLoadBalancerTlsCertificatesResultTypeDef = TypedDict(
     "GetLoadBalancerTlsCertificatesResultTypeDef",
     {
         "tlsCertificates": List[LoadBalancerTlsCertificateTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDomainResultTypeDef = TypedDict(
     "GetDomainResultTypeDef",
     {
         "domain": DomainTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDomainsResultTypeDef = TypedDict(
     "GetDomainsResultTypeDef",
     {
         "domains": List[DomainTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetInstanceResultTypeDef = TypedDict(
     "GetInstanceResultTypeDef",
     {
         "instance": InstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetInstancesResultTypeDef = TypedDict(
     "GetInstancesResultTypeDef",
     {
         "instances": List[InstanceTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ContainerServicesListResultTypeDef = TypedDict(
     "ContainerServicesListResultTypeDef",
     {
         "containerServices": List[ContainerServiceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateContainerServiceDeploymentResultTypeDef = TypedDict(
     "CreateContainerServiceDeploymentResultTypeDef",
     {
         "containerService": ContainerServiceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateContainerServiceResultTypeDef = TypedDict(
     "CreateContainerServiceResultTypeDef",
     {
         "containerService": ContainerServiceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateContainerServiceResultTypeDef = TypedDict(
     "UpdateContainerServiceResultTypeDef",
     {
         "containerService": ContainerServiceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetExportSnapshotRecordsResultTypeDef = TypedDict(
     "GetExportSnapshotRecordsResultTypeDef",
     {
         "exportSnapshotRecords": List[ExportSnapshotRecordTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CertificateSummaryTypeDef = TypedDict(
     "CertificateSummaryTypeDef",
     {
         "certificateArn": str,
@@ -5328,23 +5391,32 @@
         "domainName": str,
         "certificateDetail": CertificateTypeDef,
         "tags": List[TagTypeDef],
     },
     total=False,
 )
 
+GetCostEstimateResultTypeDef = TypedDict(
+    "GetCostEstimateResultTypeDef",
+    {
+        "resourcesBudgetEstimate": List[ResourceBudgetEstimateTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateCertificateResultTypeDef = TypedDict(
     "CreateCertificateResultTypeDef",
     {
         "certificate": CertificateSummaryTypeDef,
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCertificatesResultTypeDef = TypedDict(
     "GetCertificatesResultTypeDef",
     {
         "certificates": List[CertificateSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "nextPageToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-lightsail-2.5.0.post1/types_aiobotocore_lightsail/type_defs.pyi` & `types-aiobotocore-lightsail-2.5.1/types_aiobotocore_lightsail/type_defs.py`

 * *Files 6% similar despite different names*

```diff
@@ -15,15 +15,17 @@
 from datetime import datetime
 from typing import Dict, List, Mapping, Sequence, Union
 
 from .literals import (
     AccessDirectionType,
     AccessTypeType,
     AccountLevelBpaSyncStatusType,
+    AddOnTypeType,
     AlarmStateType,
+    AutoMountStatusType,
     AutoSnapshotStatusType,
     BehaviorEnumType,
     BlueprintTypeType,
     BPAStatusMessageType,
     BucketMetricNameType,
     CertificateDomainValidationStatusType,
     CertificateStatusType,
@@ -71,45 +73,48 @@
     NetworkProtocolType,
     OperationStatusType,
     OperationTypeType,
     OriginProtocolPolicyEnumType,
     PortAccessTypeType,
     PortInfoSourceTypeType,
     PortStateType,
+    PricingUnitType,
     R53HostedZoneDeletionStateCodeType,
     RecordStateType,
     RegionNameType,
     RelationalDatabaseMetricNameType,
     RelationalDatabasePasswordVersionType,
     RenewalStatusType,
     ResourceBucketAccessType,
     ResourceTypeType,
+    StatusType,
     StatusTypeType,
     TreatMissingDataType,
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
     "AccessKeyLastUsedTypeDef",
     "AccessRulesTypeDef",
     "AccountLevelBpaSyncTypeDef",
     "AutoSnapshotAddOnRequestTypeDef",
+    "StopInstanceOnIdleRequestTypeDef",
     "AddOnTypeDef",
     "MonitoredResourceInfoTypeDef",
     "ResourceLocationTypeDef",
     "AllocateStaticIpRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "AttachCertificateToDistributionRequestRequestTypeDef",
     "AttachDiskRequestRequestTypeDef",
     "AttachInstancesToLoadBalancerRequestRequestTypeDef",
     "AttachLoadBalancerTlsCertificateRequestRequestTypeDef",
     "AttachStaticIpRequestRequestTypeDef",
     "AttachedDiskTypeDef",
     "AvailabilityZoneTypeDef",
@@ -139,14 +144,16 @@
     "ContainerServiceStateDetailTypeDef",
     "CopySnapshotRequestRequestTypeDef",
     "CreateBucketAccessKeyRequestRequestTypeDef",
     "InstanceEntryTypeDef",
     "CreateContactMethodRequestRequestTypeDef",
     "InputOriginTypeDef",
     "DomainEntryTypeDef",
+    "CreateGUISessionAccessDetailsRequestRequestTypeDef",
+    "SessionTypeDef",
     "DiskMapTypeDef",
     "DeleteAlarmRequestRequestTypeDef",
     "DeleteAutoSnapshotRequestRequestTypeDef",
     "DeleteBucketAccessKeyRequestRequestTypeDef",
     "DeleteBucketRequestRequestTypeDef",
     "DeleteCertificateRequestRequestTypeDef",
     "DeleteContactMethodRequestRequestTypeDef",
@@ -170,113 +177,145 @@
     "DetachStaticIpRequestRequestTypeDef",
     "DisableAddOnRequestRequestTypeDef",
     "DiskInfoTypeDef",
     "DiskSnapshotInfoTypeDef",
     "DistributionBundleTypeDef",
     "DnsRecordCreationStateTypeDef",
     "ResourceRecordTypeDef",
+    "DownloadDefaultKeyPairResultTypeDef",
+    "TimePeriodTypeDef",
     "ExportSnapshotRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetActiveNamesRequestGetActiveNamesPaginateTypeDef",
     "GetActiveNamesRequestRequestTypeDef",
+    "GetActiveNamesResultTypeDef",
     "GetAlarmsRequestRequestTypeDef",
     "GetAutoSnapshotsRequestRequestTypeDef",
+    "GetBlueprintsRequestGetBlueprintsPaginateTypeDef",
     "GetBlueprintsRequestRequestTypeDef",
     "GetBucketAccessKeysRequestRequestTypeDef",
     "GetBucketBundlesRequestRequestTypeDef",
     "GetBucketMetricDataRequestRequestTypeDef",
     "MetricDatapointTypeDef",
     "GetBucketsRequestRequestTypeDef",
+    "GetBundlesRequestGetBundlesPaginateTypeDef",
     "GetBundlesRequestRequestTypeDef",
     "GetCertificatesRequestRequestTypeDef",
+    "GetCloudFormationStackRecordsRequestGetCloudFormationStackRecordsPaginateTypeDef",
     "GetCloudFormationStackRecordsRequestRequestTypeDef",
     "GetContactMethodsRequestRequestTypeDef",
+    "GetContainerAPIMetadataResultTypeDef",
     "GetContainerImagesRequestRequestTypeDef",
     "GetContainerLogRequestRequestTypeDef",
     "GetContainerServiceDeploymentsRequestRequestTypeDef",
     "GetContainerServiceMetricDataRequestRequestTypeDef",
     "GetContainerServicesRequestRequestTypeDef",
+    "GetCostEstimateRequestRequestTypeDef",
     "GetDiskRequestRequestTypeDef",
     "GetDiskSnapshotRequestRequestTypeDef",
+    "GetDiskSnapshotsRequestGetDiskSnapshotsPaginateTypeDef",
     "GetDiskSnapshotsRequestRequestTypeDef",
+    "GetDisksRequestGetDisksPaginateTypeDef",
     "GetDisksRequestRequestTypeDef",
     "GetDistributionLatestCacheResetRequestRequestTypeDef",
+    "GetDistributionLatestCacheResetResultTypeDef",
     "GetDistributionMetricDataRequestRequestTypeDef",
     "GetDistributionsRequestRequestTypeDef",
     "GetDomainRequestRequestTypeDef",
+    "GetDomainsRequestGetDomainsPaginateTypeDef",
     "GetDomainsRequestRequestTypeDef",
+    "GetExportSnapshotRecordsRequestGetExportSnapshotRecordsPaginateTypeDef",
     "GetExportSnapshotRecordsRequestRequestTypeDef",
     "GetInstanceAccessDetailsRequestRequestTypeDef",
     "GetInstanceMetricDataRequestRequestTypeDef",
     "GetInstancePortStatesRequestRequestTypeDef",
     "InstancePortStateTypeDef",
     "GetInstanceRequestRequestTypeDef",
     "GetInstanceSnapshotRequestRequestTypeDef",
+    "GetInstanceSnapshotsRequestGetInstanceSnapshotsPaginateTypeDef",
     "GetInstanceSnapshotsRequestRequestTypeDef",
     "GetInstanceStateRequestRequestTypeDef",
     "InstanceStateTypeDef",
+    "GetInstancesRequestGetInstancesPaginateTypeDef",
     "GetInstancesRequestRequestTypeDef",
     "GetKeyPairRequestRequestTypeDef",
+    "GetKeyPairsRequestGetKeyPairsPaginateTypeDef",
     "GetKeyPairsRequestRequestTypeDef",
     "GetLoadBalancerMetricDataRequestRequestTypeDef",
     "GetLoadBalancerRequestRequestTypeDef",
     "GetLoadBalancerTlsCertificatesRequestRequestTypeDef",
     "GetLoadBalancerTlsPoliciesRequestRequestTypeDef",
     "LoadBalancerTlsPolicyTypeDef",
+    "GetLoadBalancersRequestGetLoadBalancersPaginateTypeDef",
     "GetLoadBalancersRequestRequestTypeDef",
     "GetOperationRequestRequestTypeDef",
     "GetOperationsForResourceRequestRequestTypeDef",
+    "GetOperationsRequestGetOperationsPaginateTypeDef",
     "GetOperationsRequestRequestTypeDef",
     "GetRegionsRequestRequestTypeDef",
+    "GetRelationalDatabaseBlueprintsRequestGetRelationalDatabaseBlueprintsPaginateTypeDef",
     "GetRelationalDatabaseBlueprintsRequestRequestTypeDef",
     "RelationalDatabaseBlueprintTypeDef",
+    "GetRelationalDatabaseBundlesRequestGetRelationalDatabaseBundlesPaginateTypeDef",
     "GetRelationalDatabaseBundlesRequestRequestTypeDef",
     "RelationalDatabaseBundleTypeDef",
+    "GetRelationalDatabaseEventsRequestGetRelationalDatabaseEventsPaginateTypeDef",
     "GetRelationalDatabaseEventsRequestRequestTypeDef",
     "RelationalDatabaseEventTypeDef",
     "GetRelationalDatabaseLogEventsRequestRequestTypeDef",
     "LogEventTypeDef",
     "GetRelationalDatabaseLogStreamsRequestRequestTypeDef",
+    "GetRelationalDatabaseLogStreamsResultTypeDef",
     "GetRelationalDatabaseMasterUserPasswordRequestRequestTypeDef",
+    "GetRelationalDatabaseMasterUserPasswordResultTypeDef",
     "GetRelationalDatabaseMetricDataRequestRequestTypeDef",
+    "GetRelationalDatabaseParametersRequestGetRelationalDatabaseParametersPaginateTypeDef",
     "GetRelationalDatabaseParametersRequestRequestTypeDef",
     "RelationalDatabaseParameterTypeDef",
     "GetRelationalDatabaseRequestRequestTypeDef",
     "GetRelationalDatabaseSnapshotRequestRequestTypeDef",
+    "GetRelationalDatabaseSnapshotsRequestGetRelationalDatabaseSnapshotsPaginateTypeDef",
     "GetRelationalDatabaseSnapshotsRequestRequestTypeDef",
+    "GetRelationalDatabasesRequestGetRelationalDatabasesPaginateTypeDef",
     "GetRelationalDatabasesRequestRequestTypeDef",
     "GetStaticIpRequestRequestTypeDef",
+    "GetStaticIpsRequestGetStaticIpsPaginateTypeDef",
     "GetStaticIpsRequestRequestTypeDef",
     "HostKeyAttributesTypeDef",
     "ImportKeyPairRequestRequestTypeDef",
     "PasswordDataTypeDef",
     "InstanceHealthSummaryTypeDef",
     "InstanceMetadataOptionsTypeDef",
     "InstancePortInfoTypeDef",
     "MonthlyTransferTypeDef",
+    "IsVpcPeeredResultTypeDef",
     "OriginTypeDef",
     "LoadBalancerTlsCertificateDnsRecordCreationStateTypeDef",
     "LoadBalancerTlsCertificateDomainValidationOptionTypeDef",
     "LoadBalancerTlsCertificateSummaryTypeDef",
     "NameServersUpdateStateTypeDef",
+    "PaginatorConfigTypeDef",
     "PendingMaintenanceActionTypeDef",
     "PendingModifiedRelationalDatabaseValuesTypeDef",
     "PutAlarmRequestRequestTypeDef",
     "R53HostedZoneDeletionStateTypeDef",
     "RebootInstanceRequestRequestTypeDef",
     "RebootRelationalDatabaseRequestRequestTypeDef",
     "RegisterContainerImageRequestRequestTypeDef",
     "RelationalDatabaseEndpointTypeDef",
     "RelationalDatabaseHardwareTypeDef",
     "ReleaseStaticIpRequestRequestTypeDef",
     "ResetDistributionCacheRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "SendContactMethodVerificationRequestRequestTypeDef",
     "SetIpAddressTypeRequestRequestTypeDef",
     "SetResourceAccessForBucketRequestRequestTypeDef",
+    "StartGUISessionRequestRequestTypeDef",
     "StartInstanceRequestRequestTypeDef",
     "StartRelationalDatabaseRequestRequestTypeDef",
+    "StopGUISessionRequestRequestTypeDef",
     "StopInstanceRequestRequestTypeDef",
     "StopRelationalDatabaseRequestRequestTypeDef",
     "TestAlarmRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateBucketBundleRequestRequestTypeDef",
     "UpdateDistributionBundleRequestRequestTypeDef",
     "UpdateInstanceMetadataOptionsRequestRequestTypeDef",
@@ -284,21 +323,14 @@
     "UpdateRelationalDatabaseRequestRequestTypeDef",
     "AccessKeyTypeDef",
     "AddOnRequestTypeDef",
     "AlarmTypeDef",
     "ContactMethodTypeDef",
     "OperationTypeDef",
     "StaticIpTypeDef",
-    "DownloadDefaultKeyPairResultTypeDef",
-    "GetActiveNamesResultTypeDef",
-    "GetContainerAPIMetadataResultTypeDef",
-    "GetDistributionLatestCacheResetResultTypeDef",
-    "GetRelationalDatabaseLogStreamsResultTypeDef",
-    "GetRelationalDatabaseMasterUserPasswordResultTypeDef",
-    "IsVpcPeeredResultTypeDef",
     "AutoSnapshotDetailsTypeDef",
     "RegionTypeDef",
     "GetBlueprintsResultTypeDef",
     "UpdateBucketRequestRequestTypeDef",
     "GetBucketBundlesResultTypeDef",
     "BucketTypeDef",
     "CreateBucketRequestRequestTypeDef",
@@ -332,37 +364,19 @@
     "GetContainerLogResultTypeDef",
     "GetContainerServicePowersResultTypeDef",
     "CreateContainerServiceRegistryLoginResultTypeDef",
     "CreateCloudFormationStackRequestRequestTypeDef",
     "CreateDomainEntryRequestRequestTypeDef",
     "DeleteDomainEntryRequestRequestTypeDef",
     "UpdateDomainEntryRequestRequestTypeDef",
+    "CreateGUISessionAccessDetailsResultTypeDef",
     "InstanceSnapshotInfoTypeDef",
     "GetDistributionBundlesResultTypeDef",
     "DomainValidationRecordTypeDef",
-    "GetActiveNamesRequestGetActiveNamesPaginateTypeDef",
-    "GetBlueprintsRequestGetBlueprintsPaginateTypeDef",
-    "GetBundlesRequestGetBundlesPaginateTypeDef",
-    "GetCloudFormationStackRecordsRequestGetCloudFormationStackRecordsPaginateTypeDef",
-    "GetDiskSnapshotsRequestGetDiskSnapshotsPaginateTypeDef",
-    "GetDisksRequestGetDisksPaginateTypeDef",
-    "GetDomainsRequestGetDomainsPaginateTypeDef",
-    "GetExportSnapshotRecordsRequestGetExportSnapshotRecordsPaginateTypeDef",
-    "GetInstanceSnapshotsRequestGetInstanceSnapshotsPaginateTypeDef",
-    "GetInstancesRequestGetInstancesPaginateTypeDef",
-    "GetKeyPairsRequestGetKeyPairsPaginateTypeDef",
-    "GetLoadBalancersRequestGetLoadBalancersPaginateTypeDef",
-    "GetOperationsRequestGetOperationsPaginateTypeDef",
-    "GetRelationalDatabaseBlueprintsRequestGetRelationalDatabaseBlueprintsPaginateTypeDef",
-    "GetRelationalDatabaseBundlesRequestGetRelationalDatabaseBundlesPaginateTypeDef",
-    "GetRelationalDatabaseEventsRequestGetRelationalDatabaseEventsPaginateTypeDef",
-    "GetRelationalDatabaseParametersRequestGetRelationalDatabaseParametersPaginateTypeDef",
-    "GetRelationalDatabaseSnapshotsRequestGetRelationalDatabaseSnapshotsPaginateTypeDef",
-    "GetRelationalDatabasesRequestGetRelationalDatabasesPaginateTypeDef",
-    "GetStaticIpsRequestGetStaticIpsPaginateTypeDef",
+    "EstimateByTimeTypeDef",
     "GetBucketMetricDataResultTypeDef",
     "GetContainerServiceMetricDataResultTypeDef",
     "GetDistributionMetricDataResultTypeDef",
     "GetInstanceMetricDataResultTypeDef",
     "GetLoadBalancerMetricDataResultTypeDef",
     "GetRelationalDatabaseMetricDataResultTypeDef",
     "GetInstancePortStatesResultTypeDef",
@@ -450,16 +464,18 @@
     "RebootInstanceResultTypeDef",
     "RebootRelationalDatabaseResultTypeDef",
     "ReleaseStaticIpResultTypeDef",
     "ResetDistributionCacheResultTypeDef",
     "SendContactMethodVerificationResultTypeDef",
     "SetIpAddressTypeResultTypeDef",
     "SetResourceAccessForBucketResultTypeDef",
+    "StartGUISessionResultTypeDef",
     "StartInstanceResultTypeDef",
     "StartRelationalDatabaseResultTypeDef",
+    "StopGUISessionResultTypeDef",
     "StopInstanceResultTypeDef",
     "StopRelationalDatabaseResultTypeDef",
     "TagResourceResultTypeDef",
     "TestAlarmResultTypeDef",
     "UnpeerVpcResultTypeDef",
     "UntagResourceResultTypeDef",
     "UpdateBucketBundleResultTypeDef",
@@ -494,14 +510,15 @@
     "GetCloudFormationStackRecordsResultTypeDef",
     "UpdateContainerServiceRequestRequestTypeDef",
     "ContainerServiceDeploymentTypeDef",
     "ContainerServiceDeploymentRequestTypeDef",
     "CreateContainerServiceDeploymentRequestRequestTypeDef",
     "ExportSnapshotRecordSourceInfoTypeDef",
     "RenewalSummaryTypeDef",
+    "CostEstimateTypeDef",
     "GetInstanceAccessDetailsResultTypeDef",
     "LoadBalancerTlsCertificateTypeDef",
     "GetLoadBalancerResultTypeDef",
     "GetLoadBalancersResultTypeDef",
     "DomainTypeDef",
     "GetRelationalDatabaseResultTypeDef",
     "GetRelationalDatabasesResultTypeDef",
@@ -511,25 +528,27 @@
     "CreateDistributionResultTypeDef",
     "GetDistributionsResultTypeDef",
     "ContainerServiceTypeDef",
     "GetContainerServiceDeploymentsResultTypeDef",
     "CreateContainerServiceRequestRequestTypeDef",
     "ExportSnapshotRecordTypeDef",
     "CertificateTypeDef",
+    "ResourceBudgetEstimateTypeDef",
     "GetLoadBalancerTlsCertificatesResultTypeDef",
     "GetDomainResultTypeDef",
     "GetDomainsResultTypeDef",
     "GetInstanceResultTypeDef",
     "GetInstancesResultTypeDef",
     "ContainerServicesListResultTypeDef",
     "CreateContainerServiceDeploymentResultTypeDef",
     "CreateContainerServiceResultTypeDef",
     "UpdateContainerServiceResultTypeDef",
     "GetExportSnapshotRecordsResultTypeDef",
     "CertificateSummaryTypeDef",
+    "GetCostEstimateResultTypeDef",
     "CreateCertificateResultTypeDef",
     "GetCertificatesResultTypeDef",
 )
 
 AccessKeyLastUsedTypeDef = TypedDict(
     "AccessKeyLastUsedTypeDef",
     {
@@ -564,21 +583,32 @@
     "AutoSnapshotAddOnRequestTypeDef",
     {
         "snapshotTimeOfDay": str,
     },
     total=False,
 )
 
+StopInstanceOnIdleRequestTypeDef = TypedDict(
+    "StopInstanceOnIdleRequestTypeDef",
+    {
+        "threshold": str,
+        "duration": str,
+    },
+    total=False,
+)
+
 AddOnTypeDef = TypedDict(
     "AddOnTypeDef",
     {
         "name": str,
         "status": str,
         "snapshotTimeOfDay": str,
         "nextSnapshotTimeOfDay": str,
+        "threshold": str,
+        "duration": str,
     },
     total=False,
 )
 
 MonitoredResourceInfoTypeDef = TypedDict(
     "MonitoredResourceInfoTypeDef",
     {
@@ -601,41 +631,44 @@
 AllocateStaticIpRequestRequestTypeDef = TypedDict(
     "AllocateStaticIpRequestRequestTypeDef",
     {
         "staticIpName": str,
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
 AttachCertificateToDistributionRequestRequestTypeDef = TypedDict(
     "AttachCertificateToDistributionRequestRequestTypeDef",
     {
         "distributionName": str,
         "certificateName": str,
     },
 )
 
-AttachDiskRequestRequestTypeDef = TypedDict(
-    "AttachDiskRequestRequestTypeDef",
+_RequiredAttachDiskRequestRequestTypeDef = TypedDict(
+    "_RequiredAttachDiskRequestRequestTypeDef",
     {
         "diskName": str,
         "instanceName": str,
         "diskPath": str,
     },
 )
+_OptionalAttachDiskRequestRequestTypeDef = TypedDict(
+    "_OptionalAttachDiskRequestRequestTypeDef",
+    {
+        "autoMounting": bool,
+    },
+    total=False,
+)
+
+
+class AttachDiskRequestRequestTypeDef(
+    _RequiredAttachDiskRequestRequestTypeDef, _OptionalAttachDiskRequestRequestTypeDef
+):
+    pass
+
 
 AttachInstancesToLoadBalancerRequestRequestTypeDef = TypedDict(
     "AttachInstancesToLoadBalancerRequestRequestTypeDef",
     {
         "loadBalancerName": str,
         "instanceNames": Sequence[str],
     },
@@ -686,14 +719,15 @@
         "isActive": bool,
         "minPower": int,
         "version": str,
         "versionCode": str,
         "productUrl": str,
         "licenseUrl": str,
         "platform": InstancePlatformType,
+        "appCategory": Literal["LfR"],
     },
     total=False,
 )
 
 _RequiredBucketAccessLogConfigTypeDef = TypedDict(
     "_RequiredBucketAccessLogConfigTypeDef",
     {
@@ -705,19 +739,21 @@
     {
         "destination": str,
         "prefix": str,
     },
     total=False,
 )
 
+
 class BucketAccessLogConfigTypeDef(
     _RequiredBucketAccessLogConfigTypeDef, _OptionalBucketAccessLogConfigTypeDef
 ):
     pass
 
+
 BucketBundleTypeDef = TypedDict(
     "BucketBundleTypeDef",
     {
         "bundleId": str,
         "name": str,
         "price": float,
         "storagePerMonthInGb": int,
@@ -764,14 +800,15 @@
         "instanceType": str,
         "isActive": bool,
         "name": str,
         "power": int,
         "ramSizeInGb": float,
         "transferPerMonthInGb": int,
         "supportedPlatforms": List[InstancePlatformType],
+        "supportedAppCategories": List[Literal["LfR"]],
     },
     total=False,
 )
 
 CacheBehaviorPerPathTypeDef = TypedDict(
     "CacheBehaviorPerPathTypeDef",
     {
@@ -955,19 +992,21 @@
         "sourceResourceName": str,
         "restoreDate": str,
         "useLatestRestorableAutoSnapshot": bool,
     },
     total=False,
 )
 
+
 class CopySnapshotRequestRequestTypeDef(
     _RequiredCopySnapshotRequestRequestTypeDef, _OptionalCopySnapshotRequestRequestTypeDef
 ):
     pass
 
+
 CreateBucketAccessKeyRequestRequestTypeDef = TypedDict(
     "CreateBucketAccessKeyRequestRequestTypeDef",
     {
         "bucketName": str,
     },
 )
 
@@ -984,17 +1023,19 @@
     "_OptionalInstanceEntryTypeDef",
     {
         "userData": str,
     },
     total=False,
 )
 
+
 class InstanceEntryTypeDef(_RequiredInstanceEntryTypeDef, _OptionalInstanceEntryTypeDef):
     pass
 
+
 CreateContactMethodRequestRequestTypeDef = TypedDict(
     "CreateContactMethodRequestRequestTypeDef",
     {
         "protocol": ContactProtocolType,
         "contactEndpoint": str,
     },
 )
@@ -1018,14 +1059,31 @@
         "isAlias": bool,
         "type": str,
         "options": Mapping[str, str],
     },
     total=False,
 )
 
+CreateGUISessionAccessDetailsRequestRequestTypeDef = TypedDict(
+    "CreateGUISessionAccessDetailsRequestRequestTypeDef",
+    {
+        "resourceName": str,
+    },
+)
+
+SessionTypeDef = TypedDict(
+    "SessionTypeDef",
+    {
+        "name": str,
+        "url": str,
+        "isPrimary": bool,
+    },
+    total=False,
+)
+
 DiskMapTypeDef = TypedDict(
     "DiskMapTypeDef",
     {
         "originalDiskPath": str,
         "newDiskName": str,
     },
     total=False,
@@ -1064,19 +1122,21 @@
     "_OptionalDeleteBucketRequestRequestTypeDef",
     {
         "forceDelete": bool,
     },
     total=False,
 )
 
+
 class DeleteBucketRequestRequestTypeDef(
     _RequiredDeleteBucketRequestRequestTypeDef, _OptionalDeleteBucketRequestRequestTypeDef
 ):
     pass
 
+
 DeleteCertificateRequestRequestTypeDef = TypedDict(
     "DeleteCertificateRequestRequestTypeDef",
     {
         "certificateName": str,
     },
 )
 
@@ -1112,19 +1172,21 @@
     "_OptionalDeleteDiskRequestRequestTypeDef",
     {
         "forceDeleteAddOns": bool,
     },
     total=False,
 )
 
+
 class DeleteDiskRequestRequestTypeDef(
     _RequiredDeleteDiskRequestRequestTypeDef, _OptionalDeleteDiskRequestRequestTypeDef
 ):
     pass
 
+
 DeleteDiskSnapshotRequestRequestTypeDef = TypedDict(
     "DeleteDiskSnapshotRequestRequestTypeDef",
     {
         "diskSnapshotName": str,
     },
 )
 
@@ -1153,19 +1215,21 @@
     "_OptionalDeleteInstanceRequestRequestTypeDef",
     {
         "forceDeleteAddOns": bool,
     },
     total=False,
 )
 
+
 class DeleteInstanceRequestRequestTypeDef(
     _RequiredDeleteInstanceRequestRequestTypeDef, _OptionalDeleteInstanceRequestRequestTypeDef
 ):
     pass
 
+
 DeleteInstanceSnapshotRequestRequestTypeDef = TypedDict(
     "DeleteInstanceSnapshotRequestRequestTypeDef",
     {
         "instanceSnapshotName": str,
     },
 )
 
@@ -1179,19 +1243,21 @@
     "_OptionalDeleteKeyPairRequestRequestTypeDef",
     {
         "expectedFingerprint": str,
     },
     total=False,
 )
 
+
 class DeleteKeyPairRequestRequestTypeDef(
     _RequiredDeleteKeyPairRequestRequestTypeDef, _OptionalDeleteKeyPairRequestRequestTypeDef
 ):
     pass
 
+
 DeleteKnownHostKeysRequestRequestTypeDef = TypedDict(
     "DeleteKnownHostKeysRequestRequestTypeDef",
     {
         "instanceName": str,
     },
 )
 
@@ -1213,20 +1279,22 @@
     "_OptionalDeleteLoadBalancerTlsCertificateRequestRequestTypeDef",
     {
         "force": bool,
     },
     total=False,
 )
 
+
 class DeleteLoadBalancerTlsCertificateRequestRequestTypeDef(
     _RequiredDeleteLoadBalancerTlsCertificateRequestRequestTypeDef,
     _OptionalDeleteLoadBalancerTlsCertificateRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredDeleteRelationalDatabaseRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteRelationalDatabaseRequestRequestTypeDef",
     {
         "relationalDatabaseName": str,
     },
 )
 _OptionalDeleteRelationalDatabaseRequestRequestTypeDef = TypedDict(
@@ -1234,20 +1302,22 @@
     {
         "skipFinalSnapshot": bool,
         "finalRelationalDatabaseSnapshotName": str,
     },
     total=False,
 )
 
+
 class DeleteRelationalDatabaseRequestRequestTypeDef(
     _RequiredDeleteRelationalDatabaseRequestRequestTypeDef,
     _OptionalDeleteRelationalDatabaseRequestRequestTypeDef,
 ):
     pass
 
+
 DeleteRelationalDatabaseSnapshotRequestRequestTypeDef = TypedDict(
     "DeleteRelationalDatabaseSnapshotRequestRequestTypeDef",
     {
         "relationalDatabaseSnapshotName": str,
     },
 )
 
@@ -1279,15 +1349,15 @@
         "staticIpName": str,
     },
 )
 
 DisableAddOnRequestRequestTypeDef = TypedDict(
     "DisableAddOnRequestRequestTypeDef",
     {
-        "addOnType": Literal["AutoSnapshot"],
+        "addOnType": AddOnTypeType,
         "resourceName": str,
     },
 )
 
 DiskInfoTypeDef = TypedDict(
     "DiskInfoTypeDef",
     {
@@ -1334,39 +1404,65 @@
         "name": str,
         "type": str,
         "value": str,
     },
     total=False,
 )
 
+DownloadDefaultKeyPairResultTypeDef = TypedDict(
+    "DownloadDefaultKeyPairResultTypeDef",
+    {
+        "publicKeyBase64": str,
+        "privateKeyBase64": str,
+        "createdAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+TimePeriodTypeDef = TypedDict(
+    "TimePeriodTypeDef",
+    {
+        "start": datetime,
+        "end": datetime,
+    },
+    total=False,
+)
+
 ExportSnapshotRequestRequestTypeDef = TypedDict(
     "ExportSnapshotRequestRequestTypeDef",
     {
         "sourceSnapshotName": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetActiveNamesRequestGetActiveNamesPaginateTypeDef = TypedDict(
+    "GetActiveNamesRequestGetActiveNamesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 GetActiveNamesRequestRequestTypeDef = TypedDict(
     "GetActiveNamesRequestRequestTypeDef",
     {
         "pageToken": str,
     },
     total=False,
 )
 
+GetActiveNamesResultTypeDef = TypedDict(
+    "GetActiveNamesResultTypeDef",
+    {
+        "activeNames": List[str],
+        "nextPageToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetAlarmsRequestRequestTypeDef = TypedDict(
     "GetAlarmsRequestRequestTypeDef",
     {
         "alarmName": str,
         "pageToken": str,
         "monitoredResourceName": str,
     },
@@ -1376,19 +1472,30 @@
 GetAutoSnapshotsRequestRequestTypeDef = TypedDict(
     "GetAutoSnapshotsRequestRequestTypeDef",
     {
         "resourceName": str,
     },
 )
 
+GetBlueprintsRequestGetBlueprintsPaginateTypeDef = TypedDict(
+    "GetBlueprintsRequestGetBlueprintsPaginateTypeDef",
+    {
+        "includeInactive": bool,
+        "appCategory": Literal["LfR"],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetBlueprintsRequestRequestTypeDef = TypedDict(
     "GetBlueprintsRequestRequestTypeDef",
     {
         "includeInactive": bool,
         "pageToken": str,
+        "appCategory": Literal["LfR"],
     },
     total=False,
 )
 
 GetBucketAccessKeysRequestRequestTypeDef = TypedDict(
     "GetBucketAccessKeysRequestRequestTypeDef",
     {
@@ -1437,29 +1544,49 @@
         "bucketName": str,
         "pageToken": str,
         "includeConnectedResources": bool,
     },
     total=False,
 )
 
+GetBundlesRequestGetBundlesPaginateTypeDef = TypedDict(
+    "GetBundlesRequestGetBundlesPaginateTypeDef",
+    {
+        "includeInactive": bool,
+        "appCategory": Literal["LfR"],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetBundlesRequestRequestTypeDef = TypedDict(
     "GetBundlesRequestRequestTypeDef",
     {
         "includeInactive": bool,
         "pageToken": str,
+        "appCategory": Literal["LfR"],
     },
     total=False,
 )
 
 GetCertificatesRequestRequestTypeDef = TypedDict(
     "GetCertificatesRequestRequestTypeDef",
     {
         "certificateStatuses": Sequence[CertificateStatusType],
         "includeCertificateDetails": bool,
         "certificateName": str,
+        "pageToken": str,
+    },
+    total=False,
+)
+
+GetCloudFormationStackRecordsRequestGetCloudFormationStackRecordsPaginateTypeDef = TypedDict(
+    "GetCloudFormationStackRecordsRequestGetCloudFormationStackRecordsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 GetCloudFormationStackRecordsRequestRequestTypeDef = TypedDict(
     "GetCloudFormationStackRecordsRequestRequestTypeDef",
     {
@@ -1472,14 +1599,22 @@
     "GetContactMethodsRequestRequestTypeDef",
     {
         "protocols": Sequence[ContactProtocolType],
     },
     total=False,
 )
 
+GetContainerAPIMetadataResultTypeDef = TypedDict(
+    "GetContainerAPIMetadataResultTypeDef",
+    {
+        "metadata": List[Dict[str, str]],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetContainerImagesRequestRequestTypeDef = TypedDict(
     "GetContainerImagesRequestRequestTypeDef",
     {
         "serviceName": str,
     },
 )
 
@@ -1497,19 +1632,21 @@
         "endTime": Union[datetime, str],
         "filterPattern": str,
         "pageToken": str,
     },
     total=False,
 )
 
+
 class GetContainerLogRequestRequestTypeDef(
     _RequiredGetContainerLogRequestRequestTypeDef, _OptionalGetContainerLogRequestRequestTypeDef
 ):
     pass
 
+
 GetContainerServiceDeploymentsRequestRequestTypeDef = TypedDict(
     "GetContainerServiceDeploymentsRequestRequestTypeDef",
     {
         "serviceName": str,
     },
 )
 
@@ -1529,36 +1666,61 @@
     "GetContainerServicesRequestRequestTypeDef",
     {
         "serviceName": str,
     },
     total=False,
 )
 
+GetCostEstimateRequestRequestTypeDef = TypedDict(
+    "GetCostEstimateRequestRequestTypeDef",
+    {
+        "resourceName": str,
+        "startTime": Union[datetime, str],
+        "endTime": Union[datetime, str],
+    },
+)
+
 GetDiskRequestRequestTypeDef = TypedDict(
     "GetDiskRequestRequestTypeDef",
     {
         "diskName": str,
     },
 )
 
 GetDiskSnapshotRequestRequestTypeDef = TypedDict(
     "GetDiskSnapshotRequestRequestTypeDef",
     {
         "diskSnapshotName": str,
     },
 )
 
+GetDiskSnapshotsRequestGetDiskSnapshotsPaginateTypeDef = TypedDict(
+    "GetDiskSnapshotsRequestGetDiskSnapshotsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetDiskSnapshotsRequestRequestTypeDef = TypedDict(
     "GetDiskSnapshotsRequestRequestTypeDef",
     {
         "pageToken": str,
     },
     total=False,
 )
 
+GetDisksRequestGetDisksPaginateTypeDef = TypedDict(
+    "GetDisksRequestGetDisksPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetDisksRequestRequestTypeDef = TypedDict(
     "GetDisksRequestRequestTypeDef",
     {
         "pageToken": str,
     },
     total=False,
 )
@@ -1567,14 +1729,23 @@
     "GetDistributionLatestCacheResetRequestRequestTypeDef",
     {
         "distributionName": str,
     },
     total=False,
 )
 
+GetDistributionLatestCacheResetResultTypeDef = TypedDict(
+    "GetDistributionLatestCacheResetResultTypeDef",
+    {
+        "status": str,
+        "createTime": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetDistributionMetricDataRequestRequestTypeDef = TypedDict(
     "GetDistributionMetricDataRequestRequestTypeDef",
     {
         "distributionName": str,
         "metricName": DistributionMetricNameType,
         "startTime": Union[datetime, str],
         "endTime": Union[datetime, str],
@@ -1596,22 +1767,38 @@
 GetDomainRequestRequestTypeDef = TypedDict(
     "GetDomainRequestRequestTypeDef",
     {
         "domainName": str,
     },
 )
 
+GetDomainsRequestGetDomainsPaginateTypeDef = TypedDict(
+    "GetDomainsRequestGetDomainsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetDomainsRequestRequestTypeDef = TypedDict(
     "GetDomainsRequestRequestTypeDef",
     {
         "pageToken": str,
     },
     total=False,
 )
 
+GetExportSnapshotRecordsRequestGetExportSnapshotRecordsPaginateTypeDef = TypedDict(
+    "GetExportSnapshotRecordsRequestGetExportSnapshotRecordsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetExportSnapshotRecordsRequestRequestTypeDef = TypedDict(
     "GetExportSnapshotRecordsRequestRequestTypeDef",
     {
         "pageToken": str,
     },
     total=False,
 )
@@ -1626,20 +1813,22 @@
     "_OptionalGetInstanceAccessDetailsRequestRequestTypeDef",
     {
         "protocol": InstanceAccessProtocolType,
     },
     total=False,
 )
 
+
 class GetInstanceAccessDetailsRequestRequestTypeDef(
     _RequiredGetInstanceAccessDetailsRequestRequestTypeDef,
     _OptionalGetInstanceAccessDetailsRequestRequestTypeDef,
 ):
     pass
 
+
 GetInstanceMetricDataRequestRequestTypeDef = TypedDict(
     "GetInstanceMetricDataRequestRequestTypeDef",
     {
         "instanceName": str,
         "metricName": InstanceMetricNameType,
         "period": int,
         "startTime": Union[datetime, str],
@@ -1680,14 +1869,22 @@
 GetInstanceSnapshotRequestRequestTypeDef = TypedDict(
     "GetInstanceSnapshotRequestRequestTypeDef",
     {
         "instanceSnapshotName": str,
     },
 )
 
+GetInstanceSnapshotsRequestGetInstanceSnapshotsPaginateTypeDef = TypedDict(
+    "GetInstanceSnapshotsRequestGetInstanceSnapshotsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetInstanceSnapshotsRequestRequestTypeDef = TypedDict(
     "GetInstanceSnapshotsRequestRequestTypeDef",
     {
         "pageToken": str,
     },
     total=False,
 )
@@ -1704,14 +1901,22 @@
     {
         "code": int,
         "name": str,
     },
     total=False,
 )
 
+GetInstancesRequestGetInstancesPaginateTypeDef = TypedDict(
+    "GetInstancesRequestGetInstancesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetInstancesRequestRequestTypeDef = TypedDict(
     "GetInstancesRequestRequestTypeDef",
     {
         "pageToken": str,
     },
     total=False,
 )
@@ -1719,14 +1924,23 @@
 GetKeyPairRequestRequestTypeDef = TypedDict(
     "GetKeyPairRequestRequestTypeDef",
     {
         "keyPairName": str,
     },
 )
 
+GetKeyPairsRequestGetKeyPairsPaginateTypeDef = TypedDict(
+    "GetKeyPairsRequestGetKeyPairsPaginateTypeDef",
+    {
+        "includeDefaultKeyPair": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetKeyPairsRequestRequestTypeDef = TypedDict(
     "GetKeyPairsRequestRequestTypeDef",
     {
         "pageToken": str,
         "includeDefaultKeyPair": bool,
     },
     total=False,
@@ -1775,14 +1989,22 @@
         "description": str,
         "protocols": List[str],
         "ciphers": List[str],
     },
     total=False,
 )
 
+GetLoadBalancersRequestGetLoadBalancersPaginateTypeDef = TypedDict(
+    "GetLoadBalancersRequestGetLoadBalancersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetLoadBalancersRequestRequestTypeDef = TypedDict(
     "GetLoadBalancersRequestRequestTypeDef",
     {
         "pageToken": str,
     },
     total=False,
 )
@@ -1804,20 +2026,30 @@
     "_OptionalGetOperationsForResourceRequestRequestTypeDef",
     {
         "pageToken": str,
     },
     total=False,
 )
 
+
 class GetOperationsForResourceRequestRequestTypeDef(
     _RequiredGetOperationsForResourceRequestRequestTypeDef,
     _OptionalGetOperationsForResourceRequestRequestTypeDef,
 ):
     pass
 
+
+GetOperationsRequestGetOperationsPaginateTypeDef = TypedDict(
+    "GetOperationsRequestGetOperationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetOperationsRequestRequestTypeDef = TypedDict(
     "GetOperationsRequestRequestTypeDef",
     {
         "pageToken": str,
     },
     total=False,
 )
@@ -1827,14 +2059,22 @@
     {
         "includeAvailabilityZones": bool,
         "includeRelationalDatabaseAvailabilityZones": bool,
     },
     total=False,
 )
 
+GetRelationalDatabaseBlueprintsRequestGetRelationalDatabaseBlueprintsPaginateTypeDef = TypedDict(
+    "GetRelationalDatabaseBlueprintsRequestGetRelationalDatabaseBlueprintsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetRelationalDatabaseBlueprintsRequestRequestTypeDef = TypedDict(
     "GetRelationalDatabaseBlueprintsRequestRequestTypeDef",
     {
         "pageToken": str,
     },
     total=False,
 )
@@ -1848,14 +2088,23 @@
         "engineDescription": str,
         "engineVersionDescription": str,
         "isEngineDefault": bool,
     },
     total=False,
 )
 
+GetRelationalDatabaseBundlesRequestGetRelationalDatabaseBundlesPaginateTypeDef = TypedDict(
+    "GetRelationalDatabaseBundlesRequestGetRelationalDatabaseBundlesPaginateTypeDef",
+    {
+        "includeInactive": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetRelationalDatabaseBundlesRequestRequestTypeDef = TypedDict(
     "GetRelationalDatabaseBundlesRequestRequestTypeDef",
     {
         "pageToken": str,
         "includeInactive": bool,
     },
     total=False,
@@ -1873,14 +2122,37 @@
         "cpuCount": int,
         "isEncrypted": bool,
         "isActive": bool,
     },
     total=False,
 )
 
+_RequiredGetRelationalDatabaseEventsRequestGetRelationalDatabaseEventsPaginateTypeDef = TypedDict(
+    "_RequiredGetRelationalDatabaseEventsRequestGetRelationalDatabaseEventsPaginateTypeDef",
+    {
+        "relationalDatabaseName": str,
+    },
+)
+_OptionalGetRelationalDatabaseEventsRequestGetRelationalDatabaseEventsPaginateTypeDef = TypedDict(
+    "_OptionalGetRelationalDatabaseEventsRequestGetRelationalDatabaseEventsPaginateTypeDef",
+    {
+        "durationInMinutes": int,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetRelationalDatabaseEventsRequestGetRelationalDatabaseEventsPaginateTypeDef(
+    _RequiredGetRelationalDatabaseEventsRequestGetRelationalDatabaseEventsPaginateTypeDef,
+    _OptionalGetRelationalDatabaseEventsRequestGetRelationalDatabaseEventsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetRelationalDatabaseEventsRequestRequestTypeDef = TypedDict(
     "_RequiredGetRelationalDatabaseEventsRequestRequestTypeDef",
     {
         "relationalDatabaseName": str,
     },
 )
 _OptionalGetRelationalDatabaseEventsRequestRequestTypeDef = TypedDict(
@@ -1888,20 +2160,22 @@
     {
         "durationInMinutes": int,
         "pageToken": str,
     },
     total=False,
 )
 
+
 class GetRelationalDatabaseEventsRequestRequestTypeDef(
     _RequiredGetRelationalDatabaseEventsRequestRequestTypeDef,
     _OptionalGetRelationalDatabaseEventsRequestRequestTypeDef,
 ):
     pass
 
+
 RelationalDatabaseEventTypeDef = TypedDict(
     "RelationalDatabaseEventTypeDef",
     {
         "resource": str,
         "createdAt": datetime,
         "message": str,
         "eventCategories": List[str],
@@ -1923,20 +2197,22 @@
         "endTime": Union[datetime, str],
         "startFromHead": bool,
         "pageToken": str,
     },
     total=False,
 )
 
+
 class GetRelationalDatabaseLogEventsRequestRequestTypeDef(
     _RequiredGetRelationalDatabaseLogEventsRequestRequestTypeDef,
     _OptionalGetRelationalDatabaseLogEventsRequestRequestTypeDef,
 ):
     pass
 
+
 LogEventTypeDef = TypedDict(
     "LogEventTypeDef",
     {
         "createdAt": datetime,
         "message": str,
     },
     total=False,
@@ -1945,67 +2221,110 @@
 GetRelationalDatabaseLogStreamsRequestRequestTypeDef = TypedDict(
     "GetRelationalDatabaseLogStreamsRequestRequestTypeDef",
     {
         "relationalDatabaseName": str,
     },
 )
 
+GetRelationalDatabaseLogStreamsResultTypeDef = TypedDict(
+    "GetRelationalDatabaseLogStreamsResultTypeDef",
+    {
+        "logStreams": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGetRelationalDatabaseMasterUserPasswordRequestRequestTypeDef = TypedDict(
     "_RequiredGetRelationalDatabaseMasterUserPasswordRequestRequestTypeDef",
     {
         "relationalDatabaseName": str,
     },
 )
 _OptionalGetRelationalDatabaseMasterUserPasswordRequestRequestTypeDef = TypedDict(
     "_OptionalGetRelationalDatabaseMasterUserPasswordRequestRequestTypeDef",
     {
         "passwordVersion": RelationalDatabasePasswordVersionType,
     },
     total=False,
 )
 
+
 class GetRelationalDatabaseMasterUserPasswordRequestRequestTypeDef(
     _RequiredGetRelationalDatabaseMasterUserPasswordRequestRequestTypeDef,
     _OptionalGetRelationalDatabaseMasterUserPasswordRequestRequestTypeDef,
 ):
     pass
 
+
+GetRelationalDatabaseMasterUserPasswordResultTypeDef = TypedDict(
+    "GetRelationalDatabaseMasterUserPasswordResultTypeDef",
+    {
+        "masterUserPassword": str,
+        "createdAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetRelationalDatabaseMetricDataRequestRequestTypeDef = TypedDict(
     "GetRelationalDatabaseMetricDataRequestRequestTypeDef",
     {
         "relationalDatabaseName": str,
         "metricName": RelationalDatabaseMetricNameType,
         "period": int,
         "startTime": Union[datetime, str],
         "endTime": Union[datetime, str],
         "unit": MetricUnitType,
         "statistics": Sequence[MetricStatisticType],
     },
 )
 
+_RequiredGetRelationalDatabaseParametersRequestGetRelationalDatabaseParametersPaginateTypeDef = TypedDict(
+    "_RequiredGetRelationalDatabaseParametersRequestGetRelationalDatabaseParametersPaginateTypeDef",
+    {
+        "relationalDatabaseName": str,
+    },
+)
+_OptionalGetRelationalDatabaseParametersRequestGetRelationalDatabaseParametersPaginateTypeDef = TypedDict(
+    "_OptionalGetRelationalDatabaseParametersRequestGetRelationalDatabaseParametersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class GetRelationalDatabaseParametersRequestGetRelationalDatabaseParametersPaginateTypeDef(
+    _RequiredGetRelationalDatabaseParametersRequestGetRelationalDatabaseParametersPaginateTypeDef,
+    _OptionalGetRelationalDatabaseParametersRequestGetRelationalDatabaseParametersPaginateTypeDef,
+):
+    pass
+
+
 _RequiredGetRelationalDatabaseParametersRequestRequestTypeDef = TypedDict(
     "_RequiredGetRelationalDatabaseParametersRequestRequestTypeDef",
     {
         "relationalDatabaseName": str,
     },
 )
 _OptionalGetRelationalDatabaseParametersRequestRequestTypeDef = TypedDict(
     "_OptionalGetRelationalDatabaseParametersRequestRequestTypeDef",
     {
         "pageToken": str,
     },
     total=False,
 )
 
+
 class GetRelationalDatabaseParametersRequestRequestTypeDef(
     _RequiredGetRelationalDatabaseParametersRequestRequestTypeDef,
     _OptionalGetRelationalDatabaseParametersRequestRequestTypeDef,
 ):
     pass
 
+
 RelationalDatabaseParameterTypeDef = TypedDict(
     "RelationalDatabaseParameterTypeDef",
     {
         "allowedValues": str,
         "applyMethod": str,
         "applyType": str,
         "dataType": str,
@@ -2027,22 +2346,38 @@
 GetRelationalDatabaseSnapshotRequestRequestTypeDef = TypedDict(
     "GetRelationalDatabaseSnapshotRequestRequestTypeDef",
     {
         "relationalDatabaseSnapshotName": str,
     },
 )
 
+GetRelationalDatabaseSnapshotsRequestGetRelationalDatabaseSnapshotsPaginateTypeDef = TypedDict(
+    "GetRelationalDatabaseSnapshotsRequestGetRelationalDatabaseSnapshotsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetRelationalDatabaseSnapshotsRequestRequestTypeDef = TypedDict(
     "GetRelationalDatabaseSnapshotsRequestRequestTypeDef",
     {
         "pageToken": str,
     },
     total=False,
 )
 
+GetRelationalDatabasesRequestGetRelationalDatabasesPaginateTypeDef = TypedDict(
+    "GetRelationalDatabasesRequestGetRelationalDatabasesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetRelationalDatabasesRequestRequestTypeDef = TypedDict(
     "GetRelationalDatabasesRequestRequestTypeDef",
     {
         "pageToken": str,
     },
     total=False,
 )
@@ -2050,14 +2385,22 @@
 GetStaticIpRequestRequestTypeDef = TypedDict(
     "GetStaticIpRequestRequestTypeDef",
     {
         "staticIpName": str,
     },
 )
 
+GetStaticIpsRequestGetStaticIpsPaginateTypeDef = TypedDict(
+    "GetStaticIpsRequestGetStaticIpsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 GetStaticIpsRequestRequestTypeDef = TypedDict(
     "GetStaticIpsRequestRequestTypeDef",
     {
         "pageToken": str,
     },
     total=False,
 )
@@ -2136,14 +2479,22 @@
     "MonthlyTransferTypeDef",
     {
         "gbPerMonthAllocated": int,
     },
     total=False,
 )
 
+IsVpcPeeredResultTypeDef = TypedDict(
+    "IsVpcPeeredResultTypeDef",
+    {
+        "isPeered": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 OriginTypeDef = TypedDict(
     "OriginTypeDef",
     {
         "name": str,
         "resourceType": ResourceTypeType,
         "regionName": RegionNameType,
         "protocolPolicy": OriginProtocolPolicyEnumType,
@@ -2183,14 +2534,24 @@
     {
         "code": NameServersUpdateStateCodeType,
         "message": str,
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
 PendingMaintenanceActionTypeDef = TypedDict(
     "PendingMaintenanceActionTypeDef",
     {
         "action": str,
         "description": str,
         "currentApplyDate": datetime,
     },
@@ -2226,19 +2587,21 @@
         "contactProtocols": Sequence[ContactProtocolType],
         "notificationTriggers": Sequence[AlarmStateType],
         "notificationEnabled": bool,
     },
     total=False,
 )
 
+
 class PutAlarmRequestRequestTypeDef(
     _RequiredPutAlarmRequestRequestTypeDef, _OptionalPutAlarmRequestRequestTypeDef
 ):
     pass
 
+
 R53HostedZoneDeletionStateTypeDef = TypedDict(
     "R53HostedZoneDeletionStateTypeDef",
     {
         "code": R53HostedZoneDeletionStateCodeType,
         "message": str,
     },
     total=False,
@@ -2297,14 +2660,25 @@
     "ResetDistributionCacheRequestRequestTypeDef",
     {
         "distributionName": str,
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
 SendContactMethodVerificationRequestRequestTypeDef = TypedDict(
     "SendContactMethodVerificationRequestRequestTypeDef",
     {
         "protocol": Literal["Email"],
     },
 )
 
@@ -2322,67 +2696,85 @@
     {
         "resourceName": str,
         "bucketName": str,
         "access": ResourceBucketAccessType,
     },
 )
 
+StartGUISessionRequestRequestTypeDef = TypedDict(
+    "StartGUISessionRequestRequestTypeDef",
+    {
+        "resourceName": str,
+    },
+)
+
 StartInstanceRequestRequestTypeDef = TypedDict(
     "StartInstanceRequestRequestTypeDef",
     {
         "instanceName": str,
     },
 )
 
 StartRelationalDatabaseRequestRequestTypeDef = TypedDict(
     "StartRelationalDatabaseRequestRequestTypeDef",
     {
         "relationalDatabaseName": str,
     },
 )
 
+StopGUISessionRequestRequestTypeDef = TypedDict(
+    "StopGUISessionRequestRequestTypeDef",
+    {
+        "resourceName": str,
+    },
+)
+
 _RequiredStopInstanceRequestRequestTypeDef = TypedDict(
     "_RequiredStopInstanceRequestRequestTypeDef",
     {
         "instanceName": str,
     },
 )
 _OptionalStopInstanceRequestRequestTypeDef = TypedDict(
     "_OptionalStopInstanceRequestRequestTypeDef",
     {
         "force": bool,
     },
     total=False,
 )
 
+
 class StopInstanceRequestRequestTypeDef(
     _RequiredStopInstanceRequestRequestTypeDef, _OptionalStopInstanceRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredStopRelationalDatabaseRequestRequestTypeDef = TypedDict(
     "_RequiredStopRelationalDatabaseRequestRequestTypeDef",
     {
         "relationalDatabaseName": str,
     },
 )
 _OptionalStopRelationalDatabaseRequestRequestTypeDef = TypedDict(
     "_OptionalStopRelationalDatabaseRequestRequestTypeDef",
     {
         "relationalDatabaseSnapshotName": str,
     },
     total=False,
 )
 
+
 class StopRelationalDatabaseRequestRequestTypeDef(
     _RequiredStopRelationalDatabaseRequestRequestTypeDef,
     _OptionalStopRelationalDatabaseRequestRequestTypeDef,
 ):
     pass
 
+
 TestAlarmRequestRequestTypeDef = TypedDict(
     "TestAlarmRequestRequestTypeDef",
     {
         "alarmName": str,
         "state": AlarmStateType,
     },
 )
@@ -2398,19 +2790,21 @@
     "_OptionalUntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
     total=False,
 )
 
+
 class UntagResourceRequestRequestTypeDef(
     _RequiredUntagResourceRequestRequestTypeDef, _OptionalUntagResourceRequestRequestTypeDef
 ):
     pass
 
+
 UpdateBucketBundleRequestRequestTypeDef = TypedDict(
     "UpdateBucketBundleRequestRequestTypeDef",
     {
         "bucketName": str,
         "bundleId": str,
     },
 )
@@ -2437,20 +2831,22 @@
         "httpEndpoint": HttpEndpointType,
         "httpPutResponseHopLimit": int,
         "httpProtocolIpv6": HttpProtocolIpv6Type,
     },
     total=False,
 )
 
+
 class UpdateInstanceMetadataOptionsRequestRequestTypeDef(
     _RequiredUpdateInstanceMetadataOptionsRequestRequestTypeDef,
     _OptionalUpdateInstanceMetadataOptionsRequestRequestTypeDef,
 ):
     pass
 
+
 UpdateLoadBalancerAttributeRequestRequestTypeDef = TypedDict(
     "UpdateLoadBalancerAttributeRequestRequestTypeDef",
     {
         "loadBalancerName": str,
         "attributeName": LoadBalancerAttributeNameType,
         "attributeValue": str,
     },
@@ -2474,20 +2870,22 @@
         "publiclyAccessible": bool,
         "applyImmediately": bool,
         "caCertificateIdentifier": str,
     },
     total=False,
 )
 
+
 class UpdateRelationalDatabaseRequestRequestTypeDef(
     _RequiredUpdateRelationalDatabaseRequestRequestTypeDef,
     _OptionalUpdateRelationalDatabaseRequestRequestTypeDef,
 ):
     pass
 
+
 AccessKeyTypeDef = TypedDict(
     "AccessKeyTypeDef",
     {
         "accessKeyId": str,
         "secretAccessKey": str,
         "status": StatusTypeType,
         "createdAt": datetime,
@@ -2495,28 +2893,31 @@
     },
     total=False,
 )
 
 _RequiredAddOnRequestTypeDef = TypedDict(
     "_RequiredAddOnRequestTypeDef",
     {
-        "addOnType": Literal["AutoSnapshot"],
+        "addOnType": AddOnTypeType,
     },
 )
 _OptionalAddOnRequestTypeDef = TypedDict(
     "_OptionalAddOnRequestTypeDef",
     {
         "autoSnapshotAddOnRequest": AutoSnapshotAddOnRequestTypeDef,
+        "stopInstanceOnIdleRequest": StopInstanceOnIdleRequestTypeDef,
     },
     total=False,
 )
 
+
 class AddOnRequestTypeDef(_RequiredAddOnRequestTypeDef, _OptionalAddOnRequestTypeDef):
     pass
 
+
 AlarmTypeDef = TypedDict(
     "AlarmTypeDef",
     {
         "name": str,
         "arn": str,
         "createdAt": datetime,
         "location": ResourceLocationTypeDef,
@@ -2587,75 +2988,14 @@
         "ipAddress": str,
         "attachedTo": str,
         "isAttached": bool,
     },
     total=False,
 )
 
-DownloadDefaultKeyPairResultTypeDef = TypedDict(
-    "DownloadDefaultKeyPairResultTypeDef",
-    {
-        "publicKeyBase64": str,
-        "privateKeyBase64": str,
-        "createdAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetActiveNamesResultTypeDef = TypedDict(
-    "GetActiveNamesResultTypeDef",
-    {
-        "activeNames": List[str],
-        "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetContainerAPIMetadataResultTypeDef = TypedDict(
-    "GetContainerAPIMetadataResultTypeDef",
-    {
-        "metadata": List[Dict[str, str]],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetDistributionLatestCacheResetResultTypeDef = TypedDict(
-    "GetDistributionLatestCacheResetResultTypeDef",
-    {
-        "status": str,
-        "createTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetRelationalDatabaseLogStreamsResultTypeDef = TypedDict(
-    "GetRelationalDatabaseLogStreamsResultTypeDef",
-    {
-        "logStreams": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetRelationalDatabaseMasterUserPasswordResultTypeDef = TypedDict(
-    "GetRelationalDatabaseMasterUserPasswordResultTypeDef",
-    {
-        "masterUserPassword": str,
-        "createdAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-IsVpcPeeredResultTypeDef = TypedDict(
-    "IsVpcPeeredResultTypeDef",
-    {
-        "isPeered": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 AutoSnapshotDetailsTypeDef = TypedDict(
     "AutoSnapshotDetailsTypeDef",
     {
         "date": str,
         "createdAt": datetime,
         "status": AutoSnapshotStatusType,
         "fromAttachedDisks": List[AttachedDiskTypeDef],
@@ -2677,15 +3017,15 @@
 )
 
 GetBlueprintsResultTypeDef = TypedDict(
     "GetBlueprintsResultTypeDef",
     {
         "blueprints": List[BlueprintTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateBucketRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateBucketRequestRequestTypeDef",
     {
         "bucketName": str,
@@ -2698,24 +3038,26 @@
         "versioning": str,
         "readonlyAccessAccounts": Sequence[str],
         "accessLogConfig": BucketAccessLogConfigTypeDef,
     },
     total=False,
 )
 
+
 class UpdateBucketRequestRequestTypeDef(
     _RequiredUpdateBucketRequestRequestTypeDef, _OptionalUpdateBucketRequestRequestTypeDef
 ):
     pass
 
+
 GetBucketBundlesResultTypeDef = TypedDict(
     "GetBucketBundlesResultTypeDef",
     {
         "bundles": List[BucketBundleTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BucketTypeDef = TypedDict(
     "BucketTypeDef",
     {
         "resourceType": str,
@@ -2750,19 +3092,21 @@
     {
         "tags": Sequence[TagTypeDef],
         "enableObjectVersioning": bool,
     },
     total=False,
 )
 
+
 class CreateBucketRequestRequestTypeDef(
     _RequiredCreateBucketRequestRequestTypeDef, _OptionalCreateBucketRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredCreateCertificateRequestRequestTypeDef = TypedDict(
     "_RequiredCreateCertificateRequestRequestTypeDef",
     {
         "certificateName": str,
         "domainName": str,
     },
 )
@@ -2771,19 +3115,21 @@
     {
         "subjectAlternativeNames": Sequence[str],
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateCertificateRequestRequestTypeDef(
     _RequiredCreateCertificateRequestRequestTypeDef, _OptionalCreateCertificateRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredCreateDiskSnapshotRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDiskSnapshotRequestRequestTypeDef",
     {
         "diskSnapshotName": str,
     },
 )
 _OptionalCreateDiskSnapshotRequestRequestTypeDef = TypedDict(
@@ -2792,39 +3138,43 @@
         "diskName": str,
         "instanceName": str,
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateDiskSnapshotRequestRequestTypeDef(
     _RequiredCreateDiskSnapshotRequestRequestTypeDef,
     _OptionalCreateDiskSnapshotRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredCreateDomainRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDomainRequestRequestTypeDef",
     {
         "domainName": str,
     },
 )
 _OptionalCreateDomainRequestRequestTypeDef = TypedDict(
     "_OptionalCreateDomainRequestRequestTypeDef",
     {
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateDomainRequestRequestTypeDef(
     _RequiredCreateDomainRequestRequestTypeDef, _OptionalCreateDomainRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredCreateInstanceSnapshotRequestRequestTypeDef = TypedDict(
     "_RequiredCreateInstanceSnapshotRequestRequestTypeDef",
     {
         "instanceSnapshotName": str,
         "instanceName": str,
     },
 )
@@ -2832,39 +3182,43 @@
     "_OptionalCreateInstanceSnapshotRequestRequestTypeDef",
     {
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateInstanceSnapshotRequestRequestTypeDef(
     _RequiredCreateInstanceSnapshotRequestRequestTypeDef,
     _OptionalCreateInstanceSnapshotRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredCreateKeyPairRequestRequestTypeDef = TypedDict(
     "_RequiredCreateKeyPairRequestRequestTypeDef",
     {
         "keyPairName": str,
     },
 )
 _OptionalCreateKeyPairRequestRequestTypeDef = TypedDict(
     "_OptionalCreateKeyPairRequestRequestTypeDef",
     {
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateKeyPairRequestRequestTypeDef(
     _RequiredCreateKeyPairRequestRequestTypeDef, _OptionalCreateKeyPairRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredCreateLoadBalancerRequestRequestTypeDef = TypedDict(
     "_RequiredCreateLoadBalancerRequestRequestTypeDef",
     {
         "loadBalancerName": str,
         "instancePort": int,
     },
 )
@@ -2878,20 +3232,22 @@
         "tags": Sequence[TagTypeDef],
         "ipAddressType": IpAddressTypeType,
         "tlsPolicyName": str,
     },
     total=False,
 )
 
+
 class CreateLoadBalancerRequestRequestTypeDef(
     _RequiredCreateLoadBalancerRequestRequestTypeDef,
     _OptionalCreateLoadBalancerRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredCreateLoadBalancerTlsCertificateRequestRequestTypeDef = TypedDict(
     "_RequiredCreateLoadBalancerTlsCertificateRequestRequestTypeDef",
     {
         "loadBalancerName": str,
         "certificateName": str,
         "certificateDomainName": str,
     },
@@ -2901,20 +3257,22 @@
     {
         "certificateAlternativeNames": Sequence[str],
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateLoadBalancerTlsCertificateRequestRequestTypeDef(
     _RequiredCreateLoadBalancerTlsCertificateRequestRequestTypeDef,
     _OptionalCreateLoadBalancerTlsCertificateRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredCreateRelationalDatabaseFromSnapshotRequestRequestTypeDef = TypedDict(
     "_RequiredCreateRelationalDatabaseFromSnapshotRequestRequestTypeDef",
     {
         "relationalDatabaseName": str,
     },
 )
 _OptionalCreateRelationalDatabaseFromSnapshotRequestRequestTypeDef = TypedDict(
@@ -2928,20 +3286,22 @@
         "restoreTime": Union[datetime, str],
         "useLatestRestorableTime": bool,
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateRelationalDatabaseFromSnapshotRequestRequestTypeDef(
     _RequiredCreateRelationalDatabaseFromSnapshotRequestRequestTypeDef,
     _OptionalCreateRelationalDatabaseFromSnapshotRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredCreateRelationalDatabaseRequestRequestTypeDef = TypedDict(
     "_RequiredCreateRelationalDatabaseRequestRequestTypeDef",
     {
         "relationalDatabaseName": str,
         "relationalDatabaseBlueprintId": str,
         "relationalDatabaseBundleId": str,
         "masterDatabaseName": str,
@@ -2957,20 +3317,22 @@
         "preferredMaintenanceWindow": str,
         "publiclyAccessible": bool,
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateRelationalDatabaseRequestRequestTypeDef(
     _RequiredCreateRelationalDatabaseRequestRequestTypeDef,
     _OptionalCreateRelationalDatabaseRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredCreateRelationalDatabaseSnapshotRequestRequestTypeDef = TypedDict(
     "_RequiredCreateRelationalDatabaseSnapshotRequestRequestTypeDef",
     {
         "relationalDatabaseName": str,
         "relationalDatabaseSnapshotName": str,
     },
 )
@@ -2978,20 +3340,22 @@
     "_OptionalCreateRelationalDatabaseSnapshotRequestRequestTypeDef",
     {
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateRelationalDatabaseSnapshotRequestRequestTypeDef(
     _RequiredCreateRelationalDatabaseSnapshotRequestRequestTypeDef,
     _OptionalCreateRelationalDatabaseSnapshotRequestRequestTypeDef,
 ):
     pass
 
+
 DiskSnapshotTypeDef = TypedDict(
     "DiskSnapshotTypeDef",
     {
         "name": str,
         "arn": str,
         "supportCode": str,
         "createdAt": datetime,
@@ -3026,14 +3390,15 @@
         "iops": int,
         "path": str,
         "state": DiskStateType,
         "attachedTo": str,
         "isAttached": bool,
         "attachmentState": str,
         "gbInUse": int,
+        "autoMountStatus": AutoMountStatusType,
     },
     total=False,
 )
 
 KeyPairTypeDef = TypedDict(
     "KeyPairTypeDef",
     {
@@ -3082,25 +3447,27 @@
     "_OptionalTagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
     total=False,
 )
 
+
 class TagResourceRequestRequestTypeDef(
     _RequiredTagResourceRequestRequestTypeDef, _OptionalTagResourceRequestRequestTypeDef
 ):
     pass
 
+
 GetBundlesResultTypeDef = TypedDict(
     "GetBundlesResultTypeDef",
     {
         "bundles": List[BundleTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CacheSettingsTypeDef = TypedDict(
     "CacheSettingsTypeDef",
     {
         "defaultTTL": int,
@@ -3154,23 +3521,23 @@
     total=False,
 )
 
 GetContainerImagesResultTypeDef = TypedDict(
     "GetContainerImagesResultTypeDef",
     {
         "containerImages": List[ContainerImageTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RegisterContainerImageResultTypeDef = TypedDict(
     "RegisterContainerImageResultTypeDef",
     {
         "containerImage": ContainerImageTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PrivateRegistryAccessRequestTypeDef = TypedDict(
     "PrivateRegistryAccessRequestTypeDef",
     {
         "ecrImagePullerRole": ContainerServiceECRImagePullerRoleRequestTypeDef,
@@ -3207,39 +3574,41 @@
     "_OptionalEndpointRequestTypeDef",
     {
         "healthCheck": ContainerServiceHealthCheckConfigTypeDef,
     },
     total=False,
 )
 
+
 class EndpointRequestTypeDef(_RequiredEndpointRequestTypeDef, _OptionalEndpointRequestTypeDef):
     pass
 
+
 GetContainerLogResultTypeDef = TypedDict(
     "GetContainerLogResultTypeDef",
     {
         "logEvents": List[ContainerServiceLogEventTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetContainerServicePowersResultTypeDef = TypedDict(
     "GetContainerServicePowersResultTypeDef",
     {
         "powers": List[ContainerServicePowerTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateContainerServiceRegistryLoginResultTypeDef = TypedDict(
     "CreateContainerServiceRegistryLoginResultTypeDef",
     {
         "registryLogin": ContainerServiceRegistryLoginTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateCloudFormationStackRequestRequestTypeDef = TypedDict(
     "CreateCloudFormationStackRequestRequestTypeDef",
     {
         "instances": Sequence[InstanceEntryTypeDef],
@@ -3266,354 +3635,189 @@
     "UpdateDomainEntryRequestRequestTypeDef",
     {
         "domainName": str,
         "domainEntry": DomainEntryTypeDef,
     },
 )
 
+CreateGUISessionAccessDetailsResultTypeDef = TypedDict(
+    "CreateGUISessionAccessDetailsResultTypeDef",
+    {
+        "resourceName": str,
+        "status": StatusType,
+        "percentageComplete": int,
+        "failureReason": str,
+        "sessions": List[SessionTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 InstanceSnapshotInfoTypeDef = TypedDict(
     "InstanceSnapshotInfoTypeDef",
     {
         "fromBundleId": str,
         "fromBlueprintId": str,
         "fromDiskInfo": List[DiskInfoTypeDef],
     },
     total=False,
 )
 
 GetDistributionBundlesResultTypeDef = TypedDict(
     "GetDistributionBundlesResultTypeDef",
     {
         "bundles": List[DistributionBundleTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DomainValidationRecordTypeDef = TypedDict(
     "DomainValidationRecordTypeDef",
     {
         "domainName": str,
         "resourceRecord": ResourceRecordTypeDef,
         "dnsRecordCreationState": DnsRecordCreationStateTypeDef,
         "validationStatus": CertificateDomainValidationStatusType,
     },
     total=False,
 )
 
-GetActiveNamesRequestGetActiveNamesPaginateTypeDef = TypedDict(
-    "GetActiveNamesRequestGetActiveNamesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetBlueprintsRequestGetBlueprintsPaginateTypeDef = TypedDict(
-    "GetBlueprintsRequestGetBlueprintsPaginateTypeDef",
-    {
-        "includeInactive": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetBundlesRequestGetBundlesPaginateTypeDef = TypedDict(
-    "GetBundlesRequestGetBundlesPaginateTypeDef",
-    {
-        "includeInactive": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetCloudFormationStackRecordsRequestGetCloudFormationStackRecordsPaginateTypeDef = TypedDict(
-    "GetCloudFormationStackRecordsRequestGetCloudFormationStackRecordsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetDiskSnapshotsRequestGetDiskSnapshotsPaginateTypeDef = TypedDict(
-    "GetDiskSnapshotsRequestGetDiskSnapshotsPaginateTypeDef",
+EstimateByTimeTypeDef = TypedDict(
+    "EstimateByTimeTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetDisksRequestGetDisksPaginateTypeDef = TypedDict(
-    "GetDisksRequestGetDisksPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetDomainsRequestGetDomainsPaginateTypeDef = TypedDict(
-    "GetDomainsRequestGetDomainsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetExportSnapshotRecordsRequestGetExportSnapshotRecordsPaginateTypeDef = TypedDict(
-    "GetExportSnapshotRecordsRequestGetExportSnapshotRecordsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetInstanceSnapshotsRequestGetInstanceSnapshotsPaginateTypeDef = TypedDict(
-    "GetInstanceSnapshotsRequestGetInstanceSnapshotsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetInstancesRequestGetInstancesPaginateTypeDef = TypedDict(
-    "GetInstancesRequestGetInstancesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetKeyPairsRequestGetKeyPairsPaginateTypeDef = TypedDict(
-    "GetKeyPairsRequestGetKeyPairsPaginateTypeDef",
-    {
-        "includeDefaultKeyPair": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetLoadBalancersRequestGetLoadBalancersPaginateTypeDef = TypedDict(
-    "GetLoadBalancersRequestGetLoadBalancersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetOperationsRequestGetOperationsPaginateTypeDef = TypedDict(
-    "GetOperationsRequestGetOperationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetRelationalDatabaseBlueprintsRequestGetRelationalDatabaseBlueprintsPaginateTypeDef = TypedDict(
-    "GetRelationalDatabaseBlueprintsRequestGetRelationalDatabaseBlueprintsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetRelationalDatabaseBundlesRequestGetRelationalDatabaseBundlesPaginateTypeDef = TypedDict(
-    "GetRelationalDatabaseBundlesRequestGetRelationalDatabaseBundlesPaginateTypeDef",
-    {
-        "includeInactive": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredGetRelationalDatabaseEventsRequestGetRelationalDatabaseEventsPaginateTypeDef = TypedDict(
-    "_RequiredGetRelationalDatabaseEventsRequestGetRelationalDatabaseEventsPaginateTypeDef",
-    {
-        "relationalDatabaseName": str,
-    },
-)
-_OptionalGetRelationalDatabaseEventsRequestGetRelationalDatabaseEventsPaginateTypeDef = TypedDict(
-    "_OptionalGetRelationalDatabaseEventsRequestGetRelationalDatabaseEventsPaginateTypeDef",
-    {
-        "durationInMinutes": int,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetRelationalDatabaseEventsRequestGetRelationalDatabaseEventsPaginateTypeDef(
-    _RequiredGetRelationalDatabaseEventsRequestGetRelationalDatabaseEventsPaginateTypeDef,
-    _OptionalGetRelationalDatabaseEventsRequestGetRelationalDatabaseEventsPaginateTypeDef,
-):
-    pass
-
-_RequiredGetRelationalDatabaseParametersRequestGetRelationalDatabaseParametersPaginateTypeDef = TypedDict(
-    "_RequiredGetRelationalDatabaseParametersRequestGetRelationalDatabaseParametersPaginateTypeDef",
-    {
-        "relationalDatabaseName": str,
-    },
-)
-_OptionalGetRelationalDatabaseParametersRequestGetRelationalDatabaseParametersPaginateTypeDef = TypedDict(
-    "_OptionalGetRelationalDatabaseParametersRequestGetRelationalDatabaseParametersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class GetRelationalDatabaseParametersRequestGetRelationalDatabaseParametersPaginateTypeDef(
-    _RequiredGetRelationalDatabaseParametersRequestGetRelationalDatabaseParametersPaginateTypeDef,
-    _OptionalGetRelationalDatabaseParametersRequestGetRelationalDatabaseParametersPaginateTypeDef,
-):
-    pass
-
-GetRelationalDatabaseSnapshotsRequestGetRelationalDatabaseSnapshotsPaginateTypeDef = TypedDict(
-    "GetRelationalDatabaseSnapshotsRequestGetRelationalDatabaseSnapshotsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetRelationalDatabasesRequestGetRelationalDatabasesPaginateTypeDef = TypedDict(
-    "GetRelationalDatabasesRequestGetRelationalDatabasesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-GetStaticIpsRequestGetStaticIpsPaginateTypeDef = TypedDict(
-    "GetStaticIpsRequestGetStaticIpsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "usageCost": float,
+        "pricingUnit": PricingUnitType,
+        "unit": float,
+        "currency": Literal["USD"],
+        "timePeriod": TimePeriodTypeDef,
     },
     total=False,
 )
 
 GetBucketMetricDataResultTypeDef = TypedDict(
     "GetBucketMetricDataResultTypeDef",
     {
         "metricName": BucketMetricNameType,
         "metricData": List[MetricDatapointTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetContainerServiceMetricDataResultTypeDef = TypedDict(
     "GetContainerServiceMetricDataResultTypeDef",
     {
         "metricName": ContainerServiceMetricNameType,
         "metricData": List[MetricDatapointTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDistributionMetricDataResultTypeDef = TypedDict(
     "GetDistributionMetricDataResultTypeDef",
     {
         "metricName": DistributionMetricNameType,
         "metricData": List[MetricDatapointTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetInstanceMetricDataResultTypeDef = TypedDict(
     "GetInstanceMetricDataResultTypeDef",
     {
         "metricName": InstanceMetricNameType,
         "metricData": List[MetricDatapointTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetLoadBalancerMetricDataResultTypeDef = TypedDict(
     "GetLoadBalancerMetricDataResultTypeDef",
     {
         "metricName": LoadBalancerMetricNameType,
         "metricData": List[MetricDatapointTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRelationalDatabaseMetricDataResultTypeDef = TypedDict(
     "GetRelationalDatabaseMetricDataResultTypeDef",
     {
         "metricName": RelationalDatabaseMetricNameType,
         "metricData": List[MetricDatapointTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetInstancePortStatesResultTypeDef = TypedDict(
     "GetInstancePortStatesResultTypeDef",
     {
         "portStates": List[InstancePortStateTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetInstanceStateResultTypeDef = TypedDict(
     "GetInstanceStateResultTypeDef",
     {
         "state": InstanceStateTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetLoadBalancerTlsPoliciesResultTypeDef = TypedDict(
     "GetLoadBalancerTlsPoliciesResultTypeDef",
     {
         "tlsPolicies": List[LoadBalancerTlsPolicyTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRelationalDatabaseBlueprintsResultTypeDef = TypedDict(
     "GetRelationalDatabaseBlueprintsResultTypeDef",
     {
         "blueprints": List[RelationalDatabaseBlueprintTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRelationalDatabaseBundlesResultTypeDef = TypedDict(
     "GetRelationalDatabaseBundlesResultTypeDef",
     {
         "bundles": List[RelationalDatabaseBundleTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRelationalDatabaseEventsResultTypeDef = TypedDict(
     "GetRelationalDatabaseEventsResultTypeDef",
     {
         "relationalDatabaseEvents": List[RelationalDatabaseEventTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRelationalDatabaseLogEventsResultTypeDef = TypedDict(
     "GetRelationalDatabaseLogEventsResultTypeDef",
     {
         "resourceLogEvents": List[LogEventTypeDef],
         "nextBackwardToken": str,
         "nextForwardToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRelationalDatabaseParametersResultTypeDef = TypedDict(
     "GetRelationalDatabaseParametersResultTypeDef",
     {
         "parameters": List[RelationalDatabaseParameterTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateRelationalDatabaseParametersRequestRequestTypeDef = TypedDict(
     "UpdateRelationalDatabaseParametersRequestRequestTypeDef",
     {
         "relationalDatabaseName": str,
@@ -3737,15 +3941,15 @@
     total=False,
 )
 
 GetBucketAccessKeysResultTypeDef = TypedDict(
     "GetBucketAccessKeysResultTypeDef",
     {
         "accessKeys": List[AccessKeyTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateDiskFromSnapshotRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDiskFromSnapshotRequestRequestTypeDef",
     {
         "diskName": str,
@@ -3762,20 +3966,22 @@
         "sourceDiskName": str,
         "restoreDate": str,
         "useLatestRestorableAutoSnapshot": bool,
     },
     total=False,
 )
 
+
 class CreateDiskFromSnapshotRequestRequestTypeDef(
     _RequiredCreateDiskFromSnapshotRequestRequestTypeDef,
     _OptionalCreateDiskFromSnapshotRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredCreateDiskRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDiskRequestRequestTypeDef",
     {
         "diskName": str,
         "availabilityZone": str,
         "sizeInGb": int,
     },
@@ -3785,19 +3991,21 @@
     {
         "tags": Sequence[TagTypeDef],
         "addOns": Sequence[AddOnRequestTypeDef],
     },
     total=False,
 )
 
+
 class CreateDiskRequestRequestTypeDef(
     _RequiredCreateDiskRequestRequestTypeDef, _OptionalCreateDiskRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredCreateInstancesFromSnapshotRequestRequestTypeDef = TypedDict(
     "_RequiredCreateInstancesFromSnapshotRequestRequestTypeDef",
     {
         "instanceNames": Sequence[str],
         "availabilityZone": str,
         "bundleId": str,
     },
@@ -3815,20 +4023,22 @@
         "sourceInstanceName": str,
         "restoreDate": str,
         "useLatestRestorableAutoSnapshot": bool,
     },
     total=False,
 )
 
+
 class CreateInstancesFromSnapshotRequestRequestTypeDef(
     _RequiredCreateInstancesFromSnapshotRequestRequestTypeDef,
     _OptionalCreateInstancesFromSnapshotRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredCreateInstancesRequestRequestTypeDef = TypedDict(
     "_RequiredCreateInstancesRequestRequestTypeDef",
     {
         "instanceNames": Sequence[str],
         "availabilityZone": str,
         "blueprintId": str,
         "bundleId": str,
@@ -3843,792 +4053,810 @@
         "tags": Sequence[TagTypeDef],
         "addOns": Sequence[AddOnRequestTypeDef],
         "ipAddressType": IpAddressTypeType,
     },
     total=False,
 )
 
+
 class CreateInstancesRequestRequestTypeDef(
     _RequiredCreateInstancesRequestRequestTypeDef, _OptionalCreateInstancesRequestRequestTypeDef
 ):
     pass
 
+
 EnableAddOnRequestRequestTypeDef = TypedDict(
     "EnableAddOnRequestRequestTypeDef",
     {
         "resourceName": str,
         "addOnRequest": AddOnRequestTypeDef,
     },
 )
 
 GetAlarmsResultTypeDef = TypedDict(
     "GetAlarmsResultTypeDef",
     {
         "alarms": List[AlarmTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetContactMethodsResultTypeDef = TypedDict(
     "GetContactMethodsResultTypeDef",
     {
         "contactMethods": List[ContactMethodTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AllocateStaticIpResultTypeDef = TypedDict(
     "AllocateStaticIpResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AttachCertificateToDistributionResultTypeDef = TypedDict(
     "AttachCertificateToDistributionResultTypeDef",
     {
         "operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AttachDiskResultTypeDef = TypedDict(
     "AttachDiskResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AttachInstancesToLoadBalancerResultTypeDef = TypedDict(
     "AttachInstancesToLoadBalancerResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AttachLoadBalancerTlsCertificateResultTypeDef = TypedDict(
     "AttachLoadBalancerTlsCertificateResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AttachStaticIpResultTypeDef = TypedDict(
     "AttachStaticIpResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CloseInstancePublicPortsResultTypeDef = TypedDict(
     "CloseInstancePublicPortsResultTypeDef",
     {
         "operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CopySnapshotResultTypeDef = TypedDict(
     "CopySnapshotResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateBucketAccessKeyResultTypeDef = TypedDict(
     "CreateBucketAccessKeyResultTypeDef",
     {
         "accessKey": AccessKeyTypeDef,
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateCloudFormationStackResultTypeDef = TypedDict(
     "CreateCloudFormationStackResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateContactMethodResultTypeDef = TypedDict(
     "CreateContactMethodResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDiskFromSnapshotResultTypeDef = TypedDict(
     "CreateDiskFromSnapshotResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDiskResultTypeDef = TypedDict(
     "CreateDiskResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDiskSnapshotResultTypeDef = TypedDict(
     "CreateDiskSnapshotResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDomainEntryResultTypeDef = TypedDict(
     "CreateDomainEntryResultTypeDef",
     {
         "operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDomainResultTypeDef = TypedDict(
     "CreateDomainResultTypeDef",
     {
         "operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateInstanceSnapshotResultTypeDef = TypedDict(
     "CreateInstanceSnapshotResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateInstancesFromSnapshotResultTypeDef = TypedDict(
     "CreateInstancesFromSnapshotResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateInstancesResultTypeDef = TypedDict(
     "CreateInstancesResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateLoadBalancerResultTypeDef = TypedDict(
     "CreateLoadBalancerResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateLoadBalancerTlsCertificateResultTypeDef = TypedDict(
     "CreateLoadBalancerTlsCertificateResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateRelationalDatabaseFromSnapshotResultTypeDef = TypedDict(
     "CreateRelationalDatabaseFromSnapshotResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateRelationalDatabaseResultTypeDef = TypedDict(
     "CreateRelationalDatabaseResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateRelationalDatabaseSnapshotResultTypeDef = TypedDict(
     "CreateRelationalDatabaseSnapshotResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteAlarmResultTypeDef = TypedDict(
     "DeleteAlarmResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteAutoSnapshotResultTypeDef = TypedDict(
     "DeleteAutoSnapshotResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteBucketAccessKeyResultTypeDef = TypedDict(
     "DeleteBucketAccessKeyResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteBucketResultTypeDef = TypedDict(
     "DeleteBucketResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteCertificateResultTypeDef = TypedDict(
     "DeleteCertificateResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteContactMethodResultTypeDef = TypedDict(
     "DeleteContactMethodResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteDiskResultTypeDef = TypedDict(
     "DeleteDiskResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteDiskSnapshotResultTypeDef = TypedDict(
     "DeleteDiskSnapshotResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteDistributionResultTypeDef = TypedDict(
     "DeleteDistributionResultTypeDef",
     {
         "operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteDomainEntryResultTypeDef = TypedDict(
     "DeleteDomainEntryResultTypeDef",
     {
         "operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteDomainResultTypeDef = TypedDict(
     "DeleteDomainResultTypeDef",
     {
         "operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteInstanceResultTypeDef = TypedDict(
     "DeleteInstanceResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteInstanceSnapshotResultTypeDef = TypedDict(
     "DeleteInstanceSnapshotResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteKeyPairResultTypeDef = TypedDict(
     "DeleteKeyPairResultTypeDef",
     {
         "operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteKnownHostKeysResultTypeDef = TypedDict(
     "DeleteKnownHostKeysResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteLoadBalancerResultTypeDef = TypedDict(
     "DeleteLoadBalancerResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteLoadBalancerTlsCertificateResultTypeDef = TypedDict(
     "DeleteLoadBalancerTlsCertificateResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteRelationalDatabaseResultTypeDef = TypedDict(
     "DeleteRelationalDatabaseResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteRelationalDatabaseSnapshotResultTypeDef = TypedDict(
     "DeleteRelationalDatabaseSnapshotResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DetachCertificateFromDistributionResultTypeDef = TypedDict(
     "DetachCertificateFromDistributionResultTypeDef",
     {
         "operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DetachDiskResultTypeDef = TypedDict(
     "DetachDiskResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DetachInstancesFromLoadBalancerResultTypeDef = TypedDict(
     "DetachInstancesFromLoadBalancerResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DetachStaticIpResultTypeDef = TypedDict(
     "DetachStaticIpResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DisableAddOnResultTypeDef = TypedDict(
     "DisableAddOnResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EnableAddOnResultTypeDef = TypedDict(
     "EnableAddOnResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ExportSnapshotResultTypeDef = TypedDict(
     "ExportSnapshotResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetOperationResultTypeDef = TypedDict(
     "GetOperationResultTypeDef",
     {
         "operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetOperationsForResourceResultTypeDef = TypedDict(
     "GetOperationsForResourceResultTypeDef",
     {
         "operations": List[OperationTypeDef],
         "nextPageCount": str,
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetOperationsResultTypeDef = TypedDict(
     "GetOperationsResultTypeDef",
     {
         "operations": List[OperationTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ImportKeyPairResultTypeDef = TypedDict(
     "ImportKeyPairResultTypeDef",
     {
         "operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OpenInstancePublicPortsResultTypeDef = TypedDict(
     "OpenInstancePublicPortsResultTypeDef",
     {
         "operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PeerVpcResultTypeDef = TypedDict(
     "PeerVpcResultTypeDef",
     {
         "operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutAlarmResultTypeDef = TypedDict(
     "PutAlarmResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutInstancePublicPortsResultTypeDef = TypedDict(
     "PutInstancePublicPortsResultTypeDef",
     {
         "operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RebootInstanceResultTypeDef = TypedDict(
     "RebootInstanceResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RebootRelationalDatabaseResultTypeDef = TypedDict(
     "RebootRelationalDatabaseResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ReleaseStaticIpResultTypeDef = TypedDict(
     "ReleaseStaticIpResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResetDistributionCacheResultTypeDef = TypedDict(
     "ResetDistributionCacheResultTypeDef",
     {
         "status": str,
         "createTime": datetime,
         "operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SendContactMethodVerificationResultTypeDef = TypedDict(
     "SendContactMethodVerificationResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SetIpAddressTypeResultTypeDef = TypedDict(
     "SetIpAddressTypeResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SetResourceAccessForBucketResultTypeDef = TypedDict(
     "SetResourceAccessForBucketResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StartGUISessionResultTypeDef = TypedDict(
+    "StartGUISessionResultTypeDef",
+    {
+        "operations": List[OperationTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartInstanceResultTypeDef = TypedDict(
     "StartInstanceResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartRelationalDatabaseResultTypeDef = TypedDict(
     "StartRelationalDatabaseResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StopGUISessionResultTypeDef = TypedDict(
+    "StopGUISessionResultTypeDef",
+    {
+        "operations": List[OperationTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopInstanceResultTypeDef = TypedDict(
     "StopInstanceResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopRelationalDatabaseResultTypeDef = TypedDict(
     "StopRelationalDatabaseResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TagResourceResultTypeDef = TypedDict(
     "TagResourceResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TestAlarmResultTypeDef = TypedDict(
     "TestAlarmResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UnpeerVpcResultTypeDef = TypedDict(
     "UnpeerVpcResultTypeDef",
     {
         "operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UntagResourceResultTypeDef = TypedDict(
     "UntagResourceResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateBucketBundleResultTypeDef = TypedDict(
     "UpdateBucketBundleResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDistributionBundleResultTypeDef = TypedDict(
     "UpdateDistributionBundleResultTypeDef",
     {
         "operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDistributionResultTypeDef = TypedDict(
     "UpdateDistributionResultTypeDef",
     {
         "operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDomainEntryResultTypeDef = TypedDict(
     "UpdateDomainEntryResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateInstanceMetadataOptionsResultTypeDef = TypedDict(
     "UpdateInstanceMetadataOptionsResultTypeDef",
     {
         "operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateLoadBalancerAttributeResultTypeDef = TypedDict(
     "UpdateLoadBalancerAttributeResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateRelationalDatabaseParametersResultTypeDef = TypedDict(
     "UpdateRelationalDatabaseParametersResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateRelationalDatabaseResultTypeDef = TypedDict(
     "UpdateRelationalDatabaseResultTypeDef",
     {
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetStaticIpResultTypeDef = TypedDict(
     "GetStaticIpResultTypeDef",
     {
         "staticIp": StaticIpTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetStaticIpsResultTypeDef = TypedDict(
     "GetStaticIpsResultTypeDef",
     {
         "staticIps": List[StaticIpTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetAutoSnapshotsResultTypeDef = TypedDict(
     "GetAutoSnapshotsResultTypeDef",
     {
         "resourceName": str,
         "resourceType": ResourceTypeType,
         "autoSnapshots": List[AutoSnapshotDetailsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRegionsResultTypeDef = TypedDict(
     "GetRegionsResultTypeDef",
     {
         "regions": List[RegionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateBucketResultTypeDef = TypedDict(
     "CreateBucketResultTypeDef",
     {
         "bucket": BucketTypeDef,
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetBucketsResultTypeDef = TypedDict(
     "GetBucketsResultTypeDef",
     {
         "buckets": List[BucketTypeDef],
         "nextPageToken": str,
         "accountLevelBpaSync": AccountLevelBpaSyncTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateBucketResultTypeDef = TypedDict(
     "UpdateBucketResultTypeDef",
     {
         "bucket": BucketTypeDef,
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDiskSnapshotResultTypeDef = TypedDict(
     "GetDiskSnapshotResultTypeDef",
     {
         "diskSnapshot": DiskSnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDiskSnapshotsResultTypeDef = TypedDict(
     "GetDiskSnapshotsResultTypeDef",
     {
         "diskSnapshots": List[DiskSnapshotTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDiskResultTypeDef = TypedDict(
     "GetDiskResultTypeDef",
     {
         "disk": DiskTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDisksResultTypeDef = TypedDict(
     "GetDisksResultTypeDef",
     {
         "disks": List[DiskTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InstanceHardwareTypeDef = TypedDict(
     "InstanceHardwareTypeDef",
     {
         "cpuCount": int,
@@ -4664,49 +4892,49 @@
 CreateKeyPairResultTypeDef = TypedDict(
     "CreateKeyPairResultTypeDef",
     {
         "keyPair": KeyPairTypeDef,
         "publicKeyBase64": str,
         "privateKeyBase64": str,
         "operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetKeyPairResultTypeDef = TypedDict(
     "GetKeyPairResultTypeDef",
     {
         "keyPair": KeyPairTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetKeyPairsResultTypeDef = TypedDict(
     "GetKeyPairsResultTypeDef",
     {
         "keyPairs": List[KeyPairTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRelationalDatabaseSnapshotResultTypeDef = TypedDict(
     "GetRelationalDatabaseSnapshotResultTypeDef",
     {
         "relationalDatabaseSnapshot": RelationalDatabaseSnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRelationalDatabaseSnapshotsResultTypeDef = TypedDict(
     "GetRelationalDatabaseSnapshotsResultTypeDef",
     {
         "relationalDatabaseSnapshots": List[RelationalDatabaseSnapshotTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateDistributionRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDistributionRequestRequestTypeDef",
     {
         "distributionName": str,
@@ -4722,20 +4950,22 @@
         "cacheBehaviors": Sequence[CacheBehaviorPerPathTypeDef],
         "ipAddressType": IpAddressTypeType,
         "tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateDistributionRequestRequestTypeDef(
     _RequiredCreateDistributionRequestRequestTypeDef,
     _OptionalCreateDistributionRequestRequestTypeDef,
 ):
     pass
 
+
 LightsailDistributionTypeDef = TypedDict(
     "LightsailDistributionTypeDef",
     {
         "name": str,
         "arn": str,
         "supportCode": str,
         "createdAt": datetime,
@@ -4773,26 +5003,28 @@
         "cacheBehaviorSettings": CacheSettingsTypeDef,
         "cacheBehaviors": Sequence[CacheBehaviorPerPathTypeDef],
         "isEnabled": bool,
     },
     total=False,
 )
 
+
 class UpdateDistributionRequestRequestTypeDef(
     _RequiredUpdateDistributionRequestRequestTypeDef,
     _OptionalUpdateDistributionRequestRequestTypeDef,
 ):
     pass
 
+
 GetCloudFormationStackRecordsResultTypeDef = TypedDict(
     "GetCloudFormationStackRecordsResultTypeDef",
     {
         "cloudFormationStackRecords": List[CloudFormationStackRecordTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateContainerServiceRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateContainerServiceRequestRequestTypeDef",
     {
         "serviceName": str,
@@ -4806,20 +5038,22 @@
         "isDisabled": bool,
         "publicDomainNames": Mapping[str, Sequence[str]],
         "privateRegistryAccess": PrivateRegistryAccessRequestTypeDef,
     },
     total=False,
 )
 
+
 class UpdateContainerServiceRequestRequestTypeDef(
     _RequiredUpdateContainerServiceRequestRequestTypeDef,
     _OptionalUpdateContainerServiceRequestRequestTypeDef,
 ):
     pass
 
+
 ContainerServiceDeploymentTypeDef = TypedDict(
     "ContainerServiceDeploymentTypeDef",
     {
         "version": int,
         "state": ContainerServiceDeploymentStateType,
         "containers": Dict[str, ContainerTypeDef],
         "publicEndpoint": ContainerServiceEndpointTypeDef,
@@ -4848,20 +5082,22 @@
     {
         "containers": Mapping[str, ContainerTypeDef],
         "publicEndpoint": EndpointRequestTypeDef,
     },
     total=False,
 )
 
+
 class CreateContainerServiceDeploymentRequestRequestTypeDef(
     _RequiredCreateContainerServiceDeploymentRequestRequestTypeDef,
     _OptionalCreateContainerServiceDeploymentRequestRequestTypeDef,
 ):
     pass
 
+
 ExportSnapshotRecordSourceInfoTypeDef = TypedDict(
     "ExportSnapshotRecordSourceInfoTypeDef",
     {
         "resourceType": ExportSnapshotRecordSourceTypeType,
         "createdAt": datetime,
         "name": str,
         "arn": str,
@@ -4880,19 +5116,28 @@
         "renewalStatus": RenewalStatusType,
         "renewalStatusReason": str,
         "updatedAt": datetime,
     },
     total=False,
 )
 
+CostEstimateTypeDef = TypedDict(
+    "CostEstimateTypeDef",
+    {
+        "usageType": str,
+        "resultsByTime": List[EstimateByTimeTypeDef],
+    },
+    total=False,
+)
+
 GetInstanceAccessDetailsResultTypeDef = TypedDict(
     "GetInstanceAccessDetailsResultTypeDef",
     {
         "accessDetails": InstanceAccessDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LoadBalancerTlsCertificateTypeDef = TypedDict(
     "LoadBalancerTlsCertificateTypeDef",
     {
         "name": str,
@@ -4924,24 +5169,24 @@
     total=False,
 )
 
 GetLoadBalancerResultTypeDef = TypedDict(
     "GetLoadBalancerResultTypeDef",
     {
         "loadBalancer": LoadBalancerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetLoadBalancersResultTypeDef = TypedDict(
     "GetLoadBalancersResultTypeDef",
     {
         "loadBalancers": List[LoadBalancerTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DomainTypeDef = TypedDict(
     "DomainTypeDef",
     {
         "name": str,
@@ -4957,24 +5202,24 @@
     total=False,
 )
 
 GetRelationalDatabaseResultTypeDef = TypedDict(
     "GetRelationalDatabaseResultTypeDef",
     {
         "relationalDatabase": RelationalDatabaseTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRelationalDatabasesResultTypeDef = TypedDict(
     "GetRelationalDatabasesResultTypeDef",
     {
         "relationalDatabases": List[RelationalDatabaseTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InstanceTypeDef = TypedDict(
     "InstanceTypeDef",
     {
         "name": str,
@@ -5003,42 +5248,42 @@
     total=False,
 )
 
 GetInstanceSnapshotResultTypeDef = TypedDict(
     "GetInstanceSnapshotResultTypeDef",
     {
         "instanceSnapshot": InstanceSnapshotTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetInstanceSnapshotsResultTypeDef = TypedDict(
     "GetInstanceSnapshotsResultTypeDef",
     {
         "instanceSnapshots": List[InstanceSnapshotTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDistributionResultTypeDef = TypedDict(
     "CreateDistributionResultTypeDef",
     {
         "distribution": LightsailDistributionTypeDef,
         "operation": OperationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDistributionsResultTypeDef = TypedDict(
     "GetDistributionsResultTypeDef",
     {
         "distributions": List[LightsailDistributionTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ContainerServiceTypeDef = TypedDict(
     "ContainerServiceTypeDef",
     {
         "containerServiceName": str,
@@ -5064,15 +5309,15 @@
     total=False,
 )
 
 GetContainerServiceDeploymentsResultTypeDef = TypedDict(
     "GetContainerServiceDeploymentsResultTypeDef",
     {
         "deployments": List[ContainerServiceDeploymentTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateContainerServiceRequestRequestTypeDef = TypedDict(
     "_RequiredCreateContainerServiceRequestRequestTypeDef",
     {
         "serviceName": str,
@@ -5087,20 +5332,22 @@
         "publicDomainNames": Mapping[str, Sequence[str]],
         "deployment": ContainerServiceDeploymentRequestTypeDef,
         "privateRegistryAccess": PrivateRegistryAccessRequestTypeDef,
     },
     total=False,
 )
 
+
 class CreateContainerServiceRequestRequestTypeDef(
     _RequiredCreateContainerServiceRequestRequestTypeDef,
     _OptionalCreateContainerServiceRequestRequestTypeDef,
 ):
     pass
 
+
 ExportSnapshotRecordTypeDef = TypedDict(
     "ExportSnapshotRecordTypeDef",
     {
         "name": str,
         "arn": str,
         "createdAt": datetime,
         "location": ResourceLocationTypeDef,
@@ -5136,94 +5383,106 @@
         "revocationReason": str,
         "tags": List[TagTypeDef],
         "supportCode": str,
     },
     total=False,
 )
 
+ResourceBudgetEstimateTypeDef = TypedDict(
+    "ResourceBudgetEstimateTypeDef",
+    {
+        "resourceName": str,
+        "resourceType": ResourceTypeType,
+        "costEstimates": List[CostEstimateTypeDef],
+        "startTime": datetime,
+        "endTime": datetime,
+    },
+    total=False,
+)
+
 GetLoadBalancerTlsCertificatesResultTypeDef = TypedDict(
     "GetLoadBalancerTlsCertificatesResultTypeDef",
     {
         "tlsCertificates": List[LoadBalancerTlsCertificateTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDomainResultTypeDef = TypedDict(
     "GetDomainResultTypeDef",
     {
         "domain": DomainTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDomainsResultTypeDef = TypedDict(
     "GetDomainsResultTypeDef",
     {
         "domains": List[DomainTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetInstanceResultTypeDef = TypedDict(
     "GetInstanceResultTypeDef",
     {
         "instance": InstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetInstancesResultTypeDef = TypedDict(
     "GetInstancesResultTypeDef",
     {
         "instances": List[InstanceTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ContainerServicesListResultTypeDef = TypedDict(
     "ContainerServicesListResultTypeDef",
     {
         "containerServices": List[ContainerServiceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateContainerServiceDeploymentResultTypeDef = TypedDict(
     "CreateContainerServiceDeploymentResultTypeDef",
     {
         "containerService": ContainerServiceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateContainerServiceResultTypeDef = TypedDict(
     "CreateContainerServiceResultTypeDef",
     {
         "containerService": ContainerServiceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateContainerServiceResultTypeDef = TypedDict(
     "UpdateContainerServiceResultTypeDef",
     {
         "containerService": ContainerServiceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetExportSnapshotRecordsResultTypeDef = TypedDict(
     "GetExportSnapshotRecordsResultTypeDef",
     {
         "exportSnapshotRecords": List[ExportSnapshotRecordTypeDef],
         "nextPageToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CertificateSummaryTypeDef = TypedDict(
     "CertificateSummaryTypeDef",
     {
         "certificateArn": str,
@@ -5231,23 +5490,32 @@
         "domainName": str,
         "certificateDetail": CertificateTypeDef,
         "tags": List[TagTypeDef],
     },
     total=False,
 )
 
+GetCostEstimateResultTypeDef = TypedDict(
+    "GetCostEstimateResultTypeDef",
+    {
+        "resourcesBudgetEstimate": List[ResourceBudgetEstimateTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CreateCertificateResultTypeDef = TypedDict(
     "CreateCertificateResultTypeDef",
     {
         "certificate": CertificateSummaryTypeDef,
         "operations": List[OperationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetCertificatesResultTypeDef = TypedDict(
     "GetCertificatesResultTypeDef",
     {
         "certificates": List[CertificateSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "nextPageToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-lightsail-2.5.0.post1/types_aiobotocore_lightsail.egg-info/PKG-INFO` & `types-aiobotocore-lightsail-2.5.1/README.md`

 * *Files 4% similar despite different names*

```diff
@@ -1,62 +1,29 @@
-Metadata-Version: 2.1
-Name: types-aiobotocore-lightsail
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Lightsail 2.5.0 service generated with mypy-boto3-builder 7.13.0
-Home-page: https://github.com/youtype/mypy_boto3_builder
-Author: Vlad Emelianov
-Author-email: vlad.emelianov.nz@gmail.com
-License: MIT License
-Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/
-Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
-Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
-Keywords: aiobotocore lightsail type-annotations boto3-stubs mypy typeshed autocomplete
-Classifier: Development Status :: 5 - Production/Stable
-Classifier: Intended Audience :: Developers
-Classifier: Environment :: Console
-Classifier: License :: OSI Approved :: MIT License
-Classifier: Natural Language :: English
-Classifier: Operating System :: OS Independent
-Classifier: Programming Language :: Python :: 3
-Classifier: Programming Language :: Python :: 3.7
-Classifier: Programming Language :: Python :: 3.7
-Classifier: Programming Language :: Python :: 3.8
-Classifier: Programming Language :: Python :: 3.9
-Classifier: Programming Language :: Python :: 3.10
-Classifier: Programming Language :: Python :: 3.11
-Classifier: Programming Language :: Python :: 3.12
-Classifier: Programming Language :: Python :: 3 :: Only
-Classifier: Programming Language :: Python :: Implementation :: CPython
-Classifier: Typing :: Typed
-Requires-Python: >=3.7
-Description-Content-Type: text/markdown
-License-File: LICENSE
-
 <a id="types-aiobotocore-lightsail"></a>
 
 # types-aiobotocore-lightsail
 
 [![PyPI - types-aiobotocore-lightsail](https://img.shields.io/pypi/v/types-aiobotocore-lightsail.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lightsail)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-lightsail.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lightsail)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-lightsail?color=blue)](https://pypistats.org/packages/types-aiobotocore-lightsail)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Lightsail 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail)
+[aiobotocore.Lightsail 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/lightsail.html#Lightsail)
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
 [types-aiobotocore-lightsail docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lightsail/).
 
 See how it helps to find and fix potential bugs:
 
@@ -359,14 +326,16 @@
 ```python
 from types_aiobotocore_lightsail.literals import (
     AccessDirectionType,
     AccessTypeType,
     AccountLevelBpaSyncStatusType,
     AddOnTypeType,
     AlarmStateType,
+    AppCategoryType,
+    AutoMountStatusType,
     AutoSnapshotStatusType,
     BPAStatusMessageType,
     BehaviorEnumType,
     BlueprintTypeType,
     BucketMetricNameType,
     CertificateDomainValidationStatusType,
     CertificateStatusType,
@@ -377,14 +346,15 @@
     ContactProtocolType,
     ContainerServiceDeploymentStateType,
     ContainerServiceMetricNameType,
     ContainerServicePowerNameType,
     ContainerServiceProtocolType,
     ContainerServiceStateDetailCodeType,
     ContainerServiceStateType,
+    CurrencyType,
     DiskSnapshotStateType,
     DiskStateType,
     DistributionMetricNameType,
     DnsRecordCreationStateCodeType,
     ExportSnapshotRecordSourceTypeType,
     ForwardValuesType,
     GetActiveNamesPaginatorName,
@@ -436,23 +406,25 @@
     NetworkProtocolType,
     OperationStatusType,
     OperationTypeType,
     OriginProtocolPolicyEnumType,
     PortAccessTypeType,
     PortInfoSourceTypeType,
     PortStateType,
+    PricingUnitType,
     R53HostedZoneDeletionStateCodeType,
     RecordStateType,
     RegionNameType,
     RelationalDatabaseEngineType,
     RelationalDatabaseMetricNameType,
     RelationalDatabasePasswordVersionType,
     RenewalStatusType,
     ResourceBucketAccessType,
     ResourceTypeType,
+    StatusType,
     StatusTypeType,
     TreatMissingDataType,
     LightsailServiceName,
     ServiceName,
     ResourceServiceName,
     PaginatorName,
     RegionName,
@@ -472,19 +444,19 @@
 
 ```python
 from types_aiobotocore_lightsail.type_defs import (
     AccessKeyLastUsedTypeDef,
     AccessRulesTypeDef,
     AccountLevelBpaSyncTypeDef,
     AutoSnapshotAddOnRequestTypeDef,
+    StopInstanceOnIdleRequestTypeDef,
     AddOnTypeDef,
     MonitoredResourceInfoTypeDef,
     ResourceLocationTypeDef,
     AllocateStaticIpRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     AttachCertificateToDistributionRequestRequestTypeDef,
     AttachDiskRequestRequestTypeDef,
     AttachInstancesToLoadBalancerRequestRequestTypeDef,
     AttachLoadBalancerTlsCertificateRequestRequestTypeDef,
     AttachStaticIpRequestRequestTypeDef,
     AttachedDiskTypeDef,
     AvailabilityZoneTypeDef,
@@ -514,14 +486,16 @@
     ContainerServiceStateDetailTypeDef,
     CopySnapshotRequestRequestTypeDef,
     CreateBucketAccessKeyRequestRequestTypeDef,
     InstanceEntryTypeDef,
     CreateContactMethodRequestRequestTypeDef,
     InputOriginTypeDef,
     DomainEntryTypeDef,
+    CreateGUISessionAccessDetailsRequestRequestTypeDef,
+    SessionTypeDef,
     DiskMapTypeDef,
     DeleteAlarmRequestRequestTypeDef,
     DeleteAutoSnapshotRequestRequestTypeDef,
     DeleteBucketAccessKeyRequestRequestTypeDef,
     DeleteBucketRequestRequestTypeDef,
     DeleteCertificateRequestRequestTypeDef,
     DeleteContactMethodRequestRequestTypeDef,
@@ -545,113 +519,145 @@
     DetachStaticIpRequestRequestTypeDef,
     DisableAddOnRequestRequestTypeDef,
     DiskInfoTypeDef,
     DiskSnapshotInfoTypeDef,
     DistributionBundleTypeDef,
     DnsRecordCreationStateTypeDef,
     ResourceRecordTypeDef,
+    DownloadDefaultKeyPairResultTypeDef,
+    TimePeriodTypeDef,
     ExportSnapshotRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetActiveNamesRequestGetActiveNamesPaginateTypeDef,
     GetActiveNamesRequestRequestTypeDef,
+    GetActiveNamesResultTypeDef,
     GetAlarmsRequestRequestTypeDef,
     GetAutoSnapshotsRequestRequestTypeDef,
+    GetBlueprintsRequestGetBlueprintsPaginateTypeDef,
     GetBlueprintsRequestRequestTypeDef,
     GetBucketAccessKeysRequestRequestTypeDef,
     GetBucketBundlesRequestRequestTypeDef,
     GetBucketMetricDataRequestRequestTypeDef,
     MetricDatapointTypeDef,
     GetBucketsRequestRequestTypeDef,
+    GetBundlesRequestGetBundlesPaginateTypeDef,
     GetBundlesRequestRequestTypeDef,
     GetCertificatesRequestRequestTypeDef,
+    GetCloudFormationStackRecordsRequestGetCloudFormationStackRecordsPaginateTypeDef,
     GetCloudFormationStackRecordsRequestRequestTypeDef,
     GetContactMethodsRequestRequestTypeDef,
+    GetContainerAPIMetadataResultTypeDef,
     GetContainerImagesRequestRequestTypeDef,
     GetContainerLogRequestRequestTypeDef,
     GetContainerServiceDeploymentsRequestRequestTypeDef,
     GetContainerServiceMetricDataRequestRequestTypeDef,
     GetContainerServicesRequestRequestTypeDef,
+    GetCostEstimateRequestRequestTypeDef,
     GetDiskRequestRequestTypeDef,
     GetDiskSnapshotRequestRequestTypeDef,
+    GetDiskSnapshotsRequestGetDiskSnapshotsPaginateTypeDef,
     GetDiskSnapshotsRequestRequestTypeDef,
+    GetDisksRequestGetDisksPaginateTypeDef,
     GetDisksRequestRequestTypeDef,
     GetDistributionLatestCacheResetRequestRequestTypeDef,
+    GetDistributionLatestCacheResetResultTypeDef,
     GetDistributionMetricDataRequestRequestTypeDef,
     GetDistributionsRequestRequestTypeDef,
     GetDomainRequestRequestTypeDef,
+    GetDomainsRequestGetDomainsPaginateTypeDef,
     GetDomainsRequestRequestTypeDef,
+    GetExportSnapshotRecordsRequestGetExportSnapshotRecordsPaginateTypeDef,
     GetExportSnapshotRecordsRequestRequestTypeDef,
     GetInstanceAccessDetailsRequestRequestTypeDef,
     GetInstanceMetricDataRequestRequestTypeDef,
     GetInstancePortStatesRequestRequestTypeDef,
     InstancePortStateTypeDef,
     GetInstanceRequestRequestTypeDef,
     GetInstanceSnapshotRequestRequestTypeDef,
+    GetInstanceSnapshotsRequestGetInstanceSnapshotsPaginateTypeDef,
     GetInstanceSnapshotsRequestRequestTypeDef,
     GetInstanceStateRequestRequestTypeDef,
     InstanceStateTypeDef,
+    GetInstancesRequestGetInstancesPaginateTypeDef,
     GetInstancesRequestRequestTypeDef,
     GetKeyPairRequestRequestTypeDef,
+    GetKeyPairsRequestGetKeyPairsPaginateTypeDef,
     GetKeyPairsRequestRequestTypeDef,
     GetLoadBalancerMetricDataRequestRequestTypeDef,
     GetLoadBalancerRequestRequestTypeDef,
     GetLoadBalancerTlsCertificatesRequestRequestTypeDef,
     GetLoadBalancerTlsPoliciesRequestRequestTypeDef,
     LoadBalancerTlsPolicyTypeDef,
+    GetLoadBalancersRequestGetLoadBalancersPaginateTypeDef,
     GetLoadBalancersRequestRequestTypeDef,
     GetOperationRequestRequestTypeDef,
     GetOperationsForResourceRequestRequestTypeDef,
+    GetOperationsRequestGetOperationsPaginateTypeDef,
     GetOperationsRequestRequestTypeDef,
     GetRegionsRequestRequestTypeDef,
+    GetRelationalDatabaseBlueprintsRequestGetRelationalDatabaseBlueprintsPaginateTypeDef,
     GetRelationalDatabaseBlueprintsRequestRequestTypeDef,
     RelationalDatabaseBlueprintTypeDef,
+    GetRelationalDatabaseBundlesRequestGetRelationalDatabaseBundlesPaginateTypeDef,
     GetRelationalDatabaseBundlesRequestRequestTypeDef,
     RelationalDatabaseBundleTypeDef,
+    GetRelationalDatabaseEventsRequestGetRelationalDatabaseEventsPaginateTypeDef,
     GetRelationalDatabaseEventsRequestRequestTypeDef,
     RelationalDatabaseEventTypeDef,
     GetRelationalDatabaseLogEventsRequestRequestTypeDef,
     LogEventTypeDef,
     GetRelationalDatabaseLogStreamsRequestRequestTypeDef,
+    GetRelationalDatabaseLogStreamsResultTypeDef,
     GetRelationalDatabaseMasterUserPasswordRequestRequestTypeDef,
+    GetRelationalDatabaseMasterUserPasswordResultTypeDef,
     GetRelationalDatabaseMetricDataRequestRequestTypeDef,
+    GetRelationalDatabaseParametersRequestGetRelationalDatabaseParametersPaginateTypeDef,
     GetRelationalDatabaseParametersRequestRequestTypeDef,
     RelationalDatabaseParameterTypeDef,
     GetRelationalDatabaseRequestRequestTypeDef,
     GetRelationalDatabaseSnapshotRequestRequestTypeDef,
+    GetRelationalDatabaseSnapshotsRequestGetRelationalDatabaseSnapshotsPaginateTypeDef,
     GetRelationalDatabaseSnapshotsRequestRequestTypeDef,
+    GetRelationalDatabasesRequestGetRelationalDatabasesPaginateTypeDef,
     GetRelationalDatabasesRequestRequestTypeDef,
     GetStaticIpRequestRequestTypeDef,
+    GetStaticIpsRequestGetStaticIpsPaginateTypeDef,
     GetStaticIpsRequestRequestTypeDef,
     HostKeyAttributesTypeDef,
     ImportKeyPairRequestRequestTypeDef,
     PasswordDataTypeDef,
     InstanceHealthSummaryTypeDef,
     InstanceMetadataOptionsTypeDef,
     InstancePortInfoTypeDef,
     MonthlyTransferTypeDef,
+    IsVpcPeeredResultTypeDef,
     OriginTypeDef,
     LoadBalancerTlsCertificateDnsRecordCreationStateTypeDef,
     LoadBalancerTlsCertificateDomainValidationOptionTypeDef,
     LoadBalancerTlsCertificateSummaryTypeDef,
     NameServersUpdateStateTypeDef,
+    PaginatorConfigTypeDef,
     PendingMaintenanceActionTypeDef,
     PendingModifiedRelationalDatabaseValuesTypeDef,
     PutAlarmRequestRequestTypeDef,
     R53HostedZoneDeletionStateTypeDef,
     RebootInstanceRequestRequestTypeDef,
     RebootRelationalDatabaseRequestRequestTypeDef,
     RegisterContainerImageRequestRequestTypeDef,
     RelationalDatabaseEndpointTypeDef,
     RelationalDatabaseHardwareTypeDef,
     ReleaseStaticIpRequestRequestTypeDef,
     ResetDistributionCacheRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     SendContactMethodVerificationRequestRequestTypeDef,
     SetIpAddressTypeRequestRequestTypeDef,
     SetResourceAccessForBucketRequestRequestTypeDef,
+    StartGUISessionRequestRequestTypeDef,
     StartInstanceRequestRequestTypeDef,
     StartRelationalDatabaseRequestRequestTypeDef,
+    StopGUISessionRequestRequestTypeDef,
     StopInstanceRequestRequestTypeDef,
     StopRelationalDatabaseRequestRequestTypeDef,
     TestAlarmRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateBucketBundleRequestRequestTypeDef,
     UpdateDistributionBundleRequestRequestTypeDef,
     UpdateInstanceMetadataOptionsRequestRequestTypeDef,
@@ -659,21 +665,14 @@
     UpdateRelationalDatabaseRequestRequestTypeDef,
     AccessKeyTypeDef,
     AddOnRequestTypeDef,
     AlarmTypeDef,
     ContactMethodTypeDef,
     OperationTypeDef,
     StaticIpTypeDef,
-    DownloadDefaultKeyPairResultTypeDef,
-    GetActiveNamesResultTypeDef,
-    GetContainerAPIMetadataResultTypeDef,
-    GetDistributionLatestCacheResetResultTypeDef,
-    GetRelationalDatabaseLogStreamsResultTypeDef,
-    GetRelationalDatabaseMasterUserPasswordResultTypeDef,
-    IsVpcPeeredResultTypeDef,
     AutoSnapshotDetailsTypeDef,
     RegionTypeDef,
     GetBlueprintsResultTypeDef,
     UpdateBucketRequestRequestTypeDef,
     GetBucketBundlesResultTypeDef,
     BucketTypeDef,
     CreateBucketRequestRequestTypeDef,
@@ -707,37 +706,19 @@
     GetContainerLogResultTypeDef,
     GetContainerServicePowersResultTypeDef,
     CreateContainerServiceRegistryLoginResultTypeDef,
     CreateCloudFormationStackRequestRequestTypeDef,
     CreateDomainEntryRequestRequestTypeDef,
     DeleteDomainEntryRequestRequestTypeDef,
     UpdateDomainEntryRequestRequestTypeDef,
+    CreateGUISessionAccessDetailsResultTypeDef,
     InstanceSnapshotInfoTypeDef,
     GetDistributionBundlesResultTypeDef,
     DomainValidationRecordTypeDef,
-    GetActiveNamesRequestGetActiveNamesPaginateTypeDef,
-    GetBlueprintsRequestGetBlueprintsPaginateTypeDef,
-    GetBundlesRequestGetBundlesPaginateTypeDef,
-    GetCloudFormationStackRecordsRequestGetCloudFormationStackRecordsPaginateTypeDef,
-    GetDiskSnapshotsRequestGetDiskSnapshotsPaginateTypeDef,
-    GetDisksRequestGetDisksPaginateTypeDef,
-    GetDomainsRequestGetDomainsPaginateTypeDef,
-    GetExportSnapshotRecordsRequestGetExportSnapshotRecordsPaginateTypeDef,
-    GetInstanceSnapshotsRequestGetInstanceSnapshotsPaginateTypeDef,
-    GetInstancesRequestGetInstancesPaginateTypeDef,
-    GetKeyPairsRequestGetKeyPairsPaginateTypeDef,
-    GetLoadBalancersRequestGetLoadBalancersPaginateTypeDef,
-    GetOperationsRequestGetOperationsPaginateTypeDef,
-    GetRelationalDatabaseBlueprintsRequestGetRelationalDatabaseBlueprintsPaginateTypeDef,
-    GetRelationalDatabaseBundlesRequestGetRelationalDatabaseBundlesPaginateTypeDef,
-    GetRelationalDatabaseEventsRequestGetRelationalDatabaseEventsPaginateTypeDef,
-    GetRelationalDatabaseParametersRequestGetRelationalDatabaseParametersPaginateTypeDef,
-    GetRelationalDatabaseSnapshotsRequestGetRelationalDatabaseSnapshotsPaginateTypeDef,
-    GetRelationalDatabasesRequestGetRelationalDatabasesPaginateTypeDef,
-    GetStaticIpsRequestGetStaticIpsPaginateTypeDef,
+    EstimateByTimeTypeDef,
     GetBucketMetricDataResultTypeDef,
     GetContainerServiceMetricDataResultTypeDef,
     GetDistributionMetricDataResultTypeDef,
     GetInstanceMetricDataResultTypeDef,
     GetLoadBalancerMetricDataResultTypeDef,
     GetRelationalDatabaseMetricDataResultTypeDef,
     GetInstancePortStatesResultTypeDef,
@@ -825,16 +806,18 @@
     RebootInstanceResultTypeDef,
     RebootRelationalDatabaseResultTypeDef,
     ReleaseStaticIpResultTypeDef,
     ResetDistributionCacheResultTypeDef,
     SendContactMethodVerificationResultTypeDef,
     SetIpAddressTypeResultTypeDef,
     SetResourceAccessForBucketResultTypeDef,
+    StartGUISessionResultTypeDef,
     StartInstanceResultTypeDef,
     StartRelationalDatabaseResultTypeDef,
+    StopGUISessionResultTypeDef,
     StopInstanceResultTypeDef,
     StopRelationalDatabaseResultTypeDef,
     TagResourceResultTypeDef,
     TestAlarmResultTypeDef,
     UnpeerVpcResultTypeDef,
     UntagResourceResultTypeDef,
     UpdateBucketBundleResultTypeDef,
@@ -869,14 +852,15 @@
     GetCloudFormationStackRecordsResultTypeDef,
     UpdateContainerServiceRequestRequestTypeDef,
     ContainerServiceDeploymentTypeDef,
     ContainerServiceDeploymentRequestTypeDef,
     CreateContainerServiceDeploymentRequestRequestTypeDef,
     ExportSnapshotRecordSourceInfoTypeDef,
     RenewalSummaryTypeDef,
+    CostEstimateTypeDef,
     GetInstanceAccessDetailsResultTypeDef,
     LoadBalancerTlsCertificateTypeDef,
     GetLoadBalancerResultTypeDef,
     GetLoadBalancersResultTypeDef,
     DomainTypeDef,
     GetRelationalDatabaseResultTypeDef,
     GetRelationalDatabasesResultTypeDef,
@@ -886,25 +870,27 @@
     CreateDistributionResultTypeDef,
     GetDistributionsResultTypeDef,
     ContainerServiceTypeDef,
     GetContainerServiceDeploymentsResultTypeDef,
     CreateContainerServiceRequestRequestTypeDef,
     ExportSnapshotRecordTypeDef,
     CertificateTypeDef,
+    ResourceBudgetEstimateTypeDef,
     GetLoadBalancerTlsCertificatesResultTypeDef,
     GetDomainResultTypeDef,
     GetDomainsResultTypeDef,
     GetInstanceResultTypeDef,
     GetInstancesResultTypeDef,
     ContainerServicesListResultTypeDef,
     CreateContainerServiceDeploymentResultTypeDef,
     CreateContainerServiceResultTypeDef,
     UpdateContainerServiceResultTypeDef,
     GetExportSnapshotRecordsResultTypeDef,
     CertificateSummaryTypeDef,
+    GetCostEstimateResultTypeDef,
     CreateCertificateResultTypeDef,
     GetCertificatesResultTypeDef,
 )
 
 
 def get_structure() -> AccessKeyLastUsedTypeDef:
     return {...}
@@ -913,43 +899,43 @@
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

### Comparing `types-aiobotocore-lightsail-2.5.0.post1/types_aiobotocore_lightsail.egg-info/SOURCES.txt` & `types-aiobotocore-lightsail-2.5.1/types_aiobotocore_lightsail.egg-info/SOURCES.txt`

 * *Files identical despite different names*

