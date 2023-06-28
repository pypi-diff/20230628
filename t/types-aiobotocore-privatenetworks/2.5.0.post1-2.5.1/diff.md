# Comparing `tmp/types-aiobotocore-privatenetworks-2.5.0.post1.tar.gz` & `tmp/types-aiobotocore-privatenetworks-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-privatenetworks-2.5.0.post1.tar", last modified: Sat Mar 11 12:27:08 2023, max compression
+gzip compressed data, was "types-aiobotocore-privatenetworks-2.5.1.tar", last modified: Wed Jun 28 01:44:00 2023, max compression
```

## Comparing `types-aiobotocore-privatenetworks-2.5.0.post1.tar` & `types-aiobotocore-privatenetworks-2.5.1.tar`

### file list

```diff
@@ -1,27 +1,27 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:08.683513 types-aiobotocore-privatenetworks-2.5.0.post1/
--rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-03-11 12:20:06.000000 types-aiobotocore-privatenetworks-2.5.0.post1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)    17007 2023-03-11 12:27:08.683513 types-aiobotocore-privatenetworks-2.5.0.post1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    15410 2023-03-11 12:20:06.000000 types-aiobotocore-privatenetworks-2.5.0.post1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-03-11 12:27:08.683513 types-aiobotocore-privatenetworks-2.5.0.post1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2174 2023-03-11 12:20:06.000000 types-aiobotocore-privatenetworks-2.5.0.post1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:08.679513 types-aiobotocore-privatenetworks-2.5.0.post1/types_aiobotocore_privatenetworks/
--rw-r--r--   0 runner    (1001) docker     (123)     1525 2023-03-11 12:20:06.000000 types-aiobotocore-privatenetworks-2.5.0.post1/types_aiobotocore_privatenetworks/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1524 2023-03-11 12:20:06.000000 types-aiobotocore-privatenetworks-2.5.0.post1/types_aiobotocore_privatenetworks/__init__.pyi
--rw-r--r--   0 runner    (1001) docker     (123)      963 2023-03-11 12:20:06.000000 types-aiobotocore-privatenetworks-2.5.0.post1/types_aiobotocore_privatenetworks/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)    22807 2023-03-11 12:20:06.000000 types-aiobotocore-privatenetworks-2.5.0.post1/types_aiobotocore_privatenetworks/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    22767 2023-03-11 12:20:06.000000 types-aiobotocore-privatenetworks-2.5.0.post1/types_aiobotocore_privatenetworks/client.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     9670 2023-03-11 12:20:06.000000 types-aiobotocore-privatenetworks-2.5.0.post1/types_aiobotocore_privatenetworks/literals.py
--rw-r--r--   0 runner    (1001) docker     (123)     9668 2023-03-11 12:20:06.000000 types-aiobotocore-privatenetworks-2.5.0.post1/types_aiobotocore_privatenetworks/literals.pyi
--rw-r--r--   0 runner    (1001) docker     (123)     7476 2023-03-11 12:20:06.000000 types-aiobotocore-privatenetworks-2.5.0.post1/types_aiobotocore_privatenetworks/paginator.py
--rw-r--r--   0 runner    (1001) docker     (123)     7468 2023-03-11 12:20:06.000000 types-aiobotocore-privatenetworks-2.5.0.post1/types_aiobotocore_privatenetworks/paginator.pyi
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-11 12:20:06.000000 types-aiobotocore-privatenetworks-2.5.0.post1/types_aiobotocore_privatenetworks/py.typed
--rw-r--r--   0 runner    (1001) docker     (123)    27319 2023-03-11 12:20:07.000000 types-aiobotocore-privatenetworks-2.5.0.post1/types_aiobotocore_privatenetworks/type_defs.py
--rw-r--r--   0 runner    (1001) docker     (123)    27270 2023-03-11 12:20:07.000000 types-aiobotocore-privatenetworks-2.5.0.post1/types_aiobotocore_privatenetworks/type_defs.pyi
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-03-11 12:20:06.000000 types-aiobotocore-privatenetworks-2.5.0.post1/types_aiobotocore_privatenetworks/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-11 12:27:08.683513 types-aiobotocore-privatenetworks-2.5.0.post1/types_aiobotocore_privatenetworks.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    17007 2023-03-11 12:27:08.000000 types-aiobotocore-privatenetworks-2.5.0.post1/types_aiobotocore_privatenetworks.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      965 2023-03-11 12:27:08.000000 types-aiobotocore-privatenetworks-2.5.0.post1/types_aiobotocore_privatenetworks.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:08.000000 types-aiobotocore-privatenetworks-2.5.0.post1/types_aiobotocore_privatenetworks.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-11 12:27:08.000000 types-aiobotocore-privatenetworks-2.5.0.post1/types_aiobotocore_privatenetworks.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-03-11 12:27:08.000000 types-aiobotocore-privatenetworks-2.5.0.post1/types_aiobotocore_privatenetworks.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       34 2023-03-11 12:27:08.000000 types-aiobotocore-privatenetworks-2.5.0.post1/types_aiobotocore_privatenetworks.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:00.614195 types-aiobotocore-privatenetworks-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:36:52.000000 types-aiobotocore-privatenetworks-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    17007 2023-06-28 01:44:00.614195 types-aiobotocore-privatenetworks-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    15416 2023-06-28 01:36:52.000000 types-aiobotocore-privatenetworks-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:44:00.614195 types-aiobotocore-privatenetworks-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2168 2023-06-28 01:36:52.000000 types-aiobotocore-privatenetworks-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:00.614195 types-aiobotocore-privatenetworks-2.5.1/types_aiobotocore_privatenetworks/
+-rw-r--r--   0 runner    (1001) docker     (123)     1525 2023-06-28 01:36:52.000000 types-aiobotocore-privatenetworks-2.5.1/types_aiobotocore_privatenetworks/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1524 2023-06-28 01:36:52.000000 types-aiobotocore-privatenetworks-2.5.1/types_aiobotocore_privatenetworks/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      951 2023-06-28 01:36:52.000000 types-aiobotocore-privatenetworks-2.5.1/types_aiobotocore_privatenetworks/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22807 2023-06-28 01:36:53.000000 types-aiobotocore-privatenetworks-2.5.1/types_aiobotocore_privatenetworks/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22767 2023-06-28 01:36:52.000000 types-aiobotocore-privatenetworks-2.5.1/types_aiobotocore_privatenetworks/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     9879 2023-06-28 01:36:53.000000 types-aiobotocore-privatenetworks-2.5.1/types_aiobotocore_privatenetworks/literals.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9877 2023-06-28 01:36:53.000000 types-aiobotocore-privatenetworks-2.5.1/types_aiobotocore_privatenetworks/literals.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     7379 2023-06-28 01:36:53.000000 types-aiobotocore-privatenetworks-2.5.1/types_aiobotocore_privatenetworks/paginator.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7371 2023-06-28 01:36:53.000000 types-aiobotocore-privatenetworks-2.5.1/types_aiobotocore_privatenetworks/paginator.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:36:52.000000 types-aiobotocore-privatenetworks-2.5.1/types_aiobotocore_privatenetworks/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)    27375 2023-06-28 01:36:53.000000 types-aiobotocore-privatenetworks-2.5.1/types_aiobotocore_privatenetworks/type_defs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27326 2023-06-28 01:36:53.000000 types-aiobotocore-privatenetworks-2.5.1/types_aiobotocore_privatenetworks/type_defs.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:36:52.000000 types-aiobotocore-privatenetworks-2.5.1/types_aiobotocore_privatenetworks/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:44:00.614195 types-aiobotocore-privatenetworks-2.5.1/types_aiobotocore_privatenetworks.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    17007 2023-06-28 01:44:00.000000 types-aiobotocore-privatenetworks-2.5.1/types_aiobotocore_privatenetworks.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      965 2023-06-28 01:44:00.000000 types-aiobotocore-privatenetworks-2.5.1/types_aiobotocore_privatenetworks.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:00.000000 types-aiobotocore-privatenetworks-2.5.1/types_aiobotocore_privatenetworks.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:44:00.000000 types-aiobotocore-privatenetworks-2.5.1/types_aiobotocore_privatenetworks.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 01:44:00.000000 types-aiobotocore-privatenetworks-2.5.1/types_aiobotocore_privatenetworks.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       34 2023-06-28 01:44:00.000000 types-aiobotocore-privatenetworks-2.5.1/types_aiobotocore_privatenetworks.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-privatenetworks-2.5.0.post1/LICENSE` & `types-aiobotocore-privatenetworks-2.5.1/LICENSE`

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

### Comparing `types-aiobotocore-privatenetworks-2.5.0.post1/PKG-INFO` & `types-aiobotocore-privatenetworks-2.5.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-privatenetworks
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Private5G 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Private5G 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_privatenetworks/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-privatenetworks"></a>
 
 # types-aiobotocore-privatenetworks
 
 [![PyPI - types-aiobotocore-privatenetworks](https://img.shields.io/pypi/v/types-aiobotocore-privatenetworks.svg?color=blue)](https://pypi.org/project/types-aiobotocore-privatenetworks)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-privatenetworks.svg?color=blue)](https://pypi.org/project/types-aiobotocore-privatenetworks)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_privatenetworks/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-privatenetworks?color=blue)](https://pypistats.org/packages/types-aiobotocore-privatenetworks)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Private5G 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/privatenetworks.html#Private5G)
+[aiobotocore.Private5G 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/privatenetworks.html#Private5G)
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
 [types-aiobotocore-privatenetworks docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_privatenetworks/).
 
 See how it helps to find and fix potential bugs:
 
@@ -350,60 +350,60 @@
 
 `types_aiobotocore_privatenetworks.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_privatenetworks.type_defs import (
     AcknowledgeOrderReceiptRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     ActivateDeviceIdentifierRequestRequestTypeDef,
     DeviceIdentifierTypeDef,
     AddressTypeDef,
     PositionTypeDef,
     CreateNetworkRequestRequestTypeDef,
     NetworkTypeDef,
     DeactivateDeviceIdentifierRequestRequestTypeDef,
     DeleteNetworkRequestRequestTypeDef,
     DeleteNetworkSiteRequestRequestTypeDef,
     GetDeviceIdentifierRequestRequestTypeDef,
     GetNetworkRequestRequestTypeDef,
     GetNetworkResourceRequestRequestTypeDef,
     GetNetworkSiteRequestRequestTypeDef,
     GetOrderRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListDeviceIdentifiersRequestListDeviceIdentifiersPaginateTypeDef,
     ListDeviceIdentifiersRequestRequestTypeDef,
+    ListNetworkResourcesRequestListNetworkResourcesPaginateTypeDef,
     ListNetworkResourcesRequestRequestTypeDef,
+    ListNetworkSitesRequestListNetworkSitesPaginateTypeDef,
     ListNetworkSitesRequestRequestTypeDef,
+    ListNetworksRequestListNetworksPaginateTypeDef,
     ListNetworksRequestRequestTypeDef,
+    ListOrdersRequestListOrdersPaginateTypeDef,
     ListOrdersRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     NameValuePairTypeDef,
     TrackingInformationTypeDef,
+    PaginatorConfigTypeDef,
+    PingResponseTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateNetworkSiteRequestRequestTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    PingResponseTypeDef,
     ActivateDeviceIdentifierResponseTypeDef,
     DeactivateDeviceIdentifierResponseTypeDef,
     GetDeviceIdentifierResponseTypeDef,
     ListDeviceIdentifiersResponseTypeDef,
     ActivateNetworkSiteRequestRequestTypeDef,
     ReturnInformationTypeDef,
     StartNetworkResourceUpdateRequestRequestTypeDef,
     ConfigureAccessPointRequestRequestTypeDef,
     CreateNetworkResponseTypeDef,
     DeleteNetworkResponseTypeDef,
     GetNetworkResponseTypeDef,
     ListNetworksResponseTypeDef,
-    ListDeviceIdentifiersRequestListDeviceIdentifiersPaginateTypeDef,
-    ListNetworkResourcesRequestListNetworkResourcesPaginateTypeDef,
-    ListNetworkSitesRequestListNetworkSitesPaginateTypeDef,
-    ListNetworksRequestListNetworksPaginateTypeDef,
-    ListOrdersRequestListOrdersPaginateTypeDef,
     NetworkResourceDefinitionTypeDef,
     OrderTypeDef,
     NetworkResourceTypeDef,
     SitePlanTypeDef,
     AcknowledgeOrderReceiptResponseTypeDef,
     GetOrderResponseTypeDef,
     ListOrdersResponseTypeDef,
@@ -430,43 +430,43 @@
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

### Comparing `types-aiobotocore-privatenetworks-2.5.0.post1/README.md` & `types-aiobotocore-privatenetworks-2.5.1/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,29 +1,29 @@
 <a id="types-aiobotocore-privatenetworks"></a>
 
 # types-aiobotocore-privatenetworks
 
 [![PyPI - types-aiobotocore-privatenetworks](https://img.shields.io/pypi/v/types-aiobotocore-privatenetworks.svg?color=blue)](https://pypi.org/project/types-aiobotocore-privatenetworks)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-privatenetworks.svg?color=blue)](https://pypi.org/project/types-aiobotocore-privatenetworks)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_privatenetworks/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-privatenetworks?color=blue)](https://pypistats.org/packages/types-aiobotocore-privatenetworks)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Private5G 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/privatenetworks.html#Private5G)
+[aiobotocore.Private5G 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/privatenetworks.html#Private5G)
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
 [types-aiobotocore-privatenetworks docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_privatenetworks/).
 
 See how it helps to find and fix potential bugs:
 
@@ -317,60 +317,60 @@
 
 `types_aiobotocore_privatenetworks.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_privatenetworks.type_defs import (
     AcknowledgeOrderReceiptRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     ActivateDeviceIdentifierRequestRequestTypeDef,
     DeviceIdentifierTypeDef,
     AddressTypeDef,
     PositionTypeDef,
     CreateNetworkRequestRequestTypeDef,
     NetworkTypeDef,
     DeactivateDeviceIdentifierRequestRequestTypeDef,
     DeleteNetworkRequestRequestTypeDef,
     DeleteNetworkSiteRequestRequestTypeDef,
     GetDeviceIdentifierRequestRequestTypeDef,
     GetNetworkRequestRequestTypeDef,
     GetNetworkResourceRequestRequestTypeDef,
     GetNetworkSiteRequestRequestTypeDef,
     GetOrderRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListDeviceIdentifiersRequestListDeviceIdentifiersPaginateTypeDef,
     ListDeviceIdentifiersRequestRequestTypeDef,
+    ListNetworkResourcesRequestListNetworkResourcesPaginateTypeDef,
     ListNetworkResourcesRequestRequestTypeDef,
+    ListNetworkSitesRequestListNetworkSitesPaginateTypeDef,
     ListNetworkSitesRequestRequestTypeDef,
+    ListNetworksRequestListNetworksPaginateTypeDef,
     ListNetworksRequestRequestTypeDef,
+    ListOrdersRequestListOrdersPaginateTypeDef,
     ListOrdersRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     NameValuePairTypeDef,
     TrackingInformationTypeDef,
+    PaginatorConfigTypeDef,
+    PingResponseTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateNetworkSiteRequestRequestTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    PingResponseTypeDef,
     ActivateDeviceIdentifierResponseTypeDef,
     DeactivateDeviceIdentifierResponseTypeDef,
     GetDeviceIdentifierResponseTypeDef,
     ListDeviceIdentifiersResponseTypeDef,
     ActivateNetworkSiteRequestRequestTypeDef,
     ReturnInformationTypeDef,
     StartNetworkResourceUpdateRequestRequestTypeDef,
     ConfigureAccessPointRequestRequestTypeDef,
     CreateNetworkResponseTypeDef,
     DeleteNetworkResponseTypeDef,
     GetNetworkResponseTypeDef,
     ListNetworksResponseTypeDef,
-    ListDeviceIdentifiersRequestListDeviceIdentifiersPaginateTypeDef,
-    ListNetworkResourcesRequestListNetworkResourcesPaginateTypeDef,
-    ListNetworkSitesRequestListNetworkSitesPaginateTypeDef,
-    ListNetworksRequestListNetworksPaginateTypeDef,
-    ListOrdersRequestListOrdersPaginateTypeDef,
     NetworkResourceDefinitionTypeDef,
     OrderTypeDef,
     NetworkResourceTypeDef,
     SitePlanTypeDef,
     AcknowledgeOrderReceiptResponseTypeDef,
     GetOrderResponseTypeDef,
     ListOrdersResponseTypeDef,
@@ -397,43 +397,43 @@
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

### Comparing `types-aiobotocore-privatenetworks-2.5.0.post1/setup.py` & `types-aiobotocore-privatenetworks-2.5.1/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 """
 Setup script for types-aiobotocore-privatenetworks.
 """
-from os.path import abspath, dirname
+from pathlib import Path
 
 from setuptools import setup
 
-LONG_DESCRIPTION = open(dirname(abspath(__file__)) + "/README.md", "r").read()
+LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-privatenetworks",
-    version="2.5.0.post1",
+    version="2.5.1",
     packages=["types_aiobotocore_privatenetworks"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
     description=(
-        "Type annotations for aiobotocore.Private5G 2.5.0 service generated with mypy-boto3-builder"
-        " 7.13.0"
+        "Type annotations for aiobotocore.Private5G 2.5.1 service generated with mypy-boto3-builder"
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
             "https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_privatenetworks/"
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

### Comparing `types-aiobotocore-privatenetworks-2.5.0.post1/types_aiobotocore_privatenetworks/__init__.py` & `types-aiobotocore-privatenetworks-2.5.1/types_aiobotocore_privatenetworks/__init__.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-privatenetworks-2.5.0.post1/types_aiobotocore_privatenetworks/__init__.pyi` & `types-aiobotocore-privatenetworks-2.5.1/types_aiobotocore_privatenetworks/__init__.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-privatenetworks-2.5.0.post1/types_aiobotocore_privatenetworks/__main__.py` & `types-aiobotocore-privatenetworks-2.5.1/types_aiobotocore_privatenetworks/__main__.py`

 * *Files 16% similar despite different names*

```diff
@@ -5,29 +5,29 @@
 
 
 def print_info() -> None:
     """
     Print package info to stdout.
     """
     print(
-        "Type annotations for aiobotocore.Private5G 2.5.0\nVersion:         2.5.0.post1\nBuilder"
-        " version: 7.13.0\nDocs:           "
+        "Type annotations for aiobotocore.Private5G 2.5.1\nVersion:         2.5.1\nBuilder version:"
+        " 7.14.5\nDocs:           "
         " https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_privatenetworks//\nBoto3"
         " docs:     "
         " https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/privatenetworks.html#Private5G\nOther"
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

### Comparing `types-aiobotocore-privatenetworks-2.5.0.post1/types_aiobotocore_privatenetworks/client.py` & `types-aiobotocore-privatenetworks-2.5.1/types_aiobotocore_privatenetworks/client.py`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-privatenetworks-2.5.0.post1/types_aiobotocore_privatenetworks/client.pyi` & `types-aiobotocore-privatenetworks-2.5.1/types_aiobotocore_privatenetworks/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-privatenetworks-2.5.0.post1/types_aiobotocore_privatenetworks/literals.py` & `types-aiobotocore-privatenetworks-2.5.1/types_aiobotocore_privatenetworks/literals.py`

 * *Files 2% similar despite different names*

```diff
@@ -138,14 +138,15 @@
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
@@ -224,14 +225,15 @@
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
@@ -242,14 +244,15 @@
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
@@ -285,14 +288,15 @@
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
@@ -311,16 +315,19 @@
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
@@ -404,15 +411,17 @@
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

### Comparing `types-aiobotocore-privatenetworks-2.5.0.post1/types_aiobotocore_privatenetworks/literals.pyi` & `types-aiobotocore-privatenetworks-2.5.1/types_aiobotocore_privatenetworks/literals.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -136,14 +136,15 @@
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
@@ -222,14 +223,15 @@
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
@@ -240,14 +242,15 @@
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
@@ -283,14 +286,15 @@
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
@@ -309,16 +313,19 @@
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
@@ -402,15 +409,17 @@
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

### Comparing `types-aiobotocore-privatenetworks-2.5.0.post1/types_aiobotocore_privatenetworks/paginator.py` & `types-aiobotocore-privatenetworks-2.5.1/types_aiobotocore_privatenetworks/paginator.py`

 * *Files 2% similar despite different names*

```diff
@@ -25,15 +25,15 @@
         list_network_resources_paginator: ListNetworkResourcesPaginator = client.get_paginator("list_network_resources")
         list_network_sites_paginator: ListNetworkSitesPaginator = client.get_paginator("list_network_sites")
         list_networks_paginator: ListNetworksPaginator = client.get_paginator("list_networks")
         list_orders_paginator: ListOrdersPaginator = client.get_paginator("list_orders")
     ```
 """
 import sys
-from typing import Generic, Iterator, Mapping, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Mapping, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     DeviceIdentifierFilterKeysType,
     NetworkResourceFilterKeysType,
@@ -44,18 +44,14 @@
     ListNetworkResourcesResponseTypeDef,
     ListNetworkSitesResponseTypeDef,
     ListNetworksResponseTypeDef,
     ListOrdersResponseTypeDef,
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
@@ -84,15 +80,15 @@
     """
 
     def paginate(
         self,
         *,
         networkArn: str,
         filters: Mapping[DeviceIdentifierFilterKeysType, Sequence[str]] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDeviceIdentifiersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/privatenetworks.html#Private5G.Paginator.ListDeviceIdentifiers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_privatenetworks/paginators/#listdeviceidentifierspaginator)
         """
 
 
@@ -103,15 +99,15 @@
     """
 
     def paginate(
         self,
         *,
         networkArn: str,
         filters: Mapping[NetworkResourceFilterKeysType, Sequence[str]] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListNetworkResourcesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/privatenetworks.html#Private5G.Paginator.ListNetworkResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_privatenetworks/paginators/#listnetworkresourcespaginator)
         """
 
 
@@ -122,15 +118,15 @@
     """
 
     def paginate(
         self,
         *,
         networkArn: str,
         filters: Mapping[Literal["STATUS"], Sequence[str]] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListNetworkSitesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/privatenetworks.html#Private5G.Paginator.ListNetworkSites.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_privatenetworks/paginators/#listnetworksitespaginator)
         """
 
 
@@ -140,15 +136,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_privatenetworks/paginators/#listnetworkspaginator)
     """
 
     def paginate(
         self,
         *,
         filters: Mapping[Literal["STATUS"], Sequence[str]] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListNetworksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/privatenetworks.html#Private5G.Paginator.ListNetworks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_privatenetworks/paginators/#listnetworkspaginator)
         """
 
 
@@ -159,13 +155,13 @@
     """
 
     def paginate(
         self,
         *,
         networkArn: str,
         filters: Mapping[OrderFilterKeysType, Sequence[str]] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOrdersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/privatenetworks.html#Private5G.Paginator.ListOrders.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_privatenetworks/paginators/#listorderspaginator)
         """
```

### Comparing `types-aiobotocore-privatenetworks-2.5.0.post1/types_aiobotocore_privatenetworks/paginator.pyi` & `types-aiobotocore-privatenetworks-2.5.1/types_aiobotocore_privatenetworks/paginator.pyi`

 * *Files 5% similar despite different names*

```diff
@@ -25,15 +25,15 @@
         list_network_resources_paginator: ListNetworkResourcesPaginator = client.get_paginator("list_network_resources")
         list_network_sites_paginator: ListNetworkSitesPaginator = client.get_paginator("list_network_sites")
         list_networks_paginator: ListNetworksPaginator = client.get_paginator("list_networks")
         list_orders_paginator: ListOrdersPaginator = client.get_paginator("list_orders")
     ```
 """
 import sys
-from typing import Generic, Iterator, Mapping, Sequence, TypeVar
+from typing import AsyncIterator, Generic, Iterator, Mapping, Sequence, TypeVar
 
 from aiobotocore.paginate import AioPaginator
 from botocore.paginate import PageIterator
 
 from .literals import (
     DeviceIdentifierFilterKeysType,
     NetworkResourceFilterKeysType,
@@ -44,18 +44,14 @@
     ListNetworkResourcesResponseTypeDef,
     ListNetworkSitesResponseTypeDef,
     ListNetworksResponseTypeDef,
     ListOrdersResponseTypeDef,
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
     "ListDeviceIdentifiersPaginator",
@@ -80,15 +76,15 @@
     """
 
     def paginate(
         self,
         *,
         networkArn: str,
         filters: Mapping[DeviceIdentifierFilterKeysType, Sequence[str]] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListDeviceIdentifiersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/privatenetworks.html#Private5G.Paginator.ListDeviceIdentifiers.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_privatenetworks/paginators/#listdeviceidentifierspaginator)
         """
 
 class ListNetworkResourcesPaginator(AioPaginator):
@@ -98,15 +94,15 @@
     """
 
     def paginate(
         self,
         *,
         networkArn: str,
         filters: Mapping[NetworkResourceFilterKeysType, Sequence[str]] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListNetworkResourcesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/privatenetworks.html#Private5G.Paginator.ListNetworkResources.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_privatenetworks/paginators/#listnetworkresourcespaginator)
         """
 
 class ListNetworkSitesPaginator(AioPaginator):
@@ -116,15 +112,15 @@
     """
 
     def paginate(
         self,
         *,
         networkArn: str,
         filters: Mapping[Literal["STATUS"], Sequence[str]] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListNetworkSitesResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/privatenetworks.html#Private5G.Paginator.ListNetworkSites.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_privatenetworks/paginators/#listnetworksitespaginator)
         """
 
 class ListNetworksPaginator(AioPaginator):
@@ -133,15 +129,15 @@
     [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_privatenetworks/paginators/#listnetworkspaginator)
     """
 
     def paginate(
         self,
         *,
         filters: Mapping[Literal["STATUS"], Sequence[str]] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListNetworksResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/privatenetworks.html#Private5G.Paginator.ListNetworks.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_privatenetworks/paginators/#listnetworkspaginator)
         """
 
 class ListOrdersPaginator(AioPaginator):
@@ -151,13 +147,13 @@
     """
 
     def paginate(
         self,
         *,
         networkArn: str,
         filters: Mapping[OrderFilterKeysType, Sequence[str]] = ...,
-        PaginationConfig: PaginatorConfigTypeDef = ...
+        PaginationConfig: "PaginatorConfigTypeDef" = ...
     ) -> AsyncIterator[ListOrdersResponseTypeDef]:
         """
         [Show boto3 documentation](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/privatenetworks.html#Private5G.Paginator.ListOrders.paginate)
         [Show types-aiobotocore documentation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_privatenetworks/paginators/#listorderspaginator)
         """
```

### Comparing `types-aiobotocore-privatenetworks-2.5.0.post1/types_aiobotocore_privatenetworks/type_defs.py` & `types-aiobotocore-privatenetworks-2.5.1/types_aiobotocore_privatenetworks/type_defs.py`

 * *Files 2% similar despite different names*

```diff
@@ -38,60 +38,60 @@
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 
 __all__ = (
     "AcknowledgeOrderReceiptRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "ActivateDeviceIdentifierRequestRequestTypeDef",
     "DeviceIdentifierTypeDef",
     "AddressTypeDef",
     "PositionTypeDef",
     "CreateNetworkRequestRequestTypeDef",
     "NetworkTypeDef",
     "DeactivateDeviceIdentifierRequestRequestTypeDef",
     "DeleteNetworkRequestRequestTypeDef",
     "DeleteNetworkSiteRequestRequestTypeDef",
     "GetDeviceIdentifierRequestRequestTypeDef",
     "GetNetworkRequestRequestTypeDef",
     "GetNetworkResourceRequestRequestTypeDef",
     "GetNetworkSiteRequestRequestTypeDef",
     "GetOrderRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListDeviceIdentifiersRequestListDeviceIdentifiersPaginateTypeDef",
     "ListDeviceIdentifiersRequestRequestTypeDef",
+    "ListNetworkResourcesRequestListNetworkResourcesPaginateTypeDef",
     "ListNetworkResourcesRequestRequestTypeDef",
+    "ListNetworkSitesRequestListNetworkSitesPaginateTypeDef",
     "ListNetworkSitesRequestRequestTypeDef",
+    "ListNetworksRequestListNetworksPaginateTypeDef",
     "ListNetworksRequestRequestTypeDef",
+    "ListOrdersRequestListOrdersPaginateTypeDef",
     "ListOrdersRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "NameValuePairTypeDef",
     "TrackingInformationTypeDef",
+    "PaginatorConfigTypeDef",
+    "PingResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateNetworkSiteRequestRequestTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "PingResponseTypeDef",
     "ActivateDeviceIdentifierResponseTypeDef",
     "DeactivateDeviceIdentifierResponseTypeDef",
     "GetDeviceIdentifierResponseTypeDef",
     "ListDeviceIdentifiersResponseTypeDef",
     "ActivateNetworkSiteRequestRequestTypeDef",
     "ReturnInformationTypeDef",
     "StartNetworkResourceUpdateRequestRequestTypeDef",
     "ConfigureAccessPointRequestRequestTypeDef",
     "CreateNetworkResponseTypeDef",
     "DeleteNetworkResponseTypeDef",
     "GetNetworkResponseTypeDef",
     "ListNetworksResponseTypeDef",
-    "ListDeviceIdentifiersRequestListDeviceIdentifiersPaginateTypeDef",
-    "ListNetworkResourcesRequestListNetworkResourcesPaginateTypeDef",
-    "ListNetworkSitesRequestListNetworkSitesPaginateTypeDef",
-    "ListNetworksRequestListNetworksPaginateTypeDef",
-    "ListOrdersRequestListOrdersPaginateTypeDef",
     "NetworkResourceDefinitionTypeDef",
     "OrderTypeDef",
     "NetworkResourceTypeDef",
     "SitePlanTypeDef",
     "AcknowledgeOrderReceiptResponseTypeDef",
     "GetOrderResponseTypeDef",
     "ListOrdersResponseTypeDef",
@@ -113,25 +113,14 @@
 AcknowledgeOrderReceiptRequestRequestTypeDef = TypedDict(
     "AcknowledgeOrderReceiptRequestRequestTypeDef",
     {
         "orderArn": str,
     },
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
 _RequiredActivateDeviceIdentifierRequestRequestTypeDef = TypedDict(
     "_RequiredActivateDeviceIdentifierRequestRequestTypeDef",
     {
         "deviceIdentifierArn": str,
     },
 )
 _OptionalActivateDeviceIdentifierRequestRequestTypeDef = TypedDict(
@@ -346,24 +335,37 @@
 GetOrderRequestRequestTypeDef = TypedDict(
     "GetOrderRequestRequestTypeDef",
     {
         "orderArn": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListDeviceIdentifiersRequestListDeviceIdentifiersPaginateTypeDef = TypedDict(
+    "_RequiredListDeviceIdentifiersRequestListDeviceIdentifiersPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "networkArn": str,
+    },
+)
+_OptionalListDeviceIdentifiersRequestListDeviceIdentifiersPaginateTypeDef = TypedDict(
+    "_OptionalListDeviceIdentifiersRequestListDeviceIdentifiersPaginateTypeDef",
+    {
+        "filters": Mapping[DeviceIdentifierFilterKeysType, Sequence[str]],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+
+class ListDeviceIdentifiersRequestListDeviceIdentifiersPaginateTypeDef(
+    _RequiredListDeviceIdentifiersRequestListDeviceIdentifiersPaginateTypeDef,
+    _OptionalListDeviceIdentifiersRequestListDeviceIdentifiersPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListDeviceIdentifiersRequestRequestTypeDef = TypedDict(
     "_RequiredListDeviceIdentifiersRequestRequestTypeDef",
     {
         "networkArn": str,
     },
 )
 _OptionalListDeviceIdentifiersRequestRequestTypeDef = TypedDict(
@@ -380,14 +382,37 @@
 class ListDeviceIdentifiersRequestRequestTypeDef(
     _RequiredListDeviceIdentifiersRequestRequestTypeDef,
     _OptionalListDeviceIdentifiersRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListNetworkResourcesRequestListNetworkResourcesPaginateTypeDef = TypedDict(
+    "_RequiredListNetworkResourcesRequestListNetworkResourcesPaginateTypeDef",
+    {
+        "networkArn": str,
+    },
+)
+_OptionalListNetworkResourcesRequestListNetworkResourcesPaginateTypeDef = TypedDict(
+    "_OptionalListNetworkResourcesRequestListNetworkResourcesPaginateTypeDef",
+    {
+        "filters": Mapping[NetworkResourceFilterKeysType, Sequence[str]],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListNetworkResourcesRequestListNetworkResourcesPaginateTypeDef(
+    _RequiredListNetworkResourcesRequestListNetworkResourcesPaginateTypeDef,
+    _OptionalListNetworkResourcesRequestListNetworkResourcesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListNetworkResourcesRequestRequestTypeDef = TypedDict(
     "_RequiredListNetworkResourcesRequestRequestTypeDef",
     {
         "networkArn": str,
     },
 )
 _OptionalListNetworkResourcesRequestRequestTypeDef = TypedDict(
@@ -404,14 +429,37 @@
 class ListNetworkResourcesRequestRequestTypeDef(
     _RequiredListNetworkResourcesRequestRequestTypeDef,
     _OptionalListNetworkResourcesRequestRequestTypeDef,
 ):
     pass
 
 
+_RequiredListNetworkSitesRequestListNetworkSitesPaginateTypeDef = TypedDict(
+    "_RequiredListNetworkSitesRequestListNetworkSitesPaginateTypeDef",
+    {
+        "networkArn": str,
+    },
+)
+_OptionalListNetworkSitesRequestListNetworkSitesPaginateTypeDef = TypedDict(
+    "_OptionalListNetworkSitesRequestListNetworkSitesPaginateTypeDef",
+    {
+        "filters": Mapping[Literal["STATUS"], Sequence[str]],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListNetworkSitesRequestListNetworkSitesPaginateTypeDef(
+    _RequiredListNetworkSitesRequestListNetworkSitesPaginateTypeDef,
+    _OptionalListNetworkSitesRequestListNetworkSitesPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListNetworkSitesRequestRequestTypeDef = TypedDict(
     "_RequiredListNetworkSitesRequestRequestTypeDef",
     {
         "networkArn": str,
     },
 )
 _OptionalListNetworkSitesRequestRequestTypeDef = TypedDict(
@@ -427,24 +475,56 @@
 
 class ListNetworkSitesRequestRequestTypeDef(
     _RequiredListNetworkSitesRequestRequestTypeDef, _OptionalListNetworkSitesRequestRequestTypeDef
 ):
     pass
 
 
+ListNetworksRequestListNetworksPaginateTypeDef = TypedDict(
+    "ListNetworksRequestListNetworksPaginateTypeDef",
+    {
+        "filters": Mapping[Literal["STATUS"], Sequence[str]],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListNetworksRequestRequestTypeDef = TypedDict(
     "ListNetworksRequestRequestTypeDef",
     {
         "filters": Mapping[Literal["STATUS"], Sequence[str]],
         "maxResults": int,
         "startToken": str,
     },
     total=False,
 )
 
+_RequiredListOrdersRequestListOrdersPaginateTypeDef = TypedDict(
+    "_RequiredListOrdersRequestListOrdersPaginateTypeDef",
+    {
+        "networkArn": str,
+    },
+)
+_OptionalListOrdersRequestListOrdersPaginateTypeDef = TypedDict(
+    "_OptionalListOrdersRequestListOrdersPaginateTypeDef",
+    {
+        "filters": Mapping[OrderFilterKeysType, Sequence[str]],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+
+class ListOrdersRequestListOrdersPaginateTypeDef(
+    _RequiredListOrdersRequestListOrdersPaginateTypeDef,
+    _OptionalListOrdersRequestListOrdersPaginateTypeDef,
+):
+    pass
+
+
 _RequiredListOrdersRequestRequestTypeDef = TypedDict(
     "_RequiredListOrdersRequestRequestTypeDef",
     {
         "networkArn": str,
     },
 )
 _OptionalListOrdersRequestRequestTypeDef = TypedDict(
@@ -467,14 +547,22 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredNameValuePairTypeDef = TypedDict(
     "_RequiredNameValuePairTypeDef",
     {
         "name": str,
     },
 )
 _OptionalNameValuePairTypeDef = TypedDict(
@@ -494,14 +582,43 @@
     "TrackingInformationTypeDef",
     {
         "trackingNumber": str,
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
+PingResponseTypeDef = TypedDict(
+    "PingResponseTypeDef",
+    {
+        "status": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
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
         "resourceArn": str,
         "tags": Mapping[str, str],
     },
 )
@@ -532,62 +649,46 @@
 
 class UpdateNetworkSiteRequestRequestTypeDef(
     _RequiredUpdateNetworkSiteRequestRequestTypeDef, _OptionalUpdateNetworkSiteRequestRequestTypeDef
 ):
     pass
 
 
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PingResponseTypeDef = TypedDict(
-    "PingResponseTypeDef",
-    {
-        "status": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ActivateDeviceIdentifierResponseTypeDef = TypedDict(
     "ActivateDeviceIdentifierResponseTypeDef",
     {
         "deviceIdentifier": DeviceIdentifierTypeDef,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeactivateDeviceIdentifierResponseTypeDef = TypedDict(
     "DeactivateDeviceIdentifierResponseTypeDef",
     {
         "deviceIdentifier": DeviceIdentifierTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDeviceIdentifierResponseTypeDef = TypedDict(
     "GetDeviceIdentifierResponseTypeDef",
     {
         "deviceIdentifier": DeviceIdentifierTypeDef,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDeviceIdentifiersResponseTypeDef = TypedDict(
     "ListDeviceIdentifiersResponseTypeDef",
     {
         "deviceIdentifiers": List[DeviceIdentifierTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredActivateNetworkSiteRequestRequestTypeDef = TypedDict(
     "_RequiredActivateNetworkSiteRequestRequestTypeDef",
     {
         "networkSiteArn": str,
@@ -672,144 +773,43 @@
 
 
 CreateNetworkResponseTypeDef = TypedDict(
     "CreateNetworkResponseTypeDef",
     {
         "network": NetworkTypeDef,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteNetworkResponseTypeDef = TypedDict(
     "DeleteNetworkResponseTypeDef",
     {
         "network": NetworkTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetNetworkResponseTypeDef = TypedDict(
     "GetNetworkResponseTypeDef",
     {
         "network": NetworkTypeDef,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListNetworksResponseTypeDef = TypedDict(
     "ListNetworksResponseTypeDef",
     {
         "networks": List[NetworkTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredListDeviceIdentifiersRequestListDeviceIdentifiersPaginateTypeDef = TypedDict(
-    "_RequiredListDeviceIdentifiersRequestListDeviceIdentifiersPaginateTypeDef",
-    {
-        "networkArn": str,
-    },
-)
-_OptionalListDeviceIdentifiersRequestListDeviceIdentifiersPaginateTypeDef = TypedDict(
-    "_OptionalListDeviceIdentifiersRequestListDeviceIdentifiersPaginateTypeDef",
-    {
-        "filters": Mapping[DeviceIdentifierFilterKeysType, Sequence[str]],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListDeviceIdentifiersRequestListDeviceIdentifiersPaginateTypeDef(
-    _RequiredListDeviceIdentifiersRequestListDeviceIdentifiersPaginateTypeDef,
-    _OptionalListDeviceIdentifiersRequestListDeviceIdentifiersPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListNetworkResourcesRequestListNetworkResourcesPaginateTypeDef = TypedDict(
-    "_RequiredListNetworkResourcesRequestListNetworkResourcesPaginateTypeDef",
-    {
-        "networkArn": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
-_OptionalListNetworkResourcesRequestListNetworkResourcesPaginateTypeDef = TypedDict(
-    "_OptionalListNetworkResourcesRequestListNetworkResourcesPaginateTypeDef",
-    {
-        "filters": Mapping[NetworkResourceFilterKeysType, Sequence[str]],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListNetworkResourcesRequestListNetworkResourcesPaginateTypeDef(
-    _RequiredListNetworkResourcesRequestListNetworkResourcesPaginateTypeDef,
-    _OptionalListNetworkResourcesRequestListNetworkResourcesPaginateTypeDef,
-):
-    pass
-
-
-_RequiredListNetworkSitesRequestListNetworkSitesPaginateTypeDef = TypedDict(
-    "_RequiredListNetworkSitesRequestListNetworkSitesPaginateTypeDef",
-    {
-        "networkArn": str,
-    },
-)
-_OptionalListNetworkSitesRequestListNetworkSitesPaginateTypeDef = TypedDict(
-    "_OptionalListNetworkSitesRequestListNetworkSitesPaginateTypeDef",
-    {
-        "filters": Mapping[Literal["STATUS"], Sequence[str]],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListNetworkSitesRequestListNetworkSitesPaginateTypeDef(
-    _RequiredListNetworkSitesRequestListNetworkSitesPaginateTypeDef,
-    _OptionalListNetworkSitesRequestListNetworkSitesPaginateTypeDef,
-):
-    pass
-
-
-ListNetworksRequestListNetworksPaginateTypeDef = TypedDict(
-    "ListNetworksRequestListNetworksPaginateTypeDef",
-    {
-        "filters": Mapping[Literal["STATUS"], Sequence[str]],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListOrdersRequestListOrdersPaginateTypeDef = TypedDict(
-    "_RequiredListOrdersRequestListOrdersPaginateTypeDef",
-    {
-        "networkArn": str,
-    },
-)
-_OptionalListOrdersRequestListOrdersPaginateTypeDef = TypedDict(
-    "_OptionalListOrdersRequestListOrdersPaginateTypeDef",
-    {
-        "filters": Mapping[OrderFilterKeysType, Sequence[str]],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-
-class ListOrdersRequestListOrdersPaginateTypeDef(
-    _RequiredListOrdersRequestListOrdersPaginateTypeDef,
-    _OptionalListOrdersRequestListOrdersPaginateTypeDef,
-):
-    pass
-
 
 _RequiredNetworkResourceDefinitionTypeDef = TypedDict(
     "_RequiredNetworkResourceDefinitionTypeDef",
     {
         "count": int,
         "type": NetworkResourceDefinitionTypeType,
     },
@@ -875,67 +875,67 @@
     total=False,
 )
 
 AcknowledgeOrderReceiptResponseTypeDef = TypedDict(
     "AcknowledgeOrderReceiptResponseTypeDef",
     {
         "order": OrderTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetOrderResponseTypeDef = TypedDict(
     "GetOrderResponseTypeDef",
     {
         "order": OrderTypeDef,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListOrdersResponseTypeDef = TypedDict(
     "ListOrdersResponseTypeDef",
     {
         "nextToken": str,
         "orders": List[OrderTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ConfigureAccessPointResponseTypeDef = TypedDict(
     "ConfigureAccessPointResponseTypeDef",
     {
         "accessPoint": NetworkResourceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetNetworkResourceResponseTypeDef = TypedDict(
     "GetNetworkResourceResponseTypeDef",
     {
         "networkResource": NetworkResourceTypeDef,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListNetworkResourcesResponseTypeDef = TypedDict(
     "ListNetworkResourcesResponseTypeDef",
     {
         "networkResources": List[NetworkResourceTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartNetworkResourceUpdateResponseTypeDef = TypedDict(
     "StartNetworkResourceUpdateResponseTypeDef",
     {
         "networkResource": NetworkResourceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateNetworkSiteRequestRequestTypeDef = TypedDict(
     "_RequiredCreateNetworkSiteRequestRequestTypeDef",
     {
         "networkArn": str,
@@ -1013,54 +1013,54 @@
     pass
 
 
 ActivateNetworkSiteResponseTypeDef = TypedDict(
     "ActivateNetworkSiteResponseTypeDef",
     {
         "networkSite": NetworkSiteTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateNetworkSiteResponseTypeDef = TypedDict(
     "CreateNetworkSiteResponseTypeDef",
     {
         "networkSite": NetworkSiteTypeDef,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteNetworkSiteResponseTypeDef = TypedDict(
     "DeleteNetworkSiteResponseTypeDef",
     {
         "networkSite": NetworkSiteTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetNetworkSiteResponseTypeDef = TypedDict(
     "GetNetworkSiteResponseTypeDef",
     {
         "networkSite": NetworkSiteTypeDef,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListNetworkSitesResponseTypeDef = TypedDict(
     "ListNetworkSitesResponseTypeDef",
     {
         "networkSites": List[NetworkSiteTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateNetworkSiteResponseTypeDef = TypedDict(
     "UpdateNetworkSiteResponseTypeDef",
     {
         "networkSite": NetworkSiteTypeDef,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-privatenetworks-2.5.0.post1/types_aiobotocore_privatenetworks/type_defs.pyi` & `types-aiobotocore-privatenetworks-2.5.1/types_aiobotocore_privatenetworks/type_defs.pyi`

 * *Files 2% similar despite different names*

```diff
@@ -37,60 +37,60 @@
 if sys.version_info >= (3, 9):
     from typing import TypedDict
 else:
     from typing_extensions import TypedDict
 
 __all__ = (
     "AcknowledgeOrderReceiptRequestRequestTypeDef",
-    "ResponseMetadataTypeDef",
     "ActivateDeviceIdentifierRequestRequestTypeDef",
     "DeviceIdentifierTypeDef",
     "AddressTypeDef",
     "PositionTypeDef",
     "CreateNetworkRequestRequestTypeDef",
     "NetworkTypeDef",
     "DeactivateDeviceIdentifierRequestRequestTypeDef",
     "DeleteNetworkRequestRequestTypeDef",
     "DeleteNetworkSiteRequestRequestTypeDef",
     "GetDeviceIdentifierRequestRequestTypeDef",
     "GetNetworkRequestRequestTypeDef",
     "GetNetworkResourceRequestRequestTypeDef",
     "GetNetworkSiteRequestRequestTypeDef",
     "GetOrderRequestRequestTypeDef",
-    "PaginatorConfigTypeDef",
+    "ListDeviceIdentifiersRequestListDeviceIdentifiersPaginateTypeDef",
     "ListDeviceIdentifiersRequestRequestTypeDef",
+    "ListNetworkResourcesRequestListNetworkResourcesPaginateTypeDef",
     "ListNetworkResourcesRequestRequestTypeDef",
+    "ListNetworkSitesRequestListNetworkSitesPaginateTypeDef",
     "ListNetworkSitesRequestRequestTypeDef",
+    "ListNetworksRequestListNetworksPaginateTypeDef",
     "ListNetworksRequestRequestTypeDef",
+    "ListOrdersRequestListOrdersPaginateTypeDef",
     "ListOrdersRequestRequestTypeDef",
     "ListTagsForResourceRequestRequestTypeDef",
+    "ListTagsForResourceResponseTypeDef",
     "NameValuePairTypeDef",
     "TrackingInformationTypeDef",
+    "PaginatorConfigTypeDef",
+    "PingResponseTypeDef",
+    "ResponseMetadataTypeDef",
     "TagResourceRequestRequestTypeDef",
     "UntagResourceRequestRequestTypeDef",
     "UpdateNetworkSiteRequestRequestTypeDef",
-    "ListTagsForResourceResponseTypeDef",
-    "PingResponseTypeDef",
     "ActivateDeviceIdentifierResponseTypeDef",
     "DeactivateDeviceIdentifierResponseTypeDef",
     "GetDeviceIdentifierResponseTypeDef",
     "ListDeviceIdentifiersResponseTypeDef",
     "ActivateNetworkSiteRequestRequestTypeDef",
     "ReturnInformationTypeDef",
     "StartNetworkResourceUpdateRequestRequestTypeDef",
     "ConfigureAccessPointRequestRequestTypeDef",
     "CreateNetworkResponseTypeDef",
     "DeleteNetworkResponseTypeDef",
     "GetNetworkResponseTypeDef",
     "ListNetworksResponseTypeDef",
-    "ListDeviceIdentifiersRequestListDeviceIdentifiersPaginateTypeDef",
-    "ListNetworkResourcesRequestListNetworkResourcesPaginateTypeDef",
-    "ListNetworkSitesRequestListNetworkSitesPaginateTypeDef",
-    "ListNetworksRequestListNetworksPaginateTypeDef",
-    "ListOrdersRequestListOrdersPaginateTypeDef",
     "NetworkResourceDefinitionTypeDef",
     "OrderTypeDef",
     "NetworkResourceTypeDef",
     "SitePlanTypeDef",
     "AcknowledgeOrderReceiptResponseTypeDef",
     "GetOrderResponseTypeDef",
     "ListOrdersResponseTypeDef",
@@ -112,25 +112,14 @@
 AcknowledgeOrderReceiptRequestRequestTypeDef = TypedDict(
     "AcknowledgeOrderReceiptRequestRequestTypeDef",
     {
         "orderArn": str,
     },
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
 _RequiredActivateDeviceIdentifierRequestRequestTypeDef = TypedDict(
     "_RequiredActivateDeviceIdentifierRequestRequestTypeDef",
     {
         "deviceIdentifierArn": str,
     },
 )
 _OptionalActivateDeviceIdentifierRequestRequestTypeDef = TypedDict(
@@ -331,24 +320,35 @@
 GetOrderRequestRequestTypeDef = TypedDict(
     "GetOrderRequestRequestTypeDef",
     {
         "orderArn": str,
     },
 )
 
-PaginatorConfigTypeDef = TypedDict(
-    "PaginatorConfigTypeDef",
+_RequiredListDeviceIdentifiersRequestListDeviceIdentifiersPaginateTypeDef = TypedDict(
+    "_RequiredListDeviceIdentifiersRequestListDeviceIdentifiersPaginateTypeDef",
     {
-        "MaxItems": int,
-        "PageSize": int,
-        "StartingToken": str,
+        "networkArn": str,
+    },
+)
+_OptionalListDeviceIdentifiersRequestListDeviceIdentifiersPaginateTypeDef = TypedDict(
+    "_OptionalListDeviceIdentifiersRequestListDeviceIdentifiersPaginateTypeDef",
+    {
+        "filters": Mapping[DeviceIdentifierFilterKeysType, Sequence[str]],
+        "PaginationConfig": "PaginatorConfigTypeDef",
     },
     total=False,
 )
 
+class ListDeviceIdentifiersRequestListDeviceIdentifiersPaginateTypeDef(
+    _RequiredListDeviceIdentifiersRequestListDeviceIdentifiersPaginateTypeDef,
+    _OptionalListDeviceIdentifiersRequestListDeviceIdentifiersPaginateTypeDef,
+):
+    pass
+
 _RequiredListDeviceIdentifiersRequestRequestTypeDef = TypedDict(
     "_RequiredListDeviceIdentifiersRequestRequestTypeDef",
     {
         "networkArn": str,
     },
 )
 _OptionalListDeviceIdentifiersRequestRequestTypeDef = TypedDict(
@@ -363,14 +363,35 @@
 
 class ListDeviceIdentifiersRequestRequestTypeDef(
     _RequiredListDeviceIdentifiersRequestRequestTypeDef,
     _OptionalListDeviceIdentifiersRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListNetworkResourcesRequestListNetworkResourcesPaginateTypeDef = TypedDict(
+    "_RequiredListNetworkResourcesRequestListNetworkResourcesPaginateTypeDef",
+    {
+        "networkArn": str,
+    },
+)
+_OptionalListNetworkResourcesRequestListNetworkResourcesPaginateTypeDef = TypedDict(
+    "_OptionalListNetworkResourcesRequestListNetworkResourcesPaginateTypeDef",
+    {
+        "filters": Mapping[NetworkResourceFilterKeysType, Sequence[str]],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListNetworkResourcesRequestListNetworkResourcesPaginateTypeDef(
+    _RequiredListNetworkResourcesRequestListNetworkResourcesPaginateTypeDef,
+    _OptionalListNetworkResourcesRequestListNetworkResourcesPaginateTypeDef,
+):
+    pass
+
 _RequiredListNetworkResourcesRequestRequestTypeDef = TypedDict(
     "_RequiredListNetworkResourcesRequestRequestTypeDef",
     {
         "networkArn": str,
     },
 )
 _OptionalListNetworkResourcesRequestRequestTypeDef = TypedDict(
@@ -385,14 +406,35 @@
 
 class ListNetworkResourcesRequestRequestTypeDef(
     _RequiredListNetworkResourcesRequestRequestTypeDef,
     _OptionalListNetworkResourcesRequestRequestTypeDef,
 ):
     pass
 
+_RequiredListNetworkSitesRequestListNetworkSitesPaginateTypeDef = TypedDict(
+    "_RequiredListNetworkSitesRequestListNetworkSitesPaginateTypeDef",
+    {
+        "networkArn": str,
+    },
+)
+_OptionalListNetworkSitesRequestListNetworkSitesPaginateTypeDef = TypedDict(
+    "_OptionalListNetworkSitesRequestListNetworkSitesPaginateTypeDef",
+    {
+        "filters": Mapping[Literal["STATUS"], Sequence[str]],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListNetworkSitesRequestListNetworkSitesPaginateTypeDef(
+    _RequiredListNetworkSitesRequestListNetworkSitesPaginateTypeDef,
+    _OptionalListNetworkSitesRequestListNetworkSitesPaginateTypeDef,
+):
+    pass
+
 _RequiredListNetworkSitesRequestRequestTypeDef = TypedDict(
     "_RequiredListNetworkSitesRequestRequestTypeDef",
     {
         "networkArn": str,
     },
 )
 _OptionalListNetworkSitesRequestRequestTypeDef = TypedDict(
@@ -406,24 +448,54 @@
 )
 
 class ListNetworkSitesRequestRequestTypeDef(
     _RequiredListNetworkSitesRequestRequestTypeDef, _OptionalListNetworkSitesRequestRequestTypeDef
 ):
     pass
 
+ListNetworksRequestListNetworksPaginateTypeDef = TypedDict(
+    "ListNetworksRequestListNetworksPaginateTypeDef",
+    {
+        "filters": Mapping[Literal["STATUS"], Sequence[str]],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
 ListNetworksRequestRequestTypeDef = TypedDict(
     "ListNetworksRequestRequestTypeDef",
     {
         "filters": Mapping[Literal["STATUS"], Sequence[str]],
         "maxResults": int,
         "startToken": str,
     },
     total=False,
 )
 
+_RequiredListOrdersRequestListOrdersPaginateTypeDef = TypedDict(
+    "_RequiredListOrdersRequestListOrdersPaginateTypeDef",
+    {
+        "networkArn": str,
+    },
+)
+_OptionalListOrdersRequestListOrdersPaginateTypeDef = TypedDict(
+    "_OptionalListOrdersRequestListOrdersPaginateTypeDef",
+    {
+        "filters": Mapping[OrderFilterKeysType, Sequence[str]],
+        "PaginationConfig": "PaginatorConfigTypeDef",
+    },
+    total=False,
+)
+
+class ListOrdersRequestListOrdersPaginateTypeDef(
+    _RequiredListOrdersRequestListOrdersPaginateTypeDef,
+    _OptionalListOrdersRequestListOrdersPaginateTypeDef,
+):
+    pass
+
 _RequiredListOrdersRequestRequestTypeDef = TypedDict(
     "_RequiredListOrdersRequestRequestTypeDef",
     {
         "networkArn": str,
     },
 )
 _OptionalListOrdersRequestRequestTypeDef = TypedDict(
@@ -444,14 +516,22 @@
 ListTagsForResourceRequestRequestTypeDef = TypedDict(
     "ListTagsForResourceRequestRequestTypeDef",
     {
         "resourceArn": str,
     },
 )
 
+ListTagsForResourceResponseTypeDef = TypedDict(
+    "ListTagsForResourceResponseTypeDef",
+    {
+        "tags": Dict[str, str],
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
+)
+
 _RequiredNameValuePairTypeDef = TypedDict(
     "_RequiredNameValuePairTypeDef",
     {
         "name": str,
     },
 )
 _OptionalNameValuePairTypeDef = TypedDict(
@@ -469,14 +549,43 @@
     "TrackingInformationTypeDef",
     {
         "trackingNumber": str,
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
+PingResponseTypeDef = TypedDict(
+    "PingResponseTypeDef",
+    {
+        "status": str,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
+    },
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
         "resourceArn": str,
         "tags": Mapping[str, str],
     },
 )
@@ -505,62 +614,46 @@
 )
 
 class UpdateNetworkSiteRequestRequestTypeDef(
     _RequiredUpdateNetworkSiteRequestRequestTypeDef, _OptionalUpdateNetworkSiteRequestRequestTypeDef
 ):
     pass
 
-ListTagsForResourceResponseTypeDef = TypedDict(
-    "ListTagsForResourceResponseTypeDef",
-    {
-        "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-PingResponseTypeDef = TypedDict(
-    "PingResponseTypeDef",
-    {
-        "status": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
 ActivateDeviceIdentifierResponseTypeDef = TypedDict(
     "ActivateDeviceIdentifierResponseTypeDef",
     {
         "deviceIdentifier": DeviceIdentifierTypeDef,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeactivateDeviceIdentifierResponseTypeDef = TypedDict(
     "DeactivateDeviceIdentifierResponseTypeDef",
     {
         "deviceIdentifier": DeviceIdentifierTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetDeviceIdentifierResponseTypeDef = TypedDict(
     "GetDeviceIdentifierResponseTypeDef",
     {
         "deviceIdentifier": DeviceIdentifierTypeDef,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListDeviceIdentifiersResponseTypeDef = TypedDict(
     "ListDeviceIdentifiersResponseTypeDef",
     {
         "deviceIdentifiers": List[DeviceIdentifierTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredActivateNetworkSiteRequestRequestTypeDef = TypedDict(
     "_RequiredActivateNetworkSiteRequestRequestTypeDef",
     {
         "networkSiteArn": str,
@@ -639,137 +732,44 @@
     pass
 
 CreateNetworkResponseTypeDef = TypedDict(
     "CreateNetworkResponseTypeDef",
     {
         "network": NetworkTypeDef,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteNetworkResponseTypeDef = TypedDict(
     "DeleteNetworkResponseTypeDef",
     {
         "network": NetworkTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetNetworkResponseTypeDef = TypedDict(
     "GetNetworkResponseTypeDef",
     {
         "network": NetworkTypeDef,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListNetworksResponseTypeDef = TypedDict(
     "ListNetworksResponseTypeDef",
     {
         "networks": List[NetworkTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
-    },
-)
-
-_RequiredListDeviceIdentifiersRequestListDeviceIdentifiersPaginateTypeDef = TypedDict(
-    "_RequiredListDeviceIdentifiersRequestListDeviceIdentifiersPaginateTypeDef",
-    {
-        "networkArn": str,
-    },
-)
-_OptionalListDeviceIdentifiersRequestListDeviceIdentifiersPaginateTypeDef = TypedDict(
-    "_OptionalListDeviceIdentifiersRequestListDeviceIdentifiersPaginateTypeDef",
-    {
-        "filters": Mapping[DeviceIdentifierFilterKeysType, Sequence[str]],
-        "PaginationConfig": PaginatorConfigTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
-    total=False,
 )
 
-class ListDeviceIdentifiersRequestListDeviceIdentifiersPaginateTypeDef(
-    _RequiredListDeviceIdentifiersRequestListDeviceIdentifiersPaginateTypeDef,
-    _OptionalListDeviceIdentifiersRequestListDeviceIdentifiersPaginateTypeDef,
-):
-    pass
-
-_RequiredListNetworkResourcesRequestListNetworkResourcesPaginateTypeDef = TypedDict(
-    "_RequiredListNetworkResourcesRequestListNetworkResourcesPaginateTypeDef",
-    {
-        "networkArn": str,
-    },
-)
-_OptionalListNetworkResourcesRequestListNetworkResourcesPaginateTypeDef = TypedDict(
-    "_OptionalListNetworkResourcesRequestListNetworkResourcesPaginateTypeDef",
-    {
-        "filters": Mapping[NetworkResourceFilterKeysType, Sequence[str]],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListNetworkResourcesRequestListNetworkResourcesPaginateTypeDef(
-    _RequiredListNetworkResourcesRequestListNetworkResourcesPaginateTypeDef,
-    _OptionalListNetworkResourcesRequestListNetworkResourcesPaginateTypeDef,
-):
-    pass
-
-_RequiredListNetworkSitesRequestListNetworkSitesPaginateTypeDef = TypedDict(
-    "_RequiredListNetworkSitesRequestListNetworkSitesPaginateTypeDef",
-    {
-        "networkArn": str,
-    },
-)
-_OptionalListNetworkSitesRequestListNetworkSitesPaginateTypeDef = TypedDict(
-    "_OptionalListNetworkSitesRequestListNetworkSitesPaginateTypeDef",
-    {
-        "filters": Mapping[Literal["STATUS"], Sequence[str]],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListNetworkSitesRequestListNetworkSitesPaginateTypeDef(
-    _RequiredListNetworkSitesRequestListNetworkSitesPaginateTypeDef,
-    _OptionalListNetworkSitesRequestListNetworkSitesPaginateTypeDef,
-):
-    pass
-
-ListNetworksRequestListNetworksPaginateTypeDef = TypedDict(
-    "ListNetworksRequestListNetworksPaginateTypeDef",
-    {
-        "filters": Mapping[Literal["STATUS"], Sequence[str]],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-_RequiredListOrdersRequestListOrdersPaginateTypeDef = TypedDict(
-    "_RequiredListOrdersRequestListOrdersPaginateTypeDef",
-    {
-        "networkArn": str,
-    },
-)
-_OptionalListOrdersRequestListOrdersPaginateTypeDef = TypedDict(
-    "_OptionalListOrdersRequestListOrdersPaginateTypeDef",
-    {
-        "filters": Mapping[OrderFilterKeysType, Sequence[str]],
-        "PaginationConfig": PaginatorConfigTypeDef,
-    },
-    total=False,
-)
-
-class ListOrdersRequestListOrdersPaginateTypeDef(
-    _RequiredListOrdersRequestListOrdersPaginateTypeDef,
-    _OptionalListOrdersRequestListOrdersPaginateTypeDef,
-):
-    pass
-
 _RequiredNetworkResourceDefinitionTypeDef = TypedDict(
     "_RequiredNetworkResourceDefinitionTypeDef",
     {
         "count": int,
         "type": NetworkResourceDefinitionTypeType,
     },
 )
@@ -832,67 +832,67 @@
     total=False,
 )
 
 AcknowledgeOrderReceiptResponseTypeDef = TypedDict(
     "AcknowledgeOrderReceiptResponseTypeDef",
     {
         "order": OrderTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetOrderResponseTypeDef = TypedDict(
     "GetOrderResponseTypeDef",
     {
         "order": OrderTypeDef,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListOrdersResponseTypeDef = TypedDict(
     "ListOrdersResponseTypeDef",
     {
         "nextToken": str,
         "orders": List[OrderTypeDef],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ConfigureAccessPointResponseTypeDef = TypedDict(
     "ConfigureAccessPointResponseTypeDef",
     {
         "accessPoint": NetworkResourceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetNetworkResourceResponseTypeDef = TypedDict(
     "GetNetworkResourceResponseTypeDef",
     {
         "networkResource": NetworkResourceTypeDef,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListNetworkResourcesResponseTypeDef = TypedDict(
     "ListNetworkResourcesResponseTypeDef",
     {
         "networkResources": List[NetworkResourceTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 StartNetworkResourceUpdateResponseTypeDef = TypedDict(
     "StartNetworkResourceUpdateResponseTypeDef",
     {
         "networkResource": NetworkResourceTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 _RequiredCreateNetworkSiteRequestRequestTypeDef = TypedDict(
     "_RequiredCreateNetworkSiteRequestRequestTypeDef",
     {
         "networkArn": str,
@@ -964,54 +964,54 @@
 ):
     pass
 
 ActivateNetworkSiteResponseTypeDef = TypedDict(
     "ActivateNetworkSiteResponseTypeDef",
     {
         "networkSite": NetworkSiteTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 CreateNetworkSiteResponseTypeDef = TypedDict(
     "CreateNetworkSiteResponseTypeDef",
     {
         "networkSite": NetworkSiteTypeDef,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 DeleteNetworkSiteResponseTypeDef = TypedDict(
     "DeleteNetworkSiteResponseTypeDef",
     {
         "networkSite": NetworkSiteTypeDef,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 GetNetworkSiteResponseTypeDef = TypedDict(
     "GetNetworkSiteResponseTypeDef",
     {
         "networkSite": NetworkSiteTypeDef,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 ListNetworkSitesResponseTypeDef = TypedDict(
     "ListNetworkSitesResponseTypeDef",
     {
         "networkSites": List[NetworkSiteTypeDef],
         "nextToken": str,
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
 
 UpdateNetworkSiteResponseTypeDef = TypedDict(
     "UpdateNetworkSiteResponseTypeDef",
     {
         "networkSite": NetworkSiteTypeDef,
         "tags": Dict[str, str],
-        "ResponseMetadata": ResponseMetadataTypeDef,
+        "ResponseMetadata": "ResponseMetadataTypeDef",
     },
 )
```

### Comparing `types-aiobotocore-privatenetworks-2.5.0.post1/types_aiobotocore_privatenetworks.egg-info/PKG-INFO` & `types-aiobotocore-privatenetworks-2.5.1/types_aiobotocore_privatenetworks.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-privatenetworks
-Version: 2.5.0.post1
-Summary: Type annotations for aiobotocore.Private5G 2.5.0 service generated with mypy-boto3-builder 7.13.0
+Version: 2.5.1
+Summary: Type annotations for aiobotocore.Private5G 2.5.1 service generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_privatenetworks/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -33,30 +33,30 @@
 
 <a id="types-aiobotocore-privatenetworks"></a>
 
 # types-aiobotocore-privatenetworks
 
 [![PyPI - types-aiobotocore-privatenetworks](https://img.shields.io/pypi/v/types-aiobotocore-privatenetworks.svg?color=blue)](https://pypi.org/project/types-aiobotocore-privatenetworks)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-privatenetworks.svg?color=blue)](https://pypi.org/project/types-aiobotocore-privatenetworks)
-[![Docs](https://img.shields.io/readthedocs/mypy-boto3-builder.svg?color=blue)](https://mypy-boto3-builder.readthedocs.io/)
+[![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_privatenetworks/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-privatenetworks?color=blue)](https://pypistats.org/packages/types-aiobotocore-privatenetworks)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore.Private5G 2.5.0](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/privatenetworks.html#Private5G)
+[aiobotocore.Private5G 2.5.1](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/privatenetworks.html#Private5G)
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
 [types-aiobotocore-privatenetworks docs](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_privatenetworks/).
 
 See how it helps to find and fix potential bugs:
 
@@ -350,60 +350,60 @@
 
 `types_aiobotocore_privatenetworks.type_defs` module contains structures and
 shapes assembled to typed dictionaries for additional type checking.
 
 ```python
 from types_aiobotocore_privatenetworks.type_defs import (
     AcknowledgeOrderReceiptRequestRequestTypeDef,
-    ResponseMetadataTypeDef,
     ActivateDeviceIdentifierRequestRequestTypeDef,
     DeviceIdentifierTypeDef,
     AddressTypeDef,
     PositionTypeDef,
     CreateNetworkRequestRequestTypeDef,
     NetworkTypeDef,
     DeactivateDeviceIdentifierRequestRequestTypeDef,
     DeleteNetworkRequestRequestTypeDef,
     DeleteNetworkSiteRequestRequestTypeDef,
     GetDeviceIdentifierRequestRequestTypeDef,
     GetNetworkRequestRequestTypeDef,
     GetNetworkResourceRequestRequestTypeDef,
     GetNetworkSiteRequestRequestTypeDef,
     GetOrderRequestRequestTypeDef,
-    PaginatorConfigTypeDef,
+    ListDeviceIdentifiersRequestListDeviceIdentifiersPaginateTypeDef,
     ListDeviceIdentifiersRequestRequestTypeDef,
+    ListNetworkResourcesRequestListNetworkResourcesPaginateTypeDef,
     ListNetworkResourcesRequestRequestTypeDef,
+    ListNetworkSitesRequestListNetworkSitesPaginateTypeDef,
     ListNetworkSitesRequestRequestTypeDef,
+    ListNetworksRequestListNetworksPaginateTypeDef,
     ListNetworksRequestRequestTypeDef,
+    ListOrdersRequestListOrdersPaginateTypeDef,
     ListOrdersRequestRequestTypeDef,
     ListTagsForResourceRequestRequestTypeDef,
+    ListTagsForResourceResponseTypeDef,
     NameValuePairTypeDef,
     TrackingInformationTypeDef,
+    PaginatorConfigTypeDef,
+    PingResponseTypeDef,
+    ResponseMetadataTypeDef,
     TagResourceRequestRequestTypeDef,
     UntagResourceRequestRequestTypeDef,
     UpdateNetworkSiteRequestRequestTypeDef,
-    ListTagsForResourceResponseTypeDef,
-    PingResponseTypeDef,
     ActivateDeviceIdentifierResponseTypeDef,
     DeactivateDeviceIdentifierResponseTypeDef,
     GetDeviceIdentifierResponseTypeDef,
     ListDeviceIdentifiersResponseTypeDef,
     ActivateNetworkSiteRequestRequestTypeDef,
     ReturnInformationTypeDef,
     StartNetworkResourceUpdateRequestRequestTypeDef,
     ConfigureAccessPointRequestRequestTypeDef,
     CreateNetworkResponseTypeDef,
     DeleteNetworkResponseTypeDef,
     GetNetworkResponseTypeDef,
     ListNetworksResponseTypeDef,
-    ListDeviceIdentifiersRequestListDeviceIdentifiersPaginateTypeDef,
-    ListNetworkResourcesRequestListNetworkResourcesPaginateTypeDef,
-    ListNetworkSitesRequestListNetworkSitesPaginateTypeDef,
-    ListNetworksRequestListNetworksPaginateTypeDef,
-    ListOrdersRequestListOrdersPaginateTypeDef,
     NetworkResourceDefinitionTypeDef,
     OrderTypeDef,
     NetworkResourceTypeDef,
     SitePlanTypeDef,
     AcknowledgeOrderReceiptResponseTypeDef,
     GetOrderResponseTypeDef,
     ListOrdersResponseTypeDef,
@@ -430,43 +430,43 @@
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

### Comparing `types-aiobotocore-privatenetworks-2.5.0.post1/types_aiobotocore_privatenetworks.egg-info/SOURCES.txt` & `types-aiobotocore-privatenetworks-2.5.1/types_aiobotocore_privatenetworks.egg-info/SOURCES.txt`

 * *Files identical despite different names*

