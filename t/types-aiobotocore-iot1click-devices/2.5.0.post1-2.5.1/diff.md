# Comparing `tmp/types-aiobotocore-iot1click-devices-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-iot1click-devices-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-iot1click-devices-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:44 2023, max compression
+gzip compressed data, was "types-aiobotocore-iot1click-devices-2.5.1.tar", last modified: Wed Jun 28 01:43:36 2023, max compression
```

## Comparing `types-aiobotocore-iot1click-devices-2.5.0.post1.tar` & `types-aiobotocore-iot1click-devices-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:44.591276 types-aiobotocore-iot1click-devices-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:16:12.000000 types-aiobotocore-iot1click-devices-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    14829 2023-03-11 12:26:44.583276 types-aiobotocore-iot1click-devices-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13212 2023-03-11 12:16:12.000000 types-aiobotocore-iot1click-devices-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:44.591276 types-aiobotocore-iot1click-devices-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2216 2023-03-11 12:16:12.000000 types-aiobotocore-iot1click-devices-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:44.583276 types-aiobotocore-iot1click-devices-2.5.0.post1/types_aiobotocore_iot1click_devices/
--rw-r--r--   0 runner    (1001) docker     (123)      954 2023-03-11 12:16:12.000000 types-aiobotocore-iot1click-devices-2.5.0.post1/types_aiobotocore_iot1click_devices/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      953 2023-03-11 12:16:12.000000 types-aiobotocore-iot1click-devices-2.5.0.post1/types_aiobotocore_iot1click_devices/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      995 2023-03-11 12:16:12.000000 types-aiobotocore-iot1click-devices-2.5.0.post1/types_aiobotocore_iot1click_devices/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    14023 2023-03-11 12:16:12.000000 types-aiobotocore-iot1click-devices-2.5.0.post1/types_aiobotocore_iot1click_devices/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    13999 2023-03-11 12:16:12.000000 types-aiobotocore-iot1click-devices-2.5.0.post1/types_aiobotocore_iot1click_devices/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7681 2023-03-11 12:16:12.000000 types-aiobotocore-iot1click-devices-2.5.0.post1/types_aiobotocore_iot1click_devices/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     7679 2023-03-11 12:16:12.000000 types-aiobotocore-iot1click-devices-2.5.0.post1/types_aiobotocore_iot1click_devices/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     3568 2023-03-11 12:16:12.000000 types-aiobotocore-iot1click-devices-2.5.0.post1/types_aiobotocore_iot1click_devices/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     3563 2023-03-11 12:16:12.000000 types-aiobotocore-iot1click-devices-2.5.0.post1/types_aiobotocore_iot1click_devices/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:16:12.000000 types-aiobotocore-iot1click-devices-2.5.0.post1/types_aiobotocore_iot1click_devices/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)     9733 2023-03-11 12:16:12.000000 types-aiobotocore-iot1click-devices-2.5.0.post1/types_aiobotocore_iot1click_devices/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)     9722 2023-03-11 12:16:12.000000 types-aiobotocore-iot1click-devices-2.5.0.post1/types_aiobotocore_iot1click_devices/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:16:12.000000 types-aiobotocore-iot1click-devices-2.5.0.post1/types_aiobotocore_iot1click_devices/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:44.583276 types-aiobotocore-iot1click-devices-2.5.0.post1/types_aiobotocore_iot1click_devices.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    14829 2023-03-11 12:26:44.000000 types-aiobotocore-iot1click-devices-2.5.0.post1/types_aiobotocore_iot1click_devices.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1003 2023-03-11 12:26:44.000000 types-aiobotocore-iot1click-devices-2.5.0.post1/types_aiobotocore_iot1click_devices.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:44.000000 types-aiobotocore-iot1click-devices-2.5.0.post1/types_aiobotocore_iot1click_devices.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:44.000000 types-aiobotocore-iot1click-devices-2.5.0.post1/types_aiobotocore_iot1click_devices.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:44.000000 types-aiobotocore-iot1click-devices-2.5.0.post1/types_aiobotocore_iot1click_devices.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       36 2023-03-11 12:26:44.000000 types-aiobotocore-iot1click-devices-2.5.0.post1/types_aiobotocore_iot1click_devices.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:36.326149 types-aiobotocore-iot1click-devices-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:32:50.000000 types-aiobotocore-iot1click-devices-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    14831 2023-06-28 01:43:36.326149 types-aiobotocore-iot1click-devices-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13220 2023-06-28 01:32:50.000000 types-aiobotocore-iot1click-devices-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:36.326149 types-aiobotocore-iot1click-devices-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2210 2023-06-28 01:32:50.000000 types-aiobotocore-iot1click-devices-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:36.326149 types-aiobotocore-iot1click-devices-2.5.1/types_aiobotocore_iot1click_devices/
+-rw-r--r--   0 runner    (1001) docker     (123)      954 2023-06-28 01:32:50.000000 types-aiobotocore-iot1click-devices-2.5.1/types_aiobotocore_iot1click_devices/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      953 2023-06-28 01:32:50.000000 types-aiobotocore-iot1click-devices-2.5.1/types_aiobotocore_iot1click_devices/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      983 2023-06-28 01:32:50.000000 types-aiobotocore-iot1click-devices-2.5.1/types_aiobotocore_iot1click_devices/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14023 2023-06-28 01:32:50.000000 types-aiobotocore-iot1click-devices-2.5.1/types_aiobotocore_iot1click_devices/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13999 2023-06-28 01:32:50.000000 types-aiobotocore-iot1click-devices-2.5.1/types_aiobotocore_iot1click_devices/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     7890 2023-06-28 01:32:50.000000 types-aiobotocore-iot1click-devices-2.5.1/types_aiobotocore_iot1click_devices/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7888 2023-06-28 01:32:50.000000 types-aiobotocore-iot1click-devices-2.5.1/types_aiobotocore_iot1click_devices/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     3452 2023-06-28 01:32:50.000000 types-aiobotocore-iot1click-devices-2.5.1/types_aiobotocore_iot1click_devices/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3448 2023-06-28 01:32:50.000000 types-aiobotocore-iot1click-devices-2.5.1/types_aiobotocore_iot1click_devices/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:32:50.000000 types-aiobotocore-iot1click-devices-2.5.1/types_aiobotocore_iot1click_devices/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     9759 2023-06-28 01:32:50.000000 types-aiobotocore-iot1click-devices-2.5.1/types_aiobotocore_iot1click_devices/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9748 2023-06-28 01:32:50.000000 types-aiobotocore-iot1click-devices-2.5.1/types_aiobotocore_iot1click_devices/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:32:50.000000 types-aiobotocore-iot1click-devices-2.5.1/types_aiobotocore_iot1click_devices/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:36.326149 types-aiobotocore-iot1click-devices-2.5.1/types_aiobotocore_iot1click_devices.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    14831 2023-06-28 01:43:36.000000 types-aiobotocore-iot1click-devices-2.5.1/types_aiobotocore_iot1click_devices.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1003 2023-06-28 01:43:36.000000 types-aiobotocore-iot1click-devices-2.5.1/types_aiobotocore_iot1click_devices.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:36.000000 types-aiobotocore-iot1click-devices-2.5.1/types_aiobotocore_iot1click_devices.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:36.000000 types-aiobotocore-iot1click-devices-2.5.1/types_aiobotocore_iot1click_devices.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:36.000000 types-aiobotocore-iot1click-devices-2.5.1/types_aiobotocore_iot1click_devices.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       36 2023-06-28 01:43:36.000000 types-aiobotocore-iot1click-devices-2.5.1/types_aiobotocore_iot1click_devices.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-iot1click-devices-2.5.0.post1/LICENSE` & `types-aiobotocore-iot1click-devices-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-iot1click-devices-2.5.0.post1/PKG-INFO` & `types-aiobotocore-iot1click-devices-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-iot1click-devices
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.IoT1ClickDevicesService 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.IoT1ClickDevicesService 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot1click_devices/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-iot1click-devices"></a>
 
 # types-aiobotocore-iot1click-devices
 
 [![PyPI - types-aiobotocore-iot1click-devices](https://img.shields.io/pypi/v/types-aiobotocore-iot1click-devices.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iot1click-devices)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iot1click-devices.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iot1click-devices)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot1click_devices/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iot1click-devices?color=blue)](https://pypistats.org/packages/types-aiobotocore-iot1click-devices)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoT1ClickDevicesService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot1click-devices.html#IoT1ClickDevicesService)
+[aiobotocore.IoT1ClickDevicesService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot1click-devices.html#IoT1ClickDevicesService)
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
 [types-aiobotocore-iot1click-devices docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot1click_devices/).
 
 See how it helps to find and fix potential bugs:
 
@@ -321,44 +321,44 @@
 
 `types_aiobotocore_iot1click_devices.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_iot1click_devices.type_defs import (
     ClaimDevicesByClaimCodeRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    ClaimDevicesByClaimCodeResponseTypeDef,
     DescribeDeviceRequestRequestTypeDef,
     DeviceDescriptionTypeDef,
     DeviceTypeDef,
     DeviceMethodTypeDef,
+    EmptyResponseMetadataTypeDef,
     FinalizeDeviceClaimRequestRequestTypeDef,
+    FinalizeDeviceClaimResponseTypeDef,
     GetDeviceMethodsRequestRequestTypeDef,
     InitiateDeviceClaimRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    InitiateDeviceClaimResponseTypeDef,
+    InvokeDeviceMethodResponseTypeDef,
+    ListDeviceEventsRequestListDeviceEventsPaginateTypeDef,
     ListDeviceEventsRequestRequestTypeDef,
+    ListDevicesRequestListDevicesPaginateTypeDef,
     ListDevicesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UnclaimDeviceRequestRequestTypeDef,
+    UnclaimDeviceResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateDeviceStateRequestRequestTypeDef,
-    ClaimDevicesByClaimCodeResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    FinalizeDeviceClaimResponseTypeDef,
-    InitiateDeviceClaimResponseTypeDef,
-    InvokeDeviceMethodResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    UnclaimDeviceResponseTypeDef,
     DescribeDeviceResponseTypeDef,
     ListDevicesResponseTypeDef,
     DeviceEventTypeDef,
     GetDeviceMethodsResponseTypeDef,
     InvokeDeviceMethodRequestRequestTypeDef,
-    ListDeviceEventsRequestListDeviceEventsPaginateTypeDef,
-    ListDevicesRequestListDevicesPaginateTypeDef,
     ListDeviceEventsResponseTypeDef,
 )
 
 
 def get_structure() -> ClaimDevicesByClaimCodeRequestRequestTypeDef:
     return {...}
 ```
@@ -366,43 +366,43 @@
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

### Comparing `types-aiobotocore-iot1click-devices-2.5.0.post1/README.md` & `types-aiobotocore-iot1click-devices-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-iot1click-devices"></a>
 
 # types-aiobotocore-iot1click-devices
 
 [![PyPI - types-aiobotocore-iot1click-devices](https://img.shields.io/pypi/v/types-aiobotocore-iot1click-devices.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iot1click-devices)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iot1click-devices.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iot1click-devices)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot1click_devices/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iot1click-devices?color=blue)](https://pypistats.org/packages/types-aiobotocore-iot1click-devices)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoT1ClickDevicesService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot1click-devices.html#IoT1ClickDevicesService)
+[aiobotocore.IoT1ClickDevicesService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot1click-devices.html#IoT1ClickDevicesService)
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
 [types-aiobotocore-iot1click-devices docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot1click_devices/).
 
 See how it helps to find and fix potential bugs:
 
@@ -288,44 +288,44 @@
 
 `types_aiobotocore_iot1click_devices.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_iot1click_devices.type_defs import (
     ClaimDevicesByClaimCodeRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    ClaimDevicesByClaimCodeResponseTypeDef,
     DescribeDeviceRequestRequestTypeDef,
     DeviceDescriptionTypeDef,
     DeviceTypeDef,
     DeviceMethodTypeDef,
+    EmptyResponseMetadataTypeDef,
     FinalizeDeviceClaimRequestRequestTypeDef,
+    FinalizeDeviceClaimResponseTypeDef,
     GetDeviceMethodsRequestRequestTypeDef,
     InitiateDeviceClaimRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    InitiateDeviceClaimResponseTypeDef,
+    InvokeDeviceMethodResponseTypeDef,
+    ListDeviceEventsRequestListDeviceEventsPaginateTypeDef,
     ListDeviceEventsRequestRequestTypeDef,
+    ListDevicesRequestListDevicesPaginateTypeDef,
     ListDevicesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UnclaimDeviceRequestRequestTypeDef,
+    UnclaimDeviceResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateDeviceStateRequestRequestTypeDef,
-    ClaimDevicesByClaimCodeResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    FinalizeDeviceClaimResponseTypeDef,
-    InitiateDeviceClaimResponseTypeDef,
-    InvokeDeviceMethodResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    UnclaimDeviceResponseTypeDef,
     DescribeDeviceResponseTypeDef,
     ListDevicesResponseTypeDef,
     DeviceEventTypeDef,
     GetDeviceMethodsResponseTypeDef,
     InvokeDeviceMethodRequestRequestTypeDef,
-    ListDeviceEventsRequestListDeviceEventsPaginateTypeDef,
-    ListDevicesRequestListDevicesPaginateTypeDef,
     ListDeviceEventsResponseTypeDef,
 )
 
 
 def get_structure() -> ClaimDevicesByClaimCodeRequestRequestTypeDef:
     return {...}
 ```
@@ -333,43 +333,43 @@
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

### Comparing `types-aiobotocore-iot1click-devices-2.5.0.post1/setup.py` & `types-aiobotocore-iot1click-devices-2.5.1/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-iot1click-devices.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-iot1click-devices",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_iot1click_devices"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.IoT1ClickDevicesService 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.IoT1ClickDevicesService 2.5.1 service generated with"
+        " mypy-boto3-builder 7.14.5"
     ),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
@@ -50,11 +50,11 @@
         "Documentation": (
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot1click_devices/"
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

### Comparing `types-aiobotocore-iot1click-devices-2.5.0.post1/types_aiobotocore_iot1click_devices/__init__.py` & `types-aiobotocore-iot1click-devices-2.5.1/types_aiobotocore_iot1click_devices/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iot1click-devices-2.5.0.post1/types_aiobotocore_iot1click_devices/__init__.pyi` & `types-aiobotocore-iot1click-devices-2.5.1/types_aiobotocore_iot1click_devices/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iot1click-devices-2.5.0.post1/types_aiobotocore_iot1click_devices/__main__.py` & `types-aiobotocore-iot1click-devices-2.5.1/types_aiobotocore_iot1click_devices/__main__.py`

 * *Files 4% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.IoT1ClickDevicesService 2.5.0\nVersion:        "
-        " 2.5.0.post1\nBuilder version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.IoT1ClickDevicesService 2.5.1\nVersion:        "
+        " 2.5.1\nBuilder version: 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot1click_devices//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot1click-devices.html#IoT1ClickDevicesService\nOther"
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

### Comparing `types-aiobotocore-iot1click-devices-2.5.0.post1/types_aiobotocore_iot1click_devices/client.py` & `types-aiobotocore-iot1click-devices-2.5.1/types_aiobotocore_iot1click_devices/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iot1click-devices-2.5.0.post1/types_aiobotocore_iot1click_devices/client.pyi` & `types-aiobotocore-iot1click-devices-2.5.1/types_aiobotocore_iot1click_devices/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iot1click-devices-2.5.0.post1/types_aiobotocore_iot1click_devices/literals.py` & `types-aiobotocore-iot1click-devices-2.5.1/types_aiobotocore_iot1click_devices/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -14,25 +14,23 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
-
 __all__ = (
     "ListDeviceEventsPaginatorName",
     "ListDevicesPaginatorName",
     "IoT1ClickDevicesServiceServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
 )
 
-
 ListDeviceEventsPaginatorName = Literal["list_device_events"]
 ListDevicesPaginatorName = Literal["list_devices"]
 IoT1ClickDevicesServiceServiceName = Literal["iot1click-devices"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
@@ -90,14 +88,15 @@
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
@@ -176,14 +175,15 @@
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
@@ -194,14 +194,15 @@
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
@@ -237,14 +238,15 @@
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
@@ -263,16 +265,19 @@
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
@@ -356,15 +361,17 @@
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

### Comparing `types-aiobotocore-iot1click-devices-2.5.0.post1/types_aiobotocore_iot1click_devices/literals.pyi` & `types-aiobotocore-iot1click-devices-2.5.1/types_aiobotocore_iot1click_devices/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -14,23 +14,25 @@
 import sys
 
 if sys.version_info >= (3, 9):
     from typing import Literal
 else:
     from typing_extensions import Literal
 
+
 __all__ = (
     "ListDeviceEventsPaginatorName",
     "ListDevicesPaginatorName",
     "IoT1ClickDevicesServiceServiceName",
     "ServiceName",
     "ResourceServiceName",
     "PaginatorName",
 )
 
+
 ListDeviceEventsPaginatorName = Literal["list_device_events"]
 ListDevicesPaginatorName = Literal["list_devices"]
 IoT1ClickDevicesServiceServiceName = Literal["iot1click-devices"]
 ServiceName = Literal[
     "accessanalyzer",
     "account",
     "acm",
@@ -88,14 +90,15 @@
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
@@ -174,14 +177,15 @@
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
@@ -192,14 +196,15 @@
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
@@ -235,14 +240,15 @@
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
@@ -261,16 +267,19 @@
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
@@ -354,15 +363,17 @@
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

### Comparing `types-aiobotocore-iot1click-devices-2.5.0.post1/types_aiobotocore_iot1click_devices/paginator.py` & `types-aiobotocore-iot1click-devices-2.5.1/types_aiobotocore_iot1click_devices/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -18,33 +18,26 @@
     with session.create_client("iot1click-devices") as client:
         client: IoT1ClickDevicesServiceClient
 
         list_device_events_paginator: ListDeviceEventsPaginator = client.get_paginator("list_device_events")
         list_devices_paginator: ListDevicesPaginator = client.get_paginator("list_devices")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListDeviceEventsResponseTypeDef,
     ListDevicesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = ("ListDeviceEventsPaginator", "ListDevicesPaginator")
 
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
@@ -62,28 +55,28 @@
 
     def paginate(
         self,
         *,
         DeviceId: str,
         FromTimeStamp: Union[datetime, str],
         ToTimeStamp: Union[datetime, str],
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDeviceEventsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot1click-devices.html#IoT1ClickDevicesService.Paginator.ListDeviceEvents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot1click_devices/paginators/#listdeviceeventspaginator)
         """
 
 
 class ListDevicesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot1click-devices.html#IoT1ClickDevicesService.Paginator.ListDevices)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot1click_devices/paginators/#listdevicespaginator)
     """
 
     def paginate(
-        self, *, DeviceType: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, DeviceType: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDevicesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot1click-devices.html#IoT1ClickDevicesService.Paginator.ListDevices.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot1click_devices/paginators/#listdevicespaginator)
         """
```

### Comparing `types-aiobotocore-iot1click-devices-2.5.0.post1/types_aiobotocore_iot1click_devices/paginator.pyi` & `types-aiobotocore-iot1click-devices-2.5.1/types_aiobotocore_iot1click_devices/paginator.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -18,32 +18,26 @@
     with session.create_client("iot1click-devices") as client:
         client: IoT1ClickDevicesServiceClient
 
         list_device_events_paginator: ListDeviceEventsPaginator = client.get_paginator("list_device_events")
         list_devices_paginator: ListDevicesPaginator = client.get_paginator("list_devices")
     ```
 """
-import sys
 from datetime import datetime
-from typing import Generic, Iterator, TypeVar, Union
+from typing import AsyncIterator, Generic, Iterator, TypeVar, Union
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .type_defs import (
     ListDeviceEventsResponseTypeDef,
     ListDevicesResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = ("ListDeviceEventsPaginator", "ListDevicesPaginator")
 
 _ItemTypeDef = TypeVar("_ItemTypeDef")
 
 class _PageIterator(Generic[_ItemTypeDef], PageIterator):
     def __iter__(self) -> Iterator[_ItemTypeDef]:
         """
@@ -58,27 +52,27 @@
 
     def paginate(
         self,
         *,
         DeviceId: str,
         FromTimeStamp: Union[datetime, str],
         ToTimeStamp: Union[datetime, str],
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDeviceEventsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot1click-devices.html#IoT1ClickDevicesService.Paginator.ListDeviceEvents.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot1click_devices/paginators/#listdeviceeventspaginator)
         """
 
 class ListDevicesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot1click-devices.html#IoT1ClickDevicesService.Paginator.ListDevices)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot1click_devices/paginators/#listdevicespaginator)
     """
 
     def paginate(
-        self, *, DeviceType: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, DeviceType: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDevicesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot1click-devices.html#IoT1ClickDevicesService.Paginator.ListDevices.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot1click_devices/paginators/#listdevicespaginator)
         """
```

### Comparing `types-aiobotocore-iot1click-devices-2.5.0.post1/types_aiobotocore_iot1click_devices/type_defs.py` & `types-aiobotocore-iot1click-devices-2.5.1/types_aiobotocore_iot1click_devices/type_defs.py`

 * *Files 4% similar despite different names*

```diff
@@ -19,62 +19,60 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "ClaimDevicesByClaimCodeRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "ClaimDevicesByClaimCodeResponseTypeDef",
     "DescribeDeviceRequestRequestTypeDef",
     "DeviceDescriptionTypeDef",
     "DeviceTypeDef",
     "DeviceMethodTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "FinalizeDeviceClaimRequestRequestTypeDef",
+    "FinalizeDeviceClaimResponseTypeDef",
     "GetDeviceMethodsRequestRequestTypeDef",
     "InitiateDeviceClaimRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "InitiateDeviceClaimResponseTypeDef",
+    "InvokeDeviceMethodResponseTypeDef",
+    "ListDeviceEventsRequestListDeviceEventsPaginateTypeDef",
     "ListDeviceEventsRequestRequestTypeDef",
+    "ListDevicesRequestListDevicesPaginateTypeDef",
     "ListDevicesRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UnclaimDeviceRequestRequestTypeDef",
+    "UnclaimDeviceResponseTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateDeviceStateRequestRequestTypeDef",
-    "ClaimDevicesByClaimCodeResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "FinalizeDeviceClaimResponseTypeDef",
-    "InitiateDeviceClaimResponseTypeDef",
-    "InvokeDeviceMethodResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "UnclaimDeviceResponseTypeDef",
     "DescribeDeviceResponseTypeDef",
     "ListDevicesResponseTypeDef",
     "DeviceEventTypeDef",
     "GetDeviceMethodsResponseTypeDef",
     "InvokeDeviceMethodRequestRequestTypeDef",
-    "ListDeviceEventsRequestListDeviceEventsPaginateTypeDef",
-    "ListDevicesRequestListDevicesPaginateTypeDef",
     "ListDeviceEventsResponseTypeDef",
 )
 
 ClaimDevicesByClaimCodeRequestRequestTypeDef = TypedDict(
     "ClaimDevicesByClaimCodeRequestRequestTypeDef",
     {
         "ClaimCode": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+ClaimDevicesByClaimCodeResponseTypeDef = TypedDict(
+    "ClaimDevicesByClaimCodeResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ClaimCode": str,
+        "Total": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDeviceRequestRequestTypeDef = TypedDict(
     "DescribeDeviceRequestRequestTypeDef",
     {
         "DeviceId": str,
@@ -110,14 +108,21 @@
     {
         "DeviceType": str,
         "MethodName": str,
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
 _RequiredFinalizeDeviceClaimRequestRequestTypeDef = TypedDict(
     "_RequiredFinalizeDeviceClaimRequestRequestTypeDef",
     {
         "DeviceId": str,
     },
 )
 _OptionalFinalizeDeviceClaimRequestRequestTypeDef = TypedDict(
@@ -132,38 +137,76 @@
 class FinalizeDeviceClaimRequestRequestTypeDef(
     _RequiredFinalizeDeviceClaimRequestRequestTypeDef,
     _OptionalFinalizeDeviceClaimRequestRequestTypeDef,
 ):
     pass
 
 
+FinalizeDeviceClaimResponseTypeDef = TypedDict(
+    "FinalizeDeviceClaimResponseTypeDef",
+    {
+        "State": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetDeviceMethodsRequestRequestTypeDef = TypedDict(
     "GetDeviceMethodsRequestRequestTypeDef",
     {
         "DeviceId": str,
     },
 )
 
 InitiateDeviceClaimRequestRequestTypeDef = TypedDict(
     "InitiateDeviceClaimRequestRequestTypeDef",
     {
         "DeviceId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+InitiateDeviceClaimResponseTypeDef = TypedDict(
+    "InitiateDeviceClaimResponseTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "State": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+InvokeDeviceMethodResponseTypeDef = TypedDict(
+    "InvokeDeviceMethodResponseTypeDef",
+    {
+        "DeviceMethodResponse": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListDeviceEventsRequestListDeviceEventsPaginateTypeDef = TypedDict(
+    "_RequiredListDeviceEventsRequestListDeviceEventsPaginateTypeDef",
+    {
+        "DeviceId": str,
+        "FromTimeStamp": Union[datetime, str],
+        "ToTimeStamp": Union[datetime, str],
+    },
+)
+_OptionalListDeviceEventsRequestListDeviceEventsPaginateTypeDef = TypedDict(
+    "_OptionalListDeviceEventsRequestListDeviceEventsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListDeviceEventsRequestListDeviceEventsPaginateTypeDef(
+    _RequiredListDeviceEventsRequestListDeviceEventsPaginateTypeDef,
+    _OptionalListDeviceEventsRequestListDeviceEventsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListDeviceEventsRequestRequestTypeDef = TypedDict(
     "_RequiredListDeviceEventsRequestRequestTypeDef",
     {
         "DeviceId": str,
         "FromTimeStamp": Union[datetime, str],
         "ToTimeStamp": Union[datetime, str],
     },
@@ -180,14 +223,23 @@
 
 class ListDeviceEventsRequestRequestTypeDef(
     _RequiredListDeviceEventsRequestRequestTypeDef, _OptionalListDeviceEventsRequestRequestTypeDef
 ):
     pass
 
 
+ListDevicesRequestListDevicesPaginateTypeDef = TypedDict(
+    "ListDevicesRequestListDevicesPaginateTypeDef",
+    {
+        "DeviceType": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDevicesRequestRequestTypeDef = TypedDict(
     "ListDevicesRequestRequestTypeDef",
     {
         "DeviceType": str,
         "MaxResults": int,
         "NextToken": str,
     },
@@ -197,14 +249,43 @@
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
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "Tags": Mapping[str, str],
     },
 )
@@ -212,14 +293,22 @@
 UnclaimDeviceRequestRequestTypeDef = TypedDict(
     "UnclaimDeviceRequestRequestTypeDef",
     {
         "DeviceId": str,
     },
 )
 
+UnclaimDeviceResponseTypeDef = TypedDict(
+    "UnclaimDeviceResponseTypeDef",
+    {
+        "State": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
@@ -241,84 +330,28 @@
 
 class UpdateDeviceStateRequestRequestTypeDef(
     _RequiredUpdateDeviceStateRequestRequestTypeDef, _OptionalUpdateDeviceStateRequestRequestTypeDef
 ):
     pass
 
 
-ClaimDevicesByClaimCodeResponseTypeDef = TypedDict(
-    "ClaimDevicesByClaimCodeResponseTypeDef",
-    {
-        "ClaimCode": str,
-        "Total": int,
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
-FinalizeDeviceClaimResponseTypeDef = TypedDict(
-    "FinalizeDeviceClaimResponseTypeDef",
-    {
-        "State": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-InitiateDeviceClaimResponseTypeDef = TypedDict(
-    "InitiateDeviceClaimResponseTypeDef",
-    {
-        "State": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-InvokeDeviceMethodResponseTypeDef = TypedDict(
-    "InvokeDeviceMethodResponseTypeDef",
-    {
-        "DeviceMethodResponse": str,
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
-UnclaimDeviceResponseTypeDef = TypedDict(
-    "UnclaimDeviceResponseTypeDef",
-    {
-        "State": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 DescribeDeviceResponseTypeDef = TypedDict(
     "DescribeDeviceResponseTypeDef",
     {
         "DeviceDescription": DeviceDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDevicesResponseTypeDef = TypedDict(
     "ListDevicesResponseTypeDef",
     {
         "Devices": List[DeviceDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeviceEventTypeDef = TypedDict(
     "DeviceEventTypeDef",
     {
         "Device": DeviceTypeDef,
@@ -327,15 +360,15 @@
     total=False,
 )
 
 GetDeviceMethodsResponseTypeDef = TypedDict(
     "GetDeviceMethodsResponseTypeDef",
     {
         "DeviceMethods": List[DeviceMethodTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredInvokeDeviceMethodRequestRequestTypeDef = TypedDict(
     "_RequiredInvokeDeviceMethodRequestRequestTypeDef",
     {
         "DeviceId": str,
@@ -354,48 +387,15 @@
 class InvokeDeviceMethodRequestRequestTypeDef(
     _RequiredInvokeDeviceMethodRequestRequestTypeDef,
     _OptionalInvokeDeviceMethodRequestRequestTypeDef,
 ):
     pass
 
 
-_RequiredListDeviceEventsRequestListDeviceEventsPaginateTypeDef = TypedDict(
-    "_RequiredListDeviceEventsRequestListDeviceEventsPaginateTypeDef",
-    {
-        "DeviceId": str,
-        "FromTimeStamp": Union[datetime, str],
-        "ToTimeStamp": Union[datetime, str],
-    },
-)
-_OptionalListDeviceEventsRequestListDeviceEventsPaginateTypeDef = TypedDict(
-    "_OptionalListDeviceEventsRequestListDeviceEventsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListDeviceEventsRequestListDeviceEventsPaginateTypeDef(
-    _RequiredListDeviceEventsRequestListDeviceEventsPaginateTypeDef,
-    _OptionalListDeviceEventsRequestListDeviceEventsPaginateTypeDef,
-):
-    pass
-
-
-ListDevicesRequestListDevicesPaginateTypeDef = TypedDict(
-    "ListDevicesRequestListDevicesPaginateTypeDef",
-    {
-        "DeviceType": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListDeviceEventsResponseTypeDef = TypedDict(
     "ListDeviceEventsResponseTypeDef",
     {
         "Events": List[DeviceEventTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-iot1click-devices-2.5.0.post1/types_aiobotocore_iot1click_devices/type_defs.pyi` & `types-aiobotocore-iot1click-devices-2.5.1/types_aiobotocore_iot1click_devices/type_defs.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -18,62 +18,60 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "ClaimDevicesByClaimCodeRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "ClaimDevicesByClaimCodeResponseTypeDef",
     "DescribeDeviceRequestRequestTypeDef",
     "DeviceDescriptionTypeDef",
     "DeviceTypeDef",
     "DeviceMethodTypeDef",
+    "EmptyResponseMetadataTypeDef",
     "FinalizeDeviceClaimRequestRequestTypeDef",
+    "FinalizeDeviceClaimResponseTypeDef",
     "GetDeviceMethodsRequestRequestTypeDef",
     "InitiateDeviceClaimRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "InitiateDeviceClaimResponseTypeDef",
+    "InvokeDeviceMethodResponseTypeDef",
+    "ListDeviceEventsRequestListDeviceEventsPaginateTypeDef",
     "ListDeviceEventsRequestRequestTypeDef",
+    "ListDevicesRequestListDevicesPaginateTypeDef",
     "ListDevicesRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UnclaimDeviceRequestRequestTypeDef",
+    "UnclaimDeviceResponseTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateDeviceStateRequestRequestTypeDef",
-    "ClaimDevicesByClaimCodeResponseTypeDef",
-    "EmptyResponseMetadataTypeDef",
-    "FinalizeDeviceClaimResponseTypeDef",
-    "InitiateDeviceClaimResponseTypeDef",
-    "InvokeDeviceMethodResponseTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "UnclaimDeviceResponseTypeDef",
     "DescribeDeviceResponseTypeDef",
     "ListDevicesResponseTypeDef",
     "DeviceEventTypeDef",
     "GetDeviceMethodsResponseTypeDef",
     "InvokeDeviceMethodRequestRequestTypeDef",
-    "ListDeviceEventsRequestListDeviceEventsPaginateTypeDef",
-    "ListDevicesRequestListDevicesPaginateTypeDef",
     "ListDeviceEventsResponseTypeDef",
 )
 
 ClaimDevicesByClaimCodeRequestRequestTypeDef = TypedDict(
     "ClaimDevicesByClaimCodeRequestRequestTypeDef",
     {
         "ClaimCode": str,
     },
 )
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+ClaimDevicesByClaimCodeResponseTypeDef = TypedDict(
+    "ClaimDevicesByClaimCodeResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "ClaimCode": str,
+        "Total": int,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DescribeDeviceRequestRequestTypeDef = TypedDict(
     "DescribeDeviceRequestRequestTypeDef",
     {
         "DeviceId": str,
@@ -109,14 +107,21 @@
     {
         "DeviceType": str,
         "MethodName": str,
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
 _RequiredFinalizeDeviceClaimRequestRequestTypeDef = TypedDict(
     "_RequiredFinalizeDeviceClaimRequestRequestTypeDef",
     {
         "DeviceId": str,
     },
 )
 _OptionalFinalizeDeviceClaimRequestRequestTypeDef = TypedDict(
@@ -129,38 +134,74 @@
 
 class FinalizeDeviceClaimRequestRequestTypeDef(
     _RequiredFinalizeDeviceClaimRequestRequestTypeDef,
     _OptionalFinalizeDeviceClaimRequestRequestTypeDef,
 ):
     pass
 
+FinalizeDeviceClaimResponseTypeDef = TypedDict(
+    "FinalizeDeviceClaimResponseTypeDef",
+    {
+        "State": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetDeviceMethodsRequestRequestTypeDef = TypedDict(
     "GetDeviceMethodsRequestRequestTypeDef",
     {
         "DeviceId": str,
     },
 )
 
 InitiateDeviceClaimRequestRequestTypeDef = TypedDict(
     "InitiateDeviceClaimRequestRequestTypeDef",
     {
         "DeviceId": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+InitiateDeviceClaimResponseTypeDef = TypedDict(
+    "InitiateDeviceClaimResponseTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "State": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+InvokeDeviceMethodResponseTypeDef = TypedDict(
+    "InvokeDeviceMethodResponseTypeDef",
+    {
+        "DeviceMethodResponse": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
+_RequiredListDeviceEventsRequestListDeviceEventsPaginateTypeDef = TypedDict(
+    "_RequiredListDeviceEventsRequestListDeviceEventsPaginateTypeDef",
+    {
+        "DeviceId": str,
+        "FromTimeStamp": Union[datetime, str],
+        "ToTimeStamp": Union[datetime, str],
+    },
+)
+_OptionalListDeviceEventsRequestListDeviceEventsPaginateTypeDef = TypedDict(
+    "_OptionalListDeviceEventsRequestListDeviceEventsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListDeviceEventsRequestListDeviceEventsPaginateTypeDef(
+    _RequiredListDeviceEventsRequestListDeviceEventsPaginateTypeDef,
+    _OptionalListDeviceEventsRequestListDeviceEventsPaginateTypeDef,
+):
+    pass
+
 _RequiredListDeviceEventsRequestRequestTypeDef = TypedDict(
     "_RequiredListDeviceEventsRequestRequestTypeDef",
     {
         "DeviceId": str,
         "FromTimeStamp": Union[datetime, str],
         "ToTimeStamp": Union[datetime, str],
     },
@@ -175,14 +216,23 @@
 )
 
 class ListDeviceEventsRequestRequestTypeDef(
     _RequiredListDeviceEventsRequestRequestTypeDef, _OptionalListDeviceEventsRequestRequestTypeDef
 ):
     pass
 
+ListDevicesRequestListDevicesPaginateTypeDef = TypedDict(
+    "ListDevicesRequestListDevicesPaginateTypeDef",
+    {
+        "DeviceType": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListDevicesRequestRequestTypeDef = TypedDict(
     "ListDevicesRequestRequestTypeDef",
     {
         "DeviceType": str,
         "MaxResults": int,
         "NextToken": str,
     },
@@ -192,14 +242,43 @@
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
 TagResourceRequestRequestTypeDef = TypedDict(
     "TagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "Tags": Mapping[str, str],
     },
 )
@@ -207,14 +286,22 @@
 UnclaimDeviceRequestRequestTypeDef = TypedDict(
     "UnclaimDeviceRequestRequestTypeDef",
     {
         "DeviceId": str,
     },
 )
 
+UnclaimDeviceResponseTypeDef = TypedDict(
+    "UnclaimDeviceResponseTypeDef",
+    {
+        "State": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 UntagResourceRequestRequestTypeDef = TypedDict(
     "UntagResourceRequestRequestTypeDef",
     {
         "ResourceArn": str,
         "TagKeys": Sequence[str],
     },
 )
@@ -234,84 +321,28 @@
 )
 
 class UpdateDeviceStateRequestRequestTypeDef(
     _RequiredUpdateDeviceStateRequestRequestTypeDef, _OptionalUpdateDeviceStateRequestRequestTypeDef
 ):
     pass
 
-ClaimDevicesByClaimCodeResponseTypeDef = TypedDict(
-    "ClaimDevicesByClaimCodeResponseTypeDef",
-    {
-        "ClaimCode": str,
-        "Total": int,
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
-FinalizeDeviceClaimResponseTypeDef = TypedDict(
-    "FinalizeDeviceClaimResponseTypeDef",
-    {
-        "State": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-InitiateDeviceClaimResponseTypeDef = TypedDict(
-    "InitiateDeviceClaimResponseTypeDef",
-    {
-        "State": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-InvokeDeviceMethodResponseTypeDef = TypedDict(
-    "InvokeDeviceMethodResponseTypeDef",
-    {
-        "DeviceMethodResponse": str,
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
-UnclaimDeviceResponseTypeDef = TypedDict(
-    "UnclaimDeviceResponseTypeDef",
-    {
-        "State": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 DescribeDeviceResponseTypeDef = TypedDict(
     "DescribeDeviceResponseTypeDef",
     {
         "DeviceDescription": DeviceDescriptionTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDevicesResponseTypeDef = TypedDict(
     "ListDevicesResponseTypeDef",
     {
         "Devices": List[DeviceDescriptionTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeviceEventTypeDef = TypedDict(
     "DeviceEventTypeDef",
     {
         "Device": DeviceTypeDef,
@@ -320,15 +351,15 @@
     total=False,
 )
 
 GetDeviceMethodsResponseTypeDef = TypedDict(
     "GetDeviceMethodsResponseTypeDef",
     {
         "DeviceMethods": List[DeviceMethodTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredInvokeDeviceMethodRequestRequestTypeDef = TypedDict(
     "_RequiredInvokeDeviceMethodRequestRequestTypeDef",
     {
         "DeviceId": str,
@@ -345,46 +376,15 @@
 
 class InvokeDeviceMethodRequestRequestTypeDef(
     _RequiredInvokeDeviceMethodRequestRequestTypeDef,
     _OptionalInvokeDeviceMethodRequestRequestTypeDef,
 ):
     pass
 
-_RequiredListDeviceEventsRequestListDeviceEventsPaginateTypeDef = TypedDict(
-    "_RequiredListDeviceEventsRequestListDeviceEventsPaginateTypeDef",
-    {
-        "DeviceId": str,
-        "FromTimeStamp": Union[datetime, str],
-        "ToTimeStamp": Union[datetime, str],
-    },
-)
-_OptionalListDeviceEventsRequestListDeviceEventsPaginateTypeDef = TypedDict(
-    "_OptionalListDeviceEventsRequestListDeviceEventsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListDeviceEventsRequestListDeviceEventsPaginateTypeDef(
-    _RequiredListDeviceEventsRequestListDeviceEventsPaginateTypeDef,
-    _OptionalListDeviceEventsRequestListDeviceEventsPaginateTypeDef,
-):
-    pass
-
-ListDevicesRequestListDevicesPaginateTypeDef = TypedDict(
-    "ListDevicesRequestListDevicesPaginateTypeDef",
-    {
-        "DeviceType": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
 ListDeviceEventsResponseTypeDef = TypedDict(
     "ListDeviceEventsResponseTypeDef",
     {
         "Events": List[DeviceEventTypeDef],
         "NextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-iot1click-devices-2.5.0.post1/types_aiobotocore_iot1click_devices.egg-info/PKG-INFO` & `types-aiobotocore-iot1click-devices-2.5.1/types_aiobotocore_iot1click_devices.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-iot1click-devices
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.IoT1ClickDevicesService 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.IoT1ClickDevicesService 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot1click_devices/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-iot1click-devices"></a>
 
 # types-aiobotocore-iot1click-devices
 
 [![PyPI - types-aiobotocore-iot1click-devices](https://img.shields.io/pypi/v/types-aiobotocore-iot1click-devices.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iot1click-devices)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iot1click-devices.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iot1click-devices)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot1click_devices/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iot1click-devices?color=blue)](https://pypistats.org/packages/types-aiobotocore-iot1click-devices)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoT1ClickDevicesService 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot1click-devices.html#IoT1ClickDevicesService)
+[aiobotocore.IoT1ClickDevicesService 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot1click-devices.html#IoT1ClickDevicesService)
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
 [types-aiobotocore-iot1click-devices docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot1click_devices/).
 
 See how it helps to find and fix potential bugs:
 
@@ -321,44 +321,44 @@
 
 `types_aiobotocore_iot1click_devices.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_iot1click_devices.type_defs import (
     ClaimDevicesByClaimCodeRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    ClaimDevicesByClaimCodeResponseTypeDef,
     DescribeDeviceRequestRequestTypeDef,
     DeviceDescriptionTypeDef,
     DeviceTypeDef,
     DeviceMethodTypeDef,
+    EmptyResponseMetadataTypeDef,
     FinalizeDeviceClaimRequestRequestTypeDef,
+    FinalizeDeviceClaimResponseTypeDef,
     GetDeviceMethodsRequestRequestTypeDef,
     InitiateDeviceClaimRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    InitiateDeviceClaimResponseTypeDef,
+    InvokeDeviceMethodResponseTypeDef,
+    ListDeviceEventsRequestListDeviceEventsPaginateTypeDef,
     ListDeviceEventsRequestRequestTypeDef,
+    ListDevicesRequestListDevicesPaginateTypeDef,
     ListDevicesRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UnclaimDeviceRequestRequestTypeDef,
+    UnclaimDeviceResponseTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateDeviceStateRequestRequestTypeDef,
-    ClaimDevicesByClaimCodeResponseTypeDef,
-    EmptyResponseMetadataTypeDef,
-    FinalizeDeviceClaimResponseTypeDef,
-    InitiateDeviceClaimResponseTypeDef,
-    InvokeDeviceMethodResponseTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    UnclaimDeviceResponseTypeDef,
     DescribeDeviceResponseTypeDef,
     ListDevicesResponseTypeDef,
     DeviceEventTypeDef,
     GetDeviceMethodsResponseTypeDef,
     InvokeDeviceMethodRequestRequestTypeDef,
-    ListDeviceEventsRequestListDeviceEventsPaginateTypeDef,
-    ListDevicesRequestListDevicesPaginateTypeDef,
     ListDeviceEventsResponseTypeDef,
 )
 
 
 def get_structure() -> ClaimDevicesByClaimCodeRequestRequestTypeDef:
     return {...}
 ```
@@ -366,43 +366,43 @@
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

### Comparing `types-aiobotocore-iot1click-devices-2.5.0.post1/types_aiobotocore_iot1click_devices.egg-info/SOURCES.txt` & `types-aiobotocore-iot1click-devices-2.5.1/types_aiobotocore_iot1click_devices.egg-info/SOURCES.txt`

 * *Files identical despite different names*

