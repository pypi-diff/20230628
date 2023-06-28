# Comparing `tmp/types-aiobotocore-codedeploy-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-codedeploy-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-codedeploy-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:22 2023, max compression
+gzip compressed data, was "types-aiobotocore-codedeploy-2.5.1.tar", last modified: Wed Jun 28 01:43:15 2023, max compression
```

## Comparing `types-aiobotocore-codedeploy-2.5.0.post1.tar` & `types-aiobotocore-codedeploy-2.5.1.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:22.523050 types-aiobotocore-codedeploy-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:11:18.000000 types-aiobotocore-codedeploy-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    22223 2023-03-11 12:26:22.523050 types-aiobotocore-codedeploy-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    20640 2023-03-11 12:11:18.000000 types-aiobotocore-codedeploy-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:22.523050 types-aiobotocore-codedeploy-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2145 2023-03-11 12:11:18.000000 types-aiobotocore-codedeploy-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:22.519050 types-aiobotocore-codedeploy-2.5.0.post1/types_aiobotocore_codedeploy/
--rw-r--r--   0 runner    (1001) docker     (123)     2845 2023-03-11 12:11:18.000000 types-aiobotocore-codedeploy-2.5.0.post1/types_aiobotocore_codedeploy/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2844 2023-03-11 12:11:18.000000 types-aiobotocore-codedeploy-2.5.0.post1/types_aiobotocore_codedeploy/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      955 2023-03-11 12:11:18.000000 types-aiobotocore-codedeploy-2.5.0.post1/types_aiobotocore_codedeploy/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    48531 2023-03-11 12:11:18.000000 types-aiobotocore-codedeploy-2.5.0.post1/types_aiobotocore_codedeploy/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    48465 2023-03-11 12:11:18.000000 types-aiobotocore-codedeploy-2.5.0.post1/types_aiobotocore_codedeploy/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    14240 2023-03-11 12:11:19.000000 types-aiobotocore-codedeploy-2.5.0.post1/types_aiobotocore_codedeploy/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    14238 2023-03-11 12:11:19.000000 types-aiobotocore-codedeploy-2.5.0.post1/types_aiobotocore_codedeploy/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    12754 2023-03-11 12:11:18.000000 types-aiobotocore-codedeploy-2.5.0.post1/types_aiobotocore_codedeploy/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    12742 2023-03-11 12:11:18.000000 types-aiobotocore-codedeploy-2.5.0.post1/types_aiobotocore_codedeploy/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:11:18.000000 types-aiobotocore-codedeploy-2.5.0.post1/types_aiobotocore_codedeploy/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    50613 2023-03-11 12:11:20.000000 types-aiobotocore-codedeploy-2.5.0.post1/types_aiobotocore_codedeploy/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    50580 2023-03-11 12:11:19.000000 types-aiobotocore-codedeploy-2.5.0.post1/types_aiobotocore_codedeploy/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:11:18.000000 types-aiobotocore-codedeploy-2.5.0.post1/types_aiobotocore_codedeploy/version.py
--rw-r--r--   0 runner    (1001) docker     (123)     1621 2023-03-11 12:11:18.000000 types-aiobotocore-codedeploy-2.5.0.post1/types_aiobotocore_codedeploy/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)     1620 2023-03-11 12:11:18.000000 types-aiobotocore-codedeploy-2.5.0.post1/types_aiobotocore_codedeploy/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:22.523050 types-aiobotocore-codedeploy-2.5.0.post1/types_aiobotocore_codedeploy.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    22223 2023-03-11 12:26:22.000000 types-aiobotocore-codedeploy-2.5.0.post1/types_aiobotocore_codedeploy.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      949 2023-03-11 12:26:22.000000 types-aiobotocore-codedeploy-2.5.0.post1/types_aiobotocore_codedeploy.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:22.000000 types-aiobotocore-codedeploy-2.5.0.post1/types_aiobotocore_codedeploy.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:22.000000 types-aiobotocore-codedeploy-2.5.0.post1/types_aiobotocore_codedeploy.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:22.000000 types-aiobotocore-codedeploy-2.5.0.post1/types_aiobotocore_codedeploy.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       29 2023-03-11 12:26:22.000000 types-aiobotocore-codedeploy-2.5.0.post1/types_aiobotocore_codedeploy.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:15.738111 types-aiobotocore-codedeploy-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:27:54.000000 types-aiobotocore-codedeploy-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    22218 2023-06-28 01:43:15.738111 types-aiobotocore-codedeploy-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    20641 2023-06-28 01:27:54.000000 types-aiobotocore-codedeploy-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:15.738111 types-aiobotocore-codedeploy-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2139 2023-06-28 01:27:54.000000 types-aiobotocore-codedeploy-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:15.738111 types-aiobotocore-codedeploy-2.5.1/types_aiobotocore_codedeploy/
+-rw-r--r--   0 runner    (1001) docker     (123)     2845 2023-06-28 01:27:54.000000 types-aiobotocore-codedeploy-2.5.1/types_aiobotocore_codedeploy/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2844 2023-06-28 01:27:54.000000 types-aiobotocore-codedeploy-2.5.1/types_aiobotocore_codedeploy/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      943 2023-06-28 01:27:54.000000 types-aiobotocore-codedeploy-2.5.1/types_aiobotocore_codedeploy/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    48531 2023-06-28 01:27:54.000000 types-aiobotocore-codedeploy-2.5.1/types_aiobotocore_codedeploy/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    48465 2023-06-28 01:27:54.000000 types-aiobotocore-codedeploy-2.5.1/types_aiobotocore_codedeploy/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    14449 2023-06-28 01:27:55.000000 types-aiobotocore-codedeploy-2.5.1/types_aiobotocore_codedeploy/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14447 2023-06-28 01:27:55.000000 types-aiobotocore-codedeploy-2.5.1/types_aiobotocore_codedeploy/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    12652 2023-06-28 01:27:55.000000 types-aiobotocore-codedeploy-2.5.1/types_aiobotocore_codedeploy/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12641 2023-06-28 01:27:54.000000 types-aiobotocore-codedeploy-2.5.1/types_aiobotocore_codedeploy/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:27:54.000000 types-aiobotocore-codedeploy-2.5.1/types_aiobotocore_codedeploy/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    50701 2023-06-28 01:27:56.000000 types-aiobotocore-codedeploy-2.5.1/types_aiobotocore_codedeploy/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    50668 2023-06-28 01:27:55.000000 types-aiobotocore-codedeploy-2.5.1/types_aiobotocore_codedeploy/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:27:54.000000 types-aiobotocore-codedeploy-2.5.1/types_aiobotocore_codedeploy/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1621 2023-06-28 01:27:55.000000 types-aiobotocore-codedeploy-2.5.1/types_aiobotocore_codedeploy/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1620 2023-06-28 01:27:55.000000 types-aiobotocore-codedeploy-2.5.1/types_aiobotocore_codedeploy/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:15.738111 types-aiobotocore-codedeploy-2.5.1/types_aiobotocore_codedeploy.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    22218 2023-06-28 01:43:15.000000 types-aiobotocore-codedeploy-2.5.1/types_aiobotocore_codedeploy.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      949 2023-06-28 01:43:15.000000 types-aiobotocore-codedeploy-2.5.1/types_aiobotocore_codedeploy.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:15.000000 types-aiobotocore-codedeploy-2.5.1/types_aiobotocore_codedeploy.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:15.000000 types-aiobotocore-codedeploy-2.5.1/types_aiobotocore_codedeploy.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:15.000000 types-aiobotocore-codedeploy-2.5.1/types_aiobotocore_codedeploy.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       29 2023-06-28 01:43:15.000000 types-aiobotocore-codedeploy-2.5.1/types_aiobotocore_codedeploy.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-codedeploy-2.5.0.post1/LICENSE` & `types-aiobotocore-codedeploy-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-codedeploy-2.5.0.post1/PKG-INFO` & `types-aiobotocore-codedeploy-2.5.1/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-codedeploy
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CodeDeploy 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CodeDeploy 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-codedeploy"></a>
 
 # types-aiobotocore-codedeploy
 
 [![PyPI - types-aiobotocore-codedeploy](https://img.shields.io/pypi/v/types-aiobotocore-codedeploy.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codedeploy)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-codedeploy.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codedeploy)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-codedeploy?color=blue)](https://pypistats.org/packages/types-aiobotocore-codedeploy)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CodeDeploy 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codedeploy.html#CodeDeploy)
+[aiobotocore.CodeDeploy 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codedeploy.html#CodeDeploy)
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
 [types-aiobotocore-codedeploy docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/).
 
 See how it helps to find and fix potential bugs:
 
@@ -422,119 +422,119 @@
 from types_aiobotocore_codedeploy.type_defs import (
     TagTypeDef,
     AlarmTypeDef,
     AppSpecContentTypeDef,
     ApplicationInfoTypeDef,
     AutoRollbackConfigurationTypeDef,
     AutoScalingGroupTypeDef,
-    ResponseMetadataTypeDef,
     BatchGetApplicationsInputRequestTypeDef,
     BatchGetDeploymentGroupsInputRequestTypeDef,
     BatchGetDeploymentInstancesInputRequestTypeDef,
     BatchGetDeploymentTargetsInputRequestTypeDef,
     BatchGetDeploymentsInputRequestTypeDef,
     BatchGetOnPremisesInstancesInputRequestTypeDef,
     BlueInstanceTerminationOptionTypeDef,
     DeploymentReadyOptionTypeDef,
     GreenFleetProvisioningOptionTypeDef,
     ContinueDeploymentInputRequestTypeDef,
+    CreateApplicationOutputTypeDef,
     MinimumHealthyHostsTypeDef,
+    CreateDeploymentConfigOutputTypeDef,
     DeploymentStyleTypeDef,
     EC2TagFilterTypeDef,
     ECSServiceTypeDef,
     TagFilterTypeDef,
     TriggerConfigTypeDef,
+    CreateDeploymentGroupOutputTypeDef,
+    CreateDeploymentOutputTypeDef,
     DeleteApplicationInputRequestTypeDef,
     DeleteDeploymentConfigInputRequestTypeDef,
     DeleteDeploymentGroupInputRequestTypeDef,
     DeleteGitHubAccountTokenInputRequestTypeDef,
+    DeleteGitHubAccountTokenOutputTypeDef,
     DeleteResourcesByExternalIdInputRequestTypeDef,
     LastDeploymentInfoTypeDef,
     DeploymentOverviewTypeDef,
     ErrorInformationTypeDef,
     RelatedDeploymentsTypeDef,
     RollbackInfoTypeDef,
     DeregisterOnPremisesInstanceInputRequestTypeDef,
     DiagnosticsTypeDef,
     TargetGroupInfoTypeDef,
     ELBInfoTypeDef,
+    EmptyResponseMetadataTypeDef,
     GenericRevisionInfoTypeDef,
     GetApplicationInputRequestTypeDef,
     GetDeploymentConfigInputRequestTypeDef,
     GetDeploymentGroupInputRequestTypeDef,
     WaiterConfigTypeDef,
     GetDeploymentInputRequestTypeDef,
     GetDeploymentInstanceInputRequestTypeDef,
     GetDeploymentTargetInputRequestTypeDef,
     GetOnPremisesInstanceInputRequestTypeDef,
     GitHubLocationTypeDef,
     LambdaFunctionInfoTypeDef,
-    PaginatorConfigTypeDef,
+    ListApplicationRevisionsInputListApplicationRevisionsPaginateTypeDef,
     ListApplicationRevisionsInputRequestTypeDef,
+    ListApplicationsInputListApplicationsPaginateTypeDef,
     ListApplicationsInputRequestTypeDef,
+    ListApplicationsOutputTypeDef,
+    ListDeploymentConfigsInputListDeploymentConfigsPaginateTypeDef,
     ListDeploymentConfigsInputRequestTypeDef,
+    ListDeploymentConfigsOutputTypeDef,
+    ListDeploymentGroupsInputListDeploymentGroupsPaginateTypeDef,
     ListDeploymentGroupsInputRequestTypeDef,
+    ListDeploymentGroupsOutputTypeDef,
+    ListDeploymentInstancesInputListDeploymentInstancesPaginateTypeDef,
     ListDeploymentInstancesInputRequestTypeDef,
+    ListDeploymentInstancesOutputTypeDef,
+    ListDeploymentTargetsInputListDeploymentTargetsPaginateTypeDef,
     ListDeploymentTargetsInputRequestTypeDef,
+    ListDeploymentTargetsOutputTypeDef,
     TimeRangeTypeDef,
+    ListDeploymentsOutputTypeDef,
+    ListGitHubAccountTokenNamesInputListGitHubAccountTokenNamesPaginateTypeDef,
     ListGitHubAccountTokenNamesInputRequestTypeDef,
+    ListGitHubAccountTokenNamesOutputTypeDef,
+    ListOnPremisesInstancesOutputTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    PaginatorConfigTypeDef,
     PutLifecycleEventHookExecutionStatusInputRequestTypeDef,
+    PutLifecycleEventHookExecutionStatusOutputTypeDef,
     RawStringTypeDef,
     RegisterOnPremisesInstanceInputRequestTypeDef,
+    ResponseMetadataTypeDef,
     S3LocationTypeDef,
     SkipWaitTimeForInstanceTerminationInputRequestTypeDef,
     StopDeploymentInputRequestTypeDef,
+    StopDeploymentOutputTypeDef,
     TrafficRouteTypeDef,
     TimeBasedCanaryTypeDef,
     TimeBasedLinearTypeDef,
     UntagResourceInputRequestTypeDef,
     UpdateApplicationInputRequestTypeDef,
     AddTagsToOnPremisesInstancesInputRequestTypeDef,
     CreateApplicationInputRequestTypeDef,
     InstanceInfoTypeDef,
+    ListTagsForResourceOutputTypeDef,
     RemoveTagsFromOnPremisesInstancesInputRequestTypeDef,
     TagResourceInputRequestTypeDef,
     AlarmConfigurationTypeDef,
     BatchGetApplicationsOutputTypeDef,
-    CreateApplicationOutputTypeDef,
-    CreateDeploymentConfigOutputTypeDef,
-    CreateDeploymentGroupOutputTypeDef,
-    CreateDeploymentOutputTypeDef,
-    DeleteDeploymentGroupOutputTypeDef,
-    DeleteGitHubAccountTokenOutputTypeDef,
-    EmptyResponseMetadataTypeDef,
     GetApplicationOutputTypeDef,
-    ListApplicationsOutputTypeDef,
-    ListDeploymentConfigsOutputTypeDef,
-    ListDeploymentGroupsOutputTypeDef,
-    ListDeploymentInstancesOutputTypeDef,
-    ListDeploymentTargetsOutputTypeDef,
-    ListDeploymentsOutputTypeDef,
-    ListGitHubAccountTokenNamesOutputTypeDef,
-    ListOnPremisesInstancesOutputTypeDef,
-    ListTagsForResourceOutputTypeDef,
-    PutLifecycleEventHookExecutionStatusOutputTypeDef,
-    StopDeploymentOutputTypeDef,
+    DeleteDeploymentGroupOutputTypeDef,
     UpdateDeploymentGroupOutputTypeDef,
     BlueGreenDeploymentConfigurationTypeDef,
     EC2TagSetTypeDef,
+    ListOnPremisesInstancesInputListOnPremisesInstancesPaginateTypeDef,
     ListOnPremisesInstancesInputRequestTypeDef,
     OnPremisesTagSetTypeDef,
     LifecycleEventTypeDef,
     ECSTaskSetTypeDef,
     GetDeploymentInputDeploymentSuccessfulWaitTypeDef,
-    ListApplicationRevisionsInputListApplicationRevisionsPaginateTypeDef,
-    ListApplicationsInputListApplicationsPaginateTypeDef,
-    ListDeploymentConfigsInputListDeploymentConfigsPaginateTypeDef,
-    ListDeploymentGroupsInputListDeploymentGroupsPaginateTypeDef,
-    ListDeploymentInstancesInputListDeploymentInstancesPaginateTypeDef,
-    ListDeploymentTargetsInputListDeploymentTargetsPaginateTypeDef,
-    ListGitHubAccountTokenNamesInputListGitHubAccountTokenNamesPaginateTypeDef,
-    ListOnPremisesInstancesInputListOnPremisesInstancesPaginateTypeDef,
     ListDeploymentsInputListDeploymentsPaginateTypeDef,
     ListDeploymentsInputRequestTypeDef,
     RevisionLocationTypeDef,
     TargetGroupPairInfoTypeDef,
     TrafficRoutingConfigTypeDef,
     BatchGetOnPremisesInstancesOutputTypeDef,
     GetOnPremisesInstanceOutputTypeDef,
@@ -579,43 +579,43 @@
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

### Comparing `types-aiobotocore-codedeploy-2.5.0.post1/README.md` & `types-aiobotocore-codedeploy-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-codedeploy"></a>
 
 # types-aiobotocore-codedeploy
 
 [![PyPI - types-aiobotocore-codedeploy](https://img.shields.io/pypi/v/types-aiobotocore-codedeploy.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codedeploy)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-codedeploy.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codedeploy)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-codedeploy?color=blue)](https://pypistats.org/packages/types-aiobotocore-codedeploy)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CodeDeploy 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codedeploy.html#CodeDeploy)
+[aiobotocore.CodeDeploy 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codedeploy.html#CodeDeploy)
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
 [types-aiobotocore-codedeploy docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/).
 
 See how it helps to find and fix potential bugs:
 
@@ -389,119 +389,119 @@
 from types_aiobotocore_codedeploy.type_defs import (
     TagTypeDef,
     AlarmTypeDef,
     AppSpecContentTypeDef,
     ApplicationInfoTypeDef,
     AutoRollbackConfigurationTypeDef,
     AutoScalingGroupTypeDef,
-    ResponseMetadataTypeDef,
     BatchGetApplicationsInputRequestTypeDef,
     BatchGetDeploymentGroupsInputRequestTypeDef,
     BatchGetDeploymentInstancesInputRequestTypeDef,
     BatchGetDeploymentTargetsInputRequestTypeDef,
     BatchGetDeploymentsInputRequestTypeDef,
     BatchGetOnPremisesInstancesInputRequestTypeDef,
     BlueInstanceTerminationOptionTypeDef,
     DeploymentReadyOptionTypeDef,
     GreenFleetProvisioningOptionTypeDef,
     ContinueDeploymentInputRequestTypeDef,
+    CreateApplicationOutputTypeDef,
     MinimumHealthyHostsTypeDef,
+    CreateDeploymentConfigOutputTypeDef,
     DeploymentStyleTypeDef,
     EC2TagFilterTypeDef,
     ECSServiceTypeDef,
     TagFilterTypeDef,
     TriggerConfigTypeDef,
+    CreateDeploymentGroupOutputTypeDef,
+    CreateDeploymentOutputTypeDef,
     DeleteApplicationInputRequestTypeDef,
     DeleteDeploymentConfigInputRequestTypeDef,
     DeleteDeploymentGroupInputRequestTypeDef,
     DeleteGitHubAccountTokenInputRequestTypeDef,
+    DeleteGitHubAccountTokenOutputTypeDef,
     DeleteResourcesByExternalIdInputRequestTypeDef,
     LastDeploymentInfoTypeDef,
     DeploymentOverviewTypeDef,
     ErrorInformationTypeDef,
     RelatedDeploymentsTypeDef,
     RollbackInfoTypeDef,
     DeregisterOnPremisesInstanceInputRequestTypeDef,
     DiagnosticsTypeDef,
     TargetGroupInfoTypeDef,
     ELBInfoTypeDef,
+    EmptyResponseMetadataTypeDef,
     GenericRevisionInfoTypeDef,
     GetApplicationInputRequestTypeDef,
     GetDeploymentConfigInputRequestTypeDef,
     GetDeploymentGroupInputRequestTypeDef,
     WaiterConfigTypeDef,
     GetDeploymentInputRequestTypeDef,
     GetDeploymentInstanceInputRequestTypeDef,
     GetDeploymentTargetInputRequestTypeDef,
     GetOnPremisesInstanceInputRequestTypeDef,
     GitHubLocationTypeDef,
     LambdaFunctionInfoTypeDef,
-    PaginatorConfigTypeDef,
+    ListApplicationRevisionsInputListApplicationRevisionsPaginateTypeDef,
     ListApplicationRevisionsInputRequestTypeDef,
+    ListApplicationsInputListApplicationsPaginateTypeDef,
     ListApplicationsInputRequestTypeDef,
+    ListApplicationsOutputTypeDef,
+    ListDeploymentConfigsInputListDeploymentConfigsPaginateTypeDef,
     ListDeploymentConfigsInputRequestTypeDef,
+    ListDeploymentConfigsOutputTypeDef,
+    ListDeploymentGroupsInputListDeploymentGroupsPaginateTypeDef,
     ListDeploymentGroupsInputRequestTypeDef,
+    ListDeploymentGroupsOutputTypeDef,
+    ListDeploymentInstancesInputListDeploymentInstancesPaginateTypeDef,
     ListDeploymentInstancesInputRequestTypeDef,
+    ListDeploymentInstancesOutputTypeDef,
+    ListDeploymentTargetsInputListDeploymentTargetsPaginateTypeDef,
     ListDeploymentTargetsInputRequestTypeDef,
+    ListDeploymentTargetsOutputTypeDef,
     TimeRangeTypeDef,
+    ListDeploymentsOutputTypeDef,
+    ListGitHubAccountTokenNamesInputListGitHubAccountTokenNamesPaginateTypeDef,
     ListGitHubAccountTokenNamesInputRequestTypeDef,
+    ListGitHubAccountTokenNamesOutputTypeDef,
+    ListOnPremisesInstancesOutputTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    PaginatorConfigTypeDef,
     PutLifecycleEventHookExecutionStatusInputRequestTypeDef,
+    PutLifecycleEventHookExecutionStatusOutputTypeDef,
     RawStringTypeDef,
     RegisterOnPremisesInstanceInputRequestTypeDef,
+    ResponseMetadataTypeDef,
     S3LocationTypeDef,
     SkipWaitTimeForInstanceTerminationInputRequestTypeDef,
     StopDeploymentInputRequestTypeDef,
+    StopDeploymentOutputTypeDef,
     TrafficRouteTypeDef,
     TimeBasedCanaryTypeDef,
     TimeBasedLinearTypeDef,
     UntagResourceInputRequestTypeDef,
     UpdateApplicationInputRequestTypeDef,
     AddTagsToOnPremisesInstancesInputRequestTypeDef,
     CreateApplicationInputRequestTypeDef,
     InstanceInfoTypeDef,
+    ListTagsForResourceOutputTypeDef,
     RemoveTagsFromOnPremisesInstancesInputRequestTypeDef,
     TagResourceInputRequestTypeDef,
     AlarmConfigurationTypeDef,
     BatchGetApplicationsOutputTypeDef,
-    CreateApplicationOutputTypeDef,
-    CreateDeploymentConfigOutputTypeDef,
-    CreateDeploymentGroupOutputTypeDef,
-    CreateDeploymentOutputTypeDef,
-    DeleteDeploymentGroupOutputTypeDef,
-    DeleteGitHubAccountTokenOutputTypeDef,
-    EmptyResponseMetadataTypeDef,
     GetApplicationOutputTypeDef,
-    ListApplicationsOutputTypeDef,
-    ListDeploymentConfigsOutputTypeDef,
-    ListDeploymentGroupsOutputTypeDef,
-    ListDeploymentInstancesOutputTypeDef,
-    ListDeploymentTargetsOutputTypeDef,
-    ListDeploymentsOutputTypeDef,
-    ListGitHubAccountTokenNamesOutputTypeDef,
-    ListOnPremisesInstancesOutputTypeDef,
-    ListTagsForResourceOutputTypeDef,
-    PutLifecycleEventHookExecutionStatusOutputTypeDef,
-    StopDeploymentOutputTypeDef,
+    DeleteDeploymentGroupOutputTypeDef,
     UpdateDeploymentGroupOutputTypeDef,
     BlueGreenDeploymentConfigurationTypeDef,
     EC2TagSetTypeDef,
+    ListOnPremisesInstancesInputListOnPremisesInstancesPaginateTypeDef,
     ListOnPremisesInstancesInputRequestTypeDef,
     OnPremisesTagSetTypeDef,
     LifecycleEventTypeDef,
     ECSTaskSetTypeDef,
     GetDeploymentInputDeploymentSuccessfulWaitTypeDef,
-    ListApplicationRevisionsInputListApplicationRevisionsPaginateTypeDef,
-    ListApplicationsInputListApplicationsPaginateTypeDef,
-    ListDeploymentConfigsInputListDeploymentConfigsPaginateTypeDef,
-    ListDeploymentGroupsInputListDeploymentGroupsPaginateTypeDef,
-    ListDeploymentInstancesInputListDeploymentInstancesPaginateTypeDef,
-    ListDeploymentTargetsInputListDeploymentTargetsPaginateTypeDef,
-    ListGitHubAccountTokenNamesInputListGitHubAccountTokenNamesPaginateTypeDef,
-    ListOnPremisesInstancesInputListOnPremisesInstancesPaginateTypeDef,
     ListDeploymentsInputListDeploymentsPaginateTypeDef,
     ListDeploymentsInputRequestTypeDef,
     RevisionLocationTypeDef,
     TargetGroupPairInfoTypeDef,
     TrafficRoutingConfigTypeDef,
     BatchGetOnPremisesInstancesOutputTypeDef,
     GetOnPremisesInstanceOutputTypeDef,
@@ -546,43 +546,43 @@
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

### Comparing `types-aiobotocore-codedeploy-2.5.0.post1/setup.py` & `types-aiobotocore-codedeploy-2.5.1/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-codedeploy.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-codedeploy",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_codedeploy"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.CodeDeploy 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.CodeDeploy 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/"
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

### Comparing `types-aiobotocore-codedeploy-2.5.0.post1/types_aiobotocore_codedeploy/__init__.py` & `types-aiobotocore-codedeploy-2.5.1/types_aiobotocore_codedeploy/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-codedeploy-2.5.0.post1/types_aiobotocore_codedeploy/__init__.pyi` & `types-aiobotocore-codedeploy-2.5.1/types_aiobotocore_codedeploy/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-codedeploy-2.5.0.post1/types_aiobotocore_codedeploy/__main__.py` & `types-aiobotocore-codedeploy-2.5.1/types_aiobotocore_codedeploy/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.CodeDeploy 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.CodeDeploy 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codedeploy.html#CodeDeploy\nOther"
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

### Comparing `types-aiobotocore-codedeploy-2.5.0.post1/types_aiobotocore_codedeploy/client.py` & `types-aiobotocore-codedeploy-2.5.1/types_aiobotocore_codedeploy/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-codedeploy-2.5.0.post1/types_aiobotocore_codedeploy/client.pyi` & `types-aiobotocore-codedeploy-2.5.1/types_aiobotocore_codedeploy/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-codedeploy-2.5.0.post1/types_aiobotocore_codedeploy/literals.py` & `types-aiobotocore-codedeploy-2.5.1/types_aiobotocore_codedeploy/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -247,14 +247,15 @@
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
@@ -333,14 +334,15 @@
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
@@ -351,14 +353,15 @@
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
@@ -394,14 +397,15 @@
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
@@ -420,16 +424,19 @@
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
@@ -513,15 +520,17 @@
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

### Comparing `types-aiobotocore-codedeploy-2.5.0.post1/types_aiobotocore_codedeploy/literals.pyi` & `types-aiobotocore-codedeploy-2.5.1/types_aiobotocore_codedeploy/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -245,14 +245,15 @@
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
@@ -331,14 +332,15 @@
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
@@ -349,14 +351,15 @@
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
@@ -392,14 +395,15 @@
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
@@ -418,16 +422,19 @@
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
@@ -511,15 +518,17 @@
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

### Comparing `types-aiobotocore-codedeploy-2.5.0.post1/types_aiobotocore_codedeploy/paginator.py` & `types-aiobotocore-codedeploy-2.5.1/types_aiobotocore_codedeploy/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -32,16 +32,15 @@
         list_deployment_instances_paginator: ListDeploymentInstancesPaginator = client.get_paginator("list_deployment_instances")
         list_deployment_targets_paginator: ListDeploymentTargetsPaginator = client.get_paginator("list_deployment_targets")
         list_deployments_paginator: ListDeploymentsPaginator = client.get_paginator("list_deployments")
         list_git_hub_account_token_names_paginator: ListGitHubAccountTokenNamesPaginator = client.get_paginator("list_git_hub_account_token_names")
         list_on_premises_instances_paginator: ListOnPremisesInstancesPaginator = client.get_paginator("list_on_premises_instances")
     ```
 """
-import sys
-from typing import Generic, Iterator, Mapping, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Mapping, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     ApplicationRevisionSortByType,
     DeploymentStatusType,
@@ -63,43 +62,34 @@
     ListGitHubAccountTokenNamesOutputTypeDef,
     ListOnPremisesInstancesOutputTypeDef,
     PaginatorConfigTypeDef,
     TagFilterTypeDef,
     TimeRangeTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListApplicationRevisionsPaginator",
     "ListApplicationsPaginator",
     "ListDeploymentConfigsPaginator",
     "ListDeploymentGroupsPaginator",
     "ListDeploymentInstancesPaginator",
     "ListDeploymentTargetsPaginator",
     "ListDeploymentsPaginator",
     "ListGitHubAccountTokenNamesPaginator",
     "ListOnPremisesInstancesPaginator",
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
 class ListApplicationRevisionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codedeploy.html#CodeDeploy.Paginator.ListApplicationRevisions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/paginators/#listapplicationrevisionspaginator)
     """
 
     def paginate(
@@ -107,153 +97,145 @@
         *,
         applicationName: str,
         sortBy: ApplicationRevisionSortByType = ...,
         sortOrder: SortOrderType = ...,
         s3Bucket: str = ...,
         s3KeyPrefix: str = ...,
         deployed: ListStateFilterActionType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListApplicationRevisionsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codedeploy.html#CodeDeploy.Paginator.ListApplicationRevisions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/paginators/#listapplicationrevisionspaginator)
         """
 
-
 class ListApplicationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codedeploy.html#CodeDeploy.Paginator.ListApplications)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/paginators/#listapplicationspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListApplicationsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codedeploy.html#CodeDeploy.Paginator.ListApplications.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/paginators/#listapplicationspaginator)
         """
 
-
 class ListDeploymentConfigsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codedeploy.html#CodeDeploy.Paginator.ListDeploymentConfigs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/paginators/#listdeploymentconfigspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDeploymentConfigsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codedeploy.html#CodeDeploy.Paginator.ListDeploymentConfigs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/paginators/#listdeploymentconfigspaginator)
         """
 
-
 class ListDeploymentGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codedeploy.html#CodeDeploy.Paginator.ListDeploymentGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/paginators/#listdeploymentgroupspaginator)
     """
 
     def paginate(
-        self, *, applicationName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, applicationName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDeploymentGroupsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codedeploy.html#CodeDeploy.Paginator.ListDeploymentGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/paginators/#listdeploymentgroupspaginator)
         """
 
-
 class ListDeploymentInstancesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codedeploy.html#CodeDeploy.Paginator.ListDeploymentInstances)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/paginators/#listdeploymentinstancespaginator)
     """
 
     def paginate(
         self,
         *,
         deploymentId: str,
         instanceStatusFilter: Sequence[InstanceStatusType] = ...,
         instanceTypeFilter: Sequence[InstanceTypeType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDeploymentInstancesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codedeploy.html#CodeDeploy.Paginator.ListDeploymentInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/paginators/#listdeploymentinstancespaginator)
         """
 
-
 class ListDeploymentTargetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codedeploy.html#CodeDeploy.Paginator.ListDeploymentTargets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/paginators/#listdeploymenttargetspaginator)
     """
 
     def paginate(
         self,
         *,
         deploymentId: str = ...,
         targetFilters: Mapping[TargetFilterNameType, Sequence[str]] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDeploymentTargetsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codedeploy.html#CodeDeploy.Paginator.ListDeploymentTargets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/paginators/#listdeploymenttargetspaginator)
         """
 
-
 class ListDeploymentsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codedeploy.html#CodeDeploy.Paginator.ListDeployments)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/paginators/#listdeploymentspaginator)
     """
 
     def paginate(
         self,
         *,
         applicationName: str = ...,
         deploymentGroupName: str = ...,
         externalId: str = ...,
         includeOnlyStatuses: Sequence[DeploymentStatusType] = ...,
         createTimeRange: TimeRangeTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDeploymentsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codedeploy.html#CodeDeploy.Paginator.ListDeployments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/paginators/#listdeploymentspaginator)
         """
 
-
 class ListGitHubAccountTokenNamesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codedeploy.html#CodeDeploy.Paginator.ListGitHubAccountTokenNames)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/paginators/#listgithubaccounttokennamespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGitHubAccountTokenNamesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codedeploy.html#CodeDeploy.Paginator.ListGitHubAccountTokenNames.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/paginators/#listgithubaccounttokennamespaginator)
         """
 
-
 class ListOnPremisesInstancesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codedeploy.html#CodeDeploy.Paginator.ListOnPremisesInstances)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/paginators/#listonpremisesinstancespaginator)
     """
 
     def paginate(
         self,
         *,
         registrationStatus: RegistrationStatusType = ...,
         tagFilters: Sequence[TagFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOnPremisesInstancesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codedeploy.html#CodeDeploy.Paginator.ListOnPremisesInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/paginators/#listonpremisesinstancespaginator)
         """
```

### Comparing `types-aiobotocore-codedeploy-2.5.0.post1/types_aiobotocore_codedeploy/paginator.pyi` & `types-aiobotocore-codedeploy-2.5.1/types_aiobotocore_codedeploy/paginator.py`

 * *Files 1% similar despite different names*

```diff
@@ -32,16 +32,15 @@
         list_deployment_instances_paginator: ListDeploymentInstancesPaginator = client.get_paginator("list_deployment_instances")
         list_deployment_targets_paginator: ListDeploymentTargetsPaginator = client.get_paginator("list_deployment_targets")
         list_deployments_paginator: ListDeploymentsPaginator = client.get_paginator("list_deployments")
         list_git_hub_account_token_names_paginator: ListGitHubAccountTokenNamesPaginator = client.get_paginator("list_git_hub_account_token_names")
         list_on_premises_instances_paginator: ListOnPremisesInstancesPaginator = client.get_paginator("list_on_premises_instances")
     ```
 """
-import sys
-from typing import Generic, Iterator, Mapping, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Mapping, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     ApplicationRevisionSortByType,
     DeploymentStatusType,
@@ -63,39 +62,37 @@
     ListGitHubAccountTokenNamesOutputTypeDef,
     ListOnPremisesInstancesOutputTypeDef,
     PaginatorConfigTypeDef,
     TagFilterTypeDef,
     TimeRangeTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListApplicationRevisionsPaginator",
     "ListApplicationsPaginator",
     "ListDeploymentConfigsPaginator",
     "ListDeploymentGroupsPaginator",
     "ListDeploymentInstancesPaginator",
     "ListDeploymentTargetsPaginator",
     "ListDeploymentsPaginator",
     "ListGitHubAccountTokenNamesPaginator",
     "ListOnPremisesInstancesPaginator",
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
 class ListApplicationRevisionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codedeploy.html#CodeDeploy.Paginator.ListApplicationRevisions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/paginators/#listapplicationrevisionspaginator)
     """
 
     def paginate(
@@ -103,145 +100,153 @@
         *,
         applicationName: str,
         sortBy: ApplicationRevisionSortByType = ...,
         sortOrder: SortOrderType = ...,
         s3Bucket: str = ...,
         s3KeyPrefix: str = ...,
         deployed: ListStateFilterActionType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListApplicationRevisionsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codedeploy.html#CodeDeploy.Paginator.ListApplicationRevisions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/paginators/#listapplicationrevisionspaginator)
         """
 
+
 class ListApplicationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codedeploy.html#CodeDeploy.Paginator.ListApplications)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/paginators/#listapplicationspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListApplicationsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codedeploy.html#CodeDeploy.Paginator.ListApplications.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/paginators/#listapplicationspaginator)
         """
 
+
 class ListDeploymentConfigsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codedeploy.html#CodeDeploy.Paginator.ListDeploymentConfigs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/paginators/#listdeploymentconfigspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDeploymentConfigsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codedeploy.html#CodeDeploy.Paginator.ListDeploymentConfigs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/paginators/#listdeploymentconfigspaginator)
         """
 
+
 class ListDeploymentGroupsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codedeploy.html#CodeDeploy.Paginator.ListDeploymentGroups)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/paginators/#listdeploymentgroupspaginator)
     """
 
     def paginate(
-        self, *, applicationName: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, applicationName: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDeploymentGroupsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codedeploy.html#CodeDeploy.Paginator.ListDeploymentGroups.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/paginators/#listdeploymentgroupspaginator)
         """
 
+
 class ListDeploymentInstancesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codedeploy.html#CodeDeploy.Paginator.ListDeploymentInstances)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/paginators/#listdeploymentinstancespaginator)
     """
 
     def paginate(
         self,
         *,
         deploymentId: str,
         instanceStatusFilter: Sequence[InstanceStatusType] = ...,
         instanceTypeFilter: Sequence[InstanceTypeType] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDeploymentInstancesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codedeploy.html#CodeDeploy.Paginator.ListDeploymentInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/paginators/#listdeploymentinstancespaginator)
         """
 
+
 class ListDeploymentTargetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codedeploy.html#CodeDeploy.Paginator.ListDeploymentTargets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/paginators/#listdeploymenttargetspaginator)
     """
 
     def paginate(
         self,
         *,
         deploymentId: str = ...,
         targetFilters: Mapping[TargetFilterNameType, Sequence[str]] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDeploymentTargetsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codedeploy.html#CodeDeploy.Paginator.ListDeploymentTargets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/paginators/#listdeploymenttargetspaginator)
         """
 
+
 class ListDeploymentsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codedeploy.html#CodeDeploy.Paginator.ListDeployments)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/paginators/#listdeploymentspaginator)
     """
 
     def paginate(
         self,
         *,
         applicationName: str = ...,
         deploymentGroupName: str = ...,
         externalId: str = ...,
         includeOnlyStatuses: Sequence[DeploymentStatusType] = ...,
         createTimeRange: TimeRangeTypeDef = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDeploymentsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codedeploy.html#CodeDeploy.Paginator.ListDeployments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/paginators/#listdeploymentspaginator)
         """
 
+
 class ListGitHubAccountTokenNamesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codedeploy.html#CodeDeploy.Paginator.ListGitHubAccountTokenNames)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/paginators/#listgithubaccounttokennamespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListGitHubAccountTokenNamesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codedeploy.html#CodeDeploy.Paginator.ListGitHubAccountTokenNames.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/paginators/#listgithubaccounttokennamespaginator)
         """
 
+
 class ListOnPremisesInstancesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codedeploy.html#CodeDeploy.Paginator.ListOnPremisesInstances)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/paginators/#listonpremisesinstancespaginator)
     """
 
     def paginate(
         self,
         *,
         registrationStatus: RegistrationStatusType = ...,
         tagFilters: Sequence[TagFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOnPremisesInstancesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codedeploy.html#CodeDeploy.Paginator.ListOnPremisesInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/paginators/#listonpremisesinstancespaginator)
         """
```

### Comparing `types-aiobotocore-codedeploy-2.5.0.post1/types_aiobotocore_codedeploy/type_defs.py` & `types-aiobotocore-codedeploy-2.5.1/types_aiobotocore_codedeploy/type_defs.py`

 * *Files 5% similar despite different names*

```diff
@@ -60,119 +60,119 @@
 __all__ = (
     "TagTypeDef",
     "AlarmTypeDef",
     "AppSpecContentTypeDef",
     "ApplicationInfoTypeDef",
     "AutoRollbackConfigurationTypeDef",
     "AutoScalingGroupTypeDef",
-    "ResponseMetadataTypeDef",
     "BatchGetApplicationsInputRequestTypeDef",
     "BatchGetDeploymentGroupsInputRequestTypeDef",
     "BatchGetDeploymentInstancesInputRequestTypeDef",
     "BatchGetDeploymentTargetsInputRequestTypeDef",
     "BatchGetDeploymentsInputRequestTypeDef",
     "BatchGetOnPremisesInstancesInputRequestTypeDef",
     "BlueInstanceTerminationOptionTypeDef",
     "DeploymentReadyOptionTypeDef",
     "GreenFleetProvisioningOptionTypeDef",
     "ContinueDeploymentInputRequestTypeDef",
+    "CreateApplicationOutputTypeDef",
     "MinimumHealthyHostsTypeDef",
+    "CreateDeploymentConfigOutputTypeDef",
     "DeploymentStyleTypeDef",
     "EC2TagFilterTypeDef",
     "ECSServiceTypeDef",
     "TagFilterTypeDef",
     "TriggerConfigTypeDef",
+    "CreateDeploymentGroupOutputTypeDef",
+    "CreateDeploymentOutputTypeDef",
     "DeleteApplicationInputRequestTypeDef",
     "DeleteDeploymentConfigInputRequestTypeDef",
     "DeleteDeploymentGroupInputRequestTypeDef",
     "DeleteGitHubAccountTokenInputRequestTypeDef",
+    "DeleteGitHubAccountTokenOutputTypeDef",
     "DeleteResourcesByExternalIdInputRequestTypeDef",
     "LastDeploymentInfoTypeDef",
     "DeploymentOverviewTypeDef",
     "ErrorInformationTypeDef",
     "RelatedDeploymentsTypeDef",
     "RollbackInfoTypeDef",
     "DeregisterOnPremisesInstanceInputRequestTypeDef",
     "DiagnosticsTypeDef",
     "TargetGroupInfoTypeDef",
     "ELBInfoTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GenericRevisionInfoTypeDef",
     "GetApplicationInputRequestTypeDef",
     "GetDeploymentConfigInputRequestTypeDef",
     "GetDeploymentGroupInputRequestTypeDef",
     "WaiterConfigTypeDef",
     "GetDeploymentInputRequestTypeDef",
     "GetDeploymentInstanceInputRequestTypeDef",
     "GetDeploymentTargetInputRequestTypeDef",
     "GetOnPremisesInstanceInputRequestTypeDef",
     "GitHubLocationTypeDef",
     "LambdaFunctionInfoTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListApplicationRevisionsInputListApplicationRevisionsPaginateTypeDef",
     "ListApplicationRevisionsInputRequestTypeDef",
+    "ListApplicationsInputListApplicationsPaginateTypeDef",
     "ListApplicationsInputRequestTypeDef",
+    "ListApplicationsOutputTypeDef",
+    "ListDeploymentConfigsInputListDeploymentConfigsPaginateTypeDef",
     "ListDeploymentConfigsInputRequestTypeDef",
+    "ListDeploymentConfigsOutputTypeDef",
+    "ListDeploymentGroupsInputListDeploymentGroupsPaginateTypeDef",
     "ListDeploymentGroupsInputRequestTypeDef",
+    "ListDeploymentGroupsOutputTypeDef",
+    "ListDeploymentInstancesInputListDeploymentInstancesPaginateTypeDef",
     "ListDeploymentInstancesInputRequestTypeDef",
+    "ListDeploymentInstancesOutputTypeDef",
+    "ListDeploymentTargetsInputListDeploymentTargetsPaginateTypeDef",
     "ListDeploymentTargetsInputRequestTypeDef",
+    "ListDeploymentTargetsOutputTypeDef",
     "TimeRangeTypeDef",
+    "ListDeploymentsOutputTypeDef",
+    "ListGitHubAccountTokenNamesInputListGitHubAccountTokenNamesPaginateTypeDef",
     "ListGitHubAccountTokenNamesInputRequestTypeDef",
+    "ListGitHubAccountTokenNamesOutputTypeDef",
+    "ListOnPremisesInstancesOutputTypeDef",
     "ListTagsForResourceInputRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "PutLifecycleEventHookExecutionStatusInputRequestTypeDef",
+    "PutLifecycleEventHookExecutionStatusOutputTypeDef",
     "RawStringTypeDef",
     "RegisterOnPremisesInstanceInputRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "S3LocationTypeDef",
     "SkipWaitTimeForInstanceTerminationInputRequestTypeDef",
     "StopDeploymentInputRequestTypeDef",
+    "StopDeploymentOutputTypeDef",
     "TrafficRouteTypeDef",
     "TimeBasedCanaryTypeDef",
     "TimeBasedLinearTypeDef",
     "UntagResourceInputRequestTypeDef",
     "UpdateApplicationInputRequestTypeDef",
     "AddTagsToOnPremisesInstancesInputRequestTypeDef",
     "CreateApplicationInputRequestTypeDef",
     "InstanceInfoTypeDef",
+    "ListTagsForResourceOutputTypeDef",
     "RemoveTagsFromOnPremisesInstancesInputRequestTypeDef",
     "TagResourceInputRequestTypeDef",
     "AlarmConfigurationTypeDef",
     "BatchGetApplicationsOutputTypeDef",
-    "CreateApplicationOutputTypeDef",
-    "CreateDeploymentConfigOutputTypeDef",
-    "CreateDeploymentGroupOutputTypeDef",
-    "CreateDeploymentOutputTypeDef",
-    "DeleteDeploymentGroupOutputTypeDef",
-    "DeleteGitHubAccountTokenOutputTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "GetApplicationOutputTypeDef",
-    "ListApplicationsOutputTypeDef",
-    "ListDeploymentConfigsOutputTypeDef",
-    "ListDeploymentGroupsOutputTypeDef",
-    "ListDeploymentInstancesOutputTypeDef",
-    "ListDeploymentTargetsOutputTypeDef",
-    "ListDeploymentsOutputTypeDef",
-    "ListGitHubAccountTokenNamesOutputTypeDef",
-    "ListOnPremisesInstancesOutputTypeDef",
-    "ListTagsForResourceOutputTypeDef",
-    "PutLifecycleEventHookExecutionStatusOutputTypeDef",
-    "StopDeploymentOutputTypeDef",
+    "DeleteDeploymentGroupOutputTypeDef",
     "UpdateDeploymentGroupOutputTypeDef",
     "BlueGreenDeploymentConfigurationTypeDef",
     "EC2TagSetTypeDef",
+    "ListOnPremisesInstancesInputListOnPremisesInstancesPaginateTypeDef",
     "ListOnPremisesInstancesInputRequestTypeDef",
     "OnPremisesTagSetTypeDef",
     "LifecycleEventTypeDef",
     "ECSTaskSetTypeDef",
     "GetDeploymentInputDeploymentSuccessfulWaitTypeDef",
-    "ListApplicationRevisionsInputListApplicationRevisionsPaginateTypeDef",
-    "ListApplicationsInputListApplicationsPaginateTypeDef",
-    "ListDeploymentConfigsInputListDeploymentConfigsPaginateTypeDef",
-    "ListDeploymentGroupsInputListDeploymentGroupsPaginateTypeDef",
-    "ListDeploymentInstancesInputListDeploymentInstancesPaginateTypeDef",
-    "ListDeploymentTargetsInputListDeploymentTargetsPaginateTypeDef",
-    "ListGitHubAccountTokenNamesInputListGitHubAccountTokenNamesPaginateTypeDef",
-    "ListOnPremisesInstancesInputListOnPremisesInstancesPaginateTypeDef",
     "ListDeploymentsInputListDeploymentsPaginateTypeDef",
     "ListDeploymentsInputRequestTypeDef",
     "RevisionLocationTypeDef",
     "TargetGroupPairInfoTypeDef",
     "TrafficRoutingConfigTypeDef",
     "BatchGetOnPremisesInstancesOutputTypeDef",
     "GetOnPremisesInstanceOutputTypeDef",
@@ -262,25 +262,14 @@
     {
         "name": str,
         "hook": str,
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
 BatchGetApplicationsInputRequestTypeDef = TypedDict(
     "BatchGetApplicationsInputRequestTypeDef",
     {
         "applicationNames": Sequence[str],
     },
 )
 
@@ -354,23 +343,39 @@
     {
         "deploymentId": str,
         "deploymentWaitType": DeploymentWaitTypeType,
     },
     total=False,
 )
 
+CreateApplicationOutputTypeDef = TypedDict(
+    "CreateApplicationOutputTypeDef",
+    {
+        "applicationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 MinimumHealthyHostsTypeDef = TypedDict(
     "MinimumHealthyHostsTypeDef",
     {
         "type": MinimumHealthyHostsTypeType,
         "value": int,
     },
     total=False,
 )
 
+CreateDeploymentConfigOutputTypeDef = TypedDict(
+    "CreateDeploymentConfigOutputTypeDef",
+    {
+        "deploymentConfigId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeploymentStyleTypeDef = TypedDict(
     "DeploymentStyleTypeDef",
     {
         "deploymentType": DeploymentTypeType,
         "deploymentOption": DeploymentOptionType,
     },
     total=False,
@@ -411,14 +416,30 @@
         "triggerName": str,
         "triggerTargetArn": str,
         "triggerEvents": List[TriggerEventTypeType],
     },
     total=False,
 )
 
+CreateDeploymentGroupOutputTypeDef = TypedDict(
+    "CreateDeploymentGroupOutputTypeDef",
+    {
+        "deploymentGroupId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateDeploymentOutputTypeDef = TypedDict(
+    "CreateDeploymentOutputTypeDef",
+    {
+        "deploymentId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteApplicationInputRequestTypeDef = TypedDict(
     "DeleteApplicationInputRequestTypeDef",
     {
         "applicationName": str,
     },
 )
 
@@ -441,14 +462,22 @@
     "DeleteGitHubAccountTokenInputRequestTypeDef",
     {
         "tokenName": str,
     },
     total=False,
 )
 
+DeleteGitHubAccountTokenOutputTypeDef = TypedDict(
+    "DeleteGitHubAccountTokenOutputTypeDef",
+    {
+        "tokenName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteResourcesByExternalIdInputRequestTypeDef = TypedDict(
     "DeleteResourcesByExternalIdInputRequestTypeDef",
     {
         "externalId": str,
     },
     total=False,
 )
@@ -535,14 +564,21 @@
     "ELBInfoTypeDef",
     {
         "name": str,
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
 GenericRevisionInfoTypeDef = TypedDict(
     "GenericRevisionInfoTypeDef",
     {
         "description": str,
         "deploymentGroups": List[str],
         "firstUsedTime": datetime,
         "lastUsedTime": datetime,
@@ -630,24 +666,41 @@
         "currentVersion": str,
         "targetVersion": str,
         "targetVersionWeight": float,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListApplicationRevisionsInputListApplicationRevisionsPaginateTypeDef = TypedDict(
+    "_RequiredListApplicationRevisionsInputListApplicationRevisionsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "applicationName": str,
+    },
+)
+_OptionalListApplicationRevisionsInputListApplicationRevisionsPaginateTypeDef = TypedDict(
+    "_OptionalListApplicationRevisionsInputListApplicationRevisionsPaginateTypeDef",
+    {
+        "sortBy": ApplicationRevisionSortByType,
+        "sortOrder": SortOrderType,
+        "s3Bucket": str,
+        "s3KeyPrefix": str,
+        "deployed": ListStateFilterActionType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListApplicationRevisionsInputListApplicationRevisionsPaginateTypeDef(
+    _RequiredListApplicationRevisionsInputListApplicationRevisionsPaginateTypeDef,
+    _OptionalListApplicationRevisionsInputListApplicationRevisionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListApplicationRevisionsInputRequestTypeDef = TypedDict(
     "_RequiredListApplicationRevisionsInputRequestTypeDef",
     {
         "applicationName": str,
     },
 )
 _OptionalListApplicationRevisionsInputRequestTypeDef = TypedDict(
@@ -667,30 +720,86 @@
 class ListApplicationRevisionsInputRequestTypeDef(
     _RequiredListApplicationRevisionsInputRequestTypeDef,
     _OptionalListApplicationRevisionsInputRequestTypeDef,
 ):
     pass
 
 
+ListApplicationsInputListApplicationsPaginateTypeDef = TypedDict(
+    "ListApplicationsInputListApplicationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListApplicationsInputRequestTypeDef = TypedDict(
     "ListApplicationsInputRequestTypeDef",
     {
         "nextToken": str,
     },
     total=False,
 )
 
+ListApplicationsOutputTypeDef = TypedDict(
+    "ListApplicationsOutputTypeDef",
+    {
+        "applications": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListDeploymentConfigsInputListDeploymentConfigsPaginateTypeDef = TypedDict(
+    "ListDeploymentConfigsInputListDeploymentConfigsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDeploymentConfigsInputRequestTypeDef = TypedDict(
     "ListDeploymentConfigsInputRequestTypeDef",
     {
         "nextToken": str,
     },
     total=False,
 )
 
+ListDeploymentConfigsOutputTypeDef = TypedDict(
+    "ListDeploymentConfigsOutputTypeDef",
+    {
+        "deploymentConfigsList": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListDeploymentGroupsInputListDeploymentGroupsPaginateTypeDef = TypedDict(
+    "_RequiredListDeploymentGroupsInputListDeploymentGroupsPaginateTypeDef",
+    {
+        "applicationName": str,
+    },
+)
+_OptionalListDeploymentGroupsInputListDeploymentGroupsPaginateTypeDef = TypedDict(
+    "_OptionalListDeploymentGroupsInputListDeploymentGroupsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListDeploymentGroupsInputListDeploymentGroupsPaginateTypeDef(
+    _RequiredListDeploymentGroupsInputListDeploymentGroupsPaginateTypeDef,
+    _OptionalListDeploymentGroupsInputListDeploymentGroupsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListDeploymentGroupsInputRequestTypeDef = TypedDict(
     "_RequiredListDeploymentGroupsInputRequestTypeDef",
     {
         "applicationName": str,
     },
 )
 _OptionalListDeploymentGroupsInputRequestTypeDef = TypedDict(
@@ -705,14 +814,48 @@
 class ListDeploymentGroupsInputRequestTypeDef(
     _RequiredListDeploymentGroupsInputRequestTypeDef,
     _OptionalListDeploymentGroupsInputRequestTypeDef,
 ):
     pass
 
 
+ListDeploymentGroupsOutputTypeDef = TypedDict(
+    "ListDeploymentGroupsOutputTypeDef",
+    {
+        "applicationName": str,
+        "deploymentGroups": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListDeploymentInstancesInputListDeploymentInstancesPaginateTypeDef = TypedDict(
+    "_RequiredListDeploymentInstancesInputListDeploymentInstancesPaginateTypeDef",
+    {
+        "deploymentId": str,
+    },
+)
+_OptionalListDeploymentInstancesInputListDeploymentInstancesPaginateTypeDef = TypedDict(
+    "_OptionalListDeploymentInstancesInputListDeploymentInstancesPaginateTypeDef",
+    {
+        "instanceStatusFilter": Sequence[InstanceStatusType],
+        "instanceTypeFilter": Sequence[InstanceTypeType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListDeploymentInstancesInputListDeploymentInstancesPaginateTypeDef(
+    _RequiredListDeploymentInstancesInputListDeploymentInstancesPaginateTypeDef,
+    _OptionalListDeploymentInstancesInputListDeploymentInstancesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListDeploymentInstancesInputRequestTypeDef = TypedDict(
     "_RequiredListDeploymentInstancesInputRequestTypeDef",
     {
         "deploymentId": str,
     },
 )
 _OptionalListDeploymentInstancesInputRequestTypeDef = TypedDict(
@@ -729,41 +872,104 @@
 class ListDeploymentInstancesInputRequestTypeDef(
     _RequiredListDeploymentInstancesInputRequestTypeDef,
     _OptionalListDeploymentInstancesInputRequestTypeDef,
 ):
     pass
 
 
+ListDeploymentInstancesOutputTypeDef = TypedDict(
+    "ListDeploymentInstancesOutputTypeDef",
+    {
+        "instancesList": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListDeploymentTargetsInputListDeploymentTargetsPaginateTypeDef = TypedDict(
+    "ListDeploymentTargetsInputListDeploymentTargetsPaginateTypeDef",
+    {
+        "deploymentId": str,
+        "targetFilters": Mapping[TargetFilterNameType, Sequence[str]],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDeploymentTargetsInputRequestTypeDef = TypedDict(
     "ListDeploymentTargetsInputRequestTypeDef",
     {
         "deploymentId": str,
         "nextToken": str,
         "targetFilters": Mapping[TargetFilterNameType, Sequence[str]],
     },
     total=False,
 )
 
+ListDeploymentTargetsOutputTypeDef = TypedDict(
+    "ListDeploymentTargetsOutputTypeDef",
+    {
+        "targetIds": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TimeRangeTypeDef = TypedDict(
     "TimeRangeTypeDef",
     {
         "start": Union[datetime, str],
         "end": Union[datetime, str],
     },
     total=False,
 )
 
+ListDeploymentsOutputTypeDef = TypedDict(
+    "ListDeploymentsOutputTypeDef",
+    {
+        "deployments": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListGitHubAccountTokenNamesInputListGitHubAccountTokenNamesPaginateTypeDef = TypedDict(
+    "ListGitHubAccountTokenNamesInputListGitHubAccountTokenNamesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListGitHubAccountTokenNamesInputRequestTypeDef = TypedDict(
     "ListGitHubAccountTokenNamesInputRequestTypeDef",
     {
         "nextToken": str,
     },
     total=False,
 )
 
+ListGitHubAccountTokenNamesOutputTypeDef = TypedDict(
+    "ListGitHubAccountTokenNamesOutputTypeDef",
+    {
+        "tokenNameList": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListOnPremisesInstancesOutputTypeDef = TypedDict(
+    "ListOnPremisesInstancesOutputTypeDef",
+    {
+        "instanceNames": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredListTagsForResourceInputRequestTypeDef = TypedDict(
     "_RequiredListTagsForResourceInputRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 _OptionalListTagsForResourceInputRequestTypeDef = TypedDict(
@@ -777,24 +983,42 @@
 
 class ListTagsForResourceInputRequestTypeDef(
     _RequiredListTagsForResourceInputRequestTypeDef, _OptionalListTagsForResourceInputRequestTypeDef
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
 PutLifecycleEventHookExecutionStatusInputRequestTypeDef = TypedDict(
     "PutLifecycleEventHookExecutionStatusInputRequestTypeDef",
     {
         "deploymentId": str,
         "lifecycleEventHookExecutionId": str,
         "status": LifecycleEventStatusType,
     },
     total=False,
 )
 
+PutLifecycleEventHookExecutionStatusOutputTypeDef = TypedDict(
+    "PutLifecycleEventHookExecutionStatusOutputTypeDef",
+    {
+        "lifecycleEventHookExecutionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RawStringTypeDef = TypedDict(
     "RawStringTypeDef",
     {
         "content": str,
         "sha256": str,
     },
     total=False,
@@ -819,14 +1043,25 @@
 class RegisterOnPremisesInstanceInputRequestTypeDef(
     _RequiredRegisterOnPremisesInstanceInputRequestTypeDef,
     _OptionalRegisterOnPremisesInstanceInputRequestTypeDef,
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
 S3LocationTypeDef = TypedDict(
     "S3LocationTypeDef",
     {
         "bucket": str,
         "key": str,
         "bundleType": BundleTypeType,
         "version": str,
@@ -860,14 +1095,23 @@
 
 class StopDeploymentInputRequestTypeDef(
     _RequiredStopDeploymentInputRequestTypeDef, _OptionalStopDeploymentInputRequestTypeDef
 ):
     pass
 
 
+StopDeploymentOutputTypeDef = TypedDict(
+    "StopDeploymentOutputTypeDef",
+    {
+        "status": StopStatusType,
+        "statusMessage": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TrafficRouteTypeDef = TypedDict(
     "TrafficRouteTypeDef",
     {
         "listenerArns": List[str],
     },
     total=False,
 )
@@ -947,14 +1191,23 @@
         "registerTime": datetime,
         "deregisterTime": datetime,
         "tags": List[TagTypeDef],
     },
     total=False,
 )
 
+ListTagsForResourceOutputTypeDef = TypedDict(
+    "ListTagsForResourceOutputTypeDef",
+    {
+        "Tags": List[TagTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RemoveTagsFromOnPremisesInstancesInputRequestTypeDef = TypedDict(
     "RemoveTagsFromOnPremisesInstancesInputRequestTypeDef",
     {
         "tags": Sequence[TagTypeDef],
         "instanceNames": Sequence[str],
     },
 )
@@ -977,185 +1230,39 @@
     total=False,
 )
 
 BatchGetApplicationsOutputTypeDef = TypedDict(
     "BatchGetApplicationsOutputTypeDef",
     {
         "applicationsInfo": List[ApplicationInfoTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateApplicationOutputTypeDef = TypedDict(
-    "CreateApplicationOutputTypeDef",
-    {
-        "applicationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDeploymentConfigOutputTypeDef = TypedDict(
-    "CreateDeploymentConfigOutputTypeDef",
-    {
-        "deploymentConfigId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDeploymentGroupOutputTypeDef = TypedDict(
-    "CreateDeploymentGroupOutputTypeDef",
-    {
-        "deploymentGroupId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDeploymentOutputTypeDef = TypedDict(
-    "CreateDeploymentOutputTypeDef",
-    {
-        "deploymentId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteDeploymentGroupOutputTypeDef = TypedDict(
-    "DeleteDeploymentGroupOutputTypeDef",
-    {
-        "hooksNotCleanedUp": List[AutoScalingGroupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteGitHubAccountTokenOutputTypeDef = TypedDict(
-    "DeleteGitHubAccountTokenOutputTypeDef",
-    {
-        "tokenName": str,
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
 
 GetApplicationOutputTypeDef = TypedDict(
     "GetApplicationOutputTypeDef",
     {
         "application": ApplicationInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListApplicationsOutputTypeDef = TypedDict(
-    "ListApplicationsOutputTypeDef",
-    {
-        "applications": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDeploymentConfigsOutputTypeDef = TypedDict(
-    "ListDeploymentConfigsOutputTypeDef",
-    {
-        "deploymentConfigsList": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDeploymentGroupsOutputTypeDef = TypedDict(
-    "ListDeploymentGroupsOutputTypeDef",
-    {
-        "applicationName": str,
-        "deploymentGroups": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListDeploymentInstancesOutputTypeDef = TypedDict(
-    "ListDeploymentInstancesOutputTypeDef",
-    {
-        "instancesList": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDeploymentTargetsOutputTypeDef = TypedDict(
-    "ListDeploymentTargetsOutputTypeDef",
-    {
-        "targetIds": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDeploymentsOutputTypeDef = TypedDict(
-    "ListDeploymentsOutputTypeDef",
-    {
-        "deployments": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListGitHubAccountTokenNamesOutputTypeDef = TypedDict(
-    "ListGitHubAccountTokenNamesOutputTypeDef",
-    {
-        "tokenNameList": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListOnPremisesInstancesOutputTypeDef = TypedDict(
-    "ListOnPremisesInstancesOutputTypeDef",
-    {
-        "instanceNames": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceOutputTypeDef = TypedDict(
-    "ListTagsForResourceOutputTypeDef",
-    {
-        "Tags": List[TagTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutLifecycleEventHookExecutionStatusOutputTypeDef = TypedDict(
-    "PutLifecycleEventHookExecutionStatusOutputTypeDef",
-    {
-        "lifecycleEventHookExecutionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StopDeploymentOutputTypeDef = TypedDict(
-    "StopDeploymentOutputTypeDef",
+DeleteDeploymentGroupOutputTypeDef = TypedDict(
+    "DeleteDeploymentGroupOutputTypeDef",
     {
-        "status": StopStatusType,
-        "statusMessage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "hooksNotCleanedUp": List[AutoScalingGroupTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDeploymentGroupOutputTypeDef = TypedDict(
     "UpdateDeploymentGroupOutputTypeDef",
     {
         "hooksNotCleanedUp": List[AutoScalingGroupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BlueGreenDeploymentConfigurationTypeDef = TypedDict(
     "BlueGreenDeploymentConfigurationTypeDef",
     {
         "terminateBlueInstancesOnDeploymentSuccess": BlueInstanceTerminationOptionTypeDef,
@@ -1169,14 +1276,24 @@
     "EC2TagSetTypeDef",
     {
         "ec2TagSetList": List[List[EC2TagFilterTypeDef]],
     },
     total=False,
 )
 
+ListOnPremisesInstancesInputListOnPremisesInstancesPaginateTypeDef = TypedDict(
+    "ListOnPremisesInstancesInputListOnPremisesInstancesPaginateTypeDef",
+    {
+        "registrationStatus": RegistrationStatusType,
+        "tagFilters": Sequence[TagFilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListOnPremisesInstancesInputRequestTypeDef = TypedDict(
     "ListOnPremisesInstancesInputRequestTypeDef",
     {
         "registrationStatus": RegistrationStatusType,
         "tagFilters": Sequence[TagFilterTypeDef],
         "nextToken": str,
     },
@@ -1236,140 +1353,23 @@
 class GetDeploymentInputDeploymentSuccessfulWaitTypeDef(
     _RequiredGetDeploymentInputDeploymentSuccessfulWaitTypeDef,
     _OptionalGetDeploymentInputDeploymentSuccessfulWaitTypeDef,
 ):
     pass
 
 
-_RequiredListApplicationRevisionsInputListApplicationRevisionsPaginateTypeDef = TypedDict(
-    "_RequiredListApplicationRevisionsInputListApplicationRevisionsPaginateTypeDef",
-    {
-        "applicationName": str,
-    },
-)
-_OptionalListApplicationRevisionsInputListApplicationRevisionsPaginateTypeDef = TypedDict(
-    "_OptionalListApplicationRevisionsInputListApplicationRevisionsPaginateTypeDef",
-    {
-        "sortBy": ApplicationRevisionSortByType,
-        "sortOrder": SortOrderType,
-        "s3Bucket": str,
-        "s3KeyPrefix": str,
-        "deployed": ListStateFilterActionType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListApplicationRevisionsInputListApplicationRevisionsPaginateTypeDef(
-    _RequiredListApplicationRevisionsInputListApplicationRevisionsPaginateTypeDef,
-    _OptionalListApplicationRevisionsInputListApplicationRevisionsPaginateTypeDef,
-):
-    pass
-
-
-ListApplicationsInputListApplicationsPaginateTypeDef = TypedDict(
-    "ListApplicationsInputListApplicationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListDeploymentConfigsInputListDeploymentConfigsPaginateTypeDef = TypedDict(
-    "ListDeploymentConfigsInputListDeploymentConfigsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListDeploymentGroupsInputListDeploymentGroupsPaginateTypeDef = TypedDict(
-    "_RequiredListDeploymentGroupsInputListDeploymentGroupsPaginateTypeDef",
-    {
-        "applicationName": str,
-    },
-)
-_OptionalListDeploymentGroupsInputListDeploymentGroupsPaginateTypeDef = TypedDict(
-    "_OptionalListDeploymentGroupsInputListDeploymentGroupsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListDeploymentGroupsInputListDeploymentGroupsPaginateTypeDef(
-    _RequiredListDeploymentGroupsInputListDeploymentGroupsPaginateTypeDef,
-    _OptionalListDeploymentGroupsInputListDeploymentGroupsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListDeploymentInstancesInputListDeploymentInstancesPaginateTypeDef = TypedDict(
-    "_RequiredListDeploymentInstancesInputListDeploymentInstancesPaginateTypeDef",
-    {
-        "deploymentId": str,
-    },
-)
-_OptionalListDeploymentInstancesInputListDeploymentInstancesPaginateTypeDef = TypedDict(
-    "_OptionalListDeploymentInstancesInputListDeploymentInstancesPaginateTypeDef",
-    {
-        "instanceStatusFilter": Sequence[InstanceStatusType],
-        "instanceTypeFilter": Sequence[InstanceTypeType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListDeploymentInstancesInputListDeploymentInstancesPaginateTypeDef(
-    _RequiredListDeploymentInstancesInputListDeploymentInstancesPaginateTypeDef,
-    _OptionalListDeploymentInstancesInputListDeploymentInstancesPaginateTypeDef,
-):
-    pass
-
-
-ListDeploymentTargetsInputListDeploymentTargetsPaginateTypeDef = TypedDict(
-    "ListDeploymentTargetsInputListDeploymentTargetsPaginateTypeDef",
-    {
-        "deploymentId": str,
-        "targetFilters": Mapping[TargetFilterNameType, Sequence[str]],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListGitHubAccountTokenNamesInputListGitHubAccountTokenNamesPaginateTypeDef = TypedDict(
-    "ListGitHubAccountTokenNamesInputListGitHubAccountTokenNamesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListOnPremisesInstancesInputListOnPremisesInstancesPaginateTypeDef = TypedDict(
-    "ListOnPremisesInstancesInputListOnPremisesInstancesPaginateTypeDef",
-    {
-        "registrationStatus": RegistrationStatusType,
-        "tagFilters": Sequence[TagFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListDeploymentsInputListDeploymentsPaginateTypeDef = TypedDict(
     "ListDeploymentsInputListDeploymentsPaginateTypeDef",
     {
         "applicationName": str,
         "deploymentGroupName": str,
         "externalId": str,
         "includeOnlyStatuses": Sequence[DeploymentStatusType],
         "createTimeRange": TimeRangeTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListDeploymentsInputRequestTypeDef = TypedDict(
     "ListDeploymentsInputRequestTypeDef",
     {
@@ -1415,23 +1415,23 @@
     total=False,
 )
 
 BatchGetOnPremisesInstancesOutputTypeDef = TypedDict(
     "BatchGetOnPremisesInstancesOutputTypeDef",
     {
         "instanceInfos": List[InstanceInfoTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetOnPremisesInstanceOutputTypeDef = TypedDict(
     "GetOnPremisesInstanceOutputTypeDef",
     {
         "instanceInfo": InstanceInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TargetInstancesTypeDef = TypedDict(
     "TargetInstancesTypeDef",
     {
         "tagFilters": List[EC2TagFilterTypeDef],
@@ -1528,24 +1528,24 @@
 
 GetApplicationRevisionOutputTypeDef = TypedDict(
     "GetApplicationRevisionOutputTypeDef",
     {
         "applicationName": str,
         "revision": RevisionLocationTypeDef,
         "revisionInfo": GenericRevisionInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListApplicationRevisionsOutputTypeDef = TypedDict(
     "ListApplicationRevisionsOutputTypeDef",
     {
         "revisions": List[RevisionLocationTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredRegisterApplicationRevisionInputRequestTypeDef = TypedDict(
     "_RequiredRegisterApplicationRevisionInputRequestTypeDef",
     {
         "applicationName": str,
@@ -1655,23 +1655,23 @@
 
 
 BatchGetDeploymentInstancesOutputTypeDef = TypedDict(
     "BatchGetDeploymentInstancesOutputTypeDef",
     {
         "instancesSummary": List[InstanceSummaryTypeDef],
         "errorMessage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDeploymentInstanceOutputTypeDef = TypedDict(
     "GetDeploymentInstanceOutputTypeDef",
     {
         "instanceSummary": InstanceSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeploymentTargetTypeDef = TypedDict(
     "DeploymentTargetTypeDef",
     {
         "deploymentTargetType": DeploymentTargetTypeType,
@@ -1685,15 +1685,15 @@
 
 BatchGetApplicationRevisionsOutputTypeDef = TypedDict(
     "BatchGetApplicationRevisionsOutputTypeDef",
     {
         "applicationName": str,
         "errorMessage": str,
         "revisions": List[RevisionInfoTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateDeploymentGroupInputRequestTypeDef = TypedDict(
     "_RequiredCreateDeploymentGroupInputRequestTypeDef",
     {
         "applicationName": str,
@@ -1835,59 +1835,59 @@
     pass
 
 
 GetDeploymentConfigOutputTypeDef = TypedDict(
     "GetDeploymentConfigOutputTypeDef",
     {
         "deploymentConfigInfo": DeploymentConfigInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetDeploymentTargetsOutputTypeDef = TypedDict(
     "BatchGetDeploymentTargetsOutputTypeDef",
     {
         "deploymentTargets": List[DeploymentTargetTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDeploymentTargetOutputTypeDef = TypedDict(
     "GetDeploymentTargetOutputTypeDef",
     {
         "deploymentTarget": DeploymentTargetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetDeploymentGroupsOutputTypeDef = TypedDict(
     "BatchGetDeploymentGroupsOutputTypeDef",
     {
         "deploymentGroupsInfo": List[DeploymentGroupInfoTypeDef],
         "errorMessage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDeploymentGroupOutputTypeDef = TypedDict(
     "GetDeploymentGroupOutputTypeDef",
     {
         "deploymentGroupInfo": DeploymentGroupInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetDeploymentsOutputTypeDef = TypedDict(
     "BatchGetDeploymentsOutputTypeDef",
     {
         "deploymentsInfo": List[DeploymentInfoTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDeploymentOutputTypeDef = TypedDict(
     "GetDeploymentOutputTypeDef",
     {
         "deploymentInfo": DeploymentInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-codedeploy-2.5.0.post1/types_aiobotocore_codedeploy/type_defs.pyi` & `types-aiobotocore-codedeploy-2.5.1/types_aiobotocore_codedeploy/type_defs.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -59,119 +59,119 @@
 __all__ = (
     "TagTypeDef",
     "AlarmTypeDef",
     "AppSpecContentTypeDef",
     "ApplicationInfoTypeDef",
     "AutoRollbackConfigurationTypeDef",
     "AutoScalingGroupTypeDef",
-    "ResponseMetadataTypeDef",
     "BatchGetApplicationsInputRequestTypeDef",
     "BatchGetDeploymentGroupsInputRequestTypeDef",
     "BatchGetDeploymentInstancesInputRequestTypeDef",
     "BatchGetDeploymentTargetsInputRequestTypeDef",
     "BatchGetDeploymentsInputRequestTypeDef",
     "BatchGetOnPremisesInstancesInputRequestTypeDef",
     "BlueInstanceTerminationOptionTypeDef",
     "DeploymentReadyOptionTypeDef",
     "GreenFleetProvisioningOptionTypeDef",
     "ContinueDeploymentInputRequestTypeDef",
+    "CreateApplicationOutputTypeDef",
     "MinimumHealthyHostsTypeDef",
+    "CreateDeploymentConfigOutputTypeDef",
     "DeploymentStyleTypeDef",
     "EC2TagFilterTypeDef",
     "ECSServiceTypeDef",
     "TagFilterTypeDef",
     "TriggerConfigTypeDef",
+    "CreateDeploymentGroupOutputTypeDef",
+    "CreateDeploymentOutputTypeDef",
     "DeleteApplicationInputRequestTypeDef",
     "DeleteDeploymentConfigInputRequestTypeDef",
     "DeleteDeploymentGroupInputRequestTypeDef",
     "DeleteGitHubAccountTokenInputRequestTypeDef",
+    "DeleteGitHubAccountTokenOutputTypeDef",
     "DeleteResourcesByExternalIdInputRequestTypeDef",
     "LastDeploymentInfoTypeDef",
     "DeploymentOverviewTypeDef",
     "ErrorInformationTypeDef",
     "RelatedDeploymentsTypeDef",
     "RollbackInfoTypeDef",
     "DeregisterOnPremisesInstanceInputRequestTypeDef",
     "DiagnosticsTypeDef",
     "TargetGroupInfoTypeDef",
     "ELBInfoTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "GenericRevisionInfoTypeDef",
     "GetApplicationInputRequestTypeDef",
     "GetDeploymentConfigInputRequestTypeDef",
     "GetDeploymentGroupInputRequestTypeDef",
     "WaiterConfigTypeDef",
     "GetDeploymentInputRequestTypeDef",
     "GetDeploymentInstanceInputRequestTypeDef",
     "GetDeploymentTargetInputRequestTypeDef",
     "GetOnPremisesInstanceInputRequestTypeDef",
     "GitHubLocationTypeDef",
     "LambdaFunctionInfoTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListApplicationRevisionsInputListApplicationRevisionsPaginateTypeDef",
     "ListApplicationRevisionsInputRequestTypeDef",
+    "ListApplicationsInputListApplicationsPaginateTypeDef",
     "ListApplicationsInputRequestTypeDef",
+    "ListApplicationsOutputTypeDef",
+    "ListDeploymentConfigsInputListDeploymentConfigsPaginateTypeDef",
     "ListDeploymentConfigsInputRequestTypeDef",
+    "ListDeploymentConfigsOutputTypeDef",
+    "ListDeploymentGroupsInputListDeploymentGroupsPaginateTypeDef",
     "ListDeploymentGroupsInputRequestTypeDef",
+    "ListDeploymentGroupsOutputTypeDef",
+    "ListDeploymentInstancesInputListDeploymentInstancesPaginateTypeDef",
     "ListDeploymentInstancesInputRequestTypeDef",
+    "ListDeploymentInstancesOutputTypeDef",
+    "ListDeploymentTargetsInputListDeploymentTargetsPaginateTypeDef",
     "ListDeploymentTargetsInputRequestTypeDef",
+    "ListDeploymentTargetsOutputTypeDef",
     "TimeRangeTypeDef",
+    "ListDeploymentsOutputTypeDef",
+    "ListGitHubAccountTokenNamesInputListGitHubAccountTokenNamesPaginateTypeDef",
     "ListGitHubAccountTokenNamesInputRequestTypeDef",
+    "ListGitHubAccountTokenNamesOutputTypeDef",
+    "ListOnPremisesInstancesOutputTypeDef",
     "ListTagsForResourceInputRequestTypeDef",
+    "PaginatorConfigTypeDef",
     "PutLifecycleEventHookExecutionStatusInputRequestTypeDef",
+    "PutLifecycleEventHookExecutionStatusOutputTypeDef",
     "RawStringTypeDef",
     "RegisterOnPremisesInstanceInputRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "S3LocationTypeDef",
     "SkipWaitTimeForInstanceTerminationInputRequestTypeDef",
     "StopDeploymentInputRequestTypeDef",
+    "StopDeploymentOutputTypeDef",
     "TrafficRouteTypeDef",
     "TimeBasedCanaryTypeDef",
     "TimeBasedLinearTypeDef",
     "UntagResourceInputRequestTypeDef",
     "UpdateApplicationInputRequestTypeDef",
     "AddTagsToOnPremisesInstancesInputRequestTypeDef",
     "CreateApplicationInputRequestTypeDef",
     "InstanceInfoTypeDef",
+    "ListTagsForResourceOutputTypeDef",
     "RemoveTagsFromOnPremisesInstancesInputRequestTypeDef",
     "TagResourceInputRequestTypeDef",
     "AlarmConfigurationTypeDef",
     "BatchGetApplicationsOutputTypeDef",
-    "CreateApplicationOutputTypeDef",
-    "CreateDeploymentConfigOutputTypeDef",
-    "CreateDeploymentGroupOutputTypeDef",
-    "CreateDeploymentOutputTypeDef",
-    "DeleteDeploymentGroupOutputTypeDef",
-    "DeleteGitHubAccountTokenOutputTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "GetApplicationOutputTypeDef",
-    "ListApplicationsOutputTypeDef",
-    "ListDeploymentConfigsOutputTypeDef",
-    "ListDeploymentGroupsOutputTypeDef",
-    "ListDeploymentInstancesOutputTypeDef",
-    "ListDeploymentTargetsOutputTypeDef",
-    "ListDeploymentsOutputTypeDef",
-    "ListGitHubAccountTokenNamesOutputTypeDef",
-    "ListOnPremisesInstancesOutputTypeDef",
-    "ListTagsForResourceOutputTypeDef",
-    "PutLifecycleEventHookExecutionStatusOutputTypeDef",
-    "StopDeploymentOutputTypeDef",
+    "DeleteDeploymentGroupOutputTypeDef",
     "UpdateDeploymentGroupOutputTypeDef",
     "BlueGreenDeploymentConfigurationTypeDef",
     "EC2TagSetTypeDef",
+    "ListOnPremisesInstancesInputListOnPremisesInstancesPaginateTypeDef",
     "ListOnPremisesInstancesInputRequestTypeDef",
     "OnPremisesTagSetTypeDef",
     "LifecycleEventTypeDef",
     "ECSTaskSetTypeDef",
     "GetDeploymentInputDeploymentSuccessfulWaitTypeDef",
-    "ListApplicationRevisionsInputListApplicationRevisionsPaginateTypeDef",
-    "ListApplicationsInputListApplicationsPaginateTypeDef",
-    "ListDeploymentConfigsInputListDeploymentConfigsPaginateTypeDef",
-    "ListDeploymentGroupsInputListDeploymentGroupsPaginateTypeDef",
-    "ListDeploymentInstancesInputListDeploymentInstancesPaginateTypeDef",
-    "ListDeploymentTargetsInputListDeploymentTargetsPaginateTypeDef",
-    "ListGitHubAccountTokenNamesInputListGitHubAccountTokenNamesPaginateTypeDef",
-    "ListOnPremisesInstancesInputListOnPremisesInstancesPaginateTypeDef",
     "ListDeploymentsInputListDeploymentsPaginateTypeDef",
     "ListDeploymentsInputRequestTypeDef",
     "RevisionLocationTypeDef",
     "TargetGroupPairInfoTypeDef",
     "TrafficRoutingConfigTypeDef",
     "BatchGetOnPremisesInstancesOutputTypeDef",
     "GetOnPremisesInstanceOutputTypeDef",
@@ -261,25 +261,14 @@
     {
         "name": str,
         "hook": str,
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
 BatchGetApplicationsInputRequestTypeDef = TypedDict(
     "BatchGetApplicationsInputRequestTypeDef",
     {
         "applicationNames": Sequence[str],
     },
 )
 
@@ -353,23 +342,39 @@
     {
         "deploymentId": str,
         "deploymentWaitType": DeploymentWaitTypeType,
     },
     total=False,
 )
 
+CreateApplicationOutputTypeDef = TypedDict(
+    "CreateApplicationOutputTypeDef",
+    {
+        "applicationId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 MinimumHealthyHostsTypeDef = TypedDict(
     "MinimumHealthyHostsTypeDef",
     {
         "type": MinimumHealthyHostsTypeType,
         "value": int,
     },
     total=False,
 )
 
+CreateDeploymentConfigOutputTypeDef = TypedDict(
+    "CreateDeploymentConfigOutputTypeDef",
+    {
+        "deploymentConfigId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeploymentStyleTypeDef = TypedDict(
     "DeploymentStyleTypeDef",
     {
         "deploymentType": DeploymentTypeType,
         "deploymentOption": DeploymentOptionType,
     },
     total=False,
@@ -410,14 +415,30 @@
         "triggerName": str,
         "triggerTargetArn": str,
         "triggerEvents": List[TriggerEventTypeType],
     },
     total=False,
 )
 
+CreateDeploymentGroupOutputTypeDef = TypedDict(
+    "CreateDeploymentGroupOutputTypeDef",
+    {
+        "deploymentGroupId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreateDeploymentOutputTypeDef = TypedDict(
+    "CreateDeploymentOutputTypeDef",
+    {
+        "deploymentId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteApplicationInputRequestTypeDef = TypedDict(
     "DeleteApplicationInputRequestTypeDef",
     {
         "applicationName": str,
     },
 )
 
@@ -440,14 +461,22 @@
     "DeleteGitHubAccountTokenInputRequestTypeDef",
     {
         "tokenName": str,
     },
     total=False,
 )
 
+DeleteGitHubAccountTokenOutputTypeDef = TypedDict(
+    "DeleteGitHubAccountTokenOutputTypeDef",
+    {
+        "tokenName": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteResourcesByExternalIdInputRequestTypeDef = TypedDict(
     "DeleteResourcesByExternalIdInputRequestTypeDef",
     {
         "externalId": str,
     },
     total=False,
 )
@@ -534,14 +563,21 @@
     "ELBInfoTypeDef",
     {
         "name": str,
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
 GenericRevisionInfoTypeDef = TypedDict(
     "GenericRevisionInfoTypeDef",
     {
         "description": str,
         "deploymentGroups": List[str],
         "firstUsedTime": datetime,
         "lastUsedTime": datetime,
@@ -629,24 +665,39 @@
         "currentVersion": str,
         "targetVersion": str,
         "targetVersionWeight": float,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListApplicationRevisionsInputListApplicationRevisionsPaginateTypeDef = TypedDict(
+    "_RequiredListApplicationRevisionsInputListApplicationRevisionsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "applicationName": str,
+    },
+)
+_OptionalListApplicationRevisionsInputListApplicationRevisionsPaginateTypeDef = TypedDict(
+    "_OptionalListApplicationRevisionsInputListApplicationRevisionsPaginateTypeDef",
+    {
+        "sortBy": ApplicationRevisionSortByType,
+        "sortOrder": SortOrderType,
+        "s3Bucket": str,
+        "s3KeyPrefix": str,
+        "deployed": ListStateFilterActionType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListApplicationRevisionsInputListApplicationRevisionsPaginateTypeDef(
+    _RequiredListApplicationRevisionsInputListApplicationRevisionsPaginateTypeDef,
+    _OptionalListApplicationRevisionsInputListApplicationRevisionsPaginateTypeDef,
+):
+    pass
+
 _RequiredListApplicationRevisionsInputRequestTypeDef = TypedDict(
     "_RequiredListApplicationRevisionsInputRequestTypeDef",
     {
         "applicationName": str,
     },
 )
 _OptionalListApplicationRevisionsInputRequestTypeDef = TypedDict(
@@ -664,30 +715,84 @@
 
 class ListApplicationRevisionsInputRequestTypeDef(
     _RequiredListApplicationRevisionsInputRequestTypeDef,
     _OptionalListApplicationRevisionsInputRequestTypeDef,
 ):
     pass
 
+ListApplicationsInputListApplicationsPaginateTypeDef = TypedDict(
+    "ListApplicationsInputListApplicationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListApplicationsInputRequestTypeDef = TypedDict(
     "ListApplicationsInputRequestTypeDef",
     {
         "nextToken": str,
     },
     total=False,
 )
 
+ListApplicationsOutputTypeDef = TypedDict(
+    "ListApplicationsOutputTypeDef",
+    {
+        "applications": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListDeploymentConfigsInputListDeploymentConfigsPaginateTypeDef = TypedDict(
+    "ListDeploymentConfigsInputListDeploymentConfigsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDeploymentConfigsInputRequestTypeDef = TypedDict(
     "ListDeploymentConfigsInputRequestTypeDef",
     {
         "nextToken": str,
     },
     total=False,
 )
 
+ListDeploymentConfigsOutputTypeDef = TypedDict(
+    "ListDeploymentConfigsOutputTypeDef",
+    {
+        "deploymentConfigsList": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListDeploymentGroupsInputListDeploymentGroupsPaginateTypeDef = TypedDict(
+    "_RequiredListDeploymentGroupsInputListDeploymentGroupsPaginateTypeDef",
+    {
+        "applicationName": str,
+    },
+)
+_OptionalListDeploymentGroupsInputListDeploymentGroupsPaginateTypeDef = TypedDict(
+    "_OptionalListDeploymentGroupsInputListDeploymentGroupsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListDeploymentGroupsInputListDeploymentGroupsPaginateTypeDef(
+    _RequiredListDeploymentGroupsInputListDeploymentGroupsPaginateTypeDef,
+    _OptionalListDeploymentGroupsInputListDeploymentGroupsPaginateTypeDef,
+):
+    pass
+
 _RequiredListDeploymentGroupsInputRequestTypeDef = TypedDict(
     "_RequiredListDeploymentGroupsInputRequestTypeDef",
     {
         "applicationName": str,
     },
 )
 _OptionalListDeploymentGroupsInputRequestTypeDef = TypedDict(
@@ -700,14 +805,46 @@
 
 class ListDeploymentGroupsInputRequestTypeDef(
     _RequiredListDeploymentGroupsInputRequestTypeDef,
     _OptionalListDeploymentGroupsInputRequestTypeDef,
 ):
     pass
 
+ListDeploymentGroupsOutputTypeDef = TypedDict(
+    "ListDeploymentGroupsOutputTypeDef",
+    {
+        "applicationName": str,
+        "deploymentGroups": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListDeploymentInstancesInputListDeploymentInstancesPaginateTypeDef = TypedDict(
+    "_RequiredListDeploymentInstancesInputListDeploymentInstancesPaginateTypeDef",
+    {
+        "deploymentId": str,
+    },
+)
+_OptionalListDeploymentInstancesInputListDeploymentInstancesPaginateTypeDef = TypedDict(
+    "_OptionalListDeploymentInstancesInputListDeploymentInstancesPaginateTypeDef",
+    {
+        "instanceStatusFilter": Sequence[InstanceStatusType],
+        "instanceTypeFilter": Sequence[InstanceTypeType],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListDeploymentInstancesInputListDeploymentInstancesPaginateTypeDef(
+    _RequiredListDeploymentInstancesInputListDeploymentInstancesPaginateTypeDef,
+    _OptionalListDeploymentInstancesInputListDeploymentInstancesPaginateTypeDef,
+):
+    pass
+
 _RequiredListDeploymentInstancesInputRequestTypeDef = TypedDict(
     "_RequiredListDeploymentInstancesInputRequestTypeDef",
     {
         "deploymentId": str,
     },
 )
 _OptionalListDeploymentInstancesInputRequestTypeDef = TypedDict(
@@ -722,41 +859,104 @@
 
 class ListDeploymentInstancesInputRequestTypeDef(
     _RequiredListDeploymentInstancesInputRequestTypeDef,
     _OptionalListDeploymentInstancesInputRequestTypeDef,
 ):
     pass
 
+ListDeploymentInstancesOutputTypeDef = TypedDict(
+    "ListDeploymentInstancesOutputTypeDef",
+    {
+        "instancesList": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListDeploymentTargetsInputListDeploymentTargetsPaginateTypeDef = TypedDict(
+    "ListDeploymentTargetsInputListDeploymentTargetsPaginateTypeDef",
+    {
+        "deploymentId": str,
+        "targetFilters": Mapping[TargetFilterNameType, Sequence[str]],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDeploymentTargetsInputRequestTypeDef = TypedDict(
     "ListDeploymentTargetsInputRequestTypeDef",
     {
         "deploymentId": str,
         "nextToken": str,
         "targetFilters": Mapping[TargetFilterNameType, Sequence[str]],
     },
     total=False,
 )
 
+ListDeploymentTargetsOutputTypeDef = TypedDict(
+    "ListDeploymentTargetsOutputTypeDef",
+    {
+        "targetIds": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TimeRangeTypeDef = TypedDict(
     "TimeRangeTypeDef",
     {
         "start": Union[datetime, str],
         "end": Union[datetime, str],
     },
     total=False,
 )
 
+ListDeploymentsOutputTypeDef = TypedDict(
+    "ListDeploymentsOutputTypeDef",
+    {
+        "deployments": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListGitHubAccountTokenNamesInputListGitHubAccountTokenNamesPaginateTypeDef = TypedDict(
+    "ListGitHubAccountTokenNamesInputListGitHubAccountTokenNamesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListGitHubAccountTokenNamesInputRequestTypeDef = TypedDict(
     "ListGitHubAccountTokenNamesInputRequestTypeDef",
     {
         "nextToken": str,
     },
     total=False,
 )
 
+ListGitHubAccountTokenNamesOutputTypeDef = TypedDict(
+    "ListGitHubAccountTokenNamesOutputTypeDef",
+    {
+        "tokenNameList": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListOnPremisesInstancesOutputTypeDef = TypedDict(
+    "ListOnPremisesInstancesOutputTypeDef",
+    {
+        "instanceNames": List[str],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredListTagsForResourceInputRequestTypeDef = TypedDict(
     "_RequiredListTagsForResourceInputRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 _OptionalListTagsForResourceInputRequestTypeDef = TypedDict(
@@ -768,24 +968,42 @@
 )
 
 class ListTagsForResourceInputRequestTypeDef(
     _RequiredListTagsForResourceInputRequestTypeDef, _OptionalListTagsForResourceInputRequestTypeDef
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
 PutLifecycleEventHookExecutionStatusInputRequestTypeDef = TypedDict(
     "PutLifecycleEventHookExecutionStatusInputRequestTypeDef",
     {
         "deploymentId": str,
         "lifecycleEventHookExecutionId": str,
         "status": LifecycleEventStatusType,
     },
     total=False,
 )
 
+PutLifecycleEventHookExecutionStatusOutputTypeDef = TypedDict(
+    "PutLifecycleEventHookExecutionStatusOutputTypeDef",
+    {
+        "lifecycleEventHookExecutionId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RawStringTypeDef = TypedDict(
     "RawStringTypeDef",
     {
         "content": str,
         "sha256": str,
     },
     total=False,
@@ -808,14 +1026,25 @@
 
 class RegisterOnPremisesInstanceInputRequestTypeDef(
     _RequiredRegisterOnPremisesInstanceInputRequestTypeDef,
     _OptionalRegisterOnPremisesInstanceInputRequestTypeDef,
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
 S3LocationTypeDef = TypedDict(
     "S3LocationTypeDef",
     {
         "bucket": str,
         "key": str,
         "bundleType": BundleTypeType,
         "version": str,
@@ -847,14 +1076,23 @@
 )
 
 class StopDeploymentInputRequestTypeDef(
     _RequiredStopDeploymentInputRequestTypeDef, _OptionalStopDeploymentInputRequestTypeDef
 ):
     pass
 
+StopDeploymentOutputTypeDef = TypedDict(
+    "StopDeploymentOutputTypeDef",
+    {
+        "status": StopStatusType,
+        "statusMessage": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TrafficRouteTypeDef = TypedDict(
     "TrafficRouteTypeDef",
     {
         "listenerArns": List[str],
     },
     total=False,
 )
@@ -932,14 +1170,23 @@
         "registerTime": datetime,
         "deregisterTime": datetime,
         "tags": List[TagTypeDef],
     },
     total=False,
 )
 
+ListTagsForResourceOutputTypeDef = TypedDict(
+    "ListTagsForResourceOutputTypeDef",
+    {
+        "Tags": List[TagTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 RemoveTagsFromOnPremisesInstancesInputRequestTypeDef = TypedDict(
     "RemoveTagsFromOnPremisesInstancesInputRequestTypeDef",
     {
         "tags": Sequence[TagTypeDef],
         "instanceNames": Sequence[str],
     },
 )
@@ -962,185 +1209,39 @@
     total=False,
 )
 
 BatchGetApplicationsOutputTypeDef = TypedDict(
     "BatchGetApplicationsOutputTypeDef",
     {
         "applicationsInfo": List[ApplicationInfoTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateApplicationOutputTypeDef = TypedDict(
-    "CreateApplicationOutputTypeDef",
-    {
-        "applicationId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDeploymentConfigOutputTypeDef = TypedDict(
-    "CreateDeploymentConfigOutputTypeDef",
-    {
-        "deploymentConfigId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDeploymentGroupOutputTypeDef = TypedDict(
-    "CreateDeploymentGroupOutputTypeDef",
-    {
-        "deploymentGroupId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateDeploymentOutputTypeDef = TypedDict(
-    "CreateDeploymentOutputTypeDef",
-    {
-        "deploymentId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteDeploymentGroupOutputTypeDef = TypedDict(
-    "DeleteDeploymentGroupOutputTypeDef",
-    {
-        "hooksNotCleanedUp": List[AutoScalingGroupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteGitHubAccountTokenOutputTypeDef = TypedDict(
-    "DeleteGitHubAccountTokenOutputTypeDef",
-    {
-        "tokenName": str,
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
 
 GetApplicationOutputTypeDef = TypedDict(
     "GetApplicationOutputTypeDef",
     {
         "application": ApplicationInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListApplicationsOutputTypeDef = TypedDict(
-    "ListApplicationsOutputTypeDef",
-    {
-        "applications": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDeploymentConfigsOutputTypeDef = TypedDict(
-    "ListDeploymentConfigsOutputTypeDef",
-    {
-        "deploymentConfigsList": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDeploymentGroupsOutputTypeDef = TypedDict(
-    "ListDeploymentGroupsOutputTypeDef",
-    {
-        "applicationName": str,
-        "deploymentGroups": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-ListDeploymentInstancesOutputTypeDef = TypedDict(
-    "ListDeploymentInstancesOutputTypeDef",
-    {
-        "instancesList": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDeploymentTargetsOutputTypeDef = TypedDict(
-    "ListDeploymentTargetsOutputTypeDef",
-    {
-        "targetIds": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDeploymentsOutputTypeDef = TypedDict(
-    "ListDeploymentsOutputTypeDef",
-    {
-        "deployments": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListGitHubAccountTokenNamesOutputTypeDef = TypedDict(
-    "ListGitHubAccountTokenNamesOutputTypeDef",
-    {
-        "tokenNameList": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListOnPremisesInstancesOutputTypeDef = TypedDict(
-    "ListOnPremisesInstancesOutputTypeDef",
-    {
-        "instanceNames": List[str],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceOutputTypeDef = TypedDict(
-    "ListTagsForResourceOutputTypeDef",
-    {
-        "Tags": List[TagTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PutLifecycleEventHookExecutionStatusOutputTypeDef = TypedDict(
-    "PutLifecycleEventHookExecutionStatusOutputTypeDef",
-    {
-        "lifecycleEventHookExecutionId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-StopDeploymentOutputTypeDef = TypedDict(
-    "StopDeploymentOutputTypeDef",
+DeleteDeploymentGroupOutputTypeDef = TypedDict(
+    "DeleteDeploymentGroupOutputTypeDef",
     {
-        "status": StopStatusType,
-        "statusMessage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "hooksNotCleanedUp": List[AutoScalingGroupTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDeploymentGroupOutputTypeDef = TypedDict(
     "UpdateDeploymentGroupOutputTypeDef",
     {
         "hooksNotCleanedUp": List[AutoScalingGroupTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BlueGreenDeploymentConfigurationTypeDef = TypedDict(
     "BlueGreenDeploymentConfigurationTypeDef",
     {
         "terminateBlueInstancesOnDeploymentSuccess": BlueInstanceTerminationOptionTypeDef,
@@ -1154,14 +1255,24 @@
     "EC2TagSetTypeDef",
     {
         "ec2TagSetList": List[List[EC2TagFilterTypeDef]],
     },
     total=False,
 )
 
+ListOnPremisesInstancesInputListOnPremisesInstancesPaginateTypeDef = TypedDict(
+    "ListOnPremisesInstancesInputListOnPremisesInstancesPaginateTypeDef",
+    {
+        "registrationStatus": RegistrationStatusType,
+        "tagFilters": Sequence[TagFilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListOnPremisesInstancesInputRequestTypeDef = TypedDict(
     "ListOnPremisesInstancesInputRequestTypeDef",
     {
         "registrationStatus": RegistrationStatusType,
         "tagFilters": Sequence[TagFilterTypeDef],
         "nextToken": str,
     },
@@ -1219,134 +1330,23 @@
 
 class GetDeploymentInputDeploymentSuccessfulWaitTypeDef(
     _RequiredGetDeploymentInputDeploymentSuccessfulWaitTypeDef,
     _OptionalGetDeploymentInputDeploymentSuccessfulWaitTypeDef,
 ):
     pass
 
-_RequiredListApplicationRevisionsInputListApplicationRevisionsPaginateTypeDef = TypedDict(
-    "_RequiredListApplicationRevisionsInputListApplicationRevisionsPaginateTypeDef",
-    {
-        "applicationName": str,
-    },
-)
-_OptionalListApplicationRevisionsInputListApplicationRevisionsPaginateTypeDef = TypedDict(
-    "_OptionalListApplicationRevisionsInputListApplicationRevisionsPaginateTypeDef",
-    {
-        "sortBy": ApplicationRevisionSortByType,
-        "sortOrder": SortOrderType,
-        "s3Bucket": str,
-        "s3KeyPrefix": str,
-        "deployed": ListStateFilterActionType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListApplicationRevisionsInputListApplicationRevisionsPaginateTypeDef(
-    _RequiredListApplicationRevisionsInputListApplicationRevisionsPaginateTypeDef,
-    _OptionalListApplicationRevisionsInputListApplicationRevisionsPaginateTypeDef,
-):
-    pass
-
-ListApplicationsInputListApplicationsPaginateTypeDef = TypedDict(
-    "ListApplicationsInputListApplicationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListDeploymentConfigsInputListDeploymentConfigsPaginateTypeDef = TypedDict(
-    "ListDeploymentConfigsInputListDeploymentConfigsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListDeploymentGroupsInputListDeploymentGroupsPaginateTypeDef = TypedDict(
-    "_RequiredListDeploymentGroupsInputListDeploymentGroupsPaginateTypeDef",
-    {
-        "applicationName": str,
-    },
-)
-_OptionalListDeploymentGroupsInputListDeploymentGroupsPaginateTypeDef = TypedDict(
-    "_OptionalListDeploymentGroupsInputListDeploymentGroupsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListDeploymentGroupsInputListDeploymentGroupsPaginateTypeDef(
-    _RequiredListDeploymentGroupsInputListDeploymentGroupsPaginateTypeDef,
-    _OptionalListDeploymentGroupsInputListDeploymentGroupsPaginateTypeDef,
-):
-    pass
-
-_RequiredListDeploymentInstancesInputListDeploymentInstancesPaginateTypeDef = TypedDict(
-    "_RequiredListDeploymentInstancesInputListDeploymentInstancesPaginateTypeDef",
-    {
-        "deploymentId": str,
-    },
-)
-_OptionalListDeploymentInstancesInputListDeploymentInstancesPaginateTypeDef = TypedDict(
-    "_OptionalListDeploymentInstancesInputListDeploymentInstancesPaginateTypeDef",
-    {
-        "instanceStatusFilter": Sequence[InstanceStatusType],
-        "instanceTypeFilter": Sequence[InstanceTypeType],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListDeploymentInstancesInputListDeploymentInstancesPaginateTypeDef(
-    _RequiredListDeploymentInstancesInputListDeploymentInstancesPaginateTypeDef,
-    _OptionalListDeploymentInstancesInputListDeploymentInstancesPaginateTypeDef,
-):
-    pass
-
-ListDeploymentTargetsInputListDeploymentTargetsPaginateTypeDef = TypedDict(
-    "ListDeploymentTargetsInputListDeploymentTargetsPaginateTypeDef",
-    {
-        "deploymentId": str,
-        "targetFilters": Mapping[TargetFilterNameType, Sequence[str]],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListGitHubAccountTokenNamesInputListGitHubAccountTokenNamesPaginateTypeDef = TypedDict(
-    "ListGitHubAccountTokenNamesInputListGitHubAccountTokenNamesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListOnPremisesInstancesInputListOnPremisesInstancesPaginateTypeDef = TypedDict(
-    "ListOnPremisesInstancesInputListOnPremisesInstancesPaginateTypeDef",
-    {
-        "registrationStatus": RegistrationStatusType,
-        "tagFilters": Sequence[TagFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListDeploymentsInputListDeploymentsPaginateTypeDef = TypedDict(
     "ListDeploymentsInputListDeploymentsPaginateTypeDef",
     {
         "applicationName": str,
         "deploymentGroupName": str,
         "externalId": str,
         "includeOnlyStatuses": Sequence[DeploymentStatusType],
         "createTimeRange": TimeRangeTypeDef,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListDeploymentsInputRequestTypeDef = TypedDict(
     "ListDeploymentsInputRequestTypeDef",
     {
@@ -1392,23 +1392,23 @@
     total=False,
 )
 
 BatchGetOnPremisesInstancesOutputTypeDef = TypedDict(
     "BatchGetOnPremisesInstancesOutputTypeDef",
     {
         "instanceInfos": List[InstanceInfoTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetOnPremisesInstanceOutputTypeDef = TypedDict(
     "GetOnPremisesInstanceOutputTypeDef",
     {
         "instanceInfo": InstanceInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 TargetInstancesTypeDef = TypedDict(
     "TargetInstancesTypeDef",
     {
         "tagFilters": List[EC2TagFilterTypeDef],
@@ -1505,24 +1505,24 @@
 
 GetApplicationRevisionOutputTypeDef = TypedDict(
     "GetApplicationRevisionOutputTypeDef",
     {
         "applicationName": str,
         "revision": RevisionLocationTypeDef,
         "revisionInfo": GenericRevisionInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListApplicationRevisionsOutputTypeDef = TypedDict(
     "ListApplicationRevisionsOutputTypeDef",
     {
         "revisions": List[RevisionLocationTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredRegisterApplicationRevisionInputRequestTypeDef = TypedDict(
     "_RequiredRegisterApplicationRevisionInputRequestTypeDef",
     {
         "applicationName": str,
@@ -1626,23 +1626,23 @@
     pass
 
 BatchGetDeploymentInstancesOutputTypeDef = TypedDict(
     "BatchGetDeploymentInstancesOutputTypeDef",
     {
         "instancesSummary": List[InstanceSummaryTypeDef],
         "errorMessage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDeploymentInstanceOutputTypeDef = TypedDict(
     "GetDeploymentInstanceOutputTypeDef",
     {
         "instanceSummary": InstanceSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeploymentTargetTypeDef = TypedDict(
     "DeploymentTargetTypeDef",
     {
         "deploymentTargetType": DeploymentTargetTypeType,
@@ -1656,15 +1656,15 @@
 
 BatchGetApplicationRevisionsOutputTypeDef = TypedDict(
     "BatchGetApplicationRevisionsOutputTypeDef",
     {
         "applicationName": str,
         "errorMessage": str,
         "revisions": List[RevisionInfoTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateDeploymentGroupInputRequestTypeDef = TypedDict(
     "_RequiredCreateDeploymentGroupInputRequestTypeDef",
     {
         "applicationName": str,
@@ -1802,59 +1802,59 @@
 ):
     pass
 
 GetDeploymentConfigOutputTypeDef = TypedDict(
     "GetDeploymentConfigOutputTypeDef",
     {
         "deploymentConfigInfo": DeploymentConfigInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetDeploymentTargetsOutputTypeDef = TypedDict(
     "BatchGetDeploymentTargetsOutputTypeDef",
     {
         "deploymentTargets": List[DeploymentTargetTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDeploymentTargetOutputTypeDef = TypedDict(
     "GetDeploymentTargetOutputTypeDef",
     {
         "deploymentTarget": DeploymentTargetTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetDeploymentGroupsOutputTypeDef = TypedDict(
     "BatchGetDeploymentGroupsOutputTypeDef",
     {
         "deploymentGroupsInfo": List[DeploymentGroupInfoTypeDef],
         "errorMessage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDeploymentGroupOutputTypeDef = TypedDict(
     "GetDeploymentGroupOutputTypeDef",
     {
         "deploymentGroupInfo": DeploymentGroupInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 BatchGetDeploymentsOutputTypeDef = TypedDict(
     "BatchGetDeploymentsOutputTypeDef",
     {
         "deploymentsInfo": List[DeploymentInfoTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDeploymentOutputTypeDef = TypedDict(
     "GetDeploymentOutputTypeDef",
     {
         "deploymentInfo": DeploymentInfoTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-codedeploy-2.5.0.post1/types_aiobotocore_codedeploy/waiter.py` & `types-aiobotocore-codedeploy-2.5.1/types_aiobotocore_codedeploy/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-codedeploy-2.5.0.post1/types_aiobotocore_codedeploy/waiter.pyi` & `types-aiobotocore-codedeploy-2.5.1/types_aiobotocore_codedeploy/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-codedeploy-2.5.0.post1/types_aiobotocore_codedeploy.egg-info/PKG-INFO` & `types-aiobotocore-codedeploy-2.5.1/types_aiobotocore_codedeploy.egg-info/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-codedeploy
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.CodeDeploy 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.CodeDeploy 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-codedeploy"></a>
 
 # types-aiobotocore-codedeploy
 
 [![PyPI - types-aiobotocore-codedeploy](https://img.shields.io/pypi/v/types-aiobotocore-codedeploy.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codedeploy)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-codedeploy.svg?color=blue)](https://pypi.org/project/types-aiobotocore-codedeploy)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-codedeploy?color=blue)](https://pypistats.org/packages/types-aiobotocore-codedeploy)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.CodeDeploy 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codedeploy.html#CodeDeploy)
+[aiobotocore.CodeDeploy 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/codedeploy.html#CodeDeploy)
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
 [types-aiobotocore-codedeploy docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/).
 
 See how it helps to find and fix potential bugs:
 
@@ -422,119 +422,119 @@
 from types_aiobotocore_codedeploy.type_defs import (
     TagTypeDef,
     AlarmTypeDef,
     AppSpecContentTypeDef,
     ApplicationInfoTypeDef,
     AutoRollbackConfigurationTypeDef,
     AutoScalingGroupTypeDef,
-    ResponseMetadataTypeDef,
     BatchGetApplicationsInputRequestTypeDef,
     BatchGetDeploymentGroupsInputRequestTypeDef,
     BatchGetDeploymentInstancesInputRequestTypeDef,
     BatchGetDeploymentTargetsInputRequestTypeDef,
     BatchGetDeploymentsInputRequestTypeDef,
     BatchGetOnPremisesInstancesInputRequestTypeDef,
     BlueInstanceTerminationOptionTypeDef,
     DeploymentReadyOptionTypeDef,
     GreenFleetProvisioningOptionTypeDef,
     ContinueDeploymentInputRequestTypeDef,
+    CreateApplicationOutputTypeDef,
     MinimumHealthyHostsTypeDef,
+    CreateDeploymentConfigOutputTypeDef,
     DeploymentStyleTypeDef,
     EC2TagFilterTypeDef,
     ECSServiceTypeDef,
     TagFilterTypeDef,
     TriggerConfigTypeDef,
+    CreateDeploymentGroupOutputTypeDef,
+    CreateDeploymentOutputTypeDef,
     DeleteApplicationInputRequestTypeDef,
     DeleteDeploymentConfigInputRequestTypeDef,
     DeleteDeploymentGroupInputRequestTypeDef,
     DeleteGitHubAccountTokenInputRequestTypeDef,
+    DeleteGitHubAccountTokenOutputTypeDef,
     DeleteResourcesByExternalIdInputRequestTypeDef,
     LastDeploymentInfoTypeDef,
     DeploymentOverviewTypeDef,
     ErrorInformationTypeDef,
     RelatedDeploymentsTypeDef,
     RollbackInfoTypeDef,
     DeregisterOnPremisesInstanceInputRequestTypeDef,
     DiagnosticsTypeDef,
     TargetGroupInfoTypeDef,
     ELBInfoTypeDef,
+    EmptyResponseMetadataTypeDef,
     GenericRevisionInfoTypeDef,
     GetApplicationInputRequestTypeDef,
     GetDeploymentConfigInputRequestTypeDef,
     GetDeploymentGroupInputRequestTypeDef,
     WaiterConfigTypeDef,
     GetDeploymentInputRequestTypeDef,
     GetDeploymentInstanceInputRequestTypeDef,
     GetDeploymentTargetInputRequestTypeDef,
     GetOnPremisesInstanceInputRequestTypeDef,
     GitHubLocationTypeDef,
     LambdaFunctionInfoTypeDef,
-    PaginatorConfigTypeDef,
+    ListApplicationRevisionsInputListApplicationRevisionsPaginateTypeDef,
     ListApplicationRevisionsInputRequestTypeDef,
+    ListApplicationsInputListApplicationsPaginateTypeDef,
     ListApplicationsInputRequestTypeDef,
+    ListApplicationsOutputTypeDef,
+    ListDeploymentConfigsInputListDeploymentConfigsPaginateTypeDef,
     ListDeploymentConfigsInputRequestTypeDef,
+    ListDeploymentConfigsOutputTypeDef,
+    ListDeploymentGroupsInputListDeploymentGroupsPaginateTypeDef,
     ListDeploymentGroupsInputRequestTypeDef,
+    ListDeploymentGroupsOutputTypeDef,
+    ListDeploymentInstancesInputListDeploymentInstancesPaginateTypeDef,
     ListDeploymentInstancesInputRequestTypeDef,
+    ListDeploymentInstancesOutputTypeDef,
+    ListDeploymentTargetsInputListDeploymentTargetsPaginateTypeDef,
     ListDeploymentTargetsInputRequestTypeDef,
+    ListDeploymentTargetsOutputTypeDef,
     TimeRangeTypeDef,
+    ListDeploymentsOutputTypeDef,
+    ListGitHubAccountTokenNamesInputListGitHubAccountTokenNamesPaginateTypeDef,
     ListGitHubAccountTokenNamesInputRequestTypeDef,
+    ListGitHubAccountTokenNamesOutputTypeDef,
+    ListOnPremisesInstancesOutputTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    PaginatorConfigTypeDef,
     PutLifecycleEventHookExecutionStatusInputRequestTypeDef,
+    PutLifecycleEventHookExecutionStatusOutputTypeDef,
     RawStringTypeDef,
     RegisterOnPremisesInstanceInputRequestTypeDef,
+    ResponseMetadataTypeDef,
     S3LocationTypeDef,
     SkipWaitTimeForInstanceTerminationInputRequestTypeDef,
     StopDeploymentInputRequestTypeDef,
+    StopDeploymentOutputTypeDef,
     TrafficRouteTypeDef,
     TimeBasedCanaryTypeDef,
     TimeBasedLinearTypeDef,
     UntagResourceInputRequestTypeDef,
     UpdateApplicationInputRequestTypeDef,
     AddTagsToOnPremisesInstancesInputRequestTypeDef,
     CreateApplicationInputRequestTypeDef,
     InstanceInfoTypeDef,
+    ListTagsForResourceOutputTypeDef,
     RemoveTagsFromOnPremisesInstancesInputRequestTypeDef,
     TagResourceInputRequestTypeDef,
     AlarmConfigurationTypeDef,
     BatchGetApplicationsOutputTypeDef,
-    CreateApplicationOutputTypeDef,
-    CreateDeploymentConfigOutputTypeDef,
-    CreateDeploymentGroupOutputTypeDef,
-    CreateDeploymentOutputTypeDef,
-    DeleteDeploymentGroupOutputTypeDef,
-    DeleteGitHubAccountTokenOutputTypeDef,
-    EmptyResponseMetadataTypeDef,
     GetApplicationOutputTypeDef,
-    ListApplicationsOutputTypeDef,
-    ListDeploymentConfigsOutputTypeDef,
-    ListDeploymentGroupsOutputTypeDef,
-    ListDeploymentInstancesOutputTypeDef,
-    ListDeploymentTargetsOutputTypeDef,
-    ListDeploymentsOutputTypeDef,
-    ListGitHubAccountTokenNamesOutputTypeDef,
-    ListOnPremisesInstancesOutputTypeDef,
-    ListTagsForResourceOutputTypeDef,
-    PutLifecycleEventHookExecutionStatusOutputTypeDef,
-    StopDeploymentOutputTypeDef,
+    DeleteDeploymentGroupOutputTypeDef,
     UpdateDeploymentGroupOutputTypeDef,
     BlueGreenDeploymentConfigurationTypeDef,
     EC2TagSetTypeDef,
+    ListOnPremisesInstancesInputListOnPremisesInstancesPaginateTypeDef,
     ListOnPremisesInstancesInputRequestTypeDef,
     OnPremisesTagSetTypeDef,
     LifecycleEventTypeDef,
     ECSTaskSetTypeDef,
     GetDeploymentInputDeploymentSuccessfulWaitTypeDef,
-    ListApplicationRevisionsInputListApplicationRevisionsPaginateTypeDef,
-    ListApplicationsInputListApplicationsPaginateTypeDef,
-    ListDeploymentConfigsInputListDeploymentConfigsPaginateTypeDef,
-    ListDeploymentGroupsInputListDeploymentGroupsPaginateTypeDef,
-    ListDeploymentInstancesInputListDeploymentInstancesPaginateTypeDef,
-    ListDeploymentTargetsInputListDeploymentTargetsPaginateTypeDef,
-    ListGitHubAccountTokenNamesInputListGitHubAccountTokenNamesPaginateTypeDef,
-    ListOnPremisesInstancesInputListOnPremisesInstancesPaginateTypeDef,
     ListDeploymentsInputListDeploymentsPaginateTypeDef,
     ListDeploymentsInputRequestTypeDef,
     RevisionLocationTypeDef,
     TargetGroupPairInfoTypeDef,
     TrafficRoutingConfigTypeDef,
     BatchGetOnPremisesInstancesOutputTypeDef,
     GetOnPremisesInstanceOutputTypeDef,
@@ -579,43 +579,43 @@
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

### Comparing `types-aiobotocore-codedeploy-2.5.0.post1/types_aiobotocore_codedeploy.egg-info/SOURCES.txt` & `types-aiobotocore-codedeploy-2.5.1/types_aiobotocore_codedeploy.egg-info/SOURCES.txt`

 * *Files identical despite different names*

