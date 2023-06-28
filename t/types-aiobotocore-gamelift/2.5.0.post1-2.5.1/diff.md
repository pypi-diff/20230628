# Comparing `tmp/types-aiobotocore-gamelift-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-gamelift-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-gamelift-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:39 2023, max compression
+gzip compressed data, was "types-aiobotocore-gamelift-2.5.1.tar", last modified: Wed Jun 28 01:43:31 2023, max compression
```

## Comparing `types-aiobotocore-gamelift-2.5.0.post1.tar` & `types-aiobotocore-gamelift-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:39.743227 types-aiobotocore-gamelift-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:14:55.000000 types-aiobotocore-gamelift-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    29379 2023-03-11 12:26:39.743227 types-aiobotocore-gamelift-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    27804 2023-03-11 12:14:55.000000 types-aiobotocore-gamelift-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:39.743227 types-aiobotocore-gamelift-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2131 2023-03-11 12:14:55.000000 types-aiobotocore-gamelift-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:39.743227 types-aiobotocore-gamelift-2.5.0.post1/types_aiobotocore_gamelift/
--rw-r--r--   0 runner    (1001) docker     (123)     5417 2023-03-11 12:14:55.000000 types-aiobotocore-gamelift-2.5.0.post1/types_aiobotocore_gamelift/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     5416 2023-03-11 12:14:55.000000 types-aiobotocore-gamelift-2.5.0.post1/types_aiobotocore_gamelift/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      947 2023-03-11 12:14:55.000000 types-aiobotocore-gamelift-2.5.0.post1/types_aiobotocore_gamelift/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    88468 2023-03-11 12:14:55.000000 types-aiobotocore-gamelift-2.5.0.post1/types_aiobotocore_gamelift/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    88333 2023-03-11 12:14:55.000000 types-aiobotocore-gamelift-2.5.0.post1/types_aiobotocore_gamelift/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    20314 2023-03-11 12:14:56.000000 types-aiobotocore-gamelift-2.5.0.post1/types_aiobotocore_gamelift/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    20312 2023-03-11 12:14:56.000000 types-aiobotocore-gamelift-2.5.0.post1/types_aiobotocore_gamelift/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    27776 2023-03-11 12:14:56.000000 types-aiobotocore-gamelift-2.5.0.post1/types_aiobotocore_gamelift/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    27751 2023-03-11 12:14:55.000000 types-aiobotocore-gamelift-2.5.0.post1/types_aiobotocore_gamelift/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:14:55.000000 types-aiobotocore-gamelift-2.5.0.post1/types_aiobotocore_gamelift/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    97737 2023-03-11 12:14:59.000000 types-aiobotocore-gamelift-2.5.0.post1/types_aiobotocore_gamelift/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    97638 2023-03-11 12:14:58.000000 types-aiobotocore-gamelift-2.5.0.post1/types_aiobotocore_gamelift/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:14:55.000000 types-aiobotocore-gamelift-2.5.0.post1/types_aiobotocore_gamelift/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:39.743227 types-aiobotocore-gamelift-2.5.0.post1/types_aiobotocore_gamelift.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    29379 2023-03-11 12:26:39.000000 types-aiobotocore-gamelift-2.5.0.post1/types_aiobotocore_gamelift.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      832 2023-03-11 12:26:39.000000 types-aiobotocore-gamelift-2.5.0.post1/types_aiobotocore_gamelift.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:39.000000 types-aiobotocore-gamelift-2.5.0.post1/types_aiobotocore_gamelift.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:39.000000 types-aiobotocore-gamelift-2.5.0.post1/types_aiobotocore_gamelift.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:39.000000 types-aiobotocore-gamelift-2.5.0.post1/types_aiobotocore_gamelift.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       27 2023-03-11 12:26:39.000000 types-aiobotocore-gamelift-2.5.0.post1/types_aiobotocore_gamelift.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:31.774141 types-aiobotocore-gamelift-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:31:31.000000 types-aiobotocore-gamelift-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    29432 2023-06-28 01:43:31.770141 types-aiobotocore-gamelift-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    27863 2023-06-28 01:31:31.000000 types-aiobotocore-gamelift-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:31.774141 types-aiobotocore-gamelift-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2125 2023-06-28 01:31:31.000000 types-aiobotocore-gamelift-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:31.770141 types-aiobotocore-gamelift-2.5.1/types_aiobotocore_gamelift/
+-rw-r--r--   0 runner    (1001) docker     (123)     5417 2023-06-28 01:31:31.000000 types-aiobotocore-gamelift-2.5.1/types_aiobotocore_gamelift/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5416 2023-06-28 01:31:31.000000 types-aiobotocore-gamelift-2.5.1/types_aiobotocore_gamelift/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      935 2023-06-28 01:31:31.000000 types-aiobotocore-gamelift-2.5.1/types_aiobotocore_gamelift/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    88770 2023-06-28 01:31:32.000000 types-aiobotocore-gamelift-2.5.1/types_aiobotocore_gamelift/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    88635 2023-06-28 01:31:32.000000 types-aiobotocore-gamelift-2.5.1/types_aiobotocore_gamelift/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    20628 2023-06-28 01:31:33.000000 types-aiobotocore-gamelift-2.5.1/types_aiobotocore_gamelift/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20626 2023-06-28 01:31:32.000000 types-aiobotocore-gamelift-2.5.1/types_aiobotocore_gamelift/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    27700 2023-06-28 01:31:32.000000 types-aiobotocore-gamelift-2.5.1/types_aiobotocore_gamelift/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27676 2023-06-28 01:31:32.000000 types-aiobotocore-gamelift-2.5.1/types_aiobotocore_gamelift/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:31:31.000000 types-aiobotocore-gamelift-2.5.1/types_aiobotocore_gamelift/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    98234 2023-06-28 01:31:35.000000 types-aiobotocore-gamelift-2.5.1/types_aiobotocore_gamelift/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    98135 2023-06-28 01:31:34.000000 types-aiobotocore-gamelift-2.5.1/types_aiobotocore_gamelift/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:31:31.000000 types-aiobotocore-gamelift-2.5.1/types_aiobotocore_gamelift/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:31.770141 types-aiobotocore-gamelift-2.5.1/types_aiobotocore_gamelift.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    29432 2023-06-28 01:43:31.000000 types-aiobotocore-gamelift-2.5.1/types_aiobotocore_gamelift.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      832 2023-06-28 01:43:31.000000 types-aiobotocore-gamelift-2.5.1/types_aiobotocore_gamelift.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:31.000000 types-aiobotocore-gamelift-2.5.1/types_aiobotocore_gamelift.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:31.000000 types-aiobotocore-gamelift-2.5.1/types_aiobotocore_gamelift.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:31.000000 types-aiobotocore-gamelift-2.5.1/types_aiobotocore_gamelift.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       27 2023-06-28 01:43:31.000000 types-aiobotocore-gamelift-2.5.1/types_aiobotocore_gamelift.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-gamelift-2.5.0.post1/LICENSE` & `types-aiobotocore-gamelift-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-gamelift-2.5.0.post1/PKG-INFO` & `types-aiobotocore-gamelift-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-gamelift
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.GameLift 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.GameLift 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-gamelift"></a>
 
 # types-aiobotocore-gamelift
 
 [![PyPI - types-aiobotocore-gamelift](https://img.shields.io/pypi/v/types-aiobotocore-gamelift.svg?color=blue)](https://pypi.org/project/types-aiobotocore-gamelift)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-gamelift.svg?color=blue)](https://pypi.org/project/types-aiobotocore-gamelift)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-gamelift?color=blue)](https://pypistats.org/packages/types-aiobotocore-gamelift)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.GameLift 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift)
+[aiobotocore.GameLift 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift)
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
 [types-aiobotocore-gamelift docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/).
 
 See how it helps to find and fix potential bugs:
 
@@ -390,14 +390,15 @@
     DescribeInstancesPaginatorName,
     DescribeMatchmakingConfigurationsPaginatorName,
     DescribeMatchmakingRuleSetsPaginatorName,
     DescribePlayerSessionsPaginatorName,
     DescribeScalingPoliciesPaginatorName,
     EC2InstanceTypeType,
     EventCodeType,
+    FilterInstanceStatusType,
     FleetActionType,
     FleetStatusType,
     FleetTypeType,
     FlexMatchModeType,
     GameServerClaimStatusType,
     GameServerGroupActionType,
     GameServerGroupDeleteOptionType,
@@ -459,17 +460,16 @@
     AcceptMatchInputRequestTypeDef,
     RoutingStrategyTypeDef,
     AnywhereConfigurationTypeDef,
     AttributeValueTypeDef,
     AwsCredentialsTypeDef,
     BuildTypeDef,
     CertificateConfigurationTypeDef,
-    ClaimGameServerInputRequestTypeDef,
+    ClaimFilterOptionTypeDef,
     GameServerTypeDef,
-    ResponseMetadataTypeDef,
     ComputeTypeDef,
     TagTypeDef,
     S3LocationTypeDef,
     IpPermissionTypeDef,
     LocationConfigurationTypeDef,
     ResourceCreationLimitPolicyTypeDef,
     LocationStateTypeDef,
@@ -504,107 +504,131 @@
     DeregisterComputeInputRequestTypeDef,
     DeregisterGameServerInputRequestTypeDef,
     DescribeAliasInputRequestTypeDef,
     DescribeBuildInputRequestTypeDef,
     DescribeComputeInputRequestTypeDef,
     DescribeEC2InstanceLimitsInputRequestTypeDef,
     EC2InstanceLimitTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeFleetAttributesInputDescribeFleetAttributesPaginateTypeDef,
     DescribeFleetAttributesInputRequestTypeDef,
+    DescribeFleetCapacityInputDescribeFleetCapacityPaginateTypeDef,
     DescribeFleetCapacityInputRequestTypeDef,
+    DescribeFleetEventsInputDescribeFleetEventsPaginateTypeDef,
     DescribeFleetEventsInputRequestTypeDef,
     EventTypeDef,
     DescribeFleetLocationAttributesInputRequestTypeDef,
     DescribeFleetLocationCapacityInputRequestTypeDef,
     DescribeFleetLocationUtilizationInputRequestTypeDef,
     FleetUtilizationTypeDef,
     DescribeFleetPortSettingsInputRequestTypeDef,
+    DescribeFleetUtilizationInputDescribeFleetUtilizationPaginateTypeDef,
     DescribeFleetUtilizationInputRequestTypeDef,
     DescribeGameServerGroupInputRequestTypeDef,
     DescribeGameServerInputRequestTypeDef,
+    DescribeGameServerInstancesInputDescribeGameServerInstancesPaginateTypeDef,
     DescribeGameServerInstancesInputRequestTypeDef,
     GameServerInstanceTypeDef,
+    DescribeGameSessionDetailsInputDescribeGameSessionDetailsPaginateTypeDef,
     DescribeGameSessionDetailsInputRequestTypeDef,
     DescribeGameSessionPlacementInputRequestTypeDef,
+    DescribeGameSessionQueuesInputDescribeGameSessionQueuesPaginateTypeDef,
     DescribeGameSessionQueuesInputRequestTypeDef,
+    DescribeGameSessionsInputDescribeGameSessionsPaginateTypeDef,
     DescribeGameSessionsInputRequestTypeDef,
+    DescribeInstancesInputDescribeInstancesPaginateTypeDef,
     DescribeInstancesInputRequestTypeDef,
     InstanceTypeDef,
+    DescribeMatchmakingConfigurationsInputDescribeMatchmakingConfigurationsPaginateTypeDef,
     DescribeMatchmakingConfigurationsInputRequestTypeDef,
     DescribeMatchmakingInputRequestTypeDef,
+    DescribeMatchmakingRuleSetsInputDescribeMatchmakingRuleSetsPaginateTypeDef,
     DescribeMatchmakingRuleSetsInputRequestTypeDef,
+    DescribePlayerSessionsInputDescribePlayerSessionsPaginateTypeDef,
     DescribePlayerSessionsInputRequestTypeDef,
     DescribeRuntimeConfigurationInputRequestTypeDef,
+    DescribeScalingPoliciesInputDescribeScalingPoliciesPaginateTypeDef,
     DescribeScalingPoliciesInputRequestTypeDef,
     DescribeScriptInputRequestTypeDef,
     DescribeVpcPeeringConnectionsInputRequestTypeDef,
     DesiredPlayerSessionTypeDef,
     EC2InstanceCountsTypeDef,
+    EmptyResponseMetadataTypeDef,
     TargetTrackingConfigurationTypeDef,
     MatchedPlayerSessionTypeDef,
     PlacedPlayerSessionTypeDef,
     PlayerLatencyTypeDef,
     GetComputeAccessInputRequestTypeDef,
     GetComputeAuthTokenInputRequestTypeDef,
+    GetComputeAuthTokenOutputTypeDef,
     GetGameSessionLogUrlInputRequestTypeDef,
+    GetGameSessionLogUrlOutputTypeDef,
     GetInstanceAccessInputRequestTypeDef,
     InstanceCredentialsTypeDef,
+    ListAliasesInputListAliasesPaginateTypeDef,
     ListAliasesInputRequestTypeDef,
+    ListBuildsInputListBuildsPaginateTypeDef,
     ListBuildsInputRequestTypeDef,
+    ListComputeInputListComputePaginateTypeDef,
     ListComputeInputRequestTypeDef,
+    ListFleetsInputListFleetsPaginateTypeDef,
     ListFleetsInputRequestTypeDef,
+    ListFleetsOutputTypeDef,
+    ListGameServerGroupsInputListGameServerGroupsPaginateTypeDef,
     ListGameServerGroupsInputRequestTypeDef,
+    ListGameServersInputListGameServersPaginateTypeDef,
     ListGameServersInputRequestTypeDef,
+    ListLocationsInputListLocationsPaginateTypeDef,
     ListLocationsInputRequestTypeDef,
+    ListScriptsInputListScriptsPaginateTypeDef,
     ListScriptsInputRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     TargetConfigurationTypeDef,
+    PutScalingPolicyOutputTypeDef,
     RegisterComputeInputRequestTypeDef,
     RegisterGameServerInputRequestTypeDef,
     RequestUploadCredentialsInputRequestTypeDef,
     ResolveAliasInputRequestTypeDef,
+    ResolveAliasOutputTypeDef,
+    ResponseMetadataTypeDef,
     ResumeGameServerGroupInputRequestTypeDef,
     ServerProcessTypeDef,
     SearchGameSessionsInputRequestTypeDef,
+    SearchGameSessionsInputSearchGameSessionsPaginateTypeDef,
     StartFleetActionsInputRequestTypeDef,
+    StartFleetActionsOutputTypeDef,
     StopFleetActionsInputRequestTypeDef,
+    StopFleetActionsOutputTypeDef,
     StopGameSessionPlacementInputRequestTypeDef,
     StopMatchmakingInputRequestTypeDef,
     SuspendGameServerGroupInputRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateBuildInputRequestTypeDef,
+    UpdateFleetAttributesOutputTypeDef,
     UpdateFleetCapacityInputRequestTypeDef,
+    UpdateFleetCapacityOutputTypeDef,
+    UpdateFleetPortSettingsOutputTypeDef,
     UpdateGameServerInputRequestTypeDef,
     UpdateGameSessionInputRequestTypeDef,
     ValidateMatchmakingRuleSetInputRequestTypeDef,
+    ValidateMatchmakingRuleSetOutputTypeDef,
     VpcPeeringConnectionStatusTypeDef,
     AliasTypeDef,
     UpdateAliasInputRequestTypeDef,
     PlayerTypeDef,
-    ClaimGameServerOutputTypeDef,
-    DescribeBuildOutputTypeDef,
-    DescribeGameServerOutputTypeDef,
-    EmptyResponseMetadataTypeDef,
     GetComputeAccessOutputTypeDef,
-    GetComputeAuthTokenOutputTypeDef,
-    GetGameSessionLogUrlOutputTypeDef,
+    DescribeBuildOutputTypeDef,
     ListBuildsOutputTypeDef,
-    ListFleetsOutputTypeDef,
+    UpdateBuildOutputTypeDef,
+    ClaimGameServerInputRequestTypeDef,
+    ClaimGameServerOutputTypeDef,
+    DescribeGameServerOutputTypeDef,
     ListGameServersOutputTypeDef,
-    PutScalingPolicyOutputTypeDef,
     RegisterGameServerOutputTypeDef,
-    ResolveAliasOutputTypeDef,
-    StartFleetActionsOutputTypeDef,
-    StopFleetActionsOutputTypeDef,
-    UpdateBuildOutputTypeDef,
-    UpdateFleetAttributesOutputTypeDef,
-    UpdateFleetCapacityOutputTypeDef,
-    UpdateFleetPortSettingsOutputTypeDef,
     UpdateGameServerOutputTypeDef,
-    ValidateMatchmakingRuleSetOutputTypeDef,
     DescribeComputeOutputTypeDef,
     ListComputeOutputTypeDef,
     RegisterComputeOutputTypeDef,
     CreateAliasInputRequestTypeDef,
     CreateLocationInputRequestTypeDef,
     CreateMatchmakingRuleSetInputRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
@@ -639,36 +663,14 @@
     DescribeMatchmakingRuleSetsOutputTypeDef,
     CreatePlayerSessionOutputTypeDef,
     CreatePlayerSessionsOutputTypeDef,
     DescribePlayerSessionsOutputTypeDef,
     CreateVpcPeeringAuthorizationOutputTypeDef,
     DescribeVpcPeeringAuthorizationsOutputTypeDef,
     DescribeEC2InstanceLimitsOutputTypeDef,
-    DescribeFleetAttributesInputDescribeFleetAttributesPaginateTypeDef,
-    DescribeFleetCapacityInputDescribeFleetCapacityPaginateTypeDef,
-    DescribeFleetEventsInputDescribeFleetEventsPaginateTypeDef,
-    DescribeFleetUtilizationInputDescribeFleetUtilizationPaginateTypeDef,
-    DescribeGameServerInstancesInputDescribeGameServerInstancesPaginateTypeDef,
-    DescribeGameSessionDetailsInputDescribeGameSessionDetailsPaginateTypeDef,
-    DescribeGameSessionQueuesInputDescribeGameSessionQueuesPaginateTypeDef,
-    DescribeGameSessionsInputDescribeGameSessionsPaginateTypeDef,
-    DescribeInstancesInputDescribeInstancesPaginateTypeDef,
-    DescribeMatchmakingConfigurationsInputDescribeMatchmakingConfigurationsPaginateTypeDef,
-    DescribeMatchmakingRuleSetsInputDescribeMatchmakingRuleSetsPaginateTypeDef,
-    DescribePlayerSessionsInputDescribePlayerSessionsPaginateTypeDef,
-    DescribeScalingPoliciesInputDescribeScalingPoliciesPaginateTypeDef,
-    ListAliasesInputListAliasesPaginateTypeDef,
-    ListBuildsInputListBuildsPaginateTypeDef,
-    ListComputeInputListComputePaginateTypeDef,
-    ListFleetsInputListFleetsPaginateTypeDef,
-    ListGameServerGroupsInputListGameServerGroupsPaginateTypeDef,
-    ListGameServersInputListGameServersPaginateTypeDef,
-    ListLocationsInputListLocationsPaginateTypeDef,
-    ListScriptsInputListScriptsPaginateTypeDef,
-    SearchGameSessionsInputSearchGameSessionsPaginateTypeDef,
     DescribeFleetEventsOutputTypeDef,
     DescribeFleetLocationUtilizationOutputTypeDef,
     DescribeFleetUtilizationOutputTypeDef,
     DescribeGameServerInstancesOutputTypeDef,
     DescribeInstancesOutputTypeDef,
     FleetCapacityTypeDef,
     GameServerGroupAutoScalingPolicyTypeDef,
@@ -739,43 +741,43 @@
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

### Comparing `types-aiobotocore-gamelift-2.5.0.post1/README.md` & `types-aiobotocore-gamelift-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-gamelift"></a>
 
 # types-aiobotocore-gamelift
 
 [![PyPI - types-aiobotocore-gamelift](https://img.shields.io/pypi/v/types-aiobotocore-gamelift.svg?color=blue)](https://pypi.org/project/types-aiobotocore-gamelift)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-gamelift.svg?color=blue)](https://pypi.org/project/types-aiobotocore-gamelift)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-gamelift?color=blue)](https://pypistats.org/packages/types-aiobotocore-gamelift)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.GameLift 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift)
+[aiobotocore.GameLift 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift)
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
 [types-aiobotocore-gamelift docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/).
 
 See how it helps to find and fix potential bugs:
 
@@ -357,14 +357,15 @@
     DescribeInstancesPaginatorName,
     DescribeMatchmakingConfigurationsPaginatorName,
     DescribeMatchmakingRuleSetsPaginatorName,
     DescribePlayerSessionsPaginatorName,
     DescribeScalingPoliciesPaginatorName,
     EC2InstanceTypeType,
     EventCodeType,
+    FilterInstanceStatusType,
     FleetActionType,
     FleetStatusType,
     FleetTypeType,
     FlexMatchModeType,
     GameServerClaimStatusType,
     GameServerGroupActionType,
     GameServerGroupDeleteOptionType,
@@ -426,17 +427,16 @@
     AcceptMatchInputRequestTypeDef,
     RoutingStrategyTypeDef,
     AnywhereConfigurationTypeDef,
     AttributeValueTypeDef,
     AwsCredentialsTypeDef,
     BuildTypeDef,
     CertificateConfigurationTypeDef,
-    ClaimGameServerInputRequestTypeDef,
+    ClaimFilterOptionTypeDef,
     GameServerTypeDef,
-    ResponseMetadataTypeDef,
     ComputeTypeDef,
     TagTypeDef,
     S3LocationTypeDef,
     IpPermissionTypeDef,
     LocationConfigurationTypeDef,
     ResourceCreationLimitPolicyTypeDef,
     LocationStateTypeDef,
@@ -471,107 +471,131 @@
     DeregisterComputeInputRequestTypeDef,
     DeregisterGameServerInputRequestTypeDef,
     DescribeAliasInputRequestTypeDef,
     DescribeBuildInputRequestTypeDef,
     DescribeComputeInputRequestTypeDef,
     DescribeEC2InstanceLimitsInputRequestTypeDef,
     EC2InstanceLimitTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeFleetAttributesInputDescribeFleetAttributesPaginateTypeDef,
     DescribeFleetAttributesInputRequestTypeDef,
+    DescribeFleetCapacityInputDescribeFleetCapacityPaginateTypeDef,
     DescribeFleetCapacityInputRequestTypeDef,
+    DescribeFleetEventsInputDescribeFleetEventsPaginateTypeDef,
     DescribeFleetEventsInputRequestTypeDef,
     EventTypeDef,
     DescribeFleetLocationAttributesInputRequestTypeDef,
     DescribeFleetLocationCapacityInputRequestTypeDef,
     DescribeFleetLocationUtilizationInputRequestTypeDef,
     FleetUtilizationTypeDef,
     DescribeFleetPortSettingsInputRequestTypeDef,
+    DescribeFleetUtilizationInputDescribeFleetUtilizationPaginateTypeDef,
     DescribeFleetUtilizationInputRequestTypeDef,
     DescribeGameServerGroupInputRequestTypeDef,
     DescribeGameServerInputRequestTypeDef,
+    DescribeGameServerInstancesInputDescribeGameServerInstancesPaginateTypeDef,
     DescribeGameServerInstancesInputRequestTypeDef,
     GameServerInstanceTypeDef,
+    DescribeGameSessionDetailsInputDescribeGameSessionDetailsPaginateTypeDef,
     DescribeGameSessionDetailsInputRequestTypeDef,
     DescribeGameSessionPlacementInputRequestTypeDef,
+    DescribeGameSessionQueuesInputDescribeGameSessionQueuesPaginateTypeDef,
     DescribeGameSessionQueuesInputRequestTypeDef,
+    DescribeGameSessionsInputDescribeGameSessionsPaginateTypeDef,
     DescribeGameSessionsInputRequestTypeDef,
+    DescribeInstancesInputDescribeInstancesPaginateTypeDef,
     DescribeInstancesInputRequestTypeDef,
     InstanceTypeDef,
+    DescribeMatchmakingConfigurationsInputDescribeMatchmakingConfigurationsPaginateTypeDef,
     DescribeMatchmakingConfigurationsInputRequestTypeDef,
     DescribeMatchmakingInputRequestTypeDef,
+    DescribeMatchmakingRuleSetsInputDescribeMatchmakingRuleSetsPaginateTypeDef,
     DescribeMatchmakingRuleSetsInputRequestTypeDef,
+    DescribePlayerSessionsInputDescribePlayerSessionsPaginateTypeDef,
     DescribePlayerSessionsInputRequestTypeDef,
     DescribeRuntimeConfigurationInputRequestTypeDef,
+    DescribeScalingPoliciesInputDescribeScalingPoliciesPaginateTypeDef,
     DescribeScalingPoliciesInputRequestTypeDef,
     DescribeScriptInputRequestTypeDef,
     DescribeVpcPeeringConnectionsInputRequestTypeDef,
     DesiredPlayerSessionTypeDef,
     EC2InstanceCountsTypeDef,
+    EmptyResponseMetadataTypeDef,
     TargetTrackingConfigurationTypeDef,
     MatchedPlayerSessionTypeDef,
     PlacedPlayerSessionTypeDef,
     PlayerLatencyTypeDef,
     GetComputeAccessInputRequestTypeDef,
     GetComputeAuthTokenInputRequestTypeDef,
+    GetComputeAuthTokenOutputTypeDef,
     GetGameSessionLogUrlInputRequestTypeDef,
+    GetGameSessionLogUrlOutputTypeDef,
     GetInstanceAccessInputRequestTypeDef,
     InstanceCredentialsTypeDef,
+    ListAliasesInputListAliasesPaginateTypeDef,
     ListAliasesInputRequestTypeDef,
+    ListBuildsInputListBuildsPaginateTypeDef,
     ListBuildsInputRequestTypeDef,
+    ListComputeInputListComputePaginateTypeDef,
     ListComputeInputRequestTypeDef,
+    ListFleetsInputListFleetsPaginateTypeDef,
     ListFleetsInputRequestTypeDef,
+    ListFleetsOutputTypeDef,
+    ListGameServerGroupsInputListGameServerGroupsPaginateTypeDef,
     ListGameServerGroupsInputRequestTypeDef,
+    ListGameServersInputListGameServersPaginateTypeDef,
     ListGameServersInputRequestTypeDef,
+    ListLocationsInputListLocationsPaginateTypeDef,
     ListLocationsInputRequestTypeDef,
+    ListScriptsInputListScriptsPaginateTypeDef,
     ListScriptsInputRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     TargetConfigurationTypeDef,
+    PutScalingPolicyOutputTypeDef,
     RegisterComputeInputRequestTypeDef,
     RegisterGameServerInputRequestTypeDef,
     RequestUploadCredentialsInputRequestTypeDef,
     ResolveAliasInputRequestTypeDef,
+    ResolveAliasOutputTypeDef,
+    ResponseMetadataTypeDef,
     ResumeGameServerGroupInputRequestTypeDef,
     ServerProcessTypeDef,
     SearchGameSessionsInputRequestTypeDef,
+    SearchGameSessionsInputSearchGameSessionsPaginateTypeDef,
     StartFleetActionsInputRequestTypeDef,
+    StartFleetActionsOutputTypeDef,
     StopFleetActionsInputRequestTypeDef,
+    StopFleetActionsOutputTypeDef,
     StopGameSessionPlacementInputRequestTypeDef,
     StopMatchmakingInputRequestTypeDef,
     SuspendGameServerGroupInputRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateBuildInputRequestTypeDef,
+    UpdateFleetAttributesOutputTypeDef,
     UpdateFleetCapacityInputRequestTypeDef,
+    UpdateFleetCapacityOutputTypeDef,
+    UpdateFleetPortSettingsOutputTypeDef,
     UpdateGameServerInputRequestTypeDef,
     UpdateGameSessionInputRequestTypeDef,
     ValidateMatchmakingRuleSetInputRequestTypeDef,
+    ValidateMatchmakingRuleSetOutputTypeDef,
     VpcPeeringConnectionStatusTypeDef,
     AliasTypeDef,
     UpdateAliasInputRequestTypeDef,
     PlayerTypeDef,
-    ClaimGameServerOutputTypeDef,
-    DescribeBuildOutputTypeDef,
-    DescribeGameServerOutputTypeDef,
-    EmptyResponseMetadataTypeDef,
     GetComputeAccessOutputTypeDef,
-    GetComputeAuthTokenOutputTypeDef,
-    GetGameSessionLogUrlOutputTypeDef,
+    DescribeBuildOutputTypeDef,
     ListBuildsOutputTypeDef,
-    ListFleetsOutputTypeDef,
+    UpdateBuildOutputTypeDef,
+    ClaimGameServerInputRequestTypeDef,
+    ClaimGameServerOutputTypeDef,
+    DescribeGameServerOutputTypeDef,
     ListGameServersOutputTypeDef,
-    PutScalingPolicyOutputTypeDef,
     RegisterGameServerOutputTypeDef,
-    ResolveAliasOutputTypeDef,
-    StartFleetActionsOutputTypeDef,
-    StopFleetActionsOutputTypeDef,
-    UpdateBuildOutputTypeDef,
-    UpdateFleetAttributesOutputTypeDef,
-    UpdateFleetCapacityOutputTypeDef,
-    UpdateFleetPortSettingsOutputTypeDef,
     UpdateGameServerOutputTypeDef,
-    ValidateMatchmakingRuleSetOutputTypeDef,
     DescribeComputeOutputTypeDef,
     ListComputeOutputTypeDef,
     RegisterComputeOutputTypeDef,
     CreateAliasInputRequestTypeDef,
     CreateLocationInputRequestTypeDef,
     CreateMatchmakingRuleSetInputRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
@@ -606,36 +630,14 @@
     DescribeMatchmakingRuleSetsOutputTypeDef,
     CreatePlayerSessionOutputTypeDef,
     CreatePlayerSessionsOutputTypeDef,
     DescribePlayerSessionsOutputTypeDef,
     CreateVpcPeeringAuthorizationOutputTypeDef,
     DescribeVpcPeeringAuthorizationsOutputTypeDef,
     DescribeEC2InstanceLimitsOutputTypeDef,
-    DescribeFleetAttributesInputDescribeFleetAttributesPaginateTypeDef,
-    DescribeFleetCapacityInputDescribeFleetCapacityPaginateTypeDef,
-    DescribeFleetEventsInputDescribeFleetEventsPaginateTypeDef,
-    DescribeFleetUtilizationInputDescribeFleetUtilizationPaginateTypeDef,
-    DescribeGameServerInstancesInputDescribeGameServerInstancesPaginateTypeDef,
-    DescribeGameSessionDetailsInputDescribeGameSessionDetailsPaginateTypeDef,
-    DescribeGameSessionQueuesInputDescribeGameSessionQueuesPaginateTypeDef,
-    DescribeGameSessionsInputDescribeGameSessionsPaginateTypeDef,
-    DescribeInstancesInputDescribeInstancesPaginateTypeDef,
-    DescribeMatchmakingConfigurationsInputDescribeMatchmakingConfigurationsPaginateTypeDef,
-    DescribeMatchmakingRuleSetsInputDescribeMatchmakingRuleSetsPaginateTypeDef,
-    DescribePlayerSessionsInputDescribePlayerSessionsPaginateTypeDef,
-    DescribeScalingPoliciesInputDescribeScalingPoliciesPaginateTypeDef,
-    ListAliasesInputListAliasesPaginateTypeDef,
-    ListBuildsInputListBuildsPaginateTypeDef,
-    ListComputeInputListComputePaginateTypeDef,
-    ListFleetsInputListFleetsPaginateTypeDef,
-    ListGameServerGroupsInputListGameServerGroupsPaginateTypeDef,
-    ListGameServersInputListGameServersPaginateTypeDef,
-    ListLocationsInputListLocationsPaginateTypeDef,
-    ListScriptsInputListScriptsPaginateTypeDef,
-    SearchGameSessionsInputSearchGameSessionsPaginateTypeDef,
     DescribeFleetEventsOutputTypeDef,
     DescribeFleetLocationUtilizationOutputTypeDef,
     DescribeFleetUtilizationOutputTypeDef,
     DescribeGameServerInstancesOutputTypeDef,
     DescribeInstancesOutputTypeDef,
     FleetCapacityTypeDef,
     GameServerGroupAutoScalingPolicyTypeDef,
@@ -706,43 +708,43 @@
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

### Comparing `types-aiobotocore-gamelift-2.5.0.post1/setup.py` & `types-aiobotocore-gamelift-2.5.1/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-gamelift.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-gamelift",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_gamelift"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.GameLift 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.GameLift 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/"
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

### Comparing `types-aiobotocore-gamelift-2.5.0.post1/types_aiobotocore_gamelift/__init__.py` & `types-aiobotocore-gamelift-2.5.1/types_aiobotocore_gamelift/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-gamelift-2.5.0.post1/types_aiobotocore_gamelift/__init__.pyi` & `types-aiobotocore-gamelift-2.5.1/types_aiobotocore_gamelift/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-gamelift-2.5.0.post1/types_aiobotocore_gamelift/__main__.py` & `types-aiobotocore-gamelift-2.5.1/types_aiobotocore_gamelift/__main__.py`

 * *Files 16% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.GameLift 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.GameLift 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift\nOther"
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

### Comparing `types-aiobotocore-gamelift-2.5.0.post1/types_aiobotocore_gamelift/client.py` & `types-aiobotocore-gamelift-2.5.1/types_aiobotocore_gamelift/client.py`

 * *Files 1% similar despite different names*

```diff
@@ -69,14 +69,15 @@
     ListLocationsPaginator,
     ListScriptsPaginator,
     SearchGameSessionsPaginator,
 )
 from .type_defs import (
     AnywhereConfigurationTypeDef,
     CertificateConfigurationTypeDef,
+    ClaimFilterOptionTypeDef,
     ClaimGameServerOutputTypeDef,
     CreateAliasOutputTypeDef,
     CreateBuildOutputTypeDef,
     CreateFleetLocationsOutputTypeDef,
     CreateFleetOutputTypeDef,
     CreateGameServerGroupOutputTypeDef,
     CreateGameSessionOutputTypeDef,
@@ -249,20 +250,25 @@
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#can_paginate)
         """
 
     async def claim_game_server(
-        self, *, GameServerGroupName: str, GameServerId: str = ..., GameServerData: str = ...
+        self,
+        *,
+        GameServerGroupName: str,
+        GameServerId: str = ...,
+        GameServerData: str = ...,
+        FilterOption: ClaimFilterOptionTypeDef = ...
     ) -> ClaimGameServerOutputTypeDef:
         """
-        **This operation is used with the GameLift FleetIQ solution and game server
-        groups.** Locates an available game server and temporarily reserves it to host
-        gameplay and players.
+        **This operation is used with the Amazon GameLift FleetIQ solution and game
+        server groups.** Locates an available game server and temporarily reserves it to
+        host gameplay and players.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.claim_game_server)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#claim_game_server)
         """
 
     async def close(self) -> None:
         """
@@ -327,16 +333,16 @@
         CertificateConfiguration: CertificateConfigurationTypeDef = ...,
         Locations: Sequence[LocationConfigurationTypeDef] = ...,
         Tags: Sequence[TagTypeDef] = ...,
         ComputeType: ComputeTypeType = ...,
         AnywhereConfiguration: AnywhereConfigurationTypeDef = ...
     ) -> CreateFleetOutputTypeDef:
         """
-        Creates a fleet of Amazon Elastic Compute Cloud (Amazon Elastic Compute Cloud)
-        instances to host your custom game server or Realtime Servers.
+        Creates a fleet of Amazon Elastic Compute Cloud (Amazon EC2) instances to host
+        your custom game server or Realtime Servers.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.create_fleet)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#create_fleet)
         """
 
     async def create_fleet_locations(
         self, *, FleetId: str, Locations: Sequence[LocationConfigurationTypeDef]
@@ -361,17 +367,18 @@
         AutoScalingPolicy: GameServerGroupAutoScalingPolicyTypeDef = ...,
         BalancingStrategy: BalancingStrategyType = ...,
         GameServerProtectionPolicy: GameServerProtectionPolicyType = ...,
         VpcSubnets: Sequence[str] = ...,
         Tags: Sequence[TagTypeDef] = ...
     ) -> CreateGameServerGroupOutputTypeDef:
         """
-        **This operation is used with the GameLift FleetIQ solution and game server
-        groups.** Creates a GameLift FleetIQ game server group for managing game hosting
-        on a collection of Amazon Elastic Compute Cloud instances for game hosting.
+        **This operation is used with the Amazon GameLift FleetIQ solution and game
+        server groups.** Creates a Amazon GameLift FleetIQ game server group for
+        managing game hosting on a collection of Amazon Elastic Compute Cloud instances
+        for game hosting.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.create_game_server_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#create_game_server_group)
         """
 
     async def create_game_session(
         self,
@@ -557,17 +564,17 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#delete_fleet_locations)
         """
 
     async def delete_game_server_group(
         self, *, GameServerGroupName: str, DeleteOption: GameServerGroupDeleteOptionType = ...
     ) -> DeleteGameServerGroupOutputTypeDef:
         """
-        **This operation is used with the GameLift FleetIQ solution and game server
-        groups.** Terminates a game server group and permanently deletes the game server
-        group record.
+        **This operation is used with the Amazon GameLift FleetIQ solution and game
+        server groups.** Terminates a game server group and permanently deletes the game
+        server group record.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.delete_game_server_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#delete_game_server_group)
         """
 
     async def delete_game_session_queue(self, *, Name: str) -> Dict[str, Any]:
         """
@@ -647,16 +654,16 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#deregister_compute)
         """
 
     async def deregister_game_server(
         self, *, GameServerGroupName: str, GameServerId: str
     ) -> EmptyResponseMetadataTypeDef:
         """
-        **This operation is used with the GameLift FleetIQ solution and game server
-        groups.** Removes the game server from a game server group.
+        **This operation is used with the Amazon GameLift FleetIQ solution and game
+        server groups.** Removes the game server from a game server group.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.deregister_game_server)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#deregister_game_server)
         """
 
     async def describe_alias(self, *, AliasId: str) -> DescribeAliasOutputTypeDef:
         """
@@ -788,44 +795,44 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#describe_fleet_utilization)
         """
 
     async def describe_game_server(
         self, *, GameServerGroupName: str, GameServerId: str
     ) -> DescribeGameServerOutputTypeDef:
         """
-        **This operation is used with the GameLift FleetIQ solution and game server
-        groups.** Retrieves information for a registered game server.
+        **This operation is used with the Amazon GameLift FleetIQ solution and game
+        server groups.** Retrieves information for a registered game server.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.describe_game_server)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#describe_game_server)
         """
 
     async def describe_game_server_group(
         self, *, GameServerGroupName: str
     ) -> DescribeGameServerGroupOutputTypeDef:
         """
-        **This operation is used with the GameLift FleetIQ solution and game server
-        groups.** Retrieves information on a game server group.
+        **This operation is used with the Amazon GameLift FleetIQ solution and game
+        server groups.** Retrieves information on a game server group.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.describe_game_server_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#describe_game_server_group)
         """
 
     async def describe_game_server_instances(
         self,
         *,
         GameServerGroupName: str,
         InstanceIds: Sequence[str] = ...,
         Limit: int = ...,
         NextToken: str = ...
     ) -> DescribeGameServerInstancesOutputTypeDef:
         """
-        **This operation is used with the GameLift FleetIQ solution and game server
-        groups.** Retrieves status information about the Amazon EC2 instances associated
-        with a GameLift FleetIQ game server group.
+        **This operation is used with the Amazon GameLift FleetIQ solution and game
+        server groups.** Retrieves status information about the Amazon EC2 instances
+        associated with a Amazon GameLift FleetIQ game server group.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.describe_game_server_instances)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#describe_game_server_instances)
         """
 
     async def describe_game_session_details(
         self,
@@ -1034,25 +1041,26 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#get_compute_access)
         """
 
     async def get_compute_auth_token(
         self, *, FleetId: str, ComputeName: str
     ) -> GetComputeAuthTokenOutputTypeDef:
         """
-        Requests an authorization token from GameLift.
+        Requests an authentication token from Amazon GameLift.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.get_compute_auth_token)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#get_compute_auth_token)
         """
 
     async def get_game_session_log_url(
         self, *, GameSessionId: str
     ) -> GetGameSessionLogUrlOutputTypeDef:
         """
-        Retrieves the location of stored game session logs for a specified game session.
+        Retrieves the location of stored game session logs for a specified game session
+        on Amazon GameLift managed fleets.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.get_game_session_log_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#get_game_session_log_url)
         """
 
     async def get_instance_access(
         self, *, FleetId: str, InstanceId: str
@@ -1126,17 +1134,17 @@
         *,
         GameServerGroupName: str,
         SortOrder: SortOrderType = ...,
         Limit: int = ...,
         NextToken: str = ...
     ) -> ListGameServersOutputTypeDef:
         """
-        **This operation is used with the GameLift FleetIQ solution and game server
-        groups.** Retrieves information on all game servers that are currently active in
-        a specified game server group.
+        **This operation is used with the Amazon GameLift FleetIQ solution and game
+        server groups.** Retrieves information on all game servers that are currently
+        active in a specified game server group.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.list_game_servers)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#list_game_servers)
         """
 
     async def list_locations(
         self, *, Filters: Sequence[LocationFilterType] = ..., Limit: int = ..., NextToken: str = ...
@@ -1159,15 +1167,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#list_scripts)
         """
 
     async def list_tags_for_resource(
         self, *, ResourceARN: str
     ) -> ListTagsForResourceResponseTypeDef:
         """
-        Retrieves all tags that are assigned to a GameLift resource.
+        Retrieves all tags assigned to a Amazon GameLift resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#list_tags_for_resource)
         """
 
     async def put_scaling_policy(
         self,
@@ -1213,17 +1221,17 @@
         GameServerGroupName: str,
         GameServerId: str,
         InstanceId: str,
         ConnectionInfo: str = ...,
         GameServerData: str = ...
     ) -> RegisterGameServerOutputTypeDef:
         """
-        **This operation is used with the GameLift FleetIQ solution and game server
-        groups.** Creates a new game server resource and notifies GameLift FleetIQ that
-        the game server is ready to host gameplay and players.
+        **This operation is used with the Amazon GameLift FleetIQ solution and game
+        server groups.** Creates a new game server resource and notifies Amazon GameLift
+        FleetIQ that the game server is ready to host gameplay and players.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.register_game_server)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#register_game_server)
         """
 
     async def request_upload_credentials(
         self, *, BuildId: str
@@ -1247,16 +1255,16 @@
     async def resume_game_server_group(
         self,
         *,
         GameServerGroupName: str,
         ResumeActions: Sequence[Literal["REPLACE_INSTANCE_TYPES"]]
     ) -> ResumeGameServerGroupOutputTypeDef:
         """
-        **This operation is used with the GameLift FleetIQ solution and game server
-        groups.** Reinstates activity on a game server group after it has been
+        **This operation is used with the Amazon GameLift FleetIQ solution and game
+        server groups.** Reinstates activity on a game server group after it has been
         suspended.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.resume_game_server_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#resume_game_server_group)
         """
 
     async def search_game_sessions(
@@ -1366,33 +1374,33 @@
     async def suspend_game_server_group(
         self,
         *,
         GameServerGroupName: str,
         SuspendActions: Sequence[Literal["REPLACE_INSTANCE_TYPES"]]
     ) -> SuspendGameServerGroupOutputTypeDef:
         """
-        **This operation is used with the GameLift FleetIQ solution and game server
-        groups.** Temporarily stops activity on a game server group without terminating
-        instances or the game server group.
+        **This operation is used with the Amazon GameLift FleetIQ solution and game
+        server groups.** Temporarily stops activity on a game server group without
+        terminating instances or the game server group.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.suspend_game_server_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#suspend_game_server_group)
         """
 
     async def tag_resource(self, *, ResourceARN: str, Tags: Sequence[TagTypeDef]) -> Dict[str, Any]:
         """
-        Assigns a tag to a GameLift resource.
+        Assigns a tag to an Amazon GameLift resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#tag_resource)
         """
 
     async def untag_resource(self, *, ResourceARN: str, TagKeys: Sequence[str]) -> Dict[str, Any]:
         """
-        Removes a tag that is assigned to a GameLift resource.
+        Removes a tag assigned to a Amazon GameLift resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#untag_resource)
         """
 
     async def update_alias(
         self,
@@ -1475,17 +1483,17 @@
         GameServerGroupName: str,
         GameServerId: str,
         GameServerData: str = ...,
         UtilizationStatus: GameServerUtilizationStatusType = ...,
         HealthCheck: Literal["HEALTHY"] = ...
     ) -> UpdateGameServerOutputTypeDef:
         """
-        **This operation is used with the GameLift FleetIQ solution and game server
-        groups.** Updates information about a registered game server to help GameLift
-        FleetIQ to track game server availability.
+        **This operation is used with the Amazon GameLift FleetIQ solution and game
+        server groups.** Updates information about a registered game server to help
+        Amazon GameLift FleetIQ to track game server availability.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.update_game_server)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#update_game_server)
         """
 
     async def update_game_server_group(
         self,
@@ -1493,16 +1501,17 @@
         GameServerGroupName: str,
         RoleArn: str = ...,
         InstanceDefinitions: Sequence[InstanceDefinitionTypeDef] = ...,
         GameServerProtectionPolicy: GameServerProtectionPolicyType = ...,
         BalancingStrategy: BalancingStrategyType = ...
     ) -> UpdateGameServerGroupOutputTypeDef:
         """
-        **This operation is used with the GameLift FleetIQ solution and game server
-        groups.** Updates GameLift FleetIQ-specific properties for a game server group.
+        **This operation is used with the Amazon GameLift FleetIQ solution and game
+        server groups.** Updates Amazon GameLift FleetIQ-specific properties for a game
+        server group.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.update_game_server_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#update_game_server_group)
         """
 
     async def update_game_session(
         self,
@@ -1566,15 +1575,15 @@
         """
 
     async def update_runtime_configuration(
         self, *, FleetId: str, RuntimeConfiguration: RuntimeConfigurationTypeDef
     ) -> UpdateRuntimeConfigurationOutputTypeDef:
         """
         Updates the current runtime configuration for the specified fleet, which tells
-        GameLift how to launch server processes on all instances in the fleet.
+        Amazon GameLift how to launch server processes on all instances in the fleet.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.update_runtime_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#update_runtime_configuration)
         """
 
     async def update_script(
         self,
```

### Comparing `types-aiobotocore-gamelift-2.5.0.post1/types_aiobotocore_gamelift/client.pyi` & `types-aiobotocore-gamelift-2.5.1/types_aiobotocore_gamelift/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -69,14 +69,15 @@
     ListLocationsPaginator,
     ListScriptsPaginator,
     SearchGameSessionsPaginator,
 )
 from .type_defs import (
     AnywhereConfigurationTypeDef,
     CertificateConfigurationTypeDef,
+    ClaimFilterOptionTypeDef,
     ClaimGameServerOutputTypeDef,
     CreateAliasOutputTypeDef,
     CreateBuildOutputTypeDef,
     CreateFleetLocationsOutputTypeDef,
     CreateFleetOutputTypeDef,
     CreateGameServerGroupOutputTypeDef,
     CreateGameSessionOutputTypeDef,
@@ -242,20 +243,25 @@
         """
         Check if an operation can be paginated.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.can_paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#can_paginate)
         """
     async def claim_game_server(
-        self, *, GameServerGroupName: str, GameServerId: str = ..., GameServerData: str = ...
+        self,
+        *,
+        GameServerGroupName: str,
+        GameServerId: str = ...,
+        GameServerData: str = ...,
+        FilterOption: ClaimFilterOptionTypeDef = ...
     ) -> ClaimGameServerOutputTypeDef:
         """
-        **This operation is used with the GameLift FleetIQ solution and game server
-        groups.** Locates an available game server and temporarily reserves it to host
-        gameplay and players.
+        **This operation is used with the Amazon GameLift FleetIQ solution and game
+        server groups.** Locates an available game server and temporarily reserves it to
+        host gameplay and players.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.claim_game_server)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#claim_game_server)
         """
     async def close(self) -> None:
         """
         Closes underlying endpoint connections.
@@ -316,16 +322,16 @@
         CertificateConfiguration: CertificateConfigurationTypeDef = ...,
         Locations: Sequence[LocationConfigurationTypeDef] = ...,
         Tags: Sequence[TagTypeDef] = ...,
         ComputeType: ComputeTypeType = ...,
         AnywhereConfiguration: AnywhereConfigurationTypeDef = ...
     ) -> CreateFleetOutputTypeDef:
         """
-        Creates a fleet of Amazon Elastic Compute Cloud (Amazon Elastic Compute Cloud)
-        instances to host your custom game server or Realtime Servers.
+        Creates a fleet of Amazon Elastic Compute Cloud (Amazon EC2) instances to host
+        your custom game server or Realtime Servers.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.create_fleet)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#create_fleet)
         """
     async def create_fleet_locations(
         self, *, FleetId: str, Locations: Sequence[LocationConfigurationTypeDef]
     ) -> CreateFleetLocationsOutputTypeDef:
@@ -348,17 +354,18 @@
         AutoScalingPolicy: GameServerGroupAutoScalingPolicyTypeDef = ...,
         BalancingStrategy: BalancingStrategyType = ...,
         GameServerProtectionPolicy: GameServerProtectionPolicyType = ...,
         VpcSubnets: Sequence[str] = ...,
         Tags: Sequence[TagTypeDef] = ...
     ) -> CreateGameServerGroupOutputTypeDef:
         """
-        **This operation is used with the GameLift FleetIQ solution and game server
-        groups.** Creates a GameLift FleetIQ game server group for managing game hosting
-        on a collection of Amazon Elastic Compute Cloud instances for game hosting.
+        **This operation is used with the Amazon GameLift FleetIQ solution and game
+        server groups.** Creates a Amazon GameLift FleetIQ game server group for
+        managing game hosting on a collection of Amazon Elastic Compute Cloud instances
+        for game hosting.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.create_game_server_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#create_game_server_group)
         """
     async def create_game_session(
         self,
         *,
@@ -529,17 +536,17 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.delete_fleet_locations)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#delete_fleet_locations)
         """
     async def delete_game_server_group(
         self, *, GameServerGroupName: str, DeleteOption: GameServerGroupDeleteOptionType = ...
     ) -> DeleteGameServerGroupOutputTypeDef:
         """
-        **This operation is used with the GameLift FleetIQ solution and game server
-        groups.** Terminates a game server group and permanently deletes the game server
-        group record.
+        **This operation is used with the Amazon GameLift FleetIQ solution and game
+        server groups.** Terminates a game server group and permanently deletes the game
+        server group record.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.delete_game_server_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#delete_game_server_group)
         """
     async def delete_game_session_queue(self, *, Name: str) -> Dict[str, Any]:
         """
         Deletes a game session queue.
@@ -609,16 +616,16 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.deregister_compute)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#deregister_compute)
         """
     async def deregister_game_server(
         self, *, GameServerGroupName: str, GameServerId: str
     ) -> EmptyResponseMetadataTypeDef:
         """
-        **This operation is used with the GameLift FleetIQ solution and game server
-        groups.** Removes the game server from a game server group.
+        **This operation is used with the Amazon GameLift FleetIQ solution and game
+        server groups.** Removes the game server from a game server group.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.deregister_game_server)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#deregister_game_server)
         """
     async def describe_alias(self, *, AliasId: str) -> DescribeAliasOutputTypeDef:
         """
         Retrieves properties for an alias.
@@ -737,42 +744,42 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.describe_fleet_utilization)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#describe_fleet_utilization)
         """
     async def describe_game_server(
         self, *, GameServerGroupName: str, GameServerId: str
     ) -> DescribeGameServerOutputTypeDef:
         """
-        **This operation is used with the GameLift FleetIQ solution and game server
-        groups.** Retrieves information for a registered game server.
+        **This operation is used with the Amazon GameLift FleetIQ solution and game
+        server groups.** Retrieves information for a registered game server.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.describe_game_server)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#describe_game_server)
         """
     async def describe_game_server_group(
         self, *, GameServerGroupName: str
     ) -> DescribeGameServerGroupOutputTypeDef:
         """
-        **This operation is used with the GameLift FleetIQ solution and game server
-        groups.** Retrieves information on a game server group.
+        **This operation is used with the Amazon GameLift FleetIQ solution and game
+        server groups.** Retrieves information on a game server group.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.describe_game_server_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#describe_game_server_group)
         """
     async def describe_game_server_instances(
         self,
         *,
         GameServerGroupName: str,
         InstanceIds: Sequence[str] = ...,
         Limit: int = ...,
         NextToken: str = ...
     ) -> DescribeGameServerInstancesOutputTypeDef:
         """
-        **This operation is used with the GameLift FleetIQ solution and game server
-        groups.** Retrieves status information about the Amazon EC2 instances associated
-        with a GameLift FleetIQ game server group.
+        **This operation is used with the Amazon GameLift FleetIQ solution and game
+        server groups.** Retrieves status information about the Amazon EC2 instances
+        associated with a Amazon GameLift FleetIQ game server group.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.describe_game_server_instances)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#describe_game_server_instances)
         """
     async def describe_game_session_details(
         self,
         *,
@@ -964,24 +971,25 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.get_compute_access)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#get_compute_access)
         """
     async def get_compute_auth_token(
         self, *, FleetId: str, ComputeName: str
     ) -> GetComputeAuthTokenOutputTypeDef:
         """
-        Requests an authorization token from GameLift.
+        Requests an authentication token from Amazon GameLift.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.get_compute_auth_token)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#get_compute_auth_token)
         """
     async def get_game_session_log_url(
         self, *, GameSessionId: str
     ) -> GetGameSessionLogUrlOutputTypeDef:
         """
-        Retrieves the location of stored game session logs for a specified game session.
+        Retrieves the location of stored game session logs for a specified game session
+        on Amazon GameLift managed fleets.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.get_game_session_log_url)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#get_game_session_log_url)
         """
     async def get_instance_access(
         self, *, FleetId: str, InstanceId: str
     ) -> GetInstanceAccessOutputTypeDef:
@@ -1048,17 +1056,17 @@
         *,
         GameServerGroupName: str,
         SortOrder: SortOrderType = ...,
         Limit: int = ...,
         NextToken: str = ...
     ) -> ListGameServersOutputTypeDef:
         """
-        **This operation is used with the GameLift FleetIQ solution and game server
-        groups.** Retrieves information on all game servers that are currently active in
-        a specified game server group.
+        **This operation is used with the Amazon GameLift FleetIQ solution and game
+        server groups.** Retrieves information on all game servers that are currently
+        active in a specified game server group.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.list_game_servers)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#list_game_servers)
         """
     async def list_locations(
         self, *, Filters: Sequence[LocationFilterType] = ..., Limit: int = ..., NextToken: str = ...
     ) -> ListLocationsOutputTypeDef:
@@ -1078,15 +1086,15 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.list_scripts)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#list_scripts)
         """
     async def list_tags_for_resource(
         self, *, ResourceARN: str
     ) -> ListTagsForResourceResponseTypeDef:
         """
-        Retrieves all tags that are assigned to a GameLift resource.
+        Retrieves all tags assigned to a Amazon GameLift resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.list_tags_for_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#list_tags_for_resource)
         """
     async def put_scaling_policy(
         self,
         *,
@@ -1129,17 +1137,17 @@
         GameServerGroupName: str,
         GameServerId: str,
         InstanceId: str,
         ConnectionInfo: str = ...,
         GameServerData: str = ...
     ) -> RegisterGameServerOutputTypeDef:
         """
-        **This operation is used with the GameLift FleetIQ solution and game server
-        groups.** Creates a new game server resource and notifies GameLift FleetIQ that
-        the game server is ready to host gameplay and players.
+        **This operation is used with the Amazon GameLift FleetIQ solution and game
+        server groups.** Creates a new game server resource and notifies Amazon GameLift
+        FleetIQ that the game server is ready to host gameplay and players.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.register_game_server)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#register_game_server)
         """
     async def request_upload_credentials(
         self, *, BuildId: str
     ) -> RequestUploadCredentialsOutputTypeDef:
@@ -1160,16 +1168,16 @@
     async def resume_game_server_group(
         self,
         *,
         GameServerGroupName: str,
         ResumeActions: Sequence[Literal["REPLACE_INSTANCE_TYPES"]]
     ) -> ResumeGameServerGroupOutputTypeDef:
         """
-        **This operation is used with the GameLift FleetIQ solution and game server
-        groups.** Reinstates activity on a game server group after it has been
+        **This operation is used with the Amazon GameLift FleetIQ solution and game
+        server groups.** Reinstates activity on a game server group after it has been
         suspended.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.resume_game_server_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#resume_game_server_group)
         """
     async def search_game_sessions(
         self,
@@ -1270,31 +1278,31 @@
     async def suspend_game_server_group(
         self,
         *,
         GameServerGroupName: str,
         SuspendActions: Sequence[Literal["REPLACE_INSTANCE_TYPES"]]
     ) -> SuspendGameServerGroupOutputTypeDef:
         """
-        **This operation is used with the GameLift FleetIQ solution and game server
-        groups.** Temporarily stops activity on a game server group without terminating
-        instances or the game server group.
+        **This operation is used with the Amazon GameLift FleetIQ solution and game
+        server groups.** Temporarily stops activity on a game server group without
+        terminating instances or the game server group.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.suspend_game_server_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#suspend_game_server_group)
         """
     async def tag_resource(self, *, ResourceARN: str, Tags: Sequence[TagTypeDef]) -> Dict[str, Any]:
         """
-        Assigns a tag to a GameLift resource.
+        Assigns a tag to an Amazon GameLift resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.tag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#tag_resource)
         """
     async def untag_resource(self, *, ResourceARN: str, TagKeys: Sequence[str]) -> Dict[str, Any]:
         """
-        Removes a tag that is assigned to a GameLift resource.
+        Removes a tag assigned to a Amazon GameLift resource.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.untag_resource)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#untag_resource)
         """
     async def update_alias(
         self,
         *,
@@ -1371,33 +1379,34 @@
         GameServerGroupName: str,
         GameServerId: str,
         GameServerData: str = ...,
         UtilizationStatus: GameServerUtilizationStatusType = ...,
         HealthCheck: Literal["HEALTHY"] = ...
     ) -> UpdateGameServerOutputTypeDef:
         """
-        **This operation is used with the GameLift FleetIQ solution and game server
-        groups.** Updates information about a registered game server to help GameLift
-        FleetIQ to track game server availability.
+        **This operation is used with the Amazon GameLift FleetIQ solution and game
+        server groups.** Updates information about a registered game server to help
+        Amazon GameLift FleetIQ to track game server availability.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.update_game_server)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#update_game_server)
         """
     async def update_game_server_group(
         self,
         *,
         GameServerGroupName: str,
         RoleArn: str = ...,
         InstanceDefinitions: Sequence[InstanceDefinitionTypeDef] = ...,
         GameServerProtectionPolicy: GameServerProtectionPolicyType = ...,
         BalancingStrategy: BalancingStrategyType = ...
     ) -> UpdateGameServerGroupOutputTypeDef:
         """
-        **This operation is used with the GameLift FleetIQ solution and game server
-        groups.** Updates GameLift FleetIQ-specific properties for a game server group.
+        **This operation is used with the Amazon GameLift FleetIQ solution and game
+        server groups.** Updates Amazon GameLift FleetIQ-specific properties for a game
+        server group.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.update_game_server_group)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#update_game_server_group)
         """
     async def update_game_session(
         self,
         *,
@@ -1457,15 +1466,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#update_matchmaking_configuration)
         """
     async def update_runtime_configuration(
         self, *, FleetId: str, RuntimeConfiguration: RuntimeConfigurationTypeDef
     ) -> UpdateRuntimeConfigurationOutputTypeDef:
         """
         Updates the current runtime configuration for the specified fleet, which tells
-        GameLift how to launch server processes on all instances in the fleet.
+        Amazon GameLift how to launch server processes on all instances in the fleet.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Client.update_runtime_configuration)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/client/#update_runtime_configuration)
         """
     async def update_script(
         self,
         *,
```

### Comparing `types-aiobotocore-gamelift-2.5.0.post1/types_aiobotocore_gamelift/literals.py` & `types-aiobotocore-gamelift-2.5.1/types_aiobotocore_gamelift/literals.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -14,15 +14,14 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "AcceptanceTypeType",
     "BackfillModeType",
     "BalancingStrategyType",
     "BuildStatusType",
     "CertificateTypeType",
     "ComparisonOperatorTypeType",
@@ -39,14 +38,15 @@
     "DescribeInstancesPaginatorName",
     "DescribeMatchmakingConfigurationsPaginatorName",
     "DescribeMatchmakingRuleSetsPaginatorName",
     "DescribePlayerSessionsPaginatorName",
     "DescribeScalingPoliciesPaginatorName",
     "EC2InstanceTypeType",
     "EventCodeType",
+    "FilterInstanceStatusType",
     "FleetActionType",
     "FleetStatusType",
     "FleetTypeType",
     "FlexMatchModeType",
     "GameServerClaimStatusType",
     "GameServerGroupActionType",
     "GameServerGroupDeleteOptionType",
@@ -87,15 +87,14 @@
     "GameLiftServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
-
 AcceptanceTypeType = Literal["ACCEPT", "REJECT"]
 BackfillModeType = Literal["AUTOMATIC", "MANUAL"]
 BalancingStrategyType = Literal["ON_DEMAND_ONLY", "SPOT_ONLY", "SPOT_PREFERRED"]
 BuildStatusType = Literal["FAILED", "INITIALIZED", "READY"]
 CertificateTypeType = Literal["DISABLED", "GENERATED"]
 ComparisonOperatorTypeType = Literal[
     "GreaterThanOrEqualToThreshold",
@@ -266,14 +265,15 @@
     "SERVER_PROCESS_FORCE_TERMINATED",
     "SERVER_PROCESS_INVALID_PATH",
     "SERVER_PROCESS_PROCESS_EXIT_TIMEOUT",
     "SERVER_PROCESS_PROCESS_READY_TIMEOUT",
     "SERVER_PROCESS_SDK_INITIALIZATION_TIMEOUT",
     "SERVER_PROCESS_TERMINATED_UNHEALTHY",
 ]
+FilterInstanceStatusType = Literal["ACTIVE", "DRAINING"]
 FleetActionType = Literal["AUTO_SCALING"]
 FleetStatusType = Literal[
     "ACTIVATING",
     "ACTIVE",
     "BUILDING",
     "DELETING",
     "DOWNLOADING",
@@ -420,15 +420,15 @@
     "CurrentPlayerSessions",
     "IdleInstances",
     "PercentAvailableGameSessions",
     "PercentIdleInstances",
     "QueueDepth",
     "WaitTime",
 ]
-OperatingSystemType = Literal["AMAZON_LINUX", "AMAZON_LINUX_2", "WINDOWS_2012"]
+OperatingSystemType = Literal["AMAZON_LINUX", "AMAZON_LINUX_2", "WINDOWS_2012", "WINDOWS_2016"]
 PlayerSessionCreationPolicyType = Literal["ACCEPT_ALL", "DENY_ALL"]
 PlayerSessionStatusType = Literal["ACTIVE", "COMPLETED", "RESERVED", "TIMEDOUT"]
 PolicyTypeType = Literal["RuleBased", "TargetBased"]
 PriorityTypeType = Literal["COST", "DESTINATION", "LATENCY", "LOCATION"]
 ProtectionPolicyType = Literal["FullProtection", "NoProtection"]
 RoutingStrategyTypeType = Literal["SIMPLE", "TERMINAL"]
 ScalingAdjustmentTypeType = Literal["ChangeInCapacity", "ExactCapacity", "PercentChangeInCapacity"]
@@ -496,14 +496,15 @@
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
@@ -582,14 +583,15 @@
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
@@ -600,14 +602,15 @@
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
@@ -643,14 +646,15 @@
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
@@ -669,16 +673,19 @@
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
@@ -762,15 +769,17 @@
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

### Comparing `types-aiobotocore-gamelift-2.5.0.post1/types_aiobotocore_gamelift/literals.pyi` & `types-aiobotocore-gamelift-2.5.1/types_aiobotocore_gamelift/literals.py`

 * *Files 0% similar despite different names*

```diff
@@ -14,14 +14,15 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "AcceptanceTypeType",
     "BackfillModeType",
     "BalancingStrategyType",
     "BuildStatusType",
     "CertificateTypeType",
     "ComparisonOperatorTypeType",
@@ -38,14 +39,15 @@
     "DescribeInstancesPaginatorName",
     "DescribeMatchmakingConfigurationsPaginatorName",
     "DescribeMatchmakingRuleSetsPaginatorName",
     "DescribePlayerSessionsPaginatorName",
     "DescribeScalingPoliciesPaginatorName",
     "EC2InstanceTypeType",
     "EventCodeType",
+    "FilterInstanceStatusType",
     "FleetActionType",
     "FleetStatusType",
     "FleetTypeType",
     "FlexMatchModeType",
     "GameServerClaimStatusType",
     "GameServerGroupActionType",
     "GameServerGroupDeleteOptionType",
@@ -86,14 +88,15 @@
     "GameLiftServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
     "RegionName",
 )
 
+
 AcceptanceTypeType = Literal["ACCEPT", "REJECT"]
 BackfillModeType = Literal["AUTOMATIC", "MANUAL"]
 BalancingStrategyType = Literal["ON_DEMAND_ONLY", "SPOT_ONLY", "SPOT_PREFERRED"]
 BuildStatusType = Literal["FAILED", "INITIALIZED", "READY"]
 CertificateTypeType = Literal["DISABLED", "GENERATED"]
 ComparisonOperatorTypeType = Literal[
     "GreaterThanOrEqualToThreshold",
@@ -264,14 +267,15 @@
     "SERVER_PROCESS_FORCE_TERMINATED",
     "SERVER_PROCESS_INVALID_PATH",
     "SERVER_PROCESS_PROCESS_EXIT_TIMEOUT",
     "SERVER_PROCESS_PROCESS_READY_TIMEOUT",
     "SERVER_PROCESS_SDK_INITIALIZATION_TIMEOUT",
     "SERVER_PROCESS_TERMINATED_UNHEALTHY",
 ]
+FilterInstanceStatusType = Literal["ACTIVE", "DRAINING"]
 FleetActionType = Literal["AUTO_SCALING"]
 FleetStatusType = Literal[
     "ACTIVATING",
     "ACTIVE",
     "BUILDING",
     "DELETING",
     "DOWNLOADING",
@@ -418,15 +422,15 @@
     "CurrentPlayerSessions",
     "IdleInstances",
     "PercentAvailableGameSessions",
     "PercentIdleInstances",
     "QueueDepth",
     "WaitTime",
 ]
-OperatingSystemType = Literal["AMAZON_LINUX", "AMAZON_LINUX_2", "WINDOWS_2012"]
+OperatingSystemType = Literal["AMAZON_LINUX", "AMAZON_LINUX_2", "WINDOWS_2012", "WINDOWS_2016"]
 PlayerSessionCreationPolicyType = Literal["ACCEPT_ALL", "DENY_ALL"]
 PlayerSessionStatusType = Literal["ACTIVE", "COMPLETED", "RESERVED", "TIMEDOUT"]
 PolicyTypeType = Literal["RuleBased", "TargetBased"]
 PriorityTypeType = Literal["COST", "DESTINATION", "LATENCY", "LOCATION"]
 ProtectionPolicyType = Literal["FullProtection", "NoProtection"]
 RoutingStrategyTypeType = Literal["SIMPLE", "TERMINAL"]
 ScalingAdjustmentTypeType = Literal["ChangeInCapacity", "ExactCapacity", "PercentChangeInCapacity"]
@@ -494,14 +498,15 @@
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
@@ -580,14 +585,15 @@
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
@@ -598,14 +604,15 @@
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
@@ -641,14 +648,15 @@
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
@@ -667,16 +675,19 @@
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
@@ -760,15 +771,17 @@
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

### Comparing `types-aiobotocore-gamelift-2.5.0.post1/types_aiobotocore_gamelift/paginator.py` & `types-aiobotocore-gamelift-2.5.1/types_aiobotocore_gamelift/paginator.py`

 * *Files 6% similar despite different names*

```diff
@@ -58,17 +58,16 @@
         list_game_server_groups_paginator: ListGameServerGroupsPaginator = client.get_paginator("list_game_server_groups")
         list_game_servers_paginator: ListGameServersPaginator = client.get_paginator("list_game_servers")
         list_locations_paginator: ListLocationsPaginator = client.get_paginator("list_locations")
         list_scripts_paginator: ListScriptsPaginator = client.get_paginator("list_scripts")
         search_game_sessions_paginator: SearchGameSessionsPaginator = client.get_paginator("search_game_sessions")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, Sequence, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     BuildStatusType,
     LocationFilterType,
@@ -98,20 +97,14 @@
     ListGameServersOutputTypeDef,
     ListLocationsOutputTypeDef,
     ListScriptsOutputTypeDef,
     PaginatorConfigTypeDef,
     SearchGameSessionsOutputTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "DescribeFleetAttributesPaginator",
     "DescribeFleetCapacityPaginator",
     "DescribeFleetEventsPaginator",
     "DescribeFleetUtilizationPaginator",
     "DescribeGameServerInstancesPaginator",
     "DescribeGameSessionDetailsPaginator",
@@ -147,30 +140,30 @@
 class DescribeFleetAttributesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeFleetAttributes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#describefleetattributespaginator)
     """
 
     def paginate(
-        self, *, FleetIds: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, FleetIds: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeFleetAttributesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeFleetAttributes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#describefleetattributespaginator)
         """
 
 
 class DescribeFleetCapacityPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeFleetCapacity)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#describefleetcapacitypaginator)
     """
 
     def paginate(
-        self, *, FleetIds: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, FleetIds: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeFleetCapacityOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeFleetCapacity.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#describefleetcapacitypaginator)
         """
 
 
@@ -182,30 +175,30 @@
 
     def paginate(
         self,
         *,
         FleetId: str,
         StartTime: Union[datetime, str] = ...,
         EndTime: Union[datetime, str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeFleetEventsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeFleetEvents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#describefleeteventspaginator)
         """
 
 
 class DescribeFleetUtilizationPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeFleetUtilization)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#describefleetutilizationpaginator)
     """
 
     def paginate(
-        self, *, FleetIds: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, FleetIds: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeFleetUtilizationOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeFleetUtilization.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#describefleetutilizationpaginator)
         """
 
 
@@ -216,15 +209,15 @@
     """
 
     def paginate(
         self,
         *,
         GameServerGroupName: str,
         InstanceIds: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeGameServerInstancesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeGameServerInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#describegameserverinstancespaginator)
         """
 
 
@@ -238,30 +231,30 @@
         self,
         *,
         FleetId: str = ...,
         GameSessionId: str = ...,
         AliasId: str = ...,
         Location: str = ...,
         StatusFilter: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeGameSessionDetailsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeGameSessionDetails.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#describegamesessiondetailspaginator)
         """
 
 
 class DescribeGameSessionQueuesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeGameSessionQueues)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#describegamesessionqueuespaginator)
     """
 
     def paginate(
-        self, *, Names: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Names: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeGameSessionQueuesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeGameSessionQueues.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#describegamesessionqueuespaginator)
         """
 
 
@@ -275,15 +268,15 @@
         self,
         *,
         FleetId: str = ...,
         GameSessionId: str = ...,
         AliasId: str = ...,
         Location: str = ...,
         StatusFilter: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeGameSessionsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeGameSessions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#describegamesessionspaginator)
         """
 
 
@@ -295,15 +288,15 @@
 
     def paginate(
         self,
         *,
         FleetId: str,
         InstanceId: str = ...,
         Location: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeInstancesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#describeinstancespaginator)
         """
 
 
@@ -314,30 +307,30 @@
     """
 
     def paginate(
         self,
         *,
         Names: Sequence[str] = ...,
         RuleSetName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeMatchmakingConfigurationsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeMatchmakingConfigurations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#describematchmakingconfigurationspaginator)
         """
 
 
 class DescribeMatchmakingRuleSetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeMatchmakingRuleSets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#describematchmakingrulesetspaginator)
     """
 
     def paginate(
-        self, *, Names: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Names: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeMatchmakingRuleSetsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeMatchmakingRuleSets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#describematchmakingrulesetspaginator)
         """
 
 
@@ -350,15 +343,15 @@
     def paginate(
         self,
         *,
         GameSessionId: str = ...,
         PlayerId: str = ...,
         PlayerSessionId: str = ...,
         PlayerSessionStatusFilter: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribePlayerSessionsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribePlayerSessions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#describeplayersessionspaginator)
         """
 
 
@@ -370,15 +363,15 @@
 
     def paginate(
         self,
         *,
         FleetId: str,
         StatusFilter: ScalingStatusTypeType = ...,
         Location: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeScalingPoliciesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeScalingPolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#describescalingpoliciespaginator)
         """
 
 
@@ -389,45 +382,45 @@
     """
 
     def paginate(
         self,
         *,
         RoutingStrategyType: RoutingStrategyTypeType = ...,
         Name: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAliasesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.ListAliases.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#listaliasespaginator)
         """
 
 
 class ListBuildsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.ListBuilds)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#listbuildspaginator)
     """
 
     def paginate(
-        self, *, Status: BuildStatusType = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Status: BuildStatusType = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBuildsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.ListBuilds.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#listbuildspaginator)
         """
 
 
 class ListComputePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.ListCompute)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#listcomputepaginator)
     """
 
     def paginate(
-        self, *, FleetId: str, Location: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, FleetId: str, Location: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListComputeOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.ListCompute.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#listcomputepaginator)
         """
 
 
@@ -438,30 +431,30 @@
     """
 
     def paginate(
         self,
         *,
         BuildId: str = ...,
         ScriptId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFleetsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.ListFleets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#listfleetspaginator)
         """
 
 
 class ListGameServerGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.ListGameServerGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#listgameservergroupspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGameServerGroupsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.ListGameServerGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#listgameservergroupspaginator)
         """
 
 
@@ -472,15 +465,15 @@
     """
 
     def paginate(
         self,
         *,
         GameServerGroupName: str,
         SortOrder: SortOrderType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGameServersOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.ListGameServers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#listgameserverspaginator)
         """
 
 
@@ -490,30 +483,30 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#listlocationspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[LocationFilterType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListLocationsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.ListLocations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#listlocationspaginator)
         """
 
 
 class ListScriptsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.ListScripts)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#listscriptspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListScriptsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.ListScripts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#listscriptspaginator)
         """
 
 
@@ -527,13 +520,13 @@
         self,
         *,
         FleetId: str = ...,
         AliasId: str = ...,
         Location: str = ...,
         FilterExpression: str = ...,
         SortExpression: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SearchGameSessionsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.SearchGameSessions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#searchgamesessionspaginator)
         """
```

### Comparing `types-aiobotocore-gamelift-2.5.0.post1/types_aiobotocore_gamelift/paginator.pyi` & `types-aiobotocore-gamelift-2.5.1/types_aiobotocore_gamelift/paginator.pyi`

 * *Files 8% similar despite different names*

```diff
@@ -58,17 +58,16 @@
         list_game_server_groups_paginator: ListGameServerGroupsPaginator = client.get_paginator("list_game_server_groups")
         list_game_servers_paginator: ListGameServersPaginator = client.get_paginator("list_game_servers")
         list_locations_paginator: ListLocationsPaginator = client.get_paginator("list_locations")
         list_scripts_paginator: ListScriptsPaginator = client.get_paginator("list_scripts")
         search_game_sessions_paginator: SearchGameSessionsPaginator = client.get_paginator("search_game_sessions")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, Sequence, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     BuildStatusType,
     LocationFilterType,
@@ -98,19 +97,14 @@
     ListGameServersOutputTypeDef,
     ListLocationsOutputTypeDef,
     ListScriptsOutputTypeDef,
     PaginatorConfigTypeDef,
     SearchGameSessionsOutputTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "DescribeFleetAttributesPaginator",
     "DescribeFleetCapacityPaginator",
     "DescribeFleetEventsPaginator",
     "DescribeFleetUtilizationPaginator",
     "DescribeGameServerInstancesPaginator",
     "DescribeGameSessionDetailsPaginator",
@@ -143,29 +137,29 @@
 class DescribeFleetAttributesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeFleetAttributes)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#describefleetattributespaginator)
     """
 
     def paginate(
-        self, *, FleetIds: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, FleetIds: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeFleetAttributesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeFleetAttributes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#describefleetattributespaginator)
         """
 
 class DescribeFleetCapacityPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeFleetCapacity)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#describefleetcapacitypaginator)
     """
 
     def paginate(
-        self, *, FleetIds: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, FleetIds: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeFleetCapacityOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeFleetCapacity.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#describefleetcapacitypaginator)
         """
 
 class DescribeFleetEventsPaginator(AioPaginator):
@@ -176,29 +170,29 @@
 
     def paginate(
         self,
         *,
         FleetId: str,
         StartTime: Union[datetime, str] = ...,
         EndTime: Union[datetime, str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeFleetEventsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeFleetEvents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#describefleeteventspaginator)
         """
 
 class DescribeFleetUtilizationPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeFleetUtilization)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#describefleetutilizationpaginator)
     """
 
     def paginate(
-        self, *, FleetIds: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, FleetIds: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeFleetUtilizationOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeFleetUtilization.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#describefleetutilizationpaginator)
         """
 
 class DescribeGameServerInstancesPaginator(AioPaginator):
@@ -208,15 +202,15 @@
     """
 
     def paginate(
         self,
         *,
         GameServerGroupName: str,
         InstanceIds: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeGameServerInstancesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeGameServerInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#describegameserverinstancespaginator)
         """
 
 class DescribeGameSessionDetailsPaginator(AioPaginator):
@@ -229,29 +223,29 @@
         self,
         *,
         FleetId: str = ...,
         GameSessionId: str = ...,
         AliasId: str = ...,
         Location: str = ...,
         StatusFilter: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeGameSessionDetailsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeGameSessionDetails.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#describegamesessiondetailspaginator)
         """
 
 class DescribeGameSessionQueuesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeGameSessionQueues)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#describegamesessionqueuespaginator)
     """
 
     def paginate(
-        self, *, Names: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Names: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeGameSessionQueuesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeGameSessionQueues.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#describegamesessionqueuespaginator)
         """
 
 class DescribeGameSessionsPaginator(AioPaginator):
@@ -264,15 +258,15 @@
         self,
         *,
         FleetId: str = ...,
         GameSessionId: str = ...,
         AliasId: str = ...,
         Location: str = ...,
         StatusFilter: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeGameSessionsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeGameSessions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#describegamesessionspaginator)
         """
 
 class DescribeInstancesPaginator(AioPaginator):
@@ -283,15 +277,15 @@
 
     def paginate(
         self,
         *,
         FleetId: str,
         InstanceId: str = ...,
         Location: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeInstancesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#describeinstancespaginator)
         """
 
 class DescribeMatchmakingConfigurationsPaginator(AioPaginator):
@@ -301,29 +295,29 @@
     """
 
     def paginate(
         self,
         *,
         Names: Sequence[str] = ...,
         RuleSetName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeMatchmakingConfigurationsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeMatchmakingConfigurations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#describematchmakingconfigurationspaginator)
         """
 
 class DescribeMatchmakingRuleSetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeMatchmakingRuleSets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#describematchmakingrulesetspaginator)
     """
 
     def paginate(
-        self, *, Names: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Names: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeMatchmakingRuleSetsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeMatchmakingRuleSets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#describematchmakingrulesetspaginator)
         """
 
 class DescribePlayerSessionsPaginator(AioPaginator):
@@ -335,15 +329,15 @@
     def paginate(
         self,
         *,
         GameSessionId: str = ...,
         PlayerId: str = ...,
         PlayerSessionId: str = ...,
         PlayerSessionStatusFilter: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribePlayerSessionsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribePlayerSessions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#describeplayersessionspaginator)
         """
 
 class DescribeScalingPoliciesPaginator(AioPaginator):
@@ -354,15 +348,15 @@
 
     def paginate(
         self,
         *,
         FleetId: str,
         StatusFilter: ScalingStatusTypeType = ...,
         Location: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeScalingPoliciesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.DescribeScalingPolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#describescalingpoliciespaginator)
         """
 
 class ListAliasesPaginator(AioPaginator):
@@ -372,43 +366,43 @@
     """
 
     def paginate(
         self,
         *,
         RoutingStrategyType: RoutingStrategyTypeType = ...,
         Name: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAliasesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.ListAliases.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#listaliasespaginator)
         """
 
 class ListBuildsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.ListBuilds)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#listbuildspaginator)
     """
 
     def paginate(
-        self, *, Status: BuildStatusType = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, Status: BuildStatusType = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListBuildsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.ListBuilds.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#listbuildspaginator)
         """
 
 class ListComputePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.ListCompute)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#listcomputepaginator)
     """
 
     def paginate(
-        self, *, FleetId: str, Location: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, FleetId: str, Location: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListComputeOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.ListCompute.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#listcomputepaginator)
         """
 
 class ListFleetsPaginator(AioPaginator):
@@ -418,29 +412,29 @@
     """
 
     def paginate(
         self,
         *,
         BuildId: str = ...,
         ScriptId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListFleetsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.ListFleets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#listfleetspaginator)
         """
 
 class ListGameServerGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.ListGameServerGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#listgameservergroupspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGameServerGroupsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.ListGameServerGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#listgameservergroupspaginator)
         """
 
 class ListGameServersPaginator(AioPaginator):
@@ -450,15 +444,15 @@
     """
 
     def paginate(
         self,
         *,
         GameServerGroupName: str,
         SortOrder: SortOrderType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGameServersOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.ListGameServers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#listgameserverspaginator)
         """
 
 class ListLocationsPaginator(AioPaginator):
@@ -467,29 +461,29 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#listlocationspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[LocationFilterType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListLocationsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.ListLocations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#listlocationspaginator)
         """
 
 class ListScriptsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.ListScripts)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#listscriptspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListScriptsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.ListScripts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#listscriptspaginator)
         """
 
 class SearchGameSessionsPaginator(AioPaginator):
@@ -502,13 +496,13 @@
         self,
         *,
         FleetId: str = ...,
         AliasId: str = ...,
         Location: str = ...,
         FilterExpression: str = ...,
         SortExpression: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[SearchGameSessionsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift.Paginator.SearchGameSessions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/paginators/#searchgamesessionspaginator)
         """
```

### Comparing `types-aiobotocore-gamelift-2.5.0.post1/types_aiobotocore_gamelift/type_defs.py` & `types-aiobotocore-gamelift-2.5.1/types_aiobotocore_gamelift/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -24,14 +24,15 @@
     BuildStatusType,
     CertificateTypeType,
     ComparisonOperatorTypeType,
     ComputeStatusType,
     ComputeTypeType,
     EC2InstanceTypeType,
     EventCodeType,
+    FilterInstanceStatusType,
     FleetStatusType,
     FleetTypeType,
     FlexMatchModeType,
     GameServerGroupDeleteOptionType,
     GameServerGroupInstanceTypeType,
     GameServerGroupStatusType,
     GameServerInstanceStatusType,
@@ -61,26 +62,24 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
-
 __all__ = (
     "AcceptMatchInputRequestTypeDef",
     "RoutingStrategyTypeDef",
     "AnywhereConfigurationTypeDef",
     "AttributeValueTypeDef",
     "AwsCredentialsTypeDef",
     "BuildTypeDef",
     "CertificateConfigurationTypeDef",
-    "ClaimGameServerInputRequestTypeDef",
+    "ClaimFilterOptionTypeDef",
     "GameServerTypeDef",
-    "ResponseMetadataTypeDef",
     "ComputeTypeDef",
     "TagTypeDef",
     "S3LocationTypeDef",
     "IpPermissionTypeDef",
     "LocationConfigurationTypeDef",
     "ResourceCreationLimitPolicyTypeDef",
     "LocationStateTypeDef",
@@ -115,107 +114,131 @@
     "DeregisterComputeInputRequestTypeDef",
     "DeregisterGameServerInputRequestTypeDef",
     "DescribeAliasInputRequestTypeDef",
     "DescribeBuildInputRequestTypeDef",
     "DescribeComputeInputRequestTypeDef",
     "DescribeEC2InstanceLimitsInputRequestTypeDef",
     "EC2InstanceLimitTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeFleetAttributesInputDescribeFleetAttributesPaginateTypeDef",
     "DescribeFleetAttributesInputRequestTypeDef",
+    "DescribeFleetCapacityInputDescribeFleetCapacityPaginateTypeDef",
     "DescribeFleetCapacityInputRequestTypeDef",
+    "DescribeFleetEventsInputDescribeFleetEventsPaginateTypeDef",
     "DescribeFleetEventsInputRequestTypeDef",
     "EventTypeDef",
     "DescribeFleetLocationAttributesInputRequestTypeDef",
     "DescribeFleetLocationCapacityInputRequestTypeDef",
     "DescribeFleetLocationUtilizationInputRequestTypeDef",
     "FleetUtilizationTypeDef",
     "DescribeFleetPortSettingsInputRequestTypeDef",
+    "DescribeFleetUtilizationInputDescribeFleetUtilizationPaginateTypeDef",
     "DescribeFleetUtilizationInputRequestTypeDef",
     "DescribeGameServerGroupInputRequestTypeDef",
     "DescribeGameServerInputRequestTypeDef",
+    "DescribeGameServerInstancesInputDescribeGameServerInstancesPaginateTypeDef",
     "DescribeGameServerInstancesInputRequestTypeDef",
     "GameServerInstanceTypeDef",
+    "DescribeGameSessionDetailsInputDescribeGameSessionDetailsPaginateTypeDef",
     "DescribeGameSessionDetailsInputRequestTypeDef",
     "DescribeGameSessionPlacementInputRequestTypeDef",
+    "DescribeGameSessionQueuesInputDescribeGameSessionQueuesPaginateTypeDef",
     "DescribeGameSessionQueuesInputRequestTypeDef",
+    "DescribeGameSessionsInputDescribeGameSessionsPaginateTypeDef",
     "DescribeGameSessionsInputRequestTypeDef",
+    "DescribeInstancesInputDescribeInstancesPaginateTypeDef",
     "DescribeInstancesInputRequestTypeDef",
     "InstanceTypeDef",
+    "DescribeMatchmakingConfigurationsInputDescribeMatchmakingConfigurationsPaginateTypeDef",
     "DescribeMatchmakingConfigurationsInputRequestTypeDef",
     "DescribeMatchmakingInputRequestTypeDef",
+    "DescribeMatchmakingRuleSetsInputDescribeMatchmakingRuleSetsPaginateTypeDef",
     "DescribeMatchmakingRuleSetsInputRequestTypeDef",
+    "DescribePlayerSessionsInputDescribePlayerSessionsPaginateTypeDef",
     "DescribePlayerSessionsInputRequestTypeDef",
     "DescribeRuntimeConfigurationInputRequestTypeDef",
+    "DescribeScalingPoliciesInputDescribeScalingPoliciesPaginateTypeDef",
     "DescribeScalingPoliciesInputRequestTypeDef",
     "DescribeScriptInputRequestTypeDef",
     "DescribeVpcPeeringConnectionsInputRequestTypeDef",
     "DesiredPlayerSessionTypeDef",
     "EC2InstanceCountsTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "TargetTrackingConfigurationTypeDef",
     "MatchedPlayerSessionTypeDef",
     "PlacedPlayerSessionTypeDef",
     "PlayerLatencyTypeDef",
     "GetComputeAccessInputRequestTypeDef",
     "GetComputeAuthTokenInputRequestTypeDef",
+    "GetComputeAuthTokenOutputTypeDef",
     "GetGameSessionLogUrlInputRequestTypeDef",
+    "GetGameSessionLogUrlOutputTypeDef",
     "GetInstanceAccessInputRequestTypeDef",
     "InstanceCredentialsTypeDef",
+    "ListAliasesInputListAliasesPaginateTypeDef",
     "ListAliasesInputRequestTypeDef",
+    "ListBuildsInputListBuildsPaginateTypeDef",
     "ListBuildsInputRequestTypeDef",
+    "ListComputeInputListComputePaginateTypeDef",
     "ListComputeInputRequestTypeDef",
+    "ListFleetsInputListFleetsPaginateTypeDef",
     "ListFleetsInputRequestTypeDef",
+    "ListFleetsOutputTypeDef",
+    "ListGameServerGroupsInputListGameServerGroupsPaginateTypeDef",
     "ListGameServerGroupsInputRequestTypeDef",
+    "ListGameServersInputListGameServersPaginateTypeDef",
     "ListGameServersInputRequestTypeDef",
+    "ListLocationsInputListLocationsPaginateTypeDef",
     "ListLocationsInputRequestTypeDef",
+    "ListScriptsInputListScriptsPaginateTypeDef",
     "ListScriptsInputRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "TargetConfigurationTypeDef",
+    "PutScalingPolicyOutputTypeDef",
     "RegisterComputeInputRequestTypeDef",
     "RegisterGameServerInputRequestTypeDef",
     "RequestUploadCredentialsInputRequestTypeDef",
     "ResolveAliasInputRequestTypeDef",
+    "ResolveAliasOutputTypeDef",
+    "ResponseMetadataTypeDef",
     "ResumeGameServerGroupInputRequestTypeDef",
     "ServerProcessTypeDef",
     "SearchGameSessionsInputRequestTypeDef",
+    "SearchGameSessionsInputSearchGameSessionsPaginateTypeDef",
     "StartFleetActionsInputRequestTypeDef",
+    "StartFleetActionsOutputTypeDef",
     "StopFleetActionsInputRequestTypeDef",
+    "StopFleetActionsOutputTypeDef",
     "StopGameSessionPlacementInputRequestTypeDef",
     "StopMatchmakingInputRequestTypeDef",
     "SuspendGameServerGroupInputRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateBuildInputRequestTypeDef",
+    "UpdateFleetAttributesOutputTypeDef",
     "UpdateFleetCapacityInputRequestTypeDef",
+    "UpdateFleetCapacityOutputTypeDef",
+    "UpdateFleetPortSettingsOutputTypeDef",
     "UpdateGameServerInputRequestTypeDef",
     "UpdateGameSessionInputRequestTypeDef",
     "ValidateMatchmakingRuleSetInputRequestTypeDef",
+    "ValidateMatchmakingRuleSetOutputTypeDef",
     "VpcPeeringConnectionStatusTypeDef",
     "AliasTypeDef",
     "UpdateAliasInputRequestTypeDef",
     "PlayerTypeDef",
-    "ClaimGameServerOutputTypeDef",
-    "DescribeBuildOutputTypeDef",
-    "DescribeGameServerOutputTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "GetComputeAccessOutputTypeDef",
-    "GetComputeAuthTokenOutputTypeDef",
-    "GetGameSessionLogUrlOutputTypeDef",
+    "DescribeBuildOutputTypeDef",
     "ListBuildsOutputTypeDef",
-    "ListFleetsOutputTypeDef",
+    "UpdateBuildOutputTypeDef",
+    "ClaimGameServerInputRequestTypeDef",
+    "ClaimGameServerOutputTypeDef",
+    "DescribeGameServerOutputTypeDef",
     "ListGameServersOutputTypeDef",
-    "PutScalingPolicyOutputTypeDef",
     "RegisterGameServerOutputTypeDef",
-    "ResolveAliasOutputTypeDef",
-    "StartFleetActionsOutputTypeDef",
-    "StopFleetActionsOutputTypeDef",
-    "UpdateBuildOutputTypeDef",
-    "UpdateFleetAttributesOutputTypeDef",
-    "UpdateFleetCapacityOutputTypeDef",
-    "UpdateFleetPortSettingsOutputTypeDef",
     "UpdateGameServerOutputTypeDef",
-    "ValidateMatchmakingRuleSetOutputTypeDef",
     "DescribeComputeOutputTypeDef",
     "ListComputeOutputTypeDef",
     "RegisterComputeOutputTypeDef",
     "CreateAliasInputRequestTypeDef",
     "CreateLocationInputRequestTypeDef",
     "CreateMatchmakingRuleSetInputRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
@@ -250,36 +273,14 @@
     "DescribeMatchmakingRuleSetsOutputTypeDef",
     "CreatePlayerSessionOutputTypeDef",
     "CreatePlayerSessionsOutputTypeDef",
     "DescribePlayerSessionsOutputTypeDef",
     "CreateVpcPeeringAuthorizationOutputTypeDef",
     "DescribeVpcPeeringAuthorizationsOutputTypeDef",
     "DescribeEC2InstanceLimitsOutputTypeDef",
-    "DescribeFleetAttributesInputDescribeFleetAttributesPaginateTypeDef",
-    "DescribeFleetCapacityInputDescribeFleetCapacityPaginateTypeDef",
-    "DescribeFleetEventsInputDescribeFleetEventsPaginateTypeDef",
-    "DescribeFleetUtilizationInputDescribeFleetUtilizationPaginateTypeDef",
-    "DescribeGameServerInstancesInputDescribeGameServerInstancesPaginateTypeDef",
-    "DescribeGameSessionDetailsInputDescribeGameSessionDetailsPaginateTypeDef",
-    "DescribeGameSessionQueuesInputDescribeGameSessionQueuesPaginateTypeDef",
-    "DescribeGameSessionsInputDescribeGameSessionsPaginateTypeDef",
-    "DescribeInstancesInputDescribeInstancesPaginateTypeDef",
-    "DescribeMatchmakingConfigurationsInputDescribeMatchmakingConfigurationsPaginateTypeDef",
-    "DescribeMatchmakingRuleSetsInputDescribeMatchmakingRuleSetsPaginateTypeDef",
-    "DescribePlayerSessionsInputDescribePlayerSessionsPaginateTypeDef",
-    "DescribeScalingPoliciesInputDescribeScalingPoliciesPaginateTypeDef",
-    "ListAliasesInputListAliasesPaginateTypeDef",
-    "ListBuildsInputListBuildsPaginateTypeDef",
-    "ListComputeInputListComputePaginateTypeDef",
-    "ListFleetsInputListFleetsPaginateTypeDef",
-    "ListGameServerGroupsInputListGameServerGroupsPaginateTypeDef",
-    "ListGameServersInputListGameServersPaginateTypeDef",
-    "ListLocationsInputListLocationsPaginateTypeDef",
-    "ListScriptsInputListScriptsPaginateTypeDef",
-    "SearchGameSessionsInputSearchGameSessionsPaginateTypeDef",
     "DescribeFleetEventsOutputTypeDef",
     "DescribeFleetLocationUtilizationOutputTypeDef",
     "DescribeFleetUtilizationOutputTypeDef",
     "DescribeGameServerInstancesOutputTypeDef",
     "DescribeInstancesOutputTypeDef",
     "FleetCapacityTypeDef",
     "GameServerGroupAutoScalingPolicyTypeDef",
@@ -408,36 +409,22 @@
 CertificateConfigurationTypeDef = TypedDict(
     "CertificateConfigurationTypeDef",
     {
         "CertificateType": CertificateTypeType,
     },
 )
 
-_RequiredClaimGameServerInputRequestTypeDef = TypedDict(
-    "_RequiredClaimGameServerInputRequestTypeDef",
+ClaimFilterOptionTypeDef = TypedDict(
+    "ClaimFilterOptionTypeDef",
     {
-        "GameServerGroupName": str,
-    },
-)
-_OptionalClaimGameServerInputRequestTypeDef = TypedDict(
-    "_OptionalClaimGameServerInputRequestTypeDef",
-    {
-        "GameServerId": str,
-        "GameServerData": str,
+        "InstanceStatuses": Sequence[FilterInstanceStatusType],
     },
     total=False,
 )
 
-
-class ClaimGameServerInputRequestTypeDef(
-    _RequiredClaimGameServerInputRequestTypeDef, _OptionalClaimGameServerInputRequestTypeDef
-):
-    pass
-
-
 GameServerTypeDef = TypedDict(
     "GameServerTypeDef",
     {
         "GameServerGroupName": str,
         "GameServerGroupArn": str,
         "GameServerId": str,
         "InstanceId": str,
@@ -448,25 +435,14 @@
         "RegistrationTime": datetime,
         "LastClaimTime": datetime,
         "LastHealthCheckTime": datetime,
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
 ComputeTypeDef = TypedDict(
     "ComputeTypeDef",
     {
         "FleetId": str,
         "FleetArn": str,
         "ComputeName": str,
         "ComputeArn": str,
@@ -546,21 +522,19 @@
     "_OptionalInstanceDefinitionTypeDef",
     {
         "WeightedCapacity": str,
     },
     total=False,
 )
 
-
 class InstanceDefinitionTypeDef(
     _RequiredInstanceDefinitionTypeDef, _OptionalInstanceDefinitionTypeDef
 ):
     pass
 
-
 LaunchTemplateSpecificationTypeDef = TypedDict(
     "LaunchTemplateSpecificationTypeDef",
     {
         "LaunchTemplateId": str,
         "LaunchTemplateName": str,
         "Version": str,
     },
@@ -630,21 +604,19 @@
         "RuleSetName": str,
         "RuleSetArn": str,
         "CreationTime": datetime,
     },
     total=False,
 )
 
-
 class MatchmakingRuleSetTypeDef(
     _RequiredMatchmakingRuleSetTypeDef, _OptionalMatchmakingRuleSetTypeDef
 ):
     pass
 
-
 _RequiredCreatePlayerSessionInputRequestTypeDef = TypedDict(
     "_RequiredCreatePlayerSessionInputRequestTypeDef",
     {
         "GameSessionId": str,
         "PlayerId": str,
     },
 )
@@ -652,21 +624,19 @@
     "_OptionalCreatePlayerSessionInputRequestTypeDef",
     {
         "PlayerData": str,
     },
     total=False,
 )
 
-
 class CreatePlayerSessionInputRequestTypeDef(
     _RequiredCreatePlayerSessionInputRequestTypeDef, _OptionalCreatePlayerSessionInputRequestTypeDef
 ):
     pass
 
-
 PlayerSessionTypeDef = TypedDict(
     "PlayerSessionTypeDef",
     {
         "PlayerSessionId": str,
         "PlayerId": str,
         "GameSessionId": str,
         "FleetId": str,
@@ -693,22 +663,20 @@
     "_OptionalCreatePlayerSessionsInputRequestTypeDef",
     {
         "PlayerDataMap": Mapping[str, str],
     },
     total=False,
 )
 
-
 class CreatePlayerSessionsInputRequestTypeDef(
     _RequiredCreatePlayerSessionsInputRequestTypeDef,
     _OptionalCreatePlayerSessionsInputRequestTypeDef,
 ):
     pass
 
-
 CreateVpcPeeringAuthorizationInputRequestTypeDef = TypedDict(
     "CreateVpcPeeringAuthorizationInputRequestTypeDef",
     {
         "GameLiftAwsAccountId": str,
         "PeerVpcId": str,
     },
 )
@@ -773,22 +741,20 @@
     "_OptionalDeleteGameServerGroupInputRequestTypeDef",
     {
         "DeleteOption": GameServerGroupDeleteOptionType,
     },
     total=False,
 )
 
-
 class DeleteGameServerGroupInputRequestTypeDef(
     _RequiredDeleteGameServerGroupInputRequestTypeDef,
     _OptionalDeleteGameServerGroupInputRequestTypeDef,
 ):
     pass
 
-
 DeleteGameSessionQueueInputRequestTypeDef = TypedDict(
     "DeleteGameSessionQueueInputRequestTypeDef",
     {
         "Name": str,
     },
 )
 
@@ -898,44 +864,74 @@
         "CurrentInstances": int,
         "InstanceLimit": int,
         "Location": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeFleetAttributesInputDescribeFleetAttributesPaginateTypeDef = TypedDict(
+    "DescribeFleetAttributesInputDescribeFleetAttributesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "FleetIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeFleetAttributesInputRequestTypeDef = TypedDict(
     "DescribeFleetAttributesInputRequestTypeDef",
     {
         "FleetIds": Sequence[str],
         "Limit": int,
         "NextToken": str,
     },
     total=False,
 )
 
+DescribeFleetCapacityInputDescribeFleetCapacityPaginateTypeDef = TypedDict(
+    "DescribeFleetCapacityInputDescribeFleetCapacityPaginateTypeDef",
+    {
+        "FleetIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeFleetCapacityInputRequestTypeDef = TypedDict(
     "DescribeFleetCapacityInputRequestTypeDef",
     {
         "FleetIds": Sequence[str],
         "Limit": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredDescribeFleetEventsInputDescribeFleetEventsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeFleetEventsInputDescribeFleetEventsPaginateTypeDef",
+    {
+        "FleetId": str,
+    },
+)
+_OptionalDescribeFleetEventsInputDescribeFleetEventsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeFleetEventsInputDescribeFleetEventsPaginateTypeDef",
+    {
+        "StartTime": Union[datetime, str],
+        "EndTime": Union[datetime, str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeFleetEventsInputDescribeFleetEventsPaginateTypeDef(
+    _RequiredDescribeFleetEventsInputDescribeFleetEventsPaginateTypeDef,
+    _OptionalDescribeFleetEventsInputDescribeFleetEventsPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeFleetEventsInputRequestTypeDef = TypedDict(
     "_RequiredDescribeFleetEventsInputRequestTypeDef",
     {
         "FleetId": str,
     },
 )
 _OptionalDescribeFleetEventsInputRequestTypeDef = TypedDict(
@@ -945,21 +941,19 @@
         "EndTime": Union[datetime, str],
         "Limit": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class DescribeFleetEventsInputRequestTypeDef(
     _RequiredDescribeFleetEventsInputRequestTypeDef, _OptionalDescribeFleetEventsInputRequestTypeDef
 ):
     pass
 
-
 EventTypeDef = TypedDict(
     "EventTypeDef",
     {
         "EventId": str,
         "ResourceId": str,
         "EventCode": EventCodeType,
         "Message": str,
@@ -981,22 +975,20 @@
         "Locations": Sequence[str],
         "Limit": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class DescribeFleetLocationAttributesInputRequestTypeDef(
     _RequiredDescribeFleetLocationAttributesInputRequestTypeDef,
     _OptionalDescribeFleetLocationAttributesInputRequestTypeDef,
 ):
     pass
 
-
 DescribeFleetLocationCapacityInputRequestTypeDef = TypedDict(
     "DescribeFleetLocationCapacityInputRequestTypeDef",
     {
         "FleetId": str,
         "Location": str,
     },
 )
@@ -1033,21 +1025,28 @@
     "_OptionalDescribeFleetPortSettingsInputRequestTypeDef",
     {
         "Location": str,
     },
     total=False,
 )
 
-
 class DescribeFleetPortSettingsInputRequestTypeDef(
     _RequiredDescribeFleetPortSettingsInputRequestTypeDef,
     _OptionalDescribeFleetPortSettingsInputRequestTypeDef,
 ):
     pass
 
+DescribeFleetUtilizationInputDescribeFleetUtilizationPaginateTypeDef = TypedDict(
+    "DescribeFleetUtilizationInputDescribeFleetUtilizationPaginateTypeDef",
+    {
+        "FleetIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
 
 DescribeFleetUtilizationInputRequestTypeDef = TypedDict(
     "DescribeFleetUtilizationInputRequestTypeDef",
     {
         "FleetIds": Sequence[str],
         "Limit": int,
         "NextToken": str,
@@ -1066,14 +1065,35 @@
     "DescribeGameServerInputRequestTypeDef",
     {
         "GameServerGroupName": str,
         "GameServerId": str,
     },
 )
 
+_RequiredDescribeGameServerInstancesInputDescribeGameServerInstancesPaginateTypeDef = TypedDict(
+    "_RequiredDescribeGameServerInstancesInputDescribeGameServerInstancesPaginateTypeDef",
+    {
+        "GameServerGroupName": str,
+    },
+)
+_OptionalDescribeGameServerInstancesInputDescribeGameServerInstancesPaginateTypeDef = TypedDict(
+    "_OptionalDescribeGameServerInstancesInputDescribeGameServerInstancesPaginateTypeDef",
+    {
+        "InstanceIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeGameServerInstancesInputDescribeGameServerInstancesPaginateTypeDef(
+    _RequiredDescribeGameServerInstancesInputDescribeGameServerInstancesPaginateTypeDef,
+    _OptionalDescribeGameServerInstancesInputDescribeGameServerInstancesPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeGameServerInstancesInputRequestTypeDef = TypedDict(
     "_RequiredDescribeGameServerInstancesInputRequestTypeDef",
     {
         "GameServerGroupName": str,
     },
 )
 _OptionalDescribeGameServerInstancesInputRequestTypeDef = TypedDict(
@@ -1082,33 +1102,44 @@
         "InstanceIds": Sequence[str],
         "Limit": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class DescribeGameServerInstancesInputRequestTypeDef(
     _RequiredDescribeGameServerInstancesInputRequestTypeDef,
     _OptionalDescribeGameServerInstancesInputRequestTypeDef,
 ):
     pass
 
-
 GameServerInstanceTypeDef = TypedDict(
     "GameServerInstanceTypeDef",
     {
         "GameServerGroupName": str,
         "GameServerGroupArn": str,
         "InstanceId": str,
         "InstanceStatus": GameServerInstanceStatusType,
     },
     total=False,
 )
 
+DescribeGameSessionDetailsInputDescribeGameSessionDetailsPaginateTypeDef = TypedDict(
+    "DescribeGameSessionDetailsInputDescribeGameSessionDetailsPaginateTypeDef",
+    {
+        "FleetId": str,
+        "GameSessionId": str,
+        "AliasId": str,
+        "Location": str,
+        "StatusFilter": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeGameSessionDetailsInputRequestTypeDef = TypedDict(
     "DescribeGameSessionDetailsInputRequestTypeDef",
     {
         "FleetId": str,
         "GameSessionId": str,
         "AliasId": str,
         "Location": str,
@@ -1122,38 +1153,82 @@
 DescribeGameSessionPlacementInputRequestTypeDef = TypedDict(
     "DescribeGameSessionPlacementInputRequestTypeDef",
     {
         "PlacementId": str,
     },
 )
 
+DescribeGameSessionQueuesInputDescribeGameSessionQueuesPaginateTypeDef = TypedDict(
+    "DescribeGameSessionQueuesInputDescribeGameSessionQueuesPaginateTypeDef",
+    {
+        "Names": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeGameSessionQueuesInputRequestTypeDef = TypedDict(
     "DescribeGameSessionQueuesInputRequestTypeDef",
     {
         "Names": Sequence[str],
         "Limit": int,
         "NextToken": str,
     },
     total=False,
 )
 
+DescribeGameSessionsInputDescribeGameSessionsPaginateTypeDef = TypedDict(
+    "DescribeGameSessionsInputDescribeGameSessionsPaginateTypeDef",
+    {
+        "FleetId": str,
+        "GameSessionId": str,
+        "AliasId": str,
+        "Location": str,
+        "StatusFilter": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeGameSessionsInputRequestTypeDef = TypedDict(
     "DescribeGameSessionsInputRequestTypeDef",
     {
         "FleetId": str,
         "GameSessionId": str,
         "AliasId": str,
         "Location": str,
         "StatusFilter": str,
         "Limit": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredDescribeInstancesInputDescribeInstancesPaginateTypeDef = TypedDict(
+    "_RequiredDescribeInstancesInputDescribeInstancesPaginateTypeDef",
+    {
+        "FleetId": str,
+    },
+)
+_OptionalDescribeInstancesInputDescribeInstancesPaginateTypeDef = TypedDict(
+    "_OptionalDescribeInstancesInputDescribeInstancesPaginateTypeDef",
+    {
+        "InstanceId": str,
+        "Location": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeInstancesInputDescribeInstancesPaginateTypeDef(
+    _RequiredDescribeInstancesInputDescribeInstancesPaginateTypeDef,
+    _OptionalDescribeInstancesInputDescribeInstancesPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeInstancesInputRequestTypeDef = TypedDict(
     "_RequiredDescribeInstancesInputRequestTypeDef",
     {
         "FleetId": str,
     },
 )
 _OptionalDescribeInstancesInputRequestTypeDef = TypedDict(
@@ -1163,21 +1238,19 @@
         "Limit": int,
         "NextToken": str,
         "Location": str,
     },
     total=False,
 )
 
-
 class DescribeInstancesInputRequestTypeDef(
     _RequiredDescribeInstancesInputRequestTypeDef, _OptionalDescribeInstancesInputRequestTypeDef
 ):
     pass
 
-
 InstanceTypeDef = TypedDict(
     "InstanceTypeDef",
     {
         "FleetId": str,
         "FleetArn": str,
         "InstanceId": str,
         "IpAddress": str,
@@ -1187,14 +1260,24 @@
         "Status": InstanceStatusType,
         "CreationTime": datetime,
         "Location": str,
     },
     total=False,
 )
 
+DescribeMatchmakingConfigurationsInputDescribeMatchmakingConfigurationsPaginateTypeDef = TypedDict(
+    "DescribeMatchmakingConfigurationsInputDescribeMatchmakingConfigurationsPaginateTypeDef",
+    {
+        "Names": Sequence[str],
+        "RuleSetName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeMatchmakingConfigurationsInputRequestTypeDef = TypedDict(
     "DescribeMatchmakingConfigurationsInputRequestTypeDef",
     {
         "Names": Sequence[str],
         "RuleSetName": str,
         "Limit": int,
         "NextToken": str,
@@ -1205,24 +1288,45 @@
 DescribeMatchmakingInputRequestTypeDef = TypedDict(
     "DescribeMatchmakingInputRequestTypeDef",
     {
         "TicketIds": Sequence[str],
     },
 )
 
+DescribeMatchmakingRuleSetsInputDescribeMatchmakingRuleSetsPaginateTypeDef = TypedDict(
+    "DescribeMatchmakingRuleSetsInputDescribeMatchmakingRuleSetsPaginateTypeDef",
+    {
+        "Names": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeMatchmakingRuleSetsInputRequestTypeDef = TypedDict(
     "DescribeMatchmakingRuleSetsInputRequestTypeDef",
     {
         "Names": Sequence[str],
         "Limit": int,
         "NextToken": str,
     },
     total=False,
 )
 
+DescribePlayerSessionsInputDescribePlayerSessionsPaginateTypeDef = TypedDict(
+    "DescribePlayerSessionsInputDescribePlayerSessionsPaginateTypeDef",
+    {
+        "GameSessionId": str,
+        "PlayerId": str,
+        "PlayerSessionId": str,
+        "PlayerSessionStatusFilter": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribePlayerSessionsInputRequestTypeDef = TypedDict(
     "DescribePlayerSessionsInputRequestTypeDef",
     {
         "GameSessionId": str,
         "PlayerId": str,
         "PlayerSessionId": str,
         "PlayerSessionStatusFilter": str,
@@ -1235,14 +1339,36 @@
 DescribeRuntimeConfigurationInputRequestTypeDef = TypedDict(
     "DescribeRuntimeConfigurationInputRequestTypeDef",
     {
         "FleetId": str,
     },
 )
 
+_RequiredDescribeScalingPoliciesInputDescribeScalingPoliciesPaginateTypeDef = TypedDict(
+    "_RequiredDescribeScalingPoliciesInputDescribeScalingPoliciesPaginateTypeDef",
+    {
+        "FleetId": str,
+    },
+)
+_OptionalDescribeScalingPoliciesInputDescribeScalingPoliciesPaginateTypeDef = TypedDict(
+    "_OptionalDescribeScalingPoliciesInputDescribeScalingPoliciesPaginateTypeDef",
+    {
+        "StatusFilter": ScalingStatusTypeType,
+        "Location": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeScalingPoliciesInputDescribeScalingPoliciesPaginateTypeDef(
+    _RequiredDescribeScalingPoliciesInputDescribeScalingPoliciesPaginateTypeDef,
+    _OptionalDescribeScalingPoliciesInputDescribeScalingPoliciesPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeScalingPoliciesInputRequestTypeDef = TypedDict(
     "_RequiredDescribeScalingPoliciesInputRequestTypeDef",
     {
         "FleetId": str,
     },
 )
 _OptionalDescribeScalingPoliciesInputRequestTypeDef = TypedDict(
@@ -1252,22 +1378,20 @@
         "Limit": int,
         "NextToken": str,
         "Location": str,
     },
     total=False,
 )
 
-
 class DescribeScalingPoliciesInputRequestTypeDef(
     _RequiredDescribeScalingPoliciesInputRequestTypeDef,
     _OptionalDescribeScalingPoliciesInputRequestTypeDef,
 ):
     pass
 
-
 DescribeScriptInputRequestTypeDef = TypedDict(
     "DescribeScriptInputRequestTypeDef",
     {
         "ScriptId": str,
     },
 )
 
@@ -1298,14 +1422,21 @@
         "ACTIVE": int,
         "IDLE": int,
         "TERMINATING": int,
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
 TargetTrackingConfigurationTypeDef = TypedDict(
     "TargetTrackingConfigurationTypeDef",
     {
         "TargetValue": float,
     },
 )
 
@@ -1349,21 +1480,42 @@
     "GetComputeAuthTokenInputRequestTypeDef",
     {
         "FleetId": str,
         "ComputeName": str,
     },
 )
 
+GetComputeAuthTokenOutputTypeDef = TypedDict(
+    "GetComputeAuthTokenOutputTypeDef",
+    {
+        "FleetId": str,
+        "FleetArn": str,
+        "ComputeName": str,
+        "ComputeArn": str,
+        "AuthToken": str,
+        "ExpirationTimestamp": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetGameSessionLogUrlInputRequestTypeDef = TypedDict(
     "GetGameSessionLogUrlInputRequestTypeDef",
     {
         "GameSessionId": str,
     },
 )
 
+GetGameSessionLogUrlOutputTypeDef = TypedDict(
+    "GetGameSessionLogUrlOutputTypeDef",
+    {
+        "PreSignedUrl": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetInstanceAccessInputRequestTypeDef = TypedDict(
     "GetInstanceAccessInputRequestTypeDef",
     {
         "FleetId": str,
         "InstanceId": str,
     },
 )
@@ -1373,35 +1525,75 @@
     {
         "UserName": str,
         "Secret": str,
     },
     total=False,
 )
 
+ListAliasesInputListAliasesPaginateTypeDef = TypedDict(
+    "ListAliasesInputListAliasesPaginateTypeDef",
+    {
+        "RoutingStrategyType": RoutingStrategyTypeType,
+        "Name": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListAliasesInputRequestTypeDef = TypedDict(
     "ListAliasesInputRequestTypeDef",
     {
         "RoutingStrategyType": RoutingStrategyTypeType,
         "Name": str,
         "Limit": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListBuildsInputListBuildsPaginateTypeDef = TypedDict(
+    "ListBuildsInputListBuildsPaginateTypeDef",
+    {
+        "Status": BuildStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListBuildsInputRequestTypeDef = TypedDict(
     "ListBuildsInputRequestTypeDef",
     {
         "Status": BuildStatusType,
         "Limit": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredListComputeInputListComputePaginateTypeDef = TypedDict(
+    "_RequiredListComputeInputListComputePaginateTypeDef",
+    {
+        "FleetId": str,
+    },
+)
+_OptionalListComputeInputListComputePaginateTypeDef = TypedDict(
+    "_OptionalListComputeInputListComputePaginateTypeDef",
+    {
+        "Location": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListComputeInputListComputePaginateTypeDef(
+    _RequiredListComputeInputListComputePaginateTypeDef,
+    _OptionalListComputeInputListComputePaginateTypeDef,
+):
+    pass
+
 _RequiredListComputeInputRequestTypeDef = TypedDict(
     "_RequiredListComputeInputRequestTypeDef",
     {
         "FleetId": str,
     },
 )
 _OptionalListComputeInputRequestTypeDef = TypedDict(
@@ -1410,41 +1602,87 @@
         "Location": str,
         "Limit": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class ListComputeInputRequestTypeDef(
     _RequiredListComputeInputRequestTypeDef, _OptionalListComputeInputRequestTypeDef
 ):
     pass
 
+ListFleetsInputListFleetsPaginateTypeDef = TypedDict(
+    "ListFleetsInputListFleetsPaginateTypeDef",
+    {
+        "BuildId": str,
+        "ScriptId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
 
 ListFleetsInputRequestTypeDef = TypedDict(
     "ListFleetsInputRequestTypeDef",
     {
         "BuildId": str,
         "ScriptId": str,
         "Limit": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListFleetsOutputTypeDef = TypedDict(
+    "ListFleetsOutputTypeDef",
+    {
+        "FleetIds": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListGameServerGroupsInputListGameServerGroupsPaginateTypeDef = TypedDict(
+    "ListGameServerGroupsInputListGameServerGroupsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListGameServerGroupsInputRequestTypeDef = TypedDict(
     "ListGameServerGroupsInputRequestTypeDef",
     {
         "Limit": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredListGameServersInputListGameServersPaginateTypeDef = TypedDict(
+    "_RequiredListGameServersInputListGameServersPaginateTypeDef",
+    {
+        "GameServerGroupName": str,
+    },
+)
+_OptionalListGameServersInputListGameServersPaginateTypeDef = TypedDict(
+    "_OptionalListGameServersInputListGameServersPaginateTypeDef",
+    {
+        "SortOrder": SortOrderType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListGameServersInputListGameServersPaginateTypeDef(
+    _RequiredListGameServersInputListGameServersPaginateTypeDef,
+    _OptionalListGameServersInputListGameServersPaginateTypeDef,
+):
+    pass
+
 _RequiredListGameServersInputRequestTypeDef = TypedDict(
     "_RequiredListGameServersInputRequestTypeDef",
     {
         "GameServerGroupName": str,
     },
 )
 _OptionalListGameServersInputRequestTypeDef = TypedDict(
@@ -1453,31 +1691,46 @@
         "SortOrder": SortOrderType,
         "Limit": int,
         "NextToken": str,
     },
     total=False,
 )
 
-
 class ListGameServersInputRequestTypeDef(
     _RequiredListGameServersInputRequestTypeDef, _OptionalListGameServersInputRequestTypeDef
 ):
     pass
 
+ListLocationsInputListLocationsPaginateTypeDef = TypedDict(
+    "ListLocationsInputListLocationsPaginateTypeDef",
+    {
+        "Filters": Sequence[LocationFilterType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
 
 ListLocationsInputRequestTypeDef = TypedDict(
     "ListLocationsInputRequestTypeDef",
     {
         "Filters": Sequence[LocationFilterType],
         "Limit": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListScriptsInputListScriptsPaginateTypeDef = TypedDict(
+    "ListScriptsInputListScriptsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListScriptsInputRequestTypeDef = TypedDict(
     "ListScriptsInputRequestTypeDef",
     {
         "Limit": int,
         "NextToken": str,
     },
     total=False,
@@ -1486,21 +1739,39 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
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
 TargetConfigurationTypeDef = TypedDict(
     "TargetConfigurationTypeDef",
     {
         "TargetValue": float,
     },
 )
 
+PutScalingPolicyOutputTypeDef = TypedDict(
+    "PutScalingPolicyOutputTypeDef",
+    {
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredRegisterComputeInputRequestTypeDef = TypedDict(
     "_RequiredRegisterComputeInputRequestTypeDef",
     {
         "FleetId": str,
         "ComputeName": str,
     },
 )
@@ -1511,21 +1782,19 @@
         "DnsName": str,
         "IpAddress": str,
         "Location": str,
     },
     total=False,
 )
 
-
 class RegisterComputeInputRequestTypeDef(
     _RequiredRegisterComputeInputRequestTypeDef, _OptionalRegisterComputeInputRequestTypeDef
 ):
     pass
 
-
 _RequiredRegisterGameServerInputRequestTypeDef = TypedDict(
     "_RequiredRegisterGameServerInputRequestTypeDef",
     {
         "GameServerGroupName": str,
         "GameServerId": str,
         "InstanceId": str,
     },
@@ -1535,35 +1804,53 @@
     {
         "ConnectionInfo": str,
         "GameServerData": str,
     },
     total=False,
 )
 
-
 class RegisterGameServerInputRequestTypeDef(
     _RequiredRegisterGameServerInputRequestTypeDef, _OptionalRegisterGameServerInputRequestTypeDef
 ):
     pass
 
-
 RequestUploadCredentialsInputRequestTypeDef = TypedDict(
     "RequestUploadCredentialsInputRequestTypeDef",
     {
         "BuildId": str,
     },
 )
 
 ResolveAliasInputRequestTypeDef = TypedDict(
     "ResolveAliasInputRequestTypeDef",
     {
         "AliasId": str,
     },
 )
 
+ResolveAliasOutputTypeDef = TypedDict(
+    "ResolveAliasOutputTypeDef",
+    {
+        "FleetId": str,
+        "FleetArn": str,
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
 ResumeGameServerGroupInputRequestTypeDef = TypedDict(
     "ResumeGameServerGroupInputRequestTypeDef",
     {
         "GameServerGroupName": str,
         "ResumeActions": Sequence[Literal["REPLACE_INSTANCE_TYPES"]],
     },
 )
@@ -1579,33 +1866,44 @@
     "_OptionalServerProcessTypeDef",
     {
         "Parameters": str,
     },
     total=False,
 )
 
-
 class ServerProcessTypeDef(_RequiredServerProcessTypeDef, _OptionalServerProcessTypeDef):
     pass
 
-
 SearchGameSessionsInputRequestTypeDef = TypedDict(
     "SearchGameSessionsInputRequestTypeDef",
     {
         "FleetId": str,
         "AliasId": str,
         "Location": str,
         "FilterExpression": str,
         "SortExpression": str,
         "Limit": int,
         "NextToken": str,
     },
     total=False,
 )
 
+SearchGameSessionsInputSearchGameSessionsPaginateTypeDef = TypedDict(
+    "SearchGameSessionsInputSearchGameSessionsPaginateTypeDef",
+    {
+        "FleetId": str,
+        "AliasId": str,
+        "Location": str,
+        "FilterExpression": str,
+        "SortExpression": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 _RequiredStartFleetActionsInputRequestTypeDef = TypedDict(
     "_RequiredStartFleetActionsInputRequestTypeDef",
     {
         "FleetId": str,
         "Actions": Sequence[Literal["AUTO_SCALING"]],
     },
 )
@@ -1613,20 +1911,27 @@
     "_OptionalStartFleetActionsInputRequestTypeDef",
     {
         "Location": str,
     },
     total=False,
 )
 
-
 class StartFleetActionsInputRequestTypeDef(
     _RequiredStartFleetActionsInputRequestTypeDef, _OptionalStartFleetActionsInputRequestTypeDef
 ):
     pass
 
+StartFleetActionsOutputTypeDef = TypedDict(
+    "StartFleetActionsOutputTypeDef",
+    {
+        "FleetId": str,
+        "FleetArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredStopFleetActionsInputRequestTypeDef = TypedDict(
     "_RequiredStopFleetActionsInputRequestTypeDef",
     {
         "FleetId": str,
         "Actions": Sequence[Literal["AUTO_SCALING"]],
     },
@@ -1635,20 +1940,27 @@
     "_OptionalStopFleetActionsInputRequestTypeDef",
     {
         "Location": str,
     },
     total=False,
 )
 
-
 class StopFleetActionsInputRequestTypeDef(
     _RequiredStopFleetActionsInputRequestTypeDef, _OptionalStopFleetActionsInputRequestTypeDef
 ):
     pass
 
+StopFleetActionsOutputTypeDef = TypedDict(
+    "StopFleetActionsOutputTypeDef",
+    {
+        "FleetId": str,
+        "FleetArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 StopGameSessionPlacementInputRequestTypeDef = TypedDict(
     "StopGameSessionPlacementInputRequestTypeDef",
     {
         "PlacementId": str,
     },
 )
@@ -1687,20 +1999,27 @@
     {
         "Name": str,
         "Version": str,
     },
     total=False,
 )
 
-
 class UpdateBuildInputRequestTypeDef(
     _RequiredUpdateBuildInputRequestTypeDef, _OptionalUpdateBuildInputRequestTypeDef
 ):
     pass
 
+UpdateFleetAttributesOutputTypeDef = TypedDict(
+    "UpdateFleetAttributesOutputTypeDef",
+    {
+        "FleetId": str,
+        "FleetArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredUpdateFleetCapacityInputRequestTypeDef = TypedDict(
     "_RequiredUpdateFleetCapacityInputRequestTypeDef",
     {
         "FleetId": str,
     },
 )
@@ -1711,20 +2030,37 @@
         "MinSize": int,
         "MaxSize": int,
         "Location": str,
     },
     total=False,
 )
 
-
 class UpdateFleetCapacityInputRequestTypeDef(
     _RequiredUpdateFleetCapacityInputRequestTypeDef, _OptionalUpdateFleetCapacityInputRequestTypeDef
 ):
     pass
 
+UpdateFleetCapacityOutputTypeDef = TypedDict(
+    "UpdateFleetCapacityOutputTypeDef",
+    {
+        "FleetId": str,
+        "FleetArn": str,
+        "Location": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateFleetPortSettingsOutputTypeDef = TypedDict(
+    "UpdateFleetPortSettingsOutputTypeDef",
+    {
+        "FleetId": str,
+        "FleetArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
 
 _RequiredUpdateGameServerInputRequestTypeDef = TypedDict(
     "_RequiredUpdateGameServerInputRequestTypeDef",
     {
         "GameServerGroupName": str,
         "GameServerId": str,
     },
@@ -1735,21 +2071,19 @@
         "GameServerData": str,
         "UtilizationStatus": GameServerUtilizationStatusType,
         "HealthCheck": Literal["HEALTHY"],
     },
     total=False,
 )
 
-
 class UpdateGameServerInputRequestTypeDef(
     _RequiredUpdateGameServerInputRequestTypeDef, _OptionalUpdateGameServerInputRequestTypeDef
 ):
     pass
 
-
 _RequiredUpdateGameSessionInputRequestTypeDef = TypedDict(
     "_RequiredUpdateGameSessionInputRequestTypeDef",
     {
         "GameSessionId": str,
     },
 )
 _OptionalUpdateGameSessionInputRequestTypeDef = TypedDict(
@@ -1759,28 +2093,34 @@
         "Name": str,
         "PlayerSessionCreationPolicy": PlayerSessionCreationPolicyType,
         "ProtectionPolicy": ProtectionPolicyType,
     },
     total=False,
 )
 
-
 class UpdateGameSessionInputRequestTypeDef(
     _RequiredUpdateGameSessionInputRequestTypeDef, _OptionalUpdateGameSessionInputRequestTypeDef
 ):
     pass
 
-
 ValidateMatchmakingRuleSetInputRequestTypeDef = TypedDict(
     "ValidateMatchmakingRuleSetInputRequestTypeDef",
     {
         "RuleSetBody": str,
     },
 )
 
+ValidateMatchmakingRuleSetOutputTypeDef = TypedDict(
+    "ValidateMatchmakingRuleSetOutputTypeDef",
+    {
+        "Valid": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 VpcPeeringConnectionStatusTypeDef = TypedDict(
     "VpcPeeringConnectionStatusTypeDef",
     {
         "Code": str,
         "Message": str,
     },
     total=False,
@@ -1812,240 +2152,151 @@
         "Name": str,
         "Description": str,
         "RoutingStrategy": RoutingStrategyTypeDef,
     },
     total=False,
 )
 
-
 class UpdateAliasInputRequestTypeDef(
     _RequiredUpdateAliasInputRequestTypeDef, _OptionalUpdateAliasInputRequestTypeDef
 ):
     pass
 
-
 PlayerTypeDef = TypedDict(
     "PlayerTypeDef",
     {
         "PlayerId": str,
         "PlayerAttributes": Dict[str, AttributeValueTypeDef],
         "Team": str,
         "LatencyInMs": Dict[str, int],
     },
     total=False,
 )
 
-ClaimGameServerOutputTypeDef = TypedDict(
-    "ClaimGameServerOutputTypeDef",
-    {
-        "GameServer": GameServerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeBuildOutputTypeDef = TypedDict(
-    "DescribeBuildOutputTypeDef",
-    {
-        "Build": BuildTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeGameServerOutputTypeDef = TypedDict(
-    "DescribeGameServerOutputTypeDef",
-    {
-        "GameServer": GameServerTypeDef,
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
 GetComputeAccessOutputTypeDef = TypedDict(
     "GetComputeAccessOutputTypeDef",
     {
         "FleetId": str,
         "FleetArn": str,
         "ComputeName": str,
         "ComputeArn": str,
         "Credentials": AwsCredentialsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetComputeAuthTokenOutputTypeDef = TypedDict(
-    "GetComputeAuthTokenOutputTypeDef",
-    {
-        "FleetId": str,
-        "FleetArn": str,
-        "ComputeName": str,
-        "ComputeArn": str,
-        "AuthToken": str,
-        "ExpirationTimestamp": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetGameSessionLogUrlOutputTypeDef = TypedDict(
-    "GetGameSessionLogUrlOutputTypeDef",
+DescribeBuildOutputTypeDef = TypedDict(
+    "DescribeBuildOutputTypeDef",
     {
-        "PreSignedUrl": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Build": BuildTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListBuildsOutputTypeDef = TypedDict(
     "ListBuildsOutputTypeDef",
     {
         "Builds": List[BuildTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListFleetsOutputTypeDef = TypedDict(
-    "ListFleetsOutputTypeDef",
-    {
-        "FleetIds": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListGameServersOutputTypeDef = TypedDict(
-    "ListGameServersOutputTypeDef",
-    {
-        "GameServers": List[GameServerTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutScalingPolicyOutputTypeDef = TypedDict(
-    "PutScalingPolicyOutputTypeDef",
-    {
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RegisterGameServerOutputTypeDef = TypedDict(
-    "RegisterGameServerOutputTypeDef",
+UpdateBuildOutputTypeDef = TypedDict(
+    "UpdateBuildOutputTypeDef",
     {
-        "GameServer": GameServerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Build": BuildTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ResolveAliasOutputTypeDef = TypedDict(
-    "ResolveAliasOutputTypeDef",
+_RequiredClaimGameServerInputRequestTypeDef = TypedDict(
+    "_RequiredClaimGameServerInputRequestTypeDef",
     {
-        "FleetId": str,
-        "FleetArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "GameServerGroupName": str,
     },
 )
-
-StartFleetActionsOutputTypeDef = TypedDict(
-    "StartFleetActionsOutputTypeDef",
+_OptionalClaimGameServerInputRequestTypeDef = TypedDict(
+    "_OptionalClaimGameServerInputRequestTypeDef",
     {
-        "FleetId": str,
-        "FleetArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "GameServerId": str,
+        "GameServerData": str,
+        "FilterOption": ClaimFilterOptionTypeDef,
     },
+    total=False,
 )
 
-StopFleetActionsOutputTypeDef = TypedDict(
-    "StopFleetActionsOutputTypeDef",
-    {
-        "FleetId": str,
-        "FleetArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class ClaimGameServerInputRequestTypeDef(
+    _RequiredClaimGameServerInputRequestTypeDef, _OptionalClaimGameServerInputRequestTypeDef
+):
+    pass
 
-UpdateBuildOutputTypeDef = TypedDict(
-    "UpdateBuildOutputTypeDef",
+ClaimGameServerOutputTypeDef = TypedDict(
+    "ClaimGameServerOutputTypeDef",
     {
-        "Build": BuildTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "GameServer": GameServerTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateFleetAttributesOutputTypeDef = TypedDict(
-    "UpdateFleetAttributesOutputTypeDef",
+DescribeGameServerOutputTypeDef = TypedDict(
+    "DescribeGameServerOutputTypeDef",
     {
-        "FleetId": str,
-        "FleetArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "GameServer": GameServerTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateFleetCapacityOutputTypeDef = TypedDict(
-    "UpdateFleetCapacityOutputTypeDef",
+ListGameServersOutputTypeDef = TypedDict(
+    "ListGameServersOutputTypeDef",
     {
-        "FleetId": str,
-        "FleetArn": str,
-        "Location": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "GameServers": List[GameServerTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateFleetPortSettingsOutputTypeDef = TypedDict(
-    "UpdateFleetPortSettingsOutputTypeDef",
+RegisterGameServerOutputTypeDef = TypedDict(
+    "RegisterGameServerOutputTypeDef",
     {
-        "FleetId": str,
-        "FleetArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "GameServer": GameServerTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateGameServerOutputTypeDef = TypedDict(
     "UpdateGameServerOutputTypeDef",
     {
         "GameServer": GameServerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ValidateMatchmakingRuleSetOutputTypeDef = TypedDict(
-    "ValidateMatchmakingRuleSetOutputTypeDef",
-    {
-        "Valid": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeComputeOutputTypeDef = TypedDict(
     "DescribeComputeOutputTypeDef",
     {
         "Compute": ComputeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListComputeOutputTypeDef = TypedDict(
     "ListComputeOutputTypeDef",
     {
         "ComputeList": List[ComputeTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RegisterComputeOutputTypeDef = TypedDict(
     "RegisterComputeOutputTypeDef",
     {
         "Compute": ComputeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateAliasInputRequestTypeDef = TypedDict(
     "_RequiredCreateAliasInputRequestTypeDef",
     {
         "Name": str,
@@ -2057,42 +2308,38 @@
     {
         "Description": str,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateAliasInputRequestTypeDef(
     _RequiredCreateAliasInputRequestTypeDef, _OptionalCreateAliasInputRequestTypeDef
 ):
     pass
 
-
 _RequiredCreateLocationInputRequestTypeDef = TypedDict(
     "_RequiredCreateLocationInputRequestTypeDef",
     {
         "LocationName": str,
     },
 )
 _OptionalCreateLocationInputRequestTypeDef = TypedDict(
     "_OptionalCreateLocationInputRequestTypeDef",
     {
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateLocationInputRequestTypeDef(
     _RequiredCreateLocationInputRequestTypeDef, _OptionalCreateLocationInputRequestTypeDef
 ):
     pass
 
-
 _RequiredCreateMatchmakingRuleSetInputRequestTypeDef = TypedDict(
     "_RequiredCreateMatchmakingRuleSetInputRequestTypeDef",
     {
         "Name": str,
         "RuleSetBody": str,
     },
 )
@@ -2100,27 +2347,25 @@
     "_OptionalCreateMatchmakingRuleSetInputRequestTypeDef",
     {
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateMatchmakingRuleSetInputRequestTypeDef(
     _RequiredCreateMatchmakingRuleSetInputRequestTypeDef,
     _OptionalCreateMatchmakingRuleSetInputRequestTypeDef,
 ):
     pass
 
-
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
@@ -2143,15 +2388,15 @@
 
 CreateBuildOutputTypeDef = TypedDict(
     "CreateBuildOutputTypeDef",
     {
         "Build": BuildTypeDef,
         "UploadCredentials": AwsCredentialsTypeDef,
         "StorageLocation": S3LocationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateScriptInputRequestTypeDef = TypedDict(
     "CreateScriptInputRequestTypeDef",
     {
         "Name": str,
@@ -2164,15 +2409,15 @@
 )
 
 RequestUploadCredentialsOutputTypeDef = TypedDict(
     "RequestUploadCredentialsOutputTypeDef",
     {
         "UploadCredentials": AwsCredentialsTypeDef,
         "StorageLocation": S3LocationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ScriptTypeDef = TypedDict(
     "ScriptTypeDef",
     {
         "ScriptId": str,
@@ -2199,30 +2444,28 @@
         "Version": str,
         "StorageLocation": S3LocationTypeDef,
         "ZipFile": Union[str, bytes, IO[Any], StreamingBody],
     },
     total=False,
 )
 
-
 class UpdateScriptInputRequestTypeDef(
     _RequiredUpdateScriptInputRequestTypeDef, _OptionalUpdateScriptInputRequestTypeDef
 ):
     pass
 
-
 DescribeFleetPortSettingsOutputTypeDef = TypedDict(
     "DescribeFleetPortSettingsOutputTypeDef",
     {
         "FleetId": str,
         "FleetArn": str,
         "InboundPermissions": List[IpPermissionTypeDef],
         "UpdateStatus": Literal["PENDING_UPDATE"],
         "Location": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateFleetPortSettingsInputRequestTypeDef = TypedDict(
     "_RequiredUpdateFleetPortSettingsInputRequestTypeDef",
     {
         "FleetId": str,
@@ -2233,22 +2476,20 @@
     {
         "InboundPermissionAuthorizations": Sequence[IpPermissionTypeDef],
         "InboundPermissionRevocations": Sequence[IpPermissionTypeDef],
     },
     total=False,
 )
 
-
 class UpdateFleetPortSettingsInputRequestTypeDef(
     _RequiredUpdateFleetPortSettingsInputRequestTypeDef,
     _OptionalUpdateFleetPortSettingsInputRequestTypeDef,
 ):
     pass
 
-
 CreateFleetLocationsInputRequestTypeDef = TypedDict(
     "CreateFleetLocationsInputRequestTypeDef",
     {
         "FleetId": str,
         "Locations": Sequence[LocationConfigurationTypeDef],
     },
 )
@@ -2300,39 +2541,37 @@
         "ResourceCreationLimitPolicy": ResourceCreationLimitPolicyTypeDef,
         "MetricGroups": Sequence[str],
         "AnywhereConfiguration": AnywhereConfigurationTypeDef,
     },
     total=False,
 )
 
-
 class UpdateFleetAttributesInputRequestTypeDef(
     _RequiredUpdateFleetAttributesInputRequestTypeDef,
     _OptionalUpdateFleetAttributesInputRequestTypeDef,
 ):
     pass
 
-
 CreateFleetLocationsOutputTypeDef = TypedDict(
     "CreateFleetLocationsOutputTypeDef",
     {
         "FleetId": str,
         "FleetArn": str,
         "LocationStates": List[LocationStateTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteFleetLocationsOutputTypeDef = TypedDict(
     "DeleteFleetLocationsOutputTypeDef",
     {
         "FleetId": str,
         "FleetArn": str,
         "LocationStates": List[LocationStateTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LocationAttributesTypeDef = TypedDict(
     "LocationAttributesTypeDef",
     {
         "LocationState": LocationStateTypeDef,
@@ -2374,22 +2613,20 @@
         "InstanceDefinitions": Sequence[InstanceDefinitionTypeDef],
         "GameServerProtectionPolicy": GameServerProtectionPolicyType,
         "BalancingStrategy": BalancingStrategyType,
     },
     total=False,
 )
 
-
 class UpdateGameServerGroupInputRequestTypeDef(
     _RequiredUpdateGameServerGroupInputRequestTypeDef,
     _OptionalUpdateGameServerGroupInputRequestTypeDef,
 ):
     pass
 
-
 _RequiredCreateGameSessionInputRequestTypeDef = TypedDict(
     "_RequiredCreateGameSessionInputRequestTypeDef",
     {
         "MaximumPlayerSessionCount": int,
     },
 )
 _OptionalCreateGameSessionInputRequestTypeDef = TypedDict(
@@ -2404,21 +2641,19 @@
         "IdempotencyToken": str,
         "GameSessionData": str,
         "Location": str,
     },
     total=False,
 )
 
-
 class CreateGameSessionInputRequestTypeDef(
     _RequiredCreateGameSessionInputRequestTypeDef, _OptionalCreateGameSessionInputRequestTypeDef
 ):
     pass
 
-
 _RequiredCreateMatchmakingConfigurationInputRequestTypeDef = TypedDict(
     "_RequiredCreateMatchmakingConfigurationInputRequestTypeDef",
     {
         "Name": str,
         "RequestTimeoutSeconds": int,
         "AcceptanceRequired": bool,
         "RuleSetName": str,
@@ -2438,22 +2673,20 @@
         "BackfillMode": BackfillModeType,
         "FlexMatchMode": FlexMatchModeType,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateMatchmakingConfigurationInputRequestTypeDef(
     _RequiredCreateMatchmakingConfigurationInputRequestTypeDef,
     _OptionalCreateMatchmakingConfigurationInputRequestTypeDef,
 ):
     pass
 
-
 GameSessionTypeDef = TypedDict(
     "GameSessionTypeDef",
     {
         "GameSessionId": str,
         "Name": str,
         "FleetId": str,
         "FleetArn": str,
@@ -2522,22 +2755,20 @@
         "GameSessionData": str,
         "BackfillMode": BackfillModeType,
         "FlexMatchMode": FlexMatchModeType,
     },
     total=False,
 )
 
-
 class UpdateMatchmakingConfigurationInputRequestTypeDef(
     _RequiredUpdateMatchmakingConfigurationInputRequestTypeDef,
     _OptionalUpdateMatchmakingConfigurationInputRequestTypeDef,
 ):
     pass
 
-
 _RequiredCreateGameSessionQueueInputRequestTypeDef = TypedDict(
     "_RequiredCreateGameSessionQueueInputRequestTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalCreateGameSessionQueueInputRequestTypeDef = TypedDict(
@@ -2551,22 +2782,20 @@
         "CustomEventData": str,
         "NotificationTarget": str,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateGameSessionQueueInputRequestTypeDef(
     _RequiredCreateGameSessionQueueInputRequestTypeDef,
     _OptionalCreateGameSessionQueueInputRequestTypeDef,
 ):
     pass
 
-
 GameSessionQueueTypeDef = TypedDict(
     "GameSessionQueueTypeDef",
     {
         "Name": str,
         "GameSessionQueueArn": str,
         "TimeoutInSeconds": int,
         "PlayerLatencyPolicies": List[PlayerLatencyPolicyTypeDef],
@@ -2595,447 +2824,144 @@
         "PriorityConfiguration": PriorityConfigurationTypeDef,
         "CustomEventData": str,
         "NotificationTarget": str,
     },
     total=False,
 )
 
-
 class UpdateGameSessionQueueInputRequestTypeDef(
     _RequiredUpdateGameSessionQueueInputRequestTypeDef,
     _OptionalUpdateGameSessionQueueInputRequestTypeDef,
 ):
     pass
 
-
 CreateLocationOutputTypeDef = TypedDict(
     "CreateLocationOutputTypeDef",
     {
         "Location": LocationModelTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListLocationsOutputTypeDef = TypedDict(
     "ListLocationsOutputTypeDef",
     {
         "Locations": List[LocationModelTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateMatchmakingRuleSetOutputTypeDef = TypedDict(
     "CreateMatchmakingRuleSetOutputTypeDef",
     {
         "RuleSet": MatchmakingRuleSetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeMatchmakingRuleSetsOutputTypeDef = TypedDict(
     "DescribeMatchmakingRuleSetsOutputTypeDef",
     {
         "RuleSets": List[MatchmakingRuleSetTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreatePlayerSessionOutputTypeDef = TypedDict(
     "CreatePlayerSessionOutputTypeDef",
     {
         "PlayerSession": PlayerSessionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreatePlayerSessionsOutputTypeDef = TypedDict(
     "CreatePlayerSessionsOutputTypeDef",
     {
         "PlayerSessions": List[PlayerSessionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribePlayerSessionsOutputTypeDef = TypedDict(
     "DescribePlayerSessionsOutputTypeDef",
     {
         "PlayerSessions": List[PlayerSessionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateVpcPeeringAuthorizationOutputTypeDef = TypedDict(
     "CreateVpcPeeringAuthorizationOutputTypeDef",
     {
         "VpcPeeringAuthorization": VpcPeeringAuthorizationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeVpcPeeringAuthorizationsOutputTypeDef = TypedDict(
     "DescribeVpcPeeringAuthorizationsOutputTypeDef",
     {
         "VpcPeeringAuthorizations": List[VpcPeeringAuthorizationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEC2InstanceLimitsOutputTypeDef = TypedDict(
     "DescribeEC2InstanceLimitsOutputTypeDef",
     {
         "EC2InstanceLimits": List[EC2InstanceLimitTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DescribeFleetAttributesInputDescribeFleetAttributesPaginateTypeDef = TypedDict(
-    "DescribeFleetAttributesInputDescribeFleetAttributesPaginateTypeDef",
-    {
-        "FleetIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeFleetCapacityInputDescribeFleetCapacityPaginateTypeDef = TypedDict(
-    "DescribeFleetCapacityInputDescribeFleetCapacityPaginateTypeDef",
-    {
-        "FleetIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeFleetEventsInputDescribeFleetEventsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeFleetEventsInputDescribeFleetEventsPaginateTypeDef",
-    {
-        "FleetId": str,
-    },
-)
-_OptionalDescribeFleetEventsInputDescribeFleetEventsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeFleetEventsInputDescribeFleetEventsPaginateTypeDef",
-    {
-        "StartTime": Union[datetime, str],
-        "EndTime": Union[datetime, str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeFleetEventsInputDescribeFleetEventsPaginateTypeDef(
-    _RequiredDescribeFleetEventsInputDescribeFleetEventsPaginateTypeDef,
-    _OptionalDescribeFleetEventsInputDescribeFleetEventsPaginateTypeDef,
-):
-    pass
-
-
-DescribeFleetUtilizationInputDescribeFleetUtilizationPaginateTypeDef = TypedDict(
-    "DescribeFleetUtilizationInputDescribeFleetUtilizationPaginateTypeDef",
-    {
-        "FleetIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeGameServerInstancesInputDescribeGameServerInstancesPaginateTypeDef = TypedDict(
-    "_RequiredDescribeGameServerInstancesInputDescribeGameServerInstancesPaginateTypeDef",
-    {
-        "GameServerGroupName": str,
-    },
-)
-_OptionalDescribeGameServerInstancesInputDescribeGameServerInstancesPaginateTypeDef = TypedDict(
-    "_OptionalDescribeGameServerInstancesInputDescribeGameServerInstancesPaginateTypeDef",
-    {
-        "InstanceIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeGameServerInstancesInputDescribeGameServerInstancesPaginateTypeDef(
-    _RequiredDescribeGameServerInstancesInputDescribeGameServerInstancesPaginateTypeDef,
-    _OptionalDescribeGameServerInstancesInputDescribeGameServerInstancesPaginateTypeDef,
-):
-    pass
-
-
-DescribeGameSessionDetailsInputDescribeGameSessionDetailsPaginateTypeDef = TypedDict(
-    "DescribeGameSessionDetailsInputDescribeGameSessionDetailsPaginateTypeDef",
-    {
-        "FleetId": str,
-        "GameSessionId": str,
-        "AliasId": str,
-        "Location": str,
-        "StatusFilter": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeGameSessionQueuesInputDescribeGameSessionQueuesPaginateTypeDef = TypedDict(
-    "DescribeGameSessionQueuesInputDescribeGameSessionQueuesPaginateTypeDef",
-    {
-        "Names": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeGameSessionsInputDescribeGameSessionsPaginateTypeDef = TypedDict(
-    "DescribeGameSessionsInputDescribeGameSessionsPaginateTypeDef",
-    {
-        "FleetId": str,
-        "GameSessionId": str,
-        "AliasId": str,
-        "Location": str,
-        "StatusFilter": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeInstancesInputDescribeInstancesPaginateTypeDef = TypedDict(
-    "_RequiredDescribeInstancesInputDescribeInstancesPaginateTypeDef",
-    {
-        "FleetId": str,
-    },
-)
-_OptionalDescribeInstancesInputDescribeInstancesPaginateTypeDef = TypedDict(
-    "_OptionalDescribeInstancesInputDescribeInstancesPaginateTypeDef",
-    {
-        "InstanceId": str,
-        "Location": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeInstancesInputDescribeInstancesPaginateTypeDef(
-    _RequiredDescribeInstancesInputDescribeInstancesPaginateTypeDef,
-    _OptionalDescribeInstancesInputDescribeInstancesPaginateTypeDef,
-):
-    pass
-
-
-DescribeMatchmakingConfigurationsInputDescribeMatchmakingConfigurationsPaginateTypeDef = TypedDict(
-    "DescribeMatchmakingConfigurationsInputDescribeMatchmakingConfigurationsPaginateTypeDef",
-    {
-        "Names": Sequence[str],
-        "RuleSetName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeMatchmakingRuleSetsInputDescribeMatchmakingRuleSetsPaginateTypeDef = TypedDict(
-    "DescribeMatchmakingRuleSetsInputDescribeMatchmakingRuleSetsPaginateTypeDef",
-    {
-        "Names": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribePlayerSessionsInputDescribePlayerSessionsPaginateTypeDef = TypedDict(
-    "DescribePlayerSessionsInputDescribePlayerSessionsPaginateTypeDef",
-    {
-        "GameSessionId": str,
-        "PlayerId": str,
-        "PlayerSessionId": str,
-        "PlayerSessionStatusFilter": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeScalingPoliciesInputDescribeScalingPoliciesPaginateTypeDef = TypedDict(
-    "_RequiredDescribeScalingPoliciesInputDescribeScalingPoliciesPaginateTypeDef",
-    {
-        "FleetId": str,
-    },
-)
-_OptionalDescribeScalingPoliciesInputDescribeScalingPoliciesPaginateTypeDef = TypedDict(
-    "_OptionalDescribeScalingPoliciesInputDescribeScalingPoliciesPaginateTypeDef",
-    {
-        "StatusFilter": ScalingStatusTypeType,
-        "Location": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeScalingPoliciesInputDescribeScalingPoliciesPaginateTypeDef(
-    _RequiredDescribeScalingPoliciesInputDescribeScalingPoliciesPaginateTypeDef,
-    _OptionalDescribeScalingPoliciesInputDescribeScalingPoliciesPaginateTypeDef,
-):
-    pass
-
-
-ListAliasesInputListAliasesPaginateTypeDef = TypedDict(
-    "ListAliasesInputListAliasesPaginateTypeDef",
-    {
-        "RoutingStrategyType": RoutingStrategyTypeType,
-        "Name": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListBuildsInputListBuildsPaginateTypeDef = TypedDict(
-    "ListBuildsInputListBuildsPaginateTypeDef",
-    {
-        "Status": BuildStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListComputeInputListComputePaginateTypeDef = TypedDict(
-    "_RequiredListComputeInputListComputePaginateTypeDef",
-    {
-        "FleetId": str,
-    },
-)
-_OptionalListComputeInputListComputePaginateTypeDef = TypedDict(
-    "_OptionalListComputeInputListComputePaginateTypeDef",
-    {
-        "Location": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListComputeInputListComputePaginateTypeDef(
-    _RequiredListComputeInputListComputePaginateTypeDef,
-    _OptionalListComputeInputListComputePaginateTypeDef,
-):
-    pass
-
-
-ListFleetsInputListFleetsPaginateTypeDef = TypedDict(
-    "ListFleetsInputListFleetsPaginateTypeDef",
-    {
-        "BuildId": str,
-        "ScriptId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListGameServerGroupsInputListGameServerGroupsPaginateTypeDef = TypedDict(
-    "ListGameServerGroupsInputListGameServerGroupsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListGameServersInputListGameServersPaginateTypeDef = TypedDict(
-    "_RequiredListGameServersInputListGameServersPaginateTypeDef",
-    {
-        "GameServerGroupName": str,
-    },
-)
-_OptionalListGameServersInputListGameServersPaginateTypeDef = TypedDict(
-    "_OptionalListGameServersInputListGameServersPaginateTypeDef",
-    {
-        "SortOrder": SortOrderType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListGameServersInputListGameServersPaginateTypeDef(
-    _RequiredListGameServersInputListGameServersPaginateTypeDef,
-    _OptionalListGameServersInputListGameServersPaginateTypeDef,
-):
-    pass
-
-
-ListLocationsInputListLocationsPaginateTypeDef = TypedDict(
-    "ListLocationsInputListLocationsPaginateTypeDef",
-    {
-        "Filters": Sequence[LocationFilterType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListScriptsInputListScriptsPaginateTypeDef = TypedDict(
-    "ListScriptsInputListScriptsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-SearchGameSessionsInputSearchGameSessionsPaginateTypeDef = TypedDict(
-    "SearchGameSessionsInputSearchGameSessionsPaginateTypeDef",
-    {
-        "FleetId": str,
-        "AliasId": str,
-        "Location": str,
-        "FilterExpression": str,
-        "SortExpression": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 DescribeFleetEventsOutputTypeDef = TypedDict(
     "DescribeFleetEventsOutputTypeDef",
     {
         "Events": List[EventTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFleetLocationUtilizationOutputTypeDef = TypedDict(
     "DescribeFleetLocationUtilizationOutputTypeDef",
     {
         "FleetUtilization": FleetUtilizationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFleetUtilizationOutputTypeDef = TypedDict(
     "DescribeFleetUtilizationOutputTypeDef",
     {
         "FleetUtilization": List[FleetUtilizationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeGameServerInstancesOutputTypeDef = TypedDict(
     "DescribeGameServerInstancesOutputTypeDef",
     {
         "GameServerInstances": List[GameServerInstanceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeInstancesOutputTypeDef = TypedDict(
     "DescribeInstancesOutputTypeDef",
     {
         "Instances": List[InstanceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FleetCapacityTypeDef = TypedDict(
     "FleetCapacityTypeDef",
     {
         "FleetId": str,
@@ -3057,22 +2983,20 @@
     "_OptionalGameServerGroupAutoScalingPolicyTypeDef",
     {
         "EstimatedInstanceWarmup": int,
     },
     total=False,
 )
 
-
 class GameServerGroupAutoScalingPolicyTypeDef(
     _RequiredGameServerGroupAutoScalingPolicyTypeDef,
     _OptionalGameServerGroupAutoScalingPolicyTypeDef,
 ):
     pass
 
-
 GameSessionConnectionInfoTypeDef = TypedDict(
     "GameSessionConnectionInfoTypeDef",
     {
         "GameSessionArn": str,
         "IpAddress": str,
         "DnsName": str,
         "Port": int,
@@ -3122,22 +3046,20 @@
         "PlayerLatencies": Sequence[PlayerLatencyTypeDef],
         "DesiredPlayerSessions": Sequence[DesiredPlayerSessionTypeDef],
         "GameSessionData": str,
     },
     total=False,
 )
 
-
 class StartGameSessionPlacementInputRequestTypeDef(
     _RequiredStartGameSessionPlacementInputRequestTypeDef,
     _OptionalStartGameSessionPlacementInputRequestTypeDef,
 ):
     pass
 
-
 InstanceAccessTypeDef = TypedDict(
     "InstanceAccessTypeDef",
     {
         "FleetId": str,
         "InstanceId": str,
         "IpAddress": str,
         "OperatingSystem": OperatingSystemType,
@@ -3164,21 +3086,19 @@
         "EvaluationPeriods": int,
         "PolicyType": PolicyTypeType,
         "TargetConfiguration": TargetConfigurationTypeDef,
     },
     total=False,
 )
 
-
 class PutScalingPolicyInputRequestTypeDef(
     _RequiredPutScalingPolicyInputRequestTypeDef, _OptionalPutScalingPolicyInputRequestTypeDef
 ):
     pass
 
-
 ScalingPolicyTypeDef = TypedDict(
     "ScalingPolicyTypeDef",
     {
         "FleetId": str,
         "FleetArn": str,
         "Name": str,
         "Status": ScalingStatusTypeType,
@@ -3220,40 +3140,40 @@
     total=False,
 )
 
 CreateAliasOutputTypeDef = TypedDict(
     "CreateAliasOutputTypeDef",
     {
         "Alias": AliasTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAliasOutputTypeDef = TypedDict(
     "DescribeAliasOutputTypeDef",
     {
         "Alias": AliasTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAliasesOutputTypeDef = TypedDict(
     "ListAliasesOutputTypeDef",
     {
         "Aliases": List[AliasTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAliasOutputTypeDef = TypedDict(
     "UpdateAliasOutputTypeDef",
     {
         "Alias": AliasTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStartMatchBackfillInputRequestTypeDef = TypedDict(
     "_RequiredStartMatchBackfillInputRequestTypeDef",
     {
         "ConfigurationName": str,
@@ -3265,21 +3185,19 @@
     {
         "TicketId": str,
         "GameSessionArn": str,
     },
     total=False,
 )
 
-
 class StartMatchBackfillInputRequestTypeDef(
     _RequiredStartMatchBackfillInputRequestTypeDef, _OptionalStartMatchBackfillInputRequestTypeDef
 ):
     pass
 
-
 _RequiredStartMatchmakingInputRequestTypeDef = TypedDict(
     "_RequiredStartMatchmakingInputRequestTypeDef",
     {
         "ConfigurationName": str,
         "Players": Sequence[PlayerTypeDef],
     },
 )
@@ -3287,154 +3205,152 @@
     "_OptionalStartMatchmakingInputRequestTypeDef",
     {
         "TicketId": str,
     },
     total=False,
 )
 
-
 class StartMatchmakingInputRequestTypeDef(
     _RequiredStartMatchmakingInputRequestTypeDef, _OptionalStartMatchmakingInputRequestTypeDef
 ):
     pass
 
-
 CreateScriptOutputTypeDef = TypedDict(
     "CreateScriptOutputTypeDef",
     {
         "Script": ScriptTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeScriptOutputTypeDef = TypedDict(
     "DescribeScriptOutputTypeDef",
     {
         "Script": ScriptTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListScriptsOutputTypeDef = TypedDict(
     "ListScriptsOutputTypeDef",
     {
         "Scripts": List[ScriptTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateScriptOutputTypeDef = TypedDict(
     "UpdateScriptOutputTypeDef",
     {
         "Script": ScriptTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateFleetOutputTypeDef = TypedDict(
     "CreateFleetOutputTypeDef",
     {
         "FleetAttributes": FleetAttributesTypeDef,
         "LocationStates": List[LocationStateTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFleetAttributesOutputTypeDef = TypedDict(
     "DescribeFleetAttributesOutputTypeDef",
     {
         "FleetAttributes": List[FleetAttributesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFleetLocationAttributesOutputTypeDef = TypedDict(
     "DescribeFleetLocationAttributesOutputTypeDef",
     {
         "FleetId": str,
         "FleetArn": str,
         "LocationAttributes": List[LocationAttributesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateGameServerGroupOutputTypeDef = TypedDict(
     "CreateGameServerGroupOutputTypeDef",
     {
         "GameServerGroup": GameServerGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteGameServerGroupOutputTypeDef = TypedDict(
     "DeleteGameServerGroupOutputTypeDef",
     {
         "GameServerGroup": GameServerGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeGameServerGroupOutputTypeDef = TypedDict(
     "DescribeGameServerGroupOutputTypeDef",
     {
         "GameServerGroup": GameServerGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListGameServerGroupsOutputTypeDef = TypedDict(
     "ListGameServerGroupsOutputTypeDef",
     {
         "GameServerGroups": List[GameServerGroupTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResumeGameServerGroupOutputTypeDef = TypedDict(
     "ResumeGameServerGroupOutputTypeDef",
     {
         "GameServerGroup": GameServerGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SuspendGameServerGroupOutputTypeDef = TypedDict(
     "SuspendGameServerGroupOutputTypeDef",
     {
         "GameServerGroup": GameServerGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateGameServerGroupOutputTypeDef = TypedDict(
     "UpdateGameServerGroupOutputTypeDef",
     {
         "GameServerGroup": GameServerGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateGameSessionOutputTypeDef = TypedDict(
     "CreateGameSessionOutputTypeDef",
     {
         "GameSession": GameSessionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeGameSessionsOutputTypeDef = TypedDict(
     "DescribeGameSessionsOutputTypeDef",
     {
         "GameSessions": List[GameSessionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GameSessionDetailTypeDef = TypedDict(
     "GameSessionDetailTypeDef",
     {
         "GameSession": GameSessionTypeDef,
@@ -3444,90 +3360,90 @@
 )
 
 SearchGameSessionsOutputTypeDef = TypedDict(
     "SearchGameSessionsOutputTypeDef",
     {
         "GameSessions": List[GameSessionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateGameSessionOutputTypeDef = TypedDict(
     "UpdateGameSessionOutputTypeDef",
     {
         "GameSession": GameSessionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateMatchmakingConfigurationOutputTypeDef = TypedDict(
     "CreateMatchmakingConfigurationOutputTypeDef",
     {
         "Configuration": MatchmakingConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeMatchmakingConfigurationsOutputTypeDef = TypedDict(
     "DescribeMatchmakingConfigurationsOutputTypeDef",
     {
         "Configurations": List[MatchmakingConfigurationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateMatchmakingConfigurationOutputTypeDef = TypedDict(
     "UpdateMatchmakingConfigurationOutputTypeDef",
     {
         "Configuration": MatchmakingConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateGameSessionQueueOutputTypeDef = TypedDict(
     "CreateGameSessionQueueOutputTypeDef",
     {
         "GameSessionQueue": GameSessionQueueTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeGameSessionQueuesOutputTypeDef = TypedDict(
     "DescribeGameSessionQueuesOutputTypeDef",
     {
         "GameSessionQueues": List[GameSessionQueueTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateGameSessionQueueOutputTypeDef = TypedDict(
     "UpdateGameSessionQueueOutputTypeDef",
     {
         "GameSessionQueue": GameSessionQueueTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFleetCapacityOutputTypeDef = TypedDict(
     "DescribeFleetCapacityOutputTypeDef",
     {
         "FleetCapacity": List[FleetCapacityTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFleetLocationCapacityOutputTypeDef = TypedDict(
     "DescribeFleetLocationCapacityOutputTypeDef",
     {
         "FleetCapacity": FleetCapacityTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateGameServerGroupInputRequestTypeDef = TypedDict(
     "_RequiredCreateGameServerGroupInputRequestTypeDef",
     {
         "GameServerGroupName": str,
@@ -3546,22 +3462,20 @@
         "GameServerProtectionPolicy": GameServerProtectionPolicyType,
         "VpcSubnets": Sequence[str],
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
-
 class CreateGameServerGroupInputRequestTypeDef(
     _RequiredCreateGameServerGroupInputRequestTypeDef,
     _OptionalCreateGameServerGroupInputRequestTypeDef,
 ):
     pass
 
-
 MatchmakingTicketTypeDef = TypedDict(
     "MatchmakingTicketTypeDef",
     {
         "TicketId": str,
         "ConfigurationName": str,
         "ConfigurationArn": str,
         "Status": MatchmakingConfigurationStatusType,
@@ -3576,48 +3490,48 @@
     total=False,
 )
 
 DescribeGameSessionPlacementOutputTypeDef = TypedDict(
     "DescribeGameSessionPlacementOutputTypeDef",
     {
         "GameSessionPlacement": GameSessionPlacementTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartGameSessionPlacementOutputTypeDef = TypedDict(
     "StartGameSessionPlacementOutputTypeDef",
     {
         "GameSessionPlacement": GameSessionPlacementTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopGameSessionPlacementOutputTypeDef = TypedDict(
     "StopGameSessionPlacementOutputTypeDef",
     {
         "GameSessionPlacement": GameSessionPlacementTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetInstanceAccessOutputTypeDef = TypedDict(
     "GetInstanceAccessOutputTypeDef",
     {
         "InstanceAccess": InstanceAccessTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeScalingPoliciesOutputTypeDef = TypedDict(
     "DescribeScalingPoliciesOutputTypeDef",
     {
         "ScalingPolicies": List[ScalingPolicyTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateFleetInputRequestTypeDef = TypedDict(
     "_RequiredCreateFleetInputRequestTypeDef",
     {
         "Name": str,
@@ -3647,26 +3561,24 @@
         "Tags": Sequence[TagTypeDef],
         "ComputeType": ComputeTypeType,
         "AnywhereConfiguration": AnywhereConfigurationTypeDef,
     },
     total=False,
 )
 
-
 class CreateFleetInputRequestTypeDef(
     _RequiredCreateFleetInputRequestTypeDef, _OptionalCreateFleetInputRequestTypeDef
 ):
     pass
 
-
 DescribeRuntimeConfigurationOutputTypeDef = TypedDict(
     "DescribeRuntimeConfigurationOutputTypeDef",
     {
         "RuntimeConfiguration": RuntimeConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateRuntimeConfigurationInputRequestTypeDef = TypedDict(
     "UpdateRuntimeConfigurationInputRequestTypeDef",
     {
         "FleetId": str,
@@ -3674,51 +3586,51 @@
     },
 )
 
 UpdateRuntimeConfigurationOutputTypeDef = TypedDict(
     "UpdateRuntimeConfigurationOutputTypeDef",
     {
         "RuntimeConfiguration": RuntimeConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeVpcPeeringConnectionsOutputTypeDef = TypedDict(
     "DescribeVpcPeeringConnectionsOutputTypeDef",
     {
         "VpcPeeringConnections": List[VpcPeeringConnectionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeGameSessionDetailsOutputTypeDef = TypedDict(
     "DescribeGameSessionDetailsOutputTypeDef",
     {
         "GameSessionDetails": List[GameSessionDetailTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeMatchmakingOutputTypeDef = TypedDict(
     "DescribeMatchmakingOutputTypeDef",
     {
         "TicketList": List[MatchmakingTicketTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartMatchBackfillOutputTypeDef = TypedDict(
     "StartMatchBackfillOutputTypeDef",
     {
         "MatchmakingTicket": MatchmakingTicketTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartMatchmakingOutputTypeDef = TypedDict(
     "StartMatchmakingOutputTypeDef",
     {
         "MatchmakingTicket": MatchmakingTicketTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-gamelift-2.5.0.post1/types_aiobotocore_gamelift/type_defs.pyi` & `types-aiobotocore-gamelift-2.5.1/types_aiobotocore_gamelift/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -24,14 +24,15 @@
     BuildStatusType,
     CertificateTypeType,
     ComparisonOperatorTypeType,
     ComputeStatusType,
     ComputeTypeType,
     EC2InstanceTypeType,
     EventCodeType,
+    FilterInstanceStatusType,
     FleetStatusType,
     FleetTypeType,
     FlexMatchModeType,
     GameServerGroupDeleteOptionType,
     GameServerGroupInstanceTypeType,
     GameServerGroupStatusType,
     GameServerInstanceStatusType,
@@ -61,25 +62,25 @@
 else:
     from typing_extensions import Literal
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
+
 __all__ = (
     "AcceptMatchInputRequestTypeDef",
     "RoutingStrategyTypeDef",
     "AnywhereConfigurationTypeDef",
     "AttributeValueTypeDef",
     "AwsCredentialsTypeDef",
     "BuildTypeDef",
     "CertificateConfigurationTypeDef",
-    "ClaimGameServerInputRequestTypeDef",
+    "ClaimFilterOptionTypeDef",
     "GameServerTypeDef",
-    "ResponseMetadataTypeDef",
     "ComputeTypeDef",
     "TagTypeDef",
     "S3LocationTypeDef",
     "IpPermissionTypeDef",
     "LocationConfigurationTypeDef",
     "ResourceCreationLimitPolicyTypeDef",
     "LocationStateTypeDef",
@@ -114,107 +115,131 @@
     "DeregisterComputeInputRequestTypeDef",
     "DeregisterGameServerInputRequestTypeDef",
     "DescribeAliasInputRequestTypeDef",
     "DescribeBuildInputRequestTypeDef",
     "DescribeComputeInputRequestTypeDef",
     "DescribeEC2InstanceLimitsInputRequestTypeDef",
     "EC2InstanceLimitTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeFleetAttributesInputDescribeFleetAttributesPaginateTypeDef",
     "DescribeFleetAttributesInputRequestTypeDef",
+    "DescribeFleetCapacityInputDescribeFleetCapacityPaginateTypeDef",
     "DescribeFleetCapacityInputRequestTypeDef",
+    "DescribeFleetEventsInputDescribeFleetEventsPaginateTypeDef",
     "DescribeFleetEventsInputRequestTypeDef",
     "EventTypeDef",
     "DescribeFleetLocationAttributesInputRequestTypeDef",
     "DescribeFleetLocationCapacityInputRequestTypeDef",
     "DescribeFleetLocationUtilizationInputRequestTypeDef",
     "FleetUtilizationTypeDef",
     "DescribeFleetPortSettingsInputRequestTypeDef",
+    "DescribeFleetUtilizationInputDescribeFleetUtilizationPaginateTypeDef",
     "DescribeFleetUtilizationInputRequestTypeDef",
     "DescribeGameServerGroupInputRequestTypeDef",
     "DescribeGameServerInputRequestTypeDef",
+    "DescribeGameServerInstancesInputDescribeGameServerInstancesPaginateTypeDef",
     "DescribeGameServerInstancesInputRequestTypeDef",
     "GameServerInstanceTypeDef",
+    "DescribeGameSessionDetailsInputDescribeGameSessionDetailsPaginateTypeDef",
     "DescribeGameSessionDetailsInputRequestTypeDef",
     "DescribeGameSessionPlacementInputRequestTypeDef",
+    "DescribeGameSessionQueuesInputDescribeGameSessionQueuesPaginateTypeDef",
     "DescribeGameSessionQueuesInputRequestTypeDef",
+    "DescribeGameSessionsInputDescribeGameSessionsPaginateTypeDef",
     "DescribeGameSessionsInputRequestTypeDef",
+    "DescribeInstancesInputDescribeInstancesPaginateTypeDef",
     "DescribeInstancesInputRequestTypeDef",
     "InstanceTypeDef",
+    "DescribeMatchmakingConfigurationsInputDescribeMatchmakingConfigurationsPaginateTypeDef",
     "DescribeMatchmakingConfigurationsInputRequestTypeDef",
     "DescribeMatchmakingInputRequestTypeDef",
+    "DescribeMatchmakingRuleSetsInputDescribeMatchmakingRuleSetsPaginateTypeDef",
     "DescribeMatchmakingRuleSetsInputRequestTypeDef",
+    "DescribePlayerSessionsInputDescribePlayerSessionsPaginateTypeDef",
     "DescribePlayerSessionsInputRequestTypeDef",
     "DescribeRuntimeConfigurationInputRequestTypeDef",
+    "DescribeScalingPoliciesInputDescribeScalingPoliciesPaginateTypeDef",
     "DescribeScalingPoliciesInputRequestTypeDef",
     "DescribeScriptInputRequestTypeDef",
     "DescribeVpcPeeringConnectionsInputRequestTypeDef",
     "DesiredPlayerSessionTypeDef",
     "EC2InstanceCountsTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "TargetTrackingConfigurationTypeDef",
     "MatchedPlayerSessionTypeDef",
     "PlacedPlayerSessionTypeDef",
     "PlayerLatencyTypeDef",
     "GetComputeAccessInputRequestTypeDef",
     "GetComputeAuthTokenInputRequestTypeDef",
+    "GetComputeAuthTokenOutputTypeDef",
     "GetGameSessionLogUrlInputRequestTypeDef",
+    "GetGameSessionLogUrlOutputTypeDef",
     "GetInstanceAccessInputRequestTypeDef",
     "InstanceCredentialsTypeDef",
+    "ListAliasesInputListAliasesPaginateTypeDef",
     "ListAliasesInputRequestTypeDef",
+    "ListBuildsInputListBuildsPaginateTypeDef",
     "ListBuildsInputRequestTypeDef",
+    "ListComputeInputListComputePaginateTypeDef",
     "ListComputeInputRequestTypeDef",
+    "ListFleetsInputListFleetsPaginateTypeDef",
     "ListFleetsInputRequestTypeDef",
+    "ListFleetsOutputTypeDef",
+    "ListGameServerGroupsInputListGameServerGroupsPaginateTypeDef",
     "ListGameServerGroupsInputRequestTypeDef",
+    "ListGameServersInputListGameServersPaginateTypeDef",
     "ListGameServersInputRequestTypeDef",
+    "ListLocationsInputListLocationsPaginateTypeDef",
     "ListLocationsInputRequestTypeDef",
+    "ListScriptsInputListScriptsPaginateTypeDef",
     "ListScriptsInputRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "TargetConfigurationTypeDef",
+    "PutScalingPolicyOutputTypeDef",
     "RegisterComputeInputRequestTypeDef",
     "RegisterGameServerInputRequestTypeDef",
     "RequestUploadCredentialsInputRequestTypeDef",
     "ResolveAliasInputRequestTypeDef",
+    "ResolveAliasOutputTypeDef",
+    "ResponseMetadataTypeDef",
     "ResumeGameServerGroupInputRequestTypeDef",
     "ServerProcessTypeDef",
     "SearchGameSessionsInputRequestTypeDef",
+    "SearchGameSessionsInputSearchGameSessionsPaginateTypeDef",
     "StartFleetActionsInputRequestTypeDef",
+    "StartFleetActionsOutputTypeDef",
     "StopFleetActionsInputRequestTypeDef",
+    "StopFleetActionsOutputTypeDef",
     "StopGameSessionPlacementInputRequestTypeDef",
     "StopMatchmakingInputRequestTypeDef",
     "SuspendGameServerGroupInputRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateBuildInputRequestTypeDef",
+    "UpdateFleetAttributesOutputTypeDef",
     "UpdateFleetCapacityInputRequestTypeDef",
+    "UpdateFleetCapacityOutputTypeDef",
+    "UpdateFleetPortSettingsOutputTypeDef",
     "UpdateGameServerInputRequestTypeDef",
     "UpdateGameSessionInputRequestTypeDef",
     "ValidateMatchmakingRuleSetInputRequestTypeDef",
+    "ValidateMatchmakingRuleSetOutputTypeDef",
     "VpcPeeringConnectionStatusTypeDef",
     "AliasTypeDef",
     "UpdateAliasInputRequestTypeDef",
     "PlayerTypeDef",
-    "ClaimGameServerOutputTypeDef",
-    "DescribeBuildOutputTypeDef",
-    "DescribeGameServerOutputTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "GetComputeAccessOutputTypeDef",
-    "GetComputeAuthTokenOutputTypeDef",
-    "GetGameSessionLogUrlOutputTypeDef",
+    "DescribeBuildOutputTypeDef",
     "ListBuildsOutputTypeDef",
-    "ListFleetsOutputTypeDef",
+    "UpdateBuildOutputTypeDef",
+    "ClaimGameServerInputRequestTypeDef",
+    "ClaimGameServerOutputTypeDef",
+    "DescribeGameServerOutputTypeDef",
     "ListGameServersOutputTypeDef",
-    "PutScalingPolicyOutputTypeDef",
     "RegisterGameServerOutputTypeDef",
-    "ResolveAliasOutputTypeDef",
-    "StartFleetActionsOutputTypeDef",
-    "StopFleetActionsOutputTypeDef",
-    "UpdateBuildOutputTypeDef",
-    "UpdateFleetAttributesOutputTypeDef",
-    "UpdateFleetCapacityOutputTypeDef",
-    "UpdateFleetPortSettingsOutputTypeDef",
     "UpdateGameServerOutputTypeDef",
-    "ValidateMatchmakingRuleSetOutputTypeDef",
     "DescribeComputeOutputTypeDef",
     "ListComputeOutputTypeDef",
     "RegisterComputeOutputTypeDef",
     "CreateAliasInputRequestTypeDef",
     "CreateLocationInputRequestTypeDef",
     "CreateMatchmakingRuleSetInputRequestTypeDef",
     "ListTagsForResourceResponseTypeDef",
@@ -249,36 +274,14 @@
     "DescribeMatchmakingRuleSetsOutputTypeDef",
     "CreatePlayerSessionOutputTypeDef",
     "CreatePlayerSessionsOutputTypeDef",
     "DescribePlayerSessionsOutputTypeDef",
     "CreateVpcPeeringAuthorizationOutputTypeDef",
     "DescribeVpcPeeringAuthorizationsOutputTypeDef",
     "DescribeEC2InstanceLimitsOutputTypeDef",
-    "DescribeFleetAttributesInputDescribeFleetAttributesPaginateTypeDef",
-    "DescribeFleetCapacityInputDescribeFleetCapacityPaginateTypeDef",
-    "DescribeFleetEventsInputDescribeFleetEventsPaginateTypeDef",
-    "DescribeFleetUtilizationInputDescribeFleetUtilizationPaginateTypeDef",
-    "DescribeGameServerInstancesInputDescribeGameServerInstancesPaginateTypeDef",
-    "DescribeGameSessionDetailsInputDescribeGameSessionDetailsPaginateTypeDef",
-    "DescribeGameSessionQueuesInputDescribeGameSessionQueuesPaginateTypeDef",
-    "DescribeGameSessionsInputDescribeGameSessionsPaginateTypeDef",
-    "DescribeInstancesInputDescribeInstancesPaginateTypeDef",
-    "DescribeMatchmakingConfigurationsInputDescribeMatchmakingConfigurationsPaginateTypeDef",
-    "DescribeMatchmakingRuleSetsInputDescribeMatchmakingRuleSetsPaginateTypeDef",
-    "DescribePlayerSessionsInputDescribePlayerSessionsPaginateTypeDef",
-    "DescribeScalingPoliciesInputDescribeScalingPoliciesPaginateTypeDef",
-    "ListAliasesInputListAliasesPaginateTypeDef",
-    "ListBuildsInputListBuildsPaginateTypeDef",
-    "ListComputeInputListComputePaginateTypeDef",
-    "ListFleetsInputListFleetsPaginateTypeDef",
-    "ListGameServerGroupsInputListGameServerGroupsPaginateTypeDef",
-    "ListGameServersInputListGameServersPaginateTypeDef",
-    "ListLocationsInputListLocationsPaginateTypeDef",
-    "ListScriptsInputListScriptsPaginateTypeDef",
-    "SearchGameSessionsInputSearchGameSessionsPaginateTypeDef",
     "DescribeFleetEventsOutputTypeDef",
     "DescribeFleetLocationUtilizationOutputTypeDef",
     "DescribeFleetUtilizationOutputTypeDef",
     "DescribeGameServerInstancesOutputTypeDef",
     "DescribeInstancesOutputTypeDef",
     "FleetCapacityTypeDef",
     "GameServerGroupAutoScalingPolicyTypeDef",
@@ -407,34 +410,22 @@
 CertificateConfigurationTypeDef = TypedDict(
     "CertificateConfigurationTypeDef",
     {
         "CertificateType": CertificateTypeType,
     },
 )
 
-_RequiredClaimGameServerInputRequestTypeDef = TypedDict(
-    "_RequiredClaimGameServerInputRequestTypeDef",
+ClaimFilterOptionTypeDef = TypedDict(
+    "ClaimFilterOptionTypeDef",
     {
-        "GameServerGroupName": str,
-    },
-)
-_OptionalClaimGameServerInputRequestTypeDef = TypedDict(
-    "_OptionalClaimGameServerInputRequestTypeDef",
-    {
-        "GameServerId": str,
-        "GameServerData": str,
+        "InstanceStatuses": Sequence[FilterInstanceStatusType],
     },
     total=False,
 )
 
-class ClaimGameServerInputRequestTypeDef(
-    _RequiredClaimGameServerInputRequestTypeDef, _OptionalClaimGameServerInputRequestTypeDef
-):
-    pass
-
 GameServerTypeDef = TypedDict(
     "GameServerTypeDef",
     {
         "GameServerGroupName": str,
         "GameServerGroupArn": str,
         "GameServerId": str,
         "InstanceId": str,
@@ -445,25 +436,14 @@
         "RegistrationTime": datetime,
         "LastClaimTime": datetime,
         "LastHealthCheckTime": datetime,
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
 ComputeTypeDef = TypedDict(
     "ComputeTypeDef",
     {
         "FleetId": str,
         "FleetArn": str,
         "ComputeName": str,
         "ComputeArn": str,
@@ -543,19 +523,21 @@
     "_OptionalInstanceDefinitionTypeDef",
     {
         "WeightedCapacity": str,
     },
     total=False,
 )
 
+
 class InstanceDefinitionTypeDef(
     _RequiredInstanceDefinitionTypeDef, _OptionalInstanceDefinitionTypeDef
 ):
     pass
 
+
 LaunchTemplateSpecificationTypeDef = TypedDict(
     "LaunchTemplateSpecificationTypeDef",
     {
         "LaunchTemplateId": str,
         "LaunchTemplateName": str,
         "Version": str,
     },
@@ -625,19 +607,21 @@
         "RuleSetName": str,
         "RuleSetArn": str,
         "CreationTime": datetime,
     },
     total=False,
 )
 
+
 class MatchmakingRuleSetTypeDef(
     _RequiredMatchmakingRuleSetTypeDef, _OptionalMatchmakingRuleSetTypeDef
 ):
     pass
 
+
 _RequiredCreatePlayerSessionInputRequestTypeDef = TypedDict(
     "_RequiredCreatePlayerSessionInputRequestTypeDef",
     {
         "GameSessionId": str,
         "PlayerId": str,
     },
 )
@@ -645,19 +629,21 @@
     "_OptionalCreatePlayerSessionInputRequestTypeDef",
     {
         "PlayerData": str,
     },
     total=False,
 )
 
+
 class CreatePlayerSessionInputRequestTypeDef(
     _RequiredCreatePlayerSessionInputRequestTypeDef, _OptionalCreatePlayerSessionInputRequestTypeDef
 ):
     pass
 
+
 PlayerSessionTypeDef = TypedDict(
     "PlayerSessionTypeDef",
     {
         "PlayerSessionId": str,
         "PlayerId": str,
         "GameSessionId": str,
         "FleetId": str,
@@ -684,20 +670,22 @@
     "_OptionalCreatePlayerSessionsInputRequestTypeDef",
     {
         "PlayerDataMap": Mapping[str, str],
     },
     total=False,
 )
 
+
 class CreatePlayerSessionsInputRequestTypeDef(
     _RequiredCreatePlayerSessionsInputRequestTypeDef,
     _OptionalCreatePlayerSessionsInputRequestTypeDef,
 ):
     pass
 
+
 CreateVpcPeeringAuthorizationInputRequestTypeDef = TypedDict(
     "CreateVpcPeeringAuthorizationInputRequestTypeDef",
     {
         "GameLiftAwsAccountId": str,
         "PeerVpcId": str,
     },
 )
@@ -762,20 +750,22 @@
     "_OptionalDeleteGameServerGroupInputRequestTypeDef",
     {
         "DeleteOption": GameServerGroupDeleteOptionType,
     },
     total=False,
 )
 
+
 class DeleteGameServerGroupInputRequestTypeDef(
     _RequiredDeleteGameServerGroupInputRequestTypeDef,
     _OptionalDeleteGameServerGroupInputRequestTypeDef,
 ):
     pass
 
+
 DeleteGameSessionQueueInputRequestTypeDef = TypedDict(
     "DeleteGameSessionQueueInputRequestTypeDef",
     {
         "Name": str,
     },
 )
 
@@ -885,44 +875,76 @@
         "CurrentInstances": int,
         "InstanceLimit": int,
         "Location": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeFleetAttributesInputDescribeFleetAttributesPaginateTypeDef = TypedDict(
+    "DescribeFleetAttributesInputDescribeFleetAttributesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "FleetIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeFleetAttributesInputRequestTypeDef = TypedDict(
     "DescribeFleetAttributesInputRequestTypeDef",
     {
         "FleetIds": Sequence[str],
         "Limit": int,
         "NextToken": str,
     },
     total=False,
 )
 
+DescribeFleetCapacityInputDescribeFleetCapacityPaginateTypeDef = TypedDict(
+    "DescribeFleetCapacityInputDescribeFleetCapacityPaginateTypeDef",
+    {
+        "FleetIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeFleetCapacityInputRequestTypeDef = TypedDict(
     "DescribeFleetCapacityInputRequestTypeDef",
     {
         "FleetIds": Sequence[str],
         "Limit": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredDescribeFleetEventsInputDescribeFleetEventsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeFleetEventsInputDescribeFleetEventsPaginateTypeDef",
+    {
+        "FleetId": str,
+    },
+)
+_OptionalDescribeFleetEventsInputDescribeFleetEventsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeFleetEventsInputDescribeFleetEventsPaginateTypeDef",
+    {
+        "StartTime": Union[datetime, str],
+        "EndTime": Union[datetime, str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeFleetEventsInputDescribeFleetEventsPaginateTypeDef(
+    _RequiredDescribeFleetEventsInputDescribeFleetEventsPaginateTypeDef,
+    _OptionalDescribeFleetEventsInputDescribeFleetEventsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeFleetEventsInputRequestTypeDef = TypedDict(
     "_RequiredDescribeFleetEventsInputRequestTypeDef",
     {
         "FleetId": str,
     },
 )
 _OptionalDescribeFleetEventsInputRequestTypeDef = TypedDict(
@@ -932,19 +954,21 @@
         "EndTime": Union[datetime, str],
         "Limit": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class DescribeFleetEventsInputRequestTypeDef(
     _RequiredDescribeFleetEventsInputRequestTypeDef, _OptionalDescribeFleetEventsInputRequestTypeDef
 ):
     pass
 
+
 EventTypeDef = TypedDict(
     "EventTypeDef",
     {
         "EventId": str,
         "ResourceId": str,
         "EventCode": EventCodeType,
         "Message": str,
@@ -966,20 +990,22 @@
         "Locations": Sequence[str],
         "Limit": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class DescribeFleetLocationAttributesInputRequestTypeDef(
     _RequiredDescribeFleetLocationAttributesInputRequestTypeDef,
     _OptionalDescribeFleetLocationAttributesInputRequestTypeDef,
 ):
     pass
 
+
 DescribeFleetLocationCapacityInputRequestTypeDef = TypedDict(
     "DescribeFleetLocationCapacityInputRequestTypeDef",
     {
         "FleetId": str,
         "Location": str,
     },
 )
@@ -1016,20 +1042,31 @@
     "_OptionalDescribeFleetPortSettingsInputRequestTypeDef",
     {
         "Location": str,
     },
     total=False,
 )
 
+
 class DescribeFleetPortSettingsInputRequestTypeDef(
     _RequiredDescribeFleetPortSettingsInputRequestTypeDef,
     _OptionalDescribeFleetPortSettingsInputRequestTypeDef,
 ):
     pass
 
+
+DescribeFleetUtilizationInputDescribeFleetUtilizationPaginateTypeDef = TypedDict(
+    "DescribeFleetUtilizationInputDescribeFleetUtilizationPaginateTypeDef",
+    {
+        "FleetIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeFleetUtilizationInputRequestTypeDef = TypedDict(
     "DescribeFleetUtilizationInputRequestTypeDef",
     {
         "FleetIds": Sequence[str],
         "Limit": int,
         "NextToken": str,
     },
@@ -1047,14 +1084,37 @@
     "DescribeGameServerInputRequestTypeDef",
     {
         "GameServerGroupName": str,
         "GameServerId": str,
     },
 )
 
+_RequiredDescribeGameServerInstancesInputDescribeGameServerInstancesPaginateTypeDef = TypedDict(
+    "_RequiredDescribeGameServerInstancesInputDescribeGameServerInstancesPaginateTypeDef",
+    {
+        "GameServerGroupName": str,
+    },
+)
+_OptionalDescribeGameServerInstancesInputDescribeGameServerInstancesPaginateTypeDef = TypedDict(
+    "_OptionalDescribeGameServerInstancesInputDescribeGameServerInstancesPaginateTypeDef",
+    {
+        "InstanceIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeGameServerInstancesInputDescribeGameServerInstancesPaginateTypeDef(
+    _RequiredDescribeGameServerInstancesInputDescribeGameServerInstancesPaginateTypeDef,
+    _OptionalDescribeGameServerInstancesInputDescribeGameServerInstancesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeGameServerInstancesInputRequestTypeDef = TypedDict(
     "_RequiredDescribeGameServerInstancesInputRequestTypeDef",
     {
         "GameServerGroupName": str,
     },
 )
 _OptionalDescribeGameServerInstancesInputRequestTypeDef = TypedDict(
@@ -1063,31 +1123,46 @@
         "InstanceIds": Sequence[str],
         "Limit": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class DescribeGameServerInstancesInputRequestTypeDef(
     _RequiredDescribeGameServerInstancesInputRequestTypeDef,
     _OptionalDescribeGameServerInstancesInputRequestTypeDef,
 ):
     pass
 
+
 GameServerInstanceTypeDef = TypedDict(
     "GameServerInstanceTypeDef",
     {
         "GameServerGroupName": str,
         "GameServerGroupArn": str,
         "InstanceId": str,
         "InstanceStatus": GameServerInstanceStatusType,
     },
     total=False,
 )
 
+DescribeGameSessionDetailsInputDescribeGameSessionDetailsPaginateTypeDef = TypedDict(
+    "DescribeGameSessionDetailsInputDescribeGameSessionDetailsPaginateTypeDef",
+    {
+        "FleetId": str,
+        "GameSessionId": str,
+        "AliasId": str,
+        "Location": str,
+        "StatusFilter": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeGameSessionDetailsInputRequestTypeDef = TypedDict(
     "DescribeGameSessionDetailsInputRequestTypeDef",
     {
         "FleetId": str,
         "GameSessionId": str,
         "AliasId": str,
         "Location": str,
@@ -1101,38 +1176,84 @@
 DescribeGameSessionPlacementInputRequestTypeDef = TypedDict(
     "DescribeGameSessionPlacementInputRequestTypeDef",
     {
         "PlacementId": str,
     },
 )
 
+DescribeGameSessionQueuesInputDescribeGameSessionQueuesPaginateTypeDef = TypedDict(
+    "DescribeGameSessionQueuesInputDescribeGameSessionQueuesPaginateTypeDef",
+    {
+        "Names": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeGameSessionQueuesInputRequestTypeDef = TypedDict(
     "DescribeGameSessionQueuesInputRequestTypeDef",
     {
         "Names": Sequence[str],
         "Limit": int,
         "NextToken": str,
     },
     total=False,
 )
 
+DescribeGameSessionsInputDescribeGameSessionsPaginateTypeDef = TypedDict(
+    "DescribeGameSessionsInputDescribeGameSessionsPaginateTypeDef",
+    {
+        "FleetId": str,
+        "GameSessionId": str,
+        "AliasId": str,
+        "Location": str,
+        "StatusFilter": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeGameSessionsInputRequestTypeDef = TypedDict(
     "DescribeGameSessionsInputRequestTypeDef",
     {
         "FleetId": str,
         "GameSessionId": str,
         "AliasId": str,
         "Location": str,
         "StatusFilter": str,
         "Limit": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredDescribeInstancesInputDescribeInstancesPaginateTypeDef = TypedDict(
+    "_RequiredDescribeInstancesInputDescribeInstancesPaginateTypeDef",
+    {
+        "FleetId": str,
+    },
+)
+_OptionalDescribeInstancesInputDescribeInstancesPaginateTypeDef = TypedDict(
+    "_OptionalDescribeInstancesInputDescribeInstancesPaginateTypeDef",
+    {
+        "InstanceId": str,
+        "Location": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeInstancesInputDescribeInstancesPaginateTypeDef(
+    _RequiredDescribeInstancesInputDescribeInstancesPaginateTypeDef,
+    _OptionalDescribeInstancesInputDescribeInstancesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeInstancesInputRequestTypeDef = TypedDict(
     "_RequiredDescribeInstancesInputRequestTypeDef",
     {
         "FleetId": str,
     },
 )
 _OptionalDescribeInstancesInputRequestTypeDef = TypedDict(
@@ -1142,19 +1263,21 @@
         "Limit": int,
         "NextToken": str,
         "Location": str,
     },
     total=False,
 )
 
+
 class DescribeInstancesInputRequestTypeDef(
     _RequiredDescribeInstancesInputRequestTypeDef, _OptionalDescribeInstancesInputRequestTypeDef
 ):
     pass
 
+
 InstanceTypeDef = TypedDict(
     "InstanceTypeDef",
     {
         "FleetId": str,
         "FleetArn": str,
         "InstanceId": str,
         "IpAddress": str,
@@ -1164,14 +1287,24 @@
         "Status": InstanceStatusType,
         "CreationTime": datetime,
         "Location": str,
     },
     total=False,
 )
 
+DescribeMatchmakingConfigurationsInputDescribeMatchmakingConfigurationsPaginateTypeDef = TypedDict(
+    "DescribeMatchmakingConfigurationsInputDescribeMatchmakingConfigurationsPaginateTypeDef",
+    {
+        "Names": Sequence[str],
+        "RuleSetName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeMatchmakingConfigurationsInputRequestTypeDef = TypedDict(
     "DescribeMatchmakingConfigurationsInputRequestTypeDef",
     {
         "Names": Sequence[str],
         "RuleSetName": str,
         "Limit": int,
         "NextToken": str,
@@ -1182,24 +1315,45 @@
 DescribeMatchmakingInputRequestTypeDef = TypedDict(
     "DescribeMatchmakingInputRequestTypeDef",
     {
         "TicketIds": Sequence[str],
     },
 )
 
+DescribeMatchmakingRuleSetsInputDescribeMatchmakingRuleSetsPaginateTypeDef = TypedDict(
+    "DescribeMatchmakingRuleSetsInputDescribeMatchmakingRuleSetsPaginateTypeDef",
+    {
+        "Names": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeMatchmakingRuleSetsInputRequestTypeDef = TypedDict(
     "DescribeMatchmakingRuleSetsInputRequestTypeDef",
     {
         "Names": Sequence[str],
         "Limit": int,
         "NextToken": str,
     },
     total=False,
 )
 
+DescribePlayerSessionsInputDescribePlayerSessionsPaginateTypeDef = TypedDict(
+    "DescribePlayerSessionsInputDescribePlayerSessionsPaginateTypeDef",
+    {
+        "GameSessionId": str,
+        "PlayerId": str,
+        "PlayerSessionId": str,
+        "PlayerSessionStatusFilter": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribePlayerSessionsInputRequestTypeDef = TypedDict(
     "DescribePlayerSessionsInputRequestTypeDef",
     {
         "GameSessionId": str,
         "PlayerId": str,
         "PlayerSessionId": str,
         "PlayerSessionStatusFilter": str,
@@ -1212,14 +1366,38 @@
 DescribeRuntimeConfigurationInputRequestTypeDef = TypedDict(
     "DescribeRuntimeConfigurationInputRequestTypeDef",
     {
         "FleetId": str,
     },
 )
 
+_RequiredDescribeScalingPoliciesInputDescribeScalingPoliciesPaginateTypeDef = TypedDict(
+    "_RequiredDescribeScalingPoliciesInputDescribeScalingPoliciesPaginateTypeDef",
+    {
+        "FleetId": str,
+    },
+)
+_OptionalDescribeScalingPoliciesInputDescribeScalingPoliciesPaginateTypeDef = TypedDict(
+    "_OptionalDescribeScalingPoliciesInputDescribeScalingPoliciesPaginateTypeDef",
+    {
+        "StatusFilter": ScalingStatusTypeType,
+        "Location": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeScalingPoliciesInputDescribeScalingPoliciesPaginateTypeDef(
+    _RequiredDescribeScalingPoliciesInputDescribeScalingPoliciesPaginateTypeDef,
+    _OptionalDescribeScalingPoliciesInputDescribeScalingPoliciesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeScalingPoliciesInputRequestTypeDef = TypedDict(
     "_RequiredDescribeScalingPoliciesInputRequestTypeDef",
     {
         "FleetId": str,
     },
 )
 _OptionalDescribeScalingPoliciesInputRequestTypeDef = TypedDict(
@@ -1229,20 +1407,22 @@
         "Limit": int,
         "NextToken": str,
         "Location": str,
     },
     total=False,
 )
 
+
 class DescribeScalingPoliciesInputRequestTypeDef(
     _RequiredDescribeScalingPoliciesInputRequestTypeDef,
     _OptionalDescribeScalingPoliciesInputRequestTypeDef,
 ):
     pass
 
+
 DescribeScriptInputRequestTypeDef = TypedDict(
     "DescribeScriptInputRequestTypeDef",
     {
         "ScriptId": str,
     },
 )
 
@@ -1273,14 +1453,21 @@
         "ACTIVE": int,
         "IDLE": int,
         "TERMINATING": int,
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
 TargetTrackingConfigurationTypeDef = TypedDict(
     "TargetTrackingConfigurationTypeDef",
     {
         "TargetValue": float,
     },
 )
 
@@ -1324,21 +1511,42 @@
     "GetComputeAuthTokenInputRequestTypeDef",
     {
         "FleetId": str,
         "ComputeName": str,
     },
 )
 
+GetComputeAuthTokenOutputTypeDef = TypedDict(
+    "GetComputeAuthTokenOutputTypeDef",
+    {
+        "FleetId": str,
+        "FleetArn": str,
+        "ComputeName": str,
+        "ComputeArn": str,
+        "AuthToken": str,
+        "ExpirationTimestamp": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetGameSessionLogUrlInputRequestTypeDef = TypedDict(
     "GetGameSessionLogUrlInputRequestTypeDef",
     {
         "GameSessionId": str,
     },
 )
 
+GetGameSessionLogUrlOutputTypeDef = TypedDict(
+    "GetGameSessionLogUrlOutputTypeDef",
+    {
+        "PreSignedUrl": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetInstanceAccessInputRequestTypeDef = TypedDict(
     "GetInstanceAccessInputRequestTypeDef",
     {
         "FleetId": str,
         "InstanceId": str,
     },
 )
@@ -1348,35 +1556,77 @@
     {
         "UserName": str,
         "Secret": str,
     },
     total=False,
 )
 
+ListAliasesInputListAliasesPaginateTypeDef = TypedDict(
+    "ListAliasesInputListAliasesPaginateTypeDef",
+    {
+        "RoutingStrategyType": RoutingStrategyTypeType,
+        "Name": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListAliasesInputRequestTypeDef = TypedDict(
     "ListAliasesInputRequestTypeDef",
     {
         "RoutingStrategyType": RoutingStrategyTypeType,
         "Name": str,
         "Limit": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListBuildsInputListBuildsPaginateTypeDef = TypedDict(
+    "ListBuildsInputListBuildsPaginateTypeDef",
+    {
+        "Status": BuildStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListBuildsInputRequestTypeDef = TypedDict(
     "ListBuildsInputRequestTypeDef",
     {
         "Status": BuildStatusType,
         "Limit": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredListComputeInputListComputePaginateTypeDef = TypedDict(
+    "_RequiredListComputeInputListComputePaginateTypeDef",
+    {
+        "FleetId": str,
+    },
+)
+_OptionalListComputeInputListComputePaginateTypeDef = TypedDict(
+    "_OptionalListComputeInputListComputePaginateTypeDef",
+    {
+        "Location": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListComputeInputListComputePaginateTypeDef(
+    _RequiredListComputeInputListComputePaginateTypeDef,
+    _OptionalListComputeInputListComputePaginateTypeDef,
+):
+    pass
+
+
 _RequiredListComputeInputRequestTypeDef = TypedDict(
     "_RequiredListComputeInputRequestTypeDef",
     {
         "FleetId": str,
     },
 )
 _OptionalListComputeInputRequestTypeDef = TypedDict(
@@ -1385,39 +1635,91 @@
         "Location": str,
         "Limit": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class ListComputeInputRequestTypeDef(
     _RequiredListComputeInputRequestTypeDef, _OptionalListComputeInputRequestTypeDef
 ):
     pass
 
+
+ListFleetsInputListFleetsPaginateTypeDef = TypedDict(
+    "ListFleetsInputListFleetsPaginateTypeDef",
+    {
+        "BuildId": str,
+        "ScriptId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListFleetsInputRequestTypeDef = TypedDict(
     "ListFleetsInputRequestTypeDef",
     {
         "BuildId": str,
         "ScriptId": str,
         "Limit": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListFleetsOutputTypeDef = TypedDict(
+    "ListFleetsOutputTypeDef",
+    {
+        "FleetIds": List[str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListGameServerGroupsInputListGameServerGroupsPaginateTypeDef = TypedDict(
+    "ListGameServerGroupsInputListGameServerGroupsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListGameServerGroupsInputRequestTypeDef = TypedDict(
     "ListGameServerGroupsInputRequestTypeDef",
     {
         "Limit": int,
         "NextToken": str,
     },
     total=False,
 )
 
+_RequiredListGameServersInputListGameServersPaginateTypeDef = TypedDict(
+    "_RequiredListGameServersInputListGameServersPaginateTypeDef",
+    {
+        "GameServerGroupName": str,
+    },
+)
+_OptionalListGameServersInputListGameServersPaginateTypeDef = TypedDict(
+    "_OptionalListGameServersInputListGameServersPaginateTypeDef",
+    {
+        "SortOrder": SortOrderType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListGameServersInputListGameServersPaginateTypeDef(
+    _RequiredListGameServersInputListGameServersPaginateTypeDef,
+    _OptionalListGameServersInputListGameServersPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListGameServersInputRequestTypeDef = TypedDict(
     "_RequiredListGameServersInputRequestTypeDef",
     {
         "GameServerGroupName": str,
     },
 )
 _OptionalListGameServersInputRequestTypeDef = TypedDict(
@@ -1426,29 +1728,48 @@
         "SortOrder": SortOrderType,
         "Limit": int,
         "NextToken": str,
     },
     total=False,
 )
 
+
 class ListGameServersInputRequestTypeDef(
     _RequiredListGameServersInputRequestTypeDef, _OptionalListGameServersInputRequestTypeDef
 ):
     pass
 
+
+ListLocationsInputListLocationsPaginateTypeDef = TypedDict(
+    "ListLocationsInputListLocationsPaginateTypeDef",
+    {
+        "Filters": Sequence[LocationFilterType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListLocationsInputRequestTypeDef = TypedDict(
     "ListLocationsInputRequestTypeDef",
     {
         "Filters": Sequence[LocationFilterType],
         "Limit": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListScriptsInputListScriptsPaginateTypeDef = TypedDict(
+    "ListScriptsInputListScriptsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListScriptsInputRequestTypeDef = TypedDict(
     "ListScriptsInputRequestTypeDef",
     {
         "Limit": int,
         "NextToken": str,
     },
     total=False,
@@ -1457,21 +1778,39 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceARN": str,
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
 TargetConfigurationTypeDef = TypedDict(
     "TargetConfigurationTypeDef",
     {
         "TargetValue": float,
     },
 )
 
+PutScalingPolicyOutputTypeDef = TypedDict(
+    "PutScalingPolicyOutputTypeDef",
+    {
+        "Name": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredRegisterComputeInputRequestTypeDef = TypedDict(
     "_RequiredRegisterComputeInputRequestTypeDef",
     {
         "FleetId": str,
         "ComputeName": str,
     },
 )
@@ -1482,19 +1821,21 @@
         "DnsName": str,
         "IpAddress": str,
         "Location": str,
     },
     total=False,
 )
 
+
 class RegisterComputeInputRequestTypeDef(
     _RequiredRegisterComputeInputRequestTypeDef, _OptionalRegisterComputeInputRequestTypeDef
 ):
     pass
 
+
 _RequiredRegisterGameServerInputRequestTypeDef = TypedDict(
     "_RequiredRegisterGameServerInputRequestTypeDef",
     {
         "GameServerGroupName": str,
         "GameServerId": str,
         "InstanceId": str,
     },
@@ -1504,33 +1845,55 @@
     {
         "ConnectionInfo": str,
         "GameServerData": str,
     },
     total=False,
 )
 
+
 class RegisterGameServerInputRequestTypeDef(
     _RequiredRegisterGameServerInputRequestTypeDef, _OptionalRegisterGameServerInputRequestTypeDef
 ):
     pass
 
+
 RequestUploadCredentialsInputRequestTypeDef = TypedDict(
     "RequestUploadCredentialsInputRequestTypeDef",
     {
         "BuildId": str,
     },
 )
 
 ResolveAliasInputRequestTypeDef = TypedDict(
     "ResolveAliasInputRequestTypeDef",
     {
         "AliasId": str,
     },
 )
 
+ResolveAliasOutputTypeDef = TypedDict(
+    "ResolveAliasOutputTypeDef",
+    {
+        "FleetId": str,
+        "FleetArn": str,
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
 ResumeGameServerGroupInputRequestTypeDef = TypedDict(
     "ResumeGameServerGroupInputRequestTypeDef",
     {
         "GameServerGroupName": str,
         "ResumeActions": Sequence[Literal["REPLACE_INSTANCE_TYPES"]],
     },
 )
@@ -1546,31 +1909,46 @@
     "_OptionalServerProcessTypeDef",
     {
         "Parameters": str,
     },
     total=False,
 )
 
+
 class ServerProcessTypeDef(_RequiredServerProcessTypeDef, _OptionalServerProcessTypeDef):
     pass
 
+
 SearchGameSessionsInputRequestTypeDef = TypedDict(
     "SearchGameSessionsInputRequestTypeDef",
     {
         "FleetId": str,
         "AliasId": str,
         "Location": str,
         "FilterExpression": str,
         "SortExpression": str,
         "Limit": int,
         "NextToken": str,
     },
     total=False,
 )
 
+SearchGameSessionsInputSearchGameSessionsPaginateTypeDef = TypedDict(
+    "SearchGameSessionsInputSearchGameSessionsPaginateTypeDef",
+    {
+        "FleetId": str,
+        "AliasId": str,
+        "Location": str,
+        "FilterExpression": str,
+        "SortExpression": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 _RequiredStartFleetActionsInputRequestTypeDef = TypedDict(
     "_RequiredStartFleetActionsInputRequestTypeDef",
     {
         "FleetId": str,
         "Actions": Sequence[Literal["AUTO_SCALING"]],
     },
 )
@@ -1578,19 +1956,30 @@
     "_OptionalStartFleetActionsInputRequestTypeDef",
     {
         "Location": str,
     },
     total=False,
 )
 
+
 class StartFleetActionsInputRequestTypeDef(
     _RequiredStartFleetActionsInputRequestTypeDef, _OptionalStartFleetActionsInputRequestTypeDef
 ):
     pass
 
+
+StartFleetActionsOutputTypeDef = TypedDict(
+    "StartFleetActionsOutputTypeDef",
+    {
+        "FleetId": str,
+        "FleetArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredStopFleetActionsInputRequestTypeDef = TypedDict(
     "_RequiredStopFleetActionsInputRequestTypeDef",
     {
         "FleetId": str,
         "Actions": Sequence[Literal["AUTO_SCALING"]],
     },
 )
@@ -1598,19 +1987,30 @@
     "_OptionalStopFleetActionsInputRequestTypeDef",
     {
         "Location": str,
     },
     total=False,
 )
 
+
 class StopFleetActionsInputRequestTypeDef(
     _RequiredStopFleetActionsInputRequestTypeDef, _OptionalStopFleetActionsInputRequestTypeDef
 ):
     pass
 
+
+StopFleetActionsOutputTypeDef = TypedDict(
+    "StopFleetActionsOutputTypeDef",
+    {
+        "FleetId": str,
+        "FleetArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StopGameSessionPlacementInputRequestTypeDef = TypedDict(
     "StopGameSessionPlacementInputRequestTypeDef",
     {
         "PlacementId": str,
     },
 )
 
@@ -1648,19 +2048,30 @@
     {
         "Name": str,
         "Version": str,
     },
     total=False,
 )
 
+
 class UpdateBuildInputRequestTypeDef(
     _RequiredUpdateBuildInputRequestTypeDef, _OptionalUpdateBuildInputRequestTypeDef
 ):
     pass
 
+
+UpdateFleetAttributesOutputTypeDef = TypedDict(
+    "UpdateFleetAttributesOutputTypeDef",
+    {
+        "FleetId": str,
+        "FleetArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateFleetCapacityInputRequestTypeDef = TypedDict(
     "_RequiredUpdateFleetCapacityInputRequestTypeDef",
     {
         "FleetId": str,
     },
 )
 _OptionalUpdateFleetCapacityInputRequestTypeDef = TypedDict(
@@ -1670,19 +2081,40 @@
         "MinSize": int,
         "MaxSize": int,
         "Location": str,
     },
     total=False,
 )
 
+
 class UpdateFleetCapacityInputRequestTypeDef(
     _RequiredUpdateFleetCapacityInputRequestTypeDef, _OptionalUpdateFleetCapacityInputRequestTypeDef
 ):
     pass
 
+
+UpdateFleetCapacityOutputTypeDef = TypedDict(
+    "UpdateFleetCapacityOutputTypeDef",
+    {
+        "FleetId": str,
+        "FleetArn": str,
+        "Location": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+UpdateFleetPortSettingsOutputTypeDef = TypedDict(
+    "UpdateFleetPortSettingsOutputTypeDef",
+    {
+        "FleetId": str,
+        "FleetArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateGameServerInputRequestTypeDef = TypedDict(
     "_RequiredUpdateGameServerInputRequestTypeDef",
     {
         "GameServerGroupName": str,
         "GameServerId": str,
     },
 )
@@ -1692,19 +2124,21 @@
         "GameServerData": str,
         "UtilizationStatus": GameServerUtilizationStatusType,
         "HealthCheck": Literal["HEALTHY"],
     },
     total=False,
 )
 
+
 class UpdateGameServerInputRequestTypeDef(
     _RequiredUpdateGameServerInputRequestTypeDef, _OptionalUpdateGameServerInputRequestTypeDef
 ):
     pass
 
+
 _RequiredUpdateGameSessionInputRequestTypeDef = TypedDict(
     "_RequiredUpdateGameSessionInputRequestTypeDef",
     {
         "GameSessionId": str,
     },
 )
 _OptionalUpdateGameSessionInputRequestTypeDef = TypedDict(
@@ -1714,26 +2148,36 @@
         "Name": str,
         "PlayerSessionCreationPolicy": PlayerSessionCreationPolicyType,
         "ProtectionPolicy": ProtectionPolicyType,
     },
     total=False,
 )
 
+
 class UpdateGameSessionInputRequestTypeDef(
     _RequiredUpdateGameSessionInputRequestTypeDef, _OptionalUpdateGameSessionInputRequestTypeDef
 ):
     pass
 
+
 ValidateMatchmakingRuleSetInputRequestTypeDef = TypedDict(
     "ValidateMatchmakingRuleSetInputRequestTypeDef",
     {
         "RuleSetBody": str,
     },
 )
 
+ValidateMatchmakingRuleSetOutputTypeDef = TypedDict(
+    "ValidateMatchmakingRuleSetOutputTypeDef",
+    {
+        "Valid": bool,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 VpcPeeringConnectionStatusTypeDef = TypedDict(
     "VpcPeeringConnectionStatusTypeDef",
     {
         "Code": str,
         "Message": str,
     },
     total=False,
@@ -1765,238 +2209,155 @@
         "Name": str,
         "Description": str,
         "RoutingStrategy": RoutingStrategyTypeDef,
     },
     total=False,
 )
 
+
 class UpdateAliasInputRequestTypeDef(
     _RequiredUpdateAliasInputRequestTypeDef, _OptionalUpdateAliasInputRequestTypeDef
 ):
     pass
 
+
 PlayerTypeDef = TypedDict(
     "PlayerTypeDef",
     {
         "PlayerId": str,
         "PlayerAttributes": Dict[str, AttributeValueTypeDef],
         "Team": str,
         "LatencyInMs": Dict[str, int],
     },
     total=False,
 )
 
-ClaimGameServerOutputTypeDef = TypedDict(
-    "ClaimGameServerOutputTypeDef",
-    {
-        "GameServer": GameServerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeBuildOutputTypeDef = TypedDict(
-    "DescribeBuildOutputTypeDef",
-    {
-        "Build": BuildTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeGameServerOutputTypeDef = TypedDict(
-    "DescribeGameServerOutputTypeDef",
-    {
-        "GameServer": GameServerTypeDef,
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
 GetComputeAccessOutputTypeDef = TypedDict(
     "GetComputeAccessOutputTypeDef",
     {
         "FleetId": str,
         "FleetArn": str,
         "ComputeName": str,
         "ComputeArn": str,
         "Credentials": AwsCredentialsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetComputeAuthTokenOutputTypeDef = TypedDict(
-    "GetComputeAuthTokenOutputTypeDef",
-    {
-        "FleetId": str,
-        "FleetArn": str,
-        "ComputeName": str,
-        "ComputeArn": str,
-        "AuthToken": str,
-        "ExpirationTimestamp": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetGameSessionLogUrlOutputTypeDef = TypedDict(
-    "GetGameSessionLogUrlOutputTypeDef",
+DescribeBuildOutputTypeDef = TypedDict(
+    "DescribeBuildOutputTypeDef",
     {
-        "PreSignedUrl": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Build": BuildTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListBuildsOutputTypeDef = TypedDict(
     "ListBuildsOutputTypeDef",
     {
         "Builds": List[BuildTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListFleetsOutputTypeDef = TypedDict(
-    "ListFleetsOutputTypeDef",
-    {
-        "FleetIds": List[str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListGameServersOutputTypeDef = TypedDict(
-    "ListGameServersOutputTypeDef",
+UpdateBuildOutputTypeDef = TypedDict(
+    "UpdateBuildOutputTypeDef",
     {
-        "GameServers": List[GameServerTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "Build": BuildTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-PutScalingPolicyOutputTypeDef = TypedDict(
-    "PutScalingPolicyOutputTypeDef",
+_RequiredClaimGameServerInputRequestTypeDef = TypedDict(
+    "_RequiredClaimGameServerInputRequestTypeDef",
     {
-        "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "GameServerGroupName": str,
     },
 )
-
-RegisterGameServerOutputTypeDef = TypedDict(
-    "RegisterGameServerOutputTypeDef",
+_OptionalClaimGameServerInputRequestTypeDef = TypedDict(
+    "_OptionalClaimGameServerInputRequestTypeDef",
     {
-        "GameServer": GameServerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "GameServerId": str,
+        "GameServerData": str,
+        "FilterOption": ClaimFilterOptionTypeDef,
     },
+    total=False,
 )
 
-ResolveAliasOutputTypeDef = TypedDict(
-    "ResolveAliasOutputTypeDef",
-    {
-        "FleetId": str,
-        "FleetArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-StartFleetActionsOutputTypeDef = TypedDict(
-    "StartFleetActionsOutputTypeDef",
-    {
-        "FleetId": str,
-        "FleetArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class ClaimGameServerInputRequestTypeDef(
+    _RequiredClaimGameServerInputRequestTypeDef, _OptionalClaimGameServerInputRequestTypeDef
+):
+    pass
 
-StopFleetActionsOutputTypeDef = TypedDict(
-    "StopFleetActionsOutputTypeDef",
-    {
-        "FleetId": str,
-        "FleetArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
 
-UpdateBuildOutputTypeDef = TypedDict(
-    "UpdateBuildOutputTypeDef",
+ClaimGameServerOutputTypeDef = TypedDict(
+    "ClaimGameServerOutputTypeDef",
     {
-        "Build": BuildTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "GameServer": GameServerTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateFleetAttributesOutputTypeDef = TypedDict(
-    "UpdateFleetAttributesOutputTypeDef",
+DescribeGameServerOutputTypeDef = TypedDict(
+    "DescribeGameServerOutputTypeDef",
     {
-        "FleetId": str,
-        "FleetArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "GameServer": GameServerTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateFleetCapacityOutputTypeDef = TypedDict(
-    "UpdateFleetCapacityOutputTypeDef",
+ListGameServersOutputTypeDef = TypedDict(
+    "ListGameServersOutputTypeDef",
     {
-        "FleetId": str,
-        "FleetArn": str,
-        "Location": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "GameServers": List[GameServerTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateFleetPortSettingsOutputTypeDef = TypedDict(
-    "UpdateFleetPortSettingsOutputTypeDef",
+RegisterGameServerOutputTypeDef = TypedDict(
+    "RegisterGameServerOutputTypeDef",
     {
-        "FleetId": str,
-        "FleetArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "GameServer": GameServerTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateGameServerOutputTypeDef = TypedDict(
     "UpdateGameServerOutputTypeDef",
     {
         "GameServer": GameServerTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ValidateMatchmakingRuleSetOutputTypeDef = TypedDict(
-    "ValidateMatchmakingRuleSetOutputTypeDef",
-    {
-        "Valid": bool,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeComputeOutputTypeDef = TypedDict(
     "DescribeComputeOutputTypeDef",
     {
         "Compute": ComputeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListComputeOutputTypeDef = TypedDict(
     "ListComputeOutputTypeDef",
     {
         "ComputeList": List[ComputeTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RegisterComputeOutputTypeDef = TypedDict(
     "RegisterComputeOutputTypeDef",
     {
         "Compute": ComputeTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateAliasInputRequestTypeDef = TypedDict(
     "_RequiredCreateAliasInputRequestTypeDef",
     {
         "Name": str,
@@ -2008,38 +2369,42 @@
     {
         "Description": str,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateAliasInputRequestTypeDef(
     _RequiredCreateAliasInputRequestTypeDef, _OptionalCreateAliasInputRequestTypeDef
 ):
     pass
 
+
 _RequiredCreateLocationInputRequestTypeDef = TypedDict(
     "_RequiredCreateLocationInputRequestTypeDef",
     {
         "LocationName": str,
     },
 )
 _OptionalCreateLocationInputRequestTypeDef = TypedDict(
     "_OptionalCreateLocationInputRequestTypeDef",
     {
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateLocationInputRequestTypeDef(
     _RequiredCreateLocationInputRequestTypeDef, _OptionalCreateLocationInputRequestTypeDef
 ):
     pass
 
+
 _RequiredCreateMatchmakingRuleSetInputRequestTypeDef = TypedDict(
     "_RequiredCreateMatchmakingRuleSetInputRequestTypeDef",
     {
         "Name": str,
         "RuleSetBody": str,
     },
 )
@@ -2047,25 +2412,27 @@
     "_OptionalCreateMatchmakingRuleSetInputRequestTypeDef",
     {
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateMatchmakingRuleSetInputRequestTypeDef(
     _RequiredCreateMatchmakingRuleSetInputRequestTypeDef,
     _OptionalCreateMatchmakingRuleSetInputRequestTypeDef,
 ):
     pass
 
+
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
@@ -2088,15 +2455,15 @@
 
 CreateBuildOutputTypeDef = TypedDict(
     "CreateBuildOutputTypeDef",
     {
         "Build": BuildTypeDef,
         "UploadCredentials": AwsCredentialsTypeDef,
         "StorageLocation": S3LocationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateScriptInputRequestTypeDef = TypedDict(
     "CreateScriptInputRequestTypeDef",
     {
         "Name": str,
@@ -2109,15 +2476,15 @@
 )
 
 RequestUploadCredentialsOutputTypeDef = TypedDict(
     "RequestUploadCredentialsOutputTypeDef",
     {
         "UploadCredentials": AwsCredentialsTypeDef,
         "StorageLocation": S3LocationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ScriptTypeDef = TypedDict(
     "ScriptTypeDef",
     {
         "ScriptId": str,
@@ -2144,28 +2511,30 @@
         "Version": str,
         "StorageLocation": S3LocationTypeDef,
         "ZipFile": Union[str, bytes, IO[Any], StreamingBody],
     },
     total=False,
 )
 
+
 class UpdateScriptInputRequestTypeDef(
     _RequiredUpdateScriptInputRequestTypeDef, _OptionalUpdateScriptInputRequestTypeDef
 ):
     pass
 
+
 DescribeFleetPortSettingsOutputTypeDef = TypedDict(
     "DescribeFleetPortSettingsOutputTypeDef",
     {
         "FleetId": str,
         "FleetArn": str,
         "InboundPermissions": List[IpPermissionTypeDef],
         "UpdateStatus": Literal["PENDING_UPDATE"],
         "Location": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateFleetPortSettingsInputRequestTypeDef = TypedDict(
     "_RequiredUpdateFleetPortSettingsInputRequestTypeDef",
     {
         "FleetId": str,
@@ -2176,20 +2545,22 @@
     {
         "InboundPermissionAuthorizations": Sequence[IpPermissionTypeDef],
         "InboundPermissionRevocations": Sequence[IpPermissionTypeDef],
     },
     total=False,
 )
 
+
 class UpdateFleetPortSettingsInputRequestTypeDef(
     _RequiredUpdateFleetPortSettingsInputRequestTypeDef,
     _OptionalUpdateFleetPortSettingsInputRequestTypeDef,
 ):
     pass
 
+
 CreateFleetLocationsInputRequestTypeDef = TypedDict(
     "CreateFleetLocationsInputRequestTypeDef",
     {
         "FleetId": str,
         "Locations": Sequence[LocationConfigurationTypeDef],
     },
 )
@@ -2241,37 +2612,39 @@
         "ResourceCreationLimitPolicy": ResourceCreationLimitPolicyTypeDef,
         "MetricGroups": Sequence[str],
         "AnywhereConfiguration": AnywhereConfigurationTypeDef,
     },
     total=False,
 )
 
+
 class UpdateFleetAttributesInputRequestTypeDef(
     _RequiredUpdateFleetAttributesInputRequestTypeDef,
     _OptionalUpdateFleetAttributesInputRequestTypeDef,
 ):
     pass
 
+
 CreateFleetLocationsOutputTypeDef = TypedDict(
     "CreateFleetLocationsOutputTypeDef",
     {
         "FleetId": str,
         "FleetArn": str,
         "LocationStates": List[LocationStateTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteFleetLocationsOutputTypeDef = TypedDict(
     "DeleteFleetLocationsOutputTypeDef",
     {
         "FleetId": str,
         "FleetArn": str,
         "LocationStates": List[LocationStateTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LocationAttributesTypeDef = TypedDict(
     "LocationAttributesTypeDef",
     {
         "LocationState": LocationStateTypeDef,
@@ -2313,20 +2686,22 @@
         "InstanceDefinitions": Sequence[InstanceDefinitionTypeDef],
         "GameServerProtectionPolicy": GameServerProtectionPolicyType,
         "BalancingStrategy": BalancingStrategyType,
     },
     total=False,
 )
 
+
 class UpdateGameServerGroupInputRequestTypeDef(
     _RequiredUpdateGameServerGroupInputRequestTypeDef,
     _OptionalUpdateGameServerGroupInputRequestTypeDef,
 ):
     pass
 
+
 _RequiredCreateGameSessionInputRequestTypeDef = TypedDict(
     "_RequiredCreateGameSessionInputRequestTypeDef",
     {
         "MaximumPlayerSessionCount": int,
     },
 )
 _OptionalCreateGameSessionInputRequestTypeDef = TypedDict(
@@ -2341,19 +2716,21 @@
         "IdempotencyToken": str,
         "GameSessionData": str,
         "Location": str,
     },
     total=False,
 )
 
+
 class CreateGameSessionInputRequestTypeDef(
     _RequiredCreateGameSessionInputRequestTypeDef, _OptionalCreateGameSessionInputRequestTypeDef
 ):
     pass
 
+
 _RequiredCreateMatchmakingConfigurationInputRequestTypeDef = TypedDict(
     "_RequiredCreateMatchmakingConfigurationInputRequestTypeDef",
     {
         "Name": str,
         "RequestTimeoutSeconds": int,
         "AcceptanceRequired": bool,
         "RuleSetName": str,
@@ -2373,20 +2750,22 @@
         "BackfillMode": BackfillModeType,
         "FlexMatchMode": FlexMatchModeType,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateMatchmakingConfigurationInputRequestTypeDef(
     _RequiredCreateMatchmakingConfigurationInputRequestTypeDef,
     _OptionalCreateMatchmakingConfigurationInputRequestTypeDef,
 ):
     pass
 
+
 GameSessionTypeDef = TypedDict(
     "GameSessionTypeDef",
     {
         "GameSessionId": str,
         "Name": str,
         "FleetId": str,
         "FleetArn": str,
@@ -2455,20 +2834,22 @@
         "GameSessionData": str,
         "BackfillMode": BackfillModeType,
         "FlexMatchMode": FlexMatchModeType,
     },
     total=False,
 )
 
+
 class UpdateMatchmakingConfigurationInputRequestTypeDef(
     _RequiredUpdateMatchmakingConfigurationInputRequestTypeDef,
     _OptionalUpdateMatchmakingConfigurationInputRequestTypeDef,
 ):
     pass
 
+
 _RequiredCreateGameSessionQueueInputRequestTypeDef = TypedDict(
     "_RequiredCreateGameSessionQueueInputRequestTypeDef",
     {
         "Name": str,
     },
 )
 _OptionalCreateGameSessionQueueInputRequestTypeDef = TypedDict(
@@ -2482,20 +2863,22 @@
         "CustomEventData": str,
         "NotificationTarget": str,
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateGameSessionQueueInputRequestTypeDef(
     _RequiredCreateGameSessionQueueInputRequestTypeDef,
     _OptionalCreateGameSessionQueueInputRequestTypeDef,
 ):
     pass
 
+
 GameSessionQueueTypeDef = TypedDict(
     "GameSessionQueueTypeDef",
     {
         "Name": str,
         "GameSessionQueueArn": str,
         "TimeoutInSeconds": int,
         "PlayerLatencyPolicies": List[PlayerLatencyPolicyTypeDef],
@@ -2524,433 +2907,146 @@
         "PriorityConfiguration": PriorityConfigurationTypeDef,
         "CustomEventData": str,
         "NotificationTarget": str,
     },
     total=False,
 )
 
+
 class UpdateGameSessionQueueInputRequestTypeDef(
     _RequiredUpdateGameSessionQueueInputRequestTypeDef,
     _OptionalUpdateGameSessionQueueInputRequestTypeDef,
 ):
     pass
 
+
 CreateLocationOutputTypeDef = TypedDict(
     "CreateLocationOutputTypeDef",
     {
         "Location": LocationModelTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListLocationsOutputTypeDef = TypedDict(
     "ListLocationsOutputTypeDef",
     {
         "Locations": List[LocationModelTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateMatchmakingRuleSetOutputTypeDef = TypedDict(
     "CreateMatchmakingRuleSetOutputTypeDef",
     {
         "RuleSet": MatchmakingRuleSetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeMatchmakingRuleSetsOutputTypeDef = TypedDict(
     "DescribeMatchmakingRuleSetsOutputTypeDef",
     {
         "RuleSets": List[MatchmakingRuleSetTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreatePlayerSessionOutputTypeDef = TypedDict(
     "CreatePlayerSessionOutputTypeDef",
     {
         "PlayerSession": PlayerSessionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreatePlayerSessionsOutputTypeDef = TypedDict(
     "CreatePlayerSessionsOutputTypeDef",
     {
         "PlayerSessions": List[PlayerSessionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribePlayerSessionsOutputTypeDef = TypedDict(
     "DescribePlayerSessionsOutputTypeDef",
     {
         "PlayerSessions": List[PlayerSessionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateVpcPeeringAuthorizationOutputTypeDef = TypedDict(
     "CreateVpcPeeringAuthorizationOutputTypeDef",
     {
         "VpcPeeringAuthorization": VpcPeeringAuthorizationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeVpcPeeringAuthorizationsOutputTypeDef = TypedDict(
     "DescribeVpcPeeringAuthorizationsOutputTypeDef",
     {
         "VpcPeeringAuthorizations": List[VpcPeeringAuthorizationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEC2InstanceLimitsOutputTypeDef = TypedDict(
     "DescribeEC2InstanceLimitsOutputTypeDef",
     {
         "EC2InstanceLimits": List[EC2InstanceLimitTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeFleetAttributesInputDescribeFleetAttributesPaginateTypeDef = TypedDict(
-    "DescribeFleetAttributesInputDescribeFleetAttributesPaginateTypeDef",
-    {
-        "FleetIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeFleetCapacityInputDescribeFleetCapacityPaginateTypeDef = TypedDict(
-    "DescribeFleetCapacityInputDescribeFleetCapacityPaginateTypeDef",
-    {
-        "FleetIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeFleetEventsInputDescribeFleetEventsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeFleetEventsInputDescribeFleetEventsPaginateTypeDef",
-    {
-        "FleetId": str,
-    },
-)
-_OptionalDescribeFleetEventsInputDescribeFleetEventsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeFleetEventsInputDescribeFleetEventsPaginateTypeDef",
-    {
-        "StartTime": Union[datetime, str],
-        "EndTime": Union[datetime, str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeFleetEventsInputDescribeFleetEventsPaginateTypeDef(
-    _RequiredDescribeFleetEventsInputDescribeFleetEventsPaginateTypeDef,
-    _OptionalDescribeFleetEventsInputDescribeFleetEventsPaginateTypeDef,
-):
-    pass
-
-DescribeFleetUtilizationInputDescribeFleetUtilizationPaginateTypeDef = TypedDict(
-    "DescribeFleetUtilizationInputDescribeFleetUtilizationPaginateTypeDef",
-    {
-        "FleetIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeGameServerInstancesInputDescribeGameServerInstancesPaginateTypeDef = TypedDict(
-    "_RequiredDescribeGameServerInstancesInputDescribeGameServerInstancesPaginateTypeDef",
-    {
-        "GameServerGroupName": str,
-    },
-)
-_OptionalDescribeGameServerInstancesInputDescribeGameServerInstancesPaginateTypeDef = TypedDict(
-    "_OptionalDescribeGameServerInstancesInputDescribeGameServerInstancesPaginateTypeDef",
-    {
-        "InstanceIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeGameServerInstancesInputDescribeGameServerInstancesPaginateTypeDef(
-    _RequiredDescribeGameServerInstancesInputDescribeGameServerInstancesPaginateTypeDef,
-    _OptionalDescribeGameServerInstancesInputDescribeGameServerInstancesPaginateTypeDef,
-):
-    pass
-
-DescribeGameSessionDetailsInputDescribeGameSessionDetailsPaginateTypeDef = TypedDict(
-    "DescribeGameSessionDetailsInputDescribeGameSessionDetailsPaginateTypeDef",
-    {
-        "FleetId": str,
-        "GameSessionId": str,
-        "AliasId": str,
-        "Location": str,
-        "StatusFilter": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeGameSessionQueuesInputDescribeGameSessionQueuesPaginateTypeDef = TypedDict(
-    "DescribeGameSessionQueuesInputDescribeGameSessionQueuesPaginateTypeDef",
-    {
-        "Names": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeGameSessionsInputDescribeGameSessionsPaginateTypeDef = TypedDict(
-    "DescribeGameSessionsInputDescribeGameSessionsPaginateTypeDef",
-    {
-        "FleetId": str,
-        "GameSessionId": str,
-        "AliasId": str,
-        "Location": str,
-        "StatusFilter": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeInstancesInputDescribeInstancesPaginateTypeDef = TypedDict(
-    "_RequiredDescribeInstancesInputDescribeInstancesPaginateTypeDef",
-    {
-        "FleetId": str,
-    },
-)
-_OptionalDescribeInstancesInputDescribeInstancesPaginateTypeDef = TypedDict(
-    "_OptionalDescribeInstancesInputDescribeInstancesPaginateTypeDef",
-    {
-        "InstanceId": str,
-        "Location": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeInstancesInputDescribeInstancesPaginateTypeDef(
-    _RequiredDescribeInstancesInputDescribeInstancesPaginateTypeDef,
-    _OptionalDescribeInstancesInputDescribeInstancesPaginateTypeDef,
-):
-    pass
-
-DescribeMatchmakingConfigurationsInputDescribeMatchmakingConfigurationsPaginateTypeDef = TypedDict(
-    "DescribeMatchmakingConfigurationsInputDescribeMatchmakingConfigurationsPaginateTypeDef",
-    {
-        "Names": Sequence[str],
-        "RuleSetName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeMatchmakingRuleSetsInputDescribeMatchmakingRuleSetsPaginateTypeDef = TypedDict(
-    "DescribeMatchmakingRuleSetsInputDescribeMatchmakingRuleSetsPaginateTypeDef",
-    {
-        "Names": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribePlayerSessionsInputDescribePlayerSessionsPaginateTypeDef = TypedDict(
-    "DescribePlayerSessionsInputDescribePlayerSessionsPaginateTypeDef",
-    {
-        "GameSessionId": str,
-        "PlayerId": str,
-        "PlayerSessionId": str,
-        "PlayerSessionStatusFilter": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeScalingPoliciesInputDescribeScalingPoliciesPaginateTypeDef = TypedDict(
-    "_RequiredDescribeScalingPoliciesInputDescribeScalingPoliciesPaginateTypeDef",
-    {
-        "FleetId": str,
-    },
-)
-_OptionalDescribeScalingPoliciesInputDescribeScalingPoliciesPaginateTypeDef = TypedDict(
-    "_OptionalDescribeScalingPoliciesInputDescribeScalingPoliciesPaginateTypeDef",
-    {
-        "StatusFilter": ScalingStatusTypeType,
-        "Location": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeScalingPoliciesInputDescribeScalingPoliciesPaginateTypeDef(
-    _RequiredDescribeScalingPoliciesInputDescribeScalingPoliciesPaginateTypeDef,
-    _OptionalDescribeScalingPoliciesInputDescribeScalingPoliciesPaginateTypeDef,
-):
-    pass
-
-ListAliasesInputListAliasesPaginateTypeDef = TypedDict(
-    "ListAliasesInputListAliasesPaginateTypeDef",
-    {
-        "RoutingStrategyType": RoutingStrategyTypeType,
-        "Name": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListBuildsInputListBuildsPaginateTypeDef = TypedDict(
-    "ListBuildsInputListBuildsPaginateTypeDef",
-    {
-        "Status": BuildStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListComputeInputListComputePaginateTypeDef = TypedDict(
-    "_RequiredListComputeInputListComputePaginateTypeDef",
-    {
-        "FleetId": str,
-    },
-)
-_OptionalListComputeInputListComputePaginateTypeDef = TypedDict(
-    "_OptionalListComputeInputListComputePaginateTypeDef",
-    {
-        "Location": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListComputeInputListComputePaginateTypeDef(
-    _RequiredListComputeInputListComputePaginateTypeDef,
-    _OptionalListComputeInputListComputePaginateTypeDef,
-):
-    pass
-
-ListFleetsInputListFleetsPaginateTypeDef = TypedDict(
-    "ListFleetsInputListFleetsPaginateTypeDef",
-    {
-        "BuildId": str,
-        "ScriptId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListGameServerGroupsInputListGameServerGroupsPaginateTypeDef = TypedDict(
-    "ListGameServerGroupsInputListGameServerGroupsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
-)
-
-_RequiredListGameServersInputListGameServersPaginateTypeDef = TypedDict(
-    "_RequiredListGameServersInputListGameServersPaginateTypeDef",
-    {
-        "GameServerGroupName": str,
-    },
-)
-_OptionalListGameServersInputListGameServersPaginateTypeDef = TypedDict(
-    "_OptionalListGameServersInputListGameServersPaginateTypeDef",
-    {
-        "SortOrder": SortOrderType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListGameServersInputListGameServersPaginateTypeDef(
-    _RequiredListGameServersInputListGameServersPaginateTypeDef,
-    _OptionalListGameServersInputListGameServersPaginateTypeDef,
-):
-    pass
-
-ListLocationsInputListLocationsPaginateTypeDef = TypedDict(
-    "ListLocationsInputListLocationsPaginateTypeDef",
-    {
-        "Filters": Sequence[LocationFilterType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListScriptsInputListScriptsPaginateTypeDef = TypedDict(
-    "ListScriptsInputListScriptsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-SearchGameSessionsInputSearchGameSessionsPaginateTypeDef = TypedDict(
-    "SearchGameSessionsInputSearchGameSessionsPaginateTypeDef",
-    {
-        "FleetId": str,
-        "AliasId": str,
-        "Location": str,
-        "FilterExpression": str,
-        "SortExpression": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
 )
 
 DescribeFleetEventsOutputTypeDef = TypedDict(
     "DescribeFleetEventsOutputTypeDef",
     {
         "Events": List[EventTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFleetLocationUtilizationOutputTypeDef = TypedDict(
     "DescribeFleetLocationUtilizationOutputTypeDef",
     {
         "FleetUtilization": FleetUtilizationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFleetUtilizationOutputTypeDef = TypedDict(
     "DescribeFleetUtilizationOutputTypeDef",
     {
         "FleetUtilization": List[FleetUtilizationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeGameServerInstancesOutputTypeDef = TypedDict(
     "DescribeGameServerInstancesOutputTypeDef",
     {
         "GameServerInstances": List[GameServerInstanceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeInstancesOutputTypeDef = TypedDict(
     "DescribeInstancesOutputTypeDef",
     {
         "Instances": List[InstanceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FleetCapacityTypeDef = TypedDict(
     "FleetCapacityTypeDef",
     {
         "FleetId": str,
@@ -2972,20 +3068,22 @@
     "_OptionalGameServerGroupAutoScalingPolicyTypeDef",
     {
         "EstimatedInstanceWarmup": int,
     },
     total=False,
 )
 
+
 class GameServerGroupAutoScalingPolicyTypeDef(
     _RequiredGameServerGroupAutoScalingPolicyTypeDef,
     _OptionalGameServerGroupAutoScalingPolicyTypeDef,
 ):
     pass
 
+
 GameSessionConnectionInfoTypeDef = TypedDict(
     "GameSessionConnectionInfoTypeDef",
     {
         "GameSessionArn": str,
         "IpAddress": str,
         "DnsName": str,
         "Port": int,
@@ -3035,20 +3133,22 @@
         "PlayerLatencies": Sequence[PlayerLatencyTypeDef],
         "DesiredPlayerSessions": Sequence[DesiredPlayerSessionTypeDef],
         "GameSessionData": str,
     },
     total=False,
 )
 
+
 class StartGameSessionPlacementInputRequestTypeDef(
     _RequiredStartGameSessionPlacementInputRequestTypeDef,
     _OptionalStartGameSessionPlacementInputRequestTypeDef,
 ):
     pass
 
+
 InstanceAccessTypeDef = TypedDict(
     "InstanceAccessTypeDef",
     {
         "FleetId": str,
         "InstanceId": str,
         "IpAddress": str,
         "OperatingSystem": OperatingSystemType,
@@ -3075,19 +3175,21 @@
         "EvaluationPeriods": int,
         "PolicyType": PolicyTypeType,
         "TargetConfiguration": TargetConfigurationTypeDef,
     },
     total=False,
 )
 
+
 class PutScalingPolicyInputRequestTypeDef(
     _RequiredPutScalingPolicyInputRequestTypeDef, _OptionalPutScalingPolicyInputRequestTypeDef
 ):
     pass
 
+
 ScalingPolicyTypeDef = TypedDict(
     "ScalingPolicyTypeDef",
     {
         "FleetId": str,
         "FleetArn": str,
         "Name": str,
         "Status": ScalingStatusTypeType,
@@ -3129,40 +3231,40 @@
     total=False,
 )
 
 CreateAliasOutputTypeDef = TypedDict(
     "CreateAliasOutputTypeDef",
     {
         "Alias": AliasTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAliasOutputTypeDef = TypedDict(
     "DescribeAliasOutputTypeDef",
     {
         "Alias": AliasTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAliasesOutputTypeDef = TypedDict(
     "ListAliasesOutputTypeDef",
     {
         "Aliases": List[AliasTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateAliasOutputTypeDef = TypedDict(
     "UpdateAliasOutputTypeDef",
     {
         "Alias": AliasTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredStartMatchBackfillInputRequestTypeDef = TypedDict(
     "_RequiredStartMatchBackfillInputRequestTypeDef",
     {
         "ConfigurationName": str,
@@ -3174,19 +3276,21 @@
     {
         "TicketId": str,
         "GameSessionArn": str,
     },
     total=False,
 )
 
+
 class StartMatchBackfillInputRequestTypeDef(
     _RequiredStartMatchBackfillInputRequestTypeDef, _OptionalStartMatchBackfillInputRequestTypeDef
 ):
     pass
 
+
 _RequiredStartMatchmakingInputRequestTypeDef = TypedDict(
     "_RequiredStartMatchmakingInputRequestTypeDef",
     {
         "ConfigurationName": str,
         "Players": Sequence[PlayerTypeDef],
     },
 )
@@ -3194,152 +3298,154 @@
     "_OptionalStartMatchmakingInputRequestTypeDef",
     {
         "TicketId": str,
     },
     total=False,
 )
 
+
 class StartMatchmakingInputRequestTypeDef(
     _RequiredStartMatchmakingInputRequestTypeDef, _OptionalStartMatchmakingInputRequestTypeDef
 ):
     pass
 
+
 CreateScriptOutputTypeDef = TypedDict(
     "CreateScriptOutputTypeDef",
     {
         "Script": ScriptTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeScriptOutputTypeDef = TypedDict(
     "DescribeScriptOutputTypeDef",
     {
         "Script": ScriptTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListScriptsOutputTypeDef = TypedDict(
     "ListScriptsOutputTypeDef",
     {
         "Scripts": List[ScriptTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateScriptOutputTypeDef = TypedDict(
     "UpdateScriptOutputTypeDef",
     {
         "Script": ScriptTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateFleetOutputTypeDef = TypedDict(
     "CreateFleetOutputTypeDef",
     {
         "FleetAttributes": FleetAttributesTypeDef,
         "LocationStates": List[LocationStateTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFleetAttributesOutputTypeDef = TypedDict(
     "DescribeFleetAttributesOutputTypeDef",
     {
         "FleetAttributes": List[FleetAttributesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFleetLocationAttributesOutputTypeDef = TypedDict(
     "DescribeFleetLocationAttributesOutputTypeDef",
     {
         "FleetId": str,
         "FleetArn": str,
         "LocationAttributes": List[LocationAttributesTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateGameServerGroupOutputTypeDef = TypedDict(
     "CreateGameServerGroupOutputTypeDef",
     {
         "GameServerGroup": GameServerGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteGameServerGroupOutputTypeDef = TypedDict(
     "DeleteGameServerGroupOutputTypeDef",
     {
         "GameServerGroup": GameServerGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeGameServerGroupOutputTypeDef = TypedDict(
     "DescribeGameServerGroupOutputTypeDef",
     {
         "GameServerGroup": GameServerGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListGameServerGroupsOutputTypeDef = TypedDict(
     "ListGameServerGroupsOutputTypeDef",
     {
         "GameServerGroups": List[GameServerGroupTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ResumeGameServerGroupOutputTypeDef = TypedDict(
     "ResumeGameServerGroupOutputTypeDef",
     {
         "GameServerGroup": GameServerGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 SuspendGameServerGroupOutputTypeDef = TypedDict(
     "SuspendGameServerGroupOutputTypeDef",
     {
         "GameServerGroup": GameServerGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateGameServerGroupOutputTypeDef = TypedDict(
     "UpdateGameServerGroupOutputTypeDef",
     {
         "GameServerGroup": GameServerGroupTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateGameSessionOutputTypeDef = TypedDict(
     "CreateGameSessionOutputTypeDef",
     {
         "GameSession": GameSessionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeGameSessionsOutputTypeDef = TypedDict(
     "DescribeGameSessionsOutputTypeDef",
     {
         "GameSessions": List[GameSessionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GameSessionDetailTypeDef = TypedDict(
     "GameSessionDetailTypeDef",
     {
         "GameSession": GameSessionTypeDef,
@@ -3349,90 +3455,90 @@
 )
 
 SearchGameSessionsOutputTypeDef = TypedDict(
     "SearchGameSessionsOutputTypeDef",
     {
         "GameSessions": List[GameSessionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateGameSessionOutputTypeDef = TypedDict(
     "UpdateGameSessionOutputTypeDef",
     {
         "GameSession": GameSessionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateMatchmakingConfigurationOutputTypeDef = TypedDict(
     "CreateMatchmakingConfigurationOutputTypeDef",
     {
         "Configuration": MatchmakingConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeMatchmakingConfigurationsOutputTypeDef = TypedDict(
     "DescribeMatchmakingConfigurationsOutputTypeDef",
     {
         "Configurations": List[MatchmakingConfigurationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateMatchmakingConfigurationOutputTypeDef = TypedDict(
     "UpdateMatchmakingConfigurationOutputTypeDef",
     {
         "Configuration": MatchmakingConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateGameSessionQueueOutputTypeDef = TypedDict(
     "CreateGameSessionQueueOutputTypeDef",
     {
         "GameSessionQueue": GameSessionQueueTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeGameSessionQueuesOutputTypeDef = TypedDict(
     "DescribeGameSessionQueuesOutputTypeDef",
     {
         "GameSessionQueues": List[GameSessionQueueTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateGameSessionQueueOutputTypeDef = TypedDict(
     "UpdateGameSessionQueueOutputTypeDef",
     {
         "GameSessionQueue": GameSessionQueueTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFleetCapacityOutputTypeDef = TypedDict(
     "DescribeFleetCapacityOutputTypeDef",
     {
         "FleetCapacity": List[FleetCapacityTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeFleetLocationCapacityOutputTypeDef = TypedDict(
     "DescribeFleetLocationCapacityOutputTypeDef",
     {
         "FleetCapacity": FleetCapacityTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateGameServerGroupInputRequestTypeDef = TypedDict(
     "_RequiredCreateGameServerGroupInputRequestTypeDef",
     {
         "GameServerGroupName": str,
@@ -3451,20 +3557,22 @@
         "GameServerProtectionPolicy": GameServerProtectionPolicyType,
         "VpcSubnets": Sequence[str],
         "Tags": Sequence[TagTypeDef],
     },
     total=False,
 )
 
+
 class CreateGameServerGroupInputRequestTypeDef(
     _RequiredCreateGameServerGroupInputRequestTypeDef,
     _OptionalCreateGameServerGroupInputRequestTypeDef,
 ):
     pass
 
+
 MatchmakingTicketTypeDef = TypedDict(
     "MatchmakingTicketTypeDef",
     {
         "TicketId": str,
         "ConfigurationName": str,
         "ConfigurationArn": str,
         "Status": MatchmakingConfigurationStatusType,
@@ -3479,48 +3587,48 @@
     total=False,
 )
 
 DescribeGameSessionPlacementOutputTypeDef = TypedDict(
     "DescribeGameSessionPlacementOutputTypeDef",
     {
         "GameSessionPlacement": GameSessionPlacementTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartGameSessionPlacementOutputTypeDef = TypedDict(
     "StartGameSessionPlacementOutputTypeDef",
     {
         "GameSessionPlacement": GameSessionPlacementTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopGameSessionPlacementOutputTypeDef = TypedDict(
     "StopGameSessionPlacementOutputTypeDef",
     {
         "GameSessionPlacement": GameSessionPlacementTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetInstanceAccessOutputTypeDef = TypedDict(
     "GetInstanceAccessOutputTypeDef",
     {
         "InstanceAccess": InstanceAccessTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeScalingPoliciesOutputTypeDef = TypedDict(
     "DescribeScalingPoliciesOutputTypeDef",
     {
         "ScalingPolicies": List[ScalingPolicyTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateFleetInputRequestTypeDef = TypedDict(
     "_RequiredCreateFleetInputRequestTypeDef",
     {
         "Name": str,
@@ -3550,24 +3658,26 @@
         "Tags": Sequence[TagTypeDef],
         "ComputeType": ComputeTypeType,
         "AnywhereConfiguration": AnywhereConfigurationTypeDef,
     },
     total=False,
 )
 
+
 class CreateFleetInputRequestTypeDef(
     _RequiredCreateFleetInputRequestTypeDef, _OptionalCreateFleetInputRequestTypeDef
 ):
     pass
 
+
 DescribeRuntimeConfigurationOutputTypeDef = TypedDict(
     "DescribeRuntimeConfigurationOutputTypeDef",
     {
         "RuntimeConfiguration": RuntimeConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateRuntimeConfigurationInputRequestTypeDef = TypedDict(
     "UpdateRuntimeConfigurationInputRequestTypeDef",
     {
         "FleetId": str,
@@ -3575,51 +3685,51 @@
     },
 )
 
 UpdateRuntimeConfigurationOutputTypeDef = TypedDict(
     "UpdateRuntimeConfigurationOutputTypeDef",
     {
         "RuntimeConfiguration": RuntimeConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeVpcPeeringConnectionsOutputTypeDef = TypedDict(
     "DescribeVpcPeeringConnectionsOutputTypeDef",
     {
         "VpcPeeringConnections": List[VpcPeeringConnectionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeGameSessionDetailsOutputTypeDef = TypedDict(
     "DescribeGameSessionDetailsOutputTypeDef",
     {
         "GameSessionDetails": List[GameSessionDetailTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeMatchmakingOutputTypeDef = TypedDict(
     "DescribeMatchmakingOutputTypeDef",
     {
         "TicketList": List[MatchmakingTicketTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartMatchBackfillOutputTypeDef = TypedDict(
     "StartMatchBackfillOutputTypeDef",
     {
         "MatchmakingTicket": MatchmakingTicketTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartMatchmakingOutputTypeDef = TypedDict(
     "StartMatchmakingOutputTypeDef",
     {
         "MatchmakingTicket": MatchmakingTicketTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-gamelift-2.5.0.post1/types_aiobotocore_gamelift.egg-info/PKG-INFO` & `types-aiobotocore-gamelift-2.5.1/types_aiobotocore_gamelift.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-gamelift
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.GameLift 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.GameLift 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-gamelift"></a>
 
 # types-aiobotocore-gamelift
 
 [![PyPI - types-aiobotocore-gamelift](https://img.shields.io/pypi/v/types-aiobotocore-gamelift.svg?color=blue)](https://pypi.org/project/types-aiobotocore-gamelift)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-gamelift.svg?color=blue)](https://pypi.org/project/types-aiobotocore-gamelift)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-gamelift?color=blue)](https://pypistats.org/packages/types-aiobotocore-gamelift)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.GameLift 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift)
+[aiobotocore.GameLift 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/gamelift.html#GameLift)
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
 [types-aiobotocore-gamelift docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_gamelift/).
 
 See how it helps to find and fix potential bugs:
 
@@ -390,14 +390,15 @@
     DescribeInstancesPaginatorName,
     DescribeMatchmakingConfigurationsPaginatorName,
     DescribeMatchmakingRuleSetsPaginatorName,
     DescribePlayerSessionsPaginatorName,
     DescribeScalingPoliciesPaginatorName,
     EC2InstanceTypeType,
     EventCodeType,
+    FilterInstanceStatusType,
     FleetActionType,
     FleetStatusType,
     FleetTypeType,
     FlexMatchModeType,
     GameServerClaimStatusType,
     GameServerGroupActionType,
     GameServerGroupDeleteOptionType,
@@ -459,17 +460,16 @@
     AcceptMatchInputRequestTypeDef,
     RoutingStrategyTypeDef,
     AnywhereConfigurationTypeDef,
     AttributeValueTypeDef,
     AwsCredentialsTypeDef,
     BuildTypeDef,
     CertificateConfigurationTypeDef,
-    ClaimGameServerInputRequestTypeDef,
+    ClaimFilterOptionTypeDef,
     GameServerTypeDef,
-    ResponseMetadataTypeDef,
     ComputeTypeDef,
     TagTypeDef,
     S3LocationTypeDef,
     IpPermissionTypeDef,
     LocationConfigurationTypeDef,
     ResourceCreationLimitPolicyTypeDef,
     LocationStateTypeDef,
@@ -504,107 +504,131 @@
     DeregisterComputeInputRequestTypeDef,
     DeregisterGameServerInputRequestTypeDef,
     DescribeAliasInputRequestTypeDef,
     DescribeBuildInputRequestTypeDef,
     DescribeComputeInputRequestTypeDef,
     DescribeEC2InstanceLimitsInputRequestTypeDef,
     EC2InstanceLimitTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeFleetAttributesInputDescribeFleetAttributesPaginateTypeDef,
     DescribeFleetAttributesInputRequestTypeDef,
+    DescribeFleetCapacityInputDescribeFleetCapacityPaginateTypeDef,
     DescribeFleetCapacityInputRequestTypeDef,
+    DescribeFleetEventsInputDescribeFleetEventsPaginateTypeDef,
     DescribeFleetEventsInputRequestTypeDef,
     EventTypeDef,
     DescribeFleetLocationAttributesInputRequestTypeDef,
     DescribeFleetLocationCapacityInputRequestTypeDef,
     DescribeFleetLocationUtilizationInputRequestTypeDef,
     FleetUtilizationTypeDef,
     DescribeFleetPortSettingsInputRequestTypeDef,
+    DescribeFleetUtilizationInputDescribeFleetUtilizationPaginateTypeDef,
     DescribeFleetUtilizationInputRequestTypeDef,
     DescribeGameServerGroupInputRequestTypeDef,
     DescribeGameServerInputRequestTypeDef,
+    DescribeGameServerInstancesInputDescribeGameServerInstancesPaginateTypeDef,
     DescribeGameServerInstancesInputRequestTypeDef,
     GameServerInstanceTypeDef,
+    DescribeGameSessionDetailsInputDescribeGameSessionDetailsPaginateTypeDef,
     DescribeGameSessionDetailsInputRequestTypeDef,
     DescribeGameSessionPlacementInputRequestTypeDef,
+    DescribeGameSessionQueuesInputDescribeGameSessionQueuesPaginateTypeDef,
     DescribeGameSessionQueuesInputRequestTypeDef,
+    DescribeGameSessionsInputDescribeGameSessionsPaginateTypeDef,
     DescribeGameSessionsInputRequestTypeDef,
+    DescribeInstancesInputDescribeInstancesPaginateTypeDef,
     DescribeInstancesInputRequestTypeDef,
     InstanceTypeDef,
+    DescribeMatchmakingConfigurationsInputDescribeMatchmakingConfigurationsPaginateTypeDef,
     DescribeMatchmakingConfigurationsInputRequestTypeDef,
     DescribeMatchmakingInputRequestTypeDef,
+    DescribeMatchmakingRuleSetsInputDescribeMatchmakingRuleSetsPaginateTypeDef,
     DescribeMatchmakingRuleSetsInputRequestTypeDef,
+    DescribePlayerSessionsInputDescribePlayerSessionsPaginateTypeDef,
     DescribePlayerSessionsInputRequestTypeDef,
     DescribeRuntimeConfigurationInputRequestTypeDef,
+    DescribeScalingPoliciesInputDescribeScalingPoliciesPaginateTypeDef,
     DescribeScalingPoliciesInputRequestTypeDef,
     DescribeScriptInputRequestTypeDef,
     DescribeVpcPeeringConnectionsInputRequestTypeDef,
     DesiredPlayerSessionTypeDef,
     EC2InstanceCountsTypeDef,
+    EmptyResponseMetadataTypeDef,
     TargetTrackingConfigurationTypeDef,
     MatchedPlayerSessionTypeDef,
     PlacedPlayerSessionTypeDef,
     PlayerLatencyTypeDef,
     GetComputeAccessInputRequestTypeDef,
     GetComputeAuthTokenInputRequestTypeDef,
+    GetComputeAuthTokenOutputTypeDef,
     GetGameSessionLogUrlInputRequestTypeDef,
+    GetGameSessionLogUrlOutputTypeDef,
     GetInstanceAccessInputRequestTypeDef,
     InstanceCredentialsTypeDef,
+    ListAliasesInputListAliasesPaginateTypeDef,
     ListAliasesInputRequestTypeDef,
+    ListBuildsInputListBuildsPaginateTypeDef,
     ListBuildsInputRequestTypeDef,
+    ListComputeInputListComputePaginateTypeDef,
     ListComputeInputRequestTypeDef,
+    ListFleetsInputListFleetsPaginateTypeDef,
     ListFleetsInputRequestTypeDef,
+    ListFleetsOutputTypeDef,
+    ListGameServerGroupsInputListGameServerGroupsPaginateTypeDef,
     ListGameServerGroupsInputRequestTypeDef,
+    ListGameServersInputListGameServersPaginateTypeDef,
     ListGameServersInputRequestTypeDef,
+    ListLocationsInputListLocationsPaginateTypeDef,
     ListLocationsInputRequestTypeDef,
+    ListScriptsInputListScriptsPaginateTypeDef,
     ListScriptsInputRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
     TargetConfigurationTypeDef,
+    PutScalingPolicyOutputTypeDef,
     RegisterComputeInputRequestTypeDef,
     RegisterGameServerInputRequestTypeDef,
     RequestUploadCredentialsInputRequestTypeDef,
     ResolveAliasInputRequestTypeDef,
+    ResolveAliasOutputTypeDef,
+    ResponseMetadataTypeDef,
     ResumeGameServerGroupInputRequestTypeDef,
     ServerProcessTypeDef,
     SearchGameSessionsInputRequestTypeDef,
+    SearchGameSessionsInputSearchGameSessionsPaginateTypeDef,
     StartFleetActionsInputRequestTypeDef,
+    StartFleetActionsOutputTypeDef,
     StopFleetActionsInputRequestTypeDef,
+    StopFleetActionsOutputTypeDef,
     StopGameSessionPlacementInputRequestTypeDef,
     StopMatchmakingInputRequestTypeDef,
     SuspendGameServerGroupInputRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateBuildInputRequestTypeDef,
+    UpdateFleetAttributesOutputTypeDef,
     UpdateFleetCapacityInputRequestTypeDef,
+    UpdateFleetCapacityOutputTypeDef,
+    UpdateFleetPortSettingsOutputTypeDef,
     UpdateGameServerInputRequestTypeDef,
     UpdateGameSessionInputRequestTypeDef,
     ValidateMatchmakingRuleSetInputRequestTypeDef,
+    ValidateMatchmakingRuleSetOutputTypeDef,
     VpcPeeringConnectionStatusTypeDef,
     AliasTypeDef,
     UpdateAliasInputRequestTypeDef,
     PlayerTypeDef,
-    ClaimGameServerOutputTypeDef,
-    DescribeBuildOutputTypeDef,
-    DescribeGameServerOutputTypeDef,
-    EmptyResponseMetadataTypeDef,
     GetComputeAccessOutputTypeDef,
-    GetComputeAuthTokenOutputTypeDef,
-    GetGameSessionLogUrlOutputTypeDef,
+    DescribeBuildOutputTypeDef,
     ListBuildsOutputTypeDef,
-    ListFleetsOutputTypeDef,
+    UpdateBuildOutputTypeDef,
+    ClaimGameServerInputRequestTypeDef,
+    ClaimGameServerOutputTypeDef,
+    DescribeGameServerOutputTypeDef,
     ListGameServersOutputTypeDef,
-    PutScalingPolicyOutputTypeDef,
     RegisterGameServerOutputTypeDef,
-    ResolveAliasOutputTypeDef,
-    StartFleetActionsOutputTypeDef,
-    StopFleetActionsOutputTypeDef,
-    UpdateBuildOutputTypeDef,
-    UpdateFleetAttributesOutputTypeDef,
-    UpdateFleetCapacityOutputTypeDef,
-    UpdateFleetPortSettingsOutputTypeDef,
     UpdateGameServerOutputTypeDef,
-    ValidateMatchmakingRuleSetOutputTypeDef,
     DescribeComputeOutputTypeDef,
     ListComputeOutputTypeDef,
     RegisterComputeOutputTypeDef,
     CreateAliasInputRequestTypeDef,
     CreateLocationInputRequestTypeDef,
     CreateMatchmakingRuleSetInputRequestTypeDef,
     ListTagsForResourceResponseTypeDef,
@@ -639,36 +663,14 @@
     DescribeMatchmakingRuleSetsOutputTypeDef,
     CreatePlayerSessionOutputTypeDef,
     CreatePlayerSessionsOutputTypeDef,
     DescribePlayerSessionsOutputTypeDef,
     CreateVpcPeeringAuthorizationOutputTypeDef,
     DescribeVpcPeeringAuthorizationsOutputTypeDef,
     DescribeEC2InstanceLimitsOutputTypeDef,
-    DescribeFleetAttributesInputDescribeFleetAttributesPaginateTypeDef,
-    DescribeFleetCapacityInputDescribeFleetCapacityPaginateTypeDef,
-    DescribeFleetEventsInputDescribeFleetEventsPaginateTypeDef,
-    DescribeFleetUtilizationInputDescribeFleetUtilizationPaginateTypeDef,
-    DescribeGameServerInstancesInputDescribeGameServerInstancesPaginateTypeDef,
-    DescribeGameSessionDetailsInputDescribeGameSessionDetailsPaginateTypeDef,
-    DescribeGameSessionQueuesInputDescribeGameSessionQueuesPaginateTypeDef,
-    DescribeGameSessionsInputDescribeGameSessionsPaginateTypeDef,
-    DescribeInstancesInputDescribeInstancesPaginateTypeDef,
-    DescribeMatchmakingConfigurationsInputDescribeMatchmakingConfigurationsPaginateTypeDef,
-    DescribeMatchmakingRuleSetsInputDescribeMatchmakingRuleSetsPaginateTypeDef,
-    DescribePlayerSessionsInputDescribePlayerSessionsPaginateTypeDef,
-    DescribeScalingPoliciesInputDescribeScalingPoliciesPaginateTypeDef,
-    ListAliasesInputListAliasesPaginateTypeDef,
-    ListBuildsInputListBuildsPaginateTypeDef,
-    ListComputeInputListComputePaginateTypeDef,
-    ListFleetsInputListFleetsPaginateTypeDef,
-    ListGameServerGroupsInputListGameServerGroupsPaginateTypeDef,
-    ListGameServersInputListGameServersPaginateTypeDef,
-    ListLocationsInputListLocationsPaginateTypeDef,
-    ListScriptsInputListScriptsPaginateTypeDef,
-    SearchGameSessionsInputSearchGameSessionsPaginateTypeDef,
     DescribeFleetEventsOutputTypeDef,
     DescribeFleetLocationUtilizationOutputTypeDef,
     DescribeFleetUtilizationOutputTypeDef,
     DescribeGameServerInstancesOutputTypeDef,
     DescribeInstancesOutputTypeDef,
     FleetCapacityTypeDef,
     GameServerGroupAutoScalingPolicyTypeDef,
@@ -739,43 +741,43 @@
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

### Comparing `types-aiobotocore-gamelift-2.5.0.post1/types_aiobotocore_gamelift.egg-info/SOURCES.txt` & `types-aiobotocore-gamelift-2.5.1/types_aiobotocore_gamelift.egg-info/SOURCES.txt`

 * *Files identical despite different names*

