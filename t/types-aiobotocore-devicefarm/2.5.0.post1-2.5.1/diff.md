# Comparing `tmp/types-aiobotocore-devicefarm-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-devicefarm-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-devicefarm-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:29 2023, max compression
+gzip compressed data, was "types-aiobotocore-devicefarm-2.5.1.tar", last modified: Wed Jun 28 01:43:22 2023, max compression
```

## Comparing `types-aiobotocore-devicefarm-2.5.0.post1.tar` & `types-aiobotocore-devicefarm-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:29.751123 types-aiobotocore-devicefarm-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:12:19.000000 types-aiobotocore-devicefarm-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    25187 2023-03-11 12:26:29.751123 types-aiobotocore-devicefarm-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    23604 2023-03-11 12:12:19.000000 types-aiobotocore-devicefarm-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:29.751123 types-aiobotocore-devicefarm-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2145 2023-03-11 12:12:19.000000 types-aiobotocore-devicefarm-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:29.747123 types-aiobotocore-devicefarm-2.5.0.post1/types_aiobotocore_devicefarm/
--rw-r--r--   0 runner    (1001) docker     (123)     4483 2023-03-11 12:12:19.000000 types-aiobotocore-devicefarm-2.5.0.post1/types_aiobotocore_devicefarm/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4482 2023-03-11 12:12:19.000000 types-aiobotocore-devicefarm-2.5.0.post1/types_aiobotocore_devicefarm/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      955 2023-03-11 12:12:19.000000 types-aiobotocore-devicefarm-2.5.0.post1/types_aiobotocore_devicefarm/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    60984 2023-03-11 12:12:20.000000 types-aiobotocore-devicefarm-2.5.0.post1/types_aiobotocore_devicefarm/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    60878 2023-03-11 12:12:20.000000 types-aiobotocore-devicefarm-2.5.0.post1/types_aiobotocore_devicefarm/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    15510 2023-03-11 12:12:20.000000 types-aiobotocore-devicefarm-2.5.0.post1/types_aiobotocore_devicefarm/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    15508 2023-03-11 12:12:20.000000 types-aiobotocore-devicefarm-2.5.0.post1/types_aiobotocore_devicefarm/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    23486 2023-03-11 12:12:20.000000 types-aiobotocore-devicefarm-2.5.0.post1/types_aiobotocore_devicefarm/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)    23463 2023-03-11 12:12:20.000000 types-aiobotocore-devicefarm-2.5.0.post1/types_aiobotocore_devicefarm/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:12:19.000000 types-aiobotocore-devicefarm-2.5.0.post1/types_aiobotocore_devicefarm/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    73098 2023-03-11 12:12:23.000000 types-aiobotocore-devicefarm-2.5.0.post1/types_aiobotocore_devicefarm/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    73007 2023-03-11 12:12:22.000000 types-aiobotocore-devicefarm-2.5.0.post1/types_aiobotocore_devicefarm/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:12:19.000000 types-aiobotocore-devicefarm-2.5.0.post1/types_aiobotocore_devicefarm/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:29.751123 types-aiobotocore-devicefarm-2.5.0.post1/types_aiobotocore_devicefarm.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    25187 2023-03-11 12:26:29.000000 types-aiobotocore-devicefarm-2.5.0.post1/types_aiobotocore_devicefarm.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      870 2023-03-11 12:26:29.000000 types-aiobotocore-devicefarm-2.5.0.post1/types_aiobotocore_devicefarm.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:29.000000 types-aiobotocore-devicefarm-2.5.0.post1/types_aiobotocore_devicefarm.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:29.000000 types-aiobotocore-devicefarm-2.5.0.post1/types_aiobotocore_devicefarm.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:29.000000 types-aiobotocore-devicefarm-2.5.0.post1/types_aiobotocore_devicefarm.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       29 2023-03-11 12:26:29.000000 types-aiobotocore-devicefarm-2.5.0.post1/types_aiobotocore_devicefarm.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:22.518123 types-aiobotocore-devicefarm-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:28:59.000000 types-aiobotocore-devicefarm-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    25182 2023-06-28 01:43:22.514123 types-aiobotocore-devicefarm-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    23605 2023-06-28 01:28:59.000000 types-aiobotocore-devicefarm-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:22.518123 types-aiobotocore-devicefarm-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2139 2023-06-28 01:28:58.000000 types-aiobotocore-devicefarm-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:22.514123 types-aiobotocore-devicefarm-2.5.1/types_aiobotocore_devicefarm/
+-rw-r--r--   0 runner    (1001) docker     (123)     4483 2023-06-28 01:28:59.000000 types-aiobotocore-devicefarm-2.5.1/types_aiobotocore_devicefarm/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4482 2023-06-28 01:28:59.000000 types-aiobotocore-devicefarm-2.5.1/types_aiobotocore_devicefarm/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      943 2023-06-28 01:28:59.000000 types-aiobotocore-devicefarm-2.5.1/types_aiobotocore_devicefarm/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    60984 2023-06-28 01:29:00.000000 types-aiobotocore-devicefarm-2.5.1/types_aiobotocore_devicefarm/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    60878 2023-06-28 01:29:00.000000 types-aiobotocore-devicefarm-2.5.1/types_aiobotocore_devicefarm/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    15719 2023-06-28 01:29:00.000000 types-aiobotocore-devicefarm-2.5.1/types_aiobotocore_devicefarm/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15717 2023-06-28 01:29:00.000000 types-aiobotocore-devicefarm-2.5.1/types_aiobotocore_devicefarm/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    23406 2023-06-28 01:29:00.000000 types-aiobotocore-devicefarm-2.5.1/types_aiobotocore_devicefarm/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23384 2023-06-28 01:29:00.000000 types-aiobotocore-devicefarm-2.5.1/types_aiobotocore_devicefarm/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:28:59.000000 types-aiobotocore-devicefarm-2.5.1/types_aiobotocore_devicefarm/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    73270 2023-06-28 01:29:02.000000 types-aiobotocore-devicefarm-2.5.1/types_aiobotocore_devicefarm/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    73179 2023-06-28 01:29:01.000000 types-aiobotocore-devicefarm-2.5.1/types_aiobotocore_devicefarm/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:28:59.000000 types-aiobotocore-devicefarm-2.5.1/types_aiobotocore_devicefarm/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:22.514123 types-aiobotocore-devicefarm-2.5.1/types_aiobotocore_devicefarm.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    25182 2023-06-28 01:43:22.000000 types-aiobotocore-devicefarm-2.5.1/types_aiobotocore_devicefarm.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      870 2023-06-28 01:43:22.000000 types-aiobotocore-devicefarm-2.5.1/types_aiobotocore_devicefarm.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:22.000000 types-aiobotocore-devicefarm-2.5.1/types_aiobotocore_devicefarm.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:22.000000 types-aiobotocore-devicefarm-2.5.1/types_aiobotocore_devicefarm.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:22.000000 types-aiobotocore-devicefarm-2.5.1/types_aiobotocore_devicefarm.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       29 2023-06-28 01:43:22.000000 types-aiobotocore-devicefarm-2.5.1/types_aiobotocore_devicefarm.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-devicefarm-2.5.0.post1/LICENSE` & `types-aiobotocore-devicefarm-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-devicefarm-2.5.0.post1/PKG-INFO` & `types-aiobotocore-devicefarm-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-devicefarm
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.DeviceFarm 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.DeviceFarm 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-devicefarm"></a>
 
 # types-aiobotocore-devicefarm
 
 [![PyPI - types-aiobotocore-devicefarm](https://img.shields.io/pypi/v/types-aiobotocore-devicefarm.svg?color=blue)](https://pypi.org/project/types-aiobotocore-devicefarm)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-devicefarm.svg?color=blue)](https://pypi.org/project/types-aiobotocore-devicefarm)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-devicefarm?color=blue)](https://pypistats.org/packages/types-aiobotocore-devicefarm)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.DeviceFarm 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm)
+[aiobotocore.DeviceFarm 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm)
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
 [types-aiobotocore-devicefarm docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/).
 
 See how it helps to find and fix potential bugs:
 
@@ -426,23 +426,23 @@
 ```python
 from types_aiobotocore_devicefarm.type_defs import (
     TrialMinutesTypeDef,
     ArtifactTypeDef,
     CPUTypeDef,
     CountersTypeDef,
     RuleTypeDef,
-    ResponseMetadataTypeDef,
     CreateInstanceProfileRequestRequestTypeDef,
     InstanceProfileTypeDef,
     CreateNetworkProfileRequestRequestTypeDef,
     NetworkProfileTypeDef,
     VpcConfigTypeDef,
     CreateRemoteAccessSessionConfigurationTypeDef,
     TestGridVpcConfigTypeDef,
     CreateTestGridUrlRequestRequestTypeDef,
+    CreateTestGridUrlResultTypeDef,
     CreateUploadRequestRequestTypeDef,
     UploadTypeDef,
     CreateVPCEConfigurationRequestRequestTypeDef,
     VPCEConfigurationTypeDef,
     CustomerArtifactPathsTypeDef,
     DeleteDevicePoolRequestRequestTypeDef,
     DeleteInstanceProfileRequestRequestTypeDef,
@@ -461,76 +461,95 @@
     GetDeviceInstanceRequestRequestTypeDef,
     ScheduleRunTestTypeDef,
     GetDevicePoolRequestRequestTypeDef,
     GetDeviceRequestRequestTypeDef,
     GetInstanceProfileRequestRequestTypeDef,
     GetJobRequestRequestTypeDef,
     GetNetworkProfileRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetOfferingStatusRequestGetOfferingStatusPaginateTypeDef,
     GetOfferingStatusRequestRequestTypeDef,
     GetProjectRequestRequestTypeDef,
     GetRemoteAccessSessionRequestRequestTypeDef,
     GetRunRequestRequestTypeDef,
     GetSuiteRequestRequestTypeDef,
     GetTestGridProjectRequestRequestTypeDef,
     GetTestGridSessionRequestRequestTypeDef,
     TestGridSessionTypeDef,
     GetTestRequestRequestTypeDef,
     GetUploadRequestRequestTypeDef,
     GetVPCEConfigurationRequestRequestTypeDef,
     InstallToRemoteAccessSessionRequestRequestTypeDef,
+    ListArtifactsRequestListArtifactsPaginateTypeDef,
     ListArtifactsRequestRequestTypeDef,
+    ListDeviceInstancesRequestListDeviceInstancesPaginateTypeDef,
     ListDeviceInstancesRequestRequestTypeDef,
+    ListDevicePoolsRequestListDevicePoolsPaginateTypeDef,
     ListDevicePoolsRequestRequestTypeDef,
+    ListInstanceProfilesRequestListInstanceProfilesPaginateTypeDef,
     ListInstanceProfilesRequestRequestTypeDef,
+    ListJobsRequestListJobsPaginateTypeDef,
     ListJobsRequestRequestTypeDef,
+    ListNetworkProfilesRequestListNetworkProfilesPaginateTypeDef,
     ListNetworkProfilesRequestRequestTypeDef,
+    ListOfferingPromotionsRequestListOfferingPromotionsPaginateTypeDef,
     ListOfferingPromotionsRequestRequestTypeDef,
     OfferingPromotionTypeDef,
+    ListOfferingTransactionsRequestListOfferingTransactionsPaginateTypeDef,
     ListOfferingTransactionsRequestRequestTypeDef,
+    ListOfferingsRequestListOfferingsPaginateTypeDef,
     ListOfferingsRequestRequestTypeDef,
+    ListProjectsRequestListProjectsPaginateTypeDef,
     ListProjectsRequestRequestTypeDef,
+    ListRemoteAccessSessionsRequestListRemoteAccessSessionsPaginateTypeDef,
     ListRemoteAccessSessionsRequestRequestTypeDef,
+    ListRunsRequestListRunsPaginateTypeDef,
     ListRunsRequestRequestTypeDef,
+    ListSamplesRequestListSamplesPaginateTypeDef,
     ListSamplesRequestRequestTypeDef,
     SampleTypeDef,
+    ListSuitesRequestListSuitesPaginateTypeDef,
     ListSuitesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     TagTypeDef,
     ListTestGridProjectsRequestRequestTypeDef,
     ListTestGridSessionActionsRequestRequestTypeDef,
     TestGridSessionActionTypeDef,
     ListTestGridSessionArtifactsRequestRequestTypeDef,
     TestGridSessionArtifactTypeDef,
     ListTestGridSessionsRequestRequestTypeDef,
+    ListTestsRequestListTestsPaginateTypeDef,
     ListTestsRequestRequestTypeDef,
+    ListUniqueProblemsRequestListUniqueProblemsPaginateTypeDef,
     ListUniqueProblemsRequestRequestTypeDef,
+    ListUploadsRequestListUploadsPaginateTypeDef,
     ListUploadsRequestRequestTypeDef,
+    ListVPCEConfigurationsRequestListVPCEConfigurationsPaginateTypeDef,
     ListVPCEConfigurationsRequestRequestTypeDef,
     LocationTypeDef,
     MonetaryAmountTypeDef,
+    PaginatorConfigTypeDef,
     ProblemDetailTypeDef,
     PurchaseOfferingRequestRequestTypeDef,
     RadiosTypeDef,
     RenewOfferingRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     StopJobRequestRequestTypeDef,
     StopRemoteAccessSessionRequestRequestTypeDef,
     StopRunRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateDeviceInstanceRequestRequestTypeDef,
     UpdateInstanceProfileRequestRequestTypeDef,
     UpdateNetworkProfileRequestRequestTypeDef,
     UpdateUploadRequestRequestTypeDef,
     UpdateVPCEConfigurationRequestRequestTypeDef,
     AccountSettingsTypeDef,
+    ListArtifactsResultTypeDef,
     CreateDevicePoolRequestRequestTypeDef,
     DevicePoolTypeDef,
     UpdateDevicePoolRequestRequestTypeDef,
-    CreateTestGridUrlResultTypeDef,
-    ListArtifactsResultTypeDef,
     CreateInstanceProfileResultTypeDef,
     DeviceInstanceTypeDef,
     GetInstanceProfileResultTypeDef,
     ListInstanceProfilesResultTypeDef,
     UpdateInstanceProfileResultTypeDef,
     CreateNetworkProfileResultTypeDef,
     GetNetworkProfileResultTypeDef,
@@ -550,37 +569,18 @@
     UpdateUploadResultTypeDef,
     CreateVPCEConfigurationResultTypeDef,
     GetVPCEConfigurationResultTypeDef,
     ListVPCEConfigurationsResultTypeDef,
     UpdateVPCEConfigurationResultTypeDef,
     DeviceSelectionConfigurationTypeDef,
     DeviceSelectionResultTypeDef,
+    ListDevicesRequestListDevicesPaginateTypeDef,
     ListDevicesRequestRequestTypeDef,
     SuiteTypeDef,
     TestTypeDef,
-    GetOfferingStatusRequestGetOfferingStatusPaginateTypeDef,
-    ListArtifactsRequestListArtifactsPaginateTypeDef,
-    ListDeviceInstancesRequestListDeviceInstancesPaginateTypeDef,
-    ListDevicePoolsRequestListDevicePoolsPaginateTypeDef,
-    ListDevicesRequestListDevicesPaginateTypeDef,
-    ListInstanceProfilesRequestListInstanceProfilesPaginateTypeDef,
-    ListJobsRequestListJobsPaginateTypeDef,
-    ListNetworkProfilesRequestListNetworkProfilesPaginateTypeDef,
-    ListOfferingPromotionsRequestListOfferingPromotionsPaginateTypeDef,
-    ListOfferingTransactionsRequestListOfferingTransactionsPaginateTypeDef,
-    ListOfferingsRequestListOfferingsPaginateTypeDef,
-    ListProjectsRequestListProjectsPaginateTypeDef,
-    ListRemoteAccessSessionsRequestListRemoteAccessSessionsPaginateTypeDef,
-    ListRunsRequestListRunsPaginateTypeDef,
-    ListSamplesRequestListSamplesPaginateTypeDef,
-    ListSuitesRequestListSuitesPaginateTypeDef,
-    ListTestsRequestListTestsPaginateTypeDef,
-    ListUniqueProblemsRequestListUniqueProblemsPaginateTypeDef,
-    ListUploadsRequestListUploadsPaginateTypeDef,
-    ListVPCEConfigurationsRequestListVPCEConfigurationsPaginateTypeDef,
     GetTestGridSessionResultTypeDef,
     ListTestGridSessionsResultTypeDef,
     ListOfferingPromotionsResultTypeDef,
     ListSamplesResultTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     ListTestGridSessionActionsResultTypeDef,
@@ -649,43 +649,43 @@
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

### Comparing `types-aiobotocore-devicefarm-2.5.0.post1/README.md` & `types-aiobotocore-devicefarm-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-devicefarm"></a>
 
 # types-aiobotocore-devicefarm
 
 [![PyPI - types-aiobotocore-devicefarm](https://img.shields.io/pypi/v/types-aiobotocore-devicefarm.svg?color=blue)](https://pypi.org/project/types-aiobotocore-devicefarm)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-devicefarm.svg?color=blue)](https://pypi.org/project/types-aiobotocore-devicefarm)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-devicefarm?color=blue)](https://pypistats.org/packages/types-aiobotocore-devicefarm)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.DeviceFarm 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm)
+[aiobotocore.DeviceFarm 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm)
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
 [types-aiobotocore-devicefarm docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/).
 
 See how it helps to find and fix potential bugs:
 
@@ -393,23 +393,23 @@
 ```python
 from types_aiobotocore_devicefarm.type_defs import (
     TrialMinutesTypeDef,
     ArtifactTypeDef,
     CPUTypeDef,
     CountersTypeDef,
     RuleTypeDef,
-    ResponseMetadataTypeDef,
     CreateInstanceProfileRequestRequestTypeDef,
     InstanceProfileTypeDef,
     CreateNetworkProfileRequestRequestTypeDef,
     NetworkProfileTypeDef,
     VpcConfigTypeDef,
     CreateRemoteAccessSessionConfigurationTypeDef,
     TestGridVpcConfigTypeDef,
     CreateTestGridUrlRequestRequestTypeDef,
+    CreateTestGridUrlResultTypeDef,
     CreateUploadRequestRequestTypeDef,
     UploadTypeDef,
     CreateVPCEConfigurationRequestRequestTypeDef,
     VPCEConfigurationTypeDef,
     CustomerArtifactPathsTypeDef,
     DeleteDevicePoolRequestRequestTypeDef,
     DeleteInstanceProfileRequestRequestTypeDef,
@@ -428,76 +428,95 @@
     GetDeviceInstanceRequestRequestTypeDef,
     ScheduleRunTestTypeDef,
     GetDevicePoolRequestRequestTypeDef,
     GetDeviceRequestRequestTypeDef,
     GetInstanceProfileRequestRequestTypeDef,
     GetJobRequestRequestTypeDef,
     GetNetworkProfileRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetOfferingStatusRequestGetOfferingStatusPaginateTypeDef,
     GetOfferingStatusRequestRequestTypeDef,
     GetProjectRequestRequestTypeDef,
     GetRemoteAccessSessionRequestRequestTypeDef,
     GetRunRequestRequestTypeDef,
     GetSuiteRequestRequestTypeDef,
     GetTestGridProjectRequestRequestTypeDef,
     GetTestGridSessionRequestRequestTypeDef,
     TestGridSessionTypeDef,
     GetTestRequestRequestTypeDef,
     GetUploadRequestRequestTypeDef,
     GetVPCEConfigurationRequestRequestTypeDef,
     InstallToRemoteAccessSessionRequestRequestTypeDef,
+    ListArtifactsRequestListArtifactsPaginateTypeDef,
     ListArtifactsRequestRequestTypeDef,
+    ListDeviceInstancesRequestListDeviceInstancesPaginateTypeDef,
     ListDeviceInstancesRequestRequestTypeDef,
+    ListDevicePoolsRequestListDevicePoolsPaginateTypeDef,
     ListDevicePoolsRequestRequestTypeDef,
+    ListInstanceProfilesRequestListInstanceProfilesPaginateTypeDef,
     ListInstanceProfilesRequestRequestTypeDef,
+    ListJobsRequestListJobsPaginateTypeDef,
     ListJobsRequestRequestTypeDef,
+    ListNetworkProfilesRequestListNetworkProfilesPaginateTypeDef,
     ListNetworkProfilesRequestRequestTypeDef,
+    ListOfferingPromotionsRequestListOfferingPromotionsPaginateTypeDef,
     ListOfferingPromotionsRequestRequestTypeDef,
     OfferingPromotionTypeDef,
+    ListOfferingTransactionsRequestListOfferingTransactionsPaginateTypeDef,
     ListOfferingTransactionsRequestRequestTypeDef,
+    ListOfferingsRequestListOfferingsPaginateTypeDef,
     ListOfferingsRequestRequestTypeDef,
+    ListProjectsRequestListProjectsPaginateTypeDef,
     ListProjectsRequestRequestTypeDef,
+    ListRemoteAccessSessionsRequestListRemoteAccessSessionsPaginateTypeDef,
     ListRemoteAccessSessionsRequestRequestTypeDef,
+    ListRunsRequestListRunsPaginateTypeDef,
     ListRunsRequestRequestTypeDef,
+    ListSamplesRequestListSamplesPaginateTypeDef,
     ListSamplesRequestRequestTypeDef,
     SampleTypeDef,
+    ListSuitesRequestListSuitesPaginateTypeDef,
     ListSuitesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     TagTypeDef,
     ListTestGridProjectsRequestRequestTypeDef,
     ListTestGridSessionActionsRequestRequestTypeDef,
     TestGridSessionActionTypeDef,
     ListTestGridSessionArtifactsRequestRequestTypeDef,
     TestGridSessionArtifactTypeDef,
     ListTestGridSessionsRequestRequestTypeDef,
+    ListTestsRequestListTestsPaginateTypeDef,
     ListTestsRequestRequestTypeDef,
+    ListUniqueProblemsRequestListUniqueProblemsPaginateTypeDef,
     ListUniqueProblemsRequestRequestTypeDef,
+    ListUploadsRequestListUploadsPaginateTypeDef,
     ListUploadsRequestRequestTypeDef,
+    ListVPCEConfigurationsRequestListVPCEConfigurationsPaginateTypeDef,
     ListVPCEConfigurationsRequestRequestTypeDef,
     LocationTypeDef,
     MonetaryAmountTypeDef,
+    PaginatorConfigTypeDef,
     ProblemDetailTypeDef,
     PurchaseOfferingRequestRequestTypeDef,
     RadiosTypeDef,
     RenewOfferingRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     StopJobRequestRequestTypeDef,
     StopRemoteAccessSessionRequestRequestTypeDef,
     StopRunRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateDeviceInstanceRequestRequestTypeDef,
     UpdateInstanceProfileRequestRequestTypeDef,
     UpdateNetworkProfileRequestRequestTypeDef,
     UpdateUploadRequestRequestTypeDef,
     UpdateVPCEConfigurationRequestRequestTypeDef,
     AccountSettingsTypeDef,
+    ListArtifactsResultTypeDef,
     CreateDevicePoolRequestRequestTypeDef,
     DevicePoolTypeDef,
     UpdateDevicePoolRequestRequestTypeDef,
-    CreateTestGridUrlResultTypeDef,
-    ListArtifactsResultTypeDef,
     CreateInstanceProfileResultTypeDef,
     DeviceInstanceTypeDef,
     GetInstanceProfileResultTypeDef,
     ListInstanceProfilesResultTypeDef,
     UpdateInstanceProfileResultTypeDef,
     CreateNetworkProfileResultTypeDef,
     GetNetworkProfileResultTypeDef,
@@ -517,37 +536,18 @@
     UpdateUploadResultTypeDef,
     CreateVPCEConfigurationResultTypeDef,
     GetVPCEConfigurationResultTypeDef,
     ListVPCEConfigurationsResultTypeDef,
     UpdateVPCEConfigurationResultTypeDef,
     DeviceSelectionConfigurationTypeDef,
     DeviceSelectionResultTypeDef,
+    ListDevicesRequestListDevicesPaginateTypeDef,
     ListDevicesRequestRequestTypeDef,
     SuiteTypeDef,
     TestTypeDef,
-    GetOfferingStatusRequestGetOfferingStatusPaginateTypeDef,
-    ListArtifactsRequestListArtifactsPaginateTypeDef,
-    ListDeviceInstancesRequestListDeviceInstancesPaginateTypeDef,
-    ListDevicePoolsRequestListDevicePoolsPaginateTypeDef,
-    ListDevicesRequestListDevicesPaginateTypeDef,
-    ListInstanceProfilesRequestListInstanceProfilesPaginateTypeDef,
-    ListJobsRequestListJobsPaginateTypeDef,
-    ListNetworkProfilesRequestListNetworkProfilesPaginateTypeDef,
-    ListOfferingPromotionsRequestListOfferingPromotionsPaginateTypeDef,
-    ListOfferingTransactionsRequestListOfferingTransactionsPaginateTypeDef,
-    ListOfferingsRequestListOfferingsPaginateTypeDef,
-    ListProjectsRequestListProjectsPaginateTypeDef,
-    ListRemoteAccessSessionsRequestListRemoteAccessSessionsPaginateTypeDef,
-    ListRunsRequestListRunsPaginateTypeDef,
-    ListSamplesRequestListSamplesPaginateTypeDef,
-    ListSuitesRequestListSuitesPaginateTypeDef,
-    ListTestsRequestListTestsPaginateTypeDef,
-    ListUniqueProblemsRequestListUniqueProblemsPaginateTypeDef,
-    ListUploadsRequestListUploadsPaginateTypeDef,
-    ListVPCEConfigurationsRequestListVPCEConfigurationsPaginateTypeDef,
     GetTestGridSessionResultTypeDef,
     ListTestGridSessionsResultTypeDef,
     ListOfferingPromotionsResultTypeDef,
     ListSamplesResultTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     ListTestGridSessionActionsResultTypeDef,
@@ -616,43 +616,43 @@
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

### Comparing `types-aiobotocore-devicefarm-2.5.0.post1/setup.py` & `types-aiobotocore-devicefarm-2.5.1/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-devicefarm.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-devicefarm",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_devicefarm"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.DeviceFarm 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.DeviceFarm 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/"
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

### Comparing `types-aiobotocore-devicefarm-2.5.0.post1/types_aiobotocore_devicefarm/__init__.py` & `types-aiobotocore-devicefarm-2.5.1/types_aiobotocore_devicefarm/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-devicefarm-2.5.0.post1/types_aiobotocore_devicefarm/__init__.pyi` & `types-aiobotocore-devicefarm-2.5.1/types_aiobotocore_devicefarm/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-devicefarm-2.5.0.post1/types_aiobotocore_devicefarm/__main__.py` & `types-aiobotocore-devicefarm-2.5.1/types_aiobotocore_devicefarm/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.DeviceFarm 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.DeviceFarm 2.5.1\nVersion:         2.5.1\nBuilder"
+        " version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm\nOther"
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

### Comparing `types-aiobotocore-devicefarm-2.5.0.post1/types_aiobotocore_devicefarm/client.py` & `types-aiobotocore-devicefarm-2.5.1/types_aiobotocore_devicefarm/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-devicefarm-2.5.0.post1/types_aiobotocore_devicefarm/client.pyi` & `types-aiobotocore-devicefarm-2.5.1/types_aiobotocore_devicefarm/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-devicefarm-2.5.0.post1/types_aiobotocore_devicefarm/literals.py` & `types-aiobotocore-devicefarm-2.5.1/types_aiobotocore_devicefarm/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -333,14 +333,15 @@
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
@@ -419,14 +420,15 @@
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
@@ -437,14 +439,15 @@
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
@@ -480,14 +483,15 @@
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
@@ -506,16 +510,19 @@
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
@@ -599,15 +606,17 @@
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

### Comparing `types-aiobotocore-devicefarm-2.5.0.post1/types_aiobotocore_devicefarm/literals.pyi` & `types-aiobotocore-devicefarm-2.5.1/types_aiobotocore_devicefarm/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -331,14 +331,15 @@
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
@@ -417,14 +418,15 @@
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
@@ -435,14 +437,15 @@
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
@@ -478,14 +481,15 @@
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
@@ -504,16 +508,19 @@
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
@@ -597,15 +604,17 @@
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

### Comparing `types-aiobotocore-devicefarm-2.5.0.post1/types_aiobotocore_devicefarm/paginator.py` & `types-aiobotocore-devicefarm-2.5.1/types_aiobotocore_devicefarm/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -54,16 +54,15 @@
         list_suites_paginator: ListSuitesPaginator = client.get_paginator("list_suites")
         list_tests_paginator: ListTestsPaginator = client.get_paginator("list_tests")
         list_unique_problems_paginator: ListUniqueProblemsPaginator = client.get_paginator("list_unique_problems")
         list_uploads_paginator: ListUploadsPaginator = client.get_paginator("list_uploads")
         list_vpce_configurations_paginator: ListVPCEConfigurationsPaginator = client.get_paginator("list_vpce_configurations")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     ArtifactCategoryType,
     DevicePoolTypeType,
@@ -91,20 +90,14 @@
     ListTestsResultTypeDef,
     ListUniqueProblemsResultTypeDef,
     ListUploadsResultTypeDef,
     ListVPCEConfigurationsResultTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "GetOfferingStatusPaginator",
     "ListArtifactsPaginator",
     "ListDeviceInstancesPaginator",
     "ListDevicePoolsPaginator",
     "ListDevicesPaginator",
     "ListInstanceProfilesPaginator",
@@ -138,15 +131,15 @@
 class GetOfferingStatusPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.GetOfferingStatus)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#getofferingstatuspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetOfferingStatusResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.GetOfferingStatus.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#getofferingstatuspaginator)
         """
 
 
@@ -157,30 +150,30 @@
     """
 
     def paginate(
         self,
         *,
         arn: str,
         type: ArtifactCategoryType,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListArtifactsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListArtifacts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listartifactspaginator)
         """
 
 
 class ListDeviceInstancesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListDeviceInstances)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listdeviceinstancespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDeviceInstancesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListDeviceInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listdeviceinstancespaginator)
         """
 
 
@@ -191,15 +184,15 @@
     """
 
     def paginate(
         self,
         *,
         arn: str,
         type: DevicePoolTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDevicePoolsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListDevicePools.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listdevicepoolspaginator)
         """
 
 
@@ -210,45 +203,45 @@
     """
 
     def paginate(
         self,
         *,
         arn: str = ...,
         filters: Sequence[DeviceFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDevicesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListDevices.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listdevicespaginator)
         """
 
 
 class ListInstanceProfilesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListInstanceProfiles)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listinstanceprofilespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListInstanceProfilesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListInstanceProfiles.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listinstanceprofilespaginator)
         """
 
 
 class ListJobsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listjobspaginator)
     """
 
     def paginate(
-        self, *, arn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, arn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListJobsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listjobspaginator)
         """
 
 
@@ -259,165 +252,165 @@
     """
 
     def paginate(
         self,
         *,
         arn: str,
         type: NetworkProfileTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListNetworkProfilesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListNetworkProfiles.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listnetworkprofilespaginator)
         """
 
 
 class ListOfferingPromotionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListOfferingPromotions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listofferingpromotionspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOfferingPromotionsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListOfferingPromotions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listofferingpromotionspaginator)
         """
 
 
 class ListOfferingTransactionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListOfferingTransactions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listofferingtransactionspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOfferingTransactionsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListOfferingTransactions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listofferingtransactionspaginator)
         """
 
 
 class ListOfferingsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListOfferings)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listofferingspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOfferingsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListOfferings.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listofferingspaginator)
         """
 
 
 class ListProjectsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListProjects)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listprojectspaginator)
     """
 
     def paginate(
-        self, *, arn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, arn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProjectsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListProjects.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listprojectspaginator)
         """
 
 
 class ListRemoteAccessSessionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListRemoteAccessSessions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listremoteaccesssessionspaginator)
     """
 
     def paginate(
-        self, *, arn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, arn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRemoteAccessSessionsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListRemoteAccessSessions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listremoteaccesssessionspaginator)
         """
 
 
 class ListRunsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListRuns)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listrunspaginator)
     """
 
     def paginate(
-        self, *, arn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, arn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRunsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListRuns.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listrunspaginator)
         """
 
 
 class ListSamplesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListSamples)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listsamplespaginator)
     """
 
     def paginate(
-        self, *, arn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, arn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSamplesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListSamples.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listsamplespaginator)
         """
 
 
 class ListSuitesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListSuites)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listsuitespaginator)
     """
 
     def paginate(
-        self, *, arn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, arn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSuitesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListSuites.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listsuitespaginator)
         """
 
 
 class ListTestsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListTests)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listtestspaginator)
     """
 
     def paginate(
-        self, *, arn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, arn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTestsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListTests.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listtestspaginator)
         """
 
 
 class ListUniqueProblemsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListUniqueProblems)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listuniqueproblemspaginator)
     """
 
     def paginate(
-        self, *, arn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, arn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListUniqueProblemsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListUniqueProblems.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listuniqueproblemspaginator)
         """
 
 
@@ -428,28 +421,28 @@
     """
 
     def paginate(
         self,
         *,
         arn: str,
         type: UploadTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListUploadsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListUploads.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listuploadspaginator)
         """
 
 
 class ListVPCEConfigurationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListVPCEConfigurations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listvpceconfigurationspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListVPCEConfigurationsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListVPCEConfigurations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listvpceconfigurationspaginator)
         """
```

### Comparing `types-aiobotocore-devicefarm-2.5.0.post1/types_aiobotocore_devicefarm/paginator.pyi` & `types-aiobotocore-devicefarm-2.5.1/types_aiobotocore_devicefarm/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -54,16 +54,15 @@
         list_suites_paginator: ListSuitesPaginator = client.get_paginator("list_suites")
         list_tests_paginator: ListTestsPaginator = client.get_paginator("list_tests")
         list_unique_problems_paginator: ListUniqueProblemsPaginator = client.get_paginator("list_unique_problems")
         list_uploads_paginator: ListUploadsPaginator = client.get_paginator("list_uploads")
         list_vpce_configurations_paginator: ListVPCEConfigurationsPaginator = client.get_paginator("list_vpce_configurations")
     ```
 """
-import sys
-from typing import Generic, Iterator, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     ArtifactCategoryType,
     DevicePoolTypeType,
@@ -91,19 +90,14 @@
     ListTestsResultTypeDef,
     ListUniqueProblemsResultTypeDef,
     ListUploadsResultTypeDef,
     ListVPCEConfigurationsResultTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "GetOfferingStatusPaginator",
     "ListArtifactsPaginator",
     "ListDeviceInstancesPaginator",
     "ListDevicePoolsPaginator",
     "ListDevicesPaginator",
     "ListInstanceProfilesPaginator",
@@ -134,15 +128,15 @@
 class GetOfferingStatusPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.GetOfferingStatus)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#getofferingstatuspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[GetOfferingStatusResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.GetOfferingStatus.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#getofferingstatuspaginator)
         """
 
 class ListArtifactsPaginator(AioPaginator):
@@ -152,29 +146,29 @@
     """
 
     def paginate(
         self,
         *,
         arn: str,
         type: ArtifactCategoryType,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListArtifactsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListArtifacts.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listartifactspaginator)
         """
 
 class ListDeviceInstancesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListDeviceInstances)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listdeviceinstancespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDeviceInstancesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListDeviceInstances.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listdeviceinstancespaginator)
         """
 
 class ListDevicePoolsPaginator(AioPaginator):
@@ -184,15 +178,15 @@
     """
 
     def paginate(
         self,
         *,
         arn: str,
         type: DevicePoolTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDevicePoolsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListDevicePools.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listdevicepoolspaginator)
         """
 
 class ListDevicesPaginator(AioPaginator):
@@ -202,43 +196,43 @@
     """
 
     def paginate(
         self,
         *,
         arn: str = ...,
         filters: Sequence[DeviceFilterTypeDef] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDevicesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListDevices.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listdevicespaginator)
         """
 
 class ListInstanceProfilesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListInstanceProfiles)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listinstanceprofilespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListInstanceProfilesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListInstanceProfiles.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listinstanceprofilespaginator)
         """
 
 class ListJobsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listjobspaginator)
     """
 
     def paginate(
-        self, *, arn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, arn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListJobsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listjobspaginator)
         """
 
 class ListNetworkProfilesPaginator(AioPaginator):
@@ -248,155 +242,155 @@
     """
 
     def paginate(
         self,
         *,
         arn: str,
         type: NetworkProfileTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListNetworkProfilesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListNetworkProfiles.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listnetworkprofilespaginator)
         """
 
 class ListOfferingPromotionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListOfferingPromotions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listofferingpromotionspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOfferingPromotionsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListOfferingPromotions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listofferingpromotionspaginator)
         """
 
 class ListOfferingTransactionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListOfferingTransactions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listofferingtransactionspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOfferingTransactionsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListOfferingTransactions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listofferingtransactionspaginator)
         """
 
 class ListOfferingsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListOfferings)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listofferingspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOfferingsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListOfferings.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listofferingspaginator)
         """
 
 class ListProjectsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListProjects)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listprojectspaginator)
     """
 
     def paginate(
-        self, *, arn: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, arn: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListProjectsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListProjects.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listprojectspaginator)
         """
 
 class ListRemoteAccessSessionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListRemoteAccessSessions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listremoteaccesssessionspaginator)
     """
 
     def paginate(
-        self, *, arn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, arn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRemoteAccessSessionsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListRemoteAccessSessions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listremoteaccesssessionspaginator)
         """
 
 class ListRunsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListRuns)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listrunspaginator)
     """
 
     def paginate(
-        self, *, arn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, arn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListRunsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListRuns.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listrunspaginator)
         """
 
 class ListSamplesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListSamples)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listsamplespaginator)
     """
 
     def paginate(
-        self, *, arn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, arn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSamplesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListSamples.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listsamplespaginator)
         """
 
 class ListSuitesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListSuites)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listsuitespaginator)
     """
 
     def paginate(
-        self, *, arn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, arn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSuitesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListSuites.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listsuitespaginator)
         """
 
 class ListTestsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListTests)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listtestspaginator)
     """
 
     def paginate(
-        self, *, arn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, arn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTestsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListTests.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listtestspaginator)
         """
 
 class ListUniqueProblemsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListUniqueProblems)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listuniqueproblemspaginator)
     """
 
     def paginate(
-        self, *, arn: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, arn: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListUniqueProblemsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListUniqueProblems.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listuniqueproblemspaginator)
         """
 
 class ListUploadsPaginator(AioPaginator):
@@ -406,27 +400,27 @@
     """
 
     def paginate(
         self,
         *,
         arn: str,
         type: UploadTypeType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListUploadsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListUploads.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listuploadspaginator)
         """
 
 class ListVPCEConfigurationsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListVPCEConfigurations)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listvpceconfigurationspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListVPCEConfigurationsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm.Paginator.ListVPCEConfigurations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/paginators/#listvpceconfigurationspaginator)
         """
```

### Comparing `types-aiobotocore-devicefarm-2.5.0.post1/types_aiobotocore_devicefarm/type_defs.py` & `types-aiobotocore-devicefarm-2.5.1/types_aiobotocore_devicefarm/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -55,23 +55,23 @@
 
 __all__ = (
     "TrialMinutesTypeDef",
     "ArtifactTypeDef",
     "CPUTypeDef",
     "CountersTypeDef",
     "RuleTypeDef",
-    "ResponseMetadataTypeDef",
     "CreateInstanceProfileRequestRequestTypeDef",
     "InstanceProfileTypeDef",
     "CreateNetworkProfileRequestRequestTypeDef",
     "NetworkProfileTypeDef",
     "VpcConfigTypeDef",
     "CreateRemoteAccessSessionConfigurationTypeDef",
     "TestGridVpcConfigTypeDef",
     "CreateTestGridUrlRequestRequestTypeDef",
+    "CreateTestGridUrlResultTypeDef",
     "CreateUploadRequestRequestTypeDef",
     "UploadTypeDef",
     "CreateVPCEConfigurationRequestRequestTypeDef",
     "VPCEConfigurationTypeDef",
     "CustomerArtifactPathsTypeDef",
     "DeleteDevicePoolRequestRequestTypeDef",
     "DeleteInstanceProfileRequestRequestTypeDef",
@@ -90,76 +90,95 @@
     "GetDeviceInstanceRequestRequestTypeDef",
     "ScheduleRunTestTypeDef",
     "GetDevicePoolRequestRequestTypeDef",
     "GetDeviceRequestRequestTypeDef",
     "GetInstanceProfileRequestRequestTypeDef",
     "GetJobRequestRequestTypeDef",
     "GetNetworkProfileRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetOfferingStatusRequestGetOfferingStatusPaginateTypeDef",
     "GetOfferingStatusRequestRequestTypeDef",
     "GetProjectRequestRequestTypeDef",
     "GetRemoteAccessSessionRequestRequestTypeDef",
     "GetRunRequestRequestTypeDef",
     "GetSuiteRequestRequestTypeDef",
     "GetTestGridProjectRequestRequestTypeDef",
     "GetTestGridSessionRequestRequestTypeDef",
     "TestGridSessionTypeDef",
     "GetTestRequestRequestTypeDef",
     "GetUploadRequestRequestTypeDef",
     "GetVPCEConfigurationRequestRequestTypeDef",
     "InstallToRemoteAccessSessionRequestRequestTypeDef",
+    "ListArtifactsRequestListArtifactsPaginateTypeDef",
     "ListArtifactsRequestRequestTypeDef",
+    "ListDeviceInstancesRequestListDeviceInstancesPaginateTypeDef",
     "ListDeviceInstancesRequestRequestTypeDef",
+    "ListDevicePoolsRequestListDevicePoolsPaginateTypeDef",
     "ListDevicePoolsRequestRequestTypeDef",
+    "ListInstanceProfilesRequestListInstanceProfilesPaginateTypeDef",
     "ListInstanceProfilesRequestRequestTypeDef",
+    "ListJobsRequestListJobsPaginateTypeDef",
     "ListJobsRequestRequestTypeDef",
+    "ListNetworkProfilesRequestListNetworkProfilesPaginateTypeDef",
     "ListNetworkProfilesRequestRequestTypeDef",
+    "ListOfferingPromotionsRequestListOfferingPromotionsPaginateTypeDef",
     "ListOfferingPromotionsRequestRequestTypeDef",
     "OfferingPromotionTypeDef",
+    "ListOfferingTransactionsRequestListOfferingTransactionsPaginateTypeDef",
     "ListOfferingTransactionsRequestRequestTypeDef",
+    "ListOfferingsRequestListOfferingsPaginateTypeDef",
     "ListOfferingsRequestRequestTypeDef",
+    "ListProjectsRequestListProjectsPaginateTypeDef",
     "ListProjectsRequestRequestTypeDef",
+    "ListRemoteAccessSessionsRequestListRemoteAccessSessionsPaginateTypeDef",
     "ListRemoteAccessSessionsRequestRequestTypeDef",
+    "ListRunsRequestListRunsPaginateTypeDef",
     "ListRunsRequestRequestTypeDef",
+    "ListSamplesRequestListSamplesPaginateTypeDef",
     "ListSamplesRequestRequestTypeDef",
     "SampleTypeDef",
+    "ListSuitesRequestListSuitesPaginateTypeDef",
     "ListSuitesRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "TagTypeDef",
     "ListTestGridProjectsRequestRequestTypeDef",
     "ListTestGridSessionActionsRequestRequestTypeDef",
     "TestGridSessionActionTypeDef",
     "ListTestGridSessionArtifactsRequestRequestTypeDef",
     "TestGridSessionArtifactTypeDef",
     "ListTestGridSessionsRequestRequestTypeDef",
+    "ListTestsRequestListTestsPaginateTypeDef",
     "ListTestsRequestRequestTypeDef",
+    "ListUniqueProblemsRequestListUniqueProblemsPaginateTypeDef",
     "ListUniqueProblemsRequestRequestTypeDef",
+    "ListUploadsRequestListUploadsPaginateTypeDef",
     "ListUploadsRequestRequestTypeDef",
+    "ListVPCEConfigurationsRequestListVPCEConfigurationsPaginateTypeDef",
     "ListVPCEConfigurationsRequestRequestTypeDef",
     "LocationTypeDef",
     "MonetaryAmountTypeDef",
+    "PaginatorConfigTypeDef",
     "ProblemDetailTypeDef",
     "PurchaseOfferingRequestRequestTypeDef",
     "RadiosTypeDef",
     "RenewOfferingRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "StopJobRequestRequestTypeDef",
     "StopRemoteAccessSessionRequestRequestTypeDef",
     "StopRunRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateDeviceInstanceRequestRequestTypeDef",
     "UpdateInstanceProfileRequestRequestTypeDef",
     "UpdateNetworkProfileRequestRequestTypeDef",
     "UpdateUploadRequestRequestTypeDef",
     "UpdateVPCEConfigurationRequestRequestTypeDef",
     "AccountSettingsTypeDef",
+    "ListArtifactsResultTypeDef",
     "CreateDevicePoolRequestRequestTypeDef",
     "DevicePoolTypeDef",
     "UpdateDevicePoolRequestRequestTypeDef",
-    "CreateTestGridUrlResultTypeDef",
-    "ListArtifactsResultTypeDef",
     "CreateInstanceProfileResultTypeDef",
     "DeviceInstanceTypeDef",
     "GetInstanceProfileResultTypeDef",
     "ListInstanceProfilesResultTypeDef",
     "UpdateInstanceProfileResultTypeDef",
     "CreateNetworkProfileResultTypeDef",
     "GetNetworkProfileResultTypeDef",
@@ -179,37 +198,18 @@
     "UpdateUploadResultTypeDef",
     "CreateVPCEConfigurationResultTypeDef",
     "GetVPCEConfigurationResultTypeDef",
     "ListVPCEConfigurationsResultTypeDef",
     "UpdateVPCEConfigurationResultTypeDef",
     "DeviceSelectionConfigurationTypeDef",
     "DeviceSelectionResultTypeDef",
+    "ListDevicesRequestListDevicesPaginateTypeDef",
     "ListDevicesRequestRequestTypeDef",
     "SuiteTypeDef",
     "TestTypeDef",
-    "GetOfferingStatusRequestGetOfferingStatusPaginateTypeDef",
-    "ListArtifactsRequestListArtifactsPaginateTypeDef",
-    "ListDeviceInstancesRequestListDeviceInstancesPaginateTypeDef",
-    "ListDevicePoolsRequestListDevicePoolsPaginateTypeDef",
-    "ListDevicesRequestListDevicesPaginateTypeDef",
-    "ListInstanceProfilesRequestListInstanceProfilesPaginateTypeDef",
-    "ListJobsRequestListJobsPaginateTypeDef",
-    "ListNetworkProfilesRequestListNetworkProfilesPaginateTypeDef",
-    "ListOfferingPromotionsRequestListOfferingPromotionsPaginateTypeDef",
-    "ListOfferingTransactionsRequestListOfferingTransactionsPaginateTypeDef",
-    "ListOfferingsRequestListOfferingsPaginateTypeDef",
-    "ListProjectsRequestListProjectsPaginateTypeDef",
-    "ListRemoteAccessSessionsRequestListRemoteAccessSessionsPaginateTypeDef",
-    "ListRunsRequestListRunsPaginateTypeDef",
-    "ListSamplesRequestListSamplesPaginateTypeDef",
-    "ListSuitesRequestListSuitesPaginateTypeDef",
-    "ListTestsRequestListTestsPaginateTypeDef",
-    "ListUniqueProblemsRequestListUniqueProblemsPaginateTypeDef",
-    "ListUploadsRequestListUploadsPaginateTypeDef",
-    "ListVPCEConfigurationsRequestListVPCEConfigurationsPaginateTypeDef",
     "GetTestGridSessionResultTypeDef",
     "ListTestGridSessionsResultTypeDef",
     "ListOfferingPromotionsResultTypeDef",
     "ListSamplesResultTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "ListTestGridSessionActionsResultTypeDef",
@@ -321,25 +321,14 @@
         "attribute": DeviceAttributeType,
         "operator": RuleOperatorType,
         "value": str,
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
 _RequiredCreateInstanceProfileRequestRequestTypeDef = TypedDict(
     "_RequiredCreateInstanceProfileRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalCreateInstanceProfileRequestRequestTypeDef = TypedDict(
@@ -456,14 +445,23 @@
     "CreateTestGridUrlRequestRequestTypeDef",
     {
         "projectArn": str,
         "expiresInSeconds": int,
     },
 )
 
+CreateTestGridUrlResultTypeDef = TypedDict(
+    "CreateTestGridUrlResultTypeDef",
+    {
+        "url": str,
+        "expires": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateUploadRequestRequestTypeDef = TypedDict(
     "_RequiredCreateUploadRequestRequestTypeDef",
     {
         "projectArn": str,
         "name": str,
         "type": UploadTypeType,
     },
@@ -718,20 +716,18 @@
 GetNetworkProfileRequestRequestTypeDef = TypedDict(
     "GetNetworkProfileRequestRequestTypeDef",
     {
         "arn": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetOfferingStatusRequestGetOfferingStatusPaginateTypeDef = TypedDict(
+    "GetOfferingStatusRequestGetOfferingStatusPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 GetOfferingStatusRequestRequestTypeDef = TypedDict(
     "GetOfferingStatusRequestRequestTypeDef",
     {
@@ -823,14 +819,37 @@
     "InstallToRemoteAccessSessionRequestRequestTypeDef",
     {
         "remoteAccessSessionArn": str,
         "appArn": str,
     },
 )
 
+_RequiredListArtifactsRequestListArtifactsPaginateTypeDef = TypedDict(
+    "_RequiredListArtifactsRequestListArtifactsPaginateTypeDef",
+    {
+        "arn": str,
+        "type": ArtifactCategoryType,
+    },
+)
+_OptionalListArtifactsRequestListArtifactsPaginateTypeDef = TypedDict(
+    "_OptionalListArtifactsRequestListArtifactsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListArtifactsRequestListArtifactsPaginateTypeDef(
+    _RequiredListArtifactsRequestListArtifactsPaginateTypeDef,
+    _OptionalListArtifactsRequestListArtifactsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListArtifactsRequestRequestTypeDef = TypedDict(
     "_RequiredListArtifactsRequestRequestTypeDef",
     {
         "arn": str,
         "type": ArtifactCategoryType,
     },
 )
@@ -845,23 +864,54 @@
 
 class ListArtifactsRequestRequestTypeDef(
     _RequiredListArtifactsRequestRequestTypeDef, _OptionalListArtifactsRequestRequestTypeDef
 ):
     pass
 
 
+ListDeviceInstancesRequestListDeviceInstancesPaginateTypeDef = TypedDict(
+    "ListDeviceInstancesRequestListDeviceInstancesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDeviceInstancesRequestRequestTypeDef = TypedDict(
     "ListDeviceInstancesRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+_RequiredListDevicePoolsRequestListDevicePoolsPaginateTypeDef = TypedDict(
+    "_RequiredListDevicePoolsRequestListDevicePoolsPaginateTypeDef",
+    {
+        "arn": str,
+    },
+)
+_OptionalListDevicePoolsRequestListDevicePoolsPaginateTypeDef = TypedDict(
+    "_OptionalListDevicePoolsRequestListDevicePoolsPaginateTypeDef",
+    {
+        "type": DevicePoolTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListDevicePoolsRequestListDevicePoolsPaginateTypeDef(
+    _RequiredListDevicePoolsRequestListDevicePoolsPaginateTypeDef,
+    _OptionalListDevicePoolsRequestListDevicePoolsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListDevicePoolsRequestRequestTypeDef = TypedDict(
     "_RequiredListDevicePoolsRequestRequestTypeDef",
     {
         "arn": str,
     },
 )
 _OptionalListDevicePoolsRequestRequestTypeDef = TypedDict(
@@ -876,23 +926,52 @@
 
 class ListDevicePoolsRequestRequestTypeDef(
     _RequiredListDevicePoolsRequestRequestTypeDef, _OptionalListDevicePoolsRequestRequestTypeDef
 ):
     pass
 
 
+ListInstanceProfilesRequestListInstanceProfilesPaginateTypeDef = TypedDict(
+    "ListInstanceProfilesRequestListInstanceProfilesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListInstanceProfilesRequestRequestTypeDef = TypedDict(
     "ListInstanceProfilesRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+_RequiredListJobsRequestListJobsPaginateTypeDef = TypedDict(
+    "_RequiredListJobsRequestListJobsPaginateTypeDef",
+    {
+        "arn": str,
+    },
+)
+_OptionalListJobsRequestListJobsPaginateTypeDef = TypedDict(
+    "_OptionalListJobsRequestListJobsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListJobsRequestListJobsPaginateTypeDef(
+    _RequiredListJobsRequestListJobsPaginateTypeDef, _OptionalListJobsRequestListJobsPaginateTypeDef
+):
+    pass
+
+
 _RequiredListJobsRequestRequestTypeDef = TypedDict(
     "_RequiredListJobsRequestRequestTypeDef",
     {
         "arn": str,
     },
 )
 _OptionalListJobsRequestRequestTypeDef = TypedDict(
@@ -906,14 +985,37 @@
 
 class ListJobsRequestRequestTypeDef(
     _RequiredListJobsRequestRequestTypeDef, _OptionalListJobsRequestRequestTypeDef
 ):
     pass
 
 
+_RequiredListNetworkProfilesRequestListNetworkProfilesPaginateTypeDef = TypedDict(
+    "_RequiredListNetworkProfilesRequestListNetworkProfilesPaginateTypeDef",
+    {
+        "arn": str,
+    },
+)
+_OptionalListNetworkProfilesRequestListNetworkProfilesPaginateTypeDef = TypedDict(
+    "_OptionalListNetworkProfilesRequestListNetworkProfilesPaginateTypeDef",
+    {
+        "type": NetworkProfileTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListNetworkProfilesRequestListNetworkProfilesPaginateTypeDef(
+    _RequiredListNetworkProfilesRequestListNetworkProfilesPaginateTypeDef,
+    _OptionalListNetworkProfilesRequestListNetworkProfilesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListNetworkProfilesRequestRequestTypeDef = TypedDict(
     "_RequiredListNetworkProfilesRequestRequestTypeDef",
     {
         "arn": str,
     },
 )
 _OptionalListNetworkProfilesRequestRequestTypeDef = TypedDict(
@@ -929,14 +1031,22 @@
 class ListNetworkProfilesRequestRequestTypeDef(
     _RequiredListNetworkProfilesRequestRequestTypeDef,
     _OptionalListNetworkProfilesRequestRequestTypeDef,
 ):
     pass
 
 
+ListOfferingPromotionsRequestListOfferingPromotionsPaginateTypeDef = TypedDict(
+    "ListOfferingPromotionsRequestListOfferingPromotionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListOfferingPromotionsRequestRequestTypeDef = TypedDict(
     "ListOfferingPromotionsRequestRequestTypeDef",
     {
         "nextToken": str,
     },
     total=False,
 )
@@ -946,39 +1056,86 @@
     {
         "id": str,
         "description": str,
     },
     total=False,
 )
 
+ListOfferingTransactionsRequestListOfferingTransactionsPaginateTypeDef = TypedDict(
+    "ListOfferingTransactionsRequestListOfferingTransactionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListOfferingTransactionsRequestRequestTypeDef = TypedDict(
     "ListOfferingTransactionsRequestRequestTypeDef",
     {
         "nextToken": str,
     },
     total=False,
 )
 
+ListOfferingsRequestListOfferingsPaginateTypeDef = TypedDict(
+    "ListOfferingsRequestListOfferingsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListOfferingsRequestRequestTypeDef = TypedDict(
     "ListOfferingsRequestRequestTypeDef",
     {
         "nextToken": str,
     },
     total=False,
 )
 
+ListProjectsRequestListProjectsPaginateTypeDef = TypedDict(
+    "ListProjectsRequestListProjectsPaginateTypeDef",
+    {
+        "arn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListProjectsRequestRequestTypeDef = TypedDict(
     "ListProjectsRequestRequestTypeDef",
     {
         "arn": str,
         "nextToken": str,
     },
     total=False,
 )
 
+_RequiredListRemoteAccessSessionsRequestListRemoteAccessSessionsPaginateTypeDef = TypedDict(
+    "_RequiredListRemoteAccessSessionsRequestListRemoteAccessSessionsPaginateTypeDef",
+    {
+        "arn": str,
+    },
+)
+_OptionalListRemoteAccessSessionsRequestListRemoteAccessSessionsPaginateTypeDef = TypedDict(
+    "_OptionalListRemoteAccessSessionsRequestListRemoteAccessSessionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListRemoteAccessSessionsRequestListRemoteAccessSessionsPaginateTypeDef(
+    _RequiredListRemoteAccessSessionsRequestListRemoteAccessSessionsPaginateTypeDef,
+    _OptionalListRemoteAccessSessionsRequestListRemoteAccessSessionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListRemoteAccessSessionsRequestRequestTypeDef = TypedDict(
     "_RequiredListRemoteAccessSessionsRequestRequestTypeDef",
     {
         "arn": str,
     },
 )
 _OptionalListRemoteAccessSessionsRequestRequestTypeDef = TypedDict(
@@ -993,14 +1150,35 @@
 class ListRemoteAccessSessionsRequestRequestTypeDef(
     _RequiredListRemoteAccessSessionsRequestRequestTypeDef,
     _OptionalListRemoteAccessSessionsRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListRunsRequestListRunsPaginateTypeDef = TypedDict(
+    "_RequiredListRunsRequestListRunsPaginateTypeDef",
+    {
+        "arn": str,
+    },
+)
+_OptionalListRunsRequestListRunsPaginateTypeDef = TypedDict(
+    "_OptionalListRunsRequestListRunsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListRunsRequestListRunsPaginateTypeDef(
+    _RequiredListRunsRequestListRunsPaginateTypeDef, _OptionalListRunsRequestListRunsPaginateTypeDef
+):
+    pass
+
+
 _RequiredListRunsRequestRequestTypeDef = TypedDict(
     "_RequiredListRunsRequestRequestTypeDef",
     {
         "arn": str,
     },
 )
 _OptionalListRunsRequestRequestTypeDef = TypedDict(
@@ -1014,14 +1192,36 @@
 
 class ListRunsRequestRequestTypeDef(
     _RequiredListRunsRequestRequestTypeDef, _OptionalListRunsRequestRequestTypeDef
 ):
     pass
 
 
+_RequiredListSamplesRequestListSamplesPaginateTypeDef = TypedDict(
+    "_RequiredListSamplesRequestListSamplesPaginateTypeDef",
+    {
+        "arn": str,
+    },
+)
+_OptionalListSamplesRequestListSamplesPaginateTypeDef = TypedDict(
+    "_OptionalListSamplesRequestListSamplesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListSamplesRequestListSamplesPaginateTypeDef(
+    _RequiredListSamplesRequestListSamplesPaginateTypeDef,
+    _OptionalListSamplesRequestListSamplesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListSamplesRequestRequestTypeDef = TypedDict(
     "_RequiredListSamplesRequestRequestTypeDef",
     {
         "arn": str,
     },
 )
 _OptionalListSamplesRequestRequestTypeDef = TypedDict(
@@ -1045,14 +1245,36 @@
         "arn": str,
         "type": SampleTypeType,
         "url": str,
     },
     total=False,
 )
 
+_RequiredListSuitesRequestListSuitesPaginateTypeDef = TypedDict(
+    "_RequiredListSuitesRequestListSuitesPaginateTypeDef",
+    {
+        "arn": str,
+    },
+)
+_OptionalListSuitesRequestListSuitesPaginateTypeDef = TypedDict(
+    "_OptionalListSuitesRequestListSuitesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListSuitesRequestListSuitesPaginateTypeDef(
+    _RequiredListSuitesRequestListSuitesPaginateTypeDef,
+    _OptionalListSuitesRequestListSuitesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListSuitesRequestRequestTypeDef = TypedDict(
     "_RequiredListSuitesRequestRequestTypeDef",
     {
         "arn": str,
     },
 )
 _OptionalListSuitesRequestRequestTypeDef = TypedDict(
@@ -1187,14 +1409,36 @@
 class ListTestGridSessionsRequestRequestTypeDef(
     _RequiredListTestGridSessionsRequestRequestTypeDef,
     _OptionalListTestGridSessionsRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListTestsRequestListTestsPaginateTypeDef = TypedDict(
+    "_RequiredListTestsRequestListTestsPaginateTypeDef",
+    {
+        "arn": str,
+    },
+)
+_OptionalListTestsRequestListTestsPaginateTypeDef = TypedDict(
+    "_OptionalListTestsRequestListTestsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListTestsRequestListTestsPaginateTypeDef(
+    _RequiredListTestsRequestListTestsPaginateTypeDef,
+    _OptionalListTestsRequestListTestsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListTestsRequestRequestTypeDef = TypedDict(
     "_RequiredListTestsRequestRequestTypeDef",
     {
         "arn": str,
     },
 )
 _OptionalListTestsRequestRequestTypeDef = TypedDict(
@@ -1208,14 +1452,36 @@
 
 class ListTestsRequestRequestTypeDef(
     _RequiredListTestsRequestRequestTypeDef, _OptionalListTestsRequestRequestTypeDef
 ):
     pass
 
 
+_RequiredListUniqueProblemsRequestListUniqueProblemsPaginateTypeDef = TypedDict(
+    "_RequiredListUniqueProblemsRequestListUniqueProblemsPaginateTypeDef",
+    {
+        "arn": str,
+    },
+)
+_OptionalListUniqueProblemsRequestListUniqueProblemsPaginateTypeDef = TypedDict(
+    "_OptionalListUniqueProblemsRequestListUniqueProblemsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListUniqueProblemsRequestListUniqueProblemsPaginateTypeDef(
+    _RequiredListUniqueProblemsRequestListUniqueProblemsPaginateTypeDef,
+    _OptionalListUniqueProblemsRequestListUniqueProblemsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListUniqueProblemsRequestRequestTypeDef = TypedDict(
     "_RequiredListUniqueProblemsRequestRequestTypeDef",
     {
         "arn": str,
     },
 )
 _OptionalListUniqueProblemsRequestRequestTypeDef = TypedDict(
@@ -1230,14 +1496,37 @@
 class ListUniqueProblemsRequestRequestTypeDef(
     _RequiredListUniqueProblemsRequestRequestTypeDef,
     _OptionalListUniqueProblemsRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListUploadsRequestListUploadsPaginateTypeDef = TypedDict(
+    "_RequiredListUploadsRequestListUploadsPaginateTypeDef",
+    {
+        "arn": str,
+    },
+)
+_OptionalListUploadsRequestListUploadsPaginateTypeDef = TypedDict(
+    "_OptionalListUploadsRequestListUploadsPaginateTypeDef",
+    {
+        "type": UploadTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListUploadsRequestListUploadsPaginateTypeDef(
+    _RequiredListUploadsRequestListUploadsPaginateTypeDef,
+    _OptionalListUploadsRequestListUploadsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListUploadsRequestRequestTypeDef = TypedDict(
     "_RequiredListUploadsRequestRequestTypeDef",
     {
         "arn": str,
     },
 )
 _OptionalListUploadsRequestRequestTypeDef = TypedDict(
@@ -1252,14 +1541,22 @@
 
 class ListUploadsRequestRequestTypeDef(
     _RequiredListUploadsRequestRequestTypeDef, _OptionalListUploadsRequestRequestTypeDef
 ):
     pass
 
 
+ListVPCEConfigurationsRequestListVPCEConfigurationsPaginateTypeDef = TypedDict(
+    "ListVPCEConfigurationsRequestListVPCEConfigurationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListVPCEConfigurationsRequestRequestTypeDef = TypedDict(
     "ListVPCEConfigurationsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -1278,14 +1575,24 @@
     {
         "amount": float,
         "currencyCode": Literal["USD"],
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
 ProblemDetailTypeDef = TypedDict(
     "ProblemDetailTypeDef",
     {
         "arn": str,
         "name": str,
     },
     total=False,
@@ -1328,14 +1635,25 @@
     "RenewOfferingRequestRequestTypeDef",
     {
         "offeringId": str,
         "quantity": int,
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
 StopJobRequestRequestTypeDef = TypedDict(
     "StopJobRequestRequestTypeDef",
     {
         "arn": str,
     },
 )
 
@@ -1501,14 +1819,23 @@
         "maxSlots": Dict[str, int],
         "defaultJobTimeoutMinutes": int,
         "skipAppResign": bool,
     },
     total=False,
 )
 
+ListArtifactsResultTypeDef = TypedDict(
+    "ListArtifactsResultTypeDef",
+    {
+        "artifacts": List[ArtifactTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateDevicePoolRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDevicePoolRequestRequestTypeDef",
     {
         "projectArn": str,
         "name": str,
         "rules": Sequence[RuleTypeDef],
     },
@@ -1563,37 +1890,19 @@
 
 class UpdateDevicePoolRequestRequestTypeDef(
     _RequiredUpdateDevicePoolRequestRequestTypeDef, _OptionalUpdateDevicePoolRequestRequestTypeDef
 ):
     pass
 
 
-CreateTestGridUrlResultTypeDef = TypedDict(
-    "CreateTestGridUrlResultTypeDef",
-    {
-        "url": str,
-        "expires": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListArtifactsResultTypeDef = TypedDict(
-    "ListArtifactsResultTypeDef",
-    {
-        "artifacts": List[ArtifactTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 CreateInstanceProfileResultTypeDef = TypedDict(
     "CreateInstanceProfileResultTypeDef",
     {
         "instanceProfile": InstanceProfileTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeviceInstanceTypeDef = TypedDict(
     "DeviceInstanceTypeDef",
     {
         "arn": str,
@@ -1606,65 +1915,65 @@
     total=False,
 )
 
 GetInstanceProfileResultTypeDef = TypedDict(
     "GetInstanceProfileResultTypeDef",
     {
         "instanceProfile": InstanceProfileTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListInstanceProfilesResultTypeDef = TypedDict(
     "ListInstanceProfilesResultTypeDef",
     {
         "instanceProfiles": List[InstanceProfileTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateInstanceProfileResultTypeDef = TypedDict(
     "UpdateInstanceProfileResultTypeDef",
     {
         "instanceProfile": InstanceProfileTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateNetworkProfileResultTypeDef = TypedDict(
     "CreateNetworkProfileResultTypeDef",
     {
         "networkProfile": NetworkProfileTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetNetworkProfileResultTypeDef = TypedDict(
     "GetNetworkProfileResultTypeDef",
     {
         "networkProfile": NetworkProfileTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListNetworkProfilesResultTypeDef = TypedDict(
     "ListNetworkProfilesResultTypeDef",
     {
         "networkProfiles": List[NetworkProfileTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateNetworkProfileResultTypeDef = TypedDict(
     "UpdateNetworkProfileResultTypeDef",
     {
         "networkProfile": NetworkProfileTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateProjectRequestRequestTypeDef = TypedDict(
     "_RequiredCreateProjectRequestRequestTypeDef",
     {
         "name": str,
@@ -1812,81 +2121,81 @@
     pass
 
 
 CreateUploadResultTypeDef = TypedDict(
     "CreateUploadResultTypeDef",
     {
         "upload": UploadTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetUploadResultTypeDef = TypedDict(
     "GetUploadResultTypeDef",
     {
         "upload": UploadTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InstallToRemoteAccessSessionResultTypeDef = TypedDict(
     "InstallToRemoteAccessSessionResultTypeDef",
     {
         "appUpload": UploadTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListUploadsResultTypeDef = TypedDict(
     "ListUploadsResultTypeDef",
     {
         "uploads": List[UploadTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateUploadResultTypeDef = TypedDict(
     "UpdateUploadResultTypeDef",
     {
         "upload": UploadTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateVPCEConfigurationResultTypeDef = TypedDict(
     "CreateVPCEConfigurationResultTypeDef",
     {
         "vpceConfiguration": VPCEConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetVPCEConfigurationResultTypeDef = TypedDict(
     "GetVPCEConfigurationResultTypeDef",
     {
         "vpceConfiguration": VPCEConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVPCEConfigurationsResultTypeDef = TypedDict(
     "ListVPCEConfigurationsResultTypeDef",
     {
         "vpceConfigurations": List[VPCEConfigurationTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateVPCEConfigurationResultTypeDef = TypedDict(
     "UpdateVPCEConfigurationResultTypeDef",
     {
         "vpceConfiguration": VPCEConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeviceSelectionConfigurationTypeDef = TypedDict(
     "DeviceSelectionConfigurationTypeDef",
     {
         "filters": Sequence[DeviceFilterTypeDef],
@@ -1900,14 +2209,24 @@
         "filters": List[DeviceFilterTypeDef],
         "matchedDevicesCount": int,
         "maxDevices": int,
     },
     total=False,
 )
 
+ListDevicesRequestListDevicesPaginateTypeDef = TypedDict(
+    "ListDevicesRequestListDevicesPaginateTypeDef",
+    {
+        "arn": str,
+        "filters": Sequence[DeviceFilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDevicesRequestRequestTypeDef = TypedDict(
     "ListDevicesRequestRequestTypeDef",
     {
         "arn": str,
         "nextToken": str,
         "filters": Sequence[DeviceFilterTypeDef],
     },
@@ -1946,373 +2265,54 @@
         "counters": CountersTypeDef,
         "message": str,
         "deviceMinutes": DeviceMinutesTypeDef,
     },
     total=False,
 )
 
-GetOfferingStatusRequestGetOfferingStatusPaginateTypeDef = TypedDict(
-    "GetOfferingStatusRequestGetOfferingStatusPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListArtifactsRequestListArtifactsPaginateTypeDef = TypedDict(
-    "_RequiredListArtifactsRequestListArtifactsPaginateTypeDef",
-    {
-        "arn": str,
-        "type": ArtifactCategoryType,
-    },
-)
-_OptionalListArtifactsRequestListArtifactsPaginateTypeDef = TypedDict(
-    "_OptionalListArtifactsRequestListArtifactsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListArtifactsRequestListArtifactsPaginateTypeDef(
-    _RequiredListArtifactsRequestListArtifactsPaginateTypeDef,
-    _OptionalListArtifactsRequestListArtifactsPaginateTypeDef,
-):
-    pass
-
-
-ListDeviceInstancesRequestListDeviceInstancesPaginateTypeDef = TypedDict(
-    "ListDeviceInstancesRequestListDeviceInstancesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListDevicePoolsRequestListDevicePoolsPaginateTypeDef = TypedDict(
-    "_RequiredListDevicePoolsRequestListDevicePoolsPaginateTypeDef",
-    {
-        "arn": str,
-    },
-)
-_OptionalListDevicePoolsRequestListDevicePoolsPaginateTypeDef = TypedDict(
-    "_OptionalListDevicePoolsRequestListDevicePoolsPaginateTypeDef",
-    {
-        "type": DevicePoolTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListDevicePoolsRequestListDevicePoolsPaginateTypeDef(
-    _RequiredListDevicePoolsRequestListDevicePoolsPaginateTypeDef,
-    _OptionalListDevicePoolsRequestListDevicePoolsPaginateTypeDef,
-):
-    pass
-
-
-ListDevicesRequestListDevicesPaginateTypeDef = TypedDict(
-    "ListDevicesRequestListDevicesPaginateTypeDef",
-    {
-        "arn": str,
-        "filters": Sequence[DeviceFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListInstanceProfilesRequestListInstanceProfilesPaginateTypeDef = TypedDict(
-    "ListInstanceProfilesRequestListInstanceProfilesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListJobsRequestListJobsPaginateTypeDef = TypedDict(
-    "_RequiredListJobsRequestListJobsPaginateTypeDef",
-    {
-        "arn": str,
-    },
-)
-_OptionalListJobsRequestListJobsPaginateTypeDef = TypedDict(
-    "_OptionalListJobsRequestListJobsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListJobsRequestListJobsPaginateTypeDef(
-    _RequiredListJobsRequestListJobsPaginateTypeDef, _OptionalListJobsRequestListJobsPaginateTypeDef
-):
-    pass
-
-
-_RequiredListNetworkProfilesRequestListNetworkProfilesPaginateTypeDef = TypedDict(
-    "_RequiredListNetworkProfilesRequestListNetworkProfilesPaginateTypeDef",
-    {
-        "arn": str,
-    },
-)
-_OptionalListNetworkProfilesRequestListNetworkProfilesPaginateTypeDef = TypedDict(
-    "_OptionalListNetworkProfilesRequestListNetworkProfilesPaginateTypeDef",
-    {
-        "type": NetworkProfileTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListNetworkProfilesRequestListNetworkProfilesPaginateTypeDef(
-    _RequiredListNetworkProfilesRequestListNetworkProfilesPaginateTypeDef,
-    _OptionalListNetworkProfilesRequestListNetworkProfilesPaginateTypeDef,
-):
-    pass
-
-
-ListOfferingPromotionsRequestListOfferingPromotionsPaginateTypeDef = TypedDict(
-    "ListOfferingPromotionsRequestListOfferingPromotionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListOfferingTransactionsRequestListOfferingTransactionsPaginateTypeDef = TypedDict(
-    "ListOfferingTransactionsRequestListOfferingTransactionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListOfferingsRequestListOfferingsPaginateTypeDef = TypedDict(
-    "ListOfferingsRequestListOfferingsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListProjectsRequestListProjectsPaginateTypeDef = TypedDict(
-    "ListProjectsRequestListProjectsPaginateTypeDef",
-    {
-        "arn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListRemoteAccessSessionsRequestListRemoteAccessSessionsPaginateTypeDef = TypedDict(
-    "_RequiredListRemoteAccessSessionsRequestListRemoteAccessSessionsPaginateTypeDef",
-    {
-        "arn": str,
-    },
-)
-_OptionalListRemoteAccessSessionsRequestListRemoteAccessSessionsPaginateTypeDef = TypedDict(
-    "_OptionalListRemoteAccessSessionsRequestListRemoteAccessSessionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListRemoteAccessSessionsRequestListRemoteAccessSessionsPaginateTypeDef(
-    _RequiredListRemoteAccessSessionsRequestListRemoteAccessSessionsPaginateTypeDef,
-    _OptionalListRemoteAccessSessionsRequestListRemoteAccessSessionsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListRunsRequestListRunsPaginateTypeDef = TypedDict(
-    "_RequiredListRunsRequestListRunsPaginateTypeDef",
-    {
-        "arn": str,
-    },
-)
-_OptionalListRunsRequestListRunsPaginateTypeDef = TypedDict(
-    "_OptionalListRunsRequestListRunsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListRunsRequestListRunsPaginateTypeDef(
-    _RequiredListRunsRequestListRunsPaginateTypeDef, _OptionalListRunsRequestListRunsPaginateTypeDef
-):
-    pass
-
-
-_RequiredListSamplesRequestListSamplesPaginateTypeDef = TypedDict(
-    "_RequiredListSamplesRequestListSamplesPaginateTypeDef",
-    {
-        "arn": str,
-    },
-)
-_OptionalListSamplesRequestListSamplesPaginateTypeDef = TypedDict(
-    "_OptionalListSamplesRequestListSamplesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListSamplesRequestListSamplesPaginateTypeDef(
-    _RequiredListSamplesRequestListSamplesPaginateTypeDef,
-    _OptionalListSamplesRequestListSamplesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListSuitesRequestListSuitesPaginateTypeDef = TypedDict(
-    "_RequiredListSuitesRequestListSuitesPaginateTypeDef",
-    {
-        "arn": str,
-    },
-)
-_OptionalListSuitesRequestListSuitesPaginateTypeDef = TypedDict(
-    "_OptionalListSuitesRequestListSuitesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListSuitesRequestListSuitesPaginateTypeDef(
-    _RequiredListSuitesRequestListSuitesPaginateTypeDef,
-    _OptionalListSuitesRequestListSuitesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListTestsRequestListTestsPaginateTypeDef = TypedDict(
-    "_RequiredListTestsRequestListTestsPaginateTypeDef",
-    {
-        "arn": str,
-    },
-)
-_OptionalListTestsRequestListTestsPaginateTypeDef = TypedDict(
-    "_OptionalListTestsRequestListTestsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListTestsRequestListTestsPaginateTypeDef(
-    _RequiredListTestsRequestListTestsPaginateTypeDef,
-    _OptionalListTestsRequestListTestsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListUniqueProblemsRequestListUniqueProblemsPaginateTypeDef = TypedDict(
-    "_RequiredListUniqueProblemsRequestListUniqueProblemsPaginateTypeDef",
-    {
-        "arn": str,
-    },
-)
-_OptionalListUniqueProblemsRequestListUniqueProblemsPaginateTypeDef = TypedDict(
-    "_OptionalListUniqueProblemsRequestListUniqueProblemsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListUniqueProblemsRequestListUniqueProblemsPaginateTypeDef(
-    _RequiredListUniqueProblemsRequestListUniqueProblemsPaginateTypeDef,
-    _OptionalListUniqueProblemsRequestListUniqueProblemsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListUploadsRequestListUploadsPaginateTypeDef = TypedDict(
-    "_RequiredListUploadsRequestListUploadsPaginateTypeDef",
-    {
-        "arn": str,
-    },
-)
-_OptionalListUploadsRequestListUploadsPaginateTypeDef = TypedDict(
-    "_OptionalListUploadsRequestListUploadsPaginateTypeDef",
-    {
-        "type": UploadTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListUploadsRequestListUploadsPaginateTypeDef(
-    _RequiredListUploadsRequestListUploadsPaginateTypeDef,
-    _OptionalListUploadsRequestListUploadsPaginateTypeDef,
-):
-    pass
-
-
-ListVPCEConfigurationsRequestListVPCEConfigurationsPaginateTypeDef = TypedDict(
-    "ListVPCEConfigurationsRequestListVPCEConfigurationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 GetTestGridSessionResultTypeDef = TypedDict(
     "GetTestGridSessionResultTypeDef",
     {
         "testGridSession": TestGridSessionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTestGridSessionsResultTypeDef = TypedDict(
     "ListTestGridSessionsResultTypeDef",
     {
         "testGridSessions": List[TestGridSessionTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListOfferingPromotionsResultTypeDef = TypedDict(
     "ListOfferingPromotionsResultTypeDef",
     {
         "offeringPromotions": List[OfferingPromotionTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSamplesResultTypeDef = TypedDict(
     "ListSamplesResultTypeDef",
     {
         "samples": List[SampleTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
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
@@ -2321,24 +2321,24 @@
 )
 
 ListTestGridSessionActionsResultTypeDef = TypedDict(
     "ListTestGridSessionActionsResultTypeDef",
     {
         "actions": List[TestGridSessionActionTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTestGridSessionArtifactsResultTypeDef = TypedDict(
     "ListTestGridSessionArtifactsResultTypeDef",
     {
         "artifacts": List[TestGridSessionArtifactTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RecurringChargeTypeDef = TypedDict(
     "RecurringChargeTypeDef",
     {
         "cost": MonetaryAmountTypeDef,
@@ -2363,48 +2363,48 @@
     total=False,
 )
 
 GetAccountSettingsResultTypeDef = TypedDict(
     "GetAccountSettingsResultTypeDef",
     {
         "accountSettings": AccountSettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDevicePoolResultTypeDef = TypedDict(
     "CreateDevicePoolResultTypeDef",
     {
         "devicePool": DevicePoolTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDevicePoolResultTypeDef = TypedDict(
     "GetDevicePoolResultTypeDef",
     {
         "devicePool": DevicePoolTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDevicePoolsResultTypeDef = TypedDict(
     "ListDevicePoolsResultTypeDef",
     {
         "devicePools": List[DevicePoolTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDevicePoolResultTypeDef = TypedDict(
     "UpdateDevicePoolResultTypeDef",
     {
         "devicePool": DevicePoolTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeviceTypeDef = TypedDict(
     "DeviceTypeDef",
     {
         "arn": str,
@@ -2432,98 +2432,98 @@
     total=False,
 )
 
 GetDeviceInstanceResultTypeDef = TypedDict(
     "GetDeviceInstanceResultTypeDef",
     {
         "deviceInstance": DeviceInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDeviceInstancesResultTypeDef = TypedDict(
     "ListDeviceInstancesResultTypeDef",
     {
         "deviceInstances": List[DeviceInstanceTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDeviceInstanceResultTypeDef = TypedDict(
     "UpdateDeviceInstanceResultTypeDef",
     {
         "deviceInstance": DeviceInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateProjectResultTypeDef = TypedDict(
     "CreateProjectResultTypeDef",
     {
         "project": ProjectTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetProjectResultTypeDef = TypedDict(
     "GetProjectResultTypeDef",
     {
         "project": ProjectTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProjectsResultTypeDef = TypedDict(
     "ListProjectsResultTypeDef",
     {
         "projects": List[ProjectTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateProjectResultTypeDef = TypedDict(
     "UpdateProjectResultTypeDef",
     {
         "project": ProjectTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateTestGridProjectResultTypeDef = TypedDict(
     "CreateTestGridProjectResultTypeDef",
     {
         "testGridProject": TestGridProjectTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTestGridProjectResultTypeDef = TypedDict(
     "GetTestGridProjectResultTypeDef",
     {
         "testGridProject": TestGridProjectTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTestGridProjectsResultTypeDef = TypedDict(
     "ListTestGridProjectsResultTypeDef",
     {
         "testGridProjects": List[TestGridProjectTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateTestGridProjectResultTypeDef = TypedDict(
     "UpdateTestGridProjectResultTypeDef",
     {
         "testGridProject": TestGridProjectTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RunTypeDef = TypedDict(
     "RunTypeDef",
     {
         "arn": str,
@@ -2562,41 +2562,41 @@
     total=False,
 )
 
 GetSuiteResultTypeDef = TypedDict(
     "GetSuiteResultTypeDef",
     {
         "suite": SuiteTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSuitesResultTypeDef = TypedDict(
     "ListSuitesResultTypeDef",
     {
         "suites": List[SuiteTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTestResultTypeDef = TypedDict(
     "GetTestResultTypeDef",
     {
         "test": TestTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTestsResultTypeDef = TypedDict(
     "ListTestsResultTypeDef",
     {
         "tests": List[TestTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OfferingTypeDef = TypedDict(
     "OfferingTypeDef",
     {
         "id": str,
@@ -2670,15 +2670,15 @@
     total=False,
 )
 
 GetDeviceResultTypeDef = TypedDict(
     "GetDeviceResultTypeDef",
     {
         "device": DeviceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 JobTypeDef = TypedDict(
     "JobTypeDef",
     {
         "arn": str,
@@ -2701,15 +2701,15 @@
 )
 
 ListDevicesResultTypeDef = TypedDict(
     "ListDevicesResultTypeDef",
     {
         "devices": List[DeviceTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ProblemTypeDef = TypedDict(
     "ProblemTypeDef",
     {
         "run": ProblemDetailTypeDef,
@@ -2752,49 +2752,49 @@
     total=False,
 )
 
 GetRunResultTypeDef = TypedDict(
     "GetRunResultTypeDef",
     {
         "run": RunTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRunsResultTypeDef = TypedDict(
     "ListRunsResultTypeDef",
     {
         "runs": List[RunTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ScheduleRunResultTypeDef = TypedDict(
     "ScheduleRunResultTypeDef",
     {
         "run": RunTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopRunResultTypeDef = TypedDict(
     "StopRunResultTypeDef",
     {
         "run": RunTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListOfferingsResultTypeDef = TypedDict(
     "ListOfferingsResultTypeDef",
     {
         "offerings": List[OfferingTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OfferingStatusTypeDef = TypedDict(
     "OfferingStatusTypeDef",
     {
         "type": OfferingTransactionTypeType,
@@ -2806,40 +2806,40 @@
 )
 
 GetDevicePoolCompatibilityResultTypeDef = TypedDict(
     "GetDevicePoolCompatibilityResultTypeDef",
     {
         "compatibleDevices": List[DevicePoolCompatibilityResultTypeDef],
         "incompatibleDevices": List[DevicePoolCompatibilityResultTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetJobResultTypeDef = TypedDict(
     "GetJobResultTypeDef",
     {
         "job": JobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListJobsResultTypeDef = TypedDict(
     "ListJobsResultTypeDef",
     {
         "jobs": List[JobTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopJobResultTypeDef = TypedDict(
     "StopJobResultTypeDef",
     {
         "job": JobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UniqueProblemTypeDef = TypedDict(
     "UniqueProblemTypeDef",
     {
         "message": str,
@@ -2848,50 +2848,50 @@
     total=False,
 )
 
 CreateRemoteAccessSessionResultTypeDef = TypedDict(
     "CreateRemoteAccessSessionResultTypeDef",
     {
         "remoteAccessSession": RemoteAccessSessionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRemoteAccessSessionResultTypeDef = TypedDict(
     "GetRemoteAccessSessionResultTypeDef",
     {
         "remoteAccessSession": RemoteAccessSessionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRemoteAccessSessionsResultTypeDef = TypedDict(
     "ListRemoteAccessSessionsResultTypeDef",
     {
         "remoteAccessSessions": List[RemoteAccessSessionTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopRemoteAccessSessionResultTypeDef = TypedDict(
     "StopRemoteAccessSessionResultTypeDef",
     {
         "remoteAccessSession": RemoteAccessSessionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetOfferingStatusResultTypeDef = TypedDict(
     "GetOfferingStatusResultTypeDef",
     {
         "current": Dict[str, OfferingStatusTypeDef],
         "nextPeriod": Dict[str, OfferingStatusTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OfferingTransactionTypeDef = TypedDict(
     "OfferingTransactionTypeDef",
     {
         "offeringStatus": OfferingStatusTypeDef,
@@ -2904,35 +2904,35 @@
 )
 
 ListUniqueProblemsResultTypeDef = TypedDict(
     "ListUniqueProblemsResultTypeDef",
     {
         "uniqueProblems": Dict[ExecutionResultType, List[UniqueProblemTypeDef]],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListOfferingTransactionsResultTypeDef = TypedDict(
     "ListOfferingTransactionsResultTypeDef",
     {
         "offeringTransactions": List[OfferingTransactionTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PurchaseOfferingResultTypeDef = TypedDict(
     "PurchaseOfferingResultTypeDef",
     {
         "offeringTransaction": OfferingTransactionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RenewOfferingResultTypeDef = TypedDict(
     "RenewOfferingResultTypeDef",
     {
         "offeringTransaction": OfferingTransactionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-devicefarm-2.5.0.post1/types_aiobotocore_devicefarm/type_defs.pyi` & `types-aiobotocore-devicefarm-2.5.1/types_aiobotocore_devicefarm/type_defs.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -54,23 +54,23 @@
 
 __all__ = (
     "TrialMinutesTypeDef",
     "ArtifactTypeDef",
     "CPUTypeDef",
     "CountersTypeDef",
     "RuleTypeDef",
-    "ResponseMetadataTypeDef",
     "CreateInstanceProfileRequestRequestTypeDef",
     "InstanceProfileTypeDef",
     "CreateNetworkProfileRequestRequestTypeDef",
     "NetworkProfileTypeDef",
     "VpcConfigTypeDef",
     "CreateRemoteAccessSessionConfigurationTypeDef",
     "TestGridVpcConfigTypeDef",
     "CreateTestGridUrlRequestRequestTypeDef",
+    "CreateTestGridUrlResultTypeDef",
     "CreateUploadRequestRequestTypeDef",
     "UploadTypeDef",
     "CreateVPCEConfigurationRequestRequestTypeDef",
     "VPCEConfigurationTypeDef",
     "CustomerArtifactPathsTypeDef",
     "DeleteDevicePoolRequestRequestTypeDef",
     "DeleteInstanceProfileRequestRequestTypeDef",
@@ -89,76 +89,95 @@
     "GetDeviceInstanceRequestRequestTypeDef",
     "ScheduleRunTestTypeDef",
     "GetDevicePoolRequestRequestTypeDef",
     "GetDeviceRequestRequestTypeDef",
     "GetInstanceProfileRequestRequestTypeDef",
     "GetJobRequestRequestTypeDef",
     "GetNetworkProfileRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "GetOfferingStatusRequestGetOfferingStatusPaginateTypeDef",
     "GetOfferingStatusRequestRequestTypeDef",
     "GetProjectRequestRequestTypeDef",
     "GetRemoteAccessSessionRequestRequestTypeDef",
     "GetRunRequestRequestTypeDef",
     "GetSuiteRequestRequestTypeDef",
     "GetTestGridProjectRequestRequestTypeDef",
     "GetTestGridSessionRequestRequestTypeDef",
     "TestGridSessionTypeDef",
     "GetTestRequestRequestTypeDef",
     "GetUploadRequestRequestTypeDef",
     "GetVPCEConfigurationRequestRequestTypeDef",
     "InstallToRemoteAccessSessionRequestRequestTypeDef",
+    "ListArtifactsRequestListArtifactsPaginateTypeDef",
     "ListArtifactsRequestRequestTypeDef",
+    "ListDeviceInstancesRequestListDeviceInstancesPaginateTypeDef",
     "ListDeviceInstancesRequestRequestTypeDef",
+    "ListDevicePoolsRequestListDevicePoolsPaginateTypeDef",
     "ListDevicePoolsRequestRequestTypeDef",
+    "ListInstanceProfilesRequestListInstanceProfilesPaginateTypeDef",
     "ListInstanceProfilesRequestRequestTypeDef",
+    "ListJobsRequestListJobsPaginateTypeDef",
     "ListJobsRequestRequestTypeDef",
+    "ListNetworkProfilesRequestListNetworkProfilesPaginateTypeDef",
     "ListNetworkProfilesRequestRequestTypeDef",
+    "ListOfferingPromotionsRequestListOfferingPromotionsPaginateTypeDef",
     "ListOfferingPromotionsRequestRequestTypeDef",
     "OfferingPromotionTypeDef",
+    "ListOfferingTransactionsRequestListOfferingTransactionsPaginateTypeDef",
     "ListOfferingTransactionsRequestRequestTypeDef",
+    "ListOfferingsRequestListOfferingsPaginateTypeDef",
     "ListOfferingsRequestRequestTypeDef",
+    "ListProjectsRequestListProjectsPaginateTypeDef",
     "ListProjectsRequestRequestTypeDef",
+    "ListRemoteAccessSessionsRequestListRemoteAccessSessionsPaginateTypeDef",
     "ListRemoteAccessSessionsRequestRequestTypeDef",
+    "ListRunsRequestListRunsPaginateTypeDef",
     "ListRunsRequestRequestTypeDef",
+    "ListSamplesRequestListSamplesPaginateTypeDef",
     "ListSamplesRequestRequestTypeDef",
     "SampleTypeDef",
+    "ListSuitesRequestListSuitesPaginateTypeDef",
     "ListSuitesRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
     "TagTypeDef",
     "ListTestGridProjectsRequestRequestTypeDef",
     "ListTestGridSessionActionsRequestRequestTypeDef",
     "TestGridSessionActionTypeDef",
     "ListTestGridSessionArtifactsRequestRequestTypeDef",
     "TestGridSessionArtifactTypeDef",
     "ListTestGridSessionsRequestRequestTypeDef",
+    "ListTestsRequestListTestsPaginateTypeDef",
     "ListTestsRequestRequestTypeDef",
+    "ListUniqueProblemsRequestListUniqueProblemsPaginateTypeDef",
     "ListUniqueProblemsRequestRequestTypeDef",
+    "ListUploadsRequestListUploadsPaginateTypeDef",
     "ListUploadsRequestRequestTypeDef",
+    "ListVPCEConfigurationsRequestListVPCEConfigurationsPaginateTypeDef",
     "ListVPCEConfigurationsRequestRequestTypeDef",
     "LocationTypeDef",
     "MonetaryAmountTypeDef",
+    "PaginatorConfigTypeDef",
     "ProblemDetailTypeDef",
     "PurchaseOfferingRequestRequestTypeDef",
     "RadiosTypeDef",
     "RenewOfferingRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
     "StopJobRequestRequestTypeDef",
     "StopRemoteAccessSessionRequestRequestTypeDef",
     "StopRunRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateDeviceInstanceRequestRequestTypeDef",
     "UpdateInstanceProfileRequestRequestTypeDef",
     "UpdateNetworkProfileRequestRequestTypeDef",
     "UpdateUploadRequestRequestTypeDef",
     "UpdateVPCEConfigurationRequestRequestTypeDef",
     "AccountSettingsTypeDef",
+    "ListArtifactsResultTypeDef",
     "CreateDevicePoolRequestRequestTypeDef",
     "DevicePoolTypeDef",
     "UpdateDevicePoolRequestRequestTypeDef",
-    "CreateTestGridUrlResultTypeDef",
-    "ListArtifactsResultTypeDef",
     "CreateInstanceProfileResultTypeDef",
     "DeviceInstanceTypeDef",
     "GetInstanceProfileResultTypeDef",
     "ListInstanceProfilesResultTypeDef",
     "UpdateInstanceProfileResultTypeDef",
     "CreateNetworkProfileResultTypeDef",
     "GetNetworkProfileResultTypeDef",
@@ -178,37 +197,18 @@
     "UpdateUploadResultTypeDef",
     "CreateVPCEConfigurationResultTypeDef",
     "GetVPCEConfigurationResultTypeDef",
     "ListVPCEConfigurationsResultTypeDef",
     "UpdateVPCEConfigurationResultTypeDef",
     "DeviceSelectionConfigurationTypeDef",
     "DeviceSelectionResultTypeDef",
+    "ListDevicesRequestListDevicesPaginateTypeDef",
     "ListDevicesRequestRequestTypeDef",
     "SuiteTypeDef",
     "TestTypeDef",
-    "GetOfferingStatusRequestGetOfferingStatusPaginateTypeDef",
-    "ListArtifactsRequestListArtifactsPaginateTypeDef",
-    "ListDeviceInstancesRequestListDeviceInstancesPaginateTypeDef",
-    "ListDevicePoolsRequestListDevicePoolsPaginateTypeDef",
-    "ListDevicesRequestListDevicesPaginateTypeDef",
-    "ListInstanceProfilesRequestListInstanceProfilesPaginateTypeDef",
-    "ListJobsRequestListJobsPaginateTypeDef",
-    "ListNetworkProfilesRequestListNetworkProfilesPaginateTypeDef",
-    "ListOfferingPromotionsRequestListOfferingPromotionsPaginateTypeDef",
-    "ListOfferingTransactionsRequestListOfferingTransactionsPaginateTypeDef",
-    "ListOfferingsRequestListOfferingsPaginateTypeDef",
-    "ListProjectsRequestListProjectsPaginateTypeDef",
-    "ListRemoteAccessSessionsRequestListRemoteAccessSessionsPaginateTypeDef",
-    "ListRunsRequestListRunsPaginateTypeDef",
-    "ListSamplesRequestListSamplesPaginateTypeDef",
-    "ListSuitesRequestListSuitesPaginateTypeDef",
-    "ListTestsRequestListTestsPaginateTypeDef",
-    "ListUniqueProblemsRequestListUniqueProblemsPaginateTypeDef",
-    "ListUploadsRequestListUploadsPaginateTypeDef",
-    "ListVPCEConfigurationsRequestListVPCEConfigurationsPaginateTypeDef",
     "GetTestGridSessionResultTypeDef",
     "ListTestGridSessionsResultTypeDef",
     "ListOfferingPromotionsResultTypeDef",
     "ListSamplesResultTypeDef",
     "ListTagsForResourceResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "ListTestGridSessionActionsResultTypeDef",
@@ -320,25 +320,14 @@
         "attribute": DeviceAttributeType,
         "operator": RuleOperatorType,
         "value": str,
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
 _RequiredCreateInstanceProfileRequestRequestTypeDef = TypedDict(
     "_RequiredCreateInstanceProfileRequestRequestTypeDef",
     {
         "name": str,
     },
 )
 _OptionalCreateInstanceProfileRequestRequestTypeDef = TypedDict(
@@ -451,14 +440,23 @@
     "CreateTestGridUrlRequestRequestTypeDef",
     {
         "projectArn": str,
         "expiresInSeconds": int,
     },
 )
 
+CreateTestGridUrlResultTypeDef = TypedDict(
+    "CreateTestGridUrlResultTypeDef",
+    {
+        "url": str,
+        "expires": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateUploadRequestRequestTypeDef = TypedDict(
     "_RequiredCreateUploadRequestRequestTypeDef",
     {
         "projectArn": str,
         "name": str,
         "type": UploadTypeType,
     },
@@ -707,20 +705,18 @@
 GetNetworkProfileRequestRequestTypeDef = TypedDict(
     "GetNetworkProfileRequestRequestTypeDef",
     {
         "arn": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+GetOfferingStatusRequestGetOfferingStatusPaginateTypeDef = TypedDict(
+    "GetOfferingStatusRequestGetOfferingStatusPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 GetOfferingStatusRequestRequestTypeDef = TypedDict(
     "GetOfferingStatusRequestRequestTypeDef",
     {
@@ -812,14 +808,35 @@
     "InstallToRemoteAccessSessionRequestRequestTypeDef",
     {
         "remoteAccessSessionArn": str,
         "appArn": str,
     },
 )
 
+_RequiredListArtifactsRequestListArtifactsPaginateTypeDef = TypedDict(
+    "_RequiredListArtifactsRequestListArtifactsPaginateTypeDef",
+    {
+        "arn": str,
+        "type": ArtifactCategoryType,
+    },
+)
+_OptionalListArtifactsRequestListArtifactsPaginateTypeDef = TypedDict(
+    "_OptionalListArtifactsRequestListArtifactsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListArtifactsRequestListArtifactsPaginateTypeDef(
+    _RequiredListArtifactsRequestListArtifactsPaginateTypeDef,
+    _OptionalListArtifactsRequestListArtifactsPaginateTypeDef,
+):
+    pass
+
 _RequiredListArtifactsRequestRequestTypeDef = TypedDict(
     "_RequiredListArtifactsRequestRequestTypeDef",
     {
         "arn": str,
         "type": ArtifactCategoryType,
     },
 )
@@ -832,23 +849,52 @@
 )
 
 class ListArtifactsRequestRequestTypeDef(
     _RequiredListArtifactsRequestRequestTypeDef, _OptionalListArtifactsRequestRequestTypeDef
 ):
     pass
 
+ListDeviceInstancesRequestListDeviceInstancesPaginateTypeDef = TypedDict(
+    "ListDeviceInstancesRequestListDeviceInstancesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDeviceInstancesRequestRequestTypeDef = TypedDict(
     "ListDeviceInstancesRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+_RequiredListDevicePoolsRequestListDevicePoolsPaginateTypeDef = TypedDict(
+    "_RequiredListDevicePoolsRequestListDevicePoolsPaginateTypeDef",
+    {
+        "arn": str,
+    },
+)
+_OptionalListDevicePoolsRequestListDevicePoolsPaginateTypeDef = TypedDict(
+    "_OptionalListDevicePoolsRequestListDevicePoolsPaginateTypeDef",
+    {
+        "type": DevicePoolTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListDevicePoolsRequestListDevicePoolsPaginateTypeDef(
+    _RequiredListDevicePoolsRequestListDevicePoolsPaginateTypeDef,
+    _OptionalListDevicePoolsRequestListDevicePoolsPaginateTypeDef,
+):
+    pass
+
 _RequiredListDevicePoolsRequestRequestTypeDef = TypedDict(
     "_RequiredListDevicePoolsRequestRequestTypeDef",
     {
         "arn": str,
     },
 )
 _OptionalListDevicePoolsRequestRequestTypeDef = TypedDict(
@@ -861,23 +907,50 @@
 )
 
 class ListDevicePoolsRequestRequestTypeDef(
     _RequiredListDevicePoolsRequestRequestTypeDef, _OptionalListDevicePoolsRequestRequestTypeDef
 ):
     pass
 
+ListInstanceProfilesRequestListInstanceProfilesPaginateTypeDef = TypedDict(
+    "ListInstanceProfilesRequestListInstanceProfilesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListInstanceProfilesRequestRequestTypeDef = TypedDict(
     "ListInstanceProfilesRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+_RequiredListJobsRequestListJobsPaginateTypeDef = TypedDict(
+    "_RequiredListJobsRequestListJobsPaginateTypeDef",
+    {
+        "arn": str,
+    },
+)
+_OptionalListJobsRequestListJobsPaginateTypeDef = TypedDict(
+    "_OptionalListJobsRequestListJobsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListJobsRequestListJobsPaginateTypeDef(
+    _RequiredListJobsRequestListJobsPaginateTypeDef, _OptionalListJobsRequestListJobsPaginateTypeDef
+):
+    pass
+
 _RequiredListJobsRequestRequestTypeDef = TypedDict(
     "_RequiredListJobsRequestRequestTypeDef",
     {
         "arn": str,
     },
 )
 _OptionalListJobsRequestRequestTypeDef = TypedDict(
@@ -889,14 +962,35 @@
 )
 
 class ListJobsRequestRequestTypeDef(
     _RequiredListJobsRequestRequestTypeDef, _OptionalListJobsRequestRequestTypeDef
 ):
     pass
 
+_RequiredListNetworkProfilesRequestListNetworkProfilesPaginateTypeDef = TypedDict(
+    "_RequiredListNetworkProfilesRequestListNetworkProfilesPaginateTypeDef",
+    {
+        "arn": str,
+    },
+)
+_OptionalListNetworkProfilesRequestListNetworkProfilesPaginateTypeDef = TypedDict(
+    "_OptionalListNetworkProfilesRequestListNetworkProfilesPaginateTypeDef",
+    {
+        "type": NetworkProfileTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListNetworkProfilesRequestListNetworkProfilesPaginateTypeDef(
+    _RequiredListNetworkProfilesRequestListNetworkProfilesPaginateTypeDef,
+    _OptionalListNetworkProfilesRequestListNetworkProfilesPaginateTypeDef,
+):
+    pass
+
 _RequiredListNetworkProfilesRequestRequestTypeDef = TypedDict(
     "_RequiredListNetworkProfilesRequestRequestTypeDef",
     {
         "arn": str,
     },
 )
 _OptionalListNetworkProfilesRequestRequestTypeDef = TypedDict(
@@ -910,14 +1004,22 @@
 
 class ListNetworkProfilesRequestRequestTypeDef(
     _RequiredListNetworkProfilesRequestRequestTypeDef,
     _OptionalListNetworkProfilesRequestRequestTypeDef,
 ):
     pass
 
+ListOfferingPromotionsRequestListOfferingPromotionsPaginateTypeDef = TypedDict(
+    "ListOfferingPromotionsRequestListOfferingPromotionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListOfferingPromotionsRequestRequestTypeDef = TypedDict(
     "ListOfferingPromotionsRequestRequestTypeDef",
     {
         "nextToken": str,
     },
     total=False,
 )
@@ -927,39 +1029,84 @@
     {
         "id": str,
         "description": str,
     },
     total=False,
 )
 
+ListOfferingTransactionsRequestListOfferingTransactionsPaginateTypeDef = TypedDict(
+    "ListOfferingTransactionsRequestListOfferingTransactionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListOfferingTransactionsRequestRequestTypeDef = TypedDict(
     "ListOfferingTransactionsRequestRequestTypeDef",
     {
         "nextToken": str,
     },
     total=False,
 )
 
+ListOfferingsRequestListOfferingsPaginateTypeDef = TypedDict(
+    "ListOfferingsRequestListOfferingsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListOfferingsRequestRequestTypeDef = TypedDict(
     "ListOfferingsRequestRequestTypeDef",
     {
         "nextToken": str,
     },
     total=False,
 )
 
+ListProjectsRequestListProjectsPaginateTypeDef = TypedDict(
+    "ListProjectsRequestListProjectsPaginateTypeDef",
+    {
+        "arn": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListProjectsRequestRequestTypeDef = TypedDict(
     "ListProjectsRequestRequestTypeDef",
     {
         "arn": str,
         "nextToken": str,
     },
     total=False,
 )
 
+_RequiredListRemoteAccessSessionsRequestListRemoteAccessSessionsPaginateTypeDef = TypedDict(
+    "_RequiredListRemoteAccessSessionsRequestListRemoteAccessSessionsPaginateTypeDef",
+    {
+        "arn": str,
+    },
+)
+_OptionalListRemoteAccessSessionsRequestListRemoteAccessSessionsPaginateTypeDef = TypedDict(
+    "_OptionalListRemoteAccessSessionsRequestListRemoteAccessSessionsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListRemoteAccessSessionsRequestListRemoteAccessSessionsPaginateTypeDef(
+    _RequiredListRemoteAccessSessionsRequestListRemoteAccessSessionsPaginateTypeDef,
+    _OptionalListRemoteAccessSessionsRequestListRemoteAccessSessionsPaginateTypeDef,
+):
+    pass
+
 _RequiredListRemoteAccessSessionsRequestRequestTypeDef = TypedDict(
     "_RequiredListRemoteAccessSessionsRequestRequestTypeDef",
     {
         "arn": str,
     },
 )
 _OptionalListRemoteAccessSessionsRequestRequestTypeDef = TypedDict(
@@ -972,14 +1119,33 @@
 
 class ListRemoteAccessSessionsRequestRequestTypeDef(
     _RequiredListRemoteAccessSessionsRequestRequestTypeDef,
     _OptionalListRemoteAccessSessionsRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListRunsRequestListRunsPaginateTypeDef = TypedDict(
+    "_RequiredListRunsRequestListRunsPaginateTypeDef",
+    {
+        "arn": str,
+    },
+)
+_OptionalListRunsRequestListRunsPaginateTypeDef = TypedDict(
+    "_OptionalListRunsRequestListRunsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListRunsRequestListRunsPaginateTypeDef(
+    _RequiredListRunsRequestListRunsPaginateTypeDef, _OptionalListRunsRequestListRunsPaginateTypeDef
+):
+    pass
+
 _RequiredListRunsRequestRequestTypeDef = TypedDict(
     "_RequiredListRunsRequestRequestTypeDef",
     {
         "arn": str,
     },
 )
 _OptionalListRunsRequestRequestTypeDef = TypedDict(
@@ -991,14 +1157,34 @@
 )
 
 class ListRunsRequestRequestTypeDef(
     _RequiredListRunsRequestRequestTypeDef, _OptionalListRunsRequestRequestTypeDef
 ):
     pass
 
+_RequiredListSamplesRequestListSamplesPaginateTypeDef = TypedDict(
+    "_RequiredListSamplesRequestListSamplesPaginateTypeDef",
+    {
+        "arn": str,
+    },
+)
+_OptionalListSamplesRequestListSamplesPaginateTypeDef = TypedDict(
+    "_OptionalListSamplesRequestListSamplesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListSamplesRequestListSamplesPaginateTypeDef(
+    _RequiredListSamplesRequestListSamplesPaginateTypeDef,
+    _OptionalListSamplesRequestListSamplesPaginateTypeDef,
+):
+    pass
+
 _RequiredListSamplesRequestRequestTypeDef = TypedDict(
     "_RequiredListSamplesRequestRequestTypeDef",
     {
         "arn": str,
     },
 )
 _OptionalListSamplesRequestRequestTypeDef = TypedDict(
@@ -1020,14 +1206,34 @@
         "arn": str,
         "type": SampleTypeType,
         "url": str,
     },
     total=False,
 )
 
+_RequiredListSuitesRequestListSuitesPaginateTypeDef = TypedDict(
+    "_RequiredListSuitesRequestListSuitesPaginateTypeDef",
+    {
+        "arn": str,
+    },
+)
+_OptionalListSuitesRequestListSuitesPaginateTypeDef = TypedDict(
+    "_OptionalListSuitesRequestListSuitesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListSuitesRequestListSuitesPaginateTypeDef(
+    _RequiredListSuitesRequestListSuitesPaginateTypeDef,
+    _OptionalListSuitesRequestListSuitesPaginateTypeDef,
+):
+    pass
+
 _RequiredListSuitesRequestRequestTypeDef = TypedDict(
     "_RequiredListSuitesRequestRequestTypeDef",
     {
         "arn": str,
     },
 )
 _OptionalListSuitesRequestRequestTypeDef = TypedDict(
@@ -1154,14 +1360,34 @@
 
 class ListTestGridSessionsRequestRequestTypeDef(
     _RequiredListTestGridSessionsRequestRequestTypeDef,
     _OptionalListTestGridSessionsRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListTestsRequestListTestsPaginateTypeDef = TypedDict(
+    "_RequiredListTestsRequestListTestsPaginateTypeDef",
+    {
+        "arn": str,
+    },
+)
+_OptionalListTestsRequestListTestsPaginateTypeDef = TypedDict(
+    "_OptionalListTestsRequestListTestsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListTestsRequestListTestsPaginateTypeDef(
+    _RequiredListTestsRequestListTestsPaginateTypeDef,
+    _OptionalListTestsRequestListTestsPaginateTypeDef,
+):
+    pass
+
 _RequiredListTestsRequestRequestTypeDef = TypedDict(
     "_RequiredListTestsRequestRequestTypeDef",
     {
         "arn": str,
     },
 )
 _OptionalListTestsRequestRequestTypeDef = TypedDict(
@@ -1173,14 +1399,34 @@
 )
 
 class ListTestsRequestRequestTypeDef(
     _RequiredListTestsRequestRequestTypeDef, _OptionalListTestsRequestRequestTypeDef
 ):
     pass
 
+_RequiredListUniqueProblemsRequestListUniqueProblemsPaginateTypeDef = TypedDict(
+    "_RequiredListUniqueProblemsRequestListUniqueProblemsPaginateTypeDef",
+    {
+        "arn": str,
+    },
+)
+_OptionalListUniqueProblemsRequestListUniqueProblemsPaginateTypeDef = TypedDict(
+    "_OptionalListUniqueProblemsRequestListUniqueProblemsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListUniqueProblemsRequestListUniqueProblemsPaginateTypeDef(
+    _RequiredListUniqueProblemsRequestListUniqueProblemsPaginateTypeDef,
+    _OptionalListUniqueProblemsRequestListUniqueProblemsPaginateTypeDef,
+):
+    pass
+
 _RequiredListUniqueProblemsRequestRequestTypeDef = TypedDict(
     "_RequiredListUniqueProblemsRequestRequestTypeDef",
     {
         "arn": str,
     },
 )
 _OptionalListUniqueProblemsRequestRequestTypeDef = TypedDict(
@@ -1193,14 +1439,35 @@
 
 class ListUniqueProblemsRequestRequestTypeDef(
     _RequiredListUniqueProblemsRequestRequestTypeDef,
     _OptionalListUniqueProblemsRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListUploadsRequestListUploadsPaginateTypeDef = TypedDict(
+    "_RequiredListUploadsRequestListUploadsPaginateTypeDef",
+    {
+        "arn": str,
+    },
+)
+_OptionalListUploadsRequestListUploadsPaginateTypeDef = TypedDict(
+    "_OptionalListUploadsRequestListUploadsPaginateTypeDef",
+    {
+        "type": UploadTypeType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListUploadsRequestListUploadsPaginateTypeDef(
+    _RequiredListUploadsRequestListUploadsPaginateTypeDef,
+    _OptionalListUploadsRequestListUploadsPaginateTypeDef,
+):
+    pass
+
 _RequiredListUploadsRequestRequestTypeDef = TypedDict(
     "_RequiredListUploadsRequestRequestTypeDef",
     {
         "arn": str,
     },
 )
 _OptionalListUploadsRequestRequestTypeDef = TypedDict(
@@ -1213,14 +1480,22 @@
 )
 
 class ListUploadsRequestRequestTypeDef(
     _RequiredListUploadsRequestRequestTypeDef, _OptionalListUploadsRequestRequestTypeDef
 ):
     pass
 
+ListVPCEConfigurationsRequestListVPCEConfigurationsPaginateTypeDef = TypedDict(
+    "ListVPCEConfigurationsRequestListVPCEConfigurationsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListVPCEConfigurationsRequestRequestTypeDef = TypedDict(
     "ListVPCEConfigurationsRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -1239,14 +1514,24 @@
     {
         "amount": float,
         "currencyCode": Literal["USD"],
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
 ProblemDetailTypeDef = TypedDict(
     "ProblemDetailTypeDef",
     {
         "arn": str,
         "name": str,
     },
     total=False,
@@ -1287,14 +1572,25 @@
     "RenewOfferingRequestRequestTypeDef",
     {
         "offeringId": str,
         "quantity": int,
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
 StopJobRequestRequestTypeDef = TypedDict(
     "StopJobRequestRequestTypeDef",
     {
         "arn": str,
     },
 )
 
@@ -1450,14 +1746,23 @@
         "maxSlots": Dict[str, int],
         "defaultJobTimeoutMinutes": int,
         "skipAppResign": bool,
     },
     total=False,
 )
 
+ListArtifactsResultTypeDef = TypedDict(
+    "ListArtifactsResultTypeDef",
+    {
+        "artifacts": List[ArtifactTypeDef],
+        "nextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateDevicePoolRequestRequestTypeDef = TypedDict(
     "_RequiredCreateDevicePoolRequestRequestTypeDef",
     {
         "projectArn": str,
         "name": str,
         "rules": Sequence[RuleTypeDef],
     },
@@ -1508,37 +1813,19 @@
 )
 
 class UpdateDevicePoolRequestRequestTypeDef(
     _RequiredUpdateDevicePoolRequestRequestTypeDef, _OptionalUpdateDevicePoolRequestRequestTypeDef
 ):
     pass
 
-CreateTestGridUrlResultTypeDef = TypedDict(
-    "CreateTestGridUrlResultTypeDef",
-    {
-        "url": str,
-        "expires": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListArtifactsResultTypeDef = TypedDict(
-    "ListArtifactsResultTypeDef",
-    {
-        "artifacts": List[ArtifactTypeDef],
-        "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 CreateInstanceProfileResultTypeDef = TypedDict(
     "CreateInstanceProfileResultTypeDef",
     {
         "instanceProfile": InstanceProfileTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeviceInstanceTypeDef = TypedDict(
     "DeviceInstanceTypeDef",
     {
         "arn": str,
@@ -1551,65 +1838,65 @@
     total=False,
 )
 
 GetInstanceProfileResultTypeDef = TypedDict(
     "GetInstanceProfileResultTypeDef",
     {
         "instanceProfile": InstanceProfileTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListInstanceProfilesResultTypeDef = TypedDict(
     "ListInstanceProfilesResultTypeDef",
     {
         "instanceProfiles": List[InstanceProfileTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateInstanceProfileResultTypeDef = TypedDict(
     "UpdateInstanceProfileResultTypeDef",
     {
         "instanceProfile": InstanceProfileTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateNetworkProfileResultTypeDef = TypedDict(
     "CreateNetworkProfileResultTypeDef",
     {
         "networkProfile": NetworkProfileTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetNetworkProfileResultTypeDef = TypedDict(
     "GetNetworkProfileResultTypeDef",
     {
         "networkProfile": NetworkProfileTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListNetworkProfilesResultTypeDef = TypedDict(
     "ListNetworkProfilesResultTypeDef",
     {
         "networkProfiles": List[NetworkProfileTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateNetworkProfileResultTypeDef = TypedDict(
     "UpdateNetworkProfileResultTypeDef",
     {
         "networkProfile": NetworkProfileTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateProjectRequestRequestTypeDef = TypedDict(
     "_RequiredCreateProjectRequestRequestTypeDef",
     {
         "name": str,
@@ -1747,81 +2034,81 @@
 ):
     pass
 
 CreateUploadResultTypeDef = TypedDict(
     "CreateUploadResultTypeDef",
     {
         "upload": UploadTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetUploadResultTypeDef = TypedDict(
     "GetUploadResultTypeDef",
     {
         "upload": UploadTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InstallToRemoteAccessSessionResultTypeDef = TypedDict(
     "InstallToRemoteAccessSessionResultTypeDef",
     {
         "appUpload": UploadTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListUploadsResultTypeDef = TypedDict(
     "ListUploadsResultTypeDef",
     {
         "uploads": List[UploadTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateUploadResultTypeDef = TypedDict(
     "UpdateUploadResultTypeDef",
     {
         "upload": UploadTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateVPCEConfigurationResultTypeDef = TypedDict(
     "CreateVPCEConfigurationResultTypeDef",
     {
         "vpceConfiguration": VPCEConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetVPCEConfigurationResultTypeDef = TypedDict(
     "GetVPCEConfigurationResultTypeDef",
     {
         "vpceConfiguration": VPCEConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListVPCEConfigurationsResultTypeDef = TypedDict(
     "ListVPCEConfigurationsResultTypeDef",
     {
         "vpceConfigurations": List[VPCEConfigurationTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateVPCEConfigurationResultTypeDef = TypedDict(
     "UpdateVPCEConfigurationResultTypeDef",
     {
         "vpceConfiguration": VPCEConfigurationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeviceSelectionConfigurationTypeDef = TypedDict(
     "DeviceSelectionConfigurationTypeDef",
     {
         "filters": Sequence[DeviceFilterTypeDef],
@@ -1835,14 +2122,24 @@
         "filters": List[DeviceFilterTypeDef],
         "matchedDevicesCount": int,
         "maxDevices": int,
     },
     total=False,
 )
 
+ListDevicesRequestListDevicesPaginateTypeDef = TypedDict(
+    "ListDevicesRequestListDevicesPaginateTypeDef",
+    {
+        "arn": str,
+        "filters": Sequence[DeviceFilterTypeDef],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDevicesRequestRequestTypeDef = TypedDict(
     "ListDevicesRequestRequestTypeDef",
     {
         "arn": str,
         "nextToken": str,
         "filters": Sequence[DeviceFilterTypeDef],
     },
@@ -1881,351 +2178,54 @@
         "counters": CountersTypeDef,
         "message": str,
         "deviceMinutes": DeviceMinutesTypeDef,
     },
     total=False,
 )
 
-GetOfferingStatusRequestGetOfferingStatusPaginateTypeDef = TypedDict(
-    "GetOfferingStatusRequestGetOfferingStatusPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListArtifactsRequestListArtifactsPaginateTypeDef = TypedDict(
-    "_RequiredListArtifactsRequestListArtifactsPaginateTypeDef",
-    {
-        "arn": str,
-        "type": ArtifactCategoryType,
-    },
-)
-_OptionalListArtifactsRequestListArtifactsPaginateTypeDef = TypedDict(
-    "_OptionalListArtifactsRequestListArtifactsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListArtifactsRequestListArtifactsPaginateTypeDef(
-    _RequiredListArtifactsRequestListArtifactsPaginateTypeDef,
-    _OptionalListArtifactsRequestListArtifactsPaginateTypeDef,
-):
-    pass
-
-ListDeviceInstancesRequestListDeviceInstancesPaginateTypeDef = TypedDict(
-    "ListDeviceInstancesRequestListDeviceInstancesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListDevicePoolsRequestListDevicePoolsPaginateTypeDef = TypedDict(
-    "_RequiredListDevicePoolsRequestListDevicePoolsPaginateTypeDef",
-    {
-        "arn": str,
-    },
-)
-_OptionalListDevicePoolsRequestListDevicePoolsPaginateTypeDef = TypedDict(
-    "_OptionalListDevicePoolsRequestListDevicePoolsPaginateTypeDef",
-    {
-        "type": DevicePoolTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListDevicePoolsRequestListDevicePoolsPaginateTypeDef(
-    _RequiredListDevicePoolsRequestListDevicePoolsPaginateTypeDef,
-    _OptionalListDevicePoolsRequestListDevicePoolsPaginateTypeDef,
-):
-    pass
-
-ListDevicesRequestListDevicesPaginateTypeDef = TypedDict(
-    "ListDevicesRequestListDevicesPaginateTypeDef",
-    {
-        "arn": str,
-        "filters": Sequence[DeviceFilterTypeDef],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListInstanceProfilesRequestListInstanceProfilesPaginateTypeDef = TypedDict(
-    "ListInstanceProfilesRequestListInstanceProfilesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListJobsRequestListJobsPaginateTypeDef = TypedDict(
-    "_RequiredListJobsRequestListJobsPaginateTypeDef",
-    {
-        "arn": str,
-    },
-)
-_OptionalListJobsRequestListJobsPaginateTypeDef = TypedDict(
-    "_OptionalListJobsRequestListJobsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListJobsRequestListJobsPaginateTypeDef(
-    _RequiredListJobsRequestListJobsPaginateTypeDef, _OptionalListJobsRequestListJobsPaginateTypeDef
-):
-    pass
-
-_RequiredListNetworkProfilesRequestListNetworkProfilesPaginateTypeDef = TypedDict(
-    "_RequiredListNetworkProfilesRequestListNetworkProfilesPaginateTypeDef",
-    {
-        "arn": str,
-    },
-)
-_OptionalListNetworkProfilesRequestListNetworkProfilesPaginateTypeDef = TypedDict(
-    "_OptionalListNetworkProfilesRequestListNetworkProfilesPaginateTypeDef",
-    {
-        "type": NetworkProfileTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListNetworkProfilesRequestListNetworkProfilesPaginateTypeDef(
-    _RequiredListNetworkProfilesRequestListNetworkProfilesPaginateTypeDef,
-    _OptionalListNetworkProfilesRequestListNetworkProfilesPaginateTypeDef,
-):
-    pass
-
-ListOfferingPromotionsRequestListOfferingPromotionsPaginateTypeDef = TypedDict(
-    "ListOfferingPromotionsRequestListOfferingPromotionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListOfferingTransactionsRequestListOfferingTransactionsPaginateTypeDef = TypedDict(
-    "ListOfferingTransactionsRequestListOfferingTransactionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListOfferingsRequestListOfferingsPaginateTypeDef = TypedDict(
-    "ListOfferingsRequestListOfferingsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-ListProjectsRequestListProjectsPaginateTypeDef = TypedDict(
-    "ListProjectsRequestListProjectsPaginateTypeDef",
-    {
-        "arn": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListRemoteAccessSessionsRequestListRemoteAccessSessionsPaginateTypeDef = TypedDict(
-    "_RequiredListRemoteAccessSessionsRequestListRemoteAccessSessionsPaginateTypeDef",
-    {
-        "arn": str,
-    },
-)
-_OptionalListRemoteAccessSessionsRequestListRemoteAccessSessionsPaginateTypeDef = TypedDict(
-    "_OptionalListRemoteAccessSessionsRequestListRemoteAccessSessionsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListRemoteAccessSessionsRequestListRemoteAccessSessionsPaginateTypeDef(
-    _RequiredListRemoteAccessSessionsRequestListRemoteAccessSessionsPaginateTypeDef,
-    _OptionalListRemoteAccessSessionsRequestListRemoteAccessSessionsPaginateTypeDef,
-):
-    pass
-
-_RequiredListRunsRequestListRunsPaginateTypeDef = TypedDict(
-    "_RequiredListRunsRequestListRunsPaginateTypeDef",
-    {
-        "arn": str,
-    },
-)
-_OptionalListRunsRequestListRunsPaginateTypeDef = TypedDict(
-    "_OptionalListRunsRequestListRunsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListRunsRequestListRunsPaginateTypeDef(
-    _RequiredListRunsRequestListRunsPaginateTypeDef, _OptionalListRunsRequestListRunsPaginateTypeDef
-):
-    pass
-
-_RequiredListSamplesRequestListSamplesPaginateTypeDef = TypedDict(
-    "_RequiredListSamplesRequestListSamplesPaginateTypeDef",
-    {
-        "arn": str,
-    },
-)
-_OptionalListSamplesRequestListSamplesPaginateTypeDef = TypedDict(
-    "_OptionalListSamplesRequestListSamplesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListSamplesRequestListSamplesPaginateTypeDef(
-    _RequiredListSamplesRequestListSamplesPaginateTypeDef,
-    _OptionalListSamplesRequestListSamplesPaginateTypeDef,
-):
-    pass
-
-_RequiredListSuitesRequestListSuitesPaginateTypeDef = TypedDict(
-    "_RequiredListSuitesRequestListSuitesPaginateTypeDef",
-    {
-        "arn": str,
-    },
-)
-_OptionalListSuitesRequestListSuitesPaginateTypeDef = TypedDict(
-    "_OptionalListSuitesRequestListSuitesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListSuitesRequestListSuitesPaginateTypeDef(
-    _RequiredListSuitesRequestListSuitesPaginateTypeDef,
-    _OptionalListSuitesRequestListSuitesPaginateTypeDef,
-):
-    pass
-
-_RequiredListTestsRequestListTestsPaginateTypeDef = TypedDict(
-    "_RequiredListTestsRequestListTestsPaginateTypeDef",
-    {
-        "arn": str,
-    },
-)
-_OptionalListTestsRequestListTestsPaginateTypeDef = TypedDict(
-    "_OptionalListTestsRequestListTestsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListTestsRequestListTestsPaginateTypeDef(
-    _RequiredListTestsRequestListTestsPaginateTypeDef,
-    _OptionalListTestsRequestListTestsPaginateTypeDef,
-):
-    pass
-
-_RequiredListUniqueProblemsRequestListUniqueProblemsPaginateTypeDef = TypedDict(
-    "_RequiredListUniqueProblemsRequestListUniqueProblemsPaginateTypeDef",
-    {
-        "arn": str,
-    },
-)
-_OptionalListUniqueProblemsRequestListUniqueProblemsPaginateTypeDef = TypedDict(
-    "_OptionalListUniqueProblemsRequestListUniqueProblemsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListUniqueProblemsRequestListUniqueProblemsPaginateTypeDef(
-    _RequiredListUniqueProblemsRequestListUniqueProblemsPaginateTypeDef,
-    _OptionalListUniqueProblemsRequestListUniqueProblemsPaginateTypeDef,
-):
-    pass
-
-_RequiredListUploadsRequestListUploadsPaginateTypeDef = TypedDict(
-    "_RequiredListUploadsRequestListUploadsPaginateTypeDef",
-    {
-        "arn": str,
-    },
-)
-_OptionalListUploadsRequestListUploadsPaginateTypeDef = TypedDict(
-    "_OptionalListUploadsRequestListUploadsPaginateTypeDef",
-    {
-        "type": UploadTypeType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListUploadsRequestListUploadsPaginateTypeDef(
-    _RequiredListUploadsRequestListUploadsPaginateTypeDef,
-    _OptionalListUploadsRequestListUploadsPaginateTypeDef,
-):
-    pass
-
-ListVPCEConfigurationsRequestListVPCEConfigurationsPaginateTypeDef = TypedDict(
-    "ListVPCEConfigurationsRequestListVPCEConfigurationsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 GetTestGridSessionResultTypeDef = TypedDict(
     "GetTestGridSessionResultTypeDef",
     {
         "testGridSession": TestGridSessionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTestGridSessionsResultTypeDef = TypedDict(
     "ListTestGridSessionsResultTypeDef",
     {
         "testGridSessions": List[TestGridSessionTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListOfferingPromotionsResultTypeDef = TypedDict(
     "ListOfferingPromotionsResultTypeDef",
     {
         "offeringPromotions": List[OfferingPromotionTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSamplesResultTypeDef = TypedDict(
     "ListSamplesResultTypeDef",
     {
         "samples": List[SampleTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
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
@@ -2234,24 +2234,24 @@
 )
 
 ListTestGridSessionActionsResultTypeDef = TypedDict(
     "ListTestGridSessionActionsResultTypeDef",
     {
         "actions": List[TestGridSessionActionTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTestGridSessionArtifactsResultTypeDef = TypedDict(
     "ListTestGridSessionArtifactsResultTypeDef",
     {
         "artifacts": List[TestGridSessionArtifactTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RecurringChargeTypeDef = TypedDict(
     "RecurringChargeTypeDef",
     {
         "cost": MonetaryAmountTypeDef,
@@ -2276,48 +2276,48 @@
     total=False,
 )
 
 GetAccountSettingsResultTypeDef = TypedDict(
     "GetAccountSettingsResultTypeDef",
     {
         "accountSettings": AccountSettingsTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateDevicePoolResultTypeDef = TypedDict(
     "CreateDevicePoolResultTypeDef",
     {
         "devicePool": DevicePoolTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDevicePoolResultTypeDef = TypedDict(
     "GetDevicePoolResultTypeDef",
     {
         "devicePool": DevicePoolTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDevicePoolsResultTypeDef = TypedDict(
     "ListDevicePoolsResultTypeDef",
     {
         "devicePools": List[DevicePoolTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDevicePoolResultTypeDef = TypedDict(
     "UpdateDevicePoolResultTypeDef",
     {
         "devicePool": DevicePoolTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeviceTypeDef = TypedDict(
     "DeviceTypeDef",
     {
         "arn": str,
@@ -2345,98 +2345,98 @@
     total=False,
 )
 
 GetDeviceInstanceResultTypeDef = TypedDict(
     "GetDeviceInstanceResultTypeDef",
     {
         "deviceInstance": DeviceInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDeviceInstancesResultTypeDef = TypedDict(
     "ListDeviceInstancesResultTypeDef",
     {
         "deviceInstances": List[DeviceInstanceTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateDeviceInstanceResultTypeDef = TypedDict(
     "UpdateDeviceInstanceResultTypeDef",
     {
         "deviceInstance": DeviceInstanceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateProjectResultTypeDef = TypedDict(
     "CreateProjectResultTypeDef",
     {
         "project": ProjectTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetProjectResultTypeDef = TypedDict(
     "GetProjectResultTypeDef",
     {
         "project": ProjectTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListProjectsResultTypeDef = TypedDict(
     "ListProjectsResultTypeDef",
     {
         "projects": List[ProjectTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateProjectResultTypeDef = TypedDict(
     "UpdateProjectResultTypeDef",
     {
         "project": ProjectTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateTestGridProjectResultTypeDef = TypedDict(
     "CreateTestGridProjectResultTypeDef",
     {
         "testGridProject": TestGridProjectTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTestGridProjectResultTypeDef = TypedDict(
     "GetTestGridProjectResultTypeDef",
     {
         "testGridProject": TestGridProjectTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTestGridProjectsResultTypeDef = TypedDict(
     "ListTestGridProjectsResultTypeDef",
     {
         "testGridProjects": List[TestGridProjectTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateTestGridProjectResultTypeDef = TypedDict(
     "UpdateTestGridProjectResultTypeDef",
     {
         "testGridProject": TestGridProjectTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RunTypeDef = TypedDict(
     "RunTypeDef",
     {
         "arn": str,
@@ -2475,41 +2475,41 @@
     total=False,
 )
 
 GetSuiteResultTypeDef = TypedDict(
     "GetSuiteResultTypeDef",
     {
         "suite": SuiteTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListSuitesResultTypeDef = TypedDict(
     "ListSuitesResultTypeDef",
     {
         "suites": List[SuiteTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetTestResultTypeDef = TypedDict(
     "GetTestResultTypeDef",
     {
         "test": TestTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTestsResultTypeDef = TypedDict(
     "ListTestsResultTypeDef",
     {
         "tests": List[TestTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OfferingTypeDef = TypedDict(
     "OfferingTypeDef",
     {
         "id": str,
@@ -2579,15 +2579,15 @@
     total=False,
 )
 
 GetDeviceResultTypeDef = TypedDict(
     "GetDeviceResultTypeDef",
     {
         "device": DeviceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 JobTypeDef = TypedDict(
     "JobTypeDef",
     {
         "arn": str,
@@ -2610,15 +2610,15 @@
 )
 
 ListDevicesResultTypeDef = TypedDict(
     "ListDevicesResultTypeDef",
     {
         "devices": List[DeviceTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ProblemTypeDef = TypedDict(
     "ProblemTypeDef",
     {
         "run": ProblemDetailTypeDef,
@@ -2661,49 +2661,49 @@
     total=False,
 )
 
 GetRunResultTypeDef = TypedDict(
     "GetRunResultTypeDef",
     {
         "run": RunTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRunsResultTypeDef = TypedDict(
     "ListRunsResultTypeDef",
     {
         "runs": List[RunTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ScheduleRunResultTypeDef = TypedDict(
     "ScheduleRunResultTypeDef",
     {
         "run": RunTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopRunResultTypeDef = TypedDict(
     "StopRunResultTypeDef",
     {
         "run": RunTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListOfferingsResultTypeDef = TypedDict(
     "ListOfferingsResultTypeDef",
     {
         "offerings": List[OfferingTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OfferingStatusTypeDef = TypedDict(
     "OfferingStatusTypeDef",
     {
         "type": OfferingTransactionTypeType,
@@ -2715,40 +2715,40 @@
 )
 
 GetDevicePoolCompatibilityResultTypeDef = TypedDict(
     "GetDevicePoolCompatibilityResultTypeDef",
     {
         "compatibleDevices": List[DevicePoolCompatibilityResultTypeDef],
         "incompatibleDevices": List[DevicePoolCompatibilityResultTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetJobResultTypeDef = TypedDict(
     "GetJobResultTypeDef",
     {
         "job": JobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListJobsResultTypeDef = TypedDict(
     "ListJobsResultTypeDef",
     {
         "jobs": List[JobTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopJobResultTypeDef = TypedDict(
     "StopJobResultTypeDef",
     {
         "job": JobTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UniqueProblemTypeDef = TypedDict(
     "UniqueProblemTypeDef",
     {
         "message": str,
@@ -2757,50 +2757,50 @@
     total=False,
 )
 
 CreateRemoteAccessSessionResultTypeDef = TypedDict(
     "CreateRemoteAccessSessionResultTypeDef",
     {
         "remoteAccessSession": RemoteAccessSessionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetRemoteAccessSessionResultTypeDef = TypedDict(
     "GetRemoteAccessSessionResultTypeDef",
     {
         "remoteAccessSession": RemoteAccessSessionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListRemoteAccessSessionsResultTypeDef = TypedDict(
     "ListRemoteAccessSessionsResultTypeDef",
     {
         "remoteAccessSessions": List[RemoteAccessSessionTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StopRemoteAccessSessionResultTypeDef = TypedDict(
     "StopRemoteAccessSessionResultTypeDef",
     {
         "remoteAccessSession": RemoteAccessSessionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetOfferingStatusResultTypeDef = TypedDict(
     "GetOfferingStatusResultTypeDef",
     {
         "current": Dict[str, OfferingStatusTypeDef],
         "nextPeriod": Dict[str, OfferingStatusTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OfferingTransactionTypeDef = TypedDict(
     "OfferingTransactionTypeDef",
     {
         "offeringStatus": OfferingStatusTypeDef,
@@ -2813,35 +2813,35 @@
 )
 
 ListUniqueProblemsResultTypeDef = TypedDict(
     "ListUniqueProblemsResultTypeDef",
     {
         "uniqueProblems": Dict[ExecutionResultType, List[UniqueProblemTypeDef]],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListOfferingTransactionsResultTypeDef = TypedDict(
     "ListOfferingTransactionsResultTypeDef",
     {
         "offeringTransactions": List[OfferingTransactionTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PurchaseOfferingResultTypeDef = TypedDict(
     "PurchaseOfferingResultTypeDef",
     {
         "offeringTransaction": OfferingTransactionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 RenewOfferingResultTypeDef = TypedDict(
     "RenewOfferingResultTypeDef",
     {
         "offeringTransaction": OfferingTransactionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-devicefarm-2.5.0.post1/types_aiobotocore_devicefarm.egg-info/PKG-INFO` & `types-aiobotocore-devicefarm-2.5.1/types_aiobotocore_devicefarm.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-devicefarm
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.DeviceFarm 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.DeviceFarm 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-devicefarm"></a>
 
 # types-aiobotocore-devicefarm
 
 [![PyPI - types-aiobotocore-devicefarm](https://img.shields.io/pypi/v/types-aiobotocore-devicefarm.svg?color=blue)](https://pypi.org/project/types-aiobotocore-devicefarm)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-devicefarm.svg?color=blue)](https://pypi.org/project/types-aiobotocore-devicefarm)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-devicefarm?color=blue)](https://pypistats.org/packages/types-aiobotocore-devicefarm)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.DeviceFarm 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm)
+[aiobotocore.DeviceFarm 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/devicefarm.html#DeviceFarm)
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
 [types-aiobotocore-devicefarm docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_devicefarm/).
 
 See how it helps to find and fix potential bugs:
 
@@ -426,23 +426,23 @@
 ```python
 from types_aiobotocore_devicefarm.type_defs import (
     TrialMinutesTypeDef,
     ArtifactTypeDef,
     CPUTypeDef,
     CountersTypeDef,
     RuleTypeDef,
-    ResponseMetadataTypeDef,
     CreateInstanceProfileRequestRequestTypeDef,
     InstanceProfileTypeDef,
     CreateNetworkProfileRequestRequestTypeDef,
     NetworkProfileTypeDef,
     VpcConfigTypeDef,
     CreateRemoteAccessSessionConfigurationTypeDef,
     TestGridVpcConfigTypeDef,
     CreateTestGridUrlRequestRequestTypeDef,
+    CreateTestGridUrlResultTypeDef,
     CreateUploadRequestRequestTypeDef,
     UploadTypeDef,
     CreateVPCEConfigurationRequestRequestTypeDef,
     VPCEConfigurationTypeDef,
     CustomerArtifactPathsTypeDef,
     DeleteDevicePoolRequestRequestTypeDef,
     DeleteInstanceProfileRequestRequestTypeDef,
@@ -461,76 +461,95 @@
     GetDeviceInstanceRequestRequestTypeDef,
     ScheduleRunTestTypeDef,
     GetDevicePoolRequestRequestTypeDef,
     GetDeviceRequestRequestTypeDef,
     GetInstanceProfileRequestRequestTypeDef,
     GetJobRequestRequestTypeDef,
     GetNetworkProfileRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    GetOfferingStatusRequestGetOfferingStatusPaginateTypeDef,
     GetOfferingStatusRequestRequestTypeDef,
     GetProjectRequestRequestTypeDef,
     GetRemoteAccessSessionRequestRequestTypeDef,
     GetRunRequestRequestTypeDef,
     GetSuiteRequestRequestTypeDef,
     GetTestGridProjectRequestRequestTypeDef,
     GetTestGridSessionRequestRequestTypeDef,
     TestGridSessionTypeDef,
     GetTestRequestRequestTypeDef,
     GetUploadRequestRequestTypeDef,
     GetVPCEConfigurationRequestRequestTypeDef,
     InstallToRemoteAccessSessionRequestRequestTypeDef,
+    ListArtifactsRequestListArtifactsPaginateTypeDef,
     ListArtifactsRequestRequestTypeDef,
+    ListDeviceInstancesRequestListDeviceInstancesPaginateTypeDef,
     ListDeviceInstancesRequestRequestTypeDef,
+    ListDevicePoolsRequestListDevicePoolsPaginateTypeDef,
     ListDevicePoolsRequestRequestTypeDef,
+    ListInstanceProfilesRequestListInstanceProfilesPaginateTypeDef,
     ListInstanceProfilesRequestRequestTypeDef,
+    ListJobsRequestListJobsPaginateTypeDef,
     ListJobsRequestRequestTypeDef,
+    ListNetworkProfilesRequestListNetworkProfilesPaginateTypeDef,
     ListNetworkProfilesRequestRequestTypeDef,
+    ListOfferingPromotionsRequestListOfferingPromotionsPaginateTypeDef,
     ListOfferingPromotionsRequestRequestTypeDef,
     OfferingPromotionTypeDef,
+    ListOfferingTransactionsRequestListOfferingTransactionsPaginateTypeDef,
     ListOfferingTransactionsRequestRequestTypeDef,
+    ListOfferingsRequestListOfferingsPaginateTypeDef,
     ListOfferingsRequestRequestTypeDef,
+    ListProjectsRequestListProjectsPaginateTypeDef,
     ListProjectsRequestRequestTypeDef,
+    ListRemoteAccessSessionsRequestListRemoteAccessSessionsPaginateTypeDef,
     ListRemoteAccessSessionsRequestRequestTypeDef,
+    ListRunsRequestListRunsPaginateTypeDef,
     ListRunsRequestRequestTypeDef,
+    ListSamplesRequestListSamplesPaginateTypeDef,
     ListSamplesRequestRequestTypeDef,
     SampleTypeDef,
+    ListSuitesRequestListSuitesPaginateTypeDef,
     ListSuitesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
     TagTypeDef,
     ListTestGridProjectsRequestRequestTypeDef,
     ListTestGridSessionActionsRequestRequestTypeDef,
     TestGridSessionActionTypeDef,
     ListTestGridSessionArtifactsRequestRequestTypeDef,
     TestGridSessionArtifactTypeDef,
     ListTestGridSessionsRequestRequestTypeDef,
+    ListTestsRequestListTestsPaginateTypeDef,
     ListTestsRequestRequestTypeDef,
+    ListUniqueProblemsRequestListUniqueProblemsPaginateTypeDef,
     ListUniqueProblemsRequestRequestTypeDef,
+    ListUploadsRequestListUploadsPaginateTypeDef,
     ListUploadsRequestRequestTypeDef,
+    ListVPCEConfigurationsRequestListVPCEConfigurationsPaginateTypeDef,
     ListVPCEConfigurationsRequestRequestTypeDef,
     LocationTypeDef,
     MonetaryAmountTypeDef,
+    PaginatorConfigTypeDef,
     ProblemDetailTypeDef,
     PurchaseOfferingRequestRequestTypeDef,
     RadiosTypeDef,
     RenewOfferingRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
     StopJobRequestRequestTypeDef,
     StopRemoteAccessSessionRequestRequestTypeDef,
     StopRunRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateDeviceInstanceRequestRequestTypeDef,
     UpdateInstanceProfileRequestRequestTypeDef,
     UpdateNetworkProfileRequestRequestTypeDef,
     UpdateUploadRequestRequestTypeDef,
     UpdateVPCEConfigurationRequestRequestTypeDef,
     AccountSettingsTypeDef,
+    ListArtifactsResultTypeDef,
     CreateDevicePoolRequestRequestTypeDef,
     DevicePoolTypeDef,
     UpdateDevicePoolRequestRequestTypeDef,
-    CreateTestGridUrlResultTypeDef,
-    ListArtifactsResultTypeDef,
     CreateInstanceProfileResultTypeDef,
     DeviceInstanceTypeDef,
     GetInstanceProfileResultTypeDef,
     ListInstanceProfilesResultTypeDef,
     UpdateInstanceProfileResultTypeDef,
     CreateNetworkProfileResultTypeDef,
     GetNetworkProfileResultTypeDef,
@@ -550,37 +569,18 @@
     UpdateUploadResultTypeDef,
     CreateVPCEConfigurationResultTypeDef,
     GetVPCEConfigurationResultTypeDef,
     ListVPCEConfigurationsResultTypeDef,
     UpdateVPCEConfigurationResultTypeDef,
     DeviceSelectionConfigurationTypeDef,
     DeviceSelectionResultTypeDef,
+    ListDevicesRequestListDevicesPaginateTypeDef,
     ListDevicesRequestRequestTypeDef,
     SuiteTypeDef,
     TestTypeDef,
-    GetOfferingStatusRequestGetOfferingStatusPaginateTypeDef,
-    ListArtifactsRequestListArtifactsPaginateTypeDef,
-    ListDeviceInstancesRequestListDeviceInstancesPaginateTypeDef,
-    ListDevicePoolsRequestListDevicePoolsPaginateTypeDef,
-    ListDevicesRequestListDevicesPaginateTypeDef,
-    ListInstanceProfilesRequestListInstanceProfilesPaginateTypeDef,
-    ListJobsRequestListJobsPaginateTypeDef,
-    ListNetworkProfilesRequestListNetworkProfilesPaginateTypeDef,
-    ListOfferingPromotionsRequestListOfferingPromotionsPaginateTypeDef,
-    ListOfferingTransactionsRequestListOfferingTransactionsPaginateTypeDef,
-    ListOfferingsRequestListOfferingsPaginateTypeDef,
-    ListProjectsRequestListProjectsPaginateTypeDef,
-    ListRemoteAccessSessionsRequestListRemoteAccessSessionsPaginateTypeDef,
-    ListRunsRequestListRunsPaginateTypeDef,
-    ListSamplesRequestListSamplesPaginateTypeDef,
-    ListSuitesRequestListSuitesPaginateTypeDef,
-    ListTestsRequestListTestsPaginateTypeDef,
-    ListUniqueProblemsRequestListUniqueProblemsPaginateTypeDef,
-    ListUploadsRequestListUploadsPaginateTypeDef,
-    ListVPCEConfigurationsRequestListVPCEConfigurationsPaginateTypeDef,
     GetTestGridSessionResultTypeDef,
     ListTestGridSessionsResultTypeDef,
     ListOfferingPromotionsResultTypeDef,
     ListSamplesResultTypeDef,
     ListTagsForResourceResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     ListTestGridSessionActionsResultTypeDef,
@@ -649,43 +649,43 @@
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

### Comparing `types-aiobotocore-devicefarm-2.5.0.post1/types_aiobotocore_devicefarm.egg-info/SOURCES.txt` & `types-aiobotocore-devicefarm-2.5.1/types_aiobotocore_devicefarm.egg-info/SOURCES.txt`

 * *Files identical despite different names*

