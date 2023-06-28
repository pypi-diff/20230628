# Comparing `tmp/types-aiobotocore-ecs-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-ecs-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-ecs-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:34 2023, max compression
+gzip compressed data, was "types-aiobotocore-ecs-2.5.1.tar", last modified: Wed Jun 28 01:43:26 2023, max compression
```

## Comparing `types-aiobotocore-ecs-2.5.0.post1.tar` & `types-aiobotocore-ecs-2.5.1.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:34.383172 types-aiobotocore-ecs-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:13:51.000000 types-aiobotocore-ecs-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    24846 2023-03-11 12:26:34.379172 types-aiobotocore-ecs-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    23291 2023-03-11 12:13:51.000000 types-aiobotocore-ecs-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:34.383172 types-aiobotocore-ecs-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2072 2023-03-11 12:13:51.000000 types-aiobotocore-ecs-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:34.371172 types-aiobotocore-ecs-2.5.0.post1/types_aiobotocore_ecs/
--rw-r--r--   0 runner    (1001) docker     (123)     3054 2023-03-11 12:13:51.000000 types-aiobotocore-ecs-2.5.0.post1/types_aiobotocore_ecs/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3053 2023-03-11 12:13:51.000000 types-aiobotocore-ecs-2.5.0.post1/types_aiobotocore_ecs/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      916 2023-03-11 12:13:51.000000 types-aiobotocore-ecs-2.5.0.post1/types_aiobotocore_ecs/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    52014 2023-03-11 12:13:51.000000 types-aiobotocore-ecs-2.5.0.post1/types_aiobotocore_ecs/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    51937 2023-03-11 12:13:51.000000 types-aiobotocore-ecs-2.5.0.post1/types_aiobotocore_ecs/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    15401 2023-03-11 12:13:52.000000 types-aiobotocore-ecs-2.5.0.post1/types_aiobotocore_ecs/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    15399 2023-03-11 12:13:51.000000 types-aiobotocore-ecs-2.5.0.post1/types_aiobotocore_ecs/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    12151 2023-03-11 12:13:51.000000 types-aiobotocore-ecs-2.5.0.post1/types_aiobotocore_ecs/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    12139 2023-03-11 12:13:51.000000 types-aiobotocore-ecs-2.5.0.post1/types_aiobotocore_ecs/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:13:51.000000 types-aiobotocore-ecs-2.5.0.post1/types_aiobotocore_ecs/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    84917 2023-03-11 12:13:54.000000 types-aiobotocore-ecs-2.5.0.post1/types_aiobotocore_ecs/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    84816 2023-03-11 12:13:54.000000 types-aiobotocore-ecs-2.5.0.post1/types_aiobotocore_ecs/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:13:51.000000 types-aiobotocore-ecs-2.5.0.post1/types_aiobotocore_ecs/version.py
--rw-r--r--   0 runner    (1001) docker     (123)     4838 2023-03-11 12:13:51.000000 types-aiobotocore-ecs-2.5.0.post1/types_aiobotocore_ecs/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)     4833 2023-03-11 12:13:51.000000 types-aiobotocore-ecs-2.5.0.post1/types_aiobotocore_ecs/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:34.379172 types-aiobotocore-ecs-2.5.0.post1/types_aiobotocore_ecs.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    24846 2023-03-11 12:26:34.000000 types-aiobotocore-ecs-2.5.0.post1/types_aiobotocore_ecs.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      802 2023-03-11 12:26:34.000000 types-aiobotocore-ecs-2.5.0.post1/types_aiobotocore_ecs.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:34.000000 types-aiobotocore-ecs-2.5.0.post1/types_aiobotocore_ecs.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:34.000000 types-aiobotocore-ecs-2.5.0.post1/types_aiobotocore_ecs.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:34.000000 types-aiobotocore-ecs-2.5.0.post1/types_aiobotocore_ecs.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-03-11 12:26:34.000000 types-aiobotocore-ecs-2.5.0.post1/types_aiobotocore_ecs.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:26.898131 types-aiobotocore-ecs-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:30:28.000000 types-aiobotocore-ecs-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    24924 2023-06-28 01:43:26.898131 types-aiobotocore-ecs-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    23375 2023-06-28 01:30:28.000000 types-aiobotocore-ecs-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:26.898131 types-aiobotocore-ecs-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2066 2023-06-28 01:30:28.000000 types-aiobotocore-ecs-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:26.898131 types-aiobotocore-ecs-2.5.1/types_aiobotocore_ecs/
+-rw-r--r--   0 runner    (1001) docker     (123)     3054 2023-06-28 01:30:28.000000 types-aiobotocore-ecs-2.5.1/types_aiobotocore_ecs/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3053 2023-06-28 01:30:28.000000 types-aiobotocore-ecs-2.5.1/types_aiobotocore_ecs/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      904 2023-06-28 01:30:28.000000 types-aiobotocore-ecs-2.5.1/types_aiobotocore_ecs/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    52556 2023-06-28 01:30:28.000000 types-aiobotocore-ecs-2.5.1/types_aiobotocore_ecs/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    52478 2023-06-28 01:30:28.000000 types-aiobotocore-ecs-2.5.1/types_aiobotocore_ecs/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    15687 2023-06-28 01:30:30.000000 types-aiobotocore-ecs-2.5.1/types_aiobotocore_ecs/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15685 2023-06-28 01:30:28.000000 types-aiobotocore-ecs-2.5.1/types_aiobotocore_ecs/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    12062 2023-06-28 01:30:28.000000 types-aiobotocore-ecs-2.5.1/types_aiobotocore_ecs/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12050 2023-06-28 01:30:28.000000 types-aiobotocore-ecs-2.5.1/types_aiobotocore_ecs/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:30:28.000000 types-aiobotocore-ecs-2.5.1/types_aiobotocore_ecs/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    85562 2023-06-28 01:30:31.000000 types-aiobotocore-ecs-2.5.1/types_aiobotocore_ecs/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    85461 2023-06-28 01:30:30.000000 types-aiobotocore-ecs-2.5.1/types_aiobotocore_ecs/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:30:28.000000 types-aiobotocore-ecs-2.5.1/types_aiobotocore_ecs/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4838 2023-06-28 01:30:28.000000 types-aiobotocore-ecs-2.5.1/types_aiobotocore_ecs/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4833 2023-06-28 01:30:28.000000 types-aiobotocore-ecs-2.5.1/types_aiobotocore_ecs/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:26.898131 types-aiobotocore-ecs-2.5.1/types_aiobotocore_ecs.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    24924 2023-06-28 01:43:26.000000 types-aiobotocore-ecs-2.5.1/types_aiobotocore_ecs.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      802 2023-06-28 01:43:26.000000 types-aiobotocore-ecs-2.5.1/types_aiobotocore_ecs.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:26.000000 types-aiobotocore-ecs-2.5.1/types_aiobotocore_ecs.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:26.000000 types-aiobotocore-ecs-2.5.1/types_aiobotocore_ecs.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:26.000000 types-aiobotocore-ecs-2.5.1/types_aiobotocore_ecs.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 01:43:26.000000 types-aiobotocore-ecs-2.5.1/types_aiobotocore_ecs.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-ecs-2.5.0.post1/LICENSE` & `types-aiobotocore-ecs-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-ecs-2.5.0.post1/PKG-INFO` & `types-aiobotocore-ecs-2.5.1/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-ecs
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ECS 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ECS 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-ecs"></a>
 
 # types-aiobotocore-ecs
 
 [![PyPI - types-aiobotocore-ecs](https://img.shields.io/pypi/v/types-aiobotocore-ecs.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ecs)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-ecs.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ecs)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-ecs?color=blue)](https://pypistats.org/packages/types-aiobotocore-ecs)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ECS 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS)
+[aiobotocore.ECS 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS)
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
 [types-aiobotocore-ecs docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs/).
 
 See how it helps to find and fix potential bugs:
 
@@ -471,114 +471,124 @@
     VolumeFromTypeDef,
     InstanceHealthCheckResultTypeDef,
     ResourceTypeDef,
     VersionInfoTypeDef,
     NetworkBindingTypeDef,
     ManagedAgentTypeDef,
     NetworkInterfaceTypeDef,
-    ResponseMetadataTypeDef,
     DeploymentControllerTypeDef,
     LoadBalancerTypeDef,
     PlacementConstraintTypeDef,
     PlacementStrategyTypeDef,
     ServiceRegistryTypeDef,
     ScaleTypeDef,
     DeleteAccountSettingRequestRequestTypeDef,
     SettingTypeDef,
     DeleteCapacityProviderRequestRequestTypeDef,
     DeleteClusterRequestRequestTypeDef,
     DeleteServiceRequestRequestTypeDef,
+    DeleteTaskDefinitionsRequestRequestTypeDef,
+    FailureTypeDef,
     DeleteTaskSetRequestRequestTypeDef,
     DeploymentAlarmsTypeDef,
     DeploymentCircuitBreakerTypeDef,
     ServiceConnectServiceResourceTypeDef,
     DeregisterContainerInstanceRequestRequestTypeDef,
     DeregisterTaskDefinitionRequestRequestTypeDef,
     DescribeCapacityProvidersRequestRequestTypeDef,
-    FailureTypeDef,
     DescribeClustersRequestRequestTypeDef,
     DescribeContainerInstancesRequestRequestTypeDef,
     DescribeServicesRequestRequestTypeDef,
     WaiterConfigTypeDef,
     DescribeTaskDefinitionRequestRequestTypeDef,
     DescribeTaskSetsRequestRequestTypeDef,
     DescribeTasksRequestRequestTypeDef,
     DeviceTypeDef,
     DiscoverPollEndpointRequestRequestTypeDef,
+    DiscoverPollEndpointResponseTypeDef,
     DockerVolumeConfigurationTypeDef,
     EFSAuthorizationConfigTypeDef,
     EphemeralStorageTypeDef,
     ExecuteCommandLogConfigurationTypeDef,
     ExecuteCommandRequestRequestTypeDef,
     SessionTypeDef,
     FSxWindowsFileServerAuthorizationConfigTypeDef,
     GetTaskProtectionRequestRequestTypeDef,
     ProtectedTaskTypeDef,
     HostVolumePropertiesTypeDef,
     InferenceAcceleratorOverrideTypeDef,
     InferenceAcceleratorTypeDef,
     KernelCapabilitiesTypeDef,
     TmpfsTypeDef,
-    PaginatorConfigTypeDef,
+    ListAccountSettingsRequestListAccountSettingsPaginateTypeDef,
     ListAccountSettingsRequestRequestTypeDef,
+    ListAttributesRequestListAttributesPaginateTypeDef,
     ListAttributesRequestRequestTypeDef,
+    ListClustersRequestListClustersPaginateTypeDef,
     ListClustersRequestRequestTypeDef,
+    ListClustersResponseTypeDef,
+    ListContainerInstancesRequestListContainerInstancesPaginateTypeDef,
     ListContainerInstancesRequestRequestTypeDef,
+    ListContainerInstancesResponseTypeDef,
+    ListServicesByNamespaceRequestListServicesByNamespacePaginateTypeDef,
     ListServicesByNamespaceRequestRequestTypeDef,
+    ListServicesByNamespaceResponseTypeDef,
+    ListServicesRequestListServicesPaginateTypeDef,
     ListServicesRequestRequestTypeDef,
+    ListServicesResponseTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTaskDefinitionFamiliesRequestListTaskDefinitionFamiliesPaginateTypeDef,
     ListTaskDefinitionFamiliesRequestRequestTypeDef,
+    ListTaskDefinitionFamiliesResponseTypeDef,
+    ListTaskDefinitionsRequestListTaskDefinitionsPaginateTypeDef,
     ListTaskDefinitionsRequestRequestTypeDef,
+    ListTaskDefinitionsResponseTypeDef,
+    ListTasksRequestListTasksPaginateTypeDef,
     ListTasksRequestRequestTypeDef,
+    ListTasksResponseTypeDef,
     ManagedAgentStateChangeTypeDef,
+    PaginatorConfigTypeDef,
     PlatformDeviceTypeDef,
     PutAccountSettingDefaultRequestRequestTypeDef,
     PutAccountSettingRequestRequestTypeDef,
     RuntimePlatformTypeDef,
     TaskDefinitionPlacementConstraintTypeDef,
+    ResponseMetadataTypeDef,
     ServiceConnectClientAliasTypeDef,
     ServiceEventTypeDef,
     StopTaskRequestRequestTypeDef,
+    SubmitAttachmentStateChangesResponseTypeDef,
+    SubmitContainerStateChangeResponseTypeDef,
+    SubmitTaskStateChangeResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateContainerAgentRequestRequestTypeDef,
     UpdateContainerInstancesStateRequestRequestTypeDef,
     UpdateServicePrimaryTaskSetRequestRequestTypeDef,
     UpdateTaskProtectionRequestRequestTypeDef,
     SubmitAttachmentStateChangesRequestRequestTypeDef,
     AttachmentTypeDef,
     ProxyConfigurationTypeDef,
     DeleteAttributesRequestRequestTypeDef,
+    DeleteAttributesResponseTypeDef,
+    ListAttributesResponseTypeDef,
     PutAttributesRequestRequestTypeDef,
+    PutAttributesResponseTypeDef,
     AutoScalingGroupProviderTypeDef,
     AutoScalingGroupProviderUpdateTypeDef,
     NetworkConfigurationTypeDef,
     PutClusterCapacityProvidersRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UpdateClusterSettingsRequestRequestTypeDef,
     ContainerOverrideTypeDef,
     LogConfigurationTypeDef,
     ContainerInstanceHealthStatusTypeDef,
     ContainerStateChangeTypeDef,
     SubmitContainerStateChangeRequestRequestTypeDef,
     ContainerTypeDef,
-    DeleteAttributesResponseTypeDef,
-    DiscoverPollEndpointResponseTypeDef,
-    ListAttributesResponseTypeDef,
-    ListClustersResponseTypeDef,
-    ListContainerInstancesResponseTypeDef,
-    ListServicesByNamespaceResponseTypeDef,
-    ListServicesResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    ListTaskDefinitionFamiliesResponseTypeDef,
-    ListTaskDefinitionsResponseTypeDef,
-    ListTasksResponseTypeDef,
-    PutAttributesResponseTypeDef,
-    SubmitAttachmentStateChangesResponseTypeDef,
-    SubmitContainerStateChangeResponseTypeDef,
-    SubmitTaskStateChangeResponseTypeDef,
     UpdateTaskSetRequestRequestTypeDef,
     DeleteAccountSettingResponseTypeDef,
     ListAccountSettingsResponseTypeDef,
     PutAccountSettingDefaultResponseTypeDef,
     PutAccountSettingResponseTypeDef,
     DeploymentConfigurationTypeDef,
     DescribeServicesRequestServicesInactiveWaitTypeDef,
@@ -588,23 +598,14 @@
     EFSVolumeConfigurationTypeDef,
     ExecuteCommandConfigurationTypeDef,
     ExecuteCommandResponseTypeDef,
     FSxWindowsFileServerVolumeConfigurationTypeDef,
     GetTaskProtectionResponseTypeDef,
     UpdateTaskProtectionResponseTypeDef,
     LinuxParametersTypeDef,
-    ListAccountSettingsRequestListAccountSettingsPaginateTypeDef,
-    ListAttributesRequestListAttributesPaginateTypeDef,
-    ListClustersRequestListClustersPaginateTypeDef,
-    ListContainerInstancesRequestListContainerInstancesPaginateTypeDef,
-    ListServicesByNamespaceRequestListServicesByNamespacePaginateTypeDef,
-    ListServicesRequestListServicesPaginateTypeDef,
-    ListTaskDefinitionFamiliesRequestListTaskDefinitionFamiliesPaginateTypeDef,
-    ListTaskDefinitionsRequestListTaskDefinitionsPaginateTypeDef,
-    ListTasksRequestListTasksPaginateTypeDef,
     RegisterContainerInstanceRequestRequestTypeDef,
     ServiceConnectServiceTypeDef,
     CapacityProviderTypeDef,
     CreateCapacityProviderRequestRequestTypeDef,
     UpdateCapacityProviderRequestRequestTypeDef,
     CreateTaskSetRequestRequestTypeDef,
     TaskSetTypeDef,
@@ -646,14 +647,15 @@
     StopTaskResponseTypeDef,
     CreateClusterResponseTypeDef,
     DeleteClusterResponseTypeDef,
     DescribeClustersResponseTypeDef,
     PutClusterCapacityProvidersResponseTypeDef,
     UpdateClusterResponseTypeDef,
     UpdateClusterSettingsResponseTypeDef,
+    DeleteTaskDefinitionsResponseTypeDef,
     DeregisterTaskDefinitionResponseTypeDef,
     DescribeTaskDefinitionResponseTypeDef,
     RegisterTaskDefinitionResponseTypeDef,
     ServiceTypeDef,
     CreateServiceResponseTypeDef,
     DeleteServiceResponseTypeDef,
     DescribeServicesResponseTypeDef,
@@ -668,43 +670,43 @@
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

### Comparing `types-aiobotocore-ecs-2.5.0.post1/README.md` & `types-aiobotocore-ecs-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-ecs"></a>
 
 # types-aiobotocore-ecs
 
 [![PyPI - types-aiobotocore-ecs](https://img.shields.io/pypi/v/types-aiobotocore-ecs.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ecs)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-ecs.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ecs)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-ecs?color=blue)](https://pypistats.org/packages/types-aiobotocore-ecs)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ECS 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS)
+[aiobotocore.ECS 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS)
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
 [types-aiobotocore-ecs docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs/).
 
 See how it helps to find and fix potential bugs:
 
@@ -438,114 +438,124 @@
     VolumeFromTypeDef,
     InstanceHealthCheckResultTypeDef,
     ResourceTypeDef,
     VersionInfoTypeDef,
     NetworkBindingTypeDef,
     ManagedAgentTypeDef,
     NetworkInterfaceTypeDef,
-    ResponseMetadataTypeDef,
     DeploymentControllerTypeDef,
     LoadBalancerTypeDef,
     PlacementConstraintTypeDef,
     PlacementStrategyTypeDef,
     ServiceRegistryTypeDef,
     ScaleTypeDef,
     DeleteAccountSettingRequestRequestTypeDef,
     SettingTypeDef,
     DeleteCapacityProviderRequestRequestTypeDef,
     DeleteClusterRequestRequestTypeDef,
     DeleteServiceRequestRequestTypeDef,
+    DeleteTaskDefinitionsRequestRequestTypeDef,
+    FailureTypeDef,
     DeleteTaskSetRequestRequestTypeDef,
     DeploymentAlarmsTypeDef,
     DeploymentCircuitBreakerTypeDef,
     ServiceConnectServiceResourceTypeDef,
     DeregisterContainerInstanceRequestRequestTypeDef,
     DeregisterTaskDefinitionRequestRequestTypeDef,
     DescribeCapacityProvidersRequestRequestTypeDef,
-    FailureTypeDef,
     DescribeClustersRequestRequestTypeDef,
     DescribeContainerInstancesRequestRequestTypeDef,
     DescribeServicesRequestRequestTypeDef,
     WaiterConfigTypeDef,
     DescribeTaskDefinitionRequestRequestTypeDef,
     DescribeTaskSetsRequestRequestTypeDef,
     DescribeTasksRequestRequestTypeDef,
     DeviceTypeDef,
     DiscoverPollEndpointRequestRequestTypeDef,
+    DiscoverPollEndpointResponseTypeDef,
     DockerVolumeConfigurationTypeDef,
     EFSAuthorizationConfigTypeDef,
     EphemeralStorageTypeDef,
     ExecuteCommandLogConfigurationTypeDef,
     ExecuteCommandRequestRequestTypeDef,
     SessionTypeDef,
     FSxWindowsFileServerAuthorizationConfigTypeDef,
     GetTaskProtectionRequestRequestTypeDef,
     ProtectedTaskTypeDef,
     HostVolumePropertiesTypeDef,
     InferenceAcceleratorOverrideTypeDef,
     InferenceAcceleratorTypeDef,
     KernelCapabilitiesTypeDef,
     TmpfsTypeDef,
-    PaginatorConfigTypeDef,
+    ListAccountSettingsRequestListAccountSettingsPaginateTypeDef,
     ListAccountSettingsRequestRequestTypeDef,
+    ListAttributesRequestListAttributesPaginateTypeDef,
     ListAttributesRequestRequestTypeDef,
+    ListClustersRequestListClustersPaginateTypeDef,
     ListClustersRequestRequestTypeDef,
+    ListClustersResponseTypeDef,
+    ListContainerInstancesRequestListContainerInstancesPaginateTypeDef,
     ListContainerInstancesRequestRequestTypeDef,
+    ListContainerInstancesResponseTypeDef,
+    ListServicesByNamespaceRequestListServicesByNamespacePaginateTypeDef,
     ListServicesByNamespaceRequestRequestTypeDef,
+    ListServicesByNamespaceResponseTypeDef,
+    ListServicesRequestListServicesPaginateTypeDef,
     ListServicesRequestRequestTypeDef,
+    ListServicesResponseTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTaskDefinitionFamiliesRequestListTaskDefinitionFamiliesPaginateTypeDef,
     ListTaskDefinitionFamiliesRequestRequestTypeDef,
+    ListTaskDefinitionFamiliesResponseTypeDef,
+    ListTaskDefinitionsRequestListTaskDefinitionsPaginateTypeDef,
     ListTaskDefinitionsRequestRequestTypeDef,
+    ListTaskDefinitionsResponseTypeDef,
+    ListTasksRequestListTasksPaginateTypeDef,
     ListTasksRequestRequestTypeDef,
+    ListTasksResponseTypeDef,
     ManagedAgentStateChangeTypeDef,
+    PaginatorConfigTypeDef,
     PlatformDeviceTypeDef,
     PutAccountSettingDefaultRequestRequestTypeDef,
     PutAccountSettingRequestRequestTypeDef,
     RuntimePlatformTypeDef,
     TaskDefinitionPlacementConstraintTypeDef,
+    ResponseMetadataTypeDef,
     ServiceConnectClientAliasTypeDef,
     ServiceEventTypeDef,
     StopTaskRequestRequestTypeDef,
+    SubmitAttachmentStateChangesResponseTypeDef,
+    SubmitContainerStateChangeResponseTypeDef,
+    SubmitTaskStateChangeResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateContainerAgentRequestRequestTypeDef,
     UpdateContainerInstancesStateRequestRequestTypeDef,
     UpdateServicePrimaryTaskSetRequestRequestTypeDef,
     UpdateTaskProtectionRequestRequestTypeDef,
     SubmitAttachmentStateChangesRequestRequestTypeDef,
     AttachmentTypeDef,
     ProxyConfigurationTypeDef,
     DeleteAttributesRequestRequestTypeDef,
+    DeleteAttributesResponseTypeDef,
+    ListAttributesResponseTypeDef,
     PutAttributesRequestRequestTypeDef,
+    PutAttributesResponseTypeDef,
     AutoScalingGroupProviderTypeDef,
     AutoScalingGroupProviderUpdateTypeDef,
     NetworkConfigurationTypeDef,
     PutClusterCapacityProvidersRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UpdateClusterSettingsRequestRequestTypeDef,
     ContainerOverrideTypeDef,
     LogConfigurationTypeDef,
     ContainerInstanceHealthStatusTypeDef,
     ContainerStateChangeTypeDef,
     SubmitContainerStateChangeRequestRequestTypeDef,
     ContainerTypeDef,
-    DeleteAttributesResponseTypeDef,
-    DiscoverPollEndpointResponseTypeDef,
-    ListAttributesResponseTypeDef,
-    ListClustersResponseTypeDef,
-    ListContainerInstancesResponseTypeDef,
-    ListServicesByNamespaceResponseTypeDef,
-    ListServicesResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    ListTaskDefinitionFamiliesResponseTypeDef,
-    ListTaskDefinitionsResponseTypeDef,
-    ListTasksResponseTypeDef,
-    PutAttributesResponseTypeDef,
-    SubmitAttachmentStateChangesResponseTypeDef,
-    SubmitContainerStateChangeResponseTypeDef,
-    SubmitTaskStateChangeResponseTypeDef,
     UpdateTaskSetRequestRequestTypeDef,
     DeleteAccountSettingResponseTypeDef,
     ListAccountSettingsResponseTypeDef,
     PutAccountSettingDefaultResponseTypeDef,
     PutAccountSettingResponseTypeDef,
     DeploymentConfigurationTypeDef,
     DescribeServicesRequestServicesInactiveWaitTypeDef,
@@ -555,23 +565,14 @@
     EFSVolumeConfigurationTypeDef,
     ExecuteCommandConfigurationTypeDef,
     ExecuteCommandResponseTypeDef,
     FSxWindowsFileServerVolumeConfigurationTypeDef,
     GetTaskProtectionResponseTypeDef,
     UpdateTaskProtectionResponseTypeDef,
     LinuxParametersTypeDef,
-    ListAccountSettingsRequestListAccountSettingsPaginateTypeDef,
-    ListAttributesRequestListAttributesPaginateTypeDef,
-    ListClustersRequestListClustersPaginateTypeDef,
-    ListContainerInstancesRequestListContainerInstancesPaginateTypeDef,
-    ListServicesByNamespaceRequestListServicesByNamespacePaginateTypeDef,
-    ListServicesRequestListServicesPaginateTypeDef,
-    ListTaskDefinitionFamiliesRequestListTaskDefinitionFamiliesPaginateTypeDef,
-    ListTaskDefinitionsRequestListTaskDefinitionsPaginateTypeDef,
-    ListTasksRequestListTasksPaginateTypeDef,
     RegisterContainerInstanceRequestRequestTypeDef,
     ServiceConnectServiceTypeDef,
     CapacityProviderTypeDef,
     CreateCapacityProviderRequestRequestTypeDef,
     UpdateCapacityProviderRequestRequestTypeDef,
     CreateTaskSetRequestRequestTypeDef,
     TaskSetTypeDef,
@@ -613,14 +614,15 @@
     StopTaskResponseTypeDef,
     CreateClusterResponseTypeDef,
     DeleteClusterResponseTypeDef,
     DescribeClustersResponseTypeDef,
     PutClusterCapacityProvidersResponseTypeDef,
     UpdateClusterResponseTypeDef,
     UpdateClusterSettingsResponseTypeDef,
+    DeleteTaskDefinitionsResponseTypeDef,
     DeregisterTaskDefinitionResponseTypeDef,
     DescribeTaskDefinitionResponseTypeDef,
     RegisterTaskDefinitionResponseTypeDef,
     ServiceTypeDef,
     CreateServiceResponseTypeDef,
     DeleteServiceResponseTypeDef,
     DescribeServicesResponseTypeDef,
@@ -635,43 +637,43 @@
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

### Comparing `types-aiobotocore-ecs-2.5.0.post1/setup.py` & `types-aiobotocore-ecs-2.5.1/setup.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-ecs.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-ecs",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_ecs"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.ECS 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.ECS 2.5.1 service generated with mypy-boto3-builder"
+        " 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -46,11 +46,11 @@
     python_requires=">=3.7",
     project_urls={
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs/",
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

### Comparing `types-aiobotocore-ecs-2.5.0.post1/types_aiobotocore_ecs/__init__.py` & `types-aiobotocore-ecs-2.5.1/types_aiobotocore_ecs/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ecs-2.5.0.post1/types_aiobotocore_ecs/__init__.pyi` & `types-aiobotocore-ecs-2.5.1/types_aiobotocore_ecs/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ecs-2.5.0.post1/types_aiobotocore_ecs/__main__.py` & `types-aiobotocore-ecs-2.5.1/types_aiobotocore_ecs/__main__.py`

 * *Files 17% similar despite different names*

```diff
@@ -5,28 +5,28 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.ECS 2.5.0\nVersion:         2.5.0.post1\nBuilder version:"
-        " 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.ECS 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs//\nBoto3 docs:    "
         "  https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS\nOther"
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

### Comparing `types-aiobotocore-ecs-2.5.0.post1/types_aiobotocore_ecs/client.py` & `types-aiobotocore-ecs-2.5.1/types_aiobotocore_ecs/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -65,14 +65,15 @@
     CreateServiceResponseTypeDef,
     CreateTaskSetResponseTypeDef,
     DeleteAccountSettingResponseTypeDef,
     DeleteAttributesResponseTypeDef,
     DeleteCapacityProviderResponseTypeDef,
     DeleteClusterResponseTypeDef,
     DeleteServiceResponseTypeDef,
+    DeleteTaskDefinitionsResponseTypeDef,
     DeleteTaskSetResponseTypeDef,
     DeploymentConfigurationTypeDef,
     DeploymentControllerTypeDef,
     DeregisterContainerInstanceResponseTypeDef,
     DeregisterTaskDefinitionResponseTypeDef,
     DescribeCapacityProvidersResponseTypeDef,
     DescribeClustersResponseTypeDef,
@@ -313,16 +314,16 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs/client/#create_task_set)
         """
 
     async def delete_account_setting(
         self, *, name: SettingNameType, principalArn: str = ...
     ) -> DeleteAccountSettingResponseTypeDef:
         """
-        Disables an account setting for a specified IAM user, IAM role, or the root user
-        for an account.
+        Disables an account setting for a specified user, role, or the root user for an
+        account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Client.delete_account_setting)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs/client/#delete_account_setting)
         """
 
     async def delete_attributes(
         self, *, attributes: Sequence[AttributeTypeDef], cluster: str = ...
@@ -358,14 +359,24 @@
         """
         Deletes a specified service within a cluster.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Client.delete_service)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs/client/#delete_service)
         """
 
+    async def delete_task_definitions(
+        self, *, taskDefinitions: Sequence[str]
+    ) -> DeleteTaskDefinitionsResponseTypeDef:
+        """
+        Deletes one or more task definitions.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Client.delete_task_definitions)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs/client/#delete_task_definitions)
+        """
+
     async def delete_task_set(
         self, *, cluster: str, service: str, taskSet: str, force: bool = ...
     ) -> DeleteTaskSetResponseTypeDef:
         """
         Deletes a specified task set within a service.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Client.delete_task_set)
@@ -689,16 +700,16 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs/client/#put_account_setting)
         """
 
     async def put_account_setting_default(
         self, *, name: SettingNameType, value: str
     ) -> PutAccountSettingDefaultResponseTypeDef:
         """
-        Modifies an account setting for all IAM users on an account for whom no
-        individual account setting has been specified.
+        Modifies an account setting for all users on an account for whom no individual
+        account setting has been specified.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Client.put_account_setting_default)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs/client/#put_account_setting_default)
         """
 
     async def put_attributes(
         self, *, attributes: Sequence[AttributeTypeDef], cluster: str = ...
```

### Comparing `types-aiobotocore-ecs-2.5.0.post1/types_aiobotocore_ecs/client.pyi` & `types-aiobotocore-ecs-2.5.1/types_aiobotocore_ecs/client.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -65,14 +65,15 @@
     CreateServiceResponseTypeDef,
     CreateTaskSetResponseTypeDef,
     DeleteAccountSettingResponseTypeDef,
     DeleteAttributesResponseTypeDef,
     DeleteCapacityProviderResponseTypeDef,
     DeleteClusterResponseTypeDef,
     DeleteServiceResponseTypeDef,
+    DeleteTaskDefinitionsResponseTypeDef,
     DeleteTaskSetResponseTypeDef,
     DeploymentConfigurationTypeDef,
     DeploymentControllerTypeDef,
     DeregisterContainerInstanceResponseTypeDef,
     DeregisterTaskDefinitionResponseTypeDef,
     DescribeCapacityProvidersResponseTypeDef,
     DescribeClustersResponseTypeDef,
@@ -302,16 +303,16 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Client.create_task_set)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs/client/#create_task_set)
         """
     async def delete_account_setting(
         self, *, name: SettingNameType, principalArn: str = ...
     ) -> DeleteAccountSettingResponseTypeDef:
         """
-        Disables an account setting for a specified IAM user, IAM role, or the root user
-        for an account.
+        Disables an account setting for a specified user, role, or the root user for an
+        account.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Client.delete_account_setting)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs/client/#delete_account_setting)
         """
     async def delete_attributes(
         self, *, attributes: Sequence[AttributeTypeDef], cluster: str = ...
     ) -> DeleteAttributesResponseTypeDef:
@@ -342,14 +343,23 @@
     ) -> DeleteServiceResponseTypeDef:
         """
         Deletes a specified service within a cluster.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Client.delete_service)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs/client/#delete_service)
         """
+    async def delete_task_definitions(
+        self, *, taskDefinitions: Sequence[str]
+    ) -> DeleteTaskDefinitionsResponseTypeDef:
+        """
+        Deletes one or more task definitions.
+
+        [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Client.delete_task_definitions)
+        [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs/client/#delete_task_definitions)
+        """
     async def delete_task_set(
         self, *, cluster: str, service: str, taskSet: str, force: bool = ...
     ) -> DeleteTaskSetResponseTypeDef:
         """
         Deletes a specified task set within a service.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Client.delete_task_set)
@@ -648,16 +658,16 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Client.put_account_setting)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs/client/#put_account_setting)
         """
     async def put_account_setting_default(
         self, *, name: SettingNameType, value: str
     ) -> PutAccountSettingDefaultResponseTypeDef:
         """
-        Modifies an account setting for all IAM users on an account for whom no
-        individual account setting has been specified.
+        Modifies an account setting for all users on an account for whom no individual
+        account setting has been specified.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Client.put_account_setting_default)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs/client/#put_account_setting_default)
         """
     async def put_attributes(
         self, *, attributes: Sequence[AttributeTypeDef], cluster: str = ...
     ) -> PutAttributesResponseTypeDef:
```

### Comparing `types-aiobotocore-ecs-2.5.0.post1/types_aiobotocore_ecs/literals.py` & `types-aiobotocore-ecs-2.5.1/types_aiobotocore_ecs/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -176,24 +176,26 @@
 ServiceFieldType = Literal["TAGS"]
 ServicesInactiveWaiterName = Literal["services_inactive"]
 ServicesStableWaiterName = Literal["services_stable"]
 SettingNameType = Literal[
     "awsvpcTrunking",
     "containerInsights",
     "containerInstanceLongArnFormat",
+    "fargateFIPSMode",
     "serviceLongArnFormat",
+    "tagResourceAuthorization",
     "taskLongArnFormat",
 ]
 SortOrderType = Literal["ASC", "DESC"]
 StabilityStatusType = Literal["STABILIZING", "STEADY_STATE"]
 TargetTypeType = Literal["container-instance"]
 TaskDefinitionFamilyStatusType = Literal["ACTIVE", "ALL", "INACTIVE"]
 TaskDefinitionFieldType = Literal["TAGS"]
 TaskDefinitionPlacementConstraintTypeType = Literal["memberOf"]
-TaskDefinitionStatusType = Literal["ACTIVE", "INACTIVE"]
+TaskDefinitionStatusType = Literal["ACTIVE", "DELETE_IN_PROGRESS", "INACTIVE"]
 TaskFieldType = Literal["TAGS"]
 TaskSetFieldType = Literal["TAGS"]
 TaskStopCodeType = Literal[
     "EssentialContainerExited",
     "ServiceSchedulerInitiated",
     "SpotInterruption",
     "TaskFailedToStart",
@@ -279,14 +281,15 @@
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
@@ -365,14 +368,15 @@
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
@@ -383,14 +387,15 @@
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
@@ -426,14 +431,15 @@
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
@@ -452,16 +458,19 @@
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
@@ -545,15 +554,17 @@
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

### Comparing `types-aiobotocore-ecs-2.5.0.post1/types_aiobotocore_ecs/literals.pyi` & `types-aiobotocore-ecs-2.5.1/types_aiobotocore_ecs/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -174,24 +174,26 @@
 ServiceFieldType = Literal["TAGS"]
 ServicesInactiveWaiterName = Literal["services_inactive"]
 ServicesStableWaiterName = Literal["services_stable"]
 SettingNameType = Literal[
     "awsvpcTrunking",
     "containerInsights",
     "containerInstanceLongArnFormat",
+    "fargateFIPSMode",
     "serviceLongArnFormat",
+    "tagResourceAuthorization",
     "taskLongArnFormat",
 ]
 SortOrderType = Literal["ASC", "DESC"]
 StabilityStatusType = Literal["STABILIZING", "STEADY_STATE"]
 TargetTypeType = Literal["container-instance"]
 TaskDefinitionFamilyStatusType = Literal["ACTIVE", "ALL", "INACTIVE"]
 TaskDefinitionFieldType = Literal["TAGS"]
 TaskDefinitionPlacementConstraintTypeType = Literal["memberOf"]
-TaskDefinitionStatusType = Literal["ACTIVE", "INACTIVE"]
+TaskDefinitionStatusType = Literal["ACTIVE", "DELETE_IN_PROGRESS", "INACTIVE"]
 TaskFieldType = Literal["TAGS"]
 TaskSetFieldType = Literal["TAGS"]
 TaskStopCodeType = Literal[
     "EssentialContainerExited",
     "ServiceSchedulerInitiated",
     "SpotInterruption",
     "TaskFailedToStart",
@@ -277,14 +279,15 @@
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
@@ -363,14 +366,15 @@
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
@@ -381,14 +385,15 @@
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
@@ -424,14 +429,15 @@
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
@@ -450,16 +456,19 @@
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
@@ -543,15 +552,17 @@
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

### Comparing `types-aiobotocore-ecs-2.5.0.post1/types_aiobotocore_ecs/paginator.py` & `types-aiobotocore-ecs-2.5.1/types_aiobotocore_ecs/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -33,15 +33,15 @@
         list_services_by_namespace_paginator: ListServicesByNamespacePaginator = client.get_paginator("list_services_by_namespace")
         list_task_definition_families_paginator: ListTaskDefinitionFamiliesPaginator = client.get_paginator("list_task_definition_families")
         list_task_definitions_paginator: ListTaskDefinitionsPaginator = client.get_paginator("list_task_definitions")
         list_tasks_paginator: ListTasksPaginator = client.get_paginator("list_tasks")
     ```
 """
 import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     ContainerInstanceStatusType,
     DesiredStatusType,
@@ -61,18 +61,14 @@
     ListServicesResponseTypeDef,
     ListTaskDefinitionFamiliesResponseTypeDef,
     ListTaskDefinitionsResponseTypeDef,
     ListTasksResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 
 __all__ = (
@@ -107,15 +103,15 @@
     def paginate(
         self,
         *,
         name: SettingNameType = ...,
         value: str = ...,
         principalArn: str = ...,
         effectiveSettings: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAccountSettingsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Paginator.ListAccountSettings.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs/paginators/#listaccountsettingspaginator)
         """
 
 
@@ -128,30 +124,30 @@
     def paginate(
         self,
         *,
         targetType: Literal["container-instance"],
         cluster: str = ...,
         attributeName: str = ...,
         attributeValue: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAttributesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Paginator.ListAttributes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs/paginators/#listattributespaginator)
         """
 
 
 class ListClustersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Paginator.ListClusters)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs/paginators/#listclusterspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListClustersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Paginator.ListClusters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs/paginators/#listclusterspaginator)
         """
 
 
@@ -163,15 +159,15 @@
 
     def paginate(
         self,
         *,
         cluster: str = ...,
         filter: str = ...,
         status: ContainerInstanceStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListContainerInstancesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Paginator.ListContainerInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs/paginators/#listcontainerinstancespaginator)
         """
 
 
@@ -183,30 +179,30 @@
 
     def paginate(
         self,
         *,
         cluster: str = ...,
         launchType: LaunchTypeType = ...,
         schedulingStrategy: SchedulingStrategyType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListServicesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Paginator.ListServices.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs/paginators/#listservicespaginator)
         """
 
 
 class ListServicesByNamespacePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Paginator.ListServicesByNamespace)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs/paginators/#listservicesbynamespacepaginator)
     """
 
     def paginate(
-        self, *, namespace: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, namespace: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListServicesByNamespaceResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Paginator.ListServicesByNamespace.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs/paginators/#listservicesbynamespacepaginator)
         """
 
 
@@ -217,15 +213,15 @@
     """
 
     def paginate(
         self,
         *,
         familyPrefix: str = ...,
         status: TaskDefinitionFamilyStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTaskDefinitionFamiliesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Paginator.ListTaskDefinitionFamilies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs/paginators/#listtaskdefinitionfamiliespaginator)
         """
 
 
@@ -237,15 +233,15 @@
 
     def paginate(
         self,
         *,
         familyPrefix: str = ...,
         status: TaskDefinitionStatusType = ...,
         sort: SortOrderType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTaskDefinitionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Paginator.ListTaskDefinitions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs/paginators/#listtaskdefinitionspaginator)
         """
 
 
@@ -261,13 +257,13 @@
         cluster: str = ...,
         containerInstance: str = ...,
         family: str = ...,
         startedBy: str = ...,
         serviceName: str = ...,
         desiredStatus: DesiredStatusType = ...,
         launchType: LaunchTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTasksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Paginator.ListTasks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs/paginators/#listtaskspaginator)
         """
```

### Comparing `types-aiobotocore-ecs-2.5.0.post1/types_aiobotocore_ecs/paginator.pyi` & `types-aiobotocore-ecs-2.5.1/types_aiobotocore_ecs/paginator.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -33,15 +33,15 @@
         list_services_by_namespace_paginator: ListServicesByNamespacePaginator = client.get_paginator("list_services_by_namespace")
         list_task_definition_families_paginator: ListTaskDefinitionFamiliesPaginator = client.get_paginator("list_task_definition_families")
         list_task_definitions_paginator: ListTaskDefinitionsPaginator = client.get_paginator("list_task_definitions")
         list_tasks_paginator: ListTasksPaginator = client.get_paginator("list_tasks")
     ```
 """
 import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     ContainerInstanceStatusType,
     DesiredStatusType,
@@ -61,18 +61,14 @@
     ListServicesResponseTypeDef,
     ListTaskDefinitionFamiliesResponseTypeDef,
     ListTaskDefinitionsResponseTypeDef,
     ListTasksResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
 __all__ = (
     "ListAccountSettingsPaginator",
@@ -103,15 +99,15 @@
     def paginate(
         self,
         *,
         name: SettingNameType = ...,
         value: str = ...,
         principalArn: str = ...,
         effectiveSettings: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAccountSettingsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Paginator.ListAccountSettings.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs/paginators/#listaccountsettingspaginator)
         """
 
 class ListAttributesPaginator(AioPaginator):
@@ -123,29 +119,29 @@
     def paginate(
         self,
         *,
         targetType: Literal["container-instance"],
         cluster: str = ...,
         attributeName: str = ...,
         attributeValue: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListAttributesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Paginator.ListAttributes.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs/paginators/#listattributespaginator)
         """
 
 class ListClustersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Paginator.ListClusters)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs/paginators/#listclusterspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListClustersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Paginator.ListClusters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs/paginators/#listclusterspaginator)
         """
 
 class ListContainerInstancesPaginator(AioPaginator):
@@ -156,15 +152,15 @@
 
     def paginate(
         self,
         *,
         cluster: str = ...,
         filter: str = ...,
         status: ContainerInstanceStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListContainerInstancesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Paginator.ListContainerInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs/paginators/#listcontainerinstancespaginator)
         """
 
 class ListServicesPaginator(AioPaginator):
@@ -175,29 +171,29 @@
 
     def paginate(
         self,
         *,
         cluster: str = ...,
         launchType: LaunchTypeType = ...,
         schedulingStrategy: SchedulingStrategyType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListServicesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Paginator.ListServices.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs/paginators/#listservicespaginator)
         """
 
 class ListServicesByNamespacePaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Paginator.ListServicesByNamespace)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs/paginators/#listservicesbynamespacepaginator)
     """
 
     def paginate(
-        self, *, namespace: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, namespace: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListServicesByNamespaceResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Paginator.ListServicesByNamespace.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs/paginators/#listservicesbynamespacepaginator)
         """
 
 class ListTaskDefinitionFamiliesPaginator(AioPaginator):
@@ -207,15 +203,15 @@
     """
 
     def paginate(
         self,
         *,
         familyPrefix: str = ...,
         status: TaskDefinitionFamilyStatusType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTaskDefinitionFamiliesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Paginator.ListTaskDefinitionFamilies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs/paginators/#listtaskdefinitionfamiliespaginator)
         """
 
 class ListTaskDefinitionsPaginator(AioPaginator):
@@ -226,15 +222,15 @@
 
     def paginate(
         self,
         *,
         familyPrefix: str = ...,
         status: TaskDefinitionStatusType = ...,
         sort: SortOrderType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTaskDefinitionsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Paginator.ListTaskDefinitions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs/paginators/#listtaskdefinitionspaginator)
         """
 
 class ListTasksPaginator(AioPaginator):
@@ -249,13 +245,13 @@
         cluster: str = ...,
         containerInstance: str = ...,
         family: str = ...,
         startedBy: str = ...,
         serviceName: str = ...,
         desiredStatus: DesiredStatusType = ...,
         launchType: LaunchTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTasksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS.Paginator.ListTasks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs/paginators/#listtaskspaginator)
         """
```

### Comparing `types-aiobotocore-ecs-2.5.0.post1/types_aiobotocore_ecs/type_defs.py` & `types-aiobotocore-ecs-2.5.1/types_aiobotocore_ecs/type_defs.py`

 * *Files 7% similar despite different names*

```diff
@@ -98,114 +98,124 @@
     "VolumeFromTypeDef",
     "InstanceHealthCheckResultTypeDef",
     "ResourceTypeDef",
     "VersionInfoTypeDef",
     "NetworkBindingTypeDef",
     "ManagedAgentTypeDef",
     "NetworkInterfaceTypeDef",
-    "ResponseMetadataTypeDef",
     "DeploymentControllerTypeDef",
     "LoadBalancerTypeDef",
     "PlacementConstraintTypeDef",
     "PlacementStrategyTypeDef",
     "ServiceRegistryTypeDef",
     "ScaleTypeDef",
     "DeleteAccountSettingRequestRequestTypeDef",
     "SettingTypeDef",
     "DeleteCapacityProviderRequestRequestTypeDef",
     "DeleteClusterRequestRequestTypeDef",
     "DeleteServiceRequestRequestTypeDef",
+    "DeleteTaskDefinitionsRequestRequestTypeDef",
+    "FailureTypeDef",
     "DeleteTaskSetRequestRequestTypeDef",
     "DeploymentAlarmsTypeDef",
     "DeploymentCircuitBreakerTypeDef",
     "ServiceConnectServiceResourceTypeDef",
     "DeregisterContainerInstanceRequestRequestTypeDef",
     "DeregisterTaskDefinitionRequestRequestTypeDef",
     "DescribeCapacityProvidersRequestRequestTypeDef",
-    "FailureTypeDef",
     "DescribeClustersRequestRequestTypeDef",
     "DescribeContainerInstancesRequestRequestTypeDef",
     "DescribeServicesRequestRequestTypeDef",
     "WaiterConfigTypeDef",
     "DescribeTaskDefinitionRequestRequestTypeDef",
     "DescribeTaskSetsRequestRequestTypeDef",
     "DescribeTasksRequestRequestTypeDef",
     "DeviceTypeDef",
     "DiscoverPollEndpointRequestRequestTypeDef",
+    "DiscoverPollEndpointResponseTypeDef",
     "DockerVolumeConfigurationTypeDef",
     "EFSAuthorizationConfigTypeDef",
     "EphemeralStorageTypeDef",
     "ExecuteCommandLogConfigurationTypeDef",
     "ExecuteCommandRequestRequestTypeDef",
     "SessionTypeDef",
     "FSxWindowsFileServerAuthorizationConfigTypeDef",
     "GetTaskProtectionRequestRequestTypeDef",
     "ProtectedTaskTypeDef",
     "HostVolumePropertiesTypeDef",
     "InferenceAcceleratorOverrideTypeDef",
     "InferenceAcceleratorTypeDef",
     "KernelCapabilitiesTypeDef",
     "TmpfsTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListAccountSettingsRequestListAccountSettingsPaginateTypeDef",
     "ListAccountSettingsRequestRequestTypeDef",
+    "ListAttributesRequestListAttributesPaginateTypeDef",
     "ListAttributesRequestRequestTypeDef",
+    "ListClustersRequestListClustersPaginateTypeDef",
     "ListClustersRequestRequestTypeDef",
+    "ListClustersResponseTypeDef",
+    "ListContainerInstancesRequestListContainerInstancesPaginateTypeDef",
     "ListContainerInstancesRequestRequestTypeDef",
+    "ListContainerInstancesResponseTypeDef",
+    "ListServicesByNamespaceRequestListServicesByNamespacePaginateTypeDef",
     "ListServicesByNamespaceRequestRequestTypeDef",
+    "ListServicesByNamespaceResponseTypeDef",
+    "ListServicesRequestListServicesPaginateTypeDef",
     "ListServicesRequestRequestTypeDef",
+    "ListServicesResponseTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTaskDefinitionFamiliesRequestListTaskDefinitionFamiliesPaginateTypeDef",
     "ListTaskDefinitionFamiliesRequestRequestTypeDef",
+    "ListTaskDefinitionFamiliesResponseTypeDef",
+    "ListTaskDefinitionsRequestListTaskDefinitionsPaginateTypeDef",
     "ListTaskDefinitionsRequestRequestTypeDef",
+    "ListTaskDefinitionsResponseTypeDef",
+    "ListTasksRequestListTasksPaginateTypeDef",
     "ListTasksRequestRequestTypeDef",
+    "ListTasksResponseTypeDef",
     "ManagedAgentStateChangeTypeDef",
+    "PaginatorConfigTypeDef",
     "PlatformDeviceTypeDef",
     "PutAccountSettingDefaultRequestRequestTypeDef",
     "PutAccountSettingRequestRequestTypeDef",
     "RuntimePlatformTypeDef",
     "TaskDefinitionPlacementConstraintTypeDef",
+    "ResponseMetadataTypeDef",
     "ServiceConnectClientAliasTypeDef",
     "ServiceEventTypeDef",
     "StopTaskRequestRequestTypeDef",
+    "SubmitAttachmentStateChangesResponseTypeDef",
+    "SubmitContainerStateChangeResponseTypeDef",
+    "SubmitTaskStateChangeResponseTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateContainerAgentRequestRequestTypeDef",
     "UpdateContainerInstancesStateRequestRequestTypeDef",
     "UpdateServicePrimaryTaskSetRequestRequestTypeDef",
     "UpdateTaskProtectionRequestRequestTypeDef",
     "SubmitAttachmentStateChangesRequestRequestTypeDef",
     "AttachmentTypeDef",
     "ProxyConfigurationTypeDef",
     "DeleteAttributesRequestRequestTypeDef",
+    "DeleteAttributesResponseTypeDef",
+    "ListAttributesResponseTypeDef",
     "PutAttributesRequestRequestTypeDef",
+    "PutAttributesResponseTypeDef",
     "AutoScalingGroupProviderTypeDef",
     "AutoScalingGroupProviderUpdateTypeDef",
     "NetworkConfigurationTypeDef",
     "PutClusterCapacityProvidersRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UpdateClusterSettingsRequestRequestTypeDef",
     "ContainerOverrideTypeDef",
     "LogConfigurationTypeDef",
     "ContainerInstanceHealthStatusTypeDef",
     "ContainerStateChangeTypeDef",
     "SubmitContainerStateChangeRequestRequestTypeDef",
     "ContainerTypeDef",
-    "DeleteAttributesResponseTypeDef",
-    "DiscoverPollEndpointResponseTypeDef",
-    "ListAttributesResponseTypeDef",
-    "ListClustersResponseTypeDef",
-    "ListContainerInstancesResponseTypeDef",
-    "ListServicesByNamespaceResponseTypeDef",
-    "ListServicesResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "ListTaskDefinitionFamiliesResponseTypeDef",
-    "ListTaskDefinitionsResponseTypeDef",
-    "ListTasksResponseTypeDef",
-    "PutAttributesResponseTypeDef",
-    "SubmitAttachmentStateChangesResponseTypeDef",
-    "SubmitContainerStateChangeResponseTypeDef",
-    "SubmitTaskStateChangeResponseTypeDef",
     "UpdateTaskSetRequestRequestTypeDef",
     "DeleteAccountSettingResponseTypeDef",
     "ListAccountSettingsResponseTypeDef",
     "PutAccountSettingDefaultResponseTypeDef",
     "PutAccountSettingResponseTypeDef",
     "DeploymentConfigurationTypeDef",
     "DescribeServicesRequestServicesInactiveWaitTypeDef",
@@ -215,23 +225,14 @@
     "EFSVolumeConfigurationTypeDef",
     "ExecuteCommandConfigurationTypeDef",
     "ExecuteCommandResponseTypeDef",
     "FSxWindowsFileServerVolumeConfigurationTypeDef",
     "GetTaskProtectionResponseTypeDef",
     "UpdateTaskProtectionResponseTypeDef",
     "LinuxParametersTypeDef",
-    "ListAccountSettingsRequestListAccountSettingsPaginateTypeDef",
-    "ListAttributesRequestListAttributesPaginateTypeDef",
-    "ListClustersRequestListClustersPaginateTypeDef",
-    "ListContainerInstancesRequestListContainerInstancesPaginateTypeDef",
-    "ListServicesByNamespaceRequestListServicesByNamespacePaginateTypeDef",
-    "ListServicesRequestListServicesPaginateTypeDef",
-    "ListTaskDefinitionFamiliesRequestListTaskDefinitionFamiliesPaginateTypeDef",
-    "ListTaskDefinitionsRequestListTaskDefinitionsPaginateTypeDef",
-    "ListTasksRequestListTasksPaginateTypeDef",
     "RegisterContainerInstanceRequestRequestTypeDef",
     "ServiceConnectServiceTypeDef",
     "CapacityProviderTypeDef",
     "CreateCapacityProviderRequestRequestTypeDef",
     "UpdateCapacityProviderRequestRequestTypeDef",
     "CreateTaskSetRequestRequestTypeDef",
     "TaskSetTypeDef",
@@ -273,14 +274,15 @@
     "StopTaskResponseTypeDef",
     "CreateClusterResponseTypeDef",
     "DeleteClusterResponseTypeDef",
     "DescribeClustersResponseTypeDef",
     "PutClusterCapacityProvidersResponseTypeDef",
     "UpdateClusterResponseTypeDef",
     "UpdateClusterSettingsResponseTypeDef",
+    "DeleteTaskDefinitionsResponseTypeDef",
     "DeregisterTaskDefinitionResponseTypeDef",
     "DescribeTaskDefinitionResponseTypeDef",
     "RegisterTaskDefinitionResponseTypeDef",
     "ServiceTypeDef",
     "CreateServiceResponseTypeDef",
     "DeleteServiceResponseTypeDef",
     "DescribeServicesResponseTypeDef",
@@ -618,25 +620,14 @@
         "attachmentId": str,
         "privateIpv4Address": str,
         "ipv6Address": str,
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
 DeploymentControllerTypeDef = TypedDict(
     "DeploymentControllerTypeDef",
     {
         "type": DeploymentControllerTypeType,
     },
 )
 
@@ -753,14 +744,31 @@
 
 class DeleteServiceRequestRequestTypeDef(
     _RequiredDeleteServiceRequestRequestTypeDef, _OptionalDeleteServiceRequestRequestTypeDef
 ):
     pass
 
 
+DeleteTaskDefinitionsRequestRequestTypeDef = TypedDict(
+    "DeleteTaskDefinitionsRequestRequestTypeDef",
+    {
+        "taskDefinitions": Sequence[str],
+    },
+)
+
+FailureTypeDef = TypedDict(
+    "FailureTypeDef",
+    {
+        "arn": str,
+        "reason": str,
+        "detail": str,
+    },
+    total=False,
+)
+
 _RequiredDeleteTaskSetRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteTaskSetRequestRequestTypeDef",
     {
         "cluster": str,
         "service": str,
         "taskSet": str,
     },
@@ -843,24 +851,14 @@
         "include": Sequence[Literal["TAGS"]],
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
-FailureTypeDef = TypedDict(
-    "FailureTypeDef",
-    {
-        "arn": str,
-        "reason": str,
-        "detail": str,
-    },
-    total=False,
-)
-
 DescribeClustersRequestRequestTypeDef = TypedDict(
     "DescribeClustersRequestRequestTypeDef",
     {
         "clusters": Sequence[str],
         "include": Sequence[ClusterFieldType],
     },
     total=False,
@@ -1012,14 +1010,24 @@
     {
         "containerInstance": str,
         "cluster": str,
     },
     total=False,
 )
 
+DiscoverPollEndpointResponseTypeDef = TypedDict(
+    "DiscoverPollEndpointResponseTypeDef",
+    {
+        "endpoint": str,
+        "telemetryEndpoint": str,
+        "serviceConnectEndpoint": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DockerVolumeConfigurationTypeDef = TypedDict(
     "DockerVolumeConfigurationTypeDef",
     {
         "scope": ScopeType,
         "autoprovision": bool,
         "driver": str,
         "driverOpts": Dict[str, str],
@@ -1179,20 +1187,22 @@
 )
 
 
 class TmpfsTypeDef(_RequiredTmpfsTypeDef, _OptionalTmpfsTypeDef):
     pass
 
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListAccountSettingsRequestListAccountSettingsPaginateTypeDef = TypedDict(
+    "ListAccountSettingsRequestListAccountSettingsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "name": SettingNameType,
+        "value": str,
+        "principalArn": str,
+        "effectiveSettings": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListAccountSettingsRequestRequestTypeDef = TypedDict(
     "ListAccountSettingsRequestRequestTypeDef",
     {
@@ -1202,14 +1212,39 @@
         "effectiveSettings": bool,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+_RequiredListAttributesRequestListAttributesPaginateTypeDef = TypedDict(
+    "_RequiredListAttributesRequestListAttributesPaginateTypeDef",
+    {
+        "targetType": Literal["container-instance"],
+    },
+)
+_OptionalListAttributesRequestListAttributesPaginateTypeDef = TypedDict(
+    "_OptionalListAttributesRequestListAttributesPaginateTypeDef",
+    {
+        "cluster": str,
+        "attributeName": str,
+        "attributeValue": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListAttributesRequestListAttributesPaginateTypeDef(
+    _RequiredListAttributesRequestListAttributesPaginateTypeDef,
+    _OptionalListAttributesRequestListAttributesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListAttributesRequestRequestTypeDef = TypedDict(
     "_RequiredListAttributesRequestRequestTypeDef",
     {
         "targetType": Literal["container-instance"],
     },
 )
 _OptionalListAttributesRequestRequestTypeDef = TypedDict(
@@ -1227,35 +1262,94 @@
 
 class ListAttributesRequestRequestTypeDef(
     _RequiredListAttributesRequestRequestTypeDef, _OptionalListAttributesRequestRequestTypeDef
 ):
     pass
 
 
+ListClustersRequestListClustersPaginateTypeDef = TypedDict(
+    "ListClustersRequestListClustersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListClustersRequestRequestTypeDef = TypedDict(
     "ListClustersRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListClustersResponseTypeDef = TypedDict(
+    "ListClustersResponseTypeDef",
+    {
+        "clusterArns": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListContainerInstancesRequestListContainerInstancesPaginateTypeDef = TypedDict(
+    "ListContainerInstancesRequestListContainerInstancesPaginateTypeDef",
+    {
+        "cluster": str,
+        "filter": str,
+        "status": ContainerInstanceStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListContainerInstancesRequestRequestTypeDef = TypedDict(
     "ListContainerInstancesRequestRequestTypeDef",
     {
         "cluster": str,
         "filter": str,
         "nextToken": str,
         "maxResults": int,
         "status": ContainerInstanceStatusType,
     },
     total=False,
 )
 
+ListContainerInstancesResponseTypeDef = TypedDict(
+    "ListContainerInstancesResponseTypeDef",
+    {
+        "containerInstanceArns": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListServicesByNamespaceRequestListServicesByNamespacePaginateTypeDef = TypedDict(
+    "_RequiredListServicesByNamespaceRequestListServicesByNamespacePaginateTypeDef",
+    {
+        "namespace": str,
+    },
+)
+_OptionalListServicesByNamespaceRequestListServicesByNamespacePaginateTypeDef = TypedDict(
+    "_OptionalListServicesByNamespaceRequestListServicesByNamespacePaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListServicesByNamespaceRequestListServicesByNamespacePaginateTypeDef(
+    _RequiredListServicesByNamespaceRequestListServicesByNamespacePaginateTypeDef,
+    _OptionalListServicesByNamespaceRequestListServicesByNamespacePaginateTypeDef,
+):
+    pass
+
+
 _RequiredListServicesByNamespaceRequestRequestTypeDef = TypedDict(
     "_RequiredListServicesByNamespaceRequestRequestTypeDef",
     {
         "namespace": str,
     },
 )
 _OptionalListServicesByNamespaceRequestRequestTypeDef = TypedDict(
@@ -1271,56 +1365,139 @@
 class ListServicesByNamespaceRequestRequestTypeDef(
     _RequiredListServicesByNamespaceRequestRequestTypeDef,
     _OptionalListServicesByNamespaceRequestRequestTypeDef,
 ):
     pass
 
 
+ListServicesByNamespaceResponseTypeDef = TypedDict(
+    "ListServicesByNamespaceResponseTypeDef",
+    {
+        "serviceArns": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListServicesRequestListServicesPaginateTypeDef = TypedDict(
+    "ListServicesRequestListServicesPaginateTypeDef",
+    {
+        "cluster": str,
+        "launchType": LaunchTypeType,
+        "schedulingStrategy": SchedulingStrategyType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListServicesRequestRequestTypeDef = TypedDict(
     "ListServicesRequestRequestTypeDef",
     {
         "cluster": str,
         "nextToken": str,
         "maxResults": int,
         "launchType": LaunchTypeType,
         "schedulingStrategy": SchedulingStrategyType,
     },
     total=False,
 )
 
+ListServicesResponseTypeDef = TypedDict(
+    "ListServicesResponseTypeDef",
+    {
+        "serviceArns": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
+ListTaskDefinitionFamiliesRequestListTaskDefinitionFamiliesPaginateTypeDef = TypedDict(
+    "ListTaskDefinitionFamiliesRequestListTaskDefinitionFamiliesPaginateTypeDef",
+    {
+        "familyPrefix": str,
+        "status": TaskDefinitionFamilyStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListTaskDefinitionFamiliesRequestRequestTypeDef = TypedDict(
     "ListTaskDefinitionFamiliesRequestRequestTypeDef",
     {
         "familyPrefix": str,
         "status": TaskDefinitionFamilyStatusType,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListTaskDefinitionFamiliesResponseTypeDef = TypedDict(
+    "ListTaskDefinitionFamiliesResponseTypeDef",
+    {
+        "families": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListTaskDefinitionsRequestListTaskDefinitionsPaginateTypeDef = TypedDict(
+    "ListTaskDefinitionsRequestListTaskDefinitionsPaginateTypeDef",
+    {
+        "familyPrefix": str,
+        "status": TaskDefinitionStatusType,
+        "sort": SortOrderType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListTaskDefinitionsRequestRequestTypeDef = TypedDict(
     "ListTaskDefinitionsRequestRequestTypeDef",
     {
         "familyPrefix": str,
         "status": TaskDefinitionStatusType,
         "sort": SortOrderType,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListTaskDefinitionsResponseTypeDef = TypedDict(
+    "ListTaskDefinitionsResponseTypeDef",
+    {
+        "taskDefinitionArns": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListTasksRequestListTasksPaginateTypeDef = TypedDict(
+    "ListTasksRequestListTasksPaginateTypeDef",
+    {
+        "cluster": str,
+        "containerInstance": str,
+        "family": str,
+        "startedBy": str,
+        "serviceName": str,
+        "desiredStatus": DesiredStatusType,
+        "launchType": LaunchTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListTasksRequestRequestTypeDef = TypedDict(
     "ListTasksRequestRequestTypeDef",
     {
         "cluster": str,
         "containerInstance": str,
         "family": str,
         "nextToken": str,
@@ -1329,14 +1506,23 @@
         "serviceName": str,
         "desiredStatus": DesiredStatusType,
         "launchType": LaunchTypeType,
     },
     total=False,
 )
 
+ListTasksResponseTypeDef = TypedDict(
+    "ListTasksResponseTypeDef",
+    {
+        "taskArns": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredManagedAgentStateChangeTypeDef = TypedDict(
     "_RequiredManagedAgentStateChangeTypeDef",
     {
         "containerName": str,
         "managedAgentName": Literal["ExecuteCommandAgent"],
         "status": str,
     },
@@ -1352,14 +1538,24 @@
 
 class ManagedAgentStateChangeTypeDef(
     _RequiredManagedAgentStateChangeTypeDef, _OptionalManagedAgentStateChangeTypeDef
 ):
     pass
 
 
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
 PlatformDeviceTypeDef = TypedDict(
     "PlatformDeviceTypeDef",
     {
         "id": str,
         "type": Literal["GPU"],
     },
 )
@@ -1408,14 +1604,25 @@
     {
         "type": Literal["memberOf"],
         "expression": str,
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
 _RequiredServiceConnectClientAliasTypeDef = TypedDict(
     "_RequiredServiceConnectClientAliasTypeDef",
     {
         "port": int,
     },
 )
 _OptionalServiceConnectClientAliasTypeDef = TypedDict(
@@ -1461,14 +1668,38 @@
 
 class StopTaskRequestRequestTypeDef(
     _RequiredStopTaskRequestRequestTypeDef, _OptionalStopTaskRequestRequestTypeDef
 ):
     pass
 
 
+SubmitAttachmentStateChangesResponseTypeDef = TypedDict(
+    "SubmitAttachmentStateChangesResponseTypeDef",
+    {
+        "acknowledgment": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+SubmitContainerStateChangeResponseTypeDef = TypedDict(
+    "SubmitContainerStateChangeResponseTypeDef",
+    {
+        "acknowledgment": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+SubmitTaskStateChangeResponseTypeDef = TypedDict(
+    "SubmitTaskStateChangeResponseTypeDef",
+    {
+        "acknowledgment": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
@@ -1623,14 +1854,31 @@
 
 class DeleteAttributesRequestRequestTypeDef(
     _RequiredDeleteAttributesRequestRequestTypeDef, _OptionalDeleteAttributesRequestRequestTypeDef
 ):
     pass
 
 
+DeleteAttributesResponseTypeDef = TypedDict(
+    "DeleteAttributesResponseTypeDef",
+    {
+        "attributes": List[AttributeTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListAttributesResponseTypeDef = TypedDict(
+    "ListAttributesResponseTypeDef",
+    {
+        "attributes": List[AttributeTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredPutAttributesRequestRequestTypeDef = TypedDict(
     "_RequiredPutAttributesRequestRequestTypeDef",
     {
         "attributes": Sequence[AttributeTypeDef],
     },
 )
 _OptionalPutAttributesRequestRequestTypeDef = TypedDict(
@@ -1644,14 +1892,22 @@
 
 class PutAttributesRequestRequestTypeDef(
     _RequiredPutAttributesRequestRequestTypeDef, _OptionalPutAttributesRequestRequestTypeDef
 ):
     pass
 
 
+PutAttributesResponseTypeDef = TypedDict(
+    "PutAttributesResponseTypeDef",
+    {
+        "attributes": List[AttributeTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredAutoScalingGroupProviderTypeDef = TypedDict(
     "_RequiredAutoScalingGroupProviderTypeDef",
     {
         "autoScalingGroupArn": str,
     },
 )
 _OptionalAutoScalingGroupProviderTypeDef = TypedDict(
@@ -1692,14 +1948,22 @@
     {
         "cluster": str,
         "capacityProviders": Sequence[str],
         "defaultCapacityProviderStrategy": Sequence[CapacityProviderStrategyItemTypeDef],
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "tags": List[TagTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tags": Sequence[TagTypeDef],
     },
 )
@@ -1805,184 +2069,54 @@
         "memory": str,
         "memoryReservation": str,
         "gpuIds": List[str],
     },
     total=False,
 )
 
-DeleteAttributesResponseTypeDef = TypedDict(
-    "DeleteAttributesResponseTypeDef",
-    {
-        "attributes": List[AttributeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DiscoverPollEndpointResponseTypeDef = TypedDict(
-    "DiscoverPollEndpointResponseTypeDef",
-    {
-        "endpoint": str,
-        "telemetryEndpoint": str,
-        "serviceConnectEndpoint": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAttributesResponseTypeDef = TypedDict(
-    "ListAttributesResponseTypeDef",
-    {
-        "attributes": List[AttributeTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListClustersResponseTypeDef = TypedDict(
-    "ListClustersResponseTypeDef",
-    {
-        "clusterArns": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListContainerInstancesResponseTypeDef = TypedDict(
-    "ListContainerInstancesResponseTypeDef",
-    {
-        "containerInstanceArns": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListServicesByNamespaceResponseTypeDef = TypedDict(
-    "ListServicesByNamespaceResponseTypeDef",
-    {
-        "serviceArns": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListServicesResponseTypeDef = TypedDict(
-    "ListServicesResponseTypeDef",
-    {
-        "serviceArns": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTaskDefinitionFamiliesResponseTypeDef = TypedDict(
-    "ListTaskDefinitionFamiliesResponseTypeDef",
-    {
-        "families": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTaskDefinitionsResponseTypeDef = TypedDict(
-    "ListTaskDefinitionsResponseTypeDef",
-    {
-        "taskDefinitionArns": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTasksResponseTypeDef = TypedDict(
-    "ListTasksResponseTypeDef",
-    {
-        "taskArns": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutAttributesResponseTypeDef = TypedDict(
-    "PutAttributesResponseTypeDef",
-    {
-        "attributes": List[AttributeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SubmitAttachmentStateChangesResponseTypeDef = TypedDict(
-    "SubmitAttachmentStateChangesResponseTypeDef",
-    {
-        "acknowledgment": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SubmitContainerStateChangeResponseTypeDef = TypedDict(
-    "SubmitContainerStateChangeResponseTypeDef",
-    {
-        "acknowledgment": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SubmitTaskStateChangeResponseTypeDef = TypedDict(
-    "SubmitTaskStateChangeResponseTypeDef",
-    {
-        "acknowledgment": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 UpdateTaskSetRequestRequestTypeDef = TypedDict(
     "UpdateTaskSetRequestRequestTypeDef",
     {
         "cluster": str,
         "service": str,
         "taskSet": str,
         "scale": ScaleTypeDef,
     },
 )
 
 DeleteAccountSettingResponseTypeDef = TypedDict(
     "DeleteAccountSettingResponseTypeDef",
     {
         "setting": SettingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAccountSettingsResponseTypeDef = TypedDict(
     "ListAccountSettingsResponseTypeDef",
     {
         "settings": List[SettingTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutAccountSettingDefaultResponseTypeDef = TypedDict(
     "PutAccountSettingDefaultResponseTypeDef",
     {
         "setting": SettingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutAccountSettingResponseTypeDef = TypedDict(
     "PutAccountSettingResponseTypeDef",
     {
         "setting": SettingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeploymentConfigurationTypeDef = TypedDict(
     "DeploymentConfigurationTypeDef",
     {
         "deploymentCircuitBreaker": DeploymentCircuitBreakerTypeDef,
@@ -2128,15 +2262,15 @@
     {
         "clusterArn": str,
         "containerArn": str,
         "containerName": str,
         "interactive": bool,
         "session": SessionTypeDef,
         "taskArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FSxWindowsFileServerVolumeConfigurationTypeDef = TypedDict(
     "FSxWindowsFileServerVolumeConfigurationTypeDef",
     {
         "fileSystemId": str,
@@ -2146,24 +2280,24 @@
 )
 
 GetTaskProtectionResponseTypeDef = TypedDict(
     "GetTaskProtectionResponseTypeDef",
     {
         "protectedTasks": List[ProtectedTaskTypeDef],
         "failures": List[FailureTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateTaskProtectionResponseTypeDef = TypedDict(
     "UpdateTaskProtectionResponseTypeDef",
     {
         "protectedTasks": List[ProtectedTaskTypeDef],
         "failures": List[FailureTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LinuxParametersTypeDef = TypedDict(
     "LinuxParametersTypeDef",
     {
         "capabilities": KernelCapabilitiesTypeDef,
@@ -2173,139 +2307,14 @@
         "tmpfs": List[TmpfsTypeDef],
         "maxSwap": int,
         "swappiness": int,
     },
     total=False,
 )
 
-ListAccountSettingsRequestListAccountSettingsPaginateTypeDef = TypedDict(
-    "ListAccountSettingsRequestListAccountSettingsPaginateTypeDef",
-    {
-        "name": SettingNameType,
-        "value": str,
-        "principalArn": str,
-        "effectiveSettings": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListAttributesRequestListAttributesPaginateTypeDef = TypedDict(
-    "_RequiredListAttributesRequestListAttributesPaginateTypeDef",
-    {
-        "targetType": Literal["container-instance"],
-    },
-)
-_OptionalListAttributesRequestListAttributesPaginateTypeDef = TypedDict(
-    "_OptionalListAttributesRequestListAttributesPaginateTypeDef",
-    {
-        "cluster": str,
-        "attributeName": str,
-        "attributeValue": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListAttributesRequestListAttributesPaginateTypeDef(
-    _RequiredListAttributesRequestListAttributesPaginateTypeDef,
-    _OptionalListAttributesRequestListAttributesPaginateTypeDef,
-):
-    pass
-
-
-ListClustersRequestListClustersPaginateTypeDef = TypedDict(
-    "ListClustersRequestListClustersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListContainerInstancesRequestListContainerInstancesPaginateTypeDef = TypedDict(
-    "ListContainerInstancesRequestListContainerInstancesPaginateTypeDef",
-    {
-        "cluster": str,
-        "filter": str,
-        "status": ContainerInstanceStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListServicesByNamespaceRequestListServicesByNamespacePaginateTypeDef = TypedDict(
-    "_RequiredListServicesByNamespaceRequestListServicesByNamespacePaginateTypeDef",
-    {
-        "namespace": str,
-    },
-)
-_OptionalListServicesByNamespaceRequestListServicesByNamespacePaginateTypeDef = TypedDict(
-    "_OptionalListServicesByNamespaceRequestListServicesByNamespacePaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListServicesByNamespaceRequestListServicesByNamespacePaginateTypeDef(
-    _RequiredListServicesByNamespaceRequestListServicesByNamespacePaginateTypeDef,
-    _OptionalListServicesByNamespaceRequestListServicesByNamespacePaginateTypeDef,
-):
-    pass
-
-
-ListServicesRequestListServicesPaginateTypeDef = TypedDict(
-    "ListServicesRequestListServicesPaginateTypeDef",
-    {
-        "cluster": str,
-        "launchType": LaunchTypeType,
-        "schedulingStrategy": SchedulingStrategyType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListTaskDefinitionFamiliesRequestListTaskDefinitionFamiliesPaginateTypeDef = TypedDict(
-    "ListTaskDefinitionFamiliesRequestListTaskDefinitionFamiliesPaginateTypeDef",
-    {
-        "familyPrefix": str,
-        "status": TaskDefinitionFamilyStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListTaskDefinitionsRequestListTaskDefinitionsPaginateTypeDef = TypedDict(
-    "ListTaskDefinitionsRequestListTaskDefinitionsPaginateTypeDef",
-    {
-        "familyPrefix": str,
-        "status": TaskDefinitionStatusType,
-        "sort": SortOrderType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListTasksRequestListTasksPaginateTypeDef = TypedDict(
-    "ListTasksRequestListTasksPaginateTypeDef",
-    {
-        "cluster": str,
-        "containerInstance": str,
-        "family": str,
-        "startedBy": str,
-        "serviceName": str,
-        "desiredStatus": DesiredStatusType,
-        "launchType": LaunchTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 RegisterContainerInstanceRequestRequestTypeDef = TypedDict(
     "RegisterContainerInstanceRequestRequestTypeDef",
     {
         "cluster": str,
         "instanceIdentityDocument": str,
         "instanceIdentityDocumentSignature": str,
         "totalResources": Sequence[ResourceTypeDef],
@@ -2594,82 +2603,82 @@
     pass
 
 
 CreateCapacityProviderResponseTypeDef = TypedDict(
     "CreateCapacityProviderResponseTypeDef",
     {
         "capacityProvider": CapacityProviderTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteCapacityProviderResponseTypeDef = TypedDict(
     "DeleteCapacityProviderResponseTypeDef",
     {
         "capacityProvider": CapacityProviderTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeCapacityProvidersResponseTypeDef = TypedDict(
     "DescribeCapacityProvidersResponseTypeDef",
     {
         "capacityProviders": List[CapacityProviderTypeDef],
         "failures": List[FailureTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateCapacityProviderResponseTypeDef = TypedDict(
     "UpdateCapacityProviderResponseTypeDef",
     {
         "capacityProvider": CapacityProviderTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateTaskSetResponseTypeDef = TypedDict(
     "CreateTaskSetResponseTypeDef",
     {
         "taskSet": TaskSetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteTaskSetResponseTypeDef = TypedDict(
     "DeleteTaskSetResponseTypeDef",
     {
         "taskSet": TaskSetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeTaskSetsResponseTypeDef = TypedDict(
     "DescribeTaskSetsResponseTypeDef",
     {
         "taskSets": List[TaskSetTypeDef],
         "failures": List[FailureTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateServicePrimaryTaskSetResponseTypeDef = TypedDict(
     "UpdateServicePrimaryTaskSetResponseTypeDef",
     {
         "taskSet": TaskSetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateTaskSetResponseTypeDef = TypedDict(
     "UpdateTaskSetResponseTypeDef",
     {
         "taskSet": TaskSetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredRunTaskRequestRequestTypeDef = TypedDict(
     "_RequiredRunTaskRequestRequestTypeDef",
     {
         "taskDefinition": str,
@@ -2779,49 +2788,49 @@
     total=False,
 )
 
 DeregisterContainerInstanceResponseTypeDef = TypedDict(
     "DeregisterContainerInstanceResponseTypeDef",
     {
         "containerInstance": ContainerInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeContainerInstancesResponseTypeDef = TypedDict(
     "DescribeContainerInstancesResponseTypeDef",
     {
         "containerInstances": List[ContainerInstanceTypeDef],
         "failures": List[FailureTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RegisterContainerInstanceResponseTypeDef = TypedDict(
     "RegisterContainerInstanceResponseTypeDef",
     {
         "containerInstance": ContainerInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateContainerAgentResponseTypeDef = TypedDict(
     "UpdateContainerAgentResponseTypeDef",
     {
         "containerInstance": ContainerInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateContainerInstancesStateResponseTypeDef = TypedDict(
     "UpdateContainerInstancesStateResponseTypeDef",
     {
         "containerInstances": List[ContainerInstanceTypeDef],
         "failures": List[FailureTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ClusterTypeDef = TypedDict(
     "ClusterTypeDef",
     {
         "clusterArn": str,
@@ -3054,116 +3063,125 @@
 
 
 DescribeTasksResponseTypeDef = TypedDict(
     "DescribeTasksResponseTypeDef",
     {
         "tasks": List[TaskTypeDef],
         "failures": List[FailureTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RunTaskResponseTypeDef = TypedDict(
     "RunTaskResponseTypeDef",
     {
         "tasks": List[TaskTypeDef],
         "failures": List[FailureTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartTaskResponseTypeDef = TypedDict(
     "StartTaskResponseTypeDef",
     {
         "tasks": List[TaskTypeDef],
         "failures": List[FailureTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopTaskResponseTypeDef = TypedDict(
     "StopTaskResponseTypeDef",
     {
         "task": TaskTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateClusterResponseTypeDef = TypedDict(
     "CreateClusterResponseTypeDef",
     {
         "cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteClusterResponseTypeDef = TypedDict(
     "DeleteClusterResponseTypeDef",
     {
         "cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeClustersResponseTypeDef = TypedDict(
     "DescribeClustersResponseTypeDef",
     {
         "clusters": List[ClusterTypeDef],
         "failures": List[FailureTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutClusterCapacityProvidersResponseTypeDef = TypedDict(
     "PutClusterCapacityProvidersResponseTypeDef",
     {
         "cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateClusterResponseTypeDef = TypedDict(
     "UpdateClusterResponseTypeDef",
     {
         "cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateClusterSettingsResponseTypeDef = TypedDict(
     "UpdateClusterSettingsResponseTypeDef",
     {
         "cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DeleteTaskDefinitionsResponseTypeDef = TypedDict(
+    "DeleteTaskDefinitionsResponseTypeDef",
+    {
+        "taskDefinitions": List[TaskDefinitionTypeDef],
+        "failures": List[FailureTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeregisterTaskDefinitionResponseTypeDef = TypedDict(
     "DeregisterTaskDefinitionResponseTypeDef",
     {
         "taskDefinition": TaskDefinitionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeTaskDefinitionResponseTypeDef = TypedDict(
     "DescribeTaskDefinitionResponseTypeDef",
     {
         "taskDefinition": TaskDefinitionTypeDef,
         "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RegisterTaskDefinitionResponseTypeDef = TypedDict(
     "RegisterTaskDefinitionResponseTypeDef",
     {
         "taskDefinition": TaskDefinitionTypeDef,
         "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ServiceTypeDef = TypedDict(
     "ServiceTypeDef",
     {
         "serviceArn": str,
@@ -3201,35 +3219,35 @@
     total=False,
 )
 
 CreateServiceResponseTypeDef = TypedDict(
     "CreateServiceResponseTypeDef",
     {
         "service": ServiceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteServiceResponseTypeDef = TypedDict(
     "DeleteServiceResponseTypeDef",
     {
         "service": ServiceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeServicesResponseTypeDef = TypedDict(
     "DescribeServicesResponseTypeDef",
     {
         "services": List[ServiceTypeDef],
         "failures": List[FailureTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateServiceResponseTypeDef = TypedDict(
     "UpdateServiceResponseTypeDef",
     {
         "service": ServiceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-ecs-2.5.0.post1/types_aiobotocore_ecs/type_defs.pyi` & `types-aiobotocore-ecs-2.5.1/types_aiobotocore_ecs/type_defs.pyi`

 * *Files 7% similar despite different names*

```diff
@@ -97,114 +97,124 @@
     "VolumeFromTypeDef",
     "InstanceHealthCheckResultTypeDef",
     "ResourceTypeDef",
     "VersionInfoTypeDef",
     "NetworkBindingTypeDef",
     "ManagedAgentTypeDef",
     "NetworkInterfaceTypeDef",
-    "ResponseMetadataTypeDef",
     "DeploymentControllerTypeDef",
     "LoadBalancerTypeDef",
     "PlacementConstraintTypeDef",
     "PlacementStrategyTypeDef",
     "ServiceRegistryTypeDef",
     "ScaleTypeDef",
     "DeleteAccountSettingRequestRequestTypeDef",
     "SettingTypeDef",
     "DeleteCapacityProviderRequestRequestTypeDef",
     "DeleteClusterRequestRequestTypeDef",
     "DeleteServiceRequestRequestTypeDef",
+    "DeleteTaskDefinitionsRequestRequestTypeDef",
+    "FailureTypeDef",
     "DeleteTaskSetRequestRequestTypeDef",
     "DeploymentAlarmsTypeDef",
     "DeploymentCircuitBreakerTypeDef",
     "ServiceConnectServiceResourceTypeDef",
     "DeregisterContainerInstanceRequestRequestTypeDef",
     "DeregisterTaskDefinitionRequestRequestTypeDef",
     "DescribeCapacityProvidersRequestRequestTypeDef",
-    "FailureTypeDef",
     "DescribeClustersRequestRequestTypeDef",
     "DescribeContainerInstancesRequestRequestTypeDef",
     "DescribeServicesRequestRequestTypeDef",
     "WaiterConfigTypeDef",
     "DescribeTaskDefinitionRequestRequestTypeDef",
     "DescribeTaskSetsRequestRequestTypeDef",
     "DescribeTasksRequestRequestTypeDef",
     "DeviceTypeDef",
     "DiscoverPollEndpointRequestRequestTypeDef",
+    "DiscoverPollEndpointResponseTypeDef",
     "DockerVolumeConfigurationTypeDef",
     "EFSAuthorizationConfigTypeDef",
     "EphemeralStorageTypeDef",
     "ExecuteCommandLogConfigurationTypeDef",
     "ExecuteCommandRequestRequestTypeDef",
     "SessionTypeDef",
     "FSxWindowsFileServerAuthorizationConfigTypeDef",
     "GetTaskProtectionRequestRequestTypeDef",
     "ProtectedTaskTypeDef",
     "HostVolumePropertiesTypeDef",
     "InferenceAcceleratorOverrideTypeDef",
     "InferenceAcceleratorTypeDef",
     "KernelCapabilitiesTypeDef",
     "TmpfsTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListAccountSettingsRequestListAccountSettingsPaginateTypeDef",
     "ListAccountSettingsRequestRequestTypeDef",
+    "ListAttributesRequestListAttributesPaginateTypeDef",
     "ListAttributesRequestRequestTypeDef",
+    "ListClustersRequestListClustersPaginateTypeDef",
     "ListClustersRequestRequestTypeDef",
+    "ListClustersResponseTypeDef",
+    "ListContainerInstancesRequestListContainerInstancesPaginateTypeDef",
     "ListContainerInstancesRequestRequestTypeDef",
+    "ListContainerInstancesResponseTypeDef",
+    "ListServicesByNamespaceRequestListServicesByNamespacePaginateTypeDef",
     "ListServicesByNamespaceRequestRequestTypeDef",
+    "ListServicesByNamespaceResponseTypeDef",
+    "ListServicesRequestListServicesPaginateTypeDef",
     "ListServicesRequestRequestTypeDef",
+    "ListServicesResponseTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTaskDefinitionFamiliesRequestListTaskDefinitionFamiliesPaginateTypeDef",
     "ListTaskDefinitionFamiliesRequestRequestTypeDef",
+    "ListTaskDefinitionFamiliesResponseTypeDef",
+    "ListTaskDefinitionsRequestListTaskDefinitionsPaginateTypeDef",
     "ListTaskDefinitionsRequestRequestTypeDef",
+    "ListTaskDefinitionsResponseTypeDef",
+    "ListTasksRequestListTasksPaginateTypeDef",
     "ListTasksRequestRequestTypeDef",
+    "ListTasksResponseTypeDef",
     "ManagedAgentStateChangeTypeDef",
+    "PaginatorConfigTypeDef",
     "PlatformDeviceTypeDef",
     "PutAccountSettingDefaultRequestRequestTypeDef",
     "PutAccountSettingRequestRequestTypeDef",
     "RuntimePlatformTypeDef",
     "TaskDefinitionPlacementConstraintTypeDef",
+    "ResponseMetadataTypeDef",
     "ServiceConnectClientAliasTypeDef",
     "ServiceEventTypeDef",
     "StopTaskRequestRequestTypeDef",
+    "SubmitAttachmentStateChangesResponseTypeDef",
+    "SubmitContainerStateChangeResponseTypeDef",
+    "SubmitTaskStateChangeResponseTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateContainerAgentRequestRequestTypeDef",
     "UpdateContainerInstancesStateRequestRequestTypeDef",
     "UpdateServicePrimaryTaskSetRequestRequestTypeDef",
     "UpdateTaskProtectionRequestRequestTypeDef",
     "SubmitAttachmentStateChangesRequestRequestTypeDef",
     "AttachmentTypeDef",
     "ProxyConfigurationTypeDef",
     "DeleteAttributesRequestRequestTypeDef",
+    "DeleteAttributesResponseTypeDef",
+    "ListAttributesResponseTypeDef",
     "PutAttributesRequestRequestTypeDef",
+    "PutAttributesResponseTypeDef",
     "AutoScalingGroupProviderTypeDef",
     "AutoScalingGroupProviderUpdateTypeDef",
     "NetworkConfigurationTypeDef",
     "PutClusterCapacityProvidersRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UpdateClusterSettingsRequestRequestTypeDef",
     "ContainerOverrideTypeDef",
     "LogConfigurationTypeDef",
     "ContainerInstanceHealthStatusTypeDef",
     "ContainerStateChangeTypeDef",
     "SubmitContainerStateChangeRequestRequestTypeDef",
     "ContainerTypeDef",
-    "DeleteAttributesResponseTypeDef",
-    "DiscoverPollEndpointResponseTypeDef",
-    "ListAttributesResponseTypeDef",
-    "ListClustersResponseTypeDef",
-    "ListContainerInstancesResponseTypeDef",
-    "ListServicesByNamespaceResponseTypeDef",
-    "ListServicesResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "ListTaskDefinitionFamiliesResponseTypeDef",
-    "ListTaskDefinitionsResponseTypeDef",
-    "ListTasksResponseTypeDef",
-    "PutAttributesResponseTypeDef",
-    "SubmitAttachmentStateChangesResponseTypeDef",
-    "SubmitContainerStateChangeResponseTypeDef",
-    "SubmitTaskStateChangeResponseTypeDef",
     "UpdateTaskSetRequestRequestTypeDef",
     "DeleteAccountSettingResponseTypeDef",
     "ListAccountSettingsResponseTypeDef",
     "PutAccountSettingDefaultResponseTypeDef",
     "PutAccountSettingResponseTypeDef",
     "DeploymentConfigurationTypeDef",
     "DescribeServicesRequestServicesInactiveWaitTypeDef",
@@ -214,23 +224,14 @@
     "EFSVolumeConfigurationTypeDef",
     "ExecuteCommandConfigurationTypeDef",
     "ExecuteCommandResponseTypeDef",
     "FSxWindowsFileServerVolumeConfigurationTypeDef",
     "GetTaskProtectionResponseTypeDef",
     "UpdateTaskProtectionResponseTypeDef",
     "LinuxParametersTypeDef",
-    "ListAccountSettingsRequestListAccountSettingsPaginateTypeDef",
-    "ListAttributesRequestListAttributesPaginateTypeDef",
-    "ListClustersRequestListClustersPaginateTypeDef",
-    "ListContainerInstancesRequestListContainerInstancesPaginateTypeDef",
-    "ListServicesByNamespaceRequestListServicesByNamespacePaginateTypeDef",
-    "ListServicesRequestListServicesPaginateTypeDef",
-    "ListTaskDefinitionFamiliesRequestListTaskDefinitionFamiliesPaginateTypeDef",
-    "ListTaskDefinitionsRequestListTaskDefinitionsPaginateTypeDef",
-    "ListTasksRequestListTasksPaginateTypeDef",
     "RegisterContainerInstanceRequestRequestTypeDef",
     "ServiceConnectServiceTypeDef",
     "CapacityProviderTypeDef",
     "CreateCapacityProviderRequestRequestTypeDef",
     "UpdateCapacityProviderRequestRequestTypeDef",
     "CreateTaskSetRequestRequestTypeDef",
     "TaskSetTypeDef",
@@ -272,14 +273,15 @@
     "StopTaskResponseTypeDef",
     "CreateClusterResponseTypeDef",
     "DeleteClusterResponseTypeDef",
     "DescribeClustersResponseTypeDef",
     "PutClusterCapacityProvidersResponseTypeDef",
     "UpdateClusterResponseTypeDef",
     "UpdateClusterSettingsResponseTypeDef",
+    "DeleteTaskDefinitionsResponseTypeDef",
     "DeregisterTaskDefinitionResponseTypeDef",
     "DescribeTaskDefinitionResponseTypeDef",
     "RegisterTaskDefinitionResponseTypeDef",
     "ServiceTypeDef",
     "CreateServiceResponseTypeDef",
     "DeleteServiceResponseTypeDef",
     "DescribeServicesResponseTypeDef",
@@ -607,25 +609,14 @@
         "attachmentId": str,
         "privateIpv4Address": str,
         "ipv6Address": str,
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
 DeploymentControllerTypeDef = TypedDict(
     "DeploymentControllerTypeDef",
     {
         "type": DeploymentControllerTypeType,
     },
 )
 
@@ -738,14 +729,31 @@
 )
 
 class DeleteServiceRequestRequestTypeDef(
     _RequiredDeleteServiceRequestRequestTypeDef, _OptionalDeleteServiceRequestRequestTypeDef
 ):
     pass
 
+DeleteTaskDefinitionsRequestRequestTypeDef = TypedDict(
+    "DeleteTaskDefinitionsRequestRequestTypeDef",
+    {
+        "taskDefinitions": Sequence[str],
+    },
+)
+
+FailureTypeDef = TypedDict(
+    "FailureTypeDef",
+    {
+        "arn": str,
+        "reason": str,
+        "detail": str,
+    },
+    total=False,
+)
+
 _RequiredDeleteTaskSetRequestRequestTypeDef = TypedDict(
     "_RequiredDeleteTaskSetRequestRequestTypeDef",
     {
         "cluster": str,
         "service": str,
         "taskSet": str,
     },
@@ -824,24 +832,14 @@
         "include": Sequence[Literal["TAGS"]],
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
-FailureTypeDef = TypedDict(
-    "FailureTypeDef",
-    {
-        "arn": str,
-        "reason": str,
-        "detail": str,
-    },
-    total=False,
-)
-
 DescribeClustersRequestRequestTypeDef = TypedDict(
     "DescribeClustersRequestRequestTypeDef",
     {
         "clusters": Sequence[str],
         "include": Sequence[ClusterFieldType],
     },
     total=False,
@@ -981,14 +979,24 @@
     {
         "containerInstance": str,
         "cluster": str,
     },
     total=False,
 )
 
+DiscoverPollEndpointResponseTypeDef = TypedDict(
+    "DiscoverPollEndpointResponseTypeDef",
+    {
+        "endpoint": str,
+        "telemetryEndpoint": str,
+        "serviceConnectEndpoint": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DockerVolumeConfigurationTypeDef = TypedDict(
     "DockerVolumeConfigurationTypeDef",
     {
         "scope": ScopeType,
         "autoprovision": bool,
         "driver": str,
         "driverOpts": Dict[str, str],
@@ -1142,20 +1150,22 @@
     },
     total=False,
 )
 
 class TmpfsTypeDef(_RequiredTmpfsTypeDef, _OptionalTmpfsTypeDef):
     pass
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+ListAccountSettingsRequestListAccountSettingsPaginateTypeDef = TypedDict(
+    "ListAccountSettingsRequestListAccountSettingsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "name": SettingNameType,
+        "value": str,
+        "principalArn": str,
+        "effectiveSettings": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListAccountSettingsRequestRequestTypeDef = TypedDict(
     "ListAccountSettingsRequestRequestTypeDef",
     {
@@ -1165,14 +1175,37 @@
         "effectiveSettings": bool,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+_RequiredListAttributesRequestListAttributesPaginateTypeDef = TypedDict(
+    "_RequiredListAttributesRequestListAttributesPaginateTypeDef",
+    {
+        "targetType": Literal["container-instance"],
+    },
+)
+_OptionalListAttributesRequestListAttributesPaginateTypeDef = TypedDict(
+    "_OptionalListAttributesRequestListAttributesPaginateTypeDef",
+    {
+        "cluster": str,
+        "attributeName": str,
+        "attributeValue": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListAttributesRequestListAttributesPaginateTypeDef(
+    _RequiredListAttributesRequestListAttributesPaginateTypeDef,
+    _OptionalListAttributesRequestListAttributesPaginateTypeDef,
+):
+    pass
+
 _RequiredListAttributesRequestRequestTypeDef = TypedDict(
     "_RequiredListAttributesRequestRequestTypeDef",
     {
         "targetType": Literal["container-instance"],
     },
 )
 _OptionalListAttributesRequestRequestTypeDef = TypedDict(
@@ -1188,35 +1221,92 @@
 )
 
 class ListAttributesRequestRequestTypeDef(
     _RequiredListAttributesRequestRequestTypeDef, _OptionalListAttributesRequestRequestTypeDef
 ):
     pass
 
+ListClustersRequestListClustersPaginateTypeDef = TypedDict(
+    "ListClustersRequestListClustersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListClustersRequestRequestTypeDef = TypedDict(
     "ListClustersRequestRequestTypeDef",
     {
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListClustersResponseTypeDef = TypedDict(
+    "ListClustersResponseTypeDef",
+    {
+        "clusterArns": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListContainerInstancesRequestListContainerInstancesPaginateTypeDef = TypedDict(
+    "ListContainerInstancesRequestListContainerInstancesPaginateTypeDef",
+    {
+        "cluster": str,
+        "filter": str,
+        "status": ContainerInstanceStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListContainerInstancesRequestRequestTypeDef = TypedDict(
     "ListContainerInstancesRequestRequestTypeDef",
     {
         "cluster": str,
         "filter": str,
         "nextToken": str,
         "maxResults": int,
         "status": ContainerInstanceStatusType,
     },
     total=False,
 )
 
+ListContainerInstancesResponseTypeDef = TypedDict(
+    "ListContainerInstancesResponseTypeDef",
+    {
+        "containerInstanceArns": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListServicesByNamespaceRequestListServicesByNamespacePaginateTypeDef = TypedDict(
+    "_RequiredListServicesByNamespaceRequestListServicesByNamespacePaginateTypeDef",
+    {
+        "namespace": str,
+    },
+)
+_OptionalListServicesByNamespaceRequestListServicesByNamespacePaginateTypeDef = TypedDict(
+    "_OptionalListServicesByNamespaceRequestListServicesByNamespacePaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListServicesByNamespaceRequestListServicesByNamespacePaginateTypeDef(
+    _RequiredListServicesByNamespaceRequestListServicesByNamespacePaginateTypeDef,
+    _OptionalListServicesByNamespaceRequestListServicesByNamespacePaginateTypeDef,
+):
+    pass
+
 _RequiredListServicesByNamespaceRequestRequestTypeDef = TypedDict(
     "_RequiredListServicesByNamespaceRequestRequestTypeDef",
     {
         "namespace": str,
     },
 )
 _OptionalListServicesByNamespaceRequestRequestTypeDef = TypedDict(
@@ -1230,56 +1320,139 @@
 
 class ListServicesByNamespaceRequestRequestTypeDef(
     _RequiredListServicesByNamespaceRequestRequestTypeDef,
     _OptionalListServicesByNamespaceRequestRequestTypeDef,
 ):
     pass
 
+ListServicesByNamespaceResponseTypeDef = TypedDict(
+    "ListServicesByNamespaceResponseTypeDef",
+    {
+        "serviceArns": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListServicesRequestListServicesPaginateTypeDef = TypedDict(
+    "ListServicesRequestListServicesPaginateTypeDef",
+    {
+        "cluster": str,
+        "launchType": LaunchTypeType,
+        "schedulingStrategy": SchedulingStrategyType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListServicesRequestRequestTypeDef = TypedDict(
     "ListServicesRequestRequestTypeDef",
     {
         "cluster": str,
         "nextToken": str,
         "maxResults": int,
         "launchType": LaunchTypeType,
         "schedulingStrategy": SchedulingStrategyType,
     },
     total=False,
 )
 
+ListServicesResponseTypeDef = TypedDict(
+    "ListServicesResponseTypeDef",
+    {
+        "serviceArns": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
+ListTaskDefinitionFamiliesRequestListTaskDefinitionFamiliesPaginateTypeDef = TypedDict(
+    "ListTaskDefinitionFamiliesRequestListTaskDefinitionFamiliesPaginateTypeDef",
+    {
+        "familyPrefix": str,
+        "status": TaskDefinitionFamilyStatusType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListTaskDefinitionFamiliesRequestRequestTypeDef = TypedDict(
     "ListTaskDefinitionFamiliesRequestRequestTypeDef",
     {
         "familyPrefix": str,
         "status": TaskDefinitionFamilyStatusType,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListTaskDefinitionFamiliesResponseTypeDef = TypedDict(
+    "ListTaskDefinitionFamiliesResponseTypeDef",
+    {
+        "families": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListTaskDefinitionsRequestListTaskDefinitionsPaginateTypeDef = TypedDict(
+    "ListTaskDefinitionsRequestListTaskDefinitionsPaginateTypeDef",
+    {
+        "familyPrefix": str,
+        "status": TaskDefinitionStatusType,
+        "sort": SortOrderType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListTaskDefinitionsRequestRequestTypeDef = TypedDict(
     "ListTaskDefinitionsRequestRequestTypeDef",
     {
         "familyPrefix": str,
         "status": TaskDefinitionStatusType,
         "sort": SortOrderType,
         "nextToken": str,
         "maxResults": int,
     },
     total=False,
 )
 
+ListTaskDefinitionsResponseTypeDef = TypedDict(
+    "ListTaskDefinitionsResponseTypeDef",
+    {
+        "taskDefinitionArns": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListTasksRequestListTasksPaginateTypeDef = TypedDict(
+    "ListTasksRequestListTasksPaginateTypeDef",
+    {
+        "cluster": str,
+        "containerInstance": str,
+        "family": str,
+        "startedBy": str,
+        "serviceName": str,
+        "desiredStatus": DesiredStatusType,
+        "launchType": LaunchTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListTasksRequestRequestTypeDef = TypedDict(
     "ListTasksRequestRequestTypeDef",
     {
         "cluster": str,
         "containerInstance": str,
         "family": str,
         "nextToken": str,
@@ -1288,14 +1461,23 @@
         "serviceName": str,
         "desiredStatus": DesiredStatusType,
         "launchType": LaunchTypeType,
     },
     total=False,
 )
 
+ListTasksResponseTypeDef = TypedDict(
+    "ListTasksResponseTypeDef",
+    {
+        "taskArns": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredManagedAgentStateChangeTypeDef = TypedDict(
     "_RequiredManagedAgentStateChangeTypeDef",
     {
         "containerName": str,
         "managedAgentName": Literal["ExecuteCommandAgent"],
         "status": str,
     },
@@ -1309,14 +1491,24 @@
 )
 
 class ManagedAgentStateChangeTypeDef(
     _RequiredManagedAgentStateChangeTypeDef, _OptionalManagedAgentStateChangeTypeDef
 ):
     pass
 
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
 PlatformDeviceTypeDef = TypedDict(
     "PlatformDeviceTypeDef",
     {
         "id": str,
         "type": Literal["GPU"],
     },
 )
@@ -1363,14 +1555,25 @@
     {
         "type": Literal["memberOf"],
         "expression": str,
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
 _RequiredServiceConnectClientAliasTypeDef = TypedDict(
     "_RequiredServiceConnectClientAliasTypeDef",
     {
         "port": int,
     },
 )
 _OptionalServiceConnectClientAliasTypeDef = TypedDict(
@@ -1412,14 +1615,38 @@
 )
 
 class StopTaskRequestRequestTypeDef(
     _RequiredStopTaskRequestRequestTypeDef, _OptionalStopTaskRequestRequestTypeDef
 ):
     pass
 
+SubmitAttachmentStateChangesResponseTypeDef = TypedDict(
+    "SubmitAttachmentStateChangesResponseTypeDef",
+    {
+        "acknowledgment": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+SubmitContainerStateChangeResponseTypeDef = TypedDict(
+    "SubmitContainerStateChangeResponseTypeDef",
+    {
+        "acknowledgment": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+SubmitTaskStateChangeResponseTypeDef = TypedDict(
+    "SubmitTaskStateChangeResponseTypeDef",
+    {
+        "acknowledgment": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tagKeys": Sequence[str],
     },
 )
@@ -1562,14 +1789,31 @@
 )
 
 class DeleteAttributesRequestRequestTypeDef(
     _RequiredDeleteAttributesRequestRequestTypeDef, _OptionalDeleteAttributesRequestRequestTypeDef
 ):
     pass
 
+DeleteAttributesResponseTypeDef = TypedDict(
+    "DeleteAttributesResponseTypeDef",
+    {
+        "attributes": List[AttributeTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListAttributesResponseTypeDef = TypedDict(
+    "ListAttributesResponseTypeDef",
+    {
+        "attributes": List[AttributeTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredPutAttributesRequestRequestTypeDef = TypedDict(
     "_RequiredPutAttributesRequestRequestTypeDef",
     {
         "attributes": Sequence[AttributeTypeDef],
     },
 )
 _OptionalPutAttributesRequestRequestTypeDef = TypedDict(
@@ -1581,14 +1825,22 @@
 )
 
 class PutAttributesRequestRequestTypeDef(
     _RequiredPutAttributesRequestRequestTypeDef, _OptionalPutAttributesRequestRequestTypeDef
 ):
     pass
 
+PutAttributesResponseTypeDef = TypedDict(
+    "PutAttributesResponseTypeDef",
+    {
+        "attributes": List[AttributeTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredAutoScalingGroupProviderTypeDef = TypedDict(
     "_RequiredAutoScalingGroupProviderTypeDef",
     {
         "autoScalingGroupArn": str,
     },
 )
 _OptionalAutoScalingGroupProviderTypeDef = TypedDict(
@@ -1627,14 +1879,22 @@
     {
         "cluster": str,
         "capacityProviders": Sequence[str],
         "defaultCapacityProviderStrategy": Sequence[CapacityProviderStrategyItemTypeDef],
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "tags": List[TagTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
         "tags": Sequence[TagTypeDef],
     },
 )
@@ -1738,184 +1998,54 @@
         "memory": str,
         "memoryReservation": str,
         "gpuIds": List[str],
     },
     total=False,
 )
 
-DeleteAttributesResponseTypeDef = TypedDict(
-    "DeleteAttributesResponseTypeDef",
-    {
-        "attributes": List[AttributeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DiscoverPollEndpointResponseTypeDef = TypedDict(
-    "DiscoverPollEndpointResponseTypeDef",
-    {
-        "endpoint": str,
-        "telemetryEndpoint": str,
-        "serviceConnectEndpoint": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListAttributesResponseTypeDef = TypedDict(
-    "ListAttributesResponseTypeDef",
-    {
-        "attributes": List[AttributeTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListClustersResponseTypeDef = TypedDict(
-    "ListClustersResponseTypeDef",
-    {
-        "clusterArns": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListContainerInstancesResponseTypeDef = TypedDict(
-    "ListContainerInstancesResponseTypeDef",
-    {
-        "containerInstanceArns": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListServicesByNamespaceResponseTypeDef = TypedDict(
-    "ListServicesByNamespaceResponseTypeDef",
-    {
-        "serviceArns": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListServicesResponseTypeDef = TypedDict(
-    "ListServicesResponseTypeDef",
-    {
-        "serviceArns": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTaskDefinitionFamiliesResponseTypeDef = TypedDict(
-    "ListTaskDefinitionFamiliesResponseTypeDef",
-    {
-        "families": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTaskDefinitionsResponseTypeDef = TypedDict(
-    "ListTaskDefinitionsResponseTypeDef",
-    {
-        "taskDefinitionArns": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTasksResponseTypeDef = TypedDict(
-    "ListTasksResponseTypeDef",
-    {
-        "taskArns": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutAttributesResponseTypeDef = TypedDict(
-    "PutAttributesResponseTypeDef",
-    {
-        "attributes": List[AttributeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SubmitAttachmentStateChangesResponseTypeDef = TypedDict(
-    "SubmitAttachmentStateChangesResponseTypeDef",
-    {
-        "acknowledgment": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SubmitContainerStateChangeResponseTypeDef = TypedDict(
-    "SubmitContainerStateChangeResponseTypeDef",
-    {
-        "acknowledgment": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SubmitTaskStateChangeResponseTypeDef = TypedDict(
-    "SubmitTaskStateChangeResponseTypeDef",
-    {
-        "acknowledgment": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 UpdateTaskSetRequestRequestTypeDef = TypedDict(
     "UpdateTaskSetRequestRequestTypeDef",
     {
         "cluster": str,
         "service": str,
         "taskSet": str,
         "scale": ScaleTypeDef,
     },
 )
 
 DeleteAccountSettingResponseTypeDef = TypedDict(
     "DeleteAccountSettingResponseTypeDef",
     {
         "setting": SettingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAccountSettingsResponseTypeDef = TypedDict(
     "ListAccountSettingsResponseTypeDef",
     {
         "settings": List[SettingTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutAccountSettingDefaultResponseTypeDef = TypedDict(
     "PutAccountSettingDefaultResponseTypeDef",
     {
         "setting": SettingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutAccountSettingResponseTypeDef = TypedDict(
     "PutAccountSettingResponseTypeDef",
     {
         "setting": SettingTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeploymentConfigurationTypeDef = TypedDict(
     "DeploymentConfigurationTypeDef",
     {
         "deploymentCircuitBreaker": DeploymentCircuitBreakerTypeDef,
@@ -2051,15 +2181,15 @@
     {
         "clusterArn": str,
         "containerArn": str,
         "containerName": str,
         "interactive": bool,
         "session": SessionTypeDef,
         "taskArn": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 FSxWindowsFileServerVolumeConfigurationTypeDef = TypedDict(
     "FSxWindowsFileServerVolumeConfigurationTypeDef",
     {
         "fileSystemId": str,
@@ -2069,24 +2199,24 @@
 )
 
 GetTaskProtectionResponseTypeDef = TypedDict(
     "GetTaskProtectionResponseTypeDef",
     {
         "protectedTasks": List[ProtectedTaskTypeDef],
         "failures": List[FailureTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateTaskProtectionResponseTypeDef = TypedDict(
     "UpdateTaskProtectionResponseTypeDef",
     {
         "protectedTasks": List[ProtectedTaskTypeDef],
         "failures": List[FailureTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LinuxParametersTypeDef = TypedDict(
     "LinuxParametersTypeDef",
     {
         "capabilities": KernelCapabilitiesTypeDef,
@@ -2096,135 +2226,14 @@
         "tmpfs": List[TmpfsTypeDef],
         "maxSwap": int,
         "swappiness": int,
     },
     total=False,
 )
 
-ListAccountSettingsRequestListAccountSettingsPaginateTypeDef = TypedDict(
-    "ListAccountSettingsRequestListAccountSettingsPaginateTypeDef",
-    {
-        "name": SettingNameType,
-        "value": str,
-        "principalArn": str,
-        "effectiveSettings": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListAttributesRequestListAttributesPaginateTypeDef = TypedDict(
-    "_RequiredListAttributesRequestListAttributesPaginateTypeDef",
-    {
-        "targetType": Literal["container-instance"],
-    },
-)
-_OptionalListAttributesRequestListAttributesPaginateTypeDef = TypedDict(
-    "_OptionalListAttributesRequestListAttributesPaginateTypeDef",
-    {
-        "cluster": str,
-        "attributeName": str,
-        "attributeValue": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListAttributesRequestListAttributesPaginateTypeDef(
-    _RequiredListAttributesRequestListAttributesPaginateTypeDef,
-    _OptionalListAttributesRequestListAttributesPaginateTypeDef,
-):
-    pass
-
-ListClustersRequestListClustersPaginateTypeDef = TypedDict(
-    "ListClustersRequestListClustersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListContainerInstancesRequestListContainerInstancesPaginateTypeDef = TypedDict(
-    "ListContainerInstancesRequestListContainerInstancesPaginateTypeDef",
-    {
-        "cluster": str,
-        "filter": str,
-        "status": ContainerInstanceStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListServicesByNamespaceRequestListServicesByNamespacePaginateTypeDef = TypedDict(
-    "_RequiredListServicesByNamespaceRequestListServicesByNamespacePaginateTypeDef",
-    {
-        "namespace": str,
-    },
-)
-_OptionalListServicesByNamespaceRequestListServicesByNamespacePaginateTypeDef = TypedDict(
-    "_OptionalListServicesByNamespaceRequestListServicesByNamespacePaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListServicesByNamespaceRequestListServicesByNamespacePaginateTypeDef(
-    _RequiredListServicesByNamespaceRequestListServicesByNamespacePaginateTypeDef,
-    _OptionalListServicesByNamespaceRequestListServicesByNamespacePaginateTypeDef,
-):
-    pass
-
-ListServicesRequestListServicesPaginateTypeDef = TypedDict(
-    "ListServicesRequestListServicesPaginateTypeDef",
-    {
-        "cluster": str,
-        "launchType": LaunchTypeType,
-        "schedulingStrategy": SchedulingStrategyType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListTaskDefinitionFamiliesRequestListTaskDefinitionFamiliesPaginateTypeDef = TypedDict(
-    "ListTaskDefinitionFamiliesRequestListTaskDefinitionFamiliesPaginateTypeDef",
-    {
-        "familyPrefix": str,
-        "status": TaskDefinitionFamilyStatusType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListTaskDefinitionsRequestListTaskDefinitionsPaginateTypeDef = TypedDict(
-    "ListTaskDefinitionsRequestListTaskDefinitionsPaginateTypeDef",
-    {
-        "familyPrefix": str,
-        "status": TaskDefinitionStatusType,
-        "sort": SortOrderType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListTasksRequestListTasksPaginateTypeDef = TypedDict(
-    "ListTasksRequestListTasksPaginateTypeDef",
-    {
-        "cluster": str,
-        "containerInstance": str,
-        "family": str,
-        "startedBy": str,
-        "serviceName": str,
-        "desiredStatus": DesiredStatusType,
-        "launchType": LaunchTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 RegisterContainerInstanceRequestRequestTypeDef = TypedDict(
     "RegisterContainerInstanceRequestRequestTypeDef",
     {
         "cluster": str,
         "instanceIdentityDocument": str,
         "instanceIdentityDocumentSignature": str,
         "totalResources": Sequence[ResourceTypeDef],
@@ -2505,82 +2514,82 @@
 ):
     pass
 
 CreateCapacityProviderResponseTypeDef = TypedDict(
     "CreateCapacityProviderResponseTypeDef",
     {
         "capacityProvider": CapacityProviderTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteCapacityProviderResponseTypeDef = TypedDict(
     "DeleteCapacityProviderResponseTypeDef",
     {
         "capacityProvider": CapacityProviderTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeCapacityProvidersResponseTypeDef = TypedDict(
     "DescribeCapacityProvidersResponseTypeDef",
     {
         "capacityProviders": List[CapacityProviderTypeDef],
         "failures": List[FailureTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateCapacityProviderResponseTypeDef = TypedDict(
     "UpdateCapacityProviderResponseTypeDef",
     {
         "capacityProvider": CapacityProviderTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateTaskSetResponseTypeDef = TypedDict(
     "CreateTaskSetResponseTypeDef",
     {
         "taskSet": TaskSetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteTaskSetResponseTypeDef = TypedDict(
     "DeleteTaskSetResponseTypeDef",
     {
         "taskSet": TaskSetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeTaskSetsResponseTypeDef = TypedDict(
     "DescribeTaskSetsResponseTypeDef",
     {
         "taskSets": List[TaskSetTypeDef],
         "failures": List[FailureTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateServicePrimaryTaskSetResponseTypeDef = TypedDict(
     "UpdateServicePrimaryTaskSetResponseTypeDef",
     {
         "taskSet": TaskSetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateTaskSetResponseTypeDef = TypedDict(
     "UpdateTaskSetResponseTypeDef",
     {
         "taskSet": TaskSetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredRunTaskRequestRequestTypeDef = TypedDict(
     "_RequiredRunTaskRequestRequestTypeDef",
     {
         "taskDefinition": str,
@@ -2686,49 +2695,49 @@
     total=False,
 )
 
 DeregisterContainerInstanceResponseTypeDef = TypedDict(
     "DeregisterContainerInstanceResponseTypeDef",
     {
         "containerInstance": ContainerInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeContainerInstancesResponseTypeDef = TypedDict(
     "DescribeContainerInstancesResponseTypeDef",
     {
         "containerInstances": List[ContainerInstanceTypeDef],
         "failures": List[FailureTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RegisterContainerInstanceResponseTypeDef = TypedDict(
     "RegisterContainerInstanceResponseTypeDef",
     {
         "containerInstance": ContainerInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateContainerAgentResponseTypeDef = TypedDict(
     "UpdateContainerAgentResponseTypeDef",
     {
         "containerInstance": ContainerInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateContainerInstancesStateResponseTypeDef = TypedDict(
     "UpdateContainerInstancesStateResponseTypeDef",
     {
         "containerInstances": List[ContainerInstanceTypeDef],
         "failures": List[FailureTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ClusterTypeDef = TypedDict(
     "ClusterTypeDef",
     {
         "clusterArn": str,
@@ -2953,116 +2962,125 @@
     pass
 
 DescribeTasksResponseTypeDef = TypedDict(
     "DescribeTasksResponseTypeDef",
     {
         "tasks": List[TaskTypeDef],
         "failures": List[FailureTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RunTaskResponseTypeDef = TypedDict(
     "RunTaskResponseTypeDef",
     {
         "tasks": List[TaskTypeDef],
         "failures": List[FailureTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartTaskResponseTypeDef = TypedDict(
     "StartTaskResponseTypeDef",
     {
         "tasks": List[TaskTypeDef],
         "failures": List[FailureTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopTaskResponseTypeDef = TypedDict(
     "StopTaskResponseTypeDef",
     {
         "task": TaskTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateClusterResponseTypeDef = TypedDict(
     "CreateClusterResponseTypeDef",
     {
         "cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteClusterResponseTypeDef = TypedDict(
     "DeleteClusterResponseTypeDef",
     {
         "cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeClustersResponseTypeDef = TypedDict(
     "DescribeClustersResponseTypeDef",
     {
         "clusters": List[ClusterTypeDef],
         "failures": List[FailureTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PutClusterCapacityProvidersResponseTypeDef = TypedDict(
     "PutClusterCapacityProvidersResponseTypeDef",
     {
         "cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateClusterResponseTypeDef = TypedDict(
     "UpdateClusterResponseTypeDef",
     {
         "cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateClusterSettingsResponseTypeDef = TypedDict(
     "UpdateClusterSettingsResponseTypeDef",
     {
         "cluster": ClusterTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DeleteTaskDefinitionsResponseTypeDef = TypedDict(
+    "DeleteTaskDefinitionsResponseTypeDef",
+    {
+        "taskDefinitions": List[TaskDefinitionTypeDef],
+        "failures": List[FailureTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeregisterTaskDefinitionResponseTypeDef = TypedDict(
     "DeregisterTaskDefinitionResponseTypeDef",
     {
         "taskDefinition": TaskDefinitionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeTaskDefinitionResponseTypeDef = TypedDict(
     "DescribeTaskDefinitionResponseTypeDef",
     {
         "taskDefinition": TaskDefinitionTypeDef,
         "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RegisterTaskDefinitionResponseTypeDef = TypedDict(
     "RegisterTaskDefinitionResponseTypeDef",
     {
         "taskDefinition": TaskDefinitionTypeDef,
         "tags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ServiceTypeDef = TypedDict(
     "ServiceTypeDef",
     {
         "serviceArn": str,
@@ -3100,35 +3118,35 @@
     total=False,
 )
 
 CreateServiceResponseTypeDef = TypedDict(
     "CreateServiceResponseTypeDef",
     {
         "service": ServiceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteServiceResponseTypeDef = TypedDict(
     "DeleteServiceResponseTypeDef",
     {
         "service": ServiceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeServicesResponseTypeDef = TypedDict(
     "DescribeServicesResponseTypeDef",
     {
         "services": List[ServiceTypeDef],
         "failures": List[FailureTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateServiceResponseTypeDef = TypedDict(
     "UpdateServiceResponseTypeDef",
     {
         "service": ServiceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-ecs-2.5.0.post1/types_aiobotocore_ecs/waiter.py` & `types-aiobotocore-ecs-2.5.1/types_aiobotocore_ecs/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ecs-2.5.0.post1/types_aiobotocore_ecs/waiter.pyi` & `types-aiobotocore-ecs-2.5.1/types_aiobotocore_ecs/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-ecs-2.5.0.post1/types_aiobotocore_ecs.egg-info/PKG-INFO` & `types-aiobotocore-ecs-2.5.1/types_aiobotocore_ecs.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-ecs
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ECS 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ECS 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-ecs"></a>
 
 # types-aiobotocore-ecs
 
 [![PyPI - types-aiobotocore-ecs](https://img.shields.io/pypi/v/types-aiobotocore-ecs.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ecs)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-ecs.svg?color=blue)](https://pypi.org/project/types-aiobotocore-ecs)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-ecs?color=blue)](https://pypistats.org/packages/types-aiobotocore-ecs)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ECS 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS)
+[aiobotocore.ECS 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/ecs.html#ECS)
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
 [types-aiobotocore-ecs docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ecs/).
 
 See how it helps to find and fix potential bugs:
 
@@ -471,114 +471,124 @@
     VolumeFromTypeDef,
     InstanceHealthCheckResultTypeDef,
     ResourceTypeDef,
     VersionInfoTypeDef,
     NetworkBindingTypeDef,
     ManagedAgentTypeDef,
     NetworkInterfaceTypeDef,
-    ResponseMetadataTypeDef,
     DeploymentControllerTypeDef,
     LoadBalancerTypeDef,
     PlacementConstraintTypeDef,
     PlacementStrategyTypeDef,
     ServiceRegistryTypeDef,
     ScaleTypeDef,
     DeleteAccountSettingRequestRequestTypeDef,
     SettingTypeDef,
     DeleteCapacityProviderRequestRequestTypeDef,
     DeleteClusterRequestRequestTypeDef,
     DeleteServiceRequestRequestTypeDef,
+    DeleteTaskDefinitionsRequestRequestTypeDef,
+    FailureTypeDef,
     DeleteTaskSetRequestRequestTypeDef,
     DeploymentAlarmsTypeDef,
     DeploymentCircuitBreakerTypeDef,
     ServiceConnectServiceResourceTypeDef,
     DeregisterContainerInstanceRequestRequestTypeDef,
     DeregisterTaskDefinitionRequestRequestTypeDef,
     DescribeCapacityProvidersRequestRequestTypeDef,
-    FailureTypeDef,
     DescribeClustersRequestRequestTypeDef,
     DescribeContainerInstancesRequestRequestTypeDef,
     DescribeServicesRequestRequestTypeDef,
     WaiterConfigTypeDef,
     DescribeTaskDefinitionRequestRequestTypeDef,
     DescribeTaskSetsRequestRequestTypeDef,
     DescribeTasksRequestRequestTypeDef,
     DeviceTypeDef,
     DiscoverPollEndpointRequestRequestTypeDef,
+    DiscoverPollEndpointResponseTypeDef,
     DockerVolumeConfigurationTypeDef,
     EFSAuthorizationConfigTypeDef,
     EphemeralStorageTypeDef,
     ExecuteCommandLogConfigurationTypeDef,
     ExecuteCommandRequestRequestTypeDef,
     SessionTypeDef,
     FSxWindowsFileServerAuthorizationConfigTypeDef,
     GetTaskProtectionRequestRequestTypeDef,
     ProtectedTaskTypeDef,
     HostVolumePropertiesTypeDef,
     InferenceAcceleratorOverrideTypeDef,
     InferenceAcceleratorTypeDef,
     KernelCapabilitiesTypeDef,
     TmpfsTypeDef,
-    PaginatorConfigTypeDef,
+    ListAccountSettingsRequestListAccountSettingsPaginateTypeDef,
     ListAccountSettingsRequestRequestTypeDef,
+    ListAttributesRequestListAttributesPaginateTypeDef,
     ListAttributesRequestRequestTypeDef,
+    ListClustersRequestListClustersPaginateTypeDef,
     ListClustersRequestRequestTypeDef,
+    ListClustersResponseTypeDef,
+    ListContainerInstancesRequestListContainerInstancesPaginateTypeDef,
     ListContainerInstancesRequestRequestTypeDef,
+    ListContainerInstancesResponseTypeDef,
+    ListServicesByNamespaceRequestListServicesByNamespacePaginateTypeDef,
     ListServicesByNamespaceRequestRequestTypeDef,
+    ListServicesByNamespaceResponseTypeDef,
+    ListServicesRequestListServicesPaginateTypeDef,
     ListServicesRequestRequestTypeDef,
+    ListServicesResponseTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTaskDefinitionFamiliesRequestListTaskDefinitionFamiliesPaginateTypeDef,
     ListTaskDefinitionFamiliesRequestRequestTypeDef,
+    ListTaskDefinitionFamiliesResponseTypeDef,
+    ListTaskDefinitionsRequestListTaskDefinitionsPaginateTypeDef,
     ListTaskDefinitionsRequestRequestTypeDef,
+    ListTaskDefinitionsResponseTypeDef,
+    ListTasksRequestListTasksPaginateTypeDef,
     ListTasksRequestRequestTypeDef,
+    ListTasksResponseTypeDef,
     ManagedAgentStateChangeTypeDef,
+    PaginatorConfigTypeDef,
     PlatformDeviceTypeDef,
     PutAccountSettingDefaultRequestRequestTypeDef,
     PutAccountSettingRequestRequestTypeDef,
     RuntimePlatformTypeDef,
     TaskDefinitionPlacementConstraintTypeDef,
+    ResponseMetadataTypeDef,
     ServiceConnectClientAliasTypeDef,
     ServiceEventTypeDef,
     StopTaskRequestRequestTypeDef,
+    SubmitAttachmentStateChangesResponseTypeDef,
+    SubmitContainerStateChangeResponseTypeDef,
+    SubmitTaskStateChangeResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateContainerAgentRequestRequestTypeDef,
     UpdateContainerInstancesStateRequestRequestTypeDef,
     UpdateServicePrimaryTaskSetRequestRequestTypeDef,
     UpdateTaskProtectionRequestRequestTypeDef,
     SubmitAttachmentStateChangesRequestRequestTypeDef,
     AttachmentTypeDef,
     ProxyConfigurationTypeDef,
     DeleteAttributesRequestRequestTypeDef,
+    DeleteAttributesResponseTypeDef,
+    ListAttributesResponseTypeDef,
     PutAttributesRequestRequestTypeDef,
+    PutAttributesResponseTypeDef,
     AutoScalingGroupProviderTypeDef,
     AutoScalingGroupProviderUpdateTypeDef,
     NetworkConfigurationTypeDef,
     PutClusterCapacityProvidersRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UpdateClusterSettingsRequestRequestTypeDef,
     ContainerOverrideTypeDef,
     LogConfigurationTypeDef,
     ContainerInstanceHealthStatusTypeDef,
     ContainerStateChangeTypeDef,
     SubmitContainerStateChangeRequestRequestTypeDef,
     ContainerTypeDef,
-    DeleteAttributesResponseTypeDef,
-    DiscoverPollEndpointResponseTypeDef,
-    ListAttributesResponseTypeDef,
-    ListClustersResponseTypeDef,
-    ListContainerInstancesResponseTypeDef,
-    ListServicesByNamespaceResponseTypeDef,
-    ListServicesResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    ListTaskDefinitionFamiliesResponseTypeDef,
-    ListTaskDefinitionsResponseTypeDef,
-    ListTasksResponseTypeDef,
-    PutAttributesResponseTypeDef,
-    SubmitAttachmentStateChangesResponseTypeDef,
-    SubmitContainerStateChangeResponseTypeDef,
-    SubmitTaskStateChangeResponseTypeDef,
     UpdateTaskSetRequestRequestTypeDef,
     DeleteAccountSettingResponseTypeDef,
     ListAccountSettingsResponseTypeDef,
     PutAccountSettingDefaultResponseTypeDef,
     PutAccountSettingResponseTypeDef,
     DeploymentConfigurationTypeDef,
     DescribeServicesRequestServicesInactiveWaitTypeDef,
@@ -588,23 +598,14 @@
     EFSVolumeConfigurationTypeDef,
     ExecuteCommandConfigurationTypeDef,
     ExecuteCommandResponseTypeDef,
     FSxWindowsFileServerVolumeConfigurationTypeDef,
     GetTaskProtectionResponseTypeDef,
     UpdateTaskProtectionResponseTypeDef,
     LinuxParametersTypeDef,
-    ListAccountSettingsRequestListAccountSettingsPaginateTypeDef,
-    ListAttributesRequestListAttributesPaginateTypeDef,
-    ListClustersRequestListClustersPaginateTypeDef,
-    ListContainerInstancesRequestListContainerInstancesPaginateTypeDef,
-    ListServicesByNamespaceRequestListServicesByNamespacePaginateTypeDef,
-    ListServicesRequestListServicesPaginateTypeDef,
-    ListTaskDefinitionFamiliesRequestListTaskDefinitionFamiliesPaginateTypeDef,
-    ListTaskDefinitionsRequestListTaskDefinitionsPaginateTypeDef,
-    ListTasksRequestListTasksPaginateTypeDef,
     RegisterContainerInstanceRequestRequestTypeDef,
     ServiceConnectServiceTypeDef,
     CapacityProviderTypeDef,
     CreateCapacityProviderRequestRequestTypeDef,
     UpdateCapacityProviderRequestRequestTypeDef,
     CreateTaskSetRequestRequestTypeDef,
     TaskSetTypeDef,
@@ -646,14 +647,15 @@
     StopTaskResponseTypeDef,
     CreateClusterResponseTypeDef,
     DeleteClusterResponseTypeDef,
     DescribeClustersResponseTypeDef,
     PutClusterCapacityProvidersResponseTypeDef,
     UpdateClusterResponseTypeDef,
     UpdateClusterSettingsResponseTypeDef,
+    DeleteTaskDefinitionsResponseTypeDef,
     DeregisterTaskDefinitionResponseTypeDef,
     DescribeTaskDefinitionResponseTypeDef,
     RegisterTaskDefinitionResponseTypeDef,
     ServiceTypeDef,
     CreateServiceResponseTypeDef,
     DeleteServiceResponseTypeDef,
     DescribeServicesResponseTypeDef,
@@ -668,43 +670,43 @@
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

### Comparing `types-aiobotocore-ecs-2.5.0.post1/types_aiobotocore_ecs.egg-info/SOURCES.txt` & `types-aiobotocore-ecs-2.5.1/types_aiobotocore_ecs.egg-info/SOURCES.txt`

 * *Files identical despite different names*

