# Comparing `tmp/types-aiobotocore-snowball-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-snowball-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-snowball-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:23 2023, max compression
+gzip compressed data, was "types-aiobotocore-snowball-2.5.1.tar", last modified: Wed Jun 28 01:44:12 2023, max compression
```

## Comparing `types-aiobotocore-snowball-2.5.0.post1.tar` & `types-aiobotocore-snowball-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:23.127654 types-aiobotocore-snowball-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:24:20.000000 types-aiobotocore-snowball-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    17128 2023-03-11 12:27:23.127654 types-aiobotocore-snowball-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    15553 2023-03-11 12:24:20.000000 types-aiobotocore-snowball-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:23.127654 types-aiobotocore-snowball-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2131 2023-03-11 12:24:20.000000 types-aiobotocore-snowball-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:23.119654 types-aiobotocore-snowball-2.5.0.post1/types_aiobotocore_snowball/
--rw-r--r--   0 runner    (1001) docker     (123)     1679 2023-03-11 12:24:20.000000 types-aiobotocore-snowball-2.5.0.post1/types_aiobotocore_snowball/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1678 2023-03-11 12:24:20.000000 types-aiobotocore-snowball-2.5.0.post1/types_aiobotocore_snowball/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      947 2023-03-11 12:24:20.000000 types-aiobotocore-snowball-2.5.0.post1/types_aiobotocore_snowball/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    25025 2023-03-11 12:24:20.000000 types-aiobotocore-snowball-2.5.0.post1/types_aiobotocore_snowball/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    24984 2023-03-11 12:24:20.000000 types-aiobotocore-snowball-2.5.0.post1/types_aiobotocore_snowball/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10118 2023-03-11 12:24:21.000000 types-aiobotocore-snowball-2.5.0.post1/types_aiobotocore_snowball/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    10116 2023-03-11 12:24:21.000000 types-aiobotocore-snowball-2.5.0.post1/types_aiobotocore_snowball/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7535 2023-03-11 12:24:20.000000 types-aiobotocore-snowball-2.5.0.post1/types_aiobotocore_snowball/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     7526 2023-03-11 12:24:20.000000 types-aiobotocore-snowball-2.5.0.post1/types_aiobotocore_snowball/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:24:20.000000 types-aiobotocore-snowball-2.5.0.post1/types_aiobotocore_snowball/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    26980 2023-03-11 12:24:21.000000 types-aiobotocore-snowball-2.5.0.post1/types_aiobotocore_snowball/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    26959 2023-03-11 12:24:21.000000 types-aiobotocore-snowball-2.5.0.post1/types_aiobotocore_snowball/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:24:20.000000 types-aiobotocore-snowball-2.5.0.post1/types_aiobotocore_snowball/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:23.127654 types-aiobotocore-snowball-2.5.0.post1/types_aiobotocore_snowball.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    17128 2023-03-11 12:27:22.000000 types-aiobotocore-snowball-2.5.0.post1/types_aiobotocore_snowball.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      832 2023-03-11 12:27:22.000000 types-aiobotocore-snowball-2.5.0.post1/types_aiobotocore_snowball.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:22.000000 types-aiobotocore-snowball-2.5.0.post1/types_aiobotocore_snowball.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:22.000000 types-aiobotocore-snowball-2.5.0.post1/types_aiobotocore_snowball.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:22.000000 types-aiobotocore-snowball-2.5.0.post1/types_aiobotocore_snowball.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       27 2023-03-11 12:27:22.000000 types-aiobotocore-snowball-2.5.0.post1/types_aiobotocore_snowball.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:12.946218 types-aiobotocore-snowball-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:41:08.000000 types-aiobotocore-snowball-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    17164 2023-06-28 01:44:12.946218 types-aiobotocore-snowball-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    15595 2023-06-28 01:41:08.000000 types-aiobotocore-snowball-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:12.946218 types-aiobotocore-snowball-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2125 2023-06-28 01:41:08.000000 types-aiobotocore-snowball-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:12.926218 types-aiobotocore-snowball-2.5.1/types_aiobotocore_snowball/
+-rw-r--r--   0 runner    (1001) docker     (123)     1679 2023-06-28 01:41:08.000000 types-aiobotocore-snowball-2.5.1/types_aiobotocore_snowball/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1678 2023-06-28 01:41:08.000000 types-aiobotocore-snowball-2.5.1/types_aiobotocore_snowball/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      935 2023-06-28 01:41:08.000000 types-aiobotocore-snowball-2.5.1/types_aiobotocore_snowball/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25224 2023-06-28 01:41:09.000000 types-aiobotocore-snowball-2.5.1/types_aiobotocore_snowball/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25183 2023-06-28 01:41:08.000000 types-aiobotocore-snowball-2.5.1/types_aiobotocore_snowball/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10376 2023-06-28 01:41:09.000000 types-aiobotocore-snowball-2.5.1/types_aiobotocore_snowball/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10374 2023-06-28 01:41:09.000000 types-aiobotocore-snowball-2.5.1/types_aiobotocore_snowball/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     7427 2023-06-28 01:41:09.000000 types-aiobotocore-snowball-2.5.1/types_aiobotocore_snowball/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7419 2023-06-28 01:41:09.000000 types-aiobotocore-snowball-2.5.1/types_aiobotocore_snowball/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:41:08.000000 types-aiobotocore-snowball-2.5.1/types_aiobotocore_snowball/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    27628 2023-06-28 01:41:09.000000 types-aiobotocore-snowball-2.5.1/types_aiobotocore_snowball/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27607 2023-06-28 01:41:09.000000 types-aiobotocore-snowball-2.5.1/types_aiobotocore_snowball/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:41:08.000000 types-aiobotocore-snowball-2.5.1/types_aiobotocore_snowball/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:12.946218 types-aiobotocore-snowball-2.5.1/types_aiobotocore_snowball.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    17164 2023-06-28 01:44:12.000000 types-aiobotocore-snowball-2.5.1/types_aiobotocore_snowball.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      832 2023-06-28 01:44:12.000000 types-aiobotocore-snowball-2.5.1/types_aiobotocore_snowball.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:12.000000 types-aiobotocore-snowball-2.5.1/types_aiobotocore_snowball.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:12.000000 types-aiobotocore-snowball-2.5.1/types_aiobotocore_snowball.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:12.000000 types-aiobotocore-snowball-2.5.1/types_aiobotocore_snowball.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       27 2023-06-28 01:44:12.000000 types-aiobotocore-snowball-2.5.1/types_aiobotocore_snowball.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-snowball-2.5.0.post1/LICENSE` & `types-aiobotocore-snowball-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-snowball-2.5.0.post1/PKG-INFO` & `types-aiobotocore-snowball-2.5.1/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-snowball
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Snowball 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Snowball 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-snowball"></a>
 
 # types-aiobotocore-snowball
 
 [![PyPI - types-aiobotocore-snowball](https://img.shields.io/pypi/v/types-aiobotocore-snowball.svg?color=blue)](https://pypi.org/project/types-aiobotocore-snowball)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-snowball.svg?color=blue)](https://pypi.org/project/types-aiobotocore-snowball)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-snowball?color=blue)](https://pypistats.org/packages/types-aiobotocore-snowball)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Snowball 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snowball.html#Snowball)
+[aiobotocore.Snowball 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snowball.html#Snowball)
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
 [types-aiobotocore-snowball docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball/).
 
 See how it helps to find and fix potential bugs:
 
@@ -358,74 +358,75 @@
 from types_aiobotocore_snowball.type_defs import (
     AddressTypeDef,
     CancelClusterRequestRequestTypeDef,
     CancelJobRequestRequestTypeDef,
     ClusterListEntryTypeDef,
     NotificationTypeDef,
     CompatibleImageTypeDef,
-    ResponseMetadataTypeDef,
+    CreateAddressResultTypeDef,
+    JobListEntryTypeDef,
+    CreateJobResultTypeDef,
     CreateLongTermPricingRequestRequestTypeDef,
+    CreateLongTermPricingResultTypeDef,
     CreateReturnShippingLabelRequestRequestTypeDef,
+    CreateReturnShippingLabelResultTypeDef,
     DataTransferTypeDef,
     ServiceVersionTypeDef,
     DescribeAddressRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeAddressesRequestDescribeAddressesPaginateTypeDef,
     DescribeAddressesRequestRequestTypeDef,
     DescribeClusterRequestRequestTypeDef,
     DescribeJobRequestRequestTypeDef,
     DescribeReturnShippingLabelRequestRequestTypeDef,
+    DescribeReturnShippingLabelResultTypeDef,
     EKSOnDeviceServiceConfigurationTypeDef,
     Ec2AmiResourceTypeDef,
     EventTriggerDefinitionTypeDef,
     GetJobManifestRequestRequestTypeDef,
+    GetJobManifestResultTypeDef,
     GetJobUnlockCodeRequestRequestTypeDef,
+    GetJobUnlockCodeResultTypeDef,
+    GetSnowballUsageResultTypeDef,
     GetSoftwareUpdatesRequestRequestTypeDef,
+    GetSoftwareUpdatesResultTypeDef,
     INDTaxDocumentsTypeDef,
-    JobListEntryTypeDef,
     JobLogsTypeDef,
     KeyRangeTypeDef,
+    ListClusterJobsRequestListClusterJobsPaginateTypeDef,
     ListClusterJobsRequestRequestTypeDef,
+    ListClustersRequestListClustersPaginateTypeDef,
     ListClustersRequestRequestTypeDef,
+    ListCompatibleImagesRequestListCompatibleImagesPaginateTypeDef,
     ListCompatibleImagesRequestRequestTypeDef,
+    ListJobsRequestListJobsPaginateTypeDef,
     ListJobsRequestRequestTypeDef,
+    ListLongTermPricingRequestListLongTermPricingPaginateTypeDef,
     ListLongTermPricingRequestRequestTypeDef,
     LongTermPricingListEntryTypeDef,
     NFSOnDeviceServiceConfigurationTypeDef,
+    S3OnDeviceServiceConfigurationTypeDef,
     TGWOnDeviceServiceConfigurationTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     TargetOnDeviceServiceTypeDef,
     ShipmentTypeDef,
     WirelessConnectionTypeDef,
     UpdateJobShipmentStateRequestRequestTypeDef,
     UpdateLongTermPricingRequestRequestTypeDef,
     CreateAddressRequestRequestTypeDef,
-    CreateAddressResultTypeDef,
-    CreateClusterResultTypeDef,
-    CreateJobResultTypeDef,
-    CreateLongTermPricingResultTypeDef,
-    CreateReturnShippingLabelResultTypeDef,
     DescribeAddressResultTypeDef,
     DescribeAddressesResultTypeDef,
-    DescribeReturnShippingLabelResultTypeDef,
-    GetJobManifestResultTypeDef,
-    GetJobUnlockCodeResultTypeDef,
-    GetSnowballUsageResultTypeDef,
-    GetSoftwareUpdatesResultTypeDef,
     ListClustersResultTypeDef,
     ListCompatibleImagesResultTypeDef,
+    CreateClusterResultTypeDef,
+    ListClusterJobsResultTypeDef,
+    ListJobsResultTypeDef,
     DependentServiceTypeDef,
-    DescribeAddressesRequestDescribeAddressesPaginateTypeDef,
-    ListClusterJobsRequestListClusterJobsPaginateTypeDef,
-    ListClustersRequestListClustersPaginateTypeDef,
-    ListCompatibleImagesRequestListCompatibleImagesPaginateTypeDef,
-    ListJobsRequestListJobsPaginateTypeDef,
-    ListLongTermPricingRequestListLongTermPricingPaginateTypeDef,
     LambdaResourceTypeDef,
     TaxDocumentsTypeDef,
-    ListClusterJobsResultTypeDef,
-    ListJobsResultTypeDef,
     ListLongTermPricingResultTypeDef,
     OnDeviceServiceConfigurationTypeDef,
     S3ResourceTypeDef,
     ShippingDetailsTypeDef,
     SnowconeDeviceConfigurationTypeDef,
     ListServiceVersionsRequestRequestTypeDef,
     ListServiceVersionsResultTypeDef,
@@ -449,43 +450,43 @@
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

### Comparing `types-aiobotocore-snowball-2.5.0.post1/README.md` & `types-aiobotocore-snowball-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-snowball"></a>
 
 # types-aiobotocore-snowball
 
 [![PyPI - types-aiobotocore-snowball](https://img.shields.io/pypi/v/types-aiobotocore-snowball.svg?color=blue)](https://pypi.org/project/types-aiobotocore-snowball)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-snowball.svg?color=blue)](https://pypi.org/project/types-aiobotocore-snowball)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-snowball?color=blue)](https://pypistats.org/packages/types-aiobotocore-snowball)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Snowball 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snowball.html#Snowball)
+[aiobotocore.Snowball 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snowball.html#Snowball)
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
 [types-aiobotocore-snowball docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball/).
 
 See how it helps to find and fix potential bugs:
 
@@ -325,74 +325,75 @@
 from types_aiobotocore_snowball.type_defs import (
     AddressTypeDef,
     CancelClusterRequestRequestTypeDef,
     CancelJobRequestRequestTypeDef,
     ClusterListEntryTypeDef,
     NotificationTypeDef,
     CompatibleImageTypeDef,
-    ResponseMetadataTypeDef,
+    CreateAddressResultTypeDef,
+    JobListEntryTypeDef,
+    CreateJobResultTypeDef,
     CreateLongTermPricingRequestRequestTypeDef,
+    CreateLongTermPricingResultTypeDef,
     CreateReturnShippingLabelRequestRequestTypeDef,
+    CreateReturnShippingLabelResultTypeDef,
     DataTransferTypeDef,
     ServiceVersionTypeDef,
     DescribeAddressRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeAddressesRequestDescribeAddressesPaginateTypeDef,
     DescribeAddressesRequestRequestTypeDef,
     DescribeClusterRequestRequestTypeDef,
     DescribeJobRequestRequestTypeDef,
     DescribeReturnShippingLabelRequestRequestTypeDef,
+    DescribeReturnShippingLabelResultTypeDef,
     EKSOnDeviceServiceConfigurationTypeDef,
     Ec2AmiResourceTypeDef,
     EventTriggerDefinitionTypeDef,
     GetJobManifestRequestRequestTypeDef,
+    GetJobManifestResultTypeDef,
     GetJobUnlockCodeRequestRequestTypeDef,
+    GetJobUnlockCodeResultTypeDef,
+    GetSnowballUsageResultTypeDef,
     GetSoftwareUpdatesRequestRequestTypeDef,
+    GetSoftwareUpdatesResultTypeDef,
     INDTaxDocumentsTypeDef,
-    JobListEntryTypeDef,
     JobLogsTypeDef,
     KeyRangeTypeDef,
+    ListClusterJobsRequestListClusterJobsPaginateTypeDef,
     ListClusterJobsRequestRequestTypeDef,
+    ListClustersRequestListClustersPaginateTypeDef,
     ListClustersRequestRequestTypeDef,
+    ListCompatibleImagesRequestListCompatibleImagesPaginateTypeDef,
     ListCompatibleImagesRequestRequestTypeDef,
+    ListJobsRequestListJobsPaginateTypeDef,
     ListJobsRequestRequestTypeDef,
+    ListLongTermPricingRequestListLongTermPricingPaginateTypeDef,
     ListLongTermPricingRequestRequestTypeDef,
     LongTermPricingListEntryTypeDef,
     NFSOnDeviceServiceConfigurationTypeDef,
+    S3OnDeviceServiceConfigurationTypeDef,
     TGWOnDeviceServiceConfigurationTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     TargetOnDeviceServiceTypeDef,
     ShipmentTypeDef,
     WirelessConnectionTypeDef,
     UpdateJobShipmentStateRequestRequestTypeDef,
     UpdateLongTermPricingRequestRequestTypeDef,
     CreateAddressRequestRequestTypeDef,
-    CreateAddressResultTypeDef,
-    CreateClusterResultTypeDef,
-    CreateJobResultTypeDef,
-    CreateLongTermPricingResultTypeDef,
-    CreateReturnShippingLabelResultTypeDef,
     DescribeAddressResultTypeDef,
     DescribeAddressesResultTypeDef,
-    DescribeReturnShippingLabelResultTypeDef,
-    GetJobManifestResultTypeDef,
-    GetJobUnlockCodeResultTypeDef,
-    GetSnowballUsageResultTypeDef,
-    GetSoftwareUpdatesResultTypeDef,
     ListClustersResultTypeDef,
     ListCompatibleImagesResultTypeDef,
+    CreateClusterResultTypeDef,
+    ListClusterJobsResultTypeDef,
+    ListJobsResultTypeDef,
     DependentServiceTypeDef,
-    DescribeAddressesRequestDescribeAddressesPaginateTypeDef,
-    ListClusterJobsRequestListClusterJobsPaginateTypeDef,
-    ListClustersRequestListClustersPaginateTypeDef,
-    ListCompatibleImagesRequestListCompatibleImagesPaginateTypeDef,
-    ListJobsRequestListJobsPaginateTypeDef,
-    ListLongTermPricingRequestListLongTermPricingPaginateTypeDef,
     LambdaResourceTypeDef,
     TaxDocumentsTypeDef,
-    ListClusterJobsResultTypeDef,
-    ListJobsResultTypeDef,
     ListLongTermPricingResultTypeDef,
     OnDeviceServiceConfigurationTypeDef,
     S3ResourceTypeDef,
     ShippingDetailsTypeDef,
     SnowconeDeviceConfigurationTypeDef,
     ListServiceVersionsRequestRequestTypeDef,
     ListServiceVersionsResultTypeDef,
@@ -416,43 +417,43 @@
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

### Comparing `types-aiobotocore-snowball-2.5.0.post1/setup.py` & `types-aiobotocore-snowball-2.5.1/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-snowball.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-snowball",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_snowball"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Snowball 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.Snowball 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball/"
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

### Comparing `types-aiobotocore-snowball-2.5.0.post1/types_aiobotocore_snowball/__init__.py` & `types-aiobotocore-snowball-2.5.1/types_aiobotocore_snowball/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-snowball-2.5.0.post1/types_aiobotocore_snowball/__init__.pyi` & `types-aiobotocore-snowball-2.5.1/types_aiobotocore_snowball/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-snowball-2.5.0.post1/types_aiobotocore_snowball/__main__.py` & `types-aiobotocore-snowball-2.5.1/types_aiobotocore_snowball/__main__.py`

 * *Files 17% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Snowball 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Snowball 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snowball.html#Snowball\nOther"
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

### Comparing `types-aiobotocore-snowball-2.5.0.post1/types_aiobotocore_snowball/client.py` & `types-aiobotocore-snowball-2.5.1/types_aiobotocore_snowball/client.py`

 * *Files 1% similar despite different names*

```diff
@@ -157,26 +157,30 @@
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball/client/#create_address)
         """
 
     async def create_cluster(
         self,
         *,
         JobType: JobTypeType,
-        Resources: JobResourceTypeDef,
         AddressId: str,
-        RoleARN: str,
         SnowballType: SnowballTypeType,
         ShippingOption: ShippingOptionType,
+        Resources: JobResourceTypeDef = ...,
         OnDeviceServiceConfiguration: OnDeviceServiceConfigurationTypeDef = ...,
         Description: str = ...,
         KmsKeyARN: str = ...,
+        RoleARN: str = ...,
         Notification: NotificationTypeDef = ...,
         ForwardingAddressId: str = ...,
         TaxDocuments: TaxDocumentsTypeDef = ...,
-        RemoteManagement: RemoteManagementType = ...
+        RemoteManagement: RemoteManagementType = ...,
+        InitialClusterSize: int = ...,
+        ForceCreateJobs: bool = ...,
+        LongTermPricingIds: Sequence[str] = ...,
+        SnowballCapacityPreference: SnowballCapacityType = ...
     ) -> CreateClusterResultTypeDef:
         """
         Creates an empty cluster.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snowball.html#Snowball.Client.create_cluster)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball/client/#create_cluster)
         """
@@ -322,15 +326,15 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snowball.html#Snowball.Client.get_snowball_usage)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball/client/#get_snowball_usage)
         """
 
     async def get_software_updates(self, *, JobId: str) -> GetSoftwareUpdatesResultTypeDef:
         """
         Returns an Amazon S3 presigned URL for an update file associated with a
-        specified `JobId` .
+        specified `JobId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snowball.html#Snowball.Client.get_software_updates)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball/client/#get_software_updates)
         """
 
     async def list_cluster_jobs(
         self, *, ClusterId: str, MaxResults: int = ..., NextToken: str = ...
@@ -431,15 +435,15 @@
         AddressId: str = ...,
         ShippingOption: ShippingOptionType = ...,
         Description: str = ...,
         SnowballCapacityPreference: SnowballCapacityType = ...,
         ForwardingAddressId: str = ...
     ) -> Dict[str, Any]:
         """
-        While a job's `JobState` value is `New` , you can update some of the information
+        While a job's `JobState` value is `New`, you can update some of the information
         associated with a job.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snowball.html#Snowball.Client.update_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball/client/#update_job)
         """
 
     async def update_job_shipment_state(
```

### Comparing `types-aiobotocore-snowball-2.5.0.post1/types_aiobotocore_snowball/client.pyi` & `types-aiobotocore-snowball-2.5.1/types_aiobotocore_snowball/client.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -147,26 +147,30 @@
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snowball.html#Snowball.Client.create_address)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball/client/#create_address)
         """
     async def create_cluster(
         self,
         *,
         JobType: JobTypeType,
-        Resources: JobResourceTypeDef,
         AddressId: str,
-        RoleARN: str,
         SnowballType: SnowballTypeType,
         ShippingOption: ShippingOptionType,
+        Resources: JobResourceTypeDef = ...,
         OnDeviceServiceConfiguration: OnDeviceServiceConfigurationTypeDef = ...,
         Description: str = ...,
         KmsKeyARN: str = ...,
+        RoleARN: str = ...,
         Notification: NotificationTypeDef = ...,
         ForwardingAddressId: str = ...,
         TaxDocuments: TaxDocumentsTypeDef = ...,
-        RemoteManagement: RemoteManagementType = ...
+        RemoteManagement: RemoteManagementType = ...,
+        InitialClusterSize: int = ...,
+        ForceCreateJobs: bool = ...,
+        LongTermPricingIds: Sequence[str] = ...,
+        SnowballCapacityPreference: SnowballCapacityType = ...
     ) -> CreateClusterResultTypeDef:
         """
         Creates an empty cluster.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snowball.html#Snowball.Client.create_cluster)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball/client/#create_cluster)
         """
@@ -299,15 +303,15 @@
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snowball.html#Snowball.Client.get_snowball_usage)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball/client/#get_snowball_usage)
         """
     async def get_software_updates(self, *, JobId: str) -> GetSoftwareUpdatesResultTypeDef:
         """
         Returns an Amazon S3 presigned URL for an update file associated with a
-        specified `JobId` .
+        specified `JobId`.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snowball.html#Snowball.Client.get_software_updates)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball/client/#get_software_updates)
         """
     async def list_cluster_jobs(
         self, *, ClusterId: str, MaxResults: int = ..., NextToken: str = ...
     ) -> ListClusterJobsResultTypeDef:
@@ -400,15 +404,15 @@
         AddressId: str = ...,
         ShippingOption: ShippingOptionType = ...,
         Description: str = ...,
         SnowballCapacityPreference: SnowballCapacityType = ...,
         ForwardingAddressId: str = ...
     ) -> Dict[str, Any]:
         """
-        While a job's `JobState` value is `New` , you can update some of the information
+        While a job's `JobState` value is `New`, you can update some of the information
         associated with a job.
 
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snowball.html#Snowball.Client.update_job)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball/client/#update_job)
         """
     async def update_job_shipment_state(
         self, *, JobId: str, ShipmentState: ShipmentStateType
```

### Comparing `types-aiobotocore-snowball-2.5.0.post1/types_aiobotocore_snowball/literals.py` & `types-aiobotocore-snowball-2.5.1/types_aiobotocore_snowball/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -68,25 +68,25 @@
 ]
 JobTypeType = Literal["EXPORT", "IMPORT", "LOCAL_USE"]
 ListClusterJobsPaginatorName = Literal["list_cluster_jobs"]
 ListClustersPaginatorName = Literal["list_clusters"]
 ListCompatibleImagesPaginatorName = Literal["list_compatible_images"]
 ListJobsPaginatorName = Literal["list_jobs"]
 ListLongTermPricingPaginatorName = Literal["list_long_term_pricing"]
-LongTermPricingTypeType = Literal["OneYear", "ThreeYear"]
+LongTermPricingTypeType = Literal["OneMonth", "OneYear", "ThreeYear"]
 RemoteManagementType = Literal["INSTALLED_AUTOSTART", "INSTALLED_ONLY"]
 ServiceNameType = Literal["EKS_ANYWHERE", "KUBERNETES"]
 ShipmentStateType = Literal["RECEIVED", "RETURNED"]
 ShippingLabelStatusType = Literal["Failed", "InProgress", "Succeeded", "TimedOut"]
 ShippingOptionType = Literal["EXPRESS", "NEXT_DAY", "SECOND_DAY", "STANDARD"]
 SnowballCapacityType = Literal[
-    "NoPreference", "T100", "T14", "T32", "T42", "T50", "T8", "T80", "T98"
+    "NoPreference", "T100", "T14", "T240", "T32", "T42", "T50", "T8", "T80", "T98"
 ]
 SnowballTypeType = Literal[
-    "EDGE", "EDGE_C", "EDGE_CG", "EDGE_S", "SNC1_HDD", "SNC1_SSD", "STANDARD", "V3_5C"
+    "EDGE", "EDGE_C", "EDGE_CG", "EDGE_S", "SNC1_HDD", "SNC1_SSD", "STANDARD", "V3_5C", "V3_5S"
 ]
 StorageUnitType = Literal["TB"]
 TransferOptionType = Literal["EXPORT", "IMPORT", "LOCAL_USE"]
 SnowballServiceName = Literal["snowball"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
@@ -145,14 +145,15 @@
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
@@ -231,14 +232,15 @@
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
@@ -249,14 +251,15 @@
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
@@ -292,14 +295,15 @@
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
@@ -318,16 +322,19 @@
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
@@ -411,15 +418,17 @@
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
@@ -462,13 +471,14 @@
     "ca-central-1",
     "eu-central-1",
     "eu-north-1",
     "eu-south-1",
     "eu-west-1",
     "eu-west-2",
     "eu-west-3",
+    "me-central-1",
     "sa-east-1",
     "us-east-1",
     "us-east-2",
     "us-west-1",
     "us-west-2",
 ]
```

### Comparing `types-aiobotocore-snowball-2.5.0.post1/types_aiobotocore_snowball/literals.pyi` & `types-aiobotocore-snowball-2.5.1/types_aiobotocore_snowball/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -66,25 +66,25 @@
 ]
 JobTypeType = Literal["EXPORT", "IMPORT", "LOCAL_USE"]
 ListClusterJobsPaginatorName = Literal["list_cluster_jobs"]
 ListClustersPaginatorName = Literal["list_clusters"]
 ListCompatibleImagesPaginatorName = Literal["list_compatible_images"]
 ListJobsPaginatorName = Literal["list_jobs"]
 ListLongTermPricingPaginatorName = Literal["list_long_term_pricing"]
-LongTermPricingTypeType = Literal["OneYear", "ThreeYear"]
+LongTermPricingTypeType = Literal["OneMonth", "OneYear", "ThreeYear"]
 RemoteManagementType = Literal["INSTALLED_AUTOSTART", "INSTALLED_ONLY"]
 ServiceNameType = Literal["EKS_ANYWHERE", "KUBERNETES"]
 ShipmentStateType = Literal["RECEIVED", "RETURNED"]
 ShippingLabelStatusType = Literal["Failed", "InProgress", "Succeeded", "TimedOut"]
 ShippingOptionType = Literal["EXPRESS", "NEXT_DAY", "SECOND_DAY", "STANDARD"]
 SnowballCapacityType = Literal[
-    "NoPreference", "T100", "T14", "T32", "T42", "T50", "T8", "T80", "T98"
+    "NoPreference", "T100", "T14", "T240", "T32", "T42", "T50", "T8", "T80", "T98"
 ]
 SnowballTypeType = Literal[
-    "EDGE", "EDGE_C", "EDGE_CG", "EDGE_S", "SNC1_HDD", "SNC1_SSD", "STANDARD", "V3_5C"
+    "EDGE", "EDGE_C", "EDGE_CG", "EDGE_S", "SNC1_HDD", "SNC1_SSD", "STANDARD", "V3_5C", "V3_5S"
 ]
 StorageUnitType = Literal["TB"]
 TransferOptionType = Literal["EXPORT", "IMPORT", "LOCAL_USE"]
 SnowballServiceName = Literal["snowball"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
@@ -143,14 +143,15 @@
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
@@ -229,14 +230,15 @@
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
@@ -247,14 +249,15 @@
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
@@ -290,14 +293,15 @@
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
@@ -316,16 +320,19 @@
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
@@ -409,15 +416,17 @@
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
@@ -460,13 +469,14 @@
     "ca-central-1",
     "eu-central-1",
     "eu-north-1",
     "eu-south-1",
     "eu-west-1",
     "eu-west-2",
     "eu-west-3",
+    "me-central-1",
     "sa-east-1",
     "us-east-1",
     "us-east-2",
     "us-west-1",
     "us-west-2",
 ]
```

### Comparing `types-aiobotocore-snowball-2.5.0.post1/types_aiobotocore_snowball/paginator.py` & `types-aiobotocore-snowball-2.5.1/types_aiobotocore_snowball/paginator.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -26,137 +26,122 @@
         list_cluster_jobs_paginator: ListClusterJobsPaginator = client.get_paginator("list_cluster_jobs")
         list_clusters_paginator: ListClustersPaginator = client.get_paginator("list_clusters")
         list_compatible_images_paginator: ListCompatibleImagesPaginator = client.get_paginator("list_compatible_images")
         list_jobs_paginator: ListJobsPaginator = client.get_paginator("list_jobs")
         list_long_term_pricing_paginator: ListLongTermPricingPaginator = client.get_paginator("list_long_term_pricing")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DescribeAddressesResultTypeDef,
     ListClusterJobsResultTypeDef,
     ListClustersResultTypeDef,
     ListCompatibleImagesResultTypeDef,
     ListJobsResultTypeDef,
     ListLongTermPricingResultTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "DescribeAddressesPaginator",
     "ListClusterJobsPaginator",
     "ListClustersPaginator",
     "ListCompatibleImagesPaginator",
     "ListJobsPaginator",
     "ListLongTermPricingPaginator",
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
 class DescribeAddressesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snowball.html#Snowball.Paginator.DescribeAddresses)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball/paginators/#describeaddressespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeAddressesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snowball.html#Snowball.Paginator.DescribeAddresses.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball/paginators/#describeaddressespaginator)
         """
 
-
 class ListClusterJobsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snowball.html#Snowball.Paginator.ListClusterJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball/paginators/#listclusterjobspaginator)
     """
 
     def paginate(
-        self, *, ClusterId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ClusterId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListClusterJobsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snowball.html#Snowball.Paginator.ListClusterJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball/paginators/#listclusterjobspaginator)
         """
 
-
 class ListClustersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snowball.html#Snowball.Paginator.ListClusters)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball/paginators/#listclusterspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListClustersResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snowball.html#Snowball.Paginator.ListClusters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball/paginators/#listclusterspaginator)
         """
 
-
 class ListCompatibleImagesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snowball.html#Snowball.Paginator.ListCompatibleImages)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball/paginators/#listcompatibleimagespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCompatibleImagesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snowball.html#Snowball.Paginator.ListCompatibleImages.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball/paginators/#listcompatibleimagespaginator)
         """
 
-
 class ListJobsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snowball.html#Snowball.Paginator.ListJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball/paginators/#listjobspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListJobsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snowball.html#Snowball.Paginator.ListJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball/paginators/#listjobspaginator)
         """
 
-
 class ListLongTermPricingPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snowball.html#Snowball.Paginator.ListLongTermPricing)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball/paginators/#listlongtermpricingpaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListLongTermPricingResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snowball.html#Snowball.Paginator.ListLongTermPricing.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball/paginators/#listlongtermpricingpaginator)
         """
```

### Comparing `types-aiobotocore-snowball-2.5.0.post1/types_aiobotocore_snowball/paginator.pyi` & `types-aiobotocore-snowball-2.5.1/types_aiobotocore_snowball/paginator.py`

 * *Files 4% similar despite different names*

```diff
@@ -26,128 +26,130 @@
         list_cluster_jobs_paginator: ListClusterJobsPaginator = client.get_paginator("list_cluster_jobs")
         list_clusters_paginator: ListClustersPaginator = client.get_paginator("list_clusters")
         list_compatible_images_paginator: ListCompatibleImagesPaginator = client.get_paginator("list_compatible_images")
         list_jobs_paginator: ListJobsPaginator = client.get_paginator("list_jobs")
         list_long_term_pricing_paginator: ListLongTermPricingPaginator = client.get_paginator("list_long_term_pricing")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     DescribeAddressesResultTypeDef,
     ListClusterJobsResultTypeDef,
     ListClustersResultTypeDef,
     ListCompatibleImagesResultTypeDef,
     ListJobsResultTypeDef,
     ListLongTermPricingResultTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "DescribeAddressesPaginator",
     "ListClusterJobsPaginator",
     "ListClustersPaginator",
     "ListCompatibleImagesPaginator",
     "ListJobsPaginator",
     "ListLongTermPricingPaginator",
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
 class DescribeAddressesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snowball.html#Snowball.Paginator.DescribeAddresses)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball/paginators/#describeaddressespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[DescribeAddressesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snowball.html#Snowball.Paginator.DescribeAddresses.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball/paginators/#describeaddressespaginator)
         """
 
+
 class ListClusterJobsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snowball.html#Snowball.Paginator.ListClusterJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball/paginators/#listclusterjobspaginator)
     """
 
     def paginate(
-        self, *, ClusterId: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, ClusterId: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListClusterJobsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snowball.html#Snowball.Paginator.ListClusterJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball/paginators/#listclusterjobspaginator)
         """
 
+
 class ListClustersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snowball.html#Snowball.Paginator.ListClusters)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball/paginators/#listclusterspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListClustersResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snowball.html#Snowball.Paginator.ListClusters.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball/paginators/#listclusterspaginator)
         """
 
+
 class ListCompatibleImagesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snowball.html#Snowball.Paginator.ListCompatibleImages)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball/paginators/#listcompatibleimagespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListCompatibleImagesResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snowball.html#Snowball.Paginator.ListCompatibleImages.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball/paginators/#listcompatibleimagespaginator)
         """
 
+
 class ListJobsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snowball.html#Snowball.Paginator.ListJobs)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball/paginators/#listjobspaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListJobsResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snowball.html#Snowball.Paginator.ListJobs.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball/paginators/#listjobspaginator)
         """
 
+
 class ListLongTermPricingPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snowball.html#Snowball.Paginator.ListLongTermPricing)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball/paginators/#listlongtermpricingpaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListLongTermPricingResultTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snowball.html#Snowball.Paginator.ListLongTermPricing.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball/paginators/#listlongtermpricingpaginator)
         """
```

### Comparing `types-aiobotocore-snowball-2.5.0.post1/types_aiobotocore_snowball/type_defs.py` & `types-aiobotocore-snowball-2.5.1/types_aiobotocore_snowball/type_defs.py`

 * *Files 6% similar despite different names*

```diff
@@ -44,74 +44,75 @@
 __all__ = (
     "AddressTypeDef",
     "CancelClusterRequestRequestTypeDef",
     "CancelJobRequestRequestTypeDef",
     "ClusterListEntryTypeDef",
     "NotificationTypeDef",
     "CompatibleImageTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateAddressResultTypeDef",
+    "JobListEntryTypeDef",
+    "CreateJobResultTypeDef",
     "CreateLongTermPricingRequestRequestTypeDef",
+    "CreateLongTermPricingResultTypeDef",
     "CreateReturnShippingLabelRequestRequestTypeDef",
+    "CreateReturnShippingLabelResultTypeDef",
     "DataTransferTypeDef",
     "ServiceVersionTypeDef",
     "DescribeAddressRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeAddressesRequestDescribeAddressesPaginateTypeDef",
     "DescribeAddressesRequestRequestTypeDef",
     "DescribeClusterRequestRequestTypeDef",
     "DescribeJobRequestRequestTypeDef",
     "DescribeReturnShippingLabelRequestRequestTypeDef",
+    "DescribeReturnShippingLabelResultTypeDef",
     "EKSOnDeviceServiceConfigurationTypeDef",
     "Ec2AmiResourceTypeDef",
     "EventTriggerDefinitionTypeDef",
     "GetJobManifestRequestRequestTypeDef",
+    "GetJobManifestResultTypeDef",
     "GetJobUnlockCodeRequestRequestTypeDef",
+    "GetJobUnlockCodeResultTypeDef",
+    "GetSnowballUsageResultTypeDef",
     "GetSoftwareUpdatesRequestRequestTypeDef",
+    "GetSoftwareUpdatesResultTypeDef",
     "INDTaxDocumentsTypeDef",
-    "JobListEntryTypeDef",
     "JobLogsTypeDef",
     "KeyRangeTypeDef",
+    "ListClusterJobsRequestListClusterJobsPaginateTypeDef",
     "ListClusterJobsRequestRequestTypeDef",
+    "ListClustersRequestListClustersPaginateTypeDef",
     "ListClustersRequestRequestTypeDef",
+    "ListCompatibleImagesRequestListCompatibleImagesPaginateTypeDef",
     "ListCompatibleImagesRequestRequestTypeDef",
+    "ListJobsRequestListJobsPaginateTypeDef",
     "ListJobsRequestRequestTypeDef",
+    "ListLongTermPricingRequestListLongTermPricingPaginateTypeDef",
     "ListLongTermPricingRequestRequestTypeDef",
     "LongTermPricingListEntryTypeDef",
     "NFSOnDeviceServiceConfigurationTypeDef",
+    "S3OnDeviceServiceConfigurationTypeDef",
     "TGWOnDeviceServiceConfigurationTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "TargetOnDeviceServiceTypeDef",
     "ShipmentTypeDef",
     "WirelessConnectionTypeDef",
     "UpdateJobShipmentStateRequestRequestTypeDef",
     "UpdateLongTermPricingRequestRequestTypeDef",
     "CreateAddressRequestRequestTypeDef",
-    "CreateAddressResultTypeDef",
-    "CreateClusterResultTypeDef",
-    "CreateJobResultTypeDef",
-    "CreateLongTermPricingResultTypeDef",
-    "CreateReturnShippingLabelResultTypeDef",
     "DescribeAddressResultTypeDef",
     "DescribeAddressesResultTypeDef",
-    "DescribeReturnShippingLabelResultTypeDef",
-    "GetJobManifestResultTypeDef",
-    "GetJobUnlockCodeResultTypeDef",
-    "GetSnowballUsageResultTypeDef",
-    "GetSoftwareUpdatesResultTypeDef",
     "ListClustersResultTypeDef",
     "ListCompatibleImagesResultTypeDef",
+    "CreateClusterResultTypeDef",
+    "ListClusterJobsResultTypeDef",
+    "ListJobsResultTypeDef",
     "DependentServiceTypeDef",
-    "DescribeAddressesRequestDescribeAddressesPaginateTypeDef",
-    "ListClusterJobsRequestListClusterJobsPaginateTypeDef",
-    "ListClustersRequestListClustersPaginateTypeDef",
-    "ListCompatibleImagesRequestListCompatibleImagesPaginateTypeDef",
-    "ListJobsRequestListJobsPaginateTypeDef",
-    "ListLongTermPricingRequestListLongTermPricingPaginateTypeDef",
     "LambdaResourceTypeDef",
     "TaxDocumentsTypeDef",
-    "ListClusterJobsResultTypeDef",
-    "ListJobsResultTypeDef",
     "ListLongTermPricingResultTypeDef",
     "OnDeviceServiceConfigurationTypeDef",
     "S3ResourceTypeDef",
     "ShippingDetailsTypeDef",
     "SnowconeDeviceConfigurationTypeDef",
     "ListServiceVersionsRequestRequestTypeDef",
     "ListServiceVersionsResultTypeDef",
@@ -188,22 +189,41 @@
     {
         "AmiId": str,
         "Name": str,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateAddressResultTypeDef = TypedDict(
+    "CreateAddressResultTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "AddressId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+JobListEntryTypeDef = TypedDict(
+    "JobListEntryTypeDef",
+    {
+        "JobId": str,
+        "JobState": JobStateType,
+        "IsMaster": bool,
+        "JobType": JobTypeType,
+        "SnowballType": SnowballTypeType,
+        "CreationDate": datetime,
+        "Description": str,
+    },
+    total=False,
+)
+
+CreateJobResultTypeDef = TypedDict(
+    "CreateJobResultTypeDef",
+    {
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateLongTermPricingRequestRequestTypeDef = TypedDict(
     "_RequiredCreateLongTermPricingRequestRequestTypeDef",
     {
         "LongTermPricingType": LongTermPricingTypeType,
@@ -222,14 +242,22 @@
 class CreateLongTermPricingRequestRequestTypeDef(
     _RequiredCreateLongTermPricingRequestRequestTypeDef,
     _OptionalCreateLongTermPricingRequestRequestTypeDef,
 ):
     pass
 
 
+CreateLongTermPricingResultTypeDef = TypedDict(
+    "CreateLongTermPricingResultTypeDef",
+    {
+        "LongTermPricingId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateReturnShippingLabelRequestRequestTypeDef = TypedDict(
     "_RequiredCreateReturnShippingLabelRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 _OptionalCreateReturnShippingLabelRequestRequestTypeDef = TypedDict(
@@ -244,14 +272,22 @@
 class CreateReturnShippingLabelRequestRequestTypeDef(
     _RequiredCreateReturnShippingLabelRequestRequestTypeDef,
     _OptionalCreateReturnShippingLabelRequestRequestTypeDef,
 ):
     pass
 
 
+CreateReturnShippingLabelResultTypeDef = TypedDict(
+    "CreateReturnShippingLabelResultTypeDef",
+    {
+        "Status": ShippingLabelStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DataTransferTypeDef = TypedDict(
     "DataTransferTypeDef",
     {
         "BytesTransferred": int,
         "ObjectsTransferred": int,
         "TotalBytes": int,
         "TotalObjects": int,
@@ -270,20 +306,18 @@
 DescribeAddressRequestRequestTypeDef = TypedDict(
     "DescribeAddressRequestRequestTypeDef",
     {
         "AddressId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeAddressesRequestDescribeAddressesPaginateTypeDef = TypedDict(
+    "DescribeAddressesRequestDescribeAddressesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeAddressesRequestRequestTypeDef = TypedDict(
     "DescribeAddressesRequestRequestTypeDef",
     {
@@ -310,14 +344,24 @@
 DescribeReturnShippingLabelRequestRequestTypeDef = TypedDict(
     "DescribeReturnShippingLabelRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 
+DescribeReturnShippingLabelResultTypeDef = TypedDict(
+    "DescribeReturnShippingLabelResultTypeDef",
+    {
+        "Status": ShippingLabelStatusType,
+        "ExpirationDate": datetime,
+        "ReturnShippingLabelURI": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EKSOnDeviceServiceConfigurationTypeDef = TypedDict(
     "EKSOnDeviceServiceConfigurationTypeDef",
     {
         "KubernetesVersion": str,
         "EKSAnywhereVersion": str,
     },
     total=False,
@@ -353,46 +397,65 @@
 GetJobManifestRequestRequestTypeDef = TypedDict(
     "GetJobManifestRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 
+GetJobManifestResultTypeDef = TypedDict(
+    "GetJobManifestResultTypeDef",
+    {
+        "ManifestURI": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetJobUnlockCodeRequestRequestTypeDef = TypedDict(
     "GetJobUnlockCodeRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 
+GetJobUnlockCodeResultTypeDef = TypedDict(
+    "GetJobUnlockCodeResultTypeDef",
+    {
+        "UnlockCode": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetSnowballUsageResultTypeDef = TypedDict(
+    "GetSnowballUsageResultTypeDef",
+    {
+        "SnowballLimit": int,
+        "SnowballsInUse": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetSoftwareUpdatesRequestRequestTypeDef = TypedDict(
     "GetSoftwareUpdatesRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 
-INDTaxDocumentsTypeDef = TypedDict(
-    "INDTaxDocumentsTypeDef",
+GetSoftwareUpdatesResultTypeDef = TypedDict(
+    "GetSoftwareUpdatesResultTypeDef",
     {
-        "GSTIN": str,
+        "UpdatesURI": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-JobListEntryTypeDef = TypedDict(
-    "JobListEntryTypeDef",
+INDTaxDocumentsTypeDef = TypedDict(
+    "INDTaxDocumentsTypeDef",
     {
-        "JobId": str,
-        "JobState": JobStateType,
-        "IsMaster": bool,
-        "JobType": JobTypeType,
-        "SnowballType": SnowballTypeType,
-        "CreationDate": datetime,
-        "Description": str,
+        "GSTIN": str,
     },
     total=False,
 )
 
 JobLogsTypeDef = TypedDict(
     "JobLogsTypeDef",
     {
@@ -408,14 +471,36 @@
     {
         "BeginMarker": str,
         "EndMarker": str,
     },
     total=False,
 )
 
+_RequiredListClusterJobsRequestListClusterJobsPaginateTypeDef = TypedDict(
+    "_RequiredListClusterJobsRequestListClusterJobsPaginateTypeDef",
+    {
+        "ClusterId": str,
+    },
+)
+_OptionalListClusterJobsRequestListClusterJobsPaginateTypeDef = TypedDict(
+    "_OptionalListClusterJobsRequestListClusterJobsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListClusterJobsRequestListClusterJobsPaginateTypeDef(
+    _RequiredListClusterJobsRequestListClusterJobsPaginateTypeDef,
+    _OptionalListClusterJobsRequestListClusterJobsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListClusterJobsRequestRequestTypeDef = TypedDict(
     "_RequiredListClusterJobsRequestRequestTypeDef",
     {
         "ClusterId": str,
     },
 )
 _OptionalListClusterJobsRequestRequestTypeDef = TypedDict(
@@ -430,41 +515,73 @@
 
 class ListClusterJobsRequestRequestTypeDef(
     _RequiredListClusterJobsRequestRequestTypeDef, _OptionalListClusterJobsRequestRequestTypeDef
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
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListCompatibleImagesRequestListCompatibleImagesPaginateTypeDef = TypedDict(
+    "ListCompatibleImagesRequestListCompatibleImagesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCompatibleImagesRequestRequestTypeDef = TypedDict(
     "ListCompatibleImagesRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListJobsRequestListJobsPaginateTypeDef = TypedDict(
+    "ListJobsRequestListJobsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListJobsRequestRequestTypeDef = TypedDict(
     "ListJobsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListLongTermPricingRequestListLongTermPricingPaginateTypeDef = TypedDict(
+    "ListLongTermPricingRequestListLongTermPricingPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListLongTermPricingRequestRequestTypeDef = TypedDict(
     "ListLongTermPricingRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -492,23 +609,55 @@
     {
         "StorageLimit": int,
         "StorageUnit": Literal["TB"],
     },
     total=False,
 )
 
+S3OnDeviceServiceConfigurationTypeDef = TypedDict(
+    "S3OnDeviceServiceConfigurationTypeDef",
+    {
+        "StorageLimit": float,
+        "StorageUnit": Literal["TB"],
+        "ServiceSize": int,
+        "FaultTolerance": int,
+    },
+    total=False,
+)
+
 TGWOnDeviceServiceConfigurationTypeDef = TypedDict(
     "TGWOnDeviceServiceConfigurationTypeDef",
     {
         "StorageLimit": int,
         "StorageUnit": Literal["TB"],
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
 TargetOnDeviceServiceTypeDef = TypedDict(
     "TargetOnDeviceServiceTypeDef",
     {
         "ServiceName": DeviceServiceNameType,
         "TransferOption": TransferOptionType,
     },
     total=False,
@@ -565,199 +714,81 @@
 CreateAddressRequestRequestTypeDef = TypedDict(
     "CreateAddressRequestRequestTypeDef",
     {
         "Address": AddressTypeDef,
     },
 )
 
-CreateAddressResultTypeDef = TypedDict(
-    "CreateAddressResultTypeDef",
-    {
-        "AddressId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateClusterResultTypeDef = TypedDict(
-    "CreateClusterResultTypeDef",
-    {
-        "ClusterId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateJobResultTypeDef = TypedDict(
-    "CreateJobResultTypeDef",
-    {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateLongTermPricingResultTypeDef = TypedDict(
-    "CreateLongTermPricingResultTypeDef",
-    {
-        "LongTermPricingId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateReturnShippingLabelResultTypeDef = TypedDict(
-    "CreateReturnShippingLabelResultTypeDef",
-    {
-        "Status": ShippingLabelStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 DescribeAddressResultTypeDef = TypedDict(
     "DescribeAddressResultTypeDef",
     {
         "Address": AddressTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAddressesResultTypeDef = TypedDict(
     "DescribeAddressesResultTypeDef",
     {
         "Addresses": List[AddressTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeReturnShippingLabelResultTypeDef = TypedDict(
-    "DescribeReturnShippingLabelResultTypeDef",
-    {
-        "Status": ShippingLabelStatusType,
-        "ExpirationDate": datetime,
-        "ReturnShippingLabelURI": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetJobManifestResultTypeDef = TypedDict(
-    "GetJobManifestResultTypeDef",
-    {
-        "ManifestURI": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetJobUnlockCodeResultTypeDef = TypedDict(
-    "GetJobUnlockCodeResultTypeDef",
-    {
-        "UnlockCode": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSnowballUsageResultTypeDef = TypedDict(
-    "GetSnowballUsageResultTypeDef",
-    {
-        "SnowballLimit": int,
-        "SnowballsInUse": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSoftwareUpdatesResultTypeDef = TypedDict(
-    "GetSoftwareUpdatesResultTypeDef",
-    {
-        "UpdatesURI": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListClustersResultTypeDef = TypedDict(
     "ListClustersResultTypeDef",
     {
         "ClusterListEntries": List[ClusterListEntryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCompatibleImagesResultTypeDef = TypedDict(
     "ListCompatibleImagesResultTypeDef",
     {
         "CompatibleImages": List[CompatibleImageTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DependentServiceTypeDef = TypedDict(
-    "DependentServiceTypeDef",
-    {
-        "ServiceName": ServiceNameType,
-        "ServiceVersion": ServiceVersionTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-DescribeAddressesRequestDescribeAddressesPaginateTypeDef = TypedDict(
-    "DescribeAddressesRequestDescribeAddressesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListClusterJobsRequestListClusterJobsPaginateTypeDef = TypedDict(
-    "_RequiredListClusterJobsRequestListClusterJobsPaginateTypeDef",
+CreateClusterResultTypeDef = TypedDict(
+    "CreateClusterResultTypeDef",
     {
         "ClusterId": str,
+        "JobListEntries": List[JobListEntryTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalListClusterJobsRequestListClusterJobsPaginateTypeDef = TypedDict(
-    "_OptionalListClusterJobsRequestListClusterJobsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListClusterJobsRequestListClusterJobsPaginateTypeDef(
-    _RequiredListClusterJobsRequestListClusterJobsPaginateTypeDef,
-    _OptionalListClusterJobsRequestListClusterJobsPaginateTypeDef,
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
 
-ListCompatibleImagesRequestListCompatibleImagesPaginateTypeDef = TypedDict(
-    "ListCompatibleImagesRequestListCompatibleImagesPaginateTypeDef",
+ListClusterJobsResultTypeDef = TypedDict(
+    "ListClusterJobsResultTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "JobListEntries": List[JobListEntryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-ListJobsRequestListJobsPaginateTypeDef = TypedDict(
-    "ListJobsRequestListJobsPaginateTypeDef",
+ListJobsResultTypeDef = TypedDict(
+    "ListJobsResultTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "JobListEntries": List[JobListEntryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-ListLongTermPricingRequestListLongTermPricingPaginateTypeDef = TypedDict(
-    "ListLongTermPricingRequestListLongTermPricingPaginateTypeDef",
+DependentServiceTypeDef = TypedDict(
+    "DependentServiceTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ServiceName": ServiceNameType,
+        "ServiceVersion": ServiceVersionTypeDef,
     },
     total=False,
 )
 
 LambdaResourceTypeDef = TypedDict(
     "LambdaResourceTypeDef",
     {
@@ -771,47 +802,30 @@
     "TaxDocumentsTypeDef",
     {
         "IND": INDTaxDocumentsTypeDef,
     },
     total=False,
 )
 
-ListClusterJobsResultTypeDef = TypedDict(
-    "ListClusterJobsResultTypeDef",
-    {
-        "JobListEntries": List[JobListEntryTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListJobsResultTypeDef = TypedDict(
-    "ListJobsResultTypeDef",
-    {
-        "JobListEntries": List[JobListEntryTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ListLongTermPricingResultTypeDef = TypedDict(
     "ListLongTermPricingResultTypeDef",
     {
         "LongTermPricingEntries": List[LongTermPricingListEntryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OnDeviceServiceConfigurationTypeDef = TypedDict(
     "OnDeviceServiceConfigurationTypeDef",
     {
         "NFSOnDeviceService": NFSOnDeviceServiceConfigurationTypeDef,
         "TGWOnDeviceService": TGWOnDeviceServiceConfigurationTypeDef,
         "EKSOnDeviceService": EKSOnDeviceServiceConfigurationTypeDef,
+        "S3OnDeviceService": S3OnDeviceServiceConfigurationTypeDef,
     },
     total=False,
 )
 
 S3ResourceTypeDef = TypedDict(
     "S3ResourceTypeDef",
     {
@@ -867,15 +881,15 @@
 ListServiceVersionsResultTypeDef = TypedDict(
     "ListServiceVersionsResultTypeDef",
     {
         "ServiceVersions": List[ServiceVersionTypeDef],
         "ServiceName": ServiceNameType,
         "DependentServices": List[DependentServiceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 JobResourceTypeDef = TypedDict(
     "JobResourceTypeDef",
     {
         "S3Resources": Sequence[S3ResourceTypeDef],
@@ -915,31 +929,35 @@
     total=False,
 )
 
 _RequiredCreateClusterRequestRequestTypeDef = TypedDict(
     "_RequiredCreateClusterRequestRequestTypeDef",
     {
         "JobType": JobTypeType,
-        "Resources": JobResourceTypeDef,
         "AddressId": str,
-        "RoleARN": str,
         "SnowballType": SnowballTypeType,
         "ShippingOption": ShippingOptionType,
     },
 )
 _OptionalCreateClusterRequestRequestTypeDef = TypedDict(
     "_OptionalCreateClusterRequestRequestTypeDef",
     {
+        "Resources": JobResourceTypeDef,
         "OnDeviceServiceConfiguration": OnDeviceServiceConfigurationTypeDef,
         "Description": str,
         "KmsKeyARN": str,
+        "RoleARN": str,
         "Notification": NotificationTypeDef,
         "ForwardingAddressId": str,
         "TaxDocuments": TaxDocumentsTypeDef,
         "RemoteManagement": RemoteManagementType,
+        "InitialClusterSize": int,
+        "ForceCreateJobs": bool,
+        "LongTermPricingIds": Sequence[str],
+        "SnowballCapacityPreference": SnowballCapacityType,
     },
     total=False,
 )
 
 
 class CreateClusterRequestRequestTypeDef(
     _RequiredCreateClusterRequestRequestTypeDef, _OptionalCreateClusterRequestRequestTypeDef
@@ -1057,19 +1075,19 @@
     total=False,
 )
 
 DescribeClusterResultTypeDef = TypedDict(
     "DescribeClusterResultTypeDef",
     {
         "ClusterMetadata": ClusterMetadataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeJobResultTypeDef = TypedDict(
     "DescribeJobResultTypeDef",
     {
         "JobMetadata": JobMetadataTypeDef,
         "SubJobMetadata": List[JobMetadataTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-snowball-2.5.0.post1/types_aiobotocore_snowball/type_defs.pyi` & `types-aiobotocore-snowball-2.5.1/types_aiobotocore_snowball/type_defs.pyi`

 * *Files 6% similar despite different names*

```diff
@@ -43,74 +43,75 @@
 __all__ = (
     "AddressTypeDef",
     "CancelClusterRequestRequestTypeDef",
     "CancelJobRequestRequestTypeDef",
     "ClusterListEntryTypeDef",
     "NotificationTypeDef",
     "CompatibleImageTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateAddressResultTypeDef",
+    "JobListEntryTypeDef",
+    "CreateJobResultTypeDef",
     "CreateLongTermPricingRequestRequestTypeDef",
+    "CreateLongTermPricingResultTypeDef",
     "CreateReturnShippingLabelRequestRequestTypeDef",
+    "CreateReturnShippingLabelResultTypeDef",
     "DataTransferTypeDef",
     "ServiceVersionTypeDef",
     "DescribeAddressRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "DescribeAddressesRequestDescribeAddressesPaginateTypeDef",
     "DescribeAddressesRequestRequestTypeDef",
     "DescribeClusterRequestRequestTypeDef",
     "DescribeJobRequestRequestTypeDef",
     "DescribeReturnShippingLabelRequestRequestTypeDef",
+    "DescribeReturnShippingLabelResultTypeDef",
     "EKSOnDeviceServiceConfigurationTypeDef",
     "Ec2AmiResourceTypeDef",
     "EventTriggerDefinitionTypeDef",
     "GetJobManifestRequestRequestTypeDef",
+    "GetJobManifestResultTypeDef",
     "GetJobUnlockCodeRequestRequestTypeDef",
+    "GetJobUnlockCodeResultTypeDef",
+    "GetSnowballUsageResultTypeDef",
     "GetSoftwareUpdatesRequestRequestTypeDef",
+    "GetSoftwareUpdatesResultTypeDef",
     "INDTaxDocumentsTypeDef",
-    "JobListEntryTypeDef",
     "JobLogsTypeDef",
     "KeyRangeTypeDef",
+    "ListClusterJobsRequestListClusterJobsPaginateTypeDef",
     "ListClusterJobsRequestRequestTypeDef",
+    "ListClustersRequestListClustersPaginateTypeDef",
     "ListClustersRequestRequestTypeDef",
+    "ListCompatibleImagesRequestListCompatibleImagesPaginateTypeDef",
     "ListCompatibleImagesRequestRequestTypeDef",
+    "ListJobsRequestListJobsPaginateTypeDef",
     "ListJobsRequestRequestTypeDef",
+    "ListLongTermPricingRequestListLongTermPricingPaginateTypeDef",
     "ListLongTermPricingRequestRequestTypeDef",
     "LongTermPricingListEntryTypeDef",
     "NFSOnDeviceServiceConfigurationTypeDef",
+    "S3OnDeviceServiceConfigurationTypeDef",
     "TGWOnDeviceServiceConfigurationTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "TargetOnDeviceServiceTypeDef",
     "ShipmentTypeDef",
     "WirelessConnectionTypeDef",
     "UpdateJobShipmentStateRequestRequestTypeDef",
     "UpdateLongTermPricingRequestRequestTypeDef",
     "CreateAddressRequestRequestTypeDef",
-    "CreateAddressResultTypeDef",
-    "CreateClusterResultTypeDef",
-    "CreateJobResultTypeDef",
-    "CreateLongTermPricingResultTypeDef",
-    "CreateReturnShippingLabelResultTypeDef",
     "DescribeAddressResultTypeDef",
     "DescribeAddressesResultTypeDef",
-    "DescribeReturnShippingLabelResultTypeDef",
-    "GetJobManifestResultTypeDef",
-    "GetJobUnlockCodeResultTypeDef",
-    "GetSnowballUsageResultTypeDef",
-    "GetSoftwareUpdatesResultTypeDef",
     "ListClustersResultTypeDef",
     "ListCompatibleImagesResultTypeDef",
+    "CreateClusterResultTypeDef",
+    "ListClusterJobsResultTypeDef",
+    "ListJobsResultTypeDef",
     "DependentServiceTypeDef",
-    "DescribeAddressesRequestDescribeAddressesPaginateTypeDef",
-    "ListClusterJobsRequestListClusterJobsPaginateTypeDef",
-    "ListClustersRequestListClustersPaginateTypeDef",
-    "ListCompatibleImagesRequestListCompatibleImagesPaginateTypeDef",
-    "ListJobsRequestListJobsPaginateTypeDef",
-    "ListLongTermPricingRequestListLongTermPricingPaginateTypeDef",
     "LambdaResourceTypeDef",
     "TaxDocumentsTypeDef",
-    "ListClusterJobsResultTypeDef",
-    "ListJobsResultTypeDef",
     "ListLongTermPricingResultTypeDef",
     "OnDeviceServiceConfigurationTypeDef",
     "S3ResourceTypeDef",
     "ShippingDetailsTypeDef",
     "SnowconeDeviceConfigurationTypeDef",
     "ListServiceVersionsRequestRequestTypeDef",
     "ListServiceVersionsResultTypeDef",
@@ -187,22 +188,41 @@
     {
         "AmiId": str,
         "Name": str,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateAddressResultTypeDef = TypedDict(
+    "CreateAddressResultTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "AddressId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+JobListEntryTypeDef = TypedDict(
+    "JobListEntryTypeDef",
+    {
+        "JobId": str,
+        "JobState": JobStateType,
+        "IsMaster": bool,
+        "JobType": JobTypeType,
+        "SnowballType": SnowballTypeType,
+        "CreationDate": datetime,
+        "Description": str,
+    },
+    total=False,
+)
+
+CreateJobResultTypeDef = TypedDict(
+    "CreateJobResultTypeDef",
+    {
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateLongTermPricingRequestRequestTypeDef = TypedDict(
     "_RequiredCreateLongTermPricingRequestRequestTypeDef",
     {
         "LongTermPricingType": LongTermPricingTypeType,
@@ -219,14 +239,22 @@
 
 class CreateLongTermPricingRequestRequestTypeDef(
     _RequiredCreateLongTermPricingRequestRequestTypeDef,
     _OptionalCreateLongTermPricingRequestRequestTypeDef,
 ):
     pass
 
+CreateLongTermPricingResultTypeDef = TypedDict(
+    "CreateLongTermPricingResultTypeDef",
+    {
+        "LongTermPricingId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateReturnShippingLabelRequestRequestTypeDef = TypedDict(
     "_RequiredCreateReturnShippingLabelRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 _OptionalCreateReturnShippingLabelRequestRequestTypeDef = TypedDict(
@@ -239,14 +267,22 @@
 
 class CreateReturnShippingLabelRequestRequestTypeDef(
     _RequiredCreateReturnShippingLabelRequestRequestTypeDef,
     _OptionalCreateReturnShippingLabelRequestRequestTypeDef,
 ):
     pass
 
+CreateReturnShippingLabelResultTypeDef = TypedDict(
+    "CreateReturnShippingLabelResultTypeDef",
+    {
+        "Status": ShippingLabelStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DataTransferTypeDef = TypedDict(
     "DataTransferTypeDef",
     {
         "BytesTransferred": int,
         "ObjectsTransferred": int,
         "TotalBytes": int,
         "TotalObjects": int,
@@ -265,20 +301,18 @@
 DescribeAddressRequestRequestTypeDef = TypedDict(
     "DescribeAddressRequestRequestTypeDef",
     {
         "AddressId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+DescribeAddressesRequestDescribeAddressesPaginateTypeDef = TypedDict(
+    "DescribeAddressesRequestDescribeAddressesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
 DescribeAddressesRequestRequestTypeDef = TypedDict(
     "DescribeAddressesRequestRequestTypeDef",
     {
@@ -305,14 +339,24 @@
 DescribeReturnShippingLabelRequestRequestTypeDef = TypedDict(
     "DescribeReturnShippingLabelRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 
+DescribeReturnShippingLabelResultTypeDef = TypedDict(
+    "DescribeReturnShippingLabelResultTypeDef",
+    {
+        "Status": ShippingLabelStatusType,
+        "ExpirationDate": datetime,
+        "ReturnShippingLabelURI": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 EKSOnDeviceServiceConfigurationTypeDef = TypedDict(
     "EKSOnDeviceServiceConfigurationTypeDef",
     {
         "KubernetesVersion": str,
         "EKSAnywhereVersion": str,
     },
     total=False,
@@ -346,46 +390,65 @@
 GetJobManifestRequestRequestTypeDef = TypedDict(
     "GetJobManifestRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 
+GetJobManifestResultTypeDef = TypedDict(
+    "GetJobManifestResultTypeDef",
+    {
+        "ManifestURI": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetJobUnlockCodeRequestRequestTypeDef = TypedDict(
     "GetJobUnlockCodeRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 
+GetJobUnlockCodeResultTypeDef = TypedDict(
+    "GetJobUnlockCodeResultTypeDef",
+    {
+        "UnlockCode": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+GetSnowballUsageResultTypeDef = TypedDict(
+    "GetSnowballUsageResultTypeDef",
+    {
+        "SnowballLimit": int,
+        "SnowballsInUse": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetSoftwareUpdatesRequestRequestTypeDef = TypedDict(
     "GetSoftwareUpdatesRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 
-INDTaxDocumentsTypeDef = TypedDict(
-    "INDTaxDocumentsTypeDef",
+GetSoftwareUpdatesResultTypeDef = TypedDict(
+    "GetSoftwareUpdatesResultTypeDef",
     {
-        "GSTIN": str,
+        "UpdatesURI": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-JobListEntryTypeDef = TypedDict(
-    "JobListEntryTypeDef",
+INDTaxDocumentsTypeDef = TypedDict(
+    "INDTaxDocumentsTypeDef",
     {
-        "JobId": str,
-        "JobState": JobStateType,
-        "IsMaster": bool,
-        "JobType": JobTypeType,
-        "SnowballType": SnowballTypeType,
-        "CreationDate": datetime,
-        "Description": str,
+        "GSTIN": str,
     },
     total=False,
 )
 
 JobLogsTypeDef = TypedDict(
     "JobLogsTypeDef",
     {
@@ -401,14 +464,34 @@
     {
         "BeginMarker": str,
         "EndMarker": str,
     },
     total=False,
 )
 
+_RequiredListClusterJobsRequestListClusterJobsPaginateTypeDef = TypedDict(
+    "_RequiredListClusterJobsRequestListClusterJobsPaginateTypeDef",
+    {
+        "ClusterId": str,
+    },
+)
+_OptionalListClusterJobsRequestListClusterJobsPaginateTypeDef = TypedDict(
+    "_OptionalListClusterJobsRequestListClusterJobsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListClusterJobsRequestListClusterJobsPaginateTypeDef(
+    _RequiredListClusterJobsRequestListClusterJobsPaginateTypeDef,
+    _OptionalListClusterJobsRequestListClusterJobsPaginateTypeDef,
+):
+    pass
+
 _RequiredListClusterJobsRequestRequestTypeDef = TypedDict(
     "_RequiredListClusterJobsRequestRequestTypeDef",
     {
         "ClusterId": str,
     },
 )
 _OptionalListClusterJobsRequestRequestTypeDef = TypedDict(
@@ -421,41 +504,73 @@
 )
 
 class ListClusterJobsRequestRequestTypeDef(
     _RequiredListClusterJobsRequestRequestTypeDef, _OptionalListClusterJobsRequestRequestTypeDef
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
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListCompatibleImagesRequestListCompatibleImagesPaginateTypeDef = TypedDict(
+    "ListCompatibleImagesRequestListCompatibleImagesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListCompatibleImagesRequestRequestTypeDef = TypedDict(
     "ListCompatibleImagesRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListJobsRequestListJobsPaginateTypeDef = TypedDict(
+    "ListJobsRequestListJobsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListJobsRequestRequestTypeDef = TypedDict(
     "ListJobsRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
 )
 
+ListLongTermPricingRequestListLongTermPricingPaginateTypeDef = TypedDict(
+    "ListLongTermPricingRequestListLongTermPricingPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListLongTermPricingRequestRequestTypeDef = TypedDict(
     "ListLongTermPricingRequestRequestTypeDef",
     {
         "MaxResults": int,
         "NextToken": str,
     },
     total=False,
@@ -483,23 +598,55 @@
     {
         "StorageLimit": int,
         "StorageUnit": Literal["TB"],
     },
     total=False,
 )
 
+S3OnDeviceServiceConfigurationTypeDef = TypedDict(
+    "S3OnDeviceServiceConfigurationTypeDef",
+    {
+        "StorageLimit": float,
+        "StorageUnit": Literal["TB"],
+        "ServiceSize": int,
+        "FaultTolerance": int,
+    },
+    total=False,
+)
+
 TGWOnDeviceServiceConfigurationTypeDef = TypedDict(
     "TGWOnDeviceServiceConfigurationTypeDef",
     {
         "StorageLimit": int,
         "StorageUnit": Literal["TB"],
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
 TargetOnDeviceServiceTypeDef = TypedDict(
     "TargetOnDeviceServiceTypeDef",
     {
         "ServiceName": DeviceServiceNameType,
         "TransferOption": TransferOptionType,
     },
     total=False,
@@ -554,197 +701,81 @@
 CreateAddressRequestRequestTypeDef = TypedDict(
     "CreateAddressRequestRequestTypeDef",
     {
         "Address": AddressTypeDef,
     },
 )
 
-CreateAddressResultTypeDef = TypedDict(
-    "CreateAddressResultTypeDef",
-    {
-        "AddressId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateClusterResultTypeDef = TypedDict(
-    "CreateClusterResultTypeDef",
-    {
-        "ClusterId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateJobResultTypeDef = TypedDict(
-    "CreateJobResultTypeDef",
-    {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateLongTermPricingResultTypeDef = TypedDict(
-    "CreateLongTermPricingResultTypeDef",
-    {
-        "LongTermPricingId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateReturnShippingLabelResultTypeDef = TypedDict(
-    "CreateReturnShippingLabelResultTypeDef",
-    {
-        "Status": ShippingLabelStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 DescribeAddressResultTypeDef = TypedDict(
     "DescribeAddressResultTypeDef",
     {
         "Address": AddressTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeAddressesResultTypeDef = TypedDict(
     "DescribeAddressesResultTypeDef",
     {
         "Addresses": List[AddressTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeReturnShippingLabelResultTypeDef = TypedDict(
-    "DescribeReturnShippingLabelResultTypeDef",
-    {
-        "Status": ShippingLabelStatusType,
-        "ExpirationDate": datetime,
-        "ReturnShippingLabelURI": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetJobManifestResultTypeDef = TypedDict(
-    "GetJobManifestResultTypeDef",
-    {
-        "ManifestURI": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetJobUnlockCodeResultTypeDef = TypedDict(
-    "GetJobUnlockCodeResultTypeDef",
-    {
-        "UnlockCode": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSnowballUsageResultTypeDef = TypedDict(
-    "GetSnowballUsageResultTypeDef",
-    {
-        "SnowballLimit": int,
-        "SnowballsInUse": int,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSoftwareUpdatesResultTypeDef = TypedDict(
-    "GetSoftwareUpdatesResultTypeDef",
-    {
-        "UpdatesURI": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListClustersResultTypeDef = TypedDict(
     "ListClustersResultTypeDef",
     {
         "ClusterListEntries": List[ClusterListEntryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListCompatibleImagesResultTypeDef = TypedDict(
     "ListCompatibleImagesResultTypeDef",
     {
         "CompatibleImages": List[CompatibleImageTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-DependentServiceTypeDef = TypedDict(
-    "DependentServiceTypeDef",
-    {
-        "ServiceName": ServiceNameType,
-        "ServiceVersion": ServiceVersionTypeDef,
-    },
-    total=False,
-)
-
-DescribeAddressesRequestDescribeAddressesPaginateTypeDef = TypedDict(
-    "DescribeAddressesRequestDescribeAddressesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListClusterJobsRequestListClusterJobsPaginateTypeDef = TypedDict(
-    "_RequiredListClusterJobsRequestListClusterJobsPaginateTypeDef",
+CreateClusterResultTypeDef = TypedDict(
+    "CreateClusterResultTypeDef",
     {
         "ClusterId": str,
+        "JobListEntries": List[JobListEntryTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalListClusterJobsRequestListClusterJobsPaginateTypeDef = TypedDict(
-    "_OptionalListClusterJobsRequestListClusterJobsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListClusterJobsRequestListClusterJobsPaginateTypeDef(
-    _RequiredListClusterJobsRequestListClusterJobsPaginateTypeDef,
-    _OptionalListClusterJobsRequestListClusterJobsPaginateTypeDef,
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
 
-ListCompatibleImagesRequestListCompatibleImagesPaginateTypeDef = TypedDict(
-    "ListCompatibleImagesRequestListCompatibleImagesPaginateTypeDef",
+ListClusterJobsResultTypeDef = TypedDict(
+    "ListClusterJobsResultTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "JobListEntries": List[JobListEntryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-ListJobsRequestListJobsPaginateTypeDef = TypedDict(
-    "ListJobsRequestListJobsPaginateTypeDef",
+ListJobsResultTypeDef = TypedDict(
+    "ListJobsResultTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "JobListEntries": List[JobListEntryTypeDef],
+        "NextToken": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-ListLongTermPricingRequestListLongTermPricingPaginateTypeDef = TypedDict(
-    "ListLongTermPricingRequestListLongTermPricingPaginateTypeDef",
+DependentServiceTypeDef = TypedDict(
+    "DependentServiceTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ServiceName": ServiceNameType,
+        "ServiceVersion": ServiceVersionTypeDef,
     },
     total=False,
 )
 
 LambdaResourceTypeDef = TypedDict(
     "LambdaResourceTypeDef",
     {
@@ -758,47 +789,30 @@
     "TaxDocumentsTypeDef",
     {
         "IND": INDTaxDocumentsTypeDef,
     },
     total=False,
 )
 
-ListClusterJobsResultTypeDef = TypedDict(
-    "ListClusterJobsResultTypeDef",
-    {
-        "JobListEntries": List[JobListEntryTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListJobsResultTypeDef = TypedDict(
-    "ListJobsResultTypeDef",
-    {
-        "JobListEntries": List[JobListEntryTypeDef],
-        "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ListLongTermPricingResultTypeDef = TypedDict(
     "ListLongTermPricingResultTypeDef",
     {
         "LongTermPricingEntries": List[LongTermPricingListEntryTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 OnDeviceServiceConfigurationTypeDef = TypedDict(
     "OnDeviceServiceConfigurationTypeDef",
     {
         "NFSOnDeviceService": NFSOnDeviceServiceConfigurationTypeDef,
         "TGWOnDeviceService": TGWOnDeviceServiceConfigurationTypeDef,
         "EKSOnDeviceService": EKSOnDeviceServiceConfigurationTypeDef,
+        "S3OnDeviceService": S3OnDeviceServiceConfigurationTypeDef,
     },
     total=False,
 )
 
 S3ResourceTypeDef = TypedDict(
     "S3ResourceTypeDef",
     {
@@ -852,15 +866,15 @@
 ListServiceVersionsResultTypeDef = TypedDict(
     "ListServiceVersionsResultTypeDef",
     {
         "ServiceVersions": List[ServiceVersionTypeDef],
         "ServiceName": ServiceNameType,
         "DependentServices": List[DependentServiceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 JobResourceTypeDef = TypedDict(
     "JobResourceTypeDef",
     {
         "S3Resources": Sequence[S3ResourceTypeDef],
@@ -900,31 +914,35 @@
     total=False,
 )
 
 _RequiredCreateClusterRequestRequestTypeDef = TypedDict(
     "_RequiredCreateClusterRequestRequestTypeDef",
     {
         "JobType": JobTypeType,
-        "Resources": JobResourceTypeDef,
         "AddressId": str,
-        "RoleARN": str,
         "SnowballType": SnowballTypeType,
         "ShippingOption": ShippingOptionType,
     },
 )
 _OptionalCreateClusterRequestRequestTypeDef = TypedDict(
     "_OptionalCreateClusterRequestRequestTypeDef",
     {
+        "Resources": JobResourceTypeDef,
         "OnDeviceServiceConfiguration": OnDeviceServiceConfigurationTypeDef,
         "Description": str,
         "KmsKeyARN": str,
+        "RoleARN": str,
         "Notification": NotificationTypeDef,
         "ForwardingAddressId": str,
         "TaxDocuments": TaxDocumentsTypeDef,
         "RemoteManagement": RemoteManagementType,
+        "InitialClusterSize": int,
+        "ForceCreateJobs": bool,
+        "LongTermPricingIds": Sequence[str],
+        "SnowballCapacityPreference": SnowballCapacityType,
     },
     total=False,
 )
 
 class CreateClusterRequestRequestTypeDef(
     _RequiredCreateClusterRequestRequestTypeDef, _OptionalCreateClusterRequestRequestTypeDef
 ):
@@ -1036,19 +1054,19 @@
     total=False,
 )
 
 DescribeClusterResultTypeDef = TypedDict(
     "DescribeClusterResultTypeDef",
     {
         "ClusterMetadata": ClusterMetadataTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeJobResultTypeDef = TypedDict(
     "DescribeJobResultTypeDef",
     {
         "JobMetadata": JobMetadataTypeDef,
         "SubJobMetadata": List[JobMetadataTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-snowball-2.5.0.post1/types_aiobotocore_snowball.egg-info/PKG-INFO` & `types-aiobotocore-snowball-2.5.1/types_aiobotocore_snowball.egg-info/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-snowball
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Snowball 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Snowball 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-snowball"></a>
 
 # types-aiobotocore-snowball
 
 [![PyPI - types-aiobotocore-snowball](https://img.shields.io/pypi/v/types-aiobotocore-snowball.svg?color=blue)](https://pypi.org/project/types-aiobotocore-snowball)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-snowball.svg?color=blue)](https://pypi.org/project/types-aiobotocore-snowball)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-snowball?color=blue)](https://pypistats.org/packages/types-aiobotocore-snowball)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Snowball 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snowball.html#Snowball)
+[aiobotocore.Snowball 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snowball.html#Snowball)
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
 [types-aiobotocore-snowball docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snowball/).
 
 See how it helps to find and fix potential bugs:
 
@@ -358,74 +358,75 @@
 from types_aiobotocore_snowball.type_defs import (
     AddressTypeDef,
     CancelClusterRequestRequestTypeDef,
     CancelJobRequestRequestTypeDef,
     ClusterListEntryTypeDef,
     NotificationTypeDef,
     CompatibleImageTypeDef,
-    ResponseMetadataTypeDef,
+    CreateAddressResultTypeDef,
+    JobListEntryTypeDef,
+    CreateJobResultTypeDef,
     CreateLongTermPricingRequestRequestTypeDef,
+    CreateLongTermPricingResultTypeDef,
     CreateReturnShippingLabelRequestRequestTypeDef,
+    CreateReturnShippingLabelResultTypeDef,
     DataTransferTypeDef,
     ServiceVersionTypeDef,
     DescribeAddressRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    DescribeAddressesRequestDescribeAddressesPaginateTypeDef,
     DescribeAddressesRequestRequestTypeDef,
     DescribeClusterRequestRequestTypeDef,
     DescribeJobRequestRequestTypeDef,
     DescribeReturnShippingLabelRequestRequestTypeDef,
+    DescribeReturnShippingLabelResultTypeDef,
     EKSOnDeviceServiceConfigurationTypeDef,
     Ec2AmiResourceTypeDef,
     EventTriggerDefinitionTypeDef,
     GetJobManifestRequestRequestTypeDef,
+    GetJobManifestResultTypeDef,
     GetJobUnlockCodeRequestRequestTypeDef,
+    GetJobUnlockCodeResultTypeDef,
+    GetSnowballUsageResultTypeDef,
     GetSoftwareUpdatesRequestRequestTypeDef,
+    GetSoftwareUpdatesResultTypeDef,
     INDTaxDocumentsTypeDef,
-    JobListEntryTypeDef,
     JobLogsTypeDef,
     KeyRangeTypeDef,
+    ListClusterJobsRequestListClusterJobsPaginateTypeDef,
     ListClusterJobsRequestRequestTypeDef,
+    ListClustersRequestListClustersPaginateTypeDef,
     ListClustersRequestRequestTypeDef,
+    ListCompatibleImagesRequestListCompatibleImagesPaginateTypeDef,
     ListCompatibleImagesRequestRequestTypeDef,
+    ListJobsRequestListJobsPaginateTypeDef,
     ListJobsRequestRequestTypeDef,
+    ListLongTermPricingRequestListLongTermPricingPaginateTypeDef,
     ListLongTermPricingRequestRequestTypeDef,
     LongTermPricingListEntryTypeDef,
     NFSOnDeviceServiceConfigurationTypeDef,
+    S3OnDeviceServiceConfigurationTypeDef,
     TGWOnDeviceServiceConfigurationTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     TargetOnDeviceServiceTypeDef,
     ShipmentTypeDef,
     WirelessConnectionTypeDef,
     UpdateJobShipmentStateRequestRequestTypeDef,
     UpdateLongTermPricingRequestRequestTypeDef,
     CreateAddressRequestRequestTypeDef,
-    CreateAddressResultTypeDef,
-    CreateClusterResultTypeDef,
-    CreateJobResultTypeDef,
-    CreateLongTermPricingResultTypeDef,
-    CreateReturnShippingLabelResultTypeDef,
     DescribeAddressResultTypeDef,
     DescribeAddressesResultTypeDef,
-    DescribeReturnShippingLabelResultTypeDef,
-    GetJobManifestResultTypeDef,
-    GetJobUnlockCodeResultTypeDef,
-    GetSnowballUsageResultTypeDef,
-    GetSoftwareUpdatesResultTypeDef,
     ListClustersResultTypeDef,
     ListCompatibleImagesResultTypeDef,
+    CreateClusterResultTypeDef,
+    ListClusterJobsResultTypeDef,
+    ListJobsResultTypeDef,
     DependentServiceTypeDef,
-    DescribeAddressesRequestDescribeAddressesPaginateTypeDef,
-    ListClusterJobsRequestListClusterJobsPaginateTypeDef,
-    ListClustersRequestListClustersPaginateTypeDef,
-    ListCompatibleImagesRequestListCompatibleImagesPaginateTypeDef,
-    ListJobsRequestListJobsPaginateTypeDef,
-    ListLongTermPricingRequestListLongTermPricingPaginateTypeDef,
     LambdaResourceTypeDef,
     TaxDocumentsTypeDef,
-    ListClusterJobsResultTypeDef,
-    ListJobsResultTypeDef,
     ListLongTermPricingResultTypeDef,
     OnDeviceServiceConfigurationTypeDef,
     S3ResourceTypeDef,
     ShippingDetailsTypeDef,
     SnowconeDeviceConfigurationTypeDef,
     ListServiceVersionsRequestRequestTypeDef,
     ListServiceVersionsResultTypeDef,
@@ -449,43 +450,43 @@
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

### Comparing `types-aiobotocore-snowball-2.5.0.post1/types_aiobotocore_snowball.egg-info/SOURCES.txt` & `types-aiobotocore-snowball-2.5.1/types_aiobotocore_snowball.egg-info/SOURCES.txt`

 * *Files identical despite different names*

