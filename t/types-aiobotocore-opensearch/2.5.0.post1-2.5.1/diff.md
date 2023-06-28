# Comparing `tmp/types-aiobotocore-opensearch-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-opensearch-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-opensearch-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:03 2023, max compression
+gzip compressed data, was "types-aiobotocore-opensearch-2.5.1.tar", last modified: Wed Jun 28 01:43:55 2023, max compression
```

## Comparing `types-aiobotocore-opensearch-2.5.0.post1.tar` & `types-aiobotocore-opensearch-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:03.939468 types-aiobotocore-opensearch-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:19:23.000000 types-aiobotocore-opensearch-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    19975 2023-03-11 12:27:03.939468 types-aiobotocore-opensearch-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    18385 2023-03-11 12:19:23.000000 types-aiobotocore-opensearch-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:03.939468 types-aiobotocore-opensearch-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2152 2023-03-11 12:19:23.000000 types-aiobotocore-opensearch-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:03.931468 types-aiobotocore-opensearch-2.5.0.post1/types_aiobotocore_opensearch/
--rw-r--r--   0 runner    (1001) docker     (123)      501 2023-03-11 12:19:23.000000 types-aiobotocore-opensearch-2.5.0.post1/types_aiobotocore_opensearch/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      500 2023-03-11 12:19:23.000000 types-aiobotocore-opensearch-2.5.0.post1/types_aiobotocore_opensearch/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      969 2023-03-11 12:19:23.000000 types-aiobotocore-opensearch-2.5.0.post1/types_aiobotocore_opensearch/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    39810 2023-03-11 12:19:23.000000 types-aiobotocore-opensearch-2.5.0.post1/types_aiobotocore_opensearch/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    39751 2023-03-11 12:19:23.000000 types-aiobotocore-opensearch-2.5.0.post1/types_aiobotocore_opensearch/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    14056 2023-03-11 12:19:23.000000 types-aiobotocore-opensearch-2.5.0.post1/types_aiobotocore_opensearch/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    14054 2023-03-11 12:19:23.000000 types-aiobotocore-opensearch-2.5.0.post1/types_aiobotocore_opensearch/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:19:23.000000 types-aiobotocore-opensearch-2.5.0.post1/types_aiobotocore_opensearch/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    60114 2023-03-11 12:19:24.000000 types-aiobotocore-opensearch-2.5.0.post1/types_aiobotocore_opensearch/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    60065 2023-03-11 12:19:24.000000 types-aiobotocore-opensearch-2.5.0.post1/types_aiobotocore_opensearch/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:19:23.000000 types-aiobotocore-opensearch-2.5.0.post1/types_aiobotocore_opensearch/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:03.939468 types-aiobotocore-opensearch-2.5.0.post1/types_aiobotocore_opensearch.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    19975 2023-03-11 12:27:03.000000 types-aiobotocore-opensearch-2.5.0.post1/types_aiobotocore_opensearch.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      785 2023-03-11 12:27:03.000000 types-aiobotocore-opensearch-2.5.0.post1/types_aiobotocore_opensearch.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:03.000000 types-aiobotocore-opensearch-2.5.0.post1/types_aiobotocore_opensearch.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:03.000000 types-aiobotocore-opensearch-2.5.0.post1/types_aiobotocore_opensearch.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:03.000000 types-aiobotocore-opensearch-2.5.0.post1/types_aiobotocore_opensearch.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       29 2023-03-11 12:27:03.000000 types-aiobotocore-opensearch-2.5.0.post1/types_aiobotocore_opensearch.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:55.766186 types-aiobotocore-opensearch-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:36:08.000000 types-aiobotocore-opensearch-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    20951 2023-06-28 01:43:55.746186 types-aiobotocore-opensearch-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    19367 2023-06-28 01:36:08.000000 types-aiobotocore-opensearch-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:55.766186 types-aiobotocore-opensearch-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2146 2023-06-28 01:36:08.000000 types-aiobotocore-opensearch-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:55.746186 types-aiobotocore-opensearch-2.5.1/types_aiobotocore_opensearch/
+-rw-r--r--   0 runner    (1001) docker     (123)      501 2023-06-28 01:36:08.000000 types-aiobotocore-opensearch-2.5.1/types_aiobotocore_opensearch/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      500 2023-06-28 01:36:08.000000 types-aiobotocore-opensearch-2.5.1/types_aiobotocore_opensearch/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      957 2023-06-28 01:36:08.000000 types-aiobotocore-opensearch-2.5.1/types_aiobotocore_opensearch/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    43479 2023-06-28 01:36:08.000000 types-aiobotocore-opensearch-2.5.1/types_aiobotocore_opensearch/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    43416 2023-06-28 01:36:08.000000 types-aiobotocore-opensearch-2.5.1/types_aiobotocore_opensearch/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    15352 2023-06-28 01:36:09.000000 types-aiobotocore-opensearch-2.5.1/types_aiobotocore_opensearch/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15350 2023-06-28 01:36:08.000000 types-aiobotocore-opensearch-2.5.1/types_aiobotocore_opensearch/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:36:08.000000 types-aiobotocore-opensearch-2.5.1/types_aiobotocore_opensearch/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    68145 2023-06-28 01:36:10.000000 types-aiobotocore-opensearch-2.5.1/types_aiobotocore_opensearch/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    68088 2023-06-28 01:36:09.000000 types-aiobotocore-opensearch-2.5.1/types_aiobotocore_opensearch/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:36:08.000000 types-aiobotocore-opensearch-2.5.1/types_aiobotocore_opensearch/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:55.746186 types-aiobotocore-opensearch-2.5.1/types_aiobotocore_opensearch.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    20951 2023-06-28 01:43:55.000000 types-aiobotocore-opensearch-2.5.1/types_aiobotocore_opensearch.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      785 2023-06-28 01:43:55.000000 types-aiobotocore-opensearch-2.5.1/types_aiobotocore_opensearch.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:55.000000 types-aiobotocore-opensearch-2.5.1/types_aiobotocore_opensearch.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:55.000000 types-aiobotocore-opensearch-2.5.1/types_aiobotocore_opensearch.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:55.000000 types-aiobotocore-opensearch-2.5.1/types_aiobotocore_opensearch.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       29 2023-06-28 01:43:55.000000 types-aiobotocore-opensearch-2.5.1/types_aiobotocore_opensearch.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-opensearch-2.5.0.post1/LICENSE` & `types-aiobotocore-opensearch-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-opensearch-2.5.0.post1/PKG-INFO` & `types-aiobotocore-opensearch-2.5.1/PKG-INFO`

 * *Files 6% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-opensearch
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.OpenSearchService 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.OpenSearchService 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-opensearch"></a>
 
 # types-aiobotocore-opensearch
 
 [![PyPI - types-aiobotocore-opensearch](https://img.shields.io/pypi/v/types-aiobotocore-opensearch.svg?color=blue)](https://pypi.org/project/types-aiobotocore-opensearch)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-opensearch.svg?color=blue)](https://pypi.org/project/types-aiobotocore-opensearch)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-opensearch?color=blue)](https://pypistats.org/packages/types-aiobotocore-opensearch)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.OpenSearchService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearch.html#OpenSearchService)
+[aiobotocore.OpenSearchService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearch.html#OpenSearchService)
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
 [types-aiobotocore-opensearch docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/).
 
 See how it helps to find and fix potential bugs:
 
@@ -269,105 +269,121 @@
 ### Literals
 
 `types_aiobotocore_opensearch.literals` module contains literals extracted from
 shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_opensearch.literals import (
+    ActionSeverityType,
+    ActionStatusType,
+    ActionTypeType,
     AutoTuneDesiredStateType,
     AutoTuneStateType,
     AutoTuneTypeType,
     ConnectionModeType,
     DeploymentStatusType,
     DescribePackagesFilterNameType,
+    DomainHealthType,
     DomainPackageStatusType,
+    DomainStateType,
     DryRunModeType,
     EngineTypeType,
     InboundConnectionStatusCodeType,
     LogTypeType,
+    MasterNodeStatusType,
+    NodeStatusType,
+    NodeTypeType,
     OpenSearchPartitionInstanceTypeType,
     OpenSearchWarmPartitionInstanceTypeType,
     OptionStateType,
     OutboundConnectionStatusCodeType,
     OverallChangeStatusType,
     PackageStatusType,
     PackageTypeType,
     PrincipalTypeType,
     ReservedInstancePaymentOptionType,
     RollbackOnDisableType,
+    ScheduleAtType,
     ScheduledAutoTuneActionTypeType,
     ScheduledAutoTuneSeverityTypeType,
+    ScheduledByType,
+    SkipUnavailableStatusType,
     TLSSecurityPolicyType,
     TimeUnitType,
     UpgradeStatusType,
     UpgradeStepType,
     VolumeTypeType,
     VpcEndpointErrorCodeType,
     VpcEndpointStatusType,
+    ZoneStatusType,
     OpenSearchServiceServiceName,
     ServiceName,
     ResourceServiceName,
     RegionName,
 )
 
 
-def check_value(value: AutoTuneDesiredStateType) -> bool:
+def check_value(value: ActionSeverityType) -> bool:
     ...
 ```
 
 <a id="typed-dictionaries"></a>
 
 ### Typed dictionaries
 
 `types_aiobotocore_opensearch.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_opensearch.type_defs import (
     AWSDomainInformationTypeDef,
     AcceptInboundConnectionRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     OptionStatusTypeDef,
     TagTypeDef,
     AdditionalLimitTypeDef,
     MasterUserOptionsTypeDef,
     AssociatePackageRequestRequestTypeDef,
     AuthorizeVpcEndpointAccessRequestRequestTypeDef,
     AuthorizedPrincipalTypeDef,
     ScheduledAutoTuneDetailsTypeDef,
     DurationTypeDef,
     AutoTuneOptionsOutputTypeDef,
     AutoTuneStatusTypeDef,
+    AvailabilityZoneInfoTypeDef,
     CancelServiceSoftwareUpdateRequestRequestTypeDef,
     ServiceSoftwareOptionsTypeDef,
     ChangeProgressDetailsTypeDef,
     ChangeProgressStageTypeDef,
     ColdStorageOptionsTypeDef,
     ZoneAwarenessConfigTypeDef,
     CognitoOptionsTypeDef,
     CompatibleVersionsMapTypeDef,
-    ConnectionPropertiesTypeDef,
+    CrossClusterSearchConnectionPropertiesTypeDef,
     DomainEndpointOptionsTypeDef,
     EBSOptionsTypeDef,
     EncryptionAtRestOptionsTypeDef,
     LogPublishingOptionTypeDef,
     NodeToNodeEncryptionOptionsTypeDef,
     SnapshotOptionsTypeDef,
+    SoftwareUpdateOptionsTypeDef,
     VPCOptionsTypeDef,
     OutboundConnectionStatusTypeDef,
     PackageSourceTypeDef,
     DeleteDomainRequestRequestTypeDef,
     DeleteInboundConnectionRequestRequestTypeDef,
     DeleteOutboundConnectionRequestRequestTypeDef,
     DeletePackageRequestRequestTypeDef,
     DeleteVpcEndpointRequestRequestTypeDef,
     VpcEndpointSummaryTypeDef,
     DescribeDomainAutoTunesRequestRequestTypeDef,
     DescribeDomainChangeProgressRequestRequestTypeDef,
     DescribeDomainConfigRequestRequestTypeDef,
+    DescribeDomainHealthRequestRequestTypeDef,
+    DescribeDomainNodesRequestRequestTypeDef,
+    DomainNodesStatusTypeDef,
     DescribeDomainRequestRequestTypeDef,
     DescribeDomainsRequestRequestTypeDef,
     DescribeDryRunProgressRequestRequestTypeDef,
     DryRunResultsTypeDef,
     FilterTypeDef,
     DescribeInstanceTypeLimitsRequestRequestTypeDef,
     DescribePackagesFilterTypeDef,
@@ -376,127 +392,142 @@
     DescribeVpcEndpointsRequestRequestTypeDef,
     VpcEndpointErrorTypeDef,
     DissociatePackageRequestRequestTypeDef,
     DomainInfoTypeDef,
     ErrorDetailsTypeDef,
     VPCDerivedInfoTypeDef,
     ValidationFailureTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetCompatibleVersionsRequestRequestTypeDef,
     GetPackageVersionHistoryRequestRequestTypeDef,
     PackageVersionHistoryTypeDef,
     GetUpgradeHistoryRequestRequestTypeDef,
     GetUpgradeStatusRequestRequestTypeDef,
+    GetUpgradeStatusResponseTypeDef,
     InboundConnectionStatusTypeDef,
     InstanceCountLimitsTypeDef,
     InstanceTypeDetailsTypeDef,
     ListDomainNamesRequestRequestTypeDef,
     ListDomainsForPackageRequestRequestTypeDef,
     ListInstanceTypeDetailsRequestRequestTypeDef,
     ListPackagesForDomainRequestRequestTypeDef,
+    ListScheduledActionsRequestRequestTypeDef,
+    ScheduledActionTypeDef,
     ListTagsRequestRequestTypeDef,
     ListVersionsRequestRequestTypeDef,
+    ListVersionsResponseTypeDef,
     ListVpcEndpointAccessRequestRequestTypeDef,
     ListVpcEndpointsForDomainRequestRequestTypeDef,
     ListVpcEndpointsRequestRequestTypeDef,
+    WindowStartTimeTypeDef,
     PurchaseReservedInstanceOfferingRequestRequestTypeDef,
+    PurchaseReservedInstanceOfferingResponseTypeDef,
     RecurringChargeTypeDef,
     RejectInboundConnectionRequestRequestTypeDef,
     RemoveTagsRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     RevokeVpcEndpointAccessRequestRequestTypeDef,
     SAMLIdpTypeDef,
     StartServiceSoftwareUpdateRequestRequestTypeDef,
     StorageTypeLimitTypeDef,
+    UpdateScheduledActionRequestRequestTypeDef,
     UpgradeDomainRequestRequestTypeDef,
     UpgradeStepItemTypeDef,
     DomainInformationContainerTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetUpgradeStatusResponseTypeDef,
-    ListVersionsResponseTypeDef,
-    PurchaseReservedInstanceOfferingResponseTypeDef,
     AccessPoliciesStatusTypeDef,
     AdvancedOptionsStatusTypeDef,
     VersionStatusTypeDef,
     AddTagsRequestRequestTypeDef,
     ListTagsResponseTypeDef,
     AuthorizeVpcEndpointAccessResponseTypeDef,
     ListVpcEndpointAccessResponseTypeDef,
     AutoTuneDetailsTypeDef,
     AutoTuneMaintenanceScheduleTypeDef,
+    EnvironmentInfoTypeDef,
     CancelServiceSoftwareUpdateResponseTypeDef,
     StartServiceSoftwareUpdateResponseTypeDef,
     UpgradeDomainResponseTypeDef,
     ChangeProgressStatusDetailsTypeDef,
     ClusterConfigTypeDef,
     CognitoOptionsStatusTypeDef,
     GetCompatibleVersionsResponseTypeDef,
+    ConnectionPropertiesTypeDef,
     DomainEndpointOptionsStatusTypeDef,
     EBSOptionsStatusTypeDef,
     EncryptionAtRestOptionsStatusTypeDef,
     LogPublishingOptionsStatusTypeDef,
     NodeToNodeEncryptionOptionsStatusTypeDef,
     SnapshotOptionsStatusTypeDef,
+    SoftwareUpdateOptionsStatusTypeDef,
     CreateVpcEndpointRequestRequestTypeDef,
     UpdateVpcEndpointRequestRequestTypeDef,
     CreatePackageRequestRequestTypeDef,
     UpdatePackageRequestRequestTypeDef,
     DeleteVpcEndpointResponseTypeDef,
     ListVpcEndpointsForDomainResponseTypeDef,
     ListVpcEndpointsResponseTypeDef,
+    DescribeDomainNodesResponseTypeDef,
     DescribeInboundConnectionsRequestRequestTypeDef,
     DescribeOutboundConnectionsRequestRequestTypeDef,
     DescribePackagesRequestRequestTypeDef,
     ListDomainNamesResponseTypeDef,
     DomainPackageDetailsTypeDef,
     PackageDetailsTypeDef,
     VPCDerivedInfoStatusTypeDef,
     VpcEndpointTypeDef,
     DryRunProgressStatusTypeDef,
     GetPackageVersionHistoryResponseTypeDef,
     InstanceLimitsTypeDef,
     ListInstanceTypeDetailsResponseTypeDef,
+    ListScheduledActionsResponseTypeDef,
+    UpdateScheduledActionResponseTypeDef,
+    OffPeakWindowTypeDef,
     ReservedInstanceOfferingTypeDef,
     ReservedInstanceTypeDef,
     SAMLOptionsInputTypeDef,
     SAMLOptionsOutputTypeDef,
     StorageTypeTypeDef,
     UpgradeHistoryTypeDef,
-    CreateOutboundConnectionRequestRequestTypeDef,
-    CreateOutboundConnectionResponseTypeDef,
     InboundConnectionTypeDef,
-    OutboundConnectionTypeDef,
     AutoTuneTypeDef,
     AutoTuneOptionsInputTypeDef,
     AutoTuneOptionsTypeDef,
+    DescribeDomainHealthResponseTypeDef,
     DescribeDomainChangeProgressResponseTypeDef,
     ClusterConfigStatusTypeDef,
+    CreateOutboundConnectionRequestRequestTypeDef,
+    CreateOutboundConnectionResponseTypeDef,
+    OutboundConnectionTypeDef,
     AssociatePackageResponseTypeDef,
     DissociatePackageResponseTypeDef,
     ListDomainsForPackageResponseTypeDef,
     ListPackagesForDomainResponseTypeDef,
     CreatePackageResponseTypeDef,
     DeletePackageResponseTypeDef,
     DescribePackagesResponseTypeDef,
     UpdatePackageResponseTypeDef,
     CreateVpcEndpointResponseTypeDef,
     DescribeVpcEndpointsResponseTypeDef,
     UpdateVpcEndpointResponseTypeDef,
+    OffPeakWindowOptionsTypeDef,
     DescribeReservedInstanceOfferingsResponseTypeDef,
     DescribeReservedInstancesResponseTypeDef,
     AdvancedSecurityOptionsInputTypeDef,
     AdvancedSecurityOptionsTypeDef,
     LimitsTypeDef,
     GetUpgradeHistoryResponseTypeDef,
     AcceptInboundConnectionResponseTypeDef,
     DeleteInboundConnectionResponseTypeDef,
     DescribeInboundConnectionsResponseTypeDef,
     RejectInboundConnectionResponseTypeDef,
-    DeleteOutboundConnectionResponseTypeDef,
-    DescribeOutboundConnectionsResponseTypeDef,
     DescribeDomainAutoTunesResponseTypeDef,
     AutoTuneOptionsStatusTypeDef,
+    DeleteOutboundConnectionResponseTypeDef,
+    DescribeOutboundConnectionsResponseTypeDef,
+    OffPeakWindowOptionsStatusTypeDef,
     CreateDomainRequestRequestTypeDef,
     UpdateDomainConfigRequestRequestTypeDef,
     AdvancedSecurityOptionsStatusTypeDef,
     DomainStatusTypeDef,
     DescribeInstanceTypeLimitsResponseTypeDef,
     DomainConfigTypeDef,
     CreateDomainResponseTypeDef,
@@ -516,43 +547,43 @@
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

### Comparing `types-aiobotocore-opensearch-2.5.0.post1/README.md` & `types-aiobotocore-opensearch-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-opensearch"></a>
 
 # types-aiobotocore-opensearch
 
 [![PyPI - types-aiobotocore-opensearch](https://img.shields.io/pypi/v/types-aiobotocore-opensearch.svg?color=blue)](https://pypi.org/project/types-aiobotocore-opensearch)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-opensearch.svg?color=blue)](https://pypi.org/project/types-aiobotocore-opensearch)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-opensearch?color=blue)](https://pypistats.org/packages/types-aiobotocore-opensearch)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.OpenSearchService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearch.html#OpenSearchService)
+[aiobotocore.OpenSearchService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearch.html#OpenSearchService)
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
 [types-aiobotocore-opensearch docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/).
 
 See how it helps to find and fix potential bugs:
 
@@ -236,105 +236,121 @@
 ### Literals
 
 `types_aiobotocore_opensearch.literals` module contains literals extracted from
 shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_opensearch.literals import (
+    ActionSeverityType,
+    ActionStatusType,
+    ActionTypeType,
     AutoTuneDesiredStateType,
     AutoTuneStateType,
     AutoTuneTypeType,
     ConnectionModeType,
     DeploymentStatusType,
     DescribePackagesFilterNameType,
+    DomainHealthType,
     DomainPackageStatusType,
+    DomainStateType,
     DryRunModeType,
     EngineTypeType,
     InboundConnectionStatusCodeType,
     LogTypeType,
+    MasterNodeStatusType,
+    NodeStatusType,
+    NodeTypeType,
     OpenSearchPartitionInstanceTypeType,
     OpenSearchWarmPartitionInstanceTypeType,
     OptionStateType,
     OutboundConnectionStatusCodeType,
     OverallChangeStatusType,
     PackageStatusType,
     PackageTypeType,
     PrincipalTypeType,
     ReservedInstancePaymentOptionType,
     RollbackOnDisableType,
+    ScheduleAtType,
     ScheduledAutoTuneActionTypeType,
     ScheduledAutoTuneSeverityTypeType,
+    ScheduledByType,
+    SkipUnavailableStatusType,
     TLSSecurityPolicyType,
     TimeUnitType,
     UpgradeStatusType,
     UpgradeStepType,
     VolumeTypeType,
     VpcEndpointErrorCodeType,
     VpcEndpointStatusType,
+    ZoneStatusType,
     OpenSearchServiceServiceName,
     ServiceName,
     ResourceServiceName,
     RegionName,
 )
 
 
-def check_value(value: AutoTuneDesiredStateType) -> bool:
+def check_value(value: ActionSeverityType) -> bool:
     ...
 ```
 
 <a id="typed-dictionaries"></a>
 
 ### Typed dictionaries
 
 `types_aiobotocore_opensearch.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_opensearch.type_defs import (
     AWSDomainInformationTypeDef,
     AcceptInboundConnectionRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     OptionStatusTypeDef,
     TagTypeDef,
     AdditionalLimitTypeDef,
     MasterUserOptionsTypeDef,
     AssociatePackageRequestRequestTypeDef,
     AuthorizeVpcEndpointAccessRequestRequestTypeDef,
     AuthorizedPrincipalTypeDef,
     ScheduledAutoTuneDetailsTypeDef,
     DurationTypeDef,
     AutoTuneOptionsOutputTypeDef,
     AutoTuneStatusTypeDef,
+    AvailabilityZoneInfoTypeDef,
     CancelServiceSoftwareUpdateRequestRequestTypeDef,
     ServiceSoftwareOptionsTypeDef,
     ChangeProgressDetailsTypeDef,
     ChangeProgressStageTypeDef,
     ColdStorageOptionsTypeDef,
     ZoneAwarenessConfigTypeDef,
     CognitoOptionsTypeDef,
     CompatibleVersionsMapTypeDef,
-    ConnectionPropertiesTypeDef,
+    CrossClusterSearchConnectionPropertiesTypeDef,
     DomainEndpointOptionsTypeDef,
     EBSOptionsTypeDef,
     EncryptionAtRestOptionsTypeDef,
     LogPublishingOptionTypeDef,
     NodeToNodeEncryptionOptionsTypeDef,
     SnapshotOptionsTypeDef,
+    SoftwareUpdateOptionsTypeDef,
     VPCOptionsTypeDef,
     OutboundConnectionStatusTypeDef,
     PackageSourceTypeDef,
     DeleteDomainRequestRequestTypeDef,
     DeleteInboundConnectionRequestRequestTypeDef,
     DeleteOutboundConnectionRequestRequestTypeDef,
     DeletePackageRequestRequestTypeDef,
     DeleteVpcEndpointRequestRequestTypeDef,
     VpcEndpointSummaryTypeDef,
     DescribeDomainAutoTunesRequestRequestTypeDef,
     DescribeDomainChangeProgressRequestRequestTypeDef,
     DescribeDomainConfigRequestRequestTypeDef,
+    DescribeDomainHealthRequestRequestTypeDef,
+    DescribeDomainNodesRequestRequestTypeDef,
+    DomainNodesStatusTypeDef,
     DescribeDomainRequestRequestTypeDef,
     DescribeDomainsRequestRequestTypeDef,
     DescribeDryRunProgressRequestRequestTypeDef,
     DryRunResultsTypeDef,
     FilterTypeDef,
     DescribeInstanceTypeLimitsRequestRequestTypeDef,
     DescribePackagesFilterTypeDef,
@@ -343,127 +359,142 @@
     DescribeVpcEndpointsRequestRequestTypeDef,
     VpcEndpointErrorTypeDef,
     DissociatePackageRequestRequestTypeDef,
     DomainInfoTypeDef,
     ErrorDetailsTypeDef,
     VPCDerivedInfoTypeDef,
     ValidationFailureTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetCompatibleVersionsRequestRequestTypeDef,
     GetPackageVersionHistoryRequestRequestTypeDef,
     PackageVersionHistoryTypeDef,
     GetUpgradeHistoryRequestRequestTypeDef,
     GetUpgradeStatusRequestRequestTypeDef,
+    GetUpgradeStatusResponseTypeDef,
     InboundConnectionStatusTypeDef,
     InstanceCountLimitsTypeDef,
     InstanceTypeDetailsTypeDef,
     ListDomainNamesRequestRequestTypeDef,
     ListDomainsForPackageRequestRequestTypeDef,
     ListInstanceTypeDetailsRequestRequestTypeDef,
     ListPackagesForDomainRequestRequestTypeDef,
+    ListScheduledActionsRequestRequestTypeDef,
+    ScheduledActionTypeDef,
     ListTagsRequestRequestTypeDef,
     ListVersionsRequestRequestTypeDef,
+    ListVersionsResponseTypeDef,
     ListVpcEndpointAccessRequestRequestTypeDef,
     ListVpcEndpointsForDomainRequestRequestTypeDef,
     ListVpcEndpointsRequestRequestTypeDef,
+    WindowStartTimeTypeDef,
     PurchaseReservedInstanceOfferingRequestRequestTypeDef,
+    PurchaseReservedInstanceOfferingResponseTypeDef,
     RecurringChargeTypeDef,
     RejectInboundConnectionRequestRequestTypeDef,
     RemoveTagsRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     RevokeVpcEndpointAccessRequestRequestTypeDef,
     SAMLIdpTypeDef,
     StartServiceSoftwareUpdateRequestRequestTypeDef,
     StorageTypeLimitTypeDef,
+    UpdateScheduledActionRequestRequestTypeDef,
     UpgradeDomainRequestRequestTypeDef,
     UpgradeStepItemTypeDef,
     DomainInformationContainerTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetUpgradeStatusResponseTypeDef,
-    ListVersionsResponseTypeDef,
-    PurchaseReservedInstanceOfferingResponseTypeDef,
     AccessPoliciesStatusTypeDef,
     AdvancedOptionsStatusTypeDef,
     VersionStatusTypeDef,
     AddTagsRequestRequestTypeDef,
     ListTagsResponseTypeDef,
     AuthorizeVpcEndpointAccessResponseTypeDef,
     ListVpcEndpointAccessResponseTypeDef,
     AutoTuneDetailsTypeDef,
     AutoTuneMaintenanceScheduleTypeDef,
+    EnvironmentInfoTypeDef,
     CancelServiceSoftwareUpdateResponseTypeDef,
     StartServiceSoftwareUpdateResponseTypeDef,
     UpgradeDomainResponseTypeDef,
     ChangeProgressStatusDetailsTypeDef,
     ClusterConfigTypeDef,
     CognitoOptionsStatusTypeDef,
     GetCompatibleVersionsResponseTypeDef,
+    ConnectionPropertiesTypeDef,
     DomainEndpointOptionsStatusTypeDef,
     EBSOptionsStatusTypeDef,
     EncryptionAtRestOptionsStatusTypeDef,
     LogPublishingOptionsStatusTypeDef,
     NodeToNodeEncryptionOptionsStatusTypeDef,
     SnapshotOptionsStatusTypeDef,
+    SoftwareUpdateOptionsStatusTypeDef,
     CreateVpcEndpointRequestRequestTypeDef,
     UpdateVpcEndpointRequestRequestTypeDef,
     CreatePackageRequestRequestTypeDef,
     UpdatePackageRequestRequestTypeDef,
     DeleteVpcEndpointResponseTypeDef,
     ListVpcEndpointsForDomainResponseTypeDef,
     ListVpcEndpointsResponseTypeDef,
+    DescribeDomainNodesResponseTypeDef,
     DescribeInboundConnectionsRequestRequestTypeDef,
     DescribeOutboundConnectionsRequestRequestTypeDef,
     DescribePackagesRequestRequestTypeDef,
     ListDomainNamesResponseTypeDef,
     DomainPackageDetailsTypeDef,
     PackageDetailsTypeDef,
     VPCDerivedInfoStatusTypeDef,
     VpcEndpointTypeDef,
     DryRunProgressStatusTypeDef,
     GetPackageVersionHistoryResponseTypeDef,
     InstanceLimitsTypeDef,
     ListInstanceTypeDetailsResponseTypeDef,
+    ListScheduledActionsResponseTypeDef,
+    UpdateScheduledActionResponseTypeDef,
+    OffPeakWindowTypeDef,
     ReservedInstanceOfferingTypeDef,
     ReservedInstanceTypeDef,
     SAMLOptionsInputTypeDef,
     SAMLOptionsOutputTypeDef,
     StorageTypeTypeDef,
     UpgradeHistoryTypeDef,
-    CreateOutboundConnectionRequestRequestTypeDef,
-    CreateOutboundConnectionResponseTypeDef,
     InboundConnectionTypeDef,
-    OutboundConnectionTypeDef,
     AutoTuneTypeDef,
     AutoTuneOptionsInputTypeDef,
     AutoTuneOptionsTypeDef,
+    DescribeDomainHealthResponseTypeDef,
     DescribeDomainChangeProgressResponseTypeDef,
     ClusterConfigStatusTypeDef,
+    CreateOutboundConnectionRequestRequestTypeDef,
+    CreateOutboundConnectionResponseTypeDef,
+    OutboundConnectionTypeDef,
     AssociatePackageResponseTypeDef,
     DissociatePackageResponseTypeDef,
     ListDomainsForPackageResponseTypeDef,
     ListPackagesForDomainResponseTypeDef,
     CreatePackageResponseTypeDef,
     DeletePackageResponseTypeDef,
     DescribePackagesResponseTypeDef,
     UpdatePackageResponseTypeDef,
     CreateVpcEndpointResponseTypeDef,
     DescribeVpcEndpointsResponseTypeDef,
     UpdateVpcEndpointResponseTypeDef,
+    OffPeakWindowOptionsTypeDef,
     DescribeReservedInstanceOfferingsResponseTypeDef,
     DescribeReservedInstancesResponseTypeDef,
     AdvancedSecurityOptionsInputTypeDef,
     AdvancedSecurityOptionsTypeDef,
     LimitsTypeDef,
     GetUpgradeHistoryResponseTypeDef,
     AcceptInboundConnectionResponseTypeDef,
     DeleteInboundConnectionResponseTypeDef,
     DescribeInboundConnectionsResponseTypeDef,
     RejectInboundConnectionResponseTypeDef,
-    DeleteOutboundConnectionResponseTypeDef,
-    DescribeOutboundConnectionsResponseTypeDef,
     DescribeDomainAutoTunesResponseTypeDef,
     AutoTuneOptionsStatusTypeDef,
+    DeleteOutboundConnectionResponseTypeDef,
+    DescribeOutboundConnectionsResponseTypeDef,
+    OffPeakWindowOptionsStatusTypeDef,
     CreateDomainRequestRequestTypeDef,
     UpdateDomainConfigRequestRequestTypeDef,
     AdvancedSecurityOptionsStatusTypeDef,
     DomainStatusTypeDef,
     DescribeInstanceTypeLimitsResponseTypeDef,
     DomainConfigTypeDef,
     CreateDomainResponseTypeDef,
@@ -483,43 +514,43 @@
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

### Comparing `types-aiobotocore-opensearch-2.5.0.post1/setup.py` & `types-aiobotocore-opensearch-2.5.1/setup.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-opensearch.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-opensearch",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_opensearch"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.OpenSearchService 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.OpenSearchService 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/"
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

### Comparing `types-aiobotocore-opensearch-2.5.0.post1/types_aiobotocore_opensearch/__main__.py` & `types-aiobotocore-opensearch-2.5.1/types_aiobotocore_opensearch/__main__.py`

 * *Files 6% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.OpenSearchService 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.OpenSearchService 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearch.html#OpenSearchService\nOther"
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

### Comparing `types-aiobotocore-opensearch-2.5.0.post1/types_aiobotocore_opensearch/client.py` & `types-aiobotocore-opensearch-2.5.1/types_aiobotocore_opensearch/client.py`

 * *Files 2% similar despite different names*

```diff
@@ -17,42 +17,47 @@
 import sys
 from typing import Any, Dict, Mapping, Sequence, Type
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import (
+    ActionTypeType,
     ConnectionModeType,
     DryRunModeType,
     EngineTypeType,
     LogTypeType,
     OpenSearchPartitionInstanceTypeType,
+    ScheduleAtType,
 )
 from .type_defs import (
     AcceptInboundConnectionResponseTypeDef,
     AdvancedSecurityOptionsInputTypeDef,
     AssociatePackageResponseTypeDef,
     AuthorizeVpcEndpointAccessResponseTypeDef,
     AutoTuneOptionsInputTypeDef,
     AutoTuneOptionsTypeDef,
     CancelServiceSoftwareUpdateResponseTypeDef,
     ClusterConfigTypeDef,
     CognitoOptionsTypeDef,
+    ConnectionPropertiesTypeDef,
     CreateDomainResponseTypeDef,
     CreateOutboundConnectionResponseTypeDef,
     CreatePackageResponseTypeDef,
     CreateVpcEndpointResponseTypeDef,
     DeleteDomainResponseTypeDef,
     DeleteInboundConnectionResponseTypeDef,
     DeleteOutboundConnectionResponseTypeDef,
     DeletePackageResponseTypeDef,
     DeleteVpcEndpointResponseTypeDef,
     DescribeDomainAutoTunesResponseTypeDef,
     DescribeDomainChangeProgressResponseTypeDef,
     DescribeDomainConfigResponseTypeDef,
+    DescribeDomainHealthResponseTypeDef,
+    DescribeDomainNodesResponseTypeDef,
     DescribeDomainResponseTypeDef,
     DescribeDomainsResponseTypeDef,
     DescribeDryRunProgressResponseTypeDef,
     DescribeInboundConnectionsResponseTypeDef,
     DescribeInstanceTypeLimitsResponseTypeDef,
     DescribeOutboundConnectionsResponseTypeDef,
     DescribePackagesFilterTypeDef,
@@ -71,29 +76,33 @@
     GetPackageVersionHistoryResponseTypeDef,
     GetUpgradeHistoryResponseTypeDef,
     GetUpgradeStatusResponseTypeDef,
     ListDomainNamesResponseTypeDef,
     ListDomainsForPackageResponseTypeDef,
     ListInstanceTypeDetailsResponseTypeDef,
     ListPackagesForDomainResponseTypeDef,
+    ListScheduledActionsResponseTypeDef,
     ListTagsResponseTypeDef,
     ListVersionsResponseTypeDef,
     ListVpcEndpointAccessResponseTypeDef,
     ListVpcEndpointsForDomainResponseTypeDef,
     ListVpcEndpointsResponseTypeDef,
     LogPublishingOptionTypeDef,
     NodeToNodeEncryptionOptionsTypeDef,
+    OffPeakWindowOptionsTypeDef,
     PackageSourceTypeDef,
     PurchaseReservedInstanceOfferingResponseTypeDef,
     RejectInboundConnectionResponseTypeDef,
     SnapshotOptionsTypeDef,
+    SoftwareUpdateOptionsTypeDef,
     StartServiceSoftwareUpdateResponseTypeDef,
     TagTypeDef,
     UpdateDomainConfigResponseTypeDef,
     UpdatePackageResponseTypeDef,
+    UpdateScheduledActionResponseTypeDef,
     UpdateVpcEndpointResponseTypeDef,
     UpgradeDomainResponseTypeDef,
     VPCOptionsTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
@@ -113,21 +122,23 @@
 
 
 class Exceptions:
     AccessDeniedException: Type[BotocoreClientError]
     BaseException: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
     ConflictException: Type[BotocoreClientError]
+    DependencyFailureException: Type[BotocoreClientError]
     DisabledOperationException: Type[BotocoreClientError]
     InternalException: Type[BotocoreClientError]
     InvalidPaginationTokenException: Type[BotocoreClientError]
     InvalidTypeException: Type[BotocoreClientError]
     LimitExceededException: Type[BotocoreClientError]
     ResourceAlreadyExistsException: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
+    SlotNotAvailableException: Type[BotocoreClientError]
     ValidationException: Type[BotocoreClientError]
 
 
 class OpenSearchServiceClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearch.html#OpenSearchService.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/client/)
@@ -227,30 +238,33 @@
         EncryptionAtRestOptions: EncryptionAtRestOptionsTypeDef = ...,
         NodeToNodeEncryptionOptions: NodeToNodeEncryptionOptionsTypeDef = ...,
         AdvancedOptions: Mapping[str, str] = ...,
         LogPublishingOptions: Mapping[LogTypeType, LogPublishingOptionTypeDef] = ...,
         DomainEndpointOptions: DomainEndpointOptionsTypeDef = ...,
         AdvancedSecurityOptions: AdvancedSecurityOptionsInputTypeDef = ...,
         TagList: Sequence[TagTypeDef] = ...,
-        AutoTuneOptions: AutoTuneOptionsInputTypeDef = ...
+        AutoTuneOptions: AutoTuneOptionsInputTypeDef = ...,
+        OffPeakWindowOptions: OffPeakWindowOptionsTypeDef = ...,
+        SoftwareUpdateOptions: SoftwareUpdateOptionsTypeDef = ...
     ) -> CreateDomainResponseTypeDef:
         """
         Creates an Amazon OpenSearch Service domain.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearch.html#OpenSearchService.Client.create_domain)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/client/#create_domain)
         """
 
     async def create_outbound_connection(
         self,
         *,
         LocalDomainInfo: DomainInformationContainerTypeDef,
         RemoteDomainInfo: DomainInformationContainerTypeDef,
         ConnectionAlias: str,
-        ConnectionMode: ConnectionModeType = ...
+        ConnectionMode: ConnectionModeType = ...,
+        ConnectionProperties: ConnectionPropertiesTypeDef = ...
     ) -> CreateOutboundConnectionResponseTypeDef:
         """
         Creates a new cross-cluster search connection from a source Amazon OpenSearch
         Service domain to a destination domain.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearch.html#OpenSearchService.Client.create_outbound_connection)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/client/#create_outbound_connection)
@@ -364,14 +378,35 @@
         """
         Returns the configuration of an Amazon OpenSearch Service domain.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearch.html#OpenSearchService.Client.describe_domain_config)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/client/#describe_domain_config)
         """
 
+    async def describe_domain_health(
+        self, *, DomainName: str
+    ) -> DescribeDomainHealthResponseTypeDef:
+        """
+        Returns information about domain and node health, the standby Availability Zone,
+        number of nodes per Availability Zone, and shard count per node.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearch.html#OpenSearchService.Client.describe_domain_health)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/client/#describe_domain_health)
+        """
+
+    async def describe_domain_nodes(self, *, DomainName: str) -> DescribeDomainNodesResponseTypeDef:
+        """
+        Returns information about domain and nodes, including data nodes, master nodes,
+        ultrawarm nodes, Availability Zone(s), standby nodes, node configurations, and
+        node states.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearch.html#OpenSearchService.Client.describe_domain_nodes)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/client/#describe_domain_nodes)
+        """
+
     async def describe_domains(
         self, *, DomainNames: Sequence[str]
     ) -> DescribeDomainsResponseTypeDef:
         """
         Returns domain configuration information about the specified Amazon OpenSearch
         Service domains.
 
@@ -509,15 +544,16 @@
         """
 
     async def get_package_version_history(
         self, *, PackageID: str, MaxResults: int = ..., NextToken: str = ...
     ) -> GetPackageVersionHistoryResponseTypeDef:
         """
         Returns a list of Amazon OpenSearch Service package versions, along with their
-        creation time and commit message.
+        creation time, commit message, and plugin properties (if the package is a zip
+        plugin package).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearch.html#OpenSearchService.Client.get_package_version_history)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/client/#get_package_version_history)
         """
 
     async def get_upgrade_history(
         self, *, DomainName: str, MaxResults: int = ..., NextToken: str = ...
@@ -562,15 +598,17 @@
 
     async def list_instance_type_details(
         self,
         *,
         EngineVersion: str,
         DomainName: str = ...,
         MaxResults: int = ...,
-        NextToken: str = ...
+        NextToken: str = ...,
+        RetrieveAZs: bool = ...,
+        InstanceType: str = ...
     ) -> ListInstanceTypeDetailsResponseTypeDef:
         """
         Lists all instance types and available features for a given OpenSearch or
         Elasticsearch version.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearch.html#OpenSearchService.Client.list_instance_type_details)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/client/#list_instance_type_details)
@@ -582,14 +620,24 @@
         """
         Lists all packages associated with an Amazon OpenSearch Service domain.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearch.html#OpenSearchService.Client.list_packages_for_domain)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/client/#list_packages_for_domain)
         """
 
+    async def list_scheduled_actions(
+        self, *, DomainName: str, MaxResults: int = ..., NextToken: str = ...
+    ) -> ListScheduledActionsResponseTypeDef:
+        """
+        Retrieves a list of configuration changes that are scheduled for a domain.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearch.html#OpenSearchService.Client.list_scheduled_actions)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/client/#list_scheduled_actions)
+        """
+
     async def list_tags(self, *, ARN: str) -> ListTagsResponseTypeDef:
         """
         Returns all resource tags for an Amazon OpenSearch Service domain.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearch.html#OpenSearchService.Client.list_tags)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/client/#list_tags)
         """
@@ -674,15 +722,15 @@
         an interface VPC endpoint.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearch.html#OpenSearchService.Client.revoke_vpc_endpoint_access)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/client/#revoke_vpc_endpoint_access)
         """
 
     async def start_service_software_update(
-        self, *, DomainName: str
+        self, *, DomainName: str, ScheduleAt: ScheduleAtType = ..., DesiredStartTime: int = ...
     ) -> StartServiceSoftwareUpdateResponseTypeDef:
         """
         Schedules a service software update for an Amazon OpenSearch Service domain.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearch.html#OpenSearchService.Client.start_service_software_update)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/client/#start_service_software_update)
         """
@@ -701,19 +749,22 @@
         LogPublishingOptions: Mapping[LogTypeType, LogPublishingOptionTypeDef] = ...,
         EncryptionAtRestOptions: EncryptionAtRestOptionsTypeDef = ...,
         DomainEndpointOptions: DomainEndpointOptionsTypeDef = ...,
         NodeToNodeEncryptionOptions: NodeToNodeEncryptionOptionsTypeDef = ...,
         AdvancedSecurityOptions: AdvancedSecurityOptionsInputTypeDef = ...,
         AutoTuneOptions: AutoTuneOptionsTypeDef = ...,
         DryRun: bool = ...,
-        DryRunMode: DryRunModeType = ...
+        DryRunMode: DryRunModeType = ...,
+        OffPeakWindowOptions: OffPeakWindowOptionsTypeDef = ...,
+        SoftwareUpdateOptions: SoftwareUpdateOptionsTypeDef = ...
     ) -> UpdateDomainConfigResponseTypeDef:
         """
         Modifies the cluster configuration of the specified Amazon OpenSearch Service
-        domain.
+        domain.sl See also: [AWS API
+        Documentation](https://docs.aws.amazon.com/goto/WebAPI/opensearch-2021-01-01/UpdateDomainConfig).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearch.html#OpenSearchService.Client.update_domain_config)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/client/#update_domain_config)
         """
 
     async def update_package(
         self,
@@ -726,14 +777,30 @@
         """
         Updates a package for use with Amazon OpenSearch Service domains.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearch.html#OpenSearchService.Client.update_package)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/client/#update_package)
         """
 
+    async def update_scheduled_action(
+        self,
+        *,
+        DomainName: str,
+        ActionID: str,
+        ActionType: ActionTypeType,
+        ScheduleAt: ScheduleAtType,
+        DesiredStartTime: int = ...
+    ) -> UpdateScheduledActionResponseTypeDef:
+        """
+        Reschedules a planned domain configuration change for a later time.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearch.html#OpenSearchService.Client.update_scheduled_action)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/client/#update_scheduled_action)
+        """
+
     async def update_vpc_endpoint(
         self, *, VpcEndpointId: str, VpcOptions: VPCOptionsTypeDef
     ) -> UpdateVpcEndpointResponseTypeDef:
         """
         Modifies an Amazon OpenSearch Service-managed interface VPC endpoint.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearch.html#OpenSearchService.Client.update_vpc_endpoint)
```

### Comparing `types-aiobotocore-opensearch-2.5.0.post1/types_aiobotocore_opensearch/client.pyi` & `types-aiobotocore-opensearch-2.5.1/types_aiobotocore_opensearch/client.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -17,42 +17,47 @@
 import sys
 from typing import Any, Dict, Mapping, Sequence, Type
 
 from aiobotocore.client import AioBaseClient
 from botocore.client import ClientMeta
 
 from .literals import (
+    ActionTypeType,
     ConnectionModeType,
     DryRunModeType,
     EngineTypeType,
     LogTypeType,
     OpenSearchPartitionInstanceTypeType,
+    ScheduleAtType,
 )
 from .type_defs import (
     AcceptInboundConnectionResponseTypeDef,
     AdvancedSecurityOptionsInputTypeDef,
     AssociatePackageResponseTypeDef,
     AuthorizeVpcEndpointAccessResponseTypeDef,
     AutoTuneOptionsInputTypeDef,
     AutoTuneOptionsTypeDef,
     CancelServiceSoftwareUpdateResponseTypeDef,
     ClusterConfigTypeDef,
     CognitoOptionsTypeDef,
+    ConnectionPropertiesTypeDef,
     CreateDomainResponseTypeDef,
     CreateOutboundConnectionResponseTypeDef,
     CreatePackageResponseTypeDef,
     CreateVpcEndpointResponseTypeDef,
     DeleteDomainResponseTypeDef,
     DeleteInboundConnectionResponseTypeDef,
     DeleteOutboundConnectionResponseTypeDef,
     DeletePackageResponseTypeDef,
     DeleteVpcEndpointResponseTypeDef,
     DescribeDomainAutoTunesResponseTypeDef,
     DescribeDomainChangeProgressResponseTypeDef,
     DescribeDomainConfigResponseTypeDef,
+    DescribeDomainHealthResponseTypeDef,
+    DescribeDomainNodesResponseTypeDef,
     DescribeDomainResponseTypeDef,
     DescribeDomainsResponseTypeDef,
     DescribeDryRunProgressResponseTypeDef,
     DescribeInboundConnectionsResponseTypeDef,
     DescribeInstanceTypeLimitsResponseTypeDef,
     DescribeOutboundConnectionsResponseTypeDef,
     DescribePackagesFilterTypeDef,
@@ -71,29 +76,33 @@
     GetPackageVersionHistoryResponseTypeDef,
     GetUpgradeHistoryResponseTypeDef,
     GetUpgradeStatusResponseTypeDef,
     ListDomainNamesResponseTypeDef,
     ListDomainsForPackageResponseTypeDef,
     ListInstanceTypeDetailsResponseTypeDef,
     ListPackagesForDomainResponseTypeDef,
+    ListScheduledActionsResponseTypeDef,
     ListTagsResponseTypeDef,
     ListVersionsResponseTypeDef,
     ListVpcEndpointAccessResponseTypeDef,
     ListVpcEndpointsForDomainResponseTypeDef,
     ListVpcEndpointsResponseTypeDef,
     LogPublishingOptionTypeDef,
     NodeToNodeEncryptionOptionsTypeDef,
+    OffPeakWindowOptionsTypeDef,
     PackageSourceTypeDef,
     PurchaseReservedInstanceOfferingResponseTypeDef,
     RejectInboundConnectionResponseTypeDef,
     SnapshotOptionsTypeDef,
+    SoftwareUpdateOptionsTypeDef,
     StartServiceSoftwareUpdateResponseTypeDef,
     TagTypeDef,
     UpdateDomainConfigResponseTypeDef,
     UpdatePackageResponseTypeDef,
+    UpdateScheduledActionResponseTypeDef,
     UpdateVpcEndpointResponseTypeDef,
     UpgradeDomainResponseTypeDef,
     VPCOptionsTypeDef,
 )
 
 if sys.version_info >= (3, 9):
     from typing import Literal
@@ -110,21 +119,23 @@
         self.operation_name: str
 
 class Exceptions:
     AccessDeniedException: Type[BotocoreClientError]
     BaseException: Type[BotocoreClientError]
     ClientError: Type[BotocoreClientError]
     ConflictException: Type[BotocoreClientError]
+    DependencyFailureException: Type[BotocoreClientError]
     DisabledOperationException: Type[BotocoreClientError]
     InternalException: Type[BotocoreClientError]
     InvalidPaginationTokenException: Type[BotocoreClientError]
     InvalidTypeException: Type[BotocoreClientError]
     LimitExceededException: Type[BotocoreClientError]
     ResourceAlreadyExistsException: Type[BotocoreClientError]
     ResourceNotFoundException: Type[BotocoreClientError]
+    SlotNotAvailableException: Type[BotocoreClientError]
     ValidationException: Type[BotocoreClientError]
 
 class OpenSearchServiceClient(AioBaseClient):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearch.html#OpenSearchService.Client)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/client/)
     """
@@ -215,29 +226,32 @@
         EncryptionAtRestOptions: EncryptionAtRestOptionsTypeDef = ...,
         NodeToNodeEncryptionOptions: NodeToNodeEncryptionOptionsTypeDef = ...,
         AdvancedOptions: Mapping[str, str] = ...,
         LogPublishingOptions: Mapping[LogTypeType, LogPublishingOptionTypeDef] = ...,
         DomainEndpointOptions: DomainEndpointOptionsTypeDef = ...,
         AdvancedSecurityOptions: AdvancedSecurityOptionsInputTypeDef = ...,
         TagList: Sequence[TagTypeDef] = ...,
-        AutoTuneOptions: AutoTuneOptionsInputTypeDef = ...
+        AutoTuneOptions: AutoTuneOptionsInputTypeDef = ...,
+        OffPeakWindowOptions: OffPeakWindowOptionsTypeDef = ...,
+        SoftwareUpdateOptions: SoftwareUpdateOptionsTypeDef = ...
     ) -> CreateDomainResponseTypeDef:
         """
         Creates an Amazon OpenSearch Service domain.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearch.html#OpenSearchService.Client.create_domain)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/client/#create_domain)
         """
     async def create_outbound_connection(
         self,
         *,
         LocalDomainInfo: DomainInformationContainerTypeDef,
         RemoteDomainInfo: DomainInformationContainerTypeDef,
         ConnectionAlias: str,
-        ConnectionMode: ConnectionModeType = ...
+        ConnectionMode: ConnectionModeType = ...,
+        ConnectionProperties: ConnectionPropertiesTypeDef = ...
     ) -> CreateOutboundConnectionResponseTypeDef:
         """
         Creates a new cross-cluster search connection from a source Amazon OpenSearch
         Service domain to a destination domain.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearch.html#OpenSearchService.Client.create_outbound_connection)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/client/#create_outbound_connection)
@@ -339,14 +353,33 @@
     ) -> DescribeDomainConfigResponseTypeDef:
         """
         Returns the configuration of an Amazon OpenSearch Service domain.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearch.html#OpenSearchService.Client.describe_domain_config)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/client/#describe_domain_config)
         """
+    async def describe_domain_health(
+        self, *, DomainName: str
+    ) -> DescribeDomainHealthResponseTypeDef:
+        """
+        Returns information about domain and node health, the standby Availability Zone,
+        number of nodes per Availability Zone, and shard count per node.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearch.html#OpenSearchService.Client.describe_domain_health)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/client/#describe_domain_health)
+        """
+    async def describe_domain_nodes(self, *, DomainName: str) -> DescribeDomainNodesResponseTypeDef:
+        """
+        Returns information about domain and nodes, including data nodes, master nodes,
+        ultrawarm nodes, Availability Zone(s), standby nodes, node configurations, and
+        node states.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearch.html#OpenSearchService.Client.describe_domain_nodes)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/client/#describe_domain_nodes)
+        """
     async def describe_domains(
         self, *, DomainNames: Sequence[str]
     ) -> DescribeDomainsResponseTypeDef:
         """
         Returns domain configuration information about the specified Amazon OpenSearch
         Service domains.
 
@@ -472,15 +505,16 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/client/#get_compatible_versions)
         """
     async def get_package_version_history(
         self, *, PackageID: str, MaxResults: int = ..., NextToken: str = ...
     ) -> GetPackageVersionHistoryResponseTypeDef:
         """
         Returns a list of Amazon OpenSearch Service package versions, along with their
-        creation time and commit message.
+        creation time, commit message, and plugin properties (if the package is a zip
+        plugin package).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearch.html#OpenSearchService.Client.get_package_version_history)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/client/#get_package_version_history)
         """
     async def get_upgrade_history(
         self, *, DomainName: str, MaxResults: int = ..., NextToken: str = ...
     ) -> GetUpgradeHistoryResponseTypeDef:
@@ -520,15 +554,17 @@
         """
     async def list_instance_type_details(
         self,
         *,
         EngineVersion: str,
         DomainName: str = ...,
         MaxResults: int = ...,
-        NextToken: str = ...
+        NextToken: str = ...,
+        RetrieveAZs: bool = ...,
+        InstanceType: str = ...
     ) -> ListInstanceTypeDetailsResponseTypeDef:
         """
         Lists all instance types and available features for a given OpenSearch or
         Elasticsearch version.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearch.html#OpenSearchService.Client.list_instance_type_details)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/client/#list_instance_type_details)
@@ -538,14 +574,23 @@
     ) -> ListPackagesForDomainResponseTypeDef:
         """
         Lists all packages associated with an Amazon OpenSearch Service domain.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearch.html#OpenSearchService.Client.list_packages_for_domain)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/client/#list_packages_for_domain)
         """
+    async def list_scheduled_actions(
+        self, *, DomainName: str, MaxResults: int = ..., NextToken: str = ...
+    ) -> ListScheduledActionsResponseTypeDef:
+        """
+        Retrieves a list of configuration changes that are scheduled for a domain.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearch.html#OpenSearchService.Client.list_scheduled_actions)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/client/#list_scheduled_actions)
+        """
     async def list_tags(self, *, ARN: str) -> ListTagsResponseTypeDef:
         """
         Returns all resource tags for an Amazon OpenSearch Service domain.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearch.html#OpenSearchService.Client.list_tags)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/client/#list_tags)
         """
@@ -621,15 +666,15 @@
         Revokes access to an Amazon OpenSearch Service domain that was provided through
         an interface VPC endpoint.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearch.html#OpenSearchService.Client.revoke_vpc_endpoint_access)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/client/#revoke_vpc_endpoint_access)
         """
     async def start_service_software_update(
-        self, *, DomainName: str
+        self, *, DomainName: str, ScheduleAt: ScheduleAtType = ..., DesiredStartTime: int = ...
     ) -> StartServiceSoftwareUpdateResponseTypeDef:
         """
         Schedules a service software update for an Amazon OpenSearch Service domain.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearch.html#OpenSearchService.Client.start_service_software_update)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/client/#start_service_software_update)
         """
@@ -647,19 +692,22 @@
         LogPublishingOptions: Mapping[LogTypeType, LogPublishingOptionTypeDef] = ...,
         EncryptionAtRestOptions: EncryptionAtRestOptionsTypeDef = ...,
         DomainEndpointOptions: DomainEndpointOptionsTypeDef = ...,
         NodeToNodeEncryptionOptions: NodeToNodeEncryptionOptionsTypeDef = ...,
         AdvancedSecurityOptions: AdvancedSecurityOptionsInputTypeDef = ...,
         AutoTuneOptions: AutoTuneOptionsTypeDef = ...,
         DryRun: bool = ...,
-        DryRunMode: DryRunModeType = ...
+        DryRunMode: DryRunModeType = ...,
+        OffPeakWindowOptions: OffPeakWindowOptionsTypeDef = ...,
+        SoftwareUpdateOptions: SoftwareUpdateOptionsTypeDef = ...
     ) -> UpdateDomainConfigResponseTypeDef:
         """
         Modifies the cluster configuration of the specified Amazon OpenSearch Service
-        domain.
+        domain.sl See also: [AWS API
+        Documentation](https://docs.aws.amazon.com/goto/WebAPI/opensearch-2021-01-01/UpdateDomainConfig).
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearch.html#OpenSearchService.Client.update_domain_config)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/client/#update_domain_config)
         """
     async def update_package(
         self,
         *,
@@ -670,14 +718,29 @@
     ) -> UpdatePackageResponseTypeDef:
         """
         Updates a package for use with Amazon OpenSearch Service domains.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearch.html#OpenSearchService.Client.update_package)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/client/#update_package)
         """
+    async def update_scheduled_action(
+        self,
+        *,
+        DomainName: str,
+        ActionID: str,
+        ActionType: ActionTypeType,
+        ScheduleAt: ScheduleAtType,
+        DesiredStartTime: int = ...
+    ) -> UpdateScheduledActionResponseTypeDef:
+        """
+        Reschedules a planned domain configuration change for a later time.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearch.html#OpenSearchService.Client.update_scheduled_action)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/client/#update_scheduled_action)
+        """
     async def update_vpc_endpoint(
         self, *, VpcEndpointId: str, VpcOptions: VPCOptionsTypeDef
     ) -> UpdateVpcEndpointResponseTypeDef:
         """
         Modifies an Amazon OpenSearch Service-managed interface VPC endpoint.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearch.html#OpenSearchService.Client.update_vpc_endpoint)
```

### Comparing `types-aiobotocore-opensearch-2.5.0.post1/types_aiobotocore_opensearch/literals.py` & `types-aiobotocore-opensearch-2.5.1/types_aiobotocore_opensearch/literals.py`

 * *Files 10% similar despite different names*

```diff
@@ -2,65 +2,82 @@
 Type annotations for opensearch service literal definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/literals/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_opensearch.literals import AutoTuneDesiredStateType
+    from types_aiobotocore_opensearch.literals import ActionSeverityType
 
-    data: AutoTuneDesiredStateType = "DISABLED"
+    data: ActionSeverityType = "HIGH"
     ```
 """
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 
 __all__ = (
+    "ActionSeverityType",
+    "ActionStatusType",
+    "ActionTypeType",
     "AutoTuneDesiredStateType",
     "AutoTuneStateType",
     "AutoTuneTypeType",
     "ConnectionModeType",
     "DeploymentStatusType",
     "DescribePackagesFilterNameType",
+    "DomainHealthType",
     "DomainPackageStatusType",
+    "DomainStateType",
     "DryRunModeType",
     "EngineTypeType",
     "InboundConnectionStatusCodeType",
     "LogTypeType",
+    "MasterNodeStatusType",
+    "NodeStatusType",
+    "NodeTypeType",
     "OpenSearchPartitionInstanceTypeType",
     "OpenSearchWarmPartitionInstanceTypeType",
     "OptionStateType",
     "OutboundConnectionStatusCodeType",
     "OverallChangeStatusType",
     "PackageStatusType",
     "PackageTypeType",
     "PrincipalTypeType",
     "ReservedInstancePaymentOptionType",
     "RollbackOnDisableType",
+    "ScheduleAtType",
     "ScheduledAutoTuneActionTypeType",
     "ScheduledAutoTuneSeverityTypeType",
+    "ScheduledByType",
+    "SkipUnavailableStatusType",
     "TLSSecurityPolicyType",
     "TimeUnitType",
     "UpgradeStatusType",
     "UpgradeStepType",
     "VolumeTypeType",
     "VpcEndpointErrorCodeType",
     "VpcEndpointStatusType",
+    "ZoneStatusType",
     "OpenSearchServiceServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
 
+ActionSeverityType = Literal["HIGH", "LOW", "MEDIUM"]
+ActionStatusType = Literal[
+    "COMPLETED", "ELIGIBLE", "FAILED", "IN_PROGRESS", "NOT_ELIGIBLE", "PENDING_UPDATE"
+]
+ActionTypeType = Literal["JVM_HEAP_SIZE_TUNING", "JVM_YOUNG_GEN_TUNING", "SERVICE_SOFTWARE_UPDATE"]
 AutoTuneDesiredStateType = Literal["DISABLED", "ENABLED"]
 AutoTuneStateType = Literal[
     "DISABLED",
     "DISABLED_AND_ROLLBACK_COMPLETE",
     "DISABLED_AND_ROLLBACK_ERROR",
     "DISABLED_AND_ROLLBACK_IN_PROGRESS",
     "DISABLED_AND_ROLLBACK_SCHEDULED",
@@ -71,30 +88,35 @@
 ]
 AutoTuneTypeType = Literal["SCHEDULED_ACTION"]
 ConnectionModeType = Literal["DIRECT", "VPC_ENDPOINT"]
 DeploymentStatusType = Literal[
     "COMPLETED", "ELIGIBLE", "IN_PROGRESS", "NOT_ELIGIBLE", "PENDING_UPDATE"
 ]
 DescribePackagesFilterNameType = Literal["PackageID", "PackageName", "PackageStatus"]
+DomainHealthType = Literal["Green", "NotAvailable", "Red", "Yellow"]
 DomainPackageStatusType = Literal[
     "ACTIVE", "ASSOCIATING", "ASSOCIATION_FAILED", "DISSOCIATING", "DISSOCIATION_FAILED"
 ]
+DomainStateType = Literal["Active", "NotAvailable", "Processing"]
 DryRunModeType = Literal["Basic", "Verbose"]
 EngineTypeType = Literal["Elasticsearch", "OpenSearch"]
 InboundConnectionStatusCodeType = Literal[
     "ACTIVE",
     "APPROVED",
     "DELETED",
     "DELETING",
     "PENDING_ACCEPTANCE",
     "PROVISIONING",
     "REJECTED",
     "REJECTING",
 ]
 LogTypeType = Literal["AUDIT_LOGS", "ES_APPLICATION_LOGS", "INDEX_SLOW_LOGS", "SEARCH_SLOW_LOGS"]
+MasterNodeStatusType = Literal["Available", "UnAvailable"]
+NodeStatusType = Literal["Active", "NotAvailable", "StandBy"]
+NodeTypeType = Literal["Data", "Master", "Ultrawarm"]
 OpenSearchPartitionInstanceTypeType = Literal[
     "c4.2xlarge.search",
     "c4.4xlarge.search",
     "c4.8xlarge.search",
     "c4.large.search",
     "c4.xlarge.search",
     "c5.18xlarge.search",
@@ -215,25 +237,29 @@
     "VALIDATING",
     "VALIDATION_FAILED",
 ]
 PackageTypeType = Literal["TXT-DICTIONARY"]
 PrincipalTypeType = Literal["AWS_ACCOUNT", "AWS_SERVICE"]
 ReservedInstancePaymentOptionType = Literal["ALL_UPFRONT", "NO_UPFRONT", "PARTIAL_UPFRONT"]
 RollbackOnDisableType = Literal["DEFAULT_ROLLBACK", "NO_ROLLBACK"]
+ScheduleAtType = Literal["NOW", "OFF_PEAK_WINDOW", "TIMESTAMP"]
 ScheduledAutoTuneActionTypeType = Literal["JVM_HEAP_SIZE_TUNING", "JVM_YOUNG_GEN_TUNING"]
 ScheduledAutoTuneSeverityTypeType = Literal["HIGH", "LOW", "MEDIUM"]
+ScheduledByType = Literal["CUSTOMER", "SYSTEM"]
+SkipUnavailableStatusType = Literal["DISABLED", "ENABLED"]
 TLSSecurityPolicyType = Literal["Policy-Min-TLS-1-0-2019-07", "Policy-Min-TLS-1-2-2019-07"]
 TimeUnitType = Literal["HOURS"]
 UpgradeStatusType = Literal["FAILED", "IN_PROGRESS", "SUCCEEDED", "SUCCEEDED_WITH_ISSUES"]
 UpgradeStepType = Literal["PRE_UPGRADE_CHECK", "SNAPSHOT", "UPGRADE"]
 VolumeTypeType = Literal["gp2", "gp3", "io1", "standard"]
 VpcEndpointErrorCodeType = Literal["ENDPOINT_NOT_FOUND", "SERVER_ERROR"]
 VpcEndpointStatusType = Literal[
     "ACTIVE", "CREATE_FAILED", "CREATING", "DELETE_FAILED", "DELETING", "UPDATE_FAILED", "UPDATING"
 ]
+ZoneStatusType = Literal["Active", "NotAvailable", "StandBy"]
 OpenSearchServiceServiceName = Literal["opensearch"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
     "alexaforbusiness",
@@ -289,14 +315,15 @@
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
@@ -375,14 +402,15 @@
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
@@ -393,14 +421,15 @@
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
@@ -436,14 +465,15 @@
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
@@ -462,16 +492,19 @@
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
@@ -555,15 +588,17 @@
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

### Comparing `types-aiobotocore-opensearch-2.5.0.post1/types_aiobotocore_opensearch/literals.pyi` & `types-aiobotocore-opensearch-2.5.1/types_aiobotocore_opensearch/literals.pyi`

 * *Files 11% similar despite different names*

```diff
@@ -2,63 +2,80 @@
 Type annotations for opensearch service literal definitions.
 
 [Open documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/literals/)
 
 Usage::
 
     ```python
-    from types_aiobotocore_opensearch.literals import AutoTuneDesiredStateType
+    from types_aiobotocore_opensearch.literals import ActionSeverityType
 
-    data: AutoTuneDesiredStateType = "DISABLED"
+    data: ActionSeverityType = "HIGH"
     ```
 """
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 __all__ = (
+    "ActionSeverityType",
+    "ActionStatusType",
+    "ActionTypeType",
     "AutoTuneDesiredStateType",
     "AutoTuneStateType",
     "AutoTuneTypeType",
     "ConnectionModeType",
     "DeploymentStatusType",
     "DescribePackagesFilterNameType",
+    "DomainHealthType",
     "DomainPackageStatusType",
+    "DomainStateType",
     "DryRunModeType",
     "EngineTypeType",
     "InboundConnectionStatusCodeType",
     "LogTypeType",
+    "MasterNodeStatusType",
+    "NodeStatusType",
+    "NodeTypeType",
     "OpenSearchPartitionInstanceTypeType",
     "OpenSearchWarmPartitionInstanceTypeType",
     "OptionStateType",
     "OutboundConnectionStatusCodeType",
     "OverallChangeStatusType",
     "PackageStatusType",
     "PackageTypeType",
     "PrincipalTypeType",
     "ReservedInstancePaymentOptionType",
     "RollbackOnDisableType",
+    "ScheduleAtType",
     "ScheduledAutoTuneActionTypeType",
     "ScheduledAutoTuneSeverityTypeType",
+    "ScheduledByType",
+    "SkipUnavailableStatusType",
     "TLSSecurityPolicyType",
     "TimeUnitType",
     "UpgradeStatusType",
     "UpgradeStepType",
     "VolumeTypeType",
     "VpcEndpointErrorCodeType",
     "VpcEndpointStatusType",
+    "ZoneStatusType",
     "OpenSearchServiceServiceName",
     "ServiceName",
     "ResourceServiceName",
     "RegionName",
 )
 
+ActionSeverityType = Literal["HIGH", "LOW", "MEDIUM"]
+ActionStatusType = Literal[
+    "COMPLETED", "ELIGIBLE", "FAILED", "IN_PROGRESS", "NOT_ELIGIBLE", "PENDING_UPDATE"
+]
+ActionTypeType = Literal["JVM_HEAP_SIZE_TUNING", "JVM_YOUNG_GEN_TUNING", "SERVICE_SOFTWARE_UPDATE"]
 AutoTuneDesiredStateType = Literal["DISABLED", "ENABLED"]
 AutoTuneStateType = Literal[
     "DISABLED",
     "DISABLED_AND_ROLLBACK_COMPLETE",
     "DISABLED_AND_ROLLBACK_ERROR",
     "DISABLED_AND_ROLLBACK_IN_PROGRESS",
     "DISABLED_AND_ROLLBACK_SCHEDULED",
@@ -69,30 +86,35 @@
 ]
 AutoTuneTypeType = Literal["SCHEDULED_ACTION"]
 ConnectionModeType = Literal["DIRECT", "VPC_ENDPOINT"]
 DeploymentStatusType = Literal[
     "COMPLETED", "ELIGIBLE", "IN_PROGRESS", "NOT_ELIGIBLE", "PENDING_UPDATE"
 ]
 DescribePackagesFilterNameType = Literal["PackageID", "PackageName", "PackageStatus"]
+DomainHealthType = Literal["Green", "NotAvailable", "Red", "Yellow"]
 DomainPackageStatusType = Literal[
     "ACTIVE", "ASSOCIATING", "ASSOCIATION_FAILED", "DISSOCIATING", "DISSOCIATION_FAILED"
 ]
+DomainStateType = Literal["Active", "NotAvailable", "Processing"]
 DryRunModeType = Literal["Basic", "Verbose"]
 EngineTypeType = Literal["Elasticsearch", "OpenSearch"]
 InboundConnectionStatusCodeType = Literal[
     "ACTIVE",
     "APPROVED",
     "DELETED",
     "DELETING",
     "PENDING_ACCEPTANCE",
     "PROVISIONING",
     "REJECTED",
     "REJECTING",
 ]
 LogTypeType = Literal["AUDIT_LOGS", "ES_APPLICATION_LOGS", "INDEX_SLOW_LOGS", "SEARCH_SLOW_LOGS"]
+MasterNodeStatusType = Literal["Available", "UnAvailable"]
+NodeStatusType = Literal["Active", "NotAvailable", "StandBy"]
+NodeTypeType = Literal["Data", "Master", "Ultrawarm"]
 OpenSearchPartitionInstanceTypeType = Literal[
     "c4.2xlarge.search",
     "c4.4xlarge.search",
     "c4.8xlarge.search",
     "c4.large.search",
     "c4.xlarge.search",
     "c5.18xlarge.search",
@@ -213,25 +235,29 @@
     "VALIDATING",
     "VALIDATION_FAILED",
 ]
 PackageTypeType = Literal["TXT-DICTIONARY"]
 PrincipalTypeType = Literal["AWS_ACCOUNT", "AWS_SERVICE"]
 ReservedInstancePaymentOptionType = Literal["ALL_UPFRONT", "NO_UPFRONT", "PARTIAL_UPFRONT"]
 RollbackOnDisableType = Literal["DEFAULT_ROLLBACK", "NO_ROLLBACK"]
+ScheduleAtType = Literal["NOW", "OFF_PEAK_WINDOW", "TIMESTAMP"]
 ScheduledAutoTuneActionTypeType = Literal["JVM_HEAP_SIZE_TUNING", "JVM_YOUNG_GEN_TUNING"]
 ScheduledAutoTuneSeverityTypeType = Literal["HIGH", "LOW", "MEDIUM"]
+ScheduledByType = Literal["CUSTOMER", "SYSTEM"]
+SkipUnavailableStatusType = Literal["DISABLED", "ENABLED"]
 TLSSecurityPolicyType = Literal["Policy-Min-TLS-1-0-2019-07", "Policy-Min-TLS-1-2-2019-07"]
 TimeUnitType = Literal["HOURS"]
 UpgradeStatusType = Literal["FAILED", "IN_PROGRESS", "SUCCEEDED", "SUCCEEDED_WITH_ISSUES"]
 UpgradeStepType = Literal["PRE_UPGRADE_CHECK", "SNAPSHOT", "UPGRADE"]
 VolumeTypeType = Literal["gp2", "gp3", "io1", "standard"]
 VpcEndpointErrorCodeType = Literal["ENDPOINT_NOT_FOUND", "SERVER_ERROR"]
 VpcEndpointStatusType = Literal[
     "ACTIVE", "CREATE_FAILED", "CREATING", "DELETE_FAILED", "DELETING", "UPDATE_FAILED", "UPDATING"
 ]
+ZoneStatusType = Literal["Active", "NotAvailable", "StandBy"]
 OpenSearchServiceServiceName = Literal["opensearch"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
     "acm-pca",
     "alexaforbusiness",
@@ -287,14 +313,15 @@
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
@@ -373,14 +400,15 @@
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
@@ -391,14 +419,15 @@
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
@@ -434,14 +463,15 @@
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
@@ -460,16 +490,19 @@
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
@@ -553,15 +586,17 @@
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

### Comparing `types-aiobotocore-opensearch-2.5.0.post1/types_aiobotocore_opensearch/type_defs.py` & `types-aiobotocore-opensearch-2.5.1/types_aiobotocore_opensearch/type_defs.pyi`

 * *Files 8% similar despite different names*

```diff
@@ -12,95 +12,110 @@
     ```
 """
 import sys
 from datetime import datetime
 from typing import Dict, List, Mapping, Sequence, Union
 
 from .literals import (
+    ActionSeverityType,
+    ActionStatusType,
+    ActionTypeType,
     AutoTuneDesiredStateType,
     AutoTuneStateType,
     ConnectionModeType,
     DeploymentStatusType,
     DescribePackagesFilterNameType,
+    DomainHealthType,
     DomainPackageStatusType,
+    DomainStateType,
     DryRunModeType,
     EngineTypeType,
     InboundConnectionStatusCodeType,
     LogTypeType,
+    MasterNodeStatusType,
+    NodeStatusType,
+    NodeTypeType,
     OpenSearchPartitionInstanceTypeType,
     OpenSearchWarmPartitionInstanceTypeType,
     OptionStateType,
     OutboundConnectionStatusCodeType,
     OverallChangeStatusType,
     PackageStatusType,
     PrincipalTypeType,
     ReservedInstancePaymentOptionType,
     RollbackOnDisableType,
+    ScheduleAtType,
     ScheduledAutoTuneActionTypeType,
     ScheduledAutoTuneSeverityTypeType,
+    ScheduledByType,
+    SkipUnavailableStatusType,
     TLSSecurityPolicyType,
     UpgradeStatusType,
     UpgradeStepType,
     VolumeTypeType,
     VpcEndpointErrorCodeType,
     VpcEndpointStatusType,
+    ZoneStatusType,
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
     "AWSDomainInformationTypeDef",
     "AcceptInboundConnectionRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "OptionStatusTypeDef",
     "TagTypeDef",
     "AdditionalLimitTypeDef",
     "MasterUserOptionsTypeDef",
     "AssociatePackageRequestRequestTypeDef",
     "AuthorizeVpcEndpointAccessRequestRequestTypeDef",
     "AuthorizedPrincipalTypeDef",
     "ScheduledAutoTuneDetailsTypeDef",
     "DurationTypeDef",
     "AutoTuneOptionsOutputTypeDef",
     "AutoTuneStatusTypeDef",
+    "AvailabilityZoneInfoTypeDef",
     "CancelServiceSoftwareUpdateRequestRequestTypeDef",
     "ServiceSoftwareOptionsTypeDef",
     "ChangeProgressDetailsTypeDef",
     "ChangeProgressStageTypeDef",
     "ColdStorageOptionsTypeDef",
     "ZoneAwarenessConfigTypeDef",
     "CognitoOptionsTypeDef",
     "CompatibleVersionsMapTypeDef",
-    "ConnectionPropertiesTypeDef",
+    "CrossClusterSearchConnectionPropertiesTypeDef",
     "DomainEndpointOptionsTypeDef",
     "EBSOptionsTypeDef",
     "EncryptionAtRestOptionsTypeDef",
     "LogPublishingOptionTypeDef",
     "NodeToNodeEncryptionOptionsTypeDef",
     "SnapshotOptionsTypeDef",
+    "SoftwareUpdateOptionsTypeDef",
     "VPCOptionsTypeDef",
     "OutboundConnectionStatusTypeDef",
     "PackageSourceTypeDef",
     "DeleteDomainRequestRequestTypeDef",
     "DeleteInboundConnectionRequestRequestTypeDef",
     "DeleteOutboundConnectionRequestRequestTypeDef",
     "DeletePackageRequestRequestTypeDef",
     "DeleteVpcEndpointRequestRequestTypeDef",
     "VpcEndpointSummaryTypeDef",
     "DescribeDomainAutoTunesRequestRequestTypeDef",
     "DescribeDomainChangeProgressRequestRequestTypeDef",
     "DescribeDomainConfigRequestRequestTypeDef",
+    "DescribeDomainHealthRequestRequestTypeDef",
+    "DescribeDomainNodesRequestRequestTypeDef",
+    "DomainNodesStatusTypeDef",
     "DescribeDomainRequestRequestTypeDef",
     "DescribeDomainsRequestRequestTypeDef",
     "DescribeDryRunProgressRequestRequestTypeDef",
     "DryRunResultsTypeDef",
     "FilterTypeDef",
     "DescribeInstanceTypeLimitsRequestRequestTypeDef",
     "DescribePackagesFilterTypeDef",
@@ -109,127 +124,142 @@
     "DescribeVpcEndpointsRequestRequestTypeDef",
     "VpcEndpointErrorTypeDef",
     "DissociatePackageRequestRequestTypeDef",
     "DomainInfoTypeDef",
     "ErrorDetailsTypeDef",
     "VPCDerivedInfoTypeDef",
     "ValidationFailureTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetCompatibleVersionsRequestRequestTypeDef",
     "GetPackageVersionHistoryRequestRequestTypeDef",
     "PackageVersionHistoryTypeDef",
     "GetUpgradeHistoryRequestRequestTypeDef",
     "GetUpgradeStatusRequestRequestTypeDef",
+    "GetUpgradeStatusResponseTypeDef",
     "InboundConnectionStatusTypeDef",
     "InstanceCountLimitsTypeDef",
     "InstanceTypeDetailsTypeDef",
     "ListDomainNamesRequestRequestTypeDef",
     "ListDomainsForPackageRequestRequestTypeDef",
     "ListInstanceTypeDetailsRequestRequestTypeDef",
     "ListPackagesForDomainRequestRequestTypeDef",
+    "ListScheduledActionsRequestRequestTypeDef",
+    "ScheduledActionTypeDef",
     "ListTagsRequestRequestTypeDef",
     "ListVersionsRequestRequestTypeDef",
+    "ListVersionsResponseTypeDef",
     "ListVpcEndpointAccessRequestRequestTypeDef",
     "ListVpcEndpointsForDomainRequestRequestTypeDef",
     "ListVpcEndpointsRequestRequestTypeDef",
+    "WindowStartTimeTypeDef",
     "PurchaseReservedInstanceOfferingRequestRequestTypeDef",
+    "PurchaseReservedInstanceOfferingResponseTypeDef",
     "RecurringChargeTypeDef",
     "RejectInboundConnectionRequestRequestTypeDef",
     "RemoveTagsRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "RevokeVpcEndpointAccessRequestRequestTypeDef",
     "SAMLIdpTypeDef",
     "StartServiceSoftwareUpdateRequestRequestTypeDef",
     "StorageTypeLimitTypeDef",
+    "UpdateScheduledActionRequestRequestTypeDef",
     "UpgradeDomainRequestRequestTypeDef",
     "UpgradeStepItemTypeDef",
     "DomainInformationContainerTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetUpgradeStatusResponseTypeDef",
-    "ListVersionsResponseTypeDef",
-    "PurchaseReservedInstanceOfferingResponseTypeDef",
     "AccessPoliciesStatusTypeDef",
     "AdvancedOptionsStatusTypeDef",
     "VersionStatusTypeDef",
     "AddTagsRequestRequestTypeDef",
     "ListTagsResponseTypeDef",
     "AuthorizeVpcEndpointAccessResponseTypeDef",
     "ListVpcEndpointAccessResponseTypeDef",
     "AutoTuneDetailsTypeDef",
     "AutoTuneMaintenanceScheduleTypeDef",
+    "EnvironmentInfoTypeDef",
     "CancelServiceSoftwareUpdateResponseTypeDef",
     "StartServiceSoftwareUpdateResponseTypeDef",
     "UpgradeDomainResponseTypeDef",
     "ChangeProgressStatusDetailsTypeDef",
     "ClusterConfigTypeDef",
     "CognitoOptionsStatusTypeDef",
     "GetCompatibleVersionsResponseTypeDef",
+    "ConnectionPropertiesTypeDef",
     "DomainEndpointOptionsStatusTypeDef",
     "EBSOptionsStatusTypeDef",
     "EncryptionAtRestOptionsStatusTypeDef",
     "LogPublishingOptionsStatusTypeDef",
     "NodeToNodeEncryptionOptionsStatusTypeDef",
     "SnapshotOptionsStatusTypeDef",
+    "SoftwareUpdateOptionsStatusTypeDef",
     "CreateVpcEndpointRequestRequestTypeDef",
     "UpdateVpcEndpointRequestRequestTypeDef",
     "CreatePackageRequestRequestTypeDef",
     "UpdatePackageRequestRequestTypeDef",
     "DeleteVpcEndpointResponseTypeDef",
     "ListVpcEndpointsForDomainResponseTypeDef",
     "ListVpcEndpointsResponseTypeDef",
+    "DescribeDomainNodesResponseTypeDef",
     "DescribeInboundConnectionsRequestRequestTypeDef",
     "DescribeOutboundConnectionsRequestRequestTypeDef",
     "DescribePackagesRequestRequestTypeDef",
     "ListDomainNamesResponseTypeDef",
     "DomainPackageDetailsTypeDef",
     "PackageDetailsTypeDef",
     "VPCDerivedInfoStatusTypeDef",
     "VpcEndpointTypeDef",
     "DryRunProgressStatusTypeDef",
     "GetPackageVersionHistoryResponseTypeDef",
     "InstanceLimitsTypeDef",
     "ListInstanceTypeDetailsResponseTypeDef",
+    "ListScheduledActionsResponseTypeDef",
+    "UpdateScheduledActionResponseTypeDef",
+    "OffPeakWindowTypeDef",
     "ReservedInstanceOfferingTypeDef",
     "ReservedInstanceTypeDef",
     "SAMLOptionsInputTypeDef",
     "SAMLOptionsOutputTypeDef",
     "StorageTypeTypeDef",
     "UpgradeHistoryTypeDef",
-    "CreateOutboundConnectionRequestRequestTypeDef",
-    "CreateOutboundConnectionResponseTypeDef",
     "InboundConnectionTypeDef",
-    "OutboundConnectionTypeDef",
     "AutoTuneTypeDef",
     "AutoTuneOptionsInputTypeDef",
     "AutoTuneOptionsTypeDef",
+    "DescribeDomainHealthResponseTypeDef",
     "DescribeDomainChangeProgressResponseTypeDef",
     "ClusterConfigStatusTypeDef",
+    "CreateOutboundConnectionRequestRequestTypeDef",
+    "CreateOutboundConnectionResponseTypeDef",
+    "OutboundConnectionTypeDef",
     "AssociatePackageResponseTypeDef",
     "DissociatePackageResponseTypeDef",
     "ListDomainsForPackageResponseTypeDef",
     "ListPackagesForDomainResponseTypeDef",
     "CreatePackageResponseTypeDef",
     "DeletePackageResponseTypeDef",
     "DescribePackagesResponseTypeDef",
     "UpdatePackageResponseTypeDef",
     "CreateVpcEndpointResponseTypeDef",
     "DescribeVpcEndpointsResponseTypeDef",
     "UpdateVpcEndpointResponseTypeDef",
+    "OffPeakWindowOptionsTypeDef",
     "DescribeReservedInstanceOfferingsResponseTypeDef",
     "DescribeReservedInstancesResponseTypeDef",
     "AdvancedSecurityOptionsInputTypeDef",
     "AdvancedSecurityOptionsTypeDef",
     "LimitsTypeDef",
     "GetUpgradeHistoryResponseTypeDef",
     "AcceptInboundConnectionResponseTypeDef",
     "DeleteInboundConnectionResponseTypeDef",
     "DescribeInboundConnectionsResponseTypeDef",
     "RejectInboundConnectionResponseTypeDef",
-    "DeleteOutboundConnectionResponseTypeDef",
-    "DescribeOutboundConnectionsResponseTypeDef",
     "DescribeDomainAutoTunesResponseTypeDef",
     "AutoTuneOptionsStatusTypeDef",
+    "DeleteOutboundConnectionResponseTypeDef",
+    "DescribeOutboundConnectionsResponseTypeDef",
+    "OffPeakWindowOptionsStatusTypeDef",
     "CreateDomainRequestRequestTypeDef",
     "UpdateDomainConfigRequestRequestTypeDef",
     "AdvancedSecurityOptionsStatusTypeDef",
     "DomainStatusTypeDef",
     "DescribeInstanceTypeLimitsResponseTypeDef",
     "DomainConfigTypeDef",
     "CreateDomainResponseTypeDef",
@@ -252,39 +282,26 @@
     {
         "OwnerId": str,
         "Region": str,
     },
     total=False,
 )
 
-
 class AWSDomainInformationTypeDef(
     _RequiredAWSDomainInformationTypeDef, _OptionalAWSDomainInformationTypeDef
 ):
     pass
 
-
 AcceptInboundConnectionRequestRequestTypeDef = TypedDict(
     "AcceptInboundConnectionRequestRequestTypeDef",
     {
         "ConnectionId": str,
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
 _RequiredOptionStatusTypeDef = TypedDict(
     "_RequiredOptionStatusTypeDef",
     {
         "CreationDate": datetime,
         "UpdateDate": datetime,
         "State": OptionStateType,
     },
@@ -294,19 +311,17 @@
     {
         "UpdateVersion": int,
         "PendingDeletion": bool,
     },
     total=False,
 )
 
-
 class OptionStatusTypeDef(_RequiredOptionStatusTypeDef, _OptionalOptionStatusTypeDef):
     pass
 
-
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
@@ -376,14 +391,15 @@
 )
 
 AutoTuneOptionsOutputTypeDef = TypedDict(
     "AutoTuneOptionsOutputTypeDef",
     {
         "State": AutoTuneStateType,
         "ErrorMessage": str,
+        "UseOffPeakWindow": bool,
     },
     total=False,
 )
 
 _RequiredAutoTuneStatusTypeDef = TypedDict(
     "_RequiredAutoTuneStatusTypeDef",
     {
@@ -398,18 +414,29 @@
         "UpdateVersion": int,
         "ErrorMessage": str,
         "PendingDeletion": bool,
     },
     total=False,
 )
 
-
 class AutoTuneStatusTypeDef(_RequiredAutoTuneStatusTypeDef, _OptionalAutoTuneStatusTypeDef):
     pass
 
+AvailabilityZoneInfoTypeDef = TypedDict(
+    "AvailabilityZoneInfoTypeDef",
+    {
+        "AvailabilityZoneName": str,
+        "ZoneStatus": ZoneStatusType,
+        "ConfiguredDataNodeCount": str,
+        "AvailableDataNodeCount": str,
+        "TotalShards": str,
+        "TotalUnAssignedShards": str,
+    },
+    total=False,
+)
 
 CancelServiceSoftwareUpdateRequestRequestTypeDef = TypedDict(
     "CancelServiceSoftwareUpdateRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
@@ -480,18 +507,18 @@
     {
         "SourceVersion": str,
         "TargetVersions": List[str],
     },
     total=False,
 )
 
-ConnectionPropertiesTypeDef = TypedDict(
-    "ConnectionPropertiesTypeDef",
+CrossClusterSearchConnectionPropertiesTypeDef = TypedDict(
+    "CrossClusterSearchConnectionPropertiesTypeDef",
     {
-        "Endpoint": str,
+        "SkipUnavailable": SkipUnavailableStatusType,
     },
     total=False,
 )
 
 DomainEndpointOptionsTypeDef = TypedDict(
     "DomainEndpointOptionsTypeDef",
     {
@@ -546,14 +573,22 @@
     "SnapshotOptionsTypeDef",
     {
         "AutomatedSnapshotStartHour": int,
     },
     total=False,
 )
 
+SoftwareUpdateOptionsTypeDef = TypedDict(
+    "SoftwareUpdateOptionsTypeDef",
+    {
+        "AutoSoftwareUpdateEnabled": bool,
+    },
+    total=False,
+)
+
 VPCOptionsTypeDef = TypedDict(
     "VPCOptionsTypeDef",
     {
         "SubnetIds": Sequence[str],
         "SecurityGroupIds": Sequence[str],
     },
     total=False,
@@ -634,51 +669,76 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class DescribeDomainAutoTunesRequestRequestTypeDef(
     _RequiredDescribeDomainAutoTunesRequestRequestTypeDef,
     _OptionalDescribeDomainAutoTunesRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredDescribeDomainChangeProgressRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeDomainChangeProgressRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 _OptionalDescribeDomainChangeProgressRequestRequestTypeDef = TypedDict(
     "_OptionalDescribeDomainChangeProgressRequestRequestTypeDef",
     {
         "ChangeId": str,
     },
     total=False,
 )
 
-
 class DescribeDomainChangeProgressRequestRequestTypeDef(
     _RequiredDescribeDomainChangeProgressRequestRequestTypeDef,
     _OptionalDescribeDomainChangeProgressRequestRequestTypeDef,
 ):
     pass
 
-
 DescribeDomainConfigRequestRequestTypeDef = TypedDict(
     "DescribeDomainConfigRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 
+DescribeDomainHealthRequestRequestTypeDef = TypedDict(
+    "DescribeDomainHealthRequestRequestTypeDef",
+    {
+        "DomainName": str,
+    },
+)
+
+DescribeDomainNodesRequestRequestTypeDef = TypedDict(
+    "DescribeDomainNodesRequestRequestTypeDef",
+    {
+        "DomainName": str,
+    },
+)
+
+DomainNodesStatusTypeDef = TypedDict(
+    "DomainNodesStatusTypeDef",
+    {
+        "NodeId": str,
+        "NodeType": NodeTypeType,
+        "AvailabilityZone": str,
+        "InstanceType": OpenSearchPartitionInstanceTypeType,
+        "NodeStatus": NodeStatusType,
+        "StorageType": str,
+        "StorageVolumeType": VolumeTypeType,
+        "StorageSize": str,
+    },
+    total=False,
+)
+
 DescribeDomainRequestRequestTypeDef = TypedDict(
     "DescribeDomainRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 
@@ -700,22 +760,20 @@
     {
         "DryRunId": str,
         "LoadDryRunConfig": bool,
     },
     total=False,
 )
 
-
 class DescribeDryRunProgressRequestRequestTypeDef(
     _RequiredDescribeDryRunProgressRequestRequestTypeDef,
     _OptionalDescribeDryRunProgressRequestRequestTypeDef,
 ):
     pass
 
-
 DryRunResultsTypeDef = TypedDict(
     "DryRunResultsTypeDef",
     {
         "DeploymentType": str,
         "Message": str,
     },
     total=False,
@@ -741,22 +799,20 @@
     "_OptionalDescribeInstanceTypeLimitsRequestRequestTypeDef",
     {
         "DomainName": str,
     },
     total=False,
 )
 
-
 class DescribeInstanceTypeLimitsRequestRequestTypeDef(
     _RequiredDescribeInstanceTypeLimitsRequestRequestTypeDef,
     _OptionalDescribeInstanceTypeLimitsRequestRequestTypeDef,
 ):
     pass
 
-
 DescribePackagesFilterTypeDef = TypedDict(
     "DescribePackagesFilterTypeDef",
     {
         "Name": DescribePackagesFilterNameType,
         "Value": Sequence[str],
     },
     total=False,
@@ -841,14 +897,21 @@
     {
         "Code": str,
         "Message": str,
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
 GetCompatibleVersionsRequestRequestTypeDef = TypedDict(
     "GetCompatibleVersionsRequestRequestTypeDef",
     {
         "DomainName": str,
     },
     total=False,
 )
@@ -864,22 +927,20 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class GetPackageVersionHistoryRequestRequestTypeDef(
     _RequiredGetPackageVersionHistoryRequestRequestTypeDef,
     _OptionalGetPackageVersionHistoryRequestRequestTypeDef,
 ):
     pass
 
-
 PackageVersionHistoryTypeDef = TypedDict(
     "PackageVersionHistoryTypeDef",
     {
         "PackageVersion": str,
         "CommitMessage": str,
         "CreatedAt": datetime,
     },
@@ -897,28 +958,36 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class GetUpgradeHistoryRequestRequestTypeDef(
     _RequiredGetUpgradeHistoryRequestRequestTypeDef, _OptionalGetUpgradeHistoryRequestRequestTypeDef
 ):
     pass
 
-
 GetUpgradeStatusRequestRequestTypeDef = TypedDict(
     "GetUpgradeStatusRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 
+GetUpgradeStatusResponseTypeDef = TypedDict(
+    "GetUpgradeStatusResponseTypeDef",
+    {
+        "UpgradeStep": UpgradeStepType,
+        "StepStatus": UpgradeStatusType,
+        "UpgradeName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 InboundConnectionStatusTypeDef = TypedDict(
     "InboundConnectionStatusTypeDef",
     {
         "StatusCode": InboundConnectionStatusCodeType,
         "Message": str,
     },
     total=False,
@@ -939,14 +1008,15 @@
         "InstanceType": OpenSearchPartitionInstanceTypeType,
         "EncryptionEnabled": bool,
         "CognitoEnabled": bool,
         "AppLogsEnabled": bool,
         "AdvancedSecurityEnabled": bool,
         "WarmEnabled": bool,
         "InstanceRole": List[str],
+        "AvailabilityZones": List[str],
     },
     total=False,
 )
 
 ListDomainNamesRequestRequestTypeDef = TypedDict(
     "ListDomainNamesRequestRequestTypeDef",
     {
@@ -966,46 +1036,44 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class ListDomainsForPackageRequestRequestTypeDef(
     _RequiredListDomainsForPackageRequestRequestTypeDef,
     _OptionalListDomainsForPackageRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredListInstanceTypeDetailsRequestRequestTypeDef = TypedDict(
     "_RequiredListInstanceTypeDetailsRequestRequestTypeDef",
     {
         "EngineVersion": str,
     },
 )
 _OptionalListInstanceTypeDetailsRequestRequestTypeDef = TypedDict(
     "_OptionalListInstanceTypeDetailsRequestRequestTypeDef",
     {
         "DomainName": str,
         "MaxResults": int,
         "NextToken": str,
+        "RetrieveAZs": bool,
+        "InstanceType": str,
     },
     total=False,
 )
 
-
 class ListInstanceTypeDetailsRequestRequestTypeDef(
     _RequiredListInstanceTypeDetailsRequestRequestTypeDef,
     _OptionalListInstanceTypeDetailsRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredListPackagesForDomainRequestRequestTypeDef = TypedDict(
     "_RequiredListPackagesForDomainRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 _OptionalListPackagesForDomainRequestRequestTypeDef = TypedDict(
@@ -1013,21 +1081,64 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class ListPackagesForDomainRequestRequestTypeDef(
     _RequiredListPackagesForDomainRequestRequestTypeDef,
     _OptionalListPackagesForDomainRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListScheduledActionsRequestRequestTypeDef = TypedDict(
+    "_RequiredListScheduledActionsRequestRequestTypeDef",
+    {
+        "DomainName": str,
+    },
+)
+_OptionalListScheduledActionsRequestRequestTypeDef = TypedDict(
+    "_OptionalListScheduledActionsRequestRequestTypeDef",
+    {
+        "MaxResults": int,
+        "NextToken": str,
+    },
+    total=False,
+)
+
+class ListScheduledActionsRequestRequestTypeDef(
+    _RequiredListScheduledActionsRequestRequestTypeDef,
+    _OptionalListScheduledActionsRequestRequestTypeDef,
+):
+    pass
+
+_RequiredScheduledActionTypeDef = TypedDict(
+    "_RequiredScheduledActionTypeDef",
+    {
+        "Id": str,
+        "Type": ActionTypeType,
+        "Severity": ActionSeverityType,
+        "ScheduledTime": int,
+    },
+)
+_OptionalScheduledActionTypeDef = TypedDict(
+    "_OptionalScheduledActionTypeDef",
+    {
+        "Description": str,
+        "ScheduledBy": ScheduledByType,
+        "Status": ActionStatusType,
+        "Mandatory": bool,
+        "Cancellable": bool,
+    },
+    total=False,
+)
+
+class ScheduledActionTypeDef(_RequiredScheduledActionTypeDef, _OptionalScheduledActionTypeDef):
+    pass
 
 ListTagsRequestRequestTypeDef = TypedDict(
     "ListTagsRequestRequestTypeDef",
     {
         "ARN": str,
     },
 )
@@ -1037,66 +1148,79 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListVersionsResponseTypeDef = TypedDict(
+    "ListVersionsResponseTypeDef",
+    {
+        "Versions": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredListVpcEndpointAccessRequestRequestTypeDef = TypedDict(
     "_RequiredListVpcEndpointAccessRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 _OptionalListVpcEndpointAccessRequestRequestTypeDef = TypedDict(
     "_OptionalListVpcEndpointAccessRequestRequestTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
-
 class ListVpcEndpointAccessRequestRequestTypeDef(
     _RequiredListVpcEndpointAccessRequestRequestTypeDef,
     _OptionalListVpcEndpointAccessRequestRequestTypeDef,
 ):
     pass
 
-
 _RequiredListVpcEndpointsForDomainRequestRequestTypeDef = TypedDict(
     "_RequiredListVpcEndpointsForDomainRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 _OptionalListVpcEndpointsForDomainRequestRequestTypeDef = TypedDict(
     "_OptionalListVpcEndpointsForDomainRequestRequestTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
-
 class ListVpcEndpointsForDomainRequestRequestTypeDef(
     _RequiredListVpcEndpointsForDomainRequestRequestTypeDef,
     _OptionalListVpcEndpointsForDomainRequestRequestTypeDef,
 ):
     pass
 
-
 ListVpcEndpointsRequestRequestTypeDef = TypedDict(
     "ListVpcEndpointsRequestRequestTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
+WindowStartTimeTypeDef = TypedDict(
+    "WindowStartTimeTypeDef",
+    {
+        "Hours": int,
+        "Minutes": int,
+    },
+)
+
 _RequiredPurchaseReservedInstanceOfferingRequestRequestTypeDef = TypedDict(
     "_RequiredPurchaseReservedInstanceOfferingRequestRequestTypeDef",
     {
         "ReservedInstanceOfferingId": str,
         "ReservationName": str,
     },
 )
@@ -1104,21 +1228,28 @@
     "_OptionalPurchaseReservedInstanceOfferingRequestRequestTypeDef",
     {
         "InstanceCount": int,
     },
     total=False,
 )
 
-
 class PurchaseReservedInstanceOfferingRequestRequestTypeDef(
     _RequiredPurchaseReservedInstanceOfferingRequestRequestTypeDef,
     _OptionalPurchaseReservedInstanceOfferingRequestRequestTypeDef,
 ):
     pass
 
+PurchaseReservedInstanceOfferingResponseTypeDef = TypedDict(
+    "PurchaseReservedInstanceOfferingResponseTypeDef",
+    {
+        "ReservedInstanceId": str,
+        "ReservationName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 RecurringChargeTypeDef = TypedDict(
     "RecurringChargeTypeDef",
     {
         "RecurringChargeAmount": float,
         "RecurringChargeFrequency": str,
     },
@@ -1136,14 +1267,25 @@
     "RemoveTagsRequestRequestTypeDef",
     {
         "ARN": str,
         "TagKeys": Sequence[str],
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
 RevokeVpcEndpointAccessRequestRequestTypeDef = TypedDict(
     "RevokeVpcEndpointAccessRequestRequestTypeDef",
     {
         "DomainName": str,
         "Account": str,
     },
 )
@@ -1152,30 +1294,67 @@
     "SAMLIdpTypeDef",
     {
         "MetadataContent": str,
         "EntityId": str,
     },
 )
 
-StartServiceSoftwareUpdateRequestRequestTypeDef = TypedDict(
-    "StartServiceSoftwareUpdateRequestRequestTypeDef",
+_RequiredStartServiceSoftwareUpdateRequestRequestTypeDef = TypedDict(
+    "_RequiredStartServiceSoftwareUpdateRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
+_OptionalStartServiceSoftwareUpdateRequestRequestTypeDef = TypedDict(
+    "_OptionalStartServiceSoftwareUpdateRequestRequestTypeDef",
+    {
+        "ScheduleAt": ScheduleAtType,
+        "DesiredStartTime": int,
+    },
+    total=False,
+)
+
+class StartServiceSoftwareUpdateRequestRequestTypeDef(
+    _RequiredStartServiceSoftwareUpdateRequestRequestTypeDef,
+    _OptionalStartServiceSoftwareUpdateRequestRequestTypeDef,
+):
+    pass
 
 StorageTypeLimitTypeDef = TypedDict(
     "StorageTypeLimitTypeDef",
     {
         "LimitName": str,
         "LimitValues": List[str],
     },
     total=False,
 )
 
+_RequiredUpdateScheduledActionRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateScheduledActionRequestRequestTypeDef",
+    {
+        "DomainName": str,
+        "ActionID": str,
+        "ActionType": ActionTypeType,
+        "ScheduleAt": ScheduleAtType,
+    },
+)
+_OptionalUpdateScheduledActionRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateScheduledActionRequestRequestTypeDef",
+    {
+        "DesiredStartTime": int,
+    },
+    total=False,
+)
+
+class UpdateScheduledActionRequestRequestTypeDef(
+    _RequiredUpdateScheduledActionRequestRequestTypeDef,
+    _OptionalUpdateScheduledActionRequestRequestTypeDef,
+):
+    pass
+
 _RequiredUpgradeDomainRequestRequestTypeDef = TypedDict(
     "_RequiredUpgradeDomainRequestRequestTypeDef",
     {
         "DomainName": str,
         "TargetVersion": str,
     },
 )
@@ -1184,21 +1363,19 @@
     {
         "PerformCheckOnly": bool,
         "AdvancedOptions": Mapping[str, str],
     },
     total=False,
 )
 
-
 class UpgradeDomainRequestRequestTypeDef(
     _RequiredUpgradeDomainRequestRequestTypeDef, _OptionalUpgradeDomainRequestRequestTypeDef
 ):
     pass
 
-
 UpgradeStepItemTypeDef = TypedDict(
     "UpgradeStepItemTypeDef",
     {
         "UpgradeStep": UpgradeStepType,
         "UpgradeStepStatus": UpgradeStatusType,
         "Issues": List[str],
         "ProgressPercent": float,
@@ -1210,49 +1387,14 @@
     "DomainInformationContainerTypeDef",
     {
         "AWSDomainInformation": AWSDomainInformationTypeDef,
     },
     total=False,
 )
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetUpgradeStatusResponseTypeDef = TypedDict(
-    "GetUpgradeStatusResponseTypeDef",
-    {
-        "UpgradeStep": UpgradeStepType,
-        "StepStatus": UpgradeStatusType,
-        "UpgradeName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListVersionsResponseTypeDef = TypedDict(
-    "ListVersionsResponseTypeDef",
-    {
-        "Versions": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PurchaseReservedInstanceOfferingResponseTypeDef = TypedDict(
-    "PurchaseReservedInstanceOfferingResponseTypeDef",
-    {
-        "ReservedInstanceId": str,
-        "ReservationName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 AccessPoliciesStatusTypeDef = TypedDict(
     "AccessPoliciesStatusTypeDef",
     {
         "Options": str,
         "Status": OptionStatusTypeDef,
     },
 )
@@ -1281,32 +1423,32 @@
     },
 )
 
 ListTagsResponseTypeDef = TypedDict(
     "ListTagsResponseTypeDef",
     {
         "TagList": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AuthorizeVpcEndpointAccessResponseTypeDef = TypedDict(
     "AuthorizeVpcEndpointAccessResponseTypeDef",
     {
         "AuthorizedPrincipal": AuthorizedPrincipalTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVpcEndpointAccessResponseTypeDef = TypedDict(
     "ListVpcEndpointAccessResponseTypeDef",
     {
         "AuthorizedPrincipalList": List[AuthorizedPrincipalTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AutoTuneDetailsTypeDef = TypedDict(
     "AutoTuneDetailsTypeDef",
     {
         "ScheduledAutoTuneDetails": ScheduledAutoTuneDetailsTypeDef,
@@ -1320,40 +1462,48 @@
         "StartAt": Union[datetime, str],
         "Duration": DurationTypeDef,
         "CronExpressionForRecurrence": str,
     },
     total=False,
 )
 
+EnvironmentInfoTypeDef = TypedDict(
+    "EnvironmentInfoTypeDef",
+    {
+        "AvailabilityZoneInformation": List[AvailabilityZoneInfoTypeDef],
+    },
+    total=False,
+)
+
 CancelServiceSoftwareUpdateResponseTypeDef = TypedDict(
     "CancelServiceSoftwareUpdateResponseTypeDef",
     {
         "ServiceSoftwareOptions": ServiceSoftwareOptionsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartServiceSoftwareUpdateResponseTypeDef = TypedDict(
     "StartServiceSoftwareUpdateResponseTypeDef",
     {
         "ServiceSoftwareOptions": ServiceSoftwareOptionsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpgradeDomainResponseTypeDef = TypedDict(
     "UpgradeDomainResponseTypeDef",
     {
         "UpgradeId": str,
         "DomainName": str,
         "TargetVersion": str,
         "PerformCheckOnly": bool,
         "AdvancedOptions": Dict[str, str],
         "ChangeProgressDetails": ChangeProgressDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ChangeProgressStatusDetailsTypeDef = TypedDict(
     "ChangeProgressStatusDetailsTypeDef",
     {
         "ChangeId": str,
@@ -1377,14 +1527,15 @@
         "ZoneAwarenessConfig": ZoneAwarenessConfigTypeDef,
         "DedicatedMasterType": OpenSearchPartitionInstanceTypeType,
         "DedicatedMasterCount": int,
         "WarmEnabled": bool,
         "WarmType": OpenSearchWarmPartitionInstanceTypeType,
         "WarmCount": int,
         "ColdStorageOptions": ColdStorageOptionsTypeDef,
+        "MultiAZWithStandbyEnabled": bool,
     },
     total=False,
 )
 
 CognitoOptionsStatusTypeDef = TypedDict(
     "CognitoOptionsStatusTypeDef",
     {
@@ -1393,18 +1544,27 @@
     },
 )
 
 GetCompatibleVersionsResponseTypeDef = TypedDict(
     "GetCompatibleVersionsResponseTypeDef",
     {
         "CompatibleVersions": List[CompatibleVersionsMapTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
+ConnectionPropertiesTypeDef = TypedDict(
+    "ConnectionPropertiesTypeDef",
+    {
+        "Endpoint": str,
+        "CrossClusterSearch": CrossClusterSearchConnectionPropertiesTypeDef,
+    },
+    total=False,
+)
+
 DomainEndpointOptionsStatusTypeDef = TypedDict(
     "DomainEndpointOptionsStatusTypeDef",
     {
         "Options": DomainEndpointOptionsTypeDef,
         "Status": OptionStatusTypeDef,
     },
 )
@@ -1446,14 +1606,23 @@
     "SnapshotOptionsStatusTypeDef",
     {
         "Options": SnapshotOptionsTypeDef,
         "Status": OptionStatusTypeDef,
     },
 )
 
+SoftwareUpdateOptionsStatusTypeDef = TypedDict(
+    "SoftwareUpdateOptionsStatusTypeDef",
+    {
+        "Options": SoftwareUpdateOptionsTypeDef,
+        "Status": OptionStatusTypeDef,
+    },
+    total=False,
+)
+
 _RequiredCreateVpcEndpointRequestRequestTypeDef = TypedDict(
     "_RequiredCreateVpcEndpointRequestRequestTypeDef",
     {
         "DomainArn": str,
         "VpcOptions": VPCOptionsTypeDef,
     },
 )
@@ -1461,21 +1630,19 @@
     "_OptionalCreateVpcEndpointRequestRequestTypeDef",
     {
         "ClientToken": str,
     },
     total=False,
 )
 
-
 class CreateVpcEndpointRequestRequestTypeDef(
     _RequiredCreateVpcEndpointRequestRequestTypeDef, _OptionalCreateVpcEndpointRequestRequestTypeDef
 ):
     pass
 
-
 UpdateVpcEndpointRequestRequestTypeDef = TypedDict(
     "UpdateVpcEndpointRequestRequestTypeDef",
     {
         "VpcEndpointId": str,
         "VpcOptions": VPCOptionsTypeDef,
     },
 )
@@ -1492,21 +1659,19 @@
     "_OptionalCreatePackageRequestRequestTypeDef",
     {
         "PackageDescription": str,
     },
     total=False,
 )
 
-
 class CreatePackageRequestRequestTypeDef(
     _RequiredCreatePackageRequestRequestTypeDef, _OptionalCreatePackageRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredUpdatePackageRequestRequestTypeDef = TypedDict(
     "_RequiredUpdatePackageRequestRequestTypeDef",
     {
         "PackageID": str,
         "PackageSource": PackageSourceTypeDef,
     },
 )
@@ -1515,44 +1680,50 @@
     {
         "PackageDescription": str,
         "CommitMessage": str,
     },
     total=False,
 )
 
-
 class UpdatePackageRequestRequestTypeDef(
     _RequiredUpdatePackageRequestRequestTypeDef, _OptionalUpdatePackageRequestRequestTypeDef
 ):
     pass
 
-
 DeleteVpcEndpointResponseTypeDef = TypedDict(
     "DeleteVpcEndpointResponseTypeDef",
     {
         "VpcEndpointSummary": VpcEndpointSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVpcEndpointsForDomainResponseTypeDef = TypedDict(
     "ListVpcEndpointsForDomainResponseTypeDef",
     {
         "VpcEndpointSummaryList": List[VpcEndpointSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVpcEndpointsResponseTypeDef = TypedDict(
     "ListVpcEndpointsResponseTypeDef",
     {
         "VpcEndpointSummaryList": List[VpcEndpointSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeDomainNodesResponseTypeDef = TypedDict(
+    "DescribeDomainNodesResponseTypeDef",
+    {
+        "DomainNodesStatusList": List[DomainNodesStatusTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeInboundConnectionsRequestRequestTypeDef = TypedDict(
     "DescribeInboundConnectionsRequestRequestTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
@@ -1582,15 +1753,15 @@
     total=False,
 )
 
 ListDomainNamesResponseTypeDef = TypedDict(
     "ListDomainNamesResponseTypeDef",
     {
         "DomainNames": List[DomainInfoTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DomainPackageDetailsTypeDef = TypedDict(
     "DomainPackageDetailsTypeDef",
     {
         "PackageID": str,
@@ -1656,28 +1827,26 @@
     "_OptionalDryRunProgressStatusTypeDef",
     {
         "ValidationFailures": List[ValidationFailureTypeDef],
     },
     total=False,
 )
 
-
 class DryRunProgressStatusTypeDef(
     _RequiredDryRunProgressStatusTypeDef, _OptionalDryRunProgressStatusTypeDef
 ):
     pass
 
-
 GetPackageVersionHistoryResponseTypeDef = TypedDict(
     "GetPackageVersionHistoryResponseTypeDef",
     {
         "PackageID": str,
         "PackageVersionHistoryList": List[PackageVersionHistoryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InstanceLimitsTypeDef = TypedDict(
     "InstanceLimitsTypeDef",
     {
         "InstanceCountLimits": InstanceCountLimitsTypeDef,
@@ -1686,18 +1855,43 @@
 )
 
 ListInstanceTypeDetailsResponseTypeDef = TypedDict(
     "ListInstanceTypeDetailsResponseTypeDef",
     {
         "InstanceTypeDetails": List[InstanceTypeDetailsTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListScheduledActionsResponseTypeDef = TypedDict(
+    "ListScheduledActionsResponseTypeDef",
+    {
+        "ScheduledActions": List[ScheduledActionTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateScheduledActionResponseTypeDef = TypedDict(
+    "UpdateScheduledActionResponseTypeDef",
+    {
+        "ScheduledAction": ScheduledActionTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
+OffPeakWindowTypeDef = TypedDict(
+    "OffPeakWindowTypeDef",
+    {
+        "WindowStartTime": WindowStartTimeTypeDef,
+    },
+    total=False,
+)
+
 ReservedInstanceOfferingTypeDef = TypedDict(
     "ReservedInstanceOfferingTypeDef",
     {
         "ReservedInstanceOfferingId": str,
         "InstanceType": OpenSearchPartitionInstanceTypeType,
         "Duration": int,
         "FixedPrice": float,
@@ -1773,229 +1967,259 @@
         "StartTimestamp": datetime,
         "UpgradeStatus": UpgradeStatusType,
         "StepsList": List[UpgradeStepItemTypeDef],
     },
     total=False,
 )
 
-_RequiredCreateOutboundConnectionRequestRequestTypeDef = TypedDict(
-    "_RequiredCreateOutboundConnectionRequestRequestTypeDef",
-    {
-        "LocalDomainInfo": DomainInformationContainerTypeDef,
-        "RemoteDomainInfo": DomainInformationContainerTypeDef,
-        "ConnectionAlias": str,
-    },
-)
-_OptionalCreateOutboundConnectionRequestRequestTypeDef = TypedDict(
-    "_OptionalCreateOutboundConnectionRequestRequestTypeDef",
-    {
-        "ConnectionMode": ConnectionModeType,
-    },
-    total=False,
-)
-
-
-class CreateOutboundConnectionRequestRequestTypeDef(
-    _RequiredCreateOutboundConnectionRequestRequestTypeDef,
-    _OptionalCreateOutboundConnectionRequestRequestTypeDef,
-):
-    pass
-
-
-CreateOutboundConnectionResponseTypeDef = TypedDict(
-    "CreateOutboundConnectionResponseTypeDef",
-    {
-        "LocalDomainInfo": DomainInformationContainerTypeDef,
-        "RemoteDomainInfo": DomainInformationContainerTypeDef,
-        "ConnectionAlias": str,
-        "ConnectionStatus": OutboundConnectionStatusTypeDef,
-        "ConnectionId": str,
-        "ConnectionMode": ConnectionModeType,
-        "ConnectionProperties": ConnectionPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 InboundConnectionTypeDef = TypedDict(
     "InboundConnectionTypeDef",
     {
         "LocalDomainInfo": DomainInformationContainerTypeDef,
         "RemoteDomainInfo": DomainInformationContainerTypeDef,
         "ConnectionId": str,
         "ConnectionStatus": InboundConnectionStatusTypeDef,
         "ConnectionMode": ConnectionModeType,
     },
     total=False,
 )
 
-OutboundConnectionTypeDef = TypedDict(
-    "OutboundConnectionTypeDef",
-    {
-        "LocalDomainInfo": DomainInformationContainerTypeDef,
-        "RemoteDomainInfo": DomainInformationContainerTypeDef,
-        "ConnectionId": str,
-        "ConnectionAlias": str,
-        "ConnectionStatus": OutboundConnectionStatusTypeDef,
-        "ConnectionMode": ConnectionModeType,
-        "ConnectionProperties": ConnectionPropertiesTypeDef,
-    },
-    total=False,
-)
-
 AutoTuneTypeDef = TypedDict(
     "AutoTuneTypeDef",
     {
         "AutoTuneType": Literal["SCHEDULED_ACTION"],
         "AutoTuneDetails": AutoTuneDetailsTypeDef,
     },
     total=False,
 )
 
 AutoTuneOptionsInputTypeDef = TypedDict(
     "AutoTuneOptionsInputTypeDef",
     {
         "DesiredState": AutoTuneDesiredStateType,
         "MaintenanceSchedules": Sequence[AutoTuneMaintenanceScheduleTypeDef],
+        "UseOffPeakWindow": bool,
     },
     total=False,
 )
 
 AutoTuneOptionsTypeDef = TypedDict(
     "AutoTuneOptionsTypeDef",
     {
         "DesiredState": AutoTuneDesiredStateType,
         "RollbackOnDisable": RollbackOnDisableType,
         "MaintenanceSchedules": List[AutoTuneMaintenanceScheduleTypeDef],
+        "UseOffPeakWindow": bool,
     },
     total=False,
 )
 
+DescribeDomainHealthResponseTypeDef = TypedDict(
+    "DescribeDomainHealthResponseTypeDef",
+    {
+        "DomainState": DomainStateType,
+        "AvailabilityZoneCount": str,
+        "ActiveAvailabilityZoneCount": str,
+        "StandByAvailabilityZoneCount": str,
+        "DataNodeCount": str,
+        "DedicatedMaster": bool,
+        "MasterEligibleNodeCount": str,
+        "WarmNodeCount": str,
+        "MasterNode": MasterNodeStatusType,
+        "ClusterHealth": DomainHealthType,
+        "TotalShards": str,
+        "TotalUnAssignedShards": str,
+        "EnvironmentInformation": List[EnvironmentInfoTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeDomainChangeProgressResponseTypeDef = TypedDict(
     "DescribeDomainChangeProgressResponseTypeDef",
     {
         "ChangeProgressStatus": ChangeProgressStatusDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ClusterConfigStatusTypeDef = TypedDict(
     "ClusterConfigStatusTypeDef",
     {
         "Options": ClusterConfigTypeDef,
         "Status": OptionStatusTypeDef,
     },
 )
 
+_RequiredCreateOutboundConnectionRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateOutboundConnectionRequestRequestTypeDef",
+    {
+        "LocalDomainInfo": DomainInformationContainerTypeDef,
+        "RemoteDomainInfo": DomainInformationContainerTypeDef,
+        "ConnectionAlias": str,
+    },
+)
+_OptionalCreateOutboundConnectionRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateOutboundConnectionRequestRequestTypeDef",
+    {
+        "ConnectionMode": ConnectionModeType,
+        "ConnectionProperties": ConnectionPropertiesTypeDef,
+    },
+    total=False,
+)
+
+class CreateOutboundConnectionRequestRequestTypeDef(
+    _RequiredCreateOutboundConnectionRequestRequestTypeDef,
+    _OptionalCreateOutboundConnectionRequestRequestTypeDef,
+):
+    pass
+
+CreateOutboundConnectionResponseTypeDef = TypedDict(
+    "CreateOutboundConnectionResponseTypeDef",
+    {
+        "LocalDomainInfo": DomainInformationContainerTypeDef,
+        "RemoteDomainInfo": DomainInformationContainerTypeDef,
+        "ConnectionAlias": str,
+        "ConnectionStatus": OutboundConnectionStatusTypeDef,
+        "ConnectionId": str,
+        "ConnectionMode": ConnectionModeType,
+        "ConnectionProperties": ConnectionPropertiesTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+OutboundConnectionTypeDef = TypedDict(
+    "OutboundConnectionTypeDef",
+    {
+        "LocalDomainInfo": DomainInformationContainerTypeDef,
+        "RemoteDomainInfo": DomainInformationContainerTypeDef,
+        "ConnectionId": str,
+        "ConnectionAlias": str,
+        "ConnectionStatus": OutboundConnectionStatusTypeDef,
+        "ConnectionMode": ConnectionModeType,
+        "ConnectionProperties": ConnectionPropertiesTypeDef,
+    },
+    total=False,
+)
+
 AssociatePackageResponseTypeDef = TypedDict(
     "AssociatePackageResponseTypeDef",
     {
         "DomainPackageDetails": DomainPackageDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DissociatePackageResponseTypeDef = TypedDict(
     "DissociatePackageResponseTypeDef",
     {
         "DomainPackageDetails": DomainPackageDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDomainsForPackageResponseTypeDef = TypedDict(
     "ListDomainsForPackageResponseTypeDef",
     {
         "DomainPackageDetailsList": List[DomainPackageDetailsTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPackagesForDomainResponseTypeDef = TypedDict(
     "ListPackagesForDomainResponseTypeDef",
     {
         "DomainPackageDetailsList": List[DomainPackageDetailsTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreatePackageResponseTypeDef = TypedDict(
     "CreatePackageResponseTypeDef",
     {
         "PackageDetails": PackageDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeletePackageResponseTypeDef = TypedDict(
     "DeletePackageResponseTypeDef",
     {
         "PackageDetails": PackageDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribePackagesResponseTypeDef = TypedDict(
     "DescribePackagesResponseTypeDef",
     {
         "PackageDetailsList": List[PackageDetailsTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdatePackageResponseTypeDef = TypedDict(
     "UpdatePackageResponseTypeDef",
     {
         "PackageDetails": PackageDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateVpcEndpointResponseTypeDef = TypedDict(
     "CreateVpcEndpointResponseTypeDef",
     {
         "VpcEndpoint": VpcEndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeVpcEndpointsResponseTypeDef = TypedDict(
     "DescribeVpcEndpointsResponseTypeDef",
     {
         "VpcEndpoints": List[VpcEndpointTypeDef],
         "VpcEndpointErrors": List[VpcEndpointErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateVpcEndpointResponseTypeDef = TypedDict(
     "UpdateVpcEndpointResponseTypeDef",
     {
         "VpcEndpoint": VpcEndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
+OffPeakWindowOptionsTypeDef = TypedDict(
+    "OffPeakWindowOptionsTypeDef",
+    {
+        "Enabled": bool,
+        "OffPeakWindow": OffPeakWindowTypeDef,
+    },
+    total=False,
+)
+
 DescribeReservedInstanceOfferingsResponseTypeDef = TypedDict(
     "DescribeReservedInstanceOfferingsResponseTypeDef",
     {
         "NextToken": str,
         "ReservedInstanceOfferings": List[ReservedInstanceOfferingTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeReservedInstancesResponseTypeDef = TypedDict(
     "DescribeReservedInstancesResponseTypeDef",
     {
         "NextToken": str,
         "ReservedInstances": List[ReservedInstanceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AdvancedSecurityOptionsInputTypeDef = TypedDict(
     "AdvancedSecurityOptionsInputTypeDef",
     {
         "Enabled": bool,
@@ -2030,82 +2254,91 @@
 )
 
 GetUpgradeHistoryResponseTypeDef = TypedDict(
     "GetUpgradeHistoryResponseTypeDef",
     {
         "UpgradeHistories": List[UpgradeHistoryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AcceptInboundConnectionResponseTypeDef = TypedDict(
     "AcceptInboundConnectionResponseTypeDef",
     {
         "Connection": InboundConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteInboundConnectionResponseTypeDef = TypedDict(
     "DeleteInboundConnectionResponseTypeDef",
     {
         "Connection": InboundConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeInboundConnectionsResponseTypeDef = TypedDict(
     "DescribeInboundConnectionsResponseTypeDef",
     {
         "Connections": List[InboundConnectionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RejectInboundConnectionResponseTypeDef = TypedDict(
     "RejectInboundConnectionResponseTypeDef",
     {
         "Connection": InboundConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeDomainAutoTunesResponseTypeDef = TypedDict(
+    "DescribeDomainAutoTunesResponseTypeDef",
+    {
+        "AutoTunes": List[AutoTuneTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+AutoTuneOptionsStatusTypeDef = TypedDict(
+    "AutoTuneOptionsStatusTypeDef",
+    {
+        "Options": AutoTuneOptionsTypeDef,
+        "Status": AutoTuneStatusTypeDef,
     },
+    total=False,
 )
 
 DeleteOutboundConnectionResponseTypeDef = TypedDict(
     "DeleteOutboundConnectionResponseTypeDef",
     {
         "Connection": OutboundConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeOutboundConnectionsResponseTypeDef = TypedDict(
     "DescribeOutboundConnectionsResponseTypeDef",
     {
         "Connections": List[OutboundConnectionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DescribeDomainAutoTunesResponseTypeDef = TypedDict(
-    "DescribeDomainAutoTunesResponseTypeDef",
+OffPeakWindowOptionsStatusTypeDef = TypedDict(
+    "OffPeakWindowOptionsStatusTypeDef",
     {
-        "AutoTunes": List[AutoTuneTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-AutoTuneOptionsStatusTypeDef = TypedDict(
-    "AutoTuneOptionsStatusTypeDef",
-    {
-        "Options": AutoTuneOptionsTypeDef,
-        "Status": AutoTuneStatusTypeDef,
+        "Options": OffPeakWindowOptionsTypeDef,
+        "Status": OptionStatusTypeDef,
     },
     total=False,
 )
 
 _RequiredCreateDomainRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDomainRequestRequestTypeDef",
     {
@@ -2126,25 +2359,25 @@
         "NodeToNodeEncryptionOptions": NodeToNodeEncryptionOptionsTypeDef,
         "AdvancedOptions": Mapping[str, str],
         "LogPublishingOptions": Mapping[LogTypeType, LogPublishingOptionTypeDef],
         "DomainEndpointOptions": DomainEndpointOptionsTypeDef,
         "AdvancedSecurityOptions": AdvancedSecurityOptionsInputTypeDef,
         "TagList": Sequence[TagTypeDef],
         "AutoTuneOptions": AutoTuneOptionsInputTypeDef,
+        "OffPeakWindowOptions": OffPeakWindowOptionsTypeDef,
+        "SoftwareUpdateOptions": SoftwareUpdateOptionsTypeDef,
     },
     total=False,
 )
 
-
 class CreateDomainRequestRequestTypeDef(
     _RequiredCreateDomainRequestRequestTypeDef, _OptionalCreateDomainRequestRequestTypeDef
 ):
     pass
 
-
 _RequiredUpdateDomainConfigRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateDomainConfigRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 _OptionalUpdateDomainConfigRequestRequestTypeDef = TypedDict(
@@ -2161,26 +2394,26 @@
         "EncryptionAtRestOptions": EncryptionAtRestOptionsTypeDef,
         "DomainEndpointOptions": DomainEndpointOptionsTypeDef,
         "NodeToNodeEncryptionOptions": NodeToNodeEncryptionOptionsTypeDef,
         "AdvancedSecurityOptions": AdvancedSecurityOptionsInputTypeDef,
         "AutoTuneOptions": AutoTuneOptionsTypeDef,
         "DryRun": bool,
         "DryRunMode": DryRunModeType,
+        "OffPeakWindowOptions": OffPeakWindowOptionsTypeDef,
+        "SoftwareUpdateOptions": SoftwareUpdateOptionsTypeDef,
     },
     total=False,
 )
 
-
 class UpdateDomainConfigRequestRequestTypeDef(
     _RequiredUpdateDomainConfigRequestRequestTypeDef,
     _OptionalUpdateDomainConfigRequestRequestTypeDef,
 ):
     pass
 
-
 AdvancedSecurityOptionsStatusTypeDef = TypedDict(
     "AdvancedSecurityOptionsStatusTypeDef",
     {
         "Options": AdvancedSecurityOptionsTypeDef,
         "Status": OptionStatusTypeDef,
     },
 )
@@ -2214,28 +2447,28 @@
         "AdvancedOptions": Dict[str, str],
         "LogPublishingOptions": Dict[LogTypeType, LogPublishingOptionTypeDef],
         "ServiceSoftwareOptions": ServiceSoftwareOptionsTypeDef,
         "DomainEndpointOptions": DomainEndpointOptionsTypeDef,
         "AdvancedSecurityOptions": AdvancedSecurityOptionsTypeDef,
         "AutoTuneOptions": AutoTuneOptionsOutputTypeDef,
         "ChangeProgressDetails": ChangeProgressDetailsTypeDef,
+        "OffPeakWindowOptions": OffPeakWindowOptionsTypeDef,
+        "SoftwareUpdateOptions": SoftwareUpdateOptionsTypeDef,
     },
     total=False,
 )
 
-
 class DomainStatusTypeDef(_RequiredDomainStatusTypeDef, _OptionalDomainStatusTypeDef):
     pass
 
-
 DescribeInstanceTypeLimitsResponseTypeDef = TypedDict(
     "DescribeInstanceTypeLimitsResponseTypeDef",
     {
         "LimitsByRole": Dict[str, LimitsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DomainConfigTypeDef = TypedDict(
     "DomainConfigTypeDef",
     {
         "EngineVersion": VersionStatusTypeDef,
@@ -2249,70 +2482,72 @@
         "NodeToNodeEncryptionOptions": NodeToNodeEncryptionOptionsStatusTypeDef,
         "AdvancedOptions": AdvancedOptionsStatusTypeDef,
         "LogPublishingOptions": LogPublishingOptionsStatusTypeDef,
         "DomainEndpointOptions": DomainEndpointOptionsStatusTypeDef,
         "AdvancedSecurityOptions": AdvancedSecurityOptionsStatusTypeDef,
         "AutoTuneOptions": AutoTuneOptionsStatusTypeDef,
         "ChangeProgressDetails": ChangeProgressDetailsTypeDef,
+        "OffPeakWindowOptions": OffPeakWindowOptionsStatusTypeDef,
+        "SoftwareUpdateOptions": SoftwareUpdateOptionsStatusTypeDef,
     },
     total=False,
 )
 
 CreateDomainResponseTypeDef = TypedDict(
     "CreateDomainResponseTypeDef",
     {
         "DomainStatus": DomainStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteDomainResponseTypeDef = TypedDict(
     "DeleteDomainResponseTypeDef",
     {
         "DomainStatus": DomainStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDomainResponseTypeDef = TypedDict(
     "DescribeDomainResponseTypeDef",
     {
         "DomainStatus": DomainStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDomainsResponseTypeDef = TypedDict(
     "DescribeDomainsResponseTypeDef",
     {
         "DomainStatusList": List[DomainStatusTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDryRunProgressResponseTypeDef = TypedDict(
     "DescribeDryRunProgressResponseTypeDef",
     {
         "DryRunProgressStatus": DryRunProgressStatusTypeDef,
         "DryRunConfig": DomainStatusTypeDef,
         "DryRunResults": DryRunResultsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDomainConfigResponseTypeDef = TypedDict(
     "DescribeDomainConfigResponseTypeDef",
     {
         "DomainConfig": DomainConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDomainConfigResponseTypeDef = TypedDict(
     "UpdateDomainConfigResponseTypeDef",
     {
         "DomainConfig": DomainConfigTypeDef,
         "DryRunResults": DryRunResultsTypeDef,
         "DryRunProgressStatus": DryRunProgressStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-opensearch-2.5.0.post1/types_aiobotocore_opensearch/type_defs.pyi` & `types-aiobotocore-opensearch-2.5.1/types_aiobotocore_opensearch/type_defs.py`

 * *Files 9% similar despite different names*

```diff
@@ -12,94 +12,111 @@
     ```
 """
 import sys
 from datetime import datetime
 from typing import Dict, List, Mapping, Sequence, Union
 
 from .literals import (
+    ActionSeverityType,
+    ActionStatusType,
+    ActionTypeType,
     AutoTuneDesiredStateType,
     AutoTuneStateType,
     ConnectionModeType,
     DeploymentStatusType,
     DescribePackagesFilterNameType,
+    DomainHealthType,
     DomainPackageStatusType,
+    DomainStateType,
     DryRunModeType,
     EngineTypeType,
     InboundConnectionStatusCodeType,
     LogTypeType,
+    MasterNodeStatusType,
+    NodeStatusType,
+    NodeTypeType,
     OpenSearchPartitionInstanceTypeType,
     OpenSearchWarmPartitionInstanceTypeType,
     OptionStateType,
     OutboundConnectionStatusCodeType,
     OverallChangeStatusType,
     PackageStatusType,
     PrincipalTypeType,
     ReservedInstancePaymentOptionType,
     RollbackOnDisableType,
+    ScheduleAtType,
     ScheduledAutoTuneActionTypeType,
     ScheduledAutoTuneSeverityTypeType,
+    ScheduledByType,
+    SkipUnavailableStatusType,
     TLSSecurityPolicyType,
     UpgradeStatusType,
     UpgradeStepType,
     VolumeTypeType,
     VpcEndpointErrorCodeType,
     VpcEndpointStatusType,
+    ZoneStatusType,
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
     "AWSDomainInformationTypeDef",
     "AcceptInboundConnectionRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "OptionStatusTypeDef",
     "TagTypeDef",
     "AdditionalLimitTypeDef",
     "MasterUserOptionsTypeDef",
     "AssociatePackageRequestRequestTypeDef",
     "AuthorizeVpcEndpointAccessRequestRequestTypeDef",
     "AuthorizedPrincipalTypeDef",
     "ScheduledAutoTuneDetailsTypeDef",
     "DurationTypeDef",
     "AutoTuneOptionsOutputTypeDef",
     "AutoTuneStatusTypeDef",
+    "AvailabilityZoneInfoTypeDef",
     "CancelServiceSoftwareUpdateRequestRequestTypeDef",
     "ServiceSoftwareOptionsTypeDef",
     "ChangeProgressDetailsTypeDef",
     "ChangeProgressStageTypeDef",
     "ColdStorageOptionsTypeDef",
     "ZoneAwarenessConfigTypeDef",
     "CognitoOptionsTypeDef",
     "CompatibleVersionsMapTypeDef",
-    "ConnectionPropertiesTypeDef",
+    "CrossClusterSearchConnectionPropertiesTypeDef",
     "DomainEndpointOptionsTypeDef",
     "EBSOptionsTypeDef",
     "EncryptionAtRestOptionsTypeDef",
     "LogPublishingOptionTypeDef",
     "NodeToNodeEncryptionOptionsTypeDef",
     "SnapshotOptionsTypeDef",
+    "SoftwareUpdateOptionsTypeDef",
     "VPCOptionsTypeDef",
     "OutboundConnectionStatusTypeDef",
     "PackageSourceTypeDef",
     "DeleteDomainRequestRequestTypeDef",
     "DeleteInboundConnectionRequestRequestTypeDef",
     "DeleteOutboundConnectionRequestRequestTypeDef",
     "DeletePackageRequestRequestTypeDef",
     "DeleteVpcEndpointRequestRequestTypeDef",
     "VpcEndpointSummaryTypeDef",
     "DescribeDomainAutoTunesRequestRequestTypeDef",
     "DescribeDomainChangeProgressRequestRequestTypeDef",
     "DescribeDomainConfigRequestRequestTypeDef",
+    "DescribeDomainHealthRequestRequestTypeDef",
+    "DescribeDomainNodesRequestRequestTypeDef",
+    "DomainNodesStatusTypeDef",
     "DescribeDomainRequestRequestTypeDef",
     "DescribeDomainsRequestRequestTypeDef",
     "DescribeDryRunProgressRequestRequestTypeDef",
     "DryRunResultsTypeDef",
     "FilterTypeDef",
     "DescribeInstanceTypeLimitsRequestRequestTypeDef",
     "DescribePackagesFilterTypeDef",
@@ -108,127 +125,142 @@
     "DescribeVpcEndpointsRequestRequestTypeDef",
     "VpcEndpointErrorTypeDef",
     "DissociatePackageRequestRequestTypeDef",
     "DomainInfoTypeDef",
     "ErrorDetailsTypeDef",
     "VPCDerivedInfoTypeDef",
     "ValidationFailureTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetCompatibleVersionsRequestRequestTypeDef",
     "GetPackageVersionHistoryRequestRequestTypeDef",
     "PackageVersionHistoryTypeDef",
     "GetUpgradeHistoryRequestRequestTypeDef",
     "GetUpgradeStatusRequestRequestTypeDef",
+    "GetUpgradeStatusResponseTypeDef",
     "InboundConnectionStatusTypeDef",
     "InstanceCountLimitsTypeDef",
     "InstanceTypeDetailsTypeDef",
     "ListDomainNamesRequestRequestTypeDef",
     "ListDomainsForPackageRequestRequestTypeDef",
     "ListInstanceTypeDetailsRequestRequestTypeDef",
     "ListPackagesForDomainRequestRequestTypeDef",
+    "ListScheduledActionsRequestRequestTypeDef",
+    "ScheduledActionTypeDef",
     "ListTagsRequestRequestTypeDef",
     "ListVersionsRequestRequestTypeDef",
+    "ListVersionsResponseTypeDef",
     "ListVpcEndpointAccessRequestRequestTypeDef",
     "ListVpcEndpointsForDomainRequestRequestTypeDef",
     "ListVpcEndpointsRequestRequestTypeDef",
+    "WindowStartTimeTypeDef",
     "PurchaseReservedInstanceOfferingRequestRequestTypeDef",
+    "PurchaseReservedInstanceOfferingResponseTypeDef",
     "RecurringChargeTypeDef",
     "RejectInboundConnectionRequestRequestTypeDef",
     "RemoveTagsRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "RevokeVpcEndpointAccessRequestRequestTypeDef",
     "SAMLIdpTypeDef",
     "StartServiceSoftwareUpdateRequestRequestTypeDef",
     "StorageTypeLimitTypeDef",
+    "UpdateScheduledActionRequestRequestTypeDef",
     "UpgradeDomainRequestRequestTypeDef",
     "UpgradeStepItemTypeDef",
     "DomainInformationContainerTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetUpgradeStatusResponseTypeDef",
-    "ListVersionsResponseTypeDef",
-    "PurchaseReservedInstanceOfferingResponseTypeDef",
     "AccessPoliciesStatusTypeDef",
     "AdvancedOptionsStatusTypeDef",
     "VersionStatusTypeDef",
     "AddTagsRequestRequestTypeDef",
     "ListTagsResponseTypeDef",
     "AuthorizeVpcEndpointAccessResponseTypeDef",
     "ListVpcEndpointAccessResponseTypeDef",
     "AutoTuneDetailsTypeDef",
     "AutoTuneMaintenanceScheduleTypeDef",
+    "EnvironmentInfoTypeDef",
     "CancelServiceSoftwareUpdateResponseTypeDef",
     "StartServiceSoftwareUpdateResponseTypeDef",
     "UpgradeDomainResponseTypeDef",
     "ChangeProgressStatusDetailsTypeDef",
     "ClusterConfigTypeDef",
     "CognitoOptionsStatusTypeDef",
     "GetCompatibleVersionsResponseTypeDef",
+    "ConnectionPropertiesTypeDef",
     "DomainEndpointOptionsStatusTypeDef",
     "EBSOptionsStatusTypeDef",
     "EncryptionAtRestOptionsStatusTypeDef",
     "LogPublishingOptionsStatusTypeDef",
     "NodeToNodeEncryptionOptionsStatusTypeDef",
     "SnapshotOptionsStatusTypeDef",
+    "SoftwareUpdateOptionsStatusTypeDef",
     "CreateVpcEndpointRequestRequestTypeDef",
     "UpdateVpcEndpointRequestRequestTypeDef",
     "CreatePackageRequestRequestTypeDef",
     "UpdatePackageRequestRequestTypeDef",
     "DeleteVpcEndpointResponseTypeDef",
     "ListVpcEndpointsForDomainResponseTypeDef",
     "ListVpcEndpointsResponseTypeDef",
+    "DescribeDomainNodesResponseTypeDef",
     "DescribeInboundConnectionsRequestRequestTypeDef",
     "DescribeOutboundConnectionsRequestRequestTypeDef",
     "DescribePackagesRequestRequestTypeDef",
     "ListDomainNamesResponseTypeDef",
     "DomainPackageDetailsTypeDef",
     "PackageDetailsTypeDef",
     "VPCDerivedInfoStatusTypeDef",
     "VpcEndpointTypeDef",
     "DryRunProgressStatusTypeDef",
     "GetPackageVersionHistoryResponseTypeDef",
     "InstanceLimitsTypeDef",
     "ListInstanceTypeDetailsResponseTypeDef",
+    "ListScheduledActionsResponseTypeDef",
+    "UpdateScheduledActionResponseTypeDef",
+    "OffPeakWindowTypeDef",
     "ReservedInstanceOfferingTypeDef",
     "ReservedInstanceTypeDef",
     "SAMLOptionsInputTypeDef",
     "SAMLOptionsOutputTypeDef",
     "StorageTypeTypeDef",
     "UpgradeHistoryTypeDef",
-    "CreateOutboundConnectionRequestRequestTypeDef",
-    "CreateOutboundConnectionResponseTypeDef",
     "InboundConnectionTypeDef",
-    "OutboundConnectionTypeDef",
     "AutoTuneTypeDef",
     "AutoTuneOptionsInputTypeDef",
     "AutoTuneOptionsTypeDef",
+    "DescribeDomainHealthResponseTypeDef",
     "DescribeDomainChangeProgressResponseTypeDef",
     "ClusterConfigStatusTypeDef",
+    "CreateOutboundConnectionRequestRequestTypeDef",
+    "CreateOutboundConnectionResponseTypeDef",
+    "OutboundConnectionTypeDef",
     "AssociatePackageResponseTypeDef",
     "DissociatePackageResponseTypeDef",
     "ListDomainsForPackageResponseTypeDef",
     "ListPackagesForDomainResponseTypeDef",
     "CreatePackageResponseTypeDef",
     "DeletePackageResponseTypeDef",
     "DescribePackagesResponseTypeDef",
     "UpdatePackageResponseTypeDef",
     "CreateVpcEndpointResponseTypeDef",
     "DescribeVpcEndpointsResponseTypeDef",
     "UpdateVpcEndpointResponseTypeDef",
+    "OffPeakWindowOptionsTypeDef",
     "DescribeReservedInstanceOfferingsResponseTypeDef",
     "DescribeReservedInstancesResponseTypeDef",
     "AdvancedSecurityOptionsInputTypeDef",
     "AdvancedSecurityOptionsTypeDef",
     "LimitsTypeDef",
     "GetUpgradeHistoryResponseTypeDef",
     "AcceptInboundConnectionResponseTypeDef",
     "DeleteInboundConnectionResponseTypeDef",
     "DescribeInboundConnectionsResponseTypeDef",
     "RejectInboundConnectionResponseTypeDef",
-    "DeleteOutboundConnectionResponseTypeDef",
-    "DescribeOutboundConnectionsResponseTypeDef",
     "DescribeDomainAutoTunesResponseTypeDef",
     "AutoTuneOptionsStatusTypeDef",
+    "DeleteOutboundConnectionResponseTypeDef",
+    "DescribeOutboundConnectionsResponseTypeDef",
+    "OffPeakWindowOptionsStatusTypeDef",
     "CreateDomainRequestRequestTypeDef",
     "UpdateDomainConfigRequestRequestTypeDef",
     "AdvancedSecurityOptionsStatusTypeDef",
     "DomainStatusTypeDef",
     "DescribeInstanceTypeLimitsResponseTypeDef",
     "DomainConfigTypeDef",
     "CreateDomainResponseTypeDef",
@@ -251,37 +283,28 @@
     {
         "OwnerId": str,
         "Region": str,
     },
     total=False,
 )
 
+
 class AWSDomainInformationTypeDef(
     _RequiredAWSDomainInformationTypeDef, _OptionalAWSDomainInformationTypeDef
 ):
     pass
 
+
 AcceptInboundConnectionRequestRequestTypeDef = TypedDict(
     "AcceptInboundConnectionRequestRequestTypeDef",
     {
         "ConnectionId": str,
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
 _RequiredOptionStatusTypeDef = TypedDict(
     "_RequiredOptionStatusTypeDef",
     {
         "CreationDate": datetime,
         "UpdateDate": datetime,
         "State": OptionStateType,
     },
@@ -291,17 +314,19 @@
     {
         "UpdateVersion": int,
         "PendingDeletion": bool,
     },
     total=False,
 )
 
+
 class OptionStatusTypeDef(_RequiredOptionStatusTypeDef, _OptionalOptionStatusTypeDef):
     pass
 
+
 TagTypeDef = TypedDict(
     "TagTypeDef",
     {
         "Key": str,
         "Value": str,
     },
 )
@@ -371,14 +396,15 @@
 )
 
 AutoTuneOptionsOutputTypeDef = TypedDict(
     "AutoTuneOptionsOutputTypeDef",
     {
         "State": AutoTuneStateType,
         "ErrorMessage": str,
+        "UseOffPeakWindow": bool,
     },
     total=False,
 )
 
 _RequiredAutoTuneStatusTypeDef = TypedDict(
     "_RequiredAutoTuneStatusTypeDef",
     {
@@ -393,17 +419,32 @@
         "UpdateVersion": int,
         "ErrorMessage": str,
         "PendingDeletion": bool,
     },
     total=False,
 )
 
+
 class AutoTuneStatusTypeDef(_RequiredAutoTuneStatusTypeDef, _OptionalAutoTuneStatusTypeDef):
     pass
 
+
+AvailabilityZoneInfoTypeDef = TypedDict(
+    "AvailabilityZoneInfoTypeDef",
+    {
+        "AvailabilityZoneName": str,
+        "ZoneStatus": ZoneStatusType,
+        "ConfiguredDataNodeCount": str,
+        "AvailableDataNodeCount": str,
+        "TotalShards": str,
+        "TotalUnAssignedShards": str,
+    },
+    total=False,
+)
+
 CancelServiceSoftwareUpdateRequestRequestTypeDef = TypedDict(
     "CancelServiceSoftwareUpdateRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 
@@ -473,18 +514,18 @@
     {
         "SourceVersion": str,
         "TargetVersions": List[str],
     },
     total=False,
 )
 
-ConnectionPropertiesTypeDef = TypedDict(
-    "ConnectionPropertiesTypeDef",
+CrossClusterSearchConnectionPropertiesTypeDef = TypedDict(
+    "CrossClusterSearchConnectionPropertiesTypeDef",
     {
-        "Endpoint": str,
+        "SkipUnavailable": SkipUnavailableStatusType,
     },
     total=False,
 )
 
 DomainEndpointOptionsTypeDef = TypedDict(
     "DomainEndpointOptionsTypeDef",
     {
@@ -539,14 +580,22 @@
     "SnapshotOptionsTypeDef",
     {
         "AutomatedSnapshotStartHour": int,
     },
     total=False,
 )
 
+SoftwareUpdateOptionsTypeDef = TypedDict(
+    "SoftwareUpdateOptionsTypeDef",
+    {
+        "AutoSoftwareUpdateEnabled": bool,
+    },
+    total=False,
+)
+
 VPCOptionsTypeDef = TypedDict(
     "VPCOptionsTypeDef",
     {
         "SubnetIds": Sequence[str],
         "SecurityGroupIds": Sequence[str],
     },
     total=False,
@@ -627,47 +676,80 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class DescribeDomainAutoTunesRequestRequestTypeDef(
     _RequiredDescribeDomainAutoTunesRequestRequestTypeDef,
     _OptionalDescribeDomainAutoTunesRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredDescribeDomainChangeProgressRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeDomainChangeProgressRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 _OptionalDescribeDomainChangeProgressRequestRequestTypeDef = TypedDict(
     "_OptionalDescribeDomainChangeProgressRequestRequestTypeDef",
     {
         "ChangeId": str,
     },
     total=False,
 )
 
+
 class DescribeDomainChangeProgressRequestRequestTypeDef(
     _RequiredDescribeDomainChangeProgressRequestRequestTypeDef,
     _OptionalDescribeDomainChangeProgressRequestRequestTypeDef,
 ):
     pass
 
+
 DescribeDomainConfigRequestRequestTypeDef = TypedDict(
     "DescribeDomainConfigRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 
+DescribeDomainHealthRequestRequestTypeDef = TypedDict(
+    "DescribeDomainHealthRequestRequestTypeDef",
+    {
+        "DomainName": str,
+    },
+)
+
+DescribeDomainNodesRequestRequestTypeDef = TypedDict(
+    "DescribeDomainNodesRequestRequestTypeDef",
+    {
+        "DomainName": str,
+    },
+)
+
+DomainNodesStatusTypeDef = TypedDict(
+    "DomainNodesStatusTypeDef",
+    {
+        "NodeId": str,
+        "NodeType": NodeTypeType,
+        "AvailabilityZone": str,
+        "InstanceType": OpenSearchPartitionInstanceTypeType,
+        "NodeStatus": NodeStatusType,
+        "StorageType": str,
+        "StorageVolumeType": VolumeTypeType,
+        "StorageSize": str,
+    },
+    total=False,
+)
+
 DescribeDomainRequestRequestTypeDef = TypedDict(
     "DescribeDomainRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 
@@ -689,20 +771,22 @@
     {
         "DryRunId": str,
         "LoadDryRunConfig": bool,
     },
     total=False,
 )
 
+
 class DescribeDryRunProgressRequestRequestTypeDef(
     _RequiredDescribeDryRunProgressRequestRequestTypeDef,
     _OptionalDescribeDryRunProgressRequestRequestTypeDef,
 ):
     pass
 
+
 DryRunResultsTypeDef = TypedDict(
     "DryRunResultsTypeDef",
     {
         "DeploymentType": str,
         "Message": str,
     },
     total=False,
@@ -728,20 +812,22 @@
     "_OptionalDescribeInstanceTypeLimitsRequestRequestTypeDef",
     {
         "DomainName": str,
     },
     total=False,
 )
 
+
 class DescribeInstanceTypeLimitsRequestRequestTypeDef(
     _RequiredDescribeInstanceTypeLimitsRequestRequestTypeDef,
     _OptionalDescribeInstanceTypeLimitsRequestRequestTypeDef,
 ):
     pass
 
+
 DescribePackagesFilterTypeDef = TypedDict(
     "DescribePackagesFilterTypeDef",
     {
         "Name": DescribePackagesFilterNameType,
         "Value": Sequence[str],
     },
     total=False,
@@ -826,14 +912,21 @@
     {
         "Code": str,
         "Message": str,
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
 GetCompatibleVersionsRequestRequestTypeDef = TypedDict(
     "GetCompatibleVersionsRequestRequestTypeDef",
     {
         "DomainName": str,
     },
     total=False,
 )
@@ -849,20 +942,22 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class GetPackageVersionHistoryRequestRequestTypeDef(
     _RequiredGetPackageVersionHistoryRequestRequestTypeDef,
     _OptionalGetPackageVersionHistoryRequestRequestTypeDef,
 ):
     pass
 
+
 PackageVersionHistoryTypeDef = TypedDict(
     "PackageVersionHistoryTypeDef",
     {
         "PackageVersion": str,
         "CommitMessage": str,
         "CreatedAt": datetime,
     },
@@ -880,26 +975,38 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class GetUpgradeHistoryRequestRequestTypeDef(
     _RequiredGetUpgradeHistoryRequestRequestTypeDef, _OptionalGetUpgradeHistoryRequestRequestTypeDef
 ):
     pass
 
+
 GetUpgradeStatusRequestRequestTypeDef = TypedDict(
     "GetUpgradeStatusRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 
+GetUpgradeStatusResponseTypeDef = TypedDict(
+    "GetUpgradeStatusResponseTypeDef",
+    {
+        "UpgradeStep": UpgradeStepType,
+        "StepStatus": UpgradeStatusType,
+        "UpgradeName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 InboundConnectionStatusTypeDef = TypedDict(
     "InboundConnectionStatusTypeDef",
     {
         "StatusCode": InboundConnectionStatusCodeType,
         "Message": str,
     },
     total=False,
@@ -920,14 +1027,15 @@
         "InstanceType": OpenSearchPartitionInstanceTypeType,
         "EncryptionEnabled": bool,
         "CognitoEnabled": bool,
         "AppLogsEnabled": bool,
         "AdvancedSecurityEnabled": bool,
         "WarmEnabled": bool,
         "InstanceRole": List[str],
+        "AvailabilityZones": List[str],
     },
     total=False,
 )
 
 ListDomainNamesRequestRequestTypeDef = TypedDict(
     "ListDomainNamesRequestRequestTypeDef",
     {
@@ -947,42 +1055,48 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class ListDomainsForPackageRequestRequestTypeDef(
     _RequiredListDomainsForPackageRequestRequestTypeDef,
     _OptionalListDomainsForPackageRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredListInstanceTypeDetailsRequestRequestTypeDef = TypedDict(
     "_RequiredListInstanceTypeDetailsRequestRequestTypeDef",
     {
         "EngineVersion": str,
     },
 )
 _OptionalListInstanceTypeDetailsRequestRequestTypeDef = TypedDict(
     "_OptionalListInstanceTypeDetailsRequestRequestTypeDef",
     {
         "DomainName": str,
         "MaxResults": int,
         "NextToken": str,
+        "RetrieveAZs": bool,
+        "InstanceType": str,
     },
     total=False,
 )
 
+
 class ListInstanceTypeDetailsRequestRequestTypeDef(
     _RequiredListInstanceTypeDetailsRequestRequestTypeDef,
     _OptionalListInstanceTypeDetailsRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredListPackagesForDomainRequestRequestTypeDef = TypedDict(
     "_RequiredListPackagesForDomainRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 _OptionalListPackagesForDomainRequestRequestTypeDef = TypedDict(
@@ -990,20 +1104,71 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class ListPackagesForDomainRequestRequestTypeDef(
     _RequiredListPackagesForDomainRequestRequestTypeDef,
     _OptionalListPackagesForDomainRequestRequestTypeDef,
 ):
     pass
 
+
+_RequiredListScheduledActionsRequestRequestTypeDef = TypedDict(
+    "_RequiredListScheduledActionsRequestRequestTypeDef",
+    {
+        "DomainName": str,
+    },
+)
+_OptionalListScheduledActionsRequestRequestTypeDef = TypedDict(
+    "_OptionalListScheduledActionsRequestRequestTypeDef",
+    {
+        "MaxResults": int,
+        "NextToken": str,
+    },
+    total=False,
+)
+
+
+class ListScheduledActionsRequestRequestTypeDef(
+    _RequiredListScheduledActionsRequestRequestTypeDef,
+    _OptionalListScheduledActionsRequestRequestTypeDef,
+):
+    pass
+
+
+_RequiredScheduledActionTypeDef = TypedDict(
+    "_RequiredScheduledActionTypeDef",
+    {
+        "Id": str,
+        "Type": ActionTypeType,
+        "Severity": ActionSeverityType,
+        "ScheduledTime": int,
+    },
+)
+_OptionalScheduledActionTypeDef = TypedDict(
+    "_OptionalScheduledActionTypeDef",
+    {
+        "Description": str,
+        "ScheduledBy": ScheduledByType,
+        "Status": ActionStatusType,
+        "Mandatory": bool,
+        "Cancellable": bool,
+    },
+    total=False,
+)
+
+
+class ScheduledActionTypeDef(_RequiredScheduledActionTypeDef, _OptionalScheduledActionTypeDef):
+    pass
+
+
 ListTagsRequestRequestTypeDef = TypedDict(
     "ListTagsRequestRequestTypeDef",
     {
         "ARN": str,
     },
 )
 
@@ -1012,62 +1177,83 @@
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListVersionsResponseTypeDef = TypedDict(
+    "ListVersionsResponseTypeDef",
+    {
+        "Versions": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredListVpcEndpointAccessRequestRequestTypeDef = TypedDict(
     "_RequiredListVpcEndpointAccessRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 _OptionalListVpcEndpointAccessRequestRequestTypeDef = TypedDict(
     "_OptionalListVpcEndpointAccessRequestRequestTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
+
 class ListVpcEndpointAccessRequestRequestTypeDef(
     _RequiredListVpcEndpointAccessRequestRequestTypeDef,
     _OptionalListVpcEndpointAccessRequestRequestTypeDef,
 ):
     pass
 
+
 _RequiredListVpcEndpointsForDomainRequestRequestTypeDef = TypedDict(
     "_RequiredListVpcEndpointsForDomainRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 _OptionalListVpcEndpointsForDomainRequestRequestTypeDef = TypedDict(
     "_OptionalListVpcEndpointsForDomainRequestRequestTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
+
 class ListVpcEndpointsForDomainRequestRequestTypeDef(
     _RequiredListVpcEndpointsForDomainRequestRequestTypeDef,
     _OptionalListVpcEndpointsForDomainRequestRequestTypeDef,
 ):
     pass
 
+
 ListVpcEndpointsRequestRequestTypeDef = TypedDict(
     "ListVpcEndpointsRequestRequestTypeDef",
     {
         "NextToken": str,
     },
     total=False,
 )
 
+WindowStartTimeTypeDef = TypedDict(
+    "WindowStartTimeTypeDef",
+    {
+        "Hours": int,
+        "Minutes": int,
+    },
+)
+
 _RequiredPurchaseReservedInstanceOfferingRequestRequestTypeDef = TypedDict(
     "_RequiredPurchaseReservedInstanceOfferingRequestRequestTypeDef",
     {
         "ReservedInstanceOfferingId": str,
         "ReservationName": str,
     },
 )
@@ -1075,20 +1261,31 @@
     "_OptionalPurchaseReservedInstanceOfferingRequestRequestTypeDef",
     {
         "InstanceCount": int,
     },
     total=False,
 )
 
+
 class PurchaseReservedInstanceOfferingRequestRequestTypeDef(
     _RequiredPurchaseReservedInstanceOfferingRequestRequestTypeDef,
     _OptionalPurchaseReservedInstanceOfferingRequestRequestTypeDef,
 ):
     pass
 
+
+PurchaseReservedInstanceOfferingResponseTypeDef = TypedDict(
+    "PurchaseReservedInstanceOfferingResponseTypeDef",
+    {
+        "ReservedInstanceId": str,
+        "ReservationName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RecurringChargeTypeDef = TypedDict(
     "RecurringChargeTypeDef",
     {
         "RecurringChargeAmount": float,
         "RecurringChargeFrequency": str,
     },
     total=False,
@@ -1105,14 +1302,25 @@
     "RemoveTagsRequestRequestTypeDef",
     {
         "ARN": str,
         "TagKeys": Sequence[str],
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
 RevokeVpcEndpointAccessRequestRequestTypeDef = TypedDict(
     "RevokeVpcEndpointAccessRequestRequestTypeDef",
     {
         "DomainName": str,
         "Account": str,
     },
 )
@@ -1121,30 +1329,71 @@
     "SAMLIdpTypeDef",
     {
         "MetadataContent": str,
         "EntityId": str,
     },
 )
 
-StartServiceSoftwareUpdateRequestRequestTypeDef = TypedDict(
-    "StartServiceSoftwareUpdateRequestRequestTypeDef",
+_RequiredStartServiceSoftwareUpdateRequestRequestTypeDef = TypedDict(
+    "_RequiredStartServiceSoftwareUpdateRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
+_OptionalStartServiceSoftwareUpdateRequestRequestTypeDef = TypedDict(
+    "_OptionalStartServiceSoftwareUpdateRequestRequestTypeDef",
+    {
+        "ScheduleAt": ScheduleAtType,
+        "DesiredStartTime": int,
+    },
+    total=False,
+)
+
+
+class StartServiceSoftwareUpdateRequestRequestTypeDef(
+    _RequiredStartServiceSoftwareUpdateRequestRequestTypeDef,
+    _OptionalStartServiceSoftwareUpdateRequestRequestTypeDef,
+):
+    pass
+
 
 StorageTypeLimitTypeDef = TypedDict(
     "StorageTypeLimitTypeDef",
     {
         "LimitName": str,
         "LimitValues": List[str],
     },
     total=False,
 )
 
+_RequiredUpdateScheduledActionRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateScheduledActionRequestRequestTypeDef",
+    {
+        "DomainName": str,
+        "ActionID": str,
+        "ActionType": ActionTypeType,
+        "ScheduleAt": ScheduleAtType,
+    },
+)
+_OptionalUpdateScheduledActionRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateScheduledActionRequestRequestTypeDef",
+    {
+        "DesiredStartTime": int,
+    },
+    total=False,
+)
+
+
+class UpdateScheduledActionRequestRequestTypeDef(
+    _RequiredUpdateScheduledActionRequestRequestTypeDef,
+    _OptionalUpdateScheduledActionRequestRequestTypeDef,
+):
+    pass
+
+
 _RequiredUpgradeDomainRequestRequestTypeDef = TypedDict(
     "_RequiredUpgradeDomainRequestRequestTypeDef",
     {
         "DomainName": str,
         "TargetVersion": str,
     },
 )
@@ -1153,19 +1402,21 @@
     {
         "PerformCheckOnly": bool,
         "AdvancedOptions": Mapping[str, str],
     },
     total=False,
 )
 
+
 class UpgradeDomainRequestRequestTypeDef(
     _RequiredUpgradeDomainRequestRequestTypeDef, _OptionalUpgradeDomainRequestRequestTypeDef
 ):
     pass
 
+
 UpgradeStepItemTypeDef = TypedDict(
     "UpgradeStepItemTypeDef",
     {
         "UpgradeStep": UpgradeStepType,
         "UpgradeStepStatus": UpgradeStatusType,
         "Issues": List[str],
         "ProgressPercent": float,
@@ -1177,49 +1428,14 @@
     "DomainInformationContainerTypeDef",
     {
         "AWSDomainInformation": AWSDomainInformationTypeDef,
     },
     total=False,
 )
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetUpgradeStatusResponseTypeDef = TypedDict(
-    "GetUpgradeStatusResponseTypeDef",
-    {
-        "UpgradeStep": UpgradeStepType,
-        "StepStatus": UpgradeStatusType,
-        "UpgradeName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListVersionsResponseTypeDef = TypedDict(
-    "ListVersionsResponseTypeDef",
-    {
-        "Versions": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PurchaseReservedInstanceOfferingResponseTypeDef = TypedDict(
-    "PurchaseReservedInstanceOfferingResponseTypeDef",
-    {
-        "ReservedInstanceId": str,
-        "ReservationName": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 AccessPoliciesStatusTypeDef = TypedDict(
     "AccessPoliciesStatusTypeDef",
     {
         "Options": str,
         "Status": OptionStatusTypeDef,
     },
 )
@@ -1248,32 +1464,32 @@
     },
 )
 
 ListTagsResponseTypeDef = TypedDict(
     "ListTagsResponseTypeDef",
     {
         "TagList": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AuthorizeVpcEndpointAccessResponseTypeDef = TypedDict(
     "AuthorizeVpcEndpointAccessResponseTypeDef",
     {
         "AuthorizedPrincipal": AuthorizedPrincipalTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVpcEndpointAccessResponseTypeDef = TypedDict(
     "ListVpcEndpointAccessResponseTypeDef",
     {
         "AuthorizedPrincipalList": List[AuthorizedPrincipalTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AutoTuneDetailsTypeDef = TypedDict(
     "AutoTuneDetailsTypeDef",
     {
         "ScheduledAutoTuneDetails": ScheduledAutoTuneDetailsTypeDef,
@@ -1287,40 +1503,48 @@
         "StartAt": Union[datetime, str],
         "Duration": DurationTypeDef,
         "CronExpressionForRecurrence": str,
     },
     total=False,
 )
 
+EnvironmentInfoTypeDef = TypedDict(
+    "EnvironmentInfoTypeDef",
+    {
+        "AvailabilityZoneInformation": List[AvailabilityZoneInfoTypeDef],
+    },
+    total=False,
+)
+
 CancelServiceSoftwareUpdateResponseTypeDef = TypedDict(
     "CancelServiceSoftwareUpdateResponseTypeDef",
     {
         "ServiceSoftwareOptions": ServiceSoftwareOptionsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartServiceSoftwareUpdateResponseTypeDef = TypedDict(
     "StartServiceSoftwareUpdateResponseTypeDef",
     {
         "ServiceSoftwareOptions": ServiceSoftwareOptionsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpgradeDomainResponseTypeDef = TypedDict(
     "UpgradeDomainResponseTypeDef",
     {
         "UpgradeId": str,
         "DomainName": str,
         "TargetVersion": str,
         "PerformCheckOnly": bool,
         "AdvancedOptions": Dict[str, str],
         "ChangeProgressDetails": ChangeProgressDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ChangeProgressStatusDetailsTypeDef = TypedDict(
     "ChangeProgressStatusDetailsTypeDef",
     {
         "ChangeId": str,
@@ -1344,14 +1568,15 @@
         "ZoneAwarenessConfig": ZoneAwarenessConfigTypeDef,
         "DedicatedMasterType": OpenSearchPartitionInstanceTypeType,
         "DedicatedMasterCount": int,
         "WarmEnabled": bool,
         "WarmType": OpenSearchWarmPartitionInstanceTypeType,
         "WarmCount": int,
         "ColdStorageOptions": ColdStorageOptionsTypeDef,
+        "MultiAZWithStandbyEnabled": bool,
     },
     total=False,
 )
 
 CognitoOptionsStatusTypeDef = TypedDict(
     "CognitoOptionsStatusTypeDef",
     {
@@ -1360,18 +1585,27 @@
     },
 )
 
 GetCompatibleVersionsResponseTypeDef = TypedDict(
     "GetCompatibleVersionsResponseTypeDef",
     {
         "CompatibleVersions": List[CompatibleVersionsMapTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
+ConnectionPropertiesTypeDef = TypedDict(
+    "ConnectionPropertiesTypeDef",
+    {
+        "Endpoint": str,
+        "CrossClusterSearch": CrossClusterSearchConnectionPropertiesTypeDef,
+    },
+    total=False,
+)
+
 DomainEndpointOptionsStatusTypeDef = TypedDict(
     "DomainEndpointOptionsStatusTypeDef",
     {
         "Options": DomainEndpointOptionsTypeDef,
         "Status": OptionStatusTypeDef,
     },
 )
@@ -1413,14 +1647,23 @@
     "SnapshotOptionsStatusTypeDef",
     {
         "Options": SnapshotOptionsTypeDef,
         "Status": OptionStatusTypeDef,
     },
 )
 
+SoftwareUpdateOptionsStatusTypeDef = TypedDict(
+    "SoftwareUpdateOptionsStatusTypeDef",
+    {
+        "Options": SoftwareUpdateOptionsTypeDef,
+        "Status": OptionStatusTypeDef,
+    },
+    total=False,
+)
+
 _RequiredCreateVpcEndpointRequestRequestTypeDef = TypedDict(
     "_RequiredCreateVpcEndpointRequestRequestTypeDef",
     {
         "DomainArn": str,
         "VpcOptions": VPCOptionsTypeDef,
     },
 )
@@ -1428,19 +1671,21 @@
     "_OptionalCreateVpcEndpointRequestRequestTypeDef",
     {
         "ClientToken": str,
     },
     total=False,
 )
 
+
 class CreateVpcEndpointRequestRequestTypeDef(
     _RequiredCreateVpcEndpointRequestRequestTypeDef, _OptionalCreateVpcEndpointRequestRequestTypeDef
 ):
     pass
 
+
 UpdateVpcEndpointRequestRequestTypeDef = TypedDict(
     "UpdateVpcEndpointRequestRequestTypeDef",
     {
         "VpcEndpointId": str,
         "VpcOptions": VPCOptionsTypeDef,
     },
 )
@@ -1457,19 +1702,21 @@
     "_OptionalCreatePackageRequestRequestTypeDef",
     {
         "PackageDescription": str,
     },
     total=False,
 )
 
+
 class CreatePackageRequestRequestTypeDef(
     _RequiredCreatePackageRequestRequestTypeDef, _OptionalCreatePackageRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredUpdatePackageRequestRequestTypeDef = TypedDict(
     "_RequiredUpdatePackageRequestRequestTypeDef",
     {
         "PackageID": str,
         "PackageSource": PackageSourceTypeDef,
     },
 )
@@ -1478,42 +1725,52 @@
     {
         "PackageDescription": str,
         "CommitMessage": str,
     },
     total=False,
 )
 
+
 class UpdatePackageRequestRequestTypeDef(
     _RequiredUpdatePackageRequestRequestTypeDef, _OptionalUpdatePackageRequestRequestTypeDef
 ):
     pass
 
+
 DeleteVpcEndpointResponseTypeDef = TypedDict(
     "DeleteVpcEndpointResponseTypeDef",
     {
         "VpcEndpointSummary": VpcEndpointSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVpcEndpointsForDomainResponseTypeDef = TypedDict(
     "ListVpcEndpointsForDomainResponseTypeDef",
     {
         "VpcEndpointSummaryList": List[VpcEndpointSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVpcEndpointsResponseTypeDef = TypedDict(
     "ListVpcEndpointsResponseTypeDef",
     {
         "VpcEndpointSummaryList": List[VpcEndpointSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeDomainNodesResponseTypeDef = TypedDict(
+    "DescribeDomainNodesResponseTypeDef",
+    {
+        "DomainNodesStatusList": List[DomainNodesStatusTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeInboundConnectionsRequestRequestTypeDef = TypedDict(
     "DescribeInboundConnectionsRequestRequestTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
@@ -1543,15 +1800,15 @@
     total=False,
 )
 
 ListDomainNamesResponseTypeDef = TypedDict(
     "ListDomainNamesResponseTypeDef",
     {
         "DomainNames": List[DomainInfoTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DomainPackageDetailsTypeDef = TypedDict(
     "DomainPackageDetailsTypeDef",
     {
         "PackageID": str,
@@ -1617,26 +1874,28 @@
     "_OptionalDryRunProgressStatusTypeDef",
     {
         "ValidationFailures": List[ValidationFailureTypeDef],
     },
     total=False,
 )
 
+
 class DryRunProgressStatusTypeDef(
     _RequiredDryRunProgressStatusTypeDef, _OptionalDryRunProgressStatusTypeDef
 ):
     pass
 
+
 GetPackageVersionHistoryResponseTypeDef = TypedDict(
     "GetPackageVersionHistoryResponseTypeDef",
     {
         "PackageID": str,
         "PackageVersionHistoryList": List[PackageVersionHistoryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InstanceLimitsTypeDef = TypedDict(
     "InstanceLimitsTypeDef",
     {
         "InstanceCountLimits": InstanceCountLimitsTypeDef,
@@ -1645,18 +1904,43 @@
 )
 
 ListInstanceTypeDetailsResponseTypeDef = TypedDict(
     "ListInstanceTypeDetailsResponseTypeDef",
     {
         "InstanceTypeDetails": List[InstanceTypeDetailsTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListScheduledActionsResponseTypeDef = TypedDict(
+    "ListScheduledActionsResponseTypeDef",
+    {
+        "ScheduledActions": List[ScheduledActionTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
+UpdateScheduledActionResponseTypeDef = TypedDict(
+    "UpdateScheduledActionResponseTypeDef",
+    {
+        "ScheduledAction": ScheduledActionTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+OffPeakWindowTypeDef = TypedDict(
+    "OffPeakWindowTypeDef",
+    {
+        "WindowStartTime": WindowStartTimeTypeDef,
+    },
+    total=False,
+)
+
 ReservedInstanceOfferingTypeDef = TypedDict(
     "ReservedInstanceOfferingTypeDef",
     {
         "ReservedInstanceOfferingId": str,
         "InstanceType": OpenSearchPartitionInstanceTypeType,
         "Duration": int,
         "FixedPrice": float,
@@ -1732,227 +2016,261 @@
         "StartTimestamp": datetime,
         "UpgradeStatus": UpgradeStatusType,
         "StepsList": List[UpgradeStepItemTypeDef],
     },
     total=False,
 )
 
-_RequiredCreateOutboundConnectionRequestRequestTypeDef = TypedDict(
-    "_RequiredCreateOutboundConnectionRequestRequestTypeDef",
-    {
-        "LocalDomainInfo": DomainInformationContainerTypeDef,
-        "RemoteDomainInfo": DomainInformationContainerTypeDef,
-        "ConnectionAlias": str,
-    },
-)
-_OptionalCreateOutboundConnectionRequestRequestTypeDef = TypedDict(
-    "_OptionalCreateOutboundConnectionRequestRequestTypeDef",
-    {
-        "ConnectionMode": ConnectionModeType,
-    },
-    total=False,
-)
-
-class CreateOutboundConnectionRequestRequestTypeDef(
-    _RequiredCreateOutboundConnectionRequestRequestTypeDef,
-    _OptionalCreateOutboundConnectionRequestRequestTypeDef,
-):
-    pass
-
-CreateOutboundConnectionResponseTypeDef = TypedDict(
-    "CreateOutboundConnectionResponseTypeDef",
-    {
-        "LocalDomainInfo": DomainInformationContainerTypeDef,
-        "RemoteDomainInfo": DomainInformationContainerTypeDef,
-        "ConnectionAlias": str,
-        "ConnectionStatus": OutboundConnectionStatusTypeDef,
-        "ConnectionId": str,
-        "ConnectionMode": ConnectionModeType,
-        "ConnectionProperties": ConnectionPropertiesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 InboundConnectionTypeDef = TypedDict(
     "InboundConnectionTypeDef",
     {
         "LocalDomainInfo": DomainInformationContainerTypeDef,
         "RemoteDomainInfo": DomainInformationContainerTypeDef,
         "ConnectionId": str,
         "ConnectionStatus": InboundConnectionStatusTypeDef,
         "ConnectionMode": ConnectionModeType,
     },
     total=False,
 )
 
-OutboundConnectionTypeDef = TypedDict(
-    "OutboundConnectionTypeDef",
-    {
-        "LocalDomainInfo": DomainInformationContainerTypeDef,
-        "RemoteDomainInfo": DomainInformationContainerTypeDef,
-        "ConnectionId": str,
-        "ConnectionAlias": str,
-        "ConnectionStatus": OutboundConnectionStatusTypeDef,
-        "ConnectionMode": ConnectionModeType,
-        "ConnectionProperties": ConnectionPropertiesTypeDef,
-    },
-    total=False,
-)
-
 AutoTuneTypeDef = TypedDict(
     "AutoTuneTypeDef",
     {
         "AutoTuneType": Literal["SCHEDULED_ACTION"],
         "AutoTuneDetails": AutoTuneDetailsTypeDef,
     },
     total=False,
 )
 
 AutoTuneOptionsInputTypeDef = TypedDict(
     "AutoTuneOptionsInputTypeDef",
     {
         "DesiredState": AutoTuneDesiredStateType,
         "MaintenanceSchedules": Sequence[AutoTuneMaintenanceScheduleTypeDef],
+        "UseOffPeakWindow": bool,
     },
     total=False,
 )
 
 AutoTuneOptionsTypeDef = TypedDict(
     "AutoTuneOptionsTypeDef",
     {
         "DesiredState": AutoTuneDesiredStateType,
         "RollbackOnDisable": RollbackOnDisableType,
         "MaintenanceSchedules": List[AutoTuneMaintenanceScheduleTypeDef],
+        "UseOffPeakWindow": bool,
     },
     total=False,
 )
 
+DescribeDomainHealthResponseTypeDef = TypedDict(
+    "DescribeDomainHealthResponseTypeDef",
+    {
+        "DomainState": DomainStateType,
+        "AvailabilityZoneCount": str,
+        "ActiveAvailabilityZoneCount": str,
+        "StandByAvailabilityZoneCount": str,
+        "DataNodeCount": str,
+        "DedicatedMaster": bool,
+        "MasterEligibleNodeCount": str,
+        "WarmNodeCount": str,
+        "MasterNode": MasterNodeStatusType,
+        "ClusterHealth": DomainHealthType,
+        "TotalShards": str,
+        "TotalUnAssignedShards": str,
+        "EnvironmentInformation": List[EnvironmentInfoTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeDomainChangeProgressResponseTypeDef = TypedDict(
     "DescribeDomainChangeProgressResponseTypeDef",
     {
         "ChangeProgressStatus": ChangeProgressStatusDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ClusterConfigStatusTypeDef = TypedDict(
     "ClusterConfigStatusTypeDef",
     {
         "Options": ClusterConfigTypeDef,
         "Status": OptionStatusTypeDef,
     },
 )
 
+_RequiredCreateOutboundConnectionRequestRequestTypeDef = TypedDict(
+    "_RequiredCreateOutboundConnectionRequestRequestTypeDef",
+    {
+        "LocalDomainInfo": DomainInformationContainerTypeDef,
+        "RemoteDomainInfo": DomainInformationContainerTypeDef,
+        "ConnectionAlias": str,
+    },
+)
+_OptionalCreateOutboundConnectionRequestRequestTypeDef = TypedDict(
+    "_OptionalCreateOutboundConnectionRequestRequestTypeDef",
+    {
+        "ConnectionMode": ConnectionModeType,
+        "ConnectionProperties": ConnectionPropertiesTypeDef,
+    },
+    total=False,
+)
+
+
+class CreateOutboundConnectionRequestRequestTypeDef(
+    _RequiredCreateOutboundConnectionRequestRequestTypeDef,
+    _OptionalCreateOutboundConnectionRequestRequestTypeDef,
+):
+    pass
+
+
+CreateOutboundConnectionResponseTypeDef = TypedDict(
+    "CreateOutboundConnectionResponseTypeDef",
+    {
+        "LocalDomainInfo": DomainInformationContainerTypeDef,
+        "RemoteDomainInfo": DomainInformationContainerTypeDef,
+        "ConnectionAlias": str,
+        "ConnectionStatus": OutboundConnectionStatusTypeDef,
+        "ConnectionId": str,
+        "ConnectionMode": ConnectionModeType,
+        "ConnectionProperties": ConnectionPropertiesTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+OutboundConnectionTypeDef = TypedDict(
+    "OutboundConnectionTypeDef",
+    {
+        "LocalDomainInfo": DomainInformationContainerTypeDef,
+        "RemoteDomainInfo": DomainInformationContainerTypeDef,
+        "ConnectionId": str,
+        "ConnectionAlias": str,
+        "ConnectionStatus": OutboundConnectionStatusTypeDef,
+        "ConnectionMode": ConnectionModeType,
+        "ConnectionProperties": ConnectionPropertiesTypeDef,
+    },
+    total=False,
+)
+
 AssociatePackageResponseTypeDef = TypedDict(
     "AssociatePackageResponseTypeDef",
     {
         "DomainPackageDetails": DomainPackageDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DissociatePackageResponseTypeDef = TypedDict(
     "DissociatePackageResponseTypeDef",
     {
         "DomainPackageDetails": DomainPackageDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDomainsForPackageResponseTypeDef = TypedDict(
     "ListDomainsForPackageResponseTypeDef",
     {
         "DomainPackageDetailsList": List[DomainPackageDetailsTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPackagesForDomainResponseTypeDef = TypedDict(
     "ListPackagesForDomainResponseTypeDef",
     {
         "DomainPackageDetailsList": List[DomainPackageDetailsTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreatePackageResponseTypeDef = TypedDict(
     "CreatePackageResponseTypeDef",
     {
         "PackageDetails": PackageDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeletePackageResponseTypeDef = TypedDict(
     "DeletePackageResponseTypeDef",
     {
         "PackageDetails": PackageDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribePackagesResponseTypeDef = TypedDict(
     "DescribePackagesResponseTypeDef",
     {
         "PackageDetailsList": List[PackageDetailsTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdatePackageResponseTypeDef = TypedDict(
     "UpdatePackageResponseTypeDef",
     {
         "PackageDetails": PackageDetailsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateVpcEndpointResponseTypeDef = TypedDict(
     "CreateVpcEndpointResponseTypeDef",
     {
         "VpcEndpoint": VpcEndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeVpcEndpointsResponseTypeDef = TypedDict(
     "DescribeVpcEndpointsResponseTypeDef",
     {
         "VpcEndpoints": List[VpcEndpointTypeDef],
         "VpcEndpointErrors": List[VpcEndpointErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateVpcEndpointResponseTypeDef = TypedDict(
     "UpdateVpcEndpointResponseTypeDef",
     {
         "VpcEndpoint": VpcEndpointTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+OffPeakWindowOptionsTypeDef = TypedDict(
+    "OffPeakWindowOptionsTypeDef",
+    {
+        "Enabled": bool,
+        "OffPeakWindow": OffPeakWindowTypeDef,
     },
+    total=False,
 )
 
 DescribeReservedInstanceOfferingsResponseTypeDef = TypedDict(
     "DescribeReservedInstanceOfferingsResponseTypeDef",
     {
         "NextToken": str,
         "ReservedInstanceOfferings": List[ReservedInstanceOfferingTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeReservedInstancesResponseTypeDef = TypedDict(
     "DescribeReservedInstancesResponseTypeDef",
     {
         "NextToken": str,
         "ReservedInstances": List[ReservedInstanceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AdvancedSecurityOptionsInputTypeDef = TypedDict(
     "AdvancedSecurityOptionsInputTypeDef",
     {
         "Enabled": bool,
@@ -1987,82 +2305,91 @@
 )
 
 GetUpgradeHistoryResponseTypeDef = TypedDict(
     "GetUpgradeHistoryResponseTypeDef",
     {
         "UpgradeHistories": List[UpgradeHistoryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AcceptInboundConnectionResponseTypeDef = TypedDict(
     "AcceptInboundConnectionResponseTypeDef",
     {
         "Connection": InboundConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteInboundConnectionResponseTypeDef = TypedDict(
     "DeleteInboundConnectionResponseTypeDef",
     {
         "Connection": InboundConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeInboundConnectionsResponseTypeDef = TypedDict(
     "DescribeInboundConnectionsResponseTypeDef",
     {
         "Connections": List[InboundConnectionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RejectInboundConnectionResponseTypeDef = TypedDict(
     "RejectInboundConnectionResponseTypeDef",
     {
         "Connection": InboundConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeDomainAutoTunesResponseTypeDef = TypedDict(
+    "DescribeDomainAutoTunesResponseTypeDef",
+    {
+        "AutoTunes": List[AutoTuneTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+AutoTuneOptionsStatusTypeDef = TypedDict(
+    "AutoTuneOptionsStatusTypeDef",
+    {
+        "Options": AutoTuneOptionsTypeDef,
+        "Status": AutoTuneStatusTypeDef,
     },
+    total=False,
 )
 
 DeleteOutboundConnectionResponseTypeDef = TypedDict(
     "DeleteOutboundConnectionResponseTypeDef",
     {
         "Connection": OutboundConnectionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeOutboundConnectionsResponseTypeDef = TypedDict(
     "DescribeOutboundConnectionsResponseTypeDef",
     {
         "Connections": List[OutboundConnectionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeDomainAutoTunesResponseTypeDef = TypedDict(
-    "DescribeDomainAutoTunesResponseTypeDef",
-    {
-        "AutoTunes": List[AutoTuneTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-AutoTuneOptionsStatusTypeDef = TypedDict(
-    "AutoTuneOptionsStatusTypeDef",
+OffPeakWindowOptionsStatusTypeDef = TypedDict(
+    "OffPeakWindowOptionsStatusTypeDef",
     {
-        "Options": AutoTuneOptionsTypeDef,
-        "Status": AutoTuneStatusTypeDef,
+        "Options": OffPeakWindowOptionsTypeDef,
+        "Status": OptionStatusTypeDef,
     },
     total=False,
 )
 
 _RequiredCreateDomainRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDomainRequestRequestTypeDef",
     {
@@ -2083,23 +2410,27 @@
         "NodeToNodeEncryptionOptions": NodeToNodeEncryptionOptionsTypeDef,
         "AdvancedOptions": Mapping[str, str],
         "LogPublishingOptions": Mapping[LogTypeType, LogPublishingOptionTypeDef],
         "DomainEndpointOptions": DomainEndpointOptionsTypeDef,
         "AdvancedSecurityOptions": AdvancedSecurityOptionsInputTypeDef,
         "TagList": Sequence[TagTypeDef],
         "AutoTuneOptions": AutoTuneOptionsInputTypeDef,
+        "OffPeakWindowOptions": OffPeakWindowOptionsTypeDef,
+        "SoftwareUpdateOptions": SoftwareUpdateOptionsTypeDef,
     },
     total=False,
 )
 
+
 class CreateDomainRequestRequestTypeDef(
     _RequiredCreateDomainRequestRequestTypeDef, _OptionalCreateDomainRequestRequestTypeDef
 ):
     pass
 
+
 _RequiredUpdateDomainConfigRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateDomainConfigRequestRequestTypeDef",
     {
         "DomainName": str,
     },
 )
 _OptionalUpdateDomainConfigRequestRequestTypeDef = TypedDict(
@@ -2116,24 +2447,28 @@
         "EncryptionAtRestOptions": EncryptionAtRestOptionsTypeDef,
         "DomainEndpointOptions": DomainEndpointOptionsTypeDef,
         "NodeToNodeEncryptionOptions": NodeToNodeEncryptionOptionsTypeDef,
         "AdvancedSecurityOptions": AdvancedSecurityOptionsInputTypeDef,
         "AutoTuneOptions": AutoTuneOptionsTypeDef,
         "DryRun": bool,
         "DryRunMode": DryRunModeType,
+        "OffPeakWindowOptions": OffPeakWindowOptionsTypeDef,
+        "SoftwareUpdateOptions": SoftwareUpdateOptionsTypeDef,
     },
     total=False,
 )
 
+
 class UpdateDomainConfigRequestRequestTypeDef(
     _RequiredUpdateDomainConfigRequestRequestTypeDef,
     _OptionalUpdateDomainConfigRequestRequestTypeDef,
 ):
     pass
 
+
 AdvancedSecurityOptionsStatusTypeDef = TypedDict(
     "AdvancedSecurityOptionsStatusTypeDef",
     {
         "Options": AdvancedSecurityOptionsTypeDef,
         "Status": OptionStatusTypeDef,
     },
 )
@@ -2167,26 +2502,30 @@
         "AdvancedOptions": Dict[str, str],
         "LogPublishingOptions": Dict[LogTypeType, LogPublishingOptionTypeDef],
         "ServiceSoftwareOptions": ServiceSoftwareOptionsTypeDef,
         "DomainEndpointOptions": DomainEndpointOptionsTypeDef,
         "AdvancedSecurityOptions": AdvancedSecurityOptionsTypeDef,
         "AutoTuneOptions": AutoTuneOptionsOutputTypeDef,
         "ChangeProgressDetails": ChangeProgressDetailsTypeDef,
+        "OffPeakWindowOptions": OffPeakWindowOptionsTypeDef,
+        "SoftwareUpdateOptions": SoftwareUpdateOptionsTypeDef,
     },
     total=False,
 )
 
+
 class DomainStatusTypeDef(_RequiredDomainStatusTypeDef, _OptionalDomainStatusTypeDef):
     pass
 
+
 DescribeInstanceTypeLimitsResponseTypeDef = TypedDict(
     "DescribeInstanceTypeLimitsResponseTypeDef",
     {
         "LimitsByRole": Dict[str, LimitsTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DomainConfigTypeDef = TypedDict(
     "DomainConfigTypeDef",
     {
         "EngineVersion": VersionStatusTypeDef,
@@ -2200,70 +2539,72 @@
         "NodeToNodeEncryptionOptions": NodeToNodeEncryptionOptionsStatusTypeDef,
         "AdvancedOptions": AdvancedOptionsStatusTypeDef,
         "LogPublishingOptions": LogPublishingOptionsStatusTypeDef,
         "DomainEndpointOptions": DomainEndpointOptionsStatusTypeDef,
         "AdvancedSecurityOptions": AdvancedSecurityOptionsStatusTypeDef,
         "AutoTuneOptions": AutoTuneOptionsStatusTypeDef,
         "ChangeProgressDetails": ChangeProgressDetailsTypeDef,
+        "OffPeakWindowOptions": OffPeakWindowOptionsStatusTypeDef,
+        "SoftwareUpdateOptions": SoftwareUpdateOptionsStatusTypeDef,
     },
     total=False,
 )
 
 CreateDomainResponseTypeDef = TypedDict(
     "CreateDomainResponseTypeDef",
     {
         "DomainStatus": DomainStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteDomainResponseTypeDef = TypedDict(
     "DeleteDomainResponseTypeDef",
     {
         "DomainStatus": DomainStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDomainResponseTypeDef = TypedDict(
     "DescribeDomainResponseTypeDef",
     {
         "DomainStatus": DomainStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDomainsResponseTypeDef = TypedDict(
     "DescribeDomainsResponseTypeDef",
     {
         "DomainStatusList": List[DomainStatusTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDryRunProgressResponseTypeDef = TypedDict(
     "DescribeDryRunProgressResponseTypeDef",
     {
         "DryRunProgressStatus": DryRunProgressStatusTypeDef,
         "DryRunConfig": DomainStatusTypeDef,
         "DryRunResults": DryRunResultsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDomainConfigResponseTypeDef = TypedDict(
     "DescribeDomainConfigResponseTypeDef",
     {
         "DomainConfig": DomainConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDomainConfigResponseTypeDef = TypedDict(
     "UpdateDomainConfigResponseTypeDef",
     {
         "DomainConfig": DomainConfigTypeDef,
         "DryRunResults": DryRunResultsTypeDef,
         "DryRunProgressStatus": DryRunProgressStatusTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-opensearch-2.5.0.post1/types_aiobotocore_opensearch.egg-info/PKG-INFO` & `types-aiobotocore-opensearch-2.5.1/types_aiobotocore_opensearch.egg-info/PKG-INFO`

 * *Files 6% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-opensearch
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.OpenSearchService 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.OpenSearchService 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-opensearch"></a>
 
 # types-aiobotocore-opensearch
 
 [![PyPI - types-aiobotocore-opensearch](https://img.shields.io/pypi/v/types-aiobotocore-opensearch.svg?color=blue)](https://pypi.org/project/types-aiobotocore-opensearch)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-opensearch.svg?color=blue)](https://pypi.org/project/types-aiobotocore-opensearch)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-opensearch?color=blue)](https://pypistats.org/packages/types-aiobotocore-opensearch)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.OpenSearchService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearch.html#OpenSearchService)
+[aiobotocore.OpenSearchService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opensearch.html#OpenSearchService)
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
 [types-aiobotocore-opensearch docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opensearch/).
 
 See how it helps to find and fix potential bugs:
 
@@ -269,105 +269,121 @@
 ### Literals
 
 `types_aiobotocore_opensearch.literals` module contains literals extracted from
 shapes that can be used in user code for type checking.
 
 ```python
 from types_aiobotocore_opensearch.literals import (
+    ActionSeverityType,
+    ActionStatusType,
+    ActionTypeType,
     AutoTuneDesiredStateType,
     AutoTuneStateType,
     AutoTuneTypeType,
     ConnectionModeType,
     DeploymentStatusType,
     DescribePackagesFilterNameType,
+    DomainHealthType,
     DomainPackageStatusType,
+    DomainStateType,
     DryRunModeType,
     EngineTypeType,
     InboundConnectionStatusCodeType,
     LogTypeType,
+    MasterNodeStatusType,
+    NodeStatusType,
+    NodeTypeType,
     OpenSearchPartitionInstanceTypeType,
     OpenSearchWarmPartitionInstanceTypeType,
     OptionStateType,
     OutboundConnectionStatusCodeType,
     OverallChangeStatusType,
     PackageStatusType,
     PackageTypeType,
     PrincipalTypeType,
     ReservedInstancePaymentOptionType,
     RollbackOnDisableType,
+    ScheduleAtType,
     ScheduledAutoTuneActionTypeType,
     ScheduledAutoTuneSeverityTypeType,
+    ScheduledByType,
+    SkipUnavailableStatusType,
     TLSSecurityPolicyType,
     TimeUnitType,
     UpgradeStatusType,
     UpgradeStepType,
     VolumeTypeType,
     VpcEndpointErrorCodeType,
     VpcEndpointStatusType,
+    ZoneStatusType,
     OpenSearchServiceServiceName,
     ServiceName,
     ResourceServiceName,
     RegionName,
 )
 
 
-def check_value(value: AutoTuneDesiredStateType) -> bool:
+def check_value(value: ActionSeverityType) -> bool:
     ...
 ```
 
 <a id="typed-dictionaries"></a>
 
 ### Typed dictionaries
 
 `types_aiobotocore_opensearch.type_defs` module contains structures and shapes
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_opensearch.type_defs import (
     AWSDomainInformationTypeDef,
     AcceptInboundConnectionRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     OptionStatusTypeDef,
     TagTypeDef,
     AdditionalLimitTypeDef,
     MasterUserOptionsTypeDef,
     AssociatePackageRequestRequestTypeDef,
     AuthorizeVpcEndpointAccessRequestRequestTypeDef,
     AuthorizedPrincipalTypeDef,
     ScheduledAutoTuneDetailsTypeDef,
     DurationTypeDef,
     AutoTuneOptionsOutputTypeDef,
     AutoTuneStatusTypeDef,
+    AvailabilityZoneInfoTypeDef,
     CancelServiceSoftwareUpdateRequestRequestTypeDef,
     ServiceSoftwareOptionsTypeDef,
     ChangeProgressDetailsTypeDef,
     ChangeProgressStageTypeDef,
     ColdStorageOptionsTypeDef,
     ZoneAwarenessConfigTypeDef,
     CognitoOptionsTypeDef,
     CompatibleVersionsMapTypeDef,
-    ConnectionPropertiesTypeDef,
+    CrossClusterSearchConnectionPropertiesTypeDef,
     DomainEndpointOptionsTypeDef,
     EBSOptionsTypeDef,
     EncryptionAtRestOptionsTypeDef,
     LogPublishingOptionTypeDef,
     NodeToNodeEncryptionOptionsTypeDef,
     SnapshotOptionsTypeDef,
+    SoftwareUpdateOptionsTypeDef,
     VPCOptionsTypeDef,
     OutboundConnectionStatusTypeDef,
     PackageSourceTypeDef,
     DeleteDomainRequestRequestTypeDef,
     DeleteInboundConnectionRequestRequestTypeDef,
     DeleteOutboundConnectionRequestRequestTypeDef,
     DeletePackageRequestRequestTypeDef,
     DeleteVpcEndpointRequestRequestTypeDef,
     VpcEndpointSummaryTypeDef,
     DescribeDomainAutoTunesRequestRequestTypeDef,
     DescribeDomainChangeProgressRequestRequestTypeDef,
     DescribeDomainConfigRequestRequestTypeDef,
+    DescribeDomainHealthRequestRequestTypeDef,
+    DescribeDomainNodesRequestRequestTypeDef,
+    DomainNodesStatusTypeDef,
     DescribeDomainRequestRequestTypeDef,
     DescribeDomainsRequestRequestTypeDef,
     DescribeDryRunProgressRequestRequestTypeDef,
     DryRunResultsTypeDef,
     FilterTypeDef,
     DescribeInstanceTypeLimitsRequestRequestTypeDef,
     DescribePackagesFilterTypeDef,
@@ -376,127 +392,142 @@
     DescribeVpcEndpointsRequestRequestTypeDef,
     VpcEndpointErrorTypeDef,
     DissociatePackageRequestRequestTypeDef,
     DomainInfoTypeDef,
     ErrorDetailsTypeDef,
     VPCDerivedInfoTypeDef,
     ValidationFailureTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetCompatibleVersionsRequestRequestTypeDef,
     GetPackageVersionHistoryRequestRequestTypeDef,
     PackageVersionHistoryTypeDef,
     GetUpgradeHistoryRequestRequestTypeDef,
     GetUpgradeStatusRequestRequestTypeDef,
+    GetUpgradeStatusResponseTypeDef,
     InboundConnectionStatusTypeDef,
     InstanceCountLimitsTypeDef,
     InstanceTypeDetailsTypeDef,
     ListDomainNamesRequestRequestTypeDef,
     ListDomainsForPackageRequestRequestTypeDef,
     ListInstanceTypeDetailsRequestRequestTypeDef,
     ListPackagesForDomainRequestRequestTypeDef,
+    ListScheduledActionsRequestRequestTypeDef,
+    ScheduledActionTypeDef,
     ListTagsRequestRequestTypeDef,
     ListVersionsRequestRequestTypeDef,
+    ListVersionsResponseTypeDef,
     ListVpcEndpointAccessRequestRequestTypeDef,
     ListVpcEndpointsForDomainRequestRequestTypeDef,
     ListVpcEndpointsRequestRequestTypeDef,
+    WindowStartTimeTypeDef,
     PurchaseReservedInstanceOfferingRequestRequestTypeDef,
+    PurchaseReservedInstanceOfferingResponseTypeDef,
     RecurringChargeTypeDef,
     RejectInboundConnectionRequestRequestTypeDef,
     RemoveTagsRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     RevokeVpcEndpointAccessRequestRequestTypeDef,
     SAMLIdpTypeDef,
     StartServiceSoftwareUpdateRequestRequestTypeDef,
     StorageTypeLimitTypeDef,
+    UpdateScheduledActionRequestRequestTypeDef,
     UpgradeDomainRequestRequestTypeDef,
     UpgradeStepItemTypeDef,
     DomainInformationContainerTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetUpgradeStatusResponseTypeDef,
-    ListVersionsResponseTypeDef,
-    PurchaseReservedInstanceOfferingResponseTypeDef,
     AccessPoliciesStatusTypeDef,
     AdvancedOptionsStatusTypeDef,
     VersionStatusTypeDef,
     AddTagsRequestRequestTypeDef,
     ListTagsResponseTypeDef,
     AuthorizeVpcEndpointAccessResponseTypeDef,
     ListVpcEndpointAccessResponseTypeDef,
     AutoTuneDetailsTypeDef,
     AutoTuneMaintenanceScheduleTypeDef,
+    EnvironmentInfoTypeDef,
     CancelServiceSoftwareUpdateResponseTypeDef,
     StartServiceSoftwareUpdateResponseTypeDef,
     UpgradeDomainResponseTypeDef,
     ChangeProgressStatusDetailsTypeDef,
     ClusterConfigTypeDef,
     CognitoOptionsStatusTypeDef,
     GetCompatibleVersionsResponseTypeDef,
+    ConnectionPropertiesTypeDef,
     DomainEndpointOptionsStatusTypeDef,
     EBSOptionsStatusTypeDef,
     EncryptionAtRestOptionsStatusTypeDef,
     LogPublishingOptionsStatusTypeDef,
     NodeToNodeEncryptionOptionsStatusTypeDef,
     SnapshotOptionsStatusTypeDef,
+    SoftwareUpdateOptionsStatusTypeDef,
     CreateVpcEndpointRequestRequestTypeDef,
     UpdateVpcEndpointRequestRequestTypeDef,
     CreatePackageRequestRequestTypeDef,
     UpdatePackageRequestRequestTypeDef,
     DeleteVpcEndpointResponseTypeDef,
     ListVpcEndpointsForDomainResponseTypeDef,
     ListVpcEndpointsResponseTypeDef,
+    DescribeDomainNodesResponseTypeDef,
     DescribeInboundConnectionsRequestRequestTypeDef,
     DescribeOutboundConnectionsRequestRequestTypeDef,
     DescribePackagesRequestRequestTypeDef,
     ListDomainNamesResponseTypeDef,
     DomainPackageDetailsTypeDef,
     PackageDetailsTypeDef,
     VPCDerivedInfoStatusTypeDef,
     VpcEndpointTypeDef,
     DryRunProgressStatusTypeDef,
     GetPackageVersionHistoryResponseTypeDef,
     InstanceLimitsTypeDef,
     ListInstanceTypeDetailsResponseTypeDef,
+    ListScheduledActionsResponseTypeDef,
+    UpdateScheduledActionResponseTypeDef,
+    OffPeakWindowTypeDef,
     ReservedInstanceOfferingTypeDef,
     ReservedInstanceTypeDef,
     SAMLOptionsInputTypeDef,
     SAMLOptionsOutputTypeDef,
     StorageTypeTypeDef,
     UpgradeHistoryTypeDef,
-    CreateOutboundConnectionRequestRequestTypeDef,
-    CreateOutboundConnectionResponseTypeDef,
     InboundConnectionTypeDef,
-    OutboundConnectionTypeDef,
     AutoTuneTypeDef,
     AutoTuneOptionsInputTypeDef,
     AutoTuneOptionsTypeDef,
+    DescribeDomainHealthResponseTypeDef,
     DescribeDomainChangeProgressResponseTypeDef,
     ClusterConfigStatusTypeDef,
+    CreateOutboundConnectionRequestRequestTypeDef,
+    CreateOutboundConnectionResponseTypeDef,
+    OutboundConnectionTypeDef,
     AssociatePackageResponseTypeDef,
     DissociatePackageResponseTypeDef,
     ListDomainsForPackageResponseTypeDef,
     ListPackagesForDomainResponseTypeDef,
     CreatePackageResponseTypeDef,
     DeletePackageResponseTypeDef,
     DescribePackagesResponseTypeDef,
     UpdatePackageResponseTypeDef,
     CreateVpcEndpointResponseTypeDef,
     DescribeVpcEndpointsResponseTypeDef,
     UpdateVpcEndpointResponseTypeDef,
+    OffPeakWindowOptionsTypeDef,
     DescribeReservedInstanceOfferingsResponseTypeDef,
     DescribeReservedInstancesResponseTypeDef,
     AdvancedSecurityOptionsInputTypeDef,
     AdvancedSecurityOptionsTypeDef,
     LimitsTypeDef,
     GetUpgradeHistoryResponseTypeDef,
     AcceptInboundConnectionResponseTypeDef,
     DeleteInboundConnectionResponseTypeDef,
     DescribeInboundConnectionsResponseTypeDef,
     RejectInboundConnectionResponseTypeDef,
-    DeleteOutboundConnectionResponseTypeDef,
-    DescribeOutboundConnectionsResponseTypeDef,
     DescribeDomainAutoTunesResponseTypeDef,
     AutoTuneOptionsStatusTypeDef,
+    DeleteOutboundConnectionResponseTypeDef,
+    DescribeOutboundConnectionsResponseTypeDef,
+    OffPeakWindowOptionsStatusTypeDef,
     CreateDomainRequestRequestTypeDef,
     UpdateDomainConfigRequestRequestTypeDef,
     AdvancedSecurityOptionsStatusTypeDef,
     DomainStatusTypeDef,
     DescribeInstanceTypeLimitsResponseTypeDef,
     DomainConfigTypeDef,
     CreateDomainResponseTypeDef,
@@ -516,43 +547,43 @@
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

### Comparing `types-aiobotocore-opensearch-2.5.0.post1/types_aiobotocore_opensearch.egg-info/SOURCES.txt` & `types-aiobotocore-opensearch-2.5.1/types_aiobotocore_opensearch.egg-info/SOURCES.txt`

 * *Files identical despite different names*

