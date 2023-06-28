# Comparing `tmp/types-aiobotocore-iot-roborunner-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-iot-roborunner-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-iot-roborunner-2.5.0.post1.tar", last modified: Sat Mar 11 12:26:46 2023, max compression
+gzip compressed data, was "types-aiobotocore-iot-roborunner-2.5.1.tar", last modified: Wed Jun 28 01:43:38 2023, max compression
```

## Comparing `types-aiobotocore-iot-roborunner-2.5.0.post1.tar` & `types-aiobotocore-iot-roborunner-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:46.479295 types-aiobotocore-iot-roborunner-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:16:11.000000 types-aiobotocore-iot-roborunner-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    15513 2023-03-11 12:26:46.479295 types-aiobotocore-iot-roborunner-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13915 2023-03-11 12:16:11.000000 types-aiobotocore-iot-roborunner-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:26:46.479295 types-aiobotocore-iot-roborunner-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2172 2023-03-11 12:16:10.000000 types-aiobotocore-iot-roborunner-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:46.479295 types-aiobotocore-iot-roborunner-2.5.0.post1/types_aiobotocore_iot_roborunner/
--rw-r--r--   0 runner    (1001) docker     (123)     1270 2023-03-11 12:16:11.000000 types-aiobotocore-iot-roborunner-2.5.0.post1/types_aiobotocore_iot_roborunner/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1269 2023-03-11 12:16:11.000000 types-aiobotocore-iot-roborunner-2.5.0.post1/types_aiobotocore_iot_roborunner/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      969 2023-03-11 12:16:11.000000 types-aiobotocore-iot-roborunner-2.5.0.post1/types_aiobotocore_iot_roborunner/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    20847 2023-03-11 12:16:11.000000 types-aiobotocore-iot-roborunner-2.5.0.post1/types_aiobotocore_iot_roborunner/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    20814 2023-03-11 12:16:11.000000 types-aiobotocore-iot-roborunner-2.5.0.post1/types_aiobotocore_iot_roborunner/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     8005 2023-03-11 12:16:11.000000 types-aiobotocore-iot-roborunner-2.5.0.post1/types_aiobotocore_iot_roborunner/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     8003 2023-03-11 12:16:11.000000 types-aiobotocore-iot-roborunner-2.5.0.post1/types_aiobotocore_iot_roborunner/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     5614 2023-03-11 12:16:11.000000 types-aiobotocore-iot-roborunner-2.5.0.post1/types_aiobotocore_iot_roborunner/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     5607 2023-03-11 12:16:11.000000 types-aiobotocore-iot-roborunner-2.5.0.post1/types_aiobotocore_iot_roborunner/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:16:11.000000 types-aiobotocore-iot-roborunner-2.5.0.post1/types_aiobotocore_iot_roborunner/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    20236 2023-03-11 12:16:11.000000 types-aiobotocore-iot-roborunner-2.5.0.post1/types_aiobotocore_iot_roborunner/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    20197 2023-03-11 12:16:11.000000 types-aiobotocore-iot-roborunner-2.5.0.post1/types_aiobotocore_iot_roborunner/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:16:11.000000 types-aiobotocore-iot-roborunner-2.5.0.post1/types_aiobotocore_iot_roborunner/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:26:46.479295 types-aiobotocore-iot-roborunner-2.5.0.post1/types_aiobotocore_iot_roborunner.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    15513 2023-03-11 12:26:46.000000 types-aiobotocore-iot-roborunner-2.5.0.post1/types_aiobotocore_iot_roborunner.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      946 2023-03-11 12:26:46.000000 types-aiobotocore-iot-roborunner-2.5.0.post1/types_aiobotocore_iot_roborunner.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:46.000000 types-aiobotocore-iot-roborunner-2.5.0.post1/types_aiobotocore_iot_roborunner.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:26:46.000000 types-aiobotocore-iot-roborunner-2.5.0.post1/types_aiobotocore_iot_roborunner.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:26:46.000000 types-aiobotocore-iot-roborunner-2.5.0.post1/types_aiobotocore_iot_roborunner.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       33 2023-03-11 12:26:46.000000 types-aiobotocore-iot-roborunner-2.5.0.post1/types_aiobotocore_iot_roborunner.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:38.026152 types-aiobotocore-iot-roborunner-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:32:49.000000 types-aiobotocore-iot-roborunner-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    15512 2023-06-28 01:43:38.026152 types-aiobotocore-iot-roborunner-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13920 2023-06-28 01:32:49.000000 types-aiobotocore-iot-roborunner-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:38.026152 types-aiobotocore-iot-roborunner-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2166 2023-06-28 01:32:49.000000 types-aiobotocore-iot-roborunner-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:38.026152 types-aiobotocore-iot-roborunner-2.5.1/types_aiobotocore_iot_roborunner/
+-rw-r--r--   0 runner    (1001) docker     (123)     1270 2023-06-28 01:32:49.000000 types-aiobotocore-iot-roborunner-2.5.1/types_aiobotocore_iot_roborunner/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1269 2023-06-28 01:32:49.000000 types-aiobotocore-iot-roborunner-2.5.1/types_aiobotocore_iot_roborunner/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      957 2023-06-28 01:32:49.000000 types-aiobotocore-iot-roborunner-2.5.1/types_aiobotocore_iot_roborunner/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20847 2023-06-28 01:32:49.000000 types-aiobotocore-iot-roborunner-2.5.1/types_aiobotocore_iot_roborunner/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20814 2023-06-28 01:32:49.000000 types-aiobotocore-iot-roborunner-2.5.1/types_aiobotocore_iot_roborunner/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     8214 2023-06-28 01:32:49.000000 types-aiobotocore-iot-roborunner-2.5.1/types_aiobotocore_iot_roborunner/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8212 2023-06-28 01:32:49.000000 types-aiobotocore-iot-roborunner-2.5.1/types_aiobotocore_iot_roborunner/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     5502 2023-06-28 01:32:49.000000 types-aiobotocore-iot-roborunner-2.5.1/types_aiobotocore_iot_roborunner/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5496 2023-06-28 01:32:49.000000 types-aiobotocore-iot-roborunner-2.5.1/types_aiobotocore_iot_roborunner/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:32:49.000000 types-aiobotocore-iot-roborunner-2.5.1/types_aiobotocore_iot_roborunner/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    20276 2023-06-28 01:32:50.000000 types-aiobotocore-iot-roborunner-2.5.1/types_aiobotocore_iot_roborunner/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20237 2023-06-28 01:32:49.000000 types-aiobotocore-iot-roborunner-2.5.1/types_aiobotocore_iot_roborunner/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:32:49.000000 types-aiobotocore-iot-roborunner-2.5.1/types_aiobotocore_iot_roborunner/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:38.026152 types-aiobotocore-iot-roborunner-2.5.1/types_aiobotocore_iot_roborunner.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    15512 2023-06-28 01:43:37.000000 types-aiobotocore-iot-roborunner-2.5.1/types_aiobotocore_iot_roborunner.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      946 2023-06-28 01:43:37.000000 types-aiobotocore-iot-roborunner-2.5.1/types_aiobotocore_iot_roborunner.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:37.000000 types-aiobotocore-iot-roborunner-2.5.1/types_aiobotocore_iot_roborunner.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:37.000000 types-aiobotocore-iot-roborunner-2.5.1/types_aiobotocore_iot_roborunner.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:43:37.000000 types-aiobotocore-iot-roborunner-2.5.1/types_aiobotocore_iot_roborunner.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       33 2023-06-28 01:43:37.000000 types-aiobotocore-iot-roborunner-2.5.1/types_aiobotocore_iot_roborunner.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-iot-roborunner-2.5.0.post1/LICENSE` & `types-aiobotocore-iot-roborunner-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-iot-roborunner-2.5.0.post1/PKG-INFO` & `types-aiobotocore-iot-roborunner-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-iot-roborunner
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.IoTRoboRunner 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.IoTRoboRunner 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_roborunner/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-iot-roborunner"></a>
 
 # types-aiobotocore-iot-roborunner
 
 [![PyPI - types-aiobotocore-iot-roborunner](https://img.shields.io/pypi/v/types-aiobotocore-iot-roborunner.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iot-roborunner)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iot-roborunner.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iot-roborunner)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_roborunner/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iot-roborunner?color=blue)](https://pypistats.org/packages/types-aiobotocore-iot-roborunner)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoTRoboRunner 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot-roborunner.html#IoTRoboRunner)
+[aiobotocore.IoTRoboRunner 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot-roborunner.html#IoTRoboRunner)
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
 [types-aiobotocore-iot-roborunner docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_roborunner/).
 
 See how it helps to find and fix potential bugs:
 
@@ -332,54 +332,54 @@
 `types_aiobotocore_iot_roborunner.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_iot_roborunner.type_defs import (
     CartesianCoordinatesTypeDef,
     CreateDestinationRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CreateDestinationResponseTypeDef,
     CreateSiteRequestRequestTypeDef,
+    CreateSiteResponseTypeDef,
     CreateWorkerFleetRequestRequestTypeDef,
+    CreateWorkerFleetResponseTypeDef,
     OrientationTypeDef,
     VendorPropertiesTypeDef,
+    CreateWorkerResponseTypeDef,
     DeleteDestinationRequestRequestTypeDef,
     DeleteSiteRequestRequestTypeDef,
     DeleteWorkerFleetRequestRequestTypeDef,
     DeleteWorkerRequestRequestTypeDef,
     DestinationTypeDef,
     GetDestinationRequestRequestTypeDef,
+    GetDestinationResponseTypeDef,
     GetSiteRequestRequestTypeDef,
+    GetSiteResponseTypeDef,
     GetWorkerFleetRequestRequestTypeDef,
+    GetWorkerFleetResponseTypeDef,
     GetWorkerRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListDestinationsRequestListDestinationsPaginateTypeDef,
     ListDestinationsRequestRequestTypeDef,
+    ListSitesRequestListSitesPaginateTypeDef,
     ListSitesRequestRequestTypeDef,
     SiteTypeDef,
+    ListWorkerFleetsRequestListWorkerFleetsPaginateTypeDef,
     ListWorkerFleetsRequestRequestTypeDef,
     WorkerFleetTypeDef,
+    ListWorkersRequestListWorkersPaginateTypeDef,
     ListWorkersRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     UpdateDestinationRequestRequestTypeDef,
-    UpdateSiteRequestRequestTypeDef,
-    UpdateWorkerFleetRequestRequestTypeDef,
-    PositionCoordinatesTypeDef,
-    CreateDestinationResponseTypeDef,
-    CreateSiteResponseTypeDef,
-    CreateWorkerFleetResponseTypeDef,
-    CreateWorkerResponseTypeDef,
-    GetDestinationResponseTypeDef,
-    GetSiteResponseTypeDef,
-    GetWorkerFleetResponseTypeDef,
     UpdateDestinationResponseTypeDef,
+    UpdateSiteRequestRequestTypeDef,
     UpdateSiteResponseTypeDef,
+    UpdateWorkerFleetRequestRequestTypeDef,
     UpdateWorkerFleetResponseTypeDef,
+    PositionCoordinatesTypeDef,
     ListDestinationsResponseTypeDef,
-    ListDestinationsRequestListDestinationsPaginateTypeDef,
-    ListSitesRequestListSitesPaginateTypeDef,
-    ListWorkerFleetsRequestListWorkerFleetsPaginateTypeDef,
-    ListWorkersRequestListWorkersPaginateTypeDef,
     ListSitesResponseTypeDef,
     ListWorkerFleetsResponseTypeDef,
     CreateWorkerRequestRequestTypeDef,
     GetWorkerResponseTypeDef,
     UpdateWorkerRequestRequestTypeDef,
     UpdateWorkerResponseTypeDef,
     WorkerTypeDef,
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

### Comparing `types-aiobotocore-iot-roborunner-2.5.0.post1/README.md` & `types-aiobotocore-iot-roborunner-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-iot-roborunner"></a>
 
 # types-aiobotocore-iot-roborunner
 
 [![PyPI - types-aiobotocore-iot-roborunner](https://img.shields.io/pypi/v/types-aiobotocore-iot-roborunner.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iot-roborunner)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iot-roborunner.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iot-roborunner)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_roborunner/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iot-roborunner?color=blue)](https://pypistats.org/packages/types-aiobotocore-iot-roborunner)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoTRoboRunner 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot-roborunner.html#IoTRoboRunner)
+[aiobotocore.IoTRoboRunner 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot-roborunner.html#IoTRoboRunner)
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
 [types-aiobotocore-iot-roborunner docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_roborunner/).
 
 See how it helps to find and fix potential bugs:
 
@@ -299,54 +299,54 @@
 `types_aiobotocore_iot_roborunner.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_iot_roborunner.type_defs import (
     CartesianCoordinatesTypeDef,
     CreateDestinationRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CreateDestinationResponseTypeDef,
     CreateSiteRequestRequestTypeDef,
+    CreateSiteResponseTypeDef,
     CreateWorkerFleetRequestRequestTypeDef,
+    CreateWorkerFleetResponseTypeDef,
     OrientationTypeDef,
     VendorPropertiesTypeDef,
+    CreateWorkerResponseTypeDef,
     DeleteDestinationRequestRequestTypeDef,
     DeleteSiteRequestRequestTypeDef,
     DeleteWorkerFleetRequestRequestTypeDef,
     DeleteWorkerRequestRequestTypeDef,
     DestinationTypeDef,
     GetDestinationRequestRequestTypeDef,
+    GetDestinationResponseTypeDef,
     GetSiteRequestRequestTypeDef,
+    GetSiteResponseTypeDef,
     GetWorkerFleetRequestRequestTypeDef,
+    GetWorkerFleetResponseTypeDef,
     GetWorkerRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListDestinationsRequestListDestinationsPaginateTypeDef,
     ListDestinationsRequestRequestTypeDef,
+    ListSitesRequestListSitesPaginateTypeDef,
     ListSitesRequestRequestTypeDef,
     SiteTypeDef,
+    ListWorkerFleetsRequestListWorkerFleetsPaginateTypeDef,
     ListWorkerFleetsRequestRequestTypeDef,
     WorkerFleetTypeDef,
+    ListWorkersRequestListWorkersPaginateTypeDef,
     ListWorkersRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     UpdateDestinationRequestRequestTypeDef,
-    UpdateSiteRequestRequestTypeDef,
-    UpdateWorkerFleetRequestRequestTypeDef,
-    PositionCoordinatesTypeDef,
-    CreateDestinationResponseTypeDef,
-    CreateSiteResponseTypeDef,
-    CreateWorkerFleetResponseTypeDef,
-    CreateWorkerResponseTypeDef,
-    GetDestinationResponseTypeDef,
-    GetSiteResponseTypeDef,
-    GetWorkerFleetResponseTypeDef,
     UpdateDestinationResponseTypeDef,
+    UpdateSiteRequestRequestTypeDef,
     UpdateSiteResponseTypeDef,
+    UpdateWorkerFleetRequestRequestTypeDef,
     UpdateWorkerFleetResponseTypeDef,
+    PositionCoordinatesTypeDef,
     ListDestinationsResponseTypeDef,
-    ListDestinationsRequestListDestinationsPaginateTypeDef,
-    ListSitesRequestListSitesPaginateTypeDef,
-    ListWorkerFleetsRequestListWorkerFleetsPaginateTypeDef,
-    ListWorkersRequestListWorkersPaginateTypeDef,
     ListSitesResponseTypeDef,
     ListWorkerFleetsResponseTypeDef,
     CreateWorkerRequestRequestTypeDef,
     GetWorkerResponseTypeDef,
     UpdateWorkerRequestRequestTypeDef,
     UpdateWorkerResponseTypeDef,
     WorkerTypeDef,
@@ -361,43 +361,43 @@
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

### Comparing `types-aiobotocore-iot-roborunner-2.5.0.post1/setup.py` & `types-aiobotocore-iot-roborunner-2.5.1/setup.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-iot-roborunner.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-iot-roborunner",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_iot_roborunner"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.IoTRoboRunner 2.5.0 service generated with"
-        " mypy-boto3-builder 7.13.0"
+        "Type annotations for aiobotocore.IoTRoboRunner 2.5.1 service generated with"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_roborunner/"
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

### Comparing `types-aiobotocore-iot-roborunner-2.5.0.post1/types_aiobotocore_iot_roborunner/__init__.py` & `types-aiobotocore-iot-roborunner-2.5.1/types_aiobotocore_iot_roborunner/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iot-roborunner-2.5.0.post1/types_aiobotocore_iot_roborunner/__init__.pyi` & `types-aiobotocore-iot-roborunner-2.5.1/types_aiobotocore_iot_roborunner/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iot-roborunner-2.5.0.post1/types_aiobotocore_iot_roborunner/client.py` & `types-aiobotocore-iot-roborunner-2.5.1/types_aiobotocore_iot_roborunner/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iot-roborunner-2.5.0.post1/types_aiobotocore_iot_roborunner/client.pyi` & `types-aiobotocore-iot-roborunner-2.5.1/types_aiobotocore_iot_roborunner/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-iot-roborunner-2.5.0.post1/types_aiobotocore_iot_roborunner/literals.py` & `types-aiobotocore-iot-roborunner-2.5.1/types_aiobotocore_iot_roborunner/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -97,14 +97,15 @@
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
@@ -183,14 +184,15 @@
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
@@ -201,14 +203,15 @@
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
@@ -244,14 +247,15 @@
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
@@ -270,16 +274,19 @@
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
@@ -363,15 +370,17 @@
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

### Comparing `types-aiobotocore-iot-roborunner-2.5.0.post1/types_aiobotocore_iot_roborunner/literals.pyi` & `types-aiobotocore-iot-roborunner-2.5.1/types_aiobotocore_iot_roborunner/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -95,14 +95,15 @@
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
@@ -181,14 +182,15 @@
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
@@ -199,14 +201,15 @@
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
@@ -242,14 +245,15 @@
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
@@ -268,16 +272,19 @@
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
@@ -361,15 +368,17 @@
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

### Comparing `types-aiobotocore-iot-roborunner-2.5.0.post1/types_aiobotocore_iot_roborunner/paginator.py` & `types-aiobotocore-iot-roborunner-2.5.1/types_aiobotocore_iot_roborunner/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -22,35 +22,28 @@
 
         list_destinations_paginator: ListDestinationsPaginator = client.get_paginator("list_destinations")
         list_sites_paginator: ListSitesPaginator = client.get_paginator("list_sites")
         list_worker_fleets_paginator: ListWorkerFleetsPaginator = client.get_paginator("list_worker_fleets")
         list_workers_paginator: ListWorkersPaginator = client.get_paginator("list_workers")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import DestinationStateType
 from .type_defs import (
     ListDestinationsResponseTypeDef,
     ListSitesResponseTypeDef,
     ListWorkerFleetsResponseTypeDef,
     ListWorkersResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
-
 __all__ = (
     "ListDestinationsPaginator",
     "ListSitesPaginator",
     "ListWorkerFleetsPaginator",
     "ListWorkersPaginator",
 )
 
@@ -72,58 +65,58 @@
     """
 
     def paginate(
         self,
         *,
         site: str,
         state: DestinationStateType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDestinationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot-roborunner.html#IoTRoboRunner.Paginator.ListDestinations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_roborunner/paginators/#listdestinationspaginator)
         """
 
 
 class ListSitesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot-roborunner.html#IoTRoboRunner.Paginator.ListSites)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_roborunner/paginators/#listsitespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSitesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot-roborunner.html#IoTRoboRunner.Paginator.ListSites.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_roborunner/paginators/#listsitespaginator)
         """
 
 
 class ListWorkerFleetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot-roborunner.html#IoTRoboRunner.Paginator.ListWorkerFleets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_roborunner/paginators/#listworkerfleetspaginator)
     """
 
     def paginate(
-        self, *, site: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, site: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListWorkerFleetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot-roborunner.html#IoTRoboRunner.Paginator.ListWorkerFleets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_roborunner/paginators/#listworkerfleetspaginator)
         """
 
 
 class ListWorkersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot-roborunner.html#IoTRoboRunner.Paginator.ListWorkers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_roborunner/paginators/#listworkerspaginator)
     """
 
     def paginate(
-        self, *, site: str, fleet: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, site: str, fleet: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListWorkersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot-roborunner.html#IoTRoboRunner.Paginator.ListWorkers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_roborunner/paginators/#listworkerspaginator)
         """
```

### Comparing `types-aiobotocore-iot-roborunner-2.5.0.post1/types_aiobotocore_iot_roborunner/paginator.pyi` & `types-aiobotocore-iot-roborunner-2.5.1/types_aiobotocore_iot_roborunner/paginator.pyi`

 * *Files 8% similar despite different names*

```diff
@@ -22,34 +22,28 @@
 
         list_destinations_paginator: ListDestinationsPaginator = client.get_paginator("list_destinations")
         list_sites_paginator: ListSitesPaginator = client.get_paginator("list_sites")
         list_worker_fleets_paginator: ListWorkerFleetsPaginator = client.get_paginator("list_worker_fleets")
         list_workers_paginator: ListWorkersPaginator = client.get_paginator("list_workers")
     ```
 """
-import sys
-from typing import Generic, Iterator, TypeVar
+from typing import AsyncIterator, Generic, Iterator, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import DestinationStateType
 from .type_defs import (
     ListDestinationsResponseTypeDef,
     ListSitesResponseTypeDef,
     ListWorkerFleetsResponseTypeDef,
     ListWorkersResponseTypeDef,
     PaginatorConfigTypeDef,
 )
 
-if sys.version_info >= (3, 8):
-    from typing import AsyncIterator
-else:
-    from typing_extensions import AsyncIterator
-
 __all__ = (
     "ListDestinationsPaginator",
     "ListSitesPaginator",
     "ListWorkerFleetsPaginator",
     "ListWorkersPaginator",
 )
 
@@ -68,55 +62,55 @@
     """
 
     def paginate(
         self,
         *,
         site: str,
         state: DestinationStateType = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDestinationsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot-roborunner.html#IoTRoboRunner.Paginator.ListDestinations.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_roborunner/paginators/#listdestinationspaginator)
         """
 
 class ListSitesPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot-roborunner.html#IoTRoboRunner.Paginator.ListSites)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_roborunner/paginators/#listsitespaginator)
     """
 
     def paginate(
-        self, *, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListSitesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot-roborunner.html#IoTRoboRunner.Paginator.ListSites.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_roborunner/paginators/#listsitespaginator)
         """
 
 class ListWorkerFleetsPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot-roborunner.html#IoTRoboRunner.Paginator.ListWorkerFleets)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_roborunner/paginators/#listworkerfleetspaginator)
     """
 
     def paginate(
-        self, *, site: str, PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, site: str, PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListWorkerFleetsResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot-roborunner.html#IoTRoboRunner.Paginator.ListWorkerFleets.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_roborunner/paginators/#listworkerfleetspaginator)
         """
 
 class ListWorkersPaginator(AioPaginator):
     """
     [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot-roborunner.html#IoTRoboRunner.Paginator.ListWorkers)
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_roborunner/paginators/#listworkerspaginator)
     """
 
     def paginate(
-        self, *, site: str, fleet: str = ..., PaginationConfig: PaginatorConfigTypeDef = ...
+        self, *, site: str, fleet: str = ..., PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListWorkersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot-roborunner.html#IoTRoboRunner.Paginator.ListWorkers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_roborunner/paginators/#listworkerspaginator)
         """
```

### Comparing `types-aiobotocore-iot-roborunner-2.5.0.post1/types_aiobotocore_iot_roborunner/type_defs.py` & `types-aiobotocore-iot-roborunner-2.5.1/types_aiobotocore_iot_roborunner/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -22,54 +22,54 @@
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "CartesianCoordinatesTypeDef",
     "CreateDestinationRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateDestinationResponseTypeDef",
     "CreateSiteRequestRequestTypeDef",
+    "CreateSiteResponseTypeDef",
     "CreateWorkerFleetRequestRequestTypeDef",
+    "CreateWorkerFleetResponseTypeDef",
     "OrientationTypeDef",
     "VendorPropertiesTypeDef",
+    "CreateWorkerResponseTypeDef",
     "DeleteDestinationRequestRequestTypeDef",
     "DeleteSiteRequestRequestTypeDef",
     "DeleteWorkerFleetRequestRequestTypeDef",
     "DeleteWorkerRequestRequestTypeDef",
     "DestinationTypeDef",
     "GetDestinationRequestRequestTypeDef",
+    "GetDestinationResponseTypeDef",
     "GetSiteRequestRequestTypeDef",
+    "GetSiteResponseTypeDef",
     "GetWorkerFleetRequestRequestTypeDef",
+    "GetWorkerFleetResponseTypeDef",
     "GetWorkerRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListDestinationsRequestListDestinationsPaginateTypeDef",
     "ListDestinationsRequestRequestTypeDef",
+    "ListSitesRequestListSitesPaginateTypeDef",
     "ListSitesRequestRequestTypeDef",
     "SiteTypeDef",
+    "ListWorkerFleetsRequestListWorkerFleetsPaginateTypeDef",
     "ListWorkerFleetsRequestRequestTypeDef",
     "WorkerFleetTypeDef",
+    "ListWorkersRequestListWorkersPaginateTypeDef",
     "ListWorkersRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "UpdateDestinationRequestRequestTypeDef",
-    "UpdateSiteRequestRequestTypeDef",
-    "UpdateWorkerFleetRequestRequestTypeDef",
-    "PositionCoordinatesTypeDef",
-    "CreateDestinationResponseTypeDef",
-    "CreateSiteResponseTypeDef",
-    "CreateWorkerFleetResponseTypeDef",
-    "CreateWorkerResponseTypeDef",
-    "GetDestinationResponseTypeDef",
-    "GetSiteResponseTypeDef",
-    "GetWorkerFleetResponseTypeDef",
     "UpdateDestinationResponseTypeDef",
+    "UpdateSiteRequestRequestTypeDef",
     "UpdateSiteResponseTypeDef",
+    "UpdateWorkerFleetRequestRequestTypeDef",
     "UpdateWorkerFleetResponseTypeDef",
+    "PositionCoordinatesTypeDef",
     "ListDestinationsResponseTypeDef",
-    "ListDestinationsRequestListDestinationsPaginateTypeDef",
-    "ListSitesRequestListSitesPaginateTypeDef",
-    "ListWorkerFleetsRequestListWorkerFleetsPaginateTypeDef",
-    "ListWorkersRequestListWorkersPaginateTypeDef",
     "ListSitesResponseTypeDef",
     "ListWorkerFleetsResponseTypeDef",
     "CreateWorkerRequestRequestTypeDef",
     "GetWorkerResponseTypeDef",
     "UpdateWorkerRequestRequestTypeDef",
     "UpdateWorkerResponseTypeDef",
     "WorkerTypeDef",
@@ -118,22 +118,23 @@
 
 class CreateDestinationRequestRequestTypeDef(
     _RequiredCreateDestinationRequestRequestTypeDef, _OptionalCreateDestinationRequestRequestTypeDef
 ):
     pass
 
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateDestinationResponseTypeDef = TypedDict(
+    "CreateDestinationResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "arn": str,
+        "id": str,
+        "createdAt": datetime,
+        "updatedAt": datetime,
+        "state": DestinationStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateSiteRequestRequestTypeDef = TypedDict(
     "_RequiredCreateSiteRequestRequestTypeDef",
     {
         "name": str,
@@ -152,14 +153,25 @@
 
 class CreateSiteRequestRequestTypeDef(
     _RequiredCreateSiteRequestRequestTypeDef, _OptionalCreateSiteRequestRequestTypeDef
 ):
     pass
 
 
+CreateSiteResponseTypeDef = TypedDict(
+    "CreateSiteResponseTypeDef",
+    {
+        "arn": str,
+        "id": str,
+        "createdAt": datetime,
+        "updatedAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateWorkerFleetRequestRequestTypeDef = TypedDict(
     "_RequiredCreateWorkerFleetRequestRequestTypeDef",
     {
         "name": str,
         "site": str,
     },
 )
@@ -175,14 +187,25 @@
 
 class CreateWorkerFleetRequestRequestTypeDef(
     _RequiredCreateWorkerFleetRequestRequestTypeDef, _OptionalCreateWorkerFleetRequestRequestTypeDef
 ):
     pass
 
 
+CreateWorkerFleetResponseTypeDef = TypedDict(
+    "CreateWorkerFleetResponseTypeDef",
+    {
+        "arn": str,
+        "id": str,
+        "createdAt": datetime,
+        "updatedAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 OrientationTypeDef = TypedDict(
     "OrientationTypeDef",
     {
         "degrees": float,
     },
     total=False,
 )
@@ -204,14 +227,26 @@
 )
 
 
 class VendorPropertiesTypeDef(_RequiredVendorPropertiesTypeDef, _OptionalVendorPropertiesTypeDef):
     pass
 
 
+CreateWorkerResponseTypeDef = TypedDict(
+    "CreateWorkerResponseTypeDef",
+    {
+        "arn": str,
+        "id": str,
+        "createdAt": datetime,
+        "updatedAt": datetime,
+        "site": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteDestinationRequestRequestTypeDef = TypedDict(
     "DeleteDestinationRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
@@ -264,45 +299,101 @@
 GetDestinationRequestRequestTypeDef = TypedDict(
     "GetDestinationRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
+GetDestinationResponseTypeDef = TypedDict(
+    "GetDestinationResponseTypeDef",
+    {
+        "arn": str,
+        "id": str,
+        "name": str,
+        "site": str,
+        "createdAt": datetime,
+        "updatedAt": datetime,
+        "state": DestinationStateType,
+        "additionalFixedProperties": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetSiteRequestRequestTypeDef = TypedDict(
     "GetSiteRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
+GetSiteResponseTypeDef = TypedDict(
+    "GetSiteResponseTypeDef",
+    {
+        "arn": str,
+        "id": str,
+        "name": str,
+        "countryCode": str,
+        "description": str,
+        "createdAt": datetime,
+        "updatedAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetWorkerFleetRequestRequestTypeDef = TypedDict(
     "GetWorkerFleetRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
+GetWorkerFleetResponseTypeDef = TypedDict(
+    "GetWorkerFleetResponseTypeDef",
+    {
+        "id": str,
+        "arn": str,
+        "name": str,
+        "site": str,
+        "createdAt": datetime,
+        "updatedAt": datetime,
+        "additionalFixedProperties": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetWorkerRequestRequestTypeDef = TypedDict(
     "GetWorkerRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListDestinationsRequestListDestinationsPaginateTypeDef = TypedDict(
+    "_RequiredListDestinationsRequestListDestinationsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "site": str,
+    },
+)
+_OptionalListDestinationsRequestListDestinationsPaginateTypeDef = TypedDict(
+    "_OptionalListDestinationsRequestListDestinationsPaginateTypeDef",
+    {
+        "state": DestinationStateType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListDestinationsRequestListDestinationsPaginateTypeDef(
+    _RequiredListDestinationsRequestListDestinationsPaginateTypeDef,
+    _OptionalListDestinationsRequestListDestinationsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListDestinationsRequestRequestTypeDef = TypedDict(
     "_RequiredListDestinationsRequestRequestTypeDef",
     {
         "site": str,
     },
 )
 _OptionalListDestinationsRequestRequestTypeDef = TypedDict(
@@ -318,14 +409,22 @@
 
 class ListDestinationsRequestRequestTypeDef(
     _RequiredListDestinationsRequestRequestTypeDef, _OptionalListDestinationsRequestRequestTypeDef
 ):
     pass
 
 
+ListSitesRequestListSitesPaginateTypeDef = TypedDict(
+    "ListSitesRequestListSitesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSitesRequestRequestTypeDef = TypedDict(
     "ListSitesRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -337,14 +436,36 @@
         "arn": str,
         "name": str,
         "countryCode": str,
         "createdAt": datetime,
     },
 )
 
+_RequiredListWorkerFleetsRequestListWorkerFleetsPaginateTypeDef = TypedDict(
+    "_RequiredListWorkerFleetsRequestListWorkerFleetsPaginateTypeDef",
+    {
+        "site": str,
+    },
+)
+_OptionalListWorkerFleetsRequestListWorkerFleetsPaginateTypeDef = TypedDict(
+    "_OptionalListWorkerFleetsRequestListWorkerFleetsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListWorkerFleetsRequestListWorkerFleetsPaginateTypeDef(
+    _RequiredListWorkerFleetsRequestListWorkerFleetsPaginateTypeDef,
+    _OptionalListWorkerFleetsRequestListWorkerFleetsPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListWorkerFleetsRequestRequestTypeDef = TypedDict(
     "_RequiredListWorkerFleetsRequestRequestTypeDef",
     {
         "site": str,
     },
 )
 _OptionalListWorkerFleetsRequestRequestTypeDef = TypedDict(
@@ -383,14 +504,37 @@
 )
 
 
 class WorkerFleetTypeDef(_RequiredWorkerFleetTypeDef, _OptionalWorkerFleetTypeDef):
     pass
 
 
+_RequiredListWorkersRequestListWorkersPaginateTypeDef = TypedDict(
+    "_RequiredListWorkersRequestListWorkersPaginateTypeDef",
+    {
+        "site": str,
+    },
+)
+_OptionalListWorkersRequestListWorkersPaginateTypeDef = TypedDict(
+    "_OptionalListWorkersRequestListWorkersPaginateTypeDef",
+    {
+        "fleet": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListWorkersRequestListWorkersPaginateTypeDef(
+    _RequiredListWorkersRequestListWorkersPaginateTypeDef,
+    _OptionalListWorkersRequestListWorkersPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListWorkersRequestRequestTypeDef = TypedDict(
     "_RequiredListWorkersRequestRequestTypeDef",
     {
         "site": str,
     },
 )
 _OptionalListWorkersRequestRequestTypeDef = TypedDict(
@@ -406,14 +550,35 @@
 
 class ListWorkersRequestRequestTypeDef(
     _RequiredListWorkersRequestRequestTypeDef, _OptionalListWorkersRequestRequestTypeDef
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
 _RequiredUpdateDestinationRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateDestinationRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 _OptionalUpdateDestinationRequestRequestTypeDef = TypedDict(
@@ -429,14 +594,27 @@
 
 class UpdateDestinationRequestRequestTypeDef(
     _RequiredUpdateDestinationRequestRequestTypeDef, _OptionalUpdateDestinationRequestRequestTypeDef
 ):
     pass
 
 
+UpdateDestinationResponseTypeDef = TypedDict(
+    "UpdateDestinationResponseTypeDef",
+    {
+        "arn": str,
+        "id": str,
+        "name": str,
+        "updatedAt": datetime,
+        "state": DestinationStateType,
+        "additionalFixedProperties": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateSiteRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateSiteRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 _OptionalUpdateSiteRequestRequestTypeDef = TypedDict(
@@ -452,14 +630,27 @@
 
 class UpdateSiteRequestRequestTypeDef(
     _RequiredUpdateSiteRequestRequestTypeDef, _OptionalUpdateSiteRequestRequestTypeDef
 ):
     pass
 
 
+UpdateSiteResponseTypeDef = TypedDict(
+    "UpdateSiteResponseTypeDef",
+    {
+        "arn": str,
+        "id": str,
+        "name": str,
+        "countryCode": str,
+        "description": str,
+        "updatedAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateWorkerFleetRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateWorkerFleetRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 _OptionalUpdateWorkerFleetRequestRequestTypeDef = TypedDict(
@@ -474,249 +665,58 @@
 
 class UpdateWorkerFleetRequestRequestTypeDef(
     _RequiredUpdateWorkerFleetRequestRequestTypeDef, _OptionalUpdateWorkerFleetRequestRequestTypeDef
 ):
     pass
 
 
-PositionCoordinatesTypeDef = TypedDict(
-    "PositionCoordinatesTypeDef",
-    {
-        "cartesianCoordinates": CartesianCoordinatesTypeDef,
-    },
-    total=False,
-)
-
-CreateDestinationResponseTypeDef = TypedDict(
-    "CreateDestinationResponseTypeDef",
-    {
-        "arn": str,
-        "id": str,
-        "createdAt": datetime,
-        "updatedAt": datetime,
-        "state": DestinationStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateSiteResponseTypeDef = TypedDict(
-    "CreateSiteResponseTypeDef",
-    {
-        "arn": str,
-        "id": str,
-        "createdAt": datetime,
-        "updatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateWorkerFleetResponseTypeDef = TypedDict(
-    "CreateWorkerFleetResponseTypeDef",
-    {
-        "arn": str,
-        "id": str,
-        "createdAt": datetime,
-        "updatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateWorkerResponseTypeDef = TypedDict(
-    "CreateWorkerResponseTypeDef",
-    {
-        "arn": str,
-        "id": str,
-        "createdAt": datetime,
-        "updatedAt": datetime,
-        "site": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetDestinationResponseTypeDef = TypedDict(
-    "GetDestinationResponseTypeDef",
-    {
-        "arn": str,
-        "id": str,
-        "name": str,
-        "site": str,
-        "createdAt": datetime,
-        "updatedAt": datetime,
-        "state": DestinationStateType,
-        "additionalFixedProperties": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSiteResponseTypeDef = TypedDict(
-    "GetSiteResponseTypeDef",
-    {
-        "arn": str,
-        "id": str,
-        "name": str,
-        "countryCode": str,
-        "description": str,
-        "createdAt": datetime,
-        "updatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetWorkerFleetResponseTypeDef = TypedDict(
-    "GetWorkerFleetResponseTypeDef",
-    {
-        "id": str,
-        "arn": str,
-        "name": str,
-        "site": str,
-        "createdAt": datetime,
-        "updatedAt": datetime,
-        "additionalFixedProperties": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateDestinationResponseTypeDef = TypedDict(
-    "UpdateDestinationResponseTypeDef",
+UpdateWorkerFleetResponseTypeDef = TypedDict(
+    "UpdateWorkerFleetResponseTypeDef",
     {
         "arn": str,
         "id": str,
         "name": str,
         "updatedAt": datetime,
-        "state": DestinationStateType,
         "additionalFixedProperties": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-UpdateSiteResponseTypeDef = TypedDict(
-    "UpdateSiteResponseTypeDef",
-    {
-        "arn": str,
-        "id": str,
-        "name": str,
-        "countryCode": str,
-        "description": str,
-        "updatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-UpdateWorkerFleetResponseTypeDef = TypedDict(
-    "UpdateWorkerFleetResponseTypeDef",
+PositionCoordinatesTypeDef = TypedDict(
+    "PositionCoordinatesTypeDef",
     {
-        "arn": str,
-        "id": str,
-        "name": str,
-        "updatedAt": datetime,
-        "additionalFixedProperties": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "cartesianCoordinates": CartesianCoordinatesTypeDef,
     },
+    total=False,
 )
 
 ListDestinationsResponseTypeDef = TypedDict(
     "ListDestinationsResponseTypeDef",
     {
         "nextToken": str,
         "destinations": List[DestinationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredListDestinationsRequestListDestinationsPaginateTypeDef = TypedDict(
-    "_RequiredListDestinationsRequestListDestinationsPaginateTypeDef",
-    {
-        "site": str,
-    },
-)
-_OptionalListDestinationsRequestListDestinationsPaginateTypeDef = TypedDict(
-    "_OptionalListDestinationsRequestListDestinationsPaginateTypeDef",
-    {
-        "state": DestinationStateType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListDestinationsRequestListDestinationsPaginateTypeDef(
-    _RequiredListDestinationsRequestListDestinationsPaginateTypeDef,
-    _OptionalListDestinationsRequestListDestinationsPaginateTypeDef,
-):
-    pass
-
-
-ListSitesRequestListSitesPaginateTypeDef = TypedDict(
-    "ListSitesRequestListSitesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-_RequiredListWorkerFleetsRequestListWorkerFleetsPaginateTypeDef = TypedDict(
-    "_RequiredListWorkerFleetsRequestListWorkerFleetsPaginateTypeDef",
-    {
-        "site": str,
-    },
-)
-_OptionalListWorkerFleetsRequestListWorkerFleetsPaginateTypeDef = TypedDict(
-    "_OptionalListWorkerFleetsRequestListWorkerFleetsPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListWorkerFleetsRequestListWorkerFleetsPaginateTypeDef(
-    _RequiredListWorkerFleetsRequestListWorkerFleetsPaginateTypeDef,
-    _OptionalListWorkerFleetsRequestListWorkerFleetsPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListWorkersRequestListWorkersPaginateTypeDef = TypedDict(
-    "_RequiredListWorkersRequestListWorkersPaginateTypeDef",
-    {
-        "site": str,
-    },
-)
-_OptionalListWorkersRequestListWorkersPaginateTypeDef = TypedDict(
-    "_OptionalListWorkersRequestListWorkersPaginateTypeDef",
-    {
-        "fleet": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListWorkersRequestListWorkersPaginateTypeDef(
-    _RequiredListWorkersRequestListWorkersPaginateTypeDef,
-    _OptionalListWorkersRequestListWorkersPaginateTypeDef,
-):
-    pass
-
-
 ListSitesResponseTypeDef = TypedDict(
     "ListSitesResponseTypeDef",
     {
         "nextToken": str,
         "sites": List[SiteTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListWorkerFleetsResponseTypeDef = TypedDict(
     "ListWorkerFleetsResponseTypeDef",
     {
         "nextToken": str,
         "workerFleets": List[WorkerFleetTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateWorkerRequestRequestTypeDef = TypedDict(
     "_RequiredCreateWorkerRequestRequestTypeDef",
     {
         "name": str,
@@ -754,15 +754,15 @@
         "updatedAt": datetime,
         "name": str,
         "additionalTransientProperties": str,
         "additionalFixedProperties": str,
         "vendorProperties": VendorPropertiesTypeDef,
         "position": PositionCoordinatesTypeDef,
         "orientation": OrientationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateWorkerRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateWorkerRequestRequestTypeDef",
     {
         "id": str,
@@ -797,15 +797,15 @@
         "updatedAt": datetime,
         "name": str,
         "additionalTransientProperties": str,
         "additionalFixedProperties": str,
         "orientation": OrientationTypeDef,
         "vendorProperties": VendorPropertiesTypeDef,
         "position": PositionCoordinatesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredWorkerTypeDef = TypedDict(
     "_RequiredWorkerTypeDef",
     {
         "arn": str,
@@ -835,10 +835,10 @@
 
 
 ListWorkersResponseTypeDef = TypedDict(
     "ListWorkersResponseTypeDef",
     {
         "nextToken": str,
         "workers": List[WorkerTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-iot-roborunner-2.5.0.post1/types_aiobotocore_iot_roborunner/type_defs.pyi` & `types-aiobotocore-iot-roborunner-2.5.1/types_aiobotocore_iot_roborunner/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -21,54 +21,54 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "CartesianCoordinatesTypeDef",
     "CreateDestinationRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
+    "CreateDestinationResponseTypeDef",
     "CreateSiteRequestRequestTypeDef",
+    "CreateSiteResponseTypeDef",
     "CreateWorkerFleetRequestRequestTypeDef",
+    "CreateWorkerFleetResponseTypeDef",
     "OrientationTypeDef",
     "VendorPropertiesTypeDef",
+    "CreateWorkerResponseTypeDef",
     "DeleteDestinationRequestRequestTypeDef",
     "DeleteSiteRequestRequestTypeDef",
     "DeleteWorkerFleetRequestRequestTypeDef",
     "DeleteWorkerRequestRequestTypeDef",
     "DestinationTypeDef",
     "GetDestinationRequestRequestTypeDef",
+    "GetDestinationResponseTypeDef",
     "GetSiteRequestRequestTypeDef",
+    "GetSiteResponseTypeDef",
     "GetWorkerFleetRequestRequestTypeDef",
+    "GetWorkerFleetResponseTypeDef",
     "GetWorkerRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListDestinationsRequestListDestinationsPaginateTypeDef",
     "ListDestinationsRequestRequestTypeDef",
+    "ListSitesRequestListSitesPaginateTypeDef",
     "ListSitesRequestRequestTypeDef",
     "SiteTypeDef",
+    "ListWorkerFleetsRequestListWorkerFleetsPaginateTypeDef",
     "ListWorkerFleetsRequestRequestTypeDef",
     "WorkerFleetTypeDef",
+    "ListWorkersRequestListWorkersPaginateTypeDef",
     "ListWorkersRequestRequestTypeDef",
+    "PaginatorConfigTypeDef",
+    "ResponseMetadataTypeDef",
     "UpdateDestinationRequestRequestTypeDef",
-    "UpdateSiteRequestRequestTypeDef",
-    "UpdateWorkerFleetRequestRequestTypeDef",
-    "PositionCoordinatesTypeDef",
-    "CreateDestinationResponseTypeDef",
-    "CreateSiteResponseTypeDef",
-    "CreateWorkerFleetResponseTypeDef",
-    "CreateWorkerResponseTypeDef",
-    "GetDestinationResponseTypeDef",
-    "GetSiteResponseTypeDef",
-    "GetWorkerFleetResponseTypeDef",
     "UpdateDestinationResponseTypeDef",
+    "UpdateSiteRequestRequestTypeDef",
     "UpdateSiteResponseTypeDef",
+    "UpdateWorkerFleetRequestRequestTypeDef",
     "UpdateWorkerFleetResponseTypeDef",
+    "PositionCoordinatesTypeDef",
     "ListDestinationsResponseTypeDef",
-    "ListDestinationsRequestListDestinationsPaginateTypeDef",
-    "ListSitesRequestListSitesPaginateTypeDef",
-    "ListWorkerFleetsRequestListWorkerFleetsPaginateTypeDef",
-    "ListWorkersRequestListWorkersPaginateTypeDef",
     "ListSitesResponseTypeDef",
     "ListWorkerFleetsResponseTypeDef",
     "CreateWorkerRequestRequestTypeDef",
     "GetWorkerResponseTypeDef",
     "UpdateWorkerRequestRequestTypeDef",
     "UpdateWorkerResponseTypeDef",
     "WorkerTypeDef",
@@ -113,22 +113,23 @@
 )
 
 class CreateDestinationRequestRequestTypeDef(
     _RequiredCreateDestinationRequestRequestTypeDef, _OptionalCreateDestinationRequestRequestTypeDef
 ):
     pass
 
-ResponseMetadataTypeDef = TypedDict(
-    "ResponseMetadataTypeDef",
+CreateDestinationResponseTypeDef = TypedDict(
+    "CreateDestinationResponseTypeDef",
     {
-        "RequestId": str,
-        "HostId": str,
-        "HTTPStatusCode": int,
-        "HTTPHeaders": Dict[str, str],
-        "RetryAttempts": int,
+        "arn": str,
+        "id": str,
+        "createdAt": datetime,
+        "updatedAt": datetime,
+        "state": DestinationStateType,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateSiteRequestRequestTypeDef = TypedDict(
     "_RequiredCreateSiteRequestRequestTypeDef",
     {
         "name": str,
@@ -145,14 +146,25 @@
 )
 
 class CreateSiteRequestRequestTypeDef(
     _RequiredCreateSiteRequestRequestTypeDef, _OptionalCreateSiteRequestRequestTypeDef
 ):
     pass
 
+CreateSiteResponseTypeDef = TypedDict(
+    "CreateSiteResponseTypeDef",
+    {
+        "arn": str,
+        "id": str,
+        "createdAt": datetime,
+        "updatedAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredCreateWorkerFleetRequestRequestTypeDef = TypedDict(
     "_RequiredCreateWorkerFleetRequestRequestTypeDef",
     {
         "name": str,
         "site": str,
     },
 )
@@ -166,14 +178,25 @@
 )
 
 class CreateWorkerFleetRequestRequestTypeDef(
     _RequiredCreateWorkerFleetRequestRequestTypeDef, _OptionalCreateWorkerFleetRequestRequestTypeDef
 ):
     pass
 
+CreateWorkerFleetResponseTypeDef = TypedDict(
+    "CreateWorkerFleetResponseTypeDef",
+    {
+        "arn": str,
+        "id": str,
+        "createdAt": datetime,
+        "updatedAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 OrientationTypeDef = TypedDict(
     "OrientationTypeDef",
     {
         "degrees": float,
     },
     total=False,
 )
@@ -193,14 +216,26 @@
     },
     total=False,
 )
 
 class VendorPropertiesTypeDef(_RequiredVendorPropertiesTypeDef, _OptionalVendorPropertiesTypeDef):
     pass
 
+CreateWorkerResponseTypeDef = TypedDict(
+    "CreateWorkerResponseTypeDef",
+    {
+        "arn": str,
+        "id": str,
+        "createdAt": datetime,
+        "updatedAt": datetime,
+        "site": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 DeleteDestinationRequestRequestTypeDef = TypedDict(
     "DeleteDestinationRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
@@ -251,45 +286,99 @@
 GetDestinationRequestRequestTypeDef = TypedDict(
     "GetDestinationRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
+GetDestinationResponseTypeDef = TypedDict(
+    "GetDestinationResponseTypeDef",
+    {
+        "arn": str,
+        "id": str,
+        "name": str,
+        "site": str,
+        "createdAt": datetime,
+        "updatedAt": datetime,
+        "state": DestinationStateType,
+        "additionalFixedProperties": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetSiteRequestRequestTypeDef = TypedDict(
     "GetSiteRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
+GetSiteResponseTypeDef = TypedDict(
+    "GetSiteResponseTypeDef",
+    {
+        "arn": str,
+        "id": str,
+        "name": str,
+        "countryCode": str,
+        "description": str,
+        "createdAt": datetime,
+        "updatedAt": datetime,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetWorkerFleetRequestRequestTypeDef = TypedDict(
     "GetWorkerFleetRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
+GetWorkerFleetResponseTypeDef = TypedDict(
+    "GetWorkerFleetResponseTypeDef",
+    {
+        "id": str,
+        "arn": str,
+        "name": str,
+        "site": str,
+        "createdAt": datetime,
+        "updatedAt": datetime,
+        "additionalFixedProperties": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 GetWorkerRequestRequestTypeDef = TypedDict(
     "GetWorkerRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListDestinationsRequestListDestinationsPaginateTypeDef = TypedDict(
+    "_RequiredListDestinationsRequestListDestinationsPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "site": str,
+    },
+)
+_OptionalListDestinationsRequestListDestinationsPaginateTypeDef = TypedDict(
+    "_OptionalListDestinationsRequestListDestinationsPaginateTypeDef",
+    {
+        "state": DestinationStateType,
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListDestinationsRequestListDestinationsPaginateTypeDef(
+    _RequiredListDestinationsRequestListDestinationsPaginateTypeDef,
+    _OptionalListDestinationsRequestListDestinationsPaginateTypeDef,
+):
+    pass
+
 _RequiredListDestinationsRequestRequestTypeDef = TypedDict(
     "_RequiredListDestinationsRequestRequestTypeDef",
     {
         "site": str,
     },
 )
 _OptionalListDestinationsRequestRequestTypeDef = TypedDict(
@@ -303,14 +392,22 @@
 )
 
 class ListDestinationsRequestRequestTypeDef(
     _RequiredListDestinationsRequestRequestTypeDef, _OptionalListDestinationsRequestRequestTypeDef
 ):
     pass
 
+ListSitesRequestListSitesPaginateTypeDef = TypedDict(
+    "ListSitesRequestListSitesPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListSitesRequestRequestTypeDef = TypedDict(
     "ListSitesRequestRequestTypeDef",
     {
         "maxResults": int,
         "nextToken": str,
     },
     total=False,
@@ -322,14 +419,34 @@
         "arn": str,
         "name": str,
         "countryCode": str,
         "createdAt": datetime,
     },
 )
 
+_RequiredListWorkerFleetsRequestListWorkerFleetsPaginateTypeDef = TypedDict(
+    "_RequiredListWorkerFleetsRequestListWorkerFleetsPaginateTypeDef",
+    {
+        "site": str,
+    },
+)
+_OptionalListWorkerFleetsRequestListWorkerFleetsPaginateTypeDef = TypedDict(
+    "_OptionalListWorkerFleetsRequestListWorkerFleetsPaginateTypeDef",
+    {
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListWorkerFleetsRequestListWorkerFleetsPaginateTypeDef(
+    _RequiredListWorkerFleetsRequestListWorkerFleetsPaginateTypeDef,
+    _OptionalListWorkerFleetsRequestListWorkerFleetsPaginateTypeDef,
+):
+    pass
+
 _RequiredListWorkerFleetsRequestRequestTypeDef = TypedDict(
     "_RequiredListWorkerFleetsRequestRequestTypeDef",
     {
         "site": str,
     },
 )
 _OptionalListWorkerFleetsRequestRequestTypeDef = TypedDict(
@@ -364,14 +481,35 @@
     },
     total=False,
 )
 
 class WorkerFleetTypeDef(_RequiredWorkerFleetTypeDef, _OptionalWorkerFleetTypeDef):
     pass
 
+_RequiredListWorkersRequestListWorkersPaginateTypeDef = TypedDict(
+    "_RequiredListWorkersRequestListWorkersPaginateTypeDef",
+    {
+        "site": str,
+    },
+)
+_OptionalListWorkersRequestListWorkersPaginateTypeDef = TypedDict(
+    "_OptionalListWorkersRequestListWorkersPaginateTypeDef",
+    {
+        "fleet": str,
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListWorkersRequestListWorkersPaginateTypeDef(
+    _RequiredListWorkersRequestListWorkersPaginateTypeDef,
+    _OptionalListWorkersRequestListWorkersPaginateTypeDef,
+):
+    pass
+
 _RequiredListWorkersRequestRequestTypeDef = TypedDict(
     "_RequiredListWorkersRequestRequestTypeDef",
     {
         "site": str,
     },
 )
 _OptionalListWorkersRequestRequestTypeDef = TypedDict(
@@ -385,14 +523,35 @@
 )
 
 class ListWorkersRequestRequestTypeDef(
     _RequiredListWorkersRequestRequestTypeDef, _OptionalListWorkersRequestRequestTypeDef
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
 _RequiredUpdateDestinationRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateDestinationRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 _OptionalUpdateDestinationRequestRequestTypeDef = TypedDict(
@@ -406,14 +565,27 @@
 )
 
 class UpdateDestinationRequestRequestTypeDef(
     _RequiredUpdateDestinationRequestRequestTypeDef, _OptionalUpdateDestinationRequestRequestTypeDef
 ):
     pass
 
+UpdateDestinationResponseTypeDef = TypedDict(
+    "UpdateDestinationResponseTypeDef",
+    {
+        "arn": str,
+        "id": str,
+        "name": str,
+        "updatedAt": datetime,
+        "state": DestinationStateType,
+        "additionalFixedProperties": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredUpdateSiteRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateSiteRequestRequestTypeDef",
     {
         "id": str,
     },
 )
 _OptionalUpdateSiteRequestRequestTypeDef = TypedDict(
@@ -427,263 +599,91 @@
 )
 
 class UpdateSiteRequestRequestTypeDef(
     _RequiredUpdateSiteRequestRequestTypeDef, _OptionalUpdateSiteRequestRequestTypeDef
 ):
     pass
 
-_RequiredUpdateWorkerFleetRequestRequestTypeDef = TypedDict(
-    "_RequiredUpdateWorkerFleetRequestRequestTypeDef",
-    {
-        "id": str,
-    },
-)
-_OptionalUpdateWorkerFleetRequestRequestTypeDef = TypedDict(
-    "_OptionalUpdateWorkerFleetRequestRequestTypeDef",
-    {
-        "name": str,
-        "additionalFixedProperties": str,
-    },
-    total=False,
-)
-
-class UpdateWorkerFleetRequestRequestTypeDef(
-    _RequiredUpdateWorkerFleetRequestRequestTypeDef, _OptionalUpdateWorkerFleetRequestRequestTypeDef
-):
-    pass
-
-PositionCoordinatesTypeDef = TypedDict(
-    "PositionCoordinatesTypeDef",
-    {
-        "cartesianCoordinates": CartesianCoordinatesTypeDef,
-    },
-    total=False,
-)
-
-CreateDestinationResponseTypeDef = TypedDict(
-    "CreateDestinationResponseTypeDef",
-    {
-        "arn": str,
-        "id": str,
-        "createdAt": datetime,
-        "updatedAt": datetime,
-        "state": DestinationStateType,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateSiteResponseTypeDef = TypedDict(
-    "CreateSiteResponseTypeDef",
-    {
-        "arn": str,
-        "id": str,
-        "createdAt": datetime,
-        "updatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateWorkerFleetResponseTypeDef = TypedDict(
-    "CreateWorkerFleetResponseTypeDef",
-    {
-        "arn": str,
-        "id": str,
-        "createdAt": datetime,
-        "updatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-CreateWorkerResponseTypeDef = TypedDict(
-    "CreateWorkerResponseTypeDef",
-    {
-        "arn": str,
-        "id": str,
-        "createdAt": datetime,
-        "updatedAt": datetime,
-        "site": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetDestinationResponseTypeDef = TypedDict(
-    "GetDestinationResponseTypeDef",
-    {
-        "arn": str,
-        "id": str,
-        "name": str,
-        "site": str,
-        "createdAt": datetime,
-        "updatedAt": datetime,
-        "state": DestinationStateType,
-        "additionalFixedProperties": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-GetSiteResponseTypeDef = TypedDict(
-    "GetSiteResponseTypeDef",
+UpdateSiteResponseTypeDef = TypedDict(
+    "UpdateSiteResponseTypeDef",
     {
         "arn": str,
         "id": str,
         "name": str,
         "countryCode": str,
         "description": str,
-        "createdAt": datetime,
         "updatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-GetWorkerFleetResponseTypeDef = TypedDict(
-    "GetWorkerFleetResponseTypeDef",
+_RequiredUpdateWorkerFleetRequestRequestTypeDef = TypedDict(
+    "_RequiredUpdateWorkerFleetRequestRequestTypeDef",
     {
         "id": str,
-        "arn": str,
-        "name": str,
-        "site": str,
-        "createdAt": datetime,
-        "updatedAt": datetime,
-        "additionalFixedProperties": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
 )
-
-UpdateDestinationResponseTypeDef = TypedDict(
-    "UpdateDestinationResponseTypeDef",
+_OptionalUpdateWorkerFleetRequestRequestTypeDef = TypedDict(
+    "_OptionalUpdateWorkerFleetRequestRequestTypeDef",
     {
-        "arn": str,
-        "id": str,
         "name": str,
-        "updatedAt": datetime,
-        "state": DestinationStateType,
         "additionalFixedProperties": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
     },
+    total=False,
 )
 
-UpdateSiteResponseTypeDef = TypedDict(
-    "UpdateSiteResponseTypeDef",
-    {
-        "arn": str,
-        "id": str,
-        "name": str,
-        "countryCode": str,
-        "description": str,
-        "updatedAt": datetime,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
+class UpdateWorkerFleetRequestRequestTypeDef(
+    _RequiredUpdateWorkerFleetRequestRequestTypeDef, _OptionalUpdateWorkerFleetRequestRequestTypeDef
+):
+    pass
 
 UpdateWorkerFleetResponseTypeDef = TypedDict(
     "UpdateWorkerFleetResponseTypeDef",
     {
         "arn": str,
         "id": str,
         "name": str,
         "updatedAt": datetime,
         "additionalFixedProperties": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-ListDestinationsResponseTypeDef = TypedDict(
-    "ListDestinationsResponseTypeDef",
-    {
-        "nextToken": str,
-        "destinations": List[DestinationTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
-_RequiredListDestinationsRequestListDestinationsPaginateTypeDef = TypedDict(
-    "_RequiredListDestinationsRequestListDestinationsPaginateTypeDef",
-    {
-        "site": str,
-    },
-)
-_OptionalListDestinationsRequestListDestinationsPaginateTypeDef = TypedDict(
-    "_OptionalListDestinationsRequestListDestinationsPaginateTypeDef",
-    {
-        "state": DestinationStateType,
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListDestinationsRequestListDestinationsPaginateTypeDef(
-    _RequiredListDestinationsRequestListDestinationsPaginateTypeDef,
-    _OptionalListDestinationsRequestListDestinationsPaginateTypeDef,
-):
-    pass
-
-ListSitesRequestListSitesPaginateTypeDef = TypedDict(
-    "ListSitesRequestListSitesPaginateTypeDef",
-    {
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListWorkerFleetsRequestListWorkerFleetsPaginateTypeDef = TypedDict(
-    "_RequiredListWorkerFleetsRequestListWorkerFleetsPaginateTypeDef",
-    {
-        "site": str,
-    },
-)
-_OptionalListWorkerFleetsRequestListWorkerFleetsPaginateTypeDef = TypedDict(
-    "_OptionalListWorkerFleetsRequestListWorkerFleetsPaginateTypeDef",
+PositionCoordinatesTypeDef = TypedDict(
+    "PositionCoordinatesTypeDef",
     {
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "cartesianCoordinates": CartesianCoordinatesTypeDef,
     },
     total=False,
 )
 
-class ListWorkerFleetsRequestListWorkerFleetsPaginateTypeDef(
-    _RequiredListWorkerFleetsRequestListWorkerFleetsPaginateTypeDef,
-    _OptionalListWorkerFleetsRequestListWorkerFleetsPaginateTypeDef,
-):
-    pass
-
-_RequiredListWorkersRequestListWorkersPaginateTypeDef = TypedDict(
-    "_RequiredListWorkersRequestListWorkersPaginateTypeDef",
-    {
-        "site": str,
-    },
-)
-_OptionalListWorkersRequestListWorkersPaginateTypeDef = TypedDict(
-    "_OptionalListWorkersRequestListWorkersPaginateTypeDef",
+ListDestinationsResponseTypeDef = TypedDict(
+    "ListDestinationsResponseTypeDef",
     {
-        "fleet": str,
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "nextToken": str,
+        "destinations": List[DestinationTypeDef],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-class ListWorkersRequestListWorkersPaginateTypeDef(
-    _RequiredListWorkersRequestListWorkersPaginateTypeDef,
-    _OptionalListWorkersRequestListWorkersPaginateTypeDef,
-):
-    pass
-
 ListSitesResponseTypeDef = TypedDict(
     "ListSitesResponseTypeDef",
     {
         "nextToken": str,
         "sites": List[SiteTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListWorkerFleetsResponseTypeDef = TypedDict(
     "ListWorkerFleetsResponseTypeDef",
     {
         "nextToken": str,
         "workerFleets": List[WorkerFleetTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateWorkerRequestRequestTypeDef = TypedDict(
     "_RequiredCreateWorkerRequestRequestTypeDef",
     {
         "name": str,
@@ -719,15 +719,15 @@
         "updatedAt": datetime,
         "name": str,
         "additionalTransientProperties": str,
         "additionalFixedProperties": str,
         "vendorProperties": VendorPropertiesTypeDef,
         "position": PositionCoordinatesTypeDef,
         "orientation": OrientationTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredUpdateWorkerRequestRequestTypeDef = TypedDict(
     "_RequiredUpdateWorkerRequestRequestTypeDef",
     {
         "id": str,
@@ -760,15 +760,15 @@
         "updatedAt": datetime,
         "name": str,
         "additionalTransientProperties": str,
         "additionalFixedProperties": str,
         "orientation": OrientationTypeDef,
         "vendorProperties": VendorPropertiesTypeDef,
         "position": PositionCoordinatesTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredWorkerTypeDef = TypedDict(
     "_RequiredWorkerTypeDef",
     {
         "arn": str,
@@ -796,10 +796,10 @@
     pass
 
 ListWorkersResponseTypeDef = TypedDict(
     "ListWorkersResponseTypeDef",
     {
         "nextToken": str,
         "workers": List[WorkerTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-iot-roborunner-2.5.0.post1/types_aiobotocore_iot_roborunner.egg-info/PKG-INFO` & `types-aiobotocore-iot-roborunner-2.5.1/types_aiobotocore_iot_roborunner.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-iot-roborunner
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.IoTRoboRunner 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.IoTRoboRunner 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_roborunner/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-iot-roborunner"></a>
 
 # types-aiobotocore-iot-roborunner
 
 [![PyPI - types-aiobotocore-iot-roborunner](https://img.shields.io/pypi/v/types-aiobotocore-iot-roborunner.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iot-roborunner)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-iot-roborunner.svg?color=blue)](https://pypi.org/project/types-aiobotocore-iot-roborunner)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_roborunner/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-iot-roborunner?color=blue)](https://pypistats.org/packages/types-aiobotocore-iot-roborunner)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.IoTRoboRunner 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot-roborunner.html#IoTRoboRunner)
+[aiobotocore.IoTRoboRunner 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/iot-roborunner.html#IoTRoboRunner)
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
 [types-aiobotocore-iot-roborunner docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_roborunner/).
 
 See how it helps to find and fix potential bugs:
 
@@ -332,54 +332,54 @@
 `types_aiobotocore_iot_roborunner.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_iot_roborunner.type_defs import (
     CartesianCoordinatesTypeDef,
     CreateDestinationRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
+    CreateDestinationResponseTypeDef,
     CreateSiteRequestRequestTypeDef,
+    CreateSiteResponseTypeDef,
     CreateWorkerFleetRequestRequestTypeDef,
+    CreateWorkerFleetResponseTypeDef,
     OrientationTypeDef,
     VendorPropertiesTypeDef,
+    CreateWorkerResponseTypeDef,
     DeleteDestinationRequestRequestTypeDef,
     DeleteSiteRequestRequestTypeDef,
     DeleteWorkerFleetRequestRequestTypeDef,
     DeleteWorkerRequestRequestTypeDef,
     DestinationTypeDef,
     GetDestinationRequestRequestTypeDef,
+    GetDestinationResponseTypeDef,
     GetSiteRequestRequestTypeDef,
+    GetSiteResponseTypeDef,
     GetWorkerFleetRequestRequestTypeDef,
+    GetWorkerFleetResponseTypeDef,
     GetWorkerRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListDestinationsRequestListDestinationsPaginateTypeDef,
     ListDestinationsRequestRequestTypeDef,
+    ListSitesRequestListSitesPaginateTypeDef,
     ListSitesRequestRequestTypeDef,
     SiteTypeDef,
+    ListWorkerFleetsRequestListWorkerFleetsPaginateTypeDef,
     ListWorkerFleetsRequestRequestTypeDef,
     WorkerFleetTypeDef,
+    ListWorkersRequestListWorkersPaginateTypeDef,
     ListWorkersRequestRequestTypeDef,
+    PaginatorConfigTypeDef,
+    ResponseMetadataTypeDef,
     UpdateDestinationRequestRequestTypeDef,
-    UpdateSiteRequestRequestTypeDef,
-    UpdateWorkerFleetRequestRequestTypeDef,
-    PositionCoordinatesTypeDef,
-    CreateDestinationResponseTypeDef,
-    CreateSiteResponseTypeDef,
-    CreateWorkerFleetResponseTypeDef,
-    CreateWorkerResponseTypeDef,
-    GetDestinationResponseTypeDef,
-    GetSiteResponseTypeDef,
-    GetWorkerFleetResponseTypeDef,
     UpdateDestinationResponseTypeDef,
+    UpdateSiteRequestRequestTypeDef,
     UpdateSiteResponseTypeDef,
+    UpdateWorkerFleetRequestRequestTypeDef,
     UpdateWorkerFleetResponseTypeDef,
+    PositionCoordinatesTypeDef,
     ListDestinationsResponseTypeDef,
-    ListDestinationsRequestListDestinationsPaginateTypeDef,
-    ListSitesRequestListSitesPaginateTypeDef,
-    ListWorkerFleetsRequestListWorkerFleetsPaginateTypeDef,
-    ListWorkersRequestListWorkersPaginateTypeDef,
     ListSitesResponseTypeDef,
     ListWorkerFleetsResponseTypeDef,
     CreateWorkerRequestRequestTypeDef,
     GetWorkerResponseTypeDef,
     UpdateWorkerRequestRequestTypeDef,
     UpdateWorkerResponseTypeDef,
     WorkerTypeDef,
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

### Comparing `types-aiobotocore-iot-roborunner-2.5.0.post1/types_aiobotocore_iot_roborunner.egg-info/SOURCES.txt` & `types-aiobotocore-iot-roborunner-2.5.1/types_aiobotocore_iot_roborunner.egg-info/SOURCES.txt`

 * *Files identical despite different names*

