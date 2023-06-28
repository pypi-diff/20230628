# Comparing `tmp/types-aiobotocore-panorama-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-panorama-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-panorama-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:06 2023, max compression
+gzip compressed data, was "types-aiobotocore-panorama-2.5.1.tar", last modified: Wed Jun 28 01:43:56 2023, max compression
```

## Comparing `types-aiobotocore-panorama-2.5.0.post1.tar` & `types-aiobotocore-panorama-2.5.1.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:06.087489 types-aiobotocore-panorama-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:19:38.000000 types-aiobotocore-panorama-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    16649 2023-03-11 12:27:06.087489 types-aiobotocore-panorama-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    15074 2023-03-11 12:19:38.000000 types-aiobotocore-panorama-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:06.087489 types-aiobotocore-panorama-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2131 2023-03-11 12:19:38.000000 types-aiobotocore-panorama-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:06.083488 types-aiobotocore-panorama-2.5.0.post1/types_aiobotocore_panorama/
--rw-r--r--   0 runner    (1001) docker     (123)      450 2023-03-11 12:19:38.000000 types-aiobotocore-panorama-2.5.0.post1/types_aiobotocore_panorama/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      449 2023-03-11 12:19:38.000000 types-aiobotocore-panorama-2.5.0.post1/types_aiobotocore_panorama/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      947 2023-03-11 12:19:38.000000 types-aiobotocore-panorama-2.5.0.post1/types_aiobotocore_panorama/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    25607 2023-03-11 12:19:38.000000 types-aiobotocore-panorama-2.5.0.post1/types_aiobotocore_panorama/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    25564 2023-03-11 12:19:38.000000 types-aiobotocore-panorama-2.5.0.post1/types_aiobotocore_panorama/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)    10757 2023-03-11 12:19:38.000000 types-aiobotocore-panorama-2.5.0.post1/types_aiobotocore_panorama/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)    10755 2023-03-11 12:19:38.000000 types-aiobotocore-panorama-2.5.0.post1/types_aiobotocore_panorama/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:19:38.000000 types-aiobotocore-panorama-2.5.0.post1/types_aiobotocore_panorama/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    37318 2023-03-11 12:19:39.000000 types-aiobotocore-panorama-2.5.0.post1/types_aiobotocore_panorama/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    37277 2023-03-11 12:19:39.000000 types-aiobotocore-panorama-2.5.0.post1/types_aiobotocore_panorama/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:19:38.000000 types-aiobotocore-panorama-2.5.0.post1/types_aiobotocore_panorama/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:06.087489 types-aiobotocore-panorama-2.5.0.post1/types_aiobotocore_panorama.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    16649 2023-03-11 12:27:05.000000 types-aiobotocore-panorama-2.5.0.post1/types_aiobotocore_panorama.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      751 2023-03-11 12:27:05.000000 types-aiobotocore-panorama-2.5.0.post1/types_aiobotocore_panorama.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:05.000000 types-aiobotocore-panorama-2.5.0.post1/types_aiobotocore_panorama.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:05.000000 types-aiobotocore-panorama-2.5.0.post1/types_aiobotocore_panorama.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:05.000000 types-aiobotocore-panorama-2.5.0.post1/types_aiobotocore_panorama.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       27 2023-03-11 12:27:05.000000 types-aiobotocore-panorama-2.5.0.post1/types_aiobotocore_panorama.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:56.734188 types-aiobotocore-panorama-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:36:23.000000 types-aiobotocore-panorama-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    16642 2023-06-28 01:43:56.734188 types-aiobotocore-panorama-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    15073 2023-06-28 01:36:23.000000 types-aiobotocore-panorama-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:56.734188 types-aiobotocore-panorama-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2125 2023-06-28 01:36:23.000000 types-aiobotocore-panorama-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:56.734188 types-aiobotocore-panorama-2.5.1/types_aiobotocore_panorama/
+-rw-r--r--   0 runner    (1001) docker     (123)      450 2023-06-28 01:36:23.000000 types-aiobotocore-panorama-2.5.1/types_aiobotocore_panorama/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      449 2023-06-28 01:36:23.000000 types-aiobotocore-panorama-2.5.1/types_aiobotocore_panorama/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      935 2023-06-28 01:36:23.000000 types-aiobotocore-panorama-2.5.1/types_aiobotocore_panorama/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25607 2023-06-28 01:36:23.000000 types-aiobotocore-panorama-2.5.1/types_aiobotocore_panorama/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25564 2023-06-28 01:36:23.000000 types-aiobotocore-panorama-2.5.1/types_aiobotocore_panorama/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)    10966 2023-06-28 01:36:23.000000 types-aiobotocore-panorama-2.5.1/types_aiobotocore_panorama/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10964 2023-06-28 01:36:23.000000 types-aiobotocore-panorama-2.5.1/types_aiobotocore_panorama/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:36:23.000000 types-aiobotocore-panorama-2.5.1/types_aiobotocore_panorama/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    37374 2023-06-28 01:36:24.000000 types-aiobotocore-panorama-2.5.1/types_aiobotocore_panorama/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    37333 2023-06-28 01:36:24.000000 types-aiobotocore-panorama-2.5.1/types_aiobotocore_panorama/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:36:23.000000 types-aiobotocore-panorama-2.5.1/types_aiobotocore_panorama/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:56.734188 types-aiobotocore-panorama-2.5.1/types_aiobotocore_panorama.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    16642 2023-06-28 01:43:56.000000 types-aiobotocore-panorama-2.5.1/types_aiobotocore_panorama.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      751 2023-06-28 01:43:56.000000 types-aiobotocore-panorama-2.5.1/types_aiobotocore_panorama.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:56.000000 types-aiobotocore-panorama-2.5.1/types_aiobotocore_panorama.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:56.000000 types-aiobotocore-panorama-2.5.1/types_aiobotocore_panorama.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:56.000000 types-aiobotocore-panorama-2.5.1/types_aiobotocore_panorama.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       27 2023-06-28 01:43:56.000000 types-aiobotocore-panorama-2.5.1/types_aiobotocore_panorama.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-panorama-2.5.0.post1/LICENSE` & `types-aiobotocore-panorama-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-panorama-2.5.0.post1/PKG-INFO` & `types-aiobotocore-panorama-2.5.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-panorama
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Panorama 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Panorama 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_panorama/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-panorama"></a>
 
 # types-aiobotocore-panorama
 
 [![PyPI - types-aiobotocore-panorama](https://img.shields.io/pypi/v/types-aiobotocore-panorama.svg?color=blue)](https://pypi.org/project/types-aiobotocore-panorama)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-panorama.svg?color=blue)](https://pypi.org/project/types-aiobotocore-panorama)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_panorama/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-panorama?color=blue)](https://pypistats.org/packages/types-aiobotocore-panorama)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Panorama 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/panorama.html#Panorama)
+[aiobotocore.Panorama 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/panorama.html#Panorama)
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
 [types-aiobotocore-panorama docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_panorama/).
 
 See how it helps to find and fix potential bugs:
 
@@ -317,32 +317,37 @@
 
 ```python
 from types_aiobotocore_panorama.type_defs import (
     AlternateSoftwareMetadataTypeDef,
     ReportedRuntimeContextStateTypeDef,
     ManifestOverridesPayloadTypeDef,
     ManifestPayloadTypeDef,
-    ResponseMetadataTypeDef,
+    CreateApplicationInstanceResponseTypeDef,
     JobTypeDef,
     JobResourceTagsTypeDef,
+    CreateNodeFromTemplateJobResponseTypeDef,
+    CreatePackageImportJobResponseTypeDef,
     CreatePackageRequestRequestTypeDef,
     StorageLocationTypeDef,
     DeleteDeviceRequestRequestTypeDef,
+    DeleteDeviceResponseTypeDef,
     DeletePackageRequestRequestTypeDef,
     DeregisterPackageVersionRequestRequestTypeDef,
     DescribeApplicationInstanceDetailsRequestRequestTypeDef,
     DescribeApplicationInstanceRequestRequestTypeDef,
     DescribeDeviceJobRequestRequestTypeDef,
+    DescribeDeviceJobResponseTypeDef,
     DescribeDeviceRequestRequestTypeDef,
     LatestDeviceJobTypeDef,
     DescribeNodeFromTemplateJobRequestRequestTypeDef,
     DescribeNodeRequestRequestTypeDef,
     DescribePackageImportJobRequestRequestTypeDef,
     DescribePackageRequestRequestTypeDef,
     DescribePackageVersionRequestRequestTypeDef,
+    DescribePackageVersionResponseTypeDef,
     OTAJobConfigTypeDef,
     DeviceJobTypeDef,
     StaticIpConnectionInfoTypeDef,
     EthernetStatusTypeDef,
     ListApplicationInstanceDependenciesRequestRequestTypeDef,
     PackageObjectTypeDef,
     ListApplicationInstanceNodeInstancesRequestRequestTypeDef,
@@ -355,41 +360,36 @@
     ListNodesRequestRequestTypeDef,
     NodeTypeDef,
     ListPackageImportJobsRequestRequestTypeDef,
     PackageImportJobTypeDef,
     ListPackagesRequestRequestTypeDef,
     PackageListItemTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     NtpPayloadTypeDef,
     NtpStatusTypeDef,
     NodeInputPortTypeDef,
     NodeOutputPortTypeDef,
     NodeSignalTypeDef,
     OutPutS3LocationTypeDef,
     PackageVersionOutputConfigTypeDef,
     S3LocationTypeDef,
+    ProvisionDeviceResponseTypeDef,
     RegisterPackageVersionRequestRequestTypeDef,
     RemoveApplicationInstanceRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
+    SignalApplicationInstanceNodeInstancesResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateDeviceMetadataRequestRequestTypeDef,
+    UpdateDeviceMetadataResponseTypeDef,
     ApplicationInstanceTypeDef,
+    DescribeApplicationInstanceResponseTypeDef,
     CreateApplicationInstanceRequestRequestTypeDef,
-    CreateApplicationInstanceResponseTypeDef,
-    CreateNodeFromTemplateJobResponseTypeDef,
-    CreatePackageImportJobResponseTypeDef,
-    DeleteDeviceResponseTypeDef,
     DescribeApplicationInstanceDetailsResponseTypeDef,
-    DescribeApplicationInstanceResponseTypeDef,
-    DescribeDeviceJobResponseTypeDef,
-    DescribePackageVersionResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    ProvisionDeviceResponseTypeDef,
-    SignalApplicationInstanceNodeInstancesResponseTypeDef,
-    UpdateDeviceMetadataResponseTypeDef,
     CreateJobForDevicesResponseTypeDef,
     CreateNodeFromTemplateJobRequestRequestTypeDef,
     DescribeNodeFromTemplateJobResponseTypeDef,
     CreatePackageResponseTypeDef,
     DescribePackageResponseTypeDef,
     DeviceTypeDef,
     DeviceJobConfigTypeDef,
@@ -427,43 +427,43 @@
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

### Comparing `types-aiobotocore-panorama-2.5.0.post1/README.md` & `types-aiobotocore-panorama-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-panorama"></a>
 
 # types-aiobotocore-panorama
 
 [![PyPI - types-aiobotocore-panorama](https://img.shields.io/pypi/v/types-aiobotocore-panorama.svg?color=blue)](https://pypi.org/project/types-aiobotocore-panorama)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-panorama.svg?color=blue)](https://pypi.org/project/types-aiobotocore-panorama)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_panorama/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-panorama?color=blue)](https://pypistats.org/packages/types-aiobotocore-panorama)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Panorama 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/panorama.html#Panorama)
+[aiobotocore.Panorama 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/panorama.html#Panorama)
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
 [types-aiobotocore-panorama docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_panorama/).
 
 See how it helps to find and fix potential bugs:
 
@@ -284,32 +284,37 @@
 
 ```python
 from types_aiobotocore_panorama.type_defs import (
     AlternateSoftwareMetadataTypeDef,
     ReportedRuntimeContextStateTypeDef,
     ManifestOverridesPayloadTypeDef,
     ManifestPayloadTypeDef,
-    ResponseMetadataTypeDef,
+    CreateApplicationInstanceResponseTypeDef,
     JobTypeDef,
     JobResourceTagsTypeDef,
+    CreateNodeFromTemplateJobResponseTypeDef,
+    CreatePackageImportJobResponseTypeDef,
     CreatePackageRequestRequestTypeDef,
     StorageLocationTypeDef,
     DeleteDeviceRequestRequestTypeDef,
+    DeleteDeviceResponseTypeDef,
     DeletePackageRequestRequestTypeDef,
     DeregisterPackageVersionRequestRequestTypeDef,
     DescribeApplicationInstanceDetailsRequestRequestTypeDef,
     DescribeApplicationInstanceRequestRequestTypeDef,
     DescribeDeviceJobRequestRequestTypeDef,
+    DescribeDeviceJobResponseTypeDef,
     DescribeDeviceRequestRequestTypeDef,
     LatestDeviceJobTypeDef,
     DescribeNodeFromTemplateJobRequestRequestTypeDef,
     DescribeNodeRequestRequestTypeDef,
     DescribePackageImportJobRequestRequestTypeDef,
     DescribePackageRequestRequestTypeDef,
     DescribePackageVersionRequestRequestTypeDef,
+    DescribePackageVersionResponseTypeDef,
     OTAJobConfigTypeDef,
     DeviceJobTypeDef,
     StaticIpConnectionInfoTypeDef,
     EthernetStatusTypeDef,
     ListApplicationInstanceDependenciesRequestRequestTypeDef,
     PackageObjectTypeDef,
     ListApplicationInstanceNodeInstancesRequestRequestTypeDef,
@@ -322,41 +327,36 @@
     ListNodesRequestRequestTypeDef,
     NodeTypeDef,
     ListPackageImportJobsRequestRequestTypeDef,
     PackageImportJobTypeDef,
     ListPackagesRequestRequestTypeDef,
     PackageListItemTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     NtpPayloadTypeDef,
     NtpStatusTypeDef,
     NodeInputPortTypeDef,
     NodeOutputPortTypeDef,
     NodeSignalTypeDef,
     OutPutS3LocationTypeDef,
     PackageVersionOutputConfigTypeDef,
     S3LocationTypeDef,
+    ProvisionDeviceResponseTypeDef,
     RegisterPackageVersionRequestRequestTypeDef,
     RemoveApplicationInstanceRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
+    SignalApplicationInstanceNodeInstancesResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateDeviceMetadataRequestRequestTypeDef,
+    UpdateDeviceMetadataResponseTypeDef,
     ApplicationInstanceTypeDef,
+    DescribeApplicationInstanceResponseTypeDef,
     CreateApplicationInstanceRequestRequestTypeDef,
-    CreateApplicationInstanceResponseTypeDef,
-    CreateNodeFromTemplateJobResponseTypeDef,
-    CreatePackageImportJobResponseTypeDef,
-    DeleteDeviceResponseTypeDef,
     DescribeApplicationInstanceDetailsResponseTypeDef,
-    DescribeApplicationInstanceResponseTypeDef,
-    DescribeDeviceJobResponseTypeDef,
-    DescribePackageVersionResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    ProvisionDeviceResponseTypeDef,
-    SignalApplicationInstanceNodeInstancesResponseTypeDef,
-    UpdateDeviceMetadataResponseTypeDef,
     CreateJobForDevicesResponseTypeDef,
     CreateNodeFromTemplateJobRequestRequestTypeDef,
     DescribeNodeFromTemplateJobResponseTypeDef,
     CreatePackageResponseTypeDef,
     DescribePackageResponseTypeDef,
     DeviceTypeDef,
     DeviceJobConfigTypeDef,
@@ -394,43 +394,43 @@
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

### Comparing `types-aiobotocore-panorama-2.5.0.post1/setup.py` & `types-aiobotocore-panorama-2.5.1/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-panorama.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-panorama",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_panorama"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Panorama 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.Panorama 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_panorama/"
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

### Comparing `types-aiobotocore-panorama-2.5.0.post1/types_aiobotocore_panorama/__main__.py` & `types-aiobotocore-panorama-2.5.1/types_aiobotocore_panorama/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Panorama 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Panorama 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_panorama//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/panorama.html#Panorama\nOther"
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

### Comparing `types-aiobotocore-panorama-2.5.0.post1/types_aiobotocore_panorama/client.py` & `types-aiobotocore-panorama-2.5.1/types_aiobotocore_panorama/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-panorama-2.5.0.post1/types_aiobotocore_panorama/client.pyi` & `types-aiobotocore-panorama-2.5.1/types_aiobotocore_panorama/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-panorama-2.5.0.post1/types_aiobotocore_panorama/literals.py` & `types-aiobotocore-panorama-2.5.1/types_aiobotocore_panorama/literals.py`

 * *Files 2% similar despite different names*

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

### Comparing `types-aiobotocore-panorama-2.5.0.post1/types_aiobotocore_panorama/literals.pyi` & `types-aiobotocore-panorama-2.5.1/types_aiobotocore_panorama/literals.pyi`

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

### Comparing `types-aiobotocore-panorama-2.5.0.post1/types_aiobotocore_panorama/type_defs.py` & `types-aiobotocore-panorama-2.5.1/types_aiobotocore_panorama/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -53,32 +53,37 @@
 
 
 __all__ = (
     "AlternateSoftwareMetadataTypeDef",
     "ReportedRuntimeContextStateTypeDef",
     "ManifestOverridesPayloadTypeDef",
     "ManifestPayloadTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateApplicationInstanceResponseTypeDef",
     "JobTypeDef",
     "JobResourceTagsTypeDef",
+    "CreateNodeFromTemplateJobResponseTypeDef",
+    "CreatePackageImportJobResponseTypeDef",
     "CreatePackageRequestRequestTypeDef",
     "StorageLocationTypeDef",
     "DeleteDeviceRequestRequestTypeDef",
+    "DeleteDeviceResponseTypeDef",
     "DeletePackageRequestRequestTypeDef",
     "DeregisterPackageVersionRequestRequestTypeDef",
     "DescribeApplicationInstanceDetailsRequestRequestTypeDef",
     "DescribeApplicationInstanceRequestRequestTypeDef",
     "DescribeDeviceJobRequestRequestTypeDef",
+    "DescribeDeviceJobResponseTypeDef",
     "DescribeDeviceRequestRequestTypeDef",
     "LatestDeviceJobTypeDef",
     "DescribeNodeFromTemplateJobRequestRequestTypeDef",
     "DescribeNodeRequestRequestTypeDef",
     "DescribePackageImportJobRequestRequestTypeDef",
     "DescribePackageRequestRequestTypeDef",
     "DescribePackageVersionRequestRequestTypeDef",
+    "DescribePackageVersionResponseTypeDef",
     "OTAJobConfigTypeDef",
     "DeviceJobTypeDef",
     "StaticIpConnectionInfoTypeDef",
     "EthernetStatusTypeDef",
     "ListApplicationInstanceDependenciesRequestRequestTypeDef",
     "PackageObjectTypeDef",
     "ListApplicationInstanceNodeInstancesRequestRequestTypeDef",
@@ -91,41 +96,36 @@
     "ListNodesRequestRequestTypeDef",
     "NodeTypeDef",
     "ListPackageImportJobsRequestRequestTypeDef",
     "PackageImportJobTypeDef",
     "ListPackagesRequestRequestTypeDef",
     "PackageListItemTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "NtpPayloadTypeDef",
     "NtpStatusTypeDef",
     "NodeInputPortTypeDef",
     "NodeOutputPortTypeDef",
     "NodeSignalTypeDef",
     "OutPutS3LocationTypeDef",
     "PackageVersionOutputConfigTypeDef",
     "S3LocationTypeDef",
+    "ProvisionDeviceResponseTypeDef",
     "RegisterPackageVersionRequestRequestTypeDef",
     "RemoveApplicationInstanceRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
+    "SignalApplicationInstanceNodeInstancesResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateDeviceMetadataRequestRequestTypeDef",
+    "UpdateDeviceMetadataResponseTypeDef",
     "ApplicationInstanceTypeDef",
+    "DescribeApplicationInstanceResponseTypeDef",
     "CreateApplicationInstanceRequestRequestTypeDef",
-    "CreateApplicationInstanceResponseTypeDef",
-    "CreateNodeFromTemplateJobResponseTypeDef",
-    "CreatePackageImportJobResponseTypeDef",
-    "DeleteDeviceResponseTypeDef",
     "DescribeApplicationInstanceDetailsResponseTypeDef",
-    "DescribeApplicationInstanceResponseTypeDef",
-    "DescribeDeviceJobResponseTypeDef",
-    "DescribePackageVersionResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "ProvisionDeviceResponseTypeDef",
-    "SignalApplicationInstanceNodeInstancesResponseTypeDef",
-    "UpdateDeviceMetadataResponseTypeDef",
     "CreateJobForDevicesResponseTypeDef",
     "CreateNodeFromTemplateJobRequestRequestTypeDef",
     "DescribeNodeFromTemplateJobResponseTypeDef",
     "CreatePackageResponseTypeDef",
     "DescribePackageResponseTypeDef",
     "DeviceTypeDef",
     "DeviceJobConfigTypeDef",
@@ -185,22 +185,19 @@
     "ManifestPayloadTypeDef",
     {
         "PayloadData": str,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateApplicationInstanceResponseTypeDef = TypedDict(
+    "CreateApplicationInstanceResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ApplicationInstanceId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 JobTypeDef = TypedDict(
     "JobTypeDef",
     {
         "DeviceId": str,
@@ -213,14 +210,30 @@
     "JobResourceTagsTypeDef",
     {
         "ResourceType": Literal["PACKAGE"],
         "Tags": Mapping[str, str],
     },
 )
 
+CreateNodeFromTemplateJobResponseTypeDef = TypedDict(
+    "CreateNodeFromTemplateJobResponseTypeDef",
+    {
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreatePackageImportJobResponseTypeDef = TypedDict(
+    "CreatePackageImportJobResponseTypeDef",
+    {
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreatePackageRequestRequestTypeDef = TypedDict(
     "_RequiredCreatePackageRequestRequestTypeDef",
     {
         "PackageName": str,
     },
 )
 _OptionalCreatePackageRequestRequestTypeDef = TypedDict(
@@ -252,14 +265,22 @@
 DeleteDeviceRequestRequestTypeDef = TypedDict(
     "DeleteDeviceRequestRequestTypeDef",
     {
         "DeviceId": str,
     },
 )
 
+DeleteDeviceResponseTypeDef = TypedDict(
+    "DeleteDeviceResponseTypeDef",
+    {
+        "DeviceId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeletePackageRequestRequestTypeDef = TypedDict(
     "_RequiredDeletePackageRequestRequestTypeDef",
     {
         "PackageId": str,
     },
 )
 _OptionalDeletePackageRequestRequestTypeDef = TypedDict(
@@ -319,14 +340,30 @@
 DescribeDeviceJobRequestRequestTypeDef = TypedDict(
     "DescribeDeviceJobRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 
+DescribeDeviceJobResponseTypeDef = TypedDict(
+    "DescribeDeviceJobResponseTypeDef",
+    {
+        "CreatedTime": datetime,
+        "DeviceArn": str,
+        "DeviceId": str,
+        "DeviceName": str,
+        "DeviceType": DeviceTypeType,
+        "ImageVersion": str,
+        "JobId": str,
+        "JobType": JobTypeType,
+        "Status": UpdateProgressType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeDeviceRequestRequestTypeDef = TypedDict(
     "DescribeDeviceRequestRequestTypeDef",
     {
         "DeviceId": str,
     },
 )
 
@@ -402,14 +439,31 @@
 class DescribePackageVersionRequestRequestTypeDef(
     _RequiredDescribePackageVersionRequestRequestTypeDef,
     _OptionalDescribePackageVersionRequestRequestTypeDef,
 ):
     pass
 
 
+DescribePackageVersionResponseTypeDef = TypedDict(
+    "DescribePackageVersionResponseTypeDef",
+    {
+        "IsLatestPatch": bool,
+        "OwnerAccount": str,
+        "PackageArn": str,
+        "PackageId": str,
+        "PackageName": str,
+        "PackageVersion": str,
+        "PatchVersion": str,
+        "RegisteredTime": datetime,
+        "Status": PackageVersionStatusType,
+        "StatusDescription": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredOTAJobConfigTypeDef = TypedDict(
     "_RequiredOTAJobConfigTypeDef",
     {
         "ImageVersion": str,
     },
 )
 _OptionalOTAJobConfigTypeDef = TypedDict(
@@ -680,14 +734,22 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 NtpPayloadTypeDef = TypedDict(
     "NtpPayloadTypeDef",
     {
         "NtpServers": List[str],
     },
 )
 
@@ -777,14 +839,26 @@
 )
 
 
 class S3LocationTypeDef(_RequiredS3LocationTypeDef, _OptionalS3LocationTypeDef):
     pass
 
 
+ProvisionDeviceResponseTypeDef = TypedDict(
+    "ProvisionDeviceResponseTypeDef",
+    {
+        "Arn": str,
+        "Certificates": bytes,
+        "DeviceId": str,
+        "IotThingName": str,
+        "Status": DeviceStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredRegisterPackageVersionRequestRequestTypeDef = TypedDict(
     "_RequiredRegisterPackageVersionRequestRequestTypeDef",
     {
         "PackageId": str,
         "PackageVersion": str,
         "PatchVersion": str,
     },
@@ -809,14 +883,33 @@
 RemoveApplicationInstanceRequestRequestTypeDef = TypedDict(
     "RemoveApplicationInstanceRequestRequestTypeDef",
     {
         "ApplicationInstanceId": str,
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
+SignalApplicationInstanceNodeInstancesResponseTypeDef = TypedDict(
+    "SignalApplicationInstanceNodeInstancesResponseTypeDef",
+    {
+        "ApplicationInstanceId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "Tags": Mapping[str, str],
     },
 )
@@ -847,14 +940,22 @@
 class UpdateDeviceMetadataRequestRequestTypeDef(
     _RequiredUpdateDeviceMetadataRequestRequestTypeDef,
     _OptionalUpdateDeviceMetadataRequestRequestTypeDef,
 ):
     pass
 
 
+UpdateDeviceMetadataResponseTypeDef = TypedDict(
+    "UpdateDeviceMetadataResponseTypeDef",
+    {
+        "DeviceId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ApplicationInstanceTypeDef = TypedDict(
     "ApplicationInstanceTypeDef",
     {
         "ApplicationInstanceId": str,
         "Arn": str,
         "CreatedTime": datetime,
         "DefaultRuntimeContextDevice": str,
@@ -866,14 +967,36 @@
         "Status": ApplicationInstanceStatusType,
         "StatusDescription": str,
         "Tags": Dict[str, str],
     },
     total=False,
 )
 
+DescribeApplicationInstanceResponseTypeDef = TypedDict(
+    "DescribeApplicationInstanceResponseTypeDef",
+    {
+        "ApplicationInstanceId": str,
+        "ApplicationInstanceIdToReplace": str,
+        "Arn": str,
+        "CreatedTime": datetime,
+        "DefaultRuntimeContextDevice": str,
+        "DefaultRuntimeContextDeviceName": str,
+        "Description": str,
+        "HealthStatus": ApplicationInstanceHealthStatusType,
+        "LastUpdatedTime": datetime,
+        "Name": str,
+        "RuntimeContextStates": List[ReportedRuntimeContextStateTypeDef],
+        "RuntimeRoleArn": str,
+        "Status": ApplicationInstanceStatusType,
+        "StatusDescription": str,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateApplicationInstanceRequestRequestTypeDef = TypedDict(
     "_RequiredCreateApplicationInstanceRequestRequestTypeDef",
     {
         "DefaultRuntimeContextDevice": str,
         "ManifestPayload": ManifestPayloadTypeDef,
     },
 )
@@ -894,157 +1017,34 @@
 class CreateApplicationInstanceRequestRequestTypeDef(
     _RequiredCreateApplicationInstanceRequestRequestTypeDef,
     _OptionalCreateApplicationInstanceRequestRequestTypeDef,
 ):
     pass
 
 
-CreateApplicationInstanceResponseTypeDef = TypedDict(
-    "CreateApplicationInstanceResponseTypeDef",
-    {
-        "ApplicationInstanceId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateNodeFromTemplateJobResponseTypeDef = TypedDict(
-    "CreateNodeFromTemplateJobResponseTypeDef",
-    {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreatePackageImportJobResponseTypeDef = TypedDict(
-    "CreatePackageImportJobResponseTypeDef",
-    {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteDeviceResponseTypeDef = TypedDict(
-    "DeleteDeviceResponseTypeDef",
-    {
-        "DeviceId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 DescribeApplicationInstanceDetailsResponseTypeDef = TypedDict(
     "DescribeApplicationInstanceDetailsResponseTypeDef",
     {
         "ApplicationInstanceId": str,
         "ApplicationInstanceIdToReplace": str,
         "CreatedTime": datetime,
         "DefaultRuntimeContextDevice": str,
         "Description": str,
         "ManifestOverridesPayload": ManifestOverridesPayloadTypeDef,
         "ManifestPayload": ManifestPayloadTypeDef,
         "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeApplicationInstanceResponseTypeDef = TypedDict(
-    "DescribeApplicationInstanceResponseTypeDef",
-    {
-        "ApplicationInstanceId": str,
-        "ApplicationInstanceIdToReplace": str,
-        "Arn": str,
-        "CreatedTime": datetime,
-        "DefaultRuntimeContextDevice": str,
-        "DefaultRuntimeContextDeviceName": str,
-        "Description": str,
-        "HealthStatus": ApplicationInstanceHealthStatusType,
-        "LastUpdatedTime": datetime,
-        "Name": str,
-        "RuntimeContextStates": List[ReportedRuntimeContextStateTypeDef],
-        "RuntimeRoleArn": str,
-        "Status": ApplicationInstanceStatusType,
-        "StatusDescription": str,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeDeviceJobResponseTypeDef = TypedDict(
-    "DescribeDeviceJobResponseTypeDef",
-    {
-        "CreatedTime": datetime,
-        "DeviceArn": str,
-        "DeviceId": str,
-        "DeviceName": str,
-        "DeviceType": DeviceTypeType,
-        "ImageVersion": str,
-        "JobId": str,
-        "JobType": JobTypeType,
-        "Status": UpdateProgressType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribePackageVersionResponseTypeDef = TypedDict(
-    "DescribePackageVersionResponseTypeDef",
-    {
-        "IsLatestPatch": bool,
-        "OwnerAccount": str,
-        "PackageArn": str,
-        "PackageId": str,
-        "PackageName": str,
-        "PackageVersion": str,
-        "PatchVersion": str,
-        "RegisteredTime": datetime,
-        "Status": PackageVersionStatusType,
-        "StatusDescription": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ProvisionDeviceResponseTypeDef = TypedDict(
-    "ProvisionDeviceResponseTypeDef",
-    {
-        "Arn": str,
-        "Certificates": bytes,
-        "DeviceId": str,
-        "IotThingName": str,
-        "Status": DeviceStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SignalApplicationInstanceNodeInstancesResponseTypeDef = TypedDict(
-    "SignalApplicationInstanceNodeInstancesResponseTypeDef",
-    {
-        "ApplicationInstanceId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateDeviceMetadataResponseTypeDef = TypedDict(
-    "UpdateDeviceMetadataResponseTypeDef",
-    {
-        "DeviceId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateJobForDevicesResponseTypeDef = TypedDict(
     "CreateJobForDevicesResponseTypeDef",
     {
         "Jobs": List[JobTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateNodeFromTemplateJobRequestRequestTypeDef = TypedDict(
     "_RequiredCreateNodeFromTemplateJobRequestRequestTypeDef",
     {
         "NodeName": str,
@@ -1082,40 +1082,40 @@
         "NodeName": str,
         "OutputPackageName": str,
         "OutputPackageVersion": str,
         "Status": NodeFromTemplateJobStatusType,
         "StatusMessage": str,
         "TemplateParameters": Dict[str, str],
         "TemplateType": Literal["RTSP_CAMERA_STREAM"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreatePackageResponseTypeDef = TypedDict(
     "CreatePackageResponseTypeDef",
     {
         "Arn": str,
         "PackageId": str,
         "StorageLocation": StorageLocationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribePackageResponseTypeDef = TypedDict(
     "DescribePackageResponseTypeDef",
     {
         "Arn": str,
         "CreatedTime": datetime,
         "PackageId": str,
         "PackageName": str,
         "ReadAccessPrincipalArns": List[str],
         "StorageLocation": StorageLocationTypeDef,
         "Tags": Dict[str, str],
         "WriteAccessPrincipalArns": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeviceTypeDef = TypedDict(
     "DeviceTypeDef",
     {
         "Brand": DeviceBrandType,
@@ -1144,15 +1144,15 @@
 )
 
 ListDevicesJobsResponseTypeDef = TypedDict(
     "ListDevicesJobsResponseTypeDef",
     {
         "DeviceJobs": List[DeviceJobTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredEthernetPayloadTypeDef = TypedDict(
     "_RequiredEthernetPayloadTypeDef",
     {
         "ConnectionType": ConnectionTypeType,
@@ -1172,60 +1172,60 @@
 
 
 ListApplicationInstanceDependenciesResponseTypeDef = TypedDict(
     "ListApplicationInstanceDependenciesResponseTypeDef",
     {
         "NextToken": str,
         "PackageObjects": List[PackageObjectTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListApplicationInstanceNodeInstancesResponseTypeDef = TypedDict(
     "ListApplicationInstanceNodeInstancesResponseTypeDef",
     {
         "NextToken": str,
         "NodeInstances": List[NodeInstanceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListNodeFromTemplateJobsResponseTypeDef = TypedDict(
     "ListNodeFromTemplateJobsResponseTypeDef",
     {
         "NextToken": str,
         "NodeFromTemplateJobs": List[NodeFromTemplateJobTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListNodesResponseTypeDef = TypedDict(
     "ListNodesResponseTypeDef",
     {
         "NextToken": str,
         "Nodes": List[NodeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPackageImportJobsResponseTypeDef = TypedDict(
     "ListPackageImportJobsResponseTypeDef",
     {
         "NextToken": str,
         "PackageImportJobs": List[PackageImportJobTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPackagesResponseTypeDef = TypedDict(
     "ListPackagesResponseTypeDef",
     {
         "NextToken": str,
         "Packages": List[PackageListItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 NetworkStatusTypeDef = TypedDict(
     "NetworkStatusTypeDef",
     {
         "Ethernet0Status": EthernetStatusTypeDef,
@@ -1278,24 +1278,24 @@
 )
 
 ListApplicationInstancesResponseTypeDef = TypedDict(
     "ListApplicationInstancesResponseTypeDef",
     {
         "ApplicationInstances": List[ApplicationInstanceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDevicesResponseTypeDef = TypedDict(
     "ListDevicesResponseTypeDef",
     {
         "Devices": List[DeviceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateJobForDevicesRequestRequestTypeDef = TypedDict(
     "_RequiredCreateJobForDevicesRequestRequestTypeDef",
     {
         "DeviceIds": Sequence[str],
@@ -1341,15 +1341,15 @@
         "NodeInterface": NodeInterfaceTypeDef,
         "OwnerAccount": str,
         "PackageArn": str,
         "PackageId": str,
         "PackageName": str,
         "PackageVersion": str,
         "PatchVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PackageImportJobInputConfigTypeDef = TypedDict(
     "PackageImportJobInputConfigTypeDef",
     {
         "PackageVersionInputConfig": PackageVersionInputConfigTypeDef,
@@ -1376,15 +1376,15 @@
         "LeaseExpirationTime": datetime,
         "Name": str,
         "NetworkingConfiguration": NetworkPayloadTypeDef,
         "ProvisioningStatus": DeviceStatusType,
         "SerialNumber": str,
         "Tags": Dict[str, str],
         "Type": DeviceTypeType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredProvisionDeviceRequestRequestTypeDef = TypedDict(
     "_RequiredProvisionDeviceRequestRequestTypeDef",
     {
         "Name": str,
@@ -1442,10 +1442,10 @@
         "JobTags": List[JobResourceTagsTypeDef],
         "JobType": PackageImportJobTypeType,
         "LastUpdatedTime": datetime,
         "Output": PackageImportJobOutputTypeDef,
         "OutputConfig": PackageImportJobOutputConfigTypeDef,
         "Status": PackageImportJobStatusType,
         "StatusMessage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-panorama-2.5.0.post1/types_aiobotocore_panorama/type_defs.pyi` & `types-aiobotocore-panorama-2.5.1/types_aiobotocore_panorama/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -52,32 +52,37 @@
     from typing_extensions import TypedDict
 
 __all__ = (
     "AlternateSoftwareMetadataTypeDef",
     "ReportedRuntimeContextStateTypeDef",
     "ManifestOverridesPayloadTypeDef",
     "ManifestPayloadTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateApplicationInstanceResponseTypeDef",
     "JobTypeDef",
     "JobResourceTagsTypeDef",
+    "CreateNodeFromTemplateJobResponseTypeDef",
+    "CreatePackageImportJobResponseTypeDef",
     "CreatePackageRequestRequestTypeDef",
     "StorageLocationTypeDef",
     "DeleteDeviceRequestRequestTypeDef",
+    "DeleteDeviceResponseTypeDef",
     "DeletePackageRequestRequestTypeDef",
     "DeregisterPackageVersionRequestRequestTypeDef",
     "DescribeApplicationInstanceDetailsRequestRequestTypeDef",
     "DescribeApplicationInstanceRequestRequestTypeDef",
     "DescribeDeviceJobRequestRequestTypeDef",
+    "DescribeDeviceJobResponseTypeDef",
     "DescribeDeviceRequestRequestTypeDef",
     "LatestDeviceJobTypeDef",
     "DescribeNodeFromTemplateJobRequestRequestTypeDef",
     "DescribeNodeRequestRequestTypeDef",
     "DescribePackageImportJobRequestRequestTypeDef",
     "DescribePackageRequestRequestTypeDef",
     "DescribePackageVersionRequestRequestTypeDef",
+    "DescribePackageVersionResponseTypeDef",
     "OTAJobConfigTypeDef",
     "DeviceJobTypeDef",
     "StaticIpConnectionInfoTypeDef",
     "EthernetStatusTypeDef",
     "ListApplicationInstanceDependenciesRequestRequestTypeDef",
     "PackageObjectTypeDef",
     "ListApplicationInstanceNodeInstancesRequestRequestTypeDef",
@@ -90,41 +95,36 @@
     "ListNodesRequestRequestTypeDef",
     "NodeTypeDef",
     "ListPackageImportJobsRequestRequestTypeDef",
     "PackageImportJobTypeDef",
     "ListPackagesRequestRequestTypeDef",
     "PackageListItemTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "NtpPayloadTypeDef",
     "NtpStatusTypeDef",
     "NodeInputPortTypeDef",
     "NodeOutputPortTypeDef",
     "NodeSignalTypeDef",
     "OutPutS3LocationTypeDef",
     "PackageVersionOutputConfigTypeDef",
     "S3LocationTypeDef",
+    "ProvisionDeviceResponseTypeDef",
     "RegisterPackageVersionRequestRequestTypeDef",
     "RemoveApplicationInstanceRequestRequestTypeDef",
+    "ResponseMetadataTypeDef",
+    "SignalApplicationInstanceNodeInstancesResponseTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateDeviceMetadataRequestRequestTypeDef",
+    "UpdateDeviceMetadataResponseTypeDef",
     "ApplicationInstanceTypeDef",
+    "DescribeApplicationInstanceResponseTypeDef",
     "CreateApplicationInstanceRequestRequestTypeDef",
-    "CreateApplicationInstanceResponseTypeDef",
-    "CreateNodeFromTemplateJobResponseTypeDef",
-    "CreatePackageImportJobResponseTypeDef",
-    "DeleteDeviceResponseTypeDef",
     "DescribeApplicationInstanceDetailsResponseTypeDef",
-    "DescribeApplicationInstanceResponseTypeDef",
-    "DescribeDeviceJobResponseTypeDef",
-    "DescribePackageVersionResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "ProvisionDeviceResponseTypeDef",
-    "SignalApplicationInstanceNodeInstancesResponseTypeDef",
-    "UpdateDeviceMetadataResponseTypeDef",
     "CreateJobForDevicesResponseTypeDef",
     "CreateNodeFromTemplateJobRequestRequestTypeDef",
     "DescribeNodeFromTemplateJobResponseTypeDef",
     "CreatePackageResponseTypeDef",
     "DescribePackageResponseTypeDef",
     "DeviceTypeDef",
     "DeviceJobConfigTypeDef",
@@ -184,22 +184,19 @@
     "ManifestPayloadTypeDef",
     {
         "PayloadData": str,
     },
     total=False,
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateApplicationInstanceResponseTypeDef = TypedDict(
+    "CreateApplicationInstanceResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ApplicationInstanceId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 JobTypeDef = TypedDict(
     "JobTypeDef",
     {
         "DeviceId": str,
@@ -212,14 +209,30 @@
     "JobResourceTagsTypeDef",
     {
         "ResourceType": Literal["PACKAGE"],
         "Tags": Mapping[str, str],
     },
 )
 
+CreateNodeFromTemplateJobResponseTypeDef = TypedDict(
+    "CreateNodeFromTemplateJobResponseTypeDef",
+    {
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+CreatePackageImportJobResponseTypeDef = TypedDict(
+    "CreatePackageImportJobResponseTypeDef",
+    {
+        "JobId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreatePackageRequestRequestTypeDef = TypedDict(
     "_RequiredCreatePackageRequestRequestTypeDef",
     {
         "PackageName": str,
     },
 )
 _OptionalCreatePackageRequestRequestTypeDef = TypedDict(
@@ -249,14 +262,22 @@
 DeleteDeviceRequestRequestTypeDef = TypedDict(
     "DeleteDeviceRequestRequestTypeDef",
     {
         "DeviceId": str,
     },
 )
 
+DeleteDeviceResponseTypeDef = TypedDict(
+    "DeleteDeviceResponseTypeDef",
+    {
+        "DeviceId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredDeletePackageRequestRequestTypeDef = TypedDict(
     "_RequiredDeletePackageRequestRequestTypeDef",
     {
         "PackageId": str,
     },
 )
 _OptionalDeletePackageRequestRequestTypeDef = TypedDict(
@@ -312,14 +333,30 @@
 DescribeDeviceJobRequestRequestTypeDef = TypedDict(
     "DescribeDeviceJobRequestRequestTypeDef",
     {
         "JobId": str,
     },
 )
 
+DescribeDeviceJobResponseTypeDef = TypedDict(
+    "DescribeDeviceJobResponseTypeDef",
+    {
+        "CreatedTime": datetime,
+        "DeviceArn": str,
+        "DeviceId": str,
+        "DeviceName": str,
+        "DeviceType": DeviceTypeType,
+        "ImageVersion": str,
+        "JobId": str,
+        "JobType": JobTypeType,
+        "Status": UpdateProgressType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeDeviceRequestRequestTypeDef = TypedDict(
     "DescribeDeviceRequestRequestTypeDef",
     {
         "DeviceId": str,
     },
 )
 
@@ -391,14 +428,31 @@
 
 class DescribePackageVersionRequestRequestTypeDef(
     _RequiredDescribePackageVersionRequestRequestTypeDef,
     _OptionalDescribePackageVersionRequestRequestTypeDef,
 ):
     pass
 
+DescribePackageVersionResponseTypeDef = TypedDict(
+    "DescribePackageVersionResponseTypeDef",
+    {
+        "IsLatestPatch": bool,
+        "OwnerAccount": str,
+        "PackageArn": str,
+        "PackageId": str,
+        "PackageName": str,
+        "PackageVersion": str,
+        "PatchVersion": str,
+        "RegisteredTime": datetime,
+        "Status": PackageVersionStatusType,
+        "StatusDescription": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredOTAJobConfigTypeDef = TypedDict(
     "_RequiredOTAJobConfigTypeDef",
     {
         "ImageVersion": str,
     },
 )
 _OptionalOTAJobConfigTypeDef = TypedDict(
@@ -659,14 +713,22 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 NtpPayloadTypeDef = TypedDict(
     "NtpPayloadTypeDef",
     {
         "NtpServers": List[str],
     },
 )
 
@@ -752,14 +814,26 @@
     },
     total=False,
 )
 
 class S3LocationTypeDef(_RequiredS3LocationTypeDef, _OptionalS3LocationTypeDef):
     pass
 
+ProvisionDeviceResponseTypeDef = TypedDict(
+    "ProvisionDeviceResponseTypeDef",
+    {
+        "Arn": str,
+        "Certificates": bytes,
+        "DeviceId": str,
+        "IotThingName": str,
+        "Status": DeviceStatusType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredRegisterPackageVersionRequestRequestTypeDef = TypedDict(
     "_RequiredRegisterPackageVersionRequestRequestTypeDef",
     {
         "PackageId": str,
         "PackageVersion": str,
         "PatchVersion": str,
     },
@@ -782,14 +856,33 @@
 RemoveApplicationInstanceRequestRequestTypeDef = TypedDict(
     "RemoveApplicationInstanceRequestRequestTypeDef",
     {
         "ApplicationInstanceId": str,
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
+SignalApplicationInstanceNodeInstancesResponseTypeDef = TypedDict(
+    "SignalApplicationInstanceNodeInstancesResponseTypeDef",
+    {
+        "ApplicationInstanceId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "Tags": Mapping[str, str],
     },
 )
@@ -818,14 +911,22 @@
 
 class UpdateDeviceMetadataRequestRequestTypeDef(
     _RequiredUpdateDeviceMetadataRequestRequestTypeDef,
     _OptionalUpdateDeviceMetadataRequestRequestTypeDef,
 ):
     pass
 
+UpdateDeviceMetadataResponseTypeDef = TypedDict(
+    "UpdateDeviceMetadataResponseTypeDef",
+    {
+        "DeviceId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 ApplicationInstanceTypeDef = TypedDict(
     "ApplicationInstanceTypeDef",
     {
         "ApplicationInstanceId": str,
         "Arn": str,
         "CreatedTime": datetime,
         "DefaultRuntimeContextDevice": str,
@@ -837,14 +938,36 @@
         "Status": ApplicationInstanceStatusType,
         "StatusDescription": str,
         "Tags": Dict[str, str],
     },
     total=False,
 )
 
+DescribeApplicationInstanceResponseTypeDef = TypedDict(
+    "DescribeApplicationInstanceResponseTypeDef",
+    {
+        "ApplicationInstanceId": str,
+        "ApplicationInstanceIdToReplace": str,
+        "Arn": str,
+        "CreatedTime": datetime,
+        "DefaultRuntimeContextDevice": str,
+        "DefaultRuntimeContextDeviceName": str,
+        "Description": str,
+        "HealthStatus": ApplicationInstanceHealthStatusType,
+        "LastUpdatedTime": datetime,
+        "Name": str,
+        "RuntimeContextStates": List[ReportedRuntimeContextStateTypeDef],
+        "RuntimeRoleArn": str,
+        "Status": ApplicationInstanceStatusType,
+        "StatusDescription": str,
+        "Tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateApplicationInstanceRequestRequestTypeDef = TypedDict(
     "_RequiredCreateApplicationInstanceRequestRequestTypeDef",
     {
         "DefaultRuntimeContextDevice": str,
         "ManifestPayload": ManifestPayloadTypeDef,
     },
 )
@@ -863,157 +986,34 @@
 
 class CreateApplicationInstanceRequestRequestTypeDef(
     _RequiredCreateApplicationInstanceRequestRequestTypeDef,
     _OptionalCreateApplicationInstanceRequestRequestTypeDef,
 ):
     pass
 
-CreateApplicationInstanceResponseTypeDef = TypedDict(
-    "CreateApplicationInstanceResponseTypeDef",
-    {
-        "ApplicationInstanceId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateNodeFromTemplateJobResponseTypeDef = TypedDict(
-    "CreateNodeFromTemplateJobResponseTypeDef",
-    {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreatePackageImportJobResponseTypeDef = TypedDict(
-    "CreatePackageImportJobResponseTypeDef",
-    {
-        "JobId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DeleteDeviceResponseTypeDef = TypedDict(
-    "DeleteDeviceResponseTypeDef",
-    {
-        "DeviceId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 DescribeApplicationInstanceDetailsResponseTypeDef = TypedDict(
     "DescribeApplicationInstanceDetailsResponseTypeDef",
     {
         "ApplicationInstanceId": str,
         "ApplicationInstanceIdToReplace": str,
         "CreatedTime": datetime,
         "DefaultRuntimeContextDevice": str,
         "Description": str,
         "ManifestOverridesPayload": ManifestOverridesPayloadTypeDef,
         "ManifestPayload": ManifestPayloadTypeDef,
         "Name": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeApplicationInstanceResponseTypeDef = TypedDict(
-    "DescribeApplicationInstanceResponseTypeDef",
-    {
-        "ApplicationInstanceId": str,
-        "ApplicationInstanceIdToReplace": str,
-        "Arn": str,
-        "CreatedTime": datetime,
-        "DefaultRuntimeContextDevice": str,
-        "DefaultRuntimeContextDeviceName": str,
-        "Description": str,
-        "HealthStatus": ApplicationInstanceHealthStatusType,
-        "LastUpdatedTime": datetime,
-        "Name": str,
-        "RuntimeContextStates": List[ReportedRuntimeContextStateTypeDef],
-        "RuntimeRoleArn": str,
-        "Status": ApplicationInstanceStatusType,
-        "StatusDescription": str,
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeDeviceJobResponseTypeDef = TypedDict(
-    "DescribeDeviceJobResponseTypeDef",
-    {
-        "CreatedTime": datetime,
-        "DeviceArn": str,
-        "DeviceId": str,
-        "DeviceName": str,
-        "DeviceType": DeviceTypeType,
-        "ImageVersion": str,
-        "JobId": str,
-        "JobType": JobTypeType,
-        "Status": UpdateProgressType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribePackageVersionResponseTypeDef = TypedDict(
-    "DescribePackageVersionResponseTypeDef",
-    {
-        "IsLatestPatch": bool,
-        "OwnerAccount": str,
-        "PackageArn": str,
-        "PackageId": str,
-        "PackageName": str,
-        "PackageVersion": str,
-        "PatchVersion": str,
-        "RegisteredTime": datetime,
-        "Status": PackageVersionStatusType,
-        "StatusDescription": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "Tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ProvisionDeviceResponseTypeDef = TypedDict(
-    "ProvisionDeviceResponseTypeDef",
-    {
-        "Arn": str,
-        "Certificates": bytes,
-        "DeviceId": str,
-        "IotThingName": str,
-        "Status": DeviceStatusType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-SignalApplicationInstanceNodeInstancesResponseTypeDef = TypedDict(
-    "SignalApplicationInstanceNodeInstancesResponseTypeDef",
-    {
-        "ApplicationInstanceId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateDeviceMetadataResponseTypeDef = TypedDict(
-    "UpdateDeviceMetadataResponseTypeDef",
-    {
-        "DeviceId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateJobForDevicesResponseTypeDef = TypedDict(
     "CreateJobForDevicesResponseTypeDef",
     {
         "Jobs": List[JobTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateNodeFromTemplateJobRequestRequestTypeDef = TypedDict(
     "_RequiredCreateNodeFromTemplateJobRequestRequestTypeDef",
     {
         "NodeName": str,
@@ -1049,40 +1049,40 @@
         "NodeName": str,
         "OutputPackageName": str,
         "OutputPackageVersion": str,
         "Status": NodeFromTemplateJobStatusType,
         "StatusMessage": str,
         "TemplateParameters": Dict[str, str],
         "TemplateType": Literal["RTSP_CAMERA_STREAM"],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreatePackageResponseTypeDef = TypedDict(
     "CreatePackageResponseTypeDef",
     {
         "Arn": str,
         "PackageId": str,
         "StorageLocation": StorageLocationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribePackageResponseTypeDef = TypedDict(
     "DescribePackageResponseTypeDef",
     {
         "Arn": str,
         "CreatedTime": datetime,
         "PackageId": str,
         "PackageName": str,
         "ReadAccessPrincipalArns": List[str],
         "StorageLocation": StorageLocationTypeDef,
         "Tags": Dict[str, str],
         "WriteAccessPrincipalArns": List[str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeviceTypeDef = TypedDict(
     "DeviceTypeDef",
     {
         "Brand": DeviceBrandType,
@@ -1111,15 +1111,15 @@
 )
 
 ListDevicesJobsResponseTypeDef = TypedDict(
     "ListDevicesJobsResponseTypeDef",
     {
         "DeviceJobs": List[DeviceJobTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredEthernetPayloadTypeDef = TypedDict(
     "_RequiredEthernetPayloadTypeDef",
     {
         "ConnectionType": ConnectionTypeType,
@@ -1137,60 +1137,60 @@
     pass
 
 ListApplicationInstanceDependenciesResponseTypeDef = TypedDict(
     "ListApplicationInstanceDependenciesResponseTypeDef",
     {
         "NextToken": str,
         "PackageObjects": List[PackageObjectTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListApplicationInstanceNodeInstancesResponseTypeDef = TypedDict(
     "ListApplicationInstanceNodeInstancesResponseTypeDef",
     {
         "NextToken": str,
         "NodeInstances": List[NodeInstanceTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListNodeFromTemplateJobsResponseTypeDef = TypedDict(
     "ListNodeFromTemplateJobsResponseTypeDef",
     {
         "NextToken": str,
         "NodeFromTemplateJobs": List[NodeFromTemplateJobTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListNodesResponseTypeDef = TypedDict(
     "ListNodesResponseTypeDef",
     {
         "NextToken": str,
         "Nodes": List[NodeTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPackageImportJobsResponseTypeDef = TypedDict(
     "ListPackageImportJobsResponseTypeDef",
     {
         "NextToken": str,
         "PackageImportJobs": List[PackageImportJobTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListPackagesResponseTypeDef = TypedDict(
     "ListPackagesResponseTypeDef",
     {
         "NextToken": str,
         "Packages": List[PackageListItemTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 NetworkStatusTypeDef = TypedDict(
     "NetworkStatusTypeDef",
     {
         "Ethernet0Status": EthernetStatusTypeDef,
@@ -1243,24 +1243,24 @@
 )
 
 ListApplicationInstancesResponseTypeDef = TypedDict(
     "ListApplicationInstancesResponseTypeDef",
     {
         "ApplicationInstances": List[ApplicationInstanceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDevicesResponseTypeDef = TypedDict(
     "ListDevicesResponseTypeDef",
     {
         "Devices": List[DeviceTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateJobForDevicesRequestRequestTypeDef = TypedDict(
     "_RequiredCreateJobForDevicesRequestRequestTypeDef",
     {
         "DeviceIds": Sequence[str],
@@ -1304,15 +1304,15 @@
         "NodeInterface": NodeInterfaceTypeDef,
         "OwnerAccount": str,
         "PackageArn": str,
         "PackageId": str,
         "PackageName": str,
         "PackageVersion": str,
         "PatchVersion": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 PackageImportJobInputConfigTypeDef = TypedDict(
     "PackageImportJobInputConfigTypeDef",
     {
         "PackageVersionInputConfig": PackageVersionInputConfigTypeDef,
@@ -1339,15 +1339,15 @@
         "LeaseExpirationTime": datetime,
         "Name": str,
         "NetworkingConfiguration": NetworkPayloadTypeDef,
         "ProvisioningStatus": DeviceStatusType,
         "SerialNumber": str,
         "Tags": Dict[str, str],
         "Type": DeviceTypeType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredProvisionDeviceRequestRequestTypeDef = TypedDict(
     "_RequiredProvisionDeviceRequestRequestTypeDef",
     {
         "Name": str,
@@ -1401,10 +1401,10 @@
         "JobTags": List[JobResourceTagsTypeDef],
         "JobType": PackageImportJobTypeType,
         "LastUpdatedTime": datetime,
         "Output": PackageImportJobOutputTypeDef,
         "OutputConfig": PackageImportJobOutputConfigTypeDef,
         "Status": PackageImportJobStatusType,
         "StatusMessage": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-panorama-2.5.0.post1/types_aiobotocore_panorama.egg-info/PKG-INFO` & `types-aiobotocore-panorama-2.5.1/types_aiobotocore_panorama.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-panorama
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Panorama 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Panorama 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_panorama/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-panorama"></a>
 
 # types-aiobotocore-panorama
 
 [![PyPI - types-aiobotocore-panorama](https://img.shields.io/pypi/v/types-aiobotocore-panorama.svg?color=blue)](https://pypi.org/project/types-aiobotocore-panorama)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-panorama.svg?color=blue)](https://pypi.org/project/types-aiobotocore-panorama)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_panorama/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-panorama?color=blue)](https://pypistats.org/packages/types-aiobotocore-panorama)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Panorama 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/panorama.html#Panorama)
+[aiobotocore.Panorama 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/panorama.html#Panorama)
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
 [types-aiobotocore-panorama docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_panorama/).
 
 See how it helps to find and fix potential bugs:
 
@@ -317,32 +317,37 @@
 
 ```python
 from types_aiobotocore_panorama.type_defs import (
     AlternateSoftwareMetadataTypeDef,
     ReportedRuntimeContextStateTypeDef,
     ManifestOverridesPayloadTypeDef,
     ManifestPayloadTypeDef,
-    ResponseMetadataTypeDef,
+    CreateApplicationInstanceResponseTypeDef,
     JobTypeDef,
     JobResourceTagsTypeDef,
+    CreateNodeFromTemplateJobResponseTypeDef,
+    CreatePackageImportJobResponseTypeDef,
     CreatePackageRequestRequestTypeDef,
     StorageLocationTypeDef,
     DeleteDeviceRequestRequestTypeDef,
+    DeleteDeviceResponseTypeDef,
     DeletePackageRequestRequestTypeDef,
     DeregisterPackageVersionRequestRequestTypeDef,
     DescribeApplicationInstanceDetailsRequestRequestTypeDef,
     DescribeApplicationInstanceRequestRequestTypeDef,
     DescribeDeviceJobRequestRequestTypeDef,
+    DescribeDeviceJobResponseTypeDef,
     DescribeDeviceRequestRequestTypeDef,
     LatestDeviceJobTypeDef,
     DescribeNodeFromTemplateJobRequestRequestTypeDef,
     DescribeNodeRequestRequestTypeDef,
     DescribePackageImportJobRequestRequestTypeDef,
     DescribePackageRequestRequestTypeDef,
     DescribePackageVersionRequestRequestTypeDef,
+    DescribePackageVersionResponseTypeDef,
     OTAJobConfigTypeDef,
     DeviceJobTypeDef,
     StaticIpConnectionInfoTypeDef,
     EthernetStatusTypeDef,
     ListApplicationInstanceDependenciesRequestRequestTypeDef,
     PackageObjectTypeDef,
     ListApplicationInstanceNodeInstancesRequestRequestTypeDef,
@@ -355,41 +360,36 @@
     ListNodesRequestRequestTypeDef,
     NodeTypeDef,
     ListPackageImportJobsRequestRequestTypeDef,
     PackageImportJobTypeDef,
     ListPackagesRequestRequestTypeDef,
     PackageListItemTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     NtpPayloadTypeDef,
     NtpStatusTypeDef,
     NodeInputPortTypeDef,
     NodeOutputPortTypeDef,
     NodeSignalTypeDef,
     OutPutS3LocationTypeDef,
     PackageVersionOutputConfigTypeDef,
     S3LocationTypeDef,
+    ProvisionDeviceResponseTypeDef,
     RegisterPackageVersionRequestRequestTypeDef,
     RemoveApplicationInstanceRequestRequestTypeDef,
+    ResponseMetadataTypeDef,
+    SignalApplicationInstanceNodeInstancesResponseTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateDeviceMetadataRequestRequestTypeDef,
+    UpdateDeviceMetadataResponseTypeDef,
     ApplicationInstanceTypeDef,
+    DescribeApplicationInstanceResponseTypeDef,
     CreateApplicationInstanceRequestRequestTypeDef,
-    CreateApplicationInstanceResponseTypeDef,
-    CreateNodeFromTemplateJobResponseTypeDef,
-    CreatePackageImportJobResponseTypeDef,
-    DeleteDeviceResponseTypeDef,
     DescribeApplicationInstanceDetailsResponseTypeDef,
-    DescribeApplicationInstanceResponseTypeDef,
-    DescribeDeviceJobResponseTypeDef,
-    DescribePackageVersionResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    ProvisionDeviceResponseTypeDef,
-    SignalApplicationInstanceNodeInstancesResponseTypeDef,
-    UpdateDeviceMetadataResponseTypeDef,
     CreateJobForDevicesResponseTypeDef,
     CreateNodeFromTemplateJobRequestRequestTypeDef,
     DescribeNodeFromTemplateJobResponseTypeDef,
     CreatePackageResponseTypeDef,
     DescribePackageResponseTypeDef,
     DeviceTypeDef,
     DeviceJobConfigTypeDef,
@@ -427,43 +427,43 @@
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

### Comparing `types-aiobotocore-panorama-2.5.0.post1/types_aiobotocore_panorama.egg-info/SOURCES.txt` & `types-aiobotocore-panorama-2.5.1/types_aiobotocore_panorama.egg-info/SOURCES.txt`

 * *Files identical despite different names*

