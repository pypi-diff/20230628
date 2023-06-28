# Comparing `tmp/types-aiobotocore-opsworks-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-opsworks-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-opsworks-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:05 2023, max compression
+gzip compressed data, was "types-aiobotocore-opsworks-2.5.1.tar", last modified: Wed Jun 28 01:43:56 2023, max compression
```

## Comparing `types-aiobotocore-opsworks-2.5.0.post1.tar` & `types-aiobotocore-opsworks-2.5.1.tar`

### file list

```diff
@@ -1,31 +1,31 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:05.539483 types-aiobotocore-opsworks-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:19:29.000000 types-aiobotocore-opsworks-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    23728 2023-03-11 12:27:05.531483 types-aiobotocore-opsworks-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    22153 2023-03-11 12:19:29.000000 types-aiobotocore-opsworks-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:05.539483 types-aiobotocore-opsworks-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2131 2023-03-11 12:19:28.000000 types-aiobotocore-opsworks-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:05.531483 types-aiobotocore-opsworks-2.5.0.post1/types_aiobotocore_opsworks/
--rw-r--r--   0 runner    (1001) docker     (123)     1985 2023-03-11 12:19:29.000000 types-aiobotocore-opsworks-2.5.0.post1/types_aiobotocore_opsworks/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1984 2023-03-11 12:19:29.000000 types-aiobotocore-opsworks-2.5.0.post1/types_aiobotocore_opsworks/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      947 2023-03-11 12:19:29.000000 types-aiobotocore-opsworks-2.5.0.post1/types_aiobotocore_opsworks/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    54755 2023-03-11 12:19:29.000000 types-aiobotocore-opsworks-2.5.0.post1/types_aiobotocore_opsworks/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    54665 2023-03-11 12:19:29.000000 types-aiobotocore-opsworks-2.5.0.post1/types_aiobotocore_opsworks/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    12231 2023-03-11 12:19:30.000000 types-aiobotocore-opsworks-2.5.0.post1/types_aiobotocore_opsworks/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    12229 2023-03-11 12:19:29.000000 types-aiobotocore-opsworks-2.5.0.post1/types_aiobotocore_opsworks/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     2269 2023-03-11 12:19:29.000000 types-aiobotocore-opsworks-2.5.0.post1/types_aiobotocore_opsworks/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     2265 2023-03-11 12:19:29.000000 types-aiobotocore-opsworks-2.5.0.post1/types_aiobotocore_opsworks/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:19:29.000000 types-aiobotocore-opsworks-2.5.0.post1/types_aiobotocore_opsworks/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    21960 2023-03-11 12:19:29.000000 types-aiobotocore-opsworks-2.5.0.post1/types_aiobotocore_opsworks/service_resource.py
--rw-r--r--   0 runner    (1001) docker     (123)    21922 2023-03-11 12:19:29.000000 types-aiobotocore-opsworks-2.5.0.post1/types_aiobotocore_opsworks/service_resource.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    64755 2023-03-11 12:19:31.000000 types-aiobotocore-opsworks-2.5.0.post1/types_aiobotocore_opsworks/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    64688 2023-03-11 12:19:30.000000 types-aiobotocore-opsworks-2.5.0.post1/types_aiobotocore_opsworks/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:19:29.000000 types-aiobotocore-opsworks-2.5.0.post1/types_aiobotocore_opsworks/version.py
--rw-r--r--   0 runner    (1001) docker     (123)     7021 2023-03-11 12:19:29.000000 types-aiobotocore-opsworks-2.5.0.post1/types_aiobotocore_opsworks/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)     7015 2023-03-11 12:19:29.000000 types-aiobotocore-opsworks-2.5.0.post1/types_aiobotocore_opsworks/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:05.531483 types-aiobotocore-opsworks-2.5.0.post1/types_aiobotocore_opsworks.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    23728 2023-03-11 12:27:05.000000 types-aiobotocore-opsworks-2.5.0.post1/types_aiobotocore_opsworks.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1002 2023-03-11 12:27:05.000000 types-aiobotocore-opsworks-2.5.0.post1/types_aiobotocore_opsworks.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:05.000000 types-aiobotocore-opsworks-2.5.0.post1/types_aiobotocore_opsworks.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:05.000000 types-aiobotocore-opsworks-2.5.0.post1/types_aiobotocore_opsworks.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:05.000000 types-aiobotocore-opsworks-2.5.0.post1/types_aiobotocore_opsworks.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       27 2023-03-11 12:27:05.000000 types-aiobotocore-opsworks-2.5.0.post1/types_aiobotocore_opsworks.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:56.194187 types-aiobotocore-opsworks-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:36:12.000000 types-aiobotocore-opsworks-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    23594 2023-06-28 01:43:56.194187 types-aiobotocore-opsworks-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    22025 2023-06-28 01:36:12.000000 types-aiobotocore-opsworks-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:56.194187 types-aiobotocore-opsworks-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2125 2023-06-28 01:36:12.000000 types-aiobotocore-opsworks-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:56.194187 types-aiobotocore-opsworks-2.5.1/types_aiobotocore_opsworks/
+-rw-r--r--   0 runner    (1001) docker     (123)     1985 2023-06-28 01:36:12.000000 types-aiobotocore-opsworks-2.5.1/types_aiobotocore_opsworks/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1984 2023-06-28 01:36:12.000000 types-aiobotocore-opsworks-2.5.1/types_aiobotocore_opsworks/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      935 2023-06-28 01:36:12.000000 types-aiobotocore-opsworks-2.5.1/types_aiobotocore_opsworks/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    54754 2023-06-28 01:36:14.000000 types-aiobotocore-opsworks-2.5.1/types_aiobotocore_opsworks/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    54664 2023-06-28 01:36:12.000000 types-aiobotocore-opsworks-2.5.1/types_aiobotocore_opsworks/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    12440 2023-06-28 01:36:14.000000 types-aiobotocore-opsworks-2.5.1/types_aiobotocore_opsworks/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12438 2023-06-28 01:36:14.000000 types-aiobotocore-opsworks-2.5.1/types_aiobotocore_opsworks/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     2151 2023-06-28 01:36:14.000000 types-aiobotocore-opsworks-2.5.1/types_aiobotocore_opsworks/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2148 2023-06-28 01:36:14.000000 types-aiobotocore-opsworks-2.5.1/types_aiobotocore_opsworks/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:36:12.000000 types-aiobotocore-opsworks-2.5.1/types_aiobotocore_opsworks/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    21853 2023-06-28 01:36:14.000000 types-aiobotocore-opsworks-2.5.1/types_aiobotocore_opsworks/service_resource.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21815 2023-06-28 01:36:14.000000 types-aiobotocore-opsworks-2.5.1/types_aiobotocore_opsworks/service_resource.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    64317 2023-06-28 01:36:16.000000 types-aiobotocore-opsworks-2.5.1/types_aiobotocore_opsworks/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    64250 2023-06-28 01:36:15.000000 types-aiobotocore-opsworks-2.5.1/types_aiobotocore_opsworks/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:36:12.000000 types-aiobotocore-opsworks-2.5.1/types_aiobotocore_opsworks/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7021 2023-06-28 01:36:14.000000 types-aiobotocore-opsworks-2.5.1/types_aiobotocore_opsworks/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7015 2023-06-28 01:36:14.000000 types-aiobotocore-opsworks-2.5.1/types_aiobotocore_opsworks/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:56.194187 types-aiobotocore-opsworks-2.5.1/types_aiobotocore_opsworks.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    23594 2023-06-28 01:43:56.000000 types-aiobotocore-opsworks-2.5.1/types_aiobotocore_opsworks.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1002 2023-06-28 01:43:56.000000 types-aiobotocore-opsworks-2.5.1/types_aiobotocore_opsworks.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:56.000000 types-aiobotocore-opsworks-2.5.1/types_aiobotocore_opsworks.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:56.000000 types-aiobotocore-opsworks-2.5.1/types_aiobotocore_opsworks.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:56.000000 types-aiobotocore-opsworks-2.5.1/types_aiobotocore_opsworks.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       27 2023-06-28 01:43:56.000000 types-aiobotocore-opsworks-2.5.1/types_aiobotocore_opsworks.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-opsworks-2.5.0.post1/LICENSE` & `types-aiobotocore-opsworks-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-opsworks-2.5.0.post1/PKG-INFO` & `types-aiobotocore-opsworks-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-opsworks
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.OpsWorks 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.OpsWorks 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworks/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-opsworks"></a>
 
 # types-aiobotocore-opsworks
 
 [![PyPI - types-aiobotocore-opsworks](https://img.shields.io/pypi/v/types-aiobotocore-opsworks.svg?color=blue)](https://pypi.org/project/types-aiobotocore-opsworks)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-opsworks.svg?color=blue)](https://pypi.org/project/types-aiobotocore-opsworks)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworks/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-opsworks?color=blue)](https://pypistats.org/packages/types-aiobotocore-opsworks)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.OpsWorks 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks)
+[aiobotocore.OpsWorks 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks)
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
 [types-aiobotocore-opsworks docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworks/).
 
 See how it helps to find and fix potential bugs:
 
@@ -452,37 +452,44 @@
     SslConfigurationTypeDef,
     AssignInstanceRequestRequestTypeDef,
     AssignVolumeRequestRequestTypeDef,
     AssociateElasticIpRequestRequestTypeDef,
     AttachElasticLoadBalancerRequestRequestTypeDef,
     AutoScalingThresholdsTypeDef,
     EbsBlockDeviceTypeDef,
-    ResponseMetadataTypeDef,
+    ChefConfigurationResponseMetadataTypeDef,
     ChefConfigurationTypeDef,
+    CloneStackResultTypeDef,
     CloudWatchLogsLogStreamTypeDef,
     CommandTypeDef,
+    CreateAppResultTypeDef,
     DeploymentCommandTypeDef,
+    CreateDeploymentResultTypeDef,
+    CreateInstanceResultTypeDef,
     RecipesTypeDef,
     VolumeConfigurationTypeDef,
+    CreateLayerResultTypeDef,
+    CreateStackResultTypeDef,
     CreateUserProfileRequestRequestTypeDef,
+    CreateUserProfileResultTypeDef,
     DeleteAppRequestRequestTypeDef,
     DeleteInstanceRequestRequestTypeDef,
     DeleteLayerRequestRequestTypeDef,
     DeleteStackRequestRequestTypeDef,
     DeleteUserProfileRequestRequestTypeDef,
     DeregisterEcsClusterRequestRequestTypeDef,
     DeregisterElasticIpRequestRequestTypeDef,
     DeregisterInstanceRequestRequestTypeDef,
     DeregisterRdsDbInstanceRequestRequestTypeDef,
     DeregisterVolumeRequestRequestTypeDef,
     WaiterConfigTypeDef,
     DescribeAppsRequestRequestTypeDef,
     DescribeCommandsRequestRequestTypeDef,
     DescribeDeploymentsRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeEcsClustersRequestDescribeEcsClustersPaginateTypeDef,
     DescribeEcsClustersRequestRequestTypeDef,
     EcsClusterTypeDef,
     DescribeElasticIpsRequestRequestTypeDef,
     ElasticIpTypeDef,
     DescribeElasticLoadBalancersRequestRequestTypeDef,
     ElasticLoadBalancerTypeDef,
     DescribeInstancesRequestRequestTypeDef,
@@ -494,42 +501,53 @@
     DescribeRaidArraysRequestRequestTypeDef,
     RaidArrayTypeDef,
     DescribeRdsDbInstancesRequestRequestTypeDef,
     RdsDbInstanceTypeDef,
     DescribeServiceErrorsRequestRequestTypeDef,
     ServiceErrorTypeDef,
     DescribeStackProvisioningParametersRequestRequestTypeDef,
+    DescribeStackProvisioningParametersResultTypeDef,
     DescribeStackSummaryRequestRequestTypeDef,
     DescribeStacksRequestRequestTypeDef,
     DescribeTimeBasedAutoScalingRequestRequestTypeDef,
     DescribeUserProfilesRequestRequestTypeDef,
     UserProfileTypeDef,
     DescribeVolumesRequestRequestTypeDef,
     VolumeTypeDef,
     DetachElasticLoadBalancerRequestRequestTypeDef,
     DisassociateElasticIpRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetHostnameSuggestionRequestRequestTypeDef,
+    GetHostnameSuggestionResultTypeDef,
     GrantAccessRequestRequestTypeDef,
     TemporaryCredentialTypeDef,
     InstanceIdentityTypeDef,
     ReportedOsTypeDef,
+    InstancesCountResponseMetadataTypeDef,
     InstancesCountTypeDef,
     ShutdownEventConfigurationTypeDef,
     ListTagsRequestRequestTypeDef,
+    ListTagsResultTypeDef,
     OperatingSystemConfigurationManagerTypeDef,
+    PaginatorConfigTypeDef,
     RebootInstanceRequestRequestTypeDef,
+    RecipesResponseMetadataTypeDef,
     RegisterEcsClusterRequestRequestTypeDef,
+    RegisterEcsClusterResultTypeDef,
     RegisterElasticIpRequestRequestTypeDef,
+    RegisterElasticIpResultTypeDef,
+    RegisterInstanceResultTypeDef,
     RegisterRdsDbInstanceRequestRequestTypeDef,
     RegisterVolumeRequestRequestTypeDef,
-    ServiceResourceLayerRequestTypeDef,
-    ServiceResourceStackRequestTypeDef,
-    ServiceResourceStackSummaryRequestTypeDef,
+    RegisterVolumeResultTypeDef,
+    ResponseMetadataTypeDef,
     SetPermissionRequestRequestTypeDef,
     WeeklyAutoScalingScheduleTypeDef,
+    SourceResponseMetadataTypeDef,
+    StackConfigurationManagerResponseMetadataTypeDef,
     StartInstanceRequestRequestTypeDef,
     StartStackRequestRequestTypeDef,
     StopInstanceRequestRequestTypeDef,
     StopStackRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UnassignInstanceRequestRequestTypeDef,
     UnassignVolumeRequestRequestTypeDef,
@@ -544,34 +562,14 @@
     DescribeAgentVersionsRequestRequestTypeDef,
     AppTypeDef,
     CreateAppRequestRequestTypeDef,
     UpdateAppRequestRequestTypeDef,
     LoadBasedAutoScalingConfigurationTypeDef,
     SetLoadBasedAutoScalingRequestRequestTypeDef,
     BlockDeviceMappingTypeDef,
-    ChefConfigurationResponseMetadataTypeDef,
-    CloneStackResultTypeDef,
-    CreateAppResultTypeDef,
-    CreateDeploymentResultTypeDef,
-    CreateInstanceResultTypeDef,
-    CreateLayerResultTypeDef,
-    CreateStackResultTypeDef,
-    CreateUserProfileResultTypeDef,
-    DescribeStackProvisioningParametersResultTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetHostnameSuggestionResultTypeDef,
-    InstancesCountResponseMetadataTypeDef,
-    ListTagsResultTypeDef,
-    RecipesResponseMetadataTypeDef,
-    RegisterEcsClusterResultTypeDef,
-    RegisterElasticIpResultTypeDef,
-    RegisterInstanceResultTypeDef,
-    RegisterVolumeResultTypeDef,
-    SourceResponseMetadataTypeDef,
-    StackConfigurationManagerResponseMetadataTypeDef,
     CloneStackRequestRequestTypeDef,
     CreateStackRequestRequestTypeDef,
     CreateStackRequestServiceResourceCreateStackTypeDef,
     StackTypeDef,
     UpdateStackRequestRequestTypeDef,
     CloudWatchLogsConfigurationResponseMetadataTypeDef,
     CloudWatchLogsConfigurationTypeDef,
@@ -580,15 +578,14 @@
     DeploymentTypeDef,
     DescribeAppsRequestAppExistsWaitTypeDef,
     DescribeDeploymentsRequestDeploymentSuccessfulWaitTypeDef,
     DescribeInstancesRequestInstanceOnlineWaitTypeDef,
     DescribeInstancesRequestInstanceRegisteredWaitTypeDef,
     DescribeInstancesRequestInstanceStoppedWaitTypeDef,
     DescribeInstancesRequestInstanceTerminatedWaitTypeDef,
-    DescribeEcsClustersRequestDescribeEcsClustersPaginateTypeDef,
     DescribeEcsClustersResultTypeDef,
     DescribeElasticIpsResultTypeDef,
     DescribeElasticLoadBalancersResultTypeDef,
     DescribeMyUserProfileResultTypeDef,
     DescribePermissionsResultTypeDef,
     DescribeRaidArraysResultTypeDef,
     DescribeRdsDbInstancesResultTypeDef,
@@ -629,43 +626,43 @@
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

### Comparing `types-aiobotocore-opsworks-2.5.0.post1/README.md` & `types-aiobotocore-opsworks-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-opsworks"></a>
 
 # types-aiobotocore-opsworks
 
 [![PyPI - types-aiobotocore-opsworks](https://img.shields.io/pypi/v/types-aiobotocore-opsworks.svg?color=blue)](https://pypi.org/project/types-aiobotocore-opsworks)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-opsworks.svg?color=blue)](https://pypi.org/project/types-aiobotocore-opsworks)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworks/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-opsworks?color=blue)](https://pypistats.org/packages/types-aiobotocore-opsworks)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.OpsWorks 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks)
+[aiobotocore.OpsWorks 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks)
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
 [types-aiobotocore-opsworks docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworks/).
 
 See how it helps to find and fix potential bugs:
 
@@ -419,37 +419,44 @@
     SslConfigurationTypeDef,
     AssignInstanceRequestRequestTypeDef,
     AssignVolumeRequestRequestTypeDef,
     AssociateElasticIpRequestRequestTypeDef,
     AttachElasticLoadBalancerRequestRequestTypeDef,
     AutoScalingThresholdsTypeDef,
     EbsBlockDeviceTypeDef,
-    ResponseMetadataTypeDef,
+    ChefConfigurationResponseMetadataTypeDef,
     ChefConfigurationTypeDef,
+    CloneStackResultTypeDef,
     CloudWatchLogsLogStreamTypeDef,
     CommandTypeDef,
+    CreateAppResultTypeDef,
     DeploymentCommandTypeDef,
+    CreateDeploymentResultTypeDef,
+    CreateInstanceResultTypeDef,
     RecipesTypeDef,
     VolumeConfigurationTypeDef,
+    CreateLayerResultTypeDef,
+    CreateStackResultTypeDef,
     CreateUserProfileRequestRequestTypeDef,
+    CreateUserProfileResultTypeDef,
     DeleteAppRequestRequestTypeDef,
     DeleteInstanceRequestRequestTypeDef,
     DeleteLayerRequestRequestTypeDef,
     DeleteStackRequestRequestTypeDef,
     DeleteUserProfileRequestRequestTypeDef,
     DeregisterEcsClusterRequestRequestTypeDef,
     DeregisterElasticIpRequestRequestTypeDef,
     DeregisterInstanceRequestRequestTypeDef,
     DeregisterRdsDbInstanceRequestRequestTypeDef,
     DeregisterVolumeRequestRequestTypeDef,
     WaiterConfigTypeDef,
     DescribeAppsRequestRequestTypeDef,
     DescribeCommandsRequestRequestTypeDef,
     DescribeDeploymentsRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeEcsClustersRequestDescribeEcsClustersPaginateTypeDef,
     DescribeEcsClustersRequestRequestTypeDef,
     EcsClusterTypeDef,
     DescribeElasticIpsRequestRequestTypeDef,
     ElasticIpTypeDef,
     DescribeElasticLoadBalancersRequestRequestTypeDef,
     ElasticLoadBalancerTypeDef,
     DescribeInstancesRequestRequestTypeDef,
@@ -461,42 +468,53 @@
     DescribeRaidArraysRequestRequestTypeDef,
     RaidArrayTypeDef,
     DescribeRdsDbInstancesRequestRequestTypeDef,
     RdsDbInstanceTypeDef,
     DescribeServiceErrorsRequestRequestTypeDef,
     ServiceErrorTypeDef,
     DescribeStackProvisioningParametersRequestRequestTypeDef,
+    DescribeStackProvisioningParametersResultTypeDef,
     DescribeStackSummaryRequestRequestTypeDef,
     DescribeStacksRequestRequestTypeDef,
     DescribeTimeBasedAutoScalingRequestRequestTypeDef,
     DescribeUserProfilesRequestRequestTypeDef,
     UserProfileTypeDef,
     DescribeVolumesRequestRequestTypeDef,
     VolumeTypeDef,
     DetachElasticLoadBalancerRequestRequestTypeDef,
     DisassociateElasticIpRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetHostnameSuggestionRequestRequestTypeDef,
+    GetHostnameSuggestionResultTypeDef,
     GrantAccessRequestRequestTypeDef,
     TemporaryCredentialTypeDef,
     InstanceIdentityTypeDef,
     ReportedOsTypeDef,
+    InstancesCountResponseMetadataTypeDef,
     InstancesCountTypeDef,
     ShutdownEventConfigurationTypeDef,
     ListTagsRequestRequestTypeDef,
+    ListTagsResultTypeDef,
     OperatingSystemConfigurationManagerTypeDef,
+    PaginatorConfigTypeDef,
     RebootInstanceRequestRequestTypeDef,
+    RecipesResponseMetadataTypeDef,
     RegisterEcsClusterRequestRequestTypeDef,
+    RegisterEcsClusterResultTypeDef,
     RegisterElasticIpRequestRequestTypeDef,
+    RegisterElasticIpResultTypeDef,
+    RegisterInstanceResultTypeDef,
     RegisterRdsDbInstanceRequestRequestTypeDef,
     RegisterVolumeRequestRequestTypeDef,
-    ServiceResourceLayerRequestTypeDef,
-    ServiceResourceStackRequestTypeDef,
-    ServiceResourceStackSummaryRequestTypeDef,
+    RegisterVolumeResultTypeDef,
+    ResponseMetadataTypeDef,
     SetPermissionRequestRequestTypeDef,
     WeeklyAutoScalingScheduleTypeDef,
+    SourceResponseMetadataTypeDef,
+    StackConfigurationManagerResponseMetadataTypeDef,
     StartInstanceRequestRequestTypeDef,
     StartStackRequestRequestTypeDef,
     StopInstanceRequestRequestTypeDef,
     StopStackRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UnassignInstanceRequestRequestTypeDef,
     UnassignVolumeRequestRequestTypeDef,
@@ -511,34 +529,14 @@
     DescribeAgentVersionsRequestRequestTypeDef,
     AppTypeDef,
     CreateAppRequestRequestTypeDef,
     UpdateAppRequestRequestTypeDef,
     LoadBasedAutoScalingConfigurationTypeDef,
     SetLoadBasedAutoScalingRequestRequestTypeDef,
     BlockDeviceMappingTypeDef,
-    ChefConfigurationResponseMetadataTypeDef,
-    CloneStackResultTypeDef,
-    CreateAppResultTypeDef,
-    CreateDeploymentResultTypeDef,
-    CreateInstanceResultTypeDef,
-    CreateLayerResultTypeDef,
-    CreateStackResultTypeDef,
-    CreateUserProfileResultTypeDef,
-    DescribeStackProvisioningParametersResultTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetHostnameSuggestionResultTypeDef,
-    InstancesCountResponseMetadataTypeDef,
-    ListTagsResultTypeDef,
-    RecipesResponseMetadataTypeDef,
-    RegisterEcsClusterResultTypeDef,
-    RegisterElasticIpResultTypeDef,
-    RegisterInstanceResultTypeDef,
-    RegisterVolumeResultTypeDef,
-    SourceResponseMetadataTypeDef,
-    StackConfigurationManagerResponseMetadataTypeDef,
     CloneStackRequestRequestTypeDef,
     CreateStackRequestRequestTypeDef,
     CreateStackRequestServiceResourceCreateStackTypeDef,
     StackTypeDef,
     UpdateStackRequestRequestTypeDef,
     CloudWatchLogsConfigurationResponseMetadataTypeDef,
     CloudWatchLogsConfigurationTypeDef,
@@ -547,15 +545,14 @@
     DeploymentTypeDef,
     DescribeAppsRequestAppExistsWaitTypeDef,
     DescribeDeploymentsRequestDeploymentSuccessfulWaitTypeDef,
     DescribeInstancesRequestInstanceOnlineWaitTypeDef,
     DescribeInstancesRequestInstanceRegisteredWaitTypeDef,
     DescribeInstancesRequestInstanceStoppedWaitTypeDef,
     DescribeInstancesRequestInstanceTerminatedWaitTypeDef,
-    DescribeEcsClustersRequestDescribeEcsClustersPaginateTypeDef,
     DescribeEcsClustersResultTypeDef,
     DescribeElasticIpsResultTypeDef,
     DescribeElasticLoadBalancersResultTypeDef,
     DescribeMyUserProfileResultTypeDef,
     DescribePermissionsResultTypeDef,
     DescribeRaidArraysResultTypeDef,
     DescribeRdsDbInstancesResultTypeDef,
@@ -596,43 +593,43 @@
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

### Comparing `types-aiobotocore-opsworks-2.5.0.post1/setup.py` & `types-aiobotocore-opsworks-2.5.1/setup.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-opsworks.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-opsworks",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_opsworks"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.OpsWorks 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.OpsWorks 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworks/"
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

### Comparing `types-aiobotocore-opsworks-2.5.0.post1/types_aiobotocore_opsworks/__init__.py` & `types-aiobotocore-opsworks-2.5.1/types_aiobotocore_opsworks/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-opsworks-2.5.0.post1/types_aiobotocore_opsworks/__init__.pyi` & `types-aiobotocore-opsworks-2.5.1/types_aiobotocore_opsworks/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-opsworks-2.5.0.post1/types_aiobotocore_opsworks/__main__.py` & `types-aiobotocore-opsworks-2.5.1/types_aiobotocore_opsworks/__main__.py`

 * *Files 5% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.OpsWorks 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.OpsWorks 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworks//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks\nOther"
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

### Comparing `types-aiobotocore-opsworks-2.5.0.post1/types_aiobotocore_opsworks/client.py` & `types-aiobotocore-opsworks-2.5.1/types_aiobotocore_opsworks/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -625,15 +625,15 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.describe_stack_provisioning_parameters)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworks/client/#describe_stack_provisioning_parameters)
         """
 
     async def describe_stack_summary(self, *, StackId: str) -> DescribeStackSummaryResultTypeDef:
         """
         Describes the number of layers and apps in a specified stack, and the number of
-        instances in each state, such as `running_setup` or `online` .
+        instances in each state, such as `running_setup` or `online`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.describe_stack_summary)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworks/client/#describe_stack_summary)
         """
 
     async def describe_stacks(
         self, *, StackIds: Sequence[str] = ...
```

### Comparing `types-aiobotocore-opsworks-2.5.0.post1/types_aiobotocore_opsworks/client.pyi` & `types-aiobotocore-opsworks-2.5.1/types_aiobotocore_opsworks/client.pyi`

 * *Files 0% similar despite different names*

```diff
@@ -580,15 +580,15 @@
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.describe_stack_provisioning_parameters)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworks/client/#describe_stack_provisioning_parameters)
         """
     async def describe_stack_summary(self, *, StackId: str) -> DescribeStackSummaryResultTypeDef:
         """
         Describes the number of layers and apps in a specified stack, and the number of
-        instances in each state, such as `running_setup` or `online` .
+        instances in each state, such as `running_setup` or `online`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Client.describe_stack_summary)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworks/client/#describe_stack_summary)
         """
     async def describe_stacks(
         self, *, StackIds: Sequence[str] = ...
     ) -> DescribeStacksResultTypeDef:
```

### Comparing `types-aiobotocore-opsworks-2.5.0.post1/types_aiobotocore_opsworks/literals.py` & `types-aiobotocore-opsworks-2.5.1/types_aiobotocore_opsworks/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -279,14 +279,15 @@
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
@@ -365,14 +366,15 @@
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
@@ -383,14 +385,15 @@
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
@@ -426,14 +429,15 @@
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
@@ -452,16 +456,19 @@
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
@@ -545,15 +552,17 @@
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

### Comparing `types-aiobotocore-opsworks-2.5.0.post1/types_aiobotocore_opsworks/literals.pyi` & `types-aiobotocore-opsworks-2.5.1/types_aiobotocore_opsworks/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -277,14 +277,15 @@
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
@@ -363,14 +364,15 @@
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
@@ -381,14 +383,15 @@
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
@@ -424,14 +427,15 @@
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
@@ -450,16 +454,19 @@
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
@@ -543,15 +550,17 @@
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

### Comparing `types-aiobotocore-opsworks-2.5.0.post1/types_aiobotocore_opsworks/paginator.py` & `types-aiobotocore-opsworks-2.5.1/types_aiobotocore_opsworks/paginator.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -16,51 +16,41 @@
     session = get_session()
     with session.create_client("opsworks") as client:
         client: OpsWorksClient
 
         describe_ecs_clusters_paginator: DescribeEcsClustersPaginator = client.get_paginator("describe_ecs_clusters")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import DescribeEcsClustersResultTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("DescribeEcsClustersPaginator",)
 
-
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
-
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
-
 class DescribeEcsClustersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Paginator.DescribeEcsClusters)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworks/paginators/#describeecsclusterspaginator)
     """
 
     def paginate(
         self,
         *,
         EcsClusterArns: Sequence[str] = ...,
         StackId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEcsClustersResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Paginator.DescribeEcsClusters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworks/paginators/#describeecsclusterspaginator)
         """
```

### Comparing `types-aiobotocore-opsworks-2.5.0.post1/types_aiobotocore_opsworks/paginator.pyi` & `types-aiobotocore-opsworks-2.5.1/types_aiobotocore_opsworks/paginator.py`

 * *Files 10% similar despite different names*

```diff
@@ -16,47 +16,44 @@
     session = get_session()
     with session.create_client("opsworks") as client:
         client: OpsWorksClient
 
         describe_ecs_clusters_paginator: DescribeEcsClustersPaginator = client.get_paginator("describe_ecs_clusters")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import DescribeEcsClustersResultTypeDef, PaginatorConfigTypeDef
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("DescribeEcsClustersPaginator",)
 
+
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
+
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
         Proxy method to specify iterator item type.
         """
 
+
 class DescribeEcsClustersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Paginator.DescribeEcsClusters)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworks/paginators/#describeecsclusterspaginator)
     """
 
     def paginate(
         self,
         *,
         EcsClusterArns: Sequence[str] = ...,
         StackId: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEcsClustersResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks.Paginator.DescribeEcsClusters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworks/paginators/#describeecsclusterspaginator)
         """
```

### Comparing `types-aiobotocore-opsworks-2.5.0.post1/types_aiobotocore_opsworks/service_resource.py` & `types-aiobotocore-opsworks-2.5.1/types_aiobotocore_opsworks/service_resource.py`

 * *Files 1% similar despite different names*

```diff
@@ -17,15 +17,15 @@
 
         my_layer: opsworks_resources.Layer = resource.Layer(...)
         my_stack: opsworks_resources.Stack = resource.Stack(...)
         my_stack_summary: opsworks_resources.StackSummary = resource.StackSummary(...)
 ```
 """
 import sys
-from typing import Awaitable, Dict, List, Mapping, NoReturn, Sequence
+from typing import AsyncIterator, Awaitable, Dict, List, Mapping, NoReturn, Sequence
 
 from .client import OpsWorksClient
 from .literals import LayerAttributesKeysType, LayerTypeType, RootDeviceTypeType
 from .type_defs import (
     ChefConfigurationResponseMetadataTypeDef,
     ChefConfigurationTypeDef,
     CloudWatchLogsConfigurationResponseMetadataTypeDef,
@@ -46,18 +46,14 @@
     from aioboto3.resources.base import AIOBoto3ServiceResource
 except (ModuleNotFoundError, ImportError):
     from builtins import object as AIOBoto3ServiceResource
 try:
     from aioboto3.resources.collection import AIOResourceCollection
 except (ModuleNotFoundError, ImportError):
     from builtins import object as AIOResourceCollection
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 try:
     from boto3.resources.base import ResourceMeta
 except (ModuleNotFoundError, ImportError):
```

### Comparing `types-aiobotocore-opsworks-2.5.0.post1/types_aiobotocore_opsworks/service_resource.pyi` & `types-aiobotocore-opsworks-2.5.1/types_aiobotocore_opsworks/service_resource.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -17,15 +17,15 @@
 
         my_layer: opsworks_resources.Layer = resource.Layer(...)
         my_stack: opsworks_resources.Stack = resource.Stack(...)
         my_stack_summary: opsworks_resources.StackSummary = resource.StackSummary(...)
 ```
 """
 import sys
-from typing import Awaitable, Dict, List, Mapping, NoReturn, Sequence
+from typing import AsyncIterator, Awaitable, Dict, List, Mapping, NoReturn, Sequence
 
 from .client import OpsWorksClient
 from .literals import LayerAttributesKeysType, LayerTypeType, RootDeviceTypeType
 from .type_defs import (
     ChefConfigurationResponseMetadataTypeDef,
     ChefConfigurationTypeDef,
     CloudWatchLogsConfigurationResponseMetadataTypeDef,
@@ -46,18 +46,14 @@
     from aioboto3.resources.base import AIOBoto3ServiceResource
 except (ModuleNotFoundError, ImportError):
     from builtins import object as AIOBoto3ServiceResource
 try:
     from aioboto3.resources.collection import AIOResourceCollection
 except (ModuleNotFoundError, ImportError):
     from builtins import object as AIOResourceCollection
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 try:
     from boto3.resources.base import ResourceMeta
 except (ModuleNotFoundError, ImportError):
```

### Comparing `types-aiobotocore-opsworks-2.5.0.post1/types_aiobotocore_opsworks/type_defs.py` & `types-aiobotocore-opsworks-2.5.1/types_aiobotocore_opsworks/type_defs.py`

 * *Files 3% similar despite different names*

```diff
@@ -49,37 +49,44 @@
     "SslConfigurationTypeDef",
     "AssignInstanceRequestRequestTypeDef",
     "AssignVolumeRequestRequestTypeDef",
     "AssociateElasticIpRequestRequestTypeDef",
     "AttachElasticLoadBalancerRequestRequestTypeDef",
     "AutoScalingThresholdsTypeDef",
     "EbsBlockDeviceTypeDef",
-    "ResponseMetadataTypeDef",
+    "ChefConfigurationResponseMetadataTypeDef",
     "ChefConfigurationTypeDef",
+    "CloneStackResultTypeDef",
     "CloudWatchLogsLogStreamTypeDef",
     "CommandTypeDef",
+    "CreateAppResultTypeDef",
     "DeploymentCommandTypeDef",
+    "CreateDeploymentResultTypeDef",
+    "CreateInstanceResultTypeDef",
     "RecipesTypeDef",
     "VolumeConfigurationTypeDef",
+    "CreateLayerResultTypeDef",
+    "CreateStackResultTypeDef",
     "CreateUserProfileRequestRequestTypeDef",
+    "CreateUserProfileResultTypeDef",
     "DeleteAppRequestRequestTypeDef",
     "DeleteInstanceRequestRequestTypeDef",
     "DeleteLayerRequestRequestTypeDef",
     "DeleteStackRequestRequestTypeDef",
     "DeleteUserProfileRequestRequestTypeDef",
     "DeregisterEcsClusterRequestRequestTypeDef",
     "DeregisterElasticIpRequestRequestTypeDef",
     "DeregisterInstanceRequestRequestTypeDef",
     "DeregisterRdsDbInstanceRequestRequestTypeDef",
     "DeregisterVolumeRequestRequestTypeDef",
     "WaiterConfigTypeDef",
     "DescribeAppsRequestRequestTypeDef",
     "DescribeCommandsRequestRequestTypeDef",
     "DescribeDeploymentsRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeEcsClustersRequestDescribeEcsClustersPaginateTypeDef",
     "DescribeEcsClustersRequestRequestTypeDef",
     "EcsClusterTypeDef",
     "DescribeElasticIpsRequestRequestTypeDef",
     "ElasticIpTypeDef",
     "DescribeElasticLoadBalancersRequestRequestTypeDef",
     "ElasticLoadBalancerTypeDef",
     "DescribeInstancesRequestRequestTypeDef",
@@ -91,42 +98,53 @@
     "DescribeRaidArraysRequestRequestTypeDef",
     "RaidArrayTypeDef",
     "DescribeRdsDbInstancesRequestRequestTypeDef",
     "RdsDbInstanceTypeDef",
     "DescribeServiceErrorsRequestRequestTypeDef",
     "ServiceErrorTypeDef",
     "DescribeStackProvisioningParametersRequestRequestTypeDef",
+    "DescribeStackProvisioningParametersResultTypeDef",
     "DescribeStackSummaryRequestRequestTypeDef",
     "DescribeStacksRequestRequestTypeDef",
     "DescribeTimeBasedAutoScalingRequestRequestTypeDef",
     "DescribeUserProfilesRequestRequestTypeDef",
     "UserProfileTypeDef",
     "DescribeVolumesRequestRequestTypeDef",
     "VolumeTypeDef",
     "DetachElasticLoadBalancerRequestRequestTypeDef",
     "DisassociateElasticIpRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetHostnameSuggestionRequestRequestTypeDef",
+    "GetHostnameSuggestionResultTypeDef",
     "GrantAccessRequestRequestTypeDef",
     "TemporaryCredentialTypeDef",
     "InstanceIdentityTypeDef",
     "ReportedOsTypeDef",
+    "InstancesCountResponseMetadataTypeDef",
     "InstancesCountTypeDef",
     "ShutdownEventConfigurationTypeDef",
     "ListTagsRequestRequestTypeDef",
+    "ListTagsResultTypeDef",
     "OperatingSystemConfigurationManagerTypeDef",
+    "PaginatorConfigTypeDef",
     "RebootInstanceRequestRequestTypeDef",
+    "RecipesResponseMetadataTypeDef",
     "RegisterEcsClusterRequestRequestTypeDef",
+    "RegisterEcsClusterResultTypeDef",
     "RegisterElasticIpRequestRequestTypeDef",
+    "RegisterElasticIpResultTypeDef",
+    "RegisterInstanceResultTypeDef",
     "RegisterRdsDbInstanceRequestRequestTypeDef",
     "RegisterVolumeRequestRequestTypeDef",
-    "ServiceResourceLayerRequestTypeDef",
-    "ServiceResourceStackRequestTypeDef",
-    "ServiceResourceStackSummaryRequestTypeDef",
+    "RegisterVolumeResultTypeDef",
+    "ResponseMetadataTypeDef",
     "SetPermissionRequestRequestTypeDef",
     "WeeklyAutoScalingScheduleTypeDef",
+    "SourceResponseMetadataTypeDef",
+    "StackConfigurationManagerResponseMetadataTypeDef",
     "StartInstanceRequestRequestTypeDef",
     "StartStackRequestRequestTypeDef",
     "StopInstanceRequestRequestTypeDef",
     "StopStackRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UnassignInstanceRequestRequestTypeDef",
     "UnassignVolumeRequestRequestTypeDef",
@@ -141,34 +159,14 @@
     "DescribeAgentVersionsRequestRequestTypeDef",
     "AppTypeDef",
     "CreateAppRequestRequestTypeDef",
     "UpdateAppRequestRequestTypeDef",
     "LoadBasedAutoScalingConfigurationTypeDef",
     "SetLoadBasedAutoScalingRequestRequestTypeDef",
     "BlockDeviceMappingTypeDef",
-    "ChefConfigurationResponseMetadataTypeDef",
-    "CloneStackResultTypeDef",
-    "CreateAppResultTypeDef",
-    "CreateDeploymentResultTypeDef",
-    "CreateInstanceResultTypeDef",
-    "CreateLayerResultTypeDef",
-    "CreateStackResultTypeDef",
-    "CreateUserProfileResultTypeDef",
-    "DescribeStackProvisioningParametersResultTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetHostnameSuggestionResultTypeDef",
-    "InstancesCountResponseMetadataTypeDef",
-    "ListTagsResultTypeDef",
-    "RecipesResponseMetadataTypeDef",
-    "RegisterEcsClusterResultTypeDef",
-    "RegisterElasticIpResultTypeDef",
-    "RegisterInstanceResultTypeDef",
-    "RegisterVolumeResultTypeDef",
-    "SourceResponseMetadataTypeDef",
-    "StackConfigurationManagerResponseMetadataTypeDef",
     "CloneStackRequestRequestTypeDef",
     "CreateStackRequestRequestTypeDef",
     "CreateStackRequestServiceResourceCreateStackTypeDef",
     "StackTypeDef",
     "UpdateStackRequestRequestTypeDef",
     "CloudWatchLogsConfigurationResponseMetadataTypeDef",
     "CloudWatchLogsConfigurationTypeDef",
@@ -177,15 +175,14 @@
     "DeploymentTypeDef",
     "DescribeAppsRequestAppExistsWaitTypeDef",
     "DescribeDeploymentsRequestDeploymentSuccessfulWaitTypeDef",
     "DescribeInstancesRequestInstanceOnlineWaitTypeDef",
     "DescribeInstancesRequestInstanceRegisteredWaitTypeDef",
     "DescribeInstancesRequestInstanceStoppedWaitTypeDef",
     "DescribeInstancesRequestInstanceTerminatedWaitTypeDef",
-    "DescribeEcsClustersRequestDescribeEcsClustersPaginateTypeDef",
     "DescribeEcsClustersResultTypeDef",
     "DescribeElasticIpsResultTypeDef",
     "DescribeElasticLoadBalancersResultTypeDef",
     "DescribeMyUserProfileResultTypeDef",
     "DescribePermissionsResultTypeDef",
     "DescribeRaidArraysResultTypeDef",
     "DescribeRdsDbInstancesResultTypeDef",
@@ -373,34 +370,40 @@
         "VolumeSize": int,
         "VolumeType": VolumeTypeType,
         "DeleteOnTermination": bool,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+ChefConfigurationResponseMetadataTypeDef = TypedDict(
+    "ChefConfigurationResponseMetadataTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ManageBerkshelf": bool,
+        "BerkshelfVersion": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ChefConfigurationTypeDef = TypedDict(
     "ChefConfigurationTypeDef",
     {
         "ManageBerkshelf": bool,
         "BerkshelfVersion": str,
     },
     total=False,
 )
 
+CloneStackResultTypeDef = TypedDict(
+    "CloneStackResultTypeDef",
+    {
+        "StackId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CloudWatchLogsLogStreamTypeDef = TypedDict(
     "CloudWatchLogsLogStreamTypeDef",
     {
         "LogGroupName": str,
         "DatetimeFormat": str,
         "TimeZone": CloudWatchLogsTimeZoneType,
         "File": str,
@@ -428,14 +431,22 @@
         "ExitCode": int,
         "LogUrl": str,
         "Type": str,
     },
     total=False,
 )
 
+CreateAppResultTypeDef = TypedDict(
+    "CreateAppResultTypeDef",
+    {
+        "AppId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeploymentCommandTypeDef = TypedDict(
     "_RequiredDeploymentCommandTypeDef",
     {
         "Name": DeploymentCommandNameType,
     },
 )
 _OptionalDeploymentCommandTypeDef = TypedDict(
@@ -449,14 +460,30 @@
 
 class DeploymentCommandTypeDef(
     _RequiredDeploymentCommandTypeDef, _OptionalDeploymentCommandTypeDef
 ):
     pass
 
 
+CreateDeploymentResultTypeDef = TypedDict(
+    "CreateDeploymentResultTypeDef",
+    {
+        "DeploymentId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateInstanceResultTypeDef = TypedDict(
+    "CreateInstanceResultTypeDef",
+    {
+        "InstanceId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RecipesTypeDef = TypedDict(
     "RecipesTypeDef",
     {
         "Setup": Sequence[str],
         "Configure": Sequence[str],
         "Deploy": Sequence[str],
         "Undeploy": Sequence[str],
@@ -487,14 +514,30 @@
 
 class VolumeConfigurationTypeDef(
     _RequiredVolumeConfigurationTypeDef, _OptionalVolumeConfigurationTypeDef
 ):
     pass
 
 
+CreateLayerResultTypeDef = TypedDict(
+    "CreateLayerResultTypeDef",
+    {
+        "LayerId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateStackResultTypeDef = TypedDict(
+    "CreateStackResultTypeDef",
+    {
+        "StackId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateUserProfileRequestRequestTypeDef = TypedDict(
     "_RequiredCreateUserProfileRequestRequestTypeDef",
     {
         "IamUserArn": str,
     },
 )
 _OptionalCreateUserProfileRequestRequestTypeDef = TypedDict(
@@ -510,14 +553,22 @@
 
 class CreateUserProfileRequestRequestTypeDef(
     _RequiredCreateUserProfileRequestRequestTypeDef, _OptionalCreateUserProfileRequestRequestTypeDef
 ):
     pass
 
 
+CreateUserProfileResultTypeDef = TypedDict(
+    "CreateUserProfileResultTypeDef",
+    {
+        "IamUserArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteAppRequestRequestTypeDef = TypedDict(
     "DeleteAppRequestRequestTypeDef",
     {
         "AppId": str,
     },
 )
 
@@ -633,20 +684,20 @@
         "StackId": str,
         "AppId": str,
         "DeploymentIds": Sequence[str],
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeEcsClustersRequestDescribeEcsClustersPaginateTypeDef = TypedDict(
+    "DescribeEcsClustersRequestDescribeEcsClustersPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "EcsClusterArns": Sequence[str],
+        "StackId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeEcsClustersRequestRequestTypeDef = TypedDict(
     "DescribeEcsClustersRequestRequestTypeDef",
     {
@@ -868,14 +919,23 @@
 DescribeStackProvisioningParametersRequestRequestTypeDef = TypedDict(
     "DescribeStackProvisioningParametersRequestRequestTypeDef",
     {
         "StackId": str,
     },
 )
 
+DescribeStackProvisioningParametersResultTypeDef = TypedDict(
+    "DescribeStackProvisioningParametersResultTypeDef",
+    {
+        "AgentInstallerUrl": str,
+        "Parameters": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeStackSummaryRequestRequestTypeDef = TypedDict(
     "DescribeStackSummaryRequestRequestTypeDef",
     {
         "StackId": str,
     },
 )
 
@@ -957,21 +1017,37 @@
 DisassociateElasticIpRequestRequestTypeDef = TypedDict(
     "DisassociateElasticIpRequestRequestTypeDef",
     {
         "ElasticIp": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetHostnameSuggestionRequestRequestTypeDef = TypedDict(
     "GetHostnameSuggestionRequestRequestTypeDef",
     {
         "LayerId": str,
     },
 )
 
+GetHostnameSuggestionResultTypeDef = TypedDict(
+    "GetHostnameSuggestionResultTypeDef",
+    {
+        "LayerId": str,
+        "Hostname": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGrantAccessRequestRequestTypeDef = TypedDict(
     "_RequiredGrantAccessRequestRequestTypeDef",
     {
         "InstanceId": str,
     },
 )
 _OptionalGrantAccessRequestRequestTypeDef = TypedDict(
@@ -1015,14 +1091,41 @@
         "Family": str,
         "Name": str,
         "Version": str,
     },
     total=False,
 )
 
+InstancesCountResponseMetadataTypeDef = TypedDict(
+    "InstancesCountResponseMetadataTypeDef",
+    {
+        "Assigning": int,
+        "Booting": int,
+        "ConnectionLost": int,
+        "Deregistering": int,
+        "Online": int,
+        "Pending": int,
+        "Rebooting": int,
+        "Registered": int,
+        "Registering": int,
+        "Requested": int,
+        "RunningSetup": int,
+        "SetupFailed": int,
+        "ShuttingDown": int,
+        "StartFailed": int,
+        "StopFailed": int,
+        "Stopped": int,
+        "Stopping": int,
+        "Terminated": int,
+        "Terminating": int,
+        "Unassigning": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 InstancesCountTypeDef = TypedDict(
     "InstancesCountTypeDef",
     {
         "Assigning": int,
         "Booting": int,
         "ConnectionLost": int,
         "Deregistering": int,
@@ -1073,46 +1176,101 @@
 
 class ListTagsRequestRequestTypeDef(
     _RequiredListTagsRequestRequestTypeDef, _OptionalListTagsRequestRequestTypeDef
 ):
     pass
 
 
+ListTagsResultTypeDef = TypedDict(
+    "ListTagsResultTypeDef",
+    {
+        "Tags": Dict[str, str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 OperatingSystemConfigurationManagerTypeDef = TypedDict(
     "OperatingSystemConfigurationManagerTypeDef",
     {
         "Name": str,
         "Version": str,
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
 RebootInstanceRequestRequestTypeDef = TypedDict(
     "RebootInstanceRequestRequestTypeDef",
     {
         "InstanceId": str,
     },
 )
 
+RecipesResponseMetadataTypeDef = TypedDict(
+    "RecipesResponseMetadataTypeDef",
+    {
+        "Setup": List[str],
+        "Configure": List[str],
+        "Deploy": List[str],
+        "Undeploy": List[str],
+        "Shutdown": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RegisterEcsClusterRequestRequestTypeDef = TypedDict(
     "RegisterEcsClusterRequestRequestTypeDef",
     {
         "EcsClusterArn": str,
         "StackId": str,
     },
 )
 
+RegisterEcsClusterResultTypeDef = TypedDict(
+    "RegisterEcsClusterResultTypeDef",
+    {
+        "EcsClusterArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RegisterElasticIpRequestRequestTypeDef = TypedDict(
     "RegisterElasticIpRequestRequestTypeDef",
     {
         "ElasticIp": str,
         "StackId": str,
     },
 )
 
+RegisterElasticIpResultTypeDef = TypedDict(
+    "RegisterElasticIpResultTypeDef",
+    {
+        "ElasticIp": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+RegisterInstanceResultTypeDef = TypedDict(
+    "RegisterInstanceResultTypeDef",
+    {
+        "InstanceId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RegisterRdsDbInstanceRequestRequestTypeDef = TypedDict(
     "RegisterRdsDbInstanceRequestRequestTypeDef",
     {
         "StackId": str,
         "RdsDbInstanceArn": str,
         "DbUser": str,
         "DbPassword": str,
@@ -1136,32 +1294,30 @@
 
 class RegisterVolumeRequestRequestTypeDef(
     _RequiredRegisterVolumeRequestRequestTypeDef, _OptionalRegisterVolumeRequestRequestTypeDef
 ):
     pass
 
 
-ServiceResourceLayerRequestTypeDef = TypedDict(
-    "ServiceResourceLayerRequestTypeDef",
-    {
-        "id": str,
-    },
-)
-
-ServiceResourceStackRequestTypeDef = TypedDict(
-    "ServiceResourceStackRequestTypeDef",
+RegisterVolumeResultTypeDef = TypedDict(
+    "RegisterVolumeResultTypeDef",
     {
-        "id": str,
+        "VolumeId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ServiceResourceStackSummaryRequestTypeDef = TypedDict(
-    "ServiceResourceStackSummaryRequestTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "stack_id": str,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
 _RequiredSetPermissionRequestRequestTypeDef = TypedDict(
     "_RequiredSetPermissionRequestRequestTypeDef",
     {
         "StackId": str,
@@ -1195,14 +1351,36 @@
         "Friday": Dict[str, str],
         "Saturday": Dict[str, str],
         "Sunday": Dict[str, str],
     },
     total=False,
 )
 
+SourceResponseMetadataTypeDef = TypedDict(
+    "SourceResponseMetadataTypeDef",
+    {
+        "Type": SourceTypeType,
+        "Url": str,
+        "Username": str,
+        "Password": str,
+        "SshKey": str,
+        "Revision": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StackConfigurationManagerResponseMetadataTypeDef = TypedDict(
+    "StackConfigurationManagerResponseMetadataTypeDef",
+    {
+        "Name": str,
+        "Version": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartInstanceRequestRequestTypeDef = TypedDict(
     "StartInstanceRequestRequestTypeDef",
     {
         "InstanceId": str,
     },
 )
 
@@ -1541,206 +1719,14 @@
         "NoDevice": str,
         "VirtualName": str,
         "Ebs": EbsBlockDeviceTypeDef,
     },
     total=False,
 )
 
-ChefConfigurationResponseMetadataTypeDef = TypedDict(
-    "ChefConfigurationResponseMetadataTypeDef",
-    {
-        "ManageBerkshelf": bool,
-        "BerkshelfVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CloneStackResultTypeDef = TypedDict(
-    "CloneStackResultTypeDef",
-    {
-        "StackId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateAppResultTypeDef = TypedDict(
-    "CreateAppResultTypeDef",
-    {
-        "AppId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDeploymentResultTypeDef = TypedDict(
-    "CreateDeploymentResultTypeDef",
-    {
-        "DeploymentId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateInstanceResultTypeDef = TypedDict(
-    "CreateInstanceResultTypeDef",
-    {
-        "InstanceId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateLayerResultTypeDef = TypedDict(
-    "CreateLayerResultTypeDef",
-    {
-        "LayerId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateStackResultTypeDef = TypedDict(
-    "CreateStackResultTypeDef",
-    {
-        "StackId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateUserProfileResultTypeDef = TypedDict(
-    "CreateUserProfileResultTypeDef",
-    {
-        "IamUserArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeStackProvisioningParametersResultTypeDef = TypedDict(
-    "DescribeStackProvisioningParametersResultTypeDef",
-    {
-        "AgentInstallerUrl": str,
-        "Parameters": Dict[str, str],
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
-GetHostnameSuggestionResultTypeDef = TypedDict(
-    "GetHostnameSuggestionResultTypeDef",
-    {
-        "LayerId": str,
-        "Hostname": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-InstancesCountResponseMetadataTypeDef = TypedDict(
-    "InstancesCountResponseMetadataTypeDef",
-    {
-        "Assigning": int,
-        "Booting": int,
-        "ConnectionLost": int,
-        "Deregistering": int,
-        "Online": int,
-        "Pending": int,
-        "Rebooting": int,
-        "Registered": int,
-        "Registering": int,
-        "Requested": int,
-        "RunningSetup": int,
-        "SetupFailed": int,
-        "ShuttingDown": int,
-        "StartFailed": int,
-        "StopFailed": int,
-        "Stopped": int,
-        "Stopping": int,
-        "Terminated": int,
-        "Terminating": int,
-        "Unassigning": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsResultTypeDef = TypedDict(
-    "ListTagsResultTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RecipesResponseMetadataTypeDef = TypedDict(
-    "RecipesResponseMetadataTypeDef",
-    {
-        "Setup": List[str],
-        "Configure": List[str],
-        "Deploy": List[str],
-        "Undeploy": List[str],
-        "Shutdown": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RegisterEcsClusterResultTypeDef = TypedDict(
-    "RegisterEcsClusterResultTypeDef",
-    {
-        "EcsClusterArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RegisterElasticIpResultTypeDef = TypedDict(
-    "RegisterElasticIpResultTypeDef",
-    {
-        "ElasticIp": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RegisterInstanceResultTypeDef = TypedDict(
-    "RegisterInstanceResultTypeDef",
-    {
-        "InstanceId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RegisterVolumeResultTypeDef = TypedDict(
-    "RegisterVolumeResultTypeDef",
-    {
-        "VolumeId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SourceResponseMetadataTypeDef = TypedDict(
-    "SourceResponseMetadataTypeDef",
-    {
-        "Type": SourceTypeType,
-        "Url": str,
-        "Username": str,
-        "Password": str,
-        "SshKey": str,
-        "Revision": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StackConfigurationManagerResponseMetadataTypeDef = TypedDict(
-    "StackConfigurationManagerResponseMetadataTypeDef",
-    {
-        "Name": str,
-        "Version": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 _RequiredCloneStackRequestRequestTypeDef = TypedDict(
     "_RequiredCloneStackRequestRequestTypeDef",
     {
         "SourceStackId": str,
         "ServiceRoleArn": str,
     },
 )
@@ -1922,15 +1908,15 @@
 
 
 CloudWatchLogsConfigurationResponseMetadataTypeDef = TypedDict(
     "CloudWatchLogsConfigurationResponseMetadataTypeDef",
     {
         "Enabled": bool,
         "LogStreams": List[CloudWatchLogsLogStreamTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CloudWatchLogsConfigurationTypeDef = TypedDict(
     "CloudWatchLogsConfigurationTypeDef",
     {
         "Enabled": bool,
@@ -1939,15 +1925,15 @@
     total=False,
 )
 
 DescribeCommandsResultTypeDef = TypedDict(
     "DescribeCommandsResultTypeDef",
     {
         "Commands": List[CommandTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateDeploymentRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDeploymentRequestRequestTypeDef",
     {
         "StackId": str,
@@ -2053,110 +2039,100 @@
         "LayerId": str,
         "InstanceIds": Sequence[str],
         "WaiterConfig": WaiterConfigTypeDef,
     },
     total=False,
 )
 
-DescribeEcsClustersRequestDescribeEcsClustersPaginateTypeDef = TypedDict(
-    "DescribeEcsClustersRequestDescribeEcsClustersPaginateTypeDef",
-    {
-        "EcsClusterArns": Sequence[str],
-        "StackId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 DescribeEcsClustersResultTypeDef = TypedDict(
     "DescribeEcsClustersResultTypeDef",
     {
         "EcsClusters": List[EcsClusterTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeElasticIpsResultTypeDef = TypedDict(
     "DescribeElasticIpsResultTypeDef",
     {
         "ElasticIps": List[ElasticIpTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeElasticLoadBalancersResultTypeDef = TypedDict(
     "DescribeElasticLoadBalancersResultTypeDef",
     {
         "ElasticLoadBalancers": List[ElasticLoadBalancerTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeMyUserProfileResultTypeDef = TypedDict(
     "DescribeMyUserProfileResultTypeDef",
     {
         "UserProfile": SelfUserProfileTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribePermissionsResultTypeDef = TypedDict(
     "DescribePermissionsResultTypeDef",
     {
         "Permissions": List[PermissionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeRaidArraysResultTypeDef = TypedDict(
     "DescribeRaidArraysResultTypeDef",
     {
         "RaidArrays": List[RaidArrayTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeRdsDbInstancesResultTypeDef = TypedDict(
     "DescribeRdsDbInstancesResultTypeDef",
     {
         "RdsDbInstances": List[RdsDbInstanceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeServiceErrorsResultTypeDef = TypedDict(
     "DescribeServiceErrorsResultTypeDef",
     {
         "ServiceErrors": List[ServiceErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeUserProfilesResultTypeDef = TypedDict(
     "DescribeUserProfilesResultTypeDef",
     {
         "UserProfiles": List[UserProfileTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeVolumesResultTypeDef = TypedDict(
     "DescribeVolumesResultTypeDef",
     {
         "Volumes": List[VolumeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GrantAccessResultTypeDef = TypedDict(
     "GrantAccessResultTypeDef",
     {
         "TemporaryCredential": TemporaryCredentialTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredRegisterInstanceRequestRequestTypeDef = TypedDict(
     "_RequiredRegisterInstanceRequestRequestTypeDef",
     {
         "StackId": str,
@@ -2195,15 +2171,15 @@
     total=False,
 )
 
 LifecycleEventConfigurationResponseMetadataTypeDef = TypedDict(
     "LifecycleEventConfigurationResponseMetadataTypeDef",
     {
         "Shutdown": ShutdownEventConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LifecycleEventConfigurationTypeDef = TypedDict(
     "LifecycleEventConfigurationTypeDef",
     {
         "Shutdown": ShutdownEventConfigurationTypeDef,
@@ -2256,31 +2232,31 @@
     total=False,
 )
 
 DescribeAgentVersionsResultTypeDef = TypedDict(
     "DescribeAgentVersionsResultTypeDef",
     {
         "AgentVersions": List[AgentVersionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAppsResultTypeDef = TypedDict(
     "DescribeAppsResultTypeDef",
     {
         "Apps": List[AppTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeLoadBasedAutoScalingResultTypeDef = TypedDict(
     "DescribeLoadBasedAutoScalingResultTypeDef",
     {
         "LoadBasedAutoScalingConfigurations": List[LoadBasedAutoScalingConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateInstanceRequestRequestTypeDef = TypedDict(
     "_RequiredCreateInstanceRequestRequestTypeDef",
     {
         "StackId": str,
@@ -2365,31 +2341,31 @@
     total=False,
 )
 
 DescribeStacksResultTypeDef = TypedDict(
     "DescribeStacksResultTypeDef",
     {
         "Stacks": List[StackTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDeploymentsResultTypeDef = TypedDict(
     "DescribeDeploymentsResultTypeDef",
     {
         "Deployments": List[DeploymentTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeStackSummaryResultTypeDef = TypedDict(
     "DescribeStackSummaryResultTypeDef",
     {
         "StackSummary": StackSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateLayerRequestRequestTypeDef = TypedDict(
     "_RequiredCreateLayerRequestRequestTypeDef",
     {
         "StackId": str,
@@ -2529,34 +2505,34 @@
     pass
 
 
 DescribeOperatingSystemsResponseTypeDef = TypedDict(
     "DescribeOperatingSystemsResponseTypeDef",
     {
         "OperatingSystems": List[OperatingSystemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeTimeBasedAutoScalingResultTypeDef = TypedDict(
     "DescribeTimeBasedAutoScalingResultTypeDef",
     {
         "TimeBasedAutoScalingConfigurations": List[TimeBasedAutoScalingConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeInstancesResultTypeDef = TypedDict(
     "DescribeInstancesResultTypeDef",
     {
         "Instances": List[InstanceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeLayersResultTypeDef = TypedDict(
     "DescribeLayersResultTypeDef",
     {
         "Layers": List[LayerTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-opsworks-2.5.0.post1/types_aiobotocore_opsworks/type_defs.pyi` & `types-aiobotocore-opsworks-2.5.1/types_aiobotocore_opsworks/type_defs.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -48,37 +48,44 @@
     "SslConfigurationTypeDef",
     "AssignInstanceRequestRequestTypeDef",
     "AssignVolumeRequestRequestTypeDef",
     "AssociateElasticIpRequestRequestTypeDef",
     "AttachElasticLoadBalancerRequestRequestTypeDef",
     "AutoScalingThresholdsTypeDef",
     "EbsBlockDeviceTypeDef",
-    "ResponseMetadataTypeDef",
+    "ChefConfigurationResponseMetadataTypeDef",
     "ChefConfigurationTypeDef",
+    "CloneStackResultTypeDef",
     "CloudWatchLogsLogStreamTypeDef",
     "CommandTypeDef",
+    "CreateAppResultTypeDef",
     "DeploymentCommandTypeDef",
+    "CreateDeploymentResultTypeDef",
+    "CreateInstanceResultTypeDef",
     "RecipesTypeDef",
     "VolumeConfigurationTypeDef",
+    "CreateLayerResultTypeDef",
+    "CreateStackResultTypeDef",
     "CreateUserProfileRequestRequestTypeDef",
+    "CreateUserProfileResultTypeDef",
     "DeleteAppRequestRequestTypeDef",
     "DeleteInstanceRequestRequestTypeDef",
     "DeleteLayerRequestRequestTypeDef",
     "DeleteStackRequestRequestTypeDef",
     "DeleteUserProfileRequestRequestTypeDef",
     "DeregisterEcsClusterRequestRequestTypeDef",
     "DeregisterElasticIpRequestRequestTypeDef",
     "DeregisterInstanceRequestRequestTypeDef",
     "DeregisterRdsDbInstanceRequestRequestTypeDef",
     "DeregisterVolumeRequestRequestTypeDef",
     "WaiterConfigTypeDef",
     "DescribeAppsRequestRequestTypeDef",
     "DescribeCommandsRequestRequestTypeDef",
     "DescribeDeploymentsRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeEcsClustersRequestDescribeEcsClustersPaginateTypeDef",
     "DescribeEcsClustersRequestRequestTypeDef",
     "EcsClusterTypeDef",
     "DescribeElasticIpsRequestRequestTypeDef",
     "ElasticIpTypeDef",
     "DescribeElasticLoadBalancersRequestRequestTypeDef",
     "ElasticLoadBalancerTypeDef",
     "DescribeInstancesRequestRequestTypeDef",
@@ -90,42 +97,53 @@
     "DescribeRaidArraysRequestRequestTypeDef",
     "RaidArrayTypeDef",
     "DescribeRdsDbInstancesRequestRequestTypeDef",
     "RdsDbInstanceTypeDef",
     "DescribeServiceErrorsRequestRequestTypeDef",
     "ServiceErrorTypeDef",
     "DescribeStackProvisioningParametersRequestRequestTypeDef",
+    "DescribeStackProvisioningParametersResultTypeDef",
     "DescribeStackSummaryRequestRequestTypeDef",
     "DescribeStacksRequestRequestTypeDef",
     "DescribeTimeBasedAutoScalingRequestRequestTypeDef",
     "DescribeUserProfilesRequestRequestTypeDef",
     "UserProfileTypeDef",
     "DescribeVolumesRequestRequestTypeDef",
     "VolumeTypeDef",
     "DetachElasticLoadBalancerRequestRequestTypeDef",
     "DisassociateElasticIpRequestRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GetHostnameSuggestionRequestRequestTypeDef",
+    "GetHostnameSuggestionResultTypeDef",
     "GrantAccessRequestRequestTypeDef",
     "TemporaryCredentialTypeDef",
     "InstanceIdentityTypeDef",
     "ReportedOsTypeDef",
+    "InstancesCountResponseMetadataTypeDef",
     "InstancesCountTypeDef",
     "ShutdownEventConfigurationTypeDef",
     "ListTagsRequestRequestTypeDef",
+    "ListTagsResultTypeDef",
     "OperatingSystemConfigurationManagerTypeDef",
+    "PaginatorConfigTypeDef",
     "RebootInstanceRequestRequestTypeDef",
+    "RecipesResponseMetadataTypeDef",
     "RegisterEcsClusterRequestRequestTypeDef",
+    "RegisterEcsClusterResultTypeDef",
     "RegisterElasticIpRequestRequestTypeDef",
+    "RegisterElasticIpResultTypeDef",
+    "RegisterInstanceResultTypeDef",
     "RegisterRdsDbInstanceRequestRequestTypeDef",
     "RegisterVolumeRequestRequestTypeDef",
-    "ServiceResourceLayerRequestTypeDef",
-    "ServiceResourceStackRequestTypeDef",
-    "ServiceResourceStackSummaryRequestTypeDef",
+    "RegisterVolumeResultTypeDef",
+    "ResponseMetadataTypeDef",
     "SetPermissionRequestRequestTypeDef",
     "WeeklyAutoScalingScheduleTypeDef",
+    "SourceResponseMetadataTypeDef",
+    "StackConfigurationManagerResponseMetadataTypeDef",
     "StartInstanceRequestRequestTypeDef",
     "StartStackRequestRequestTypeDef",
     "StopInstanceRequestRequestTypeDef",
     "StopStackRequestRequestTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UnassignInstanceRequestRequestTypeDef",
     "UnassignVolumeRequestRequestTypeDef",
@@ -140,34 +158,14 @@
     "DescribeAgentVersionsRequestRequestTypeDef",
     "AppTypeDef",
     "CreateAppRequestRequestTypeDef",
     "UpdateAppRequestRequestTypeDef",
     "LoadBasedAutoScalingConfigurationTypeDef",
     "SetLoadBasedAutoScalingRequestRequestTypeDef",
     "BlockDeviceMappingTypeDef",
-    "ChefConfigurationResponseMetadataTypeDef",
-    "CloneStackResultTypeDef",
-    "CreateAppResultTypeDef",
-    "CreateDeploymentResultTypeDef",
-    "CreateInstanceResultTypeDef",
-    "CreateLayerResultTypeDef",
-    "CreateStackResultTypeDef",
-    "CreateUserProfileResultTypeDef",
-    "DescribeStackProvisioningParametersResultTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "GetHostnameSuggestionResultTypeDef",
-    "InstancesCountResponseMetadataTypeDef",
-    "ListTagsResultTypeDef",
-    "RecipesResponseMetadataTypeDef",
-    "RegisterEcsClusterResultTypeDef",
-    "RegisterElasticIpResultTypeDef",
-    "RegisterInstanceResultTypeDef",
-    "RegisterVolumeResultTypeDef",
-    "SourceResponseMetadataTypeDef",
-    "StackConfigurationManagerResponseMetadataTypeDef",
     "CloneStackRequestRequestTypeDef",
     "CreateStackRequestRequestTypeDef",
     "CreateStackRequestServiceResourceCreateStackTypeDef",
     "StackTypeDef",
     "UpdateStackRequestRequestTypeDef",
     "CloudWatchLogsConfigurationResponseMetadataTypeDef",
     "CloudWatchLogsConfigurationTypeDef",
@@ -176,15 +174,14 @@
     "DeploymentTypeDef",
     "DescribeAppsRequestAppExistsWaitTypeDef",
     "DescribeDeploymentsRequestDeploymentSuccessfulWaitTypeDef",
     "DescribeInstancesRequestInstanceOnlineWaitTypeDef",
     "DescribeInstancesRequestInstanceRegisteredWaitTypeDef",
     "DescribeInstancesRequestInstanceStoppedWaitTypeDef",
     "DescribeInstancesRequestInstanceTerminatedWaitTypeDef",
-    "DescribeEcsClustersRequestDescribeEcsClustersPaginateTypeDef",
     "DescribeEcsClustersResultTypeDef",
     "DescribeElasticIpsResultTypeDef",
     "DescribeElasticLoadBalancersResultTypeDef",
     "DescribeMyUserProfileResultTypeDef",
     "DescribePermissionsResultTypeDef",
     "DescribeRaidArraysResultTypeDef",
     "DescribeRdsDbInstancesResultTypeDef",
@@ -364,34 +361,40 @@
         "VolumeSize": int,
         "VolumeType": VolumeTypeType,
         "DeleteOnTermination": bool,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+ChefConfigurationResponseMetadataTypeDef = TypedDict(
+    "ChefConfigurationResponseMetadataTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ManageBerkshelf": bool,
+        "BerkshelfVersion": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ChefConfigurationTypeDef = TypedDict(
     "ChefConfigurationTypeDef",
     {
         "ManageBerkshelf": bool,
         "BerkshelfVersion": str,
     },
     total=False,
 )
 
+CloneStackResultTypeDef = TypedDict(
+    "CloneStackResultTypeDef",
+    {
+        "StackId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CloudWatchLogsLogStreamTypeDef = TypedDict(
     "CloudWatchLogsLogStreamTypeDef",
     {
         "LogGroupName": str,
         "DatetimeFormat": str,
         "TimeZone": CloudWatchLogsTimeZoneType,
         "File": str,
@@ -419,14 +422,22 @@
         "ExitCode": int,
         "LogUrl": str,
         "Type": str,
     },
     total=False,
 )
 
+CreateAppResultTypeDef = TypedDict(
+    "CreateAppResultTypeDef",
+    {
+        "AppId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeploymentCommandTypeDef = TypedDict(
     "_RequiredDeploymentCommandTypeDef",
     {
         "Name": DeploymentCommandNameType,
     },
 )
 _OptionalDeploymentCommandTypeDef = TypedDict(
@@ -438,14 +449,30 @@
 )
 
 class DeploymentCommandTypeDef(
     _RequiredDeploymentCommandTypeDef, _OptionalDeploymentCommandTypeDef
 ):
     pass
 
+CreateDeploymentResultTypeDef = TypedDict(
+    "CreateDeploymentResultTypeDef",
+    {
+        "DeploymentId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateInstanceResultTypeDef = TypedDict(
+    "CreateInstanceResultTypeDef",
+    {
+        "InstanceId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RecipesTypeDef = TypedDict(
     "RecipesTypeDef",
     {
         "Setup": Sequence[str],
         "Configure": Sequence[str],
         "Deploy": Sequence[str],
         "Undeploy": Sequence[str],
@@ -474,14 +501,30 @@
 )
 
 class VolumeConfigurationTypeDef(
     _RequiredVolumeConfigurationTypeDef, _OptionalVolumeConfigurationTypeDef
 ):
     pass
 
+CreateLayerResultTypeDef = TypedDict(
+    "CreateLayerResultTypeDef",
+    {
+        "LayerId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateStackResultTypeDef = TypedDict(
+    "CreateStackResultTypeDef",
+    {
+        "StackId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateUserProfileRequestRequestTypeDef = TypedDict(
     "_RequiredCreateUserProfileRequestRequestTypeDef",
     {
         "IamUserArn": str,
     },
 )
 _OptionalCreateUserProfileRequestRequestTypeDef = TypedDict(
@@ -495,14 +538,22 @@
 )
 
 class CreateUserProfileRequestRequestTypeDef(
     _RequiredCreateUserProfileRequestRequestTypeDef, _OptionalCreateUserProfileRequestRequestTypeDef
 ):
     pass
 
+CreateUserProfileResultTypeDef = TypedDict(
+    "CreateUserProfileResultTypeDef",
+    {
+        "IamUserArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteAppRequestRequestTypeDef = TypedDict(
     "DeleteAppRequestRequestTypeDef",
     {
         "AppId": str,
     },
 )
 
@@ -616,20 +667,20 @@
         "StackId": str,
         "AppId": str,
         "DeploymentIds": Sequence[str],
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeEcsClustersRequestDescribeEcsClustersPaginateTypeDef = TypedDict(
+    "DescribeEcsClustersRequestDescribeEcsClustersPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "EcsClusterArns": Sequence[str],
+        "StackId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeEcsClustersRequestRequestTypeDef = TypedDict(
     "DescribeEcsClustersRequestRequestTypeDef",
     {
@@ -849,14 +900,23 @@
 DescribeStackProvisioningParametersRequestRequestTypeDef = TypedDict(
     "DescribeStackProvisioningParametersRequestRequestTypeDef",
     {
         "StackId": str,
     },
 )
 
+DescribeStackProvisioningParametersResultTypeDef = TypedDict(
+    "DescribeStackProvisioningParametersResultTypeDef",
+    {
+        "AgentInstallerUrl": str,
+        "Parameters": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeStackSummaryRequestRequestTypeDef = TypedDict(
     "DescribeStackSummaryRequestRequestTypeDef",
     {
         "StackId": str,
     },
 )
 
@@ -938,21 +998,37 @@
 DisassociateElasticIpRequestRequestTypeDef = TypedDict(
     "DisassociateElasticIpRequestRequestTypeDef",
     {
         "ElasticIp": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetHostnameSuggestionRequestRequestTypeDef = TypedDict(
     "GetHostnameSuggestionRequestRequestTypeDef",
     {
         "LayerId": str,
     },
 )
 
+GetHostnameSuggestionResultTypeDef = TypedDict(
+    "GetHostnameSuggestionResultTypeDef",
+    {
+        "LayerId": str,
+        "Hostname": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredGrantAccessRequestRequestTypeDef = TypedDict(
     "_RequiredGrantAccessRequestRequestTypeDef",
     {
         "InstanceId": str,
     },
 )
 _OptionalGrantAccessRequestRequestTypeDef = TypedDict(
@@ -994,14 +1070,41 @@
         "Family": str,
         "Name": str,
         "Version": str,
     },
     total=False,
 )
 
+InstancesCountResponseMetadataTypeDef = TypedDict(
+    "InstancesCountResponseMetadataTypeDef",
+    {
+        "Assigning": int,
+        "Booting": int,
+        "ConnectionLost": int,
+        "Deregistering": int,
+        "Online": int,
+        "Pending": int,
+        "Rebooting": int,
+        "Registered": int,
+        "Registering": int,
+        "Requested": int,
+        "RunningSetup": int,
+        "SetupFailed": int,
+        "ShuttingDown": int,
+        "StartFailed": int,
+        "StopFailed": int,
+        "Stopped": int,
+        "Stopping": int,
+        "Terminated": int,
+        "Terminating": int,
+        "Unassigning": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 InstancesCountTypeDef = TypedDict(
     "InstancesCountTypeDef",
     {
         "Assigning": int,
         "Booting": int,
         "ConnectionLost": int,
         "Deregistering": int,
@@ -1050,46 +1153,101 @@
 )
 
 class ListTagsRequestRequestTypeDef(
     _RequiredListTagsRequestRequestTypeDef, _OptionalListTagsRequestRequestTypeDef
 ):
     pass
 
+ListTagsResultTypeDef = TypedDict(
+    "ListTagsResultTypeDef",
+    {
+        "Tags": Dict[str, str],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 OperatingSystemConfigurationManagerTypeDef = TypedDict(
     "OperatingSystemConfigurationManagerTypeDef",
     {
         "Name": str,
         "Version": str,
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
 RebootInstanceRequestRequestTypeDef = TypedDict(
     "RebootInstanceRequestRequestTypeDef",
     {
         "InstanceId": str,
     },
 )
 
+RecipesResponseMetadataTypeDef = TypedDict(
+    "RecipesResponseMetadataTypeDef",
+    {
+        "Setup": List[str],
+        "Configure": List[str],
+        "Deploy": List[str],
+        "Undeploy": List[str],
+        "Shutdown": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RegisterEcsClusterRequestRequestTypeDef = TypedDict(
     "RegisterEcsClusterRequestRequestTypeDef",
     {
         "EcsClusterArn": str,
         "StackId": str,
     },
 )
 
+RegisterEcsClusterResultTypeDef = TypedDict(
+    "RegisterEcsClusterResultTypeDef",
+    {
+        "EcsClusterArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RegisterElasticIpRequestRequestTypeDef = TypedDict(
     "RegisterElasticIpRequestRequestTypeDef",
     {
         "ElasticIp": str,
         "StackId": str,
     },
 )
 
+RegisterElasticIpResultTypeDef = TypedDict(
+    "RegisterElasticIpResultTypeDef",
+    {
+        "ElasticIp": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+RegisterInstanceResultTypeDef = TypedDict(
+    "RegisterInstanceResultTypeDef",
+    {
+        "InstanceId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RegisterRdsDbInstanceRequestRequestTypeDef = TypedDict(
     "RegisterRdsDbInstanceRequestRequestTypeDef",
     {
         "StackId": str,
         "RdsDbInstanceArn": str,
         "DbUser": str,
         "DbPassword": str,
@@ -1111,32 +1269,30 @@
 )
 
 class RegisterVolumeRequestRequestTypeDef(
     _RequiredRegisterVolumeRequestRequestTypeDef, _OptionalRegisterVolumeRequestRequestTypeDef
 ):
     pass
 
-ServiceResourceLayerRequestTypeDef = TypedDict(
-    "ServiceResourceLayerRequestTypeDef",
-    {
-        "id": str,
-    },
-)
-
-ServiceResourceStackRequestTypeDef = TypedDict(
-    "ServiceResourceStackRequestTypeDef",
+RegisterVolumeResultTypeDef = TypedDict(
+    "RegisterVolumeResultTypeDef",
     {
-        "id": str,
+        "VolumeId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ServiceResourceStackSummaryRequestTypeDef = TypedDict(
-    "ServiceResourceStackSummaryRequestTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "stack_id": str,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
 _RequiredSetPermissionRequestRequestTypeDef = TypedDict(
     "_RequiredSetPermissionRequestRequestTypeDef",
     {
         "StackId": str,
@@ -1168,14 +1324,36 @@
         "Friday": Dict[str, str],
         "Saturday": Dict[str, str],
         "Sunday": Dict[str, str],
     },
     total=False,
 )
 
+SourceResponseMetadataTypeDef = TypedDict(
+    "SourceResponseMetadataTypeDef",
+    {
+        "Type": SourceTypeType,
+        "Url": str,
+        "Username": str,
+        "Password": str,
+        "SshKey": str,
+        "Revision": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+StackConfigurationManagerResponseMetadataTypeDef = TypedDict(
+    "StackConfigurationManagerResponseMetadataTypeDef",
+    {
+        "Name": str,
+        "Version": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 StartInstanceRequestRequestTypeDef = TypedDict(
     "StartInstanceRequestRequestTypeDef",
     {
         "InstanceId": str,
     },
 )
 
@@ -1496,206 +1674,14 @@
         "NoDevice": str,
         "VirtualName": str,
         "Ebs": EbsBlockDeviceTypeDef,
     },
     total=False,
 )
 
-ChefConfigurationResponseMetadataTypeDef = TypedDict(
-    "ChefConfigurationResponseMetadataTypeDef",
-    {
-        "ManageBerkshelf": bool,
-        "BerkshelfVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CloneStackResultTypeDef = TypedDict(
-    "CloneStackResultTypeDef",
-    {
-        "StackId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateAppResultTypeDef = TypedDict(
-    "CreateAppResultTypeDef",
-    {
-        "AppId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDeploymentResultTypeDef = TypedDict(
-    "CreateDeploymentResultTypeDef",
-    {
-        "DeploymentId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateInstanceResultTypeDef = TypedDict(
-    "CreateInstanceResultTypeDef",
-    {
-        "InstanceId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateLayerResultTypeDef = TypedDict(
-    "CreateLayerResultTypeDef",
-    {
-        "LayerId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateStackResultTypeDef = TypedDict(
-    "CreateStackResultTypeDef",
-    {
-        "StackId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateUserProfileResultTypeDef = TypedDict(
-    "CreateUserProfileResultTypeDef",
-    {
-        "IamUserArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeStackProvisioningParametersResultTypeDef = TypedDict(
-    "DescribeStackProvisioningParametersResultTypeDef",
-    {
-        "AgentInstallerUrl": str,
-        "Parameters": Dict[str, str],
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
-GetHostnameSuggestionResultTypeDef = TypedDict(
-    "GetHostnameSuggestionResultTypeDef",
-    {
-        "LayerId": str,
-        "Hostname": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-InstancesCountResponseMetadataTypeDef = TypedDict(
-    "InstancesCountResponseMetadataTypeDef",
-    {
-        "Assigning": int,
-        "Booting": int,
-        "ConnectionLost": int,
-        "Deregistering": int,
-        "Online": int,
-        "Pending": int,
-        "Rebooting": int,
-        "Registered": int,
-        "Registering": int,
-        "Requested": int,
-        "RunningSetup": int,
-        "SetupFailed": int,
-        "ShuttingDown": int,
-        "StartFailed": int,
-        "StopFailed": int,
-        "Stopped": int,
-        "Stopping": int,
-        "Terminated": int,
-        "Terminating": int,
-        "Unassigning": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsResultTypeDef = TypedDict(
-    "ListTagsResultTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RecipesResponseMetadataTypeDef = TypedDict(
-    "RecipesResponseMetadataTypeDef",
-    {
-        "Setup": List[str],
-        "Configure": List[str],
-        "Deploy": List[str],
-        "Undeploy": List[str],
-        "Shutdown": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RegisterEcsClusterResultTypeDef = TypedDict(
-    "RegisterEcsClusterResultTypeDef",
-    {
-        "EcsClusterArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RegisterElasticIpResultTypeDef = TypedDict(
-    "RegisterElasticIpResultTypeDef",
-    {
-        "ElasticIp": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RegisterInstanceResultTypeDef = TypedDict(
-    "RegisterInstanceResultTypeDef",
-    {
-        "InstanceId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RegisterVolumeResultTypeDef = TypedDict(
-    "RegisterVolumeResultTypeDef",
-    {
-        "VolumeId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SourceResponseMetadataTypeDef = TypedDict(
-    "SourceResponseMetadataTypeDef",
-    {
-        "Type": SourceTypeType,
-        "Url": str,
-        "Username": str,
-        "Password": str,
-        "SshKey": str,
-        "Revision": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StackConfigurationManagerResponseMetadataTypeDef = TypedDict(
-    "StackConfigurationManagerResponseMetadataTypeDef",
-    {
-        "Name": str,
-        "Version": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 _RequiredCloneStackRequestRequestTypeDef = TypedDict(
     "_RequiredCloneStackRequestRequestTypeDef",
     {
         "SourceStackId": str,
         "ServiceRoleArn": str,
     },
 )
@@ -1869,15 +1855,15 @@
     pass
 
 CloudWatchLogsConfigurationResponseMetadataTypeDef = TypedDict(
     "CloudWatchLogsConfigurationResponseMetadataTypeDef",
     {
         "Enabled": bool,
         "LogStreams": List[CloudWatchLogsLogStreamTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CloudWatchLogsConfigurationTypeDef = TypedDict(
     "CloudWatchLogsConfigurationTypeDef",
     {
         "Enabled": bool,
@@ -1886,15 +1872,15 @@
     total=False,
 )
 
 DescribeCommandsResultTypeDef = TypedDict(
     "DescribeCommandsResultTypeDef",
     {
         "Commands": List[CommandTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateDeploymentRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDeploymentRequestRequestTypeDef",
     {
         "StackId": str,
@@ -1998,110 +1984,100 @@
         "LayerId": str,
         "InstanceIds": Sequence[str],
         "WaiterConfig": WaiterConfigTypeDef,
     },
     total=False,
 )
 
-DescribeEcsClustersRequestDescribeEcsClustersPaginateTypeDef = TypedDict(
-    "DescribeEcsClustersRequestDescribeEcsClustersPaginateTypeDef",
-    {
-        "EcsClusterArns": Sequence[str],
-        "StackId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 DescribeEcsClustersResultTypeDef = TypedDict(
     "DescribeEcsClustersResultTypeDef",
     {
         "EcsClusters": List[EcsClusterTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeElasticIpsResultTypeDef = TypedDict(
     "DescribeElasticIpsResultTypeDef",
     {
         "ElasticIps": List[ElasticIpTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeElasticLoadBalancersResultTypeDef = TypedDict(
     "DescribeElasticLoadBalancersResultTypeDef",
     {
         "ElasticLoadBalancers": List[ElasticLoadBalancerTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeMyUserProfileResultTypeDef = TypedDict(
     "DescribeMyUserProfileResultTypeDef",
     {
         "UserProfile": SelfUserProfileTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribePermissionsResultTypeDef = TypedDict(
     "DescribePermissionsResultTypeDef",
     {
         "Permissions": List[PermissionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeRaidArraysResultTypeDef = TypedDict(
     "DescribeRaidArraysResultTypeDef",
     {
         "RaidArrays": List[RaidArrayTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeRdsDbInstancesResultTypeDef = TypedDict(
     "DescribeRdsDbInstancesResultTypeDef",
     {
         "RdsDbInstances": List[RdsDbInstanceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeServiceErrorsResultTypeDef = TypedDict(
     "DescribeServiceErrorsResultTypeDef",
     {
         "ServiceErrors": List[ServiceErrorTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeUserProfilesResultTypeDef = TypedDict(
     "DescribeUserProfilesResultTypeDef",
     {
         "UserProfiles": List[UserProfileTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeVolumesResultTypeDef = TypedDict(
     "DescribeVolumesResultTypeDef",
     {
         "Volumes": List[VolumeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GrantAccessResultTypeDef = TypedDict(
     "GrantAccessResultTypeDef",
     {
         "TemporaryCredential": TemporaryCredentialTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredRegisterInstanceRequestRequestTypeDef = TypedDict(
     "_RequiredRegisterInstanceRequestRequestTypeDef",
     {
         "StackId": str,
@@ -2138,15 +2114,15 @@
     total=False,
 )
 
 LifecycleEventConfigurationResponseMetadataTypeDef = TypedDict(
     "LifecycleEventConfigurationResponseMetadataTypeDef",
     {
         "Shutdown": ShutdownEventConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LifecycleEventConfigurationTypeDef = TypedDict(
     "LifecycleEventConfigurationTypeDef",
     {
         "Shutdown": ShutdownEventConfigurationTypeDef,
@@ -2197,31 +2173,31 @@
     total=False,
 )
 
 DescribeAgentVersionsResultTypeDef = TypedDict(
     "DescribeAgentVersionsResultTypeDef",
     {
         "AgentVersions": List[AgentVersionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAppsResultTypeDef = TypedDict(
     "DescribeAppsResultTypeDef",
     {
         "Apps": List[AppTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeLoadBasedAutoScalingResultTypeDef = TypedDict(
     "DescribeLoadBasedAutoScalingResultTypeDef",
     {
         "LoadBasedAutoScalingConfigurations": List[LoadBasedAutoScalingConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateInstanceRequestRequestTypeDef = TypedDict(
     "_RequiredCreateInstanceRequestRequestTypeDef",
     {
         "StackId": str,
@@ -2304,31 +2280,31 @@
     total=False,
 )
 
 DescribeStacksResultTypeDef = TypedDict(
     "DescribeStacksResultTypeDef",
     {
         "Stacks": List[StackTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDeploymentsResultTypeDef = TypedDict(
     "DescribeDeploymentsResultTypeDef",
     {
         "Deployments": List[DeploymentTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeStackSummaryResultTypeDef = TypedDict(
     "DescribeStackSummaryResultTypeDef",
     {
         "StackSummary": StackSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateLayerRequestRequestTypeDef = TypedDict(
     "_RequiredCreateLayerRequestRequestTypeDef",
     {
         "StackId": str,
@@ -2462,34 +2438,34 @@
 ):
     pass
 
 DescribeOperatingSystemsResponseTypeDef = TypedDict(
     "DescribeOperatingSystemsResponseTypeDef",
     {
         "OperatingSystems": List[OperatingSystemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeTimeBasedAutoScalingResultTypeDef = TypedDict(
     "DescribeTimeBasedAutoScalingResultTypeDef",
     {
         "TimeBasedAutoScalingConfigurations": List[TimeBasedAutoScalingConfigurationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeInstancesResultTypeDef = TypedDict(
     "DescribeInstancesResultTypeDef",
     {
         "Instances": List[InstanceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeLayersResultTypeDef = TypedDict(
     "DescribeLayersResultTypeDef",
     {
         "Layers": List[LayerTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-opsworks-2.5.0.post1/types_aiobotocore_opsworks/waiter.py` & `types-aiobotocore-opsworks-2.5.1/types_aiobotocore_opsworks/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-opsworks-2.5.0.post1/types_aiobotocore_opsworks/waiter.pyi` & `types-aiobotocore-opsworks-2.5.1/types_aiobotocore_opsworks/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-opsworks-2.5.0.post1/types_aiobotocore_opsworks.egg-info/PKG-INFO` & `types-aiobotocore-opsworks-2.5.1/types_aiobotocore_opsworks.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-opsworks
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.OpsWorks 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.OpsWorks 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworks/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-opsworks"></a>
 
 # types-aiobotocore-opsworks
 
 [![PyPI - types-aiobotocore-opsworks](https://img.shields.io/pypi/v/types-aiobotocore-opsworks.svg?color=blue)](https://pypi.org/project/types-aiobotocore-opsworks)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-opsworks.svg?color=blue)](https://pypi.org/project/types-aiobotocore-opsworks)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworks/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-opsworks?color=blue)](https://pypistats.org/packages/types-aiobotocore-opsworks)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.OpsWorks 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks)
+[aiobotocore.OpsWorks 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/opsworks.html#OpsWorks)
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
 [types-aiobotocore-opsworks docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworks/).
 
 See how it helps to find and fix potential bugs:
 
@@ -452,37 +452,44 @@
     SslConfigurationTypeDef,
     AssignInstanceRequestRequestTypeDef,
     AssignVolumeRequestRequestTypeDef,
     AssociateElasticIpRequestRequestTypeDef,
     AttachElasticLoadBalancerRequestRequestTypeDef,
     AutoScalingThresholdsTypeDef,
     EbsBlockDeviceTypeDef,
-    ResponseMetadataTypeDef,
+    ChefConfigurationResponseMetadataTypeDef,
     ChefConfigurationTypeDef,
+    CloneStackResultTypeDef,
     CloudWatchLogsLogStreamTypeDef,
     CommandTypeDef,
+    CreateAppResultTypeDef,
     DeploymentCommandTypeDef,
+    CreateDeploymentResultTypeDef,
+    CreateInstanceResultTypeDef,
     RecipesTypeDef,
     VolumeConfigurationTypeDef,
+    CreateLayerResultTypeDef,
+    CreateStackResultTypeDef,
     CreateUserProfileRequestRequestTypeDef,
+    CreateUserProfileResultTypeDef,
     DeleteAppRequestRequestTypeDef,
     DeleteInstanceRequestRequestTypeDef,
     DeleteLayerRequestRequestTypeDef,
     DeleteStackRequestRequestTypeDef,
     DeleteUserProfileRequestRequestTypeDef,
     DeregisterEcsClusterRequestRequestTypeDef,
     DeregisterElasticIpRequestRequestTypeDef,
     DeregisterInstanceRequestRequestTypeDef,
     DeregisterRdsDbInstanceRequestRequestTypeDef,
     DeregisterVolumeRequestRequestTypeDef,
     WaiterConfigTypeDef,
     DescribeAppsRequestRequestTypeDef,
     DescribeCommandsRequestRequestTypeDef,
     DescribeDeploymentsRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeEcsClustersRequestDescribeEcsClustersPaginateTypeDef,
     DescribeEcsClustersRequestRequestTypeDef,
     EcsClusterTypeDef,
     DescribeElasticIpsRequestRequestTypeDef,
     ElasticIpTypeDef,
     DescribeElasticLoadBalancersRequestRequestTypeDef,
     ElasticLoadBalancerTypeDef,
     DescribeInstancesRequestRequestTypeDef,
@@ -494,42 +501,53 @@
     DescribeRaidArraysRequestRequestTypeDef,
     RaidArrayTypeDef,
     DescribeRdsDbInstancesRequestRequestTypeDef,
     RdsDbInstanceTypeDef,
     DescribeServiceErrorsRequestRequestTypeDef,
     ServiceErrorTypeDef,
     DescribeStackProvisioningParametersRequestRequestTypeDef,
+    DescribeStackProvisioningParametersResultTypeDef,
     DescribeStackSummaryRequestRequestTypeDef,
     DescribeStacksRequestRequestTypeDef,
     DescribeTimeBasedAutoScalingRequestRequestTypeDef,
     DescribeUserProfilesRequestRequestTypeDef,
     UserProfileTypeDef,
     DescribeVolumesRequestRequestTypeDef,
     VolumeTypeDef,
     DetachElasticLoadBalancerRequestRequestTypeDef,
     DisassociateElasticIpRequestRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     GetHostnameSuggestionRequestRequestTypeDef,
+    GetHostnameSuggestionResultTypeDef,
     GrantAccessRequestRequestTypeDef,
     TemporaryCredentialTypeDef,
     InstanceIdentityTypeDef,
     ReportedOsTypeDef,
+    InstancesCountResponseMetadataTypeDef,
     InstancesCountTypeDef,
     ShutdownEventConfigurationTypeDef,
     ListTagsRequestRequestTypeDef,
+    ListTagsResultTypeDef,
     OperatingSystemConfigurationManagerTypeDef,
+    PaginatorConfigTypeDef,
     RebootInstanceRequestRequestTypeDef,
+    RecipesResponseMetadataTypeDef,
     RegisterEcsClusterRequestRequestTypeDef,
+    RegisterEcsClusterResultTypeDef,
     RegisterElasticIpRequestRequestTypeDef,
+    RegisterElasticIpResultTypeDef,
+    RegisterInstanceResultTypeDef,
     RegisterRdsDbInstanceRequestRequestTypeDef,
     RegisterVolumeRequestRequestTypeDef,
-    ServiceResourceLayerRequestTypeDef,
-    ServiceResourceStackRequestTypeDef,
-    ServiceResourceStackSummaryRequestTypeDef,
+    RegisterVolumeResultTypeDef,
+    ResponseMetadataTypeDef,
     SetPermissionRequestRequestTypeDef,
     WeeklyAutoScalingScheduleTypeDef,
+    SourceResponseMetadataTypeDef,
+    StackConfigurationManagerResponseMetadataTypeDef,
     StartInstanceRequestRequestTypeDef,
     StartStackRequestRequestTypeDef,
     StopInstanceRequestRequestTypeDef,
     StopStackRequestRequestTypeDef,
     TagResourceRequestRequestTypeDef,
     UnassignInstanceRequestRequestTypeDef,
     UnassignVolumeRequestRequestTypeDef,
@@ -544,34 +562,14 @@
     DescribeAgentVersionsRequestRequestTypeDef,
     AppTypeDef,
     CreateAppRequestRequestTypeDef,
     UpdateAppRequestRequestTypeDef,
     LoadBasedAutoScalingConfigurationTypeDef,
     SetLoadBasedAutoScalingRequestRequestTypeDef,
     BlockDeviceMappingTypeDef,
-    ChefConfigurationResponseMetadataTypeDef,
-    CloneStackResultTypeDef,
-    CreateAppResultTypeDef,
-    CreateDeploymentResultTypeDef,
-    CreateInstanceResultTypeDef,
-    CreateLayerResultTypeDef,
-    CreateStackResultTypeDef,
-    CreateUserProfileResultTypeDef,
-    DescribeStackProvisioningParametersResultTypeDef,
-    EmptyResponseMetadataTypeDef,
-    GetHostnameSuggestionResultTypeDef,
-    InstancesCountResponseMetadataTypeDef,
-    ListTagsResultTypeDef,
-    RecipesResponseMetadataTypeDef,
-    RegisterEcsClusterResultTypeDef,
-    RegisterElasticIpResultTypeDef,
-    RegisterInstanceResultTypeDef,
-    RegisterVolumeResultTypeDef,
-    SourceResponseMetadataTypeDef,
-    StackConfigurationManagerResponseMetadataTypeDef,
     CloneStackRequestRequestTypeDef,
     CreateStackRequestRequestTypeDef,
     CreateStackRequestServiceResourceCreateStackTypeDef,
     StackTypeDef,
     UpdateStackRequestRequestTypeDef,
     CloudWatchLogsConfigurationResponseMetadataTypeDef,
     CloudWatchLogsConfigurationTypeDef,
@@ -580,15 +578,14 @@
     DeploymentTypeDef,
     DescribeAppsRequestAppExistsWaitTypeDef,
     DescribeDeploymentsRequestDeploymentSuccessfulWaitTypeDef,
     DescribeInstancesRequestInstanceOnlineWaitTypeDef,
     DescribeInstancesRequestInstanceRegisteredWaitTypeDef,
     DescribeInstancesRequestInstanceStoppedWaitTypeDef,
     DescribeInstancesRequestInstanceTerminatedWaitTypeDef,
-    DescribeEcsClustersRequestDescribeEcsClustersPaginateTypeDef,
     DescribeEcsClustersResultTypeDef,
     DescribeElasticIpsResultTypeDef,
     DescribeElasticLoadBalancersResultTypeDef,
     DescribeMyUserProfileResultTypeDef,
     DescribePermissionsResultTypeDef,
     DescribeRaidArraysResultTypeDef,
     DescribeRdsDbInstancesResultTypeDef,
@@ -629,43 +626,43 @@
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

### Comparing `types-aiobotocore-opsworks-2.5.0.post1/types_aiobotocore_opsworks.egg-info/SOURCES.txt` & `types-aiobotocore-opsworks-2.5.1/types_aiobotocore_opsworks.egg-info/SOURCES.txt`

 * *Files identical despite different names*

