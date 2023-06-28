# Comparing `tmp/types-aiobotocore-autoscaling-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-autoscaling-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-autoscaling-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:15 2023, max compression
+gzip compressed data, was "types-aiobotocore-autoscaling-2.5.1.tar", last modified: Wed Jun 28 01:43:08 2023, max compression
```

## Comparing `types-aiobotocore-autoscaling-2.5.0.post1.tar` & `types-aiobotocore-autoscaling-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:15.066972 types-aiobotocore-autoscaling-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:09:58.000000 types-aiobotocore-autoscaling-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    23154 2023-03-11 12:26:15.058972 types-aiobotocore-autoscaling-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    21567 2023-03-11 12:09:58.000000 types-aiobotocore-autoscaling-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:15.066972 types-aiobotocore-autoscaling-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2152 2023-03-11 12:09:58.000000 types-aiobotocore-autoscaling-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:15.058972 types-aiobotocore-autoscaling-2.5.0.post1/types_aiobotocore_autoscaling/
--rw-r--r--   0 runner    (1001) docker     (123)     3067 2023-03-11 12:09:58.000000 types-aiobotocore-autoscaling-2.5.0.post1/types_aiobotocore_autoscaling/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3066 2023-03-11 12:09:58.000000 types-aiobotocore-autoscaling-2.5.0.post1/types_aiobotocore_autoscaling/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      959 2023-03-11 12:09:58.000000 types-aiobotocore-autoscaling-2.5.0.post1/types_aiobotocore_autoscaling/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    55695 2023-03-11 12:09:58.000000 types-aiobotocore-autoscaling-2.5.0.post1/types_aiobotocore_autoscaling/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    55611 2023-03-11 12:09:58.000000 types-aiobotocore-autoscaling-2.5.0.post1/types_aiobotocore_autoscaling/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    13367 2023-03-11 12:09:59.000000 types-aiobotocore-autoscaling-2.5.0.post1/types_aiobotocore_autoscaling/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    13365 2023-03-11 12:09:59.000000 types-aiobotocore-autoscaling-2.5.0.post1/types_aiobotocore_autoscaling/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    13961 2023-03-11 12:09:59.000000 types-aiobotocore-autoscaling-2.5.0.post1/types_aiobotocore_autoscaling/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    13948 2023-03-11 12:09:59.000000 types-aiobotocore-autoscaling-2.5.0.post1/types_aiobotocore_autoscaling/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:09:58.000000 types-aiobotocore-autoscaling-2.5.0.post1/types_aiobotocore_autoscaling/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    75001 2023-03-11 12:10:01.000000 types-aiobotocore-autoscaling-2.5.0.post1/types_aiobotocore_autoscaling/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    74886 2023-03-11 12:10:00.000000 types-aiobotocore-autoscaling-2.5.0.post1/types_aiobotocore_autoscaling/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:09:58.000000 types-aiobotocore-autoscaling-2.5.0.post1/types_aiobotocore_autoscaling/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:15.058972 types-aiobotocore-autoscaling-2.5.0.post1/types_aiobotocore_autoscaling.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    23154 2023-03-11 12:26:14.000000 types-aiobotocore-autoscaling-2.5.0.post1/types_aiobotocore_autoscaling.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      889 2023-03-11 12:26:14.000000 types-aiobotocore-autoscaling-2.5.0.post1/types_aiobotocore_autoscaling.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:14.000000 types-aiobotocore-autoscaling-2.5.0.post1/types_aiobotocore_autoscaling.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:14.000000 types-aiobotocore-autoscaling-2.5.0.post1/types_aiobotocore_autoscaling.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:14.000000 types-aiobotocore-autoscaling-2.5.0.post1/types_aiobotocore_autoscaling.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       30 2023-03-11 12:26:14.000000 types-aiobotocore-autoscaling-2.5.0.post1/types_aiobotocore_autoscaling.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:08.714098 types-aiobotocore-autoscaling-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:26:35.000000 types-aiobotocore-autoscaling-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    23150 2023-06-28 01:43:08.714098 types-aiobotocore-autoscaling-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    21569 2023-06-28 01:26:35.000000 types-aiobotocore-autoscaling-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:08.714098 types-aiobotocore-autoscaling-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2146 2023-06-28 01:26:35.000000 types-aiobotocore-autoscaling-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:08.710098 types-aiobotocore-autoscaling-2.5.1/types_aiobotocore_autoscaling/
+-rw-r--r--   0 runner    (1001) docker     (123)     3067 2023-06-28 01:26:35.000000 types-aiobotocore-autoscaling-2.5.1/types_aiobotocore_autoscaling/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3066 2023-06-28 01:26:35.000000 types-aiobotocore-autoscaling-2.5.1/types_aiobotocore_autoscaling/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      947 2023-06-28 01:26:35.000000 types-aiobotocore-autoscaling-2.5.1/types_aiobotocore_autoscaling/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    55230 2023-06-28 01:26:35.000000 types-aiobotocore-autoscaling-2.5.1/types_aiobotocore_autoscaling/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    55146 2023-06-28 01:26:35.000000 types-aiobotocore-autoscaling-2.5.1/types_aiobotocore_autoscaling/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    13612 2023-06-28 01:26:35.000000 types-aiobotocore-autoscaling-2.5.1/types_aiobotocore_autoscaling/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13610 2023-06-28 01:26:35.000000 types-aiobotocore-autoscaling-2.5.1/types_aiobotocore_autoscaling/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    13861 2023-06-28 01:26:35.000000 types-aiobotocore-autoscaling-2.5.1/types_aiobotocore_autoscaling/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13849 2023-06-28 01:26:35.000000 types-aiobotocore-autoscaling-2.5.1/types_aiobotocore_autoscaling/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:26:35.000000 types-aiobotocore-autoscaling-2.5.1/types_aiobotocore_autoscaling/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    75427 2023-06-28 01:26:37.000000 types-aiobotocore-autoscaling-2.5.1/types_aiobotocore_autoscaling/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    75310 2023-06-28 01:26:37.000000 types-aiobotocore-autoscaling-2.5.1/types_aiobotocore_autoscaling/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:26:35.000000 types-aiobotocore-autoscaling-2.5.1/types_aiobotocore_autoscaling/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:08.714098 types-aiobotocore-autoscaling-2.5.1/types_aiobotocore_autoscaling.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    23150 2023-06-28 01:43:08.000000 types-aiobotocore-autoscaling-2.5.1/types_aiobotocore_autoscaling.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      889 2023-06-28 01:43:08.000000 types-aiobotocore-autoscaling-2.5.1/types_aiobotocore_autoscaling.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:08.000000 types-aiobotocore-autoscaling-2.5.1/types_aiobotocore_autoscaling.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:08.000000 types-aiobotocore-autoscaling-2.5.1/types_aiobotocore_autoscaling.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:08.000000 types-aiobotocore-autoscaling-2.5.1/types_aiobotocore_autoscaling.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       30 2023-06-28 01:43:08.000000 types-aiobotocore-autoscaling-2.5.1/types_aiobotocore_autoscaling.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-autoscaling-2.5.0.post1/LICENSE` & `types-aiobotocore-autoscaling-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-autoscaling-2.5.0.post1/PKG-INFO` & `types-aiobotocore-autoscaling-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-autoscaling
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.AutoScaling 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.AutoScaling 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-autoscaling"></a>
 
 # types-aiobotocore-autoscaling
 
 [![PyPI - types-aiobotocore-autoscaling](https://img.shields.io/pypi/v/types-aiobotocore-autoscaling.svg?color=blue)](https://pypi.org/project/types-aiobotocore-autoscaling)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-autoscaling.svg?color=blue)](https://pypi.org/project/types-aiobotocore-autoscaling)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-autoscaling?color=blue)](https://pypistats.org/packages/types-aiobotocore-autoscaling)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.AutoScaling 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling)
+[aiobotocore.AutoScaling 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling)
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
 [types-aiobotocore-autoscaling docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/).
 
 See how it helps to find and fix potential bugs:
 
@@ -390,68 +390,79 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_autoscaling.type_defs import (
     AcceleratorCountRequestTypeDef,
     AcceleratorTotalMemoryMiBRequestTypeDef,
     ActivityTypeDef,
-    ResponseMetadataTypeDef,
     AdjustmentTypeTypeDef,
     AlarmTypeDef,
     AttachInstancesQueryRequestTypeDef,
     AttachLoadBalancerTargetGroupsTypeRequestTypeDef,
     AttachLoadBalancersTypeRequestTypeDef,
     TrafficSourceIdentifierTypeDef,
     FilterTypeDef,
-    PaginatorConfigTypeDef,
     EnabledMetricTypeDef,
     LaunchTemplateSpecificationTypeDef,
     SuspendedProcessTypeDef,
     TagDescriptionTypeDef,
     BaselineEbsBandwidthMbpsRequestTypeDef,
     FailedScheduledUpdateGroupActionRequestTypeDef,
     BatchDeleteScheduledActionTypeRequestTypeDef,
     ScheduledUpdateGroupActionRequestTypeDef,
     EbsTypeDef,
+    CancelInstanceRefreshAnswerTypeDef,
     CancelInstanceRefreshTypeRequestTypeDef,
     CapacityForecastTypeDef,
     CompleteLifecycleActionTypeRequestTypeDef,
     LifecycleHookSpecificationTypeDef,
     TagTypeDef,
     InstanceMetadataOptionsTypeDef,
     InstanceMonitoringTypeDef,
     MetricDimensionTypeDef,
     DeleteAutoScalingGroupTypeRequestTypeDef,
     DeleteLifecycleHookTypeRequestTypeDef,
     DeleteNotificationConfigurationTypeRequestTypeDef,
     DeletePolicyTypeRequestTypeDef,
     DeleteScheduledActionTypeRequestTypeDef,
     DeleteWarmPoolTypeRequestTypeDef,
+    DescribeAccountLimitsAnswerTypeDef,
+    DescribeAutoScalingInstancesTypeDescribeAutoScalingInstancesPaginateTypeDef,
     DescribeAutoScalingInstancesTypeRequestTypeDef,
+    DescribeAutoScalingNotificationTypesAnswerTypeDef,
     DescribeInstanceRefreshesTypeRequestTypeDef,
+    DescribeLifecycleHookTypesAnswerTypeDef,
     LifecycleHookTypeDef,
     DescribeLifecycleHooksTypeRequestTypeDef,
+    DescribeLoadBalancerTargetGroupsRequestDescribeLoadBalancerTargetGroupsPaginateTypeDef,
     DescribeLoadBalancerTargetGroupsRequestRequestTypeDef,
     LoadBalancerTargetGroupStateTypeDef,
+    DescribeLoadBalancersRequestDescribeLoadBalancersPaginateTypeDef,
     DescribeLoadBalancersRequestRequestTypeDef,
     LoadBalancerStateTypeDef,
     MetricCollectionTypeTypeDef,
     MetricGranularityTypeTypeDef,
     NotificationConfigurationTypeDef,
+    DescribeNotificationConfigurationsTypeDescribeNotificationConfigurationsPaginateTypeDef,
     DescribeNotificationConfigurationsTypeRequestTypeDef,
+    DescribePoliciesTypeDescribePoliciesPaginateTypeDef,
     DescribePoliciesTypeRequestTypeDef,
+    DescribeScalingActivitiesTypeDescribeScalingActivitiesPaginateTypeDef,
     DescribeScalingActivitiesTypeRequestTypeDef,
+    DescribeScheduledActionsTypeDescribeScheduledActionsPaginateTypeDef,
     DescribeScheduledActionsTypeRequestTypeDef,
+    DescribeTerminationPolicyTypesAnswerTypeDef,
     DescribeTrafficSourcesRequestRequestTypeDef,
     TrafficSourceStateTypeDef,
     DescribeWarmPoolTypeRequestTypeDef,
     DetachInstancesQueryRequestTypeDef,
     DetachLoadBalancerTargetGroupsTypeRequestTypeDef,
     DetachLoadBalancersTypeRequestTypeDef,
     DisableMetricsCollectionQueryRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EnableMetricsCollectionQueryRequestTypeDef,
     EnterStandbyQueryRequestTypeDef,
     ExecutePolicyTypeRequestTypeDef,
     ExitStandbyQueryRequestTypeDef,
     GetPredictiveScalingForecastTypeRequestTypeDef,
     InstanceRefreshLivePoolProgressTypeDef,
     InstanceRefreshWarmPoolProgressTypeDef,
@@ -461,61 +472,50 @@
     NetworkBandwidthGbpsRequestTypeDef,
     NetworkInterfaceCountRequestTypeDef,
     TotalLocalStorageGBRequestTypeDef,
     VCpuCountRequestTypeDef,
     InstanceReusePolicyTypeDef,
     InstancesDistributionTypeDef,
     LaunchConfigurationNameTypeRequestTypeDef,
+    LaunchConfigurationNamesTypeDescribeLaunchConfigurationsPaginateTypeDef,
     LaunchConfigurationNamesTypeRequestTypeDef,
+    PaginatorConfigTypeDef,
     PredefinedMetricSpecificationTypeDef,
     PredictiveScalingPredefinedLoadMetricTypeDef,
     PredictiveScalingPredefinedMetricPairTypeDef,
     PredictiveScalingPredefinedScalingMetricTypeDef,
     ProcessTypeTypeDef,
     PutLifecycleHookTypeRequestTypeDef,
     PutNotificationConfigurationTypeRequestTypeDef,
     StepAdjustmentTypeDef,
     PutScheduledUpdateGroupActionTypeRequestTypeDef,
     RecordLifecycleActionHeartbeatTypeRequestTypeDef,
+    ResponseMetadataTypeDef,
+    RollbackInstanceRefreshAnswerTypeDef,
     RollbackInstanceRefreshTypeRequestTypeDef,
     ScalingProcessQueryRequestTypeDef,
     ScheduledUpdateGroupActionTypeDef,
     SetDesiredCapacityTypeRequestTypeDef,
     SetInstanceHealthQueryRequestTypeDef,
     SetInstanceProtectionQueryRequestTypeDef,
+    StartInstanceRefreshAnswerTypeDef,
     TerminateInstanceInAutoScalingGroupTypeRequestTypeDef,
     ActivitiesTypeTypeDef,
     ActivityTypeTypeDef,
-    CancelInstanceRefreshAnswerTypeDef,
-    DescribeAccountLimitsAnswerTypeDef,
-    DescribeAutoScalingNotificationTypesAnswerTypeDef,
-    DescribeLifecycleHookTypesAnswerTypeDef,
-    DescribeTerminationPolicyTypesAnswerTypeDef,
     DetachInstancesAnswerTypeDef,
-    EmptyResponseMetadataTypeDef,
     EnterStandbyAnswerTypeDef,
     ExitStandbyAnswerTypeDef,
-    RollbackInstanceRefreshAnswerTypeDef,
-    StartInstanceRefreshAnswerTypeDef,
     DescribeAdjustmentTypesAnswerTypeDef,
     PolicyARNTypeTypeDef,
     AttachTrafficSourcesTypeRequestTypeDef,
     DetachTrafficSourcesTypeRequestTypeDef,
-    AutoScalingGroupNamesTypeRequestTypeDef,
-    DescribeTagsTypeRequestTypeDef,
     AutoScalingGroupNamesTypeDescribeAutoScalingGroupsPaginateTypeDef,
-    DescribeAutoScalingInstancesTypeDescribeAutoScalingInstancesPaginateTypeDef,
-    DescribeLoadBalancerTargetGroupsRequestDescribeLoadBalancerTargetGroupsPaginateTypeDef,
-    DescribeLoadBalancersRequestDescribeLoadBalancersPaginateTypeDef,
-    DescribeNotificationConfigurationsTypeDescribeNotificationConfigurationsPaginateTypeDef,
-    DescribePoliciesTypeDescribePoliciesPaginateTypeDef,
-    DescribeScalingActivitiesTypeDescribeScalingActivitiesPaginateTypeDef,
-    DescribeScheduledActionsTypeDescribeScheduledActionsPaginateTypeDef,
+    AutoScalingGroupNamesTypeRequestTypeDef,
     DescribeTagsTypeDescribeTagsPaginateTypeDef,
-    LaunchConfigurationNamesTypeDescribeLaunchConfigurationsPaginateTypeDef,
+    DescribeTagsTypeRequestTypeDef,
     AutoScalingInstanceDetailsTypeDef,
     InstanceTypeDef,
     TagsTypeTypeDef,
     BatchDeleteScheduledActionAnswerTypeDef,
     BatchPutScheduledUpdateGroupActionAnswerTypeDef,
     BatchPutScheduledUpdateGroupActionTypeRequestTypeDef,
     BlockDeviceMappingTypeDef,
@@ -577,43 +577,43 @@
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

### Comparing `types-aiobotocore-autoscaling-2.5.0.post1/README.md` & `types-aiobotocore-autoscaling-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-autoscaling"></a>
 
 # types-aiobotocore-autoscaling
 
 [![PyPI - types-aiobotocore-autoscaling](https://img.shields.io/pypi/v/types-aiobotocore-autoscaling.svg?color=blue)](https://pypi.org/project/types-aiobotocore-autoscaling)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-autoscaling.svg?color=blue)](https://pypi.org/project/types-aiobotocore-autoscaling)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-autoscaling?color=blue)](https://pypistats.org/packages/types-aiobotocore-autoscaling)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.AutoScaling 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling)
+[aiobotocore.AutoScaling 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling)
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
 [types-aiobotocore-autoscaling docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/).
 
 See how it helps to find and fix potential bugs:
 
@@ -357,68 +357,79 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_autoscaling.type_defs import (
     AcceleratorCountRequestTypeDef,
     AcceleratorTotalMemoryMiBRequestTypeDef,
     ActivityTypeDef,
-    ResponseMetadataTypeDef,
     AdjustmentTypeTypeDef,
     AlarmTypeDef,
     AttachInstancesQueryRequestTypeDef,
     AttachLoadBalancerTargetGroupsTypeRequestTypeDef,
     AttachLoadBalancersTypeRequestTypeDef,
     TrafficSourceIdentifierTypeDef,
     FilterTypeDef,
-    PaginatorConfigTypeDef,
     EnabledMetricTypeDef,
     LaunchTemplateSpecificationTypeDef,
     SuspendedProcessTypeDef,
     TagDescriptionTypeDef,
     BaselineEbsBandwidthMbpsRequestTypeDef,
     FailedScheduledUpdateGroupActionRequestTypeDef,
     BatchDeleteScheduledActionTypeRequestTypeDef,
     ScheduledUpdateGroupActionRequestTypeDef,
     EbsTypeDef,
+    CancelInstanceRefreshAnswerTypeDef,
     CancelInstanceRefreshTypeRequestTypeDef,
     CapacityForecastTypeDef,
     CompleteLifecycleActionTypeRequestTypeDef,
     LifecycleHookSpecificationTypeDef,
     TagTypeDef,
     InstanceMetadataOptionsTypeDef,
     InstanceMonitoringTypeDef,
     MetricDimensionTypeDef,
     DeleteAutoScalingGroupTypeRequestTypeDef,
     DeleteLifecycleHookTypeRequestTypeDef,
     DeleteNotificationConfigurationTypeRequestTypeDef,
     DeletePolicyTypeRequestTypeDef,
     DeleteScheduledActionTypeRequestTypeDef,
     DeleteWarmPoolTypeRequestTypeDef,
+    DescribeAccountLimitsAnswerTypeDef,
+    DescribeAutoScalingInstancesTypeDescribeAutoScalingInstancesPaginateTypeDef,
     DescribeAutoScalingInstancesTypeRequestTypeDef,
+    DescribeAutoScalingNotificationTypesAnswerTypeDef,
     DescribeInstanceRefreshesTypeRequestTypeDef,
+    DescribeLifecycleHookTypesAnswerTypeDef,
     LifecycleHookTypeDef,
     DescribeLifecycleHooksTypeRequestTypeDef,
+    DescribeLoadBalancerTargetGroupsRequestDescribeLoadBalancerTargetGroupsPaginateTypeDef,
     DescribeLoadBalancerTargetGroupsRequestRequestTypeDef,
     LoadBalancerTargetGroupStateTypeDef,
+    DescribeLoadBalancersRequestDescribeLoadBalancersPaginateTypeDef,
     DescribeLoadBalancersRequestRequestTypeDef,
     LoadBalancerStateTypeDef,
     MetricCollectionTypeTypeDef,
     MetricGranularityTypeTypeDef,
     NotificationConfigurationTypeDef,
+    DescribeNotificationConfigurationsTypeDescribeNotificationConfigurationsPaginateTypeDef,
     DescribeNotificationConfigurationsTypeRequestTypeDef,
+    DescribePoliciesTypeDescribePoliciesPaginateTypeDef,
     DescribePoliciesTypeRequestTypeDef,
+    DescribeScalingActivitiesTypeDescribeScalingActivitiesPaginateTypeDef,
     DescribeScalingActivitiesTypeRequestTypeDef,
+    DescribeScheduledActionsTypeDescribeScheduledActionsPaginateTypeDef,
     DescribeScheduledActionsTypeRequestTypeDef,
+    DescribeTerminationPolicyTypesAnswerTypeDef,
     DescribeTrafficSourcesRequestRequestTypeDef,
     TrafficSourceStateTypeDef,
     DescribeWarmPoolTypeRequestTypeDef,
     DetachInstancesQueryRequestTypeDef,
     DetachLoadBalancerTargetGroupsTypeRequestTypeDef,
     DetachLoadBalancersTypeRequestTypeDef,
     DisableMetricsCollectionQueryRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EnableMetricsCollectionQueryRequestTypeDef,
     EnterStandbyQueryRequestTypeDef,
     ExecutePolicyTypeRequestTypeDef,
     ExitStandbyQueryRequestTypeDef,
     GetPredictiveScalingForecastTypeRequestTypeDef,
     InstanceRefreshLivePoolProgressTypeDef,
     InstanceRefreshWarmPoolProgressTypeDef,
@@ -428,61 +439,50 @@
     NetworkBandwidthGbpsRequestTypeDef,
     NetworkInterfaceCountRequestTypeDef,
     TotalLocalStorageGBRequestTypeDef,
     VCpuCountRequestTypeDef,
     InstanceReusePolicyTypeDef,
     InstancesDistributionTypeDef,
     LaunchConfigurationNameTypeRequestTypeDef,
+    LaunchConfigurationNamesTypeDescribeLaunchConfigurationsPaginateTypeDef,
     LaunchConfigurationNamesTypeRequestTypeDef,
+    PaginatorConfigTypeDef,
     PredefinedMetricSpecificationTypeDef,
     PredictiveScalingPredefinedLoadMetricTypeDef,
     PredictiveScalingPredefinedMetricPairTypeDef,
     PredictiveScalingPredefinedScalingMetricTypeDef,
     ProcessTypeTypeDef,
     PutLifecycleHookTypeRequestTypeDef,
     PutNotificationConfigurationTypeRequestTypeDef,
     StepAdjustmentTypeDef,
     PutScheduledUpdateGroupActionTypeRequestTypeDef,
     RecordLifecycleActionHeartbeatTypeRequestTypeDef,
+    ResponseMetadataTypeDef,
+    RollbackInstanceRefreshAnswerTypeDef,
     RollbackInstanceRefreshTypeRequestTypeDef,
     ScalingProcessQueryRequestTypeDef,
     ScheduledUpdateGroupActionTypeDef,
     SetDesiredCapacityTypeRequestTypeDef,
     SetInstanceHealthQueryRequestTypeDef,
     SetInstanceProtectionQueryRequestTypeDef,
+    StartInstanceRefreshAnswerTypeDef,
     TerminateInstanceInAutoScalingGroupTypeRequestTypeDef,
     ActivitiesTypeTypeDef,
     ActivityTypeTypeDef,
-    CancelInstanceRefreshAnswerTypeDef,
-    DescribeAccountLimitsAnswerTypeDef,
-    DescribeAutoScalingNotificationTypesAnswerTypeDef,
-    DescribeLifecycleHookTypesAnswerTypeDef,
-    DescribeTerminationPolicyTypesAnswerTypeDef,
     DetachInstancesAnswerTypeDef,
-    EmptyResponseMetadataTypeDef,
     EnterStandbyAnswerTypeDef,
     ExitStandbyAnswerTypeDef,
-    RollbackInstanceRefreshAnswerTypeDef,
-    StartInstanceRefreshAnswerTypeDef,
     DescribeAdjustmentTypesAnswerTypeDef,
     PolicyARNTypeTypeDef,
     AttachTrafficSourcesTypeRequestTypeDef,
     DetachTrafficSourcesTypeRequestTypeDef,
-    AutoScalingGroupNamesTypeRequestTypeDef,
-    DescribeTagsTypeRequestTypeDef,
     AutoScalingGroupNamesTypeDescribeAutoScalingGroupsPaginateTypeDef,
-    DescribeAutoScalingInstancesTypeDescribeAutoScalingInstancesPaginateTypeDef,
-    DescribeLoadBalancerTargetGroupsRequestDescribeLoadBalancerTargetGroupsPaginateTypeDef,
-    DescribeLoadBalancersRequestDescribeLoadBalancersPaginateTypeDef,
-    DescribeNotificationConfigurationsTypeDescribeNotificationConfigurationsPaginateTypeDef,
-    DescribePoliciesTypeDescribePoliciesPaginateTypeDef,
-    DescribeScalingActivitiesTypeDescribeScalingActivitiesPaginateTypeDef,
-    DescribeScheduledActionsTypeDescribeScheduledActionsPaginateTypeDef,
+    AutoScalingGroupNamesTypeRequestTypeDef,
     DescribeTagsTypeDescribeTagsPaginateTypeDef,
-    LaunchConfigurationNamesTypeDescribeLaunchConfigurationsPaginateTypeDef,
+    DescribeTagsTypeRequestTypeDef,
     AutoScalingInstanceDetailsTypeDef,
     InstanceTypeDef,
     TagsTypeTypeDef,
     BatchDeleteScheduledActionAnswerTypeDef,
     BatchPutScheduledUpdateGroupActionAnswerTypeDef,
     BatchPutScheduledUpdateGroupActionTypeRequestTypeDef,
     BlockDeviceMappingTypeDef,
@@ -544,43 +544,43 @@
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

### Comparing `types-aiobotocore-autoscaling-2.5.0.post1/setup.py` & `types-aiobotocore-autoscaling-2.5.1/setup.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-autoscaling.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-autoscaling",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_autoscaling"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.AutoScaling 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.AutoScaling 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/"
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

### Comparing `types-aiobotocore-autoscaling-2.5.0.post1/types_aiobotocore_autoscaling/__init__.py` & `types-aiobotocore-autoscaling-2.5.1/types_aiobotocore_autoscaling/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-autoscaling-2.5.0.post1/types_aiobotocore_autoscaling/__init__.pyi` & `types-aiobotocore-autoscaling-2.5.1/types_aiobotocore_autoscaling/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-autoscaling-2.5.0.post1/types_aiobotocore_autoscaling/__main__.py` & `types-aiobotocore-autoscaling-2.5.1/types_aiobotocore_autoscaling/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.AutoScaling 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.AutoScaling 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling\nOther"
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

### Comparing `types-aiobotocore-autoscaling-2.5.0.post1/types_aiobotocore_autoscaling/client.py` & `types-aiobotocore-autoscaling-2.5.1/types_aiobotocore_autoscaling/client.py`

 * *Files 1% similar despite different names*

```diff
@@ -144,15 +144,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/client/#attach_instances)
         """
 
     async def attach_load_balancer_target_groups(
         self, *, AutoScalingGroupName: str, TargetGroupARNs: Sequence[str]
     ) -> Dict[str, Any]:
         """
-        Attaches one or more target groups to the specified Auto Scaling group.
+        .
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Client.attach_load_balancer_target_groups)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/client/#attach_load_balancer_target_groups)
         """
 
     async def attach_load_balancers(
         self, *, AutoScalingGroupName: str, LoadBalancerNames: Sequence[str]
@@ -164,16 +164,15 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/client/#attach_load_balancers)
         """
 
     async def attach_traffic_sources(
         self, *, AutoScalingGroupName: str, TrafficSources: Sequence[TrafficSourceIdentifierTypeDef]
     ) -> Dict[str, Any]:
         """
-        **Reserved for use with Amazon VPC Lattice, which is in preview and subject to
-        change.
+        Attaches one or more traffic sources to the specified Auto Scaling group.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Client.attach_traffic_sources)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/client/#attach_traffic_sources)
         """
 
     async def batch_delete_scheduled_action(
         self, *, AutoScalingGroupName: str, ScheduledActionNames: Sequence[str]
@@ -500,26 +499,25 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/client/#describe_lifecycle_hooks)
         """
 
     async def describe_load_balancer_target_groups(
         self, *, AutoScalingGroupName: str, NextToken: str = ..., MaxRecords: int = ...
     ) -> DescribeLoadBalancerTargetGroupsResponseTypeDef:
         """
-        Gets information about the Elastic Load Balancing target groups for the
-        specified Auto Scaling group.
+        .
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Client.describe_load_balancer_target_groups)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/client/#describe_load_balancer_target_groups)
         """
 
     async def describe_load_balancers(
         self, *, AutoScalingGroupName: str, NextToken: str = ..., MaxRecords: int = ...
     ) -> DescribeLoadBalancersResponseTypeDef:
         """
-        Gets information about the load balancers for the specified Auto Scaling group.
+        .
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Client.describe_load_balancers)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/client/#describe_load_balancers)
         """
 
     async def describe_metric_collection_types(self) -> DescribeMetricCollectionTypesAnswerTypeDef:
         """
@@ -623,21 +621,20 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/client/#describe_termination_policy_types)
         """
 
     async def describe_traffic_sources(
         self,
         *,
         AutoScalingGroupName: str,
-        TrafficSourceType: str,
+        TrafficSourceType: str = ...,
         NextToken: str = ...,
         MaxRecords: int = ...
     ) -> DescribeTrafficSourcesResponseTypeDef:
         """
-        **Reserved for use with Amazon VPC Lattice, which is in preview and subject to
-        change.
+        Gets information about the traffic sources for the specified Auto Scaling group.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Client.describe_traffic_sources)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/client/#describe_traffic_sources)
         """
 
     async def describe_warm_pool(
         self, *, AutoScalingGroupName: str, MaxRecords: int = ..., NextToken: str = ...
@@ -663,37 +660,35 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/client/#detach_instances)
         """
 
     async def detach_load_balancer_target_groups(
         self, *, AutoScalingGroupName: str, TargetGroupARNs: Sequence[str]
     ) -> Dict[str, Any]:
         """
-        Detaches one or more target groups from the specified Auto Scaling group.
+        .
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Client.detach_load_balancer_target_groups)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/client/#detach_load_balancer_target_groups)
         """
 
     async def detach_load_balancers(
         self, *, AutoScalingGroupName: str, LoadBalancerNames: Sequence[str]
     ) -> Dict[str, Any]:
         """
-        Detaches one or more Classic Load Balancers from the specified Auto Scaling
-        group.
+        .
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Client.detach_load_balancers)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/client/#detach_load_balancers)
         """
 
     async def detach_traffic_sources(
         self, *, AutoScalingGroupName: str, TrafficSources: Sequence[TrafficSourceIdentifierTypeDef]
     ) -> Dict[str, Any]:
         """
-        **Reserved for use with Amazon VPC Lattice, which is in preview and subject to
-        change.
+        Detaches one or more traffic sources from the specified Auto Scaling group.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Client.detach_traffic_sources)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/client/#detach_traffic_sources)
         """
 
     async def disable_metrics_collection(
         self, *, AutoScalingGroupName: str, Metrics: Sequence[str] = ...
```

### Comparing `types-aiobotocore-autoscaling-2.5.0.post1/types_aiobotocore_autoscaling/client.pyi` & `types-aiobotocore-autoscaling-2.5.1/types_aiobotocore_autoscaling/client.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -138,15 +138,15 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Client.attach_instances)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/client/#attach_instances)
         """
     async def attach_load_balancer_target_groups(
         self, *, AutoScalingGroupName: str, TargetGroupARNs: Sequence[str]
     ) -> Dict[str, Any]:
         """
-        Attaches one or more target groups to the specified Auto Scaling group.
+        .
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Client.attach_load_balancer_target_groups)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/client/#attach_load_balancer_target_groups)
         """
     async def attach_load_balancers(
         self, *, AutoScalingGroupName: str, LoadBalancerNames: Sequence[str]
     ) -> Dict[str, Any]:
@@ -156,16 +156,15 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Client.attach_load_balancers)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/client/#attach_load_balancers)
         """
     async def attach_traffic_sources(
         self, *, AutoScalingGroupName: str, TrafficSources: Sequence[TrafficSourceIdentifierTypeDef]
     ) -> Dict[str, Any]:
         """
-        **Reserved for use with Amazon VPC Lattice, which is in preview and subject to
-        change.
+        Attaches one or more traffic sources to the specified Auto Scaling group.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Client.attach_traffic_sources)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/client/#attach_traffic_sources)
         """
     async def batch_delete_scheduled_action(
         self, *, AutoScalingGroupName: str, ScheduledActionNames: Sequence[str]
     ) -> BatchDeleteScheduledActionAnswerTypeDef:
@@ -465,25 +464,24 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Client.describe_lifecycle_hooks)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/client/#describe_lifecycle_hooks)
         """
     async def describe_load_balancer_target_groups(
         self, *, AutoScalingGroupName: str, NextToken: str = ..., MaxRecords: int = ...
     ) -> DescribeLoadBalancerTargetGroupsResponseTypeDef:
         """
-        Gets information about the Elastic Load Balancing target groups for the
-        specified Auto Scaling group.
+        .
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Client.describe_load_balancer_target_groups)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/client/#describe_load_balancer_target_groups)
         """
     async def describe_load_balancers(
         self, *, AutoScalingGroupName: str, NextToken: str = ..., MaxRecords: int = ...
     ) -> DescribeLoadBalancersResponseTypeDef:
         """
-        Gets information about the load balancers for the specified Auto Scaling group.
+        .
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Client.describe_load_balancers)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/client/#describe_load_balancers)
         """
     async def describe_metric_collection_types(self) -> DescribeMetricCollectionTypesAnswerTypeDef:
         """
         Describes the available CloudWatch metrics for Amazon EC2 Auto Scaling.
@@ -578,21 +576,20 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Client.describe_termination_policy_types)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/client/#describe_termination_policy_types)
         """
     async def describe_traffic_sources(
         self,
         *,
         AutoScalingGroupName: str,
-        TrafficSourceType: str,
+        TrafficSourceType: str = ...,
         NextToken: str = ...,
         MaxRecords: int = ...
     ) -> DescribeTrafficSourcesResponseTypeDef:
         """
-        **Reserved for use with Amazon VPC Lattice, which is in preview and subject to
-        change.
+        Gets information about the traffic sources for the specified Auto Scaling group.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Client.describe_traffic_sources)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/client/#describe_traffic_sources)
         """
     async def describe_warm_pool(
         self, *, AutoScalingGroupName: str, MaxRecords: int = ..., NextToken: str = ...
     ) -> DescribeWarmPoolAnswerTypeDef:
@@ -615,35 +612,33 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Client.detach_instances)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/client/#detach_instances)
         """
     async def detach_load_balancer_target_groups(
         self, *, AutoScalingGroupName: str, TargetGroupARNs: Sequence[str]
     ) -> Dict[str, Any]:
         """
-        Detaches one or more target groups from the specified Auto Scaling group.
+        .
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Client.detach_load_balancer_target_groups)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/client/#detach_load_balancer_target_groups)
         """
     async def detach_load_balancers(
         self, *, AutoScalingGroupName: str, LoadBalancerNames: Sequence[str]
     ) -> Dict[str, Any]:
         """
-        Detaches one or more Classic Load Balancers from the specified Auto Scaling
-        group.
+        .
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Client.detach_load_balancers)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/client/#detach_load_balancers)
         """
     async def detach_traffic_sources(
         self, *, AutoScalingGroupName: str, TrafficSources: Sequence[TrafficSourceIdentifierTypeDef]
     ) -> Dict[str, Any]:
         """
-        **Reserved for use with Amazon VPC Lattice, which is in preview and subject to
-        change.
+        Detaches one or more traffic sources from the specified Auto Scaling group.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Client.detach_traffic_sources)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/client/#detach_traffic_sources)
         """
     async def disable_metrics_collection(
         self, *, AutoScalingGroupName: str, Metrics: Sequence[str] = ...
     ) -> EmptyResponseMetadataTypeDef:
```

### Comparing `types-aiobotocore-autoscaling-2.5.0.post1/types_aiobotocore_autoscaling/literals.py` & `types-aiobotocore-autoscaling-2.5.1/types_aiobotocore_autoscaling/literals.py`

 * *Files 4% similar despite different names*

```diff
@@ -151,14 +151,15 @@
     "Cancelled",
     "Failed",
     "InProgress",
     "MidLifecycleAction",
     "PendingSpotBidPlacement",
     "PreInService",
     "Successful",
+    "WaitingForConnectionDraining",
     "WaitingForELBConnectionDraining",
     "WaitingForInstanceId",
     "WaitingForInstanceWarmup",
     "WaitingForSpotInstanceId",
     "WaitingForSpotInstanceRequestId",
 ]
 StandbyInstancesType = Literal["Ignore", "Terminate", "Wait"]
@@ -223,14 +224,15 @@
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
@@ -309,14 +311,15 @@
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
@@ -327,14 +330,15 @@
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
@@ -370,14 +374,15 @@
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
@@ -396,16 +401,19 @@
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
@@ -489,15 +497,17 @@
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

### Comparing `types-aiobotocore-autoscaling-2.5.0.post1/types_aiobotocore_autoscaling/literals.pyi` & `types-aiobotocore-autoscaling-2.5.1/types_aiobotocore_autoscaling/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -149,14 +149,15 @@
     "Cancelled",
     "Failed",
     "InProgress",
     "MidLifecycleAction",
     "PendingSpotBidPlacement",
     "PreInService",
     "Successful",
+    "WaitingForConnectionDraining",
     "WaitingForELBConnectionDraining",
     "WaitingForInstanceId",
     "WaitingForInstanceWarmup",
     "WaitingForSpotInstanceId",
     "WaitingForSpotInstanceRequestId",
 ]
 StandbyInstancesType = Literal["Ignore", "Terminate", "Wait"]
@@ -221,14 +222,15 @@
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
@@ -307,14 +309,15 @@
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
@@ -325,14 +328,15 @@
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
@@ -368,14 +372,15 @@
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
@@ -394,16 +399,19 @@
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
@@ -487,15 +495,17 @@
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

### Comparing `types-aiobotocore-autoscaling-2.5.0.post1/types_aiobotocore_autoscaling/paginator.py` & `types-aiobotocore-autoscaling-2.5.1/types_aiobotocore_autoscaling/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -34,17 +34,16 @@
         describe_notification_configurations_paginator: DescribeNotificationConfigurationsPaginator = client.get_paginator("describe_notification_configurations")
         describe_policies_paginator: DescribePoliciesPaginator = client.get_paginator("describe_policies")
         describe_scaling_activities_paginator: DescribeScalingActivitiesPaginator = client.get_paginator("describe_scaling_activities")
         describe_scheduled_actions_paginator: DescribeScheduledActionsPaginator = client.get_paginator("describe_scheduled_actions")
         describe_tags_paginator: DescribeTagsPaginator = client.get_paginator("describe_tags")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, Sequence, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ActivitiesTypeTypeDef,
     AutoScalingGroupsTypeTypeDef,
@@ -56,20 +55,14 @@
     LaunchConfigurationsTypeTypeDef,
     PaginatorConfigTypeDef,
     PoliciesTypeTypeDef,
     ScheduledActionsTypeTypeDef,
     TagsTypeTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "DescribeAutoScalingGroupsPaginator",
     "DescribeAutoScalingInstancesPaginator",
     "DescribeLaunchConfigurationsPaginator",
     "DescribeLoadBalancerTargetGroupsPaginator",
     "DescribeLoadBalancersPaginator",
     "DescribeNotificationConfigurationsPaginator",
@@ -97,30 +90,30 @@
     """
 
     def paginate(
         self,
         *,
         AutoScalingGroupNames: Sequence[str] = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[AutoScalingGroupsTypeTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Paginator.DescribeAutoScalingGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/paginators/#describeautoscalinggroupspaginator)
         """
 
 
 class DescribeAutoScalingInstancesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Paginator.DescribeAutoScalingInstances)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/paginators/#describeautoscalinginstancespaginator)
     """
 
     def paginate(
-        self, *, InstanceIds: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, InstanceIds: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[AutoScalingInstancesTypeTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Paginator.DescribeAutoScalingInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/paginators/#describeautoscalinginstancespaginator)
         """
 
 
@@ -130,45 +123,45 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/paginators/#describelaunchconfigurationspaginator)
     """
 
     def paginate(
         self,
         *,
         LaunchConfigurationNames: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[LaunchConfigurationsTypeTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Paginator.DescribeLaunchConfigurations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/paginators/#describelaunchconfigurationspaginator)
         """
 
 
 class DescribeLoadBalancerTargetGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Paginator.DescribeLoadBalancerTargetGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/paginators/#describeloadbalancertargetgroupspaginator)
     """
 
     def paginate(
-        self, *, AutoScalingGroupName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, AutoScalingGroupName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeLoadBalancerTargetGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Paginator.DescribeLoadBalancerTargetGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/paginators/#describeloadbalancertargetgroupspaginator)
         """
 
 
 class DescribeLoadBalancersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Paginator.DescribeLoadBalancers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/paginators/#describeloadbalancerspaginator)
     """
 
     def paginate(
-        self, *, AutoScalingGroupName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, AutoScalingGroupName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeLoadBalancersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Paginator.DescribeLoadBalancers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/paginators/#describeloadbalancerspaginator)
         """
 
 
@@ -178,15 +171,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/paginators/#describenotificationconfigurationspaginator)
     """
 
     def paginate(
         self,
         *,
         AutoScalingGroupNames: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeNotificationConfigurationsAnswerTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Paginator.DescribeNotificationConfigurations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/paginators/#describenotificationconfigurationspaginator)
         """
 
 
@@ -198,15 +191,15 @@
 
     def paginate(
         self,
         *,
         AutoScalingGroupName: str = ...,
         PolicyNames: Sequence[str] = ...,
         PolicyTypes: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[PoliciesTypeTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Paginator.DescribePolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/paginators/#describepoliciespaginator)
         """
 
 
@@ -218,15 +211,15 @@
 
     def paginate(
         self,
         *,
         ActivityIds: Sequence[str] = ...,
         AutoScalingGroupName: str = ...,
         IncludeDeletedGroups: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ActivitiesTypeTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Paginator.DescribeScalingActivities.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/paginators/#describescalingactivitiespaginator)
         """
 
 
@@ -239,15 +232,15 @@
     def paginate(
         self,
         *,
         AutoScalingGroupName: str = ...,
         ScheduledActionNames: Sequence[str] = ...,
         StartTime: Union[datetime, str] = ...,
         EndTime: Union[datetime, str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ScheduledActionsTypeTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Paginator.DescribeScheduledActions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/paginators/#describescheduledactionspaginator)
         """
 
 
@@ -257,13 +250,13 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/paginators/#describetagspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[TagsTypeTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Paginator.DescribeTags.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/paginators/#describetagspaginator)
         """
```

### Comparing `types-aiobotocore-autoscaling-2.5.0.post1/types_aiobotocore_autoscaling/paginator.pyi` & `types-aiobotocore-autoscaling-2.5.1/types_aiobotocore_autoscaling/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -34,17 +34,16 @@
         describe_notification_configurations_paginator: DescribeNotificationConfigurationsPaginator = client.get_paginator("describe_notification_configurations")
         describe_policies_paginator: DescribePoliciesPaginator = client.get_paginator("describe_policies")
         describe_scaling_activities_paginator: DescribeScalingActivitiesPaginator = client.get_paginator("describe_scaling_activities")
         describe_scheduled_actions_paginator: DescribeScheduledActionsPaginator = client.get_paginator("describe_scheduled_actions")
         describe_tags_paginator: DescribeTagsPaginator = client.get_paginator("describe_tags")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, Sequence, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ActivitiesTypeTypeDef,
     AutoScalingGroupsTypeTypeDef,
@@ -56,19 +55,14 @@
     LaunchConfigurationsTypeTypeDef,
     PaginatorConfigTypeDef,
     PoliciesTypeTypeDef,
     ScheduledActionsTypeTypeDef,
     TagsTypeTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "DescribeAutoScalingGroupsPaginator",
     "DescribeAutoScalingInstancesPaginator",
     "DescribeLaunchConfigurationsPaginator",
     "DescribeLoadBalancerTargetGroupsPaginator",
     "DescribeLoadBalancersPaginator",
     "DescribeNotificationConfigurationsPaginator",
@@ -93,29 +87,29 @@
     """
 
     def paginate(
         self,
         *,
         AutoScalingGroupNames: Sequence[str] = ...,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[AutoScalingGroupsTypeTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Paginator.DescribeAutoScalingGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/paginators/#describeautoscalinggroupspaginator)
         """
 
 class DescribeAutoScalingInstancesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Paginator.DescribeAutoScalingInstances)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/paginators/#describeautoscalinginstancespaginator)
     """
 
     def paginate(
-        self, *, InstanceIds: Sequence[str] = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, InstanceIds: Sequence[str] = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[AutoScalingInstancesTypeTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Paginator.DescribeAutoScalingInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/paginators/#describeautoscalinginstancespaginator)
         """
 
 class DescribeLaunchConfigurationsPaginator(AioPaginator):
@@ -124,43 +118,43 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/paginators/#describelaunchconfigurationspaginator)
     """
 
     def paginate(
         self,
         *,
         LaunchConfigurationNames: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[LaunchConfigurationsTypeTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Paginator.DescribeLaunchConfigurations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/paginators/#describelaunchconfigurationspaginator)
         """
 
 class DescribeLoadBalancerTargetGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Paginator.DescribeLoadBalancerTargetGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/paginators/#describeloadbalancertargetgroupspaginator)
     """
 
     def paginate(
-        self, *, AutoScalingGroupName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, AutoScalingGroupName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeLoadBalancerTargetGroupsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Paginator.DescribeLoadBalancerTargetGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/paginators/#describeloadbalancertargetgroupspaginator)
         """
 
 class DescribeLoadBalancersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Paginator.DescribeLoadBalancers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/paginators/#describeloadbalancerspaginator)
     """
 
     def paginate(
-        self, *, AutoScalingGroupName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, AutoScalingGroupName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeLoadBalancersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Paginator.DescribeLoadBalancers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/paginators/#describeloadbalancerspaginator)
         """
 
 class DescribeNotificationConfigurationsPaginator(AioPaginator):
@@ -169,15 +163,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/paginators/#describenotificationconfigurationspaginator)
     """
 
     def paginate(
         self,
         *,
         AutoScalingGroupNames: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeNotificationConfigurationsAnswerTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Paginator.DescribeNotificationConfigurations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/paginators/#describenotificationconfigurationspaginator)
         """
 
 class DescribePoliciesPaginator(AioPaginator):
@@ -188,15 +182,15 @@
 
     def paginate(
         self,
         *,
         AutoScalingGroupName: str = ...,
         PolicyNames: Sequence[str] = ...,
         PolicyTypes: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[PoliciesTypeTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Paginator.DescribePolicies.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/paginators/#describepoliciespaginator)
         """
 
 class DescribeScalingActivitiesPaginator(AioPaginator):
@@ -207,15 +201,15 @@
 
     def paginate(
         self,
         *,
         ActivityIds: Sequence[str] = ...,
         AutoScalingGroupName: str = ...,
         IncludeDeletedGroups: bool = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ActivitiesTypeTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Paginator.DescribeScalingActivities.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/paginators/#describescalingactivitiespaginator)
         """
 
 class DescribeScheduledActionsPaginator(AioPaginator):
@@ -227,15 +221,15 @@
     def paginate(
         self,
         *,
         AutoScalingGroupName: str = ...,
         ScheduledActionNames: Sequence[str] = ...,
         StartTime: Union[datetime, str] = ...,
         EndTime: Union[datetime, str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ScheduledActionsTypeTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Paginator.DescribeScheduledActions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/paginators/#describescheduledactionspaginator)
         """
 
 class DescribeTagsPaginator(AioPaginator):
@@ -244,13 +238,13 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/paginators/#describetagspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[FilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[TagsTypeTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling.Paginator.DescribeTags.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/paginators/#describetagspaginator)
         """
```

### Comparing `types-aiobotocore-autoscaling-2.5.0.post1/types_aiobotocore_autoscaling/type_defs.py` & `types-aiobotocore-autoscaling-2.5.1/types_aiobotocore_autoscaling/type_defs.py`

 * *Files 1% similar despite different names*

```diff
@@ -52,68 +52,79 @@
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AcceleratorCountRequestTypeDef",
     "AcceleratorTotalMemoryMiBRequestTypeDef",
     "ActivityTypeDef",
-    "ResponseMetadataTypeDef",
     "AdjustmentTypeTypeDef",
     "AlarmTypeDef",
     "AttachInstancesQueryRequestTypeDef",
     "AttachLoadBalancerTargetGroupsTypeRequestTypeDef",
     "AttachLoadBalancersTypeRequestTypeDef",
     "TrafficSourceIdentifierTypeDef",
     "FilterTypeDef",
-    "PaginatorConfigTypeDef",
     "EnabledMetricTypeDef",
     "LaunchTemplateSpecificationTypeDef",
     "SuspendedProcessTypeDef",
     "TagDescriptionTypeDef",
     "BaselineEbsBandwidthMbpsRequestTypeDef",
     "FailedScheduledUpdateGroupActionRequestTypeDef",
     "BatchDeleteScheduledActionTypeRequestTypeDef",
     "ScheduledUpdateGroupActionRequestTypeDef",
     "EbsTypeDef",
+    "CancelInstanceRefreshAnswerTypeDef",
     "CancelInstanceRefreshTypeRequestTypeDef",
     "CapacityForecastTypeDef",
     "CompleteLifecycleActionTypeRequestTypeDef",
     "LifecycleHookSpecificationTypeDef",
     "TagTypeDef",
     "InstanceMetadataOptionsTypeDef",
     "InstanceMonitoringTypeDef",
     "MetricDimensionTypeDef",
     "DeleteAutoScalingGroupTypeRequestTypeDef",
     "DeleteLifecycleHookTypeRequestTypeDef",
     "DeleteNotificationConfigurationTypeRequestTypeDef",
     "DeletePolicyTypeRequestTypeDef",
     "DeleteScheduledActionTypeRequestTypeDef",
     "DeleteWarmPoolTypeRequestTypeDef",
+    "DescribeAccountLimitsAnswerTypeDef",
+    "DescribeAutoScalingInstancesTypeDescribeAutoScalingInstancesPaginateTypeDef",
     "DescribeAutoScalingInstancesTypeRequestTypeDef",
+    "DescribeAutoScalingNotificationTypesAnswerTypeDef",
     "DescribeInstanceRefreshesTypeRequestTypeDef",
+    "DescribeLifecycleHookTypesAnswerTypeDef",
     "LifecycleHookTypeDef",
     "DescribeLifecycleHooksTypeRequestTypeDef",
+    "DescribeLoadBalancerTargetGroupsRequestDescribeLoadBalancerTargetGroupsPaginateTypeDef",
     "DescribeLoadBalancerTargetGroupsRequestRequestTypeDef",
     "LoadBalancerTargetGroupStateTypeDef",
+    "DescribeLoadBalancersRequestDescribeLoadBalancersPaginateTypeDef",
     "DescribeLoadBalancersRequestRequestTypeDef",
     "LoadBalancerStateTypeDef",
     "MetricCollectionTypeTypeDef",
     "MetricGranularityTypeTypeDef",
     "NotificationConfigurationTypeDef",
+    "DescribeNotificationConfigurationsTypeDescribeNotificationConfigurationsPaginateTypeDef",
     "DescribeNotificationConfigurationsTypeRequestTypeDef",
+    "DescribePoliciesTypeDescribePoliciesPaginateTypeDef",
     "DescribePoliciesTypeRequestTypeDef",
+    "DescribeScalingActivitiesTypeDescribeScalingActivitiesPaginateTypeDef",
     "DescribeScalingActivitiesTypeRequestTypeDef",
+    "DescribeScheduledActionsTypeDescribeScheduledActionsPaginateTypeDef",
     "DescribeScheduledActionsTypeRequestTypeDef",
+    "DescribeTerminationPolicyTypesAnswerTypeDef",
     "DescribeTrafficSourcesRequestRequestTypeDef",
     "TrafficSourceStateTypeDef",
     "DescribeWarmPoolTypeRequestTypeDef",
     "DetachInstancesQueryRequestTypeDef",
     "DetachLoadBalancerTargetGroupsTypeRequestTypeDef",
     "DetachLoadBalancersTypeRequestTypeDef",
     "DisableMetricsCollectionQueryRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EnableMetricsCollectionQueryRequestTypeDef",
     "EnterStandbyQueryRequestTypeDef",
     "ExecutePolicyTypeRequestTypeDef",
     "ExitStandbyQueryRequestTypeDef",
     "GetPredictiveScalingForecastTypeRequestTypeDef",
     "InstanceRefreshLivePoolProgressTypeDef",
     "InstanceRefreshWarmPoolProgressTypeDef",
@@ -123,61 +134,50 @@
     "NetworkBandwidthGbpsRequestTypeDef",
     "NetworkInterfaceCountRequestTypeDef",
     "TotalLocalStorageGBRequestTypeDef",
     "VCpuCountRequestTypeDef",
     "InstanceReusePolicyTypeDef",
     "InstancesDistributionTypeDef",
     "LaunchConfigurationNameTypeRequestTypeDef",
+    "LaunchConfigurationNamesTypeDescribeLaunchConfigurationsPaginateTypeDef",
     "LaunchConfigurationNamesTypeRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "PredefinedMetricSpecificationTypeDef",
     "PredictiveScalingPredefinedLoadMetricTypeDef",
     "PredictiveScalingPredefinedMetricPairTypeDef",
     "PredictiveScalingPredefinedScalingMetricTypeDef",
     "ProcessTypeTypeDef",
     "PutLifecycleHookTypeRequestTypeDef",
     "PutNotificationConfigurationTypeRequestTypeDef",
     "StepAdjustmentTypeDef",
     "PutScheduledUpdateGroupActionTypeRequestTypeDef",
     "RecordLifecycleActionHeartbeatTypeRequestTypeDef",
+    "ResponseMetadataTypeDef",
+    "RollbackInstanceRefreshAnswerTypeDef",
     "RollbackInstanceRefreshTypeRequestTypeDef",
     "ScalingProcessQueryRequestTypeDef",
     "ScheduledUpdateGroupActionTypeDef",
     "SetDesiredCapacityTypeRequestTypeDef",
     "SetInstanceHealthQueryRequestTypeDef",
     "SetInstanceProtectionQueryRequestTypeDef",
+    "StartInstanceRefreshAnswerTypeDef",
     "TerminateInstanceInAutoScalingGroupTypeRequestTypeDef",
     "ActivitiesTypeTypeDef",
     "ActivityTypeTypeDef",
-    "CancelInstanceRefreshAnswerTypeDef",
-    "DescribeAccountLimitsAnswerTypeDef",
-    "DescribeAutoScalingNotificationTypesAnswerTypeDef",
-    "DescribeLifecycleHookTypesAnswerTypeDef",
-    "DescribeTerminationPolicyTypesAnswerTypeDef",
     "DetachInstancesAnswerTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "EnterStandbyAnswerTypeDef",
     "ExitStandbyAnswerTypeDef",
-    "RollbackInstanceRefreshAnswerTypeDef",
-    "StartInstanceRefreshAnswerTypeDef",
     "DescribeAdjustmentTypesAnswerTypeDef",
     "PolicyARNTypeTypeDef",
     "AttachTrafficSourcesTypeRequestTypeDef",
     "DetachTrafficSourcesTypeRequestTypeDef",
-    "AutoScalingGroupNamesTypeRequestTypeDef",
-    "DescribeTagsTypeRequestTypeDef",
     "AutoScalingGroupNamesTypeDescribeAutoScalingGroupsPaginateTypeDef",
-    "DescribeAutoScalingInstancesTypeDescribeAutoScalingInstancesPaginateTypeDef",
-    "DescribeLoadBalancerTargetGroupsRequestDescribeLoadBalancerTargetGroupsPaginateTypeDef",
-    "DescribeLoadBalancersRequestDescribeLoadBalancersPaginateTypeDef",
-    "DescribeNotificationConfigurationsTypeDescribeNotificationConfigurationsPaginateTypeDef",
-    "DescribePoliciesTypeDescribePoliciesPaginateTypeDef",
-    "DescribeScalingActivitiesTypeDescribeScalingActivitiesPaginateTypeDef",
-    "DescribeScheduledActionsTypeDescribeScheduledActionsPaginateTypeDef",
+    "AutoScalingGroupNamesTypeRequestTypeDef",
     "DescribeTagsTypeDescribeTagsPaginateTypeDef",
-    "LaunchConfigurationNamesTypeDescribeLaunchConfigurationsPaginateTypeDef",
+    "DescribeTagsTypeRequestTypeDef",
     "AutoScalingInstanceDetailsTypeDef",
     "InstanceTypeDef",
     "TagsTypeTypeDef",
     "BatchDeleteScheduledActionAnswerTypeDef",
     "BatchPutScheduledUpdateGroupActionAnswerTypeDef",
     "BatchPutScheduledUpdateGroupActionTypeRequestTypeDef",
     "BlockDeviceMappingTypeDef",
@@ -274,25 +274,14 @@
 )
 
 
 class ActivityTypeDef(_RequiredActivityTypeDef, _OptionalActivityTypeDef):
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
 AdjustmentTypeTypeDef = TypedDict(
     "AdjustmentTypeTypeDef",
     {
         "AdjustmentType": str,
     },
     total=False,
 )
@@ -339,41 +328,44 @@
     "AttachLoadBalancersTypeRequestTypeDef",
     {
         "AutoScalingGroupName": str,
         "LoadBalancerNames": Sequence[str],
     },
 )
 
-TrafficSourceIdentifierTypeDef = TypedDict(
-    "TrafficSourceIdentifierTypeDef",
+_RequiredTrafficSourceIdentifierTypeDef = TypedDict(
+    "_RequiredTrafficSourceIdentifierTypeDef",
     {
         "Identifier": str,
     },
+)
+_OptionalTrafficSourceIdentifierTypeDef = TypedDict(
+    "_OptionalTrafficSourceIdentifierTypeDef",
+    {
+        "Type": str,
+    },
     total=False,
 )
 
+
+class TrafficSourceIdentifierTypeDef(
+    _RequiredTrafficSourceIdentifierTypeDef, _OptionalTrafficSourceIdentifierTypeDef
+):
+    pass
+
+
 FilterTypeDef = TypedDict(
     "FilterTypeDef",
     {
         "Name": str,
         "Values": Sequence[str],
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
-    {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
-    },
-    total=False,
-)
-
 EnabledMetricTypeDef = TypedDict(
     "EnabledMetricTypeDef",
     {
         "Metric": str,
         "Granularity": str,
     },
     total=False,
@@ -488,14 +480,22 @@
         "Iops": int,
         "Encrypted": bool,
         "Throughput": int,
     },
     total=False,
 )
 
+CancelInstanceRefreshAnswerTypeDef = TypedDict(
+    "CancelInstanceRefreshAnswerTypeDef",
+    {
+        "InstanceRefreshId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CancelInstanceRefreshTypeRequestTypeDef = TypedDict(
     "CancelInstanceRefreshTypeRequestTypeDef",
     {
         "AutoScalingGroupName": str,
     },
 )
 
@@ -690,24 +690,52 @@
 
 class DeleteWarmPoolTypeRequestTypeDef(
     _RequiredDeleteWarmPoolTypeRequestTypeDef, _OptionalDeleteWarmPoolTypeRequestTypeDef
 ):
     pass
 
 
+DescribeAccountLimitsAnswerTypeDef = TypedDict(
+    "DescribeAccountLimitsAnswerTypeDef",
+    {
+        "MaxNumberOfAutoScalingGroups": int,
+        "MaxNumberOfLaunchConfigurations": int,
+        "NumberOfAutoScalingGroups": int,
+        "NumberOfLaunchConfigurations": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeAutoScalingInstancesTypeDescribeAutoScalingInstancesPaginateTypeDef = TypedDict(
+    "DescribeAutoScalingInstancesTypeDescribeAutoScalingInstancesPaginateTypeDef",
+    {
+        "InstanceIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeAutoScalingInstancesTypeRequestTypeDef = TypedDict(
     "DescribeAutoScalingInstancesTypeRequestTypeDef",
     {
         "InstanceIds": Sequence[str],
         "MaxRecords": int,
         "NextToken": str,
     },
     total=False,
 )
 
+DescribeAutoScalingNotificationTypesAnswerTypeDef = TypedDict(
+    "DescribeAutoScalingNotificationTypesAnswerTypeDef",
+    {
+        "AutoScalingNotificationTypes": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDescribeInstanceRefreshesTypeRequestTypeDef = TypedDict(
     "_RequiredDescribeInstanceRefreshesTypeRequestTypeDef",
     {
         "AutoScalingGroupName": str,
     },
 )
 _OptionalDescribeInstanceRefreshesTypeRequestTypeDef = TypedDict(
@@ -724,14 +752,22 @@
 class DescribeInstanceRefreshesTypeRequestTypeDef(
     _RequiredDescribeInstanceRefreshesTypeRequestTypeDef,
     _OptionalDescribeInstanceRefreshesTypeRequestTypeDef,
 ):
     pass
 
 
+DescribeLifecycleHookTypesAnswerTypeDef = TypedDict(
+    "DescribeLifecycleHookTypesAnswerTypeDef",
+    {
+        "LifecycleHookTypes": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 LifecycleHookTypeDef = TypedDict(
     "LifecycleHookTypeDef",
     {
         "LifecycleHookName": str,
         "AutoScalingGroupName": str,
         "LifecycleTransition": str,
         "NotificationTargetARN": str,
@@ -762,14 +798,36 @@
 class DescribeLifecycleHooksTypeRequestTypeDef(
     _RequiredDescribeLifecycleHooksTypeRequestTypeDef,
     _OptionalDescribeLifecycleHooksTypeRequestTypeDef,
 ):
     pass
 
 
+_RequiredDescribeLoadBalancerTargetGroupsRequestDescribeLoadBalancerTargetGroupsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeLoadBalancerTargetGroupsRequestDescribeLoadBalancerTargetGroupsPaginateTypeDef",
+    {
+        "AutoScalingGroupName": str,
+    },
+)
+_OptionalDescribeLoadBalancerTargetGroupsRequestDescribeLoadBalancerTargetGroupsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeLoadBalancerTargetGroupsRequestDescribeLoadBalancerTargetGroupsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeLoadBalancerTargetGroupsRequestDescribeLoadBalancerTargetGroupsPaginateTypeDef(
+    _RequiredDescribeLoadBalancerTargetGroupsRequestDescribeLoadBalancerTargetGroupsPaginateTypeDef,
+    _OptionalDescribeLoadBalancerTargetGroupsRequestDescribeLoadBalancerTargetGroupsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeLoadBalancerTargetGroupsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeLoadBalancerTargetGroupsRequestRequestTypeDef",
     {
         "AutoScalingGroupName": str,
     },
 )
 _OptionalDescribeLoadBalancerTargetGroupsRequestRequestTypeDef = TypedDict(
@@ -794,14 +852,36 @@
     {
         "LoadBalancerTargetGroupARN": str,
         "State": str,
     },
     total=False,
 )
 
+_RequiredDescribeLoadBalancersRequestDescribeLoadBalancersPaginateTypeDef = TypedDict(
+    "_RequiredDescribeLoadBalancersRequestDescribeLoadBalancersPaginateTypeDef",
+    {
+        "AutoScalingGroupName": str,
+    },
+)
+_OptionalDescribeLoadBalancersRequestDescribeLoadBalancersPaginateTypeDef = TypedDict(
+    "_OptionalDescribeLoadBalancersRequestDescribeLoadBalancersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class DescribeLoadBalancersRequestDescribeLoadBalancersPaginateTypeDef(
+    _RequiredDescribeLoadBalancersRequestDescribeLoadBalancersPaginateTypeDef,
+    _OptionalDescribeLoadBalancersRequestDescribeLoadBalancersPaginateTypeDef,
+):
+    pass
+
+
 _RequiredDescribeLoadBalancersRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeLoadBalancersRequestRequestTypeDef",
     {
         "AutoScalingGroupName": str,
     },
 )
 _OptionalDescribeLoadBalancersRequestRequestTypeDef = TypedDict(
@@ -852,71 +932,122 @@
         "AutoScalingGroupName": str,
         "TopicARN": str,
         "NotificationType": str,
     },
     total=False,
 )
 
+DescribeNotificationConfigurationsTypeDescribeNotificationConfigurationsPaginateTypeDef = TypedDict(
+    "DescribeNotificationConfigurationsTypeDescribeNotificationConfigurationsPaginateTypeDef",
+    {
+        "AutoScalingGroupNames": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeNotificationConfigurationsTypeRequestTypeDef = TypedDict(
     "DescribeNotificationConfigurationsTypeRequestTypeDef",
     {
         "AutoScalingGroupNames": Sequence[str],
         "NextToken": str,
         "MaxRecords": int,
     },
     total=False,
 )
 
+DescribePoliciesTypeDescribePoliciesPaginateTypeDef = TypedDict(
+    "DescribePoliciesTypeDescribePoliciesPaginateTypeDef",
+    {
+        "AutoScalingGroupName": str,
+        "PolicyNames": Sequence[str],
+        "PolicyTypes": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribePoliciesTypeRequestTypeDef = TypedDict(
     "DescribePoliciesTypeRequestTypeDef",
     {
         "AutoScalingGroupName": str,
         "PolicyNames": Sequence[str],
         "PolicyTypes": Sequence[str],
         "NextToken": str,
         "MaxRecords": int,
     },
     total=False,
 )
 
+DescribeScalingActivitiesTypeDescribeScalingActivitiesPaginateTypeDef = TypedDict(
+    "DescribeScalingActivitiesTypeDescribeScalingActivitiesPaginateTypeDef",
+    {
+        "ActivityIds": Sequence[str],
+        "AutoScalingGroupName": str,
+        "IncludeDeletedGroups": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeScalingActivitiesTypeRequestTypeDef = TypedDict(
     "DescribeScalingActivitiesTypeRequestTypeDef",
     {
         "ActivityIds": Sequence[str],
         "AutoScalingGroupName": str,
         "IncludeDeletedGroups": bool,
         "MaxRecords": int,
         "NextToken": str,
     },
     total=False,
 )
 
+DescribeScheduledActionsTypeDescribeScheduledActionsPaginateTypeDef = TypedDict(
+    "DescribeScheduledActionsTypeDescribeScheduledActionsPaginateTypeDef",
+    {
+        "AutoScalingGroupName": str,
+        "ScheduledActionNames": Sequence[str],
+        "StartTime": Union[datetime, str],
+        "EndTime": Union[datetime, str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeScheduledActionsTypeRequestTypeDef = TypedDict(
     "DescribeScheduledActionsTypeRequestTypeDef",
     {
         "AutoScalingGroupName": str,
         "ScheduledActionNames": Sequence[str],
         "StartTime": Union[datetime, str],
         "EndTime": Union[datetime, str],
         "NextToken": str,
         "MaxRecords": int,
     },
     total=False,
 )
 
+DescribeTerminationPolicyTypesAnswerTypeDef = TypedDict(
+    "DescribeTerminationPolicyTypesAnswerTypeDef",
+    {
+        "TerminationPolicyTypes": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDescribeTrafficSourcesRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeTrafficSourcesRequestRequestTypeDef",
     {
         "AutoScalingGroupName": str,
-        "TrafficSourceType": str,
     },
 )
 _OptionalDescribeTrafficSourcesRequestRequestTypeDef = TypedDict(
     "_OptionalDescribeTrafficSourcesRequestRequestTypeDef",
     {
+        "TrafficSourceType": str,
         "NextToken": str,
         "MaxRecords": int,
     },
     total=False,
 )
 
 
@@ -928,14 +1059,16 @@
 
 
 TrafficSourceStateTypeDef = TypedDict(
     "TrafficSourceStateTypeDef",
     {
         "TrafficSource": str,
         "State": str,
+        "Identifier": str,
+        "Type": str,
     },
     total=False,
 )
 
 _RequiredDescribeWarmPoolTypeRequestTypeDef = TypedDict(
     "_RequiredDescribeWarmPoolTypeRequestTypeDef",
     {
@@ -1014,14 +1147,21 @@
 class DisableMetricsCollectionQueryRequestTypeDef(
     _RequiredDisableMetricsCollectionQueryRequestTypeDef,
     _OptionalDisableMetricsCollectionQueryRequestTypeDef,
 ):
     pass
 
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredEnableMetricsCollectionQueryRequestTypeDef = TypedDict(
     "_RequiredEnableMetricsCollectionQueryRequestTypeDef",
     {
         "AutoScalingGroupName": str,
         "Granularity": str,
     },
 )
@@ -1249,24 +1389,43 @@
 LaunchConfigurationNameTypeRequestTypeDef = TypedDict(
     "LaunchConfigurationNameTypeRequestTypeDef",
     {
         "LaunchConfigurationName": str,
     },
 )
 
+LaunchConfigurationNamesTypeDescribeLaunchConfigurationsPaginateTypeDef = TypedDict(
+    "LaunchConfigurationNamesTypeDescribeLaunchConfigurationsPaginateTypeDef",
+    {
+        "LaunchConfigurationNames": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 LaunchConfigurationNamesTypeRequestTypeDef = TypedDict(
     "LaunchConfigurationNamesTypeRequestTypeDef",
     {
         "LaunchConfigurationNames": Sequence[str],
         "NextToken": str,
         "MaxRecords": int,
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
 _RequiredPredefinedMetricSpecificationTypeDef = TypedDict(
     "_RequiredPredefinedMetricSpecificationTypeDef",
     {
         "PredefinedMetricType": MetricTypeType,
     },
 )
 _OptionalPredefinedMetricSpecificationTypeDef = TypedDict(
@@ -1463,14 +1622,33 @@
 class RecordLifecycleActionHeartbeatTypeRequestTypeDef(
     _RequiredRecordLifecycleActionHeartbeatTypeRequestTypeDef,
     _OptionalRecordLifecycleActionHeartbeatTypeRequestTypeDef,
 ):
     pass
 
 
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
+RollbackInstanceRefreshAnswerTypeDef = TypedDict(
+    "RollbackInstanceRefreshAnswerTypeDef",
+    {
+        "InstanceRefreshId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RollbackInstanceRefreshTypeRequestTypeDef = TypedDict(
     "RollbackInstanceRefreshTypeRequestTypeDef",
     {
         "AutoScalingGroupName": str,
     },
     total=False,
 )
@@ -1563,143 +1741,85 @@
     {
         "InstanceIds": Sequence[str],
         "AutoScalingGroupName": str,
         "ProtectedFromScaleIn": bool,
     },
 )
 
+StartInstanceRefreshAnswerTypeDef = TypedDict(
+    "StartInstanceRefreshAnswerTypeDef",
+    {
+        "InstanceRefreshId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TerminateInstanceInAutoScalingGroupTypeRequestTypeDef = TypedDict(
     "TerminateInstanceInAutoScalingGroupTypeRequestTypeDef",
     {
         "InstanceId": str,
         "ShouldDecrementDesiredCapacity": bool,
     },
 )
 
 ActivitiesTypeTypeDef = TypedDict(
     "ActivitiesTypeTypeDef",
     {
         "Activities": List[ActivityTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ActivityTypeTypeDef = TypedDict(
     "ActivityTypeTypeDef",
     {
         "Activity": ActivityTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CancelInstanceRefreshAnswerTypeDef = TypedDict(
-    "CancelInstanceRefreshAnswerTypeDef",
-    {
-        "InstanceRefreshId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeAccountLimitsAnswerTypeDef = TypedDict(
-    "DescribeAccountLimitsAnswerTypeDef",
-    {
-        "MaxNumberOfAutoScalingGroups": int,
-        "MaxNumberOfLaunchConfigurations": int,
-        "NumberOfAutoScalingGroups": int,
-        "NumberOfLaunchConfigurations": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeAutoScalingNotificationTypesAnswerTypeDef = TypedDict(
-    "DescribeAutoScalingNotificationTypesAnswerTypeDef",
-    {
-        "AutoScalingNotificationTypes": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeLifecycleHookTypesAnswerTypeDef = TypedDict(
-    "DescribeLifecycleHookTypesAnswerTypeDef",
-    {
-        "LifecycleHookTypes": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeTerminationPolicyTypesAnswerTypeDef = TypedDict(
-    "DescribeTerminationPolicyTypesAnswerTypeDef",
-    {
-        "TerminationPolicyTypes": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DetachInstancesAnswerTypeDef = TypedDict(
     "DetachInstancesAnswerTypeDef",
     {
         "Activities": List[ActivityTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EnterStandbyAnswerTypeDef = TypedDict(
     "EnterStandbyAnswerTypeDef",
     {
         "Activities": List[ActivityTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ExitStandbyAnswerTypeDef = TypedDict(
     "ExitStandbyAnswerTypeDef",
     {
         "Activities": List[ActivityTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RollbackInstanceRefreshAnswerTypeDef = TypedDict(
-    "RollbackInstanceRefreshAnswerTypeDef",
-    {
-        "InstanceRefreshId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartInstanceRefreshAnswerTypeDef = TypedDict(
-    "StartInstanceRefreshAnswerTypeDef",
-    {
-        "InstanceRefreshId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAdjustmentTypesAnswerTypeDef = TypedDict(
     "DescribeAdjustmentTypesAnswerTypeDef",
     {
         "AdjustmentTypes": List[AdjustmentTypeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PolicyARNTypeTypeDef = TypedDict(
     "PolicyARNTypeTypeDef",
     {
         "PolicyARN": str,
         "Alarms": List[AlarmTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AttachTrafficSourcesTypeRequestTypeDef = TypedDict(
     "AttachTrafficSourcesTypeRequestTypeDef",
     {
         "AutoScalingGroupName": str,
@@ -1711,155 +1831,50 @@
     "DetachTrafficSourcesTypeRequestTypeDef",
     {
         "AutoScalingGroupName": str,
         "TrafficSources": Sequence[TrafficSourceIdentifierTypeDef],
     },
 )
 
-AutoScalingGroupNamesTypeRequestTypeDef = TypedDict(
-    "AutoScalingGroupNamesTypeRequestTypeDef",
-    {
-        "AutoScalingGroupNames": Sequence[str],
-        "NextToken": str,
-        "MaxRecords": int,
-        "Filters": Sequence[FilterTypeDef],
-    },
-    total=False,
-)
-
-DescribeTagsTypeRequestTypeDef = TypedDict(
-    "DescribeTagsTypeRequestTypeDef",
-    {
-        "Filters": Sequence[FilterTypeDef],
-        "NextToken": str,
-        "MaxRecords": int,
-    },
-    total=False,
-)
-
 AutoScalingGroupNamesTypeDescribeAutoScalingGroupsPaginateTypeDef = TypedDict(
     "AutoScalingGroupNamesTypeDescribeAutoScalingGroupsPaginateTypeDef",
     {
         "AutoScalingGroupNames": Sequence[str],
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-DescribeAutoScalingInstancesTypeDescribeAutoScalingInstancesPaginateTypeDef = TypedDict(
-    "DescribeAutoScalingInstancesTypeDescribeAutoScalingInstancesPaginateTypeDef",
-    {
-        "InstanceIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeLoadBalancerTargetGroupsRequestDescribeLoadBalancerTargetGroupsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeLoadBalancerTargetGroupsRequestDescribeLoadBalancerTargetGroupsPaginateTypeDef",
-    {
-        "AutoScalingGroupName": str,
-    },
-)
-_OptionalDescribeLoadBalancerTargetGroupsRequestDescribeLoadBalancerTargetGroupsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeLoadBalancerTargetGroupsRequestDescribeLoadBalancerTargetGroupsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeLoadBalancerTargetGroupsRequestDescribeLoadBalancerTargetGroupsPaginateTypeDef(
-    _RequiredDescribeLoadBalancerTargetGroupsRequestDescribeLoadBalancerTargetGroupsPaginateTypeDef,
-    _OptionalDescribeLoadBalancerTargetGroupsRequestDescribeLoadBalancerTargetGroupsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredDescribeLoadBalancersRequestDescribeLoadBalancersPaginateTypeDef = TypedDict(
-    "_RequiredDescribeLoadBalancersRequestDescribeLoadBalancersPaginateTypeDef",
-    {
-        "AutoScalingGroupName": str,
-    },
-)
-_OptionalDescribeLoadBalancersRequestDescribeLoadBalancersPaginateTypeDef = TypedDict(
-    "_OptionalDescribeLoadBalancersRequestDescribeLoadBalancersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class DescribeLoadBalancersRequestDescribeLoadBalancersPaginateTypeDef(
-    _RequiredDescribeLoadBalancersRequestDescribeLoadBalancersPaginateTypeDef,
-    _OptionalDescribeLoadBalancersRequestDescribeLoadBalancersPaginateTypeDef,
-):
-    pass
-
-
-DescribeNotificationConfigurationsTypeDescribeNotificationConfigurationsPaginateTypeDef = TypedDict(
-    "DescribeNotificationConfigurationsTypeDescribeNotificationConfigurationsPaginateTypeDef",
+AutoScalingGroupNamesTypeRequestTypeDef = TypedDict(
+    "AutoScalingGroupNamesTypeRequestTypeDef",
     {
         "AutoScalingGroupNames": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribePoliciesTypeDescribePoliciesPaginateTypeDef = TypedDict(
-    "DescribePoliciesTypeDescribePoliciesPaginateTypeDef",
-    {
-        "AutoScalingGroupName": str,
-        "PolicyNames": Sequence[str],
-        "PolicyTypes": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeScalingActivitiesTypeDescribeScalingActivitiesPaginateTypeDef = TypedDict(
-    "DescribeScalingActivitiesTypeDescribeScalingActivitiesPaginateTypeDef",
-    {
-        "ActivityIds": Sequence[str],
-        "AutoScalingGroupName": str,
-        "IncludeDeletedGroups": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeScheduledActionsTypeDescribeScheduledActionsPaginateTypeDef = TypedDict(
-    "DescribeScheduledActionsTypeDescribeScheduledActionsPaginateTypeDef",
-    {
-        "AutoScalingGroupName": str,
-        "ScheduledActionNames": Sequence[str],
-        "StartTime": Union[datetime, str],
-        "EndTime": Union[datetime, str],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "NextToken": str,
+        "MaxRecords": int,
+        "Filters": Sequence[FilterTypeDef],
     },
     total=False,
 )
 
 DescribeTagsTypeDescribeTagsPaginateTypeDef = TypedDict(
     "DescribeTagsTypeDescribeTagsPaginateTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-LaunchConfigurationNamesTypeDescribeLaunchConfigurationsPaginateTypeDef = TypedDict(
-    "LaunchConfigurationNamesTypeDescribeLaunchConfigurationsPaginateTypeDef",
+DescribeTagsTypeRequestTypeDef = TypedDict(
+    "DescribeTagsTypeRequestTypeDef",
     {
-        "LaunchConfigurationNames": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "Filters": Sequence[FilterTypeDef],
+        "NextToken": str,
+        "MaxRecords": int,
     },
     total=False,
 )
 
 _RequiredAutoScalingInstanceDetailsTypeDef = TypedDict(
     "_RequiredAutoScalingInstanceDetailsTypeDef",
     {
@@ -1916,31 +1931,31 @@
 
 
 TagsTypeTypeDef = TypedDict(
     "TagsTypeTypeDef",
     {
         "Tags": List[TagDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDeleteScheduledActionAnswerTypeDef = TypedDict(
     "BatchDeleteScheduledActionAnswerTypeDef",
     {
         "FailedScheduledActions": List[FailedScheduledUpdateGroupActionRequestTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchPutScheduledUpdateGroupActionAnswerTypeDef = TypedDict(
     "BatchPutScheduledUpdateGroupActionAnswerTypeDef",
     {
         "FailedScheduledUpdateGroupActions": List[FailedScheduledUpdateGroupActionRequestTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchPutScheduledUpdateGroupActionTypeRequestTypeDef = TypedDict(
     "BatchPutScheduledUpdateGroupActionTypeRequestTypeDef",
     {
         "AutoScalingGroupName": str,
@@ -2005,60 +2020,60 @@
     pass
 
 
 DescribeLifecycleHooksAnswerTypeDef = TypedDict(
     "DescribeLifecycleHooksAnswerTypeDef",
     {
         "LifecycleHooks": List[LifecycleHookTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeLoadBalancerTargetGroupsResponseTypeDef = TypedDict(
     "DescribeLoadBalancerTargetGroupsResponseTypeDef",
     {
         "LoadBalancerTargetGroups": List[LoadBalancerTargetGroupStateTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeLoadBalancersResponseTypeDef = TypedDict(
     "DescribeLoadBalancersResponseTypeDef",
     {
         "LoadBalancers": List[LoadBalancerStateTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeMetricCollectionTypesAnswerTypeDef = TypedDict(
     "DescribeMetricCollectionTypesAnswerTypeDef",
     {
         "Metrics": List[MetricCollectionTypeTypeDef],
         "Granularities": List[MetricGranularityTypeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeNotificationConfigurationsAnswerTypeDef = TypedDict(
     "DescribeNotificationConfigurationsAnswerTypeDef",
     {
         "NotificationConfigurations": List[NotificationConfigurationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeTrafficSourcesResponseTypeDef = TypedDict(
     "DescribeTrafficSourcesResponseTypeDef",
     {
         "TrafficSources": List[TrafficSourceStateTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InstanceRefreshProgressDetailsTypeDef = TypedDict(
     "InstanceRefreshProgressDetailsTypeDef",
     {
         "LivePoolProgress": InstanceRefreshLivePoolProgressTypeDef,
@@ -2145,33 +2160,33 @@
     total=False,
 )
 
 ProcessesTypeTypeDef = TypedDict(
     "ProcessesTypeTypeDef",
     {
         "Processes": List[ProcessTypeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ScheduledActionsTypeTypeDef = TypedDict(
     "ScheduledActionsTypeTypeDef",
     {
         "ScheduledUpdateGroupActions": List[ScheduledUpdateGroupActionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AutoScalingInstancesTypeTypeDef = TypedDict(
     "AutoScalingInstancesTypeTypeDef",
     {
         "AutoScalingInstances": List[AutoScalingInstanceDetailsTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateLaunchConfigurationTypeRequestTypeDef = TypedDict(
     "_RequiredCreateLaunchConfigurationTypeRequestTypeDef",
     {
         "LaunchConfigurationName": str,
@@ -2316,24 +2331,24 @@
 
 DescribeWarmPoolAnswerTypeDef = TypedDict(
     "DescribeWarmPoolAnswerTypeDef",
     {
         "WarmPoolConfiguration": WarmPoolConfigurationTypeDef,
         "Instances": List[InstanceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LaunchConfigurationsTypeTypeDef = TypedDict(
     "LaunchConfigurationsTypeTypeDef",
     {
         "LaunchConfigurations": List[LaunchConfigurationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredMetricDataQueryTypeDef = TypedDict(
     "_RequiredMetricDataQueryTypeDef",
     {
         "Id": str,
@@ -2663,15 +2678,15 @@
 
 
 AutoScalingGroupsTypeTypeDef = TypedDict(
     "AutoScalingGroupsTypeTypeDef",
     {
         "AutoScalingGroups": List[AutoScalingGroupTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InstanceRefreshTypeDef = TypedDict(
     "InstanceRefreshTypeDef",
     {
         "InstanceRefreshId": str,
@@ -2715,15 +2730,15 @@
 
 GetPredictiveScalingForecastAnswerTypeDef = TypedDict(
     "GetPredictiveScalingForecastAnswerTypeDef",
     {
         "LoadForecast": List[LoadForecastTypeDef],
         "CapacityForecast": CapacityForecastTypeDef,
         "UpdateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutScalingPolicyTypeRequestTypeDef = TypedDict(
     "_RequiredPutScalingPolicyTypeRequestTypeDef",
     {
         "AutoScalingGroupName": str,
@@ -2780,19 +2795,19 @@
 )
 
 DescribeInstanceRefreshesAnswerTypeDef = TypedDict(
     "DescribeInstanceRefreshesAnswerTypeDef",
     {
         "InstanceRefreshes": List[InstanceRefreshTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PoliciesTypeTypeDef = TypedDict(
     "PoliciesTypeTypeDef",
     {
         "ScalingPolicies": List[ScalingPolicyTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-autoscaling-2.5.0.post1/types_aiobotocore_autoscaling/type_defs.pyi` & `types-aiobotocore-autoscaling-2.5.1/types_aiobotocore_autoscaling/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -51,68 +51,79 @@
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AcceleratorCountRequestTypeDef",
     "AcceleratorTotalMemoryMiBRequestTypeDef",
     "ActivityTypeDef",
-    "ResponseMetadataTypeDef",
     "AdjustmentTypeTypeDef",
     "AlarmTypeDef",
     "AttachInstancesQueryRequestTypeDef",
     "AttachLoadBalancerTargetGroupsTypeRequestTypeDef",
     "AttachLoadBalancersTypeRequestTypeDef",
     "TrafficSourceIdentifierTypeDef",
     "FilterTypeDef",
-    "PaginatorConfigTypeDef",
     "EnabledMetricTypeDef",
     "LaunchTemplateSpecificationTypeDef",
     "SuspendedProcessTypeDef",
     "TagDescriptionTypeDef",
     "BaselineEbsBandwidthMbpsRequestTypeDef",
     "FailedScheduledUpdateGroupActionRequestTypeDef",
     "BatchDeleteScheduledActionTypeRequestTypeDef",
     "ScheduledUpdateGroupActionRequestTypeDef",
     "EbsTypeDef",
+    "CancelInstanceRefreshAnswerTypeDef",
     "CancelInstanceRefreshTypeRequestTypeDef",
     "CapacityForecastTypeDef",
     "CompleteLifecycleActionTypeRequestTypeDef",
     "LifecycleHookSpecificationTypeDef",
     "TagTypeDef",
     "InstanceMetadataOptionsTypeDef",
     "InstanceMonitoringTypeDef",
     "MetricDimensionTypeDef",
     "DeleteAutoScalingGroupTypeRequestTypeDef",
     "DeleteLifecycleHookTypeRequestTypeDef",
     "DeleteNotificationConfigurationTypeRequestTypeDef",
     "DeletePolicyTypeRequestTypeDef",
     "DeleteScheduledActionTypeRequestTypeDef",
     "DeleteWarmPoolTypeRequestTypeDef",
+    "DescribeAccountLimitsAnswerTypeDef",
+    "DescribeAutoScalingInstancesTypeDescribeAutoScalingInstancesPaginateTypeDef",
     "DescribeAutoScalingInstancesTypeRequestTypeDef",
+    "DescribeAutoScalingNotificationTypesAnswerTypeDef",
     "DescribeInstanceRefreshesTypeRequestTypeDef",
+    "DescribeLifecycleHookTypesAnswerTypeDef",
     "LifecycleHookTypeDef",
     "DescribeLifecycleHooksTypeRequestTypeDef",
+    "DescribeLoadBalancerTargetGroupsRequestDescribeLoadBalancerTargetGroupsPaginateTypeDef",
     "DescribeLoadBalancerTargetGroupsRequestRequestTypeDef",
     "LoadBalancerTargetGroupStateTypeDef",
+    "DescribeLoadBalancersRequestDescribeLoadBalancersPaginateTypeDef",
     "DescribeLoadBalancersRequestRequestTypeDef",
     "LoadBalancerStateTypeDef",
     "MetricCollectionTypeTypeDef",
     "MetricGranularityTypeTypeDef",
     "NotificationConfigurationTypeDef",
+    "DescribeNotificationConfigurationsTypeDescribeNotificationConfigurationsPaginateTypeDef",
     "DescribeNotificationConfigurationsTypeRequestTypeDef",
+    "DescribePoliciesTypeDescribePoliciesPaginateTypeDef",
     "DescribePoliciesTypeRequestTypeDef",
+    "DescribeScalingActivitiesTypeDescribeScalingActivitiesPaginateTypeDef",
     "DescribeScalingActivitiesTypeRequestTypeDef",
+    "DescribeScheduledActionsTypeDescribeScheduledActionsPaginateTypeDef",
     "DescribeScheduledActionsTypeRequestTypeDef",
+    "DescribeTerminationPolicyTypesAnswerTypeDef",
     "DescribeTrafficSourcesRequestRequestTypeDef",
     "TrafficSourceStateTypeDef",
     "DescribeWarmPoolTypeRequestTypeDef",
     "DetachInstancesQueryRequestTypeDef",
     "DetachLoadBalancerTargetGroupsTypeRequestTypeDef",
     "DetachLoadBalancersTypeRequestTypeDef",
     "DisableMetricsCollectionQueryRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EnableMetricsCollectionQueryRequestTypeDef",
     "EnterStandbyQueryRequestTypeDef",
     "ExecutePolicyTypeRequestTypeDef",
     "ExitStandbyQueryRequestTypeDef",
     "GetPredictiveScalingForecastTypeRequestTypeDef",
     "InstanceRefreshLivePoolProgressTypeDef",
     "InstanceRefreshWarmPoolProgressTypeDef",
@@ -122,61 +133,50 @@
     "NetworkBandwidthGbpsRequestTypeDef",
     "NetworkInterfaceCountRequestTypeDef",
     "TotalLocalStorageGBRequestTypeDef",
     "VCpuCountRequestTypeDef",
     "InstanceReusePolicyTypeDef",
     "InstancesDistributionTypeDef",
     "LaunchConfigurationNameTypeRequestTypeDef",
+    "LaunchConfigurationNamesTypeDescribeLaunchConfigurationsPaginateTypeDef",
     "LaunchConfigurationNamesTypeRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "PredefinedMetricSpecificationTypeDef",
     "PredictiveScalingPredefinedLoadMetricTypeDef",
     "PredictiveScalingPredefinedMetricPairTypeDef",
     "PredictiveScalingPredefinedScalingMetricTypeDef",
     "ProcessTypeTypeDef",
     "PutLifecycleHookTypeRequestTypeDef",
     "PutNotificationConfigurationTypeRequestTypeDef",
     "StepAdjustmentTypeDef",
     "PutScheduledUpdateGroupActionTypeRequestTypeDef",
     "RecordLifecycleActionHeartbeatTypeRequestTypeDef",
+    "ResponseMetadataTypeDef",
+    "RollbackInstanceRefreshAnswerTypeDef",
     "RollbackInstanceRefreshTypeRequestTypeDef",
     "ScalingProcessQueryRequestTypeDef",
     "ScheduledUpdateGroupActionTypeDef",
     "SetDesiredCapacityTypeRequestTypeDef",
     "SetInstanceHealthQueryRequestTypeDef",
     "SetInstanceProtectionQueryRequestTypeDef",
+    "StartInstanceRefreshAnswerTypeDef",
     "TerminateInstanceInAutoScalingGroupTypeRequestTypeDef",
     "ActivitiesTypeTypeDef",
     "ActivityTypeTypeDef",
-    "CancelInstanceRefreshAnswerTypeDef",
-    "DescribeAccountLimitsAnswerTypeDef",
-    "DescribeAutoScalingNotificationTypesAnswerTypeDef",
-    "DescribeLifecycleHookTypesAnswerTypeDef",
-    "DescribeTerminationPolicyTypesAnswerTypeDef",
     "DetachInstancesAnswerTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "EnterStandbyAnswerTypeDef",
     "ExitStandbyAnswerTypeDef",
-    "RollbackInstanceRefreshAnswerTypeDef",
-    "StartInstanceRefreshAnswerTypeDef",
     "DescribeAdjustmentTypesAnswerTypeDef",
     "PolicyARNTypeTypeDef",
     "AttachTrafficSourcesTypeRequestTypeDef",
     "DetachTrafficSourcesTypeRequestTypeDef",
-    "AutoScalingGroupNamesTypeRequestTypeDef",
-    "DescribeTagsTypeRequestTypeDef",
     "AutoScalingGroupNamesTypeDescribeAutoScalingGroupsPaginateTypeDef",
-    "DescribeAutoScalingInstancesTypeDescribeAutoScalingInstancesPaginateTypeDef",
-    "DescribeLoadBalancerTargetGroupsRequestDescribeLoadBalancerTargetGroupsPaginateTypeDef",
-    "DescribeLoadBalancersRequestDescribeLoadBalancersPaginateTypeDef",
-    "DescribeNotificationConfigurationsTypeDescribeNotificationConfigurationsPaginateTypeDef",
-    "DescribePoliciesTypeDescribePoliciesPaginateTypeDef",
-    "DescribeScalingActivitiesTypeDescribeScalingActivitiesPaginateTypeDef",
-    "DescribeScheduledActionsTypeDescribeScheduledActionsPaginateTypeDef",
+    "AutoScalingGroupNamesTypeRequestTypeDef",
     "DescribeTagsTypeDescribeTagsPaginateTypeDef",
-    "LaunchConfigurationNamesTypeDescribeLaunchConfigurationsPaginateTypeDef",
+    "DescribeTagsTypeRequestTypeDef",
     "AutoScalingInstanceDetailsTypeDef",
     "InstanceTypeDef",
     "TagsTypeTypeDef",
     "BatchDeleteScheduledActionAnswerTypeDef",
     "BatchPutScheduledUpdateGroupActionAnswerTypeDef",
     "BatchPutScheduledUpdateGroupActionTypeRequestTypeDef",
     "BlockDeviceMappingTypeDef",
@@ -271,25 +271,14 @@
     },
     total=False,
 )
 
 class ActivityTypeDef(_RequiredActivityTypeDef, _OptionalActivityTypeDef):
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
 AdjustmentTypeTypeDef = TypedDict(
     "AdjustmentTypeTypeDef",
     {
         "AdjustmentType": str,
     },
     total=False,
 )
@@ -334,41 +323,42 @@
     "AttachLoadBalancersTypeRequestTypeDef",
     {
         "AutoScalingGroupName": str,
         "LoadBalancerNames": Sequence[str],
     },
 )
 
-TrafficSourceIdentifierTypeDef = TypedDict(
-    "TrafficSourceIdentifierTypeDef",
+_RequiredTrafficSourceIdentifierTypeDef = TypedDict(
+    "_RequiredTrafficSourceIdentifierTypeDef",
     {
         "Identifier": str,
     },
+)
+_OptionalTrafficSourceIdentifierTypeDef = TypedDict(
+    "_OptionalTrafficSourceIdentifierTypeDef",
+    {
+        "Type": str,
+    },
     total=False,
 )
 
+class TrafficSourceIdentifierTypeDef(
+    _RequiredTrafficSourceIdentifierTypeDef, _OptionalTrafficSourceIdentifierTypeDef
+):
+    pass
+
 FilterTypeDef = TypedDict(
     "FilterTypeDef",
     {
         "Name": str,
         "Values": Sequence[str],
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
-    {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
-    },
-    total=False,
-)
-
 EnabledMetricTypeDef = TypedDict(
     "EnabledMetricTypeDef",
     {
         "Metric": str,
         "Granularity": str,
     },
     total=False,
@@ -479,14 +469,22 @@
         "Iops": int,
         "Encrypted": bool,
         "Throughput": int,
     },
     total=False,
 )
 
+CancelInstanceRefreshAnswerTypeDef = TypedDict(
+    "CancelInstanceRefreshAnswerTypeDef",
+    {
+        "InstanceRefreshId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CancelInstanceRefreshTypeRequestTypeDef = TypedDict(
     "CancelInstanceRefreshTypeRequestTypeDef",
     {
         "AutoScalingGroupName": str,
     },
 )
 
@@ -669,24 +667,52 @@
 )
 
 class DeleteWarmPoolTypeRequestTypeDef(
     _RequiredDeleteWarmPoolTypeRequestTypeDef, _OptionalDeleteWarmPoolTypeRequestTypeDef
 ):
     pass
 
+DescribeAccountLimitsAnswerTypeDef = TypedDict(
+    "DescribeAccountLimitsAnswerTypeDef",
+    {
+        "MaxNumberOfAutoScalingGroups": int,
+        "MaxNumberOfLaunchConfigurations": int,
+        "NumberOfAutoScalingGroups": int,
+        "NumberOfLaunchConfigurations": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+DescribeAutoScalingInstancesTypeDescribeAutoScalingInstancesPaginateTypeDef = TypedDict(
+    "DescribeAutoScalingInstancesTypeDescribeAutoScalingInstancesPaginateTypeDef",
+    {
+        "InstanceIds": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeAutoScalingInstancesTypeRequestTypeDef = TypedDict(
     "DescribeAutoScalingInstancesTypeRequestTypeDef",
     {
         "InstanceIds": Sequence[str],
         "MaxRecords": int,
         "NextToken": str,
     },
     total=False,
 )
 
+DescribeAutoScalingNotificationTypesAnswerTypeDef = TypedDict(
+    "DescribeAutoScalingNotificationTypesAnswerTypeDef",
+    {
+        "AutoScalingNotificationTypes": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDescribeInstanceRefreshesTypeRequestTypeDef = TypedDict(
     "_RequiredDescribeInstanceRefreshesTypeRequestTypeDef",
     {
         "AutoScalingGroupName": str,
     },
 )
 _OptionalDescribeInstanceRefreshesTypeRequestTypeDef = TypedDict(
@@ -701,14 +727,22 @@
 
 class DescribeInstanceRefreshesTypeRequestTypeDef(
     _RequiredDescribeInstanceRefreshesTypeRequestTypeDef,
     _OptionalDescribeInstanceRefreshesTypeRequestTypeDef,
 ):
     pass
 
+DescribeLifecycleHookTypesAnswerTypeDef = TypedDict(
+    "DescribeLifecycleHookTypesAnswerTypeDef",
+    {
+        "LifecycleHookTypes": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 LifecycleHookTypeDef = TypedDict(
     "LifecycleHookTypeDef",
     {
         "LifecycleHookName": str,
         "AutoScalingGroupName": str,
         "LifecycleTransition": str,
         "NotificationTargetARN": str,
@@ -737,14 +771,34 @@
 
 class DescribeLifecycleHooksTypeRequestTypeDef(
     _RequiredDescribeLifecycleHooksTypeRequestTypeDef,
     _OptionalDescribeLifecycleHooksTypeRequestTypeDef,
 ):
     pass
 
+_RequiredDescribeLoadBalancerTargetGroupsRequestDescribeLoadBalancerTargetGroupsPaginateTypeDef = TypedDict(
+    "_RequiredDescribeLoadBalancerTargetGroupsRequestDescribeLoadBalancerTargetGroupsPaginateTypeDef",
+    {
+        "AutoScalingGroupName": str,
+    },
+)
+_OptionalDescribeLoadBalancerTargetGroupsRequestDescribeLoadBalancerTargetGroupsPaginateTypeDef = TypedDict(
+    "_OptionalDescribeLoadBalancerTargetGroupsRequestDescribeLoadBalancerTargetGroupsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeLoadBalancerTargetGroupsRequestDescribeLoadBalancerTargetGroupsPaginateTypeDef(
+    _RequiredDescribeLoadBalancerTargetGroupsRequestDescribeLoadBalancerTargetGroupsPaginateTypeDef,
+    _OptionalDescribeLoadBalancerTargetGroupsRequestDescribeLoadBalancerTargetGroupsPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeLoadBalancerTargetGroupsRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeLoadBalancerTargetGroupsRequestRequestTypeDef",
     {
         "AutoScalingGroupName": str,
     },
 )
 _OptionalDescribeLoadBalancerTargetGroupsRequestRequestTypeDef = TypedDict(
@@ -767,14 +821,34 @@
     {
         "LoadBalancerTargetGroupARN": str,
         "State": str,
     },
     total=False,
 )
 
+_RequiredDescribeLoadBalancersRequestDescribeLoadBalancersPaginateTypeDef = TypedDict(
+    "_RequiredDescribeLoadBalancersRequestDescribeLoadBalancersPaginateTypeDef",
+    {
+        "AutoScalingGroupName": str,
+    },
+)
+_OptionalDescribeLoadBalancersRequestDescribeLoadBalancersPaginateTypeDef = TypedDict(
+    "_OptionalDescribeLoadBalancersRequestDescribeLoadBalancersPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class DescribeLoadBalancersRequestDescribeLoadBalancersPaginateTypeDef(
+    _RequiredDescribeLoadBalancersRequestDescribeLoadBalancersPaginateTypeDef,
+    _OptionalDescribeLoadBalancersRequestDescribeLoadBalancersPaginateTypeDef,
+):
+    pass
+
 _RequiredDescribeLoadBalancersRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeLoadBalancersRequestRequestTypeDef",
     {
         "AutoScalingGroupName": str,
     },
 )
 _OptionalDescribeLoadBalancersRequestRequestTypeDef = TypedDict(
@@ -823,71 +897,122 @@
         "AutoScalingGroupName": str,
         "TopicARN": str,
         "NotificationType": str,
     },
     total=False,
 )
 
+DescribeNotificationConfigurationsTypeDescribeNotificationConfigurationsPaginateTypeDef = TypedDict(
+    "DescribeNotificationConfigurationsTypeDescribeNotificationConfigurationsPaginateTypeDef",
+    {
+        "AutoScalingGroupNames": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeNotificationConfigurationsTypeRequestTypeDef = TypedDict(
     "DescribeNotificationConfigurationsTypeRequestTypeDef",
     {
         "AutoScalingGroupNames": Sequence[str],
         "NextToken": str,
         "MaxRecords": int,
     },
     total=False,
 )
 
+DescribePoliciesTypeDescribePoliciesPaginateTypeDef = TypedDict(
+    "DescribePoliciesTypeDescribePoliciesPaginateTypeDef",
+    {
+        "AutoScalingGroupName": str,
+        "PolicyNames": Sequence[str],
+        "PolicyTypes": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribePoliciesTypeRequestTypeDef = TypedDict(
     "DescribePoliciesTypeRequestTypeDef",
     {
         "AutoScalingGroupName": str,
         "PolicyNames": Sequence[str],
         "PolicyTypes": Sequence[str],
         "NextToken": str,
         "MaxRecords": int,
     },
     total=False,
 )
 
+DescribeScalingActivitiesTypeDescribeScalingActivitiesPaginateTypeDef = TypedDict(
+    "DescribeScalingActivitiesTypeDescribeScalingActivitiesPaginateTypeDef",
+    {
+        "ActivityIds": Sequence[str],
+        "AutoScalingGroupName": str,
+        "IncludeDeletedGroups": bool,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeScalingActivitiesTypeRequestTypeDef = TypedDict(
     "DescribeScalingActivitiesTypeRequestTypeDef",
     {
         "ActivityIds": Sequence[str],
         "AutoScalingGroupName": str,
         "IncludeDeletedGroups": bool,
         "MaxRecords": int,
         "NextToken": str,
     },
     total=False,
 )
 
+DescribeScheduledActionsTypeDescribeScheduledActionsPaginateTypeDef = TypedDict(
+    "DescribeScheduledActionsTypeDescribeScheduledActionsPaginateTypeDef",
+    {
+        "AutoScalingGroupName": str,
+        "ScheduledActionNames": Sequence[str],
+        "StartTime": Union[datetime, str],
+        "EndTime": Union[datetime, str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeScheduledActionsTypeRequestTypeDef = TypedDict(
     "DescribeScheduledActionsTypeRequestTypeDef",
     {
         "AutoScalingGroupName": str,
         "ScheduledActionNames": Sequence[str],
         "StartTime": Union[datetime, str],
         "EndTime": Union[datetime, str],
         "NextToken": str,
         "MaxRecords": int,
     },
     total=False,
 )
 
+DescribeTerminationPolicyTypesAnswerTypeDef = TypedDict(
+    "DescribeTerminationPolicyTypesAnswerTypeDef",
+    {
+        "TerminationPolicyTypes": List[str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDescribeTrafficSourcesRequestRequestTypeDef = TypedDict(
     "_RequiredDescribeTrafficSourcesRequestRequestTypeDef",
     {
         "AutoScalingGroupName": str,
-        "TrafficSourceType": str,
     },
 )
 _OptionalDescribeTrafficSourcesRequestRequestTypeDef = TypedDict(
     "_OptionalDescribeTrafficSourcesRequestRequestTypeDef",
     {
+        "TrafficSourceType": str,
         "NextToken": str,
         "MaxRecords": int,
     },
     total=False,
 )
 
 class DescribeTrafficSourcesRequestRequestTypeDef(
@@ -897,14 +1022,16 @@
     pass
 
 TrafficSourceStateTypeDef = TypedDict(
     "TrafficSourceStateTypeDef",
     {
         "TrafficSource": str,
         "State": str,
+        "Identifier": str,
+        "Type": str,
     },
     total=False,
 )
 
 _RequiredDescribeWarmPoolTypeRequestTypeDef = TypedDict(
     "_RequiredDescribeWarmPoolTypeRequestTypeDef",
     {
@@ -977,14 +1104,21 @@
 
 class DisableMetricsCollectionQueryRequestTypeDef(
     _RequiredDisableMetricsCollectionQueryRequestTypeDef,
     _OptionalDisableMetricsCollectionQueryRequestTypeDef,
 ):
     pass
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredEnableMetricsCollectionQueryRequestTypeDef = TypedDict(
     "_RequiredEnableMetricsCollectionQueryRequestTypeDef",
     {
         "AutoScalingGroupName": str,
         "Granularity": str,
     },
 )
@@ -1200,24 +1334,43 @@
 LaunchConfigurationNameTypeRequestTypeDef = TypedDict(
     "LaunchConfigurationNameTypeRequestTypeDef",
     {
         "LaunchConfigurationName": str,
     },
 )
 
+LaunchConfigurationNamesTypeDescribeLaunchConfigurationsPaginateTypeDef = TypedDict(
+    "LaunchConfigurationNamesTypeDescribeLaunchConfigurationsPaginateTypeDef",
+    {
+        "LaunchConfigurationNames": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 LaunchConfigurationNamesTypeRequestTypeDef = TypedDict(
     "LaunchConfigurationNamesTypeRequestTypeDef",
     {
         "LaunchConfigurationNames": Sequence[str],
         "NextToken": str,
         "MaxRecords": int,
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
 _RequiredPredefinedMetricSpecificationTypeDef = TypedDict(
     "_RequiredPredefinedMetricSpecificationTypeDef",
     {
         "PredefinedMetricType": MetricTypeType,
     },
 )
 _OptionalPredefinedMetricSpecificationTypeDef = TypedDict(
@@ -1398,14 +1551,33 @@
 
 class RecordLifecycleActionHeartbeatTypeRequestTypeDef(
     _RequiredRecordLifecycleActionHeartbeatTypeRequestTypeDef,
     _OptionalRecordLifecycleActionHeartbeatTypeRequestTypeDef,
 ):
     pass
 
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
+RollbackInstanceRefreshAnswerTypeDef = TypedDict(
+    "RollbackInstanceRefreshAnswerTypeDef",
+    {
+        "InstanceRefreshId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RollbackInstanceRefreshTypeRequestTypeDef = TypedDict(
     "RollbackInstanceRefreshTypeRequestTypeDef",
     {
         "AutoScalingGroupName": str,
     },
     total=False,
 )
@@ -1492,143 +1664,85 @@
     {
         "InstanceIds": Sequence[str],
         "AutoScalingGroupName": str,
         "ProtectedFromScaleIn": bool,
     },
 )
 
+StartInstanceRefreshAnswerTypeDef = TypedDict(
+    "StartInstanceRefreshAnswerTypeDef",
+    {
+        "InstanceRefreshId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TerminateInstanceInAutoScalingGroupTypeRequestTypeDef = TypedDict(
     "TerminateInstanceInAutoScalingGroupTypeRequestTypeDef",
     {
         "InstanceId": str,
         "ShouldDecrementDesiredCapacity": bool,
     },
 )
 
 ActivitiesTypeTypeDef = TypedDict(
     "ActivitiesTypeTypeDef",
     {
         "Activities": List[ActivityTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ActivityTypeTypeDef = TypedDict(
     "ActivityTypeTypeDef",
     {
         "Activity": ActivityTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CancelInstanceRefreshAnswerTypeDef = TypedDict(
-    "CancelInstanceRefreshAnswerTypeDef",
-    {
-        "InstanceRefreshId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeAccountLimitsAnswerTypeDef = TypedDict(
-    "DescribeAccountLimitsAnswerTypeDef",
-    {
-        "MaxNumberOfAutoScalingGroups": int,
-        "MaxNumberOfLaunchConfigurations": int,
-        "NumberOfAutoScalingGroups": int,
-        "NumberOfLaunchConfigurations": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeAutoScalingNotificationTypesAnswerTypeDef = TypedDict(
-    "DescribeAutoScalingNotificationTypesAnswerTypeDef",
-    {
-        "AutoScalingNotificationTypes": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeLifecycleHookTypesAnswerTypeDef = TypedDict(
-    "DescribeLifecycleHookTypesAnswerTypeDef",
-    {
-        "LifecycleHookTypes": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeTerminationPolicyTypesAnswerTypeDef = TypedDict(
-    "DescribeTerminationPolicyTypesAnswerTypeDef",
-    {
-        "TerminationPolicyTypes": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DetachInstancesAnswerTypeDef = TypedDict(
     "DetachInstancesAnswerTypeDef",
     {
         "Activities": List[ActivityTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
-    {
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EnterStandbyAnswerTypeDef = TypedDict(
     "EnterStandbyAnswerTypeDef",
     {
         "Activities": List[ActivityTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ExitStandbyAnswerTypeDef = TypedDict(
     "ExitStandbyAnswerTypeDef",
     {
         "Activities": List[ActivityTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-RollbackInstanceRefreshAnswerTypeDef = TypedDict(
-    "RollbackInstanceRefreshAnswerTypeDef",
-    {
-        "InstanceRefreshId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StartInstanceRefreshAnswerTypeDef = TypedDict(
-    "StartInstanceRefreshAnswerTypeDef",
-    {
-        "InstanceRefreshId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAdjustmentTypesAnswerTypeDef = TypedDict(
     "DescribeAdjustmentTypesAnswerTypeDef",
     {
         "AdjustmentTypes": List[AdjustmentTypeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PolicyARNTypeTypeDef = TypedDict(
     "PolicyARNTypeTypeDef",
     {
         "PolicyARN": str,
         "Alarms": List[AlarmTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AttachTrafficSourcesTypeRequestTypeDef = TypedDict(
     "AttachTrafficSourcesTypeRequestTypeDef",
     {
         "AutoScalingGroupName": str,
@@ -1640,151 +1754,50 @@
     "DetachTrafficSourcesTypeRequestTypeDef",
     {
         "AutoScalingGroupName": str,
         "TrafficSources": Sequence[TrafficSourceIdentifierTypeDef],
     },
 )
 
-AutoScalingGroupNamesTypeRequestTypeDef = TypedDict(
-    "AutoScalingGroupNamesTypeRequestTypeDef",
-    {
-        "AutoScalingGroupNames": Sequence[str],
-        "NextToken": str,
-        "MaxRecords": int,
-        "Filters": Sequence[FilterTypeDef],
-    },
-    total=False,
-)
-
-DescribeTagsTypeRequestTypeDef = TypedDict(
-    "DescribeTagsTypeRequestTypeDef",
-    {
-        "Filters": Sequence[FilterTypeDef],
-        "NextToken": str,
-        "MaxRecords": int,
-    },
-    total=False,
-)
-
 AutoScalingGroupNamesTypeDescribeAutoScalingGroupsPaginateTypeDef = TypedDict(
     "AutoScalingGroupNamesTypeDescribeAutoScalingGroupsPaginateTypeDef",
     {
         "AutoScalingGroupNames": Sequence[str],
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeAutoScalingInstancesTypeDescribeAutoScalingInstancesPaginateTypeDef = TypedDict(
-    "DescribeAutoScalingInstancesTypeDescribeAutoScalingInstancesPaginateTypeDef",
-    {
-        "InstanceIds": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredDescribeLoadBalancerTargetGroupsRequestDescribeLoadBalancerTargetGroupsPaginateTypeDef = TypedDict(
-    "_RequiredDescribeLoadBalancerTargetGroupsRequestDescribeLoadBalancerTargetGroupsPaginateTypeDef",
-    {
-        "AutoScalingGroupName": str,
-    },
-)
-_OptionalDescribeLoadBalancerTargetGroupsRequestDescribeLoadBalancerTargetGroupsPaginateTypeDef = TypedDict(
-    "_OptionalDescribeLoadBalancerTargetGroupsRequestDescribeLoadBalancerTargetGroupsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class DescribeLoadBalancerTargetGroupsRequestDescribeLoadBalancerTargetGroupsPaginateTypeDef(
-    _RequiredDescribeLoadBalancerTargetGroupsRequestDescribeLoadBalancerTargetGroupsPaginateTypeDef,
-    _OptionalDescribeLoadBalancerTargetGroupsRequestDescribeLoadBalancerTargetGroupsPaginateTypeDef,
-):
-    pass
-
-_RequiredDescribeLoadBalancersRequestDescribeLoadBalancersPaginateTypeDef = TypedDict(
-    "_RequiredDescribeLoadBalancersRequestDescribeLoadBalancersPaginateTypeDef",
-    {
-        "AutoScalingGroupName": str,
-    },
-)
-_OptionalDescribeLoadBalancersRequestDescribeLoadBalancersPaginateTypeDef = TypedDict(
-    "_OptionalDescribeLoadBalancersRequestDescribeLoadBalancersPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-class DescribeLoadBalancersRequestDescribeLoadBalancersPaginateTypeDef(
-    _RequiredDescribeLoadBalancersRequestDescribeLoadBalancersPaginateTypeDef,
-    _OptionalDescribeLoadBalancersRequestDescribeLoadBalancersPaginateTypeDef,
-):
-    pass
-
-DescribeNotificationConfigurationsTypeDescribeNotificationConfigurationsPaginateTypeDef = TypedDict(
-    "DescribeNotificationConfigurationsTypeDescribeNotificationConfigurationsPaginateTypeDef",
+AutoScalingGroupNamesTypeRequestTypeDef = TypedDict(
+    "AutoScalingGroupNamesTypeRequestTypeDef",
     {
         "AutoScalingGroupNames": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribePoliciesTypeDescribePoliciesPaginateTypeDef = TypedDict(
-    "DescribePoliciesTypeDescribePoliciesPaginateTypeDef",
-    {
-        "AutoScalingGroupName": str,
-        "PolicyNames": Sequence[str],
-        "PolicyTypes": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeScalingActivitiesTypeDescribeScalingActivitiesPaginateTypeDef = TypedDict(
-    "DescribeScalingActivitiesTypeDescribeScalingActivitiesPaginateTypeDef",
-    {
-        "ActivityIds": Sequence[str],
-        "AutoScalingGroupName": str,
-        "IncludeDeletedGroups": bool,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeScheduledActionsTypeDescribeScheduledActionsPaginateTypeDef = TypedDict(
-    "DescribeScheduledActionsTypeDescribeScheduledActionsPaginateTypeDef",
-    {
-        "AutoScalingGroupName": str,
-        "ScheduledActionNames": Sequence[str],
-        "StartTime": Union[datetime, str],
-        "EndTime": Union[datetime, str],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "NextToken": str,
+        "MaxRecords": int,
+        "Filters": Sequence[FilterTypeDef],
     },
     total=False,
 )
 
 DescribeTagsTypeDescribeTagsPaginateTypeDef = TypedDict(
     "DescribeTagsTypeDescribeTagsPaginateTypeDef",
     {
         "Filters": Sequence[FilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
-LaunchConfigurationNamesTypeDescribeLaunchConfigurationsPaginateTypeDef = TypedDict(
-    "LaunchConfigurationNamesTypeDescribeLaunchConfigurationsPaginateTypeDef",
+DescribeTagsTypeRequestTypeDef = TypedDict(
+    "DescribeTagsTypeRequestTypeDef",
     {
-        "LaunchConfigurationNames": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "Filters": Sequence[FilterTypeDef],
+        "NextToken": str,
+        "MaxRecords": int,
     },
     total=False,
 )
 
 _RequiredAutoScalingInstanceDetailsTypeDef = TypedDict(
     "_RequiredAutoScalingInstanceDetailsTypeDef",
     {
@@ -1837,31 +1850,31 @@
     pass
 
 TagsTypeTypeDef = TypedDict(
     "TagsTypeTypeDef",
     {
         "Tags": List[TagDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchDeleteScheduledActionAnswerTypeDef = TypedDict(
     "BatchDeleteScheduledActionAnswerTypeDef",
     {
         "FailedScheduledActions": List[FailedScheduledUpdateGroupActionRequestTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchPutScheduledUpdateGroupActionAnswerTypeDef = TypedDict(
     "BatchPutScheduledUpdateGroupActionAnswerTypeDef",
     {
         "FailedScheduledUpdateGroupActions": List[FailedScheduledUpdateGroupActionRequestTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchPutScheduledUpdateGroupActionTypeRequestTypeDef = TypedDict(
     "BatchPutScheduledUpdateGroupActionTypeRequestTypeDef",
     {
         "AutoScalingGroupName": str,
@@ -1922,60 +1935,60 @@
 class MetricTypeDef(_RequiredMetricTypeDef, _OptionalMetricTypeDef):
     pass
 
 DescribeLifecycleHooksAnswerTypeDef = TypedDict(
     "DescribeLifecycleHooksAnswerTypeDef",
     {
         "LifecycleHooks": List[LifecycleHookTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeLoadBalancerTargetGroupsResponseTypeDef = TypedDict(
     "DescribeLoadBalancerTargetGroupsResponseTypeDef",
     {
         "LoadBalancerTargetGroups": List[LoadBalancerTargetGroupStateTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeLoadBalancersResponseTypeDef = TypedDict(
     "DescribeLoadBalancersResponseTypeDef",
     {
         "LoadBalancers": List[LoadBalancerStateTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeMetricCollectionTypesAnswerTypeDef = TypedDict(
     "DescribeMetricCollectionTypesAnswerTypeDef",
     {
         "Metrics": List[MetricCollectionTypeTypeDef],
         "Granularities": List[MetricGranularityTypeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeNotificationConfigurationsAnswerTypeDef = TypedDict(
     "DescribeNotificationConfigurationsAnswerTypeDef",
     {
         "NotificationConfigurations": List[NotificationConfigurationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeTrafficSourcesResponseTypeDef = TypedDict(
     "DescribeTrafficSourcesResponseTypeDef",
     {
         "TrafficSources": List[TrafficSourceStateTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InstanceRefreshProgressDetailsTypeDef = TypedDict(
     "InstanceRefreshProgressDetailsTypeDef",
     {
         "LivePoolProgress": InstanceRefreshLivePoolProgressTypeDef,
@@ -2058,33 +2071,33 @@
     total=False,
 )
 
 ProcessesTypeTypeDef = TypedDict(
     "ProcessesTypeTypeDef",
     {
         "Processes": List[ProcessTypeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ScheduledActionsTypeTypeDef = TypedDict(
     "ScheduledActionsTypeTypeDef",
     {
         "ScheduledUpdateGroupActions": List[ScheduledUpdateGroupActionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 AutoScalingInstancesTypeTypeDef = TypedDict(
     "AutoScalingInstancesTypeTypeDef",
     {
         "AutoScalingInstances": List[AutoScalingInstanceDetailsTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateLaunchConfigurationTypeRequestTypeDef = TypedDict(
     "_RequiredCreateLaunchConfigurationTypeRequestTypeDef",
     {
         "LaunchConfigurationName": str,
@@ -2221,24 +2234,24 @@
 
 DescribeWarmPoolAnswerTypeDef = TypedDict(
     "DescribeWarmPoolAnswerTypeDef",
     {
         "WarmPoolConfiguration": WarmPoolConfigurationTypeDef,
         "Instances": List[InstanceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 LaunchConfigurationsTypeTypeDef = TypedDict(
     "LaunchConfigurationsTypeTypeDef",
     {
         "LaunchConfigurations": List[LaunchConfigurationTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredMetricDataQueryTypeDef = TypedDict(
     "_RequiredMetricDataQueryTypeDef",
     {
         "Id": str,
@@ -2552,15 +2565,15 @@
     pass
 
 AutoScalingGroupsTypeTypeDef = TypedDict(
     "AutoScalingGroupsTypeTypeDef",
     {
         "AutoScalingGroups": List[AutoScalingGroupTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InstanceRefreshTypeDef = TypedDict(
     "InstanceRefreshTypeDef",
     {
         "InstanceRefreshId": str,
@@ -2602,15 +2615,15 @@
 
 GetPredictiveScalingForecastAnswerTypeDef = TypedDict(
     "GetPredictiveScalingForecastAnswerTypeDef",
     {
         "LoadForecast": List[LoadForecastTypeDef],
         "CapacityForecast": CapacityForecastTypeDef,
         "UpdateTime": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredPutScalingPolicyTypeRequestTypeDef = TypedDict(
     "_RequiredPutScalingPolicyTypeRequestTypeDef",
     {
         "AutoScalingGroupName": str,
@@ -2665,19 +2678,19 @@
 )
 
 DescribeInstanceRefreshesAnswerTypeDef = TypedDict(
     "DescribeInstanceRefreshesAnswerTypeDef",
     {
         "InstanceRefreshes": List[InstanceRefreshTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PoliciesTypeTypeDef = TypedDict(
     "PoliciesTypeTypeDef",
     {
         "ScalingPolicies": List[ScalingPolicyTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-autoscaling-2.5.0.post1/types_aiobotocore_autoscaling.egg-info/PKG-INFO` & `types-aiobotocore-autoscaling-2.5.1/types_aiobotocore_autoscaling.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-autoscaling
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.AutoScaling 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.AutoScaling 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-autoscaling"></a>
 
 # types-aiobotocore-autoscaling
 
 [![PyPI - types-aiobotocore-autoscaling](https://img.shields.io/pypi/v/types-aiobotocore-autoscaling.svg?color=blue)](https://pypi.org/project/types-aiobotocore-autoscaling)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-autoscaling.svg?color=blue)](https://pypi.org/project/types-aiobotocore-autoscaling)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-autoscaling?color=blue)](https://pypistats.org/packages/types-aiobotocore-autoscaling)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.AutoScaling 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling)
+[aiobotocore.AutoScaling 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/autoscaling.html#AutoScaling)
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
 [types-aiobotocore-autoscaling docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_autoscaling/).
 
 See how it helps to find and fix potential bugs:
 
@@ -390,68 +390,79 @@
 assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_autoscaling.type_defs import (
     AcceleratorCountRequestTypeDef,
     AcceleratorTotalMemoryMiBRequestTypeDef,
     ActivityTypeDef,
-    ResponseMetadataTypeDef,
     AdjustmentTypeTypeDef,
     AlarmTypeDef,
     AttachInstancesQueryRequestTypeDef,
     AttachLoadBalancerTargetGroupsTypeRequestTypeDef,
     AttachLoadBalancersTypeRequestTypeDef,
     TrafficSourceIdentifierTypeDef,
     FilterTypeDef,
-    PaginatorConfigTypeDef,
     EnabledMetricTypeDef,
     LaunchTemplateSpecificationTypeDef,
     SuspendedProcessTypeDef,
     TagDescriptionTypeDef,
     BaselineEbsBandwidthMbpsRequestTypeDef,
     FailedScheduledUpdateGroupActionRequestTypeDef,
     BatchDeleteScheduledActionTypeRequestTypeDef,
     ScheduledUpdateGroupActionRequestTypeDef,
     EbsTypeDef,
+    CancelInstanceRefreshAnswerTypeDef,
     CancelInstanceRefreshTypeRequestTypeDef,
     CapacityForecastTypeDef,
     CompleteLifecycleActionTypeRequestTypeDef,
     LifecycleHookSpecificationTypeDef,
     TagTypeDef,
     InstanceMetadataOptionsTypeDef,
     InstanceMonitoringTypeDef,
     MetricDimensionTypeDef,
     DeleteAutoScalingGroupTypeRequestTypeDef,
     DeleteLifecycleHookTypeRequestTypeDef,
     DeleteNotificationConfigurationTypeRequestTypeDef,
     DeletePolicyTypeRequestTypeDef,
     DeleteScheduledActionTypeRequestTypeDef,
     DeleteWarmPoolTypeRequestTypeDef,
+    DescribeAccountLimitsAnswerTypeDef,
+    DescribeAutoScalingInstancesTypeDescribeAutoScalingInstancesPaginateTypeDef,
     DescribeAutoScalingInstancesTypeRequestTypeDef,
+    DescribeAutoScalingNotificationTypesAnswerTypeDef,
     DescribeInstanceRefreshesTypeRequestTypeDef,
+    DescribeLifecycleHookTypesAnswerTypeDef,
     LifecycleHookTypeDef,
     DescribeLifecycleHooksTypeRequestTypeDef,
+    DescribeLoadBalancerTargetGroupsRequestDescribeLoadBalancerTargetGroupsPaginateTypeDef,
     DescribeLoadBalancerTargetGroupsRequestRequestTypeDef,
     LoadBalancerTargetGroupStateTypeDef,
+    DescribeLoadBalancersRequestDescribeLoadBalancersPaginateTypeDef,
     DescribeLoadBalancersRequestRequestTypeDef,
     LoadBalancerStateTypeDef,
     MetricCollectionTypeTypeDef,
     MetricGranularityTypeTypeDef,
     NotificationConfigurationTypeDef,
+    DescribeNotificationConfigurationsTypeDescribeNotificationConfigurationsPaginateTypeDef,
     DescribeNotificationConfigurationsTypeRequestTypeDef,
+    DescribePoliciesTypeDescribePoliciesPaginateTypeDef,
     DescribePoliciesTypeRequestTypeDef,
+    DescribeScalingActivitiesTypeDescribeScalingActivitiesPaginateTypeDef,
     DescribeScalingActivitiesTypeRequestTypeDef,
+    DescribeScheduledActionsTypeDescribeScheduledActionsPaginateTypeDef,
     DescribeScheduledActionsTypeRequestTypeDef,
+    DescribeTerminationPolicyTypesAnswerTypeDef,
     DescribeTrafficSourcesRequestRequestTypeDef,
     TrafficSourceStateTypeDef,
     DescribeWarmPoolTypeRequestTypeDef,
     DetachInstancesQueryRequestTypeDef,
     DetachLoadBalancerTargetGroupsTypeRequestTypeDef,
     DetachLoadBalancersTypeRequestTypeDef,
     DisableMetricsCollectionQueryRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EnableMetricsCollectionQueryRequestTypeDef,
     EnterStandbyQueryRequestTypeDef,
     ExecutePolicyTypeRequestTypeDef,
     ExitStandbyQueryRequestTypeDef,
     GetPredictiveScalingForecastTypeRequestTypeDef,
     InstanceRefreshLivePoolProgressTypeDef,
     InstanceRefreshWarmPoolProgressTypeDef,
@@ -461,61 +472,50 @@
     NetworkBandwidthGbpsRequestTypeDef,
     NetworkInterfaceCountRequestTypeDef,
     TotalLocalStorageGBRequestTypeDef,
     VCpuCountRequestTypeDef,
     InstanceReusePolicyTypeDef,
     InstancesDistributionTypeDef,
     LaunchConfigurationNameTypeRequestTypeDef,
+    LaunchConfigurationNamesTypeDescribeLaunchConfigurationsPaginateTypeDef,
     LaunchConfigurationNamesTypeRequestTypeDef,
+    PaginatorConfigTypeDef,
     PredefinedMetricSpecificationTypeDef,
     PredictiveScalingPredefinedLoadMetricTypeDef,
     PredictiveScalingPredefinedMetricPairTypeDef,
     PredictiveScalingPredefinedScalingMetricTypeDef,
     ProcessTypeTypeDef,
     PutLifecycleHookTypeRequestTypeDef,
     PutNotificationConfigurationTypeRequestTypeDef,
     StepAdjustmentTypeDef,
     PutScheduledUpdateGroupActionTypeRequestTypeDef,
     RecordLifecycleActionHeartbeatTypeRequestTypeDef,
+    ResponseMetadataTypeDef,
+    RollbackInstanceRefreshAnswerTypeDef,
     RollbackInstanceRefreshTypeRequestTypeDef,
     ScalingProcessQueryRequestTypeDef,
     ScheduledUpdateGroupActionTypeDef,
     SetDesiredCapacityTypeRequestTypeDef,
     SetInstanceHealthQueryRequestTypeDef,
     SetInstanceProtectionQueryRequestTypeDef,
+    StartInstanceRefreshAnswerTypeDef,
     TerminateInstanceInAutoScalingGroupTypeRequestTypeDef,
     ActivitiesTypeTypeDef,
     ActivityTypeTypeDef,
-    CancelInstanceRefreshAnswerTypeDef,
-    DescribeAccountLimitsAnswerTypeDef,
-    DescribeAutoScalingNotificationTypesAnswerTypeDef,
-    DescribeLifecycleHookTypesAnswerTypeDef,
-    DescribeTerminationPolicyTypesAnswerTypeDef,
     DetachInstancesAnswerTypeDef,
-    EmptyResponseMetadataTypeDef,
     EnterStandbyAnswerTypeDef,
     ExitStandbyAnswerTypeDef,
-    RollbackInstanceRefreshAnswerTypeDef,
-    StartInstanceRefreshAnswerTypeDef,
     DescribeAdjustmentTypesAnswerTypeDef,
     PolicyARNTypeTypeDef,
     AttachTrafficSourcesTypeRequestTypeDef,
     DetachTrafficSourcesTypeRequestTypeDef,
-    AutoScalingGroupNamesTypeRequestTypeDef,
-    DescribeTagsTypeRequestTypeDef,
     AutoScalingGroupNamesTypeDescribeAutoScalingGroupsPaginateTypeDef,
-    DescribeAutoScalingInstancesTypeDescribeAutoScalingInstancesPaginateTypeDef,
-    DescribeLoadBalancerTargetGroupsRequestDescribeLoadBalancerTargetGroupsPaginateTypeDef,
-    DescribeLoadBalancersRequestDescribeLoadBalancersPaginateTypeDef,
-    DescribeNotificationConfigurationsTypeDescribeNotificationConfigurationsPaginateTypeDef,
-    DescribePoliciesTypeDescribePoliciesPaginateTypeDef,
-    DescribeScalingActivitiesTypeDescribeScalingActivitiesPaginateTypeDef,
-    DescribeScheduledActionsTypeDescribeScheduledActionsPaginateTypeDef,
+    AutoScalingGroupNamesTypeRequestTypeDef,
     DescribeTagsTypeDescribeTagsPaginateTypeDef,
-    LaunchConfigurationNamesTypeDescribeLaunchConfigurationsPaginateTypeDef,
+    DescribeTagsTypeRequestTypeDef,
     AutoScalingInstanceDetailsTypeDef,
     InstanceTypeDef,
     TagsTypeTypeDef,
     BatchDeleteScheduledActionAnswerTypeDef,
     BatchPutScheduledUpdateGroupActionAnswerTypeDef,
     BatchPutScheduledUpdateGroupActionTypeRequestTypeDef,
     BlockDeviceMappingTypeDef,
@@ -577,43 +577,43 @@
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

### Comparing `types-aiobotocore-autoscaling-2.5.0.post1/types_aiobotocore_autoscaling.egg-info/SOURCES.txt` & `types-aiobotocore-autoscaling-2.5.1/types_aiobotocore_autoscaling.egg-info/SOURCES.txt`

 * *Files identical despite different names*

