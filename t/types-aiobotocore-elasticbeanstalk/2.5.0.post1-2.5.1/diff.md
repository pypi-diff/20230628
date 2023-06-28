# Comparing `tmp/types-aiobotocore-elasticbeanstalk-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-elasticbeanstalk-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-elasticbeanstalk-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:34 2023, max compression
+gzip compressed data, was "types-aiobotocore-elasticbeanstalk-2.5.1.tar", last modified: Wed Jun 28 01:43:27 2023, max compression
```

## Comparing `types-aiobotocore-elasticbeanstalk-2.5.0.post1.tar` & `types-aiobotocore-elasticbeanstalk-2.5.1.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:34.795176 types-aiobotocore-elasticbeanstalk-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:14:06.000000 types-aiobotocore-elasticbeanstalk-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    21918 2023-03-11 12:26:34.795176 types-aiobotocore-elasticbeanstalk-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    20311 2023-03-11 12:14:06.000000 types-aiobotocore-elasticbeanstalk-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:34.795176 types-aiobotocore-elasticbeanstalk-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2187 2023-03-11 12:14:05.000000 types-aiobotocore-elasticbeanstalk-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:34.795176 types-aiobotocore-elasticbeanstalk-2.5.0.post1/types_aiobotocore_elasticbeanstalk/
--rw-r--r--   0 runner    (1001) docker     (123)     2421 2023-03-11 12:14:06.000000 types-aiobotocore-elasticbeanstalk-2.5.0.post1/types_aiobotocore_elasticbeanstalk/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2420 2023-03-11 12:14:06.000000 types-aiobotocore-elasticbeanstalk-2.5.0.post1/types_aiobotocore_elasticbeanstalk/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      979 2023-03-11 12:14:06.000000 types-aiobotocore-elasticbeanstalk-2.5.0.post1/types_aiobotocore_elasticbeanstalk/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    45094 2023-03-11 12:14:07.000000 types-aiobotocore-elasticbeanstalk-2.5.0.post1/types_aiobotocore_elasticbeanstalk/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    45030 2023-03-11 12:14:07.000000 types-aiobotocore-elasticbeanstalk-2.5.0.post1/types_aiobotocore_elasticbeanstalk/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    11569 2023-03-11 12:14:07.000000 types-aiobotocore-elasticbeanstalk-2.5.0.post1/types_aiobotocore_elasticbeanstalk/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    11567 2023-03-11 12:14:07.000000 types-aiobotocore-elasticbeanstalk-2.5.0.post1/types_aiobotocore_elasticbeanstalk/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8322 2023-03-11 12:14:07.000000 types-aiobotocore-elasticbeanstalk-2.5.0.post1/types_aiobotocore_elasticbeanstalk/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     8314 2023-03-11 12:14:07.000000 types-aiobotocore-elasticbeanstalk-2.5.0.post1/types_aiobotocore_elasticbeanstalk/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:14:06.000000 types-aiobotocore-elasticbeanstalk-2.5.0.post1/types_aiobotocore_elasticbeanstalk/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    52808 2023-03-11 12:14:08.000000 types-aiobotocore-elasticbeanstalk-2.5.0.post1/types_aiobotocore_elasticbeanstalk/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    52769 2023-03-11 12:14:08.000000 types-aiobotocore-elasticbeanstalk-2.5.0.post1/types_aiobotocore_elasticbeanstalk/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:14:06.000000 types-aiobotocore-elasticbeanstalk-2.5.0.post1/types_aiobotocore_elasticbeanstalk/version.py
--rw-r--r--   0 runner    (1001) docker     (123)     4808 2023-03-11 12:14:07.000000 types-aiobotocore-elasticbeanstalk-2.5.0.post1/types_aiobotocore_elasticbeanstalk/waiter.py
--rw-r--r--   0 runner    (1001) docker     (123)     4805 2023-03-11 12:14:07.000000 types-aiobotocore-elasticbeanstalk-2.5.0.post1/types_aiobotocore_elasticbeanstalk/waiter.pyi
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:34.795176 types-aiobotocore-elasticbeanstalk-2.5.0.post1/types_aiobotocore_elasticbeanstalk.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    21918 2023-03-11 12:26:34.000000 types-aiobotocore-elasticbeanstalk-2.5.0.post1/types_aiobotocore_elasticbeanstalk.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1075 2023-03-11 12:26:34.000000 types-aiobotocore-elasticbeanstalk-2.5.0.post1/types_aiobotocore_elasticbeanstalk.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:34.000000 types-aiobotocore-elasticbeanstalk-2.5.0.post1/types_aiobotocore_elasticbeanstalk.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:34.000000 types-aiobotocore-elasticbeanstalk-2.5.0.post1/types_aiobotocore_elasticbeanstalk.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:34.000000 types-aiobotocore-elasticbeanstalk-2.5.0.post1/types_aiobotocore_elasticbeanstalk.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       35 2023-03-11 12:26:34.000000 types-aiobotocore-elasticbeanstalk-2.5.0.post1/types_aiobotocore_elasticbeanstalk.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:27.098132 types-aiobotocore-elasticbeanstalk-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:30:42.000000 types-aiobotocore-elasticbeanstalk-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    21919 2023-06-28 01:43:27.090132 types-aiobotocore-elasticbeanstalk-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    20318 2023-06-28 01:30:42.000000 types-aiobotocore-elasticbeanstalk-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:27.098132 types-aiobotocore-elasticbeanstalk-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2181 2023-06-28 01:30:42.000000 types-aiobotocore-elasticbeanstalk-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:27.090132 types-aiobotocore-elasticbeanstalk-2.5.1/types_aiobotocore_elasticbeanstalk/
+-rw-r--r--   0 runner    (1001) docker     (123)     2421 2023-06-28 01:30:42.000000 types-aiobotocore-elasticbeanstalk-2.5.1/types_aiobotocore_elasticbeanstalk/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2420 2023-06-28 01:30:42.000000 types-aiobotocore-elasticbeanstalk-2.5.1/types_aiobotocore_elasticbeanstalk/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      967 2023-06-28 01:30:42.000000 types-aiobotocore-elasticbeanstalk-2.5.1/types_aiobotocore_elasticbeanstalk/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    45094 2023-06-28 01:30:43.000000 types-aiobotocore-elasticbeanstalk-2.5.1/types_aiobotocore_elasticbeanstalk/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    45030 2023-06-28 01:30:43.000000 types-aiobotocore-elasticbeanstalk-2.5.1/types_aiobotocore_elasticbeanstalk/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    11778 2023-06-28 01:30:43.000000 types-aiobotocore-elasticbeanstalk-2.5.1/types_aiobotocore_elasticbeanstalk/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11776 2023-06-28 01:30:43.000000 types-aiobotocore-elasticbeanstalk-2.5.1/types_aiobotocore_elasticbeanstalk/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8212 2023-06-28 01:30:43.000000 types-aiobotocore-elasticbeanstalk-2.5.1/types_aiobotocore_elasticbeanstalk/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8205 2023-06-28 01:30:43.000000 types-aiobotocore-elasticbeanstalk-2.5.1/types_aiobotocore_elasticbeanstalk/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:30:42.000000 types-aiobotocore-elasticbeanstalk-2.5.1/types_aiobotocore_elasticbeanstalk/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    52878 2023-06-28 01:30:44.000000 types-aiobotocore-elasticbeanstalk-2.5.1/types_aiobotocore_elasticbeanstalk/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    52839 2023-06-28 01:30:44.000000 types-aiobotocore-elasticbeanstalk-2.5.1/types_aiobotocore_elasticbeanstalk/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:30:42.000000 types-aiobotocore-elasticbeanstalk-2.5.1/types_aiobotocore_elasticbeanstalk/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4808 2023-06-28 01:30:43.000000 types-aiobotocore-elasticbeanstalk-2.5.1/types_aiobotocore_elasticbeanstalk/waiter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4805 2023-06-28 01:30:43.000000 types-aiobotocore-elasticbeanstalk-2.5.1/types_aiobotocore_elasticbeanstalk/waiter.pyi
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:27.090132 types-aiobotocore-elasticbeanstalk-2.5.1/types_aiobotocore_elasticbeanstalk.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    21919 2023-06-28 01:43:26.000000 types-aiobotocore-elasticbeanstalk-2.5.1/types_aiobotocore_elasticbeanstalk.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1075 2023-06-28 01:43:26.000000 types-aiobotocore-elasticbeanstalk-2.5.1/types_aiobotocore_elasticbeanstalk.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:26.000000 types-aiobotocore-elasticbeanstalk-2.5.1/types_aiobotocore_elasticbeanstalk.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:26.000000 types-aiobotocore-elasticbeanstalk-2.5.1/types_aiobotocore_elasticbeanstalk.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:26.000000 types-aiobotocore-elasticbeanstalk-2.5.1/types_aiobotocore_elasticbeanstalk.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       35 2023-06-28 01:43:26.000000 types-aiobotocore-elasticbeanstalk-2.5.1/types_aiobotocore_elasticbeanstalk.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-elasticbeanstalk-2.5.0.post1/LICENSE` & `types-aiobotocore-elasticbeanstalk-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-elasticbeanstalk-2.5.0.post1/PKG-INFO` & `types-aiobotocore-elasticbeanstalk-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-elasticbeanstalk
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ElasticBeanstalk 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ElasticBeanstalk 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticbeanstalk/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-elasticbeanstalk"></a>
 
 # types-aiobotocore-elasticbeanstalk
 
 [![PyPI - types-aiobotocore-elasticbeanstalk](https://img.shields.io/pypi/v/types-aiobotocore-elasticbeanstalk.svg?color=blue)](https://pypi.org/project/types-aiobotocore-elasticbeanstalk)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-elasticbeanstalk.svg?color=blue)](https://pypi.org/project/types-aiobotocore-elasticbeanstalk)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticbeanstalk/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-elasticbeanstalk?color=blue)](https://pypistats.org/packages/types-aiobotocore-elasticbeanstalk)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ElasticBeanstalk 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk)
+[aiobotocore.ElasticBeanstalk 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk)
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
 [types-aiobotocore-elasticbeanstalk docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticbeanstalk/).
 
 See how it helps to find and fix potential bugs:
 
@@ -391,61 +391,67 @@
 
 `types_aiobotocore_elasticbeanstalk.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_elasticbeanstalk.type_defs import (
     AbortEnvironmentUpdateMessageRequestTypeDef,
-    ResponseMetadataTypeDef,
     LatencyTypeDef,
     StatusCodesTypeDef,
     S3LocationTypeDef,
     SourceBuildInformationTypeDef,
     MaxAgeRuleTypeDef,
     MaxCountRuleTypeDef,
     ApplyEnvironmentManagedActionRequestRequestTypeDef,
+    ApplyEnvironmentManagedActionResultTypeDef,
     AssociateEnvironmentOperationsRoleMessageRequestTypeDef,
     AutoScalingGroupTypeDef,
     BuildConfigurationTypeDef,
     BuilderTypeDef,
     CPUUtilizationTypeDef,
     CheckDNSAvailabilityMessageRequestTypeDef,
+    CheckDNSAvailabilityResultMessageTypeDef,
     ComposeEnvironmentsMessageRequestTypeDef,
     OptionRestrictionRegexTypeDef,
     ConfigurationOptionSettingTypeDef,
     ValidationMessageTypeDef,
     TagTypeDef,
     SourceConfigurationTypeDef,
     EnvironmentTierTypeDef,
     OptionSpecificationTypeDef,
     PlatformSummaryTypeDef,
+    CreateStorageLocationResultMessageTypeDef,
     CustomAmiTypeDef,
     DeleteApplicationMessageRequestTypeDef,
     DeleteApplicationVersionMessageRequestTypeDef,
     DeleteConfigurationTemplateMessageRequestTypeDef,
     DeleteEnvironmentConfigurationMessageRequestTypeDef,
     DeletePlatformVersionRequestRequestTypeDef,
     DeploymentTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeApplicationVersionsMessageDescribeApplicationVersionsPaginateTypeDef,
     DescribeApplicationVersionsMessageRequestTypeDef,
     DescribeApplicationsMessageRequestTypeDef,
     DescribeConfigurationSettingsMessageRequestTypeDef,
     DescribeEnvironmentHealthRequestRequestTypeDef,
     InstanceHealthSummaryTypeDef,
+    DescribeEnvironmentManagedActionHistoryRequestDescribeEnvironmentManagedActionHistoryPaginateTypeDef,
     DescribeEnvironmentManagedActionHistoryRequestRequestTypeDef,
     ManagedActionHistoryItemTypeDef,
     DescribeEnvironmentManagedActionsRequestRequestTypeDef,
     ManagedActionTypeDef,
     DescribeEnvironmentResourcesMessageRequestTypeDef,
+    DescribeEnvironmentsMessageDescribeEnvironmentsPaginateTypeDef,
     WaiterConfigTypeDef,
     DescribeEnvironmentsMessageRequestTypeDef,
+    DescribeEventsMessageDescribeEventsPaginateTypeDef,
     DescribeEventsMessageRequestTypeDef,
     DescribeInstancesHealthRequestRequestTypeDef,
     DescribePlatformVersionRequestRequestTypeDef,
     DisassociateEnvironmentOperationsRoleMessageRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EnvironmentLinkTypeDef,
     EnvironmentInfoDescriptionTypeDef,
     InstanceTypeDef,
     LaunchConfigurationTypeDef,
     LaunchTemplateTypeDef,
     LoadBalancerTypeDef,
     QueueTypeDef,
@@ -453,29 +459,27 @@
     EventDescriptionTypeDef,
     SolutionStackDescriptionTypeDef,
     SearchFilterTypeDef,
     PlatformBranchSummaryTypeDef,
     PlatformFilterTypeDef,
     ListTagsForResourceMessageRequestTypeDef,
     ListenerTypeDef,
+    PaginatorConfigTypeDef,
     PlatformFrameworkTypeDef,
     PlatformProgrammingLanguageTypeDef,
     RebuildEnvironmentMessageRequestTypeDef,
     RequestEnvironmentInfoMessageRequestTypeDef,
     ResourceQuotaTypeDef,
+    ResponseMetadataTypeDef,
     RestartAppServerMessageRequestTypeDef,
     RetrieveEnvironmentInfoMessageRequestTypeDef,
     SwapEnvironmentCNAMEsMessageRequestTypeDef,
     TerminateEnvironmentMessageRequestTypeDef,
     UpdateApplicationMessageRequestTypeDef,
     UpdateApplicationVersionMessageRequestTypeDef,
-    ApplyEnvironmentManagedActionResultTypeDef,
-    CheckDNSAvailabilityResultMessageTypeDef,
-    CreateStorageLocationResultMessageTypeDef,
-    EmptyResponseMetadataTypeDef,
     ApplicationMetricsTypeDef,
     ApplicationVersionDescriptionTypeDef,
     ApplicationVersionLifecycleConfigTypeDef,
     SystemStatusTypeDef,
     ConfigurationOptionDescriptionTypeDef,
     ConfigurationSettingsDescriptionResponseMetadataTypeDef,
     ConfigurationSettingsDescriptionTypeDef,
@@ -489,18 +493,14 @@
     CreateEnvironmentMessageRequestTypeDef,
     DescribeConfigurationOptionsMessageRequestTypeDef,
     UpdateConfigurationTemplateMessageRequestTypeDef,
     UpdateEnvironmentMessageRequestTypeDef,
     CreatePlatformVersionResultTypeDef,
     DeletePlatformVersionResultTypeDef,
     ListPlatformVersionsResultTypeDef,
-    DescribeApplicationVersionsMessageDescribeApplicationVersionsPaginateTypeDef,
-    DescribeEnvironmentManagedActionHistoryRequestDescribeEnvironmentManagedActionHistoryPaginateTypeDef,
-    DescribeEnvironmentsMessageDescribeEnvironmentsPaginateTypeDef,
-    DescribeEventsMessageDescribeEventsPaginateTypeDef,
     DescribeEnvironmentManagedActionHistoryResultTypeDef,
     DescribeEnvironmentManagedActionsResultTypeDef,
     DescribeEnvironmentsMessageEnvironmentExistsWaitTypeDef,
     DescribeEnvironmentsMessageEnvironmentTerminatedWaitTypeDef,
     DescribeEnvironmentsMessageEnvironmentUpdatedWaitTypeDef,
     RetrieveEnvironmentInfoResultMessageTypeDef,
     EnvironmentResourceDescriptionTypeDef,
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

### Comparing `types-aiobotocore-elasticbeanstalk-2.5.0.post1/README.md` & `types-aiobotocore-elasticbeanstalk-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-elasticbeanstalk"></a>
 
 # types-aiobotocore-elasticbeanstalk
 
 [![PyPI - types-aiobotocore-elasticbeanstalk](https://img.shields.io/pypi/v/types-aiobotocore-elasticbeanstalk.svg?color=blue)](https://pypi.org/project/types-aiobotocore-elasticbeanstalk)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-elasticbeanstalk.svg?color=blue)](https://pypi.org/project/types-aiobotocore-elasticbeanstalk)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticbeanstalk/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-elasticbeanstalk?color=blue)](https://pypistats.org/packages/types-aiobotocore-elasticbeanstalk)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ElasticBeanstalk 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk)
+[aiobotocore.ElasticBeanstalk 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk)
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
 [types-aiobotocore-elasticbeanstalk docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticbeanstalk/).
 
 See how it helps to find and fix potential bugs:
 
@@ -358,61 +358,67 @@
 
 `types_aiobotocore_elasticbeanstalk.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_elasticbeanstalk.type_defs import (
     AbortEnvironmentUpdateMessageRequestTypeDef,
-    ResponseMetadataTypeDef,
     LatencyTypeDef,
     StatusCodesTypeDef,
     S3LocationTypeDef,
     SourceBuildInformationTypeDef,
     MaxAgeRuleTypeDef,
     MaxCountRuleTypeDef,
     ApplyEnvironmentManagedActionRequestRequestTypeDef,
+    ApplyEnvironmentManagedActionResultTypeDef,
     AssociateEnvironmentOperationsRoleMessageRequestTypeDef,
     AutoScalingGroupTypeDef,
     BuildConfigurationTypeDef,
     BuilderTypeDef,
     CPUUtilizationTypeDef,
     CheckDNSAvailabilityMessageRequestTypeDef,
+    CheckDNSAvailabilityResultMessageTypeDef,
     ComposeEnvironmentsMessageRequestTypeDef,
     OptionRestrictionRegexTypeDef,
     ConfigurationOptionSettingTypeDef,
     ValidationMessageTypeDef,
     TagTypeDef,
     SourceConfigurationTypeDef,
     EnvironmentTierTypeDef,
     OptionSpecificationTypeDef,
     PlatformSummaryTypeDef,
+    CreateStorageLocationResultMessageTypeDef,
     CustomAmiTypeDef,
     DeleteApplicationMessageRequestTypeDef,
     DeleteApplicationVersionMessageRequestTypeDef,
     DeleteConfigurationTemplateMessageRequestTypeDef,
     DeleteEnvironmentConfigurationMessageRequestTypeDef,
     DeletePlatformVersionRequestRequestTypeDef,
     DeploymentTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeApplicationVersionsMessageDescribeApplicationVersionsPaginateTypeDef,
     DescribeApplicationVersionsMessageRequestTypeDef,
     DescribeApplicationsMessageRequestTypeDef,
     DescribeConfigurationSettingsMessageRequestTypeDef,
     DescribeEnvironmentHealthRequestRequestTypeDef,
     InstanceHealthSummaryTypeDef,
+    DescribeEnvironmentManagedActionHistoryRequestDescribeEnvironmentManagedActionHistoryPaginateTypeDef,
     DescribeEnvironmentManagedActionHistoryRequestRequestTypeDef,
     ManagedActionHistoryItemTypeDef,
     DescribeEnvironmentManagedActionsRequestRequestTypeDef,
     ManagedActionTypeDef,
     DescribeEnvironmentResourcesMessageRequestTypeDef,
+    DescribeEnvironmentsMessageDescribeEnvironmentsPaginateTypeDef,
     WaiterConfigTypeDef,
     DescribeEnvironmentsMessageRequestTypeDef,
+    DescribeEventsMessageDescribeEventsPaginateTypeDef,
     DescribeEventsMessageRequestTypeDef,
     DescribeInstancesHealthRequestRequestTypeDef,
     DescribePlatformVersionRequestRequestTypeDef,
     DisassociateEnvironmentOperationsRoleMessageRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EnvironmentLinkTypeDef,
     EnvironmentInfoDescriptionTypeDef,
     InstanceTypeDef,
     LaunchConfigurationTypeDef,
     LaunchTemplateTypeDef,
     LoadBalancerTypeDef,
     QueueTypeDef,
@@ -420,29 +426,27 @@
     EventDescriptionTypeDef,
     SolutionStackDescriptionTypeDef,
     SearchFilterTypeDef,
     PlatformBranchSummaryTypeDef,
     PlatformFilterTypeDef,
     ListTagsForResourceMessageRequestTypeDef,
     ListenerTypeDef,
+    PaginatorConfigTypeDef,
     PlatformFrameworkTypeDef,
     PlatformProgrammingLanguageTypeDef,
     RebuildEnvironmentMessageRequestTypeDef,
     RequestEnvironmentInfoMessageRequestTypeDef,
     ResourceQuotaTypeDef,
+    ResponseMetadataTypeDef,
     RestartAppServerMessageRequestTypeDef,
     RetrieveEnvironmentInfoMessageRequestTypeDef,
     SwapEnvironmentCNAMEsMessageRequestTypeDef,
     TerminateEnvironmentMessageRequestTypeDef,
     UpdateApplicationMessageRequestTypeDef,
     UpdateApplicationVersionMessageRequestTypeDef,
-    ApplyEnvironmentManagedActionResultTypeDef,
-    CheckDNSAvailabilityResultMessageTypeDef,
-    CreateStorageLocationResultMessageTypeDef,
-    EmptyResponseMetadataTypeDef,
     ApplicationMetricsTypeDef,
     ApplicationVersionDescriptionTypeDef,
     ApplicationVersionLifecycleConfigTypeDef,
     SystemStatusTypeDef,
     ConfigurationOptionDescriptionTypeDef,
     ConfigurationSettingsDescriptionResponseMetadataTypeDef,
     ConfigurationSettingsDescriptionTypeDef,
@@ -456,18 +460,14 @@
     CreateEnvironmentMessageRequestTypeDef,
     DescribeConfigurationOptionsMessageRequestTypeDef,
     UpdateConfigurationTemplateMessageRequestTypeDef,
     UpdateEnvironmentMessageRequestTypeDef,
     CreatePlatformVersionResultTypeDef,
     DeletePlatformVersionResultTypeDef,
     ListPlatformVersionsResultTypeDef,
-    DescribeApplicationVersionsMessageDescribeApplicationVersionsPaginateTypeDef,
-    DescribeEnvironmentManagedActionHistoryRequestDescribeEnvironmentManagedActionHistoryPaginateTypeDef,
-    DescribeEnvironmentsMessageDescribeEnvironmentsPaginateTypeDef,
-    DescribeEventsMessageDescribeEventsPaginateTypeDef,
     DescribeEnvironmentManagedActionHistoryResultTypeDef,
     DescribeEnvironmentManagedActionsResultTypeDef,
     DescribeEnvironmentsMessageEnvironmentExistsWaitTypeDef,
     DescribeEnvironmentsMessageEnvironmentTerminatedWaitTypeDef,
     DescribeEnvironmentsMessageEnvironmentUpdatedWaitTypeDef,
     RetrieveEnvironmentInfoResultMessageTypeDef,
     EnvironmentResourceDescriptionTypeDef,
@@ -511,43 +511,43 @@
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

### Comparing `types-aiobotocore-elasticbeanstalk-2.5.0.post1/setup.py` & `types-aiobotocore-elasticbeanstalk-2.5.1/setup.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-elasticbeanstalk.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-elasticbeanstalk",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_elasticbeanstalk"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.ElasticBeanstalk 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.ElasticBeanstalk 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticbeanstalk/"
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

### Comparing `types-aiobotocore-elasticbeanstalk-2.5.0.post1/types_aiobotocore_elasticbeanstalk/__init__.py` & `types-aiobotocore-elasticbeanstalk-2.5.1/types_aiobotocore_elasticbeanstalk/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-elasticbeanstalk-2.5.0.post1/types_aiobotocore_elasticbeanstalk/__init__.pyi` & `types-aiobotocore-elasticbeanstalk-2.5.1/types_aiobotocore_elasticbeanstalk/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-elasticbeanstalk-2.5.0.post1/types_aiobotocore_elasticbeanstalk/__main__.py` & `types-aiobotocore-elasticbeanstalk-2.5.1/types_aiobotocore_elasticbeanstalk/__main__.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.ElasticBeanstalk 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.ElasticBeanstalk 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticbeanstalk//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk\nOther"
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

### Comparing `types-aiobotocore-elasticbeanstalk-2.5.0.post1/types_aiobotocore_elasticbeanstalk/client.py` & `types-aiobotocore-elasticbeanstalk-2.5.1/types_aiobotocore_elasticbeanstalk/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-elasticbeanstalk-2.5.0.post1/types_aiobotocore_elasticbeanstalk/client.pyi` & `types-aiobotocore-elasticbeanstalk-2.5.1/types_aiobotocore_elasticbeanstalk/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-elasticbeanstalk-2.5.0.post1/types_aiobotocore_elasticbeanstalk/literals.py` & `types-aiobotocore-elasticbeanstalk-2.5.1/types_aiobotocore_elasticbeanstalk/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -186,14 +186,15 @@
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
@@ -272,14 +273,15 @@
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
@@ -290,14 +292,15 @@
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
@@ -333,14 +336,15 @@
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
@@ -359,16 +363,19 @@
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
@@ -452,15 +459,17 @@
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

### Comparing `types-aiobotocore-elasticbeanstalk-2.5.0.post1/types_aiobotocore_elasticbeanstalk/literals.pyi` & `types-aiobotocore-elasticbeanstalk-2.5.1/types_aiobotocore_elasticbeanstalk/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -184,14 +184,15 @@
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
@@ -270,14 +271,15 @@
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
@@ -288,14 +290,15 @@
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
@@ -331,14 +334,15 @@
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
@@ -357,16 +361,19 @@
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
@@ -450,15 +457,17 @@
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

### Comparing `types-aiobotocore-elasticbeanstalk-2.5.0.post1/types_aiobotocore_elasticbeanstalk/paginator.py` & `types-aiobotocore-elasticbeanstalk-2.5.1/types_aiobotocore_elasticbeanstalk/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -24,17 +24,16 @@
         describe_application_versions_paginator: DescribeApplicationVersionsPaginator = client.get_paginator("describe_application_versions")
         describe_environment_managed_action_history_paginator: DescribeEnvironmentManagedActionHistoryPaginator = client.get_paginator("describe_environment_managed_action_history")
         describe_environments_paginator: DescribeEnvironmentsPaginator = client.get_paginator("describe_environments")
         describe_events_paginator: DescribeEventsPaginator = client.get_paginator("describe_events")
         list_platform_versions_paginator: ListPlatformVersionsPaginator = client.get_paginator("list_platform_versions")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, Sequence, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import EventSeverityType
 from .type_defs import (
     ApplicationVersionDescriptionsMessageTypeDef,
@@ -42,20 +41,14 @@
     EnvironmentDescriptionsMessageTypeDef,
     EventDescriptionsMessageTypeDef,
     ListPlatformVersionsResultTypeDef,
     PaginatorConfigTypeDef,
     PlatformFilterTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "DescribeApplicationVersionsPaginator",
     "DescribeEnvironmentManagedActionHistoryPaginator",
     "DescribeEnvironmentsPaginator",
     "DescribeEventsPaginator",
     "ListPlatformVersionsPaginator",
 )
@@ -78,15 +71,15 @@
     """
 
     def paginate(
         self,
         *,
         ApplicationName: str = ...,
         VersionLabels: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ApplicationVersionDescriptionsMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Paginator.DescribeApplicationVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticbeanstalk/paginators/#describeapplicationversionspaginator)
         """
 
 
@@ -97,15 +90,15 @@
     """
 
     def paginate(
         self,
         *,
         EnvironmentId: str = ...,
         EnvironmentName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEnvironmentManagedActionHistoryResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Paginator.DescribeEnvironmentManagedActionHistory.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticbeanstalk/paginators/#describeenvironmentmanagedactionhistorypaginator)
         """
 
 
@@ -120,15 +113,15 @@
         *,
         ApplicationName: str = ...,
         VersionLabel: str = ...,
         EnvironmentIds: Sequence[str] = ...,
         EnvironmentNames: Sequence[str] = ...,
         IncludeDeleted: bool = ...,
         IncludedDeletedBackTo: Union[datetime, str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[EnvironmentDescriptionsMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Paginator.DescribeEnvironments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticbeanstalk/paginators/#describeenvironmentspaginator)
         """
 
 
@@ -147,15 +140,15 @@
         EnvironmentId: str = ...,
         EnvironmentName: str = ...,
         PlatformArn: str = ...,
         RequestId: str = ...,
         Severity: EventSeverityType = ...,
         StartTime: Union[datetime, str] = ...,
         EndTime: Union[datetime, str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[EventDescriptionsMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Paginator.DescribeEvents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticbeanstalk/paginators/#describeeventspaginator)
         """
 
 
@@ -165,13 +158,13 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticbeanstalk/paginators/#listplatformversionspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[PlatformFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPlatformVersionsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Paginator.ListPlatformVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticbeanstalk/paginators/#listplatformversionspaginator)
         """
```

### Comparing `types-aiobotocore-elasticbeanstalk-2.5.0.post1/types_aiobotocore_elasticbeanstalk/paginator.pyi` & `types-aiobotocore-elasticbeanstalk-2.5.1/types_aiobotocore_elasticbeanstalk/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -24,17 +24,16 @@
         describe_application_versions_paginator: DescribeApplicationVersionsPaginator = client.get_paginator("describe_application_versions")
         describe_environment_managed_action_history_paginator: DescribeEnvironmentManagedActionHistoryPaginator = client.get_paginator("describe_environment_managed_action_history")
         describe_environments_paginator: DescribeEnvironmentsPaginator = client.get_paginator("describe_environments")
         describe_events_paginator: DescribeEventsPaginator = client.get_paginator("describe_events")
         list_platform_versions_paginator: ListPlatformVersionsPaginator = client.get_paginator("list_platform_versions")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, Sequence, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import EventSeverityType
 from .type_defs import (
     ApplicationVersionDescriptionsMessageTypeDef,
@@ -42,19 +41,14 @@
     EnvironmentDescriptionsMessageTypeDef,
     EventDescriptionsMessageTypeDef,
     ListPlatformVersionsResultTypeDef,
     PaginatorConfigTypeDef,
     PlatformFilterTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "DescribeApplicationVersionsPaginator",
     "DescribeEnvironmentManagedActionHistoryPaginator",
     "DescribeEnvironmentsPaginator",
     "DescribeEventsPaginator",
     "ListPlatformVersionsPaginator",
 )
@@ -74,15 +68,15 @@
     """
 
     def paginate(
         self,
         *,
         ApplicationName: str = ...,
         VersionLabels: Sequence[str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ApplicationVersionDescriptionsMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Paginator.DescribeApplicationVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticbeanstalk/paginators/#describeapplicationversionspaginator)
         """
 
 class DescribeEnvironmentManagedActionHistoryPaginator(AioPaginator):
@@ -92,15 +86,15 @@
     """
 
     def paginate(
         self,
         *,
         EnvironmentId: str = ...,
         EnvironmentName: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeEnvironmentManagedActionHistoryResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Paginator.DescribeEnvironmentManagedActionHistory.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticbeanstalk/paginators/#describeenvironmentmanagedactionhistorypaginator)
         """
 
 class DescribeEnvironmentsPaginator(AioPaginator):
@@ -114,15 +108,15 @@
         *,
         ApplicationName: str = ...,
         VersionLabel: str = ...,
         EnvironmentIds: Sequence[str] = ...,
         EnvironmentNames: Sequence[str] = ...,
         IncludeDeleted: bool = ...,
         IncludedDeletedBackTo: Union[datetime, str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[EnvironmentDescriptionsMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Paginator.DescribeEnvironments.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticbeanstalk/paginators/#describeenvironmentspaginator)
         """
 
 class DescribeEventsPaginator(AioPaginator):
@@ -140,15 +134,15 @@
         EnvironmentId: str = ...,
         EnvironmentName: str = ...,
         PlatformArn: str = ...,
         RequestId: str = ...,
         Severity: EventSeverityType = ...,
         StartTime: Union[datetime, str] = ...,
         EndTime: Union[datetime, str] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[EventDescriptionsMessageTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Paginator.DescribeEvents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticbeanstalk/paginators/#describeeventspaginator)
         """
 
 class ListPlatformVersionsPaginator(AioPaginator):
@@ -157,13 +151,13 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticbeanstalk/paginators/#listplatformversionspaginator)
     """
 
     def paginate(
         self,
         *,
         Filters: Sequence[PlatformFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListPlatformVersionsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk.Paginator.ListPlatformVersions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticbeanstalk/paginators/#listplatformversionspaginator)
         """
```

### Comparing `types-aiobotocore-elasticbeanstalk-2.5.0.post1/types_aiobotocore_elasticbeanstalk/type_defs.py` & `types-aiobotocore-elasticbeanstalk-2.5.1/types_aiobotocore_elasticbeanstalk/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -41,61 +41,67 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AbortEnvironmentUpdateMessageRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "LatencyTypeDef",
     "StatusCodesTypeDef",
     "S3LocationTypeDef",
     "SourceBuildInformationTypeDef",
     "MaxAgeRuleTypeDef",
     "MaxCountRuleTypeDef",
     "ApplyEnvironmentManagedActionRequestRequestTypeDef",
+    "ApplyEnvironmentManagedActionResultTypeDef",
     "AssociateEnvironmentOperationsRoleMessageRequestTypeDef",
     "AutoScalingGroupTypeDef",
     "BuildConfigurationTypeDef",
     "BuilderTypeDef",
     "CPUUtilizationTypeDef",
     "CheckDNSAvailabilityMessageRequestTypeDef",
+    "CheckDNSAvailabilityResultMessageTypeDef",
     "ComposeEnvironmentsMessageRequestTypeDef",
     "OptionRestrictionRegexTypeDef",
     "ConfigurationOptionSettingTypeDef",
     "ValidationMessageTypeDef",
     "TagTypeDef",
     "SourceConfigurationTypeDef",
     "EnvironmentTierTypeDef",
     "OptionSpecificationTypeDef",
     "PlatformSummaryTypeDef",
+    "CreateStorageLocationResultMessageTypeDef",
     "CustomAmiTypeDef",
     "DeleteApplicationMessageRequestTypeDef",
     "DeleteApplicationVersionMessageRequestTypeDef",
     "DeleteConfigurationTemplateMessageRequestTypeDef",
     "DeleteEnvironmentConfigurationMessageRequestTypeDef",
     "DeletePlatformVersionRequestRequestTypeDef",
     "DeploymentTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeApplicationVersionsMessageDescribeApplicationVersionsPaginateTypeDef",
     "DescribeApplicationVersionsMessageRequestTypeDef",
     "DescribeApplicationsMessageRequestTypeDef",
     "DescribeConfigurationSettingsMessageRequestTypeDef",
     "DescribeEnvironmentHealthRequestRequestTypeDef",
     "InstanceHealthSummaryTypeDef",
+    "DescribeEnvironmentManagedActionHistoryRequestDescribeEnvironmentManagedActionHistoryPaginateTypeDef",
     "DescribeEnvironmentManagedActionHistoryRequestRequestTypeDef",
     "ManagedActionHistoryItemTypeDef",
     "DescribeEnvironmentManagedActionsRequestRequestTypeDef",
     "ManagedActionTypeDef",
     "DescribeEnvironmentResourcesMessageRequestTypeDef",
+    "DescribeEnvironmentsMessageDescribeEnvironmentsPaginateTypeDef",
     "WaiterConfigTypeDef",
     "DescribeEnvironmentsMessageRequestTypeDef",
+    "DescribeEventsMessageDescribeEventsPaginateTypeDef",
     "DescribeEventsMessageRequestTypeDef",
     "DescribeInstancesHealthRequestRequestTypeDef",
     "DescribePlatformVersionRequestRequestTypeDef",
     "DisassociateEnvironmentOperationsRoleMessageRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EnvironmentLinkTypeDef",
     "EnvironmentInfoDescriptionTypeDef",
     "InstanceTypeDef",
     "LaunchConfigurationTypeDef",
     "LaunchTemplateTypeDef",
     "LoadBalancerTypeDef",
     "QueueTypeDef",
@@ -103,29 +109,27 @@
     "EventDescriptionTypeDef",
     "SolutionStackDescriptionTypeDef",
     "SearchFilterTypeDef",
     "PlatformBranchSummaryTypeDef",
     "PlatformFilterTypeDef",
     "ListTagsForResourceMessageRequestTypeDef",
     "ListenerTypeDef",
+    "PaginatorConfigTypeDef",
     "PlatformFrameworkTypeDef",
     "PlatformProgrammingLanguageTypeDef",
     "RebuildEnvironmentMessageRequestTypeDef",
     "RequestEnvironmentInfoMessageRequestTypeDef",
     "ResourceQuotaTypeDef",
+    "ResponseMetadataTypeDef",
     "RestartAppServerMessageRequestTypeDef",
     "RetrieveEnvironmentInfoMessageRequestTypeDef",
     "SwapEnvironmentCNAMEsMessageRequestTypeDef",
     "TerminateEnvironmentMessageRequestTypeDef",
     "UpdateApplicationMessageRequestTypeDef",
     "UpdateApplicationVersionMessageRequestTypeDef",
-    "ApplyEnvironmentManagedActionResultTypeDef",
-    "CheckDNSAvailabilityResultMessageTypeDef",
-    "CreateStorageLocationResultMessageTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "ApplicationMetricsTypeDef",
     "ApplicationVersionDescriptionTypeDef",
     "ApplicationVersionLifecycleConfigTypeDef",
     "SystemStatusTypeDef",
     "ConfigurationOptionDescriptionTypeDef",
     "ConfigurationSettingsDescriptionResponseMetadataTypeDef",
     "ConfigurationSettingsDescriptionTypeDef",
@@ -139,18 +143,14 @@
     "CreateEnvironmentMessageRequestTypeDef",
     "DescribeConfigurationOptionsMessageRequestTypeDef",
     "UpdateConfigurationTemplateMessageRequestTypeDef",
     "UpdateEnvironmentMessageRequestTypeDef",
     "CreatePlatformVersionResultTypeDef",
     "DeletePlatformVersionResultTypeDef",
     "ListPlatformVersionsResultTypeDef",
-    "DescribeApplicationVersionsMessageDescribeApplicationVersionsPaginateTypeDef",
-    "DescribeEnvironmentManagedActionHistoryRequestDescribeEnvironmentManagedActionHistoryPaginateTypeDef",
-    "DescribeEnvironmentsMessageDescribeEnvironmentsPaginateTypeDef",
-    "DescribeEventsMessageDescribeEventsPaginateTypeDef",
     "DescribeEnvironmentManagedActionHistoryResultTypeDef",
     "DescribeEnvironmentManagedActionsResultTypeDef",
     "DescribeEnvironmentsMessageEnvironmentExistsWaitTypeDef",
     "DescribeEnvironmentsMessageEnvironmentTerminatedWaitTypeDef",
     "DescribeEnvironmentsMessageEnvironmentUpdatedWaitTypeDef",
     "RetrieveEnvironmentInfoResultMessageTypeDef",
     "EnvironmentResourceDescriptionTypeDef",
@@ -191,25 +191,14 @@
     {
         "EnvironmentId": str,
         "EnvironmentName": str,
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
 LatencyTypeDef = TypedDict(
     "LatencyTypeDef",
     {
         "P999": float,
         "P99": float,
         "P95": float,
         "P90": float,
@@ -309,14 +298,25 @@
 class ApplyEnvironmentManagedActionRequestRequestTypeDef(
     _RequiredApplyEnvironmentManagedActionRequestRequestTypeDef,
     _OptionalApplyEnvironmentManagedActionRequestRequestTypeDef,
 ):
     pass
 
 
+ApplyEnvironmentManagedActionResultTypeDef = TypedDict(
+    "ApplyEnvironmentManagedActionResultTypeDef",
+    {
+        "ActionId": str,
+        "ActionDescription": str,
+        "ActionType": ActionTypeType,
+        "Status": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AssociateEnvironmentOperationsRoleMessageRequestTypeDef = TypedDict(
     "AssociateEnvironmentOperationsRoleMessageRequestTypeDef",
     {
         "EnvironmentName": str,
         "OperationsRole": str,
     },
 )
@@ -379,14 +379,23 @@
 CheckDNSAvailabilityMessageRequestTypeDef = TypedDict(
     "CheckDNSAvailabilityMessageRequestTypeDef",
     {
         "CNAMEPrefix": str,
     },
 )
 
+CheckDNSAvailabilityResultMessageTypeDef = TypedDict(
+    "CheckDNSAvailabilityResultMessageTypeDef",
+    {
+        "Available": bool,
+        "FullyQualifiedCNAME": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ComposeEnvironmentsMessageRequestTypeDef = TypedDict(
     "ComposeEnvironmentsMessageRequestTypeDef",
     {
         "ApplicationName": str,
         "GroupName": str,
         "VersionLabels": Sequence[str],
     },
@@ -477,14 +486,22 @@
         "PlatformVersion": str,
         "PlatformBranchName": str,
         "PlatformBranchLifecycleState": str,
     },
     total=False,
 )
 
+CreateStorageLocationResultMessageTypeDef = TypedDict(
+    "CreateStorageLocationResultMessageTypeDef",
+    {
+        "S3Bucket": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CustomAmiTypeDef = TypedDict(
     "CustomAmiTypeDef",
     {
         "VirtualizationType": str,
         "ImageId": str,
     },
     total=False,
@@ -565,20 +582,20 @@
         "DeploymentId": int,
         "Status": str,
         "DeploymentTime": datetime,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeApplicationVersionsMessageDescribeApplicationVersionsPaginateTypeDef = TypedDict(
+    "DescribeApplicationVersionsMessageDescribeApplicationVersionsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ApplicationName": str,
+        "VersionLabels": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeApplicationVersionsMessageRequestTypeDef = TypedDict(
     "DescribeApplicationVersionsMessageRequestTypeDef",
     {
@@ -642,14 +659,24 @@
         "Warning": int,
         "Degraded": int,
         "Severe": int,
     },
     total=False,
 )
 
+DescribeEnvironmentManagedActionHistoryRequestDescribeEnvironmentManagedActionHistoryPaginateTypeDef = TypedDict(
+    "DescribeEnvironmentManagedActionHistoryRequestDescribeEnvironmentManagedActionHistoryPaginateTypeDef",
+    {
+        "EnvironmentId": str,
+        "EnvironmentName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeEnvironmentManagedActionHistoryRequestRequestTypeDef = TypedDict(
     "DescribeEnvironmentManagedActionHistoryRequestRequestTypeDef",
     {
         "EnvironmentId": str,
         "EnvironmentName": str,
         "NextToken": str,
         "MaxItems": int,
@@ -699,14 +726,28 @@
     {
         "EnvironmentId": str,
         "EnvironmentName": str,
     },
     total=False,
 )
 
+DescribeEnvironmentsMessageDescribeEnvironmentsPaginateTypeDef = TypedDict(
+    "DescribeEnvironmentsMessageDescribeEnvironmentsPaginateTypeDef",
+    {
+        "ApplicationName": str,
+        "VersionLabel": str,
+        "EnvironmentIds": Sequence[str],
+        "EnvironmentNames": Sequence[str],
+        "IncludeDeleted": bool,
+        "IncludedDeletedBackTo": Union[datetime, str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 WaiterConfigTypeDef = TypedDict(
     "WaiterConfigTypeDef",
     {
         "Delay": int,
         "MaxAttempts": int,
     },
     total=False,
@@ -723,14 +764,32 @@
         "IncludedDeletedBackTo": Union[datetime, str],
         "MaxRecords": int,
         "NextToken": str,
     },
     total=False,
 )
 
+DescribeEventsMessageDescribeEventsPaginateTypeDef = TypedDict(
+    "DescribeEventsMessageDescribeEventsPaginateTypeDef",
+    {
+        "ApplicationName": str,
+        "VersionLabel": str,
+        "TemplateName": str,
+        "EnvironmentId": str,
+        "EnvironmentName": str,
+        "PlatformArn": str,
+        "RequestId": str,
+        "Severity": EventSeverityType,
+        "StartTime": Union[datetime, str],
+        "EndTime": Union[datetime, str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeEventsMessageRequestTypeDef = TypedDict(
     "DescribeEventsMessageRequestTypeDef",
     {
         "ApplicationName": str,
         "VersionLabel": str,
         "TemplateName": str,
         "EnvironmentId": str,
@@ -768,14 +827,21 @@
 DisassociateEnvironmentOperationsRoleMessageRequestTypeDef = TypedDict(
     "DisassociateEnvironmentOperationsRoleMessageRequestTypeDef",
     {
         "EnvironmentName": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EnvironmentLinkTypeDef = TypedDict(
     "EnvironmentLinkTypeDef",
     {
         "LinkName": str,
         "EnvironmentName": str,
     },
     total=False,
@@ -910,14 +976,24 @@
     {
         "Protocol": str,
         "Port": int,
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
 PlatformFrameworkTypeDef = TypedDict(
     "PlatformFrameworkTypeDef",
     {
         "Name": str,
         "Version": str,
     },
     total=False,
@@ -968,14 +1044,25 @@
     "ResourceQuotaTypeDef",
     {
         "Maximum": int,
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
 RestartAppServerMessageRequestTypeDef = TypedDict(
     "RestartAppServerMessageRequestTypeDef",
     {
         "EnvironmentId": str,
         "EnvironmentName": str,
     },
     total=False,
@@ -1066,49 +1153,14 @@
 class UpdateApplicationVersionMessageRequestTypeDef(
     _RequiredUpdateApplicationVersionMessageRequestTypeDef,
     _OptionalUpdateApplicationVersionMessageRequestTypeDef,
 ):
     pass
 
 
-ApplyEnvironmentManagedActionResultTypeDef = TypedDict(
-    "ApplyEnvironmentManagedActionResultTypeDef",
-    {
-        "ActionId": str,
-        "ActionDescription": str,
-        "ActionType": ActionTypeType,
-        "Status": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CheckDNSAvailabilityResultMessageTypeDef = TypedDict(
-    "CheckDNSAvailabilityResultMessageTypeDef",
-    {
-        "Available": bool,
-        "FullyQualifiedCNAME": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateStorageLocationResultMessageTypeDef = TypedDict(
-    "CreateStorageLocationResultMessageTypeDef",
-    {
-        "S3Bucket": str,
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
 ApplicationMetricsTypeDef = TypedDict(
     "ApplicationMetricsTypeDef",
     {
         "Duration": int,
         "RequestCount": int,
         "StatusCodes": StatusCodesTypeDef,
         "Latency": LatencyTypeDef,
@@ -1178,15 +1230,15 @@
         "TemplateName": str,
         "Description": str,
         "EnvironmentName": str,
         "DeploymentStatus": ConfigurationDeploymentStatusType,
         "DateCreated": datetime,
         "DateUpdated": datetime,
         "OptionSettings": List[ConfigurationOptionSettingTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ConfigurationSettingsDescriptionTypeDef = TypedDict(
     "ConfigurationSettingsDescriptionTypeDef",
     {
         "SolutionStackName": str,
@@ -1227,15 +1279,15 @@
     pass
 
 
 ConfigurationSettingsValidationMessagesTypeDef = TypedDict(
     "ConfigurationSettingsValidationMessagesTypeDef",
     {
         "Messages": List[ValidationMessageTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateApplicationVersionMessageRequestTypeDef = TypedDict(
     "_RequiredCreateApplicationVersionMessageRequestTypeDef",
     {
         "ApplicationName": str,
@@ -1291,15 +1343,15 @@
 
 
 ResourceTagsDescriptionMessageTypeDef = TypedDict(
     "ResourceTagsDescriptionMessageTypeDef",
     {
         "ResourceArn": str,
         "ResourceTags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateTagsForResourceMessageRequestTypeDef = TypedDict(
     "_RequiredUpdateTagsForResourceMessageRequestTypeDef",
     {
         "ResourceArn": str,
@@ -1442,101 +1494,49 @@
 )
 
 CreatePlatformVersionResultTypeDef = TypedDict(
     "CreatePlatformVersionResultTypeDef",
     {
         "PlatformSummary": PlatformSummaryTypeDef,
         "Builder": BuilderTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeletePlatformVersionResultTypeDef = TypedDict(
     "DeletePlatformVersionResultTypeDef",
     {
         "PlatformSummary": PlatformSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPlatformVersionsResultTypeDef = TypedDict(
     "ListPlatformVersionsResultTypeDef",
     {
         "PlatformSummaryList": List[PlatformSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeApplicationVersionsMessageDescribeApplicationVersionsPaginateTypeDef = TypedDict(
-    "DescribeApplicationVersionsMessageDescribeApplicationVersionsPaginateTypeDef",
-    {
-        "ApplicationName": str,
-        "VersionLabels": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeEnvironmentManagedActionHistoryRequestDescribeEnvironmentManagedActionHistoryPaginateTypeDef = TypedDict(
-    "DescribeEnvironmentManagedActionHistoryRequestDescribeEnvironmentManagedActionHistoryPaginateTypeDef",
-    {
-        "EnvironmentId": str,
-        "EnvironmentName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeEnvironmentsMessageDescribeEnvironmentsPaginateTypeDef = TypedDict(
-    "DescribeEnvironmentsMessageDescribeEnvironmentsPaginateTypeDef",
-    {
-        "ApplicationName": str,
-        "VersionLabel": str,
-        "EnvironmentIds": Sequence[str],
-        "EnvironmentNames": Sequence[str],
-        "IncludeDeleted": bool,
-        "IncludedDeletedBackTo": Union[datetime, str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeEventsMessageDescribeEventsPaginateTypeDef = TypedDict(
-    "DescribeEventsMessageDescribeEventsPaginateTypeDef",
-    {
-        "ApplicationName": str,
-        "VersionLabel": str,
-        "TemplateName": str,
-        "EnvironmentId": str,
-        "EnvironmentName": str,
-        "PlatformArn": str,
-        "RequestId": str,
-        "Severity": EventSeverityType,
-        "StartTime": Union[datetime, str],
-        "EndTime": Union[datetime, str],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
 DescribeEnvironmentManagedActionHistoryResultTypeDef = TypedDict(
     "DescribeEnvironmentManagedActionHistoryResultTypeDef",
     {
         "ManagedActionHistoryItems": List[ManagedActionHistoryItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEnvironmentManagedActionsResultTypeDef = TypedDict(
     "DescribeEnvironmentManagedActionsResultTypeDef",
     {
         "ManagedActions": List[ManagedActionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEnvironmentsMessageEnvironmentExistsWaitTypeDef = TypedDict(
     "DescribeEnvironmentsMessageEnvironmentExistsWaitTypeDef",
     {
         "ApplicationName": str,
@@ -1584,15 +1584,15 @@
     total=False,
 )
 
 RetrieveEnvironmentInfoResultMessageTypeDef = TypedDict(
     "RetrieveEnvironmentInfoResultMessageTypeDef",
     {
         "EnvironmentInfo": List[EnvironmentInfoDescriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EnvironmentResourceDescriptionTypeDef = TypedDict(
     "EnvironmentResourceDescriptionTypeDef",
     {
         "EnvironmentName": str,
@@ -1608,24 +1608,24 @@
 )
 
 EventDescriptionsMessageTypeDef = TypedDict(
     "EventDescriptionsMessageTypeDef",
     {
         "Events": List[EventDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAvailableSolutionStacksResultMessageTypeDef = TypedDict(
     "ListAvailableSolutionStacksResultMessageTypeDef",
     {
         "SolutionStacks": List[str],
         "SolutionStackDetails": List[SolutionStackDescriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPlatformBranchesRequestRequestTypeDef = TypedDict(
     "ListPlatformBranchesRequestRequestTypeDef",
     {
         "Filters": Sequence[SearchFilterTypeDef],
@@ -1636,23 +1636,23 @@
 )
 
 ListPlatformBranchesResultTypeDef = TypedDict(
     "ListPlatformBranchesResultTypeDef",
     {
         "PlatformBranchSummaryList": List[PlatformBranchSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPlatformVersionsRequestListPlatformVersionsPaginateTypeDef = TypedDict(
     "ListPlatformVersionsRequestListPlatformVersionsPaginateTypeDef",
     {
         "Filters": Sequence[PlatformFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListPlatformVersionsRequestRequestTypeDef = TypedDict(
     "ListPlatformVersionsRequestRequestTypeDef",
     {
@@ -1720,32 +1720,32 @@
         "HealthStatus": str,
         "Status": EnvironmentHealthType,
         "Color": str,
         "Causes": List[str],
         "ApplicationMetrics": ApplicationMetricsTypeDef,
         "InstancesHealth": InstanceHealthSummaryTypeDef,
         "RefreshedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ApplicationVersionDescriptionMessageTypeDef = TypedDict(
     "ApplicationVersionDescriptionMessageTypeDef",
     {
         "ApplicationVersion": ApplicationVersionDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ApplicationVersionDescriptionsMessageTypeDef = TypedDict(
     "ApplicationVersionDescriptionsMessageTypeDef",
     {
         "ApplicationVersions": List[ApplicationVersionDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ApplicationResourceLifecycleConfigTypeDef = TypedDict(
     "ApplicationResourceLifecycleConfigTypeDef",
     {
         "ServiceRole": str,
@@ -1773,31 +1773,31 @@
 
 ConfigurationOptionsDescriptionTypeDef = TypedDict(
     "ConfigurationOptionsDescriptionTypeDef",
     {
         "SolutionStackName": str,
         "PlatformArn": str,
         "Options": List[ConfigurationOptionDescriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ConfigurationSettingsDescriptionsTypeDef = TypedDict(
     "ConfigurationSettingsDescriptionsTypeDef",
     {
         "ConfigurationSettings": List[ConfigurationSettingsDescriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EnvironmentResourceDescriptionsMessageTypeDef = TypedDict(
     "EnvironmentResourceDescriptionsMessageTypeDef",
     {
         "EnvironmentResources": EnvironmentResourceDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EnvironmentResourcesDescriptionTypeDef = TypedDict(
     "EnvironmentResourcesDescriptionTypeDef",
     {
         "LoadBalancer": LoadBalancerDescriptionTypeDef,
@@ -1805,23 +1805,23 @@
     total=False,
 )
 
 DescribePlatformVersionResultTypeDef = TypedDict(
     "DescribePlatformVersionResultTypeDef",
     {
         "PlatformDescription": PlatformDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAccountAttributesResultTypeDef = TypedDict(
     "DescribeAccountAttributesResultTypeDef",
     {
         "ResourceQuotas": ResourceQuotasTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ApplicationDescriptionTypeDef = TypedDict(
     "ApplicationDescriptionTypeDef",
     {
         "ApplicationArn": str,
@@ -1837,15 +1837,15 @@
 )
 
 ApplicationResourceLifecycleDescriptionMessageTypeDef = TypedDict(
     "ApplicationResourceLifecycleDescriptionMessageTypeDef",
     {
         "ApplicationName": str,
         "ResourceLifecycleConfig": ApplicationResourceLifecycleConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateApplicationMessageRequestTypeDef = TypedDict(
     "_RequiredCreateApplicationMessageRequestTypeDef",
     {
         "ApplicationName": str,
@@ -1878,15 +1878,15 @@
 
 DescribeInstancesHealthResultTypeDef = TypedDict(
     "DescribeInstancesHealthResultTypeDef",
     {
         "InstanceHealthList": List[SingleInstanceHealthTypeDef],
         "RefreshedAt": datetime,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EnvironmentDescriptionResponseMetadataTypeDef = TypedDict(
     "EnvironmentDescriptionResponseMetadataTypeDef",
     {
         "EnvironmentName": str,
@@ -1906,15 +1906,15 @@
         "Health": EnvironmentHealthType,
         "HealthStatus": EnvironmentHealthStatusType,
         "Resources": EnvironmentResourcesDescriptionTypeDef,
         "Tier": EnvironmentTierTypeDef,
         "EnvironmentLinks": List[EnvironmentLinkTypeDef],
         "EnvironmentArn": str,
         "OperationsRole": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EnvironmentDescriptionTypeDef = TypedDict(
     "EnvironmentDescriptionTypeDef",
     {
         "EnvironmentName": str,
@@ -1942,27 +1942,27 @@
     total=False,
 )
 
 ApplicationDescriptionMessageTypeDef = TypedDict(
     "ApplicationDescriptionMessageTypeDef",
     {
         "Application": ApplicationDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ApplicationDescriptionsMessageTypeDef = TypedDict(
     "ApplicationDescriptionsMessageTypeDef",
     {
         "Applications": List[ApplicationDescriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EnvironmentDescriptionsMessageTypeDef = TypedDict(
     "EnvironmentDescriptionsMessageTypeDef",
     {
         "Environments": List[EnvironmentDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-elasticbeanstalk-2.5.0.post1/types_aiobotocore_elasticbeanstalk/type_defs.pyi` & `types-aiobotocore-elasticbeanstalk-2.5.1/types_aiobotocore_elasticbeanstalk/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -40,61 +40,67 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AbortEnvironmentUpdateMessageRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "LatencyTypeDef",
     "StatusCodesTypeDef",
     "S3LocationTypeDef",
     "SourceBuildInformationTypeDef",
     "MaxAgeRuleTypeDef",
     "MaxCountRuleTypeDef",
     "ApplyEnvironmentManagedActionRequestRequestTypeDef",
+    "ApplyEnvironmentManagedActionResultTypeDef",
     "AssociateEnvironmentOperationsRoleMessageRequestTypeDef",
     "AutoScalingGroupTypeDef",
     "BuildConfigurationTypeDef",
     "BuilderTypeDef",
     "CPUUtilizationTypeDef",
     "CheckDNSAvailabilityMessageRequestTypeDef",
+    "CheckDNSAvailabilityResultMessageTypeDef",
     "ComposeEnvironmentsMessageRequestTypeDef",
     "OptionRestrictionRegexTypeDef",
     "ConfigurationOptionSettingTypeDef",
     "ValidationMessageTypeDef",
     "TagTypeDef",
     "SourceConfigurationTypeDef",
     "EnvironmentTierTypeDef",
     "OptionSpecificationTypeDef",
     "PlatformSummaryTypeDef",
+    "CreateStorageLocationResultMessageTypeDef",
     "CustomAmiTypeDef",
     "DeleteApplicationMessageRequestTypeDef",
     "DeleteApplicationVersionMessageRequestTypeDef",
     "DeleteConfigurationTemplateMessageRequestTypeDef",
     "DeleteEnvironmentConfigurationMessageRequestTypeDef",
     "DeletePlatformVersionRequestRequestTypeDef",
     "DeploymentTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeApplicationVersionsMessageDescribeApplicationVersionsPaginateTypeDef",
     "DescribeApplicationVersionsMessageRequestTypeDef",
     "DescribeApplicationsMessageRequestTypeDef",
     "DescribeConfigurationSettingsMessageRequestTypeDef",
     "DescribeEnvironmentHealthRequestRequestTypeDef",
     "InstanceHealthSummaryTypeDef",
+    "DescribeEnvironmentManagedActionHistoryRequestDescribeEnvironmentManagedActionHistoryPaginateTypeDef",
     "DescribeEnvironmentManagedActionHistoryRequestRequestTypeDef",
     "ManagedActionHistoryItemTypeDef",
     "DescribeEnvironmentManagedActionsRequestRequestTypeDef",
     "ManagedActionTypeDef",
     "DescribeEnvironmentResourcesMessageRequestTypeDef",
+    "DescribeEnvironmentsMessageDescribeEnvironmentsPaginateTypeDef",
     "WaiterConfigTypeDef",
     "DescribeEnvironmentsMessageRequestTypeDef",
+    "DescribeEventsMessageDescribeEventsPaginateTypeDef",
     "DescribeEventsMessageRequestTypeDef",
     "DescribeInstancesHealthRequestRequestTypeDef",
     "DescribePlatformVersionRequestRequestTypeDef",
     "DisassociateEnvironmentOperationsRoleMessageRequestTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "EnvironmentLinkTypeDef",
     "EnvironmentInfoDescriptionTypeDef",
     "InstanceTypeDef",
     "LaunchConfigurationTypeDef",
     "LaunchTemplateTypeDef",
     "LoadBalancerTypeDef",
     "QueueTypeDef",
@@ -102,29 +108,27 @@
     "EventDescriptionTypeDef",
     "SolutionStackDescriptionTypeDef",
     "SearchFilterTypeDef",
     "PlatformBranchSummaryTypeDef",
     "PlatformFilterTypeDef",
     "ListTagsForResourceMessageRequestTypeDef",
     "ListenerTypeDef",
+    "PaginatorConfigTypeDef",
     "PlatformFrameworkTypeDef",
     "PlatformProgrammingLanguageTypeDef",
     "RebuildEnvironmentMessageRequestTypeDef",
     "RequestEnvironmentInfoMessageRequestTypeDef",
     "ResourceQuotaTypeDef",
+    "ResponseMetadataTypeDef",
     "RestartAppServerMessageRequestTypeDef",
     "RetrieveEnvironmentInfoMessageRequestTypeDef",
     "SwapEnvironmentCNAMEsMessageRequestTypeDef",
     "TerminateEnvironmentMessageRequestTypeDef",
     "UpdateApplicationMessageRequestTypeDef",
     "UpdateApplicationVersionMessageRequestTypeDef",
-    "ApplyEnvironmentManagedActionResultTypeDef",
-    "CheckDNSAvailabilityResultMessageTypeDef",
-    "CreateStorageLocationResultMessageTypeDef",
-    "EmptyResponseMetadataTypeDef",
     "ApplicationMetricsTypeDef",
     "ApplicationVersionDescriptionTypeDef",
     "ApplicationVersionLifecycleConfigTypeDef",
     "SystemStatusTypeDef",
     "ConfigurationOptionDescriptionTypeDef",
     "ConfigurationSettingsDescriptionResponseMetadataTypeDef",
     "ConfigurationSettingsDescriptionTypeDef",
@@ -138,18 +142,14 @@
     "CreateEnvironmentMessageRequestTypeDef",
     "DescribeConfigurationOptionsMessageRequestTypeDef",
     "UpdateConfigurationTemplateMessageRequestTypeDef",
     "UpdateEnvironmentMessageRequestTypeDef",
     "CreatePlatformVersionResultTypeDef",
     "DeletePlatformVersionResultTypeDef",
     "ListPlatformVersionsResultTypeDef",
-    "DescribeApplicationVersionsMessageDescribeApplicationVersionsPaginateTypeDef",
-    "DescribeEnvironmentManagedActionHistoryRequestDescribeEnvironmentManagedActionHistoryPaginateTypeDef",
-    "DescribeEnvironmentsMessageDescribeEnvironmentsPaginateTypeDef",
-    "DescribeEventsMessageDescribeEventsPaginateTypeDef",
     "DescribeEnvironmentManagedActionHistoryResultTypeDef",
     "DescribeEnvironmentManagedActionsResultTypeDef",
     "DescribeEnvironmentsMessageEnvironmentExistsWaitTypeDef",
     "DescribeEnvironmentsMessageEnvironmentTerminatedWaitTypeDef",
     "DescribeEnvironmentsMessageEnvironmentUpdatedWaitTypeDef",
     "RetrieveEnvironmentInfoResultMessageTypeDef",
     "EnvironmentResourceDescriptionTypeDef",
@@ -190,25 +190,14 @@
     {
         "EnvironmentId": str,
         "EnvironmentName": str,
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
 LatencyTypeDef = TypedDict(
     "LatencyTypeDef",
     {
         "P999": float,
         "P99": float,
         "P95": float,
         "P90": float,
@@ -302,14 +291,25 @@
 
 class ApplyEnvironmentManagedActionRequestRequestTypeDef(
     _RequiredApplyEnvironmentManagedActionRequestRequestTypeDef,
     _OptionalApplyEnvironmentManagedActionRequestRequestTypeDef,
 ):
     pass
 
+ApplyEnvironmentManagedActionResultTypeDef = TypedDict(
+    "ApplyEnvironmentManagedActionResultTypeDef",
+    {
+        "ActionId": str,
+        "ActionDescription": str,
+        "ActionType": ActionTypeType,
+        "Status": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 AssociateEnvironmentOperationsRoleMessageRequestTypeDef = TypedDict(
     "AssociateEnvironmentOperationsRoleMessageRequestTypeDef",
     {
         "EnvironmentName": str,
         "OperationsRole": str,
     },
 )
@@ -370,14 +370,23 @@
 CheckDNSAvailabilityMessageRequestTypeDef = TypedDict(
     "CheckDNSAvailabilityMessageRequestTypeDef",
     {
         "CNAMEPrefix": str,
     },
 )
 
+CheckDNSAvailabilityResultMessageTypeDef = TypedDict(
+    "CheckDNSAvailabilityResultMessageTypeDef",
+    {
+        "Available": bool,
+        "FullyQualifiedCNAME": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ComposeEnvironmentsMessageRequestTypeDef = TypedDict(
     "ComposeEnvironmentsMessageRequestTypeDef",
     {
         "ApplicationName": str,
         "GroupName": str,
         "VersionLabels": Sequence[str],
     },
@@ -468,14 +477,22 @@
         "PlatformVersion": str,
         "PlatformBranchName": str,
         "PlatformBranchLifecycleState": str,
     },
     total=False,
 )
 
+CreateStorageLocationResultMessageTypeDef = TypedDict(
+    "CreateStorageLocationResultMessageTypeDef",
+    {
+        "S3Bucket": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 CustomAmiTypeDef = TypedDict(
     "CustomAmiTypeDef",
     {
         "VirtualizationType": str,
         "ImageId": str,
     },
     total=False,
@@ -552,20 +569,20 @@
         "DeploymentId": int,
         "Status": str,
         "DeploymentTime": datetime,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeApplicationVersionsMessageDescribeApplicationVersionsPaginateTypeDef = TypedDict(
+    "DescribeApplicationVersionsMessageDescribeApplicationVersionsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "ApplicationName": str,
+        "VersionLabels": Sequence[str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeApplicationVersionsMessageRequestTypeDef = TypedDict(
     "DescribeApplicationVersionsMessageRequestTypeDef",
     {
@@ -627,14 +644,24 @@
         "Warning": int,
         "Degraded": int,
         "Severe": int,
     },
     total=False,
 )
 
+DescribeEnvironmentManagedActionHistoryRequestDescribeEnvironmentManagedActionHistoryPaginateTypeDef = TypedDict(
+    "DescribeEnvironmentManagedActionHistoryRequestDescribeEnvironmentManagedActionHistoryPaginateTypeDef",
+    {
+        "EnvironmentId": str,
+        "EnvironmentName": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeEnvironmentManagedActionHistoryRequestRequestTypeDef = TypedDict(
     "DescribeEnvironmentManagedActionHistoryRequestRequestTypeDef",
     {
         "EnvironmentId": str,
         "EnvironmentName": str,
         "NextToken": str,
         "MaxItems": int,
@@ -684,14 +711,28 @@
     {
         "EnvironmentId": str,
         "EnvironmentName": str,
     },
     total=False,
 )
 
+DescribeEnvironmentsMessageDescribeEnvironmentsPaginateTypeDef = TypedDict(
+    "DescribeEnvironmentsMessageDescribeEnvironmentsPaginateTypeDef",
+    {
+        "ApplicationName": str,
+        "VersionLabel": str,
+        "EnvironmentIds": Sequence[str],
+        "EnvironmentNames": Sequence[str],
+        "IncludeDeleted": bool,
+        "IncludedDeletedBackTo": Union[datetime, str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 WaiterConfigTypeDef = TypedDict(
     "WaiterConfigTypeDef",
     {
         "Delay": int,
         "MaxAttempts": int,
     },
     total=False,
@@ -708,14 +749,32 @@
         "IncludedDeletedBackTo": Union[datetime, str],
         "MaxRecords": int,
         "NextToken": str,
     },
     total=False,
 )
 
+DescribeEventsMessageDescribeEventsPaginateTypeDef = TypedDict(
+    "DescribeEventsMessageDescribeEventsPaginateTypeDef",
+    {
+        "ApplicationName": str,
+        "VersionLabel": str,
+        "TemplateName": str,
+        "EnvironmentId": str,
+        "EnvironmentName": str,
+        "PlatformArn": str,
+        "RequestId": str,
+        "Severity": EventSeverityType,
+        "StartTime": Union[datetime, str],
+        "EndTime": Union[datetime, str],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 DescribeEventsMessageRequestTypeDef = TypedDict(
     "DescribeEventsMessageRequestTypeDef",
     {
         "ApplicationName": str,
         "VersionLabel": str,
         "TemplateName": str,
         "EnvironmentId": str,
@@ -753,14 +812,21 @@
 DisassociateEnvironmentOperationsRoleMessageRequestTypeDef = TypedDict(
     "DisassociateEnvironmentOperationsRoleMessageRequestTypeDef",
     {
         "EnvironmentName": str,
     },
 )
 
+EmptyResponseMetadataTypeDef = TypedDict(
+    "EmptyResponseMetadataTypeDef",
+    {
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EnvironmentLinkTypeDef = TypedDict(
     "EnvironmentLinkTypeDef",
     {
         "LinkName": str,
         "EnvironmentName": str,
     },
     total=False,
@@ -895,14 +961,24 @@
     {
         "Protocol": str,
         "Port": int,
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
 PlatformFrameworkTypeDef = TypedDict(
     "PlatformFrameworkTypeDef",
     {
         "Name": str,
         "Version": str,
     },
     total=False,
@@ -951,14 +1027,25 @@
     "ResourceQuotaTypeDef",
     {
         "Maximum": int,
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
 RestartAppServerMessageRequestTypeDef = TypedDict(
     "RestartAppServerMessageRequestTypeDef",
     {
         "EnvironmentId": str,
         "EnvironmentName": str,
     },
     total=False,
@@ -1043,49 +1130,14 @@
 
 class UpdateApplicationVersionMessageRequestTypeDef(
     _RequiredUpdateApplicationVersionMessageRequestTypeDef,
     _OptionalUpdateApplicationVersionMessageRequestTypeDef,
 ):
     pass
 
-ApplyEnvironmentManagedActionResultTypeDef = TypedDict(
-    "ApplyEnvironmentManagedActionResultTypeDef",
-    {
-        "ActionId": str,
-        "ActionDescription": str,
-        "ActionType": ActionTypeType,
-        "Status": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CheckDNSAvailabilityResultMessageTypeDef = TypedDict(
-    "CheckDNSAvailabilityResultMessageTypeDef",
-    {
-        "Available": bool,
-        "FullyQualifiedCNAME": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateStorageLocationResultMessageTypeDef = TypedDict(
-    "CreateStorageLocationResultMessageTypeDef",
-    {
-        "S3Bucket": str,
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
 ApplicationMetricsTypeDef = TypedDict(
     "ApplicationMetricsTypeDef",
     {
         "Duration": int,
         "RequestCount": int,
         "StatusCodes": StatusCodesTypeDef,
         "Latency": LatencyTypeDef,
@@ -1155,15 +1207,15 @@
         "TemplateName": str,
         "Description": str,
         "EnvironmentName": str,
         "DeploymentStatus": ConfigurationDeploymentStatusType,
         "DateCreated": datetime,
         "DateUpdated": datetime,
         "OptionSettings": List[ConfigurationOptionSettingTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ConfigurationSettingsDescriptionTypeDef = TypedDict(
     "ConfigurationSettingsDescriptionTypeDef",
     {
         "SolutionStackName": str,
@@ -1202,15 +1254,15 @@
 ):
     pass
 
 ConfigurationSettingsValidationMessagesTypeDef = TypedDict(
     "ConfigurationSettingsValidationMessagesTypeDef",
     {
         "Messages": List[ValidationMessageTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateApplicationVersionMessageRequestTypeDef = TypedDict(
     "_RequiredCreateApplicationVersionMessageRequestTypeDef",
     {
         "ApplicationName": str,
@@ -1262,15 +1314,15 @@
     pass
 
 ResourceTagsDescriptionMessageTypeDef = TypedDict(
     "ResourceTagsDescriptionMessageTypeDef",
     {
         "ResourceArn": str,
         "ResourceTags": List[TagTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateTagsForResourceMessageRequestTypeDef = TypedDict(
     "_RequiredUpdateTagsForResourceMessageRequestTypeDef",
     {
         "ResourceArn": str,
@@ -1405,101 +1457,49 @@
 )
 
 CreatePlatformVersionResultTypeDef = TypedDict(
     "CreatePlatformVersionResultTypeDef",
     {
         "PlatformSummary": PlatformSummaryTypeDef,
         "Builder": BuilderTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeletePlatformVersionResultTypeDef = TypedDict(
     "DeletePlatformVersionResultTypeDef",
     {
         "PlatformSummary": PlatformSummaryTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPlatformVersionsResultTypeDef = TypedDict(
     "ListPlatformVersionsResultTypeDef",
     {
         "PlatformSummaryList": List[PlatformSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeApplicationVersionsMessageDescribeApplicationVersionsPaginateTypeDef = TypedDict(
-    "DescribeApplicationVersionsMessageDescribeApplicationVersionsPaginateTypeDef",
-    {
-        "ApplicationName": str,
-        "VersionLabels": Sequence[str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeEnvironmentManagedActionHistoryRequestDescribeEnvironmentManagedActionHistoryPaginateTypeDef = TypedDict(
-    "DescribeEnvironmentManagedActionHistoryRequestDescribeEnvironmentManagedActionHistoryPaginateTypeDef",
-    {
-        "EnvironmentId": str,
-        "EnvironmentName": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeEnvironmentsMessageDescribeEnvironmentsPaginateTypeDef = TypedDict(
-    "DescribeEnvironmentsMessageDescribeEnvironmentsPaginateTypeDef",
-    {
-        "ApplicationName": str,
-        "VersionLabel": str,
-        "EnvironmentIds": Sequence[str],
-        "EnvironmentNames": Sequence[str],
-        "IncludeDeleted": bool,
-        "IncludedDeletedBackTo": Union[datetime, str],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-DescribeEventsMessageDescribeEventsPaginateTypeDef = TypedDict(
-    "DescribeEventsMessageDescribeEventsPaginateTypeDef",
-    {
-        "ApplicationName": str,
-        "VersionLabel": str,
-        "TemplateName": str,
-        "EnvironmentId": str,
-        "EnvironmentName": str,
-        "PlatformArn": str,
-        "RequestId": str,
-        "Severity": EventSeverityType,
-        "StartTime": Union[datetime, str],
-        "EndTime": Union[datetime, str],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
 DescribeEnvironmentManagedActionHistoryResultTypeDef = TypedDict(
     "DescribeEnvironmentManagedActionHistoryResultTypeDef",
     {
         "ManagedActionHistoryItems": List[ManagedActionHistoryItemTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEnvironmentManagedActionsResultTypeDef = TypedDict(
     "DescribeEnvironmentManagedActionsResultTypeDef",
     {
         "ManagedActions": List[ManagedActionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeEnvironmentsMessageEnvironmentExistsWaitTypeDef = TypedDict(
     "DescribeEnvironmentsMessageEnvironmentExistsWaitTypeDef",
     {
         "ApplicationName": str,
@@ -1547,15 +1547,15 @@
     total=False,
 )
 
 RetrieveEnvironmentInfoResultMessageTypeDef = TypedDict(
     "RetrieveEnvironmentInfoResultMessageTypeDef",
     {
         "EnvironmentInfo": List[EnvironmentInfoDescriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EnvironmentResourceDescriptionTypeDef = TypedDict(
     "EnvironmentResourceDescriptionTypeDef",
     {
         "EnvironmentName": str,
@@ -1571,24 +1571,24 @@
 )
 
 EventDescriptionsMessageTypeDef = TypedDict(
     "EventDescriptionsMessageTypeDef",
     {
         "Events": List[EventDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListAvailableSolutionStacksResultMessageTypeDef = TypedDict(
     "ListAvailableSolutionStacksResultMessageTypeDef",
     {
         "SolutionStacks": List[str],
         "SolutionStackDetails": List[SolutionStackDescriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPlatformBranchesRequestRequestTypeDef = TypedDict(
     "ListPlatformBranchesRequestRequestTypeDef",
     {
         "Filters": Sequence[SearchFilterTypeDef],
@@ -1599,23 +1599,23 @@
 )
 
 ListPlatformBranchesResultTypeDef = TypedDict(
     "ListPlatformBranchesResultTypeDef",
     {
         "PlatformBranchSummaryList": List[PlatformBranchSummaryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPlatformVersionsRequestListPlatformVersionsPaginateTypeDef = TypedDict(
     "ListPlatformVersionsRequestListPlatformVersionsPaginateTypeDef",
     {
         "Filters": Sequence[PlatformFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 ListPlatformVersionsRequestRequestTypeDef = TypedDict(
     "ListPlatformVersionsRequestRequestTypeDef",
     {
@@ -1683,32 +1683,32 @@
         "HealthStatus": str,
         "Status": EnvironmentHealthType,
         "Color": str,
         "Causes": List[str],
         "ApplicationMetrics": ApplicationMetricsTypeDef,
         "InstancesHealth": InstanceHealthSummaryTypeDef,
         "RefreshedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ApplicationVersionDescriptionMessageTypeDef = TypedDict(
     "ApplicationVersionDescriptionMessageTypeDef",
     {
         "ApplicationVersion": ApplicationVersionDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ApplicationVersionDescriptionsMessageTypeDef = TypedDict(
     "ApplicationVersionDescriptionsMessageTypeDef",
     {
         "ApplicationVersions": List[ApplicationVersionDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ApplicationResourceLifecycleConfigTypeDef = TypedDict(
     "ApplicationResourceLifecycleConfigTypeDef",
     {
         "ServiceRole": str,
@@ -1736,31 +1736,31 @@
 
 ConfigurationOptionsDescriptionTypeDef = TypedDict(
     "ConfigurationOptionsDescriptionTypeDef",
     {
         "SolutionStackName": str,
         "PlatformArn": str,
         "Options": List[ConfigurationOptionDescriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ConfigurationSettingsDescriptionsTypeDef = TypedDict(
     "ConfigurationSettingsDescriptionsTypeDef",
     {
         "ConfigurationSettings": List[ConfigurationSettingsDescriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EnvironmentResourceDescriptionsMessageTypeDef = TypedDict(
     "EnvironmentResourceDescriptionsMessageTypeDef",
     {
         "EnvironmentResources": EnvironmentResourceDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EnvironmentResourcesDescriptionTypeDef = TypedDict(
     "EnvironmentResourcesDescriptionTypeDef",
     {
         "LoadBalancer": LoadBalancerDescriptionTypeDef,
@@ -1768,23 +1768,23 @@
     total=False,
 )
 
 DescribePlatformVersionResultTypeDef = TypedDict(
     "DescribePlatformVersionResultTypeDef",
     {
         "PlatformDescription": PlatformDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAccountAttributesResultTypeDef = TypedDict(
     "DescribeAccountAttributesResultTypeDef",
     {
         "ResourceQuotas": ResourceQuotasTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ApplicationDescriptionTypeDef = TypedDict(
     "ApplicationDescriptionTypeDef",
     {
         "ApplicationArn": str,
@@ -1800,15 +1800,15 @@
 )
 
 ApplicationResourceLifecycleDescriptionMessageTypeDef = TypedDict(
     "ApplicationResourceLifecycleDescriptionMessageTypeDef",
     {
         "ApplicationName": str,
         "ResourceLifecycleConfig": ApplicationResourceLifecycleConfigTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateApplicationMessageRequestTypeDef = TypedDict(
     "_RequiredCreateApplicationMessageRequestTypeDef",
     {
         "ApplicationName": str,
@@ -1839,15 +1839,15 @@
 
 DescribeInstancesHealthResultTypeDef = TypedDict(
     "DescribeInstancesHealthResultTypeDef",
     {
         "InstanceHealthList": List[SingleInstanceHealthTypeDef],
         "RefreshedAt": datetime,
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EnvironmentDescriptionResponseMetadataTypeDef = TypedDict(
     "EnvironmentDescriptionResponseMetadataTypeDef",
     {
         "EnvironmentName": str,
@@ -1867,15 +1867,15 @@
         "Health": EnvironmentHealthType,
         "HealthStatus": EnvironmentHealthStatusType,
         "Resources": EnvironmentResourcesDescriptionTypeDef,
         "Tier": EnvironmentTierTypeDef,
         "EnvironmentLinks": List[EnvironmentLinkTypeDef],
         "EnvironmentArn": str,
         "OperationsRole": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EnvironmentDescriptionTypeDef = TypedDict(
     "EnvironmentDescriptionTypeDef",
     {
         "EnvironmentName": str,
@@ -1903,27 +1903,27 @@
     total=False,
 )
 
 ApplicationDescriptionMessageTypeDef = TypedDict(
     "ApplicationDescriptionMessageTypeDef",
     {
         "Application": ApplicationDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ApplicationDescriptionsMessageTypeDef = TypedDict(
     "ApplicationDescriptionsMessageTypeDef",
     {
         "Applications": List[ApplicationDescriptionTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 EnvironmentDescriptionsMessageTypeDef = TypedDict(
     "EnvironmentDescriptionsMessageTypeDef",
     {
         "Environments": List[EnvironmentDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-elasticbeanstalk-2.5.0.post1/types_aiobotocore_elasticbeanstalk/waiter.py` & `types-aiobotocore-elasticbeanstalk-2.5.1/types_aiobotocore_elasticbeanstalk/waiter.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-elasticbeanstalk-2.5.0.post1/types_aiobotocore_elasticbeanstalk/waiter.pyi` & `types-aiobotocore-elasticbeanstalk-2.5.1/types_aiobotocore_elasticbeanstalk/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-elasticbeanstalk-2.5.0.post1/types_aiobotocore_elasticbeanstalk.egg-info/PKG-INFO` & `types-aiobotocore-elasticbeanstalk-2.5.1/types_aiobotocore_elasticbeanstalk.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-elasticbeanstalk
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.ElasticBeanstalk 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.ElasticBeanstalk 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticbeanstalk/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-elasticbeanstalk"></a>
 
 # types-aiobotocore-elasticbeanstalk
 
 [![PyPI - types-aiobotocore-elasticbeanstalk](https://img.shields.io/pypi/v/types-aiobotocore-elasticbeanstalk.svg?color=blue)](https://pypi.org/project/types-aiobotocore-elasticbeanstalk)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-elasticbeanstalk.svg?color=blue)](https://pypi.org/project/types-aiobotocore-elasticbeanstalk)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticbeanstalk/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-elasticbeanstalk?color=blue)](https://pypistats.org/packages/types-aiobotocore-elasticbeanstalk)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.ElasticBeanstalk 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk)
+[aiobotocore.ElasticBeanstalk 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/elasticbeanstalk.html#ElasticBeanstalk)
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
 [types-aiobotocore-elasticbeanstalk docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_elasticbeanstalk/).
 
 See how it helps to find and fix potential bugs:
 
@@ -391,61 +391,67 @@
 
 `types_aiobotocore_elasticbeanstalk.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_elasticbeanstalk.type_defs import (
     AbortEnvironmentUpdateMessageRequestTypeDef,
-    ResponseMetadataTypeDef,
     LatencyTypeDef,
     StatusCodesTypeDef,
     S3LocationTypeDef,
     SourceBuildInformationTypeDef,
     MaxAgeRuleTypeDef,
     MaxCountRuleTypeDef,
     ApplyEnvironmentManagedActionRequestRequestTypeDef,
+    ApplyEnvironmentManagedActionResultTypeDef,
     AssociateEnvironmentOperationsRoleMessageRequestTypeDef,
     AutoScalingGroupTypeDef,
     BuildConfigurationTypeDef,
     BuilderTypeDef,
     CPUUtilizationTypeDef,
     CheckDNSAvailabilityMessageRequestTypeDef,
+    CheckDNSAvailabilityResultMessageTypeDef,
     ComposeEnvironmentsMessageRequestTypeDef,
     OptionRestrictionRegexTypeDef,
     ConfigurationOptionSettingTypeDef,
     ValidationMessageTypeDef,
     TagTypeDef,
     SourceConfigurationTypeDef,
     EnvironmentTierTypeDef,
     OptionSpecificationTypeDef,
     PlatformSummaryTypeDef,
+    CreateStorageLocationResultMessageTypeDef,
     CustomAmiTypeDef,
     DeleteApplicationMessageRequestTypeDef,
     DeleteApplicationVersionMessageRequestTypeDef,
     DeleteConfigurationTemplateMessageRequestTypeDef,
     DeleteEnvironmentConfigurationMessageRequestTypeDef,
     DeletePlatformVersionRequestRequestTypeDef,
     DeploymentTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeApplicationVersionsMessageDescribeApplicationVersionsPaginateTypeDef,
     DescribeApplicationVersionsMessageRequestTypeDef,
     DescribeApplicationsMessageRequestTypeDef,
     DescribeConfigurationSettingsMessageRequestTypeDef,
     DescribeEnvironmentHealthRequestRequestTypeDef,
     InstanceHealthSummaryTypeDef,
+    DescribeEnvironmentManagedActionHistoryRequestDescribeEnvironmentManagedActionHistoryPaginateTypeDef,
     DescribeEnvironmentManagedActionHistoryRequestRequestTypeDef,
     ManagedActionHistoryItemTypeDef,
     DescribeEnvironmentManagedActionsRequestRequestTypeDef,
     ManagedActionTypeDef,
     DescribeEnvironmentResourcesMessageRequestTypeDef,
+    DescribeEnvironmentsMessageDescribeEnvironmentsPaginateTypeDef,
     WaiterConfigTypeDef,
     DescribeEnvironmentsMessageRequestTypeDef,
+    DescribeEventsMessageDescribeEventsPaginateTypeDef,
     DescribeEventsMessageRequestTypeDef,
     DescribeInstancesHealthRequestRequestTypeDef,
     DescribePlatformVersionRequestRequestTypeDef,
     DisassociateEnvironmentOperationsRoleMessageRequestTypeDef,
+    EmptyResponseMetadataTypeDef,
     EnvironmentLinkTypeDef,
     EnvironmentInfoDescriptionTypeDef,
     InstanceTypeDef,
     LaunchConfigurationTypeDef,
     LaunchTemplateTypeDef,
     LoadBalancerTypeDef,
     QueueTypeDef,
@@ -453,29 +459,27 @@
     EventDescriptionTypeDef,
     SolutionStackDescriptionTypeDef,
     SearchFilterTypeDef,
     PlatformBranchSummaryTypeDef,
     PlatformFilterTypeDef,
     ListTagsForResourceMessageRequestTypeDef,
     ListenerTypeDef,
+    PaginatorConfigTypeDef,
     PlatformFrameworkTypeDef,
     PlatformProgrammingLanguageTypeDef,
     RebuildEnvironmentMessageRequestTypeDef,
     RequestEnvironmentInfoMessageRequestTypeDef,
     ResourceQuotaTypeDef,
+    ResponseMetadataTypeDef,
     RestartAppServerMessageRequestTypeDef,
     RetrieveEnvironmentInfoMessageRequestTypeDef,
     SwapEnvironmentCNAMEsMessageRequestTypeDef,
     TerminateEnvironmentMessageRequestTypeDef,
     UpdateApplicationMessageRequestTypeDef,
     UpdateApplicationVersionMessageRequestTypeDef,
-    ApplyEnvironmentManagedActionResultTypeDef,
-    CheckDNSAvailabilityResultMessageTypeDef,
-    CreateStorageLocationResultMessageTypeDef,
-    EmptyResponseMetadataTypeDef,
     ApplicationMetricsTypeDef,
     ApplicationVersionDescriptionTypeDef,
     ApplicationVersionLifecycleConfigTypeDef,
     SystemStatusTypeDef,
     ConfigurationOptionDescriptionTypeDef,
     ConfigurationSettingsDescriptionResponseMetadataTypeDef,
     ConfigurationSettingsDescriptionTypeDef,
@@ -489,18 +493,14 @@
     CreateEnvironmentMessageRequestTypeDef,
     DescribeConfigurationOptionsMessageRequestTypeDef,
     UpdateConfigurationTemplateMessageRequestTypeDef,
     UpdateEnvironmentMessageRequestTypeDef,
     CreatePlatformVersionResultTypeDef,
     DeletePlatformVersionResultTypeDef,
     ListPlatformVersionsResultTypeDef,
-    DescribeApplicationVersionsMessageDescribeApplicationVersionsPaginateTypeDef,
-    DescribeEnvironmentManagedActionHistoryRequestDescribeEnvironmentManagedActionHistoryPaginateTypeDef,
-    DescribeEnvironmentsMessageDescribeEnvironmentsPaginateTypeDef,
-    DescribeEventsMessageDescribeEventsPaginateTypeDef,
     DescribeEnvironmentManagedActionHistoryResultTypeDef,
     DescribeEnvironmentManagedActionsResultTypeDef,
     DescribeEnvironmentsMessageEnvironmentExistsWaitTypeDef,
     DescribeEnvironmentsMessageEnvironmentTerminatedWaitTypeDef,
     DescribeEnvironmentsMessageEnvironmentUpdatedWaitTypeDef,
     RetrieveEnvironmentInfoResultMessageTypeDef,
     EnvironmentResourceDescriptionTypeDef,
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

### Comparing `types-aiobotocore-elasticbeanstalk-2.5.0.post1/types_aiobotocore_elasticbeanstalk.egg-info/SOURCES.txt` & `types-aiobotocore-elasticbeanstalk-2.5.1/types_aiobotocore_elasticbeanstalk.egg-info/SOURCES.txt`

 * *Files identical despite different names*

