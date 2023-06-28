# Comparing `tmp/types-aiobotocore-snow-device-management-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-snow-device-management-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-snow-device-management-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:22 2023, max compression
+gzip compressed data, was "types-aiobotocore-snow-device-management-2.5.1.tar", last modified: Wed Jun 28 01:44:12 2023, max compression
```

## Comparing `types-aiobotocore-snow-device-management-2.5.0.post1.tar` & `types-aiobotocore-snow-device-management-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:22.875651 types-aiobotocore-snow-device-management-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:24:19.000000 types-aiobotocore-snow-device-management-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    15836 2023-03-11 12:27:22.871652 types-aiobotocore-snow-device-management-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    14207 2023-03-11 12:24:19.000000 types-aiobotocore-snow-device-management-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:22.875651 types-aiobotocore-snow-device-management-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2219 2023-03-11 12:24:19.000000 types-aiobotocore-snow-device-management-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:22.871652 types-aiobotocore-snow-device-management-2.5.0.post1/types_aiobotocore_snow_device_management/
--rw-r--r--   0 runner    (1001) docker     (123)     1335 2023-03-11 12:24:19.000000 types-aiobotocore-snow-device-management-2.5.0.post1/types_aiobotocore_snow_device_management/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1334 2023-03-11 12:24:19.000000 types-aiobotocore-snow-device-management-2.5.0.post1/types_aiobotocore_snow_device_management/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      999 2023-03-11 12:24:19.000000 types-aiobotocore-snow-device-management-2.5.0.post1/types_aiobotocore_snow_device_management/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    14953 2023-03-11 12:24:19.000000 types-aiobotocore-snow-device-management-2.5.0.post1/types_aiobotocore_snow_device_management/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    14927 2023-03-11 12:24:19.000000 types-aiobotocore-snow-device-management-2.5.0.post1/types_aiobotocore_snow_device_management/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8646 2023-03-11 12:24:19.000000 types-aiobotocore-snow-device-management-2.5.0.post1/types_aiobotocore_snow_device_management/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8644 2023-03-11 12:24:19.000000 types-aiobotocore-snow-device-management-2.5.0.post1/types_aiobotocore_snow_device_management/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     5938 2023-03-11 12:24:19.000000 types-aiobotocore-snow-device-management-2.5.0.post1/types_aiobotocore_snow_device_management/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     5931 2023-03-11 12:24:19.000000 types-aiobotocore-snow-device-management-2.5.0.post1/types_aiobotocore_snow_device_management/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:24:19.000000 types-aiobotocore-snow-device-management-2.5.0.post1/types_aiobotocore_snow_device_management/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    14757 2023-03-11 12:24:20.000000 types-aiobotocore-snow-device-management-2.5.0.post1/types_aiobotocore_snow_device_management/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    14742 2023-03-11 12:24:20.000000 types-aiobotocore-snow-device-management-2.5.0.post1/types_aiobotocore_snow_device_management/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:24:19.000000 types-aiobotocore-snow-device-management-2.5.0.post1/types_aiobotocore_snow_device_management/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:22.871652 types-aiobotocore-snow-device-management-2.5.0.post1/types_aiobotocore_snow_device_management.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    15836 2023-03-11 12:27:22.000000 types-aiobotocore-snow-device-management-2.5.0.post1/types_aiobotocore_snow_device_management.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1098 2023-03-11 12:27:22.000000 types-aiobotocore-snow-device-management-2.5.0.post1/types_aiobotocore_snow_device_management.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:22.000000 types-aiobotocore-snow-device-management-2.5.0.post1/types_aiobotocore_snow_device_management.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:22.000000 types-aiobotocore-snow-device-management-2.5.0.post1/types_aiobotocore_snow_device_management.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:22.000000 types-aiobotocore-snow-device-management-2.5.0.post1/types_aiobotocore_snow_device_management.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       41 2023-03-11 12:27:22.000000 types-aiobotocore-snow-device-management-2.5.0.post1/types_aiobotocore_snow_device_management.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:12.530217 types-aiobotocore-snow-device-management-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:41:07.000000 types-aiobotocore-snow-device-management-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    15843 2023-06-28 01:44:12.526217 types-aiobotocore-snow-device-management-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    14220 2023-06-28 01:41:07.000000 types-aiobotocore-snow-device-management-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:12.530217 types-aiobotocore-snow-device-management-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2213 2023-06-28 01:41:07.000000 types-aiobotocore-snow-device-management-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:12.522217 types-aiobotocore-snow-device-management-2.5.1/types_aiobotocore_snow_device_management/
+-rw-r--r--   0 runner    (1001) docker     (123)     1335 2023-06-28 01:41:07.000000 types-aiobotocore-snow-device-management-2.5.1/types_aiobotocore_snow_device_management/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1334 2023-06-28 01:41:07.000000 types-aiobotocore-snow-device-management-2.5.1/types_aiobotocore_snow_device_management/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      987 2023-06-28 01:41:07.000000 types-aiobotocore-snow-device-management-2.5.1/types_aiobotocore_snow_device_management/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14953 2023-06-28 01:41:07.000000 types-aiobotocore-snow-device-management-2.5.1/types_aiobotocore_snow_device_management/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14927 2023-06-28 01:41:07.000000 types-aiobotocore-snow-device-management-2.5.1/types_aiobotocore_snow_device_management/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8855 2023-06-28 01:41:08.000000 types-aiobotocore-snow-device-management-2.5.1/types_aiobotocore_snow_device_management/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8853 2023-06-28 01:41:07.000000 types-aiobotocore-snow-device-management-2.5.1/types_aiobotocore_snow_device_management/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     5826 2023-06-28 01:41:07.000000 types-aiobotocore-snow-device-management-2.5.1/types_aiobotocore_snow_device_management/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5820 2023-06-28 01:41:07.000000 types-aiobotocore-snow-device-management-2.5.1/types_aiobotocore_snow_device_management/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:41:07.000000 types-aiobotocore-snow-device-management-2.5.1/types_aiobotocore_snow_device_management/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    14789 2023-06-28 01:41:08.000000 types-aiobotocore-snow-device-management-2.5.1/types_aiobotocore_snow_device_management/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14774 2023-06-28 01:41:08.000000 types-aiobotocore-snow-device-management-2.5.1/types_aiobotocore_snow_device_management/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:41:07.000000 types-aiobotocore-snow-device-management-2.5.1/types_aiobotocore_snow_device_management/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:12.526217 types-aiobotocore-snow-device-management-2.5.1/types_aiobotocore_snow_device_management.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    15843 2023-06-28 01:44:12.000000 types-aiobotocore-snow-device-management-2.5.1/types_aiobotocore_snow_device_management.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1098 2023-06-28 01:44:12.000000 types-aiobotocore-snow-device-management-2.5.1/types_aiobotocore_snow_device_management.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:12.000000 types-aiobotocore-snow-device-management-2.5.1/types_aiobotocore_snow_device_management.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:12.000000 types-aiobotocore-snow-device-management-2.5.1/types_aiobotocore_snow_device_management.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:12.000000 types-aiobotocore-snow-device-management-2.5.1/types_aiobotocore_snow_device_management.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       41 2023-06-28 01:44:12.000000 types-aiobotocore-snow-device-management-2.5.1/types_aiobotocore_snow_device_management.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-snow-device-management-2.5.0.post1/LICENSE` & `types-aiobotocore-snow-device-management-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-snow-device-management-2.5.0.post1/PKG-INFO` & `types-aiobotocore-snow-device-management-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-snow-device-management
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SnowDeviceManagement 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SnowDeviceManagement 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snow_device_management/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-snow-device-management"></a>
 
 # types-aiobotocore-snow-device-management
 
 [![PyPI - types-aiobotocore-snow-device-management](https://img.shields.io/pypi/v/types-aiobotocore-snow-device-management.svg?color=blue)](https://pypi.org/project/types-aiobotocore-snow-device-management)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-snow-device-management.svg?color=blue)](https://pypi.org/project/types-aiobotocore-snow-device-management)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snow_device_management/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-snow-device-management?color=blue)](https://pypistats.org/packages/types-aiobotocore-snow-device-management)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SnowDeviceManagement 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snow-device-management.html#SnowDeviceManagement)
+[aiobotocore.SnowDeviceManagement 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snow-device-management.html#SnowDeviceManagement)
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
 [types-aiobotocore-snow-device-management docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snow_device_management/).
 
 See how it helps to find and fix potential bugs:
 
@@ -334,54 +334,54 @@
 
 `types_aiobotocore_snow_device_management.type_defs` module contains structures
 and shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_snow_device_management.type_defs import (
     CancelTaskInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CancelTaskOutputTypeDef,
     CapacityTypeDef,
     CommandTypeDef,
     CpuOptionsTypeDef,
+    CreateTaskOutputTypeDef,
     DescribeDeviceEc2InputRequestTypeDef,
     DescribeDeviceInputRequestTypeDef,
     PhysicalNetworkInterfaceTypeDef,
     SoftwareInformationTypeDef,
     DescribeExecutionInputRequestTypeDef,
+    DescribeExecutionOutputTypeDef,
     DescribeTaskInputRequestTypeDef,
+    DescribeTaskOutputTypeDef,
     DeviceSummaryTypeDef,
     EbsInstanceBlockDeviceTypeDef,
+    EmptyResponseMetadataTypeDef,
     ExecutionSummaryTypeDef,
     InstanceStateTypeDef,
     SecurityGroupIdentifierTypeDef,
-    PaginatorConfigTypeDef,
+    ListDeviceResourcesInputListDeviceResourcesPaginateTypeDef,
     ListDeviceResourcesInputRequestTypeDef,
     ResourceSummaryTypeDef,
+    ListDevicesInputListDevicesPaginateTypeDef,
     ListDevicesInputRequestTypeDef,
+    ListExecutionsInputListExecutionsPaginateTypeDef,
     ListExecutionsInputRequestTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    ListTagsForResourceOutputTypeDef,
+    ListTasksInputListTasksPaginateTypeDef,
     ListTasksInputRequestTypeDef,
     TaskSummaryTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceInputRequestTypeDef,
     UntagResourceInputRequestTypeDef,
-    CancelTaskOutputTypeDef,
-    CreateTaskOutputTypeDef,
-    DescribeExecutionOutputTypeDef,
-    DescribeTaskOutputTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ListTagsForResourceOutputTypeDef,
     CreateTaskInputRequestTypeDef,
     DescribeDeviceOutputTypeDef,
     ListDevicesOutputTypeDef,
     InstanceBlockDeviceMappingTypeDef,
     ListExecutionsOutputTypeDef,
-    ListDeviceResourcesInputListDeviceResourcesPaginateTypeDef,
-    ListDevicesInputListDevicesPaginateTypeDef,
-    ListExecutionsInputListExecutionsPaginateTypeDef,
-    ListTasksInputListTasksPaginateTypeDef,
     ListDeviceResourcesOutputTypeDef,
     ListTasksOutputTypeDef,
     InstanceTypeDef,
     InstanceSummaryTypeDef,
     DescribeDeviceEc2OutputTypeDef,
 )
 
@@ -393,43 +393,43 @@
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

### Comparing `types-aiobotocore-snow-device-management-2.5.0.post1/README.md` & `types-aiobotocore-snow-device-management-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-snow-device-management"></a>
 
 # types-aiobotocore-snow-device-management
 
 [![PyPI - types-aiobotocore-snow-device-management](https://img.shields.io/pypi/v/types-aiobotocore-snow-device-management.svg?color=blue)](https://pypi.org/project/types-aiobotocore-snow-device-management)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-snow-device-management.svg?color=blue)](https://pypi.org/project/types-aiobotocore-snow-device-management)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snow_device_management/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-snow-device-management?color=blue)](https://pypistats.org/packages/types-aiobotocore-snow-device-management)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SnowDeviceManagement 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snow-device-management.html#SnowDeviceManagement)
+[aiobotocore.SnowDeviceManagement 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snow-device-management.html#SnowDeviceManagement)
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
 [types-aiobotocore-snow-device-management docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snow_device_management/).
 
 See how it helps to find and fix potential bugs:
 
@@ -301,54 +301,54 @@
 
 `types_aiobotocore_snow_device_management.type_defs` module contains structures
 and shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_snow_device_management.type_defs import (
     CancelTaskInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CancelTaskOutputTypeDef,
     CapacityTypeDef,
     CommandTypeDef,
     CpuOptionsTypeDef,
+    CreateTaskOutputTypeDef,
     DescribeDeviceEc2InputRequestTypeDef,
     DescribeDeviceInputRequestTypeDef,
     PhysicalNetworkInterfaceTypeDef,
     SoftwareInformationTypeDef,
     DescribeExecutionInputRequestTypeDef,
+    DescribeExecutionOutputTypeDef,
     DescribeTaskInputRequestTypeDef,
+    DescribeTaskOutputTypeDef,
     DeviceSummaryTypeDef,
     EbsInstanceBlockDeviceTypeDef,
+    EmptyResponseMetadataTypeDef,
     ExecutionSummaryTypeDef,
     InstanceStateTypeDef,
     SecurityGroupIdentifierTypeDef,
-    PaginatorConfigTypeDef,
+    ListDeviceResourcesInputListDeviceResourcesPaginateTypeDef,
     ListDeviceResourcesInputRequestTypeDef,
     ResourceSummaryTypeDef,
+    ListDevicesInputListDevicesPaginateTypeDef,
     ListDevicesInputRequestTypeDef,
+    ListExecutionsInputListExecutionsPaginateTypeDef,
     ListExecutionsInputRequestTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    ListTagsForResourceOutputTypeDef,
+    ListTasksInputListTasksPaginateTypeDef,
     ListTasksInputRequestTypeDef,
     TaskSummaryTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceInputRequestTypeDef,
     UntagResourceInputRequestTypeDef,
-    CancelTaskOutputTypeDef,
-    CreateTaskOutputTypeDef,
-    DescribeExecutionOutputTypeDef,
-    DescribeTaskOutputTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ListTagsForResourceOutputTypeDef,
     CreateTaskInputRequestTypeDef,
     DescribeDeviceOutputTypeDef,
     ListDevicesOutputTypeDef,
     InstanceBlockDeviceMappingTypeDef,
     ListExecutionsOutputTypeDef,
-    ListDeviceResourcesInputListDeviceResourcesPaginateTypeDef,
-    ListDevicesInputListDevicesPaginateTypeDef,
-    ListExecutionsInputListExecutionsPaginateTypeDef,
-    ListTasksInputListTasksPaginateTypeDef,
     ListDeviceResourcesOutputTypeDef,
     ListTasksOutputTypeDef,
     InstanceTypeDef,
     InstanceSummaryTypeDef,
     DescribeDeviceEc2OutputTypeDef,
 )
 
@@ -360,43 +360,43 @@
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

### Comparing `types-aiobotocore-snow-device-management-2.5.0.post1/setup.py` & `types-aiobotocore-snow-device-management-2.5.1/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-snow-device-management.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-snow-device-management",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_snow_device_management"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.SnowDeviceManagement 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.SnowDeviceManagement 2.5.1 service generated with"
+        " mypy-boto3-builder 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -48,11 +48,11 @@
     python_requires=">=3.7",
     project_urls={
         "Documentation": "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snow_device_management/",
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

### Comparing `types-aiobotocore-snow-device-management-2.5.0.post1/types_aiobotocore_snow_device_management/__init__.py` & `types-aiobotocore-snow-device-management-2.5.1/types_aiobotocore_snow_device_management/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-snow-device-management-2.5.0.post1/types_aiobotocore_snow_device_management/__init__.pyi` & `types-aiobotocore-snow-device-management-2.5.1/types_aiobotocore_snow_device_management/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-snow-device-management-2.5.0.post1/types_aiobotocore_snow_device_management/__main__.py` & `types-aiobotocore-snow-device-management-2.5.1/types_aiobotocore_snow_device_management/__main__.py`

 * *Files 10% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.SnowDeviceManagement 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.SnowDeviceManagement 2.5.1\nVersion:        "
+        " 2.5.1\nBuilder version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snow_device_management//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snow-device-management.html#SnowDeviceManagement\nOther"
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

### Comparing `types-aiobotocore-snow-device-management-2.5.0.post1/types_aiobotocore_snow_device_management/client.py` & `types-aiobotocore-snow-device-management-2.5.1/types_aiobotocore_snow_device_management/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-snow-device-management-2.5.0.post1/types_aiobotocore_snow_device_management/client.pyi` & `types-aiobotocore-snow-device-management-2.5.1/types_aiobotocore_snow_device_management/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-snow-device-management-2.5.0.post1/types_aiobotocore_snow_device_management/literals.py` & `types-aiobotocore-snow-device-management-2.5.1/types_aiobotocore_snow_device_management/literals.py`

 * *Files 1% similar despite different names*

```diff
@@ -112,14 +112,15 @@
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
@@ -198,14 +199,15 @@
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
@@ -216,14 +218,15 @@
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
@@ -259,14 +262,15 @@
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
@@ -285,16 +289,19 @@
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
@@ -378,15 +385,17 @@
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

### Comparing `types-aiobotocore-snow-device-management-2.5.0.post1/types_aiobotocore_snow_device_management/literals.pyi` & `types-aiobotocore-snow-device-management-2.5.1/types_aiobotocore_snow_device_management/literals.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -110,14 +110,15 @@
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
@@ -196,14 +197,15 @@
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
@@ -214,14 +216,15 @@
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
@@ -257,14 +260,15 @@
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
@@ -283,16 +287,19 @@
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
@@ -376,15 +383,17 @@
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

### Comparing `types-aiobotocore-snow-device-management-2.5.0.post1/types_aiobotocore_snow_device_management/paginator.py` & `types-aiobotocore-snow-device-management-2.5.1/types_aiobotocore_snow_device_management/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -22,112 +22,99 @@
 
         list_device_resources_paginator: ListDeviceResourcesPaginator = client.get_paginator("list_device_resources")
         list_devices_paginator: ListDevicesPaginator = client.get_paginator("list_devices")
         list_executions_paginator: ListExecutionsPaginator = client.get_paginator("list_executions")
         list_tasks_paginator: ListTasksPaginator = client.get_paginator("list_tasks")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ExecutionStateType, TaskStateType
 from .type_defs import (
     ListDeviceResourcesOutputTypeDef,
     ListDevicesOutputTypeDef,
     ListExecutionsOutputTypeDef,
     ListTasksOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListDeviceResourcesPaginator",
     "ListDevicesPaginator",
     "ListExecutionsPaginator",
     "ListTasksPaginator",
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
 class ListDeviceResourcesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snow-device-management.html#SnowDeviceManagement.Paginator.ListDeviceResources)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snow_device_management/paginators/#listdeviceresourcespaginator)
     """
 
     def paginate(
         self,
         *,
         managedDeviceId: str,
         type: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDeviceResourcesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snow-device-management.html#SnowDeviceManagement.Paginator.ListDeviceResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snow_device_management/paginators/#listdeviceresourcespaginator)
         """
 
-
 class ListDevicesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snow-device-management.html#SnowDeviceManagement.Paginator.ListDevices)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snow_device_management/paginators/#listdevicespaginator)
     """
 
     def paginate(
-        self, *, jobId: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, jobId: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDevicesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snow-device-management.html#SnowDeviceManagement.Paginator.ListDevices.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snow_device_management/paginators/#listdevicespaginator)
         """
 
-
 class ListExecutionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snow-device-management.html#SnowDeviceManagement.Paginator.ListExecutions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snow_device_management/paginators/#listexecutionspaginator)
     """
 
     def paginate(
         self,
         *,
         taskId: str,
         state: ExecutionStateType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListExecutionsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snow-device-management.html#SnowDeviceManagement.Paginator.ListExecutions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snow_device_management/paginators/#listexecutionspaginator)
         """
 
-
 class ListTasksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snow-device-management.html#SnowDeviceManagement.Paginator.ListTasks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snow_device_management/paginators/#listtaskspaginator)
     """
 
     def paginate(
-        self, *, state: TaskStateType = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, state: TaskStateType = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTasksOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snow-device-management.html#SnowDeviceManagement.Paginator.ListTasks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snow_device_management/paginators/#listtaskspaginator)
         """
```

### Comparing `types-aiobotocore-snow-device-management-2.5.0.post1/types_aiobotocore_snow_device_management/paginator.pyi` & `types-aiobotocore-snow-device-management-2.5.1/types_aiobotocore_snow_device_management/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -22,105 +22,105 @@
 
         list_device_resources_paginator: ListDeviceResourcesPaginator = client.get_paginator("list_device_resources")
         list_devices_paginator: ListDevicesPaginator = client.get_paginator("list_devices")
         list_executions_paginator: ListExecutionsPaginator = client.get_paginator("list_executions")
         list_tasks_paginator: ListTasksPaginator = client.get_paginator("list_tasks")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import ExecutionStateType, TaskStateType
 from .type_defs import (
     ListDeviceResourcesOutputTypeDef,
     ListDevicesOutputTypeDef,
     ListExecutionsOutputTypeDef,
     ListTasksOutputTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListDeviceResourcesPaginator",
     "ListDevicesPaginator",
     "ListExecutionsPaginator",
     "ListTasksPaginator",
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
 class ListDeviceResourcesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snow-device-management.html#SnowDeviceManagement.Paginator.ListDeviceResources)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snow_device_management/paginators/#listdeviceresourcespaginator)
     """
 
     def paginate(
         self,
         *,
         managedDeviceId: str,
         type: str = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDeviceResourcesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snow-device-management.html#SnowDeviceManagement.Paginator.ListDeviceResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snow_device_management/paginators/#listdeviceresourcespaginator)
         """
 
+
 class ListDevicesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snow-device-management.html#SnowDeviceManagement.Paginator.ListDevices)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snow_device_management/paginators/#listdevicespaginator)
     """
 
     def paginate(
-        self, *, jobId: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, jobId: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDevicesOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snow-device-management.html#SnowDeviceManagement.Paginator.ListDevices.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snow_device_management/paginators/#listdevicespaginator)
         """
 
+
 class ListExecutionsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snow-device-management.html#SnowDeviceManagement.Paginator.ListExecutions)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snow_device_management/paginators/#listexecutionspaginator)
     """
 
     def paginate(
         self,
         *,
         taskId: str,
         state: ExecutionStateType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListExecutionsOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snow-device-management.html#SnowDeviceManagement.Paginator.ListExecutions.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snow_device_management/paginators/#listexecutionspaginator)
         """
 
+
 class ListTasksPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snow-device-management.html#SnowDeviceManagement.Paginator.ListTasks)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snow_device_management/paginators/#listtaskspaginator)
     """
 
     def paginate(
-        self, *, state: TaskStateType = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, state: TaskStateType = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListTasksOutputTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snow-device-management.html#SnowDeviceManagement.Paginator.ListTasks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snow_device_management/paginators/#listtaskspaginator)
         """
```

### Comparing `types-aiobotocore-snow-device-management-2.5.0.post1/types_aiobotocore_snow_device_management/type_defs.py` & `types-aiobotocore-snow-device-management-2.5.1/types_aiobotocore_snow_device_management/type_defs.py`

 * *Files 1% similar despite different names*

```diff
@@ -29,76 +29,73 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "CancelTaskInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CancelTaskOutputTypeDef",
     "CapacityTypeDef",
     "CommandTypeDef",
     "CpuOptionsTypeDef",
+    "CreateTaskOutputTypeDef",
     "DescribeDeviceEc2InputRequestTypeDef",
     "DescribeDeviceInputRequestTypeDef",
     "PhysicalNetworkInterfaceTypeDef",
     "SoftwareInformationTypeDef",
     "DescribeExecutionInputRequestTypeDef",
+    "DescribeExecutionOutputTypeDef",
     "DescribeTaskInputRequestTypeDef",
+    "DescribeTaskOutputTypeDef",
     "DeviceSummaryTypeDef",
     "EbsInstanceBlockDeviceTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "ExecutionSummaryTypeDef",
     "InstanceStateTypeDef",
     "SecurityGroupIdentifierTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListDeviceResourcesInputListDeviceResourcesPaginateTypeDef",
     "ListDeviceResourcesInputRequestTypeDef",
     "ResourceSummaryTypeDef",
+    "ListDevicesInputListDevicesPaginateTypeDef",
     "ListDevicesInputRequestTypeDef",
+    "ListExecutionsInputListExecutionsPaginateTypeDef",
     "ListExecutionsInputRequestTypeDef",
     "ListTagsForResourceInputRequestTypeDef",
+    "ListTagsForResourceOutputTypeDef",
+    "ListTasksInputListTasksPaginateTypeDef",
     "ListTasksInputRequestTypeDef",
     "TaskSummaryTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceInputRequestTypeDef",
     "UntagResourceInputRequestTypeDef",
-    "CancelTaskOutputTypeDef",
-    "CreateTaskOutputTypeDef",
-    "DescribeExecutionOutputTypeDef",
-    "DescribeTaskOutputTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ListTagsForResourceOutputTypeDef",
     "CreateTaskInputRequestTypeDef",
     "DescribeDeviceOutputTypeDef",
     "ListDevicesOutputTypeDef",
     "InstanceBlockDeviceMappingTypeDef",
     "ListExecutionsOutputTypeDef",
-    "ListDeviceResourcesInputListDeviceResourcesPaginateTypeDef",
-    "ListDevicesInputListDevicesPaginateTypeDef",
-    "ListExecutionsInputListExecutionsPaginateTypeDef",
-    "ListTasksInputListTasksPaginateTypeDef",
     "ListDeviceResourcesOutputTypeDef",
     "ListTasksOutputTypeDef",
     "InstanceTypeDef",
     "InstanceSummaryTypeDef",
     "DescribeDeviceEc2OutputTypeDef",
 )
 
 CancelTaskInputRequestTypeDef = TypedDict(
     "CancelTaskInputRequestTypeDef",
     {
         "taskId": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CancelTaskOutputTypeDef = TypedDict(
+    "CancelTaskOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "taskId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CapacityTypeDef = TypedDict(
     "CapacityTypeDef",
     {
         "available": int,
@@ -124,14 +121,23 @@
     {
         "coreCount": int,
         "threadsPerCore": int,
     },
     total=False,
 )
 
+CreateTaskOutputTypeDef = TypedDict(
+    "CreateTaskOutputTypeDef",
+    {
+        "taskArn": str,
+        "taskId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeDeviceEc2InputRequestTypeDef = TypedDict(
     "DescribeDeviceEc2InputRequestTypeDef",
     {
         "instanceIds": Sequence[str],
         "managedDeviceId": str,
     },
 )
@@ -171,21 +177,50 @@
     "DescribeExecutionInputRequestTypeDef",
     {
         "managedDeviceId": str,
         "taskId": str,
     },
 )
 
+DescribeExecutionOutputTypeDef = TypedDict(
+    "DescribeExecutionOutputTypeDef",
+    {
+        "executionId": str,
+        "lastUpdatedAt": datetime,
+        "managedDeviceId": str,
+        "startedAt": datetime,
+        "state": ExecutionStateType,
+        "taskId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeTaskInputRequestTypeDef = TypedDict(
     "DescribeTaskInputRequestTypeDef",
     {
         "taskId": str,
     },
 )
 
+DescribeTaskOutputTypeDef = TypedDict(
+    "DescribeTaskOutputTypeDef",
+    {
+        "completedAt": datetime,
+        "createdAt": datetime,
+        "description": str,
+        "lastUpdatedAt": datetime,
+        "state": TaskStateType,
+        "tags": Dict[str, str],
+        "targets": List[str],
+        "taskArn": str,
+        "taskId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeviceSummaryTypeDef = TypedDict(
     "DeviceSummaryTypeDef",
     {
         "associatedWithJob": str,
         "managedDeviceArn": str,
         "managedDeviceId": str,
         "tags": Dict[str, str],
@@ -200,14 +235,21 @@
         "deleteOnTermination": bool,
         "status": AttachmentStatusType,
         "volumeId": str,
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
 ExecutionSummaryTypeDef = TypedDict(
     "ExecutionSummaryTypeDef",
     {
         "executionId": str,
         "managedDeviceId": str,
         "state": ExecutionStateType,
         "taskId": str,
@@ -229,24 +271,37 @@
     {
         "groupId": str,
         "groupName": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListDeviceResourcesInputListDeviceResourcesPaginateTypeDef = TypedDict(
+    "_RequiredListDeviceResourcesInputListDeviceResourcesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "managedDeviceId": str,
+    },
+)
+_OptionalListDeviceResourcesInputListDeviceResourcesPaginateTypeDef = TypedDict(
+    "_OptionalListDeviceResourcesInputListDeviceResourcesPaginateTypeDef",
+    {
+        "type": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListDeviceResourcesInputListDeviceResourcesPaginateTypeDef(
+    _RequiredListDeviceResourcesInputListDeviceResourcesPaginateTypeDef,
+    _OptionalListDeviceResourcesInputListDeviceResourcesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListDeviceResourcesInputRequestTypeDef = TypedDict(
     "_RequiredListDeviceResourcesInputRequestTypeDef",
     {
         "managedDeviceId": str,
     },
 )
 _OptionalListDeviceResourcesInputRequestTypeDef = TypedDict(
@@ -282,24 +337,56 @@
 )
 
 
 class ResourceSummaryTypeDef(_RequiredResourceSummaryTypeDef, _OptionalResourceSummaryTypeDef):
     pass
 
 
+ListDevicesInputListDevicesPaginateTypeDef = TypedDict(
+    "ListDevicesInputListDevicesPaginateTypeDef",
+    {
+        "jobId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDevicesInputRequestTypeDef = TypedDict(
     "ListDevicesInputRequestTypeDef",
     {
         "jobId": str,
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+_RequiredListExecutionsInputListExecutionsPaginateTypeDef = TypedDict(
+    "_RequiredListExecutionsInputListExecutionsPaginateTypeDef",
+    {
+        "taskId": str,
+    },
+)
+_OptionalListExecutionsInputListExecutionsPaginateTypeDef = TypedDict(
+    "_OptionalListExecutionsInputListExecutionsPaginateTypeDef",
+    {
+        "state": ExecutionStateType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListExecutionsInputListExecutionsPaginateTypeDef(
+    _RequiredListExecutionsInputListExecutionsPaginateTypeDef,
+    _OptionalListExecutionsInputListExecutionsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListExecutionsInputRequestTypeDef = TypedDict(
     "_RequiredListExecutionsInputRequestTypeDef",
     {
         "taskId": str,
     },
 )
 _OptionalListExecutionsInputRequestTypeDef = TypedDict(
@@ -322,14 +409,31 @@
 ListTagsForResourceInputRequestTypeDef = TypedDict(
     "ListTagsForResourceInputRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
+ListTagsForResourceOutputTypeDef = TypedDict(
+    "ListTagsForResourceOutputTypeDef",
+    {
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListTasksInputListTasksPaginateTypeDef = TypedDict(
+    "ListTasksInputListTasksPaginateTypeDef",
+    {
+        "state": TaskStateType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListTasksInputRequestTypeDef = TypedDict(
     "ListTasksInputRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
         "state": TaskStateType,
     },
@@ -353,88 +457,48 @@
 )
 
 
 class TaskSummaryTypeDef(_RequiredTaskSummaryTypeDef, _OptionalTaskSummaryTypeDef):
     pass
 
 
-TagResourceInputRequestTypeDef = TypedDict(
-    "TagResourceInputRequestTypeDef",
-    {
-        "resourceArn": str,
-        "tags": Mapping[str, str],
-    },
-)
-
-UntagResourceInputRequestTypeDef = TypedDict(
-    "UntagResourceInputRequestTypeDef",
-    {
-        "resourceArn": str,
-        "tagKeys": Sequence[str],
-    },
-)
-
-CancelTaskOutputTypeDef = TypedDict(
-    "CancelTaskOutputTypeDef",
-    {
-        "taskId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateTaskOutputTypeDef = TypedDict(
-    "CreateTaskOutputTypeDef",
-    {
-        "taskArn": str,
-        "taskId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeExecutionOutputTypeDef = TypedDict(
-    "DescribeExecutionOutputTypeDef",
+PaginatorConfigTypeDef = TypedDict(
+    "PaginatorConfigTypeDef",
     {
-        "executionId": str,
-        "lastUpdatedAt": datetime,
-        "managedDeviceId": str,
-        "startedAt": datetime,
-        "state": ExecutionStateType,
-        "taskId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "MaxItems": int,
+        "PageSize": int,
+        "StartingToken": str,
     },
+    total=False,
 )
 
-DescribeTaskOutputTypeDef = TypedDict(
-    "DescribeTaskOutputTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "completedAt": datetime,
-        "createdAt": datetime,
-        "description": str,
-        "lastUpdatedAt": datetime,
-        "state": TaskStateType,
-        "tags": Dict[str, str],
-        "targets": List[str],
-        "taskArn": str,
-        "taskId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
+TagResourceInputRequestTypeDef = TypedDict(
+    "TagResourceInputRequestTypeDef",
     {
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "resourceArn": str,
+        "tags": Mapping[str, str],
     },
 )
 
-ListTagsForResourceOutputTypeDef = TypedDict(
-    "ListTagsForResourceOutputTypeDef",
+UntagResourceInputRequestTypeDef = TypedDict(
+    "UntagResourceInputRequestTypeDef",
     {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "resourceArn": str,
+        "tagKeys": Sequence[str],
     },
 )
 
 _RequiredCreateTaskInputRequestTypeDef = TypedDict(
     "_RequiredCreateTaskInputRequestTypeDef",
     {
         "command": CommandTypeDef,
@@ -468,24 +532,24 @@
         "lastReachedOutAt": datetime,
         "lastUpdatedAt": datetime,
         "managedDeviceArn": str,
         "managedDeviceId": str,
         "physicalNetworkInterfaces": List[PhysicalNetworkInterfaceTypeDef],
         "software": SoftwareInformationTypeDef,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDevicesOutputTypeDef = TypedDict(
     "ListDevicesOutputTypeDef",
     {
         "devices": List[DeviceSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InstanceBlockDeviceMappingTypeDef = TypedDict(
     "InstanceBlockDeviceMappingTypeDef",
     {
         "deviceName": str,
@@ -495,97 +559,33 @@
 )
 
 ListExecutionsOutputTypeDef = TypedDict(
     "ListExecutionsOutputTypeDef",
     {
         "executions": List[ExecutionSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-_RequiredListDeviceResourcesInputListDeviceResourcesPaginateTypeDef = TypedDict(
-    "_RequiredListDeviceResourcesInputListDeviceResourcesPaginateTypeDef",
-    {
-        "managedDeviceId": str,
-    },
-)
-_OptionalListDeviceResourcesInputListDeviceResourcesPaginateTypeDef = TypedDict(
-    "_OptionalListDeviceResourcesInputListDeviceResourcesPaginateTypeDef",
-    {
-        "type": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListDeviceResourcesInputListDeviceResourcesPaginateTypeDef(
-    _RequiredListDeviceResourcesInputListDeviceResourcesPaginateTypeDef,
-    _OptionalListDeviceResourcesInputListDeviceResourcesPaginateTypeDef,
-):
-    pass
-
-
-ListDevicesInputListDevicesPaginateTypeDef = TypedDict(
-    "ListDevicesInputListDevicesPaginateTypeDef",
-    {
-        "jobId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListExecutionsInputListExecutionsPaginateTypeDef = TypedDict(
-    "_RequiredListExecutionsInputListExecutionsPaginateTypeDef",
-    {
-        "taskId": str,
-    },
-)
-_OptionalListExecutionsInputListExecutionsPaginateTypeDef = TypedDict(
-    "_OptionalListExecutionsInputListExecutionsPaginateTypeDef",
-    {
-        "state": ExecutionStateType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListExecutionsInputListExecutionsPaginateTypeDef(
-    _RequiredListExecutionsInputListExecutionsPaginateTypeDef,
-    _OptionalListExecutionsInputListExecutionsPaginateTypeDef,
-):
-    pass
-
-
-ListTasksInputListTasksPaginateTypeDef = TypedDict(
-    "ListTasksInputListTasksPaginateTypeDef",
-    {
-        "state": TaskStateType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListDeviceResourcesOutputTypeDef = TypedDict(
     "ListDeviceResourcesOutputTypeDef",
     {
         "nextToken": str,
         "resources": List[ResourceSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTasksOutputTypeDef = TypedDict(
     "ListTasksOutputTypeDef",
     {
         "nextToken": str,
         "tasks": List[TaskSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InstanceTypeDef = TypedDict(
     "InstanceTypeDef",
     {
         "amiLaunchIndex": int,
@@ -614,10 +614,10 @@
     total=False,
 )
 
 DescribeDeviceEc2OutputTypeDef = TypedDict(
     "DescribeDeviceEc2OutputTypeDef",
     {
         "instances": List[InstanceSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-snow-device-management-2.5.0.post1/types_aiobotocore_snow_device_management/type_defs.pyi` & `types-aiobotocore-snow-device-management-2.5.1/types_aiobotocore_snow_device_management/type_defs.pyi`

 * *Files 1% similar despite different names*

```diff
@@ -28,76 +28,73 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "CancelTaskInputRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CancelTaskOutputTypeDef",
     "CapacityTypeDef",
     "CommandTypeDef",
     "CpuOptionsTypeDef",
+    "CreateTaskOutputTypeDef",
     "DescribeDeviceEc2InputRequestTypeDef",
     "DescribeDeviceInputRequestTypeDef",
     "PhysicalNetworkInterfaceTypeDef",
     "SoftwareInformationTypeDef",
     "DescribeExecutionInputRequestTypeDef",
+    "DescribeExecutionOutputTypeDef",
     "DescribeTaskInputRequestTypeDef",
+    "DescribeTaskOutputTypeDef",
     "DeviceSummaryTypeDef",
     "EbsInstanceBlockDeviceTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "ExecutionSummaryTypeDef",
     "InstanceStateTypeDef",
     "SecurityGroupIdentifierTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListDeviceResourcesInputListDeviceResourcesPaginateTypeDef",
     "ListDeviceResourcesInputRequestTypeDef",
     "ResourceSummaryTypeDef",
+    "ListDevicesInputListDevicesPaginateTypeDef",
     "ListDevicesInputRequestTypeDef",
+    "ListExecutionsInputListExecutionsPaginateTypeDef",
     "ListExecutionsInputRequestTypeDef",
     "ListTagsForResourceInputRequestTypeDef",
+    "ListTagsForResourceOutputTypeDef",
+    "ListTasksInputListTasksPaginateTypeDef",
     "ListTasksInputRequestTypeDef",
     "TaskSummaryTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceInputRequestTypeDef",
     "UntagResourceInputRequestTypeDef",
-    "CancelTaskOutputTypeDef",
-    "CreateTaskOutputTypeDef",
-    "DescribeExecutionOutputTypeDef",
-    "DescribeTaskOutputTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "ListTagsForResourceOutputTypeDef",
     "CreateTaskInputRequestTypeDef",
     "DescribeDeviceOutputTypeDef",
     "ListDevicesOutputTypeDef",
     "InstanceBlockDeviceMappingTypeDef",
     "ListExecutionsOutputTypeDef",
-    "ListDeviceResourcesInputListDeviceResourcesPaginateTypeDef",
-    "ListDevicesInputListDevicesPaginateTypeDef",
-    "ListExecutionsInputListExecutionsPaginateTypeDef",
-    "ListTasksInputListTasksPaginateTypeDef",
     "ListDeviceResourcesOutputTypeDef",
     "ListTasksOutputTypeDef",
     "InstanceTypeDef",
     "InstanceSummaryTypeDef",
     "DescribeDeviceEc2OutputTypeDef",
 )
 
 CancelTaskInputRequestTypeDef = TypedDict(
     "CancelTaskInputRequestTypeDef",
     {
         "taskId": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CancelTaskOutputTypeDef = TypedDict(
+    "CancelTaskOutputTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "taskId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CapacityTypeDef = TypedDict(
     "CapacityTypeDef",
     {
         "available": int,
@@ -123,14 +120,23 @@
     {
         "coreCount": int,
         "threadsPerCore": int,
     },
     total=False,
 )
 
+CreateTaskOutputTypeDef = TypedDict(
+    "CreateTaskOutputTypeDef",
+    {
+        "taskArn": str,
+        "taskId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeDeviceEc2InputRequestTypeDef = TypedDict(
     "DescribeDeviceEc2InputRequestTypeDef",
     {
         "instanceIds": Sequence[str],
         "managedDeviceId": str,
     },
 )
@@ -170,21 +176,50 @@
     "DescribeExecutionInputRequestTypeDef",
     {
         "managedDeviceId": str,
         "taskId": str,
     },
 )
 
+DescribeExecutionOutputTypeDef = TypedDict(
+    "DescribeExecutionOutputTypeDef",
+    {
+        "executionId": str,
+        "lastUpdatedAt": datetime,
+        "managedDeviceId": str,
+        "startedAt": datetime,
+        "state": ExecutionStateType,
+        "taskId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DescribeTaskInputRequestTypeDef = TypedDict(
     "DescribeTaskInputRequestTypeDef",
     {
         "taskId": str,
     },
 )
 
+DescribeTaskOutputTypeDef = TypedDict(
+    "DescribeTaskOutputTypeDef",
+    {
+        "completedAt": datetime,
+        "createdAt": datetime,
+        "description": str,
+        "lastUpdatedAt": datetime,
+        "state": TaskStateType,
+        "tags": Dict[str, str],
+        "targets": List[str],
+        "taskArn": str,
+        "taskId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeviceSummaryTypeDef = TypedDict(
     "DeviceSummaryTypeDef",
     {
         "associatedWithJob": str,
         "managedDeviceArn": str,
         "managedDeviceId": str,
         "tags": Dict[str, str],
@@ -199,14 +234,21 @@
         "deleteOnTermination": bool,
         "status": AttachmentStatusType,
         "volumeId": str,
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
 ExecutionSummaryTypeDef = TypedDict(
     "ExecutionSummaryTypeDef",
     {
         "executionId": str,
         "managedDeviceId": str,
         "state": ExecutionStateType,
         "taskId": str,
@@ -228,24 +270,35 @@
     {
         "groupId": str,
         "groupName": str,
     },
     total=False,
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListDeviceResourcesInputListDeviceResourcesPaginateTypeDef = TypedDict(
+    "_RequiredListDeviceResourcesInputListDeviceResourcesPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "managedDeviceId": str,
+    },
+)
+_OptionalListDeviceResourcesInputListDeviceResourcesPaginateTypeDef = TypedDict(
+    "_OptionalListDeviceResourcesInputListDeviceResourcesPaginateTypeDef",
+    {
+        "type": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListDeviceResourcesInputListDeviceResourcesPaginateTypeDef(
+    _RequiredListDeviceResourcesInputListDeviceResourcesPaginateTypeDef,
+    _OptionalListDeviceResourcesInputListDeviceResourcesPaginateTypeDef,
+):
+    pass
+
 _RequiredListDeviceResourcesInputRequestTypeDef = TypedDict(
     "_RequiredListDeviceResourcesInputRequestTypeDef",
     {
         "managedDeviceId": str,
     },
 )
 _OptionalListDeviceResourcesInputRequestTypeDef = TypedDict(
@@ -277,24 +330,54 @@
     },
     total=False,
 )
 
 class ResourceSummaryTypeDef(_RequiredResourceSummaryTypeDef, _OptionalResourceSummaryTypeDef):
     pass
 
+ListDevicesInputListDevicesPaginateTypeDef = TypedDict(
+    "ListDevicesInputListDevicesPaginateTypeDef",
+    {
+        "jobId": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDevicesInputRequestTypeDef = TypedDict(
     "ListDevicesInputRequestTypeDef",
     {
         "jobId": str,
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
 )
 
+_RequiredListExecutionsInputListExecutionsPaginateTypeDef = TypedDict(
+    "_RequiredListExecutionsInputListExecutionsPaginateTypeDef",
+    {
+        "taskId": str,
+    },
+)
+_OptionalListExecutionsInputListExecutionsPaginateTypeDef = TypedDict(
+    "_OptionalListExecutionsInputListExecutionsPaginateTypeDef",
+    {
+        "state": ExecutionStateType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListExecutionsInputListExecutionsPaginateTypeDef(
+    _RequiredListExecutionsInputListExecutionsPaginateTypeDef,
+    _OptionalListExecutionsInputListExecutionsPaginateTypeDef,
+):
+    pass
+
 _RequiredListExecutionsInputRequestTypeDef = TypedDict(
     "_RequiredListExecutionsInputRequestTypeDef",
     {
         "taskId": str,
     },
 )
 _OptionalListExecutionsInputRequestTypeDef = TypedDict(
@@ -315,14 +398,31 @@
 ListTagsForResourceInputRequestTypeDef = TypedDict(
     "ListTagsForResourceInputRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
+ListTagsForResourceOutputTypeDef = TypedDict(
+    "ListTagsForResourceOutputTypeDef",
+    {
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+ListTasksInputListTasksPaginateTypeDef = TypedDict(
+    "ListTasksInputListTasksPaginateTypeDef",
+    {
+        "state": TaskStateType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListTasksInputRequestTypeDef = TypedDict(
     "ListTasksInputRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
         "state": TaskStateType,
     },
@@ -344,88 +444,48 @@
     },
     total=False,
 )
 
 class TaskSummaryTypeDef(_RequiredTaskSummaryTypeDef, _OptionalTaskSummaryTypeDef):
     pass
 
-TagResourceInputRequestTypeDef = TypedDict(
-    "TagResourceInputRequestTypeDef",
-    {
-        "resourceArn": str,
-        "tags": Mapping[str, str],
-    },
-)
-
-UntagResourceInputRequestTypeDef = TypedDict(
-    "UntagResourceInputRequestTypeDef",
-    {
-        "resourceArn": str,
-        "tagKeys": Sequence[str],
-    },
-)
-
-CancelTaskOutputTypeDef = TypedDict(
-    "CancelTaskOutputTypeDef",
-    {
-        "taskId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateTaskOutputTypeDef = TypedDict(
-    "CreateTaskOutputTypeDef",
-    {
-        "taskArn": str,
-        "taskId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-DescribeExecutionOutputTypeDef = TypedDict(
-    "DescribeExecutionOutputTypeDef",
+PaginatorConfigTypeDef = TypedDict(
+    "PaginatorConfigTypeDef",
     {
-        "executionId": str,
-        "lastUpdatedAt": datetime,
-        "managedDeviceId": str,
-        "startedAt": datetime,
-        "state": ExecutionStateType,
-        "taskId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "MaxItems": int,
+        "PageSize": int,
+        "StartingToken": str,
     },
+    total=False,
 )
 
-DescribeTaskOutputTypeDef = TypedDict(
-    "DescribeTaskOutputTypeDef",
+ResponseMetadataTypeDef = TypedDict(
+    "ResponseMetadataTypeDef",
     {
-        "completedAt": datetime,
-        "createdAt": datetime,
-        "description": str,
-        "lastUpdatedAt": datetime,
-        "state": TaskStateType,
-        "tags": Dict[str, str],
-        "targets": List[str],
-        "taskArn": str,
-        "taskId": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "RequestId": str,
+        "HostId": str,
+        "HTTPStatusCode": int,
+        "HTTPHeaders": Dict[str, str],
+        "RetryAttempts": int,
     },
 )
 
-EmptyResponseMetadataTypeDef = TypedDict(
-    "EmptyResponseMetadataTypeDef",
+TagResourceInputRequestTypeDef = TypedDict(
+    "TagResourceInputRequestTypeDef",
     {
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "resourceArn": str,
+        "tags": Mapping[str, str],
     },
 )
 
-ListTagsForResourceOutputTypeDef = TypedDict(
-    "ListTagsForResourceOutputTypeDef",
+UntagResourceInputRequestTypeDef = TypedDict(
+    "UntagResourceInputRequestTypeDef",
     {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "resourceArn": str,
+        "tagKeys": Sequence[str],
     },
 )
 
 _RequiredCreateTaskInputRequestTypeDef = TypedDict(
     "_RequiredCreateTaskInputRequestTypeDef",
     {
         "command": CommandTypeDef,
@@ -457,24 +517,24 @@
         "lastReachedOutAt": datetime,
         "lastUpdatedAt": datetime,
         "managedDeviceArn": str,
         "managedDeviceId": str,
         "physicalNetworkInterfaces": List[PhysicalNetworkInterfaceTypeDef],
         "software": SoftwareInformationTypeDef,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDevicesOutputTypeDef = TypedDict(
     "ListDevicesOutputTypeDef",
     {
         "devices": List[DeviceSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InstanceBlockDeviceMappingTypeDef = TypedDict(
     "InstanceBlockDeviceMappingTypeDef",
     {
         "deviceName": str,
@@ -484,93 +544,33 @@
 )
 
 ListExecutionsOutputTypeDef = TypedDict(
     "ListExecutionsOutputTypeDef",
     {
         "executions": List[ExecutionSummaryTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredListDeviceResourcesInputListDeviceResourcesPaginateTypeDef = TypedDict(
-    "_RequiredListDeviceResourcesInputListDeviceResourcesPaginateTypeDef",
-    {
-        "managedDeviceId": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalListDeviceResourcesInputListDeviceResourcesPaginateTypeDef = TypedDict(
-    "_OptionalListDeviceResourcesInputListDeviceResourcesPaginateTypeDef",
-    {
-        "type": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListDeviceResourcesInputListDeviceResourcesPaginateTypeDef(
-    _RequiredListDeviceResourcesInputListDeviceResourcesPaginateTypeDef,
-    _OptionalListDeviceResourcesInputListDeviceResourcesPaginateTypeDef,
-):
-    pass
-
-ListDevicesInputListDevicesPaginateTypeDef = TypedDict(
-    "ListDevicesInputListDevicesPaginateTypeDef",
-    {
-        "jobId": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListExecutionsInputListExecutionsPaginateTypeDef = TypedDict(
-    "_RequiredListExecutionsInputListExecutionsPaginateTypeDef",
-    {
-        "taskId": str,
-    },
-)
-_OptionalListExecutionsInputListExecutionsPaginateTypeDef = TypedDict(
-    "_OptionalListExecutionsInputListExecutionsPaginateTypeDef",
-    {
-        "state": ExecutionStateType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListExecutionsInputListExecutionsPaginateTypeDef(
-    _RequiredListExecutionsInputListExecutionsPaginateTypeDef,
-    _OptionalListExecutionsInputListExecutionsPaginateTypeDef,
-):
-    pass
-
-ListTasksInputListTasksPaginateTypeDef = TypedDict(
-    "ListTasksInputListTasksPaginateTypeDef",
-    {
-        "state": TaskStateType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
 
 ListDeviceResourcesOutputTypeDef = TypedDict(
     "ListDeviceResourcesOutputTypeDef",
     {
         "nextToken": str,
         "resources": List[ResourceSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListTasksOutputTypeDef = TypedDict(
     "ListTasksOutputTypeDef",
     {
         "nextToken": str,
         "tasks": List[TaskSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 InstanceTypeDef = TypedDict(
     "InstanceTypeDef",
     {
         "amiLaunchIndex": int,
@@ -599,10 +599,10 @@
     total=False,
 )
 
 DescribeDeviceEc2OutputTypeDef = TypedDict(
     "DescribeDeviceEc2OutputTypeDef",
     {
         "instances": List[InstanceSummaryTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-snow-device-management-2.5.0.post1/types_aiobotocore_snow_device_management.egg-info/PKG-INFO` & `types-aiobotocore-snow-device-management-2.5.1/types_aiobotocore_snow_device_management.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-snow-device-management
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.SnowDeviceManagement 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.SnowDeviceManagement 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snow_device_management/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-snow-device-management"></a>
 
 # types-aiobotocore-snow-device-management
 
 [![PyPI - types-aiobotocore-snow-device-management](https://img.shields.io/pypi/v/types-aiobotocore-snow-device-management.svg?color=blue)](https://pypi.org/project/types-aiobotocore-snow-device-management)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-snow-device-management.svg?color=blue)](https://pypi.org/project/types-aiobotocore-snow-device-management)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snow_device_management/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-snow-device-management?color=blue)](https://pypistats.org/packages/types-aiobotocore-snow-device-management)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.SnowDeviceManagement 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snow-device-management.html#SnowDeviceManagement)
+[aiobotocore.SnowDeviceManagement 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/snow-device-management.html#SnowDeviceManagement)
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
 [types-aiobotocore-snow-device-management docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_snow_device_management/).
 
 See how it helps to find and fix potential bugs:
 
@@ -334,54 +334,54 @@
 
 `types_aiobotocore_snow_device_management.type_defs` module contains structures
 and shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_snow_device_management.type_defs import (
     CancelTaskInputRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CancelTaskOutputTypeDef,
     CapacityTypeDef,
     CommandTypeDef,
     CpuOptionsTypeDef,
+    CreateTaskOutputTypeDef,
     DescribeDeviceEc2InputRequestTypeDef,
     DescribeDeviceInputRequestTypeDef,
     PhysicalNetworkInterfaceTypeDef,
     SoftwareInformationTypeDef,
     DescribeExecutionInputRequestTypeDef,
+    DescribeExecutionOutputTypeDef,
     DescribeTaskInputRequestTypeDef,
+    DescribeTaskOutputTypeDef,
     DeviceSummaryTypeDef,
     EbsInstanceBlockDeviceTypeDef,
+    EmptyResponseMetadataTypeDef,
     ExecutionSummaryTypeDef,
     InstanceStateTypeDef,
     SecurityGroupIdentifierTypeDef,
-    PaginatorConfigTypeDef,
+    ListDeviceResourcesInputListDeviceResourcesPaginateTypeDef,
     ListDeviceResourcesInputRequestTypeDef,
     ResourceSummaryTypeDef,
+    ListDevicesInputListDevicesPaginateTypeDef,
     ListDevicesInputRequestTypeDef,
+    ListExecutionsInputListExecutionsPaginateTypeDef,
     ListExecutionsInputRequestTypeDef,
     ListTagsForResourceInputRequestTypeDef,
+    ListTagsForResourceOutputTypeDef,
+    ListTasksInputListTasksPaginateTypeDef,
     ListTasksInputRequestTypeDef,
     TaskSummaryTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceInputRequestTypeDef,
     UntagResourceInputRequestTypeDef,
-    CancelTaskOutputTypeDef,
-    CreateTaskOutputTypeDef,
-    DescribeExecutionOutputTypeDef,
-    DescribeTaskOutputTypeDef,
-    EmptyResponseMetadataTypeDef,
-    ListTagsForResourceOutputTypeDef,
     CreateTaskInputRequestTypeDef,
     DescribeDeviceOutputTypeDef,
     ListDevicesOutputTypeDef,
     InstanceBlockDeviceMappingTypeDef,
     ListExecutionsOutputTypeDef,
-    ListDeviceResourcesInputListDeviceResourcesPaginateTypeDef,
-    ListDevicesInputListDevicesPaginateTypeDef,
-    ListExecutionsInputListExecutionsPaginateTypeDef,
-    ListTasksInputListTasksPaginateTypeDef,
     ListDeviceResourcesOutputTypeDef,
     ListTasksOutputTypeDef,
     InstanceTypeDef,
     InstanceSummaryTypeDef,
     DescribeDeviceEc2OutputTypeDef,
 )
 
@@ -393,43 +393,43 @@
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

### Comparing `types-aiobotocore-snow-device-management-2.5.0.post1/types_aiobotocore_snow_device_management.egg-info/SOURCES.txt` & `types-aiobotocore-snow-device-management-2.5.1/types_aiobotocore_snow_device_management.egg-info/SOURCES.txt`

 * *Files identical despite different names*

